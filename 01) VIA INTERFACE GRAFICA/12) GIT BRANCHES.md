# GIT BRANCHES
Branches, em termos de controle de versão e Git, são cópias separadas do código-fonte de um projeto, cada uma delas representando uma linha de desenvolvimento independente. Eles permitem que várias pessoas trabalhem em diferentes recursos ou correções de bugs simultaneamente, sem afetar o código principal do projeto até que estejam prontos para mesclar suas alterações.

Aqui estão os principais conceitos relacionados a branches:

1. **Branch Padrão (Master ou Main):** Ao criar um novo repositório Git, geralmente há uma branch principal chamada "master" ou "main". Essa é a branch principal onde o código estável e pronto para produção é mantido.

2. **Criando Branches:** Você pode criar novas branches a partir da branch principal ou de outras branches existentes. Isso é feito para isolar o trabalho em progresso e evitar conflitos prematuros com o código principal.

3. **Trabalhando em Branches:** Cada branch representa uma linha de desenvolvimento separada. Desenvolvedores podem trabalhar em diferentes branches simultaneamente, adicionando novos recursos, fazendo correções de bugs, etc.

4. **Mesclando Branches:** Quando o trabalho em uma branch está concluído e pronto para ser incorporado ao código principal, você pode mesclar (merge) a branch de volta na branch principal. Isso combina as alterações da branch secundária na branch principal.

5. **Resolvendo Conflitos:** Às vezes, ocorrem conflitos quando você tenta mesclar uma branch. Isso acontece quando duas alterações conflitantes afetam a mesma parte do código. Você precisa resolver esses conflitos manualmente.

6. **Excluindo Branches:** Após mesclar com sucesso uma branch ou quando não é mais necessária, você pode excluir a branch. Isso mantém o repositório limpo e organizado.

7. **Branches Remotas:** Além de branches locais, você pode criar branches remotas que existem no servidor remoto. Essas branches permitem colaboração entre equipes distribuídas.

8. **Pull Requests e Merge Requests:** Em plataformas como o GitHub e GitLab, os pull requests (GitHub) ou merge requests (GitLab) são mecanismos para revisar e mesclar branches. Eles permitem que outros membros da equipe revisem as alterações antes de serem mescladas na branch principal.

Branches são uma parte fundamental do fluxo de trabalho de controle de versão com Git. Eles permitem uma abordagem estruturada para o desenvolvimento colaborativo, onde diferentes recursos e correções podem ser trabalhados simultaneamente sem causar conflitos constantes. Branches também ajudam a manter o código principal (branch principal) estável enquanto o desenvolvimento está em andamento em outras áreas do projeto.

## BRANCHES E COMMITS:
O Branch no Git não é um registro de commits em si, mas é mais como um marcador ou uma "linha de desenvolvimento separada" que aponta para um determinado commit em um determinado momento da história do projeto. É como se você estivesse criando cópias do seu projeto em momentos específicos para desenvolver recursos ou correções de bugs separadamente.

Para dar um exemplo do cotidiano, imagine que você está escrevendo um livro. O livro é o seu projeto principal. O que você faz com o Git é semelhante a ter diferentes rascunhos do livro em paralelo, cada um com suas próprias mudanças e melhorias. Vamos usar isso como analogia:

1. **Branch Principal (Master/Main):** Este é o seu rascunho principal, onde você está escrevendo a história principal do livro. É onde você se concentra na narrativa principal e mantém tudo em ordem.

2. **Branch de Desenvolvimento de Personagem:** Digamos que você queira criar personagens mais ricos e desenvolvidos em seu livro. Você cria um novo rascunho (branch) chamado "Personagens" e começa a desenvolver os detalhes dos personagens sem afetar a história principal.

3. **Branch de Revisão de Gramática:** Para garantir que o livro tenha uma gramática impecável, você cria um novo rascunho (branch) chamado "Revisão-Gramatical" e concentra-se apenas na correção de erros de gramática.

4. **Branch de Desenvolvimento de Plot Twist:** Você quer adicionar um plot twist surpreendente à sua história. Então, você cria um novo rascunho (branch) chamado "Plot-Twist" e trabalha nisso separadamente.

5. **Branch de Correção de Erros:** À medida que você revisa seu livro, pode encontrar erros que precisam ser corrigidos. Você cria um rascunho (branch) chamado "Correção-Erros" para corrigir esses problemas sem afetar os outros aspectos da história.

6. **Mesclando Branches:** Quando estiver satisfeito com o desenvolvimento de um aspecto específico (por exemplo, o desenvolvimento de personagens), você pode mesclar esse branch de volta ao branch principal, incorporando essas melhorias à história principal do livro.

7. **Gerenciando Versões:** Cada branch representa uma versão diferente do livro em desenvolvimento. Isso permite que você trabalhe em várias partes do seu projeto ao mesmo tempo e mantenha o branch principal (sua história principal) sempre estável.

Assim como na escrita de um livro, os branches no Git permitem que você trabalhe em diferentes aspectos do seu projeto sem comprometer o projeto principal. Você pode desenvolver recursos, corrigir erros e melhorar partes específicas do projeto em paralelo, mantendo tudo organizado e, quando estiver satisfeito com uma parte específica, pode mesclá-la de volta à versão principal do projeto. Isso facilita o desenvolvimento colaborativo e a organização de trabalho em equipe em projetos de software.

## FAZENDO O MERGE:
Para fazer um merge (mesclagem) de branches usando o GitHub Desktop, siga os passos abaixo:

**Pré-requisito:** Certifique-se de que você tenha o GitHub Desktop instalado e esteja conectado à sua conta do GitHub.

1. **Abra o Repositório no GitHub Desktop:**
   
   Abra o GitHub Desktop e selecione o repositório no qual você deseja fazer o merge. Ele aparecerá na lista de repositórios no aplicativo.

2. **Escolha a Branch Destino (Branch Principal):**

   Antes de fazer o merge, você precisa decidir em qual branch você deseja incorporar as alterações. Geralmente, você mesclará uma branch secundária (a ser mesclada) em uma branch principal (onde as alterações serão incorporadas).

   - Selecione a branch principal (por exemplo, "master" ou "main") na lista de branches disponíveis. Isso será a branch de destino para o merge.

3. **Inicie o Merge:**

   - Agora, vá até a branch que você deseja mesclar na lista de branches disponíveis.
   - Clique com o botão direito do mouse na branch secundária que você deseja mesclar.
   - No menu de contexto que aparece, escolha "Merge into current branch" (Mesclar na branch atual). Isso iniciará o processo de merge.

4. **Resolva Conflitos (se houver):**

   Se houver conflitos entre as alterações na branch secundária e a branch de destino, você precisará resolvê-los. O GitHub Desktop fornecerá ferramentas para ajudá-lo a resolver esses conflitos manualmente.

5. **Conclua o Merge:**

   - Após resolver os conflitos, você verá uma prévia das alterações que serão incorporadas no merge.
   - Revise as alterações para garantir que estão corretas.
   - Quando estiver pronto para continuar, clique no botão "Merge branch" (Mesclar branch).

6. **Confirme o Merge:**

   - O GitHub Desktop solicitará que você adicione um comentário descrevendo o merge, se desejar.
   - Clique em "Confirm merge" (Confirmar merge) para confirmar o merge.

7. **Envie as Alterações para o GitHub:**

   Após confirmar o merge, as alterações mescladas estarão em seu repositório local. Para enviá-las ao repositório remoto no GitHub, clique no botão "Push origin" (Enviar para a origem) no canto superior direito do GitHub Desktop.

Pronto! Você concluiu com sucesso o merge de uma branch no GitHub Desktop. As alterações agora foram incorporadas à branch de destino e estão disponíveis no seu repositório no GitHub. Certifique-se de revisar e testar as alterações após o merge para garantir que tudo funcione conforme o esperado.