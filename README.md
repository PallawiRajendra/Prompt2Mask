# 🛣️ Prompt2Poly — for Road Object Segmentation

**Prompt2Poly** is an AI-powered annotation tool that converts **natural language prompts** into **precise polygon masks** for **road and map features**.  
Built on top of [Grounded-Segment-Anything](https://github.com/IDEA-Research/Grounded-Segment-Anything), it enables **natural language-driven segmentation** and delivers **clean, structured polygon outputs** with **valuable statistics** — so you can save time, effort, and labeling costs.

---

## 💎 Why Use Prompt2Poly?

While Segment Anything (SAM) only returns **binary masks**, **Prompt2Poly** goes further:

✅ Converts SAM masks into **polygonal annotations**  
✅ Filters and cleans masks automatically  
✅ Provides **statistics per class**, **per image**, and **per session**  
✅ Outputs ready-to-use formats for ML pipelines, annotation tools, and GIS systems

✨ **No post-editing required. It's annotation made effortless.**

---

## 🚀 What is Prompt2Poly?

**Prompt2Poly** enables fast, zero-shot annotation of **road and map features** using simple text prompts like `"asphalt"`, `"pothole"`, `"zebra crossing"`, or `"traffic sign"`.  
It's perfect for:

- 🛣️ Autonomous Driving
- 🗺️ Mapmaking & HD Maps
- 🧭 GIS Applications
- 🚧 Road Maintenance & Urban Mobility

---

## 🎯 Key Features

- ✅ **Zero-shot segmentation** with natural language prompts
- 📐 **Polygons instead of masks** — perfect for annotation tools
- 📊 **Detailed stats**: object counts, areas, classes, and more
- 💾 Export to COCO-style JSON, PNG masks, or shapefiles
- 🧠 Optimized for **road and map-related object classes**
- 🛠️ Modular post-processing script to adapt to your use case

---
## 🛤️ Roadmap

- [x] **Prompt-based segmentation & mask saving**
- [x] **Smart polygon selection for road surface** with **GUI interface** (powered by post-processing script)
- [x] **CSV export** of road surface segmentation results
- [ ] **Pole segmentation** — *In Progress*
- [ ] GUI support for more object classes (e.g., poles, sidewalks)
- [ ] Multi-object prompt support (e.g., "road + pole + sidewalk")
- [ ] Export masks to COCO, YOLO, or GIS-compatible formats
- [ ] Web UI for end-to-end annotation
- [ ] Integration with real-world datasets (e.g., Mapillary, OpenStreetCam)

---

## 🧱 Label Objects Like:

- **Road Surface**: `asphalt`, `concrete`, `gravel`, `dirt road`, `mud`, `cobblestone`
- **Markings**: `lane markings`, `zebra crossing`, `bike lane marking`, `arrow markings`, `stop line`
- **Damage & Irregularities**: `pothole`, `crack`, `manhole`, `speed bump`, `construction zone`
- **Signs & Poles**: `traffic sign`, `stop sign`, `direction board`, `traffic light`, `roadside pole`, `street lamp`
- **Boundaries & Edges**: `curb`, `sidewalk`, `footpath`, `median strip`, `barrier`, `guard rail`
- **Street Elements**: `drain`, `bus stop`, `bollard`, `crosswalk`, `reflector`, `speed limit sign`
- **Others**: `pedestrian`, `bicycle`, `car`, `truck`, `building`, `tree`, `vegetation`

🔧 Add your own object prompts easily!

---

## 🧪 Quick Start

```bash
git clone https://github.com/PallawiRajendra/Prompt2Poly.git
cd Prompt2Poly
