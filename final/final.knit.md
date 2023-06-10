---
title: "Türkiye'de Eğitim ve Yoksulluk ilişkisi"
author: 
  - Muhammed Daş[^1]
bibliography: ../bibliography/biblio.bib
csl: ../csl/apa-tr.csl
header-includes:
  - \usepackage{polyglossia}
  - \setmainlanguage{turkish}
  - \usepackage{booktabs}
  - \usepackage{caption} 
  - \captionsetup[table]{skip=10pt}
output:
  bookdown::pdf_document2:
    fig_caption: yes
    fig_height: 3
    fig_width: 4
    keep_tex: no
    latex_engine: xelatex
    number_sections: yes
    toc: no
geometry: margin=1in
link-citations: yes
urlcolor: blue
fontsize: 12pt
biblio-style: apalike
abstract: |
  Bu bölümde çalışmanızın özetini yazınız.
---


<!-- ======================================================================= -->
<!-- ============================== NOTLAR ================================= -->
<!-- ======================================================================= -->
[^1]: 20080270, [Github Repo](https://github.com/muhammedddas/deneme.git/muhammedddas/deneme)

# Final Hakkında Önemli Bilgiler

\colorbox{BurntOrange}{GITHUB REPO BAĞLANTINIZI BU DOSYANIN 37. SATIRINA YAZINIZ!}

**Proje gönderimi, Github repo linki ile birlikte ekampus sistemine bir zip dosyası yüklenerek yapılacaktır. Sisteme zip dosyası yüklemezseniz ve Github repo linki vermezseniz ara sınav ve final sınavlarına girmemiş sayılırsınız.**

**Proje klasörünüzü sıkıştırdıktan sonra (`OgrenciNumarasi.zip` dosyası) 9 Haziran 2023 23:59'a kadar *ekampus.ankara.edu.tr* adresine yüklemeniz gerekmektedir.**

\colorbox{WildStrawberry}{Daha fazla bilgi için proje klasöründeki README.md dosyasını okuyunuz.}

# Giriş
Tüm Dünya’da olduğu gibi Türkiye’de de yoksulluk başlıca sorunlardandır. Bununla beraber son yıllarda hızla artan yoksulluk ile birlikte hem ulusal hem de uluslararası düzeyde yoksulluğu önlemek amacıyla çeşitli politikalar uygulanmaktadır. Bunların en başında gösterebileceğimiz eğitim politikaları yer  almaktadır.(@alpaydin2008turkiye) .Bu yüzden proje önerimin araştırma konusu olarak da Türkiye’de eğitim ve yoksulluk arasında ne tür bir ilişki olduğunu incelemeyi seçtim. Proje önerimin veri setini Türkiye İstatistik Kurumu’nun web sitesinden elde ettim. Veri setinde yoksul sayısı ve yoksulluk oranı başlıkları altında Türkiye’de nüfusun eğitim düzeyleri ve okur-yazar olma durumları gibi değişkenler bulunmaktadır. Bununla birlikte yoksulluk riskleri de veri setinde yer almaktadır. Bu veriler 2006-2021 yılları arası incelenmiş olup 50 gözleme dayanmaktadır.
## Çalışmanın Amacı
 Çalışma, Türkiye’de yoksulluğun ve eğitimin birbirleri arasındaki ilişkisini, bu ilişkinin ne tür bir ilişki olduğunu ortaya koymayı ve analiz edebilmeyi konu edinmiştir.
   
   Yoksulluk ve eğitim üzerine birçok çalışma bulunmaktadır. Bu çalışma, bu konu ile ilgili yayınlanmış makaleleri, kitapları, grafikleri ve diğer verileri de inceleyip analize dahil edebilmeyi hedeflemektedir. Bununla birlikte Türkiye gibi gelişmekte olan ülkeleri ve diğer Avrupa ülkelerini de inceleyip veri setinin ortaya koymuş olduğu eğitimin yoksulluğu azaltmadaki etkin rolünü gösterebilmek ve desteklemektir. Bunun sonucunda konu ile ilgili bulunan veriler ışığında bu ilişkiyi incelemek ve istatistiksel analiz yapabilmeyi amaçlamaktadır.
## Literatür 

Eğitim ve yoksulluk araındaki ilişkiyi incelemeden önce kısaca tanımlarını yapmamız gerekir.Yoksulluk mutlak yoksulluk ve göreli yoksulluk olarak ikiye ayrılır. Mutlak yoksulluk, insan varlığının devamı için gerekli olan yiyecek, içecek ve barınma gibi en temel ihtiyaçlarının karşılanamaması durumudur. Göreli yoksulluk ise, insanların temel ihtiyaçlarını karşılayabilmesine rağmen kişisel kaynaklarının yetersizliği nedeniyle toplumun genel refah düzeyinin altında kalması durumudur. Eğitim, her ne kadar görüş birliğine varılan tek bir tanımı olmasa da eğitimi genel olarak, kültürün genç kuşaklara aktarılması ve toplumun varlığını sürdürebilmesi için gerekli sosyal değişimleri yapabilecek yaratıcı kişilerin yetiştirilmesi olarak tanımlamak mümkündür[@ccokgezen2015gelicsmekte].
  
   Literatür incelendiğinde eğitimin yoksulluk üzerinde dramatik bir etkiye sahip olduğu görülmektedir(@bilenkisi2015impact)     
Yoksulluğa sebep olan birçok faktör mevcuttur. Bunlar arasında ön plana çıkanlar ise; ekonomik, işsizlik, göç, cinsiyet ve de eğitimdir. Yoksulluk olgusu tüm yönleriyle incelendiğinde, en önemli nedenin eğitimden kaynaklandığı söylenebilir. Bu bağlamda eğitimin ekonomi ve işsizlikle doğrudan ilişkili olduğu ifade edilebilir.Bu bağlamda söz konusu bireylerin yoksulluğun kısır döngüsüne girmelerine engel olma noktasında alınacak tedbirler ve uygulanacak politikalar hayati önem taşımaktadır. Yoksulluğun nesilden nesille bir miras olarak bırakılmamasın tek yolu ise eğitim seviyesinin yükseltilmesinden geçmektedir [@ocalguncel]
Öte yandan eğitim, insanların ekonomiye ve topluma katılma becerileri kazanmalarına yardımcı olur.Bulguları göz önüne alındığında, eğitim özünde geliri eşit dağıtmak için bir mihenk taşıdır ve yoksullara ekonomik büyümeden daha fazla yararlanma fırsatı sağlar.Bu nedenle eğitim politikaları, örgün ve yaygın eğitime katılımı artırmaya çalışırken, yoksullukla mücadelede önemli bir rol üstlenmeyi hedeflemeli (@bilenkisi2015impact)

  Sonuç olarak, yoksulluk ve eğitim birbiriyle ters orantılıdır.
Aynı zamanda eğitimden yoksulluğa doğru ters nedensellik olabileceği gibi, yoksulluktan eğitime doğru da eşit derecede nedensellik olabilir. Örneğin, eğitime yapılan yatırım, insanların üretkenliğinin yanı sıra ücretleri veya geliri artırarak yoksulluğu azaltır. Ayrıca eğitim, insanların daha etkin üretim yapma kapasitelerini geliştiren bazı gerekli becerileri edinmelerini sağlar. Öte yandan yoksulluk, öğrencilere sağlanan kaynakları etkileyerek eğitimin kalitesini ve eğitime eşit erişimi kısıtlamaktadır[@citak2020causal]

  Yoksulluk nedeniyle bireylerin yetersiz eğitim alması bir yandan yoksulluğu devam ettirici bir etki yaratırken; bir diğer yandan bu bireylerin topluma katkılarının da düşük düzeyde kalmasına neden olarak ülkenin kalkınmasını olumsuz yönde etkilemektedir. Bu nedenle yoksullukla mücadelede eğitim konusu sosyal politika alanında ve ekonomik kalkınmada önemli bir unsuru teşkil etmektedir[@erikli2016gencc]

# Veri 
Bu bölümde çalışmanızda kullandığınız veri setinin kaynağını, ham veri üzerinde herhangi bir işlem yaptıysanız bu işlemleri ve veri seti ile ilgili özet istatistikleri tartışınız. Bu bölümde tüm değişkenlere ait özet istatistikleri (ortalama, standart sapma, minimum, maksimum, vb. değerleri) içeren bir tablo (Tablo \ref{tab:ozet}) olması zorunludur. Tablolarınıza gerekli göndermeleri bir önceki cümlede gösterildiği gibi yapınız. [@perkins:1991]

Analize ait R kodları bu bölümde başlamalıdır. Bu bölümde veri setini R'a aktaran ve özet istatistikleri üreten kodlar yer almalıdır.


```r
library(tidyverse)
library(here)
survey <- read_csv("https://raw.githubusercontent.com/muhammedddas/deneme/main/data/survey.csv")
tibble(expand.grid(Illiterate=c( 'Less than high school', '2011' )))
```

```
## # A tibble: 2 x 1
##   Illiterate           
##   <fct>                
## 1 Less than high school
## 2 2011
```

```r
glimpse(survey)
```

```
## Rows: 48
## Columns: 15
## $ years                               <dbl> 2006, NA, NA, 2007, NA, NA, 2008, ~
## $ `15 age +  Risk of poverty`         <chr> NA, "%50 - 50%", "%60 - 60%", NA, ~
## $ `number of poors {thousand person}` <lgl> NA, NA, NA, NA, NA, NA, NA, NA, NA~
## $ `\nIlliterate...4`                  <chr> NA, "1 969", "2 486", NA, "1 842",~
## $ `\nLiterate with no degree...5`     <chr> NA, "1 004", "1 327", NA, "919", "~
## $ `Less than          high school`    <chr> NA, "3 783", "5 605", NA, "3 392",~
## $ `\nHigh school or equivalent...7`   <chr> NA, "463", "825", NA, "486", "807"~
## $ `\nHigher           education...8`  <dbl> NA, 24, 48, NA, 31, 61, NA, 29, 51~
## $ `poverty rate  %`                   <lgl> NA, NA, NA, NA, NA, NA, NA, NA, NA~
## $ `\nIlliterate...10`                 <dbl> NA, 33, 41, NA, 31, 40, NA, 30, 30~
## $ `\nLiterate with no degree...11`    <dbl> NA, 28, 37, NA, 25, 35, NA, 24, 34~
## $ `\nLess than          high school`  <dbl> NA, 14, 21, NA, 12, 20, NA, 13, 21~
## $ `\nHigh school or equivalent...13`  <dbl> NA, 5, 10, NA, 5, 9, NA, 5, 8, NA,~
## $ `\nHigher           education...14` <dbl> NA, 1, 1, NA, 1, 2, NA, 1, 1, NA, ~
## $ ...15                               <lgl> NA, NA, NA, NA, NA, NA, NA, NA, NA~
```

Rmd dosyasında kod bloklarının bazılarında kod seçeneklerinin düzenlendiğine dikkat edin. 



`echo=FALSE` seçeneği ile kodların türetilen pdf dosyasında görünmesini engelleyin ve sonuçlarınızı tablo halinde rapor edin.

\begin{table}[ht]
\centering
\caption{Özet İstatistikler} 
\label{tab:ozet}
\begin{tabular}{lccccc}
  \toprule
 & Ortalama & Std.Sap & Min & Medyan & Mak \\ 
  \midrule

Higher           education...8 & 172.34 & 142.19 & 24.00 & 122.00 & 538.00 \\ 
   \bottomrule
\end{tabular}
\end{table}


# Yöntem ve Veri Analizi
Bu bölümde veri setindeki bilgileri kullanarak çalışmanın amacına ulaşmak için kullanılacak yöntemleri açıklayın. Derste işlenen/işlenecek olan analiz yöntemlerinden (Hipotez testleri ve korelasyon analizi gibi) çalışmanın amacına ve veri setine uygun olanlar bu bölümde kullanılmalıdır. [@newbold:2003; @ozsoy:2010; @ozsoy:2014]

Örneğin, regresyon analizi gerçekleştiriyorsanız tahmin ettiğiniz denklemi bu bölümde tartışınız. Denklemlerinizi ve matematiksel ifadeleri $LaTeX$ kullanarak yazınız.

$$
Y_t = \beta_0 + \beta_N N_t + \beta_P P_t + \beta_I I_t + \varepsilon_t
$$

Bu bölümde analize ilişkin farklı tablolar ve grafiklere yer verilmelidir. Çalışmanıza uygun biçimde histogram, nokta grafiği (Şekil \@ref(fig:plot) gibi), kutu grafiği, vb. grafikleri bu bölüme ekleyiniz. Şekillerinize de gerekli göndermeleri bir önceki cümlede gösterildiği gibi yapınız.Less than          high school","\nHigh school or equivalent...7





# Sonuç
Bu bölümde çalışmanızın sonuçlarını özetleyiniz. Sonuçlarınızın başlangıçta belirlediğiniz araştırma sorusuna ne derece cevap verdiğini ve ileride bu çalışmanın nasıl geliştirilebileceğini tartışınız.

**Kaynakça bölümü Rmarkdown tarafından otomatik olarak oluşturulmaktadır. Taslak dosyada Kaynakça kısmında herhangi bir değişikliğe gerek yoktur.** 

**_Taslakta bu cümleden sonra yer alan hiçbir şey silinmemelidir._**

\newpage
# Kaynakça {#references}
<div id="refs"></div>

