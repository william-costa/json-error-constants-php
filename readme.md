# Array PHP com constantes e mensagens de erro JSON

Parte do código de implementação do analisador de erros JSON, apresentado no canal [WDEV](https://youtube.com/wdevoficial).

___________________

## Vídeo WDEV

Para assistir o vídeo sobre manipulação de dados em JSON acesse: [Manipulando JSONs com PHP: Encode, decode e constantes (YouTube)](https://youtu.be/MYMGMg1StVk)
___________________

## Array de constantes de erro JSON

```php
  $jsonErrors = [
    JSON_ERROR_NONE => 'Nenhum erro',

    JSON_ERROR_DEPTH => 'O limite da pilha de camadas foi ultrapassado',

    JSON_ERROR_STATE_MISMATCH => 'Ocorre em underflows ou com incongruência de modos',

    JSON_ERROR_CTRL_CHAR => 'Erro em caracter de controle, possivelmente erro de enconding',

    JSON_ERROR_SYNTAX => 'Erro de sintaxe',

    JSON_ERROR_UTF8 => 'Caracteres UTF-8 mal formados, possivelmente erro de enconding',

    JSON_ERROR_RECURSION => 'O objeto ou array passado para json_encode() inclui referências recursivas, e não pôde ser formatada',

    JSON_ERROR_INF_OR_NAN => 'Um valor passado para json_encode() inclui NAN ou INF',

    JSON_ERROR_UNSUPPORTED_TYPE => 'Um valor de um tipo não suportado foi informado para json_encode()'
  ];
```

___________________

## Canal no YouTube
<img height="60" style="margin-bottom:10px;" src="https://raw.githubusercontent.com/william-costa/william-costa/master/assets/images/logo-wdev.png">

Canal de tecnologia com conteúdos sobre programação e super dicas para a galera que está começando no mundo dev.

Todo **sábado** às **20h** tem vídeo novo, então inscreva-se para não perder nenhuma novidade:

<a href="https://youtube.com/wdevoficial"><img height="30" src="https://raw.githubusercontent.com/william-costa/william-costa/master/assets/images/subscribe-youtube.png"></a>