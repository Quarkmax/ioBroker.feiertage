![Logo](admin/feiertage.png)
# ioBroker.feiertage
=================

[![NPM version](http://img.shields.io/npm/v/iobroker.feiertage.svg)](https://www.npmjs.com/package/iobroker.feiertage)
[![Downloads](https://img.shields.io/npm/dm/iobroker.feiertage.svg)](https://www.npmjs.com/package/iobroker.feiertage)
[![Tests](https://travis-ci.org/ioBroker/ioBroker.feiertage.svg?branch=master)](https://travis-ci.org/ioBroker/ioBroker.feiertage)

[![NPM](https://nodei.co/npm/iobroker.feiertage.png?downloads=true)](https://nodei.co/npm/iobroker.feiertage/)

## Beschreibung / Description
Deutsch  | English
------------- | -------------
Dieser Adapter liefert das Datum und den Namen des nächsten deutschen Feiertages und gibt Auskunft, ob heute, morgen oder übermorgen ein Feiertag ist.  | This adapter delivers date and name of the next German holiday. Furthermore it tells if today, tommorw or the day after tommorow is a holiday in Germany.



## Datenpunkte / Datapoints

Feiertag heute  (false/true)

Feiertag heute Name  (z.B. "1. Weihnachtsfeiertag")

Feiertag morgen  (false/true)

Feiertag morgen Name  (z.B. "2. Weihnachtsfeiertag")

Feiertag uebermorgen  (false/true)

Feiertag uebermorgen Name  (z.B. "")

Feiertag naechster Name  (z.B. "Maifeiertag")

Feiertag naechster Datum  (z.B. "01.05.2016")

Feiertag naechster Dauer  (z.B. "2 Tage")

## Einstellungen / Configuration
Deutsch  | English
------------- | -------------
Es können keine Einstellungen am Adapter vorgenommen werden.  | There is nothing to setup.

## Aktivierung / Schedule
Deutsch  | English
------------- | -------------
Der Adapter startet jeden Tag um Mitternacht. Ein häufigeres Starten ist nicht erforderlich. | The adapter starts daily at midnight. Due to the nature of the subject, no higher frequency is required.

## Changelog
### 0.0.3 (2016-04-27)
* (pix) Writing to objects corrected
* (pix) Workaround for formatDate

### 0.0.2 (2016-04-27)
* (pix) Title and description corrected
* (pix) English translation of readme file

### 0.0.1 (2016-04-26)
* (pix) Adapter created

## Todo

* Übersetzungen / Translation
* Dauer wird ggf. falsch berechnet
* Einstellungsdatei / config file

## License

The MIT License (MIT)

Copyright (c) 2016 pix

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
---
Logo is crafted by CHALLENGER
Thank you, paul53, for the inspiration!
