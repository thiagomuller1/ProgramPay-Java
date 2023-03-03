# ProgramPay-Java

•  O que é programação orientada a objetos?
Programação Orientada a Objetos (POO) é um paradigma de programação que se baseia em conceitos como objetos, classes, encapsulamento, herança e polimorfismo para modelar e resolver problemas de forma mais intuitiva e organizada.

•  Quais são os pilares da programação orientada a objetos?
Os pilares da POO são: encapsulamento, herança e polimorfismo

•  O que é uma classe em Java?
Em Java, uma classe é uma estrutura que define um conjunto de atributos e métodos comuns a um conjunto de objetos. Ela funciona como um molde para a criação de objetos.

•  Como criar um objeto a partir de uma classe em Java?
Para criar um objeto a partir de uma classe em Java, é necessário utilizar o operador new e o nome da classe seguido dos parênteses. Exemplo: PaymentType payment = new PaymentType();

•  O que faz a palavra new no Java?
A palavra new em Java é responsável por alocar memória para um novo objeto e chamar o construtor da classe.

•  Quais as semelhanças entre Java e C?
Java e C possuem sintaxe semelhante, pois ambas são linguagens de programação orientadas a objetos e estruturadas. No entanto, Java possui recursos adicionais, como gerenciamento automático de memória e exceções.

•  Quais as diferenças entre Java e C?
Algumas diferenças entre Java e C são: Java possui gerenciamento automático de memória, C permite manipulação direta da memória; Java é mais seguro em relação a erros de ponteiros, C é mais vulnerável a esses erros; Java é executado em uma Máquina Virtual, C é compilado em código de máquina nativo.

•  O que é a classe InputReader e qual é a sua função no programa?
A classe InputReader é responsável por ler dados de entrada do usuário. Ela é utilizada no programa para ler o valor do pagamento.

•  Qual é a finalidade do método readDouble na classe InputReader?
O método readDouble na classe InputReader tem como finalidade ler um número decimal de entrada do usuário e retornar o seu valor como um double.

•  O que é a interface PaymentType e como ela é utilizada no programa?
PaymentType é uma interface que define os métodos que devem ser implementados pelas classes que representam os tipos de pagamento disponíveis no programa. Ela é utilizada para permitir que objetos de diferentes tipos de pagamento possam ser tratados de forma polimórfica.

•  Como a classe PaymentTypeSelector é responsável por selecionar o tipo de pagamento a ser utilizado?
A classe PaymentTypeSelector é responsável por selecionar o tipo de pagamento a ser utilizado com base na entrada do usuário. Ela utiliza a classe Scanner e a classe InputReader para ler a entrada do usuário e o método selectPaymentType para selecionar o tipo de pagamento

•  Qual é a relação entre a classe PaymentTypeSelector e as classes PixPayment, CreditPayment e BoletoPayment?
A classe PaymentTypeSelector é responsável por selecionar o tipo de pagamento a ser utilizado e as classes PixPayment, CreditPayment e BoletoPayment representam os diferentes tipos de pagamento disponíveis no programa. Essas classes implementam a interface PaymentType para garantir que possuam os métodos necessários para serem tratadas de forma polimórfica.

•  O que é polimorfismo e como ele é utilizado no programa?
Polimorfismo é a capacidade de um objeto ser tratado de várias formas. No programa, o polimorfismo é utilizado para tratar os diferentes tipos de pagamento de forma genérica, utilizando a interface PaymentType para definir os métodos comuns a todos os tipos de pagamento.

•  Qual é a finalidade do método getName na interface PaymentType e nas classes que a implementam?
O método getName na interface PaymentType e nas classes que a implementam tem como finalidade retornar o nome do tipo de pagamento.

•  O que é a classe Scanner e como ela é utilizada no programa?
A  classe Scanner é utilizada no programa para ler a entrada do usuário. Ela é utilizada pela classe PaymentTypeSelector para ler o tipo de pagamento escolhido pelo usuário.

•  O que é uma exceção e como ela é tratada no método selectPaymentType da classe PaymentTypeSelector?
Uma exceção é um evento que ocorre durante a execução do programa e que interrompe o seu fluxo normal. No método selectPaymentType da classe PaymentTypeSelector

•  Como seria possível adicionar um novo tipo de pagamento ao programa?
Para adicionar um novo tipo de pagamento ao programa, é necessário criar uma nova classe que implemente a interface PaymentType. Essa classe deve conter a implementação dos métodos da interface e os comportamentos específicos do novo tipo de pagamento.

•  Qual é a importância de utilizar interfaces no desenvolvimento de sistemas orientados a objetos?
Interfaces permitem definir um conjunto de métodos que uma classe deve implementar, sem especificar como esses métodos devem ser implementados. Isso permite que as classes sejam mais flexíveis e modularizadas, e também torna mais fácil a criação de classes que implementem múltiplas interfaces.

•  Qual é a diferença entre uma classe abstrata e uma interface?
Uma classe abstrata pode ter métodos abstratos, ou seja, métodos que não têm implementação e precisam ser implementados pelas subclasses. Além disso, uma classe abstrata pode ter métodos concretos (com implementação) e pode ter variáveis de instância. Já uma interface é um conjunto de métodos abstratos (sem implementação) que uma classe pode implementar.

•  O que é encapsulamento e como ele é aplicado no programa?
Encapsulamento é o conceito de ocultar a implementação interna de uma classe, fornecendo apenas uma interface pública para que outras classes possam interagir com ela. No programa, o encapsulamento é aplicado definindo os atributos da classe como privados e fornecendo métodos públicos para acessá-los e modificá-los, como o método getAmount() da classe Payment.

•  Como seria possível melhorar a legibilidade do programa?
Algumas formas de melhorar a legibilidade do programa são: usar nomes descritivos para classes, métodos e variáveis, utilizar indentação adequada, separar o código em blocos lógicos e adicionar comentários que expliquem o que cada parte do código faz.

•  Qual é a finalidade da classe Main no programa?
A classe Main é responsável por iniciar a execução do programa, criando um objeto PaymentTypeSelector e chamando o método selectPaymentType().

•  O que é um construtor padrão e quando ele é utilizado?
Um construtor padrão é um construtor que não recebe argumentos e tem uma implementação padrão (geralmente vazia). Ele é utilizado para inicializar os objetos quando nenhum argumento é passado para o construtor.

•  Como é possível proteger o programa contra erros de entrada do usuário?
Uma forma de proteger o programa contra erros de entrada do usuário é validar as entradas de dados antes de processá-las. Isso pode ser feito utilizando estruturas de controle, como if e try-catch, para verificar se a entrada está no formato correto ou se está dentro dos limites aceitáveis.

•  Qual é a importância de utilizar nomes descritivos para as classes, métodos e variáveis?
Utilizar nomes descritivos para as classes, métodos e variáveis torna o código mais legível e compreensível, facilitando a manutenção e o entendimento do funcionamento do programa.

•  O que é herança e como ela pode ser aplicada no programa?
Herança é um conceito de programação orientada a objetos em que uma classe pode herdar atributos e métodos de outra classe. Isso permite que as classes sejam organizadas em hierarquias e compartilhem comportamentos e características comuns. No programa, a classe PaymentTypeSelector

•  Como é possível utilizar a sobrecarga de métodos no programa?
A sobrecarga de métodos é utilizada no programa por meio da criação de vários métodos com o mesmo nome, porém com diferentes parâmetros de entrada. No caso específico do programa, a classe PaymentTypeSelector possui vários métodos selectPaymentType com diferentes assinaturas, sendo possível selecionar o tipo de pagamento com diferentes tipos de entrada, como um objeto PaymentType, uma string contendo o nome do tipo de pagamento ou um inteiro representando o código do tipo de pagamento. Essa técnica é útil para simplificar a utilização dos métodos, tornando mais fácil para o usuário final compreender e utilizar o sistema.
