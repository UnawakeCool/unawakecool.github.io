<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>UnawakeCool | Hub</title>
    <style>
        :root {
            --bg-color: #0f111a;
            --card-bg: #1e2233;
            --accent-color: #5865F2; /* Discord/Gamer Blurple */
            --text-main: #ffffff;
            --text-muted: #a0a5c0;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-main);
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            min-height: 100vi;
        }

        header {
            text-align: center;
            margin-top: 60px;
            margin-bottom: 40px;
        }

        .avatar-placeholder {
            width: 100px;
            height: 100px;
            border-radius: 50%;
            background-color: var(--accent-color);
            display: inline-flex;
            align-items: center;
            justify-content: center;
            font-size: 2.5rem;
            font-weight: bold;
            box-shadow: 0 8px 24px rgba(88, 101, 242, 0.4);
            margin-bottom: 15px;
        }

        h1 {
            margin: 0;
            font-size: 2.5rem;
            letter-spacing: -0.5px;
        }

        p.subtitle {
            color: var(--text-muted);
            font-size: 1.1rem;
            margin-top: 8px;
        }

        main {
            width: 90%;
            max-width: 800px;
            margin-bottom: 60px;
        }

        .section-title {
            font-size: 1.2rem;
            text-transform: uppercase;
            letter-spacing: 2px;
            color: var(--accent-color);
            margin-bottom: 20px;
            border-bottom: 1px solid rgba(255, 255, 255, 0.1);
            padding-bottom: 8px;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .card {
            background-color: var(--card-bg);
            border-radius: 12px;
            padding: 24px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.2);
            transition: transform 0.2s ease, box-shadow 0.2s ease;
            text-decoration: none;
            color: inherit;
            display: block;
        }

        .card:hover {
            transform: translateY(-4px);
            box-shadow: 0 12px 24px rgba(0,0,0,0.3);
            border: 1px solid rgba(88, 101, 242, 0.3);
        }

        .card h3 {
            margin: 0 0 10px 0;
            color: #ffffff;
        }

        .card p {
            margin: 0;
            color: var(--text-muted);
            font-size: 0.95rem;
            line-height: 1.5;
        }

        .tag {
            display: inline-block;
            background: rgba(88, 101, 242, 0.15);
            color: var(--accent-color);
            padding: 4px 8px;
            border-radius: 6px;
            font-size: 0.8rem;
            font-weight: bold;
            margin-top: 15px;
        }
    </style>
</head>
<body>

    <header>
        <div class="avatar-placeholder">U</div>
        <h1>UnawakeCool</h1>
        <p class="subtitle">Developer & Minecraft Server Architect</p>
    </header>

    <main>
        <div class="section-title">My Projects</div>
        <div class="grid">
            
            <!-- Project 1 -->
            <div class="card">
                <h3>Custom Anti-Cheat</h3>
                <p>An asynchronous, modular, and high-performance Spigot/Paper anti-cheat built to secure Minecraft servers without main-thread lag.</p>
                <span class="tag">Java</span>
            </div>

            <!-- Project 2 -->
            <div class="card">
                <h3>Server Utilities</h3>
                <p>Lightweight utility plugins and tools targeted entirely at custom gameplay mechanics and performance optimizations.</p>
                <span class="tag">Bukkit API</span>
            </div>

        </div>
    </main>

</body>
</html>
