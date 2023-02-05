## CSS Layouting

### Display

    1.  value dari display :
        - inline
        - inline-block
        - block
        - none
    2.  Perbedaan dispaly dan span :
        - div default display nya itu block
        - span default display nya itu inline

### Dimensi & Overflow

    1.  Dimensi
        width & heigh
        px, %, in, cm, mm, pt, pc

    2.  Overflow
        - visible
        - auto
        - hidden
        - scroll

### Box Model

    1.  CSS Box Model terdisi dari:
        - margin
        - border
        - padding
        - content
        - box-sizing

### Website sederhana

    1.  Header
        - index.html
        - style.css
    2.  Hero
        - index.html
        - img/hero.jpg
          docs: https://unsplash.com/s/photos/computer
          gambarnya resize jd 1024 untuk width nanati lebar akan mengikuti
        - style.css
          * panggil image : background-image : url('img/hero.jpg')
          * background-size: cover;
          * background-position: 0 -150px; nol pertama untuk horizontal dan nilai yang kedua vertikal
          * border-bottom: 5px solid lightskyblue;
          * border-top: 5px solid salmon;
    3.  Content
        - index.html
        - style.css
    4.  Footer & Background-image
        - index.html
        - style.css
        - img/food.png
          link : https://www.toptal.com/designers/subtlepatterns/tag/doodle/

### Float

    Float merupakan properti pada CSS untuk mengatur posisi sebuah element.Jadi sebuah element dapat dipaksa untuk berada di sebelah kiri atau kanan dari parent/ pembungkusnya dengan menggunakan properti ini.
        - none
        - left
        - right

    1.  text wrapping
        - index.html
        - img/logo-serepet4.png

    2.  image-gallery
        - image-gallery.html

    3.  multi-column layout
        - multi-column-layout.html

### Clear

    clear berfungsi untuk menghentikan/membersihkan float : left, right & both
    1.  text wrapping
        - index.html
        - img/logo-serepet4.png
    2.  image-gallery
        - image-gallery.html
        jika float:right menggunakan clear:right
        jika float:left menggunakan clear:left
    3.  multi-column layout
        - multi-column-layout.html
        jika ada 2 float right dan right gunakan clear both
