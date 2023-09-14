# CLONANDO REPOSITÓRIO
Clonar repositórios usando o GitHub Desktop e o GitHub na web são duas maneiras diferentes de obter uma cópia de um repositório Git. Vou explicar como fazer isso em ambos os casos e, em seguida, destacar a diferença entre clonar seu próprio repositório e clonar o repositório de outra pessoa:

## Clonando um Repositório com o GitHub Desktop:
1. Abra o GitHub Desktop e faça login na sua conta do GitHub, caso ainda não esteja conectado.

2. No canto superior esquerdo da janela do GitHub Desktop, clique em "File" (Arquivo) e selecione "Clone Repository" (Clonar Repositório).

3. Você verá uma lista dos seus repositórios GitHub na seção "Your Repositories" (Seus Repositórios). Escolha o repositório que deseja clonar.

4. Escolha o diretório local onde deseja que o repositório seja clonado em seu computador.

5. Clique em "Clone" (Clonar). O GitHub Desktop irá baixar o repositório para o diretório escolhido.

## Clonando um Repositório via GitHub na Web:
1. Abra o GitHub na web e faça login na sua conta.

2. Acesse o repositório que deseja clonar.

3. No canto direito da página do repositório, você verá um botão verde "Code" (Código). Clique nele.

4. Na janela que aparece, clique em "HTTPS" para copiar a URL do repositório.

5. Abra o terminal no seu computador e navegue para o diretório onde deseja clonar o repositório.

6. Use o comando `git clone` seguido da URL que você copiou. Por exemplo:

   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
   ```

   Substitua a URL pelo URL do repositório que você deseja clonar.

Agora, quanto à diferença entre clonar seu próprio repositório e clonar o repositório de outra pessoa:

## Clonar Seu Próprio Repositório:
- Clonar seu próprio repositório é comum quando você deseja começar a trabalhar em um projeto existente que você mesmo criou. Isso cria uma cópia local do repositório em seu computador para que você possa fazer alterações e colaborar com outras pessoas, se desejar.

- Você terá permissões completas de leitura e gravação no repositório clonado, o que significa que você pode fazer commits, criar branches, abrir issues e fazer push das suas alterações para o repositório.

## Clonar o Repositório de Outra Pessoa:
- Clonar o repositório de outra pessoa é comum quando você deseja colaborar em um projeto de código aberto ou contribuir para um projeto de terceiros. Isso cria uma cópia local do repositório em seu computador para que você possa fazer alterações e, em seguida, propor essas alterações por meio de um "pull request".

- Você terá permissões de leitura no repositório clonado, o que significa que você pode ver o código, mas não pode fazer alterações diretas no repositório original sem permissão do proprietário. Para contribuir, você normalmente cria um fork do repositório, faz alterações no seu fork e, em seguida, abre um pull request para propor as alterações ao repositório original.

Em resumo, clonar seu próprio repositório permite que você trabalhe diretamente em suas próprias criações, enquanto clonar o repositório de outra pessoa geralmente envolve a colaboração em projetos existentes, seguindo práticas de código aberto e contribuindo para a comunidade de desenvolvedores.