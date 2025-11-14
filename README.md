# Проект 10-дюймовый Rack
<meta name="takprodam-verification" content="47fb124d-de19-4518-ac2c-7444a0772bf1">
Мини‑стойки для компактных домашних серверных шкафов

Проект **10-дюймовый Rack** веду я — Леончук Евгений. В российском интернете почти нет информации о компактных 10‑дюймовых стойках, поэтому я решил собрать свою и поделиться опытом. Я вдохновился проектом с канала «Электроника в объективе» ([ссылка на видео](https://youtu.be/sfptg0vh3g8?si=5HCHOAXV1L_87TZ-)) и частично материалами сайта [Jeff Geerling — Mini Rack](https://mini-rack.jeffgeerling.com/), используя их как источник идей для собственной сборки.

На этой странице я буду оставлять полезные ссылки для сборки, модели и другие материалы, которые находил в процессе экспериментов и создания своей версии стойки. 

Цель проекта — развить стандарт 10 дюймовых етевых шкафов, собрать базу совместимых устройств и 3D моделей, показать, как построить компактную мини‑стойку для домашних лабораторий, сетевых проектов или портативных серверов.

<!-- Некоторые ссылки на этом сайте могут быть партнёрскими. Они помогают покрывать расходы на поддержку проекта, но основной фокус — образовательный и практический. -->

---

## Содержание
- [Сообщество](#сообщество)
- [Стандарт 10” Mini Rack](#стандарт-10-mini-rack)
- [Аппаратное обеспечение](#аппаратное-обеспечение)
- [10” Mini Racks](#10-mini-racks)
- [PDU (модули распределения питания)](#pdu-модули-распределения-питания)
- [UPS (источники бесперебойного питания)](#ups-источники-бесперебойного-питания)
- [Панели патч‑кабелей](#панели-патч-кабелей)
- [Сетевое оборудование](#сетевое-оборудование)
- [Прочее оборудование](#прочее-оборудование)
- [Полки для мини‑ПК/серверов](#полки-для-мини-пксерверов)
- [Полки для SBC](#полки-для-sbc)
- [Полки для дисков](#полки-для-дисков)
- [Полки и заглушки (blanking panels)](#полки-и-заглушки-blanking-panels)
- [Кабельное управление](#кабельное-управление)
- [Демонстрации сборок](#демонстрации-сборок)
- [Программное обеспечение](#программное-обеспечение)
- [Лицензия](#лицензия)

---

## Стандарт 10” Mini Rack

Не существует официального стандарта для мини‑стойки, который бы был принят во всём мире. Тем не менее, большинство производителей придерживаются следующих параметров:

- Высота 1U — как у обычной 19‑дюймовой стойки (44,45 мм или 1,75”).
- Ширина 10 дюймов (≈236 мм) между монтажными отверстиями.
- Полезная горизонтальная ширина — около 210 мм (8,45”), с учётом монтажных винтов и боковых зазоров.
- Отверстия для винтов — квадратные поз закладные гайки или обычные винты М6 реже М5, с вертикальным шагом как у стандартной стойки.

Таким образом, мини‑стойка совместима с большинством компактного оборудования и панелей, предназначенных для 10” rack.

[![Сборка MINI RACK](Картинки/Чертеж%2010-дюймового%20rack.png "Сборка MINI RACK")](Картинки/Чертеж%2010-дюймового%20rack.webp)


---

## Сообщество

Проект **10-дюймовый Rack** ориентирован на обмен опытом и знаниями:

- Обсуждать сборки, делиться идеями и получать советы можно через **[Issues проекта на GitHub](https://github.com/shaurum/rack/issues)**.


---

##  Моя сборка
Лично я собираю стойку по запчастям на Ozon. Основу сделал из конструкционного алюминиевого профиля — сверху и снизу. Спереди установил стандартные рэковые направляющие, а заднюю стенку сделал из тонированного оргстекла.
По-хорошему, направляющие нужно ставить и сзади, но мне стало жалко денег, поэтому ограничился оргстеклом — оно тоже отлично держит форму.

Ниже — список всех комплектующих, которые я использовал:
|Название|Количество|Комментарий|
|-|-|-|
|[Рэковые направляющие 10U, Rack 30*21*445 мм](https://ozon.ru/t/tkA4fWS)|1|По хорошему 2 шт.|
|[Профиль конструкционный 20х20 (Ан. черный) / 300 мм ](https://www.ozon.ru/product/profil-konstruktsionnyy-20h20-an-chernyy-300-mm-2-sht-soberizavod-2128569113/)|2|Пилил пополам, если найдете сразу 150мм - берите|
|[Профиль конструкционный 20х20 (Ан. черный) / 250 мм](https://ozon.ru/t/A0LczQG)|4||
|[Гайка закладная М6 без контакта 2092200 Rittal](https://ozon.ru/t/quGDjHa)|32||
|[Винт DIN 7985 М6х12 с полукруглой головкой](https://ozon.ru/t/M4Eq70e)|32||
|[Оргстекло тонированное 50x70см, толщина 3 мм](https://ozon.ru/t/9wJlZ7T)|1||
|[Винт с потайной головкой M5х8 внутр.шестигр. нержавейка, ISO 10642](https://ozon.ru/t/sY4BL3J)|24||
|[Т-гайки М5 для профиля 2020 с пазом 6 мм](https://ozon.ru/t/WN8iVds)|24||


## 10-дюймовое оборудование

###  Готовые сетевые шкафы

|Название|Размер|Комментарий|
|-|-|-|
|[Cabeus WSC-8U](https://cabeus.ru/product/7877/)|8U||
|[Cabeus WSC-4U](https://cabeus.ru/product/7876/)|4U||
|[ЦМО ШРН-8.255-10](https://www.cmo.ru/catalog/cmo/nastennye_telekommunikatsionnye_shkafy/nastennye_shkafy_shrn_10/shkaf_telekommunikatsionnyy_nastennyy_10_8u_320_255/)|8U||
|[ЦМО ШРН-12.255-10](https://www.cmo.ru/catalog/cmo/nastennye_telekommunikatsionnye_shkafy/nastennye_shkafy_shrn_10/shkaf_telekommunikatsionnyy_nastennyy_10_12u_320_255/)|12U||

###  Коммутаторы, маргрутизаторы

|Название|Комментарий|
|-|-|
|[MikroTik CRS112-8P-4S-IN](https://ozon.ru/t/NIDNPZu)||
|[MikroTik CRS310-1G-5S-4S+IN](https://ozon.ru/t/M4EMNuW)||
|[MikroTik CRS310-8G+2S+IN](https://ozon.ru/t/zq1zFIF)||
|[MikroTik CSS318-16G-2S+IN](https://ozon.ru/t/ifHiUz5)||
|[MikroTik CSS610-8G-2S+IN](https://ozon.ru/t/jhVjHkJ)||
|[MikroTik L009UiGS-RM](https://ozon.ru/t/tkAta1h)||
|[MikroTik RB5009UG+S+IN](https://ozon.ru/t/IFyIrIK)||
|[MikroTik RB5009UPr+S+IN](https://ozon.ru/t/GvzG6kz)||

###   Прочее
|Название|Комментарий|
|-|-|
|[Патч-панель Cabeus PL-12-Cat.5e 10"-Dual IDC](https://cabeus.ru/product/7451/)||
|[Патч-панель Cabeus PL-12-Cat.6 10"-SH-Dual IDC](https://cabeus.ru/product/7841/)||
|[Полка Cabeus WSC-J018-10](https://cabeus.ru/product/7271/)||
|[Полка ЦМО МС-15-10](https://www.cmo.ru/catalog/cmo/aksessuary_k_telekommunikatsionnym_shkafam_i_stoykam/aksessuary_dlya_shrn_10/polka_10/)||
|[Бокс оптический ST 10". БОН-М-10](https://www.cmo.ru/catalog/cmo/aksessuary_k_telekommunikatsionnym_shkafam_i_stoykam/aksessuary_dlya_shrn_10/boks_opticheskiy_st_10/)||
|[Кабельный органайзер ГКО-1U-10](https://www.cmo.ru/catalog/cmo/aksessuary_k_telekommunikatsionnym_shkafam_i_stoykam/aksessuary_dlya_shrn_10/gorizontalnyy_kabelnyy_organayzer_10/)||
|[Фальшпанель ФП-5-10](https://www.cmo.ru/catalog/cmo/aksessuary_k_telekommunikatsionnym_shkafam_i_stoykam/aksessuary_dlya_shrn_10/falshpanel_10/)||
|[Блок силовых розеток БР-3П-10-9005](https://www.cmo.ru/catalog/cmo/aksessuary_k_telekommunikatsionnym_shkafam_i_stoykam/aksessuary_dlya_shrn_10/blok_silovykh_rozetok_10_bez_shnura_s_vyklyuchatelem_3_rozetki/)||
|[Патч-панель для 8 модулей RJ-45, keystone ПТ-8-10](cmo.ru/catalog/cmo/aksessuary_k_telekommunikatsionnym_shkafam_i_stoykam/aksessuary_dlya_shrn_10/patch_panel_10_dlya_8_moduley_rj_45_keystone/)||



---

## Полезные ссылки

[Электроника в объективе](https://youtu.be/sfptg0vh3g8?si=5HCHOAXV1L_87TZ-).  
[Jeff Geerling — Mini Rack](https://mini-rack.jeffgeerling.com/)

---

## Лицензия

Материалы сайта открыты для образовательного и личного использования. Коммерческое использование без согласия автора запрещено.