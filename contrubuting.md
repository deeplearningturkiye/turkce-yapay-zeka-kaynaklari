# KATKIDA BULUNMA REHBERİ

## Yeni Kayıt Ekleme

1. [readme.md](https://github.com/deeplearningturkiye/turkce-derin-ogrenme-kaynaklari/blob/master/readme.md) adresinde sayfanın sağ üstünde bulunan **Raw Blame History** butonlarının hemen yanında bulunan **Edit This File** butonuna tıklayın.

2. Sayfada güncelleme yaptıktan sonra, önce en altta bulunan **Propose File Change** butonuna sonra da açılan sayfada **Create Pull Request** butonuna tıklayın.

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

Kitaplar için kitabın aktif olarak satışının yapıldığı kitap hakkında açıklama bilgilerine yer veren bir alış veriş sitesi adresi yada ön izleme versiyonu verilebilir. 

## Genel uyarılar

### Açıklayıcı bir başlık (title) belirtmeye özen gösteriniz.
Örneğin bir birleştirme isteği (pull Request) `Update readme.md` şeklinde varsayılan değer olmamalıdır.

Öncelikli amaç yapay zeka alanındaki türkçe kaynakları toplamak olduğu için bu açıklamalarda da türkçe kullanılması daha uygun olur. 

### içeriğin kalitesi ve güncelliği

Kaliteli içeriklere daha çok yer verilmesi gerekiyor.

Bu farklı yayınlarda farklı değerlendirilebilir. 
Örneğin sadece türkçe olduğu için 10 yıl oncesinde yazılmış, 
insanlara eksik yada artık kullanımda olmayacak kadar hantal olduğu kesinleşmiş algoritmaları tavsiye eden bir kitabi eklememelisiniz.

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

Sonradan linkin 400lü veya 500lü sayfalara düşmesi gibi bir durumlara karşın aynı linkin archive.org kaydı zaman damgasıyla birlikte 
Pull request açiklamasında belirtilebilir. 

Ilgili kaynağın bulunduğu web sayfasinin güvenirliğinden emin değilseniz virustotal.com üzerinden taratıp sunuc sayfasini pull request açıklamasına ekleyebilirsiniz.

Dosya direk indirme linkleri youtube videoları gibi kaynaklarda archive.org kaydı eklemeye gerek yoktur.

Link kısaltma servislerinden kaçınılmalıdır. 
Bunun gerekçesi link kısaltma servislerinin anlaşılabilirliği düşürmesi ve sayfa yayında olmadığı zamanlarda archive.org gibi sitelerden orjinal kaynağa ulaşılamaması gibi sebeplerdir.

Verilen dosyaların kaynaklarının guvenilir olmasına dikkat edilmelidir. Asla şifre korumalı .rar .zip .tar gibi sıkıştırılmış içerikler ve bu içerikleri paylaşan sayfalar paylaşılmamalıdır.

Eğer kaynak olarak göstereceğiniz dosyanın güvenirliğinden emin değilseniz virustotal.com üzerinden taratabilirsiniz. 
Virustotal uzerinde yapilan tarama işleminin sonucunu -varsa- Pr açıklamasında yazabilirsiniz.

## Yasal Sorumluluklar

Herhangi bir şekilde ücret dahilinde sağlanan içeriklerde (online eğitim serisi, kitap, video gibi) verilecek olan linklendirme
eser sahibinin yada telif hakları sahip veya sahiplerinin haklarını gözeterek yapılmalıdır.

Korsan içerik satışı yapilan siteler, içeriğin doğrudan indirme linki, kitaplar için pdf indirme adresi, Online eğitim setleri için satın alınmış kullanıcı hesabı bilgileri verilmemelidir. 
