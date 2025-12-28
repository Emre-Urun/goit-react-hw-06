# 📘 Phonebook App (Redux Toolkit & Persist)

<div align="center">

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Redux](https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)

<br />

**Kişilerinizi güvenle saklayın, filtreleyin ve yönetin.** Modern React mimarisi ve Redux durum yönetimi ile geliştirilmiştir.

[Canlı Önizleme (Demo) Görüntüle](https://goit-react-hw-06-eight.vercel.app/) · [Hata Bildir](https://github.com/Emre-Urun/goit-react-hw-06/issues)

</div>

---

## 📑 İçindekiler

- [Proje Hakkında](#-proje-hakkında)
- [Özellikler](#-özellikler)
- [Teknoloji Yığını](#-teknoloji-yığını)
- [Proje Mimarisi](#-proje-mimarisi)
- [Kurulum ve Çalıştırma](#-kurulum-ve-çalıştırma)
- [Geliştirici](#-geliştirici)

---

## 📖 Proje Hakkında

Bu proje, **GoIT React Bootcamp - 6. Modül** bitirme ödevi olarak geliştirilmiştir. Uygulamanın temel amacı, React ekosistemindeki global durum yönetimi (Global State Management) aracı olan **Redux Toolkit**'in yeteneklerini sergilemektir.

Kullanıcılar yeni kişi ekleyebilir, mevcut kişileri silebilir ve anlık olarak isimle arama yapabilirler. **Redux Persist** entegrasyonu sayesinde, tarayıcı yenilense veya kapatılsa bile veriler kaybolmaz, `localStorage` üzerinde güvenle tutulur.

---

## ✨ Özellikler

| Özellik | Açıklama |
| :--- | :--- |
| 🗂️ **Merkezi Yönetim** | Tüm veriler Redux Store üzerinde tek bir merkezden yönetilir. |
| 💾 **Veri Kalıcılığı** | `redux-persist` sayesinde veriler tarayıcı hafızasında saklanır. |
| 🔍 **Anlık Filtreleme** | Kullanıcı yazı yazdığı anda liste dinamik olarak filtrelenir. |
| ⚡ **Hızlı & Reaktif** | Vite altyapısı sayesinde yüksek performanslıdır. |
| 🎨 **Modern Arayüz** | CSS Modules kullanılarak responsive ve şık bir tasarım sunar. |
| ✅ **Validasyon** | Formik ve Yup ile hatalı veri girişleri (kısa isim, boş numara) engellenir. |

---

## 🛠 Teknoloji Yığını

Bu projede aşağıdaki kütüphaneler ve teknolojiler kullanılmıştır:

* **Çekirdek:** React 18, Vite
* **Durum Yönetimi:** @reduxjs/toolkit, react-redux
* **Veri Saklama:** redux-persist
* **Form Yönetimi:** Formik
* **Şema Doğrulama:** Yup
* **Stil:** CSS Modules, Modern Normalize
* **İkonlar:** React Icons (`react-icons/fa`)
* **ID Üretimi:** nanoid

---

## 📂 Proje Mimarisi

Uygulama, sürdürülebilirlik ve okunabilirlik için modüler bir yapıda tasarlanmıştır:

```bash
src/
├── 📂 components/          # React Bileşenleri
│   ├── 📂 Contact/         # Tekli kişi kartı görünümü
│   ├── 📂 ContactForm/     # Kişi ekleme formu ve validasyon
│   ├── 📂 ContactList/     # Kişilerin listelendiği ve filtrelendiği alan
│   └── 📂 SearchBox/       # Arama input alanı
├── 📂 redux/               # Redux Mantığı
│   ├── 📄 contactsSlice.js # Kişi ekleme/silme reducer'ları
│   ├── 📄 filtersSlice.js  # Arama filtresi reducer'ı
│   └── 📄 store.js         # Store konfigürasyonu ve Persist ayarları
├── 📄 App.jsx              # Ana Layout
└── 📄 main.jsx             # Provider ve PersistGate sarmalayıcıları

## 🚀 Kurulum ve Çalıştırma
1. Projeyi kendi bilgisayarınızda çalıştırmak için aşağıdaki adımları izleyin:
```bash
git@github.com:Emre-Urun/goit-react-hw-06.git
```
2.Gerekli Paketleri Yükleyin:
```bash
npm install
```
3.Uygulamayı Başlatın:
```bash
npm run dev
```
4.Tarayıcıda Açın: Terminalde verilen yerel sunucu adresine `(genellikle http://localhost:5173)` gidin.

## 🤝 Katkıda Bulunma

Bu proje açık kaynaklıdır ve geliştirmeye açıktır. Herhangi bir hata fark ederseniz veya özellik eklemek isterseniz:

1. Bu repoyu Fork'layın.
  
2. Yeni bir dal (branch) oluşturun (`git checkout -b ozellik/yeni-ozellik`).

3. Değişikliklerinizi yapın ve Commit'leyin (`git commit -m 'Yeni özellik eklendi'`).

4. Dalınızı Push'layın (`git push origin ozellik/yeni-ozellik`).

5. Bir Pull Request oluşturun.

## 👨‍💻 Geliştirici

Bu proje Emre Ürün tarafından React öğrenme sürecinin bir parçası olarak geliştirilmiştir.

Eğer bu projeyi beğendiyseniz ⭐️ vermeyi unutmayın!
