# Dotnet CLI

- CLI (Command Line Interface)
  - Interface de linha de comando
  - Comandos adicionados ao nosso terminal

Microsoft Windows [versão 10.0.19045.4894]
(c) Microsoft Corporation. Todos os direitos reservados.

C:\Users\randu>dotnet --version    // Serve para checar a versão do dotnet
8.0.401

C:\Users\randu>dotnet --list-sdks  // Para listar todos os sdks instalados (atualmente é um só)
8.0.401 [C:\Program Files\dotnet\sdk]

C:\Users\randu>dotnet --list-runtimes  // Aplicativos e seus caminhos
Microsoft.AspNetCore.App 8.0.8 [C:\Program Files\dotnet\shared\Microsoft.AspNetCore.App]
Microsoft.NETCore.App 8.0.8 [C:\Program Files\dotnet\shared\Microsoft.NETCore.App]
Microsoft.WindowsDesktop.App 8.0.8 [C:\Program Files\dotnet\shared\Microsoft.WindowsDesktop.App]

C:\Users\randu>dotnet help  // Comando para ajuda 

Bem-vindo(a) ao .NET 8.0.
---------------------
Versão do SDK: 8.0.401

Telemetria
---------
As ferramentas do .NET coletam dados de uso para ajudar-nos a aprimorar sua experiência. Eles são coletados pela Microsoft e compartilhados com a comunidade. Você pode recusar a telemetria definindo a variável de ambiente DOTNET_CLI_TELEMETRY_OPTOUT como '1' ou 'true' usando seu shell favorito.

Leia mais sobre a telemetria das Ferramentas da CLI do .NET: https://aka.ms/dotnet-cli-telemetry

----------------
Instalou um certificado de desenvolvimento ASP.NET Core HTTPS.
Para confiar no certificado, execute 'dotnet dev-certs https --trust'
Saiba mais HTTPS: https://aka.ms/dotnet-https

----------------
Escreva seu primeiro aplicativo: https://aka.ms/dotnet-hello-world
Descubra o que há de novo: https://aka.ms/dotnet-whats-new
Explorar a documentação: https://aka.ms/dotnet-docs
Relate problemas e encontre a fonte no GitHub: https://github.com/dotnet/core
Use 'dotnet --help' para ver os comandos disponíveis ou visite: https://aka.ms/dotnet-cli
--------------------------------------------------------------------------------------
SDK do .NET (8.0.401)
Uso: dotnet [runtime-options] [path-to-application] [arguments]

Execute um aplicativo do .NET.

runtime-options:
  --additionalprobingpath <path>   Caminho contendo a política de investigação e os assemblies a investigar.
  --additional-deps <path>         Caminho para o arquivo deps.json adicional.
  --depsfile                       Caminho para o arquivo <application>.deps.json.
  --fx-version <version>           Versão do Shared Framework instalada a ser usada para a execução do aplicativo.
  --roll-forward <setting>         Role para frente para a versão de estrutura (LatestPatch, Minor, LatestMinor, Major, LatestMajor, Disable).
  --runtimeconfig                  Caminho para o arquivo <application>. runtimeconfig.json.

path-to-application:
  O caminho para um arquivo .dll de aplicativo a ser executado.

Uso: dotnet [sdk-options] [command] [command-options] [arguments]

Execute um comando do SDK do .NET.

sdk-options:
  -d|--diagnostics  Habilitar saída de diagnóstico.
  -h|--help         Mostrar a ajuda da linha de comando.
  --info            Exiba informações do .NET.
  --list-runtimes   Exiba os runtimes instalados.
  --list-sdks       Exiba os SDKs instalados.
  --version         Exiba a versão do SDK do .NET em uso.

Comandos do SDK:
  add               Adicionar um pacote ou uma referência a um projeto do .NET.
  build             Criar um projeto do .NET.
  build-server      Interagir com servidores iniciados por um build.
  clean             Limpar as saídas do build de um projeto do .NET.
  format            Aplicar preferências de estilo a um projeto ou solução.
  help              Mostrar a ajuda da linha de comando.
  list              Listar as referências de um projeto do .NET.
  msbuild           Executar comandos do MSBuild (Microsoft Build Engine).
  new               Criar um novo projeto ou arquivo do .NET.
  nuget             Fornece comandos adicionais do NuGet.
  pack              Criar um pacote do NuGet.
  publish           Publicar um projeto do .NET para implantação.
  remove            Remover um pacote ou uma referência de um projeto do .NET.
  restore           Restaurar as dependências especificadas em um projeto do .NET.
  run               Criar e executar uma saída de projeto do .NET.
  sdk               Gerencie a instalação do SDK do .NET.
  sln               Modificar os arquivos da solução do Visual Studio.
  store             Armazenar os assemblies especificados no repositório de pacotes do runtime.
  test              Executar testes de unidade usando o executor de testes especificado em um projeto do .NET.
  tool              Instalar ou gerenciar ferramentas que ampliam a experiência do .NET.
  vstest            Executar comandos do VSTest (Microsoft Test Engine).
  workload          Gerenciar as cargas de trabalho opcionais.

Comandos adicionais de ferramentas em pacote:
  dev-certs         Crie e gerencie certificados de desenvolvimento.
  fsi               Iniciar F# Interativo / executar scripts do F#.
  user-jwts         Gerenciar tokens da Web JSON em desenvolvimento.
  user-secrets      Gerencie segredos do usuário de desenvolvimento.
  watch             Inicie um observador de arquivo que executa um comando quando os arquivos são alterados.

Execute 'dotnet [command] --help' para obter mais informações sobre um comando.

C:\Users\randu>
