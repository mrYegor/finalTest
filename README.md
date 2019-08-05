# finalTest

1. Принять от пользователя имена людей для набора в команду. Имена принять и сохранить в массиве. Количество имён должно соответсвовать количеству должностей.
2. Создать объект team в котором будут храниться новые объекты-сотрудники с параметрами name и position, данные для этих свойств добавляем из массивов.
3. Добавить сотрудникам зарплаты (свойство salary) при помощи метода Math.random(), который будет выдавать произвольное число в промежутке между N1 и N2 исходя из принципа:
   - если в должности есть слово "junior" сумма будет от 500 до 1000;
   - если в должности есть слово "middle" сумма будет от 1500 до 2000;
   - если в должности есть слово "senior" сумма будет от 2500 до 3000;
   - для всех остальных - от 4000 до 4500;
Для определения того есть ли слово в имени должности используйте метод ```str.indexOf('часть строки для поиска')```. Например:
```
   var name = 'Junior developer';
   name.indexOf('Junior'); /*в данном случае вернет 0, если такая строка отсутсвует вернет -1. Регистр имеет значение, по этому "junior" вернет -1*/
```
4. Добавить каждому сотруднику метод tellAboutYourSelf(), который будет сообщать информацию о пользователе (например "Меня зовут John и я - Project manager. Я зарабатываю 4863$.").
5. Добавить объекту team метод showTeam(), который будет выводить информацию о всех сотрудниках в консоль в виде таблицы в формате: "John - Project manager. Зарплата - 4863$."*

Для удобства создайте по порядку все необходимые функции и в конце сделать вызов этих функций в логическом порядке. Например:
   - getNames();
   - createTeam();
   - setSalary();
   - создание цикла для установки метода tellAboutYourSelf();
   - *создание team.showTeam() = function() {...};
   - *вызов мтеода showTeam();
