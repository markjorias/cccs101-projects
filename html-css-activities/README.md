<div align="center">

# HTML/CSS Activities

**CCCS 101 · Web Development · BSCS 1A**

Four webpage exercises, from a basic HTML page to a responsive recreation of the X landing page.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=flat&logo=visualstudiocode&logoColor=white)
![Status](https://img.shields.io/badge/Activities-4%20of%204-success?style=flat)
![Period](https://img.shields.io/badge/Nov%E2%80%93Dec-2023-blue?style=flat)

</div>

---

## Contents

- [Overview](#overview)
- [Tech stack](#tech-stack)
- [Activity 1: College of Computer Studies page](#activity-1--college-of-computer-studies-page)
- [Activity 2: Sign-up form](#activity-2--sign-up-form)
- [Activity 3: TikTok log-in page](#activity-3--tiktok-log-in-page)
- [Activity 4: X landing page](#activity-4--x-landing-page)
- [Timeline](#timeline)
- [Project structure](#project-structure)
- [Running the pages](#running-the-pages)

---

## Overview

| # | Folder | Project | Date | Highlights |
|:-:|---|---|---|---|
| 1 | [`lab_act1`](lab_act1/) | College of Computer Studies page | 5 – 7 Nov 2023 | Headings, image, list, table, embedded CSS |
| 2 | [`lab_act2`](lab_act2/) | "Create an account" sign-up form | 15 Nov 2023 | Form inputs, external stylesheet, Flexbox, button states |
| 3 | [`lab_act3`](lab_act3/) | TikTok "Log in" page | 20 – 21 Nov 2023 | Pixel-matched layout, icon buttons, hover transitions |
| 4 | [`lab_act4`](lab_act4/) | X "Happening now / Join today" page | 28 – 29 Nov 2023 | Custom font, two-column layout, responsive breakpoint |

Each activity includes its source files, the task material, and screenshots of the HTML, the CSS and the rendered output.

---

## Tech stack

| Technology | Used for | Activities |
|---|---|:-:|
| **HTML5** | Page structure, semantic elements, forms and inputs, tables, lists | 1 – 4 |
| **CSS3** | Styling, external stylesheets, hover / active states, transitions | 1 – 4 |
| **Flexbox** | Centering and row / column layouts | 2 – 4 |
| **Media queries** | Responsive layout (`max-width: 1017px`) | 4 |
| **`@font-face`** | Self-hosted Anek Latin variable font | 4 |
| **Visual Studio Code** | Code editor | 1 – 4 |
| **Live Server** | Local preview during development | 2 – 4 |
| **Google Chrome** | Browser used for testing and output screenshots | 1 – 4 |
| **icons8** | Icon images for the log-in buttons | 3 |

---

## Activity 1 · College of Computer Studies page

| | |
|---|---|
| **Folder** | [`lab_act1/`](lab_act1/) |
| **Date** | 5 – 7 Nov 2023 |
| **Files** | [`WEBPAGE1.html`](lab_act1/WEBPAGE1.html) |
| **Stack** | HTML5 · embedded CSS |

A static page for the College of Computer Studies, Bachelor of Computer Science.

**Features**
- Centered page heading over a cyan background
- Feature image
- **PROGRAMS** section with a list of the college's programs
- Class identification table (`CCCS101 · BSCS · 1A`)

<div align="center">

| Output |
|:-:|
| <a href="lab_act1/SCREENSHOTS/WEBPAGE1_OUTPUT.png"><img src="lab_act1/SCREENSHOTS/WEBPAGE1_OUTPUT.png" alt="Activity 1 output" width="480"></a> |

</div>

<sub>Output rendered in headless Firefox.</sub>

---

## Activity 2 · Sign-up form

| | |
|---|---|
| **Folder** | [`lab_act2/`](lab_act2/) |
| **Date** | 15 Nov 2023 |
| **Files** | [`WEBPAGE2.html`](lab_act2/ORIAS_1A/WEBPAGE2.html) · [`WEBPAGE2.css`](lab_act2/ORIAS_1A/styles/WEBPAGE2.css) |
| **Stack** | HTML5 · CSS3 · Flexbox |

A centered "Create an account" card with first name, last name, email and password fields and a **Sign Up** button.

**Features**
- Card centered on the screen with Flexbox (`height: 100vh`)
- Form fields stacked in a column, with `text`, `email` and `password` input types and placeholders
- Yellow page background with a white, rounded card
- Button with `:hover` and `:active` colour states
- Styles kept in an external stylesheet under `styles/`

<div align="center">

| Output | Source code |
|:-:|:-:|
| <a href="lab_act2/SCREENSHOTS/%5B2%5D%20ORIAS_1A_WEBPAGE2_LIVE_VIEW.png"><img src="lab_act2/SCREENSHOTS/%5B2%5D%20ORIAS_1A_WEBPAGE2_LIVE_VIEW.png" alt="Activity 2 output" width="440"></a> | <a href="lab_act2/SCREENSHOTS/%5B3%5D%20ORIAS_1A_WEBPAGE2_VS_CODE.png"><img src="lab_act2/SCREENSHOTS/%5B3%5D%20ORIAS_1A_WEBPAGE2_VS_CODE.png" alt="Activity 2 source in VS Code" width="200"></a> |

</div>

---

## Activity 3 · TikTok log-in page

| | |
|---|---|
| **Folder** | [`lab_act3/`](lab_act3/) |
| **Date** | 20 – 21 Nov 2023 (opened 20 Nov, due 21 Nov) |
| **Files** | [`WEBPAGE3.html`](lab_act3/ORIAS_1A/WEBPAGE3.html) · [`WEBPAGE3.css`](lab_act3/ORIAS_1A/WEBPAGE3.css) |
| **Stack** | HTML5 · CSS3 · Flexbox · icons8 |

A recreation of TikTok's "Log in to TikTok" dialog from a reference image ([`TASK/`](lab_act3/TASK/)).

**Features**
- Title and subtitle above six full-width login options: phone / email / username, Facebook, Google, Twitter, Apple and Instagram
- Card limited to `max-width: 420px` with a soft shadow, centered with Flexbox
- Each button is a Flexbox row: fixed-size icon on the left, centered label
- `transition: .4s ease` with a goldenrod hover colour
- Layout holds in both landscape and portrait windows
- Icons load from icons8, so an internet connection is needed

<div align="center">

| Reference | Output · landscape | Output · portrait |
|:-:|:-:|:-:|
| <a href="lab_act3/TASK/TikTok-website-4.jpg"><img src="lab_act3/TASK/TikTok-website-4.jpg" alt="TikTok reference" width="190"></a> | <a href="lab_act3/SCREENSHOTS/WEBPAGE3_OUTPUT_LANDSCAPE.png"><img src="lab_act3/SCREENSHOTS/WEBPAGE3_OUTPUT_LANDSCAPE.png" alt="Landscape output" width="400"></a> | <a href="lab_act3/SCREENSHOTS/WEBPAGE3_OUTPUT_PORTRAIT.png"><img src="lab_act3/SCREENSHOTS/WEBPAGE3_OUTPUT_PORTRAIT.png" alt="Portrait output" width="150"></a> |

</div>

<details>
<summary><b>Code screenshots</b></summary>
<br>

<div align="center">

| HTML | CSS |
|:-:|:-:|
| <a href="lab_act3/SCREENSHOTS/WEBPAGE3_HTML.png"><img src="lab_act3/SCREENSHOTS/WEBPAGE3_HTML.png" alt="HTML screenshot" width="240"></a> | <a href="lab_act3/SCREENSHOTS/WEBPAGE3_CSS.png"><img src="lab_act3/SCREENSHOTS/WEBPAGE3_CSS.png" alt="CSS screenshot" width="240"></a> |

</div>

</details>

---

## Activity 4 · X landing page

| | |
|---|---|
| **Folder** | [`lab_act4/`](lab_act4/) |
| **Date** | 28 – 29 Nov 2023 (opened 28 Nov, due 29 Dec); redo on 5 Dec 2023 |
| **Files** | [`WEBPAGE4.html`](lab_act4/ORIAS_1A/WEBPAGE4.html) · [`WEBPAGE4.css`](lab_act4/ORIAS_1A/WEBPAGE4.css) |
| **Stack** | HTML5 · CSS3 · Flexbox · Media queries · Anek Latin font |

The X (formerly Twitter) logged-out landing page with a responsive layout.

**Features**
- Two-column layout: large X logo on the left, **"Happening now / Join today."** sign-up column on the right
- *Sign up with Google* and *Sign up with Apple* buttons with logos, an "or" divider, a blue *Create account* button and an outlined *Sign in* button
- Terms notice and the full footer link row
- Anek Latin variable font loaded locally with `@font-face`
- `@media (max-width: 1017px)` breakpoint that stacks the columns and resizes the logo, headings and footer
- [`REDO/`](lab_act4/REDO/): alternate layout scaffold (`Home.html`, `styles.css`) with its own icons

<div align="center">

| Task prompt | Output · desktop |
|:-:|:-:|
| <a href="lab_act4/TASK.png"><img src="lab_act4/TASK.png" alt="Activity 4 task" width="440"></a> | <a href="lab_act4/SCREENSHOTS/WEBPAGE4_OUTPUT.png"><img src="lab_act4/SCREENSHOTS/WEBPAGE4_OUTPUT.png" alt="Desktop output" width="440"></a> |

| Output · responsive (1) | Output · responsive (2) |
|:-:|:-:|
| <a href="lab_act4/SCREENSHOTS/WEBPAGE4_OUTPUT_RESPONSIVE1.png"><img src="lab_act4/SCREENSHOTS/WEBPAGE4_OUTPUT_RESPONSIVE1.png" alt="Responsive output 1" width="440"></a> | <a href="lab_act4/SCREENSHOTS/WEBPAGE4_OUTPUT_RESPONSIVE2.png"><img src="lab_act4/SCREENSHOTS/WEBPAGE4_OUTPUT_RESPONSIVE2.png" alt="Responsive output 2" width="440"></a> |

</div>

<details>
<summary><b>Code screenshots</b></summary>
<br>

<div align="center">

| HTML | CSS (1) | CSS (2) | CSS (3) |
|:-:|:-:|:-:|:-:|
| <a href="lab_act4/SCREENSHOTS/WEBPAGE4_HTML.png"><img src="lab_act4/SCREENSHOTS/WEBPAGE4_HTML.png" alt="HTML screenshot" width="160"></a> | <a href="lab_act4/SCREENSHOTS/WEBPAGE4_CSS/1.png"><img src="lab_act4/SCREENSHOTS/WEBPAGE4_CSS/1.png" alt="CSS 1" width="200"></a> | <a href="lab_act4/SCREENSHOTS/WEBPAGE4_CSS/2.png"><img src="lab_act4/SCREENSHOTS/WEBPAGE4_CSS/2.png" alt="CSS 2" width="200"></a> | <a href="lab_act4/SCREENSHOTS/WEBPAGE4_CSS/3.png"><img src="lab_act4/SCREENSHOTS/WEBPAGE4_CSS/3.png" alt="CSS 3" width="200"></a> |

</div>

</details>

---

## Timeline

| Date (2023) | Milestone |
|---|---|
| 5 – 7 Nov | **Activity 1** completed |
| 15 Nov | **Activity 2** completed |
| 20 – 21 Nov | **Activity 3** opened 20 Nov, completed and submitted 21 Nov |
| 28 – 29 Nov | **Activity 4** opened 28 Nov, completed 29 Nov |
| 5 Dec | **Activity 4** redo started |

<sub>Dates for activities 3 and 4 come from the task prompts. The others come from the timestamps of the original assets and screenshots.</sub>

---

## Project structure

```
html-css-activities/
├── lab_act1/    WEBPAGE1.html · images · SCREENSHOTS/
├── lab_act2/    ORIAS_1A/ (WEBPAGE2.html · styles/) · SCREENSHOTS/
├── lab_act3/    ORIAS_1A/ (WEBPAGE3.html · WEBPAGE3.css) · SCREENSHOTS/ · TASK/
└── lab_act4/    ORIAS_1A/ (WEBPAGE4.html · WEBPAGE4.css · logos · font) · REDO/ · SCREENSHOTS/ · TASK.png
```

---

## Running the pages

No build step or dependencies are required.

1. Clone or download the repository.
2. Open the `.html` file of any activity in a browser, or serve the folder with the VS Code **Live Server** extension.

> [!NOTE]
> Activity 3 loads its icons from icons8, so open it while online.
