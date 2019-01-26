### [Русский](#перевод-gzdoom-на-русский-язык)

### [English](#russian-translation-for-gzdoom)

# Перевод GZDoom на русский язык
![https://u.cubeupload.com/SashaRed/ScreenshotDoom201901.png](https://u.cubeupload.com/SashaRed/ScreenshotDoom201901.png)

### Текущая версия перевода: [0.6.6](https://github.com/Nemrtvi/gzdoom-russian-translation/releases/tag/0.6.6)

Приветствую!

Это — русский перевод для движка [GZDoom](https://zdoom.org/index). Перевод всё ещё находится в разработке и поддерживает следующие игры:
- [*The Ultimate DOOM*](https://ru.wikipedia.org/wiki/Doom_(игра,_1993))
- [*DOOM II: Hell on Earth*](https://ru.wikipedia.org/wiki/Doom_II:_Hell_on_Earth)
	- [*Final DOOM*](https://ru.wikipedia.org/wiki/Final_Doom) (оба эпизода)
- [*Freedoom*](https://freedoom.github.io/) (в разработке)
- [*Heretic: Shadow of the Serpent Riders*](https://ru.wikipedia.org/wiki/Heretic)
- [*Hexen: Beyond Heretic*](https://ru.wikipedia.org/wiki/Hexen)
	- [*Hexen: Deathkings of the Dark Citadel*](https://ru.wikipedia.org/wiki/Hexen#Deathkings_of_the_Dark_Citadel) (в разработке)
- [*Strife: Quest for the Sigil*](https://ru.wikipedia.org/wiki/Strife) (некоторые дополнительные материалы непереведены)

С этим переводом также появляется возможность использовать (почти) все русские буквы в игре и в файлах, вместе с английскими. GZDoom использует кодировку шрифтов [Windows 1252](https://en.wikipedia.org/wiki/Windows_1252), а перевод добавляет символы кириллицы из кодировки [Windows-1251](https://en.wikipedia.org/wiki/Windows-1251). В игре доступны как английский, так и русский наборы символов.

## Инструкция:

1. Скачать последнюю версию файла [*russian.pk3*](https://github.com/Nemrtvi/gzdoom-russian-translation/releases), поместить в папку с GZDoom и перетащить файл на *gzdoom.exe*
	- Если вы хотите, чтобы файл загрузился автоматически при запуске GZDoom, найдите следующий пункт в файле *gzdoom-\<пользователь\>.ini*:
```
[Global.Autoload]
```
Добавьте следующую строку под ним:
```
Path=russian.pk3
```
2. После загрузки GZDoom должен использовать русский язык по умолчанию, если он является системным — если же нет, выберите его в **Options → Language → Русский (RU)**

Готово!

---

## Примечания:
- Буква Ё формально поддерживается, но работает некорректно среди некоторых других букв. В данном переводе она используется только для уточнения слов, смысл которых, без буквы Ё, меняется.
	- Пример: «Игрока %o см**ё**л Крестоносец» вместо «Игрока %o см**е**л Крестоносец»
- Если Вы желаете открыть языковой файл [*language.rus*](pk3/language.rus) для редактирования, [скачайте его с репозитория](https://raw.githubusercontent.com/Nemrtvi/gzdoom-russian-translation/master/pk3/language.rus) (с помощью клавиш Ctrl + S) и откройте с редактором кода, поддерживающим кодировку [Windows-1251](https://en.wikipedia.org/wiki/Windows-1251), например [Notepad++](https://notepad-plus-plus.org/download/) или [Visual Studio Code](https://code.visualstudio.com/).
	- Наиболее эффективный способ отправления отредактированного языкового файла для включения в переводе — отправить pull request.
- Буквы Ч и Я ведут себя немного странно: в *Doom* и *Strife* они работают только в верхнем регистре при написании в заглавных шрифтах (*bigfont.lmp в файле [*zd-extra.pk3*](https://github.com/coelckers/gzdoom/tree/master/wadsrc_extra/static)).
	- Это объясняется отсутствием поддержки строчных вариантов этих букв в кодировке GZDoom — потому в bigfont-строках будет использован верхний регистр для вышеупомянутых букв, или для всей строки целиком.
	- К счастью, это не применяется к обычным, малым шрифтам, поэтому там можно писать свободно. Так же, эти две буквы присутствуют парами в архиве: буква Ч существует и как *stcfn215.lmp*, и как *stcfn247.lmp*, а Я — и как *stcfn223.lmp*, и как *stcfn255.lmp*.

[Тема на форуме ZDoom](https://forum.zdoom.org/viewtopic.php?f=19&t=58872)

[Тема на форуме Doom Power](https://i.iddqd.ru/viewtopic.php?t=1492)

*(Я не русский, а просто моддер, который учит язык и хочет создать перевод для тех, кому это может быть полезно. С радостью выслушаю все предложения по улучшению перевода, и вношу правки по усмотрению!)*

*Данный перевод частично основан на проекте [Russian Doom](https://github.com/JNechaevsky/russian-doom), созданном Юлианом Нечаевским, и на [переводе Strife: Quest for the Sigil](http://arc.iddqd.ru/14072015/viewtopic.php?t=5331), созданном Ameba, theleo\_ua и bed.intruder. С разрешения авторов, в моём переводе используется их творчество.*

---

# Russian translation for GZDoom

### Current translation version: [0.6.6](https://github.com/Nemrtvi/gzdoom-russian-translation/releases/tag/0.6.6)

Welcome!

This is a Russian translation for the source port [GZDoom](https://zdoom.org/index). The translation is still a work in progress and supports the following games:
- [*The Ultimate DOOM*](https://en.wikipedia.org/wiki/Doom_(1993_video_game))
- [*DOOM II: Hell on Earth*](https://en.wikipedia.org/wiki/Doom_II:_Hell_on_Earth)
	- [*Final DOOM*](https://en.wikipedia.org/wiki/Final_Doom) (both episodes)
- [*Freedoom*](https://freedoom.github.io/) (in progress)
- [*Heretic: Shadow of the Serpent Riders*](https://en.wikipedia.org/wiki/Heretic)
- [*Hexen: Beyond Heretic*](https://en.wikipedia.org/wiki/Hexen)
	- [*Hexen: Deathkings of the Dark Citadel*](https://en.wikipedia.org/wiki/Hexen:_Beyond_Heretic#Deathkings_of_the_Dark_Citadel) (in progress)
- [*Strife: Quest for the Sigil*](https://en.wikipedia.org/wiki/Strife_(1996_video_game)) (some extra materials are untranslated)

This translation allows the user to write (nearly) all letters in both the Russian and English alphabets. GZDoom is based on the [Windows 1252](https://en.wikipedia.org/wiki/Windows_1252) encoding for fonts, and by adding Cyrillic characters based on the [Windows-1251](https://en.wikipedia.org/wiki/Windows-1251) (cp1251) encoding, both the English and Russian alphabets can be used ingame.

## Instructions:

1. Download the latest release version of [*russian.pk3*](https://github.com/Nemrtvi/gzdoom-russian-translation/releases), place it in the GZDoom folder and load it ingame
	- If you wish the file to load automatically when launching GZDoom, find the following section in the file *gzdoom-\<user\>.ini*:
```
[Global.Autoload]
```
Copy and paste this line underneath the above section:
```
Path=russian.pk3
```
2. After loading, GZDoom should be set to use Russian by default if it is the system language—if not, select it under **Options → Language → Русский (RU)**

Done!

---

## Notes:
- The letter Ё is officially supported, but works incorrectly around some other letters. In this translation, the letter is used only to clarify words whose meanings would be changed without it.
	- Example: “Игрока %o см**ё**л Крестоносец” compared to “Игрока %o см**е**л Крестоносец”
- If you wish to open the language file [*language.rus*](pk3/language.rus) in the .pk3 archive, [download it from the repository](https://raw.githubusercontent.com/Nemrtvi/gzdoom-russian-translation/master/pk3/language.rus) (using the keys Ctrl + S) and open it using a code editor that supports the [Windows-1251](https://en.wikipedia.org/wiki/Windows-1251) (cp1251) encoding, such as [Notepad++](https://notepad-plus-plus.org/download/) or [Visual Studio Code](https://code.visualstudio.com/).
	- The most efficient way of contributing an edited language file to the translation is to make a pull request.
- The letters Ч and Я behave somewhat strangely: in *Doom* and *Strife*, they work only in uppercase when written in header texts (*bigfont.lmp in the file [*zd-extra.pk3*](https://github.com/coelckers/gzdoom/tree/master/wadsrc_extra/static)).
	- This is due to a lack of support for lowercase variants of these letters in GZDoom’s encoding; therefore, only the uppercase is used for the aforementioned letters in bigfont strings or for the whole string as a whole.
	- Fortunately, this does not apply to regular, small fonts; as such, they can be written freely. On the other hand, these two letters come in pairs in the archive: the letter Ч exists as both *stcfn215.lmp* and *stcfn247.lmp*, and the letter Я appears as *stcfn223.lmp* and *stcfn255.lmp*.

[ZDoom forum topic](https://forum.zdoom.org/viewtopic.php?f=19&t=58872)

[Doom Power forum topic](https://i.iddqd.ru/viewtopic.php?t=1492) (in Russian)

*(I’m not Russian; rather, I’m just a modder with technical knowledge of the source port who also studies the language and wants to create a translation for anyone who might have use for it!)*

*This translation is partly based on the project [Russian Doom](https://github.com/JNechaevsky/russian-doom), created by Yulian Nechaevsky, and on [a Russian translation of Strife: Quest for the Sigil](http://arc.iddqd.ru/14072015/viewtopic.php?t=5331), created by Ameba, theleo_ua and bed.intruder. The aforementioned individuals have given me permission to use their work in this translation.*
