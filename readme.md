# Medical Image Control

## Sobre o projeto

O **Medical Image Control** é uma aplicação desenvolvida em [Electron](https://www.electronjs.org/) que empacota e executa os builds de duas aplicações essenciais para o processamento e visualização de arquivos DICOM:

1. **API DICOM Converter** – Uma API responsável por consumir arquivos DICOM e convertê-los para o formato DICOMweb, permitindo uma integração mais eficiente com visualizadores e sistemas de PACS modernos.

2. **OHIF Viewer** – Um visualizador open-source para dados DICOM, amplamente utilizado na comunidade médica para a visualização avançada de imagens médicas.

## Funcionalidades

- Interface amigável para gerenciar os builds e execução das aplicações.
- Empacotamento simplificado das dependências, garantindo um ambiente estável e isolado.
- Suporte ao padrão **DICOMweb**, facilitando a interoperabilidade com outros sistemas.
- Integração direta com o **OHIF Viewer** para uma experiência completa na visualização de imagens médicas.

## Tecnologias utilizadas

- **Electron** – Para empacotamento e execução da aplicação.
- **Node.js** – Para gerenciamento das dependências e execução da API.
- **OHIF Viewer** – Para visualização dos dados DICOM.

## Como executar

1. Clone este repositório:
   ```bash
   git clone git@github.com:DaquinoS/Medical-Image-Control.git
   cd Medical-Image-Control
   ```
2. Instale as dependências:
   ```bash
   npm install
   ```
3. Execute a aplicação:
   ```bash
   npm start
   ```

## Importante

Os builds do OHIF Viewer e da API devem estar presentes no diretório apps

## Contribuição

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests para melhorias e correções.

## Licença

Este projeto segue a licença [MIT](LICENSE).

