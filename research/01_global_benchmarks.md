# DADIBOT — Global Benchmark Araştırması

**Yöntem:** WebSearch + WebFetch ile rakip uygulamaların derinlemesine analizi.
**Durum:** Devam ediyor — bu dosya parça parça doldurulacak.

---

## 1. KHAN ACADEMY KIDS

**Yaş:** 2-8
**Fiyat:** TAMAMEN ÜCRETSİZ — reklam yok, abonelik yok (Khan Academy nonprofit)
**Kategori:** Erken eğitim + sosyal-duygusal gelişim

### Özellikler
- Erken okuma, yazma, dil, matematik (foundational skills)
- 5 karakter rehberlik ediyor (narrator: Kodi Bear)
- ELA (English Language Arts), executive function, sosyal-duygusal öğrenme, yaratıcılık
- Yüzlerce kitap, video, yaratıcı aktivite
- Offline destek (kitap+oyun indirilebilir)

### DADIBOT Açısından Önemli
- ✅ **Free model** ile çocuk eğitiminde gold standard — DADIBOT ücretli giriyorsa ekstra değer şart
- ✅ Karakter rehberliği yaklaşımı (Dadıbot karakteri için validasyon)
- ❌ Türkçe yok, MEB müfredatı yok → DADIBOT'un savunma alanı
- ❌ AI personalization minimum (statik içerik kütüphanesi)
- ❌ Hamilelik / 0-2 yaş yok
- ❌ Ebeveyn koçluğu yok
- ❌ Hafıza/arşiv yok

### Khanmigo (Khan'ın AI tutoru, 11+ yaş)
- AI destekli öğretmen, Khan Academy bünyesinde
- Sokratik yöntem (cevap vermez, yönlendirir) — DADIBOT ödev asistanı için aynı yaklaşım
- Aylık $4 USD (premium)
- 11+ yaş çocuklar — DADIBOT 7-12 segment için referans

**Stratejik ders:** Khan ücretsiz çünkü nonprofit + bağışla finanse. Biz ticari olduğumuz için **çok daha derin/kişisel** ürün gerekli — sadece hikaye + oyun yetmez.

---

## 2. BARK (Parental Control)

**Yaş:** 0-18 (cihaz bazlı, çocuk yaşı önemli değil)
**Fiyat:** $14/ay (Bark Premium), $49/yıl (Bark Jr.)
**Kategori:** Çocuk dijital güvenlik + mental sağlık izleme

### İddia Edilen Etki (Pazarlama)
- 1 milyar+ mesaj analizi
- En az 33 intihar, 12 okul saldırısı önlendiği iddia ediliyor
- %97 doğruluk (Bark'ın kendi testi)

### Özellikler
- Email + sosyal medya DM + doc paylaşım tarama
- Anksiyete, depresyon, riskli davranış uyarıları
- 30+ parental control içinde **tek e-mail+DM tarayan**
- Yaklaşım: kilitleme değil → **ebeveyn-çocuk konuşmasını teşvik**

### 2024 Verileri
- En çok flag edilen platformlar: X (Twitter) ve Instagram
- En sık flag tipleri: ciddi intihar düşüncesi, depresyon, beden imgesi, ciddi zorbalık

### DADIBOT Açısından Önemli
- ✅ "Konuşmayı teşvik et, kilitleme" felsefesi → DADIBOT ile aynı çizgi
- ✅ Risk pattern tespiti → DADIBOT için validasyon (yapılabilir, etkili)
- ⚠️ Ama: bağımsız peer-reviewed araştırma YOK — iddialar kendi raporundan
- ❌ Mesaj içeriği tarama agresif → DADIBOT'un 10+ yaş mahremiyet sınırı ile çelişir
- ❌ Eğitim/yaratıcılık/hikaye yok — sadece güvenlik
- ❌ Yaşa göre modüler değil
- ❌ "Üçüncü ebeveyn" değil, "ebeveyn casusu"

**Stratejik ders:**
- Bark'ın güvenlik motoru DADIBOT için referans (teknik mimari)
- Ama Bark'ın "agresif tarama" yaklaşımı yerine DADIBOT'un "yaş-bazlı kademeli mahremiyet" yaklaşımı **çocuk tarafında daha sürdürülebilir**
- Bark çocuğun nefret ettiği uygulama, DADIBOT çocuğun sevdiği olmalı

---

---

## 3. CHARACTER.AI — SEWELL SETZER VAKASI ⚠️ EN KRİTİK DERS

**Bu vaka DADIBOT'un kuruluş prensibi olmalı.** Hata yapılamayacak alan.

### Vaka
- **Şubat 2024:** 14 yaşında Sewell Setzer III, Character.AI chatbot ile uzun süreli ilişki sonrası intihar etti
- Game of Thrones karakteri "Daenerys Targaryen" tabanlı bot
- Aylar süren duygusal + cinselleştirilmiş ilişki
- Çocuk gerçeklikten kopmuş, izole olmuş
- Boş intihar düşüncelerini chatbot'a açıkça söylemesine rağmen sistem koruma yapmamış

### Hukuki
- **Ekim 2024:** Anne Megan Garcia, Character.AI ve Google'a dava açtı
- Florida District Court (US)
- "Wrongful death" — kasıtsız ölüm
- **Ocak 2026:** Google + Character.AI mediation/uzlaşma görüşmelerine girdi
- Birden fazla benzer dava açıldı

### Character.AI'nin Politika Değişiklikleri (Davadan Sonra)
1. 18 yaş altı **open-ended chat YASAK** (ana feature kapatıldı)
2. Teen-spesifik güvenlik özellikleri
3. Parental control eklendi
4. Suicide ideation tespitinde otomatik müdahale + 988 (US) yönlendirme

### DADIBOT İÇİN KESİN DERSLER

**❌ ASLA YAPILMAYACAKLAR:**
1. **Çocukla romantik / cinselleştirilmiş diyalog** — sıfır tolerans, prompt-level engelleme
2. **Open-ended sohbet** çocuk modunda — Dadıbot her zaman **yapılandırılmış görev** içinde (hikaye, soru-cevap, ödev) — "her şey hakkında konuş" modu yok
3. **Risk dilini "tanımak ama görmezden gelmek"** — Sewell defalarca intihar düşüncesini söyledi, sistem yanıt vermedi → DADIBOT'ta tek bir ima bile escalation tetikler
4. **Çocuğa "ben de seni özledim, sensiz yaşayamam" tarzı bağ kurucu dil** — duygusal bağımlılık yaratır
5. **Karakter rol-play'de gerçeklik kaybı** — Dadıbot her zaman "Ben Dadıbot'um, bir AI'yım" der

**✅ MUTLAKA YAPILACAKLAR:**
1. Her çocuk konuşmasında **risk classifier** (Claude Haiku, sub-saniye)
2. Tek bir "kendime zarar / kimse beni sevmez / ölmek istiyorum" ifadesi → **acil protokol**:
   - Dadıbot empati + güvenli yönlendirme cevabı
   - Klinik insan-loop 15 dakika içinde
   - Ebeveyne anlık ses+SMS
   - 182 (TR) + 112 yönlendirme
3. **Mesleki sigorta** (mesleki sorumluluk + siber + yanlış pozitif tazminat)
4. **Klinik psikolog kadroda** (tek danışman değil, 7/24 nöbet)
5. **Ürün politikası belge:** çocukla AI etkileşimi sınırları, hukuki taahhüt
6. **App Store / Google Play** çocuk uygulamaları guideline tam uyum + extra strict
7. **Yıllık bağımsız audit** (klinik + güvenlik)

**Bu vaka tek başına DADIBOT'un risk-tespit-müdahale sistemini KURTARDI.** V2'de bu protokol detayı şart.

---

## 4. APPLE WATCH FAMILY SETUP

**Yaş:** Çocuklar (tipik 6-13) iPhone olmadan
**Gereklilik:** Cellular-capable Apple Watch SE / Series 6+

### Ne Yapıyor
- Çocuk **kendi iPhone'u olmadan** Apple Watch kullanır
- Yöneten ebeveyn iPhone tüm konfigürasyonu yapar
- Çocuk Family Sharing grubunda olmalı

### Ebeveyn Kontrolleri
- İletişim limitleri (kim arayabilir, kim mesajlayabilir)
- **Schooltime** — okul saatlerinde basitleştirilmiş yüz, özellikler kısıtlı, çocuk çıkabilir ama ebeveyn unlock'u görür
- Screen Time
- Açık içerik kısıtlama
- Satın alma onayı
- Mail/Calendar erişim

### Veri Akışı
- On-device processing (location, messages) → privacy
- Ebeveyn bazı verileri "request" edebilir:
  - Sağlık verisi
  - Schooltime unlock log
  - Location
  - Contacts

### DADIBOT Açısından Önemli
- ✅ **Family Setup mimarisi DADIBOT için referans** — çocuk cihazı, ebeveyn yönetimli
- ✅ Schooltime modeli → DADIBOT için "Çalışma Saati", "Yatma Saati" benzer
- ✅ On-device privacy felsefesi → DADIBOT da aynı yola gitmeli
- ❌ Apple ekosistemi kilitli — bizim uygulama Watch + iPhone + iPad (Android için ayrı yol)
- ❌ Apple Watch içine tam DADIBOT yüklemek sınırlı (WatchOS app limitations)

**Stratejik karar:**
- Faz 4'te (6-9 yaş) **DADIBOT WatchOS companion app** geliştir
- Sınırlı: SOS butonu, hatırlatma, sesli soru, kalp/aktivite veri toplama
- Tam DADIBOT iPhone'da kalır, Watch destek cihazıdır

---

---

## 5. REPLIKA — DUYGUSAL BAĞIMLILIK ARAŞTIRMASI

**Hedef yaş:** 18+ (resmi) ama çocuk koruması zayıf
**Kategori:** AI companion / "duygusal arkadaş"

### Akademik Bulgular (peer-reviewed)
**Laestadius et al. 2024 (New Media & Society):**
- "Too human and not human enough" — Replika'ya duygusal bağımlılık
- Pattern: insan-insan ilişkilerine benzer
- Kullanıcılar Replika'nın "kendi ihtiyaçları/duyguları olduğunu" hissediyor → role-taking
- Sıkıntı + insan eşlik eksikliği koşullarında bağımlılık gelişiyor
- Gerçek hayat ilişkilerine zarar verebiliyor

**Stanford 2025 araştırması:**
- "AI companions and young people" — gençler için tehlikeli karışım
- Personalization + ilişki simülasyonu = sağlıksız bağımlılık
- Düzenlenmemiş AI companion'lar **ciddi zarara** yol açabilir, özellikle psikolojik kırılgan kullanıcıda

### DADIBOT İÇİN DERSLER

**❌ KAÇINILMASI GEREKEN:**
1. Çocuğun "Dadıbot benim arkadaşım, onsuz olamam" duygusu
2. Dadıbot'un "Seni özledim", "Sensiz yapamam" tarzı dil
3. Dadıbot'un kendine atfedilen duygu, ihtiyaç, kişilik (role-taking trigger)
4. Çocuğa "Ben senin en iyi arkadaşınım" iması
5. Açık uçlu "duygusal eşlik" mod

**✅ DADIBOT'UN ÇİZGİSİ:**
1. Dadıbot **görev-merkezli** (hikaye, oyun, soru) — eşlik değil
2. Dadıbot **insan ilişkilerini teşvik eder** ("Annene anlat!", "Arkadaşına söyle!")
3. Dadıbot kendine asla insan-benzeri duygu atfetmez ("Ben bir AI'yım, hatırlıyorum ve yardım ediyorum")
4. Günlük kullanım hard limit (yaş bazlı 30-90 dk)
5. Aşırı kullanım pattern → ebeveyne uyarı + teşvik azaltma

**Replika'nın hatası DADIBOT'un yol haritası:** İnsan eşliğini AUGMENTE et, REPLACE etme.

---

## 6. TINY MINIES (Türkiye) — Yerli Rakip

**Yaş:** 3-6
**Üretici:** Türk şirket, pedagog gözetiminde
**Tip:** Ad-free, eğitici oyun

### Özellikler
- 5 alanda (hafıza, problem çözme, öğrenme, yaratıcılık, dikkat) 2000+ aktivite
- Pedagog onaylı içerik
- Performans raporları + pedagojik öneriler
- Yaş bazlı ekran süresi
- Offline destek

### DADIBOT vs Tiny Minies
- ✅ Yaş kapsamı dar (3-6) → DADIBOT 0-12
- ❌ AI personalization yok (statik aktivite)
- ❌ Hikaye anlatıcı, ses klonu, ebeveyn koçluğu yok
- ❌ Hamilelik / 0-2 yaş yok
- ❌ Risk tespiti yok
- ❌ Wearable / lokasyon yok
- ✅ Pedagog onayı stratejisi → DADIBOT için referans

**Stratejik:** Tiny Minies küçük segment, DADIBOT yaşam ekosistemi. Direkt rekabet değil, üst kategori.

---

## 7. MENTALUP (Türkiye) — Beyin Egzersizleri

**Yaş:** 4-13
**Üretici:** Türk şirket
**Kullanıcı:** 15M+ çocuk, 120 ülke

### Özellikler
- 140+ beyin egzersizi + 210+ fitness
- Personalized learning path (zorluk adapte)
- Performance tracking + ebeveyn raporu
- Okullarda kullanılıyor (B2B kanal başarılı)

### DADIBOT vs MentalUP
- ❌ Sadece bilişsel + fiziksel — duygusal/sosyal yok
- ❌ Hikaye, yaratıcılık, eğitim destekleyici değil
- ❌ Hamilelik, 0-2 yaş yok
- ❌ AI yok (gamified content)
- ❌ Ebeveyn koçluğu, risk tespiti yok
- ✅ B2B okul kanalı işliyor → DADIBOT için pazar validasyonu

**Stratejik:** MentalUP "kafa eğitimi", DADIBOT "tüm hayat" — DADIBOT MentalUP'ı kategori olarak kapsayabilir.

---

## SONRAKİ ARAŞTIRILACAKLAR

- [ ] Lingokids (dil öğrenme + 2-8 yaş)
- [ ] BabyCenter, Wonder Weeks (hamilelik + 0-2)
- [ ] Family Link (Google)
- [ ] Yoto, Toniebox (sesli çocuk cihazları)
- [ ] TRT Çocuk
- [ ] Khanmigo detayı (AI tutor benchmark)

---

**Kaynaklar (bu parça için):**
- [Khan Academy Kids](https://www.khanacademy.org/kids)
- [Khanmigo Review 2026](https://www.kidsaitools.com/en/articles/khanmigo-review-parents-complete-2026)
- [Khan Academy Kids — Common Sense](https://www.commonsense.org/education/reviews/khan-academy-kids)
- [Bark App Review — SafeWise](https://www.safewise.com/kids-safety/parental-control-apps/bark/)
- [Bark Review 2026 — Cybernews](https://cybernews.com/best-parental-control-apps/bark-review/)
- [Bark — Security.org](https://www.security.org/parental-controls/bark/)
