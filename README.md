# BOOTSTRAP - patika.dev - Soru ve Cevapları
>**[patika.dev](https://app.patika.dev/courses/bootstrap) platformu BOOTSTRAP öğrenme amaçlı soruların cevaplanması projesidir.** \
> **Profil için tıklayınız: [app.patika.dev/nmelihkutlu](https://app.patika.dev/nmelihkutlu)**


![](https://raw.githubusercontent.com/nmelihkutlu/patikaBootstrap/main/patikaBootstrap.png)



[Ödev1](#ödev-1) - [Ödev2](#ödev-2)

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
