# Agregador de Dados para Imposto de Renda — Excel

## 📌 Sobre o projeto

Este projeto foi desenvolvido como parte de um desafio prático da **DIO** com o objetivo de construir, no Microsoft Excel, uma ferramenta para organizar informações importantes para a declaração de Imposto de Renda.

A solução funciona como um agregador de dados, permitindo reunir informações cadastrais, informes financeiros, rendimentos, pagamentos, despesas e bens em um único arquivo.

> **Observação:** os dados preenchidos no arquivo são apenas exemplos didáticos e não representam informações reais.

## 🎯 Objetivos

- Centralizar dados utilizados na preparação da declaração de Imposto de Renda;
- Facilitar a conferência das informações antes do preenchimento da declaração;
- Aplicar validações de dados no Excel;
- Criar uma navegação simples entre as abas;
- Automatizar consolidações por meio de fórmulas;
- Utilizar recursos visuais para melhorar a experiência do usuário.

## 🗂️ Estrutura da planilha

A pasta de trabalho contém as seguintes abas:

| Aba | Finalidade |
|---|---|
| **Menu** | Tela inicial com atalhos para as demais áreas |
| **Titular** | Cadastro das informações do contribuinte |
| **Informes** | Controle de informes bancários e financeiros |
| **Rendimentos** | Registro de rendimentos tributáveis e não tributáveis |
| **Pagamentos** | Registro de pagamentos, despesas e possíveis deduções |
| **Bens_Direitos** | Controle patrimonial de bens e direitos |
| **Resumo** | Consolidação automática dos principais valores |
| **Listas** | Tabelas auxiliares utilizadas nas validações |

## ⚙️ Recursos utilizados

Durante o desenvolvimento foram aplicados recursos do Excel como:

- Fórmulas `SUM` e `SUMIF`;
- Validação de dados com listas suspensas;
- Tabelas estruturadas;
- Formatação monetária;
- Organização por abas;
- Hiperlinks para navegação interna;
- Links rápidos para páginas da Receita Federal;
- Painel de resumo automático;
- Gráfico para visualização dos valores consolidados;
- Congelamento de painéis para melhorar a navegação.

## 📊 Funcionamento do resumo

A aba **Resumo** consolida automaticamente informações registradas nas demais abas, incluindo:

- Total de rendimentos;
- Total de Imposto de Renda retido;
- Total de pagamentos registrados;
- Total de pagamentos marcados como dedutíveis;
- Patrimônio informado em 31/12;
- Separação entre rendimentos tributáveis e não tributáveis.

## ▶️ Como utilizar

1. Abra o arquivo `Agregador_Imposto_de_Renda_DIO.xlsx`.
2. Acesse a aba **Menu**.
3. Preencha os dados do titular.
4. Cadastre os informes financeiros.
5. Registre os rendimentos recebidos.
6. Informe pagamentos e despesas.
7. Cadastre os bens e direitos.
8. Acesse a aba **Resumo** para conferir os valores consolidados.

## 📁 Estrutura do repositório

```text
.
├── Agregador_Imposto_de_Renda_DIO.xlsx
├── README.md
└── images/
```

A pasta `images` pode ser utilizada para adicionar capturas de tela do projeto.

## 🖼️ Sugestões de capturas de tela

Para valorizar a apresentação no GitHub, podem ser adicionadas imagens das seguintes telas:

- Menu principal;
- Aba de Rendimentos;
- Aba de Pagamentos;
- Aba de Bens e Direitos;
- Painel da aba Resumo.

Depois de adicionar as imagens, elas podem ser exibidas no README utilizando:

```markdown
![Menu principal](images/menu.png)
```

## 🧠 Aprendizados

O desenvolvimento deste projeto permitiu praticar a criação de uma solução mais completa no Excel, indo além do simples armazenamento de dados. Foram utilizados recursos de organização, validação, fórmulas e navegação para tornar a ferramenta mais intuitiva e reduzir erros de preenchimento.

Também foi possível reforçar a importância da documentação técnica e do uso do GitHub como portfólio para compartilhar projetos e demonstrar conhecimentos adquiridos.

## 🚀 Tecnologias

- Microsoft Excel
- Git
- GitHub
- Markdown

## 📚 Desafio

Projeto desenvolvido para entrega de desafio da **DIO — Digital Innovation One**.

---

### Aviso

Esta planilha possui finalidade exclusivamente educacional e organizacional. Ela não substitui o programa oficial da Receita Federal nem orientação profissional contábil.
