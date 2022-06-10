### O que é o GitHub e por que ele é importante?
  GitHub é uma plataforma de repositório de dados compartilhados e é utilizada mundialmente por programadores e desenvolvedores pela praticidade em hospedar códigos-fonte e arquivos na nuvem. Essa plataforma é muito importante quando se quer desenvolver algum projeto, já que nele existe a possibilidade de que vários membros de uma equipe trabalhem juntos, inclusive de maneira remota. Além disso, mesmo após a conclusão de um projeto, ele constantemente é atualizado e corrigido, e uma das propostas do GitHub é acompanhar modificações feitas no código base de forma que ele não se perca e possa ser revisto futuramente se necessário.
  
### Criando repositório
O repositório é o local no qual todos os arquivos de um projeto estarão armazenados, juntamente com o seu histórico de modificações. Ele pode estar disponível tanto na versão web do GitHub, quanto no seu computador - aprenderemos a fazer isso no decorrer deste tutorial. Veja a seguir os passos necessários para criá-lo.

1. Na página principal, vá até a seção destinada aos repositórios e crie um novo clicando em `New`;
2.	Dê um nome ao seu repositório;
3.	Insira uma breve descrição;
4.	Para permitir que seu arquivo seja visualizado por qualquer pessoa, selecione a opção `Public`. Caso queira escolher quem poderá visualizar e realizar os commits, selecione `Private`;
5.	Adicionar um arquivo `README` é opcional, mas recomendamos que seja feito e contenha a explicação do projeto;
6. O arquivo `.gitignore` informa quais arquivos deverão ser ignorados em um commit. Por padrão, o GitHub possui uma lista com inúmeros arquivos desse tipo para diferentes necessidades. Selecione o template que desejar;
7.	Caso queira, adicione uma das licenças disponíveis, ou serão aplicadas as leis padrão de copyright. Se você quer que seu código seja aberto, escolha uma licença para esse tipo;
8.	Salve as configurações e seu repositório estará criado!

### Adicionando arquivos ao seu repositório

1.	Clique em `Add File` – `Create New File`;
2.	Nomeie seu novo arquivo;
3.	Para salvar seu arquivo, vá até `Commit New File`, dê um nome ao seu commit e escreva uma breve descrição sobre o que foi feito para que seja registrado detalhadamente no seu histórico;
4.	Para ver seu histórico de commits, vá até seu repositório e clique no ícone de relógio que mostra a quantidade e commits feitos;
5.	Clique no símbolo `<>` presente com cada commit do histórico para visualizar suas alterações;
6.	Para editar o arquivo, basta clicar no ícone de lápis no canto direito da pasta.

### Abrindo e editando um arquivo do git no computador 

1.	Clique com o botão direito no local em que deseja colocar o arquivo do git e vá em `Git Bash Here`;
2.	No github web, abra seu repositório, clique no botão code e copie o link disponível na parte `HTTPS`;
3.	No terminal do gitbash, insira o comando “git clone *insira seu link*” para clonar seu repositório na pasta escolhida;
4.	Com o comando git status é possível verificar as modificações pendentes;
5.	Abra e edite o arquivo que deseja alterar;
6.	Com o arquivo alterado, insira o comando git add # (substitua o “#” pelo nome do arquivo que deseja adicionar, ou coloque um “.” caso deseje adicionar todos);
7.	Em seguida, insira o comando “git commit -m *insira seu link*” para realizar o commit do arquivo previamente adicionado;
8.	Por fim, utilize “git push” para atualizar as modificações também no git web.

### Atualizando no clone os arquivos modificados no git web

1.	Basta utilizar "git pull";
 > **Dica**: recomenda-se utilizar o git pull antes de usar o "git push", pois pode haver atualizações feitas no git web que não foram retificadas no seu computador

### Criando ‘forks’ de um repositório

	`Fork` é uma cópia de um repositório que pode ser editada livremente sem alterar o repositório original. Essa ferramenta é comumente utilizada para propor alterações em projetos alheios aos quais você não possui acesso, mas pode ser utilizada para criar novas versões de seus próprios repositórios ou simplesmente para editar códigos que não são seus.

1.	No github web, acesse o repositório que você deseja 'forkar';
2.	Clique no botão `Fork`;
3.	Ao criar um fork, a interface do github vai pedir um nome e descrição, como se você estivesse criando um repositório do zero, no entanto, se você não inserir nada, os detalhes vão continuar como o repositório original que você está copiando;
4.	A partir daí, é possível editar o fork como qualquer outro repositório, cloná-lo para o seu computador pessoal e atualizá-lo;
5.	Se você quiser, pode fazer um `pull request` (um pedido ao autor do repositório original para atualizar este com as suas alterações);

### Fazendo ‘pull requests’

1.	No github web, acesse o repositório fork que você quer requisitar que seja agregado ao original;
2.	Note que, ao abrir o repositório, você se encontra na aba `Code`;
3.	Clique na aba `Pull requests`;
4.	Selecione o botão verde `New pull request`;
5.	Clique `Create pull request`;
6.	Preencha os dados da descrição explicando as alterações ou deixando um comentário opcional;
7.	Aguarde o autor do repositório original aceitar ou recusar o seu pedido.
