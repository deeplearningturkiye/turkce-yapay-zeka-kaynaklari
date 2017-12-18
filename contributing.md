# KATKIDA BULUNMA REHBERİ

## Yeni Kayıt Ekleme

1. [readme.md](https://github.com/deeplearningturkiye/turkce-derin-ogrenme-kaynaklari/blob/master/readme.md) adresinde sayfanın sağ üstünde bulunan **Raw Blame History** butonlarının hemen yanında bulunan **Edit This File** butonuna tıklayın.
![image](https://user-images.githubusercontent.com/12828465/34069164-283c9bae-e253-11e7-8a3d-3d18eb1002cf.png)

2. Sayfada güncelleme yaptıktan sonra, önce en altta bulunan **Propose File Change** butonuna sonra da açılan sayfada **Create Pull Request** butonuna tıklayın.
![image](https://user-images.githubusercontent.com/12828465/34069179-6f2eaea8-e253-11e7-9867-1d473a7e34e5.png)

## Yazım formatı

``` markdown
## ANA KONU BAŞLIĞI

### Alt Konu Başlığı

* [Link'in görüntüleneceği şekil](https://www.icerige.ait/yol/) (Açıklamalar)

```
Girilecek içeriğin formatı yukarıdakine benzer şeklinde olmalıdır.

Açıklamalarda once yazar/sahip adı -varsa- yazılmalıdır.
Eğer içerigin birden fazla yazarı/sahibi var ise ',' ile ayrılmalıdır. 
Söz konusu makale - akademik çalışma ingilizce olarak yayınlanmış ise '""' içerisinde yazardan sonra eklenmelidir.
Söz konusu kaynağa ait olarak kayıt, yayınlanma, baskı tarih ve yeri bilgisi mevcut ise '@' karakteriyle ayrılıp belirtilmelidir.
örneğin (İsim SOYİSİM @ university üniversitesi 2016 mart) gibi.

Video tarzı içeriklerde ek olarak '{}' parametreleri arasında içeriğin dakika bilgisi verilmelidir.

Kitaplar için kitabın aktif olarak satışının yapıldığı kitap hakkında açıklama bilgilerine yer veren bir alışveriş sitesi adresi ya da önizleme versiyonu verilebilir. 

## Sorun Bildirimi (ISSUE Template)

Sorunlu olan kayıtlar için (Kırık link Yanlış isim, ilegal içerik gibi)
[issues](https://github.com/deeplearningturkiye/turkce-yapay-zeka-kaynaklari/issues/new) sayfasından bildirimde bulunabilirsiniz.

Eklenmesini istediğiniz yeni içerikleri Pull Request ile belirtmeniz gereklidir bunun için issue oluşturmayınız.

Eksiklik olan içeriği satır no ile vermeye çalismayınız liste değişebilir. Yada bildirdiğiniz sorun birisi sizin açtığınız konuya bakmadan once (yazım yanlışı gibi) başka biri tarafından düzeltilebilir. Bu yüzden doğrudan 30. satırdaki açıklama yanlış şeklinde bir bildirim yanlıştır.

Yanlış içeriği belirtmek için 

..... ana konu başlığı altındaki ..... alt konusunun içerisindeki 
  "yanlış olan içerik" ..... sorunu bulunmaktadır.
  olması gereken "yeni içerik değeri -eğer çözüm öneriniz varsa-" şeklinde olmalıdır.

Sorun açık bir biçimde belirtilmelidir. Sadece yanlış olmuş şeklinde bir açıklama fazla dikkate alınmayabilir.

Onun yerine kırık link, rar arşivi hasarlı, makale ismi yanlış, web sayfası 9 yıl once yazılmış veya yazarın soy ismi yanlış girilmiş şeklinde ifadeler olmalıdır.

Sorunu düzeltme imkanınız varsa olması gereken içeriği issue altinda belirtiniz.

### MarkDown Desteği
GitHub Tarafından desteklenen içerik stilleri için daha fazla bilgiye 
[Mastering Markdown](https://guides.github.com/features/mastering-markdown/) adresinden ulaşabilirsiniz.


## Genel uyarılar

### Açıklayıcı bir başlık (title) belirtmeye özen gösteriniz.
Örneğin bir birleştirme isteği (pull Request) `Update readme.md` şeklinde varsayılan değer olmamalıdır.

Öncelikli amaç yapay zeka alanındaki türkçe kaynakları toplamak olduğu için bu açıklamalarda da Türkçe kullanılması daha uygun olur. 

### içeriğin kalitesi ve güncelliği

Kaliteli içeriklere daha çok yer verilmesi gerekiyor.

Bu farklı yayınlarda farklı değerlendirilebilir. 
Örneğin sadece Türkçe olduğu için 10 yıl oncesinde yazılmış, 
insanlara eksik ya da artık kullanımda olmayacak kadar hantal olduğu kesinleşmiş algoritmaları tavsiye eden bir kitabi eklememelisiniz.

Eklemek istediğiniz bloğun sürekli yeni makaleler girilen güncel bir blog,

bu bir yazilim deposu (git svn vb repository) ise 
sürdürücüsü (maintainer) tarafından unutulmadığını - terk edilmediğini doğrulamanız gerekir. (genellikle Abonded tagiyle belirtilir)

#### Eksik içerik ön bildirimi
Yetersiz kalitede olan kaynaklarda bunun ayriyeten belirtilmesi gereklidir.

Bu durum kurallandırılamaz tamamen insiyatif dahilindedir. Örneğin formatı biçimlendirilmemiş olan veri setleri gibi.
Doğrudan veriyi kullanmak olanaksıza yakındır öncelikle işlenip tasnif edilmesi gereklidir. Ama geliştirilmek istenen yapay zekanın
samanlıkta iğne bulabiliyor olması gerekliyse çok uygun bir veri seti olabilir.

### Verilen URL'lerin standardı
Sayfanın çalışabilirliği verilen linklerin kırık olmadığını teyit etmemiz gerekir.

Sonradan linkin 400'lü veya 500'lü sayfalara düşmesi gibi bir durumlara karşın aynı linkin archive.org kaydı zaman damgasıyla birlikte 
Pull Request açiklamasında belirtilebilir. 

İlgili kaynağın bulunduğu web sayfasinin güvenirliğinden emin değilseniz virustotal.com üzerinden taratıp sunuc sayfasini Pull Request açıklamasına ekleyebilirsiniz.

Dosya direk indirme linkleri Youtube videoları gibi kaynaklarda archive.org kaydı eklemeye gerek yoktur.

Link kısaltma servislerinden kaçınılmalıdır. 
Bunun gerekçesi link kısaltma servislerinin anlaşılabilirliği düşürmesi ve sayfa yayında olmadığı zamanlarda archive.org gibi sitelerden orjinal kaynağa ulaşılamaması gibi sebeplerdir.

Verilen dosyaların kaynaklarının guvenilir olmasına dikkat edilmelidir. Asla şifre korumalı .rar .zip .tar gibi sıkıştırılmış içerikler ve bu içerikleri paylaşan sayfalar paylaşılmamalıdır.

Eğer kaynak olarak göstereceğiniz dosyanın güvenirliğinden emin değilseniz virustotal.com üzerinden taratabilirsiniz. 
Virustotal uzerinde yapilan tarama işleminin sonucunu -varsa- Pr açıklamasında yazabilirsiniz.

## Yasal Sorumluluklar

Herhangi bir şekilde ücret dahilinde sağlanan içeriklerde (online eğitim serisi, kitap, video gibi) verilecek olan linklendirme
eser sahibinin ya da telif hakları sahip veya sahiplerinin haklarını gözeterek yapılmalıdır.

Korsan içerik satışı yapilan siteler, içeriğin doğrudan indirme linki, kitaplar için pdf indirme adresi, Online eğitim setleri için satın alınmış kullanıcı hesabı bilgileri verilmemelidir. 
