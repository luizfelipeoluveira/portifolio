# 💻 Portfólio Profissional — Luiz Felipe

**Aluno:** Luiz Felipe

## 📌 Descrição do projeto

Este projeto consiste no desenvolvimento de um portfólio profissional e acadêmico, criado com o objetivo de apresentar meu perfil, minha formação, minhas tecnologias e ferramentas estudadas, além de projetos desenvolvidos durante minha jornada na área de tecnologia.

O site foi desenvolvido utilizando HTML5, CSS3 e Bootstrap, buscando proporcionar uma navegação intuitiva, uma interface organizada e um layout responsivo.

## 🚀 Tecnologias utilizadas

As seguintes tecnologias e ferramentas foram utilizadas no desenvolvimento:

- **HTML5:** estruturação e organização do conteúdo do site.
- **CSS3:** estilização dos elementos, personalização visual e ajustes de layout.
- **Bootstrap 5.3.3:** utilização de componentes, classes e recursos para criação de uma interface responsiva.
- **JavaScript:** implementação de interações e funcionalidades dinâmicas.
- **Devicon:** biblioteca utilizada para exibição de ícones das tecnologias.
- **Visual Studio Code:** ambiente utilizado para desenvolvimento do projeto.
- **GitHub:** armazenamento e versionamento do código-fonte.

## 🌐 Site publicado

**Link de acesso:** [INSERIR LINK DO SITE PUBLICADO]

## ⚙️ Funcionamento do projeto

O portfólio é dividido em seções que permitem ao visitante conhecer diferentes informações sobre o desenvolvedor.

- **Carrossel:** apresenta imagens em destaque, permitindo alternar entre diferentes slides por meio de indicadores e controles laterais.
- **Perfil:** apresenta informações pessoais e profissionais, formação acadêmica, localização, objetivos e área de interesse.
- **Tecnologias e ferramentas:** exibe as principais tecnologias e ferramentas estudadas, acompanhadas de seus respectivos ícones e descrições.
- **Projetos:** apresenta projetos e atividades desenvolvidos, com imagens, descrições e links para acesso.
- **Contato:** disponibiliza links para comunicação por e-mail, GitHub e LinkedIn.
- **Menu de navegação:** permite acessar diretamente as diferentes seções do portfólio.

## ✨ Recursos adicionais implementados

Além das funcionalidades básicas, foram adicionados recursos para melhorar a experiência de navegação e personalizar a interface.

### 1. Sidebar (Menu lateral retrátil)

O menu de navegação foi modificado de uma barra horizontal superior para uma barra lateral fixa, localizada no lado esquerdo da tela.

Também foi implementado um botão que permite expandir ou recolher o menu, oferecendo duas opções de visualização:

- **Expandido:** apresenta o nome do desenvolvedor e os textos dos links de navegação, ocupando 220px de largura.
- **Recolhido:** reduz a largura do menu para 75px e oculta os textos, economizando espaço na tela.

### 2. Personalização do background

Foi utilizada a propriedade `background-color` do CSS para permitir a personalização das cores de fundo dos elementos do site.

Também foram utilizadas classes de background do Bootstrap, como `bg-dark` e `bg-white`, para diferenciar visualmente as seções e componentes.

### 3. Animação de transição da sidebar

Foi adicionada uma transição suave durante a expansão e o recolhimento do menu lateral, utilizando a propriedade `transition` do CSS.

Isso evita mudanças bruscas na interface e proporciona uma navegação visualmente mais agradável.

## 🛠️ Como os recursos foram implementados

### Sidebar fixa

A barra lateral foi posicionada utilizando propriedades CSS:

- `position: fixed`: mantém o menu fixo na tela durante a rolagem.
- `top: 0` e `left: 0`: posicionam o menu no canto superior esquerdo.
- `width: 220px`: define a largura inicial.
- `height: 100vh`: faz o menu ocupar toda a altura da tela.

Para evitar que o conteúdo do site ficasse escondido atrás da sidebar, foi aplicada uma margem esquerda de 220px ao `body`, utilizando `margin-left`.

### Expansão e recolhimento do menu

A funcionalidade foi implementada com JavaScript, utilizando os métodos `getElementById()`, `querySelector()` e `addEventListener()`.

O método `classList.toggle()` permite adicionar ou remover classes CSS conforme o usuário clica no botão.

Com isso, a classe `collapsed` é aplicada ou removida da sidebar, alterando sua largura. Outra classe é aplicada ao `body` para ajustar a margem do conteúdo de acordo com o tamanho atual do menu.

### Ocultação dos textos

Para ocultar os nomes dos links e o nome do desenvolvedor quando o menu está recolhido, foi utilizada a propriedade CSS `display: none`, aplicada aos elementos que possuem a classe `sidebar-label`.

### Transição visual

A propriedade `transition` foi utilizada para criar uma animação suave na alteração da largura da sidebar e da margem do conteúdo principal.

### Personalização das cores

A personalização visual foi realizada por meio de propriedades CSS e classes utilitárias do Bootstrap, permitindo controlar as cores de fundo de diferentes partes da página.

---

## 🎯 Objetivo acadêmico

O desenvolvimento deste projeto teve como objetivo colocar em prática os conhecimentos adquiridos em HTML, CSS e Bootstrap , explorando conceitos de estruturação de páginas, estilização, responsividade e manipulação de elementos HTML.

O portfólio também representa uma forma de documentar minha evolução como estudante e apresentar meus conhecimentos e projetos na área de desenvolvimento de sistemas.

---

**Desenvolvido por Luiz Felipe**