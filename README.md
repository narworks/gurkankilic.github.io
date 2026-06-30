# G. Gürkan Kılıç — Personal Portfolio

Kişisel portföy sitesi · **[gurkankilic.com](https://gurkankilic.com)**

İki dilli (TR/EN) editöryel tek-sayfa portföy. GitHub Pages üzerinde statik olarak yayınlanır.

## İçerik

- **Hero** — otomatik dönen 3 slaytlı tanıtım
- **Hakkımda** — özet, biyografi, istatistikler ve yetenekler
- **Projeler** — Portfoymax, Muhasebe Asistanı, Nar Menu, XR & Indie Oyunlar
- **Deneyim** — kariyer zaman çizelgesi
- **Narworks** — girişim stüdyosu bölümü
- **İletişim**

## Yapı

| Dosya | Açıklama |
|-------|----------|
| `index.html` | Sayfanın tamamı (içerik + bileşen) |
| `support.js` | Claude Design `dc-runtime` (React'ı çalışma anında yükler) |
| `image-slot.js` | Hero görsel bileşeni |
| `uploads/` | Proje kartı arka plan görselleri |
| `favicon.svg` | GK monogram favicon |
| `CNAME` | Özel alan adı (gurkankilic.com) |

## Notlar

- Tasarım bir **Claude Design** projesinden taşınmıştır.
- `dc-runtime`, React/ReactDOM ve Babel'i çalışma anında `unpkg` CDN'inden yükler.
- Yerelde önizleme: `python3 -m http.server 8000` → `http://localhost:8000`
