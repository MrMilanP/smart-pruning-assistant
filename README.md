# Smart Pruning Assistant – Prior Art Disclosure

Prior art disclosure of an AR-based Android app concept for pruning fruit trees using machine learning.

**Author**: Milan Petrović  
**Initial concept date**: March 2025  
**Published as prior art**: April 21, 2025  
**License**: Apache 2.0  

---

## 🔍 Idea Summary

This project discloses a concept for a mobile application designed to assist users in pruning fruit trees using **machine learning** and **augmented reality (AR)**.

While walking around a tree (e.g., apple tree), the user points their smartphone camera at the branches.  
The app uses ML to analyze the tree’s structure and overlays **suggested cutting lines** directly on the screen.

The core idea was independently conceived by the author in Serbia, without any prior knowledge of similar patent filings or commercial systems, and is now published to:

- prevent exclusive patent claims over this general idea,  
- support open development of accessible pruning tools,  
- allow anyone to build similar systems freely and legally.

---

## 💡 Technical Flow (Concept Overview)

### 2D-Only Flow
1. User walks around the tree holding a phone.  
2. Camera captures a sequence of **2D images**.  
3. ML model (trained on labeled datasets) analyzes branch angles and form.  
4. Suggested cut lines are calculated and overlaid live on screen.  
5. **No 3D model** is required.

### Optional 3D Extension (Included in Prior Art)
1. Multiple 2D images are optionally used to reconstruct a 3D structure.  
2. ML model identifies key branch features (e.g., bifurcations, canes).  
3. Cut instructions are rendered over the 3D structure or camera feed.  
4. AR rendering synchronizes overlay with real-world visuals.

---

## 🔧 Extended Technology Disclosure

This disclosure **explicitly includes** all of the following technologies and configurations:

### 📲 Device Types & Interfaces
- Smartphone-based solutions (Android/iOS)  
- Tablet or AR-glasses implementations  
- Screen-based AR overlays and lens-integrated displays  

### 🖼️ Image Capture & Spatial Data
- 2D image capture from single or multiple angles  
- Multi-view capture for **3D reconstruction** (photogrammetry, SLAM, TSDF)  
- Optional use of:  
  - **RGB-D**, **LIDAR**, **ToF**, **Depth API**  
  - **Infrared**, **accelerometer**, **gyroscope**, **compass**  

### 🤖 ML & Processing Architectures
- On-device inference (e.g., TensorFlow Lite)  
- Cloud/edge-based remote processing  
- Hybrid workflows (local capture + server inference)  
- Human-in-the-loop expert interaction  

### 🧠 Algorithm Types
- Rule-based pruning logic (heuristics)  
- Neural networks (CNN, GNN, ViT)  
- Geometry-based decisions (angle, height, bifurcation analysis)  
- Shape classification (vase, conical, etc.)  

### 🪓 Pruning Guidance Methods
- Cut-line overlays (live video or 3D render)  
- Highlighted branches (color masks, labels)  
- Voice or text instructions  
- Pre-recorded/dynamic video clips or diagrams  

### 🌐 Architecture & Modularity
- Fully offline (on-device only)  
- Connected mode with cloud fallback  
- Modular blocks:  
  - Scanner (SLAM/Depth)  
  - Segmenter (ML or heuristic)  
  - Evaluator (pruning logic)  
  - Visualizer (AR overlay)  
  - Interaction (voice, UI, remote)  
  - Feedback loop (cut detection, scene update)

### 📊 Use-case Coverage
- Visual pruning guidance while physically walking around a tree  
- Live adjustment when a branch is cut (feedback loop)  
- Educational usage in schools or training settings  
- Real-time expert feedback or collaborative pruning  
- Data export (e.g., CSV, PDF) and history tracking  
- Support for various plants: fruit trees, vines, ornamental shrubs

---

## 📜 Claims-style Breakdown (for patent clarity)

The following functional elements are disclosed as prior art:

1. A mobile system for assisting pruning using an **on-device camera** and **ML-based analysis**.  
2. Real-time **overlay of cut suggestions** on live video using AR.  
3. Classification of branch geometry using **shape models** (e.g., “vase”, “conical”).  
4. Optional generation of a **3D digital model** from multiple 2D images.  
5. Use of **depth/spatial sensors** (LIDAR, RGB-D, ToF).  
6. Support for **remote inference** or **on-device-only** variants.  
7. Multi-modal feedback: **visual overlays**, **annotations**, **AR guidance**, **remote video sessions**.  
8. Detection of branch removal and dynamic update of AR scene.

---

## 🔓 Legal Notice

This repository and all its contents are published as **defensive prior art**.  
The author **explicitly disclaims** any exclusive rights over the general method or system, including any implementation involving:

- 2D or 3D image capture  
- Mobile device-based pruning guidance  
- Machine learning for decision logic  
- AR rendering of cut guidance  
- Remote human-assisted or automated analysis  
- Use of sensors for depth, orientation or spectral data  
- Feedback mechanisms for detecting physical pruning events

Any patent filed after this disclosure attempting to claim such features must **account for this public prior art**.

---

## 🌍 Open for All

This idea is published under the **Apache 2.0 License**, which:

- allows unrestricted use, redistribution, and modification  
- includes a **patent retaliation clause** protecting the community  
- enables both commercial and non-commercial reuse

---

## 🌝 Archival

This disclosure will be permanently archived and timestamped via a public repository.  
*DOI to be added after final Zenodo deposit.*

---
