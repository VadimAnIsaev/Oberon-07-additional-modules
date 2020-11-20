Модуль обработки строк в кодировке UTF-8. Для компилятора языка Оберон Антона Кротова https://github.com/AntKrotov/oberon-07-compiler
Простейшие процедуры.

Elementary procedures for processing strings 
in UTF-8 encoding. For compiler lang Oberon of Anton Krotov https://github.com/AntKrotov/oberon-07-compiler

Список процедур:

Length() - длина строки в символах. Length of the string (in simbols).

Copy() - копирование части строки из строки. Copy substring from string.

Pos() - позиция части строки в строке. Position of substring in string.

Delete() - удаление  части строки из строки. Delete substring from string.

Insert() - вставка одной строки в другую. Insert substring into string.

Trim() - удаление пробелов и управляющих символов с начала и конца втроки. Delete space and control chars from string.

UpperCase() - преревод маленьких букв в заглавные. Uppercase symbols in string.

LowerCase() - перевод заглавных букв в маленькие. Lowercase symbols in string.

*Примечание: обе процедуры выше работают с большинством парных европейских символов с диакритами. Плюс греческие символы и кирилица. Для азиатских языков пока не сделано.

*Attantion: the above two procedures work with most European diacritical characters. As well as with Greek and Cyrillic symbols. Asian symbols don't work yet.

IntToHex() - представление целого числа в шестнадцатеричном строковом виде. Present integer in hexstring view.

HexToInt() - перевод строки шестнадцатиричных символов в целое число. Convert hexstring to integer.

StrToInt() - перевод строки с целым числом в целое число. Convert string with integer number to integer.

IntToStr() - представление целого числа в строковом виде. Present integer in string view.
