## Parallel Bible Corpus

Project
-------

* __Name:__ Parallel Bible Corpus
* __URL:__ <http://paralleltext.info>
* __Description:__ The Parallel Bible Corpus is an ongoing project that aims at collecting Bible texts from the world's languages with the inherent parallelism of the verses being preserved. The ultimate goal is to provide a large collection of language data from all continents and language families that can be used for language comparison on the text level. The texts are not collected with a liturgical goal, nor for the enhancement of bible study. Although we think that the current resource might also be valuable in that context, we are explicitly making a resource for comparative linguistics. We aim to represent the text as close as possible to the intended form of the original translation, and we give full credit and reference for all translations included in this corpus. We welcome all suggestions and corrections (cysouw@uni-marburg.de). However, please note that the texts in this corpus are not intended to be authoritative liturgical versions of the respective translations. Please consult the original version as indicated in our corpus to obtain the translation in its original context. The corpus is compiled and maintained by Thomas Mayer and Michael Cysouw within the Paralleltext.info project at the Philipps University of Marburg, with thankfully acknowledged assistance from Östen Dahl, Matthew Dryer, Harald Hammarström and Bernhard Wälchli. A summary of the goals and methods of the project can be found in: Mayer & Cysouw (2015) Creating a Massively Parallel Bible Corpus (http://paralleltext.info/).

Format Description
------------------

The format for the Bible texts has the following structure. Each line contains two elements which are separated by a TAB. The first element is the verse ID and the second element contains the actual text. The verse ID contains information about the book, chapter and verse number and is structured as follows (for the example of the verse ID 40001003):

* the first two digits represent the number of the book (e.g. 40 refers to the first book in the New Testament, the Gospel according to Matthew). The correspondences between book names and numbers are given below.
* the next three digits indicate the chapter (e.g. 001 refers to the first chapter in the book)
* the last three digits show the verse number (e.g. 003 refers to the third verse in the chapter)

Some lines contain only a verse ID and a TAB, but no actual text. In these cases, the translation of the respective verse ID is combined into the last preceding full text line above the empty text line. For example, when ID 400001003 has no text, but ID 400001002 (directly preceding) contains text, then one can assume that the content of ID 400001003 is available somewhere inside that text of ID 400001002, but it is not easy to separate the content.

Bible Book IDs
--------------

* 01 : Genesis 
* 02 : Exodus 
* 03 : Leviticus 
* 04 : Numbers 
* 05 : Deuteronomy 
* 06 : Joshua 
* 07 : Judges 
* 08 : Ruth 
* 09 : 1 Samuel 
* 10 : 2 Samuel 
* 11 : 1 Kings 
* 12 : 2 Kings 
* 13 : 1 Chronicles 
* 14 : 2 Chronicles 
* 15 : Ezra 
* 16 : Nehemiah 
* 17 : Esther 
* 18 : Job 
* 19 : Psalms 
* 20 : Proverbs 
* 21 : Ecclesiastes 
* 22 : Song of Solomon 
* 23 : Isaiah 
* 24 : Jeremiah 
* 25 : Lamentations 
* 26 : Ezekiel 
* 27 : Daniel 
* 28 : Hosea 
* 29 : Joel 
* 30 : Amos 
* 31 : Obadiah 
* 32 : Jonah 
* 33 : Micah 
* 34 : Nahum 
* 35 : Habakkuk 
* 36 : Zephaniah 
* 37 : Haggai 
* 38 : Zechariah 
* 39 : Malachi 
* 40 : Matthew 
* 41 : Mark 
* 42 : Luke 
* 43 : John 
* 44 : Acts 
* 45 : Romans 
* 46 : 1 Corinthians 
* 47 : 2 Corinthians 
* 48 : Galatians 
* 49 : Ephesians 
* 50 : Philippians 
* 51 : Colossians 
* 52 : 1 Thessalonians 
* 53 : 2 Thessalonians 
* 54 : 1 Timothy 
* 55 : 2 Timothy 
* 56 : Titus 
* 57 : Philemon 
* 58 : Hebrews 
* 59 : James 
* 60 : 1 Peter 
* 61 : 2 Peter 
* 62 : 1 John 
* 63 : 2 John 
* 64 : 3 John 
* 65 : Jude 
* 66 : Revelation
* 67 : Tobit
* 68 : Judith
* 69 : Esther (Greek)
* 70 : Wisdom of Solomon
* 71 : Ecclesiasticus (Sirach)
* 72 : Baruch
* 74 : Prayer of Azariah
* 77 : 1 Maccabees
* 78 : 2 Maccabees
* 79 : 3 Maccabees
* 80 : 4 Maccabees
* 81 : 1 Esdras
* 82 : 2 Esdras
* 83 : Prayer of Manasseh
* 84 : Psalm 151
* 85 : Psalm of Solomon
* 86 : Odes

Please note:

* The 'Epistle of Jeremiah' is considered as Baruch Chapter 6 in catholic versions, but as a separate book in orthodox versions. We include it always as Baruch 6, so it is numbered as 72006001 to 72006072.
* The Book 'Susanna' is sometimes part of Daniel (Chapter 13), but sometimes listed as a separate apocryphal book. For reasons of parallelism we always treat it as a part of Daniel, so it is numbered 27013001 to 27013064.
* The Book 'Bel and the Dragon' is sometimes part of Daniel (Chapter 14), but sometimes listed as a separate apocryphal book. For reasons of parallelism we always treat it as a part of Daniel, so it is numbered 27014001 to 27014042.

Some more details about consistent numbering of verses to assure parallelism:

* Bibles with a verse 43006072: these mostly have an additional separation of verse 43006051 into two verses. As a solution, 43006052 should be merged with the preceding verse 43006051, and verses 43006053 to 43006072 should be shifted one number back.
* Bibles with a verse 43001052: these mostly have an additional separation of verse 43001038 into two verses. As a solution, 43001039 should be merged with the preceding verse 43001038, and verses 43001040 to 43001052 should be shifted one number back.
* Bibles with a verse 41009051 (mostly French, apparently): this verse should be merged with the preceding verse 41009050
* Bibles with a verse 45007026: This occurs very rarely, so they are better merged with the preceding verse 45007025.
* Bibles with a verse 66012018: the content of this verse is in many translations part of the start of the next chapter 66013001. As a solution, any existing 66012018 will be merged to the start of 66013001.
* Bibles without a verse 64001015: Most, but not all, translations have a verse 64001015. In some translations the content of this verse is part of the preceding verse 64001014, and 64001015 does not exist. An empty 64001015 should be added to those that do not have this verse.
* Bibles without a verse 44019041: Most, but not all, translations have a verse 44019041. In some translation the content of this verse is part of the preceding verse 44019040, and 44019041 does not exist. An empty 44019041 should be added to those that do not have this verse.
* Bibles without a verse 47013014: This happens because verse 47013012 is often split in two, but not always. As a solution: when verse 47013014 does not exist, then 47013013 should be changed to 47013014, and an empty 47013013 should be inserted.

Maintainers
-----------

* __Thomas Mayer__  
	<thommy.mayer@gmail.com>  
	<http://th-mayer.de>

* __Michael Cysouw__  
	<cysouw@uni-marburg.de>  
	<http://cysouw.de/home>
	