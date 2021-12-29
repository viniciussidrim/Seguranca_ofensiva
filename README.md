# Destinado a cdigos para Segurança Ofensiva <h2>

**Arquivo: Shell.php**

* **FINALIDADE:** Ser enviado a sites que não tem verificação de extensões (Upload de arquivos) e utiliizam requisições $_GET

* **USO:** 

  * Ao ser enviado, realize a abertura da página do mesmo (Ex: http://teste/diretorio/script.php)

    * No final da URL insira " = comando" , (Desconsiderar as aspas duplas)

    * Onde está escrito "comando" pode ser quaisquer comando do linux 
      * EX: http://teste/diretorio/script.php = ls
        * O mesmo ira listar todos os arquivos no diretório atual
        * Diante disso, pode-se navegar e realizar diversas alterações no servidor como criar pastas com mkdir, ler arquivos com o cat e criar arquivos.

**CÓDIGO TESTE, NÃO ME RESPONSABILIZO POR QUAISQUER PESSOA MAL INTENCIONADA QUE UTILIZE OS CODIGOS AQUI MENCIONADOS PARA PRATICAR ATIVIDADES FORA DA LEI**
