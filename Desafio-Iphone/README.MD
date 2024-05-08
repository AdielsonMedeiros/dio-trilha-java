📱 Diagramação de classes do iPhone</br></br>
📋 Descrição
Neste repositório, você encontrará uma implementação abrangente de um desafio de modelagem de software que tem como objetivo representar de forma detalhada e precisa as funcionalidades de um iPhone. Este projeto utiliza princípios de programação orientada a objetos e técnicas de modelagem UML para criar uma estrutura robusta e versátil que permite que um dispositivo iPhone desempenhe os três papéis distintos e cruciais: Reprodutor Musical, Aparelho Telefônico e Navegador na Internet.</br>

</br>Este repositório não apenas fornece o código-fonte em Java para as classes e interfaces correspondentes, mas também inclui uma documentação completa, insights de design e instruções detalhadas sobre como executar o código e explorar o diagrama UML associado. Ao explorar este projeto, eu tive a oportunidade de aprender e aplicar melhores práticas de engenharia de software, desenvolvendo um entendimento profundo de como a modelagem e a programação orientada a objetos podem ser utilizadas para criar sistemas complexos e funcionais.</br>

</br>📊 Diagrama UML
Diagrama de Classes

![alt text](./image-1.png)

</br>Nesta seção, apresentamos uma explicação detalhada de cada classe representada no diagrama de classe do projeto. Cada classe desempenha um papel específico e contribui para a funcionalidade global do sistema.

</br>iPhone :</br>
A classe iPhone é a classe principal que representa o dispositivo como um todo. Ela implementa as interfaces ReprodutorMusical, AparelhoTelefonico e NavegadorInternet. Isso permite que o iPhone desempenhe os papéis de reprodutor musical, aparelho telefônico e navegador na Internet.

ReprodutorMusical :</br>
A interface ReprodutorMusical define os métodos necessários para controlar a reprodução de música, como tocar(), pausar() e selecionarMusica(). As classes que implementam essa interface são capazes de reproduzir músicas.

AparelhoTelefonico :</br>
A interface AparelhoTelefonico define os métodos para realizar chamadas telefônicas e enviar mensagens, incluindo ligar(), atender() e iniciarCorreioVoz(). As classes que implementam essa interface podem funcionar como dispositivos telefônicos.

NavegadorInternet :</br>
A interface NavegadorInternet define métodos para a navegação na web, como exibirPagina(), adicionarNovaAba() e atualizarPagina(). As classes que implementam essa interface podem atuar como navegadores da Internet.