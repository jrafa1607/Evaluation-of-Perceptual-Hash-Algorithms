## Computational Vision Experiment about Perceptual Hash Algorithms Evaluation
> In this repository have the files used for the development of Perceptual Hash Algorithms Evaluation Research. 6 types of Perceptual Hash Algorithms were selected in this Research: AverageHash, Crop-ResistanceHash, DifferenceHash, HSV-ColorHash, PerceptualHash and WaveletHash

### 💻 Image Databases Description
> For the development of the experiment, 5 image databases were selected. All bases have an Original image and the variations of the Original image. The objective of the experiment is to identify that both images, Original and Variations, if they have a relationship determined by the Perceptual Hash. All image databases are available in [this repository](https://github.com/jrafa1607/Evaluation-of-Perceptual-Hash-Algorithms/tree/main/ImageDatabase)

####  LennaDatabase And WashingtonDatabase (Avaliable in: [<b> Images from Digital Image Processing, 3rd ed, by Gonzalez and Woods.</b>](https://imageprocessingplace.com/root_files_V3/image_databases.htm))
- [x] Lenna Database (20 Images)
- [x] Washington Database (07 Images)

#### PalaceDatabase e MountainDatabase
As Bases PalaceDatabase e MountainDatabase foram selecionadas na Base de Imagens: <b> SUID: Synthetic Underwater Image Dataset.</b> Disponível no Link: https://ieee-dataport.org/open-access/suid-synthetic-underwater-image-dataset
- [x] PalaceDatabase (31 Imagens)
- [x] MountainDatabase (30 Imagens)

#### ParkDatabase
A Base ParkDatabase foi selecionada na Base de Imagens: <b> CoMoFoD - Image Database for Copy-Move Forgery Detection.</b> Disponível no Link: https://www.vcl.fer.hr/comofod/download.html
- [x] ParkDatabase (11 Imagens)


## Sobre as Automações
### 📊📝 Automações para Visão Computacional com Python
Para realizar os experimentos, foram desenvolvidos duas automações em Python:
- [x] <b>Perceptual Hashing Evaluation:</b> Automação responsável por Calcular a distância de Hamming entre os 6 Tipos de Hash Perceptivo e a Imagem Original
- [x] <b>Distance Calc (Euclidean & Manhattan):</b> Automação responsável por Cálcular a distância Eucliana e Manhattan dos Valores de Hamming obtidos pela primeira automação.


### 📈 Informações sobre o Experimento
- A pasta Dados contém o valor das distâncias de Hamming entre o Hash Perceptivo e a Imagem Original.
- A pasta Resultados contém os resultados do Hash Convencional, do Hash Perceptivo e dos cálculos de distância.
- A pasta Anexos contém as imagens com as fórmulas e anotações sobre as Distâncias de Hamming, Euclidiana, Manhattan e Minkovski.