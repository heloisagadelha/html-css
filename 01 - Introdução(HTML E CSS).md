# 📗 Aula — Introdução a HTML e CSS (Capítulo 3)  

> Observação: HTML e CSS **não são linguagens de programação** — HTML é uma *linguagem de marcação* e CSS são *folhas de estilo em cascata*.

---

## 🧩 Por que as três juntas?
- **HTML** provê o conteúdo.
- **CSS** deixa o conteúdo visualmente atrativo.
- **JavaScript** controla interações.  
Aprender as três em conjunto é fundamental para construir sites completos.

---

## 🔤 Terminologia importante
- **Tag** — marca delimitada por `<` e `>` (ex.: `<h1>`, `<p>`, `<img>`).
- **Atributo** — informação dentro da tag (ex.: `src="foto.png"`).
- **Valor** — conteúdo do atributo (ex.: `"foto.png"`).
- **Seletores (CSS)** — alvo das regras (ex.: `h1`, `.classe`, `#id`).
- **Declaração (CSS)** — `propriedade: valor;` (ex.: `color: blue;`).

---

## 🧠 Exemplos rápidos

### HTML — estrutura mínima (HTML5)

´´´

                  <html lang="pt-BR">
                  <head>
                      <meta charset="UTF-8" />
                      <meta name="viewport" content="width=device-width, initial-scale=1.0" />
                      <title>Título da Página</title>
                  </head>
                  <body>
                      <h1>Olá, mundo!</h1>
                      <p>Este é um parágrafo de exemplo.</p>
                      <img src="exemplo.png" alt="Descrição da imagem" />
                  </body>
                  </html>
´´´



## 📝 Resumo da Aula – Símbolos e Emojis em HTML.

🎯 2. Símbolos especiais (HTML Entities)

Alguns símbolos não podem ser digitados diretamente porque podem quebrar o HTML ou têm funções específicas dentro da linguagem.

Por isso, usamos entities, que começam com & e terminam com ;.

Exemplos importantes:
Símbolo	Código
<	&lt;
>	&gt;
&	&amp;
©	&copy;
®	&reg;
€	&euro;
£	&pound;
¥	&yen;

Esses códigos garantem que o navegador entenda corretamente o símbolo.

😀 3. Emojis no HTML

Para inserir emojis, usamos códigos Unicode no formato:
´´´

    &#x + CÓDIGO_DO_EMOJI;
´´´

