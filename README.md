# Ani Cli для Debian based 
![ICON](icon.jpg)
## Оглавление  
- Что такое ani cli
- Зависимости
- Установка    
    1. APT 

    2. GIT  
- Ипользование

<!-- vim-markdown-toc -->

### Что такое ani cli {#whatis}
**Ani cli** - консольная команда, которая позволяет смотреть аниме в терминале. 
### Зависимости 
| Утилита  | Описание                   |     |
| -------- | -------------------------- | --- |
| grep     | Поиск в файлах             |     |
| sed      | Редактирование потока      |     |
| curl     | Передача данных по URL     |     |
| mpv      | Видеоплеер                 |     |
| aria2c   | Менеджер скачивания        |     |
| yt-dlp   | Загрузчик m3u8             |     |
| ffmpeg   | Загрузчик m3u8 (резервный) |     |
| fzf      | Пользовательский интерфейс |     |
| ani-skip | Пропуск опенингов          |     |
| patch    | Самообновление             |     |
### Установка 
1. APT 
```bash
sudo apt install ani-cli
```
2. GIT
 ``` bash
git clone "https://github.com/pystardust/ani-cli.git"
sudo cp ani-cli/ani-cli /usr/local/bin
rm -rf ani-cli 
```
### Использование 
1. ![Поиск](find.png) 
2. ![Vibor](choose.png)
3. ![FInal](final.png)






