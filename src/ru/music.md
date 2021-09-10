# Категория: **Music**
### `/play <query>`
Начать воспроизведение трека или же добавить его в очередь.
Вы должны находиться в голосовом канале, чтобы использовать эту команду.

> **Задержка**: 5 секунд   
> **Требуемые права**: Нет

### `/repeat <choice>`
Управление режимом повторения трека. Если аргумент `choice` равен
значению `Yes-s-s` - режим повторения будет включен. Выбор значения
`No` - отключит режим повторения трека.

> **Задержка**: 5 секунд   
> **Требуемые права**: Нет

### `/stop`
Остановить проигрывание музыки на этом сервере. Вы при этом должны
находиться в голосовом канале.

> **Задержка**: 5 секунд   
> **Требуемые права**: Нет

### `/pause`
Снять или поставить воспроизведение на паузу. Если воспроизведение на
паузе, то снимет, если нет, то поставит.

> **Задержка**: 5 секунд   
> **Требуемые права**: Нет

### `/skip`
Пропустить текущий трек и начать воспроизведение следующего. Если
текущий трек - последний в очереди, то воспроизведение будет остановлено.

> **Задержка**: 5 секунд   
> **Требуемые права**: Нет

### `/rewind <time>`
Перемотать трек на определенный момент. Для перемотки используется
следующий формат времени: `mm:ss`, где `m` - минуты, `s` - секунды.
Например: `/rewind 2:35`

> **Задержка**: 5 секунд   
> **Требуемые права**: Нет

### `/volume [new_volume]`
Изменить уровень громкости. Максимальный уровень громкости - 200%.
Узнать, какая громкость проигрывателя установлена в данный момент
можно с помощью команды `/nowplaying`.

> **Задержка**: 5 секунд   
> **Требуемые права**: Нет

### `/nowplaying`
Информация о текущем треке, а также очередь воспроизведения.
Отображает полосу прогресса проигрывания, громкость, позицию плеера,
длительность трека, его название, ссылку на источник и многое другое.

> **Задержка**: 5 секунд   
> **Требуемые права**: Нет