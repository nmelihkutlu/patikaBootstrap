# BOOTSTRAP - patika.dev - Soru ve Cevapları
>**[patika.dev](https://app.patika.dev/courses/bootstrap) platformu BOOTSTRAP öğrenme amaçlı soruların cevaplanması projesidir.** \
> **Profil için tıklayınız: [app.patika.dev/nmelihkutlu](https://app.patika.dev/nmelihkutlu)**


![](https://raw.githubusercontent.com/nmelihkutlu/patikaBootstrap/main/patikaBootstrap.png)



[Ödev1](#ödev-1) - [Ödev2](#ödev-2) - [Ödev3](#ödev-3)

## Ödev 1

### Soru
Bootstrap Özelliklerini Kullanarak Yaptığımız Siteyi Geliştirelim

Hatırlar mısınız CSS'in ilk ödevinde boynu bükük bir site yapmıştık. Bu site CSS'in özelliklerini kullanan bir müzik aleti satış sitesiydi. Bu siteyi Bootstrap ile tekrar tasarlayacağız.

Sizden Beklediklerimiz
- HTML kısmını önceki ödevden alabilirsiniz fakat baştan yapmanızı öneririz.
- Menüyü koyu renkli olarak düzenleyin. İsterseniz arka plan rengi de verebilirsiniz.
- Ana sayfaya bir jumbotron koyup içeriğinizin açıklamasını yazınız.
- Arka plan rengini #E9ECEF ile değiştirin.
- Ürünlerimiz sayfasında card yapısını kullanın.
- Kullandığınız card yapısını grid sistemin içinde kullanın.
- Ürün card boyutlarının tamamen aynı olduğuna dikkat edin.
- Hakkımızda sayfasını da bir card yapısı içine alın.
- Bootstrap Dökümantasyonu'nu iyi inceleyip farklı elementleri denemeye çalışın.
![](https://github.com/Kodluyoruz/taskforce/blob/bootstrap/bootstrap/odev1/figures/bootstrap.gif?raw=true)

### Cevap

**Dosya için tıklayınız: [index.html](https://github.com/nmelihkutlu/patikaBootstrap/blob/main/index.html)**


## Ödev 2

### Soru
Bootstrap ile Instagram Clone

![](https://github.com/Kodluyoruz/taskforce/raw/main/bootstrap/odev2/figures/instagram.gif)

Yukarıda görmüş olduğunuz şahane yapıyı Kodluyoruz mühendisleri üstün dil CSS ile 6 yıl boyunca Ağrı Dağı eteklerinde geliştirdiler. Büyük acılar, büyük zorluklar sonrası bu muhteşem yapıyı oluşturdular desek tabii ki doğru olmaz. Bootstrap ile sizin için böyle bir yapı geliştirdik ve geliştirme sırası şimdi sizde. Bütün vicdansızlığımızı kullanarak yukarıdaki yapıyı aşağıdakine dönüştürdük ve gerekli düzenlemeleri yaparak bu yapı üzerinde çalışıp bu clone'u tekrar yazmanızı istiyoruz.

![](https://github.com/Kodluyoruz/taskforce/raw/main/bootstrap/odev2/figures/instagrambroken.gif)

Hazırlamış olduğumuz Instagram clone'una [buradan](https://drive.google.com/drive/folders/1hRWmpYpuax4Aqsf_BRKdpDoNUowTpzKe?usp=sharing) ulaşabilirsiniz.

Sizden Beklediklerimiz

- Navbar'ı yukarı sabitleyip sayfayı aşağı kaydırdığınızda hala yukarıda durmasını sağlayın. 
    > fixed-top

- İçerik ile birleşmemesi için body'e padding veriniz.
    > mb-5

- Navbarın height'ı 54 px olmalı ve arkaplan rengi beyaz olmalı.
    > bg-white

    > style="height: 54px;" 

- Navbar'daki elementlerin doğru yerde olmadığını fark ettiniz mi? Öncelikle navbar'ın başındaki logo class'ının içine 192px soldan margin verin.
    >style="margin-left:192px;"

- Arama kısmını d-flex ile ortaya alıp soldan 5 birim margin verin.
    >style="text-align: center; margin-left: 5px;"

- CSS dosyası içindeki ::placeholder kısmının arkaplanına assets klasörü içinde bulunan arama simgesini ekleyin. Ve resmin tekrar etmemesini sağlayın.
    >background-image: url(../assets/search-solid.svg);
    
    >background-repeat: no-repeat;

Clone ödevimizdeki ikonları FontAwesome sitesinden aldık. Daha detaylı bilgi için web sitesini ziyaret edin ve nasıl çalıştığını öğrenin.

- Sağ üstte yer alan menü kısmına soldan 5 birim üstten 2 birim margin verin.
    > ml-5 mt-2 

- Sağ üstte yer alan menü kısmına sayfa sm boyutunda olunca kaybolacak şekilde display verin. Bunun için Bootstrap Display property sayfasını inceleyebilirsiniz.
    > display-sm-none

- İçerik alanı(ortadaki gönderilerin olduğu alan) offset 4 olmalı ve üstten 2 birim margin almalı.
    > offset-4 mt-2

- Class'da belirttiğimiz middlearea içinde maksimum yükseklik 200px olmalı ve bunu important ile yazmalısınız. (important'ın ne olduğunu, ne işe yaradığını henüz bilmiyorsanız bir "Css important nedir?" şeklinde aramanızı ve ne işe yaradığını öğrenmenizi öneririz. Unutmayın parametre vermek bazen istemediğiniz durumlara yol açabilir bilinçli kullanmak gerekir.)
    > style="max-height: 200px !important"

- Bu alanın col'unun default değerini 12, diğer tüm ölçekleri ise 6 olarak ayarlayın. Yani normal boyutta 12, sayfa küçülüp büyüdükçe, boyutuyla oynadıkça 6 ölçek olacak şekilde ayarlayın. (Grid sistemin 12'lik olduğunu hatırlayın)
    > col-12 

- Hikayeler kısmında isimler nasıl resimlerin altına gelecek? (İpucu: Arama kısmında kullandığımız özellik)
İçerik kısmında üç nokta sağda olmalı.

- Beğenme, yorum yapma, paylaşma kısmında border olmamalı.

- Bookmark ikonunun offset'i 7 birim olmalı.

- Card header ve card footer'lar beyaz renk olmalı.

- Yorum paylaş metnini sağa alın.

- Sağ panele verilen alan sizce yeterli mi? Değilse düzeltin.

- Sağ panel için stickysidebar ve rightpanel diye iki class verdiğimizi fark etmişsiniz. Stickysidebar bu panelin sayfayı aşağı kaydırdıkça onun da gelmesini sağlıyor. Bunu sağlamak için için CSS'in position property'sini kullanabilirsiniz. 

- Rightpanel'de de arkaplan rengi beyaz olup kenarlık olmamalı.

- Tümünü gör ve takip et yazılarını sağa alınız.

- Bütün sayfanın arkaplan rengini Instagram'dan alıp uygulayın.

Burada belirtmediğimiz ama gözünüze takılan bir yer olursa orayı da düzeltin. Bu ödev için bol bol Instagram sitesini inspect/incele etmeniz gerekecek.

Buradaki ana amacımız Bootstrap elementlerini kullanarak ve özellikle deneyip yanılarak doğru yöntemi bulmanız. Mükemmel olmasına gerek yok. Unutmayın efektif olması mükemmel olmasından daha önemlidir.

![](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/bootstrap/odev2/figures/arog.jpg)

Hepinize başarılar, kolay gelsin!

### Cevap

**Dosya için tıklayınız: [index.html](https://github.com/nmelihkutlu/patikaBootstrap/blob/main/odev2/index.html)**


## Ödev 3

### Soru
Bootstrap Linkedin Clone

Günümüzde iş hayatının Facebook'u, biznısın göbeği olan Linkedin çok sık kullanılmakta. Eğer bir Linkedin hesabınız yoksa hemen oluşturmanızı öneririz. Network bizim mesleğimizde ekstra daha çok önemli. Bu güzel sitenin muhteşem bir cloneunu Kodluyoruz mühendislerimiz uzun uğraşlar sonucu yapmayı başardı. Karşınızda Koyun Dolly değil Bootstrap Linkedin!

![](https://github.com/Kodluyoruz/taskforce/raw/main/bootstrap/odev3/figures/linkedin.gif)

Yine bir vicdansızlık yaparak size temel olarak vereceğimiz projeyi şuna dönüştürdük.

![](https://github.com/Kodluyoruz/taskforce/raw/main/bootstrap/odev3/figures/garibanlinkedin.gif)

Temel dosyalara [şuradan](https://github.com/Kodluyoruz/taskforce/tree/main/bootstrap/odev3/bootstraplinkedinclone) ulaşabilirsiniz.

- Navbar yukarıya sabitlenmemiş durumda ve kenarlığı yok. Bunları düzeltiniz.

- Logoya soldan boşluk ayarlayınız.

- Arama alanına sağdan boşluk bırakınız ve placeholder'ini düzeltiniz.

- Arama alanı ile menü arasındaki boşluğu ayarlayınız.

- Menülerdeki yazıları ve ikonları ortalayın.

- Ben kategorisini diğer kategori isimleri gibi düzenleyiniz ve profil fotoğrafını düzeltiniz.

- Navbar'da bir değişiklik görüyor musunuz? Navbar'ın yüzüne ne olmuş yahu?

![](https://raw.githubusercontent.com/Kodluyoruz/taskforce/main/bootstrap/odev3/figures/nolmus.jpg)

Biz de onu soruyoruz işte ne olmuş?

- Navbar'ı yukarı sabitleyince fark etmişsinizdir ki içerik biraz yukarıda kalıyor. O yüzden yukarıdan biraz boşluk bırakın.

- İçerik biraz geniş kalmış sanki, toplamak için ne kullanabiliriz? İpucu: Layout

- Responsive yapı için sol panele 2 birim, orta panele 6 birim, sağ panele de 3 birim veriniz. Bütün boyutlarda aynı ölçü geçerli olsun.

- Profil fotoğrafını ortalayın, kenarlığını yuvarlak yapın ve 2 birim beyaz kenarlık verin.

- Yazıları eski haline getiriniz.

- Bu alanda gözünüze çarpan kısımları kendinize göre düzenleyiniz.

- Sayfa bildirimi sayısını sağa alınız.

- En Yeni bölümüne sticky pozisyon verin ve overflowunu görünür yapın. Yukarıdan 4rem mesafe verin.

- Gönderi başlatın placeholderını düzeltiniz.

- Butonlara Bootstrap'ta bulunan düzenlemeyi yapınız.

- Fotoğraf'a #70B5F9, Video'ya #7FC15E, Etkinlik'e #E7A33E, Yazı Yaz'a #F5987E renklerini uygulayın. İpucu: fill

- Posttaki kullanıcı adını üste, meslek title'sını ortaya, post paylaşım süresini aşağı sabitleyiniz. İpucu: align

- inline-css şeklinde yazılan CSS'leri düzenli hale getiriniz.

- Beğenme, kalp ve alkışa margin veriniz.

- Butonlara bootstrap düzenlemesi yapınız.

- Sağ panelde logoların yazıları yanlarında olması lazım. Div yerine ne kullanmak gerekiyor?

- Bugünün en çok izlenen eğitimleri bölümünün genişliğini üstteki gibi ayarlayınız.

- Sağ panelde en alttaki bölüme sticky pozisyon verin ve overflowunu görünür yapın. Yukarıdan 4rem mesafe verin.

- Bu bölümdeki linkler yan yana olmalı.

- Mesajlaşmanın genişliği 300px olmalı, arkaplanı beyaz olmalı.

İçeriğinde çok şey var diye paniğe kapılmayın, sırayla gittiğinizde her şeyin çok seri şekilde geleceğine emin olabilirsiniz.

Hepinize başarılar ve kolay gelsin.



### Cevap

**Dosya için tıklayınız: [index.html](https://github.com/nmelihkutlu/patikaBootstrap/blob/main/linkedin.com-clone/index.html)**


