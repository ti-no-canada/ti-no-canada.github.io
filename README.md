# Repositório oficial da comunidade TI no Canadá

O [Portal TI no Canadá](https://ti-no-canada.github.io) é o site oficial da comunidade TI no Canadá no Telegram, servindo como um centro de recursos, atualizações e informações. Contribuições são bem-vindas através de **Pull Requests**.

## Como Contribuir

### Configuração do Ambiente de Desenvolvimento Local

1. Clone o repositório:

  ```bash
  git clone https://github.com/ti-no-canada/ti-no-canada.github.io.git
  ```

2. Navegue até o diretório do projeto:

  ```bash
  cd src
  ```

3. Construa e inicie o ambiente de desenvolvimento usando Docker:

  ```bash
  docker-compose up --build
  ```

4. Acesse o site localmente em `http://localhost:4000`.


5. Se você precisar incluir novas dependências e gerar o arquivo `Gemfile.lock`

```bash
docker run --rm -v "${PWD}:/usr/src/app" -w /usr/src/app ruby:3.2 bundle install
```

Sinta-se à vontade para contribuir e ajudar a melhorar esta plataforma!

## Sobre o Template Jekyll

Este projeto utiliza o tema [Just the Docs] para Jekyll, que oferece suporte para:

- Implantação no GitHub Pages via Actions
- Builds e previews locais
- Fácil personalização e suporte a plugins

## Licenciamento

Este repositório está licenciado sob a [Licença MIT]. Sinta-se à vontade para reutilizar ou estender o código, e nos avise como podemos melhorá-lo!

[Just the Docs](https://just-the-docs.github.io/just-the-docs/)
[use this template](https://github.com/just-the-docs/just-the-docs-template/generate)
[Licença MIT](https://pt.wikipedia.org/wiki/Licen%C3%A7a_MIT)


# Agradecimentos

Agradecemos aos membros que contribuíram com este repositório, ajudando muitas pessoas no processo de imigração.

![GitHub Contributors Image](https://contrib.rocks/image?repo=ti-no-canada/imigracao-para-o-canada)
