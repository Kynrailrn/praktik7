# praktik7
TugasPweb7
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Document</title>
</head>
<style>
    body {
        margin: 0;
    }
    header {
        display: flex;
        background-color: blue;
        justify-content: space-between;
        padding: 10px 15px;
        align-items: center;

        & ul{
            display: flex;
            list-style: none;
        }
        & a {
            color: white;
            font-weight: bold;
            margin-right: 10px;
            text-decoration: none;
        }
    }
    .img img{
        width: 200px;
    }
    #banner {
        height: 100vh;
        width: 100%;
        background: url(https://nurulfikri.ac.id/wp-content/uploads/slider/cache/b9cdbba1a0e7c5c45cc35ca06eaebf93/Banner-Web-1-scaled.webp);
        display: flex; 
        align-items: center;
            & .promosi{
            width: 25%;
            margin-left: 20px;
            color: white;
        }
        & h2 {
                background-color: blue;
                text-align: justify;
                padding: 2px;
                margin-bottom: -16px;
                text-transform: capitalize;
            }
            & p {
                background-color: orange;
                text-align: justify;
                padding: 2px;
            }
    
    }
    #prodi {
        background-color: rgb(91, 91, 219);
        width: 100%;
        display: flex;
        flex-wrap: wrap;
        padding: 15px;
        justify-content: center;
        & .card {
            background: white;
            width: 25%;
            border-radius: 15px;
            padding: 2px 20px 10px 20px;
            margin: 5px;
        }
        .btn-mobile{
            border:1px solid blue;
            padding: 2px;
            border-radius: 15px;
        }
    }

</style>
<body>
    <header>
        <div class="img">
            <img src="img/gojo.jpg" alt="STT NF">
        </div>
        <ul>
            <li><a href="">Beranda</a></li>
            <li><a href="">Profile</a></li>
            <li><a href="">Program</a></li>
            <li><a href="">Akademi</a></li>
            <li><a href="">Penelitian</a></li>
        </ul>
    </header>
    <main>
        <section id="banner">
            <div class="promosi">
                <h2>PENDAFTARAAN MAHASISWA BARU ADMISI STT NF DIBUKA</h2>
                <p class="welcome">
PENDAFTARAN MAHASISWA BARU ADMISI STT-NF DIBUKA
Selamat datang di kampus STT-NF. Kami sangat senang dapat menawarkan dunia pengetahuan IT dan bisnis yang sesuai dengan perkembangan zaman sekarang.
                </p>
            </div>
        </section>
        <section id="prodi">
            <div class="card">
                <h4>
                    Info Pendaftaran Mahasiswa Baru
                </h4>
                <P>
                    Informasi Penerimaan Mahasiswa Baru STT Nurul Fikri mengenai persyaratan, alur pendaftaran, biaya, dll.
                </P>
                <a href="" class="btn-mobile">Admisi Pendaftaran/a>
            </div>
            <div class="card">
                <h4>
                    Info Pendaftaran Mahasiswa Baru
                </h4>
                <P>
                    Informasi Penerimaan Mahasiswa Baru STT Nurul Fikri mengenai persyaratan, alur pendaftaran, biaya, dll.
                </P>
                <a href="" class="btn-mobile">Admisi Pendaftaran/a>
            </div>
            <div class="card">
                <h4>
                    Info Pendaftaran Mahasiswa Baru
                </h4>
                <P>
                    Informasi Penerimaan Mahasiswa Baru STT Nurul Fikri mengenai persyaratan, alur pendaftaran, biaya, dll.
                </P>
                <a href="" class="btn-mobile">Admisi Pendaftaran/a>
            </div>
            <div class="card">
                <h4>
                    Info Pendaftaran Mahasiswa Baru
                </h4>
                <P>
                    Informasi Penerimaan Mahasiswa Baru STT Nurul Fikri mengenai persyaratan, alur pendaftaran, biaya, dll.
                </P>
                <a href="" class="btn-mobile">Admisi Pendaftaran
            </div>
            <div class="card">
                <h4>
                    Info Pendaftaran Mahasiswa Baru
                </h4>
                <P>
                    Informasi Penerimaan Mahasiswa Baru STT Nurul Fikri mengenai persyaratan, alur pendaftaran, biaya, dll.
                </P>
                <a href="" class="btn-mobile">Admisi Pendaftaran
            </div>
            <div class="card">
                <h4>
                    Info Pendaftaran Mahasiswa Baru
                </h4>
                <P>
                    Informasi Penerimaan Mahasiswa Baru STT Nurul Fikri mengenai persyaratan, alur pendaftaran, biaya, dll.
                </P>
                <a href="" class="btn-mobile">Admisi Pendaftaran/a>
            </div>
        </section>
    </main>
</body>
</html>
