grid-template-area => Mendefinisikan grid template menggunakan nama dari area yang ditulis pada property grid-area pada item
 Penggunaan:
  .container {
      display: grid;
      grid-template-areas: "<nama-area> | none | '.'"
        "<nama-area> <nama-area>";
  }

grid-template => Shorthand untuk mendefinisikan grid-template-rows, grid-template-columns, dan grid-template-areas dalam satu deklarasi
 Penggunaan:
  .container {
      grid-template: <grid-template-rows> | <grid-template-areas> / <grid-template-columns>;
  }

grid-gap => Mendefinisikan ukuran grid-line/jarak antara baris atau kolom. Ada dua cara penulisan, cara lama dan cara baru:
 - grid-columns-gap & grid-row-gap
 - columns-gap & row-gap
 Penggunaan:
  .container {
      /* Cara baru */
      column-gap: <line-size>;
      row-gap: <line-size>;

      /* Cara lama */
      grid-columns-gap: <line-size>;
      grid-row-gap: <line-size>;
  }

Shorthand:
 .container {
     /* Cara baru */
     gap: <grid-row-gap> <grid-columns-gap>;

     /* Cara lama */
     grid-gap: <grid-row-gap> <grid-column-gap>;

 }

Shorthand Untuk grid:
 .container {
     grid: grid-template-rows, grid-template-columns, grid-template-areas, grid-auto-rows, grid-auto-columns, grid-auto-flow;
 }

note: lambang (|) == atau