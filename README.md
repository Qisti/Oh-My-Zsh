# Oh-My-Zsh

## 1. Penjelasan singkat mengenai shell dan Zsh


**Shell** merupakan sebuah program penerjemah perintah yang memberikan jembatan antara user dengan kernel yang merupakan inti dari Sistem Operasi. Biasanya shell menyediakan prompt sebagai user interface, yaitu tempat dimana user memberikan perintah-perintah yang diinginkan baik berupa perintah internal shell, ataupun perintah eksekusi suatu file progam. Shell juga memungkinkan user menyusun sekumpulan perintah pada sebuah atau beberapa file untuk dieksekusi sebagai program.

**Zsh** merupakan sebuah shell yang disertai banyak fitur yang bash tidak ada

## 2. Cara instalasi Zsh + command line untuk instalasinya
Buka terminal di linux kemudian ketikkan perintah berikut untuk menginstallnya
> $ sudo apt-get update
> $ sudo apt-get install zsh

Setelah itu, kita mengganti harus mengganti default shell dari bash ke zsh. Jangan lupa juga untuk me-reboot agar penggantian shell bisa dieksekusi oleh system linux
> $ chsh -s /bin/zsh
> $ sudo chsh -s /bin/zsh
> $ sudo reboot

Untuk mengetahui shell yang aktif, bisa menggunakan perintah 
> $ echo $SHELL


```sh
UNTUK MAC, ZSH SUDAH OTOMATIS TERINSTALL !
```

## 3. Penjelasan singkat mengenai Oh My Zsh

**Oh My Zsh** merupakan pelengkap untuk zsh yang menambah banyak pelengkap otomatis, juga termasuk  *community-drive* untuk mengelola konfigurasi Zsh.

## 4. Cara instalasi Oh My Zsh
Pastikan untuk menginstall **Git** terlebih dahulu, kemudian kita download *theme package* yang tersimpan di *repository* github dengan perintah git sebagai berikut :
> $ sh -c "$(wget https://raw.github.com/robbyrussell/oh-my-zsh/master/tools/install.sh -O -)"

## 5. Mengganti *theme* Zsh (menggunakan Oh My Zsh)
Buka link di bawah ini untuk melihat opsi *theme* yang tersedia
> https://github.com/robbyrussell/oh-my-zsh/wiki/Themes

Sebagai alternatif, bisa masuk ke direktori ‘themes’ dan melihat daftar tema yang tersedia.
> cd ~ / .oh-my-zsh / themes /
> ls -a

Pada langkah ini, kita akan men-*tweak* zsh menggunakan kerangka ‘oh-my-zsh’ dengan mengaktifkan beberapa plugin. Untuk mengaktifkan plugin, kita perlu mengedit file konfigurasi .zshrc. Edit file konfigurasi .zshrc.
> nano ~ / .zshrc

Pilih satu tema zsh – contoh tema yang akan digunakan adalah ‘muse’.
Kemudian ubah garis ‘ZSH_THEME’ 10 dengan tema ‘muse’ seperti di bawah ini.
> ZSH_THEME = ‘muse’

Simpan dan keluar. 

## 6. Fitur-fitur Zsh yang tidak tersedia di Bash
Kelebihan dari Zsh yang tidak tersidia di bash adalah :

- Auto-completion yang lengkap
- Auto-correct
- Menyediakan berbagai tema untuk tampilannya
- Menyediakan banyak ALIAS untuk aplikasi-aplikasi populer, diantaranya adalah : 

*
        gst dari git status
        ga dari git add
        gc dari git commit
        gp dari git push





