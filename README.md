# Projeto de Integração Contínua com HTML e Python

Este é um projeto simples demonstrando como implementar integração contínua (CI) usando HTML e Python, com o auxílio do GitHub Actions.

## Estrutura do Projeto

- **index.html**: Arquivo HTML principal do projeto.
- **script.py**: Script em Python para atualizar dinamicamente o arquivo HTML.
- **.github/workflows/main.yml**: Arquivo de configuração do GitHub Actions para a CI.

## Funcionamento

Quando ocorre um push para o branch `main`, o GitHub Actions é acionado e executa os seguintes passos:

1. Realiza o checkout do código.
2. Configura o ambiente Python.
3. Instala as dependências Python (se houver).
4. Executa o script Python para atualizar o arquivo `index.html`.
5. Commita e faz push das alterações de volta para o repositório.

## Como Usar

1. Clone este repositório:
    ```bash
    git clone https://github.com/seu-usuario/nome-do-repositorio.git
    ```

2. Navegue até o diretório do projeto:
    ```bash
    cd nome-do-repositorio
    ```

3. Execute o projeto:
    - Abra o arquivo `index.html` em um navegador da web para visualizar a página.

4. Para contribuir:
    - Faça as alterações desejadas no código.
    - Faça commit das alterações:
        ```bash
        git add .
        git commit -m "Sua mensagem de commit"
        ```
    - Faça push das alterações:
        ```bash
        git push origin main
        ```


