# Formulários de Cadastro - HTML

Este repositório contém três formulários HTML desenvolvidos para fins de aprendizado e demonstração de diferentes elementos de entrada de dados em formulários web. Abaixo está a descrição de cada um dos três arquivos HTML incluídos.

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

## 📄 Outros Exemplos de Formulários

Arquivos:
- [`button e seus tipos/button e seus tipos.html`](button%20e%20seus%20tipos.html)
- [`button e seus tipos/select e seus tipos.html`](select%20e%20seus%20tipos.html)
- [`button e seus tipos/textura.html`](textura.html)

### Descrição:
Formulários variados demonstrando diferentes tipos de campos de entrada, seleção múltipla, áreas de texto e botões.

---

## 💡 Considerações Finais

Esses formulários são exemplos simples e podem ser aprimorados com:

- Validações JavaScript.
- Definição adequada dos métodos HTTP (`POST` ou `GET`).
- Estilização com CSS.
- Integração com backend (PHP, Node.js, Python, etc.).

---

## 🧾 Licença

Este projeto é livre para fins educacionais.

