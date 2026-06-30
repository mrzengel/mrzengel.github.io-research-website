---
layout: page
permalink: /research/
title: research
nav: true
nav_order: 1
---

<div class="research">

<h2>Current Research</h2>

<div class="re-card re-card--current">
  <span class="re-date">Aug 2025 – Present</span>
  <h3 class="re-title">Ultrafast Surface Dynamics in Quantum Materials</h3>
  <div class="re-affil">Gedik Lab &middot; Department of Physics, MIT &middot; Cambridge, MA</div>
  <p class="re-desc">
    I study ultrafast surface dynamics of quantum materials using Time- and Angle-Resolved Photoemission Spectroscopy (tr-ARPES) and Momentum Microscopy. These techniques use ultrashort laser pulses to drive materials out of equilibrium and probe the resulting changes in electronic structure on femtosecond timescales, revealing non-equilibrium phenomena inaccessible to static measurements.
  </p>
</div>

<h2>Past Research</h2>

<div class="re-card">
  <span class="re-date">May 2022 – May 2025</span>
  <h3 class="re-title">First-Principles Study of Heusler Alloys</h3>
  <div class="re-affil">Hauser Lab &middot; Department of Physics, University of Alabama &middot; Tuscaloosa, AL</div>
  <p class="re-desc">
    Used Density Functional Theory (Quantum Espresso) on HPC systems to predict the atomic ordering, magnetic properties, and electronic structure of ternary Heusler alloys. Compared theoretical predictions against experimentally grown materials characterized by XRD and XRR. This work resulted in four peer-reviewed publications.
  </p>
</div>

<div class="re-card">
  <span class="re-date">Jun 2024 – Aug 2024</span>
  <h3 class="re-title">JupyterLab Extension for Zenodo</h3>
  <div class="re-affil">CERN IT Department (IT-GOV-ENG) &middot; Geneva, Switzerland &middot; University of Michigan REU</div>
  <p class="re-desc">
    Developed a JupyterLab extension providing seamless integration between Zenodo (a CERN open-data repository) and analysis facilities, enabling researchers to access and share datasets directly from within a notebook environment. Presented results at the Astronomical Data Analysis Software and Systems (ADASS) conference.
  </p>
</div>

<div class="re-card">
  <span class="re-date">May 2023 – Aug 2023</span>
  <h3 class="re-title">THz Emission Generation via Photocurrent Injection</h3>
  <div class="re-affil">Justus Liebig University &middot; Gießen, Germany &middot; DAAD RISE</div>
  <p class="re-desc">
    Designed and constructed an optical setup generating terahertz radiation via photocurrent injection in semiconductors using a two-color excitation scheme. Analyzed the mobility and conductivity of MOCVD-grown monolayers using THz time-domain spectroscopy.
  </p>
</div>

<div class="re-card">
  <span class="re-date">Sep 2021 – Jul 2022</span>
  <h3 class="re-title">Machine Learning for Jet Classification at the LHC</h3>
  <div class="re-affil">Department of Physics, University of Alabama &middot; Tuscaloosa, AL</div>
  <p class="re-desc">
    Worked with Dr. Sergei Gleyzer to evaluate the performance of convolutional neural networks for classifying raw jet data from the Compact Muon Solenoid (CMS) detector at the Large Hadron Collider. Investigated data augmentation techniques to improve convergence of classification models.
  </p>
</div>

<div class="re-card">
  <span class="re-date">Jun 2019 – Aug 2021</span>
  <h3 class="re-title">Machine Learning for Density Functional Theory</h3>
  <div class="re-affil">Department of Physics, Tulane University &middot; New Orleans, LA</div>
  <p class="re-desc">
    Worked with Dr. Jianwei Sun on applying machine learning to accelerate Density Functional Theory calculations within the SCAN meta-GGA framework. Developed neural networks for property prediction and wrote automation scripts exploiting point-group symmetry to reduce redundancy in molecular input grids.
  </p>
</div>

</div>

<style>
  .research h2 {
    margin-top: 2rem;
    margin-bottom: 1rem;
  }

  .re-card {
    position: relative;
    padding: 1rem 1.25rem 1rem 1.25rem;
    margin-bottom: 1rem;
    border: 1px solid var(--global-divider-color, #e0e0e0);
    border-left: 3px solid var(--global-divider-color, #ccc);
    border-radius: 4px;
    background-color: var(--global-card-bg-color, transparent);
  }

  .re-card--current {
    border-left-color: var(--global-theme-color, #2196f3);
  }

  .re-date {
    position: absolute;
    top: 1rem;
    right: 1.25rem;
    font-size: 0.8rem;
    color: var(--global-text-color-light, #555);
    border: 1px solid var(--global-divider-color, #ddd);
    border-radius: 3px;
    padding: 0.1rem 0.45rem;
    white-space: nowrap;
  }

  .re-title {
    font-size: 1rem;
    font-weight: 600;
    margin: 0 0 0.25rem;
    padding-right: 11rem;
    line-height: 1.35;
  }

  .re-affil {
    font-size: 0.875rem;
    font-style: italic;
    color: var(--global-text-color-light, #555);
    margin-bottom: 0.6rem;
  }

  .re-desc {
    font-size: 0.9rem;
    margin: 0;
  }

  @media (max-width: 600px) {
    .re-date {
      position: static;
      display: inline-block;
      margin-bottom: 0.4rem;
    }
    .re-title {
      padding-right: 0;
    }
  }
</style>
