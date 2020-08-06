# x

Репозиторий для быстрого клонирования

```
mkdir $(date +%Y%m%d_%H%M%S) && cd $_ && git clone https://github.com/GossJS/x.git . && yarn
```

```

curl kodaktor.ru/x -o index.js
  или
wget kodaktor.ru/x -O index.js

  или
curl -SLO kodaktor.ru/x.js
```
https://raw.githubusercontent.com/GossJS/x/master/index.js

Для исследований и дебаггинга может быть удобно:

* `bash <(curl -s https://kodaktor.ru/g/eslint_exec)`
* запустить node в папке с этим файлом и сделать .load index.js
* использовать именованные функции в обработчиках – так будет информативнее выглядеть стек

https://kodaktor.ru/x0 – чуть меньше кода: минималистичный вариант после демо-создания с нуля

https://kodaktor.ru/x2 – чуть больше добавок: шутдаун и пост + content negotiation
