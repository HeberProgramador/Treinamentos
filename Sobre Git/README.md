

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

* Podemos criar tags...

Exemplo:
``` git tag -a v1.0 -m "Versão 1.0 do web site" ``` 

### Branch

* Utilize o git branch para verificar suas branch's

- para criar branch utilize o comando:
``` git branch nomeDaBranch ´´´
Exemplo: git branch Homologacao

* Utilize o git checkout e o nome da branch para mudar de uma branch para outra
- Por exemplo 'git checkout homologacao' irá mudar para branch homologacao

### Para fazer merge

* Para fazer um merge devemos voltar para branch principal e utilizar o seguinte comando:

``` git merge NomeDaBranch ```

### Podemos utilizar interface gráficas para visualizar os commits

* Uma sugestão é utilizar Sublime Merge

[https://www.sublimemerge.com/](Sublime Merge)