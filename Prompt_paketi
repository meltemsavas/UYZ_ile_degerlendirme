# Prompt Paketi — Yapay Zekâ Destekli Dönüt Verme (MagicSchool.ai + Brisk)

Bu dosya, atölyede kullanılan ortak öğrenci ürünleri (**ürün 1 / ürün 2 / ürün 3**) için
**rubriğe dayalı** dönüt üretmek üzere hazırlanmış kopyala-yapıştır promptlarını içerir.

## Kullanım Prensipleri (kısa)
- Kişisel veri girmeyin (isim/okul vb.).
- AI çıktısı taslaktır; son düzenleme öğretmende.
- Dönütte mutlaka: **kanıt + düzeltici ipucu + somut sonraki adım** olsun.

---

## A) MagicSchool.ai — Rubrik Oluşturma Promptu (K1–K4 kriterleriyle)

**KULLANIM:** MagicSchool.ai içinde Rubric Generator (veya Rubric) aracına yapıştırın.

**PROMPT:**
Fen Bilimleri dersi için (ortaokul düzeyi) aşağıdaki **ortak kriterlere** dayalı, 4 düzeyli (4–3–2–1) bir **analitik rubrik** oluştur.

**Ortak Kriterler (değiştirmeden kullan):**
- **K1 Bilimsel doğruluk**
- **K2 Akıl yürütme (neden-sonuç)**
- **K3 Kanıt/örnek**
- **K4 Açıklık & bilimsel dil**

**Düzey mantığı:**
- **4:** doğru ve tutarlı
- **3:** küçük hata/eksik bilgi
- **2:** belirgin kavram yanılgıları
- **1:** çoğu yanlış / konu dışı

**Görev bağlamı (rubrik hangi ürün için kullanılacak?):**
- Ürün türü: [kısa yanıt / deney raporu / açık uçlu soru]  ← burayı seç ve yaz
- Konu: [ör. Hal değişimleri: buharlaşma-kaynama / Basınç ve kaynama / Deney raporu: buharlaşma hızı]  ← burayı yaz
- Sınıf düzeyi: [6 / 7]  ← burayı yaz

**İstediğim çıktı:**
1) 4 kriter x 4 düzey olacak şekilde **tablo** halinde ver.
2) Her hücrede **gözlenebilir** ve **ölçülebilir** ifadeler kullan (ör. “kavramları karıştırır”, “neden-sonuç kurar”, “en az 2 uygun örnek verir”).
3) Özellikle **düzey 1–2** için bu konuyla ilgili tipik öğrenci hatalarına yer ver (genel, soyut yazma).
4) Kısa ve net yaz: her hücre en fazla **1–2 cümle** olsun.
5) En sona “**Öğretmen notu**” başlığıyla 3 madde ekle: rubriği kullanırken dikkat edilecek noktalar (adil puanlama, kanıta dayandırma, dil düzeyi).

---

## B) Brisk — Odak/Kriter Metinleri (Google Docs üzerinde)

> Brisk’te “Give Feedback” veya benzeri bir alanda **odak/criteria** istenirse aşağıdakiler yapıştırılır.
> Çıktıyı genelde “Glow & Grow” (güçlü yön / gelişim) biçiminde isteyin.

### B1) Genel Brisk odak metni (tüm ürünler)
**ODAK METNİ:**
Rubriğe göre dönüt ver:
- K1 Bilimsel doğruluk
- K2 Neden-sonuç / akıl yürütme
- K3 Kanıt/örnek
- K4 Açıklık & bilimsel dil

Çıktı formatı:
- 2 Glow (metinden kanıtla)
- 2 Grow (her biri için “nasıl geliştirebilir?” önerisi)
- 1 düşündürücü soru
- 1 somut sonraki adım
Dili destekleyici ve öğrenci seviyesine uygun olsun.

### B2) Deney raporu için Brisk odak metni (Ürün 2)
**ODAK METNİ:**
Deney raporuna dönüt ver. Rubriğe ek olarak bilimsel süreç becerilerine odaklan:
- değişken kontrolü
- ölçüm ve tekrar
- veri-yorum tutarlılığı
- hata kaynakları ve geliştirme önerileri

Çıktı:
- 2 güçlü yön (kanıtlı)
- 3 geliştirme önerisi (ne + neden + nasıl)
- 1 somut “bir sonraki deney planı” (3 madde)

---
## LLM'ler ile değerlendirme
Aşağıdaki promptu herhangi bir LLM'de köşeli parantezle belirtilen yerleri özelleştirerek kullanabilirsin. 
ROL: Sen deneyimli bir Fen Bilimleri öğretmeni ve ölçme-değerlendirme uzmanısın.
GÖREV: Aşağıdaki “MagicSchool ile geliştirilmiş rubrik”e göre öğrenci ürününü değerlendir. Rubrik dışına çıkma; yeni kriter ekleme.

ÖNEMLİ:
- Sadece verilen rubrik kriterleri ve düzey tanımlarıyla puan ver.
- Her puanı öğrenci metninden KISA kanıt(lar)la destekle (gerekirse 5–15 kelimelik alıntı).
- Dil öğrenci seviyesine uygun ve destekleyici olsun.
- Kişisel veri/kimlik bilgisi isteme veya üretme.

GİRDİLER
1) RUBRİK (aynen yapıştır):
[BURAYA MAGIC SCHOOL’DAN GELEN RUBRİĞİ YAPIŞTIR]

2) ÖĞRENCİ ÜRÜNÜ:
- Ürün türü: [kısa yanıt / deney raporu / açık uçlu]
- Sınıf düzeyi: [6/7]
- Kazanım/Konu: [ör. buharlaşma-kaynama / basınç-kaynama / deney raporu]
- Öğrenci metni:
[BURAYA ÖĞRENCİ ÜRÜNÜNÜ YAPIŞTIR]

ÇIKTI FORMATI (AYNEN BU SIRAYLA ÜRET)
A) Rubrik Puanlama Tablosu
- Her kriter için:
  1) Puan (1–4)
  2) Rubrikteki ilgili düzey ifadesi (kısaca)
  3) Kanıt (öğrenci metninden kısa alıntı veya somut referans)
  4) Gerekçe (1–2 cümle)

B) Genel Değerlendirme
- Genel başarı düzeyi (1–4 arası, tek sayı) ve 1–2 cümlelik özet
- En kritik 1 kavram yanılgısı / hata (varsa) ve neden önemli olduğu (1 cümle)

C) Öğrenciye Dönüt (140–200 kelime)
- 2 Güçlü Yön (kanıta dayalı)
- 2 Geliştirme Önerisi (her biri “Ne + Neden + Nasıl” içersin)
- 1 Düşündürcü Soru
- 1 Somut Sonraki Adım (bir sonraki çalışmada yapılacak net görev)

D) Öğretmen İçin Kısa Not (en fazla 4 madde)
- Bu öğrenci için bir sonraki ders/etkinlikte önerilen mini müdahale (kısa)
- Ölçme-değerlendirme açısından dikkat (ör. kanıt toplama, tekrar deneme, değişken kontrolü vb.)

Şimdi değerlendir.


## D) Dönüt Kalite Kontrol Listesi (30 saniyede kontrol)
- Metinden **kanıt** var mı?
- Öğrenciye uygulanabilir **somut sonraki adım** var mı?
- Dil destekleyici mi (yargılayıcı değil)?
- Fen kazanımı/kavramı doğru hedefliyor mu?
- Öğrencinin düşünmesini sağlayan en az 1 **soru** var mı?
