# Hata Kodları

7159XXX ile başlayan hata kodları Pasinor API kullanımında bankadan dönen hata kodlarını ifade etmektedir. Çok bilinen hata kodları başına 7159 eklenerek yanıt olarak API'den döndürülür. Başında 7159 olmayan hata kodları ise genellikle API validasyon hataları olarak değerlendirilir.

Hata oluşması durumunda API'ye gönderdiğiniz istek Failure olmak ile beraber alt örnekte belirttiğimiz şekilde API'den size bir hata dönecektir.

**Örnek Hata Dönüşü**

```json
{
  "errorCode": "715941",
  "errorGroup": "NOT_SUFFICIENT_FUNDS",
  "errorName": "Error",
  "errorMessage": "Kart limiti yetersiz, yetersiz bakiye"
}
```

Belirli durumlarda, bağlı olduğu banka bazında bazı anahtar/değer çiftleri yetersiz yanıt sağlayabilir.\
\
**Hata Kodları Ayrıntısı**\
Eğer bir hata bankadan dönüyorsa, 7159 ile başlayan hatalar alınır ve hata grubuna göre birçok-çoklu ilişkide olan hatalar, Pasinor tarafından sınıflandırılarak API'den döner. Hata grubuna göre (hata koduna göre değil, mutlaka grubu kullanın) üye iş yeri eşleştirmesi yapabilir veya yanıt olarak dönen mesajı son kullanıcıya gösterebilir. Örneğin, 041 kodu, 'limit yetersiz' anlamına gelir ve 715941 koduyla ve 'NOT\_SUFFICIENT\_FUNDS' grubuyla döner. Tüm liste aşağıdaki gibidir, ayrıca bu işlemleri panelde kırmızı kayıtlar olarak da görebilirsiniz.



**Aşağıdaki liste, en yaygın hata gruplarından oluşmaktadır:**



| errorCode | errorGroup | errorName | errorMessage |
| --------- | ---------- | --------- | ------------ |
|           |            |           |              |
|           |            |           |              |
|           |            |           |              |
