# Back end

## Префиксы коммитов 
```
Описание коммитов, пишется на русском языке, с довольно подробным описанием того, что было сделанно.
```
* **FEATURE** - Добавление новых функциональных возможностей (функциий)
* **FIX** - Исправление ошибок / багов
* **PERF** - Оптимизация кода / Повышение производительности
* **API** - Изменение структуры ответов, разделение/изменения/дополнение методов, которые уже существуют, изменения DTO
* **SECURITY** - Исправление в системеме безопасности
* **DOCS** - Изменение в докуметации (Например JavaDoc) 
* **TEST** - Добавление отсутствующих тестов, исправление существующих тестов, удаление ошибочных
* **REFACTOR** - Косметическое изменение кода (не несёт за собой изменени в логике работы)
* **DIFF** - Изменение, которое не попадает не под один из префиксов


## Префиксы названий веток
```
Названия веток пишутся на английском языке, маленькими буквами.
```
Префиксы названий веток совпадают с префиксами комитов, за исключением того, что `REFACTOR` ветки не создаются.

* `fix/короткое_описание_ошибки`
* `feature/короткое_описание_фичи`

Примеры:
* `fix/double_reg_bug`
    * `FIX: Исправлен баг с двойным вызовом метода createUser` 
    * `REFACTOR: В UserController удалены неиспользуемые методы регистрации`