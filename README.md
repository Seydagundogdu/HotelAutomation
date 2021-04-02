# Hotel-Automation
PROGRAMIN AMACI VE NASIL ÇALIŞTIĞI
Yazmış olduğum program bir otel otomasyonu. Otele giriş/çıkış yapan müşterilerin kaydını alan/silen, hangi odada hangi müşterinin bulunduğunu gösteren bir program. Aynı zamanda otele alınan eşyaların ve yiyeceklerin kaydını tutan bir form da mevcut. Kayıtları tutması için Sql Server’ı kullandım. Sql Server’da 7 adet tablo oluşturdum. Bu tablolar dan birincisi sisteme giriş yapabilmeyi sağlayan kullanıcı bilgilerini tutan tablo. Daha sonra müşteri bilgilerini tutan musteriBilgileri tablosu, odaların boş mu dolu mu olduğunu gösteren odalar tablosu ve mutfakla alakalı 4 adet daha tablo mevcut.
Programın çalışma mekanizmasına gelinirse ilk çalıştırıldığında karşımıza bir giriş ekranı çıkmakta. Burada kullanıcı adı ve şifre ile sisteme giriş yapıyoruz.
Sisteme girdikten sonra karşımıza ilk olarak bir menü ekranı çıkıyor, bu ana ekran. Burada hangi işlemi yapmak istiyorsak ona uygun olan butona tıklıyoruz.
Örneğin yeni müşteri kaydı yapmak istiyorsak ‘Yeni Müşteri’ butonuna tıklıyoruz ve karşımıza müşteri kayıt ekranı geliyor.
Burada sol taraftaki groupBox’ta müşteri kaydı için gerekli bilgileri isteyen bir form mevcut bu bilgileri girip ‘ODAYI VER’ butonuna tıkladığımız an müşterinin kaydı seçilen odaya yapılmakta ve oda butonunun rengi kırmızıya dönmektedir. Eğer ana ekranda odalar butonuna tıklarsak karşımıza odaları ve bu odalarda kimlerin kaldığını gösteren bir form çıkar.
Ana ekranda müşteri bilgileri butonuna tıklamak istersek karşımıza çıkacak olan ekran aşağıdaki gibi olur. Burada kullanıcı tarafından silinmediği takdirde gelmiş geçmiş bütün müşterilerin kaydını tutmak mümkün. Aynı zamanda kayıt güncelleme, kayıt görüntüleme ve kayıt arama gibi işlem seçenekleri bulunuyor.
Ve son olarak ana ekranda mutfak butonuna tıklarsak karşımıza aşağıda form gelir. Bu formdaki datagridde iki tür bilgi görüntüleme mümkün.
Şöyle ki yukarıda bulunan radio buttonlardan oda ürünleri isimli olanı seçtiğimizde karşımıza odalar için alınan eşyalar çıkarken, mutfak ürünlerini seçtiğimizde mutfak için alınan yiyecek ve içecekler görüntülenmektedir.