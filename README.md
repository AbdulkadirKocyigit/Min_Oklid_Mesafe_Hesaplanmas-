# 📏 2D Uzayda Öklid Mesafesi Hesaplama Programı

## 🎯 Projenin Amacı
Bu proje, iki boyutlu uzayda verilen noktalar arasındaki Öklid mesafesini hesaplamayı amaçlayan bir Python programıdır. Bu program, belirli bir nokta setindeki tüm nokta çiftleri arasındaki mesafeleri hesaplar ve bu mesafelerden minimum olanı bulur.

## 🧮 Öklid Mesafesi Nedir?
Öklid mesafesi, iki nokta arasındaki en kısa "düz çizgi" mesafesidir. Bu mesafe, Öklid geometrisinde sıklıkla kullanılır ve aşağıdaki formül ile hesaplanır:

\[ d = \sqrt{(x_2 - x_1)^2 + (y_2 - y_1)^2} \]

Bu formül, iki boyutlu uzaydaki (x1, y1) ve (x2, y2) noktaları arasındaki mesafeyi verir.

## 🔄 Program Akışı
1. **Noktaların Tanımlanması:** Program, 2D uzaydaki noktaları temsil eden demetlerden (tuple) oluşan bir `points` listesi kullanır.
2. **Öklid Mesafesi Hesaplama:** Program, her bir nokta çifti arasındaki mesafeyi hesaplayan `euclideanDistance` fonksiyonunu kullanır.
3. **Döngülerle Hesaplama:** Her bir nokta çifti için mesafeler hesaplanır ve `distances` adlı bir listede saklanır.
4. **Minimum Mesafenin Bulunması:** Tüm hesaplanan mesafeler arasından en küçük olanı bulunur ve kullanıcıya gösterilir.

## 🔍 Temel Özellikler
- **Fonksiyonel Yapı:** `euclideanDistance` fonksiyonu, iki nokta arasındaki Öklid mesafesini hesaplar.
- **Döngülerle Hesaplama:** Program, tüm nokta çiftleri arasındaki mesafeleri hesaplamak için döngüler kullanır.
- **Verimli Veri Yapıları:** Noktalar ve mesafeler listelerle saklanır ve işlenir.
- **Kullanıcı Dostu:** Kod, temiz ve anlaşılır bir yapıda yazılmıştır, bu da programın kolayca anlaşılmasını ve kullanılmasını sağlar.

## 🧠 Hesaplama Mantığı
Program, her iki boyutlu nokta çifti arasındaki x ve y koordinatlarındaki farkları hesaplar ve bu farkları kullanarak Öklid mesafesini bulur. Bu mesafeler bir listeye eklenir ve ardından en küçük mesafe bulunur.
