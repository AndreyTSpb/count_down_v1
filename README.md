# count_down_v1

Простой счетчик обратного отчета.

>Время для обратного отчета берет из HTML страницы где должен быть расположен
>```js
>/**
>* Плейс холдеры для счетчика  
>*/
>let ph_hour = document.querySelector('#timer .hours'),
>    ph_min  = document.querySelector('#timer .minutes'),
>    ph_sec  = document.querySelector('#timer .seconds');
>

>Для получения unix timestamp просто складывает и полученые часы и минуты
>ас*60 + мин*60 + секунды
