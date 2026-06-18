<div align="center">

<img src="https://raw.githubusercontent.com/Lazizah-Org/.github/main/profile/assets/banner.png" alt="Lazizah" width="100%" />

# Lazizah Cakes

**Point-of-sale & operations platform for a modern bakery.**

[![API Build](https://img.shields.io/github/actions/workflow/status/Lazizah-Org/lazizah_api/ci.yml?branch=main&label=API%20build&logo=github)](https://github.com/Lazizah-Org/lazizah_api/actions)
[![App Build](https://img.shields.io/github/actions/workflow/status/Lazizah-Org/lazizah_app/ci.yml?branch=main&label=App%20build&logo=github)](https://github.com/Lazizah-Org/lazizah_app/actions)
[![Release](https://img.shields.io/github/v/release/Lazizah-Org/lazizah_api?include_prereleases&label=release)](https://github.com/Lazizah-Org/lazizah_api/releases)
[![License](https://img.shields.io/badge/license-Proprietary-blue)](#license)
[![Laravel](https://img.shields.io/badge/Laravel-11-FF2D20?logo=laravel&logoColor=white)](https://laravel.com)
[![PHP](https://img.shields.io/badge/PHP-8.2+-777BB4?logo=php&logoColor=white)](https://php.net)

</div>

---

## Overview

**Lazizah** is the internal POS and back-office system for **Lazizah Cakes** — replacing manual bookkeeping with a fast, role-aware platform for sales, orders, inventory, recipe costing, and cash flow.

It runs as two repositories: a **headless REST API** and a **server-rendered frontend** that consumes it over HTTP.

## Repositories

| Repo | Stack | Description |
|------|-------|-------------|
|  [**lazizah_api**](https://github.com/Lazizah-Org/lazizah_api) | Laravel 11 · Sanctum · MySQL | Headless REST API — auth & roles, sales, orders, inventory, recipes/HPP, expenses, reporting. |
|  [**lazizah_app**](https://github.com/Lazizah-Org/lazizah_app) | Laravel 11 · Blade · PWA | Frontend — POS UI, dashboard, analytics, inventory & order management, offline-capable PWA. |

## Features

- 🛒 **Point of Sale** — fast checkout with printable receipts
- 📦 **Inventory** — stock tracking with low-stock alerts and pre-flight checks
- 🧾 **Orders** — order lifecycle with status timeline and transition guards
- 🍰 **Recipes & Costing** — HPP (cost-of-production) and margin calculation
- 💰 **Cash Book & Expenses** — multi-line expenses and cash-flow integrity
- 📊 **Reporting** — analytics dashboard and PDF report export
- 👥 **Roles & Access** — 5-level RBAC enforced end to end
- 📱 **PWA** — installable, offline-capable frontend


## Status

> 🚧 **Alpha (v0.1.0-alpha)** — Core POS, inventory, recipes, orders, and reporting are live. Currently hardening for production: RBAC, audit trails, and error feedback.

## License

Proprietary — internal business tooling for **Lazizah Cakes**. All rights reserved.

---

<div align="center">
<sub>Made with by the Lazizah team</sub>
</div>
