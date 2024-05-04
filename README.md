# PontoReminderBot

PontoReminderBot é um bot do Telegram que ajuda a lembrar os usuários de bater o ponto em horários específicos.

### Configuração

Para executar este bot em sua própria máquina ou em um servidor, siga estas etapas:

1 - Clone o repositório: 

```bash
git clone https://github.com/isaahmdantas/ponto-reminder-bot.git
```

2 - Configuração do Ambiente Virtual

Para garantir uma instalação limpa e isolada das dependências do projeto, recomenda-se configurar um ambiente virtual. Siga estas etapas para configurar e instalar o projeto em um ambiente virtual:

* Crie um ambiente virtual: Execute o seguinte comando para criar um ambiente virtual chamado venv:
    ```bash 
    python3 -m venv venv
    ```

* Ative o ambiente virtual: Para ativar o ambiente virtual, use o comando apropriado para o seu sistema operacional:
    * No Linux/macOS:
    ```bash 
    source venv/bin/activate
    ```
    * No Windows:
    ```bash 
    venv\Scripts\activate
    ```

3 - Instale as dependências: Com o ambiente virtual ativado, você pode usar o pip para instalar as dependências do projeto. Execute o seguinte comando para instalar:

```bash
pip install python-telegram-bot python-dotenv
```

4 - Configure as variáveis de ambiente: Crie um arquivo .env na raiz do projeto e adicione suas credenciais:

```
TELEGRAM_BOT_TOKEN=seu_token_aqui
```

NOTE: Substitua seu_token_aqui pelo token do seu bot do Telegram. Certifique-se de não compartilhar suas credenciais publicamente!


5 - Execute o bot: Agora que o ambiente virtual está configurado e as dependências estão instaladas, você está pronto para executar o bot. Basta executar o script bot.py:

```
python bot.py
```

O bot estará pronto para uso e responderá às mensagens recebidas no Telegram.

6 - Interaja com o bot: Inicie uma conversa com o bot no Telegram e siga as instruções para configurar seu nome e horário de chegada. O bot irá lembrá-lo de bater o ponto nos horários especificados.

7 - Desativar o ambiente virtual: Quando terminar de trabalhar com o projeto, você pode desativar o ambiente virtual usando o comando:

```bash 
deactivate
```

Isso retornará ao ambiente Python global do sistema.


### Funcionalidades

* Registro do nome do usuário e horário de chegada.
* Lembrete de bater o ponto nos horários configurados.
* Suporte a múltiplos usuários.

### Contribuição

Contribuições são bem-vindas! Se você quiser contribuir com este projeto, siga estas etapas:

* Fork o projeto
* Crie uma branch para sua feature (`git checkout -b feature/SuaFeature`)
* Faça commit das suas alterações (`git commit -am 'Adiciona uma nova feature' `)
* Faça push para a branch (`git push origin feature/SuaFeature`)
* Abra um Pull Request

Por favor, certifique-se de que seus Pull Requests seguem as diretrizes do projeto.

### Licença

Este projeto é licenciado sob a Licença MIT.






