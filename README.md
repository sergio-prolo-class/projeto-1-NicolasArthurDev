# Projeto I de Programação Front-End I de Nicolas Arthur     

Este repositório contém um site pessoal desenvolvido com HTML e CSS, apresentando informações sobre a trajetória acadêmica, profissional e interesses pessoais do autor. Abaixo estão descritos os principais recursos de HTML e CSS utilizados, com indicações de onde eles aparecem nos arquivos.

---

## **Principais Recursos de HTML**

### **1. Estrutura Semântica**
- **Descrição:** Uso de tags semânticas como `<header>`, `<nav>`, `<section>`, `<aside>` e `<footer>` para organizar o conteúdo de forma clara e acessível.
- **Localização:**
  - `index.html`: Linhas 10-90.
  - `academico.html`: Linhas 10-150.
  - `profissional.html`: Linhas 10-140.

### **2. Links e Navegação**
- **Descrição:** Uso de `<a>` para criar links internos e externos, com atributos como `href` e `target="_blank"`.
- **Localização:**
  - `index.html`: Linhas 16-20 (menu de navegação).
  - `academico.html`: Linhas 16-20 (menu de navegação) e 120-140 (links para projetos).
  - `profissional.html`: Linhas 16-20 (menu de navegação).

### **3. Listas**
- **Descrição:** Uso de `<ul>` e `<li>` para criar listas de itens, como hobbies, interesses e disciplinas.
- **Localização:**
  - `index.html`: Linhas 60-80 (hobbies e interesses).
  - `academico.html`: Linhas 70-120 (disciplinas por semestre).
  - `profissional.html`: Linhas 50-130 (habilidades desenvolvidas).

### **4. Imagens**
- **Descrição:** Uso de `<img>` para exibir imagens com atributos como `src`, `alt`, `width` e `height`.
- **Localização:**
  - `index.html`: Linhas 30-40 (imagem pessoal) e 90-110 (galeria de fotos).
  - `academico.html`: Linhas 130-140 (imagens dos projetos).
  - `profissional.html`: Linhas 120-130 (ícones de contato).

### **5. Áudio**
- **Descrição:** Uso da tag `<audio>` para incluir um player de música.
- **Localização:**
  - `index.html`: Linha 25.

---

## **Principais Recursos de CSS**

### **1. Grid Layout**
- **Descrição:** Uso de `display: grid` para organizar o layout das páginas.
- **Localização:**
  - `styles.css`: Linhas 10-20 (estrutura geral do layout).
  - `style-academico.css`: Linhas 90-100 (`#section_semestre` e `#projetos_realizados`).
  - `style-profissional.css`: Linhas 90-100 (`#section_semestre` e `#projetos_realizados`).

### **2. Flexbox**
- **Descrição:** Uso de `display: flex` para centralizar elementos e criar layouts flexíveis.
- **Localização:**
  - `styles.css`: Linhas 70-80 (centralização da imagem pessoal).
  - `style-academico.css`: Linhas 50-60 (centralização de imagens e textos).

### **3. Media Queries**
- **Descrição:** Uso de `@media` para criar estilos responsivos para diferentes tamanhos de tela.
- **Localização:**
  - `styles.css`: Linhas 30-200 (responsividade para celulares, tablets e desktops).
  - `style-academico.css`: Linhas 30-200 (responsividade para seções acadêmicas).
  - `style-profissional.css`: Linhas 30-200 (responsividade para seções profissionais).

### **4. Transições**
- **Descrição:** Uso de `transition` para criar efeitos suaves em interações, como hover.
- **Localização:**
  - `styles.css`: Linhas 150-160 (botões e imagens).
  - `style-academico.css`: Linhas 140-150 (projetos).
  - `style-profissional.css`: Linhas 140-150 (projetos).

### **5. Estilização de Links**
- **Descrição:** Uso de `text-decoration` e `color` para personalizar links.
- **Localização:**
  - `styles.css`: Linhas 50-60 (links do menu e rodapé).
  - `style-academico.css`: Linhas 50-60 (links para projetos).
  - `style-profissional.css`: Linhas 50-60 (links para contatos).

### **6. Estilização de Imagens**
- **Descrição:** Uso de `border-radius` e `object-fit` para ajustar imagens.
- **Localização:**
  - `styles.css`: Linhas 70-80 (imagem pessoal).
  - `style-academico.css`: Linhas 130-140 (imagens dos projetos).
  - `style-profissional.css`: Linhas 120-130 (ícones de contato).

---

## **Como Executar o Projeto**
1. Clone o repositório:
   ```bash
   git clone https://github.com/NicolasArthurDev/projeto-1-NicolasArthurDev.git