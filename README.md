# Bot de Divulgação para Telegram

Este bot envia mensagens automaticamente para um grupo do Telegram em intervalos de tempo configuráveis. Ele é ideal para divulgar informações, promoções ou qualquer outra mensagem de forma periódica.

## Requisitos

- PHP 7.4 ou superior
- [Composer](https://getcomposer.org/) para gerenciar dependências
- Extensão cURL do PHP

## Instalação

1. **Clone o repositório:**

    ```sh
    git clone https://github.com/Hacker666EXE/Spectrebot/
    cd seu-repositorio
    ```

2. **Instale o PHP e Composer (se ainda não tiver):**

    ```sh
    pkg update && pkg upgrade
    pkg install php
    pkg install composer
    ```

3. **Instale as dependências do projeto:**

    ```sh
    composer require guzzlehttp/guzzle
    ```

4. **Configure as credenciais do seu bot:**

    - Edite o arquivo `BotPHP.php` e insira o token do seu bot e o ID do grupo:

      ```php
      $TOKEN = 'SEU_TOKEN_DO_BOT';
      $CHAT_ID = 'ID_DO_GRUPO';
      $MENSAGEM = "Para dar parágrafo escreva \\n , exemplo : Compre no nosso site \\n www.compreaqui.com ;)";
      ```

## Uso

1. **Execute o bot:**

    ```sh
    php BotPHP.php
    ```

2. **Monitorar a saída:**

    - O bot irá exibir no terminal o tempo restante até a próxima mensagem.

