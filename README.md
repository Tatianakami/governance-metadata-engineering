%%writefile README.md
# Governance & Metadata Engineering Lab 📊

![Data Engineering Banner](https://images.unsplash.com/photo-1551288049-bbbda546697a?auto=format&fit=crop&q=80&w=1000)

Este projeto explora a manipulação e governança de metadados em diferentes formatos de dados (estruturados e não estruturados). Desenvolvido como parte do laboratório de Ciência da Computação, o objetivo é garantir a integridade, rastreabilidade e autonomia no uso de ativos de dados através de documentação técnica e metadados embutidos.

---

## 🛠️ Tecnologias e Ferramentas
O projeto utiliza tecnologias essenciais para a Engenharia de Dados moderna:

* **Python 3.12**: Linguagem base para automação e manipulação de scripts.
* **Pandas**: Utilizado para criação de dicionários de dados e simulação de "Data Blindness".
* **PyArrow (Apache Arrow)**: Ferramenta central para gestão de Schemas colunares e persistência de arquivos Parquet.
* **Pillow (PIL)**: Biblioteca para extração de metadados EXIF de imagens (dados não estruturados).
* **JSON**: Formato para estruturação de metadados de mídia e integração com APIs de vídeo.

---

## 📋 Funcionalidades Principais

* **Data Blindness Simulation**: Técnica para identificar a importância crítica de metadados na compreensão de datasets.
* **Dicionário de Dados**: Repositório centralizado com descrições, origens e regras de validação para garantir a "Fonte Única da Verdade".
* **Extração EXIF**: Leitura de metadados técnicos invisíveis em imagens, como modelo do dispositivo e software de criação.
* **Schema Engineering**: Implementação de metadados de negócio (autor, data de ingestão, descrição) diretamente no cabeçalho de arquivos `.parquet`.

---

## 🚀 Como Executar o Projeto

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/Tatianakami/governance-metadata-engineering.git](https://github.com/Tatianakami/governance-metadata-engineering.git)
    ```
2.  **Instale as dependências:**
    ```bash
    pip install pandas pyarrow Pillow
    ```
3.  **Ambiente:** O projeto foi otimizado para execução em **Jupyter Notebook** ou **Google Colab**.

---
**Desenvolvido por Tatiana Kamioka** 🕯️💻
*(Computer Science Student | Data & AI Intern)*
