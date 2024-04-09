# Exercício 4 - Branches

1. Crie uma nova pasta chamada `exercicio-4-branches`.
2. Crie um novo repositório git dentro da pasta (certifique-se de que não está em um repositório existente).
3. Crie um novo arquivo chamado `patronus.py` (deixe-o vazio por enquanto).
4. Adicione e comite o arquivo vazio, com a mensagem "adicionar arquivo patronus vazio".
5. Imediatamente crie uma nova branch chamada `harry` e outra branch chamada `snape` (ambas baseadas na branch principal).
6. Mude para a branch `harry` usando o comando "switch" para trocar de branch.
7. No arquivo `patronus.py`, adicione o seguinte:

```python
desenho = """
HARRY'S PATRONUS

   /|       |\\
`__\\       //__'
   ||      ||
 \__`\     |'__/
   `_\\   //_'
   _.,:---;,._
   \_:     :_/
     |@. .@|
     |     |
     ,\.-./ \\
     ;;`-'   `---__________-----.-.
     ;;;                         \_\\
     ';;;                         |
      ;    |                      ;
       \   \     \        |      /
        \_, \    /        \     |\\
          |';|  |,,,,,,,,/ \    \ \_
          |  |  |           \   /   |
          \  \  |           |  / \  |
           | || |           | |   | |
           | || |           | |   | |
           | || |           | |   | |
           |_||_|           |_|   |_|
          /_//_/           /_/   /_/
"""
print(desenho)
```

8. Adicione e comite as alterações, com a mensagem de commit "adicionar patrono de cervo de Harry".
9. Mude para a branch `snape` usando o comando "checkout" para trocar de branch.
10. Coloque o seguinte texto no arquivo `patronus.py`:

```python
desenho = """
PATRONO DE SNAPE
                       .     _,
                       |`\__/ /
                       \  . .(
                        | __T|
                       /   |
          _.---======='    |
         //               {}
        `|      ,   ,     {}
         \      /___;    ,'
          ) ,-;`    `\  //
         | / (        ;||
         ||`\\\        |||
         ||  \\\       |||
         )\   )\      )||
         `"   `"      `""
"""
print(desenho)
```

11. Adicione e comite as alterações na branch `snape` com a mensagem de commit "adicionar patrono de doe de Snape".
12. Em seguida, crie uma nova branch com base na branch `snape` chamada `lily`.
13. Mude para a branch `lily`.
14. Edite o arquivo `patronus.py` para que diga `PATRONO DE LILY` no topo em vez de `PATRONO DE SNAPE` (deixe a arte ASCII da doe como está).
15. Adicione e comite a alteração com a mensagem "adicionar patrono de doe de Lily".
16. Execute um comando git para listar todos as branch (você deverá ver 4).
