# 🌸 Pink Google Search

![Status](https://img.shields.io/badge/status-concluído-brightgreen?style=flat-square)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222222?style=flat-square&logo=githubpages&logoColor=white)
![CS50W](https://img.shields.io/badge/CS50W-Project%200-0057b7?style=flat-square)

> Projeto 0 do curso **CS50's Web Programming with Python and JavaScript** - Um clone da página de pesquisa do Google com tema rosa personalizado.

---

##  Sobre o Projeto

Este projeto foi desenvolvido como parte do **Projeto 0** do curso **CS50’s Web Programming with Python and JavaScript** (CS50W), oferecido por Harvard.

O objetivo foi recriar as funcionalidades básicas da página de pesquisa do Google utilizando apenas **HTML** e **CSS**, demonstrando compreensão de:

- Estruturação de páginas web
- Estilização com CSS
- Criação de formulários
- Navegação entre páginas
- Consistência visual

### 🌸 Tema Rosa

A versão disponível neste repositório apresenta um **tema rosa personalizado**, escolhido para explorar customização de CSS e identidade visual. O projeto também atende a todos os requisitos funcionais do curso.

---

##  Funcionalidades

| Funcionalidade | Descrição |
|----------------|-----------|
| 🔍 **Pesquisa Google** | Barra de pesquisa centralizada com cantos arredondados |
| 🖼️ **Pesquisa de Imagens** | Busca imagens diretamente no Google Imagens |
| ⚙️ **Pesquisa Avançada** | 4 filtros para pesquisas precisas |
| 🍀 **I'm Feeling Lucky** | Vai direto ao primeiro resultado da pesquisa |

---

##  Páginas do Projeto

O site é composto por **três páginas**, conforme especificado no projeto:

| Página | Arquivo | Descrição |
|--------|---------|-----------|
| **Pesquisa Google** | `index.html` | Página principal com barra de pesquisa e botões |
| **Pesquisa de Imagens** | `imagens.html` | Busca de imagens com parâmetro `tbm=isch` |
| **Pesquisa Avançada** | `avancada.html` | Busca com 4 filtros específicos |

### Navegação

- **Página Principal**: Links para "Pesquisa de Imagens" e "Pesquisa Avançada"
- **Demais páginas**: Link "Voltar à Pesquisa Google"

---

##  Paleta de Cores

O tema rosa foi desenvolvido com a seguinte paleta:

```css
Rosa Principal:   #bd077d  /* Botões, links, títulos */
Rosa Claro:       #ff024e  /* Título "Imagens" */
Rosa Suave:       #e96c93  /* Subtítulos */
Rosa Escuro:      #8a055a  /* Labels */
Rosa Destaque:    #ed8dcd  /* Hover dos botões */
Rosa Fundo:       #f7d6ef  /* Background dos botões em hover */
```

---

##  Tecnologias Utilizadas

| Tecnologia | Uso |
|------------|-----|
| HTML5 | Estrutura semântica das páginas |
| CSS3 | Estilização, layout e design responsivo |
| Flexbox | Alinhamento e distribuição de elementos |
| GitHub Pages | Hospedagem gratuita do projeto |

---

##  Estrutura do Projeto

```
pink-google-search/
│
├── index.html          # Página principal (Pesquisa Google)
├── imagens.html        # Pesquisa de Imagens
├── avancada.html       # Pesquisa Avançada
├── style.css           # Estilos personalizados (tema rosa)
├── logo.png            # Logo do projeto
└── README.md           # Documentação
```

---

##  Acesse o Projeto

O projeto está disponível publicamente em:

https://luuuu1208.github.io/pink-google-search/index.html

---

## 📋 Requisitos Atendidos

| Requisito | Status |
|-----------|--------|
| 3 páginas (Pesquisa, Imagens, Avançada) | ✅ |
| Links de navegação no canto superior direito | ✅ |
| Pesquisa de texto funcional | ✅ |
| Pesquisa de imagens funcional | ✅ |
| 4 campos na pesquisa avançada | ✅ |
| Campos alinhados verticalmente | ✅ |
| Botão "I'm Feeling Lucky" | ✅ |
| Botão "Advanced Search" estilizado | ✅ |
| Estética consistente | ✅ |

---

##  Detalhes Técnicos

### Pesquisa de Imagens
```html
<input type="hidden" name="tbm" value="isch">
```
O parâmetro `tbm=isch` é enviado ao Google para ativar a pesquisa de imagens.

### Pesquisa Avançada
Os 4 campos utilizam os parâmetros corretos do Google:

- `as_q` - Todas essas palavras
- `as_epq` - Frase exata
- `as_oq` - Qualquer uma dessas palavras
- `as_eq` - Nenhuma dessas palavras

### I'm Feeling Lucky
```html
<input type="submit" name="btnI" value="I'm Feeling Lucky">
```
O parâmetro `btnI=1` faz o Google redirecionar diretamente ao primeiro resultado.

---

##  Aprendizados

Durante o desenvolvimento deste projeto, foram explorados conceitos fundamentais de desenvolvimento web:

- Estruturação de páginas com HTML5
- Estilização com CSS3
- Formulários e envio de dados (GET)
- Parâmetros de URL
- Design responsivo
- Consistência visual
- Versionamento com Git e GitHub

---

##  Autora

Feito por **Luuuu1208**

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/luuuu1208)

---

##  Créditos

- **Curso:** [CS50's Web Programming with Python and JavaScript](https://cs50.harvard.edu/web/)
- **Instituição:** Harvard University
- **Inspiração:** Google Search

---

##  Licença

Este projeto foi desenvolvido para fins educacionais como parte do curso CS50W.

O Google é uma marca registrada da Google LLC.
