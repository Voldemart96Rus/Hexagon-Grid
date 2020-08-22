# Hexagon Grid

Тестовое задание. Необходимо посчитать количество доменов в гексагональной решётке

![гексагональная решётка](image.png)

Ячейкам решётки м.б. присвоено значение 0 или 1. Если 2 ячейки, имеющие одинаковое значение, имеют общую грань, то они входят в один домен.

В решётке, изображённой на рисунке можно определить 3 различных домена, отображённых на рисунке цветами. Подразумевается, что бесцветным ячейкам присвоено значение 0.

Предложить пользователю ввод размера односвязной гексагональной области ( L,N,M<=30 - три поля ввода с валидацией, на примере L=3, M=5, N=7). После ввода размера отобразить (по отдельной кнопке) на странице пустую гексагональную решётку заданного размера с возможностью ручного ввода значений в ячейки (изменение 0\1 и наоборот щелчком мыши на ячейке).

Программа должна определять количество доменов в заданной решётке, ячейки которых имеют значение 1, (кнопка «Посчитать домены») и выделить цветом ячейки, входящие в домен. Цвета разных доменов должны отличаться. Предусмотреть поле для вывода количества доменов.

Также реализовать автоматическое заполнение решётки по отдельной кнопке «АВТО» значениями 0 или 1 с предварительным указанием вероятности использования единицы (вероятность от 0,01 до 0,99) в отдельном поле ввода с валидацией. По нажатию кнопки «АВТО» также следует рассчитывать количество доменов и раскрашивать их.

После каждого автоматического заполнения и расчета количества доменов в полученной решётке добавлять строку в таблице.

| Вероятность | Всего доменов | Неодносвязных доменов | Количество ячеек | Количество 1 ячеек |
| ----------- | ------------- | --------------------- | ---------------- | ------------------ |
| 0.4         | 3             | 1                     | 30               | 1                  |
| 0.5         | 10            | 10                    | 30               | 10                 |
| 0.6         | 10            | 10                    | 30               | 10                 |
