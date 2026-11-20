# f3nri marka kiti

<p align="center"><img src="social/x-banner-1500x500.png" alt="f3nri_ — research · tools · intel" width="100%"></p>

**f3nri**: siber güvenlik araştırma ve araç geliştirme ekibi.
Okunuşu: "fenri". Kökeni: İskandinav mitolojisindeki zincir kıran kurt Fenrir.
Slogan satırı: `research · tools · intel`

---

## Klasörler

| Klasör | İçerik |
|---|---|
| `logo/` | İşaret (sembol): SVG ve PNG, 3 renk; favicon; orijinal çizim |
| `wordmark/` | Yazı logosu ve işaret + yazı birleşimleri (lockup), koyu ve açık zemin |
| `social/` | Profil fotoğrafı, GitHub avatarı, X ve LinkedIn banner, link önizleme (OG) görseli |
| `colors/` | Renk paleti görseli, `tokens.css`, `palette.json` |
| `fonts/` | Marka fontları (TTF) ve OFL lisansları |

---

## Logo

**İşaret:** tek bir vektör, her boyutta aynı çizim.
- Varsayılan: **Neon** (`#F2A1FF`) işaret, **Void** (`#0B0710`) zemin üzerinde.
- Açık zemin: **Void** renkli işaret (`f3nri-mark-void`).
- Fotoğraf ya da renkli zemin: **Bone** renkli işaret (`f3nri-mark-bone`).
- En küçük kullanım: 32 px. 16 px'te (favicon) sadece silüet görünür, bu normal.
- İşaretin etrafında, işaret genişliğinin en az %10'u kadar boşluk bırak.

**Yazı logosu:** `f3nri_`, JetBrains Mono ExtraBold.
- `f3nri` Bone (koyu zeminde) veya Void (açık zeminde).
- Alt çizgi `_` her zaman vurgu renginde: koyu zeminde **Neon**, açık zeminde **Amethyst**.
- Harf aralığı: -0.03em.

**Lockup:** işaret solda, yazı sağda. Ana kullanım `f3nri-lockup-koyu-zemin`.

**labs eki (opsiyonel):** `f3nri_ labs`, JetBrains Mono Italic, Neon. Sadece logonun ikincil versiyonu olarak kullanılır. Domain, kullanıcı adı ve handle'larda geçmez. Karşılaştırma: `wordmark/karsilastirma-labs-var-yok.png`.

**Yapma:**
- İşareti döndürme, gerdirme, gölge ya da parlama efekti ekleme.
- Paletteki renkler dışında bir renge boyama.
- Yazı logosunu başka bir fontla yeniden yazma.
- Neon işareti açık zemine koyma (kontrast yetersiz kalır).

---

## Renkler

| Ad | Hex | Kullanım |
|---|---|---|
| Void | `#0B0710` | Zemin |
| Obsidian | `#16101E` | Kart ve yüzey |
| Seam | `#2A2135` | Çizgi ve kenarlık |
| Neon | `#F2A1FF` | Marka rengi, vurgu |
| Amethyst | `#7B2CBF` | Buton, açık zeminde vurgu |
| Bone | `#EDE6F2` | Ana metin |
| Ash | `#9A92AC` | İkincil metin |
| Signal | `#FF6B8B` | Uyarı, kritik bulgu (az kullan) |

Kontrast (Void zemin üzerinde): Bone 16.4:1, Neon 10.8:1, Ash 5.8:1, Signal 7.4:1. Amethyst buton üzerinde Bone metin 5.8:1. Hepsi WCAG AA'yı geçer.

---

## Tipografi

| Rol | Font | Ağırlık |
|---|---|---|
| Yazı logosu | JetBrains Mono | ExtraBold (800) |
| Başlık | Unbounded | Bold (700) |
| Gövde metni | Inter | Regular (400), SemiBold (600) |
| Kod, CLI, IOC | JetBrains Mono | Regular (400) |

Fontların hepsi SIL Open Font License 1.1 ile lisanslı: ticari kullanım serbest. Kurmak için `fonts/` içindeki `.ttf` dosyalarına sağ tıkla, "Yükle"yi seç.
Web için Google Fonts: `JetBrains Mono`, `Unbounded`, `Inter`.

---

## Sosyal medya dosyaları

| Dosya | Nerede |
|---|---|
| `profil-foto-400x400.png` | X, LinkedIn, Instagram, Telegram, Discord profil fotoğrafı |
| `github-avatar-500x500.png` | GitHub organizasyon avatarı |
| `x-banner-1500x500.png` | X kapak görseli |
| `linkedin-banner-1584x396.png` | LinkedIn şirket sayfası kapak görseli (sol taraf profil fotoğrafı için boş bırakıldı) |
| `og-gorsel-1200x630.png` | Site linki paylaşıldığında çıkan önizleme |
| `logo/favicon.ico` | Site sekmesi ikonu |

---

## Linkler

- Web: [f3nri.com](https://f3nri.com)
- GitHub: [github.com/f3nrilabs](https://github.com/f3nrilabs)
- X: [x.com/f3nrilabs](https://x.com/f3nrilabs)
- Instagram: [instagram.com/f3nrilabs](https://instagram.com/f3nrilabs)
