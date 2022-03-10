# TonMinerPro
TON-майнер для карт Nvidia и AMD

Последний релиз https://github.com/EvgeniyKorepov/TonMinerPro/releases/latest

- Поддерживаемые пулы:
  - Ton Whales https://tonwhales.com/mining
  - TON Pool https://ton-pool.com/
- Автоматическое переключение пулов для максимальной прибыли
- В интерфейс майнера добавлены кнопки "Pool Web", "Pool stat", "Pool bot", которые соответственно открывают сайт пула, статистику пула по кошельку (если есть), телеграммы ботов пула (если есть)
- В логи баланса майнера добавлены данные о балансе и доходности каждого пула (невозможно получить баланс на пуле Ton-coin)
- CUDA и OpenCL майнинг
- Высокий хешрейт
- Очень низкая загрузка ЦП для cuda
- Блокировка частоты графического процессора и памяти на серии Nvidia RTX 3000. Требуется запустить майнер от имени администратора.
- Подробная статистика в приложении и на сайте статистики https://korepov.com/ton/minerpro/
- Использует майнер с открытым исходным кодом pow-miner-gpu
- Автоматическая смена адресов пулов при сбоях
- Очень низкий процент seed шар

**Приложение взимает 1% разработчику (одна акция из ста идет разработчику)**

Руководство по запуску майнинга https://korepov.com/ton/minerpro/help.php

Пример статистики https://korepov.com/ton/minerpro/?wallet=EQAIxel94QQBAiArH5taFYL0Lwntnhk79-AmcA23BvQsFUtc

Пример значений Bost Factor для разных карт от наших пользователей https://korepov.com/ton/minerpro/boostfactor.php

![image](https://user-images.githubusercontent.com/35364901/155695616-58360852-8a8b-4bb6-99a6-043446be7d99.png)

![image](https://user-images.githubusercontent.com/35364901/154995728-10ceb89f-287e-4e23-91d2-16aef7dc4c7a.png)

![image](https://user-images.githubusercontent.com/35364901/154995818-fe35af0d-28d8-4c9a-b0ea-3fc4846d8075.png)
