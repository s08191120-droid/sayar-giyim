# Sayar Giyim - Kapıda Ödeme Mağazası

Bu sürümde online ödeme kaldırılmıştır. Siparişler yalnızca **Kapıda Ödeme** olarak alınır.

## Dahil olanlar
- Ürün listeleme, arama ve kategori filtresi
- Sepet ve stok kontrolü
- Kapıda ödeme sipariş formu
- Sipariş numarası
- PostgreSQL veritabanı
- Güvenli admin oturumu ve şifre hashleme
- Yönetim paneli: siparişler, durum değiştirme, ürün ekleme/düzenleme/gizleme, stok
- Basit istatistikler
- İsteğe bağlı WhatsApp Cloud API sipariş bildirimi
- Gizlilik, iade/değişim ve satış şartları sayfaları
- Sitemap
- Express 5 uyumlu fallback route

## Kurulum
1. Node.js yükle.
2. `npm install`
3. `.env.example` dosyasını `.env` olarak kopyala.
4. PostgreSQL bağlantısını ve güçlü admin bilgilerini gir.
5. `npm start`

## Önemli
- Gerçek satışa geçmeden önce domain, HTTPS, kargo/kapıda tahsilat anlaşması, işletme bilgileri ve hukuki metinleri tamamla.
- WhatsApp token gibi gizli bilgileri site koduna koyma; yalnızca hosting ortam değişkenlerinde sakla.
- Admin şifresini kimseyle paylaşma.
- Kapıda ödeme siparişi almak, kargo firmasının kapıda tahsilat hizmetiyle otomatik olarak aynı şey değildir; ilgili kargo/lojistik hizmetini ayrıca etkinleştirmen gerekir.
