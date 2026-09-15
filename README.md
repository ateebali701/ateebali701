<h1 align="center">Hi 👋, I'm Muhammad Ateeb Ali</h1>
<h3 align="center">Civil Engineering Undergraduate | Water Resources & Hydrological Modeling | GIS · Remote Sensing · Google Earth Engine</h3>

<p align="center">
  📧 mateebali.be101mce@student.nust.edu.pk &nbsp;|&nbsp;
  📱 +92 334 877 5983 &nbsp;|&nbsp;
  <a href="PASTE-YOUR-LINKEDIN-LINK-HERE">🔗 LinkedIn</a> &nbsp;|&nbsp;
  <a href="https://github.com/ateebali701">💻 GitHub</a> &nbsp;|&nbsp;
  <a href="PASTE-YOUR-CV-DRIVE-LINK-HERE">📄 Full CV</a>
</p>

---

### 👋 About Me

Dedicated and research-driven civil engineering enthusiast with prior exposure to real-world dam construction environments. Skilled in QGIS, ArcGIS Pro, Google Earth Engine, Python, Remote Sensing, and HEC-HMS, with a strong focus on watershed hydrology and machine learning-based prediction. Committed to advancing innovative, data-driven water resources solutions and contributing effectively to engineering research teams through applied learning and analysis.

**🎓 Education:** B.E. Civil Engineering, National University of Sciences and Technology (NUST), Islamabad — 2023 to Present | CGPA: 3.48/4.00 (until 7th semester)
**Relevant Coursework:** River Engineering · Engineering Hydrology · Fluid Mechanics I & II · Irrigation Engineering · Soil Mechanics I & II · Engineering Geology · Geoinformatics and Slope Stability *(In Progress)*

---

## 🔬 Research Interests

- Hydrological Modeling
- Surface Runoff Analysis
- Watershed Modeling
- GIS and Spatial Analysis
- Remote Sensing
- Land Use / Land Cover Change
- Environmental Modeling
- Geospatial Data Science
- Machine Learning for Earth Observation
- Climate and Water Resources Analysis

---

## 🌊 Featured Research Project

### Impact of Land Use/Land Cover Dynamics on the Hydrological Response of the Rawalpindi-Islamabad Watershed

**Final Year Design Project (2026 – Present)** · *Advisor: Lt Colonel Ali Khan, National University of Sciences and Technology*

This research examines how historical and predicted future land-use/land-cover (LULC) changes in the Soan River / Rawalpindi-Islamabad watershed affect surface runoff and overall hydrological response, combining satellite-based classification with machine learning-based future prediction and hydrological modeling.

**LULC Classification**
- Watershed boundary delineated for the full study area.
- Supervised classification performed in Google Earth Engine across seven time steps at a 4-year interval: **2000, 2004, 2008, 2012, 2016, 2020, 2024**, using Landsat 5 (earlier years) and Landsat 8/9 (recent years), all imagery from the September–November window for seasonal consistency.
- Four LULC classes: **Water (0), Built-up (1), Vegetation (2), Barren Land (3)**, symbolized with a fixed color scheme for consistent map layouts across all years.
- Change detection performed year-on-year (2000→2004→2008→...→2024) directly in Google Earth Engine for workflow consistency.
- Map layouts generated with legend, scale bar, north arrow, and coordinate-grid tick marks for each classified year.

**Future LULC Prediction**
- Future LULC predicted for **2032, 2040, 2048, 2056, and 2064** using a Random Forest + CA-Markov modeling approach, coded in Python (Google Colab), projected forward via repeated Markov-matrix transition steps from a 2020→2024 base transition matrix.
- Model validated with two back-testing checks: predicting 2020 from the 2012→2016 transition, and predicting 2024 from the 2016→2020 transition, each compared against the actual classified map for that year.
- Environmental driving factors used: elevation, slope, and distance from roads, water bodies, and built-up areas — the distance-based factors were recomputed using Earth Engine's `fastDistanceTransform()` after an initial `cumulativeCost()`-based approach produced a striping artifact in the output.
- Prediction pipeline is also being cross-checked with an equivalent Random Forest + Markov + Cellular Automata implementation directly in Google Earth Engine (JavaScript) for consistency.

**Hydrological Modeling**
- Present-day and predicted future LULC scenarios compared to analyze changes in peak flow, surface runoff, and overall hydrological response of the watershed.

📎 **Proof of work:** [View Full Project Files / Report](PASTE-ONE-DRIVE-LINK-HERE)

---

## 📄 Publications & Research Manuscripts

### Land Use/Land Cover Change and Watershed Hydrology: A Systematic Review of Remote Sensing, GIS, and Artificial Intelligence Approaches with Implications for Hydrological Risks to Dams
**Status:** Manuscript in Preparation
A systematic literature review (2013–2026, global scope) synthesizing how remote sensing, GIS, and AI have been applied to LULC change, watershed hydrology, and hydrological risk to dams, structured to support ongoing research applications in water resources engineering.

📎 **Proof of work:** [View Manuscript / Literature Matrix](PASTE-ONE-DRIVE-LINK-HERE)

---

## 🔬 Research Experience

### Research Assistant — Senior's Final Year Design Project (Flood Modeling) *(Fall 2025)*
*National University of Sciences and Technology, Risalpur, Pakistan*
- Assisted in catchment delineation using ArcGIS to define the watershed boundary for hydrological analysis.
- Supported flood forecasting simulations in HEC-HMS for the study watershed.
- Contributed to flood inundation mapping in HEC-RAS to identify flood-prone areas.

### Undergraduate Researcher — Hydrograph Analysis and Infiltration Modeling Using Python *(Fall 2025, Self-directed)*
*National University of Sciences and Technology*
- Modeled Horton's infiltration curve in Python to estimate infiltration rate and cumulative depth.
- Coded S-Curve and superposition methods to convert and combine unit hydrographs in Python.
- Generated total surface runoff hydrographs by convolving unit hydrographs with rainfall excess, using four Python modules (Horton's Infiltration, Surface Runoff Hydrograph via convolution, S-Curve Method, Superposition Method) built and run in Google Colab, with data drawn from own Engineering Hydrology coursework.

📎 **Proof of work:** [View Supporting Files / Notebooks](PASTE-ONE-DRIVE-LINK-HERE)

---

## 🎓 Academic Projects

- **Streamflow Measurement, Cross-Sectional Discharge Analysis, and Channel Control Assessment for Flood Risk Management – Soan River** — River Engineering (CE-462), Spring 2026
- **Watershed Drainage Pattern and River Morphology Analysis Using Strahler's Bifurcation Method for Regional Flood Risk Assessment** — River Engineering (CE-462), Spring 2026
- **Irrigation Scheduling and Gross Irrigation Requirement (GIR) Analysis for Crop Water Requirement Comparison Using CLIMWAT/CROPWAT – Talagang, Punjab** — Irrigation Engineering (CE-463), Spring 2026
- **Statistical and Hydrological Analysis of 116-Year Rainfall Data for Seasonality and Trend Assessment in Pakistan** — Engineering Hydrology (CE-358), Fall 2025
- **Multi-Sub-Basin Hydrological Modeling and Calibration Using HEC-HMS for Watershed Flow Response Assessment** — Engineering Hydrology (CE-358), Fall 2025
- **Single-Event Rainfall-Runoff Simulation and Hydrograph Generation Using HEC-HMS (SCS Curve Number Method)** — Engineering Hydrology (CE-358), Fall 2025
- **Open Channel Hydraulic Analysis of Flow Regimes and Manning's Roughness Estimation for Trapezoidal and Compound Channels** — Fluid Mechanics-II (CE-252), Spring 2025
- **Topographic Mapping, Traversing, and Contouring for Road Alignment Design Using Total Station and GPS** *(Syndicate Leader)* — Engineering Surveying (CE-286), Spring 2025
- **MATLAB-Based Symbolic Computation of Differential Equations, Integrals, Derivatives, and Limits** — Numerical Methods (MATH-355), Fall 2024

<!-- Add any further academic projects below in the same format:
- **Project Title** — Course (Code), Semester
-->

📎 **All project files / reports:** [View Folder](PASTE-ONE-DRIVE-LINK-HERE)

---

## 🧪 Laboratory Experience

- **Engineering Hydrology** — Groundwater Flow, Hydraulic Gradient, Aquifer Analysis, *Fall 2025*
- **Fluid Mechanics-II** — Flow Regimes, Hydraulic Jumps, Flume, Unsteady Flow, Data Analysis, *Spring 2025*
- **Soil Mechanics-II** — Shear Strength Parameters, Bearing Capacity, Consolidation Settlement, Geotechnical Testing, *Spring 2025*
- **Fluid Mechanics-I** — Hydrostatic Pressure, Buoyancy and Stability, Impact of Jets, Discharge Coefficients (Orifice & Notch), *Fall 2024*
- **Soil Mechanics-I** — Ground Water Flow Project, *Fall 2024*

---

## 🏗️ Industrial Experience

### Internee Engineer — Diamer Basha Dam Project *(Jun 2026 – Jul 2026)*
*POWERCHINA – FWO Joint Venture (JV), Chilas, Gilgit-Baltistan, Pakistan*
- Analyzed excavation at the dam body, power intake, and downstream wing sections.
- Participated in blast drilling and charging using 38–90mm holes with millisecond delay detonation sequencing.
- Studied rock support design: 210 kN rock bolts, tendons, wire mesh, and shotcrete across 5 RMR rock classes.
- Observed dam pit foundation treatment and dental concrete placement at 898m founding level.
- Assisted in laboratory quality control testing including grout flow, compressive strength, and pull-out tests.

### Internee Engineer — Dhadhocha Dam Project *(Jun 2025 – Aug 2025)*
*Frontier Works Organization (FWO), Rawalpindi, Pakistan*
- Studied a 123 ft zoned earth-fill dam with core, filter, and shell zones for seepage control.
- Analyzed a 60,000 acre-ft reservoir storage (45,000 live) across a 129 sq mile catchment.
- Reviewed a 250 ft spillway (42,000 cusec) designed for a 1,000-year, 77,950 cusec flood.
- Studied dam components (coffer dam, inlet/outlet, spillway, bridge) designed for 35 MGD supply capacity.
- Learned dam safety monitoring: seepage, pore pressure, settlement, embankment condition.

📎 **Internship completion certificates (both):** [View Folder](PASTE-ONE-DRIVE-LINK-HERE)

---

## 🤝 Leadership & Volunteer Experience

- **Active Student Member**, American Society of Civil Engineers (ASCE) *(Sep 2025 – Present)*
- **Course Prefect**, CED-101, Military College of Engineering, NUST *(Sep 2025 – May 2026)* — Acted as the main point of contact between course mates and faculty, relaying updates and resolving exam schedules and coursework deadlines.
- **Academic Prefect**, CED-101 (PCs), Military College of Engineering, NUST *(2026)*
- **Secretary**, ASCE Bridge Design Competition 2025, MCE, NUST *(Feb 2025)* — Designed and tested a structural bridge model, applying core structural analysis principles under competition constraints.
- **Organizer and Volunteer**, FATIMID Foundation Blood Bank & Haemotological Services *(Feb 2025)* — Organized and registered blood donors, assisted during the donation process.
- **Academic Distinction Holder** — Ranked among top 3 students in class, MCE, NUST *(Spring 2025)*
- **Secretary**, Research and Innovation Society *(Spring 2024)*
- **Class Representative**, Civil Engineering Batch, MCE, NUST *(Fall 2023 – Spring 2024)*

📎 **Supporting certificates / proof (all):** [View Folder](PASTE-ONE-DRIVE-LINK-HERE)

---

## 🛠️ Technical Skills

**Software:** QGIS · ArcGIS Pro · HEC-HMS · CROPWAT · CLIMWAT · MATLAB · ETABS
**Programming Languages:** Python · JavaScript · C#
**CAD Software:** AutoCAD · BIM Revit
**Project Management Software:** Oracle Primavera P6 · Microsoft Office (Word, Excel, PowerPoint)

---

## 📜 Certifications

- Remote Sensing Image Acquisition, Analysis and Applications — UNSW Sydney & IEEE Geoscience and Remote Sensing Society (Coursera), *Sep 2026*
- Introduction to GIS Mapping — University of Toronto (Coursera), *Aug 2026*
- AutoCAD — Digiskills.pk (DSTP3.0-Batch-02), *Jul 2026*
- CPD Workshop on Construction Estimation using PlanSwift and BlueBeam — *Apr 2026*
- Supervised Machine Learning: Regression and Classification — DeepLearning.AI / Stanford (Coursera), *Aug 2025*
- Python Programming — NUST SEECS (On Campus), *Jul 2025*
- Planning and Control with Oracle Primavera PPM Professional — packt (Coursera), *Jul 2025*
- Advanced Scheduling and Project Optimization in Primavera P6 — packt (Coursera), *Jun 2025*
- Oracle Primavera P6: Project Setup and Basic Management — packt (Coursera), *May 2025*
- BIM Fundamentals for Engineers — National Taiwan University (Coursera), *May 2025*
- AutoCAD 2023 Masterclass – Produce Amazing Site Plans — packt (Coursera), *May 2025*

📎 **All certificates:** [View Folder](PASTE-ONE-DRIVE-LINK-HERE)

---

## 💬 Recommendations / Reference Letters

- **Lt Col Mohammad Ali Khan** — FYDP Supervisor, National University of Sciences and Technology
- **Dr. Mohammad Amjad** — Associate Professor & HOD, Water Resources Engineering and Management, NUST
- **Dr. Imran Ullah** — Associate Professor, National University of Sciences and Technology

📎 **All recommendation letters:** [View Folder](PASTE-ONE-DRIVE-LINK-HERE)

---

## 📫 Contact

📧 **Email:** mateebali.be101mce@student.nust.edu.pk
📱 **Phone:** +92 334 877 5983
💼 **LinkedIn:** [PASTE-YOUR-LINKEDIN-LINK-HERE](PASTE-YOUR-LINKEDIN-LINK-HERE)
💻 **GitHub:** [github.com/ateebali701](https://github.com/ateebali701)
📄 **CV:** [View / Download CV](PASTE-CV-LINK-HERE)

---

## 🤝 Research Collaboration

I am interested in research opportunities, internships, and collaborations related to:

- Hydrology
- Water Resources Engineering
- GIS
- Remote Sensing
- Environmental Modeling
- Geospatial Data Science
- Machine Learning applications in Civil and Environmental Engineering

Please feel free to contact me through LinkedIn or email.

---

<p align="center"><i>Thanks for visiting my profile — feel free to explore my pinned repositories below for detailed project code and documentation.</i></p>
