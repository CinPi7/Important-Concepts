# Conceitos de SWE

## :dna: O que são Dados?

<p>➜ Dados são informações ou um conjunto de valores brutos que são processados por um computador.</p>
<p>➜ Podem ser qualquer coisa que seja útil para o computador ou para o usuário, como números, texto, imagens, sons, etc.</p>
<p>➜ No contexto da ciência da computação, os dados são geralmente armazenados, processados e transmitidos em formato binário.</p>
<p>➜ Na ciência de dados, dados são informações coletadas que podem ser manipuladas ou analisadas para servir a um propósito específico.</p>
<p>➜ A ciência de dados envolve o uso de métodos, processos, algoritmos e sistemas para extrair conhecimento e insights desses dados em várias formas, tanto estruturadas quanto não estruturadas.</p>

## :link: O que é uma API?

<p> ➜ Uma API, ou Interface de Programação de Aplicações, é um conjunto de regras e protocolos, instruções e padrões, que especificam como os componentes de software devem interagir, formando uma interface de acesso a um aplicativo online.</p>
<p> ➜ Ela permite que diferentes softwares 'conversem' entre si de maneira padronizada.</p>
<p> ➜ Por exemplo, quando você usa um aplicativo em seu telefone para ver o tempo, o aplicativo usa uma API para solicitar dados de um serviço de previsão do tempo.</p>
<p> ➜ As arquiteturas de API, como REST e GraphQL, são maneiras diferentes de projetar e implementar APIs.</p>
<p> ➜ REST, ou Representational State Transfer, é uma arquitetura que usa o protocolo HTTP e seus métodos (GET, POST, PUT, DELETE) para criar APIs. Ela é baseada em recursos, onde cada recurso é identificado por URLs.
</p>
<p> ➜ GraphQL, por outro lado, é uma linguagem de consulta para APIs que permite aos clientes especificar exatamente quais dados eles precisam, o que pode reduzir a quantidade de dados que precisam ser transferidos.
</p>

<p> A escolha entre REST, GraphQL ou outra arquitetura de API depende das necessidades específicas do seu projeto. Por exemplo, se você precisa de uma API altamente personalizável que possa retornar muitos tipos diferentes de dados, o GraphQL pode ser uma boa escolha. Se você está criando uma API simples que se alinha bem com o modelo de recurso do REST, então o REST pode ser a melhor opção.</p>

Além dessas arquiteturas, ainda tem-se algumas outras:

<p>➜ SOAP (Simple Object Access Protocol): É um protocolo baseado em XML que permite que os aplicativos troquem informações por meio de qualquer protocolo de transporte, como HTTP, SMTP etc. Ele é altamente extensível e seguro, mas pode ser mais complexo de usar do que REST.</p>
<p>➜ JSON-RPC e XML-RPC: Ambos são protocolos de chamada de procedimento remoto que codificam chamadas e respostas em JSON ou XML, respectivamente. Eles são simples e permitem chamadas entre diferentes ambientes de programação, mas não têm muitos dos recursos de outras arquiteturas de API, como REST ou GraphQL.</p>
<p>➜ gRPC: É um framework de RPC (Remote Procedure Call) de alto desempenho desenvolvido pelo Google. Ele usa o Protocol Buffers como linguagem de interface e suporta muitos idiomas.</p>
<p>➜ OData (Open Data Protocol): Permite a criação de APIs RESTful que permitem aos clientes consultar e manipular dados usando métodos HTTP padrão.</p>

Cada uma dessas arquiteturas tem seus próprios pontos fortes e fracos, e a melhor escolha depende das necessidades específicas do seu projeto.

Mais detalhes podem ser entendidos, ainda:

<p>➜ RESTful: Uma API RESTful é baseada em recursos, onde cada recurso é identificado por uma URL. Ela usa métodos HTTP padrão, como GET, POST, PUT e DELETE. Para criar uma API RESTful, você precisa definir seus recursos e como os métodos HTTP se aplicam a eles. Por exemplo, um GET para /users pode retornar uma lista de usuários, enquanto um POST para /users pode criar um novo usuário.</p>
<p>➜ GraphQL: Ao contrário do REST, o GraphQL não é baseado em recursos. Em vez disso, ele permite que os clientes especifiquem exatamente quais dados eles precisam, o que pode reduzir a quantidade de dados que precisam ser transferidos. Para criar uma API GraphQL, você precisa definir um esquema que descreva os tipos de dados que sua API pode retornar e como eles estão relacionados.</p>
<p>➜ SOAP: SOAP é um protocolo que permite a comunicação entre aplicativos por meio de redes, como a Internet. Ele usa XML para codificar suas mensagens, que são geralmente chamadas de "envelopes". Para criar uma API SOAP, você precisa definir um WSDL (Web Services Description Language), que é um documento XML que descreve como a API pode ser chamada, quais parâmetros ela espera e quais formatos de dados ela retorna.</p>

<p>Lembre-se, a escolha da arquitetura da API depende das necessidades do seu projeto.</p>

## :scissors: O que é componetização?

<p>➜ A componentização é um conceito em desenvolvimento de software onde você divide a interface do usuário em componentes independentes e reutilizáveis.</p>
<p>➜ Cada componente é responsável por uma funcionalidade específica e pode ser usado em diferentes partes do aplicativo. Isso torna o código mais fácil de entender, testar e manter. Além disso, permite a reutilização de código, o que pode acelerar o desenvolvimento.</p>
<p>➜ Frameworks populares como React e Vue.js são baseados neste conceito de componentização.</p>

## :plate_with_cutlery: O que é Stack?

<p>➜ Pilha (ou stack, em inglês) é uma estrutura de dados que segue o princípio de LIFO (Last In, First Out), ou seja, o último elemento a ser inserido na pilha é o primeiro a ser removido.</p>
<p>➜ Você pode pensar nisso como uma pilha de pratos: você coloca um novo prato no topo da pilha e também remove do topo.</p>
<p>➜ Em termos de programação, as pilhas são usadas em várias aplicações, como para manter o controle do ponto onde um programa deve retornar após a execução de uma função.</p>
<p>➜ FILO (First In, Last Out) e LIFO (Last In, First Out) são essencialmente a mesma coisa e são usados para descrever a maneira como as pilhas funcionam. Ambos indicam que o último item que entra é o primeiro que sai. No entanto, o termo LIFO é mais comumente usado em ciência da computação.</p>
<p>➜ Na programação web, as pilhas são usadas em várias situações. Por exemplo, quando você clica em um link para ir a uma nova página e depois pressiona o botão de voltar, o navegador sabe para qual página voltar porque mantém uma pilha do seu histórico de navegação. O último site que você visitou é o primeiro a ser removido da pilha quando você pressiona o botão de voltar.</p>
<p>➜ Além disso, as pilhas também são usadas em linguagens de programação para controlar a execução de funções e métodos.</p>
<p>➜ Quando uma função é chamada, as informações sobre o estado atual do programa são empilhadas, e quando a função termina, essas informações são desempilhadas para retornar ao estado anterior. Isso é especialmente relevante em JavaScript, uma linguagem comumente usada na programação web.</p>

## DOM

<p>➜ DOM (Document Object Model) é uma interface de programação para documentos HTML e XML, e como estes são lidos pelo browser.</p>
<p>➜ Ele representa a estrutura do documento como uma árvore de objetos, onde cada objeto representa uma parte do documento (como um elemento HTML).</p>
<p>➜ Isso permite que os programadores manipulem o conteúdo e a estrutura do documento usando linguagens de script como JavaScript.</p>
<p>➜ Por exemplo, você pode usar o DOM para alterar o texto de um elemento HTML, adicionar um novo elemento ou alterar um atributo de um elemento.</p>
