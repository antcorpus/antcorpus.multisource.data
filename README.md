ANT Corpus
=============================

This documentation details information about different available versions for download of the multi-source [ANT (Arabic News Texts) Corpus](http://antcorpus.github.io).
You can find other details on the main website page.

Version details
---------------
> **Current version:** v2.1

| Version  | Articles number | Words number | Number of categories | Source
| :------: | :-------------: | :---------: | :-------------------: | :-----:|
| v2.1 **(current)** | 31 798  | > 9 670 000 | 6 | 6 different news sources (see below) |
| v1.1 | 10 161  | > 1 474 000 | 9 | [JawharaFM](http://www.jawharafm.net/ar/) |
| v1.0 | 6 005  | > 865 500 | 9 | [JawharaFM](http://www.jawharafm.net/ar/) |

Categories by news source website
----------------

| Category (en)  | Category (ar)  |  AlArabiya  |  BBC  |  CNN  |  France24  |  SkyNews  |  Total |
| :------:  |  :-------------:  |  :---------:  |  :---------:  |  :---------:  |  :---------:  |  :---------:  |  :---------: |
| culture  |  ثقافة  | 606 | 338 | - | 126 | - | 1 070 |
| economy  |  اقتصاد  | 1 071 | 281 | 463 | 78 | 1 479 | 3 372 |
| international news  |  العالم  | 2 030 | 1 220 | 734 | 2 793 | 3 575 | 10 352 |
| middle East  | الشرق الأوسط | - | 1 131 | 1 640 | 947 | 3 972 | 7 690 |
| sport  |  رياضة  | 2 443 | 385 | 483 | 297 | 2 975 | 6 583 |
| technology  | تكنولوجيا  | 369 | 460 | 187 | - | 1 715 | 2 731 |
| | **Number of docs.** | 6 519 | 3 815 | 3 507 | 4 241 | 13 716 | 31 798 |


Files format
----------------
ANT Corpus files are formatted in XML using similar tags to the [TREC](http://trec.nist.gov/) and [CLEF](http://www.clef-initiative.eu/) standard test collections.

This a sample of an article from BBC as a news web source in the "international news" (العالم) category:
```xml
<DOC>
  <DOCNO>BB-internationalNews-64-20180226</DOCNO>
  <URL>http://www.bbc.co.uk/arabic/world-43193332</URL>
  <SRC>BBC</SRC>
  <CAT>internationalNews</CAT>
  <TITLE>واشنطن تربط المحادثات مع كوريا الشمالية بـ"تفكيك برنامجها النووي"</TITLE>
  <TIME>Mon, 26 Feb 2018 02:20:10 GMT</TIME>
  <AUTHOR></AUTHOR>
  <ABSTRACT>
كوريا الجنوبية تعلن أن نظيرتها الشمالية مستعدة لإجراء محادثات مع واشنطن، والأخيرة تشترط أن يكون تفكيك البرنامج النووي لبيونغ يانغ هو الهدف النهائي لـ"أي حوار".
  </ABSTRACT>
  <TEXT>
أعلنت كوريا الجنوبية أن نظيرتها الشمالية مستعدة لإجراء محادثات مع الولايات المتحدة.
جاء هذا الإعلان بعد لقاء بين الجنرال كيم يونغ-تشول، رئيس وفد كوريا الشمالية إلى الأوليمبياد الشتوي، مع رئيس كوريا الجنوبية مون جاي-إن، قبيل الحفل الختامي للأوليمبياد.
وردت وزارة الخارجية الأمريكية، قائلة إن تفكيك البرنامج النووي لكوريا الشمالية يجب أن يكون الهدف النهائي لـ"أي حوار".
وأضافت الوزارة في بيان: "سنرى إذا ما كانت رسالة بيونغ يانغ اليوم، بأنها مستعدة لإجراء محادثات، تمثل الخطوة الأولى".
ولم تؤكد بيونغ يانغ هذا العرض من جانبها، لكنها أعلنت مرارا أنها مستعدة لإجراء محادثات دون أية شروط مسبقة.
وحضرت إيفانكا ابنة الرئيس الأمريكي دونالد ترامب الحفل الختامي للأوليمبياد، لكن من غير المتوقع أن تلتقي بأي مسؤول من كوريا الشمالية، على الرغم من أنها جلست، على بعد أقدام قليلة من الجنرال كيم في الاستاد الأوليمبي.
وشبه الجزيرة الكورية مقسمة منذ الحرب، التي دارت بين عامي 1950 و1953، ولم يوقع الجانبان على معاهدة سلام منذ ذلك الحين.
ويعتبر البعض أن التقارب بين الكوريتين خطوة من كوريا الشمالية، لتعكير العلاقات بين الجنوبية والولايات المتحدة.
ويحذر خبراء من أن التطورات الأخيرة لا تضع نهاية للتوترات الإقليمية الكامنة، خاصة في أعقاب التجارب الصاروخية والنووية، التي أجرتها الشمالية العام الماضي.
وبينما يمد الرئيس الكوري الجنوبي يده إلى الجنرال الشمالي كيم، لا يلقى ذلك قبولا لدى كل مواطني الجنوب.
واتُهم الجنرال كيم بأنه مدبر الهجوم على سفينة حربية جنوبية، وجزيرة يونبيونغ عام 2010، ما أسفر عن مقتل 46 بحارا جنوبيا.
ووصل الجنرال كيم إلى سول، بينما سعت عائلات الضحايا وبعض أعضاء البرلمان الجنوبي المحافظين إلى منع دخوله.
ونقل مكتب رئيس كوريا الجنوبية عنه قوله إن كوريا الشمالية "مستعدة للغاية"، لعقد محادثات مع الولايات المتحدة.
وأضاف المكتب أن بيونغ يانغ "تتفق على أن المحادثات بين الكوريتين، والعلاقات بين الشمالية والولايات المتحدة، يجب أن تتحسن سويا".
ويأتي هذا الإعلان من جانب رئاسة كوريا الجنوبية، بعد ساعات من بيان غاضب من جانب بيونغ يانغ، وصفت فيه عقوبات فرضتها واشنطن عليها مؤخرا بأنها "عمل من أعمال الحرب".
وأشادت وزارة خارجية الشمال بالطريقة، التي تعاونت بها الكوريتان خلال الأوليمبياد، لكنها قالت إن واشنطن "جلبت التهديد بالحرب إلى شبه الجزيرة الكورية، عبر فرض عقوبات جديدة واسعة النطاق"، قبيل اختتام الأوليمبياد.
امتلأت وسائل الإعلام الكورية الجنوبية بإشارات، إلى أن محادثات بين كوريا الشمالية والولايات المتحدة يمكن أن تعقد، في ظل وجود وفدي البلدين في بلدة بيونغ تشانغ، التي يقام فيها الأوليمبياد.
وسألت لورا بيكر، مراسلة بي بي سي في سول، مسؤولا من حكومة الجنوب، إذا ما كانت مقابلة بين وفدي الشمال والولايات المتحدة قد تحدث خلال اليومين القادمين، وكانت إجابته: "سوف نرى".
وأرسلت كوريا الشمالية وفدا عبر الحدود، من ضمنه الجنرال كيم تشوي كانغ-إيل، وهو دبلوماسي رفيع المستوى معني بشؤون أمريكا الشمالية.
في غضون ذلك، تضمن الوفد الأمريكي أليسون هوكر، وهي من مجلس الأن القومي الأمريكي، ومتخصصة في شؤون شبه الجزيرة الكورية. والتقت أليسون مع الجنرال كيم في كوريا الشمالية عام 2014، حينما كانت الولايات المتحدة تسعى لتحرير معتقلين أمريكيين اثنين.
وقد يجري إعداد المشهد لاجتماع منخفض المستوى، بدلا عن المحاولة الفاشلة التي جرت مع مايك بنس.
وكان من المقرر أن يلتقي بنس مع كيم يو-جونغ، شقيقة الزعيم الكوري الشمالي كيم يونغ-أون، في بداية الأوليمبياد، لكن اللقاء تم إلغاؤه من جانب بيونغ يانغ دون تفسير، وفقا لمسؤولين أمريكيين.
ولم تعلق كوريا الشمالية على الأمر.
ولم يجر أي اتصال رسمي بين كوريا الشمالية وإدارة الرئيس ترامب حتى الآن.
  </TEXT>
</DOC>
```
#### About tags
- `<DOCNO>` sourceAcronym `-` category `-` incremental_id `-` pubDate `</DOCNO>`
- `<AUTHOR>` may don't have content in some articles.
- `<DOCNO>`, `<URL>`, `<SRC>`, `<CAT>`, `<TITLE>`, `<TIME>`, `<ABSTRACT>`, `<TEXT>` are mandatory.


## Citation Licence
>The files of ANT Corpus are subject to the following citation license:   
>By downloading ANT Corpus, you agree to cite at least one of our papers describing ANT Corpus and/or refer the project's main page in any kind of material you produce where ANT Corpus was used to conduct search or experimentation, whether be it a research paper, dissertation, article, poster, presentation, or documentation.   
>**By using this data, you have agreed to the citation licence**.

### Publications
:page_facing_up: A. Chouigui, O. Ben Khiroun, and B. Elayeb. **ANT Corpus : An Arabic News Text Collection for Textual Classification**. In proceedings of the 14th ACS/IEEE International Conference on Computer Systems and Applications ([AICCSA 2017](http://www.aiccsa.net/AICCSA2017/)), pp. 135-142, Hammamet, Tunisia, October 30 - November 3, 2017.

:page_facing_up: A. Chouigui, O. Ben Khiroun, and B. Elayeb. **A TF-IDF and Co-occurrence Based Approach for Events Extraction from Arabic News Corpus**. In proceedings of the 23rd International Conference on Natural Language & Information Systems ([NLDB 2018](http://nldb2018.cnam.fr/)), pp. 272-280, Paris, France, 13-15 June 2018.

:page_facing_up: A. Chouigui, O. Ben Khiroun and B. Elayeb. **Related Terms Extraction from Arabic News Corpus using Word Embedding**. In: OTM Conferences & Workshops: Proceedings of the 7th International Workshop on Methods, Evaluation, Tools and Applications for the Creation and Consumption of Structured Data for the e-Society ([Meta4eS'18](http://www.otmconferences.org/index.php/ws/meta4es-2018)), Springer, LNCS, pp. 1-11, Valletta, Malta, 22-26 October 2018.

## Do you want to contribute to ANT Corpus project?
> If you want to report bugs, make suggestions for new categories, website sources and etc, your first point-of-call should by the [Issues page](https://github.com/antcorpus/antcorpus.multisource.data/issues) for the repository. If you have something to add, either to a preexisting issue, or as an entirely new issue, feel free to do so.
> ### Have any ideas?
> - If you have any ideas for features you'd like implemented, please share them with us.
> ### Can you code?
> - Please refer to the [RSSCrawlerArabicCorpus](https://github.com/antcorpus/RSSCrawlerArabicCorpus) project.
> - Reviewing and commenting on code; Pointing out ways to make it better; Refactoring, rewriting, and improving. These things are welcomed and appreciated.
> ### Can you spread the word?
> If you find the project interesting for the evolution of the Arabic language, feel free to write blog posts, mention it on social media (Facebook, Twitter), etc.


----------------------
> Project webpage: <https://antcorpus.github.io>  
> Copyright (C) 2019 All Rights Reserved.  
> [RIADI-ENSI](http://www.riadi.rnu.tn/), [University of Manouba](http://www.uma.rnu.tn) & [ENISo](eniso.rnu.tn), [University of Sousse](http://www.uc.rnu.tn).  

![Version](https://img.shields.io/badge/last_version-v2.1-green.svg)
![Status](https://img.shields.io/badge/status-beta-orange.svg)
![Licence](https://img.shields.io/badge/licence-Apache_2.0-blue.svg)
