# Mergesort Projesi
Veri yapıları ve algoritmalar proje ödevi

[16,21,11,8,12,22] -> Merge Sort

Yukarıdaki dizinin sort türüne göre aşamalarını yazınız.
Big-O gösterimini yazınız.

* [16, 21, 11] ve [8, 12, 22] olarak iki parçaya ayırılır.
* [16, 21, 11] parçasını [16, 21] ve [11] olarak iki parçaya ayırılır.
* [16, 21] parçasını sıralanır [16, 21].
* [11] parçasını sıralanır [11].
* [16, 21] ve [11] parçalarını birleştirilir [11, 16, 21].
* [8, 12, 22] parçasını [8, 12] ve [22] olarak iki parçaya ayırırılır.
* [8, 12] parçasını sıralanır [8, 12].
* [22] parçasını sıralanır [22].
* [8, 12] ve [22] parçalarını birleştirilir [8, 12, 22].
* [11, 16, 21] ve [8, 12, 22] parçalarını birleştirilir [8, 11, 12, 16, 21, 22].

* merge sort algoritması için O(n log n)
