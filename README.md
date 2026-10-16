# Jur_list: IIM Journal Research Directory (2026 Edition)

An interactive, responsive portal powered by **TanStack Table** to search, filter, and verify academic journals recognized and published across **Indian Institutes of Management (IIMs)**, including **ABDC, Scopus, FT50, UTD 24, Web of Science, and UGC-CARE**.

🌐 **Live Website Link:** [https://milliondreamsblog.github.io/Jur_list/](https://milliondreamsblog.github.io/Jur_list/)

---

## 🚀 Key Features

* **Instant Search:** Type any keyword (e.g., `finance`, `accounting`, `marketing`, `vikalpa`, `iim`, `operations`) to immediately filter journals in real time.
* **Category Filters:** Quick chips for **Finance**, **Accounting**, **IIM Published**, **FT50**, **UTD 24**, **ABDC A\***, **ABDC A**, and **Scopus Q1**.
* **TanStack Table Engine:** High-performance sorting, customizable pagination (10, 15, 25, 50, 100 rows), and multi-column filtering.
* **Export to CSV:** Download filtered journal search results with one click.
* **Direct Official Links:** One-click links to official 2026 publisher and submission portals.

---

## 📚 Categorization Frameworks Included

1. **ABDC Quality List (Australian Business Deans Council):** A*, A, B, C
2. **Financial Times Top 50 (FT50):** Elite journals calculating global B-School research ranks
3. **UT Dallas Top 24 (UTD 24):** World-class research standards
4. **Scopus (Elsevier):** Q1, Q2, Q3, Q4 quartiles with CiteScore and SJR
5. **Web of Science (Clarivate):** SSCI, SCIE, and ESCI indexing
6. **UGC-CARE (India):** Group I & Group II regulatory categories

---

## 🏛️ Flagship Journals Published Directly by IIMs

| Journal | Publishing IIM | Publisher | ABDC | Scopus | WoS |
| :--- | :--- | :--- | :---: | :---: | :---: |
| **Vikalpa** | IIM Ahmedabad | SAGE | **B** | Scopus (Q3) | ESCI |
| **IIMB Management Review (IMR)** | IIM Bangalore | Elsevier | **B** | Scopus (Q2) | ESCI |
| **DECISION** | IIM Calcutta | Springer | **B** | Scopus | ESCI |
| **IIM Kozhikode Society & Management Review** | IIM Kozhikode | SAGE | **C** | Scopus (Q2) | ESCI |
| **Metamorphosis** | IIM Lucknow | SAGE | — | — | UGC Group I |
| **IIMS Journal of Management Science** | IIM Shillong | Prints | — | — | UGC Group I |
| **IIM Ranchi Journal of Management Studies** | IIM Ranchi | Emerald | — | — | UGC Group I |
| **Indore Management Journal** | IIM Indore | IIM Indore | — | — | Institutional |
| **Emerging Economies Cases Journal** | IIM Rohtak | SAGE | — | — | UGC Group I |

---

## 📂 Project Structure

```text
├── index.html                           # Main TanStack Table web application
├── data/
│   └── journals.js                      # Curated 2026 journals dataset
├── FT50_Journals_List.csv               # Complete 50 Financial Times journals list
├── UTD24_Journals_List.csv              # Complete 24 UT Dallas premier journals list
├── IIM_Flagship_Journals.csv            # Directory of journals published by IIMs
├── IIM_Journal_Classification_Guide.md  # Comprehensive research handbook
└── .github/workflows/deploy.yml         # GitHub Actions workflow for automatic Pages deployment
```

---

## 📄 License
MIT License. Created for academic scholars, researchers, and doctoral candidates.
