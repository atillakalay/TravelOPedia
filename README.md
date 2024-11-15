# TravelOPedia

TravelOPedia, kullanıcıların seyahat destinasyonlarını ekleyip yönetebileceği bir web uygulamasıdır. Kullanıcılar, şehir ve ülke bilgilerini girerek yeni destinasyonlar ekleyebilir, mevcut destinasyonları güncelleyebilir veya silebilirler. Uygulama, kullanıcıların seyahat planlamalarına yardımcı olmayı amaçlamaktadır.

## Özellikler

- 🌍 Kullanıcı dostu arayüz
- ✈️ Destinasyon ekleme, güncelleme ve silme
- 🎒 Rastgele seyahat önerileri
- 🌐 Çoklu dil desteği (Türkçe ve İngilizce)
- 🗺️ Kullanıcıların seyahat geçmişini kaydetme ve görüntüleme

## Kullanılan Teknolojiler

- **Frontend:**
  - ⚛️ React: Kullanıcı arayüzü oluşturmak için
  - 🔄 Redux: Uygulama durumunu yönetmek için
  - 🚦 React Router: Sayfalar arasında geçiş yapmak için
  - 🎨 Bootstrap: Responsive tasarım için
  - 🌐 i18next: Çoklu dil desteği için
  - 📢 React Toastify: Kullanıcı bildirimleri için

- **Backend:**
  - 🗄️ [json-server](https://github.com/typicode/json-server): Hızlı bir REST API oluşturmak için kullanılır. Veritabanı olarak `db.json` dosyasını kullanır.

## Kurulum

1. **Depoyu klonlayın:**
   ```bash
   git clone https://github.com/atillakalay/travelopedia.git
   cd travelopedia
   ```

2. **Gerekli paketleri yükleyin:**
   ```bash
   npm install
   ```

3. **Veritabanını başlatın:**
   ```bash
   npx json-server --watch db.json
   ```

4. **Uygulamayı başlatın:**
   ```bash
   npm start
   ```

5. **Tarayıcınızda `http://localhost:3000` adresine gidin.**

## Kullanım

- Uygulama açıldığında, "Destinasyon Ekle" bölümüne gidin.
- Şehir ve ülke bilgilerini girin ve "Ekle" butonuna tıklayın.
- Eklediğiniz destinasyonlar, "Seyahat Listesi" bölümünde görüntülenecektir.
- Mevcut destinasyonları güncellemek veya silmek için ilgili butonları kullanabilirsiniz.
- Rastgele bir seyahat önerisi almak için "Rastgele Seyahat Önerisi" bölümüne göz atın.

## Katkıda Bulunma

Katkıda bulunmak isterseniz, lütfen aşağıdaki adımları izleyin:

1. Depoyu fork edin.
2. Yeni bir dal oluşturun (`git checkout -b feature/ÖzellikAdı`).
3. Değişikliklerinizi yapın ve commit edin (`git commit -m 'Yeni özellik ekle'`).
4. Dalınızı gönderin (`git push origin feature/ÖzellikAdı`).
5. Bir pull isteği oluşturun.
