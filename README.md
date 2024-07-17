# PromoWatcher Bot

## Descrição
O PromoWatcher é um bot do Telegram desenvolvido para monitorar automaticamente grupos de ofertas, filtrando e enviando as promoções mais relevantes para um grupo específico no Telegram. Ele usa critérios personalizados para selecionar ofertas, garantindo que você receba apenas aquelas que são verdadeiramente relevantes para suas necessidades.

## Características
- Monitoramento contínuo de grupos de ofertas no Telegram.
- Filtragem de ofertas baseada em critérios personalizados.
- Envio automático de ofertas selecionadas para um grupo específico.
- Configuração fácil através de comandos do Telegram.
- Ideal para caçadores de promoções e compradores que querem economizar tempo e dinheiro.

## Tecnologias Utilizadas
- Python
- Telethon
- python-telegram-bot
- Spacy para processamento de linguagem natural
- Heroku para hospedagem
- GitHub Actions para CI/CD

## Configuração
### Pré-requisitos
- Ter uma conta no Telegram.
- Ter uma conta no Heroku.
- Ter uma conta no GitHub para deploy através do GitHub Actions.

### Instalação
1. Clone o repositório:
git clone https://github.com/higordepadua/promowatcher-bot.git
2. Instale as dependências:
pip install -r requirements.txt
3. Configure as variáveis de ambiente conforme descrito em `.env.sample`.

## Uso
Para iniciar o bot, execute:
python bot.py

### Comandos do Bot
- `/start` - Inicia o bot e exibe os comandos disponíveis.
- `/addgroup <group_id>` - Adiciona um grupo ao monitoramento.
- `/removegroup <group_id>` - Remove um grupo do monitoramento.
- `/setdestinationgroup <group_id>` - Define o grupo onde as mensagens filtradas serão enviadas.
- `/setsearch "<criteria>"` - Define os critérios de busca para filtragem de ofertas.
- `/clearsearch` - Limpa todos os critérios de busca estabelecidos.
- `/help` - Mostra informações sobre os comandos disponíveis.

## Contribuições
Contribuições são sempre bem-vindas! Por favor, leia o arquivo CONTRIBUTING.md para saber como ajudar.

## Licença
Distribuído sob a licença MIT. Veja `LICENSE` para mais informações.

## Contato
Higor de Pádua - @higordepadua

Link do Projeto: [https://github.com/higordepadua/promowatcher-bot](https://github.com/higordepadua/promowatcher-bot)
