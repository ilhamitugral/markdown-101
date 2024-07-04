# Paragraf Oluşturma
Paragraf oluşturmak oldukça basittir. Normal bir yazı yazmaya başlayarak bir paragraf oluşturabilirsin.

| Markdown | HTML | Sonuç |
| :-- | :-- | :-- |
| Bu cümle örnek olarak oluşturulmuştur.<br><br>Örnek bir cümle daha. | \<p\>Bu cümle örnek olarak oluşturulmuştur.</p\><br><br>\<p\>Örnek bir cümle daha.</p\> | Bu cümle örnek olarak oluşturulmuştur.<br><br>Örnek bir cümle daha. |

<br>

---

<br>

# Başlık Oluşturma
Başlık oluşturmak için hashtag/kare `#` işareti kullanılır. **Markdown**da 1 ila 6'ya kadar başlık bulunmaktadır. Bu başlıkların oluşturulması aşağıdaki gibidir;

| Markdown | HTML | Sonuç |
| :-- | :-- | :-- |
| \# Başlık 1 | \<h1\>Başlık 1\</h1\> | <h1>Başlık 1</h1> |
| \## Başlık 2 | \<h2\>Başlık 2\</h2\> | <h2>Başlık 2</h2> |
| \### Başlık 3 | \<h3\>Başlık 3\</h3\> | <h3>Başlık 3</h3> |
| \#### Başlık 4 | \<h4\>Başlık 4\</h4\> | <h4>Başlık 4</h4> |
| \##### Başlık 5 | \<h5\>Başlık 5\</h5\> | <h5>Başlık 5</h5> |
| \###### Başlık 6 | \<h6\>Başlık 6\</h6\> | <h6>Başlık 6</h6> |

Başlık kullanırken lütfen aşağıdaki yönergeye dikkat ediniz.

| ✅ Bunu Uygula | ❌ Bunu Uygulama |
| :-- | :-- |
| # Başlık 1 | #Başlık 1 |

Ayrıca bu başlıkları oluşturmak için alternatif yöntemlerde bulunmaktadır. Fakat bu yöntem sadece **Başlık 1** ve **Başlık 2** için geçerlidir.

| Markdown | HTML | Sonuç |
| :-- | :-- | :-- |
| Başlık 1<br>=== | \<h1\>Başlık 1\</h1\> | <h1>Başlık 1</h1> |
| Başlık 2<br>--- | \<h2\>Başlık 2\</h2\> | <h2>Başlık 2</h2> |

<br>

---

<br>

# Eğik Yazı Oluşturma
**Markdown**da eğik diğer adıyla italik yazı yazmak için aşağıdaki gibi kullanabilirsiniz.

| Markdown | HTML | Sonuç |
| :-- | :-- | :-- |
| Örnek \*eğik yazı\* | Örnek \<i\>eğik yazı</i\> | Örnek *eğik yazı* |

Eğik yazı yazarken alternatif bir yöntem daha mevcuttur. O da şu şekilde;

| Markdown | HTML | Sonuç |
| :-- | :-- | :-- |
| Örnek \_eğik yazı\_ | Örnek \<i\>eğik yazı</i\> | Örnek _eğik yazı_ |

> Hatırlatma: Her ne kadar alternatif kullanımı olsa da biz; `*yazı*` biçiminde kullanmanızı tavsiye ederiz.

<br>

---

<br>

# Kalın Yazı Oluşturma
**Markdown**da kalın yazı yazmak için şu şekilde kullanabilirsiniz.

| Markdown | HTML | Sonuç |
| :-- | :-- | :-- |
| Örnek \*\*kalın yazı\*\* | Örnek \<b\>kalın yazı</b\> | Örnek **kalın yazı** |

Eğik yazıda olduğu gibi kalın yazı içinde alternatif bir yöntem daha mevcuttur.

| Markdown | HTML | Sonuç |
| :-- | :-- | :-- |
| Örnek \_\_kalın yazı\_\_ | Örnek \<b\>eğik yazı</b\> | Örnek __eğik yazı__ |

> Hatırlatma: Alternatif kullanımı olsa da `**yazı**` biçiminde kullanmanızı öneririz.

<br>

---

<br>

# Eğik ve Kalın Yazı Oluşturma
**Markdown**da aynı anda hem eğik hemde kalın yazı yazabilirsiniz. Bunun için;

| Markdown | HTML | Sonuç |
| :-- | :-- | :-- |
| Örnek \*\*\*eğik ve kalın yazı\*\*\* | Örnek \<i\>\<b\>eğik ve kalın yazı</b\>\</i\> | Örnek ***eğik ve kalın yazı*** |

Bu yazı içinde alternatif bir kullanım yöntemi mevcuttur.

| Markdown | HTML | Sonuç |
| :-- | :-- | :-- |
| Örnek \_\_\_eğik ve kalın yazı\_\_\_ | Örnek \<i\>\<b\>eğik ve kalın yazı</b\>\</i\> | Örnek ***eğik ve kalın yazı*** |

> Hatırlatma: Alternatif kullanımı olsa da `***yazı***` şeklinde kullanmanızı öneririz. Günümüzde en çok kullanılan yöntem `*` yöntemidir.

<br>

---

<br>

# Üstü Çizili Yazı
Her ne kadar YouTube videosunda üstü çizili şekilde gözükmesede güncelleme sonraı üstü çizili yazı ortaya çıktı. Sanırım **Github**ın düzenleme modu ile alakalı bir durum. Üstü çizili yazı oluşturmak için; `~` işaretini kullanıyoruz.

| Markdown | HTML | Sonuç |
| :-- | :-- | :-- |
| Örnek \~\~üstü çizili\~\~ yazı | Örnek \<s\>üstü çizili</s\> yazı | Örnek ~~üstü çizili~~ yazı |

# Alıntı Yapma
**Markdown** içerisinde bazı önemli noktalar olabilir. Bu noktaları belirtmek için `>` işaretini kullanıyoruz.

| Markdown | HTML | Sonuç |
| :-- | :-- | :-- |
| \> Örnek Not | \<blockquote\>Örnek Not\</blockquote\> | <blockquote>Örnek Not</blockquote> |

| ✅ Bunu Uygula | ❌ Bunu Uygulama |
| :-- | :-- |
| \> Örnek Not | \>Örnek Not |

Ayrıca iç içe kullanımıda mevcuttur. Aşağıdaki gibi kullanabilirsiniz.

| Markdown | HTML | Sonuç |
| :-- | :-- | :-- |
| \> Örnek Not<br>\> \> Bir örnek daha | \<blockquote\><br>Örnek Not<br>\<blockquote>Bir örnek daha\</blockquote><br>\</blockquote> | <blockquote>Örnek Not<blockquote>Bir örnek daha</blockquote></blockquote> |

<br>

---

<br>

# Liste Oluşturma

## Sırasız Liste
Sırasız liste oluşturmak için, `*` veya `-` işaretlerini kullanabiliriz.

| Markdown | HTML | Sonuç |
| :-- | :-- | :-- |
| \* Örnek Liste<br>\* Örnek Liste<br>\* Örnek Liste | \<ul\><br>\<li\>Örnek Liste\</li\><br>\<li\>Örnek Liste\</li\><br>\<li\>Örnek Liste\</li\><br>\</ul\> | <ul><li>Örnek Liste</li><li>Örnek Liste</li><li>Örnek Liste</li></ul> |

Yukarıdaki örnekte `*` yerine `-` kullanarak yine aynı çıktıyı elde edebilirsiniz.

> Liste oluştururken `*` işareti kullanmanızı tavsiye ederiz.

## Sıralı Liste
Sıralı liste için liste başına, `1.`, `2.`, `3.` vb. kullanım yapabilirsiniz.

| Markdown | HTML | Sonuç |
| :-- | :-- | :-- |
| 1. Örnek Liste<br>2. Örnek Liste<br>3. Örnek Liste | \<ol\><br>\<li\>Örnek Liste\</li\><br>\<li\>Örnek Liste\</li\><br>\<li\>Örnek Liste\</li\><br>\</ol\> | <ol><li>Örnek Liste</li><li>Örnek Liste</li><li>Örnek Liste</li></ol> |

**Sıralı liste** oluşturmak için pratik bir yol bulunmaktadır. Aşağıdaki gibi bir kullanım yaptığınızda, **sıralı liste** kullanırken avantajlı duruma geçeceksiniz.

| Markdown | HTML | Sonuç |
| :-- | :-- | :-- |
| 1. Örnek Liste<br>1. Örnek Liste<br>1. Örnek Liste | \<ol\><br>\<li\>Örnek Liste\</li\><br>\<li\>Örnek Liste\</li\><br>\<li\>Örnek Liste\</li\><br>\</ol\> | <ol><li>Örnek Liste</li><li>Örnek Liste</li><li>Örnek Liste</li></ol> |

> Yukarıdaki örnekteki gibi `1.`, `1.` ... gibi kullanmak sizin işinizi kolaylaştırabilir.

<br>

---

<br>

# Kod Bloğu Oluşturma
Kod bloğu, kodu biçimlendirmek ve vurgulamak için kullanılır.

## Tek Satırlık Kod Bloğu
<code>``</code> arasına yazmış olduğunuz kodlar **kod bloğu** olarak algılanır.

| Markdown | HTML | Sonuç |
| :-- | :-- | :-- |
| \`printf("Merhaba Dünya");\` | \<code\>printf("Merhaba Dunya");\<\/code\> | `printf("Merhaba Dunya");`

## Çoklu Satır Kod Bloğu
Aşağıdaki gibi yöntem ile kod bloğu kullandığınızda, çoklu kod bloğu elde edersiniz.

<pre><code>```
    // Kodlar burada olacak.
```</code></pre>

| Markdown | HTML | Sonuç |
| :-- | :-- | :-- |
| \`\`\`<br>echo "Merhaba Dunya";<br>\`\`\` | \<pre\><br>\<code\><br>echo "Merhaba Dunya";<br>\</pre><br>\</code> | <pre><code>echo "Merhaba Dunya";</pre></code>

Çoklu satırlarda, yazmış olduğunuz programlama dilini belirterek daha okunaklı bir görüntü sağlayabilirsiniz.

Bu yöntem için ilk <code>```</code> sonrasında istediğiniz programlama dilinin uzantısını yazarsanız, o dile yönelik derleme işlemi gerçekleşir. Birkaç adet örnek yapalım.

Aşağıdaki gibi `PHP` kodu oluşturalım.
<pre><code>```php
echo "Merhaba Dünya!";
```</code></pre>

Bu yazının çıktısı aşağıdaki gibi olacaktır.

```php
echo "Merhaba Dünya!";
```

Bu sefer `C++` için yapalım.

<pre><code>```c++
#include <iostream>

int main() {
    std::cout << "Merhaba Dunya!" << std::endl;
    return 0;
}
```</code></pre>

`C++` kodunun çıktısı aşağıdaki gibidir;

```c++
#include <iostream>

int main() {
    std::cout << "Merhaba Dunya!" << std::endl;
    return 0;
}
```

> Popüler birçok programlama dili desteklenmektedir.

<br>

---

<br>

# Görsel Ekleme

![Linux Logosu](https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Tux.svg/150px-Tux.svg.png)

Markdown'da görsel eklemek biraz zor olabilir ama kullandıkça eliniz alışacaktır. `![](Resim Yolu)` şeklinde görsellerinizi oluşturabilirsiniz.

| Markdown | HTML | Sonuç |
| :-- | :-- | :-- |
| \!\[](https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Tux.svg/150px-Tux.svg.png) | \<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Tux.svg/150px-Tux.svg.png" alt=""> | ![](https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Tux.svg/150px-Tux.svg.png) |

Görsel oluştururken `[]` içerisine resmin **alternatif metnini** girebilirsiniz. SEO açısından önemli bir konudur.

| Markdown | HTML | Sonuç |
| :-- | :-- | :-- |
| \!\[Linux Logosu](https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Tux.svg/150px-Tux.svg.png) | \<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Tux.svg/150px-Tux.svg.png" alt="Linux Logosu"> | ![Linux Logosu](https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Tux.svg/150px-Tux.svg.png) |

<br>

---

<br>

# Link Ekleme

**Görsel Ekleme** ile aynı şekilde kullanılır. Sadece `![]()` komutunda yer alan ünlem (`!`) işaretini kullanmıyoruz. Yani `[]()` komutu ile linklerinizi oluşturabilirsiniz.

| Markdown | HTML | Sonuç |
| :-- | :-- | :-- |
| \[Google](https://www.google.com.tr) | `<a href="https://www.google.com.tr">Google</a>` | [Google](https://www.google.com.tr) |

**Görsel Ekleme** bölümündeki gibi köşeli parantezler (`[]`) mevcuttur. Bu parantez içerisine yazmış olduğunuz kelime/kelimeler linki işaret edecektir.

## Görsele Link Ekleme

Oldukça fazla bir şekilde kullanmak isteyebilirsiniz. Yöntemi kullanmak biraz zordur ama kullandıkça aşina olabilirsiniz.

| Markdown | HTML | Sonuç |
| :-- | :-- | :-- |
| \[!\[Linux Logosu](https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Tux.svg/150px-Tux.svg.png)](https://linux.org/) | `<a href="https://linux.org"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Tux.svg/150px-Tux.svg.png" alt="Linux Logosu"></a>` | [![Linux Logosu](https://upload.wikimedia.org/wikipedia/commons/thumb/3/35/Tux.svg/150px-Tux.svg.png)](https://linux.org/) |

Bu şekilde görsele tıkladığınızda bir URL açılacaktır.

<br>

---

<br>

# Alt Çizgi Oluşturma

Oldukça basit bir konudur. en az üç tane olacak şekilde yan yana `-` kullandığınızda kalın bir çizgi oluşturur.

| Markdown | HTML | Sonuç |
| :-- | :-- | :-- |
| \-\-\- | \<hr> | <hr> |

Bu şekilde ihtiyaç duyduğunuz alanlarda kullanabilirsiniz.

<br>

---

<br>

# HTML Kullanma

**Markdown**'da bazı durumlarda tablo `HTML` kodlarını kullanmanız gerekebilir. Kendisi her ne kadar `HTML`'i daha kolay hale getirmek olsa da yine de `HTML`'e ihtiyacınız olduğunda `HTML`'i kullanmanıza engel olmuyor.

`HTML`'i kullanmak için direkt ihtiyacınız olan `HTML` etiketlerini girebilirsiniz.

| Markdown | HTML | Sonuç |
| :-- | :-- | :-- |
| \<b>Kalın Yazı\</b> | \<b>Kalın Yazı\</b> | <b>Kalın Yazı</b> |
| \<i>Eğik Yazı\</i> | \<i>Eğik Yazı\</i> | <i>Eğik Yazı</i> |
| \<u>Altı Çizili Yazı\</u> | \<u>Altı Çizili Yazı\</u> | <u>Altı Çizili Yazı</u> |
| \<s>Üstü Çizili Yazı\</s> | \<s>Üstü Çizili Yazı\</s> | <s>Üstü Çizili Yazı</s> |

<br>

---

<br>

# Tablo Ekleme

Tablo ekleme yapısı biraz karışıktır. Dikkatli bir şekilde bakmanız gerekiyor. `HTML` tarafında da kullanımı aynı şekilde zordur.

Aşağıdaki komut ile birlikte basit bir tablo oluşturabilirsiniz.
```md
| No | Ad | Soyad |
| -- | -- | -- |
| 1 | İlhami | Tuğral |
| 2 | Dwayne | Johnson |
| 3 | Jason | Statham |
| 4 | Keanu | Reeves | 
```

Bu tablonun çıktısı aşağıdaki gibidir;

| No | Ad | Soyad |
| - | - | ----- |
| 1 | İlhami | Tuğral |
| 2 | Dwayne | Johnson |
| 3 | Jason | Statham |
| 4 | Keanu | Reeves |

Tabloda satır ve sütun sayısını istediğiniz kadar arttırabilirsiniz. Tablo yapısını anlamak için teorik olarak bakmak yerine kodlara **görsel** bir şekilde bakmanız gerekiyor.

Yukarıda tabloda arada yer alan çizgi (`-`) en az bir tane olmak zorundadır. Dilediğiniz kadar arttırabilirsiniz.

> Kafa karışıklığı olmaması adına `No`, `Ad`, `Soyad` kelime boyutuna bağlı olarak çizgi oluşturmanızı tavsiye ederim.

## Tablo Hizalama

Tablo hizalamak için yine yukarıdaki örneği kullanalım.

Hizalama yapmak için yukarıdaki tabloda gördüğünüz çizgi (`-`) üzerinden işlem yapacağız.

Aşağıdaki yönerge tablo elemanlarının hiza yönlerini gösterecektir.

| Komut | Açıklama |
| -- | -- |
| `:-` | Sola dayalı |
| `:-:` | Ortaya dayalı |
| `-:` | Sağa dayalı |

Örneği daha iyi anlayabilmek için birkaç örnek yapalım.

### Sola Dayalı Tablo

Aşağıdaki komutu girdiğinizde sola hizalı bir tablo oluşacaktır.
```md
| No | Ad | Soyad |
| :- | :- | :----- |
| 1 | İlhami | Tuğral |
| 2 | Dwayne | Johnson |
| 3 | Jason | Statham |
| 4 | Keanu | Reeves |
```

Sonuç aşağıdaki gibidir.

| No | Ad | Soyad |
| :- | :- | :----- |
| 1 | İlhami | Tuğral |
| 2 | Dwayne | Johnson |
| 3 | Jason | Statham |
| 4 | Keanu | Reeves |

### Ortaya Dayalı Tablo

Aşağıdaki komutu girdiğinizde ortalanmış bir tablo oluşacaktır.
```md
| No | Ad | Soyad |
| :-: | :-: | :-----: |
| 1 | İlhami | Tuğral |
| 2 | Dwayne | Johnson |
| 3 | Jason | Statham |
| 4 | Keanu | Reeves |
```

Çıktı aşağıdaki gibidir.

| No | Ad | Soyad |
| :-: | :-: | :-----: |
| 1 | İlhami | Tuğral |
| 2 | Dwayne | Johnson |
| 3 | Jason | Statham |
| 4 | Keanu | Reeves |

### Sağa Dayalı Tablo

Aşağıdaki komutu girdiğinizde sağ tarafa doğru hizalı bir tablo oluşacaktır.
```md
| No | Ad | Soyad |
| -: | -: | -----: |
| 1 | İlhami | Tuğral |
| 2 | Dwayne | Johnson |
| 3 | Jason | Statham |
| 4 | Keanu | Reeves |
```

Yukarıdaki komutun sonuç aşağıdaki gibidir.

| No | Ad | Soyad |
| -: | -: | -----: |
| 1 | İlhami | Tuğral |
| 2 | Dwayne | Johnson |
| 3 | Jason | Statham |
| 4 | Keanu | Reeves |

<br>

---

<br>

# Son

**Markdown** eğitimi kabaca bu şekildeydi. Bu yönergeler ile birlikte kolay bir şekilde **Markdown** yapısına aşina olabilir ve ihtiyaçlarınızı karşılayabilirsiniz.

<br>

---

<br>

# Katkıda Bulunun
Makalede eksik gördüğünüz kısım var ise, bu repositoryi **fork**layın ve gereken değişikliği yapın. Ardından değişikliği bana göndererek kontrol edeyim. Yaptığınız güncelleme mantıklı ise, bu repositoryi güncelleyeyim.

<br>

---

<br>

# İletişim
Herhangi bir sorununuz olması durumunda aşağıdaki linklerden sosyal medya adreslerime ulaşabilirsiniz.

* [YouTube](https://youtube.com/@ilhamitugral)
* [X](https://twitter.com/ilhamitugral)
* [Instagram](https://instagram.com/ilhamitugral)
* [Threads](https://threads.net/@ilhamitugral)
