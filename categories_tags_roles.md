
# Thematic roles used in the study
The table below summarizes the thematic roles used in the description of argument structures (by ovák, A., Laki, L. J., Novák, B., Dömötör, A., Ligeti-Nagy, N., and Kalivoda, Á. (2019a). Creation of a corpus with semantic role labels for Hungarian. In A. Friedrich, D. Zeyrek, and J. Hoek (Eds.) Proceedings of the 13th Linguistic Annotation Workshop, LAW@ACL 2019, Florence, Italy, August 1, 2019, (pp. 220–229). Association for Computational Linguistics. URL: https://doi.org/10.18653/v1/w19-4026Ö. The first column shows the annotation itself. The second column contains the name of the given thematic role. The third column presents the typical question(s) of the given role. Finally, an example sentence is given in the fourth column, where the phrase with the given role is in bold.


| **Annotation** | **Name** | **Question regarding the verb** | **Example**  |
|---|---|---|---|
|	AG | agent | What is AG doing? | **John** has climbed the tree.  |
|	CHAR | characterised | What is characteristic of CHAR? | **Expertise** is an advantage.  |
|	ATTR | attribute | - | Expertise is **an advantage**.  |
|	EXP | experiencer | How does EXP feel? What has EXP perceived? | **John** has seen a swallow. |	
|	PAT | patient | What happened to PAT? | John kissed **Mary**.  |
|	PATDST  | patient-destination | What happened to PAT.to?  Where did PAT get to?  | He painted **the wall** green.  |
|	TH | theme | - | John relies **on his intuition**.  |
|	ST | stimulus | What effect has ST (on EXP)? | John loves **Mary**.|
|	CONT | information content | - | John presented **the plan** to Joe.  |
|	REC | recipient | - | John presented the plan **to Joe**.   **Mary** received a letter.  |
|	RES | result | How did RES come into being? | Mary baked **a cake**.  |
|	INS | instrument | What is AG using INS for? | John travels to work **by scooter**.  |
|	CAU | causer | What did CAU cause? What was the consequence of CAU?| John was late **because of an accident**.  |
|	MOT | motivation | - | John is studying to be **an engineer**.  |
|	LOC | location | What happened in/at/on... LOC? | John kissed Mary **in the cinema**.  |
|	SRC | source, starting point | - | John came **out of the room**.  Mary received a letter **from John**. |
|	DST | destination | How did AG/PAT get to DST? | John went **into the room**.  |
|	HOW | mode | - | John **deftly** climbed the tree.  |
|	ASPECT | aspect | - | John is doing well **financially**.  |
|	ACT | action | - | John wants **to work** from home.  |

# Categories and thematic roles 
This table summarizes the categories of locative adverbials and their possible thematic roles with the given suffixes. The cells indicate what thematic role the members of a given category can take with the given suffix. LOC-T, DST-T are the time adverbial pairs of LOC and DST answering the question When? and For when?, respectively. *bAn*, *bA*, *nÁl* etc. as a cell content indicates that the given category with the given suffix does not have a specific thematic role but answers the questions *Mi-ben?* ’What-Ine’, *Mibe?* ’What-Ill’, etc. If this suffix follows a tag (e.g. *WHO-bAn*), then the tag marks the proper wh-question that has to be used (e.g. *Ki-ben?* ’WHO-Ine’). Examples are: DEM: demonstrative role (Which?); QUANT: quantifiers with the possible questions ’How many?’, ’How much?’; FORM: describing some formal properties of the given act; CITY and LAND are tags for names of cities and countries. Any other tag not part of the above table is a novel proposal. CIRC: describing the circumstances of a given event; DIR: specifying the direction of a given act; MATER: describing the material of the thing in question; STA: giving information about the state of a participant; NUM_SIZE: a numeral denoting a (relative or absolute) size of something; SITU: specifying a situation that is the result or the source of a given action.

| category   |          | case_endings |              |             |             |              |             |              |              |              |
|------------|----------|--------------|--------------|-------------|-------------|--------------|-------------|--------------|--------------|--------------|
| main       | suppl    | bAn          | nÁl          | On          | bA          | hOz          | rA          | bÓl          | tÓl          | rÓl          |
| body       | ine-sup  | LOC          | NAL          | LOC         | DST         | HOZ          | DST         | SRC          | TOL          | SRC          |
| body       | all      | LOC          | LOC          | LOC         | DST         | DST          | DST         | SRC          | SRC          | SRC          |
| build=inst | sup      | BAN          | LOC          | LOC         | BA          | DST          | DST         | BOL          | SRC-WHO/SRC  | SRC          |
| cause      |          | CAU          | CAU          | CAU         | CAU         | CAU          | CAU         | CAU          | CAU          | CAU          |
| circumst   |          | CIRC         | CIRC         | CIRC        | SITU-BA     | CIRC-HOZ     | SITU-RA     | SITU-BOL     | SITU-TOL     | SITU-ROL     |
| curr       |          | BAN          | QUANT-NAL    | hány_On     | QUANT-BA    | HOZ          | QUANT-RA    | QUANT-BOL    | QUANT-TOL    | QUANT-ROL    |
| date       | sup      | BAN          | NAL          | LOC-T       | BA          | HOZ          | DST-T       | BOL          | SRC-T        | ROL          |
| date       | ine      | LOC-T        | NAL          | ON          | BA          | HOZ          | DST-T       | BOL          | SRC-T        | ROL          |
| dem        |          | DEM-BAN      | DEM-NAL      | DEM-ON      | DEM-BA      | DEM-HOZ      | DEM-RA      | DEM-BOL      | DEM-TOL      | DEM-ROL      |
| dempron    |          | DEM-BAN      | DEM-NAL      | DEM-ON      | DEM-BA      | DEM-HOZ      | DEM-RA      | DEM-BOL      | DEM-TOL      | DEM-ROL      |
| direct     | ine      | DIR          | NAL          | ON          | DIR         | HOZ          | RA          | SRC          | TOL          | ROL          |
| direct     | sup      | BAN          | NAL          | LOC/DIR     | BA          | HOZ          | DIR         | BOL          | TOL          | SRC          |
| event      | ade-sup  | BAN          | LOC-T/LOC    | LOC-T/LOC   | BA          | DST          | DST/DST-T   | BOL          | SRC/SRC-T    | SRC          |
| event      | sup      | BAN          | NAL          | LOC-T/LOC   | BA          | HOZ          | DST/DST-T   | DST/DST-T    | TOL          | ROL          |
| event      | ine      | LOC-T/LOC    | LOC-T/LOC    | ON          | DST         | DST          | mire/DST-T  | SRC          | SRC/SRC-T    | ROL          |
| build=inst | ine      | LOC          | LOC          | ON          | DST         | DST          | RA          | SRC          | SRC-WHO/SRC  | ROL          |
| form       | ine      | FORM-BAN     | NAL          | ON          | FORM-BA     | HOZ          | RA          | FORM-BOL     | TOL          | ROL          |
| form       | sup      | BAN          | NAL          | FORM-BAN    | BA          | HOZ          | DST         | BOL          | TOL          | SRC          |
| group      |          | LOC          | LOC          | kiken       | DST         | DST          | kikre       | SRC          | SRC          | kikről       |
| loc        | ade      | BAN          | LOC          | ON          | BA          | DST          | RA          | BOL          | SRC          | miről        |
| loc        | all      | LOC          | LOC          | LOC         | DST         | DST          | DST         | SRC          | SRC          | SRC          |
| loc        | ine      | LOC          | NAL          | ON          | DST         | HOZ          | RA          | SRC          | TOL          | miről        |
| loc        | sup      | BAN          | NAL          | LOC         | BA          | HOZ          | DST         | BOL          | TOL          | SRC          |
| loc        | ine-sup  | LOC          | NAL          | LOC         | DST         | HOZ          | DST         | SRC          | TOL          | SRC          |
| loc        | city-ine | LOC          | LOC          | CITY-ON     | DST         | DST/DST-WHO  | CITY-RA     | SRC          | SRC/SRC-WHO  | CITY-ROL     |
| loc        | city-sup | CITY-BAN     | LOC          | LOC         | CITY-BA     | DST/DST-WHO  | DST         | CITY-BOL     | SRC/SRC-WHO  | SRC          |
| loc        | country  | LOC          | LOC          | LAND-ON     | DST         | DST/DST-WHO  | DST/LAND-RA | SRC          | SRC/SRC-WHO  | LAND-ROL     |
| loc=who    |          | LOC          | LOC/LOC-WHO  | WHO-ON      | DST         | DST/DST-WHO  | WHO-RA      | SRC          | SRC-WHO/SRC  | WHO-ROL      |
| material   |          | BAN          | NAL          | ON          | BA          | HOZ          | RA          | MATER        | TOL          | ROL          |
| meas       |          | QUANT-BAN    | QUANT-NAL    | QUANT-ON    | QUANT-BA    | QUANT-HOZ    | QUANT-RA    | QUANT-BOL    | QUANT-TOL    | QUANT-ROL    |
| mode       | sup      | BAN          | NAL          | HOW         | BA          | HOZ          | HOW         | HOW          | TOL          | ROL          |
| mode       | ine      | HOW          | NAL          | ON          | BA          | HOZ          | HOW         | HOW          | TOL          | ROL          |
| num        |          | QUANT-BAN    | QUANT-NAL    | QUANT-ON    | QUANT-BA    | QUANT-HOZ    | QUANT-RA    | QUANT-BOL    | QUANT-TOL    | QUANT-ROL    |
| num2       |          | QUANT-BAN    | QUANT-NAL    | QUANT-ON    | QUANT-BA    | QUANT-HOZ    | NUM-SIZE-RA | QUANT-BOL    | QUANT-TOL    | NUM-SIZE-ROL |
| org        | ine      | LOC          | LOC          | ON          | DST         | DST          | RA          | SRC          | SRC          | ROL          |
| org        | ade      | BAN          | LOC          | ON          | BA          | DST          | RA          | BOL          | SRC          | ROL          |
| org=who    | all      | LOC          | LOC          | LOC         | DST         | DST          | DST         | SRC          | SRC/SRC-WHO  | SRC          |
| org=who    | sup      | WHO-BAN      | LOC          | LOC         | WHO-BA      | DST/DST-WHO  | DST         | WHO-BOL      | SRC/SRC-WHO  | SRC          |
| org=who    | ine      | LOC          | LOC          | WHO-ON      | DST         | DST/DST-WHO  | WHO-RA/RA   | SRC          | SRC/SRC-WHO  | WHO-ROL/ROL  |
| org=who    | ade      | WHO-BAN      | LOC          | WHO-ON      | WHO-BA      | DST/DST-WHO  | WHO-RA      | WHO-BOL      | SRC/SRC-WHO  | WHO-ROL      |
| part       |          | LOC/PART-BAN | LOC/PART-NAL | LOC/PART-ON | DST/PART-BA | DST/PART-HOZ | DST/PART-RA | SRC/PART-BOL | SRC/PART-TOL | SRC/PART-ROL |
| period     |          | LOC-T        | NAL          | ON          | BA          | HOZ          | HOW-LONG    | BOL          | SRC-T        | ROL          |
| place      | ine      | LOC          | LOC          | ON          | DST         | DST          | RA          | SRC          | SRC          | miről        |
| place      | sup      | BAN          | LOC          | LOC         | BA          | DST          | DST         | BOL          | SRC          | SRC          |
| way        |          | BAN          | LOC          | LOC         | BA          | DST          | DST         | BOL          | SRC          | SRC          |
| posi       | sup      | BAN          | NAL          | LOC         | BA          | HOZ          | DST         | BOL          | TOL          | SRC          |
| posi       | ine      | LOC          | NAL          | ON          | DST         | HOZ          | DST/RA      | SRC          | TOL          | ROL          |
| pov        |          | POV          | NAL          | ON          | BA          | HOZ          | RA          | POV          | TOL          | ROL          |
| state      |          | STA-BAN      | LOC-T        | ON          | STA-BA      | HOZ          | RA          | STA-BOL      | TOL          | ROL          |
| thing      |          | BAN          | NAL          | ON          | BA          | HOZ          | RA          | BOL          | TOL          | ROL          |
| who        |          | WHO-BAN      | LOC-WHO      | WHO-ON      | WHO-BA      | DST-WHO      | WHO-RA      | WHO-BOL      | SRC-WHO      | WHO-ROL      |
