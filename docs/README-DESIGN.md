# README V3 / The Exploration Lab

This profile presents MD Khalid Hasan as a CSE undergraduate at United International University and an AI/ML explorer. The existing coursework context, technical toolkit, learning goals, earlier project links, and contact destinations are preserved. Four featured projects connect ML experiments, algorithms, applied AI, and embedded systems; Machine Learning Hands-On remains first.

## Repository audit

Audited on 29 October 2026 (Asia/Dhaka), before editing:

- Origin: `https://github.com/khalidhasan7343/khalidhasan7343`, branch `main`.
- The working tree was clean. The repository contained only `README.md` and `animate.svg`; there were no existing asset directories, workflows, or additional documentation.
- The complete README and SVG were read. The actual SVG had **five**, rather than the six messages described in the brief, on a shared 16-second SMIL timeline. It already used clip-path reveals, base-attribute fallbacks, and reduced-motion CSS; these foundations are retained.
- The actual README already used a direct GitHub activity link, with no external streak panel. V3 keeps that reliable link and removes the old optional contribution-animation comment.
- The old blue contact badges become plain links. No contact destination changes.

The embedded-systems addition was applied as a targeted update to the completed, uncommitted V3 work. Its repository, firmware, report, wiring image, prototype photograph, and dashboard source were inspected before writing its entry. The hero, avatar, first three project entries, and existing project covers were retained.

## Visual system

An editorial identity sits above an engineering notebook: the original KH monogram, name and university in real HTML text, a small terminal panel, then four numbered project studies. The Exploration Map uses a vertical branch layout so its four domain labels remain readable on phones. Its first branch gives AI/ML a stronger border, an inset marker, and an explicit primary-exploration label. Project covers are abstract diagrams, explicitly described as cover art in their SVG descriptions.

| Token | Dark assets | Light assets |
| :--- | :--- | :--- |
| Background | `#0B0B0C` | `#FFFFFF` |
| Surface | `#161616` | `#F5F5F5` |
| Primary text | `#F5F5F5` | `#111111` |
| Secondary text | `#A3A3A3` | `#555555` |
| Decorative borders | `#303030` | `#D4D4D4` |

Sans-serif SVG text uses Arial, Helvetica, and the system sans-serif fallback. Technical annotations use `ui-monospace`, Cascadia Code, Consolas, Liberation Mono, and monospace. No fonts or images are fetched by the SVGs. GitHub's own text, link colors, spacing, and table appearance follow the visitor's GitHub theme.

Each README image uses `<picture>` with a dark source and a light default. Explicit variants support GitHub's embedding context without relying on a media query inside the SVG to select its colors. A visitor who cannot load images still has the identity, university, project descriptions, technologies, and repository links in the README text.

There are no fixed image heights except the square avatar. GitHub can scale the other images while preserving their intrinsic aspect ratios. Covers stack vertically rather than using a wide HTML table. Small cover annotations are repeated in readable Markdown headings; the map's essential domain labels use larger text.

## Asset inventory

| Use | Dark | Light / static |
| :--- | :--- | :--- |
| Typing hero | [animate.svg](../animate.svg) | [typing-light.svg](../assets/hero/typing-light.svg) |
| Animated identity | [kh-identity.svg](../assets/avatar/kh-identity.svg) | [kh-identity-light.svg](../assets/avatar/kh-identity-light.svg) |
| ML notebook cover | [machine-learning.svg](../assets/projects/machine-learning.svg) | [machine-learning-light.svg](../assets/projects/machine-learning-light.svg) |
| Algorithm cover | [algorithm-atlas.svg](../assets/projects/algorithm-atlas.svg) | [algorithm-atlas-light.svg](../assets/projects/algorithm-atlas-light.svg) |
| Maze cover | [maze-mind.svg](../assets/projects/maze-mind.svg) | [maze-mind-light.svg](../assets/projects/maze-mind-light.svg) |
| Embedded cover | [embedded-systems.svg](../assets/projects/embedded-systems.svg) | [embedded-systems-light.svg](../assets/projects/embedded-systems-light.svg) |
| Learning map | [exploration-map.svg](../assets/exploration/exploration-map.svg) | [exploration-map-light.svg](../assets/exploration/exploration-map-light.svg) |
| Motion-free identity | — | [kh-identity-static.svg](../assets/avatar/kh-identity-static.svg) |

The static avatar is provided here as a reusable, explicitly motion-free identity asset:

![Static KH monogram with three connected neural nodes](../assets/avatar/kh-identity-static.svg)

Every asset is referenced by the README or this document. `animate.svg` keeps its original root path. There is no build step, package dependency, generated workflow, or runtime script. When changing a themed asset, update its paired variant and keep geometry and timing consistent.

## Motion and accessibility

The hero's four messages share one **14.4-second** SMIL timeline. Each message gets a 3.6-second slot: approximately 0.8 seconds to reveal, 2.45 seconds to read, and 0.35 seconds to erase. The first message is complete on initial load; its next reveal crosses the cycle boundary. A separate 1.2-second cursor blink stays below two changes per second.

The messages are:

1. Exploring AI & Machine Learning
2. Learning Through Experiments
3. Algorithms, Intuition & Code
4. Building Practical Software

Clipping rectangles and cursor positions use the same key times and text widths. Discrete group opacity ensures one message is active at a time. The line has generous right padding for the longest message, and its position never changes between messages.

The avatar holds the monogram and three nodes still; only one small signal moves along the upper connection during a six-second cycle. The project covers and Exploration Map are entirely static.

With `prefers-reduced-motion: reduce`, the hero hides the entire animated group, including its cursor, and shows the first message as static text. The avatar hides its moving signal. If SMIL is unsupported, base SVG attributes still show a complete first message and recognizable monogram. The separate static avatar contains no animation elements. All SVGs have a title and description; README images have meaningful alt text.

## Featured-project evidence

All four repositories were publicly accessible through GitHub's API during this audit. Their complete recursive file trees and READMEs were inspected, along with representative implementation files. These are source inspections, not claims that their applications, firmware, or test suites were run as part of this profile task.

### Machine Learning Hands-On

Repository: [khalidhasan7343/Machine-Learning-Hands-On](https://github.com/khalidhasan7343/Machine-Learning-Hands-On).

Verified notebook source:

- [Housing regression](https://github.com/khalidhasan7343/Machine-Learning-Hands-On/blob/main/Regression_Models_on_Housing_Dataset.ipynb): Linear Regression, Ridge, Lasso, MAE, MSE, and R².
- [Iris clustering](https://github.com/khalidhasan7343/Machine-Learning-Hands-On/blob/main/Clustering_%26_Dimensionality_Reduction_%28Dataset__Iris_Dataset%29.ipynb): K-Means, PCA, and pandas imports.
- [Fashion-MNIST](https://github.com/khalidhasan7343/Machine-Learning-Hands-On/blob/main/Fashion_MNIST_Dense_vs_CNN_Assignment.ipynb): dense and convolutional networks using TensorFlow/Keras, test evaluation, and a confusion matrix.

The file tree and [project README](https://github.com/khalidhasan7343/Machine-Learning-Hands-On#readme) also confirm the MNIST digit classifier, pandas exercises, and Jupyter notebook format. The collection is described as growing, without invented model scores or achievements.

### Algorithm Atlas

Repository: [khalidhasan7343/algorithm-atlas](https://github.com/khalidhasan7343/algorithm-atlas), verified under this exact owner.

The tree includes Python/C++ implementations and tests across the documented DSA categories. Representative source inspected: [merge sort](https://github.com/khalidhasan7343/algorithm-atlas/blob/main/dsa/sorting/merge-sort/python/solution.py) and [Dijkstra](https://github.com/khalidhasan7343/algorithm-atlas/blob/main/dsa/graph-algorithms/dijkstra/python/solution.py).

The [root README](https://github.com/khalidhasan7343/algorithm-atlas#readme), [Regression](https://github.com/khalidhasan7343/algorithm-atlas/blob/main/machine-learning/supervised-learning/regression/README.md), and [Classification](https://github.com/khalidhasan7343/algorithm-atlas/blob/main/machine-learning/supervised-learning/classification/README.md) document NumPy/Python-first ML implementations, testing, and an in-progress Regression review. V3 presents an actively developing educational collection and distinguishes implemented topics from its larger ML/AI roadmap. It makes no claims about a hosted visualization app, online IDE, AI agents, or hosted CI outcomes.

### Maze Mind

Repository: [khalidhasan7343/maze_mind](https://github.com/khalidhasan7343/maze_mind). The verified URL uses an underscore.

Implementation files inspected:

- [game/maze_gen.py](https://github.com/khalidhasan7343/maze_mind/blob/main/game/maze_gen.py): randomized DFS/backtracking generation and BFS-based distance queries.
- [game/astar.py](https://github.com/khalidhasan7343/maze_mind/blob/main/game/astar.py): A* search and hunter behavior.
- [data/logger.py](https://github.com/khalidhasan7343/maze_mind/blob/main/data/logger.py): SQLite round and snapshot storage.
- [ml/knn_skill.py](https://github.com/khalidhasan7343/maze_mind/blob/main/ml/knn_skill.py), [ml/kmeans_strategy.py](https://github.com/khalidhasan7343/maze_mind/blob/main/ml/kmeans_strategy.py), and [ml/logreg_winprob.py](https://github.com/khalidhasan7343/maze_mind/blob/main/ml/logreg_winprob.py): KNN, K-Means/PCA, and logistic-regression estimates.
- [requirements.txt](https://github.com/khalidhasan7343/maze_mind/blob/main/requirements.txt), the UI file tree, and [project README](https://github.com/khalidhasan7343/maze_mind#readme): Pygame CE and classic/isometric views.

The profile retains the project's distinction between bot-generated training results and human-player accuracy. It describes model functionality without claiming predictive reliability on people.

No committed screenshot, image, video, or standalone hosted demo was found in the original three featured repository trees, and none declared a homepage. Notebook outputs exist, but those entries use compact original cover art instead of presenting output plots as application screenshots.

### Microprocessor & Microcontroller Project / MediSmart

Repository: [khalidhasan7343/CSE_4326_-Microprosser---Micro-controller-_Project](https://github.com/khalidhasan7343/CSE_4326_-Microprosser---Micro-controller-_Project). The unusual spelling and punctuation in the repository URL are preserved exactly.

The official report title is **Autonomous Smart Dual Infusion and Patient Monitoring System Using ESP32**; the prototype is called **MediSmart**. The [report source](https://github.com/khalidhasan7343/CSE_4326_-Microprosser---Micro-controller-_Project/blob/main/CSE_4326_Project_Paper/conference_101719.tex) identifies it as a university team project and lists Md. Khalid Hasan among the authors. The profile uses the requested course-project heading and the shorter MediSmart name inside its cover and description.

Verified implementation and supporting materials:

| Area | Evidence and profile scope |
| :--- | :--- |
| Controller / language | [platformio.ini](https://github.com/khalidhasan7343/CSE_4326_-Microprosser---Micro-controller-_Project/blob/main/medismart/medismartVscode/platformio.ini) selects `espressif32`, `esp32dev`, and `espidf`; [main.c](https://github.com/khalidhasan7343/CSE_4326_-Microprosser---Micro-controller-_Project/blob/main/medismart/medismartVscode/src/main.c) is C firmware using ESP-IDF and FreeRTOS. The exact physical board variant is not established. |
| Sensors | MAX30102 optical readings over I²C, AD8232 ECG acquisition through ADC and lead-off GPIOs, and HX711 clock/data input from a load cell. The [hardware chapter](https://github.com/khalidhasan7343/CSE_4326_-Microprosser---Micro-controller-_Project/blob/main/CSE_4326_Project_Paper/chapters/03_implemented_hardware.tex) cross-references firmware, wiring, and photographs. |
| Actuators | Three LEDC PWM channels command saline, syringe, and oxygen-designated servos; a GPIO controls a buzzer. The saline servo model differs between wiring and code comments, so the profile names no specific servo model. |
| Architecture / protocols | The local sensor/control loop and a separate FreeRTOS network task connect acquisition, control rules, and telemetry. Firmware uses Wi-Fi, HTTP GET/PATCH with JSON, and SNTP time synchronization. MAX30102 uses I²C; HX711 uses its clock/data interface. No MQTT, Bluetooth, Raspberry Pi, Arduino, AI, or following-control feature is claimed. |
| Web layer | [doctor.html](https://github.com/khalidhasan7343/CSE_4326_-Microprosser---Micro-controller-_Project/blob/main/medismart/public/doctor.html) contains HTML/CSS/JavaScript, Firebase Realtime Database listeners, and settings writes. [patient.html](https://github.com/khalidhasan7343/CSE_4326_-Microprosser---Micro-controller-_Project/blob/main/medismart/public/patient.html) displays telemetry. The profile describes dashboards without asserting measured latency or verified access-control behavior. |
| Photos / diagrams | Six photographs in [Project_images](https://github.com/khalidhasan7343/CSE_4326_-Microprosser---Micro-controller-_Project/tree/main/Project_images), seven dashboard/database captures in [Website_images](https://github.com/khalidhasan7343/CSE_4326_-Microprosser---Micro-controller-_Project/tree/main/Website_images), and [sensor wiring](https://github.com/khalidhasan7343/CSE_4326_-Microprosser---Micro-controller-_Project/blob/main/medismart/medismart_sensor_wiring.png) and [actuator wiring](https://github.com/khalidhasan7343/CSE_4326_-Microprosser---Micro-controller-_Project/blob/main/medismart/medismart_power_actuators_wiring.png) images are present. A prototype photograph and the sensor diagram were inspected visually. |

The [report README](https://github.com/khalidhasan7343/CSE_4326_-Microprosser---Micro-controller-_Project/blob/main/CSE_4326_Project_Paper/README.md) and [results chapter](https://github.com/khalidhasan7343/CSE_4326_-Microprosser---Micro-controller-_Project/blob/main/CSE_4326_Project_Paper/chapters/04_results.tex) distinguish captured states and source-derived behavior from calibrated measurements. V3 calls this a prototype and adds no sensor-accuracy, delivered-volume, latency, clinical-performance, or other quantitative achievement claims.

The YouTube URL remains a placeholder in [project_metadata.tex](https://github.com/khalidhasan7343/CSE_4326_-Microprosser---Micro-controller-_Project/blob/main/CSE_4326_Project_Paper/project_metadata.tex); the repository homepage is unset and no video file was found in its tree. The entry links its real repository, prototype-photo directory, and technical report. Its 600×170 monochrome cover matches the other covers, while the abstract processor/pin/traces motif is explicitly conceptual. Original color evidence remains available through those links.

The earlier [Basic-Project](https://github.com/khalidhasan7343/Basic-Project) and [dbms](https://github.com/khalidhasan7343/dbms) destinations were also confirmed public. Contact links and claimed toolkit experience come from the original README. PyTorch, RAG, Next.js, Docker, and the expanded full-stack stack remain explicitly under learning.

## Validation and limits

Completed checks:

- XML parsing of all 15 SVG files; SVG roots, viewBoxes, descriptions, and local references checked.
- README submitted to GitHub's Markdown API in GFM mode; all seven `<picture>` elements survived rendering.
- That rendered HTML was viewed locally in installed headless Chrome with a GitHub-like stylesheet at **1000px and 375px**, in both light and dark modes. All seven local images loaded, correct theme variants were selected, and neither the page nor the toolkit table required horizontal scrolling. All four covers retain the same aspect ratio; desktop and phone screenshots, including the fourth project and expanded map, were inspected.
- Browser SVG text bounds checked across all 15 assets, with no text outside the viewBox.
- Hero timeline sampled throughout the 14.4-second cycle: one active message, no overlap or gap, and cursor positions matched reveal widths. Initial, partially revealed, and static screenshots were inspected.
- Reduced-motion hero text and hidden avatar signals checked in Chrome. Removing SMIL animation elements left the complete first message visible.
- Featured and retained project URLs confirmed public through GitHub's API.
- Final local asset-reference, accessibility, palette, text-contrast, and diff checks completed without errors.

Preview tooling, downloaded audit sources, screenshots, and browser data were kept in the system temporary directory, outside this repository. No preview server, JavaScript dependency, or test harness is part of the delivered profile.

This is **not** a visual test of the published GitHub profile or GitHub's image proxy. GitHub controls final spacing, sanitization, caching, and user theme selection. A production check should follow publication: inspect the profile in both themes and with reduced motion enabled, and open the four project covers.

No manual GitHub configuration is required for this existing username-matched profile repository. Publishing the files on its default branch makes the relative assets available. No commits, pushes, pull requests, or repository settings changes were made by this task.
