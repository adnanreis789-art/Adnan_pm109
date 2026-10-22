<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Benim Bağlantılarım</title>
    <style>
        body {
            background-color: #0f172a;
            color: white;
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            margin: 0;
        }
        .container {
            text-align: center;
            width: 90%;
            max-width: 400px;
        }
        .avatar {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            margin-bottom: 15px;
            border: 2px solid #38bdf8;
        }
        h1 {
            font-size: 24px;
            margin-bottom: 5px;
        }
        p {
            color: #94a3b8;
            margin-bottom: 25px;
        }
        .links a {
            display: block;
            background-color: #1e293b;
            color: white;
            padding: 15px;
            margin: 10px 0;
            border-radius: 12px;
            text-decoration: none;
            font-weight: bold;
            transition: 0.3s;
            border: 1px solid #334155;
        }
        .links a:hover {
            background-color: #38bdf8;
            color: #0f172a;
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Profil Resmi Linki -->
        <img class="avatar" src="https://via.placeholder.com/100" alt="Profil">
        
        <!-- İsmin -->
        <h1>Adnan Reis</h1>
        <p>Sosyal medya hesaplarım ve bağlantılarım</p>

        <!-- Linklerin -->
        <div class="links">
            <a href="https://instagram.com/kullanici_adin" target="_blank">Instagram</a>
            <a href="https://youtube.com" target="_blank">YouTube</a>
            <a href="https://discord.gg" target="_blank">Discord Sunucum</a>
        </div>
    </div>
</body>
</html>
