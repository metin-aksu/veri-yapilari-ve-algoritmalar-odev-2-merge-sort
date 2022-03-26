# VERİ YAPILARI VE ALGORİTMALAR - ÖDEV 2 - MERGE SORT

[Patika.dev](http://www.patika.dev) Veri yapıları ve algoritmalar dersi - Ödev 2

**SORU :** [16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

**CEVAP :**

    * Bölme kısmı
        - [16,21,11] ------- [8,12,22]
        - [16,21]--[11] ------- [8,12]--[22]
        - [16]--[21]--[11] ------- [8]--[12]--[22]
    * Birleştirme kısmı
        - [16,21]--[11] ------- [8,12]--[22]
        - [16,11,21] ------- [8,12,22]
        - [8,11,12,16,21,22]

    * Big-O Gösterimi : O(n*log(n))
