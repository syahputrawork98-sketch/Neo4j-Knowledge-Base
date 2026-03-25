# 🕸️ Neo4j Knowledge Base: The Graph Database Specialist

> **"Relationships First: Unlocking Insights from Connected Data."**

Repositori ini adalah **Blueprint Utama (Rak 04)** dalam ekosistem *The Learning Matrix*. Fokus utamanya adalah mengeksplorasi penelusuran relasi asosiatif ekstrem menggunakan Neo4j dan Cypher Query Language.

---

## 🎯 Visi Arsitektural: Relationship-Centric (The Why)
Neo4j menghancurkan batasan `JOIN` tradisional pada data yang saling terhubung secara kompleks:
1.  **Native Graph Store**: Menyimpan data sebagai *Nodes* dan *Relationships* tanpa tabel perantara.
2.  **Index-Free Adjacency**: Menelusuri jutaan koneksi dalam waktu konstan O(1) di level memori.
3.  **Cypher Power**: Bahasa kueri deklaratif yang intuitif untuk mendeskripsikan pola graf.

Visi repositori ini adalah membedah **Neo4j as an Intelligence Engine**:
1. **Network Analysis**: Bagaimana mendeteksi pola lingkaran penipuan (*Fraud Detection*) atau jejaring sosial.
2. **Knowledge Graph**: Membangun representasi pengetahuan yang hierarkis dan terhubung.
3. **Pathfinding**: Implementasi algoritma pencarian rute terpendek dan korelasi antar entitas.

## 🧬 Jalur Matriks: Matrix Cross-Path (The What)
Sesuai konstitusi `00-Mapping-Road`, hub ini adalah persilangan:
- **Sumbu-Y**: Semua Bahasa (Logic Core).
- **Sumbu-X**: RAK-02 (Server Runtime) ➡️ **RAK-04 (Storage Hub)**.

Di sini kita belajar **"Bahwa hubungan antar data sama pentingnya dengan data itu sendiri"**.

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