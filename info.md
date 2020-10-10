---
layout: default
title: info
---
# Latin Noun Trainer (Part of [Res Latinae](https://danelh.github.io/))

## Table of Contents

- [Intro](#intro)
- [The Nouns](#the-nouns)
- [Noun Selection](#noun-selection)
- [Level](#level)
  * [frequency](#frequency)
- [Inflection selection](#inflection-selection)
- [Missing mutations](#missing-mutations)
- [Practice and exam modes](#practice-and-exam-modes)
- [Save session's parameters](#save-sessions-parameters)
- [Contact information](#contact-information)

## Intro 
This trainer was created mainly to allow the user to practice Latin nouns inflections. Each inflection (or mutation as reffered in this Trainer) consists of the noun-root and the tense-inflection. The user is given a mutation and is required to inflect it. For example for the noun "_amo_" and "_indicative active present 1st plural_", the correct inflection is _amamus_.

The correct answers were taken from Wiktionary. In several cases there is more than one attested option for inflection. For example, according to Wiktionary for "[_navis_](https://en.wiktionary.org/wiki/navis#Latin)" and "_acc_p_" there are two options: _naves_ and _navis_. The Trainer supports both options from the user. 

## The Nouns

The Trainer uses 12856 nouns from wiktionary. This is by no means the attested number of Latin nouns; yet, a noun missing from the Trainer is probably quite rare.

With respect to the gender, **there might be errors** (for example in _folia_), and in many other nouns gender is missing for no apparent reason. so when using gender feature take it with grain of salt.

## Noun Selection
There are 3 ways to select noun to practice on:

 1. **Manual selection from list**:  in the list you can search for your nouns from the Trainer list, and select them.  Selecting a noun from the list, will append it to already selected nouns displayed in the box. 
 2. **Writing directly in the nouns box**:  it is possible to write the nouns directly in the selected-nouns box. Make sure to have the nouns comma separated.  This option is recommended only in cases you have predefined list of nouns - for example when you saved the nouns from previous session - you can simply paste them in the box. **In this way you can load your nouns easily**. [Note that you may enter a noun which will be ultimately removed from the Trainer if it's missing from the list:  _volo_ , for example, will be removed because it is missing from the list - Trainer expected _volo(first)_ or _volo(irregular)_ .
3. **Automatic generator**: you can tell the Trainer to automatically generate nouns. To use this option you should specify 1) how many nouns you want to be generated 2) the level. Then you should click "Generate". The generated nouns will override  the current selected nouns.

## Level

In order to use the automatic generator, you have to specify a  _level_ . The _level_ parameter basically tells the automatic generator which nouns are entitled to be generated.  The goal of this parameter is to generate nouns that the user is likely to be familiar with, rather than complete random nouns from the list. To achieve this, the nouns were sorted by **frequency** . Thus, selecting "Top 10%" option means that the nouns will be generated from 10% of the nouns which are the most frequent (pool of 1250 nouns). The beginner may find this tool helpful for increasing his vocabulary of frequent nouns.   

### frequency

The nouns were sorted by frequency using the [Perseus Vocabulary Tool's](http://www.perseus.tufts.edu/hopper/vocablist?lang=la) _weighted frequency_ attribute. the documents pool contained docs of prominent authors ([full list](docs_names.txt)).In terms of frequency, the Trainer does not distinguish between differnt nouns of the same root like _volo(irregular)_ and _volo(first)_: they both have the same frequency for the Trainer. (the highest of the two).

## Inflection selection

Inflection selection is quite straight-forward. It should be noted, however, that the inflections which regularly  use the _perfect passive participle_ (such as _indicative passive perfect_), are missing from the Trainer for all nouns, and can't be selected. To practice those, you can use the participle itself. 
You can select more than one inflection.

## Missing mutations

Many nouns cannot be inflected in all forms. The noun [_moenia_](https://en.wiktionary.org/wiki/moenia#Latin), for example, is missing singular.

In case a noun was selected, which is not in the Trainer list, it will be noted in the window. It can happen either when the noun is simply not existing in the Wiktionary, or that Trainer [expects parentheses](#the-nouns) for this noun.

## Practice and exam modes

The Trainer has two modes of operation: practice or exam. The two modes are similiar in nature: in both the user is given mutation and required to inflect it correctly. The user should submit his answer by pressing Enter key. After an answer was submitted, the Trainer will indicate the user wheather he was correct. When the user is correct, the correct answer will be displayed in green, else the correct answer will be in red. Moreover, at the right side, the user can see his stats so far, as well as the "mutations left" which indicate the number of different mutations that might be displayed to show the user how far he is from completing the practice or the exam. To change mode, the user should click on the mode switch.

In **practice mode**, the mutation in question is selected semi-randomally (bias towards mutations the user was wrong in recently). In this mode a given mutation might be asked many times without limit; thus, theoritically, the practice might last ad infinitum. **It is under the user responsibity to prevent a mutation from being asked again**: to do so, instead of submitting an answer, he should press the right arrow key (→). After pressing (→) the user should see appropiate message, and the number of "mutations left" (in the right side) going down. The user is adviced to do so when he is sure of the correct answer (The Trainer will tell the user to consider pressing (→) after he was right three times in a row, yet the final descision is always under the user discretion: he might do so before or after that). Ideally, the practice will end when the user pressed (→) to all the mutations, but the user might switch to exam mode or select other nouns/inflection any time he wishes. The user is encouraged, especially in this mode, to click on the noun in question when he is unsure of the meaning of the noun or want to see the full conjugation table.

**Exam mode** should be used when the user feels confident about the inflections of the selected nouns, and he wants to test his level. In this mode every mutaion is asked only once (no need to press (→). At the end of the exam the user wil see his final score.


## Save session's parameters

Selecting the inflections and auto nouns-generation settings might be tedious, especially when we are using them for long.  In order to avoid re-selection of those parameters each time we open the Trainer,  the selected parameters are saved in address bar of the browser. Every change of the selected inflections or every click on "generate" button, will trigger a change in the address bar that will contain the newly-selected parameters. If you want to save the settings, simply copy the line of the address bar and save it for future use. When you use that link, the Trainer will be opened with the selected parameters, and with the nouns already generated - so you can start practice right away.

If you want to save the nouns themselves (rather than the nouns-generation parameters), you should copy the text in the [nouns box](#noun-selection), and save this text for future use. To use the saved list, you have to paste it in the nouns box.

## Contact information 

[See here](https://danelh.github.io/about)
