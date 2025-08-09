# 📚 Mesclador de PDFs com Python

Este projeto permite unir múltiplos arquivos PDF em um único documento, utilizando Python e a biblioteca PyPDF2. Ideal para consolidar relatórios, documentos escaneados ou qualquer conjunto de PDFs.

## 🚀 Funcionalidades

- Junta 3 ou mais arquivos PDF em um único documento
- Permite definir a ordem dos arquivos
- Gera um novo PDF mesclado com nome personalizado

## 🛠️ Tecnologias Utilizadas

- Python 3.x
- Biblioteca `PyPDF2`
- Biblioteca `os`

## 📦 Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/ferreira-08/mesclador-de-pdf.git

   
#Instale a biblioteca necessária:

bash
pip install PyPDF2

Coloque os arquivos PDF na mesma pasta do script.

Execute o script:

python mesclador.py

🧠 Como funciona
O script busca os arquivos PDF definidos no código, abre cada um deles, extrai suas páginas e as junta em um novo arquivo chamado pdf_final.pdf.

Você pode modificar o script para aceitar qualquer número de arquivos ou até mesmo ler os nomes dinamicamente de uma pasta.

📁 Estrutura de Pastas
mesclador-de-pdf/
├── mesclador.py
├── arquivo1.pdf
├── arquivo2.pdf
├── arquivo3.pdf
└── README.md
