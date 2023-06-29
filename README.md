# Avaliação de Algoritmos para Hash Perceptivo
> Nesse repositório, estão armazenadas os arquivos utilizados para o desenvolvimento da pesquisa de avaliação de Algoritmos para Hash Perceptivo. Foram selecionados 6 tipos de Algoritmos de Hash Perceptivos: AverageHash, Crop-ResistanceHash, DifferenceHash, HSV-ColorHash, PerceptualHash e WaveletHash

## Experimento de Visão Computacional
### 💻 Base de Imagens para os Experimentos

<p align="center">
  <img src="Anexos/image_database.jpeg" alt="Cloud Computing">
</p>

Para o desenvolvimento do experimento, foram selecionadas 5 bases de Imagens.
Todas as bases possuem uma imagem Original e outras variações da imagem Original.
O Objetivo do experimento é identificar que ambas as imagens, Original e Variações, possuem uma relação determinada pelo Hash Perceptivo.
Todas as bases de imagens estão disponíveis [nesse repositório:](https://github.com/jrafa1607/Evaluation-of-Perceptual-Hash-Algorithms/tree/main/ImageDatabase)

####  LennaDatabase e WashingtonDatabase
As Bases LennaDatabase e WashingtonDatabase foram selecionadas da publicação: <b> Images from Digital Image Processing, 3rd ed, by Gonzalez and Woods.</b> Disponível no Link: https://imageprocessingplace.com/root_files_V3/image_databases.htm
- [x] Lenna Database (20 Imagens)
- [x] Washington Database (07 Imagens)

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