EXPRESS                 - Webserver que vamos utilizar para a webapi;
CORS                    - Pacote de segurança necessário para permitir comunicação futura com o frontend;
HELMET                  - Pacote de segurança para dar uma blindada básica na nossa webapi;
DOTENV                  - Pacote de configuração para cuidar das variáveis de ambiente;
MORGAN                  - Pacote para login de requisição no terminal;
EXPRESS-ASYNC-ERRORS    - Pacote para conseguir capturar erros assincronos;

server.ts       - Módulo de inicialização do servidor web onde nossa webapi estará hospedada, módulo de infraestrutura;
app.ts          - Módulo de configuração da webapi, módulo de aplicação;
routes          - Pasta onde guardaremos os módulos de roteamento, que mapeiam endpoints para as funções de controle;
controller      - Pasta onde guardaremos os módulos de controle, que recebem as requisições roteadas e fazem os processamentos necessários;
models          - Pasta onde guardaremos os módulos de entidades, que contém especificação delas;
repositories    - Pasta onde guardaremos os módulos de repositórios, que contém as funções de leitura, exclusão, inserção, etc das entidades;