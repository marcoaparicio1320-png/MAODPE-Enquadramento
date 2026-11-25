# Instruções de utilização do template LaTeX
**MAODPE 2026/2027 — Enquadramento Técnico-Científico**

## 1. Preparação e compilação

- Importar o ficheiro ZIP numa plataforma online de edição LaTeX (por exemplo, Overleaf) ou extrair o seu conteúdo para uma pasta local, mantendo a estrutura dos ficheiros e das pastas.
- Abrir o ficheiro `main.tex` no ambiente de edição LaTeX da preferência do estudante.
- Compilar o documento utilizando pdfLaTeX e Biber, repetindo a compilação sempre que necessário para atualizar o índice, as referências bibliográficas e as referências cruzadas.
- O template utiliza o package `arimo`, com uma fonte metricamente compatível com Arial. Não é necessário instalar Arial nem alterar o compilador predefinido do Overleaf. Em instalações locais, assegurar que este package está disponível.

## 2. Elaboração do documento

- Preencher os campos da capa e os restantes elementos preliminares.
- Elaborar um resumo e indicar as palavras-chave.
- Adaptar a organização, a designação e o número de secções e subsecções à natureza e à especificidade do trabalho, assegurando os conteúdos previstos na avaliação.
- Privilegiar a análise crítica do conhecimento relevante para o trabalho de Dissertação, Projeto ou Estágio, evitando uma revisão meramente descritiva.
- Adaptar a declaração de reconhecimento do uso de ferramentas IA à utilização efetiva das tecnologias e ferramentas de apoio.

## 3. Figuras, tabelas e equações

- Os exemplos apresentados são meramente ilustrativos, tanto na estrutura como no conteúdo, e não têm caráter vinculativo.
- A pasta `pics` contém as imagens de exemplo, que poderão ser eliminadas ou substituídas.
- A inclusão de figuras, tabelas e equações deverá ser adequada à natureza do trabalho.
- Os packages `mathtools`, `amssymb`, `bm` e `siunitx` encontram-se disponíveis para a escrita de expressões matemáticas e unidades físicas.

## 4. Referências bibliográficas

- Adicionar as referências bibliográficas ao ficheiro `referencias.bib` e utilizar os comandos de citação adequados (por exemplo, `\cite{chave}`).
- O estilo das referências bibliográficas é de escolha livre (IEEE, APA, entre outros), devendo ser utilizado de forma consistente.
- O estilo numérico configurado é meramente exemplificativo. Consultar os comentários no preâmbulo do ficheiro `main.tex` para alterar o estilo.
- Não existe limite para o número de referências bibliográficas.

## 5. Formatação e limite de páginas

- Respeitar as configurações de formatação do template: formato A4, margens de 25 mm, fonte Arimo de 10 pt, espaçamento simples entre linhas, espaçamento de 6 pt após parágrafo e títulos de secções, subsecções e subsubsecções de 12, 11 e 10 pt, respetivamente.
- O documento está limitado a 15 páginas úteis, excluindo a capa, o resumo, as palavras-chave, a declaração de reconhecimento do uso de ferramentas IA, o índice e as referências bibliográficas.
- Admite-se uma tolerância máxima de 1 página útil, independentemente do template utilizado (Word ou LaTeX).
- Não são admitidos anexos ou apêndices.

## 6. Antes da entrega

- Eliminar todos os textos orientadores a cinzento, os parágrafos Lorem ipsum e os exemplos que não façam parte do trabalho desenvolvido.
- Verificar a numeração e a referenciação das figuras, tabelas e equações, bem como a correspondência entre as citações e as referências bibliográficas.
- Confirmar o cumprimento das configurações de formatação, do limite de páginas e dos requisitos de avaliação.
