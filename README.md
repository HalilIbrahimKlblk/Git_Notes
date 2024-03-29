# Git Kullanımı <br/>
### **pwd** = Mevcud konumu gösterir. <br/>
### **ls** = Mevcut konumdaki dosyaları listeler. <br/>
### **ls -a** = Mevcut konumdaki gizli dosyalar dahil hepsini listeler. <br/>
### **cd** = Dizinler arası gezinmeye yarar. <br/>
### **cd ..** = Bir önceki dizine geçer. <br/>
### **clear** = Terminal sayfasını temizler. <br/>
### **ls -a** = Gizli dosyaları listeler. <br/>
### **git add .** = Komut çalıştırılarak Staging Area adı verilen geçiş bölgesine gönderilmiş olur. <br/>
### **git commit -m "versiyon mesajı yazılır"** = Git tarafından mevcut projenin kopyası oluşturulur ve version mesajı ile commit işlemi gerçekleşmiş olur. <br/>
### **git log** = Komutu çalıştırılıp aldığımız versionları bize gösterir. <br/>
### **git status** = Komutunu çalıştırıp yapmış olduğumuz değişiklikleri bize listeler. <br/>
### **git remote add [bağlantı adı] [Uzak Server Linki]** = Komutunu çalıştırıp githup depomuz uzak depo olarak bağlanır. <br/>
### **git remote** = Komutunu çalıştırıp githup deposu yani uzak depo tanımlanan bağlantı adı ile kontrol edilir. <br/>
### **git push -u [bağlantı adı] master** = Komutunu çalıştırıp githup depomuza yeni değişikliğimizi göndermiş oluyoruz. <br/>
### **git rm -r silinecek klasör adı/** = Belirtilen klasörü ve içindekileri siler. <br/>
### **git rm silinecek dosya adı** = Belirtilen dosyayı siler. <br/>
### **git mv Eski.txt Yeni.txt** = Belirtilen dosyanın adını belirtilen yeni ad ile adlandırır. <br/>
### **git mv Dosya.txt Dizin/** = Belirtilen dosyayıyı belirtilen dizine göndererek yerini değiştirir. <br/>
### **git checkout --dosyanın ismi** = Silinen dosyayı çalışma üzerinde geri alır. <br/>
### **git restore --dosyanın ismi** = Silinen dosyayı çalışma üzerinde geri alır. <br/>
### **git reset HEAD --dosyanın ismi** = Silinen dosyayı geçiş bölgesinden geri alır. <br/>
### **git checkout [hash kodu] -- .** =Geçilmek istenen versiyonun hash kodu yada ilk 7 değeri yazılır. Sondaki nokta çok önemlidir, geçilmek istenen versiyondaki bütün dosyaları getirir. Nokta yerine dosya ismi yazarsak sadece o dosyaya ait veriler gelir. <br/>
### **cat >> .gitignore** = Gitignore klasörünü oluşturur ve buraya projemizde git ile paylaşmayı istemediğimiz dosyalar yer alır. <br/>
### **cat .gitignore** = Gitignore klasörünün içindekileri listeler. <br/>
### **git branch** = Gite bağlı branchleri sorgular. <br/>
### **git branch --all** = Gite bağlı tüm branchleri (uzak sunucu dahil) sorgular. <br/>
### **git fetch** = Uzak sunucuda yeni tanımlanmış branchleri locale çeker. <br/>
### **git branch [branch name]** = Gite bağlı localde yeni branch eklemek için kullanılır. <br/>
### **git checkout [branch name]** = Gite bağlı olan branche geçmek için kullanılır. <br/>
### **git pull [bağlantı adı] [barnch adı]** = Uzak sunucudaki dosyaları locale çekmek için kullanılır. <br/>
### **git merge [barnch adı]** = Başka bir branch'deki değişiklikleri üzerinde çalıştığınız kendi branch'inize entegre etme işlemidir. <br/>
### **git fetch -p** = Uzak sunucuda tanımlanmış ve silinmiş branchleri localden siler. <br/>
### **git branch -D [barnch adı]** = Local sunucudan branch silmek için kullanılır. <br/>
