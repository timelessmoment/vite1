<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Undangan Pernikahan</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Selamat Datang di Undangan Kami!</h1>
        <p>Nama Pengantin: [Nama Pengantin]</p>
        <p>Tanggal: 12 Desember 2024</p>
    </header>

    <section id="invitation">
        <img src="desain-canva.png" alt="Undangan Digital" id="invitation-image">
        <p>Anda diundang untuk merayakan pernikahan kami. Harap konfirmasi kehadiran Anda di bawah ini.</p>
    </section>

    <section id="event-details">
        <h2>Detail Acara</h2>
        <p><strong>Tanggal:</strong> 12 Desember 2024</p>
        <p><strong>Waktu:</strong> 10:00 WIB</p>
        <p><strong>Lokasi:</strong> Gedung ABC, Jakarta</p>
    </section>

    <section id="rsvp">
        <h2>RSVP</h2>
        <form action="mailto:emailmu@example.com" method="post" enctype="text/plain">
            <label for="name">Nama:</label><br>
            <input type="text" id="name" name="name"><br>
            <label for="attendance">Kehadiran:</label><br>
            <select id="attendance" name="attendance">
                <option value="Ya, saya akan hadir">Ya, saya akan hadir</option>
                <option value="Tidak bisa hadir">Tidak bisa hadir</option>
            </select><br><br>
            <input type="submit" value="Kirim">
        </form>
    </section>

    <footer>
        <p>Terima kasih atas kehadiran Anda! 🎉</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
