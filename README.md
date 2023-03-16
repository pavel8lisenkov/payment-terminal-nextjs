## Web приложение - терминал оплаты мобильного телефона

### Демо приложения
[Payment terminal](https://payment-terminal-alpha.vercel.app/)

В приложении есть:
1. Главный экран со списком операторов - МТС, Билайн, Tele2, Мегафон.
2. Список расширяем.
3. По клику на оператора переходим на экран формы оплаты.
 3.1. Экран с формой оплаты соответствует выбранному оператору
 3.2. Поле ввода телефона с маской и валидацией.
 3.3. Поле ввода суммы в рублях с маской и валидацией (мин 1 и макс 1000 руб)
 3.4. Кнопка подтверждения оплаты.
4. После ответа показывается сообщение об успехе или об ошибке. В случае успеха переход на основной экран.

5. Стэк:
 5.1. TypeScript
 5.2. Next.js
 5.3. React и React Hooks
 5.4. Styled-Components

- Обращение к API эмулировано. Ответы успешные или неуспешные в случайном порядке.

#### Запуск локально по команде npm run serve
