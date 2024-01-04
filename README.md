Ödev 1:

Soru: [22,27,16,2,18,6] -> Insertion Sort

Yukarı verilen dizinin sort türüne göre aşamalarını yazınız.

1. [*22,* 27, 16, 2, 18, 6]
2. [*22, 27,* 16, 2, 18, 6]
3. [*16, 22, 27,* 2, 18, 6]
4. [*2, 16, 22, 27,* 18, 6]
5. [*2, 16, 18, 22, 27,* 6]
6. [*2, 6, 16, 18, 22, 27*]

Soru: Big-O gösterimini yazınız. 
Insertion Sort'un en kötü durumdaki zaman karmaşıklığı O(n^2)'dir.

Soru: Time Complexity: Dizi sıralandıktan sonra 18 sayısı aşağıdaki case'lerden hangisinin kapsamına girer? Yazınız
18 sayısı dizinin ortasında yer alırsa, arama işlemi için her seferinde diziyi yarıya indirerek devam edebiliriz. Bu durumda time complexity O(log n) olacaktır.
Average Case: Aramak istediğimiz sayı dizinin ortasında olduğunda, average case için time complexity O(n log n) olabilir. Ancak, Insertion Sort'un kendi sıralama algoritması O(n^2) olduğu için bu durum pek uygundur.
Worst Case: Aramak istediğimiz sayı dizinin sonunda olduğunda, worst case için time complexity O(n) olacaktır, çünkü tüm diziyi kontrol etmemiz gerekecek.
Best Case: Aramak istediğimiz sayı dizinin başında olduğunda, best case için time complexity yine O(n) olacaktır, çünkü en iyi durumda bile tüm diziyi kontrol etmemiz gerekecek.

Soru: [7,3,5,8,2,9,4,15,6] dizisinin Selection Sort'a göre ilk 4 adımını yazınız.

Dizi: [7, 3, 5, 8, 2, 9, 4, 15, 6]

[2, 3, 5, 8, 7, 9, 4, 15, 6]
[2, 3, 5, 8, 7, 9, 4, 15, 6]
[2, 3, 4, 8, 7, 9, 5, 15, 6]
[2, 3, 4, 5, 7, 9, 8, 15, 6]

Ödev 2:

Soru: [16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.

[16, 21, 11] | [8, 12, 22]
[16] | [21, 11] || [8] | [12, 22]
[16] | [21] | [11] || [8] | [12] | [22]
[16, 21] | [11] || [8, 12] | [22]
[11, 16, 21] || [8, 12, 22]
[8, 11, 12, 16, 21, 22]

Soru: Big-O gösterimini yazınız.
Merge Sort'un zaman karmaşıklığı O(n log n)'dir.
