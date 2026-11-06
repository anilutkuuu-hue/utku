# 🧩 Karanlık Mavi & Mor Temalı Sudoku (PWA)

Modern, karanlık siyah arka plan üzerinde gri 3x3 bloklar ve mavi-mor neon vurgulara sahip, tarayıcıda ve mobilde tek tıkla çalışan Sudoku oyunu.

## ✨ Özellikler
- **3 Yanlış Hakkı:** Klasik Sudoku kuralları; toplam 3 hata yapıldığında oyun biter ve doğru istatistikler gösterilir.
- **Orta ve Zor Seviyeler:** Algoritmik olarak oluşturulan ve matematiksel olarak tekil çözüme (unique solution) sahip bulmacalar.
- **Canlı Süre Sayacı:** Oyuna başladığınız an süre sayar, istediğinizde duraklatabilirsiniz.
- **Alttan Sayı Seçimi:** Alttaki 1–9 tuşlarına basarak sayıyı seçebilir ve boş kutulara hızlıca yerleştirebilirsiniz. Kalan sayı adedi sayaçta görünür.
- **Klavye Desteği:** 1–9 rakam tuşları, ok tuşları ve not modu için `N` tuşu.
- **PWA Desteği (Progressive Web App):** `manifest.json` ve `sw.js` sayesinde telefona veya bilgisayara "Uygulama Olarak Yükle" (Add to Home Screen) desteği ve internetsiz (çevrimdışı) çalışabilme.
- **Ses Efektleri:** Web Audio API ile harici dosya yüklemesi gerektirmeyen doğru/yanlış ve zafer tonları.

## 🚀 GitHub Pages ile Yayınlama Adımları
1. Bu depoyu GitHub'da `sudoku` adıyla oluşturun.
2. Bu klasördeki tüm dosyaları (`index.html`, `manifest.json`, `sw.js`, `favicon.svg`, `icon-192.png`, `icon-512.png`, `.nojekyll`, `README.md`) depoya yükleyin.
3. GitHub deponuzda **Settings > Pages** sekmesine gidin.
4. **Build and deployment > Branch** kısmını `main` (veya `master`) ve `/ (root)` seçip **Save** butonuna tıklayın.
5. 1-2 dakika içinde siteniz `https://<kullanici-adiniz>.github.io/sudoku/` adresinde canlıya geçecektir!

## 📄 Lisans
MIT License
