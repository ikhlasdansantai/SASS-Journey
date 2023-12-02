# Alasan Menggunakan SASS

- Mempermudah penulisan css
- Mempermudah pengelolaan file css nya, ketika punya banyak file css atau 1 file css yang 1 juta baris😲
- banyak fungsi built in
- Dapat membuat fungsi sendiri dengan mix-in
- Dapat memodifikasi framework CSS 😲 (Bootstrap/Materialize)
- Sebetulnya tidak butuh SASS karena udah jago 😎, tapi akan penting ketika perusahaan nya udah pake css pros, untuk pengelolaan css, tidak ada salahnya yagesya, biar bisa dipake di industri
- SASS vs SCSS
- SASS untuk orang pro sementara scss untuk pemula

# Alasan Tidak Menggunakan SASS

- Banyak fitur sass yang css udah punya, seperti variabel
- Tidak untuk proyek kecil
- Styled Components / CSS in js
- masih layak dipelajari kok tentang aja

# Cara membuat nesting css

biasnaya kita membuat spt ini,
:is(.main h1, .footer h1){
//style//
}

dengan sass kita bisa membuat seperti ini
.artikel-1, .artikel-2
  p
   font-size: 2rem

# Parent Selector alias lu pake & lu punya kuasa

