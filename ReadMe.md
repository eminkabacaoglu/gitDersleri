## Baslangic ##
```js
git init
```

## Konfigurasyonlar ##
```js
git config --global --list
```
email ve username kayıtlı mı değil mi gosterir

email eklemek için
```js
git config --global user.email user@email.com
```

username eklemek için
```js
git config --global user.name username
```

<!--  -->
dosyaları stage (gonderme kanakina alir)
```
git add .
```

dosyalara-ı mesajlandırıp gönderime hazırhale getirir
```js
git commit -m "mesaj"
```

git ile github reposu birbirine bağlanır
```js
git remote add origin repo_url
```
origin aliastır takma isimdir



dosyayı github reposuna gönderiyoruz
```js
<<<<<<< HEAD
git push -u origin main 
```

sdasd
=======
git push -u origin main
```
>>>>>>> 3d7edd4a9b13974da0372a997db728784ed6b7a8
