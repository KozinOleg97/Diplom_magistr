# Diplom_magistr

Цель - нахождение физических характеристик тела человека, по видеопотоку/изображению(возможен вариант с использованием камер с дальномером). Реализация для смартфонов на IOS.

Задачи:
    0) Разобраться в основах, набрать материал (сформировать видение проекта, аналоги, технологии для реализации распознавания, технологии для разработки под IOS) 
    1) Обосновать целесообразность
    2) Обозреть аналоги
    3) Разработать распознавание скелета
     -сначала на готовых решениях
    4) Разработать расчёт параметров тела (тут проблема с одеждой, поза....)
    5) Реализовать вариант с крутой камерой (дальномер?)

Путкт 0

Задача распознавания скелета Pose Estimation

Подходы к реализации:
    Гистограмма направленных градиентов - https://ru.wikipedia.org/wiki/Гистограмма_направленных_градиентов
    Fourier Descriptor - http://fourier.eng.hmc.edu/e161/lectures/fd/node1.html
    Scale-invariant feature transform - https://en.wikipedia.org/wiki/Scale-invariant_feature_transform



Что прочитать:
    https://habr.com/ru/company/ods/blog/322626/ - набор статей, вроде норм
    https://habr.com/ru/company/yandex/blog/208034/ - статьи от yandex (сложнее и от 2014)
    


Открытые реализации Pose Estimation:
    https://github.com/CMU-Perceptual-Computing-Lab/openpose



Свободные датасеты поз:
    Frames Labeled In Cinema (FLIC)
    Leeds Sports Pose Dataset (LSP)
    http://domedb.perception.cs.cmu.edu/index.html


Реализация с использование дальномера приводит к получению данных в 3 координатах, и превращается в Point cloud задачу, + нужны особые датасеты.

Примеры изображений для распознавания:
    https://avatars.mds.yandex.net/get-pdb/1025599/7a3fc5ec-b059-47bf-9ede-3a62252f6b96/s1200

Пункт 1




Пункт 2



Ссылки на источники:

    1)https://habr.com/ru/company/ods/blog/354850/ - подход к решению как к задаче регрессии
