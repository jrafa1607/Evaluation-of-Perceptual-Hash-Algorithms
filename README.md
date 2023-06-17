# Avaliação de Algoritmos para Hash Perceptivo
> Nesse repositório, estão armazenadas os arquivos utilizados para o desenvolvimento da pesquisa de avaliação de Algoritmos para Hash Perceptivo. Foram selecionados 6 tipos de Algoritmos de Hash Perceptivos: AverageHash, Crop-ResistanceHash, DifferenceHash, HSV-ColorHash, PerceptualHash e WaveletHash

## Experimento
### 💻 Base de Imagens para os Experimentos

<p align="center">
  <img src="Anexos/image_database.jpeg" alt="Cloud Computing">
</p>

Para o desenvolvimento do experimento, foi utilizado 5 bases de Imagens.
Todas as bases possuem uma imagem Original e outras variações da imagem Original.
O Objetivo do experimento é identificar que ambas as imagens, Original e Variações, possuem uma relação determinada pelo Hash Perceptivo.
Todas as bases de imagens estão disponíveis [nesse repositório:](https://github.com/jrafa1607/Evaluation-of-Perceptual-Hash-Algorithms/tree/main/ImageDatabase)

####  LennaDatabase e WashingtonDatabase
As Bases LennaDatabase e WashingtonDatabase foram selecionadas da publicação: <b> Images from Digital Image Processing, 3rd ed, by Gonzalez and Woods.</b> Disponível no Link: https://imageprocessingplace.com/root_files_V3/image_databases.htm
- [x] Lenna Database (21 Imagens)
- [x] Washington Database (07 Imagens)

#### PalaceDatabase e MountainDatabase
As Bases PalaceDatabase e MountainDatabase foram selecionadas na Base de Imagens: <b> SUID: Synthetic Underwater Image Dataset.</b> Disponível no Link: https://ieee-dataport.org/open-access/suid-synthetic-underwater-image-dataset
- [x] PalaceDatabase (31 Imagens)
- [x] MountainDatabase (30 Imagens)

#### ParkDatabase
A Base ParkDatabase foi selecionada na Base de Imagens: <b> CoMoFoD - Image Database for Copy-Move Forgery Detection.</b> Disponível no Link: https://www.vcl.fer.hr/comofod/download.html
- [x] ParkDatabase (11 Imagens)



## Visão Computacional
### 📊📝 Automações de Visão Computacional com Python
> Para realizar os experimentos, foram desenvolvidos duas automações em Python:
- 





### 📈 Outras informações sobre o Experimento
- A pasta Dados contém o valor das distâncias de Hamming entre o Hash Perceptivo de Cada Imagem nas Bases selecionadas e a Imagem Original.
- A pasta Distances contém as imagens com as fórmulas e anotações sobre as Distâncias de Hamming, Euclidiana, Manhattan e Minkovski.
- A pasta Resultados contém os resultados do Hash Convencional, do Hash Perceptivo e dos cálculos de distância.


Lembrando que o arquivo <b>contas</b> deve ter o nome das contas do seu ambiente AWS, o mesmo nome configurado no arquivo <b>Config</b>. Por exemplo:

#### Arquivo Contas
`<AccountName-Num1>`<br>
`<AccountName-Num2>`

#### Arquivo Config
`[profile <AccountName-Num1>]`<br>
`sso_start_url = URL`<br>
`sso_region = <region>`<br>
`sso_account_id=<ID Number>`<br>
`sso_role_name = <PermissionSet>`<br>
`output = json`<br>

`[profile <AccountName-Num2>]`<br>
`sso_start_url = URL`<br>
`sso_region = <region>`<br>
`sso_account_id=<ID Number>`<br>
`sso_role_name = <PermissionSet>`<br>
`output = json`<br>