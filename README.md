# CURSO-HTML-5-DIO

# Formulários de Cadastro - HTML

Este repositório contém vários exemplos de formulários e recursos HTML desenvolvidos para fins de aprendizado e demonstração de diferentes elementos de entrada de dados e recursos visuais em páginas web.

---

## 📄 Formulário 1 - `formulario1.html`

### Descrição:
Este formulário básico de cadastro possui os seguintes campos:

- **Nome**: Campo de texto simples.
- **Cargo**: Lista de seleção múltipla (`<select multiple>`) com diversas opções de cargos.
- **Assunto**: Campo de texto simples.
- **Botão "Enviar"**: Para submeter os dados (sem ação definida).

### Observações:
- Não possui validações.
- O atributo `method` do formulário não foi definido.
- O atributo `onsubmit` está vazio, sem ação ao submeter.

---

## 📄 Formulário 2 - `formulario2.html`

### Descrição:
Este formulário possui um conjunto mais completo de entradas e utiliza o método `GET` para envio dos dados:

- **Nome**: Campo obrigatório.
- **Idade**: Campo obrigatório e do tipo numérico.
- **Senha**: Campo obrigatório com entrada oculta (`password`).
- **Sexo**: Campo de texto desabilitado (não editável).
- **Botão "Enviar"**: Para submeter o formulário via URL.

### Observações:
- Utiliza validações HTML5 com o atributo `required`.
- A senha é enviada via URL (por ser `GET`), o que não é seguro em aplicações reais.

---

## 📄 Formulário 3 - `formulario3.html`

### Descrição:
Este formulário é uma variação do Formulário 1 com campos adicionais para entrada de texto livre:

- **Nome**: Campo de texto.
- **Cargo**: Seleção múltipla.
- **Assunto**: Campo de área de texto (`<textarea>`).
- **Mensagem**: Outro campo de área de texto.
- **Botão "Enviar"**: Para envio dos dados.

### Observações:
- Também não define `method` nem `onsubmit`.
- Mais adequado para coleta de mensagens ou feedbacks mais longos.

---

## 📄 Checkbox e Radio

Arquivo: [`Checkbox e Radio/index.html`](../../Checkbox%20e%20Radio/index.html)

### Descrição:
Formulário para seleção de opcionais de pizza, borda recheada e bebida, utilizando checkboxes e radio buttons.

- **Opcionais**: Seleção múltipla com checkboxes.
- **Borda recheada**: Escolha única com radio.
- **Bebida**: Escolha única com radio.
- **Botão "Enviar pedido"**: Para submeter o pedido.

---

## 📄 Formatação de Textos

Arquivos:
- [`formatando textos/parte1.html`](../../formatando%20textos/parte1.html)
- [`formatando textos/parte2.html`](../../formatando%20textos/parte2.html)
- [`formatando textos/Div e Span.html`](../../formatando%20textos/Div%20e%20Span.html)
- [`formatando textos/fieldset.html`](../../formatando%20textos/fieldset.html)

### Descrição:
Exemplos de uso de tags de formatação de texto, como `<b>`, `<i>`, `<u>`, `<mark>`, `<small>`, `<sup>`, `<sub>`, `<blockquote>`, `<div>`, `<span>`, e `<fieldset>`. Incluem também exemplos de agrupamento de campos em formulários.

---

## 📄 Introdução ao HTML na Prática

Arquivos:
- [`introdução ao html na prática/index.html`](../../introdução%20ao%20html%20na%20prática/index.html)
- [`introdução ao html na prática/sobre.html`](../../introdução%20ao%20html%20na%20prática/sobre.html)

### Descrição:
Demonstração prática de elementos básicos do HTML, como imagens, links, listas, títulos, parágrafos e atributos.

---

## 📄 Exemplos com Iframes e Cores

Arquivos:
- [`introdução ao html na prática/Iframes.html`](introdução%20ao%20html%20na%20prática/Iframes.html)
- [`introdução ao html na prática/Resenha Cores.html`](introdução%20ao%20html%20na%20prática/Resenha%20Cores.html)

### Descrição:
Demonstrações práticas de recursos visuais em HTML:

- **Iframes.html**: Mostra como incorporar mapas, vídeos e outros conteúdos externos usando a tag `<iframe>`, com exemplos do Google Maps e YouTube.
- **Resenha Cores.html**: Exemplo visual de sobreposição de elementos (cards) com CSS, simulando resenhas de cores e explorando posicionamento absoluto e estilização.

---

## 📄 Outros Exemplos de Formulários

Arquivos:
- [`button e seus tipos/button e seus tipos.html`](button%20e%20seus%20tipos.html)
- [`button e seus tipos/select e seus tipos.html`](select%20e%20seus%20tipos.html)
- [`button e seus tipos/textura.html`](textura.html)

### Descrição:
Formulários variados demonstrando diferentes tipos de campos de entrada, seleção múltipla, áreas de texto e botões.

---

## 📄 Novos Exemplos de Mídia

Arquivos:
- [`tag.audio.html`](tag.audio.html)
- [`tag.img.html`](tag.img.html)
- [`tag.video.html`](tag.video.html)
- [`tag.table.html`](tag.table.html)

### Descrição:
Demonstrações de como incorporar mídia em páginas HTML:

- **tag.audio.html**: Exibe um player de áudio com múltiplas fontes e fallback para navegadores não suportados.
- **tag.img.html**: Exibe diferentes formatos de imagens (JPEG, PNG, SVG) com atributos de acessibilidade e estilos.
- **tag.video.html**: Exibe um player de vídeo com múltiplas fontes e legendas em diferentes idiomas usando a tag `<track>`.
- **tag.table.html**: Exemplo de tabela HTML estilizada com CSS, linhas alternadas coloridas e destaque ao passar o mouse.

---

## 💡 Considerações Finais

Esses formulários e exemplos são simples e podem ser aprimorados com:

- Validações JavaScript.
- Definição adequada dos métodos HTTP (`POST` ou `GET`).
- Estilização com CSS.
- Integração com backend (PHP, Node.js, Python, etc.).

---

## 🧾 Licença

Este projeto é livre para fins educacionais.

---

## 📄 Desafio: Site Clínica Vida Plena

Arquivo:
- [`desafio.html`](desafio.html)

### Descrição:
Site completo de uma clínica médica, criado como desafio prático para aplicar todos os conceitos do módulo de HTML. O site inclui:

- **Menu de navegação**: Acesso rápido para todas as páginas principais.
- **Página Principal**: Imagem de destaque e breve apresentação da clínica.
- **Sobre a Clínica**: Imagem institucional e texto sobre a história e missão.
- **Horário de Atendimento**: Imagem temática, texto explicativo e tabela de horários por especialidade e dia da semana.
- **Contato**: Imagem de agenda, telefones, endereço, mapa incorporado (Google Maps) e formulário de contato com campos para nome, e-mail, assunto e mensagem.

#### Recursos utilizados:
- Estruturação semântica com `<header>`, `<nav>`, `<section>`, `<footer>`, etc.
- Formatação de textos e títulos.
- Inclusão de imagens e mídias.
- Tabela de horários estilizada.
- Formulário de contato completo.
- Iframe para mapa.
- Responsividade básica via CSS.

---

