# Padrao-composite

O padrão composite é um padrão estrutural que modifica a estrutura de um objeto. Esse padrão é mais adequado nos casos em que você precisa trabalhar com objetos que formam uma hierarquia em árvore. Nessa árvore, cada nó / objeto (exceto o nó raiz) é composto ou nó folha. 
A implementação do padrão composto permite que os clientes tratem objetos e composições individuais de maneira uniforme.

O padrão composite compõe objetos em estruturas de árvore para representar hierarquias de parte inteira. O Composite permite que os clientes tratem objetos individuais e composições de objetos uniformemente.

Quando o aplicativo tem estrutura hierárquica e precisa de funcionalidade genérica em toda a estrutura.
Quando o aplicativo precisa agregar dados em uma hierarquia.
Quando o aplicativo deseja tratar objetos compostos e individuais de maneira uniforme.

Exemplo reais do padrão de composite podem ser:

-Construir uma visão consolidada da conta de um cliente no banco (ou seja, carteira do cliente)

-Criação de livros-razão

-Aplicativos de monitoramento de computador / rede

-Aplicativos de varejo e estoque

-Estrutura de diretório em implementações de sistema de arquivos

-Itens de menu nas telas da GUI

![alt text](https://howtodoinjava.com/wp-content/uploads/2015/10/composite-design-pattern.png)

Component: declara a interface para objetos na composição, implementa o comportamento padrão para a interface comum a todas as classes, conforme apropriado, declara uma interface para acessar e gerenciar seus componentes filhos.

Leaf: Representa objetos folha na composição. Uma folha não tem filhos, define o comportamento de objetos primitivos na composição.

Composite: Define o comportamento de componentes com filhos, armazena componentes filhos, implementa operações relacionadas a filhos na interface do Component.

Client: Manipula objetos na composição por meio da interface do componente





Nos arquivos deste repositório, temos códigos de exemplo implementando o padrão em JAVA.
