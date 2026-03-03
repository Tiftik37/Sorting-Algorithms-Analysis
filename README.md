# Algoritma Analizi ve Sıralama Ödevi

## 1. Insertion Sort Projesi
**Dizi:** [22, 27, 16, 2, 18, 6]

### Sıralama Aşamaları:
1. [22, 27, 16, 2, 18, 6] (Başlangıç)
2. [16, 22, 27, 2, 18, 6] (16 başa eklenir)
3. [2, 16, 22, 27, 18, 6] (2 en başa eklenir)
4. [2, 16, 18, 22, 27, 6] (18 uygun yere eklenir)
5. [2, 6, 16, 18, 22, 27] (6 uygun yere eklenir - Sonuç)

### Analiz:
* **Big-O Gösterimi:** $O(n^2)$
* **Time Complexity (18 sayısı):** Dizi sıralandıktan sonra ([2, 6, 16, 18, 22, 27]) 18 sayısı orta kısımda olduğu için **Average Case** kapsamına girer.

## 2. Selection Sort Projesi
**Dizi:** [7, 3, 5, 8, 2, 9, 4, 15, 6]

### İlk 4 Adım:
1. [2, 3, 5, 8, 7, 9, 4, 15, 6] (En küçük 2 bulundu, 7 ile yer değişti)
2. [2, 3, 5, 8, 7, 9, 4, 15, 6] (En küçük 3 bulundu, zaten yerinde)
3. [2, 3, 4, 8, 7, 9, 5, 15, 6] (En küçük 4 bulundu, 5 ile yer değişti)
4. [2, 3, 4, 5, 7, 9, 8, 15, 6] (En küçük 5 bulundu, 8 ile yer değişti)
