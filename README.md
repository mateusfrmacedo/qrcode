# QR Code Generator

<img width="1310" height="914" alt="Captura de Tela 2026-02-11 às 8 02 55 AM" src="https://github.com/user-attachments/assets/8dc6caa6-8e4f-4850-8aa5-911165e4a255" />

Um gerador de QR Codes minimalista, seguro e estático. Desenvolvido para ser rápido, responsivo e funcionar inteiramente no navegador.

🔗 **Acesse o projeto online:** [https://mateusfrmacedo.github.io/](https://mateusfrmacedo.github.io/)

## Funcionalidades

* **Design Premium:** Interface limpa inspirada no Design System da Apple (fontes SF Pro, sombras suaves, bordas arredondadas).
* **Geração Instantânea:** O QR Code é gerado em tempo real enquanto você digita ou ao pressionar Enter.
* **100% Client-Side:** Todo o processamento é feito no navegador do usuário. Seus dados nunca são enviados para um servidor externo (Privacidade total).
* **Download em Alta Qualidade:** Permite baixar o QR Code gerado em formato `.png` para uso em impressos ou web.
* **Mobile First:** O layout se adapta perfeitamente a telas de toque (iPhone/Android), prevenindo zoom indesejado em inputs.

## Tecnologias Utilizadas

* **HTML5 Semântico**
* **CSS3 Moderno** (Flexbox, Animations, Media Queries, Apple System Fonts)
* **JavaScript (ES6)**
* **Biblioteca:** `qrcode.js` (para o algoritmo de geração da matriz)

## Como funciona o Sistema

Este projeto utiliza uma abordagem **estática**. Não há backend (banco de dados ou servidor de processamento).

1.  **Input:** O usuário insere uma URL ou texto.
2.  **Processamento:** O JavaScript captura o texto e utiliza a biblioteca `qrcode.js`.
3.  **Renderização:** A biblioteca converte o texto em uma matriz binária (preto e branco) e desenha o resultado em um elemento HTML (Canvas ou Img) dentro do DOM.
4.  **Correção de Erro:** O sistema está configurado com `CorrectLevel.H` (High), permitindo que o QR Code seja lido mesmo se 30% dele estiver danificado ou coberto.

## Como rodar localmente

1.  Clone este repositório:
    ```bash
    git clone [https://github.com/mateusfrmacedo/nome-do-seu-repositorio.git](https://github.com/mateusfrmacedo/nome-do-seu-repositorio.git)
    ```
2.  Abra o arquivo `index.html` no seu navegador preferido.

---

Projeto desenvolvido com foco em UI/UX e simplicidade.
