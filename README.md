Clash of clan - Arena
===========

Description
---------------

EM CONSTRUCAO

Requirements
-------------------

 * Java => 7.0
 * Maven3
 * Mysql


Installation
--------------

    # Baixando o codigo fonte
    git clone https://github.com/evertonAmaralSP/arena
    cd arena

    # Use maven para installar as dependencias
    mvn clean compile

    # Criar schema mysql
    ./recipes/mysql/create-database.sh
    mvn flyway:clean flyway:migrate


Running 
------------------------------

Start aplicação:

    mvn jetty:run

Eclipse 
------------------------------

Start project eclipse:

    mvn eclipse:eclipse -Dwtpversion=2.0

Configurações
------------------------------

    flyway: pom.xml
    dataSource: arena.properties
    Pasta raiz para exportar arquivos: arena.properties

Contributors
------------

 * Everton Amaral <everton.amaral@gmail.com>


License
-------

  (The MIT License)

  Permission is hereby granted, free of charge, to any person obtaining
  a copy of this software and associated documentation files (the
  'Software'), to deal in the Software without restriction, including
  without limitation the rights to use, copy, modify, merge, publish,
  distribute, sublicense, and/or sell copies of the Software, and to
  permit persons to whom the Software is furnished to do so, subject to
  the following conditions:

  The above copyright notice and this permission notice shall be
  included in all copies or substantial portions of the Software.

  THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
  EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
  MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
  IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
  CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
  TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
  SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
