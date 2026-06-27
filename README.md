# Detector de Pessoas com Visão Computacional

Este projeto consiste em um sistema inteligente capaz de analisar uma imagem capturada e detectar automaticamente a presença de figuras humanas.

## Como Funciona
O sistema recebe uma imagem e utiliza uma inteligência artificial própria para escanear o cenário. Ao reconhecer o padrão de um corpo humano, ele gera automaticamente caixas delimitadoras (*bounding boxes*) ao redor das pessoas identificadas.

Para isso, eu treinei um modelo utilizando aprendizado de máquina para ser capaz de identificar pessoas na imagem, e apenas apontar isso ao ter 90% de certeza que se trata de um ser humano.

## Tecnologias e Ferramentas Utilizadas
* **Python:** Linguagem base para a construção do script e lógica do sistema.
* **OpenCV:** Biblioteca utilizada para a manipulação da imagem, leitura dos arquivos e desenho dos retângulos de detecção na tela.
* **Inteligência Artificial:** Modelo de IA treinado especificamente para mapear, reconhecer e validar as características de uma figura humana.
* **Ferramentas Correlatas:** Bibliotecas de apoio para processamento matemático e organização dos dados da imagem.

---
Desenvolvido com Python, OpenCV e Inteligência Artificial.
