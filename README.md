<p align="center"><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/logo.svg"/></a><br/><a href="https://xxai.art"><img src="https://cdn.jsdelivr.net/gh/xxai-art/doc/xxai.svg"/></a></p><p align="center"><a href="https://github.com/xxai-art/doc#readme"><img alt="I18N" src="https://cdn.jsdelivr.net/gh/wactax/img/t.svg"/></a>　<a href="https://groups.google.com/u/0/g/xxai-art"><img alt="Google Groups" src="https://cdn.jsdelivr.net/gh/wactax/img/g-groups.svg"/></a></p>

# xxAI.уметност

Дел од кодот на веб-локацијата е со отворен код, добредојдовте да помогнете во оптимизирање на преводот.

## преден код

* [преден код](https://github.com/xxai-art/web)
* [Јазични пакети за страницата како целина](https://github.com/xxai-art/web/tree/main/i18n)
* [Јазични пакети за модули за најавување](https://github.com/wacpkg/user/tree/main/ui.i18n)
* [Повеќејазична документација на веб-страница](https://github.com/xxai-doc)

Програмскиот јазик од предниот дел е [@w5/coffee_plus](http://npmjs.com/@w5/coffee_plus) , кој додава некои функции засновани на синтаксата на coffeescript, видете [./coffee_plus.md](./coffee_plus.md) .

## Интернационализација на веб-страници и документи

Изградете ги следните 3 проекти

* [@w5/mdt](https://www.npmjs.com/package/@w5/mdt)

  Наставката е `.mdt` , можете да ја користите синтаксата слична на `<+ ./coffee_plus/import.js>` за да се однесувате на надворешни датотеки и да генерирате ознака со наставката `.md` .

* [@w5/trmd](https://www.npmjs.com/package/@w5/trmd)

  Преводот на Markdown нема да преведува шифри и врски и ќе ги кешира преведените реченици. Ако преводот е изменет, но оригиналниот текст не е изменет, неговото повторно извршување нема да ја презапише модификацијата на преводот.

* [@w5/i18n](https://www.npmjs.com/package/@w5/i18n)

  Јазични датотеки за превод на веб-страници генерирани `yaml` .
