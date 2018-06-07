# Бесплатное онлайн‑обучение со стажировкой в Mail.Ru Group
Это не шутка — мы запустили полностью бесплатную программу обучения программированию.

## [Программист Ruby](https://geekbrains.ru/free-ruby)
Ruby — это динамический, интерпретируемый, высокоуровневый язык программирования, который применяется для создания сайтов, корпоративных приложений, программного обеспечения. Он входит в десятку популярнейших ЯП по версии TIOBE.

### Задание
* Решения заданий должный находиться в файлах task1.rb, task2.rb, task3.rb
* Пример запуска: `ruby task.rb arg1 arg2 arg3 .. argN`
* Используйте массив `ARGV` для доступа к аргументам
* Используйте метод `puts` для вывода данных

## [Frontend-программист](https://geekbrains.ru/free-frontend)
Frontend-разработчик создаёт интерфейсы, верстает сайты по современным стандартам. Это востребованная и высокооплачиваемая профессия, которая включает технические и творческие компоненты.

### Задание
* Решения заданий должный находиться в файлах task1.js, task2.js, task3.js
* Пример запуска: `node task.js arg1 arg2 arg3 .. argN`
* Используйте массив `process.argv` для доступа к аргументам
* Используйте метод `process.stdout.write()` для вывода данных

## Важно
* Все задания будут прогоняться через набор автоматизированных тестов, убедитесь, что ваша программа запускается. 
* В репозитории не должно быть лишних файлов. Одно задание - один файл с решением.
* Рекомендуем ответвиться от текущего репозитория (операция fork). 


## FAQ
 * Прежде чем отправлять задание, обязательно проверьте программу у себя на локальном компьютере. Для этого необходимо установить Node, либо Ruby;
 * Задания по Frontend нужно выполнять на языке программирования JavaScript, а задания по Ruby на языке программировани Ruby;
 * Результат работы вашей программы должен печататься в консоль (js: `process.stdout.write(), console.log();` `ruby: puts`). Наличие лишних символов негативно влияет на результаты проверки.
 * Правильно округляйте и выводите числа. Если в задании указано, что округление должно быть до двух знаков после запятой, то число должно иметь вид: X.YZ;
 * В заданиях с использованием NodeJS нет браузерных методов alert, prompt, document.write и т.д.;
 * Задания автоматически проверяются на наборе тесткейсов, чем больше тесткейсов пройдет успешно, тем больше баллов вы получите;
 * Входящие аргменты можно не проверять, если это явно не сказано в задании;
 * Доступ к входящим параметрам можно получить через
   `JS:    proccess.argv[] - первый аргумент программы доступен по индексу 2 `.  
   `Ruby:  ARGV[] - первый аргумент программы доступен по индексу 0`.  
 * Ни при каких условиях в программе не должно быть бесконечных циклов. Такие решения получают 0 баллов;
 * Запрещается подключать сторонние библиотеки.
