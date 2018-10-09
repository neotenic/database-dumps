# Protobowl Database Dumps

Here's an example of what the JSON files look like. Each line represents a different question

```
{"category":"Science","subcategory":"Chemistry","difficulty":"College","tournament":"ACF Winter","question":"Performing \"electro-deoxidation\" on an oxide of this metal may be able to improve on the current method of producing it and is called the Fray-Farthing-Chen Process. Along with a heavier element, extremely pure varieties of this element can be produced in the crystal bar process. When this element is combined with two oxygen molecules it yields a compound that produces the asterism in star sapphires, rutile. One method for producing the metallic form of this element yields a \"sponge\" form of it and replaced the Hunter Process; the creator of that method also devised a way to produce the chemically similar element, Zirconium. This transition metal is extracted in the Kroll process. For 10 points, name this strong, lightweight element with atomic number 22 and symbol Ti.","source":"acfdb","num":8,"year":2010,"answer":" Titanium [or Ti before read]","seen":59,"type":"qb","round":"Bellevue and Lawrence"}
{"category":"History","subcategory":"European","difficulty":"College","tournament":"ACF Winter","question":"This period ended after the failure of the Dyle Plan. Early in its history, the Opportunists held sway over its government. One political party active during this period staged an unsuccessful coup against Felix Faure and demanded the government renegotiate the Treaty of Frankfurt. Besides problems with the right-wing League of Patriots, it was rocked by the 16th of May Crisis when its president installed the Legitimist Duc de Broglie as Prime Minister. The Jules Ferry laws provided for free public education during this period. During it the Panama Scandal occurred. Its first president was Adolphe Thiers, and this government also endured the Dreyfus Affair. It was replaced by Vichy France. For 10 points, identify this French government that succeeded the Second Empire.","source":"acfdb","num":9,"year":2010,"answer":"French {Third} Republic","seen":60,"type":"qb","round":"Bellevue and Lawrence"}
{"category":"Fine Arts","subcategory":"Music","difficulty":"College","tournament":"ACF Winter","question":"David Humphreys suggested that a “Cosmic Allegory” unifies this work, while Alan Street claims that it was written in defense of criticisms made by Johannes Scheibe. Its twenty-fifth section contains many chromatics and was nicknamed the “Black Pearl” by the person who recorded it first, while Jozef Koffler created an orchestral transcription for this work in 1938. Every third section in this work is a canon except the last, which contains two folk songs as a quodlibet. Revived by Wanda Landowski, it helped bring success to its 1955 performer, Glenn Gould. For 10 points, name this harpsichord collection consisting of an aria followed by thirty variations, published in 1741 by Johann Sebastian Bach.","source":"acfdb","num":10,"year":2010,"answer":"the Goldberg Variations","seen":66,"type":"qb","round":"Bellevue and Lawrence"}
```

The keys are:

- category (e.g. "Science")
- subcategory (e.g. "Chemistry")
- difficulty (e.g. "College")
- year: the year the packet was published
- source (e.g. "acfdb")
- tournament (e.g. "ACF Winter")
- round (e.g. "Bellevue and Lawrence")
- num: the index of the question in the packet
- question (e.g. ""Performing \"electro-deoxidation\" on an oxide of this metal may be able to improve on the current method of producing it and is called the Fray-Farthing-Chen Process....")
- answer: the answer to the question (bold text is indicated by wrapping it with curly braces) (e.g. " {Titanium} [or {Ti} before read]")
- type: this will almost always be "qb" for quizbowl questions
- seen: number of times this question has been seen at the date of the dump (e.g. 59)


