# Bulgarian wordlists
Това хранилище съдържа архивирани файлове със думи и имена на български език както и единни граждански номера. Всичката информация в това хранилище е събрана от публични данни, а номерата са генерирани и валидирани използвайки алгоритъм. Използването на предоставената информация е на своя собствена отговорност.

## Съдържание
  * [Начало](#Bulgarian-wordlists)
  * [Съдържание](#Съдържание)
  * [Какво е wordlist?](#Какво-е-wordlist)
  * [Списъци](#Списъци)
    * [Думи](#Думи)
    * [Имена](#Имена)
    * [ЕГН](#Единен-граждански-номер-ЕГН)
    * [Населени места](#Населени-места)
  * [TO DO](#to-do)

## Какво е wordlist?
Това е списък с думи или номера в редактируем текстов файл, обикновено по една на ред. Имат най-различна употреба от системи за валидиране на очаквани входящи данни до речникова атака (dictionary attack) срещу уеб или настолни приложения.

## Списъци
Списъците съдържат думи на кирилица с малки букви (lowercase) подредени азбучно в текстови файлове с UTF-8 енкодинг. 

Изтегляне на всички думи: [all.txt (кирилица)](https://github.com/miglen/bulgarian-wordlists/blob/master/wordlists/all.txt?raw=true) *(755130 записа)*

### Думи
Списък с думи на български език, без различни форми и времена за сега.

Източници: [1](https://github.com/vanyog/grammar-bg) [2](https://github.com/titoBouzout/Dictionaries)

Изтегляне: [bulgarian-words.txt](https://github.com/miglen/bulgarian-wordlists/blob/master/wordlists/bulgarian-words.txt?raw=true) *(86228 записа)* [bulgarian-wikipedia.txt - Думи в Уикипедия](https://github.com/miglen/bulgarian-wordlists/blob/master/wordlists/bulgarian-wikipedia.txt?raw=true) *(714859 записа)* 

### Имена
Списък с имена на български език. Списъка е подреден в един файл с всички налични имена от източника.

Източници: http://stratsimir.exsisto.com/

Изтегляне: [bulgarian-names.txt](https://github.com/miglen/bulgarian-wordlists/blob/master/wordlists/bulgarian-names.txt?raw=true) *(5506 записа)*

### Единен граждански номер (ЕГН)
Списък с единни граждански номера на български граждани. Списъка е подреден в отделни файлове по години, както и файл със всички възможни валидни номера.
Източници: Генерирани номера от 1800г. до 2100г. и валидирани спрямо алгоритъма на ГРАО - ЕСРАГОН.

Изтегляне: [Всички в един файл - egn.zip](https://github.com/miglen/bulgarian-wordlists/releases/download/v1.0/egn.zip) или [Файлове по години - egn.zip](https://github.com/miglen/bulgarian-wordlists/releases/download/v1.0/egn-by-years.zip) *(109 млрд. записа)*

### Населени места
Списък с имената на населените места в България.

Източници: [Национален Статистически Институт](www.nsi.bg/nrnm)

Изтегляне: [bulgarian-geo.txt](https://raw.githubusercontent.com/miglen/bulgarian-wordlists/master/wordlists/bulgarian-geo.txt) *(4657 записа)*

### TO DO
 * Конвертиране на имената в:
   * Транслитерация на латиница
   * Шльокавица
 * Думи - добавяне на всички думи на български език както и категории. Потенциален източник: [анализ на думите в Уикипедия](http://nikolay.it/Blog/2011/08/%D0%90%D0%BD%D0%B0%D0%BB%D0%B8%D0%B7-%D0%BD%D0%B0-%D0%B1%D1%8A%D0%BB%D0%B3%D0%B0%D1%80%D1%81%D0%BA%D0%B8%D1%8F-%D0%B5%D0%B7%D0%B8%D0%BA-%D1%87%D1%80%D0%B5%D0%B7-Wikipedia/3)
   * Старобългарски
   * Неологизми
   * Диалектни
  * Генериране на ЕГН-та за години, полове и региони.
