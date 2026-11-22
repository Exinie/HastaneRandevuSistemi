# Hastane Randevu Otomasyon Sistemi

Python ve Tkinter ile geliştirilmiş, hasta, doktor ve yönetici rollerine sahip bir hastane randevu sistemi. Ders kapsamında dört kişilik bir grup tarafından final projesi olarak hazırlanmıştır.

Geliştirme süresi: 09.05.2025 - 06.06.2025

## Özellikler

Hasta
- Sisteme kayıt olabilir ve giriş yapabilir.
- Doktorları listeleyip randevu alabilir, mevcut randevularını iptal edebilir.

Doktor
- Kendisine atanan randevuları listeleyebilir.
- Randevuları onaylayabilir, tamamlandı olarak işaretleyebilir veya iptal edebilir.

Yönetici
- Hasta, doktor ve yönetici hesaplarını listeleyebilir, ekleyebilir ve silebilir.
- Sistemdeki işlem kayıtlarını görüntüleyebilir ve CSV olarak dışa aktarabilir.

## Kurulum

Gereksinimler:
- Python 3
- Tkinter (Linux ortamlarında ayrıca kurulması gerekebilir)
- tkcalendar

1. Sanal ortam oluşturun ve etkinleştirin:

```bash
python -m venv .venv
```

```bash
# Windows:
.venv\Scripts\activate

# Linux / macOS:
. .venv/bin/activate
```

2. Bağımlılıkları yükleyin:

```bash
pip install -r requirements.txt
```

3. Programı başlatın:

```bash
python main.py
```

Varsayılan yönetici hesabı: kullanıcı adı `admin`, şifre `123`

## Proje Yapısı

| Dosya | Açıklama |
| --- | --- |
| `main.py` | Uygulamanın giriş noktası. Tüm Tkinter pencerelerini ve arayüz akışını yönetir. |
| `veritabani_kurulumu.py` | SQLite veritabanını ve tabloları oluşturur. |
| `oturum_islemleri.py` | Kayıt, giriş, çıkış ve oturum yönetimi. |
| `hasta_islemleri.py` | Randevu alma, listeleme ve iptal etme. |
| `doktor_islemleri.py` | Doktorun randevularını listeleme ve güncelleme. |
| `yonetici_islemleri.py` | Kullanıcı ekleme ve silme, log görüntüleme ve dışa aktarma. |
| `log_islemleri.py` | İşlem kayıtlarının veritabanına yazılması. |

Geliştirme sürecinde hazırlanan taslaklar `docs/taslaklar` dizinindedir.

## Ekip

Her üye, sorumlu olduğu modülün hem servis katmanını hem de Tkinter arayüz katmanını geliştirmiştir.

| Ad Soyad | Sorumlu Olduğu Bölüm |
| --- | --- |
| Erdem Ural | Oturum yönetimi, kullanıcı kayıt ve giriş işlemleri, log modülü |
| Ege Yardımcı | Veritabanı şeması ve kurulumu, hasta işlemleri modülü |
| Yiğit Yıldız | Doktor işlemleri modülü |
| Nuh Mehmet Turhan | Yönetici işlemleri modülü |
