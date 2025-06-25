# 📝 MNG Airlines SMS Bot

## 🌟 Bot Hakkında
Bu bot, MNG Airlines sunucusu için özel olarak geliştirilmiş bir SMS (sms bomb) sistemidir.

## ✨ Özellikler
- Kullanıcılara hak ekleme/çıkarma
- Hak durumunu görüntüleme
- SMS gönderme işlemleri
- Detaylı log sistemi
- Kullanıcı bildirimleri

## 🔧 Kurulum

### Ön Gereksinimler
- Node.js v21.0.0 veya üzeri
- Discord.js v14
- Croxydb veritabanı

### Kurulum Adımları

2. Gerekli paketleri yükleyin:
```bash
npm install
```

3. Ayarlar dosyasını düzenleyin:
`settings/ayarlar.js` dosyasını kendi sunucu bilgilerinize göre düzenleyin.

4. Botu başlatın:
```bash
node .
```

## ⚙️ Komutlar

### 🛠️ Yönetici Komutları
| Komut | Açıklama | Kullanım |
|-------|----------|---------|
| `/hak-ekle` | Kullanıcıya hak ekler | `/hak-ekle kullanıcı: @Kullanıcı miktar: 5` |
| `/hak-sil` | Kullanıcının haklarını siler | `/hak-sil kullanıcı: @Kullanıcı miktar: 3` |

### 📱 Kullanıcı Komutları
| Komut | Açıklama | Kullanım |
|-------|----------|---------|
| `/sms` | SMS göndermek için kullanılır | `/sms numara: 5001111111 miktar: 500` |
| `/sms-komut-bilgi` | SMS Komutlarını gösterir | `/sms-komut-bilgi` |
| `/info` | Yapımcı Bilgilerini gösterir | `/info` |
| `/ping` | Botun pingini gösterir | `/ping` |
| `/hak-bilgi` | Kullanıcılar Haklarına Bakarlar | `/hak-bilgi` |


## 🔒 Yetki Sistemi
- **Kurucu Rolleri**: `data.Kurucu_Roller` içinde tanımlı roller
- **Yönetici Yetkisi**: `Administrator` iznine sahip kullanıcılar

## 📜 Lisans
Bu proje [MIT Lisansı](LICENSE) altında lisanslanmıştır.

## 📞 İletişim
Sorularınız için: [Discord Sunucumuz](https://discord.gg/h7YAermnyw)

---

> **Not:** Bu bot sadece MNG Airlines sunucusu için özel olarak geliştirilmiştir.

## 📸 Ekran Görüntüleri

### Komutlar
![Komutlar](./img/komutlar.png)

### Hak Yönetimi
| Hak Ekleme | Hak Silme | Hak Bilgisi |
|------------|-----------|-------------|
| ![Hak Ekle](./img/hak-ekle.png) | ![Hak Sil](./img/hak-sil.png) | ![Hak Bilgi](./img/hak-bilgi.png) |

### Log Sistemleri
| Hak Ekleme Logu | Hak Silme Logu | DM Log | Kanal Logu |
|-----------------|---------------|--------|------------|
| ![Hak Ekleme Log](./img/hak-ekleme-log.png) | ![Hak Silme Log](./img/hak-silme-log.png) | ![DM Log](./img/dm-log.png) | ![Kanal Log](./img/kanala-log.png) |

### SMS Sistemi
| SMS Komutu | SMS Bilgi | SMS Gönderim |
|------------|-----------|--------------|
| ![SMS Komut](./img/sms-komut.png) | ![SMS Komut Bilgi](./img/sms-komut-bilgi.png) | ![SMS](./img/sms.png) |

### Diğer
| Bot Bilgi | Ping |
|-----------|------|
| ![Info](./img/info.png) | ![Ping](./img/ping.png) |

# BOTUN ALT YAPISI İÇİN DİSCORD SUNUCUMA GELİN