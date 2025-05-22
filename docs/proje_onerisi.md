
# 📄 Proje Önerisi

  

## ⚒️ Ekip Üyeleri

  

| Ad - Soyad |  Numarası |
|----------------------|-------------------|
| Erdem Ural           | [gizlendi]          |
| Ege Yardımcı           | [gizlendi]          |
| Yiğit Yıldız           | [gizlendi]          |
| Nuh Mehmet Turhan           | [gizlendi]          |

  

---

  

## 📚 Proje Tanımı

  

Hastane randevu / otomasyon sistemi.

  

---

  

## 🛠️ Görev Dağılımı

  

| Ad - Soyad | Sorumlu Olduğu Bölüm / Görev       |
|----------------------|------------------------------------|
| Erdem Ural           | Oturum ve kullanıcı işlemleri modülü, Tkinter arayüz kodlaması |
| Ege Yardımcı           | Veri tabanı şeması, Hasta kullanıcılarının işlemlerinin modülü |
| Yiğit Yıldız           | Tkinter arayüz kodlaması, Doktor kullanıcılarının işlemlerinin modülü |
| Nuh Mehmet Turhan           | Tkinter arayüz kodlaması, Yönetici kullanıcılarının işlemlerinin modülü |

  

---

  

## ✅ Proje Gerekliliklerine Uyum ve Planlanan Uygulama

  


  

### 1. Genel Proje Çalışma Sistemi

Kullanıcı program arayüzünden işlemler yapabilecek, menüler arasında görüntülenen penceredeki butonlar veya diğer elemenler üzerinden gezinebilecek ve bu pencerelerdeki elementler üzerinden ilgili modüller / API ler ile iletişime geçip veri alışverişi yapacak.

  

### 2. Veri Tabanı Kullanımı

Kullanılacak veri tabanı SQLite olacaktır. Saklanacak veriler şu şekildedir:\
Hasta kullanıcı bilgileri: tc_no, sifre, ad, soyad, bilinen rahatsızlıklar.\
Doktor kullanıcı bilgileri: tc_no, sifre, ad, soyad, uzmanlik.\
Yönetici kullanıcı bilgileri: kullanici_adi, sifre.\
Log kayıtları: kullanici_id, kullanici_tipi, islem, tarih

  

### 3. Kullanıcı Yönetimi (Farklı Kullanıcı Tipleri)

Hasta : Hasta kullanıcı kaydı yapabilir. Randevu oluşturabilir. Tahlil sonuçlarına bakabilir.\
Doktor : Randevuları görüntüleyebilir, onaylayabilir. Hastanın sağlık bilgilerini görüntüleyebilir, hastaya ilaç yazabilir, hastaya tahlil sonucu girebilir.\
Yönetici : Tüm kullanıcıların bilgilerini, randevularını, yazılan ilaçları, tahlil sonuçlarını görüntüleyebilir, düzenleyebilir, silebilir. Log kayıtlarını görüntüleyebilir.



### 4. İşlem Kayıtları

Kullanıcı tarafından programın arayüzünden yapılan işlemler sonucu ilgili modüllere iletilen veriler ilgili modülde kontrol edilip işlenecek ve veritabanına kaydı gerçekleştirilecek.
  


### 5. Raporlama

Kullanıcı programı çalıştıracak, daha önceden oluşturduğu kullanıcının bilgileri ile sisteme giriş yapacak, kullanıcı tipine bağlı olarak tahlil sonuçlarını görüntüleyip indirme veya log kayıtlarını görüntüleyip indirme gibi işlemleri gerçekleştirebilecek ve bu şekilde rapor edinmiş olacak.


### 6. Grup Çalışması Kriterleri

- Veri tabanı işlemlerinin özel bir veri tabanı sınıfı üzerinden gerçekleştirilmesi.
- API entegrasyonu yapılarak gerçek zamanlı veri kullanımı.
- Projeye bir görsel arayüz eklenmesi. (Örneğin: Tkinter, PyQt, Streamlit gibi araçlarla)
- Kullanıcının sisteme dosya yükleyebilmesi, dosya kaydedebilmesi veya veri çıktısı alabilmesi. (Örneğin: PDF/CSV rapor oluşturma)
- Admin kullanıcılarının, diğer kullanıcıların yetkilerini değiştirebileceği basit bir yönetim paneli oluşturulması.
- Sistemde oturum açan kullanıcıların tüm işlemlerinin ve bu işlemlere ait tarih/saat bilgilerinin kaydedilmesi.
