# XSS-ZAF-YETL-KOD-RNE-
XSS Stored Zafiyeti

Kod açığı xss türlerinden stored türünü içerir.Stored xss, bilgisayar korsanları yüklerini güvenliği ihlal edilmiş bir sunucuda depoladığında saldırılar gerçekleşir. Genellikle zarar veren bir XSS saldırı yöntemidir. Saldırgan, yüklerini hedef uygulamaya enjekte etmek için bu yaklaşımı kullanır. Uygulamanın giriş doğrulaması yoksa, kötü amaçlı kod, uygulama tarafından veri tabanı gibi bir konumda kalıcı olarak depolanır veya kalıcı olur. Pratikte bu, saldırganın bir blog veya forum gönderisindeki yorum bölümleri gibi kullanıcı giriş alanlarına kötü amaçlı bir komut dosyası girmesine olanak tanır.

Saldırganın yükü, virüslü sayfayı açtığında, tarayıcısında meşru bir yorumun görünmesiyle aynı şekilde, kullanıcının tarayıcısına sunulur. Hedeflenen kişiler, sayfayı tarayıcılarında görüntülediklerinde yanlışlıkla kötü amaçlı komut dosyasını yürütürler.

Owaps kategorisi -> A03:2021-Injection -> Stored XSS Attacks

CVSS --> CNA:  Atlassian Base Score: 8.5 HIGH -> Vector:  CVSS:3.0/AV:N/AC:L/PR:L/UI:N/S:C/C:H/I:L/A:N


https://github.com/user-attachments/assets/730bca93-c7c2-4063-acb6-2ae5b9e68b33

