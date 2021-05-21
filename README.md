Hier entsteht das LRR file für die Schweizerisches

Aufbau:
* Primär werden Gerichte in der (dominanten) Sprache des jeweiligen Kantons inkludiert
* Für diese Gerichte werden Übersetzungen in den beiden jeweils anderen Amtssprachen (de, fr oder it) als ´variants´ angeboten.
* ´variants´ gibt es sowohl für Namen wie auch für Abkürzungen (bis jetzt nur ´ABBREV´s)

Anmerkungen:
* Bislang nicht inkludiert werden Behörden die durchaus Entscheidungsfunktion haben können (z.B. Regierungsdepartemente, Betreibungsämter, Staatsanwaltschaften), soweit diese Funktion nicht primäre Aufgabe der Behörden ist
* Es werden nur Gerichte (als eigenständige Organisationseinheit und damit Entscheidkörper), nicht aber einzelne Abteilungen oder Kammern dieser Gerichte aufgenommen. Dies kann zu einem späteren Zeitpunkt ergänzt werden, erscheint prima facie aber grösstenteils unnötig, da normalerweise nur das Gericht als ganzes zitiert wird.
* Die freiburgsche "Cellule judiciaire itinérante" wird anscheinend auch im Deutschen so bezeichnet. Es wird angenommen, dass dies wohl auch in der italienischen Praxis so wäre. Von eine Übersetzung wurde bislang abgesehen
* Die Kommissionen und das Schiedsgericht des Kantonsgerichts Appenzell-Innerrhoden könnten u.U. auch als eigene Gerichte aufgefasst werden, wurden bisher aber noch nicht inkludiert, da unklar ist, ob dies in Praxis auch so gehandhabt wird, oder, ob jeweils auch unter dem "Mantel" des Kantonsgerichts gehandelt wird
* Neuchâtel benutzt einzigartige Abkürzungen für ihre Gerichte. Da unklar ist, ob diese weitere Verbreitung haben, wurden sie nicht implementiert, da dann wohl nur für Neuchâtel eigene courts nur wegen den Abkürzungen geschaffen werden müssten. Es wird aber angenommen, dass diese Abkürzungen ausserhalb der eigenen Gerichtsorganisation nicht viel Verwendung finden.
* Generell hat Neuchâtel eine sehr eigene Art, die Entscheide ihrer Gerichte einzuordnen, die sehr schwer in JSON abzubilden ist. U.U. sollte dies später in Zusammenarbeit mit lokalen Experten abgeglichen werden.
* Die verschiedenen Schlichtungsstellen in öffentlich-rechtlichen Personalsachen des Kantons St. Gallen wurden vorerst weggelassen, da vermutlich sehr unwichtig für juristisches Schreiben.

Todo:
* Momentan ist mir unklar, inwiefern jurisdictions an die courts angefügt werden. Würde der court "Ordre des Avocats Jurassiens" der jurisdiction "Jura" als "Ordre des Avocats Jurassiens Jura" gerendert? Oder braucht es auch bei "name" ein "%s"?
