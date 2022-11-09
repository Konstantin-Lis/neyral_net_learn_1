# neyral_net_learn_1
Данный проект создан в рамках обучения нейросетям. Некоторые аспекты не обобщены, в связи с чем нейросеть отсюда необходимо использовать крайне осторожно и с предварительным внесением необходимых поправок. Непосредственная задача нейросети - определение цифр с черно-белой картинки формата 28х28 пикселей

Код данного репозитория за небольшими исправлениями взят из книги Тарика Рашида "Создаём нейронную сеть".

Исправления:
1. Заместо синусоидальной функции из модуля scipy используется она же, но написанная вручную с использованием модуля math
2. Добавлены блоки сохранения нейросети в файл и загрузки нейросети из файла. Однако они лишь прописаны кодом уровня "костылей", в связи с чем для правильной работы их необходимо "закомментировать" или "снять комментарий"
