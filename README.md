# testing-lab-spo

Лабораторные работы по дисциплине «Тестирование информационных систем».

## Лабораторная работа № 4. Работа с баг-трекером (GitHub Issues)

Тестируемое приложение: [DemoQA — Automation Practice Form](https://demoqa.com/automation-practice-form)

В ходе работы созданы три дефекта с разными приоритетами и метками:

| № | Дефект | Приоритет | Метки | Состояние |
|---|--------|-----------|-------|-----------|
| [#1](https://github.com/GigaSlavik/testing-lab-spo/issues/1) | Форма отправляется с пустым email | High | `bug`, `high-priority` | Open |
| [#2](https://github.com/GigaSlavik/testing-lab-spo/issues/2) | Нет валидации пароля (не проверяется наличие цифры) | Medium | `bug`, `medium-priority` | Open |
| [#3](https://github.com/GigaSlavik/testing-lab-spo/issues/3) | Опечатка в надписи "Permananet Address" | Low | `typo`, `low-priority` | Open |

Каждый Issue содержит шаги воспроизведения, ожидаемый и фактический результат, окружение и скриншоты.

## Метки

- `high-priority` — высокий приоритет, блокирует основной сценарий;
- `medium-priority` — средний приоритет, есть обходной путь;
- `low-priority` — низкий приоритет, косметический дефект;
- `typo` — опечатка в тексте интерфейса.
