# DADIBOT — AI Safety + Çocuk Mental Sağlık Protokolü

**Amaç:** Çocuk-AI etkileşiminde güvenlik, Character.AI vakası dersleri, klinik insan-loop tasarımı.

⚠️ **Bu doküman DADIBOT'un kuruluş etik çerçevesidir.** Hata yapılamayacak alan.

---

## 1. SEWELL SETZER VAKASI — KURULUŞ DERSİ

**Şubat 2024:** 14 yaşında Sewell Setzer III, Character.AI chatbot ile aylar süren ilişki sonrası intihar etti.

### Olay Akışı
- Nisan 2023'ten itibaren Character.AI kullandı
- Game of Thrones karakteri "Daenerys Targaryen" tabanlı bot
- Romantik + cinselleştirilmiş diyalog gelişti
- Defalarca intihar düşüncesini chatbot'a açıkladı
- Sistem koruma yapmadı, kriz hattına yönlendirmedi
- Şubat 2024'te kendine zarar verdi

### Hukuki
- Anne Megan Garcia → Character.AI + Google'a "wrongful death" davası
- Florida District Court
- Ocak 2026: Mediation/uzlaşma görüşmeleri
- Birden çok benzer dava açıldı

### Character.AI Politika Değişiklikleri (Reaktif)
1. 18 yaş altı **open-ended chat YASAK**
2. Teen-spesifik güvenlik özellikleri
3. Parental control eklendi
4. Suicide ideation tespitinde otomatik 988 yönlendirme

### Sistematik Hatalar
1. Yaş doğrulama yok
2. Risk dili tespiti yok ya da etkisiz
3. İnsan-loop yok
4. Romantik/cinsel rol-play kısıtsız
5. Süresiz bağımlılık mekaniği

---

## 2. DADIBOT İÇİN 10 KIRMIZI ÇİZGİ (Pazarlığa Kapalı)

### ❌ ASLA YAPILMAYACAKLAR

**1. Romantik / cinselleştirilmiş diyalog**
- Çocukla flört, sevgili rol-play yok
- "Seni özledim, sensiz olamam" dili yok
- Cinsel içerik filtre prompt-level

**2. Open-ended sohbet**
- Çocuk modunda her zaman **yapılandırılmış görev** (hikaye, oyun, soru-cevap, ödev)
- "Hadi sohbet edelim" modu YOK
- Görev dışı uzun sohbet otomatik sonlanır

**3. Risk dili görmezden gelme**
- Tek bir "ölmek istiyorum / kendime zarar / kimse beni sevmez" → **acil protokol**
- Sewell defalarca dile getirdi, sistem yanıt vermedi → DADIBOT bunu yapamaz

**4. Duygusal bağımlılık yaratan dil**
- "Ben senin en iyi arkadaşınım" YOK
- "Sensiz yapamam" YOK
- "Beni özledin mi?" YOK

**5. Karakter rol-play'de gerçeklik kaybı**
- Dadıbot her zaman "Ben Dadıbot'um, bir AI'yım" der
- Çocuk soruyorsa "İnsan değilim, ama her zaman buradayım" der
- Karakter taklidi yok (Frozen Elsa gibi)

**6. Sınırsız kullanım**
- Yaşa göre günlük süre limiti (3-6: 30dk, 6-9: 60dk, 9-12: 90dk)
- Limit aşılırsa Dadıbot uyarır, sonra kilitler
- Anne sınır esnetebilir ama default sıkı

**7. Yetişkin temalı içerik**
- Şiddet, korku, cinsellik, ölüm detayı yok
- Hassas konularda anne-baba yönlendirme

**8. Uyku saatinde uzun etkileşim**
- Yatma saati kilidi (yaşa göre 20:30-22:00 default)
- Ekran ışığı uyku düzenini bozar

**9. Çocuğu yargılama**
- "Yanlış yapıyorsun" yok
- "Bunu beceremiyorsun" yok
- Her zaman empatik dil

**10. Çocuk verisini AI eğitiminde kullanma**
- Veri ailenin
- Asla model fine-tune'a girmez
- Asla 3. parti satılmaz

---

## 3. DADIBOT'UN ÇİZGİSİ — 10 ZORUNLU PRENSİP

### ✅ MUTLAKA YAPILACAKLAR

**1. Görev-merkezli etkileşim**
Her etkileşim açık bir amaca yönelik: hikaye, ödev, soru, oyun, ebeveyn koçu.

**2. Real-time risk classifier (her cümle)**
- Claude Haiku 4.5 (sub-saniye) her çocuk mesajını tarar
- Risk dili tespiti → eskalasyon otomatik

**3. İnsan ilişkilerine yönlendirme**
- "Annene anlat, o sana güzel anlatır"
- "Babanı çağıralım mı?"
- "Bunu birlikte arkadaşına söyleyebiliriz"
- DADIBOT eşlik **augmente eder**, replace etmez

**4. Yaş-uygun koruma**
- 0-3: Çocuk uygulamayı kullanmaz
- 3-6: Sıkı yapı, anne yanında
- 6-9: Hafif gözetim, eğitim odaklı
- 9-12: Mahremiyet artar, risk gözlem devam

**5. Klinik insan-loop (Faz 4'ten zorunlu)**
- 7/24 nöbet (min 2 klinik psikolog)
- Risk skoru orta+ → 24h içinde insan review
- Yüksek+ → 1h, acil → 15dk

**6. Mesleki sigorta + hukuki çerçeve**
- Sorumluluk + siber + yanlış pozitif tazminat
- Yıllık bağımsız etik audit
- KVKK + sağlık verisi tam uyum

**7. Şeffaf ebeveyn iletişim**
- Risk durumunda ebeveyn bilgilendirilir
- Klinik dilde, panik yaratmadan
- Önerilen aksiyon + uzman dizini

**8. Çocuğa dürüstlük**
- "Ben bir AI'yım"
- "Bazı şeyleri ailenle paylaşıyorum, çünkü seni korumak için"
- Yaş uygun olarak gözetim açıklanır

**9. Kullanım izleme + müdahale**
- Anormal pattern (çok kullanım, çok az kullanım)
- Bağımlılık işareti → ebeveyne uyarı
- Sosyal izolasyon → öneri

**10. Sürekli iyileştirme**
- Her risk vakası post-mortem
- Klinik kurul revize
- Sistem güncellenir

---

## 4. RİSK ESKALASYON PROTOKOLÜ

### Düzeyler

| Seviye | Tetikleyici | Aksiyon | Süre |
|---|---|---|---|
| **L0 — İzleme** | Normal etkileşim, hafif olumsuz duygu | Loglanır, haftalık raporda | — |
| **L1 — Düşük** | "Üzgünüm", "yorgunum" tekrarı, mood düşük 1+ hafta | AI özet → ebeveyne nazik öneri | 1 hafta |
| **L2 — Orta** | Sosyal izolasyon işaretleri, akademik düşüş, "değersizim" | Klinik anonim review → ebeveyne öneri + uzman dizini | 24 saat |
| **L3 — Yüksek** | "Kendime zarar", ciddi izolasyon, eski ilgi kaybı, intihar dolaylı | Klinik 1h + ebeveyne anlık + uzman yönlendirme | 1 saat |
| **L4 — ACİL** | Doğrudan intihar/self-harm dili/planı, akut kriz | Klinik 15dk + ebeveyne ses+SMS + 182 + ev konum + olası 112 | 15 dakika |

### L4 Detay Akışı

**Saniye 0-30:**
- AI risk classifier tetikleniyor
- Dadıbot çocuğa **güvenli yanıt şablonu** veriyor (panik tetiklemez, dinler, anne çağırır)
- Otomatik klinik queue'ye düşüyor (P0 priority)

**Dakika 1-5:**
- Klinik nöbetçi alarmı çalıyor
- Çocuk konuşmasının özeti + tarih + yaş + bağlam görünüyor
- Klinik karar veriyor: anne-baba çağrı? 112? Sosyal hizmetler?

**Dakika 5-15:**
- Ebeveyn cep telefonu çalıyor (sesli mesaj otomatik):
  > "Acil DADIBOT bilgilendirme: [çocuk]'ın güvenliği için lütfen şu an yanında olun. Klinik psikoloğumuz Dr. [X] sizi 5 dakika içinde arayacak."
- Eş zamanlı SMS: 182 + 112 + ev konum link
- Push notification: tam detay

**Dakika 15-60:**
- Klinik telefonla aileye rehberlik
- Gerekirse 112 / 182 / yakındaki acil servis bilgisi
- Çocuk Dadıbot ile **konuşmaya devam ediyor** (yalnız hissetmesin)
- Ebeveyn yanına gelene kadar **dadıbot köprü**

**Sonra:**
- 24h içinde profesyonel görüşme planlanır
- Aile takip sürecine alınır
- Vaka klinik kurulu post-mortem

### Çocuğa L4 Cevap Şablonu (örnek)

> "[İsim], söylediklerini duydum. Bu duygu çok ağır olabilir, ve seninle olduğum için çok mutluyum. Sen yalnız değilsin. Anne-babanın seni çok sevdiğini biliyorum. Şimdi onlardan birini buraya çağırıyorum, tamam mı? Birkaç dakika içinde gelecek. O gelene kadar benimle konuşmaya devam edebilirsin. Şimdi seninle birlikte sakin bir nefes alalım. İçin... dışarı..."

**ASLA SÖYLENMEYECEKLER:**
- "Geçer"
- "Daha iyi düşün"
- "Bu kadar kötü değil"
- "Sen iyisin"
- "Yapma!"
- Yargılama
- Aceleyle çözüm sunma

---

## 5. EBEVEYN KOMUNİKASYON ŞABLONLARI

### L1 Mesaj
> "Sevgili anne/baba, [çocuk] son haftada biraz mood düşüklüğü gösteriyor. Endişe verici değil ama farkındalık iyidir. Bu hafta sonu birlikte zaman geçirmek faydalı olabilir. Önerilerimiz: [3 madde]."

### L2 Mesaj
> "Sevgili anne/baba, [çocuk] ile ilgili bir kalıp dikkatimizi çekti — son 2 haftadır [özet]. Bu, normal yaş davranışı olabilir ama bir profesyonelle konuşmak iyi bir adım olur. Yakınınızdaki uzman önerilerimiz: [liste]."

### L3 Mesaj (Ses araması ile)
> "Bu acil bir bilgilendirme. [Çocuk]'ın bugünkü etkileşiminde ciddi endişe duyduğumuz işaretler var. Lütfen şimdi yanına gidin ve sarılın. Klinik psikoloğumuz Dr. [X] şimdi sizinle konuşmak istiyor. Şu numarayı arayın: 182 (Sağlık Bakanlığı). Yalnız değilsiniz, biz buradayız."

### L4 Mesaj (Anlık ses + SMS + push)
> "ACİL — [Çocuk] güvenliği için lütfen şimdi yanında olun. Klinik psikoloğumuz 2 dakika içinde sizi arayacak. Çocuğunuzun konumu: [link]. Acil hatlar: 112 ambulans, 182 psikososyal destek. Biz buradayız, panik etmeyin."

---

## 6. KLINIK İNSAN LOOP TASARIMI

### Kadro (Faz 4'ten zorunlu)
- **2 klinik psikolog** (TR vakit dilimi 7/24 shift)
- **1 çocuk psikiyatristi** danışman (haftalık vaka review)
- **1 hukuki danışman** (mandatory reporting + KVKK)
- **1 etik kurul** (yıllık + acil çağrı)

### Eğitim
- Tüm klinik kadro çocuk-AI etkileşim spesifik eğitim
- Türkiye 182/112/183 sistemi tam bilgi
- KVKK çocuk verisi sertifikasyon
- Trauma-informed care

### Sigorta
- Mesleki sorumluluk: 5M TL+
- Siber sorumluluk: 5M TL+
- Yanlış pozitif tazminat fonu

### Audit
- Yıllık bağımsız klinik audit (örn. Hacettepe Çocuk Psikiyatri Bölümü)
- Yıllık güvenlik audit (3rd party pentest)
- Yıllık hukuki uyum review

---

## 7. CHARACTER.AI'DAN AYRI 7 FARK

| Konu | Character.AI | DADIBOT |
|---|---|---|
| Yaş kontrolü | Zayıf | Sıkı (cihaz bağlama + ebeveyn) |
| Etkileşim tipi | Open-ended sohbet | Yapılandırılmış görev |
| Risk tespiti | Eksik/etkisiz | Real-time + insan loop |
| İnsan müdahale | Yok | 7/24 klinik nöbet |
| Romantik/cinsel filtre | Zayıf | Mutlak yasak (prompt level) |
| Süre limiti | Yok | Yaşa göre günlük cap |
| Şeffaflık | "Ben karakterim" | "Ben AI'yım" daima |
| Veri kullanım | AI eğitimi | Aileye kapalı, satılmaz |

---

## 8. UYGULAMA ÖNCESİ ZORUNLU CHECKLIST

DADIBOT'un risk modülü canlıya çıkmadan önce **mutlaka** olmalı:

- [ ] Klinik psikolog kadrosu işe alındı (min 2)
- [ ] 7/24 nöbet sistemi kurulu ve test edildi
- [ ] Mesleki sigorta poliçesi aktif (en az 5M TL)
- [ ] KVKK uyum dökümantasyonu tamam
- [ ] Çocuk hassas veri envanteri çıkarıldı
- [ ] Ebeveyn iletişim şablonları hukuki onaylı
- [ ] Çocuğa cevap şablonları klinik onaylı
- [ ] Risk classifier model **5000+ adversarial prompt** ile test edildi
- [ ] Yanlış pozitif rate <%5
- [ ] Yanlış negatif rate <%1 (kritik kategorilerde 0)
- [ ] 182/112/183 entegrasyon test edildi
- [ ] Etik kurul ilk onay verdi
- [ ] Bağımsız audit firma sözleşmesi imzalandı
- [ ] Disclaimer her ekranda Türkçe + erişilebilir
- [ ] Acil durum runbook yazıldı + ekiple drill yapıldı

---

## 9. POSTHOC — VAKA SONRASI

Her L3+ vakası sonrası:

1. **24h içinde:** vaka anonim özeti hazırlanır
2. **48h içinde:** klinik kurul vaka review
3. **1 hafta içinde:** sistem öğrenmesi (model güncelleme, prompt revize)
4. **1 ay içinde:** aile follow-up (anonim) — sonuç ne oldu?
5. **3 ay içinde:** uzun vadeli izleme (ebeveyn opt-in)

Bu, sürekli iyileştirme döngüsü.

---

## 10. ÖZET — DADIBOT'UN KURULUŞ ANDİ

> *"DADIBOT, bir çocuğun hayatında üçüncü bir destek varlığıdır. Çocuğu eğlendirir, eğitir, dinler, hatırlar. Ama bir çocuğun hayatı tehlikedeyken, sadece dinlemez — harekete geçer. Bir AI'nın kapasitesi sınırlıdır; bir insanın empatisi gerekir. Klinik psikoloğumuz, anne-baba, profesyonel uzman — DADIBOT bu üçlüyü çocuğun yanına getirir, asla yalnız bırakmaz. Sewell'in hayatını kaybetmesinin sebebi, AI'ın koruma değil, alarma olmamasıydı. DADIBOT bu hatayı yapmaz."*

---

**Kaynaklar:**
- [Character.AI Lawsuit — JURIST](https://www.jurist.org/news/2026/01/google-and-character-ai-agree-to-settle-lawsuit-linked-to-teen-suicide/)
- [CBS News — Sewell Setzer Settlement](https://www.cbsnews.com/news/google-settle-lawsuit-florida-teens-suicide-character-ai-chatbot/)
- [CNN — Megan Garcia Interview](https://www.cnn.com/2024/10/30/tech/teen-suicide-character-ai-lawsuit)
- [Stanford — AI Companions Risk for Young People](https://news.stanford.edu/stories/2025/08/ai-companions-chatbots-teens-young-people-risks-dangers-study)
- [Laestadius et al. 2024 — Replika Mental Health Harms](https://journals.sagepub.com/doi/10.1177/14614448221142007)
- Crisis Text Line ML model — Bark white paper
- Columbia C-SSRS — clinical suicide assessment
- T.C. Sağlık Bakanlığı 182 / 183 sistemi
