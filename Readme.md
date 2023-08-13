Предсказание стоимости подержанного автомобиля
Описание задачи
Многие знают про маркетплейсы где продаются б/у вещи, на которых есть возможность недорого купить качественную и полезную вещь. Но всегда волнует вопрос - кто и как устанавливает цену, и какие его характеристики больше всего влияют на итоговую стоимость продажи?! Вопрос становиться особо актуальным, если речь идет про дорогие товары, например про автомобили!

Целью проекта будет разработанная модель предсказания стоимости автомобиля на вторичном рынке.

Предоставленные данные
train.csv - информация о характеристиках автомобилей (~440000), которые будут использоваться в качестве обучающих данных.

test.csv - информация о характеристиках автомобилей (~110000), которые будут использоваться в качестве тестовых данных.

Задача - предсказать значение 'sellingprice' для каждого автомобиля из датасета test.csv.

sample_submission.csv - пример файла предсказаний в правильном формате.

vin - идентификатор автомобиля в тестовом наборе.

sellingprice - Целевой признак. Для каждого автомобиля предскажите числовое значение стоимости продажи.

Описание полей данных

Date: Год выпуска автомобиля.

Make: Марка автомобиля.

Model: Модель автомобиля определенной марки.

Trim: Модификации автомобиля.

Body: Тип кузова транспортного средства относится к форме и модели конкретной марки автомобиля.

Transmission: Тип коробки передач.

VIN: Идентификационный номер транспортного средства.

State: Состояние, в котором автомобиль выставлен на аукцион.

Condition: Состояние автомобилей на момент аукциона.

Odometer: Пробег - расстояние, пройденное автомобилем с момента выпуска.

Color: Цвет кузова автомобиля.

Interior: Цвет салона автомобиля.

Seller: Продавец автомобиля, автосалоны.

mmr: Рыночная оценочная цена автомобилей.

sellingprice: цена, по которой автомобиль был продан на аукционе
