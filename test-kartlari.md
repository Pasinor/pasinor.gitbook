# Test Kartları

{% hint style="success" %}
**Üye İş Yeri Test Ortam Adresi:** [https://api-sandbox.pasinor.com](https://api-sandbox.pasinor.com/)
{% endhint %}

Pasinor test geliştirme ortamında kullanabilmeniz için size 3 farklı grupta kart sağlamaktadır.&#x20;

* <mark style="color:purple;">Başarılı Yanıt Veren Kartlar</mark>
* <mark style="color:purple;">Hata Üreten Kartlar</mark>
* <mark style="color:purple;">Yabancı Kartlar</mark>

{% hint style="danger" %}
Sandbox ortamında sadece "**Test Kartları**" kullanılmaktadır. Gerçek kart bilgileri test ortamında çalışmamaktadır.
{% endhint %}

**Başarılı Yanıt Veren Kartlar**\
<mark style="color:green;">Başarılı</mark> bir 3DS, NON-3DS durumunu test etmeniz için Debit/Credit bilgileri.

| Kart Numarası    | Banka                 | Kart Tipi            |
| ---------------- | --------------------- | -------------------- |
| 5890040000000016 | Akbank                | Master Card (Debit)  |
| 5526080000000006 | Akbank                | Master Card (Credit) |
| 4766620000000001 | Denizbank             | Visa (Debit)         |
| 4603450000000000 | Denizbank             | Visa (Credit)        |
| 4987490000000002 | Finansbank            | Visa (Debit)         |
| 5311570000000005 | Finansbank            | Mastercard (Credit)  |
| 9792020000000001 | Finansbank            | Troy (Debit)         |
| 9792030000000000 | Finansbank            | Troy (Credit)        |
| 5170410000000004 | Garanti Bankası       | Master Card (Debit)  |
| 5400360000000003 | Garanti Bankası       | Master Card (Credit) |
| 374427000000003  | Garanti Bankası       | American Express     |
| 4475050000000003 | Halkbank              | Visa (Debit)         |
| 5528790000000008 | Halkbank              | Master Card (Credit) |
| 4059030000000009 | HSBC Bank             | Visa (Debit)         |
| 5504720000000003 | HSBC Bank             | Master Card (Credit) |
| 5892830000000000 | Türkiye İş Bankası    | Master Card (Debit)  |
| 4543590000000006 | Türkiye İş Bankası    | Visa (Credit)        |
| 4910050000000006 | Vakıf Bank            | Visa (Debit)         |
| 4157920000000002 | Vakıf Bank            | Visa (Credit)        |
| 5168880000000002 | Yapı ve Kredi Bankası | Master Card (Debit)  |
| 5451030000000000 | Yapı ve Kredi Bankası | Master Card (Credit) |



**Yabancı Kartlar**\
<mark style="color:green;">Başarılı</mark> bir 3DS, NON-3DS durumunu test etmeniz için kullanmanız gereken kartlar.

| Kart Numarası    | Ülke                 |
| ---------------- | -------------------- |
| 5400010000000004 | Non-Turkish (Credit) |
| 4054180000000007 | Non-Turkish (Debit)  |
| 6221060000000004 | Iran                 |



**Hata Üreten Kartlar**\
<mark style="color:red;">Başarısız</mark> bir 3DS, NON-3DS durumunu test etmeniz için Debit/Credit bilgileri.

| Kart Numarası    | Hatalar                                              |
| ---------------- | ---------------------------------------------------- |
| 5406670000000009 | Success but cannot be cancelled, refund or post auth |
| 4111111111111129 | Not sufficient funds                                 |
| 4129111111111111 | Do not honour                                        |
| 4128111111111112 | Invalid transaction                                  |
| 4128111111111113 | Lost card                                            |
| 4128111111111114 | Stolen card                                          |
| 4128111111111115 | Expired card                                         |
| 4128111111111116 | Invalid cvc2                                         |
| 4128111111111117 | Not permitted to card holder                         |
| 4128111111111118 | Not permitted to terminal                            |
| 4128111111111119 | Fraud suspect                                        |
| 4120111111111110 | Pickup card                                          |
| 4130111111111118 | General error                                        |
| 4130111111111117 | Success but mdStatus is 0                            |
| 4141111111111115 | Success but mdStatus is 4                            |
| 4151111111111112 | 3dsecure initialize failed                           |



#### **BKM Test Bilgileri**

|                | BKM Express Test Hesap Bilgileri |
| -------------- | -------------------------------- |
| Kullanıcı Adı  | isyeri@bkm.com                   |
| Şifre          | 147258                           |
| Doğrulama Kodu | 123456                           |

<pre class="language-markup" data-overflow="wrap" data-full-width="false"><code class="lang-markup"><strong>Bu bilgilerin sadece Pasinor test geliştirme ortamında kullanılması gerektiğini unutmayın. Gerçek işlemler için gerçek kart bilgileri kullanılmalıdır.
</strong></code></pre>
