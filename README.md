### Лабораторная работа №2. Основы верстки
## Выполнил: Матвеев Д.Н. ИСП-211о

## 1. Функции приложения
Приложение состоит из 4 экранов:
"Меню" (MainActivity) и "Экран 2" (MainActivity2).
<p align="center">
    <img src="https://github.com/user-attachments/assets/543663ea-35a6-4d62-b0e3-fd451405b946" width="250"> 
    <img src="https://github.com/user-attachments/assets/237fd788-91a0-41eb-8395-30a540c864fe" width="250">
</p>

"Экран 3" (MainActivity3) и "Экран 4" (MainActivity4).
<p align="center">
    <img src="https://github.com/user-attachments/assets/792989c6-692f-410e-a3fa-b45cf8b69a5f" width="250"> 
    <img src="https://github.com/user-attachments/assets/5c68a006-43a4-42dc-bb82-d41cc350b5b9" width="250">
</p>

## 2. Меню
Меню состоит из 4х кнопок:
- "Перейти к экрану 2" (при нажатии открывается MainActivity2).
- "Перейти к экрану 3" (при нажатии открывается MainActivity3).
- "Перейти к экрану 4"(при нажатии открывается MainActivity4).
- "Выйти" (при нажатии происходит выход из приложения).

## 3. 2-й экран
Второй экран сверстан с использованием `LinearLayout`.
Он состоит из 7 кнопок:
- 3 расположены в верхней части экрана
  `android:layout_gravity="top"`
- 2 расположены по центру
  `android:layout_gravity="center"`
- 3 расположены в нижней части экрана
  `android:layout_gravity="bottom"`

## 4. 3-й экран
Третий экран сверстан с использованием `RelativeLayout`.
Он состоит из 6 кнопок:
- 2 расположены в верхней части экрана и занимают по половине экрана
  `android:layout_toLeftOf = "@+id/view"`
- `android:layout_toRightOf="@+id/view"`
- 3 расположены по центру
  `android:layout_centerInParent="true"`
  `android:layout_toLeftOf="@+id/button15"`
  `android:layout_toRightOf="@+id/button15"`
- 1 расположена в нижней части экрана

## 4-й экран
На четвертом экране расположена 1 темно-зеленая кнопка, на кодорой изображена иконка приложения. Так как я родился в апреле, то толщина обводки `4px`. При нажатии на кнопку ее цвет должен изменяться на светло-зеленый.

Внутри папки `drawable` был создан файл `my_button` для того, чтобы кнопка приобрела данные функции.

## Инструкция использования
1. Клонируйте репозиторий на свой компьютер:
2. Откройте проект в Android Studio.
3. Подключите устройство или запустите эмулятор.
4. Нажмите кнопку **Run** в Android Studio для сборки и запуска приложения.
