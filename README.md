# Belajar-Tailwind-CSS

Tailwind CSS adalah kerangka kerja CSS sumber terbuka. Fitur utama dari library ini adalah, tidak seperti framework CSS lainnya seperti Bootstrap, library ini tidak menyediakan serangkaian kelas standar untuk elemen seperti tombol atau tabel.

<img src="https://seeklogo.com/images/T/tailwind-css-logo-5AD4175897-seeklogo.com.png" >

<a href="https://tailwindcss.com/">Buka Website Tailwind CSS</a>

Software yang di butuhkan
<ul>
  <li> Web Browser </li>
  <li> Code Editor </li>
  <li> VSCode Extension </li>
  <ul>
    <li> [------------------------] </li>
    <li> Tailwind CSS IntelliSense </li>
    <li> Live Preview </li>
    <li> Post CSS Language Support </li>
    <li> [------------------------] </li>
  </ul>
  <li> NPM (Node.js) </li>
  <li> Terminal </li>
</ul>

Cara instalasi menggunakan NPM
<ul>
  <li> $npm init (Berfungsi untuk menginisiasi folder project, jika ingin langsung bisa tambahkan -y) </li>
  <li> $npm i -D tailwindcss postcss autoprefixer </li>
  <li> $npx tailwindcss init (Untuk menginisiasi tailwind config) </li>
</ul>

#index
content: [ './**/*.{html, js}' ]
<ul>
  <li> ./ (folder root) </li>
  <li> ** (mengecek semua folder yang ada didalamnya) </li>
  <li> * (mengecek semua file apapun yang ada didalamnya) </li>
  <li> *.{html, js} (mengecek semua file apapun yang ada didalamnya selama extensinya html dan js) </li>
</ul>

Konfigurasi TailwindCSS
- Tambahkan sebuah Tailwind directives ke CSS kita, tambahkan @tailwind directives untuk setiap lapisan Tailwind ke file CSS utama Anda.
  </br>example: buat di src/input.css
  </br>@tailwind base;
  </br>@tailwind components;
  </br>@tailwind utilities;
- Mulai untuk building Tailwind CSS
  Jalankan alat CLI untuk memindai file template Anda untuk kelas dan membangun CSS Anda.
  </br>npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
- Hubungkan index.html anda ke output.css
- Done happy hacking
  
<img src="https://anf.al/assets/blog-images/2021-03-06-tailwindcss-review-by-a-backend-developer/tailwindcss.png"/>  
