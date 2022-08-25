### **Alunos**: Kevin Justus Piotrowski 18015726, Leonardo Vicente Ferreira Oliveira 17242326 e Mayara Lovatto Lopes 19008226

### Features

- [x] Cadastro de Funcionários
- [x] Listagem de Funcionários Cadastrados
- [x] Remoção de Funcionários Cadastrados  
- [x] Exclusão de todos os Funcionários

### Requisitos
1) Editor de Códigos como o VSCode
2) Acesso a um sistema de Banco de Dados como o MySQL Workbench.
3) Maven



### Descrições

<p>
Páginas do sistema:
  
* Listagem de Funcionários: http://localhost:3000/ -> Tela aberta quando o front end é iniciado ou ao clicar em "Agamemnon RH" de uma das outras páginas. Lista os funcionários cadastrados permitindo a visualização de seus dados. Na tabela apresentada também é permitido que funcionários sejam excluídos individualmente através do botão excluir ou que todos os funcionários cadastrados sejam excluídos ao clicar no botão excluir todos os funcionários no final da tabela. Caso nenhum funcionário esteja cadastrado no banco a mensagem "Nenhum Funcionário Cadastrado!" é exibida;<br><br>
* Listagem de Funcionários: http://localhost:3000/list -> É aberta ao clicar no botão "Listar todos os funcionários" em uma das outras páginas. Seu funcionamento é idêntico a página descrita acima;<br><br>
* Inclusão de Funcionário: http://localhost:3000/add -> É aberta ao clicar no botão "Adicionar funcionário" em uma das outras páginas. Abre um formulário para a inclusão de um novo funcionário, contendo os campos para a inclusão de seu nome e CPF. Ao clicar no botão "Adicionar" os dados preenchidos são salvos no banco de dados como um novo funcionário;<br> <br>
</p>

<p>
Métodos da API:
  
* /api/funcionarios
  - Método **POST**: cria um funcionário;
  - Método **GET**: lista todos os funcionários;
  - Método **DELETE**: exclui todos os funcionários.
* /api/funcionarios/{id}
  - Método **DELETE**: exclui um funcionário pelo **id**.
</p>
