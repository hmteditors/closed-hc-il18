# Iliadic multiforms  in the Venetus A scholia #



Brian Clark, Claude Hanley, Stephanie Lindeborg, Stephanie Neville,

Charlie Schufreider, Alex Simrell, Melody Wauke

___

## Research Question

- Multiformity in the *Iliad*, and "the Homeric Question"
-  Present in the scholia
- Not evident in Erbse or Dindorf
- an "Alexandrian apparatus criticus"


___



##Broader context: text reuse##


Monica Berti: *text reuse* is

>the meaningful reiteration of text, usually beyond the simple repetition of common language
    

Sources for text reuse:

- literal quotation of extant or lost works
- paraphrase

___

## Method

1. Automatically extract quoted with citations (TBA)
2. Automatically extraction quoted material without citations:
    - Close reading of the scholia
    - Analysis recorded in simple `.csv` file
    - Classification into six categories


___

#Specific Examples of Categories#
___


## 1. Quotation from an extant text ##



Text quotes Iliadic line that the scholion is commenting on


E.g., scholion commenting on 18.101-18.114:

>αἱ ὑποστιγμαὶ δὲ μέχρι τοῦ "αμείνονές εἰσὶ καὶ ἄλλοι" ἀποτελοῦνται τοῦ  ἐπεὶ συνδέσμου τὸν λογον ρτῶντος ἵν' ᾗ ἀνταπόδοσις.

___

## 2. Quotation from a text that is no longer extant ##



Main scholion to *Iliad* 18.521, lemma: "αρδμος"

Quotes Cratinus to show that alpha is short: "'πισσοκονίας ἀρὴν' Κρατῖνος"


___

## 3. Quotation of hypothetical speech or text 'contrafactual quotation'

- *Iliad* 18.250: Πανθοίδης. ὃ γὰρ οἶος ὅρα πρόσσω καὶ ὀπίσσω· 

Scholion:

>τέλειον ἐγκώμιον τοῦ φρονίμου τὰ δὲ ἐναντια ἐπι τοῦ ἄφρονος 
> "οὐδέ τι οἶδε νοῆσαι ἅμα πρόσσω καὶ οπίσσω"


___


## 4. Example of usage quoted from a native speaker's knowledge of the language

*Iliad* 18.501: "ἄμφω δ᾽ ἱέσθην ἐπὶ ἴστορι πεῖραρ ἑλέσθαι."

Scholion on the line:

"ἀπο τοῦ 'είδω' 'εἴσω'. 'ἵστωρ' ἐλλείψαντος τοῦ ε ἐπεὶ τῷ ϊ τὸ στ ἐπεφέρετο ὡς ἐν τῷ 'ἱστῷ' 'ἱστίον' 'ἵστημι'"

___

## 5.Direct quotation of a multiform for a given passage

*Iliad* 18.230-231:

>ἔνθα δὲ καὶ τότ᾽ ὄλοντο δυώδεκα φῶτες ἄριστοι
>/ ἀμφὶ σφοῖς ὀχέεσσι καὶ ἔγχεσιν 

Scholion on that line: 

>ἡ διπλῆ ὅτι Ζηνόδοτος γράφει "ἔνθα δε κοῦροι ὄλοντο δυώδεκα πάντες ἄριστοι / οἷσιν ἐν βελέεσσιν"


___

## 6. Apparent multiform, not explicitly identified in the text of the scholion ##


- Lemma of the scholion does not align with the VA text
- (Can be automatically extracted when validation completed)


___


## Sample we studied:  all scholia to *Iliad* 18



- 617 lines of the *Iliad*
- 25 pages of the Venetus A
- total scholia: 399
- words in text of scholia: more than 9400


___


## Breakdown by type of scholion ##



Main scholia: 217 

Intermarginal scholia: 78 

Interlinear scholia: 38 

Interior scholia: 55 

Exterior scholia: 11 


___


## Breakdown by class of reuse

(To be added: "apparent multiforms" from lemmata to main scholia and attributed citations [TEI `cit`])


Direct quote: 86 

Lost work: 5 

Hypothetical: 4 

Language usage: 109 

Multiform: 87 


---


## A "tenth-century critical apparatus" ##


(Link to or pull up HTML page)

---

## Are citations of multiforms and citations of Alexandrian scholars connected?

---

## chi square test for independence ##

1. compares two sets of categorical data (minimum of 5 occurrences in cross-tabulation cells)
3. starts from *null hypothesis* : the two sets of data are *independent*
4. *p-value* measures  probability of randomly getting the observed data.  E.g., 0.01 means you would expect this set of values only 1 time in a 100.



|  | Name absent | Name present |  Totals  
|  ------	| ------	| ------	| ------	|  
| Multiform absent |  536 |  16 |  **552** |
| Multiform present |  30 |   34 |  **64** |
| Total | **566** | **50** | 616 |



---

## Meaning of chi square test ##


1. Define a *significance level* (e.g., 0.01 means you consider it significant if the observed data would not show up randomly in more than 1/100 trials)
2. If *p* &lt; significance level, reject the null hypothesis:  conclude that the two sets of data are **not** independent (i.e., the are correlated)



___

## Results ##


- *p* value = 1.2 *10 <sup>-42</sup> decimal places
- -> There is a correlation between the occurrence of a multiform and references to one of the three Alexandrian grammarians 
     - Aristophanes, Aristarchus, or Zenodotus




----

## Provisional interpretations ##


- multiforms are discussed together with citation of Alexandrian editors
- does this support the suggestion that the Alexandrian editions fixed the range of multiforms we see in the scholia?
- despite the range of topics we find in the scholia, the Alexandrians are cited in contexts dealing with multiforms

___

## Avenues for Future Analysis

- Evaluate the strength of the correlation between multiforms and mentions of the Alexandrian editors
     - Research the connection between the multiforms and the Alexandrian editors
- Broaden the sample size by adding text reuse analyses of other Iliadic books
- Look at the lemmata to analyze "apparent" or "implied multiforms" 
- Investigate the connection between ὅτι scholia and Aristarchean critical signs

___
