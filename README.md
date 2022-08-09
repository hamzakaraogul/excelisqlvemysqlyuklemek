# excelisqlvemysqlyuklemek
Exceli Sql ve Mysql'le yüklemek.https://youtu.be/OINBdxpfVaM
<br>
Öncelikle Microsoft Sql Server Management Studio'ya giriyoruz.
<br>
Girdikten sonra database klasörü altında yüklemek istediğimiz database sağ tıklıyoruz, task yazan yere gelip Import Data'ya basıyoruz.
<br>
<img src="https://user-images.githubusercontent.com/62428397/183643887-1598428f-1226-4471-8b61-98f65d228bd0.png">
<br>
Eğer yeni database açacaksak, Database klasörüne sağ tıklayarak new database basıyoruz. (İsim verdikten sonra ok tuşuna bastığınızda oluşturacaktır.)
<br>
<img src="https://user-images.githubusercontent.com/62428397/183644185-152964f2-0d6b-45a5-9e49-bb3201514802.png">
<br>
Import Data kısmına döndüğümüzde açılan pencerede Microsoft Exceli seçiyoruz.
<br>
<img src="https://user-images.githubusercontent.com/62428397/183644610-2c6419e5-c9db-4d4e-aa9f-7930fc4e40c6.png">
<br>
Excelin konumu browsedan seçerek ekliyoruz ve next tuşuna basıyoruz.
<br>
<img src="https://user-images.githubusercontent.com/62428397/183644750-d9784798-ea92-436b-8d01-e7feebe9a9a1.png">
<br>
Sonraki destination kısmında SQL Server Native Client'ı seçiyoruz.
<br>
<img src="https://user-images.githubusercontent.com/62428397/183644934-9413058d-21b8-482e-a315-66550169ad94.png">
<br>
Database kısmına nereye yükleyeceksek orayı yazıyoruz. next tuşuna basıyoruz.
<br>
<img src="https://user-images.githubusercontent.com/62428397/183645105-fc8b32ed-8295-4828-bb3b-a86817e0f69c.png">
<br>
1. şıkkı seçerek devam ediyoruz.
<br>
<img src="https://user-images.githubusercontent.com/62428397/183645261-2a858f9b-78bc-4a94-a2be-029c221a60d6.png">
<br>
Excel içinde hangi sekmeyi alacaksak onu seçiyoruz.
<br>
<img src="https://user-images.githubusercontent.com/62428397/183645364-be618b37-731b-48b1-96b2-5bdaa14a5aac.png">
<br>
Direk finish butonlarına basarak excel yüklemeyi bitirebiliriz. 
<br>
<img src="https://user-images.githubusercontent.com/62428397/183645490-e661b0e0-b2a5-4998-aaa5-4bab343e27a3.png">
<br>
<img src="https://user-images.githubusercontent.com/62428397/183645818-6f49aa80-b071-4786-8307-36ebdb82c83c.png">
<br>
Sonrasında bu datayı MYSQL'e yüklemek için MYSQL Workbench'i açıyoruz.( https://www.mysql.com/products/workbench/ Buradan indirebilirsiniz.)
<br>
+ kısmına basarak MYSQL sunucunuzu ekleyin.
<br>
<img src="https://user-images.githubusercontent.com/62428397/183646096-959b5881-7050-4cc6-a34a-4467a0c998e0.png">
<br>
<img src="https://user-images.githubusercontent.com/62428397/183646328-3f35ba3e-a07b-4be0-bc1f-0836754a6602.png">
<br>
Ekledikten sonra aşağıda gösterilen yere basarak bağlanınız.
<br>
<img src="https://user-images.githubusercontent.com/62428397/183646456-df5f08ec-eff1-40ff-b88c-4a517b724c82.png">
<br>
Açılan ekranda Database sekmesi altında Migration Wizard'a basınız.
<br>
<img src="https://user-images.githubusercontent.com/62428397/183646605-32cb7044-af5d-4893-a936-f446d92c38bb.png">
<br>
Start Migration'a basınız.
<br>
<img src="https://user-images.githubusercontent.com/62428397/183646797-5075965e-ec01-4b89-8bca-4075375d5255.png">
<br>
Veriyi Microsoft SQL'den alacağımız için orayı seçiniz.
<br>
Dsn aşağıdaki gibi seçeceksiniz fakat öncelikle:
<br>
<img src="https://user-images.githubusercontent.com/62428397/183647295-1d77354d-422a-406e-a89e-ef11489a1ef3.png">
<br>
Windows aramasından Odbc Veri Kaynaklarına giriniz.
<br>
<img src="https://user-images.githubusercontent.com/62428397/183647551-72303358-098a-40bf-b55e-fd2fe08d9af0.png">
<br>
Sistem DSN sekmesini seçiniz
<br>
<img src="https://user-images.githubusercontent.com/62428397/183647637-2c07be9a-91e2-4c21-8b4b-c0c1f76d9b8a.png">
<br>
Ekleye basarak SQL Server'i seçiniz
<br>
<img src="https://user-images.githubusercontent.com/62428397/183647832-42a6a882-594b-4ba7-b989-824101e4b570.png">
<br>
Adı ve açıklamaya istediğinizi yazabilirsiniz ve sunucuya sql server adresini yazınız.( Sql Server bilgisayarımda kurulu olduğu için bilgisayarımın adını yazdım.)
<br>
<img src="https://user-images.githubusercontent.com/62428397/183648822-55c7c8ea-573c-43cd-8189-b66c85c8b249.png">
<br>
Ayrı bir kimlik oluşturmadığım için windows doğrulaması ile devam ediyorum.
<br>
<img src="https://user-images.githubusercontent.com/62428397/183648294-f3b6bfc3-589c-4b53-87f1-6fbea0aa5723.png">
<br>
Sonraki, sonraki, son diyerek işlemi bitiriyoruz.
<br>
<img src="https://user-images.githubusercontent.com/62428397/183649137-f373e46a-4cfb-416d-9991-cb968a67234b.png">
<br>
<img src="https://user-images.githubusercontent.com/62428397/183649233-910ae0f4-9661-44e1-aa7a-31cf672388e1.png">
<br>
MYSQL'e döndüğümüzde next'e basarak devam ediyoruz.
<br>
<img src="https://user-images.githubusercontent.com/62428397/183649528-d8dca185-104a-4a1b-8fd4-07f707c30b34.png">
<br>
Target kısmında birşey yapmadan devam ediyoruz.
<br>
<img src="https://user-images.githubusercontent.com/62428397/183649663-5a470e14-4f72-467b-b33f-e7c255c6f494.png">
<br>
Aşağıdaki gibi sonuç verecektir devam ediyoruz.
<br>
<img src="https://user-images.githubusercontent.com/62428397/183649807-e052e265-8f60-41e1-95b4-9934ba9a13cb.png">
<br>
Yüklenecek yeri Test Databasini seçtim ve devam ediyoruz.
<br>
<img src="https://user-images.githubusercontent.com/62428397/183650030-95f71e63-9909-4954-bd10-6eca5bf83126.png">
<br>
Yüklenecek tabloları bize gösterecek ve devam ediyoruz.
<br>
<img src="https://user-images.githubusercontent.com/62428397/183650237-e6142475-c1c0-4167-ae1d-b7a6eb5c7e35.png">
<br>
Birşey yapmadan devam ediyoruz.
<br>
<img src="https://user-images.githubusercontent.com/62428397/183650366-3c5b5bc8-f13f-4ed7-9f66-7e6f85ccb80e.png">
<br>
Birşey yapmadan devam ediyoruz.
<br>
<img src="https://user-images.githubusercontent.com/62428397/183650484-27d67a1f-9a34-4085-a0a3-fac792f376b0.png">
<br>
Birşey yapmadan devam ediyoruz.
<br>
<img src="https://user-images.githubusercontent.com/62428397/183650554-2993d2bb-e06e-4aa8-a7e3-edfeacff06fc.png">
<br>
Devam ediyoruz.
<br>
<img src="https://user-images.githubusercontent.com/62428397/183650637-296481b9-e40f-4762-8df4-eba6a6cd377c.png">
<br>
Devam ediyoruz.
<br>
<img src="https://user-images.githubusercontent.com/62428397/183650713-992b2e13-155e-4209-8f41-bba88a949b13.png">
<br>
Devam ediyoruz.
<br>
<img src="https://user-images.githubusercontent.com/62428397/183650750-7e2860ac-17f0-4299-86c8-2df015262eb7.png">
<br>
Devam ediyoruz.
<br>
<img src="https://user-images.githubusercontent.com/62428397/183650823-d187c2be-78d3-4261-9057-b41938c0133c.png">
<br>
işlem bitmiştir.
<br>
<img src="https://user-images.githubusercontent.com/62428397/183650926-51a4fc5f-fc34-4177-9847-41b011884950.png">
<br>
<img src="https://user-images.githubusercontent.com/62428397/183651186-00d595c2-f9d2-44e0-96a3-d86e4de7f388.png">

<br>



