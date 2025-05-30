# Projeto A-Frame CPM

Uma experiência WebXR interativa desenvolvida com A-Frame para a unidade curricular de Conceção e Produção Multimédia (CPM) da ESMAD. Este projeto apresenta uma galeria virtual com diversos objetos 3D, cada um com descrições, animações e/ou sons interativos.

## 🎓 Sobre o Projeto

Este projeto foi desenvolvido no âmbito da unidade curricular de **Conceção e Produção Multimédia (CPM)**, integrada no curso de **Tecnologias e Sistemas de Informação para a Web (TSIW)** da **Escola Superior de Media Artes e Design (ESMAD - IPP)**.

* **Autores:**
    * **António Amorim:** [GitHub](https://github.com/amorima)
    * **Gabriel Paiva:** [GitHub](https://github.com/Gabriel-S-Paiva)
    * **Henrique Silva:** [GitHub](https://github.com/HenReis)
* **Repositório GitHub:** [amorima/Projeto-A-Frame-CPM](https://github.com/amorima/Projeto-A-Frame-CPM/)

## Demonstração Online

A demonstração do projeto está acessível online através do seguinte link:

**[Ver Projeto Online](https://projeto-a-frame-cpm.vercel.app/)**

## Funcionalidades Principais

O projeto apresenta as seguintes funcionalidades:

* **Galeria Virtual:** Permite a exploração de uma cena tridimensional contendo diversos objetos.
* **Interatividade:** Os objetos reagem ao clique do rato ou ao foco do olhar (em modo VR), permitindo:
    * Visualizar descrições textuais associadas a cada objeto.
    * Ativar animações específicas (ex: rotação do Cubo de Rubik e do Donut).
    * Reproduzir sons contextuais (ex: música no Rádio Vintage).
    * Visualizar conteúdo de vídeo (ex: clipe na TV Retro).
* **Compatibilidade VR:** O projeto foi desenhado para ser explorado em Realidade Virtual, utilizando as capacidades nativas do A-Frame.
* **Navegação:** Inclui controlos intuitivos para a navegação na cena, como movimento e rotação da câmara.

## Tecnologias Utilizadas

As principais tecnologias e bibliotecas empregues no desenvolvimento foram:

* **[A-Frame](https://aframe.io/) (v1.5.0):** Framework web para a construção de experiências de realidade virtual e aumentada.
* **HTML5:** Linguagem de marcação para a estrutura da página web.

## Como Executar Localmente

Para executar este projeto num ambiente local, siga os seguintes passos:

1.  **Clonar o repositório:**
    ```bash
    git clone [https://github.com/amorima/Projeto-A-Frame-CPM.git](https://github.com/amorima/Projeto-A-Frame-CPM.git)
    ```
2.  **Navegar para a diretoria do projeto:**
    ```bash
    cd Projeto-A-Frame-CPM
    ```
3.  **Abrir o projeto:**
    * Abra o ficheiro `index.html` diretamente num navegador web compatível.
    * Alternativamente, para uma melhor experiência e para evitar potenciais problemas de CORS (Cross-Origin Resource Sharing) com os *assets*, recomenda-se a utilização de um servidor local. Caso tenha o Node.js instalado, pode-se utilizar o comando `npx http-server` na diretoria do projeto, ou recorrer a extensões como "Live Server" no Visual Studio Code.

## Estrutura do Projeto

A organização dos ficheiros e diretorias do projeto é a seguinte:

Claro, aqui está o README completo formatado em Markdown, pronto para copiar e colar:

Markdown

# Projeto A-Frame CPM

Uma experiência WebXR interativa desenvolvida com A-Frame para a unidade curricular de Conceção e Produção Multimédia (CPM) da ESMAD. Este projeto apresenta uma galeria virtual com diversos objetos 3D, cada um com descrições, animações e/ou sons interativos.

## 🎓 Sobre o Projeto

Este projeto foi desenvolvido no âmbito da unidade curricular de **Conceção e Produção Multimédia (CPM)**, integrada no curso de **Tecnologias e Sistemas de Informação para a Web (TSIW)** da **Escola Superior de Media Artes e Design (ESMAD - IPP)**.

* **Autores:**
    * **António Amorim:** [GitHub](https://github.com/amorima)
    * **Gabriel Paiva:** [GitHub](https://github.com/Gabriel-S-Paiva)
    * **Henrique Silva:** [GitHub](https://github.com/HenReis)
* **Repositório GitHub:** [amorima/Projeto-A-Frame-CPM](https://github.com/amorima/Projeto-A-Frame-CPM/)

## Demonstração Online

A demonstração do projeto está acessível online através do seguinte link:

**[Ver Projeto Online](https://projeto-a-frame-cpm.vercel.app/)**

## Funcionalidades Principais

O projeto apresenta as seguintes funcionalidades:

* **Galeria Virtual:** Permite a exploração de uma cena tridimensional contendo diversos objetos.
* **Interatividade:** Os objetos reagem ao clique do rato ou ao foco do olhar (em modo VR), permitindo:
    * Visualizar descrições textuais associadas a cada objeto.
    * Ativar animações específicas (ex: rotação do Cubo de Rubik e do Donut).
    * Reproduzir sons contextuais (ex: música no Rádio Vintage).
    * Visualizar conteúdo de vídeo (ex: clipe na TV Retro).
* **Compatibilidade VR:** O projeto foi desenhado para ser explorado em Realidade Virtual, utilizando as capacidades nativas do A-Frame e bibliotecas como `super-hands` e `progressive-controls`.
* **Navegação:** Inclui controlos intuitivos para a navegação na cena, como movimento e rotação da câmara.

## Tecnologias Utilizadas

As principais tecnologias e bibliotecas empregues no desenvolvimento foram:

* **[A-Frame](https://aframe.io/) (v1.5.0):** Framework web para a construção de experiências de realidade virtual e aumentada.
* **HTML5:** Linguagem de marcação para a estrutura da página web.
* **JavaScript:** Linguagem de programação para a lógica de interações e controlo dinâmico dos componentes A-Frame.
* **Componentes A-Frame Adicionais:**
    * `super-hands`: Utilizado para implementar interações avançadas com as mãos ou controladores VR.
    * `progressive-controls`: Implementa controlos adaptáveis a diferentes dispositivos de entrada.
    * `event-manager`: Responsável pela gestão de eventos na cena.
    * `animation-mixer`: Utilizado para reproduzir animações em modelos 3D.

## Como Executar Localmente

Para executar este projeto num ambiente local, siga os seguintes passos:

1.  **Clonar o repositório:**
    ```bash
    git clone [https://github.com/amorima/Projeto-A-Frame-CPM.git](https://github.com/amorima/Projeto-A-Frame-CPM.git)
    ```
2.  **Navegar para a diretoria do projeto:**
    ```bash
    cd Projeto-A-Frame-CPM
    ```
3.  **Abrir o projeto:**
    * Abra o ficheiro `index.html` diretamente num navegador web compatível.
    * Alternativamente, para uma melhor experiência e para evitar potenciais problemas de CORS (Cross-Origin Resource Sharing) com os *assets*, recomenda-se a utilização de um servidor local. Caso tenha o Node.js instalado, pode-se utilizar o comando `npx http-server` na diretoria do projeto, ou recorrer a extensões como "Live Server" no Visual Studio Code.
  
## 🙏 Agradecimentos

* Escola Superior de Media Artes e Design (ESMAD)
* Politécnico do Porto (P.PORTO)
* Prof. Bárbara Cleto