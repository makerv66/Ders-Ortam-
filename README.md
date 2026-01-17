# 📚 Sanal Kütüphane - Çalışma ve Odaklanma Asistanı

**Sanal Kütüphane**, evde çalışırken kütüphane disiplinini ve huzurunu hissetmek isteyenler için tasarlanmış, tarayıcı tabanlı minimalist bir üretkenlik aracıdır. Karmaşık kurulumlar gerektirmez, tek bir dosya ile çalışır.

## 🌟 Özellikler

Bu uygulama, odaklanmayı artırmak için üç temel bileşeni bir araya getirir:

### 1. ⏱️ Gelişmiş Kronometre

* **Hassas Zaman Takibi:** Çalıştığınız süreyi saniye saniye takip eder.
* **Akıllı Başlık (Title) Desteği:** Tarayıcı sekmesinde süreyi canlı olarak gösterir. Başka bir sekmede gezinirken bile süreyi görebilirsiniz.
* **Kalıcı Hafıza:** "Durdur"a bastığınızda süreyi hafızada tutar, kaldığınız yerden devam edebilirsiniz.

### 2. 🎧 Atmosferik Ortam Sesleri

Tamamen kontrol edilebilir, karıştırılabilir sesler:

* 🌧️ **Yağmur:** Huzur verici doğa sesi.
* 🔥 **Şömine:** Çıtırdayan ateş sesi.
* ☕ **Kafe Uğultusu:** Sosyal izolasyonu kırmak için hafif arka plan gürültüsü.
* **Ses Mikseri:** Her sesin seviyesini ayrı ayrı ayarlayarak kendi ideal atmosferinizi yaratabilirsiniz (Örn: %20 Yağmur + %50 Şömine).

### 3. 📝 Dinamik Yapılacaklar Listesi (To-Do)

* Günlük hedeflerinizi ekleyin.
* Tamamlanan görevlerin üzerini tek tıkla çizin.
* Gereksiz görevleri listeden silin.

### 4. 🎨 Tasarım

* **Glassmorphism UI:** Modern, buzlu cam görünümlü şık paneller.
* **Kütüphane Teması:** Arka planda yüksek çözünürlüklü, motive edici kütüphane görseli.

---

## 🚀 Kurulum ve Kullanım

Bu proje herhangi bir sunucu kurulumu veya kütüphane (React, Vue vb.) gerektirmez. Saf **HTML, CSS ve JavaScript** ile yazılmıştır.

### Nasıl Çalıştırılır?

1. Proje dosyasını indirin veya `index.html` (veya `calisma.html`) dosyasını bilgisayarınıza kaydedin.
2. Dosyaya **çift tıklayın**.
3. Uygulama varsayılan internet tarayıcınızda (Chrome, Edge, Firefox vb.) açılacaktır.
4. İnternet bağlantısı sadece ilk açılışta (arka plan resmi ve sesleri yüklemek için) gereklidir.

---

## 🛠️ Özelleştirme (Geliştiriciler İçin)

Projeyi kendi zevkinize göre düzenlemek isterseniz, HTML dosyası içindeki ilgili yerleri değiştirebilirsiniz:

### Arka Planı Değiştirme

`style` etiketi içindeki `body` kısmını bulun:

```css
body {
    /* Buradaki URL'yi istediğiniz bir resim linkiyle değiştirin */
    background: url('YENI_RESIM_LINKI_BURAYA') ...;
}

```

### Sesleri Değiştirme

HTML içindeki `<audio>` etiketlerini bulun ve `src` kısımlarını kendi ses dosyalarınızla veya farklı URL'lerle değiştirin:

```html
<audio id="audio-rain" loop>
    <source src="DOSYA_YOLU_VEYA_URL" type="audio/ogg">
</audio>

```

---

## 📂 Dosya Yapısı

```
Sanal-Kutuphane/
│
├── index.html       # Tüm uygulamanın (HTML/CSS/JS) bulunduğu tek dosya
└── README.md        # Proje dökümantasyonu (Bu dosya)

```

---

## 🔗 Kaynaklar ve Krediler

* **Arka Plan Görseli:** [Unsplash](https://unsplash.com) (Kütüphane fotoğrafı).
* **Ses Efektleri:** Google Actions Sound Library (Ücretsiz ve telifsiz kullanım).
* **Fontlar:** Sistem varsayılan serif fontları (Georgia, Times New Roman).

---

## 🤝 Katkıda Bulunma

Bu proje açık kaynaklıdır ve geliştirmeye açıktır.

1. Fork edin.
2. Özellik ekleyin (Örn: Pomodoro sayacı, Dark mode).
3. Pull Request gönderin.

**İyi Çalışmalar! 🎓**
