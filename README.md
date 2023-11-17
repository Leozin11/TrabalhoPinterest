# DAO - Data Access Object

[![.github/workflows/ci.yaml](https://github.com/pages-themes/leap-day/actions/workflows/ci.yaml/badge.svg)](https://github.com/pages-themes/leap-day/actions/workflows/ci.yaml) [![Gem Version](https://badge.fury.io/rb/jekyll-theme-leap-day.svg)](https://badge.fury.io/rb/jekyll-theme-leap-day)

*Leap day is a Jekyll theme for GitHub Pages. You can [preview the theme to see what it looks like](http://pages-themes.github.io/leap-day), or even [use it today](#usage).*

![Thumbnail of Leap day](thumbnail.png)

## O que é o DAO?
O Data Access Object (DAO) é um padrão de design que é comumente usado na programação orientada a objetos para separar a lógica de acesso a dados da lógica de negócios de uma aplicação. Em outras palavras, o DAO é um objeto que fornece uma interface abstrata para interagir com o banco de dados e permite que as classes de negócio se concentrem na lógica de negócios.

## Origem do DAO
O DAO surgiu pela primeira vez na década de 1990 como parte da arquitetura de software Java EE. Ele foi projetado para abstrair a lógica de acesso a dados do código de negócios em aplicativos de camada de servidor. Com a popularização do paradigma de programação orientada a objetos, o DAO se tornou um padrão popular em muitas outras linguagens de programação.

## Como o DAO funciona?
O DAO encapsula o código de acesso a dados em um objeto separado, permitindo que a lógica de negócios se concentre na manipulação dos objetos de domínio e não na manipulação dos dados subjacentes. O DAO fornece uma interface abstrata que é usada pelas classes de negócios para interagir com o banco de dados, e pode ser implementado usando diferentes tecnologias de acesso a dados, como JDBC, Hibernate, JPA, etc.

## Vantagens do DAO
O DAO oferece várias vantagens na programação de aplicativos orientados a objetos. Algumas dessas vantagens incluem:

Separação de preocupações: O DAO separa a lógica de acesso a dados da lógica de negócios, permitindo que cada uma seja gerenciada separadamente.

Reutilização de código: O DAO pode ser reutilizado em várias partes da aplicação, evitando a duplicação de código e reduzindo o risco de erros.

Manutenção facilitada: Como a lógica de acesso a dados é encapsulada em um objeto separado, a manutenção do código é mais fácil. Mudanças em um banco de dados podem ser gerenciadas sem afetar as outras partes da aplicação.

Melhor desempenho: O DAO pode ser otimizado para melhorar o desempenho, permitindo que as consultas sejam escritas de forma mais eficiente e que o acesso aos dados seja otimizado.

## Implementação do DAO
A implementação do DAO pode variar dependendo da tecnologia de acesso a dados usada e da estrutura da aplicação. No entanto, a maioria das implementações do DAO segue um padrão básico:

Interface DAO: Define os métodos que serão implementados pela classe DAO concreta.

Classe DAO concreta: Implementa os métodos definidos na interface DAO.

Objeto de domínio: Representa os dados que são acessados pelo DAO.

