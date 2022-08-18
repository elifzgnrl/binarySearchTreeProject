# binarySearchTreeProject

Bu repo [Kodluyoruz](https://www.kodluyoruz.org/) Front-End Eğitiminde Veri Yapıları ve Algoritmalar dersi için hazırlanmış bir 
Binary-Search-Tree Projesidir.

Merge sort’un özelliği problemi parçalara bölmektir. 

Merge sort’un ana mantığı;
1. Problem küçük parçalara bölünür.
2. Daha küçük parçalara bölünen problemler çözülür.
3. Çözülmüş küçük parçalar tekrar birleştirilir.

Merge Sort için bir örnek olarak [16,21,11,8,12,22] inceleyecek olursak:

Adım 1: [16,21,11,8,12,22]
Adım 2: [16,21,11] [8,12,22] listeyi ikiye böldük.
Adım 3: [16] [21,11] [8, 12] [22] bir ve iki eleman içeren daha küçük parçalara ayırdık. Bir sonraki adımda sıralamaya başlayacağız.
Adım 4: [16] [11,21] [8, 12] [22] ilk ikiliyi kendi içinde sıraladık, diğer ikili sıralı.
Adım 5: [11,16,21] [8,12,22] tüm üçlüler kendi aralarında sıralandı.
Adım 6: [8,11,12,16,22] dizinin tamamı sıralandı!

[https://github.com/elifzgnrl/mergeSort](https://github.com/elifzgnrl/mergeSort)
  
# Contribution
Pull requestler kabul edilir. Büyük değişiklikler için, lütfen önce neyi değiştirmek istediğinizi tartışmak için bir konu açınız.

# License
[MIT](https://choosealicense.com/licenses/mit/)
