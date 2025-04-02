# Template LaTeX para TCC - UNIJUÍ

Este repositório contém um **template LaTeX** para trabalhos de conclusão de curso (TCC) dos cursos de **Ciência da Computação** e **Engenharia de Software** da **Universidade Regional do Estado do Rio Grande do Sul (UNIJUÍ)**.

## Sobre o Template
O template foi desenvolvido com base no **abnTeX2** e inclui diversas customizações específicas para atender às normas da UNIJUÍ. Ele facilita a formatação correta do trabalho acadêmico, garantindo conformidade com as diretrizes institucionais e as normas da ABNT.

## Recursos
✅ Estrutura padronizada para TCCs da UNIJUÍ  
✅ Configuração automática de capa, folha de rosto e elementos pré-textuais  
✅ Suporte a referências no formato ABNT usando BibTeX  
✅ Configuração para listas de figuras, tabelas e siglas  
✅ Personalizações específicas para os cursos de Ciência da Computação e Engenharia de Software  


## Estrutura do Projeto

### Arquivos principais

- **`main.tex`**: Define as configurações iniciais do projeto LaTeX, incluindo o tipo de documento, templates e pacotes utilizados. Também organiza a estrutura do documento e inclui os arquivos auxiliares das seções pretextuais, textuais e pós-textuais.

- **`01_metadados.tex`**: Contém as informações do TCC, como instituição, título, autor, orientador, banca, datas e preâmbulo. Além disso, inclui os resumos e palavras-chave (em português e inglês) que serão utilizados na capa, folha de rosto e folha de aprovação.

- **`02_pre-textuais.tex`**: Agrupa os elementos pretextuais, como dedicatória, agradecimentos, epígrafe, resumo, abstract, listas de ilustrações e tabelas, abreviaturas, siglas, símbolos e sumário.

- **`03_textuais.tex`**: Reúne os capítulos do TCC, como introdução, fundamentação teórica, metodologia, resultados e conclusão. É o principal local onde o conteúdo do trabalho é escrito.

- **`04_pos-textuais.tex`**: Inclui os elementos pós-textuais, como apêndices e anexos.

- **`references.bib`**: Arquivo BibTeX que armazena as referências bibliográficas do trabalho, permitindo a geração automática de citações conforme o estilo definido.

### Diretórios e arquivos auxiliares

- **`templates/`**: Contém os templates customizados para a formatação do documento.
  - **`abntex2cite.sty`**: Arquivo de estilo para formatação de citações conforme as normas da ABNT atualizada, baseado no projeto abnTeX2 customizado.
  - **`unijui.sty`**: Arquivo de estilo específico para construção da capa, folha de rosto e folha de aprovação, contendo regras de formatação padronizadas para documentos acadêmicos conforme recomendações da UNIJUÍ.

- **`imagens/`**: Pasta destinada ao armazenamento das figuras utilizadas no TCC. Recomenda-se criar uma estrutura hierárquica de diretórios dentro de `imagens/` para organizar as imagens conforme os capítulos e seções do trabalho.
  
  **Exemplo de estrutura:**
  ```
  imagens/
    ├── introducao/
    ├── referencial-teorico/
    │   ├── nome-secao-1/
    │   │   ├── nome-imagem1.jpg (ou .eps, .png)
    │   │   ├── nome-imagem2.jpg
    │   │   ├── nome-imagem3.jpg
    ├── nome-da-secao-de-desenvolvimento/
    │   ├── nome-secao-1/
    │   ├── nome-secao-2/
  ```

## Como Usar

Para utilizar o template, basta **clonar** este repositório e editar os arquivos conforme necessário. 

📌 **Contribuições e sugestões são bem-vindas!** Caso encontre algum problema ou tenha melhorias a sugerir, fique à vontade para abrir uma issue ou enviar um pull request.
