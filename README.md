%%writefile README.md
# Governance & Metadata Engineering Lab 📊

![Data Governance](https://raw.githubusercontent.com/Tatianakami/governance-metadata-engineering/main/banner.png)
*(Dica: Se você não tiver uma imagem própria, este link acima é apenas um placeholder. Recomendo usar esta imagem estável abaixo:)*

![Data Engineering Banner](https://images.unsplash.com/photo-1551288049-bbbda546697a?auto=format&fit=crop&q=80&w=1000)

Este projeto explora a manipulação e governança de metadados em diferentes formatos de dados (estruturados e não estruturados). Desenvolvido como parte do laboratório de Ciência da Computação, o objetivo é garantir a integridade, rastreabilidade e autonomia no uso de ativos de dados através de documentação técnica e metadados embutidos.

---

## 🛠️ Tecnologias e Ferramentas
O projeto foi desenvolvido utilizando o ecossistema Python focado em processamento de dados em larga escala:

* **Python 3.12**: Linguagem base para automação e manipulação de scripts.
* **Pandas**: Utilizado para criação de dicionários de dados e simulação de "Data Blindness".
* **PyArrow (Apache Arrow)**: Ferramenta central para gestão de Schemas colunares e persistência de arquivos Parquet.
* **Pillow (PIL)**: Biblioteca para extração de metadados EXIF de arquivos de imagem (dados não estruturados).
* **JSON**: Formato utilizado para análise e estruturação de metadados de mídia e integração com APIs.

---

## 📋 Funcionalidades Principais

* **Data Blindness Simulation**: Técnica para identificar a importância crítica de metadados na compreensão de datasets desconhecidos.
* **Dicionário de Dados**: Criação de um repositório centralizado com descrições detalhadas, origens e regras de validação para garantir a "Fonte Única da Verdade".
* **Extração EXIF**: Leitura de metadados técnicos invisíveis em imagens, como modelo do dispositivo, software e dimensões físicas.
* **Schema Engineering**: Implementação de metadados de negócio (autor, data de ingestão, descrição) diretamente no cabeçalho binário de arquivos `.parquet`, tornando-os autodescritivos.

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
3.  **Ambiente:** O projeto foi otimizado para execução em ambientes **Jupyter Notebook** ou **Google Colab**.

---
**Desenvolvido por Tatiana Kamioka** 🕯️💻
*(Computer Science Student | Data & AI Intern)*
