# kolesa-upgrade-homework-7
Дедлайн: 14.10.22 пятница 23:59  
Домашнее задание по Go

### Калькулятор на Go

Реализация калькулятора c возможностью понимать приоритеты операций и вложенные скобки был сделан на основе алгоритма
[shunting-yard_algorithm](https://en.wikipedia.org/wiki/Shunting-yard_algorithm). Более понятную и подробную реализацию
алгоритма можно найти по этой [ссылке](https://brilliant.org/wiki/shunting-yard-algorithm/).

## Доступные операторы
- `+`-> Сумма 
- `-`-> Разница
- `*` -> Умножение
- `/` -> Деление
- `^` -> Степень
- `(` -> Открыть скобки
- `)` -> Закрыть скобки

### Запустить калькулятор

Для запуска зайдите в корневой папку и запустите через терминал команду

```
go run ./cmd/.
```
