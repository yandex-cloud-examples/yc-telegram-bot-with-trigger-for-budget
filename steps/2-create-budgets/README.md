# Шаг 2. Создание бюджета

Для создания бюджета необходима роль `editor` у пользователя. Для получения оповещений достаточно роли `viewer`. 

Используйте [инструкцию](https://cloud.yandex.ru/docs/billing/operations/budgets), чтобы создать бюджет в web-консоли Yandex Cloud. Обязательно укажите облако и каталог в котором вы ведете работу в рамках этого сценария. 

При создании укажите типа бюджета `К оплате`, период рассчета `Месячный`, в качестве даты окончания используйте конец текущего года, а в поле `Уведомить` выберете себя. Вы можете установить любую доступную вам `Сумму` в бюджете, но для эксперимента я бы рекомендовал установить `100` рублей и два порога `50%` и `100%`.   

## Видео

https://youtu.be/3rj4OhUyA2M
