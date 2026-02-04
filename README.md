# 🔢 Gerador de CPF 

Este é um projeto desenvolvido em Python com o objetivo de gerar números de CPF (Cadastro de Pessoas Físicas) válidos, seguindo o algoritmo oficial de cálculos de dígitos verificadores.
O projeto foi criado para fins de estudo da lógica de programação e manipulação de strings e inteiros.

## 💻 Tecnologias

- Python 3.10+.
- Biblioteca random.

## ⚙️ Instalação

- Certifique-se de ter o Python instalado (versão 3.10 ou superior).
- Baixe o arquivo Gerador_CPF.py.
- Abra o terminal na pasta do arquivo e execute:

```bash
python Gerador_CPF.py
```

## 🛠️ Funcionalidades

O programa gera um CPF de 11 dígitos válido.
| Recurso | Descrição | Detalhes |
| :--- | :--- | :--- |
| **Geração Aleatória** | Gera os 9 primeiros dígitos de forma randômica. | Utiliza a biblioteca `random`. |
| **Cálculo de Dígitos** | Calcula matematicamente o 10º e 11º dígito. | Baseado em soma ponderada e resto da divisão por 11. |
| **Validação de Sequência** | Impede a geração de CPFs com todos os números iguais. | Verifica se o CPF gerado é uma repetição (ex: 111.111.111-11). |
| **Saída Formatada** | Exibe o resultado final em dois formatos diferentes. | Apresenta o CPF "limpo" (apenas números) e o "formal" (com pontos e traço). |

## 🕹️ Como usar

1. Execute o script Python.
2. O algoritmo irá gerar automaticamente os 9 dígitos iniciais.
3. O programa realiza o cálculo matemático para encontrar os dois dígitos verificadores.
4. O CPF gerado será exibido no terminal em dois formatos: apenas números e com pontuação oficial.
5. O programa se encerra automaticamente após gerar um CPF válido.

## 💡 Exemplo de uso

Após executar o programa, o usuário visualiza o menu principal com as opções de conversão:

![Menu principal do conversor de unidades](assets/menu-principal.png)

Selecionando a opção **1**, o usuário acessa a conversão de unidades de comprimento e informa a unidade desejada:

![Escolha da unidade de comprimento](assets/escolha-unidade.png)

Em seguida, o usuário informa o valor a ser convertido:

![Entrada do valor a ser convertido](assets/entrada-valor.png)

O programa exibe o resultado da conversão e retorna ao menu principal:

![Resultado da conversão](assets/resultado-conversao.png)
## 🚀 Status do Projeto

✅ Concluído

## 👤 Autor

Feito por **Matheus Felipe Claudino de Santana**  
GitHub: https://github.com/matheuscsantana-arch
