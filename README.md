# WoR-Translations
This repository contains the language files for the Windows on Raspberry imager tool.

## Contribute
Updates or new language files can be submitted through pull requests or by creating an issue and attaching the translation file to it. See the status of the existing translations below.

### Notes
* The file structure is very similar to INI configuration files.

* Strings/characters between curly braces must NOT be deleted as they're replaced by the application with the appropriate string. (Google Translate seems to break `{n}{n}` blocks for example, so please keep that in mind)

* The translation should match the English one as much as possible (in terms of punctuation, word capitalization, meaning etc).

* The `Author` field has been removed in version 2.0.0 as it was not used anywhere in the application. 

  You can add your name in the README.md file when submitting a translation update (we'll do it anyway in case you forget).
  
* The translation file must be saved as UTF-8 with BOM.

Issues related to the WoR tool should be reported on the [dedicated bug tracker](https://www.worproject.ml/bugtracker), not on this repository!

## Currently supported languages

| Language                                    | Filename  | Status                                                                       | Contributors 
| ------------------------------------------- | --------- | ---------------------------------------------------------------------------- | --------------
| Bahasa Melayu (Malay)                       | ms-MY.lng | [![Outdated](https://img.shields.io/badge/-Outdated-red)](/lang/ms-MY.lng) | cycool29
| Čeština (Czech)                             | cs-CZ.lng | [![Outdated](https://img.shields.io/badge/-Outdated-red)](/lang/cs-CZ.lng) | czsgaba , martindrey , Nuparu00 , lukajin
| Deutsch (German)                            | de-DE.lng | [![Outdated](https://img.shields.io/badge/-Outdated-red)](/lang/de-DE.lng) | Gnanf , manfred-mueller , EpicLPer , BastiJames333 , Schule04 , NASS-eK , ulrichrobin , Finnie2006
| English                                     | en-US.lng | [![Complete](https://img.shields.io/badge/-Complete-green)](/lang/en-US.lng) | Mario Bălănică
| Español (Spanish)                           | es-ES.lng | [![Complete](https://img.shields.io/badge/-Complete-green)](/lang/es-ES.lng) | TheNeoStormZ , davilico05 , tailys98 , Ivan Ruiz (ivigamergames) 
| Français (French)                           | fr-FR.lng | [![Complete](https://img.shields.io/badge/-Complete-green)](/lang/fr-FR.lng) | SraamaR , Garfi69
| Hrvatski (Croatian)                         | hr-HR.lng | [![Outdated](https://img.shields.io/badge/-Outdated-red)](/lang/hr-HR.lng)   | Biggie 
| Italiano (Italian)                          | it-IT.lng | [![Outdated](https://img.shields.io/badge/-Outdated-red)](/lang/it-IT.lng) | gestef , nopesir , xicciodj , lorecast162 
| Magyar (Hungarian)                          | hu-HU.lng | [![Outdated](https://img.shields.io/badge/-Outdated-red)](/lang/hu-HU.lng)   | Janaboy , Googulator 
| Nederlands (Dutch)                          | nl-NL.lng | [![Complete](https://img.shields.io/badge/-Complete-green)](/lang/nl-NL.lng) | Finnie2006
| Polski (Polish)                             | pl-PL.lng | [![Outdated](https://img.shields.io/badge/-Outdated-red)](/lang/pl-PL.lng) | macmmm81 , Gotard , Marcinoo97 , LUKI N (lukin123) , krolik-exe
| Português (Portuguese)                      | pt-PT.lng | [![Complete](https://img.shields.io/badge/-Complete-green)](/lang/pt-PT.lng) | Miguel Couto
| Português Brasileiro (Brazilian Portuguese) | pt-BR.lng | [![Outdated](https://img.shields.io/badge/-Outdated-red)](/lang/pt-BR.lng)   | Matheus Eduardo , Rafael Fontenelle
| Română (Romanian)                           | ro-RO.lng | [![Complete](https://img.shields.io/badge/-Complete-green)](/lang/ro-RO.lng) | Mario Bălănică
| Slovenčina (Slovak)                         | sk-SK.lng | [![Outdated](https://img.shields.io/badge/-Outdated-red)](/lang/sk-SK.lng) | sebkopal
| Srpski (Serbian)                            | sr-SP.lng | [![Outdated](https://img.shields.io/badge/-Outdated-red)](/lang/sr-SP.lng) | Luka Matovic
| Suomi (Finnish)                             | fi-FI.lng | [![Outdated](https://img.shields.io/badge/-Outdated-red)](/lang/fi-FI.lng) | Mixerboy24
| Svenska (Swedish)                           | sv-SE.lng | [![Outdated](https://img.shields.io/badge/-Outdated-red)](/lang/sv-SE.lng) | Daniel Lundh , joakimus74
| Türkçe (Turkish)                            | tr-TR.lng | [![Outdated](https://img.shields.io/badge/-Outdated-red)](/lang/tr-TR.lng)   | bktech2021 , ysoyipek , pixelomer , SWATcyp
| Русский (Russian)                           | ru-RU.lng | [![Complete](https://img.shields.io/badge/-Complete-green)](/lang/ru-RU.lng) | Andryshik345 , aleksrovinski , beeoss
| Українська (Ukrainian)                      | uk-UA.lng | [![Complete](https://img.shields.io/badge/-Complete-green)](/lang/uk-UA.lng) | Volodymyr Borodaykevych
| 한국어 (Korean)                              | ko-KR.lng | [![Complete](https://img.shields.io/badge/-Complete-green)](/lang/ko-KR.lng) | DoyunShin , rlatn1234 , URK96 , Raccooni
| 日本語 (Japanese)                            | ja-JP.lng | [![Complete](https://img.shields.io/badge/-Complete-green)](/lang/ja-JP.lng) | creeper-0910 , okaits , imai9999 , OSAKANATARO , Prime9999
| 简体中文 (Simplified Chinese)                | zh-CN.lng | [![Complete](https://img.shields.io/badge/-Complete-green)](/lang/zh-CN.lng) | WillowSauceR , F-fengzi , wherewhere , thchi12 , nyaruko , Meaqua233 , CirnoTH
| 繁體中文 (Traditional Chinese)               | zh-TW.lng | [![Complete](https://img.shields.io/badge/-Complete-green)](/lang/zh-TW.lng) | WillowSauceR , WangHan2014 , bacon166539 , Gekoii , ConashinChen
