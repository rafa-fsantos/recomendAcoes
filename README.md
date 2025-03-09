# Sistema de Recomendação de Ações da B3 utilizando Vetores e Espaço Vetorial

## 📘 Descrição do Projeto

Este projeto tem como objetivo desenvolver um **sistema de recomendação de ações da B3 (Bolsa de Valores do Brasil)**. O sistema sugere ações relacionadas com base na classificação setorial das empresas, utilizando técnicas de vetores e espaço vetorial. Com isso, buscamos simplificar o processo de diversificação de carteiras para investidores, fornecendo recomendações fundamentadas e precisas.

![RecomendAções](imagens/recomendAcoes.png)

## 🚩 Definição do Problema

### Objetivo

Criar um sistema que analise um **ticker** informado pelo usuário e sugira outras ações relacionadas com base nos seguintes critérios:

1. **Setor Econômico**  
2. **Subsetor**  
3. **Segmento**  
4. **Segmento de Listagem da B3**

### Motivação

Investidores frequentemente buscam diversificar suas carteiras, mas identificar manualmente ações de setores correlacionados é demorado e propenso a erros. Este sistema automatizado tem o potencial de otimizar esse processo, ajudando na tomada de decisões mais assertivas.

### Desafios

- Analisar dados setoriais de empresas listadas na B3 e organizar essas informações em um espaço vetorial.
- Manter o sistema atualizado com mudanças periódicas nas informações das empresas.
- Garantir que as recomendações sejam úteis e personalizadas para diferentes perfis de investidores.

### Produto Esperado

Um sistema que ofereça uma lista de ações relacionadas ao **ticker** informado, com base nos critérios definidos, permitindo aos usuários explorar opções dentro do mesmo setor ou de setores correlacionados. As recomendações serão baseadas em **dados transparentes e critérios objetivos**.

## 🔧 Tecnologias Utilizadas

- **Linguagens:** Python  
- **Bibliotecas:**  
  - Pandas e NumPy (manipulação de dados)  
  - Scikit-learn (modelagem vetorial)  
  - Nltk e Openpyxl (stemming e manipulação de planilhas Excel)  
- **Base de Dados:** Informações setoriais e financeiras das empresas listadas na B3.  
- **Outros:** Modelagem de vetores com técnicas de similaridade.

## 🚀 Como Funciona

1. **Coleta de Dados:**  
   Os dados são extraídos da B3 de arquivo que contêm informações sobre classificação setorial e listagem das empresas.  

2. **Processamento de Dados:**  
   As informações são organizadas em vetores, representando características como setor econômico, subsetor e segmento.  

3. **Recomendação:**  
   Dado um ticker informado, o sistema identifica ações similares usando métricas de distância vetorial, como **cosseno de similaridade**.  

4. **Output:**  
   Uma lista de ações relacionadas, baseadas nos critérios de semelhança por setor econômico, subsetor, segmento e listagem na B3.  

## 📈 Benefícios

- **Rapidez e Eficiência:** Reduz o tempo necessário para identificar ações relacionadas.  
- **Diversificação Inteligente:** Ajuda investidores a explorar setores correlacionados.  
- **Atualizações Frequentes:** Sistema preparado para lidar com mudanças periódicas nas informações da B3.  

## 📂 Estrutura do Projeto

- `dados/`: Contém os arquivos de dados utilizados no projeto.  
- `notebooks/`: Análises exploratórias e desenvolvimento do modelo.  

## 📋 Como Contribuir

1. Faça um fork do repositório.  
2. Crie uma branch para a sua feature: `git checkout -b minha-feature`.  
3. Commit suas alterações: `git commit -m 'Adicionar nova feature'`.  
4. Submeta um pull request.  

## 📜 Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

---

Contribuições são bem-vindas! Sinta-se à vontade para abrir **issues** ou enviar sugestões.  


