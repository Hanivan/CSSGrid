justify-items => Mensejajarkan grid items pada sumbu horizontal
 Penggunaan:
  .container {
      justify-items: start | end | center | stretch;
  }

align-items => Mensejajarkan grid-items pada sumbu vertikal
 Penggunaan:
  .container {
      align-items: start | end | center | stretch;
  }

place-items => Shorthand untuk menulis justify-items dan align-items dalam satu deklarasi
 Penggunaan:
  .container {
      place-items: <align-items> <justify-items>;
  }

justify-content => Mengatur posisi seluruh grid container pada sumbu horizontal. Ini bisa dilakukan ketika ukuran total grid lebih kecil dari ukuran containernya, biasanya ketika grid items nya menggunakan ukuran yang fixed (px)
 Penggunaan:
  .container {
      justify-content: start | end | center | stretch |
        space-around | space-between | space-evenly;
  }

align-content => Sama seperti justify-content, tapi untuk sumbu vertikal
 Penggunaan:
  .container {
      align-content: start | end | center | stretch |
        space-around | space-between | space-evenly;
  }

place-content => Shorthand untuk menulis justify-content dan align-content delam satu deklarasi
 Penggunaan:
  .container {
      place-content: <justify-content> <align-content>;
  }

note: lambang (|) == atau