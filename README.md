# Asterisk-syntax
 Asterisk-syntax

Asterisk syntax file "asterisk.syntax" for "mcedit" need place to this directory
/usr/share/mc/syntax


Also need add line 
file ..\*\\.(conf)$ Config\sFile
include asterisk.syntax




На памать запишу регулярное выражение для валидации номера телефона в России:

^((8|\+7)[\- ]?)?(\(?\d{3}\)?[\- ]?)?[\d\- ]{7,10}$
