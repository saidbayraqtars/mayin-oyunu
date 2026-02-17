# 💣 Mines Game

Mayın Tarlası tarzında, React ile geliştirilmiş modern bir web oyunu.

## 🎮 Özellikler

- **3 Zorluk Seviyesi** — Kolay (3-5 mayın), Orta (8-10 mayın), Zor (15-20 mayın)
- **Puan ve Çarpan Sistemi** — Her güvenli kare açıldığında çarpan artar
- **Ses Efektleri** — Web Audio API ile üretilmiş tıklama, patlama ve kazanma sesleri
- **Animasyonlar** — Framer Motion ile akıcı geçişler ve efektler
- **Responsive Tasarım** — Masaüstü ve mobil uyumlu
- **Neon / Glassmorphism UI** — Modern, şık arayüz

## 🛠️ Teknolojiler

- [React](https://react.dev) + [TypeScript](https://www.typescriptlang.org/)
- [Vite](https://vitejs.dev) — Hızlı geliştirme sunucusu
- [Tailwind CSS](https://tailwindcss.com) + [shadcn/ui](https://ui.shadcn.com)
- [Framer Motion](https://www.framer.com/motion/) — Animasyonlar
- Web Audio API — Ses efektleri

## 🚀 Kurulum

```bash
# Bağımlılıkları yükle
npm install

# Geliştirme sunucusunu başlat
npm run dev
```

Oyun varsayılan olarak `http://localhost:8080` adresinde çalışır.

## 📦 Production Build

```bash
npm run build
npm run preview
```

## 🎯 Nasıl Oynanır?

1. Zorluk seviyesini seç (Kolay / Orta / Zor)
2. **Start Game** butonuna tıkla
3. Karelere tıklayarak elmasları bul 💎
4. Mayına basarsan kaybedersin 💥
5. Tüm güvenli kareleri aç ve kazanan sen ol!

## 📁 Proje Yapısı

```
src/
├── components/
│   ├── game/          # Oyun bileşenleri
│   │   ├── MinesGame.tsx
│   │   ├── GameGrid.tsx
│   │   ├── GameTile.tsx
│   │   ├── Scoreboard.tsx
│   │   ├── DifficultySelector.tsx
│   │   ├── GameControls.tsx
│   │   ├── DiamondIcon.tsx
│   │   └── BombIcon.tsx
│   └── ui/            # shadcn/ui bileşenleri
├── hooks/
│   ├── useGameLogic.ts    # Oyun mantığı
│   └── useGameSounds.ts   # Ses efektleri
└── pages/
    ├── Index.tsx
    └── NotFound.tsx
```

## 👤 Geliştirici

**Said Bayraktar**

## 📄 Lisans

MIT
