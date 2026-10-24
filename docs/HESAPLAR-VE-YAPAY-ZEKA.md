# Hesaplar ve yapay zekâ

[← Tanıtıma dön](../README.md)

## E-posta hesabı ekleme

**Hesap ekle** bölümünden sağlayıcınızı seçin. Kurumsal hesaplarda yönetici izni veya uygulamaya özel şifre gerekebilir.

| Hesap | Bağlantı ve hazırlık |
|---|---|
| Gmail / Google Workspace | Google OAuth veya IMAP + SMTP. Hesap politikasına göre uygulama şifresi gerekir. OAuth için uygun uygulama kaydı ve izinler gerekir. |
| Outlook.com / Microsoft 365 | Microsoft OAuth + Graph. Uygulama kaydı ve hesap/kurum izni gerekir. |
| Yahoo | IMAP + SMTP ve uygulama şifresi. |
| iCloud | IMAP + SMTP ve uygulamaya özel şifre. POP3 kullanılmaz. |
| Zimbra | Kurumunuzun izin verdiği IMAP + SMTP sunucu bilgileri. |
| cPanel / Plesk / diğer sunucular | Sağlayıcınızın verdiği IMAP veya POP3 ve SMTP bilgileri. Webmail adresi posta sunucusu adı olmayabilir. |
| Şirket içi Exchange | Kurum izin veriyorsa IMAP + SMTP. EWS ve ActiveSync entegrasyonu yoktur. |

IMAP’ta klasör ve ileti işlemleri sunucunun desteklediği kapsamda eşitlenir. POP3’te klasör ve okunma işlemleri cihazda kalır. Yerel kurallar G-SMAİL açıkken çalışır; sunucunuzun kural yönetimini değiştirmez.

Bağlantı seçeneklerinin bulunması, tüm sağlayıcıların takvim, kişi rehberi ve diğer servisleriyle eksiksiz entegrasyon veya her hesapta doğrulanmış çalışma anlamına gelmez.

## Yapay zekâ ile metin düzenleme

1. **Ayarlar → Yapay zekâ** bölümünü açın.
2. Sağlayıcınızı seçin. Bölümdeki kurulum rehberini açın.
3. Sağlayıcınızdan aldığınız API anahtarını ilgili alana yapıştırın.
4. Uygun model kodunu seçin veya girin.
5. **Kaydet ve dene** ile bağlantınızı kontrol edin.
6. İleti yazarken **AI Düzenle** düğmesini kullanın ve sonucu inceleyin.

OpenRouter için ücretsiz model seçeneği vardır. Ücretsiz modellerin kota ve kullanılabilirliği sağlayıcıya bağlıdır; sınırsız kullanım garantisi değildir. Ücretli bir model seçildiğinde sağlayıcınızın ücretleri geçerli olabilir.

ChatGPT gibi sohbet abonelikleri API anahtarı yerine geçmez. Düzenleme sırasında seçilen metin ilgili sağlayıcıya gönderilir. Paylaşmak istemediğiniz bilgileri düzenleme isteğine eklemeyin.

## Sorun bildirimi

Sürümü, işletim sistemini, kullandığınız sağlayıcıyı ve gördüğünüz hata mesajını belirtin. Ekran görüntüsünde kişisel bilgileri kapatın; şifre veya API anahtarını paylaşmayın.

İletişim: [bilgi@gsantral.com.tr](mailto:bilgi@gsantral.com.tr)
