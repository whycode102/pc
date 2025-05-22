<!DOCTYPE html>
<html>
<head>
    <title>PC Specs</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&display=swap');
        
        :root {
            --accent: #FFFFFF;
            --bg: #0A0A0A;
            --card: #111111;
            --text: #FFFFFF;
            --subtext: #8A8F98;
        }
        
        body {
            background: var(--bg);
            margin: 0;
            font-family: 'Inter', sans-serif;
            color: var(--text);
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }
        
        .card {
            background: var(--card);
            border-radius: 16px;
            width: 100%;
            max-width: 340px;
            padding: 32px;
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.3);
            text-align: center;
        }
        
        .specs {
            color: var(--subtext);
            font-size: 14px;
            margin-bottom: 20px;
            line-height: 1.6;
        }
        
        .specs-item {
            margin-bottom: 8px;
            text-align: center;
        }
        
        .specs-item strong {
            color: var(--accent);
        }
    </style>
</head>
<body>
    <div class="card">
        <div class="specs">
            <div class="specs-item"><strong>CPU:</strong> Intel Core i5-12400</div>
            <div class="specs-item"><strong>GPU:</strong> NVIDIA GTX 1660 Super</div>
            <div class="specs-item"><strong>RAM:</strong> 16GB DDR4</div>
            <div class="specs-item"><strong>SSD:</strong> Ardor Gaming Ally 256GB</div>
            <div class="specs-item"><strong>SSD:</strong> ADATA XPG SPECTRIX S40G RGB 512GB</div>
            <div class="specs-item"><strong>PSU:</strong> Corsair VS550</div>
            <div class="specs-item"><strong>MB:</strong> Gigabyte B660 DS3H DDR4</div>
        </div>
    </div>
</body>
</html>
