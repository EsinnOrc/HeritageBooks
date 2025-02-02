# 📚 HeritageBooks

HeritageBooks, klasik ve değerli kitapların keşfedilmesini sağlayan bir web sitesidir. Kullanıcılar, yazar ve kategori bazlı filtreleme yaparak geniş bir koleksiyona göz atabilirler. Bu proje, **Turkcell Geleceği Yazanlar** kapsamında bir ödev olarak geliştirilmiştir.

---

## 🚀 Proje Özellikleri

- **Kitap Keşfi:** Kullanıcılar, tarihi ve kültürel öneme sahip kitapları inceleyebilir.
- **Filtreleme:** Kitapları yazara veya kategoriye göre filtreleyebilir.
- **Kitap için Crud işlemleri (Ekleme/silme/Güncelleme):** Kullanıcılar, koleksiyona yeni kitaplar ekleyebilir.
- **Arama Fonksiyonu:** Kullanıcılar, kitap ismi ve yazar ismine göre arama yapabilir.
- **Sıralama Seçenekleri:** Kitaplar, alfabetik olarak veya yayın yılına göre sıralanabilir.
  sunulmaktadır.

---

## 🛠 Kullanılan Teknolojiler

- **HTML, CSS, SCSS:** Web arayüzü ve tasarımı için kullanılmıştır.
- **JavaScript:** Dinamik bileşenler için kullanılmıştır.
- **Bootstrap 5:** Responsive tasarım ve bileşenler için entegre edilmiştir.
- **JSON Server:** Sahte bir API servisi oluşturularak veri yönetimi sağlanmıştır.

---

## 📥 Kurulum

### 1️⃣ Gerekli Bağımlılıkları Yükleyin

Öncelikle, projenin çalışması için gerekli olan bağımlılıkları yükleyin:

```bash
npm install
```

### 2️⃣ SCSS Dosyalarını İzleyin

SCSS dosyalarının değişikliklerini otomatik olarak takip etmek için:

```bash
npm run sass
```

### 3️⃣ JSON Server'ı Çalıştırın

Veri tabanı olarak JSON Server'ı kullanıyoruz. Aşağıdaki komutu çalıştırarak başlatabilirsiniz:

```bash
npx json-server --watch db.json --port 3001
```

### 4️⃣ Projeyi Tarayıcıda Açın

**index.html** dosyasını doğrudan tarayıcınızda açarak projeyi görüntüleyebilirsiniz.

---

## 📌 Kullanım

1. **Ana Sayfa:** Kullanıcılar, önerilen kitapları görebilir.
2. **Kitap Arama:** Sayfanın üst kısmındaki arama kutusunu kullanarak kitap veya yazar adına göre arama yapılabilir.
3. **Filtreleme:** Yazar veya kategori bazında kitapları filtreleyebilirsiniz.
4. **Kitap Ekleme:** "Add to Book +" butonuna basarak yeni bir kitap ekleyebilirsiniz.
5. **Kitap Güncelleme:** Mevcut kitabı güncellemek için ilgili kitabın düzenleme butonunu kullanabilirsiniz.
6. **Kitap Silme:** Mevcut kitabı silmek için ilgili kitabın silme butonunu kullanabilirsiniz.

---
