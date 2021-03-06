# German-NLP

Curated list of open-access/open-source/off-the-shelf resources and tools developed with a particular focus on German [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Resources and tools which can be used either off-the-shelf or with minor adjustments and which are maintained are primarily chosen for this list. It is deliberately biased in terms of usability and user-friendliness.

Pull requests and suggestions are welcome! See [contributing guidelines](contributing.md).


## Table of Contents

- [Corpora](#Corpora)
- [Linguistic processing and annotation](#Linguistic-processing-and-annotation)
   - [Frameworks](#Frameworks)
   - [Treebanks](#Treebanks)
   - [Tokenization](#Tokenization)
   - [Lemmatization](#Lemmatization)
   - [Morphological analysis](#Morphological-analysis)
   - [POS-tagging](#POS-tagging)
   - [Syntactical parsing](#Syntactical-parsing)
   - [Word embeddings and senses](#Word-embeddings-and-senses)
   - [Sentiment detection](#Sentiment-detection)
   - [Named Entity Recognition](#Named-Entity-Recognition)
- [Speech NLP](#Speech-NLP)
- [More lists](#More-lists)


## Corpora

### General-purpose

* [Araneum Germanicum](http://aranea.juls.savba.sk/aranea_about/_germanicum.html)
* [COW](http://corporafromtheweb.org/category/corpora/german/)
* [DWDS](https://dwds.de)
* [IDS Corpora](http://www1.ids-mannheim.de/kl/projekte/korpora)
* [Leipzig Corpora Collection](http://wortschatz.uni-leipzig.de/en/download/)
* [SdeWaC](http://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/sdewac.en.html)


#### Historical

* [Deutsches Textarchiv](https://deutschestextarchiv.de/)
* [Elektronische Texte (Thomas Gloning)](http://www.staff.uni-giessen.de/gloning/etexte.htm)
* [German Drama Corpus](https://github.com/dracor-org/gerdracor)
* [Referenzkorpus Mittelhochdeutsch (1050-1350)](https://www.ruhr-uni-bochum.de/wegera/rem/index.htm)
* [Referenzkorpus Mittelniederdeutsch/Niederrheinisch (1200-1650)](https://corpora.uni-hamburg.de/hzsk/de/islandora/object/text-corpus:ren-0.6)
* [Referenzkorpus Frühneuhochdeutsch (1350-1650)](https://www.ruhr-uni-bochum.de/wegera/ref/index.htm)


#### Specialized

* [Dortmunder Chat Korpus](http://www.chatkorpus.tu-dortmund.de/)
* [German Political Speeches Corpus](http://purl.org/corpus/german-speeches)
* [GermaParl (Bundestag)](https://github.com/PolMine/GermaParlTEI)
* [One Million Posts Corpus](https://ofai.github.io/million-post-corpus/)
* [Open Speech Data Corpus](http://voxforge.org/home/forums/other-languages/german/open-speech-data-corpus-for-german)


#### Swiss German

* [ArchiMob Corpus](https://www.spur.uzh.ch/en/departments/research/textgroup/ArchiMob.html)
* [NOAH's Corpus of Swiss German Dialects](http://kitt.cl.uzh.ch/kitt/noah/NOAHsCorpusOfSwissGermanDialects_Release2.1.zip)
* [SpinningBytes Swiss German Sentiment Corpus](https://github.com/spinningbytes/SB-CH)
* [Swiss SMS Corpus](http://www.sms4science.ch/Main/WebHome)


#### Lists

* [CLARIN-D list](https://www.clarin-d.net/en/corpora)
* [Corpora at the IMS](http://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/index.en.html)
* [CorpusExplorer's list of corpora](https://notes.jan-oliver-ruediger.de/korpora/)
* [Korpora am IMS](http://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/index.html)
* [Parallel corpora (see below)](#parallel-corpora)
* [Treebanks (see below)](#treebanks)
* [ZAS list](http://www.zas.gwz-berlin.de/katalog00100.html?&L=1)


#### Learner/Error Corpora

* [C-WEP](http://lingured.info/linguistic-resources/cwep/)
* [Falko](https://www.linguistik.hu-berlin.de/de/institut/professuren/korpuslinguistik/forschung/falko)
* [OpinionSpam](https://github.com/hdaSprachtechnologie/OpinionSpam)


### Data acquisition

* [bundestag](https://github.com/bundestag)
* [DKPro C4Corpus](https://github.com/dkpro/dkpro-c4corpus)
* [german-reddit](https://github.com/adbar/german-reddit)
* [news-crawler](https://github.com/theSoenke/news-crawler)


## Linguistic processing and annotation

#### Frameworks

* [CLARIN-D web tools](https://www.clarin-d.net/en/analysing)
* [CorpusExplorer](http://notes.jan-oliver-ruediger.de/software/corpusexplorer-overview/)
* [DKPro](https://dkpro.github.io)
* [Mate Tools](http://www.ims.uni-stuttgart.de/forschung/ressourcen/werkzeuge/matetools.en.html)
* [spaCy](https://github.com/explosion/spaCy)
* [Stanford CoreNLP](https://github.com/stanfordnlp/CoreNLP)
* [textblob-de](https://github.com/markuskiller/textblob-de)


#### Treebanks

* [German Universal Dependency Treebank](https://github.com/UniversalDependencies/UD_German-GSD/tree/master)
* [Hamburg Dependency Treebank](https://corpora.uni-hamburg.de/hzsk/de/islandora/object/treebank:hdt)
* [NEGRA](http://www.coli.uni-saarland.de/projects/sfb378/negra-corpus/)
* [TIGER Corpus](http://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/tiger.en.html)
   * [SALSA (role semantic annotation)](http://www.coli.uni-saarland.de/projects/salsa/corpus/)
   * [Tiger2Dep (dependency parses)](http://www.ims.uni-stuttgart.de/forschung/ressourcen/werkzeuge/Tiger2Dep.en.html)
* [TüBa-D/Z](http://www.sfs.uni-tuebingen.de/en/ascl/resources/corpora/tueba-dz.html)


#### Annotation

* [corpus-tools.org](http://corpus-tools.org/home/)


#### Tokenization

* [SoMaJo](https://github.com/tsproisl/SoMaJo)
* [waste](http://kaskade.dwds.de/waste/)
* [german-abbreviations](https://github.com/jfilter/german-abbreviations)


#### Word lists

* [DeReWo](http://www1.ids-mannheim.de/kl/projekte/methoden/derewo.html)
* [German Compound Database](https://www.webcorpora.org/opendata/gecodb/)
* [German nouns from Wiktionary](https://github.com/gambolputty/german-nouns)
* [German word list for GNU Aspell](https://sourceforge.net/projects/germandict/files/)
* [OpenThesaurus](https://www.openthesaurus.de/about/download)


### Stemming

* [CISTEM](https://github.com/LeonieWeissweiler/CISTEM)

#### Lemmatization

* [germalemma](https://github.com/WZBSocialScienceCenter/germalemma)
* [IWNLP](https://github.com/Liebeck/IWNLP)
   * [spacy-iwnlp](https://github.com/Liebeck/spacy-iwnlp)


#### Morphological analysis

* [CharSplit](https://github.com/dtuggener/CharSplit)
* [DEMorphy](https://github.com/DuyguA/DEMorphy)
* [Durm Lemmatizer](http://www.semanticsoftware.info/durm-german-lemmatizer)
* [HypheNN-de](https://github.com/msiemens/HypheNN-de)
* [jwordsplitter](https://github.com/danielnaber/jwordsplitter)
* [MarMoT](http://cistern.cis.lmu.de/marmot/)
* [Morphy](http://morphy.wolfganglezius.de/)
* [morphisto](https://code.google.com/archive/p/morphisto/)
* [SECOS (unsupervised compound splitter)](https://github.com/riedlma/SECOS)
* [SMOR](http://www.cis.uni-muenchen.de/~schmid/tools/SMOR/)


#### Normalization

* [CAB](http://www.deutschestextarchiv.de/cab)


#### POS-tagging

* [clevertagger](https://github.com/rsennrich/clevertagger)
* [moot](http://kaskade.dwds.de/~jurish/projects/moot)
* [pattern.de](https://www.clips.uantwerpen.be/pages/pattern-de)
* [RFTagger](http://www.cis.uni-muenchen.de/~schmid/tools/RFTagger/)
* [SoMeWeTa](https://github.com/tsproisl/SoMeWeTa)
* [TnT](http://www.coli.uni-saarland.de/~thorsten/tnt/)
* [TreeTagger](http://www.cis.uni-muenchen.de/~schmid/tools/TreeTagger/)


#### Syntactical parsing

* [Berkeley Parser](https://github.com/slavpetrov/berkeleyparser)
* [BitPar](http://www.cis.uni-muenchen.de/~schmid/tools/BitPar/)
* [CDG](https://nats-www.informatik.uni-hamburg.de/CDG/DownloadPage)
   * [jwcdg](https://gitlab.com/nats/jwcdg)
* [ParZu](https://github.com/rsennrich/parzu)
* [Stanford Parser](https://nlp.stanford.edu/software/lex-parser.shtml)


#### Word embeddings and senses

* [disco (semantic similarity)](https://github.com/linguatools/disco)
* [GermaNet](http://www.sfs.uni-tuebingen.de/GermaNet/)
   * [pygermanet](https://github.com/wroberts/pygermanet)
* [german2vec](https://github.com/Bachfischer/german2vec)
* [GermanWordEmbeddings](https://github.com/devmount/GermanWordEmbeddings)
* [Open German WordNet](https://github.com/hdaSprachtechnologie/odenet)
* [sensegram](https://github.com/tudarmstadt-lt/sensegram)
* [UBY Linked Lexical Resource](https://dkpro.github.io/dkpro-uby/)


#### Semantic analysis datasets

* [schulteimwalde.de/resources.html](http://www.schulteimwalde.de/resources.html)
* [UKP Darmstadt data list](https://www.informatik.tu-darmstadt.de/ukp/research_6/data/index.en.jsp)


#### GermEval

* [GermEval-2018 data](https://github.com/uds-lsv/GermEval-2018-Data)
* [germeval-rug](https://github.com/malvinanissim/germeval-rug)
* [jpadillamontani/germeval2018](https://github.com/jpadillamontani/germeval2018)
* [uhh-lt/GermEval2017-Baseline](https://github.com/uhh-lt/GermEval2017-Baseline)


#### Sentiment detection

* [GermanPolarityClues](http://www.ulliwaltinger.de/sentiment/)
* [SentimentWortschatz](http://wortschatz.uni-leipzig.de/en/download/)
* [spacy-sentiws](https://github.com/Liebeck/spacy-sentiws)
* [SpinningBytes Swiss German Corpus](https://github.com/spinningbytes/SB-CH)


#### Named Entity Recognition

* [flair](https://github.com/zalandoresearch/flair)
* [GermaNER](https://github.com/tudarmstadt-lt/GermaNER)
* [LSTM+CRF+FastText with models for (historic) German](https://github.com/riedlma/sequence_tagging)
* [ner-corpora](https://github.com/EuropeanaNewspapers/ner-corpora)
* [(Faruqui & Pado 2010) Compenents and evaluation data](https://nlpado.de/~sebastian/software/ner_german.shtml)


#### Psycholinguistics

* [Noun Associations for German](http://www.psycholing.es.uni-tuebingen.de/nag/index.php)


## Speech NLP

* [Archiv für gesprochenes Deutsch](http://agd.ids-mannheim.de/korpus_index.shtml)
* [BAS ressources](http://www.bas.uni-muenchen.de/Bas/BasSpeechresourceseng.html)
* [Bochumer Korpus der gesprochenen Sprache im Ruhrgebiet](https://www.ruhr-uni-bochum.de/kgsr/)
* [Database for Spoken German (IDS Mannheim)](https://dgd.ids-mannheim.de/dgd/pragdb.dgd_extern.welcome)
* [(D)iscourse (I)nformation (R)adio (N)ews (D)atabase for (L)inguistic Analysis ](http://www.ims.uni-stuttgart.de/forschung/ressourcen/korpora/dirndl.en.html)
* [Hamburger Zentrum für Sprachkorpora](https://corpora.uni-hamburg.de/hzsk/)
* [kaldi-tuda-de](https://github.com/uhh-lt/kaldi-tuda-de)


## Machine Translation

* []()


#### Parallel corpora

* [Linguatools Webcrawl German-English 2015](http://linguatools.org/tools/corpora/webcrawl-parallel-corpus-german-english-2015/)
* [MuchMore Springer Bilingual Corpus](http://muchmore.dfki.de/resources1.htm)


## Summarization

* [Tools and corpora for summarization of German texts](https://github.com/AIPHES)

## Coreference resolution

* [CorZu](https://github.com/dtuggener/CorZu)


## Standards

* [DTA Basisformat](http://www.deutschestextarchiv.de/doku/basisformat/)
* [ISO TC 37 SC 4](https://www.iso.org/committee/297592.html)

## Industry/Applications

* [German Decompounder for Apache Lucene / Apache Solr / Elasticsearch](https://github.com/uschindler/german-decompounder)

## Tutorials

* [deeplearning4nlp-tutorial](https://github.com/UKPLab/deeplearning4nlp-tutorial)

## Evaluation

* [Evaluation of different NLP toolkits](https://github.com/goerlitz/nlp-german)


## More lists

#### German

* [LRE Map](http://lremap.elra.info/?&selected_facets=languageFilter_exact%3AGerman)
* [MetaShare Language Resources](http://metashare.ilsp.gr:8080/repository/search/?q=&selected_facets=languageNameFilter_exact%3AGerman)
* [Peter Kolb's list](http://www.ling.uni-potsdam.de/~kolb/nlp-tools.html)
* [Swiss German Language Processing](http://kitt.cl.uzh.ch/kitt/noah/resources)


#### General

* [GitHub topic corpus-linguistics](https://github.com/topics/corpus-linguistics)
* [GitHub topic nlp](https://github.com/topics/nlp)
* [nlp-datasets](https://github.com/niderhoff/nlp-datasets)
* [NLP-progress](https://github.com/sebastianruder/NLP-progress)
* [/r/LanguageTechnology/](https://www.reddit.com/r/LanguageTechnology/)


#### Comparable lists

* [awesome-nlp](https://github.com/keon/awesome-nlp)
* [Awesome Community-Curated NLP List](https://github.com/alvations/awesome-community-curated-nlp)
* [awesome-chinese-nlp](https://github.com/crownpku/Awesome-Chinese-NLP)
* [awesome-hungarian-nlp](https://github.com/oroszgy/awesome-hungarian-nlp)
* [Indonesian NLP](https://github.com/kmkurn/id-nlp-resource)
* [awesome-spanish-nlp](https://github.com/dav009/awesome-spanish-nlp)
* [M. Weisser's list of NLP/Computational Linguistics Resources](http://martinweisser.org/corpora_site/comp_ling_resources.html)
* [NLP tools (Saarland University)](http://www.coli.uni-saarland.de/~csporled/page.php?id=tools)
* [Portal Computerlinguistik](http://www.computerlinguistik.org/portal/portal.html?s=Ressourcen)
* [W. Roberts' Computational Linguistics Links](http://amor.cms.hu-berlin.de/~robertsw/links.html)


## License

[![CC-BY](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by.svg)](https://creativecommons.org/licenses/by/4.0/)
