# 📚 Gaveteiro Scripts - Gerenciador de Documentações Técnicas

![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=Streamlit&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![Github](https://img.shields.io/badge/github-000000?style=for-the-badge&logo=GitHub&logoColor=white)
![Python](https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=Python&logoColor=white)

## 🚀 Visão Geral
Sistema completo para organização e gerenciamento de documentações técnicas com suporte a Markdown e sistema de tags.

## ✨ Funcionalidades

| Feature               | Descrição                                                                 |
|-----------------------|---------------------------------------------------------------------------|
| **Adição de Docs**    | Inclui título, descrição em Markdown e tags                              |
| **Visualização**      | Renderização automática de Markdown com syntax highlighting              |
| **Edição Inline**     | Atualização direta dos documentos na interface                           |
| **Sistema de Tags**   | Organização por categorias com relacionamento muitos-para-muitos         |
| **Copiar Descrição**  | Botão de copiar com um clique para o conteúdo Markdown                   |
| **Busca**             | Filtragem por tags ou conteúdo                                           |

## 🛠️ Tecnologias

- **Frontend**: Streamlit
- **Backend**: Python 3.9+
- **Database**: SQLite3
- **Formatação**: Markdown

## 📦 Estrutura do Projeto

```bash
gaveteiro-scripts/
├── app.py                  # Interface principal
├── controller/
│   ├── __init__.py
│   └── controller.py       # Lógica de negócios
├── database/
│   ├── __init__.py
│   └── manager.py          # Modelo de dados
├── prog_documentacao/
│   └── documentacao.db     # Banco de dados
├── requirements.txt        # Dependências
└── README.md               # Documentação
```

## 🚀 Como Executar

### Pré-requisitos
```bash
Python 3.9+
Pip instalado
```

### Instalação
```bash
git clone https://github.com/seu-usuario/gaveteiro-scripts.git
cd gaveteiro-scripts
pip install -r requirements.txt
```
### Inicialização
```bash
streamlit run app.py
🔗 A aplicação estará disponível em: http://localhost:8501
```

### 📄 Licença
MIT License - Veja LICENSE para detalhes.

Desenvolvido com ❤️ por [Gustavo Palacio](https://www.linkedin.com/in/gfpalacio/)
