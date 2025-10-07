# De HTML ao React — Ebook (inteiramente gerado por IA)

Resumo curto
Este ebook guia a jornada do desenvolvimento web — do HTML estático ao React moderno — com explicações, exemplos de código e exercícios práticos. Todo o conteúdo foi gerado e organizado por ferramentas de Inteligência Artificial.

Índice
- [Sobre este projeto](#sobre-este-projeto)
- [Resumo do conteúdo](#resumo-do-conte%C3%BAdo)
- [Estrutura do ebook](#estrutura-do-ebook)
- [Exemplos e exercícios destacados](#exemplos-e-exerc%C3%ADcios-destacados)
- [Como foi gerado (workflow de IA)](#como-foi-gerado-workflow-de-ia)
- [Como executar os exemplos](#como-executar-os-exemplos)
- [Próximos passos e sugestões de estudo](#pr%C3%B3ximos-passos-e-sugest%C3%B5es-de-estudo)
- [Contribuições](#contribui%C3%A7%C3%B5es)
- [Licença](#licen%C3%A7a)
- [Créditos](#cr%C3%A9ditos)

## Sobre este projeto
Este repositório reúne o material do ebook "De HTML ao React". O propósito é oferecer um guia prático e direto para iniciantes e desenvolvedores que desejam migrar do desenvolvimento web tradicional (HTML/CSS/JavaScript) para o ecossistema moderno com React.

Observação importante: todo o conteúdo (texto, exemplos e exercícios) foi gerado por ferramentas de IA. Recomenda-se revisão humana antes de uso acadêmico ou comercial.

## Resumo do conteúdo
- Parte 1 — Fundamentos da Web: história breve, estrutura do HTML e exemplos introdutórios.
- Parte 1 (CSS) — Estilizando a Web: conceitos de CSS, separação de conteúdo e apresentação, regras básicas e responsividade.
- Parte 2 — JavaScript e ES6+: manipulação do DOM, eventos e recursos modernos do JavaScript (arrow functions, template strings, etc.).
- Parte 3 — React (básico): componentes funcionais, JSX e criação de interfaces declarativas.
- Parte 3 — Props e Estado: passagem de dados por props e gerenciamento de estado com `useState`.
- Parte 4 — Hooks avançados: `useContext`, `useReducer`, `useMemo` e padrões de arquitetura.
- Parte 5 — Conclusão e próximos passos: recomendações para aprofundamento (Next.js, TypeScript, testes) e sugestões de mini-projetos.

## Estrutura do ebook
- Parte 1 – Fundamentos da Web
  - HTML básico (<!DOCTYPE html>, `<h1>`, `<p>`)
  - Exercícios iniciais
- Parte 1 – CSS: Estilizando a Web
  - Seletores, propriedades básicas, layout e responsividade
- Parte 2 – JavaScript (introdução e ES6+)
  - DOM, eventos, arrow functions e template strings
- Parte 3 – React (introdução)
  - Componentes, JSX, configuração inicial (Vite/CRA)
- Parte 3 – Props e Estado
  - Props, `useState`, exemplos práticos (saudação, contador)
- Parte 4 – Hooks Avançados
  - `useContext`, `useReducer`, `useMemo` e exemplos de padrões
- Parte 5 – Conclusão e Próximos Passos
  - Projetos sugeridos e caminhos de evolução

## Exemplos e exercícios destacados
HTML de exemplo:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>Exemplo Simples</title>
  </head>
  <body>
    <h1>Olá Mundo!</h1>
    <p>Bem-vindo ao desenvolvimento web.</p>
  </body>
</html>
```

CSS de exemplo:

```css
h1 {
  color: blue;
  text-align: center;
}
p {
  font-size: 16px;
  line-height: 1.5;
}
```

JavaScript de exemplo (interação simples):

```html
<script>
function mostrarMensagem() {
  alert("Olá, esta é uma interação com JavaScript!");
}
</script>
<button onclick="mostrarMensagem()">Clique aqui</button>
```

React (exemplos):

```jsx
function App() {
  return (
    <div>
      <h1>Olá, React!</h1>
    </div>
  );
}

function Saudacao(props) {
  return <h1>Olá, {props.nome}!</h1>;
}

function Contador() {
  const [contador, setContador] = React.useState(0);
  return (
    <div>
      <p>Contagem: {contador}</p>
      <button onClick={() => setContador(contador + 1)}>Incrementar</button>
    </div>
  );
}
```

Exercícios sugeridos (seleção):
- Crie uma página HTML com título e parágrafo.
- Estilize elementos com CSS (ex.: mudar cor de fundo, responsividade).
- Crie funções JS que interajam com o DOM.
- Instale React (Vite/CRA) e crie um componente que mostre seu nome.
- Implemente um contexto simples de autenticação com `useContext`.
- Desenvolva um mini-projeto em React (to-do list, calculadora, portfólio).

## Como foi gerado (workflow de IA)
O material foi produzido com ferramentas de geração de texto e snippets de código via modelos de linguagem e assistentes de código. Um fluxo típico inclui:

1. Geração da estrutura (sumário) por prompts.
2. Criação dos capítulos com exemplos de código e exercícios.
3. Refinamento iterativo para clareza e consistência.
4. Montagem e exportação para publicação (PDF/HTML).

Ferramentas típicas (atualize conforme aplicável): modelos de linguagem (ex.: GPT-family), assistentes de codificação, geradores de imagem (opcional) e conversores de documento para PDF.

Transparência: recomenda-se revisão humana antes de publicar ou usar comercialmente o conteúdo.

## Como executar os exemplos
Para experimentar os exemplos React (recomendado usar Vite):

```bash
npm create vite@latest my-ebook-demo -- --template react
cd my-ebook-demo
npm install
npm run dev
```

Depois, copie os componentes de exemplo para `src/` e abra o endereço indicado pelo Vite.

Para executar exemplos HTML/CSS/JS simples:
- Abra o arquivo `.html` no navegador ou use um servidor estático simples:

```bash
python -m http.server 3000
# ou
npx serve .
```

## Próximos passos e sugestões de estudo
- Aprofundar em Next.js (SSR/SSG) e rotas avançadas.
- Aprender TypeScript para tipagem estática em projetos React.
- Escrever testes com Jest e React Testing Library.
- Construir projetos práticos para consolidar o aprendizado.

## Contribuições
Mesmo sendo um ebook gerado por IA, contribuições são bem-vindas:
- Corrigir ou melhorar explicações.
- Substituir exemplos por versões mais avançadas.
- Adicionar demos ao vivo (CodeSandbox, Vercel/Netlify).

Abra uma issue para propor mudanças ou envie um PR com suas melhorias.

## Licença
Sugestão: MIT. Substitua YEAR e NomeDoAutor conforme necessário.

```
MIT License
Copyright (c) YEAR NomeDoAutor

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:
```

## Créditos
Conteúdo gerado por ferramentas de Inteligência Artificial e organizado neste repositório. Revisão e curadoria final por você ou pelo mantenedor do projeto.

---

Se quiser, eu posso:
- Atualizar a seção de ferramentas com os nomes exatos das ferramentas que você usou.
- Gerar uma versão curta do README (um parágrafo) ou uma versão em inglês.
- Adicionar badges (AI-generated, license) e um sumário automático.
