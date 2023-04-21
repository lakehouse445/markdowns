# Başlangıç Seviyesi HTML Öğrenme Rehberi

HTML (Hypertext Markup Language), web sayfalarını oluşturmak ve düzenlemek için kullanılan standart metin işaretleme dilidir. Bu rehberde, HTML'nin temel yapı taşlarını ve nasıl kullanılacağını öğreneceğiz.

## İçindekiler

1. [HTML nedir?](#html-nedir)
2. [HTML Temel Yapısı](#html-temel-yapısı)
3. [HTML Etiketleri](#html-etiketleri)
4. [HTML Başlıkları](#html-başlıkları)
5. [HTML Paragraflar](#html-paragraflar)
6. [HTML Linkler](#html-linkler)
7. [HTML Resimler](#html-resimler)
8. [HTML Listeler](#html-listeler)
9. [HTML Tablolar](#html-tablolar)
10. [HTML Formlar](#html-formlar)

## HTML nedir?

HTML, web tarayıcıları tarafından yorumlanan ve kullanıcıların gördüğü web sayfalarını oluşturan bir işaretleme dilidir. HTML dosyaları, etiketler (tags) adı verilen özel metinlerle işaretlenmiş düz metinden oluşur. Bu etiketler, tarayıcılara sayfanın yapısı ve görünümü hakkında bilgi sağlar.

HTML öğrenmeye başlamadan önce, bir metin düzenleyiciye ve web tarayıcısına ihtiyacınız olacak. Metin düzenleyici olarak [Notepad++](https://notepad-plus-plus.org/downloads/) veya [Visual Studio Code](https://code.visualstudio.com/download) gibi popüler bir seçenek kullanabilirsiniz. Web tarayıcısı olarak ise Google Chrome, Mozilla Firefox veya Microsoft Edge gibi herhangi bir modern tarayıcı kullanabilirsiniz.

## HTML Temel Yapısı

Her HTML dosyasının temel bir yapıya sahip olması gerekmektedir. İşte tipik bir HTML dosyasının temel yapısı:

```html
<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Belge Başlığı</title>
</head>
<body>

  <!-- İçerik buraya gelecek -->

</body>
</html>
```

- `<!DOCTYPE html>`: Bu satır, dosyanın bir HTML5 belgesi olduğunu belirtir.
- `<html>`: Bu etiket, HTML belgesinin başlangıcını işaretler.
- `<head>`: Bu etiket, sayfanın başlık, meta bilgiler ve CSS gibi ek bilgilerini içerir.
- `<meta charset="UTF-8">`: Bu etiket, belgenin karakter kodlamasının UTF-8 olduğunu belirtir.
- `<title>`: Bu etiket, sayfanın başlığını tanımlar ve tarayıcının sekme başlığında görüntülenir.
- `<body>`: Bu etiket, sayfanın gövdesini ve tüm içeriğini içerir.

## HTML Etiketleri

HTML etiketleri, `<etiket-adı>` ve `</etiket-adı>` şeklinde açılış ve kapanış etiketlerinden oluşur. Aşağıda bazı temel HTML etiketleri ve açıklamaları bulunmaktadır:

- `<p>`: Paragraf etiketi
- `<h1>` - `<h6>`: Başlık etiketleri
- `<a>`: Link etiketi
- `<img>`: Resim etiketi
- `<ul>`: Sırasız liste etiketi
- `<ol>`: Sıralı liste etiketi
- `<li>`: Liste öğesi etiketi
- `<table>`: Tablo etiketi
- `<tr>`: Tablo satırı etiketi
- `<td>`: Tablo hücresi etiketi
- `<form>`: Form etiketi

## HTML Başlıkları

Başlıklar, `<h1>` ile `<h6>` arasında değişen etiketlerle tanımlanır ve metni büyük ve kalın hale getirir. `<h1>` en büyük ve en önemli başlık olup, `<h6>` en küçük ve en az önemli başlıktır.

```html
<h1>En Büyük Başlık (h1)</h1>
<h2>Biraz Daha Küçük Başlık (h2)</h2>
<h3>Daha Küçük Başlık (h3)</h3>
<h4>Çok Küçük Başlık (h4)</h4>
<h5>Çok Çok Küçük Başlık (h5)</h5>
<h6>En Küçük Başlık (h6)</h6>
```

## HTML Paragraflar

Paragraflar, `<p>` etiketi ile tanımlanır ve metni paragraf şeklinde düzenler.

```html
<p>Bu bir paragraftır. Paragraflar, metni düzenli ve okunabilir hale getirir.</p>
```

## HTML Linkler

Linkler, `<a>` etiketi ile tanımlanır ve `href` özelliği ile hedef URL belirtilir. Linkler, kullanıcıların başka sayfalara veya sitelere yönlendirilmesini sağlar.

```html
<a href="https://www.example.com">Bu bir linktir</a>
```

## HTML Resimler

Resimler, `<img>` etiketi ile tanımlanır ve `src` özelliği ile resmin kaynağı belirtilir. Ayrıca `alt` özelliği ile resmin alternatif açıklaması da sağlanabilir.

```html
<img src="resim.jpg" alt="Bir örnek resim">
```

## HTML Listeler

HTML'de iki tür liste bulunur: sırasız liste (`<ul>`) ve sıralı liste (`<ol>`). Her iki liste türünde de liste öğeleri `<li>` etiketi ile tanımlanır.

```html
<ul>
  <li>Sırasız liste öğesi 1</li>
  <li>Sırasız liste öğesi 2</li>
</ul>

<ol>
  <li>Sıralı liste öğesi 1</li>
  <li>Sıralı liste öğesi 2</li>
</ol>
```

## HTML Tablolar

Tablolar, `<table>` etiketi ile tanımlanır. Tablo satırları `<tr>` etiketi ile, tablo hücreleri ise `<td>` etiketi ile tanımlanır.

```html
<table>
  <tr>
    <td>Hücre 1</td>
    <td>Hücre 2</td>
  </tr>
  <tr>
    <td>Hücre 3</td>
    <td>Hücre 4</td>
  </tr>
</table>
```

## HTML Formlar

Formlar, `<form>` etiketi ile tanımlanır ve kullanıcıların veri girişi yapmasını sağlar. Form içindeki giriş alanları, `<input>` etiketi ile tanımlanır ve `type` özelliği ile giriş türü belirtilir.

```html
<form>
  <label for="ad">Ad:</label>
  <input type="text" id="ad" name="ad">
  <br>
  <label for="email">E-posta:</label>
  <input type="email" id="email" name="email">
  <br>
  <input type="submit" value="Gönder">
</form>
```

Bu rehberde, HTML'nin temel yapı taşlarını ve kullanımını öğrendik. HTML öğrenmeye devam etmek için [W3Schools](https://www.w3schools.com/html/) ve [MDN Web Docs](https://developer.mozilla.org/tr/docs/Web/HTML) gibi kaynakları kullanabilirsiniz.
