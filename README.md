<div align="center">

# Integrated Web & Database Development Portfolio

A consolidated academic project showing the evolution of multiple web-development and relational-database exercises in a single repository.

`HTML5` · `CSS3` · `JavaScript` · `Bootstrap 5` · `Vue.js 3` · `SQL` · `MySQL`

</div>

## Overview

This repository now consolidates the main **Projeto Integrador II** artifacts that were previously spread across several repositories.

The current root contains a Bootstrap-based **Cafeteria Aroma** frontend prototype. Earlier units are preserved under `history/` so the repository also documents the evolution from a Vue.js task manager to relational database exercises.

## Repository Map

```text
ProjetoIntegradorII/
├── index.html                    # Current Cafeteria Aroma landing page
├── css/style.css
├── js/script.js
├── assets/
└── history/
    ├── unit-02/                  # Vue.js task-management prototype
    │   ├── index.html
    │   ├── style.css
    │   └── app.js
    ├── unit-03/                  # Bookstore relational model
    │   └── livraria.sql
    └── unit-03-evaluation/       # University-library database exercise
        └── biblioteca.sql
```

## Current Frontend — Cafeteria Aroma

The root `index.html` presents a responsive cafeteria landing page using Bootstrap 5, custom CSS, Google Fonts and local product images.

### Current Features

- responsive Bootstrap layout;
- product cards for coffee, snacks and desserts;
- local image assets;
- call-to-action buttons;
- custom stylesheet and JavaScript hook.

### Known Limitation

The landing page currently links to `fazer_pedido.html`, but that page is **not versioned in the repository**. The current root should therefore be considered a frontend prototype rather than a complete ordering application.

## Consolidated History

### Unit 02 — Vue.js Task Manager

A small reactive task-management application built with Vue.js 3 via CDN. It supports task creation, priority selection and removal, with a responsive CSS layout.

Location: `history/unit-02/`

### Unit 03 — Bookstore Database

A relational modeling exercise containing `produtos` and `pedidos`, sample records, a foreign-key relationship and basic queries.

Location: `history/unit-03/`

### Unit 03 Evaluation — University Library Database

A MySQL-oriented exercise modeling users, books, loans, reservations and fines. It includes relationships, sample data and a trigger that updates book availability when a return is registered.

Location: `history/unit-03-evaluation/`

## Running the Web Prototypes

No package manager is required for the current static frontend.

```bash
git clone https://github.com/Dyogo199/ProjetoIntegradorII.git
cd ProjetoIntegradorII
```

Open `index.html` in a browser.

For the Unit 02 Vue.js snapshot, open:

```text
history/unit-02/index.html
```

Internet access is required there because Vue.js is loaded from a CDN.

## Running the SQL Exercises

The SQL snapshots are closest to MySQL/MariaDB syntax. Import the desired script into a compatible database environment:

```text
history/unit-03/livraria.sql
history/unit-03-evaluation/biblioteca.sql
```

## Engineering Roadmap

1. implement or remove the missing `fazer_pedido.html` navigation target;
2. remove duplicate/unused root styles if confirmed unnecessary;
3. add screenshots of the current and historical prototypes;
4. add lightweight frontend validation tests;
5. add SQL schema diagrams for the database exercises;
6. add a GitHub Pages deployment for the static frontend;
7. standardize file naming and language across the project;
8. preserve future academic milestones in `history/` instead of separate repositories.

## Consolidation Policy

The `history/` directory is intentionally used to preserve meaningful earlier deliverables. This keeps the portfolio readable while retaining the technical evolution of the coursework in one canonical repository.

## Author

**Dyogo Mondego**  
Software Engineer · MSc Student in Computer Science @ IME-USP
