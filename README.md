# Analysis-projects
Решение различных кейсов по анализу данных

## ABC_analysis
**Задача**: Бизнес-заказчик - региональная торговая сеть Загляника. Они работают в формате магазина у дома и продают бытовую химию, косметику, текстиль, посуду и прочие бытовые товары. Из-за формата магазина у дома у них маленькая площадь, из-за чего вопрос ассортимента стоит наиболее остро - постоянно нужно выводить плохие товары из ассортимента, быстро тестировать новые и выжимать максимум из основного ядра ассортиментной матрицы.

**Выводы**:

**Группа AAA** - посмотреть XYZ, чтобы принять решение о поднятии цены
* Если группа X - можно поднимать цену на короткий период, чтобы увеличить маржинальность. Тестим в течение небольшого срока, чтобы оценить динамику продаж.
* Если группа Y/Z, лучше не увеличивать цену, потому что сложно будет оценить влияние. Лучше понять, почему спрос нестабильный. И либо поднять цену, но аккуратно + спланировать эксперимент на более длинный срок, либо не повышать цену (если, например, покупают только по акции).

**Группа ССA** - оценить объективность причин + часть вывести из ассортимента (их много) + попробовать перевести в группу повыше по количеству (а может и по выручке за счет этого)
* Объективность причин - не отсутствовал товар, есть ли он на полке, нормально ли его видно, не просроченный ли он.
* Подтянуть в группу B по количеству можно за счет акции 1+1 или 2+1 даже. Т.к. товар дешевый, его покупают экономичные люди. А значит можно увеличить средний чек и количество продаж за счет такой акции, стимулируя покупать больше.
* Аистенок, Дени и Сарма примерно с одинаковыми показателями, при этом там нет каких-то нишевых товаров - скорее всего это покупают условные бабушки, которым все равно. А значит можно сократить до 2 товаров.

**Группа AAB** - нужно просто найти более выгодную цену поставки, чтобы стать AAA. Либо попробовать немного подтянуть цену, если это группа X по XYZ-анализу.

**Группа ABA** - судя по всему, какой-то нишевый порошок СПАРК ДРАМ. Нужно увеличить количество продаж, не упав в прибыли. Можно попробовать постепенно:
* Поставить на более видное место + выделить какими-то ценниками или промо-оформлением
* Сделать акцию формата 1+1
* Сделать акцию скидка при покупке от N штук
* Сделать акцию через кросс-сейл, например, при покупке кондиционера скидка 10% на порошок СПАРК ДРАМ (главное не уронить доходность, оставить в группе А)

**Группа ABB**. BIO Mio - нишевая линейка, приносит средний доход и продается в среднем количестве. Это очень хорошо для нишевых продуктов. Можно попробовать подтянуть какой-то один показатель - и лучше пусть это будет количество. Люди привыкнут к продукту, а потом можно будет поднять цену и подтянуть доходность. Соответственно - выставляем на видное место, сочно оформляем, делаем акцию на их продукцию. Для сохранения доходности можно попросить поставщика дать скидку на время акции.

**Группа BAA**. Попрошок Пемос - продается много, хорошая доходность, но просто за счет низкой цены маленькая выручка. Цену поднимать довольно опасно, увеличивать сильно количество продаж - бессмысленно (т.к. дешевый сегмент). Можно просто оставить как есть.

**Группа BAB**. Ariel - довольно дорогой бренд. По количеству в группе А, но средняя доходность и средняя выручка. Если он в группе X/Y по цене, стоит попробовать поднять цену и подтянуть выручку и прибыль.

**Группа BBA**. Persil - аналог Ariel, та же история. Но у него нормальная доходность, при этом не очень много продаж. Стоит подтянуть количество продаж. Как вариант - посмотреть расположение на полках Ariel и Persil. Ariel в группе А по количеству - может быть его поставить повыше, а Persil на уровне глаз, чтобы стимулировать продажи. А Ariel, если его покупают много, потому что любят, сильно в количестве не упадет.

**Группа BCC**. Линейка Meine Liebe - еще одна нишевая линейка. Но в отличие от BIO MIO, она продается мало и с плохой доходностью. Поднимать цену нельзя - и так мало продается. Акцию не сделаешь - и так доходность маленькая.
* Ищем другого поставщика или сбиваем цену у текущего, чтобы увеличить прибыль.
* Нужно увеличить продажи и привить любовь к бренду - расставляем по магазину для кросс-сейла (например, можно поставить порошок для шерсти около пледов), ставим на кассу. Можно выдавать пробники - работает отлично. Визуально выделяем линейку, чтобы выглядело сочно.
* Делаем акцию - при покупки Meine Liebe скидка N% на какую-то высокомаржинальную смежную штуку (например, средство для посуды). За счет этого повышаем продажи, но не роняем маржинальность самого товара.
* Фиксируем срок эксперимента (в зависимости от проходимости - несколько недель или несколько месяцев). Если не помогает - выводим и пробуем другую линейку.

**Группа CBA**. Порошок АИСТ - та же история, что с группой CCA, только продается чаще. За счет вывода из ассортимента 1-2 товаров из группы CCA может вырасти его кол-во покупок и он станет CAA.

**Группа CBB**. По аналогии с CBA и CCA. Только и продается средне, и доходность низкая. Можно либо найти более дешевую цену закупки и перевести в группу CBA. Либо также посмотреть на изменение метрик за счет сокращения ассортимента.

**Группа CCC**. Меуле - нишевая фирма, но у нас она в аутсайдерах по всем параметрам, включая доходность (обычно нишевые вещи в топе по доходности, на этом можно играть). Имеет смысл вывести - фанатов у нее явно не много - и попробовать другую линейку. Либо вообще не пробовать пока и посмотреть на изменения в других нишевых линейках.

## ChatGPT_Reviews_Analysis
**Задача**: С момента выпуска ChatGPT получил множество отзывов от пользователей, которые выражают свое мнение с помощью оценок и текстовых обзоров. Понимание настроений пользователей и факторов, определяющих удовлетворенность или неудовлетворенность, имеет решающее значение для улучшения продукта и улучшения пользовательского опыта. 

**Выводы**:

* В основном большинство пользователей высказываются позитивно о приложении (76% пользователей), они отмечают, что приложение восхитительно и помогает им в решение их задач;
* В динамике идет рост пользования приложением и увеличением количества отзывов как положительных, так и отрицательных;
* В основном большинтсов отрицательных отзывов связано с неправильными ответами ChatGPT;
* Рассчитанный показатель NPS оказался на уровне 64, что говорит об отличном отношение пользователей.
