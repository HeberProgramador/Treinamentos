

# Comandos Git

* Comitar sem o git add
``` git commit -a -m "descrição" ```

Este comando somente irá funcionar para arquivos que já foram adicionados uma vez anteriormente.

- O comando git diff mostra as alterações que foram realizadas no arquivo

* Modificações no stage de area

- Quando você já utilizou o git add . e enviou para stage de area você pode também ver as modificações com o comando 

``` git diff --staged ```

* Podemos utilizar o comando git log para verificar todos os commits que já fizemos

* Caso eu faço uma alteração e queira recuperar o estado do arquivo do último commit, posso utilizar git checkout -- nomeDoArquivo

``` git checkout -- README.md  ```
Neste caso ele volta na situação do último commit