# From oral tradition to written text
## New evidence from a 10<sup>th</sup> century manuscript



Brian Clark, Claude Hanley, Stephanie Lindeborg, Stephanie Neville,

Charlie Schufreider, Alex Simrell, Melody Wauke

___


# Homer Multitext project#

>seeks to present the Homeric poems in a framework that reflects the oral tradition in which they were composed 

***

#Manuscripts of the HMT#

- Venetus A (10th Century CE)
- Venetus B (11th Century CE)
- Escorial Υ.I.1 (11th Century CE)
- Escorial Ω.I.12 (11th Century CE)
- Marciana 841 (12th/13th Century CE)
- Genavensis 44 (13th Century CE)

***

#The Venetus A Manuscript (*Marcianus Graecus* 822 = Z. 454)#


[Folio 12r of the Venetus A][f12r]


[f12r]: http://www.homermultitext.org/hmt-digital/indices?urn=urn%3Acite%3Ahmt%3Avaimg.VA012RN-0013

------

## Scholia's impact on scholarship ##

- Full of multiformity: Where do they come from? Is there even a Homer?
  - Wolf's *Prolegomena* (1795): Started modern debate
  - HMT: Evidence of a richer oral tradition
- Scholia largely attributed to three Alexandrian editors

___

## Editors at the Library of Alexandria##

*Zenodotus of Ephesus, Aristophanes of Byzantium and Aristarchus of Samothrace*

- 3rd to 2nd century BC
- responsible for editing the Homeric texts
- coincide with the reduction of various multiforms


---

## Research Question

- How do we edit and read multiforms in the scholia to the *Iliad*?
- Never completely published!
- Can we create an "Alexandrian critical apparatus"?



___


##Broader context: text reuse##


Monica Berti: *text reuse* is

>the meaningful reiteration of text, usually beyond the simple repetition of common language
    

Sources for text reuse:

- literal quotation of extant or lost works
- paraphrase

___

## Method

1. Automatically extract quoted with citations
2. Automatically extraction quoted material without citations:
    - Close reading of the scholia
    - Analysis recorded in simple `.csv` file
    - Classification into categories


-----

##Categories##

   - Direct quote from the *Iliad* line
   - Quote from a no longer extant source
   - Quotation of hypothetical speech or "contrafactual quotation"
   - Phrase quoted from native speaker's knowledge of the language
   - Multiform

___



## Direct quotation of a multiform for a given passage

*Iliad* 18.230-231:

>ἔνθα δὲ καὶ τότ᾽ ὄλοντο δυώδεκα φῶτες ἄριστοι / ἀμφὶ σφοῖς ὀχέεσσι καὶ ἔγχεσιν 

Translation:

>And there at that time the twelve best men died / by both their chariots and spears
___

Scholion for 18.230-231: 

>ἡ διπλῆ ὅτι Ζηνόδοτος γράφει "ἔνθα δε κοῦροι ὄλοντο δυώδεκα πάντες ἄριστοι / οἷσιν ἐν βελέεσσιν"

Translation:

>The diple is here because Zenodotus writes, "And there all twelve of the best boys died / among their missiles"


___


## First sample we studied:  all scholia to *Iliad* 18

- 616 lines of the *Iliad*
- 25 pages of the Venetus A
- total scholia: 399
- words in text of scholia: ca. 9500 


___


## Breakdown by class of reuse



Direct quote: 180 (58 direct quotes of other *Iliad* passages)

Lost work: 4 

Hypothetical: 2

Language usage: 123 

Multiform: 93 


---


## A "tenth-century critical apparatus" ##


See an [HTML display](../venA/stats/iliad-18-mt.html)

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
2. If *p* &lt; significance level, reject the null hypothesis:  conclude that the two sets of data are **not** independent (i.e., they are correlated)



___

## Results ##


- *p* value = 1.2 *10 <sup>-42</sup> 
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


## From Alexandria -> digital HMT

- The Alexandrian editors recorded variety of the Homeric poems: 3<sup>rd</sup>-2<sup>nd</sup> century BC
- The scribe of the Venetus A compiled his edition with scholia: 10<sup>th</sup> century
- HMT editors are creating our editions of these texts: 21<sup>st</sup> century


----

# Thank you!

-------------
