# SEM Chatbot Deneme Projesi

**🚀 Canlı Demo / Live Demo:** [https://yusufdolek.github.io/SEMChatbot/](https://yusufdolek.github.io/SEMChatbot/)

SEM Chatbot projesi, SEM’in hizmetlerini tanıtmak amacıyla geliştirilen yapay zekâ destekli bir sohbet asistanıdır. İlk aşamada şirketimizi ve sunduğumuz dijital pazarlama çözümlerini tanıtan bu chatbot, ilerleyen süreçlerde tamamlanan projelerimiz hakkında da detaylı bilgi verebilecek şekilde geliştirilecektir.

## Yapılacaklar (To-Do List)

1.  **Intent Ayarlama:**
    *   Formun açılmasını tetikleyen "hi" kelimesi yerine, Dialogflow'da özel bir Intent oluşturulacak.
    *   HTML tarafındaki JavaScript, bu özel Intent'in Dialogflow tarafından tetiklenmesi durumunda (örneğin, Dialogflow'dan gönderilecek özel bir olay/payload ile) modalı açacak şekilde güncellenecek.

2.  **2.4 Eğitimi Tekrarı ve Özeti:**
    *   Belirtilen "2.4 eğitimi" tekrar edilecek.
    *   Bu eğitimden önemli noktaları ve öğrenilenleri içeren bir özet hazırlanacak.

3.  **Formun Google E-Tablosu Bağlantısını Kontrol Etme:**
    *   Modal içinde gösterilen Google Form'un yanıtlarının, beklendiği gibi ilişkili Google E-Tablosu'na doğru ve eksiksiz bir şekilde kaydedildiği teyit edilecek.

4.  **Referans Video İzleme:**
    *   Öğrenme veya referans amacıyla [şu YouTube videosu](https://www.youtube.com/watch?v=3kZgoNoE8ts) izlenecek.

5.  **Dialogflow CX Dokümantasyonunu Gözden Geçirme:**
    *   Dialogflow CX'in resmi dokümantasyonu ([https://cloud.google.com/dialogflow/cx/docs](https://cloud.google.com/dialogflow/cx/docs)) tekrar okunarak bilgiler tazelenecek ve projedeki olası iyileştirme alanları için fikir edinilecek.

6.  **Prompt'ları Kontrol Etme:**
    *   Dialogflow agent'ında kullanılan tüm kullanıcıya yönelik metinler (prompt'lar, yanıtlar, sorular vb.) gözden geçirilecek.
    *   Anlaşılırlık, doğallık ve kullanıcı deneyimi açısından iyileştirmeler yapılacak.

7.  **Modal Açılmadan Önce Bilgilendirme:**
    *   Modal açılmadan hemen önce, Dialogflow üzerinden kullanıcıya neden form doldurması gerektiği hakkında kısa bir bilgilendirme yapılabilir (örneğin, "Size daha iyi yardımcı olabilmem için birkaç bilgiye ihtiyacım var. İletişim formunu açıyorum.").

8.  **Yapıldı:Form Gönderimi Sonrası Chatbot Onayı:**
    *   Google Form gönderildikten sonra (bu iframe içinde olduğu için doğrudan yakalamak zor olabilir, ancak kullanıcıya bilgi verilebilir), chatbot'un kullanıcıya "Formunuzu aldık, teşekkürler!" gibi bir onay mesajı vermesi sağlanabilir. Bu, Dialogflow'da form açıldıktan sonraki akışa eklenebilir.
    *   Şuan form kapandıktan sonra mesaj atıyor. Formun doldurulup doldurulmadığı kontrol edilmiyor. Daha kalıcı bir çözüm için webhook gibi sistem kullanılması gerekli. 
    *   Not: Eğer google form yerine html formu kullanırsak işimiz daha kolay. Gönder buttonuna tıklandıktansa mesajı dönebiliriz.