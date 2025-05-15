# busca-google-cse
Script de integração do mecanismo de busca do Google (CSE) em sites simples

# Integração de Busca com Google CSE (Custom Search Engine)
Este projeto contém um exemplo funcional de integração com o mecanismo de busca personalizado do Google (CSE), ideal para sites simples que não possuem backend ou banco de dados.

## 🧠 Contexto
Este script foi desenvolvido para resolver uma demanda de campo de busca funcional em um site institucional hospedado na LocaWeb, utilizando o Criador de Sites — uma plataforma com recursos limitados para personalização.

## 🔧 Como funciona
A integração utiliza o recurso de busca personalizada do Google, exibindo resultados de pesquisa dentro do seu próprio site (em sites compatíveis).

### Exemplo de uso:
```html
<!-- Google Search Engine - busca externa -->
<script async src="https://cse.google.com/cse.js?cx=SEU_ID_CSE_AQUI"></script>
<div class="gcse-search"></div>

**Substitua SEU_ID_CSE_AQUI pelo ID da sua instância CSE criada no Google.**
Exemplo: a4b2062aef0654b65


⚠️ Limitações
Não funciona em plataformas fechadas, como o Criador de Sites da LocaWeb, que restringem scripts e integrações externas.
Para usar corretamente, é necessário hospedar em um ambiente que aceite HTML, JS e código externo (como hospedagens com FTP, GitHub Pages, Netlify, etc).

✅ Tecnologias Utilizadas
Google Custom Search Engine (CSE)
HTML5
JavaScript (básico)

📁 Arquivos
index.html – [Ver index.html](./index.html)

✍️ Autor
Rafael Damasceno
[LinkedIn](https://www.linkedin.com/in/rafael-damasceno-22539b2a8/)
