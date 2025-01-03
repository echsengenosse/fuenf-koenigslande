---
tags:
  - "#Charakter"
  - "#NPC"
ausgesprochen: RIV-ven
bild: content/z_Dateien/Bilder/Riven.png
sprache:
  - Gemeinsprache
  - elfisch
  - Diebessprache
  - urtümlich
aliases:
  - ---
beruf:
  - ---
volk: Halbelf
alter: Teenager
geschlecht: männlich
sexualität: heterosexuell
heimat:
  - "[[Dumenor]]"
gesinnung: C|N
status: lebendig
organisation:
  - "[[Sturmwache]]"
ort:
  - "[[Nebelhain]]"
hinweise: TBD
charakterzüge: |-
  draufgängerisch
  aufbrausend
ideale: will in die Fußstapfen seiner Mutter treten
makel: TBD
---
>[!metadata|metadata]- Metadata
>>[!metadata|metadataoption]- Tags
>> `INPUT[Tags][inlineListSuggester:tags]`
>
>>[!metadata|metadataoption]- Bild
>>`INPUT[imageSuggester(optionQuery("")):bild]`
>
>>[!metadata|metadataoption]- Bio
>>  |  
>>---|---
>**Ausgesprochen** | `INPUT[text:ausgesprochen]`
>**Alias** | `INPUT[inlineList:alias]`
>**Beruf** | `INPUT[Beruf][inlineListSuggester:beruf]`
>**Volk** | `INPUT[Volk][suggester:volk]`
>**Alter** | `INPUT[Alter][:alter]`
>**Geschlecht** | `INPUT[Geschlecht][:geschlecht]`
>**Sexualität** |  `INPUT[Sexualität][:sexualität]`
>**Heimat** | `INPUT[inlineListSuggester(optionQuery(#Region OR #Herrschaftsgebiet AND !"z_Vorlagen"), useLinks(partial)):heimat]`
>**Religion** | `INPUT[inlineListSuggester(optionQuery(#Religion OR #Gottheit  AND !"z_Vorlagen"), useLinks(partial)):religion]`
>**Gesinnung** | `INPUT[Gesinnung][:gesinnung]`
>**Sprachen** | `INPUT[Sprache][inlineListSuggester:sprache]`
>**Status** | `INPUT[Status][:status]`
>
>>[!metadata|metadataoption]- Info
>>  |  
>>  ---|---
>>  **Organisationen** | `INPUT[inlineListSuggester(optionQuery(#Organisation AND !"z_Vorlagen"), useLinks(partial)):organisation]`
>>  **Besitzer von** | `INPUT[inlineListSuggester(optionQuery(#Geschäft OR #InteressanterOrt  AND !"z_Vorlagen"), useLinks(partial)):eigentum]`
>>  **aktueller Aufenthaltsort** | `INPUT[inlineListSuggester(optionQuery(#Ort OR #InteressanterOrt AND !"z_Vorlagen"), useLinks(partial)):ort]`
>
>>[!metadata|metadataoption]- Beziehungen
>>  |  
>>  ---|---
>>  **Gruppen** | `INPUT[inlineListSuggester(optionQuery(#Gruppe AND !"z_Vorlagen"), useLinks(partial)):gruppe]`
>>  **Beziehung** | `INPUT[Beziehung][inlineListSuggester:beziehung]`
>>  **Familie** | `INPUT[inlineListSuggester(optionQuery(#Charakter AND !"z_Vorlagen"), useLinks(partial)):familie]`
>>    | `INPUT[textArea:familieText]`
>>  **Verbündete** | `INPUT[inlineListSuggester(optionQuery(#Charakter OR #Gruppe OR #Organisation AND !"z_Vorlagen"), useLinks(partial)):verbündete]`
>>  **Feinde** | `INPUT[inlineListSuggester(optionQuery(#Charakter OR #Gruppe OR #Organisation AND !"z_Vorlagen"), useLinks(partial)):feinde]`
>
>>[!metadata|metadataoption]- Überblick
>>  |  
>>  ---|---
>>  **Hinweise** | `INPUT[textArea:hinweise]`
>>  **Charakterzüge** | `INPUT[textArea:charakterzüge]`
>>  **Ideale** | `INPUT[textArea:ideale]`
>>  **Makel** | `INPUT[textArea:makel]`


>[!infobox]+
># `=this.file.name`
>`VIEW[{ausgesprochen}][text]`
>`VIEW[!\[\[{bild}\]\]][text(renderMarkdown)]`
>
>###### Bio
>  |  
>  ---|---
>**Alias** | `VIEW[{alias}][text]`
>**Beruf** | `VIEW[{beruf}][text]`
>**Volk** | `VIEW[{volk}][text]`
>**Alter** | `VIEW[{alter}][text]`
>**Geschlecht** | `VIEW[{geschlecht}][text]`
>**Sexualität** |  `VIEW[{sexualität}][text]`
>**Heimat** | `VIEW[{heimat}][link]`
>**Religion** | `VIEW[{religion}][link]`
>**Gesinnung** | `VIEW[{gesinnung}][text]`
>**Sprachen** | `VIEW[{sprache}][text]`
>**Status** | `VIEW[{status}][text]`
>
>###### Info
>  |   
>  ---|---
>  **Organisationen** | `VIEW[{organisation}][link]`
>  **Besitzer von** | `VIEW[{eigentum}][link]`
>  **aktueller Aufenthaltsort** | `VIEW[{ort}][link]`
>
>###### Beziehungen
>  |   
>  ---|---
>  **Gruppen** | `VIEW[{gruppe}][link]`
>  **Beziehung** | `VIEW[{beziehung}][text]`
>  **Familie** | `VIEW[{familie}][link]`
>    | `VIEW[{familieText}][text]`
>  **Verbündete** | `VIEW[{verbündete}][link]`
>  **Feinde** | `VIEW[{feinde}][link]`


## Überblick
> [!column|2 no-title]
>
>> [!metadata|angewohnheiten] Hinweise
>> `VIEW[{hinweise}][text]`
>
>> [!metadata|angewohnheiten] Charakterzüge
>> `VIEW[{charakterzüge}][text]`
>
>> [!metadata|ideals] Ideale
>> `VIEW[{ideale}][text]`
> 
>> [!metadata|makel] Makel
>> `VIEW[{makel}][text]`

Riven ist [[Kendra|Kendras]] Freund und Teil der [[Sturmwache]]. Zudem ist er der beste Freund von [[Silas Eisenhammer|Silas]].
- wohnt alleine seit seine Großmutter vor 2 Jahren verstorben ist
- seine Mutter kommt in unregelmäßigen Abständen vorbei und gibt ihm Geld
	- die Mutter reist viel durch die Gegend und schmuggelt Waren von einem Ort zum nächsten
	- es ist sein großes Ziel sie eines Tages zu begleiten
- seinen Vater kennt er nicht

## Aussehen


## Beziehung zur Gruppe
### Gruppe


## Ziele


## Quests
- [ ] 

## Geschichte


## Notizen


## Stats

```statblock
layout: Basic 5e Layout
name: Riven
size: medium
type: humanoid
subtype: Halfelf
alignment: chaotic neutral
ac: 15 (studded leather armor)
hp: 15
hit_dice: 1d8, 1d6
speed: 30ft.
stats: [8, 16, 14, 10, 10, 16]
saves:
  - Dexterity: 5
  - Intelligence: 2
skillsaves:
  - Thieves tools: 7
  - Sleight of Hand: 7
  - Stealth: 5
  - Insight: 2
  - Deception: 5
damage_vulnerabilities: 
damage_resistances: lightning
damage_immunities: 
condition_immunities: 
senses: pass. Perception 10, darkvisio 60ft.
languages: Common, Thieves Cant, Elven, Primordial
cr: 1/4
spells:
  - Riven is a level 1 Sorcerer. His spellcasting attribute is charisma (spellsave DC 13, +5 to hit with spell attacks). He has the following spells prepared
  - Cantrips: dancing light, mage hand, mending, ray of frost, gust
  - Level 1 (2 Slots): disguise self, thunderwave, feather fall, fog cloud
traits:
  - name: Sneak attack
    desc: Riven deals an extra 7 (2d6) damage when it hits a target with a weapon attack and has advantage on the attack roll, or when the target is within 5 feet of an ally of the spy that isn't incapacitated and the he doesn't have disadvantage on the attack roll.
  - name: Fey ancestry
    desc: You have advantage on saving throws against being charmed, and magic can't put you to sleep.
actions:
  - name: Dagger
    desc: +5 to hit, reach 20/60ft, Hit 6 (1d4 + 3) piercing damage
  - name: Short Bow
    desc: +5 to hit, reach 80/320ft, Hit 7 (1d6 + 3) piercing damage
bonus_actions:
  - name: Tempestuous Magic
    desc: You can cause a whirling gust of elemental air to briefly surround you, immediatly before or after you cast a spell of 1st level or higher. Doing so allows you to fly up to 10 feet without provoking opportunity attacks.
```