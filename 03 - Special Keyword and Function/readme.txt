Special Function & Keyword:
 - repeat() => Menentukan ukuran grid track secara berulang
    .container {
        display: grid;
        grid-template-columns: repeat(9, 1fr);
    }
 - min-content & max-content => Menentukan seberapa besar ukuran grid track berdasarkan content pada sebuah item
    .container {
        display: grid;
        grid-template-columns: min-content | max-content;
    }
 - minmax() => Menentukan ukuran minimal dan maksimal dari grid track
    .container {
        display: grid;
        grid-template-columns: minmax(200px, 300px);
    }
 - auto-fill & auto-fit => Menentukan jumlah item untuk berada pada grid track(Biasa digunakan dalam keyword repeat())
    .container {
        display: grid;
        grid-template-columns: repeat(auto-fit, 150px);
    }

note: lambang (|) == atau