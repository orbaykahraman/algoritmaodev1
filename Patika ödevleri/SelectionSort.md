# ***VERİ YAPILARI VE ALGORİTMA ÖDEVLERİ***


# **PROJE 1**
[22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

Big-O gösterimini yazınız.

Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız

1.Average case: Aradığımız sayının ortada olması
2.Worst case: Aradığımız sayının sonda olması
3.Best case: Aradığımız sayının dizinin en başında olması.
[7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

# **CEVAPLAR**
### **1.Sorunun Cevabı:**
[22,27,16,2,18,6] bu diziden en küçük sayı seçilir ve en baştaki sayı ile yer değiştirilir. Ardından diğer sayılar içinde yer değiştirmeli sıralama işlemi yapılır.
[22,27,16,2,18,6] (n)
[2,27,16,22,18,6] (n-1) 2 ile 22 yer değiştirdi.
[2,6,16,22,18,27] (n-2) 6 ile 27 yer değiştirdi.
[2,6,16,18,22,27] (n-3) 22 ile 18 yer değiştirdi.
[2,6,16,18,22,27] 1 son hali bu olur.
### **2.Sorunun Cevabı:** 
n+(n-1)+(n-2)+(n-3)+...+1 = n.(n+1)/2 = n üssü 2 +n/2. Baskın ifade n² dir. Big-O =(n²)
### **3.Sorunun Cevabı:** 
Sıralama işleminin sonunda 18 sayısı ortada olduğu için cevap Average case'dir.
### **4.Sorunun Cevabı:**
1.Adım: [7,3,5,8,2,9,4,15,6]
2.Adım: [2,3,5,8,7,9,4,15,6] 2 ile 7 yer değiştirdi.
3.Adım: [2,3,4,8,7,9,5,15,6] 4 ile 5 yer değiştirdi.
4.Adım: [2,3,4,5,7,9,8,15,6] 5 ile 8 yer değiştirdi.
