# SVO

Проблема
Пассажиры из самолета в терминал попадают двумя способами: через телетрап или на автобусе. Автобусов и водителей в аэропорту – много (до 200). В аэропорту случаются тысячи форс-мажоров:
- Задержки рейсов
- Опоздания пассажиров
- Нештатные ситуации

Автобусами и водителями надо управлять:
- Распределять между рейсами
- Ставить задачи
- Контролировать исполнение
- Обеспечивать своевременное обслуживание пассажиров

### Задача

Необходимо разработать систему управления пассажирскими автобусами аэропорту.
Кто пользователи?
- Водители автобусов
- Диспетчеры аэропорта
- Руководители аэропорта

### Задачи:

- Формирование заданий водителям
- Контролировать исполнение задач диспетчером
- Визуализировать процесс исполнения в режиме реального времени (не в виде карты)
- Интерфейс для водителя
- Оптимизация количества используемой техники и водителей
В веб-интерфейсе решения диспетчер должен иметь возможность:
- Просмотреть задачи, назначенные ресурсам
- Изменить исполнителя, продолжительность и время задачи (интерактивно)
- Изменить масштаб отображения задач
- Визуально понять, в каком статусе находится
- Посмотреть детальную информацию по задаче

### В веб-интерфейсе мобильного приложения должен быть функционал:

- Базовой авторизации
- Принять, начать, закончить выбранную задачу
- Завершенные задачи в интерфейсе исполнителя не отображаются
- Панель статистики в интерфейсе диспетчера: Up to you ))

### По результатам разработки необходимо предоставить:

- Презентацию, отражающую особенности решения
- Автоматический генератор задач на доставку пассажиров автобусами
- Автоматический оптимизатор задач (назначение исполнителей)
- Веб-интерфейс рабочего места диспетчера
- Веб-интерфейс рабочего места исполнителя (на мобильном телефоне)
- Исходный код, размещенный в открытых источниках

### При реализации требуется учесть, что:

- Занятый ресурс не может быть использован в одно и то же время на разных задачах
- Диспетчер может назначать и снимать задачи с исполнителя
- Задачи без исполнителя должны отображаться в отдельной зоне
- С системой может работать несколько диспетчеров
- Требуется оперативное отображение изменений по задачам

### Данные:

1. Количество автобусов с водителями: Тип №1 – 30, вместимость – 100 чел.; Тип №2 – 10, вместимость – 50 чел.
2. Время выполнения 1 задачи: 10мин посадка + время на передвижение + 5 мин высадка.
3. Время начала задачи:
- Прилет – по факту посадки рейса (берем плановое время по расписанию)
- Вылет – за 30 минут до планового времени вылета
4. Скорость движения автобуса: 30 км/ч
5. Расписание рейсов с указанием кол-ва пассажиров: clck.ru (https://clck.ru/32RxU2)
6. Матрица расстояний от места стоянки до гейта, в метрах: clck.ru (https://clck.ru/32RxRh)

## Sourse

- [Задача поиска ближайшего соседа](https://ru.m.wikipedia.org/wiki/Задача_поиска_ближайшего_соседа)
- [Sprin Security](https://www.marcobehler.com/guides/spring-security)
- [KD tree Python](https://kanoki.org/2020/08/05/find-nearest-neighbor-using-kd-tree/)
- [KD tree java](https://github.com/Jilocasin/nearest-neighbour?ysclid=l9iw21wf1k448685638)
- [KNN C++](https://medium.com/stepstone-tech/native-like-performance-for-nearest-neighbors-search-using-hnswlib-in-java-applications-f3c4d19b39b5)
- [ML java](https://www.codingame.com/playgrounds/5439/machine-learning-with-java---part-3-k-nearest-neighbor)
- [ML ШАД](https://ml-handbook.ru/chapters/metric_based/intro?ysclid=l9ivuqpyox53399634)
- [java + Exel](https://www.youtube.com/watch?v=McZ77Y9jZno)
