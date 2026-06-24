<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Holographic Epigraphic Matrix | README</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        body {
            font-family: 'Segoe UI', system-ui, -apple-system, sans-serif;
            background: #050a15;
            color: #f0f4ff;
            line-height: 1.6;
            padding: 40px 20px;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            background: rgba(6, 18, 34, 0.92);
            border-radius: 20px;
            border: 1px solid rgba(45, 212, 191, 0.2);
            padding: 40px 48px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.6);
        }
        h1 {
            font-family: 'Georgia', serif;
            font-size: 2.2rem;
            color: #2dd4bf;
            margin-bottom: 8px;
            letter-spacing: 0.5px;
        }
        h1 .accent {
            color: #a78bfa;
        }
        .subtitle {
            font-size: 1rem;
            color: #94a3b8;
            margin-bottom: 30px;
            border-bottom: 1px solid rgba(45,212,191,0.1);
            padding-bottom: 16px;
        }
        .badges {
            display: flex;
            flex-wrap: wrap;
            gap: 10px;
            margin-bottom: 28px;
        }
        .badge {
            background: rgba(45,212,191,0.08);
            border: 1px solid rgba(45,212,191,0.15);
            padding: 4px 14px;
            border-radius: 20px;
            font-size: 0.7rem;
            font-family: monospace;
            color: #2dd4bf;
        }
        .badge.license {
            color: #fbbf24;
            border-color: rgba(251,191,36,0.2);
            background: rgba(251,191,36,0.06);
        }
        h2 {
            font-family: 'Georgia', serif;
            font-size: 1.3rem;
            color: #e0ecff;
            margin-top: 32px;
            margin-bottom: 12px;
            border-left: 3px solid #2dd4bf;
            padding-left: 14px;
        }
        h2 .emoji {
            color: #a78bfa;
        }
        p {
            color: #cbd5e1;
            margin-bottom: 12px;
            font-size: 0.95rem;
        }
        ul, ol {
            color: #cbd5e1;
            margin: 10px 0 16px 24px;
            font-size: 0.95rem;
        }
        ul li, ol li {
            margin-bottom: 6px;
        }
        code {
            background: rgba(255,255,255,0.04);
            padding: 2px 10px;
            border-radius: 6px;
            font-family: 'Courier New', monospace;
            font-size: 0.85rem;
            color: #2dd4bf;
            border: 1px solid rgba(45,212,191,0.06);
        }
        pre {
            background: rgba(0,0,0,0.4);
            border: 1px solid rgba(45,212,191,0.1);
            border-radius: 10px;
            padding: 16px 20px;
            overflow-x: auto;
            font-family: 'Courier New', monospace;
            font-size: 0.8rem;
            color: #cbd5e1;
            margin: 12px 0 16px 0;
            line-height: 1.5;
        }
        pre .cyan { color: #2dd4bf; }
        pre .gold { color: #fbbf24; }
        pre .purple { color: #a78bfa; }
        pre .green { color: #34d399; }
        pre .pink { color: #f472b6; }
        .feature-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 16px;
            margin: 16px 0;
        }
        .feature-card {
            background: rgba(255,255,255,0.02);
            border: 1px solid rgba(255,255,255,0.04);
            border-radius: 10px;
            padding: 14px 18px;
            transition: all 0.3s;
        }
        .feature-card:hover {
            background: rgba(45,212,191,0.03);
            border-color: rgba(45,212,191,0.08);
        }
        .feature-card .icon {
            font-size: 1.2rem;
            margin-right: 6px;
        }
        .feature-card h4 {
            color: #e0ecff;
            font-size: 0.85rem;
            margin-bottom: 2px;
        }
        .feature-card p {
            font-size: 0.8rem;
            color: #94a3b8;
            margin-bottom: 0;
        }
        .screenshot-placeholder {
            background: rgba(0,0,0,0.3);
            border: 2px dashed rgba(45,212,191,0.15);
            border-radius: 12px;
            padding: 40px 20px;
            text-align: center;
            color: #94a3b8;
            margin: 16px 0;
            font-size: 0.9rem;
        }
        .screenshot-placeholder .icon {
            font-size: 3rem;
            display: block;
            margin-bottom: 8px;
        }
        .divider {
            border: none;
            border-top: 1px solid rgba(45,212,191,0.08);
            margin: 28px 0;
        }
        .footer {
            margin-top: 30px;
            padding-top: 20px;
            border-top: 1px solid rgba(45,212,191,0.08);
            font-size: 0.8rem;
            color: #64748b;
            text-align: center;
        }
        .footer a {
            color: #2dd4bf;
            text-decoration: none;
        }
        .footer a:hover {
            text-decoration: underline;
        }
        @media (max-width: 700px) {
            .container { padding: 24px 16px; }
            h1 { font-size: 1.6rem; }
            .feature-grid { grid-template-columns: 1fr; }
        }
        .inline-code {
            background: rgba(255,255,255,0.04);
            padding: 1px 6px;
            border-radius: 4px;
            font-family: monospace;
            font-size: 0.8rem;
            color: #2dd4bf;
        }
    </style>
</head>
<body>

<div class="container">

    <!-- Header -->
    <h1>◈ Holographic <span class="accent">Epigraphic Matrix</span></h1>
    <div class="subtitle">
        Interactive 3D visualization of 6 critical early Islamic inscriptions (24 AH – c. 100 AH)
    </div>

    <!-- Badges -->
    <div class="badges">
        <span class="badge">📜 Epigraphy</span>
        <span class="badge">🏛️ 3D Visualization</span>
        <span class="badge license">📄 MIT License</span>
        <span class="badge">🔊 Audio Narration</span>
        <span class="badge">🖥️ Three.js</span>
        <span class="badge">🌐 GitHub Pages</span>
    </div>

    <!-- Description -->
    <p>
        The <strong>Holographic Epigraphic Matrix</strong> is an immersive 3D web application that visualizes six of the 
        most critical early Islamic inscriptions. Each inscription is represented as a holographic marker on an interactive 
        map, allowing users to explore epigraphic data, Arabic/English translations, spectrometry metrics, 
        geographical significance, and credible APA references in a futuristic academic interface.
    </p>

    <!-- Demo Notice -->
    <div class="screenshot-placeholder">
        <span class="icon">📸</span>
        <strong style="color:#e0ecff;">Live Demo Available</strong><br>
        View the interactive 3D map at: <br>
        <code style="font-size:1rem; color:#2dd4bf;">https://yourusername.github.io/Holographic-Epigraphic-Matrix/</code>
    </div>

    <!-- Features -->
    <h2>✨ Features</h2>
    <div class="feature-grid">
        <div class="feature-card">
            <span class="icon">🗺️</span>
            <h4>Interactive 3D Map</h4>
            <p>Explore 6 inscriptions on a holographic globe with intuitive drag, zoom, and rotate controls.</p>
        </div>
        <div class="feature-card">
            <span class="icon">📜</span>
            <h4>Epigraphic Data</h4>
            <p>Access detailed inscription information including original Arabic text, English translation, and historical context.</p>
        </div>
        <div class="feature-card">
            <span class="icon">🔬</span>
            <h4>Spectrometry Metrics</h4>
            <p>View lab analysis data including substrate formation, elemental profiles, and weathering indices.</p>
        </div>
        <div class="feature-card">
            <span class="icon">📚</span>
            <h4>APA References</h4>
            <p>Credible academic sources for each inscription with direct links to publications and UNESCO listings.</p>
        </div>
        <div class="feature-card">
            <span class="icon">🔊</span>
            <h4>Audio Narration</h4>
            <p>Listen to inscription names spoken aloud with a single click. Welcome audio guides your exploration.</p>
        </div>
        <div class="feature-card">
            <span class="icon">🖱️</span>
            <h4>3D Rock Models</h4>
            <p>View stylized 3D representations of each inscription with photographic textures and interactive controls.</p>
        </div>
    </div>

    <hr class="divider">

    <!-- Inscriptions -->
    <h2>🏛️ The 6 Inscriptions</h2>
    <ul>
        <li><strong>[24 AH] Zuhayr Inscription</strong> — AlUla, Saudi Arabia <span style="color:#94a3b8;">· UNESCO Memory of the World</span></li>
        <li><strong>[24 AH] Ghar al-Khail Cave Inscription</strong> — Mada'in Salih, Saudi Arabia <span style="color:#94a3b8;">· Saudi Heritage Commission</span></li>
        <li><strong>[58 AH] Mu'awiya Dam Inscription</strong> — Wadi al-Khanaq, Ta'if <span style="color:#94a3b8;">· Umayyad civil engineering record</span></li>
        <li><strong>[c. 60 AH] Throne Verse Graffito</strong> — Al-Hawra Coastal Outpost <span style="color:#94a3b8;">· Early Quranic inscription</span></li>
        <li><strong>[93 AH] Usays Graffito</strong> — Jabal Usays, Syria <span style="color:#94a3b8;">· Umayyad military frontier</span></li>
        <li><strong>[c. 100 AH] Darb Zubayda Boundary Matrix</strong> — Dhali' al-Nis, Hail <span style="color:#94a3b8;">· Pilgrim route inscription</span></li>
    </ul>

    <hr class="divider">

    <!-- Installation -->
    <h2>🚀 Quick Start</h2>
    <pre>
<span class="cyan"># Clone the repository</span>
git clone https://github.com/yourusername/Holographic-Epigraphic-Matrix.git

<span class="cyan"># Navigate to project folder</span>
cd Holographic-Epigraphic-Matrix

<span class="cyan"># Open in browser (or use Live Server)</span>
open index.html

<span class="cyan"># Or use Python's built-in server</span>
python -m http.server 8000
<span class="cyan"># Visit: http://localhost:8000</span>
    </pre>

    <h2>📸 Adding Your Images</h2>
    <p>
        Place your inscription photographs in the same folder as <code>index.html</code> with these exact filenames:
    </p>
    <pre>
<span class="gold">1.png</span>   <span class="pink"># Zuhayr Inscription</span>
<span class="gold">2.png</span>   <span class="pink"># Ghar al-Khail Cave</span>
<span class="gold">3.png</span>   <span class="pink"># Mu'awiya Dam</span>
<span class="gold">4.png</span>   <span class="pink"># Throne Verse</span>
<span class="gold">5.png</span>   <span class="pink"># Usays Graffito</span>
<span class="gold">6.png</span>   <span class="pink"># Darb Zubayda</span>
    </pre>

    <hr class="divider">

    <!-- Dependencies -->
    <h2>📦 Dependencies</h2>
    <ul>
        <li><a href="https://threejs.org/" style="color:#2dd4bf;">Three.js</a> (r128+) — MIT License</li>
        <li><a href="https://github.com/mrdoob/three.js/tree/dev/examples/js/controls/OrbitControls.js" style="color:#2dd4bf;">OrbitControls</a> — Three.js extension</li>
        <li><a href="https://developer.mozilla.org/en-US/docs/Web/API/SpeechSynthesis" style="color:#2dd4bf;">Web Speech API</a> — Built into modern browsers</li>
    </ul>

    <hr class="divider">

    <!-- License -->
    <h2>📄 License</h2>
    <p>
        This project is licensed under the <strong>MIT License</strong> — you are free to use, modify, and distribute 
        this software for any purpose, provided you retain the copyright notice.
    </p>
    <pre>
<span class="gold">MIT License</span>

Copyright (c) 2026 [Your Name]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

[View full license in the <span class="cyan">LICENSE</span> file]
    </pre>

    <hr class="divider">

    <!-- Citation -->
    <h2>📖 Citation</h2>
    <p>
        If you use this tool in your research or teaching, please cite it as:
    </p>
    <pre>
<span class="purple">@misc</span>{epigraphic-matrix-2026,
    title  = {Holographic Epigraphic Matrix: Interactive 3D Viewer for Early Islamic Inscriptions},
    author = {[Your Name]},
    year   = {2026},
    url    = {https://github.com/yourusername/Holographic-Epigraphic-Matrix}
}
    </pre>

    <hr class="divider">

    <!-- Acknowledgements -->
    <h2>🙏 Acknowledgements</h2>
    <ul>
        <li><strong>Saudi Heritage Commission</strong> — Primary source for inscription documentation</li>
        <li><strong>UNESCO</strong> — Memory of the World Register for Zuhayr Inscription</li>
        <li><strong>Discover Islamic Art (MWNF)</strong> — Throne Verse inscription entry</li>
        <li><strong>Three.js Community</strong> — 3D rendering framework</li>
    </ul>

    <hr class="divider">

    <!-- Footer -->
    <div class="footer">
        Built with ❤️ for scholars, educators, and digital humanities.<br>
        <a href="https://github.com/yourusername/Holographic-Epigraphic-Matrix">GitHub Repository</a> ·
        <a href="https://yourusername.github.io/Holographic-Epigraphic-Matrix/">Live Demo</a> ·
        <a href="https://opensource.org/licenses/MIT">MIT License</a><br>
        <span style="color:#94a3b8;">© 2026 · All epigraphic data cited from peer-reviewed academic sources</span>
    </div>

</div>

</body>
</html>
