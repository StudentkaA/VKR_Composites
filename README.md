# VKR_Composites

Выпускная квалификационная работа по программе повышения квалификации «Data Science» в обучающем центре МГТУ им. Н. Э. Баумана 2023г.

На входе имеются данные о начальных свойствах компонентов композиционных материалов (количество связующего, наполнителя, температурный режим отверждения и т.д.).
Необходимо было спрогнозировать ряд конечных свойств получаемых композиционных материалов, а именно: 
- модуль упругости при растяжении,
- прочность при растяжении,
- соотношение матрица-наполнитель.

То есть требовалось разработать модели, прогнозирующие значения данных свойств в зависимости от остальных.
Также требовалось разработать приложение, делающее удобным использование данных моделей (в коде попытка приложения для нейросети, предсказывающей соотношение матрица-наполнитель).

Представлено два датасета в файлах X_bp.xlsx и Х_nup.xlsx:
- X_bp содержит: признаков: 10 и индекс; строк: 1023.
- X_nup содержит: признаков: 3 и индекс; строк: 1040.

! Работа новичка в IT в целом и в data sience в частности. Код приложения некорректный, надеюсь, позднее исправить.
Решить поставленные задачи не удалось, модели показывают отрицательный R2.
