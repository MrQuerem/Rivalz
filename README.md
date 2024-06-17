# Rivalz
Teşvikli Rivalz Node Kurulumu

# Öncelikle Rivalz hesabı oluşturup, node için hazırlıklı olalım.
[Buradan](https://rivalz.ai?r=motleyhuman)  hesap oluşturalım.

EVM cüzdanı, DC ve X hesaplarını bağlayalım. Siteyi kurcalayıp biraz bilgi sahibi ol.

NFT mint  Post like gibi sosyal görevler falan olabiliyor, takip edelim.




Kurulumu Hetzner'e göre anlatıyorum.
En düşük özellikli sunucuda kurabilirsiniz ama sunucunuz ne kadar güçlüyse o kadar çok puan kazanırsınız.


# Sunucuya Windows Kuruyoruz
Sunucuya giriş yaptıktan sonra;

1-) ISO Images tıkla,

2-) Arama kutusuna "2019" yazıp "enter" bas,

3-) Windows Server 2019 English satırında "Mount" butonuna tıkla,

4-) 4 numaradaki "Console" ikonuna tıkla.

![1](https://github.com/MrQuerem/Rivalz/assets/172882082/cda25434-13ee-4017-9605-7514edb2d4dc)




4 numaradaki "Console" ikonuna tıklayınca sunucuna erişeceğin yeni bir pencere açılacak.

1_) GUI-Mode seçeneğini işaretle,

2_) Ctrl+Alt+Del butonunu tıkla

![2](https://github.com/MrQuerem/Rivalz/assets/172882082/485f449a-131d-4ca2-9ea3-1bf51d701823)




Açılan pencerede hiçbirşey değişmeden "Next" butonuna bas.

![3](https://github.com/MrQuerem/Rivalz/assets/172882082/879184f0-160b-4864-a5e8-f40d82574be2)




Açılan pencerede "Install" butonuna bas

![4](https://github.com/MrQuerem/Rivalz/assets/172882082/f410f2d0-93c7-42a0-8589-448346f4cba0)



Açılan pencerede 1 numaradaki "I accept the license terms" seçeneğini işaretle

"Next" butonuna tıkla,

![5](https://github.com/MrQuerem/Rivalz/assets/172882082/eaf6b429-ccf5-4d49-9ffc-fd6fdd9c02a0)


Açılan pencerede 2 numaradaki Windows Server 2019 Standard (Desktop Experince) satırını işaretle,

"Next" butonuna tıkla,
![6](https://github.com/MrQuerem/Rivalz/assets/172882082/80d0195b-26b3-4e2e-9879-6d8d92066229)



Açılan pencerede "Custom: Install Windows only" seçeneğine tıkla,
![7](https://github.com/MrQuerem/Rivalz/assets/172882082/56635ae9-c4f0-432f-ab63-771ee7d07115)



Hetzner sunucu paneline geri dön,

1-) ISO Images tıkla,

2-) Arama kutusuna "virtio" yazıp "enter" bas,

3-) virtio-win-0.1.240.iso satırında "Mount" butonuna tıkla,

4-) 4 numaradaki "Console" ikonuna tıkla.
![8](https://github.com/MrQuerem/Rivalz/assets/172882082/79ad5781-7a69-48ca-a935-7281a3787ddb)


Sunucu konsolüne geri dön, "Load Driver" butonuna tıkla,
![9](https://github.com/MrQuerem/Rivalz/assets/172882082/8c99f8f9-d657-4fa4-b7cd-7505af69421f)


Açılan pencerede "OK" butonuna bas,
![10](https://github.com/MrQuerem/Rivalz/assets/172882082/1ba46e78-ae10-4808-8d87-16d6c324b4ae)


Açılan pencerede 1 numarayla işretlenen satırı seç ve "Next" butonuna bas,
![11](https://github.com/MrQuerem/Rivalz/assets/172882082/d19cb826-5545-4d67-8b73-83ce6891fe9f)


Açılan pencerede 3 adet driver var, hepsini sırayla "Delete" butonu ile sil,
![12](https://github.com/MrQuerem/Rivalz/assets/172882082/ac35241d-d198-4ffc-9cf6-7d5eb3b02960)


Silme işlemi bittikten sonra "New" butonuna tıkla ve "Size" değerini değiştirmeden "Apply" butonuna bas.
![13](https://github.com/MrQuerem/Rivalz/assets/172882082/192b2182-f617-44be-bedb-7898599b69e6)


Açılan uyarı penceresinde "OK" tıkla.
![14](https://github.com/MrQuerem/Rivalz/assets/172882082/56fad44b-54f3-495b-8c1d-dac47396dbf9)


Hetzner sunucu paneline geri dön,

1-) ISO Images tıkla,

2-) Arama kutusuna "2019" yazıp "enter" bas,

3-) Windows Server 2019 English satırında "Mount" butonuna tıkla,
![15](https://github.com/MrQuerem/Rivalz/assets/172882082/57cc69f1-79d7-4f84-93b0-3cf5ed37adb8)



Sunucu konsolüne geri dön,

1-) "Refresh" butonuna tıkla,

2-) 2 numaradaki satırı seç,

3-) "Next" butonuna tıkla.
![16](https://github.com/MrQuerem/Rivalz/assets/172882082/d3baa281-bead-4ed3-9815-cc40f1dc1dd8)



Windows'un kurulmasını bekle.
![17](https://github.com/MrQuerem/Rivalz/assets/172882082/8e2773b5-feac-4620-8667-bf1e622c88e7)


Windows kurulduktan sonra şifre belirleme penceresi açılacak.

Kullanıcı adı "Administrator" kalıyor, değiştiremiyoruz.

Küçük harf/Büyük harf ve rakamlardan oluşan 8 haneli şifre belirle ve "Finish" butonuna bas.
![18](https://github.com/MrQuerem/Rivalz/assets/172882082/cc4067a4-3720-4976-977c-2963f1139263)


Windows kilit ekranı açılacak, sağ alttaki "Ctrl+Alt+Del" butonuna tıklayarak ve masaüstüne geçiş yapın.
![19](https://github.com/MrQuerem/Rivalz/assets/172882082/fd8f1b21-8b20-4721-bd5e-d0439648d518)

Masaüstü açılış ekranına şifreni yazıp giriş sağla.
![20](https://github.com/MrQuerem/Rivalz/assets/172882082/e0d61480-caa5-4116-946d-1b6f05038fbb)


Açılışta "Server Manager" otomatik olarak açılacak ve küçük bir uyarı penceresi gelecek.

1 numaradaki kutucuğu işaretle ve 2 numaradaki çarpı işaretine basarak pencereyi kapat.
![21](https://github.com/MrQuerem/Rivalz/assets/172882082/ef34b78c-1e6e-4ddc-b78d-3a5b249456f6)



1-) "Manage" tıkla,

2-) "Server Manager Properties" tıkla,

3-) Açılan pencerede 3 numaradalı kutucuk işaretli olmasın,

4-) 4 numaradalı kutucuk işaretli olsun,

5-) "OK" butonuna bas,

6-) "Server Manager" penceresini kapat.

Kurulum aşaması burada bitmiş oldu.
![22](https://github.com/MrQuerem/Rivalz/assets/172882082/6bb654a6-ba84-4ba6-af78-dbd73455cb4d)



# Şimdi ayarları yapalım.

Hetzner sunucu paneline geri dön,

1-) ISO Images tıkla,

2-) Arama kutusuna "virtio" yazıp "enter" bas,

3-) virtio-win-0.1.248.iso satırında "Mount" butonuna tıkla,
![23](https://github.com/MrQuerem/Rivalz/assets/172882082/e84a4ade-4c1f-439d-b2f9-ca3be12d8f5a)


Sunucu konsolüne geri dön,

Windows logo'suna sağ tıkla ve Device Manager aç.
![24](https://github.com/MrQuerem/Rivalz/assets/172882082/dabdfec4-3be9-4d0d-8151-7c69ab471936)


Açılan "Device Manage" penceresinde güncellenmesi gereken 4 adet sürücü göreceksin.

Güncelleme adımları  her 4 sürücü için aynı olacak. lk olarak "Ethernet Conrtoller" sürücüsünü güncelliyoruz.

1-) "Ethernet Controller" sürücüsüne sağ tıkla,

2-) "Update Driver" tıkla.
![25](https://github.com/MrQuerem/Rivalz/assets/172882082/d3e73cc6-9449-4aa0-b514-2e8b21a016a5)



Açılan pencerede " Browse my computer for driver software" tıkla,
![26](https://github.com/MrQuerem/Rivalz/assets/172882082/b6e36d3d-129c-4058-bd0a-11ac3292a49b)


Açılan pencerede "Browse" butonuna tıkla,
![27](https://github.com/MrQuerem/Rivalz/assets/172882082/c60aae4b-0b0a-42f8-8e42-e69cfe16294a)


Açılan pencerede 1 numarada gösterilen satırı seçerek "OK" butonuna bas,
![28](https://github.com/MrQuerem/Rivalz/assets/172882082/940c12ec-cf40-4d95-b979-d4b78ede6357)


Açılan pencerede "Next" butonuna bas,
![29](https://github.com/MrQuerem/Rivalz/assets/172882082/831846ed-314a-42fe-b656-8c6444f400ab)


Sağ tarafta açılan mavi renkli pencerede "Yes" butonuna bas.
![30](https://github.com/MrQuerem/Rivalz/assets/172882082/203be9fa-7ced-4f26-a366-7d8080d323a0)


"Ethernet Controller" sürücü güncelleme işlemleri bitti, pencereyi kapatmak için "Close" butonuna basıyoruz.
![31](https://github.com/MrQuerem/Rivalz/assets/172882082/2574c9f6-dca1-46e8-bf25-15c80f49f945)

Not: Kalan diğer 3 adet sürücüleri güncellemek için aynı adımları uygula.



