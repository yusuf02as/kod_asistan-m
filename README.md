yusuf serin

Kod-Asistan v0.1

1. BAŞLA
2. saat = 1
3. DÖNGÜ (Sürekli / Şarta bağlı):
   a. O anki saat için sensörden su_seviyesi değerini oku
   b. EĞER su_seviyesi > 50 İSE:
        Ekrana yazdır: "Kritik Eşik Aşıldı! Tahliye Saati:", saat, "Su Seviyesi:", su_seviyesi, "metre"
        DÖNGÜYÜ KIR (Bitir)
      DEĞİLSE:
        Ekrana yazdır: saat, ". saat: Su seviyesi normal (", su_seviyesi, "m). Kapaklar kapalı, saat artırılıyor."
        saat = saat + 1
4. BİTİR
