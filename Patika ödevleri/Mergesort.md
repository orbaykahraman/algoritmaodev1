# ***VERİ YAPILARI VE ALGORİTMA ÖDEVLERİ***


# **PROJE 2**
[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız. Big-O gösterimini yazınız.

## **1.Sorunun Cevabı:** 
1.Adım: [16,21,11,8,12,22] ortadan iki gruba ayır.
2.Adım: [16,21,11]-[8,12,22] tekrar 2 ye ayır.
3.Adım: [16,21]-[11]-[8,12]-[22] tekrar 2 ye ayır.
4.Adım: [16]-[21]-[11]-[8]-[12]-[22] bütün elemanlar tek kaldığı için şimdi küçükten büyüğe doğru sıralayıp tekrar birleştiriyoruz.
5.Adım:[11,16,21] ve [8,12,22] sol ve sağ taraftaki kutuların ilk elemanları karşlılaştırılır. Sonra sırasıyla hangi kutudaki numara daha küçükse ona göre dizilir.
6.Adım: [8,11,12,16,21,22] son hali

## **2.Sorunun Cevabı:**
Big-O=O(nlogn)