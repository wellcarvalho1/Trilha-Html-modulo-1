# Elementos HTML: div, span, fieldset, embed e iframe

Este repositório explora o uso de elementos HTML importantes para estruturação e incorporação de conteúdo: `<div>`, `<span>`, `<fieldset>`, `<embed>` e `<iframe>`.

## Elementos de estruturação

* **`<div>` (Division):** Um elemento de bloco de nível de contêiner, usado para agrupar outros elementos HTML.  Primariamente utilizado para fins de estilo (aplicando CSS) ou manipulação com JavaScript.  É um elemento genérico sem significado semântico.

    ```html
    <div id="meu-container">
        <p>Conteúdo dentro da div</p>
    </div>
    ```

* **`<span>` (Inline Container):** Um elemento inline usado para agrupar texto ou outros elementos inline.  Assim como a `<div>`, o `<span>` é usado principalmente para aplicar estilos ou para manipulação com JavaScript e não possui significado semântico inerente.

    ```html
    <p>Este é um <span class="destaque">texto destacado</span>.</p>
    ```

* **`<fieldset>` (Fieldset):** Um elemento de bloco usado para agrupar elementos de formulário relacionados, geralmente com uma legenda (`<legend>`).  Oferece melhor estrutura semântica para formulários, agrupando campos logicamente.

    ```html
    <fieldset>
        <legend>Informações Pessoais</legend>
        <label for="nome">Nome:</label>
        <input type="text" id="nome" name="nome">
    </fieldset>
    ```

## Elementos de incorporação

* **`<embed>` (Embed):**  Incorpora conteúdo externo, como vídeos, PDFs ou outros recursos web. O suporte e os recursos podem variar entre navegadores.  Para incorporar vídeos, a tag `<video>` é geralmente preferível por oferecer mais controle e melhor compatibilidade.

    ```html
    <embed src="video.mp4" width="400" height="300" type="video/mp4">
    ```

* **`<iframe>` (Inline Frame):** Permite incorporar outro documento HTML dentro do documento atual. Útil para incorporar conteúdo de outros sites, mapas, vídeos e outros recursos web.

    ```html
    <iframe src="https://www.example.com" width="600" height="400"></iframe>
    ```

## Recursos adicionais

* [MDN Web Docs: div](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/div)
* [MDN Web Docs: span](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/span)
* [MDN Web Docs: fieldset](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/fieldset)
* [MDN Web Docs: embed](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/embed)
* [MDN Web Docs: iframe](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/iframe)


## Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para abrir um pull request com melhorias ou correções.