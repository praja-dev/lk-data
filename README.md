# Base Data for Sri Lanka

Base data for Sri Lanka under a Public Domain CC0 license.

> 🚧🚧🚧 Under construction—not ready for use. 🚧🚧🚧

## Administrative Divisions

Abbreviations used:
* `PID` - _Parent ID_ points to another object in this dataset
* `SID` - _Sequence ID_ within sibling objects
* `ID` - _ID_ unique across all objects in the Administrative Divisions dataset
* `EID` - _External ID_ the `LIFe Location Code` is used here, which is unique across Sri Lanka government datasets
* `ESID` - _External Sequence ID_ within sibling objects: the `LIFe Code` is used here

LIFe stands for Lanka Interoperability Framework.

### Administrative Divisions

* `9` [Provinces](admin/L1-PROVINCE.csv)
* `25` [Districts](admin/L2-DISTRICT.csv)
* `331` [DS (Divisional Secretariat) Divisions](admin/L3-DSD.csv)
* `14,022` GN (Grama Niladhari) Divisions
  + [Colombo District](admin/L4-GND-01-COLOMBO.csv) `557`GNDs,     `13`DSDs
  + [Gampaha District](admin/L4-GND-02-GAMPAHA.csv) `1177`GNDs,     `13`DSDs
  + [Kalutara District](admin/L4-GND-03-KALUTARA.csv) `762`GNDs,     `14`DSDs

### Electoral Divisions

* Electoral Districts - `22`
* Polling Divisions - `160`
* Polling Districts - `13,314`

## Languages

Sinhala and Tamil are the official languages of Sri Lanka while English is the link language.

Sinhala and Tamil languages and scripts share  many similarities, including some shared vocabulary, 
making it fairly easy for a Sinhala speaker to learn Tamil, and vice versa.

> 🚧🚧🚧 Under construction—many errors and ommissions exist. 🚧🚧🚧

* [Sinhala Vowels](lang/sinhala-vowels.csv) - `20`
* [Sinhala Consonants](lang/sinhala-consonants.csv) - `40`
* [Tamil Vowels](lang/tamil-vowels.csv) - `12`
* [Tamil Consonants](lang/tamil-consonants.csv) - `18`
* [Tamil All Letters](lang/tamil-all-letters.csv) - draft
