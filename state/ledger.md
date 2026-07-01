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

### 2026-07-01
- VK внедрит ИИ-поиск в свои сервисы [15:00 МСК, обязательный дайджест] — https://adindex.ru/news/digital/2026/07/1/346799.phtml
- Авторы ВКонтакте заработали 1,4 млрд рублей с помощью VK AdBlogger [15:00 МСК, обязательный дайджест] — https://likeni.ru/events/avtory-vkontakte-zarabotali-1-4-mlrd-rubley-s-pomoshchyu-vk-adblogger-s-nachala-goda/
- Скандалы вокруг WPP ослабляют репутацию холдинга [15:00 МСК, обязательный дайджест] — https://sostav.ru/publication/skandaly-vokrug-wpp-oslablyayut-reputatsiyu-kholdinga-84958.html
- «Пятёрочка» отправила Галю спасать параллельные реальности [15:00 МСК, обязательный дайджест] — https://adindex.ru/news/creative/2026/07/1/346803.phtml
- Финансовые сервисы становятся одним из главных источников роста для маркетплейсов [15:00 МСК, обязательный дайджест] — https://sostav.ru/publication/finansovye-servisy-stanovyatsya-odnim-iz-glavnykh-istochnikov-rosta-dlya-marketplejsov-84955.html
- Бренды стали публиковать больше контента в «Максе» и «ВКонтакте» после замедления Telegram [14:00 МСК, обычный прогон] — https://sostav.ru/publication/brendy-stali-publikovat-bolshe-kontenta-v-makse-i-vkontakte-posle-zamedleniya-telegram-84957.html
- «Авито» масштабирует ИИ-ассистента для продавцов [12:03 МСК, обычный прогон] — https://sostav.ru/publication/avito-masshtabiruet-ii-assistenta-dlya-prodavtsov-84952.html
- Андрей Егоров назначен главным управляющим директором SkyAlliance [12:03 МСК, обычный прогон] — https://adindex.ru/news/hr/2026/07/1/346728.phtml
- Как перезапустить диалог с молодой аудиторией: кейс INFLUENCE BEAUTY, «Яндекс Музыки» и PHD [12:03 МСК, обычный прогон] — https://sostav.ru/publication/kak-perezapustit-dialog-s-molodoj-auditoriej-kejs-influence-beauty-yandeks-muzyki-i-phd-84937.html
- Яндекс Ритм запустил геотаргетинг для компаний из сферы услуг [11:00 МСК, обычный прогон] — https://ppc.world/news/yandeks-ritm-zapustil-geotargeting-dlya-kompaniy-iz-sfery-uslug/
- В Авито Рекламе появился таргетинг на пользователей, ожидающих ребёнка [11:00 МСК, обычный прогон] — https://ppc.world/news/v-avito-reklame-poyavilsya-targeting-na-polzovateley-ozhidayuschih-rebenka/
- Кейс МТС DSP и «Детский мир»: как увеличить продажи в высокий сезон на 30% [11:00 МСК, обычный прогон] — https://sostav.ru/publication/kejs-mts-dsp-i-detskij-mir-kak-uvelichit-prodazhi-v-shkolnyj-sezon-na-30-84896.html
- Рейтинг «Технологический Индекс»: Big Data [11:00 МСК, обычный прогон] — https://adindex.ru/news/digital/2026/07/1/346738.phtml
- Havas урегулировала спор с регулятором США по делу о рекламном сговоре [10:00 МСК, обязательный дайджест] — https://sostav.ru/publication/havas-uregulirovala-spor-s-regulyatorom-ssha-po-delu-o-reklamnom-sgovore-84947.html
- Omnicom выиграла глобальный медиаконтракт Adidas [10:00 МСК, обязательный дайджест] — https://sostav.ru/publication/omnicom-vyigrala-globalnyj-mediakontrakt-adidas-84946.html
- Wildberries купил контрольный пакет «Еаптеки» [10:00 МСК, обязательный дайджест] — https://sostav.ru/publication/wildberries-kupil-kontrolnyj-paket-eapteki-84943.html
- «М.Видео» и «Эльдорадо» объединятся в рамках маркетплейса [10:00 МСК, обязательный дайджест] — https://adindex.ru/news/tendencies/2026/07/1/346737.phtml

### 2026-06-30
- Яндекс обновил нейросетевую модель прогнозирования конверсий в Директе [11:00 МСК, обычный прогон] — https://sostav.ru/publication/yandeks-vnedril-v-svoyu-reklamnuyu-sistemu-novuyu-model-prognozirovaniya-konversij-84913.html
- WhatsApp запустил юзернеймы — бронирование уже открыто [11:00 МСК, обычный прогон] — https://adindex.ru/news/digital/2026/06/30/346472.phtml
- Vitamin.tools — 3-е место в рейтинге агрегаторов рекламных сервисов «Технологический Индекс» [12:02 МСК, обычный прогон] — https://adindex.ru/news/digital/2026/06/30/346478.phtml
- Перспективные категории Telegram-каналов для размещения рекламы в 2026 [12:02 МСК, обычный прогон] — https://sostav.ru/publication/perspektivnye-kategorii-telegram-kanalov-84898.html
- Вертикальные микродрамы впервые выйдут на российском ТВ [12:02 МСК, обычный прогон] — https://adindex.ru/news/media/2026/06/30/346502.phtml
- Яндекс Директ: товарные объявления для приложений теперь доступны для ретаргетинга [10:00 МСК, обязательный дайджест] — https://yandex.ru/adv/news/tovarnye-obyavleniya-dlya-prilozheniy-dostupny-dlya-retargetinga
- Минздрав предложил запретить рекламу фастфуда и сладкого с 7:00 до 22:00 [10:00 МСК, обязательный дайджест] — https://sostav.ru/publication/minzdrav-predlozhil-uzhestochit-regulirovanie-reklamy-i-markirovki-vrednoj-edy-84911.html
- Ретейл переходит на вертикальное видео: бюджеты на продвижение выросли на 40–70% [10:00 МСК, обязательный дайджест] — https://adindex.ru/news/researches/2026/06/30/346479.phtml
- Франция запретит рекламу Shein и Temu через блогеров и в диджитал-каналах [10:00 МСК, обязательный дайджест] — https://sostav.ru/publication/frantsiya-zapretit-reklamu-shein-84905.html
- Wildberries вводит 45-дневный срок уведомления продавцов об изменении комиссий и тарифов [10:00 МСК, обязательный дайджест] — https://sostav.ru/publication/wildberries-uvelichila-srok-uvedomleniya-prodavtsov-84908.html
- VK Реклама запустила чат-бот ассистента рекламодателя в MAX [13:00 МСК, обычный прогон] — https://www.seonews.ru/events/vk-reklama-zapustila-chat-bot-assistenta-reklamodatelya-v-max/
- Havas: 84% брендов остаются невидимыми для потребителей [13:00 МСК, обычный прогон] — https://sostav.ru/publication/havas-84-brendov-ostayutsya-nevidimymi-dlya-potrebitelej-84912.html
- IBM назначила Omnicom Media глобальным медиапартнёром [13:00 МСК, обычный прогон] — https://sostav.ru/publication/ibm-vybrala-omnicom-media-globalnym-mediapartnerom-84919.html
- Маркетплейсы и селлеры стали в разы чаще судиться: претензии выросли с 800 млн до 5,8 млрд руб. [13:00 МСК, обычный прогон] — https://adindex.ru/news/tendencies/2026/06/30/346470.phtml
- Яндекс Директ: ТГО переходят в комбинаторный формат — автообновление с 14 июля [15:01 МСК, обязательный дайджест] — https://yandex.ru/adv/news/obnovlenie-tekstovo-graficheskih-obyavleniy-do-kombinatornyh-protsess-i-osobennosti
- Wildberries запустил биржу карточек товаров для продавцов [15:01 МСК, обязательный дайджест] — https://sostav.ru/publication/wildberries-zapustil-birzhu-kartochek-tovarov-dlya-prodavtsov-84922.html
- ВКонтакте внедрила ИИ-модели рекомендаций товаров: клики ×5, переходы на маркетплейсы ×15, заказы ×20 [15:01 МСК, обязательный дайджест] — https://likeni.ru/events/vkontakte-vnedrila-novye-ii-modeli-dlya-rekomendatsiy-tovarov/
- Кирилл Тренин возглавит кластер Kion вместо Алексея Иванова [15:01 МСК, обязательный дайджест] — https://adindex.ru/news/hr/2026/06/30/346498.phtml
- Исследование Sape: как ChatGPT, Алиса и Gemini ранжируют бизнес в ИИ-поиске [17:01 МСК, обычный прогон] — https://www.seonews.ru/events/kak-chatgpt-alisa-i-gemini-ranzhiruyut-servisy-bronirovaniya-oteley-i-chto-s-etim-delat-issledovanie-sape/
- РОЦИТ: рынок российских соцплатформ достиг зрелости — ВК и ОК лидеры, Rutube/TenChat/Дзен — ниши [17:01 МСК, обычный прогон] — https://sostav.ru/publication/rotsit-rossijskij-rynok-sotsplatform-pereshel-ot-importozameshcheniya-k-sobstvennoj-ekosisteme-84929.html
- Аутентичность против глянца: «несовершенный» креатив продаёт лучше в 2026 [17:01 МСК, обычный прогон] — https://sostav.ru/publication/autentichnost-protiv-glyantsa-pochemu-nesovershennyj-84881.html
- Бренду не нужно быть везде: как компании раздувают маркетинговые бюджеты [17:01 МСК, обычный прогон] — https://sostav.ru/publication/brendu-ne-nuzhno-byt-vezde-kak-kompanii-sami-razduvayut-marketingovye-byudzhety-84924.html
- Петр Середкин (экс-VK) перешёл в «Яндекс Плюс AdTech», спецпроекты Кинопоиска [17:01 МСК, обычный прогон] — https://adindex.ru/news/hr/2026/06/30/346625.phtml
- Апелляционный суд подтвердил законность сделки по продаже рекламной группы АДВ [18:02 МСК, обычный прогон] — https://adindex.ru/news/right/2026/06/30/346627.phtml
- Workspace опубликовал Рейтинг SEO-компаний и 14 топов по диджитал-услугам [18:02 МСК, обычный прогон] — https://www.seonews.ru/events/workspace-opublikoval-reyting-seo-kompaniy-i-eshche-14-topov-po-drugim-didzhital-uslugam/
- Механика азарта: почему блогеры перестали реагировать на классические офферы [19:01 МСК, обычный прогон] — https://sostav.ru/publication/mekhanika-azarta-pochemy-blogery-perestali-reagirovat-na-klassicheskie-offery-84900.html
- Зумеры чаще подписываются на бренды, если нравится основатель компании [19:01 МСК, обычный прогон] — https://sostav.ru/publication/zumery-chashche-podpisyvayutsya-na-brendy-esli-im-nravitsya-osnovatel-kompanii-84936.html

### 2026-06-29
- Суд рассмотрит иск о продаже рекламной группы АДВ [10:01 МСК, обязательный дайджест] — https://adindex.ru/news/right/2026/06/29/346292.phtml
- Instagram улучшит подбор контента для пользователей [10:01 МСК, обязательный дайджест] — https://adindex.ru/news/media/2026/06/29/346294.phtml
- Nissan направляет до 60% маркетингового бюджета на digital, ИИ и инфлюенсеров [10:01 МСК, обязательный дайджест] — https://sostav.ru/publication/nissan-napravlyaet-do-60-marketingovogo-byudzheta-na-digital-ii-i-inflyuenserov-84866.html
- В Калифорнии запретили громкую рекламу в стриминговых сервисах [10:01 МСК, обязательный дайджест] — https://sostav.ru/publication/v-kalifornii-zapretili-gromkuyu-reklamu-v-strimingovykh-servisakh-84865.html
- Рейтинг «Технологический Индекс». Комплексные ИТ-платформы [11:00 МСК, обычный прогон] — https://adindex.ru/news/digital/2026/06/29/346302.phtml
- WPP лидирует на Cannes Lions 2026 [11:00 МСК, обычный прогон] — https://sostav.ru/publication/wpp-lidiruet-na-cannes-lions-2026-84869.html
- OpenAI представила серию моделей GPT-5.6: Sol, Terra и Luna [11:00 МСК, обычный прогон] — https://ppc.world/news/openai-predstavila-gpt-56-sol-terra-i-luna/
- Яндекс представил платформу для создания ИИ-агентов на базе «Алисы AI» [13:01 МСК, обычный прогон] — https://sostav.ru/publication/yandeks-predstavil-platformu-dlya-sozdaniya-ii-agentov-na-baze-alisy-ai-84884.html
- Google завершил June 2026 Spam Update [13:01 МСК, обычный прогон] — https://www.seonews.ru/events/google-vykatil-i-zavershil-june-2026-spam-update/
- Почти половина россиян совершали покупки по рекомендациям ИИ [13:01 МСК, обычный прогон] — https://adindex.ru/news/researches/2026/06/29/346321.phtml
- Яндекс запустил реферальную программу KITβ для агентств и веб-студий [15:00 МСК, обязательный дайджест] — https://yandex.ru/adv/news/referralnaya-programma-yandex-kit-nachnite-zarabatyvat
- 98% маркетологов запускают рекламные кампании с задержкой [15:00 МСК, обязательный дайджест] — https://sostav.ru/publication/98-marketologov-zapuskayut-reklamnye-kampanii-s-zaderzhkoj-84883.html
- Алексей Иванов уходит с поста гендиректора «Кион» (МТС) [15:00 МСК, обязательный дайджест] — https://sostav.ru/publication/aleksej-ivanov-ukhodit-s-posta-gendirektora-kontentnogo-klastera-kion-84877.html
- Последний день Cannes Lions 2026: ролики года, титановые идеи и реклама, которая меняет мир [16:02 МСК, обычный прогон] — https://sostav.ru/publication/poslednij-den-kannskikh-lvov-2026-roliki-goda-titanovye-idei-i-reklama-kotoraya-menyaet-mir-84882.html
- Подборка профессиональных событий на июль [16:02 МСК, обычный прогон] — https://adindex.ru/news/marketing/2026/06/29/346349.phtml
- BBFC применил нейросеть для классификации всего каталога HBO Max [16:02 МСК, обычный прогон] — https://adindex.ru/news/media/2026/06/29/346299.phtml
- Rabbit Group запустила Bloggers Booking — платформу для агентств и менеджеров блогеров [17:01 МСК, обычный прогон] — https://adindex.ru/news/marketing/2026/06/29/346372.phtml
- Яндекс Директ добавил ИИ-управление рекламой в мессенджерах [17:01 МСК, обычный прогон] — https://adindex.ru/news/marketing/2026/06/29/346372.phtml
- Суд оштрафовал Pinterest, Telegram и Twitch на 3,5 млн рублей каждый [18:01 МСК, обычный прогон] — https://sostav.ru/publication/sud-oshtrafoval-pinterest-telegram-i-twitch-na-3-5-mln-rublej-kazhdyj-84899.html
- Что такое «плохо»: шесть поводов для тревоги на рекламном рынке [18:01 МСК, обычный прогон] — https://sostav.ru/publication/chto-takoe-plokho-sem-povodov-dlya-trevogi-na-reklamnom-rynke-84886.html
- Кейс «Дикси»: сегменты на телеком-данных T2 повысили предпочтение бренда на 50% [18:01 МСК, обычный прогон] — https://sostav.ru/publication/kejs-diksi-84810.html

### 2026-06-28
- В бета-версии Telegram появились сообщества — объединения нескольких групп наподобие Discord [10:02 МСК, обязательный дайджест] — https://kod.ru/telegram-communities-beta
- Markdown-редактор Telegram добрался до бета-версии для Android [10:02 МСК, обязательный дайджест] — https://kod.ru/telegram-markdown-editor-beta-android
- SEOnews: итоги рейтинга «SEO глазами клиентов 2026» [10:02 МСК, обязательный дайджест] — https://www.seonews.ru/events/seonews-podvel-itogi-masshtabnogo-reytinga-seo-glazami-klientov-2026/
- ВГТРК отчитался об убытках и увеличении времени просмотра контента [15:00 МСК, обязательный дайджест] — https://adindex.ru/news/tendencies/2026/06/25/346222.phtml
- МВД поддержало признание использования ИИ отягчающим обстоятельством при преступлениях [15:00 МСК, обязательный дайджест] — https://kod.ru/mvd-ai-otyagchayushe
- IKEA превратила товары для дома в национальные флаги в честь ЧМ-2026 [15:00 МСК, обязательный дайджест] — https://sostav.ru/publication/ikea-prevratila-tovary-dlya-doma-v-natsionalnye-flagi-v-chest-chm-2026-84854.html

### 2026-06-27
- XII «Технологический Индекс» 2026: рейтинг лучших платформ автоматизации рекламных кампаний [10:01 МСК, обязательный дайджест] — https://adindex.ru/news/digital/2026/06/26/346281.phtml
- Почти 10% вакансий в рекламе требуют ИИ-навыков — в 5 раз выше среднего по рынку (HeadHunter) [10:01 МСК, обязательный дайджест] — https://adindex.ru/news/researches/2026/06/26/346283.phtml
- Новое агентство Reacta для инфлюенс-маркетинга и назначения в Кион, МТС Live [10:01 МСК, обязательный дайджест] — https://adindex.ru/news/hr/2026/06/26/346269.phtml
- Уведомления VK и Mail на iPhone: почему пропали и как вернуть [15:00 МСК, обязательный дайджест] — https://hi-tech.mail.ru/news/150243-uvedomleniya-vk-mail-iphone-app-store/
- США частично сняли запрет на использование ИИ-модели Anthropic [15:00 МСК, обязательный дайджест] — https://sostav.ru/publication/ssha-chastichno-snyali-zapret-na-ispolzovanie-ii-modeli-anthropic-84851.html
- Suno даст начинающим артистам деньги на маркетинг и продвижение [15:00 МСК, обязательный дайджест] — https://adindex.ru/news/marketing/2026/06/26/346273.phtml
- Авито Реклама запустила ретаргетинг по кликам на баннер [17:00 МСК, обычный прогон] — https://www.seonews.ru/events/avito-reklama-zapustila-retargeting-po-klikam-na-banner/
- Silver Mercury 2026 изменил расстановку сил в Национальном рейтинге рекламных агентств [17:00 МСК, обычный прогон] — https://ratings.sostav.ru/news/silver-mercury

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

