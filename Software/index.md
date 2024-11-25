---
title: Software and Resources
layout: default
group: Software
---
<h2>ISB Lab Software and Resources</h2>
<div class="container-fluid">

Check out software developed by our group and other open-source freebies at [ISB Lab GitHub](https://github.com/isblab). <br>

<table>
    <thead>
        <tr>
            <th style="text-align: center; width: 20%;">Name</th>
            <th style="text-align: center; width: 30%;"></th>
            <th style="text-align: center; width: 40%;">Description</th>
            <th style="text-align: center; width: 10%;">Link</th>
        </tr>
    </thead>
    <tbody>
        <!-- Integrative modeling software section -->
        <tr class="heading-row">
            <td colspan="4" style="text-align: center; font-weight: bold; background-color: #cbc3e3; padding: 15px;">Integrative modeling software</td>
        </tr>
        <tr class="row-dark">
            <td style="text-align: center;">Wall-EASAL</td>
            <td style="text-align: center;"><img src="/static/img/software/easal.png" class="logo"></td>
            <td style="text-align: center;">Integrative docking with crosslinks.</td>
            <td style="text-align: center;">
            <a href="https://github.com/isblab/Integrative_docking_benchmark" class="link">GitHub</a><br>
            <a href="https://bitbucket.org/geoplexity/easal-dev/src/Crosslink" class="link"> EASAL Software</a>
            </td>
        </tr>
        <tr class="row-light">
            <td style="text-align: center;">NestOR</td>
            <td style="text-align: center;"><img src="/static/img/software/nestor.png" class="logo"></td>
            <td style="text-align: center;">Nested sampling-based optimization of representation for integrative structural modeling.</td>
            <td style="text-align: center;"><a href="https://github.com/isblab/nestor" class="link">GitHub</a></td>
        </tr>
        <tr class="row-dark">
            <td style="text-align: center;">PrISM</td>
            <td style="text-align: center;"><img src="/static/img/software/prism.png" class="logo"></td>
            <td style="text-align: center;">Package to annotate high- and low-precision regions in integrative structure models. Now used by wwPDB to validate integrative models!</td>
            <td style="text-align: center;"><a href="https://github.com/isblab/prism" class="link">GitHub</a></td>
        </tr>
        <tr class="row-light">
            <td style="text-align: center;">StOP</td>
            <td style="text-align: center;"><img src="/static/img/software/stop.png" class="logo"></td>
            <td style="text-align: center;">Stochastic Optimization of Parameters (StOP) automates the tuning of MCMC parameters for stochastic sampling in IMP.<br>
                - Check this <a href="https://github.com/isblab/stop/blob/main/docs/tutorial_basic.md" class="link">tutorial</a> for optimizing Monte Carlo move sizes/restraint weights.<br>
                - And this <a href="https://github.com/isblab/stop/blob/main/docs/tutorial_replica.md" class="link">tutorial</a> for optimizing replica exchange temperatures.
            </td>
            <td style="text-align: center;"><a href="https://github.com/isblab/stop" class="link">GitHub</a></td>
        </tr>
        <tr class="row-dark">
            <td style="text-align: center;">Sampcon</td>
            <td style="text-align: center;"><img src="/static/img/software/sampcon.png" class="logo"></td>
            <td style="text-align: center;">Pipeline for analyzing integrative models after MCMC sampling. Includes tests for assessing sampling exhaustiveness, clustering models, and calculating precision.</td>
            <td style="text-align: center;"><a href="https://github.com/salilab/imp-sampcon" class="link">GitHub</a></td>
        </tr>
        <tr class="row-light">
            <td style="text-align: center;">Scoring functions for protein-protein docking and other utilities for parsing PDBs</td>
            <td style="text-align: center;"><img src="/static/img/software/ppd.png" class="logo"></td>
            <td style="text-align: center;">PISA (atomic), PIE (residue), and C3 (combination) scoring functions for ranking models. Interface RMSD calculation, utilities for modifying PDBs, adding chain names, and running Modeller.</td>
            <td style="text-align: center;"><a href="https://github.com/isblab/dockingScripts/tree/main/capriScripts/potentials" class="link">GitHub</a></td>
        </tr>
        <!-- Database -->
        <tr class="heading-row">
            <td colspan="4" style="text-align: center; font-weight: bold; background-color: #cbc3e3; padding: 15px;">Intrinsically disordered regions (IDR)-related software</td>
        </tr>
        <tr class="row-light">
            <td style="text-align: center;">StrIDR</td>
            <td style="text-align: center;"><img src="/static/img/software/stridr.png" class="logo"></td>
            <td style="text-align: center;">StrIDR is a database of IDRs, confirmed via experimental or homology-based evidence, that are resolved in experimentally determined structures.</td>
            <td style="text-align: center;">
                <a href="https://github.com/isblab/stridr" class="link">GitHub</a><br>
                <a href="https://isblab.ncbs.res.in/stridr" class="link">Database</a>
            </td>
        </tr>
    </tbody>
</table>

<style>
    /* Add styles for alternating row colors */
    .row-light {
        background-color: #f0f0f0; /* Light grey */
    }
    .row-dark {
        background-color: #ffffff; /* White */
    }
    .heading-row {
        background-color: #cbc3e3; /* Light purple for headings */
    }
    .link {
        color: #0066cc; 
    }
    .logo {
        max-width: 250px;
        height: auto;
        vertical-align: middle;
    }
    table {
        width: 100%; 
        border-collapse: collapse; 
    }
    th, td {
        padding: 12px; 
        border: 1px solid #ddd;
    }
    th {
        background-color: #ffffff;
    }
    /* Bold text in the Name column */
    td:first-child {
        font-weight: bold;
    }
</style>

<br><br>

<h3>Courses and Workshops</h3><br>

<h4>Integrative Modeling Tutorials and Workshops</h4>
<ul>
    <li>
        IMP Tutorial at <a href="https://meetings.embo.org/event/24-cryo-em" class="link">EMBOCEM3DIP</a> IISc Bangalore 2024. 
        <a href="https://github.com/isblab/IMP_Tutorial" class="link">GitHub</a> | 
        <a href="https://drive.google.com/drive/folders/13dUNwgPMZE0mAeyGEdUwgnGz5ybfxs1Z" class="link">Talks</a>
    </li>
    <li>
        IMP Tutorial at <a href="https://sites.google.com/acads.iiserpune.ac.in/masfe/home" class="link">MASFE</a> IISER Pune 2023. 
        <a href="https://github.com/isblab/IMP_Tutorial/tree/masfe2023" class="link">GitHub</a> | 
        <a href="https://drive.google.com/drive/folders/188BHx67a8Wq53nDTanM-vWwX3X9F_OS5" class="link">Talks</a>
    </li>
    <li>
        <a href="https://integrativemodeling.org/talks.html" class="link">IMP Workshops</a>
    </li>
</ul>

<h4>Graduate Courses at NCBS</h4>
<ul>
    <li>
        <a href="https://moodle.ncbs.res.in/enrol/index.php?id=165" class="link">Statistical Inference in Biology</a> (internal link) co-taught with Dr Shaon Chakrabarti at NCBS.
    </li>
    <li>
        Crash course in <a href="https://github.com/isblab/pycrash" class="link">Python</a> taught during the Statistical Inference course.
    </li>
</ul>

