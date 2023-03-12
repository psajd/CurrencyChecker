# ConcurencyChecker

<br />
<br />

Программа которая раз в 10 секунд опрашивает данные о курсе валют и выводит текущие значения.

По окончанию работы выводит среднее и медианное значение.
В рамках работы было использованно:
 <br />
  1. Данные от ЦБ. Публичное API (https://www.cbr-xml-daily.ru/#howto)
  <br />
  2. Способ им воспользоваться из С++. libcurl (https://curl.se/libcurl/)
  <br />
  3. Библиотека для работы с JSON. Можно выбрать любую, например https://github.com/nlohmann/json
<br />
<br />
<br />



Для хранения и подсчета статистики, спроектированны и реализованны структуры данных,
обеспечивающие оптимальную алгоритмическую сложность расчетов и не
избыточность по памяти.
