 Общий обзор

Этот проект представляет собой простое приложение для рисования, разработанное на Python с использованием библиотеки Tkinter. Приложение позволяет пользователям рисовать, выбирать цвета, использовать ластик, очищать холст и сохранять свои работы в формате PNG.

Структура и модули проекта

1. painter.py:
   - Основной файл приложения.
   - Инициализирует главное окно, создает интерфейс пользователя и связывает события с функциями рисования и управления.

 Описание функций

1. class DrawingApp:
   - __init__: Описывает инициализацию приложения.
   - setup_ui: Объясняет создание пользовательского интерфейса с кнопками управления.
   - update_color_box_position: Указывает, что метод обновляет позицию поля цвета.
   - new_canvas: Описывает создание нового холста с пользовательскими размерами.
   - paint: Описывает процесс рисования на холсте.
   - reset: Справляется с обнулением координат последней точки.
   - clear_canvas: Описывает процесс очистки холста.
   - choose_color: Объясняет выбор цвета для рисования.
   - update_color_display: Описывает обновление отображения текущего цвета.
   - eraser: Описывает переключение режима "ластик".
   - save_image: Описывает процесс сохранения текущего изображения.
   - pick_color: Описывает выбор цвета из пикселей на холсте.
Пошаговое использование

1. Запустите `painter.py`.
2. Используйте левую кнопку мыши для рисования на холсте.
3. Поле в правом верхнем углу отображает текущий цвет кисти
3. Щелкните правой кнопкой мыши на любом месте холста, чтобы изменить цвет кисти на цвет пикселя в этом месте.
4. Используйте кнопку "Новый холст" для создания нового холста с обновленными параметрами ширины и высоты.
5. Используйте кнопку "Ластик" для стирания нарисованного.
5. Кнопка "Очистить" позволяет очистить холст.
6. Кнопка "Сохранить" открывает диалог для сохранения вашего рисунка в формате PNG.
7. Горячая клавиша CTRL+S открывает диалог для сохранения вашего рисунка в формате PNG.
8. Горячая клавиша CTRL+С Открывает диалог выбора цвета для кисти.

 Установка

Для работы приложения вам потребуется Python и библиотека Pillow. Вы можете установить Pillow с помощью следующей команды:

pip install Pillow