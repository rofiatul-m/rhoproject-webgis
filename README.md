# 🗺️ RHO-PROJECT: WebGIS for Shelter Coverage and Evacuation Route Elevation Analysis

## 🎯 Overview

**RHO-PROJECT** adalah aplikasi WebGIS interaktif yang dikembangkan untuk meningkatkan kesiapsiagaan bencana dan mengoptimalkan proses evakuasi di wilayah rawan bencana di Indonesia. Proyek ini memberikan solusi analitik geospasial mendalam yang berfokus pada aksesibilitas shelter dan keselamatan rute.

## ✨ Fitur Utama (Key Features)

| Fitur | Deskripsi |
| :--- | :--- |
| **Isoline Coverage Analysis** | Menghitung dan memvisualisasikan area jangkauan (isochrone/isodistance) dari shelter evakuasi berdasarkan waktu/jarak tempuh dan berbagai moda transportasi (**walk, car, motorcycle**). Membantu mengidentifikasi area yang dapat menjangkau **berapa shelter** dalam waktu tertentu. |
| **Optimal Route & Elevation Profiling** | Menentukan rute evakuasi terpendek/tercepat ke shelter tujuan. Analisis ini menyertakan grafik **profil elevasi** yang detail, menampilkan nilai *Loss* (penurunan) dan *Gain* (peningkatan) ketinggian untuk memitigasi risiko topografi. |

## 🔗 Akses Cepat (Live Demo)

[![Lihat Demo Langsung](https://img.shields.io/badge/Akses%20Peta%20Langsung-RHO--PROJECT-blue?style=for-the-badge&logo=maplibre)](https://rofiatul-m.github.io/rhoproject-webgis/map.html)

## 🛠️ Stack & Dependencies

Proyek ini dibangun menggunakan *stack* pemetaan dan analisis geospasial modern:

| Komponen | Teknologi/Library | Peran |
| :--- | :--- | :--- |
| **Mapping Engine** | `MapLibre GL JS` | *Rendering* peta vektor yang cepat dan tampilan data geospasial. |
| **Core Analysis** | `Geoapify Isoline & Routes API` | Backend untuk perhitungan isoline dan *routing* kompleks (termasuk data elevasi). |
| **Data Visualization** | `Chart.js` | Digunakan untuk visualisasi grafik profil elevasi rute secara dinamis. |
| **Processing** | `Turf.js` | Operasi dan manipulasi data GeoJSON di sisi klien (*client-side*). |
| **Frontend** | HTML, CSS, JavaScript | Struktur antarmuka dan logika aplikasi. |
| **Data Processing** | QGIS | Digunakan untuk pengolahan data awal (misalnya, perhitungan kerawanan bencana). |
