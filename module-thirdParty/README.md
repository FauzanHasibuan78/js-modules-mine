untuk menginisiasi project menggunakan npm kita harus menjalankan beberapa komen untuk menginisiasinya dengan cara:

`npm init` atau mau skip aja pake `npm --yes` atau `npm init -y`

setelah npm init akan terbuat/tercipta `package.json`dimana `package.json` mengindikasikan bahwa project yang di buat itu akan menggunakan package dari npm, dan juga memiliki informasi tentang project tersebut dan juga memakai package apa saja yang ada dalam project tersebut 

dan akan menginstall package yang di butuhkan package yang di install yang ada di `package.json` lalu akan tersedia dalam folder `node_modules` 

perlu di ingat bahwa folder `node_modules` tidak perlu di shere ke githun, karna orang lain dapat menginstal mandiri dengan cara `npm install` dan juga `node_modules` biasanya berat atau size filenya besar
agar tidak ke push ke github si `node_modules`nya kalian bisa buat file dengan nama `.gitignore` dan masukan node_modules ke dalamnya
kalau males kalian bisa pakek perintah di cli di terminal dengan cara `echo "node_modules" >> .gitignore`