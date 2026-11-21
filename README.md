# RDU Readers — Literary Passport 2026

Interactive, printable literary passport booklet created for the **Raleigh–Durham Readers Book Club**'s *"Around the World in Books"* 2026 reading series.

🔗 **Create Your Passport:** `https://<your-github-username>.github.io/<repo-name>/`

---

## How to Use (For Club Members)

1. **Personalize Your Cover:** Type your name into the input box at the top to update the front cover and member information page in real time.
2. **Customize Your Stamps:** Missed a meetup? Click any month pill at the top (or click a stamp directly on Pages 3–4) to swap it for an *Awaiting Entry* slot. Your Reading Log and country progress bar on Page 5 update automatically.
3. **Rate Your Reads (Optional):** Click the stars next to each book on Page 5. Your highest-rated title automatically fills in as your **2026 Favorite** on Page 2 (or leave unrated to leave a blank line for handwriting).
4. **Download Your PDF:**
   - **Print Booklet (A4 Fold):** Exports 3 landscape sheets arranged for double-sided booklet folding.
   - **Single Pages (A5):** Exports 6 sequential pages for digital viewing or single-page printing.

---

## Printing & Assembly

1. Open the **Print Booklet (A4 Fold)** PDF.
2. Print **double-sided (duplex)** on A4 or US Letter cardstock:
   - **Binding / Flip:** **Flip on Short Edge** *(important so inside pages aren't upside down)*
   - **Scale:** **100% / Actual Size**
3. Stack the 3 printed sheets in order, fold down the center tick marks, and staple along the spine.

---

## 2026 Reading Itinerary

| Month | Country | Book | Author |
| :--- | :--- | :--- | :--- |
| **Jan** | 🇬🇧 United Kingdom | *The Midnight Library* & *Ottolenghi Simple* | Matt Haig / Yotam Ottolenghi |
| **Feb** | 🇺🇸 United States | *The Correspondent* | Virginia Evans |
| **May** | 🇯🇵 Japan | *The Healing Hippo of Hinode Park* | Michiko Aoyama |
| **Jun** | 🇮🇹 Italy | *My Brilliant Friend* | Elena Ferrante |
| **Jul** | 🇹🇷 Turkey | *10 Minutes 38 Seconds in This Strange World* | Elif Shafak |
| **Aug** | 🇰🇷 South Korea | *Pachinko* | Min Jin Lee |
| **Sep** | 🇸🇪 Sweden | *A Man Called Ove* | Fredrik Backman |
| **Oct** | 🇲🇽 Mexico | *Mexican Gothic* | Silvia Moreno-Garcia |
| **Nov** | 🇮🇳 India | *Heart Lamp* | Banu Mushtaq |
| **Dec** | 🇮🇪 Ireland | *This Is Happiness* | Niall Williams |

---

## Maintainer Notes

- **Zero-Build Single File:** Everything (React 18, Babel, Google Fonts, `html2canvas`, and `jsPDF`) is loaded via CDN inside `index.html`.
- **Updating for Future Years:** Edit the `STAMPS_DATA` array near the top of `index.html` to update months, country codes, colors, icons, titles, and authors[span_1](start_span)[span_1](end_span).
- # RDU-readers-passport
RDU bookclub passport 2026, journey through the world
