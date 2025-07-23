# Gerador de QR Code 

<p align="center">
  <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
  <img alt="CSS3" src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
  <img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
</p>

<p align="center">
  <a href="https://daniela02s.github.io/gerador-qrCode/" target="_blank">
    <strong>➡️ Acessar a demonstração ao vivo</strong>
  </a>
</p>

## 📝 Descrição

Este é um projeto de uma aplicação web simples e intuitiva para criar QR Codes instantaneamente. Basta inserir qualquer texto ou URL no campo indicado e clicar no botão para que o código seja gerado e exibido na tela, pronto para ser escaneado.

---

## ✨ Funcionalidades

* **Geração Instantânea:** Crie QR Codes a partir de qualquer texto ou link.
* **Interface Limpa:** Design minimalista e focado na usabilidade.
* **Responsividade:** Funciona bem em diferentes tamanhos de tela (desktop e mobile).
* **Feedback Visual:** A interface mostra o QR Code gerado de forma clara e destaca o campo de input quando ativo.

---

## 🚀 Tecnologias Utilizadas

O projeto foi construído utilizando tecnologias web fundamentais e uma API pública para a geração dos códigos.

* **HTML5:** Para a estrutura semântica da página.
* **CSS3:** Para a estilização, layout e responsividade.
* **JavaScript:** Para toda a lógica de interatividade, captura de eventos e comunicação com a API.
* **API Pública:** [QR Code API](https://goqr.me/api/) para a conversão do texto em imagem de QR Code.

---

## 🤔 Como Funciona

1.  O usuário digita o texto ou URL desejada no campo de input.
2.  Ao clicar no botão "Gerar QR Code", um evento de clique é acionado.
3.  O JavaScript captura o valor do input.
4.  Se o campo não estiver vazio, uma requisição é feita para a API `https://api.qrserver.com/v1/create-qr-code/`, passando o texto do usuário como um parâmetro na URL.
5.  A API retorna uma imagem do QR Code correspondente.
6.  O JavaScript atualiza a `src` da tag `<img>` no HTML, exibindo o QR Code para




