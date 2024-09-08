# Aplicação Web: Busca de Animes

**Descrição:**

Esta aplicação web simples permite que os usuários busquem por animes em uma base de dados (**dados**) e exiba os resultados relevantes. A interface é intuitiva e fácil de usar, com um campo de pesquisa e uma seção para exibir os resultados.

**Funcionalidades:**

* **Pesquisa por palavras-chave:** O usuário pode digitar palavras-chave relacionadas ao anime desejado no campo de pesquisa.
* **Resultados dinâmicos:** A aplicação busca por correspondências nas propriedades "título", "descrição" e "tags" dos animes na base de dados e exibe os resultados em tempo real.
* **Exibição detalhada:** Para cada anime encontrado, são exibidos o título, uma breve descrição e um link para mais informações.

**Tecnologias Utilizadas:**

* **HTML:** Estrutura básica da página, definindo os elementos da interface do usuário.
* **CSS:** Estilização da página, responsável pela aparência visual.
* **JavaScript:** Lógica da aplicação, incluindo a função de pesquisa e a manipulação do DOM para exibir os resultados.

**Como Usar:**

1. **Clonar o repositório:** Clone este repositório para sua máquina local utilizando o Git.
2. **Abrir o arquivo HTML:** Abra o arquivo `index.html` em um navegador web.
3. **Realizar uma pesquisa:** Digite o nome do anime ou palavras-chave relacionadas no campo de pesquisa e clique no botão "Pesquisar".
4. **Visualizar resultados:** Os resultados da pesquisa serão exibidos abaixo do campo de pesquisa.

**Estrutura de Dados (dados):**

A aplicação utiliza um array de objetos chamado `dados` para armazenar as informações sobre os animes. Cada objeto possui as seguintes propriedades:

* `titulo`: Título do anime.
* `descricao`: Breve descrição do anime.
* `tags`: Palavras-chave relacionadas ao anime.
* `link`: Link para mais informações sobre o anime.

**Exemplo de um objeto em dados:**

```javascript
{
  "titulo": "My Hero Academia",
  "descricao": "Um mundo onde a maioria das pessoas possuem superpoderes...",
  "tags": ["shonen", "super-herois", "escola"],
  "link": "[https://www.example.com/my-hero-academia](https://www.example.com/my-hero-academia)"
}
```
**Obrigado**
