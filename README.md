     ________________
      (@^,^,^,^,^,@)
        )`){o}(`(
        ,`,`,`,`,`
        ==========
         ||||||||
         ||||||||
         ||||||||
         ||||||||
         ||||||||
         ||||||||
         ||||||||
        ,________,
          )    (
        ,       `
      _/__________\_
     |___________ejm|

# p_ILR
a "translation" of the "Interagency Language Roundtable" for *p*rogrammers, pronounced "Pillar"

## motivation
It is really hard to judge fluency in a language. Harder still to judge fluency in programming generally. This is an attempt at a scale for the former, easier problem. The intent is less a tool for hiring (as language specific skill probably *shouldn't* be our metric) but for learning and leveling in a *skill guild*.

The scale is modeled on [ILR Scale](https://en.wikipedia.org/wiki/ILR_scale):
> a set of descriptions of abilities to communicate in a language. It is the standard grading scale for language proficiency in the Federal service. It was originally developed by the Interagency Language Roundtable (ILR), which included representation by United States Foreign Service Institute, the predecessor of the National Foreign Affairs Training Center (NFATC).

The ILR scale is as compared against the "native speaker". For this interpretation, who is this "native speaker?" We roughly claim the "native speaker" is the primary or foundational author of a language or its key compiler/interpreter (in other words, the computer as a native speaker).

## the p_ILR
- [p_ILR Level 0](#p_ilr-level-0) – No proficiency
- [p_ILR Level 1](#p_ilr-level-1) – Elementary proficiency
- [p_ILR Level 2](#p_ilr-level-2) – Limited working proficiency
- [p_ILR Level 3](#p_ilr-level-3) – Professional working proficiency
- [p_ILR Level 4](#p_ilr-level-4) – Full professional proficiency
- [p_ILR Level 5](#p_ilr-level-5) – Core requirements author or contributor

## p_ILR Level 0
The baseline level of the scale is no proficiency, rated 0. The following describes the traits of an ILR Level 0 individual:
> oral production limited to occasional, isolated words

Workflow often looks like: `Google -> StackOverflow -> cmd + c -> cmd + v`

> may be able to ask questions or make statements with reasonable accuracy only with memorized utterances or formulae
> understanding limited to occasional isolated words or memorized utterances in areas of immediate needs.
> may be able to produce symbols in an alphabetic or syllabic writing system or 50 of the most common characters

Knows an isolated, common slice of the core API. For instance, someone who can use jQuery selectors in the web console, but doesn't otherwise know any JavaScript.

> unable to read connected prose but may be able to read numbers, isolated words and phrases, personal and place names, street signs, office and shop designations

Has some rough sense of the syntax sufficient to determine keywords. May be able to recognize statement flow, functions, variables.

## p_ILR Level 1
Elementary proficiency is rated 1 on the scale. The following describes the traits of an ILR Level 1 individual:
> can fulfill travelling needs and conduct themselves in a polite manner
> able to use questions and answers for simple topics within a limited level of experience

Has broad but not deep awareness of the most popular libraries in the industry for a language.

> able to understand basic questions and speech, which allows for guides, such as slower speech or repetition, to aid understanding

Able to navigate the common practices of dependency management for a language.

> has only a vocabulary large enough to communicate the most basic of needs; also makes frequent punctuation and grammatical mistakes in writing of the language
speech is normally very laborious.
> The majority of individuals classified as Level 1 are able to perform most basic functions using the language. This includes buying goods, reading the time, ordering simple meals and asking for minimal directions.

Can write basic scripts using core library API.


## p_ILR Level 2
Limited working proficiency is rated 2 on the scale. A person at this level is described as follows:
> able to satisfy routine social demands and limited work requirements

Can reliably contribute production quality code under normal supervision.

> can handle with confidence most basic social situations including introductions and casual conversations about current events, work, family, and autobiographical information

Has more than cursory knowledge of the popular libraries involved. Would not be overwhelmed at needing to select a library to use.

> can handle limited work requirements, needing help in handling any complications or difficulties; can get the gist of most conversations on non-technical subjects (i.e. topics which require no specialized knowledge), and has a speaking vocabulary sufficient to respond simply with some circumlocutions

Does not have depth in any library they work with, but knows how to ask for help in the context of the language.

> has an accent which, though often quite faulty, is intelligible

May mischaracterize features of the language, or use analogy to another language, to try to explain what they're doing. Probably writes in psuedocode first and "transliterates" to the language.

> can usually handle elementary constructions quite accurately but does not have thorough or confident control of the grammar.

Will probably miss idioms that allow easier manipulation of language constructs.

## p_ILR Level 3
Professional working proficiency is rated 3 on the scale. Level 3 is what is usually used to measure how many people in the world know a given language. A person at this level is described as follows:
> able to speak the language with sufficient structural accuracy and vocabulary to participate effectively in most conversations on practical, social, and professional topics

Will not mischaracterize language features, and makes use of common idioms to make the most of the language. Probably isn't meta-programming, using higher level functions, or type theoretic concepts of the language.

> can discuss particular interests and special fields of competence with reasonable ease

Has deep knowledge of a library they use, should be able to compare it to another library they encounter.

> has comprehension which is quite complete for a normal rate of speech

Will likely not need supervision in writing code. Is able to navigate a test harness appropriate to their task.

> has a general vocabulary which is broad enough that he or she rarely has to grope for a word

Knows all the common functions, where to look up any they are unsure of, and can read documentation productively without much if any assistance.

> has an accent which may be obviously foreign; has a good control of grammar; and whose errors virtually never interfere with understanding and rarely disturb the native speaker.

May not write the most concise or fluid code, but has no issues with syntax or misusing constructs. A Haskell programmer using all `do` notation may be in this category.

## p_ILR Level 4
Full professional proficiency is rated 4 on the scale. A person at this level is described as follows:
> able to use the language fluently and accurately on all levels and as normally pertinent to professional needs.

Can easily practice TDD in this language when appropriate, if applicable. Works more comfortably in this language than psuedocode first.

> can understand and participate in any conversations within the range of own personal and professional experience with a high degree of fluency and precision of vocabulary

Can comfortably mentor others in the language, answer any intermediate questions on it, and debate merits of language versus other languages. Has worked deeply with several important libraries, and has informed opinions on their merits from experience. Has probably had contact with the maintainers of libraries, or made contributions to common libraries.

> would rarely be taken for a native speaker, but can respond appropriately even in unfamiliar grounds or situations

Does not necessarily know the internals of how the language was written, but should probably know their effects: in Java could explain relative merits of garbage collection strategies even if they have not helped write any of them. Probably has not authored any critical or foundational libraries, ie. in Ruby was not a Rails contributor.

> makes only quite rare and minute errors of pronunciation and grammar

Solid and productive code reviewer.

> can handle informal interpreting of the language.

Able to explain the core concepts of a language (if applicable) or "metaphors" of the language (if applicable), ie. in TCL understands "everything is a command"/"everything is a string" and can explain how that influences or causes language constructs "this is why you can't have a comment at the end of an instruction".

## p_ILR Level 5
Native or bilingual proficiency is rated 5 on the scale. A person at this level is described as follows:
> has a speaking proficiency equivalent to that of an educated native speaker

Needs to keep up with activity of latest news in the language development, via mailing list or other discussion tools. Has made: some contributions to the core of the language or foundational libraries, ie. in Java contributed substantially to Spring; written books; keeps a non-trivial blog, spoken at conferences. (Not an exhaustive list.)

> has complete fluency in the language, such that speech on all levels is fully accepted by educated native speakers in all of its features, including breadth of vocabulary and idiom, colloquialisms, and pertinent cultural references.

Is a maintainer of it the language's spec/standard. Has written or contributed substantially to interpreters/compilers for the language and can explain the relationship between the implementation of features and the constraints placed on those features by implementation.
