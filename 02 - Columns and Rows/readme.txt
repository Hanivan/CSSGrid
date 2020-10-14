CSS Grid Properties >>
Gelombang 1 (Untuk Container):
 - grid-template-columns
 - grid-template-rows
 - grid-auto-columns
 - grid-auto-rows
 - grid-auto-flow
 - grid-template-areas
 - grid-template
 - grid-column-gap
 - grid-row-gap
 - grid-gap
 - grid
 - justify-items
 - align-items
 - place-items
 - justify-content
 - align-content
 - place-content

Gelombang 2 (Untuk Items):
 - grid-column-start
 - grid-column-end
 - grid-row-start
 - grid-row-end
 - grid-column
 - grid-row
 - grid-area
 - justify-self
 - align-self
 - place-self

Pengertian:
grid-template-columns & grid-template-rows => Mendefinisikan kolom/baris dengan cara menuliskan nilai dipisahkan oleh spasi. Nilai merepresentasikan ukuran grid track dan spasi merepresentasikan grid line
 Penggunaan:
  .container {
      display: grid;
      grid-template-columns: <track-size> ... | <line-name> <track-size> ...;
      grid-template-rows: <track-size> ... | <line-name> <track-size> ...;
  }
<track-size>: bisa berupa px, %, auto, atau fr(fraction)
<line-name>: nama yang bisa diberikan pada track

note: lambang (|) => atau

grid-auto-columns & grid-auto-rows => Mengatur ukuran grid track yang tidak dituliskan pada grid-template (implicit track)
 Penggunaan:
  .container {
      grid-auto-columns: <track-size>;
      grid-auto-rows: <track-size>;
  }

grid-auto-flow => Mengatur penempatan item/cell pada grid track, termasuk yang ditulis secara implicit
 Penggunaan:
  .container {
      grid-auto-flow: row | column | row dense | column dense;
  }