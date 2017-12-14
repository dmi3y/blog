+++
title = "Skycoin - Coin Интервью Youtube транскрипт"
tags = [
]
date = "2017-11-25"
categories = [
    "Ask the Developers",
]
description = "Транскрипт интервью с Synth представителем Skycoin, проводимого youtube каналом Coin Интервью (от 2017-10-30)"
+++

*originally held October 30, 2017 on the Coin Interview youtube channel (https://www.youtube.com/watch?v=BuY5IbkkbXg)*
*Запись интервью проводимого 30 Октября 2017 youtube каналом Coin Интервью (https://www.youtube.com/watch?v=BuY5IbkkbXg)*

*Интервью в формате "спрашивайте что хотите",
synth представитель skycoin.
christian и evan задают вопросы*

**christian**
Мы на связи с Synth, одним из ведущих проект менеджеров Skyledger, Skycoin, ну и вы в курсе что это. Так же хотел поблагодарить наших спонсоров, это ark.io. Дайте нам знать если и вы заинтересованы в поддержке канала.

**synth**
Обожаю Ark.

**christian**
Эти пацаны круты.

**synth**
Да они много нам помогали и ребята из Lisk-а тоже.

**christian**
Точно, я еще не приводил Макса на шоу. Я даже не знаю для чего Lisk нужен, но давай отложим Lisk на потом, давай сейчас поговорим о Skycoin. Рано или поздно мы приведем их на шоу. Нам нужно составить большой список всех проектов которые мы еще не освещали, ну или что то типа того.

**synth**
Мы работаем с bitseed, Майк его звать, я думаю мы даже разделяем производство на фабрике в Шэньчжэнь, это представитель от Ark. Он собирает bitseed оборудование для Ethereum и Bitcoin, мы собираемся выпускать подобные для Skycoin, как железо.

**christian**
Хочешь нам рассказать о Skycoin? Для людей кто не в курсе. Это новый блокчейн? Это вообще блокчейн?

**synth**
Ну, наш проект не новый, ему уже где то шесть лет. В общем, когда Bitcoin появился было много ранних Bitcoin адептов которые делали аудит сети Bitcoin. Они пришли со стороны фирм занимающихся финансовыми операциями, фирм которым было интересно - Как это вообще работает? Работоспособны ли эти алгоритмы? Какие есть подводные камни? Если положить деньги в сеть, будут ли они потеряны? Не карточный ли это домик, который развалится завтра?
В общем эти все эти люди желали знать больше о Bitcoin и хотели провести полный аудит как на уровне кода так и на криптографическом уровне. И много народа было вовлечено, включая ранних Skycoin разработчиков, и мы просматривая исходники находили проблемный функционал. Существовало три или четыре различных групп которые пытались исправить Bitcoin. И так мы начали и потратили следующие шесть лет на то что бы переписать все с нуля, три раза.
Были такие вещи как дупликация эмиссий. У вас есть транзакция которая создает монеты и собственно сама транзакция которая отвечает за перевод. И получалось так что сеть создавала две одинаковые транзакции на эмиссию монет, две транзакции имеющих одинаковый хэш, и таким образом сеть Bitcoin страдала от хэш коллизий. 90% работы Сатоши была исключительно продумана, но где то от 10% хотелось плакать. И мы исправили дупликацию выпускаемых монет, возможность подмены подписи, подмены транзакций, и другие проблемы того времени, и позже нашлись проблемы в консенсус алгоритме.
Где то в это время появился gigahash.io. Это была группа друзей в маленьком городе на севере Украины которые все были вовлечены в только что зарождающийся Bitcoin бизнес. Один из них запустил майнинг пул, другой основал компанию по производству железа для майнинга, третий открыл онлайн обменку BTC-E, и так эта группа друзей создала собственную небольшую Bitcoin индустрию.
Gigahash.io удалось взять под контроль выше 60-70% всех майнинг ресурсов Bitcoin. И так, вся сеть Bitcoin годами находилась под контролем одного майнинг пула. Они скрывали хэш ресурсы под видом других майнинг пулов, так как они поняли что это будет выглядеть не очень хорошо если они огласят что  они держат под своим контролем свыше 60% сети.

**synth**
Алгоритмом доказательства работы (PoW) Сатоши изначально желал децентрализовать сеть Bitcoin на сотни и тысячи компьютеров расположенных в различных странах, но что случилось то что майнинг сеть сейчас практически состоит из трех больших майнинг пулов в Китае. Так что мы не можем назвать Bitcoin децентрализованным, он очень централизованный.
И с тем что в мире сейчас только один производитель ASIC майнинг оборудования для Bitcoin он еще более централизован под этим углом. Мы хотели исправить консенсус алгоритм и это желание выросло в большой, в огромный исследовательский проект который занял три года. Skycoin начался как просто улучшения над Bitcoin блокчейном и переработку Bitcoin в продуманную технологию которая бы была надежней в использовании, потому что Bitcoin до сих пор имеет много заплаток и костылей.
Со временем проект развивался и расширялся. И сейчас у нас на руках около пятнадцати команд разработчиков работающих над разными проектами. И когда ты спросил что такое Skycoin, ну, у нас есть блокчейн, у нас есть консенсус алгоритм [обелиск], мы недавно создали язык программирования CX, который я бы не стал называть языком для умных контрактов, потому что, я считаю что умные контракты это ерунда, CX настоящий язык программирования для приложений.
Это CX.Skycoin.net. У нас есть CXO, библиотека неизменяемого хранилища данных потому что мы осознали что блоки, транзакции и эмиссии были все изменяемыми объектами данных, и так мы создали целую библиотеку для того что бы работать с этими объектами копировать их. И этот проект занял два года. И потом каким то образом, мы умудрились создать сеть ячеистой топологии. Распределенный интернет провайдер который мы назвали Skywire.
И так, люди обеспечивают сеть рабочими узлами и они обменивают передаваемые пакеты и получают вознаграждение за предоставленную пропускную полосу предоставляемую соседям. И это суть общественного интернета на блокчейне, где вы получаете прибыль за предоставление сервисов людям. И у нас есть возможность запустить VPN туннель по верх этой сети, и так я могу использовать узел в Шанхае, Гон-Конге, Лос-Анджелесе что дает возможность запустить мульти-интервальный VPN который позволит быстро менять положение через пять различных мест и таким образом полностью анонимизировать трафик.
Я могу использовать сеть для своих целей, и я могу так же позволить другим людям использовать ее и получать взамен монеты. Разработка Skywire заняла четыре года, я думаю, и это была огромная работа. Причина по которой сеть Skywire увидела свет, это возможность использовать ее для защиты сети Bitcoin от атаки в которой используется IP адреса участников сети.
Так если вы запустили узел Bitcoin сети и вы подключились к пяти IP адресам и ваш интернет провайдер или служба безопасности контролирует ваш модем, то они могут перехватить весь трафик на эти IP адреса так что вы даже не сможете определить к настоящей ли сети Bitcoin вы подключены.
Власти могут создать фальшивую сеть Bitcoin с тысячами узлов которые находятся под центральным контролем и они подключат вас к этой сети, а вы будете думать что вы подключены к настоящей Bitcoin сети. И так возник этот вопрос, как определить если сеть к которой вы подключены настоящая сеть Bitcoin или это теневая сеть где IP адреса подделаны.

[пауза для того что бы поправить микрофон]

**christian**
Гляди-ка, и это то о чем никто даже не догадывается...

**evan**
Ага, это было интересное введение.

**synth**
И все это заняло массу ресурсов, и мы только подошли к старту, люди начинают запускать узлы. И так как мы используем эти узлы, нам необходимо куча железа для работоспособной сети. Мы не хотим что бы их запускали в облачных сервисах типа Amazon, так что мы занялись выпуском собственного железа, которое будет доступно где то через месяц. У нас на сайте есть описание с фото. И скорее всего, все будет в открытом доступе. В дополнение, мы работаем над хардверным кошельком. На прошлой неделе мы наняли нашего первого инженера электроника который начал работать над этим кошельком.
И как мы выяснили в дальнейшем, люди начали клонировать Skycoin и создавать свои собственные монеты, и так появился проект Skyledger. На данный момент, мы имеем пятнадцать или двадцать проектов использующих Skycoin в качестве платформы. Мы можем сравнить Skycoin с ERC-20 платформой. И так как мы не можем запретить клонирование Skycoin, мы решили расширить его до уровня платформы с помощью которой можно создавать свои монеты.

**christian**
Откуда у вас деньги изначально? И насколько проект поддерживает себя финансово?

**synth**
Когда мы запустились, Bitcoin был меньше чем $1, ну и мы просто... вкладывались [смех] и мы никогда собственно не нуждались в деньгах.

**christian**
То есть, у вас нет правительственного спонсора, корпоративного спонсора, и прочей лабуды, есть просто разработчики? Анонимные разработчики? Известные разработчики?

**synth**
Да с нами сотрудничает много анонимных людей много из ранних крипто адептов. Эти крипто люди на самом деле странные типы..

**christian**
Ага, я могу представить

**synth**
И через Bitcoin за это время прошло двенадцать различных волн. И те люди которые объявились сейчас, они вроде, "Стань богатым быстро!!" "Делай деньги пока спишь!!" "Ах какие высокие дивиденды" "Эта валюта возвращает мне 10% в месяц, зачем я буду вкладывать в вашу если эта валюта приносит больше... и тд."
Они тут просто из за жадности. Ранние адепты Bitcoin-а, первая волна, они были реальными параноиками типа крипто-анархо-капиталистами. Они хотели свергнуть правительство со спецслужбами. Они считали что центральные банки это рабство и нам нужно избавится от них и это была идея ради которой они строили эту вещь.
Понимаете, Сатоши, в одном из его сообщений которое он оставил в блокчайне было о том что банковский кризис был специально устроен, это был грабеж устроенный группой банков... по простому, они устроили этот кризис что бы правительство напечатало 20 триллионов долларов в ответ, и они направили эти деньги в карманы своих друзей.

**christian**
Без сомнений

**synth**
Это было типа, "Ооо да, дайте нам двадцать триллионов долларов, или конец мира на завтра" [смех]

**christian**
Конечно. Так и есть.

**synth**
Вот так просто, обычные люди были ограблены центральными банками.  И все эти ранние адепты Bitcoin.. Иронично, многие из них работали на власти, работали на людей с большими деньгами и были вынуждены подписывать все эти соглашения о не разглашении. Они не были публично ассоциированы с проектом Bitcoin вообще, никогда. У Bitcoin-а было несколько публичных лиц, но основная масса людей стоящих за проектом стояли в тени. Я был на Bitcoin конференции в Лас Вегасе и видел такой типаж, он просто сидит в углу и наблюдает за всеми. Эти люди не общаются, они просто сидят на месте, типа "Хммм что тут происходит, кто тут обманщик и тому подобное" Вот так эти люди наблюдали за Bitcoin-ом и направлением в котором шла его разработка, но они негде не принимали участия. И вот так, каждые шесть месяцев совершенно новая толпа приходит в крипто сферу и так было на протяжении восьми лет. Я так прикидываю, это уже двенадцатая волна новых людей.

**christian**
И много сообществ разработчиков по всему миру. Я вступил на этот путь только в начале 2016. Я слышал о Bitcoin-е в 2013 но конечно если вы не знаете как программировать и что эта фигня на самом деле делает, а просто читаете новости, то просто с 2010 по 2015 все было негативно. Везде было даркнет и прочая фигня. Ну так вот, мой вопрос, есть много сообществ... как все эти сообщества хакеров черные шляпы и все эти конференции типа devcon. Насколько связаны эти специалисты по безопастности с этими финтек/крипто/деньги вещами? Которые мы знаем как Bitcoin/Skycoin? Или они все на деле каждый за себя. Эти парни которые круты в безопасности типа, о да Bitcoin... но я взламываю сети и тому подобное.

**synth**
Я бы не сказал что... каждый за себя. Нужно понять что эти группы очень маленькие. Вы можете взять эту группу в Украине как интересный пример. Просто кучка друзей собрались в баре, они слышали о Bitcoin и они все купили за доллар, ну они купили за копейки и теперь когда Bitcoin поднялся за сотни долларов, сейчас они все богаты.
Ну и один запустил майнинг пул, Gigahash, другой Bitcoin объменку, BTC-E, трений компанию по выпуску майнинг оборудования, Starfury, и так они создали свою закрытую Bitcoin экосистему. Они на деле были первыми людьми которые вложились... они предвосхитили структурные интегральные схемы специального назначения (ASIC). Они использовали программируемые пользователем матрицы (FPGA) для майнинга.
И эти ребята были первыми в разработке майнинга на графических картах (GPU), и затем они переключились на FPGA майнинг, и затем они взялись за ASIC, потому что у них были деньги и они были заинтересованы в этом. И опять, это была небольшая группа друзей. Так в пределах этих сообществ на поруках, может быть двадцать людей которые заинтересованы в Bitcoin и кто супер крутые разработчики, и которые сами себе на уме. И я бы не сказал что эти сообщества очень организованны. Это громадное слабо сформированное сборище людей с небольшими структурами внутри которые занимаются тем или этим.

**christian**
И когда люди видят что нибудь типа devcon, они чувствуют "нифига себе, эти ребята могут опустить мир на колени" но в действительности это не так... это просто кучка людей в комнате, это не то что когда государство организует группы на военном уровне от 3000 до 4000 хакеров.

**synth**
[смех] Ага, я видел такие бригады хакеров от государства, они используют Windows XP... и типа [смех] да это просто не серьезно.

**christian**
Я уверен что спецслужбы держат несколько квалифицированных спецов, знаешь. Ну да, я знаю что есть такие которые пинают балду, но есть и те которые получают огромные деньги за то что они знают чем занимаются.

**synth**
Все такие из частного сектора.

**christian**
Ну да, точно они из частного сектора потому что они не собираются протирать штаны в офисе и разбираться с бюрократией. Они просто делают дело. И ты знаешь все эти разговоры о деньгах.
И так это Skycoin, они вкладывают свои средства, органично развиваются.. Я уверен что ваши разработчики расположены по всему миру. Есть ли центральное место для Skycoin организации?

**synth**
Нет.. у нас есть типа тридцать три богатыря. [смех]

**christian**
Ага, понял, понял.

**synth**
У нас есть люди из России, люди из Китая, Штатов, несколько из Европы, еще меньше из Южной Америки, но в основном это граждане мира.

**christian**
Ну ты знаешь, для многих людей, очень простой вопрос будет... хорошо в чем разница между Skycoin и Bitcoin-ом, но честно на втором месте это Ethereum. И ты упомянул Skyledger и то что вы можете печатать свои типа ERC-20 токены, в чем большая разница между вами и Ethereum, и почему это люди не используют Skycoin вместо чего нибудь типа Ethereum?

**synth**
Ну наш скриптинг язык был закончен только два месяца назад, и это одна причина. Ethereum изначально продвигался, типа, как программируемый блокчейн и сообщество раздвинуло границы возможного. Они построили это громадное сообщество разработчиков и проделали громадную работу, но то что они сделали еще не готово к использованию. К примеру, если у вас есть четыре тысячи приложений на Ethereum с четырьмя тысячами ERC-20 токенов и если один токен проводит ICO, вся сеть будет лежать два дня просто из за проводимых транзакций для этого ICO. И если вы большая компания к примеру Siemens, и вы хотите интегрировать электрическую сеть на Ethereum, и ваша электрическая сеть отключается на два дня потому что ну знаете, Котэкоин проводит ICO, это будет просто смешно. И этим компании заинтересованы в Ethereum, им нравится блокчейны но они не хотят строить свой бизнес на нем. Они хотят свой собственный блокчейн. И это одно из различий, и причина почему мы создали Skyledger, это то что эти компании спрашивали у нас "нам нужен свой блокчейн". Мы не желаем делить блокчейн. Мы хотим свой. И они опробовали Ethereum, но в производство не запустили, и так же по правовым вопросам.. вроде если в результате взломы было бы украдено шесть сотен миллионов долларов, то они смогли бы сбросить блокчайн и возвратить эти деньги вместо того что бы просить Ethereum сделать это за них.  
Так же, они были обеспокоены о всех этих деньгах. Из новостей типа "двадцать миллионов долларов украдено" или "мой друг отправил восемь сотен тысяч долларов на ничейный адрес и теперь деньги там и никто не может их потратить".

**christian**
В натуре чувак, ты серьезно? Восемь сотен тысяч долларов? Елы палы.

**synth**
Ага, если кто то сделает ошибку в адресе то эти деньги застрянут там без возможности их забрать обратно, и они типа "как мы вытащим их обратно?". Потому что у них ошибка со скриптовым языком или что то подобное.

**christian**
Точно, я уже слышал об этом. Да есть эта большая проблема с ICO, эта огромная проблема, особенно с хардвэрными кошельками. Я знаю точно о чем ты говоришь, это имеет смысл.

**synth**
Ага и некоторые денежные инциденты, количество денег. Это типа "Ох я потерял биллион долларов". Для Bitcoin это норма, я мог бы владеть кошельком с пятью тысячами Bitcoin-ов на нем и могло бы опс, я случайно удалил его. Вроде ох я не могу найти где я его оставил, и это на самом деле... потеря миллионов долларов экспериментируя с крипто это нормально, но в бизнесе [у них есть правила]. И если у вас рабочая электрическая сеть, и существует множество законов о том как начисляется суммы для оплаты пользователям, и в случае если сумма превысит 0.3%, то с вашу компанию могут оштрафовать на миллион долларов. И этим компаниям нравятся блокчейн технологии, но им не нравится отсутствие надежности. И это не имеет смысла держать всю информацию мира на один гигантский блокчейн и заставлять всех загружать сотню терабайт информации. Это просто не имеет смысла делать это.
Мы выделяем каждому приложению собственный блокчейн. И наша платформа может запустить миллион блокчейнов и это очень интересно. В Делавере есть закон что если ваша компания, маленькая компания, зарегистрирована в этом штате, то вы можете зарегистрировать сток на блокчейн. И если ваш сток на блокчейн... вроде маленькой пекарни в Делавере и вы открыли компанию и выпустили акции. И люди смогут покупать и продавать ваши доли на блокчейн. Это очень просто и без дополнительных сборов. И вот так небольшая пекарня может стать публично торгуемой компанией которая хочет поднять деньги. Если они захотят продавать акции компании и пекарня будет приносить прибыль, то цена акций может подняться в цене, и это очень интересно, и для этой компании мы сможем выделить собственный блокчейн. Вот ваша собственная биржевая книга, и вам не нужно посредника. Вот ваш блокчейн. Мы можем сделать тоже самое для десяти миллионов других компаний в Делавере и им всем нужны свои блокчейны. Они не хотят быть засунутыми в одну гигантскую кучу со всей информацией мира.

**christian**
Хорошо, и вы решили эту проблему параллельным запуском блокчейнов, просто вроде как когда для решения проблем с трафиком создают дополнительные полосы для увеличения пропускной способности, правильно?

**synth**
Ага

**christian**
Отлично, я понял почти все. Но вот, когда я запустил свой блокчейн, это означает что я запустил токены на этом чейне, или как?

**synth**
И это интересная часть, все сейчас одержимы токенами, потому что они позволяют запускать ICO и превращать токены в деньги, но блокчейн это всего лишь база данных. Блокчейн не нуждается в токенах вообще. Вместо токенов его можно привязать к грузовым контейнерам. Или к обслуживанию автомобилей или к доставке посылок, можно отслеживать статус доставки или время работы частей механизма точно зная когда их нужно заменять. Люди не понимают что блокчейн это, блокчейн всего лишь база данных. И когда вы говорите что блокчейн это база данных, все начинают впадать в депрессию потому что это скучно, но это то что есть на самом деле. И большинство корпоративных приложений используют блокчейн в качестве базы данных. Thomas Reuters для собственных целей, им не нужны токены. Потому что токен не имеет смысла для их целей, им интересно хранить информацию и изменять ее.
И когда вы начинаете думать о блокчейне как о базе данных вы понимаете ценность технологии для настоящих приложений.  Но если все что вам нужно сделать деньги то вам нужны токены, так как все одержимы ICO и токенами. И когда у вас есть токены, вы можете выложить их на рынок и затем прокачать цену и начать спекулировать это то для чего они нужны.

**christian**
Ага, я понял. Так Skycoin, это токен. Ethereum будет переходить, я надеюсь, на алгоритм подтверждения доли (PoS) с введением в действие Casper, вероятно в 2018-2019. Как работает Skycoin? Нужно ли майнить токены? Есть ли какое либо требование подтверждения доли? Или мастернод технологии? Или что нибудь индивидуальное?

**synth**
Совершенно новое, это следующее поколение.

**christian**
И так, как заработать Skycoin помимо вкладывания денег на покупку и накопления?

**synth**
А ну хорошо тут два вопроса. Для Skycoin, мы не хотели что бы люди контролирующие консенсус соперничали за контроль сети в целях получения максимума платы за транзакции, потому что мы наблюдали за тем что происходило внутри сети Bitcoin; то как майнеры делали деньги на транзакциях держа сеть в заложниках и искусственно завышая цены. Один из майнинг пулов спамил блокчейн микротранзакциями сеть годами в целях получения больших выгоды на транзакциях. Майнеры, и это их бизнес, и их интересы отличны от интересов сообщества, и мы хотим избавиться от этого. Для того что бы избежать этого, нам пришлось избавиться от майнинг наград и платы за транзакции. Потому что если майнеры получают награду за транзакции, то они будут бороться за контроль над консенсусом и это приведет к появлению одной или двух огромных компаний контролирующих сеть.

**synth**
So we created this new consensus algorithm called Obelisk, it’s sort of a web of trust. You have a consensus network and each node has a public key and each node subscribes to other nodes. It has a trust list of people, for instance if you know me personally you can add my public key to your trust list and the nodes subscribe to each other and they publish messages. Through this process, it’s actually a very old algorithm from the 1980s, the nodes all reach global consensus on what the current block head is. This type of mining doesn't require a lot of electricity. You could run it on a 30 watt cell phone processor. You don't need to have 600 gigawatt power like the Bitcoin mining network rigs. This is a much more efficient, much faster type of consensus process, but it does it in a completely different way. We have some whitepapers, but we have to write a sixty page whitepaper to go over more the implementation specifics because they matter a lot. Because most of the attacks aren’t actually an algorithm and they’re not the math it’s about how the thing is implemented. So since we don't have mining rewards and we don't have transaction fees, we are forced to create all the coins in the genesis block. And this was a problem because a few years ago people would always say “well that's premined!” Now people are sort of used to premined. They don't call them premines anymore it’s just the way it’s done. We had to figure out a way to distribute the coins fairly, so instead of just running this machine and doing mining and like blowing electricity like throwing money in a pit and burning it, we tried to find ways that people can receive coins for providing services that people are willing to pay for. One of the applications is Skywire, which is sort of a decentralized ISP where people will receive coins for forwarding packets. So once that's up, that’s going to be the primary method for distributing the rest of the Skycoin.

**christian**
Ok that makes sense because there has to be a way to distribute it, either manually or... so who is in charge of the keys to the master wallet right now? Is it a group of developers, what you have nine out of twelve signatures or something?

**synth**
Yea, It’s actually worse than that. It would’ve been better if it were nine out of twelve but it’s unanimous, so whenever we say we are going to distribute another million coins we have to get all of the developers to agree; which is why the distribution has been so slow. Because you have one guy who says, “well I don’t think that’s a good use of the coins and we shouldn’t do that etc.” Basically the community was screaming loud enough for enough years that it forced us to distribute this many coins on a set schedule and we finally found an agreement. I don’t think that it’s aggressive enough. I would’ve preferred to distribute 50% of the coins, but we have an agreement to get up to 30% and then to do 5% per year for the next fourteen years.

**christian**
So right now, I’m sure that you are paying people for work in Skycoin. Wait let’s slow it down here, coinmarketcap says one hundred million Skycoin? Is that right?

**synth**
No, well actually there is one hundred million, but only twenty million of them are spendable because they are time locked.

**christian**
Oh I see.

**synth**
That’s actually wrong, they haven’t updated this. The maximum supply, the total that will ever exist is one hundred million. Skycoin has six decimal places before the zero. If you have one million coins, you have 1% of the coins and then it goes six decimal places to the right of the zero. So this is a really human number because I didn't like the twelve zeroes or the 0.05969785 where you screw with the zero and you don’t know if it’s twelve zeroes or eleven zeroes or how many digits the thing is. So there’s one hundred million total and the reason that number was chosen was that one million coins is exactly 1% of Skycoin. The maximum that will ever exists is one hundred million. The total that exist right now that are spendable is actually less than twenty million, but coinmarketcap for some reason hasn’t updated and it still says one hundred million.

**christian**
Yea it only says circulating supply of like six million.

**synth**
Yea, and then six million have been distributed.

**christian**
Well let’s slow down, so in terms of how the coins get out right now. There’s an organization of developers and they are choosing where these coins go. Now, so there are strategic partners, I know you said Skywire, there are projects associated with this. Are there any other modes to get in and get coins other than buying on the exchange right now?

**synth**
Well you know buying them, doing work, bounties, translations, software development. For the coins, we have to distribute up to 20% and the next 10% are reserved for mining rewards so those will be distributed to the early people running the Skywire nodes. After the 30%, there’s a time lock and there’s a maximum of 5% per year of coins being released from that. So it will take fourteen years to get to the rest. So, essentially there is only thirty million coins and then the rest of the coins are going to take like two decades to get out and I don’t even think that they are going to be distributed at the maximum rate that they have been unlocked. We have twenty million coins unlocked right now and we have only been able to distribute six million so far and we’re distributing as fast as we can. For distribution, there are two major things: in two weeks we are launching an OTC market and we are going to start putting up ten Bitcoin per day of Skycoin on the OTC market so that the whales and the traders can start getting the coins more easily. So one of the complaints that we’ve have is that Skycoin is listed on cryptopia but nobody can buy it because nobody is selling the coin. So if you wanted to buy twenty Bitcoin worth of Skycoin, nobody will sell it to you. So there’s no trading because  you have a market and nobody will sell it to you at the market price.

**christian**
I mean, mine are sitting in a private wallet. I don't even know why they are even on exchanges at all right now. I mean I guess people need to spend their money, some people work in crypto like you have to move the coins. Anyways, so let’s keep going, so how are these coins getting out?

**synth**
Well this is very interesting. So we have some whales and they will buy twenty dollars a day, fifty dollars a day, two hundred dollars a day and they only buy but they won’t sell. Because the attitude is, if there is a coin and it can get listed on a larger exchange or it’s launching all this stuff then they’re expecting the price to increase in the future. They’re like why would I sell now if I could for 150x more in a year from now or six months from now. So we have a lot of really long term holders and they are just taking the coins, putting them in cold store, and they never leave cold store. We tracked down the cryptopia wallet and basically less than like 4-6% of the total Skycoin ended up back on the exchange and there are so few coins on the exchange that you can't day trade on it. So this is a problem with liquidity, because the traders want to trade and they can't trade because there isn't enough depth on the order book. We are trying to get through this distribution phase to add more liquidity and get the volume up a little bit.

**christian**
Do you think Skycoin will have their own exchange one day?

**synth**
We have github.com/skycoin-exchange, so we actually wrote our own exchange. This is a dark net distributed federated exchange and we wrote it about a year ago, but we haven’t had time to fix it and get it into production. In the end, we ended up scrapping that and then using a third party exchange. Parts of that exchange became the OTC market so now we are gonna have the OTC market and I think that eventually we will have that exchange up. It's more like a dex.

**christian**
Yea, I mean its only going to be for the super hardcore guys right?

**synth**
No no, it's really easy

**christian**
Oh it is? ok

**synth**
So with Bitcoin, when you are trading on an exchange... since Bitcoin can take over an hour or twenty minutes to deposit money, you have to take your one hundred thousand dollars of Bitcoin and leave it on the exchange. Sometimes it gets stolen. For our exchange, we didn’t want our users taking a lot of money and having the exchange hold it for them. So with Skycoin, the transaction time is as low as two seconds. If you want to make some trades, you just deposit the money in two seconds, you make the trade and then you withdraw the money back to your wallet in five seconds. We have this exchange that doesn’t actually hold any money, which is a pretty good design. You can actually hit a button and it will withdraw all of your money from the exchange right back to your wallet. So the client and the server are actually integrated and it’s all public key based, so there’s no username, password, or email. It’s just a Skycoin public key that identifies you to the exchange and the order book. Also, if your account is idle for like a year, or a month, when you want to create your account it gives you a deposit address to return the money so that if you close your account it will just send all of your money back to this default address. So it’s a very interesting design, its not like an http exchange, its like an application that you run locally and it opens the web browser. It connects through the darknet to the order book backend. Anyways, I could go on for hours about that.

**christian**
Yea I hear what you’re saying. So I mean, what got you into this whole thing? I mean this project itself as you said it has been around for a number of years. What specifically was your sort of jump into this?

**synth**
I’ve been doing this like forever. It feels like fifteen to twenty years for me. I was in the early like crypto anarcho-capitalists like underground newsgroup servers. I was one of the first people to hear about Bitcoin and I was stuck fixing the bugs. When Bitcoin was released and it wouldn’t compile on Linux because the guy was just like svn, there was no way to submit changes so you would fix this bug and they didn’t have Github so you couldn't do a pull request. So you would make a fix and then nobody would actually incorporate the fix into the repo, then next week somebody would end up having that same problem again. As far as crypto, I’ve been doing crypto and networking for awhile... like I did a video game, I worked at a hedge fund, I did early Bitcoin stuff. Now, I’m involved with like fifteen coins I think.

**christian**
I’ve always been very curious like because I you know I’m like most white guys in their mid twenties, buying Bitcoins and storing it in wallets, doing some cool stuff with coin interview and stuff, but not anything like... how do you even begin to?? I always try to get into programming but I could never—

**synth**
—adderrall [laughs]

**christian**
Yeah.. so where do you start? So you say you’re fresh out of high school, you know I can go to the military, or go to college or I can start poking out on the web and getting into some sort of code, especially with crypto and coins. How do you learn how to code and fix things and do that? Did it just come natural for you?

**synth**
No... Well you start with math and you start hard things like video games, like puzzle games or something, and then you go start programming. I started programming at like eight or something in logo. I had an apple two and this program with a turtle and it was like “turtle go right, turtle go forward” and like drawing stuff. After college, I started doing websites and I created a bot that would spam up one hundred thousand websites to get ad revenues. It would just take this database and generate all these websites and it would catch google search results and people would come in on mobile and accidentally click the ads and I would make like twelve cents or something like that [laughs]. I had like a whole botnet going and that was in PHP. Then for some reason, I started making a video game in Javascript and then after I realized Javascript was too slow I moved to C++ and I ended up making a 3D video game. That took like two years. Then I started doing like hedge fund stuff which is the same stuff as the video game, you have a database and you have to do all these fast operations and networking. We were using Amazon EC2 when it just came out and we were renting like fifteen thousand servers from Amazon and blowing like seventy five thousand dollars in one go [laughs] you know? Ummm and then Bitcoin and then I started getting into crypto because I was fixing the bugs in Bitcoin and I was dealing with things like, “oh does it compile, or why don’t they have compressed signatures enabled?” and then I got pulled into doing this audit for this other crap you know it just keeps going and going and going and going.

**christian**
Yea so its kind of like a snowball effect, you just kind of start messing around and then you just get into it because I’ve tried reading books on Python and I’m like okay—

**synth**
[laughs]

**christian**
--like this hurts

**synth**
The books are shit. You just have to go in and figure out a game you want to make like flappy bird or something. Like ok how do I draw something?

**christian**
You know I don’t play games I used to have like a gaming addiction so I stay away from that shit now.

**synth**
[laughs]

**christian**
Here’s another thing, you can't fucking do everything in life either. Some people are not fucking like renaissance geniuses like I cannot do thirty things perfectly. We’re not fucking robots. Everyone has their own specialty. I really should ask that question more though because it’s a rabbit hole right? Like there’s so much fucking shit you can do it’s almost infinite right? It’s just code, as long as you can think it you can do it right?

**synth**
Theres this guy who made this thing like Worm Online. He started a project in college making like an MMO and its sort of like Morrowind. He spent like fifteen to twenty years doing this and he essentially wrote like World of Warcraft by himself. [laughs] It’s pretty funny. You just start on it and it never ends, and thats how Skycoin has been. We’re not even finished with one thing and we’re starting like five more projects. Like, “Oh now we need to double the developers, oh we need to double the teams, more projects etc.” For example sometime last week, we decided like oh were gonna have a hardware wallet now; so we just hired a guy who does pcb boards and he designed a pcb board and we just had it sent to the factory and he needs to solder the components. Then we have to flash the firmware and do testing and then in two weeks we'll have a hardware wallet and then we have to use a factory to start shipping out these hardware wallets. Then the other people on Skyledger, like we have Solarbankers and we have spaco.online, which is some like distributed file storage project. All of these coins on Skyledger, they want branded wallets, so we have to customize the wallet with their logo on it and something like that. We have a sports betting company and we have a forex company who is launching a coin too and they want gold plated, you know like a solid gold hardware wallet, so now its like hey how do I find a machine shop who does a solid gold casing wallet [laughs] and it just keeps going and going and going you know?

**christian**
Right, so in terms of going and going and going, with digital currency there really is no end to this right. People are going to find a way to monetize every single fucking thing that they can that make sense, because some things just don’t fucking make sense to monetize.

**synth**
I think its very funny because we are seeing like ten ICOs per day and most of these projects... it doesn’t make sense to have a coin, like theres an instant messenger and they’re launching a coin and they want to raise one hundred fifty million dollars on an ICO. It's like ok now I have messenger coin. So it’s like, “oh what do we need messenger coin for?” “Oh you want to send somebody a message on your cellphone and it costs coins!!” So every message would be like ten coins right and I’m like this is retarded. They are trying to take things that you are already getting for free and then attach coins on it so you can have an ICO and it doesn’t make any sense at all. These coins are not... they are just apps they are like app coins.

**christian**
So like me, I don’t understand the app coins. I run some of the dynodes for the Duality Project and for me its always cooler for someone who’s not really interested, you know I can follow tutorials and shit. For me, setting up the nodes or the validators and staking the wallets that for me where it makes a lot more sense to put your time and attention into rather than just... I mean yea I’m gonna send a message to my friend and I’m gonna get like .000001.

**synth**
[laughs] and you’re gonna get paid for messaging your friend? Oh yea and this, “we’re gonna get paid to watch ads bullshit thing” like, oh yea people watch ads so were gonna pay them money to watch ads and then this company would like spawned ten thousand bots to collect the points and then try to redeem them for like Amazon gift cards [laughs].

**christian**
Yea theres like really hard questions. I wish I always had like a programmer on our show so I could ask the most ridiculous questions. because that how I was like.. now that you mention it I interviewed Bitclave and they have some really cool devs on their team but like cant you just get bots to run on the...

**synth**
[laughs]

**christian**
Like how do you protect against botnets? Like those are just malicious nodes right?

**synth**
Substratum... ты же знаешь, что я не должен говорить о людях гадости, но это довольно забавно. У них есть сервер, и они говорят, что вы можете запустить свой сервер, и вы будете получать монеты каждый раз, когда кто-либо обратится к вашему веб-серверу? Так почему бы мне просто не запустить бота и не открывать мою страницу сто раз в секунду и просто получать монеты в кошелёк? Такие компании, как Google и Facebook, тратят миллиарды долларов в год, пытаясь остановить этот тип мошенничества, и они не могут остановить его, это практически невозможно. Это забавно, потому что Facebook продавал на сотни миллионов долларов рекламы на  продвижение в правой панели Facebook, и вот что происходит: люди тратили в рекламных кампаниях по 50 миллионов долларов, но в некоторых из этих компаний была аналитика. Они начинают говорить: «Ну, откуда взялись эти IP-адреса?». И они выяснили, что 50% трафика из рекламы в Facebook поступает из Китая, и все похожи друг на друга: «Эй, погодите, но Facebook заблокирован в Китае? Почему мы получаем все это? ». Затем они понимают: «О, это боты». Так что, как с Facebook, пока рекламодатели готовы платить за бот-трафик, им все равно, но когда они узнают правду, будут проблемы.

**christian**
Они могут получить иск, правильно?

**synth**
Ну, вы бы просто направили свои рекламные деньги на другую платформу.

**christian**
Ну, вы могли бы пернаправить рекламные деньги, но вы не собираетесь подавать долбанный иск к Facebook, чтобы здорово потрахаться с ними. [смеется] Я имею в виду, что это только когда вы все знаете, я думаю, что весь ЕС должен был подать в суд на Amazon или Google, это должен быть конгломерат, например пятьдесят гребаных стран, чтобы выдрать назад часть из своих гребаных платежей, и на самом деле даже не так много денег они получат назад.

**synth**
Их маржа очень маленькая, так что, если у вас есть рекламный бюджет, и вы проводите небольшую рекламную кампанию, которая едва зарабатывает деньги, может быть, около двухсот тысяч в год. ОК, как вы говорите, избавьтесь от этой чертовой статьи, поджарьте этого парня, они не хотят потерять этот рекламный бюджет, потому что их маржа очень маленькая. Они фактически теряют деньги в течение многих лет. «Нью-Йорк Таймс» пытается поставить пейволл (платную подписку), а «Вашингтон пост» не зарабатывает деньги и должна быть продана.

**christian**
Итак, давайте идеи дальше, про эту фальшивую новость. Я думаю, что нынешнее расследование, Мюллер, сейчас они обвиняют людей. Кампания Трампа. Это чертовски похоже на большие новости, так как Skycoin поможет с поддельными новостями? Это как атака Сибиллы, правильно? Я могу взломать всю пропаганду всей гребаной страны и заставить выбрать президента, мы должны разобраться со всем этим дерьмом.

**synth**
В принципе, есть группа людей, и они хотят контролировать, какие статьи и рассказы читают люди. Так, например, есть люди, которые владеют банками и нефтяными компаниями, и они владеют промышленностью,  заводами, большей частью земли. Одна семья может владеть почти одной  третью западного Нью-Йорка, а некоторые из этих семей владеют целыми городами. И на самом деле не ясно, принадлежит ли все одному человеку, но они очень тесно связаны или вступают в брак, может быть, это четыре семьи, но все они женаты друг на друге, поэтому у них разные имена, но это одна и та же группа. И традиционно они контролируют средства массовой информации, поэтому, если вы владеете банками и владеете фабриками, то вы трудоустраиваете всех людей в каком-то городе, вы также контролируете газету. Поэтому они привыкли иметь эту власть над тем, что публикуется и что не публикуется, и из-за Интернета они эту власть сейчас теряют. Другая ситуация, если вы являетесь национальным государством, таким как США, тогда правительство будет иметь некоторый контроль над New York Times, и каждый проснется утром, и у них будет одна местная газета для своего города, а  еще одна национальная газета, поэтому есть две газеты, и у них не может быть больше информации. Так что правительство придет и скажет: «Ну, ок, война во Вьетнаме, пусть скажут это и это, и не перейдут туда и бла-бла». А сейчас они в основном теряют контроль над информацией, которую люди получают в средствах массовой информации, и Google пришел, есть Google, Apple, Twitter,  они в основном стали средствами массовой информации; например, Google - это медиа. Если вы перейдете к новостям Google, именно там люди получают свои новости, поэтому эти очень богатые, сильные группы, которые владеют этими компаниями ... они как бы теряют власть, потому что они владеют New York Times, но не получают ту власть, которую они имели прежде, влияние. Таким образом, они практически прижали Google, это очень забавно, все эти корпорации вытащили, я думаю, все семьсот - восемьсот миллионов долларов рекламных денег. Они сразу же вытащили деньги из Google, чтобы показать, насколько они сильны. Они говорят, что это наши деньги, и если вы хотите наши деньги, вы должны делать то, что мы говорим. Затем выходит генеральный директор Google Эрик Шмидт, он выходит публично, и он говорит, что это не цензура, мы просто удаляем результаты поиска.

**christian**
Что??

**synth**
[смеется] Итак, как вы думаете, это не цензура? Это очень забавная цитата Эрика Шмидта, потому что Google - это компания, и у них есть соотношение цены и прибыли, для цены на акции. Если они получат один доллар денег, их акции растут на шестьдесят долларов или двадцать долларов или что-то еще. Поэтому, если вы вытаскиваете шестьсот миллионов долларов из Google в год, это удаляет шестьдесят миллиардов долларов стоимости акций из кармана владельцев, поэтому они в основном должны делать то, что им говорят. Это в точности то, что происходит, и вы это сделаете, если вы хотите наши деньги, вам нужно делать то, что мы говорим. Европейский союз сделал то же самое, но политики в Европейском союзе выписали штраф. Они сказали, что ты будешь делать то, что мы говорим, или мы собираемся оштрафовать тебе на четыре миллиарда долларов. Вот что происходит. Если вы являетесь сильной группой в такой стране как Франция или Германия, вы хотите контролировать свое население, и вы хотите контролировать свои СМИ. Вам не нужен Google, который является американской компанией из Сан-Франциско, вы не хотите, чтобы они контролировали ваше население. Потому что, если вы контролируете Google, вы контролируете, кто избирается, вы контролируете, интересуются ли люди беспорядками или нет, вы контролируете, сосредоточены ли они на спортивной игре или сосредоточены на каком-то скандале в педофилии. Вы в основном контролируете все внимание толпы. Таким образом, эти политики отправятся в Facebook и Google, и они скажут: «Вы поддерживаете мою кампанию, и вы не будете поддерживать его кампанию, я хочу только негативного к нему отношения», и если у этого человека есть власть, он может отправить регулятора в Google или Facebook и оштрафует их на миллиард долларов, если Facebook не сделает то, что они говорят.

**christian**
Что? Я этого не понимаю, штрафуют за что?

**synth**
За что угодно, правительство может вытащить причины из своей задницы. Они могут сделать любое дерьмо. Говорят, что Google слишком велик, и мы оштрафуем вас  за то, что слишком большие. Причины, которые они создают для того, чтобы оштрафовать эти компании, просто смешны. Это похоже на то, что «Google слишком велик, он слишком успешный, поэтому мы должны наказать вас за монополию». Но это не монополия, потому что вы можете просто переключиться на Yahoo, вы можете переключиться на Bing, но никто не использует их, потому что они не так хороши. Так что это не монополия, никто не заставил вас использовать Google, приставляя пистолет к голове. Люди просто предпочитают использовать его, потому что услуга лучше, но Европейский Союз может прийти и сказать, что у вас слишком большая доля на рынке, поэтому мы должны разбить вас на более мелкие компании или что-то в этом роде. И они это делают, помните? Они сделали это с Microsoft. Когда Microsoft становилась довольно мощной, правительство вошло с федеральным иском против Microsoft. Они сказали, что собираются разбить компанию на шесть или восемь штук, но: «О, если вы сделаете то, что мы говорим, мы можем помочь вам здесь и избавиться от этого», а затем Microsoft легла в постель с NSA, и правительством, и отделом обороны,  теперь они являются одним из их мальчиков. Поэтому, если вы доберетесь до определенного уровня власти, вам, в конце концов, нужно будет войти в эту систему и сотрудничать с этими людьми или они будут давить вас, как муху.

**christian**
Итак, у нас тут сложилась целая картина, а сейчас мы возвращаемся в крипту, потому что, хорошо, вы не можете остановить меня, потому что вы не знаете, сколько у меня денег, вы не знаете, кто я в постели, вы не можете отслеживать все эти IP-адреса.

**synth**
То, что происходит, очень интересно, Китай хочет контролировать свое население, Европейский союз хочет контролировать свое население, Соединенные Штаты хотят контролировать свое население, поэтому теперь они жалуются, что Россия идет в Соединенные Штаты и покупает рекламу и влияет на выборы. Они в основном жалуются: «Мы хотим контролировать наше население, мы не хотим, чтобы Россия вмешивалась в наши дела». Итак, что будет происходить довольно скоро: я думаю, что через десять-пятнадцать лет у вас не будет глобального интернета. У нас был такой период, когда был глобальный интернет. Теперь мы получаем китайский интернет. Мы получаем российский интернет. Мы получаем североамериканский интернет. Мы получаем интернет  в Европейском Союзе. Мы получаем бразильский интернет. Если вы находитесь в китайском Интернете и пытаетесь использовать Dropbox или Google Drive, они не работают, потому что правительство блокирует их. Вы должны использовать диск Baidu, через него китайское правительство может получить все ваши данные. Если вы находитесь в Соединенных Штатах, тогда у вас есть компании, такие как Dropbox и Amazon. Поэтому, если вы передадите свои данные Dropbox, у Amazon появляются ваши данные, а затем через Amazon - у правительства Соединенных Штатов. Таким образом, правительство Соединенных Штатов хочет, чтобы люди шли в Dropbox, поэтому они, возможно, будут замедлять или блокировать часть зарубежных услуг, таких как Baidu.

**christian**
Подождите, давайте остановимся на секунду, прежде чем продолжить. Итак, мы говорим о данных, есть определенные злонамеренные люди, которые хотят взорвать гребаные здания и прочее дерьмо, это вроде реально, это на самом деле происходит, но почему правительство вообще хочет ... Я думаю, вопрос будет таким, что вы думаете о надзоре? Потому что это действительно надзор, и в определенной степени вам нужно наблюдение, ведь вы не можете просто прийти и уничтожить целый городской квартал, а они могут это сделать, если не ... не так ли?

**synth**
Ну, они не хотят ... Я имею в виду, что это очень интересно, потому что, если кто-то идет и взрывает здание, они увеличивают свой бюджет, поэтому им жаль, что, похоже, больше не взрывают зданий. Потому что у них есть эти огромные бюджеты, и они нуждаются в очередной террористической атаке каждые полгода, иначе люди начинают говорить: «Почему мы тратим все эти деньги?» Я имею в виду, что есть хорошие люди, но в основном, я думаю, речь идет о деньгах. Я думаю, это все, что их заботит.

**christian**
Верно, хорошо. Хорошо, тогда продолжаем.

**synth**
Итак, у нас был глобальный интернет, который был классным, и теперь, поскольку каждая страна хочет контролировать «своих» людей, и следить за своими людьми, и удерживать другие страны от контроля над своим населением, и контролировать выборы, и быть шпионом на них. Так что, если вы используете Dropbox в Бразилии, тогда правительство США получает копию всех данных, которые производят Бразилия, а затем бразильское правительство говорит: «Нет, эти данные нам нужны и мы не хотим, чтобы их имело правительство США». Поэтому они начинают блокировать Dropbox, или они принимают закон, говорящий, что если компания работает с этой страной, то данные должны оставаться в стране. Китайское правительство не закрыло Apple и iPhone. Они просто сказали Apple: "Если вы хотите работать в Китае, вам нужно построить центры обработки данных в Китае, и вам не разрешается управлять этими центрами обработки данных. Мы сделаем это для вас на наших серверах, а вы заплатите нашим государственным компаниям за работу с серверами, и все данные для китайских пользователей iPhone останутся в Китае". Так что теперь Apple должна строить эти центры обработки данных, потому что китайское правительство не хотело, чтобы правительственный чиновник использовал iMessage и данные возвращались в Калифорнию, а затем правительство США могло шантажировать кого-то записями в журналах чата iMessage или что-то в этом роде. Итак, вот что происходит, интернет балканизируется странами. Вот что мы делаем со Skycoin, создаем еще один слой поверх Интернета, практически новый интернет Skywire, и у нас будет Dropbox и Twitter, а также некоторые социальные медиа и обмен сообщениями, и он разработан так, что он действительно не может быть заблокирован границами. Он разработан таким образом, что пользователи смогут контролировать свои собственные данные. Он не будет контролироваться третьей стороной, такой как Facebook или Twitter, но пользователи фактически будут владеть данными.

**christian**
Итак, это похоже на шаг в прошлое, как ... есть Тор, есть ITP, это Freenet.

**synth**
Это совершенно новый интернет, это не просто виджет.

**christian**
Хорошо, так что это далеко за рамки тех программ, которые вы можете запустить сейчас, чтобы обойти цензуру и тому подобное.

**synth**
Да, например, твиты, мы сохраняем все наши твиты в Twitter и Twitter предоставляет серверы, но поскольку они предоставляют серверы, они контролируют данные. Поэтому, если китайское правительство хочет заблокировать Twitter, они просто блокируют серверы Twitter, а затем вы не теряете доступ. С нашим сервисом, ваша идентификация осуществляется через открытый ключ. Ваша идентификация похожа на биткойн адрес. Если вы хотите опубликовать твит, вы подписываете его своим открытым ключом. Вы берете свои данные, подписывая их своим открытым ключом, и публикуете его, а если тысяча человек подписались на ваши данные, все они получают копию. Поэтому, как только одна копия данных поступает в страну, она просто копируется в одноранговую сеть. Невозможно заблокировать это. Нет веб-серверов. Третьей стороны нет. Нет корпорации, которая владеет вашими данными. Никто не может запретить или заблокировать вас. Таким образом, это дает людям большую свободу, но есть такие вопросы, как ...

**christian**
Так как же остановить человека, который просто хочет быть подобно... я не знаю, считает, что это забавно - рассылать детское порно по всему миру. Некоторые люди чертовски отсталы.

**synth**
Вы помните, goatSC, парень, который раздвигает анус руками, и люди просто спамили его всюду в 2002 году, вы помните это?

**christian**
Как же цензура сообщества, ну, да, цензура, потому что люди не хотят видеть это гребанное дерьмо. Итак, как вы подвергаете цензуре глупых участников своей сети?

**synth**
Невозможность цензуры заложена в дизайне системы, но вот что мы делаем, у вас есть подписные листы. Это ваши друзья, это те, кого вы интересуете и люди, которым вы доверяете, поэтому вы получаете только нужные вам данные. Итак, есть парень, отправляющий goatSC, просто забаньте его. Надеюсь, никто не подпишется на него. Это больше похоже на сеть доверия, и она основана на сообществах.

**christian**
Это имеет смысл. Это тот ответ, о котором я даже не думал, что это возможно. Это как я получаю информацию в настоящее время. Единственное, что я читаю, это то, что входит на мой адрес электронной почты. Мое внимание будет обращено на людей, которые со мной свяжутся, а потом, может быть, как на первой странице, как мировые новости sub-reddit, где я просто читаю все заголовки, чтобы оставаться в курсе. Это сообщество, потому что вы просто блокируете всю другую ерунду. Как кто-то использует Facebook?

**synth**
[смеется] Я знаю, похоже, что они умирают. Есть такая модель, которая показывает, что если около 1% людей уйдут, остальные пятьсот миллионов человек исчезнут, как гигантское стадо, и они это знают. Они на самом деле похожи на MySpace. Люди приходят, они делают это некоторое время, и они уходят. Все классные парни не на Facebook, классные парни на этих новых платформах, и они пытаются подобрать прикрытие и восполнить с помощью бот-трафика и тому подобного.

**christian**
Считаете ли вы, что это из-за дизайна, инженеры чертовски глупы? Или я думаю, что более логичным является то, что они взяли венчурные деньги, они взяли правительственные деньги, и теперь они не могут шевелиться также быстро, как раньше. Это похоже на: «У нас есть серьезные обязательства по выплате дивидендов акционерам в течение следующих пяти лет».

**synth**
Для людей, когда это начиналось, все было круто, им нравилось: «О да, я могу делиться фотографиями круто, я могу и т. д. и т. д.». Но действительно ли вы хотите сидеть перед Facebook в течение всего дня, рассматривая фотографии других людей? Например, вы не хотите кататься на сноуборде, или я мог бы пойти купаться, или я мог бы пойти на альпинизм, или я мог бы сделать видеоигру. Люди хотят делать что-то со своими жизнями. Они не хотят сидеть в Интернете и нажимать на фотографии весь день, а это действительно основная аудитория Facebook, люди, которые сидят там, как зомби, весь день.

**christian**
В основном, я думаю, они действительно обращаются к самому маленькому общему знаменателю, и это прекрасно, потому что это законы рынка, но когда дело доходит до целого поколения, которое разумно; это своего рода, ну, вы должны быть все более и более умным каждый долбаный день, чтобы идти в ногу со всей этой чертовой штукой. Я имею в виду вот что это такое ... Я просто подумал кое о чем, когда вы говорили о хранении данных. Я имею в виду, что скоро люди собираются запускать собственные спутники, а потом они просто ...

**synth**
Да, мы хотим сделать это для Skycoin. Если мы достигнем рыночной капитализации в миллиард долларов, мы определенно хотим сделать это для Skycoin. Это стоит всего лишь десять тысяч долларов.

**christian**
Так кто-то просто спросил в чате, насколько должна быть велика сеть Skycoin, чтобы было бы невозможно для правительства закрыть ее?

**synth**
Я думаю, что это могут быть два человека. Можете ли вы закрыть Bittorrent? Как кто-то делится чем-то на Bittorrent? Правительство пытается это сделать уже десятилетие. Они установили на сотни тысяч и миллионы долларов оборудования, чтобы выяснить, к кому подключается ваш компьютер, и если вы используете Bittorrent, если используете VPN, отключить его или замедлить, и они потерпели неудачу. Они не смогли, даже китайское правительство, хотя потратили на это много денег. Они контролируют свои границы, интернет-провайдеры являются государственными, у них есть backdoor на кабельных модемах, но VPN все еще работают большую часть времени. Это непрактично, потому что, если они закрывают одно, люди просто будут делать что-то другое. Это проигравшая битва, если правительство лезет туда слишком сильно. Они предпочли бы контролировать это. Например, если вы закрываете все бирманские биржи в стране, люди начинают торговать биткойном на месте со своими друзьями, оплачивая наличными. Вы не можете отследить еэто. Правительство предпочло бы, чтобы вы переместили все свои биткойны через Coinbase, чтобы они могли видеть, сколько денег вы отправляете, к кому вы их отправляете, как часто кто использует его, они хотят получить эти данные. Если они закрывают все биржи биткойна, люди просто переходят на наличные, тогда они проиграли.

**christian**
У меня нет проблем с людьми, платящими налоги. Да, это отстой, что правительство может просто получить судебный приказ и сказать мне отдать мот записи, верно? Но у них есть настоящее гребаное законное оружие, они могут приставить пистолет к вашей голове. Вы хотите, чтобы вас застрелили в затылок, или вы можете просто передать свои деньги, и мы можем понять это? Как если бы у вас был судебный приказ о ваших финансах, вы в каком-то дерьме, они знают, кто вы, они знают ваше имя, они знают, сколько денег у вас на счету, кто эти деньги присылал, какой чувак. Конечно, я знаю, что у них есть широкая сеть, чтобы видеть отношения, такие как программа тонкой нити, разработанная в девяностые годы NSA. Они могут видеть весь трафик и куда он идет, но они ищут очень плохих парней.

**synth**
Эхх, это зависит, это очень забавно, потому что некоторые из этих хакерских фирм, NSA, люди всегда вроде: «Охх, NSA», но все реальные вещи находятся в частных секторах. Таким образом, у вас есть эти огромные компании, никто и не слышал о них, и это те, кто делает грязную работу, потому что правительство не может этого сделать, потому что у них есть правила и законы. Если вы частная компания, вы можете делать все, что захотите, и вас эти законы не ограничивают, как правительство. Поэтому они будут отправлять заказы для этих компаний. Что очень забавно, так это то, что я видел, некоторые из этих компаний делают эти уязвимости нулевого дня, они охотятся за кошельками биткойна и крадут, потому что, если они украдут биткойн-кошелек, кто узнает? Правильно? Так что они такие, как мы можем избавиться от этого? У нас есть все, что мы создали, так что мы можем заработать на этом. Понимаете, это как полиция, вы едете в какую-то страну, и полиция хватает вас и они говорят: «О, мы нашли наркотики у вас», и они делают это не потому, что на самом деле хотят вас арестовывать, они просто хотят сто долларов.

**christian**
Да, это случается, и быстро переходит в человеческую природу. Некоторые люди, очевидно, являются социопатами, психопатами и тому подобное, но почему? Это так странно, почему мир ... вы когда-нибудь задавали себе такой вопрос: «Почему, черт возьми, мир такой, какой он есть?» Как вы инженер, вы программист, и почему я могу строить лучше, чем все эти гребаные идиоты.

**synth**
В смысле, лучше для кого, так?

**christian**
Верно, точно, да.

**synth**
Люди наверху. Они знают, как работает игра, и это приносит им пользу. Им нравится то, что есть. Они не хотят, чтобы это было «лучше», потому что это лучше, они его разработали.

**christian**
Это немного пугает вас?

**synth**
Я познакомился с некоторыми из этих людей, и на самом деле это довольно забавно, как будто у вас обед с этой семьей, а они сделали деньги на нефти и гражданской войне, где было убито шестьсот тысяч человек, а они сидят там за ужином, жалуясь на других людей за морями, которые начали гражданскую войну, и это плохо, потому что двести тысяч человек погибли из-за какой-то гражданской войны, на которой те начали зарабатывать деньги, но когда эти начинают гражданскую войну, тогда это большое благо.


**christian**
You see this is a fallacy because this is how the whole fucking thing comes crashing down right. I mean we’re starting to see... first of all there have been people killing each other since before the beginning of time but now there is this cascading effect where countries are fucking falling apart. That’s a little different.

**synth**
They are just looting everything.

**christian**
Yea thats the thing like the whole fucking thing is coming down and that’s a little different than just, “yea the world is a bad place etc.” What I’m getting to is like, it seems to be a little more engineered now, it seems to be methodically going in and abstracting everything out and dumping all the bullshit on people for people to deal with and thats not sustainable. That’s how we get into this whole fucking global energy crisis and that’s a whole other thing.

**synth**
So you create problems and then people react, and if people aren’t stupid they fix the problem and they survive and we get to the next level. So one example, in the UK you had this little island and they don’t have many resources, they don’t have much population and this is maybe 1800s and they are burning coal for warmth in the winter and they would freeze to death because they didn’t have enough coal. There weren't enough trees on their little island to heat them. So they are digging for coal and they run out of coal and because they have water lines, they dig deep enough and the coal mine they are digging fills with water, so some guy invented the steam engine to pump the water out. Then somebody took that steam engine and put it on wheels and then somebody put it on railroad tracks and then later somebody puts it on a plane with a propeller and the later on that gets replaced by a jet engine. So if you didn’t have the wells flooding, then people would just keep digging the coal the way they had been digging coal for five hundred years. When you run out of coal, and people’s lives depend on fixing the problem, then you see the innovation. So yea this corruption is bad, but it’s part of a cycle. We see governments cracking down and we see 80% taxes in Europe and they’re banning cash. So they’re like we are going to tax you 80-90%, all your money belongs to us, and you’re lucky we let you keep five cents. People are starving because they cant afford to heat their homes in the winter because it’s too expensive. And the government wants more and more and more and they are banning cash, but at the same time that they are banning cash, cryptos are coming in. So this is, it’s just part of a cycle and eventually it will work out.

**christian**
Yea I mean it’s funny, a lot of people think they are in control, even at the top and they’re actually not.

**synth**
No its complete chaos.

**christian**
I mean it is chaos because we are all just moving towards death. If you don’t accept that, then I am sorry for those listening but you just gotta wake up in the morning like I’m going to die some day. That should be the number one thing on top of your mind, and number two should be ok what should I do to have a good life. And if you’re a white guy like me, in the United States, whoa, you’re doing pretty fucking good compared to like 99% of the planet, but here’s the scary thing about that. Now everyone just turns around like, “well the United States has everything, or Europe is doing pretty good so I’m gonna go take their shit because they are just like pissing on me.” And that’s kind of scary because I woke up in 1990 like, hey I’m here. Oh look Desert Storm, ok 9/11, ok this is my fucking narrative. That’s another fucking weird thing like you’re born into fucking conflict.

**synth**
[laughs, mocking] “They hate our freedoms! We’re gonna fight the freedom haters.”

**christian**
I guess to bring it all back to crypto. You need tools to be able to have some fucking leverage on what you are doing. If you don’t have fucking control of the actual things that you create, then it’s fucking hell on earth.

**synth**
You either control it or someone else controls it.

**christian**
So this is going to be like a master-slave dichotomy, but i feel like the crypto thing evens that all out, so its still kind of there because there are still social Its still kind of there because there are still relationships but it isn’t so binary where its like slave-master. There’s more variation. I’m not into the whole nihilist, the Ayn Rand shit. It’s like ok dude calm the fuck down.

**synth**
This crypto thing is very funny because if you look the government says, you printed like twelve trillion dollars.

**christian**
[responding to comments in live chat] Wait we need to shout out the guy talking about white guilt. Its not like, dude, its not about being white. I realize I’m way fucking luckier than most fucking... like I’ve been around the world man. I’ve been to a lot of countries. You know go ahead man I'm sorry.

**synth**
The whole thing is they want people to feel guilty about who they are.

**christian**
Oh sure sure.

**synth**
Like, “Oh you’re white you’re etc.”

**christian**
Guilt, ok, but you also need to have some fucking degree of empathy for your fellow human being. If you have no mental, like if you have nothing to compare your shit to because you’ve never been outside of the United States. You just like, you know the whole white guilt thing is big right now but its not about being white. Ok lets take out the skin color shit, its just money, like I am way more set up than most people will ever be in their life. So if you need to feel guilty about that then ok so to speak, I’m thankful to even be in a fucking room talking about crypto at this point because its like ten, fifteen years ahead of some people at this point.

**synth**
Oh so this is uh, so you have these governments these central banks, supposedly there’s fifteen trillion dollars in fiat, like the USD, EUR, YUAN, YEN, and so on and thats the number they officially published, but theres actually all this money and nobody knows how much money there actually is. They lie. They don’t have to report the exact number. They always smudge the numbers. Every country smudges the numbers to make them look better so they can get more loans and all this other stuff. They always understand inflation and they have all these different ways of fudging the numbers. I was talking to this guy and he does some offshore stuff. Basically, they think... there’s documented like seventy trillion, so the government says there is fifteen trillion but there is actually seventy trillion dollars offshore. What’s happening now is the US government is coming in with GACTA and FACTA and the G20 and all these laws and international treaties that are forcing all of the people out of these offshore tax havens. They did the Panama Papers and hacking banks and leaking all of this information about who is storing money overseas and like Putin’s friends, the families in China, and the ruling elite in Britain and basically like saying that you can’t hide your money from us we are going to find you. So this money that is like seventy trillion dollars, is basically being forced into the US because if you are overseas, the US is actually a tax haven. The US government requires data from every other country, but if you put your money in the US, the US government will not give its’ data to any other country. So if you hide your money in the US and you are from like Saudi Arabia, if another country tries to get that money or find where it is and who has it, they’ll just shoot down the lawsuit. But if you are a bank in Saudi Arabia you have to report your data to everyone... so this moves all this money into the US dolars and whats happening though is this seventy trilllion dollars that is offshore is now flooding into crypto. You see a lot, and these people dont know how to use it they are not technically literate it is still early but we are seeing this massive flood of money into crypto. The volume is unimaginable and the crypto market is one hundred and eighty billion right now and i think that it will go to ten trillion before it pops. Deoitte said that it will be worth five trillion dolars by 2030. The growth rate is over 1% a day and it has been that way for ten years now. If you actually plot, if you take the Bitcoin market cap and you put a straight line a regression line, the slope of that line is 1% per day. The boom and the bust cyle hasnt chagned that. This is also going to be a dot com bubble and burst too because most of these coins don’t have any value, so there is a huge amount of money flooding in and people are taking advantage of that. There are fifteen different smart contract platforms. 90% of these smart contract platforms don’t have any users, so if a smart contract platform doesn’t have any users then why is it worth ten billion dollars.

**christian**
A fucking scam thats why

**synth**
And it is very funny because I saw one pop up into the top ten or something. They didn’t even do an ICO. They had no ICO, no pre-ICO. They just sold some coins to some people and just put it on Bittrex and were trading it at like a billion dollars or something. Some company I'd never heard of. And um, its like, "Our thing has scale!" but they have no users and its like why is this worth a billion dollars. So whats gonna happen is, people are gonna ride the bubble, they are gonna invest in these speculative things if the marketing is good. Then before the bubble bursts, when it's near its' peak, the smart money is going to start moving all their assets into the coins with actual value. Like you have a coal mine, you have a gold mine, you have a silver mine, you're selling sand for coins. You have an ISP, a distributed utility company, you have actual solar panels. They are going to want physical infrastructure, like collateral that actually ensures these coins. Then we are going to have a bubble in these asset or commodity backed coins because all of this money has nowhere to flee. The other thing is, the money only flows into Bitcoin. If you bought Bitcoin at a penny and it goes to six thousand dollars, you can't sell one hundred fifty million dollars of Bitcoin. They don't even want to be taxed on it. They don't know if they are going to have to pay a 30% tax, a 10% tax or a 15% tax, they would actually rather just sit on the Bitcoin. No one actually ever sells the coins. It comes in they make the money and they just dont want to deal with the problems of running it back into paper money.

**christian**
It's not really.. it's not that there is a huge problem because there is no money moving. There is no money moving, there is no economy. Ok, you have a whole pile of shit, cool. Are you gonna move it? No you're not? Ok I don't give a fuck then.

**synth**
Well you can buy houses with it now--

**christian**
--so what do you think about the royal mint gold token? The royal mint england should be launching it in 2018 I think.

**synth**
I met the one from Dubai. The xantum or xannium, or um..

**christian**
Yea fuck that though, this is like the royal mint England, this is legit like fucking, gold, royal mint has been around for a millenia dude. It's been around forever.

**synth**
You know... gold is really weird because you buy a gold ETF or like paper gold and they'll take the same bar of gold and sell the same bar to three hundred different people, giving a piece of paper saying they own the same bar. So I don't even really trust.. I'm very suspicious about it. Like, "Oh yea we have these gold bars!" but when you actually ask for the bars they don't have them. If that is an actually legit one that could be good I don't know. Like just take it and bury it in your backyard or something [laughs].

**christian**
Well this is all the gold in our city, the royal mint owns it; so it's actually their gold. It isn't like the United States where you get a certificate or something like that. Anyway, umm,

**synth**
Oh this is funny, we had a guy who had some mountain with a piece of paper saying he has a bunch of gold on the mountain and he wants to do like an ICO for the mountain.

**christian**
What????

**synth**
[laughs] I was like ok...

**christian**
What???? Get that shit dude, get the blocks out and mine the shit out.

**evan**
What????

**synth**
Remember sandcoin? That zirconium coin?

**christian**
Yeaaa dude, we interviewed them. What happened to that project? Are they still around?

**synth**
It's only been two weeks. [laughs] What do you mean are they still around? That quick?

**christian**
Well I mean I guess they just finished their ICO. We interviewed them before they finished their ICO.

**synth**
Sp they finished the ICO and two weeks later they're like gone?

**christian**
I would not be surprised... I would not be. I'm telling you. Ok so we are almost at an hour and a half, so what's the next steps? The hardware ledger? The hardware wallet?

**synth**
So we are launching the mobile wallet. We just put in a new version of the desktop wallet, completely from scratch. We were just fixing bugs. There were like twenty bugs we didn't know about, so we fixed those. We are trying to get larger exchanges. We are going to be listing on CyberX when they launch. They were supposed to be launching a week ago, but they had project management delays and whatever. We are talking to binance. It's very hard to get in contact with any human at these exchanges. We have people who are just full time contacting these exchanges, but they just have these zen forms, so it's like fill out the zen form and hope someone contacts you. There are so many coins now. There is like a thousand coins and the exchanges only have room to list like fifty coins, so we are trying to get through that and get our marketing stuff in order and do more exchanges. We are trying to get the OTC listing done. We are trying to launch the Skycoin Skywire miner, which is the hardware platform for doing this decentralized internet. We are trying to ship the first units within a month. We have a supplier and we want three thousand CPUs, but they only have one thousand CPUs so we have to wait three weeks for the factory to produce more. So we are dealing with supply chain and how do we ship it and things like will customs reject it because they are electronics. So we're shipping those out we are getting started on the hardware wallet. We are starting with the marketing. We did a marketing campaign test, but we couldnt do anything because the media is focusing on this hard fork for Bitcoin. So we are waiting for this to die down so we can start our marketing coverage. We just did a new logo. We did our rebranding. We just finished getting like sixty thousand stickers printed up. I have a stack of stickers that is like sixty feet high.

**christian**
Oh my god.

**synth**
We're just hiring more people, hiring more developers. We're doing more interviews. We have like twelve more interviews lined up. It's exhausting. There is so much going on. The CX language. We don't have any press releases about that. We need to get the press releases for Skywire. There is just a billion things. It is really massive. It's exhausting too.

**christian**
This CX language is really interesting.

**synth**
We have a guy. Do you remember Huntercoin?

**christian**
Yea.

**synth**
That was one of my favorite coins. He did Namecoin too. He dropped dead at like 28 for no reason, this Russian guy. Huntercoin was like this MMO on the blockchain where you would fight people and you would get real money coins for fighting them. This sort of like nethack or something. This idea of a video game on the blockchain I really liked. With CX, we have this developer working on Dwarf Fortress or like Sim Ant and I want him to do some video game demos to show off what we can do with CX. Ethereum you can't really do poker on the blockchain because each block is thirty seconds. With Obelisk we can get the block time down to like half a second, so we can do real time games like poker or chess on the blockchain. So I want to see what people can do with that. So we are opening a dev platform and we are letting people come in and make games, and they can create their own token for the game and so on. Skycoin won't make money from that directly, but we will get people on the platform, get attention, and get people to install the software.

**christian**
Hmmm, yea I think the guys changed the project to like Chimera, the Huntercoin.

**synth**
They renamed it?

**christian**
They forked the code yea. They are pushing that fork.

**synth**
That's cool.

**christian**
I mean shit man, this Skywire thing, I am going to look into it as soon as it's launched and starts running. Basically a mesh network right?

**synth**
Yea a mesh net, but it's actually more general than the mesh net. Mesh net is a good marketing term but it's actually software defined networking. This just lets software control the networking. Like you can throw up a bunch of nodes on your roof, or your neighbors roof, and it will just automatically reconfigure to work and route the packets to the right place because each node has a computer in it. Whereas with IP, with the old internet protocol, you just look up the IP and the router looks it up and it forwards it to the next port. It's stupid. It uses like BGP. There isn't any intelligence on the network. With software defined networking, we put the whole network and how packets are routed under control of the software. It could literally be used for anything, for any type of networking. For VPNs, Socks5 proxies, mesh networks, or satellites, for whatever you are doing, you can just run a program to change how the network behaves. So this is very interesting.

**christian**
Well I'm happy to hear that. I didn't even know you guys had a discord group. Is it pretty active there?

**synth**
I don't really use it. We have a telegram and we are active there. We had a slack. We log into the slack and we see that there is like 28,000 messages a day. There are just spam bots spamming each other. One spam bot says, "Hi!" and the other spam bot says, "Hi!" and they just go back and forth in an infinite loop in private messaging and then the message queue ends up filling over.

**christian**
Yea I understand.

**synth**
With Telegram too, we have so much.. like every five minutes someone comes in and they're like, "Join our pump groups!! We have the biggest pumps!!" It's like penis pump cartel. "Coin pump, pump, pump, pump!"

**christian**
Apparently, Skycoin is pumping right now. That's what they're saying in the chat dude. We're not fucking responsible for that shit.

**synth**
What is it at now?

**christian**
I have no idea they're probably just fucking with us.

**synth**
I gotta check this

**christian**
We had the guys from Golem on our show. They went crazy in the Polo trollbox and they pumped fucking Golem up. I was like I'm not fucking responsible for you guys losing your money. I couldnt believe that shit dude.

**synth**
Oh we're almost at $4 we're up like 20% that's great

**christian**
That's good there you go. Fucking boom Skycoin dude, go get that shit.

**synth**
I can't wait for the Cliff High interview. He mentioned us in like his investment report and the price doubled in like eight hours.

**christian**
Have you heard of the Palm Beach Confidential group? These guys? Aw man, they took ZenCash from like $6 to $25 dude it's like alright.

**synth**
What's ZenCash?

**christian**
It's like a fork of Zcash.

**synth**
[laughs] A fork of a fork.

**christian**
I don't understand. Like I guess it's not illegal to do that. Like ok, "This is my pick and this is my bias and this is what I'm telling other people to buy." It's not illegal to do that. I would not fucking trust anybody who buys that coin. Like dude what the fuck are you talking about, if I read about it and it makes sense I'll get it.

**synth**
I see these investment newsletters with these guys on a caribbean island on like a beach with two hot girls and a giant gold necklace and its' like, "buy this coin!! make 5000% profit!!" and I'm like what the fuck.

**christian**
Good luck.. good luck. Yea I just got back from Spain. The whole idea of just being on the beach. It's where devcon is. I was going to go to devcon, but man... Cancun dude I don't know man. I just don't know about people who only want that in their life. Let's be real dude. For three days, you're like ok, and then you're like let's get the fuck out of here. I have other shit to do man.

**synth**
"Snowboarding"

**christian**
Yea exactly [laughs]

**synth**
How hard is it to get onto Polo? I can't even get a hold of anyone on Polo at this point.

**christian**
Dude let me tell you a story about Polo. I've been waiting about six months for my ticket to be answered.

**synth**
[laughs]

**christian**
They have like $10,000 of my coins in their master wallet because my friend sent me a transaction. There are only two transactions in that wallet. He had to resend the transaction to pay me again. Like you guys have my fucking coins they are sitting right there like right there you can see it on the blockchain. Who else has a wallet with like twenty eight million fucking AMPs that's Poloniex's fucking wallet. They still have not answered me. I think Polo is a fucking scam dude I'm going to be honest with you.

**evan**
I think it is.

**synth**
I think they're all... like most of them are scams. One exchange wants like $250,000 to list a coin.

**christian**
I know Kraken is like that, you have to pay Kraken up to get on Kraken. You have to pay Kraken 150 Gs to get listed on there. Have you talked to the guys at Bittrex?

**synth**
We were scheduled to be listed, but then the SEC shit happened--

**christian**
--Yea you have to do some paperwork with them

**synth**
--and like 30 coins that were supposed to get listed got cancelled and then Bill was like being evasive and disappeared.

**christian**
You have to talk to like Julian or that other lady. They are doing more compliance shit now like, "Is this legit? Do you have developers?--

**synth**
-- [laughs] "Do you have developers, do you have a blockchain?" Most of these coins don't--

**christian**
--"Oh you do have developers. Is it a security? Oh it isn't a security? ok. Oh you guys actually have a blockchain? ok." You could also try the um.. I could put you in touch with the guys in charge of the exchange in Switzerland. There's not a lot of liquidity on it yet but that's a solid fucking team behind that. That's not a bullshit squad. I mean let me look up the volume on the exchange right now.

**synth**
Oh and they're pumping the volume on these exchanges. For some of these exchanges to keep their ranking in the top 20, they are doing a lot of wash trading. Like I see it, and they are just using bots trading back and forth between each other like a million times a second.

**christian**
I have guys that want to setup arbitrage so bad. It's nothing to move the money, like moving money from the US to...

**synth**
The fees are ridiculous too, like the .1% fee. If you have a million dollars of volume, you are paying tens of thousands dollars a day for a million dollars. And it's on both sides because the buyer pays the fees and the seller. So if you are doing ten million dollars a day in volume, that coin is paying twenty thousand a day on the exchange. So the exchange not only wants $250,000 to get listed, but they want us to pay them like $20,000 a day for volume basically. I'm like fuck that I could just buy like 3 houses.

**christian**
Yea exactly, I mean there's the guys at Bithumb.

**synth**
Yea I like Bithumb.

**christian**
There's HitBTC that came out of nowhere. They really stepped up their shit.

**synth**
Is that real?

**christian**
Yea I think, maybe. Who knows dude lets be real. I can't talk shit if I don't fucking know em. HitBTC is there. Um Kraken.. I mean you're just dropping down from there. Why don't you talk to the guys at Liqui?

**synth**
Liqui is good yea.

**christian**
Liqui is not terrible, like eighteen million dollars a day that's good.

**synth**
We are doing this OTC thing for Skyledger so when the coins launch on Skyledger, that coin is going to be liquid and traded from day one. They are going to trade their coin and five minutes later they are going to have an order book. These coins like, they raise one hundred and fifty million dollars in an ICO and they cannot get listed on any exchange at all. It's retarded.

**christian**
Yea I mean I did message Bill one day and I was like how much does it cost to get listed on Bittrex like 40 Gs? He was like, "No, we don't fucking need your money, we need you to be fucking legit so our ass is covered." Like that's where I think it's going, the guys running these exchanges have so much money now.
These guys are running Bithumb like how much fucking money do you need. "I've got five hundred million dollars cash" like alright dude chill.

**synth**
Look at their volume. If their volume is real and they are getting .02% on each trade on the bid and ask and their volume isn't fake. I think that they are rebating the fees for special accounts and institutional investors and they lie and say that they aren't doing that. But if you take the volume and like a billion dollars, and look at the fees they would pay if the fees are actually paid, then you have this exchange that's making ten million dollars a day. It's like this four person exchange is not making four million dollars a day. I think the volume is there just to get the smucks in to buy. Like, "Oh look at this volume, people are trading! Buy this!" For some of these exchanges like HitBTC, if you don't have volume, they have a volume expert and you can go to this guy... like I talked to one of these guys. Not the one from HitBTC, but this was very funny. He wanted three million dollars in coins and all he does is just sit there and day trade on the coin and create volume. I was like, "Why would I give you three million dollars to sit there and day trade?" And he was like well that's what the other coins are giving him so he wouldn't do less than that and he has like four people asking him.

**christian**
That is fucking insane dude.

**synth**
[laughs]

**christian**
It makes complete sense but like what the fuck are we doing out here guys. Of course this shit happens, like duh, but it's just like. I would fuck up the trade so bad like, I'd make the price go down 80%.

**synth**
[laughs] Yea just like dumping em, and he probably wants a kick back from the exchange for the volume fees. Like, "I'm giving you ten million dollars in volume, how much are you giving me?"

**christian**
That's actually a good point though. It is curious how some of these coins have so much volume. Like $26,000,000 in volume, like Vertcoin.

**synth**
Yea Vertcoin, my favorite coins is Veriteseum. This guy created four hundred million coins and put them in his pocket, then he gave like 2% of the coins out to the community and he gets an exchange to list it. And he's like, "Look I have four hundred million dollars of bling!!" He's really cool, but it's just funny..

**christian**
He is a cool guy. I did an interview with him and he sounded pretty knowledgeable. Everyone I've talked to about that project says it's a scam like look at the website.

**synth**
He knows how to play the game though. Like we could do that, "Oh look Skycoin is sixteen billion dollars!" You just create a bunch of coins and then trade them back and forth between yourself at like $3. It's like "Ohh look we have thirty billion dollars." I mean that's what Ripple does and these other coins.
If you can create a huge number of coins and then not distribute them, but still get coinmarketcap to say they are distributed. With Skycoin, we get a lot of shit because of the distribution number. We didn't say it was 60%. We could say it was 60% and nobody would complain but that number is actually accurate in calculation. Whereas some of these other coins, they release billions of coins supposedly, but actually the community only has one hundred thousand coins to trade on so their market cap gets blown up by like 600x. They have to pay people to do the volume or else they get delisted off of coinmarketcap.

**christian**
I mean there are so many coins. They dont have any tangible shit behind it. They don't have users or anything it's just a fucking coin. Once the volume goes sideways its going down and I'm telling you it's not going back up. You better fucking get something going or it's done. I know so many coins, like Numerai. It was $150 now that shit's at $12. It collapsed by like 15x. If you bought at the fucking top, you are fucking completely done.

**synth**
I like ByteBalls. There are some coins that have developers and they might not know what they're doing, but there are like five coins that have developers and they all fucking blow up from like one penny to $700.

**christian**
Well ByteBall was actually a fair distribution.

**synth**
Yea they did a really good job.

**christian**
That shit, people just speculated it like way too high. It went up to like $900 and now its like $200.

**synth**
I got it at $.10 [laughs]. It was at like $700 and I was like "Yea!!".

**christian**
Yea when it hit the exchange it was trading at like $50 so if you sell at $1000 you cannot fucking complain like.. and you can stake those right? You just lock them all up and run.. I sold all of mine but.

**synth**
So if you look at these coins that have actual applications and they have actual users and a real user community and you buy them early you can't lose money on them. Their communities are growing like 3% a day, 5% a day and the price eventually reflects that. The Skycoin telegram. We had 100 people in our telegram like a few months ago and now we are near 1,000. We just got fifty people in the last two days and its growing like 3% a day. It's been growing like that for years but you just start out really small. When you have ten people and you get 10% a day you only get one person but it's 10% growth. And eventually you have 1,000 people and you are still getting 1 or 2% a day and it continues for years. That's what we saw with Litecoin. The coins that were really successful they grew at a constant rate over years, like four or five years and then the price for no reason goes from a penny to like $50.

**christian**
I mean let's be real though it only takes like three or four whales and a couple coordinated moves and they can really move the whole market.

**synth**
Yea

**christian**
That's what happened with Ripple.

**christian**
Same thing with NEM. Somebody told me to buy in February. They said it was going to go to a $1 and it didnt go to $1 but it fucking went up like 20x like alright dude.

**synth**
Ooh another thing that I look at when I'm investing um, I look at do people actually have the wallet? So I was talking to this Ethereum whale and he had like $300M in Ethereum and I asked him what Ethereum wallet did he use. I needed an Ethereum thin wallet because I didn't want to download this huge blockchain. I asked him what wallet he was using he was like, "I don't know." Like what do you mean you don't know? You're a freaking Ether whale. I talked to another user and it was the same thing, so if you ask these people like... they have this coin most of the users do not community even have the wallet. Their coins are sitting on an exchange waiting to get stolen and they never install the wallet for that coin. It's just incredible.

**christian**
I don't hold any coins on the exchanges unless like... right now the Dynamic blockchain is down so they are storing them on their central server. So you're storing them with Duality or you are storing them on the exchange but thats it everything else fucking stays in cold storage dude. You have got to move your shit to cold storage guys.

**synth**
Yes. But how can you have a cold store for like 300 coins? I can't even deal with like four wallets. Like how do people?

**christian**
I mean the Jaxx Wallet. They are putting out an update which will work for like sixty coins soon.

**synth**
I think we are going to get on there. Some guy messaged us about that. We have to follow up on that.

**christian**
I mean Exodus is pretty good. I heard the security on Exodus is better.

**synth**
Is that the Louis Vutton one?

**christian**
No I mean Exodus is legit ummm.. and then like you can get a Ledger. You can store only a couple cryptos on a Ledger though, but Ledger is good because it's hardware. What you could also do... have you ever seen that cryptosteel shit? It's like a block of fucking--

**synth**
--Yea I love that thing. I want to go to the airport with that. [laughs] Like, "what the fuck is this??"

**christian**
Like, "What is this?" It's a fucking piece of metal they'd be like, "Yea ok you can go through with this..." [laughs]

**synth**
Yea like sheet metal. It's like $200 right?

**christian**
Yea my friend was like thats some real cypher shit right there like some 1990s shit.

**synth**
You got the Hex one and you have the numeric--

**christian**
--So thats what the Royal Mint that's what they are going to be using. If you have an account with RMG, they give you a cryptosteel and you put it in their lockbox in their vault. It's so legit dude. That's the fucking future like you go in and you cant rob the fucking vault because they are all fucking crypto steels dude.

**synth**
You want to do like an interview series every week? Or every month?

**christian**
Yea we can. We can do it biweekly or weekly. It just depends. If the guests are hot, or if there's hot news, or if you just want to talk bullshit and bring developers on or.. really anything we're here.

**synth**
Yea, like what are we on an hour and forty?

**christian**
Yea we can slow down. We can cut this off in a minute. I don't really see any questions in the chat. A lot of people came to support. There were like twenty people watching, which is pretty cool.

**synth**
That's great. Yea so besides Skycoin, we have a bunch of coins. Spaco is really interesting. They're doing like a filecoin but it's based Skycoin and our CXO and it runs on Skywire. So the people get Spaco and they get Skycoins for running this thing. And then the Solarbankers and then we are actually talking to a company in Mauritius and they are a huge forex site. They have like meta trader four and these people... they are even more hardcore gamblers then these altcoin people. They are just like Forex, like 400x leverage trades on currency pairs and we are going to do a coin for that Forex exchange. With the profits from the Forex exchange, about half of them are going to go back to the coin I think. I saw some coin that was trying to do derivatives and they tried to raise like a billion dollars, so I'm wondering if these guys are going to do a hundred and fifty million dollar ICO or what, but we have some pretty interesting coins signing up now.

**christian**
Cool. I mean that's what you need right. You just need some volume in and then some cool shit to back it up. Once you have the financial framework down then you can just add like the fun stuff to it right.

**synth**
Yea.

**christian**
Cool.

**synth**
You want to end it?

**christian**
Yea, this is an interview with Skycoin. Synth, I guess will be back at some point. We definitely have some cool shit to talk about. Well it was a pleasure having the interview.

**synth**
Yea this was great.

**christian**
Cool, alright and we're out, we're gonna sign out and end it here. Uhh I guess we'll be back whenever.

**synth**
Is this on Youtube or?

**christian**
Yea its gonna go right to Youtube. It's already on Youtube so.. cool, alright I'm gonna end it now guys, later.
