# Vue CRUD Dersi

Bu bölümde [vue_dersleri_ders_1](https://github.com/msbeden/vue_dersleri_ders_1) üzerinden geçici json server oluşturarak CRUD işlemleri yapılacaktır.


# Gerekli programlar

 - NPM

## Gerekli kütüphanelerin kurulumu
Geçici json server oluşturmak için aşağıdaki komutu kullanıyoruz.

    npm install -g json-server

## json server'ın açılması
Proje içeriğinde **src\api** klasörüne girilir. db.json dosyasının varlığı kontrol edilir ve aşağıdaki komut çalıştırılır.

    json-server --watch db.json
