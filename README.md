# Ani Cli для Debian based 
images/icon.jpg
## Оглавление  
- [Что такое ani cli](#what_is)  
- [Зависимости](#dependencies)
- [Установка](#install)  
       1. [APT](#apt)  
       2. [GIT](#git)  
- [Ипользование](#usecase)


### Что такое ani cli {#what_is}
**Ani cli** - консольная команда, которая позволяет смотреть аниме в терминале. 
### Зависимости {#dependencies}
| Утилита  | Описание                   |     |
| -------- | -------------------------- | --- |
| grep     | Поиск в файлах             |     |
| sed      | Редактирование потока      |     |
| curl     | Передача данных по URL     |     |
| mpv      | Видеоплеер                 |     |
|          |                            |     |
| aria2c   | Менеджер скачивания        |     |
| yt-dlp   | Загрузчик m3u8             |     |
| ffmpeg   | Загрузчик m3u8 (резервный) |     |
| fzf      | Пользовательский интерфейс |     |
| ani-skip | Пропуск опенингов          |     |
| patch    | Самообновление             |     |
### Установка 
1. APT {#apt}
```bash
sudo apt install ani-cli
```
2. GIT {#git}
 ``` bash
git clone "https://github.com/pystardust/ani-cli.git"
sudo cp ani-cli/ani-cli /usr/local/bin
rm -rf ani-cli ```

### Использование {#usecase}
1. images/find.png 
2. images/choose.png
3. images/final.png






