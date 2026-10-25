# G-SMAİL kurulumu

[← Tanıtıma dön](../README.md) · [İndirme sayfası](https://github.com/gokhanbarisboz/G-SMail/releases/latest)

## Windows 64 bit

### Kurulum — önerilen

1. `G-SMail-Setup.exe` dosyasını indirin.
2. G-SMAİL zaten açıksa **Dosya → Uygulamadan çık** ile kapatın.
3. Kurulum dosyasını açın ve ekrandaki adımları tamamlayın.
4. G-SMAİL’i açıp **Hesap ekle** ile hesabınızı bağlayın.

Yeni sürümü eskisini elle kaldırmadan kurabilirsiniz. Mevcut kullanıcı profilindeki hesaplar ve postalar korunur. Önemli geçişlerden önce **Ayarlar → Yedekleme** bölümünden yedek alabilirsiniz.

### Kurulumsuz kullanım

- **Tek dosya:** `G-SMail-Portable.exe` dosyasını açın.

Bu seçenek aynı Windows kullanıcısının posta profilini kullanır. “Portable”, kullanıcı verilerinin otomatik olarak USB bellekte tutulduğu anlamına gelmez.

## Linux 64 bit — önizleme

Hedef dağıtımlar Ubuntu, Linux Mint, Debian ve Pardus’un güncel 64 bit masaüstü sürümleridir. ARM paketi değildir. Paket bütünlüğü doğrulandı; gerçek Linux kurulum ve çalışma testi henüz yapılmadı.

### DEB paketi — önerilen

1. `G-SMail-1.2.34-linux-amd64.deb` dosyasını indirin.
2. Dağıtımınızın Paket Kurucu uygulamasıyla açın.
3. Uygulama menüsünden **G-SMAİL**’i başlatın.

Terminalden kurulum:

```sh
sudo apt install ./G-SMail-1.2.34-linux-amd64.deb
```

Uygulamanın kendisini `sudo` veya root olarak çalıştırmayın.

### Taşınabilir klasör

`G-SMail-1.2.34-linux-x64.tar.gz` arşivini tamamen çıkarın. `G-SMail` klasöründeki `Baslat.sh` dosyasını çalıştırın. Bu paket sistem bağımlılıklarını kurmaz; bir sorunla karşılaşırsanız DEB paketini tercih edin.

### Hesap bilgilerinin saklanması

GNOME Keyring veya KWallet oturumu açık olmalıdır. Güvenli anahtarlık olmadan hesap bilgileri korumasız kaydedilmez. Windows profil klasörünü doğrudan Linux’a kopyalamayın; ilk Linux kullanımında hesaplarınızı yeniden bağlayın.

## İlk açılış

1. Destek ekranını **Uygulamaya devam et** ile kapatın. **Bir daha gösterme** seçeneği sonraki açılışlar için tercihinizi saklar.
2. **Hesap ekle** ile sağlayıcınızı seçin.
3. Gereken bağlantı bilgilerini tamamlayın.
4. **Gönder / Al** ile postalarınızı eşitleyin.
5. İsterseniz tema, imza ve kuralları Ayarlar bölümünden düzenleyin.

## Yardım

[Hesap ve yapay zekâ rehberi](HESAPLAR-VE-YAPAY-ZEKA.md) · [bilgi@gsantral.com.tr](mailto:bilgi@gsantral.com.tr)
