<div align="center">

<img src="assets/mascot.jpg" width="120" alt="TechDuo Maskot" />

# ⚡ TechDuo

### Duolingo tarzı Türkçe teknoloji okuryazarlığı uygulaması

[![Demo](https://img.shields.io/badge/🌐_Demo-Canlı-22c55e?style=for-the-badge)](https://mahsumaktas.github.io/techduo/)
[![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-deployed-38bdf8?style=for-the-badge&logo=github)](https://mahsumaktas.github.io/techduo/)
[![License](https://img.shields.io/badge/License-MIT-fbbf24?style=for-the-badge)](LICENSE)

**Python nedir? Docker nedir? Yapay zeka nasıl çalışır?**  
Hiç bilmeden başla, oynayarak öğren. 🎮

[**👉 Hemen Oyna**](https://mahsumaktas.github.io/techduo/)

</div>

---

## 🎯 Ne Bu?

TechDuo, **teknik bilgisi sıfır olan** herkesin teknoloji dünyasını keşfedebileceği bir öğrenme oyunu.

Anneni, babanı, iş arkadaşını düşün — "Binary nedir?", "Cloud ne demek?", "AI gerçekten ne yapıyor?" sorularını soran herkes için yapıldı.

Duolingo'nun oyun mekaniği + teknoloji içeriği = **TechDuo**

---

## 🕹️ Özellikler

| Özellik | Detay |
|---------|-------|
| 🎮 **Gamification** | XP, 🔥 Streak, ❤️ 5 Can sistemi |
| 📚 **10 Ünite** | Binary'den Güvenlik'e tam müfredat |
| ❓ **107 Soru** | Çoktan seçmeli, Doğru/Yanlış, Boşluk doldur |
| 🔒 **Progressif Kilitleme** | Önceki üniteyi bitir, sıradakini aç |
| 💾 **Kayıt** | İlerleme tarayıcıda kaydedilir |
| 📱 **Mobil Uyumlu** | Telefon ve masaüstü desteği |
| 🌙 **Koyu Tema** | Göz yormayan dark mode |
| 🇹🇷 **Türkçe** | Tamamen Türkçe içerik |

---

## 📖 Müfredat

```
💾 Ünite 1  — Bilgisayarın Dili     (0 ve 1, bit, byte)
💻 Ünite 2  — Yazılım ve Donanım    (ne fark var, örnekler)
🌐 Ünite 3  — İnternet Nasıl Çalışır (DNS, IP, HTTP)
🧑‍💻 Ünite 4  — Programlama Nedir    (kod, algoritma, dil)
🐍 Ünite 5  — Python'a Giriş        (print, değişken, fonksiyon)
🗄️ Ünite 6  — Veri ve Veritabanları  (SQL, tablo, sorgu)
🕸️ Ünite 7  — Web Geliştirme         (HTML, CSS, JS)
🤖 Ünite 8  — Yapay Zeka ve LLM     (AI, ML, prompt)
☁️ Ünite 9  — DevOps ve Bulut       (Docker, Git, CI/CD)
🔒 Ünite 10 — Güvenlik ve Gizlilik  (şifre, 2FA, phishing)
```

---

## 🚀 Yerel Kurulum

Sıfır bağımlılık — tek HTML dosyası:

```bash
git clone https://github.com/mahsumaktas/techduo.git
cd techduo
# Tarayıcıda aç:
open index.html
# Veya local server:
python3 -m http.server 8000
# → http://localhost:8000
```

---

## 🛠️ Teknoloji

- **Saf HTML + CSS + JS** — framework yok, bağımlılık yok
- **Tek dosya** — `index.html` tüm oyun mantığını içeriyor
- **`curriculum.json`** — 10 ünite, 107 soru ayrı JSON'da
- **GitHub Pages** — ücretsiz hosting
- **Görseller** — [Nano Banana Pro](https://ai.google.dev/) ile üretildi

---

## 🗺️ Yol Haritası

- [ ] Placement test (seviye atlama)
- [ ] Daha fazla soru türü (kod tamamlama, eşleştirme)
- [ ] Liderlik tablosu
- [ ] İngilizce çeviri
- [ ] Ses efektleri
- [ ] PWA (telefona yüklenebilir uygulama)
- [ ] Daha fazla ünite (Linux, API, Blockchain...)

---

## 🤝 Katkı

PR'lar memnuniyetle karşılanır! Özellikle:
- Yeni sorular / ünite içerikleri
- Bug fix'ler
- UI iyileştirmeleri

```bash
# Yeni soru eklemek için:
# curriculum.json dosyasını düzenle
# Her stop şu formatı takip etmeli:
{
  "type": "mc",           # mc | tf | fill
  "question": "...",
  "options": ["A","B","C","D"],
  "correct": 0,           # index
  "explanation": "..."
}
```

---

## 📄 Lisans

MIT © [Mahsum Aktaş](https://github.com/mahsumaktas)

---

<div align="center">

Bir gecede yapıldı ⚡ · Feedback için: [@muxamos](https://x.com/muxamos)

</div>
