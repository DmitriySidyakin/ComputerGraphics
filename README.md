# Компьютерная графика

Приложения на C# для объяснения компьютерной графики

## Решение на C# для Кривых Безье

Приложение генерирует кадры для анимации в текущем каталоге исполняемого файла. Приложение написано на C# WPF.
Размер кадра: 400 на 200 точек. Не учитывается уровень дискретизации t, далее в статье написано как рассчитать шаг для Кривых Безье старше 1-го порядка на примере кривых 1-го порядка. 

Подкаталог: https://github.com/DmitriySidyakin/ComputerGraphics/tree/master/Bezier/BezierSolution

Русскоязычное Описание алгоритма: [Мой Блог: Кривые Безье](https://designermanuals.blogspot.com/2019/12/KryvyeBezier.html)
![4 points Bezier Curve](https://octodex.github.com/images/yaktocat.png)
![4 points De Casteljau's Bezier Curve](https://octodex.github.com/images/yaktocat.png)
![5 points Bezier Curve](https://octodex.github.com/images/yaktocat.png)
![5 points De Casteljau's Bezier Curve](https://octodex.github.com/images/yaktocat.png)

## Решение на C# для начала Движка для трёхмерной визуализации функциональных повержностей

Приложение использует Движок для рендеринга функциональных объектов. Всё построение основано на хранении цветов в 3-х мерном массиве, который представляет собой мир. Главное правильно направить камеру.

Подкаталог: https://github.com/DmitriySidyakin/ComputerGraphics/tree/master/3DSamles/

Русскоязычное Описание алгоритма: [Мой Блог: 3D графика](https://designermanuals.blogspot.com/2021/01/3D.html)

### Проект рендерит следующие картинки:
![Cube](https://octodex.github.com/images/yaktocat.png)
![Bezier Surface](https://octodex.github.com/images/yaktocat.png)
