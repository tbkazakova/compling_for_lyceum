# Домашнее задание

Файл для заданий: ['Трое в лодке, не считая собаки'](https://github.com/tbkazakova/compling_for_lyceum/blob/main/data/Three_men_in_a_boat.txt).

## 1. Частотные слова (2 балла)
Напечатайте топ-20 самых частотных слов в тексте с количеством их вхождений.

Пример:
```
the  5465
of  3167
...
and  3042
to  2761
a  2052
```

## 2. Краткие содержания (2 балла)

В первом абзаце после номера каждой главы кратко перечислены основные события.

Пример:
```
CHAPTER I.
 Three invalids.—Sufferings of George and Harris.—A victim to one hundred and seven fatal maladies.—Useful prescriptions.—Cure for liver complaint in children.—We agree that we are overworked, and need rest.—A week on the rolling deep?—George suggests the River.—Montmorency lodges an objection.—Original motion carried by majority of three to one.
...
CHAPTER II.
 Plans discussed.—Pleasures of “camping-out,” on fine nights.—Ditto, wet nights.—Compromise decided on.—Montmorency, first impressions of.—Fears lest he is too good for this world, fears subsequently dismissed as groundless.—Meeting adjourns.
```
Найдите подобные краткие содержания и запишите их в словарь, в котором ключами будут номера глав, а значениями краткие содержания без знаков "-". (В тексте 19 глав.)

Пример:
```
{'I': 'Three invalids. Sufferings of George and Harris. (...) Original motion carried by majority of three to one.',
'II': 'Plans discussed. Pleasures of “camping-out,” on fine nights. Ditto, wet nights. (...) Meeting adjourns.'
...}
```
## 3. Без картинок (1 балл)
В файле отмечены места, где в книжке расположены илюстрации.

Пример:
```
[Picture: Graphic of three men in a rowing boat]
...
[Picture: Montmorency] 
```

Удалите все подобные пометки и сохраните оставшийся текст в файл `no_pictures.txt`.

Подсказка: используйте регулярные выражения.


