# Avaliação de Algoritmos para Hash Perceptivo

> Nesse repositório, estão armazenadas os arquivos utilizados para o desenvolvimento da pesquisa de avaliação de Algoritmos para Hash Perceptivo. Foram selecionados 6 tipos de Algoritmos de Hash Perceptivos: AverageHash, Crop-ResistanceHash, DifferenceHash, HSV-ColorHash, PerceptualHash e WaveletHash


## Experimento
### 💻 Base de Imagens para os Experimentos

Para o desenvolvimento do experimento, foi utilizado 6 bases de Imagens:



Para executar as automações desenvolvidas para ambientes AWS, é necessário:
- [x] [Instalação e Configuração do AWS CLI](https://aws.amazon.com/pt/cli/)
- [x] Configurar no Diretório .AWS os arquivos `Config` e `Credentials`
- [x] Copiar as automações disponíveis neste repositório para um diretório na home do seu usuário.
- [x] Copiar para dentro do diretório recém-criado, o arquivo chamado "contas"

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