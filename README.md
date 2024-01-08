## Computational Vision - Perceptual Hash Algorithms Evaluation
> 5 types of Perceptual Hash Algorithms were selected in this Research: AverageHash, Crop-ResistanceHash, DifferenceHash, PerceptualHash and WaveletHash

### 💻 Image Databases Description
> 5 image databases were selected. All bases have an Original image and the variations of the Original image. The objective of the experiment is to identify that both images, Original and Variations, if they have a relationship determined by the Perceptual Hash. All image databases are available in [this repository](https://github.com/jrafa1607/Evaluation-of-Perceptual-Hash-Algorithms/tree/main/ImageDatabase)

####  LennaDatabase (20 Images) And WashingtonDatabase (07 Images) - Avaliable in: [<b> Images from Digital Image Processing, 3rd ed, by Gonzalez and Woods.</b>](https://imageprocessingplace.com/root_files_V3/image_databases.htm)
- [x] Lenna Database (20 Images)
- [x] Washington Database (07 Images)

#### PalaceDatabase And Mountain Database - Avaliable in: [<b> SUID: Synthetic Underwater Image Dataset.</b>](https://ieee-dataport.org/open-access/suid-synthetic-underwater-image-dataset)
- [x] PalaceDatabase (31 Images)
- [x] MountainDatabase (30 Images)

#### ParkDatabase - Avaliable in: [<b> CoMoFoD - Image Database for Copy-Move Forgery Detection.</b>](https://www.vcl.fer.hr/comofod/download.html)
- [x] ParkDatabase (11 Images)

### 📊📝 About the Computational Vision Automations with Python
- [x] <b>Perceptual Hashing Evaluation:</b> Calculate the 5 types of Perceptual Hashing of the Original Image: AverageHash, Crop-ResistanceHash, DifferenceHash, PerceptualHash and WaveletHash. After that, calculate the Hamming Distance between the 5 types of Perceptual Hashing and the Original Image.

- [x] <b>Distance Calc (Euclidean & Manhattan): </b> Calculate the Euclidean & Manhattan Distances between the results of Hamming Distance in the Perceptual Hashing Evaluation

### 📈 Additional Info about the Experiment
- [x] The folder Dados has the Hamming Distances Results Values.
- [x] The folder ImageDatabases has all the images used in this experiment.
- [x] The folder Results has all info about Conventional Hash (MD5, SHA-1 and SHA-256), Prceptual Hashing and Hamming Distances Calcs.