 
# __Персональний помічник__
### **Система для зберігання та взаємодії з записами адресної книги та нотатками з можливістю додавання тегів**

## Основне завдання:
1. Зберігати контакти з іменами, адресами, номерами телефонів, email та днями народження до книги контактів;
2. Виводити список контактів, у яких день народження через задану кількість днів від поточної дати;
3. Перевіряти правильність введеного номера телефону та email під час створення або редагування запису та повідомляти користувача у разі некоректного введення;
4. Здійснювати пошук контактів серед контактів книги;
5. Редагувати та видаляти записи з книги контактів;
6. Зберігати нотатки з текстовою інформацією;
7. Проводити пошук за нотатками;
8. Редагувати та видаляти нотатки;

___
__Команди для контактів:__
- 0 - "help" -> Виводить всі доступні команди
- 1 - "hello" -> Привітання з користувачем
- 2 - "all" -> Виводить все що є в словнику
- 3 - "exit" -> Закрити програму без збереження даних
- 4 - "close" -> Зберегти і закрити
- 5 - "save" -> Команда зберігання словника в файл .pkl
- 6 - "open-book [link to file]" -> Команда для відкриття файлу в ручну
- 7 - "add [Name]" -> Створити користувача
- 8 - "remove-user [Name]" -> Команда видалення користувача
- 9 - "add-phone [Name] [номер телефону]" -> Зберігає новий номер телефону для контакту що вже існує в записнику
- 10 - "phone [Name]" -> Виводить номер телефону контакту
- 11 - "add-birthday [Name] [дата народження]" -> Додає до контакту день народження
- 12 - "show-birthday [Name]" -> Показує день народження контакту
-  - "birthdays" -> Повертає список користувачів, яких потрібно привітати через задану кількість днів від поточної дати
- 14 - "add-email [Name] [Email]" -> Команда додавання електронної пошти до користувача
- - "show-email [Name]" -> Показує Email
- - "add-addres [Name] [addres]" -> Команда додавання адреси до користувача
- - "show-addres [Name]" -> Показує адресу
- - "show-user" -> Покозує всіх користувачів

__Команди для тегів:__
- 0 - "add-tag [name]" -> Додає тег до користувача
- 1 - "tag-user [tag]" -> Шукає користувача за тегом

__Команди для нотатків:__
- 0 - "n [name] [coment] [notes]" -> Додавання нотаток до користувача або редагую існуючі
- 1 - "view-notes [name]" -> Виводить нотатки користувача
- 2 - "view-all-notes" -> Виводить всі нотатки всіх користувачів
- 3 - "remove-notes-all [name]" -> Видаляє всі нотати в користувача
- 4 - "remove-note [name] [comment]" -> Видаляє конкретну нотатку в користувача


    