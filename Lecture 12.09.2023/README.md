"# Lecture 12.09.2023"

# Что такое **JavaScript?**

#### JavaScript - динамический типизированный мультипарадигменный язык программирования, так как он поддерживает разные парадигмы (стили) программирования:

### Объектно-ориентированный стиль программирования в JavaScript позволяет создавать и использовать объекты, которые могут содержать свойства (переменные) и методы (функции), а также взаимодействовать друг с другом.

### Императивный стиль программирования в JavaScript описывает последовательность команд, которые должны быть выполнены для достижения определенного результата.

### Функциональный стиль программирования в JavaScript основан на использовании функций как основного строительного блока программы.

#### JavaScript - широко используется для создания интерактивных веб-страниц. Интерактивные веб-страницы - это веб-страницы, которые позволяют пользователям взаимодействовать с ними и влиять на их содержимое. Вместо того, чтобы быть просто статическими и пассивными, интерактивные веб-страницы предлагают пользователю возможность взаимодействовать с элементами страницы, выполнять действия и получать обратную связь. JavaScript — это язык программирования, который используют для написания frontend- и backend-частей сайтов, а также мобильных приложений.

# Для чего нужен **JavaScript?**

#### В веб-приложениях HTML отвечает за разметку страницы. Расположение контента, внешний вид интерфейса описывается с помощью CSS, а JavaScript отвечает за интерактивность функционал этого интерфейса, примеры задач которые решает JS:

### **Взаимодействие с пользователем.** Всплывающие окна с полем для ввода почты или других данных

### **Обработка данных HTML.** JS помогает заполнить необходимые поля в формах, проверять буквенные и числовые значения, а также управлять HTML-элементами на странице.

### **Анимация.** Это не только движущиеся объекты на странице и кнопки, но и карусель в галерее или плавная прокрутка страницы.

### **Математические вычисления.** С помощью JS-скриптов на сайтах реализованы калькуляторы, например подсчет суммы заказа в корзине интернет-магазина.

# Что такое ECMAScript?

### Спецификация ECMAScript - это стандартизированная спецификация скриптового языка. Стандартизированная спецификация означает, что определенный язык программирования или технология имеет официально установленные правила и нормы, которым должны следовать разработчики и реализации этого языка или технологии.

# Перечислите способы запуска JavaScript кода?

### _1.Вкладка консоль-разработчика веб-браузере_

### _2.Командная строка node js_

### _3.Создавая js файл и подключение к браузеру в последствии просмотр кода в консоле-разработчика в браузере_

# Расскажите про типы данных в JavaScript какие бывают и их значение?

## В JS существуют две типы данных - Примитивные и Объекты (PRIMITIVES and OBJECT).

### К примитывным типов данных входят эти типы:

#### 1.Number - представляют числовые значения

#### 2.String - представляют последовательность символов, заключенных в кавычки

#### 3.Booleans - представляют логические значения true (истина) или false (ложь).

#### 4.Undefined - это специальное значение, которое указывает на отсутствие значения у переменной или свойства объекта. Когда переменная объявлена, но ей не присвоено значение, она автоматически инициализируется значением undefined

#### 5.Null - указывает на явное присвоение пустого значения переменной.

#### 6.Symbol - это новый примитивный тип данных, который был добавлен в стандарт ECMAScript 6 (ES6). Он представляет собой уникальное и неизменяемое значение, которое может быть использовано в качестве идентификатора для свойств объектов. Символы полезны, когда вам нужно создать уникальные ключи для свойств объектов, чтобы избежать возможных конфликтов имен.

#### 7.BigInt - это встроенный тип данных, который представляет целые числа произвольной длины. Он позволяет работать с числами, которые выходят за пределы максимального значения, которое может быть представлено обычными числами JavaScript (Number).

### К объектным типом данных входят эти типы:

#### 1. Object literal в JavaScript - представляют коллекцию свойств и методов. Object literal это набор пар "ключ: значение", заключенных в фигурные скобки {}. Каждая пара "ключ: значение" определяет свойство объекта, где ключ - это имя свойства, а значение - это значение свойства. Например:

#### _var person = {_

#### _name: "John",_

#### _age: 30,_

#### _city: "New York"_

#### _}_

#### 2.Arrays - Массивы в JavaScript являются упорядоченными списками элементов, которые могут содержать любые типы данных.

#### 3.Functions - Функции в JavaScript являются объектами, которые могут быть вызваны для выполнения определенных действий. Они могут принимать аргументы (входные значения), выполнять определенный код и возвращать результаты.

#### 4.Many more: Date, RegExp, Map, Set, Promise

# Что выдаст такой код **"typeof(null)"**?

#### Это официально признанная ошибка в языке, она выдаст строку "object"

# Что будет если для константы не задать значение?

#### Будет ошибка: Uncaught SyntaxError: Missing initializer in const declaration

# Отличие null от unedfined?

#### null обычно задаётся переменной явно и означает, что она ничего не содержит. undefined показывает, что значение переменной «не определено». undefined обычно присваивается переменной, когда она была объявлена, но не было определено её начальное значение. Также, undefined может возвращаться и из функции — это происходит, если функции явно не возвращает ничего другого. null же обычно возвращают из функции явно, чтобы показать, что результат функции равен «ничему».

### console.log(null + null); // 0

### console.log(undefined + undefined); // NaN

# Variable name и Value type что это?

#### Имя переменной - это идентификатор, который используется для обращения к значению, хранящемуся в переменной. Например, в следующем коде "x" является именем переменной:

#### let x = 5;

#### Тип значения - это тип данных, который определяет характеристики значения, хранящегося в переменной. Например, в предыдущем примере тип значения переменной "x" будет "число" (Number), так как ей присвоено числовое значение.

# Динамичность и Интерактивность - что это?

#### Интерактивность в JavaScript означает, что пользователь может взаимодействовать с веб-страницей или приложением, и код JavaScript может реагировать на эти действия. Например, вы можете обрабатывать клики мыши, нажатия клавиш, отправку форм, перемещение указателя мыши и другие события, чтобы выполнять определенные действия или изменять состояние страницы.

#### Динамикность в JavaScript означает, что код может изменяться и выполняться во время выполнения программы. Это позволяет создавать динамические и интерактивные веб-страницы, где элементы страницы могут изменяться, обновляться или добавляться в ответ на действия пользователя или другие события. Например, вы можете изменять содержимое элементов HTML, стилизовать элементы, анимировать их и многое другое.

# Что такое const, let, var и их отличия?

#### const - объявляет переменную, значение которой не может быть изменено после присваивания. Она имеет блочную область видимости, что означает, что она доступна только внутри блока кода, в котором она объявлена.

#### let - объявляет переменную, значение которой может быть изменено. Она также имеет блочную область видимости.

#### var - такой же как и let но имеет функциональную область видимости или глобальную область видимости, в зависимости от того, где они объявлены.
