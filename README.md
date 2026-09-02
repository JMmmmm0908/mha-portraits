# My Hero Academia Portraits

Original AI-generated portrait assets for **My Hero Academia: Unwritten Names**.

## Disclaimer

This project is unofficial, fan-made, AI-generated, unaffiliated with the rights holders, and intended for personal/non-commercial use. No general copyright license is asserted over the underlying characters.

## Asset contract

Every portrait follows the **Hero Society Evidence** direction: original anime-painted, head-and-shoulders artwork in an opaque sRGB WebP. Files are exactly **512×640 pixels** at a **4:5** aspect ratio, with the stable UI focal point at **50% 30%** (manifest value `[0.5, 0.3]`).

Each roster key maps to this exact raw URI template:

```text
https://raw.githubusercontent.com/JMmmmm0908/mha-portraits/main/<roster-key>-favor.webp
```

The consuming application falls back to the roster glyph when a portrait URI is empty or fails to load; if the glyph is missing, it uses two-character initials.

GitHub raw-CDN caching may delay a replacement image for several minutes.

## Portrait index

Every roster key appears here. `live` means the file is in this repo and the raw URI resolves; `pending` means the
roster key exists and the consuming application is currently falling back to that character glyph.

**52 live · 16 pending · 68 total**

| File | Subject | Group | Earliest era | Status |
|---|---|---|---|---|
| `izuku-favor.webp` | Izuku Midoriya | Class 1-A | `entrance-season` | live |
| `bakugo-favor.webp` | Katsuki Bakugo | Class 1-A | `entrance-season` | live |
| `ochaco-favor.webp` | Ochaco Uraraka | Class 1-A | `entrance-season` | live |
| `iida-favor.webp` | Tenya Iida | Class 1-A | `entrance-season` | live |
| `shoto-favor.webp` | Shoto Todoroki | Class 1-A | `entrance-season` | live |
| `tsuyu-favor.webp` | Tsuyu Asui | Class 1-A | `entrance-season` | live |
| `mineta-favor.webp` | Minoru Mineta | Class 1-A | `entrance-season` | live |
| `kirishima-favor.webp` | Eijiro Kirishima | Class 1-A | `entrance-season` | live |
| `momo-favor.webp` | Momo Yaoyorozu | Class 1-A | `entrance-season` | live |
| `tokoyami-favor.webp` | Fumikage Tokoyami | Class 1-A | `entrance-season` | live |
| `denki-favor.webp` | Denki Kaminari | Class 1-A | `entrance-season` | live |
| `aoyama-favor.webp` | Yuga Aoyama | Class 1-A | `entrance-season` | live |
| `jiro-favor.webp` | Kyoka Jiro | Class 1-A | `entrance-season` | live |
| `mina-favor.webp` | Mina Ashido | Class 1-A | `entrance-season` | live |
| `shoji-favor.webp` | Mezo Shoji | Class 1-A | `entrance-season` | live |
| `ojiro-favor.webp` | Mashirao Ojiro | Class 1-A | `entrance-season` | live |
| `sero-favor.webp` | Hanta Sero | Class 1-A | `entrance-season` | live |
| `toru-favor.webp` | Toru Hagakure | Class 1-A | `entrance-season` | live |
| `sato-favor.webp` | Rikido Sato | Class 1-A | `entrance-season` | live |
| `koda-favor.webp` | Koji Koda | Class 1-A | `entrance-season` | live |
| `kendo-favor.webp` | Itsuka Kendo | Class 1-B | `sports-festival` | live |
| `monoma-favor.webp` | Neito Monoma | Class 1-B | `sports-festival` | live |
| `tetsutetsu-favor.webp` | Tetsutetsu Tetsutetsu | Class 1-B | `sports-festival` | live |
| `shinso-favor.webp` | Hitoshi Shinso | General Studies | `sports-festival` | live |
| `mei-favor.webp` | Mei Hatsume | Support Course | `sports-festival` | live |
| `ibara-favor.webp` | Ibara Shiozaki | Class 1-B | `sports-festival` | pending |
| `aizawa-favor.webp` | Shota Aizawa | U.A. Faculty | `entrance-season` | live |
| `all-might-favor.webp` | All Might | U.A. Faculty | `entrance-season` | live |
| `nezu-favor.webp` | Nezu | U.A. Faculty | `entrance-season` | live |
| `present-mic-favor.webp` | Hizashi Yamada | U.A. Faculty | `entrance-season` | live |
| `midnight-favor.webp` | Midnight | U.A. Faculty | `entrance-season` | live |
| `recovery-girl-favor.webp` | Chiyo Shuzenji | U.A. Faculty | `entrance-season` | live |
| `cementoss-favor.webp` | Cementoss | U.A. Faculty | `entrance-season` | pending |
| `mirio-favor.webp` | Mirio Togata | U.A. Big Three | `license-hassaikai` | live |
| `nejire-favor.webp` | Nejire Hado | U.A. Big Three | `license-hassaikai` | live |
| `tamaki-favor.webp` | Tamaki Amajiki | U.A. Big Three | `license-hassaikai` | live |
| `eri-favor.webp` | Eri | Shie Hassaikai | `license-hassaikai` | live |
| `endeavor-favor.webp` | Enji Todoroki | Endeavor Agency | `internships-hosu` | live |
| `hawks-favor.webp` | Keigo Takami | Hero Public Safety Commission | `school-festival-pro-hero` | live |
| `best-jeanist-favor.webp` | Tsunagu Hakamada | Pro Heroes | `kamino-fallout` | live |
| `mirko-favor.webp` | Rumi Usagiyama | Pro Heroes | `internships-hosu` | live |
| `fat-gum-favor.webp` | Taishiro Toyomitsu | Fat Gum Agency | `internships-hosu` | live |
| `nighteye-favor.webp` | Mirai Sasaki | Nighteye Agency | `license-hassaikai` | live |
| `gran-torino-favor.webp` | Sorahiko Torino | Independent Pro Hero | `internships-hosu` | live |
| `mt-lady-favor.webp` | Mt. Lady | Pro Heroes | `entrance-season` | pending |
| `uwabami-favor.webp` | Uwabami | Uwabami Agency | `internships-hosu` | pending |
| `kamui-woods-favor.webp` | Kamui Woods | Pro Heroes | `entrance-season` | pending |
| `ryukyu-favor.webp` | Ryukyu | Ryukyu Agency | `license-hassaikai` | pending |
| `shigaraki-favor.webp` | Tomura Shigaraki | League of Villains | `spring-usj` | live |
| `all-for-one-favor.webp` | All For One | All For One Network | `kamino-fallout` | live |
| `dabi-favor.webp` | Dabi | League of Villains | `finals-training-camp` | live |
| `toga-favor.webp` | Himiko Toga | League of Villains | `finals-training-camp` | live |
| `twice-favor.webp` | Jin Bubaigawara | League of Villains | `finals-training-camp` | live |
| `spinner-favor.webp` | Shuichi Iguchi | League of Villains | `finals-training-camp` | live |
| `compress-favor.webp` | Atsuhiro Sako | League of Villains | `finals-training-camp` | live |
| `stain-favor.webp` | Chizome Akaguro | Independent Villain | `internships-hosu` | live |
| `overhaul-favor.webp` | Kai Chisaki | Shie Hassaikai | `license-hassaikai` | live |
| `re-destro-favor.webp` | Re-Destro | Meta Liberation Army | `liberation-buildup` | live |
| `lady-nagant-favor.webp` | Lady Nagant | Former HPSC Pro Hero | `dark-hero-evacuation` | pending |
| `tsukauchi-favor.webp` | Naomasa Tsukauchi | Police Force | `spring-usj` | pending |
| `awase-favor.webp` | Yosetsu Awase | Class 1-B | `sports-festival` | pending |
| `tiger-favor.webp` | Tiger | Wild Wild Pussycats | `finals-training-camp` | pending |
| `kota-favor.webp` | Kota Izumi | Civilian | `finals-training-camp` | pending |
| `mera-favor.webp` | Yokumiru Mera | Hero Public Safety Commission | `license-hassaikai` | pending |
| `inasa-favor.webp` | Inasa Yoarashi | Shiketsu High | `license-hassaikai` | pending |
| `camie-favor.webp` | Camie Utsushimi | Shiketsu High | `license-hassaikai` | pending |
| `gang-orca-favor.webp` | Gang Orca | Pro Heroes | `license-hassaikai` | pending |
| `shindo-favor.webp` | Yo Shindo | Ketsubutsu Academy | `license-hassaikai` | pending |
