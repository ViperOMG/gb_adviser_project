# GB ADviser Project


## Задание:
`1. Реализовать верстку предоставленного дизайн-макета`
<br> </br>

`2. Реализовать адаптивный дизайн `

>[!NOTE]
>[Макет в Figma](https://www.figma.com/file/bNTF4VVYd23Fo84jjh5AeB/GB-Adviser?type=design&node-id=0-1&mode=design&t=W17AqDvx3HqtZWNz-0)
>
>[Смотреть работу тут](https://viperomg.github.io/gb_adviser_project/)

 __Что было сделано:__
 > -Реализован адаптивный дизайн


 > -Для широкоформатных экранов реализовано ограничение, для комфортного восприятия интерфеса



 > -Увеличены внутренние отступы на всех кнопках в `navbar` и `aside bar`, для комфортного взаимодействия как на десктопах, так и на мобильных устройствах. 

 > -`Кнопка` вызова меню перенесена в нижнюю часть экрана на мобильных устройствах ( ИМХО: так удобнее, чем тянуться на самый вверх, хотя возможно первое время не привычно )

 > -Исправлены иконки в `navbar`, теперь при наведении и фокусе на элементе - иконка перекрашивается в светлый цвет. 

 > -Реализован кастомный `scrollbar` , теперь выглядит современно и красиво 

 > -Реализована система `TAB`-переключения в `Допольнительной информации`; для того чтобы сильно не дергать темплейт - реализовано органичение окна и добален скролл.

 > -Нажать на кнопку `да` в оценке статьи можно один раз; После ее нажатия рядом появляется уведомление с благодарностью

![image](https://github.com/ViperOMG/gb_adviser_project/assets/81018280/93c37d76-7391-4a41-802e-5d8074ee83ec)


 > -При нажатии на кнопку `нет` в оценке статьи вызывает `модал окно` для отправки комментария.

 > -При вызове `меню` или `модал-окна` отключен скролл страницы, так же страница не прыгает при вызове этих компонентов.

 > -Реализовано прилипание `navbar` и `aside bar` при скролле, для более удобного взаимодествия с интерфейсом

 > -При нажтатии на `поиск` в настройках профиля реализованы быстрые сниппеты ( в перспективе упроситить пользовтелям взаимодействие )

![image](https://github.com/ViperOMG/gb_adviser_project/assets/81018280/38913371-e24f-41c9-a876-59c9b45b9478)


 >[!TIP]
 >Рекомендуется подобный проект либо делать частично на php для переиспользования компонентов, таких как `navbar` `header` `aside bar` `footer` 
 >Или делать как приложение: комплекс из бэка и фронта на vue/react или nuxt 
___
