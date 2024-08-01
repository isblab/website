---
title: Software and Resources
layout: default
group: Software
---
<h1>ISB Lab Software and Resources</h1>
<div class="container-fluid">

<h2>Software</h2>

<table>
    <thead>
        <tr>
            <th style="text-align: center;">Name</th>
            <th style="text-align: center;">Graphical abstract</th>
            <th style="text-align: center;">Description</th>
            <th style="text-align: center;">Link</th>
        </tr>
    </thead>
    <tbody>
        <!-- IMP-related software section -->
        <tr class="heading-row">
            <td colspan="4" style="text-align: center; font-weight: bold; background-color: #f0f0f0;">IMP-related software</td>
        </tr>
        <tr class="row-light">
            <td>NestOR</td>
            <td><img src="static/img/software/nestor.png" alt="NestOR graphical abstract" style="max-width: 100px; height: auto;"></td>
            <td>Nested sampling-based optimization of representation for integrative structural modeling.</td>
            <td><a href="https://github.com/isblab/nestor" class="link">GitHub</a></td>
        </tr>
        <tr class="row-dark">
            <td>PrISM</td>
            <td><img src="static/img/software/prism.png" alt="PrISM graphical abstract" style="max-width: 100px; height: auto;"></td>
            <td>Package to annotate high- and low-precision regions in integrative structure models. Now used by wwPDB to validate integrative models!</td>
            <td><a href="https://github.com/isblab/prism" class="link">GitHub</a></td>
        </tr>
        <tr class="row-light">
            <td>StOP</td>
            <td><img src="static/img/software/stop.png" alt="StOP graphical abstract" style="max-width: 100px; height: auto;"></td>
            <td>Stochastic Optimization of Parameters (StOP) automates the tuning of MCMC parameters for stochastic sampling in IMP.<br>
                - Check this <a href="https://github.com/isblab/stop/blob/main/docs/tutorial_basic.md" class="link">tutorial</a> for optimizing Monte Carlo move sizes/restraint weights.<br>
                - And this <a href="https://github.com/isblab/stop/blob/main/docs/tutorial_replica.md" class="link">tutorial</a> for optimizing replica exchange temperatures.
            </td>
            <td><a href="https://github.com/isblab/stop" class="link">GitHub</a></td>
        </tr>
        <tr class="row-dark">
            <td>Sampcon</td>
            <td><img src="static/img/software/sampcon.png" alt="Sampcon graphical abstract" style="max-width: 100px; height: auto;"></td>
            <td>Pipeline for analyzing integrative models after MCMC sampling. Includes tests for assessing sampling exhaustiveness, clustering models, and calculating precision.</td>
            <td><a href="https://github.com/salilab/imp-sampcon" class="link">GitHub</a></td>
        </tr>
        <!-- Protein-protein docking-related software section -->
        <tr class="heading-row">
            <td colspan="4" style="text-align: center; font-weight: bold; background-color: #f0f0f0;">Protein-protein docking-related software</td>
        </tr>
        <tr class="row-light">
            <td>Scoring functions</td>
            <td></td>
            <td>PISA (atomic), PIE (residue), and C3 (combination) scoring functions for ranking models of protein-protein complexes produced by docking programs.</td>
            <td><a href="https://github.com/isblab/dockingScripts/tree/main/capriScripts/potentials" class="link">GitHub</a></td>
        </tr>
        <tr class="row-dark">
            <td>Other utilities</td>
            <td></td>
            <td>Contains scripts for calculating interface RMSD, and other utilities for modifying PDBs, adding chain names, running Modeller etc.</td>
            <td><a href="https://github.com/isblab/dockingScripts" class="link">GitHub</a></td>
        </tr>
    </tbody>
</table>

<style>
    /* Add styles for alternating row colors */
    .row-light {
        background-color: #CBC3E3; /* Light purple */
    }
    .row-dark {
        background-color: #ffffff; /* White */
    }
    .heading-row {
        background-color: #f0f0f0; /* Light grey for headings */
    }
    .link {
        color: #0066cc; /* Link color */
        text-decoration: none; /* Remove underline from links */
    }
    .logo {
        vertical-align: middle;
    }
</style>



<br><br>

<h2>Courses and Workshops</h2>

<h3>Integrative Modeling Tutorials and Workshops</h3>
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

<h3>Graduate Courses at NCBS</h3>
<ul>
    <li>
        <a href="http://moodle.ncbs.res.in/course/view.php?id=107" class="link">Statistical Inference in Biology</a> (internal link) co-taught with Dr Shaon Chakrabarti at NCBS.
    </li>
    <li>
        Crash course in <a href="https://github.com/isblab/pycrash" class="link">Python</a> taught during the Statistical Inference course.
    </li>
</ul>
