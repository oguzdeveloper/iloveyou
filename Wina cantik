# I Love You — Animasyonlu Kalp

<p align="center">
  <img src="iloveyou.gif" alt="I Love You - Onizleme" width="600" />
</p>

Kalp silueti boyunca akan *"I love you"* yazilariyla goze carpan, neon-pembe parlamayla desteklenmis hafif bir web animasyonu. Harici bagimliligi yoktur; saf HTML + CSS + JS ile calisir.

---

## On Izleme

| Masaustu | Mobil |
|----------|-------|
| 100 kelime, kesintisiz 50 sn dongu | 50 kelime, optimize edilmis yerlesim |

> `index.html` dosyasini herhangi bir modern tarayicida acmaniz yeterlidir — derleme adimi gerektirmez.

---

## Ozellikler

- **Kalp yolu animasyonu** — kelimeler, CSS `offset-path` kullanilarak matematiksel olarak olusturulan kalp egrisi uzerinde surekli hareket eder.
- **Neon parlama efekti** — katmanli `text-shadow` ile koyu arka plan uzerinde canli pembe isik yayilimi saglanir.
- **Responsive tasarim** — kelime sayisi, font boyutu ve kalp olcegi mobil ve masaustu gorunumlere otomatik uyum saglar.
- **GPU hizlandirmali** — `will-change: offset-distance` ve `contain` ozellikleri sayesinde takılma olmadan 60 fps render yapilir.
- **Kolayca ozellestirilebilir** — metin, renk, hiz ve merkez etiketi minimum duzenlemeyle degistirilebilir.

---

## Teknoloji Yigini

| Katman | Teknoloji |
|--------|-----------|
| Yapi | HTML5 |
| Stil ve Animasyon | CSS3 (custom properties, `offset-path`, keyframes) |
| Mantik | Vanilla JavaScript (ES5 uyumlu IIFE) |
| Tipografi | Google Fonts — Great Vibes, Poppins |

---

## Baslangic

```bash
git clone https://github.com/oguzdeveloper/iloveyou.git
cd iloveyou
```

Ardindan `index.html` dosyasini tarayicinizda acin. Hepsi bu.

Projeyi canli yayinlamak icin **GitHub Pages**, **Netlify**, **Vercel** veya herhangi bir statik dosya sunucusuna yukleyebilirsiniz.

---

## Proje Yapisi

```
iloveyou/
├── index.html          Ana HTML dosyasi
├── styles.css          Tum stiller, animasyonlar ve responsive kurallar
├── script.js           Kalp egrisi olusturma ve kelime yerlestirme
├── iloveyou.gif        Onizleme animasyonu
└── README.md           Bu dosya
```

---

## Ozellestirme

### Metin

`script.js` dosyasinda asagidaki satiri bulun ve istediginiz ifadeyle degistirin:

```javascript
el.textContent = "I love you";   // istediginiz metni yazin
```

### Renkler

`styles.css` icindeki CSS degiskenlerini duzenleyin:

```css
:root {
  --pink: #ff2d95;
  --pink-glow: rgba(255, 45, 149, 0.9);
}
```

### Animasyon Hizi

`styles.css` icindeki `--travel` ve `script.js` icindeki `TRAVEL_SEC` degerlerini esit tutarak ayarlayin:

```css
:root {
  --travel: 50s;      /* daha yavas = daha yuksek deger */
}
```

```javascript
var TRAVEL_SEC = 50;   // CSS ile senkron tutun
```

### Merkez Etiketi

Kalbin ortasinda gorunen isim `index.html` icerisinde belirlenir:

```html
<span class="brand-kitty">Oğuz</span>
```

---

## Tarayici Destegi

CSS `offset-path` destegi gerektirir. Chrome, Edge, Firefox ve Safari'nin guncel surumleri tam uyumludur.

---

## Lisans

Bu proje [MIT Lisansi](https://opensource.org/licenses/MIT) altinda yayinlanmistir. Serbestce kullanabilir, degistirebilir ve dagitabilirsiniz.

---

<p align="center"><strong>oguzdeveloper</strong> tarafindan ozenle yapilmistir.</p>
