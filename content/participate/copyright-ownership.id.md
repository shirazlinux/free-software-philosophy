---
title: Mengatur kepemilikan hak cipta
weight: 90
---

Kepemilikan hak cipta dalam Free Software perlu diperjelas.
Tanpa adanya _Contributor License Agreement_ (CLA) atau dokumen yang serupa
(sebuah praktik yang kami [sangat tidak anjurkan][0]), bagaimana pengembang
dan penerbit Free Software mengatur hak-hak legalitas yang berhubungan dengan
hak cipta perangkat lunak?

[0]: /id/learn/participate/contribute/#regarding-contributor-license-agreements

## Siapa yang memiliki proyek Free Software?

Saat Anda berkontribusi pada proyek Free Software, jika Anda tidak memberikan
hak cipta ke orang lain, Anda akan tetap memiliki hak properti intelektual
terhadap kontribusi Anda.
Perubahan Anda kemudian *di-lisensi-kan* ke orang lain, termasuk pemegang hak
cipta lainnya, di bawah syarat yang sama dari lisensi proyek tersebut
di-distribusi-kan.

Oleh karena itu, pada banyak kasus, hak cipta dari proyek Free Software
dipegang secara bersama-sama oleh orang-orang yang telah memberikan kontribusi
properti intelektual mereka, yang kemudian me-lisensi kan ke pengguna, dan
ke sesama kontributor, dengan sebuah
[lisensi Free Software][1].

[1]: /id/learn/licenses/

## Membangun riwayat hak cipta

Bagi beberapa proyek, khususnya proyek komersil, memiliki prosedur untuk
setiap kontribusi:

1. Kontributor memegang hak cipta bagi kontribusi mereka, atau pemegang hak
   cipta memberikan otorisasi untuk menggunakan hasil kontribusi tersebut.
2. Kontributor setuju me-lisensi-kan hak cipta mereka di bawah syarat dari
   lisensi proyek.

Jika proyek Anda ingin membangun prosedur riwayat hak cipta dengan cara
tersebut, kami rekomendasi-kan menggunakan [Developer Certificate of
Origin][2].
Kebanyakan proyek memfasilitasi hal ini dengan meminta kontributor
supaya "sign-off" (menandatangani) kontribusi mereka.
Sistem kontrol versi seperti [Git][3] menyediakan cara ini dengan
mengindikasikan bahwa setiap kontribusi telah ditandatangani dengan "[git
commit -s][4]".

[2]: https://developercertificate.org/
[3]: https://git-scm.com/
[4]: https://git-scm.com/docs/git-commit#Documentation/git-commit.txt--s

## Mengubah lisensi proyek

Anda mungkin suatu saat ingin mengubah lisensi dari proyek Anda.

[lisensi permisif]: /id/learn/participate/choose-a-license/#permissive-licenses
[lisensi _copyleft_]: /id/learn/participate/choose-a-license/#copyleft-licenses

Jika proyek di-lisensi dengan [lisensi permisif], biasanya memungkinkan
untuk proyek tersebut menggunakan lisensi yang baru, dengan menerapkan lisensi
baru terhadap perubahan di masa depan.
Anda harus tetap tunduk dengan syarat lisensi yang asli, seperti atribusi,
namun perubahan selanjutnya akan diberikan lisensi dengan syarat-syarat yang
berbeda.
Dengan cara ini, mengubah lisensi sama dengan membuat proyek baru dan
menggabungkan basis kode asli ke dalamnya.

Namun, bila proyek tersebut menggunakan [lisensi _copyleft_], hal ini lebih
sukar -- terkadang tidak memungkinkan.
Hal ini merupakan sifat dari lisensi _copyleft_: untuk mencegah proyek
tersebut digabungkan ke dalam perangkat lunak tidak bebas.
Anda biasanya tidak bisa me-lisensi sebuah proyek _copyleft_ dengan cara yang
sama Anda mengubah lisensi dari proyek permisif.

Proyek dengan lisensi _copyleft_ bisa diganti lisensi-nya, dengan syarat
<nobr>**(a)** pastikan</nobr> meminta permisi ke semua pemegang hak cipta,
atau
<nobr>**(b)** tulis ulang kontribusi mereka</nobr>.
Pendekatan ini juga cocok jika Anda ingin mengubah lisensi permisif tanpa
mengikuti syarat-syarat aslinya (seperti atribusi), namun biasanya hal ini
tidak sebanding usahanya, mempertimbangkan lisensi yang permisif relatif tidak
memberatkan.

Oleh karena itu memegang hak cipta secara bersama-sama, oleh dan di antara
para kontributor, bukan diberikan ke satu entitas, sangat di-rekomendasi-kan
bagi proyek _copyleft_: ia memperkuat jaminan jangka panjang dari status
proyek Free Software dengan membuatnya lebih sukar mengubahnya ke lisensi yang
tidak bebas.
