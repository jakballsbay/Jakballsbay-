# Jakballsbay-<!DOCTYPE html>
<html lang="km">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Jakballsbay - វេបសាយចាក់បាល់</title>
    <style>
        body {
            font-family: "Khmer OS", Arial, sans-serif;
            background-color: #f0f0f0;
            margin: 0; padding: 0;
        }
        header {
            background-color: #004080;
            color: white;
            padding: 20px;
            text-align: center;
            font-size: 2em;
        }
        nav {
            background-color: #003366;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            padding: 20px;
            max-width: 900px;
            margin: auto;
            background: white;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h2 {
            color: #004080;
        }
        /* IPTV Embed Video */
        .stream-container {
            position: relative;
            padding-bottom: 56.25%;
            height: 0;
            overflow: hidden;
            max-width: 100%;
            background: black;
        }
        .stream-container iframe {
            position: absolute;
            top:0; left: 0;
            width: 100%;
            height: 100%;
            border: none;
        }
        footer {
            text-align: center;
            padding: 15px;
            background-color: #004080;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        Jakballsbay - វេបសាយចាក់បាល់
    </header>
    <nav>
        <a href="#live">ចាក់បាល់ផ្ទាល់</a>
        <a href="#news">ព័ត៌មានបាល់ទាត់</a>
        <a href="#contact">ទំនាក់ទំនង</a>
    </nav>
    <main>
        <section id="live">
            <h2>ចាក់បាល់ផ្ទាល់</h2>
            <div class="stream-container">
                <!-- ត្រូវប្ដូរលីងនេះជាលីង IPTV របស់អ្នក -->
                <iframe src="https://example.com/iptv-stream" allowfullscreen></iframe>
            </div>
        </section>

        <section id="news">
            <h2>ព័ត៌មានបាល់ទាត់ថ្មីៗ</h2>
            <article>
                <h3>លទ្ធផលបាល់ទាត់លើកថ្មីៗ</h3>
                <p>នៅថ្ងៃនេះក្រុមយើងបានឈ្នះក្នុងការប្រកួតយ៉ាងសង្ហារប៉ុន្មាន...</p>
            </article>
            <article>
                <h3>ព័ត៌មានកីឡាករជាទីចាប់អារម្មណ៍</h3>
                <p>កីឡាករចម្បងបានធ្វើការផ្លាស់ទីទៅក្រុមថ្មីនៅសប្តាហ៍នេះ...</p>
            </article>
        </section>

        <section id="contact">
            <h2>ទំនាក់ទំនង</h2>
            <p>អ៊ីមែល: support@jakballsbay.com</p>
            <p>ទូរស័ព្ទ: +855 12 345 678</p>
        </section>
    </main>

    <footer>
        &copy; 2025 Jakballsbay. រក្សាសិទ្ធិគ្រប់យ៉ាង។
    </footer>
</body>
</html>
