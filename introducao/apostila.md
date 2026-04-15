🎨 GUIA CSS (BÁSICO → INTERMEDIÁRIO) 


🔹 1. O que é CSS? 

CSS (Cascading Style Sheets) é a linguagem usada para estilizar páginas HTML. 

👉 Ele controla: 

Cores 🎨  

Tamanhos 📏  

Espaçamentos 📦  

Layout 📐  

 

🔹 2. Como usar CSS 

🔸 1. Inline (não recomendado) 

<p style="color: red;">Texto</p> 

 

🔸 2. Interno 

<style> 
p { 
 color: red; 
} 
</style> 

 

🔸 3. Externo (melhor prática ✅) 

<link rel="stylesheet" href="style.css"> 

 

🔹 3. Sintaxe básica 

seletor { 
 propriedade: valor; 
} 

Exemplo: 

p { 
 color: blue; 
 font-size: 16px; 
} 

 

🔹 4. Principais seletores 

🔸 Por elemento 

p { 
 color: red; 
} 

🔸 Por classe 

.destaque { 
 color: green; 
} 

<p class="destaque">Texto</p> 

 

🔸 Por ID 

#titulo { 
 color: purple; 
} 

<h1 id="titulo">Título</h1> 

 

🔸 Seletores combinados 

div p { 
 color: orange; 
} 

 

🔹 5. Cores no CSS 

color: red; 
color: #ff0000; 
color: rgb(255, 0, 0); 

 

🔹 6. Texto e fontes 

p { 
 font-family: Arial; 
 font-size: 18px; 
 font-weight: bold; 
 text-align: center; 
} 

 

🔹 7. Box Model (MUITO IMPORTANTE 🔥) 

Todo elemento é uma caixa: 

div { 
 width: 200px; 
 padding: 10px; 
 border: 2px solid black; 
 margin: 20px; 
} 

📦 Ordem: 

Conteúdo  

Padding  

Border  

Margin  

 

🔹 8. Display 

display: block; 
display: inline; 
display: inline-block; 
display: none; 

👉 Controle de comportamento do elemento 

 

🔹 9. Flexbox (INTERMEDIÁRIO 🔥) 

👉 Para organizar layout facilmente 

.container { 
 display: flex; 
 justify-content: center; 
 align-items: center; 
} 

Principais propriedades: 

justify-content → horizontal  

align-items → vertical  

 

🔹 10. Grid (noção básica) 

.container { 
 display: grid; 
 grid-template-columns: 1fr 1fr; 
} 

👉 Cria layouts em grade 

 

🔹 11. Pseudo-classes 

a:hover { 
 color: red; 
} 

👉 Ação do usuário (mouse, clique, etc.) 

 

🔹 12. Responsividade (básico) 

@media (max-width: 600px) { 
 body { 
   background-color: lightgray; 
 } 
} 

👉 Adapta para celular 📱 

 

🔹 13. Boas práticas 

✅ Use CSS externo 
✅ Use classes (evite muitos IDs) 
✅ Organize o código 
✅ Comente quando necessário 

 