# План реализации своего проекта:

1. ### Реализуем самый базовый функционал:
   добавление, поиск, изменение, удаление, свитчер


2. ### Стили - React Bootstrap или Material-UI.
   предоставляют различные компоненты, в том числе Switcher.


3. ### Записать демо с кратким обзором сделанной работы.
   * оно должно быть на английском;
   * screen recording (запись монитора, демонстрация фич с комментированием);
   * структура демо: вступление, обзор каждой фичи, завершение;
   * показать в разных браузерах (Chrome, Firefox, Safari);
   * продолжительность 3–5 минут;
   * показывать только функционал (не код).


4. ### Добавить Redux в проект.
   Переносим локальный стэйт в глобальный стор. Добавляем экшены, редюсер, подключаем стор.


5. ### Добавить тесты в проект (Jest / Enzyme)
   Покрываем тестами редюсеры, экшены и компоненты. Не стоит делать акцент на snapshots.


6. ### Пагинация
   Добавляем пагинацию. Не делаем акцент на верстке. Можно использовать готовый компонент, например bootstrap. Для реалистичного использования пагинации нужен бэкенд с базой данных, где будет возможность получать, удалять, обновлять. Еще полезно добавить возможность переключения количества notes на страничке.


7. ### Авторизация
   Форму регистрации и авторизации можно добавить в модальном окне. Но, для того чтобы охватить больше тем, эти формы надо разметить на различных страничках приложения. Для этого подключите роутер. Теперь вместо одной странички у нас целых три (1, login, sign-up). Можно также добавить валидацию для форм регистрации и входа. Formik — неплохая библиотека, которая упрощает работу с формами. Еще интересное задание — добавить авторизацию с помощью Facebook или Instagram.


8. ### Сокеты
   почему нужно отписываться от подписок в componentWillUnmount. как в одном браузере добавляет новую note, а в другом она сразу же появляется.


9. ### Локализация
   Хоть английский и популярный язык, но все же не стоит терять возможность привлечь клиентов, которые не знают его. опыт работы с библиотеками, которые упрощают внедрение локализации. i18next — неплохое решения для React-приложений.


10. ### Улучшаем производительность
    Стоит обратить внимание на React.memo, PureComponent, React.useCallback, React.useMemo и так далее. Например, сосредотачиваемся на том, чтобы при изменении состояния одной note не было re-render всех остальных. Добавляем возможность показать одновременно больше 1000 notes на страничке. Записываем демо, где сравниваем результаты производительности до и после. Вот ссылка, как проверять перформанс React-приложения.


11. ### TypeScript
    Переписать все на TypeScript. этот пункт можно отложить на потом, поскольку пока еще многие проекты не используют этот язык.
