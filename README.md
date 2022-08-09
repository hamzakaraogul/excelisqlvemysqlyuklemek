# excelisqlvemysqlyuklemek
Exceli Sql ve Mysql'le yüklemek.
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
![image](https://user-images.githubusercontent.com/62428397/183649137-f373e46a-4cfb-416d-9991-cb968a67234b.png)
![image](https://user-images.githubusercontent.com/62428397/183649233-910ae0f4-9661-44e1-aa7a-31cf672388e1.png)





