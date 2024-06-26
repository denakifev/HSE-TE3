**Описание приложения для заказа и доставки еды**

Проектируемая система — приложение для заказа и доставки еды. Основные участники и процессы:

### Участники:
- **Пользователь**: заказывает еду через приложение.
- **Ресторан**: предоставляет меню и готовит заказы.
- **Курьер**: доставляет заказы клиентам.
- **Система приложения**: обрабатывает данные пользователей и предоставляет функционал.

### Основные сценарии использования:
1. **Заказ еды**: пользователь выбирает ресторан и блюда, оформляет заказ.
2. **Подтверждение заказа**: ресторан получает и подтверждает заказ.
3. **Подготовка заказа**: ресторан готовит блюда.
4. **Доставка заказа**: курьер доставляет заказ клиенту.
5. **Отслеживание заказа**: пользователь отслеживает статус заказа.

### Процесс заказа (диаграмма последовательности):
1. Пользователь открывает приложение и выбирает ресторан.
2. Приложение отображает меню ресторана.
3. Пользователь выбирает блюда и добавляет их в корзину.
4. Приложение вычисляет сумму заказа и предлагает оформить его.
5. Пользователь подтверждает заказ и вводит адрес доставки.
6. Приложение отправляет заказ в систему ресторана.
7. Ресторан подтверждает заказ и начинает его готовить.
8. Курьер забирает заказ и доставляет его клиенту.
9. Приложение отслеживает местоположение курьера и сообщает статус доставки пользователю.
10. Курьер доставляет заказ, пользователь получает и оплачивает его.
11. Пользователь завершает процесс доставки.

### Основные статусы заказа (диаграмма состояний):
- **Новый заказ**: ещё не обработан системой.
- **Подтвержденный заказ**: принят системой и назначен курьеру.
- **Заказ в процессе доставки**: курьер в пути.
- **Заказ доставлен**: доставлен клиенту.
- **Заказ получен**: клиент оплачивает и забирает.
- **Отмененный заказ**: отменен клиентом.

### Диаграммы:
- **Деятельности**: детализирует действия, ведущие к состояниям заказа.
- **Классов**: включает классы участников с их свойствами и методами, а также модули для различных функций.
- **Вариантов использования**: описывает основные сценарии использования приложения, такие как заказ еды, подтверждение заказа, подготовка заказа, доставка заказа и отслеживание заказа.
- **Последовательности**: показывает пошаговый процесс заказа, от выбора ресторана до доставки еды клиенту.
- **Состояний**: демонстрирует переходы между различными статусами заказа, от нового заказа до доставки и получения заказа клиентом.
