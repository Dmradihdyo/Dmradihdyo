- ## Hallo, Everyone 👋 ##
* 👂 Nama saya ... Damar Adi Handoyo
* 🔭 Saya sedang mengerjakan ... TUGAS SEKOLAH 
* 🌱 Saya sedang belajar ... js,php
* 🤝 Saya ingin berkolaborasi di ... NANTI
* 🤔 Saya mencari bantuan dengan ... NANTI
* 💬 Tanya saya tentang ... Hobi??? OLAHRAGA
* ❤️ Saya suka ... Makan
* ⚡ Fakta menarik: ... saya lebih suka Nasi menjadi protein dari pada Nikah sama Tante jihyo

- ### <summary><strong>Contact!!</strong></summary>
  <a href="https://x.com/dmradhdyo">
  <img align="left" alt="Goo's Twitter" width="20px" src="https://simpleicons.now.sh/twitter/495f7e" />
</a>
 <a href="https://www.instagram.com/dmradhdyo/">
  <img align="left" alt="Goo's Instagram" width="20px" src="https://simpleicons.now.sh/instagram/495f7e" />
</a>

<script>
// Informasi diri
const nama = "Nama Anda";
const alamatEmail = "email@example.com";
const alamat = "Alamat Anda";
const telepon = "Nomor Telepon Anda";
const hobi = ["Membaca", "Menulis", "Bersepeda"];

// Fungsi untuk menampilkan informasi diri
function tampilkanInfoDiri() {
    document.getElementById('nama').textContent = nama;
    document.getElementById('alamatEmail').textContent = alamatEmail;
    document.getElementById('alamat').textContent = alamat;
    document.getElementById('telepon').textContent = telepon;

    const hobiList = document.getElementById('hobi');
    hobi.forEach(function(hobiItem) {
        const li = document.createElement('li');
        li.textContent = hobiItem;
        hobiList.appendChild(li);
    });
}

// Memanggil fungsi untuk menampilkan informasi diri setelah halaman dimuat
window.onload = tampilkanInfoDiri;
</script>
