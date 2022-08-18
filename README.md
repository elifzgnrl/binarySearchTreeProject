# binarySearchTreeProject

Bu repo [Kodluyoruz](https://www.kodluyoruz.org/) Front-End Eğitiminde Veri Yapıları ve Algoritmalar dersi için hazırlanmış bir 
Binary-Search-Tree Projesidir.

Binary-Search-Tree ana mantığı;
Binary Search Tree, node’lardan oluşan ve her bir node’un en fazla 2 child node’a sahip olduğu veri yapılarından bir tanesidir.
Node, bir veri yapısının en temel birimidir.
Node’lar veriler içerebilirler ve aynı zamanda diğer nodelar ile aralarında bir bağlantı bulundurabilirler.
Binary Search Treede en üstte bulunan node Root olarak adlandırılır.
Root’tan küçük değere sahip olan node’lar Root’un sol tarafında yer alır
Root’tan büyük değere sahip olan node’lar Root’un sağ tarafında yer alır.

Binary Search Tree’nin Avantajları Nelerdir ?

Binary search tree kullanarak oluşturan bir yapıda, bir elemanı silmek, eklemek veya bulmak gibi işlemler hızlı gerçekleştirilebilir. Burada bir elemanı bulabilmek için tek tek tüm elemanları dolaşmak yerine her seferinde veri setini ikiye bölerek ilerleme sağlanır. Örnek verecek olursak eğer;

Sözlükten bir kelime baktığımızı düşünelim. Sözlüklerde, her kelimenin alfabetik olarak sıralı olduğunu biliyoruz. Aradığımız kelimeyi bulmak için şu iki algoritmayı deneyebiliriz:

A algoritması:

Kitabın en başından başlayarak aradığımız kelimeyi bulana kadar sırasıyla tüm kelimeleri incelemek.
B algoritması:

Kitabın ortasından açıp ilk kelimeye bakmak. Eğer aranan kelime, alfabetik olarak kitabın ortasında bulunan ilk kelimeden büyükse kitabın sağ tarafına, değilse sol tarafına bakmaya devam etmek.
A algoritmasında kelime kelime gideceğimizden dolayı Time complexity değeri O(N)’dir.

Örnek olarak [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını inceleyecek olursak:
İlk rakamdan başlayıp (7), bu rakamın root node olduğunu kabul edelim.

1.Adım: 7' den sonra gelen rakam 5 ve 5, 7' den küçük:

5-7

2.Adım: 3. rakamımız ise 1 ve 1 de 7' n küçük:

1-5-7

3.Adım: 4. rakamımız 8 ve 8, 7'de büyük:

1-5-7-8

4.Adım: 5.rakamımız 3, 7' den küçük:

3-1-5-7-8

5.Adım: 6.rakamımız 6 ve 6, 7' den küçük:

6-3-1-5-7-8

6.Adım: 7.rakamımız 0 ve 0, 7'den küçük:

0-6-3-1-5-7-8

7.Adım: 8.rakamımız 9 ve 9, 7'den büyük:

0-6-3-1-5-7-8-9

8.Adım: 9.rakamımız 4 ve 4, 7'den küçük:

4-0-6-3-1-5-7-8-9

9.Adım: 10.rakamımız 2 ve 2, 7'den küçük:

2-4-0-6-3-1-5-7-8-9

[https://github.com/elifzgnrl/binarySearchTreeProject](https://github.com/elifzgnrl/binarySearchTreeProject)
  
# Contribution
Pull requestler kabul edilir. Büyük değişiklikler için, lütfen önce neyi değiştirmek istediğinizi tartışmak için bir konu açınız.

# License
[MIT](https://choosealicense.com/licenses/mit/)
