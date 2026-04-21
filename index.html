<?php
session_start();
// Cek apakah user sudah login
if($_SESSION['status'] != "login"){
    header("location:login.php?pesan=belum_login");
	}
?>

<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <title>Rekam User & Location</title>
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website Responsif</title>
    <link rel="stylesheet" href="style.css">
</head>
<link rel="stylesheet" href="style.css">
<body>
	<h1>Monitoring Akun dan Lokasi Pendataan (MONALISA)SE 2026</h1>
	<div class="form-container">
    <form id="locationForm" action="save.php" method="POST">
        <!-- Mengubah input text menjadi select (Listbox) -->
        <select name="username" required style="width: 100%; padding: 8px; margin-bottom: 15px;">
            <option value="">Pilih Akun</option>
            <?php
            // Koneksi ke database
            $conn = new mysqli("localhost", "root", "", "db_lokasi");
            
            // Ambil data username dari tabel user
            $sql = "SELECT nm_akun FROM user_akun ORDER BY nm_akun ASC";
            $result = $conn->query($sql);

            if ($result->num_rows > 0) {
                while($row = $result->fetch_assoc()) {
                    echo "<option value='" . $row['nm_akun'] . "'>" . $row['nm_akun'] . "</option>";
                }
            }
            $conn->close();
            ?>
        </select>
		<select name="kecamatan" required style="width: 100%; padding: 8px; margin-bottom: 15px;">
            <option value="">Pilih Kecamatan</option>
            <?php
            // Koneksi ke database
            $conn = new mysqli("localhost", "root", "", "db_lokasi");
            
            // Ambil data username dari tabel user
            $sql = "SELECT nm_kec FROM list_kec";
            $result = $conn->query($sql);

            if ($result->num_rows > 0) {
                while($row = $result->fetch_assoc()) {
                    echo "<option value='" . $row['nm_kec'] . "'>" . $row['nm_kec'] . "</option>";
                }
            }
            $conn->close();
            ?>
        </select>
		<select name="kelurahan" required style="width: 100%; padding: 8px; margin-bottom: 15px;">
            <option value="">Pilih Kelurahan</option>
            <?php
            // Koneksi ke database
            $conn = new mysqli("localhost", "root", "", "db_lokasi");
            
            // Ambil data username dari tabel user_akun
            $sql = "SELECT nm_kel FROM list_kel";
            $result = $conn->query($sql);

            if ($result->num_rows > 0) {
                while($row = $result->fetch_assoc()) {
                    echo "<option value='" . $row['nm_kel'] . "'>" . $row['nm_kel'] . "</option>";
                }
            }
            $conn->close();
            ?>
		</select>
		<select name="sls" required style="width: 100%; padding: 8px; margin-bottom: 15px;">
            <option value="">Pilih RT/RW/Lingk</option>
            <?php
            // Koneksi ke database
            $conn = new mysqli("localhost", "root", "", "db_lokasi");
            
            // Ambil data username dari tabel user_akun
            $sql = "SELECT nm_sls FROM list_sls";
            $result = $conn->query($sql);

            if ($result->num_rows > 0) {
                while($row = $result->fetch_assoc()) {
                    echo "<option value='" . $row['nm_sls'] . "'>" . $row['nm_sls'] . "</option>";
                }
            }
            $conn->close();
            ?>
		</select>
		<input type="hidden" name="latitude" id="latitude">
        <input type="hidden" name="longitude" id="longitude">
        <button type="submit">Simpan Data</button>
		</div>
    </form>
	</div>

    <script>
        // Mengambil lokasi pengguna saat halaman dimuat
        if (navigator.geolocation) {
            navigator.geolocation.getCurrentPosition(function(position) {
                document.getElementById('latitude').value = position.coords.latitude;
                document.getElementById('longitude').value = position.coords.longitude;
            }, function(error) {
                alert("Izin lokasi ditolak atau gagal mendapatkan lokasi.");
            });
        } else {
            alert("Geolocation tidak didukung oleh browser Anda.");
        }
    </script>
	<a href="logout.php">Logout</a>
</body>
</html>
