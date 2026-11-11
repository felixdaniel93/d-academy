# D•Academy — Landing page de academia de alto padrão

Landing page responsiva para uma academia fictícia, criada como projeto prático do curso de Bootstrap. O foco foi construir uma página completa, do menu ao formulário de contato, aplicando componentes, animações e JavaScript sobre uma base em HTML e CSS.


## Funcionalidades

- **Hero com carrossel** em tela cheia, com transição em fade, setas e indicadores
- **Menu fixo** com destaque automático da seção ativa (ScrollSpy)
- **Contadores animados** na seção de estatísticas
- **Cards de serviços** responsivos (1, 2 ou 3 colunas, conforme a tela)
- **Galeria de unidades** em layout masonry, com **filtro por categoria** e **lightbox** para ampliar as fotos
- **Call to action** com imagem de fundo em efeito parallax e botão para WhatsApp
- **Formulário de contato** com máscara de telefone, validação de 11 dígitos e envio via Formspree, sem recarregar a página
- **Animações de entrada** ao rolar a página (AOS)

## Tecnologias

| Categoria | Ferramentas |
|---|---|
| Base | HTML5, CSS3, JavaScript (vanilla) |
| Framework | Bootstrap 5.3.8 |
| Ícones | Bootstrap Icons 1.13.1 |
| Animações | AOS 2.3.1, PureCounter |
| Galeria | Isotope, Masonry, imagesLoaded, GLightbox |
| Formulário | Formspree (fetch API) |

## Estrutura do projeto

```
.
├── index.html
├── css/
│   └── style.css
├── img/
│   ├── hero/        # imagens do carrossel
│   ├── galeria/     # fotos da galeria de unidades
│   └── ...
└── README.md
```

## Como executar

Não precisa instalar nada. As bibliotecas são carregadas por CDN.

```bash
git clone https://github.com/felixdaniel93/d-academy
cd d-academy

```

Abra o `index.html` no navegador. Se preferir um servidor local, use a extensão **Live Server** do VS Code.

## O que pratiquei neste projeto

- Estruturar uma página longa com HTML semântico e sistema de grid do Bootstrap
- Sobrescrever estilos do Bootstrap com CSS próprio (carrossel, botões, filtros)
- Integrar bibliotecas de terceiros via CDN e inicializá-las com JavaScript
- Manipular o DOM: filtros da galeria, máscara de telefone e validação de formulário
- Enviar dados com `fetch` e tratar sucesso, erro e falha de conexão
- Pensar em responsividade (mobile first) e acessibilidade básica (`alt` nas imagens, `label` nos campos)

## Próximos passos

- [ ] Preencher as páginas dos botões "Leia Mais" dos serviços
- [ ] Trocar os dados fictícios (endereço, telefone, e-mail) por dados reais, se o projeto for usado
- [ ] Otimizar as imagens (formato WebP) para carregar mais rápido
- [ ] Tornar os filtros da galeria acessíveis por teclado

## Autor

**Daniel Felix**

[LinkedIn](https://www.linkedin.com/in/felixdaniel93/) · [GitHub](https://github.com/felixdaniel93) · [E-mail](danielfdamaceno93@gmail.com)

---

_Projeto fictício, criado apenas para fins de estudo e portfólio. Nome, textos, endereço e contatos são exemplos._
