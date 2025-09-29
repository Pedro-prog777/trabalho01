# Trabalho 01 - Exercícios de Programação em Python

## Descrição
Este repositório contém uma série de exercícios de programação em Python, organizados em diferentes questões. Cada questão aborda um conceito fundamental da programação, como manipulação de listas e strings, conversão de unidades, sistemas de autenticação, verificação de paridade e controle de notas.

## Estrutura do Repositório
O repositório está organizado em pastas, onde cada pasta `qX` (sendo `X` o número da questão) contém os arquivos Python relacionados àquela questão.

*   **`.git/`**: Contém os arquivos de controle de versão do Git.
*   **`q1/`**: Manipulação de listas e strings.
*   **`q2/`**: Conversor de Temperatura (Celsius e Fahrenheit).
*   **`q3/`**: Sistema de Autenticação Simples.
*   **`q4/`**: Verificador de Números Pares e Ímpares.
*   **`q5/`**: Controle de Notas (Média, Maior, Menor).
*   **`q6/`**: Conversor de Moedas (Real para Dólar e vice-versa).

## Como Executar os Projetos

Para executar qualquer um dos projetos, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/seu-usuario/trabalho01.git
    ```
    (Lembre-se de substituir `seu-usuario` pelo seu nome de usuário do GitHub e `trabalho01` pelo nome real do seu repositório, se for diferente.)

2.  **Navegue até a pasta do projeto desejado:**
    ```bash
    cd trabalho01/trabalho01/qX 
    ```
    (Substitua `X` pelo número da questão, por exemplo, `q1`, `q2`, etc.)

3.  **Execute o arquivo `main.py`:**
    ```bash
    python main.py
    ```

## Detalhes das Questões

### Questão 1: Manipulação de Listas e Strings
*   **Arquivo:** `q1/main.py`
*   **Funcionalidade:** Conta a ocorrência de uma palavra específica em uma frase, ignorando maiúsculas e minúsculas.

### Questão 2: Conversor de Temperatura
*   **Arquivos:** `q2/main.py`, `q2/converso.py`
*   **Funcionalidade:** Converte temperaturas entre Celsius e Fahrenheit. As funções de conversão estão em `converso.py` e são importadas por `main.py`.

### Questão 3: Sistema de Autenticação Simples
*   **Arquivos:** `q3/main.py`, `q3/Trabalho wagner git hub.py`
*   **Funcionalidade:** Autentica usuários com base em um dicionário pré-definido de usuários e senhas.
    *   **Observação:** Há dois arquivos com funcionalidade idêntica (`main.py` e `Trabalho wagner git hub.py`). Recomenda-se manter apenas um para evitar redundância.

### Questão 4: Verificador de Números Pares e Ímpares
*   **Arquivo:** `q4/main.py`
*   **Funcionalidade:** Recebe um número inteiro e retorna se ele é par ou ímpar.

### Questão 5: Controle de Notas
*   **Arquivos:** `q5/main.py`, `q5/notas.py`
*   **Funcionalidade:** Permite ao usuário inserir notas, calcula a média, e encontra a maior e menor nota. As funções de cálculo estão em `notas.py`.

### Questão 6: Conversor de Moedas
*   **Arquivos:** `q6/main.py`, `q6/converso.py`
*   **Funcionalidade:** Converte valores entre Real e Dólar, utilizando uma cotação fornecida pelo usuário. As funções de conversão estão em `converso.py`.

## Contribuição
Sinta-se à vontade para explorar o código, sugerir melhorias ou corrigir bugs.

## Autor
[Seu Nome ou Nome do Autor]

## Licença
Este projeto está licenciado sob a [Nome da Licença, por exemplo, MIT License]. Veja o arquivo `LICENSE` para mais detalhes.
