## Что это? / Another Amica git?
"Amica for Windows" - это попытка сделать **Amica** более доступной для запуска на OS Windows.  
Оригинальный проект [Amica](https://github.com/semperai/amica) был предназначен для Linux, поэтому запускался с ошибками на Windows.  

Моя доработка заключается в изменении определения путей файлов в папке **_./amica/public_** с помощью... изменения слешей в обозначении путей: с \ на _**/**_. Да, все решения ошибок на Windows заключаются только в этом.

Не вспомню в каком из скриптов я это поправил, но теперь оно работает. Сделал архив того что у меня уже работает, поэтому надеюсь, что вам будет достаточно просто распаковать архив и запустить Amica.  

----  

“Amica for Windows” is an attempt to make **Amica** more accessible for running on Windows.  
The original [Amica](https://github.com/semperai/amica) project was designed for Linux, so it ran with errors on Windows.  

My modification involves changing the file path definitions in the **_./amica/public_** folder by... changing the slashes in the path notation: from \ to _**/**_. Yes, that’s all it takes to fix the errors on Windows.

I can't remember which script I fixed this in, but it works now. I've created an archive of what's already working for me, so I hope you'll just need to unzip the archive and run Amica.  


## Что добавлено? / What's added?

В архиве добавлена папка **_"Autostart .bat'niks"_** с .bat-файлами для автозапуска Amica в двух вариантах:  

1. Только Amica
2. Amica + llama.cpp + TTS

Эти файлы можете править как вам угодно, но прочитайте **_"read me before start.txt"_**, который лежит в этой же папке, перед началом.

Также добавлена моделька от <хз чё за автор>, скачаная из [VRoid](https://hub.vroid.com/) среди свободно распространяемых vrm-моделей. Мне она показалась прикольной, и я решил её оставить. Если вы против - можете удалить её, мне лень убирать её из архива.  

-------------  

The archive includes a folder named **_“Autostart .bat'niks”_** containing .bat files for automatically launching Amica in two configurations:  

1. Amica only
2. Amica + llama.cpp + TTS

You can edit these files as you like, but please read **_“read me before start.txt”_**, which is located in the same folder, before you begin.

I’ve also added a model by <Author_whats_he's_name>, downloaded from [VRoid](https://hub.vroid.com/) among the freely distributed VRM models. I thought it was cute, so I decided to keep it. If you don’t like it, you can delete it—I’m too lazy to remove it from the archive.


## Планы / Plans
Ещё у меня в планах добавить в Amica поддержку агентных систем. Зачем? Просто потому что хочу 😛  

Это случится не скоро из-за большой загрузки на работе, но релизы буду публиковаться здесь, а новости на моих страницах:  
- [Telegram](https://t.me/Nez_Norlag)
- [Twitter](https://x.com/Nez_Norlag)

---  

I also plan to add support for agent-based systems to Amica. Why? Just because I want to 😛  

It won’t happen anytime soon due to my heavy workload, but releases will be posted here, and news will be shared on my pages:  
- [Telegram](https://t.me/Nez_Norlag)
- [Twitter](https://x.com/Nez_Norlag)

## Как запустить? / How to start?
Архив содержит всё необходимое для запуска.  

Шаги:  
1. Распаковать;
2. Ввести в адресную строку Проводника команду _cmd_ и нажать _Enter_;
3. После того как откроется командная строка ввести команду: _npm run dev_ и нажать _Enter_;
4. Открыть браузер;
5. Ввести в адресную строку _localhost:3000_ и нажать _Enter_;
6. Пользоваться!

<sup>*</sup> _Обратите внимание, что в настройках командной строки должен быть включен запуск от имени Администратора!_  

...Или используйте .bat-файлы из папки **_"Autostart .bat'niks"_**, но перед этим прочитайте **_"read me before start.txt"_**.

[Здесь](https://github.com/NezNorlag/Amica-for-Windows/releases) расположен сильно сжатый rar-архив, на [Hugging Face](https://huggingface.co/datasets/Nez-Norlag/Amica_for_Windows) - тот же самый архив, но без сжатия.

--------------------------------------------------------------------------------------------

The archive contains everything you need to get started.  

Steps:  
1. Extract the files;
2. Type _cmd_ in the address bar of File Explorer and press _Enter_;
3. Once the command prompt opens, type the command: _npm run dev_ and press _Enter_;
4. Open your browser;
5. Type _localhost:3000_ in the address bar and press _Enter_;
6. Enjoy!

<sup>*</sup> _Please note that the command prompt settings must be configured to run as Administrator!_  

...Or use the .bat files from the **_“Autostart .bat'niks”_** folder, but be sure to read **_“read me before start.txt”_** first.

[Here](https://github.com/NezNorlag/Amica-for-Windows/releases) is a highly compressed RAR archive. On [Hugging Face](https://huggingface.co/datasets/Nez-Norlag/Amica_for_Windows) - same archive, but uncompressed.

--------------------------------------------------------------------------------------------
