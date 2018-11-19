# anova-for-attachment-ambiguity-data

The goal of this project was to develop an ANOVA from scratch and compare it's results to that of the built in ANOVA function in R, aov(). The data used are from Logachev & Vasishth (2015) and can be found in the file logachevVasishth2015CogSci.csv. The data set contains reading times from a self-paced reading study run in German which was designed to test for the “ambiguity advantage,” in which a sentence like (iii) in which attachment is ambiguous is parsed faster than related unambiguous sentences like (i) and (ii): 

The driver of the car that had a moustache was pretty cool. (high attachment)
The car of the driver that had a moustache was pretty cool. (low attachment)
The son of the driver that had a moustache was pretty cool. (ambiguous: both high and low attachment are possible.)

The 6 types of sentences used as stimuli are as follows:

“a”: both nouns are feminine in grammatical gender, and the relative pronoun is also feminine, so the relative clause could attach high or low, i.e. attachment is ambiguous,

“b”: first noun fem., second masc., rel. pro. masc.: unambiguous low,

“c”: first noun fem., second masc., rel. pro. fem.: unambiguous high,

“d”: first noun masc., second masc., rel. pro. masc.: ambiguous,

“e”: first noun masc., second fem., rel. pro. fem.: unambiguous low,

“f”: first noun masc., second fem., rel. pro. masc.: unambiguous high.
