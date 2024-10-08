<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>İbrahim Aybora Tozun - Portföy</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #eef2f3;
        }
        header {
            background: #4a90e2;
            color: #fff;
            padding: 20px;
            text-align: center;
        }
        nav ul {
            list-style: none;
            padding: 0;
        }
        nav ul li {
            display: inline;
            margin: 0 15px;
        }
        nav ul li a {
            color: #fff;
            text-decoration: none;
        }
        section {
            padding: 20px;
            margin: 10px auto;
            background: #fff;
            max-width: 800px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            padding: 10px;
            background: #4a90e2;
            color: #fff;
            position: relative;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>İbrahim Aybora Tozun</h1>
        <nav>
            <ul>
                <li><a href="#hakkimda">Hakkımda</a></li>
                <li><a href="#yetenekler">Yetenekler</a></li>
                <li><a href="#deneyimlerim">Deneyimlerim</a></li>
                <li><a href="#projelerim">Projelerim</a></li>
                <li><a href="#egitim">Eğitim</a></li>
                <li><a href="#iletisim">İletişim</a></li>
            </ul>
        </nav>
    </header>

    <section id="hakkimda">
        <h2>Hakkımda</h2>
        <p>Merhaba! Ben İbrahim Aybora Tozun, yazılım geliştirme alanında tutkuluyu. yönetim bilişim sistemler eğitimi alıyorum. Devler gelir devler gider bi dev kalır ALİ EREN KARATAŞ.</p>
        <p>Teknolojiye olan ilgim ve sürekli öğrenme arzum, beni farklı projelere yönlendiriyor. Analitik düşünme becerim ve detaylara verdiğim önem sayesinde, kullanıcı deneyimini artıracak çözümler geliştirmeyi hedefliyorum.</p>
        <p>Boş zamanlarımda yeni teknolojileri keşfetmek, açık kaynak projelerine katkıda bulunmak ve fotoğraf çekmek gibi hobilerim var. Sizinle tanışmayı ve projelerimde birlikte çalışmayı dört gözle bekliyorum! Hayata korkusuzca bakanlar ölümden de korkmazlar</p>
    </section>

    <section id="yetenekler">
        <h2>Yetenekler</h2>
        <ul>
            <li>HTML5, CSS3 ve JavaScript</li>
            <li>React ve Angular ile SPA geliştirme</li>
            <li>Node.js ile sunucu tarafı programlama</li>
            <li>Veritabanı yönetimi (SQL, MongoDB)</li>
        </ul>
    </section>

    <section id="deneyimlerim">
        <h2>Deneyimlerim</h2>
        <ul>
            <li>
                <strong>ABC Teknoloji</strong> - Yazılım Geliştirici (2022 - Günümüz)
                <p>Kullanıcı deneyimini geliştirmek için web uygulamaları üzerinde çalışıyorum.</p>
            </li>
            <li>
                <strong>XYZ Danışmanlık</strong> - Stajyer Yazılım Geliştirici (2021 - 2022)
                <p>Çeşitli projelerde yer alarak temel yazılım becerilerimi geliştirdim.</p>
            </li>
        </ul>
    </section>

    <section id="projelerim">
        <h2>Projelerim</h2>
        <div class="proje">
            <h3>Web Uygulaması 1</h3>
            <p>Bu proje, kullanıcıların not almasına olanak tanıyan bir web uygulaması.</p>
            <a href="#" target="_blank">Projeyi Görüntüle</a>
        </div>
        <div class="proje">
            <h3>Web Uygulaması 2</h3>
            <p>Bu proje, kullanıcıların günlük görevlerini takip etmelerini sağlayan bir uygulama.</p>
            <a href="#" target="_blank">Projeyi Görüntüle</a>
        </div>
    </section>

    <section id="egitim">
        <h2>Eğitim</h2>
        <ul>
            <li>
                <strong>ABC Üniversitesi</strong> - Bilgisayar Mühendisliği (2018 - 2022)
                <p>Yazılım geliştirme ve veri yapıları üzerine yoğunlaştım.</p>
            </li>
        </ul>
    </section>

    <section id="iletisim">
        <h2>İletişim Bilgileri</h2>
        <form>
            <label for="isim">İsim:</label>
            <input type="text" id="isim" name="isim" required>
            
            <label for="email">E-posta:</label>
            <input type="email" id="email" name="email" required>
            
            <label for="mesaj">Mesaj:</label>
            <textarea id="mesaj" name="mesaj" required></textarea>
            
            <button type="submit">Gönder</button>
        </form>
    </section>

    <footer>
        <p>İbrahim Aybora Tozun</p>
    </footer>
</body>
</html>
