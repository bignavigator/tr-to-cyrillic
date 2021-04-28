# Introduction
Greetings. This is my first successful attempt to create a Latin-to-Cyrillic conversion tool, and as such, please don't judge me strictly.

I wanted to create a Turkish Latin to Cyrillic conversion tool for my Turkish friends so they could get fun experience seeing and reading their native language written in the Cyrillic script. Additionally, there's a bizarre wiki focusing around cyrillization of a wide variety of different non-Cyrillic languages, called [Cyrillic Wiki](https://cyrillic.fandom.com/wiki/Cyrillic_Wikia). I would like to contribute to that wiki, using my conversion tool to add Turkish Cyrillic pages.

For anybody else, this tool is useful if you're a) a native speaker of a Cyrillic-based language and wish to learn Turkish in your native script b) a native Turkish speaker and wish to learn a Cyrillic-based language, or just the Cyrillic script c) just want to see how would Turkish look like if it were in Cyrillic for fun. You even can use it to chat with Turkish speakers in a bizarre way, contribute to the Turkish section of the Cyrillic Wiki, introduce this Turkish Cyrillic project to a linguisctics community (be it a social network group, a Telegram chat, a Discord server, a forum, a website, etc.), or whatever will come up to your mind.

## Usage
To use this tool, you don't have to download the file. You just need a browser to get to [this page](https://codepen.io/bignavigator/pen/zYNXavb).

Now you can see a sample Article 1 of the Universal Declaration of Human Rights transliteration in Turkish. Put your own Turkish Latin text into the first field, press on the «Transliterate» button, and get the Turkish Cyrillic text in the second field. Fairly easy, isn't it?

# Transliteration guide
Before asking questions like «Why does Letter X appear and not Letter Y?», please read this guide closely. And of course, my Turkish Cyrillic is neither the absolute definitive standard, nor will become official in the near future.

## Consonants
Almost every consonant can be found on a regular ЙЦУКЕН keyboard layout, with the exception of Ӂӂ from Moldovan Cyrillic, representing the [d͡ʒ] phoneme, and the silent Ғғ consonant.
* **b**ayram → **б**айрам
* **c**evap → **ӂ**евап
* **ç**içek → **ч**ичек
* **d**eve → **д**еве
* **f**ikir → **ф**икир
* **g**üç → **г**үч
* **ğ**arp → **ғ**арп
* **h**ayvan → **х**айван
* **j**enerik → **ж**енерик
* **k**edi → **к**еди
* **l**iyakat → **л**иякат
* **m**ühendis → **м**үхендис
* **p**azartesi → **п**азартеси
* **r**eddetmek → **р**еддетмек
* **s**özlük → **с**өзлүк
* **ş**ıvgın → **ш**ывгын
* **t**aşak → **т**ашак
* **v**iki → **в**ики
* ma**y**mun → ма**й**мун
* **z**orunlu → **з**орунлу

## Vowels
The vowels correspond to those of Kipchak Turkic languages written in Cyrillic.
* **a**raba → **а**раба
* **e**ylem → **е**йлем
* **i**nsan → **и**нсан
* **ı**şık → **ы**шык
* **o**lmak → **о**лмак
* **ö**küz → **ө**күз
* **u**zun → **у**зун
* **ü**züm → **ү**зүм

### Y + Vowel
As you probably know, many Cyrillic languages include so-called iotated vowels: those're basically the /j/ plus a vowel sound, thus you can write one letter instead of two. However, some Cyrillic languages cover just a few pairs (there're only Я and Ю in Bulgarian), the other ones cover the same pairs differently (Е/Є, Ё/Ӧ/ЙО, Ї/ЙИ), and the else are exceptional ones that don't use iotated vowels at all (such as Serbian and Macedonian). 

Meanwhile, Turkish also includes pairs that don't have separate letters as iotated ones in any Cyrillic language (such as yı, yö, and yü). I solved the issue ingeniously: I put extra Cyrillic letters that are derivatives of the remained ones but with diacritics, and conceived them as iotated vowels. I confess they aren't iotated in the languages they're actually used, but the same letters don't have to sound the same in different languages.
* **ya**lan → **я**лан
* **ye**mek → **є**мек
* **yi**rmi → **ї**рми
* **yı**l → **ӹ**л
* **yo**k → **ӧ**к
* **yö**n → **ӫ**н
* **yu**dum → **ю**дум
* **yü**k → **ӳ**к

### Consonant + Iotated vowel
As in Russian, I decided to use the hard (Ъъ) and soft (Ьь) signs in positions where a iotated vowel is located after a consonant. Thus we avoid a possible problem where native Cyrillic readers pronounce медя instead of мед**ь**я: just patalizing the consonant without clear /j/ pronunciation.

Turkish consonants [[can be divided by soft and hard ones]](https://en.wikibooks.org/wiki/Turkish/Pronunciation_and_Alphabet/Consonant_Classifications_and_Harmony). As such, the soft sign is added after soft consonants while the hard sign is after hard ones.
#### Soft consonants
* Li**bya** → Ли**бья**
* me**dya** → ме**дья**
* Fri**gya** → Фри**гья**
* mi**lyo**n → ми**льӧ**н
* Te**myi**z → Те**мьї**з
* **ğ**arp → **ғ**арп
* Esto**nya** → Есто**нья**
* Sibi**rya** → Сиби**рья**
* So**vye**t → Со**вьє**т
* fi**zyo**nomist → фи**зьӧ**номист
#### Hard consonants
* coğra**fya**sına → ӂоғра**фъя**сына
* Küta**hya** → Күта**хъя**
* A**sya** → А**съя**
* e**şya** → е**шъя**
* ko**pya** → ко**пъя**
* Mala**tya** → Мала**тъя**
* o**kya**nus → о**къя**нус

### Circumflex vowels
Additionally, there're 3 circumflex vowels in Turkish. I decided to use the Chuvash Ӑӑ for Ââ. As for Îî and Ûû, I decided to use Ѝѝ and Ӯӯ respectively.
* k**â**r → к**ӑ**р
* mill**î** → милл**ѝ**
* mahk**û**m → махк**ӯ**м

### Apostrophe
The apostrophe comes out the same:
* Türkiye'nin başkenti Ankara'dır. → Түркиє'нин башкенти Анкара'дыр.
