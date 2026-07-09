<h1 align="center">Hi, I'm Mohammad Salman 👋</h1>

<p align="center">
  <b>MSc Geoinformatics</b> — IIRS (ISRO), in collaboration with ITC, University of Twente<br>
  <sub>Remote Sensing · Hyperspectral Imaging · Geospatial AI</sub>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/mohammadsalman-geo/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:msiirs2025@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

I build **classification and mapping pipelines on satellite and hyperspectral imagery** — where
the hard part is rarely the model, but proving the signal is real. Lately that has meant lunar
spectroscopy: separating genuine mineral absorption bands from instrument artefacts in
Chandrayaan data, and cross-validating one spacecraft's answer against another's.

My work spans **planetary surface mapping**, **urban growth analysis**, and **web-based
geovisualisation**.

<br>

<div align="center">
  <a href="https://github.com/msiirs2025/Moon_Soil_Mineral_Mapping_Hyperspectral">
    <img src="https://raw.githubusercontent.com/msiirs2025/Moon_Soil_Mineral_Mapping_Hyperspectral/main/docs/figures/iirs_destriped.png" width="150" alt="Dawes crater seen by Chandrayaan-2 IIRS">
  </a>
  <br>
  <sub><i>Dawes crater, Mare Tranquillitatis — Chandrayaan-2 IIRS, after radiometric, thermal,<br>photometric and destriping correction. <a href="https://github.com/msiirs2025/Moon_Soil_Mineral_Mapping_Hyperspectral">See the pipeline →</a></i></sub>
</div>

---

### 🛰️ Tech Stack

| Category | Tools & Technologies |
| :--- | :--- |
| **Languages** | ![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E) ![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=flat&logo=typescript&logoColor=white) |
| **Geospatial** | ![GDAL](https://img.shields.io/badge/GDAL-016A70?style=flat&logo=gdal&logoColor=white) ![QGIS](https://img.shields.io/badge/QGIS-589632?style=flat&logo=qgis&logoColor=white) **Rasterio** · **ENVI** · **PDS4** · **OBIA** |
| **Hyperspectral** | **SAM** · **SFF** · **Continuum removal** · **Band-ratio / BSA parameters** · **RELAB spectral libraries** |
| **Sensors** | **Chandrayaan-1 M³** · **Chandrayaan-2 IIRS** · **Sentinel-2** |
| **AI / Machine Learning** | ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=flat&logo=scikit-learn&logoColor=white) **Random Forest** · **SVM** · **Object-based classification** |
| **Data & Analysis** | ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=flat&logo=numpy&logoColor=white) ![SciPy](https://img.shields.io/badge/SciPy-%230C55A5.svg?style=flat&logo=scipy&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=flat&logo=pandas&logoColor=white) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=flat&logo=Matplotlib&logoColor=black) |
| **Web & Backend** | ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat&logo=fastapi) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white) ![GitHub Pages](https://img.shields.io/badge/GitHub_Pages-222222?style=flat&logo=github-pages&logoColor=white) |
| **Tools** | ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=flat&logo=git&logoColor=white) |

---

### 🌍 Featured Projects

#### 🌑 [Moon Soil Mineral Mapping — Hyperspectral](https://github.com/msiirs2025/Moon_Soil_Mineral_Mapping_Hyperspectral)

`Python` · `Chandrayaan-1 M³` · `Chandrayaan-2 IIRS`

End-to-end lunar mineral mapping over **Dawes crater, Mare Tranquillitatis** — raw radiance to
mineral maps, every step delivered as ENVI + GeoTIFF.

- Reproduces the **ISRO CH2IIRS** chain (radiometric → thermal removal → photometric →
  selenoreferencing → destriping) and validates it against ISRO's own reference products:
  incidence angle exact, temperature within **0.1 K**, reflectance sub-percent.
- Maps minerals with **SAM, SFF and SVM** on continuum-removed diagnostic bands, alongside
  Band-Shaping-Algorithm parameter images.
- **Result —** M³ and IIRS independently agree that Dawes crater is clinopyroxene-rich:
  **99.6 % per-pixel agreement (SAM)** between two spacecraft sixteen years apart.
- **Finding —** the apparent 1.9 µm "absorption band" in IIRS traces back, in the raw DN, to an
  **instrument spectral-response artefact** rather than mineralogy — a real limit on what this
  L1 product can support.

#### 🏙️ [OBIA vs Pixel-Based Classification — Sentinel-2](https://github.com/msiirs2025/obia-vs-pixel-sentinel2)

`Python` · `Sentinel-2` · `MIT`

Comparative study of **Object-Based Image Analysis** against pixel-based **Random Forest**
classification, applied to **Dehradun urban expansion (2016–2024)**.

#### 🦠 [Cholera Web Map](https://github.com/msiirs2025/web_cholera) — [**live demo ↗**](https://msiirs2025.github.io/web_cholera/)

`JavaScript` · `GitHub Pages`

Interactive browser-based geovisualisation of cholera data — the classic epidemiological mapping
problem, rebuilt as a modern web map.

#### 📈 [Dehradun Urban Growth Analysis](https://github.com/msiirs2025/dehradun_Urban_growth_analysis)

`Python` · `LULC`

Land-use / land-cover change analysis of Dehradun from 1990 onward, with GUI tooling and an
urban growth dashboard.

#### 🗂️ [EliteMappers](https://github.com/msiirs2025/EliteMappers_website)

`FastAPI` · `Next.js` · `TypeScript`

A student-services and project-management platform: FastAPI backend with 36 endpoints, Next.js
client and admin dashboards, designed to deploy at zero infrastructure cost.

---

### 📊 GitHub

<div align="center">
  <img height="150" alt="GitHub stats" src="https://github-readme-stats.vercel.app/api?username=msiirs2025&show_icons=true&hide_border=true&hide_title=true">
  <img height="150" alt="Top languages" src="https://github-readme-stats.vercel.app/api/top-langs/?username=msiirs2025&layout=compact&hide_border=true">
</div>

---

<p align="center">
  <sub>Open to collaboration on planetary remote sensing, hyperspectral analysis, and geospatial ML.</sub>
</p>
