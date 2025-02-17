### Работа с полевыми данными в FieldWorks  

[Fieldworks](https://software.sil.org/fieldworks/download/) - инструмент для документации языковых и этнографических данных, разработанный SIL International. Полезные функции:  
  * Глоссирование текстов  
  * Словари малых языков
  * Создание скетча грамматики
  * Дискурс-анализ, объединение лексики в классы для антропологии, анализа фольклора и т. д.
  * Метаданные текстов  
  * Автоматизация глоссирования на основе ранее созданных словарных входов
  * Замена разметки по всему тексту/текстам при редактировании информации в словаре  
  * Автоматический анализ разборов с помощью правил парсера  
  * Гибкая настройка категорий в грамматике и словаре, категорий словарей (Main/Draft)
  * Поддержка списков - например, информантов, мест записи и т.п.
  * Легкий переход от словаря к конкордансу, от списка информантов к списку его текстов и т. п.  
  * Поддержка командной работы
  * Изменения сохраняются автоматически (и можно делать бэкапы для сохранения промежуточных версий)  

### Создание проекта  
`File > New FieldWorks project...`  
* Язык полевых данных (vernacular language)  
* Язык описания (analysis)  
`Tools > Configure`  
* Донастройка языков описания и анализа - IPA, Audio и др.  

### Lexicon - Создание словаря  
`Tools > Configure` 
* Основные поля  
* Поиски, фильтры, сортировки, видимые поля словаря

<img src="fig/FlEX_lexicon.png" width="70%">  

### Texts and Words - Работа с текстом  
`> Insert > New text`  
* Interlinear text: На вкладке `Baseline` вставьте предложения, по одному предложению на строку    
* Глоссирование: На вкладке `Analyze` посмотрите готовые разборы, одобрите автоматические построенные и добавьте новые     
* Добавление грамматической информации: в карточке разбора `▼ > Create new entry` или выбор из существующих разборов    
* Разбиение на морфемы: в слое морфологии разделите словоформу на сегменты с помощью `-`  
* Алломорфы  
* Пакетная обработка разборов: используйте зеленую галочку с плюсиком    
* Парсинг слов: с помощью встроенных парсеров, разработанных для отдельных языков  

<img src="fig/FlEX_text_analysis.png" width="70%">  

<img src="fig/FlEX_new_entry.png" width="50%">  

###  Grammar - Грамматика  
`> Insert > Category (or Part of speech)...`  
  - инвентарь грамматических категорий   
`> Insert > Affix template`  
  - шаблоны для аффиксов  

### Другие возможности  
* работа с пользовательскими списками (информантов, населенных пунктов и т.п.)   
* скрипты для построения фонетических правил и другой обработки  
* публикация данных  
* коллективная работа  
* импорт и экспорт данных, форматы экспорта  

### Упражнения  
1. Разметьте в FieldWorks пример восточнославянской диалектной речи (Хиславичский район Смоленской обл.)
ну ёсть/ ёсть/ и… и зьмеи ёсть/ и ужы ёсь/ асобина вън у Соини/ мы едим/ лянь/ нъ кънях/ ина ляжыть нъ пяску/ длинъя тъкая!// ну мы зъкричали/ ина пабеɣла// ну/ ина пабеɣла/ а етъй/ мужык усьлед за ёю/ ина узила/ хвост кинъла/ съма утикла// [ого!] зьмия/ да!// ну думъить/ хвастом зънимайтись/ а ина утикла!/  
[Источник](https://processing.ruscorpora.ru/search.xml?docid=ZGlhbGVjdC9zbW9sZW5zay9wb3ZhcmVua292YTJfem1lamFfMjJfMi54bWw%3D&expand=full&mode=dialect&nodia=1&req=%D0%BB%D1%8F%D0%B6%D1%8B%D1%82%D1%8C&sid=1&sort=i_grtagging&text=lexform): Диалектный корпус НКРЯ

2. Разметьте в FieldWorks пример на эвенском  
(Окончание истории следующего содержания: _Приехали в гости к нам. Спать готовились. И ели, чай пили. Потом на улицу выходили и кукуль (спальник) дали. И никто не видел, как он лёг спать. Утром проснулись. Он проснулся, вся голова мокрая. Почему же он намок, спрашивают. Почему такой мокрый? Эхех..._).
```
ekiči       ira-r           turku-ri-wu      onə-č    ukle-wo-d-i-š
невозможно  дышать-CVB.NEG  не_мочь-PST-1SG  как-INS  спать-HAB-PROG-PST-2PL

budel'u-gda  gilla.l-li-n      iŋenə.l-li-n
ноги-side    охладеть-PST-3SG  замерзнуть-PST-3SG
‘Невозможно дышать не мог, как вы спите, ноги остыли, стали замерзать.’

onə-š     ukle-ri-š?
как-EMPH  спать-PST-2SG
‘Как спал?’

mukču-dula-n        i-ri-wu          dil-ǯi
тупик-LOC-POSS.3SG  входить-PST-1SG  голова-INS.POSS.REFL.SG
‘В мешок залез головой.’
```

После выполнения упражнения посмотрите на скетч созданной вами грамматики на основе разметки текста (`Grammar > Grammar sketch`)  

### Полезные ссылки  
* [Данные для работы](https://github.com/olesar/lingdata/blob/gh-pages/data/Russian-CL%202021-11-16%201439.fwbackup) - пример проекта для русского языка (пользуйтесь `File > Project management > Restore from backup` для загрузки)
* примеры проектов на сайте [SIL](https://software.sil.org/fieldworks/download/sample-projects)  
* [видео](https://disk.yandex.ru/i/iSw3uDh4kZubXg) тьюториала С. Ю. Толдовой  
* [История создания](https://www.sil.org/about/history) Summer Institute of Linguistics (SIL)  
* [обучающие ролики SIL](https://software.sil.org/fieldworks/download/demo-movies/index-of-demo-movies/)  
* [обучающие ролики](https://www.youtube.com/watch?v=K9yuZ6lKVrc&list=PLJLUPwIFOI8fYftqs5FBS9j9NEnPKvq60) ютьюб-канала Linguistics Institute Payap University  
* [тьюториал](fig/FLEx-HSE-20201124.pdf) А. В. Архипова в ВШЭ  
* Лейпцигские правила глоссирования [LGR](https://www.eva.mpg.de/lingua/resources/glossing-rules.php)  
* [конвертор IPA](https://baltoslav.eu/ipa)   

Примеры:  
* R. Gersamia, I. Lobzhanidze. The Megrelian Language in FLEx: Texts, Lexicon, Grammar [pdf](https://kld.iliauni.edu.ge/abstracts/Gersamia_Lobzhanidze_Eng.pdf)  
