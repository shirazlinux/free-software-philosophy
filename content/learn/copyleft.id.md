---
title: Apa itu copyleft?
weight: -8
---

**Copyleft** adalah lisensi yang unik terhadap Free Software.
Ia dirancang untuk mendorong proliferasi Free Software dan melindungi-nya dari
tercampur dengan pekerjaan yang tidak bebas.
Ia bekerja dengan memberikan Anda tidak saja *hak* untuk berbagi peningkatan
(perubahan, perbaikan), tapi juga *kewajiban* untuk membagikan peningkatan
Anda dengan kondisi-kondisi tertentu.
Sangatlah penting untuk memahami kewajiban ini saat menggunakan perangkat
lunak dengan lisensi _copyleft_ dalam pekerjaan Anda.

{{< tip >}}
**Catatan**:
Kebingungan antara terminologi _copyleft_ dan "Free Software" sering terjadi:
perangkat lunak yang bukan _copyleft_ bisa jadi Free Software, dan perangkat
lunak Open Source bisa jadi _copyleft_.
Namun, mereka yang bergerak dalam Free Software cenderung lebih menyukai
lisensi _copyleft_ daripada yang bergerak dalam Open Source.
{{< /tip >}}

## Spektrum dari _copyleft_

Beberapa lisensi Free Software menempati ruang spektrum yang berbeda, dari
yang **permisif** sampai **_copyleft_**, berdasarkan tingkat penekanan pada
syarat dan kondisi dalam lisensi tersebut.
Lisensi yang permisif cenderung membolehkan penggunaan hasil kerja dengan
kewajiban yang sedikit dan tidak memberatkan, seperti kondisi mencantumkan
nama penulis asli dari hasil kerja.
Sebaliknya, lisensi yang _copyleft_ mengharuskan untuk membagikan perubahan
Anda dan hasil pekerjaan turunan dengan lisensi yang sama.

<img src="/images/licensing-spectrum.svg" alt="beragam proyek dan lisensi dalam spektrum" />
<small>
  Beragam lisensi perangkat lunak dan contoh proyek yang menggunakan mereka,
  dikelompokkan dalam spektrum <i>copyleft</i>.
  Gambar asli oleh David A Wheeler, CC BY-SA 3.0.
</small>

## Kenapa memilih lisensi _copyleft_?

Sangatlah umum bagi Free Software dengan lisensi-permisif digunakan dalam
pekerjaan yang tidak bebas.
Hal ini sering kali dilakukan karena profit dengan mengindahkan empat
kebebasan bagi pengguna yang menerima hasil kerja tersebut, menggali profit
dari penggunaan perangkat lunak tanpa memberi balik ke komunitas Free
Software.

Lisensi _copyleft_ mengatasi beberapa masalah ini:

1. _Copyleft_ mempromosikan proliferasi dari Free Software dan empat kebebasan
   dengan memastikan bahwa hasil kerja yang dibangun dengan Free Software
   tumbuh dan menguntungkan ekosistem Free Software.
2. _Copyleft_ menjamin mereka yang meningkatkan atau menggunakan Free Software
   membagikan perubahan mereka dengan komunitas, sehingga semua pengguna
   mendapatkan keuntungan dari peningkatan tersebut.

Perangkat lunak dengan lisensi _copyleft_ dapat dijual, seperti perangkat lunak
bebas lainnya, namun mengharuskan setiap peningkatan dari hasil komersial
tetap menjamin empat kebebasan dipegang oleh semua partisipan.
Lebih lanjut, tidak mudah mengubah lisensi dari perangkat lunak yang
_copyleft_ jika hak cipta dipegang [secara bersama-sama][0], sebagai landasan
yang menjamin masa depan dari perangkat lunak sebagai Free Software.

[0]: /id/learn/participate/copyright-ownership/

## _Copyleft_ lemah dan kuat

Lisensi _copyleft_ berbeda dalam seberapa kuat klausa _copyleft_ mempengaruhi
penggunaan ulang dari perangkat lunak.
Sebagai contohnya, lisensi _copyleft_ lemah [Mozilla Public License][MPL]
(MPL) adalah *berbasis-berkas*, yang mana klausa dari _copyleft_ melingkupi
berkas-berkas dari sumber kode secara tersendiri, bukan seluruh proyek: Anda
dapat mengambil dan menggunakan salah satu berkas ber-lisensi MPL ke dalam
proyek lain tanpa harus me-lisensi ulang seluruh proyek, selama Anda
merilis setiap perubahan terhadap berkas tersebut.

[MPL]: https://www.mozilla.org/en-US/MPL/2.0/

Contoh yang lebih kuat yaitu [GNU Lesser General Public License][LGPL] (LGPL),
yang khusus menangani pustaka perangkat lunak.
Setiap pustaka tersebut dikompilasi menjadi satu artifak perangkat lunak,
seperti _shared object_ atau arsip statis, dan ketentuan _copyleft_ berlaku
terhadap seluruh artifak.
Namun, bila digabung dengan program pihak-ketiga, klausa _copyleft_ tidak
berlaku lagi.
Yang lebih kuat lagi yaitu [GNU General Public License][GPL] (GPL), yang mana
klausa dari _copyleft_ berlaku terhadap keseluruhan program sebagai artifak
perangkat lunak.

[LGPL]: https://www.gnu.org/licenses/lgpl-3.0.en.html
[GPL]: https://www.gnu.org/licenses/gpl-3.0.html

Di ujung spektrum dari _copyleft_ yaitu lisensi seperti [GNU Affero General
Public License][AGPL] (AGPL), yang memperluas
<abbr title="GNU General Public License">GPL</abbr>
supaya berlaku untuk perangkat lunak yang digunakan dalam jaringan, seperti
basis data, dan menganggap pengguna dari perangkat lunak tersebut sebagai
"penerima", sehingga berhak menerima sumber kode.

[AGPL]: https://www.gnu.org/licenses/agpl-3.0.html

## Bagaimana menggunakan hasil kerja _copyleft_

Cara paling mudah menggunakan hasil kerja dari _copyleft_ yaitu menerapkan
lisensi mereka ke dalam hasil kerja Anda dan mendistribusikan-nya (dengan
lisensi yang sama).

Jika Anda tidak ingin seperti itu, Anda hanya dapat menggunakan hasil kerja
_copyleft_ di bawah kondisi yang dibolehkan oleh lisensi-nya, dan kemungkinan
terbatas pada penggunaan dari hasil kerja _copyleft_ yang lemah.
Sebagai contohnya, jika perangkat lunak Anda bergantung pada sebuah pustaka
dengan lisensi
<abbr title="GNU Lesser General Public License">LGPL</abbr>,
Anda dapat menggunakan lisensi apa pun terhadap hasil kerja Anda tapi harus
membagikan perubahan yang Anda buat pada pustaka tersebut.
Jika pustaka tersebut menggunakan lisensi GPL atau AGPL, pendekatan Anda akan
lebih terbatas.
Bacalah ketentuan dari setiap lisensi secara seksama dan konsultasi dengan
pengacara jika Anda tidak yakin bagaimana cara kerjanya.

Untuk lebih rinci, lihat halaman
[penggunaan ulang Free Software](/id/learn/participate/derived-works/).

{{< tip >}}
[Software Freedom Conservancy][sfc] adalah sebuah organisasi yang bekerja,
salah satunya, menempuh jalur hukum untuk penerapan _copyleft_.
Untuk mempelajari lebih lanjut tentang penerapan _copyleft_ bagi proyek Anda,
Anda bisa berkonsultasi dengan mereka.

[sfc]: https://sfconservancy.org/
{{< /tip >}}
