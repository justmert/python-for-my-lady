# python-for-my-lady

## Resources

* [python cheat sheet](https://www.pythoncheatsheet.org/#Python-Basics)
--- 

## Practices

### Level 1 - Number Guessing

Program 1 ile 100 arasında rastgele bir sayı seçsin. Kullanıcı, yaptığı tahminlerle bu sayıyın kaç olduğunu bilmeye çalışacak. Eğer kullanıcı, seçilen sayıdan büyük bir sayı tahmin ederse ekrana 'daha da küçük bir sayı tahmin etmelisin' basmalısın. Eğer kullanıcı, seçilen sayıdan küçük bir sayı tahmin ederse ekrana 'daha da büyük bir sayı tahmin etmelisin' basmalısın. Oyun, kullanıcı, seçilen sayıyı bildiğinde biter.

Örnek: 
Program rastgele bir sayı seçti ve 72 geldi diyelim.
```
Tahmin et: 23

Daha da büyük bir sayı tahmin etmelisin

Tahmin et: 89

Daha da küçük bir sayı tahmin etmelisin

Tahmin et: 72

Bravo! Bildin
```


### Level 2 - Hangman

Adam asmacayı kodla. Kodda, 10 tane kelime tanımla. Program bunlardan birini seçsin ve adam asmaca oyununa başlasın. Bundan sonrasını örnekle açıklamak daha iyi olur.

Örnek:
Kelime, 'kelebek' olsun.

```
kelime: _______ 
harf alayım: b

harika, 1 tane b var

kelime: ____b__
harf alayım: z

hiç z yok. 4 hakkın kaldı

kelime: ____b__
harf alayım: k

harika, 2 tane k var

kelime: k___b_k
harf alayım: k

# bu şekilde devam ediyor
```

### Level 3 - Library

Bir kütüphane uygulaması yap. 'Kitap ekle', 'Kitapları listele' diye iki tane seçenek olsun. Kitap ekle diyince, kitabın ismini istesin. Kullanıcı kitabın ismini girdikten sonra program kitabı bir listeye kaydetsin ki daha sonra 'kitapları listele' seçeneğini seçtiğimde bana bu kitabı gösterebilsin. Ayrıca bu seçenekler bir döngünün içinde olmalı ki ben programdan çıkana kadar bana bu seçenekleri tekrar ve tekrar sunabilsin. Aşağıdaki örnek daha açıklayıcı olabilir.

Örnek:
```
1. kitap ekle
2. kitap listele
ne yapmak istiyorsun: 1

kitabın ismi: Karamazov Kardesler

kitabın eklendi!

1. kitap ekle
2. kitap listele
ne yapmak istiyorsun: 2

* Karamazov Kardeşler


1. kitap ekle
2. kitap listele
ne yapmak istiyorsun: 

# bu şekilde devam ediyor

```

### Level 1 - Email Slicer

Mail adresini ayrıştırabilcek bir uygulama yaz. Her defasında kullanıcıdan bir mail adresi iste ve onu parçalarına ayır

```
mail adresini gir: randomtestmail@gazi.edu.tr

kullanici adi: randomtestmail
domain ismi: gazi.edu.tr
```

### Level 2 - Rock, Paper, Scissors

Bilgisayara karşı taş, kağıt, makas oyunu. Program taş, kağıt ya da makastan birini seçsin ve sen de onu yenmeye çalış. Ayrıca program bir döngünün içinde olsun ki tekrar ve tekrar oynayabilelim

```
3,2,1 
ne seçtin bakıyım: kagıt

ah, ben taş seçmiştim.. sen kazandın

3,2,1
ne seçtin bakıyım: makas

za, ben taş seçmiştim.. ben kazandım
```

### Level 4 - Tic, Tac, Toe

İki kişinin oynadığı tic,tac,toe oyununu kodla. 3x3 bir parmaklığa kullanıcılar sırayla X ve O yerleştirsin. Tic, tac, toe oyununu bildiğini farzedip örnek gösteriyorum. Oyunu kullanıcılardan biri kazandığında, kazananı ekrana bassın ve 'tekrar oynamak ister misiniz?' diye bir seçenek sunulsun. 

```
-------------
|   |   |   | 
-------------
|   |   |   |
-------------
|   |   |   |
-------------
1. kullanıcı oynuyor
Hamle: 2,3

-------------
|   |   |   | 
-------------
|   |   | X |
-------------
|   |   |   |
-------------
2.kullanıcı oynuyor
Hamle: 1,2 

-------------
|   | O |   | 
-------------
|   |   | X |
-------------
|   |   |   |
-------------
1.kullanıcı oynuyor
Hamle: 3,3 

-------------
|   | O |   | 
-------------
|   |   | X |
-------------
|   |   | X |
-------------
2.kullanıcı oynuyor
Hamle: 3,3 

# bu şekilde devam ediyor
```




