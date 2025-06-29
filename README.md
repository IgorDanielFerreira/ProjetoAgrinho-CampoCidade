# Harmonia Natural: Conexão Campo & Cidade

Este projeto, "Harmonia Natural: Conexão Campo & Cidade", foi desenvolvido com o objetivo de celebrar a sinergia essencial e a interdependência entre os ambientes rural e urbano. Ele explora como o campo provê os recursos e a cidade impulsiona a inovação, mostrando as pontes que unem esses dois mundos.

## Objetivo do Projeto

O principal objetivo do site é:

-   **Incentivar a conscientização:** Destacar a importância da agricultura e da natureza para o desenvolvimento das cidades e a qualidade de vida urbana.
-   **Valorizar a conexão:** Mostrar como as inovações urbanas beneficiam o campo (como tecnologias agrícolas) e como o campo, por sua vez, nutre e inspira a vida na cidade (alimentos, bem-estar, ecoturismo).
-   **Promover a sustentabilidade:** Apresentar exemplos e iniciativas que fortalecem práticas sustentáveis em ambos os ambientes, como a agricultura de precisão e as hortas urbanas.
-   **Engajar a comunidade:** Inspirar o público a se conectar mais com a origem dos alimentos e com o movimento de agricultura urbana, participando ativamente de iniciativas locais.

## Detalhes da Interface e Interatividade

Para uma navegação intuitiva e uma experiência visual dinâmica:

-   O **Cabeçalho (Header)** inclui navegação principal e elementos visuais para fácil orientação.
-   O **Rodapé (Footer)** apresenta uma simulação de formulário de contato por e-mail e informações importantes. **Importante:** Este formulário tem fins demonstrativos e não envia mensagens reais.

## Seções Principais

O site é dividido nas seguintes seções, que abordam diferentes aspectos da conexão campo-cidade:

-   **A Alma do Campo:** Explora a importância do meio rural, desde a agricultura familiar até as revoluções tecnológicas, como a Agricultura de Precisão e o Robô Açaí.
-   **A Energia da Cidade:** Apresenta a cidade como centro de inovação, cultura e oportunidades, destacando seu dinamismo e as demandas que impulsionam o campo.
-   **Pontes que Unem:** Demonstra as diversas formas de conexão e colaboração entre campo e cidade, incluindo a agricultura familiar, o ecoturismo rural e a inovação sustentável.
-   **Comunidade em Ação:** Foca em iniciativas concretas de sucesso, como as hortas urbanas e o papel da USP na vanguarda da agricultura urbana, incluindo os benefícios simbólicos e afetivos dessas práticas.
-   **Sobre o Projeto & Recursos Visuais:** Detalhes sobre o autor, instituição, concurso e as ferramentas utilizadas na edição e criação dos elementos visuais.
-   **Contato:** Seção para interação com os visitantes.

## Tecnologias Utilizadas

Este projeto foi construído utilizando tecnologias web fundamentais:

-   **HTML5:** Para a estrutura e conteúdo da página.
-   **CSS3:** Para o design, layout responsivo, animações e efeitos visuais.

## Contexto do Projeto

Este site foi desenvolvido por **Igor Daniel Ferreira**, um estudante do 3º do Ensino Médio, para o **Concurso Agrinho 2025**, com o tema "Festejando a conexão campo cidade".

## Histórico de Versões (Releases)

Aqui você pode acompanhar as principais mudanças e melhorias em cada versão do projeto.

### Versão 1.4.0 - 20 de junho de 2025

-   **Melhoria:** Removido transition do container principal da intro.
-   **Melhoria:** Adaptado o responsive.css para mais adaptabilidade em disposivos como tablets e celulares.
-   **Melhoria:** Colocado animações em todas as imagens da página.
-   **Melhoria:** Animação de hover na lista do header arrumado após mudar de cor.
-   **Melhoria:** Alterações no hover na seção Alma Do Campo.
-   **Melhoria:** Dados restantes como contato adicionados.

### Versão 1.3.0 - 20 de Junho de 2025

-   **Melhoria:** Novas imagens adicionadas para o projeto.
-   **Melhoria:** Adaptação maior para mobile concertos de responsividade.
-   **Escalabiliadade:** A quebra de style.css para responsive.css para separar o estilo bruto dos media queries para maior escalabilidade do projeto.
-   **Funcionalidade:** Implementação de `display: none` inicial para o conteúdo da página principal (`#main-page-content`), que é revelado via CSS puro (sem JavaScript) ao clicar no botão "Entrar no Site".
-   **Melhoria Visual:** A barra de rolagem agora está camuflada em verde escuro (`--cor-primaria`) inicialmente e muda para uma cor visível (`--cor-secundaria`) via CSS puro quando o conteúdo principal da página é revelado.
-   **Usabilidade:** Os botões de navegação do carrossel (`.nav-arrow`) na seção "A Energia da Cidade" foram redimensionados e reposicionados para a parte inferior do contêiner da imagem, evitando que obstruam o texto ao passar o mouse.

### Versão 1.2.0 - 19 de Junho de 2025

-   **Melhoria:** Ícone principal da página adicionado no header e no footer e também svgs da seção "Pontos Que Unem".
-   **Melhoria:** Imagem do campo principal adicionado com a devidas informações das fontes da imagem.
-   **Melhoria:** Paddings e fontes diminuidas para melhor resposividade para mobile.

### Versão 1.1.6 - 18 de Junho de 2025 (Hotfix e Refinamentos)

-   **Hotfix:** Substituição de formatação Markdown `**texto**` por tags HTML `<strong>texto</strong>` para garantir renderização consistente e correta do negrito.
-   **Hotfix:** Implementação de JavaScript para garantir que o scroll da página seja resetado para o topo e mantido durante e após a animação de introdução, desativando a restauração automática do scroll do navegador.
-   **Hotfix:** Ajustes no CSS para garantir que a `intro-animation-container` cubra totalmente a tela, mesmo com zoom, evitando que o fundo do site seja visível antes da transição completa.
-   **Melhoria:** Botões de links redirecionáveis na seção de "Comunidade em Ação: Hortas Urbanas" e a remoção de das "Fontes de informação".

### Versão 1.1.5 - 18 de Junho de 2025

-   **Melhoria:** Aumento e centralização do texto na seção "Agricultura de Precisão e o Robô Açaí" com informações adicionais para maior clareza.
-   **Melhoria:** Ajustes finos nos estilos CSS para garantir que os títulos se adaptem melhor a telas mobile, evitando que "escapem" dos contêineres.
-   **Melhoria:** Criação de uma nova seção "Sobre o Projeto & Recursos Visuais" com detalhes sobre o autor, instituição e propósito do projeto para o Concurso Agrinho 2025.
-   **Melhoria:** Detalhamento das ferramentas visuais utilizadas e inclusão de uma galeria com *todos os placeholders de imagens* do site para demonstração.
-   **Melhoria:** Ajuste da cor do texto forte nas informações do autor/projeto para um verde mais escuro, melhorando a visibilidade.
-   **Melhoria:** Consolidação do texto geral do site para ser mais direto ao ponto e otimizado para leitura rápida.
-   **Melhoria:** Atualização do texto do rodapé para refletir que o projeto foi desenvolvido por um estudante do Ensino Médio para o Concurso Agrinho 2025.

### Versão 1.0.0 - 16 de Junho de 2025

-   **Lançamento Inicial:** Versão inicial do site "Harmonia Natural: Conexão Campo & Cidade".
-   **Funcionalidades:** Implementação das seções "Hero", "Campo", "Cidade", "Conexão", "Comunidade" e "Contato".
-   **Design:** Layout responsivo básico com tema verde e fontes definidas.
-   **Animações:** Introdução e efeitos de rolagem no cabeçalho e na seção de boas-vindas.

## Sobre o Projeto e Recursos Visuais

Este projeto foi desenvolvido por um **estudante do Ensino Médio** para o **Concurso Agrinho 2025**, com o tema "Festejando a conexão campo cidade". O intuito é demonstrar a harmonia e interdependência entre os ambientes rural e urbano através de um site interativo e visualmente atraente.

### Informações do Projeto

-   **Autor:** Igor Daniel Ferreira
-   **Localidade:** Ortigueira, Paraná, Brasil
-   **Instituição:** CEAM | Colégio Estadual Altair Mongruel
-   **Concurso:** Agrinho 2025 - Tema "Festejando a conexão campo cidade"
-   **Ano:** 2025

### Ferramentas Visuais Utilizadas

As ferramentas utilizadas para a criação e edição das imagens foram:(exceto as que não são de autoria do autor, você pode saber mais na seção "Créditos de Imagens e Atribuições" no site)

-   **Canva:** Plataforma intuitiva para design gráfico e composição de elementos.
-   **GIMP:** Software de manipulação de imagens gratuito e de código aberto para ajustes detalhados.

## Projeto Na Vercel
https://projeto-agrinho-campo-cidade-phi.vercel.app
## Projeto no Git Hub
https://igordanielferreira.github.io/ProjetoAgrinho-CampoCidade/

*Desenvolvido com paixão por um estudante do Ensino Médio para o Concurso Agrinho 2025.*
