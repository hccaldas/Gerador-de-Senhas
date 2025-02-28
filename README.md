# Gerador de Senhas em Python

Este repositório contém um script em Python que gera senhas aleatórias. O usuário pode especificar o tamanho da senha, e o script irá gerar uma senha contendo letras maiúsculas, minúsculas, dígitos e caracteres de pontuação.

## Funcionalidades

- Geração de senhas aleatórias.
- Personalização do tamanho da senha.

## Pré-requisitos

- Python 3.x

## Como usar

1. Clone este repositório ou copie o código para o seu ambiente local.
2. Certifique-se de ter o Python 3.x instalado no seu sistema.
3. Execute o script.
4. Insira o tamanho desejado para a senha quando solicitado.
5. A senha gerada será exibida na tela.

## Exemplo de Uso

```python
"
import random 
import string

def gerar_senha(tamanho=12):
    caracteres = string.ascii_letters + string.digits + string.punctuation
    senha = ''.join(random.choice(caracteres) for _ in range(tamanho))
    return senha

tamanho = int(input("Digite o tamanho da senha: "))
print(f"Senha gerada: {gerar_senha(tamanho)}")
"

Contribuição
Sinta-se à vontade para contribuir com melhorias para este projeto. Você pode fazer isso abrindo uma issue ou enviando um pull request.

