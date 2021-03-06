# 渾星圖

#### 目錄

[緣起](#header1)

[渾星圖的原理](#header2)

[天文小知識](#header3)

[農曆小知識](#header4)

[Android 版渾星圖操作說明](#header5)


<a name="header1"/>

## 緣起

即使不是天文發燒友，在亱空看見明亮的星時，總會想知道顆星是什麼名字。或者可以求助於星圖，有某種手錶也是配有星圖的。只要經過校準，就能辨認出星座和相關恒星。

- 圖1.1
 ![Image](https://github.com/kcfkwok2003/HunXingTu/blob/main/images/pic1.1.png?raw=true)

- 圖1.2
 ![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic1.2.png?raw=true)
 
 但如果所看見的是一顆行星，星圖上是不會找到的。因為星圖只能展示恒星。所謂恒星，它們在天空上彼此相對的位置是固定的，所以才能組成星座圖案。
 
 有一種軟件叫占星軟件，你不必對占星術有興趣，都可以使用它來計算出特定時間地點看見的行星位置。如果今晚約了朋友去觀星，除了要帶上星圖外，也不防用占星軟件計算一下晚上能看到那幾顆行星。

有一種天文現象叫「五星連珠」。2016年1月17日太陽出來之前會看到五大行星同時在天空出現。下面是一張網上找到的圖片，其下是占星軟件計算結果和對應日期時間的星圖。

- 圖1.3 2016年1月17日6時45分的天空 (每日頭條 ,2020)
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic1.3.jpg?raw=true)

- 圖1.4　星相圖
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic1.4.png?raw=true)

- 圖1.5　觀星圖
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic1.5.png?raw=true)

圖1.4中所使用的符號可參考圖1.2中的說明。這3張圖中，東方在左邊。比較圖1.3和圖1.4，可以看出行星位置是對應和一致的。太陽在地平線下並未升起，由東至西顺序是水星、金星、土星、火星和木星。火星在子午線位置。再比較圖1.3和圖1.5，在東南偏南方向能看見天蝎座，因些也是一致的。圖1.3和圖1.5的對應關係比較直觀。要看懂圖1.4便要花點心思了。


要看懂圖1.4也不困難，因為它只對應圖1.5中的那條黃色虛線。這條線稱為黃道，它是太陽在一年裏在天空走過的軌跡。行星和月亮大概也在這條軌跡上走動。而這條軌跡可以用所經過的星座來分區並命名。這一工作大概在四千年前已經做了並一直用到今天。這個稱為黃道12 宫的分區是以春分點為起點的，當時春分點在白羊座，所以第一宫叫白羊宫，跟著是金牛宫，如此類推。每宫均分天區佔30度。為了方便分別四季變化，人們調整曆法使每年太陽經過春分點都在3月21日前後。如果你的出生日在3月21日之後一個月內，人們會説你是白羊座的，專業一點的會說你的太陽星座是白羊座。

相對恒星背景，春分點實際每年都會向西移動一點點，72年移動1度。四千年便差不多移動了兩個星座。這就解釋了為什麼實際看到土星在天蝎座，而星相圖上的土星卻在人馬宫了。

為了避了混亂，這裡會嚴格使用星座和星宫兩個詞。星座指實際觀察到的星座，星宫指以春分點開始劃分的黃道分區。

由此可見，觀星圖和星相圖各有其好處，那能否合而為一更方便觀看呢。這便是本創作想要完成的工作。

<a name="header2"/>

## 渾星圖的原理

星相圖是可以計算得到的。觀星圖需說是靜態的，但實際上要知道經緯度和日期時間才可以計算出地平圏和可看見的天空。既然都是要計算的，那就要找有計算能力的器件了。為了方便攜帶，不能太大，也要有電池和省電，有時鐘功能，可以經互聯網同步時間。拜物聯網的興起，這類器件已經有很多選擇了。

另一個要考慮的是使用什麼顯示器，電子墨水屏是不錯的選擇。省電、不傷眼睛，但沒有彩色，更新速度慢。圖1.5a和圖1.5b所示的是4.2吋(400點x300點)和7.5吋(800點x480點)的電子墨水屏。

下面是星相圖和觀星圖混合後的效果，我把它稱為渾星圖。是顯示在7.5吋墨水屏上截取出來的。而渾星錶(圖1.5c)的解釋度較低(240點x240點)，也就進一步簡化了。

- 圖1.5a 渾星儀(4.2吋電子墨水屏)
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic1.5a.jpg?raw=true)

- 圖1.5b 渾星儀(7.5吋電子墨水屏)
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic1.5b.jpg?raw=true)

- 圖1.5c 渾星錶(LCD彩屏)
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic1.5c.jpg?raw=true)


- 圖1.6 渾星圖(電子墨水屏)
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic1.6.png?raw=true)

- 圖1.7渾星圖(TFT LCD)
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic1.7.png?raw=true)

在北半球，天上群星環繞北極星轉動，因此拿星圖時面向北方較自然。此時右邊是東方，所以圖1.4和圖1.6正好左右反轉。應該容易看出，圖1.6的外圍是星相圖部份，而內部則是觀星圖部份。為了精簡，觀星圖部份只顯示了黃道上的星座、仙后座和北斗七星。仙后和北斗都很易辨認，認出它們就能找到北極星，正北方向也就找到了。


下面是渾星圖的詳細解說。

- 圖1.8
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic1.8.png?raw=true)


（１）子午線:當地的子午線，當太陽在這線最上端時是中午12時，當太陽在這線最下端時是深亱0時。
（２）最外面第一組圓形：代表黃道星宮對應的月份，月份用羅馬數字表示。
（３）最外面第二組圓形：代表黃道星宮對應的符號。
（４）最外面第三組圓形：代表黃道星宮的三分刻度，每一刻度表示10度。
（５）這區域是太陽、月亮、和其他行星的位置和符號。
（６）地平圈：地平圈內是當地可以看見的天空，太陽在這圈內是日間，在圈外是晚上。我們知道日出日落不單和我們所處地方的經度有關，也和緯度有關。我們去旅遊時會有這樣的經驗，在夏季時，越往北的地方天黑越遲。如果緯度改變，地平圈的位置也會相應地改變。當到達北極時，地平圈只复蓋北半球的天空，看不到南半球的星星。這裏顯示的地平圈是用香港的緯度計算的。
（７）天赤道：實線圓形是天赤道。在此圓內是北半球的天空，在此圓外是南半球的天空。
（８）上升宮位指示線：中間較粗的橫線有箭頭的方向指向東方水平線正在上升的星宮。日間太陽會在這條線的上方，日落時太陽會走到這條線的下方去。
（９）黃道：偏離中心的虛線圓形是黃道，在黃道區域內的點和線構成的圖案表示黃道12星座。
由於行星基本上都是沿著黃度運行的，圖中的行星符號有連線指向外圍的星宮刻度和內圍黃道虛線上的位置。表示當時行星宮位和天空位置。

- 圖1.9星儀的赤道、黃道、地平圏和觀察者之間的關係在星儀上的表示
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic1.9.png?raw=true)

我們所用經緯度的地點進行天文計算時是用了香港的經緯度，即東經114.15 ，北緯22.15

<a name="header3"/>

## 天文小知識

如果對上述解釋還是不好理解的話，這裡補充一些天文小知識，或者有助對渾星圖的了解。

上文提到群星會環繞北極星轉動，這是因為地球自轉引致的視運動，恒星背景實際並無運動。地球自轉亦引致太陽的視運動。太陽的視運動不單涉及地球自轉，也涉及地球公轉。我們說地球自轉一圏是一日，但嚴格來說這叫做恒星日，如果以中午太陽位於子午線算起，地球自轉一圏後，還要轉多四分鐘，太陽才到逹明日的子午線，這才是我們慣常稱呼的「1日」，謂之太陽日。參閱下圖。

- 圖1.10
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic1.10.png?raw=true)


- 圖1.11

![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic1.11a.png?raw=true)

![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic1.11b.png?raw=true)

![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic1.11c.png?raw=true)

天文學知識對研究歷史考古亦很有幫助。我們可能以為除了太陽，月亮和行星外的其他恆星位置是不會改變的。但事實並非如此。由於人們對天文知識主要運用在預測季節的到來，從而安排農作物的播種和收成。而季節的形成是地軸和地球公轉軌道（黃道）形成角度。因而地球在公轉轉軌道（黃道）的不同位置太陽光直射在不同的緯度上，從而形成春夏秋冬的季節變化。(圖1.12a)

- 圖1.12a
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic1.12a.png?raw=true)

- 圖1.12b
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic1.12b.png?raw=true)

古人如何知道春天的到來呢？就是通過觀察每天太陽升起的位置。古人發現太陽出來之前看見的星星背景每天都在變化，古人把較明亮的星連上線條並想像成不同的事物，稱之為星座。伴著太陽升起的星座有12個。當所有這12個星座都伴隨過太陽升起後太陽又回到第一個星座的位置，這個周期就稱為一年。我們知道從新月到下一個新月的周期稱為一個月。我們就會發現一年大概有12個月，因此大概1個月就由1個星座負責帶領太陽升起。這12個星座被稱為黃道12星座。星座在天空的區域是有大有小的。如果把整個黃道等分為12份，則稱為黃道12宮，而每個星座都可以分配到一個宮，而對應的宮就用分配到的星座命名。（圖1.12b）

為什麼會有四季？太陽有半年時間是每天都移往較北的地方升起的，當太陽到了最北的位置的下一天便開始向南移動。這一天便是夏至日，天氣進入盛夏。太陽會在之後的半年裏每天向南方移一點直到冬至日到來，這時天氣步入嚴冬。之後又再掉頭往北移。在嚴寒的冬季人類會減少外出活動。古羅馬的凱撒大帝在征服高盧（現在的法國）的數年間這時候都會把軍旅安放在較近南方去渡過嚴寒的冬天，等待春天到來後再開展軍事行動，而這個可以開始軍事活動的月份就被稱為March(行軍)。

春天亦是很多農作物適合播種的季節，溫暖和濕潤的天氣很適合幼苗生長，而到夏天這些作物已茁壯成長，可以抵受嚴熱的天氣和猛烈的陽光。植物藉著光合作用提供的能量生產出滿足人類需要的糧食。到了秋天人們會把收成貯存起來用以渡過寒冬。

由此可見，如何準确預測春天的到來是和人類的生存和發展有莫大關係的。地軸傾斜約23.5度，當我們看到太陽從最北面的地方升起時，即夏至當日，太陽光是直射北緯23.5度，這個緯度線我們稱為北回歸線。而當太陽從最南端的地方升起時，即冬至當天，太陽光直射南回歸線。而位於這兩個緯度中間的是地球的最大的圓周，稱為赤度。(圖1.13a,b)當太陽從直射南半球移向北半球直射赤度的一刻稱為春分點，而當天就是春分日。

- 圖1.13a
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic1.13a.png?raw=true)

- 圖1.13b
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic1.13b.png?raw=true)

- 圖1.14
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic1.14.png?raw=true)

如果在地上觀察，在春分當天，太陽會從正東方升起。但如何得知那個方向是正東方，古人需要累積相當的天文知識和掌握足夠的測量技術才能準確指定這個方向。聽說某些巨石陣的用途就是用來觀察春分日升起的太陽。最古老和這方面有關的可能是埃及的獅身人面象。它就是面向正東方向，目的可能就是為了迎接春分日的到來。

春分點的義意非比尋常。星相學和天文學都以它作為最重要的參考點。表示春分點的符號和表示白羊星座的符號是一樣的。這意味著古人發現當時的春分點在白羊星座。因而在劃分12宮時就以白羊宮為起點，而這個規定一直沿用至今。但時移世易，物換星移。由於地軸不是恆久指向一個方向的，而是在繞圈晃動，但一直保持和黃道面的23. 5度交角。在力學上，這個現象稱為進動，進動周期約為26,000年。這個現象在中國稱為嵗差。(圖1.14)

嵗差現象會使春分點每72年向西移動1度，這個變化在人一生中可能很難觀察出來，但如果相距兩千年，那就是30度，春分點會從一個星座跑到另一個星座。如果從今天春分點的位置反推，春分點在白羊星座應是四千年前的事情，因此可以認為現在的星相學是建構於四千年前的，在二千年前，春分點進入了雙魚星座。而在今天開始的未來嵗月，春分點會跑進寶瓶星座。

有些星相學愛好者講出了很有趣的說法，以二千年間隔的嵗差現象去看人類歷史，白羊座時代可以引領猶太人出埃及的先知摩西為標誌，摩西被流放時曾經當過牧羊人。雙魚座時代則可以耶穌的出現為標誌，因為耶穌曾以五餅二魚幫人們渡過難關。而現在的寶瓶座時代，人們會擺脫宗教的束縛進入知識大爆發的年代。

<a name="header4"/>
         
## 農曆小知識

世界的曆法可以分為三類：陽曆（例如現時的公曆）、陰曆（例如伊斯蘭曆）和陰陽曆（例如中國農曆）。

陰曆是根據月球的運行周期制定的。當月球運行到太陽和地球之間，月球面向地球的一面完全沒有日照，看不到月球存在，稱為日月合朔(簡稱朔)，反之地球在太陽和月球之間而地球看到月球向著地球一面完全照亮時稱為望。為了和公曆的月份區分，這個從朔到朔的一個月周期稱為朔望月。一個朔望月有29.5306日。因此陰曆小月為29天，大月為30天。中國採用的農曆月份編號為:正月、二月、...九月、十月、冬月(十一月)、腊月(十二月)。

中國農曆除了包含朔望月外，也把太陽運行周期考慮進去。以冬至的後一天到下一個冬至日定為一年。把一年劃分為24份，規定了12個節氣和12個中氣。因此公曆的每個月都會分配到一個節氣和一個中氣。節氣在公曆日期中基本固定，上半年在6日和21日，下半年在8日和23日，前後不差1至2天。為了使農曆的月份也能反映季節的變化，就要使農曆的月份和節氣對齊。方法就是規定冬至是冬月(十一月)的中氣，大寒是腊月(十二月)的中氣，雨水是正月的中氣，春分是二月的中氣，如此類推。從冬至到冬至的一年中，如果有13個朔望月，那麼會有一個朔望月没有中气，這個朔望月便定為潤月，潤月按前一月份命名，例如前一月份為四月，潤月便稱為潤四月。

- 圖1.15
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic1.15.png?raw=true)

此外，中國還有使用干支記錄年月日時的習慣(在商代的甲骨文中已有記載干支紀日)。天干由10個字組成：甲乙丙丁戊己庚辛壬癸；地支由12個字組成：子丑寅卯辰巳午未申酉戌亥，地支也對應12種動物,稱為12生肖:鼠牛虎兔龙蛇马羊猴鸡狗猪

按天干地支編排的周期為60，按這種方式排列時間據說可以把更多的天體運行周期納入觀察規律之中。

以太陽、水星、金星、火星、木星、土星相對於地球觀察，其運動有1年、10年、5年、2年、12年和30年輪回准周期。當太陽經歷60年回到原點時，它們則各自周轉了246、96、30、5、2個周期回到了原點，可見太陽和五大行星周年視運動具有60年輪回准周期性。中國傳統上有天人相應的思想，所以認為人類社會也有相應的運程變化。

用干支排列年月日時可得到8個字，稱為八字。

用干支記錄月份時要注意它和朔望月是不對齊的，干支月是以節气來計算。以2019年冬至所在月份為例，冬至在公曆12月22日，由於規定了該朔望月是農曆冬月(十一月)，朔日在公曆11月26日，該日即為農曆冬月(十一月)初一。按干支月計算，冬至所在干支月稱為子月，子月是由大雪節气開始的，這年大雪在公曆12月7日，而農曆是冬月(十一月)十二日。

「子」是地支的第一位，那麽子月是不是一年的開始呢?

歷史上，周朝確是以子月(公曆12月)為一年的開始的(周正建子)，而商朝則是以丑月(公曆1月)為一年的開始的(殷正建丑)。而更早期的夏朝是以寅月(公暦2月)為一年的開始的。中國大部份的朝代以至今天的農曆都是跟隨夏曆的習慣，所以農曆正月在公暦2月， 地支是寅。

<a name="header5"/>

## Android 版渾星圖操作說明

[Google play 下載](https://play.google.com/store/apps/details?id=com.huawei.hunXingTu)


當所有屏幕設定關閉時的顯示:


- 圖2.1
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic2.1.png?raw=true)

菜單系統

- 圖2.2
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic2.2.png?raw=true)


赤道座標系和地平座標系選擇


- 圖2.3
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic2.3.png?raw=true)


顯示時分秒針

- 圖2.4
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic2.4.png?raw=true)


顯示赤道

- 圖2.5
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic2.5.png?raw=true)


顯示赤道、黃道、黃道星座連線和黃道星宫符號

- 圖2.6
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic2.6.png?raw=true)


顯示赤道、黃道、黃道星座連線和廿四節氣

- 圖2.7
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic2.7.png?raw=true)


顯示赤道、黃道、黃道星座連線和農曆月支

- 圖2.8
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic2.8.png?raw=true)

顯示地平坐標線

- 圖2.9
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic2.9.png?raw=true)

顯示星座連線、北極圏、南極圏

- 圖2.10
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic2.10.png?raw=true)

顯示行星符號、上升線和子午線


- 圖2.11
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic2.11.png?raw=true)


全部設定開關開啟下的赤道坐標系顯示

- 圖2.12
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic2.12.png?raw=true)

全部設定開關開啟下的地平坐標系顯示(可見天空部分)

- 圖2.13
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic2.13.png?raw=true)


全部設定開關開啟下的地平坐標系顯示(不可見天空部分)

- 圖2.14
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic2.14.png?raw=true)

星座圖鑑

- 圖2.15
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic2.15.png?raw=true)


設定自家插圖路徑及加入插圖

- 圖2.16
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic2.16.png?raw=true)


顯示自家插圖

- 圖2.17
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic2.17.png?raw=true)

物換星移，天路歷程模擬之旅


- 圖2.18a 進行模擬時鐘變動
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic2.18a.png?raw=true)

- 圖2.19a 模擬時鐘變動效果
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic2.19a.png?raw=true)


- 圖2.18b 進行模擬分鐘變動
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic2.18b.png?raw=true)

- 圖2.18c 進行模擬年份變動
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic2.18c.png?raw=true)

- 圖2.18d 進行模擬月份變動
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic2.18d.png?raw=true)

- 圖2.18e 進行模擬日期變動
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic2.18e.png?raw=true)

- 圖2.18f 進行模擬緯度變動
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic2.18f.png?raw=true)

- 圖2.19b 模擬緯度變動效果
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic2.19b.png?raw=true)


- 圖2.18g 進行模擬南北半球切換
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic2.18g.png?raw=true)

- 圖2.18h 進行模擬經度變動
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic2.18h.png?raw=true)

- 圖2.18i 進行模擬東西半球切換
![Image](https://github.com/kcfkwok2003/HunXingTu/raw/main/images/pic2.18i.png?raw=true)

