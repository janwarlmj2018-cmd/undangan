<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Undangan Pernikahan — Janwar & Suci</title>

    <!-- 🎵 MUSIK: Jalaraning Tresno - Versi Kroncong (YouTube) -->
    <iframe id="yt-music" 
        src="https://www.youtube.com/embed/5iMztimFbu0?autoplay=1&loop=1&playlist=5iMztimFbu0&mute=0" 
        style="display:none;" 
        frameborder="0" 
        allow="autoplay; encrypted-media" 
        allowfullscreen>
    </iframe>

    <style>
        *{margin:0;padding:0;box-sizing:border-box;scroll-behavior:smooth}
        body{font-family:'Segoe UI',serif;color:#5a3e36;background:#fefaf6;line-height:1.6}
        h1,h2,h3{font-family:'Georgia',serif}

        /* Hero Section */
        .hero{height:100vh;display:flex;flex-direction:column;align-items:center;justify-content:center;text-align:center;
            background:linear-gradient(rgba(90,62,54,.6),rgba(90,62,54,.6)),
                        url('https://images.unsplash.com/photo-1519741497674-611481863552?w=1200') center/cover no-repeat;
            color:white;padding:20px;position:relative}
        .hero h1{font-size:clamp(2.5rem,8vw,4.5rem);margin-bottom:10px;letter-spacing:3px}
        .hero .couple{font-size:clamp(1.5rem,5vw,2.5rem);margin:15px 0;font-weight:600}
        .hero .date{font-size:1.3rem;opacity:.9}
        .btn{margin-top:40px;padding:14px 36px;background:white;color:#5a3e36;border-radius:50px;text-decoration:none;
            font-weight:600;transition:.3s;box-shadow:0 4px 15px rgba(0,0,0,.15)}
        .btn:hover{transform:translateY(-3px);box-shadow:0 6px 20px rgba(0,0,0,.2)}

        /* Section Common */
        section{padding:60px 20px;max-width:900px;margin:0 auto}
        .section-title{text-align:center;font-size:2rem;margin-bottom:40px;color:#8b5d4a;position:relative}
        .section-title::after{content:'💍';display:block;margin-top:10px;font-size:1.5rem}

        /* Countdown */
        .countdown{display:flex;justify-content:center;gap:15px;flex-wrap:wrap;margin-top:30px}
        .count-item{background:#fff0e8;padding:20px 25px;border-radius:12px;min-width:90px;text-align:center;box-shadow:0 3px 10px rgba(90,62,54,.1)}
        .count-item span{display:block;font-size:2rem;font-weight:700;color:#8b5d4a}
        .count-item small{color:#886f65}

        /* Couple & Info */
        .couple-wrap{display:flex;justify-content:center;gap:40px;flex-wrap:wrap;text-align:center}
        .person{flex:1 1 250px}
        .person h3{font-size:1.5rem;margin:10px 0 5px;color:#5a3e36}
        .person p{color:#886f65}
        .divider{font-size:2.5rem;align-self:center;color:#d4a373}

        .info-box{background:#fff0e8;padding:30px;border-radius:16px;margin-top:20px;box-shadow:0 3px 12px rgba(90,62,54,.08)}
        .info-box h3{margin-bottom:15px;color:#8b5d4a}
        .info-box p{margin:8px 0}
        a.map-link{color:#8b5d4a;font-weight:600;text-decoration:underline;display:inline-block;margin-top:8px}

        /* Form Ucapan */
        form{background:#fff0e8;padding:30px;border-radius:16px;box-shadow:0 3px 12px rgba(90,62,54,.08)}
        input,textarea{width:100%;padding:12px;margin:8px 0 16px;border:1px solid #e0c5b5;border-radius:8px;font-size:1rem;background:#fff}
        button{background:#8b5d4a;color:white;border:none;padding:12px 30px;border-radius:8px;font-size:1rem;cursor:pointer;transition:.3s}
        button:hover{background:#704a39}

        /* Footer */
        footer{text-align:center;padding:30px;background:#5a3e36;color:#f3e5dc;font-size:.9rem}

        @media(max-width:600px){.couple-wrap{flex-direction:column}}
    </style>
</head>
<body>

<!-- Hero Section -->
<section class="hero">
    <p>Dengan Memohon Rahmat & Ridha Allah SWT</p>
    <h1>UNDANGAN PERNIKAHAN</h1>
    <div class="couple">Janwar & Suci</div>
    <p class="date">📅 Jum'at, 18 September 2026</p>
    <a href="#detail" class="btn" onclick="playMusic()">Lihat Undangan 📩</a>
</section>

<!-- Countdown -->
<section id="detail">
    <h2 class="section-title">Menuju Hari Bahagia</h2>
    <div class="countdown">
        <div class="count-item"><span id="days">00</span><small>Hari</small></div>
        <div class="count-item"><span id="hours">00</span><small>Jam</small></div>
        <div class="count-item"><span id="minutes">00</span><small>Menit</small></div>
        <div class="count-item"><span id="seconds">00</span><small>Detik</small></div>
    </div>
</section>

<!-- Mempelai -->
<section>
    <h2 class="section-title">Kedua Mempelai</h2>
    <div class="couple-wrap">
        <div class="person">
            <h3>Janwar Febriyanto</h3>
            <p>Putra dari Bpk. Suwari & Ibu Ponitri</p>
        </div>
        <div class="divider">❤️</div>
        <div class="person">
            <h3>Suci Rahmawati</h3>
            <p>Putri dari Bpk. Heri Nursio & Ibu Dewi Musyarofa</p>
        </div>
    </div>
</section>

<!-- Acara -->
<section>
    <h2 class="section-title">Akad & Resepsi</h2>
    <div class="info-box">
        <h3>🕌 Akad Nikah</h3>
        <p>📅 Jum'at, 18 September 2026</p>
        <p>⏰ Pukul 08.00 WIB</p>
        <p>📍 Dsn. Suluman Ds. Bades Kec. Pasirian</p>
        <a href="https://maps.app.goo.gl/bzDdork2EipFquSn8" target="_blank" class="map-link">🔗 Buka di Google Maps</a>
    </div>
    <div class="info-box" style="margin-top:25px">
        <h3>🎉 Resepsi</h3>
        <p>📅 Jum'at, 18 September 2026</p>
        <p>⏰ Pukul 13.00 s.d. selesai WIB</p>
        <p>📍 Dsn. Siluman Ds. Bades Kec. Pasirian</p>
        <a href="https://maps.app.goo.gl/bzDdork2EipFquSn8" target="_blank" class="map-link">🔗 Buka di Google Maps</a>
    </div>
</section>

<!-- Ucapan & Doa -->
<section>
    <h2 class="section-title">Kirim Ucapan & Doa</h2>
    <form onsubmit="kirimUcapan(event)">
        <input type="text" id="nama" placeholder="Nama Anda" required>
        <input type="text" id="asal" placeholder="Asal / Kota (opsional)">
        <textarea id="ucapan" rows="4" placeholder="Tulis doa & ucapan untuk kami..." required></textarea>
        <button type="submit">Kirim Ucapan 🤲</button>
    </form>
    <p id="pesan" style="margin-top:15px;color:#2e7d32;display:none">✅ Terima kasih! Ucapan Anda terkirim.</p>
</section>

<!-- Penutup -->
<section style="text-align:center">
    <p style="font-size:1.1rem;max-width:600px;margin:0 auto">
        Merupakan suatu kehormatan dan kebahagiaan bagi kami apabila Bapak/Ibu/Saudara/i berkenan hadir dan memberikan doa restu.<br><br>
        <em>“Dan Kami jadikan pasangan-pasangan kalian untuk bersenang-senang dengannya, lalu kamu menetaplah bersama mereka dan saling mencintai.”</em><br><br>
        Wassalamu'alaikum Warahmatullahi Wabarakatuh ❤️
    </p>
</section>

<footer>
    &copy; 2026 Undangan Pernikahan — Janwar & Suci
</footer>

<script>
// === PUTAR MUSIK SAAT TOMBOL DIKLIK (untuk bypass blokir autoplay) ===
function playMusic(){
    const iframe = document.getElementById('yt-music');
    iframe.src = iframe.src;
}

// === HITUNG MUNDUR — 18 September 2026, 08.00 WIB ===
const targetDate = new Date(2026, 8, 18, 8, 0, 0); 

function updateCountdown(){
    const now = new Date();
    const diff = targetDate - now;
    if(diff <= 0){
        document.getElementById('days').textContent = '00';
        document.getElementById('hours').textContent = '00';
        document.getElementById('minutes').textContent = '00';
        document.getElementById('seconds').textContent = '00';
        return;
    }
    const days = Math.floor(diff / (1000*60*60*24));
    const hours = Math.floor((diff % (1000*60*60*24)) / (1000*60*60));
    const minutes = Math.floor((diff % (1000*60*60)) / (1000*60));
    const seconds = Math.floor((diff % (1000*60)) / 1000);

    document.getElementById('days').textContent = String(days).padStart(2,'0');
    document.getElementById('hours').textContent = String(hours).padStart(2,'0');
    document.getElementById('minutes').textContent = String(minutes).padStart(2,'0');
    document.getElementById('seconds').textContent = String(seconds).padStart(2,'0');
}
setInterval(updateCountdown, 1000);
updateCountdown();

// === FORM UCAPAN ===
function kirimUcapan(e){
    e.preventDefault();
    document.getElementById('pesan').style.display = 'block';
    e.target.reset();
}
</script>

</body>
</html>
