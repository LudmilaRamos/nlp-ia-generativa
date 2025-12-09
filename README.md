# nlp-ia-generativa
# NLP com IA Generativa (Projeto Conceitual) 🚀

![Python](https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![OpenAI](https://img.shields.io/badge/OpenAI-414141?style=for-the-badge&logo=openai&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FF6C37?style=for-the-badge&logo=huggingface&logoColor=white)
![Transformers](https://img.shields.io/badge/Transformers-000000?style=for-the-badge&logo=transformers&logoColor=white)

> Pipeline conceitual de **NLP com LLMs** para **classificação e sumarização de textos**, aplicando fundamentos de **IA Generativa e prompting**. Ideal para portfólio profissional e aprendizado prático.

---

## 🎯 Objetivos

- Criar um pipeline conceitual de NLP com LLMs.
- Demonstrar classificação e sumarização automática de textos.
- Aplicar técnicas de prompting de forma prática.
- Organizar um projeto profissional para portfólio.

---

## 🗂 Estrutura do Projeto

- **pipeline.py** – Função `gerar_texto()` para formatação do prompt e geração de respostas.
- **app.py** – Script interativo para testar o pipeline (perguntas e resumos).
- **.venv/** – Ambiente virtual Python com todas as dependências (não versionado no GitHub).
- **__pycache__/** – Cache do Python.

---

## ⚙ Pipeline Conceitual

1. **Entrada de Dados**: textos ou perguntas digitadas pelo usuário.  
2. **Pré-processamento**: limpeza e formatação do texto para o modelo.  
3. **Classificação de Texto**: LLMs categorizam ou respondem à pergunta.  
4. **Sumarização**: geração automática de resumos quando solicitado.  
5. **Saída**: respostas ou resumos gerados pelo modelo.

---

## 🛠 Tecnologias e Ferramentas

- Python 3.10+
- Hugging Face Transformers
- OpenAI API (opcional)
- Pandas, NumPy
- Jupyter Notebook

---

## 🚀 Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/LudmilaRamos/nlp-ia-generativa.git
cd nlp-ia-generativa

2. Crie e ative um ambiente virtual:
python -m venv .venv
# Windows PowerShell
.\.venv\Scripts\Activate.ps1
# ou Windows CMD
.\.venv\Scripts\activate.bat
# macOS / Linux
source .venv/bin/activate

3. Instale as dependências:
pip install -r requirements.txt

4.Rode o script principal:
python app.py

5.Digite sua pergunta ou instrução de texto:
Digite sua pergunta (ou 'resumir: <texto>' / 'sair'):
Para resumir um texto:
Digite sua pergunta (ou 'resumir: <texto>' / 'sair'): resumir: A inteligência artificial está mudando o mundo, permitindo automações avançadas...
Para sair do app, digite:
sair

---

💡 Observações

O projeto é conceitual, ou seja, serve para aprendizado e portfólio.

As respostas podem aparecer parcialmente em inglês dependendo do modelo, mas ajustes no pipeline.py garantem respostas em português.

O ambiente virtual (.venv) deve ser incluído no .gitignore para não subir no GitHub.

---

📬 Contato

Ludmila Almeida Ramos
Email: ludmilaramos0@gmail.com
GitHub: LudmilaRamos
Linkedin: https://www.linkedin.com/in/ludmila-almeida-ramos/
