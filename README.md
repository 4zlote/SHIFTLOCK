# SHIFTLOCK

## O systemie

#### Jeśli jesteś studentem Uniwersytetu Śląskiego, masz wielki natłok pracy i nie masz czasu sprawdzić planu zajęć. Chciałbyś wiedzieć czy jakiś przedmiot nie został przesunięty albo odwołany lub po prostu nie masz Internetu żeby sprawdzić co czeka Cię następnego dnia na studiach nasz system ci w tym pomoże.

#### Wyślij mail z prośbą o dołączenie już teraz!

#### System  przed każdym rozpoczynającym się dniem o godzinie 17 wyśle Ci sms, w którym poinformuję Cię o Twoim planie zajęć, godzinie rozpoczęcia i o ewentualnych zmianach. 

## To nie wszystko
#### System uwzględni również numer sali w których odbędą się zajęcia.

## Rynek

#### Na rynku pojawiły się też programy podobne do naszego takie jak:  https://serwersms.pl/funkcje/funkcje-systemowe
#### Jednak że nasz program jest mniej skomplikowany. Jedynie co należy zrobić to wysłać maila i zapoznać się z naszymi szczegółami.

#### Aby mieć pewność, że korzystasz z naszego produktu nasza firma posługuje się tym logo:

## [Click me](https://drive.google.com/file/d/1dhihyDA8MSp9ByKUoQj2dUPQPQWZ-wFv/view?usp=sharing "Google's Homepage")

 #### Z obawy przed podróbkami nasza firma zastrzegła sobie logo naszej strony które przedstawia: ołówek na którym widnieje napis ,,sheduleus.me” natomiast na gumce tego ołówka widnieje skrót naszego Uniwersytetu ,,US”.


## Kontakt

### Jeśli chcesz się z nami skontaktować, zapraszamy na stronę internetową SCHEDULEUS.ME na facebooku, osobiście w godzinach od 14-18 na ul. Sokolskiej 2 w Katowicach w każdy poniedziałek i piątek lub podjedź do nas na uczelni.


## Kod systemu

``` Create to and message vars with your own values
In [16]: to = "..."
         message = "Twój plan na dzisiaj:"
In [17]: url + "/%s/%s" % (to, message)
Out[17]:'https://justsend.pl/api/rest/message/send/JDJhJDEyJGtRL0dkMVowbmdFakFQd2tvUWtNdWVwalJZWlNTaUM4SVozTXJkUWpLSzFGMGRkMC8wdm9p/48881345922/Twój plan na dzisiaj'
In [18]: import urllib
message = urllib.parse.quote(message)
url += "/%s/%s" % (to, message)
url
Out[18]:'https://justsend.pl/api/rest/message/send/JDJhJDEyJGtRL0dkMVowbmdFakFQd2tvUWtNdWVwalJZWlNTaUM4SVozTXJkUWpLSzFGMGRkMC8wdm9p/.../Twoj_plan%2C%20na_dzisiaj%21'
```






