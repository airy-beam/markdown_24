1. Пользователь заходит в личный кабинет [VP-1: Авторизация TO DO](https://i5kander.atlassian.net/browse/VP-1)
1. Пользователь читает меню и добавляет блюда [VP-4: Добавление блюда в корзину TO DO](https://i5kander.atlassian.net/browse/VP-4)
1. Пользователь просматривает корзину [VP-5: Просмотр корзины TO DO](https://i5kander.atlassian.net/browse/VP-5)
1. Пользователь указывает адрес доставки [VP-9: Выбор адреса доставки TO DO](https://i5kander.atlassian.net/browse/VP-9)
1. Система отображает примерное время доставки общую стоимость [VP-18: Расчет времени доставки](https://i5kander.atlassian.net/browse/VP-18) *IN PROGRESS* ;
1. Пользователь оплачивает заказ онлайн [VP-3: Онлайн оплата](https://i5kander.atlassian.net/browse/VP-3) *TO DO*
1. Система регистрирует заказ пользователя и передает в обработку менеджеру пиццерии
1. Пользователь получает СМС уведомление о том, что заказ принят в обработку [VP-13: Отправка СМС пользователю](https://i5kander.atlassian.net/browse/VP-13)
*IN PROGRESS*
1. Пиццерия готовит заказ и передает в доставку курьером
1. Курьер доставляет заказ пользователю

Альтернативные сценарии:
* Пользователь может добавить или удалить ингредиенты из блюда
* Пользователь может выбрать адрес доставки из сохраненных [VP-9: Выбор адреса доставки](https://i5kander.atlassian.net/browse/VP-9) *TO DO*
* Пользователь может сначала не регистрироваться, а добавить блюда в заказ, и просмотреть корзину. Регистрация на сайте
может происходить при оформлении заказа.

Исключения:
* В случае, если оплата онлайн не прошла, пользователю выводится соответствующее уведомление и предложение использовать
другую карту, либо опция оплатить заказ наличными
* В случае, если указанный адрес находится на расстоянии более 15 км от пиццерии, пользователю выдается уведомление, что
заказ не может быть доставлен
