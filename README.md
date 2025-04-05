#Material de apoio em testes de software 

Mentalidade QA
Um explosão de curiosidade, criticiscmo, emaptia pelo cliente
  Obejtivo: Antecipação de problemas

Caracteristicas:
Produto atende as expectativas do meu cliente;
Antecipar comportamento inespetrados;
Missão disseminar essa mentalidade dentro meu time.

Comunicação: Entender o produto que será criado como para  comunicar riscos, discutir uma possível inconsistência no produto,
  Precisão e assertividade ao comunicar;
  Não tenha medo ou receio de compartilhar seus pensamentos ou duvidas;
  maturidade para dar e receber feedbacks

Colabore sob a perspectiva de qualidade desde o inicio
  Ideação> Levantamento requisito> codificação

A noção de que é possíveltestar em diversas camadas -  Frontend, Backend, API Rest, Web, Mobile, Desktop

Identificar o que testar - Abrodagem empírica ou sistemática
empirica: baseado na experência no produto atual ou em produto semelhante
Sistemática: baseado em técnica de testes que ajudam a identificar o que testar em fontes de informações, como requsitos, códigos, riscos e etc.

Teste modelo cascata -  Sequêncial contam com suas fases de testes
  Waterfall - Escopo fecahdo e interações mais longas
Segregação de papeis: Testador, analista de teste, automatizador, líder, gerente.

Mentalidade - Que é produzir com base nas documentações e requisitos fornecidos por fases anteriores, os artefatos de teste que guiarão com testes das aplicações;

Artefatos de testes:
Atividades: executando casos de testes já criados;
Automatização de testes;
Gerindo incosistências e retestando;

Artefatos:
Logos de teste - Relatporio de incidentes + Scripts testes automatizados
relatorio de status de testes

Ági Modelo Iterativo e incremental, trazem a execução de ciclos e entregas de pequenas porções do software
scrum, SAFe, Scaling -  são framework ágil

#Ideação no Ágil: Criar mapas mentais

User History
  Estoria de usuário - Aqui se leva a estoria da solicitação
  Integração - Todas as integrações externas e internas
  Riscos- Aqui se aponta riscos comportamento que pode impactar a evolução
  Ferramente - Aqui se aponta as ferramentas utilizadas
  Notas gerais - Aqui se anota observações do time
  condição de teste -  Aquo pensa nas condições variadas de testes

TDD - Test Driven Development: Pensar primeiro na arquitetura do software, Pensar em como provar que o software foi construído corretamente

ATTD - Acceptance teste driven development: Segue os mesmos principios que o TDD, porém o que espera testar são exemplos de funcionalidade ao invés de um unico metódo de uma classe

BDD -  Behavior Driven Development - temos uma escrita estruturada e criada de maneira colaborativa -  Comportamento da aplicação através de cenários e essa definição com base no negócio PO, QA e DEV

Gerkin - é um DSL utilizada a fazer a escrita de BDD;
  DSL -  Domain specific language
    Dado:
    Quando:
    Então:


#java
Processo assíncrono: quando um processo é demorado, é melhor executar ele de forma assíncrona, para permitir ua melhor expereência ao usuário

Estrutura de uma classe:
Public class <nome da Classe>{
}

Itellyj - PSNM - Comando para criar a classe principal, ou seja a main
  public static void main(){
  }

Atributos: servem para definir qual é os aspecto de seuas objetos, em java eles são variaveis especificas de uma classe e servem para descrever as propriedades de um objetos

Encapsulamento: è uma forma de proteção de atributos, com ele você consegue limitar quem, externo a classe, pode manipular as atributos - modificador dos atribuits para que sejam privados e da criação de métodos que atribuem em capturam o valor atual do atributo

Construtor: Servem para das as informações  a um objeto durante seu nascimento, na verdade o termo correto, é instanciação

Laços: podem ajudar a interagir com listas de valores ou objetos

Polimorfismo: Um cenceito muito relacionado a herança é o polimorfiscmo que permite que você utilize os mesmos métodos mas atribua a eles comportamentos distintos.

Interfaces - servem para que você crie constratos ou seja, obrigações a serem seguidas por qualquer classe que assinar aquele contrato .


#teste de API

Sempre observa depências de framework;
Exemplo: rest Assutrance, Junit

Uma API(Interface de programação de aplicações) é um tipo de implemtação de software que permite expor uma aplicação backend ao mundo exterior sem que haja a necessidade de acesso ao codigo fonte dela.
Conceitos básico de APIs Rest  - A aarquitetura propõe que a API exponha os recurso da aplicação em um servidor e que esses recrusos possam ser acessados através de métodos, por exemplo: buscar, inserir, alterar, excluir

Heuristica para testes exploratorio de API rest -
V - verbos
A - Authentication & Authorization - mecanismo de autenticação e autorizações
D - Data -  Dados e sua estrutura
E - Erros - Código de estado HTTP para erros
R - Responsiviness - tempo de resposta

Check list básico de testes de APIs Resy
Reegras de negócio
continuidade dos fluxos
Tipagem de dados
Parâmetros (corpo, filtro, path, etc)
Uso de token de usuários diferentes
Valiação de étodos
Listagem de 0,1 e muitos recursos
Estrutura da resposta
Código dos estados HTTP
Documentação dos contratos da API



Teste de performance

Perguntas:
Qual o objetivo nos temos?
Qual a quantidade de usuários vamos ter?
Qual o tempo de utilização?
Qual o cenário vamos ter do usuário executando?
Qual o resultado você espera ter com este teste?



Comandos principais do GIT:
git clone – Copia um repositório remoto para sua máquina local.
git init – Cria um novo repositório Git em um diretório local.
git add – Adiciona arquivos ao estágio (staging area) para serem comitados.
git commit – Salva as alterações adicionadas ao repositório com uma mensagem.
git status – Mostra o estado atual dos arquivos no repositório.
git log – Exibe o histórico de commits do repositório.
git branch – Lista, cria ou exclui ramificações (branches).
git checkout – Muda para outra branch ou restaura arquivos para um estado anterior.
git merge – Junta as alterações de uma branch com outra.
git pull – Atualiza o repositório local com as mudanças do repositório remoto.
git push – Envia os commits locais para o repositório remoto.









