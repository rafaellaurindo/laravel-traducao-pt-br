# Tradução do Laravel 5.8 para português (pt-br)

Esses arquivos de tradução traz em português todas as mensagens padrões do laravel 5.8.

## Como utilizar

Clone o projeto para dentro do diretório **resources/lang/** do seu projeto, nomeando à pasta como **pt-br**:

```bash
cd resources/lang/
git clone https://github.com/rafaellaurindo/laravel-5.8-pt-br-localization ./pt-br
rm -rf ./pt-br/.git
```

Então, edite o arquivo **config/app.php** para alterar o idioma padrão da sua aplicação:

```php
// encontre a seguinte linha:
'locale' => 'en',

// e altere para:
'locale' => 'pt-br',
```

Pronto! Seu projeto agora estará em português. :tada:

## Contribuindo

*Pull requests* são sempre bem-vindos. Para alterações importantes, por favor, abra uma *issue* primeiro para discutir o que você gostaria de mudar.

## License

[MIT](https://github.com/rafaellaurindo/laravel-5.8-pt-br-localization/blob/master/LICENSE)
