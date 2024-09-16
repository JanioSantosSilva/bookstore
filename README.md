# Projeto Django com Poetry

Este é um projeto Django configurado para usar o Poetry para gerenciamento de dependências.

## Requisitos

- Python 3.8+
- Poetry

## Instalação

1. Clone o repositório:

    ```bash
    git clone https://github.com/seu-usuario/seu-projeto.git
    cd seu-projeto
    ```

2. Instale as dependências usando o Poetry:

    ```bash
    poetry install
    ```

3. Ative o ambiente virtual do Poetry:

    ```bash
    poetry shell
    ```

4. Configure o banco de dados:

    ```bash
    python manage.py migrate
    ```

5. Crie um superusuário para acessar o admin do Django:

    ```bash
    python manage.py createsuperuser
    ```

6. Inicie o servidor de desenvolvimento:

    ```bash
    python manage.py runserver
    ```

## Estrutura do Projeto

- `manage.py`: Script de gerenciamento do Django.
- `pyproject.toml`: Arquivo de configuração do Poetry.
- `README.md`: Este arquivo.
- `app/`: Diretório principal da aplicação Django.

## Comandos Úteis

- `poetry add <pacote>`: Adiciona um novo pacote.
- `poetry update`: Atualiza as dependências.
- `python manage.py <comando>`: Executa comandos do Django.

## Contribuição

1. Faça um fork do projeto.
2. Crie uma nova branch (`git checkout -b feature/nova-feature`).
3. Commit suas mudanças (`git commit -am 'Adiciona nova feature'`).
4. Faça o push para a branch (`git push origin feature/nova-feature`).
5. Abra um Pull Request.

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.
