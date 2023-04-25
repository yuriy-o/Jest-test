## Jest test

### Команди:

- `npm run test` &mdash; Запуск тесту

[Jest](https://jestjs.io/) - це популярна бібліотека для тестування JavaScript
коду. Вона надає ряд корисних функцій для написання, запуску та аналізу
результатів тестів.

Основні переваги, які роблять бібліотеку Jest дуже популярним інструментом для
тестування JavaScript коду, зокрема для тестування React компонентів та Node.js
додатків:

1. Легкий у використанні: Jest надає простий і легкий у використанні синтаксис
   для написання тестів.
2. Швидкість: Jest швидко виконує тести завдяки вбудованій підтримці
   паралельного виконання тестів.
3. Snapshot тестування: Jest надає можливість тестувати вивід компонентів та
   об'єктів за допомогою "snapshot" тестів, які перевіряють, що вивід не
   змінюється з часом.
4. Mocks: Jest надає засоби для створення моків (фальшивих об'єктів) для
   тестування залежностей.
5. Code coverage: Jest надає можливість вимірювати code coverage - ступінь того,
   яка частка коду була протестована.

Конструкції:

`describe`: це функція, яка групує пов'язані тести разом. Вона приймає два
параметри - рядок з описом групи тестів і функцію з викликами тестів. Наприклад:
`describe('математичні операції', () => {` ` test('додавання', () => {`
` expect(1 + 2).toBe(3);` ` });` `` ` test('множення', () => {` ` expect(2 \*
3).toBe(6);` ` });` `});`

`test` (або `it`): це функція, яка описує окремий тест. Вона приймає два
параметри - рядок з описом тесту і функцію з кодом тесту. Наприклад:
`test('додавання', () => { expect(1 + 2).toBe(3); });`

![preview](./libs-testing.jpg)
