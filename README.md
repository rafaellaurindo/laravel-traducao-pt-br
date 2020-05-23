# Tradução Laravel(5.x, 6.x e 7.x) para português(pt-br)

> Mensagens padrões do Laravel em português.

[![GitHub issues][issues-image]][issues-url]
[![License][license-image]][license-url]

Arquivos de tradução para todas as mensagens padrões do [Laravel](https://laravel.com/) à partir da versão 5.x, suportando até a versão 7.x.

## Traduções Inclusas

- Erros de `validação`.
- Textos de `paginação`.
- Textos de falhas de `autenticação`.
- Textos de `redefinição de senhas`.

## Como utilizar

Clone o projeto para dentro do diretório **resources/lang/** do seu projeto Laravel, nomeando à pasta como **pt-br**:

```shellscript
git clone https://github.com/rafaellaurindo/laravel-traducao-pt-br ./resources/lang/pt-br
```

Então, edite o arquivo **config/app.php** para alterar o idioma padrão da sua aplicação:

```php
// encontre a seguinte linha:
'locale' => 'en',

// e altere para:
'locale' => 'pt-br',
```

Pronto! Seu projeto agora estará em português. :tada:

## Tutorial Passo a Passo

Eu escrevi um post para o meu [blog](https://rafaellaurindo.dev) onde mostro como traduzir o seu projeto Laravel e criar aplicações multi-idiomas de forma fácil e simplificada. [Clique aqui](https://rafaellaurindo.dev/como-criar-aplicacoes-multi-idiomas-com-laravel) para ver esse post.

## Meta

Rafael Laurindo – [@rafaellaurindo](https://rafaellaurindo.dev) – eu@rafaellaurindo.dev

Distributed under the MIT license. See [LICENSE](https://github.com/rafaellaurindo/laravel-traducao-pt-br/blob/master/LICENSE) for more information.

[https://github.com/rafaellaurindo](https://github.com/rafaellaurindo/)

## Donation

If this project have helped you in any way, consider buying me a :coffee:

Using Paypal:

<a href="https://www.buymeacoffee.com/rafaellaurindo" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-yellow.png" alt="Buy Me A Coffee" style="height: 47px !important;width: 217px !important;" ></a>

## Contributing

1. Fork it (<https://github.com/rafaellaurindo/laravel-traducao-pt-br/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -am 'Add some fooBar'`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request

[issues-image]: https://img.shields.io/github/issues/rafaellaurindo/laravel-traducao-pt-br.svg
[issues-url]: https://github.com/rafaellaurindo/laravel-traducao-pt-br/issues
[license-image]: https://img.shields.io/github/license/rafaellaurindo/laravel-traducao-pt-br.svg
[license-url]: https://github.com/rafaellaurindo/laravel-traducao-pt-br/blob/master/LICENSE
