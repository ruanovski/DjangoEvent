# Agenda de Eventos em Django 📅

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/ruanovski/DjangoEvent/blob/main/LICENSE)


## Descrição do Projeto

Este projeto é uma aplicação web construída em Django com Bootstrap para criar uma agenda de eventos. A aplicação requer autenticação, e uma vez logado, o usuário pode adicionar, editar e excluir eventos de sua agenda.

## Funcionalidades

1. **Autenticação:**
   - A aplicação exige login para acessar as funcionalidades principais.
   - Os usuários podem se cadastrar ou usar credenciais existentes.

2. **Adicionar Evento:**
   - Os usuários autenticados podem adicionar novos eventos à sua agenda.
   - Cada evento inclui informações como título, data, hora e local.

3. **Editar Evento:**
   - Permite aos usuários editar detalhes de eventos existentes.
   - A edição inclui a capacidade de modificar título, data, hora e local.

4. **Excluir Evento:**
   - Oferece aos usuários a opção de excluir eventos indesejados.

## Pré-requisitos

- Python 3.8 ou superior
- Django 3.0 ou superior

## Como Usar

   1. Clone o repositório para o seu ambiente local:

   ```bash
   git clone  https://github.com/ruanovski/DjangoEvent.git
   ```

  2. Navegue até o diretório do projeto:

   ```bash
   cd AgendaEvent
   ```

   3. Instale as dependências
   ```bash
   pip install -r requirements.txt
   ```

   4. Aplique as migraçoes
   ```bash
   python manage.py migrate
   ```

   5. Execute o servidor django
   ```bash
   python manage.py runserver
   ```

## Login para teste
- usuario: Leoteste
- senha: zeroumdois



## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests para melhorias ou correções.

## Licença
Este projeto está licenciado sob a Licença MIT - consulte o arquivo LICENSE para obter detalhes.

## Agradecimentos
Agradecemos por utilizar e contribuir para este projeto. Esperamos que seja útil para aprender conceitos básicos de programação em Python e lógica de sistemas bancários simples.
