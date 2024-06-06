---
layout: project
---

# What a Blast

Аркадная головоломка с элементами физики, схожая с играми серии Angry birds. У игрока есть пушка, из которой он стреляет по зданиям. Задача каждого уровня - уничтожить противников за отведенное количество выстрелов. Противники находятся в зданиях, которые состоят из блоков.

<iframe width="560" height="315" src="https://www.youtube.com/embed/Vd85Ph4ym3k" title="What a Blast Gameplay" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

<a href="https://raw.githubusercontent.com/pazenkin/pazenkin.github.io/main/img/what_a_blast/image0.jpg"><img src="./img/what_a_blast/image0.jpg" width="125" height="265" /></a>
<a href="https://raw.githubusercontent.com/pazenkin/pazenkin.github.io/main/img/what_a_blast/image1.jpg"><img src="./img/what_a_blast/image1.jpg" width="125" height="265" /></a>
<a href="https://raw.githubusercontent.com/pazenkin/pazenkin.github.io/main/img/what_a_blast/image2.jpg"><img src="./img/what_a_blast/image2.jpg" width="125" height="265" /></a>
<a href="https://raw.githubusercontent.com/pazenkin/pazenkin.github.io/main/img/what_a_blast/image3.jpg"><img src="./img/what_a_blast/image3.jpg" width="125" height="265" /></a>
<a href="https://raw.githubusercontent.com/pazenkin/pazenkin.github.io/main/img/what_a_blast/image4.jpg"><img src="./img/what_a_blast/image4.jpg" width="125" height="265" /></a>

---

## Интересные моменты

- Рисование траектории движения снарядов учитывает столкновения с препятствиями. Для этой механики осуществляется виртуальный запуск снарядов в невидимой копии мира, записываются координаты точек, которые пролетает снаряд, после чего траектория отображается игроку по координатам. Этот процесс производится постоянно, но мгновенно и незаметно для игрока.
- Для левел-дизайнеров были подготовлены удобные инструменты для быстрого конструирования уровней с привязкой доступных блоков друг к другу.
