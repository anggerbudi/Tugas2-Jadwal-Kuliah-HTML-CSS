# Tentang Tugas

Tugas berikut adalah tugas 2 yang diberikan pada pertemuan teori ke 3 dengan tema CSS Dasar

## Preview

Untuk melihat website tanpa mengunduh file dapat membuka link hosting berikut [Jadwalku](https://anggerbudi.github.io/).

## Halaman Index

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Menu</title>
        <link rel="stylesheet" href="style.css">
    </head>
    
    <video id="bg-video" autoplay loop muted playsinline>
        <source src="Fireplace.mp4" type="video/mp4">
    </video>

    <body class="menu">

        <header>
            <h2 class="logo">Hello</h2>
            <nav class="navigation">
                <a href="about.html">About</a>
                <a href="jadwal.html">Schedule</a>
            </nav>
        </header>
        
        <main>
            <section id="quote_generator">
                <h1>Remember this</h1>
                    <div class="quote_container">
                        <h2>
                            <i class="quote_left"></i>
                            <span class="quote" id="quote">"Ad Maiora Natus Sum"</span>
                            <i class="quote_right"></i>
                        </h2>
                        <p class="author" id="author">Aku dilahirkan untuk hal-hal besar</p>
                        <hr />
            </section>
        </main>
    </body>
</html>
```

## Halaman Schedule

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Schedule</title>
        <link rel="stylesheet" href="style.css">
    </head>

    
        <video id="bg-video" autoplay loop muted playsinline>
        <source src="Fireplace.mp4" type="video/mp4">
    </video>
    


    <body class="jadwal">
        <header>
            <h2 class="logo">Hello</h2>
            <nav class="navigation">
                <a href="about.html">About</a>
                <a href="index.html">Menu</a>
            </nav>
        </header>


        <main class="table">
            <section class="table_header">
                <h1>Jadwal Kuliah</h1>
            </section>
            <section class="table_body">
                <table>
                    <thead>
                        <tr>
                            <th> Hari/ Jam </th>
                            <th> 07-08 </th>
                            <th> 08-09 </th>
                            <th> 09-10 </th>
                            <th> 10-11 </th>
                            <th> 11-12 </th>
                            <th> 12-13 </th>
                            <th> 13-14 </th>
                            <th> 14-15 </th>
                            <th> 15-16 </th>
                            <th> 16-17 </th>
                        </tr>
                    </thead>
                    <tbody class="isi">
                        <tr>
                            <td>Senin</td>
                            <td>IMK B K.207</td>
                            <td>IMK B K.207</td>
                            <td>PAD K LBD C</td>
                            <td>PAD K LBD C</td>
                            <td></td>
                            <td></td>
                            <td>SDNL E LKD B</td>
                            <td>SDNL E LKD B</td>
                            <td>Platform LBD C</td>
                            <td>Platform LBD C</td>
                        </tr>
                        <tr>
                            <td>Selasa</td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td>ASA D K.207</td>
                            <td>ASA D K.207</td>
                            <td>ASA D K.207</td>
                            <td></td>
                            <td></td>
                        </tr>
                        <tr>
                            <td>Rabu</td>
                            <td>Platform EP Jarkom B</td>
                            <td>Platform EP Jarkom B</td>
                            <td>Platform EP Jarkom B</td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td>Kompardis B K.414</td>
                            <td>Kompardis B K.414</td>
                            <td></td>
                            <td></td>
                        </tr>
                        <tr>
                            <td>Kamis</td>
                            <td></td>
                            <td>RPL D K.312</td>
                            <td>RPL D K.312</td>
                            <td>Etika Profesi B K.311</td>
                            <td>Etika Profesi B K.311</td>
                            <td></td>
                            <td></td>
                            <td>RPL DP LBD C</td>
                            <td>RPL DP LBD C</td>
                            <td>RPL DP LBD C</td>
                        </tr>
                        <tr>
                            <td>Jumat</td>
                            <td>PAD KP LBD C</td>
                            <td>PAD KP LBD C</td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td>SDNL EP LKD A</td>
                            <td>SDNL EP LKD A</td>
                            <td>SDNL EP LKD A</td>
                        </tr>
                        <tr>
                            <td>Sabtu</td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                        </tr>
                    </tbody>
                </table>
            </section>
        </main>
    </body>


</html>
```

## Halaman About

```html
<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>About Me</title>
        <link rel="stylesheet" href="style_about.css">
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.css" integrity="sha512-5A8nwdMOWrSz20fDsjczgUidUBR8liPYU+WymTZP1lmY9G6Oc7HlZv156XqnsgNUzTyMefFTcsFH/tnJE/+xBg==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    </head>

    <!--
        <video id="bg-video" autoplay loop muted playsinline>
        <source src="Fireplace.mp4" type="video/mp4">
    </video>
    -->

    <body class="about">

        <header>
            <h2 class="logo">Hello</h2>
            <nav class="navigation">
                <a href="index.html">Menu</a>
                <a href="jadwal.html">Schedule</a>
            </nav>
        </header>

        <main class="aboutIsi">
            <div class="container">
                <div class="kiri">
                    <div class="profil">
                        <div class="foto">
                            <img src="profilePicture.png" alt="Profile Picture">
                        </div>
                        <h2>Martinus Angger<br><span>College Student</span></h2>
                    </div>

                    <div class="kontak">
                        <h3 class="title">Info Kontak</h3>
                        <ul>
                            <li>
                                <span class="icon"><i class="fa fa-phone" aria-hidden="true"></i></span>
                                <span class="text">+62 8789 6594 6902</span>
                            </li>
                            <li>
                                <span class="icon"><i class="fa fa-envelope" aria-hidden="true"></i></span>
                                <span class="text">martinus@outlook.com</span>
                            </li>
                            <li>
                                <span class="icon"><i class="fa fa-github" aria-hidden="true"></i></span>
                                <span class="text">anggerbudi.github.io</span>
                            </li>
                            <li>
                                <span class="icon"><i class="fa fa-instagram" aria-hidden="true"></i></span>
                                <span class="text">@martinus_angger</span>
                            </li>
                            <li>
                                <span class="icon"><i class="fa fa-globe" aria-hidden="true"></i></span>
                                <span class="text">Yogyakarta, Indonesia</span>
                            </li>
                        </ul>
                    </div>

                    
                    <div class="kontak edukasi">
                        <h3 class="title">Pendidikan</h3>
                        <ul>
                            <li>
                                <h5>2021 - 2025</h5>
                                <h4>Informatika</h4>
                                <h4>Universitas Sanata Dharma</h4>
                            </li>
                            <li>
                                <h5>2018 - 2021</h5>
                                <h4>MIPA</h4>
                                <h4>SMA Kolese De Britto</h4>
                            </li>
                            <li>
                                <h5>2015 - 2018</h5>
                                <h4>SMP Pangudi Luhur 1 Yogyakarta</h4>
                            </li>
                        </ul>
                    </div>

                    <div class="kontak bahasa">
                        <h3 class="title">Bahasa</h3>
                        <ul>
                            <li>
                                <span class="text">Indonesia</span>
                                <span class="persen"><div style="width: 100%;"></div></span>
                            </li>
                            <li>
                                <span class="text">Inggris</span>
                                <span class="persen"><div style="width: 75%;"></div></span>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="kanan">
                    <div class="tentang">
                        <h2 class="judul2">Profil</h2>
                        <p>Saya adalah mahasiswa informatika yang bercita-cita menjadi System Analyst. Saya memiliki pengetahuan mengenai teknologi informasi dan kemampuan menganalisis serta merancang solusi sistem yang efektif. 
                        <br><br>
                        Saya juga memiliki kemampuan kerja sama tim yang baik dan komunikasi yang efektif. Saya siap untuk terus belajar dan berkembang untuk mencapai kesuksesan sebagai System Analyst.</p>
                    </div>
                    <div class="tentang">
                        <h2 class="judul2">Pengalaman</h2>
                        <div class="box">
                        <div class="tahun">
                            <h5>2018 - sekarang</h5>
                            <h5>Discord Server Moderator</h5>
                        </div>
                        <div class="text">
                            <h4>Lead Moderator</h4>
                            <p>Dalam pekerjaan mereka, moderator Discord harus memiliki kemampuan untuk berkomunikasi dengan baik,
                               memahami aturan server dengan baik, dan dapat bekerja sama dengan admin dan pengguna untuk menciptakan lingkungan yang aman dan menyenangkan bagi semua orang.</p>
                        </div>
                        </div>
                        <div class="box">
                        <div class="tahun">
                            <h5>2020 - sekarang</h5>
                            <h5>Minecraft Mod Tester</h5>
                        </div>
                        <div class="text">
                            <h4>Alpha Tester</h4>
                            <p>Dalam pekerjaan mereka, tester mod Minecraft harus memiliki pengetahuan yang baik tentang permainan Minecraft dan modifikasi yang tersedia.
                               Mereka harus juga memiliki kemampuan untuk mengidentifikasi masalah dan memberikan saran yang konstruktif kepada pengembang.
                               Tester mod Minecraft harus berhati-hati dan teliti dalam melakukan pengujian dan memberikan umpan balik yang jelas dan objektif.</p>
                        </div>
                        </div>
                        <div class="box">
                        <div class="tahun">
                            <h5></h5>
                            <h5></h5>
                        </div>
                        <div class="text">
                            <h4></h4>
                            <p></p>
                        </div>
                        </div>
                    </div>
                    <div class="skill">
                        <h2 class="judul2">Skill</h2>
                        <div class="box">
                            <h4>Java</h4>
                            <div class="persen">
                                <div style="width: 25%;"></div>
                            </div>
                        </div>
                        <div class="box">
                            <h4>HTML</h4>
                            <div class="persen">
                                <div style="width: 45%;"></div>
                            </div>
                        </div>
                        <div class="box">
                            <h4>CSS</h4>
                            <div class="persen">
                                <div style="width: 40%;"></div>
                            </div>
                        </div>
                        <div class="box">
                            <h4>Javascript</h4>
                            <div class="persen">
                                <div style="width: 15%;"></div>
                            </div>
                        </div>
                        <div class="box">
                            <h4>Python</h4>
                            <div class="persen">
                                <div style="width: 55%;"></div>
                            </div>
                        </div>
                    </div>

                    <div class="tentang minat">
                        <h2 class="judul2">Minat</h2>
                        <ul>
                            <li><i class="fa fa-code" aria-hidden="true"></i> Coding</li>
                            <li><i class="fa fa-gamepad" aria-hidden="true"></i> Gaming</li>
                            <li><i class="fa fa-plane" aria-hidden="true"></i> Travelling</li>
                            <li><i class="fa fa-motorcycle" aria-hidden="true"></i> Riding</li>
                        </ul>
                    </div>
                </div>
            </div>

        </main>
        
    
    </body>
</html>
```
