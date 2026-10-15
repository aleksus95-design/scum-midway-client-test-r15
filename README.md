# MIDWAY — полный тестовый комплект, 15.10.2026

**Тестер, начинай с клиентского ZIP:** [скачать полный клиентский комплект, 958.8 МБ](https://github.com/aleksus95-design/scum-midway-client-test-r15/releases/download/full-test-20261015-r70-q29-b25804202/MIDWAY_FULL_CLIENT_TEST_20261015_R70_Q29.zip). Все текущие зависимости внутри.

Для администратора: [полный серверный комплект, 736.3 МБ](https://github.com/aleksus95-design/scum-midway-client-test-r15/releases/download/full-test-20261015-r70-q29-b25804202/MIDWAY_FULL_SERVER_TEST_20261015_R70_Q29.zip). Его не устанавливать в клиент.

SCUM **1.3.4.2.161892 / build 25804202**. Танк **R70**, Skyline **Q29**, MH6/V22 **Q1**, Client FULL **R19** / Server FULL **R19 Q22**, Vehicles **R43**, Silver **R44**, Memory **R54**, Zone **R36**, BuildAnywhere **Q22**, WeaponKit **R8+D9**, Stalker/Archer **R3**.

В каждом основном архиве **12 PAK**; 11 общих файлов совпадают у клиента и сервера. В клиентском ZIP есть отдельный необязательный вариант B2 без роботов, вне активной папки SCUM. Моды поставляются только как PAK; дополнительные Lua/DLL не требуются.

- [Установка и откат](https://github.com/aleksus95-design/scum-midway-client-test-r15/releases/download/full-test-20261015-r70-q29-b25804202/START_HERE_RU.md).
- [Что проверять по каждому моду](https://github.com/aleksus95-design/scum-midway-client-test-r15/releases/download/full-test-20261015-r70-q29-b25804202/TEST_PLAN_20261015.md).
- [Комплекты: танк/снаряды, оружие/магазины, устройства/батареи](https://github.com/aleksus95-design/scum-midway-client-test-r15/releases/download/full-test-20261015-r70-q29-b25804202/TEST_KITS_20261015.md).
- [Все 156 команд](https://github.com/aleksus95-design/scum-midway-client-test-r15/releases/download/full-test-20261015-r70-q29-b25804202/TEST_COMMANDS_20261015.txt).
- [Таблица проверки всех 51 оружейных комплектов](https://github.com/aleksus95-design/scum-midway-client-test-r15/releases/download/full-test-20261015-r70-q29-b25804202/WEAPONKIT_51_TEST.csv).
- [Контрольные суммы ZIP](https://github.com/aleksus95-design/scum-midway-client-test-r15/releases/download/full-test-20261015-r70-q29-b25804202/DOWNLOAD_SHA256SUMS.txt), [состав и SHA каждого PAK](https://github.com/aleksus95-design/scum-midway-client-test-r15/releases/download/full-test-20261015-r70-q29-b25804202/MANIFEST_FULL_20261015.json).

Старые FULL/PATCH не добавлять поверх. Игра должна быть закрыта при замене. Для теста зарядки танка отключить бесконечные патроны: **R — пополнение из своего инвентаря, PG-7M для пушки, обычные .50 BMG для пулемёта**. Проверять свежий танк и обе роли. Команды выдачи находятся в инструкции.

Текущие PAK сохранены без изменений. 14 уникальных PAK прошли проверку контейнеров; каждый файл обеих ZIP прочитан обратно и сверен по SHA-256. Запуск 23694 с R70 подтверждён ранее; эта публикация сервер не меняет. Полная игровая приёмка ещё требуется: исчезновение части WK-оружия, исходный магазин, Silver R44/трассер, Ghost после смерти, проходимость/защита танка, звук/нитро Skyline, пассажирские рывки. Проблемные сценарии явно включены в план.

Это **предварительный тестовый релиз**, не заявление об устранении всех крашей. Новое чтение MIDWAY на обоих бортах/корме и изменения подвески/зацепов входят в R70; рабочая цепочка пополнения/стрельбы R66 сохранена.

## Читать инструкции прямо на GitHub

[Начать здесь](START_HERE_RU.md) · [План тестов](TEST_PLAN_20261015.md) · [Комплекты и управление](TEST_KITS_20261015.md) · [Команды](TEST_COMMANDS_20261015.txt) · [51 оружие — таблица результата](WEAPONKIT_51_TEST.csv) · [Шаблон ошибки](BUG_REPORT_RU.md).

[Страница полного релиза](https://github.com/aleksus95-design/scum-midway-client-test-r15/releases/tag/full-test-20261015-r70-q29-b25804202). В GitHub Assets выбирать ZIP с CLIENT или SERVER. Автоматические Source code ZIP/TAR содержат документацию, а не полный набор PAK.

## Старые версии

R15-команды и комплекты в этом репозитории оставлены как история; их инструкции установки устарели. Для текущего теста использовать только полный релиз выше. Предыдущие релизы доступны в [архиве Releases](https://github.com/aleksus95-design/scum-midway-client-test-r15/releases).
