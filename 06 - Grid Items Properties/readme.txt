grid-column-start & grid-column-end
grid-row-start & grid-row-end
=> Menentukan tempat dari grid item dengan mengacu pada nomor atau nama grid line yang spesifik
 Penggunaan:
  .item {
      grid-column-start: <nomor> | <nama> | span <nomor> | span <nama> | auto;
      grid-column-end: <nomor> | <nama> | span <nomor> | span <nama> | auto;
      grid-row-start: <nomor> | <nama> | span <nomor> | span <nama> | auto;
      grid-row-end: <nomor> | <nama> | span <nomor> | span <nama> | auto;
  }

    <nomor> | <nama>: Mengacu pada nomor atau nama yang kita beri pada grid line
    span <nomor>: Item akan memanjang/melebar sampai sejumlah nomor
    span <nama>: Item akan memanjang/melebar sampai ke nama grid line tertentu

grid-column & grid-row => Shorthand untuk start dan end pada grid-column & grid-row
 Penggunaan:
  .item {
      grid-column: <start-line> / <end-line> | <start-line> / span <value>;
      grid-row: <start-line> / <end-line> | <start-line> / span <value>;
  }

grid-area => Menentukan nama area pada item sesuai dengan template yang sudah dibuat sebelumnya melalui properti grid-template-areas.
 => Bisa digunakan sebagai shorthand untuk grid-column-start, grid-column-end, grid-row-start, dan grid-row-end
  Penggunaan:
   .item {
       grid-area: <name> | <row-start> / <column-start> / <row-end> / <column-end>;
   }

justify-self => Mengatur posisi item pada sebuah cell terhadap sumbu horizontal
 Penggunaan:
  .item {
      justify-self: start | end | center | stretch;
  }

align-self => Mengatur posisi item pada sebuah cell terhadap sumbu vertical
 Penggunaan:
  .item {
      align-self: start | end | center | stretch;
  }

place-self => Shorthand posisi item pada sebuah cell terhadap sumbu vertical dan sumbu horizontal dalam satu deklarasi
 Penggunaan:
  .item {
      place-self: <align-self> <justify-self>;
  }

note: lambang (|) == atau