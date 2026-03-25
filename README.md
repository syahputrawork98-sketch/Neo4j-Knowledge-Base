# 🕸️ Neo4j Knowledge Base: The Graph Database Specialist

> **"Relationships First: Unlocking Insights from Connected Data."**

## 📖 Apa itu Neo4j? (The What)
**Neo4j** adalah database graf (*Graph Database*) terkemuka di dunia. Jika database biasa melihat data sebagai "kotak-kotak" terpisah dalam tabel, Neo4j melihat data sebagai jaring laba-laba yang saling terhubung secara alami oleh relasi.

Dalam ekosistem *The Learning Matrix*, Neo4j mewakili paradigma **Native Graph Connectivity**: di mana hubungan antar data diperlakukan sebagai warga negara kelas satu (*First-class Citizen*), bukan sekadar kunci asing (*foreign key*) yang tersembunyi.

---

## 🎯 Mengapa Kita Menggunakan Neo4j? (The Why)
Neo4j menyelesaikan masalah yang mustahil diselesaikan secara efisien oleh database relasional:
1.  **Koneksi Tanpa Batas (Deep Relationships)**: Menelusuri relasi "teman dari temannya teman" hingga kedalaman tak terbatas dengan performa kilat.
2.  **Tanpa JOIN yang Lambat**: Menggunakan teknik *Index-Free Adjacency* yang membuat pencarian relasi tidak bergantung pada total jumlah data.
3.  **Skema Fleksibel**: Hubungan antar data bisa berubah dan berkembang secara dinamis tanpa harus merombak seluruh struktur.
4.  **Visualisasi Alami**: Data graf sangat mudah divisualisasikan untuk deteksi penipuan, rekomendasi produk, hingga pelacakan jaringan sosial.

---

## 🧭 Visi Arsitektural: Neo4j as an Intelligence Engine
Repositori ini membedah Neo4j melalui tiga lensa utama:
1. **Network Analysis**: Bagaimana mendeteksi pola lingkaran penipuan (*Fraud Detection*) atau manajemen silsilah data yang kompleks.
2. **Knowledge Graph**: Membangun representasi pengetahuan AI yang hierarkis, kontekstual, dan saling terhubung.
3. **Pathfinding**: Implementasi algoritma pencarian rute terpendek dan korelasi antar entitas yang hiper-terkoneksi.

## 🧬 Jalur Matriks: Matrix Cross-Path (The What)
Sesuai konstitusi `00-Mapping-Road`, hub ini adalah persilangan:
- **Sumbu-Y**: Semua Bahasa (Logic Core).
- **Sumbu-X**: RAK-02 (Server Runtime) ➡️ **RAK-04 (Storage Hub)**.

Di sini kita belajar **"Bahwa hubungan antar data memiliki nilai yang sama berharganya dengan data itu sendiri"**.

---

## 🏗️ Struktur 8-Rak (The Taxonomy)
1. **RAK-01: Anatomy & Landscape** (Graph Theory Foundations, Neo4j History, Property Graph Model).
2. **RAK-02: Foundation & Core Rules** (Cypher Basics: MATCH, CREATE, WHERE, Nodes & Edges).
3. **RAK-03: Evolution & Interfacing** (Advanced Cypher: APOC procedures, subqueries, list processing).
4. **RAK-04: Core Mechanics & Internals** (Store Files, Index-Free Adjacency, Page Cache).
5. **RAK-05: Ecosystem & Tooling** (Neo4j Browser, Bloom, Cypher Shell).
6. **RAK-06: The Underworld** (Causal Clustering, Raft Protocol, Transaction Logs).
7. **RAK-07: Specialization** (Graph Data Science - GDS, Bloom Visualizations, Security).
8. **RAK-08: Matrix Intersection** (The Bridge: How Neo4j powers RAK-05 Architecture Hub).

---

## 📊 Status Proyek
Detail status per Rak dapat dilihat di [status.md](./status.md).

> [!NOTE]
> Proyek ini mengikuti standar dokumentasi **Gold Standard PPM V4**.

- `README.md` adalah pendahuluan ini.
- `docs/` berisi dokumentasi pendukung (pemetaan, aturan, referensi).
- `RAK-xx/` berisi semua rak utama.

## Dokumentasi
- [docs/root-governance.md](./docs/root-governance.md)