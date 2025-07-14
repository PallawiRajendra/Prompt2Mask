# 🗺️ Prompt2Mask

**Prompt2Mask** is an AI-powered visual annotation tool for **map and road object labeling**.  
Built on top of [Grounded-Segment-Anything](https://github.com/IDEA-Research/Grounded-Segment-Anything), it enables **natural language-driven segmentation** and delivers **clean, structured polygon outputs** with **valuable statistics** — so you can save time, effort, and labeling costs.

---

## 💎 Why Use Prompt2Mask?

While Segment Anything (SAM) only returns **binary masks**, **Prompt2Mask** goes further:

✅ We convert SAM masks to **polygonal annotations**  
✅ We automatically filter and clean the masks  
✅ We provide **statistics per class**, **per image**, and **per session**  
✅ You get a ready-to-use structured output for ML pipelines, annotation tools, and GIS systems

✨ **No post-editing required. It's annotation made effortless.**

---

## 🚀 What is Prompt2Mask?

**Prompt2Mask** enables fast, zero-shot annotation of **road and map features** using simple text prompts like `"asphalt"`, `"pothole"`, `"zebra crossing"`, or `"traffic sign"`.  
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
git clone https://github.com/PallawiRajendra/Prompt2Mask.git
cd Prompt2Mask
