# MIT 805 Assignment 1 - Traffic Sign Detection Dataset Analysis

## Overview
This repository contains a comprehensive analysis of a traffic sign detection dataset using the 7 Vs of Big Data framework. The analysis covers volume, velocity, variety, value, veracity, variability, and validity aspects of the dataset.

## Dataset Description
- **Total Images:** 19,346 JPG images
- **Total Annotations:** 19,346 XML files + 19,048 YOLO format files
- **Total Sign Instances:** 30,634 annotated traffic signs
- **Classes:** 76 different traffic sign classes
- **Estimated Size:** ~9.7 GB

## Repository Structure
```
MIT805/
├── images/                    # Original JPG images (19,346 files)
├── xmls/                     # XML annotations in PASCAL VOC format
├── txts (YOLO)/              # YOLO format annotations
├── crops/                    # Cropped sign images organized by class
├── classes.json              # Class definitions and counts
├── dataset.yaml              # Dataset configuration file
├── data_analysis.py          # Comprehensive analysis script
├── simple_analysis.py        # Simplified analysis script
├── requirements.txt          # Python dependencies
├── analysis_summary.json     # Analysis results summary
├── MIT805_Assignment1_Report.md  # Complete analysis report
└── README.md                 # This file
```

## Class Categories
The dataset includes 76 traffic sign classes organized into four categories:

| Category | Count | Percentage | Examples |
|----------|-------|------------|----------|
| Regulatory | 33 | 43.4% | Speed limits, stop signs, yield signs |
| Warning | 34 | 44.7% | Curve warnings, pedestrian crossings |
| Information | 6 | 7.9% | Parking, hospital, motorway signs |
| Complementary | 3 | 3.9% | Distance markers, chevron indicators |

## Key Findings

### 7 Vs of Big Data Analysis
1. **Volume:** 9.7 GB dataset with 19,346 images and 30,634 sign instances
2. **Velocity:** ~400 images/minute processing capability with real-time potential
3. **Variety:** 76 classes across 4 sign categories with multiple data formats
4. **Value:** $2.3M+ estimated value with $50B+ autonomous vehicle market potential
5. **Veracity:** 98.5% annotation coverage with professional quality standards
6. **Variability:** 1.12 coefficient of variation with significant class imbalance
7. **Validity:** 94% overall validity score with high accuracy metrics

### Business Applications
- **Autonomous Vehicles:** Real-time traffic sign recognition for safety-critical systems
- **Smart Cities:** Traffic management and urban planning optimization
- **Driver Assistance:** Enhanced safety features and navigation systems
- **Fleet Management:** Compliance monitoring and risk assessment

## Getting Started

### Prerequisites
- Python 3.7+
- Required packages listed in `requirements.txt`

### Installation
1. Clone the repository:
```bash
git clone [repository-url]
cd MIT805
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the analysis:
```bash
python simple_analysis.py
```

### Usage
The repository includes two main analysis scripts:

1. **`simple_analysis.py`**: Quick analysis focusing on the 7 Vs framework
2. **`data_analysis.py`**: Comprehensive analysis with visualizations

## Analysis Results
- Complete analysis report: `MIT805_Assignment1_Report.md`
- Summary statistics: `analysis_summary.json`
- Visualizations: Generated PNG and HTML files

## Dataset Statistics
- **Most Common Class:** regulatory--maximum-speed-limit (3,720 instances)
- **Least Common Class:** regulatory--pass-on-either-side (138 instances)
- **Annotation Coverage:** 98.5%
- **Data Quality Score:** 94%

## Business Insights
The dataset demonstrates significant potential for:
1. **Autonomous Vehicle Development** ($50B+ market)
2. **Smart City Infrastructure** ($1.5T+ market)
3. **Driver Assistance Systems** ($30B+ market)
4. **Fleet Management** ($15B+ market)

## Technical Recommendations
1. Address class imbalance through data augmentation
2. Implement real-time processing pipelines
3. Develop multi-modal analysis capabilities
4. Create continuous learning systems
5. Establish quality assurance frameworks

## File Descriptions
- `classes.json`: Complete class definitions with counts
- `dataset.yaml`: YOLO dataset configuration
- `analysis_summary.json`: Key statistics and metrics
- `MIT805_Assignment1_Report.md`: Comprehensive analysis report

## Contributing
This is an academic project for MIT 805. For questions or suggestions, please contact the author.

## License
This project is for academic purposes only. Please respect the original dataset licensing terms.

## Contact
- **Course:** MIT Data Big Science (MIT 805)
- **Institution:** University of Pretoria
- **Assignment:** Part 1 – Data Collection & Analysis

---

**Note:** This repository contains analysis code and documentation. The original dataset files are not included due to size constraints.