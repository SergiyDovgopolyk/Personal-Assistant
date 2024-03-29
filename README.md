# Встановлення додатку

1. В терміналі введіть `pip install -i https://test.pypi.org/simple/ BotDan==0.0.1`
2. Запускайте за командою `botya`

# Adress book

Це проста система керування записами у власній адресній книзі. Адресна книга складається із системи керування нотатками. Нижче наведенні команди і їх функціональність:

### Команди:

- **`hello`**: Відображає вітальне повідомлення.
- **`good bye`**, **`close`**, **`exit`**: Закриває програму та прощається.
- **`sorted path`**: Дозволяє вибрати та відсортувати теку.
- **`add`**: Додає новий контакт.
- **`find contact`**: Шукає контакт в адресній книзі.
- **`check birthday`**: Перевіряє дні народження контактів(шукає у кого скоро день народження).
- **`search`**: Здійснює пошук контакту в адресній книзі.
- **`delete`**: Видаляє контакт.
- **`add phone`**: Додає номер телефону до контакту.
- **`add address`**: Додає адресу до контакту.
- **`remove address`**: Видаляє адресу з контакту.
- **`edit address`**: Редагує існуючу адресу контакту.
- **`remove phone`**: Видаляє номер телефону з контакту
- **`edit phone`**: Редагує існуючий номер телефону контакту.
- **`find phone`**: Шукає номер телефону контакту.
- **`add email`**: Додає email адресу до контакту.
- **`edit email`**: Редагує існуючу email адресу контакту.
- **`remove email`**: Видаляє існуючу email адресу контакту.

# Notes Management System

Це проста система керування нотатками в командному рядку. Вона дозволяє створювати, редагувати, шукати та організовувати ваші нотатки. Нижче наведено доступні команди та їх функціональність:

### Команди:

- **`hello`**: Відображає вітальне повідомлення.
- **`good bye`**, **`close`**, **`exit`**: Закриває програму та прощається.
- **`note <title> text_note`**: Додає нову нотатку до системи.
- **`show note`**: Відображає всі наявні нотатки.
- **`search note [keyword]`**: Шукає нотатки, які містять задане ключове слово.
- **`edit [note TITLE] [new note text]`**: Редагує існуючу нотатку новим текстом.
- **`update [note ID] [additional text]`**: Додає новий текст до існуючої нотатки.
- **`sort`**: Сортує нотатки за часом написання.
- **`add tag [note ID] [tag]`**: Додає тег до певної нотатки.
- **`with tag [tag]`**: Відображає нотатки, пов'язані з певним тегом.
- **`send [note ID]`**: Відправляє нотатку до системи для обробки.
- **`get [note ID]`**: Отримує список нотаток з системи.

### Приклад використання:

- Щоб додати нову нотатку: `note`
- Щоб відредагувати існуючу нотатку: `edit <1> Новий текст для нотатки`
- Щоб виконати пошук нотаток: `search note_keyword`
- Щоб додати тег до нотатки: `add tag 1 важливо`

## Як запустити:

1. Переконайтеся, що на вашій системі встановлено Python.
2. Склонуйте репозиторій.
3. Відкрийте термінал і перейдіть до каталогу проекту.
4. Запустіть програму за допомогою python main.py.

Не соромтеся досліджувати та використовувати ці команди для ефективного керування нотатками та адресною книгою!
