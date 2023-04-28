# CL_project

Суммаризация текстов бытового характера на татарском языке. 
Берутся статьи со страницы газеты "Ватаным Татарстан" (https://vatantat.ru/category/bezne%d2%a3-proektlar/). Статьи не суммаризируются, если представляют собой кулинарные рецепты (добавляются в датафрейм в исходном виде) или интервью (игнорируются). Рецепты и интервью определяются при помощи регулярных выражений. Остальные статьи проходят через простейший алгоритм суммаризации (выбор самых значимых предложений, содержащих наибольшее количество ключевых, то есть самых частотных слов). Результатом проекта (в идеале) должен быть телеграм-канал, являющийся Интернет-версией печатного "Семейного календаря" на татарском языке: каждый день печатается текущая дата и житейский совет (суммаризированный текст или рецепт).

art.csv - файл с суммаризированными статьями и не суммаризированными рецептами (столбик "суммаризация")

Ссылка на Телеграм-канал (в данное время не функционирует): https://t.me/+SDwk-6-blzZjZjZi
