# devRCMF.github.io
Projeto 1 - Front End
# Ciclo Vivo

Site institucional estático de uma ONG fictícia voltada à reciclagem, à inclusão social e ao apoio a cooperativas de catadores. O projeto foi desenvolvido com **HTML5 e CSS3**, sem dependência de frameworks ou JavaScript.

## Objetivo do projeto

Apresentar a iniciativa Ciclo Vivo, divulgar seus projetos socioambientais e permitir que pessoas interessadas preencham um formulário de cadastro para demonstrar interesse em participar ou apoiar a organização.

## Páginas do site

- **`index.html`** — página inicial, com apresentação da organização, missão, história, equipe, resultados, transparência e informações de contato.
- **`projetos.html`** — apresenta projetos sociais, campanhas de arrecadação, oportunidades de voluntariado, formas de doação e dúvidas frequentes.
- **`cadastro.html`** — formulário para cadastro de pessoas interessadas, com validação nativa dos campos pelo navegador.
- **`obrigado.html`** — página de confirmação exibida após o envio do formulário.

## Estrutura de pastas

```text
ciclo-vivo/
├── index.html
├── projetos.html
├── cadastro.html
├── obrigado.html
├── README.md
├── css/
│   └── estilo.css
└── img/
    ├── hero-coleta.svg
    ├── projeto-oficina.svg
    ├── projeto-escolas.svg
    ├── projeto-cooperativa.svg
    ├── cadastro-muda.svg
    └── equipe-triagem.svg
```

## Tecnologias utilizadas

- **HTML5:** estrutura e conteúdo das páginas.
- **CSS3:** estilos, layout e adaptação a diferentes tamanhos de tela.
- **SVG:** ilustrações vetoriais utilizadas no site.

O projeto não utiliza bibliotecas externas, frameworks ou JavaScript.

## Recursos e cuidados técnicos

- Elementos HTML semânticos, como `header`, `nav`, `main`, `section`, `article` e `footer`.
- Estrutura de títulos organizada e idioma da página definido como português do Brasil (`pt-BR`).
- Recursos de acessibilidade, incluindo link para pular diretamente ao conteúdo, indicação de foco visível e rótulos associados aos campos do formulário.
- Layout responsivo, com estilos adaptados para diferentes larguras de tela.
- Imagens SVG leves, com dimensões declaradas e carregamento tardio aplicado às imagens abaixo da primeira área visível.
- Metadados de título definidos nas páginas para ajudar na identificação do conteúdo.

## Como executar localmente

1. Baixe ou extraia os arquivos do projeto.
2. Mantenha a estrutura de pastas original para que os caminhos de CSS e imagens continuem funcionando.
3. Abra o arquivo `index.html` em um navegador.
4. Use os links de navegação para acessar as outras páginas.

Não é necessário instalar dependências nem executar um servidor para visualizar as páginas estáticas.

## Validação do HTML

As páginas HTML podem ser verificadas individualmente pelo serviço oficial W3C Markup Validation Service:

https://validator.w3.org/

Selecione a opção de envio de arquivo (*Validate by File Upload*), escolha cada arquivo `.html` e clique em **Check**. Corrija os erros apresentados e repita a validação.

## Publicação no GitHub Pages

1. Crie um repositório público no GitHub.
2. Envie os arquivos e pastas do projeto para a raiz do repositório.
3. Acesse **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha a branch `main` e a pasta `/(root)`, depois clique em **Save**.
6. Aguarde a publicação e acesse o endereço fornecido pelo GitHub Pages.

## Limitações e observações

- Este é um projeto demonstrativo. Os dados institucionais, contatos, dados financeiros e números de impacto apresentados são fictícios e devem ser substituídos antes de qualquer uso real.
- O formulário utiliza validação nativa do navegador e direciona para `obrigado.html`. Ele não armazena nem processa os cadastros em um banco de dados.
- O envio atual utiliza o método GET, portanto os valores preenchidos podem aparecer na URL. Para uso em produção, o formulário deve ser conectado a um back-end apropriado e configurado para tratar os dados com segurança.
- As regras de formato para CPF, telefone e CEP não substituem a validação completa dos dados no servidor.
- As imagens fornecidas estão em SVG. Caso a entrega exija versões em múltiplos formatos, será necessário gerar formatos adicionais quando aplicável e atualizar as referências no HTML.

## Licença

Projeto acadêmico/demonstrativo. Nenhuma licença específica foi definida.
