# Merge-Sort
Merge Sort
# Patika.dev - Veri Yapıları ve Algoritmalar - Merge Sort Projesi Ödevi
>[16,21,11,8,12,22] -> Merge Sort

    Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
    Big-O gösterimini yazınız.

## Cevap
[16,21,11,8,12,22]

### Dizideki tüm elemanlar, tek eleman kalana dek sağa ve sola doğru ikiye bölünür.

>[16,21,11]    [8,12,22]
>>[16,21] [11]        [8,12] [22]
>>>[16] [21]   [11]        [8] [12]  [22]

#### Bu aşamadan sonra tekrar birleşime geçilir.

>[16,21] [11] [8] [12,22]
>>[11,16,21] [8,12,22]
>>>[8,11,12,16,21,22] son birleştirmede dizimizin düzenli son halini elde etmiş oluyoruz.

## Big-O Gösterimi:
Time complexity formülü: O(nLogn) şeklindedir. Her ikiye bölünmüş dizinin birleşim (merge) işlemi için dizinin uzunluğu kadar (n kadar) işlem yapılmıştır. O(nLogn) formülü --> O(6(log6)) şeklinde olacaktır.

[PatikaDev profilim](https://app.patika.dev/resatonur93)
[https://www.patika.dev]
