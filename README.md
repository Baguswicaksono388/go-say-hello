# go-say-hello
- Untuk menguploads module, biasakan menggunakan tag
- Untuk menulis tag nya, biasakan awalan memberi huruf v
- Ketik git tag v1.0.0
- Cara push : git push origin v1.0.0

# Upgrade version
- Git commit
- Git push
- git tag v1.5.0
- git push v1.5.0

# Major Upgrade
- Major upgrade biasanya terjadi dikarenakan ada perubahan pada isi kode program kita, sehingga membuatnya tidak backward compatible (code nya rusak)
- Sebaiknya hal ini sebisa mungkin dihindari
- Namun jika tidak bisa dihindari, strategy terbaik adalah merubah nama module (yg semula module github.com/Baguswicaksono388/go-say-hello menjadi module github.com/Baguswicaksono388/go-say-hello/v2)

# Langkah uploads major upgrade
- Git push
- Git tag v2.0.0
- Git push origin v2.0.0

# Catatan
- Sekecil apapun perubahan sebaiknya, mengganti nama versinya. Dikarenakan golang mempunyai cache ketika kita mendownloads modulenya. Jika perubahannya minor atau kecil bisa mengganti tag v1.5.1
