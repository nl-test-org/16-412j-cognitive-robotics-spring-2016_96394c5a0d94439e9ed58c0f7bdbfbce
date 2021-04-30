---
about_this_resource_text: ''
course_id: 16-412j-cognitive-robotics-spring-2016
embedded_media:
- id: Video-YouTube-Stream
  media_location: xmImNoDc9Z4
  parent_uid: 982375a3ba05137bf0a380fd51dce9ce
  title: Video-YouTube-Stream
  type: Video
  uid: c1399821704da3718503cd8bef337501
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/xmImNoDc9Z4/default.jpg
  parent_uid: 982375a3ba05137bf0a380fd51dce9ce
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 7c57770b9a7a81278a7ccdeae1a2d26b
- id: 3Play-3PlayYouTubeid-MP4
  media_location: xmImNoDc9Z4
  parent_uid: 982375a3ba05137bf0a380fd51dce9ce
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 176ee5af7805a53273411e78452fd738
- id: xmImNoDc9Z4.srt
  parent_uid: 982375a3ba05137bf0a380fd51dce9ce
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-412j-cognitive-robotics-spring-2016/videos-for-advanced-lectures/advanced-lecture-4-monte-carlo-tree-search/xmImNoDc9Z4.srt
  title: 3play caption file
  type: null
  uid: db05f1e7197839659e79d24655a1955f
- id: xmImNoDc9Z4.pdf
  parent_uid: 982375a3ba05137bf0a380fd51dce9ce
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-412j-cognitive-robotics-spring-2016/videos-for-advanced-lectures/advanced-lecture-4-monte-carlo-tree-search/xmImNoDc9Z4.pdf
  title: 3play pdf file
  type: null
  uid: e88f64ca8d5ee9a12e4613836abe7d2f
- id: Caption-3Play YouTube id-SRT
  parent_uid: 982375a3ba05137bf0a380fd51dce9ce
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 068f42c78ee0d9ae9fc3940b20ab908d
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 982375a3ba05137bf0a380fd51dce9ce
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 10620fdba9c4ca9f20b786987e1a0f4c
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT16.412S16/MIT16_412S16_Lec4_Monte_Carlo_Tree_300k.mp4
  parent_uid: 982375a3ba05137bf0a380fd51dce9ce
  title: Video-Internet Archive-MP4
  type: Video
  uid: 993af8ea7f35e3ba58d13c68e96223a7
inline_embed_id: 54778329advancedlecture4montecarlotreesearch78237409
layout: video
order_index: null
parent_uid: d55ba1f51999fdb2f0dba10fa56076dc
related_resources_text: ''
short_url: advanced-lecture-4-monte-carlo-tree-search
technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-412j-cognitive-robotics-spring-2016/videos-for-advanced-lectures/advanced-lecture-4-monte-carlo-tree-search
template_type: Tabbed
title: 'Advanced Lecture 4: Monte Carlo Tree Search'
transcript: <p><span m='1580'>The</span> <span m='1670'>following</span> <span m='2120'>content</span>
  <span m='2600'>is</span> <span m='2720'>provided</span> <span m='3170'>under</span>
  <span m='3410'>a</span> <span m='3470'>Creative</span> <span m='3920'>Commons</span>
  <span m='4310'>license.</span> <span m='5340'>Your</span> <span m='5420'>support</span>
  <span m='5900'>will</span> <span m='6050'>help</span> <span m='6320'>MIT</span>
  <span m='6800'>OpenCourseWare</span> <span m='7550'>continue</span> <span m='8029'>to</span>
  <span m='8180'>offer</span> <span m='8510'>high</span> <span m='8720'>quality</span>
  <span m='9200'>educational</span> <span m='9860'>resources</span> <span m='10430'>for</span>
  <span m='10580'>free.</span> <span m='11640'>To</span> <span m='11740'>make</span>
  <span m='11840'>a</span> <span m='11900'>donation</span> <span m='12650'>or</span>
  <span m='12830'>to</span> <span m='12950'>view</span> <span m='13160'>additional</span>
  <span m='13550'>materials</span> <span m='14180'>from</span> <span m='14360'>hundreds</span>
  <span m='14690'>of</span> <span m='14810'>MIT</span> <span m='15170'>courses,</span>
  <span m='16470'>visit</span> <span m='16670'>MIT</span> <span m='17180'>OpenCourseWare</span>
  <span m='18110'>at</span> <span m='18310'>ocw.mit.edu.</span> </p><p><span m='22420'>PROFESSOR
  WILLIAMS:</span> <span m='22540'>OK,</span> <span m='22660'>so</span> <span m='23160'>today's</span>
  <span m='23920'>lecture--</span> <span m='27010'>we're</span> <span m='27160'>going</span>
  <span m='27280'>to</span> <span m='27340'>be</span> <span m='27460'>talking</span>
  <span m='28000'>about</span> <span m='29170'>probabilistic</span> <span m='29650'>planning</span>
  <span m='30580'>later,</span> <span m='31380'>and</span> <span m='31870'>in</span>
  <span m='32070'>these</span> <span m='32240'>cases</span> <span m='32520'>where</span>
  <span m='32570'>you're</span> <span m='32995'>planning</span> <span m='33310'>a</span>
  <span m='33670'>large</span> <span m='34030'>state</span> <span m='34480'>spaces</span>
  <span m='35040'>is</span> <span m='35220'>very</span> <span m='35390'>difficult.</span>
  <span m='36570'>You</span> <span m='36987'>do</span> <span m='37404'>the</span>
  <span m='37821'>MVP</span> <span m='38240'>planning.</span> <span m='38740'>It</span>
  <span m='39240'>could</span> <span m='39340'>be</span> <span m='39700'>stress that</span>
  <span m='40100'>activity</span> <span m='40395'>planning,</span> <span m='40690'>or</span>
  <span m='41010'>the</span> <span m='41120'>likes.</span> <span m='41690'>But</span>
  <span m='41920'>you</span> <span m='42070'>have</span> <span m='42270'>to</span>
  <span m='42360'>be able</span> <span m='42560'>to</span> <span m='42870'>figure</span>
  <span m='43180'>out how</span> <span m='43320'>to deal</span> <span m='43700'>with</span>
  <span m='43860'>these state</span> <span m='44060'>spaces.</span> </p><p><span m='44950'>So</span>
  <span m='45230'>Monte</span> <span m='45510'>Carlo</span> <span m='46120'>tree</span>
  <span m='46340'>searches</span> <span m='47050'>is</span> <span m='47370'>one</span>
  <span m='47460'>of</span> <span m='47550'>the</span> <span m='47650'>techniques</span>
  <span m='48160'>that</span> <span m='48220'>people</span> <span m='48520'>can</span>
  <span m='48950'>identify,</span> <span m='49915'>over</span> <span m='50280'>last</span>
  <span m='50590'>five</span> <span m='50800'>years,</span> <span m='51040'>is</span>
  <span m='51160'>having</span> <span m='51600'>an</span> <span m='51730'>amazing</span>
  <span m='52870'>performance</span> <span m='53320'>improvement</span> <span m='53890'>over</span>
  <span m='54220'>other</span> <span m='54460'>kinds of</span> <span m='54875'>sample-based</span>
  <span m='55705'>approaches.</span> <span m='56120'>So</span> <span m='56375'>entity</span>
  <span m='56630'>is</span> <span m='56710'>very</span> <span m='57010'>interesting</span>
  <span m='57310'>from</span> <span m='57790'>that</span> <span m='58010'>standpoint.</span>
  <span m='58510'>And</span> <span m='58830'>then if</span> <span m='59300'>we</span>
  <span m='59770'>[? link it to ?]</span> <span m='60240'>the last</span> <span m='60470'>lecture,</span>
  <span m='60845'>then</span> <span m='61390'>the</span> <span m='61900'>combination</span>
  <span m='62530'>of</span> <span m='62590'>something,</span> <span m='62980'>we</span>
  <span m='63080'>just</span> <span m='63460'>learn</span> <span m='63760'>about</span>
  <span m='63970'>[INAUDIBLE]</span> <span m='64962'>and</span> <span m='65459'>combine</span>
  <span m='65870'>it</span> <span m='66370'>with</span> <span m='66870'>search,</span>
  <span m='67370'>is</span> <span m='67480'>very</span> <span m='67690'>powerful,</span>
  <span m='67960'>in</span> <span m='68230'>this</span> <span m='68670'>case,</span>
  <span m='68870'>through</span> <span m='69644'>the</span> <span m='70031'>state-of-the-art</span>
  <span m='71035'>techniques</span> <span m='71710'>for</span> <span m='71830'>that,</span>
  <span m='72000'>as much</span> <span m='72496'>as</span> <span m='72992'>tree</span>
  <span m='73488'>search</span> <span m='73984'>[INAUDIBLE]</span> <span m='74976'>later</span>
  <span m='75472'>[INAUDIBLE]</span> </p><p><span m='80940'>PROFESSOR 2:</span> <span
  m='80965'>Good</span> <span m='81240'>morning,</span> <span m='81540'>everyone.</span>
  <span m='82110'>As</span> <span m='83035'>Professor</span> <span m='83420'>Williams</span>
  <span m='83760'>just</span> <span m='84210'>said,</span> <span m='84360'>we are</span>
  <span m='84600'>going</span> <span m='84810'>to be</span> <span m='84910'>talking</span>
  <span m='85170'>about</span> <span m='85420'>Monte</span> <span m='85610'>Carlo</span>
  <span m='85915'>tree</span> <span m='86220'>search</span> <span m='86670'>today.</span>
  <span m='86910'>My</span> <span m='87355'>name</span> <span m='87800'>is</span>
  <span m='88245'>Eann</span> <span m='88690'>and</span> <span m='89056'>I'll</span>
  <span m='89422'>be</span> <span m='89790'>leading</span> <span m='90155'>the</span>
  <span m='90520'>introduction</span> <span m='90630'>and</span> <span m='91050'>motivation</span>
  <span m='91470'>of this</span> <span m='91890'>presentation.</span> <span m='92310'>By</span>
  <span m='92730'>the</span> <span m='92890'>end</span> <span m='93170'>of</span>
  <span m='93300'>this</span> <span m='93450'>presentation,</span> <span m='94320'>you</span>
  <span m='94420'>will</span> <span m='94460'>know</span> <span m='94750'>not</span>
  <span m='95055'>only</span> <span m='95360'>why</span> <span m='95810'>we</span>
  <span m='96050'>care</span> <span m='96530'>about</span> <span m='96670'>Monte</span>
  <span m='96780'>Carlo</span> <span m='97085'>tree searches.</span> <span m='97390'>As</span>
  <span m='97660'>Professor</span> <span m='98010'>Williams</span> <span m='98250'>said,</span>
  <span m='98490'>there's</span> <span m='98940'>so</span> <span m='99120'>many</span>
  <span m='99500'>algorithms</span> <span m='99930'>out</span> <span m='100260'>there.</span>
  <span m='100680'>Why</span> <span m='100870'>do</span> <span m='100920'>we</span>
  <span m='101070'>care</span> <span m='101550'>about</span> <span m='101850'>this</span>
  <span m='102060'>specific</span> <span m='102520'>one?</span> </p><p><span m='103440'>And</span>
  <span m='103560'>second,</span> <span m='104880'>we'll</span> <span m='105060'>be</span>
  <span m='105510'>going</span> <span m='105740'>through</span> <span m='105900'>the</span>
  <span m='105990'>pros</span> <span m='106260'>and</span> <span m='106350'>cons</span>
  <span m='106650'>of</span> <span m='106720'>MCTS,</span> <span m='107610'>as</span>
  <span m='107790'>well</span> <span m='107970'>as</span> <span m='108090'>the</span>
  <span m='108210'>algorithm</span> <span m='108660'>itself.</span> <span m='109620'>And</span>
  <span m='109740'>then</span> <span m='109920'>lastly,</span> <span m='110890'>we</span>
  <span m='110940'>will</span> <span m='111150'>have</span> <span m='111340'>a</span>
  <span m='111540'>pretty</span> <span m='111840'>cool</span> <span m='112140'>demo</span>
  <span m='112440'>on</span> <span m='112760'>how</span> <span m='113070'>it's</span>
  <span m='113260'>applied</span> <span m='113585'>to</span> <span m='113910'>Super</span>
  <span m='114260'>Mario</span> <span m='114560'>Brothers</span> <span m='114720'>and</span>
  <span m='115170'>the</span> <span m='115330'>latest</span> <span m='115650'>Alpha</span>
  <span m='116100'>Go</span> <span m='116590'>AI</span> <span m='117290'>that</span>
  <span m='117610'>built</span> <span m='118090'>the</span> <span m='118340'>second</span>
  <span m='118810'>best</span> <span m='120560'>leading</span> <span m='120955'>Go</span>
  <span m='121350'>player</span> <span m='121800'>in</span> <span m='122230'>the</span>
  <span m='122660'>world.</span> </p><p><span m='123520'>So</span> <span m='123950'>the</span>
  <span m='124140'>outline</span> <span m='124730'>for</span> <span m='124920'>today's</span>
  <span m='125320'>presentation</span> <span m='125820'>is,</span> <span m='125970'>first,</span>
  <span m='126300'>we're</span> <span m='126360'>going</span> <span m='126510'>to</span>
  <span m='126570'>talk</span> <span m='126900'>about</span> <span m='127255'>pre-MCTS</span>
  <span m='127920'>algorithms.</span> <span m='128220'>There</span> <span m='128570'>are</span>
  <span m='128920'>other</span> <span m='129270'>algorithms</span> <span m='129780'>that</span>
  <span m='129930'>currently</span> <span m='130320'>exist</span> <span m='130680'>out</span>
  <span m='130889'>there,</span> <span m='131130'>and</span> <span m='131270'>just</span>
  <span m='131490'>a</span> <span m='131580'>few</span> <span m='131800'>of</span>
  <span m='131910'>them</span> <span m='132435'>to</span> <span m='132690'>lead</span>
  <span m='132930'>into</span> <span m='133770'>why</span> <span m='133980'>we</span>
  <span m='134130'>do</span> <span m='134370'>care</span> <span m='134760'>about</span>
  <span m='134880'>MCTS</span> <span m='135600'>and</span> <span m='135770'>why</span>
  <span m='136100'>these</span> <span m='136380'>other</span> <span m='136620'>algorithms</span>
  <span m='137250'>fail.</span> <span m='138510'>And</span> <span m='138820'>second,</span>
  <span m='139060'>we'll</span> <span m='139400'>talk</span> <span m='139470'>about</span>
  <span m='139720'>Monte</span> <span m='139995'>Carlo</span> <span m='140270'>tree</span>
  <span m='140520'>searches</span> <span m='140850'>itself</span> <span m='141300'>with</span>
  <span m='141720'>Yo.</span> <span m='141890'>And</span> <span m='142110'>lastly,</span>
  <span m='142350'>Nick</span> <span m='142800'>will</span> <span m='143490'>tell</span>
  <span m='143670'>you</span> <span m='143790'>more</span> <span m='144000'>about</span>
  <span m='144150'>the</span> <span m='144270'>applications</span> <span m='145210'>of</span>
  <span m='145490'>Monte</span> <span m='145590'>Carlo</span> <span m='145890'>tree</span>
  <span m='146180'>searches.</span> </p><p><span m='147300'>So</span> <span m='147770'>the</span>
  <span m='147890'>motivation</span> <span m='150500'>of</span> <span m='150710'>these</span>
  <span m='150890'>kind</span> <span m='151100'>of</span> <span m='151190'>algorithms</span>
  <span m='151800'>is</span> <span m='151980'>we</span> <span m='152090'>want</span>
  <span m='152210'>to</span> <span m='152270'>be</span> <span m='152420'>able</span>
  <span m='152570'>to</span> <span m='152690'>play</span> <span m='152960'>games</span>
  <span m='153440'>and</span> <span m='153550'>we</span> <span m='153960'>want</span>
  <span m='154170'>to</span> <span m='154300'>be able</span> <span m='154680'>to</span>
  <span m='154960'>create</span> <span m='155160'>programs</span> <span m='155360'>to</span>
  <span m='155645'>play</span> <span m='155930'>these</span> <span m='156380'>games,</span>
  <span m='157030'>but</span> <span m='157330'>we</span> <span m='157420'>want</span>
  <span m='157580'>to</span> <span m='157650'>play</span> <span m='157830'>them</span>
  <span m='158280'>optimally.</span> <span m='158430'>We</span> <span m='158773'>want
  to</span> <span m='159116'>be able</span> <span m='159460'>to</span> <span m='159900'>win,</span>
  <span m='160310'>but</span> <span m='160430'>we</span> <span m='160580'>also</span>
  <span m='160880'>want</span> <span m='161060'>to be</span> <span m='161180'>able</span>
  <span m='161540'>do</span> <span m='161750'>this</span> <span m='162080'>in</span>
  <span m='162170'>a</span> <span m='162230'>reasonable</span> <span m='162710'>amount</span>
  <span m='162920'>of</span> <span m='162980'>time.</span> <span m='163890'>So</span>
  <span m='163940'>these</span> <span m='164180'>three</span> <span m='164390'>can
  train</span> <span m='164950'>itself</span> <span m='165690'>leads</span> <span
  m='165965'>to</span> <span m='166240'>different</span> <span m='166490'>kinds</span>
  <span m='166800'>of</span> <span m='167240'>algorithms,</span> <span m='167680'>and</span>
  <span m='167870'>different</span> <span m='168290'>algorithms</span> <span m='168790'>with</span>
  <span m='169310'>different</span> <span m='169580'>complexities</span> <span m='170600'>and</span>
  <span m='170720'>time,</span> <span m='172040'>or</span> <span m='172220'>times</span>
  <span m='172640'>to</span> <span m='172790'>search.</span> <span m='173420'>And</span>
  <span m='173540'>so</span> <span m='173690'>that's</span> <span m='173960'>why</span>
  <span m='174200'>today</span> <span m='174510'>we're</span> <span m='174800'>going
  to</span> <span m='175250'>be</span> <span m='175550'>talking</span> <span m='175850'>about</span>
  <span m='176090'>Monte</span> <span m='176370'>Carlo</span> <span m='176540'>tree</span>
  <span m='176710'>searches.</span> <span m='177140'>And you'll</span> <span m='177465'>figure</span>
  <span m='177790'>out</span> <span m='177910'>in</span> <span m='178165'>a</span>
  <span m='178420'>few</span> <span m='178580'>slides</span> <span m='179120'>why</span>
  <span m='179570'>we</span> <span m='179750'>do</span> <span m='180182'>care.</span>
  </p><p><span m='180614'>So</span> <span m='181046'>these</span> <span m='181478'>are
  the</span> <span m='181910'>types of</span> <span m='182342'>games</span> <span
  m='182780'>we have.</span> <span m='182900'>You have</span> <span m='183130'>this</span>
  <span m='183260'>chart</span> <span m='183640'>where</span> <span m='183970'>there's</span>
  <span m='184300'>fully</span> <span m='185520'>observable</span> <span m='185980'>games,</span>
  <span m='186250'>partially</span> <span m='186810'>observable</span> <span m='187125'>games,</span>
  <span m='187940'>determinstic,</span> <span m='188640'>and</span> <span m='188870'>games</span>
  <span m='189125'>of</span> <span m='189380'>chance.</span> <span m='190450'>And</span>
  <span m='190620'>so</span> <span m='190880'>today,</span> <span m='191580'>the</span>
  <span m='192030'>games</span> <span m='192230'>that</span> <span m='192360'>we</span>
  <span m='192530'>care</span> <span m='192740'>about</span> <span m='193240'>are</span>
  <span m='193460'>the</span> <span m='193540'>games</span> <span m='194450'>that</span>
  <span m='194600'>are</span> <span m='194780'>fully</span> <span m='195080'>observable</span>
  <span m='195405'>and</span> <span m='195730'>deterministic.</span> <span m='196790'>And</span>
  <span m='196890'>these</span> <span m='197150'>games</span> <span m='197480'>are</span>
  <span m='197600'>games</span> <span m='198440'>like</span> <span m='198590'>chess</span>
  <span m='199460'>and</span> <span m='199580'>checkers</span> <span m='200580'>and</span>
  <span m='200750'>Go.</span> <span m='201470'>And</span> <span m='201590'>we'll</span>
  <span m='201910'>also</span> <span m='202060'>be</span> <span m='202450'>talking</span>
  <span m='202840'>about</span> <span m='202960'>another</span> <span m='203430'>example</span>
  <span m='203580'>with</span> <span m='203880'>Tic-tac-toe.</span> </p><p><span m='205730'>So</span>
  <span m='205860'>these</span> <span m='206060'>pre-MCTS</span> <span m='206760'>algorithms</span>
  <span m='207580'>include</span> <span m='209280'>deterministic,</span> <span m='209990'>fully</span>
  <span m='210270'>observable</span> <span m='210520'>games,</span> <span m='211140'>like</span>
  <span m='211520'>we</span> <span m='211805'>said</span> <span m='212090'>earlier.</span>
  <span m='212660'>And</span> <span m='212900'>the</span> <span m='213080'>idea</span>
  <span m='213630'>of</span> <span m='213730'>this,</span> <span m='214010'>and</span>
  <span m='214190'>the</span> <span m='215150'>nice</span> <span m='215390'>thing</span>
  <span m='215630'>about</span> <span m='215930'>these</span> <span m='216110'>games,</span>
  <span m='216510'>is</span> <span m='216640'>that</span> <span m='216940'>they</span>
  <span m='217100'>have</span> <span m='217420'>perfect</span> <span m='217850'>information,</span>
  <span m='218760'>and</span> <span m='218890'>that</span> <span m='219160'>you</span>
  <span m='219500'>have</span> <span m='219770'>all</span> <span m='219890'>of</span>
  <span m='220240'>the</span> <span m='220680'>states</span> <span m='221180'>that</span>
  <span m='221680'>you</span> <span m='222180'>need</span> <span m='222680'>and</span>
  <span m='222920'>there's</span> <span m='223250'>no</span> <span m='223820'>opportunity</span>
  <span m='224570'>for</span> <span m='224720'>chance.</span> <span m='225650'>And</span>
  <span m='225740'>so</span> <span m='225890'>the</span> <span m='226140'>idea</span>
  <span m='226340'>is</span> <span m='226590'>that</span> <span m='226890'>we</span>
  <span m='227190'>can</span> <span m='227390'>construct a</span> <span m='227840'>tree
  that</span> <span m='228020'>contains</span> <span m='228620'>all</span> <span m='228830'>possible</span>
  <span m='229400'>outcomes</span> <span m='230240'>because</span> <span m='230480'>everything</span>
  <span m='230900'>is</span> <span m='231050'>fully</span> <span m='231320'>determined.</span>
  </p><p><span m='232990'>And</span> <span m='233150'>so</span> <span m='233330'>one</span>
  <span m='233580'>of</span> <span m='233820'>these</span> <span m='234040'>algorithms,</span>
  <span m='234330'>to</span> <span m='234450'>address</span> <span m='234860'>this,</span>
  <span m='235250'>is</span> <span m='235500'>the</span> <span m='235700'>algorithm</span>
  <span m='236140'>Minimax,</span> <span m='236813'>which</span> <span m='237156'>you</span>
  <span m='237500'>might</span> <span m='237850'>have</span> <span m='238210'>heard</span>
  <span m='238585'>before.</span> <span m='238960'>And the</span> <span m='239140'>idea</span>
  <span m='239440'>of</span> <span m='239780'>Minimax</span> <span m='240000'>to</span>
  <span m='240400'>minimize the</span> <span m='240800'>maximum</span> <span m='241340'>possible</span>
  <span m='241830'>loss.</span> <span m='242500'>That</span> <span m='242790'>sounds</span>
  <span m='243120'>a</span> <span m='243240'>little</span> <span m='243400'>weird</span>
  <span m='243610'>in the</span> <span m='243740'>beginning,</span> <span m='244150'>but</span>
  <span m='244240'>if</span> <span m='244430'>you</span> <span m='244510'>take</span>
  <span m='244820'>a</span> <span m='245150'>look</span> <span m='245520'>at</span>
  <span m='245960'>this</span> <span m='246270'>tree,</span> <span m='246540'>this
  red</span> <span m='246770'>dot,</span> <span m='246960'>for example,</span> <span
  m='247210'>is</span> <span m='247400'>the</span> <span m='247490'>computer.</span>
  <span m='248440'>And</span> <span m='248600'>so</span> <span m='248760'>in</span>
  <span m='248980'>the</span> <span m='249350'>computer's</span> <span m='249620'>eyes,</span>
  <span m='249890'>it wants</span> <span m='250340'>to</span> <span m='250670'>beat</span>
  <span m='251240'>its</span> <span m='251550'>opponent.</span> <span m='251730'>And</span>
  <span m='252090'>we're</span> <span m='252450'>assuming</span> <span m='252670'>the</span>
  <span m='253020'>opponent</span> <span m='253520'>wants</span> <span m='253780'>to</span>
  <span m='254040'>win</span> <span m='254330'>also,</span> <span m='254570'>so</span>
  <span m='254810'>they're</span> <span m='254990'>playing</span> <span m='255290'>their</span>
  <span m='255470'>best</span> <span m='255740'>game</span> <span m='256010'>as</span>
  <span m='256160'>well.</span> </p><p><span m='256815'>And</span> <span m='257260'>so</span>
  <span m='257480'>the</span> <span m='257620'>computer</span> <span m='257970'>wants</span>
  <span m='258244'>to</span> <span m='258519'>maximize</span> <span m='259430'>his</span>
  <span m='260060'>or</span> <span m='260269'>her</span> <span m='261050'>points,</span>
  <span m='261990'>but</span> <span m='262940'>also</span> <span m='263300'>knowing</span>
  <span m='263660'>that</span> <span m='263910'>the</span> <span m='264290'>opponent,</span>
  <span m='264670'>or</span> <span m='264970'>the</span> <span m='265230'>human,</span>
  <span m='265820'>wants</span> <span m='266270'>to</span> <span m='267140'>maximize</span>
  <span m='267770'>their</span> <span m='268040'>own</span> <span m='268670'>win</span>
  <span m='268880'>as</span> <span m='269375'>well.</span> <span m='269870'>And</span>
  <span m='269970'>so</span> <span m='270210'>in</span> <span m='270390'>the</span>
  <span m='270650'>computer's</span> <span m='271010'>eyes,</span> <span m='271250'>it</span>
  <span m='271730'>wants</span> <span m='272180'>to</span> <span m='272270'>minimize</span>
  <span m='272690'>the</span> <span m='272840'>maximum</span> <span m='273230'>possible</span>
  <span m='273490'>lost.</span> <span m='274000'>Does</span> <span m='274270'>that</span>
  <span m='274545'>make</span> <span m='274820'>sense</span> <span m='275090'>to</span>
  <span m='275577'>everyone?</span> <span m='277038'>Yes?</span> <span m='278012'>OK.</span>
  <span m='279480'>And</span> <span m='279600'>so</span> <span m='279750'>in</span>
  <span m='280010'>the</span> <span m='280270'>example</span> <span m='280700'>of</span>
  <span m='280920'>Minimax,</span> <span m='281430'>we're</span> <span m='281530'>going
  to</span> <span m='281570'>start</span> <span m='281860'>with</span> <span m='282200'>a</span>
  <span m='282500'>connect,</span> <span m='282810'>or</span> <span m='283050'>a</span>
  <span m='283250'>Tic-tac-toe</span> <span m='283950'>board,</span> <span m='284140'>where</span>
  <span m='284280'>the</span> <span m='284470'>computer</span> <span m='285210'>is</span>
  <span m='285450'>this</span> <span m='285630'>board</span> <span m='285920'>right</span>
  <span m='286230'>here,</span> <span m='287600'>and</span> <span m='287770'>the</span>
  <span m='287850'>blue</span> <span m='288270'>Tic-tac-toe</span> <span m='288870'>boards</span>
  <span m='289230'>are</span> <span m='289390'>the</span> <span m='290026'>states</span>
  <span m='290502'>that</span> <span m='290980'>the</span> <span m='291320'>computer</span>
  <span m='291390'>finally</span> <span m='291813'>chooses.</span> <span m='292236'>It's</span>
  <span m='292660'>anticipating</span> <span m='293490'>the</span> <span m='293990'>moves</span>
  <span m='294160'>a human</span> <span m='294570'>could</span> <span m='294810'>play.</span>
  </p><p><span m='297880'>So if</span> <span m='298365'>you take</span> <span m='298850'>a
  look</span> <span m='299120'>up</span> <span m='299280'>here,</span> <span m='299660'>here's</span>
  <span m='299820'>the</span> <span m='299940'>current</span> <span m='300305'>state</span>
  <span m='300670'>of</span> <span m='300890'>the</span> <span m='300960'>board.</span>
  <span m='302292'>The</span> <span m='302780'>current</span> <span m='303200'>state
  of</span> <span m='303310'>the</span> <span m='303440'>board.</span> <span m='303700'>And
  the</span> <span m='303890'>possible</span> <span m='304150'>options</span> <span
  m='304530'>for</span> <span m='305000'>the</span> <span m='305120'>human</span>
  <span m='305640'>are</span> <span m='305760'>this</span> <span m='306090'>guy,</span>
  <span m='306970'>this</span> <span m='307430'>guy.</span> <span m='309730'>Nope.</span>
  <span m='309880'>Possible</span> <span m='310195'>options</span> <span m='310510'>for</span>
  <span m='310660'>the</span> <span m='311110'>computer,</span> <span m='311820'>we</span>
  <span m='311950'>have</span> <span m='312310'>three</span> <span m='312480'>different</span>
  <span m='312750'>options.</span> <span m='313540'>And</span> <span m='313660'>so</span>
  <span m='313820'>you'll</span> <span m='314185'>notice</span> <span m='314550'>that</span>
  <span m='314730'>this is</span> <span m='314920'>clearly</span> <span m='315280'>the</span>
  <span m='315390'>obvious</span> <span m='315810'>winner.</span> <span m='316200'>But</span>
  <span m='316550'>in</span> <span m='316770'>the</span> <span m='317065'>state</span>
  <span m='317360'>of</span> <span m='317660'>Minimax,</span> <span m='317790'>it</span>
  <span m='318070'>goes</span> <span m='318180'>through the</span> <span m='318300'>entire</span>
  <span m='318750'>tree,</span> <span m='319410'>which</span> <span m='319590'>is</span>
  <span m='319710'>different</span> <span m='320090'>from</span> <span m='320470'>depth-first</span>
  <span m='320790'>search.</span> <span m='321270'>It</span> <span m='321645'>goes</span>
  <span m='322020'>through the</span> <span m='322170'>entire</span> <span m='322540'>tree</span>
  <span m='322950'>until</span> <span m='323240'>it</span> <span m='323420'>finds</span>
  <span m='324090'>the</span> <span m='324220'>winning</span> <span m='324520'>move</span>
  <span m='324900'>and</span> <span m='325190'>the</span> <span m='326310'>minimize</span>
  <span m='326650'>of</span> <span m='327480'>the</span> <span m='327600'>maximum</span>
  <span m='328140'>possible</span> <span m='330220'>points</span> <span m='330460'>it</span>
  <span m='330906'>could</span> <span m='331352'>win.</span> </p><p><span m='331800'>So</span>
  <span m='332160'>is</span> <span m='332440'>there a</span> <span m='332800'>way
  we</span> <span m='332920'>can</span> <span m='333240'>make</span> <span m='333430'>this</span>
  <span m='333755'>better?</span> <span m='334080'>Yes.</span> <span m='334620'>I'm</span>
  <span m='334740'>sure</span> <span m='335550'>you've</span> <span m='335710'>heard</span>
  <span m='335920'>about</span> <span m='336130'>pruning,</span> <span m='336720'>where,</span>
  <span m='338260'>in</span> <span m='338290'>our</span> <span m='338390'>human</span>
  <span m='338700'>intuition,</span> <span m='339050'>it</span> <span m='339400'>makes</span>
  <span m='339570'>sense.</span> <span m='339900'>Well,</span> <span m='340020'>why</span>
  <span m='340140'>don't</span> <span m='340320'>we</span> <span m='340380'>just</span>
  <span m='340590'>stop</span> <span m='340890'>when</span> <span m='341010'>we</span>
  <span m='341130'>win,</span> <span m='341790'>or</span> <span m='341880'>when</span>
  <span m='342000'>we</span> <span m='342120'>know</span> <span m='342420'>we're</span>
  <span m='342570'>going</span> <span m='342840'>to</span> <span m='343770'>have</span>
  <span m='343940'>a</span> <span m='344000'>game</span> <span m='344300'>that</span>
  <span m='345755'>allows</span> <span m='346240'>us</span> <span m='346520'>to</span>
  <span m='346730'>win?</span> <span m='347116'>And</span> <span m='347502'>so</span>
  <span m='347890'>this</span> <span m='348140'>idea</span> <span m='348290'>is the</span>
  <span m='348650'>idea of</span> <span m='349070'>simple</span> <span m='349340'>pruning.</span>
  <span m='349940'>And</span> <span m='350060'>so</span> <span m='350210'>when</span>
  <span m='350370'>we</span> <span m='350480'>combine</span> <span m='351020'>Minimax</span>
  <span m='351695'>and</span> <span m='352000'>simple</span> <span m='352520'>pruning,</span>
  <span m='353255'>we</span> <span m='353540'>have--</span> <span m='354270'>anyone</span>
  <span m='354400'>know?</span> </p><p><span m='357612'>AUDIENCE:</span> <span m='357850'>Alpha,</span>
  <span m='358089'>beta.</span> </p><p><span m='358570'>PROFESSOR 3:</span> <span
  m='358775'>Yes.</span> <span m='358980'>Our</span> <span m='359390'>6.034</span>
  <span m='360090'>head TA knows about this.</span> <span m='362915'>We</span> <span
  m='363372'>have</span> <span m='363830'>alpha-beta</span> <span m='364130'>pruning,</span>
  <span m='364410'>where</span> <span m='364695'>we</span> <span m='364980'>prune</span>
  <span m='365180'>away</span> <span m='365380'>any</span> <span m='365800'>branches</span>
  <span m='366075'>that</span> <span m='366640'>cannot</span> <span m='366880'>influence</span>
  <span m='367330'>the</span> <span m='367640'>final</span> <span m='368123'>decision.</span>
  <span m='369090'>So</span> <span m='370110'>in</span> <span m='370230'>other</span>
  <span m='370380'>words,</span> <span m='370620'>you</span> <span m='370950'>wouldn't</span>
  <span m='371000'>keep</span> <span m='371420'>exploring</span> <span m='372070'>the</span>
  <span m='372250'>tree</span> <span m='373100'>if</span> <span m='373350'>you</span>
  <span m='373520'>already</span> <span m='373840'>knew</span> <span m='374290'>that</span>
  <span m='374540'>a</span> <span m='374840'>previous</span> <span m='375090'>term</span>
  <span m='375340'>would</span> <span m='375595'>allow</span> <span m='375850'>you</span>
  <span m='375990'>to</span> <span m='376270'>win.</span> <span m='376890'>And</span>
  <span m='377080'>so</span> <span m='377580'>this</span> <span m='377790'>idea</span>
  <span m='378250'>in</span> <span m='378570'>alpha-beta</span> <span m='378830'>pruning,</span>
  <span m='379630'>we</span> <span m='379860'>have</span> <span m='380100'>an</span>
  <span m='380200'>alpha</span> <span m='380640'>and</span> <span m='380730'>a</span>
  <span m='380900'>beta.</span> <span m='381150'>And</span> <span m='381270'>so</span>
  <span m='382260'>the</span> <span m='382350'>details</span> <span m='384210'>aren't</span>
  <span m='384560'>important</span> <span m='384740'>for you</span> <span m='384860'>to</span>
  <span m='384990'>know</span> <span m='385170'>right</span> <span m='385320'>now,</span>
  <span m='386015'>but</span> <span m='386320'>the</span> <span m='386530'>idea</span>
  <span m='386850'>is</span> <span m='387000'>that</span> <span m='387400'>we</span>
  <span m='387750'>stop</span> <span m='388110'>whenever</span> <span m='388320'>we</span>
  <span m='388710'>know</span> <span m='389250'>we</span> <span m='389370'>don't</span>
  <span m='389490'>need</span> <span m='389640'>to</span> <span m='389760'>go</span>
  <span m='390030'>on</span> <span m='390210'>any</span> <span m='390640'>further.</span>
  </p><p><span m='391930'>So</span> <span m='392210'>in the</span> <span m='392470'>games</span>
  <span m='392950'>that</span> <span m='393180'>have</span> <span m='393420'>Tic-tac-toe</span>
  <span m='394434'>and</span> <span m='394821'>Connect</span> <span m='395210'>4</span>
  <span m='395550'>and</span> <span m='396030'>chess,</span> <span m='396150'>we have</span>
  <span m='396360'>relatively</span> <span m='397170'>low</span> <span m='397380'>branching</span>
  <span m='397730'>factor.</span> <span m='398800'>So</span> <span m='399060'>in</span>
  <span m='399220'>the</span> <span m='399350'>case</span> <span m='399660'>of</span>
  <span m='399750'>Tic-tac-toe,</span> <span m='400500'>we</span> <span m='400590'>have</span>
  <span m='400800'>2</span> <span m='401130'>to</span> <span m='401460'>the</span>
  <span m='401580'>fourth</span> <span m='401670'>branching</span> <span m='401970'>factor.</span>
  <span m='403720'>But</span> <span m='403730'>what</span> <span m='403920'>if</span>
  <span m='404070'>we</span> <span m='404220'>have</span> <span m='404640'>really</span>
  <span m='404940'>large</span> <span m='405245'>branching</span> <span m='405550'>factors,</span>
  <span m='406230'>like</span> <span m='406600'>Alpha</span> <span m='406810'>Go?</span>
  <span m='407640'>In</span> <span m='407780'>Alpha</span> <span m='408090'>Go,</span>
  <span m='408360'>we</span> <span m='408540'>have</span> <span m='408900'>2</span>
  <span m='409320'>to</span> <span m='409590'>the</span> <span m='409820'>250.</span>
  <span m='410440'>Do</span> <span m='410590'>you</span> <span m='410810'>see</span>
  <span m='411210'>that</span> <span m='411480'>Mini</span> <span m='411750'>Max,</span>
  <span m='412080'>or</span> <span m='412330'>even</span> <span m='412625'>alpha-beta</span>
  <span m='413100'>pruning,</span> <span m='413760'>would</span> <span m='413910'>be</span>
  <span m='415140'>an</span> <span m='415470'>optimal</span> <span m='415920'>algorithm</span>
  <span m='416326'>for</span> <span m='416732'>this?</span> <span m='417140'>The</span>
  <span m='417400'>answer</span> <span m='417862'>is?</span> </p><p><span m='419248'>AUDIENCE:</span>
  <span m='419479'>No.</span> </p><p><span m='419710'>PROFESSOR 3:</span> <span m='419941'>No.</span>
  <span m='420172'>And</span> <span m='420640'>this</span> <span m='420730'>leads</span>
  <span m='420950'>us</span> <span m='421130'>to</span> <span m='421430'>out</span>
  <span m='423160'>next</span> <span m='423430'>section.</span> <span m='424370'>Our
  goal is</span> <span m='424420'>going</span> <span m='424810'>to</span> <span m='424870'>talk</span>
  <span m='425140'>about</span> <span m='425770'>how</span> <span m='425950'>we</span>
  <span m='426100'>can</span> <span m='427180'>use</span> <span m='427540'>the</span>
  <span m='427680'>Monte</span> <span m='427950'>Carlo</span> <span m='428210'>tree</span>
  <span m='428470'>search</span> <span m='429050'>algorithm</span> <span m='429810'>for</span>
  <span m='429990'>games</span> <span m='430280'>with</span> <span m='430430'>really</span>
  <span m='430750'>high</span> <span m='431210'>branching</span> <span m='431690'>factors,</span>
  <span m='431920'>and</span> <span m='432060'>using</span> <span m='432460'>the</span>
  <span m='433900'>random</span> <span m='434380'>extension</span> <span m='435360'>to</span>
  <span m='435550'>allow</span> <span m='435850'>us</span> <span m='436120'>to</span>
  <span m='436360'>see,</span> <span m='436750'>ultimately,</span> <span m='437380'>how</span>
  <span m='438610'>Alpha</span> <span m='438910'>Go,</span> <span m='439390'>which</span>
  <span m='439630'>is</span> <span m='439900'>Google's</span> <span m='440315'>AI,</span>
  <span m='441490'>was</span> <span m='441760'>able</span> <span m='442030'>to</span>
  <span m='442120'>beat</span> <span m='443160'>the</span> <span m='443470'>leading</span>
  <span m='443910'>Go</span> <span m='444190'>player</span> <span m='444430'>in</span>
  <span m='444901'>the</span> <span m='445372'>world.</span> </p><p><span m='449140'>PROFESSOR
  3:</span> <span m='449375'>All</span> <span m='449611'>right,</span> <span m='450082'>guys.</span>
  <span m='451024'>So</span> <span m='452530'>this</span> <span m='452620'>is</span>
  <span m='452680'>the</span> <span m='452800'>part</span> <span m='453010'>where</span>
  <span m='453160'>we</span> <span m='453520'>re-explain</span> <span m='454000'>the</span>
  <span m='454070'>algorithm</span> <span m='454440'>itself.</span> <span m='455410'>And</span>
  <span m='455720'>before</span> <span m='455830'>we</span> <span m='456140'>dive</span>
  <span m='456330'>into</span> <span m='456610'>this,</span> <span m='456930'>I</span>
  <span m='457170'>want to</span> <span m='457310'>make</span> <span m='457600'>something</span>
  <span m='457900'>really</span> <span m='458230'>clear,</span> <span m='458810'>which</span>
  <span m='458860'>is</span> <span m='459070'>that</span> <span m='460060'>because</span>
  <span m='460480'>these</span> <span m='460660'>are</span> <span m='460720'>technical</span>
  <span m='461080'>details</span> <span m='461470'>and</span> <span m='461560'>because</span>
  <span m='461770'>we</span> <span m='461950'>actually</span> <span m='462340'>want
  you to</span> <span m='462640'>understand</span> <span m='463120'>them,</span> <span
  m='463700'>and</span> <span m='463810'>because</span> <span m='464180'>I definitely</span>
  <span m='464350'>didn't</span> <span m='464560'>understand</span> <span m='465010'>this
  the</span> <span m='465070'>first</span> <span m='465520'>three</span> <span m='465760'>times</span>
  <span m='466180'>I</span> <span m='466350'>read the paper.</span> <span m='466920'>I</span>
  <span m='467230'>really</span> <span m='467590'>want you</span> <span m='467880'>to</span>
  <span m='467950'>feel</span> <span m='468160'>free</span> <span m='468310'>to</span>
  <span m='468370'>ask</span> <span m='468800'>any</span> <span m='469060'>questions</span>
  <span m='469420'>on</span> <span m='469540'>your</span> <span m='469610'>mind,</span>
  <span m='470380'>with</span> <span m='470560'>the</span> <span m='470650'>knowledge</span>
  <span m='471250'>that,</span> <span m='472750'>in</span> <span m='472900'>my</span>
  <span m='473050'>experience,</span> <span m='473590'>it</span> <span m='473640'>is</span>
  <span m='473770'>very</span> <span m='474040'>rare</span> <span m='474350'>that</span>
  <span m='474650'>someone</span> <span m='475060'>asks</span> <span m='475230'>a</span>
  <span m='475540'>question in</span> <span m='475850'>class</span> <span m='476080'>that's</span>
  <span m='476492'>[INAUDIBLE]</span> <span m='477728'>OK,</span> <span m='478140'>so</span>
  <span m='478380'>really,</span> <span m='478930'>whenever</span> <span m='479260'>you</span>
  <span m='479380'>have</span> <span m='479550'>one.</span> </p><p><span m='480350'>OK.</span>
  <span m='481630'>So</span> <span m='482590'>why</span> <span m='482710'>are</span>
  <span m='482830'>we</span> <span m='482920'>doing</span> <span m='483190'>this?</span>
  <span m='484130'>Well,</span> <span m='484540'>the</span> <span m='484720'>ideal</span>
  <span m='485200'>goal</span> <span m='486040'>behind</span> <span m='486460'>MTCS</span>
  <span m='486620'>is</span> <span m='486860'>that we</span> <span m='487200'>want</span>
  <span m='487565'>to</span> <span m='487930'>selectively</span> <span m='488650'>build</span>
  <span m='488950'>up</span> <span m='489160'>different</span> <span m='489460'>parts</span>
  <span m='489730'>of</span> <span m='489790'>the</span> <span m='489870'>tree.</span>
  <span m='490910'>So</span> <span m='493060'>the</span> <span m='493720'>depth-first</span>
  <span m='494090'>search</span> <span m='494590'>way,</span> <span m='494990'>the</span>
  <span m='495110'>exhaustive</span> <span m='496240'>search,</span> <span m='496630'>would</span>
  <span m='496940'>have</span> <span m='497250'>us</span> <span m='497490'>exploring</span>
  <span m='498160'>the</span> <span m='498280'>entire</span> <span m='498720'>koopa</span>
  <span m='498970'>tree,</span> <span m='499270'>and</span> <span m='499610'>that</span>
  <span m='499720'>our</span> <span m='499780'>depth</span> <span m='500200'>is</span>
  <span m='500350'>limited</span> <span m='500680'>by</span> <span m='501220'>looking</span>
  <span m='501480'>at</span> <span m='501630'>all</span> <span m='501830'>the</span>
  <span m='501980'>possible</span> <span m='502170'>nodes</span> <span m='502656'>of
  that</span> <span m='503142'>level.</span> </p><p><span m='503630'>But</span> <span
  m='503800'>what</span> <span m='503980'>we</span> <span m='504160'>want</span> <span
  m='504460'>is</span> <span m='504640'>we</span> <span m='504820'>want--</span> <span
  m='505270'>because</span> <span m='506080'>the</span> <span m='506640'>amount</span>
  <span m='506970'>of computation</span> <span m='507600'>required for</span> <span
  m='507850'>that</span> <span m='508350'>explodes</span> <span m='508850'>really</span>
  <span m='509265'>quickly.</span> <span m='510080'>With</span> <span m='510350'>the</span>
  <span m='510490'>number</span> <span m='510910'>of</span> <span m='511210'>moves</span>
  <span m='511660'>that</span> <span m='511750'>you're</span> <span m='511960'>basically</span>
  <span m='512430'>looking</span> <span m='512900'>into the</span> <span m='513370'>future,</span>
  <span m='513520'>we</span> <span m='513740'>wanted</span> <span m='513789'>to be</span>
  <span m='514070'>able</span> <span m='514419'>to</span> <span m='514539'>search</span>
  <span m='514840'>selectively</span> <span m='515950'>in</span> <span m='516070'>certain</span>
  <span m='516549'>parts</span> <span m='516880'>of</span> <span m='516940'>the</span>
  <span m='517000'>tree.</span> <span m='517495'>And</span> <span m='517840'>so</span>
  <span m='518080'>for</span> <span m='518289'>example,</span> <span m='518809'>if</span>
  <span m='518909'>there</span> <span m='518970'>are</span> <span m='519039'>less</span>
  <span m='519280'>promising</span> <span m='519600'>parts</span> <span m='520390'>over</span>
  <span m='520570'>here,</span> <span m='521230'>then</span> <span m='521380'>we</span>
  <span m='521470'>care</span> <span m='521740'>less</span> <span m='522130'>about</span>
  <span m='522400'>looking</span> <span m='522679'>into</span> <span m='522840'>the</span>
  <span m='522919'>future</span> <span m='523240'>of</span> <span m='523570'>those</span>
  <span m='523900'>areas.</span> <span m='524290'>But</span> <span m='524410'>if</span>
  <span m='524650'>we have</span> <span m='525040'>a</span> <span m='525100'>certain</span>
  <span m='525370'>move--</span> <span m='526030'>in</span> <span m='526120'>chess,</span>
  <span m='526480'>for</span> <span m='526600'>example,</span> <span m='526900'>there's</span>
  <span m='527030'>a</span> <span m='527330'>certain</span> <span m='527750'>move</span>
  <span m='528050'>where</span> <span m='528260'>in</span> <span m='528370'>two</span>
  <span m='528630'>moves,</span> <span m='528890'>you're</span> <span m='529000'>going
  to</span> <span m='529150'>be able</span> <span m='529330'>to</span> <span m='529390'>take</span>
  <span m='529670'>the</span> <span m='529930'>opponent's</span> <span m='530090'>queen.</span>
  <span m='530540'>You're</span> <span m='531330'>really</span> <span m='531640'>want</span>
  <span m='531850'>to search</span> <span m='532270'>that</span> <span m='532460'>region</span>
  <span m='532810'>and</span> <span m='532900'>figure</span> <span m='533170'>out</span>
  <span m='533320'>whether</span> <span m='533470'>that's</span> <span m='533620'>going</span>
  <span m='533870'>to end</span> <span m='534270'>up</span> <span m='534470'>being</span>
  <span m='535820'>a</span> <span m='536270'>significantly</span> <span m='536720'>positive</span>
  <span m='537130'>group</span> <span m='537220'>for</span> <span m='537675'>me.</span>
  </p><p><span m='538130'>And</span> <span m='538240'>so</span> <span m='538840'>the</span>
  <span m='538960'>whole</span> <span m='539200'>goal</span> <span m='539500'>of</span>
  <span m='539720'>our</span> <span m='539975'>algorithm</span> <span m='540230'>is</span>
  <span m='540370'>going</span> <span m='540580'>to</span> <span m='540640'>be</span>
  <span m='540730'>growing</span> <span m='540985'>this</span> <span m='541240'>asymmetric</span>
  <span m='541685'>tree.</span> <span m='543020'>How</span> <span m='543170'>does</span>
  <span m='543370'>that</span> <span m='543450'>sound?</span> <span m='546820'>OK,</span>
  <span m='547560'>great.</span> <span m='548700'>So</span> <span m='549190'>how</span>
  <span m='549350'>do</span> <span m='549410'>we</span> <span m='549560'>actually</span>
  <span m='549890'>do</span> <span m='550010'>this?</span> <span m='551210'>We're</span>
  <span m='551330'>going</span> <span m='551450'>to</span> <span m='551550'>go</span>
  <span m='551810'>over</span> <span m='552080'>a</span> <span m='552170'>high-level</span>
  <span m='552520'>outline,</span> <span m='553200'>but</span> <span m='553460'>before</span>
  <span m='553640'>we</span> <span m='553850'>do</span> <span m='554165'>that,</span>
  <span m='554480'>let's</span> <span m='554640'>talk</span> <span m='554800'>about</span>
  <span m='555000'>our</span> <span m='555230'>tree,</span> <span m='555980'>which</span>
  <span m='556100'>you're</span> <span m='556250'>going to</span> <span m='556550'>get
  very</span> <span m='556730'>familiar</span> <span m='557060'>with.</span> <span
  m='560250'>Can</span> <span m='560710'>people</span> <span m='560950'>see</span>
  <span m='561170'>that this</span> <span m='561340'>is</span> <span m='561490'>red</span>
  <span m='561780'>and</span> <span m='561880'>this</span> <span m='561930'>is</span>
  <span m='562120'>blue?</span> </p><p><span m='564710'>So</span> <span m='564920'>this</span>
  <span m='565190'>is</span> <span m='565540'>our</span> <span m='565910'>game</span>
  <span m='566280'>state</span> <span m='567860'>when</span> <span m='568040'>we</span>
  <span m='568130'>start</span> <span m='568420'>our</span> <span m='568650'>game.</span>
  <span m='568850'>We can</span> <span m='569210'>be</span> <span m='569610'>given</span>
  <span m='570100'>a</span> <span m='570300'>Tic-tac-toe</span> <span m='570580'>board</span>
  <span m='570800'>with a</span> <span m='570950'>[INAUDIBLE]</span> <span m='571300'>place,</span>
  <span m='572570'>a</span> <span m='572630'>game</span> <span m='572840'>of</span>
  <span m='572930'>chess</span> <span m='573320'>with</span> <span m='573620'>the</span>
  <span m='574150'>lose</span> <span m='574540'>configured</span> <span m='574880'>a</span>
  <span m='574910'>certain</span> <span m='575120'>way.</span> <span m='575780'>And</span>
  <span m='576110'>so</span> <span m='576410'>our</span> <span m='576620'>player,</span>
  <span m='577100'>which</span> <span m='577370'>is</span> <span m='577640'>the</span>
  <span m='577970'>computer,</span> <span m='578420'>has</span> <span m='579200'>three</span>
  <span m='579470'>separate</span> <span m='579810'>moves</span> <span m='580120'>that
  it</span> <span m='580280'>can</span> <span m='580675'>take.</span> <span m='581070'>And
  so</span> <span m='581390'>each</span> <span m='581520'>of</span> <span m='581600'>those</span>
  <span m='581800'>moves</span> <span m='582080'>are</span> <span m='582260'>presented</span>
  <span m='582560'>by</span> <span m='582750'>a</span> <span m='583000'>node.</span>
  <span m='583560'>And</span> <span m='583730'>each</span> <span m='583910'>of</span>
  <span m='584000'>those</span> <span m='584300'>moves</span> <span m='585020'>have</span>
  <span m='585200'>response</span> <span m='585770'>moves</span> <span m='586570'>by</span>
  <span m='586750'>the</span> <span m='587185'>opponent.</span> </p><p><span m='588170'>So</span>
  <span m='588650'>you</span> <span m='588770'>can</span> <span m='589060'>imagine</span>
  <span m='589400'>that</span> <span m='589970'>if</span> <span m='590210'>one</span>
  <span m='590390'>of</span> <span m='590480'>these</span> <span m='590870'>is</span>
  <span m='591070'>a</span> <span m='591250'>Tic-tac-toe</span> <span m='591400'>board</span>
  <span m='591580'>with</span> <span m='591950'>just</span> <span m='592160'>a</span>
  <span m='592220'>circle,</span> <span m='592910'>that</span> <span m='593190'>one
  of</span> <span m='593390'>these</span> <span m='593730'>is</span> <span m='594100'>with</span>
  <span m='594320'>that</span> <span m='594480'>circle</span> <span m='594990'>and</span>
  <span m='595270'>the</span> <span m='595490'>next</span> <span m='595700'>place</span>
  <span m='596350'>right</span> <span m='596530'>by it.</span> <span m='597440'>And</span>
  <span m='598090'>as</span> <span m='598310'>you</span> <span m='598670'>go</span>
  <span m='598850'>down</span> <span m='599030'>the</span> <span m='599150'>this</span>
  <span m='599600'>tree,</span> <span m='600620'>you</span> <span m='600770'>start</span>
  <span m='601070'>understanding</span> <span m='602540'>basically,</span> <span m='602840'>it's</span>
  <span m='603140'>the</span> <span m='603230'>way</span> <span m='603380'>that</span>
  <span m='603620'>humans</span> <span m='604040'>think</span> <span m='604190'>about</span>
  <span m='605250'>playing</span> <span m='605450'>these games.</span> </p><p><span
  m='606260'>If</span> <span m='606590'>I</span> <span m='606720'>go</span> <span
  m='607110'>here,</span> <span m='608580'>then</span> <span m='608800'>what if</span>
  <span m='609100'>they</span> <span m='609230'>go</span> <span m='609410'>there,</span>
  <span m='610160'>and</span> <span m='610280'>then</span> <span m='610580'>what</span>
  <span m='610730'>if</span> <span m='610850'>I</span> <span m='611070'>go</span>
  <span m='611410'>right</span> <span m='611670'>here.</span> <span m='612280'>You</span>
  <span m='612380'>try</span> <span m='612620'>to</span> <span m='612680'>think</span>
  <span m='612950'>through</span> <span m='613580'>the</span> <span m='613970'>set
  of</span> <span m='614275'>future</span> <span m='614580'>moves</span> <span m='614990'>and</span>
  <span m='615080'>try</span> <span m='615320'>to</span> <span m='615380'>evaluate</span>
  <span m='616940'>whether</span> <span m='617330'>your</span> <span m='617450'>move</span>
  <span m='617750'>will</span> <span m='617930'>be</span> <span m='618050'>good</span>
  <span m='618230'>in</span> <span m='618320'>the</span> <span m='618410'>long</span>
  <span m='618660'>term</span> <span m='618840'>sense.</span> <span m='620850'>They</span>
  <span m='621140'>way that</span> <span m='621350'>are</span> <span m='621470'>going</span>
  <span m='621710'>to</span> <span m='621860'>expand</span> <span m='622280'>our</span>
  <span m='622340'>tree,</span> <span m='622610'>as</span> <span m='622730'>we</span>
  <span m='622820'>said,</span> <span m='623090'>to</span> <span m='623440'>create</span>
  <span m='623640'>an</span> <span m='624320'>asymmetric</span> <span m='624520'>tree</span>
  <span m='625490'>is</span> <span m='625850'>first</span> <span m='626150'>of</span>
  <span m='626210'>all,</span> <span m='626510'>we're</span> <span m='626610'>going</span>
  <span m='626760'>to</span> <span m='626900'>descend</span> <span m='627160'>through</span>
  <span m='627420'>the</span> <span m='627610'>tree.</span> </p><p><span m='628130'>We're</span>
  <span m='628620'>going to</span> <span m='628880'>start at the</span> <span m='629165'>top</span>
  <span m='629450'>and</span> <span m='629540'>we're</span> <span m='629840'>basically,</span>
  <span m='630260'>jump</span> <span m='630830'>down</span> <span m='631310'>some</span>
  <span m='631560'>sequence</span> <span m='632200'>of</span> <span m='633030'>branches</span>
  <span m='633570'>until</span> <span m='633780'>we</span> <span m='634060'>figure</span>
  <span m='634280'>out</span> <span m='634560'>where</span> <span m='634940'>we're</span>
  <span m='635190'>going</span> <span m='635490'>to</span> <span m='637350'>place
  our new</span> <span m='637500'>node,</span> <span m='638240'>which</span> <span
  m='638360'>seems</span> <span m='638750'>like</span> <span m='638940'>a</span> <span
  m='639010'>key</span> <span m='639330'>operation</span> <span m='639810'>here.</span>
  <span m='639920'>To</span> <span m='639950'>create</span> <span m='640170'>an</span>
  <span m='640440'>asymmetric</span> <span m='641120'>tree</span> <span m='641310'>it's
  all about</span> <span m='641782'>how you</span> <span m='642254'>[INAUDIBLE].</span>
  </p><p><span m='644060'>For</span> <span m='644210'>example,</span> <span m='644600'>in</span>
  <span m='644660'>this</span> <span m='644780'>case,</span> <span m='645150'>we're</span>
  <span m='645250'>going</span> <span m='645290'>to</span> <span m='645490'>pick</span>
  <span m='646190'>this</span> <span m='646310'>sequence</span> <span m='646730'>of</span>
  <span m='646790'>nodes.</span> <span m='648580'>And</span> <span m='649270'>once</span>
  <span m='649520'>we</span> <span m='649610'>get</span> <span m='649760'>to</span>
  <span m='649820'>the</span> <span m='649910'>bottom</span> <span m='650320'>and
  find every</span> <span m='650670'>location,</span> <span m='651596'>we're</span>
  <span m='652062'>going</span> <span m='652530'>to</span> <span m='652820'>create</span>
  <span m='653050'>a new</span> <span m='653200'>node.</span> <span m='653680'>It's</span>
  <span m='654010'>not very</span> <span m='654445'>hard.</span> </p><p><span m='655750'>Then</span>
  <span m='656900'>we're</span> <span m='657020'>going</span> <span m='657260'>to</span>
  <span m='657430'>simulate</span> <span m='657750'>a</span> <span m='658070'>game</span>
  <span m='658500'>from</span> <span m='658840'>this</span> <span m='658930'>new</span>
  <span m='659310'>node.</span> <span m='659690'>And</span> <span m='659810'>this</span>
  <span m='659960'>is</span> <span m='660420'>the</span> <span m='660500'>key</span>
  <span m='660860'>part</span> <span m='661670'>of</span> <span m='661880'>MCTS.</span>
  <span m='663260'>Once</span> <span m='663500'>you</span> <span m='663590'>get</span>
  <span m='664100'>to</span> <span m='664490'>new</span> <span m='664940'>a</span>
  <span m='665180'>location,</span> <span m='666090'>what</span> <span m='666320'>you're</span>
  <span m='666410'>going</span> <span m='666630'>to</span> <span m='666700'>be</span>
  <span m='666800'>doing</span> <span m='667170'>then,</span> <span m='667420'>is</span>
  <span m='667670'>you're</span> <span m='667900'>going</span> <span m='668100'>to</span>
  <span m='668330'>be</span> <span m='668635'>simulating</span> <span m='668940'>a
  game</span> <span m='669590'>from</span> <span m='669950'>that</span> <span m='670100'>new</span>
  <span m='670310'>location.</span> </p><p><span m='670820'>We're</span> <span m='670880'>going</span>
  <span m='671000'>to</span> <span m='671060'>talk</span> <span m='671240'>about</span>
  <span m='671450'>how</span> <span m='671720'>you</span> <span m='671840'>go</span>
  <span m='672050'>about</span> <span m='672200'>simulating</span> <span m='672790'>a</span>
  <span m='672830'>game</span> <span m='673490'>from</span> <span m='674930'>this</span>
  <span m='675790'>more</span> <span m='676070'>advanced</span> <span m='676660'>game</span>
  <span m='676920'>state</span> <span m='677300'>that</span> <span m='677570'>what</span>
  <span m='677720'>we</span> <span m='677780'>started</span> <span m='678120'>out</span>
  <span m='678530'>with.</span> <span m='678907'>Does</span> <span m='679284'>anyone
  have</span> <span m='679661'>any</span> <span m='680040'>questions</span> <span
  m='680430'>right now?</span> <span m='681010'>We</span> <span m='681130'>will</span>
  <span m='681280'>be</span> <span m='681370'>going</span> <span m='681640'>in depth</span>
  <span m='681960'>into</span> <span m='682080'>all</span> <span m='682250'>of</span>
  <span m='682560'>these</span> <span m='682800'>steps,</span> <span m='683040'>but
  just</span> <span m='683260'>in a</span> <span m='683692'>high level</span> <span
  m='684124'>sense.</span> </p><p><span m='684556'>AUDIENCE:</span> <span m='684772'>Just</span>
  <span m='684988'>a quick question.</span> </p><p><span m='685420'>PROFESSOR 3:</span>
  <span m='685540'>Yeah.</span> </p><p><span m='685660'>AUDIENCE:</span> <span m='685832'>To
  create</span> <span m='686005'>the</span> <span m='686350'>new</span> <span m='686470'>node,</span>
  <span m='686967'>is it</span> <span m='687464'>probabilistic,</span> <span m='687961'>just</span>
  <span m='688458'>creating a</span> <span m='688955'>new node</span> <span m='689452'>as
  the most probable</span> <span m='689949'>[INAUDIBLE]</span> </p><p><span m='690450'>PROFESSOR
  3:</span> <span m='690525'>No,</span> <span m='690600'>no.</span> <span m='691300'>You're</span>
  <span m='691570'>creating</span> <span m='691870'>some</span> <span m='692200'>new</span>
  <span m='692290'>node.</span> <span m='692590'>We'll talk</span> <span m='692800'>about</span>
  <span m='693010'>how</span> <span m='693240'>we</span> <span m='693330'>pick</span>
  <span m='693530'>that</span> <span m='693730'>new node,</span> <span m='694140'>but
  we're</span> <span m='694550'>just</span> <span m='694860'>making</span> <span m='695130'>a
  new</span> <span m='695250'>node</span> <span m='695706'>and</span> <span m='696162'>we're
  not thinking</span> <span m='696620'>anything about</span> <span m='696940'>probability.</span>
  </p><p><span m='697960'>The</span> <span m='698040'>next</span> <span m='698260'>thing</span>
  <span m='698630'>is that</span> <span m='698770'>we're</span> <span m='698950'>going</span>
  <span m='699260'>to</span> <span m='699380'>update the</span> <span m='699740'>tree.</span>
  <span m='700030'>So</span> <span m='700210'>whatever</span> <span m='700400'>the</span>
  <span m='700550'>value</span> <span m='700750'>of</span> <span m='700900'>the</span>
  <span m='701120'>simulation</span> <span m='701670'>delta</span> <span m='702065'>was--</span>
  <span m='703195'>delta,</span> <span m='703650'>remember--</span> <span m='707300'>we're</span>
  <span m='707480'>going</span> <span m='707810'>to</span> <span m='708420'>propagate</span>
  <span m='708710'>that</span> <span m='708980'>up</span> <span m='709670'>and</span>
  <span m='709790'>basically</span> <span m='710360'>add</span> <span m='710600'>that</span>
  <span m='711140'>to</span> <span m='711380'>all</span> <span m='711590'>of</span>
  <span m='711950'>the</span> <span m='712070'>nodes</span> <span m='712430'>that</span>
  <span m='712550'>are</span> <span m='712670'>in that</span> <span m='712760'>parent</span>
  <span m='713120'>of</span> <span m='713190'>that</span> <span m='713370'>node in
  the</span> <span m='713670'>tree</span> <span m='714500'>and</span> <span m='714740'>update</span>
  <span m='715010'>some</span> <span m='715270'>information</span> <span m='715780'>that</span>
  <span m='715950'>goes</span> <span m='716160'>in there and that they're</span> <span
  m='716590'>storing.</span> </p><p><span m='718090'>This</span> <span m='718480'>is</span>
  <span m='718610'>going</span> <span m='718790'>to</span> <span m='718850'>be</span>
  <span m='718970'>good</span> <span m='719240'>because</span> <span m='719480'>it's</span>
  <span m='719600'>going</span> <span m='719750'>to</span> <span m='719840'>mean</span>
  <span m='720140'>that--</span> <span m='720980'>it's</span> <span m='721340'>a</span>
  <span m='721400'>lot</span> <span m='721590'>like</span> <span m='721730'>in</span>
  <span m='722060'>search</span> <span m='722490'>algorithms</span> <span m='722710'>where</span>
  <span m='722975'>you have</span> <span m='723240'>trees</span> <span m='723950'>that</span>
  <span m='724310'>then</span> <span m='724640'>the</span> <span m='725090'>entirety
  of the</span> <span m='725200'>tree</span> <span m='725360'>remains</span> <span
  m='725690'>up</span> <span m='725840'>to</span> <span m='725900'>date</span> <span
  m='726110'>with</span> <span m='726240'>the</span> <span m='726320'>information</span>
  <span m='726670'>from</span> <span m='726940'>every</span> <span m='727240'>given</span>
  <span m='727713'>simulation.</span> <span m='728660'>And</span> <span m='729050'>we're</span>
  <span m='729170'>just</span> <span m='729320'>going</span> <span m='729440'>to</span>
  <span m='729500'>repeat</span> <span m='729710'>this</span> <span m='730100'>over</span>
  <span m='730400'>and</span> <span m='730490'>over</span> <span m='730700'>and</span>
  <span m='730790'>over</span> <span m='731010'>again.</span> <span m='731390'>And</span>
  <span m='731720'>slowly,</span> <span m='732200'>our</span> <span m='732290'>tree</span>
  <span m='732560'>will</span> <span m='732710'>grow</span> <span m='732950'>out</span>
  <span m='733640'>until</span> <span m='735050'>whenever</span> <span m='735380'>we</span>
  <span m='735500'>feel</span> <span m='735740'>like</span> <span m='735970'>stopping.</span>
  </p><p><span m='736280'>This</span> <span m='736510'>is</span> <span m='736640'>actually</span>
  <span m='736830'>one</span> <span m='737020'>of</span> <span m='737120'>the nice</span>
  <span m='737300'>things</span> <span m='737570'>about</span> <span m='737690'>MCTS,</span>
  <span m='738560'>is</span> <span m='738710'>that</span> <span m='739190'>whenever</span>
  <span m='739520'>we</span> <span m='739640'>decide</span> <span m='741590'>that</span>
  <span m='741980'>we're</span> <span m='742100'>out</span> <span m='742220'>of</span>
  <span m='742310'>time,</span> <span m='742730'>like for example,</span> <span m='743300'>if
  you're in a</span> <span m='743560'>competition</span> <span m='745040'>playing</span>
  <span m='745510'>a</span> <span m='745760'>champion</span> <span m='746060'>Go</span>
  <span m='746330'>player,</span> <span m='747520'>you</span> <span m='748200'>can</span>
  <span m='748340'>stop the</span> <span m='748700'>simulation.</span> <span m='749060'>And</span>
  <span m='749140'>then</span> <span m='749250'>all you</span> <span m='749440'>have
  to</span> <span m='749870'>do</span> <span m='750050'>is</span> <span m='750250'>pick</span>
  <span m='750710'>between</span> <span m='751340'>one</span> <span m='751520'>of</span>
  <span m='751640'>the</span> <span m='751790'>best</span> <span m='752810'>first</span>
  <span m='753290'>moves</span> <span m='754220'>that</span> <span m='754340'>you're</span>
  <span m='754460'>going</span> <span m='754700'>to make.</span> <span m='755780'>Because</span>
  <span m='756560'>an</span> <span m='756900'>the end of the</span> <span m='757010'>day,</span>
  <span m='758120'>after</span> <span m='758420'>you're</span> <span m='758510'>doing</span>
  <span m='758720'>all</span> <span m='758870'>the</span> <span m='758990'>simulation,</span>
  <span m='759770'>we're</span> <span m='759860'>still</span> <span m='760100'>right</span>
  <span m='760320'>here.</span> <span m='761010'>And</span> <span m='761330'>we're</span>
  <span m='761580'>still</span> <span m='761880'>only</span> <span m='762140'>picking</span>
  <span m='762260'>between the</span> <span m='762530'>movies</span> <span m='762890'>that</span>
  <span m='763580'>go</span> <span m='763820'>immediately</span> <span m='764490'>where</span>
  <span m='764570'>we</span> <span m='764710'>started.</span> <span m='765850'>Yeah.</span>
  </p><p><span m='767260'>AUDIENCE:</span> <span m='767416'>Could</span> <span m='767572'>this</span>
  <span m='767730'>[INAUDIBLE]</span> <span m='769140'>good</span> <span m='769610'>tree?</span>
  <span m='770080'>And then</span> <span m='770550'>on</span> <span m='770880'>some
  initial</span> <span m='771216'>region</span> <span m='771552'>of</span> <span m='771890'>interest,</span>
  <span m='772290'>or is</span> <span m='772742'>it</span> <span m='773646'>arbitrary</span>
  <span m='774550'>how</span> <span m='775002'>you</span> <span m='775454'>get</span>
  <span m='775906'>to</span> <span m='776358'>create it?</span> </p><p><span m='776810'>PROFESSOR
  3:</span> <span m='776915'>We'll</span> <span m='777020'>go</span> <span m='777140'>through</span>
  <span m='777320'>how</span> <span m='777710'>you pick</span> <span m='777900'>where</span>
  <span m='778010'>to</span> <span m='778280'>descend</span> <span m='778470'>right
  now.</span> <span m='780410'>I</span> <span m='780530'>guess,</span> <span m='780850'>it's</span>
  <span m='781490'>any</span> <span m='781760'>possible</span> <span m='783110'>move</span>
  <span m='783380'>that</span> <span m='783530'>starts</span> <span m='784030'>at</span>
  <span m='784250'>your</span> <span m='784480'>starting</span> <span m='784963'>game</span>
  <span m='785446'>state.</span> <span m='786412'>Does that make--</span> <span m='788350'>great.</span>
  </p><p><span m='790480'>Before</span> <span m='791110'>we</span> <span m='791740'>move</span>
  <span m='791950'>on</span> <span m='792070'>to</span> <span m='792160'>the</span>
  <span m='792300'>algorithm</span> <span m='792540'>itself,</span> <span m='792970'>let's</span>
  <span m='793270'>talk</span> <span m='793500'>about what</span> <span m='793580'>we</span>
  <span m='793925'>store</span> <span m='794270'>in each one of</span> <span m='794450'>these</span>
  <span m='794710'>nodes.</span> <span m='797360'>So</span> <span m='798050'>now</span>
  <span m='798260'>we've</span> <span m='798410'>added</span> <span m='798740'>these</span>
  <span m='798860'>numbers.</span> <span m='799400'>And</span> <span m='799610'>these</span>
  <span m='799760'>numbers</span> <span m='800030'>represent</span> <span m='800930'>is</span>
  <span m='801560'>that</span> <span m='801770'>nk,</span> <span m='802510'>as</span>
  <span m='802670'>in</span> <span m='802910'>the</span> <span m='803030'>value</span>
  <span m='803290'>of</span> <span m='803400'>the</span> <span m='803480'>right,</span>
  <span m='804170'>is</span> <span m='804620'>the</span> <span m='804770'>number</span>
  <span m='805220'>of</span> <span m='805310'>games</span> <span m='805730'>that</span>
  <span m='805870'>have</span> <span m='806010'>been</span> <span m='806150'>played</span>
  <span m='806560'>that</span> <span m='806860'>involve</span> <span m='807320'>a</span>
  <span m='807390'>certain</span> <span m='807660'>node.</span> </p><p><span m='808500'>So</span>
  <span m='808580'>for</span> <span m='808730'>example,</span> <span m='809670'>if</span>
  <span m='809800'>I</span> <span m='810020'>look</span> <span m='810370'>this</span>
  <span m='810650'>node,</span> <span m='811070'>that</span> <span m='811220'>means</span>
  <span m='811850'>that</span> <span m='812030'>four</span> <span m='812450'>games</span>
  <span m='813080'>have</span> <span m='813230'>been</span> <span m='813410'>played</span>
  <span m='814190'>that</span> <span m='814310'>involve</span> <span m='814650'>this</span>
  <span m='814820'>node.</span> <span m='814960'>A</span> <span m='815290'>game</span>
  <span m='815620'>that has</span> <span m='815740'>been played that</span> <span
  m='816110'>involves</span> <span m='816450'>the node</span> <span m='816820'>just</span>
  <span m='816980'>means</span> <span m='817510'>that</span> <span m='817730'>one</span>
  <span m='817940'>of</span> <span m='818060'>the</span> <span m='818180'>states</span>
  <span m='818570'>of the</span> <span m='818720'>board</span> <span m='819110'>at</span>
  <span m='819260'>some</span> <span m='819590'>point</span> <span m='819890'>in</span>
  <span m='820040'>the</span> <span m='820130'>game</span> <span m='820940'>was</span>
  <span m='821870'>the</span> <span m='821960'>state</span> <span m='822440'>of</span>
  <span m='822500'>the</span> <span m='822590'>board</span> <span m='823010'>that
  this</span> <span m='823400'>represents.</span> <span m='825480'>For</span> <span
  m='825660'>example,</span> <span m='825970'>if I</span> <span m='826280'>have a</span>
  <span m='826340'>game</span> <span m='826610'>that</span> <span m='826690'>was</span>
  <span m='826850'>played</span> <span m='827330'>here,</span> <span m='828400'>if
  I</span> <span m='828680'>know</span> <span m='828860'>that</span> <span m='828980'>I've</span>
  <span m='829100'>played</span> <span m='829340'>this</span> <span m='829720'>once,</span>
  <span m='830470'>then</span> <span m='830520'>that</span> <span m='830730'>guarantees</span>
  <span m='830900'>to</span> <span m='831175'>me</span> <span m='831450'>that</span>
  <span m='831590'>I</span> <span m='831650'>played</span> <span m='831830'>this</span>
  <span m='832010'>game</span> <span m='832220'>once</span> <span m='832490'>because</span>
  <span m='832730'>this</span> <span m='832880'>is</span> <span m='832970'>a</span>
  <span m='833040'>precursor</span> <span m='833390'>state</span> <span m='833740'>to</span>
  <span m='833960'>this</span> <span m='834460'>one.</span> <span m='835444'>Make</span>
  <span m='835936'>sense?</span> <span m='836920'>Yeah.</span> </p><p><span m='837904'>AUDIENCE:</span>
  <span m='838068'>How</span> <span m='838232'>can</span> <span m='838396'>the</span>
  <span m='838888'>two</span> <span m='839380'>n's</span> <span m='839872'>below that</span>
  <span m='840370'>node</span> <span m='840640'>not add up to a</span> <span m='841112'>value</span>
  <span m='841584'>of</span> <span m='842056'>[INAUDIBLE]</span> </p><p><span m='843000'>PROFESSOR
  3:</span> <span m='843115'>That</span> <span m='843230'>will</span> <span m='843730'>come</span>
  <span m='843970'>when</span> <span m='844170'>we</span> <span m='844740'>start</span>
  <span m='844990'>expanding</span> <span m='845370'>our game.</span> <span m='845960'>But</span>
  <span m='846250'>that's</span> <span m='846460'>a</span> <span m='846520'>great</span>
  <span m='846790'>question.</span> <span m='847180'>And</span> <span m='847553'>intuitively</span>
  <span m='847926'>speaking,</span> <span m='848300'>it should.</span> </p><p><span
  m='850270'>AUDIENCE:</span> <span m='850450'>You're</span> <span m='850630'>saying</span>
  <span m='850840'>you're</span> <span m='850950'>storing</span> <span m='851210'>data</span>
  <span m='851495'>from</span> <span m='851780'>past</span> <span m='852060'>games</span>
  <span m='852940'>about</span> <span m='853250'>what</span> <span m='853750'>we've--</span>
  </p><p><span m='854250'>PROFESSOR 3:</span> <span m='854350'>Yes.</span> </p><p><span
  m='854450'>AUDIENCE:</span> <span m='854688'>--done</span> <span m='854927'>before.</span>
  </p><p><span m='856690'>AUDIENCE:</span> <span m='856840'>If past</span> <span m='856990'>game's</span>
  <span m='857290'>outside</span> <span m='857860'>of</span> <span m='857920'>the</span>
  <span m='858070'>script simulation?</span> </p><p><span m='858360'>PROFESSOR 3:</span>
  <span m='858575'>No,</span> <span m='858790'>no, no.</span> <span m='859220'>Past
  game's</span> <span m='859400'>in the</span> <span m='859690'>script</span> <span
  m='860165'>simulation.</span> <span m='861850'>And</span> <span m='862140'>then
  the</span> <span m='862450'>other</span> <span m='862690'>value</span> <span m='863110'>is</span>
  <span m='863260'>the</span> <span m='863320'>number</span> <span m='863590'>of</span>
  <span m='863900'>wins</span> <span m='864390'>associated</span> <span m='865262'>with</span>
  <span m='865698'>a</span> <span m='866134'>certain</span> <span m='866570'>node.</span>
  <span m='867010'>And</span> <span m='867130'>these</span> <span m='867280'>are going
  to be</span> <span m='867580'>wins</span> <span m='867880'>for</span> <span m='868150'>player
  one,</span> <span m='868710'>which</span> <span m='868890'>is</span> <span m='869160'>red</span>
  <span m='869380'>in</span> <span m='869640'>this case.</span> <span m='870890'>It</span>
  <span m='870990'>would</span> <span m='871140'>get</span> <span m='871460'>confusing</span>
  <span m='871660'>if we</span> <span m='871770'>put both</span> <span m='872030'>of</span>
  <span m='872230'>them,</span> <span m='872410'>but</span> <span m='872620'>they're</span>
  <span m='872770'>complementary.</span> </p><p><span m='874120'>So</span> <span m='874360'>for</span>
  <span m='874510'>example,</span> <span m='875690'>three</span> <span m='875890'>out
  of the</span> <span m='876040'>four</span> <span m='876280'>times</span> <span m='877020'>that</span>
  <span m='877330'>the</span> <span m='877630'>red</span> <span m='877840'>player</span>
  <span m='878140'>visited</span> <span m='878660'>this</span> <span m='878760'>node,</span>
  <span m='878940'>they</span> <span m='879280'>won</span> <span m='879620'>in that</span>
  <span m='879900'>node.</span> <span m='882820'>And</span> <span m='883030'>these</span>
  <span m='883240'>are</span> <span m='883330'>the</span> <span m='883670'>two</span>
  <span m='883810'>numbers</span> <span m='884060'>that</span> <span m='884180'>we're
  going</span> <span m='884350'>to store. And</span> <span m='884800'>we're</span>
  <span m='884890'>going</span> <span m='885010'>to</span> <span m='885070'>see</span>
  <span m='885280'>why</span> <span m='885500'>they're</span> <span m='885600'>significant</span>
  <span m='885790'>to store</span> <span m='886075'>later.</span> </p><p><span m='888760'>So</span>
  <span m='889000'>first,</span> <span m='889400'>descending</span> <span m='890540'>the</span>
  <span m='891180'>key</span> <span m='891640'>part</span> <span m='892030'>of</span>
  <span m='892140'>our</span> <span m='892240'>algorithm</span> <span m='892700'>that</span>
  <span m='892830'>we're</span> <span m='892960'>talking about.</span> <span m='893670'>And</span>
  <span m='893970'>when</span> <span m='894200'>descending,</span> <span m='894770'>there</span>
  <span m='895200'>are</span> <span m='895600'>these two</span> <span m='895900'>counterbalanced</span>
  <span m='897710'>desires</span> <span m='898260'>that we</span> <span m='898480'>have.</span>
  <span m='899260'>The</span> <span m='899380'>first</span> <span m='899680'>of</span>
  <span m='899780'>them</span> <span m='900640'>is</span> <span m='901240'>that</span>
  <span m='901360'>we</span> <span m='901510'>want</span> <span m='901900'>to</span>
  <span m='902920'>explore</span> <span m='903400'>really</span> <span m='903670'>deeply</span>
  <span m='904090'>into</span> <span m='904350'>our</span> <span m='904420'>tree.</span>
  <span m='905410'>We</span> <span m='905470'>want</span> <span m='905650'>to</span>
  <span m='905710'>think</span> <span m='905890'>about,</span> <span m='906380'>OK,</span>
  <span m='907130'>if</span> <span m='907300'>they</span> <span m='907540'>do</span>
  <span m='907690'>this</span> <span m='908030'>then</span> <span m='908190'>I'll
  do</span> <span m='908350'>this.</span> <span m='908650'>And</span> <span m='908770'>then,</span>
  <span m='909110'>well,</span> <span m='909270'>then</span> <span m='909460'>I'll</span>
  <span m='909760'>do</span> <span m='909910'>that</span> <span m='910260'>unless</span>
  <span m='910310'>I want</span> <span m='910450'>it</span> <span m='910570'>to</span>
  <span m='910750'>forth.</span> </p><p><span m='911460'>And we</span> <span m='911600'>want</span>
  <span m='911780'>to</span> <span m='911840'>think</span> <span m='912010'>through</span>
  <span m='912190'>a</span> <span m='912250'>long</span> <span m='912440'>term</span>
  <span m='912610'>strategy.</span> <span m='913510'>But</span> <span m='913750'>at</span>
  <span m='913810'>the</span> <span m='913900'>same</span> <span m='914110'>time,
  we</span> <span m='914430'>don't</span> <span m='914720'>want to get</span> <span
  m='914890'>caught</span> <span m='915220'>in</span> <span m='915690'>that.</span>
  <span m='916870'>We</span> <span m='917320'>want</span> <span m='917470'>to</span>
  <span m='917530'>make</span> <span m='917650'>sure</span> <span m='917950'>that</span>
  <span m='918130'>we're</span> <span m='918490'>not</span> <span m='918700'>missing</span>
  <span m='919260'>a</span> <span m='919340'>really</span> <span m='919720'>promising</span>
  <span m='921400'>other</span> <span m='921700'>movie</span> <span m='922070'>that</span>
  <span m='922390'>we weren't even</span> <span m='922750'>considering</span> <span
  m='923005'>because</span> <span m='923260'>we were</span> <span m='923420'>really</span>
  <span m='924100'>going</span> <span m='924400'>down</span> <span m='924670'>this</span>
  <span m='925110'>certain</span> <span m='925470'>rabbit</span> <span m='925790'>hole</span>
  <span m='926440'>of</span> <span m='927100'>the</span> <span m='927220'>move</span>
  <span m='927410'>that</span> <span m='927520'>we</span> <span m='927640'>had</span>
  <span m='927730'>thought</span> <span m='927910'>about</span> <span m='928060'>before.</span>
  </p><p><span m='928840'>This</span> <span m='928990'>is</span> <span m='929080'>illustrated</span>
  <span m='929590'>by</span> <span m='929980'>the</span> <span m='930452'>x</span>
  <span m='930924'>case</span> <span m='931396'>[INAUDIBLE] SMBC.</span> <span m='933260'>The</span>
  <span m='933670'>SMBC</span> <span m='934080'>comic</span> <span m='934590'>about</span>
  <span m='934920'>academia</span> <span m='935420'>and</span> <span m='935920'>how</span>
  <span m='936170'>someone</span> <span m='936460'>tells</span> <span m='936730'>you</span>
  <span m='937240'>that</span> <span m='937600'>a</span> <span m='937660'>lot</span>
  <span m='937840'>of</span> <span m='937900'>really</span> <span m='938110'>great</span>
  <span m='938380'>work</span> <span m='938560'>has</span> <span m='938680'>been</span>
  <span m='938830'>done</span> <span m='938980'>in</span> <span m='939080'>an</span>
  <span m='939200'>area,</span> <span m='939490'>that</span> <span m='939670'>means</span>
  <span m='939850'>nothing</span> <span m='940240'>about</span> <span m='940450'>how</span>
  <span m='940540'>promising</span> <span m='940825'>the</span> <span m='941110'>future</span>
  <span m='941410'>will</span> <span m='941858'>be.</span> <span m='944100'>It's</span>
  <span m='944200'>all</span> <span m='944320'>about</span> <span m='944440'>expansion</span>
  <span m='944710'>and</span> <span m='944980'>exploration.</span> </p><p><span m='945790'>And</span>
  <span m='945910'>the</span> <span m='946000'>way</span> <span m='946210'>that</span>
  <span m='946300'>we're</span> <span m='946420'>going</span> <span m='946630'>to</span>
  <span m='946720'>balance</span> <span m='947260'>expansion</span> <span m='947590'>and</span>
  <span m='947920'>exploration</span> <span m='948520'>in</span> <span m='948870'>order
  to</span> <span m='949140'>create</span> <span m='949520'>our</span> <span m='949760'>really</span>
  <span m='950040'>nice</span> <span m='950320'>asymmetric</span> <span m='950640'>tree</span>
  <span m='951610'>is</span> <span m='952720'>the</span> <span m='952890'>following</span>
  <span m='953330'>formula.</span> <span m='954083'>And it's</span> <span m='954426'>fine
  if</span> <span m='954770'>that</span> <span m='954940'>looks</span> <span m='955150'>really</span>
  <span m='955510'>confusing</span> <span m='956110'>and</span> <span m='956230'>messy.</span>
  <span m='957610'>But</span> <span m='958300'>actually,</span> <span m='958720'>it</span>
  <span m='958780'>breaks</span> <span m='959080'>down</span> <span m='959380'>quite</span>
  <span m='959620'>nicely</span> <span m='960460'>into</span> <span m='960610'>two</span>
  <span m='960790'>parts.</span> </p><p><span m='963220'>This</span> <span m='963620'>formula</span>
  <span m='963950'>is</span> <span m='964090'>known as the</span> <span m='964380'>UCB.</span>
  <span m='964860'>You don't need</span> <span m='965190'>to know</span> <span m='965460'>why</span>
  <span m='965790'>it's</span> <span m='966135'>the</span> <span m='966480'>Upper</span>
  <span m='966640'>Confidence</span> <span m='967120'>Bound.</span> <span m='967600'>Let's</span>
  <span m='967780'>just</span> <span m='968050'>talk</span> <span m='968230'>about</span>
  <span m='968470'>what's</span> <span m='968650'>inside it.</span> </p><p><span m='969460'>So</span>
  <span m='969560'>first</span> <span m='969760'>of</span> <span m='969850'>all,</span>
  <span m='970070'>you</span> <span m='970090'>have</span> <span m='970210'>this</span>
  <span m='970270'>term</span> <span m='970450'>on the</span> <span m='970590'>left.</span>
  <span m='971230'>And</span> <span m='971320'>this</span> <span m='971440'>term</span>
  <span m='971620'>on</span> <span m='971710'>the</span> <span m='971800'>left</span>
  <span m='972590'>is</span> <span m='973050'>the</span> <span m='973170'>extension</span>
  <span m='973620'>term.</span> <span m='974590'>It's</span> <span m='974800'>basically</span>
  <span m='975310'>proportional</span> <span m='975820'>to</span> <span m='976480'>the</span>
  <span m='976930'>likelihood</span> <span m='978030'>that</span> <span m='978230'>the</span>
  <span m='978350'>expected</span> <span m='978910'>number</span> <span m='979150'>of</span>
  <span m='979210'>times</span> <span m='979580'>that</span> <span m='979660'>you're</span>
  <span m='979780'>going</span> <span m='979990'>to</span> <span m='980080'>win,</span>
  <span m='981050'>given</span> <span m='981310'>that</span> <span m='981430'>you</span>
  <span m='981570'>are</span> <span m='981680'>in</span> <span m='981760'>a</span>
  <span m='981830'>certain</span> <span m='982220'>node</span> <span m='983320'>and</span>
  <span m='983830'>that</span> <span m='983950'>you</span> <span m='984040'>were</span>
  <span m='984190'>a</span> <span m='984220'>certain</span> <span m='984490'>player.</span>
  <span m='987350'>It's</span> <span m='987460'>basically</span> <span m='987790'>the</span>
  <span m='987950'>quality</span> <span m='988390'>of your</span> <span m='988695'>state</span>
  <span m='989000'>in</span> <span m='989070'>some</span> <span m='989280'>abstract</span>
  <span m='989580'>level.</span> <span m='990310'>If</span> <span m='990430'>we</span>
  <span m='990580'>knew</span> <span m='990760'>this</span> <span m='991040'>perfectly,</span>
  <span m='991920'>then</span> <span m='992110'>we</span> <span m='992260'>would</span>
  <span m='992410'>be</span> <span m='992530'>doing</span> <span m='992800'>great</span>
  <span m='993050'>because</span> <span m='993440'>that's</span> <span m='993760'>the</span>
  <span m='993910'>thing</span> <span m='994250'>we're</span> <span m='994400'>looking</span>
  <span m='994720'>for</span> <span m='994990'>on</span> <span m='995110'>some</span>
  <span m='995350'>grand</span> <span m='995560'>level,</span> <span m='997240'>The
  expected</span> <span m='997780'>likelihood</span> <span m='998140'>of</span> <span
  m='998260'>winning</span> <span m='998560'>from a</span> <span m='998930'>certain
  state.</span> </p><p><span m='999910'>On</span> <span m='999970'>the</span> <span
  m='1000030'>other</span> <span m='1000210'>hand,</span> <span m='1000640'>you</span>
  <span m='1000690'>have</span> <span m='1001020'>this</span> <span m='1001200'>exploration</span>
  <span m='1001485'>term.</span> <span m='1002480'>And</span> <span m='1002660'>you</span>
  <span m='1002760'>may</span> <span m='1002960'>not</span> <span m='1003180'>be able
  to</span> <span m='1003300'>read</span> <span m='1003600'>the</span> <span m='1003720'>font</span>
  <span m='1003990'>there.</span> <span m='1004150'>But</span> <span m='1004290'>what</span>
  <span m='1004440'>this</span> <span m='1004570'>is</span> <span m='1004630'>basically</span>
  <span m='1005000'>saying</span> <span m='1005700'>is</span> <span m='1005880'>that</span>
  <span m='1006280'>it</span> <span m='1006450'>looks</span> <span m='1006660'>at</span>
  <span m='1006720'>the</span> <span m='1006840'>number</span> <span m='1007230'>of</span>
  <span m='1007320'>games</span> <span m='1009150'>that</span> <span m='1010020'>I</span>
  <span m='1010220'>have</span> <span m='1011590'>been</span> <span m='1012070'>played</span>
  <span m='1012350'>through,</span> <span m='1013050'>and</span> <span m='1013170'>it</span>
  <span m='1013230'>was</span> <span m='1013440'>the</span> <span m='1013560'>number</span>
  <span m='1013830'>of</span> <span m='1013890'>games</span> <span m='1014580'>that</span>
  <span m='1014700'>my</span> <span m='1014880'>parent</span> <span m='1015230'>has</span>
  <span m='1015380'>been</span> <span m='1015490'>played</span> <span m='1015700'>through.</span>
  <span m='1016470'>And it</span> <span m='1016740'>tries</span> <span m='1017100'>to</span>
  <span m='1017250'>preserve</span> <span m='1019240'>those</span> <span m='1019550'>numbers</span>
  <span m='1019710'>at a</span> <span m='1019980'>certain</span> <span m='1020150'>ratio,</span>
  <span m='1020460'>at</span> <span m='1020770'>a</span> <span m='1020830'>log</span>
  <span m='1021030'>ratio.</span> </p><p><span m='1021910'>And</span> <span m='1022110'>what</span>
  <span m='1022290'>that</span> <span m='1022500'>effectively</span> <span m='1022980'>means,</span>
  <span m='1024670'>is</span> <span m='1024880'>that</span> <span m='1025800'>the</span>
  <span m='1026069'>number</span> <span m='1026400'>of</span> <span m='1026490'>times</span>
  <span m='1026849'>that</span> <span m='1026970'>I</span> <span m='1027089'>have</span>
  <span m='1027270'>been--</span> <span m='1028200'>if</span> <span m='1028530'>I</span>
  <span m='1028619'>have been</span> <span m='1028880'>visited</span> <span m='1029220'>relatively</span>
  <span m='1029609'>few</span> <span m='1029790'>times,</span> <span m='1030490'>and</span>
  <span m='1030770'>the</span> <span m='1032260'>denominator</span> <span m='1032970'>is</span>
  <span m='1033270'>small.</span> <span m='1034180'>Whereas</span> <span m='1034560'>my</span>
  <span m='1035359'>parent</span> <span m='1035649'>has been</span> <span m='1035940'>visited</span>
  <span m='1036170'>many</span> <span m='1036369'>times,</span> <span m='1036609'>which</span>
  <span m='1036740'>means</span> <span m='1036890'>that</span> <span m='1037000'>my</span>
  <span m='1037170'>siblings</span> <span m='1037640'>have gotten</span> <span m='1037849'>much</span>
  <span m='1038069'>more</span> <span m='1038190'>attention,</span> <span m='1039040'>then</span>
  <span m='1039619'>the</span> <span m='1039890'>likelihood</span> <span m='1040450'>that</span>
  <span m='1040810'>I</span> <span m='1041060'>will</span> <span m='1041170'>be</span>
  <span m='1041440'>visited</span> <span m='1041730'>again</span> <span m='1042780'>actually</span>
  <span m='1043140'>increases.</span> <span m='1044380'>So</span> <span m='1045290'>this</span>
  <span m='1045560'>is</span> <span m='1045660'>biased</span> <span m='1046619'>on</span>
  <span m='1046800'>the one</span> <span m='1047099'>hand,</span> <span m='1047480'>towards</span>
  <span m='1048339'>nodes that</span> <span m='1048650'>are</span> <span m='1048720'>really</span>
  <span m='1048970'>promising,</span> <span m='1049450'>and</span> <span m='1049765'>on</span>
  <span m='1050080'>the</span> <span m='1050190'>other</span> <span m='1050520'>hand,</span>
  <span m='1051480'>towards</span> <span m='1051900'>nodes</span> <span m='1052200'>that</span>
  <span m='1052320'>haven't</span> <span m='1052650'>been</span> <span m='1052770'>explored</span>
  <span m='1053190'>yet,</span> <span m='1053445'>where</span> <span m='1053700'>there's</span>
  <span m='1053850'>a</span> <span m='1053910'>gold</span> <span m='1054240'>mine</span>
  <span m='1054680'>and all</span> <span m='1054930'>you need to do</span> <span m='1055250'>is</span>
  <span m='1055410'>dig a</span> <span m='1055805'>little bit,</span> <span m='1056200'>potentially.</span>
  </p><p><span m='1059650'>We</span> <span m='1059750'>don't</span> <span m='1059880'>actually</span>
  <span m='1060130'>have</span> <span m='1060400'>an</span> <span m='1060755'>analytical</span>
  <span m='1061110'>expression</span> <span m='1061210'>for</span> <span m='1061540'>this.</span>
  <span m='1062300'>But</span> <span m='1063380'>we</span> <span m='1063820'>can</span>
  <span m='1064020'>approximate</span> <span m='1064280'>it</span> <span m='1064540'>because</span>
  <span m='1065050'>you</span> <span m='1065140'>can</span> <span m='1065290'>think</span>
  <span m='1065560'>that</span> <span m='1065670'>the</span> <span m='1065750'>expected</span>
  <span m='1066250'>value</span> <span m='1067060'>from</span> <span m='1067210'>a</span>
  <span m='1067260'>certain</span> <span m='1067490'>node</span> <span m='1068150'>is,</span>
  <span m='1068660'>roughly</span> <span m='1068920'>speaking,</span> <span m='1069520'>approximately</span>
  <span m='1070540'>the</span> <span m='1070690'>ratio</span> <span m='1071230'>of</span>
  <span m='1071410'>wins</span> <span m='1071860'>at that</span> <span m='1072270'>node</span>
  <span m='1073090'>to</span> <span m='1073330'>the</span> <span m='1073390'>ratio</span>
  <span m='1073660'>of</span> <span m='1073730'>times</span> <span m='1074080'>that</span>
  <span m='1074290'>that node</span> <span m='1074480'>has been</span> <span m='1074690'>visit</span>
  <span m='1075030'>at</span> <span m='1075464'>all.</span> </p><p><span m='1079560'>Let's</span>
  <span m='1079770'>talk about</span> <span m='1080010'>actually</span> <span m='1080340'>applying</span>
  <span m='1081060'>this</span> <span m='1081240'>statement.</span> <span m='1081820'>Because</span>
  <span m='1082090'>what the</span> <span m='1082360'>statement is</span> <span m='1082620'>going</span>
  <span m='1082740'>to</span> <span m='1082800'>give</span> <span m='1082980'>you,</span>
  <span m='1083200'>is</span> <span m='1083440'>it's</span> <span m='1083640'>going</span>
  <span m='1083760'>to</span> <span m='1083820'>give</span> <span m='1084000'>you</span>
  <span m='1085400'>some</span> <span m='1085540'>number</span> <span m='1085860'>for
  here</span> <span m='1086130'>and</span> <span m='1086340'>some</span> <span m='1086400'>number</span>
  <span m='1086790'>here,</span> <span m='1086970'>and</span> <span m='1087110'>some</span>
  <span m='1087180'>number for</span> <span m='1087510'>here,</span> <span m='1087720'>and
  so on.</span> <span m='1089220'>When</span> <span m='1089370'>we</span> <span m='1089430'>start</span>
  <span m='1089680'>descending</span> <span m='1089800'>through</span> <span m='1090180'>the</span>
  <span m='1090300'>tree,</span> <span m='1090890'>we're going to start</span> <span
  m='1091180'>at</span> <span m='1091370'>the</span> <span m='1091490'>top</span>
  <span m='1091730'>node.</span> <span m='1092830'>And</span> <span m='1092880'>then</span>
  <span m='1093420'>we're</span> <span m='1093540'>going</span> <span m='1094110'>to</span>
  <span m='1094560'>look</span> <span m='1094950'>at</span> <span m='1095160'>the</span>
  <span m='1095280'>three</span> <span m='1095520'>children</span> <span m='1095940'>of
  that</span> <span m='1096120'>node.</span> <span m='1097500'>And</span> <span m='1097650'>we're</span>
  <span m='1097740'>going</span> <span m='1097860'>to</span> <span m='1097920'>compute</span>
  <span m='1098610'>this</span> <span m='1098850'>UCB</span> <span m='1099290'>value</span>
  <span m='1099630'>for</span> <span m='1099840'>each</span> <span m='1100050'>of</span>
  <span m='1100110'>these</span> <span m='1100290'>children</span> <span m='1101090'>and</span>
  <span m='1101340'>pick</span> <span m='1101560'>whichever</span> <span m='1102210'>one</span>
  <span m='1102330'>is</span> <span m='1102420'>the</span> <span m='1102480'>highest.</span>
  </p><p><span m='1103780'>So</span> <span m='1104400'>just</span> <span m='1104580'>as</span>
  <span m='1104730'>a</span> <span m='1106480'>thought</span> <span m='1106790'>for</span>
  <span m='1107220'>a moment,</span> <span m='1107650'>what</span> <span m='1107700'>if</span>
  <span m='1107820'>we</span> <span m='1107940'>ignore</span> <span m='1108270'>this</span>
  <span m='1108450'>one?</span> <span m='1108850'>And what</span> <span m='1108890'>if</span>
  <span m='1109060'>we're</span> <span m='1109170'>just</span> <span m='1109640'>computing</span>
  <span m='1110040'>the UCB</span> <span m='1110280'>of</span> <span m='1110370'>these</span>
  <span m='1110610'>two?</span> <span m='1111600'>Does</span> <span m='1111750'>anyone</span>
  <span m='1112080'>have</span> <span m='1112530'>any</span> <span m='1112710'>intuition</span>
  <span m='1113700'>on</span> <span m='1114360'>whether</span> <span m='1114660'>the</span>
  <span m='1114780'>UCB</span> <span m='1115770'>would</span> <span m='1115890'>be</span>
  <span m='1116160'>higher</span> <span m='1116910'>for</span> <span m='1117060'>this</span>
  <span m='1117290'>node</span> <span m='1117750'>or</span> <span m='1118196'>for
  this</span> <span m='1118642'>node?</span> </p><p><span m='1119088'>AUDIENCE:</span>
  <span m='1119311'>The</span> <span m='1119534'>left node.</span> </p><p><span m='1120430'>PROFESSOR
  3:</span> <span m='1120570'>The</span> <span m='1120900'>left</span> <span m='1121323'>node?</span>
  <span m='1122170'>OK.</span> <span m='1123040'>So</span> <span m='1123240'>why</span>
  <span m='1123450'>is</span> <span m='1123570'>that?</span> </p><p><span m='1124270'>AUDIENCE:</span>
  <span m='1124515'>It has</span> <span m='1124760'>a</span> <span m='1125250'>win</span>
  <span m='1125740'>[INAUDIBLE]</span> </p><p><span m='1126720'>PROFESSOR 3:</span>
  <span m='1126965'>Yeah.</span> <span m='1127210'>It</span> <span m='1127280'>has</span>
  <span m='1127440'>a</span> <span m='1127480'>win.</span> </p><p><span m='1128088'>AUDIENCE:</span>
  <span m='1128230'>And</span> <span m='1128372'>they</span> <span m='1128516'>both</span>
  <span m='1128944'>have a</span> <span m='1129372'>[INAUDIBLE].</span> </p><p><span
  m='1129800'>PROFESSOR 3:</span> <span m='1130040'>Exactly.</span> <span m='1130510'>And</span>
  <span m='1130580'>so</span> <span m='1130790'>clearly,</span> <span m='1131045'>you</span>
  <span m='1131300'>think</span> <span m='1131610'>the</span> <span m='1131910'>exploration</span>
  <span m='1132270'>term</span> <span m='1132490'>is</span> <span m='1132720'>the</span>
  <span m='1132850'>same</span> <span m='1133540'>because</span> <span m='1133770'>you</span>
  <span m='1133850'>know</span> <span m='1133940'>it's</span> <span m='1134060'>not</span>
  <span m='1134240'>that</span> <span m='1134330'>one</span> <span m='1134540'>child</span>
  <span m='1134820'>has been</span> <span m='1135100'>loved</span> <span m='1135280'>less</span>
  <span m='1135420'>than</span> <span m='1135530'>the</span> <span m='1135620'>other,</span>
  <span m='1136190'>but</span> <span m='1136670'>the</span> <span m='1136850'>expansion</span>
  <span m='1137330'>term</span> <span m='1137950'>is</span> <span m='1138110'>going</span>
  <span m='1138470'>to</span> <span m='1138980'>be</span> <span m='1139070'>different.</span>
  <span m='1139430'>And so</span> <span m='1139920'>it's</span> <span m='1140410'>definitely
  going to</span> <span m='1140900'>pick this</span> <span m='1141090'>one.</span>
  <span m='1141320'>In</span> <span m='1141410'>this</span> <span m='1141560'>case,</span>
  <span m='1142320'>what</span> <span m='1142370'>we're</span> <span m='1142460'>going</span>
  <span m='1142580'>to</span> <span m='1142640'>say</span> <span m='1142850'>is</span>
  <span m='1142970'>actually</span> <span m='1143510'>that</span> <span m='1143630'>this</span>
  <span m='1143810'>is</span> <span m='1143870'>so</span> <span m='1144110'>much</span>
  <span m='1144230'>more</span> <span m='1144380'>promising</span> <span m='1144770'>than</span>
  <span m='1144860'>the</span> <span m='1144950'>others</span> <span m='1145460'>that</span>
  <span m='1145630'>it's</span> <span m='1145940'>actually</span> <span m='1146180'>going</span>
  <span m='1146360'>to</span> <span m='1146420'>pick</span> <span m='1147010'>this</span>
  <span m='1147200'>left</span> <span m='1147390'>node.</span> </p><p><span m='1147885'>And
  so</span> <span m='1148380'>it's</span> <span m='1148610'>going to expand, and it's</span>
  <span m='1148800'>going</span> <span m='1148960'>to</span> <span m='1149210'>look</span>
  <span m='1149440'>down.</span> <span m='1150290'>And</span> <span m='1150430'>then
  when it</span> <span m='1150680'>looks</span> <span m='1150920'>down,</span> <span
  m='1151280'>it's</span> <span m='1151460'>going to compare</span> <span m='1151950'>between
  these</span> <span m='1152190'>two.</span> <span m='1153150'>And</span> <span m='1153770'>this</span>
  <span m='1153950'>time,</span> <span m='1154340'>remember,</span> <span m='1155230'>that</span>
  <span m='1155360'>this</span> <span m='1155510'>is</span> <span m='1155700'>a</span>
  <span m='1155920'>parent.</span> <span m='1157290'>A</span> <span m='1157730'>parent</span>
  <span m='1158090'>want to</span> <span m='1158210'>minimize</span> <span m='1159260'>the</span>
  <span m='1159380'>number</span> <span m='1159680'>of</span> <span m='1159800'>wins</span>
  <span m='1160540'>that</span> <span m='1160760'>we</span> <span m='1161000'>have.</span>
  <span m='1162590'>Which</span> <span m='1162800'>means</span> <span m='1163490'>that</span>
  <span m='1163750'>our</span> <span m='1163910'>opponent is</span> <span m='1164120'>going</span>
  <span m='1164250'>to</span> <span m='1164540'>want</span> <span m='1165240'>to</span>
  <span m='1166500'>pick</span> <span m='1166970'>the</span> <span m='1167090'>one</span>
  <span m='1167450'>that</span> <span m='1167600'>were</span> <span m='1167820'>less</span>
  <span m='1168090'>likely</span> <span m='1168950'>to</span> <span m='1169460'>win</span>
  <span m='1169720'>in</span> <span m='1169980'>and</span> <span m='1170090'>they're</span>
  <span m='1170320'>more</span> <span m='1170650'>likely to</span> <span m='1171003'>win</span>
  <span m='1171356'>in.</span> <span m='1171710'>This</span> <span m='1171860'>is</span>
  <span m='1171960'>the</span> <span m='1172130'>idea</span> <span m='1172350'>of</span>
  <span m='1172470'>mini-max,</span> <span m='1172940'>minimizing</span> <span m='1173910'>how</span>
  <span m='1174070'>well</span> <span m='1174570'>my</span> <span m='1174770'>enemy</span>
  <span m='1175160'>does</span> <span m='1175400'>in this game.</span> </p><p><span
  m='1180190'>Although</span> <span m='1180860'>again, the</span> <span m='1181240'>expiration</span>
  <span m='1181720'>term</span> <span m='1181910'>might</span> <span m='1182060'>counterbalance</span>
  <span m='1182330'>it a little</span> <span m='1182580'>bit</span> <span m='1183500'>because,</span>
  <span m='1184610'>technically,</span> <span m='1184720'>this has</span> <span m='1185150'>been</span>
  <span m='1185290'>explored</span> <span m='1185570'>more.</span> <span m='1188190'>We're</span>
  <span m='1188300'>going</span> <span m='1188450'>to</span> <span m='1188570'>pick
  the</span> <span m='1188750'>one on</span> <span m='1188840'>the</span> <span m='1188900'>left</span>
  <span m='1189140'>again.</span> <span m='1189940'>And</span> <span m='1190100'>we're</span>
  <span m='1190190'>going</span> <span m='1190310'>to</span> <span m='1190370'>get</span>
  <span m='1190550'>to</span> <span m='1191090'>that</span> <span m='1191300'>location</span>
  <span m='1191700'>that</span> <span m='1191770'>we</span> <span m='1191850'>got</span>
  <span m='1192050'>to</span> <span m='1192110'>originally.</span> </p><p><span m='1194480'>Now</span>
  <span m='1195920'>when</span> <span m='1196100'>we're</span> <span m='1196250'>comparing</span>
  <span m='1196670'>between</span> <span m='1197060'>these</span> <span m='1197330'>two,</span>
  <span m='1197750'>between</span> <span m='1197900'>a node</span> <span m='1198110'>that</span>
  <span m='1198310'>has</span> <span m='1198470'>been</span> <span m='1198680'>visited</span>
  <span m='1199080'>once</span> <span m='1199920'>and a</span> <span m='1200260'>node
  that has</span> <span m='1200420'>never</span> <span m='1200630'>been</span> <span
  m='1200800'>visited,</span> <span m='1201520'>can</span> <span m='1201720'>anyone</span>
  <span m='1201950'>guess</span> <span m='1202700'>which</span> <span m='1202880'>one
  of these</span> <span m='1203080'>it is</span> <span m='1203250'>going</span> <span
  m='1203400'>to</span> <span m='1203860'>pick?</span> <span m='1206160'>Yeah.</span>
  </p><p><span m='1206620'>AUDIENCE:</span> <span m='1206850'>Never</span> <span m='1207080'>has
  been</span> <span m='1207540'>visited.</span> </p><p><span m='1208470'>PROFESSOR
  3:</span> <span m='1208660'>Yeah,</span> <span m='1208850'>exactly.</span> <span
  m='1209310'>Because</span> <span m='1210150'>this</span> <span m='1210360'>number</span>
  <span m='1210750'>is</span> <span m='1210880'>zero.</span> <span m='1211690'>And</span>
  <span m='1211850'>so</span> <span m='1212580'>if</span> <span m='1212860'>the</span>
  <span m='1213030'>parent</span> <span m='1213300'>has</span> <span m='1213650'>ever
  been visited</span> <span m='1214260'>but</span> <span m='1214380'>the</span> <span
  m='1214660'>node</span> <span m='1215130'>hasn't,</span> <span m='1215380'>this</span>
  <span m='1215790'>is going</span> <span m='1216200'>to be</span> <span m='1216340'>infinite
  and</span> <span m='1216730'>it's</span> <span m='1216860'>going</span> <span m='1217010'>to</span>
  <span m='1217080'>have</span> <span m='1217330'>to</span> <span m='1217460'>pick</span>
  <span m='1217700'>the</span> <span m='1217840'>node</span> <span m='1218115'>that
  it</span> <span m='1218390'>has</span> <span m='1218550'>never</span> <span m='1218760'>seen</span>
  <span m='1219223'>before.</span> <span m='1220560'>So</span> <span m='1220680'>that's</span>
  <span m='1220860'>how</span> <span m='1221010'>we</span> <span m='1221200'>descend</span>
  <span m='1221430'>through</span> <span m='1221640'>the</span> <span m='1221840'>tree.</span>
  </p><p><span m='1222262'>Does</span> <span m='1222684'>anyone</span> <span m='1223106'>have
  any</span> <span m='1223530'>questions on that.</span> <span m='1223870'>Really,
  it's totally</span> <span m='1224250'>fine.</span> <span m='1225070'>We're</span>
  <span m='1225360'>going</span> <span m='1225460'>to be</span> <span m='1225560'>talking</span>
  <span m='1225780'>about</span> <span m='1225920'>this</span> <span m='1226300'>for</span>
  <span m='1226680'>a while.</span> <span m='1227440'>Yeah.</span> </p><p><span m='1228056'>AUDIENCE:</span>
  <span m='1228214'>With</span> <span m='1228372'>the</span> <span m='1228532'>left</span>
  <span m='1229010'>node</span> <span m='1229330'>that</span> <span m='1229660'>has
  the</span> <span m='1229990'>four</span> <span m='1230350'>for</span> <span m='1230540'>n
  sub k,</span> <span m='1231287'>wouldn't</span> <span m='1232450'>that</span> <span
  m='1233230'>be</span> <span m='1233670'>three</span> <span m='1234110'>because</span>
  <span m='1234550'>there's</span> <span m='1234990'>two</span> <span m='1235170'>and</span>
  <span m='1235280'>one</span> <span m='1235550'>below?</span> </p><p><span m='1236620'>PROFESSOR
  3:</span> <span m='1236725'>No</span> <span m='1237190'>because</span> <span m='1237460'>of</span>
  <span m='1237530'>the</span> <span m='1237610'>way</span> <span m='1237760'>that</span>
  <span m='1238020'>we're</span> <span m='1238110'>going</span> <span m='1238190'>to
  be</span> <span m='1238570'>updating</span> <span m='1238870'>the tree.</span> <span
  m='1239160'>Next, we'll</span> <span m='1239570'>talk about some</span> <span m='1240050'>[INAUDIBLE].</span>
  </p><p><span m='1241490'>AUDIENCE:</span> <span m='1241545'>I</span> <span m='1241600'>like</span>
  <span m='1241810'>the</span> <span m='1241900'>concept.</span> <span m='1242290'>But</span>
  <span m='1242595'>if it's</span> <span m='1242900'>a</span> <span m='1243060'>deterministic</span>
  <span m='1243310'>game,</span> <span m='1243560'>why</span> <span m='1243760'>couldn't</span>
  <span m='1244251'>it</span> <span m='1244742'>hold it's</span> <span m='1245233'>[INAUDIBLE]</span>
  <span m='1245724'>pretty strictly?</span> </p><p><span m='1246710'>PROFESSOR 3:</span>
  <span m='1246840'>That's</span> <span m='1246970'>a great</span> <span m='1247080'>question.</span>
  <span m='1248040'>That's</span> <span m='1248340'>really</span> <span m='1248700'>up</span>
  <span m='1248850'>to</span> <span m='1249060'>computer</span> <span m='1249540'>memory</span>
  <span m='1249720'>limits.</span> <span m='1250606'>As</span> <span m='1251050'>I</span>
  <span m='1251150'>think</span> <span m='1251340'>that</span> <span m='1251480'>Leah</span>
  <span m='1251857'>mentioned,</span> <span m='1252990'>the</span> <span m='1253500'>number</span>
  <span m='1253800'>of</span> <span m='1253860'>stakes</span> <span m='1254280'>in</span>
  <span m='1254420'>the</span> <span m='1254490'>game</span> <span m='1254800'>of</span>
  <span m='1254850'>Go--</span> <span m='1256050'>it's</span> <span m='1256260'>a</span>
  <span m='1256450'>19 by</span> <span m='1256815'>19</span> <span m='1257180'>board,</span>
  <span m='1257360'>and you can</span> <span m='1257645'>play</span> <span m='1257740'>something</span>
  <span m='1257835'>at</span> <span m='1257930'>every</span> <span m='1258260'>state.</span>
  <span m='1258500'>It's</span> <span m='1258942'>only</span> <span m='1259384'>like</span>
  <span m='1259826'>2</span> <span m='1260048'>to</span> <span m='1260270'>the--</span>
  </p><p><span m='1260690'>PROFESSOR 2:</span> <span m='1260920'>[INAUDIBLE]</span>
  </p><p><span m='1261150'>PROFESSOR 3:</span> <span m='1261245'>What?</span> </p><p><span
  m='1261340'>PROFESSOR 2:</span> <span m='1261550'>250.</span> </p><p><span m='1261760'>PROFESSOR
  3:</span> <span m='1261970'>250.</span> <span m='1264460'>You</span> <span m='1264690'>could</span>
  <span m='1264870'>never</span> <span m='1265210'>explore</span> <span m='1265710'>the</span>
  <span m='1265830'>entire</span> <span m='1266180'>search</span> <span m='1266590'>tree.</span>
  </p><p><span m='1267000'>AUDIENCE:</span> <span m='1267155'>[INAUDIBLE]</span> <span
  m='1267777'>over the</span> <span m='1268244'>first few</span> <span m='1268711'>layers</span>
  <span m='1269180'>or</span> <span m='1269290'>are</span> <span m='1269750'>we</span>
  <span m='1270210'>going</span> <span m='1270450'>polite.</span> <span m='1272010'>We</span>
  <span m='1272120'>try</span> <span m='1272360'>to</span> <span m='1272480'>do</span>
  <span m='1272720'>this</span> <span m='1273100'>real</span> <span m='1273480'>time</span>
  <span m='1273860'>where you</span> <span m='1274240'>could</span> <span m='1274340'>have
  done</span> <span m='1274805'>something</span> <span m='1275270'>offline.</span>
  </p><p><span m='1275710'>PROFESSOR 3:</span> <span m='1275745'>It's</span> <span
  m='1275780'>definitely</span> <span m='1276055'>true.</span> <span m='1277330'>If
  you</span> <span m='1277540'>know a</span> <span m='1277810'>state that</span> <span
  m='1278230'>you're</span> <span m='1278280'>going</span> <span m='1278440'>to</span>
  <span m='1278510'>arrive at</span> <span m='1278960'>ahead</span> <span m='1279110'>of
  time,</span> <span m='1279490'>then</span> <span m='1279870'>you</span> <span m='1280080'>can
  totally do</span> <span m='1280230'>that.</span> <span m='1280640'>But</span> <span
  m='1280850'>in a game</span> <span m='1281090'>that's</span> <span m='1281490'>large</span>
  <span m='1281760'>enough</span> <span m='1282420'>that</span> <span m='1283800'>to
  do</span> <span m='1283890'>that</span> <span m='1284100'>for</span> <span m='1284250'>all</span>
  <span m='1284490'>the</span> <span m='1284610'>possible</span> <span m='1284800'>states</span>
  <span m='1285660'>would</span> <span m='1285840'>take</span> <span m='1286110'>that
  much more</span> <span m='1286590'>time</span> <span m='1286860'>and</span> <span
  m='1286990'>take that</span> <span m='1287160'>much more</span> <span m='1287455'>memory.</span>
  <span m='1289050'>It</span> <span m='1289270'>doesn't</span> <span m='1289570'>end</span>
  <span m='1289970'>up making</span> <span m='1290280'>that</span> <span m='1290430'>much</span>
  <span m='1290520'>sense.</span> </p><p><span m='1290970'>Also,</span> <span m='1291420'>something</span>
  <span m='1291600'>to</span> <span m='1291690'>point</span> <span m='1291930'>out</span>
  <span m='1292050'>here,</span> <span m='1292550'>is</span> <span m='1292650'>that</span>
  <span m='1292740'>for</span> <span m='1292890'>most</span> <span m='1293130'>of</span>
  <span m='1293190'>the</span> <span m='1293250'>games</span> <span m='1293430'>that</span>
  <span m='1293520'>we're</span> <span m='1293580'>talking</span> <span m='1293890'>about,</span>
  <span m='1294330'>simulating</span> <span m='1294880'>a</span> <span m='1294990'>run</span>
  <span m='1295350'>through</span> <span m='1295590'>of</span> <span m='1295720'>the</span>
  <span m='1295830'>game</span> <span m='1296435'>is</span> <span m='1296790'>really</span>
  <span m='1297210'>fast.</span> <span m='1298730'>So</span> <span m='1298920'>if</span>
  <span m='1299040'>you</span> <span m='1299100'>think</span> <span m='1299310'>about</span>
  <span m='1299510'>it--</span> <span m='1300460'>let's</span> <span m='1300600'>actually</span>
  <span m='1300970'>get</span> <span m='1301080'>to</span> <span m='1301350'>that</span>
  <span m='1301975'>in</span> <span m='1302430'>next</span> <span m='1302660'>piece.</span>
  <span m='1303170'>But</span> <span m='1303260'>the</span> <span m='1303360'>point</span>
  <span m='1303540'>is</span> <span m='1303750'>that</span> <span m='1304285'>building</span>
  <span m='1304660'>up</span> <span m='1304890'>this</span> <span m='1305160'>many</span>
  <span m='1305430'>levels</span> <span m='1305695'>of a tree for a</span> <span m='1305960'>computer</span>
  <span m='1306885'>takes</span> <span m='1307260'>probably</span> <span m='1307680'>on</span>
  <span m='1307800'>the</span> <span m='1307890'>order</span> <span m='1308250'>of</span>
  <span m='1308400'>less</span> <span m='1308640'>than</span> <span m='1308790'>millisecond.</span>
  <span m='1310780'>So</span> <span m='1310950'>doing</span> <span m='1311220'>this</span>
  <span m='1311540'>for a</span> <span m='1311760'>really,</span> <span m='1312300'>really</span>
  <span m='1312480'>huge</span> <span m='1312810'>tree,</span> <span m='1315410'>it's</span>
  <span m='1315600'>peanuts</span> <span m='1316470'>because</span> <span m='1316650'>their</span>
  <span m='1317190'>such</span> <span m='1317310'>simple</span> <span m='1317590'>operations.</span>
  <span m='1318650'>But</span> <span m='1318810'>it</span> <span m='1318980'>won't</span>
  <span m='1319150'>get</span> <span m='1319320'>expensive</span> <span m='1319830'>when</span>
  <span m='1319980'>we</span> <span m='1320070'>start</span> <span m='1320260'>building</span>
  <span m='1320560'>up</span> <span m='1320670'>the</span> <span m='1320730'>tree</span>
  <span m='1321060'>to</span> <span m='1321620'>serious</span> <span m='1322020'>depths.</span>
  </p><p><span m='1324650'>AUDIENCE:</span> <span m='1324692'>But</span> <span m='1324734'>a</span>
  <span m='1324776'>game</span> <span m='1324818'>like</span> <span m='1324860'>Go,</span>
  <span m='1325360'>how</span> <span m='1325410'>many</span> <span m='1325740'>nodes</span>
  <span m='1326130'>would</span> <span m='1326560'>you</span> <span m='1326700'>have?</span>
  </p><p><span m='1328620'>PROFESSOR 3:</span> <span m='1328695'>On</span> <span m='1328770'>each</span>
  <span m='1328980'>level,</span> <span m='1329550'>in</span> <span m='1329640'>the</span>
  <span m='1329730'>beginning,</span> <span m='1330300'>we</span> <span m='1330450'>have</span>
  <span m='1330600'>something</span> <span m='1331020'>on the order of</span> <span
  m='1331350'>400</span> <span m='1331850'>nodes.</span> <span m='1332280'>And we</span>
  <span m='1332440'>have</span> <span m='1332580'>a depth</span> <span m='1332940'>of
  about,</span> <span m='1333240'>I</span> <span m='1333686'>think</span> <span m='1334580'>most
  games</span> <span m='1334910'>have</span> <span m='1335000'>up to</span> <span
  m='1335390'>250</span> <span m='1336300'>steps,</span> <span m='1336620'>or something
  like</span> <span m='1336996'>that.</span> </p><p><span m='1337750'>AUDIENCE:</span>
  <span m='1337800'>So</span> <span m='1338090'>just</span> <span m='1338540'>to</span>
  <span m='1338940'>build,</span> <span m='1339060'>if you go</span> <span m='1339210'>in</span>
  <span m='1339330'>there</span> <span m='1339510'>blank,</span> <span m='1339750'>without</span>
  <span m='1340020'>any</span> <span m='1340370'>nodes</span> <span m='1340620'>built,</span>
  <span m='1340880'>you have</span> <span m='1341270'>to in</span> <span m='1341660'>the
  computer,</span> <span m='1341950'>like you</span> <span m='1342392'>said,</span>
  <span m='1342834'>it hasn't</span> <span m='1343276'>visited a</span> <span m='1343718'>node,
  it</span> <span m='1344160'>has to go there</span> <span m='1344602'>before</span>
  <span m='1345050'>it descends</span> <span m='1345310'>further.</span> <span m='1346450'>Basically,</span>
  <span m='1346896'>like</span> <span m='1347342'>breadth</span> <span m='1347790'>first.</span>
  </p><p><span m='1348210'>PROFESSOR 3:</span> <span m='1348375'>It's</span> <span
  m='1348540'>sort</span> <span m='1348870'>of</span> <span m='1348960'>like</span>
  <span m='1349190'>breadth</span> <span m='1349450'>first but</span> <span m='1349710'>not</span>
  <span m='1349980'>quite.</span> <span m='1350240'>There's</span> <span m='1350370'>an
  important</span> <span m='1350590'>distinction here,</span> <span m='1351600'>which</span>
  <span m='1351730'>is</span> <span m='1352890'>that</span> <span m='1353275'>it</span>
  <span m='1353550'>doesn't</span> <span m='1353880'>have</span> <span m='1354060'>to</span>
  <span m='1354150'>build</span> <span m='1354320'>up</span> <span m='1354540'>this</span>
  <span m='1355060'>or</span> <span m='1355250'>this</span> <span m='1355510'>node.</span>
  <span m='1357760'>It doesn't</span> <span m='1357910'>have</span> <span m='1358000'>to</span>
  <span m='1358110'>build</span> <span m='1358320'>up</span> <span m='1358470'>all</span>
  <span m='1358710'>of</span> <span m='1358820'>the</span> <span m='1358880'>nodes</span>
  <span m='1359220'>at</span> <span m='1359310'>a</span> <span m='1359340'>certain</span>
  <span m='1359640'>level.</span> <span m='1360430'>All</span> <span m='1360540'>it
  has to</span> <span m='1360780'>do</span> <span m='1361375'>is,</span> <span m='1361640'>if</span>
  <span m='1361760'>it</span> <span m='1362010'>branches</span> <span m='1362460'>down</span>
  <span m='1363420'>to</span> <span m='1363840'>a</span> <span m='1363950'>certain</span>
  <span m='1364600'>sub region,</span> <span m='1365640'>then</span> <span m='1365850'>can't</span>
  <span m='1366270'>descend</span> <span m='1367110'>in</span> <span m='1367260'>that</span>
  <span m='1367390'>sub region</span> <span m='1368050'>below</span> <span m='1368590'>one
  of</span> <span m='1369090'>its</span> <span m='1369270'>siblings</span> <span m='1369910'>without</span>
  <span m='1370150'>having</span> <span m='1370400'>at</span> <span m='1370500'>least</span>
  <span m='1370800'>looked</span> <span m='1371160'>once</span> <span m='1371600'>at</span>
  <span m='1371690'>all</span> <span m='1371810'>its</span> <span m='1371900'>siblings.</span>
  <span m='1372410'>After</span> <span m='1372710'>it</span> <span m='1372920'>looks</span>
  <span m='1373200'>once</span> <span m='1373410'>it</span> <span m='1373470'>can</span>
  <span m='1373650'>do</span> <span m='1374220'>whatever</span> <span m='1374490'>it</span>
  <span m='1374550'>wants.</span> </p><p><span m='1375190'>And</span> <span m='1375250'>the</span>
  <span m='1375330'>point</span> <span m='1375570'>is,</span> <span m='1375960'>that</span>
  <span m='1376500'>it</span> <span m='1376800'>doesn't</span> <span m='1377130'>mean</span>
  <span m='1377440'>the</span> <span m='1377880'>tree has to</span> <span m='1378210'>be
  kept</span> <span m='1378620'>at an even</span> <span m='1379030'>level.</span>
  <span m='1379440'>All</span> <span m='1379610'>it</span> <span m='1379680'>means</span>
  <span m='1380040'>is</span> <span m='1380220'>that</span> <span m='1380340'>the</span>
  <span m='1380430'>tree,</span> <span m='1382380'>in</span> <span m='1382530'>order</span>
  <span m='1382740'>to</span> <span m='1382830'>descend</span> <span m='1383200'>on</span>
  <span m='1383250'>a</span> <span m='1383310'>specific</span> <span m='1383700'>part</span>
  <span m='1383880'>of</span> <span m='1383940'>the</span> <span m='1384000'>tree,</span>
  <span m='1384300'>it</span> <span m='1384700'>has</span> <span m='1384970'>to have</span>
  <span m='1385240'>at least</span> <span m='1385620'>visited</span> <span m='1386280'>direct</span>
  <span m='1386730'>neighbors</span> <span m='1388060'>once</span> <span m='1388180'>before.</span>
  <span m='1390220'>Any more</span> <span m='1390530'>questions</span> <span m='1390720'>on
  this</span> <span m='1391170'>before--</span> <span m='1392400'>Yeah.</span> </p><p><span
  m='1392940'>AUDIENCE:</span> <span m='1393095'>What's</span> <span m='1393250'>the</span>
  <span m='1393570'>advantage</span> <span m='1394050'>necessarily</span> <span m='1394850'>of</span>
  <span m='1395080'>having</span> <span m='1395390'>to visit</span> <span m='1395853'>every
  single?</span> </p><p><span m='1402220'>PROFESSOR 3:</span> <span m='1402435'>The</span>
  <span m='1402650'>advantage</span> <span m='1403080'>of</span> <span m='1403240'>having</span>
  <span m='1403320'>to</span> <span m='1403730'>visit</span> <span m='1403950'>every</span>
  <span m='1404090'>single--</span> <span m='1404510'>the</span> <span m='1404600'>way</span>
  <span m='1404750'>that</span> <span m='1404870'>I</span> <span m='1404960'>think</span>
  <span m='1405240'>of</span> <span m='1405400'>it,</span> <span m='1405740'>is</span>
  <span m='1405950'>that</span> <span m='1406280'>you</span> <span m='1406580'>don't</span>
  <span m='1406910'>want</span> <span m='1407150'>to</span> <span m='1407210'>be</span>
  <span m='1407330'>missing</span> <span m='1407720'>out</span> <span m='1408470'>on</span>
  <span m='1409250'>potentially</span> <span m='1410810'>being</span> <span m='1411080'>interested</span>
  <span m='1411590'>in</span> <span m='1412040'>some</span> <span m='1412250'>of the</span>
  <span m='1412550'>things</span> <span m='1412860'>and</span> <span m='1412980'>not</span>
  <span m='1414140'>others.</span> <span m='1415380'>It</span> <span m='1415790'>comes</span>
  <span m='1416030'>back</span> <span m='1416270'>to</span> <span m='1416390'>the</span>
  <span m='1416570'>exploration</span> <span m='1418670'>versus</span> <span m='1419270'>expectation</span>
  <span m='1420170'>distinction.</span> <span m='1421690'>We</span> <span m='1423080'>do</span>
  <span m='1423650'>want</span> <span m='1423950'>to</span> <span m='1424360'>descend</span>
  <span m='1424840'>into</span> <span m='1425030'>the</span> <span m='1425150'>region</span>
  <span m='1425360'>of</span> <span m='1425420'>the</span> <span m='1425540'>tree</span>
  <span m='1425800'>that</span> <span m='1426050'>is</span> <span m='1426300'>really</span>
  <span m='1426350'>valuable to</span> <span m='1426630'>us.</span> <span m='1427200'>But</span>
  <span m='1428450'>at</span> <span m='1428540'>least</span> <span m='1428780'>have</span>
  <span m='1428980'>explored</span> <span m='1429380'>a</span> <span m='1429410'>little</span>
  <span m='1429710'>bit,</span> <span m='1430280'>at</span> <span m='1430340'>least</span>
  <span m='1430520'>maintaining</span> <span m='1430940'>some</span> <span m='1431160'>baseline,</span>
  <span m='1431760'>which</span> <span m='1431780'>really</span> <span m='1432080'>isn't</span>
  <span m='1432980'>that</span> <span m='1433190'>costly</span> <span m='1433550'>compared</span>
  <span m='1433820'>to</span> <span m='1433880'>the</span> <span m='1433970'>size</span>
  <span m='1434150'>of</span> <span m='1434210'>the</span> <span m='1434300'>tree.</span>
  <span m='1435120'>400</span> <span m='1435535'>moves</span> <span m='1435950'>is</span>
  <span m='1436100'>not</span> <span m='1436310'>that</span> <span m='1436460'>bad</span>
  <span m='1436700'>compared</span> <span m='1437442'>with</span> <span m='1437824'>400</span>
  <span m='1438206'>and</span> <span m='1438590'>250.</span> </p><p><span m='1439710'>AUDIENCE:</span>
  <span m='1439795'>Are</span> <span m='1439880'>these</span> <span m='1440100'>simulations,</span>
  <span m='1441030'>they're</span> <span m='1441110'>just</span> <span m='1441320'>random</span>
  <span m='1441680'>simulations?</span> </p><p><span m='1442180'>PROFESSOR 3:</span>
  <span m='1442430'>We're</span> <span m='1442680'>going to talk</span> <span m='1443065'>about
  that in a</span> <span m='1443450'>minute.</span> <span m='1443835'>Any more questions</span>
  <span m='1444220'>before I</span> <span m='1444560'>move onto</span> <span m='1444640'>that?</span>
  </p><p><span m='1448790'>Next</span> <span m='1449030'>step</span> <span m='1449210'>is</span>
  <span m='1449330'>expanding.</span> <span m='1450420'>And</span> <span m='1450440'>this</span>
  <span m='1450590'>is</span> <span m='1450680'>very</span> <span m='1450870'>simple.</span>
  <span m='1451280'>You just</span> <span m='1451510'>create</span> <span m='1451870'>a</span>
  <span m='1452343'>node</span> <span m='1453290'>and</span> <span m='1453890'>you</span>
  <span m='1454190'>set</span> <span m='1454540'>the</span> <span m='1454780'>two</span>
  <span m='1454930'>initial</span> <span m='1455420'>values.</span> <span m='1455910'>And
  the initial values</span> <span m='1456270'>are</span> <span m='1456920'>the</span>
  <span m='1456980'>number</span> <span m='1457160'>of</span> <span m='1457220'>times</span>
  <span m='1457460'>it's been visited</span> <span m='1457610'>is</span> <span m='1458070'>zero,</span>
  <span m='1458840'>and</span> <span m='1458930'>then</span> <span m='1459020'>number
  of</span> <span m='1459170'>times that</span> <span m='1459450'>someone</span> <span
  m='1459560'>has</span> <span m='1459710'>won</span> <span m='1460080'>from</span>
  <span m='1460310'>there</span> <span m='1460720'>is zero.</span> </p><p><span m='1461130'>AUDIENCE:</span>
  <span m='1461225'>[INAUDIBLE]</span> <span m='1463270'>So the</span> <span m='1463500'>easy</span>
  <span m='1463760'>part is</span> <span m='1463990'>solving</span> <span m='1464200'>it.</span>
  </p><p><span m='1465020'>PROFESSOR 3:</span> <span m='1465140'>Now,</span> <span
  m='1465260'>simulating.</span> <span m='1467180'>Simulating</span> <span m='1467860'>is</span>
  <span m='1468290'>really</span> <span m='1468620'>hard.</span> <span m='1469320'>You</span>
  <span m='1469420'>can</span> <span m='1469430'>imagine</span> <span m='1469850'>that</span>
  <span m='1470060'>if</span> <span m='1470150'>you</span> <span m='1470270'>get</span>
  <span m='1470450'>to a</span> <span m='1470570'>single</span> <span m='1470790'>node</span>
  <span m='1471470'>and</span> <span m='1471560'>you've</span> <span m='1471740'>never</span>
  <span m='1472190'>seen</span> <span m='1472490'>that</span> <span m='1472590'>node</span>
  <span m='1472790'>before,</span> <span m='1473480'>and</span> <span m='1473600'>you</span>
  <span m='1473720'>don't</span> <span m='1473960'>know</span> <span m='1474200'>what</span>
  <span m='1474320'>to</span> <span m='1474440'>do</span> <span m='1474800'>from</span>
  <span m='1475010'>this</span> <span m='1475150'>node</span> <span m='1475440'>onward,</span>
  <span m='1476270'>that</span> <span m='1476870'>if</span> <span m='1477500'>we</span>
  <span m='1477620'>knew</span> <span m='1477830'>how</span> <span m='1478040'>the</span>
  <span m='1478130'>game</span> <span m='1478330'>was</span> <span m='1478460'>going</span>
  <span m='1478640'>to</span> <span m='1478730'>play</span> <span m='1478970'>out,</span>
  <span m='1479600'>that</span> <span m='1479780'>is</span> <span m='1480070'>exactly</span>
  <span m='1480270'>what</span> <span m='1480450'>were</span> <span m='1480590'>searching</span>
  <span m='1480780'>for,</span> <span m='1481150'>and</span> <span m='1481250'>we</span>
  <span m='1481350'>would be</span> <span m='1481520'>done.</span> <span m='1482360'>But</span>
  <span m='1482570'>we</span> <span m='1482690'>don't.</span> <span m='1483320'>And</span>
  <span m='1483680'>in</span> <span m='1483800'>fact,</span> <span m='1484250'>we</span>
  <span m='1484350'>have</span> <span m='1484400'>no</span> <span m='1484760'>idea</span>
  <span m='1486200'>how</span> <span m='1486560'>to</span> <span m='1486710'>go</span>
  <span m='1486920'>about</span> <span m='1487330'>simulating</span> <span m='1487770'>a</span>
  <span m='1487970'>realistic</span> <span m='1488560'>game,</span> <span m='1489250'>and
  a game</span> <span m='1489580'>that</span> <span m='1489790'>will tell us</span>
  <span m='1489990'>something</span> <span m='1490280'>meaningful</span> <span m='1491110'>about</span>
  <span m='1491270'>the</span> <span m='1491390'>quality</span> <span m='1491990'>of</span>
  <span m='1492200'>a certain</span> <span m='1492600'>state.</span> </p><p><span
  m='1493410'>And</span> <span m='1493570'>so,</span> <span m='1494540'>as</span>
  <span m='1494690'>you</span> <span m='1494780'>correctly</span> <span m='1495110'>guessed,</span>
  <span m='1496180'>we're going to</span> <span m='1496400'>do it</span> <span m='1496730'>randomly.</span>
  <span m='1498560'>We're</span> <span m='1498830'>going</span> <span m='1499010'>to</span>
  <span m='1499150'>be at</span> <span m='1499370'>a certain</span> <span m='1499570'>state.</span>
  <span m='1500380'>And</span> <span m='1500540'>then</span> <span m='1500870'>from</span>
  <span m='1501200'>that</span> <span m='1501320'>state,</span> <span m='1501730'>we're</span>
  <span m='1501830'>just</span> <span m='1501960'>going</span> <span m='1502160'>to</span>
  <span m='1502260'>pick</span> <span m='1502540'>random</span> <span m='1502750'>nodes</span>
  <span m='1503330'>for</span> <span m='1503480'>each</span> <span m='1503660'>of</span>
  <span m='1503750'>the</span> <span m='1503840'>players</span> <span m='1504530'>until</span>
  <span m='1504830'>the</span> <span m='1504920'>game</span> <span m='1505130'>ends.</span>
  </p><p><span m='1507280'>And</span> <span m='1507600'>if</span> <span m='1508320'>we,</span>
  <span m='1508760'>as</span> <span m='1508960'>player</span> <span m='1509180'>one,</span>
  <span m='1509660'>win</span> <span m='1510200'>then</span> <span m='1510350'>we're</span>
  <span m='1510440'>going</span> <span m='1510560'>to</span> <span m='1510620'>add</span>
  <span m='1510800'>one.</span> <span m='1511990'>Then</span> <span m='1512270'>we're</span>
  <span m='1512330'>going</span> <span m='1512450'>to</span> <span m='1512510'>say</span>
  <span m='1512640'>delta</span> <span m='1512780'>equals</span> <span m='1512970'>plus</span>
  <span m='1513390'>one.</span> <span m='1513980'>And</span> <span m='1514130'>if</span>
  <span m='1514670'>we</span> <span m='1515510'>don't</span> <span m='1515750'>win,</span>
  <span m='1516260'>or</span> <span m='1517150'>if</span> <span m='1517240'>we</span>
  <span m='1517490'>tie</span> <span m='1517790'>or</span> <span m='1517880'>lose,</span>
  <span m='1518140'>then</span> <span m='1518400'>we're going</span> <span m='1518500'>to</span>
  <span m='1518750'>call it a</span> <span m='1518990'>zero.</span> </p><p><span m='1520460'>You</span>
  <span m='1520520'>can</span> <span m='1520610'>in this</span> <span m='1521035'>graph,</span>
  <span m='1521460'>we're</span> <span m='1521840'>descending</span> <span m='1522210'>randomly</span>
  <span m='1522420'>and</span> <span m='1522590'>not</span> <span m='1522760'>thinking</span>
  <span m='1522970'>about</span> <span m='1523260'>it.</span> <span m='1523510'>And
  it turns</span> <span m='1523980'>out that</span> <span m='1524450'>this</span>
  <span m='1524750'>is</span> <span m='1524840'>actually</span> <span m='1525080'>great</span>
  <span m='1525370'>because</span> <span m='1525610'>it's</span> <span m='1525790'>really,</span>
  <span m='1526200'>really</span> <span m='1526670'>computationally</span> <span m='1527140'>efficient.</span>
  <span m='1528570'>If</span> <span m='1528770'>you</span> <span m='1528920'>have</span>
  <span m='1529120'>a</span> <span m='1529160'>board,</span> <span m='1529520'>even
  if it</span> <span m='1529820'>has</span> <span m='1530030'>400</span> <span m='1530835'>open</span>
  <span m='1531100'>squares,</span> <span m='1531860'>populating</span> <span m='1532430'>it</span>
  <span m='1532620'>by</span> <span m='1532900'>a</span> <span m='1532970'>bunch</span>
  <span m='1533210'>of</span> <span m='1533300'>random</span> <span m='1533555'>moves</span>
  <span m='1533810'>doesn't</span> <span m='1534150'>take you</span> <span m='1534450'>very</span>
  <span m='1534620'>long,</span> <span m='1535270'>on</span> <span m='1535400'>the</span>
  <span m='1535530'>order</span> <span m='1535860'>of</span> <span m='1536300'>not</span>
  <span m='1536440'>that</span> <span m='1536735'>many</span> <span m='1537030'>machine
  can.</span> </p><p><span m='1538276'>AUDIENCE:</span> <span m='1538483'>That's</span>
  <span m='1538690'>why</span> <span m='1539060'>does</span> <span m='1539420'>you</span>
  <span m='1539800'>don't score--</span> <span m='1540390'>if you</span> <span m='1540760'>go
  down</span> <span m='1540990'>a</span> <span m='1541250'>tree</span> <span m='1541520'>randomly,</span>
  <span m='1542720'>you</span> <span m='1542900'>already</span> <span m='1543260'>have</span>
  <span m='1543380'>a</span> <span m='1543856'>simulation.</span> <span m='1544332'>So</span>
  <span m='1544808'>the node's</span> <span m='1545284'>going to get to</span> <span
  m='1545760'>someplace.</span> <span m='1546580'>But you don't</span> <span m='1546820'>store</span>
  <span m='1546980'>it</span> <span m='1547040'>because</span> <span m='1547325'>it
  would</span> <span m='1547610'>lose</span> <span m='1547970'>the</span> <span m='1548170'>randomness?</span>
  </p><p><span m='1549060'>PROFESSOR 3:</span> <span m='1549160'>You're</span> <span
  m='1549260'>totally</span> <span m='1549610'>right,</span> <span m='1550020'>actually,</span>
  <span m='1550520'>in</span> <span m='1550610'>this</span> <span m='1550790'>case.</span>
  <span m='1552170'>I've</span> <span m='1552630'>thought</span> <span m='1552860'>through</span>
  <span m='1553070'>this,</span> <span m='1553270'>and</span> <span m='1553330'>I</span>
  <span m='1553430'>can't</span> <span m='1553730'>come up with</span> <span m='1554040'>a</span>
  <span m='1554150'>reason</span> <span m='1554420'>why</span> <span m='1554710'>you
  wouldn't</span> <span m='1554870'>store</span> <span m='1555240'>it,</span> <span
  m='1555510'>that's</span> <span m='1555780'>it's</span> <span m='1556030'>temporary</span>
  <span m='1556510'>values</span> <span m='1556670'>that</span> <span m='1556820'>you</span>
  <span m='1557150'>find all</span> <span m='1557360'>the way</span> <span m='1557450'>down
  the</span> <span m='1557550'>tree.</span> <span m='1558260'>But</span> <span m='1558960'>they</span>
  <span m='1559240'>don't</span> <span m='1559440'>in most</span> <span m='1559922'>of
  the</span> <span m='1560404'>literature</span> <span m='1560886'>[INAUDIBLE]</span>
  <span m='1561610'>But</span> <span m='1562101'>you're</span> <span m='1562592'>totally
  right</span> <span m='1563083'>about that.</span> </p><p><span m='1563574'>Does</span>
  <span m='1564065'>everyone</span> <span m='1564560'>understand</span> <span m='1564960'>that</span>
  <span m='1565396'>distinction?</span> <span m='1566270'>The</span> <span m='1566460'>fact
  that we</span> <span m='1566790'>only</span> <span m='1567200'>hold</span> <span
  m='1567440'>onto</span> <span m='1568040'>the</span> <span m='1568130'>result</span>
  <span m='1568460'>here</span> <span m='1568880'>and</span> <span m='1569000'>don't</span>
  <span m='1569430'>theoretically</span> <span m='1569900'>make</span> <span m='1570110'>nodes</span>
  <span m='1570380'>for</span> <span m='1570500'>every</span> <span m='1571430'>place</span>
  <span m='1571790'>down in</span> <span m='1572060'>the</span> <span m='1572120'>tree</span>
  <span m='1572540'>just</span> <span m='1572750'>because</span> <span m='1572960'>we</span>
  <span m='1573080'>could,</span> <span m='1573320'>just</span> <span m='1573530'>because</span>
  <span m='1573920'>we've</span> <span m='1574415'>seen them</span> <span m='1574910'>before.</span>
  <span m='1575000'>We don't,</span> <span m='1575260'>and</span> <span m='1575330'>it</span>
  <span m='1575390'>doesn't</span> <span m='1575540'>really</span> <span m='1575750'>matter</span>
  <span m='1575990'>in</span> <span m='1576080'>this</span> <span m='1576200'>case.</span>
  <span m='1576440'>But it's</span> <span m='1576770'>theoretically</span> <span m='1577095'>a</span>
  <span m='1577420'>slight</span> <span m='1577770'>speed up</span> <span m='1578268'>that
  you</span> <span m='1578766'>could do.</span> </p><p><span m='1579762'>AUDIENCE:</span>
  <span m='1580011'>But</span> <span m='1580260'>you</span> <span m='1580710'>reduce</span>
  <span m='1581137'>that question to</span> <span m='1581564'>generalities?</span>
  </p><p><span m='1582420'>PROFESSOR 3:</span> <span m='1582525'>Yeah,</span> <span
  m='1582630'>a little</span> <span m='1583080'>bit.</span> <span m='1585950'>So</span>
  <span m='1586940'>we</span> <span m='1587030'>can</span> <span m='1587510'>look</span>
  <span m='1587810'>at</span> <span m='1588040'>an</span> <span m='1588140'>example</span>
  <span m='1588610'>of</span> <span m='1588720'>simulating</span> <span m='1588975'>out</span>
  <span m='1589230'>a</span> <span m='1589330'>running</span> <span m='1589620'>game.</span>
  <span m='1589940'>We</span> <span m='1590050'>get</span> <span m='1590360'>some</span>
  <span m='1590540'>intuition</span> <span m='1590960'>for</span> <span m='1591110'>why</span>
  <span m='1591410'>a</span> <span m='1591650'>random</span> <span m='1592070'>game</span>
  <span m='1592460'>would</span> <span m='1592610'>be</span> <span m='1592820'>correlated</span>
  <span m='1593450'>with</span> <span m='1593930'>how</span> <span m='1594100'>good</span>
  <span m='1594350'>your</span> <span m='1594500'>board</span> <span m='1594883'>position</span>
  <span m='1595266'>is.</span> </p><p><span m='1595760'>For</span> <span m='1595910'>example,</span>
  <span m='1596690'>here</span> <span m='1596840'>we have a</span> <span m='1597285'>Detecto</span>
  <span m='1597730'>game.</span> <span m='1598470'>Circle</span> <span m='1598860'>is</span>
  <span m='1598960'>going</span> <span m='1599090'>to</span> <span m='1599150'>move</span>
  <span m='1599300'>next.</span> <span m='1600210'>But</span> <span m='1600540'>as</span>
  <span m='1601000'>hopefully</span> <span m='1601370'>you</span> <span m='1601430'>can</span>
  <span m='1601580'>see,</span> <span m='1601950'>because</span> <span m='1602120'>you</span>
  <span m='1602240'>have played</span> <span m='1602540'>Detecto</span> <span m='1602780'>before,</span>
  <span m='1603840'>this</span> <span m='1603860'>is</span> <span m='1603950'>not</span>
  <span m='1604120'>a</span> <span m='1604170'>particularly</span> <span m='1604520'>promising</span>
  <span m='1605560'>board</span> <span m='1606120'>for</span> <span m='1607390'>x.</span>
  <span m='1607990'>Because</span> <span m='1610150'>no</span> <span m='1610310'>matter</span>
  <span m='1610740'>what</span> <span m='1610910'>circle</span> <span m='1611140'>does,</span>
  <span m='1611500'>if x</span> <span m='1611800'>is</span> <span m='1611960'>an</span>
  <span m='1612020'>intelligent</span> <span m='1612530'>player</span> <span m='1612890'>x</span>
  <span m='1613308'>can</span> <span m='1613726'>win</span> <span m='1614144'>right
  now.</span> <span m='1614980'>It</span> <span m='1615040'>has</span> <span m='1615200'>two</span>
  <span m='1615350'>different</span> <span m='1615530'>options</span> <span m='1615770'>for</span>
  <span m='1616140'>winning.</span> </p><p><span m='1616510'>And</span> <span m='1616610'>so,</span>
  <span m='1616840'>if</span> <span m='1616980'>you</span> <span m='1617280'>simulated</span>
  <span m='1617450'>this</span> <span m='1617570'>forward</span> <span m='1618530'>randomly,</span>
  <span m='1619000'>what</span> <span m='1619210'>you'll get is</span> <span m='1619580'>that</span>
  <span m='1619700'>2/3</span> <span m='1620090'>of</span> <span m='1620150'>the</span>
  <span m='1620240'>time,</span> <span m='1620900'>x will</span> <span m='1621390'>in
  fact</span> <span m='1621620'>win,</span> <span m='1621890'>even</span> <span m='1622100'>if</span>
  <span m='1622220'>the</span> <span m='1622310'>players</span> <span m='1622670'>aren't</span>
  <span m='1622880'>really</span> <span m='1623230'>thinking of it</span> <span m='1623623'>ahead
  of time.</span> <span m='1624410'>Yeah.</span> </p><p><span m='1624690'>AUDIENCE:</span>
  <span m='1624919'>Then</span> <span m='1625148'>why</span> <span m='1625606'>not</span>
  <span m='1626064'>do</span> <span m='1626522'>n</span> <span m='1626980'>simulations</span>
  <span m='1627170'>at a</span> <span m='1627618'>node</span> <span m='1628066'>instead
  of</span> <span m='1628514'>just</span> <span m='1628962'>a</span> <span m='1629111'>single</span>
  <span m='1629260'>simulation?</span> </p><p><span m='1629860'>PROFESSOR 3:</span>
  <span m='1629910'>You</span> <span m='1629960'>totally can</span> <span m='1630180'>do</span>
  <span m='1630290'>that.</span> <span m='1630510'>That's</span> <span m='1630680'>in</span>
  <span m='1630800'>fact,</span> <span m='1631110'>something</span> <span m='1631400'>that</span>
  <span m='1631550'>make</span> <span m='1631860'>sense</span> <span m='1632030'>to</span>
  <span m='1632120'>do</span> <span m='1632470'>and</span> <span m='1632620'>that</span>
  <span m='1632840'>some</span> <span m='1633050'>people</span> <span m='1633260'>do.</span>
  <span m='1633740'>Although</span> <span m='1634460'>what</span> <span m='1634610'>you'll</span>
  <span m='1634730'>find</span> <span m='1635060'>somewhat</span> <span m='1635390'>soon,</span>
  <span m='1636110'>is</span> <span m='1636600'>that</span> <span m='1636780'>considering
  that</span> <span m='1637270'>we're</span> <span m='1637610'>going</span> <span
  m='1637940'>down</span> <span m='1638180'>the</span> <span m='1638270'>tree,</span>
  <span m='1638780'>and</span> <span m='1638990'>that</span> <span m='1639620'>sometimes</span>
  <span m='1640030'>soon</span> <span m='1640260'>we're</span> <span m='1640400'>going</span>
  <span m='1640520'>to</span> <span m='1640580'>explore</span> <span m='1640940'>all</span>
  <span m='1641070'>of</span> <span m='1641110'>its</span> <span m='1641180'>children,</span>
  <span m='1641960'>there's</span> <span m='1642170'>a</span> <span m='1642290'>good</span>
  <span m='1642620'>question</span> <span m='1642990'>of</span> <span m='1643430'>why</span>
  <span m='1643710'>you</span> <span m='1643830'>end</span> <span m='1644170'>simulations</span>
  <span m='1644510'>now</span> <span m='1644930'>when</span> <span m='1645040'>you</span>
  <span m='1645150'>could</span> <span m='1645260'>just</span> <span m='1645990'>descend</span>
  <span m='1646200'>through</span> <span m='1646490'>the</span> <span m='1646550'>tree</span>
  <span m='1646880'>n</span> <span m='1647000'>times</span> <span m='1648080'>and</span>
  <span m='1648500'>thereby</span> <span m='1648990'>do</span> <span m='1649250'>n</span>
  <span m='1649480'>simulations</span> <span m='1650060'>by</span> <span m='1650210'>going</span>
  <span m='1650540'>through</span> <span m='1650700'>the</span> <span m='1650910'>thing</span>
  <span m='1651030'>and also</span> <span m='1651380'>building</span> <span m='1651720'>out
  the</span> <span m='1652120'>children?</span> <span m='1654210'>This</span> <span
  m='1654760'>case</span> <span m='1655000'>is--</span> <span m='1655380'>yeah.</span>
  </p><p><span m='1655650'>AUDIENCE:</span> <span m='1655855'>This</span> <span m='1656060'>gives</span>
  <span m='1656640'>more</span> <span m='1656910'>importance</span> <span m='1657360'>to</span>
  <span m='1657500'>why</span> <span m='1657780'>you</span> <span m='1657870'>do</span>
  <span m='1658030'>randomness.</span> <span m='1658440'>Because</span> <span m='1658873'>if
  you're</span> <span m='1659306'>doing</span> <span m='1659739'>random</span> <span
  m='1660172'>simulations</span> <span m='1660605'>you would</span> <span m='1661040'>ignore
  the</span> <span m='1661250'>possibility</span> <span m='1661732'>of the best</span>
  <span m='1662214'>one.</span> <span m='1662696'>When you first ran</span> <span
  m='1663178'>a simulation</span> <span m='1663660'>here</span> <span m='1664142'>was
  that</span> <span m='1664630'>o</span> <span m='1664810'>wins.</span> <span m='1665255'>If
  I</span> <span m='1665700'>ignore</span> <span m='1665880'>this</span> <span m='1666275'>node--</span>
  </p><p><span m='1667090'>PROFESSOR 3:</span> <span m='1667310'>Absolutely.</span>
  <span m='1668230'>Which</span> <span m='1668410'>is</span> <span m='1668690'>why</span>
  <span m='1669140'>it</span> <span m='1669350'>matters</span> <span m='1669800'>that</span>
  <span m='1669920'>we</span> <span m='1670010'>do</span> <span m='1670160'>this</span>
  <span m='1670280'>so</span> <span m='1670610'>many</span> <span m='1670820'>times</span>
  <span m='1671600'>that</span> <span m='1671750'>we</span> <span m='1672530'>drown</span>
  <span m='1672950'>out</span> <span m='1673160'>all</span> <span m='1673410'>the</span>
  <span m='1673550'>noise</span> <span m='1674360'>that</span> <span m='1674480'>is</span>
  <span m='1674600'>associated</span> <span m='1675080'>with</span> <span m='1675360'>playing
  a</span> <span m='1675670'>game out</span> <span m='1676116'>randomly.</span> <span
  m='1677010'>Let's</span> <span m='1677240'>talk</span> <span m='1677480'>about</span>
  <span m='1677690'>that.</span> <span m='1678930'>If</span> <span m='1679100'>there's</span>
  <span m='1679280'>a</span> <span m='1679370'>lot</span> <span m='1679610'>of</span>
  <span m='1679700'>distance</span> <span m='1680300'>between</span> <span m='1680720'>where</span>
  <span m='1680930'>we</span> <span m='1681050'>are</span> <span m='1681180'>right</span>
  <span m='1681350'>now</span> <span m='1682010'>and</span> <span m='1682580'>our</span>
  <span m='1682760'>end</span> <span m='1682940'>result--</span> </p><p><span m='1683620'>For</span>
  <span m='1683750'>example,</span> <span m='1684020'>in this</span> <span m='1684200'>game,</span>
  <span m='1684930'>if</span> <span m='1684950'>I</span> <span m='1685040'>were</span>
  <span m='1685100'>to</span> <span m='1685190'>tell</span> <span m='1685460'>you</span>
  <span m='1685910'>how</span> <span m='1686180'>good</span> <span m='1686420'>is</span>
  <span m='1686540'>this</span> <span m='1686740'>board</span> <span m='1687230'>position,</span>
  <span m='1687745'>if</span> <span m='1688020'>you</span> <span m='1688230'>are</span>
  <span m='1688550'>one</span> <span m='1688670'>of</span> <span m='1688730'>those</span>
  <span m='1688850'>people</span> <span m='1689150'>who</span> <span m='1689290'>played
  out</span> <span m='1689640'>every</span> <span m='1689900'>game</span> <span m='1690080'>of</span>
  <span m='1690405'>Detecto,</span> <span m='1690730'>you'll</span> <span m='1690890'>know</span>
  <span m='1691330'>that this</span> <span m='1691570'>is</span> <span m='1691690'>great</span>
  <span m='1692200'>if you</span> <span m='1692290'>want</span> <span m='1692560'>it
  to</span> <span m='1692770'>be</span> <span m='1692900'>[INAUDIBLE]</span> </p><p><span
  m='1695660'>Anyway,</span> <span m='1696200'>the</span> <span m='1696320'>point</span>
  <span m='1696530'>is,</span> <span m='1697280'>that</span> <span m='1697460'>is</span>
  <span m='1697580'>not</span> <span m='1697820'>easy</span> <span m='1698030'>to</span>
  <span m='1698120'>do</span> <span m='1698340'>if</span> <span m='1698705'>you are</span>
  <span m='1699070'>doing</span> <span m='1699350'>random</span> <span m='1699570'>simulations</span>
  <span m='1700130'>from</span> <span m='1700390'>where</span> <span m='1700550'>you</span>
  <span m='1700690'>start.</span> <span m='1701730'>The</span> <span m='1702100'>correlation</span>
  <span m='1702760'>between</span> <span m='1703390'>your</span> <span m='1703570'>friend's</span>
  <span m='1703930'>board</span> <span m='1704180'>state</span> <span m='1704500'>and</span>
  <span m='1704620'>the</span> <span m='1704710'>quality</span> <span m='1705250'>of</span>
  <span m='1705310'>that</span> <span m='1705490'>state</span> <span m='1706210'>actually</span>
  <span m='1706780'>drops</span> <span m='1707110'>precipitously.</span> <span m='1708070'>And</span>
  <span m='1708160'>this</span> <span m='1708370'>for</span> <span m='1708520'>me</span>
  <span m='1708820'>is</span> <span m='1708940'>one</span> <span m='1709030'>of</span>
  <span m='1709090'>the</span> <span m='1709180'>hardest</span> <span m='1709510'>parts</span>
  <span m='1709780'>to</span> <span m='1709870'>study</span> <span m='1710610'>about</span>
  <span m='1710830'>Monte</span> <span m='1710920'>Carlo</span> <span m='1711080'>Tree</span>
  <span m='1711450'>Search.</span> </p><p><span m='1711940'>Although,</span> <span
  m='1712390'>as</span> <span m='1712695'>Nick will</span> <span m='1713000'>explain
  to</span> <span m='1713300'>you,</span> <span m='1713890'>it</span> <span m='1714070'>actually</span>
  <span m='1714490'>works</span> <span m='1714730'>quite</span> <span m='1714970'>well.</span>
  <span m='1716270'>And</span> <span m='1716590'>one</span> <span m='1716710'>of</span>
  <span m='1716770'>the</span> <span m='1716830'>reasons</span> <span m='1717160'>that
  it</span> <span m='1717310'>works</span> <span m='1717580'>quite</span> <span m='1718060'>well</span>
  <span m='1718270'>in</span> <span m='1718390'>practice</span> <span m='1718840'>for</span>
  <span m='1718960'>more</span> <span m='1719080'>complicated</span> <span m='1719560'>applications</span>
  <span m='1720040'>is</span> <span m='1720425'>they</span> <span m='1721040'>do</span>
  <span m='1721280'>away</span> <span m='1721510'>with the</span> <span m='1721915'>assumption</span>
  <span m='1722320'>of</span> <span m='1722500'>random</span> <span m='1722740'>simulation.</span>
  </p><p><span m='1723480'>Because</span> <span m='1723850'>even the</span> <span
  m='1723940'>random</span> <span m='1724370'>simulations</span> <span m='1725140'>does</span>
  <span m='1725330'>allow</span> <span m='1725530'>you</span> <span m='1725790'>to
  explore</span> <span m='1726010'>all</span> <span m='1726100'>the</span> <span m='1726170'>states,</span>
  <span m='1726800'>if</span> <span m='1726930'>you</span> <span m='1727060'>have</span>
  <span m='1727240'>some</span> <span m='1727510'>idea</span> <span m='1727920'>of</span>
  <span m='1728060'>where</span> <span m='1728500'>a</span> <span m='1728810'>reasonable</span>
  <span m='1729120'>quality</span> <span m='1729410'>approach</span> <span m='1729620'>would</span>
  <span m='1730110'>be,</span> <span m='1730600'>then</span> <span m='1731050'>using</span>
  <span m='1731440'>that,</span> <span m='1731740'>as</span> <span m='1732005'>long
  as</span> <span m='1732270'>it's</span> <span m='1732460'>not</span> <span m='1732670'>that</span>
  <span m='1732850'>much</span> <span m='1733030'>more</span> <span m='1733190'>expensive</span>
  <span m='1734510'>computationally,</span> <span m='1734943'>can</span> <span m='1735376'>help</span>
  <span m='1735810'>you</span> <span m='1735940'>with your simulation.</span> <span
  m='1736770'>Right</span> <span m='1736960'>now we're</span> <span m='1737280'>still</span>
  <span m='1737600'>talking about</span> <span m='1737760'>total</span> <span m='1738070'>randomness.</span>
  <span m='1739660'>How are</span> <span m='1739900'>people doing with that</span>
  <span m='1740380'>idea?</span> </p><p><span m='1744535'>Now</span> <span m='1744720'>we're</span>
  <span m='1744860'>going</span> <span m='1745010'>to</span> <span m='1745090'>update</span>
  <span m='1745200'>the</span> <span m='1745400'>tree</span> <span m='1745850'>with</span>
  <span m='1746000'>the</span> <span m='1746060'>results</span> <span m='1746330'>of
  our</span> <span m='1746810'>simulation.</span> <span m='1747320'>So</span> <span
  m='1748100'>given</span> <span m='1748580'>that</span> <span m='1748730'>we</span>
  <span m='1748850'>had</span> <span m='1749030'>some</span> <span m='1749230'>result</span>
  <span m='1749500'>lambda,</span> <span m='1750330'>we're going to</span> <span m='1750590'>try
  to get up</span> <span m='1750830'>the</span> <span m='1751030'>parents.</span>
  <span m='1752140'>And</span> <span m='1752630'>for</span> <span m='1752810'>each</span>
  <span m='1752990'>parent</span> <span m='1753390'>we're</span> <span m='1753500'>going</span>
  <span m='1753620'>to</span> <span m='1753680'>add</span> <span m='1753960'>that</span>
  <span m='1754250'>the</span> <span m='1754330'>game</span> <span m='1754510'>has</span>
  <span m='1754650'>been</span> <span m='1754790'>played</span> <span m='1754970'>there</span>
  <span m='1755150'>once,</span> <span m='1755780'>and</span> <span m='1758570'>that</span>
  <span m='1759570'>the</span> <span m='1759860'>result</span> <span m='1759950'>of</span>
  <span m='1760440'>that</span> <span m='1760540'>simulation</span> <span m='1760790'>gets</span>
  <span m='1761250'>added</span> <span m='1762170'>if</span> <span m='1763010'>it</span>
  <span m='1763130'>was</span> <span m='1763250'>a</span> <span m='1763310'>one.</span>
  </p><p><span m='1764460'>So</span> <span m='1764750'>for</span> <span m='1764870'>example,</span>
  <span m='1765740'>if</span> <span m='1765830'>there</span> <span m='1765950'>was</span>
  <span m='1766100'>a</span> <span m='1766170'>win</span> <span m='1766290'>in</span>
  <span m='1766360'>this</span> <span m='1766550'>game,</span> <span m='1767300'>than</span>
  <span m='1767450'>this</span> <span m='1767630'>becomes</span> <span m='1767970'>one,</span>
  <span m='1768320'>one</span> <span m='1768770'>because</span> <span m='1769040'>now</span>
  <span m='1769620'>it's</span> <span m='1769820'>won</span> <span m='1770250'>once</span>
  <span m='1770520'>and</span> <span m='1770850'>it's</span> <span m='1771030'>been
  visited</span> <span m='1771440'>once.</span> <span m='1772190'>And</span> <span
  m='1773090'>these</span> <span m='1773360'>two</span> <span m='1773690'>get</span>
  <span m='1773840'>incremented by</span> <span m='1774230'>one,</span> <span m='1774630'>and</span>
  <span m='1774790'>these two</span> <span m='1774940'>get</span> <span m='1775140'>incremented</span>
  <span m='1775300'>by one.</span> <span m='1777280'>That</span> <span m='1777710'>in</span>
  <span m='1777920'>itself</span> <span m='1779240'>comprises</span> <span m='1779900'>a</span>
  <span m='1779960'>complete</span> <span m='1780560'>iteration,</span> <span m='1781060'>the</span>
  <span m='1781452'>complete</span> <span m='1781844'>single</span> <span m='1782236'>iteration</span>
  <span m='1782630'>of</span> <span m='1783230'>running</span> <span m='1783610'>Monte</span>
  <span m='1783930'>Carlo</span> <span m='1784250'>Tree</span> <span m='1784610'>Search,</span>
  <span m='1784970'>which</span> <span m='1785120'>means</span> <span m='1786350'>that</span>
  <span m='1788050'>now</span> <span m='1788750'>we</span> <span m='1788840'>can</span>
  <span m='1789080'>keep</span> <span m='1789260'>doing</span> <span m='1789590'>this</span>
  <span m='1789950'>over</span> <span m='1790250'>and</span> <span m='1790340'>over</span>
  <span m='1790580'>again,</span> <span m='1791360'>building</span> <span m='1791690'>up</span>
  <span m='1791810'>the</span> <span m='1791920'>tree</span> <span m='1792620'>and</span>
  <span m='1792950'>slowly</span> <span m='1793400'>making</span> <span m='1793660'>it</span>
  <span m='1793760'>deeper,</span> <span m='1794990'>and making it</span> <span m='1795080'>deeper</span>
  <span m='1795350'>in</span> <span m='1795550'>selective</span> <span m='1795800'>areas.</span>
  <span m='1796740'>And</span> <span m='1797030'>having</span> <span m='1797360'>these</span>
  <span m='1797570'>numbers</span> <span m='1798080'>increase</span> <span m='1798470'>and</span>
  <span m='1798560'>increase.</span> <span m='1799450'>And</span> <span m='1799640'>be</span>
  <span m='1799880'>more</span> <span m='1800210'>and</span> <span m='1800300'>more</span>
  <span m='1800510'>proportional</span> <span m='1801080'>to</span> <span m='1801290'>the</span>
  <span m='1801650'>actual</span> <span m='1802520'>expected</span> <span m='1803000'>value</span>
  <span m='1803540'>of</span> <span m='1803630'>the</span> <span m='1803760'>quality</span>
  <span m='1804080'>of the</span> <span m='1804505'>state,</span> <span m='1805430'>until--</span>
  <span m='1806080'>does anyone have</span> <span m='1806460'>any</span> <span m='1806803'>questions</span>
  <span m='1807146'>about</span> <span m='1807490'>this</span> <span m='1807760'>idea?--</span>
  <span m='1811740'>until</span> <span m='1812250'>we</span> <span m='1812370'>terminate.</span>
  <span m='1812550'>And</span> <span m='1812820'>we</span> <span m='1813175'>have
  to come up with</span> <span m='1813530'>a</span> <span m='1813680'>way</span> <span
  m='1813940'>to</span> <span m='1814140'>terminate</span> <span m='1814280'>it.</span>
  </p><p><span m='1815040'>Now</span> <span m='1815430'>again,</span> <span m='1815760'>we</span>
  <span m='1815880'>said</span> <span m='1816120'>we're</span> <span m='1816240'>going</span>
  <span m='1816420'>to</span> <span m='1816480'>pick</span> <span m='1816810'>what</span>
  <span m='1817140'>the best</span> <span m='1817620'>child</span> <span m='1818490'>is</span>
  <span m='1818670'>going</span> <span m='1818820'>to</span> <span m='1818880'>be,</span>
  <span m='1820200'>what</span> <span m='1820350'>the</span> <span m='1820460'>best</span>
  <span m='1820950'>immediate</span> <span m='1821100'>move</span> <span m='1821340'>from</span>
  <span m='1821580'>the</span> <span m='1821640'>start</span> <span m='1821850'>state
  is going</span> <span m='1822230'>to be.</span> <span m='1824335'>That's</span>
  <span m='1824760'>the</span> <span m='1825020'>move that</span> <span m='1825150'>were</span>
  <span m='1825240'>actually</span> <span m='1825560'>going to</span> <span m='1825660'>play.</span>
  <span m='1826650'>And</span> <span m='1826790'>so,</span> <span m='1827330'>how</span>
  <span m='1827590'>do</span> <span m='1827640'>we</span> <span m='1827730'>determine</span>
  <span m='1827970'>what</span> <span m='1828110'>the</span> <span m='1828180'>best</span>
  <span m='1828540'>is?</span> </p><p><span m='1829010'>Well,</span> <span m='1829750'>the</span>
  <span m='1830310'>trivial</span> <span m='1830640'>solution</span> <span m='1831130'>is</span>
  <span m='1832020'>just</span> <span m='1832560'>the</span> <span m='1832680'>highest</span>
  <span m='1833240'>expected</span> <span m='1833590'>win</span> <span m='1834210'>given</span>
  <span m='1834300'>k.</span> <span m='1836790'>What</span> <span m='1836940'>that,</span>
  <span m='1837250'>in</span> <span m='1837360'>our</span> <span m='1837550'>case,</span>
  <span m='1837665'>is</span> <span m='1837780'>going</span> <span m='1837900'>to</span>
  <span m='1837960'>be</span> <span m='1838550'>is</span> <span m='1839340'>the</span>
  <span m='1839460'>ratio</span> <span m='1839940'>of</span> <span m='1840510'>number</span>
  <span m='1840690'>of</span> <span m='1840750'>times</span> <span m='1841020'>that</span>
  <span m='1841110'>I've</span> <span m='1841190'>win</span> <span m='1841500'>from</span>
  <span m='1841740'>a given</span> <span m='1842490'>early</span> <span m='1842730'>state</span>
  <span m='1843350'>to</span> <span m='1843610'>the</span> <span m='1843930'>number
  of times</span> <span m='1844250'>that I</span> <span m='1844410'>visited.</span>
  <span m='1845880'>However,</span> <span m='1846780'>this</span> <span m='1846930'>doesn't</span>
  <span m='1847170'>actually</span> <span m='1847470'>work as</span> <span m='1847725'>well
  as</span> <span m='1847980'>we might</span> <span m='1848070'>hope.</span> </p><p><span
  m='1848745'>Let's</span> <span m='1849120'>suppose</span> <span m='1849330'>the</span>
  <span m='1849450'>following</span> <span m='1849620'>scenario,</span> <span m='1850530'>which</span>
  <span m='1850680'>is</span> <span m='1851220'>that</span> <span m='1851870'>you</span>
  <span m='1852050'>have</span> <span m='1852160'>the</span> <span m='1852260'>Detecto</span>
  <span m='1852720'>game</span> <span m='1852960'>like</span> <span m='1853313'>this.</span>
  <span m='1854020'>And</span> <span m='1854520'>you</span> <span m='1854790'>have</span>
  <span m='1854910'>been</span> <span m='1855030'>exploring</span> <span m='1856080'>the</span>
  <span m='1856170'>tree</span> <span m='1856430'>for</span> <span m='1856560'>a</span>
  <span m='1856590'>while.</span> <span m='1857220'>And</span> <span m='1857440'>you're</span>
  <span m='1857670'>really</span> <span m='1857940'>mostly</span> <span m='1858750'>looking</span>
  <span m='1859000'>at</span> <span m='1859220'>these</span> <span m='1859560'>two</span>
  <span m='1859680'>nodes.</span> <span m='1860520'>One of</span> <span m='1860780'>these</span>
  <span m='1860970'>nodes,</span> <span m='1862800'>if</span> <span m='1862950'>you</span>
  <span m='1863570'>think</span> <span m='1863720'>it</span> <span m='1863850'>through,</span>
  <span m='1864390'>this</span> <span m='1864680'>node is</span> <span m='1864870'>quite</span>
  <span m='1865140'>promising</span> <span m='1865850'>and</span> <span m='1865950'>you've</span>
  <span m='1866070'>been</span> <span m='1866220'>exploring</span> <span m='1866610'>it</span>
  <span m='1866670'>for</span> <span m='1866790'>a</span> <span m='1866820'>while.</span>
  </p><p><span m='1867570'>There</span> <span m='1867710'>is</span> <span m='1867940'>a</span>
  <span m='1868020'>winning</span> <span m='1868230'>strategy</span> <span m='1868530'>from
  this</span> <span m='1868830'>node.</span> <span m='1869130'>It's</span> <span m='1869490'>that</span>
  <span m='1869870'>circle goes</span> <span m='1870190'>here,</span> <span m='1870460'>and</span>
  <span m='1870560'>then</span> <span m='1870620'>x goes</span> <span m='1870990'>here,</span>
  <span m='1871260'>and</span> <span m='1871350'>then</span> <span m='1871450'>circle</span>
  <span m='1871760'>loses</span> <span m='1872100'>because</span> <span m='1872370'>x
  has</span> <span m='1872650'>two</span> <span m='1873088'>options</span> <span m='1873526'>to
  win.</span> <span m='1876910'>However,</span> <span m='1877470'>if you</span> <span
  m='1877610'>explore</span> <span m='1877710'>this</span> <span m='1877840'>a</span>
  <span m='1877920'>bunch</span> <span m='1878030'>of</span> <span m='1878250'>times,</span>
  <span m='1878610'>and</span> <span m='1878730'>for</span> <span m='1878850'>some</span>
  <span m='1879060'>reason,</span> <span m='1879330'>due</span> <span m='1879450'>to</span>
  <span m='1879540'>the</span> <span m='1879600'>randomness,</span> <span m='1880480'>this</span>
  <span m='1880590'>is</span> <span m='1880680'>at</span> <span m='1881050'>11</span>
  <span m='1881420'>out</span> <span m='1881690'>of 20.</span> <span m='1881970'>Whereas</span>
  <span m='1882240'>this</span> <span m='1882420'>state,</span> <span m='1882990'>which</span>
  <span m='1883170'>is</span> <span m='1883710'>inherently</span> <span m='1884190'>inferior,</span>
  <span m='1885980'>is</span> <span m='1886400'>at</span> <span m='1886550'>three</span>
  <span m='1886760'>out of five</span> <span m='1887150'>because</span> <span m='1887420'>of
  a bunch of</span> <span m='1887760'>randomness</span> <span m='1888020'>and because</span>
  <span m='1888280'>it</span> <span m='1888540'>hasn't</span> <span m='1888900'>been</span>
  <span m='1889160'>explored</span> <span m='1889640'>as</span> <span m='1890010'>much.</span>
  </p><p><span m='1890380'>And</span> <span m='1890480'>if</span> <span m='1890490'>we
  had</span> <span m='1890790'>looked</span> <span m='1891030'>at</span> <span m='1891120'>this</span>
  <span m='1891390'>one</span> <span m='1891630'>as</span> <span m='1891750'>exhaustively</span>
  <span m='1892390'>we</span> <span m='1892530'>had at</span> <span m='1892740'>this</span>
  <span m='1892920'>one,</span> <span m='1895130'>that</span> <span m='1895350'>you</span>
  <span m='1895500'>probably</span> <span m='1895800'>would</span> <span m='1895950'>actually</span>
  <span m='1896220'>say</span> <span m='1896480'>that</span> <span m='1896600'>this</span>
  <span m='1896760'>state is</span> <span m='1896900'>actually better.</span> <span
  m='1897880'>And</span> <span m='1898010'>so,</span> <span m='1899340'>you</span>
  <span m='1899430'>can</span> <span m='1899550'>create</span> <span m='1899900'>an</span>
  <span m='1900100'>alternative</span> <span m='1900230'>criteria,</span> <span m='1900900'>which</span>
  <span m='1901050'>is</span> <span m='1901580'>that</span> <span m='1901830'>it's</span>
  <span m='1901980'>the</span> <span m='1902070'>highest</span> <span m='1902820'>expected</span>
  <span m='1903580'>win</span> <span m='1903920'>value</span> <span m='1904650'>of</span>
  <span m='1904900'>one of</span> <span m='1905190'>the</span> <span m='1905280'>children.</span>
  <span m='1906060'>But</span> <span m='1906210'>also,</span> <span m='1906870'>that</span>
  <span m='1907360'>value</span> <span m='1907860'>has</span> <span m='1908040'>to</span>
  <span m='1908160'>be</span> <span m='1909120'>the</span> <span m='1909360'>node</span>
  <span m='1909600'>that</span> <span m='1909750'>has</span> <span m='1909840'>been</span>
  <span m='1909960'>most</span> <span m='1910200'>visited</span> <span m='1910620'>so</span>
  <span m='1910790'>that</span> <span m='1910880'>they</span> <span m='1911040'>aren't</span>
  <span m='1911310'>explored</span> <span m='1912000'>by</span> <span m='1912180'>different</span>
  <span m='1912520'>amounts.</span> </p><p><span m='1914590'>What</span> <span m='1914850'>this</span>
  <span m='1915160'>sacrifice</span> <span m='1915420'>is</span> <span m='1915680'>however,</span>
  <span m='1915940'>is</span> <span m='1916080'>that</span> <span m='1916610'>this</span>
  <span m='1916770'>means</span> <span m='1917070'>that</span> <span m='1917190'>we</span>
  <span m='1917310'>can't</span> <span m='1917940'>terminate</span> <span m='1918990'>on</span>
  <span m='1919200'>demand.</span> <span m='1921050'>This</span> <span m='1921390'>is</span>
  <span m='1921600'>not</span> <span m='1921810'>always</span> <span m='1922140'>going</span>
  <span m='1922250'>to</span> <span m='1922310'>be</span> <span m='1922380'>true,</span>
  <span m='1922870'>and</span> <span m='1922890'>therefore,</span> <span m='1923380'>we're</span>
  <span m='1923480'>going</span> <span m='1923580'>to</span> <span m='1923680'>have</span>
  <span m='1923780'>to</span> <span m='1923880'>let</span> <span m='1924000'>the</span>
  <span m='1924220'>algorithm</span> <span m='1924660'>run</span> <span m='1925290'>until</span>
  <span m='1925620'>that's</span> <span m='1925820'>true</span> <span m='1926100'>for</span>
  <span m='1926250'>some</span> <span m='1926520'>start</span> <span m='1926820'>state,</span>
  <span m='1927550'>which</span> <span m='1927600'>means</span> <span m='1927900'>that</span>
  <span m='1928020'>maybe</span> <span m='1928370'>is</span> <span m='1928530'>not</span>
  <span m='1928720'>a</span> <span m='1928790'>criteria</span> <span m='1929080'>that
  we</span> <span m='1929200'>want to</span> <span m='1929440'>apply</span> <span
  m='1929680'>even though</span> <span m='1929940'>we know that</span> <span m='1930200'>it
  would be</span> <span m='1930280'>wise</span> <span m='1930530'>to do so.</span>
  <span m='1932220'>Are</span> <span m='1932310'>there</span> <span m='1932430'>any</span>
  <span m='1932520'>questions</span> <span m='1932820'>about</span> <span m='1933000'>how</span>
  <span m='1933260'>we</span> <span m='1933390'>pick</span> <span m='1933848'>the</span>
  <span m='1934306'>terminating</span> <span m='1934764'>guide?</span> </p><p><span
  m='1939280'>That</span> <span m='1939410'>was</span> <span m='1939590'>the</span>
  <span m='1939680'>whole</span> <span m='1939950'>thing.</span> <span m='1940680'>And</span>
  <span m='1940700'>now</span> <span m='1940940'>we're</span> <span m='1941090'>going</span>
  <span m='1941290'>to</span> <span m='1941360'>do it</span> <span m='1941570'>lots</span>
  <span m='1941870'>and</span> <span m='1941990'>lots of</span> <span m='1942200'>times</span>
  <span m='1942560'>until</span> <span m='1942650'>you guys</span> <span m='1942900'>are</span>
  <span m='1943110'>sick of</span> <span m='1943520'>Monte</span> <span m='1943710'>Carlo</span>
  <span m='1944124'>Tree</span> <span m='1944538'>Search.</span> <span m='1945780'>So</span>
  <span m='1946280'>this our</span> <span m='1946460'>tree.</span> <span m='1946970'>It's</span>
  <span m='1947450'>more</span> <span m='1947720'>or</span> <span m='1947750'>less</span>
  <span m='1947930'>what</span> <span m='1948020'>we've</span> <span m='1948140'>had</span>
  <span m='1948290'>before.</span> </p><p><span m='1950120'>The</span> <span m='1950210'>first</span>
  <span m='1950390'>thing</span> <span m='1950510'>we're</span> <span m='1950870'>going</span>
  <span m='1951020'>to do</span> <span m='1951200'>is we're going to</span> <span
  m='1951410'>look at the</span> <span m='1951500'>top.</span> <span m='1952235'>And
  then</span> <span m='1952700'>we're</span> <span m='1952760'>going</span> <span
  m='1952880'>to</span> <span m='1952940'>pick</span> <span m='1953120'>one</span>
  <span m='1953240'>of</span> <span m='1953300'>these</span> <span m='1953640'>children.</span>
  <span m='1955250'>Now</span> <span m='1955940'>let's</span> <span m='1956120'>say</span>
  <span m='1956360'>that</span> <span m='1956520'>we</span> <span m='1956580'>looked</span>
  <span m='1956780'>at</span> <span m='1956870'>this,</span> <span m='1957260'>and
  it</span> <span m='1957410'>turns out</span> <span m='1957640'>that the</span> <span
  m='1957770'>one on</span> <span m='1958130'>the</span> <span m='1958220'>left</span>
  <span m='1958560'>is</span> <span m='1958700'>really</span> <span m='1959000'>valuable.</span>
  <span m='1959210'>I think</span> <span m='1959280'>it's the one.</span> <span m='1960060'>Nope,</span>
  <span m='1960210'>yeah.</span> <span m='1960583'>Never mind.</span> <span m='1960956'>It's</span>
  <span m='1961330'>wrong.</span> </p><p><span m='1962960'>The one on the</span> <span
  m='1963020'>left</span> <span m='1963230'>has</span> <span m='1963350'>been</span>
  <span m='1963440'>explored</span> <span m='1963860'>a</span> <span m='1963890'>whole</span>
  <span m='1964010'>bunch</span> <span m='1964130'>of</span> <span m='1964190'>times.</span>
  <span m='1964740'>Remember,</span> <span m='1966320'>this</span> <span m='1966560'>term</span>
  <span m='1966830'>starts</span> <span m='1967160'>becoming</span> <span m='1967490'>larger</span>
  <span m='1967730'>than</span> <span m='1967970'>the</span> <span m='1968030'>ones</span>
  <span m='1968270'>that</span> <span m='1968650'>haven't</span> <span m='1968860'>been</span>
  <span m='1969060'>visited</span> <span m='1969620'>as</span> <span m='1969740'>much.</span>
  <span m='1969980'>And</span> <span m='1970430'>so</span> <span m='1970640'>we're</span>
  <span m='1970760'>going</span> <span m='1970990'>to</span> <span m='1971100'>descend</span>
  <span m='1971450'>from</span> <span m='1971960'>this</span> <span m='1972140'>one.</span>
  <span m='1973390'>And</span> <span m='1973520'>now</span> <span m='1973760'>we're</span>
  <span m='1974176'>going to</span> <span m='1974592'>descend,</span> <span m='1975010'>and
  we</span> <span m='1975420'>have</span> <span m='1975680'>these two</span> <span
  m='1975860'>options.</span> </p><p><span m='1977175'>Given</span> <span m='1977500'>what</span>
  <span m='1977690'>you</span> <span m='1977780'>know,</span> <span m='1978310'>would</span>
  <span m='1978480'>you</span> <span m='1978620'>expect</span> <span m='1980620'>that</span>
  <span m='1980910'>this</span> <span m='1981190'>is</span> <span m='1981310'>going</span>
  <span m='1981520'>to pick</span> <span m='1981740'>is</span> <span m='1981950'>going</span>
  <span m='1982070'>to</span> <span m='1982130'>be</span> <span m='1982500'>the</span>
  <span m='1982610'>one</span> <span m='1982820'>on the right or the</span> <span
  m='1983315'>one on the left?</span> </p><p><span m='1983810'>AUDIENCE:</span> <span
  m='1984057'>[INAUDIBLE]</span> </p><p><span m='1985295'>PROFESSOR 3:</span> <span
  m='1985460'>On</span> <span m='1985625'>the</span> <span m='1985790'>right because</span>
  <span m='1986060'>it's never</span> <span m='1986250'>been visited</span> <span
  m='1986560'>before.</span> <span m='1986880'>And</span> <span m='1987010'>so,</span>
  <span m='1987150'>this</span> <span m='1987410'>term is</span> <span m='1987500'>going</span>
  <span m='1987680'>to</span> <span m='1987790'>explode.</span> <span m='1988380'>And
  so,</span> <span m='1988600'>we're going</span> <span m='1989000'>to</span> <span
  m='1989400'>build</span> <span m='1989800'>a node there.</span> </p><p><span m='1990060'>And</span>
  <span m='1990440'>then</span> <span m='1990820'>we're going to</span> <span m='1991200'>simulate
  a game.</span> <span m='1991580'>And the</span> <span m='1991700'>result</span>
  <span m='1992000'>is</span> <span m='1993220'>a</span> <span m='1993530'>win,</span>
  <span m='1994250'>which</span> <span m='1994460'>is</span> <span m='1994610'>bad</span>
  <span m='1995300'>for</span> <span m='1995840'>this</span> <span m='1995990'>player.</span>
  <span m='1996440'>That</span> <span m='1996490'>means</span> <span m='1996650'>that
  he</span> <span m='1996810'>probably</span> <span m='1997100'>didn't</span> <span
  m='1997400'>want to make</span> <span m='1997610'>that</span> <span m='1997760'>move.</span>
  </p><p><span m='1998370'>And</span> <span m='1998730'>so</span> <span m='1998990'>we're
  going to</span> <span m='1999447'>propagate that</span> <span m='1999904'>value</span>
  <span m='2000361'>up.</span> <span m='2000820'>And</span> <span m='2001630'>we're</span>
  <span m='2001720'>going</span> <span m='2001930'>to</span> <span m='2002170'>start</span>
  <span m='2002440'>the algorithm</span> <span m='2002810'>again.</span> <span m='2004420'>And</span>
  <span m='2004690'>it's</span> <span m='2004830'>going</span> <span m='2005040'>to</span>
  <span m='2005370'>compare between these</span> <span m='2005700'>three.</span> </p><p><span
  m='2006430'>And</span> <span m='2006730'>now</span> <span m='2007120'>it's</span>
  <span m='2007270'>going</span> <span m='2007550'>to</span> <span m='2007620'>pick</span>
  <span m='2008260'>the</span> <span m='2008420'>one</span> <span m='2009010'>on</span>
  <span m='2011170'>the</span> <span m='2011230'>left.</span> <span m='2014686'>Now
  that</span> <span m='2015182'>it picked the</span> <span m='2015680'>one on the</span>
  <span m='2015980'>left,</span> <span m='2016310'>it going to</span> <span m='2016500'>compare</span>
  <span m='2016750'>between</span> <span m='2016930'>these</span> <span m='2017140'>two</span>
  <span m='2017260'>states.</span> <span m='2019420'>Which</span> <span m='2019800'>of
  the</span> <span m='2020170'>two</span> <span m='2020360'>is</span> <span m='2020500'>going</span>
  <span m='2020620'>to</span> <span m='2020680'>have</span> <span m='2020890'>a</span>
  <span m='2020950'>higher</span> <span m='2021310'>expansion</span> <span m='2022210'>factor?</span>
  </p><p><span m='2023933'>AUDIENCE:</span> <span m='2024178'>The</span> <span m='2024424'>left.</span>
  </p><p><span m='2026880'>AUDIENCE:</span> <span m='2026940'>Don't</span> <span m='2027000'>you</span>
  <span m='2027060'>invert it,</span> <span m='2027480'>though,</span> <span m='2027980'>because
  this</span> <span m='2028480'>is</span> <span m='2028980'>the opponent.</span> </p><p><span
  m='2029280'>PROFESSOR 3:</span> <span m='2029430'>Exactly.</span> <span m='2030480'>Because</span>
  <span m='2030960'>two</span> <span m='2031350'>out of</span> <span m='2031470'>three</span>
  <span m='2032000'>is</span> <span m='2032100'>actually</span> <span m='2032340'>better.</span>
  <span m='2032610'>Because</span> <span m='2032790'>it's</span> <span m='2032910'>one</span>
  <span m='2033090'>out</span> <span m='2033180'>of</span> <span m='2033270'>three</span>
  <span m='2033510'>for</span> <span m='2033680'>the</span> <span m='2033820'>opponent</span>
  <span m='2034247'>that's currently making the</span> <span m='2034674'>move.</span>
  <span m='2035530'>So</span> <span m='2035900'>the one</span> <span m='2036100'>on</span>
  <span m='2036180'>the</span> <span m='2036240'>left</span> <span m='2036470'>is</span>
  <span m='2036550'>going</span> <span m='2036650'>to</span> <span m='2036700'>have</span>
  <span m='2036900'>a</span> <span m='2036970'>higher</span> <span m='2037180'>expansion</span>
  <span m='2037440'>factor,</span> <span m='2037860'>and</span> <span m='2038060'>the
  one on</span> <span m='2038210'>the</span> <span m='2038280'>right</span> <span
  m='2038370'>is going to have</span> <span m='2038830'>a higher</span> <span m='2039030'>exploration</span>
  <span m='2039270'>factor.</span> <span m='2039560'>Does that</span> <span m='2040023'>make
  sense for</span> <span m='2040486'>people?</span> <span m='2041412'>It's</span>
  <span m='2041875'>OK</span> <span m='2042338'>if it doesn't.</span> </p><p><span
  m='2045590'>So</span> <span m='2046200'>we're</span> <span m='2046430'>actually</span>
  <span m='2046630'>going to</span> <span m='2046730'>pick the</span> <span m='2046960'>one
  on the</span> <span m='2047060'>right</span> <span m='2047280'>because</span> <span
  m='2047700'>the</span> <span m='2047870'>other one</span> <span m='2048290'>was</span>
  <span m='2048480'>is doing</span> <span m='2048690'>three</span> <span m='2049020'>and</span>
  <span m='2049510'>has</span> <span m='2049710'>lots</span> <span m='2049969'>of</span>
  <span m='2050330'>it's</span> <span m='2050540'>mother's</span> <span m='2050800'>love</span>
  <span m='2051000'>than</span> <span m='2051497'>that one's.</span> <span m='2051994'>Anyone
  else</span> <span m='2052491'>need a drink?</span> <span m='2054239'>We're</span>
  <span m='2054629'>going</span> <span m='2055020'>to</span> <span m='2055080'>expand
  that</span> <span m='2055335'>node. It</span> <span m='2055590'>doesn't</span> <span
  m='2055860'>matter.</span> <span m='2056370'>They are</span> <span m='2056550'>both</span>
  <span m='2056940'>equally</span> <span m='2057170'>likely</span> <span m='2057614'>to
  be</span> <span m='2058058'>expanded.</span> </p><p><span m='2058502'>We're going
  to simulate</span> <span m='2058949'>forward,</span> <span m='2059370'>and</span>
  <span m='2059750'>it's going to</span> <span m='2060005'>be one.</span> <span m='2060260'>Which</span>
  <span m='2060320'>means</span> <span m='2060560'>that that</span> <span m='2060719'>was</span>
  <span m='2060840'>probably a</span> <span m='2061170'>wise</span> <span m='2061590'>countermove.</span>
  <span m='2064639'>Yeah.</span> </p><p><span m='2065310'>AUDIENCE:</span> <span m='2065445'>So</span>
  <span m='2065800'>when</span> <span m='2066030'>it's</span> <span m='2066179'>the</span>
  <span m='2066300'>opponent's</span> <span m='2066760'>turn</span> <span m='2066969'>versus</span>
  <span m='2067290'>your</span> <span m='2067650'>turn,</span> <span m='2068010'>the</span>
  <span m='2068310'>exploration</span> <span m='2069030'>factor</span> <span m='2069300'>is</span>
  <span m='2069570'>the</span> <span m='2069659'>same</span> <span m='2069989'>but</span>
  <span m='2070699'>we</span> <span m='2071500'>complement</span> <span m='2071840'>the</span>
  <span m='2072050'>expansion</span> <span m='2072300'>factor,</span> <span m='2072610'>right?</span>
  </p><p><span m='2073770'>PROFESSOR 3:</span> <span m='2074020'>Yes.</span> <span
  m='2074270'>So</span> <span m='2074500'>the</span> <span m='2074699'>key</span>
  <span m='2075000'>here</span> <span m='2075239'>being</span> <span m='2075469'>that</span>
  <span m='2075800'>this</span> <span m='2076460'>takes</span> <span m='2076739'>in</span>
  <span m='2077179'>both</span> <span m='2077619'>the</span> <span m='2078179'>state</span>
  <span m='2078540'>that</span> <span m='2078690'>you're</span> <span m='2078810'>talking</span>
  <span m='2079110'>about</span> <span m='2079710'>and</span> <span m='2079940'>the</span>
  <span m='2080290'>player</span> <span m='2080639'>that you're talking about.</span>
  </p><p><span m='2080870'>AUDIENCE:</span> <span m='2081024'>But</span> <span m='2081179'>regardless</span>
  <span m='2081639'>of</span> <span m='2081699'>the</span> <span m='2081810'>player,</span>
  <span m='2082239'>the</span> <span m='2082380'>exploration</span> <span m='2082929'>factor
  will</span> <span m='2083370'>always</span> <span m='2083719'>be</span> <span m='2084300'>like
  this is.</span> </p><p><span m='2084570'>PROFESSOR 3:</span> <span m='2084705'>Because</span>
  <span m='2084840'>it's</span> <span m='2085139'>only</span> <span m='2085340'>the</span>
  <span m='2085440'>number</span> <span m='2085620'>of</span> <span m='2085710'>visits</span>
  <span m='2085920'>it's.</span> <span m='2086380'>It has</span> <span m='2086679'>nothing</span>
  <span m='2086830'>to do</span> <span m='2087311'>with</span> <span m='2087792'>results</span>
  <span m='2088273'>of</span> <span m='2088754'>exploration.</span> </p><p><span m='2093176'>AUDIENCE:</span>
  <span m='2093408'>If</span> <span m='2093640'>you</span> <span m='2094104'>win</span>
  <span m='2094568'>and you have</span> <span m='2095032'>the</span> <span m='2095496'>plus
  one,</span> <span m='2095960'>double plus</span> <span m='2096130'>one, and</span>
  <span m='2096545'>you've propagated</span> <span m='2096960'>out,</span> <span m='2097375'>but</span>
  <span m='2097790'>I'm</span> <span m='2098000'>wondering--</span> <span m='2100485'>so
  if</span> <span m='2100982'>the</span> <span m='2101480'>opponent</span> <span m='2101730'>wins</span>
  <span m='2102198'>do you</span> <span m='2102666'>also</span> <span m='2103134'>propagate</span>
  <span m='2103602'>out</span> <span m='2104070'>the</span> <span m='2104538'>win</span>
  <span m='2105006'>increment</span> <span m='2105474'>itself?</span> <span m='2108290'>If</span>
  <span m='2108370'>the</span> <span m='2108720'>opponent's</span> <span m='2108870'>winning,</span>
  <span m='2109340'>wouldn't you want to</span> <span m='2109810'>[INAUDIBLE]</span>
  <span m='2110750'>node</span> <span m='2111220'>here?</span> </p><p><span m='2111843'>PROFESSOR
  3:</span> <span m='2112059'>If</span> <span m='2112276'>the</span> <span m='2112710'>opponent</span>
  <span m='2112780'>wins</span> <span m='2113260'>then what</span> <span m='2113450'>you</span>
  <span m='2113530'>do is you</span> <span m='2113600'>propagate</span> <span m='2114090'>up</span>
  <span m='2114300'>a</span> <span m='2114510'>zero.</span> <span m='2114660'>Which</span>
  <span m='2115146'>means</span> <span m='2115632'>that</span> <span m='2117300'>wk</span>
  <span m='2118130'>is</span> <span m='2118230'>not</span> <span m='2118500'>incremented,</span>
  <span m='2119420'>but</span> <span m='2120040'>nk</span> <span m='2120160'>is.</span>
  <span m='2123695'>Have we</span> <span m='2124030'>seen</span> <span m='2124310'>a</span>
  <span m='2124762'>zero</span> <span m='2125214'>yet?</span> <span m='2126580'>There's</span>
  <span m='2126850'>one</span> <span m='2127260'>soon.</span> </p><p><span m='2128440'>But</span>
  <span m='2129000'>the</span> <span m='2129150'>idea</span> <span m='2129480'>is</span>
  <span m='2129720'>that</span> <span m='2130110'>rather</span> <span m='2130410'>than</span>
  <span m='2131170'>subtract</span> <span m='2131440'>or anything,</span> <span m='2131900'>all
  you</span> <span m='2132060'>do</span> <span m='2132500'>is</span> <span m='2132780'>propagate</span>
  <span m='2132900'>up the</span> <span m='2133170'>result of the</span> <span m='2133440'>game,</span>
  <span m='2134010'>which</span> <span m='2134160'>in</span> <span m='2134220'>this</span>
  <span m='2134400'>case</span> <span m='2135450'>is</span> <span m='2135570'>zero.</span>
  <span m='2137820'>Which</span> <span m='2137970'>means</span> <span m='2138210'>that</span>
  <span m='2138630'>all</span> <span m='2138810'>of</span> <span m='2138900'>those</span>
  <span m='2139170'>states</span> <span m='2139360'>seems</span> <span m='2139690'>to</span>
  <span m='2139980'>become more</span> <span m='2140190'>valuable</span> <span m='2140650'>to
  the</span> <span m='2140860'>blue</span> <span m='2141190'>and</span> <span m='2141510'>less
  valuable</span> <span m='2141820'>to the</span> <span m='2142156'>red.</span> <span
  m='2142830'>Because</span> <span m='2143790'>these</span> <span m='2144000'>numbers</span>
  <span m='2144330'>are</span> <span m='2144560'>lower</span> <span m='2144840'>than
  the</span> <span m='2145305'>other ones</span> <span m='2145770'>were.</span> </p><p><span
  m='2146235'>AUDIENCE:</span> <span m='2146467'>OK.</span> </p><p><span m='2150800'>PROFESSOR
  3:</span> <span m='2150870'>So</span> <span m='2150940'>we</span> <span m='2151376'>propagate</span>
  <span m='2151812'>this up</span> <span m='2152250'>and</span> <span m='2153630'>this</span>
  <span m='2153950'>becomes</span> <span m='2154280'>better.</span> <span m='2154580'>What</span>
  <span m='2154920'>we've</span> <span m='2155220'>done</span> <span m='2155430'>here</span>
  <span m='2155710'>is</span> <span m='2155790'>we've</span> <span m='2156210'>figured</span>
  <span m='2156510'>out</span> <span m='2156930'>a</span> <span m='2157000'>theoretical</span>
  <span m='2157500'>countermove</span> <span m='2158480'>to</span> <span m='2158820'>blue</span>
  <span m='2159290'>moving</span> <span m='2159570'>here.</span> <span m='2160440'>That's</span>
  <span m='2160620'>how</span> <span m='2160740'>you</span> <span m='2160800'>should</span>
  <span m='2160950'>think</span> <span m='2161160'>about</span> <span m='2161310'>this</span>
  <span m='2161480'>whole</span> <span m='2161810'>tree.</span> <span m='2162140'>It's</span>
  <span m='2162260'>really</span> <span m='2162620'>a</span> <span m='2162720'>lot</span>
  <span m='2163010'>like</span> <span m='2163300'>the</span> <span m='2163410'>way
  the</span> <span m='2163590'>humans</span> <span m='2164065'>think</span> <span
  m='2164540'>about these things.</span> </p><p><span m='2165440'>If</span> <span
  m='2165620'>I</span> <span m='2165720'>do</span> <span m='2165870'>this,</span>
  <span m='2166810'>then</span> <span m='2167040'>what if they</span> <span m='2167430'>do</span>
  <span m='2167560'>this?</span> <span m='2167950'>Well,</span> <span m='2168180'>then</span>
  <span m='2168380'>I'll</span> <span m='2168480'>do</span> <span m='2168770'>this.</span>
  <span m='2169140'>And</span> <span m='2169320'>I</span> <span m='2169410'>see</span>
  <span m='2169620'>that</span> <span m='2169740'>I'm</span> <span m='2170430'>successful</span>
  <span m='2170730'>when</span> <span m='2171127'>I do</span> <span m='2171524'>that.</span>
  </p><p><span m='2174142'>We're going</span> <span m='2174560'>to</span> <span m='2174920'>look</span>
  <span m='2175200'>again</span> <span m='2175410'>at the</span> <span m='2175770'>top.</span>
  <span m='2176580'>And</span> <span m='2176820'>we're</span> <span m='2177256'>going
  to</span> <span m='2177692'>pick the one</span> <span m='2178130'>on the</span>
  <span m='2178340'>left</span> <span m='2178920'>because</span> <span m='2179280'>it's</span>
  <span m='2179460'>really</span> <span m='2179760'>promising.</span> <span m='2180015'>Five</span>
  <span m='2180270'>out of</span> <span m='2180540'>six</span> <span m='2180790'>is</span>
  <span m='2180990'>a</span> <span m='2181200'>good</span> <span m='2181290'>number.</span>
  <span m='2182130'>And we're going to look at</span> <span m='2182550'>both</span>
  <span m='2182730'>sides.</span> </p><p><span m='2183270'>And</span> <span m='2183480'>which</span>
  <span m='2183640'>one</span> <span m='2183770'>is</span> <span m='2184210'>blue</span>
  <span m='2184380'>going to</span> <span m='2184775'>pick now?</span> <span m='2185960'>Well,</span>
  <span m='2186180'>it's</span> <span m='2186330'>going</span> <span m='2186480'>to</span>
  <span m='2186710'>pick the</span> <span m='2186990'>one that</span> <span m='2187255'>it's
  going to be</span> <span m='2187520'>more</span> <span m='2187700'>successful</span>
  <span m='2188005'>in,</span> <span m='2188310'>which</span> <span m='2188380'>is</span>
  <span m='2188500'>two out of</span> <span m='2188720'>three.</span> <span m='2189090'>I</span>
  <span m='2189460'>realize</span> <span m='2189820'>that</span> <span m='2189890'>this</span>
  <span m='2189990'>is</span> <span m='2190230'>actually</span> <span m='2190560'>not
  the</span> <span m='2190903'>kind of thing</span> <span m='2191246'>where I could</span>
  <span m='2191590'>necessarily</span> <span m='2191950'>ask</span> <span m='2192340'>people</span>
  <span m='2192730'>because</span> <span m='2193120'>I'm the</span> <span m='2193510'>one</span>
  <span m='2193830'>who's</span> <span m='2194090'>decided</span> <span m='2194470'>which</span>
  <span m='2194970'>node</span> <span m='2195470'>to</span> <span m='2195970'>stop.</span>
  </p><p><span m='2197680'>Then</span> <span m='2198070'>we</span> <span m='2198210'>go</span>
  <span m='2198750'>down</span> <span m='2198950'>here.</span> <span m='2199360'>And</span>
  <span m='2199490'>there's</span> <span m='2199940'>an</span> <span m='2200200'>equal</span>
  <span m='2200400'>likelihood</span> <span m='2200900'>of</span> <span m='2201180'>picking</span>
  <span m='2201430'>either</span> <span m='2201680'>of</span> <span m='2201780'>those</span>
  <span m='2201990'>nodes.</span> <span m='2202430'>And so</span> <span m='2202870'>we're
  going to</span> <span m='2202990'>pick one at</span> <span m='2203250'>random.</span>
  <span m='2203510'>So that's</span> <span m='2203680'>going to</span> <span m='2204142'>be
  the</span> <span m='2204604'>left one.</span> </p><p><span m='2205530'>And</span>
  <span m='2206120'>we're</span> <span m='2206270'>going to</span> <span m='2206630'>create</span>
  <span m='2207060'>an</span> <span m='2207120'>empty node.</span> <span m='2207320'>Then</span>
  <span m='2207780'>we're</span> <span m='2207920'>going to</span> <span m='2208040'>play</span>
  <span m='2208300'>it out.</span> <span m='2208560'>And</span> <span m='2208860'>it</span>
  <span m='2209220'>was</span> <span m='2209560'>a</span> <span m='2209926'>success
  for</span> <span m='2210292'>blue, which</span> <span m='2210660'>is</span> <span
  m='2210810'>amazing</span> <span m='2211570'>because</span> <span m='2211860'>what</span>
  <span m='2212010'>this</span> <span m='2212220'>means</span> <span m='2212520'>now</span>
  <span m='2213300'>is</span> <span m='2213390'>that</span> <span m='2213540'>suddenly,</span>
  <span m='2214080'>in</span> <span m='2214470'>this</span> <span m='2214680'>tree</span>
  <span m='2215210'>of</span> <span m='2215530'>this</span> <span m='2215670'>really</span>
  <span m='2215950'>good</span> <span m='2216120'>move</span> <span m='2216370'>that
  red</span> <span m='2216620'>could</span> <span m='2216870'>make</span> <span m='2217180'>the</span>
  <span m='2217620'>blue</span> <span m='2217830'>wasn't</span> <span m='2218010'>find
  a</span> <span m='2218220'>response</span> <span m='2218550'>to,</span> <span m='2218720'>suddenly</span>
  <span m='2219090'>there's</span> <span m='2219300'>hope</span> <span m='2219910'>because</span>
  <span m='2220960'>we're</span> <span m='2221240'>going to</span> <span m='2221410'>propagate
  this</span> <span m='2221540'>back.</span> </p><p><span m='2222280'>And</span> <span
  m='2222420'>that</span> <span m='2222700'>means</span> <span m='2223150'>that</span>
  <span m='2223370'>blue</span> <span m='2223590'>actually</span> <span m='2223830'>has</span>
  <span m='2223980'>a</span> <span m='2224010'>response</span> <span m='2224430'>move</span>
  <span m='2224940'>to</span> <span m='2225360'>that</span> <span m='2225540'>sequence</span>
  <span m='2225990'>of</span> <span m='2226220'>red's</span> <span m='2226370'>moves.</span>
  <span m='2226772'>And so</span> <span m='2227174'>it's going to</span> <span m='2227576'>propagate</span>
  <span m='2227978'>up.</span> <span m='2228380'>And</span> <span m='2228620'>this</span>
  <span m='2228960'>state's</span> <span m='2229130'>going to be more promising to</span>
  <span m='2229610'>blue</span> <span m='2230450'>and</span> <span m='2230560'>less</span>
  <span m='2230915'>promising</span> <span m='2231270'>of</span> <span m='2231560'>red.</span>
  <span m='2232350'>That</span> <span m='2232530'>region</span> <span m='2232750'>of</span>
  <span m='2232980'>the</span> <span m='2233270'>tree</span> <span m='2233530'>that
  we</span> <span m='2233790'>had dug</span> <span m='2234050'>into</span> <span m='2234230'>is
  a</span> <span m='2234360'>little</span> <span m='2234890'>less</span> <span m='2236630'>promising.</span>
  </p><p><span m='2237460'>We're going to</span> <span m='2237690'>look</span> <span
  m='2237870'>back</span> <span m='2238110'>up.</span> <span m='2238330'>And</span>
  <span m='2238470'>this</span> <span m='2238650'>time,</span> <span m='2239030'>instead,</span>
  <span m='2239390'>we're</span> <span m='2239520'>going</span> <span m='2239730'>to</span>
  <span m='2240250'>evaluate</span> <span m='2240490'>the</span> <span m='2240580'>thing</span>
  <span m='2240840'>that</span> <span m='2240990'>is</span> <span m='2241710'>both</span>
  <span m='2242080'>promising</span> <span m='2242880'>from</span> <span m='2243410'>the</span>
  <span m='2244440'>expansion</span> <span m='2244830'>factor,</span> <span m='2245380'>and</span>
  <span m='2245600'>also</span> <span m='2245910'>promising</span> <span m='2246360'>because</span>
  <span m='2247020'>we</span> <span m='2247110'>haven't</span> <span m='2247590'>looked</span>
  <span m='2247800'>at</span> <span m='2247890'>it</span> <span m='2247960'>very</span>
  <span m='2248325'>much</span> <span m='2248690'>[INAUDIBLE]</span> <span m='2248800'>exploration</span>
  <span m='2249176'>factor.</span> <span m='2249930'>We're going to</span> <span m='2250120'>pick
  between</span> <span m='2250350'>these</span> <span m='2250620'>two.</span> <span
  m='2251100'>Which</span> <span m='2251280'>one</span> <span m='2251400'>is</span>
  <span m='2251520'>going</span> <span m='2251600'>to be</span> <span m='2251750'>picked</span>
  <span m='2251940'>here?</span> </p><p><span m='2253589'>AUDIENCE:</span> <span m='2253830'>[INAUDIBLE]</span>
  </p><p><span m='2257453'>PROFESSOR 3:</span> <span m='2257696'>Because</span> <span
  m='2257940'>the</span> <span m='2258670'>exploration</span> <span m='2259090'>factor
  is</span> <span m='2259430'>the</span> <span m='2259550'>same but the</span> <span
  m='2259950'>expansion</span> <span m='2260290'>factor</span> <span m='2261020'>is</span>
  <span m='2261230'>higher</span> <span m='2261580'>for the</span> <span m='2261930'>one
  on</span> <span m='2262110'>the</span> <span m='2262220'>left.</span> <span m='2264080'>And</span>
  <span m='2264350'>it's</span> <span m='2264450'>going to</span> <span m='2264740'>show
  us a</span> <span m='2264980'>node.</span> <span m='2265700'>And</span> <span m='2266110'>the</span>
  <span m='2266350'>result is</span> <span m='2266510'>going</span> <span m='2266630'>to</span>
  <span m='2266690'>be</span> <span m='2267500'>a</span> <span m='2267590'>win</span>
  <span m='2267800'>for</span> <span m='2267930'>a</span> <span m='2267950'>red,</span>
  <span m='2268610'>which</span> <span m='2268880'>means that</span> <span m='2269030'>red</span>
  <span m='2269450'>has found a</span> <span m='2269530'>good</span> <span m='2269730'>countermove</span>
  <span m='2270380'>to</span> <span m='2270710'>the</span> <span m='2270800'>thing
  that</span> <span m='2271190'>was</span> <span m='2271380'>previously</span> <span
  m='2271650'>promising</span> <span m='2271840'>for</span> <span m='2272300'>blue.</span>
  <span m='2272760'>And we propagate it back</span> <span m='2273220'>up.</span> </p><p><span
  m='2273680'>And</span> <span m='2274280'>finally,</span> <span m='2275920'>we're</span>
  <span m='2276000'>going</span> <span m='2276130'>to</span> <span m='2276340'>pick</span>
  <span m='2276520'>the one</span> <span m='2276870'>furthest on the</span> <span
  m='2277340'>right.</span> <span m='2277730'>Because</span> <span m='2277970'>even</span>
  <span m='2278120'>though</span> <span m='2278240'>it's</span> <span m='2278390'>terrible</span>
  <span m='2278810'>for</span> <span m='2279260'>red,</span> <span m='2279360'>and
  even</span> <span m='2279480'>though</span> <span m='2279630'>it's</span> <span
  m='2279810'>never won when</span> <span m='2280160'>it's tried</span> <span m='2280460'>it,</span>
  <span m='2280950'>it</span> <span m='2281090'>has</span> <span m='2281390'>to</span>
  <span m='2281680'>obey</span> <span m='2281950'>his</span> <span m='2282130'>idea</span>
  <span m='2282460'>of</span> <span m='2282560'>the</span> <span m='2283860'>exploration</span>
  <span m='2284170'>mode</span> <span m='2284630'>to</span> <span m='2284810'>find</span>
  <span m='2285020'>out</span> <span m='2285120'>whether</span> <span m='2285320'>maybe</span>
  <span m='2285590'>there</span> <span m='2285740'>isn't</span> <span m='2285880'>something</span>
  <span m='2285990'>possible</span> <span m='2286340'>there.</span> <span m='2286910'>So
  it</span> <span m='2287260'>explores,</span> <span m='2288240'>and</span> <span
  m='2288480'>it</span> <span m='2288560'>goes</span> <span m='2288800'>down,</span>
  <span m='2289110'>and</span> <span m='2289220'>it</span> <span m='2289310'>has</span>
  <span m='2289560'>to</span> <span m='2289640'>pick</span> <span m='2289960'>the
  one on</span> <span m='2290080'>the</span> <span m='2290475'>right.</span> <span
  m='2290870'>And</span> <span m='2291080'>so it</span> <span m='2291290'>does.</span>
  </p><p><span m='2292090'>And it</span> <span m='2292390'>plays</span> <span m='2292570'>this
  game</span> <span m='2292800'>out.</span> <span m='2293420'>And</span> <span m='2293600'>it's</span>
  <span m='2293690'>a</span> <span m='2293780'>loss,</span> <span m='2294620'>again.</span>
  <span m='2296180'>Which</span> <span m='2296870'>goes</span> <span m='2297080'>to</span>
  <span m='2297140'>show</span> <span m='2297310'>you,</span> <span m='2297890'>that</span>
  <span m='2298940'>blue</span> <span m='2299310'>has</span> <span m='2299580'>found
  yet</span> <span m='2299760'>another</span> <span m='2300015'>superior</span> <span
  m='2300270'>move</span> <span m='2300670'>to</span> <span m='2300800'>this</span>
  <span m='2300980'>really</span> <span m='2301220'>bad</span> <span m='2301440'>move
  of</span> <span m='2301640'>red,</span> <span m='2302350'>where</span> <span m='2302570'>probably</span>
  <span m='2302875'>this</span> <span m='2303180'>move</span> <span m='2303380'>of
  red,</span> <span m='2303870'>if this is</span> <span m='2304070'>a game</span>
  <span m='2304320'>of</span> <span m='2304610'>chess,</span> <span m='2305015'>is
  like</span> <span m='2305420'>putting my queen</span> <span m='2305780'>directly</span>
  <span m='2306260'>in</span> <span m='2306320'>front</span> <span m='2306560'>of</span>
  <span m='2306650'>the</span> <span m='2306920'>opponent's</span> <span m='2307185'>row</span>
  <span m='2307450'>of pawns,</span> <span m='2307720'>and</span> <span m='2307870'>I
  just</span> <span m='2308110'>leave</span> <span m='2308280'>it there.</span> <span
  m='2309230'>There's</span> <span m='2309530'>nothing</span> <span m='2309865'>good
  that's</span> <span m='2310200'>ever</span> <span m='2310510'>going to</span> <span
  m='2310650'>come</span> <span m='2310760'>of it</span> <span m='2311110'>but</span>
  <span m='2311330'>we</span> <span m='2311480'>have</span> <span m='2311600'>to</span>
  <span m='2311900'>explore it</span> <span m='2312330'>just</span> <span m='2312530'>to</span>
  <span m='2312650'>find</span> <span m='2312890'>out</span> <span m='2313070'>whether</span>
  <span m='2313610'>there</span> <span m='2313700'>isn't</span> <span m='2313940'>some</span>
  <span m='2314140'>magical</span> <span m='2314410'>way</span> <span m='2314650'>that
  I</span> <span m='2314750'>should</span> <span m='2315135'>protect.</span> </p><p><span
  m='2316290'>And</span> <span m='2316910'>as</span> <span m='2317060'>you</span>
  <span m='2317120'>can</span> <span m='2317210'>see,</span> <span m='2317820'>we've</span>
  <span m='2318110'>built</span> <span m='2318260'>up</span> <span m='2318350'>this</span>
  <span m='2318530'>tree</span> <span m='2319250'>over</span> <span m='2319500'>and</span>
  <span m='2319580'>over and over</span> <span m='2320000'>again.</span> <span m='2320460'>And
  it's</span> <span m='2320580'>starting</span> <span m='2320800'>to</span> <span
  m='2321050'>look</span> <span m='2321290'>asymmetric.</span> <span m='2321970'>And</span>
  <span m='2322070'>we're</span> <span m='2322160'>starting</span> <span m='2322400'>to</span>
  <span m='2322490'>see</span> <span m='2322760'>that</span> <span m='2322880'>there's</span>
  <span m='2323120'>really</span> <span m='2323420'>this</span> <span m='2324080'>disparity</span>
  <span m='2324890'>between</span> <span m='2325685'>exploring</span> <span m='2326030'>the</span>
  <span m='2326120'>regions</span> <span m='2326560'>that are</span> <span m='2326720'>crossing</span>
  <span m='2327170'>this</span> <span m='2327260'>tree</span> <span m='2327920'>and</span>
  <span m='2328010'>exploring</span> <span m='2328430'>the</span> <span m='2328490'>regions</span>
  <span m='2328880'>that</span> <span m='2328970'>are</span> <span m='2329060'>not</span>
  <span m='2329420'>and</span> <span m='2329560'>that</span> <span m='2329660'>don't</span>
  <span m='2329870'>really</span> <span m='2330020'>matter</span> <span m='2330290'>to</span>
  <span m='2330630'>us</span> <span m='2331310'>very</span> <span m='2331520'>much.</span>
  <span m='2332500'>And</span> <span m='2332720'>that</span> <span m='2333200'>this</span>
  <span m='2333380'>is</span> <span m='2333470'>exactly</span> <span m='2333860'>what</span>
  <span m='2334250'>we</span> <span m='2334672'>wanted</span> <span m='2335094'>from</span>
  <span m='2335516'>Monte Carlo trees.</span> <span m='2335940'>That</span> <span
  m='2336110'>was</span> <span m='2336440'>why</span> <span m='2336705'>we</span>
  <span m='2336970'>started</span> <span m='2337210'>the</span> <span m='2337330'>whole</span>
  <span m='2338320'>endeavor in</span> <span m='2338630'>the first</span> <span m='2338750'>place.</span>
  </p><p><span m='2340612'>The</span> <span m='2340970'>next thing</span> <span m='2341180'>I'm
  going to</span> <span m='2341450'>talk</span> <span m='2341630'>about</span> <span
  m='2341780'>is the</span> <span m='2341900'>pros and</span> <span m='2342320'>cons.</span>
  <span m='2342530'>But before</span> <span m='2342785'>I do</span> <span m='2343040'>that,</span>
  <span m='2343360'>does</span> <span m='2343540'>anyone</span> <span m='2343700'>have</span>
  <span m='2343910'>any more</span> <span m='2344120'>questions</span> <span m='2344480'>about</span>
  <span m='2344630'>the</span> <span m='2344680'>algorithm?</span> <span m='2346810'>Yeah.</span>
  </p><p><span m='2347270'>AUDIENCE:</span> <span m='2347345'>It's</span> <span m='2347420'>still</span>
  <span m='2347750'>not</span> <span m='2347960'>clear</span> <span m='2348350'>how</span>
  <span m='2348610'>we're</span> <span m='2349062'>getting</span> <span m='2349514'>nodes</span>
  <span m='2349966'>with</span> <span m='2350418'>different</span> <span m='2350870'>denominators--</span>
  <span m='2351322'>[INAUDIBLE]</span> </p><p><span m='2353500'>PROFESSOR 3:</span>
  <span m='2353575'>The</span> <span m='2353650'>reason</span> <span m='2354070'>for</span>
  <span m='2354340'>that</span> <span m='2354610'>is</span> <span m='2355540'>because</span>
  <span m='2355870'>of</span> <span m='2355930'>the</span> <span m='2356020'>way</span>
  <span m='2356210'>that we're</span> <span m='2356300'>simulating</span> <span m='2356850'>through.</span>
  <span m='2357260'>We're</span> <span m='2357760'>actually</span> <span m='2358660'>not</span>
  <span m='2358870'>holding</span> <span m='2359200'>onto</span> <span m='2359450'>to</span>
  <span m='2359650'>the</span> <span m='2359710'>results</span> <span m='2359970'>of</span>
  <span m='2360350'>the</span> <span m='2360470'>simulation</span> <span m='2360785'>as</span>
  <span m='2361100'>we're</span> <span m='2361480'>going</span> <span m='2361930'>farther</span>
  <span m='2362330'>down</span> <span m='2362640'>the</span> <span m='2362950'>tree</span>
  <span m='2363130'>than</span> <span m='2363370'>the</span> <span m='2363810'>lowest</span>
  <span m='2364250'>node</span> <span m='2364690'>we expand.</span> </p><p><span m='2365200'>For</span>
  <span m='2365410'>example,</span> <span m='2365590'>when</span> <span m='2365700'>you</span>
  <span m='2365840'>simulate from</span> <span m='2366200'>here,</span> <span m='2367540'>you're</span>
  <span m='2367690'>going</span> <span m='2367960'>to</span> <span m='2368340'>propagate</span>
  <span m='2368560'>that</span> <span m='2368940'>value</span> <span m='2369320'>here</span>
  <span m='2369630'>and</span> <span m='2369760'>here,</span> <span m='2369970'>and</span>
  <span m='2370060'>so</span> <span m='2370180'>on.</span> <span m='2371030'>But</span>
  <span m='2371080'>then</span> <span m='2371410'>when we</span> <span m='2371490'>expand</span>
  <span m='2371830'>below,</span> <span m='2372460'>even</span> <span m='2372800'>if</span>
  <span m='2373230'>in the</span> <span m='2373450'>course of</span> <span m='2373870'>this</span>
  <span m='2374030'>guy's</span> <span m='2374330'>simulation</span> <span m='2375110'>it</span>
  <span m='2375250'>happened</span> <span m='2375530'>to</span> <span m='2375640'>go</span>
  <span m='2375820'>through</span> <span m='2375990'>one of</span> <span m='2376020'>the</span>
  <span m='2376210'>states</span> <span m='2376300'>that</span> <span m='2376480'>we</span>
  <span m='2376880'>expanded</span> <span m='2377030'>below,</span> <span m='2377310'>it</span>
  <span m='2377620'>will</span> <span m='2377920'>not</span> <span m='2378160'>have</span>
  <span m='2378690'>incremented</span> <span m='2379250'>the values of that</span>
  <span m='2379630'>state</span> <span m='2380140'>because</span> <span m='2380320'>we</span>
  <span m='2380410'>weren't</span> <span m='2380680'>keeping</span> <span m='2380940'>track
  of</span> <span m='2381150'>it.</span> <span m='2383160'>Theoretically,</span> <span
  m='2383640'>if we were</span> <span m='2383910'>to keep</span> <span m='2384210'>track</span>
  <span m='2384570'>of</span> <span m='2384910'>all</span> <span m='2385140'>of</span>
  <span m='2385190'>the</span> <span m='2385370'>simulations</span> <span m='2385650'>that</span>
  <span m='2385880'>we</span> <span m='2385940'>have in</span> <span m='2386180'>fact</span>
  <span m='2386480'>run,</span> <span m='2387050'>the</span> <span m='2387140'>numbers</span>
  <span m='2387460'>beneath</span> <span m='2387830'>these</span> <span m='2388010'>things</span>
  <span m='2388640'>would</span> <span m='2388770'>be</span> <span m='2388920'>higher.</span>
  </p><p><span m='2391480'>AUDIENCE:</span> <span m='2391633'>If</span> <span m='2391786'>you've</span>
  <span m='2391940'>already</span> <span m='2392400'>run a</span> <span m='2392700'>simulation</span>
  <span m='2393104'>from</span> <span m='2393508'>that--</span> <span m='2394316'>if</span>
  <span m='2394720'>you've</span> <span m='2394810'>already run</span> <span m='2395130'>a
  simulation</span> <span m='2395530'>from</span> <span m='2395770'>that</span> <span
  m='2395920'>red</span> <span m='2396352'>node</span> <span m='2396784'>when you</span>
  <span m='2397216'>first built it,</span> <span m='2398080'>and</span> <span m='2398390'>then</span>
  <span m='2399530'>when</span> <span m='2399610'>you</span> <span m='2399730'>created</span>
  <span m='2400060'>those</span> <span m='2400544'>two ones,</span> <span m='2401028'>each</span>
  <span m='2401512'>of those</span> <span m='2401996'>have</span> <span m='2402480'>[INAUDIBLE]</span>
  </p><p><span m='2403386'>PROFESSOR 3:</span> <span m='2403604'>OK.</span> <span
  m='2403822'>I</span> <span m='2404260'>see.</span> </p><p><span m='2404520'>AUDIENCE:</span>
  <span m='2404732'>So</span> <span m='2404945'>would the denominator</span> <span
  m='2405370'>always</span> <span m='2405640'>be</span> <span m='2405940'>one</span>
  <span m='2406240'>more</span> <span m='2406570'>than</span> <span m='2406720'>the
  sum</span> <span m='2406990'>of</span> <span m='2407080'>the</span> <span m='2407140'>children?</span>
  </p><p><span m='2408100'>PROFESSOR 3:</span> <span m='2408155'>Yeah,</span> <span
  m='2408210'>in</span> <span m='2408641'>[INAUDIBLE]</span> <span m='2410800'>Yeah.</span>
  </p><p><span m='2414020'>AUDIENCE:</span> <span m='2414145'>I</span> <span m='2414270'>understand</span>
  <span m='2414396'>how you</span> <span m='2414772'>built</span> <span m='2415150'>that.</span>
  <span m='2418304'>Is there</span> <span m='2418801'>a rule of</span> <span m='2419300'>thumb,
  like</span> <span m='2419770'>it's</span> <span m='2420100'>time</span> <span m='2420320'>to
  choose</span> <span m='2420520'>a</span> <span m='2420610'>move?</span> <span m='2420900'>And</span>
  <span m='2421265'>it seems</span> <span m='2421630'>like</span> <span m='2421840'>you
  have</span> <span m='2422140'>very</span> <span m='2422500'>low</span> <span m='2422650'>numbers</span>
  <span m='2422890'>here</span> <span m='2423150'>to</span> <span m='2423360'>make</span>
  <span m='2423805'>a</span> <span m='2424250'>[INAUDIBLE]</span> </p><p><span m='2425080'>Is
  there</span> <span m='2425500'>a</span> <span m='2425920'>rule</span> <span m='2426130'>of
  thumb on</span> <span m='2426450'>giving</span> <span m='2426770'>games</span> <span
  m='2427000'>like</span> <span m='2427425'>it's</span> <span m='2427850'>2 to the
  4</span> <span m='2428275'>or 2 to</span> <span m='2428700'>the</span> <span m='2429125'>350,
  whatever it is.</span> <span m='2429550'>What</span> <span m='2429760'>kind</span>
  <span m='2429970'>of</span> <span m='2430080'>numbers</span> <span m='2430360'>do
  you</span> <span m='2430860'>need</span> <span m='2431030'>for</span> <span m='2431376'>that</span>
  <span m='2431722'>first</span> <span m='2432070'>row</span> <span m='2432335'>before</span>
  <span m='2432600'>you</span> <span m='2432936'>[INAUDIBLE]?</span> </p><p><span
  m='2435582'>PROFESSOR 3:</span> <span m='2435793'>What</span> <span m='2436005'>we'll
  get to soon is</span> <span m='2436430'>that</span> <span m='2436780'>isn't</span>
  <span m='2436950'>one.</span> <span m='2438010'>That's</span> <span m='2438230'>one
  of</span> <span m='2438340'>the</span> <span m='2438430'>problem</span> <span m='2438670'>with</span>
  <span m='2438810'>MCTS.</span> <span m='2440750'>But</span> <span m='2441640'>in</span>
  <span m='2441730'>terms</span> <span m='2441970'>of</span> <span m='2442150'>which</span>
  <span m='2442360'>of</span> <span m='2442450'>the</span> <span m='2442570'>moves
  you</span> <span m='2443040'>will</span> <span m='2443240'>choose,</span> <span
  m='2444210'>there</span> <span m='2444940'>are</span> <span m='2445090'>actually</span>
  <span m='2445550'>variants of</span> <span m='2445810'>MCTS</span> <span m='2446620'>that</span>
  <span m='2446930'>suggest</span> <span m='2447430'>that</span> <span m='2447730'>you</span>
  <span m='2448030'>more</span> <span m='2448350'>selectively</span> <span m='2448960'>age</span>
  <span m='2449360'>or</span> <span m='2449570'>insert new</span> <span m='2449920'>children</span>
  <span m='2450970'>based</span> <span m='2451480'>on</span> <span m='2451630'>something</span>
  <span m='2451990'>more</span> <span m='2452320'>than</span> <span m='2453070'>just</span>
  <span m='2453850'>the</span> <span m='2454650'>blind</span> <span m='2455610'>look</span>
  <span m='2455960'>right</span> <span m='2456120'>now.</span> <span m='2456430'>In</span>
  <span m='2456590'>terms</span> <span m='2456890'>of,</span> <span m='2457990'>if
  I'm</span> <span m='2458460'>here</span> <span m='2458770'>and it's</span> <span
  m='2459180'>creating</span> <span m='2459790'>my</span> <span m='2460020'>next children</span>
  <span m='2460320'>as</span> <span m='2460640'>the</span> <span m='2461053'>equivalent,</span>
  <span m='2461466'>then</span> <span m='2461880'>there</span> <span m='2462010'>are</span>
  <span m='2462160'>some</span> <span m='2462340'>intelligent</span> <span m='2462910'>guesses</span>
  <span m='2463240'>that you can make</span> <span m='2463716'>in terms of</span>
  <span m='2464192'>which one you should</span> <span m='2464668'>score</span> <span
  m='2465144'>first.</span> <span m='2466096'>Although it</span> <span m='2466572'>doesn't</span>
  <span m='2467050'>particularly matter.</span> </p><p><span m='2467340'>AUDIENCE:</span>
  <span m='2467435'>I'm</span> <span m='2467530'>just</span> <span m='2467700'>saying</span>
  <span m='2468160'>computational</span> <span m='2468820'>time</span> <span m='2469540'>being</span>
  <span m='2469750'>what</span> <span m='2469870'>it</span> <span m='2469990'>is,</span>
  <span m='2470380'>you</span> <span m='2470500'>might</span> <span m='2470740'>say,</span>
  <span m='2470980'>OK,</span> <span m='2471400'>if this</span> <span m='2471610'>is</span>
  <span m='2471730'>the</span> <span m='2471860'>timeline</span> <span m='2472270'>of</span>
  <span m='2472370'>this</span> <span m='2472590'>game</span> <span m='2473230'>I</span>
  <span m='2473350'>can</span> <span m='2473480'>expect</span> <span m='2473860'>to</span>
  <span m='2473980'>do</span> <span m='2474280'>a million</span> <span m='2474680'>simulations,</span>
  <span m='2475080'>which will</span> <span m='2475480'>give</span> <span m='2475870'>me</span>
  <span m='2476380'>if</span> <span m='2476500'>there's</span> <span m='2476720'>400</span>
  <span m='2477120'>nodes,</span> <span m='2477580'>I'm</span> <span m='2477780'>going
  to have</span> <span m='2478060'>so</span> <span m='2478102'>much</span> <span m='2478230'>use.</span>
  <span m='2478440'>In</span> <span m='2478885'>other words,</span> <span m='2480040'>is</span>
  <span m='2480260'>that</span> <span m='2480430'>enough</span> <span m='2480870'>time</span>
  <span m='2481310'>to say that</span> <span m='2481550'>I</span> <span m='2481936'>can</span>
  <span m='2482322'>play</span> <span m='2482710'>through a game?</span> <span m='2482970'>I</span>
  <span m='2483235'>couldn't</span> <span m='2483500'>play</span> <span m='2483720'>through
  a</span> <span m='2483820'>game</span> <span m='2484210'>with</span> <span m='2484600'>400</span>
  <span m='2484690'>options</span> <span m='2484920'>if</span> <span m='2485270'>I've</span>
  <span m='2485520'>gotten</span> <span m='2485760'>five</span> <span m='2486156'>out
  of</span> <span m='2486552'>seven</span> <span m='2486950'>[INAUDIBLE]</span> <span
  m='2487120'>three out of</span> <span m='2487476'>four</span> <span m='2487832'>[INAUDIBLE]</span>
  </p><p><span m='2488190'>PROFESSOR 3:</span> <span m='2488270'>Absolutely.</span>
  <span m='2488350'>And I</span> <span m='2488440'>would</span> <span m='2488590'>say</span>
  <span m='2488860'>that</span> <span m='2490030'>so</span> <span m='2490180'>far</span>
  <span m='2490330'>as</span> <span m='2490450'>I</span> <span m='2490570'>know,</span>
  <span m='2490810'>that's</span> <span m='2490960'>something</span> <span m='2491370'>that's</span>
  <span m='2491610'>basically</span> <span m='2492020'>very</span> <span m='2492260'>high</span>
  <span m='2492678'>experimentally.</span> <span m='2493096'>They</span> <span m='2493235'>don't</span>
  <span m='2493374'>have</span> <span m='2493514'>good</span> <span m='2493932'>balance</span>
  <span m='2494350'>on it.</span> <span m='2494770'>[INAUDIBLE]</span> </p><p><span
  m='2495830'>So</span> <span m='2495980'>let's</span> <span m='2496100'>get</span>
  <span m='2496290'>on the</span> <span m='2496500'>first</span> <span m='2496810'>comment</span>
  <span m='2497020'>because</span> <span m='2497110'>that is</span> <span m='2497230'>a</span>
  <span m='2497350'>computer</span> <span m='2497730'>element.</span> <span m='2499070'>So</span>
  <span m='2499270'>why</span> <span m='2499570'>should</span> <span m='2499840'>you</span>
  <span m='2500020'>use</span> <span m='2500260'>this</span> <span m='2502090'>algorithm?</span>
  <span m='2502360'>Even</span> <span m='2502700'>though</span> <span m='2502910'>we've</span>
  <span m='2503060'>seen</span> <span m='2503260'>tremendous</span> <span m='2503710'>breakthroughs</span>
  <span m='2503920'>in</span> <span m='2504040'>this</span> <span m='2504340'>algorithm,</span>
  <span m='2505195'>and</span> <span m='2505630'>you're</span> <span m='2505780'>going</span>
  <span m='2505910'>to</span> <span m='2505970'>have</span> <span m='2506080'>to</span>
  <span m='2506170'>ignore</span> <span m='2506425'>everything</span> <span m='2506680'>that</span>
  <span m='2506960'>I tell</span> <span m='2507240'>you</span> <span m='2507440'>and</span>
  <span m='2507695'>remember</span> <span m='2507950'>that this</span> <span m='2508330'>does</span>
  <span m='2508610'>actually</span> <span m='2509020'>work</span> <span m='2509220'>quite</span>
  <span m='2509690'>well in certain</span> <span m='2510160'>scenarios.</span> <span
  m='2511540'>Should</span> <span m='2511770'>we use</span> <span m='2512225'>it</span>
  <span m='2512680'>or not?</span> </p><p><span m='2513920'>The</span> <span m='2514410'>pros</span>
  <span m='2514810'>are</span> <span m='2515060'>that it</span> <span m='2515300'>actually</span>
  <span m='2515690'>does</span> <span m='2515890'>the thing</span> <span m='2516307'>that
  we</span> <span m='2516724'>want it to do.</span> <span m='2517141'>It</span> <span
  m='2517560'>grows the</span> <span m='2517700'>tree</span> <span m='2517990'>asymmetrically.</span>
  <span m='2518360'>It means</span> <span m='2518835'>that we</span> <span m='2519310'>do
  not</span> <span m='2519790'>have to</span> <span m='2519890'>explore.</span> <span
  m='2520380'>And</span> <span m='2520480'>it</span> <span m='2520580'>doesn't</span>
  <span m='2521290'>explode</span> <span m='2521710'>exponentially</span> <span m='2522340'>with</span>
  <span m='2522490'>the</span> <span m='2524320'>number</span> <span m='2524590'>of</span>
  <span m='2524650'>moves</span> <span m='2524920'>that</span> <span m='2525040'>we're</span>
  <span m='2525160'>looking</span> <span m='2525470'>into</span> <span m='2525530'>the</span>
  <span m='2525800'>future.</span> <span m='2526070'>And</span> <span m='2526170'>that</span>
  <span m='2526290'>it</span> <span m='2526740'>selectively</span> <span m='2527060'>grows</span>
  <span m='2527500'>the</span> <span m='2527560'>tree</span> <span m='2527930'>towards</span>
  <span m='2528070'>the</span> <span m='2528220'>areas</span> <span m='2528500'>that</span>
  <span m='2528590'>are most</span> <span m='2528870'>promising.</span> </p><p><span
  m='2531050'>The</span> <span m='2531240'>other</span> <span m='2531570'>huge</span>
  <span m='2532020'>benefit,</span> <span m='2532470'>if</span> <span m='2532920'>you'll</span>
  <span m='2533010'>notice</span> <span m='2533540'>from</span> <span m='2533780'>what
  we've</span> <span m='2534110'>just</span> <span m='2534330'>talked</span> <span
  m='2534810'>through,</span> <span m='2535290'>is that</span> <span m='2535500'>it</span>
  <span m='2535660'>never</span> <span m='2536020'>relies</span> <span m='2536650'>on</span>
  <span m='2536830'>anything</span> <span m='2537220'>other</span> <span m='2537430'>than</span>
  <span m='2537580'>the</span> <span m='2537670'>strict</span> <span m='2537970'>rules</span>
  <span m='2538230'>of the</span> <span m='2538675'>game.</span> <span m='2539120'>What
  that</span> <span m='2539200'>means</span> <span m='2539500'>is</span> <span m='2539590'>that</span>
  <span m='2539710'>the</span> <span m='2539890'>only</span> <span m='2540460'>weight</span>
  <span m='2540650'>of the</span> <span m='2540880'>game</span> <span m='2541240'>that's</span>
  <span m='2541555'>factored</span> <span m='2541870'>in</span> <span m='2542260'>is</span>
  <span m='2542350'>that</span> <span m='2542470'>the</span> <span m='2542560'>game</span>
  <span m='2542830'>is</span> <span m='2542950'>what</span> <span m='2543100'>tells</span>
  <span m='2543400'>us</span> <span m='2543580'>what</span> <span m='2543820'>the</span>
  <span m='2543940'>next</span> <span m='2544210'>moves</span> <span m='2544540'>we</span>
  <span m='2544660'>can</span> <span m='2544810'>take</span> <span m='2545020'>from</span>
  <span m='2545190'>a given</span> <span m='2545440'>state</span> <span m='2545690'>are,</span>
  <span m='2546120'>and</span> <span m='2547810'>whether</span> <span m='2548290'>a</span>
  <span m='2548380'>given</span> <span m='2548680'>state</span> <span m='2549160'>is</span>
  <span m='2549650'>a</span> <span m='2549760'>victory</span> <span m='2550270'>or
  a</span> <span m='2550480'>defeat.</span> <span m='2552310'>And</span> <span m='2553150'>that's</span>
  <span m='2553690'>kind</span> <span m='2553900'>of</span> <span m='2553960'>amazing</span>
  <span m='2554380'>because</span> <span m='2554900'>we</span> <span m='2555070'>had</span>
  <span m='2555220'>no</span> <span m='2555480'>external</span> <span m='2555850'>heuristic</span>
  <span m='2556220'>information</span> <span m='2556690'>about</span> <span m='2556800'>this
  game.</span> </p><p><span m='2557650'>Which</span> <span m='2557800'>means</span>
  <span m='2558130'>that</span> <span m='2558550'>if</span> <span m='2558700'>I</span>
  <span m='2559110'>took a</span> <span m='2559430'>completely</span> <span m='2559640'>new
  game</span> <span m='2559850'>that</span> <span m='2559980'>someone</span> <span
  m='2560210'>had</span> <span m='2560290'>just</span> <span m='2560470'>invented,</span>
  <span m='2561590'>and I plugged</span> <span m='2562080'>MCTS</span> <span m='2562350'>into</span>
  <span m='2562610'>it,</span> <span m='2562720'>MCTS</span> <span m='2563670'>would</span>
  <span m='2563890'>be</span> <span m='2564560'>a</span> <span m='2564760'>slightly</span>
  <span m='2565260'>or</span> <span m='2565500'>someone</span> <span m='2566090'>competitive</span>
  <span m='2567300'>player</span> <span m='2567720'>for</span> <span m='2567880'>this</span>
  <span m='2568060'>game,</span> <span m='2568880'>which</span> <span m='2568900'>is</span>
  <span m='2568990'>a</span> <span m='2569050'>powerful</span> <span m='2570190'>idea.</span>
  <span m='2570600'>It</span> <span m='2570650'>leads</span> <span m='2570900'>to
  our</span> <span m='2571050'>next</span> <span m='2571290'>two</span> <span m='2571450'>pros.</span>
  <span m='2572350'>The</span> <span m='2572890'>first of</span> <span m='2573260'>which</span>
  <span m='2573400'>is</span> <span m='2573520'>that</span> <span m='2573640'>it's</span>
  <span m='2573760'>very</span> <span m='2574120'>easy</span> <span m='2574390'>to</span>
  <span m='2574590'>adapt</span> <span m='2575200'>to</span> <span m='2575290'>new</span>
  <span m='2575470'>games</span> <span m='2576220'>that</span> <span m='2576570'>it</span>
  <span m='2577420'>hasn't</span> <span m='2577660'>seen</span> <span m='2577870'>before,</span>
  <span m='2578210'>or</span> <span m='2578290'>even</span> <span m='2578440'>that</span>
  <span m='2578560'>people</span> <span m='2578850'>haven't</span> <span m='2579150'>seen
  before.</span> <span m='2582160'>This</span> <span m='2582310'>is</span> <span m='2582400'>clearly</span>
  <span m='2582820'>valuable.</span> </p><p><span m='2583720'>But</span> <span m='2583900'>the</span>
  <span m='2584080'>other</span> <span m='2584320'>nice</span> <span m='2584560'>thing</span>
  <span m='2584740'>about it</span> <span m='2585100'>is</span> <span m='2585220'>that</span>
  <span m='2585460'>even</span> <span m='2585760'>though</span> <span m='2586030'>heuristics</span>
  <span m='2586720'>are</span> <span m='2586810'>not</span> <span m='2587020'>required</span>
  <span m='2588220'>to</span> <span m='2588760'>make</span> <span m='2590450'>MCTS</span>
  <span m='2590770'>work</span> <span m='2591116'>[INAUDIBLE],</span> <span m='2591810'>it</span>
  <span m='2592070'>can work</span> <span m='2592455'>[INAUDIBLE].</span> <span m='2592840'>There</span>
  <span m='2592990'>are</span> <span m='2593170'>a</span> <span m='2593230'>number</span>
  <span m='2593620'>of</span> <span m='2593970'>[? advanced ?]</span> <span m='2594040'>places</span>
  <span m='2594520'>in</span> <span m='2594640'>the</span> <span m='2594940'>algorithm</span>
  <span m='2595240'>that you can</span> <span m='2595740'>actually</span> <span m='2596340'>incorporate</span>
  <span m='2596690'>heuristics</span> <span m='2597160'>into.</span> <span m='2597630'>Nick</span>
  <span m='2597930'>is</span> <span m='2598120'>going</span> <span m='2598240'>to</span>
  <span m='2598300'>talk</span> <span m='2598540'>about</span> <span m='2598720'>how</span>
  <span m='2598840'>AlphaGo</span> <span m='2599860'>uses</span> <span m='2600120'>this</span>
  <span m='2600310'>very</span> <span m='2600550'>heavily.</span> <span m='2600880'>AlphaGo</span>
  <span m='2601210'>is</span> <span m='2601300'>not</span> <span m='2601610'>vanilla</span>
  <span m='2601730'>Go.</span> <span m='2602460'>It</span> <span m='2602560'>has</span>
  <span m='2602650'>a</span> <span m='2602710'>lot</span> <span m='2602950'>of</span>
  <span m='2603250'>external</span> <span m='2603910'>information</span> <span m='2604270'>that's</span>
  <span m='2604630'>built</span> <span m='2604900'>into</span> <span m='2605080'>the</span>
  <span m='2605170'>way</span> <span m='2605360'>that</span> <span m='2605470'>it</span>
  <span m='2605830'>works.</span> </p><p><span m='2606430'>But</span> <span m='2606650'>MCTS</span>
  <span m='2607090'>is</span> <span m='2607240'>a</span> <span m='2607720'>framework--</span>
  <span m='2608110'>you</span> <span m='2608190'>can</span> <span m='2608270'>imagine</span>
  <span m='2609100'>your</span> <span m='2609330'>heuristics</span> <span m='2609820'>you
  can</span> <span m='2610110'>apply</span> <span m='2610430'>in the</span> <span
  m='2610750'>simulation,</span> <span m='2611120'>there are</span> <span m='2611395'>heuristics</span>
  <span m='2611670'>you</span> <span m='2611770'>can</span> <span m='2611890'>apply</span>
  <span m='2612520'>in the</span> <span m='2612570'>UCB</span> <span m='2613200'>in</span>
  <span m='2613280'>the</span> <span m='2613330'>way</span> <span m='2613420'>that</span>
  <span m='2613640'>we</span> <span m='2613990'>choose</span> <span m='2614260'>the</span>
  <span m='2614350'>next</span> <span m='2614520'>node.</span> <span m='2615550'>There</span>
  <span m='2615640'>are</span> <span m='2615790'>places</span> <span m='2616000'>that</span>
  <span m='2616120'>it</span> <span m='2616390'>can</span> <span m='2616540'>fit</span>
  <span m='2616780'>in.</span> <span m='2617210'>And this</span> <span m='2617370'>services</span>
  <span m='2617830'>as a nice</span> <span m='2618080'>infrastructure</span> <span
  m='2618230'>to do so.</span> </p><p><span m='2621320'>The</span> <span m='2622100'>other</span>
  <span m='2622280'>benefit</span> <span m='2622670'>is</span> <span m='2622790'>that</span>
  <span m='2623120'>it's</span> <span m='2623555'>an</span> <span m='2623990'>on demand</span>
  <span m='2624180'>algorithm,</span> <span m='2624830'>which</span> <span m='2625150'>is</span>
  <span m='2625300'>particularly</span> <span m='2625820'>valuable</span> <span m='2626480'>when</span>
  <span m='2626660'>you're</span> <span m='2626900'>under</span> <span m='2627110'>some</span>
  <span m='2627230'>sort</span> <span m='2627380'>of</span> <span m='2627440'>time</span>
  <span m='2627660'>pressure,</span> <span m='2628010'>when</span> <span m='2628140'>you're</span>
  <span m='2628310'>competing</span> <span m='2628820'>against</span> <span m='2629450'>someone</span>
  <span m='2629760'>that's</span> <span m='2629900'>a</span> <span m='2630110'>mathematician,</span>
  <span m='2630830'>or</span> <span m='2631400'>when</span> <span m='2632080'>something</span>
  <span m='2632500'>is</span> <span m='2632590'>about to</span> <span m='2632810'>explode</span>
  <span m='2633100'>and</span> <span m='2633390'>you have to</span> <span m='2633590'>make</span>
  <span m='2633740'>a</span> <span m='2633770'>decision</span> <span m='2634100'>on</span>
  <span m='2634220'>which</span> <span m='2634430'>reactor</span> <span m='2634650'>to
  shut</span> <span m='2634880'>down.</span> </p><p><span m='2637240'>And</span> <span
  m='2637610'>lastly--</span> <span m='2638580'>or not</span> <span m='2639040'>lastly,</span>
  <span m='2639120'>actually,</span> <span m='2639880'>it's</span> <span m='2640180'>complete,</span>
  <span m='2640890'>which</span> <span m='2641230'>is</span> <span m='2641770'>really</span>
  <span m='2642040'>nice</span> <span m='2642310'>because</span> <span m='2642520'>you</span>
  <span m='2642590'>know</span> <span m='2642700'>that</span> <span m='2643150'>if</span>
  <span m='2643270'>you</span> <span m='2643400'>run</span> <span m='2643680'>this</span>
  <span m='2643850'>game</span> <span m='2644150'>for long</span> <span m='2644340'>enough</span>
  <span m='2644740'>it's going to</span> <span m='2644940'>start</span> <span m='2645250'>looking</span>
  <span m='2645520'>at</span> <span m='2645580'>a lot</span> <span m='2645900'>like</span>
  <span m='2647070'>a</span> <span m='2647180'>BFS</span> <span m='2648040'>tree.</span>
  <span m='2649330'>No,</span> <span m='2649540'>it's actually</span> <span m='2649640'>going
  to start</span> <span m='2649790'>looking like an</span> <span m='2650230'>alpha-beta</span>
  <span m='2651110'>tree,</span> <span m='2651550'>if it</span> <span m='2651620'>is
  what it is</span> <span m='2652060'>converted to.</span> <span m='2654820'>It's</span>
  <span m='2654990'>a</span> <span m='2655250'>nice</span> <span m='2655510'>property</span>
  <span m='2655860'>to</span> <span m='2656000'>have.</span> <span m='2656650'>Although,</span>
  <span m='2656910'>this</span> <span m='2657010'>property</span> <span m='2658000'>does</span>
  <span m='2658260'>slightly</span> <span m='2658470'>get</span> <span m='2658620'>compromised</span>
  <span m='2659080'>if you</span> <span m='2659455'>remove the</span> <span m='2659830'>red</span>
  <span m='2660010'>in this idea,</span> <span m='2660160'>and</span> <span m='2660520'>if</span>
  <span m='2660970'>only</span> <span m='2661255'>simulate</span> <span m='2661830'>these</span>
  <span m='2662120'>[INAUDIBLE].</span> <span m='2664690'>Yeah.</span> </p><p><span
  m='2665594'>PROFESSOR:</span> <span m='2666050'>You</span> <span m='2666340'>made</span>
  <span m='2666550'>an</span> <span m='2666940'>interesting</span> <span m='2667170'>comment</span>
  <span m='2667370'>when you said,</span> <span m='2667700'>oh, it</span> <span m='2667980'>looks</span>
  <span m='2668140'>like</span> <span m='2668330'>-beta</span> <span m='2668750'>tree.</span>
  <span m='2669410'>So</span> <span m='2669550'>it</span> <span m='2669610'>looked</span>
  <span m='2669820'>like</span> <span m='2669940'>a</span> <span m='2670000'>mini-max</span>
  <span m='2670270'>tree.</span> <span m='2672290'>But</span> <span m='2672850'>have</span>
  <span m='2673180'>they</span> <span m='2673330'>also</span> <span m='2674230'>incorporated</span>
  <span m='2674710'>notions</span> <span m='2675190'>of</span> <span m='2675850'>pruning</span>
  <span m='2676180'>in</span> <span m='2676270'>the</span> <span m='2676350'>MCTS,</span>
  <span m='2677050'>which</span> <span m='2677200'>would</span> <span m='2677320'>make</span>
  <span m='2677530'>it</span> <span m='2677620'>look</span> <span m='2677800'>like</span>
  <span m='2677950'>an</span> <span m='2678070'>-beta</span> <span m='2678420'>tree?</span>
  </p><p><span m='2679790'>PROFESSOR 3:</span> <span m='2679920'>Sorry,</span> <span
  m='2680050'>you're</span> <span m='2680230'>completely</span> <span m='2680580'>right.</span>
  <span m='2680780'>It</span> <span m='2681222'>does look like a</span> <span m='2681664'>mini-max</span>
  <span m='2682106'>tree.</span> <span m='2682990'>I</span> <span m='2683110'>think</span>
  <span m='2683360'>I've seen</span> <span m='2683590'>variants</span> <span m='2684080'>where
  they</span> <span m='2684520'>do</span> <span m='2685000'>pruning,</span> <span
  m='2685380'>but I haven't</span> <span m='2685670'>looked into it</span> <span m='2686101'>as</span>
  <span m='2686532'>much.</span> <span m='2686963'>But</span> <span m='2687394'>I
  would</span> <span m='2687825'>imagine</span> <span m='2688256'>that they would</span>
  <span m='2688690'>converge</span> <span m='2688990'>to</span> <span m='2689060'>whatever</span>
  <span m='2689540'>you know</span> <span m='2690020'>pruning</span> <span m='2690500'>a
  certain</span> <span m='2690940'>tree</span> <span m='2691300'>[INAUDIBLE].</span>
  </p><p><span m='2692020'>AUDIENCE:</span> <span m='2692095'>But</span> <span m='2692170'>people</span>
  <span m='2692440'>have</span> <span m='2692590'>explored</span> <span m='2693490'>incorporating</span>
  <span m='2694450'>pruning</span> <span m='2694780'>into</span> <span m='2695140'>MCTS?</span>
  </p><p><span m='2695380'>PROFESSOR 3:</span> <span m='2695545'>I</span> <span m='2695710'>think</span>
  <span m='2696160'>so.</span> <span m='2697170'>I</span> <span m='2697260'>can't</span>
  <span m='2697470'>say</span> <span m='2697650'>[INAUDIBLE]</span> <span m='2700100'>And</span>
  <span m='2700200'>then</span> <span m='2700390'>lastly,</span> <span m='2701270'>it's</span>
  <span m='2701350'>really</span> <span m='2701680'>parallelizable.</span> <span m='2702680'>You'll</span>
  <span m='2702840'>notice,</span> <span m='2703320'>none</span> <span m='2703520'>of</span>
  <span m='2703630'>the</span> <span m='2704680'>regions</span> <span m='2705040'>of</span>
  <span m='2705110'>this</span> <span m='2705220'>tree,</span> <span m='2705610'>other</span>
  <span m='2705850'>than</span> <span m='2706000'>the</span> <span m='2706990'>original</span>
  <span m='2707380'>choice,</span> <span m='2708050'>ever</span> <span m='2708250'>have</span>
  <span m='2708410'>to</span> <span m='2708530'>interact</span> <span m='2708890'>with
  each other.</span> </p><p><span m='2709380'>So</span> <span m='2709480'>if</span>
  <span m='2709560'>you</span> <span m='2709690'>have</span> <span m='2710210'>200</span>
  <span m='2710710'>processors</span> <span m='2711550'>and</span> <span m='2711640'>you</span>
  <span m='2711700'>decide,</span> <span m='2712030'>OK,</span> <span m='2712420'>I'm
  going to</span> <span m='2712510'>break</span> <span m='2712780'>up</span> <span
  m='2712900'>this</span> <span m='2713080'>tree</span> <span m='2713460'>in</span>
  <span m='2713770'>the</span> <span m='2713860'>first</span> <span m='2714635'>200</span>
  <span m='2714970'>decisions</span> <span m='2715380'>and then have</span> <span
  m='2715745'>each</span> <span m='2716110'>one</span> <span m='2716230'>of</span>
  <span m='2716290'>those</span> <span m='2716470'>flesh</span> <span m='2716710'>out
  one of</span> <span m='2716890'>those</span> <span m='2717050'>decisions,</span>
  <span m='2718090'>that</span> <span m='2718470'>actually</span> <span m='2718720'>means</span>
  <span m='2719050'>that</span> <span m='2719952'>they</span> <span m='2720330'>can</span>
  <span m='2720600'>all</span> <span m='2720870'>combine</span> <span m='2721330'>information</span>
  <span m='2721720'>right at</span> <span m='2722060'>the end</span> <span m='2722400'>and</span>
  <span m='2722620'>make</span> <span m='2722760'>a</span> <span m='2722820'>decision</span>
  <span m='2723180'>[INAUDIBLE],</span> <span m='2723670'>which</span> <span m='2723820'>is</span>
  <span m='2723910'>a</span> <span m='2723980'>really</span> <span m='2724490'>nice,</span>
  <span m='2725290'>powerful</span> <span m='2725750'>principle</span> <span m='2726220'>as</span>
  <span m='2726657'>you</span> <span m='2727094'>[INAUDIBLE].</span> </p><p><span
  m='2729280'>It</span> <span m='2729370'>does</span> <span m='2729640'>have</span>
  <span m='2729850'>its</span> <span m='2730010'>fair</span> <span m='2730220'>share</span>
  <span m='2730430'>of</span> <span m='2730860'>problems.</span> <span m='2731290'>The</span>
  <span m='2731380'>first</span> <span m='2731590'>problem</span> <span m='2731920'>being</span>
  <span m='2732490'>that</span> <span m='2732790'>it</span> <span m='2732940'>does</span>
  <span m='2733780'>breakdown</span> <span m='2734950'>under</span> <span m='2735160'>extreme</span>
  <span m='2735640'>tree</span> <span m='2735890'>depth.</span> <span m='2738290'>The</span>
  <span m='2738390'>main</span> <span m='2738580'>reason</span> <span m='2738960'>for
  this</span> <span m='2739090'>being</span> <span m='2739600'>that</span> <span m='2740560'>as</span>
  <span m='2740770'>you</span> <span m='2740890'>increase</span> <span m='2741340'>more</span>
  <span m='2741640'>moves</span> <span m='2741940'>between</span> <span m='2742300'>you</span>
  <span m='2743070'>and</span> <span m='2744120'>the</span> <span m='2744250'>end</span>
  <span m='2744370'>of</span> <span m='2744430'>the</span> <span m='2744520'>game,</span>
  <span m='2745150'>you're</span> <span m='2745360'>increasing</span> <span m='2746050'>the</span>
  <span m='2746170'>probability--</span> <span m='2747250'>you</span> <span m='2747520'>are</span>
  <span m='2747580'>decreasing</span> <span m='2748030'>the</span> <span m='2748120'>correlation</span>
  <span m='2748630'>between</span> <span m='2748960'>your</span> <span m='2749350'>game</span>
  <span m='2749630'>state</span> <span m='2749950'>and</span> <span m='2750070'>whether</span>
  <span m='2750490'>a</span> <span m='2750590'>random</span> <span m='2750730'>playoff</span>
  <span m='2751120'>would</span> <span m='2751270'>suggest</span> <span m='2752050'>that</span>
  <span m='2752230'>you're</span> <span m='2752330'>in a</span> <span m='2752650'>good</span>
  <span m='2752800'>position</span> <span m='2753060'>or</span> <span m='2753320'>a</span>
  <span m='2753530'>bad</span> <span m='2754020'>position.</span> </p><p><span m='2754750'>The</span>
  <span m='2754990'>same</span> <span m='2755080'>goes</span> <span m='2755440'>for</span>
  <span m='2755800'>branching</span> <span m='2756010'>factors.</span> <span m='2756790'>One</span>
  <span m='2756880'>of</span> <span m='2756940'>the</span> <span m='2757000'>things</span>
  <span m='2757270'>that</span> <span m='2757360'>people</span> <span m='2757630'>sometimes</span>
  <span m='2758090'>talk</span> <span m='2758250'>about</span> <span m='2758520'>it
  as</span> <span m='2758690'>if</span> <span m='2759410'>MCTS</span> <span m='2761470'>AI's</span>
  <span m='2761950'>cannot</span> <span m='2762520'>play</span> <span m='2762790'>first-person</span>
  <span m='2763050'>shooters</span> <span m='2763930'>because</span> <span m='2764450'>the</span>
  <span m='2764770'>distance</span> <span m='2765220'>between</span> <span m='2766150'>the</span>
  <span m='2766690'>number</span> <span m='2766990'>of</span> <span m='2767080'>things</span>
  <span m='2767290'>that</span> <span m='2767380'>you</span> <span m='2767500'>can</span>
  <span m='2767590'>do</span> <span m='2767770'>at</span> <span m='2767920'>every</span>
  <span m='2768190'>given</span> <span m='2768490'>moment,</span> <span m='2769280'>and</span>
  <span m='2770350'>what</span> <span m='2770560'>would</span> <span m='2770680'>be</span>
  <span m='2770800'>a</span> <span m='2770830'>successful</span> <span m='2771460'>approach</span>
  <span m='2772210'>in</span> <span m='2772420'>the</span> <span m='2772510'>long</span>
  <span m='2772750'>term</span> <span m='2773110'>after</span> <span m='2773350'>meeting</span>
  <span m='2773580'>many,</span> <span m='2773970'>many,</span> <span m='2774200'>many</span>
  <span m='2774460'>moves that</span> <span m='2774830'>each</span> <span m='2775030'>have</span>
  <span m='2775180'>many</span> <span m='2775420'>branching</span> <span m='2775710'>factors,</span>
  <span m='2776360'>is</span> <span m='2776560'>that</span> <span m='2776770'>never</span>
  <span m='2777190'>begins</span> <span m='2777540'>to</span> <span m='2777880'>explore</span>
  <span m='2779670'>the</span> <span m='2779770'>size of the</span> <span m='2780060'>search
  tree.</span> <span m='2781330'>For</span> <span m='2781510'>the</span> <span m='2781570'>most</span>
  <span m='2781780'>part,</span> <span m='2782060'>it's</span> <span m='2782080'>not</span>
  <span m='2782230'>really</span> <span m='2782440'>coming</span> <span m='2782680'>up</span>
  <span m='2782770'>with</span> <span m='2782920'>a</span> <span m='2782980'>long</span>
  <span m='2783250'>term</span> <span m='2783460'>policy.</span> <span m='2784460'>It's</span>
  <span m='2784510'>really</span> <span m='2784780'>thinking</span> <span m='2785080'>about</span>
  <span m='2785410'>what</span> <span m='2785590'>are</span> <span m='2786010'>the</span>
  <span m='2786430'>next</span> <span m='2786680'>sequence</span> <span m='2787180'>of</span>
  <span m='2787625'>moves that I should</span> <span m='2788070'>[INAUDIBLE].</span>
  </p><p><span m='2791190'>Another</span> <span m='2792110'>problem</span> <span m='2792770'>is</span>
  <span m='2792910'>that it</span> <span m='2793000'>requires</span> <span m='2794000'>simulation</span>
  <span m='2794750'>to</span> <span m='2794900'>be</span> <span m='2795500'>very</span>
  <span m='2795950'>easy</span> <span m='2796790'>and</span> <span m='2797360'>very</span>
  <span m='2797620'>repeatable.</span> <span m='2798530'>So</span> <span m='2798560'>for</span>
  <span m='2798680'>example,</span> <span m='2800360'>if</span> <span m='2800540'>we</span>
  <span m='2800690'>wanted</span> <span m='2800930'>to</span> <span m='2801020'>tell
  our</span> <span m='2801395'>AI,</span> <span m='2802820'>how</span> <span m='2802990'>do</span>
  <span m='2803170'>I</span> <span m='2803420'>take</span> <span m='2803510'>over</span>
  <span m='2803780'>Ontario?</span> <span m='2804920'>There's</span> <span m='2805100'>not</span>
  <span m='2805490'>a</span> <span m='2805550'>particularly</span> <span m='2806060'>good</span>
  <span m='2806360'>way</span> <span m='2806630'>that</span> <span m='2806780'>you</span>
  <span m='2806870'>can</span> <span m='2806990'>simulate</span> <span m='2807620'>taking</span>
  <span m='2808010'>over</span> <span m='2808220'>Ontario?</span> <span m='2809480'>If</span>
  <span m='2809850'>you</span> <span m='2809930'>try it</span> <span m='2810230'>once,</span>
  <span m='2810520'>you're</span> <span m='2810740'>not</span> <span m='2810920'>going
  to</span> <span m='2811070'>have</span> <span m='2811310'>an</span> <span m='2811620'>opportunity</span>
  <span m='2811890'>to try it</span> <span m='2812120'>again,</span> <span m='2812810'>at</span>
  <span m='2812910'>least</span> <span m='2813100'>with</span> <span m='2813210'>the</span>
  <span m='2813290'>same</span> <span m='2813860'>set</span> <span m='2814130'>of</span>
  <span m='2814630'>configurations.</span> </p><p><span m='2816470'>And</span> <span
  m='2817320'>actually,</span> <span m='2817860'>one</span> <span m='2818020'>of the</span>
  <span m='2818230'>things that</span> <span m='2818410'>we really</span> <span m='2818720'>took
  advantage</span> <span m='2819030'>of, if</span> <span m='2819210'>that</span> <span
  m='2819310'>random</span> <span m='2819590'>simulation</span> <span m='2820080'>happens</span>
  <span m='2820280'>really</span> <span m='2820550'>quickly,</span> <span m='2820750'>on
  the</span> <span m='2820960'>order of</span> <span m='2821340'>microseconds.</span>
  <span m='2822865'>On</span> <span m='2823220'>other</span> <span m='2823740'>hand,</span>
  <span m='2825770'>the</span> <span m='2826240'>bigger</span> <span m='2826670'>your</span>
  <span m='2826850'>computational</span> <span m='2827630'>resources</span> <span
  m='2828170'>that</span> <span m='2828240'>you</span> <span m='2828320'>have</span>
  <span m='2828470'>access</span> <span m='2828810'>to,</span> <span m='2828910'>the</span>
  <span m='2829140'>better</span> <span m='2829210'>the</span> <span m='2829690'>algorithm</span>
  <span m='2830000'>works.</span> <span m='2830300'>That means</span> <span m='2830780'>that
  I</span> <span m='2831260'>can't run</span> <span m='2831410'>it off</span> <span
  m='2831530'>my</span> <span m='2831650'>Mac</span> <span m='2831920'>particularly</span>
  <span m='2832310'>well.</span> <span m='2832665'>It would be like</span> <span m='2833020'>large
  games.</span> </p><p><span m='2835670'>It</span> <span m='2835760'>relies</span>
  <span m='2836090'>on</span> <span m='2836180'>this</span> <span m='2836390'>tenuous</span>
  <span m='2836940'>assumption</span> <span m='2837410'>of</span> <span m='2837675'>random</span>
  <span m='2837940'>play</span> <span m='2838195'>be</span> <span m='2838450'>weakly</span>
  <span m='2839030'>correlated</span> <span m='2839870'>with</span> <span m='2840410'>the</span>
  <span m='2840500'>quality</span> <span m='2840950'>of</span> <span m='2841030'>our</span>
  <span m='2841100'>game</span> <span m='2841330'>state.</span> <span m='2841595'>And</span>
  <span m='2841860'>this is</span> <span m='2842110'>one</span> <span m='2842240'>of</span>
  <span m='2842290'>the</span> <span m='2842350'>first</span> <span m='2842670'>assumptions</span>
  <span m='2843090'>that is going to be</span> <span m='2843300'>thrown</span> <span
  m='2843530'>out</span> <span m='2843660'>the</span> <span m='2843720'>window</span>
  <span m='2844000'>for</span> <span m='2844180'>a</span> <span m='2844230'>lot</span>
  <span m='2844390'>of</span> <span m='2844460'>the</span> <span m='2844550'>more</span>
  <span m='2844730'>advanced</span> <span m='2845060'>MCTS</span> <span m='2845950'>approaches,</span>
  <span m='2846680'>which</span> <span m='2846810'>are</span> <span m='2846890'>going</span>
  <span m='2847130'>to</span> <span m='2847250'>have</span> <span m='2847880'>more</span>
  <span m='2848870'>intelligent</span> <span m='2849205'>play outs.</span> <span m='2850310'>But</span>
  <span m='2850550'>those</span> <span m='2850790'>are</span> <span m='2850830'>going
  to lose</span> <span m='2851140'>some of the</span> <span m='2851440'>generality</span>
  <span m='2851940'>that we</span> <span m='2852378'>had before.</span> </p><p><span
  m='2855380'>Something</span> <span m='2855530'>that</span> <span m='2855640'>goes</span>
  <span m='2855830'>off</span> <span m='2856030'>of</span> <span m='2856100'>that</span>
  <span m='2856520'>is</span> <span m='2856650'>that</span> <span m='2857060'>MCTS</span>
  <span m='2857650'>is</span> <span m='2857840'>a</span> <span m='2857930'>framework.</span>
  <span m='2858760'>But</span> <span m='2858980'>in order</span> <span m='2859060'>to</span>
  <span m='2859220'>actually</span> <span m='2859630'>make</span> <span m='2859750'>it</span>
  <span m='2859800'>effective</span> <span m='2860180'>for</span> <span m='2860330'>a</span>
  <span m='2860360'>lot</span> <span m='2860510'>of</span> <span m='2860570'>games</span>
  <span m='2861260'>it</span> <span m='2861350'>does</span> <span m='2861500'>require</span>
  <span m='2862190'>a</span> <span m='2862280'>lot</span> <span m='2862490'>of</span>
  <span m='2863230'>tuning,</span> <span m='2863850'>in</span> <span m='2863930'>the</span>
  <span m='2863990'>sense</span> <span m='2864250'>that</span> <span m='2864300'>there</span>
  <span m='2864470'>are a whole bunch</span> <span m='2864770'>of</span> <span m='2864860'>variants.</span>
  <span m='2865500'>And that</span> <span m='2865590'>you</span> <span m='2865830'>need</span>
  <span m='2866030'>to</span> <span m='2866090'>be</span> <span m='2866210'>able</span>
  <span m='2866330'>to</span> <span m='2866490'>implement</span> <span m='2866840'>whatever</span>
  <span m='2867140'>flavor</span> <span m='2867700'>is</span> <span m='2867820'>best</span>
  <span m='2868250'>suited</span> <span m='2868410'>for you.</span> <span m='2868745'>Which</span>
  <span m='2869080'>means that it's</span> <span m='2869360'>not</span> <span m='2869570'>quite</span>
  <span m='2869870'>as</span> <span m='2869980'>nice</span> <span m='2870190'>and</span>
  <span m='2870470'>black</span> <span m='2870690'>boxy</span> <span m='2871290'>as</span>
  <span m='2871440'>we</span> <span m='2871590'>would</span> <span m='2872210'>want
  it</span> <span m='2872450'>to</span> <span m='2872570'>be</span> <span m='2873640'>as</span>
  <span m='2873740'>far</span> <span m='2873920'>as</span> <span m='2874250'>give</span>
  <span m='2874360'>it</span> <span m='2874490'>the</span> <span m='2874580'>rules</span>
  <span m='2874890'>and</span> <span m='2875050'>have</span> <span m='2875230'>it</span>
  <span m='2875495'>magically</span> <span m='2875760'>come up</span> <span m='2876080'>with
  a</span> <span m='2876310'>strategy</span> <span m='2876800'>[INAUDIBLE].</span>
  </p><p><span m='2878270'>And</span> <span m='2878360'>then</span> <span m='2878630'>lastly,</span>
  <span m='2879360'>as</span> <span m='2879410'>you</span> <span m='2879500'>mentioned,</span>
  <span m='2880160'>there</span> <span m='2880270'>is</span> <span m='2880460'>not</span>
  <span m='2880730'>a</span> <span m='2880820'>great</span> <span m='2881300'>amount</span>
  <span m='2881540'>of</span> <span m='2881630'>literature</span> <span m='2881900'>right</span>
  <span m='2882170'>now</span> <span m='2883280'>about</span> <span m='2883910'>the</span>
  <span m='2884040'>properties</span> <span m='2884620'>of</span> <span m='2884720'>MCTS</span>
  <span m='2885150'>and its</span> <span m='2885420'>convergence,</span> <span m='2886080'>and</span>
  <span m='2886820'>what</span> <span m='2887030'>the</span> <span m='2887180'>actual</span>
  <span m='2887570'>proportion</span> <span m='2888140'>of</span> <span m='2888230'>time</span>
  <span m='2889040'>to</span> <span m='2889610'>quality</span> <span m='2889790'>of</span>
  <span m='2889930'>your</span> <span m='2890100'>solution</span> <span m='2890540'>is.</span>
  <span m='2891950'>This</span> <span m='2892130'>is</span> <span m='2892400'>true</span>
  <span m='2892700'>of</span> <span m='2892820'>all</span> <span m='2893480'>modern</span>
  <span m='2894290'>machine</span> <span m='2894740'>learning</span> <span m='2895220'>things,</span>
  <span m='2895610'>is</span> <span m='2895880'>that there is</span> <span m='2896660'>certainly</span>
  <span m='2896960'>a</span> <span m='2897100'>lot more</span> <span m='2897310'>work</span>
  <span m='2897500'>that could</span> <span m='2897640'>be</span> <span m='2897740'>done.</span>
  <span m='2898410'>But</span> <span m='2898440'>right</span> <span m='2898580'>now,</span>
  <span m='2898790'>that's</span> <span m='2899120'>a</span> <span m='2899210'>gap</span>
  <span m='2899450'>in terms</span> <span m='2899760'>of</span> <span m='2900090'>using</span>
  <span m='2900340'>this</span> <span m='2900510'>for a</span> <span m='2900860'>simulation</span>
  <span m='2901130'>that's supposed</span> <span m='2901290'>to be reliable.</span>
  <span m='2903577'>Anyone have</span> <span m='2904074'>any questions</span> <span
  m='2904571'>on the</span> <span m='2905068'>Pros and Cons?</span> </p><p><span m='2907630'>Before</span>
  <span m='2907990'>we</span> <span m='2908140'>jump</span> <span m='2908440'>dive</span>
  <span m='2908830'>into</span> <span m='2909010'>applications,</span> <span m='2909940'>let's</span>
  <span m='2910180'>talk</span> <span m='2910680'>through</span> <span m='2910970'>a
  few</span> <span m='2911380'>examples</span> <span m='2912320'>of</span> <span m='2912740'>what</span>
  <span m='2913220'>games</span> <span m='2913620'>could</span> <span m='2913840'>be</span>
  <span m='2913960'>solved</span> <span m='2914320'>and</span> <span m='2914540'>could
  not</span> <span m='2914770'>be</span> <span m='2914890'>solved</span> <span m='2915480'>by</span>
  <span m='2915720'>MCTS.</span> <span m='2916750'>Do</span> <span m='2917200'>you</span>
  <span m='2917290'>guys</span> <span m='2917660'>think that</span> <span m='2917840'>checkers</span>
  <span m='2918200'>is a game</span> <span m='2918682'>that could be</span> <span
  m='2919164'>solved</span> <span m='2919646'>by</span> <span m='2920128'>MCTS?</span>
  </p><p><span m='2920610'>AUDIENCE:</span> <span m='2920851'>Yes.</span> </p><p><span
  m='2922190'>PROFESSOR 3:</span> <span m='2922280'>It's</span> <span m='2922370'>completely</span>
  <span m='2922765'>deterministic.</span> <span m='2923160'>It's</span> <span m='2923470'>two-player.</span>
  <span m='2923810'>It</span> <span m='2924260'>satisfies</span> <span m='2924710'>all</span>
  <span m='2924940'>of</span> <span m='2925000'>the</span> <span m='2925060'>criteria</span>
  <span m='2925240'>that</span> <span m='2925675'>we've laid out</span> <span m='2926110'>before.</span>
  <span m='2926770'>Checkers</span> <span m='2927220'>is</span> <span m='2927430'>definitely</span>
  <span m='2927640'>a</span> <span m='2927770'>game</span> <span m='2928100'>that</span>
  <span m='2928240'>can</span> <span m='2928640'>and</span> <span m='2928790'>has</span>
  <span m='2929060'>been</span> <span m='2929270'>solved</span> <span m='2929760'>by</span>
  <span m='2930060'>MCTS,</span> <span m='2930625'>although</span> <span m='2930930'>not</span>
  <span m='2931180'>solved</span> <span m='2931240'>to the</span> <span m='2931430'>extent</span>
  <span m='2931990'>that</span> <span m='2932110'>you</span> <span m='2932450'>can</span>
  <span m='2932790'>defeat</span> <span m='2933110'>the thing that</span> <span m='2933420'>actually</span>
  <span m='2933760'>has</span> <span m='2933940'>the solution</span> <span m='2934377'>[INAUDIBLE].</span>
  </p><p><span m='2937270'>How</span> <span m='2937460'>about</span> <span m='2937770'>"Settlers</span>
  <span m='2937980'>of</span> <span m='2938420'>Catan?"</span> <span m='2938860'>This
  one's a</span> <span m='2938890'>little</span> <span m='2939070'>bit</span> <span
  m='2939160'>trickier.</span> <span m='2939790'>Do</span> <span m='2939850'>you</span>
  <span m='2939940'>guys</span> <span m='2940210'>think</span> <span m='2940460'>that</span>
  <span m='2940870'>MCTS</span> <span m='2941280'>is</span> <span m='2941500'>likely</span>
  <span m='2941750'>to be</span> <span m='2941870'>able</span> <span m='2942260'>to</span>
  <span m='2942570'>play</span> <span m='2942680'>"Settlers</span> <span m='2943172'>of</span>
  <span m='2943664'>Catan?"</span> <span m='2944650'>If</span> <span m='2945150'>not,</span>
  <span m='2945500'>let's</span> <span m='2945740'>throw</span> <span m='2945890'>out</span>
  <span m='2945980'>reason</span> <span m='2946290'>why</span> <span m='2946520'>or</span>
  <span m='2946610'>why</span> <span m='2946770'>not</span> <span m='2946980'>it would</span>
  <span m='2947412'>be</span> <span m='2947844'>[INAUDIBLE].</span> <span m='2949140'>Yeah.</span>
  </p><p><span m='2949580'>AUDIENCE:</span> <span m='2949735'>No</span> <span m='2949890'>because</span>
  <span m='2950332'>there's</span> <span m='2950774'>randomness.</span> </p><p><span
  m='2952100'>PROFESSOR 3:</span> <span m='2952305'>So</span> <span m='2952510'>yes,</span>
  <span m='2952810'>that</span> <span m='2952960'>is</span> <span m='2953150'>absolutely</span>
  <span m='2953570'>the</span> <span m='2953860'>criticism.</span> <span m='2954050'>And
  that's</span> <span m='2954230'>why</span> <span m='2954420'>we</span> <span m='2954480'>can't</span>
  <span m='2954740'>apply</span> <span m='2955030'>it</span> <span m='2955130'>vanilla.</span>
  <span m='2956640'>I</span> <span m='2957080'>put</span> <span m='2957280'>this</span>
  <span m='2957400'>on</span> <span m='2957730'>here</span> <span m='2958060'>as</span>
  <span m='2958220'>a</span> <span m='2958280'>trick</span> <span m='2958460'>question,</span>
  <span m='2958820'>though,</span> <span m='2959070'>because</span> <span m='2959300'>it</span>
  <span m='2959360'>turns</span> <span m='2959600'>out</span> <span m='2959770'>that</span>
  <span m='2959990'>MCTS</span> <span m='2960500'>is</span> <span m='2960680'>robust</span>
  <span m='2960995'>to</span> <span m='2961310'>randomness.</span> <span m='2962460'>That</span>
  <span m='2962670'>you</span> <span m='2962780'>can</span> <span m='2962900'>actually</span>
  <span m='2963470'>play--</span> <span m='2963990'>and</span> <span m='2964160'>I
  realize</span> <span m='2964330'>that's just</span> <span m='2964758'>me</span>
  <span m='2965186'>and we do.</span> </p><p><span m='2965614'>[LAUGHTER]</span> </p><p><span
  m='2966470'>You</span> <span m='2966820'>can</span> <span m='2967070'>actually</span>
  <span m='2967590'>play</span> <span m='2967960'>through</span> <span m='2969390'>games.</span>
  <span m='2969720'>If</span> <span m='2970100'>you think</span> <span m='2970280'>about
  the</span> <span m='2970400'>simulation,</span> <span m='2970765'>the</span> <span
  m='2971130'>simulation</span> <span m='2971540'>is</span> <span m='2971660'>actually</span>
  <span m='2971960'>applicable</span> <span m='2972680'>even</span> <span m='2974660'>if</span>
  <span m='2974990'>the</span> <span m='2975080'>game</span> <span m='2975260'>is</span>
  <span m='2975350'>not</span> <span m='2975530'>deterministic</span> <span m='2976040'>because</span>
  <span m='2976220'>it</span> <span m='2976310'>does</span> <span m='2976520'>give</span>
  <span m='2976700'>you</span> <span m='2976850'>a</span> <span m='2976880'>sense</span>
  <span m='2977180'>of the</span> <span m='2977310'>quality</span> <span m='2977650'>of
  your</span> <span m='2978056'>position.</span> <span m='2978870'>And</span> <span
  m='2979480'>the</span> <span m='2980156'>MCTS-based</span> <span m='2980850'>AI</span>
  <span m='2981590'>to</span> <span m='2981740'>play</span> <span m='2982100'>"Settlers"</span>
  <span m='2982830'>is,</span> <span m='2983100'>I think,</span> <span m='2983545'>at
  least</span> <span m='2983990'>49%</span> <span m='2984500'>competitive</span> <span
  m='2985680'>with</span> <span m='2986150'>the</span> <span m='2986710'>best</span>
  <span m='2986980'>AI</span> <span m='2987946'>to</span> <span m='2988430'>play,</span>
  <span m='2988870'>at least in</span> <span m='2989320'>the</span> <span m='2989470'>autonomous</span>
  <span m='2989933'>non-scale</span> <span m='2990396'>space.</span> <span m='2990860'>So</span>
  <span m='2991170'>it</span> <span m='2991400'>does</span> <span m='2991660'>work.</span>
  </p><p><span m='2993780'>Let's</span> <span m='2993890'>talk</span> <span m='2994120'>about</span>
  <span m='2995660'>the</span> <span m='2996370'>war</span> <span m='2996720'>operations</span>
  <span m='2997060'>plan</span> <span m='2997380'>response.</span> <span m='2997710'>Who
  here</span> <span m='2998100'>has seen</span> <span m='2998360'>the movie</span>
  <span m='2998660'>"War</span> <span m='2998960'>Games?"</span> <span m='3000990'>OK.</span>
  <span m='3001330'>Well,</span> <span m='3001470'>it</span> <span m='3001540'>should</span>
  <span m='3001720'>be</span> <span m='3001870'>more</span> <span m='3002140'>of you.</span>
  </p><p><span m='3004030'>The</span> <span m='3004660'>idea</span> <span m='3005020'>of</span>
  <span m='3005305'>"War Games"</span> <span m='3005590'>is</span> <span m='3005800'>that</span>
  <span m='3006420'>one</span> <span m='3006730'>of</span> <span m='3006870'>the</span>
  <span m='3006970'>core</span> <span m='3007270'>characters</span> <span m='3008660'>in</span>
  <span m='3008770'>this</span> <span m='3008950'>world</span> <span m='3009640'>is</span>
  <span m='3010060'>this</span> <span m='3010240'>computer</span> <span m='3010750'>that</span>
  <span m='3010900'>has</span> <span m='3011030'>been</span> <span m='3011200'>put</span>
  <span m='3011380'>in</span> <span m='3011500'>charge</span> <span m='3012220'>of</span>
  <span m='3012850'>the</span> <span m='3013620'>national</span> <span m='3013990'>defense</span>
  <span m='3014230'>strategy</span> <span m='3014520'>with</span> <span m='3014810'>respect</span>
  <span m='3015130'>to</span> <span m='3015250'>Russia.</span> <span m='3016700'>And</span>
  <span m='3017030'>that</span> <span m='3017340'>it</span> <span m='3017650'>needs
  to</span> <span m='3017990'>think</span> <span m='3018420'>through</span> <span
  m='3018710'>the</span> <span m='3018760'>possible</span> <span m='3019180'>future</span>
  <span m='3019480'>scenarios</span> <span m='3019960'>and</span> <span m='3020050'>decide</span>
  <span m='3020500'>whether</span> <span m='3020730'>it's</span> <span m='3020830'>going</span>
  <span m='3020980'>to</span> <span m='3021040'>launch</span> <span m='3021310'>the</span>
  <span m='3021400'>nukes</span> <span m='3021550'>or</span> <span m='3021760'>not.</span>
  <span m='3023170'>Do</span> <span m='3023230'>you</span> <span m='3023410'>think</span>
  <span m='3023680'>that</span> <span m='3025190'>WOPR</span> <span m='3025900'>can</span>
  <span m='3026560'>be</span> <span m='3026890'>MCTS-based?</span> </p><p><span m='3027810'>AUDIENCE:</span>
  <span m='3028010'>No.</span> </p><p><span m='3029010'>PROFESSOR 3:</span> <span
  m='3029080'>No.</span> </p><p><span m='3029900'>AUDIENCE:</span> <span m='3029950'>It</span>
  <span m='3030000'>could,</span> <span m='3030300'>it just</span> <span m='3030630'>wouldn't</span>
  <span m='3030840'>be very</span> <span m='3031232'>good.</span> </p><p><span m='3032410'>PROFESSOR
  3:</span> <span m='3032567'>Absolutely.</span> <span m='3033190'>Once you</span>
  <span m='3033390'>fire the</span> <span m='3033590'>nukes</span> <span m='3034090'>you're
  not</span> <span m='3034420'>going to get another</span> <span m='3034580'>chance.</span>
  <span m='3036060'>So</span> <span m='3036430'>you</span> <span m='3036550'>can't</span>
  <span m='3036800'>particularly</span> <span m='3037120'>simulate</span> <span m='3037600'>through</span>
  <span m='3037900'>what</span> <span m='3038140'>the</span> <span m='3038260'>possible</span>
  <span m='3038740'>scenarios</span> <span m='3039210'>are going to be like.</span>
  <span m='3039620'>Yeah.</span> </p><p><span m='3039910'>AUDIENCE:</span> <span m='3039970'>So</span>
  <span m='3040030'>what</span> <span m='3040150'>if</span> <span m='3040240'>you</span>
  <span m='3040360'>had--</span> <span m='3040780'>I</span> <span m='3041080'>agree</span>
  <span m='3041260'>you</span> <span m='3041410'>can't</span> <span m='3042210'>simulate</span>
  <span m='3042570'>it</span> <span m='3042620'>in</span> <span m='3042730'>the</span>
  <span m='3042850'>real</span> <span m='3043150'>world.</span> <span m='3043390'>But</span>
  <span m='3043510'>what</span> <span m='3043790'>if</span> <span m='3043920'>you
  had</span> <span m='3044300'>a</span> <span m='3044530'>really</span> <span m='3044800'>good</span>
  <span m='3044950'>model</span> <span m='3045790'>and</span> <span m='3045880'>you</span>
  <span m='3046180'>just</span> <span m='3046480'>simulated</span> <span m='3046720'>based</span>
  <span m='3046990'>on</span> <span m='3047110'>that</span> <span m='3047260'>model?</span>
  </p><p><span m='3051640'>PROFESSOR 3:</span> <span m='3051715'>In</span> <span m='3051790'>that</span>
  <span m='3051910'>case,</span> <span m='3052210'>it</span> <span m='3052330'>probably</span>
  <span m='3052660'>depends</span> <span m='3052990'>on</span> <span m='3053080'>the</span>
  <span m='3053190'>quality</span> <span m='3053440'>of</span> <span m='3053840'>your
  model.</span> <span m='3055536'>If</span> <span m='3055902'>you have</span> <span
  m='3056270'>a</span> <span m='3056320'>good</span> <span m='3056500'>model</span>
  <span m='3056800'>for</span> <span m='3056950'>how</span> <span m='3057880'>World</span>
  <span m='3058120'>War</span> <span m='3058330'>III</span> <span m='3058800'>is going
  to</span> <span m='3059250'>[INAUDIBLE].</span> </p><p><span m='3059736'>[LAUGHTER]</span>
  </p><p><span m='3062850'>AUDIENCE:</span> <span m='3062915'>It</span> <span m='3062980'>is</span>
  <span m='3063190'>the</span> <span m='3063280'>case</span> <span m='3063550'>that</span>
  <span m='3063640'>the</span> <span m='3063700'>military</span> <span m='3064180'>does</span>
  <span m='3065170'>have</span> <span m='3065500'>simulators</span> <span m='3066130'>and</span>
  <span m='3066250'>they</span> <span m='3066400'>do</span> <span m='3066700'>war</span>
  <span m='3066940'>games</span> <span m='3067400'>in</span> <span m='3067570'>simulation.</span>
  </p><p><span m='3070200'>PROFESSOR 3:</span> <span m='3070335'>Yes,</span> <span
  m='3070870'>that's</span> <span m='3071270'>true.</span> <span m='3072070'>They</span>
  <span m='3072190'>could</span> <span m='3072340'>certainly</span> <span m='3072730'>try</span>
  <span m='3073210'>it</span> <span m='3073660'>and</span> <span m='3073820'>run</span>
  <span m='3074030'>MCTS</span> <span m='3074290'>if they wanted.</span> <span m='3074655'>And</span>
  <span m='3074760'>that's</span> <span m='3075010'>what</span> <span m='3075190'>happened</span>
  <span m='3075490'>in</span> <span m='3075580'>the</span> <span m='3075670'>movie.</span>
  </p><p><span m='3076560'>[INTERPOSING VOICES]</span> </p><p><span m='3079435'>AUDIENCE:</span>
  <span m='3079580'>And</span> <span m='3079725'>there</span> <span m='3079870'>you're
  putting your</span> <span m='3080070'>money</span> <span m='3080542'>in the</span>
  <span m='3081014'>simulation</span> <span m='3081486'>not in</span> <span m='3081958'>the--</span>
  </p><p><span m='3082430'>AUDIENCE:</span> <span m='3082530'>It's</span> <span m='3082630'>like</span>
  <span m='3083030'>having an</span> <span m='3083240'>MCTS</span> <span m='3083674'>play</span>
  <span m='3084108'><i>SOCOM</i></span> <span m='3084542'>or something</span> <span
  m='3084976'>like that.</span> </p><p><span m='3085410'>PROFESSOR 3:</span> <span
  m='3085500'>Yeah.</span> <span m='3085590'>It's</span> <span m='3086010'>definitely</span>
  <span m='3087000'>about</span> <span m='3087590'>putting</span> <span m='3087770'>money</span>
  <span m='3088544'>into</span> <span m='3088931'>the</span> <span m='3089320'>simulation</span>
  <span m='3089490'>and</span> <span m='3089860'>you get</span> <span m='3090230'>really
  good simulation.</span> <span m='3090600'>If</span> <span m='3090760'>you</span>
  <span m='3090880'>have</span> <span m='3091080'>a</span> <span m='3091395'>really
  good</span> <span m='3091710'>simulations</span> <span m='3092712'>then</span> <span
  m='3093140'>you</span> <span m='3093400'>[INAUDIBLE]</span> <span m='3093836'>to
  play</span> <span m='3094272'>WOPR.</span> <span m='3095490'>Yeah.</span> </p><p><span
  m='3096066'>AUDIENCE:</span> <span m='3096249'>Back</span> <span m='3096432'>to</span>
  <span m='3096800'>"Settlers"</span> <span m='3096970'>for a second.</span> <span
  m='3097470'>I'm curious</span> <span m='3097830'>if there's a</span> <span m='3097960'>way</span>
  <span m='3098760'>for</span> <span m='3098950'>the</span> <span m='3099070'>whole</span>
  <span m='3099780'>player</span> <span m='3100120'>training</span> <span m='3100600'>resources</span>
  <span m='3100810'>thing,</span> <span m='3101370'>or</span> <span m='3102350'>would</span>
  <span m='3102610'>it</span> <span m='3102730'>have</span> <span m='3102970'>to</span>
  <span m='3103060'>be</span> <span m='3103240'>only</span> <span m='3103520'>purely</span>
  <span m='3104620'>like using</span> <span m='3105360'>the</span> <span m='3105824'>ports.</span>
  </p><p><span m='3107216'>PROFESSOR 3:</span> <span m='3107448'>That's</span> <span
  m='3107680'>a good</span> <span m='3107860'>question.</span> <span m='3108760'>I
  haven't</span> <span m='3109240'>looked</span> <span m='3109420'>closely</span>
  <span m='3109851'>at</span> <span m='3110282'>whether they</span> <span m='3110713'>do
  that or not.</span> <span m='3113620'>If</span> <span m='3113980'>it's</span> <span
  m='3114130'>playing</span> <span m='3114550'>a</span> <span m='3114670'>two-player</span>
  <span m='3115040'>game,</span> <span m='3115400'>then</span> <span m='3115750'>I
  would</span> <span m='3116100'>imagine</span> <span m='3116450'>that they</span>
  <span m='3116640'>wouldn't</span> <span m='3117790'>because</span> <span m='3118290'>you
  don't</span> <span m='3118790'>really trade</span> <span m='3119290'>in</span> <span
  m='3119790'>to play a game.</span> <span m='3120290'>But if they</span> <span m='3120790'>weren't,</span>
  <span m='3121100'>I bet that</span> <span m='3121380'>you</span> <span m='3121510'>can</span>
  <span m='3121730'>incorporate</span> <span m='3121840'>it</span> <span m='3122185'>with
  WOPR.</span> </p><p><span m='3123786'>AUDIENCE:</span> <span m='3123921'>Is</span>
  <span m='3124056'>it</span> <span m='3124192'>limited to two-player</span> <span
  m='3124600'>games?</span> </p><p><span m='3125090'>PROFESSOR 3:</span> <span m='3125195'>No,</span>
  <span m='3125300'>not at</span> <span m='3125685'>all.</span> <span m='3126070'>In
  fact,</span> <span m='3126370'>there are</span> <span m='3126670'>lots of</span>
  <span m='3127160'>purchases</span> <span m='3127240'>that</span> <span m='3127480'>do</span>
  <span m='3127690'>only</span> <span m='3127870'>one-player</span> <span m='3128245'>games,</span>
  <span m='3128620'>where</span> <span m='3128890'>you</span> <span m='3130170'>think</span>
  <span m='3130460'>of</span> <span m='3130620'>what's</span> <span m='3130840'>the</span>
  <span m='3130900'>best</span> <span m='3131080'>movie</span> <span m='3131350'>that
  you</span> <span m='3131470'>can</span> <span m='3131620'>make.</span> </p><p><span
  m='3131770'>AUDIENCE:</span> <span m='3131915'>I</span> <span m='3132060'>know.</span>
  <span m='3132190'>But</span> <span m='3132410'>I</span> <span m='3132510'>mean,</span>
  <span m='3132720'>couldn't</span> <span m='3133171'>MCTS</span> <span m='3133622'>handle</span>
  <span m='3134073'>three-</span> <span m='3134524'>or</span> <span m='3134975'>four-player</span>
  <span m='3135426'>games?</span> </p><p><span m='3135877'>PROFESSOR 3:</span> <span
  m='3136102'>Yeah,</span> <span m='3136328'>it absolutely</span> <span m='3136780'>could.
  I'm</span> <span m='3136900'>not</span> <span m='3137050'>sure</span> <span m='3137610'>how</span>
  <span m='3137770'>they</span> <span m='3138265'>computed</span> <span m='3138760'>their</span>
  <span m='3138910'>head-to-head.</span> <span m='3139622'>That</span> <span m='3139980'>might</span>
  <span m='3140550'>be</span> <span m='3140750'>completely</span> <span m='3141050'>flat</span>
  <span m='3141430'>cursors.</span> <span m='3141730'>I'm</span> <span m='3141820'>not
  even</span> <span m='3142150'>sure</span> <span m='3142420'>how</span> <span m='3142570'>the</span>
  <span m='3142930'>settlers</span> <span m='3143290'>interact.</span> <span m='3144748'>Yeah.</span>
  </p><p><span m='3145234'>AUDIENCE:</span> <span m='3145396'>A</span> <span m='3145558'>quick</span>
  <span m='3145720'>question.</span> <span m='3145960'>So</span> <span m='3146240'>at
  first you know</span> <span m='3146990'>if</span> <span m='3147170'>I</span> <span
  m='3147410'>reduce</span> <span m='3147740'>the</span> <span m='3147990'>chess</span>
  <span m='3148310'>board</span> <span m='3148790'>to only</span> <span m='3149270'>4
  by</span> <span m='3149650'>4</span> <span m='3150026'>or</span> <span m='3150402'>5
  by 5,</span> <span m='3150780'>and</span> <span m='3151150'>I</span> <span m='3151520'>run</span>
  <span m='3151890'>MCTS</span> <span m='3152140'>versus</span> <span m='3152530'>the</span>
  <span m='3152920'>traditional</span> <span m='3153310'>algorithm</span> <span m='3153510'>that</span>
  <span m='3153970'>AlphaGo offered as</span> <span m='3154430'>a</span> <span m='3154620'>tree.</span>
  <span m='3155050'>Do you think</span> <span m='3155480'>MCTS</span> <span m='3155780'>will</span>
  <span m='3156480'>prefer</span> <span m='3157030'>theory</span> <span m='3157270'>and</span>
  <span m='3157746'>perform</span> <span m='3158222'>this</span> <span m='3158698'>computational</span>
  <span m='3159174'>requirement.</span> </p><p><span m='3160310'>PROFESSOR 3:</span>
  <span m='3160426'>The</span> <span m='3160542'>thing</span> <span m='3160660'>about</span>
  <span m='3160800'>the</span> <span m='3161040'>way</span> <span m='3161230'>that</span>
  <span m='3161340'>Deep</span> <span m='3161670'>Blue</span> <span m='3161960'>is,</span>
  <span m='3162510'>which</span> <span m='3162660'>is</span> <span m='3162820'>the</span>
  <span m='3163150'>AI</span> <span m='3163300'>that ended</span> <span m='3163673'>the</span>
  <span m='3164046'>Kasparov</span> <span m='3164570'>thing,</span> <span m='3164967'>a
  bunch of</span> <span m='3165364'>his</span> <span m='3165761'>chess</span> <span
  m='3166160'>grand master,</span> <span m='3167370'>is</span> <span m='3167650'>that</span>
  <span m='3168110'>it</span> <span m='3168310'>has</span> <span m='3168490'>a</span>
  <span m='3168880'>tremendous</span> <span m='3169140'>amount</span> <span m='3169400'>of</span>
  <span m='3169685'>heuristic</span> <span m='3169970'>information.</span> <span m='3170770'>There's</span>
  <span m='3170920'>a</span> <span m='3171010'>lot</span> <span m='3171160'>of</span>
  <span m='3171250'>external</span> <span m='3171700'>stuff</span> <span m='3172000'>that's</span>
  <span m='3172170'>incorporated</span> <span m='3172650'>into the</span> <span m='3172810'>system</span>
  <span m='3173500'>that</span> <span m='3173650'>makes</span> <span m='3173920'>it</span>
  <span m='3174310'>able</span> <span m='3174640'>to</span> <span m='3175260'>explore</span>
  <span m='3175630'>the</span> <span m='3175780'>best</span> <span m='3176173'>paths.</span>
  </p><p><span m='3177250'>What</span> <span m='3177460'>I</span> <span m='3177490'>would</span>
  <span m='3177580'>say</span> <span m='3177850'>is</span> <span m='3178000'>that</span>
  <span m='3179270'>knoledgesless</span> <span m='3179500'>MCTS</span> <span m='3181000'>based</span>
  <span m='3181240'>on</span> <span m='3181630'>randomness,</span> <span m='3182410'>would</span>
  <span m='3182680'>take</span> <span m='3182800'>a</span> <span m='3182900'>very</span>
  <span m='3183390'>long</span> <span m='3183730'>computational</span> <span m='3184210'>time</span>
  <span m='3184890'>to</span> <span m='3185250'>even</span> <span m='3185700'>become</span>
  <span m='3186030'>competitive</span> <span m='3187140'>with</span> <span m='3187600'>those</span>
  <span m='3187850'>kinds of</span> <span m='3188115'>algorithms,</span> <span m='3188380'>and</span>
  <span m='3188470'>probably</span> <span m='3189056'>feasibly</span> <span m='3189432'>never</span>
  <span m='3189810'>would.</span> <span m='3190496'>What</span> <span m='3190840'>if</span>
  <span m='3191185'>you</span> <span m='3191530'>incorporated</span> <span m='3191800'>heuristic</span>
  <span m='3192070'>information,</span> <span m='3192340'>I</span> <span m='3192430'>think</span>
  <span m='3192670'>that</span> <span m='3192760'>there's</span> <span m='3192960'>a</span>
  <span m='3193170'>bunch of</span> <span m='3193490'>hope</span> <span m='3193810'>in</span>
  <span m='3193870'>terms</span> <span m='3194180'>of</span> <span m='3194590'>getting</span>
  <span m='3194870'>MCTS</span> <span m='3195320'>to</span> <span m='3195630'>start</span>
  <span m='3195910'>performing</span> <span m='3196375'>better.</span> </p><p><span
  m='3196840'>And</span> <span m='3197140'>you can</span> <span m='3197410'>look</span>
  <span m='3197620'>at</span> <span m='3197830'>what</span> <span m='3198000'>next</span>
  <span m='3198220'>I'm</span> <span m='3198490'>going to</span> <span m='3198640'>talk
  about,</span> <span m='3198850'>AlphaGo.</span> <span m='3199460'>It</span> <span
  m='3199815'>takes inspiration</span> <span m='3200170'>for how</span> <span m='3200900'>we</span>
  <span m='3201330'>go about</span> <span m='3201760'>incorporating</span> <span m='3202040'>these</span>
  <span m='3202490'>new circuits.</span> </p><p><span m='3202940'>AUDIENCE:</span>
  <span m='3203025'>So</span> <span m='3203110'>only</span> <span m='3203530'>the
  circuit you [INAUDIBLE]</span> </p><p><span m='3207870'>PROFESSOR 3:</span> <span
  m='3207965'>It</span> <span m='3208060'>definitely</span> <span m='3208360'>seems</span>
  <span m='3208730'>like</span> <span m='3208840'>if you have a</span> <span m='3209120'>really</span>
  <span m='3209870'>good</span> <span m='3210360'>heuristic</span> <span m='3210900'>model</span>
  <span m='3211310'>for</span> <span m='3213120'>what</span> <span m='3213330'>good</span>
  <span m='3213790'>states</span> <span m='3214200'>in the game</span> <span m='3214470'>are,</span>
  <span m='3216120'>that</span> <span m='3216420'>if</span> <span m='3216780'>it's
  a</span> <span m='3217140'>smaller</span> <span m='3218130'>search</span> <span
  m='3218530'>space,</span> <span m='3219380'>that</span> <span m='3219790'>some</span>
  <span m='3220260'>other</span> <span m='3220440'>models</span> <span m='3221150'>could</span>
  <span m='3221420'>perform</span> <span m='3221820'>better.</span> <span m='3222420'>Although,</span>
  <span m='3222810'>I'm</span> <span m='3222960'>probably</span> <span m='3223230'>going</span>
  <span m='3223390'>to</span> <span m='3223600'>eat my foot</span> <span m='3224073'>here</span>
  <span m='3224546'>because this is going to be</span> <span m='3225019'>on</span>
  <span m='3225492'>OCW</span> <span m='3225965'>some massive amount,</span> <span
  m='3227390'>massive</span> <span m='3227610'>chess playing</span> <span m='3227810'>algorithms.</span>
  <span m='3229936'>Eat my</span> <span m='3230435'>shoe</span> <span m='3230934'>not</span>
  <span m='3231433'>my</span> <span m='3231932'>foot.</span> </p><p><span m='3233429'>[LAUGHTER]</span>
  </p><p><span m='3235430'>One</span> <span m='3235610'>last</span> <span m='3235820'>game.</span>
  <span m='3238100'>Does</span> <span m='3238250'>anyone</span> <span m='3238850'>know</span>
  <span m='3239180'>what</span> <span m='3239330'>this</span> <span m='3239530'>game</span>
  <span m='3239660'>is?</span> </p><p><span m='3240470'>AUDIENCE:</span> <span m='3240605'>"Total</span>
  <span m='3240740'>War?"</span> </p><p><span m='3241280'>PROFESSOR 3:</span> <span
  m='3241490'>Yes.</span> <span m='3242380'>Nice.</span> <span m='3243060'>This</span>
  <span m='3243300'>is</span> <span m='3243620'>"Rome,</span> <span m='3243890'>Total</span>
  <span m='3244110'>War II."</span> <span m='3244850'>It's</span> <span m='3245150'>a</span>
  <span m='3245210'>simulator</span> <span m='3246020'>for</span> <span m='3247190'>this</span>
  <span m='3247370'>tremendous</span> <span m='3249110'>real</span> <span m='3249350'>time</span>
  <span m='3249530'>strategy</span> <span m='3249890'>game,</span> <span m='3250570'>where</span>
  <span m='3250760'>you</span> <span m='3251030'>play,</span> <span m='3251630'>I</span>
  <span m='3251690'>think,</span> <span m='3251930'>the</span> <span m='3252020'>Roman</span>
  <span m='3252290'>Empire.</span> <span m='3253100'>And</span> <span m='3253580'>you're</span>
  <span m='3254060'>controlling</span> <span m='3254810'>armies</span> <span m='3255380'>and</span>
  <span m='3255760'>huge</span> <span m='3256460'>infrastructure</span> <span m='3256940'>systems</span>
  <span m='3257540'>that</span> <span m='3257720'>move</span> <span m='3258380'>and</span>
  <span m='3258500'>conquer</span> <span m='3259610'>states</span> <span m='3260030'>and</span>
  <span m='3260150'>continents,</span> <span m='3260980'>and</span> <span m='3261350'>meet</span>
  <span m='3261590'>in</span> <span m='3261680'>the</span> <span m='3261770'>field,</span>
  <span m='3262160'>and</span> <span m='3263420'>manage</span> <span m='3263750'>resources,</span>
  <span m='3264290'>and</span> <span m='3264380'>do</span> <span m='3264530'>all</span>
  <span m='3264680'>of</span> <span m='3264710'>these</span> <span m='3264920'>incredible</span>
  <span m='3265286'>diplomacy</span> <span m='3265652'>feats.</span> </p><p><span
  m='3266860'>And</span> <span m='3267380'>so</span> <span m='3267560'>do</span> <span
  m='3267660'>you</span> <span m='3267830'>think</span> <span m='3268010'>that</span>
  <span m='3268130'>this</span> <span m='3268250'>game</span> <span m='3268580'>can
  be</span> <span m='3268720'>solved by</span> <span m='3269050'>MCTS?</span> </p><p><span
  m='3269490'>AUDIENCE:</span> <span m='3269710'>Yes.</span> </p><p><span m='3269930'>AUDIENCE:</span>
  <span m='3270150'>Yes.</span> </p><p><span m='3272570'>PROFESSOR 3:</span> <span
  m='3272725'>Lets say no.</span> <span m='3273450'>But I guess I put it</span> <span
  m='3273700'>on</span> <span m='3273910'>here.</span> <span m='3274200'>So</span>
  <span m='3275280'>that's</span> <span m='3275660'>good</span> <span m='3275920'>on</span>
  <span m='3276100'>you.</span> </p><p><span m='3276870'>The</span> <span m='3277210'>way</span>
  <span m='3277490'>that the</span> <span m='3277770'>AI</span> <span m='3278660'>in</span>
  <span m='3278960'>"Rome,</span> <span m='3279170'>Total</span> <span m='3279350'>War</span>
  <span m='3279660'>II"</span> <span m='3280050'>is</span> <span m='3280440'>built</span>
  <span m='3280925'>is</span> <span m='3281410'>that</span> <span m='3281810'>it's
  built on an</span> <span m='3281940'>MCTS</span> <span m='3282270'>structure.</span>
  <span m='3283200'>And</span> <span m='3283400'>it in</span> <span m='3283640'>fact</span>
  <span m='3284000'>does</span> <span m='3284450'>do</span> <span m='3284720'>resource</span>
  <span m='3285110'>allocation</span> <span m='3285980'>and</span> <span m='3286400'>a</span>
  <span m='3286460'>lot</span> <span m='3286670'>of</span> <span m='3286760'>its</span>
  <span m='3286880'>political</span> <span m='3287270'>maneuvers</span> <span m='3287780'>based</span>
  <span m='3288140'>on</span> <span m='3288320'>Monte Carlo</span> <span m='3288757'>Tree</span>
  <span m='3289194'>Search</span> <span m='3289631'>moves.</span> <span m='3290070'>There
  are a bunch</span> <span m='3290190'>of</span> <span m='3290470'>reasons</span>
  <span m='3290920'>that they</span> <span m='3291090'>explain</span> <span m='3291355'>in</span>
  <span m='3291620'>the</span> <span m='3291976'>game</span> <span m='3292332'>for</span>
  <span m='3292690'>why</span> <span m='3292900'>they</span> <span m='3293030'>do</span>
  <span m='3293210'>this,</span> <span m='3293390'>or</span> <span m='3293510'>in</span>
  <span m='3293770'>papers</span> <span m='3294000'>released</span> <span m='3294280'>about
  the</span> <span m='3294685'>game.</span> <span m='3295090'>But</span> <span m='3295250'>one</span>
  <span m='3295400'>of</span> <span m='3295460'>the</span> <span m='3295520'>nice</span>
  <span m='3295730'>ones</span> <span m='3295970'>is</span> <span m='3296090'>that</span>
  <span m='3296330'>it's</span> <span m='3296460'>random,</span> <span m='3296835'>which
  means that you're</span> <span m='3297210'>never</span> <span m='3297530'>going</span>
  <span m='3297650'>to</span> <span m='3297710'>play</span> <span m='3297980'>against</span>
  <span m='3298190'>the</span> <span m='3298290'>same</span> <span m='3298620'>kind
  of</span> <span m='3298915'>AI</span> <span m='3299210'>twice</span> <span m='3299870'>because</span>
  <span m='3300440'>every</span> <span m='3300710'>time</span> <span m='3301280'>the</span>
  <span m='3301370'>set</span> <span m='3301550'>of</span> <span m='3301610'>decisions</span>
  <span m='3302010'>that it's</span> <span m='3302150'>going</span> <span m='3302300'>to</span>
  <span m='3302360'>think</span> <span m='3302540'>about</span> <span m='3302750'>is</span>
  <span m='3302960'>completely</span> <span m='3303090'>different.</span> </p><p><span
  m='3303736'>AUDIENCE:</span> <span m='3303845'>I</span> <span m='3303954'>have</span>
  <span m='3304063'>a</span> <span m='3304172'>quick question.</span> </p><p><span
  m='3304608'>PROFESSOR 3:</span> <span m='3304826'>Yeah.</span> </p><p><span m='3305044'>AUDIENCE:</span>
  <span m='3305262'>So</span> <span m='3305480'>if I</span> <span m='3305820'>want
  to model</span> <span m='3306290'>any game</span> <span m='3306500'>with</span>
  <span m='3306882'>MCTS,</span> <span m='3307646'>does</span> <span m='3308030'>it</span>
  <span m='3308210'>have</span> <span m='3308390'>to</span> <span m='3308480'>be</span>
  <span m='3308870'>that</span> <span m='3309020'>the</span> <span m='3309514'>actions</span>
  <span m='3310008'>in</span> <span m='3310502'>playing a game</span> <span m='3310996'>has
  to be</span> <span m='3311490'>able to</span> <span m='3311984'>discretize.</span>
  </p><p><span m='3314460'>PROFESSOR 3:</span> <span m='3314655'>Yes.</span> <span
  m='3314980'>So</span> <span m='3315190'>far</span> <span m='3315390'>as</span> <span
  m='3315510'>I</span> <span m='3315680'>know,</span> <span m='3316240'>I haven't</span>
  <span m='3316590'>seen many</span> <span m='3316990'>continuous</span> <span m='3317410'>variants</span>
  <span m='3317755'>in</span> <span m='3318100'>MCTS.</span> <span m='3319520'>And</span>
  <span m='3319680'>so,</span> <span m='3319980'>I</span> <span m='3320040'>think</span>
  <span m='3320250'>that</span> <span m='3320370'>it</span> <span m='3320460'>is</span>
  <span m='3320650'>about</span> <span m='3320860'>choosing</span> <span m='3321520'>these</span>
  <span m='3321670'>reactions,</span> <span m='3322510'>which</span> <span m='3322680'>on</span>
  <span m='3323310'>it's</span> <span m='3323540'>most</span> <span m='3323984'>narrow</span>
  <span m='3324428'>level</span> <span m='3324872'>does</span> <span m='3325316'>actually
  bring</span> <span m='3325760'>it down to here.</span> <span m='3326440'>I think</span>
  <span m='3326850'>one</span> <span m='3327010'>of</span> <span m='3327090'>the</span>
  <span m='3327150'>reasons</span> <span m='3327390'>that</span> <span m='3327480'>this</span>
  <span m='3327630'>is</span> <span m='3327720'>nice</span> <span m='3327960'>is</span>
  <span m='3328050'>that</span> <span m='3328140'>there</span> <span m='3328230'>are</span>
  <span m='3328320'>so</span> <span m='3328710'>many</span> <span m='3329080'>different</span>
  <span m='3329330'>decisions that</span> <span m='3329740'>could</span> <span m='3329940'>be</span>
  <span m='3330090'>made</span> <span m='3330630'>that</span> <span m='3330900'>MCTS</span>
  <span m='3331230'>is</span> <span m='3331535'>really the</span> <span m='3331840'>only</span>
  <span m='3332180'>approach</span> <span m='3332520'>that</span> <span m='3332610'>could</span>
  <span m='3332730'>even</span> <span m='3332970'>begin</span> <span m='3333570'>to</span>
  <span m='3333700'>handle</span> <span m='3334010'>the</span> <span m='3334380'>massive</span>
  <span m='3334750'>branching</span> <span m='3334910'>factor</span> <span m='3335320'>that's
  associated</span> <span m='3335730'>with</span> <span m='3336140'>the game</span>
  <span m='3336450'>Rome, Total</span> <span m='3336903'>War.</span> <span m='3337810'>Yeah.</span>
  </p><p><span m='3338668'>AUDIENCE:</span> <span m='3338917'>This is also</span>
  <span m='3339166'>the</span> <span m='3339664'>consequence</span> <span m='3340162'>of</span>
  <span m='3340660'>this</span> <span m='3341100'>year you get the</span> <span m='3341510'>play</span>
  <span m='3341920'>off when this</span> <span m='3342330'>game comes.</span> </p><p><span
  m='3344020'>PROFESSOR 3:</span> <span m='3344085'>That's</span> <span m='3344150'>interesting.</span>
  <span m='3344740'>That's</span> <span m='3345205'>probably</span> <span m='3345670'>totally</span>
  <span m='3346135'>it.</span> <span m='3346600'>That's</span> <span m='3346760'>cool.</span>
  <span m='3350640'>That's</span> <span m='3351060'>everything</span> <span m='3351540'>about</span>
  <span m='3351840'>how</span> <span m='3352050'>the</span> <span m='3352200'>algorithm</span>
  <span m='3352560'>actually</span> <span m='3352860'>works.</span> </p><p><span m='3354710'>I'm</span>
  <span m='3355183'>going to</span> <span m='3355656'>pass it off to</span> <span
  m='3356130'>Nick, and</span> <span m='3356340'>he's going to</span> <span m='3356490'>talk
  to us</span> <span m='3357000'>about</span> <span m='3357540'>some</span> <span
  m='3357810'>actual</span> <span m='3358210'>limitations</span> <span m='3358550'>for
  this</span> <span m='3358890'>game</span> <span m='3359230'>[INAUDIBLE].</span>
  </p><p><span m='3364430'>PROFESSOR 3:</span> <span m='3364510'>So</span> <span m='3364590'>as</span>
  <span m='3364670'>you</span> <span m='3364750'>have</span> <span m='3365173'>said,</span>
  <span m='3365596'>I'm going to start</span> <span m='3366020'>diving</span> <span
  m='3366400'>into some</span> <span m='3366810'>applications</span> <span m='3367590'>here.</span>
  <span m='3367980'>And</span> <span m='3368310'>not</span> <span m='3368560'>only</span>
  <span m='3368800'>applications</span> <span m='3369480'>but</span> <span m='3370780'>also</span>
  <span m='3371170'>some</span> <span m='3371330'>modifications</span> <span m='3372180'>or</span>
  <span m='3372300'>augmentations</span> <span m='3372550'>of</span> <span m='3372890'>MCTS.</span>
  <span m='3373460'>It</span> <span m='3373920'>should</span> <span m='3374050'>hopefully</span>
  <span m='3374540'>clarify</span> <span m='3375540'>some</span> <span m='3375780'>of</span>
  <span m='3375840'>the</span> <span m='3375960'>side</span> <span m='3376280'>questions</span>
  <span m='3376590'>you all have</span> <span m='3376930'>been</span> <span m='3377070'>having</span>
  <span m='3377490'>on</span> <span m='3378420'>slight</span> <span m='3378780'>tweaks</span>
  <span m='3379200'>to</span> <span m='3379650'>MCTS.</span> </p><p><span m='3381610'>Now</span>
  <span m='3381790'>let's</span> <span m='3381990'>get</span> <span m='3382220'>started.</span>
  <span m='3383470'>Wait for</span> <span m='3383810'>it.</span> <span m='3384230'>Now</span>
  <span m='3384380'>let's</span> <span m='3384650'>get</span> <span m='3384870'>started.</span>
  </p><p><span m='3385318'>[LAUGHTER]</span> </p><p><span m='3385766'>Part</span>
  <span m='3386214'>III,</span> <span m='3387110'>applications.</span> <span m='3387600'>First</span>
  <span m='3387870'>thing</span> <span m='3388255'>we're going to</span> <span m='3388640'>look
  at</span> <span m='3389025'>is an</span> <span m='3389410'>MCTS-based</span> <span
  m='3389770'>"Mario"</span> <span m='3389980'>controller.</span> <span m='3391110'>And</span>
  <span m='3391290'>"Mario"</span> <span m='3391545'>might</span> <span m='3392100'>seem</span>
  <span m='3392310'>like</span> <span m='3393360'>some</span> <span m='3393960'>weird</span>
  <span m='3394260'>thing</span> <span m='3394530'>to</span> <span m='3394600'>test</span>
  <span m='3394740'>AI</span> <span m='3395110'>on,</span> <span m='3395290'>but</span>
  <span m='3395590'>there</span> <span m='3395890'>actually</span> <span m='3396200'>is</span>
  <span m='3396490'>a</span> <span m='3396860'>"Super</span> <span m='3397170'>Mario</span>
  <span m='3397435'>Bros"</span> <span m='3397700'>AI</span> <span m='3398000'>benchmark,</span>
  <span m='3398320'>which</span> <span m='3398580'>it used</span> <span m='3399030'>to
  test a lot of</span> <span m='3399480'>AI</span> <span m='3399930'>on</span> <span
  m='3400380'>how well</span> <span m='3400500'>they could</span> <span m='3400945'>play
  this</span> <span m='3401390'>platform.</span> </p><p><span m='3402280'>In</span>
  <span m='3402480'>case</span> <span m='3402710'>any</span> <span m='3403110'>of</span>
  <span m='3403430'>you</span> <span m='3403590'>don't</span> <span m='3403770'>know</span>
  <span m='3404540'>what</span> <span m='3404750'>"Super</span> <span m='3405020'>Mario</span>
  <span m='3405290'>Bros"</span> <span m='3405600'>is,</span> <span m='3406080'>this
  is</span> <span m='3406260'>a</span> <span m='3406390'>screenshot.</span> <span
  m='3407430'>Basically,</span> <span m='3407720'>you</span> <span m='3407890'>control</span>
  <span m='3408250'>this</span> <span m='3408420'>one</span> <span m='3408630'>character.</span>
  <span m='3409170'>It's</span> <span m='3409350'>a</span> <span m='3409380'>single-player</span>
  <span m='3410010'>game.</span> </p><p><span m='3412780'>The</span> <span m='3413020'>ultimate</span>
  <span m='3413550'>goal</span> <span m='3413850'>is</span> <span m='3414000'>to</span>
  <span m='3414060'>reach</span> <span m='3414330'>this</span> <span m='3414930'>flag</span>
  <span m='3415410'>at the</span> <span m='3415665'>end.</span> <span m='3415920'>But</span>
  <span m='3416280'>along</span> <span m='3416550'>the</span> <span m='3416610'>way</span>
  <span m='3417270'>there's</span> <span m='3417550'>enemies,</span> <span m='3418180'>there's</span>
  <span m='3418550'>some</span> <span m='3418920'>bonus</span> <span m='3419640'>shrooms</span>
  <span m='3420150'>you</span> <span m='3420240'>can</span> <span m='3420360'>get.</span>
  <span m='3421046'>If</span> <span m='3421432'>you</span> <span m='3421820'>break</span>
  <span m='3422070'>open</span> <span m='3422350'>some</span> <span m='3422550'>boxes</span>
  <span m='3422835'>you</span> <span m='3423120'>might get</span> <span m='3423430'>coins,</span>
  <span m='3423870'>things</span> <span m='3424080'>like</span> <span m='3424200'>that.</span>
  </p><p><span m='3426360'>But</span> <span m='3426600'>first,</span> <span m='3427040'>let's</span>
  <span m='3427370'>just</span> <span m='3427890'>highlight</span> <span m='3428340'>some
  of the</span> <span m='3429140'>modifications</span> <span m='3430020'>that</span>
  <span m='3430230'>need</span> <span m='3430380'>to</span> <span m='3430440'>be</span>
  <span m='3430560'>made,</span> <span m='3430830'>or</span> <span m='3430920'>some</span>
  <span m='3431040'>of</span> <span m='3431100'>the</span> <span m='3431220'>differences</span>
  <span m='3431700'>between</span> <span m='3432010'>vanilla</span> <span m='3432100'>MCTS</span>
  <span m='3433510'>and an</span> <span m='3433680'>MCTS</span> <span m='3433920'>that's</span>
  <span m='3434210'>going</span> <span m='3434330'>to</span> <span m='3434400'>be</span>
  <span m='3434540'>able</span> <span m='3434720'>to</span> <span m='3434820'>work</span>
  <span m='3435060'>for</span> <span m='3435240'>"Mario."</span> <span m='3436590'>First</span>
  <span m='3436723'>thing</span> <span m='3436856'>is</span> <span m='3436990'>that
  it's</span> <span m='3437310'>single-player.</span> <span m='3438296'>The</span>
  <span m='3438632'>second</span> <span m='3438970'>is,</span> <span m='3439270'>we
  use</span> <span m='3439560'>a</span> <span m='3439590'>slightly</span> <span m='3440070'>different</span>
  <span m='3440430'>simulation</span> <span m='3441000'>strategy</span> <span m='3441640'>than</span>
  <span m='3442260'>the</span> <span m='3442950'>initial</span> <span m='3443220'>just</span>
  <span m='3443490'>vanilla</span> <span m='3444110'>simulation.</span> </p><p><span
  m='3445130'>And</span> <span m='3445260'>someone</span> <span m='3445590'>actually</span>
  <span m='3445770'>hinted</span> <span m='3445920'>at</span> <span m='3446640'>doing</span>
  <span m='3446910'>more than</span> <span m='3447060'>one</span> <span m='3447410'>simulation</span>
  <span m='3447760'>because</span> <span m='3448110'>you,</span> <span m='3448875'>you're</span>
  <span m='3449370'>watching</span> <span m='3449580'>us to n</span> <span m='3449790'>simulations,</span>
  <span m='3450830'>I</span> <span m='3450880'>think.</span> <span m='3452280'>We'll</span>
  <span m='3452730'>touch</span> <span m='3452970'>on</span> <span m='3453150'>that.</span>
  <span m='3453810'>Then</span> <span m='3454140'>this</span> <span m='3454320'>also</span>
  <span m='3455010'>introduces</span> <span m='3455550'>what</span> <span m='3455790'>I</span>
  <span m='3455940'>would</span> <span m='3456060'>consider</span> <span m='3456630'>to</span>
  <span m='3456780'>be</span> <span m='3457170'>domain</span> <span m='3457620'>knowledge.</span>
  </p><p><span m='3458840'>Then</span> <span m='3459000'>finally,</span> <span m='3460180'>there's</span>
  <span m='3460290'>a</span> <span m='3460550'>50</span> <span m='3460960'>to</span>
  <span m='3461370'>40</span> <span m='3461780'>millisecond</span> <span m='3462190'>computation</span>
  <span m='3462600'>time.</span> <span m='3462900'>And that has</span> <span m='3463250'>to
  do</span> <span m='3463600'>with</span> <span m='3463730'>the</span> <span m='3463830'>frames</span>
  <span m='3464070'>per second</span> <span m='3464460'>of</span> <span m='3464550'>the</span>
  <span m='3464640'>game.</span> <span m='3465270'>So</span> <span m='3465960'>you</span>
  <span m='3466220'>would</span> <span m='3466390'>think</span> <span m='3466620'>that</span>
  <span m='3466800'>"Mario"</span> <span m='3467190'>is</span> <span m='3467340'>a</span>
  <span m='3467430'>continuous</span> <span m='3467910'>game,</span> <span m='3468240'>but</span>
  <span m='3468490'>if</span> <span m='3468600'>we</span> <span m='3468890'>discretize</span>
  <span m='3469170'>time</span> <span m='3470060'>into</span> <span m='3470340'>these</span>
  <span m='3470650'>chunks,</span> <span m='3470950'>then</span> <span m='3471210'>we
  can</span> <span m='3471470'>use</span> <span m='3471710'>MTTS.</span> </p><p><span
  m='3474380'>Now</span> <span m='3474710'>let's just</span> <span m='3475100'>think</span>
  <span m='3475290'>about</span> <span m='3475680'>how</span> <span m='3475830'>we</span>
  <span m='3475950'>could</span> <span m='3476280'>possibly</span> <span m='3476570'>formulate</span>
  <span m='3477340'>this</span> <span m='3477480'>problem.</span> <span m='3477840'>Can
  anyone</span> <span m='3478160'>think</span> <span m='3478560'>of</span> <span m='3479400'>what</span>
  <span m='3479730'>each</span> <span m='3479910'>of</span> <span m='3479970'>these</span>
  <span m='3480180'>nodes</span> <span m='3480630'>would</span> <span m='3480750'>be</span>
  <span m='3481080'>if we're</span> <span m='3481280'>playing</span> <span m='3481430'>"Super</span>
  <span m='3481780'>Mario?"</span> </p><p><span m='3482586'>AUDIENCE:</span> <span
  m='3482829'>Jump.</span> </p><p><span m='3484530'>PROFESSOR 3:</span> <span m='3484580'>Sorry?</span>
  </p><p><span m='3484960'>AUDIENCE:</span> <span m='3485125'>Jump.</span> <span m='3485290'>It
  would</span> <span m='3485460'>be</span> <span m='3485960'>like,</span> <span m='3486460'>first</span>
  <span m='3486960'>node you're going to jump.</span> </p><p><span m='3487960'>PROFESSOR
  3:</span> <span m='3488210'>That</span> <span m='3488460'>might</span> <span m='3488870'>be</span>
  <span m='3489140'>a</span> <span m='3489440'>way</span> <span m='3489870'>to</span>
  <span m='3490930'>formulate</span> <span m='3491470'>it.</span> <span m='3491600'>But</span>
  <span m='3492185'>I think that</span> <span m='3492550'>could get--</span> </p><p><span
  m='3493522'>AUDIENCE:</span> <span m='3493726'>Oh,</span> <span m='3493930'>it's</span>
  <span m='3494260'>not your</span> <span m='3494590'>control</span> <span m='3495087'>at</span>
  <span m='3495584'>inputs</span> <span m='3496081'>[INAUDIBLE].</span> </p><p><span
  m='3496580'>PROFESSOR 3:</span> <span m='3496735'>Right.</span> <span m='3496890'>So</span>
  <span m='3497130'>the</span> <span m='3497250'>node</span> <span m='3497610'>itself</span>
  <span m='3497880'>isn't</span> <span m='3498300'>going</span> <span m='3498540'>to</span>
  <span m='3498630'>be</span> <span m='3498960'>an</span> <span m='3499410'>action.</span>
  </p><p><span m='3502110'>AUDIENCE:</span> <span m='3502265'>Equal</span> <span m='3502420'>frames.</span>
  </p><p><span m='3503490'>PROFESSOR 3:</span> <span m='3503650'>Yeah,</span> <span
  m='3503810'>basically.</span> <span m='3504270'>So</span> <span m='3505190'>it's</span>
  <span m='3505440'>going</span> <span m='3505620'>to</span> <span m='3505680'>be</span>
  <span m='3505810'>the</span> <span m='3505920'>state</span> <span m='3506630'>of</span>
  <span m='3506710'>a</span> <span m='3506850'>game,</span> <span m='3507220'>what
  we'll call a</span> <span m='3507620'>state.</span> <span m='3508490'>So</span>
  <span m='3508800'>it's</span> <span m='3508970'>basically</span> <span m='3509220'>just
  a</span> <span m='3509410'>screen</span> <span m='3509890'>grab.</span> <span m='3510360'>And</span>
  <span m='3510450'>it take</span> <span m='3510795'>it,</span> <span m='3511140'>in</span>
  <span m='3511320'>this</span> <span m='3511530'>case,</span> <span m='3511850'>it's</span>
  <span m='3511990'>a</span> <span m='3512090'>15</span> <span m='3512470'>by</span>
  <span m='3512780'>19</span> <span m='3513130'>grid</span> <span m='3513570'>screen</span>
  <span m='3513975'>grab of the</span> <span m='3514380'>game.</span> </p><p><span
  m='3515190'>And</span> <span m='3515370'>it will</span> <span m='3515550'>have</span>
  <span m='3515790'>information</span> <span m='3516270'>about--</span> <span m='3516600'>it</span>
  <span m='3517083'>knows</span> <span m='3517566'>Mario's position,</span> <span
  m='3518050'>it knows</span> <span m='3518280'>the</span> <span m='3518700'>enemy's</span>
  <span m='3519120'>position,</span> <span m='3519800'>position</span> <span m='3520240'>of
  the</span> <span m='3520450'>blocks,</span> <span m='3521467'>et</span> <span m='3521844'>cetera.</span>
  <span m='3522600'>And</span> <span m='3522700'>then,</span> <span m='3523346'>as</span>
  <span m='3523782'>Yo was</span> <span m='3524220'>saying,</span> <span m='3524610'>in</span>
  <span m='3525080'>MCTS</span> <span m='3525370'>we</span> <span m='3525480'>have</span>
  <span m='3525670'>values</span> <span m='3526090'>associated</span> <span m='3526620'>with</span>
  <span m='3526770'>our</span> <span m='3526920'>nodes.</span> <span m='3527660'>And
  so</span> <span m='3527780'>it will</span> <span m='3527940'>also have</span> <span
  m='3528330'>a</span> <span m='3528540'>value.</span> <span m='3529240'>But</span>
  <span m='3529540'>we'll</span> <span m='3529780'>get</span> <span m='3530030'>into</span>
  <span m='3530980'>the</span> <span m='3531380'>value</span> <span m='3531780'>in
  the</span> <span m='3531840'>next</span> <span m='3532060'>slide</span> <span m='3532890'>because</span>
  <span m='3533230'>I</span> <span m='3533680'>can't</span> <span m='3534130'>really
  fit</span> <span m='3534580'>it all in here.</span> </p><p><span m='3536820'>With</span>
  <span m='3537010'>that</span> <span m='3537340'>being said</span> <span m='3537830'>for</span>
  <span m='3538070'>our</span> <span m='3538190'>node,</span> <span m='3538580'>that</span>
  <span m='3538930'>being</span> <span m='3539280'>the state of the</span> <span m='3539630'>game,</span>
  <span m='3540970'>what</span> <span m='3541120'>makes</span> <span m='3541410'>sense</span>
  <span m='3541560'>for the</span> <span m='3542025'>edge?</span> <span m='3542490'>Does
  anyone know?</span> <span m='3543420'>How</span> <span m='3543570'>do we</span>
  <span m='3543690'>transition</span> <span m='3544110'>from</span> <span m='3544290'>one</span>
  <span m='3544560'>state</span> <span m='3544920'>to another</span> <span m='3545280'>state?</span>
  </p><p><span m='3545990'>AUDIENCE:</span> <span m='3546195'>Jump.</span> </p><p><span
  m='3547220'>PROFESSOR 3:</span> <span m='3547355'>Yeah,</span> <span m='3547490'>exactly.</span>
  <span m='3547710'>So</span> <span m='3547950'>this</span> <span m='3548390'>is</span>
  <span m='3548490'>where the</span> <span m='3548790'>jump</span> <span m='3549150'>and
  all</span> <span m='3549310'>the</span> <span m='3549370'>action have</span> <span
  m='3549750'>been played.</span> <span m='3550160'>So</span> <span m='3550330'>the</span>
  <span m='3550450'>actions</span> <span m='3550950'>that</span> <span m='3551310'>you</span>
  <span m='3551540'>take--</span> <span m='3551970'>I didn't</span> <span m='3552295'>list</span>
  <span m='3552620'>all</span> <span m='3552810'>the</span> <span m='3552870'>actions.</span>
  <span m='3553230'>You</span> <span m='3553290'>can</span> <span m='3553530'>also
  have</span> <span m='3553680'>a</span> <span m='3553760'>jump</span> <span m='3554235'>left,</span>
  <span m='3554710'>jump right,</span> <span m='3555100'>all those</span> <span m='3555572'>things.</span>
  </p><p><span m='3556516'>But</span> <span m='3556990'>basically,</span> <span m='3557330'>the</span>
  <span m='3557645'>actions are what</span> <span m='3557960'>takes you</span> <span
  m='3558225'>from</span> <span m='3558490'>state</span> <span m='3558800'>to state.</span>
  <span m='3559060'>So I just</span> <span m='3559320'>drew</span> <span m='3559670'>out</span>
  <span m='3561880'>what</span> <span m='3562220'>a node</span> <span m='3562560'>might</span>
  <span m='3562890'>look like if</span> <span m='3563220'>you</span> <span m='3563400'>used
  the</span> <span m='3563600'>jump</span> <span m='3564120'>action.</span> <span
  m='3564375'>You might have</span> <span m='3564630'>Mario</span> <span m='3565062'>go
  up in the</span> <span m='3565494'>sky.</span> <span m='3567078'>Are</span> <span
  m='3567576'>there</span> <span m='3568074'>questions?</span> </p><p><span m='3568572'>AUDIENCE:</span>
  <span m='3568738'>Does</span> <span m='3568904'>it</span> <span m='3569070'>just</span>
  <span m='3569430'>run</span> <span m='3569940'>the</span> <span m='3570030'>rest
  of it?</span> <span m='3570790'>Because</span> <span m='3571120'>that</span> <span
  m='3571280'>little thing's</span> <span m='3571742'>moving</span> <span m='3572666'>as</span>
  <span m='3573128'>they move on?</span> </p><p><span m='3574520'>PROFESSOR 3:</span>
  <span m='3574645'>Well,</span> <span m='3574770'>it's</span> <span m='3575245'>not</span>
  <span m='3575720'>moving in</span> <span m='3575910'>this</span> <span m='3576360'>moment</span>
  <span m='3576720'>in</span> <span m='3576810'>time.</span> <span m='3577260'>We're</span>
  <span m='3577470'>discretizing</span> <span m='3577650'>time</span> <span m='3578030'>right</span>
  <span m='3578410'>now.</span> </p><p><span m='3579856'>AUDIENCE:</span> <span m='3579964'>But</span>
  <span m='3580072'>I'm</span> <span m='3580180'>saying,</span> <span m='3580560'>if</span>
  <span m='3580710'>your</span> <span m='3581020'>action</span> <span m='3581360'>is</span>
  <span m='3581520'>jump,</span> <span m='3581840'>just</span> <span m='3583800'>you</span>
  <span m='3584105'>would have</span> <span m='3584410'>1,000</span> <span m='3584900'>nodes</span>
  <span m='3585290'>because</span> <span m='3585530'>if</span> <span m='3585590'>you</span>
  <span m='3585680'>did</span> <span m='3586100'>plan</span> <span m='3586430'>out</span>
  <span m='3586650'>where</span> <span m='3586800'>that</span> <span m='3586930'>thing's</span>
  <span m='3587200'>moving,</span> <span m='3587470'>left or</span> <span m='3587870'>right,</span>
  <span m='3588130'>then</span> <span m='3588420'>it could be--</span> </p><p><span
  m='3588710'>PROFESSOR 3:</span> <span m='3588810'>Yeah,</span> <span m='3588910'>right.</span>
  <span m='3589170'>So</span> <span m='3589990'>in</span> <span m='3590250'>each</span>
  <span m='3590460'>state</span> <span m='3590790'>we</span> <span m='3590940'>have</span>
  <span m='3591330'>the enemy</span> <span m='3591660'>position.</span> <span m='3592450'>And</span>
  <span m='3592550'>we</span> <span m='3592560'>know</span> <span m='3592830'>the</span>
  <span m='3593105'>speed and</span> <span m='3593380'>direction.</span> <span m='3594110'>And</span>
  <span m='3594290'>so</span> <span m='3595050'>we</span> <span m='3595170'>know</span>
  <span m='3595640'>when we</span> <span m='3595730'>go</span> <span m='3595880'>from</span>
  <span m='3596010'>this</span> <span m='3596190'>node</span> <span m='3596640'>to</span>
  <span m='3596850'>one</span> <span m='3597060'>time step</span> <span m='3597290'>later,</span>
  <span m='3597620'>we'll</span> <span m='3597780'>know</span> <span m='3598030'>where</span>
  <span m='3598350'>the</span> <span m='3598590'>enemy's</span> <span m='3598730'>moving.</span>
  <span m='3600694'>Any</span> <span m='3601185'>other</span> <span m='3601676'>questions?</span>
  </p><p><span m='3604530'>Moving</span> <span m='3604934'>on.</span> <span m='3606550'>Sorry.</span>
  <span m='3607290'>Let</span> <span m='3607380'>me</span> <span m='3607470'>just</span>
  <span m='3607620'>preface</span> <span m='3608040'>this</span> <span m='3608190'>part</span>
  <span m='3608440'>real</span> <span m='3608490'>quick.</span> <span m='3609080'>So</span>
  <span m='3609480'>in</span> <span m='3609600'>our</span> <span m='3609750'>other</span>
  <span m='3610080'>simulations,</span> <span m='3610890'>at</span> <span m='3611010'>the</span>
  <span m='3611130'>end</span> <span m='3611250'>of</span> <span m='3611310'>the</span>
  <span m='3611400'>simulation</span> <span m='3611970'>we</span> <span m='3612060'>would</span>
  <span m='3612150'>get</span> <span m='3612300'>either</span> <span m='3612450'>a</span>
  <span m='3612600'>one</span> <span m='3612980'>or a</span> <span m='3613380'>zero,</span>
  <span m='3613760'>if</span> <span m='3614060'>we'd won</span> <span m='3614510'>tic-tac-toe</span>
  <span m='3614700'>or</span> <span m='3614940'>we</span> <span m='3615210'>lost</span>
  <span m='3615650'>tic-tac-toe.</span> </p><p><span m='3617910'>But</span> <span
  m='3618170'>that</span> <span m='3618360'>won't</span> <span m='3618600'>really</span>
  <span m='3618840'>work</span> <span m='3619160'>too well</span> <span m='3619440'>here</span>
  <span m='3619740'>because</span> <span m='3621420'>there's</span> <span m='3621600'>a</span>
  <span m='3621630'>lot</span> <span m='3621870'>of other</span> <span m='3622050'>factors</span>
  <span m='3622560'>that</span> <span m='3623040'>go</span> <span m='3623220'>into</span>
  <span m='3623400'>play</span> <span m='3623760'>when</span> <span m='3623850'>you're</span>
  <span m='3623970'>playing</span> <span m='3624210'>"Mario."</span> <span m='3625410'>Also,</span>
  <span m='3625800'>if</span> <span m='3625920'>you're</span> <span m='3626010'>doing
  a</span> <span m='3626250'>simulation,</span> <span m='3627530'>more than</span>
  <span m='3627990'>likely,</span> <span m='3628450'>you're</span> <span m='3628690'>going</span>
  <span m='3628830'>to</span> <span m='3628940'>end</span> <span m='3629160'>up</span>
  <span m='3629360'>hitting</span> <span m='3629670'>an</span> <span m='3629940'>enemy</span>
  <span m='3630210'>and</span> <span m='3630470'>dying</span> <span m='3630850'>or</span>
  <span m='3630940'>falling</span> <span m='3631140'>into</span> <span m='3631400'>a</span>
  <span m='3631490'>gap</span> <span m='3631820'>and</span> <span m='3631930'>dying.</span>
  <span m='3632380'>So</span> <span m='3632480'>a</span> <span m='3632510'>lot</span>
  <span m='3632700'>of these</span> <span m='3632760'>simulations</span> <span m='3633300'>might</span>
  <span m='3633780'>all</span> <span m='3634080'>return</span> <span m='3634490'>zero.</span>
  <span m='3634830'>And</span> <span m='3635290'>that</span> <span m='3635460'>is,</span>
  <span m='3635610'>you</span> <span m='3636090'>can't really</span> <span m='3636270'>distinguish</span>
  <span m='3636555'>between</span> <span m='3637200'>them.</span> </p><p><span m='3638440'>So</span>
  <span m='3638920'>this</span> <span m='3639050'>is</span> <span m='3639140'>why</span>
  <span m='3639350'>I</span> <span m='3639390'>say,</span> <span m='3640350'>this</span>
  <span m='3640500'>version</span> <span m='3640800'>of</span> <span m='3641130'>MCTS</span>
  <span m='3641670'>introduces</span> <span m='3642090'>what</span> <span m='3642210'>I
  would</span> <span m='3642470'>consider</span> <span m='3642900'>to</span> <span
  m='3642990'>be</span> <span m='3643200'>domain</span> <span m='3643560'>knowledge.</span>
  <span m='3644370'>Basically,</span> <span m='3645170'>they're</span> <span m='3645400'>assigning</span>
  <span m='3645840'>scores</span> <span m='3646860'>to</span> <span m='3647430'>potential</span>
  <span m='3648630'>things</span> <span m='3648960'>that</span> <span m='3649130'>could</span>
  <span m='3649220'>happened</span> <span m='3649530'>along</span> <span m='3649830'>the</span>
  <span m='3649890'>way.</span> <span m='3650680'>And</span> <span m='3650700'>this</span>
  <span m='3650880'>is</span> <span m='3650970'>basically</span> <span m='3651390'>telling</span>
  <span m='3652110'>the</span> <span m='3652260'>AI</span> <span m='3652770'>that</span>
  <span m='3653360'>collecting</span> <span m='3653950'>a</span> <span m='3654200'>flower</span>
  <span m='3655630'>is</span> <span m='3655820'>a</span> <span m='3655850'>little</span>
  <span m='3656070'>bit</span> <span m='3656220'>better</span> <span m='3656640'>than</span>
  <span m='3656900'>collecting a</span> <span m='3656970'>mushroom.</span> <span m='3657936'>It's</span>
  <span m='3658362'>telling it that</span> <span m='3658790'>getting</span> <span
  m='3659020'>hurt</span> <span m='3659220'>is</span> <span m='3659340'>bad.</span>
  </p><p><span m='3659760'>Right</span> <span m='3659940'>off</span> <span m='3660090'>the</span>
  <span m='3660150'>bat,</span> <span m='3660480'>all</span> <span m='3660630'>these</span>
  <span m='3660720'>things</span> <span m='3661100'>in</span> <span m='3661260'>the</span>
  <span m='3661320'>score</span> <span m='3662130'>are</span> <span m='3662250'>giving</span>
  <span m='3662520'>the AI</span> <span m='3662760'>some</span> <span m='3663390'>domain</span>
  <span m='3663750'>knowledge</span> <span m='3664110'>about</span> <span m='3664470'>"Super</span>
  <span m='3664740'>Mario</span> <span m='3665100'>Bros,"</span> <span m='3665800'>that</span>
  <span m='3665950'>it's</span> <span m='3666375'>helping</span> <span m='3666800'>it</span>
  <span m='3667070'>calculate</span> <span m='3667385'>the</span> <span m='3667860'>simulation</span>
  <span m='3668130'>results.</span> <span m='3670985'>As</span> <span m='3671320'>it
  says</span> <span m='3671790'>here,</span> <span m='3672260'>it's</span> <span m='3672430'>just
  doing</span> <span m='3672910'>a multi-objective</span> <span m='3673460'>weighted</span>
  <span m='3673990'>sum</span> <span m='3674280'>of</span> <span m='3674460'>all</span>
  <span m='3674630'>these things.</span> <span m='3675450'>Throughout</span> <span
  m='3675690'>the</span> <span m='3675750'>simulation</span> <span m='3676030'>it's</span>
  <span m='3676310'>just</span> <span m='3676590'>adding up</span> <span m='3676960'>your</span>
  <span m='3677110'>score.</span> <span m='3677360'>And</span> <span m='3677790'>then
  that's</span> <span m='3678282'>the score</span> <span m='3678774'>that is</span>
  <span m='3679266'>going to be</span> <span m='3679758'>propagated.</span> <span
  m='3680742'>Are there</span> <span m='3681234'>questions</span> <span m='3681726'>about
  the</span> <span m='3682218'>score?</span> </p><p><span m='3684680'>AUDIENCE:</span>
  <span m='3684756'>You</span> <span m='3684832'>said</span> <span m='3684910'>that</span>
  <span m='3685170'>it</span> <span m='3685500'>adds</span> <span m='3685850'>up</span>
  <span m='3685990'>all</span> <span m='3686130'>these</span> <span m='3686280'>guys</span>
  <span m='3686520'>and</span> <span m='3687020'>it</span> <span m='3687100'>propagates</span>
  <span m='3687590'>it over.</span> <span m='3687730'>Is it</span> <span m='3687950'>possible</span>
  <span m='3688190'>to just</span> <span m='3688600'>propagate</span> <span m='3689010'>the</span>
  <span m='3689420'>multi-part</span> <span m='3690240'>sum</span> <span m='3692110'>[INAUDIBLE]</span>
  <span m='3693086'>as</span> <span m='3693460'>opposed</span> <span m='3693780'>to</span>
  <span m='3694140'>propagating</span> <span m='3694500'>one</span> <span m='3694710'>value</span>
  <span m='3695157'>that</span> <span m='3695604'>you</span> <span m='3696051'>create?</span>
  <span m='3697655'>Are</span> <span m='3698040'>you</span> <span m='3698180'>essentially</span>
  <span m='3698470'>propagating</span> <span m='3699090'>all--</span> <span m='3699600'>what's
  this?--</span> <span m='3699860'>15</span> <span m='3700600'>values</span> <span
  m='3701280'>upwards</span> <span m='3701690'>at</span> <span m='3701790'>every</span>
  <span m='3702030'>node,</span> <span m='3702510'>or are you propagating</span> <span
  m='3702940'>one</span> <span m='3703290'>value--</span> </p><p><span m='3703500'>PROFESSOR
  3:</span> <span m='3703580'>Well,</span> <span m='3703660'>it's</span> <span m='3703740'>one</span>
  <span m='3704010'>value.</span> <span m='3704220'>It's the</span> <span m='3704500'>collective--</span>
  </p><p><span m='3705000'>AUDIENCE:</span> <span m='3705080'>Then</span> <span m='3705160'>you</span>
  <span m='3705240'>make</span> <span m='3705620'>them add</span> <span m='3705860'>it
  together</span> <span m='3706315'>and you got each one</span> <span m='3706770'>of
  them a</span> <span m='3707225'>sub factor.</span> </p><p><span m='3710490'>PROFESSOR
  3:</span> <span m='3710625'>Then</span> <span m='3710760'>also,</span> <span m='3711030'>just
  one</span> <span m='3711210'>thing</span> <span m='3711380'>to</span> <span m='3711480'>note</span>
  <span m='3711740'>here,</span> <span m='3712330'>is</span> <span m='3712790'>distance,</span>
  <span m='3713270'>you</span> <span m='3713370'>get</span> <span m='3713570'>0.1.</span>
  <span m='3715230'>And</span> <span m='3715380'>these</span> <span m='3715590'>are</span>
  <span m='3715680'>all</span> <span m='3716320'>parameters</span> <span m='3716600'>that</span>
  <span m='3716880'>have been</span> <span m='3717210'>tuned.</span> <span m='3718650'>In</span>
  <span m='3718860'>the</span> <span m='3719010'>initial</span> <span m='3719340'>version,</span>
  <span m='3719880'>distance</span> <span m='3720550'>was,</span> <span m='3720840'>I
  think,</span> <span m='3721470'>a</span> <span m='3721530'>reward</span> <span m='3721890'>of</span>
  <span m='3722130'>five,</span> <span m='3723330'>but</span> <span m='3724200'>probably</span>
  <span m='3724770'>realized</span> <span m='3725035'>that</span> <span m='3725300'>that</span>
  <span m='3725470'>made</span> <span m='3725970'>Mario</span> <span m='3726390'>skip</span>
  <span m='3726700'>past</span> <span m='3727020'>a lot of</span> <span m='3727330'>coins</span>
  <span m='3727630'>and things.</span> <span m='3728500'>And</span> <span m='3728660'>so</span>
  <span m='3728970'>he</span> <span m='3729170'>tweaked</span> <span m='3729570'>the</span>
  <span m='3730380'>score</span> <span m='3730650'>for</span> <span m='3730740'>that.</span>
  </p><p><span m='3731050'>And</span> <span m='3731150'>also,</span> <span m='3731250'>time</span>
  <span m='3731310'>left</span> <span m='3732420'>is</span> <span m='3732660'>two.</span>
  <span m='3733100'>So</span> <span m='3733435'>there's some</span> <span m='3733770'>weight</span>
  <span m='3734080'>there.</span> <span m='3734460'>You</span> <span m='3734520'>want</span>
  <span m='3734670'>to</span> <span m='3734730'>get</span> <span m='3734900'>to</span>
  <span m='3734960'>the</span> <span m='3735330'>very</span> <span m='3735570'>end</span>
  <span m='3735690'>of</span> <span m='3735750'>the</span> <span m='3735840'>game.</span>
  </p><p><span m='3736700'>AUDIENCE:</span> <span m='3736780'>If</span> <span m='3736860'>you're</span>
  <span m='3736980'>pushing</span> <span m='3737280'>up</span> <span m='3737430'>this</span>
  <span m='3737850'>score,</span> <span m='3738720'>it's</span> <span m='3738840'>no</span>
  <span m='3738990'>longer</span> <span m='3739990'>a</span> <span m='3740130'>win</span>
  <span m='3740410'>over</span> <span m='3740640'>losses.</span> <span m='3740850'>So
  it's</span> <span m='3741180'>not</span> <span m='3741420'>w</span> <span m='3741620'>over</span>
  <span m='3741970'>n.</span> <span m='3742920'>What</span> <span m='3743070'>is it</span>
  <span m='3743510'>affecting?</span> </p><p><span m='3743950'>PROFESSOR 3:</span>
  <span m='3744100'>You</span> <span m='3744250'>can</span> <span m='3744510'>just</span>
  <span m='3744690'>use</span> <span m='3744960'>the</span> <span m='3745060'>score.</span>
  </p><p><span m='3746210'>AUDIENCE:</span> <span m='3746330'>The</span> <span m='3746450'>score
  is</span> <span m='3746720'>the--</span> </p><p><span m='3746930'>PROFESSOR 3:</span>
  <span m='3747065'>Yeah.</span> <span m='3747860'>In</span> <span m='3748070'>MCTS</span>
  <span m='3748680'>you</span> <span m='3748800'>have</span> <span m='3749160'>this</span>
  <span m='3749310'>idea</span> <span m='3749760'>of</span> <span m='3751500'>when</span>
  <span m='3751620'>you're</span> <span m='3751770'>propagating</span> <span m='3752490'>your</span>
  <span m='3752760'>q</span> <span m='3753120'>value,</span> <span m='3755300'>you</span>
  <span m='3755460'>could</span> <span m='3755700'>have</span> <span m='3755850'>that</span>
  <span m='3755970'>to be</span> <span m='3756200'>zero,</span> <span m='3756540'>one.</span>
  </p><p><span m='3757080'>AUDIENCE:</span> <span m='3757330'>It's</span> <span m='3757580'>like</span>
  <span m='3757820'>the</span> <span m='3758120'>sum</span> <span m='3758260'>of</span>
  <span m='3758340'>all the</span> <span m='3758670'>scores</span> <span m='3759120'>and</span>
  <span m='3759270'>the</span> <span m='3759620'>nodes</span> <span m='3759910'>below</span>
  <span m='3760170'>over the</span> <span m='3760290'>number</span> <span m='3760500'>of
  games</span> <span m='3760895'>you win.</span> </p><p><span m='3761290'>PROFESSOR
  3:</span> <span m='3761375'>So</span> <span m='3761460'>basically,</span> <span
  m='3761850'>what</span> <span m='3762050'>you</span> <span m='3762150'>would be</span>
  <span m='3762320'>getting</span> <span m='3762810'>when</span> <span m='3763120'>you
  divide</span> <span m='3763370'>by</span> <span m='3763790'>the</span> <span m='3763870'>number</span>
  <span m='3764310'>of</span> <span m='3764510'>simulations</span> <span m='3764700'>is</span>
  <span m='3765060'>your</span> <span m='3765210'>average</span> <span m='3765630'>score</span>
  <span m='3766570'>at</span> <span m='3767040'>that</span> <span m='3767510'>node.</span>
  </p><p><span m='3767980'>AUDIENCE:</span> <span m='3768215'>OK.</span> </p><p><span
  m='3770330'>AUDIENCE:</span> <span m='3770565'>When</span> <span m='3770800'>you
  have</span> <span m='3771270'>killsByFire</span> <span m='3772570'>and</span> <span
  m='3773060'>[INAUDIBLE]</span> <span m='3773550'>like that,</span> <span m='3774530'>if
  you</span> <span m='3775020'>have a</span> <span m='3775510'>positive</span> <span
  m='3776000'>value,</span> <span m='3776490'>then</span> <span m='3776980'>isn't
  it</span> <span m='3777470'>good to be killed</span> <span m='3777960'>by</span>
  <span m='3778450'>fire,</span> <span m='3778940'>or something like that?</span>
  </p><p><span m='3779520'>PROFESSOR 3:</span> <span m='3779700'>This</span> <span
  m='3779880'>is killing an</span> <span m='3780040'>enemy</span> <span m='3780260'>by</span>
  <span m='3780440'>fire.</span> <span m='3781330'>Like</span> <span m='3781540'>Mario</span>
  <span m='3781840'>could collect</span> <span m='3782140'>a</span> <span m='3782390'>certain</span>
  <span m='3782890'>flower</span> <span m='3783910'>or</span> <span m='3784080'>mushroom?</span>
  <span m='3784350'>I think</span> <span m='3784620'>flower,</span> <span m='3785410'>then</span>
  <span m='3785560'>you</span> <span m='3785680'>have</span> <span m='3785820'>a</span>
  <span m='3785950'>fire</span> <span m='3786190'>breath</span> <span m='3786543'>and</span>
  <span m='3786896'>you</span> <span m='3787250'>[INAUDIBLE].</span> </p><p><span
  m='3787560'>AUDIENCE:</span> <span m='3787620'>So</span> <span m='3787680'>that's</span>
  <span m='3788010'>Mario's</span> <span m='3788300'>status</span> <span m='3788670'>if</span>
  <span m='3788820'>Mario</span> <span m='3790083'>never</span> <span m='3790504'>dies?</span>
  </p><p><span m='3791350'>PROFESSOR 3:</span> <span m='3791440'>No.</span> <span
  m='3791530'>Mario's</span> <span m='3791880'>status</span> <span m='3792400'>is--</span>
  <span m='3793120'>I</span> <span m='3793180'>believe,</span> <span m='3793630'>Mario's</span>
  <span m='3793940'>status</span> <span m='3794350'>is</span> <span m='3794860'>the</span>
  <span m='3794920'>fact</span> <span m='3795220'>that</span> <span m='3795460'>you</span>
  <span m='3795520'>could</span> <span m='3795830'>upgrade</span> <span m='3796190'>Mario</span>
  <span m='3796430'>by</span> <span m='3796600'>collecting</span> <span m='3796970'>[INAUDIBLE]</span>
  <span m='3797340'>mushroom</span> <span m='3797710'>from a</span> <span m='3797800'>fire</span>
  <span m='3798150'>Mario.</span> <span m='3800210'>So</span> <span m='3800350'>that</span>
  <span m='3800630'>gives</span> <span m='3800820'>you</span> <span m='3800970'>a
  lot of</span> <span m='3801320'>points.</span> <span m='3801570'>Because if</span>
  <span m='3801670'>you</span> <span m='3801790'>become</span> <span m='3802030'>fire</span>
  <span m='3802310'>Mario,</span> <span m='3802600'>then</span> <span m='3804070'>you're</span>
  <span m='3804370'>more</span> <span m='3804550'>likely</span> <span m='3804880'>to</span>
  <span m='3805010'>not</span> <span m='3805270'>die</span> <span m='3805610'>by</span>
  <span m='3806070'>running into</span> <span m='3806530'>enemies</span> <span m='3806795'>because</span>
  <span m='3807060'>you</span> <span m='3807555'>have</span> <span m='3808050'>fire-spewing--</span>
  </p><p><span m='3809040'>AUDIENCE:</span> <span m='3809100'>You</span> <span m='3809160'>said
  they</span> <span m='3809380'>spent a</span> <span m='3809530'>lot</span> <span
  m='3809710'>of</span> <span m='3809790'>time</span> <span m='3810225'>tuning</span>
  <span m='3810660'>these</span> <span m='3810860'>parameters.</span> <span m='3811900'>Isn't</span>
  <span m='3812110'>it</span> <span m='3812450'>generally,</span> <span m='3812790'>though,</span>
  <span m='3813290'>just</span> <span m='3813490'>an</span> <span m='3813830'>optimization</span>
  <span m='3814170'>framework</span> <span m='3814710'>if</span> <span m='3814970'>that's</span>
  <span m='3815570'>some</span> <span m='3815980'>formula?</span> <span m='3816540'>So</span>
  <span m='3816870'>they</span> <span m='3817160'>tuned</span> <span m='3817340'>the</span>
  <span m='3817660'>parameters</span> <span m='3818030'>just to</span> <span m='3818400'>make</span>
  <span m='3818580'>behave the</span> <span m='3819018'>way</span> <span m='3819456'>that</span>
  <span m='3819894'>we think</span> <span m='3821210'>is nice.</span> <span m='3821370'>But</span>
  <span m='3821700'>if you</span> <span m='3822030'>change</span> <span m='3822280'>the</span>
  <span m='3822755'>values,</span> <span m='3823420'>they'll do the</span> <span m='3823600'>right</span>
  <span m='3823870'>thing</span> <span m='3824330'>for</span> <span m='3824670'>that</span>
  <span m='3824900'>equation.</span> </p><p><span m='3825420'>PROFESSOR 3:</span>
  <span m='3825645'>Yeah.</span> </p><p><span m='3825870'>AUDIENCE:</span> <span m='3826095'>OK.</span>
  </p><p><span m='3826320'>PROFESSOR 3:</span> <span m='3826545'>Yes.</span> <span
  m='3826770'>But</span> <span m='3827160'>they</span> <span m='3827550'>were tuning
  this</span> <span m='3827940'>to make</span> <span m='3828310'>it</span> <span m='3828440'>play</span>
  <span m='3828690'>how</span> <span m='3829020'>they</span> <span m='3829180'>wanted.</span>
  </p><p><span m='3830830'>AUDIENCE:</span> <span m='3830972'>[INAUDIBLE]</span> <span
  m='3831610'>can't</span> <span m='3832006'>just</span> <span m='3832402'>be a</span>
  <span m='3832800'>reflection</span> <span m='3833040'>of</span> <span m='3833470'>[INAUDIBLE]</span>
  </p><p><span m='3836500'>PROFESSOR 3:</span> <span m='3836685'>That's</span> <span
  m='3836870'>a</span> <span m='3836980'>strategy.</span> <span m='3837360'>If you</span>
  <span m='3837706'>choose that,</span> <span m='3838052'>I don't</span> <span m='3838400'>see
  why not.</span> <span m='3839380'>That</span> <span m='3839790'>might</span> <span
  m='3841130'>affect</span> <span m='3841380'>certain</span> <span m='3841730'>things.</span>
  <span m='3842540'>Obviously,</span> <span m='3842980'>you can</span> <span m='3843240'>change</span>
  <span m='3843690'>these to</span> <span m='3843960'>whatever you</span> <span m='3844360'>want.
  It'll</span> <span m='3844760'>slightly</span> <span m='3845150'>tweak</span> <span
  m='3845640'>which</span> <span m='3846130'>simulations</span> <span m='3846730'>as
  to</span> <span m='3846810'>working</span> <span m='3847320'>better,</span> <span
  m='3848150'>in terms</span> <span m='3848480'>of</span> <span m='3849010'>changing</span>
  <span m='3849280'>which</span> <span m='3849560'>nodes</span> <span m='3850030'>you</span>
  <span m='3850240'>end up</span> <span m='3850720'>choosing</span> <span m='3851200'>[INAUDIBLE].</span>
  </p><p><span m='3852640'>So</span> <span m='3853020'>we</span> <span m='3853170'>move</span>
  <span m='3853380'>on.</span> <span m='3855670'>So</span> <span m='3855720'>we</span>
  <span m='3855810'>know</span> <span m='3856150'>about</span> <span m='3856360'>scoring</span>
  <span m='3856800'>simulations.</span> <span m='3857820'>Now</span> <span m='3857900'>we're</span>
  <span m='3858200'>going to look at</span> <span m='3858390'>exactly</span> <span
  m='3859250'>the</span> <span m='3859320'>simulation</span> <span m='3859830'>type</span>
  <span m='3860160'>that's</span> <span m='3860370'>used</span> <span m='3860700'>to</span>
  <span m='3860820'>play</span> <span m='3861770'>this</span> <span m='3862230'>MCTS</span>
  <span m='3862830'>controller.</span> </p><p><span m='3863580'>So</span> <span m='3863730'>the</span>
  <span m='3863820'>regular</span> <span m='3864180'>version</span> <span m='3864540'>that</span>
  <span m='3864720'>Yo</span> <span m='3864900'>talked</span> <span m='3865230'>about</span>
  <span m='3865500'>is</span> <span m='3865590'>just</span> <span m='3865790'>choosing
  a</span> <span m='3866180'>random</span> <span m='3866570'>node</span> <span m='3866973'>at
  each</span> <span m='3867376'>level</span> <span m='3868290'>in</span> <span m='3868710'>your</span>
  <span m='3868900'>simulation.</span> <span m='3870300'>But</span> <span m='3870700'>there</span>
  <span m='3870720'>are</span> <span m='3870930'>some</span> <span m='3871120'>other</span>
  <span m='3871230'>strategies.</span> <span m='3871840'>And</span> <span m='3871940'>someone</span>
  <span m='3872070'>brought</span> <span m='3872270'>one up.</span> </p><p><span m='3872570'>The</span>
  <span m='3872700'>first</span> <span m='3872970'>is,</span> <span m='3873490'>look
  at</span> <span m='3873640'>best of</span> <span m='3873790'>n.</span> <span m='3874500'>So</span>
  <span m='3874690'>in</span> <span m='3874800'>this</span> <span m='3875010'>one,</span>
  <span m='3876160'>you</span> <span m='3876720'>choose</span> <span m='3877380'>three</span>
  <span m='3877590'>random</span> <span m='3877930'>nodes</span> <span m='3878340'>at</span>
  <span m='3878430'>each</span> <span m='3878610'>level,</span> <span m='3879280'>except</span>
  <span m='3879620'>that</span> <span m='3880140'>you</span> <span m='3880470'>stick</span>
  <span m='3880950'>with</span> <span m='3881400'>the</span> <span m='3881520'>best</span>
  <span m='3881850'>of</span> <span m='3881910'>those</span> <span m='3882210'>three.</span>
  <span m='3883195'>Choose</span> <span m='3883470'>three</span> <span m='3883560'>random</span>
  <span m='3883950'>nodes,</span> <span m='3884190'>stick</span> <span m='3884420'>with</span>
  <span m='3884550'>this</span> <span m='3884760'>one.</span> <span m='3885080'>Go
  to the</span> <span m='3885250'>next</span> <span m='3885470'>one.</span> </p><p><span
  m='3885870'>You</span> <span m='3886020'>would</span> <span m='3886170'>choose</span>
  <span m='3886940'>n</span> <span m='3887210'>random</span> <span m='3887650'>three,</span>
  <span m='3888090'>take</span> <span m='3888300'>the best</span> <span m='3888570'>one,</span>
  <span m='3888900'>and</span> <span m='3889010'>then</span> <span m='3889130'>go</span>
  <span m='3889260'>to</span> <span m='3889320'>the</span> <span m='3889410'>next</span>
  <span m='3889620'>level.</span> <span m='3889920'>You</span> <span m='3890280'>are</span>
  <span m='3890400'>able</span> <span m='3890580'>to</span> <span m='3890670'>do</span>
  <span m='3890820'>that</span> <span m='3891000'>in</span> <span m='3891150'>this</span>
  <span m='3891360'>game</span> <span m='3892150'>because</span> <span m='3893490'>of
  the way</span> <span m='3893730'>the</span> <span m='3894050'>scoring works,</span>
  <span m='3894390'>you</span> <span m='3894590'>don't have to get to</span> <span
  m='3894840'>the</span> <span m='3894990'>end</span> <span m='3895230'>of</span>
  <span m='3895290'>the</span> <span m='3895410'>game</span> <span m='3895650'>for
  your</span> <span m='3896025'>score.</span> <span m='3896400'>You</span> <span m='3896610'>actually</span>
  <span m='3897210'>could</span> <span m='3897400'>collect a</span> <span m='3897680'>coin</span>
  <span m='3897940'>along the</span> <span m='3898200'>way.</span> </p><p><span m='3900425'>If</span>
  <span m='3900870'>this</span> <span m='3901130'>is</span> <span m='3901470'>jump,</span>
  <span m='3901740'>and then it</span> <span m='3902010'>gets to be a</span> <span
  m='3902270'>coin</span> <span m='3902780'>versus</span> <span m='3903090'>moving</span>
  <span m='3903360'>left and right.</span> <span m='3903610'>That doesn't give</span>
  <span m='3903940'>you any</span> <span m='3904410'>points.</span> <span m='3904720'>Then</span>
  <span m='3905430'>this</span> <span m='3905620'>is</span> <span m='3905730'>the
  node</span> <span m='3905990'>that would</span> <span m='3906220'>give</span> <span
  m='3906360'>you</span> <span m='3906510'>the</span> <span m='3906600'>highest</span>
  <span m='3906880'>scores,</span> <span m='3907310'>so I would</span> <span m='3907732'>choose
  that</span> <span m='3908154'>one,</span> <span m='3908576'>et cetera.</span> </p><p><span
  m='3909420'>And</span> <span m='3909570'>then</span> <span m='3909770'>the</span>
  <span m='3909950'>final</span> <span m='3910160'>one,</span> <span m='3910640'>which</span>
  <span m='3910840'>is the</span> <span m='3911150'>one that is</span> <span m='3911300'>actually</span>
  <span m='3911590'>used</span> <span m='3911870'>for</span> <span m='3912040'>this</span>
  <span m='3912150'>controller,</span> <span m='3912670'>is</span> <span m='3912780'>multi-simulation.</span>
  <span m='3914700'>This</span> <span m='3915060'>was</span> <span m='3915290'>brought</span>
  <span m='3915600'>up</span> <span m='3916081'>by</span> <span m='3916562'>him.</span>
  <span m='3917043'>I don't know your</span> <span m='3917524'>name.</span> <span
  m='3918005'>Sorry.</span> <span m='3918490'>But</span> <span m='3918800'>basically,</span>
  <span m='3919220'>you</span> <span m='3919320'>run</span> <span m='3920070'>multiple</span>
  <span m='3920440'>random</span> <span m='3920760'>simulations</span> <span m='3921450'>from</span>
  <span m='3921660'>your node.</span> <span m='3922035'>And</span> <span m='3922410'>then</span>
  <span m='3922680'>you</span> <span m='3922860'>propagate</span> <span m='3923370'>up</span>
  <span m='3923730'>whichever</span> <span m='3924090'>of</span> <span m='3924150'>those</span>
  <span m='3924330'>simulations</span> <span m='3924990'>give</span> <span m='3925130'>you</span>
  <span m='3925230'>the</span> <span m='3925350'>highest</span> <span m='3925650'>value.</span>
  </p><p><span m='3926580'>And</span> <span m='3926910'>the</span> <span m='3927030'>reason</span>
  <span m='3927380'>to</span> <span m='3927530'>do</span> <span m='3927680'>multiple</span>
  <span m='3928140'>simulations</span> <span m='3928600'>is</span> <span m='3928950'>to</span>
  <span m='3929650'>attempt</span> <span m='3929920'>to</span> <span m='3930060'>increase</span>
  <span m='3930420'>the</span> <span m='3930540'>accuracy</span> <span m='3931200'>of</span>
  <span m='3931380'>your</span> <span m='3931470'>simulations.</span> <span m='3933892'>If
  you</span> <span m='3934280'>just do</span> <span m='3934550'>one</span> <span m='3934770'>simulation</span>
  <span m='3935010'>you might just</span> <span m='3935405'>get really</span> <span
  m='3935800'>lucky.</span> <span m='3936195'>But if</span> <span m='3936590'>you</span>
  <span m='3936720'>do</span> <span m='3936870'>three</span> <span m='3937620'>then</span>
  <span m='3938580'>you</span> <span m='3938790'>can</span> <span m='3939340'>take</span>
  <span m='3939530'>the</span> <span m='3939670'>highest</span> <span m='3940050'>value</span>
  <span m='3940490'>use</span> <span m='3940770'>that</span> <span m='3941040'>as
  your</span> <span m='3941510'>value.</span> <span m='3942450'>Since</span> <span
  m='3942780'>the</span> <span m='3942840'>whole</span> <span m='3943020'>point</span>
  <span m='3943230'>of</span> <span m='3943290'>this</span> <span m='3944070'>is</span>
  <span m='3944160'>to</span> <span m='3944220'>try</span> <span m='3944430'>make
  moves</span> <span m='3944927'>that get you</span> <span m='3945424'>the highest</span>
  <span m='3945921'>values,</span> <span m='3946660'>then</span> <span m='3946995'>that
  will</span> <span m='3947330'>make</span> <span m='3947510'>your</span> <span m='3947950'>random</span>
  <span m='3948390'>simulation</span> <span m='3948852'>value</span> <span m='3949314'>more</span>
  <span m='3949776'>accurate.</span> <span m='3950700'>Are there</span> <span m='3951162'>questions
  about</span> <span m='3951630'>multi-simulation?</span> </p><p><span m='3953050'>AUDIENCE:</span>
  <span m='3953155'>So</span> <span m='3953260'>what</span> <span m='3953693'>do you
  think about</span> <span m='3954126'>the</span> <span m='3954560'>simulation</span>
  <span m='3955040'>[INAUDIBLE]</span> <span m='3956014'>how</span> <span m='3956501'>many</span>
  <span m='3956988'>[INAUDIBLE]</span> </p><p><span m='3958940'>PROFESSOR 3:</span>
  <span m='3959060'>So</span> <span m='3959180'>there's</span> <span m='3959320'>a</span>
  <span m='3959350'>trade</span> <span m='3959450'>off</span> <span m='3959770'>here.</span>
  <span m='3960990'>The</span> <span m='3961250'>more</span> <span m='3961420'>simulations</span>
  <span m='3961650'>you</span> <span m='3961750'>do</span> <span m='3962530'>the</span>
  <span m='3962650'>more</span> <span m='3964090'>accurate--</span> <span m='3965230'>the</span>
  <span m='3965390'>more</span> <span m='3965480'>representative</span> <span m='3965780'>your</span>
  <span m='3966080'>simulation</span> <span m='3966280'>will be</span> <span m='3966540'>at
  the</span> <span m='3967010'>end of the game.</span> <span m='3970720'>You</span>
  <span m='3970810'>could</span> <span m='3970930'>run</span> <span m='3972070'>two</span>
  <span m='3972520'>to the whatever</span> <span m='3973020'>simulations</span> <span
  m='3973600'>to</span> <span m='3973720'>try</span> <span m='3973930'>to</span> <span
  m='3973990'>get</span> <span m='3974190'>every single</span> <span m='3974600'>possible</span>
  <span m='3975530'>action</span> <span m='3976390'>and</span> <span m='3976480'>then</span>
  <span m='3976910'>take the</span> <span m='3977090'>max of</span> <span m='3977420'>that.</span>
  <span m='3977700'>And that</span> <span m='3977950'>would</span> <span m='3978050'>give</span>
  <span m='3978220'>you</span> <span m='3978380'>the</span> <span m='3978600'>maximum</span>
  <span m='3978820'>value.</span> <span m='3979390'>That</span> <span m='3980080'>would</span>
  <span m='3980230'>be</span> <span m='3980320'>ideal.</span> </p><p><span m='3980960'>But</span>
  <span m='3981040'>obviously,</span> <span m='3981400'>that</span> <span m='3981520'>takes</span>
  <span m='3981730'>more</span> <span m='3981850'>time.</span> <span m='3982290'>So</span>
  <span m='3982300'>there's</span> <span m='3982420'>a</span> <span m='3982450'>trade</span>
  <span m='3982550'>off</span> <span m='3982870'>between</span> <span m='3983440'>computation</span>
  <span m='3983695'>time</span> <span m='3984220'>and</span> <span m='3984310'>the</span>
  <span m='3984370'>number</span> <span m='3984680'>of</span> <span m='3984760'>simulations</span>
  <span m='3985120'>you</span> <span m='3985555'>run.</span> <span m='3985990'>And</span>
  <span m='3986110'>that's</span> <span m='3986280'>just</span> <span m='3986390'>something</span>
  <span m='3986770'>that</span> <span m='3987150'>they</span> <span m='3987280'>probably</span>
  <span m='3987700'>just played</span> <span m='3987940'>around</span> <span m='3988270'>with.</span>
  </p><p><span m='3988490'>AUDIENCE:</span> <span m='3988656'>Do</span> <span m='3988822'>you</span>
  <span m='3988989'>use</span> <span m='3989488'>[INAUDIBLE]</span> <span m='3996973'>have</span>
  <span m='3997472'>to</span> <span m='3997971'>finish</span> <span m='3998470'>the
  decision</span> <span m='3998969'>losing</span> <span m='3999468'>a couple of</span>
  <span m='3999967'>minutes</span> <span m='4000466'>or</span> <span m='4000965'>10</span>
  <span m='4001464'>minutes</span> <span m='4001963'>or they're going to</span> <span
  m='4002480'>take your</span> <span m='4002800'>[INAUDIBLE]</span> <span m='4003200'>away.</span>
  </p><p><span m='4003380'>PROFESSOR 3:</span> <span m='4003495'>In</span> <span m='4003610'>this</span>
  <span m='4003960'>competition</span> <span m='4004540'>there</span> <span m='4004690'>is</span>
  <span m='4004900'>different</span> <span m='4005770'>computation</span> <span m='4006340'>time</span>
  <span m='4006610'>budgets</span> <span m='4007000'>that</span> <span m='4007170'>you</span>
  <span m='4007606'>get.</span> <span m='4008480'>And</span> <span m='4008590'>I</span>
  <span m='4008950'>believe</span> <span m='4009310'>the</span> <span m='4009430'>reason</span>
  <span m='4009820'>for the</span> <span m='4010260'>different computation</span>
  <span m='4010700'>time</span> <span m='4011140'>budgets</span> <span m='4011330'>is</span>
  <span m='4011650'>the</span> <span m='4011970'>frame</span> <span m='4012170'>per</span>
  <span m='4012380'>second of the</span> <span m='4012610'>game.</span> </p><p><span
  m='4018390'>I</span> <span m='4018530'>told</span> <span m='4018790'>you</span>
  <span m='4018930'>all</span> <span m='4019320'>about</span> <span m='4019850'>the
  setup,</span> <span m='4020210'>we</span> <span m='4020380'>went</span> <span m='4020530'>over,</span>
  <span m='4021110'>the</span> <span m='4021210'>scoring,</span> <span m='4022065'>the</span>
  <span m='4022320'>nodes,</span> <span m='4022730'>what</span> <span m='4022890'>the</span>
  <span m='4023130'>advantages</span> <span m='4023280'>are,</span> <span m='4023800'>what</span>
  <span m='4024010'>the</span> <span m='4024426'>simulation</span> <span m='4024842'>strategy</span>
  <span m='4025260'>is</span> <span m='4025500'>used.</span> <span m='4025935'>So
  you</span> <span m='4026370'>probably</span> <span m='4026610'>want</span> <span
  m='4026790'>to</span> <span m='4026850'>see</span> <span m='4027030'>it in</span>
  <span m='4027270'>action.</span> <span m='4028490'>So</span> <span m='4028550'>this
  is always</span> <span m='4028680'>a</span> <span m='4028740'>risky</span> <span
  m='4029070'>move</span> <span m='4029920'>trying</span> <span m='4030410'>to</span>
  <span m='4030610'>get video to</span> <span m='4030850'>play.</span> </p><p><span
  m='4031150'>AUDIENCE:</span> <span m='4031380'>It's</span> <span m='4031610'>actually</span>
  <span m='4032070'>in the</span> <span m='4032530'>back up.</span> <span m='4032830'>Hit</span>
  <span m='4033220'>Escape.</span> </p><p><span m='4034000'>PROFESSOR 3:</span> <span
  m='4034185'>OK.</span> <span m='4034800'>Got</span> <span m='4035070'>it.</span>
  </p><p><span m='4035660'>AUDIENCE:</span> <span m='4035910'>And</span> <span m='4036160'>now,</span>
  <span m='4036660'>I</span> <span m='4036710'>guess,</span> <span m='4036820'>we--</span>
  </p><p><span m='4037075'>PROFESSOR 3:</span> <span m='4037202'>And</span> <span
  m='4037330'>drag</span> <span m='4037430'>it</span> <span m='4037920'>over</span>
  <span m='4038410'>again?</span> </p><p><span m='4038900'>AUDIENCE:</span> <span
  m='4039145'>Yeah.</span> </p><p><span m='4044780'>PROFESSOR 3:</span> <span m='4045025'>Running
  this</span> <span m='4045270'>full</span> <span m='4045760'>screen.</span> </p><p><span
  m='4046250'>AUDIENCE:</span> <span m='4046495'>Hit</span> <span m='4046740'>the</span>
  <span m='4047230'>[INAUDIBLE]</span> </p><p><span m='4048760'>PROFESSOR 3:</span>
  <span m='4048999'>[INAUDIBLE]</span> <span m='4051150'>All</span> <span m='4051230'>right.</span>
  <span m='4053330'>Here's this</span> <span m='4053540'>MCTS-based</span> <span m='4054650'>"Mario"</span>
  <span m='4054920'>playing</span> <span m='4055250'>controller.</span> <span m='4055980'>You</span>
  <span m='4056160'>can</span> <span m='4056370'>see he's</span> <span m='4056510'>actually</span>
  <span m='4056870'>wrecking,</span> <span m='4057170'>so</span> <span m='4057470'>doing</span>
  <span m='4057680'>some</span> <span m='4057890'>serious</span> <span m='4058340'>damage</span>
  <span m='4058670'>here.</span> </p><p><span m='4059240'>But</span> <span m='4060740'>those</span>
  <span m='4061070'>lines</span> <span m='4061400'>that</span> <span m='4061510'>you</span>
  <span m='4061570'>see,</span> <span m='4062210'>the</span> <span m='4062250'>reason</span>
  <span m='4062470'>they're</span> <span m='4062840'>different</span> <span m='4063110'>colors</span>
  <span m='4065150'>it's</span> <span m='4065270'>not</span> <span m='4065570'>showing</span>
  <span m='4065900'>different</span> <span m='4066470'>players,</span> <span m='4066745'>or</span>
  <span m='4067020'>anything</span> <span m='4067280'>like that. It's</span> <span
  m='4067660'>just</span> <span m='4067880'>using</span> <span m='4068220'>different</span>
  <span m='4068690'>colors</span> <span m='4068900'>so you</span> <span m='4068960'>can</span>
  <span m='4069110'>see</span> <span m='4069380'>the</span> <span m='4069440'>different</span>
  <span m='4069770'>layers</span> <span m='4070190'>of</span> <span m='4070400'>this</span>
  <span m='4070610'>tree</span> <span m='4070865'>search.</span> </p><p><span m='4072290'>You</span>
  <span m='4072480'>can see he actually went</span> <span m='4072910'>backwards</span>
  <span m='4073520'>there.</span> <span m='4073940'>And that's</span> <span m='4074330'>because</span>
  <span m='4074780'>in</span> <span m='4074900'>a</span> <span m='4075100'>simulation,</span>
  <span m='4075520'>when</span> <span m='4075880'>one</span> <span m='4076510'>of</span>
  <span m='4076610'>the</span> <span m='4076730'>backward</span> <span m='4077190'>ones</span>
  <span m='4077710'>landed</span> <span m='4078090'>on an</span> <span m='4078470'>enemy--</span>
  <span m='4078670'>and</span> <span m='4078950'>in</span> <span m='4079250'>fact</span>
  <span m='4079370'>gets you</span> <span m='4079550'>points</span> <span m='4080000'>from</span>
  <span m='4080150'>our</span> <span m='4080240'>scoring</span> <span m='4080600'>system</span>
  <span m='4081380'>versus</span> <span m='4081710'>if</span> <span m='4081800'>you</span>
  <span m='4081930'>had just</span> <span m='4082090'>gone</span> <span m='4082340'>forward</span>
  <span m='4082540'>you would have</span> <span m='4082790'>gotten</span> <span m='4083060'>some</span>
  <span m='4083330'>distance</span> <span m='4083700'>points</span> <span m='4084070'>but</span>
  <span m='4084478'>not--</span> <span m='4086110'>also,</span> <span m='4086480'>he</span>
  <span m='4086840'>is</span> <span m='4087200'>just</span> <span m='4087480'>[INAUDIBLE]</span>
  </p><p><span m='4088740'>The</span> <span m='4089090'>simulation</span> <span m='4089400'>is</span>
  <span m='4090090'>quickly</span> <span m='4090420'>being able</span> <span m='4090750'>to</span>
  <span m='4092060'>figure</span> <span m='4092300'>out</span> <span m='4092450'>that
  he</span> <span m='4092870'>can jump</span> <span m='4093290'>on all</span> <span
  m='4093500'>his</span> <span m='4093570'>enemies.</span> <span m='4093920'>So he's
  just</span> <span m='4094140'>wrecking</span> <span m='4094580'>all</span> <span
  m='4094820'>these</span> <span m='4094970'>guys.</span> <span m='4096340'>Getting</span>
  <span m='4096600'>lots of</span> <span m='4096950'>points</span> <span m='4097250'>here,</span>
  <span m='4097510'>collecting</span> <span m='4097939'>the</span> <span m='4098229'>coin,</span>
  <span m='4098602'>et cetera.</span> <span m='4099350'>You get</span> <span m='4099670'>the
  idea.</span> <span m='4100760'>It's</span> <span m='4100939'>pretty</span> <span
  m='4101290'>awesome</span> <span m='4101670'>to watch.</span> </p><p><span m='4102649'>There's
  that</span> <span m='4103000'>flower</span> <span m='4103399'>we were talking</span>
  <span m='4103680'>about.</span> <span m='4103979'>So</span> <span m='4104380'>now</span>
  <span m='4104600'>he's</span> <span m='4105000'>actually</span> <span m='4105279'>a</span>
  <span m='4105520'>fire-spewing</span> <span m='4105819'>Mario</span> <span m='4106264'>demon.</span>
  <span m='4108532'>He's</span> <span m='4108930'>doing</span> <span m='4109140'>some</span>
  <span m='4109270'>serious</span> <span m='4109609'>damage with</span> <span m='4110000'>that.</span>
  <span m='4110990'>Stepping</span> <span m='4111330'>on</span> <span m='4111660'>missiles.</span>
  <span m='4111979'>I didn't</span> <span m='4112130'>even know</span> <span m='4112429'>you
  could</span> <span m='4112729'>step on</span> <span m='4113120'>the missiles.</span>
  </p><p><span m='4114689'>All</span> <span m='4114750'>right.</span> <span m='4116930'>You</span>
  <span m='4117020'>could</span> <span m='4117260'>watch</span> <span m='4117529'>this</span>
  <span m='4117740'>for</span> <span m='4117920'>a</span> <span m='4117979'>while.</span>
  <span m='4118370'>But</span> <span m='4119650'>we'll</span> <span m='4120100'>exit</span>
  <span m='4120550'>now.</span> <span m='4121599'>It</span> <span m='4121970'>looks</span>
  <span m='4122540'>super</span> <span m='4123210'>promising</span> <span m='4123700'>in
  this</span> <span m='4124065'>video.</span> <span m='4124430'>I</span> <span m='4124520'>don't</span>
  <span m='4124670'>know</span> <span m='4124880'>how</span> <span m='4125120'>close</span>
  <span m='4125630'>max</span> <span m='4125990'>stuff.</span> </p><p><span m='4126450'>AUDIENCE:</span>
  <span m='4126680'>Just</span> <span m='4126910'>click</span> <span m='4127370'>on</span>
  <span m='4127830'>back</span> <span m='4128290'>[INAUDIBLE]</span> </p><p><span
  m='4128590'>PROFESSOR 3:</span> <span m='4128662'>There</span> <span m='4128734'>it</span>
  <span m='4128806'>is.</span> <span m='4130300'>OK.</span> <span m='4131819'>The</span>
  <span m='4131990'>demo</span> <span m='4132410'>looks</span> <span m='4132680'>really</span>
  <span m='4132920'>cool,</span> <span m='4133160'>looks</span> <span m='4133330'>really</span>
  <span m='4133550'>promising.</span> <span m='4134300'>Let's</span> <span m='4134479'>take</span>
  <span m='4134660'>a</span> <span m='4134689'>look</span> <span m='4134899'>at the</span>
  <span m='4135090'>charts</span> <span m='4135590'>here</span> <span m='4136320'>because</span>
  <span m='4137060'>we</span> <span m='4137180'>all</span> <span m='4137330'>want</span>
  <span m='4137720'>some</span> <span m='4138059'>quantitative</span> <span m='4138399'>stuff.</span>
  </p><p><span m='4140240'>This</span> <span m='4140420'>is</span> <span m='4140620'>the</span>
  <span m='4140689'>chart.</span> <span m='4141510'>The score</span> <span m='4141689'>is
  on the</span> <span m='4141970'>y-axis.</span> <span m='4142410'>The</span> <span
  m='4142850'>bottom</span> <span m='4143340'>is</span> <span m='4143619'>computation</span>
  <span m='4143899'>budget,</span> <span m='4144260'>which</span> <span m='4144439'>is</span>
  <span m='4144620'>something</span> <span m='4145060'>that</span> <span m='4145220'>you</span>
  <span m='4145340'>were</span> <span m='4145430'>talking</span> <span m='4145760'>about.</span>
  <span m='4146439'>I</span> <span m='4146819'>just</span> <span m='4147210'>want</span>
  <span m='4147680'>to</span> <span m='4147830'>highlight</span> <span m='4148630'>to</span>
  <span m='4148710'>make</span> <span m='4148939'>this</span> <span m='4149390'>a</span>
  <span m='4149420'>little</span> <span m='4149689'>more</span> <span m='4151760'>visually</span>
  <span m='4152210'>appealing</span> <span m='4152779'>here.</span> </p><p><span m='4153319'>All</span>
  <span m='4153560'>of</span> <span m='4153620'>these</span> <span m='4153880'>things
  that I</span> <span m='4154189'>highlighted,</span> <span m='4156870'>it's</span>
  <span m='4157029'>labelled</span> <span m='4157240'>as</span> <span m='4157380'>UCT.</span>
  <span m='4157939'>That's</span> <span m='4158529'>Upper</span> <span m='4158789'>Confidence</span>
  <span m='4159050'>Bound</span> <span m='4159490'>Tree.</span> <span m='4160410'>Remember,</span>
  <span m='4160600'>Yo</span> <span m='4160750'>talked</span> <span m='4161000'>about</span>
  <span m='4161260'>upper</span> <span m='4161550'>confidence</span> <span m='4161840'>bounds.</span>
  <span m='4162470'>That's</span> <span m='4163250'>essentially</span> <span m='4163640'>what's</span>
  <span m='4163870'>used</span> <span m='4164020'>in that</span> <span m='4164505'>TTS</span>
  <span m='4164990'>for guiding</span> <span m='4165350'>your</span> <span m='4165529'>tree</span>
  <span m='4165799'>search.</span> </p><p><span m='4166670'>So</span> <span m='4166790'>these
  are all</span> <span m='4166939'>the</span> <span m='4167319'>methods.</span> <span
  m='4167470'>But</span> <span m='4167755'>then</span> <span m='4168040'>UCT</span>
  <span m='4168300'>multi,</span> <span m='4169229'>which</span> <span m='4169410'>is
  this</span> <span m='4169609'>purple</span> <span m='4169939'>square,</span> <span
  m='4171040'>that's</span> <span m='4171200'>saying</span> <span m='4171410'>it's</span>
  <span m='4171750'>using</span> <span m='4172096'>MCTS</span> <span m='4173090'>but</span>
  <span m='4173240'>it's</span> <span m='4173359'>doing</span> <span m='4173540'>the</span>
  <span m='4173630'>multiple</span> <span m='4173990'>simulations.</span> <span m='4174930'>And</span>
  <span m='4174990'>you</span> <span m='4175069'>can</span> <span m='4175200'>see</span>
  <span m='4176700'>this</span> <span m='4177020'>multi</span> <span m='4177529'>plus</span>
  <span m='4177890'>care</span> <span m='4179569'>is</span> <span m='4179689'>also</span>
  <span m='4180040'>in the</span> <span m='4180260'>top.</span> <span m='4181090'>Both</span>
  <span m='4181470'>these use the</span> <span m='4181670'>multi-simulation</span>
  <span m='4182899'>technique.</span> <span m='4183510'>And</span> <span m='4183609'>then</span>
  <span m='4183710'>the</span> <span m='4183810'>plus</span> <span m='4184040'>car</span>
  <span m='4184760'>is</span> <span m='4185310'>they</span> <span m='4185510'>added</span>
  <span m='4186149'>an</span> <span m='4186290'>extra</span> <span m='4186649'>scoring</span>
  <span m='4187279'>mechanism</span> <span m='4188330'>for</span> <span m='4188540'>carries.</span>
  <span m='4189800'>I</span> <span m='4189870'>believe</span> <span m='4190340'>that's</span>
  <span m='4190640'>probably</span> <span m='4190970'>like</span> <span m='4191330'>carrying</span>
  <span m='4191660'>a</span> <span m='4191720'>shell.</span> <span m='4192670'>That</span>
  <span m='4193109'>made</span> <span m='4193550'>it do</span> <span m='4193819'>better.</span>
  </p><p><span m='4194900'>Then</span> <span m='4195050'>these</span> <span m='4195260'>ones</span>
  <span m='4195470'>that</span> <span m='4195620'>aren't</span> <span m='4195830'>highlighted</span>
  <span m='4196340'>are</span> <span m='4196490'>using</span> <span m='4196820'>plain</span>
  <span m='4197480'>Astar,</span> <span m='4198200'>and then</span> <span m='4198470'>a</span>
  <span m='4198560'>refined</span> <span m='4199010'>version</span> <span m='4199350'>of</span>
  <span m='4199410'>Astar.</span> <span m='4201130'>With</span> <span m='4201490'>increasing</span>
  <span m='4201890'>time,</span> <span m='4202200'>the</span> <span m='4202360'>do</span>
  <span m='4202820'>increase</span> <span m='4203230'>scores,</span> <span m='4203630'>but</span>
  <span m='4204710'>they're</span> <span m='4204920'>even</span> <span m='4205160'>worse</span>
  <span m='4205490'>than</span> <span m='4205670'>just</span> <span m='4205960'>your</span>
  <span m='4207270'>UCT</span> <span m='4207950'>with</span> <span m='4208640'>just</span>
  <span m='4209390'>random</span> <span m='4209840'>simulation,</span> <span m='4210530'>no</span>
  <span m='4210720'>multi-simulations.</span> </p><p><span m='4214320'>We're</span>
  <span m='4214530'>running low on time,</span> <span m='4214800'>which is not</span>
  <span m='4215070'>ideal.</span> <span m='4215340'>But</span> <span m='4216620'>another</span>
  <span m='4216900'>thing</span> <span m='4217070'>that</span> <span m='4217490'>I</span>
  <span m='4217550'>want</span> <span m='4217670'>to</span> <span m='4217820'>point</span>
  <span m='4218090'>out</span> <span m='4218330'>is</span> <span m='4218930'>down</span>
  <span m='4219200'>at the</span> <span m='4219590'>bottom</span> <span m='4219810'>here,</span>
  <span m='4220100'>these</span> <span m='4220340'>are</span> <span m='4220600'>the</span>
  <span m='4220860'>multi-simulations.</span> <span m='4223830'>They</span> <span
  m='4224000'>have</span> <span m='4224240'>the</span> <span m='4224900'>lowest</span>
  <span m='4225580'>maximal</span> <span m='4225990'>search</span> <span m='4226370'>depth,</span>
  <span m='4227270'>which</span> <span m='4227540'>at</span> <span m='4227690'>first</span>
  <span m='4227990'>would</span> <span m='4228140'>seem</span> <span m='4228440'>like,</span>
  <span m='4228730'>what?</span> <span m='4230846'>I have</span> <span m='4231260'>the</span>
  <span m='4231470'>lowest</span> <span m='4231860'>search</span> <span m='4232270'>depth
  but my</span> <span m='4232680'>score</span> <span m='4232935'>is the most?</span>
  </p><p><span m='4233840'>But</span> <span m='4233990'>that</span> <span m='4234230'>comes</span>
  <span m='4234470'>into</span> <span m='4234650'>play</span> <span m='4235550'>when</span>
  <span m='4235670'>you</span> <span m='4235730'>were</span> <span m='4235820'>saying</span>
  <span m='4236090'>about</span> <span m='4236270'>the</span> <span m='4236360'>trade</span>
  <span m='4236460'>off</span> <span m='4236750'>between</span> <span m='4236990'>the</span>
  <span m='4237110'>simulations</span> <span m='4238220'>and</span> <span m='4238700'>the</span>
  <span m='4239650'>amount</span> <span m='4240150'>time</span> <span m='4240440'>it</span>
  <span m='4240500'>takes.</span> <span m='4241220'>So</span> <span m='4241520'>because</span>
  <span m='4241910'>I'm</span> <span m='4242000'>doing</span> <span m='4242300'>multiple</span>
  <span m='4242540'>simulations,</span> <span m='4243530'>I'm</span> <span m='4243620'>taking</span>
  <span m='4243920'>more</span> <span m='4244100'>time</span> <span m='4244520'>at</span>
  <span m='4244790'>each</span> <span m='4245020'>node.</span> <span m='4246110'>But</span>
  <span m='4246300'>that's</span> <span m='4246520'>giving</span> <span m='4246710'>me</span>
  <span m='4246850'>a</span> <span m='4246910'>more</span> <span m='4247160'>accurate</span>
  <span m='4248130'>value</span> <span m='4248630'>assessment.</span> <span m='4249770'>So</span>
  <span m='4249920'>that</span> <span m='4250340'>let's</span> <span m='4250680'>me</span>
  <span m='4250820'>choose my</span> <span m='4250970'>actions</span> <span m='4251350'>more</span>
  <span m='4251510'>carefully,</span> <span m='4252300'>or</span> <span m='4252530'>with</span>
  <span m='4252740'>more</span> <span m='4252920'>information.</span> <span m='4254010'>And</span>
  <span m='4254120'>so</span> <span m='4254240'>that's</span> <span m='4254480'>what's</span>
  <span m='4254720'>able</span> <span m='4254960'>to give</span> <span m='4255240'>me
  this</span> <span m='4255520'>better</span> <span m='4255910'>scores.</span> </p><p><span
  m='4259590'>That's</span> <span m='4259800'>all</span> <span m='4260110'>"Mario."</span>
  <span m='4260400'>So we're</span> <span m='4260690'>going to</span> <span m='4261000'>moving</span>
  <span m='4261300'>onto</span> <span m='4261500'>AlphaGo.</span> <span m='4262010'>Are
  there</span> <span m='4262110'>any</span> <span m='4262230'>questions</span> <span
  m='4262590'>about</span> <span m='4263040'>"Mario"</span> <span m='4263490'>before</span>
  <span m='4263610'>I go to</span> <span m='4263730'>AlphaGo?</span> <span m='4264870'>Yeah.</span>
  </p><p><span m='4265090'>AUDIENCE:</span> <span m='4265340'>What's</span> <span
  m='4265590'>the</span> <span m='4266090'>table</span> <span m='4266590'>[INAUDIBLE]</span>
  <span m='4267090'>inference?</span> </p><p><span m='4268090'>PROFESSOR 3:</span>
  <span m='4268147'>That's</span> <span m='4268204'>a</span> <span m='4268261'>good</span>
  <span m='4268320'>question.</span> <span m='4268800'>I have</span> <span m='4269280'>a</span>
  <span m='4269350'>feeling</span> <span m='4269810'>it's</span> <span m='4270550'>because</span>
  <span m='4271080'>if</span> <span m='4271290'>you're</span> <span m='4271380'>doing</span>
  <span m='4271650'>best of</span> <span m='4271980'>n,</span> <span m='4272420'>that's</span>
  <span m='4272780'>really</span> <span m='4273070'>heavily</span> <span m='4273390'>relying</span>
  <span m='4273840'>on</span> <span m='4274680'>your</span> <span m='4275520'>scoring</span>
  <span m='4276210'>metrics.</span> <span m='4279360'>Let's</span> <span m='4279520'>say</span>
  <span m='4279890'>at one</span> <span m='4280090'>step</span> <span m='4281120'>if
  I</span> <span m='4281230'>jump</span> <span m='4281540'>and</span> <span m='4281980'>collect
  a</span> <span m='4282200'>coin</span> <span m='4282635'>versus if I</span> <span
  m='4283070'>go left or right</span> <span m='4283280'>and play,</span> <span m='4283660'>I'll</span>
  <span m='4283830'>get more</span> <span m='4284220'>points</span> <span m='4284280'>if
  I</span> <span m='4284370'>get that</span> <span m='4284550'>coin.</span> <span
  m='4285200'>But</span> <span m='4285550'>maybe,</span> <span m='4286270'>a</span>
  <span m='4286430'>missile</span> <span m='4286570'>is going</span> <span m='4286680'>to
  hit</span> <span m='4286975'>me in the</span> <span m='4287270'>face</span> <span
  m='4287690'>if I</span> <span m='4287900'>do that.</span> <span m='4288690'>It</span>
  <span m='4289020'>gets</span> <span m='4289230'>rid</span> <span m='4289410'>of</span>
  <span m='4289470'>some</span> <span m='4289680'>of</span> <span m='4289880'>the--</span>
  <span m='4290090'>it's</span> <span m='4290940'>forcing</span> <span m='4291450'>you</span>
  <span m='4291600'>to</span> <span m='4291690'>do</span> <span m='4291910'>certain</span>
  <span m='4292000'>moves.</span> </p><p><span m='4292670'>AUDIENCE:</span> <span
  m='4292746'>Is</span> <span m='4292822'>the</span> <span m='4292900'>A*</span> <span
  m='4293460'>heuristically</span> <span m='4293931'>using</span> <span m='4294402'>the
  same</span> <span m='4294873'>value,</span> <span m='4296290'>the</span> <span m='4296380'>same</span>
  <span m='4296826'>value that you're</span> <span m='4297272'>getting</span> <span
  m='4297718'>by</span> <span m='4298164'>your simulation?</span> </p><p><span m='4299060'>PROFESSOR
  3:</span> <span m='4299200'>Yeah.</span> <span m='4299610'>I'm</span> <span m='4299700'>not</span>
  <span m='4299880'>exactly</span> <span m='4300270'>sure</span> <span m='4300630'>what</span>
  <span m='4300990'>the</span> <span m='4301410'>Astar</span> <span m='4301680'>heuristic</span>
  <span m='4302400'>is.</span> <span m='4302820'>The</span> <span m='4302910'>whole</span>
  <span m='4303120'>reason</span> <span m='4303960'>that</span> <span m='4304996'>A*</span>
  <span m='4305380'>is</span> <span m='4307020'>difficult</span> <span m='4307480'>is</span>
  <span m='4307770'>because</span> <span m='4308040'>coming</span> <span m='4308420'>up
  with</span> <span m='4308730'>heuristics</span> <span m='4308880'>for</span> <span
  m='4309250'>these types</span> <span m='4309480'>of</span> <span m='4309590'>games</span>
  <span m='4309940'>are.</span> <span m='4311900'>But</span> <span m='4313200'>this</span>
  <span m='4313410'>is</span> <span m='4313530'>not</span> <span m='4313890'>his</span>
  <span m='4314070'>version of</span> <span m='4314500'>Astar.</span> <span m='4314670'>I
  believe</span> <span m='4314990'>this</span> <span m='4315150'>is</span> <span m='4315240'>the</span>
  <span m='4315500'>Astar</span> <span m='4315810'>that</span> <span m='4316440'>was</span>
  <span m='4316590'>used</span> <span m='4316860'>by--</span> <span m='4317190'>I
  forget</span> <span m='4317520'>the name of the</span> <span m='4317840'>guy--</span>
  <span m='4318080'>but</span> <span m='4318470'>he</span> <span m='4318670'>won</span>
  <span m='4318960'>the</span> <span m='4319230'>AI</span> <span m='4319710'>competition</span>
  <span m='4320890'>a</span> <span m='4320960'>couple</span> <span m='4321150'>of</span>
  <span m='4321230'>years</span> <span m='4321440'>ago.</span> </p><p><span m='4324060'>I'm</span>
  <span m='4324544'>going to try</span> <span m='4325028'>to move onto</span> <span
  m='4325512'>AlphaGo.</span> <span m='4326390'>Does</span> <span m='4326570'>someone</span>
  <span m='4326790'>have</span> <span m='4327030'>how many</span> <span m='4327400'>minutes</span>
  <span m='4327650'>I have left?</span> </p><p><span m='4330000'>AUDIENCE:</span>
  <span m='4330200'>Four.</span> </p><p><span m='4330610'>PROFESSOR 3:</span> <span
  m='4330770'>OK.</span> <span m='4330930'>We're</span> <span m='4331280'>going to</span>
  <span m='4331630'>power through.</span> <span m='4333005'>Here's</span> <span m='4333260'>AlphaGo.</span>
  <span m='4334330'>Hopefully,</span> <span m='4334780'>you all know the</span> <span
  m='4334860'>rules.</span> </p><p><span m='4335540'>Just</span> <span m='4335810'>in</span>
  <span m='4336130'>case, I'll just</span> <span m='4336450'>go</span> <span m='4336690'>through</span>
  <span m='4336990'>a quick--</span> <span m='4337490'>19 by</span> <span m='4337820'>19.</span>
  <span m='4338220'>You</span> <span m='4338370'>alternate</span> <span m='4338590'>black</span>
  <span m='4338820'>stones</span> <span m='4339180'>and</span> <span m='4339360'>white</span>
  <span m='4339570'>stones.</span> <span m='4340300'>You</span> <span m='4340380'>collect</span>
  <span m='4340830'>enemy</span> <span m='4341220'>stones</span> <span m='4341590'>by</span>
  <span m='4341860'>completely</span> <span m='4342130'>surrounding</span> <span m='4342910'>them.</span>
  <span m='4343480'>You</span> <span m='4343580'>can</span> <span m='4343590'>surround</span>
  <span m='4343950'>a</span> <span m='4344170'>single stone.</span> <span m='4344220'>groups</span>
  <span m='4344820'>of</span> <span m='4344930'>stones.</span> </p><p><span m='4345740'>And</span>
  <span m='4345840'>your</span> <span m='4345960'>score</span> <span m='4346350'>is</span>
  <span m='4346770'>your</span> <span m='4346890'>territory</span> <span m='4347880'>plus</span>
  <span m='4348150'>the</span> <span m='4348240'>number</span> <span m='4348420'>of</span>
  <span m='4348480'>captive</span> <span m='4348840'>pieces.</span> <span m='4349115'>So</span>
  <span m='4349390'>your</span> <span m='4349650'>territory</span> <span m='4349860'>is
  just the</span> <span m='4350240'>area</span> <span m='4350570'>that</span> <span
  m='4350640'>you're</span> <span m='4350840'>surrounding,</span> <span m='4351240'>and
  then</span> <span m='4351700'>you just</span> <span m='4351960'>add the</span> <span
  m='4352230'>stones</span> <span m='4352630'>you've</span> <span m='4352800'>collected.</span>
  </p><p><span m='4354570'>The</span> <span m='4354960'>rules</span> <span m='4355200'>aren't</span>
  <span m='4355320'>super</span> <span m='4355550'>important.</span> <span m='4355880'>The</span>
  <span m='4355950'>main</span> <span m='4356130'>emphasis</span> <span m='4356440'>is</span>
  <span m='4357990'>there's</span> <span m='4358200'>very</span> <span m='4358440'>few</span>
  <span m='4358590'>rules</span> <span m='4358980'>so you</span> <span m='4359407'>would
  think</span> <span m='4359834'>it's</span> <span m='4360261'>really simple.</span>
  <span m='4360690'>But</span> <span m='4361350'>the</span> <span m='4361410'>complexity</span>
  <span m='4361920'>of</span> <span m='4361980'>the</span> <span m='4362070'>game</span>
  <span m='4362310'>is</span> <span m='4362630'>quite</span> <span m='4362850'>extreme.</span>
  </p><p><span m='4365660'>At</span> <span m='4365820'>each</span> <span m='4366090'>turn</span>
  <span m='4366480'>you</span> <span m='4366630'>have</span> <span m='4366750'>about</span>
  <span m='4366990'>250</span> <span m='4367345'>options</span> <span m='4368000'>that</span>
  <span m='4368240'>you</span> <span m='4368370'>can</span> <span m='4368580'>play.</span>
  <span m='4370290'>Each</span> <span m='4370460'>Go</span> <span m='4370700'>game</span>
  <span m='4370960'>lasts</span> <span m='4371370'>about</span> <span m='4371470'>150</span>
  <span m='4371820'>turns.</span> <span m='4372440'>So</span> <span m='4372850'>that
  gives you</span> <span m='4373260'>a total of</span> <span m='4373670'>10</span>
  <span m='4373950'>to the</span> <span m='4374180'>761</span> <span m='4374480'>games,</span>
  <span m='4374750'>approximately.</span> </p><p><span m='4376370'>And</span> <span
  m='4376540'>to put</span> <span m='4376720'>that</span> <span m='4376960'>in</span>
  <span m='4377340'>comparison,</span> <span m='4377550'>here's</span> <span m='4377730'>chess.</span>
  <span m='4378470'>You can</span> <span m='4378620'>read</span> <span m='4378810'>those</span>
  <span m='4379050'>numbers.</span> <span m='4379820'>Chess</span> <span m='4380190'>is
  also</span> <span m='4380400'>pretty</span> <span m='4380610'>complex.</span> <span
  m='4381400'>But there's</span> <span m='4381680'>35</span> <span m='4381965'>options</span>
  <span m='4382250'>for</span> <span m='4382490'>turns.</span> </p><p><span m='4383610'>Deep</span>
  <span m='4383820'>Blue.</span> <span m='4386470'>I think you</span> <span m='4386760'>were</span>
  <span m='4387000'>talking about</span> <span m='4387230'>building</span> <span m='4387390'>out</span>
  <span m='4387680'>the</span> <span m='4387770'>whole</span> <span m='4388110'>tree.</span>
  <span m='4388890'>So</span> <span m='4389070'>Deep</span> <span m='4389310'>Blue</span>
  <span m='4389670'>would</span> <span m='4390010'>build out</span> <span m='4390350'>the
  tree</span> <span m='4390665'>for</span> <span m='4390980'>six</span> <span m='4391230'>levels.</span>
  <span m='4392100'>And</span> <span m='4392220'>then</span> <span m='4392990'>use</span>
  <span m='4393230'>this</span> <span m='4393600'>hard</span> <span m='4393930'>core</span>
  <span m='4394140'>chess</span> <span m='4394545'>master</span> <span m='4394950'>inputted</span>
  <span m='4395550'>heuristic</span> <span m='4396780'>evaluation</span> <span m='4397460'>that</span>
  <span m='4397640'>it used</span> <span m='4397850'>to</span> <span m='4398200'>find
  the</span> <span m='4398550'>best</span> <span m='4398900'>move.</span> </p><p><span
  m='4400230'>Except</span> <span m='4400605'>with</span> <span m='4400980'>Go,</span>
  <span m='4401620'>you</span> <span m='4401760'>have</span> <span m='4402040'>250</span>
  <span m='4402376'>options,</span> <span m='4402712'>which</span> <span m='4403050'>already</span>
  <span m='4403410'>is</span> <span m='4404150'>adding</span> <span m='4404370'>a
  lot</span> <span m='4404680'>more</span> <span m='4404970'>complexity.</span> <span
  m='4406670'>So</span> <span m='4406710'>that</span> <span m='4406950'>strategy</span>
  <span m='4407100'>won't</span> <span m='4407520'>work</span> <span m='4408360'>quite</span>
  <span m='4408600'>as</span> <span m='4408720'>nicely.</span> <span m='4410970'>What</span>
  <span m='4411140'>do</span> <span m='4411170'>we</span> <span m='4411270'>do?</span>
  </p><p><span m='4411870'>We use a</span> <span m='4412160'>modified</span> <span
  m='4412710'>version</span> <span m='4413040'>of</span> <span m='4413400'>MCTS.</span>
  <span m='4414075'>Well,</span> <span m='4414420'>it's not what</span> <span m='4414740'>we</span>
  <span m='4414960'>do.</span> <span m='4415210'>That's</span> <span m='4415420'>what</span>
  <span m='4417174'>Google's</span> <span m='4417611'>DeepMind</span> <span m='4418230'>team</span>
  <span m='4418725'>did with Go.</span> <span m='4419220'>They</span> <span m='4419370'>combined</span>
  <span m='4419770'>neural</span> <span m='4420030'>networks</span> <span m='4420480'>with</span>
  <span m='4420680'>MCTS.</span> <span m='4421900'>Coincidentally,</span> <span m='4423330'>we</span>
  <span m='4423450'>learned</span> <span m='4423900'>about</span> <span m='4424170'>neural
  networks</span> <span m='4424530'>last</span> <span m='4424830'>class.</span> <span
  m='4425430'>Probably</span> <span m='4425730'>not</span> <span m='4425970'>a</span>
  <span m='4426030'>coincidence.</span> </p><p><span m='4428220'>PROFESSOR 3:</span>
  <span m='4428280'>It's</span> <span m='4428340'>not a</span> <span m='4428693'>coincidence.</span>
  </p><p><span m='4429400'>PROFESSOR 3:</span> <span m='4429495'>The</span> <span
  m='4429590'>we</span> <span m='4429980'>ordered</span> <span m='4430110'>two</span>
  <span m='4430240'>policy</span> <span m='4430370'>networks</span> <span m='4431500'>in</span>
  <span m='4431720'>the</span> <span m='4431970'>AlphaGo,</span> <span m='4432420'>and</span>
  <span m='4432580'>one</span> <span m='4432770'>value</span> <span m='4433000'>network.</span>
  <span m='4433430'>And</span> <span m='4433850'>another</span> <span m='4434220'>big</span>
  <span m='4434430'>coincidence</span> <span m='4435030'>here,</span> <span m='4435580'>the</span>
  <span m='4435890'>two</span> <span m='4436180'>policy</span> <span m='4436635'>networks</span>
  <span m='4437090'>are actually</span> <span m='4437475'>CNN's,</span> <span m='4437860'>which
  we</span> <span m='4438160'>learned</span> <span m='4438390'>specifically</span>
  <span m='4439110'>about</span> <span m='4439320'>last</span> <span m='4439730'>class,</span>
  <span m='4440140'>convolutional</span> <span m='4440550'>neural</span> <span m='4440770'>nets.</span>
  </p><p><span m='4441390'>And</span> <span m='4442200'>the</span> <span m='4442260'>reason</span>
  <span m='4442530'>for</span> <span m='4442680'>that</span> <span m='4443700'>is</span>
  <span m='4443850'>the</span> <span m='4444060'>input</span> <span m='4444515'>to</span>
  <span m='4445340'>the</span> <span m='4445460'>policy</span> <span m='4445750'>neural</span>
  <span m='4446040'>networks</span> <span m='4446520'>is</span> <span m='4446730'>an</span>
  <span m='4446820'>image</span> <span m='4447450'>of</span> <span m='4447600'>the</span>
  <span m='4447690'>game.</span> <span m='4448050'>And remember,</span> <span m='4448503'>convolutional</span>
  <span m='4448956'>neural</span> <span m='4449410'>nets</span> <span m='4449720'>work</span>
  <span m='4449940'>really</span> <span m='4450120'>well</span> <span m='4450310'>with</span>
  <span m='4450560'>images.</span> <span m='4452170'>What</span> <span m='4452480'>it</span>
  <span m='4452790'>outputs,</span> <span m='4453030'>though,</span> <span m='4453300'>is</span>
  <span m='4453830'>a</span> <span m='4453900'>probability</span> <span m='4454650'>distribution</span>
  <span m='4455520'>over the</span> <span m='4455770'>legal</span> <span m='4456120'>moves.</span>
  </p><p><span m='4456770'>And</span> <span m='4457400'>the</span> <span m='4457530'>idea</span>
  <span m='4457850'>is,</span> <span m='4458040'>that</span> <span m='4458310'>if</span>
  <span m='4458610'>a move</span> <span m='4458840'>has</span> <span m='4459110'>a</span>
  <span m='4459180'>higher</span> <span m='4459420'>probability</span> <span m='4460740'>it</span>
  <span m='4460990'>will</span> <span m='4461130'>be</span> <span m='4461580'>a</span>
  <span m='4461670'>more</span> <span m='4461850'>promising</span> <span m='4462330'>move</span>
  <span m='4462520'>for</span> <span m='4462630'>you</span> <span m='4462700'>to</span>
  <span m='4462790'>take.</span> <span m='4463830'>But</span> <span m='4465000'>another</span>
  <span m='4466010'>key</span> <span m='4466150'>point</span> <span m='4466360'>is</span>
  <span m='4466410'>that</span> <span m='4466590'>it's</span> <span m='4466690'>not</span>
  <span m='4467115'>deterministic.</span> <span m='4467540'>It's not</span> <span
  m='4467770'>telling</span> <span m='4467960'>you</span> <span m='4468090'>to</span>
  <span m='4468230'>take</span> <span m='4468460'>this move.</span> <span m='4468820'>It's
  just</span> <span m='4469180'>assigning a</span> <span m='4469470'>higher</span>
  <span m='4469740'>probability</span> <span m='4470070'>to this</span> <span m='4470400'>move.</span>
  </p><p><span m='4472310'>And</span> <span m='4472530'>this</span> <span m='4472710'>network</span>
  <span m='4472980'>was generated</span> <span m='4473520'>by</span> <span m='4473810'>doing</span>
  <span m='4474290'>supervised</span> <span m='4474630'>learning</span> <span m='4474990'>on</span>
  <span m='4475260'>30</span> <span m='4475740'>million</span> <span m='4476610'>positions</span>
  <span m='4477120'>from</span> <span m='4477360'>human</span> <span m='4477750'>expert</span>
  <span m='4478170'>games.</span> <span m='4479390'>Apparently,</span> <span m='4479880'>there's</span>
  <span m='4480060'>a</span> <span m='4480120'>giant</span> <span m='4480630'>database</span>
  <span m='4481140'>of</span> <span m='4481470'>Go</span> <span m='4481820'>expert</span>
  <span m='4482220'>games.</span> <span m='4482640'>So</span> <span m='4483060'>that</span>
  <span m='4483480'>came in</span> <span m='4483690'>handy.</span> </p><p><span m='4484260'>And</span>
  <span m='4484676'>there</span> <span m='4485092'>were two</span> <span m='4485510'>different
  networks</span> <span m='4485830'>trained.</span> <span m='4486870'>One</span> <span
  m='4486990'>of</span> <span m='4487050'>them was a</span> <span m='4487320'>slow</span>
  <span m='4487710'>policy,</span> <span m='4488040'>the other</span> <span m='4488490'>was
  a</span> <span m='4488580'>fast</span> <span m='4488930'>policy.</span> <span m='4489810'>The</span>
  <span m='4489900'>slow</span> <span m='4490680'>was</span> <span m='4491040'>able</span>
  <span m='4491180'>to</span> <span m='4491270'>predict</span> <span m='4491910'>an</span>
  <span m='4492030'>expert</span> <span m='4492420'>move</span> <span m='4492780'>with</span>
  <span m='4492960'>57%</span> <span m='4493950'>accuracy,</span> <span m='4494980'>which</span>
  <span m='4495090'>to</span> <span m='4495240'>me</span> <span m='4495420'>was</span>
  <span m='4495540'>mind</span> <span m='4495870'>blowing.</span> <span m='4497250'>Using</span>
  <span m='4497520'>this</span> <span m='4498330'>neural</span> <span m='4498650'>network,</span>
  <span m='4499080'>57%</span> <span m='4499810'>of</span> <span m='4500040'>the</span>
  <span m='4500330'>time it</span> <span m='4500590'>could</span> <span m='4500790'>pin</span>
  <span m='4501480'>where</span> <span m='4501810'>the</span> <span m='4501990'>expert</span>
  <span m='4502310'>would</span> <span m='4502470'>place his</span> <span m='4502910'>move.</span>
  <span m='4504260'>That</span> <span m='4504510'>took</span> <span m='4504780'>3,000</span>
  <span m='4505050'>microseconds.</span> </p><p><span m='4505780'>Versus</span> <span
  m='4506010'>the</span> <span m='4506330'>fast</span> <span m='4506440'>policy,</span>
  <span m='4507390'>which</span> <span m='4507910'>suffered</span> <span m='4508210'>a
  bit</span> <span m='4508510'>in the</span> <span m='4508740'>accuracy,</span> <span
  m='4508995'>but</span> <span m='4509250'>it's</span> <span m='4509500'>1,500</span>
  <span m='4510270'>times</span> <span m='4510600'>faster.</span> <span m='4511370'>And</span>
  <span m='4511470'>we'll</span> <span m='4511560'>see</span> <span m='4511860'>where</span>
  <span m='4512160'>they</span> <span m='4512270'>used</span> <span m='4512550'>each
  of</span> <span m='4512800'>these</span> <span m='4512970'>different</span> <span
  m='4513220'>policies</span> <span m='4514350'>later</span> <span m='4514650'>on.</span>
  <span m='4515580'>But</span> <span m='4517170'>it could</span> <span m='4517410'>predict</span>
  <span m='4517560'>the</span> <span m='4517940'>expert</span> <span m='4518150'>move</span>
  <span m='4518370'>with</span> <span m='4518610'>57%</span> <span m='4519300'>accuracy.</span>
  </p><p><span m='4520680'>The</span> <span m='4520830'>other</span> <span m='4521010'>Go</span>
  <span m='4521180'>team</span> <span m='4521310'>was,</span> <span m='4521940'>that's</span>
  <span m='4522345'>not our</span> <span m='4522750'>goal.</span> <span m='4522930'>We</span>
  <span m='4523050'>don't want to</span> <span m='4523240'>predict</span> <span m='4523490'>an
  expert</span> <span m='4523710'>move.</span> <span m='4523810'>We</span> <span m='4524030'>want</span>
  <span m='4524190'>to</span> <span m='4524290'>predict</span> <span m='4524630'>a</span>
  <span m='4524750'>winning</span> <span m='4525140'>move.</span> </p><p><span m='4525630'>And</span>
  <span m='4525730'>so</span> <span m='4525900'>to</span> <span m='4526050'>do</span>
  <span m='4526260'>that,</span> <span m='4526560'>they</span> <span m='4526800'>took</span>
  <span m='4527040'>their</span> <span m='4527270'>policy</span> <span m='4527585'>network,</span>
  <span m='4528180'>and</span> <span m='4528630'>then they would</span> <span m='4529080'>use</span>
  <span m='4529760'>reinforcement</span> <span m='4530020'>learning.</span> <span
  m='4530170'>That's</span> <span m='4530470'>where you</span> <span m='4530760'>play</span>
  <span m='4531080'>the network</span> <span m='4531460'>against</span> <span m='4532400'>iterations</span>
  <span m='4532950'>of</span> <span m='4533040'>itself</span> <span m='4533820'>in
  order</span> <span m='4533910'>to</span> <span m='4534090'>hone</span> <span m='4534445'>in</span>
  <span m='4534800'>a</span> <span m='4534970'>better</span> <span m='4535290'>policy</span>
  <span m='4535560'>that's</span> <span m='4535830'>geared</span> <span m='4536250'>towards</span>
  <span m='4536710'>winning</span> <span m='4537000'>moves.</span> <span m='4539560'>Then</span>
  <span m='4539990'>they</span> <span m='4540140'>tested this</span> <span m='4540320'>against</span>
  <span m='4540630'>Pachi,</span> <span m='4541110'>which</span> <span m='4541685'>uses--</span>
  <span m='4543010'>for</span> <span m='4543210'>the</span> <span m='4543300'>camera,</span>
  <span m='4543800'>I have no</span> <span m='4543990'>idea</span> <span m='4544230'>if
  that's</span> <span m='4544555'>how you</span> <span m='4544880'>pronounce</span>
  <span m='4545090'>Pachi.</span> <span m='4545340'>It</span> <span m='4545540'>might</span>
  <span m='4545750'>be</span> <span m='4545990'>Patchey.</span> <span m='4546295'>I'm
  not</span> <span m='4546600'>sure.</span> <span m='4547320'>But</span> <span m='4547560'>there's</span>
  <span m='4548010'>100,000</span> <span m='4549645'>MCTS</span> <span m='4550760'>simulations</span>
  <span m='4551055'>at</span> <span m='4551350'>each</span> <span m='4551840'>turn.</span>
  <span m='4552330'>So</span> <span m='4552430'>this</span> <span m='4552480'>is</span>
  <span m='4552710'>purely</span> <span m='4553000'>MCTS.</span> </p><p><span m='4555420'>If
  it</span> <span m='4555840'>were</span> <span m='4556310'>playing</span> <span m='4556620'>just</span>
  <span m='4557040'>the</span> <span m='4557190'>AlphaGo</span> <span m='4558070'>policy</span>
  <span m='4558510'>network,</span> <span m='4559842'>the</span> <span m='4560340'>policy</span>
  <span m='4560640'>network</span> <span m='4561030'>won</span> <span m='4561310'>85%</span>
  <span m='4561763'>of the</span> <span m='4562216'>game.</span> <span m='4563700'>So</span>
  <span m='4563970'>without</span> <span m='4564250'>any</span> <span m='4564430'>sort</span>
  <span m='4564640'>of</span> <span m='4564940'>trained</span> <span m='4565370'>search</span>
  <span m='4565710'>or</span> <span m='4565960'>anything</span> <span m='4566290'>involved,</span>
  <span m='4566780'>it won</span> <span m='4567260'>85%,</span> <span m='4567860'>which
  is</span> <span m='4567960'>pretty</span> <span m='4568180'>great.</span> <span
  m='4568680'>And</span> <span m='4568760'>that</span> <span m='4569410'>suggests</span>
  <span m='4569800'>that</span> <span m='4569920'>maybe</span> <span m='4570250'>intuition</span>
  <span m='4571340'>wins</span> <span m='4571810'>over</span> <span m='4572140'>long</span>
  <span m='4572510'>reflections</span> <span m='4573030'>in</span> <span m='4573200'>Go.</span>
  <span m='4573880'>And</span> <span m='4574450'>interestingly,</span> <span m='4575040'>if</span>
  <span m='4575170'>you</span> <span m='4575230'>talk</span> <span m='4575560'>to</span>
  <span m='4575800'>expert Go</span> <span m='4576100'>players</span> <span m='4576535'>and
  you</span> <span m='4576970'>ask them</span> <span m='4577390'>why</span> <span
  m='4577570'>they did a</span> <span m='4578070'>certain move,</span> <span m='4578350'>they'll</span>
  <span m='4578695'>just</span> <span m='4579040'>say,</span> <span m='4579340'>It</span>
  <span m='4579760'>felt</span> <span m='4580060'>good,</span> <span m='4580480'>or</span>
  <span m='4580933'>I had</span> <span m='4581386'>a</span> <span m='4581840'>hunch</span>
  <span m='4582080'>in this.</span> <span m='4582840'>That's</span> <span m='4584100'>indicative</span>
  <span m='4584590'>there.</span> </p><p><span m='4586660'>Hopefully,</span> <span
  m='4587153'>I'm not</span> <span m='4587646'>going overtime.</span> <span m='4588330'>Sorry.</span>
  </p><p><span m='4589970'>Those</span> <span m='4590380'>are</span> <span m='4590560'>the</span>
  <span m='4590740'>two</span> <span m='4590920'>policy</span> <span m='4591190'>networks.</span>
  <span m='4591505'>There's also a</span> <span m='4591820'>value</span> <span m='4592120'>network.</span>
  <span m='4592270'>What</span> <span m='4592480'>the</span> <span m='4592980'>value</span>
  <span m='4593340'>network</span> <span m='4593590'>does</span> <span m='4593860'>is</span>
  <span m='4593980'>it</span> <span m='4594040'>takes</span> <span m='4594370'>in</span>
  <span m='4594830'>a</span> <span m='4595040'>board,</span> <span m='4595450'>and</span>
  <span m='4595735'>they'll</span> <span m='4596020'>give you</span> <span m='4596320'>a</span>
  <span m='4596710'>value,</span> <span m='4597220'>like</span> <span m='4598180'>how</span>
  <span m='4598480'>good</span> <span m='4598710'>is this</span> <span m='4598870'>board?</span>
  <span m='4600140'>They'll</span> <span m='4600350'>give you</span> <span m='4600713'>a</span>
  <span m='4601076'>win</span> <span m='4601440'>probability</span> <span m='4601990'>number.</span>
  <span m='4602260'>So</span> <span m='4602570'>77%,</span> <span m='4603540'>it would</span>
  <span m='4603960'>say,</span> <span m='4604560'>77%</span> <span m='4605020'>of
  the</span> <span m='4605360'>time you should</span> <span m='4605710'>win</span>
  <span m='4605960'>from</span> <span m='4606130'>the</span> <span m='4606330'>board.</span>
  </p><p><span m='4607490'>That's</span> <span m='4607700'>similar</span> <span m='4608050'>to
  the</span> <span m='4608500'>evaluation that</span> <span m='4608890'>comes from</span>
  <span m='4609240'>Deep</span> <span m='4609510'>Blue.</span> <span m='4609820'>But</span>
  <span m='4610170'>rather</span> <span m='4610440'>than</span> <span m='4610600'>a</span>
  <span m='4610990'>Go</span> <span m='4611210'>master</span> <span m='4611485'>coming</span>
  <span m='4611760'>in</span> <span m='4612210'>and</span> <span m='4612540'>telling</span>
  <span m='4612820'>you,</span> <span m='4613570'>well, if</span> <span m='4613900'>these</span>
  <span m='4614080'>are</span> <span m='4614140'>connected</span> <span m='4614560'>in</span>
  <span m='4614680'>this</span> <span m='4614830'>way,</span> <span m='4615730'>and</span>
  <span m='4615970'>down</span> <span m='4616240'>here</span> <span m='4616420'>we</span>
  <span m='4616530'>have</span> <span m='4616640'>this</span> <span m='4616870'>certain</span>
  <span m='4617290'>thing</span> <span m='4617730'>then</span> <span m='4618170'>here's</span>
  <span m='4618610'>the</span> <span m='4618970'>score</span> <span m='4619310'>we
  should</span> <span m='4619460'>expect,</span> <span m='4620060'>in</span> <span
  m='4620300'>chess,</span> <span m='4621040'>they</span> <span m='4621160'>had</span>
  <span m='4621310'>chess</span> <span m='4621550'>masters,</span> <span m='4621900'>like</span>
  <span m='4622120'>if the</span> <span m='4622260'>knight is</span> <span m='4622660'>here</span>
  <span m='4623010'>and the</span> <span m='4623140'>queen</span> <span m='4623460'>is
  here, all these</span> <span m='4623780'>specific</span> <span m='4624310'>things.</span>
  </p><p><span m='4624840'>This</span> <span m='4625070'>was actually</span> <span
  m='4625180'>learned</span> <span m='4625870'>from</span> <span m='4626470'>the</span>
  <span m='4626740'>reinforcement</span> <span m='4627430'>learning</span> <span m='4627760'>that</span>
  <span m='4627880'>was</span> <span m='4628000'>happening</span> <span m='4628660'>when</span>
  <span m='4628720'>the</span> <span m='4628810'>policy</span> <span m='4629150'>networks</span>
  <span m='4629310'>were</span> <span m='4629440'>playing</span> <span m='4629710'>each</span>
  <span m='4629975'>other.</span> <span m='4630240'>The</span> <span m='4630650'>value</span>
  <span m='4630800'>network</span> <span m='4631000'>was</span> <span m='4631180'>learning</span>
  <span m='4631780'>about</span> <span m='4632050'>those</span> <span m='4632260'>positions</span>
  <span m='4632890'>during</span> <span m='4633130'>that</span> <span m='4633280'>time.</span>
  <span m='4634650'>And</span> <span m='4634930'>the</span> <span m='4635210'>predictions</span>
  <span m='4635310'>get</span> <span m='4635600'>better</span> <span m='4635900'>towards</span>
  <span m='4636070'>the end of</span> <span m='4636280'>the</span> <span m='4636340'>game,</span>
  <span m='4636800'>which</span> <span m='4636910'>I</span> <span m='4637000'>think</span>
  <span m='4637230'>Yo</span> <span m='4637420'>mentioned</span> <span m='4638500'>in</span>
  <span m='4639030'>his</span> <span m='4639250'>talk.</span> </p><p><span m='4641590'>So</span>
  <span m='4641950'>how do you</span> <span m='4642020'>combine</span> <span m='4642400'>all</span>
  <span m='4642490'>these</span> <span m='4642730'>into</span> <span m='4642940'>MCTS?</span>
  <span m='4643980'>The</span> <span m='4644340'>slow</span> <span m='4644630'>policy</span>
  <span m='4645035'>network, if you remember, is</span> <span m='4645440'>slower</span>
  <span m='4645790'>but</span> <span m='4646360'>should</span> <span m='4646660'>give
  us</span> <span m='4646870'>stronger</span> <span m='4647320'>moves.</span> <span
  m='4647830'>It is</span> <span m='4647950'>used</span> <span m='4648130'>to</span>
  <span m='4648250'>guide</span> <span m='4648670'>our</span> <span m='4648790'>tree</span>
  <span m='4649270'>search</span> <span m='4649540'>in</span> <span m='4649600'>order</span>
  <span m='4649780'>to</span> <span m='4650280'>help</span> <span m='4650460'>us</span>
  <span m='4650920'>decide</span> <span m='4651280'>which</span> <span m='4651490'>nodes</span>
  <span m='4651780'>to</span> <span m='4651850'>expand</span> <span m='4652300'>next.</span>
  <span m='4653322'>When we</span> <span m='4653680'>expand</span> <span m='4654090'>that</span>
  <span m='4654260'>node</span> <span m='4654520'>to get</span> <span m='4654620'>the</span>
  <span m='4654770'>value,</span> <span m='4655840'>the</span> <span m='4656040'>value
  of</span> <span m='4656410'>the state</span> <span m='4656810'>is</span> <span m='4657100'>the</span>
  <span m='4657190'>simulation,</span> <span m='4657820'>like</span> <span m='4658000'>before,</span>
  <span m='4658390'>like</span> <span m='4658840'>normal</span> <span m='4659290'>MCTS,</span>
  <span m='4660050'>except</span> <span m='4660670'>it's</span> <span m='4660820'>not</span>
  <span m='4661000'>a completely</span> <span m='4661340'>random</span> <span m='4661650'>simulation.</span>
  </p><p><span m='4662560'>We use</span> <span m='4662770'>our fast</span> <span m='4663010'>policy</span>
  <span m='4663650'>network</span> <span m='4664020'>to give us</span> <span m='4664320'>a</span>
  <span m='4664450'>more</span> <span m='4664660'>educated</span> <span m='4665200'>simulation</span>
  <span m='4665770'>here.</span> <span m='4666390'>But</span> <span m='4666530'>we're</span>
  <span m='4666690'>using</span> <span m='4667170'>a fast one,</span> <span m='4667360'>obviously,</span>
  <span m='4667700'>to</span> <span m='4667900'>save</span> <span m='4668200'>some</span>
  <span m='4668810'>computation</span> <span m='4669370'>time.</span> <span m='4669990'>It's</span>
  <span m='4670180'>giving</span> <span m='4670330'>us</span> <span m='4671260'>probably</span>
  <span m='4671605'>a</span> <span m='4671950'>more</span> <span m='4672160'>indicative</span>
  <span m='4672700'>random</span> <span m='4673070'>simulation</span> <span m='4673810'>of</span>
  <span m='4673930'>what's</span> <span m='4674130'>going</span> <span m='4674260'>to</span>
  <span m='4674320'>actually</span> <span m='4674710'>happen.</span> </p><p><span
  m='4675920'>And</span> <span m='4676020'>then</span> <span m='4676120'>we</span>
  <span m='4676220'>also</span> <span m='4676810'>combine</span> <span m='4677170'>that</span>
  <span m='4677320'>with</span> <span m='4677470'>our</span> <span m='4677610'>value</span>
  <span m='4678010'>network</span> <span m='4678370'>output.</span> <span m='4678830'>So</span>
  <span m='4678880'>we</span> <span m='4678970'>run</span> <span m='4679150'>our</span>
  <span m='4679390'>value network</span> <span m='4679680'>on</span> <span m='4679890'>this</span>
  <span m='4680050'>node,</span> <span m='4680490'>as</span> <span m='4680860'>well.</span>
  <span m='4681070'>And we</span> <span m='4681400'>add that</span> <span m='4681680'>to
  our</span> <span m='4682070'>simulation value and we</span> <span m='4682502'>propagate
  it.</span> </p><p><span m='4683800'>Interestingly,</span> <span m='4684145'>the</span>
  <span m='4684490'>AlphaGo</span> <span m='4684865'>team</span> <span m='4685525'>tested</span>
  <span m='4685810'>out</span> <span m='4686440'>just</span> <span m='4686840'>using</span>
  <span m='4687190'>the</span> <span m='4687420'>fast</span> <span m='4687700'>policy</span>
  <span m='4688290'>simulation</span> <span m='4688615'>value</span> <span m='4689140'>and</span>
  <span m='4689590'>scrapping</span> <span m='4689890'>the</span> <span m='4690190'>value</span>
  <span m='4690470'>network.</span> <span m='4691180'>And they</span> <span m='4691410'>also</span>
  <span m='4692040'>just</span> <span m='4692260'>used the</span> <span m='4692710'>value
  network</span> <span m='4693160'>and scrapped the</span> <span m='4693490'>simulation</span>
  <span m='4693770'>value.</span> <span m='4694720'>And</span> <span m='4694910'>those</span>
  <span m='4695120'>both</span> <span m='4695570'>performed</span> <span m='4695820'>worse
  than</span> <span m='4696160'>if it had</span> <span m='4696570'>these.</span> </p><p><span
  m='4697030'>And</span> <span m='4697120'>another</span> <span m='4697720'>added</span>
  <span m='4698620'>interesting</span> <span m='4699070'>point</span> <span m='4699370'>here,</span>
  <span m='4699625'>is</span> <span m='4699880'>that</span> <span m='4700160'>these</span>
  <span m='4700780'>two</span> <span m='4701230'>factors</span> <span m='4701770'>in</span>
  <span m='4701860'>our</span> <span m='4701960'>value</span> <span m='4702630'>have</span>
  <span m='4702820'>about</span> <span m='4703180'>the</span> <span m='4703270'>same</span>
  <span m='4703600'>weight.</span> <span m='4704130'>They</span> <span m='4704260'>were</span>
  <span m='4704330'>both</span> <span m='4704710'>about</span> <span m='4705170'>equally</span>
  <span m='4705320'>important.</span> <span m='4707970'>I</span> <span m='4708110'>think</span>
  <span m='4708330'>I'll</span> <span m='4708640'>get into</span> <span m='4708950'>that</span>
  <span m='4709190'>later.</span> <span m='4709635'>But</span> <span m='4710080'>first--</span>
  </p><p><span m='4710410'>AUDIENCE:</span> <span m='4710497'>Can</span> <span m='4710584'>I</span>
  <span m='4710671'>just</span> <span m='4710760'>ask</span> <span m='4711030'>a quick</span>
  <span m='4711330'>question?</span> </p><p><span m='4711630'>PROFESSOR 3:</span>
  <span m='4711770'>Yeah.</span> </p><p><span m='4714160'>AUDIENCE:</span> <span m='4714265'>So</span>
  <span m='4714370'>when</span> <span m='4714520'>you</span> <span m='4714610'>said</span>
  <span m='4714760'>the</span> <span m='4714880'>policy</span> <span m='4715330'>network</span>
  <span m='4715690'>is</span> <span m='4715850'>used,</span> <span m='4716230'>is</span>
  <span m='4716350'>that</span> <span m='4716520'>used</span> <span m='4716810'>when</span>
  <span m='4716920'>you're</span> <span m='4717100'>navigating</span> <span m='4717410'>to</span>
  <span m='4717580'>the</span> <span m='4717760'>tree</span> <span m='4718240'>to</span>
  <span m='4718330'>get</span> <span m='4718460'>to a</span> <span m='4718570'>leaf,</span>
  <span m='4719020'>or</span> <span m='4719470'>is</span> <span m='4719590'>policy</span>
  <span m='4720000'>network</span> <span m='4720350'>being</span> <span m='4721420'>used</span>
  <span m='4721720'>to</span> <span m='4721840'>do</span> <span m='4721960'>the</span>
  <span m='4722050'>simulation</span> <span m='4723100'>once</span> <span m='4723340'>you're</span>
  <span m='4723470'>at the</span> <span m='4723920'>leaf, or both?</span> </p><p><span
  m='4726340'>PROFESSOR 3:</span> <span m='4726445'>The</span> <span m='4726550'>slow</span>
  <span m='4727000'>policy is</span> <span m='4727940'>done for</span> <span m='4728410'>this</span>
  <span m='4728500'>part.</span> <span m='4729310'>Then the</span> <span m='4729460'>fast</span>
  <span m='4729730'>policy</span> <span m='4729940'>is</span> <span m='4730150'>used</span>
  <span m='4730470'>for the</span> <span m='4730823'>simulation.</span> <span m='4731176'>Because</span>
  <span m='4731530'>the</span> <span m='4731770'>slow</span> <span m='4731980'>policy</span>
  <span m='4732070'>does</span> <span m='4732280'>take</span> <span m='4732520'>1,500</span>
  <span m='4733510'>faster</span> <span m='4733930'>than--</span> <span m='4734455'>or</span>
  <span m='4734710'>the</span> <span m='4734920'>slow</span> <span m='4735410'>takes</span>
  <span m='4735640'>1,500</span> <span m='4736090'>times</span> <span m='4737210'>longer</span>
  <span m='4737440'>than</span> <span m='4737630'>the</span> <span m='4737840'>fast</span>
  <span m='4738190'>policy.</span> <span m='4738540'>You</span> <span m='4738640'>don't</span>
  <span m='4738740'>want</span> <span m='4738880'>to use that in</span> <span m='4739270'>your</span>
  <span m='4739660'>simulations.</span> <span m='4740010'>That would just take</span>
  <span m='4740356'>way too long.</span> </p><p><span m='4742280'>It's</span> <span
  m='4742570'>basically just</span> <span m='4742750'>a</span> <span m='4742840'>way</span>
  <span m='4743150'>of making</span> <span m='4743260'>it</span> <span m='4743510'>so
  our</span> <span m='4743650'>simulation</span> <span m='4744100'>isn't</span> <span
  m='4744510'>completely</span> <span m='4744920'>random.</span> <span m='4745190'>It
  has</span> <span m='4745390'>some</span> <span m='4745780'>educated</span> <span
  m='4746260'>moves.</span> </p><p><span m='4749490'>Why</span> <span m='4749910'>use</span>
  <span m='4750380'>policy</span> <span m='4750790'>and</span> <span m='4751200'>value</span>
  <span m='4751380'>network</span> <span m='4751560'>synergy?</span> <span m='4751800'>Why
  can't we</span> <span m='4751930'>just</span> <span m='4752200'>use</span> <span
  m='4752590'>the policy</span> <span m='4752790'>network?</span> <span m='4753100'>Why</span>
  <span m='4753400'>can't we</span> <span m='4753600'>just</span> <span m='4753910'>use
  the</span> <span m='4754210'>value</span> <span m='4754430'>network?</span> </p><p><span
  m='4755070'>If</span> <span m='4755420'>we</span> <span m='4755660'>have</span>
  <span m='4756020'>the</span> <span m='4756380'>value network</span> <span m='4756740'>alone,</span>
  <span m='4756920'>we'll</span> <span m='4757220'>actually--</span> <span m='4757610'>here's</span>
  <span m='4757780'>a</span> <span m='4758090'>side</span> <span m='4758390'>point.</span>
  <span m='4758820'>Remember,</span> <span m='4759040'>the value</span> <span m='4759385'>network</span>
  <span m='4759730'>learned</span> <span m='4760030'>from</span> <span m='4760180'>the</span>
  <span m='4760270'>policy</span> <span m='4760560'>network.</span> <span m='4761320'>And</span>
  <span m='4761410'>then</span> <span m='4761590'>also,</span> <span m='4762070'>later</span>
  <span m='4762340'>on,</span> <span m='4762600'>the</span> <span m='4762770'>policy</span>
  <span m='4763020'>network</span> <span m='4763140'>is</span> <span m='4763350'>improved</span>
  <span m='4763840'>by</span> <span m='4764590'>our</span> <span m='4764740'>values.</span>
  <span m='4766070'>They</span> <span m='4766360'>work</span> <span m='4766650'>hand-in-hand.</span>
  </p><p><span m='4767400'>But if we</span> <span m='4767770'>had the</span> <span
  m='4768100'>value network</span> <span m='4768463'>alone,</span> <span m='4769190'>when</span>
  <span m='4769330'>we're</span> <span m='4769520'>deciding</span> <span m='4770080'>on</span>
  <span m='4770190'>it</span> <span m='4770290'>the</span> <span m='4770480'>next
  move,</span> <span m='4770780'>we're going</span> <span m='4770880'>to</span> <span
  m='4770980'>have</span> <span m='4771050'>to</span> <span m='4771210'>evaluate</span>
  <span m='4771730'>every</span> <span m='4772010'>single</span> <span m='4772290'>move,</span>
  <span m='4772510'>which</span> <span m='4772750'>would</span> <span m='4773350'>take</span>
  <span m='4773560'>forever.</span> <span m='4774550'>And</span> <span m='4774700'>so,</span>
  <span m='4775010'>what</span> <span m='4775350'>the policy</span> <span m='4775540'>network</span>
  <span m='4775740'>does</span> <span m='4776010'>is</span> <span m='4776280'>project</span>
  <span m='4777860'>the</span> <span m='4778070'>best</span> <span m='4778200'>move</span>
  <span m='4778470'>with</span> <span m='4778995'>a</span> <span m='4779410'>probably</span>
  <span m='4779710'>distribution.</span> <span m='4781040'>And it</span> <span m='4781140'>narrows
  our</span> <span m='4781500'>search</span> <span m='4781810'>space.</span> </p><p><span
  m='4783110'>And</span> <span m='4783210'>then,</span> <span m='4783310'>if</span>
  <span m='4783420'>we</span> <span m='4783490'>had</span> <span m='4783610'>the</span>
  <span m='4783670'>policy</span> <span m='4784120'>network</span> <span m='4784565'>alone,</span>
  <span m='4785010'>we'd</span> <span m='4785200'>be</span> <span m='4785680'>unable
  to</span> <span m='4785830'>compare</span> <span m='4786280'>nodes</span> <span
  m='4786580'>in</span> <span m='4786670'>different</span> <span m='4786910'>parts</span>
  <span m='4787180'>of</span> <span m='4787270'>our</span> <span m='4787340'>tree.</span>
  <span m='4788366'>The</span> <span m='4788712'>policy</span> <span m='4789060'>network
  is</span> <span m='4789450'>able</span> <span m='4789580'>to</span> <span m='4789730'>tell</span>
  <span m='4789970'>us</span> <span m='4790450'>a</span> <span m='4791020'>distribution</span>
  <span m='4791390'>over</span> <span m='4791760'>which</span> <span m='4792040'>move
  we</span> <span m='4792250'>should</span> <span m='4792370'>take</span> <span m='4792610'>from</span>
  <span m='4792810'>a</span> <span m='4793000'>certain</span> <span m='4793340'>node.</span>
  <span m='4794230'>But</span> <span m='4794350'>then,</span> <span m='4795430'>if
  I</span> <span m='4795640'>ask it</span> <span m='4796000'>if</span> <span m='4796420'>I'm</span>
  <span m='4796600'>in</span> <span m='4796680'>a</span> <span m='4796750'>better</span>
  <span m='4796990'>position</span> <span m='4797350'>here</span> <span m='4797630'>than</span>
  <span m='4798130'>in</span> <span m='4798220'>some</span> <span m='4798400'>other</span>
  <span m='4798640'>place,</span> <span m='4799050'>it</span> <span m='4799150'>won't</span>
  <span m='4799330'>know.</span> </p><p><span m='4800310'>That's</span> <span m='4800530'>where</span>
  <span m='4800650'>the value</span> <span m='4800990'>network</span> <span m='4801270'>comes
  in.</span> <span m='4801390'>It will</span> <span m='4801765'>give us</span> <span
  m='4802140'>an</span> <span m='4803540'>estimated</span> <span m='4803890'>number</span>
  <span m='4805060'>of</span> <span m='4805250'>the</span> <span m='4805330'>value</span>
  <span m='4805730'>assigned</span> <span m='4806140'>and</span> <span m='4806290'>open
  an</span> <span m='4806370'>evaluation</span> <span m='4807400'>of</span> <span
  m='4807550'>that</span> <span m='4807730'>node.</span> <span m='4808570'>And</span>
  <span m='4808660'>then</span> <span m='4808930'>these</span> <span m='4809140'>values</span>
  <span m='4809560'>are</span> <span m='4809650'>later</span> <span m='4809950'>used</span>
  <span m='4810760'>to</span> <span m='4810970'>direct</span> <span m='4811420'>our</span>
  <span m='4811510'>tree</span> <span m='4811960'>searches</span> <span m='4812590'>based</span>
  <span m='4812860'>on</span> <span m='4813580'>updating</span> <span m='4814030'>the</span>
  <span m='4814420'>policy</span> <span m='4814990'>once</span> <span m='4815230'>it</span>
  <span m='4815530'>realizes,</span> <span m='4816360'>oh,</span> <span m='4816815'>I
  thought</span> <span m='4817130'>this would</span> <span m='4817230'>be a</span>
  <span m='4817670'>good</span> <span m='4817810'>path</span> <span m='4818060'>but</span>
  <span m='4818440'>the</span> <span m='4818530'>value</span> <span m='4819240'>is</span>
  <span m='4819470'>this,</span> <span m='4819830'>so</span> <span m='4820570'>update</span>
  <span m='4820790'>all</span> <span m='4821280'>that.</span> </p><p><span m='4823240'>Then</span>
  <span m='4823690'>why</span> <span m='4823850'>do</span> <span m='4823920'>we</span>
  <span m='4824000'>combine</span> <span m='4824255'>neural</span> <span m='4824510'>networks</span>
  <span m='4824660'>with</span> <span m='4824780'>MCTS?</span> <span m='4825440'>Remember,</span>
  <span m='4826660'>the</span> <span m='4826900'>policy</span> <span m='4827150'>network</span>
  <span m='4827220'>alone</span> <span m='4827500'>played</span> <span m='4827770'>against</span>
  <span m='4828340'>Pachi,</span> <span m='4829630'>which</span> <span m='4829810'>was</span>
  <span m='4829990'>purely</span> <span m='4830370'>MCTS,</span> <span m='4831000'>and</span>
  <span m='4831110'>it</span> <span m='4831190'>did</span> <span m='4831370'>pretty</span>
  <span m='4831610'>well.</span> <span m='4833000'>So</span> <span m='4833290'>how</span>
  <span m='4833470'>does</span> <span m='4833770'>MCTS</span> <span m='4834130'>improve</span>
  <span m='4834610'>our</span> <span m='4834740'>policy</span> <span m='4835070'>network?</span>
  <span m='4837220'>Remember,</span> <span m='4837760'>MCTS</span> <span m='4838930'>did</span>
  <span m='4839800'>win</span> <span m='4840720'>15%</span> <span m='4841130'>of</span>
  <span m='4841530'>those</span> <span m='4841770'>games.</span> <span m='4842055'>So</span>
  <span m='4842340'>already,</span> <span m='4842490'>that</span> <span m='4842690'>makes</span>
  <span m='4842950'>you</span> <span m='4843010'>think</span> <span m='4843160'>there's</span>
  <span m='4843700'>something</span> <span m='4844540'>there</span> <span m='4844900'>that</span>
  <span m='4845470'>maybe</span> <span m='4845650'>the</span> <span m='4846010'>policy
  network is</span> <span m='4846370'>missing.</span> </p><p><span m='4847145'>Also,</span>
  <span m='4847510'>the policy</span> <span m='4847950'>network is</span> <span m='4848080'>just</span>
  <span m='4848290'>a</span> <span m='4848350'>prediction.</span> <span m='4849220'>So</span>
  <span m='4849400'>by</span> <span m='4849610'>using</span> <span m='4849880'>this</span>
  <span m='4850060'>tree</span> <span m='4850330'>structure,</span> <span m='4851290'>we're</span>
  <span m='4851410'>able</span> <span m='4851680'>to</span> <span m='4852497'>use</span>
  <span m='4852924'>these</span> <span m='4853351'>Monte</span> <span m='4853780'>Carlo</span>
  <span m='4854050'>rollouts</span> <span m='4854650'>to</span> <span m='4854770'>adjust</span>
  <span m='4855160'>our</span> <span m='4855280'>policy</span> <span m='4857730'>to</span>
  <span m='4857850'>move</span> <span m='4858000'>towards</span> <span m='4858290'>nodes</span>
  <span m='4858480'>that</span> <span m='4858600'>are</span> <span m='4858870'>actually</span>
  <span m='4859280'>evaluated</span> <span m='4859590'>to</span> <span m='4859850'>be</span>
  <span m='4860267'>good.</span> </p><p><span m='4861520'>And</span> <span m='4861660'>then,</span>
  <span m='4862025'>how do</span> <span m='4862390'>neural</span> <span m='4862550'>networks</span>
  <span m='4862835'>improve</span> <span m='4863120'>MCTS?</span> <span m='4863960'>The</span>
  <span m='4864060'>point should</span> <span m='4864470'>probably</span> <span m='4864840'>be
  clear</span> <span m='4865050'>by</span> <span m='4865230'>now.</span> <span m='4866280'>We're</span>
  <span m='4866430'>able</span> <span m='4866550'>to</span> <span m='4866730'>more</span>
  <span m='4867420'>intelligently</span> <span m='4867990'>lead</span> <span m='4868440'>our</span>
  <span m='4868740'>tree</span> <span m='4869070'>exploration.</span> <span m='4869930'>Our</span>
  <span m='4870040'>simulations</span> <span m='4870840'>are</span> <span m='4871110'>more</span>
  <span m='4871320'>reflective</span> <span m='4871950'>of</span> <span m='4872100'>actual</span>
  <span m='4872520'>games.</span> <span m='4873420'>And</span> <span m='4873810'>the</span>
  <span m='4873930'>value</span> <span m='4874230'>network</span> <span m='4876440'>and</span>
  <span m='4876600'>our</span> <span m='4876660'>simulation</span> <span m='4876930'>value</span>
  <span m='4877530'>are</span> <span m='4877680'>complementary,</span> <span m='4878350'>which</span>
  <span m='4878430'>I've</span> <span m='4878940'>mentioned</span> <span m='4879240'>before.</span>
  </p><p><span m='4881400'>And</span> <span m='4881670'>just</span> <span m='4881850'>to</span>
  <span m='4882330'>highlight</span> <span m='4883170'>that,</span> <span m='4883800'>basically,</span>
  <span m='4884490'>the</span> <span m='4884580'>value</span> <span m='4884850'>network</span>
  <span m='4885150'>is</span> <span m='4885270'>going</span> <span m='4885480'>to</span>
  <span m='4885540'>give</span> <span m='4885690'>us</span> <span m='4885810'>a</span>
  <span m='4885850'>value</span> <span m='4886500'>that</span> <span m='4886680'>is</span>
  <span m='4887220'>reflective</span> <span m='4887910'>as</span> <span m='4888270'>if</span>
  <span m='4888630'>we've</span> <span m='4888990'>played the</span> <span m='4889080'>slow</span>
  <span m='4889400'>policy</span> <span m='4889660'>the</span> <span m='4889740'>whole</span>
  <span m='4889970'>time.</span> <span m='4890680'>And</span> <span m='4890990'>the</span>
  <span m='4892010'>simulation</span> <span m='4892560'>is</span> <span m='4892830'>if</span>
  <span m='4893030'>we</span> <span m='4893210'>used</span> <span m='4893360'>a</span>
  <span m='4893560'>faster</span> <span m='4893820'>policy.</span> <span m='4895170'>So</span>
  <span m='4895576'>they</span> <span m='4895982'>are</span> <span m='4896390'>complementary.</span>
  </p><p><span m='4898070'>And</span> <span m='4898420'>I know I'm</span> <span m='4898770'>over</span>
  <span m='4898940'>time.</span> <span m='4899710'>So</span> <span m='4900040'>I</span>
  <span m='4900100'>just</span> <span m='4900240'>wanted</span> <span m='4900520'>to</span>
  <span m='4900600'>skim</span> <span m='4900970'>through</span> <span m='4901300'>the</span>
  <span m='4901580'>stats</span> <span m='4901760'>real</span> <span m='4902040'>quick.</span>
  <span m='4904390'>Distributed</span> <span m='4904805'>AlphaGo</span> <span m='4905550'>won</span>
  <span m='4905910'>77%</span> <span m='4906850'>of</span> <span m='4907010'>the</span>
  <span m='4907270'>games against</span> <span m='4907520'>regular</span> <span m='4907915'>AlphaGo.</span>
  <span m='4909100'>So</span> <span m='4909510'>it's</span> <span m='4909800'>the
  only</span> <span m='4910170'>thing</span> <span m='4910250'>that beat</span> <span
  m='4910610'>regular</span> <span m='4910790'>AlphaGo.</span> </p><p><span m='4911080'>And</span>
  <span m='4911230'>then</span> <span m='4911440'>distributed</span> <span m='4911600'>AlphaGo</span>
  <span m='4912600'>won</span> <span m='4912910'>100%</span> <span m='4913620'>of
  the</span> <span m='4913940'>games</span> <span m='4914250'>against</span> <span
  m='4914560'>all</span> <span m='4914990'>these.</span> <span m='4915130'>In a</span>
  <span m='4915390'>rematch</span> <span m='4915650'>against</span> <span m='4915910'>Pachi,</span>
  <span m='4916396'>now that</span> <span m='4916882'>we've added</span> <span m='4917370'>MCTS</span>
  <span m='4917720'>to our</span> <span m='4918120'>policy network</span> <span m='4918320'>and
  we have</span> <span m='4918480'>our</span> <span m='4918570'>value</span> <span
  m='4918870'>network,</span> <span m='4919265'>we</span> <span m='4919530'>slaughtered</span>
  <span m='4920320'>Pachi</span> <span m='4920590'>100%.</span> </p><p><span m='4923170'>Then</span>
  <span m='4923550'>we</span> <span m='4923885'>decided to</span> <span m='4924220'>see
  how</span> <span m='4924380'>we</span> <span m='4924510'>fare against</span> <span
  m='4924910'>humans.</span> <span m='4925460'>And</span> <span m='4925700'>by</span>
  <span m='4925890'>we,</span> <span m='4926180'>I</span> <span m='4926280'>mean</span>
  <span m='4926470'>not</span> <span m='4926730'>me,</span> <span m='4927070'>I</span>
  <span m='4927190'>mean</span> <span m='4927445'>Google.</span> <span m='4928540'>And</span>
  <span m='4929060'>they</span> <span m='4929240'>won</span> <span m='4929620'>4</span>
  <span m='4929910'>to</span> <span m='4930020'>1.</span> <span m='4931190'>And</span>
  <span m='4931560'>Lee</span> <span m='4931970'>Sedol</span> <span m='4932380'>rating
  was</span> <span m='4932790'>3,520.</span> <span m='4934680'>Now</span> <span m='4935070'>AlphaGo's</span>
  <span m='4935730'>rating is</span> <span m='4936000'>estimated</span> <span m='4936180'>to
  be</span> <span m='4936620'>about</span> <span m='4937060'>3,586.</span> </p><p><span
  m='4937880'>So you're</span> <span m='4938400'>like,</span> <span m='4938580'>whoo,</span>
  <span m='4939045'>we beat</span> <span m='4939510'>the</span> <span m='4939810'>best
  dude.</span> <span m='4939960'>Except</span> <span m='4940110'>we didn't</span>
  <span m='4940400'>because there's</span> <span m='4940720'>another</span> <span
  m='4941210'>dude</span> <span m='4942180'>who</span> <span m='4942330'>has</span>
  <span m='4942750'>an</span> <span m='4942960'>even</span> <span m='4943170'>higher</span>
  <span m='4943500'>score,</span> <span m='4943980'>apparently,</span> <span m='4944850'>3,621.</span>
  </p><p><span m='4951320'>This</span> <span m='4952100'>should</span> <span m='4952250'>be
  the</span> <span m='4952560'>last part.</span> <span m='4952970'>Here's</span> <span
  m='4953290'>this</span> <span m='4953610'>timeline.</span> <span m='4954750'>Basically,</span>
  <span m='4955035'>tic-tac-toe,</span> <span m='4956040'>checkers</span> <span m='4956760'>were</span>
  <span m='4957220'>conquered</span> <span m='4957625'>in</span> <span m='4958030'>'50.</span>
  <span m='4959410'>About</span> <span m='4959640'>40</span> <span m='4959720'>years</span>
  <span m='4959880'>later,</span> <span m='4960210'>we</span> <span m='4960430'>conquered</span>
  <span m='4960740'>checkers,</span> <span m='4961475'>chess.</span> </p><p><span
  m='4962155'>Then</span> <span m='4962910'>we</span> <span m='4963210'>scroll</span>
  <span m='4963480'>down</span> <span m='4963760'>to</span> <span m='4963860'>2015,</span>
  <span m='4964850'>is</span> <span m='4965070'>when</span> <span m='4965800'>AlphaGo</span>
  <span m='4966150'>was able</span> <span m='4966495'>to beat</span> <span m='4966840'>Fan</span>
  <span m='4967140'>Hui,</span> <span m='4967710'>who</span> <span m='4968065'>was
  a</span> <span m='4968420'>two-dan</span> <span m='4968950'>player,</span> <span
  m='4969270'>which</span> <span m='4969470'>is</span> <span m='4969960'>considered</span>
  <span m='4970740'>lower</span> <span m='4971010'>down</span> <span m='4971340'>in</span>
  <span m='4971430'>the</span> <span m='4971550'>tier</span> <span m='4971940'>of</span>
  <span m='4972570'>professional</span> <span m='4973680'>Go.</span> <span m='4974425'>But
  then,</span> <span m='4974780'>Lee Sedol</span> <span m='4975070'>was a</span> <span
  m='4975460'>nine-dan</span> <span m='4975720'>player.</span> <span m='4976470'>And</span>
  <span m='4976770'>he</span> <span m='4977040'>was</span> <span m='4977160'>able
  to</span> <span m='4977280'>beat</span> <span m='4977630'>him</span> <span m='4978070'>literally</span>
  <span m='4978360'>last</span> <span m='4978630'>month.</span> </p><p><span m='4980189'>PROFESSOR
  WILLIAMS:</span> <span m='4980410'>So</span> <span m='4980632'>good</span> <span
  m='4981075'>job.</span> </p><p><span m='4981520'>PROFESSOR 3:</span> <span m='4981585'>We're</span>
  <span m='4981650'>done.</span> </p><p><span m='4981950'>[APPLAUSE]</span> </p>
type: course
uid: 982375a3ba05137bf0a380fd51dce9ce

---
None