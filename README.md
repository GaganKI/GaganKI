# Gagan K I

**Final-year B.E. student in AI & ML (VTU, 2027) building ML systems with real backends behind them.**
Python · FastAPI / Flask · PostgreSQL · PyTorch · Docker

Based in Shivamogga, Karnataka. Looking for **ML and backend engineering internships**, Bangalore or remote.

[Portfolio](https://gaganki.github.io) · [LinkedIn](https://www.linkedin.com/in/gagan-ijantkar-29aa91292) · [Email](mailto:gaganijantkar7518@gmail.com)

---

## What I build

I like the part of ML that comes after the notebook: serving a model behind an API, storing its output in a database, and putting it somewhere a person can use it. I use AI tools to move faster, and I only ship what I can explain and rewrite myself.

## Projects

### SmartRoad: pothole detection and road monitoring
YOLOv8m detects potholes from road imagery, a MiDaS depth model estimates severity, and a Flask API stores detections with GPS coordinates in PostgreSQL/PostGIS. A React front end shows them on a map and supports live detection.

- Trained on 19,000+ annotated road instances. Current results: **0.66 recall, 0.46 mAP**. Improving recall is the next goal.
- Deployed end to end: front end on Vercel, inference API on Hugging Face, database on Render.
- Stack: `Python` `Flask` `YOLOv8m` `MiDaS` `React` `PostgreSQL` `PostGIS`

[Live demo](https://pothole-project-uw6k.vercel.app) · [Code](https://github.com/GaganKI/pothole-project)

### ADAPTO-MULE: transaction fraud detection *(in development)*
A fraud-detection backend with JWT-authenticated transaction APIs. The design centres on graph-based anomaly scoring of suspicious transaction patterns, with a Dockerised local setup.

- Stack: `Python` `FastAPI` `PostgreSQL` `Docker` `PyTorch Geometric`

### ExplainSomatic: somatic mutation detection with explainability *(final-year project, in progress)*
A dual-stream CNN + Transformer model for detecting somatic mutations, with Grad-CAM explanations and VAF-aware loss weighting so very-low-frequency variants are not drowned out. Built on the SEQC2 HCC1395 dataset, supervised by Dr. Likewin Thomas.

- Stack: `PyTorch` `Python` `Google Colab`

### CRM lead importer
A full-stack tool that imports and structures CRM leads with the Gemini API, built as a take-home assignment.

- Stack: `Next.js` `Node.js` `Gemini API`

[Live demo](https://crm-lead-importer-beta.vercel.app)

### Earlier work
- **Closed-loop precision agriculture ML system**: temporal sensor-data pipeline with automated labelling and a multi-output classifier for irrigation and nutrient recommendations (`Scikit-learn`)
- **KIA Car Showroom DBMS**: multi-role admin, sales and customer system replacing Excel workflows (`React` `PostgreSQL` `MongoDB` `Power BI`)
- **Real-time vehicle detection**: YOLOv5 + OpenCV with a live GUI and parking status (`Python` `Tkinter`)
- **College Finder, Karnataka**: REST API with server-side filtering (`Node.js` `MongoDB`)

---

## Skills

| Area | Tools |
| --- | --- |
| Languages | Python, JavaScript |
| ML / CV | PyTorch, Scikit-learn, YOLOv5/v8, OpenCV, Pandas, NumPy |
| Backend | FastAPI, Flask, REST APIs, JWT auth |
| Data | PostgreSQL, PostGIS, MongoDB |
| Tooling | Git, Docker, Vercel, Hugging Face, Render |
| Fundamentals | DSA, OOP, DBMS, OS, Computer Networks |

## Right now

- Finishing my final-year research project (ExplainSomatic)
- Building out ADAPTO-MULE
- Raising pothole-detection recall
- Practising DSA in Python and making open-source contributions (next: Flask/FastAPI docs, PyTorch Geometric)

## Recognition

TCS TechBytes 2024 (4th, regional) · Smart India Hackathon 2024 and 2025 · Google GDSC 2025 · MongoDB certification · IEEE Press Conference volunteer, PESITM

![Stats](https://github-readme-stats.vercel.app/api?username=GaganKI&show_icons=true&hide_border=true)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=GaganKI&layout=compact&hide_border=true)
