
Налаштування містяться в файлі config.json.
Налаштування описані.

Виконує знімок екрану та свайп. 
Порівнює зображення, пропонує видалити схожі (два останні). Закінчує виконання.
Для підтвердження видалення ввести 'y' (за замовченням, тому просто можна  натистути 'enter').
Для відміни видалення останнього зобоаження ввести 'n'. Регістр не важливий.
При видаленні останнього скріншоту виконує імітацію натиску кнопки "back <" (відключається в налаштуваннях).

Параметри свайпу (перша та друга точка, швидкість) задаються в налашуваннях.
Також задаються назви файлів, папок та ін...

1. Встановити Python не нижче 3.6.
Для перевірки коректності встановлення Python виконати: python -V (регістр має значення).
2. Для встановлення необхідних пакетів Python выконати: pip install -r req.txt
3. Для виконання программи: python scrshot.py (попередньо запустивши adb...)
Для компіляції
