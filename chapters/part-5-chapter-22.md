--- 
layout: chapter
title: "Open Data and Algorithmic Regulation"
chapter: 22
part: 5
author: 
  - 
    name: Tim O’Reilly
    job: Founder and CEO
    employer: O'Reilly Media Inc.
    photo_url: /images/authors/tim.png
    twitter: timoreilly
    about: "Founder and CEO of O’Reilly Media."
featured: true

permalink: /part-5/open-data-and-algorithmic-regulation/
---

Regulation is the bugaboo of today’s politics. We have too much of it in most areas, we have too little of it in others, but mostly, we just have the wrong kind, a mountain of paper rules, inefficient processes, and little ability to adjust the rules or the processes when we discover the inevitable unintended results.

法規條款是今日政治運作所底下所產生的一個嚇人的的東西。 我們有太多的法規條款出現在各個領域裡，但是在需要的領域裡卻又少之又少，並且大部分的時候，他們是以錯誤的形式出現像成堆像小山般的文件或沒有效率的流程。當我們發現我們無可避免地要面對這些不想要地結果時，卻沒有能力調整這些規則或程序。

Consider, for a moment, regulation in a broader context. Your car’s electronics regulate the fuel-air mix in the engine to find an optimal balance of fuel efficiency and minimal emissions. An airplane’s autopilot regulates the countless factors required to keep that plane aloft and heading in the right direction. Credit card companies monitor and regulate charges to detect fraud and keep you under your credit limit. Doctors regulate the dosage of the medicine they give us, sometimes loosely, sometimes with exquisite care, as with the chemotherapy required to kill cancer cells while keeping normal cells alive, or with the anesthesia that keeps us unconscious during surgery while keeping vital processes going. ISPs and corporate mail systems regulate the mail that reaches us, filtering out spam and malware to the best of their ability. Search engines regulate the results and advertisements they serve up to us, doing their best to give us more of what we want to see.

讓我們思考一下，再更廣闊的情境底下思考規範是什麼。你車子的電子元件控制燃料與空氣在引擎裡的比例，好達到最佳的燃油效率與最低廢氣排放量。飛機的自動駕駛系統控制無數有可能影響飛機平衡與往正確方向行駛的因素。信用卡公司監測與控制收付費交易，好做錯誤偵測並使你的消費維持在你的信用範圍裡。醫生規定我們的藥物使用劑量，有時候條件比較寬鬆，有時候需要細緻的調理，尤其是同時要使用化學藥物殺死癌細胞但又要讓正常細胞活著。或者是使用麻醉藥讓我們在手術時失去意識，但重要的身體功能依然有在運作。ISP與電子郵件系統替我們每日收到的郵件規定了一系列的規則，這些規則盡它們所能來過濾掉垃圾郵件和惡意軟體。搜尋引擎決定要給我們看什麼樣的搜尋結果與廣告，而盡其所能來確保結果是我們想要看到的內容

What do all these forms of regulation have in common?

1. A deep understanding of the desired outcome
2. Real-time measurement to determine if that outcome is being achieved
3. Algorithms (i.e. a set of rules) that make adjustments based on new data
4. Periodic, deeper analysis of whether the algorithms themselves are correct and performing as expected.

那麼到底這些法規或規範有什麼樣的共同點？

1. 對想要的目的有很清楚的認識
2. 有即時的衡量機制來決定是否有達到目的
3. 演算法(一系列規則)會根據新資料來調整
4. 週期性的深入分析是否演算法本身是正確的並且有照預期運作。

There are a few cases—all too few—in which governments and quasi-governmental agencies regulate using processes similar to those outlined above. Probably the best example is the way that central banks regulate the money supply in an attempt to manage interest rates, inflation, and the overall state of the economy. Surprisingly, while individual groups might prefer the US Federal Reserve to tighten or loosen the money supply at a different time or rate than they do, most accept the need for this kind of regulation.

在政府單位或者是半政府單位裡幾乎沒有任何例子-非常稀少-使用類似上述條件的方式來做監管或或規範。或許最好的例子是中央銀行透過調節貨幣供應來管理利率的方法。這套方法可以同時調整通貨膨脹和其它所有的經濟狀態。令人驚訝的是，一般個人團體他們比較偏好美國聯邦銀行來規定什麼時侯該放鬆或收縮貨幣供應的比例。大部分人同意這樣的規範機制是必要的。

為何會是這套機制？

1. 因為我們清楚的知道我們要的目的是什麼
2. 有一套經常性的衡量標準與回報機制，我們可以透過公開資料得知是否目標有達成
3. 當目的沒有達成時會做適當調整

Contrast this with the normal regulatory model, which focuses on the rules rather than the outcomes. How often have we faced rules that simply no longer make sense? How often do we see evidence that the rules are actually achieving the desired outcome?

把這套機制和其他一般的規範模式做比較，一般的規範模式著重在規則而不是結果。到底我們有多常遇到沒道理的規則？又有多常看到證據顯示這些規範有達到預期的結果呢？

Sometimes the “rules” aren’t really even rules. Gordon Bruce, the former CIO of the city of Honolulu, explained to me that when he entered government from the private sector and tried to make changes, he was told, “That’s against the law.” His reply was “OK. Show me the law.” “Well, it isn’t really a law. It’s a regulation.” “OK. Show me the regulation.” “Well, it isn’t really a regulation. It’s a policy that was put in place by Mr. Somebody twenty years ago.” “Great. We can change that!”

有時候甚至規則並不真的是規則。一位Honolulu市的前財政長，Gorden Bruce向我們解釋為何如此。當他從私人部門進入到公部門時，他嘗試做些改變，但他常被告知說"這樣做會違反法律規定"。於是他就回答：「好，請你告訴我是哪一條法律？」「嗯，事實上這並不真的是一套法規條例，這只是某位先生在20幾年前訂下的規矩。」「太好了，那我們就改變它吧！」

But often, there really is a law or a regulation that has outlived its day, an artifact of a system that takes too long to change. The Obama Administration has made some efforts to address this, with a process of both “regulatory lookback” to eliminate unnecessary regulations, and an increased effort to quantify the effect of regulations (White House, 2012).

但是經常會有一些規定真的是法律規範，而它們早已是不合時宜的古董，只因為存在太久以致於無法改變。歐巴馬政府已經做了一些努力來改變這個情況。透過一套法規回溯機制的流程來消除不需要的法規條例並同時努力量化規範機制的"效果"。

But even this kind of regulatory reform doesn’t go far enough. The laws of the United States have grown mind-bogglingly complex. The recent healthcare reform bill was nearly two thousand pages. The US Constitution, including two hundred years worth of amendments, is about twenty-one pages. The National Highway Bill of 1956, which led to the creation of the US Interstate Highway system, the largest public works project in history, was twenty-nine pages.

但即使像這樣重新改革監管機制還是走的不夠多。美國法律的規模已成長到令人心神震撼的複雜度。像最近的健保改革法案有近2000多頁。美國的憲法包含200多年來的各式修正案，也才20多頁。1956年引領美國創造了令人驕傲且是有史以來最大的公共工程高速公路系統的國家高速公路法案，也才約29頁。

Laws should specify goals, rights, outcomes, authorities, and limits. If specified broadly, those laws can stand the test of time.

一個法律需要標示清楚目標、權利、結果、授權與限制。如果標示的範圍更廣，這些法律可以承受更長時間的測試。

Regulations, which specify how to execute those laws in much more detail, should be regarded in much the same way that programmers regard their code and algorithms, that is, as a constantly updated toolset to achieve the outcomes specified in the laws.

(漏譯)

Increasingly, in today’s world, this kind of algorithmic regulation is more than a metaphor. Consider financial markets. New financial instruments are invented every day and implemented by algorithms that trade at electronic speed. How can these instruments be regulated except by programs and algorithms that track and manage them in their native element in much the same way that Google’s search quality algorithms, Google’s “regulations”, manage the constant attempts of spammers and black hat SEO experts to game the system?

漸漸地，在今日的世界裡，演算型法規已經不再是一個譬喻。考慮到像金融市場般，每天都發明新的金融工具，並且透過演算法快速地經由電腦交易。像這樣的金融工具非常難被監督管理，除非像Google一樣從基礎上就使用程式和演算法來追蹤與管理自家的搜尋品質演算法。像Google這樣的監督機制，經常要處理眾多的垃圾信件和阻擋惡意的SEO駭客利用系統軟體來操弄結果。

Revelation after revelation of bad behavior by big banks demonstrates that periodic bouts of enforcement aren’t sufficient. Systemic malfeasance needs systemic regulation. It’s time for government to enter the age of big data. Algorithmic regulation is an idea whose time has come.

在大型銀行的惡意行為被揭露以後，諸如此類的行為向世人展示定期的執法行動是不夠的，系統性的貪瀆需要系統性的監管。現在是政府部門進入巨量資料的時候了，而演算法式的監管概念的時代已經來臨。

### Open Data and Government as a Platform
### 開放資料與政府做為一個平台

There are those who say that government should just stay out of regulating many areas, and let “the market” sort things out. But there are many ways in which bad actors take advantage of a vacuum in the absence of proactive management. Just as companies like Google, Microsoft, Apple, and Amazon build regulatory mechanisms to manage their platforms, government exists as a platform to ensure the success of our society, and that platform needs to be well regulated!

有很多人認為政府應該退出眾多領域的監管，交由市場機制來運作。但是當沒有積極的管理時，有很多糟糕的操作者會利用這樣的真空來上下其手。像Google, Apple,Amazon和微軟等公司會建構一套套的規範機制來管理旗下眾多平台的運作，而政府存在的意義某種程度上也是一個確保社會正常運作的平台，而我們需要更細緻地來規範這個平台的運作。

Right now, it is clear that agencies like the SEC just can’t keep up. In the wake of Ponzi schemes like those of Bernie Madoff and Allen Stanford, the SEC has now instituted algorithmic models that flag for investigation hedge funds whose results meaningfully outperform those of peers using the same stated investment methods. But once flagged, enforcement still goes into a long loop of investigation and negotiation, with problems dealt with on a case-by-case basis. By contrast, when Google discovers via algorithmic means that a new kind of spam is damaging search results, they quickly change the rules to limit the effect of those bad actors. We need to find more ways to make the consequences of bad action systemic, rather than subject to haphazard enforcement.

現在，我們很清楚的知道像SEC這樣的單位依然無法跟上當前的局勢。所幸，在眾多學者的幫忙下，SEC現在已經建置了一套演算法模型，其概念是當某個私募基金其操作結果有顯著性的超越其他同類型基金時，而又使用相同的投資方法時，該模型就會標記該私募基金有調查的必要。但即使如此，執法單位依然需要經過一長串的深入調查，並且根據每個處理問題的情況來談判。相反的，當Google 透過演算法這樣的方法找到有新的垃圾廣告傷害了搜尋結果時，他們會迅速地改變規則來限制這些惡意操作者的影響力。我們需要更多的方法來系統化惡意行為的後果，而不是仰賴偶爾的執法調查。

This is only possible when laws and regulations focus on desired outcomes rather than the processes used to achieve them.

這只有當設計法律與規範時，把目標放在想要什麼樣的結果而不是用什麼樣的方式達成，才有可能。

There’s another point that’s worth making about SEC regulations. Financial regulation depends on disclosure - data required by the regulators to be published by financial firms in a format that makes it easy to analyze. This data is not just used by the regulators themselves, but is used by the private sector in making its own assessments of the financial health of firms, their prospects, and other financial decisions. You can see how the role of regulators in requiring what is, in effect, open data, makes the market more transparent and self-policing.

關於SEC的監管機制還有其他點值得去做。金融監管依靠的是資訊揭露--監管者要求金融公司把資料整理成易於分析的格式然後公開。這些資料不只由監管單位使用，也會由私部門用來製作自己的公司財務健康資產負債表，他們的觀點，還有其他的金融決策。你可以看到監管者如何透過扮演要求資料有效開放的腳色，使的市場更加透明且自律。

You can also see here that the modernization of how data is reported to both the government and the market is an important way of improving regulatory outcomes. Data needs to be timely, machine readable, and complete. (See Open Government Working Group, 2007.) When reporting is on paper or in opaque digital forms like PDF, or released only quarterly, it is much less useful.

你也可以看到資料呈報給政府單位與市場的現代化方法是很重要的，因為這個方法加強監管的成果。這些資料是要即時的，完整的，且製作成機器可讀的格式。(請見 OpenGonvernment 2007 工作小組 )當資料的呈現是印在紙上或是存成不可轉換的格式(如pdf)，或只釋出部分的資料時，這樣子的資料是沒有價值的

When data is provided in re-usable digital formats, the private sector can aid in ferreting out problems as well as building new services that provide consumer and citizen value. This is a goal of the US Treasury Department’s “Smart Disclosure” initiative (see http://www.data.gov/consumer/page/consumer-about). It is also central to the efforts of the new Consumer Financial Protection Bureau.

當資料是以可重複使用的數位格式供應時，私人部門可以把重點放在發現問題與建立新的服務來提供消費者或公民更多價值。這是美國財政部智慧接露方式一開始的目標，這也很接近消費者金融保護管理局的努力。

When government regulators focus on requiring disclosure, that lets private companies build services for consumers, and frees up more enforcement time to go after truly serious malefactors.

當政府監管者把目標放在資訊揭露，讓私人公司建立消費者服務並且讓執法單位空出更多時間來對付真正嚴重的貪瀆事件。

### Regulation Meets Reputation
### 當法規監督遇上信譽評等

It is true that “that government governs best that governs least.” But the secret to “governing least” is to identify key outcomes that we care about as a society—safety, health, fairness, opportunity—encode those outcomes into our laws, and then create a constantly evolving set of regulatory mechanisms that keep us on course towards them.

"政府最好的管理方式就是它幾乎不要管理"，但是要政府幾乎不要管理的訣竅就是要去辨認社會最在意的關鍵成果是什麼-- 安全，健康，公平，機會--把這些概念融入法律裡，並且促成監管機制成為經常在進步的集合體，讓我們在駛往這些理想的大道上

We are at a unique time when new technologies make it possible to reduce the amount of regulation while actually increasing the amount of oversight and production of desirable outcomes.

我們正處於歷史上一個獨特的時刻，這是一個新科技有可能降低監管的量同時又確實能增加忽略的量與想要的成果的產出。

Consider taxi regulation. Ostensibly, taxis are regulated to protect the quality and safety of the consumer experience, as well as to ensure that there are an optimal number of vehicles providing service at the time they are needed. In practice, most of us know that these regulations do a poor job of ensuring quality or availability. New services like Uber and Hailo work with existing licensed drivers, but increase their availability even in less-frequented locations, by using geolocation on smartphones to bring passengers and drivers together. But equally important in a regulatory context is the way these services ask every passenger to rate their driver (and drivers to rate their passenger). Drivers who provide poor service are eliminated. As users of these services can attest, reputation does a better job of ensuring a superb customer experience than any amount of government regulation.

想像計程車的法規條例，很明顯地，我們透過法規監督計程車來保障消費者消費的安全與品質，並且保證可以在消費者需要服務的時候，在當下提供最佳的車輛數目。實際上，我們大部分的人知道這些法規沒有辦法保證品質與可用性。新興服務像Uber和Hailo與既存的合格駕駛者合作，他們使用智慧型手機上的地理資訊，把乘客與駕駛者湊在一起，提高了駕駛者在不好搭到車的地方也可以有生意做。但在這種情況下的規範方式，同樣重要的是這些服務邀求每個乘客和和駕駛者互相給對方評價。服務差的駕駛者會消失。當這些服務的使用者可以進行評價時，這樣的機制可以確保消費者獲得比一堆政府規範帶來的更好的服務體驗。

Peer-to-peer car services like RelayRides, Lyft, and Sidecar go even further, bypassing regulated livery vehicles and allowing consumers to provide rides to each other. Here, reputation entirely replaces regulation, seemingly with no ill effect. Governments should be studying these models, not fighting them, and adopting them where there are no demonstrable ill effects.

群眾汽車服務像RelayRide, Lyft和Sidecar領先業界更多，他們即時地提供車輛，允許乘客們互相載對方。在這個情況裡，評價機制完全取代了規範機制，並且看起來沒有任何副作用。政府部門應該研究這些模式，當沒有顯著地副作用時採納這些模式，而不是打擊他們。

Services like AirBnB provide similar reputation systems that protect consumers while creating availability of lodging in neighborhoods that are often poorly served by licensed establishments.

像AirBnB這類提供相似的評價系統的服務，他們會讓那些獲得差勁服務的消費者住到附近的空房

Reputation systems are a great example of how open data can help improve outcomes for citizens with less effort by overworked regulators and enforcement officials.

評價系統是一個很好的例子，他說明了開放資料可以幫助公民促進政策的成果，且同時減少工作過度的監管單位和執法官員的負擔。

Sites like Yelp provide extensive consumer reviews of restaurants; those that provide poor food or service are flagged by unhappy customers, while those that excel are praised.

像Yelp這樣的網站提供消費者對餐廳的評論，那些提供差勁的食物或服務的餐廳會被不開心的消費者檢舉，而優良的餐廳則會被稱頌。

There are a number of interesting new projects that attempt to combine the reach and user-friendliness of consumer reputation systems with government data. One recent initiative, the LIVES standard, developed by San Francisco, Code for America, and Yelp, brings health department inspection data to Yelp and other consumer restaurant applications, using open data to provide even more information to consumers. The House Facts standard does the same with housing inspection data, integrating it with internet services like Trulia

有一定數量的有趣專案試圖要去結合使用者友善的消費者評價系統和政府資料。一個最近的新興計畫，是由舊金山，Code for America和Yelp發起的LIVES標準，他們把衛生部門的調查資料給Yelp和其他提供消費者餐廳的服務，利用開放資料的力量，讓消費者有更多的資訊。同樣地，House Fact 標準也結合了房屋調查資料並和像Tulia這樣的服務整合在一起。

Another interesting project that actually harnesses citizen help (rather than just citizen opinion) by connecting a consumer-facing app to government data is the PulsePoint project, originally started by the San Ramon, California fire department. After the fire chief had the dismaying experience of hearing an ambulance pull up to the restaurant next door to the one in which he was having lunch with staff including a number of EMR techs, he commissioned an app that would allow any citizen with EMR training to receive the same dispatch calls as officials.

其他有趣的專案像是PulsePoint，透過連結消費類型的服務app與政府資料，確實地利用了公民的幫助(不只是意見而已)。這個計畫原先是由在加州消防部門的San Ramon發起。當這位消防隊長有一次和幾位有EMR技術執照的同事在餐廳吃飯，他們聽到了救護車匆忙停在隔壁的餐廳，但卻依然發生遺憾。有了這次經驗，他開放授權給一個app，這個app允許有經過EMR訓練的公民們可以收到同樣給公部門的緊急電話

### The Role of Sensors in Algorithmic Regulation
### 感測器在演算型法規裡扮演的角色

Increasingly, our interactions with businesses, government, and the built environment are becoming digital, and thus amenable to creative forms of measurement, and ultimately algorithmic regulation.

漸漸地，我們和公部門，商家與環境的互動開始數位化，因此適合創制評量的形式與最終地演算型規範。

For example, with the rise of GPS (not to mention automatic speed cameras), it is easy to foresee a future where speeding motorists are no longer pulled over by police officers who happen to spot them, but instead automatically ticketed whenever they exceed the speed limit.

舉例來說，因為GPS的興起，我們可以輕易的預見在未來，超速的駕駛不再是被碰巧在執勤的警察攔下，取而代之的是當他們超速時，隨時由系統自動開罰。

Most people today would consider that intrusive and alarming. But we can also imagine a future in which that speed limit is automatically adjusted based on the amount of traffic, weather conditions, and other subjective conditions that make a higher or lower speed more appropriate than the static limit that is posted today. The endgame might be a future of autonomous vehicles that are able to travel faster because they are connected in an invisible web, a traffic regulatory system that keeps us safer than today’s speed limits. The goal, after all, is not to have cars go slower than they might otherwise, but to make our roads safe.

在今日，大部分的人會覺得這樣受到冒犯與警告。但我們也可以想像在未來，速限是根據交通流量，天氣狀況，各式各樣會影響到交通的條件和情況來自動調整，在這些條件下，或高或低的調整速限對於交同的改善會比現今只維持固定的速限更佳妥當。最終的情況可能會演變成一個充滿了自動駕駛載具的未來，透過連結上無形的網路，他們可以移動的更迅速。這個無形的網路會是一個交通管制系統，它可以讓我們更安全的旅行。最終，這套系統的目的是要讓車子能開的更快，但卻又同時讓道路更安全。

While such a future no doubt raises many issues and might be seen by many as an assault on privacy and other basic freedoms, early versions of that future are already in place in countries like Singapore and can be expected to spread more widely.

毫無無疑地，這樣的未來會產生很多的意見並且可能會被視為侵害了隱私與許多基本的自由權，像新加坡這樣的國家已經有這套系統的初期版本，並糗我們可以預期它會散播到更多地方。

Congestion pricing on tolls, designed to reduce traffic to city centers, is another example. Systems such as those in London where your license plate is read and you are required to make a payment will be replaced by automatic billing. You can imagine the costs of tolls floating based not just on time of day but on actual traffic.

像被設計來減少通往市中心車流量的塞車收費機制，是另外一個例子。在倫敦類似的系統是當你的通行卡被讀取時，你就要付費，這樣的系統未來會變成自動付費。你可以想像那些收費站的收費標準將不會是根據每日通過的時段，而是根據當時實際的車流量。

Smart parking meters have similar capabilities—parking can cost more at peak times, less off-peak. But perhaps more importantly, smart parking meters can report whether they are occupied or not, and eventually give guidance to drivers and car navigation systems, reducing the amount of time spent circling while aimlessly looking for a parking space.

智慧停車收費器也會有類似的功能，在尖峰時段停車會收取比離峰時段更多費用。但或許最重要地是，智慧停車收費器可以回報哪些位置是空的而哪些不是，並且最終給駕駛者和車輛導航系統引導，降低花費在漫無目標地尋找車位的時間。

As we move to a future with more electric vehicles, there are already proposals to replace gasoline taxes with miles driven—reported, of course, once again by GPS.

當我們朝著一個有愈來愈多電動車的未來前進，我們已經有取代燃料稅的可行方案，像是根據你已經行使的里程數來收費，而再一次的，我們利用了GPS

Moving further out into the future, you can imagine public transportation reinventing itself to look much like Uber. It’s a small leap from connecting one passenger and one driver to picking up four or five passengers all heading for the same destination, or along the same route. Smartphone GPS sensors and smart routing algorithms could lead to a hybrid of taxi and bus service, bringing affordable, flexible public transportation to a much larger audience.

愈思考未來會發生的可能情況，你可以想像未來的大眾運輸系統會重新改造自己，使它變的和Uber很像。這一切只是從把一個乘客和一個駕駛連結起來到把四、五位前往同樣目的或有相同路線的乘客湊在一起而已。智慧型手機的GPS感應器和智慧型路線規劃演算法可以促成一個混合計程車和巴士的服務，讓更多的人可以享受到可負擔的、有彈性的大眾運輸系統。

### The First Step is Measurement

### 第一步是評量標準

Data driven regulatory systems need not be as complex as those used by Google or credit card companies, or as those imagined above. Sometimes, it’s as simple as doing the math on data that is already being collected and putting in place new business processes to act on it.

資料驅動的管制系統並不需要像Google或信用卡公司或之前提及的系統一樣複雜。有些時候，他們只是簡單地對那些已經收集很久地資料進行計算，並且置入新的商業流程來運作。

For example, after hearing of the cost of a small government job search engine for veterans ($5 million per year), I asked how many users the site had. I was told “A couple of hundred.” I was understandably shocked, and wondered why this project was up for contract renewal. But when I asked a senior official at the General Services Administration if there were any routine process for calculating the cost per user of government websites, I was told, “That would be a good idea!” It shouldn’t just be a good idea; it should be common practice!

舉例而言，當我聽到一個小的政府部門專案的費用，這案子是專門提供給退役軍人使用的搜尋引擎(一年500萬美金)，我問這個網站一年有多少人使用。他們告訴我一年約幾百人。我徹底地被嚇到，並且想要知道為何這個專案的合約可以一直續約。但是當我詢問一位在General Services Administration工作的資深官員，是否有任何的既定流程用來計算政府網站花在每位使用者上的成本時，他們總告訴我：「那真是個好點子！」這不應該只是個好點子，他應該是個一般的工作流程。

Every commercial website not only measures its traffic, but constantly makes adjustments to remove features that are unused and to test new ones in their place. When a startup fails to gain traction with its intended customers, the venture capitalists who backed it either withdraw their funding, or “pivot” to a new approach, trying multiple options till they find one that works. The “lean startup” methodology now widely adopted in Silicon Valley considers a startup to be “a machine for learning,” using data to constantly revise and tune its approach to the market. Government, by contrast, seems to inevitably double down on bad approaches, as if admitting failure is the cardinal sin.

每個商業網站不只會監測流量，還會經常的做些調整像是移除每個沒宰使用的功能或是測試一個新的功能。當一個Start-up沒有辦法去獲得他們想要的客戶的黏著度時，投資的VC們會撤回資金或者是轉向一個新的實踐方法，他們會嘗試多種選項直到成功地找到可行的方法為止。現在被矽谷廣泛採用的精實創業方法論認為一間新創公司要像一台“學習的機器”，不斷的利用資料來改寫或測試他們作生意的方法。相反地，政府部門看起來似乎不可避免地花兩倍時間在錯誤的方法上，似乎承認失敗是原罪。

Simple web metrics considered as part of a contract renewal are one simple kind of algorithmic regulation that could lead to a massive simplification of government websites and reduction of government IT costs. Other metrics that are commonly used on the commercial web include time on site; abandon rate (people who leave without completing a transaction); and analysis of the paths people use to reach the desired information.

簡單的網路評量方程式可以考慮作為合約續約的一部份。這是一種可以達成簡化大量的政府網站和降低政府部門IT成本的演算型法規。其他一般在商業網站上常用評量方式包含使用者停留在網站上的時間，放棄地比率(人們沒有完成交易就離開該網站)和分析人們取得想要的資訊的路俓。

There is other data available as well. Many commercial sites use analysis of search queries to surface what people are looking for. The UK Government Digital Service used this technique in their effort to redesign the Gov.UK site around user needs rather than around the desires of the various cabinet offices and agencies to promote their activities. They looked what people were searching for, and redesigned the site to create new, shorter paths to the most frequently searched-for answers. (Code for America built a site for the city of Honolulu, Honolulu Answers, which took much the same approach, adding a citizen “write-a-thon” to write new, user friendly content to answer the most asked questions.)

還有其他可以使用的資料，很多商業網站利用搜尋字串的分析來理解人們正在找什麼。英國的政府數位服務努力地使用這個技術來重新設計Gov.UK 網站，這個網站的設計是以使用者想要的內容而不是以內閣辦公室和各單位想要推行的活動為主。他們觀察人們在搜尋什麼，然後重新設計網站，替那些最常被搜尋的條目創造新的、更短的搜尋路徑。(Code for America 也幫Honolulu市建立一個問答網站，Honolulu Answers 也是用同樣方法，並加入一個公民的"write-a-thon"，對最常被問的問題撰寫新的、使用者友善的內容)

This is a simpler, manual intervention that copies what Google does algorithmically when it takes search query data into account when evaluating which results to publish. For example, Google looks at what they call “long clicks” versus “short clicks.” When the user clicks on a search result and doesn’t come back, or comes back significantly later, indicating that they found the destination link useful, that is a long click. Contrast that to a short click, when users come back right away and try another link instead. Get enough short clicks, and your search result gets demoted.

這是一個簡單地、人工介入的方式。這個方式複製Google利用演算法做的事，當Google在評估什麼樣的結果要被發佈時，它會把搜尋字串的資料拿來分析。比如說，Google會看所謂的"長點選"相對於"短點選"。當使用者點選一個搜尋結果，且沒有跳回或明顯經過一段很長時間才回到搜尋頁面，這個現象表示使用者找到一個好用的目標連結，這就是一個長點選。而相對地所謂的短點選是指當使用者點選進入一個結果後就立刻跳回並且試著找下一個連結取而代之。獲得夠多的短點選，你的搜尋結果就會demoted

There are many good examples of data collection, measurement, analysis, and decision-making taking hold in government. In New York City, data mining was used to identify correlations between illegal apartment conversions and increased risk of fires, leading to a unique cooperation between building and fire inspectors. In Louisville, KY, a department focused on performance analytics has transformed the culture of government to one of continuous process improvement.

很多不錯的例子像是資料收集、評量、分析和決策機制發生在政府部門裡。在紐約市，資料探勘被用來找出違法公寓住宅和逐漸增長的火災發生率間的關連性，這個觀察結果使的火災調查員和建物稽查員令人意外地共同合昨。在Louisville, KY,一個專門做效率分析的部門成功的改變政府部門的文化，使之變成一個會不斷改善流程的文化

It’s important to understand that these manual interventions are only an essential first step. Once you understand that you have actionable data being systematically collected, and that your interventions based on that data are effective, it’s time to begin automating those interventions.

很重要的是我們要去了解到，這些人工的介入都只是基本的第一步。一但你知道你可以動用有系統收集而來的資料且你的介入是建立在資料是有效的情況時，你就會想要把這些事情變成自動化。

There’s a long way to go. We’re just at the beginning of thinking about how measurement, outcomes, and regulation come together.

是還有很長的一段路要走，我們才正要開始思考如何把評量、法規、目的整合在一起。

### Risks of Algorithmic Regulation
### 演算型法規的風險

The use of algorithmic regulation increases the power of regulators, and in some cases, could lead to abuses, or to conditions that seem anathema to us in a free society. “Mission creep” is a real risk. Once data is collected for one purpose, it’s easy to imagine new uses for it. We’ve already seen this in requests to the NSA for data on American citizens originally collected for purposes of fighting overseas terrorism being requested by other agencies to fight domestic crime, including copyright infringement! (See Lichtblau & Schmidt, 2013.)

使用演算型法規可以加強執法人員的力量，而在某些情況下會導致濫用或者是導致一種在自由社會裡人人唾棄的情況。“任務偏離效應”是真的有可能發生的風險。一但資料被以某種目的收集，我們可以很簡單地想到還有其它使用目的。我們已經看到原本NSA收集用來對抗海外恐怖攻擊的資料被其他單位索求想拿來打擊國內犯罪甚至包含版權侵害！(Lichtblau & Schmidt 2013)

The answer to this risk is not to avoid collecting the data, but to put stringent safeguards in place to limit its use beyond the original purpose. As we have seen, oversight and transparency are particularly difficult to enforce when national security is at stake and secrecy can be claimed to hide misuse. But the NSA is not the only one that needs to keep its methods hidden. Many details of Google’s search algorithms are kept as a trade secret lest knowledge of how they work be used to game the system; the same is true for credit card fraud detection.

面對這個風險的解法不是不要收集資料，但是要安置有拘束力的警衛來限制這些資料沒有被用在超出其原本目的的地方上。如同我們已經看到得，當談到國家安全與宣稱機密來掩蓋其錯誤使用的事實時，透明化與監督的權力是特別難執行。但是不是只有NSA在掩蓋他們使用的方法，Google 搜尋引擎演算法的細節也都被當作商業機密因為害怕如何運作的內容被用來破解系統。銀行信用卡的違約偵測系統也是同樣的情況

One key difference is that a search engine such as Google is based on open data (the content of the web), allowing for competition. If Google fails to provide good search results, for example because they are favoring results that lead to more advertising dollars, they risk losing market share to Bing. Users are also able to evaluate Google’s search results for themselves.

一個關鍵的不同點是，像Google這類的搜尋引擎是利用網路上的公開資料來運作，這些資料是可以被拿來競爭用的。如果Google沒辦法提供好的搜尋結果，像是他們提供可以帶來更多'廣告收益的結果，他們會有失去市場佔有率給Bing的風險。而使用者也可以自行評估Google搜尋結果的好壞

Not only that, Google’s search quality team relies on users themselves—tens of thousands of individuals who are given searches to perform, and asked whether they found what they were looking for. Enough “no” answers, and Google adjusts the algorithms.

不只如此，Google的搜尋品質管理團隊也依賴使用者本身─給予幾萬個人搜尋結果，並且詢問是否有找到想要的。有足夠的“否定選項”，Google就會調整演算法。

Whenever possible, governments putting in place algorithmic regulations must put in place similar quality measurements, emphasizing not just compliance with the rules that have been codified so far but with the original, clearly-specified goal of the regulatory system. The data used to make determinations should be auditable, and whenever possible, open for public inspection.

無論何時才有可能，政府部門想考慮使用演算型法規必須要考慮要用相似的品質衡量標準，不只是專注在採納已經成文的法條，還有清楚標明法規規範系統原始的目標。被拿來做決策用的資料是可以被閱覽的，而且只要有可能，就要公開讓大眾檢閱。

There are also huge privacy risks involved in the collection of the data needed to build true algorithmic regulatory systems. Tracking our speed while driving also means tracking our location. But that location data need not be stored as long as we are driving within the speed limit, or it can be anonymized for use in traffic control systems.

在建構一個真正的演算型法規的規範系統時，收集這個系統需要的資料的過程還有很多關於隱私權的爭議與風險。追蹤我們開車時的速度代表也同時在追蹤我們的位置，但如果我們依照速線行駛，那這些資料無須被保存，或者是把這些資料匿名提供給交通控制系統

Given the amount of data being collected by the private sector, it is clear that our current notions of privacy are changing. What we need is a strenuous discussion of the tradeoffs between data collection and the benefits we receive from its use.

考慮到目前私人單位所收集的資料量，我們可以很明顯的發覺我們對於隱私權的看法正在改變。我們需要的是細緻周延的討論關於資料收集與我們從中得到的好處之間兩相權衡後的得失。

This is no different in a government context.

這和政府所面臨的(隱私權)問題脈絡一樣

### In Conclusion
### 結論

We are just at the beginning of a big data algorithmic revolution that will touch all elements of our society. Government needs to participate in this revolution.

我們才剛處於巨量資料演算法革命的開端，這場革命會觸及我們社會裡所有的組成。政府需要參予這場革命。

As outlined in the introduction, a successful algorithmic regulation system has the following characteristics:

1. A deep understanding of the desired outcome

2. Real-time measurement to determine if that outcome is being achieved

3. Algorithms (i.e. a set of rules) that make adjustments based on new data

4. Periodic, deeper analysis of whether the algorithms themselves are correct and performing as expected.

如同我們在前言時所舉列的，一個演算型法規規範系統應該要有底下幾點特質：

1. 對想要的目的有很清楚的認識
2. 有即時衡量的機制來決定是否有達到目的
3. 演算法(一系列規則)會根據新資料來調整
4. 週期性的深入分析是否演算法本身是正確的並且有照預期運作。

Open data plays a key role in both steps 2 and 4. Open data, either provided by the government itself, or required by government of the private sector, is a key enabler of the measurement revolution. Open data also helps us to understand whether we are achieving our desired objectives, and potentially allows for competition in better ways to achieve those objectives.

開放資料在第二點和第四點扮演關鍵的腳。開放資料，或許是由政府本身提供，或者是由政府向私人單位索取，是促成這場評量標準革命發生的關鍵角色。開放資料也可以幫助我們了解到，我們是否有達到我們想要的目的，並且有機會透過競爭來找到達到目的的更好方法。

### About the Author
### 關於作者

Tim O’Reilly is the founder and CEO of O’Reilly Media Inc., thought by many to be the best computer book publisher in the world. O’Reilly Media also hosts conferences on technology topics, including the O’Reilly Open Source Convention, Strata: The Business of Data, and many others. Tim’s blog, the O’Reilly Radar “watches the alpha geeks” to determine emerging technology trends, and serves as a platform for advocacy about issues of importance to the technical community. Tim is also a partner at O’Reilly AlphaTech Ventures, O’Reilly’s early stage venture firm, and is on the board of Safari Books Online, PeerJ, Code for America, and Maker Media, which was recently spun out from O’Reilly Media. Maker Media’s Maker Faire has been compared to the West Coast Computer Faire, which launched the personal computer revolution.

Tim O'Reilly 是歐萊禮媒體(O'Reilly Media)的創辦人與執行長，很多人認為這是當今最好的電腦書籍出版商。歐萊禮媒體同時也舉辦很多關於科技議題的研討會，包含了歐萊禮開放原始碼討論會(Convention)，Strata：關於資料商業和其他很多題目。Tim的部落格，the O'Reilly Radar，關注那些頂級技客的動向來決定新興的科技潮流，並且扮演一個對於技術社群重要議題的倡議平台。Tim也是O'Reilly AlphaTech Ventures，一間早期風險投資公司的合夥人，同時也是Safari Books Online、PeerJ、Code for America 和Maker Media的董事會成員。其中，Maker Media是一個剛從歐萊禮媒體分出來的公司，其旗下的Maker Faire 已經被和引發個人電腦革命的 Western Coast Computer Faire相提並論。

### References
### 參考資料

Lichtblau, E., & Schmidt, M.S. (2013, August 3). Other Agencies Clamor for Data N.S.A. Compiles. The New York Times. Retrieved from [http://www.nytimes.com/2013/08/04/us/other-agencies-clamor-for-data-nsa-compiles.html](http://www.nytimes.com/2013/08/04/us/other-agencies-clamor-for-data-nsa-compiles.html)
[Open Government Working Group. (2007, December 8). 8 Principles of Open Government Data. Retrieved from http://www.opengovdata.org/home/8principles](http://www.opengovdata.org/home/8principles)

The White House. (2012). As Prepared for Delivery: Regulation: Looking Backward, Looking Forward - Cass R. Sunstein. Retrieved from [http://www.whitehouse.gov/sites/default/files/omb/inforeg/speeches/regulation-looking-backward-looking-forward-05102012.pdf ](http://www.whitehouse.gov/sites/default/files/omb/inforeg/speeches/regulation-looking-backward-looking-forward-05102012.pdf )
