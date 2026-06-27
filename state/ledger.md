# Леджер опубликованных новостей (дедуп)

Каждый прогон мониторинга сверяется с этим списком и НЕ повторяет уже опубликованные новости.
После публикации дайджеста добавь сюда новые пункты с датой и URL. Пункты старше ~7 дней удаляй.

<!-- curl syntax that works (interactive session with security hooks, discovered 2026-06-25, 15:00 UTC run):
  curl --variable '%TELEGRAM_BOT_TOKEN' \
       --variable 'TEXT=...multiline message...' \
       --expand-url 'https://api.telegram.org/bot{{TELEGRAM_BOT_TOKEN}}/sendMessage' \
       -d 'chat_id=-1003969663541' -d 'parse_mode=HTML' -d 'disable_web_page_preview=true' \
       --expand-data 'text={{TEXT:url}}'
  — single-quoted args avoid security hooks; {{TEXT:url}} URL-encodes multiline message.
  — for GHA runs (no hooks), --data-urlencode "text=..." with $'...' or heredoc also works.
-->

## Опубликовано

### 2026-06-27
- XII «Технологический Индекс» 2026: рейтинг лучших платформ автоматизации рекламных кампаний [10:01 МСК, обязательный дайджест] — https://adindex.ru/news/digital/2026/06/26/346281.phtml
- Почти 10% вакансий в рекламе требуют ИИ-навыков — в 5 раз выше среднего по рынку (HeadHunter) [10:01 МСК, обязательный дайджест] — https://adindex.ru/news/researches/2026/06/26/346283.phtml
- Новое агентство Reacta для инфлюенс-маркетинга и назначения в Кион, МТС Live [10:01 МСК, обязательный дайджест] — https://adindex.ru/news/hr/2026/06/26/346269.phtml

### 2026-06-26
- Алиса AI генерирует в ~5 раз больше переходов на российские сайты, чем ChatGPT — исследование Impulse.guru [11:00 МСК, обычный прогон] — https://ppc.world/news/alisa-ai-generiruet-v-pochti-5-raz-bolshe-perehodov-na-rossiyskie-sayty-chem-chatgpt-issledovanie/
- Яндекс Вебмастер ускорил обновление данных в «Мониторинге запросов»: данные за сутки с детализацией по часам [11:00 МСК, обычный прогон] — https://ppc.world/news/yandeks-vebmaster-uskoril-obnovlenie-dannyh-v-monitoringe-zaprosov/
- Объём расходов на рекламу в MAX вырос в 37 раз (число рекламодателей +18×, средний чек +4,7×) [10:00 МСК, обязательный дайджест] — https://adindex.ru/news/tendencies/2026/06/26/346270.phtml
- ФАС рекомендовала операторам до 3 июля переработать рекламу 5G — введение в заблуждение [10:00 МСК, обязательный дайджест] — https://adindex.ru/news/right/2026/06/26/346271.phtml
- YouTube меняет Shorts: ускорение просмотра до 2× и замена дизлайка на «Не интересно» [10:00 МСК, обязательный дайджест] — https://adindex.ru/news/media/2026/06/26/346272.phtml
- УФАС Дагестана проверит рекламу гипермаркета «Четыре жены — восемь рук» [10:00 МСК, обязательный дайджест] — https://sostav.ru/publication/ufas-dagestana-proverit-reklamu-gipermarketa-s-upominaniem-preimushchestv-mnogozhenstva-84820.html
- RuStore вышел на глобальный рынок — разработчики выбирают страны распространения (Африка, Азия, Европа) [10:00 МСК, обязательный дайджест] — https://vk.company/ru/press/releases/12336/
- МАХ начал тестировать комментарии в публичных каналах [13:00 МСК, обычный прогон] — https://vk.company/ru/press/releases/12344/
- Unilever сделала ставку на культурную значимость вместо роста рекламных бюджетов [13:00 МСК, обычный прогон] — https://sostav.ru/publication/unilever-sdelala-stavku-na-kulturnuyu-znachimost-vmesto-rosta-reklamnykh-byudzhetov-84832.html
- ФАС выдала предупреждение банку «Ак Барс» [13:00 МСК, обычный прогон] — https://sostav.ru/publication/fas-vydala-preduprezhdenie-banku-ak-bars-84830.html
- В отчетах Яндекс Метрики появилась детальная диагностика по офлайн-данным [15:00 МСК, обязательный дайджест] — https://ppc.world/news/v-otchetah-yandeks-metriki-poyavilas-detalnaya-diagnostika-po-oflayn-dannym/
- 42,8% пользователей начинают поиск информации в нейросетях — исследование SEOnews [15:00 МСК, обязательный дайджест] — https://www.seonews.ru/events/42-8-polzovateley-nachinayut-poisk-informatsii-v-neyrosetyakh-issledovanie/
- Okkam: эффективность indoor-рекламы зависит от среды, а не формата [15:00 МСК, обязательный дайджест] — https://adindex.ru/news/researches/2026/06/26/346284.phtml
- Cannes Lions 2026: победители в категориях Strategy и Experience [15:00 МСК, обязательный дайджест] — https://sostav.ru/publication/cannes-lions-2026-obyavili-pobeditelej-v-strategy-i-experience-84833.html
- «Авито Реклама» открыла ретаргетинг для бизнеса любого размера [12:01 МСК, обычный прогон] — https://adindex.ru/news/digital/2026/06/25/346268.phtml
- Гран-при «Каннских льовов 2026» — Adidas взял главную награду с «Supernova Adaptive» [12:01 МСК, обычный прогон] — https://adindex.ru/news/creative/2026/06/25/346267.phtml
- Каждый пятый россиянин готов платить за ИИ-помощника в приложениях на регулярной основе [12:01 МСК, обычный прогон] — https://sostav.ru/publication/kazhdyj-pyatyj-rossiyanin-gotov-platit-za-ii-pomoshchnika-v-prilozheniyakh-na-regulyarnoj-osnove-84826.html
- Рынок short video commerce в России — до 1,5 трлн руб. к 2027 году (исследование РАЭК) [16:00 МСК, обычный прогон] — https://adindex.ru/news/researches/2026/06/26/346285.phtml
- Кейс: БЛОКПОСТ + MTC OmniChannel — ROMI вырос в 2 раза [16:00 МСК, обычный прогон] — https://sostav.ru/publication/renessans-mms-kak-blokpost-i-mtc-omnichannel-uvelichili-romi-v-2-raza-84812.html
- Приложение Telega прекратит работу с 1 июля [16:00 МСК, обычный прогон] — https://likeni.ru/events/prilozhenie-telega-prekratit-rabotu-s-1-iyulya/
- Выручка брендинговых агентств в России сократилась более чем на 20% [17:00 МСК, обычный прогон] — https://sostav.ru/publication/vyruchka-brenlingovykh-agentstv-v-rossii-sokratilas-bolee-chem-na-20-84844.html
- «Мобио» выиграло тендер на продвижение мобильного приложения «Магнит» [17:00 МСК, обычный прогон] — https://sostav.ru/publication/mobio-vyigralo-tender-na-prodvizhenie-mobilnogo-prilozheniya-magnit-84840.html
- Как Only и BAIKAL430 погрузили премиальную воду в диджитал [17:00 МСК, обычный прогон] — https://sostav.ru/publication/kak-only-i-baikal430-pogruzili-premialnuyu-vodu-v-didzhital-84841.html
- В Авито Рекламе появился ретаргетинг по кампаниям и группам объявлений [18:01 МСК, обычный прогон] — https://ppc.world/news/v-avito-reklame-poyavilsya-retargeting-po-kampaniyam-i-gruppam-obyavleniy/
- 74% россиян доверяют личным рекомендациям больше, чем рекламе [18:01 МСК, обычный прогон] — https://adindex.ru/news/researches/2026/06/26/346288.phtml
- ИИ, предпринимательское мышление, многофункциональность: чего компании ждут от маркетологов в 2026 [18:01 МСК, обычный прогон] — https://sostav.ru/publication/ii-predprinimatelskoe-myshlenie-i-mnogofunktsionalnost-chego-kompanii-zhdut-ot-marketologov-v-2026-godu-84831.html
- Акцент на удержание: как работа с привлечённой аудиторией развивает бизнес на перегретом рынке [18:01 МСК, обычный прогон] — https://sostav.ru/publication/aktsent-na-uderzhanie-kak-rabota-s-uzhe-privlechennoj-auditoriej-pomogaet-razvivat-i-prodvigat-biznes-na-peregretom-rynke-84837.html

### 2026-06-25
- Яндекс запустил «Прайм-баннер» — единый охватный формат на 20+ сервисах экосистемы [17:01 МСК, обычный прогон] — https://adindex.ru/news/digital/2026/06/25/346259.phtml
- VK Реклама запустила продвижение каналов ВКонтакте, MAX и Дзен (бета) [17:01 МСК, обычный прогон] — https://vk.company/ru/press/releases/12333/
- Яндекс B2B Tech открыл Vibecraft — сайты по текстовому описанию за 5–10 минут [17:01 МСК, обычный прогон] — https://ppc.world/news/yandex-b2b-tech-otkryl-dostup-k-vibecraft-s-kotorym-mozhno-sozdat-sayt-po-tekstovomu-opisaniyu/
- Платформа для партнёров MAX открылась для самозанятых [17:01 МСК, обычный прогон] — https://vk.company/ru/press/releases/12335/
- РСЯ прекращает сотрудничество с физлицами: до 1 июля — самозанятость или ИП [12:00 МСК, обычный прогон] — https://ppc.world/news/rsya-napomnila-o-prekraschenii-sotrudnichestva-s-fizlicami-do-1-iyulya-nuzhno-pereyti-na-samozanyatost-ili-ip/
- Apple без предупреждения удалила из App Store Дзен, VK Видео, VK Знакомства, VK Мессенджер и VK Музыку [12:00 МСК, обычный прогон] — https://sostav.ru/publication/iz-app-store-udalili-prilozheniya-dzen-i-vk-messendzher-84796.html
- Meta запустила Creator Studio — ИИ-инструмент для контентмейкеров на Facebook [12:00 МСК, обычный прогон] — https://adindex.ru/news/digital/2026/06/25/346223.phtml
- Пользователи с блокировщиками рекламы тратят на покупки больше [12:00 МСК, обычный прогон] — https://sostav.ru/publication/polzovateli-s-blokirovshchikami-reklamy-tratyat-na-pokupki-bolshe-84786.html
- Publicis Groupe раскритиковала ажиотаж вокруг ИИ в рекламной индустрии [14:00 МСК, обычный прогон] — https://sostav.ru/publication/publicis-groupe-raskritikovala-azhiotazh-vokrug-ii-v-reklamnoj-industrii-84803.html
- Обновление «Алисы AI»: доводит задачу до результата и запоминает важное из диалога [14:00 МСК, обычный прогон] — https://sostav.ru/publication/obnovlenie-alisy-ai-ona-dovodit-zadachu-do-rezultata-i-zapominaet-vazhnoe-iz-dialoga-84791.html
- Почти половина маркетологов в мире признают, что их реклама остаётся шаблонной [14:00 МСК, обычный прогон] — https://sostav.ru/publication/pochti-polovina-marketologov-v-mire-priznayut-chto-ikh-reklama-ostaetsya-shablonnoj-84797.html
- Зумеры чаще других поколений готовы платить за мобильные приложения [14:00 МСК, обычный прогон] — https://adindex.ru/news/researches/2026/06/25/346220.phtml
- Минцифры обратилось в ФАС из-за удаления VK-приложений и закона о предустановке RuStore [15:00 МСК, обязательный дайджест] — https://vc.ru/services/2995176-mintsifry-trebuyut-proverit-apple-iz-za-udaleniyaprilozheniy-vk-i-rustore
- Реклама в MAX для фешен-брендов: что показал тест O'STIN и i.соm [15:00 МСК, обязательный дайджест] — https://sostav.ru/publication/reklama-v-max-dlya-feshen-brendov-84801.html
- Стриминги ищут способ победить усталость от рекламы [15:00 МСК, обязательный дайджест] — https://sostav.ru/publication/strimingi-ishchut-sposob-pobedit-ustalost-ot-reklamy-84805.html
- Маркетологи и пиарщики умерили ожидания от ИИ [15:00 МСК, обязательный дайджест] — https://sostav.ru/publication/marketologi-i-piarshchiki-umerili-svoi-ozhidaniya-otnositelno-vozmozhnostej-ii-84804.html
- Cannes Lions 2026: победители в Creative Data, Media, Direct, PR и Social & Creator [15:00 МСК, обязательный дайджест] — https://sostav.ru/publication/cannes-lions-2026-obyavili-pobeditelej-v-creative-data-media-direct-pr-i-social-creator-84800.html
- Google разрешит сторонние способы оплаты в Google Play [15:00 МСК, обязательный дайджест] — https://vc.ru/services/2994728-google-play-razreshit-alternativnye-sposoby-oplaty
- Акции VK рухнули до рекордного минимума после удаления приложений из App Store [18:01 МСК, обычный прогон] — https://adindex.ru/news/tendencies/2026/06/25/346260.phtml
- Покупки в диалоге: как мир привыкает приобретать товары через нейросети [18:01 МСК, обычный прогон] — https://sostav.ru/publication/pokupki-v-dialoge-kak-mir-privykaet-priobretat-tovary-cherez-nejroseti-84774.html
- Apple объяснила удаление VK из App Store «соблюдением санкций» (Sogaz, Газпромбанк, Ростех) [19:01 МСК, обычный прогон] — https://vc.ru/services/2995674-apple-udalenie-prilozheniy-vk
- Кабмин внёс в Госдуму законопроект о поддержке развития ИИ [19:01 МСК, обычный прогон] — https://sostav.ru/publication/kabmin-vnes-v-gosdumu-zakonoproekt-o-podderzhke-razvitiya-ii-84811.html

### 2026-06-24
- Рекламный рынок превысил 1 трлн долл. и вырастет до 1,4 трлн долл. к 2030 году [10:16 МСК, обязательный дайджест] — https://sostav.ru/publication/reklamnyj-rynok-prevysil-1-trln-i-vyrastet-do-1-4-trln-k-2030-godu-84749.html
- Т-Банк, «Дром» и Hassle стали лидерами по рекламным интеграциям на YouTube [10:16 МСК, обязательный дайджест] — https://adindex.ru/news/researches/2026/06/24/346171.phtml
- Walmart купил рекламную платформу Vibe.co для CTV-маркетинга [10:16 МСК, обязательный дайджест] — https://adindex.ru/news/marketing/2026/06/24/346177.phtml
- Twitch не работает в России — Роскомнадзор опровергает блокировку [10:16 МСК, обязательный дайджест] — https://ppc.world/news/twitch-ne-rabotaet-v-rossii-no-roskomnadzor-oproverg-blokirovku-strimingovoy-platformy/
- Госдума одобрила заморозку порога НДС — платить будет только бизнес с доходом от 20 млн руб. [13:00 МСК, обычный прогон] — https://ppc.world/news/gosduma-v-pervom-chtenii-odobrila-zamorozku-poroga-nds-platit-nds-budet-tolko-biznes-s-dohodom-ot-20-mln-rubley/
- Яндекс может запустить новый бренд для работы с блогерами [13:00 МСК, обычный прогон] — https://www.seonews.ru/events/yandeks-mozhet-zapustit-novyy-brend-dlya-raboty-s-blogerami/
- Amazon Ads добавил функцию покупки товаров прямо из телевизионной рекламы [13:00 МСК, обычный прогон] — https://adindex.ru/news/digital/2026/06/24/346183.phtml
- Маркетинг-директор P&G: ИИ открывает новую эру в маркетинге [13:00 МСК, обычный прогон] — https://sostav.ru/publication/marketing-direktor-p-g-iskusstvennyj-intellekt-otkryvaet-novuyu-eru-84755.html
- Второй день Cannes Lions 2026: Google, Adidas, Coinbase среди победителей [13:00 МСК, обычный прогон] — https://adindex.ru/news/creative/2026/06/23/346168.phtml
- WPP представила пять принципов доверия в эпоху ИИ [15:01 МСК, обязательный дайджест] — https://sostav.ru/publication/wpp-predstavila-pyat-printsipov-doveriya-v-epokhu-iskusstvennogo-intellekta-84767.html
- Omnicom Media и Paramount+ — динамические рекламные блоки в стриминге [15:01 МСК, обязательный дайджест] — https://adindex.ru/news/digital/2026/06/24/346185.phtml
- Meta разрабатывает Arena — приложение для прогнозов и ставок [15:01 МСК, обязательный дайджест] — https://adindex.ru/news/digital/2026/06/24/346173.phtml
- MAX удалён из App Store — инструкция для iPhone и до 10 каналов на организацию [17:00 МСК, обычный прогон] — https://ppc.world/news/maks-predstavil-instrukciyu-kak-poluchat-uvedomleniya-na-iphone-aktualno-posle-udaleniya-messendzhera-iz-app-store/
- Telegram тестирует расширенный редактор постов: таблицы, формулы, заголовки, коллажи [17:00 МСК, обычный прогон] — https://ppc.world/news/telegram-testiruet-rasshirennyy-tekstovyy-redaktor-s-tablicami-i-formulami/
- Cannes Lions 2026: подробный разбор второго дня — Apple, Google, Adidas, Hyundai [17:00 МСК, обычный прогон] — https://sostav.ru/publication/cannes-lions-2026-ot-gejmerov-do-gumanitarnykh-missij-pobediteli-vtorogo-dnya-festivalya-84735.html
- Рекламу криптовалют могут запретить в России [19:00 МСК, обычный прогон] — https://adindex.ru/news/right/2026/06/24/346213.phtml
- Стратегия «выхода»: почему селлеры покидают маркетплейсы и как уйти, не потеряв бизнес [19:00 МСК, обычный прогон] — https://sostav.ru/publication/strategiya-vykhoda-pochemu-sellery-pokidayut-marketplejsy-i-kak-ujti-ne-poteryav-biznes-84768.html
- ByteDance планирует взять кредит на 20 млрд долл. [19:00 МСК, обычный прогон] — https://sostav.ru/publication/bytedance-planiruet-vzyat-kredit-na-20-mlrd-84769.html

### 2026-06-23
- TikTok запустил Symphony Agent — ИИ для создания видеорекламы без съёмки [11:00 МСК, обычный прогон] — https://adindex.ru/news/digital/2026/06/23/346129.phtml
- Omnicom Media Group + Netflix: ИИ-таргетинг рекламы в стриминговом контенте [11:00 МСК, обычный прогон] — https://sostav.ru/publication/omnicom-media-i-netflix-obyavili-o-partnerstve-dlya-integratsii-reklamy-v-strimingovyj-kontent-84714.html
- Amazon запускает Creator Hub — витрина блогеров на Fire TV [11:00 МСК, обычный прогон] — https://adindex.ru/news/media/2026/06/23/346119.phtml
- Рынок наружной рекламы в России вырос до 30,3 млрд руб. в Q1 2026 (+11% г/г) [14:00 МСК, обычный прогон] — https://adindex.ru/news/ad_budjet/2026/06/23/346145.phtml
- Бренды массово выдают ИИ-инфлюенсеров за реальных людей — без маркировки [14:00 МСК, обычный прогон] — https://sostav.ru/publication/brendy-vse-chashche-vydayut-ii-inflyuenserov-za-realnykh-lyudej-84725.html
- Disney запускает ESPN Fan House — рекламная платформа для брендов на спортивных событиях [14:00 МСК, обычный прогон] — https://adindex.ru/news/digital/2026/06/23/346137.phtml
- RWB Медиа (Wildberries) запустила CPC-оплату для медийных баннеров [16:00 МСК, обычный прогон] — https://sostav.ru/publication/rwb-media-zapustila-oplatu-za-kliki-dlya-medijnykh-bannerov-84732.html
- Яндекс Тег Менеджер: сабконтейнеры и новые настройки тегов/триггеров [16:00 МСК, обычный прогон] — https://yandex.ru/adv/news/sabkonteynery-i-novye-nastrojki-triggerov-v-yandeks-teg-menedzhere
- Турецкие бренды вдвое нарастили инвестиции в рекламу на Яндексе (5 мес. 2026) [16:00 МСК, обычный прогон] — https://sostav.ru/publication/turetskie-brendy-vdvoe-narastili-investitsii-v-prodvizhenie-na-yandekse-84729.html
- «Каннские львы 2026»: старт фестиваля и главные темы индустрии [16:00 МСК, обычный прогон] — https://adindex.ru/news/tendencies/2026/06/23/346146.phtml
- Верховный суд признал законной механику «подписка на рекламу за скидку» [18:00 МСК, обычный прогон] — https://sostav.ru/publication/verkhovnyj-sud-priznal-zakonnoj-mekhaniku-podpiska-na-reklamu-za-skidku-84734.html
- В каналах ВКонтакте появились видеосообщения, закреплённые посты и репост в историю [18:00 МСК, обычный прогон] — https://ppc.world/news/v-kanalah-vkontakte-poyavilis-videosoobscheniya-zakreplennye-posty-i-repost-v-istoriyu/
- Rutube возглавил рейтинг платформ для монетизации контента в России (ставка 50–150 руб./1000 просм.) [18:00 МСК, обычный прогон] — https://ppc.world/news/rutube-vozglavil-reyting-platform-dlya-monetizacii-kontenta-v-rossii-avtory-zarabatyvayut-do-150-rubley-za-1000-prosmotrov/
- Цифровая усталость: почему реклама перестаёт работать и как бизнес перестраивает маркетинг [19:01 МСК, обычный прогон] — https://sostav.ru/publication/tsifrovaya-ustalost-pochemu-reklama-perestaet-rabotat-i-kak-biznes-perestraivaet-marketing-84731.html
- Победители первого дня «Каннских льовов 2026»: от штрихкода до мобильной клиники [19:01 МСК, обычный прогон] — https://adindex.ru/news/creative/2026/06/23/346158.phtml
- Диджитал Индекс 2.0: обновление рейтинга интернет-подрядчиков [19:01 МСК, обычный прогон] — https://adindex.ru/news/agencies/2026/06/23/346140.phtml

### 2026-06-22
- Объём рекламного рынка превысил 220 млрд рублей в первом квартале 2026 года [11:01 МСК, обычный прогон] — https://adindex.ru/news/researches/2026/06/22/346082.phtml
- Динамика медиапотребления в России сократилась [11:01 МСК, обычный прогон] — https://adindex.ru/news/tendencies/2026/06/22/346068.phtml
- Правительство поручило 11 министерствам разработать стратегию цифровых платформ [13:00 МСК, обычный прогон] — https://sostav.ru/publication/pravitelstvo-poruchilo-11-ministerstvam-podgotovit-strategiyu-razvitiya-tsifrovykh-platform-84681.html
- VK Play заблокирован в браузерах — волна отзыва сертификатов GlobalSign продолжается [13:00 МСК, обычный прогон] — https://vc.ru/services/2989299-vk-play-zablokirovan-v-brauzerakh
- L'Oréal интегрирует бренд-сервисы в ChatGPT [13:00 МСК, обычный прогон] — https://sostav.ru/publication/l-or-al-integriruet-servisy-krasoty-v-chatgpt-84678.html
- АБА: стабильные блогеры привлекают новую аудиторию в 1,7× эффективнее [14:17 МСК, обычный прогон] — https://ppc.world/news/aba-nuzhno-izuchat-pokazateli-stabilnosti-blogerov-chtoby-prognozirovat-effektivnost-kampaniy/
- Яндекс KIT подключился к доставке Ozon по модели FBS [14:17 МСК, обычный прогон] — https://yandex.ru/adv/news/polzovateli-yandex-kit-mogut-podklyuchit-ozon-dostavku-fbs
- Программатик в 2025 году: выручка превысила 56,3 млрд рублей (+11,7%) [15:01 МСК, обязательный дайджест] — https://sostav.ru/publication/vyruchka-programmatik-produktov-v-2025-godu-prevysila-56-3-mlrd-rublej-84698.html
- ФАС штрафует за нарушения рекламного законодательства: ИИ и подрядчики не спасают [15:01 МСК, обязательный дайджест] — https://sostav.ru/publication/zvezdochka-ne-spaset-2-pochemu-rossijskie-brendy-teryayut-dengi-84684.html
- WPP сохранила лидерство по биллингам: мировой рынок медиаразмещения — 478 млрд долл. [15:01 МСК, обязательный дайджест] — https://sostav.ru/publication/wpp-sokhranila-liderstvo-po-billingam-84694.html
- Яндекс Директ: ИИ-управление рекламой в мессенджерах и новые инструменты для рекламодателей [17:00 МСК, обычный прогон] — https://adindex.ru/news/marketing/2026/06/22/346101.phtml
- Директ: товарные объявления для продвижения приложений теперь работают на ретаргетинг [17:00 МСК, обычный прогон] — https://yandex.ru/adv/news/tovarnye-obyavleniya-dlya-prilozheniy-dostupny-dlya-retargetinga
- RWB Медиа (Wildberries) открыла единую рекламную сеть на партнёрских сайтах [17:00 МСК, обычный прогон] — https://adindex.ru/news/digital/2026/06/22/346096.phtml
- Яндекс Директ: в объявлениях Товарной галереи теперь показываются характеристики товаров [19:00 МСК, обычный прогон] — https://ppc.world/news/v-obyavleniyah-tovarnoy-galerei-yandeksa-teper-pokazyvayutsya-harakteristiki-tovarov/
- Лето 2026: тренды в рекламных креативах [19:00 МСК, обычный прогон] — https://sostav.ru/publication/leto-2026-trendy-v-kreative-84685.html
- Правкомиссия одобрила законопроект о регулировании ИИ в России [19:00 МСК, обычный прогон] — https://sostav.ru/publication/pravkomissiya-odobrila-zakonoproekt-o-regulirovanii-ii-84704.html

### 2026-06-21
- В Госдуме предложили приравнять к рекламе надписи о «пользе» продуктов на упаковках [10:00 МСК, обязательный дайджест] — https://sostav.ru/publication/psevdozozh-pod-kontrol-84663.html
- GlobalSign — вторая волна отзыва TLS-сертификатов у российских сайтов (310 доменов) [10:00 МСК, обязательный дайджест] — https://www.seonews.ru/events/globalsign-provodit-vtoruyu-volnu-otzyva-tls-sertifikatov-u-rossiyskikh-saytov/
- VK AI Space получил поддержку мультиагентных систем [10:00 МСК, обязательный дайджест] — https://www.seonews.ru/events/na-platforme-vk-ai-space-poyavilas-podderzhka-multiagentnykh-sistem/
- Рынок ПО для ИИ в России вырастет в 4 раза к 2030 году — до 94,8 млрд руб. [10:00 МСК, обязательный дайджест] — https://www.seonews.ru/events/rossiyskiy-rynok-po-dlya-ii-k-2030-godu-vyrastet-v-chetyre-raza-issledovanie/
- Reddit и WPP выявили, как пользователи принимают решения о покупках [15:00 МСК, обязательный дайджест] — https://sostav.ru/publication/reddit-i-wpp-vyyavili-kak-polzovateli-prinimayut-resheniya-o-pokupkakh-84665.html
- Франшизы обеспечили START две трети просмотров оригинального контента [15:00 МСК, обязательный дайджест] — https://sostav.ru/publication/franshizy-obespechili-start-dve-treti-prosmotrov-originalnykh-proektov-84664.html
- PMC купил Vox Media Brands и стал крупнейшим цифровым издателем в мире [15:00 МСК, обязательный дайджест] — https://adindex.ru/news/tendencies/2026/06/19/346037.phtml

### 2026-06-20
- Рост аудитории Ozon и Wildberries замедлился [15:00 МСК, обязательный дайджест] — https://sostav.ru/publication/marketplejsy-sbavili-temp-84662.html
- Instagram добавил индивидуальные подписи к каждому фото в «карусели» [15:00 МСК, обязательный дайджест] — https://vc.ru/services/2986566-instagram-dobavil-podpisy-dlya-kazhdoi-fotografii-v-karuseli
- Le Monde готовится открыть платный контент для ИИ-агентов [15:00 МСК, обязательный дайджест] — https://adindex.ru/news/media/2026/06/19/346064.phtml
- 79% директоров по маркетингу сталкиваются с бюрократией при принятии решений — Lippincott [15:00 МСК, обязательный дайджест] — https://adindex.ru/news/researches/2026/06/19/346063.phtml
- В Алисе AI появились ИИ-персонажи с собственными характерами [15:00 МСК, обязательный дайджест] — https://www.seonews.ru/events/v-chate-s-alisoy-ai-poyavilis-ii-personazhi-s-sobstvennymi-kharakterami/


