## 📊📝 Evaluation of Perceptual Hash Algorithms
> This repository contains experiments focused on evaluating various **Perceptual Hashing** algorithms by analyzing their Hamming Distance values across different image databases. 
> The objective is to understand how these algorithms perform when identifying image similarities and robustness.
> About **Perceptual Hash**, is a type of Hashing that generates a fingerprint for an image that is robust against minor modifications (such as scaling or brightness changes).
> This project calculates and compares the Euclidean and Manhattan distances for several hashing algorithms to determine their effectiveness.

### Experiments & Analysis
The included notebook performs the following:
1.  **Dataset Processing**: Loads and analyzes five distinct image databases (Lenna, Mountain, Palace, Park, and Washington).
2.  **Distance Calculation**: Computes distances for:
- [x] Average Hashing,
- [x] Perceptual Hashing,
- [x] Difference Hashing,
- [x] Wavelet Hashing,
- [x] Crop-Resistant Hashing
3.  **Comparative Metrics**: Calculates **Euclidean** and **Manhattan** distances to measure the similarity deviation from an original image.

---

### Image Databases Included
| Database | Image Count | Avaliable in |
| :--- | :--- | :--- |
| **Lenna** | 20 | [<b> Images from Digital Image Processing, 3rd ed, by Gonzalez and Woods.</b>](https://imageprocessingplace.com/root_files_V3/image_databases.htm) |
| **Mountain** | 30 | [<b> Images from Digital Image Processing, 3rd ed, by Gonzalez and Woods.</b>](https://imageprocessingplace.com/root_files_V3/image_databases.htm) |
| **Palace** | 31 | [<b> SUID: Synthetic Underwater Image Dataset.</b>](https://ieee-dataport.org/open-access/suid-synthetic-underwater-image-dataset) |
| **Park** | 11 | [<b> SUID: Synthetic Underwater Image Dataset.</b>](https://ieee-dataport.org/open-access/suid-synthetic-underwater-image-dataset) |
| **Washington** | 7 | [<b> CoMoFoD - Image Database for Copy-Move Forgery Detection.</b>](https://www.vcl.fer.hr/comofod/download.html) |

---

### Usage
To run the analysis:
1.  Ensure you have the required libraries installed:
    ```bash
    pip install matplotlib seaborn pandas numpy scipy
    ```
2.  Run the provided notebook to load the datasets.
3.  Select the desired database (1-5) when prompted to initiate distance calculations and graph generation.

---

### Visualizations
The script generates plots to visualize the Hamming Distance variations across the different hashing algorithms, allowing for quick identification of which algorithms produce lower distance values (indicating higher perceptual similarity).

---

#### 🔒🛠️ Intellectual Property (IP) Protection ( License, Restrictions, and Copyright )

All source code, documentation, and research methodologies contained in this repository are the exclusive Intellectual Property of the author. All rights reserved. Use of this content for academic or professional purposes must include proper citation and attribution to the original research.

> **Copyright © 2026 João Rafael Gonçalves Evangelista.**
