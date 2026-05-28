# Caravan - Agência de Viagens

O **Caravan** é um projeto de website responsivo para uma agência de viagens, desenvolvido para fins de estudo e prática das funcionalidades do framework **Bootstrap 4**. O site apresenta uma interface limpa, focada na conversão do usuário através de sessões de planos, locais e formulários de contato.

## 🚀 Funcionalidades

O projeto utiliza diversos componentes dinâmicos do Bootstrap:

- **Navegação Fixa:** Menu superior que acompanha a rolagem da página com suporte a dropdown.
- **Carousel (Hero):** Banner rotativo na página inicial exibindo destinos populares (Califórnia, Paris e Dublin).
- **Newsletter:** Campo de captura de e-mail integrado à seção principal.
- **Grid de Vantagens:** Seção detalhando benefícios (Documentos, Passagens, Translados, etc.) usando o sistema de colunas responsivas.
- **Seção de Citação:** Bloco de destaque estilizado para frases inspiracionais.
- **FAQ (Perguntas Frequentes):** Sistema de *Accordion* (Collapse) para organizar dúvidas comuns de forma compacta.
- **Design Responsivo:** Adaptável para dispositivos móveis, tablets e desktops.

## 🛠️ Tecnologias Utilizadas

As seguintes ferramentas e bibliotecas foram utilizadas na construção do projeto:

- [HTML5](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
- [CSS3](https://developer.mozilla.org/pt-BR/docs/Web/CSS) (com estilos customizados em `style.css`)
- Bootstrap 4.1.3 - Framework CSS.
- jQuery 3.3.1 (Slim) - Manipulação do DOM e suporte aos plugins do Bootstrap.
- Popper.js - Motor de posicionamento de tooltips e dropdowns.

## 📂 Estrutura de Arquivos

```text
Caravan/
├── css/
│   ├── bootstrap.css    # Arquivo core do Bootstrap
│   └── style.css        # Estilos customizados do projeto
├── js/
│   ├── bootstrap.js     # Lógica dos componentes Bootstrap
│   ├── jquery-3.3.1.slim.min.js
│   ├── popper.min.js
│   └── app.js           # Scripts customizados
├── img/                 # Ativos de imagem e ícones (SVG/JPG)
└── index.html           # Página principal
```

## 🔧 Como Executar

Como o projeto é estático, você não precisa de um servidor back-end ou instaladores complexos:

1. Faça o download ou clone este repositório.
2. Certifique-se de que a estrutura de pastas `css/`, `js/` e `img/` está preservada.
3. Abra o arquivo `index.html` em qualquer navegador moderno.

---
