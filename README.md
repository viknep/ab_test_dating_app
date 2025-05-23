# Проект: Приложение для знакомств

## Описание проекта
В этом проекте был проведен анализ данных АБ-теста для оценки нового алгоритма поиска анкет в приложении знакомств. Цель исследования — определить, улучшает ли новый алгоритм качество сервиса.

## Цели
Оценить влияние нового алгоритма на качество сервиса в приложении знакомств и предоставить рекомендации о целесообразности его внедрения для всех пользователей.

## Стек технологий
python(pandas, scipy, seaborn)


## Задачи
Определить ключевые метрики, которые отвечают за качество сервиса (например, количество мэтчей).
Сравнить эти метрики между двумя группами пользователей (группа 0 — старый алгоритм, группа 1 — новый алгоритм).
Провести статистический анализ для определения значимости различий между группами.
Сделать аналитическое заключение о влиянии нового алгоритма на качество сервиса.

## Выводы
Поскольку p-value значительно меньше обычного уровня значимости (0.05), мы отвергаем нулевую гипотезу. Это означает, что существует статистически значимое различие в конверсии между группами.

Вывод: Новый алгоритм поиска анкет значительно улучшил качество сервиса, увеличив процент мэтчей. Поэтому стоит рассмотреть возможность внедрения новой системы поиска анкет для всех пользователей приложения.
