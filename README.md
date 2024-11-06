## Hedging simulator

Дельта-хеджирование, дельта-вега-хеджирование, дельта-вега-гамма-хеджирование и другие стратегии управления рисками на основе реальных данных по опционам. Используются данные по опционам на акции Apple, которые были получены через Refinitiv с помощью скрипта, расположенного в ноутбуке ```refinitiv_datafetching.ipynb```.

```delta_hedging.ipynb``` - дельта хеджирование, рассмотрены разные интервалы ребалансировки портфеля. Рассмотрено хеджирование стредла

```delta_vega_gamma_hedging.ipynb``` - дельта-вега-хеджирование, дельта-вега-гамма-хеджирование, дельта-гамма хеджирование

Что улучшить

* Добавить больше стратегий опционов помимо стрэддла
* Применить другие стратегии хеджирования для стрэддла и стрэнгла
* Рефакторинг кода
* Более точно сравнить подходы хеджирования
