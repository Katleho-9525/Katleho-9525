<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kat</title>
</head>
<body>

    <style>
        body {
            margin: 0;
            background: #0d1117;
            color: #e6edf3;
            font-family: 'Segoe UI', Arial, sans-serif;
            line-height: 1.6;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            padding: 60px 20px;
            text-align: center;
            border: 1px solid #30363d;
            border-radius: 10px;
            border-color: #58a6ff;
        }

        .main_name {
            font-size: 2.5rem;
            font-family: 'Segoe UI', Arial, sans-serif;
            margin: 0 0 10px;
            color: #58a6ff;
        }

        .tagline {
            font-size: 0.9rem;
            font-style: italic;
            margin: 0 0 25px;
            color: #8b949e;
        }

        .bio {
        font-size: 1.05rem;
        margin: 0 0 35px;
        }

        .skills {
        display: flex;
        justify-content: center;
        align-items: center;
        flex-wrap: wrap;
        gap: 20px;
        }

        .skills img {
        height: 45px;
        transition: transform 0.2s ease;
        }

        .skills img:hover {
        transform: translateY(-6px) scale(1.15);
        }

        @media (max-width: 480px) {
        h1 { font-size: 2rem; }
        .tagline { font-size: 1.1rem; }
        .skills img { height: 36px; }
        }
    </style>





    <!-- CONTAINER HTML -->
    <div class="container">
        <section class="name">
            <h1 class="main_name">Katleho Mtimkhulu</h1>
            <h5 class="tagline">Ship it first. Shape it later</h5>
        </section>
        <section class="bio">
            <p>
                I build things that sense, think, and move. Then I break them, fix them, and learn why.
            </p>
            <p>
                Engineering student at Vaal University of Technology, from Tembisa, South Africa.
                I'm happiest where hardware meets code: Arduino and microcontrollers, Python and web tools,
                and Linux boxes running Fedora and Kali.
            </p>
        </section>

        <p class ="skills">
            <!-- Embedded -->
            <img src="https://cdn.simpleicons.org/arduino" alt="Arduino" height="45">
            <img src="https://cdn.simpleicons.org/espressif" alt="ESP32 / Espressif" height="40">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" height="45">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML5" height="45">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript" height="45">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" alt="C" height="45">
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" alt="C++" height="45">

            <!-- Linux and servers and Programming Languages -->
            <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/ubuntu/ubuntu-plain.svg" alt="Ubuntu" height="45">
            <img src="https://cdn.simpleicons.org/fedora" alt="Fedora" height="45">
            <img src="https://cdn.simpleicons.org/popos" alt="Pop!_OS" height="45">
            <img src="https://cdn.simpleicons.org/opensuse" alt="openSUSE" height="45">
            <img src="https://cdn.simpleicons.org/virtualbox" alt="VirtualBox" height="45">
            <img src="https://cdn.simpleicons.org/tailscale" alt="Tailscale" height="45">
            
        </p>
    </div>
</body>
</html>
