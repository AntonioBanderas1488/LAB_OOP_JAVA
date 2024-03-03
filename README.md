ЛАБОРАТОРНА РОБОТА №1

Мета роботи: Ознайомитись з порядком створення нового проекту та написати першу програму

Опис програми до завдання №1: Ця програма приймає 10 чисел від користувача, потім обчислює та виводить їх суму, різницю (перший мінус наступні), добуток (перше число помножене на наступні) і частку (перше число поділене на наступні). Однак, значення різниці, добутку та частки обчислюються некоректно через неправильне використання змінних.

Опис програми до завдання №2: Ця програма демонструє два варіанти реалізації складання речення з окремих слів: Варіант реалізації №1: Використовується явне оголошення окремих змінних типу String для кожного слова; Варіант реалізації №2: Використовується масив рядків для зберігання слів. Користувач вводить слова з клавіатури, які заповнюють масив. Потім слова з масиву об'єднуються в речення і виводяться на екран. Обидва варіанти демонструють способи складання речення з окремих слів, але відрізняються способом отримання слів для складання речення: статично оголошені слова проти слів, введених користувачем з клавіатури.

Опис програми до завдання №3: Ця програма створює масив користувачів та дозволяє ввести дані про кількість користувачів, їх вік, ім'я, прізвище, вагу та зріст через консоль. Після цього вона обчислює загальну суму віку, ваги та зросту всіх користувачів та виводить їх на екран. Кожен користувач представлений окремим об'єктом класу User, який має поля для інформації про id, вік, ім'я, прізвище, вагу та зріст. Конструктор класу User використовується для ініціалізації об'єктів користувачів, де дані вводяться з консолі за допомогою об'єкта Scanner. Головний клас Main створює масив об'єктів User заздалегідь визначеного розміру, заповнює його даними, обчислює суму віку, ваги та зросту користувачів, і виводить ці суми на екран.

Опис програми до завдання №4: Ця програма створює масив автомобілів та дозволяє користувачеві ввести дані про кількість автомобілів, їх марку, модель, потужність, об'єм, вагу та висоту через консоль. Після цього вона обчислює загальну суму потужностей та об'ємів всіх автомобілів та виводить їх на екран. Кожен автомобіль представлений окремим об'єктом класу Car, який має поля для інформації про id, марку, модель, потужність, об'єм, вагу та висоту. Конструктор класу Car використовується для ініціалізації об'єктів автомобілів, де дані вводяться з консолі за допомогою об'єкта Scanner. Головний клас Main створює масив об'єктів Car заздалегідь визначеного розміру, заповнює його даними, обчислює суму потужностей та об'ємів автомобілів, і виводить ці суми на екран.

Опис програми до завдання №5: Данапрограма приймає число від користувача та реверсує його, виводячи результат на екран. Вона використовує простий цикл while, щоб обернути число, записуючи цифри у зворотньому порядку.

Висновок: На лабораторній роботі №1, я ознайомився з порядком створення нового проекту та написати першу програму

ЛАБОРАТОРНА РОБОТА №2

Мета роботи: Отримати навики побудови алгоритмів розгалуженої структури за допомогою умовного оператора if та оператора вибору switch.

Опис програми до завдання №1: Ця програма призначена для знаходження розв'язків квадратного рівняння за допомогою введених користувачем коефіцієнтів. Вона перевіряє, чи коефіцієнт 'a' дорівнює нулю. Якщо 'a' не дорівнює нулю, програма обчислює дискримінант і знаходить розв'язки, враховуючи три можливі випадки: додатний, нульовий та від'ємний дискримінанти. Якщо 'a' дорівнює нулю, програма вирішує лінійне рівняння.

Опис програми до завдання №2: Ця програма призначена для визначення квадранта, в якому знаходиться точка на площині з координатами (x, y). Користувач вводить значення x та y з клавіатури, а програма перевіряє їхні знаки, щоб визначити квадрант.Якщо значення x та y додатні, точка знаходиться в першому квадранті. Якщо x від'ємний, а y додатній, точка знаходиться в другому квадранті, і так далі. Якщо одне з чисел x або y дорівнює нулю, точка знаходиться на відповідній піввісі координатної площини. Якщо обидва числа x та y дорівнюють нулю, точка знаходиться у початку координат. Програма виводить результат на екран у вигляді повідомлення про квадрант, в якому знаходиться точка.

Опис програми до завдання №3: Ця програма призначена для перевірки, чи введене користувачем число є двозначним і парним. Спочатку програма зчитує число з консолі. Потім вона перевіряє, чи введене число знаходиться у діапазоні від 10 до 99, що робить його двозначним. Якщо це так, програма перевіряє, чи число парне, шляхом перевірки залишку від ділення на 2. Якщо залишок від ділення на 2 дорівнює 0, то число є парним, і програма виводить відповідне повідомлення. В іншому випадку, якщо число є двозначним, але не парним, програма також виводить відповідне повідомлення. Якщо число не є двозначним, програма повідомляє про це.

Опис програми до завдання №4: Ця програма призначена для обчислення значення функції в залежності від введеного числа x. Вона використовує умовні конструкції для визначення, яка формула потрібна для обчислення результату відповідно до значення x. Якщо x менше за 0, обчислюється (exp(x) + exp(-x)) / 2. У випадку, коли x знаходиться в межах від 0 до 1 включно, обчислюється pow(cos(x), 2) + 2 * pow(sin(x + 1), 1/3). У всіх інших випадках, коли x більше за 1, обчислюється sqrt(abs(cos(pow((x - 1), 3)))). Після обчислення значення функції воно виводиться на екран.

Опис програми до завдання №5: Ця програма надає користувачеві меню з семи опцій. Користувач обирає одну з опцій, введену з клавіатури, і викликається відповідна функція. Опції включають перевірку, чи є день робочим, визначення пори року за номером місяця, виведення кількості днів у місяці, виведення різноманітних повідомлень, виведення назви предмету за номером пари, визначення, в яку чверть години потрапляє число хвилин, та виконання арифметичних операцій над двома числами. Кожна функція виконує відповідну дію згідно з вибором користувача.

Висновок: На лабораторній роботі №2 я отримав наавики побудови алгоритмів розгалуженої структури за допомогою умовного оператора if та оператора вибору switch.

ЛАБОРАТОРНА РОБОТА №3

Мета роботи: Отримати навики побудови алгоритмів циклічної структури за допомогою оператора while та for.

Опис програми до завдання №1:Програма приймає введену користувачем фразу і виводить її на екран 50 разів, використовуючи два типи циклів: for та while.

Опис програми до завдання №2: Програма виводить на консоль всі можливі комбінації годин (від 0 до 2) і хвилин (від 0 до 59). Вона використовує вкладені цикли for, щоб ітеруватися через години та хвилини і виводити кожну комбінацію у форматі "години хвилини".

Опис програми до завдання №3: Програма використовує вкладений цикл while, щоб вивести на консоль всі можливі комбінації годин (від 0 до 2) і хвилин (від 0 до 59). Зовнішній цикл контролює години, вкладений цикл - хвилини. Кожна комбінація виводиться у форматі "години хвилини".

Опис програми до завдання №4: Програма використовує вкладені цикли for, щоб вивести на консоль всі можливі комбінації годин (від 0 до 2), хвилин (від 0 до 59) і секунд (від 0 до 59). Зовнішній цикл контролює години, середній цикл - хвилини, а найвнутрішній - секунди. Кожна комбінація виводиться у форматі "години хвилини секунди".

Опис програми до завдання №5: Програма обчислює значення заданої функції для заданого інтервалу значень x, кроку та виводить результати за допомогою циклів for та while. Після цього вона підраховує кількість значень функції, які потрапляють у заданий діапазон, і виводить цю кількість.

Висновок: На лабораторній роботі №3 я отримав навики побудови алгоритмів циклічної структури за допомогою оператора while та for.

ЛАБОРАТОРНА РОБОТА №4

Мета роботи: Отримати навики роботи з масивами даних.

Опис програми до завдання №1: Програма створює два масиви: один для парних чисел та інший для непарних чисел, кожен масив містить 50 елементів. Потім вона заповнює ці масиви відповідно до їхнього типу чисел (парні чи непарні). Нарешті, виводить ці масиви на екран. 

Опис програми до завдання №2: Ця програма демонструє різні способи перебору та виведення елементів масиву чисел. Вона використовує цикли while та for для виведення елементів масиву у звичайному порядку, та на парних або непарних індексах. Також вона виводить масив у зворотньому порядку. Основні кроки програми: Задається масив чисел. Використовуються цикли while та for для перебору масиву та виведення його елементів на екран. Використовуються цикли while та for для виведення елементів масиву на парних або непарних індексах. Використовується цикл for для виведення масиву в зворотньому порядку.

Опис програми до завдання №3: Ця програма дозволяє користувачеві ввести кількість елементів масиву, а потім самостійно ввести значення кожного елементу. Після цього програма обчислює суму всіх елементів масиву та виводить її на екран.

Опис програми до завдання №4: Даний код створює масив цілих чисел та змінює знак непарних елементів на протилежний. Після цього він виводить отриманий масив на екран.

Висновок: На лабораторній роботі №4, я отримав навики роботи з масивами даних.

ЛАБОРАТОРНА РОБОТА №5

Мета роботи : Отримати навики побудови методів та роботи з ними на мові Java.

Опис програми: Ця програма є консольним додатком для виконання різних операцій:
Обчислення площі різних геометричних фігур (квадрат, прямокутник, паралелограм, ромб, прямокутний трикутник, трапеція, коло).Знаходження найменшого числа серед трьох введених користувачем чисел.Виведення заданого масиву чисел.Знаходження найбільшого числа в заданому масиві чисел.Користувач може вибирати потрібну операцію з меню, введенням відповідного номера. Програма виконує обрану операцію та повертає результат користувачу.Додаток надає зручний інтерфейс для користувача, де він може вибрати операцію з обчислення площі геометричних фігур або виконати операції з числами. Користувач може повторювати вибір операції без обмежень, поки не обере опцію виходу з програми.Кожна операція має свій власний набір вхідних даних, що вводяться користувачем. Після введення даних програма обробляє їх, виконуючи необхідні обчислення або дії, і виводить результат користувачу.Така програма може бути корисною для швидкого обчислення площі геометричних фігур або для знаходження мінімального або максимального числа серед заданого набору.
 
