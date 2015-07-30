# Iliadic multiforms  in the Venetus A scholia #



Brian Clark, Claude Hanley, Stephanie Lindeborg, Stephanie Neville,

Charlie Schufreider, Alex Simrell, Melody Wauke

___


# Homer Multitext project#

>seeks to present the Homeric poems in a framework that reflects the oral tradition in which they were composed 

***

#Manuscripts of the HMT#

- Venetus A (10th Century CE)
- Venetus B (15th Century CE)
- Marciana 841 (12th/13th Century CE)
- Escorial Υ.I.1 (11th Century CE)
- Escorial Ω.I.12 (11th Century CE)
- Genavensis 44 (13th Century CE)

***

#The Venetus A Manuscript (*Marcianus Graecus* 822)#


[Folio 12r of the Venetus A](http://www.homermultitext.org/hmt-digital/ict.html?urn=urn:cite:hmt:vaimg.VA012RN-0013)

------

#Editing Process#

![XML of 12r][Img1]

[Img1]:  ScreenShot.png 

-----

## Research Question

- Multiformity in the *Iliad*, and "the Homeric Question"
     -  Present in the scholia
- Not evident in modern printed editions
- an "Alexandrian apparatus criticus"


___

##Alexandrian Editors##

*Aristarchus of Samothrace, Zenodotus of Ephesus, and Aristophanes of Byzantium*
- 3rd to 2nd century BC
- responsible for editing the Homeric texts
- coincide with the reduction of various multiforms

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


-----

##Categories##

     1. Direct quote from the Iliad line
     2. Quote from a no longer extant source
     3. Quotation of hypothetical speech or "contrafactual quotation"
     4. Phrase quoted from native speaker's knowledge of the language
     5. multiform

___



## Direct quotation of a multiform for a given passage

*Iliad* 18.230-231:

>ἔνθα δὲ καὶ τότ᾽ ὄλοντο δυώδεκα φῶτες ἄριστοι
>/ ἀμφὶ σφοῖς ὀχέεσσι καὶ ἔγχεσιν 

Scholion on that line: 

>ἡ διπλῆ ὅτι Ζηνόδοτος γράφει "ἔνθα δε κοῦροι ὄλοντο δυώδεκα πάντες ἄριστοι / οἷσιν ἐν βελέεσσιν"


___


## Sample we studied:  all scholia to *Iliad* 18 and 19

**need to update all these numbers**

- 1041 lines of the *Iliad*
- 43 pages of the Venetus A
- total scholia: 515
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




----

## Provisional interpretations ##


- Multiforms are discussed in conjunction with a citation of the Alexandrian editors 
- "Canonical Multiforms"
	- Earlier papyri reflect a more diverse tradition of multiforms
	- This implies that these multiforms fell out of use in texts in the Hellenistic period.
	- The association of the Alexandrians with the multiforms indicates that they were responsible for the multiforms which are attested to in the manuscript tradition.

___

## Avenues for Future Analysis

- Further research the connection between the multiforms and the Alexandrian editors
- Broaden the sample size by adding text reuse analyses of other Iliadic books
- Run statistical analysis on other trends we've noticed over the years

___


The End!

-------------

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


___

## 6. Apparent multiform, not explicitly identified in the text of the scholion ##


- Lemma of the scholion does not align with the VA text
- (Can be automatically extracted when validation completed)



