# Исследование объявлений о продаже квартир

В вашем распоряжении данные сервиса Яндекс.Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктов за несколько лет. Нужно научиться определять рыночную стоимость объектов недвижимости. Ваша задача — установить параметры. Это позволит построить автоматизированную систему: она отследит аномалии и мошенническую деятельность. 

По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые — получены автоматически на основе картографических данных. Например, расстояние до центра, аэропорта, ближайшего парка и водоёма. 

#### <font color='#473C8B'>Цели исследования</font>

Итак, нам предстоит найти от каких фактов в большей степени зависит цена на недвижимость. А также от чего может зависеть как быстро продаётся жильё. А именно:    
- от общей площади, в том числе от жилой площади и площади кухни;    
- от этажа, особенно если это первый или последний этаж;    
- а может быть от количества балконов и высоты потолков.   
   
Также в нашем распоряжении будет следующая информация:    
- дата публикации объявления;
- район или населённый пункт;
- прочая информация об объекте недвижимости - апартаменты, студия или квартира со свободной планировкой;
- количество фотографий;
- удалённость от центра и аэропорта;
- близость парков и водоёмов.

#### <font color='#473C8B'>Ход исследования:</font>

- провести первичную обработку данных - там, где это возможно заменить пропущенные значения, удалить аномальные, найти дубликаты;
- изучить все данные и их распределения, определить особенности;
- проверить все имеющиеся параметры - как и насколько зависит от каждого из них цена на недвижимость;
- проанализировать данные о количестве дней, в течение которых объявления были опубликованы, попытаться найти возможные причины "долгих" продаж;
- выяснить, в какие из населенных пунктов с самым большим (по количеству объявлений) рынком недвижимости имеют также и самые высокие цены на жильё;
- для квартир из Санкт-Петербурга найти как зависит цена от удалённости от центра города, рассчитав цену за 1 км расстояния;
- выбрать параметры, которые являются определяющими для цены на недвижимость, чтобы рекомендовать заказчику осуществлять проверку указанной в объявлении информации.
</div>
<hr>