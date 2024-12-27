# DDON-Rus
Русификатор Dragons Dogma Online

Гугл-перевод [английского перевода](https://github.com/Sapphiratelaemara/DDON-translation) с некоторыми ручными правками 

Фаил `gmd.csv` содержит сам перевод на русский язык.

Файлы `gui_cmn.arc` и `gui_cmn_win.arc` содержат исправленный шрифт кирилицы в игре.

# Установка
1. Скачать [здесь ](https://github.com/sebastian-heinz/Arrowgene.DragonsDogmaOnline/releases)архив с файлами сервера подходящий к вашей ОС
2. Распаковать скачанный архив в любое место и распаковать распакованный архив в любое место. В результате должна быть папка `./publish`
3. Из папки `.\publish\win-x64-1.0.0.0` копируем папку `Server` и фаил `pack_gmd_english.cmd` в папку *nativePC в папке с игрой*, а именно в  `Dragons Dogma Online\nativePC` приняв замену файлов.
4. Скачать файлы из этого репозитория (любым способом, например архивом - вверху нажать *Code -> Download ZIP*).
5. Фаил `gmd.csv` скачанный из этого репозитория поместить в папку `Dragons Dogma Online\nativePC\Server\Files\Client` приняв замену.
6. Запустить процесс перевода игровых файлов - перейти в папку `Dragons Dogma Online\nativePC` и перетянуть папку `rom` на фаил `pack_gmd_english.cmd`. Должно открыться окно с командной строкой отображающее прогресс процесса перевода.
7. По окончанию процесса перевода файлы `gui_cmn.arc` и `gui_cmn_win.arc` скачанные из этого репозитория скопировать в папку `Dragons Dogma Online\nativePC\rom\ui` приняв замену.