<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Toko Oleh-oleh</title>
    <link rel="stylesheet" href="styles.css"> <!-- Link to external CSS -->
</head>
<body>
    <header>
        <h1>Selamat Datang di Toko Oleh-oleh</h1>
        <nav>
            <ul>
                <li><a href="#produk">Produk</a></li>
                <li><a href="#pesan">Pesan Sekarang</a></li>
                <li><a href="#kontak">Kontak Kami</a></li>
            </ul>
        </nav>
    </header>

    <section id="produk">
        <h2>Produk Lokal Kami</h2>
        <div class="produk-list">
            <div class="produk">
                <img src="produk1.jpg" alt="Produk 1">
                <h3>Produk 1</h3>
                <p>Rp 50,000</p>
                <button class="pesan-btn">Pesan</button>
            </div>
            <div class="produk">
                <img src="produk2.jpg" alt="Produk 2">
                <h3>Produk 2</h3>
                <p>Rp 75,000</p>
                <button class="pesan-btn">Pesan</button>
            </div>
            <!-- Produk lainnya bisa ditambahkan -->
        </div>
    </section>

    <section id="pesan">
        <h2>Formulir Pemesanan</h2>
        <form action="pesan.php" method="post">
            <label for="nama">Nama:</label>
            <input type="text" id="nama" name="nama" required><br>
            
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required><br>

            <label for="produk">Pilih Produk:</label>
            <select id="produk" name="produk">
                <option value="produk1">Produk 1</option>
                <option value="produk2">Produk 2</option>
                <!-- Tambahkan produk lainnya -->
            </select><br>

            <label for="jumlah">Jumlah:</label>
            <input type="number" id="jumlah" name="jumlah" min="1" required><br>

            <label for="alamat">Alamat Pengiriman:</label>
            <textarea id="alamat" name="alamat" required></textarea><br>

            <button type="submit">Pesan Sekarang</button>
        </form>
    </section>

    <footer id="kontak">
        <h2>Kontak Kami</h2>
        <p>Email: info@tokooleh.com</p>
        <p>Telepon: 08123456789</p>
    </footer>

    <script src="scripts.js"></script> <!-- Link to external JavaScript -->
</body>
</html>

