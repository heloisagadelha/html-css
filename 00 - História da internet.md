# 📚 Aula – História da Internet  

## 🧭 Visão Geral

---

## 🕰️ 1. Origem da Internet
- A internet nasceu durante a **Guerra Fria**, como solução militar para comunicação segura.
- Os EUA temiam perder informações em um ataque às bases militares.
- A ARPA criou a **ARPANET**, primeira rede de computadores interligados.

---

## 🖥️ 2. ARPANET – Primeira Rede
- Iniciou com **4 computadores** de fabricantes distintos (SDS, IBM, DEC).
- Máquinas não se comunicavam naturalmente → faltava um idioma comum.
- Surgiu o **NCP (Network Control Protocol)**, simples e limitado.

---

## 🔌 3. Evolução dos Protocolos
Com o crescimento da rede:

- **TCP (Transmission Control Protocol)**  
  Fragmenta dados em pacotes e garante entrega.

- **IP (Internet Protocol)**  
  Identifica máquinas e define os endereços.

- **TCP/IP**  
  Conjunto que se tornou o padrão da internet moderna.

---

## 🌍 4. Expansão Global e Organização
- Em 1977 ocorreu comunicação via satélite entre EUA e Londres.
- A ARPANET cresceu e foi dividida:
  - **MILNET** (militar)  
  - **NSFNET** (científica)  
  - Redes comerciais  

- Surge o conceito **internetworking → Internet**.

---

## 🌐 5. Infraestrutura Física da Internet
- O tráfego internacional é feito majoritariamente por **cabos submarinos de fibra óptica**.
- Complementos: satélites, antenas, redes móveis e balões de comunicação.
- A internet é um *conjunto de redes conectadas*, não uma única rede.

---

## 📦 6. Como os Dados Viajam
- O TCP divide informações em **pacotes**.
- Pacotes seguem rotas diferentes e chegam fora de ordem.
- O receptor reorganiza e reconstrói a mensagem.
- Por isso sites/vídeos podem carregar aos poucos.

---

## 📟 7. Antes da Web: Protocolo Gopher
- Navegação totalmente em texto, sem imagens.
- Sem mouse, apenas teclado.
- Base da internet antes da web gráfica.

---

## 🌐 8. A Revolução: Tim Berners-Lee
Criou em 1993:

- **HTTP** – protocolo da web  
- **HTML** – linguagem de marcação  
- **WWW (World Wide Web)** – camada de hipertexto sobre a internet  

Isso permitiu páginas gráficas, links clicáveis e navegadores.

Primeiro navegador popular: **Mosaic**.

---

## 🌐 9. Internet x WWW
- **Internet:** estrutura global de comunicação.  
- **WWW:** parte da internet que usa HTTP e HTML para exibir páginas.  

A Web é **uma sub-rede dentro da Internet**.

---

## 🔗 10. Protocolos Importantes
- **HTTP/HTML** — Web  
- **FTP** — Arquivos  
- **SMTP/POP3/IMAP** — E-mail  
- **Gopher** — Histórico  

---
# 📘 Aula – Domínios, URLs, Hospedagem e Funcionamento da Web  

---

## 🌍 1. Como outras pessoas acessam o site
Existem **3 cenários**:

### ✅ Situação 1: Arquivos no servidor  
- HTML/CSS estão hospedados em **um servidor real**.  
- Você digita uma URL → DNS encontra o IP → servidor entrega o site.  
- Outras pessoas também conseguem acessar normalmente.

### ⚠️ Situação 2: Arquivos no seu computador  
- Você consegue abrir o arquivo HTML localmente.  
- Mas **ninguém mais** consegue acessar — seu PC **não é um servidor**.  
- Não existe URL nem DNS apontando para sua máquina.

### ⚠️ Situação 3: Arquivos no computador de outra pessoa  
- Seu amigo acessa localmente, mas você não.  
- Sem servidor e sem URL pública → **acesso impossível** para terceiros.

👉 **Conclusão:** para que outras pessoas vejam seu site, ele deve estar:  
1. Em um **servidor**, e  
2. Acessível por meio de um **domínio/URL**.

---

## 🏷️ 2. Domínio e Hospedagem
### 🖥️ Hospedagem  
- É o “lugar” onde seus arquivos ficam armazenados.  
- Pode ser gratuita (GitHub Pages) ou profissional (paga).  
- É como pagar por um quarto de hotel para guardar seu site.

### 🔤 Domínio  
- É o **nome único** que identifica o site (ex.: `cursoemvideo.com`).  
- Pago anualmente (média entre R$ 30 e R$ 50 ao ano).  
- Necessário para ter uma URL acessível para qualquer pessoa.

---

## 🌐 3. O que é uma URL?
**URL** → *Uniform Resource Locator*  
É o endereço completo que aponta para um recurso na internet.

Exemplo:

A URL pode conter:

1. **Protocolo** → `http` ou `https`  
2. **Subdomínio** → `www`  
3. **Domínio** → `github.com`  
4. **Caminho (path)** → `/GustavoGuanabara`

Quando você compra um domínio, você compra **apenas**:

github.com

O subdomínio pode variar:
- `www.github.com`
- `blog.github.com`
- `api.github.com`

---

## 🏁 4. TLD — Top Level Domain
O final do domínio (`.com`, `.br`, `.io`, `.edu`, etc.) é o **TLD**.

### Tipos:
### 📌 GTLD – *Generic Top Level Domain*
- `.com`
- `.net`
- `.info`
- `.store`
- `.online`
- `.io` (muito usado em tecnologia)

### 📌 CCTLD – *Country Code Top Level Domain*
Representam países:
- `.br` — Brasil  
- `.us` — EUA  
- `.uk` — Reino Unido  
- `.tv` — Tuvalu (muito usado por canais de TV)

---

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
```html
<!DOCTYPE html>
<html lang="pt-BR">
  <head>
    <meta charset="utf-8" />
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









