# SWEN90009_2022_CA_Wombat

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#introduction">Introduction</a>
    </li>
    <li>
      <a href="#folder structure">Folder Structure</a>
    </li>
    <li>
        <a href="#changelog">Changelog</a>
    </li>
  </ol>
</details>
<br />

<!-- Introduction -->

## Introduction

The Australian Clinical Dosimetry Service (ACDS) is an independent dosimetry auditing program, providing quality assurance for radiation oncology providers and patients ([Australian Clinical Dosimetry Service | ARPANSA](https://www.arpansa.gov.au/our-services/testing-and-calibration/calibration/australian-clinical-dosimetry-service)). ACDS works with the government to find the intensity of radiation equipment across Australia and New Zealand. It conducts dosimetry audits at radiotherapy clinics across Australia and New Zealand to find this data. These audits are performed with specific oncological equipment with factors used in the dose calculations. The factors are updated on 2-year cycles including the information for multi machines used in the dosimetry processes.

Within the current system, information is kept in an Excel spreadsheet. The data in the Excel spreadsheet is updated every 6 months manually by employees of ACDS. Each time it is updated, a copy is created to be stored as a record of the previous version.

In this project, the students will design a solution to replace the Excel spreadsheets. The new solution will provide a graphical and performance upgrade through a custom frontend which will be backed by a database.

<br/>

## Folder Structure

    ├── data samples    # Necessary input documents to simulate/demonstrate the prototype
    ├── docs   # Contains requirement elicitation documentation
        ├── requirements    # Requirement Elicitation documentation
    ├── prototypes
        ├── low fidelity    # Low fidelity files (screens, mockups, etc.)
        ├── high fidelity   # high fidelity files (screens, source files, etc.)
    ├── tests   # User/System test
    ├── ui      # Images created for the prototypes (icons, fonts, backgrounds, etc.)
    └── README.md

## Changelog:

**Sprint 1**:

- Project Overview
- Requirements Elicitation

## Notes

- There is currently a `.gitignore` in a few directories to support empty directories being pushed to GitHub. These `.gitignore` files will be removed as information is pushed to each directory in future sprints.
