# Detecção de Pessoas em Imagens Térmicas

Este repositório contém um projeto de detecção de pessoas em imagens térmicas usando YOLOv8. O projeto foi desenvolvido pelos SOS IA Voluntários, com base em dados do Roboflow Universe Projects.

## Instalação

Antes de executar o código, certifique-se de instalar todas as dependências necessárias. Você pode instalar as bibliotecas necessárias executando:

```bash
pip install ultralytics==8.0.196 roboflow
```

## Uso

1. Clone o repositório.

```bash
git clone https://github.com/seu-usuario/People-Detection-Thermal.git
cd People-Detection-Thermal
```

2. Execute o script `people_detection.py` para realizar a detecção de pessoas em imagens térmicas.

```bash
python people_detection.py
```

3. Confira o arquivo `images.zip` gerado no diretório raiz, que contém as imagens com as detecções feitas pelo modelo.

## Arquivo de Configuração

Certifique-se de que o arquivo `data.yaml` contém os caminhos corretos para as imagens de treino, teste e validação.

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir um pull request ou reportar problemas no sistema de issues.

## Licença

Este projeto é licenciado sob a [MIT License](LICENSE).

Desenvolvido por [SOS IA Voluntários](https://github.com/sos-ia-voluntarios).
