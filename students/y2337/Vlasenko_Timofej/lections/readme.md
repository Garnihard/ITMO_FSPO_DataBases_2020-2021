OLTP, транзакционная система — обработка транзакций в реальном времени.
Способ организации БД, при котором система работает с небольшими по размерам транзакциями, но идущими большим потоком,
и при этом клиенту требуется от системы минимальное время отклика.

OLAP — технология обработки данных, заключающаяся в подготовке суммарной (агрегированной)
информации на основе больших массивов данных, структурированных по многомерному принципу.

Преимущества OLTP:
Высокая надёжность и достоверность данных, как следствие транзакционного подхода.
Транзакция либо совершается полностью и успешно, либо не совершается и система возвращается к предыдущему состоянию.
При любом исходе выполнения транзакции целостность данных не нарушается.
Недостатки OLTP:
OLTP-системы оптимизированы для небольших дискретных транзакций.
А вот запросы на некую комплексную информацию, характерные для аналитических приложений (OLAP),
породят сложные соединения таблиц и просмотр таблиц целиком.
На один такой запрос уйдет масса времени и компьютерных ресурсов, что затормозит обработку текущих транзакций.

Преимущества OLAP:
Основное преимущество OLAP — скорость. Реляционные базы данных хранят сущности в отдельных таблицах,
которые обычно хорошо нормализованы. Эта структура удобна для операционных баз данных (системы OLTP),
но сложные многотабличные запросы в ней выполняются относительно медленно.
Недостатки OLAP:
