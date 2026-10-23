<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Academic CV - Eduardo da Costa Batista</title>
    <style>
        @page { margin: 0; }
        *, *::before, *::after { box-sizing: border-box; }
        html, body { margin: 0; padding: 0; }
        html { background-color: #ffffff; }
        @media (prefers-color-scheme: dark) {
            html { background-color: #1f1f1f; }
        }
        body {
            padding: 24px 0;
            margin: 0 auto;
            max-width: 900px !important;
            border: none !important;
            background: transparent !important;
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
            color: #1a202c;
            -webkit-font-smoothing: antialiased;
        }
        .page {
            height: 297mm;
            width: 210mm;
            margin: 0 auto 12px auto;
            padding: 16mm 18mm 12mm 18mm;
            background-color: #ffffff;
            border: 1px solid rgba(0, 0, 0, 0.12);
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            position: relative;
            overflow: hidden;
            font-size: 10pt;
            line-height: 1.45;
        }
        @media screen and (max-width: 600px) {
            body { padding: 16px 0; }
            .page {
                margin: 0 auto 8px auto;
                border: none;
                padding: 12px 16px;
                width: 100%;
                height: auto;
            }
        }
        .page-content {
            flex: 1 1 0;
            min-height: 0;
            overflow: hidden;
        }
        .page-content > * + * {
            margin-top: 14px;
        }
        .page-content > :is(h1, h2, h3, h4) + * {
            margin-top: 6px;
        }
        .page-footer {
            flex-shrink: 0;
            margin-top: auto;
            padding-top: 3mm;
            border-top: 1px solid #e2e8f0;
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-size: 8.5pt;
            color: #64748b;
        }

        /* CV Specific Typography & Elements */
        .cv-header {
            margin-bottom: 8px;
            padding-bottom: 8px;
            border-bottom: 1.5px solid #1a365d;
        }
        .cv-name {
            font-size: 20pt;
            font-weight: 700;
            letter-spacing: -0.02em;
            color: #0f172a;
            margin: 0 0 2px 0;
            text-transform: none;
        }
        .cv-title {
            font-size: 10.5pt;
            font-weight: 600;
            color: #1a365d;
            margin: 0 0 6px 0;
            letter-spacing: 0.01em;
        }
        .contact-row {
            display: flex;
            flex-wrap: wrap;
            gap: 12px;
            font-size: 8.5pt;
            color: #334155;
        }
        .contact-item {
            display: inline-flex;
            align-items: center;
            gap: 4px;
        }
        .contact-item a {
            color: #1d4ed8;
            text-decoration: none;
        }
        .contact-item a:hover {
            text-decoration: underline;
        }

        .section-title {
            font-size: 10pt;
            font-weight: 700;
            text-transform: uppercase;
            letter-spacing: 0.08em;
            color: #1a365d;
            border-bottom: 1px solid #cbd5e1;
            padding-bottom: 3px;
            margin-top: 14px;
            margin-bottom: 8px;
        }

        .entry {
            margin-bottom: 10px;
        }
        .entry-header {
            display: flex;
            justify-content: space-between;
            align-items: baseline;
            margin-bottom: 2px;
        }
        .entry-title {
            font-weight: 700;
            font-size: 10pt;
            color: #0f172a;
        }
        .entry-subtitle {
            font-weight: 600;
            font-size: 9.5pt;
            color: #334155;
            font-style: italic;
        }
        .entry-date {
            font-size: 9pt;
            font-weight: 600;
            color: #475569;
            white-space: nowrap;
        }
        .entry-location {
            font-size: 8.5pt;
            color: #64748b;
        }

        ul.cv-list {
            margin: 3px 0 6px 0;
            padding-left: 16px;
        }
        ul.cv-list li {
            margin-bottom: 3px;
            font-size: 9.2pt;
            color: #334155;
            line-height: 1.4;
        }

        .badge-award {
            display: inline-block;
            background-color: #f1f5f9;
            border-left: 3px solid #2563eb;
            padding: 2px 6px;
            font-size: 8.5pt;
            font-weight: 600;
            color: #1e3a8a;
            margin-top: 2px;
        }

        .pub-title {
            font-weight: 700;
            color: #0f172a;
            font-size: 9.5pt;
        }
        .pub-authors {
            font-size: 9pt;
            color: #334155;
        }
        .pub-venue {
            font-size: 8.5pt;
            font-style: italic;
            color: #475569;
        }

        .skills-grid {
            display: grid;
            grid-template-columns: 140px 1fr;
            row-gap: 6px;
            column-gap: 12px;
            font-size: 9pt;
        }
        .skills-label {
            font-weight: 700;
            color: #1a365d;
        }
        .skills-val {
            color: #334155;
        }

        @media print {
            *, *::before, *::after {
                box-shadow: none !important;
                text-shadow: none !important;
                -webkit-print-color-adjust: exact;
                print-color-adjust: exact;
            }
            body { padding: 0; background: none; }
            .page {
                margin: 0;
                border: none;
                height: 297mm;
                break-after: page;
                page-break-after: always;
            }
            .page:last-child { break-after: auto; page-break-after: auto; }
        }
    </style>

</head>
<body>
<div contenteditable="true">

<section class="page">
    <div class="page-content">
        <header class="cv-header">
            <h1 class="cv-name">Eduardo da Costa Batista</h1>
            <div class="cv-title">Agronomist & Researcher | Computer Vision, Remote Sensing & Agricultural Data Science</div>
            <div class="contact-row">
                <span class="contact-item">📍 Humaitá, Amazonas, Brazil</span>
                <span class="contact-item">✉️ <a href="mailto:eduardo.batista@ufam.edu.br">eduardo.batista@ufam.edu.br</a></span>
                <span class="contact-item">📞 +55 (97) 98402-3294</span>
                <span class="contact-item">🎓 <a href="https://scholar.google.com.br/citations?user=D_aGM8UAAAAJ&hl=pt-BR" target="_blank">Google Scholar</a></span>
                <span class="contact-item">🌐 <a href="https://eduardobatista26.github.io/" target="_blank">Academic Portfolio</a></span>
            </div>
        </header>

        <section>
            <div class="section-title">Research Profile</div>
            <p style="font-size: 9.3pt; color: #2d3748; margin: 0; text-align: justify; line-height: 1.42;">
                Agronomy undergraduate and certified Agricultural Technician with research experience in digital agriculture, machine learning applications for phytopathology, and Amazonian fisheries monitoring. Specialized in Python-based scientific computing, image processing (OpenCV, PyTorch), and geospatial analysis applied to tropical agricultural systems and natural resource management. Proven track record in scientific initiation projects, field data acquisition, statistical modeling, and institutional extension work across Western Amazonia.
            </p>
        </section>

        <section>
            <div class="section-title">Education</div>

            <div class="entry">
                <div class="entry-header">
                    <span class="entry-title">Federal University of Amazonas (UFAM)</span>
                    <span class="entry-date">2023 – Present</span>
                </div>
                <div class="entry-subtitle">B.Sc. in Agricultural Engineering (Engenharia Agronômica)</div>
                <div class="entry-location">Institute of Education, Agriculture and Environment (IEAA), Humaitá, AM, Brazil</div>
                <ul class="cv-list">
                    <li>Focus on precision agriculture, plant disease diagnostics, geospatial technology, and rural extension.</li>
                    <li>Active Scientific Initiation Researcher (PIBIC/UFAM) in computer vision for phytopathology and Amazonian fisheries ecology.</li>
                </ul>
            </div>

            <div class="entry">
                <div class="entry-header">
                    <span class="entry-title">Federal Institute of Amazonas (IFAM)</span>
                    <span class="entry-date">2018 – 2020</span>
                </div>
                <div class="entry-subtitle">Technical Diploma in Agriculture (Técnico em Agropecuária)</div>
                <div class="entry-location">Humaitá, AM, Brazil — Registered with CFTA</div>
                <ul class="cv-list">
                    <li><strong>Thesis / Final Defense:</strong> <em>Estudo de tempos e movimentos no levantamento topográfico</em> (Time and motion study in topographic surveying).</li>
                    <li>Practical training in agricultural surveying, soil management, crop production, and rural extension methods.</li>
                </ul>
            </div>
        </section>

        <section>
            <div class="section-title">Research and Academic Experience</div>

            <div class="entry">
                <div class="entry-header">
                    <span class="entry-title">Ichthyology and Fisheries Management Laboratory (LIOP / UFAM)</span>
                    <span class="entry-date">2023 – 2026</span>
                </div>
                <div class="entry-subtitle">Undergraduate Research Fellow & Scientific Initiation (PIBIC)</div>
                <div class="entry-location">Humaitá, Amazonas, Brazil</div>
                <ul class="cv-list">
                    <li>Conducted systematic monitoring of small-scale, artisanal fisheries landings across the Middle Madeira River basin in Southwestern Amazonia.</li>
                    <li>Organized biometric database architectures, conducted field sampling with local fishing cooperatives, and authored technical reports.</li>
                    <li>Developed digital extension strategies and web-based data dissemination pipelines to present biological indices to local stakeholders.</li>
                </ul>
            </div>

            <div class="entry">
                <div class="entry-header">
                    <span class="entry-title">Federal University of Amazonas (UFAM)</span>
                    <span class="entry-date">2024 – 2025</span>
                </div>
                <div class="entry-subtitle">Academic Teaching Assistant (Monitoria)</div>
                <div class="entry-location">IEAA, Humaitá, AM</div>
                <ul class="cv-list">
                    <li>Assisted faculty in undergraduate course delivery, laboratory preparations, and student mentoring across four core disciplines: <strong>Cell Biology</strong>, <strong>General Phytopathology</strong>, <strong>General Zoology</strong>, and <strong>Rural Sociology</strong>.</li>
                    <li>Facilitated practical laboratory sessions, guided students in microscopic analysis and disease identification techniques.</li>
                </ul>
            </div>
        </section>
    </div>

    <footer class="page-footer">
        <span>Eduardo da Costa Batista — Academic Curriculum Vitae</span>
        <span>Page 1 of 2</span>
    </footer>

</section>

<section class="page">
    <div class="page-content">
        <section>
            <div class="section-title">Selected Publications & Academic Proceedings</div>
            <p style="font-size: 8.5pt; color: #64748b; margin-top: -4px; margin-bottom: 8px; font-style: italic;">
                Note: Citations reflect registered congress papers, proceedings, and manuscript submissions. Complete bibliographic records are verified on Google Scholar.
            </p>

            <div class="entry">
                <div class="pub-title">Protótipo de algoritmo em Python para avaliação da mancha de Phoma foliar (Phoma spp.) em clones de café Robusta amazônicos</div>
                <div class="pub-authors"><strong>Batista, E. C.</strong> et al.</div>
                <div class="pub-venue">Congresso Brasileiro de Fitopatologia (Brazilian Congress of Phytopathology), 2026.</div>
                <div class="badge-award">★ Awarded Best Work / Honorable Mention in Phytopathology</div>
            </div>

            <div class="entry">
                <div class="pub-title">Monitoramento do desembarque pesqueiro artesanal na região do Médio Rio Madeira, sudoeste da Amazônia</div>
                <div class="pub-authors"><strong>Batista, E. C.</strong>, Prestes, A. G., Pinto, M. P. G., et al.</div>
                <div class="pub-venue">Congresso de Iniciação Científica da UFAM (CONIC / PIBIC), 2026.</div>
                <div class="badge-award">★ Honorable Mention in Scientific Initiation</div>
            </div>

            <div class="entry">
                <div class="pub-title">Estimativa de desembarque pesqueiro de peixes da ordem Characiformes no município de Humaitá - AM</div>
                <div class="pub-authors"><strong>Batista, E. C.</strong> et al.</div>
                <div class="pub-venue">Relatório Científico de Iniciação Científica (PIBIC/UFAM), 2024–2025.</div>
            </div>

            <div class="entry">
                <div class="pub-title">Aplicações de Geotecnologias e Sensoriamento Remoto na Análise Ambiental e Agrícola na Amazônia Occidental</div>
                <div class="pub-authors"><strong>Batista, E. C.</strong> et al.</div>
                <div class="pub-venue">Workshop de Geotecnologias e Pesquisa Aplicada, 2025.</div>
            </div>
        </section>
    </div>

    <footer class="page-footer">
        <span>Eduardo da Costa Batista — Academic Curriculum Vitae</span>
        <span>Page 2 of 2</span>
    </footer>

</section>

</div>
</body>
</html>
