# Evan Miller Sample Size Validation

![Cover Image](Cover.png)

## Опис проекту

Цей проект призначений для перевірки та підтвердження точності онлайн калькулятора Евана Міллера у розрахунку необхідного розміру вибірок для контрольної та тестової груп при проведенні А/Б тестувань.

### Мета

Метою проекту є аналіз та оцінка ефективності калькулятора Евана Міллера за допомогою методу Монте-Карло. Проект також включає порівняння результатів з розрахунками, виконаними за допомогою бібліотеки `statsmodels` (метод `NormalIndPower`), щоб виявити будь-які можливі недоліки або неточності.

### Методологія

1. **Збір даних**: Використання біноміальних розподілів для генерації даних, які відповідають визначеним параметрам (поточна конверсія, мінімально виявний ефект (MDE), рівень значущості (alpha), бажана потужність тесту).
2. **Розрахунок розміру вибірок**: Використання онлайн калькулятора Евана Міллера та методу `NormalIndPower` для визначення необхідного розміру вибірок.
3. **Моделювання та аналіз**: Проведення численних симуляцій методом Монте-Карло для оцінки статистичної потужності та ймовірності помилки першого роду.
4. **Порівняння результатів**: Аналіз отриманих результатів для виявлення можливих розбіжностей та оцінка точності обох методів розрахунку.

### Висновки

Проект надає детальний аналіз точності розрахунків розміру вибірок, виконаних за допомогою онлайн калькулятора Евана Міллера, та демонструє надійність використання методу `NormalIndPower` з бібліотеки `statsmodels`. Результати цього проекту можуть бути корисними для розробників та аналітиків, які планують та проводять А/Б тести, забезпечуючи їм інструмент для більш точного та надійного планування їх досліджень.


