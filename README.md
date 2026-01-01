# RastgeleSay-reteci
SALİH YÖRDEM 230541141
# Collatz Conjecture RNG

Bu proje, ünlü matematiksel problem **Collatz Sanısı**'nı (3n+1 Problemi) temel alan basit bir Sözde Rastgele Sayı Üreteci (PRNG) uygulamasıdır. Bilgi Sistemleri Güvenliği dersi kapsamında geliştirilmiştir.

## 🔬 Nasıl Çalışır?

Algoritma, rastgele sayı üretmek için Collatz dizisinin kaotik yapısını kullanır:
1. Bir başlangıç tohumu (seed) belirlenir.
2. Her adımda Collatz fonksiyonu uygulanır:
   - Sayı çift ise: $n / 2$
   - Sayı tek ise: $3n + 1$
3. Sayı 1'e ulaştığında (4-2-1 döngüsü), entropiyi korumak için durum (state) yeniden tohumlanır.

## 🚀 Kurulum ve Kullanım

Kod Python 3 ile yazılmıştır. Herhangi bir harici kütüphane gerektirmez.

```bash
python collatz_rng.py
