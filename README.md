Deal Checker – veikiantis B2B skaičiavimo įrankis (Web)

Autorius: Donatas Vitenas
Statusas: Veikiantis internetinis prototipas (ribotos apimties)
Prieiga: vieša, veikia per naršyklę
Techninis veikimas: client-side (be serverio)

🔗 Gyva versija:
https://donatasvit.github.io/deal-checker-full/

Projekto paskirtis

Deal Checker – tai veikiantis B2B skaičiavimo įrankis, skirtas logistikos, transporto ir pardavimų situacijoms, kai reikia:

greitai įvertinti sandorio (deal) pelningumą

suskaičiuoti kaštus, pajamas ir balansą

parengti aiškų tekstą klientui

dirbti be serverio, be prisijungimų, be sudėtingų sistemų

Tai nėra „mock“ ar dizaino demonstracija – visa logika realiai veikia naršyklėje.

Kokią problemą sprendžia šis įrankis

Praktikoje dažna situacija B2B aplinkoje:

skirtingi kroviniai, svoriai, CBM

skirtingi transporto tipai (AUTO / ORAS / JŪRA / MULTIMODAL)

daug kaštų eilučių

reikia greitai suprasti:

ar sandoris pelningas

kokia galutinė kaina klientui

ką tiksliai jam parašyti

Deal Checker leidžia tai padaryti viename ekrane, be Excel, be CRM, be papildomų įrankių.

Ką daro Deal Checker
1. Krovinio skaičiavimai

Eilučių sistema (svoris, matmenys)

Automatinis CBM skaičiavimas

Bendras KG ir CBM

2. Transporto logika

AUTO / ORAS / JŪRA / MULTIMODAL

LTL / FTL logikos pagrindai

LDM (rankinis) palaikymas

3. Kaštai ir pajamos

Laisvai pridedamos išlaidų eilutės

Automatinis:

bendrų išlaidų skaičiavimas

pajamų skaičiavimas

balanso (pelno / nuostolio) skaičiavimas

Maržos logika

4. Tekstas klientui

Automatinis teksto generavimas

Kalbos: LT / EN

Pasirenkama:

ar rodyti maršrutą

ar rodyti krovinio informaciją

ar rodyti tik galutinę kainą

Paruošta kopijavimui

5. Archyvas (lokalus)

Deal’ai saugomi tik naudotojo naršyklėje

Naudojamas localStorage

Jokie duomenys neiškeliauja į serverius

Kodėl šis projektas yra „ribotos apimties“

Šis sprendimas sąmoningai sukurtas be serverio:

❌ nėra duomenų bazės

❌ nėra naudotojų valdymo

❌ nėra API raktų

❌ nėra integracijų su įmonių sistemomis

Tai nėra trūkumas, o architektūrinis sprendimas, leidžiantis:

greitai naudoti

demonstruoti verslo logiką

parodyti mąstymą ir struktūrą

išvengti teisinės ir infrastruktūrinės naštos

Kam šis projektas skirtas

Logistikos ir transporto specialistams

B2B pardavimų vadybininkams

Verslo vadovams

HR – praktinių kompetencijų vertinimui

Asmeniniam / profesionaliam portfeliui

Techniniai akcentai

HTML / CSS / JavaScript

Visa logika vykdoma naršyklėje

Nėra serverio

Nėra duomenų siuntimo į išorę

Duomenys saugomi tik lokaliai

Pastaba

Tai nekomercinis, bet pilnai veikiantis sprendimas, skirtas:

realių darbo scenarijų demonstravimui

diskusijai apie galimą produkto vystymą

kompetencijų parodymui

© Donatas Vitenas

ENGLISH VERSION
Deal Checker – Web-based B2B Deal Calculation Tool

Author: Donatas Vitenas
Status: Working web prototype (limited scope)
Access: Public, browser-based
Architecture: Client-side only (no server)

🔗 Live version:
https://donatasvit.github.io/deal-checker-full/

Project purpose

Deal Checker is a working B2B calculation tool designed for logistics, transport and sales scenarios where users need to:

quickly evaluate deal profitability

calculate costs, revenue and balance

generate a clear client-facing message

work without servers, logins or complex systems

This is not a mock-up – all logic runs in the browser.

What problem it solves

Typical B2B situation:

multiple cargo lines

different transport modes

many cost components

need to quickly understand:

is the deal profitable

what price to offer

what to communicate to the client

Deal Checker provides all of this in one interface.

Key features

Cargo weight & CBM calculation

Transport mode logic

Cost and margin calculation

Profit / loss visibility

Client text generation (LT / EN)

Local deal archive (browser only)

Why it is a “limited scope” solution

This project intentionally has:

no backend

no database

no user accounts

no external system integrations

This allows the tool to stay:

simple

transparent

easy to demonstrate

legally and technically lightweight

Target audience

Logistics & transport professionals

B2B sales managers

Business decision-makers

HR & recruiters

Portfolio reviewers

Technical overview

HTML / CSS / JavaScript

Client-side only

No server

LocalStorage only

Note

This is a non-commercial but fully functional prototype, created for demonstration, discussion and portfolio purposes.

© Donatas Vitenas