# Projeto Imersão Dev - Guia de Front-end

## Quem sou eu:
Meu nome é Caroline, sou estudante de Sistemas de Informação pela Estácio. Iniciei meus estudos em tecnologia em meados de 2021/2022 realizando bootcamps na área.

## Sobre o Projeto
Este projeto tem como objetivo fornecer um guia rápido e fácil de usar para desenvolvedores Front-end, com informações sobre as principais linguagens, frameworks e ferramentas utilizadas na área. A aplicação permite que o usuário busque por termos específicos e encontre recursos relevantes para seu aprendizado e desenvolvimento.

## Tecnologias Utilizadas
* **HTML:** Estrutura básica da página.
* **CSS:** Estilização da página.
* **JavaScript:** Lógica da aplicação, incluindo a função de busca.
* **Markdown:** Formatação do arquivo README.

## Como Usar

Acesse pelo link: https://imersao-dev-alura-jet.vercel.app/
ou

1. **Clone o repositório:**
   ```bash
   git clone https://seu-repositorio.git

2.Abra o projeto em um editor de código: Recomenda-se utilizar um editor como Visual Studio Code, Sublime Text ou Atom.

3. Abra o arquivo index.html em um navegador: O projeto estará funcionando localmente.

4. Utilize o campo de pesquisa: Digite a palavra-chave desejada e clique no botão "Pesquisar".

## Explicação do Código
  index.html: Arquivo principal que define a estrutura da página HTML.

  style.css: Arquivo responsável por estilizar a página.

  dados.js: Arquivo contendo o array de objetos com as informações sobre as tecnologias.

  app.js: Arquivo contendo a lógica da aplicação, como a função de pesquisa e a manipulação do DOM.

## Função de Pesquisa:
A função pesquisar() realiza a seguinte lógica:

1. Captura o termo de pesquisa inserido pelo usuário.
2. Itera sobre o array de dados, verificando se o termo de pesquisa está presente no título, descrição ou tags de cada item.
3. Constrói uma string HTML com os resultados da pesquisa e insere-a no elemento com o ID resultados-pesquisa.

## Melhorias Futuras
Implementar um sistema de filtros: Permitir ao usuário filtrar os resultados por categoria (linguagem, framework, ferramenta).
Adicionar mais dados: Expandir a base de dados com informações sobre outras tecnologias e recursos.
Melhorar a interface do usuário: Criar um design mais moderno e intuitivo.
Utilizar um framework de front-end: Simplificar o desenvolvimento e adicionar mais funcionalidades.

## Contribuições
Contribuições são bem-vindas! Se você encontrar algum bug ou tiver alguma sugestão, por favor, abra um issue ou faça um pull request.

## Licença
Este projeto está licenciado sob a licença MIT.
