<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:050816,45:0f172a,100:1d4ed8&height=250&section=header&text=GIRIJESH%20S&fontSize=62&fontColor=ffffff&fontAlignY=37&desc=I%20BUILD%20MACHINES%20THAT%20SEE%2C%20READ%20AND%20REASON&descAlignY=59&descSize=16&animation=fadeIn" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=19&duration=2400&pause=700&color=60A5FA&center=true&vCenter=true&width=900&lines=Computer+Vision+%2F+Deep+Learning+%2F+OCR;Low-Resource+AI+%2F+Document+Forensics;Tamil+Language+Technology;Research+%E2%86%92+Engineering+%E2%86%92+Real-World+Systems" />

<br>

<a href="YOUR_PORTFOLIO_URL">
<img src="https://img.shields.io/badge/ENTER%20THE%20PORTFOLIO-ffffff?style=for-the-badge&labelColor=111827&color=2563EB"/>
</a>

</div>

<br>

---

<table>
<tr>
<td width="58%" valign="top">

## I build around a simple question

**Can machines understand things that humans take for granted?**

Images.
Documents.
Handwritten characters.
Historical scripts.
Messy language.

That's where most of my work lives.

I'm a B.Tech Artificial Intelligence & Data Science student working across **computer vision, deep learning, OCR, machine learning and language technology**.

I enjoy taking a problem from raw data all the way to a working system.

</td>

<td width="42%" valign="top">

```text
┌───────────────────────────┐
│       GIRIJESH.SYS        │
├───────────────────────────┤
│                           │
│  vision        [██████]   │
│  deep learning[█████░]   │
│  OCR           [██████]   │
│  ML            [█████░]   │
│  research      [██████]   │
│                           │
│  status: BUILDING         │
│                           │
└───────────────────────────┘
```

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=13&duration=1800&pause=500&color=94A3B8&width=400&lines=processing+ideas...;training+models...;testing+assumptions...;building+again..." />

</td>
</tr>
</table>

---

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=14&duration=3000&pause=1000&color=64748B&center=true&vCenter=true&width=800&lines=%5B+01+%5D+WHAT+I+WORK+ON" />

</div>

<table>
<tr>
<td width="25%" valign="top">

### Vision

Computer vision is where I spend most of my time.

`OpenCV`

`Image Processing`

`Image Enhancement`

`Image Segmentation`

`Image Classification`

`Anomaly Detection`

</td>

<td width="25%" valign="top">

### Intelligence

Models are only useful when the pipeline around them works.

`CNN`

`Neural Networks`

`Transformers`

`PyTorch`

`TensorFlow`

`Scikit-learn`

`XGBoost`

</td>

<td width="25%" valign="top">

### Language

I'm particularly interested in language systems where data is limited or difficult.

`OCR`

`PaddleOCR`

`EasyOCR`

`NLP`

`Tamil OCR`

`Tanglish`

</td>

<td width="25%" valign="top">

### Engineering

From experiment to something people can actually use.

`Python`

`SQL`

`C`

`Java`

`Streamlit`

`Pickle`

`Git`

`GitHub`

</td>
</tr>
</table>

---

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=14&duration=3000&pause=1000&color=64748B&center=true&vCenter=true&width=800&lines=%5B+02+%5D+THE+WORK" />

</div>

# 01 / Ancient Tamil OCR

### Teaching machines to read what time almost erased.

<table>
<tr>
<td width="62%" valign="top">

Ancient and handwritten Tamil characters are not a typical OCR problem.

The data is limited.
The characters vary.
The writing surface introduces noise.
Modern OCR systems aren't always designed for this environment.

So I built the pipeline from the ground up:

```text
manuscript
    ↓
adaptive preprocessing
    ↓
text-line segmentation
    ↓
glyph segmentation
    ↓
CNN recognition
    ↓
character prediction
```

The project is currently part of my research work, with a paper in progress.

</td>

<td width="38%" valign="top">

### Research snapshot

```text
10
manuscripts

~2,200
labelled glyphs

319
Tamil glyph classes

88.10%
character accuracy

11.90%
character error rate
```

The work has also been presented at technical competitions and received awards.

</td>
</tr>
</table>

<br>

---

# 02 / Visual Forensics AI

### A document shouldn't just be called fake.

### The system should show you **where** it was manipulated.

<table>
<tr>
<td width="45%" valign="top">

I developed a document-forensics pipeline combining multiple signals rather than depending on one black-box prediction.

```text
OCR
 │
 ├── forensic evidence
 │
ORB + RANSAC
 │
 ├── copy-move analysis
 │
ELA
 │
 ├── compression anomalies
 │
ResNet34
 │
 └── anomaly detection
```

</td>

<td width="55%" valign="top">

### The output

Instead of:

> `TAMPERED = TRUE`

the system produces evidence:

**Heatmaps**

**Bounding boxes**

**Confidence scores**

**Localized suspicious regions**

That makes the result easier to inspect and explain.

**Stack**

`Python` `OpenCV` `PyTorch` `PaddleOCR`

</td>
</tr>
</table>

---

# 03 / Olaisuvadi + Tamil Research

### Building the infrastructure around low-resource OCR.

My research also extends beyond the recognition model itself.

I contributed to **Olaisuvadi**, an open-source annotation platform covering **319 Tamil glyph classes**, supporting the creation of structured data for Tamil OCR research.

The broader research pipeline includes:

```text
DATA
 ↓
ANNOTATION
 ↓
PREPROCESSING
 ↓
SEGMENTATION
 ↓
MODEL
 ↓
BENCHMARK
 ↓
ANALYSIS
```

Benchmarked against:

`PaddleOCR PP-OCRv5`

`DeepSeek-OCR`

`Pixtral-12B`

`Donut`

`PARSeq`

---

# 04 / Tanglish → Tamil

### Because language doesn't always arrive in its original script.

A lightweight NLP-based transliteration system that converts Romanized Tamil into native Tamil script.

```text
"epdi iruka?"

        ↓

   normalization

        ↓

"எப்படி இருக்க?"
```

**Built with:** `Python` + `NLP`

Small system. Useful problem. Very Tamil.

---

# 05 / Machine Learning

<table>
<tr>
<td width="50%" valign="top">

### Four problems. One complete pipeline.

**Diabetes Prediction**

Classification

**House Price Prediction**

Regression

**Sonar**

Rock vs Mine classification

**Spam Mail**

Text classification

</td>

<td width="50%" valign="top">

```text
raw data
    │
    ▼
preprocessing
    │
    ▼
feature engineering
    │
    ▼
training
    │
    ▼
evaluation
    │
    ▼
serialization
    │
    ▼
deployment
```

`Scikit-learn`

`XGBoost`

`NumPy`

`Pandas`

</td>
</tr>
</table>

---

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=14&duration=3000&pause=1000&color=64748B&center=true&vCenter=true&width=800&lines=%5B+03+%5D+THE+STACK" />

</div>

<table>
<tr>
<td width="50%" valign="top">

## Programming

`Python`

`SQL`

`C`

`Java`

### ML

`Scikit-learn`

`XGBoost`

`Classification`

`Regression`

`Feature Engineering`

`Data Preprocessing`

`Model Training`

`Model Evaluation`

`Model Deployment`

</td>

<td width="50%" valign="top">

## Deep Learning

`CNN`

`Neural Networks`

`Transformers`

`PyTorch`

`TensorFlow`

### Vision

`OpenCV`

`Image Processing`

`Image Enhancement`

`Image Segmentation`

`Image Classification`

`Anomaly Detection`

</td>
</tr>

<tr>
<td width="50%" valign="top">

## OCR / NLP

`PaddleOCR`

`EasyOCR`

`OCR`

`NLP`

### Data

`NumPy`

`Pandas`

`Matplotlib`

`Pillow`

</td>

<td width="50%" valign="top">

## Engineering / Tools

`Streamlit`

`Pickle`

`Git`

`GitHub`

`Jupyter Notebook`

`Google Colab`

### Analytics

`Power BI`

`Data Analytics`

`Data Visualization`

</td>
</tr>
</table>

---

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=14&duration=3000&pause=1000&color=64748B&center=true&vCenter=true&width=800&lines=%5B+04+%5D+ANALYTICS" />

</div>

# Call Center Analytics

Not every problem needs a neural network.

Sometimes the right answer is simply understanding the data properly.

I built an interactive Power BI dashboard to explore:

```text
CALL VOLUME
     │
     ├───────────────┐
     ▼               ▼
RESOLUTION       AGENT
  RATE         PERFORMANCE
     │               │
     └───────┬───────┘
             ▼
       TREND ANALYSIS
```

Dynamic charts and filters turn raw call-center data into something decision-makers can actually explore.

Developed during my **TechnoHacks Data Analytics Internship**.

---

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=14&duration=3000&pause=1000&color=64748B&center=true&vCenter=true&width=800&lines=%5B+05+%5D+PROOF+OF+WORK" />

</div>

<table>
<tr>
<td width="50%" valign="top">

## Recognition

**1st — E-HORIZON Pitch Tech Competition**

2026

**1st — KaniniTamil Conference**

AI-driven Tamil Language Technology

**2nd — Tamilizhi Language Technology Hackathon**

</td>

<td width="50%" valign="top">

## Speaking / Presentation

**Global Startup Event**

Presenter

**CODISSIA AI Summit**

Presenter

The work has also been presented across multiple technical competitions.

</td>
</tr>
</table>

Your resume lists these achievements and presentations as part of your technical journey.

---

# Education

<table>
<tr>
<td width="70%" valign="top">

### Bannari Amman Institute of Technology

**B.Tech — Artificial Intelligence & Data Science**

`2024 → 2028`

</td>

<td width="30%" align="right" valign="top">

### 7.8

`CGPA / 10`

</td>
</tr>
</table>

---

# Certifications

`Python — HackerRank`

`AI Fundamentals — Oracle`

`Microsoft Azure Data Fundamentals — DP-900`

`Data Analytics Internship — TechnoHacks Solutions`

`Excel with AI — Great Learning`

---

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=14&duration=3000&pause=1000&color=64748B&center=true&vCenter=true&width=800&lines=%5B+06+%5D+CURRENT+TRAJECTORY" />

</div>

<table>
<tr>
<td width="30%" valign="top">

### Now

Learning.

Experimenting.

Building.

Breaking things.

Fixing them.

</td>

<td width="70%" valign="top">

### Direction

```text
                 COMPUTER VISION
                        │
            ┌───────────┴───────────┐
            │                       │
           OCR                DOCUMENT AI
            │                       │
            └───────────┬───────────┘
                        │
                 LOW-RESOURCE AI
                        │
            ┌───────────┴───────────┐
            │                       │
        LANGUAGE AI           EXPLAINABILITY
            │                       │
            └───────────┬───────────┘
                        ↓
                USEFUL AI SYSTEMS
```

I'm particularly interested in engineering systems where **research quality and real-world usability meet**.

</td>
</tr>
</table>

---

<div align="center">

# Let's build something worth showing.

<br>

<a href="YOUR_PORTFOLIO_URL">
<img src="https://img.shields.io/badge/VIEW%20PORTFOLIO-ENTER%20→-ffffff?style=for-the-badge&labelColor=0f172a&color=2563eb"/>
</a>

<br><br>

<a href="https://linkedin.com/in/girijesh-data-science">LinkedIn</a>
  ·   <a href="https://github.com/girijesh-s001">GitHub</a>
  ·   <a href="https://leetcode.com/u/girijesh1089">LeetCode</a>
  ·   <a href="mailto:girijesh1089@gmail.com">Email</a>

<br><br>

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=13&duration=2800&pause=900&color=64748B&center=true&vCenter=true&width=700&lines=research+%E2%86%92+prototype+%E2%86%92+experiment+%E2%86%92+system;still+building.;still+learning.;still+curious." />

<br><br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1d4ed8,50:0f172a,100:050816&height=140&section=footer" width="100%"/>

</div>
