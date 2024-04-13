---
description: >-
  Geliştirici Ortamına hoş geldiniz! Sizi burada ağırlamak bizim için büyük bir
  zevk olacaktır. Geliştirici dökümanımız ile ilgili öneri ve fikirlerinizi bize
  ulaştırabilirsiniz -> arge@pasinor.com
---

# Başlangıç

Finansal teknolojilerin getirdiği olanakları keşfetmeye ve işletmelerin ve bireylerin finansal işlemlerini kolaylaştırmaya olan tutkumuz ile buradayız. Herhangi bir aidat ücreti olmaksızın tamamen ücretsiz bir şekilde sizlere Sanal Pos, Fiziki Pos, Android ve Mobil Pos ve benzer çözümler sunmaktayız.

**Pasinor ile ödeme süreci şu şekilde işler:**&#x20;

Son kullanıcı, ürün veya hizmetin sergilendiği web sitesine erişir ve satın almak istediği ürün veya hizmeti seçer. Ödeme formunu doldurur (API) veya ortak ödeme sayfasına (iframe veya link ile ödeme) yönlendirilir. Son kullanıcı Pasinor'a herhangi bir üyelik oluşturmadan ödemesini tamamlar. Ödeme işlemi, güvenlik altyapısı tarafından doğrulanarak onaylanır ve müşteriye ödemenin güvenli ve başarılı olduğu bilgisi verilir. Sonrasında, web sitesi son kullanıcıya ürün veya hizmeti sunar ve Pasinor kullanıcısı üye iş yeri ödemesini valör süresi sonunda en iyi komisyon oranı ile kayıtlı IBAN hesabına alır.



{% tabs %}
{% tab title="Canlı Ortam Adresi" %}
https://api.pasinor.com
{% endtab %}

{% tab title="Üye İşyeri Test Ortamı Adresi" %}
https://api-sandbox.pasinor.com
{% endtab %}
{% endtabs %}

İşte Pasinor Geliştirici Ortamında başlangıç yapmanızı sağlayacak bir kaç ipucu



<table data-view="cards"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td></td><td><a href="hazirlik-asamasi/">Hazırlık Aşaması</a></td><td></td></tr><tr><td></td><td><a href="test-kartlari.md">Test Kartları</a></td><td></td></tr><tr><td></td><td><a href="hata-kodlari.md">Hata Kodları</a></td><td></td></tr><tr><td><a href="oedeme-stratejileri/3ds.md">3DS Ödeme</a></td><td></td><td></td></tr><tr><td><a href="oedeme-stratejileri/non-3ds.md">NON-3DS Ödeme</a></td><td></td><td></td></tr><tr><td><a href="oedeme-stratejileri/oedeme-formu-iframe.md">Iframe Ödeme</a></td><td></td><td></td></tr><tr><td></td><td><a href="desteklenen-platformlar/acik-kaynak/">Açık Kaynak</a></td><td></td></tr><tr><td></td><td><a href="desteklenen-platformlar/hazir-altyapilar/">Hazır Altyapılar</a></td><td></td></tr><tr><td></td><td><a href="sik-sorulan-sorular.md">Sıkça Sorulan Sorular</a></td><td></td></tr></tbody></table>



Her ne tür bir projede olursanız olun, Pasinor Geliştirici Ortamı, çevrimiçi ve fiziki ödemeleri işinize dahil etmenin kolaylığını sunar. E-ticaret platformlarından mobil uygulamalara ve abonelik hizmetlerine kadar, işiniz için bir ağ geçidi görevi görür. Tek bir yapı üzerinden tüm ödemelerinizi yönetmenize ve finansal özgürlük adımı atmanıza olanak tanır.

Pasinorlu olduğunuz için size teşekkür ederiz, ihtiyacınız olan her türlü konuda size yardımcı olmak için elimizden gelen gayreti göstereceğiz ve sizi yanlız bırakmayacağız. Sizi desteklemek için sabırsızlanıyoruz.



**LÜTFEN DİKKAT!**&#x20;

Servislerimiz, PCI-DSS gereklilikleri uyarınca yalnızca TLS 1.2 ve üzeri protokolleri kullanmaya izin vermektedir. Lütfen uygulamanızın Pasinor URL'sine POST işlemlerini bu protokoller üzerinden gerçekleştirdiğinden emin olunuz. Aksi takdirde, 'Bağlantı kapatılacak veya Connection Closed' şeklinde hata mesajları alabilirsiniz.
