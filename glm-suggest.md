# Emoji Charades - Mobil Oyun Konsepti

## Oyun Özeti
Günlük emoji kombinasyonları ile film, dizi, şarkı, ünlü, yer veya kavram tahmin etme oyunu. Wordle'ın sosyal paylaşım viralliği ile Charades'in eğlencesini birleştiriyor.

## Temel Mekanik

### Günlük Puzzle
- Her gün 1 yeni puzzle (global - herkes aynı puzzle'ı çözer)
- 3-5 emoji ile bir şeyi ifade etme
- Örnek: 🧙‍♂️⚡👓 = Harry Potter
- Örnek: 🚢❄💔 = Titanic
- Örnek: 👑🦁🐒 = The Lion King

### Tahmin Sistemi
- Sınırsız tahmin hakkı (veya 5 hak limiti - A/B test)
- Harf ipuçları (streak ile kazanılır veya izle-ödül)
- Kategori ipucu (film mi? şarkı mı? kişi mi?)

### Streak & Stats
- Günlük oynama streak'i (Wordle gibi bağımlılık)
- İstatistikler: toplam çözülen, en uzun streak, kategorilere göre başarı
- Global leaderboard (haftalık sıfırlanır)

## Viral Potansiyeli

### Paylaşım Özelliği (KRİTİK)
```
Emoji Charades #47
🧙‍♂️⚡👓
✅✅✅✅✅
3 tries
```
- Sonuçlar otomatik görsel kart olarak paylaşılabilir
- Instagram Story formatında hazır şablonlar
- TikTok için animasyonlu çözüm videosu

### Sosyal Kancalar
- "Arkadaşınla yarış" - aynı günün skorunu karşılaştır
- "Bugün kim çözdü?" - arkadaş listesi
- Share to unlock - paylaş → bonus ipucu

### FOMO Elementleri
- Günlük puzzle 24 saat sonra kaybolur (veya archive'da izlenebilir)
- Özel event puzzle'ları (Oscar gecesi, Super Bowl, vb.)
- Rare kategoriler: "Bu hafta sadece 90'lar filmleri"

## Monetization

### Revenue Streams
1. **İpucu Satın Alımı** ($0.99 - 4.99)
   - Harf açma, kategori göster, skip

2. **Premium Subscription** ($4.99/ay)
   - Sınırsız ipucu
   - Archive erişimi
   - Reklamsız
   - Özel tema/emoji pack

3. **Rewarded Ads**
   - İpucu kazanmak için video izle
   - Streak kurtarma için izle

4. **Cosmetic IAP**
   - Özel emoji temaları
   - Profil çerçeveleri
   - Share kartı tasarımları

## Retention Stratejileri

### Günlük Alışkanlık Döngüsü
- Push notification: "Bugünün puzzle'ı hazır! 🔍"
- Streak kaybetme korkusu
- Gece yarısı yeni puzzle (merak)

### İlerleme & Ödül
- Kategori rozetleri (Film Uzmanı, Müzik Guru, vb.)
- Seviye sistemi (XP kazan)
- Weekly challenges (7 gün üst üste tamamla → ödül)

### Sosyal Retention
- Arkadaşlarınızın skorlarını görün
- Global/arkadaş sıralaması
- "Bugün seni geçenler" bildirimi

## İçerik Stratejisi

### Kategoriler
- 🎬 Filmler (klasikler, yeni çıkanlar, yapım yılına göre)
- 📺 Diziler
- 🎵 Şarkılar (global hits, ülke bazlı)
- 🎤 Ünlüler
- 🌍 Yerler (şehirler, ülkeler, mekanlar)
- 🎮 Oyunlar
- 📚 Kitaplar
- 💬 Deyimler/Atasözleri

### İçerik Üretimi
- İlk etap: Manuel küratörlük (kalite önemli)
- Ölçeklendikçe: AI assist + topluluk önerileri
- Ülke lokalizasyonu (Türkiye için Türk film/dizi/şarkılar)

## Teknik Yaklaşım

### MVP Stack (Hızlı piyasaya çıkış için)
- **Frontend**: React Native veya Flutter
- **Backend**: Supabase / Firebase
- **Push**: OneSignal
- **Analytics**: Mixpanel + Amplitude

### Özellik Önceliği
1. Temel oyun mekanikleri
2. Günlük puzzle sistemi
3. Paylaşım özelliği
4. Streak & basit istatistikler
5. Sosyal (arkadaş ekleme, sıralama)
6. Monetization

## Başarı Metrikleri

### North Star
- DAU (Daily Active Users) - günlük oyun bağımlılığı

### Önemli KPI'lar
- Day 1 Retention: >40%
- Day 7 Retention: >20%
- Day 30 Retention: >10%
- Share Rate: >15% (paylaşım viralitesi)
- Streak >7: >30% (bağımlılık)

## Riskler & Çözümler

| Risk | Çözüm |
|------|-------|
| İçerik tükenmesi | Kategori rotasyonu + event'ler |
| Çok kolay/zor | Dynamic difficulty + kategori seçimi |
| Kopyalanma | Güçlü topluluk + ilk mover avantajı |
| Monetization düşük | Premium value prop güçlendirme |

## Lansman Stratejisi

### Soft Launch
- Türkiye + İngiltere (farklı pazarlar test)
- 2-4 hafta veri toplama
- Retention & monetization optimizasyonu

### Global Launch
- Product Hunt featured
- Influencer seeding (TikTok/Instagram)
- ASO optimizasyonu

### Post-Launch
- Haftalık yeni kategoriler
- Aylık özel event'ler
- Topluluk önerileri sistemi

## Son Düşünceler

Emoji Charades, Wordle'ın kanıtlanmış formülünü emoji kültürü ile birleştiriyor. Düşük geliştirme maliyeti, yüksek paylaşılabilirlik ve güçlü günlük alışkanlık döngüsü ile hype olma potansiyeli yüksek.

Anahtar başarı faktörü: Paylaşım görsellerinin ne kadar estetik ve paylaşmaya değer olduğu. İnsanlar "bunu paylaşmak istiyorum" hissetmeli.

**Önerilen İsimler**: Emojinary, Emoji Decode, Guessmoji, Emojimate, Charademoji
