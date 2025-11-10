# 💻 Trilha 02 — HTML #02 — Fase 01

## Aula 05–09 | Estrutura e Conteúdo: Parágrafos, Listas, Landmarks e Imagens

### 🗓️ Data

05 de novembro de 2025

---

## 🎯 Objetivo da Aula

Dar continuidade à estrutura base do HTML e iniciar a construção do **protótipo JornadaDev — Perfil/Portfólio**, aplicando elementos semânticos e boas práticas de acessibilidade.

Protótipo no Figma:  
👉 [JornadaDev - Perfil/Portfólio](https://www.figma.com/design/QvPDepxv6IxxFhkk3ZGyjE/JornadaDev---Perfil-Portifolio?node-id=2-15&t=j9io0jK2z2GGICHo-1)

---

## 🧱 Conteúdo Abordado

### 1. **Elemento Parágrafo `<p>`**

- Criação e organização de blocos de texto.
- Separação semântica de ideias e tópicos.
- Boas práticas: evitar uso excessivo de `<br>` e manter legibilidade.

```html
<p>Sou um desenvolvedor apaixonado por tecnologia e ensino.</p>
<p>Atualmente estou aprendendo HTML, CSS e JavaScript.</p>
```

---

### 2. **Listas `<ul>`, `<ol>` e `<li>`**

- Diferença entre listas ordenadas e não ordenadas.
- Uso de listas para representar experiências, habilidades e etapas do projeto.

```html
<h3>Minhas skills</h3>
<ul>
  <li>Desenvolvimento front-end</li>
  <li>Desenvolvimento back-end</li>
  <li>Administrador de banco</li>
</ul>

<ol>
  <li>PHP</li>
  <li>
    JAVASCRIPT
    <ol>
      <li>NODEJS</li>
      <li>REACTJS</li>
      <li>REACT NATIVE</li>
    </ol>
  </li>
  <li>C#</li>
  <li>.NET</li>
</ol>
```

---

### 3. **Landmarks HTML**

- Estrutura semântica aplicada: `<header>`, `<main>`, `<footer>`.
- O elemento `<main>` é **obrigatório** para acessibilidade.
- O `<header>` apresenta o logotipo e título.
- O `<footer>` contém os créditos e direitos autorais.

```html
<header>
  <img src="logotipo.png" alt="Logotipo do portifolio JornadaDev" />
</header>

<main>
  <img
    src="https://github.com/nicholasmacedoo.png"
    height="120"
    alt="Foto perfil"
  />
  <h1>Nome do aluno</h1>
  <p>Desenvolvedor</p>
  <!-- Conteúdo e listas -->
</main>

<footer>
  <p>Todos os direitos reservados @ lab365 - 2025</p>
</footer>
```

---

### 4. **Imagens `<img>`**

- Atributos utilizados: `src`, `alt`, `height`, `width`.
- Importância do `alt` para acessibilidade e SEO.

```html
<img
  src="https://github.com/nicholasmacedoo.png"
  height="120"
  alt="Foto perfil"
/>
```

---

### 5. **Validação com W3C Validator**

- Validação feita no site [validator.w3.org](https://validator.w3.org/).
- Corrigidos avisos de acessibilidade e estrutura, garantindo o uso correto do `<main>` e dos elementos semânticos.

---

## 🧠 Resultados da Aula

- Página HTML validada e organizada sem erros de acessibilidade.
- Aplicação prática de **landmarks**, **listas** e **parágrafos**.
- Início da estrutura do **portfólio JornadaDev** no HTML.
- Base pronta para evoluir nas próximas aulas com **CSS e estilização**.

---

## 🚀 Próximos Passos

- Aprimorar a identidade visual com CSS.
- Adicionar seções e componentes do protótipo Figma.
- Preparar o portfólio para integração com projetos e links externos.
