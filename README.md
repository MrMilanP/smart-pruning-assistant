# Smart Pruning Assistant – Prior Art Disclosure

Prior art disclosure of an AR-based Android app concept for pruning fruit trees using machine learning.

**Author**: Milan Petrović  
**Initial concept date**: March 2025  
**Published as prior art**: April 18, 2025  
**License**: Apache 2.0  

---

## 🔍 Idea Summary

This project discloses a concept for a mobile application designed to assist users in pruning fruit trees using **machine learning** and **augmented reality (AR)**.

While walking around a tree (e.g., apple tree), the user points their smartphone camera at the branches.  
The app uses ML to analyze the tree's structure and overlays **suggested cutting lines** directly on the screen.

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

## 📜 Claims-style Breakdown (for patent clarity)

The following functional elements are disclosed as prior art:

1. A mobile system for assisting pruning using an **on-device camera** and **ML-based analysis**.
2. Real-time **overlay of cut suggestions** on live video using AR.
3. Classification of branch geometry using **shape models** (e.g., “vase”, “conical”).
4. Optional generation of a **3D digital model** from multiple 2D images for enhanced analysis.
5. No dependence on specialized hardware (e.g., depth sensors or LIDAR).
6. System operable **without external servers** (fully on-device possible).
7. Support for educational or assistive feedback via visual annotations.

---

## 🔓 Legal Notice

This repository and all its contents are published as **defensive prior art**.  
The author **explicitly disclaims any exclusive rights** over the general method or system, including any implementation involving:

- 2D or 3D image capture,
- mobile device-based pruning guidance,
- ML-based feature analysis,
- augmented reality rendering.

Any patent filed after this disclosure attempting to claim such features must **account for this public prior art**.

---

## 🌍 Open for All

This idea is published under the **Apache 2.0 License**, which:

- allows unrestricted use, redistribution, and modification;
- includes a **patent retaliation clause** protecting the community;
- enables both commercial and non-commercial reuse.

---

## 🆔 Archival

This disclosure will be permanently archived and timestamped via a public repository.

*DOI to be provided after final review.*


---
