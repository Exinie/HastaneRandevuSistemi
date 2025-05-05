
# 📄 Proje Önerisi

  

## ⚒️ Ekip Üyeleri

  

| Ad - Soyad |  Numarası |
|----------------------|-------------------|
| [Erdem Ural]           | [[gizlendi]]          |
| [Ege Yardımcı]           | [[gizlendi]]          |
| [Yiğit Yıldız]           | [[gizlendi]]          |
| [Nuh Mehmet Turhan]           | [[gizlendi]]          |

  

---

  

## 📚 Proje Tanımı

  

Hastaneler için randevu / otomasyon sistemi.

  

---

  

## 🛠️ Görev Dağılımı

  

| Ad - Soyad | Sorumlu Olduğu Bölüm / Görev       |
|----------------------|------------------------------------|
| [Erdem Ural]           | Python backend – API geliştirme, oturum işlemleri |
| [Ege Yardımcı]           | Veri tabanı – tablo yapısı, sorgular, ilişki düzeni |
| [Yiğit Yıldız]           | Ön yüz – HTML/CSS/JS, kullanıcı arayüzü, responsive tasarım |
| [Nuh Mehmet Turhan]           | Ön yüz – HTML/CSS/JS, kullanıcı arayüzü, responsive tasarım |

  

---

  

## ✅ Proje Gerekliliklerine Uyum ve Planlanan Uygulama

  

Aşağıdaki her proje gerekliliği için, nasıl karşılanacağını kısa bir açıklamayla belirtiniz.

  

### 1. Genel Proje Çalışma Sistemi

Kullanıcı web sayfasından işlemler yapabilecek, menüler arasında web sayfaları üzerinden geçiş yapacak ve bu web sayfalarından API ile iletişime geçecek.

  

### 2. Veri Tabanı Kullanımı

Kullanılacak veri tabanı SQLite olacaktır. Saklanacak veriler şu şekildedir: hasta / doktor kullanıcı bilgileri, rolleri, randevuları, tahlil sonuçları; yönetici kullanıcı bilgileri, log kayıtları.

  

### 3. Kullanıcı Yönetimi (Farklı Kullanıcı Tipleri)

Hasta : Hasta kullanıcı kaydı yapabilir. Randevu oluşturabilir. Tahlil sonuçlarına bakabilir.
Doktor : Randevuları görüntüleyebilir, onaylayabilir. Hastanın sağlık bilgilerini görüntüleyebilir, hastaya ilaç yazabilir, hastaya tahlil sonucu girebilir. 
Yönetici : Tüm kullanıcıların bilgilerini, randevularını, yazılan ilaçları, tahlil sonuçlarını görüntüleyebilir, düzenleyebilir, silebilir. Log kayıtlarını görüntüleyebilir.



### 4. İşlem Kayıtları

Kullanıcıdan gelen web sayfasından API'ye giden veriyi arka yüz işleyecek ve veritabanına kaydedecek.

  

### 5. Raporlama

Kullanıcılar web sitesine girecek, daha önceden oluşturduğu kullanıcının girişini yapacak, ve ilgili web sayfalarından edinmek istediği raporu elde edecek.
  

### 6. Grup Çalışması Kriterleri

- Veri tabanı işlemlerinin özel bir veri tabanı sınıfı üzerinden gerçekleştirilmesi.
- API entegrasyonu yapılarak gerçek zamanlı veri kullanımı.
- Projeye bir görsel arayüz eklenmesi. (Örneğin: Tkinter, PyQt, Streamlit gibi araçlarla)
- Kullanıcının sisteme dosya yükleyebilmesi, dosya kaydedebilmesi veya veri çıktısı alabilmesi. (Örneğin: PDF/CSV rapor oluşturma)
- Admin kullanıcılarının, diğer kullanıcıların yetkilerini değiştirebileceği basit bir yönetim paneli oluşturulması.
- Sistemde oturum açan kullanıcıların tüm işlemlerinin ve bu işlemlere ait tarih/saat bilgilerinin kaydedilmesi.
  


---

  

# 📌 Not:

- Bu dosya **docs/proje_onerisi.md** yolunda saklanmalıdır ardından bu taslak dosyası silinmelidir.

- Belirtilen tüm başlıklar eksiksiz doldurulmalıdır.

- Gereklilikler yüzeysel değil, projenize özgü ve uygulanabilir şekilde açıklanmalıdır.
