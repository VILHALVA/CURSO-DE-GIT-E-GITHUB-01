# INSTALANDO NO LINUX
O GitHub Desktop não tem uma versão oficial para Linux, mas você pode usar uma alternativa chamada "GitHub Desktop for Linux" (anteriormente conhecido como "GitHub Desktop 2"). Esta é uma versão não oficial baseada no Electron que oferece funcionalidades semelhantes à versão oficial do GitHub Desktop para Windows e macOS. Siga estas etapas para instalar o GitHub Desktop for Linux:

**Importante:** Antes de iniciar o processo de instalação, certifique-se de que seu sistema Linux tenha o Git instalado, pois o GitHub Desktop depende dele para funcionar. Você pode instalar o Git usando o gerenciador de pacotes padrão do seu sistema (por exemplo, `apt` no Ubuntu ou `dnf` no Fedora).

**Passo 1: Faça o Download do GitHub Desktop for Linux:**

1. Visite a página de lançamentos do GitHub Desktop for [Linux no GitHub](https://github.com/shiftkey/desktop/releases)

2. Role para baixo até encontrar a seção "Assets" (Ativos) e procure pelo arquivo de download apropriado para o seu sistema Linux. Geralmente, você encontrará um arquivo com extensão ".tar.gz". Certifique-se de escolher a versão mais recente.

3. Clique no link do arquivo ".tar.gz" para fazer o download.

**Passo 2: Extraia o Arquivo:**

1. Após o download, vá para a pasta onde o arquivo foi baixado.

2. Abra um terminal na pasta onde o arquivo está localizado.

3. Use o comando `tar` para extrair o conteúdo do arquivo. Por exemplo, se o arquivo for chamado "GitHubDesktop-linux-x64.tar.gz", você pode usar o seguinte comando:
   
   ```bash
   tar -xvf GitHubDesktop-linux-x64.tar.gz
   ```

**Passo 3: Execute o GitHub Desktop:**

1. Após extrair o conteúdo, você encontrará uma pasta chamada "GitHubDesktop" (ou similar) na pasta onde o arquivo foi extraído. Acesse essa pasta usando o terminal:

   ```bash
   cd GitHubDesktop
   ```

2. Dentro dessa pasta, você deve encontrar um arquivo chamado "GitHubDesktop". Execute o aplicativo com o seguinte comando:

   ```bash
   ./GitHubDesktop
   ```

O GitHub Desktop for Linux deve iniciar agora, permitindo que você faça login na sua conta do GitHub e comece a usar a interface gráfica para gerenciar seus repositórios Git. Lembre-se de que esta é uma alternativa não oficial ao GitHub Desktop, e você pode encontrar diferenças em relação à versão oficial disponível para Windows e macOS. Certifique-se de verificar as atualizações no repositório do projeto para obter a versão mais recente.