# MIDWAY R15 — комплекты для теста

Команды копировать по одной строке в админ-чат. Все строки используют точные имена из R15; короткие подписи не меняют ID.

## КОМПЛЕКТ 1 — VECTOR SD + ЕГО МАГАЗИН + 9×19

**Выдать весь комплект:**

```text
#SpawnItem zzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzMIDWAY_VectorSD 1
#SpawnItem zzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzMIDWAY_VectorMagazine40 2
#SpawnItem Cal_9mm 5
```

Зарядить магазин 9×19, установить его в Vector и дослать патрон. Родной магазин MP5 не подставлять вместо специального Vector.

**Что проверить:** Проверить вместимость 40, установку/снятие, перезарядку, одиночную/автоматическую стрельбу, хват рук и звук у второго игрока.

## КОМПЛЕКТ 2 — РУЧНОЙ MINIGUN + КОРОБ 500 + 7,62×39

**Выдать весь комплект:**

```text
#SpawnItem zzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzMIDWAY_Minigun 1
#SpawnItem zzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzMIDWAY_MinigunBox500 2
#SpawnItem Cal_7_62x39mm 25
```

Наполнить короб 7,62×39, закрепить на ручном Minigun и проверить досылание/перезарядку. Count у патронов — число стопок, а не точное число отдельных патронов.

**Что проверить:** Проверить вместимость 500, расход боеприпасов, установку и снятие короба, раскрутку, остановку, звук, руки и выстрелы для второго игрока.

## КОМПЛЕКТ 3 — BINARY RIFLE + ОДНА ЭНЕРГЕТИЧЕСКАЯ ЯЧЕЙКА

**Выдать весь комплект:**

```text
#SpawnItem zzzzzzzzzzzzMIDWAY_BinaryRifle 1
#SpawnItem zzzzzzzzzzzzzzzzzzzzzzzzMIDWAY_RailBattery 2
#SpawnItem zzzzzzzzzzzzMIDWAY_BinaryCharge 2
```

К винтовке установить одну RailBattery. Затем отдельно проверить альтернативную BinaryCharge. Обе сразу не требуются. RailEnergy_Internal — внутренний служебный боеприпас, он не заменяет ячейку.

**Что проверить:** Проверить подготовку выстрела, расход заряда, смену ячейки, удаление пустой ячейки, отмену подготовки и звук/эффект для другого игрока.

## КОМПЛЕКТ 4 — RAIL TURRET + RAILCHARGE + ПИТАНИЕ

**Выдать весь комплект:**

```text
#SpawnItem zzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzMIDWAY_RailTurret 1
#SpawnItem zzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzMIDWAY_RailCharge 5
#SpawnItem ElectricityGenerator_Small 1
#SpawnItem Gasoline_Canister 1
```

Разместить турель штатным взаимодействием/строительством, заполнить RailCharge, проверить подачу питания от генератора. Генератор и топливо — штатные вспомогательные предметы; совместимость/работу питания подтвердить в тесте.

**Что проверить:** Проверить постановку, поворот, обнаружение цели, расход боеприпасов, отключение питания, перенос/ремонт и одинаковое положение у второго игрока.

## КОМПЛЕКТ 5 — SCOUT DRONE + SCOUT DECK + БАТАРЕЯ

**Выдать весь комплект:**

```text
#SpawnItem zzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzMIDWAY_ScoutDrone 1
#SpawnItem zzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzzMIDWAY_ScoutDeck 1
#SpawnItem Smartphone_Battery 1
#SpawnItem Batteries 1
```

Установить в дрон батарею смартфона либо обычную батарейку. Поставить дрон рядом, взять Scout Deck в руки и проверить запуск управления. Батарейки проверяются по очереди.

**Что проверить:** Проверить полёт, возвращение камеры, выход из управления, заряд, посадку при разряде, замену батареи, повреждение/взрыв и отображение у второго игрока.

## КОМПЛЕКТ 6 — TARGET LOCATOR + БАТАРЕЯ LOCATOR

**Выдать весь комплект:**

```text
#SpawnItem zzzzzzMIDWAY_TargetLocator 1
#SpawnItem zzzzzzMIDWAY_LocatorBattery 1
#SpawnItem zzzzzzMIDWAY_LocatorBattery20 1
#SpawnItem zzzzzzMIDWAY_LocatorBattery30 1
#SpawnItem zzzzzzMIDWAY_LocatorBattery40 1
#SpawnItem zzzzzzMIDWAY_LocatorBattery50 1
#SpawnItem zzzzzzMIDWAY_LocatorBattery60 1
```

В целеуказатель устанавливать одну его LocatorBattery. Варианты 20/30/40/50/60 сравнить по очереди. Число в имени варианта не является здесь обещанием проверенного времени работы.

**Что проверить:** Проверить включение без/с батареей, картинку, обнаружение цели, расстояние, расход заряда, извлечение/замену и передачу устройства другому игроку.

## КОМПЛЕКТ 7 — MH6 + БОРТОВОЙ MINIGUN + 7,62×39

**Выдать весь комплект:**

```text
#SpawnVehicle zzMIDWAY_BP_MH6_LittleBird 1
#SpawnItem zzzzzzzzzzzzzzzzzzzzzzzzMIDWAY_MH6_Minigun 2
#SpawnItem zzMIDWAY_BP_MH6_Cargo 1
#SpawnItem Cal_7_62x39mm 10
```

Проверить оружейные места MH6. Бортовой Minigun — отдельный предмет с внутренней загрузкой до 100, ручной короб MinigunBox500 ему не требуется. Оба орудия выдаются для левого/правого места. Грузовой контейнер необязателен для стрельбы и проверяется отдельно; его скрытый ID может отклоняться командой.

**Что проверить:** Проверить посадку/выход, полёт, установку оружия/контейнера, загрузку и расход боеприпасов, стрельбу из соответствующего места и вид для пассажира.

## КОМПЛЕКТ 8 — МАЙНИНГ-ФЕРМА + ПИТАНИЕ

**Выдать весь комплект:**

```text
#SpawnItem zzzzzzzzzzzzzMIDWAY_MiningRig 1
#SpawnItem ElectricityGenerator 1
#SpawnItem Gasoline_Canister 1
```

Разместить ферму и проверить штатное питание Electricity. Заправить/включить генератор; подключение/дистанцию питания проверить в игре.

**Что проверить:** Проверить включение/выключение, отсутствие работы без энергии, оба потребителя, взаимодействие/вывод результата и повторное подключение игрока.

## Транспортные комплекты

КамАЗ и Spy выдавать через `SpawnVehicle`. Все их физические детали перечислены в TEST_COMMANDS_R15.txt рядом со своей машиной. Проверять каждый подходящий модуль отдельно; полному транспорту не обязательно одновременно устанавливать все альтернативные детали.

## Костюмы и независимые предметы

Ghost и Spartan выдаются по одному. Рюкзаки 01/02/03, тепловизор и ZoneGrenade перечислены в полном списке. Проверки первого лица, защиты ног и передачи между игроками включены в TEST_COMMANDS_R15.txt.

## Границы проверки

Все 99 команд сверены по типу и точному ID с реестром R15, пакеты соответствующих классов есть на обеих сторонах. В SCUM команды этого списка не выполнялись. Скрытые записи помечены в полном списке; если сервер отвечает `not allowed to be spawned`, сохранить точный отказ. Предыдущий отказ короткого `MW_PyramidHead` остаётся отдельным фактом.

Silver и пульт команд не имеют отдельного нового первичного ID; несуществующие команды для них не добавлены. Silver проверяется на дроне, появившемся штатным способом.
