# 🏛️ Museu Nacional - Página Inicial

Este projeto é o desenvolvimento de uma página inicial (Homepage) simples para o Museu Nacional, com o objetivo de apresentar as principais informações de forma clara e visualmente organizada, simulando um site informativo de museu.

## ✨ Funcionalidades

* **Navegação Principal:** Menu de navegação completo com links para diferentes seções do site (Home, Exposições, Pesquisa, Acervo, Vídeos, Fotos, Contato).
* **Destaque Visual:** Imagem de capa principal do museu.
* **Conteúdo Multimídia:**
    * Vídeo incorporado do YouTube (`iframe`) para uma introdução ao museu.
    * Mapa incorporado (`iframe`) para ajudar os visitantes a localizar o museu.
* **Lista de Exposições:** Apresenta uma lista de exposições atuais e um link para ver todas.
* **História:** Pequeno artigo sobre os "200 anos de história" do museu.
* **Barra Lateral (`aside`):**
    * Espaço para **Depoimento**.
    * **Formulário de Visita:** Permite selecionar data e quantidade de pessoas para verificar a disponibilidade de ingressos.
    * **Galeria de Fotos:** Exibe miniaturas de imagens do acervo/local.
* **Rodapé:** Links de navegação replicados e informações de direitos autorais.

## 🛠️ Tecnologias Utilizadas

Este é um projeto estático, construído com as seguintes tecnologias web fundamentais:

* **HTML5:** Estruturação semântica de todo o conteúdo da página.
* **CSS3:** (Não incluído no `index.html`, mas referenciado) Para estilização e layout (via `normalize.css` e `estilo.css`).

## 📁 Estrutura do Projeto

A página foi desenvolvida com base na seguinte estrutura de arquivos (assumindo que os arquivos CSS e de imagens estão nas respectivas pastas):

```
├── index.html  
├── style/  
    ├── normalize.css  
    └── estilo.css  
├── images/  
    ├── museu.png  
    ├── depoimento.png  
    ├── imagem1.jpg  
    ├── imagem2.jpg  
    ├── imagem3.jpg  
    └── imagem4.jpg 
```

## 🚀 Como Visualizar

Para ver esta página em funcionamento no seu navegador, siga estes passos simples:

1.  **Clone o Repositório:**
    ```bash
    git clone https://github.com/EweFiamoncini/Museu-Nacional
    ```
2.  **Navegue até a Pasta:**
    ```bash
    cd Museu-Nacional
    ```
3.  **Abra o Arquivo:**
    * Localize o arquivo `index.html` na pasta principal do projeto.
    * Dê um **duplo clique** no arquivo. Ele será aberto automaticamente no seu navegador padrão.

---

## 📝 Observações

* O CSS (arquivos em `style/`) e as imagens (arquivos em `images/`) são referenciados no HTML, mas seus conteúdos específicos não foram fornecidos. O visual final dependerá desses arquivos de estilo.
* O formulário de visita e os links são apenas modelos e não possuem funcionalidade de back-end.

## 👤 Autor

Ewerton Fiamoncini  
[GitHub](https://github.com/EweFiamoncini)  
[Linkedin](https://www.linkedin.com/in/ewertonfiamoncini/)  
[Portfolio](https://ewefiamoncini.github.io/portfolio/)