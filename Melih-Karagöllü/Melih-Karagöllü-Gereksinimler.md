1. Üye Kaydı Yapma
   API Metodu: POST /auth/register



Açıklama: Sisteme yeni kullanıcıların isim, e-posta ve şifre belirleyerek yeni bir hesap oluşturmasını sağlar.


2. Meyve Listeleme
   API Metodu: GET /products



Açıklama: Satışta olan tüm kurutulmuş meyve çeşitlerinin, görselleri ve fiyatlarıyla birlikte ana sayfada görüntülenmesini sağlar.


3. Profil Güncelleme
   API Metodu: PUT /users/profile



Açıklama: Kullanıcıların kayıtlı teslimat adresi, telefon ve iletişim bilgilerini istedikleri zaman değiştirmesine olanak tanır.

4. Siparişi İptal Etme
   API Metodu: DELETE /orders/{orderId}



Açıklama: Henüz kargoya verilmemiş olan hatalı veya vazgeçilen bir siparişin sistemden tamamen kaldırılmasını sağlar.

5. Yeni Ürün Tanımlama
   API Metodu: POST /admin/products



Açıklama: Yönetici panelinden sisteme yeni bir kurutulmuş meyve türü, stok miktarı ve ürün açıklaması girilmesini sağlar.

6. Sepet Görüntüleme
   API Metodu: GET /cart



Açıklama: Kullanıcının satın almak üzere sepetine eklediği ürünlerin güncel listesini ve ödenecek toplam tutarı görmesini sağlar.


7. Ürün Fiyatı Güncelleme
   API Metodu: PUT /admin/products/{productId}



Açıklama: Stok durumuna veya kampanya dönemlerine göre seçilen ürünün birim satış fiyatının değiştirilmesini sağlar.


8. Ürünü Sepetten Çıkarma
   API Metodu: DELETE /cart/{itemId}



Açıklama: Satın alınmaktan vazgeçilen bir ürünün sepet listesinden kalıcı olarak silinmesini sağlar.


9. Sipariş Geçmişi Listeleme
   API Metodu: GET /orders/history



Açıklama: Kullanıcının daha önce tamamladığı tüm alışverişlerin detaylarını, tarihlerini ve fatura bilgilerini görüntülemesini sağlar.

10. AI Destekli Akıllı Tadım Asistanı
    API Metodu: POST /ai/recommendations



Açıklama: Kullanıcının damak tadı tercihlerine (tatlı, ekşi, kıtır vb.) göre en uygun kurutulmuş meyve karışımını öneren yapay zeka desteği sağlar.

