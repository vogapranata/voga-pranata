# voga-pranata

berikut link image php:7.4-apache yang digunakan :

                      https://hub.docker.com/_/php
Petunjuk :

git clone pada terminal anda :

                    git clone https://github.com/vogapranata/voga-pranata.git
pull image dari dockerhub ke terminal anda :

                     docker pull vogapranata/kikivogapranata
masuk kedalam direktori file yang diambil dari github :

                     cd voga-pranata
setelah masuk kedalam direktori voga-pranata jalankan perintah berikut :

                     docker-compose up -d
setelah selesai buka web browser anda lalu masuk ke localhost :

                     localhost --> masuk ke menu web
                     
                     localhost:8080 --> masuk database
untuk membuat web bisa melakukan CRUD lakukan setting pada database, Log in ke database :

                    Username : root
                    password : example
                    Database : (kosongkan, jangan di isi)
lalu create database dengan nama : data                    

buat tabel dengan nama : tb_blog

lalu buat colom :

            id  | int | length (kosongkan) |  options (koosngkan) | NULL (kosongkan)  | AI (conteng, ini primary key) | sisanya kosongkan
            
            nama  | varchar | lenght (25) | options (default) | sisanya kosongkan
            
            nim | int | length (9)  | sisanya kosongkan
            
            Default values (conteng), Comment (conteng)
            
            lalu save.
buka lagi localhost, lalu masuk ke menu CRUD. sekarang telah bisa melakukan proses CRUD pada web ini.

untuk mematikan docker ketikkan syntax berikut pada terminal :

             docker-compose stop
