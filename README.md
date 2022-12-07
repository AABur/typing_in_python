# Школа сильных программистов. Курс "Типизация в Python"

Полезные ресурсы в отношении типизации в Python из круса "Типизация в Python" Школы
сильных программистов. Упомянутые в крусе, а так же найденные в процессе изучения.

## Полезные материалы из первой недели курса
* [PEP 484 – Type Hints](https://peps.python.org/pep-0484/) - основополагающее описание синтаксиса и способов использования аннотации типов.
* [typing-extensions](https://pypi.org/project/typing-extensions/) - бэкпорты typing объектов для старых версий Python. 
* [stubtest](https://mypy.readthedocs.io/en/stable/stubtest.html) - тестирование аннотаций типов.
* [stubgen](https://mypy.readthedocs.io/en/stable/stubgen.html) - автоматическая генерация аннотаций типов.
* [flake8-pyi](https://pypi.org/project/flake8-pyi/) - линтер для .pyi файлов.
* [PEP 561 – Distributing and Packaging Type Information](https://peps.python.org/pep-0561/) - документация для stub пакетов.
* [Стиль кодирования stub-файлов](https://github.com/python/typeshed/blob/master/CONTRIBUTING.md#stub-file-coding-style).

## Полезные материалы из второй недели курса
* [The Mypy Blog. Extending mypy with plugins](http://mypy-lang.blogspot.com/2019/03/extending-mypy-with-plugins.html) - блог с новостью про добавление плагинов в mypy.
* [API плагинов для mypy.](https://mypy.readthedocs.io/en/stable/extending_mypy.html)
* [Тестирование плагинов для mypy.](https://sobolevn.me/2019/08/testing-mypy-types)
* [pydantic mypy plugin.](https://pydantic-docs.helpmanual.io/mypy_plugin/)

### Проверка аннотаций типов
* [mypy](https://github.com/python/mypy) - Дополнительная статическая типизация в Python
* [beartype](https://github.com/beartype/beartype) - Невероятно быстрая O(1) проверка типов во время исполнения скриптов на чистом Python.
* [deal](https://github.com/life4/deal) - Мощная библиотека для написания и тестирования контрактов ([Design by contract](https://en.wikipedia.org/wiki/Design_by_contract)). Считайте, что это типизация на стероидах.
* [pyanalyze](https://github.com/quora/pyanalyze) - Расширяемый статический анализатор и средство проверки типов.
* [pyre](https://pyre-check.org/) - Производительная проверка типов для Python 3.
* [pytype](https://github.com/google/pytype) - Инструмент для проверки и вывода типов - не требуя аннотаций типов.
* [pyright](https://github.com/Microsoft/pyright) - Быстрая программа проверки типов, предназначенная для больших баз исходных текстов Python. Он может работать в " следящем" режиме и выполняет быстрое инкрементное обновление при изменении файлов.
* [pycharm](https://www.jetbrains.com/pycharm/) - Python IDE для профессиональных разработчиков с собственной реализацией проверки типов.

## Полезные материалы из третьей недели курса
* [Типы полиморфизма.](https://medium.com/devschacht/polymorphism-207d9f9cd78)
* [Тайпклассы в Python.](https://sobolevn.me/2021/06/typeclasses-in-python)
* [Обеспечение принципа единой ответственности в Python](https://sobolevn.me/2019/03/enforcing-srp) - про callable классы с DI.
* [Каким мог бы быть асинк?](https://sobolevn.me/2020/06/how-async-should-have-been)
* [Типы высшего порядка в Python.](https://sobolevn.me/2020/10/higher-kinded-types-in-python)
* [phantom-types](https://github.com/antonagestam/phantom-types) - библиотека, позволяющая произвольно сужать встроенные типы без каких-либо затрат во время выполнения.
* [Parse, don’t validate.](https://lexi-lambda.github.io/blog/2019/11/05/parse-don-t-validate/)

## Другие пололезные материалы
* [Awesome Python Typing](https://github.com/typeddjango/awesome-python-typing) - большая коллекции ресурсов по типизации в Python.
* [Variance of generic types in Python](https://rednafi.github.io/reflections/variance-of-generic-types-in-python.html) - статься о разновидностях общих (generic) типов в Python ([PEP 483 – The Theory of Type Hints - Generic Types](https://peps.python.org/pep-0483/#generic-types)).
* [Covariance, Contravariance, and Invariance — The Ultimate Python Guide](https://blog.daftcode.pl/covariance-contravariance-and-invariance-the-ultimate-python-guide-8fabc0c24278) - статья о вариативности типов в Python.
* [Parse, Don’t Validate | Python Patterns](https://towardsdatascience.com/parse-dont-validate-f559372cca45)
* [Python Type Checking | TestDriven.io](https://testdriven.io/blog/python-type-checking/)

## Материалы не по теме курса
* [Category Theory for Programmers.](https://github.com/hmemcpy/milewski-ctfp-pdf)
* [glom](https://github.com/mahmoud/glom) - штука для манипуляции словариками в декларативном стиле.
