# PHP - соглашения

В этом документе определены соглашения для 
разработки php проектов

## Общие правила
1. Все новые проекты с длинным жизненным циклом должны
использовать последнюю на момент разработки версию языка,
фреймворка и библиотек. Также внедрен статический анализатор
`PHPStan`, и должны отсутствовать ошибки ниже 5 
уровня анализатора.
4. Подключение внешних библиотек возможно только через пакетный
менеджер `composer`
