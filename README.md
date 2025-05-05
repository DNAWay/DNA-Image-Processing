DNA Image Processing Pipeline

This repository provides Python scripts for processing DNA gel electrophoresis images, detecting lanes and bands, and estimating fragment sizes using OpenCV and NumPy.

├── data/                      # Input images (e.g., gel photographs)
│   └── gel1.jpg
├── output/                    # Processed images and results
│   ├── gel1_lanes.png
│   └── gel1_bands.csv
├── dna_image_processor.py    # Main image processing script
└── README.md                  # This file

Features

Lane Detection: Identify vertical lanes in gel images.

Band Extraction: Detect horizontal bands within each lane.

Size Estimation: Estimate fragment sizes based on a DNA ladder lane.

Visualization: Output annotated images showing lanes and band positions.

Output: CSV file with band positions and estimated sizes.
