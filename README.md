*(English further down on the page)*

# Перевод GZDoom на русский язык
![https://u.cubeupload.com/SashaRed/ScreenshotDoom201901.png](https://u.cubeupload.com/SashaRed/ScreenshotDoom201901.png)

### Текущая версия: 0.6

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

С этим переводом также появляется возможность писать русскими буквами в игре и в файлах вместе с английскими. GZDoom использует кодовую страницу [ISO 8859-1](https://en.wikipedia.org/wiki/ISO/IEC_8859-1) для шрифтов, и кириллица доступна в GZDoom после добавления и переименования графических шрифтов в соответствии с их размещением в кириллической кодовой странице [Windows-1251](https://en.wikipedia.org/wiki/Windows-1251).

## Инструкция:

Скачать последнюю релизную версию файла [*russian.pk3*](https://www.dropbox.com/s/0k87m86l0uahuvu/russian.pk3?dl=1) и загрузить его в GZDoom
- GZDoom должен автоматически задать русский как язык по умолчанию, если язык компьютера настроен на русском. Если нет, необходимо ввести *language rus* в консоль.
	- Чтобы вернуться на английский язык, можно написать *language enu* (американский английский) или *language eng* (британский английский).

Готово!

## Примечания:
- Буква Ё формально поддерживается, но работает некорректно среди некоторых других букв. В данном переводе она используется только для уточнения слов, смысл которых, без буквы Ё, изменяется.
	- Пример: «Игрока %o см**ё**л Крестоносец» в сравнении с вариантом «Игрока %o см**е**л Крестоносец»
- Если Вы желаете открыть языковой файл [*language.rus*](pk3/language.rus) в архиве .pk3, экспортируйте его с архива и открывайте с помощью редактора кода, поддерживающего кодовую страницу [Windows-1251](https://en.wikipedia.org/wiki/Windows-1251), например [Notepad++](https://notepad-plus-plus.org/download/) или [Visual Studio Code](https://code.visualstudio.com/).
- Буквы Ч и Я ведут себя немного странно: в *Doom* и *Strife* они работают только в верхнем регистре при написании в заглавных шрифтах (*bigfont.lmp в файле [*zd-extra.pk3*](https://github.com/coelckers/gzdoom/tree/master/wadsrc_extra/static)).
	- Это объясняется отсутствием поддержки строчных вариантов этих букв в кодовой странице GZDoom — потому в bigfont-строках будет использован верхний регистр для вышеупомянутых букв, или для всей строки целиком.
	- К счастью, это не применяется к обычным, малым шрифтам, поэтому ими можно писать свободно. Зато эти две буквы присутствуют парами в архиве: буква Ч существует и как *stcfn215.lmp*, и как *stcfn247.lmp*, а Я — и как *stcfn223.lmp*, и как *stcfn255.lmp*.
- Некрологи в строках 820—863 в файле [*language.rus*](pk3/language.rus#L820) сформулированы забавно — я буду благодарен за помощь с их улучшением примерно по такой структуре: «Игрока %o убил %k»

---

[Тема на форуме ZDoom](https://forum.zdoom.org/viewtopic.php?f=19&t=58872)

[Тема на форуме IDDQD](https://i.iddqd.ru/viewtopic.php?t=1492)

*(Я не русский, а просто моддер с техническим знанием движка, который также учит язык и хочет создать перевод для тех, кому это может быть полезно. Получаю помощь от русскоговорящих друзей по созданию перевода и вношу правки по усмотрению, так что буду благодарен за любой фидбэк!)*

*Данный перевод частично основан на проекте [Russian Doom](https://github.com/JNechaevsky/russian-doom), созданном Юлианом Нечаевским, и на [переводе Strife: Quest for the Sigil](http://arc.iddqd.ru/14072015/viewtopic.php?t=5331), созданном Ameba, theleo_ua и bed.intruder.*

---

# English translation for GZDoom

### Current version: 0.6

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

This translation allows the user to write with all letters in both the Russian and English alphabets. GZDoom uses the [ISO 8859-1](https://en.wikipedia.org/wiki/ISO/IEC_8859-1) codepage for fonts, and the Cyrillic alphabet becomes usable in GZDoom after adding and naming graphical characters in line with their placement in the Cyrillic codepage [Windows-1251](https://en.wikipedia.org/wiki/Windows-1251).

## Instructions:

Download the latest release version of [*russian.pk3*](https://www.dropbox.com/s/0k87m86l0uahuvu/russian.pk3?dl=1) and load it in GZDoom
- GZDoom should automatically set Russian by default if the language of the computer is set to Russian. If not, the command *language rus* must be entered in the console.
	- To return to English, either the commands *language enu* (American English) or *language eng* (British English) are viable.

Done!

## Notes:
- The letter Ё is officially supported, but works incorrectly around some other letters. In this translation, the letter is used only to clarify words whose meanings would be changed without it.
	- Example: “Игрока %o см**ё**л Крестоносец” in comparison with “Игрока %o см**е**л Крестоносец”
- If you wish to open the language file [*language.rus*](pk3/language.rus) in the .pk3 archive, export it from the archive and open it using a code editor that supports the [Windows-1251](https://en.wikipedia.org/wiki/Windows-1251) codepage, such as [Notepad++](https://notepad-plus-plus.org/download/) or [Visual Studio Code](https://code.visualstudio.com/).
- The letters Ч and Я behave somewhat strangely: in *Doom* and *Strife*, they work only in uppercase when written in header texts (*bigfont.lmp in the file [*zd-extra.pk3*](https://github.com/coelckers/gzdoom/tree/master/wadsrc_extra/static)).
	- This is due to a lack of support for lowercase variants of these letters in GZDoom’s codepage; therefore, only the uppercase is used for the aforementioned letters in bigfont strings or for the whole string as a whole.
	- Fortunately, this does not apply to regular, small fonts; as such, they can be written freely. On the other hand, these two letters come in pairs in the archive: the letter Ч exists as both *stcfn215.lmp* and *stcfn247.lmp*, and the letter Я appears as *stcfn223.lmp* and *stcfn255.lmp*.
- Obituaries on lines 820—863 in the file [*language.rus*](pk3/language.rus#L820) are badly written — help is appreciated with improving them according to this sentence structure: “Игрока %o убил %k”

---

[ZDoom forum topic](https://forum.zdoom.org/viewtopic.php?f=19&t=58872)

[IDDQD forum topic](https://i.iddqd.ru/viewtopic.php?t=1492) (in Russian)

*(I’m not Russian; rather, I’m just a modder with technical knowledge of the source port who also studies the language and wants to create a translation for anyone who might have use for it. I receive help from Russian-speaking friends with developing the translation, and I make all creative decisions, so I am be grateful for any feedback!)*

*This translation is partially based on the project [Russian Doom](https://github.com/JNechaevsky/russian-doom), created by Yulian Nechaevsky, and on [a Russian translation of Strife: Quest for the Sigil](http://arc.iddqd.ru/14072015/viewtopic.php?t=5331), created by Ameba, theleo_ua и bed.intruder.*