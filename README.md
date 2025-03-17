# Desafio Amigo Secreto - Projeto JavaScript

Este repositório contém o código do projeto **Amigo Secreto**, desenvolvido como parte de um desafio de programação. O objetivo do projeto era criar uma aplicação web simples que permitisse aos usuários adicionar nomes à lista de amigos, e então, ao clicar em um botão, realizar um sorteio aleatório para definir o "amigo secreto" de cada pessoa.



### . **Estrutura do HTML**
    Comecei com a criação de um formulário simples contendo um campo de texto para inserir o nome de amigos, um botão para adicionar os nomes à lista, uma lista não ordenada (`<ul>`) para exibir os amigos e outro botão para realizar o sorteio.
   

### . **Adicionando Amigos à Lista com JavaScript**
   Utilizei o método `.push()` para adicionar o nome inserido a um array (`amigos[]`). A entrada foi validada para garantir que o campo não estivesse vazio. Após a adição, o campo de entrada foi limpo para uma nova inserção.
 

### . **Exibindo a Lista de Amigos**
   Criei uma função para percorrer o array de amigos e adicionar cada nome como um item (`<li>`) dentro de uma lista HTML. Utilizei `innerHTML` para atualizar a lista de amigos e garantir que não houvesse duplicação.
 
### . **Sortear um Amigo Secreto Aleatório**
   
   Utilize o método `Math.random()` para gerar um número aleatório e `Math.floor()` para arredondar esse número para o índice do array. Em seguida, obtenha o nome correspondente e exibi o resultado na página.
   - 


## Tecnologias Utilizadas

- **HTML**: Estrutura básica da página web.
- **CSS**: Estilização para tornar a página mais atrativa.
- **JavaScript**: Implementação da lógica de adicionar amigos e sortear aleatoriamente o amigo secreto.
- **Git**: Versionamento de código e controle de alterações.

## Como Rodar o Projeto

Para rodar este projeto localmente em seu computador, siga os passos abaixo:

1. Clone este repositório:
   ```bash
   git clone https://github.com/usuario/nome-do-repositorio.git
