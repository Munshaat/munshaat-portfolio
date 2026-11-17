# Munshaat Atiq Nuzaba — portfolio website

A dependency-free static website (HTML/CSS/JavaScript) for GitHub Pages.

## Deploy to the existing repository

1. Download and unzip `munshaat-portfolio-github-pages.zip`.
2. Back up the existing repository. Copy the **contents** of the extracted `munshaat-portfolio-site/` folder (not the folder itself) to the root of `Munshaat/munshaat-portfolio`.
3. Commit and push changes to `main`.
4. In GitHub: Settings → Pages → Deploy from a branch → `main` / `(root)` → Save.
5. Open https://munshaat.github.io/munshaat-portfolio/ after publishing.

For local testing, open `index.html` or run `python -m http.server 8000` from the extracted folder. All local links use relative URLs and work under a GitHub Pages project subdirectory.

## Page and asset structure

- `index.html`: home, education, overview, selected projects, skills, training, leadership, contact.
- `research.html`: detailed collaborative thesis and selected figures extracted **only** from the thesis.
- `projects.html`: all ten user-specified project repos plus the verified LinkedIn project; two distinct lab collections.
- `assets/css/style.css`, `assets/js/site.js`: responsive styles and mobile nav / project filters.
- `assets/figures/`: five figure crops from the undergraduate thesis, not other reports. The original thesis PDF is not bundled.
- `assets/reports/`: five **actually uploaded** non-thesis project reports, including Tic-Tac-Toe; no student IDs appear in the website narrative (original PDFs may contain student IDs and collaborator names).

## Content integrity / source notes

- Thesis supervisor: Dr. Mohammad Masum Billah; the 2026 thesis credits Munshaat Atiq Nuzaba, Mahzabin Ishrat, and Somia Alam. Manuscript remains **in preparation**.
- Analog experiments listed in exact **01–05** order from repository README.
- Biomedical collection has four top-level project directories, presented in GitHub file-list order. The repository has no numbered experiment order in its visible README, so no numbered experiment chronology is asserted.
- The requested `6 Bit SAP.pdf` **was not uploaded**. SAP-1 has a GitHub link but no fictional report download.
- The supplied LinkedIn activity is a **MATLAB convolution/correlation visualizer**, not an Esonance or Soccer Bot activity. It is therefore linked to its signal-processing project card.
- The supplied two-page CV is included locally at `assets/Munshaat_Atiq_Nuzaba_CV.pdf` and linked in the site navigation, home hero, and contact area.
- Design is inspired by the supplied dark-navy/cyan identity and built independently. The separate inspiration website could not be accessed during research.
- External resources (GitHub/LinkedIn) require network access, but the website's content works without network aside from optional Google Fonts.

## Original project repositories

- [Audio Pattern Detection Using MATLAB](https://github.com/Munshaat/audio-pattern-detection-matlab)
- [Economic Emission Dispatch Optimization](https://github.com/Munshaat/economic-emission-dispatch-optimization)
- [Home Automation System](https://github.com/Munshaat/Home-Automation-System)
- [Solar Power Conversion System](https://github.com/Munshaat/solar-power-conversion-system)
- [RetroLogic: Handheld Tic-Tac-Toe](https://github.com/Munshaat/RetroLogic-Handheld-Tic-Tac-Toe-Using-AT89C51)
- [Bluetooth Interfacing with Microcontroller](https://github.com/Munshaat/Bluetooth-Interfacing-with-Microcontroller)
- [6-bit SAP-1 Computer](https://github.com/Munshaat/6-bit-sap1-computer)
- [Langton’s Ant MATLAB App](https://github.com/Munshaat/Langtons-Ant-Matlab-App)
- [Residential Building Electrical Wiring](https://github.com/Munshaat/Residential-Building-Electrical-Wiring-)
- [Smart Home Automation System](https://github.com/Munshaat/Smart-Home-Automation-System)

## Privacy note

Only the five non-thesis project reports and the supplied CV are bundled as PDFs. **The thesis PDF is intentionally excluded and not linked anywhere**; only five selected thesis figures are used. Other project reports may contain student IDs or personal details; review before publishing.

## November 2026 revisions

- The homepage now presents comprehensive Electrical & Electronic Engineering skills, projects, and industry exposure; semiconductor research remains a featured specialization, not the sole emphasis.
- Education includes BSc (IUT), HSC Science GPA 5.00 (Rajuk Uttara Model College), and SSC Science GPA 5.00 (Rajuk Uttara Model College).
- Manuscript status has been removed from the research page.
- The thesis PDF is intentionally not packaged or linked; only five figures extracted from the thesis are used.
- The uploaded two-page CV is packaged at `assets/Munshaat_Atiq_Nuzaba_CV.pdf`.
