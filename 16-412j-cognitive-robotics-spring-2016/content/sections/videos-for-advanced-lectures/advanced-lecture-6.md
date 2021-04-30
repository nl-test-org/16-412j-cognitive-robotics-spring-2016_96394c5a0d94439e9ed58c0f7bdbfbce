---
about_this_resource_text: ''
course_id: 16-412j-cognitive-robotics-spring-2016
embedded_media:
- id: Video-YouTube-Stream
  media_location: Tmhe33f9mWA
  parent_uid: 0ac9fa7ff5c52442a6306ad9559fb84c
  title: Video-YouTube-Stream
  type: Video
  uid: c7c48c7b04a3ed42a5501b83a871f425
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/Tmhe33f9mWA/default.jpg
  parent_uid: 0ac9fa7ff5c52442a6306ad9559fb84c
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 57690976a5c1de659bfdf4ace1475a8d
- id: 3Play-3PlayYouTubeid-MP4
  media_location: Tmhe33f9mWA
  parent_uid: 0ac9fa7ff5c52442a6306ad9559fb84c
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: d64ab826c40d8d6492e00c93a00d8f37
- id: Tmhe33f9mWA.srt
  parent_uid: 0ac9fa7ff5c52442a6306ad9559fb84c
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-412j-cognitive-robotics-spring-2016/videos-for-advanced-lectures/advanced-lecture-6/Tmhe33f9mWA.srt
  title: 3play caption file
  type: null
  uid: 41cca051dde2821928ef8934d14884ff
- id: Tmhe33f9mWA.pdf
  parent_uid: 0ac9fa7ff5c52442a6306ad9559fb84c
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-412j-cognitive-robotics-spring-2016/videos-for-advanced-lectures/advanced-lecture-6/Tmhe33f9mWA.pdf
  title: 3play pdf file
  type: null
  uid: 4593271d8df55a38505878bda2b43e72
- id: Caption-3Play YouTube id-SRT
  parent_uid: 0ac9fa7ff5c52442a6306ad9559fb84c
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: d80a2849729617b4a8676a6edc597a2a
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 0ac9fa7ff5c52442a6306ad9559fb84c
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 8c9faa44afa5435ae72484d3580c5cb5
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT16.412S16/MIT16_412S16_Lec6_Temporal_Logic_300k.mp4
  parent_uid: 0ac9fa7ff5c52442a6306ad9559fb84c
  title: Video-Internet Archive-MP4
  type: Video
  uid: a2b704a13b024d4dca9af3fd9322d5a1
inline_embed_id: 58766699advancedlecture691292275
layout: video
order_index: null
parent_uid: d55ba1f51999fdb2f0dba10fa56076dc
related_resources_text: ''
short_url: advanced-lecture-6
technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-412j-cognitive-robotics-spring-2016/videos-for-advanced-lectures/advanced-lecture-6
template_type: Tabbed
title: 'Advanced Lecture 6: Planning with Temporal Logic'
transcript: <p><span m='1580'>The</span> <span m='1670'>following</span> <span m='2120'>content</span>
  <span m='2600'>is</span> <span m='2720'>provided</span> <span m='3170'>under</span>
  <span m='3380'>a</span> <span m='3470'>Creative</span> <span m='3920'>Commons</span>
  <span m='4310'>license.</span> <span m='5340'>Your</span> <span m='5420'>support</span>
  <span m='5900'>will</span> <span m='6050'>help</span> <span m='6320'>MIT</span>
  <span m='6800'>OpenCourseWare</span> <span m='7550'>continue</span> <span m='8029'>to</span>
  <span m='8180'>offer</span> <span m='8510'>high-quality</span> <span m='9200'>educational</span>
  <span m='9860'>resources</span> <span m='10430'>for</span> <span m='10580'>free.</span>
  <span m='11640'>To</span> <span m='11740'>make</span> <span m='11840'>a</span> <span
  m='11900'>donation</span> <span m='12650'>or</span> <span m='12830'>to</span> <span
  m='12950'>view</span> <span m='13160'>additional</span> <span m='13550'>materials</span>
  <span m='14180'>from</span> <span m='14360'>hundreds</span> <span m='14690'>of</span>
  <span m='14810'>MIT</span> <span m='15170'>courses</span> <span m='16470'>visit</span>
  <span m='16670'>MIT</span> <span m='17180'>OpenCourseWare</span> <span m='18110'>at</span>
  <span m='18370'>ocw.MIT.edu.</span> </p><p><span m='22118'>PROFESSOR:</span> <span
  m='22331'>Self-driving</span> <span m='22544'>cars are</span> <span m='22970'>pretty
  cool.</span> <span m='23330'>It's</span> <span m='23690'>pretty hot</span> <span
  m='24080'>nowadays,</span> <span m='24420'>so</span> <span m='25175'>we're</span>
  <span m='25590'>going to</span> <span m='25720'>use</span> <span m='25890'>this
  as an</span> <span m='26280'>example.</span> <span m='27200'>And</span> <span m='27590'>in</span>
  <span m='27680'>the</span> <span m='27770'>past</span> <span m='28400'>we</span>
  <span m='28510'>have</span> <span m='28660'>seen</span> <span m='29150'>how</span>
  <span m='29990'>we</span> <span m='30110'>can</span> <span m='30290'>give</span>
  <span m='31130'>an</span> <span m='31490'>autonomous</span> <span m='31850'>vehicle</span>
  <span m='32500'>a</span> <span m='32775'>goal--</span> <span m='33050'>some</span>
  <span m='33305'>condition</span> <span m='33910'>we</span> <span m='34040'>want</span>
  <span m='34210'>it to</span> <span m='34370'>reach.</span> <span m='35510'>For</span>
  <span m='35630'>example,</span> <span m='36180'>we</span> <span m='36280'>might</span>
  <span m='36310'>have</span> <span m='36540'>a car</span> <span m='36880'>that wants
  to pick up</span> <span m='37260'>some</span> <span m='37490'>passengers</span>
  <span m='37775'>along</span> <span m='38210'>the</span> <span m='38270'>way,</span>
  <span m='38600'>get</span> <span m='38960'>to</span> <span m='39050'>some</span>
  <span m='39230'>destination,</span> <span m='41290'>and</span> <span m='41650'>maybe</span>
  <span m='42060'>navigate</span> <span m='42420'>some</span> <span m='42710'>worlds.</span>
  </p><p><span m='44300'>But</span> <span m='44870'>let's</span> <span m='45050'>consider</span>
  <span m='45690'>that</span> <span m='46260'>for</span> <span m='46580'>something</span>
  <span m='46800'>like a</span> <span m='47010'>self-driving</span> <span m='47440'>car,</span>
  <span m='47840'>we</span> <span m='48230'>also have</span> <span m='49010'>a</span>
  <span m='49090'>number</span> <span m='49370'>of</span> <span m='49550'>other</span>
  <span m='50270'>goals</span> <span m='50870'>or</span> <span m='51020'>requirements</span>
  <span m='51950'>that</span> <span m='52040'>are</span> <span m='52130'>sort</span>
  <span m='52310'>of</span> <span m='52550'>implicit</span> <span m='52940'>along</span>
  <span m='53130'>the</span> <span m='53210'>way,</span> <span m='53540'>in</span>
  <span m='53720'>that</span> <span m='54590'>we</span> <span m='54770'>want</span>
  <span m='54950'>our</span> <span m='55170'>self-driving</span> <span m='55700'>car</span>
  <span m='56030'>to</span> <span m='56610'>obey</span> <span m='57070'>the rules
  of the</span> <span m='57535'>road as it's</span> <span m='58000'>driving.</span>
  <span m='58800'>And</span> <span m='59150'>these</span> <span m='59490'>aren't</span>
  <span m='59730'>just</span> <span m='60790'>goal</span> <span m='61100'>conditions</span>
  <span m='61695'>which</span> <span m='61950'>is</span> <span m='62330'>a</span>
  <span m='62510'>sort</span> <span m='62750'>of</span> <span m='63630'>single</span>
  <span m='64030'>goal</span> <span m='64239'>that</span> <span m='64370'>you're</span>
  <span m='64459'>trying</span> <span m='64610'>to</span> <span m='64730'>reach,</span>
  <span m='65000'>but</span> <span m='65150'>these are</span> <span m='65370'>sort</span>
  <span m='65550'>of</span> <span m='65680'>goals that</span> <span m='65890'>you're</span>
  <span m='66190'>trying</span> <span m='66370'>to</span> <span m='66680'>maintain</span>
  <span m='67050'>throughout the path</span> <span m='67498'>that you're</span> <span
  m='67946'>traveling.</span> </p><p><span m='71090'>So</span> <span m='71630'>one</span>
  <span m='71810'>example</span> <span m='72220'>of</span> <span m='72270'>this</span>
  <span m='73670'>is</span> <span m='74990'>a</span> <span m='75500'>traffic</span>
  <span m='75850'>light.</span> <span m='77000'>So</span> <span m='77480'>maybe you</span>
  <span m='77750'>guys</span> <span m='78110'>can help me</span> <span m='78290'>out</span>
  <span m='78420'>with</span> <span m='78620'>this.</span> <span m='79860'>Just</span>
  <span m='80100'>in</span> <span m='80210'>plain</span> <span m='80420'>English,</span>
  <span m='81440'>how</span> <span m='81590'>would</span> <span m='81740'>you</span>
  <span m='81920'>describe</span> <span m='83990'>the</span> <span m='84080'>rules</span>
  <span m='84560'>of</span> <span m='84650'>how</span> <span m='84770'>you</span>
  <span m='84910'>would want a</span> <span m='85110'>car</span> <span m='85360'>to
  behave</span> <span m='86430'>when</span> <span m='86620'>it comes</span> <span
  m='87000'>across</span> <span m='87380'>a</span> <span m='87590'>traffic</span>
  <span m='88040'>light?</span> <span m='90132'>Anything?</span> <span m='90610'>It's</span>
  <span m='91090'>very</span> <span m='91270'>simple.</span> <span m='91890'>Yes?</span>
  </p><p><span m='92165'>AUDIENCE:</span> <span m='92302'>Slow</span> <span m='92440'>down</span>
  <span m='92680'>when you</span> <span m='93110'>see</span> <span m='93540'>yellow,</span>
  <span m='93810'>stop</span> <span m='94080'>when you</span> <span m='94550'>see</span>
  <span m='95020'>red,</span> <span m='95490'>go if you</span> <span m='95960'>see</span>
  <span m='96430'>green.</span> </p><p><span m='97840'>PROFESSOR:</span> <span m='97970'>Yeah.</span>
  <span m='98100'>So</span> <span m='100210'>pretty</span> <span m='100440'>much</span>
  <span m='101100'>stop if</span> <span m='101520'>you</span> <span m='101650'>see</span>
  <span m='101830'>red,</span> <span m='102100'>go if you</span> <span m='102430'>see</span>
  <span m='102760'>green,</span> <span m='103600'>and</span> <span m='104493'>specifically,</span>
  <span m='104936'>if</span> <span m='105380'>you</span> <span m='105490'>see</span>
  <span m='105700'>red</span> <span m='105940'>and</span> <span m='106030'>you</span>
  <span m='106120'>stop,</span> <span m='106950'>you're going to</span> <span m='107130'>want</span>
  <span m='107290'>to</span> <span m='107350'>stop</span> <span m='107930'>until</span>
  <span m='108530'>you see the</span> <span m='108760'>green,</span> <span m='108950'>at</span>
  <span m='109230'>which</span> <span m='109450'>point</span> <span m='110140'>that</span>
  <span m='110350'>sort</span> <span m='110560'>of</span> <span m='110980'>condition</span>
  <span m='111410'>that</span> <span m='111490'>you're</span> <span m='111560'>stopping</span>
  <span m='112700'>goes</span> <span m='113070'>away,</span> <span m='113440'>and
  you're able</span> <span m='113921'>to</span> <span m='114402'>move on.</span> </p><p><span
  m='121140'>And in</span> <span m='121240'>addition</span> <span m='121910'>to</span>
  <span m='122350'>things</span> <span m='122590'>like</span> <span m='122980'>obeying</span>
  <span m='123310'>traffic</span> <span m='123640'>lights,</span> <span m='124660'>there</span>
  <span m='124720'>might</span> <span m='124840'>also</span> <span m='125080'>be</span>
  <span m='125260'>some other rules</span> <span m='125740'>of the road</span> <span
  m='126020'>that</span> <span m='126150'>we</span> <span m='126220'>want</span> <span
  m='126340'>to</span> <span m='126400'>follow.</span> <span m='127970'>For</span>
  <span m='128070'>example,</span> <span m='128710'>we</span> <span m='128810'>might</span>
  <span m='128830'>want</span> <span m='128949'>to</span> <span m='129100'>always</span>
  <span m='129580'>stay</span> <span m='129970'>within</span> <span m='130720'>the</span>
  <span m='130780'>speed</span> <span m='131080'>limit.</span> <span m='133120'>And</span>
  <span m='133240'>then</span> <span m='133390'>there</span> <span m='133460'>might</span>
  <span m='133620'>also</span> <span m='133700'>be some</span> <span m='134090'>other</span>
  <span m='134340'>practical</span> <span m='134710'>conditions</span> <span m='135340'>of</span>
  <span m='135610'>driving</span> <span m='135880'>down</span> <span m='136120'>the</span>
  <span m='136210'>road,</span> <span m='137980'>which</span> <span m='138070'>is</span>
  <span m='138360'>that at</span> <span m='138570'>some</span> <span m='138820'>point</span>
  <span m='139000'>we're</span> <span m='139090'>going</span> <span m='139210'>to</span>
  <span m='139270'>need</span> <span m='139390'>to</span> <span m='139450'>refuel.</span>
  </p><p><span m='140275'>And if</span> <span m='140530'>we consider</span> <span
  m='140900'>a</span> <span m='141210'>car</span> <span m='141580'>that might be</span>
  <span m='141860'>driving</span> <span m='142180'>for</span> <span m='142340'>a</span>
  <span m='142390'>really</span> <span m='142660'>long</span> <span m='142810'>time,</span>
  <span m='144440'>one</span> <span m='145880'>logical</span> <span m='146280'>statement</span>
  <span m='146650'>we</span> <span m='146740'>could</span> <span m='146860'>say</span>
  <span m='147310'>about</span> <span m='148270'>the</span> <span m='148750'>path</span>
  <span m='149080'>that</span> <span m='149170'>this</span> <span m='149320'>car</span>
  <span m='149570'>takes,</span> <span m='149890'>and the</span> <span m='150320'>sequence</span>
  <span m='150780'>of</span> <span m='151000'>states that it</span> <span m='151380'>goes</span>
  <span m='151630'>through</span> <span m='152350'>is</span> <span m='152500'>that</span>
  <span m='153220'>at</span> <span m='153310'>every</span> <span m='153520'>point</span>
  <span m='153730'>in</span> <span m='153820'>time</span> <span m='154900'>we</span>
  <span m='155020'>want</span> <span m='155230'>the</span> <span m='155320'>plan</span>
  <span m='155800'>to</span> <span m='155950'>have</span> <span m='156970'>some</span>
  <span m='157240'>future</span> <span m='157580'>state</span> <span m='157960'>when</span>
  <span m='158170'>we</span> <span m='158290'>are</span> <span m='158470'>going</span>
  <span m='158720'>to</span> <span m='158880'>visit</span> <span m='159180'>a</span>
  <span m='159310'>gas station.</span> <span m='160550'>So</span> <span m='161080'>this</span>
  <span m='161230'>isn't</span> <span m='161380'>just</span> <span m='161820'>a</span>
  <span m='161910'>single goal</span> <span m='162270'>that</span> <span m='162360'>we're</span>
  <span m='162490'>trying</span> <span m='162670'>to</span> <span m='162730'>reach,</span>
  <span m='162990'>but</span> <span m='163130'>over</span> <span m='163900'>a</span>
  <span m='163960'>very</span> <span m='164170'>long</span> <span m='164350'>time,</span>
  <span m='164930'>even</span> <span m='166030'>if</span> <span m='166150'>we</span>
  <span m='166270'>consider</span> <span m='166760'>the car</span> <span m='167250'>to
  be driving</span> <span m='167390'>an infinite</span> <span m='167720'>amount of</span>
  <span m='168130'>time,</span> <span m='169270'>at</span> <span m='169720'>every</span>
  <span m='169990'>point</span> <span m='170260'>in the</span> <span m='170320'>time,</span>
  <span m='171190'>we're</span> <span m='171340'>going</span> <span m='171680'>to</span>
  <span m='171820'>be</span> <span m='172000'>thinking</span> <span m='172270'>ahead</span>
  <span m='172760'>that</span> <span m='173140'>there's</span> <span m='173340'>going
  to</span> <span m='173500'>be</span> <span m='173660'>some</span> <span m='173910'>time</span>
  <span m='174370'>when</span> <span m='174650'>we</span> <span m='174760'>reach</span>
  <span m='175620'>a</span> <span m='175690'>gas</span> <span m='175900'>station</span>
  <span m='176260'>and refuel.</span> </p><p><span m='181300'>So</span> <span m='182770'>these</span>
  <span m='183010'>types</span> <span m='183310'>of</span> <span m='183400'>conditions,</span>
  <span m='184430'>things</span> <span m='184600'>like</span> <span m='185240'>staying
  at</span> <span m='185630'>a</span> <span m='185710'>red</span> <span m='185920'>light</span>
  <span m='186100'>until it</span> <span m='186420'>turns</span> <span m='186740'>green,</span>
  <span m='187750'>always</span> <span m='188040'>staying within</span> <span m='188490'>a
  certain</span> <span m='188840'>speed</span> <span m='189220'>limit,</span> <span
  m='189980'>or</span> <span m='190620'>always</span> <span m='190940'>having</span>
  <span m='191170'>some</span> <span m='191470'>path</span> <span m='191950'>in</span>
  <span m='192070'>the</span> <span m='192150'>future--</span> <span m='192520'>some
  state in</span> <span m='192740'>the</span> <span m='193090'>future</span> <span
  m='193560'>when</span> <span m='193770'>we</span> <span m='193870'>reach</span>
  <span m='194020'>a</span> <span m='194130'>gas</span> <span m='194350'>station,</span>
  <span m='194990'>are</span> <span m='195160'>things that</span> <span m='195450'>we
  can</span> <span m='195650'>express</span> <span m='196240'>with</span> <span m='196510'>a</span>
  <span m='196600'>type</span> <span m='196790'>of</span> <span m='196850'>logic</span>
  <span m='197250'>called</span> <span m='197440'>temporal</span> <span m='197790'>logic.</span>
  </p><p><span m='199010'>And</span> <span m='199320'>there are two things</span>
  <span m='199670'>that</span> <span m='200140'>we</span> <span m='200290'>hope</span>
  <span m='200560'>you're</span> <span m='200650'>going</span> <span m='200770'>to</span>
  <span m='200830'>be</span> <span m='200920'>able</span> <span m='201070'>to</span>
  <span m='201160'>do</span> <span m='201400'>by the</span> <span m='201630'>time
  you</span> <span m='201860'>leave</span> <span m='202060'>this</span> <span m='202210'>lecture.</span>
  <span m='202985'>The</span> <span m='203410'>first</span> <span m='203740'>is be
  able</span> <span m='204210'>to</span> <span m='204420'>model</span> <span m='205660'>these</span>
  <span m='205810'>temporally</span> <span m='206350'>extended</span> <span m='206890'>goals</span>
  <span m='207820'>using</span> <span m='208390'>a</span> <span m='208480'>specific</span>
  <span m='208900'>type</span> <span m='209140'>of</span> <span m='209200'>temporal</span>
  <span m='209500'>logic</span> <span m='209850'>called</span> <span m='210100'>Linear</span>
  <span m='210310'>Temporal</span> <span m='210910'>Logic,</span> <span m='211140'>or</span>
  <span m='211500'>LTL.</span> <span m='214110'>And</span> <span m='214540'>secondly,</span>
  <span m='215630'>we're</span> <span m='215650'>going</span> <span m='215770'>to</span>
  <span m='215830'>hope</span> <span m='216020'>that</span> <span m='216130'>you'll</span>
  <span m='216250'>be</span> <span m='216340'>able</span> <span m='216520'>to</span>
  <span m='217150'>actually</span> <span m='217490'>apply</span> <span m='217730'>this
  to</span> <span m='217990'>planning,</span> <span m='218740'>create</span> <span
  m='219100'>plans</span> <span m='219490'>with</span> <span m='219640'>these</span>
  <span m='219850'>temporally</span> <span m='220250'>extended</span> <span m='220540'>goals,</span>
  <span m='221440'>and</span> <span m='221830'>in</span> <span m='222295'>addition</span>
  <span m='223390'>just</span> <span m='223840'>sort</span> <span m='224020'>of</span>
  <span m='224110'>this</span> <span m='224260'>regular</span> <span m='224830'>planning</span>
  <span m='225130'>we've</span> <span m='225220'>been</span> <span m='225370'>dealing</span>
  <span m='225610'>with,</span> <span m='225910'>actually</span> <span m='226480'>incorporating</span>
  <span m='227190'>this idea</span> <span m='227560'>of</span> <span m='227800'>preferences</span>
  <span m='228790'>into</span> <span m='229210'>your</span> <span m='229330'>plans.</span>
  <span m='230320'>So a</span> <span m='230670'>preference</span> <span m='231850'>basically</span>
  <span m='232520'>is</span> <span m='233440'>not</span> <span m='233590'>a</span>
  <span m='234160'>required</span> <span m='234730'>condition,</span> <span m='235630'>but</span>
  <span m='235980'>a</span> <span m='236020'>desired</span> <span m='236590'>condition</span>
  <span m='238092'>that</span> <span m='238560'>you</span> <span m='238720'>can</span>
  <span m='238900'>use</span> <span m='239140'>to</span> <span m='239230'>select</span>
  <span m='240250'>between</span> <span m='241180'>alternative</span> <span m='241610'>paths.</span>
  <span m='242690'>So</span> <span m='243320'>you</span> <span m='243370'>know,</span>
  <span m='243700'>you</span> <span m='243790'>might</span> <span m='243970'>have</span>
  <span m='244090'>many</span> <span m='244360'>different</span> <span m='244630'>ways</span>
  <span m='245000'>that you</span> <span m='245090'>could</span> <span m='245230'>reach</span>
  <span m='245410'>your</span> <span m='245500'>goal,</span> <span m='246220'>but</span>
  <span m='246700'>we</span> <span m='246820'>can</span> <span m='246970'>use</span>
  <span m='247230'>some</span> <span m='247390'>of</span> <span m='247510'>these</span>
  <span m='247780'>temporally</span> <span m='248065'>extended</span> <span m='248620'>goals,</span>
  <span m='249100'>like</span> <span m='249820'>maybe</span> <span m='250180'>you</span>
  <span m='250330'>prefer</span> <span m='250700'>to</span> <span m='250840'>break</span>
  <span m='251160'>as</span> <span m='251300'>few</span> <span m='252210'>of</span>
  <span m='252390'>the</span> <span m='252510'>rules</span> <span m='252830'>of the
  road</span> <span m='253080'>as you</span> <span m='253482'>can,</span> <span m='254690'>and</span>
  <span m='255070'>you</span> <span m='255220'>can</span> <span m='255340'>use</span>
  <span m='255550'>those</span> <span m='256340'>a</span> <span m='256740'>preferences</span>
  <span m='257440'>to</span> <span m='258209'>choose</span> <span m='258459'>between</span>
  <span m='258850'>plans.</span> </p><p><span m='261315'>So</span> <span m='261810'>just</span>
  <span m='261950'>as</span> <span m='262100'>an outline,</span> <span m='262950'>first
  we're</span> <span m='263100'>just</span> <span m='263190'>going</span> <span m='263330'>to</span>
  <span m='263500'>do a</span> <span m='263780'>little</span> <span m='264060'>introduction</span>
  <span m='264520'>to</span> <span m='264930'>linear</span> <span m='265020'>temporal</span>
  <span m='265350'>logic.</span> <span m='266620'>We're going to</span> <span m='266890'>talk</span>
  <span m='267040'>about</span> <span m='267380'>what</span> <span m='268020'>this</span>
  <span m='268200'>is--</span> <span m='268470'>what</span> <span m='268680'>LTL</span>
  <span m='268900'>is,</span> <span m='269690'>why</span> <span m='269880'>we</span>
  <span m='269970'>want</span> <span m='270090'>to</span> <span m='270150'>use it,</span>
  <span m='270815'>and</span> <span m='271240'>we're going to</span> <span m='271665'>go</span>
  <span m='272090'>through the</span> <span m='272210'>syntax</span> <span m='272750'>and</span>
  <span m='272840'>the</span> <span m='273080'>semantics</span> <span m='273430'>of</span>
  <span m='274090'>different</span> <span m='274390'>LTL</span> <span m='274720'>operators.</span>
  <span m='276190'>Then we're going</span> <span m='276680'>to walk you</span> <span
  m='277170'>through</span> <span m='277480'>some example</span> <span m='277795'>LTL</span>
  <span m='278460'>problems,</span> <span m='279350'>and</span> <span m='279450'>actually</span>
  <span m='279660'>talk about</span> <span m='280380'>complications</span> <span m='281055'>to</span>
  <span m='281310'>plans--</span> <span m='281490'>how</span> <span m='281780'>you</span>
  <span m='281950'>create</span> <span m='282220'>plans</span> <span m='282700'>with</span>
  <span m='283285'>these</span> <span m='283630'>linear</span> <span m='283840'>temporal</span>
  <span m='284560'>logic</span> <span m='285025'>and</span> <span m='285490'>temporal</span>
  <span m='286320'>goals.</span> <span m='287160'>Finally</span> <span m='287590'>we're</span>
  <span m='288020'>going to</span> <span m='288170'>incorporate</span> <span m='288660'>preferences</span>
  <span m='288960'>into</span> <span m='289410'>this,</span> <span m='289740'>talk
  about</span> <span m='290160'>how</span> <span m='290260'>you</span> <span m='290370'>express</span>
  <span m='290790'>preferences,</span> <span m='291700'>and</span> <span m='291990'>specifically</span>
  <span m='292240'>talk about</span> <span m='292350'>a</span> <span m='292620'>language</span>
  <span m='292930'>called</span> <span m='293110'>LPP</span> <span m='293790'>that</span>
  <span m='293950'>allows you to</span> <span m='294350'>plan</span> <span m='295100'>with</span>
  <span m='295530'>temporal</span> <span m='295850'>logic</span> <span m='296020'>and</span>
  <span m='296240'>preferences.</span> </p><p><span m='300650'>So</span> <span m='300930'>now</span>
  <span m='301180'>for</span> <span m='301310'>the</span> <span m='302280'>introduction</span>
  <span m='302840'>to</span> <span m='303460'>linear</span> <span m='303610'>temporal</span>
  <span m='303840'>logic.</span> <span m='305420'>Temporal</span> <span m='305610'>logic</span>
  <span m='306000'>at its</span> <span m='306370'>core</span> <span m='306700'>is
  a</span> <span m='306970'>formalism</span> <span m='307720'>for</span> <span m='307880'>specifying</span>
  <span m='308390'>properties</span> <span m='308840'>of</span> <span m='308920'>a</span>
  <span m='308990'>system</span> <span m='309410'>that</span> <span m='309530'>vary</span>
  <span m='309800'>with</span> <span m='309890'>time.</span> <span m='310780'>So</span>
  <span m='310910'>these</span> <span m='311120'>aren't</span> <span m='311320'>just</span>
  <span m='312050'>conditions</span> <span m='313280'>that</span> <span m='313640'>are</span>
  <span m='313760'>true</span> <span m='314090'>at</span> <span m='314220'>single</span>
  <span m='314540'>state,</span> <span m='315170'>which</span> <span m='315320'>is</span>
  <span m='315410'>what</span> <span m='315490'>we've</span> <span m='315660'>mostly</span>
  <span m='315880'>been</span> <span m='316040'>dealing</span> <span m='316330'>with</span>
  <span m='316880'>prepositional</span> <span m='317490'>logic.</span> <span m='317950'>Right,</span>
  <span m='318410'>so</span> <span m='318870'>we've been</span> <span m='319260'>saying</span>
  <span m='319520'>things</span> <span m='319940'>like,</span> <span m='320910'>condition</span>
  <span m='322096'>A</span> <span m='322460'>and</span> <span m='322940'>B,</span>
  <span m='324320'>but</span> <span m='324470'>not</span> <span m='324680'>C,</span>
  <span m='325130'>are</span> <span m='325300'>true</span> <span m='325560'>at a given</span>
  <span m='325790'>state,</span> <span m='326410'>and</span> <span m='326770'>that's</span>
  <span m='327080'>prepositional</span> <span m='327630'>logic.</span> <span m='328350'>Temporal
  logic</span> <span m='328820'>is</span> <span m='328880'>sort</span> <span m='329040'>of</span>
  <span m='329110'>a</span> <span m='329360'>layer</span> <span m='329660'>on</span>
  <span m='329720'>top</span> <span m='329960'>of</span> <span m='330020'>that,</span>
  <span m='330410'>when</span> <span m='330490'>we're</span> <span m='330590'>dealing</span>
  <span m='330800'>not</span> <span m='330950'>just</span> <span m='331130'>with</span>
  <span m='331430'>what's</span> <span m='331700'>true at a</span> <span m='331985'>single</span>
  <span m='332270'>state,</span> <span m='332750'>but</span> <span m='332840'>actually</span>
  <span m='333060'>extending</span> <span m='333650'>over</span> <span m='333860'>time</span>
  <span m='334690'>as</span> <span m='334960'>the</span> <span m='335030'>system</span>
  <span m='335420'>moves through a</span> <span m='335660'>sequence</span> <span m='336090'>of
  states,</span> <span m='337050'>and</span> <span m='337370'>expressing</span> <span
  m='337790'>properties</span> <span m='338360'>on</span> <span m='338540'>a</span>
  <span m='338660'>temporal</span> <span m='339030'>level.</span> </p><p><span m='342990'>So</span>
  <span m='343510'>you</span> <span m='343690'>might</span> <span m='343900'>have</span>
  <span m='344020'>a</span> <span m='344080'>system</span> <span m='344750'>that</span>
  <span m='344920'>can be</span> <span m='345040'>represented</span> <span m='345430'>as</span>
  <span m='345750'>a</span> <span m='345830'>state</span> <span m='346200'>machine,</span>
  <span m='347524'>and a</span> <span m='347966'>[INAUDIBLE],</span> <span m='348850'>and</span>
  <span m='349720'>it</span> <span m='350360'>can</span> <span m='350740'>go</span>
  <span m='351000'>through</span> <span m='351370'>a</span> <span m='351430'>sequence</span>
  <span m='352270'>of</span> <span m='352550'>different</span> <span m='352900'>states.</span>
  <span m='354970'>And</span> <span m='355330'>while</span> <span m='355820'>you might
  be able to</span> <span m='356310'>represent</span> <span m='356580'>the</span>
  <span m='356850'>whole</span> <span m='356980'>system</span> <span m='357310'>like</span>
  <span m='357460'>this,</span> <span m='358000'>if</span> <span m='358150'>we</span>
  <span m='358240'>actually</span> <span m='358540'>execute</span> <span m='358990'>the</span>
  <span m='359080'>system</span> <span m='359950'>we're</span> <span m='360130'>going
  to</span> <span m='360180'>get</span> <span m='360700'>one</span> <span m='361400'>path</span>
  <span m='361940'>through</span> <span m='362150'>the</span> <span m='362300'>system.</span>
  <span m='363045'>And</span> <span m='364150'>that's</span> <span m='364400'>often</span>
  <span m='364740'>called</span> <span m='364840'>a</span> <span m='364930'>trace</span>
  <span m='365590'>of</span> <span m='365680'>the</span> <span m='365740'>system,</span>
  <span m='366220'>and you</span> <span m='366620'>can</span> <span m='366800'>also</span>
  <span m='366950'>think of it as</span> <span m='367200'>a</span> <span m='367370'>timeline</span>
  <span m='367840'>of</span> <span m='367930'>the</span> <span m='367990'>system.</span>
  </p><p><span m='369040'>So</span> <span m='369620'>one</span> <span m='369780'>example</span>
  <span m='370150'>timeline</span> <span m='370460'>of</span> <span m='370700'>this</span>
  <span m='370810'>system</span> <span m='371410'>is</span> <span m='372065'>it might</span>
  <span m='372360'>start in</span> <span m='372650'>state</span> <span m='373065'>A,
  and then</span> <span m='373480'>go</span> <span m='373610'>to</span> <span m='373690'>state</span>
  <span m='373970'>C,</span> <span m='375131'>and then go</span> <span m='375520'>to</span>
  <span m='375760'>D,</span> <span m='376025'>and</span> <span m='376290'>keep</span>
  <span m='376500'>looping</span> <span m='376780'>around in</span> <span m='377150'>D</span>
  <span m='377340'>forever.</span> <span m='378026'>So that's</span> <span m='378370'>one</span>
  <span m='378670'>trace, or</span> <span m='379170'>one</span> <span m='379360'>timeline</span>
  <span m='379610'>of</span> <span m='380085'>the system,</span> <span m='380560'>and</span>
  <span m='380830'>that's really</span> <span m='381050'>just a</span> <span m='381360'>sequence</span>
  <span m='381480'>of</span> <span m='381980'>states</span> <span m='382330'>that
  it</span> <span m='382680'>goes</span> <span m='382870'>through.</span> <span m='385932'>And</span>
  <span m='386420'>in the</span> <span m='386510'>past</span> <span m='386770'>we've
  seen</span> <span m='387030'>these</span> <span m='387140'>in</span> <span m='387190'>some
  of</span> <span m='387420'>the</span> <span m='387940'>problem</span> <span m='388210'>sets.</span>
  <span m='388720'>For</span> <span m='388780'>example</span> <span m='389820'>when</span>
  <span m='390090'>we were</span> <span m='390250'>modeling</span> <span m='391930'>the</span>
  <span m='392470'>warp</span> <span m='392720'>reactor,</span> <span m='394190'>we</span>
  <span m='394560'>had</span> <span m='394700'>the</span> <span m='394780'>valves</span>
  <span m='395050'>that</span> <span m='395320'>could</span> <span m='395590'>transition</span>
  <span m='396180'>between</span> <span m='396350'>open</span> <span m='396750'>and</span>
  <span m='396930'>closed</span> <span m='397150'>states.</span> <span m='398452'>It</span>
  <span m='398790'>could</span> <span m='398890'>also</span> <span m='399280'>be</span>
  <span m='399550'>the</span> <span m='399830'>whole</span> <span m='400720'>system--</span>
  <span m='401380'>the</span> <span m='401750'>starship</span> <span m='402430'>going</span>
  <span m='402670'>through</span> <span m='402970'>different</span> <span m='403240'>planets,</span>
  <span m='404380'>transitioning</span> <span m='405130'>through</span> <span m='405610'>a
  larger</span> <span m='407100'>set</span> <span m='407290'>of</span> <span m='407430'>locations,</span>
  <span m='408160'>picking</span> <span m='408290'>up</span> <span m='408575'>passengers,</span>
  <span m='408860'>dropping</span> <span m='409000'>them</span> <span m='409240'>off.</span>
  <span m='409480'>So</span> <span m='409630'>these could</span> <span m='409750'>be</span>
  <span m='410140'>quite</span> <span m='410240'>complex.</span> </p><p><span m='414569'>And</span>
  <span m='415050'>so as</span> <span m='415330'>I</span> <span m='415520'>said,</span>
  <span m='416210'>previously</span> <span m='417260'>in</span> <span m='417410'>our</span>
  <span m='418910'>problems</span> <span m='419310'>that we've been</span> <span m='419540'>modeling,</span>
  <span m='420700'>we've</span> <span m='420970'>been</span> <span m='421100'>going</span>
  <span m='421270'>through</span> <span m='421470'>a</span> <span m='421520'>system,</span>
  <span m='421845'>and</span> <span m='422170'>we've</span> <span m='422240'>been</span>
  <span m='422360'>searching</span> <span m='422720'>for</span> <span m='422880'>a</span>
  <span m='422900'>single</span> <span m='423620'>state</span> <span m='424250'>that</span>
  <span m='424370'>satisfies</span> <span m='424940'>all</span> <span m='425030'>of</span>
  <span m='425120'>our</span> <span m='425180'>goal</span> <span m='425390'>conditions.</span>
  <span m='427640'>Maybe</span> <span m='428010'>we</span> <span m='428330'>to</span>
  <span m='428390'>reach</span> <span m='428560'>[? Lavinia ?]</span> <span m='429270'>and</span>
  <span m='429560'>save</span> <span m='430130'>a</span> <span m='430190'>certain</span>
  <span m='430430'>number</span> <span m='430640'>of</span> <span m='430730'>people.</span>
  <span m='432280'>But</span> <span m='432690'>with</span> <span m='433220'>temporal</span>
  <span m='433530'>logic,</span> <span m='434940'>we</span> <span m='435320'>can</span>
  <span m='435450'>actually</span> <span m='435640'>express</span> <span m='436100'>goals</span>
  <span m='436570'>that</span> <span m='436720'>are</span> <span m='436780'>satisfied</span>
  <span m='437350'>over</span> <span m='437590'>a</span> <span m='437650'>number</span>
  <span m='437950'>of</span> <span m='438010'>states,</span> <span m='440200'>and</span>
  <span m='440800'>this</span> <span m='441070'>allows</span> <span m='441340'>us</span>
  <span m='441480'>to</span> <span m='441590'>do</span> <span m='442180'>some</span>
  <span m='442810'>more</span> <span m='443860'>expressive</span> <span m='444640'>goals</span>
  <span m='445180'>than</span> <span m='445330'>we could</span> <span m='445490'>capture</span>
  <span m='445990'>just</span> <span m='446190'>by</span> <span m='446440'>looking</span>
  <span m='446500'>at a</span> <span m='446680'>single</span> <span m='447000'>state</span>
  <span m='447330'>at</span> <span m='447450'>the</span> <span m='447560'>end.</span>
  </p><p><span m='452460'>So</span> <span m='452870'>for</span> <span m='453020'>example,</span>
  <span m='454640'>what</span> <span m='455130'>if</span> <span m='455600'>a</span>
  <span m='455690'>problem</span> <span m='456150'>requires</span> <span m='457010'>some</span>
  <span m='457250'>condition</span> <span m='457730'>to</span> <span m='457820'>be</span>
  <span m='457960'>met</span> <span m='458630'>until</span> <span m='458990'>another</span>
  <span m='459260'>condition</span> <span m='459770'>is</span> <span m='459980'>met?</span>
  <span m='460465'>And</span> <span m='460800'>for</span> <span m='460900'>example,</span>
  <span m='461600'>you</span> <span m='461650'>know,</span> <span m='461840'>when</span>
  <span m='462050'>you</span> <span m='462110'>see</span> <span m='462290'>a</span>
  <span m='462350'>red</span> <span m='462560'>light,</span> <span m='462920'>that</span>
  <span m='463070'>implies</span> <span m='463610'>that</span> <span m='463730'>we</span>
  <span m='463820'>should</span> <span m='463970'>stop</span> <span m='464600'>until</span>
  <span m='464930'>we</span> <span m='465020'>see</span> <span m='465350'>a</span>
  <span m='465470'>green</span> <span m='465710'>light.</span> <span m='467990'>And</span>
  <span m='468600'>if</span> <span m='468680'>we</span> <span m='468850'>look</span>
  <span m='469010'>at</span> <span m='469300'>a</span> <span m='469380'>timeline,</span>
  <span m='470190'>or</span> <span m='470360'>a</span> <span m='470390'>trace</span>
  <span m='470930'>of</span> <span m='471230'>one</span> <span m='471350'>of</span>
  <span m='471440'>these</span> <span m='471560'>systems,</span> <span m='472790'>that</span>
  <span m='472940'>might</span> <span m='473090'>look</span> <span m='473390'>something</span>
  <span m='473660'>like</span> <span m='473780'>this.</span> <span m='474160'>So we're</span>
  <span m='474560'>going</span> <span m='474890'>along</span> <span m='475370'>through</span>
  <span m='475490'>our</span> <span m='475580'>system,</span> <span m='476610'>and</span>
  <span m='476840'>at one of the states,</span> <span m='477320'>we</span> <span m='477470'>see</span>
  <span m='477920'>the</span> <span m='478010'>red</span> <span m='478190'>light.</span>
  <span m='479116'>So</span> <span m='479460'>that</span> <span m='479740'>adds</span>
  <span m='480190'>this</span> <span m='480360'>condition</span> <span m='480830'>that</span>
  <span m='481300'>we should</span> <span m='481630'>stop.</span> <span m='482960'>And</span>
  <span m='483080'>then</span> <span m='483350'>that</span> <span m='483490'>condition</span>
  <span m='483830'>will</span> <span m='483950'>hold</span> <span m='484190'>forever</span>
  <span m='484720'>until</span> <span m='485050'>we</span> <span m='485150'>see</span>
  <span m='485330'>a</span> <span m='485390'>green</span> <span m='485600'>light,</span>
  <span m='485810'>at</span> <span m='486270'>which</span> <span m='486350'>point</span>
  <span m='486620'>that</span> <span m='486770'>condition</span> <span m='487170'>is
  dropped,</span> <span m='487870'>and</span> <span m='488180'>we can</span> <span
  m='488310'>keep</span> <span m='488580'>moving</span> <span m='488850'>on.</span>
  <span m='490820'>Another</span> <span m='491060'>example</span> <span m='491510'>where</span>
  <span m='491660'>we</span> <span m='491750'>might</span> <span m='491900'>want</span>
  <span m='492020'>to</span> <span m='492080'>use</span> <span m='492250'>temporal</span>
  <span m='492700'>logic</span> <span m='493400'>is,</span> <span m='493700'>what</span>
  <span m='493880'>if</span> <span m='493970'>our</span> <span m='494120'>problem</span>
  <span m='494385'>requires</span> <span m='495230'>a</span> <span m='495570'>condition</span>
  <span m='496130'>to</span> <span m='497000'>always</span> <span m='497540'>eventually</span>
  <span m='497855'>be</span> <span m='498170'>met.</span> <span m='498450'>And</span>
  <span m='498550'>this is what I was</span> <span m='499040'>talking about with</span>
  <span m='499200'>the</span> <span m='499520'>gas</span> <span m='499730'>station.</span>
  <span m='500510'>So</span> <span m='502040'>we</span> <span m='502160'>want</span>
  <span m='502270'>to be</span> <span m='502340'>going</span> <span m='502610'>on</span>
  <span m='502730'>forever,</span> <span m='503750'>and</span> <span m='503990'>there</span>
  <span m='504080'>should</span> <span m='504290'>always</span> <span m='504530'>be</span>
  <span m='504650'>some</span> <span m='504920'>point</span> <span m='505190'>in</span>
  <span m='505250'>the</span> <span m='505340'>future</span> <span m='506030'>when</span>
  <span m='506270'>we</span> <span m='506660'>do</span> <span m='506990'>have</span>
  <span m='507970'>a</span> <span m='508340'>state</span> <span m='508620'>where we're
  at</span> <span m='508900'>a</span> <span m='509090'>gas</span> <span m='509300'>station.</span>
  <span m='510110'>So</span> <span m='510530'>we</span> <span m='510600'>might</span>
  <span m='511890'>start</span> <span m='512165'>our</span> <span m='512440'>system</span>
  <span m='512780'>at a</span> <span m='512929'>certain</span> <span m='513194'>state.</span>
  <span m='514309'>And</span> <span m='515030'>our</span> <span m='515150'>plan</span>
  <span m='515549'>says</span> <span m='515860'>that</span> <span m='516650'>at</span>
  <span m='516850'>some</span> <span m='517049'>point</span> <span m='517289'>we</span>
  <span m='517700'>do reach a</span> <span m='517909'>gas station,</span> <span m='518390'>so
  that's</span> <span m='518659'>good.</span> <span m='518809'>But</span> <span m='519084'>then</span>
  <span m='519360'>when we</span> <span m='519600'>get to</span> <span m='519860'>the</span>
  <span m='519919'>next</span> <span m='520179'>state,</span> <span m='520490'>we</span>
  <span m='520580'>also</span> <span m='520820'>want</span> <span m='521030'>it to</span>
  <span m='521120'>be</span> <span m='521270'>true</span> <span m='521730'>that</span>
  <span m='521900'>from</span> <span m='522080'>that</span> <span m='522230'>point</span>
  <span m='522440'>on,</span> <span m='522650'>we're</span> <span m='522740'>going</span>
  <span m='522850'>to</span> <span m='522919'>reach</span> <span m='523070'>another</span>
  <span m='523340'>gas</span> <span m='523490'>station,</span> <span m='524850'>and</span>
  <span m='525530'>after</span> <span m='525770'>that,</span> <span m='526370'>going</span>
  <span m='526670'>on</span> <span m='526860'>and on and</span> <span m='527180'>on</span>
  <span m='527500'>into</span> <span m='527650'>the</span> <span m='527750'>future.</span>
  </p><p><span m='530070'>These</span> <span m='530120'>are</span> <span m='530180'>things</span>
  <span m='530360'>that</span> <span m='530440'>you</span> <span m='530570'>can't</span>
  <span m='532790'>express</span> <span m='533540'>very</span> <span m='533780'>easily</span>
  <span m='534230'>with</span> <span m='534410'>the</span> <span m='534500'>types</span>
  <span m='535040'>of</span> <span m='535220'>logic</span> <span m='535670'>that</span>
  <span m='535790'>we've</span> <span m='535910'>been</span> <span m='536040'>dealing
  with</span> <span m='536260'>before.</span> <span m='539640'>So</span> <span m='540120'>one</span>
  <span m='540330'>important</span> <span m='540820'>distinction</span> <span m='541165'>that</span>
  <span m='541510'>we</span> <span m='541600'>should</span> <span m='541810'>clear</span>
  <span m='542080'>up</span> <span m='542230'>before</span> <span m='543370'>we</span>
  <span m='543460'>really</span> <span m='543670'>dive</span> <span m='543970'>into</span>
  <span m='544210'>the</span> <span m='544500'>syntax</span> <span m='544920'>of</span>
  <span m='545030'>how</span> <span m='545920'>these</span> <span m='546390'>linear
  temporal logics</span> <span m='546860'>work</span> <span m='548420'>is</span> <span
  m='548630'>the difference</span> <span m='549105'>between</span> <span m='549580'>branching</span>
  <span m='550000'>time</span> <span m='550360'>and</span> <span m='550680'>linear</span>
  <span m='550810'>time.</span> <span m='550950'>They're</span> <span m='551220'>really</span>
  <span m='551530'>two</span> <span m='551710'>different</span> <span m='552870'>models</span>
  <span m='553160'>of</span> <span m='553210'>time</span> <span m='553480'>that</span>
  <span m='553570'>we</span> <span m='553660'>can</span> <span m='553910'>be</span>
  <span m='554050'>working</span> <span m='554320'>with.</span> <span m='555070'>There's</span>
  <span m='555220'>two different</span> <span m='555510'>types</span> <span m='555830'>of</span>
  <span m='555910'>temporal</span> <span m='556230'>logic</span> <span m='556600'>that</span>
  <span m='556720'>exist</span> <span m='557670'>to</span> <span m='557830'>express</span>
  <span m='558220'>these</span> <span m='558400'>different</span> <span m='558640'>types</span>
  <span m='558860'>of</span> <span m='558970'>time.</span> </p><p><span m='560080'>So</span>
  <span m='560390'>linear</span> <span m='560680'>time</span> <span m='561400'>is</span>
  <span m='562890'>more</span> <span m='563080'>similar</span> <span m='563500'>to</span>
  <span m='564370'>the</span> <span m='564490'>world</span> <span m='564790'>that</span>
  <span m='564910'>we</span> <span m='565060'>live</span> <span m='565270'>in,</span>
  <span m='566030'>unless</span> <span m='566260'>you're</span> <span m='566910'>living</span>
  <span m='567150'>in some</span> <span m='567535'>sci-fi movie</span> <span m='567920'>where</span>
  <span m='568300'>time</span> <span m='568590'>is</span> <span m='568650'>branching</span>
  <span m='568960'>into</span> <span m='569200'>different</span> <span m='569440'>realities,</span>
  <span m='570820'>and</span> <span m='570910'>all</span> <span m='571030'>sorts of</span>
  <span m='571360'>crazy</span> <span m='571630'>stuff</span> <span m='571850'>is
  going</span> <span m='572186'>on.</span> <span m='572860'>You can</span> <span m='573040'>think</span>
  <span m='573220'>of</span> <span m='573310'>time</span> <span m='573740'>as</span>
  <span m='574090'>just</span> <span m='574420'>this</span> <span m='574750'>linear</span>
  <span m='575250'>timeline.</span> <span m='575930'>So</span> <span m='576160'>right</span>
  <span m='576340'>now,</span> <span m='576980'>it's</span> <span m='577120'>one</span>
  <span m='577320'>future</span> <span m='577615'>state that's</span> <span m='577910'>going
  to</span> <span m='578100'>happen</span> <span m='578410'>for</span> <span m='578540'>me.</span>
  <span m='579740'>And</span> <span m='580470'>you</span> <span m='580780'>know,</span>
  <span m='581140'>regardless</span> <span m='581860'>of</span> <span m='582040'>how</span>
  <span m='582160'>many</span> <span m='582340'>options</span> <span m='582700'>I</span>
  <span m='582790'>have,</span> <span m='583170'>there's</span> <span m='584050'>one</span>
  <span m='584290'>realization</span> <span m='584890'>of</span> <span m='585010'>the</span>
  <span m='585100'>time.</span> </p><p><span m='587180'>And</span> <span m='588760'>what</span>
  <span m='588880'>this</span> <span m='588980'>lets us</span> <span m='589330'>do</span>
  <span m='589740'>is</span> <span m='589850'>that</span> <span m='589980'>it</span>
  <span m='590140'>gives</span> <span m='590320'>us</span> <span m='590890'>a</span>
  <span m='590920'>single</span> <span m='591250'>path</span> <span m='591530'>for
  our</span> <span m='591810'>system,</span> <span m='592680'>and</span> <span m='593140'>we</span>
  <span m='593320'>can</span> <span m='594940'>reason</span> <span m='595350'>very</span>
  <span m='595760'>exactly</span> <span m='596600'>about</span> <span m='597370'>the</span>
  <span m='599860'>conditions</span> <span m='600115'>that</span> <span m='600370'>are</span>
  <span m='600550'>met</span> <span m='601180'>within</span> <span m='601330'>that</span>
  <span m='601450'>path.</span> <span m='601940'>And</span> <span m='602430'>this</span>
  <span m='602770'>lets</span> <span m='603010'>us</span> <span m='609440'>describe</span>
  <span m='610250'>what</span> <span m='610400'>will</span> <span m='610760'>always</span>
  <span m='611060'>happen</span> <span m='611300'>in a</span> <span m='611400'>system.</span>
  <span m='611680'>For</span> <span m='611880'>example,</span> <span m='612240'>we</span>
  <span m='612640'>can</span> <span m='613040'>guarantee</span> <span m='613760'>that</span>
  <span m='614360'>we</span> <span m='614540'>always</span> <span m='614840'>stop</span>
  <span m='615590'>at</span> <span m='615680'>a</span> <span m='615710'>red</span>
  <span m='615890'>light</span> <span m='616160'>until</span> <span m='616430'>we</span>
  <span m='616520'>see</span> <span m='616760'>a green</span> <span m='617040'>light,</span>
  <span m='617180'>or we always</span> <span m='617520'>stay</span> <span m='617785'>within</span>
  <span m='620180'>the</span> <span m='620630'>speed</span> <span m='620930'>limit.</span>
  </p><p><span m='623080'>This is</span> <span m='623370'>contrasted</span> <span
  m='624150'>with</span> <span m='624320'>a different</span> <span m='624745'>model
  of</span> <span m='625170'>time,</span> <span m='626820'>called</span> <span m='627120'>branching</span>
  <span m='627420'>time.</span> <span m='628360'>And</span> <span m='629113'>in this</span>
  <span m='629566'>model of</span> <span m='630020'>time,</span> <span m='630590'>at</span>
  <span m='630870'>each</span> <span m='631250'>time</span> <span m='631480'>instant,</span>
  <span m='632190'>we</span> <span m='632310'>consider</span> <span m='632820'>all</span>
  <span m='633060'>possible</span> <span m='633480'>futures.</span> <span m='634560'>So</span>
  <span m='634910'>if</span> <span m='635070'>we</span> <span m='635250'>have</span>
  <span m='636060'>multiple</span> <span m='636510'>actions</span> <span m='636840'>that</span>
  <span m='637260'>we</span> <span m='637320'>could</span> <span m='637440'>perform</span>
  <span m='638020'>at</span> <span m='638180'>a</span> <span m='638260'>given</span>
  <span m='638460'>state,</span> <span m='639180'>we're</span> <span m='639270'>going</span>
  <span m='639390'>to</span> <span m='639450'>consider</span> <span m='639870'>different</span>
  <span m='640170'>timelines</span> <span m='640570'>that</span> <span m='640770'>branch</span>
  <span m='641100'>off</span> <span m='641330'>for each of</span> <span m='641580'>those</span>
  <span m='643010'>possible</span> <span m='643305'>behaviors.</span> <span m='644730'>And</span>
  <span m='644850'>this</span> <span m='645230'>results</span> <span m='645720'>in</span>
  <span m='646800'>alternate</span> <span m='647290'>courses</span> <span m='647610'>of</span>
  <span m='647730'>time</span> <span m='648750'>that</span> <span m='648870'>we</span>
  <span m='648990'>can</span> <span m='649140'>reason</span> <span m='649420'>about</span>
  <span m='649710'>as a</span> <span m='649940'>set.</span> <span m='650730'>And</span>
  <span m='651150'>instead</span> <span m='651480'>of</span> <span m='651970'>thinking</span>
  <span m='652190'>about</span> <span m='652320'>this</span> <span m='652650'>as</span>
  <span m='653550'>always</span> <span m='653970'>conditions--</span> <span m='654390'>so,</span>
  <span m='655250'>our</span> <span m='655490'>path</span> <span m='655800'>always</span>
  <span m='656100'>does</span> <span m='656370'>this--</span> <span m='656760'>we
  can think about</span> <span m='657050'>this</span> <span m='657270'>more in</span>
  <span m='657520'>possibilities.</span> <span m='658585'>And</span> <span m='658880'>if
  we're</span> <span m='659165'>using</span> <span m='659450'>branching</span> <span
  m='659820'>time, we</span> <span m='660090'>can</span> <span m='660210'>say,</span>
  <span m='661050'>you</span> <span m='661560'>know,</span> <span m='661650'>at</span>
  <span m='661770'>this</span> <span m='661860'>state and</span> <span m='662190'>time,</span>
  <span m='662710'>there</span> <span m='662820'>exists</span> <span m='663330'>a</span>
  <span m='663390'>future</span> <span m='663690'>path</span> <span m='664290'>in</span>
  <span m='664440'>which</span> <span m='665160'>we</span> <span m='665310'>will</span>
  <span m='665490'>always</span> <span m='665700'>stay</span> <span m='666300'>under</span>
  <span m='666700'>the</span> <span m='666990'>speed</span> <span m='667210'>limit,</span>
  <span m='667860'>or,</span> <span m='668100'>at</span> <span m='668250'>this</span>
  <span m='668430'>point</span> <span m='668640'>in</span> <span m='668730'>time,</span>
  <span m='669550'>all</span> <span m='669740'>our</span> <span m='669840'>future</span>
  <span m='670190'>paths</span> <span m='671160'>satisfy</span> <span m='671680'>a</span>
  <span m='671870'>certain</span> <span m='672070'>condition.</span> </p><p><span
  m='673110'>So</span> <span m='674350'>whereas</span> <span m='674730'>linear</span>
  <span m='674860'>temporal</span> <span m='675120'>logic</span> <span m='675660'>is</span>
  <span m='675810'>more</span> <span m='677180'>about</span> <span m='677790'>guaranteeing</span>
  <span m='678420'>what</span> <span m='678570'>will</span> <span m='678690'>happen</span>
  <span m='678990'>on</span> <span m='679110'>a</span> <span m='679140'>given</span>
  <span m='680016'>path,</span> <span m='680930'>branching</span> <span m='681360'>time</span>
  <span m='681720'>allows</span> <span m='682195'>us to</span> <span m='682670'>reason</span>
  <span m='682980'>about</span> <span m='683520'>what</span> <span m='683670'>might</span>
  <span m='683820'>possibly</span> <span m='684300'>happen</span> <span m='684540'>in
  the</span> <span m='684961'>system.</span> </p><p><span m='687070'>So</span> <span
  m='687220'>for</span> <span m='687370'>our</span> <span m='687550'>purposes</span>
  <span m='688120'>with</span> <span m='688240'>planning,</span> <span m='689440'>in</span>
  <span m='689830'>part</span> <span m='690120'>because</span> <span m='690180'>it's</span>
  <span m='690520'>more</span> <span m='690700'>attractable,</span> <span m='691510'>and</span>
  <span m='691660'>in</span> <span m='691750'>part</span> <span m='691960'>because</span>
  <span m='692210'>it</span> <span m='692280'>gives</span> <span m='692460'>us</span>
  <span m='692570'>an</span> <span m='692710'>exact</span> <span m='693370'>analysis</span>
  <span m='694260'>of</span> <span m='694660'>a</span> <span m='694740'>given</span>
  <span m='695000'>path,</span> <span m='695920'>we're</span> <span m='696070'>going</span>
  <span m='696190'>to</span> <span m='696280'>be doing</span> <span m='696500'>linear</span>
  <span m='696775'>time,</span> <span m='697400'>and</span> <span m='697660'>for</span>
  <span m='697780'>that</span> <span m='697900'>reason,</span> <span m='698170'>we</span>
  <span m='698290'>use</span> <span m='698620'>what's</span> <span m='698800'>called</span>
  <span m='698990'>linear</span> <span m='699250'>temporal</span> <span m='699640'>logic.</span>
  </p><p><span m='700610'>There's</span> <span m='700830'>a</span> <span m='700890'>different</span>
  <span m='701140'>type</span> <span m='701350'>of</span> <span m='701560'>temporal</span>
  <span m='702035'>logic.</span> <span m='702985'>There's</span> <span m='703460'>one
  called</span> <span m='703935'>CTL</span> <span m='704410'>and CTL*</span> <span
  m='705700'>that</span> <span m='705850'>deal with</span> <span m='706255'>branching</span>
  <span m='706660'>time.</span> <span m='707255'>And</span> <span m='707690'>those</span>
  <span m='708000'>are</span> <span m='708280'>sort</span> <span m='708470'>of</span>
  <span m='708580'>an</span> <span m='708670'>extension</span> <span m='709240'>of</span>
  <span m='709390'>linear</span> <span m='709750'>temporal</span> <span m='709930'>logic.</span>
  <span m='710290'>They</span> <span m='710590'>add</span> <span m='710690'>a few</span>
  <span m='710890'>other</span> <span m='711270'>operators</span> <span m='712520'>that</span>
  <span m='712750'>allow</span> <span m='713260'>you</span> <span m='713410'>to</span>
  <span m='713530'>reason</span> <span m='713830'>over</span> <span m='714130'>multiple</span>
  <span m='714626'>paths.</span> <span m='715620'>But</span> <span m='715960'>for</span>
  <span m='716110'>our</span> <span m='716170'>purposes,</span> <span m='716780'>we're</span>
  <span m='716850'>just going to be</span> <span m='717140'>using</span> <span m='717650'>the</span>
  <span m='717890'>linear</span> <span m='718378'>time</span> <span m='718866'>model.</span>
  </p><p><span m='720818'>So</span> <span m='721310'>kind of</span> <span m='721460'>as
  a</span> <span m='721710'>recap,</span> <span m='723570'>what</span> <span m='723840'>linear</span>
  <span m='724020'>temporal</span> <span m='724390'>logic</span> <span m='724760'>involves--</span>
  <span m='725910'>we're</span> <span m='726210'>using this</span> <span m='726510'>linear</span>
  <span m='726770'>time</span> <span m='726960'>model.</span> <span m='728490'>Another</span>
  <span m='728750'>important</span> <span m='729010'>distinction</span> <span m='729710'>is</span>
  <span m='729870'>that</span> <span m='730230'>we're</span> <span m='730590'>actually</span>
  <span m='730830'>going</span> <span m='730950'>to</span> <span m='731010'>be</span>
  <span m='731330'>talking</span> <span m='731510'>about</span> <span m='731850'>infinite</span>
  <span m='732060'>sequences</span> <span m='732210'>of</span> <span m='732520'>states.</span>
  <span m='733900'>So</span> <span m='734640'>instead</span> <span m='734940'>of</span>
  <span m='735060'>us</span> <span m='735270'>just</span> <span m='736430'>reasoning</span>
  <span m='736950'>up</span> <span m='737130'>until</span> <span m='737520'>a</span>
  <span m='737580'>certain</span> <span m='737850'>goal</span> <span m='738090'>condition</span>
  <span m='738345'>is</span> <span m='738600'>met,</span> <span m='739080'>we're thinking</span>
  <span m='739310'>about</span> <span m='739890'>systems</span> <span m='740520'>that</span>
  <span m='740710'>could</span> <span m='741180'>theoretically</span> <span m='741900'>keep</span>
  <span m='742410'>transitioning</span> <span m='743040'>over</span> <span m='743250'>time,</span>
  <span m='744000'>over</span> <span m='744330'>and</span> <span m='744420'>over</span>
  <span m='744600'>and</span> <span m='744720'>over</span> <span m='745020'>into</span>
  <span m='745240'>the</span> <span m='745470'>future.</span> <span m='746560'>So</span>
  <span m='746790'>if</span> <span m='746910'>you</span> <span m='746970'>have</span>
  <span m='747240'>one</span> <span m='747360'>of</span> <span m='747430'>these</span>
  <span m='747660'>state</span> <span m='748000'>machines,</span> <span m='748490'>you
  could</span> <span m='748825'>think, at</span> <span m='749160'>each</span> <span
  m='749430'>time</span> <span m='749680'>step,</span> <span m='750070'>it's</span>
  <span m='750120'>going</span> <span m='750240'>to</span> <span m='750300'>visit
  the</span> <span m='750660'>new</span> <span m='750780'>state.</span> <span m='751970'>And</span>
  <span m='752060'>if</span> <span m='752310'>you</span> <span m='752430'>give</span>
  <span m='752580'>it</span> <span m='752640'>enough</span> <span m='752900'>time,</span>
  <span m='753310'>it's</span> <span m='753360'>just</span> <span m='753480'>going</span>
  <span m='753600'>to</span> <span m='753870'>generate</span> <span m='754400'>an</span>
  <span m='754500'>infinite</span> <span m='754890'>sequence</span> <span m='755205'>of
  states.</span> <span m='755970'>And</span> <span m='756060'>we can</span> <span
  m='756270'>actually</span> <span m='756990'>express</span> <span m='757350'>properties</span>
  <span m='757800'>that</span> <span m='757890'>can</span> <span m='758040'>hold</span>
  <span m='758400'>over</span> <span m='758790'>an</span> <span m='758940'>infinite</span>
  <span m='759180'>number</span> <span m='759450'>of</span> <span m='759510'>states,</span>
  <span m='760290'>not</span> <span m='760500'>just</span> <span m='761450'>the</span>
  <span m='761610'>discrete</span> <span m='761970'>number of</span> <span m='762240'>states</span>
  <span m='762710'>that</span> <span m='762880'>we</span> <span m='762990'>might</span>
  <span m='763140'>usually</span> <span m='763540'>think</span> <span m='763760'>of</span>
  <span m='764020'>to</span> <span m='764160'>reach</span> <span m='764330'>a</span>
  <span m='764400'>goal.</span> </p><p><span m='766300'>And</span> <span m='767070'>linear</span>
  <span m='767250'>temporal</span> <span m='767510'>logic</span> <span m='767900'>can</span>
  <span m='768060'>actually</span> <span m='768390'>be</span> <span m='768510'>modified</span>
  <span m='769290'>to</span> <span m='769590'>work</span> <span m='769920'>with</span>
  <span m='770160'>discrete</span> <span m='770590'>set of</span> <span m='770860'>states.</span>
  <span m='772470'>It</span> <span m='772680'>just</span> <span m='772890'>requires</span>
  <span m='774000'>an</span> <span m='774150'>additional</span> <span m='774570'>operator.</span>
  <span m='776490'>But</span> <span m='777270'>the</span> <span m='777360'>ability</span>
  <span m='777750'>to</span> <span m='777870'>reason</span> <span m='778230'>about</span>
  <span m='778490'>infinite</span> <span m='778820'>sequences</span> <span m='779000'>of
  states</span> <span m='779330'>gives</span> <span m='779780'>us</span> <span m='780540'>a</span>
  <span m='780920'>lot</span> <span m='781200'>of</span> <span m='781550'>power</span>
  <span m='782190'>in</span> <span m='782705'>talking</span> <span m='782970'>about</span>
  <span m='783360'>guarantees</span> <span m='783615'>for our</span> <span m='783870'>system,</span>
  <span m='784380'>regardless</span> <span m='784790'>of</span> <span m='784890'>how</span>
  <span m='785000'>much</span> <span m='785220'>time we're</span> <span m='785680'>talking
  about</span> <span m='786140'>it.</span> </p><p><span m='789360'>Finally,</span>
  <span m='790410'>all</span> <span m='790860'>the</span> <span m='791010'>operators</span>
  <span m='791550'>we're</span> <span m='791610'>going</span> <span m='791730'>to</span>
  <span m='791790'>be</span> <span m='791880'>looking</span> <span m='792150'>at</span>
  <span m='792390'>in</span> <span m='792510'>our</span> <span m='792630'>logic</span>
  <span m='793050'>system</span> <span m='795680'>are</span> <span m='795780'>what</span>
  <span m='795870'>we</span> <span m='795960'>call</span> <span m='796170'>forward-looking</span>
  <span m='796860'>conditions.</span> <span m='798010'>So</span> <span m='800010'>when</span>
  <span m='800210'>we're</span> <span m='800310'>given</span> <span m='800520'>a</span>
  <span m='800610'>state</span> <span m='800970'>we're</span> <span m='801440'>going
  to</span> <span m='801830'>reasoning</span> <span m='802190'>about</span> <span
  m='802440'>what's</span> <span m='802590'>going</span> <span m='802710'>to</span>
  <span m='802770'>happen</span> <span m='803070'>in</span> <span m='803160'>the</span>
  <span m='803250'>future</span> <span m='804900'>for a</span> <span m='805260'>potentially</span>
  <span m='805740'>infinite</span> <span m='806050'>amount of</span> <span m='806360'>time
  in</span> <span m='806500'>the</span> <span m='806740'>future.</span> </p><p><span
  m='807660'>There's sort of</span> <span m='808020'>a</span> <span m='808080'>symmetric</span>
  <span m='808740'>version</span> <span m='809700'>of</span> <span m='810030'>this</span>
  <span m='810300'>logic</span> <span m='810980'>that</span> <span m='811110'>reasons</span>
  <span m='811530'>about</span> <span m='811660'>the</span> <span m='811710'>past.</span>
  <span m='813550'>So</span> <span m='813750'>for</span> <span m='813870'>example,</span>
  <span m='814570'>we</span> <span m='814590'>can</span> <span m='814710'>say--</span>
  <span m='816570'>talk</span> <span m='816840'>about</span> <span m='816930'>guarantees</span>
  <span m='817440'>that</span> <span m='817530'>something</span> <span m='818340'>will</span>
  <span m='818570'>eventually</span> <span m='818880'>happen</span> <span m='819180'>in</span>
  <span m='819270'>the</span> <span m='819360'>future--</span> <span m='820740'>there's</span>
  <span m='821010'>sort</span> <span m='821190'>of</span> <span m='821280'>a</span>
  <span m='821310'>symmetric</span> <span m='821760'>version</span> <span m='822090'>where</span>
  <span m='822180'>we can</span> <span m='822300'>talk</span> <span m='822570'>about,</span>
  <span m='823060'>given</span> <span m='823555'>a</span> <span m='824050'>certain
  state,</span> <span m='824500'>we can</span> <span m='824930'>guarantee that</span>
  <span m='825270'>something</span> <span m='825960'>had</span> <span m='826365'>eventually</span>
  <span m='826950'>happened</span> <span m='827280'>in</span> <span m='827370'>the</span>
  <span m='827460'>past.</span> <span m='828810'>But</span> <span m='829210'>for</span>
  <span m='829380'>us</span> <span m='830070'>in</span> <span m='830280'>that we're</span>
  <span m='830640'>going to</span> <span m='830970'>focus</span> <span m='831270'>on</span>
  <span m='831390'>planning--</span> <span m='832020'>we're</span> <span m='832440'>typically</span>
  <span m='832950'>planning</span> <span m='833250'>about</span> <span m='833400'>what
  to do</span> <span m='833550'>in</span> <span m='833760'>the</span> <span m='833850'>future,</span>
  <span m='834165'>and</span> <span m='834480'>it</span> <span m='834580'>makes</span>
  <span m='834900'>more</span> <span m='835080'>sense</span> <span m='835470'>for</span>
  <span m='835590'>us</span> <span m='835770'>to</span> <span m='836130'>use</span>
  <span m='836310'>this</span> <span m='836490'>future</span> <span m='836840'>of
  updating</span> <span m='837190'>the set</span> <span m='837540'>for</span> <span
  m='837900'>operators.</span> </p><p><span m='841267'>And so</span> <span m='841748'>I
  guess</span> <span m='842230'>one</span> <span m='843040'>little</span> <span m='843400'>nuance</span>
  <span m='843820'>here</span> <span m='844240'>that I</span> <span m='844630'>sort
  of pointed</span> <span m='845020'>out in</span> <span m='845410'>the</span> <span
  m='845500'>previous</span> <span m='845765'>slide is</span> <span m='846030'>that</span>
  <span m='846360'>because</span> <span m='846430'>we're</span> <span m='846760'>using</span>
  <span m='847660'>a</span> <span m='848080'>linear</span> <span m='848410'>model</span>
  <span m='848650'>of</span> <span m='848710'>time</span> <span m='848980'>and</span>
  <span m='849210'>not a</span> <span m='849360'>branching</span> <span m='849800'>model
  of</span> <span m='850250'>time, we're</span> <span m='850700'>going</span> <span
  m='851070'>to</span> <span m='851180'>be</span> <span m='851480'>expressing</span>
  <span m='851950'>properties</span> <span m='852400'>that</span> <span m='852520'>happen</span>
  <span m='852760'>over</span> <span m='852940'>a</span> <span m='852970'>single</span>
  <span m='853360'>path of</span> <span m='853600'>states,</span> <span m='854650'>and</span>
  <span m='854910'>not</span> <span m='855210'>properties</span> <span m='855610'>that
  happen</span> <span m='856050'>over</span> <span m='856430'>several</span> <span
  m='856650'>path of</span> <span m='857117'>states.</span> </p><p><span m='862260'>So</span>
  <span m='862750'>finally</span> <span m='863030'>I'm just</span> <span m='863453'>going
  to talk</span> <span m='863876'>about</span> <span m='864300'>a</span> <span m='864430'>couple
  of</span> <span m='864860'>the main</span> <span m='865290'>application</span> <span
  m='865830'>for</span> <span m='867210'>linear</span> <span m='867330'>temporal</span>
  <span m='867480'>logic</span> <span m='868580'>before</span> <span m='869450'>Ellie</span>
  <span m='869690'>will</span> <span m='870070'>dive</span> <span m='870325'>in,</span>
  <span m='870580'>and</span> <span m='870690'>actually</span> <span m='871530'>talk</span>
  <span m='871800'>more</span> <span m='871950'>about</span> <span m='872130'>the</span>
  <span m='872310'>semantics</span> <span m='872960'>and</span> <span m='873030'>syntax</span>
  <span m='874290'>of how</span> <span m='874460'>we</span> <span m='874550'>use</span>
  <span m='874800'>this logic.</span> </p><p><span m='877080'>So</span> <span m='878130'>the</span>
  <span m='878220'>first</span> <span m='878560'>menus</span> <span m='878850'>is</span>
  <span m='879270'>verification</span> <span m='880330'>and model</span> <span m='880670'>checking.</span>
  <span m='882390'>We</span> <span m='882540'>can</span> <span m='883290'>use</span>
  <span m='884040'>this</span> <span m='884530'>linear</span> <span m='884990'>temporal</span>
  <span m='885210'>logic</span> <span m='885990'>to</span> <span m='886440'>create</span>
  <span m='887940'>guarantees</span> <span m='888800'>about</span> <span m='889750'>a
  system,</span> <span m='890765'>and</span> <span m='891180'>formally</span> <span
  m='892110'>verify</span> <span m='892410'>it</span> <span m='893600'>for</span>
  <span m='894130'>a</span> <span m='894220'>couple</span> <span m='894420'>different</span>
  <span m='894950'>properties.</span> <span m='896020'>For</span> <span m='896040'>example,</span>
  <span m='896810'>we can</span> <span m='896950'>talk about</span> <span m='897280'>the</span>
  <span m='897360'>safety</span> <span m='897760'>of</span> <span m='897870'>the</span>
  <span m='897930'>system.</span> <span m='898390'>We</span> <span m='898550'>can</span>
  <span m='898860'>say,</span> <span m='899560'>over</span> <span m='899980'>the</span>
  <span m='900400'>course</span> <span m='900620'>of</span> <span m='900740'>this</span>
  <span m='900880'>system,</span> <span m='901160'>we</span> <span m='901350'>guarantee</span>
  <span m='902100'>that</span> <span m='902250'>it</span> <span m='902310'>will</span>
  <span m='902460'>never</span> <span m='902820'>enter</span> <span m='903690'>a</span>
  <span m='903750'>state</span> <span m='904030'>of</span> <span m='904240'>a</span>
  <span m='904480'>certain condition.</span> <span m='905664'>We</span> <span m='906111'>could</span>
  <span m='906560'>also</span> <span m='906890'>talk about</span> <span m='907390'>the</span>
  <span m='907695'>maintenance of</span> <span m='908000'>properties.</span> <span
  m='908610'>So</span> <span m='909230'>over the</span> <span m='909400'>entire</span>
  <span m='909850'>lifetime</span> <span m='910440'>of</span> <span m='910740'>this</span>
  <span m='910900'>system,</span> <span m='911830'>we</span> <span m='911850'>guarantee</span>
  <span m='912720'>that</span> <span m='912930'>a certain</span> <span m='913185'>condition</span>
  <span m='913610'>will</span> <span m='913930'>always</span> <span m='914150'>hold.</span>
  </p><p><span m='918190'>The other</span> <span m='918580'>main</span> <span m='918980'>application</span>
  <span m='919670'>for</span> <span m='919880'>temporal</span> <span m='920290'>logic,</span>
  <span m='920565'>the</span> <span m='920840'>one</span> <span m='921000'>that</span>
  <span m='921090'>we're</span> <span m='921180'>going</span> <span m='921300'>to</span>
  <span m='921360'>be</span> <span m='921420'>focusing</span> <span m='921870'>on,</span>
  <span m='922500'>is</span> <span m='922830'>for</span> <span m='923010'>planning.</span>
  <span m='924260'>And</span> <span m='924420'>this</span> <span m='924750'>planning</span>
  <span m='925200'>using</span> <span m='925880'>these</span> <span m='926160'>temporally</span>
  <span m='926460'>extended</span> <span m='926880'>goals</span> <span m='927160'>that</span>
  <span m='927230'>I've</span> <span m='927310'>been</span> <span m='927410'>talking</span>
  <span m='927670'>about,</span> <span m='928680'>and</span> <span m='928980'>it</span>
  <span m='929100'>actually</span> <span m='929580'>extends</span> <span m='930060'>nicely</span>
  <span m='930360'>to</span> <span m='930450'>talking</span> <span m='930860'>about</span>
  <span m='931420'>temporally</span> <span m='931910'>extended</span> <span m='932190'>preferences.</span>
  <span m='933280'>So</span> <span m='933750'>this</span> <span m='933930'>is</span>
  <span m='934930'>given</span> <span m='935460'>that</span> <span m='935600'>we</span>
  <span m='935730'>have</span> <span m='936090'>a</span> <span m='936150'>number</span>
  <span m='936410'>of</span> <span m='936480'>different</span> <span m='936670'>paths</span>
  <span m='937130'>that could</span> <span m='937580'>reach a</span> <span m='937740'>goal,</span>
  <span m='938370'>we</span> <span m='938430'>can</span> <span m='938550'>actually</span>
  <span m='938820'>look</span> <span m='938970'>at</span> <span m='939060'>all</span>
  <span m='939240'>those</span> <span m='939570'>and</span> <span m='939680'>see</span>
  <span m='940050'>which</span> <span m='940260'>paths</span> <span m='940580'>satisfy</span>
  <span m='941280'>certain</span> <span m='943320'>conditions</span> <span m='943860'>over</span>
  <span m='944070'>the</span> <span m='945450'>sequence</span> <span m='945800'>of</span>
  <span m='945870'>states,</span> <span m='946960'>and</span> <span m='947130'>use</span>
  <span m='947400'>those</span> <span m='947610'>conditions</span> <span m='948030'>as</span>
  <span m='948180'>a</span> <span m='948210'>way</span> <span m='948390'>of</span>
  <span m='948840'>choosing</span> <span m='949170'>which</span> <span m='949250'>ones</span>
  <span m='949420'>we</span> <span m='949620'>prefer.</span> </p><p><span m='951400'>So</span>
  <span m='951690'>with</span> <span m='951870'>that,</span> <span m='952980'>Ellie</span>
  <span m='953070'>is</span> <span m='953370'>now</span> <span m='953843'>going to
  talk</span> <span m='954316'>about</span> <span m='954790'>some</span> <span m='955020'>of</span>
  <span m='955080'>the</span> <span m='955860'>syntax</span> <span m='956550'>of</span>
  <span m='957528'>linear</span> <span m='958017'>temporal logic.</span> </p><p><span
  m='962907'>ELLIE:</span> <span m='963070'>Hi</span> <span m='963233'>guys.</span>
  <span m='963396'>My name</span> <span m='963890'>is</span> <span m='964070'>Ellie,</span>
  <span m='964830'>and</span> <span m='965310'>I'm</span> <span m='965790'>going to
  be talking about</span> <span m='966270'>the</span> <span m='966580'>syntax</span>
  <span m='967035'>of</span> <span m='967490'>LTL.</span> </p><p><span m='970220'>So</span>
  <span m='970550'>an</span> <span m='970975'>LTL</span> <span m='971400'>formula</span>
  <span m='971790'>is</span> <span m='972045'>a</span> <span m='972300'>series</span>
  <span m='972730'>of</span> <span m='973050'>states.</span> <span m='974250'>And</span>
  <span m='974530'>at each</span> <span m='974925'>state,</span> <span m='975320'>you
  can</span> <span m='975630'>have</span> <span m='975940'>various</span> <span m='976250'>propositions</span>
  <span m='976870'>than can</span> <span m='977020'>be</span> <span m='977420'>either</span>
  <span m='977780'>true</span> <span m='977990'>or</span> <span m='978080'>false.</span>
  <span m='979400'>So</span> <span m='979530'>for example--</span> <span m='981910'>is
  it</span> <span m='981960'>OK</span> <span m='982320'>if</span> <span m='982510'>I</span>
  <span m='982920'>erase this,</span> <span m='983330'>Steve?</span> </p><p><span
  m='983740'>STEVE:</span> <span m='983817'>Yeah.</span> <span m='983894'>Go</span>
  <span m='983971'>ahead.</span> </p><p><span m='988253'>ELLIE:</span> <span m='988369'>So</span>
  <span m='988720'>for</span> <span m='989187'>example</span> <span m='990130'>you</span>
  <span m='990420'>can have</span> <span m='991340'>a</span> <span m='992720'>[INAUDIBLE]</span>
  <span m='993180'>animation</span> <span m='993640'>show</span> <span m='994100'>that
  has</span> <span m='994560'>a</span> <span m='995020'>series</span> <span m='995490'>of</span>
  <span m='995750'>states</span> <span m='997199'>that goes</span> <span m='997682'>on
  to</span> <span m='998165'>infinity.</span> <span m='999131'>And</span> <span m='999620'>at</span>
  <span m='1000010'>each</span> <span m='1000400'>state you can</span> <span m='1000860'>have</span>
  <span m='1001870'>propositions</span> <span m='1002470'>that</span> <span m='1002560'>are</span>
  <span m='1002650'>either</span> <span m='1002920'>true</span> <span m='1003160'>or</span>
  <span m='1003190'>false.</span> <span m='1004150'>So</span> <span m='1004180'>the
  traffic</span> <span m='1004660'>could</span> <span m='1004830'>be</span> <span
  m='1005320'>red</span> <span m='1005620'>could be an</span> <span m='1006040'>example
  for a</span> <span m='1006460'>proposition.</span> <span m='1007120'>We</span> <span
  m='1007612'>could be</span> <span m='1008104'>stopped,</span> <span m='1012040'>et
  cetera.</span> <span m='1017452'>And</span> <span m='1017960'>there's</span> <span
  m='1018280'>various</span> <span m='1018685'>logical</span> <span m='1019090'>operators</span>
  <span m='1019710'>that we</span> <span m='1019820'>can</span> <span m='1020030'>apply</span>
  <span m='1020366'>to</span> <span m='1020702'>these formulas--</span> <span m='1021760'>these</span>
  <span m='1021950'>sets</span> <span m='1022230'>of</span> <span m='1022320'>states,</span>
  <span m='1023280'>and</span> <span m='1023500'>we can</span> <span m='1024089'>determine</span>
  <span m='1024540'>if</span> <span m='1024970'>these</span> <span m='1025704'>logical</span>
  <span m='1026109'>operators</span> <span m='1026650'>are</span> <span m='1026770'>either</span>
  <span m='1027010'>true</span> <span m='1027339'>or</span> <span m='1027369'>false</span>
  <span m='1027880'>about</span> <span m='1028260'>each</span> <span m='1031717'>set
  of</span> <span m='1032188'>states--</span> <span m='1032659'>each formula.</span>
  <span m='1034079'>So</span> <span m='1034230'>there's</span> <span m='1034500'>the</span>
  <span m='1034609'>not operator,</span> <span m='1034944'>the</span> <span m='1035280'>or</span>
  <span m='1035460'>operator,</span> <span m='1035850'>the</span> <span m='1036240'>and,</span>
  <span m='1036730'>the</span> <span m='1036980'>implies,</span> <span m='1037420'>if
  and</span> <span m='1037859'>only and,</span> <span m='1038880'>and</span> <span
  m='1039589'>like</span> <span m='1039810'>I</span> <span m='1039869'>said,</span>
  <span m='1040140'>the</span> <span m='1040220'>state--</span> <span m='1040896'>each</span>
  <span m='1041690'>proposition</span> <span m='1041810'>of</span> <span m='1042246'>[INAUDIBLE]</span>
  <span m='1042682'>can either</span> <span m='1043119'>be true</span> <span m='1043530'>or</span>
  <span m='1043680'>false.</span> </p><p><span m='1045636'>So just</span> <span m='1046125'>to
  go through</span> <span m='1046614'>some examples</span> <span m='1047103'>of these,</span>
  <span m='1050530'>the</span> <span m='1050800'>logical</span> <span m='1051000'>operator</span>
  <span m='1051840'>true</span> <span m='1052450'>says</span> <span m='1052870'>that--</span>
  <span m='1054315'>essentially</span> <span m='1054760'>what</span> <span m='1054980'>the</span>
  <span m='1055080'>operator</span> <span m='1055936'>true</span> <span m='1056350'>says</span>
  <span m='1056860'>is</span> <span m='1057110'>it's</span> <span m='1057270'>not</span>
  <span m='1057470'>saying,</span> <span m='1058160'>oh,</span> <span m='1058510'>this</span>
  <span m='1058800'>state</span> <span m='1059060'>is</span> <span m='1059360'>true.</span>
  <span m='1059940'>The operator</span> <span m='1060500'>just</span> <span m='1060740'>true</span>
  <span m='1061030'>says that</span> <span m='1061360'>there</span> <span m='1061570'>are</span>
  <span m='1061840'>states</span> <span m='1062260'>for</span> <span m='1062520'>all</span>
  <span m='1062780'>infinity.</span> <span m='1063180'>So</span> <span m='1063370'>true</span>
  <span m='1064150'>is</span> <span m='1064300'>always</span> <span m='1064720'>true.</span>
  <span m='1064990'>So no matter</span> <span m='1065487'>what you</span> <span m='1065984'>had
  for your</span> <span m='1066481'>state</span> <span m='1066980'>here,</span> <span
  m='1067500'>the</span> <span m='1067720'>logical</span> <span m='1068140'>operator</span>
  <span m='1068395'>true</span> <span m='1068650'>holds.</span> <span m='1070490'>However,</span>
  <span m='1071100'>when</span> <span m='1071540'>you</span> <span m='1071770'>talk</span>
  <span m='1072100'>about</span> <span m='1072280'>the</span> <span m='1072400'>logical</span>
  <span m='1072660'>operator</span> <span m='1073290'>true</span> <span m='1073530'>with
  respect</span> <span m='1074000'>to a certain</span> <span m='1074470'>state</span>
  <span m='1074980'>or a</span> <span m='1075270'>certain</span> <span m='1075460'>proposition,</span>
  <span m='1077330'>then</span> <span m='1077733'>it can either</span> <span m='1078136'>be
  true or</span> <span m='1078540'>false.</span> </p><p><span m='1079130'>So for</span>
  <span m='1079560'>example,</span> <span m='1080420'>here,</span> <span m='1081280'>the</span>
  <span m='1081370'>logical</span> <span m='1082300'>operator</span> <span m='1082850'>red</span>
  <span m='1083550'>light</span> <span m='1084460'>is</span> <span m='1085090'>true</span>
  <span m='1085840'>at</span> <span m='1085940'>the</span> <span m='1086070'>first</span>
  <span m='1086290'>state.</span> <span m='1088100'>If</span> <span m='1088290'>this
  was</span> <span m='1088630'>green,</span> <span m='1089310'>then the</span> <span
  m='1089460'>logical</span> <span m='1089870'>operator</span> <span m='1090330'>red
  would</span> <span m='1090740'>be false</span> <span m='1091210'>at</span> <span
  m='1091320'>the</span> <span m='1091470'>first</span> <span m='1091710'>state.</span>
  <span m='1091990'>Does that make</span> <span m='1092290'>sense?</span> <span m='1093796'>All
  right.</span> </p><p><span m='1096060'>One</span> <span m='1096270'>important</span>
  <span m='1096790'>thing</span> <span m='1097050'>to</span> <span m='1097230'>note</span>
  <span m='1097840'>about</span> <span m='1098000'>the</span> <span m='1098140'>logical</span>
  <span m='1098370'>o</span> <span m='1098540'>operators</span> <span m='1099660'>is</span>
  <span m='1100320'>that they</span> <span m='1101040'>just</span> <span m='1101370'>apply</span>
  <span m='1102200'>to the</span> <span m='1102675'>very first</span> <span m='1103150'>state</span>
  <span m='1103580'>in</span> <span m='1103720'>your</span> <span m='1103860'>statement.</span>
  <span m='1104880'>So</span> <span m='1105440'>when</span> <span m='1105630'>we're</span>
  <span m='1105720'>discussing</span> <span m='1106090'>logical</span> <span m='1106490'>operators,</span>
  <span m='1106840'>we</span> <span m='1107340'>haven't</span> <span m='1107700'>gotten</span>
  <span m='1107960'>to</span> <span m='1108090'>the</span> <span m='1108210'>point</span>
  <span m='1109100'>where</span> <span m='1109290'>we</span> <span m='1109530'>can</span>
  <span m='1110370'>express</span> <span m='1111030'>temporal</span> <span m='1113041'>information</span>
  <span m='1113430'>about</span> <span m='1113780'>our</span> <span m='1114090'>sequence</span>
  <span m='1114470'>of</span> <span m='1114720'>states.</span> </p><p><span m='1120400'>The
  next</span> <span m='1120900'>operator is,</span> <span m='1121400'>not.</span>
  <span m='1122400'>So</span> <span m='1122810'>as you</span> <span m='1123285'>can</span>
  <span m='1123760'>see here,</span> <span m='1125390'>the traffic</span> <span m='1125830'>light</span>
  <span m='1126120'>is</span> <span m='1126210'>read at the</span> <span m='1126680'>first</span>
  <span m='1126950'>state.</span> <span m='1128200'>So</span> <span m='1128330'>the</span>
  <span m='1128490'>traffic</span> <span m='1128780'>light's</span> <span m='1129080'>not</span>
  <span m='1129540'>green.</span> <span m='1130460'>Hold,</span> <span m='1130920'>because</span>
  <span m='1131940'>the</span> <span m='1132180'>proposition</span> <span m='1132553'>green</span>
  <span m='1132926'>is</span> <span m='1133300'>not true</span> <span m='1133660'>at</span>
  <span m='1134020'>the first</span> <span m='1134180'>state.</span> <span m='1135850'>And
  the</span> <span m='1136790'>logical</span> <span m='1137100'>operator,</span> <span
  m='1137740'>and,</span> <span m='1139200'>at this</span> <span m='1139610'>first</span>
  <span m='1139980'>state</span> <span m='1140130'>is</span> <span m='1140920'>we're
  at the</span> <span m='1141370'>red</span> <span m='1141610'>light,</span> <span
  m='1142240'>and</span> <span m='1142440'>we're</span> <span m='1142640'>getting</span>
  <span m='1142940'>gas.</span> <span m='1143350'>And</span> <span m='1143840'>so</span>
  <span m='1144800'>both</span> <span m='1145450'>that</span> <span m='1145800'>we're
  at the</span> <span m='1146150'>red</span> <span m='1146360'>light</span> <span
  m='1146660'>and that we're</span> <span m='1146780'>getting</span> <span m='1147030'>gas</span>
  <span m='1147450'>holds</span> <span m='1147780'>for</span> <span m='1148130'>the
  first</span> <span m='1148320'>state.</span> </p><p><span m='1152272'>And then</span>
  <span m='1153260'>the</span> <span m='1153754'>operator,</span> <span m='1154250'>or,</span>
  <span m='1155080'>essentially</span> <span m='1155720'>says--</span> <span m='1156752'>I
  guess</span> <span m='1157224'>a lot of this is</span> <span m='1157696'>probably</span>
  <span m='1158170'>review for</span> <span m='1158330'>you guys--</span> <span m='1158820'>logical</span>
  <span m='1159160'>operators--</span> <span m='1159980'>but</span> <span m='1160820'>essentially</span>
  <span m='1161190'>if</span> <span m='1161480'>you</span> <span m='1161570'>have</span>
  <span m='1162310'>red</span> <span m='1162630'>or</span> <span m='1162870'>green</span>
  <span m='1164230'>then</span> <span m='1164440'>you</span> <span m='1164530'>could</span>
  <span m='1164660'>either</span> <span m='1164940'>have</span> <span m='1165210'>the
  traffic light</span> <span m='1165660'>be red</span> <span m='1166110'>or the</span>
  <span m='1166560'>traffic light</span> <span m='1166650'>be green</span> <span m='1167015'>at
  the</span> <span m='1167380'>first</span> <span m='1167570'>state.</span> <span
  m='1168870'>And</span> <span m='1169170'>as long as</span> <span m='1169470'>one</span>
  <span m='1169660'>of</span> <span m='1169710'>those</span> <span m='1170200'>two</span>
  <span m='1170380'>hold,</span> <span m='1170800'>or</span> <span m='1170920'>both
  of</span> <span m='1171338'>them hold,</span> <span m='1171756'>then</span> <span
  m='1172592'>it's</span> <span m='1173010'>true.</span> <span m='1173942'>And</span>
  <span m='1174300'>one</span> <span m='1174850'>thing</span> <span m='1175060'>to</span>
  <span m='1175240'>note</span> <span m='1175660'>about</span> <span m='1177040'>or</span>
  <span m='1177940'>lies</span> <span m='1178340'>in if</span> <span m='1178680'>and
  only</span> <span m='1179110'>if</span> <span m='1179350'>these</span> <span m='1179827'>can
  be</span> <span m='1180304'>re-written</span> <span m='1180781'>with just</span>
  <span m='1181258'>the</span> <span m='1181735'>logical operators,</span> <span m='1183170'>and,</span>
  <span m='1183480'>and,</span> <span m='1183950'>not.</span> </p><p><span m='1184700'>So</span>
  <span m='1185553'>another</span> <span m='1185966'>way of</span> <span m='1186380'>expressing</span>
  <span m='1187210'>red and</span> <span m='1187520'>green</span> <span m='1187830'>is
  to</span> <span m='1188300'>say that you</span> <span m='1188430'>can't</span> <span
  m='1189023'>have the</span> <span m='1189376'>scenario</span> <span m='1190250'>where</span>
  <span m='1190440'>both</span> <span m='1190836'>is</span> <span m='1191630'>not</span>
  <span m='1192010'>red, and</span> <span m='1192460'>it's</span> <span m='1192730'>not</span>
  <span m='1193080'>green.</span> <span m='1194180'>And</span> <span m='1194630'>I'm
  not</span> <span m='1194790'>going to</span> <span m='1195070'>go</span> <span m='1195320'>over</span>
  <span m='1195700'>that for,</span> <span m='1196000'>implies,</span> <span m='1196350'>and,
  if</span> <span m='1196700'>and only if,</span> <span m='1197740'>just</span> <span
  m='1197900'>for</span> <span m='1197980'>the</span> <span m='1198080'>sake</span>
  <span m='1198280'>of</span> <span m='1198727'>time.</span> </p><p><span m='1200962'>So</span>
  <span m='1201856'>that's</span> <span m='1202310'>just a</span> <span m='1202635'>review</span>
  <span m='1202960'>of the</span> <span m='1203415'>logical</span> <span m='1203870'>operators,</span>
  <span m='1204325'>and now</span> <span m='1204780'>we're going to</span> <span m='1205170'>go
  into</span> <span m='1205560'>the temporal</span> <span m='1205950'>operators.</span>
  </p><p><span m='1206340'>So</span> <span m='1207115'>when we're</span> <span m='1207590'>talking
  about our</span> <span m='1208065'>autonomous</span> <span m='1208540'>car,</span>
  <span m='1209490'>what</span> <span m='1209640'>are</span> <span m='1209760'>some</span>
  <span m='1210320'>useful</span> <span m='1211070'>temporal</span> <span m='1211500'>operators?</span>
  <span m='1212360'>Because</span> <span m='1212640'>up until</span> <span m='1213060'>now,</span>
  <span m='1213480'>we</span> <span m='1213630'>just</span> <span m='1213840'>are
  describing</span> <span m='1214260'>of</span> <span m='1214310'>the</span> <span
  m='1214410'>first</span> <span m='1214630'>state</span> <span m='1215020'>in our</span>
  <span m='1215430'>sequence,</span> <span m='1215840'>which isn't</span> <span m='1216290'>really</span>
  <span m='1216490'>useful</span> <span m='1216740'>if</span> <span m='1217050'>we</span>
  <span m='1217170'>want</span> <span m='1217420'>to</span> <span m='1217860'>talk</span>
  <span m='1218130'>about</span> <span m='1218400'>the entire</span> <span m='1219326'>set</span>
  <span m='1219790'>of sequences</span> <span m='1221522'>[INAUDIBLE]</span> <span
  m='1221998'>states.</span> </p><p><span m='1222950'>So</span> <span m='1223726'>what
  do</span> <span m='1224082'>you guys</span> <span m='1224440'>think</span> <span
  m='1224620'>are some mutual</span> <span m='1224790'>things</span> <span m='1224990'>that</span>
  <span m='1225120'>we</span> <span m='1225270'>want</span> <span m='1225500'>to be
  able</span> <span m='1225730'>to</span> <span m='1225890'>describe?</span> <span
  m='1226890'>I know</span> <span m='1227226'>Ben touched</span> <span m='1227562'>on</span>
  <span m='1227900'>some of</span> <span m='1228180'>them</span> <span m='1228410'>at</span>
  <span m='1228880'>the beginning,</span> <span m='1229350'>but if</span> <span m='1229820'>you
  guys could</span> <span m='1230000'>recount</span> <span m='1230490'>some of them.</span>
  </p><p><span m='1230980'>Yes.</span> </p><p><span m='1231470'>AUDIENCE:</span> <span
  m='1231715'>State</span> <span m='1231960'>connection.</span> </p><p><span m='1232940'>ELLIE:</span>
  <span m='1233185'>Mm-hmm.</span> <span m='1233430'>State</span> <span m='1233860'>connections.</span>
  </p><p><span m='1234830'>So</span> <span m='1238060'>exactly.</span> <span m='1238510'>So</span>
  <span m='1238800'>if</span> <span m='1238940'>I'm in</span> <span m='1239060'>a</span>
  <span m='1239390'>state</span> <span m='1239690'>right</span> <span m='1239820'>now,</span>
  <span m='1240445'>might there</span> <span m='1240800'>be</span> <span m='1240930'>concerns
  about</span> <span m='1241390'>the next</span> <span m='1241850'>state?</span> <span
  m='1242130'>Is that</span> <span m='1242475'>kind of like</span> <span m='1242820'>what</span>
  <span m='1242960'>you're</span> <span m='1243080'>saying?</span> <span m='1244234'>Exactly.</span>
  <span m='1244691'>Yeah.</span> <span m='1245150'>So</span> <span m='1245700'>next</span>
  <span m='1246070'>is</span> <span m='1246240'>one of the</span> <span m='1246737'>things
  that</span> <span m='1247234'>we might be</span> <span m='1247731'>concerned about,</span>
  <span m='1249222'>the next</span> <span m='1249719'>state.</span> </p><p><span m='1256677'>Are
  there</span> <span m='1257174'>any other</span> <span m='1257671'>tings you guys
  can</span> <span m='1258168'>think of?</span> </p><p><span m='1260156'>AUDIENCE:</span>
  <span m='1260280'>Always</span> <span m='1260404'>or</span> <span m='1260653'>[INAUDIBLE]</span>
  </p><p><span m='1261647'>ELLIE:</span> <span m='1261895'>Yes,</span> <span m='1262144'>exactly.</span>
  <span m='1262641'>Always.</span> </p><p><span m='1269599'>So</span> <span m='1274569'>like
  Ben said,</span> <span m='1275066'>we always</span> <span m='1275563'>want to follow</span>
  <span m='1276110'>the speed</span> <span m='1276290'>limit. We</span> <span m='1276680'>always
  want to</span> <span m='1277070'>be under</span> <span m='1277460'>35</span> <span
  m='1277895'>miles an hour,</span> <span m='1278330'>or whatever</span> <span m='1278680'>the
  speed</span> <span m='1279030'>limit</span> <span m='1279390'>is.</span> <span m='1280332'>Anything
  else?</span> </p><p><span m='1282220'>AUDIENCE:</span> <span m='1282310'>Until.</span>
  </p><p><span m='1282835'>ELLIE:</span> <span m='1283052'>Until.</span> <span m='1283570'>Yep.</span>
  <span m='1284640'>So</span> <span m='1285080'>like</span> <span m='1285430'>he</span>
  <span m='1285590'>said,</span> <span m='1285820'>you want</span> <span m='1286290'>to</span>
  <span m='1286480'>be</span> <span m='1286650'>stopped</span> <span m='1287470'>until</span>
  <span m='1288060'>the</span> <span m='1288190'>light</span> <span m='1288360'>turns</span>
  <span m='1288690'>green.</span> </p><p><span m='1290020'>Yes.</span> </p><p><span
  m='1290495'>AUDIENCE:</span> <span m='1290732'>Eventually.</span> </p><p><span m='1291445'>ELLIE:</span>
  <span m='1291682'>Eventually.</span> <span m='1291920'>Yep.</span> <span m='1292400'>So</span>
  <span m='1293160'>we</span> <span m='1293320'>eventually</span> <span m='1295380'>want</span>
  <span m='1295630'>to</span> <span m='1295770'>get</span> <span m='1295920'>gas.</span>
  <span m='1298152'>And</span> <span m='1300567'>eventually.</span> <span m='1302982'>Any
  other</span> <span m='1303465'>things?</span> <span m='1303948'>Yes.</span> </p><p><span
  m='1304431'>AUDIENCE:</span> <span m='1304551'>At</span> <span m='1304671'>this</span>
  <span m='1304791'>state.</span> </p><p><span m='1305397'>ELLIE:</span> <span m='1305517'>At</span>
  <span m='1305637'>this</span> <span m='1305757'>state.</span> <span m='1305880'>Yep.</span>
  <span m='1306380'>And</span> <span m='1306600'>so,</span> <span m='1306960'>at</span>
  <span m='1307330'>this</span> <span m='1307630'>state,</span> <span m='1308440'>is</span>
  <span m='1308800'>kind</span> <span m='1309130'>of</span> <span m='1309220'>what</span>
  <span m='1309510'>the logical</span> <span m='1309870'>operators</span> <span m='1310080'>were
  doing</span> <span m='1310270'>at the</span> <span m='1310750'>beginning,</span>
  <span m='1311020'>but I agree</span> <span m='1311350'>that's something</span> <span
  m='1311680'>we have</span> <span m='1311930'>to</span> <span m='1312130'>be able</span>
  <span m='1312340'>to</span> <span m='1312580'>express.</span> <span m='1313580'>So</span>
  <span m='1314740'>that's</span> <span m='1315160'>not a</span> <span m='1315577'>specific</span>
  <span m='1315994'>temporal</span> <span m='1316411'>operator,</span> <span m='1316830'>but</span>
  <span m='1317000'>it's included</span> <span m='1317470'>in the logical</span> <span
  m='1317940'>one, so I'll</span> <span m='1318240'>just write it</span> <span m='1318740'>up
  here</span> <span m='1319240'>for you.</span> </p><p><span m='1320330'>AUDIENCE:</span>
  <span m='1320565'>Can</span> <span m='1320800'>I ask a</span> <span m='1321270'>question?</span>
  </p><p><span m='1321740'>ELLIE:</span> <span m='1321896'>Uh</span> <span m='1322052'>huh.</span>
  </p><p><span m='1322210'>AUDIENCE:</span> <span m='1322293'>So</span> <span m='1322376'>the</span>
  <span m='1322460'>logical</span> <span m='1323060'>operators,</span> <span m='1323630'>are
  they</span> <span m='1323940'>acting on</span> <span m='1324416'>the--</span> <span
  m='1324892'>so</span> <span m='1325368'>they're acting</span> <span m='1325844'>for
  a state?</span> <span m='1326320'>They're not</span> <span m='1326796'>acting on
  the</span> <span m='1327272'>entire</span> <span m='1327748'>chain.</span> </p><p><span
  m='1328860'>ELLIE:</span> <span m='1328990'>They</span> <span m='1329120'>act</span>
  <span m='1329250'>for a state.</span> <span m='1330010'>And</span> <span m='1330100'>so</span>
  <span m='1330200'>if</span> <span m='1330400'>you</span> <span m='1330640'>just</span>
  <span m='1331080'>wrote</span> <span m='1331786'>the</span> <span m='1332232'>logical</span>
  <span m='1332680'>operators,</span> <span m='1334460'>just by the</span> <span m='1334910'>definition</span>
  <span m='1335360'>of</span> <span m='1335560'>LTL,</span> <span m='1335990'>it means</span>
  <span m='1336590'>let's</span> <span m='1336970'>just</span> <span m='1337350'>analyze</span>
  <span m='1338110'>the</span> <span m='1338430'>first</span> <span m='1338590'>state</span>
  <span m='1338940'>and</span> <span m='1339060'>see if</span> <span m='1339300'>it's</span>
  <span m='1339550'>true.</span> <span m='1341030'>And so</span> <span m='1341150'>it</span>
  <span m='1341250'>won't</span> <span m='1341710'>tell</span> <span m='1342170'>us
  anything</span> <span m='1342350'>about the</span> <span m='1342550'>third state
  or the</span> <span m='1342970'>fourth</span> <span m='1343230'>state or</span>
  <span m='1343640'>the</span> <span m='1343740'>second</span> <span m='1343960'>state,</span>
  <span m='1344545'>which is</span> <span m='1344890'>why</span> <span m='1345050'>we</span>
  <span m='1345160'>have</span> <span m='1345340'>to</span> <span m='1345460'>look</span>
  <span m='1345670'>at</span> <span m='1346310'>the next</span> <span m='1346570'>state.</span>
  <span m='1347059'>So yeah.</span> </p><p><span m='1349015'>Any</span> <span m='1349504'>other
  questions?</span> <span m='1352438'>OK.</span> </p><p><span m='1354883'>So</span>
  <span m='1356350'>like</span> <span m='1356839'>you said,</span> <span m='1357560'>next
  is an</span> <span m='1358048'>important</span> <span m='1358536'>one.</span> <span
  m='1359024'>So</span> <span m='1360488'>right</span> <span m='1360976'>here we</span>
  <span m='1361464'>consider</span> <span m='1361960'>OK,</span> <span m='1362240'>the
  next</span> <span m='1362500'>light</span> <span m='1362700'>will</span> <span m='1362920'>be</span>
  <span m='1363290'>green.</span> <span m='1367412'>And</span> <span m='1367870'>until</span>
  <span m='1369060'>is</span> <span m='1369250'>the one</span> <span m='1369620'>that</span>
  <span m='1370275'>she mentioned,</span> <span m='1370750'>so</span> <span m='1371376'>the</span>
  <span m='1372370'>light will be</span> <span m='1372790'>red</span> <span m='1373500'>until
  it</span> <span m='1373990'>becomes</span> <span m='1374480'>green</span> <span
  m='1378420'>eventually.</span> <span m='1380050'>So</span> <span m='1380930'>the
  light will</span> <span m='1381420'>eventually</span> <span m='1382020'>at some
  point in</span> <span m='1382450'>the future</span> <span m='1382880'>turn</span>
  <span m='1383310'>green.</span> <span m='1383620'>So</span> <span m='1383930'>you
  might</span> <span m='1384140'>be</span> <span m='1384360'>waiting</span> <span
  m='1384750'>at the</span> <span m='1384930'>red light</span> <span m='1385380'>for</span>
  <span m='1385500'>a</span> <span m='1385620'>long</span> <span m='1385920'>time,</span>
  <span m='1386270'>but</span> <span m='1386360'>eventually</span> <span m='1386780'>it's</span>
  <span m='1386980'>going</span> <span m='1387150'>to</span> <span m='1387260'>turn</span>
  <span m='1387380'>green</span> <span m='1387570'>for</span> <span m='1387720'>us.</span>
  <span m='1389826'>The</span> <span m='1390300'>light will</span> <span m='1390600'>always</span>
  <span m='1390990'>be</span> <span m='1391110'>red,</span> <span m='1391700'>so I
  guess</span> <span m='1392050'>you're</span> <span m='1392400'>stuck at the</span>
  <span m='1392730'>traffic light</span> <span m='1393227'>for a long</span> <span
  m='1393724'>time,</span> <span m='1394720'>or</span> <span m='1395150'>globally--</span>
  <span m='1395410'>that's</span> <span m='1395710'>another name</span> <span m='1395890'>for</span>
  <span m='1396260'>always.</span> </p><p><span m='1398660'>And</span> <span m='1399050'>lastly,</span>
  <span m='1399980'>this on is</span> <span m='1400445'>a little bit</span> <span
  m='1403750'>less</span> <span m='1403920'>intuitive.</span> <span m='1405040'>So</span>
  <span m='1405220'>what</span> <span m='1405430'>this</span> <span m='1405640'>is</span>
  <span m='1405730'>saying</span> <span m='1406420'>is</span> <span m='1407030'>the
  light</span> <span m='1407370'>will</span> <span m='1407530'>always</span> <span
  m='1407920'>be</span> <span m='1408540'>red</span> <span m='1409255'>until</span>
  <span m='1410380'>another</span> <span m='1411010'>circumstance</span> <span m='1411230'>coincides</span>
  <span m='1412050'>with</span> <span m='1412120'>the</span> <span m='1412250'>same</span>
  <span m='1412630'>state.</span> <span m='1413542'>So the</span> <span m='1414000'>light
  will be</span> <span m='1414390'>always</span> <span m='1414790'>red</span> <span
  m='1415090'>until</span> <span m='1415480'>the</span> <span m='1415600'>car</span>
  <span m='1415990'>gets</span> <span m='1416190'>gas.</span> <span m='1416540'>And
  then</span> <span m='1416940'>after</span> <span m='1418180'>it</span> <span m='1418340'>gets</span>
  <span m='1418540'>its</span> <span m='1418690'>gas,</span> <span m='1419110'>then
  the</span> <span m='1419530'>red</span> <span m='1419860'>is released,</span> <span
  m='1420520'>and the</span> <span m='1420660'>light</span> <span m='1420940'>can</span>
  <span m='1421170'>be</span> <span m='1421340'>either</span> <span m='1421710'>green</span>
  <span m='1421980'>or</span> <span m='1422140'>red</span> <span m='1422330'>after</span>
  <span m='1422776'>that.</span> <span m='1423670'>So</span> <span m='1423850'>you
  have</span> <span m='1424200'>red</span> <span m='1424550'>red red</span> <span
  m='1424900'>red</span> <span m='1425150'>red</span> <span m='1425593'>until</span>
  <span m='1426480'>we have</span> <span m='1426740'>both</span> <span m='1427150'>red</span>
  <span m='1427870'>and</span> <span m='1428270'>gas.</span> <span m='1429100'>And</span>
  <span m='1429560'>then</span> <span m='1429870'>it can be green</span> <span m='1430210'>or
  it</span> <span m='1430440'>can</span> <span m='1430580'>be</span> <span m='1430690'>red</span>
  <span m='1430840'>[INAUDIBLE]</span> <span m='1431515'>it's</span> <span m='1431800'>not</span>
  <span m='1432000'>constrained</span> <span m='1432335'>to being</span> <span m='1432670'>red.</span>
  </p><p><span m='1432930'>Does that</span> <span m='1433397'>make sense?</span> <span
  m='1433864'>That</span> <span m='1434331'>one's a little bit</span> <span m='1434800'>less</span>
  <span m='1435010'>intuitive,</span> <span m='1435220'>so--</span> <span m='1436956'>is
  that</span> <span m='1437438'>good?</span> <span m='1441294'>OK.</span> </p><p><span
  m='1444200'>All right.</span> <span m='1444520'>So</span> <span m='1444620'>now</span>
  <span m='1445222'>that</span> <span m='1445604'>we've gone</span> <span m='1445986'>over</span>
  <span m='1446370'>just</span> <span m='1446550'>the intuitive</span> <span m='1447966'>understanding</span>
  <span m='1448440'>of that,</span> <span m='1448700'>I'm going</span> <span m='1449110'>to
  give you</span> <span m='1449520'>the actual</span> <span m='1449930'>syntax</span>
  <span m='1450170'>for</span> <span m='1450662'>that.</span> <span m='1452138'>So</span>
  <span m='1453122'>x</span> <span m='1453614'>is representative</span> <span m='1455090'>of
  next.</span> <span m='1456570'>So</span> <span m='1456900'>in the</span> <span m='1457200'>first</span>
  <span m='1457535'>state,</span> <span m='1457870'>we</span> <span m='1457950'>don't</span>
  <span m='1458390'>care</span> <span m='1459180'>if</span> <span m='1459390'>p</span>
  <span m='1459690'>is</span> <span m='1460110'>true.</span> <span m='1460765'>p</span>
  <span m='1461040'>could</span> <span m='1461260'>be</span> <span m='1461430'>not</span>
  <span m='1461580'>true,</span> <span m='1461845'>p could</span> <span m='1462110'>be</span>
  <span m='1462260'>true. It</span> <span m='1462480'>doesn't</span> <span m='1462690'>matter.</span>
  <span m='1463390'>But</span> <span m='1463440'>in</span> <span m='1463530'>the</span>
  <span m='1463650'>second</span> <span m='1464070'>state,</span> <span m='1465140'>the</span>
  <span m='1465420'>next one up</span> <span m='1465680'>in the</span> <span m='1466030'>first</span>
  <span m='1466330'>state,</span> <span m='1466620'>p,</span> <span m='1466830'>has</span>
  <span m='1467070'>to</span> <span m='1467170'>hold</span> <span m='1468090'>in</span>
  <span m='1468180'>order</span> <span m='1468570'>for</span> <span m='1468810'>xp</span>
  <span m='1469610'>to</span> <span m='1470120'>be a</span> <span m='1470570'>true
  statement</span> <span m='1470890'>about our</span> <span m='1471355'>sequence of</span>
  <span m='1471820'>states.</span> </p><p><span m='1472750'>So</span> <span m='1473230'>what</span>
  <span m='1473550'>do you</span> <span m='1473710'>guys</span> <span m='1473840'>think</span>
  <span m='1479241'>if I</span> <span m='1479732'>wrote this?</span> <span m='1483169'>What
  would</span> <span m='1483660'>that mean?</span> </p><p><span m='1489061'>AUDIENCE:</span>
  <span m='1489306'>Different</span> <span m='1489552'>state</span> <span m='1490043'>[INAUDIBLE]</span>
  </p><p><span m='1491025'>ELLIE:</span> <span m='1491270'>Yep.</span> <span m='1491516'>So</span>
  <span m='1492007'>this</span> <span m='1492498'>one over</span> <span m='1492989'>here?</span>
  </p><p><span m='1493480'>AUDIENCE:</span> <span m='1493730'>Sure.</span> <span m='1493980'>[INAUDIBLE]</span>
  </p><p><span m='1494638'>ELLIE:</span> <span m='1494887'>Yeah.</span> <span m='1495136'>Perfect.</span>
  </p><p><span m='1497626'>All right.</span> <span m='1498124'>The until</span> <span
  m='1498622'>operator.</span> <span m='1500116'>The until operator</span> <span m='1500620'>essentially</span>
  <span m='1501620'>says,</span> <span m='1503510'>like</span> <span m='1504050'>Ben</span>
  <span m='1504260'>said,</span> <span m='1504650'>we're</span> <span m='1504790'>stopped</span>
  <span m='1505250'>until</span> <span m='1505750'>the</span> <span m='1505940'>light</span>
  <span m='1506350'>is green.</span> </p><p><span m='1507580'>So</span> <span m='1507690'>if</span>
  <span m='1507780'>you</span> <span m='1507930'>have</span> <span m='1509340'>p</span>
  <span m='1509690'>until</span> <span m='1510060'>w,</span> <span m='1510510'>you</span>
  <span m='1510960'>just</span> <span m='1511340'>p has to be</span> <span m='1511590'>true
  at</span> <span m='1511850'>every state</span> <span m='1512090'>until</span> <span
  m='1512446'>w,</span> <span m='1513160'>and after</span> <span m='1513410'>that</span>
  <span m='1513695'>point,</span> <span m='1513980'>p</span> <span m='1514110'>can</span>
  <span m='1514560'>be</span> <span m='1514720'>whatever</span> <span m='1515420'>it</span>
  <span m='1515540'>wants</span> <span m='1515720'>to</span> <span m='1515900'>be.</span>
  </p><p><span m='1518730'>p</span> <span m='1519000'>eventually,</span> <span m='1519740'>or</span>
  <span m='1520040'>future</span> <span m='1520440'>operator,</span> <span m='1521340'>says</span>
  <span m='1522270'>that</span> <span m='1522420'>at</span> <span m='1522770'>some
  point in the</span> <span m='1523020'>future</span> <span m='1523550'>we</span>
  <span m='1523890'>will</span> <span m='1523980'>get</span> <span m='1524160'>gas.</span>
  <span m='1526198'>However it's</span> <span m='1526610'>important</span> <span m='1526930'>to
  note--</span> <span m='1527600'>I know</span> <span m='1527850'>when we</span> <span
  m='1528110'>talked</span> <span m='1528370'>about</span> <span m='1528620'>getting</span>
  <span m='1528850'>gas</span> <span m='1529140'>we</span> <span m='1529350'>said,</span>
  <span m='1529530'>oh, we have</span> <span m='1529870'>to</span> <span m='1530010'>always</span>
  <span m='1530520'>get</span> <span m='1530820'>gas</span> <span m='1531723'>at some
  point</span> <span m='1532206'>in the future,</span> <span m='1532840'>but</span>
  <span m='1533160'>the</span> <span m='1533310'>future</span> <span m='1533720'>eventually</span>
  <span m='1534166'>operator</span> <span m='1535685'>is</span> <span m='1536040'>just</span>
  <span m='1536260'>at</span> <span m='1537000'>one point in</span> <span m='1537190'>the</span>
  <span m='1537560'>future.</span> <span m='1538050'>So</span> <span m='1538560'>once</span>
  <span m='1538780'>you</span> <span m='1538950'>get</span> <span m='1539160'>gas,
  you don't have</span> <span m='1539580'>to</span> <span m='1539830'>get it</span>
  <span m='1539950'>again.</span> </p><p><span m='1540240'>Yes.</span> </p><p><span
  m='1540750'>AUDIENCE:</span> <span m='1540803'>On</span> <span m='1540856'>the</span>
  <span m='1540910'>previous</span> <span m='1541090'>slide</span> <span m='1541310'>you
  had</span> <span m='1541480'>a</span> <span m='1541660'>not</span> <span m='1542050'>at
  the bottom</span> <span m='1542780'>that said</span> <span m='1543764'>that</span>
  <span m='1544256'>w</span> <span m='1544750'>is required</span> <span m='1544980'>to
  become</span> <span m='1545372'>true.</span> <span m='1545764'>Does that mean</span>
  <span m='1546156'>an</span> <span m='1546550'>until</span> <span m='1547030'>operator</span>
  <span m='1548010'>also</span> <span m='1548310'>implies</span> <span m='1548670'>a</span>
  <span m='1548940'>future operator</span> <span m='1549370'>on</span> <span m='1549839'>w?</span>
  </p><p><span m='1550777'>ELLIE:</span> <span m='1551011'>Yeah.</span> </p><p><span
  m='1551246'>AUDIENCE:</span> <span m='1551402'>All</span> <span m='1551558'>right.</span>
  <span m='1551715'>[INAUDIBLE]</span> </p><p><span m='1552184'>ELLIE:</span> <span
  m='1552301'>Yep.</span> <span m='1553591'>But it's</span> <span m='1554060'>the</span>
  <span m='1554529'>added condition</span> <span m='1554998'>that</span> <span m='1555470'>p
  will</span> <span m='1555660'>be true</span> <span m='1556006'>until</span> <span
  m='1556352'>the</span> <span m='1556700'>w.</span> </p><p><span m='1556940'>AUDIENCE:</span>
  <span m='1557066'>But</span> <span m='1557192'>like</span> <span m='1557320'>whenever</span>
  <span m='1557700'>you use</span> <span m='1557960'>until,</span> <span m='1558260'>you</span>
  <span m='1558560'>say</span> <span m='1558980'>p</span> <span m='1559475'>until</span>
  <span m='1559970'>w</span> <span m='1560465'>that</span> <span m='1560960'>you'd
  also have</span> <span m='1561455'>to add</span> <span m='1562940'>at</span> <span
  m='1563435'>some point</span> <span m='1563930'>in the future</span> <span m='1564425'>[INAUDIBLE]</span>
  </p><p><span m='1564920'>ELLIE:</span> <span m='1565167'>Yeah. Yep,</span> <span
  m='1565415'>you're right.</span> </p><p><span m='1569030'>AUDIENCE:</span> <span
  m='1569076'>Well,</span> <span m='1569122'>I</span> <span m='1569168'>mean,</span>
  <span m='1569214'>it</span> <span m='1569260'>would be</span> <span m='1569650'>possible</span>
  <span m='1569905'>that</span> <span m='1570160'>this</span> <span m='1570650'>stays</span>
  <span m='1571140'>p,</span> <span m='1571440'>right?</span> </p><p><span m='1572210'>ELLIE:</span>
  <span m='1572338'>It</span> <span m='1572466'>could.</span> <span m='1572595'>Yeah.</span>
  <span m='1572980'>But</span> <span m='1573160'>then</span> <span m='1573790'>if</span>
  <span m='1573990'>your</span> <span m='1574430'>system--</span> <span m='1574630'>that
  would</span> <span m='1575010'>be</span> <span m='1575390'>totally fine</span> <span
  m='1575770'>if</span> <span m='1576150'>you had your</span> <span m='1576310'>system</span>
  <span m='1576640'>just</span> <span m='1576850'>be</span> <span m='1576990'>p,</span>
  <span m='1577560'>but</span> <span m='1577870'>then</span> <span m='1578180'>the</span>
  <span m='1578450'>operator</span> <span m='1578950'>p</span> <span m='1579285'>until</span>
  <span m='1579620'>w</span> <span m='1580140'>wouldn't</span> <span m='1581040'>hold</span>
  <span m='1581510'>unless</span> <span m='1581980'>you had a</span> <span m='1582450'>w
  at</span> <span m='1582580'>some</span> <span m='1582880'>point</span> <span m='1583170'>in</span>
  <span m='1583270'>that</span> <span m='1583420'>sequence</span> <span m='1583770'>of</span>
  <span m='1583960'>p's.</span> </p><p><span m='1585388'>Does that</span> <span m='1585864'>make
  sense.</span> </p><p><span m='1586340'>AUDIENCE:</span> <span m='1586410'>Yeah.</span>
  <span m='1586780'>[INAUDIBLE]</span> <span m='1587530'>I</span> <span m='1587620'>guess
  it does</span> <span m='1587950'>if that's the</span> <span m='1588280'>way</span>
  <span m='1588520'>to do</span> <span m='1588995'>it, but</span> <span m='1589945'>it</span>
  <span m='1590420'>doesn't make</span> <span m='1590895'>sense</span> <span m='1591370'>[INAUDIBLE]</span>
  <span m='1591850'>it.</span> </p><p><span m='1596960'>ELLIE:</span> <span m='1597079'>So</span>
  <span m='1597198'>you're</span> <span m='1597317'>saying</span> <span m='1597439'>that
  we could have</span> <span m='1597918'>a bunch</span> <span m='1598397'>of p's,</span>
  <span m='1598876'>right?</span> <span m='1599355'>Is that what you're saying?</span>
  <span m='1601210'>And I'm</span> <span m='1601702'>saying</span> <span m='1602686'>that
  this</span> <span m='1604800'>is</span> <span m='1605315'>a</span> <span m='1605680'>fine</span>
  <span m='1605960'>state</span> <span m='1606300'>to have.</span> <span m='1606350'>You
  can</span> <span m='1606625'>have</span> <span m='1606900'>whatever</span> <span
  m='1607030'>you</span> <span m='1607100'>want.</span> <span m='1607300'>And</span>
  <span m='1607920'>we're</span> <span m='1608160'>just</span> <span m='1608530'>analyzing</span>
  <span m='1608900'>if a</span> <span m='1609470'>sentence</span> <span m='1610384'>is
  true</span> <span m='1610841'>about it.</span> </p><p><span m='1611755'>So</span>
  <span m='1612212'>this statement,</span> <span m='1613130'>it's</span> <span m='1613300'>not</span>
  <span m='1613697'>true--</span> <span m='1614890'>or,</span> <span m='1615280'>sorry.</span>
  <span m='1615660'>I'm saying</span> <span m='1616040'>that it's</span> <span m='1616420'>not</span>
  <span m='1616680'>true</span> <span m='1619476'>that</span> <span m='1619942'>we</span>
  <span m='1620408'>have</span> <span m='1620874'>p</span> <span m='1621340'>and</span>
  <span m='1621806'>lw</span> <span m='1623010'>because</span> <span m='1623280'>there's</span>
  <span m='1623550'>no</span> <span m='1623710'>w</span> <span m='1624147'>in our</span>
  <span m='1624584'>state.</span> <span m='1625460'>But</span> <span m='1625690'>if
  we</span> <span m='1626145'>add in a</span> <span m='1626600'>w somewhere</span>
  <span m='1627510'>and we</span> <span m='1627965'>keep all the</span> <span m='1628420'>p's,</span>
  <span m='1629350'>then</span> <span m='1630070'>it's</span> <span m='1630320'>true</span>
  <span m='1630630'>because</span> <span m='1630930'>we have</span> <span m='1631410'>p</span>
  <span m='1632370'>up until</span> <span m='1632850'>we get to</span> <span m='1633330'>a</span>
  <span m='1633810'>w.</span> <span m='1634963'>Did that</span> <span m='1635436'>make
  sense?</span> </p><p><span m='1635909'>AUDIENCE:</span> <span m='1636066'>It</span>
  <span m='1636223'>made sense</span> <span m='1636382'>that that's</span> <span m='1636855'>the
  rule,</span> <span m='1637510'>but it</span> <span m='1637720'>doesn't</span> <span
  m='1638060'>make sense to me</span> <span m='1638539'>why.</span> <span m='1639497'>Because
  the statement</span> <span m='1639976'>[INAUDIBLE]</span> <span m='1640455'>true</span>
  <span m='1640934'>and if</span> <span m='1641413'>w never</span> <span m='1641892'>appears.</span>
  <span m='1642850'>You have</span> <span m='1643329'>p until</span> <span m='1644287'>w,</span>
  <span m='1644766'>which</span> <span m='1645245'>never happened.</span> </p><p><span
  m='1646520'>ELLIE:</span> <span m='1646650'>Yeah.</span> <span m='1646780'>If</span>
  <span m='1646910'>w</span> <span m='1647300'>never happened,</span> <span m='1647690'>then
  it</span> <span m='1647920'>wouldn't be true.</span> </p><p><span m='1650330'>AUDIENCE:</span>
  <span m='1650436'>I</span> <span m='1650542'>mean,</span> <span m='1650650'>technically,</span>
  <span m='1651130'>for the</span> <span m='1651610'>English</span> <span m='1651850'>language</span>
  <span m='1652050'>it</span> <span m='1652250'>would be</span> <span m='1652470'>true.</span>
  </p><p><span m='1653670'>AUDIENCE:</span> <span m='1653803'>I</span> <span m='1653936'>guess</span>
  <span m='1654070'>it's</span> <span m='1654230'>not--</span> </p><p><span m='1654495'>AUDIENCE:</span>
  <span m='1654583'>If</span> <span m='1654671'>you</span> <span m='1654760'>have
  p</span> <span m='1655846'>out to</span> <span m='1656262'>infinity,</span> <span
  m='1657094'>and</span> <span m='1657510'>you</span> <span m='1657600'>never</span>
  <span m='1657900'>have</span> <span m='1658020'>w's.</span> <span m='1659120'>p</span>
  <span m='1659330'>until</span> <span m='1659700'>w</span> <span m='1660187'>is</span>
  <span m='1660674'>true.</span> </p><p><span m='1661650'>AUDIENCE:</span> <span m='1661700'>p</span>
  <span m='1661750'>until</span> <span m='1661800'>anything</span> <span m='1662150'>is</span>
  <span m='1662440'>true</span> <span m='1662860'>[INAUDIBLE]</span> </p><p><span
  m='1663280'>AUDIENCE:</span> <span m='1663320'>Like</span> <span m='1663360'>if</span>
  <span m='1663675'>you</span> <span m='1663990'>say</span> <span m='1664410'>that</span>
  <span m='1664560'>I'm</span> <span m='1664770'>hungry</span> <span m='1665040'>until</span>
  <span m='1665310'>I</span> <span m='1665570'>eat,</span> <span m='1665760'>and</span>
  <span m='1666116'>you never</span> <span m='1666472'>eat,</span> <span m='1666830'>then</span>
  <span m='1667050'>you will</span> <span m='1667260'>always</span> <span m='1667680'>be
  hungry.</span> </p><p><span m='1668125'>ELLIE:</span> <span m='1668273'>Oh,</span>
  <span m='1668421'>I</span> <span m='1668570'>see.</span> <span m='1670040'>So that</span>
  <span m='1670520'>makes sense</span> <span m='1671000'>in a</span> <span m='1671480'>logical
  sense,</span> <span m='1671960'>but that's not how</span> <span m='1672440'>it's
  described</span> <span m='1672920'>in</span> <span m='1673140'>LTL.</span> </p><p><span
  m='1673553'>PROFESSOR:</span> <span m='1673690'>There's</span> <span m='1673827'>also</span>
  <span m='1673966'>an</span> <span m='1674380'>operator</span> <span m='1674900'>that's</span>
  <span m='1675110'>sort</span> <span m='1675310'>of</span> <span m='1675640'>unofficial</span>
  <span m='1676380'>called</span> <span m='1676490'>the</span> <span m='1676580'>weak</span>
  <span m='1676820'>until,</span> <span m='1677850'>and</span> <span m='1678010'>that's</span>
  <span m='1678310'>sort</span> <span m='1678550'>of saying</span> <span m='1678730'>p</span>
  <span m='1679100'>until</span> <span m='1679560'>w,</span> <span m='1680030'>or</span>
  <span m='1680590'>always</span> <span m='1680880'>p.</span> <span m='1681720'>So</span>
  <span m='1682152'>that kind of</span> <span m='1683450'>gets</span> <span m='1683660'>rid</span>
  <span m='1683780'>of</span> <span m='1683840'>the</span> <span m='1683990'>condition</span>
  <span m='1684390'>that</span> <span m='1684480'>it reaches</span> <span m='1684740'>w</span>
  <span m='1685180'>at</span> <span m='1685380'>some point.</span> </p><p><span m='1685740'>AUDIENCE:</span>
  <span m='1685887'>It</span> <span m='1686035'>aligns</span> <span m='1686330'>more</span>
  <span m='1686680'>with the</span> <span m='1687130'>English, too.</span> </p><p><span
  m='1687593'>PROFESSOR:</span> <span m='1687824'>Yeah.</span> </p><p><span m='1688056'>ELLIE:</span>
  <span m='1688288'>Yeah.</span> </p><p><span m='1688520'>AUDIENCE:</span> <span m='1688565'>But</span>
  <span m='1688610'>just</span> <span m='1688655'>the</span> <span m='1688700'>until</span>
  <span m='1689030'>operator</span> <span m='1689250'>on</span> <span m='1689540'>its
  own</span> <span m='1689640'>is just</span> <span m='1689930'>sort</span> <span
  m='1690200'>of</span> <span m='1690290'>like</span> <span m='1690410'>a</span> <span
  m='1690520'>strong</span> <span m='1690785'>until.</span> </p><p><span m='1691922'>ELLIE:</span>
  <span m='1692141'>Yeah.</span> </p><p><span m='1692360'>PROFESSOR:</span> <span
  m='1692430'>So</span> <span m='1692500'>it</span> <span m='1692570'>adds</span>
  <span m='1692640'>the--</span> </p><p><span m='1693111'>AUDIENCE:</span> <span m='1693268'>Yeah,</span>
  <span m='1693425'>that's</span> <span m='1693582'>fine.</span> </p><p><span m='1694053'>ELLIE:</span>
  <span m='1694288'>OK.</span> </p><p><span m='1694524'>PROFESSOR:</span> <span m='1694618'>This</span>
  <span m='1694712'>is</span> <span m='1694806'>the</span> <span m='1694900'>way</span>
  <span m='1694995'>it works.</span> </p><p><span m='1695470'>ELLIE:</span> <span
  m='1695565'>Yeah.</span> <span m='1696540'>Sometimes--</span> <span m='1696980'>yeah,
  I get</span> <span m='1697420'>confused</span> <span m='1697860'>about this</span>
  <span m='1698300'>sometimes. I'll be like,</span> <span m='1698740'>why</span> <span
  m='1699080'>they</span> <span m='1699555'>necessarily</span> <span m='1700030'>[?
  chose any of these, ?]</span> <span m='1700505'>but,</span> <span m='1700980'>OK.</span>
  </p><p><span m='1701930'>And then</span> <span m='1702410'>the globally</span> <span
  m='1702780'>one,</span> <span m='1703644'>which we</span> <span m='1704076'>said--</span>
  <span m='1704508'>this is the one that</span> <span m='1704940'>you were just describing</span>
  <span m='1705330'>here</span> <span m='1705500'>[INAUDIBLE]</span> <span m='1705760'>when
  you were</span> <span m='1706170'>talking</span> <span m='1706390'>about the</span>
  <span m='1706775'>p at</span> <span m='1707160'>every</span> <span m='1707370'>single</span>
  <span m='1707610'>state</span> <span m='1707810'>in the</span> <span m='1708030'>future.</span>
  <span m='1710295'>And then the</span> <span m='1710748'>release</span> <span m='1711201'>operator</span>
  <span m='1712107'>is</span> <span m='1712560'>you</span> <span m='1712730'>have</span>
  <span m='1712940'>to</span> <span m='1713190'>have</span> <span m='1713380'>p</span>
  <span m='1713920'>until</span> <span m='1714230'>you</span> <span m='1714390'>have</span>
  <span m='1714720'>w,</span> <span m='1715430'>but</span> <span m='1715580'>p and</span>
  <span m='1715865'>w</span> <span m='1716390'>also</span> <span m='1716750'>have</span>
  <span m='1716940'>to</span> <span m='1717210'>share</span> <span m='1717880'>the</span>
  <span m='1718000'>same</span> <span m='1718250'>state</span> <span m='1718650'>when</span>
  <span m='1718960'>they</span> <span m='1719320'>switch</span> <span m='1720010'>from--</span>
  <span m='1721614'>so</span> <span m='1722510'>in</span> <span m='1722960'>until,</span>
  <span m='1724690'>you don't</span> <span m='1724880'>have to have the</span> <span
  m='1725350'>p here,</span> <span m='1726110'>but</span> <span m='1726390'>with</span>
  <span m='1726630'>release,</span> <span m='1727310'>you</span> <span m='1727460'>have</span>
  <span m='1727640'>to have the</span> <span m='1728030'>p and w</span> <span m='1728810'>occur
  in the</span> <span m='1729200'>same</span> <span m='1729530'>state.</span> <span
  m='1730522'>Does that</span> <span m='1731018'>make sense?</span> <span m='1732506'>Yes?</span>
  <span m='1733002'>OK.</span> </p><p><span m='1737466'>So</span> <span m='1737970'>just</span>
  <span m='1738310'>like</span> <span m='1738650'>before,</span> <span m='1739250'>operators</span>
  <span m='1739745'>can</span> <span m='1740240'>be</span> <span m='1740480'>described</span>
  <span m='1740870'>using</span> <span m='1741328'>not</span> <span m='1741786'>and
  and.</span> <span m='1743160'>The</span> <span m='1743310'>future,</span> <span
  m='1744120'>released,</span> <span m='1744490'>and the</span> <span m='1744870'>globally</span>
  <span m='1745380'>operators</span> <span m='1746030'>can</span> <span m='1746210'>also</span>
  <span m='1746480'>be</span> <span m='1746610'>described</span> <span m='1747600'>using</span>
  <span m='1748470'>other</span> <span m='1751640'>temporal</span> <span m='1752120'>operators.</span>
  <span m='1753030'>And</span> <span m='1753260'>so</span> <span m='1754190'>just</span>
  <span m='1754370'>as</span> <span m='1754610'>an</span> <span m='1754720'>exercise,</span>
  <span m='1756050'>can</span> <span m='1756230'>any of</span> <span m='1756490'>you</span>
  <span m='1756620'>guys</span> <span m='1756900'>tell</span> <span m='1757080'>me</span>
  <span m='1757360'>which--</span> <span m='1757790'>these are</span> <span m='1758070'>not
  in</span> <span m='1758450'>order--</span> <span m='1758670'>which of</span> <span
  m='1759070'>these</span> <span m='1759470'>line</span> <span m='1759690'>up</span>
  <span m='1760170'>with</span> <span m='1760880'>the</span> <span m='1761160'>other--</span>
  <span m='1761540'>like, whichever</span> <span m='1761976'>ones they line</span>
  <span m='1762412'>up with.</span> <span m='1763720'>And</span> <span m='1763870'>I'll
  give</span> <span m='1764060'>you</span> <span m='1764180'>guys</span> <span m='1764590'>like</span>
  <span m='1765390'>three</span> <span m='1765590'>minutes</span> <span m='1765920'>to
  just think about</span> <span m='1766383'>it,</span> <span m='1766846'>and then
  we'll</span> <span m='1767310'>work through it</span> <span m='1767680'>together</span>
  <span m='1768178'>on the</span> <span m='1768676'>board.</span> </p><p></p><p><span
  m='1853336'>All right,</span> <span m='1853834'>so have any of</span> <span m='1854332'>you
  guys</span> <span m='1854830'>thought about</span> <span m='1855328'>which ones</span>
  <span m='1855826'>might</span> <span m='1856324'>correlate</span> <span m='1856822'>to
  which ones?</span> <span m='1857818'>Does anyone have</span> <span m='1858316'>any</span>
  <span m='1858814'>suggestions?</span> <span m='1860806'>Yes.</span> </p><p><span
  m='1861304'>AUDIENCE:</span> <span m='1861428'>The</span> <span m='1861552'>first</span>
  <span m='1861676'>one's</span> <span m='1861802'>the top</span> <span m='1862300'>one.</span>
  </p><p><span m='1862798'>ELLIE:</span> <span m='1862964'>This</span> <span m='1863130'>one</span>
  <span m='1863296'>is the top</span> <span m='1863810'>one.</span> <span m='1863970'>That's</span>
  <span m='1864462'>exactly</span> <span m='1864954'>right.</span> <span m='1865446'>So</span>
  <span m='1868398'>let's continue this</span> <span m='1868890'>state</span> <span
  m='1869382'>again.</span> <span m='1870870'>So</span> <span m='1872176'>the</span>
  <span m='1872672'>statement,</span> <span m='1873170'>true,</span> <span m='1875510'>doesn't
  say</span> <span m='1875936'>anything about</span> <span m='1876362'>what</span>
  <span m='1876788'>the propositions</span> <span m='1877640'>are. It's</span> <span
  m='1878070'>just</span> <span m='1878280'>something</span> <span m='1878673'>that's
  true</span> <span m='1879066'>for all</span> <span m='1879460'>states, right?</span>
  <span m='1880996'>So if</span> <span m='1881420'>we're saying,</span> <span m='1881710'>true</span>
  <span m='1881980'>until</span> <span m='1882480'>pi,</span> <span m='1883490'>that
  means that you</span> <span m='1883865'>can</span> <span m='1884240'>have</span>
  <span m='1884460'>whatever</span> <span m='1884670'>you</span> <span m='1884850'>want</span>
  <span m='1885840'>until</span> <span m='1886300'>p</span> <span m='1886490'>occurs.</span>
  </p><p><span m='1888540'>So</span> <span m='1888930'>does that make</span> <span
  m='1889300'>sense</span> <span m='1889670'>that, at</span> <span m='1889940'>some
  point</span> <span m='1890353'>in the future,</span> <span m='1890766'>p has to</span>
  <span m='1891180'>occur,</span> <span m='1892500'>exactly</span> <span m='1893150'>because</span>
  <span m='1893550'>we</span> <span m='1893700'>had</span> <span m='1893940'>the</span>
  <span m='1894170'>strong</span> <span m='1894390'>until,</span> <span m='1895210'>right.</span>
  <span m='1896590'>Does that make sense to</span> <span m='1897050'>everyone?</span>
  <span m='1898430'>You guys want to</span> <span m='1898890'>see some</span> <span
  m='1899350'>[INAUDIBLE]?</span> </p><p><span m='1900280'>All right</span> <span
  m='1900490'>and</span> <span m='1900930'>now</span> <span m='1901205'>what</span>
  <span m='1901480'>about</span> <span m='1901800'>this</span> <span m='1902090'>one?</span>
  <span m='1902280'>We have</span> <span m='1903208'>not</span> <span m='1903672'>as</span>
  <span m='1904136'>not</span> <span m='1904600'>p.</span> <span m='1906460'>So</span>
  <span m='1907080'>this</span> <span m='1907230'>is</span> <span m='1907390'>saying</span>
  <span m='1907510'>that</span> <span m='1912410'>at</span> <span m='1912900'>some</span>
  <span m='1913390'>point,</span> <span m='1913890'>if you</span> <span m='1914110'>can't</span>
  <span m='1914545'>get a p set</span> <span m='1914980'>at some point</span> <span
  m='1915415'>in the</span> <span m='1915850'>future,</span> <span m='1916720'>you</span>
  <span m='1916870'>don't</span> <span m='1917050'>have</span> <span m='1917440'>p.</span>
  <span m='1917830'>So</span> <span m='1918220'>what</span> <span m='1918640'>do you
  think</span> <span m='1919010'>that</span> <span m='1919190'>would correspond</span>
  <span m='1919686'>to?</span> <span m='1920360'>If</span> <span m='1920590'>at some</span>
  <span m='1921082'>point in</span> <span m='1921574'>the future,</span> <span m='1922066'>you
  can't</span> <span m='1922558'>have the</span> <span m='1923050'>situation</span>
  <span m='1923542'>where there's</span> <span m='1924034'>not p.</span> </p><p><span
  m='1924526'>AUDIENCE:</span> <span m='1924649'>The</span> <span m='1924772'>third</span>
  <span m='1924895'>one.</span> </p><p><span m='1925510'>ELLIE:</span> <span m='1925633'>The</span>
  <span m='1925756'>third</span> <span m='1925879'>one?</span> <span m='1926002'>[INAUDIBLE]</span>
  <span m='1927980'>So that would</span> <span m='1928130'>be</span> <span m='1928583'>if</span>
  <span m='1929036'>you have</span> <span m='1929489'>p</span> <span m='1929942'>at
  every</span> <span m='1930395'>single state,</span> <span m='1931754'>then</span>
  <span m='1932207'>you would</span> <span m='1932660'>never</span> <span m='1932960'>have</span>
  <span m='1933320'>a situation</span> <span m='1934152'>where</span> <span m='1934570'>you
  don't</span> <span m='1934750'>have</span> <span m='1935140'>p,</span> <span m='1935530'>right?</span>
  </p><p><span m='1936640'>And so that</span> <span m='1937090'>leaves this</span>
  <span m='1937540'>last one.</span> <span m='1940262'>You</span> <span m='1940708'>don't
  have a</span> <span m='1941154'>scenario</span> <span m='1941900'>where you</span>
  <span m='1942300'>have</span> <span m='1943500'>not</span> <span m='1943770'>p</span>
  <span m='1944266'>until not</span> <span m='1945754'>w.</span> <span m='1947738'>So</span>
  <span m='1950218'>if you</span> <span m='1950714'>have</span> <span m='1951210'>not--</span>
  <span m='1953690'>OK.</span> <span m='1954186'>It's still a little</span> <span
  m='1954682'>hard.</span> <span m='1956170'>But</span> <span m='1958154'>I'll</span>
  <span m='1958650'>come back to</span> <span m='1959146'>that one at</span> <span
  m='1959642'>the end,</span> <span m='1960138'>OK?</span> <span m='1960650'>But it's</span>
  <span m='1960890'>just important to</span> <span m='1961120'>remember</span> <span
  m='1961620'>that</span> <span m='1961770'>you can</span> <span m='1963020'>describe</span>
  <span m='1964878'>these</span> <span m='1965372'>operators</span> <span m='1966360'>with</span>
  <span m='1967380'>similar</span> <span m='1967850'>to them</span> <span m='1968185'>so
  that your</span> <span m='1968520'>planner</span> <span m='1968940'>doesn't</span>
  <span m='1969240'>have</span> <span m='1969450'>to</span> <span m='1969630'>deal</span>
  <span m='1970020'>with</span> <span m='1970836'>the</span> <span m='1971200'>global</span>
  <span m='1971550'>operator</span> <span m='1971920'>or</span> <span m='1972140'>these</span>
  <span m='1972350'>operators--</span> <span m='1972540'>eventually</span> <span m='1973185'>operator,</span>
  <span m='1973790'>it can have</span> <span m='1974170'>less</span> <span m='1974805'>[INAUDIBLE]</span>
  <span m='1975290'>to deal with.</span> </p><p><span m='1978200'>So</span> <span
  m='1978685'>yeah,</span> <span m='1979170'>you guys were</span> <span m='1979655'>right.</span>
  <span m='1980140'>Perfect.</span> <span m='1981595'>And then</span> <span m='1982080'>this
  is just</span> <span m='1982565'>a recap of</span> <span m='1983050'>the different</span>
  <span m='1983550'>operators</span> <span m='1984600'>and</span> <span m='1985355'>the
  other</span> <span m='1985840'>ways that</span> <span m='1986325'>you can</span>
  <span m='1986810'>express them.</span> </p><p><span m='1990205'>And</span> <span
  m='1990690'>so</span> <span m='1991525'>there's</span> <span m='1992000'>a few more</span>
  <span m='1992475'>really cool things</span> <span m='1992950'>that you</span> <span
  m='1993080'>can do</span> <span m='1993390'>combining</span> <span m='1993760'>these</span>
  <span m='1994260'>different</span> <span m='1994600'>operators,</span> <span m='1995780'>and</span>
  <span m='1996100'>the</span> <span m='1996250'>first</span> <span m='1996610'>is</span>
  <span m='1997250'>that--</span> <span m='1999090'>remember</span> <span m='1999550'>when</span>
  <span m='2000010'>Ben</span> <span m='2000395'>was</span> <span m='2001510'>describing</span>
  <span m='2001980'>that</span> <span m='2002100'>we</span> <span m='2002220'>need</span>
  <span m='2002370'>to</span> <span m='2002520'>get</span> <span m='2002710'>gas?</span>
  <span m='2003130'>And we</span> <span m='2003620'>need to get it</span> <span m='2004110'>in
  the future,</span> <span m='2005090'>but even</span> <span m='2005580'>after we</span>
  <span m='2005800'>get</span> <span m='2006155'>gas,</span> <span m='2006510'>we're</span>
  <span m='2006750'>going to have to</span> <span m='2007105'>get it again</span>
  <span m='2007460'>some</span> <span m='2007660'>time in</span> <span m='2008112'>the
  future.</span> <span m='2010830'>So</span> <span m='2011040'>it's important</span>
  <span m='2011466'>that</span> <span m='2011892'>we can</span> <span m='2012318'>describe</span>
  <span m='2012744'>something that happens</span> <span m='2013170'>infinitely</span>
  <span m='2013735'>often.</span> <span m='2015010'>And</span> <span m='2015435'>the</span>
  <span m='2015860'>way</span> <span m='2016090'>that we describe</span> <span m='2016572'>that
  is saying</span> <span m='2017054'>that we</span> <span m='2018020'>always</span>
  <span m='2018680'>have</span> <span m='2019180'>the</span> <span m='2019260'>scenario</span>
  <span m='2020150'>where</span> <span m='2021440'>you</span> <span m='2021830'>will
  eventually</span> <span m='2022335'>reach</span> <span m='2022800'>p.</span> <span
  m='2024660'>So</span> <span m='2027460'>I'm trying to</span> <span m='2027930'>think
  of another way</span> <span m='2028400'>to describe</span> <span m='2028870'>that,
  but</span> <span m='2029340'>does that make</span> <span m='2029740'>sense</span>
  <span m='2030120'>that</span> <span m='2031460'>right</span> <span m='2031730'>now</span>
  <span m='2032040'>in</span> <span m='2032140'>the</span> <span m='2032240'>future,</span>
  <span m='2032510'>I'm going to</span> <span m='2032934'>get gas.</span> <span m='2033782'>And
  even</span> <span m='2034206'>after</span> <span m='2034630'>I</span> <span m='2034650'>get
  that</span> <span m='2034890'>gas,</span> <span m='2035980'>I</span> <span m='2036130'>will</span>
  <span m='2036250'>eventually</span> <span m='2036630'>in</span> <span m='2036750'>the</span>
  <span m='2036830'>future</span> <span m='2037520'>also</span> <span m='2037850'>need
  to</span> <span m='2038010'>get</span> <span m='2038260'>gas</span> <span m='2038480'>again,</span>
  <span m='2038750'>because</span> <span m='2039125'>your</span> <span m='2039500'>car
  will</span> <span m='2039980'>always be</span> <span m='2040375'>needing to</span>
  <span m='2040770'>get gas.</span> <span m='2041742'>Does</span> <span m='2042228'>that
  make sense?</span> <span m='2044658'>Cool.</span> </p><p><span m='2045630'>And then</span>
  <span m='2046116'>eventually</span> <span m='2047090'>forever</span> <span m='2047944'>is
  another</span> <span m='2048389'>scenario</span> <span m='2048580'>that's</span>
  <span m='2049000'>important</span> <span m='2049280'>to</span> <span m='2049380'>describe.</span>
  <span m='2051159'>So</span> <span m='2051923'>let's say</span> <span m='2052346'>that
  the traffic light</span> <span m='2052769'>will eventually</span> <span m='2053192'>turn</span>
  <span m='2053615'>green</span> <span m='2054040'>forever.</span> <span m='2055169'>We</span>
  <span m='2055429'>need</span> <span m='2055580'>to</span> <span m='2055710'>be</span>
  <span m='2055860'>able</span> <span m='2056040'>to</span> <span m='2056190'>say</span>
  <span m='2056590'>that</span> <span m='2056810'>at some</span> <span m='2057180'>point
  in the</span> <span m='2057550'>future,</span> <span m='2057985'>although we</span>
  <span m='2058420'>don't know</span> <span m='2058855'>when,</span> <span m='2059290'>the
  traffic</span> <span m='2059744'>light will</span> <span m='2060199'>turn</span>
  <span m='2060360'>green.</span> </p><p><span m='2061126'>So</span> <span m='2062290'>the</span>
  <span m='2062650'>future</span> <span m='2063543'>operator</span> <span m='2063936'>says</span>
  <span m='2064330'>that</span> <span m='2064980'>at</span> <span m='2065070'>some</span>
  <span m='2065310'>point</span> <span m='2065520'>in the</span> <span m='2066000'>future,</span>
  <span m='2066710'>you will</span> <span m='2067199'>have something</span> <span
  m='2067688'>come</span> <span m='2068179'>true.</span> <span m='2068844'>And</span>
  <span m='2069288'>so at</span> <span m='2069732'>this</span> <span m='2070179'>state,</span>
  <span m='2070959'>p</span> <span m='2071449'>becomes</span> <span m='2071770'>true,</span>
  <span m='2072540'>but</span> <span m='2072815'>the</span> <span m='2073090'>global</span>
  <span m='2073770'>operators</span> <span m='2074570'>that</span> <span m='2074730'>happened</span>
  <span m='2075489'>from</span> <span m='2075710'>this</span> <span m='2075969'>state</span>
  <span m='2076710'>forever</span> <span m='2077110'>afterwards,</span> <span m='2078480'>which</span>
  <span m='2078630'>is</span> <span m='2079290'>saying</span> <span m='2080250'>that</span>
  <span m='2080520'>you</span> <span m='2080670'>eventually</span> <span m='2082845'>will</span>
  <span m='2083280'>always</span> <span m='2083690'>have</span> <span m='2083850'>this</span>
  <span m='2084000'>state</span> <span m='2084239'>B</span> <span m='2084735'>be true.</span>
  </p><p><span m='2089199'>Do you</span> <span m='2089695'>guys have any questions</span>
  <span m='2090191'>on that?</span> <span m='2090687'>Did I</span> <span m='2091183'>explain
  that</span> <span m='2091679'>good enough.</span> </p><p><span m='2092175'>AUDIENCE:</span>
  <span m='2092343'>It</span> <span m='2092511'>seems</span> <span m='2092679'>weird</span>
  <span m='2092880'>to me</span> <span m='2093239'>that the</span> <span m='2093500'>gas
  tank</span> <span m='2093880'>is</span> <span m='2094170'>becoming</span> <span
  m='2094610'>this</span> <span m='2095490'>occasional</span> <span m='2095930'>temporal</span>
  <span m='2096370'>operator</span> <span m='2096810'>instead</span> <span m='2097070'>of</span>
  <span m='2097360'>just</span> <span m='2097570'>like</span> <span m='2097830'>the</span>
  <span m='2098165'>state that</span> <span m='2098500'>we</span> <span m='2098580'>actually</span>
  <span m='2098850'>have</span> <span m='2099120'>gas,</span> <span m='2099420'>would</span>
  <span m='2099750'>just</span> <span m='2100010'>be</span> <span m='2100470'>the
  logical</span> <span m='2100930'>thing</span> <span m='2101390'>that</span> <span
  m='2101850'>[INAUDIBLE]</span> </p><p><span m='2105070'>ELLIE:</span> <span m='2105170'>Oh,</span>
  <span m='2105270'>yeah, I--</span> </p><p><span m='2105650'>AUDIENCE:</span> <span
  m='2105795'>Why</span> <span m='2105940'>is</span> <span m='2106120'>the</span>
  <span m='2106240'>act</span> <span m='2106380'>of</span> <span m='2106675'>getting</span>
  <span m='2106970'>gas</span> <span m='2108500'>showing</span> <span m='2108865'>up</span>
  <span m='2109230'>here</span> <span m='2109360'>like that,</span> <span m='2110120'>versus</span>
  <span m='2110590'>just,</span> <span m='2110800'>you</span> <span m='2111070'>always</span>
  <span m='2111340'>need</span> <span m='2111816'>quantity of gas.</span> </p><p><span
  m='2112770'>ELLIE:</span> <span m='2112895'>That's</span> <span m='2113020'>true.</span>
  <span m='2113320'>We do always</span> <span m='2113480'>need</span> <span m='2113946'>some
  quantity</span> <span m='2114412'>of gas,</span> <span m='2114880'>and</span> <span
  m='2114970'>you</span> <span m='2115100'>would</span> <span m='2115280'>describe</span>
  <span m='2115470'>that,</span> <span m='2115883'>like you</span> <span m='2116296'>said,
  just</span> <span m='2116710'>with</span> <span m='2116880'>the always</span> <span
  m='2117317'>operator,</span> <span m='2117754'>but</span> <span m='2118191'>I guess</span>
  <span m='2118630'>my</span> <span m='2118790'>action</span> <span m='2119266'>of
  getting gas</span> <span m='2119742'>is I was thinking</span> <span m='2120218'>of
  actually</span> <span m='2120694'>driving up</span> <span m='2121170'>to the</span>
  <span m='2121640'>gas</span> <span m='2121995'>station</span> <span m='2122350'>and</span>
  <span m='2123760'>filling it</span> <span m='2124260'>up with gas.</span> <span
  m='2124760'>And</span> <span m='2125260'>if</span> <span m='2125760'>you didn't</span>
  <span m='2126260'>do that,</span> <span m='2127260'>you wouldn't</span> <span m='2129830'>be</span>
  <span m='2129960'>able</span> <span m='2130140'>to</span> <span m='2130660'>always</span>
  <span m='2130860'>have</span> <span m='2131010'>gas.</span> <span m='2131952'>Does
  that</span> <span m='2132423'>make sense?</span> </p><p><span m='2133840'>AUDIENCE:</span>
  <span m='2134070'>Right, so</span> <span m='2134300'>I</span> <span m='2134760'>would
  think</span> <span m='2135140'>that</span> <span m='2135500'>always</span> <span
  m='2135760'>having gas</span> <span m='2136070'>would</span> <span m='2136250'>make</span>
  <span m='2136703'>[INAUDIBLE]</span> <span m='2137156'>of you</span> <span m='2137609'>plan</span>
  <span m='2138062'>[INAUDIBLE]</span> </p><p><span m='2139880'>ELLIE:</span> <span
  m='2139995'>Yeah, and depending</span> <span m='2140110'>on how you</span> <span
  m='2140598'>make your model,</span> <span m='2141086'>you definitely</span> <span
  m='2141574'>could do</span> <span m='2142062'>that,</span> <span m='2142550'>and
  that</span> <span m='2142710'>definitely</span> <span m='2143040'>would</span> <span
  m='2143220'>satisfy</span> <span m='2143505'>the</span> <span m='2143790'>condition.</span>
  </p><p><span m='2144220'>[INTERPOSING VOICES]</span> </p><p><span m='2145080'>AUDIENCE:</span>
  <span m='2145200'>--the</span> <span m='2145320'>usual</span> <span m='2145440'>way</span>
  <span m='2145560'>to deal with</span> <span m='2146054'>it?</span> </p><p><span
  m='2148030'>ELLIE:</span> <span m='2148130'>Well, it</span> <span m='2148230'>depends</span>
  <span m='2148620'>on</span> <span m='2148770'>the</span> <span m='2148860'>situation.</span>
  <span m='2149460'>Maybe</span> <span m='2151290'>you</span> <span m='2151510'>[INAUDIBLE]</span>
  <span m='2151840'>want to</span> <span m='2152170'>say</span> <span m='2153490'>at</span>
  <span m='2153970'>some point in the</span> <span m='2154416'>future,</span> <span
  m='2154862'>the</span> <span m='2155310'>light</span> <span m='2155500'>will always</span>
  <span m='2156000'>be</span> <span m='2156500'>green, because</span> <span m='2157000'>you
  want to make sure</span> <span m='2157500'>that cars</span> <span m='2157770'>can
  go</span> <span m='2158135'>through,</span> <span m='2158500'>and there's a</span>
  <span m='2158680'>difference</span> <span m='2158965'>between</span> <span m='2159250'>red,</span>
  <span m='2159510'>and</span> <span m='2159790'>some</span> <span m='2160140'>point
  it will</span> <span m='2160440'>be</span> <span m='2160740'>green in</span> <span
  m='2160980'>the future.</span> </p><p><span m='2162370'>So</span> <span m='2162420'>it</span>
  <span m='2162540'>really</span> <span m='2162800'>depends</span> <span m='2163050'>on</span>
  <span m='2163110'>your</span> <span m='2163230'>model</span> <span m='2163480'>and</span>
  <span m='2163580'>how--</span> <span m='2163930'>I</span> <span m='2164040'>think</span>
  <span m='2165120'>the</span> <span m='2165240'>way</span> <span m='2165390'>you're
  saying</span> <span m='2165560'>it,</span> <span m='2165830'>where you</span> <span
  m='2166173'>always want</span> <span m='2166516'>to have</span> <span m='2166860'>gas,</span>
  <span m='2167490'>and</span> <span m='2167670'>the</span> <span m='2169128'>proposition</span>
  <span m='2170100'>gas</span> <span m='2171120'>is</span> <span m='2172450'>how much</span>
  <span m='2172860'>gas</span> <span m='2173270'>you have</span> <span m='2173380'>in
  your</span> <span m='2173640'>tank,</span> <span m='2173840'>and if you</span> <span
  m='2174340'>have it or</span> <span m='2174550'>don't,</span> <span m='2174910'>then
  I think</span> <span m='2175270'>that that</span> <span m='2175430'>would be a</span>
  <span m='2175650'>really</span> <span m='2175810'>good way</span> <span m='2176225'>to
  model</span> <span m='2176640'>it, too.</span> </p><p><span m='2177270'>AUDIENCE:</span>
  <span m='2177420'>Because</span> <span m='2177570'>this</span> <span m='2177720'>way,
  if you</span> <span m='2178170'>said,</span> <span m='2178350'>I</span> <span m='2178760'>have
  to</span> <span m='2178960'>get gas.</span> <span m='2179393'>I planned it</span>
  <span m='2179826'>for next</span> <span m='2180260'>week, but I've</span> <span
  m='2180510'>run out of</span> <span m='2180985'>gas</span> <span m='2181460'>this
  week.</span> <span m='2182885'>Do you</span> <span m='2183360'>know what I mean,</span>
  <span m='2183835'>like,</span> <span m='2184310'>you have to</span> <span m='2184790'>somehow</span>
  <span m='2185260'>be tracking the</span> <span m='2185760'>quantity</span> <span
  m='2186260'>of gas</span> <span m='2186760'>also.</span> </p><p><span m='2187260'>ELLIE:</span>
  <span m='2187362'>I</span> <span m='2187464'>agree.</span> <span m='2187566'>I</span>
  <span m='2187670'>agree.</span> <span m='2188080'>I was just using it</span> <span
  m='2188548'>as an example</span> <span m='2189016'>to</span> <span m='2189484'>explain</span>
  <span m='2189952'>the concept,</span> <span m='2190890'>but</span> <span m='2191290'>I</span>
  <span m='2191757'>agree that</span> <span m='2192224'>that definitely</span> <span
  m='2192691'>probably could be</span> <span m='2193158'>better with</span> <span
  m='2193625'>more work.</span> </p><p><span m='2194092'>AUDIENCE:</span> <span m='2194326'>Well,</span>
  <span m='2194560'>I</span> <span m='2194650'>think</span> <span m='2194940'>in</span>
  <span m='2195280'>both</span> <span m='2195650'>cases</span> <span m='2195890'>what</span>
  <span m='2196320'>it could</span> <span m='2196510'>represent</span> <span m='2196750'>is</span>
  <span m='2196980'>having</span> <span m='2197960'>gas</span> <span m='2198440'>all
  the</span> <span m='2198780'>time,</span> <span m='2199460'>or</span> <span m='2199830'>explicitly</span>
  <span m='2200350'>saying</span> <span m='2200710'>that</span> <span m='2201080'>you're
  going</span> <span m='2201320'>to</span> <span m='2201595'>be</span> <span m='2201870'>in</span>
  <span m='2202120'>gas</span> <span m='2202612'>stations</span> <span m='2204088'>eventually--</span>
  <span m='2206056'>always</span> <span m='2206548'>eventually.</span> <span m='2208024'>It</span>
  <span m='2208516'>depends on</span> <span m='2209010'>how--</span> <span m='2209475'>maybe
  we'd</span> <span m='2209800'>want</span> <span m='2209980'>to</span> <span m='2210510'>always</span>
  <span m='2211120'>have</span> <span m='2211450'>gas</span> <span m='2211750'>from</span>
  <span m='2212020'>a</span> <span m='2212290'>station,</span> <span m='2213260'>and</span>
  <span m='2213660'>also</span> <span m='2214060'>getting</span> <span m='2214330'>gas</span>
  <span m='2214540'>from it.</span> <span m='2215290'>So</span> <span m='2215530'>depending</span>
  <span m='2216376'>on how</span> <span m='2216800'>you</span> <span m='2217300'>want</span>
  <span m='2217590'>to model</span> <span m='2217800'>it,</span> <span m='2217910'>but</span>
  <span m='2218620'>I</span> <span m='2218710'>think</span> <span m='2218950'>both</span>
  <span m='2219160'>will</span> <span m='2219642'>work.</span> </p><p><span m='2223980'>AUDIENCE:</span>
  <span m='2224120'>So</span> <span m='2224260'>infinite</span> <span m='2224656'>and
  often,</span> <span m='2225450'>doesn't</span> <span m='2225930'>really</span> <span
  m='2226170'>care</span> <span m='2226470'>about</span> <span m='2227020'>how</span>
  <span m='2227320'>frequently--</span> </p><p><span m='2228460'>ELLIE:</span> <span
  m='2228606'>Yeah,</span> <span m='2228752'>it doesn't</span> <span m='2228900'>care
  how</span> <span m='2229340'>frequently.</span> </p><p><span m='2229780'>AUDIENCE:</span>
  <span m='2230000'>But</span> <span m='2230220'>[INAUDIBLE]</span> <span m='2230700'>for</span>
  <span m='2230960'>instance</span> <span m='2231360'>something</span> <span m='2231791'>that</span>
  <span m='2232222'>happens</span> <span m='2232653'>every</span> <span m='2233084'>60
  years.</span> <span m='2233950'>My</span> <span m='2234215'>system</span> <span
  m='2234480'>lifetime</span> <span m='2235050'>server is</span> <span m='2235310'>30</span>
  <span m='2235650'>years,</span> <span m='2236335'>which means</span> <span m='2236680'>something</span>
  <span m='2237080'>happens</span> <span m='2237300'>only</span> <span m='2237580'>once.</span>
  <span m='2237970'>So in</span> <span m='2238450'>this</span> <span m='2238810'>case,</span>
  <span m='2239140'>infinite</span> <span m='2239520'>and</span> <span m='2239770'>often,</span>
  <span m='2240573'>how</span> <span m='2240926'>can</span> <span m='2241280'>you
  filter</span> <span m='2241720'>a switch</span> <span m='2241940'>operator</span>
  <span m='2242320'>could</span> <span m='2242500'>be the</span> <span m='2242966'>same,
  right?</span> </p><p><span m='2244364'>ELLIE:</span> <span m='2244597'>Can</span>
  <span m='2244830'>you repeat</span> <span m='2245296'>that again</span> <span m='2245762'>[INAUDIBLE]</span>
  </p><p><span m='2246700'>AUDIENCE:</span> <span m='2246775'>So</span> <span m='2246850'>for</span>
  <span m='2246925'>instance</span> <span m='2247880'>something happens</span> <span
  m='2248130'>every</span> <span m='2248810'>60</span> <span m='2249210'>years.</span>
  <span m='2249970'>My system</span> <span m='2250300'>lifetime</span> <span m='2250520'>goes
  to</span> <span m='2250890'>30</span> <span m='2251260'>years.</span> <span m='2251540'>After
  30</span> <span m='2251890'>years,</span> <span m='2252070'>I have to</span> <span
  m='2252498'>get a re-up on</span> <span m='2252926'>the system.</span> <span m='2254210'>Then</span>
  <span m='2254640'>so</span> <span m='2254890'>during</span> <span m='2255190'>this</span>
  <span m='2255370'>[INAUDIBLE]</span> <span m='2256250'>only</span> <span m='2256690'>one</span>
  <span m='2257130'>thing happened.</span> <span m='2257790'>And so it</span> <span
  m='2258232'>happens</span> <span m='2258674'>off</span> <span m='2259116'>into</span>
  <span m='2259558'>infinity,</span> <span m='2260000'>but in the</span> <span m='2260442'>lifetime</span>
  <span m='2260890'>of the system,</span> <span m='2261230'>it only</span> <span m='2261555'>happened</span>
  <span m='2261880'>once,</span> <span m='2262555'>and</span> <span m='2262850'>therefore</span>
  <span m='2263480'>in</span> <span m='2263850'>this</span> <span m='2264190'>condition,</span>
  <span m='2264630'>the</span> <span m='2265050'>infinite and</span> <span m='2265470'>often</span>
  <span m='2266170'>should</span> <span m='2266570'>be</span> <span m='2266970'>set</span>
  <span m='2267340'>the same</span> <span m='2267550'>as</span> <span m='2267930'>the</span>
  <span m='2268150'>future,</span> <span m='2268350'>right,</span> <span m='2268600'>in</span>
  <span m='2269070'>the</span> <span m='2269190'>current</span> <span m='2269450'>state.</span>
  <span m='2269680'>Something</span> <span m='2270040'>happened in</span> <span m='2270425'>the
  future,</span> <span m='2270810'>I would</span> <span m='2271050'>say</span> <span
  m='2271250'>something</span> <span m='2271330'>could never</span> <span m='2271768'>happen
  again.</span> </p><p><span m='2273960'>ELLIE:</span> <span m='2274175'>Kind</span>
  <span m='2274390'>of.</span> <span m='2275200'>So</span> <span m='2275620'>when</span>
  <span m='2275970'>you're talking</span> <span m='2276320'>about a</span> <span m='2276670'>system</span>
  <span m='2277130'>that's dying</span> <span m='2277476'>after 30</span> <span m='2277822'>years,</span>
  <span m='2279746'>the</span> <span m='2280550'>LTL</span> <span m='2281080'>doesn't</span>
  <span m='2281420'>actual</span> <span m='2281840'>model something</span> <span m='2282320'>that</span>
  <span m='2282490'>ends.</span> <span m='2283294'>It would model</span> <span m='2283696'>something</span>
  <span m='2284098'>to</span> <span m='2284500'>infinity,</span> <span m='2285070'>although
  there</span> <span m='2285320'>is an</span> <span m='2285780'>extension to</span>
  <span m='2286250'>LTL</span> <span m='2286690'>that</span> <span m='2286870'>can</span>
  <span m='2287560'>incorporate</span> <span m='2288280'>that</span> <span m='2288550'>into</span>
  <span m='2288952'>it, having</span> <span m='2289354'>it</span> <span m='2291196'>have</span>
  <span m='2291582'>an</span> <span m='2291970'>actual</span> <span m='2292150'>end</span>
  <span m='2292590'>goal</span> <span m='2292780'>state.</span> <span m='2293335'>And</span>
  <span m='2293600'>I</span> <span m='2294010'>think in</span> <span m='2294220'>that
  case,</span> <span m='2294676'>then</span> <span m='2295590'>infinitely</span> <span
  m='2295880'>often</span> <span m='2296130'>would</span> <span m='2296430'>be</span>
  <span m='2297164'>different,</span> <span m='2297608'>and</span> <span m='2298052'>would--</span>
  <span m='2299384'>I</span> <span m='2300080'>don't</span> <span m='2300200'>know
  exactly</span> <span m='2300606'>how that</span> <span m='2301012'>would</span>
  <span m='2301420'>find</span> <span m='2301770'>that situation.</span> <span m='2302055'>Do
  you</span> <span m='2302340'>know,</span> <span m='2302560'>Ben?</span> <span m='2303052'>I
  know you had</span> <span m='2303544'>kind of--</span> </p><p><span m='2306004'>BEN:</span>
  <span m='2306252'>So</span> <span m='2306500'>there's</span> <span m='2306760'>something</span>
  <span m='2306910'>called</span> <span m='2307040'>metric</span> <span m='2307390'>temporal</span>
  <span m='2307655'>logic,</span> <span m='2308150'>which</span> <span m='2308450'>associates</span>
  <span m='2309110'>a</span> <span m='2309910'>time</span> <span m='2310270'>scale</span>
  <span m='2310660'>of each of</span> <span m='2310910'>these</span> <span m='2311080'>operators.</span>
  <span m='2312110'>So</span> <span m='2312160'>I think you'd</span> <span m='2312430'>have</span>
  <span m='2312580'>to</span> <span m='2312670'>use</span> <span m='2312850'>that</span>
  <span m='2313060'>if you</span> <span m='2313325'>were</span> <span m='2313590'>trying</span>
  <span m='2313870'>to</span> <span m='2314330'>express</span> <span m='2314720'>that
  you</span> <span m='2315205'>had to</span> <span m='2315690'>always</span> <span
  m='2315930'>meet</span> <span m='2316470'>those</span> <span m='2316840'>conditions</span>
  <span m='2317210'>still within</span> <span m='2317530'>your</span> <span m='2317942'>lifetime.</span>
  <span m='2318354'>You could have</span> <span m='2319980'>some</span> <span m='2320290'>sort</span>
  <span m='2320640'>of</span> <span m='2320890'>qualifier to</span> <span m='2321140'>these</span>
  <span m='2321540'>operators to</span> <span m='2321940'>specify</span> <span m='2322345'>an
  actual</span> <span m='2322750'>time</span> <span m='2323050'>[INAUDIBLE]</span>
  <span m='2324190'>where that</span> <span m='2324370'>operator</span> <span m='2324730'>[INAUDIBLE]</span>
  </p><p><span m='2325440'>AUDIENCE:</span> <span m='2325570'>So</span> <span m='2325700'>which
  would</span> <span m='2326156'>you file</span> <span m='2326612'>for the instance</span>
  <span m='2327070'>infinitely</span> <span m='2327390'>often</span> <span m='2328202'>[INAUDIBLE]
  scenario</span> <span m='2329014'>something</span> <span m='2329560'>at</span> <span
  m='2329930'>a little bit</span> <span m='2330070'>more</span> <span m='2330500'>frequent</span>
  <span m='2330850'>of a general system</span> <span m='2331350'>by</span> <span m='2331850'>the
  time,</span> <span m='2332456'>right.</span> <span m='2333230'>Now we have</span>
  <span m='2333460'>something</span> <span m='2334070'>you know [INAUDIBLE]</span>
  <span m='2334812'>100</span> <span m='2335304'>years</span> <span m='2335796'>ago</span>
  <span m='2336290'>for  years.</span> </p><p><span m='2337570'>BEN:</span> <span
  m='2337615'>You</span> <span m='2337660'>know,</span> <span m='2337960'>it's important</span>
  <span m='2338180'>that</span> <span m='2339860'>the</span> <span m='2340115'>LTL</span>
  <span m='2340370'>we're explaining</span> <span m='2340900'>here</span> <span m='2341120'>is
  only</span> <span m='2341310'>dealing</span> <span m='2341460'>with</span> <span
  m='2341735'>infinite</span> <span m='2342010'>states.</span> <span m='2342820'>So</span>
  <span m='2343180'>I</span> <span m='2343330'>agree,</span> <span m='2343690'>it's</span>
  <span m='2343870'>a</span> <span m='2343900'>little</span> <span m='2344050'>bit--</span>
  <span m='2344260'>you</span> <span m='2344750'>have to think</span> <span m='2345240'>about</span>
  <span m='2345420'>that</span> <span m='2345560'>process</span> <span m='2345825'>of</span>
  <span m='2346090'>how</span> <span m='2346200'>do apply</span> <span m='2346470'>something</span>
  <span m='2346820'>that</span> <span m='2347730'>goes</span> <span m='2347920'>on</span>
  <span m='2348040'>forever</span> <span m='2348500'>to a</span> <span m='2348740'>real</span>
  <span m='2348820'>system.</span> <span m='2349240'>It obviously</span> <span m='2349510'>doesn't</span>
  <span m='2349720'>model</span> <span m='2349995'>correctly.</span> </p><p><span
  m='2350760'>AUDIENCE:</span> <span m='2350881'>There</span> <span m='2351002'>has</span>
  <span m='2351125'>to be a</span> <span m='2351490'>way</span> <span m='2351730'>to--</span>
  <span m='2352076'>I mean</span> <span m='2352422'>the future</span> <span m='2352770'>thing,</span>
  <span m='2353200'>if</span> <span m='2353760'>he has a</span> <span m='2354230'>system
  that</span> <span m='2354330'>lasts</span> <span m='2354600'>30</span> <span m='2354800'>years,</span>
  <span m='2355100'>and you</span> <span m='2355240'>say</span> <span m='2355550'>future</span>
  <span m='2355990'>p,</span> <span m='2357130'>somewhere</span> <span m='2357430'>in</span>
  <span m='2357730'>your</span> <span m='2358110'>design of the</span> <span m='2358550'>system
  is</span> <span m='2358720'>going to</span> <span m='2359165'>say</span> <span m='2359610'>that</span>
  <span m='2359960'>the</span> <span m='2360350'>constraint</span> <span m='2360740'>on
  future</span> <span m='2361020'>p is</span> <span m='2361170'>that it</span> <span
  m='2361620'>has to happen</span> <span m='2362070'>within</span> <span m='2362250'>30</span>
  <span m='2362550'>years,</span> <span m='2362850'>right?</span> <span m='2363290'>Because</span>
  <span m='2363640'>future</span> <span m='2364590'>p</span> <span m='2364870'>here,
  for</span> <span m='2365170'>getting</span> <span m='2365440'>gas,</span> <span
  m='2365793'>has</span> <span m='2366146'>to happen</span> <span m='2366630'>before</span>
  <span m='2366900'>I run out</span> <span m='2367350'>of</span> <span m='2367500'>gas.</span>
  <span m='2367750'>It's not</span> <span m='2368170'>just--</span> <span m='2369040'>this</span>
  <span m='2369240'>representation</span> <span m='2369470'>says</span> <span m='2369890'>it</span>
  <span m='2370130'>just</span> <span m='2370350'>happens in</span> <span m='2370470'>the</span>
  <span m='2370720'>future,</span> <span m='2371050'>but</span> <span m='2371560'>somewhere</span>
  <span m='2372130'>in</span> <span m='2372230'>your</span> <span m='2372800'>constraint</span>
  <span m='2373554'>checking,</span> <span m='2373931'>it's going to</span> <span
  m='2374310'>say,</span> <span m='2374976'>hey, we</span> <span m='2375362'>didn't
  get</span> <span m='2375750'>gas in this</span> <span m='2376030'>plan</span> <span
  m='2376417'>soon enough,</span> <span m='2376804'>right?</span> </p><p><span m='2377580'>ELLIE:</span>
  <span m='2377705'>Yeah.</span> </p><p><span m='2378195'>AUDIENCE:</span> <span m='2378377'>Somehow.</span>
  </p><p><span m='2378560'>ELLIE:</span> <span m='2378725'>Yes,</span> <span m='2378890'>that's</span>
  <span m='2379210'>definitely true.</span> <span m='2379660'>And</span> <span m='2380133'>these</span>
  <span m='2380606'>are</span> <span m='2381079'>just</span> <span m='2382498'>tools
  to</span> <span m='2382971'>help you</span> <span m='2383444'>model it,</span> <span
  m='2383917'>but it's</span> <span m='2384390'>definitely</span> <span m='2384863'>not
  the</span> <span m='2385336'>entire model</span> <span m='2385809'>of your</span>
  <span m='2386282'>system</span> <span m='2386755'>obviously,</span> <span m='2387230'>and</span>
  <span m='2387870'>so</span> <span m='2388270'>I</span> <span m='2388480'>agree</span>
  <span m='2388780'>that</span> <span m='2389080'>we definitely</span> <span m='2389250'>would</span>
  <span m='2389525'>have</span> <span m='2389800'>to</span> <span m='2389930'>incorporate</span>
  <span m='2390375'>that in. And</span> <span m='2390820'>for</span> <span m='2391050'>finance</span>
  <span m='2391310'>systems</span> <span m='2392920'>you</span> <span m='2393100'>have</span>
  <span m='2393340'>to</span> <span m='2393490'>account</span> <span m='2393902'>for
  that.</span> <span m='2394314'>And that's</span> <span m='2394726'>why</span> <span
  m='2395140'>they have the</span> <span m='2395330'>extension of</span> <span m='2395733'>LTL</span>
  <span m='2396136'>which is the</span> <span m='2396540'>finance</span> <span m='2396780'>systems,</span>
  <span m='2398034'>which</span> <span m='2398452'>we can</span> <span m='2398870'>certainly</span>
  <span m='2399520'>drop</span> <span m='2399972'>a link of</span> <span m='2400424'>of</span>
  <span m='2400876'>the papers,</span> <span m='2401328'>and</span> <span m='2401780'>where</span>
  <span m='2402232'>we got</span> <span m='2402684'>the information,</span> <span
  m='2403140'>to the class</span> <span m='2403300'>if you guys</span> <span m='2403792'>would
  like that.</span> </p><p><span m='2406750'>AUDIENCE:</span> <span m='2406815'>Yeah,</span>
  <span m='2406880'>I</span> <span m='2407380'>think you</span> <span m='2407880'>guys</span>
  <span m='2408140'>have done a</span> <span m='2408400'>very</span> <span m='2408580'>good</span>
  <span m='2408800'>job</span> <span m='2408930'>of</span> <span m='2409310'>answering</span>
  <span m='2409970'>the</span> <span m='2410080'>questions.</span> <span m='2410430'>The</span>
  <span m='2410905'>three</span> <span m='2411380'>extensions</span> <span m='2411970'>to
  LTL</span> <span m='2412720'>that</span> <span m='2412840'>I've</span> <span m='2413170'>found</span>
  <span m='2413400'>to be the</span> <span m='2413670'>most</span> <span m='2413920'>relevant</span>
  <span m='2414500'>kinds</span> <span m='2414600'>of</span> <span m='2414660'>things</span>
  <span m='2414880'>that</span> <span m='2415060'>we're</span> <span m='2415270'>doing</span>
  <span m='2415760'>is</span> <span m='2416520'>metric</span> <span m='2416990'>temporal</span>
  <span m='2417460'>logic,</span> <span m='2417850'>which</span> <span m='2418000'>is</span>
  <span m='2418090'>the</span> <span m='2418250'>first one that</span> <span m='2418600'>you</span>
  <span m='2418700'>mentioned,</span> <span m='2419440'>also</span> <span m='2419800'>to</span>
  <span m='2419890'>be</span> <span m='2420000'>able to</span> <span m='2420280'>have
  it</span> <span m='2420400'>over</span> <span m='2420610'>bounded</span> <span m='2421080'>time,</span>
  <span m='2421360'>which</span> <span m='2421540'>is</span> <span m='2421660'>related,</span>
  <span m='2422070'>and</span> <span m='2422130'>you mentioned.</span> <span m='2422350'>And</span>
  <span m='2422530'>then</span> <span m='2422740'>the</span> <span m='2422830'>last</span>
  <span m='2423130'>one</span> <span m='2424000'>is</span> <span m='2424240'>to</span>
  <span m='2424390'>deal</span> <span m='2424570'>with</span> <span m='2424720'>uncertainty,</span>
  <span m='2424975'>and</span> <span m='2425230'>is</span> <span m='2425710'>then
  a</span> <span m='2425930'>problem of</span> <span m='2426380'>linear</span> <span
  m='2426680'>temporal</span> <span m='2427030'>logic.</span> </p><p><span m='2428136'>ELLIE:</span>
  <span m='2428382'>OK.</span> <span m='2428629'>Cool.</span> <span m='2429122'>All</span>
  <span m='2429615'>right.</span> </p><p><span m='2431587'>So</span> <span m='2432080'>I</span>
  <span m='2433066'>meant</span> <span m='2433559'>to have this as two separate</span>
  <span m='2434052'>slides,</span> <span m='2434545'>but</span> <span m='2437010'>what
  are</span> <span m='2437503'>some true</span> <span m='2437996'>statements about</span>
  <span m='2438489'>LTL</span> <span m='2439490'>that you</span> <span m='2439970'>guys
  can</span> <span m='2440942'>tell me about</span> <span m='2441434'>to look at</span>
  <span m='2441926'>this, or</span> <span m='2442420'>do,</span> <span m='2442640'>and</span>
  <span m='2443090'>explain</span> <span m='2443450'>why</span> <span m='2443870'>if
  you look</span> <span m='2444370'>at it.</span> </p><p><span m='2450190'>OK,</span>
  <span m='2450680'>so</span> <span m='2450860'>why</span> <span m='2451130'>is</span>
  <span m='2451340'>the next</span> <span m='2451810'>red</span> <span m='2451920'>true?</span>
  </p><p><span m='2454330'>AUDIENCE:</span> <span m='2454571'>The</span> <span m='2454812'>next
  step is</span> <span m='2455294'>slow down.</span> </p><p><span m='2455776'>ELLIE:</span>
  <span m='2456017'>Yep,</span> <span m='2456258'>exactly.</span> <span m='2456740'>Because
  the next one</span> <span m='2457222'>is red.</span> <span m='2457710'>Why</span>
  <span m='2457930'>is</span> <span m='2458010'>it</span> <span m='2458280'>true</span>
  <span m='2458430'>that</span> <span m='2458800'>in the</span> <span m='2459020'>future,</span>
  <span m='2459280'>that it's</span> <span m='2459540'>green?</span> </p><p><span
  m='2460380'>[INAUDIBLE]</span> </p><p><span m='2461766'>Because</span> <span m='2462230'>in
  the</span> <span m='2462450'>future, it's</span> <span m='2462877'>green.</span>
  <span m='2463731'>And why</span> <span m='2464160'>is it</span> <span m='2464520'>true</span>
  <span m='2464740'>that there's</span> <span m='2464960'>red</span> <span m='2465160'>until</span>
  <span m='2465430'>green?</span> </p><p><span m='2466612'>AUDIENCE:</span> <span
  m='2466847'>It</span> <span m='2467083'>keeps</span> <span m='2467554'>being red</span>
  <span m='2468025'>until it's</span> <span m='2468496'>green.</span> </p><p><span
  m='2469438'>ELLIE:</span> <span m='2469673'>Exactly.</span> <span m='2470380'>So
  it</span> <span m='2470860'>makes sense</span> <span m='2471150'>that if</span>
  <span m='2471530'>all</span> <span m='2471690'>of</span> <span m='2471740'>these</span>
  <span m='2471890'>are</span> <span m='2472130'>true,</span> <span m='2472370'>that</span>
  <span m='2472858'>this</span> <span m='2473346'>culmination</span> <span m='2473834'>of</span>
  <span m='2474810'>the and</span> <span m='2475298'>statements</span> <span m='2475786'>between
  all of</span> <span m='2476274'>them is</span> <span m='2476762'>also true,</span>
  <span m='2477250'>right?</span> <span m='2477510'>And so you</span> <span m='2478006'>could
  do that with</span> <span m='2478502'>or</span> <span m='2478998'>as</span> <span
  m='2479494'>well, or you could</span> <span m='2479990'>do that</span> <span m='2480210'>with--</span>
  <span m='2481170'>if you had</span> <span m='2482530'>sequences</span> <span m='2482980'>behind</span>
  <span m='2483160'>here,</span> <span m='2483932'>you could</span> <span m='2484320'>put</span>
  <span m='2484900'>a future</span> <span m='2485310'>around</span> <span m='2485720'>this
  whole</span> <span m='2486100'>thing,</span> <span m='2486410'>and it</span> <span
  m='2486870'>would</span> <span m='2487160'>be</span> <span m='2487370'>true</span>
  <span m='2487550'>that</span> <span m='2487730'>at some point</span> <span m='2488090'>in</span>
  <span m='2488270'>the</span> <span m='2488360'>future,</span> <span m='2488930'>all</span>
  <span m='2489080'>of</span> <span m='2489170'>this would</span> <span m='2489627'>hold.</span>
  </p><p><span m='2490084'>Does that</span> <span m='2490541'>make sense?</span> <span
  m='2491912'>Yes?</span> <span m='2492826'>OK.</span> </p><p><span m='2493740'>AUDIENCE:</span>
  <span m='2493767'>Why</span> <span m='2493794'>keep</span> <span m='2493821'>it</span>
  <span m='2493850'>red</span> <span m='2494120'>there?</span> <span m='2494655'>Your
  red</span> <span m='2495406'>is the</span> <span m='2495892'>next step.</span> </p><p><span
  m='2497350'>ELLIE:</span> <span m='2497505'>Yep.</span> <span m='2497660'>Exactly.</span>
  <span m='2498046'>I</span> <span m='2498432'>was</span> <span m='2498820'>just</span>
  <span m='2499130'>saying if</span> <span m='2499340'>you had</span> <span m='2499620'>more</span>
  <span m='2499860'>in</span> <span m='2500350'>the</span> <span m='2500840'>past,</span>
  <span m='2501330'>and</span> <span m='2501440'>you</span> <span m='2501510'>were</span>
  <span m='2501770'>considering it</span> <span m='2502080'>from</span> <span m='2502524'>the
  previous--</span> </p><p><span m='2503856'>All</span> <span m='2504300'>right</span>
  <span m='2504500'>so</span> <span m='2504790'>now</span> <span m='2505573'>Nadia's</span>
  <span m='2506056'>going to talk about</span> <span m='2506540'>expressing</span>
  <span m='2507520'>LTL</span> <span m='2507760'>in</span> <span m='2508243'>PDDL3.</span>
  </p><p><span m='2517920'>So</span> <span m='2518340'>Ben</span> <span m='2518780'>and</span>
  <span m='2519720'>Ellie</span> <span m='2520700'>have</span> <span m='2521495'>guided</span>
  <span m='2521910'>through</span> <span m='2522120'>how</span> <span m='2523270'>expressive</span>
  <span m='2523720'>LTL</span> <span m='2524170'>formulation</span> <span m='2525070'>is.</span>
  <span m='2525768'>I'm</span> <span m='2526226'>going to</span> <span m='2527600'>formulate</span>
  <span m='2528556'>the</span> <span m='2529290'>LTL</span> <span m='2529720'>in</span>
  <span m='2530160'>a</span> <span m='2530600'>classical</span> <span m='2531450'>planner</span>
  <span m='2531820'>like</span> <span m='2532040'>PDDL3.</span> <span m='2533010'>Now</span>
  <span m='2533600'>I'm</span> <span m='2533830'>using</span> <span m='2534220'>PDDL3,</span>
  <span m='2535030'>which</span> <span m='2535270'>is</span> <span m='2535450'>an</span>
  <span m='2536350'>composed</span> <span m='2536540'>extension</span> <span m='2536850'>of</span>
  <span m='2537345'>PDDL2.2,</span> <span m='2539340'>which</span> <span m='2539490'>supports</span>
  <span m='2540340'>some</span> <span m='2541922'>of</span> <span m='2542304'>the</span>
  <span m='2543460'>LTL</span> <span m='2543990'>operators.</span> </p><p><span m='2546170'>So</span>
  <span m='2546936'>these are</span> <span m='2547352'>the</span> <span m='2547770'>basic</span>
  <span m='2548200'>operators</span> <span m='2549350'>that</span> <span m='2549600'>you</span>
  <span m='2549670'>can</span> <span m='2549850'>use</span> <span m='2550150'>to</span>
  <span m='2550300'>express</span> <span m='2550910'>the</span> <span m='2551180'>constraints</span>
  <span m='2551920'>and</span> <span m='2552130'>goals</span> <span m='2552760'>of</span>
  <span m='2553320'>your</span> <span m='2553450'>plan.</span> <span m='2554230'>So</span>
  <span m='2554890'>you</span> <span m='2555250'>have</span> <span m='2555600'>at
  end,</span> <span m='2556260'>always,</span> <span m='2557040'>sometimes,</span>
  <span m='2557590'>within,</span> <span m='2557875'>at-most-once,</span> <span m='2559000'>sometime-after,</span>
  <span m='2560425'>sometime-before,</span> <span m='2562360'>always-within,</span>
  <span m='2563020'>and</span> <span m='2563440'>hold-during.</span> <span m='2564910'>So</span>
  <span m='2565180'>again,</span> <span m='2565660'>now</span> <span m='2566450'>here</span>
  <span m='2566930'>is</span> <span m='2567270'>a</span> <span m='2567450'>numeric</span>
  <span m='2568180'>controls</span> <span m='2568780'>that you</span> <span m='2569215'>can</span>
  <span m='2569650'>specify,</span> <span m='2570940'>and</span> <span m='2571970'>the</span>
  <span m='2572423'>ellipses</span> <span m='2573330'>represents</span> <span m='2573650'>an</span>
  <span m='2574375'>already-existing</span> <span m='2577060'>[INAUDIBLE]</span> <span
  m='2577690'>goal.</span> <span m='2578050'>This is</span> <span m='2578375'>a</span>
  <span m='2578700'>goal</span> <span m='2578920'>description--</span> <span m='2579956'>[INAUDIBLE]</span>
  </p><p><span m='2580870'>So</span> <span m='2581670'>some of</span> <span m='2582140'>the
  operators</span> <span m='2582610'>may</span> <span m='2584020'>look</span> <span
  m='2584500'>familiar</span> <span m='2584980'>to</span> <span m='2585460'>you,</span>
  <span m='2585580'>because they</span> <span m='2586070'>can</span> <span m='2586450'>also</span>
  <span m='2586800'>be used</span> <span m='2587170'>to</span> <span m='2587350'>express</span>
  <span m='2587860'>the</span> <span m='2588335'>constraint</span> <span m='2588810'>in</span>
  <span m='2589100'>STN,</span> <span m='2589450'>the</span> <span m='2589800'>Simple</span>
  <span m='2590220'>Temporal</span> <span m='2590495'>Network,</span> <span m='2591060'>that
  we</span> <span m='2591488'>learned in</span> <span m='2591916'>class.</span> <span
  m='2593200'>And</span> <span m='2594390'>there</span> <span m='2594580'>are</span>
  <span m='2594850'>some</span> <span m='2595610'>operators that are</span> <span
  m='2596000'>unique</span> <span m='2596418'>to</span> <span m='2597672'>LTL</span>
  <span m='2598410'>or</span> <span m='2598840'>other</span> <span m='2599100'>kinds,</span>
  <span m='2599450'>like</span> <span m='2600130'>metric</span> <span m='2600605'>temporal</span>
  <span m='2600990'>network,</span> <span m='2601450'>like</span> <span m='2601910'>always,</span>
  <span m='2602800'>for</span> <span m='2603000'>example.</span> <span m='2604910'>So</span>
  <span m='2605110'>now</span> <span m='2605390'>we</span> <span m='2606000'>are</span>
  <span m='2606260'>going</span> <span m='2606490'>to</span> <span m='2606790'>take</span>
  <span m='2607100'>a</span> <span m='2607150'>look</span> <span m='2607370'>at</span>
  <span m='2610960'>how</span> <span m='2611460'>you</span> <span m='2611570'>can</span>
  <span m='2611960'>express</span> <span m='2613800'>the</span> <span m='2614080'>operators</span>
  <span m='2614380'>using</span> <span m='2615144'>the</span> <span m='2616536'>PDDL3</span>
  <span m='2618910'>language.</span> <span m='2619960'>So</span> <span m='2620850'>we</span>
  <span m='2620920'>can</span> <span m='2621100'>use,</span> <span m='2621430'>within</span>
  <span m='2622000'>one</span> <span m='2622240'>occurrence</span> <span m='2622750'>to</span>
  <span m='2623070'>the</span> <span m='2623430'>next,</span> <span m='2624090'>because</span>
  <span m='2624580'>there is</span> <span m='2624940'>no</span> <span m='2625420'>explicit</span>
  <span m='2626060'>next</span> <span m='2626335'>in the</span> <span m='2626610'>PDDL3.</span>
  <span m='2628410'>And</span> <span m='2628570'>you</span> <span m='2629650'>use</span>
  <span m='2629950'>always</span> <span m='2630240'>until</span> <span m='2630530'>to</span>
  <span m='2630860'>express</span> <span m='2631280'>until.</span> <span m='2632625'>And</span>
  <span m='2633110'>in</span> <span m='2633610'>the future,</span> <span m='2634160'>you
  use</span> <span m='2634410'>sometimes</span> <span m='2635140'>after,</span> <span
  m='2636220'>and</span> <span m='2637100'>globally,</span> <span m='2637360'>you
  can</span> <span m='2637840'>use</span> <span m='2638333'>always.</span> <span m='2639320'>And</span>
  <span m='2639460'>for</span> <span m='2639730'>release,</span> <span m='2640100'>since</span>
  <span m='2640940'>it</span> <span m='2641170'>can</span> <span m='2641350'>always</span>
  <span m='2642130'>be</span> <span m='2643800'>omega</span> <span m='2644830'>or</span>
  <span m='2645760'>always</span> <span m='2646500'>until</span> <span m='2647495'>omega</span>
  <span m='2648680'>when</span> <span m='2648870'>you</span> <span m='2649395'>see</span>
  <span m='2649770'>p.</span> <span m='2649930'>You</span> <span m='2650430'>can</span>
  <span m='2650930'>use</span> <span m='2651140'>all</span> <span m='2651600'>costs,</span>
  <span m='2652090'>too,</span> <span m='2652350'>although</span> <span m='2652500'>this</span>
  <span m='2652988'>[INAUDIBLE].</span> </p><p><span m='2657380'>OK,</span> <span
  m='2657868'>let's</span> <span m='2658360'>see some</span> <span m='2658645'>examples.</span>
  <span m='2659980'>So</span> <span m='2661340'>if</span> <span m='2662740'>your</span>
  <span m='2662890'>goal</span> <span m='2663250'>is</span> <span m='2663620'>to</span>
  <span m='2663930'>have</span> <span m='2664700'>the</span> <span m='2665085'>traffic</span>
  <span m='2665470'>light</span> <span m='2665690'>turn red</span> <span m='2666065'>in
  the</span> <span m='2666440'>next</span> <span m='2666910'>state,</span> <span m='2668320'>you
  would</span> <span m='2668730'>want</span> <span m='2669110'>to</span> <span m='2672790'>formulate</span>
  <span m='2673145'>it</span> <span m='2673500'>using</span> <span m='2674622'>within</span>
  <span m='2675070'>one</span> <span m='2675290'>occurrence,</span> <span m='2676775'>the
  traffic</span> <span m='2677270'>light would</span> <span m='2677765'>turn red.</span>
  <span m='2681730'>And</span> <span m='2682050'>let's</span> <span m='2682300'>take
  a look</span> <span m='2682560'>at</span> <span m='2682750'>a</span> <span m='2682970'>more</span>
  <span m='2683285'>complicated</span> <span m='2684030'>example.</span> <span m='2685320'>So</span>
  <span m='2685680'>if</span> <span m='2686580'>you</span> <span m='2686700'>want</span>
  <span m='2686890'>to</span> <span m='2687070'>model</span> <span m='2687505'>a</span>
  <span m='2687940'>goal</span> <span m='2688280'>saying that</span> <span m='2688570'>the</span>
  <span m='2688860'>traffic</span> <span m='2689290'>light would</span> <span m='2692210'>be</span>
  <span m='2692480'>green</span> <span m='2692820'>until it</span> <span m='2693176'>turns</span>
  <span m='2693532'>red,</span> <span m='2693890'>at</span> <span m='2694250'>which</span>
  <span m='2694420'>point</span> <span m='2696558'>it</span> <span m='2696990'>would</span>
  <span m='2697170'>be</span> <span m='2697410'>red</span> <span m='2697670'>forever.</span>
  </p><p><span m='2698850'>So</span> <span m='2699180'>this</span> <span m='2699420'>is</span>
  <span m='2700850'>temporal</span> <span m='2701280'>logic</span> <span m='2702920'>of</span>
  <span m='2703130'>predicates</span> <span m='2703862'>that</span> <span m='2704230'>express</span>
  <span m='2704850'>this</span> <span m='2706870'>goal.</span> <span m='2708046'>And</span>
  <span m='2708440'>then</span> <span m='2709590'>if</span> <span m='2709860'>you</span>
  <span m='2709970'>want</span> <span m='2710190'>to</span> <span m='2710330'>model</span>
  <span m='2710810'>that using</span> <span m='2711050'>PDDL,</span> <span m='2713800'>there</span>
  <span m='2713880'>is</span> <span m='2714000'>a</span> <span m='2714060'>direct</span>
  <span m='2714390'>mapping.</span> <span m='2715580'>You</span> <span m='2715640'>can</span>
  <span m='2715790'>see</span> <span m='2716190'>the direct</span> <span m='2716400'>mapping</span>
  <span m='2716808'>between</span> <span m='2717216'>the</span> <span m='2717624'>predicates
  and</span> <span m='2718032'>the</span> <span m='2719065'>PDDL.</span> <span m='2720220'>So</span>
  <span m='2720630'>this</span> <span m='2721020'>is</span> <span m='2721330'>basically</span>
  <span m='2721530'>saying,</span> <span m='2723660'>it</span> <span m='2724140'>would</span>
  <span m='2724410'>always</span> <span m='2725740'>be green</span> <span m='2726120'>until</span>
  <span m='2726605'>it turns</span> <span m='2727090'>red.</span> <span m='2728226'>And</span>
  <span m='2728654'>turning</span> <span m='2729082'>red</span> <span m='2729510'>implies</span>
  <span m='2730040'>it</span> <span m='2730500'>will</span> <span m='2730710'>always</span>
  <span m='2730995'>turn</span> <span m='2731620'>red.</span> </p><p><span m='2736520'>So</span>
  <span m='2736940'>next,</span> <span m='2737270'>[? Arleese ?]</span> <span m='2738035'>will</span>
  <span m='2738380'>tell</span> <span m='2738710'>us</span> <span m='2738860'>how</span>
  <span m='2739130'>to</span> <span m='2739563'>map</span> <span m='2739996'>between</span>
  <span m='2741180'>the</span> <span m='2742060'>LTL</span> <span m='2742640'>to</span>
  <span m='2742860'>PDDL</span> <span m='2743570'>with a</span> <span m='2743840'>Buchi</span>
  <span m='2744110'>Automata</span> <span m='2744640'>which is</span> <span m='2744950'>a</span>
  <span m='2745370'>specialized</span> <span m='2745685'>automata.</span> </p><p><span
  m='2750940'>GUEST SPEAKER:</span> <span m='2751045'>Cool.</span> <span m='2751585'>So
  I'm</span> <span m='2752020'>[? Arleese. ?]</span> <span m='2752890'>I have</span>
  <span m='2753760'>bridged</span> <span m='2753960'>the</span> <span m='2754050'>gap</span>
  <span m='2754270'>between</span> <span m='2754575'>LTL</span> <span m='2754880'>and</span>
  <span m='2755060'>the</span> <span m='2755380'>planning</span> <span m='2755480'>world.</span>
  <span m='2756404'>So</span> <span m='2756866'>this is</span> <span m='2757328'>kind
  of the</span> <span m='2757790'>framework</span> <span m='2758270'>for</span> <span
  m='2758450'>how</span> <span m='2758590'>you would</span> <span m='2758810'>go</span>
  <span m='2759020'>from taking</span> <span m='2759370'>a</span> <span m='2759480'>problem</span>
  <span m='2759850'>with</span> <span m='2760090'>temporally</span> <span m='2760280'>extended</span>
  <span m='2760770'>goals</span> <span m='2761320'>all the way to</span> <span m='2761650'>a</span>
  <span m='2761820'>plan.</span> </p><p><span m='2763000'>So</span> <span m='2763560'>as
  you</span> <span m='2764014'>can kind of</span> <span m='2764468'>imagine</span>
  <span m='2764922'>from what</span> <span m='2765376'>Ben and Ellie</span> <span
  m='2765830'>were</span> <span m='2765950'>talking</span> <span m='2766280'>about,</span>
  <span m='2767040'>LTL is</span> <span m='2767440'>pretty</span> <span m='2767820'>expressive.</span>
  <span m='2768195'>You can</span> <span m='2768570'>express a</span> <span m='2768810'>lot</span>
  <span m='2768990'>of</span> <span m='2769150'>different types of</span> <span m='2769590'>goals</span>
  <span m='2770006'>that</span> <span m='2770838'>include</span> <span m='2771670'>more</span>
  <span m='2771890'>temporal</span> <span m='2772220'>properties</span> <span m='2772740'>than</span>
  <span m='2772880'>just</span> <span m='2773300'>a</span> <span m='2773390'>time</span>
  <span m='2774170'>window</span> <span m='2774620'>for</span> <span m='2774830'>a
  goal to</span> <span m='2775140'>be completed.</span> </p><p><span m='2777140'>So</span>
  <span m='2777320'>once</span> <span m='2777530'>we</span> <span m='2777680'>have</span>
  <span m='2778030'>a</span> <span m='2778496'>kind of defined</span> <span m='2778962'>problem
  with</span> <span m='2779430'>these</span> <span m='2779810'>temporary</span> <span
  m='2780200'>extended</span> <span m='2780400'>goals,</span> <span m='2781140'>then</span>
  <span m='2781510'>you</span> <span m='2781680'>want</span> <span m='2781860'>to</span>
  <span m='2781950'>model it in</span> <span m='2782235'>a language</span> <span m='2782520'>like</span>
  <span m='2782710'>LTL</span> <span m='2783620'>or</span> <span m='2783910'>PDDL.</span>
  <span m='2786150'>So</span> <span m='2786320'>if you have a</span> <span m='2786670'>language</span>
  <span m='2786950'>like</span> <span m='2787110'>PDDL,</span> <span m='2787520'>and
  you</span> <span m='2787790'>have a</span> <span m='2788150'>planner</span> <span
  m='2788510'>that</span> <span m='2788980'>can</span> <span m='2789240'>do</span>
  <span m='2789350'>an algorithm</span> <span m='2790100'>called</span> <span m='2790280'>progression,</span>
  <span m='2790580'>which</span> <span m='2790880'>I'll</span> <span m='2791090'>talk</span>
  <span m='2791300'>about</span> <span m='2791530'>a</span> <span m='2791570'>little</span>
  <span m='2791780'>later,</span> <span m='2792200'>you can</span> <span m='2792470'>go
  directly</span> <span m='2793210'>to</span> <span m='2793480'>a plan.</span> </p><p><span
  m='2794770'>Basically</span> <span m='2795485'>how progression</span> <span m='2796120'>works</span>
  <span m='2796750'>is</span> <span m='2797585'>it's</span> <span m='2797840'>kind
  of</span> <span m='2798140'>an algorithm</span> <span m='2798503'>that</span> <span
  m='2798866'>tells</span> <span m='2799230'>you</span> <span m='2799360'>when</span>
  <span m='2799770'>you're</span> <span m='2800180'>analyzing</span> <span m='2800320'>a
  state,</span> <span m='2800670'>and</span> <span m='2801020'>you're analyzing</span>
  <span m='2801965'>LTL-like</span> <span m='2802910'>formulas</span> <span m='2803120'>that
  are</span> <span m='2803620'>true in a</span> <span m='2804020'>specific</span>
  <span m='2804240'>state,</span> <span m='2805010'>how</span> <span m='2805160'>to</span>
  <span m='2806660'>push</span> <span m='2807060'>formulas</span> <span m='2807360'>that
  you need to</span> <span m='2807660'>evaluate</span> <span m='2808520'>later</span>
  <span m='2808850'>on</span> <span m='2809400'>to</span> <span m='2809510'>the</span>
  <span m='2809600'>next</span> <span m='2809900'>state, and</span> <span m='2810275'>how
  to</span> <span m='2810650'>keep</span> <span m='2810830'>track of</span> <span
  m='2811310'>things</span> <span m='2811600'>that</span> <span m='2811910'>you need</span>
  <span m='2812180'>to</span> <span m='2812625'>continue</span> <span m='2813070'>to
  evaluate</span> <span m='2813515'>for satisfaction</span> <span m='2814405'>in</span>
  <span m='2814850'>future</span> <span m='2815150'>states.</span> </p><p><span m='2816890'>Another</span>
  <span m='2817050'>way you</span> <span m='2817460'>can do</span> <span m='2817870'>this</span>
  <span m='2818380'>is</span> <span m='2818760'>by</span> <span m='2818910'>taking</span>
  <span m='2819283'>LTL</span> <span m='2820030'>formulations</span> <span m='2820375'>and</span>
  <span m='2820720'>translating</span> <span m='2821103'>them into</span> <span m='2821486'>Buchi</span>
  <span m='2821870'>Automata.</span> <span m='2822640'>So</span> <span m='2822850'>Buchi</span>
  <span m='2823185'>Automata</span> <span m='2823520'>are</span> <span m='2823850'>basically</span>
  <span m='2824420'>finite</span> <span m='2824800'>state</span> <span m='2825240'>machines</span>
  <span m='2825710'>that</span> <span m='2825830'>are</span> <span m='2825920'>extended</span>
  <span m='2826490'>to</span> <span m='2827780'>handle</span> <span m='2828035'>an</span>
  <span m='2828290'>infinite</span> <span m='2828960'>sequence</span> <span m='2829140'>of
  states.</span> <span m='2830530'>And</span> <span m='2830860'>I'll get</span> <span
  m='2831285'>into</span> <span m='2831710'>more</span> <span m='2832120'>about</span>
  <span m='2832580'>how</span> <span m='2832730'>Buchi</span> <span m='2833120'>Automata</span>
  <span m='2833420'>work.</span> <span m='2834110'>After you</span> <span m='2834590'>have
  a Buchi</span> <span m='2835070'>Automata,</span> <span m='2835550'>you can then</span>
  <span m='2835893'>translate</span> <span m='2836236'>that into</span> <span m='2836580'>PDDL2,</span>
  <span m='2837620'>which</span> <span m='2837770'>you</span> <span m='2837860'>guys
  are</span> <span m='2838140'>all familiar</span> <span m='2838832'>with,</span>
  <span m='2839304'>and then</span> <span m='2839776'>that</span> <span m='2840248'>PDDL2</span>
  <span m='2840720'>can be</span> <span m='2841130'>used</span> <span m='2841520'>from
  the</span> <span m='2841730'>classical</span> <span m='2842060'>planner,</span>
  <span m='2842390'>and</span> <span m='2842650'>get a plan.</span> </p><p><span m='2846850'>So</span>
  <span m='2847170'>a little</span> <span m='2847320'>bit</span> <span m='2847490'>more
  about</span> <span m='2847720'>Buchi</span> <span m='2848124'>Automata.</span> <span
  m='2848528'>Again,</span> <span m='2848932'>like I said,</span> <span m='2849336'>it's</span>
  <span m='2849740'>an</span> <span m='2849820'>extension</span> <span m='2850270'>of
  a finite</span> <span m='2850660'>state</span> <span m='2851033'>machine.</span>
  </p><p><span m='2851780'>Oh, yes.</span> </p><p><span m='2852432'>AUDIENCE:</span>
  <span m='2852653'>Why would</span> <span m='2852874'>have a</span> <span m='2853316'>Buchi
  Automata</span> <span m='2853758'>when you</span> <span m='2854200'>could just use</span>
  <span m='2854642'>a planner</span> <span m='2855090'>that will go</span> <span m='2855490'>from</span>
  <span m='2855928'>PDDL3</span> <span m='2856366'>straight</span> <span m='2856804'>to</span>
  <span m='2857242'>the</span> <span m='2857680'>plan?</span> </p><p><span m='2858925'>GUEST
  SPEAKER:</span> <span m='2859127'>I</span> <span m='2859330'>guess</span> <span
  m='2859640'>it just</span> <span m='2859900'>depends</span> <span m='2860160'>on</span>
  <span m='2860360'>how--</span> <span m='2861060'>what</span> <span m='2861560'>kind
  of</span> <span m='2862060'>planners</span> <span m='2862330'>we have access</span>
  <span m='2862690'>to,</span> <span m='2862930'>what</span> <span m='2863240'>other</span>
  <span m='2863540'>systems</span> <span m='2863810'>you</span> <span m='2864080'>have.</span>
  <span m='2864320'>It's</span> <span m='2864440'>done</span> <span m='2864680'>both</span>
  <span m='2864860'>ways.</span> <span m='2865602'>So</span> <span m='2865984'>PDDL3</span>
  <span m='2866750'>is</span> <span m='2866810'>still</span> <span m='2867050'>kind
  of</span> <span m='2867320'>new,</span> <span m='2867560'>and so there's</span>
  <span m='2868025'>not a lot of</span> <span m='2868490'>planners</span> <span m='2868750'>that</span>
  <span m='2869170'>actually</span> <span m='2869340'>have progression</span> <span
  m='2869812'>and can</span> <span m='2870284'>handle</span> <span m='2870756'>PDDL3.</span>
  </p><p><span m='2874060'>AUDIENCE:</span> <span m='2874220'>And</span> <span m='2874380'>it's</span>
  <span m='2875240'>also</span> <span m='2875450'>the</span> <span m='2875540'>case</span>
  <span m='2875870'>that</span> <span m='2876470'>the</span> <span m='2876890'>particular</span>
  <span m='2877170'>algorithms</span> <span m='2877990'>that</span> <span m='2878120'>are</span>
  <span m='2878200'>trying</span> <span m='2878480'>to</span> <span m='2878940'>either</span>
  <span m='2879100'>be</span> <span m='2879310'>verification</span> <span m='2879860'>or</span>
  <span m='2880010'>planning,</span> <span m='2880910'>maybe</span> <span m='2881350'>exploiting</span>
  <span m='2881610'>particular</span> <span m='2882250'>properties of</span> <span
  m='2882650'>the Buchi</span> <span m='2883032'>Automaton,</span> <span m='2884180'>as</span>
  <span m='2884300'>opposed</span> <span m='2884630'>to</span> <span m='2884720'>the</span>
  <span m='2884810'>properties</span> <span m='2885370'>of</span> <span m='2885470'>the
  native</span> <span m='2885927'>language.</span> </p><p><span m='2889590'>GUEST
  SPEAKER:</span> <span m='2889767'>So</span> <span m='2889945'>you</span> <span m='2890300'>guys
  are</span> <span m='2890610'>all familiar</span> <span m='2890830'>with</span> <span
  m='2891130'>regular</span> <span m='2891540'>state</span> <span m='2891870'>machines.</span>
  <span m='2892395'>Buchi Automata</span> <span m='2892790'>has</span> <span m='2893185'>a
  very similar</span> <span m='2893580'>formulation.</span> <span m='2894822'>Some</span>
  <span m='2895190'>slight</span> <span m='2895450'>differences--</span> <span m='2895770'>you
  have</span> <span m='2896090'>a set of</span> <span m='2896440'>states,</span> <span
  m='2897210'>you</span> <span m='2897330'>have</span> <span m='2897420'>an</span>
  <span m='2897510'>initial</span> <span m='2897870'>state,</span> <span m='2898670'>and
  you</span> <span m='2899070'>have a transition</span> <span m='2899220'>relation,</span>
  <span m='2901050'>and</span> <span m='2901170'>then</span> <span m='2901290'>you
  have a</span> <span m='2901520'>set</span> <span m='2901660'>of</span> <span m='2901780'>accepting</span>
  <span m='2902580'>states.</span> <span m='2903020'>These</span> <span m='2903180'>accepting</span>
  <span m='2903610'>states</span> <span m='2903840'>are</span> <span m='2904020'>essentially</span>
  <span m='2904440'>what replaces</span> <span m='2905060'>finite</span> <span m='2905610'>states
  in</span> <span m='2905976'>the state</span> <span m='2906342'>machine.</span> <span
  m='2907545'>We also have</span> <span m='2908040'>a set</span> <span m='2908535'>of
  symbols</span> <span m='2909030'>that</span> <span m='2910076'>are again</span>
  <span m='2910430'>simply the</span> <span m='2910710'>transitions</span> <span m='2911150'>between</span>
  <span m='2911622'>states.</span> </p><p><span m='2913040'>So</span> <span m='2913230'>what</span>
  <span m='2913480'>an accepting</span> <span m='2913690'>state</span> <span m='2914200'>is,</span>
  <span m='2914510'>is</span> <span m='2914800'>a</span> <span m='2915090'>Buchi</span>
  <span m='2915300'>Automata</span> <span m='2915630'>can</span> <span m='2915960'>only</span>
  <span m='2916320'>be</span> <span m='2916440'>valid</span> <span m='2916820'>if</span>
  <span m='2917752'>the sequence</span> <span m='2918220'>of</span> <span m='2918735'>transitions</span>
  <span m='2919810'>visits</span> <span m='2920240'>an</span> <span m='2920380'>accepting</span>
  <span m='2920770'>state</span> <span m='2921130'>an infinite</span> <span m='2921586'>amount
  of</span> <span m='2922042'>times.</span> </p><p><span m='2922954'>So</span> <span
  m='2923410'>I'll get into</span> <span m='2923870'>a couple</span> <span m='2924080'>examples.</span>
  <span m='2924974'>So</span> <span m='2925421'>let's say you want to</span> <span
  m='2925870'>model</span> <span m='2926190'>the</span> <span m='2926510'>ticking-tocking</span>
  <span m='2927474'>of a</span> <span m='2927956'>clock.</span> <span m='2928660'>This</span>
  <span m='2928940'>is</span> <span m='2929060'>just</span> <span m='2929310'>a regular</span>
  <span m='2929750'>finite state</span> <span m='2930190'>machine.</span> <span m='2931690'>As
  you can</span> <span m='2932150'>see,</span> <span m='2932340'>after</span> <span
  m='2932660'>some</span> <span m='2933070'>number</span> <span m='2933485'>of</span>
  <span m='2933900'>ticks and</span> <span m='2934190'>tocks,</span> <span m='2934560'>you
  get into</span> <span m='2934990'>S2,</span> <span m='2935780'>and</span> <span
  m='2935920'>you're in</span> <span m='2936220'>S2</span> <span m='2936630'>because
  you can</span> <span m='2937120'>be in</span> <span m='2937610'>transition</span>
  <span m='2938880'>only</span> <span m='2939090'>[INAUDIBLE]</span> <span m='2939350'>So
  you're</span> <span m='2939480'>in S2</span> <span m='2939970'>basically</span>
  <span m='2940530'>forever</span> <span m='2940800'>once</span> <span m='2941050'>you</span>
  <span m='2941110'>get to</span> <span m='2941320'>S2.</span> <span m='2941900'>So
  we</span> <span m='2942270'>can model</span> <span m='2942640'>this</span> <span
  m='2942790'>as a</span> <span m='2943070'>Buchi</span> <span m='2943340'>Automata</span>
  <span m='2943920'>by</span> <span m='2944020'>making</span> <span m='2944230'>S2</span>
  <span m='2945724'>an</span> <span m='2946176'>accepted</span> <span m='2946630'>state.</span>
  <span m='2947970'>This</span> <span m='2948170'>example,</span> <span m='2948495'>making</span>
  <span m='2948820'>it</span> <span m='2949010'>a Buchi</span> <span m='2949300'>Automata,</span>
  <span m='2949730'>doesn't</span> <span m='2950190'>really do</span> <span m='2950310'>anything</span>
  <span m='2950605'>for</span> <span m='2950900'>you.</span> <span m='2951180'>It's
  just</span> <span m='2951340'>kind</span> <span m='2951470'>of to</span> <span m='2951720'>illustrate</span>
  <span m='2953000'>what</span> <span m='2953230'>the</span> <span m='2953390'>accepting</span>
  <span m='2953530'>state</span> <span m='2953780'>does.</span> <span m='2954030'>So</span>
  <span m='2955020'>the</span> <span m='2955500'>accepting</span> <span m='2955670'>words</span>
  <span m='2955970'>are</span> <span m='2956280'>a sequence</span> <span m='2956590'>of</span>
  <span m='2957100'>transitions.</span> <span m='2957470'>In this</span> <span m='2957910'>case
  it</span> <span m='2958220'>would</span> <span m='2958530'>be</span> <span m='2958780'>an</span>
  <span m='2960040'>infinite</span> <span m='2960330'>combination</span> <span m='2960600'>of</span>
  <span m='2960870'>ticks</span> <span m='2961060'>and tocks</span> <span m='2961590'>that</span>
  <span m='2962130'>would</span> <span m='2962310'>make</span> <span m='2962610'>this</span>
  <span m='2962870'>Buchi</span> <span m='2963145'>Automata</span> <span m='2963480'>valid.</span>
  <span m='2964512'>Does</span> <span m='2964850'>that make</span> <span m='2965230'>sense.</span>
  <span m='2967218'>Questions</span> <span m='2967715'>about that?</span> <span m='2970810'>Here's
  another</span> <span m='2971120'>example,</span> <span m='2971340'>for</span> <span
  m='2971690'>example,</span> <span m='2971900'>if</span> <span m='2971990'>I have</span>
  <span m='2972370'>changed</span> <span m='2972695'>what</span> <span m='2973020'>my</span>
  <span m='2973210'>accepting</span> <span m='2973740'>state</span> <span m='2974130'>was.</span>
  <span m='2974780'>So</span> <span m='2975020'>if our</span> <span m='2975300'>accepting</span>
  <span m='2975550'>state was</span> <span m='2975750'>S1,</span> <span m='2976516'>I
  now have to</span> <span m='2976962'>visit S1</span> <span m='2977650'>an infinite</span>
  <span m='2978065'>amount of</span> <span m='2978480'>times</span> <span m='2978780'>for</span>
  <span m='2979180'>this</span> <span m='2979250'>Buchi</span> <span m='2979400'>Automata</span>
  <span m='2979660'>to</span> <span m='2979800'>be</span> <span m='2980270'>valid.</span>
  <span m='2980980'>That means</span> <span m='2981340'>the</span> <span m='2981700'>only</span>
  <span m='2982560'>valid</span> <span m='2983090'>sequence</span> <span m='2983620'>of</span>
  <span m='2984490'>transitions</span> <span m='2984745'>I</span> <span m='2985000'>could</span>
  <span m='2985180'>have</span> <span m='2985490'>is</span> <span m='2985780'>tock</span>
  <span m='2986070'>tick tick</span> <span m='2986340'>tick</span> <span m='2986610'>tick</span>
  <span m='2986850'>for</span> <span m='2987010'>an infinite amount</span> <span m='2987500'>of
  times.</span> <span m='2988130'>So you</span> <span m='2988555'>can kind of</span>
  <span m='2988980'>represent</span> <span m='2989830'>different</span> <span m='2990130'>things</span>
  <span m='2990830'>and</span> <span m='2991170'>different</span> <span m='2991420'>sequences</span>
  <span m='2991990'>of</span> <span m='2992220'>inputs</span> <span m='2992420'>you
  might want to</span> <span m='2992820'>have</span> <span m='2993190'>based on</span>
  <span m='2993820'>which</span> <span m='2993930'>accepting</span> <span m='2994170'>state</span>
  <span m='2994560'>you</span> <span m='2994720'>use.</span> </p><p><span m='2997596'>This
  is</span> <span m='2998050'>another</span> <span m='2998320'>example.</span> <span
  m='2998740'>If</span> <span m='2999160'>you</span> <span m='2999250'>wanted</span>
  <span m='2999400'>your</span> <span m='2999500'>clock to</span> <span m='2999855'>be</span>
  <span m='3000210'>tick</span> <span m='3000420'>tock</span> <span m='3000660'>tick</span>
  <span m='3000870'>tock</span> <span m='3001110'>tick</span> <span m='3001290'>tock,</span>
  <span m='3001920'>you can have</span> <span m='3002260'>more than</span> <span m='3002600'>one</span>
  <span m='3002930'>accepting</span> <span m='3003400'>state, and</span> <span m='3004190'>now
  I have to</span> <span m='3004340'>visit</span> <span m='3004640'>S0</span> <span
  m='3005220'>and</span> <span m='3005470'>S1</span> <span m='3005990'>an</span> <span
  m='3006456'>infinite</span> <span m='3006922'>amount of</span> <span m='3007390'>times</span>
  <span m='3008030'>if</span> <span m='3008360'>I</span> <span m='3008490'>want</span>
  <span m='3008730'>this</span> <span m='3008820'>Buchi</span> <span m='3009180'>Automata</span>
  <span m='3009540'>to be</span> <span m='3009780'>valid.</span> <span m='3011620'>So
  then</span> <span m='3011890'>the</span> <span m='3012200'>sequence</span> <span
  m='3012690'>of</span> <span m='3012850'>transitions</span> <span m='3013320'>I</span>
  <span m='3013440'>get</span> <span m='3013800'>is</span> <span m='3014010'>tick
  tock</span> <span m='3014220'>tick tock</span> <span m='3014632'>tick tock.</span>
  </p><p><span m='3015870'>Does anyone</span> <span m='3016030'>have any</span> <span
  m='3016507'>questions</span> <span m='3016984'>to really</span> <span m='3017461'>think
  about</span> <span m='3017938'>in general</span> <span m='3018415'>with Buchi</span>
  <span m='3018892'>Automata?</span> <span m='3022231'>OK.</span> </p><p><span m='3024620'>It
  might</span> <span m='3024820'>help</span> <span m='3025000'>to</span> <span m='3025120'>see</span>
  <span m='3026080'>how</span> <span m='3026530'>we model</span> <span m='3026840'>LTL</span>
  <span m='3027300'>as</span> <span m='3027786'>Buchi</span> <span m='3028272'>Automata.</span>
  <span m='3028758'>So</span> <span m='3030220'>here's</span> <span m='3030680'>an
  example</span> <span m='3031135'>of of</span> <span m='3031420'>these</span> <span
  m='3031675'>LTL</span> <span m='3032320'>formulas</span> <span m='3032800'>modeled</span>
  <span m='3033270'>as a</span> <span m='3033660'>Buchi</span> <span m='3033860'>Automata.</span>
  <span m='3035192'>I guess</span> <span m='3035640'>take</span> <span m='3035830'>a</span>
  <span m='3035860'>few</span> <span m='3036070'>minutes</span> <span m='3036430'>and</span>
  <span m='3036520'>see</span> <span m='3036660'>if</span> <span m='3036760'>you</span>
  <span m='3036850'>can</span> <span m='3037600'>get</span> <span m='3037900'>which</span>
  <span m='3038160'>one</span> <span m='3039260'>this</span> <span m='3039420'>one</span>
  <span m='3039570'>might be.</span> </p><p><span m='3053954'>AUDIENCE:</span> <span
  m='3054119'>[INAUDIBLE]</span> </p><p><span m='3055450'>GUEST SPEAKER:</span> <span
  m='3055540'>Yeah.</span> <span m='3056590'>Just so that</span> <span m='3057070'>everyone
  can kind</span> <span m='3057550'>of</span> <span m='3057640'>see</span> <span m='3057960'>that,</span>
  <span m='3058706'>and future</span> <span m='3059162'>events,</span> <span m='3059620'>we
  remember</span> <span m='3060340'>that</span> <span m='3060805'>means that</span>
  <span m='3061270'>eventually</span> <span m='3061750'>p has</span> <span m='3061980'>to</span>
  <span m='3062070'>be</span> <span m='3062260'>true</span> <span m='3063070'>at</span>
  <span m='3063160'>least</span> <span m='3063480'>once.</span> <span m='3064540'>So</span>
  <span m='3065320'>from</span> <span m='3065700'>any</span> <span m='3066010'>sort</span>
  <span m='3066250'>of</span> <span m='3067020'>input</span> <span m='3067365'>state,</span>
  <span m='3068150'>you</span> <span m='3068650'>go to</span> <span m='3069150'>S0,</span>
  <span m='3069740'>and then</span> <span m='3070076'>I do</span> <span m='3070412'>have</span>
  <span m='3070750'>amount</span> <span m='3071100'>p</span> <span m='3071340'>for</span>
  <span m='3071470'>some</span> <span m='3071680'>amount of</span> <span m='3072010'>time,</span>
  <span m='3072440'>but as</span> <span m='3072845'>soon as</span> <span m='3073250'>I</span>
  <span m='3073340'>have</span> <span m='3073610'>p,</span> <span m='3074504'>I have</span>
  <span m='3074951'>to</span> <span m='3075400'>get to</span> <span m='3075580'>p,</span>
  <span m='3076063'>because I have to be</span> <span m='3076546'>in my</span> <span
  m='3077030'>subject</span> <span m='3077160'>state</span> <span m='3077340'>an infinite
  amount</span> <span m='3077740'>of</span> <span m='3078140'>times.</span> <span
  m='3078300'>So</span> <span m='3078550'>I have</span> <span m='3078680'>to</span>
  <span m='3078945'>execute</span> <span m='3079450'>p</span> <span m='3079740'>at</span>
  <span m='3079850'>some</span> <span m='3080100'>point</span> <span m='3080340'>to</span>
  <span m='3080670'>get</span> <span m='3080880'>to my</span> <span m='3081370'>accepting</span>
  <span m='3081850'>state</span> <span m='3082290'>for</span> <span m='3082560'>this</span>
  <span m='3082750'>Buchi</span> <span m='3083200'>Automata</span> <span m='3083650'>to
  be</span> <span m='3084100'>valid. And then once</span> <span m='3084550'>I'm at</span>
  <span m='3085000'>S1,</span> <span m='3085950'>I</span> <span m='3086100'>can</span>
  <span m='3086450'>have</span> <span m='3086680'>any</span> <span m='3086950'>other</span>
  <span m='3087470'>amount</span> <span m='3087620'>of</span> <span m='3087760'>inputs.</span>
  <span m='3088050'>I'll</span> <span m='3088360'>always</span> <span m='3088780'>be
  in S1,</span> <span m='3089410'>and</span> <span m='3089840'>that's what</span>
  <span m='3090270'>the</span> <span m='3090420'>true</span> <span m='3091130'>label</span>
  <span m='3091625'>means.</span> </p><p><span m='3094100'>AUDIENCE:</span> <span
  m='3094165'>And</span> <span m='3094230'>it's</span> <span m='3094360'>also</span>
  <span m='3094670'>something</span> <span m='3094810'>stronger,</span> <span m='3095320'>right,</span>
  <span m='3095780'>which is</span> <span m='3096000'>you could--</span> <span m='3096290'>it's</span>
  <span m='3096580'>eventually</span> <span m='3096970'>globally?</span> </p><p><span
  m='3097875'>GUEST SPEAKER:</span> <span m='3098102'>Right.</span> <span m='3100150'>Yeah,
  so</span> <span m='3100600'>actually</span> <span m='3102910'>in</span> <span m='3103090'>this</span>
  <span m='3103240'>case,</span> <span m='3103570'>after</span> <span m='3104050'>it
  gets</span> <span m='3104530'>here,</span> <span m='3105730'>my input</span> <span
  m='3106150'>could be</span> <span m='3106570'>anything.</span> <span m='3106990'>So</span>
  <span m='3107170'>this</span> <span m='3107410'>basically</span> <span m='3107580'>just
  says</span> <span m='3107900'>that</span> <span m='3108860'>for my</span> <span
  m='3109320'>initial</span> <span m='3109780'>state,</span> <span m='3110260'>I</span>
  <span m='3110350'>have</span> <span m='3110560'>to</span> <span m='3110680'>execute</span>
  <span m='3110950'>p</span> <span m='3111110'>at least</span> <span m='3111550'>once</span>
  <span m='3111860'>to get to</span> <span m='3112140'>this</span> <span m='3112410'>accepting</span>
  <span m='3112680'>state,</span> <span m='3113215'>and</span> <span m='3113510'>once</span>
  <span m='3113610'>I'm</span> <span m='3113890'>there,</span> <span m='3114420'>I
  can</span> <span m='3114680'>be there--</span> <span m='3115720'>I'm</span> <span
  m='3115840'>always</span> <span m='3116140'>there.</span> <span m='3116730'>Any
  input</span> <span m='3117050'>will</span> <span m='3117530'>believe</span> <span
  m='3117790'>me</span> <span m='3118055'>in</span> <span m='3118320'>S1.</span> </p><p><span
  m='3119576'>AUDIENCE:</span> <span m='3119790'>So</span> <span m='3120004'>just
  to make</span> <span m='3120432'>this</span> <span m='3120860'>clear</span> <span
  m='3121090'>for</span> <span m='3121545'>myself</span> <span m='3122000'>and maybe</span>
  <span m='3122455'>for others,</span> <span m='3122910'>the</span> <span m='3123365'>data</span>
  <span m='3123820'>string</span> <span m='3124275'>executed</span> <span m='3124730'>that's</span>
  <span m='3125185'>at</span> <span m='3126100'>R</span> <span m='3126371'>state</span>
  <span m='3127741'>something</span> <span m='3127970'>that's</span> <span m='3128815'>on
  the</span> <span m='3129270'>loop.</span> <span m='3129390'>If</span> <span m='3129760'>you
  go</span> <span m='3130130'>from</span> <span m='3130310'>s0</span> <span m='3130575'>to
  s0,</span> <span m='3130840'>that's</span> <span m='3131140'>essentially</span>
  <span m='3131650'>saying</span> <span m='3131930'>that</span> <span m='3132140'>one</span>
  <span m='3132565'>of</span> <span m='3132990'>the</span> <span m='3133170'>nodes</span>
  <span m='3133400'>is</span> <span m='3133550'>not p.</span> <span m='3133967'>If</span>
  <span m='3134384'>you go</span> <span m='3134801'>from</span> <span m='3135220'>s0</span>
  <span m='3135460'>to</span> <span m='3135835'>s1,</span> <span m='3136210'>it's
  saying</span> <span m='3136490'>that</span> <span m='3136770'>one of the</span>
  <span m='3137050'>nodes</span> <span m='3137250'>is</span> <span m='3137692'>p.</span>
  </p><p><span m='3138134'>GUEST SPEAKER:</span> <span m='3138355'>Yeah.</span> </p><p><span
  m='3138576'>AUDIENCE:</span> <span m='3138686'>If</span> <span m='3138796'>you</span>
  <span m='3138906'>go</span> <span m='3139018'>from</span> <span m='3139460'>s1 to
  s1</span> <span m='3139660'>and</span> <span m='3139930'>take</span> <span m='3140200'>whatever</span>
  <span m='3140540'>it would be</span> <span m='3141036'>because</span> <span m='3141532'>you</span>
  <span m='3142028'>set it true.</span> </p><p><span m='3145010'>AUDIENCE:</span>
  <span m='3145050'>So</span> <span m='3145090'>if</span> <span m='3145340'>you</span>
  <span m='3145620'>put</span> <span m='3145890'>p</span> <span m='3146540'>where</span>
  <span m='3146860'>the true</span> <span m='3147310'>is right now,</span> <span m='3147430'>then</span>
  <span m='3147860'>you</span> <span m='3147960'>you won't</span> <span m='3148110'>have</span>
  <span m='3148270'>to</span> <span m='3148370'>go</span> <span m='3148590'>through.</span>
  </p><p><span m='3149370'>PROFESSOR:</span> <span m='3149525'>Right.</span> <span
  m='3149680'>That's</span> <span m='3149860'>what</span> <span m='3149980'>I</span>
  <span m='3150020'>missed.</span> <span m='3152020'>By</span> <span m='3152270'>the</span>
  <span m='3152450'>way,</span> <span m='3153300'>you</span> <span m='3153460'>guys</span>
  <span m='3153670'>have</span> <span m='3153850'>25</span> <span m='3154329'>more</span>
  <span m='3154808'>minutes.</span> </p><p><span m='3158161'>GUEST SPEAKER:</span>
  <span m='3158320'>So</span> <span m='3158479'>that's</span> <span m='3158640'>what</span>
  <span m='3159120'>we talked about.</span> <span m='3159520'>This is</span> <span
  m='3159790'>future.</span> <span m='3161232'>So</span> <span m='3161730'>the</span>
  <span m='3162000'>accepted</span> <span m='3162526'>sequence</span> <span m='3163220'>of</span>
  <span m='3163840'>propositions</span> <span m='3164550'>would</span> <span m='3164830'>be</span>
  <span m='3165085'>not</span> <span m='3165340'>to</span> <span m='3165605'>not p.</span>
  <span m='3166230'>Then</span> <span m='3166390'>you have</span> <span m='3167110'>p.</span>
  <span m='3167600'>Then it can</span> <span m='3167840'>be</span> <span m='3168220'>anything
  after</span> <span m='3168540'>you get to</span> <span m='3168680'>p.</span> </p><p><span
  m='3169450'>And</span> <span m='3169900'>then</span> <span m='3170266'>in this</span>
  <span m='3170632'>case,</span> <span m='3171000'>for</span> <span m='3171270'>Buchi</span>
  <span m='3171540'>Automata</span> <span m='3171850'>states, which</span> <span m='3172180'>are</span>
  <span m='3172630'>like</span> <span m='3172690'>[INAUDIBLE],</span> <span m='3173350'>slightly</span>
  <span m='3173680'>different</span> <span m='3173950'>than</span> <span m='3174130'>the</span>
  <span m='3174270'>LTL</span> <span m='3174660'>states</span> <span m='3174980'>we've</span>
  <span m='3175000'>been</span> <span m='3175120'>talking</span> <span m='3175480'>about.</span>
  <span m='3176153'>In this</span> <span m='3176496'>case,</span> <span m='3176840'>you're
  in</span> <span m='3177160'>s0.</span> <span m='3177350'>And</span> <span m='3177610'>then</span>
  <span m='3177860'>once</span> <span m='3178070'>you get</span> <span m='3178310'>to</span>
  <span m='3178430'>s1,</span> <span m='3178620'>you're forever</span> <span m='3178970'>in</span>
  <span m='3179240'>s1.</span> </p><p><span m='3183470'>So</span> <span m='3183680'>globally,</span>
  <span m='3184010'>looks</span> <span m='3184400'>pretty</span> <span m='3184790'>similar</span>
  <span m='3185270'>to</span> <span m='3185590'>this.</span> <span m='3186690'>Take</span>
  <span m='3186850'>a</span> <span m='3187040'>few minutes to</span> <span m='3187470'>think</span>
  <span m='3187730'>about</span> <span m='3188330'>how</span> <span m='3188840'>I</span>
  <span m='3189050'>might change</span> <span m='3189520'>this</span> <span m='3189990'>Buchi</span>
  <span m='3190450'>Automata</span> <span m='3190850'>to</span> <span m='3191750'>[INAUDIBLE]</span>
  <span m='3191950'>globally</span> <span m='3192180'>after</span> <span m='3192440'>[INAUDIBLE]</span>
  </p><p><span m='3201845'>AUDIENCE:</span> <span m='3202092'>[INAUDIBLE]</span> </p><p><span
  m='3204815'>GUEST SPEAKER:</span> <span m='3205062'>Yeah,</span> <span m='3205310'>exactly.</span>
  <span m='3209290'>So</span> <span m='3209460'>you</span> <span m='3209600'>have</span>
  <span m='3210060'>initially,</span> <span m='3210640'>your</span> <span m='3210820'>first</span>
  <span m='3211090'>state</span> <span m='3211300'>by</span> <span m='3211630'>your</span>
  <span m='3211900'>n</span> <span m='3212170'>because</span> <span m='3212560'>p</span>
  <span m='3212920'>has</span> <span m='3213100'>to</span> <span m='3213220'>be</span>
  <span m='3213340'>true</span> <span m='3214060'>forever</span> <span m='3214570'>after</span>
  <span m='3214750'>you</span> <span m='3214810'>get</span> <span m='3214930'>to</span>
  <span m='3215020'>this first</span> <span m='3215370'>state.</span> <span m='3215940'>You
  have</span> <span m='3216060'>an</span> <span m='3216310'>accepting</span> <span
  m='3216460'>state</span> <span m='3216830'>in</span> <span m='3217200'>p.</span>
  <span m='3218320'>You</span> <span m='3218590'>can</span> <span m='3218650'>also</span>
  <span m='3218920'>model</span> <span m='3219402'>not</span> <span m='3219884'>p.</span>
  <span m='3220850'>If you</span> <span m='3220960'>want to,</span> <span m='3221410'>you
  can also</span> <span m='3221860'>just</span> <span m='3222090'>have</span> <span
  m='3222300'>this</span> <span m='3222800'>single</span> <span m='3223040'>see</span>
  <span m='3223360'>which</span> <span m='3223713'>would</span> <span m='3224066'>encapsulate</span>
  <span m='3224420'>exactly</span> <span m='3224750'>what</span> <span m='3225217'>Buchi</span>
  <span m='3225684'>is.</span> <span m='3227552'>This</span> <span m='3228019'>is</span>
  <span m='3228486'>how</span> <span m='3228953'>you go</span> <span m='3229420'>from</span>
  <span m='3229575'>LTL</span> <span m='3229730'>to</span> <span m='3229887'>Buchi</span>
  <span m='3230360'>Automata.</span> </p><p><span m='3230940'>In</span> <span m='3231220'>a
  real-world</span> <span m='3231950'>scenario,</span> <span m='3232150'>we</span>
  <span m='3232415'>have</span> <span m='3232680'>multiple</span> <span m='3233010'>LTL</span>
  <span m='3233050'>formulas</span> <span m='3233917'>all</span> <span m='3234304'>combined.</span>
  <span m='3235080'>You're</span> <span m='3235380'>Buchi</span> <span m='3235735'>Automata
  are</span> <span m='3236090'>going</span> <span m='3236320'>to</span> <span m='3236380'>look</span>
  <span m='3236590'>a little bit</span> <span m='3237020'>more</span> <span m='3237220'>complicated</span>
  <span m='3237480'>than</span> <span m='3237740'>this.</span> <span m='3238930'>Try</span>
  <span m='3239320'>multiple</span> <span m='3239600'>accepting</span> <span m='3239830'>states.</span>
  <span m='3242290'>There's</span> <span m='3242500'>a</span> <span m='3242925'>full
  weighted</span> <span m='3243350'>model</span> <span m='3244155'>of</span> <span
  m='3244570'>what</span> <span m='3244800'>an</span> <span m='3245270'>LTL</span>
  <span m='3245740'>is trying to</span> <span m='3246210'>represent.</span> </p><p><span
  m='3249826'>AUDIENCE:</span> <span m='3250019'>If</span> <span m='3250212'>we</span>
  <span m='3250600'>have</span> <span m='3250870'>the</span> <span m='3251060'>not
  p</span> <span m='3251466'>transition out of there,</span> <span m='3252684'>Like</span>
  <span m='3253090'>it's</span> <span m='3253490'>possible</span> <span m='3254080'>you
  can</span> <span m='3254435'>come</span> <span m='3254790'>into</span> <span m='3255030'>s0</span>
  <span m='3255545'>to</span> <span m='3255860'>accept</span> <span m='3256100'>the</span>
  <span m='3256310'>Buchi</span> <span m='3256600'>Automata</span> <span m='3256870'>because</span>
  <span m='3256990'>it</span> <span m='3257335'>would</span> <span m='3257680'>go
  to</span> <span m='3257920'>s1,</span> <span m='3258305'>right?</span> </p><p><span
  m='3259465'>GUEST SPEAKER:</span> <span m='3259657'>Accepting</span> <span m='3259850'>a</span>
  <span m='3260250'>Buchi</span> <span m='3260730'>Automata</span> <span m='3261210'>after
  that,</span> <span m='3261690'>it's</span> <span m='3262170'>a little</span> <span
  m='3262603'>confusing.</span> <span m='3263036'>A Buchi</span> <span m='3263470'>Automata</span>
  <span m='3263740'>is only</span> <span m='3264010'>valid</span> <span m='3264170'>if</span>
  <span m='3264380'>the</span> <span m='3264735'>infinite sequence</span> <span m='3265090'>of</span>
  <span m='3265250'>states</span> <span m='3266102'>satisfies</span> <span m='3266594'>it.</span>
  <span m='3268345'>If</span> <span m='3268760'>I</span> <span m='3269175'>were</span>
  <span m='3269590'>to</span> <span m='3269860'>go</span> <span m='3270327'>the p</span>
  <span m='3270794'>instead</span> <span m='3271261'>of</span> <span m='3271728'>not
  p,</span> <span m='3273129'>my</span> <span m='3273600'>sequence</span> <span m='3273790'>would
  accept a</span> <span m='3274252'>transition of</span> <span m='3274714'>p,</span>
  <span m='3275176'>p,</span> <span m='3275640'>not</span> <span m='3275970'>p.</span>
  <span m='3276456'>Then</span> <span m='3276942'>that would not be</span> <span m='3277430'>a
  valid</span> <span m='3278315'>sequence</span> <span m='3278810'>of</span> <span
  m='3279305'>transition</span> <span m='3279800'>for this</span> <span m='3280295'>Buchi</span>
  <span m='3280790'>Automata</span> <span m='3281260'>because</span> <span m='3281750'>I'm</span>
  <span m='3282080'>transitioning</span> <span m='3282260'>out of</span> <span m='3282590'>my</span>
  <span m='3282970'>accepting</span> <span m='3283180'>state,</span> <span m='3283380'>which
  I</span> <span m='3283670'>need</span> <span m='3283890'>to</span> <span m='3284310'>have
  been in</span> <span m='3284730'>for at</span> <span m='3285160'>least the</span>
  <span m='3285410'>amount</span> <span m='3285825'>of times.</span> <span m='3286240'>And</span>
  <span m='3286520'>there's</span> <span m='3286700'>no</span> <span m='3286940'>way</span>
  <span m='3287050'>I</span> <span m='3287170'>can</span> <span m='3287300'>get</span>
  <span m='3287450'>back</span> <span m='3287924'>to</span> <span m='3288398'>success.</span>
  </p><p><span m='3296436'>Also,</span> <span m='3297270'>a more defined algorithm
  [INAUDIBLE]</span> <span m='3298420'>an</span> <span m='3298680'>intuitive</span>
  <span m='3299320'>way</span> <span m='3299700'>to build a</span> <span m='3299980'>Buchi</span>
  <span m='3300408'>Automata,</span> <span m='3300836'>or</span> <span m='3301264'>is</span>
  <span m='3301692'>an</span> <span m='3302120'>algorithm.</span> <span m='3302750'>The
  other one</span> <span m='3303030'>that's</span> <span m='3303462'>most popularly</span>
  <span m='3303894'>used was</span> <span m='3304326'>developed</span> <span m='3304760'>by</span>
  <span m='3305180'>[INAUDIBLE].</span> <span m='3305830'>This</span> <span m='3306100'>is</span>
  <span m='3306330'>a</span> <span m='3306540'>pseudocode</span> <span m='3307320'>version</span>
  <span m='3307710'>of</span> <span m='3307800'>the</span> <span m='3307940'>algorithm.</span>
  <span m='3309885'>We go from</span> <span m='3310360'>LTL</span> <span m='3310820'>to</span>
  <span m='3311080'>Buchi.</span> </p><p><span m='3311380'>As</span> <span m='3311765'>you've</span>
  <span m='3312150'>noticed, it</span> <span m='3312540'>actually uses</span> <span
  m='3312930'>progression,</span> <span m='3313960'>which</span> <span m='3313980'>is</span>
  <span m='3314040'>something</span> <span m='3314400'>that</span> <span m='3315430'>planners</span>
  <span m='3316390'>that</span> <span m='3316870'>take</span> <span m='3317200'>PDDL</span>
  <span m='3317970'>use</span> <span m='3318300'>to</span> <span m='3318620'>generate</span>
  <span m='3318990'>plans.</span> <span m='3320210'>An</span> <span m='3320555'>important</span>
  <span m='3320900'>thing</span> <span m='3321150'>to note,</span> <span m='3321460'>which</span>
  <span m='3321770'>I</span> <span m='3322070'>won't go into</span> <span m='3322470'>too
  much</span> <span m='3322870'>detail,</span> <span m='3323620'>this</span> <span
  m='3324030'>algorithm</span> <span m='3324570'>generates</span> <span m='3324890'>a</span>
  <span m='3325120'>generalized</span> <span m='3325395'>Buchi</span> <span m='3325532'>Automata,</span>
  <span m='3326250'>which</span> <span m='3326670'>you</span> <span m='3326800'>then</span>
  <span m='3328160'>change</span> <span m='3328420'>to a</span> <span m='3328650'>simple</span>
  <span m='3328955'>Buchi</span> <span m='3329107'>Automata.</span> </p><p><span m='3330040'>The</span>
  <span m='3330160'>difference</span> <span m='3330360'>is,</span> <span m='3330790'>the</span>
  <span m='3331220'>generalized</span> <span m='3331420'>Buchi</span> <span m='3331470'>Automata</span>
  <span m='3332060'>has</span> <span m='3332620'>a</span> <span m='3332740'>set</span>
  <span m='3333480'>of</span> <span m='3333650'>sets</span> <span m='3334060'>of</span>
  <span m='3334370'>accepting</span> <span m='3334690'>states.</span> <span m='3335940'>For</span>
  <span m='3336100'>a</span> <span m='3336350'>generalized</span> <span m='3336720'>Buchi</span>
  <span m='3336890'>Automata</span> <span m='3337060'>to</span> <span m='3337400'>be</span>
  <span m='3337610'>accepted,</span> <span m='3339200'>you need</span> <span m='3339500'>to</span>
  <span m='3339760'>visit</span> <span m='3340690'>an</span> <span m='3340940'>accepting</span>
  <span m='3341130'>state in</span> <span m='3341520'>each</span> <span m='3341730'>one</span>
  <span m='3341880'>of</span> <span m='3341980'>those</span> <span m='3342070'>sets</span>
  <span m='3342511'>of</span> <span m='3342952'>accepting states.</span> <span m='3343393'>At
  least</span> <span m='3343834'>one of</span> <span m='3344275'>those</span> <span
  m='3344716'>states</span> <span m='3345157'>has to</span> <span m='3345600'>be listed.</span>
  </p><p><span m='3346220'>For</span> <span m='3346670'>a</span> <span m='3346950'>simple</span>
  <span m='3347230'>Buchi</span> <span m='3347335'>Automata,</span> <span m='3347440'>you</span>
  <span m='3347935'>only</span> <span m='3348430'>have</span> <span m='3348730'>one</span>
  <span m='3348950'>set of</span> <span m='3349110'>accepting</span> <span m='3349410'>states.</span>
  <span m='3349950'>And</span> <span m='3350190'>you</span> <span m='3350340'>can</span>
  <span m='3350605'>visit</span> <span m='3350870'>any one</span> <span m='3351120'>of</span>
  <span m='3351350'>those</span> <span m='3351660'>for</span> <span m='3352270'>the</span>
  <span m='3352400'>Buchi</span> <span m='3352627'>Automata</span> <span m='3352855'>to</span>
  <span m='3353310'>be</span> <span m='3353580'>valid.</span> <span m='3354512'>On
  the</span> <span m='3354980'>translation</span> <span m='3355210'>between</span>
  <span m='3355440'>those two</span> <span m='3355620'>is a little bit</span> <span
  m='3356024'>more complicated.</span> <span m='3357640'>We'll</span> <span m='3357820'>have</span>
  <span m='3358120'>paper</span> <span m='3358340'>in the</span> <span m='3358690'>preference</span>
  <span m='3359110'>that</span> <span m='3359581'>will</span> <span m='3360052'>walk
  through</span> <span m='3360523'>how to do that.</span> <span m='3361465'>But we're
  not going to do that now.</span> </p><p><span m='3364291'>This</span> <span m='3364762'>is</span>
  <span m='3365233'>a</span> <span m='3365710'>progression</span> <span m='3365800'>algorithm.</span>
  <span m='3367800'>Basically,</span> <span m='3368970'>it</span> <span m='3369420'>just</span>
  <span m='3369690'>tells</span> <span m='3369990'>you</span> <span m='3370080'>how</span>
  <span m='3370470'>if</span> <span m='3370710'>have</span> <span m='3370910'>a</span>
  <span m='3371390'>LTL</span> <span m='3371560'>formula</span> <span m='3371750'>f</span>
  <span m='3372260'>and</span> <span m='3372690'>some</span> <span m='3373070'>current</span>
  <span m='3373410'>state</span> <span m='3373665'>N--</span> <span m='3374180'>and</span>
  <span m='3375310'>usually</span> <span m='3375860'>they</span> <span m='3376150'>involve</span>
  <span m='3376470'>some</span> <span m='3376790'>time step</span> <span m='3377110'>because</span>
  <span m='3377230'>we're in the</span> <span m='3377703'>real world</span> <span
  m='3378176'>and we can't</span> <span m='3378650'>really</span> <span m='3378900'>model</span>
  <span m='3379820'>infinite</span> <span m='3380210'>amount</span> <span m='3380550'>of</span>
  <span m='3380640'>time,</span> <span m='3381110'>and</span> <span m='3381570'>we</span>
  <span m='3381770'>have to</span> <span m='3382000'>make it</span> <span m='3382300'>discrete.</span>
  <span m='3383890'>So</span> <span m='3384180'>we</span> <span m='3384435'>have some</span>
  <span m='3384690'>time step,</span> <span m='3384945'>which</span> <span m='3385200'>means</span>
  <span m='3385610'>successive</span> <span m='3385750'>state.</span> </p><p><span
  m='3388125'>How do you</span> <span m='3388600'>push</span> <span m='3389486'>certain</span>
  <span m='3389962'>LTL</span> <span m='3390440'>formulas</span> <span m='3390650'>onto</span>
  <span m='3391370'>next</span> <span m='3391720'>states</span> <span m='3391820'>to
  be</span> <span m='3392030'>evaluated</span> <span m='3392470'>later?</span> <span
  m='3393792'>For</span> <span m='3394184'>example,</span> <span m='3394576'>I'll</span>
  <span m='3394970'>take</span> <span m='3395180'>this</span> <span m='3395635'>next</span>
  <span m='3396090'>f</span> <span m='3396340'>as</span> <span m='3396736'>an</span>
  <span m='3397132'>example.</span> <span m='3397530'>So</span> <span m='3397650'>if</span>
  <span m='3398055'>f</span> <span m='3398460'>was a</span> <span m='3398710'>next
  f of</span> <span m='3399200'>some</span> <span m='3399860'>LTL</span> <span m='3400080'>formula,</span>
  <span m='3400730'>you</span> <span m='3400990'>need</span> <span m='3401200'>to</span>
  <span m='3401980'>append</span> <span m='3402680'>that</span> <span m='3403070'>formula</span>
  <span m='3403250'>to</span> <span m='3403360'>the</span> <span m='3403730'>next</span>
  <span m='3404220'>state</span> <span m='3404936'>to</span> <span m='3405292'>be</span>
  <span m='3405650'>evaluated</span> <span m='3406010'>in the</span> <span m='3406450'>next</span>
  <span m='3406600'>state</span> <span m='3406820'>to see if that's</span> <span m='3407320'>going
  to be</span> <span m='3407820'>true</span> <span m='3408100'>or not.</span> </p><p><span
  m='3409486'>Similar</span> <span m='3409950'>things</span> <span m='3410280'>for</span>
  <span m='3410742'>LTL.</span> <span m='3411204'>And</span> <span m='3413052'>I</span>
  <span m='3413514'>won't</span> <span m='3413980'>go through</span> <span m='3414250'>this</span>
  <span m='3414510'>[INAUDIBLE]</span> <span m='3414770'>it's</span> <span m='3414950'>here</span>
  <span m='3415428'>for</span> <span m='3415906'>reference.</span> <span m='3419360'>The</span>
  <span m='3419540'>next</span> <span m='3419930'>step to this process</span> <span
  m='3420080'>is going</span> <span m='3420260'>from</span> <span m='3420710'>Buchi
  Automata,</span> <span m='3420950'>that's</span> <span m='3421180'>a</span> <span
  m='3421370'>PDDL2.</span> <span m='3423050'>This</span> <span m='3423290'>process
  is</span> <span m='3423980'>confusing.</span> <span m='3424465'>At least it is</span>
  <span m='3424860'>confusing for</span> <span m='3425100'>me</span> <span m='3425565'>to
  understand.</span> </p><p><span m='3426960'>The</span> <span m='3427310'>first</span>
  <span m='3427610'>thing</span> <span m='3427730'>I'll</span> <span m='3427850'>say</span>
  <span m='3428210'>is</span> <span m='3428390'>that</span> <span m='3428690'>Buchi</span>
  <span m='3429060'>states are</span> <span m='3429170'>not</span> <span m='3429440'>equivalent</span>
  <span m='3429950'>to</span> <span m='3430190'>traditional</span> <span m='3430570'>PDDL</span>
  <span m='3430950'>states.</span> <span m='3431330'>In a</span> <span m='3431710'>PDDL</span>
  <span m='3432070'>state,</span> <span m='3432463'>if</span> <span m='3432856'>you
  have</span> <span m='3433250'>two</span> <span m='3433610'>states,</span> <span
  m='3434570'>you</span> <span m='3434950'>have</span> <span m='3435330'>the</span>
  <span m='3435710'>same</span> <span m='3436020'>propositions</span> <span m='3436550'>that</span>
  <span m='3436670'>are</span> <span m='3436810'>true</span> <span m='3437070'>and</span>
  <span m='3437270'>false,</span> <span m='3437540'>those</span> <span m='3437630'>states</span>
  <span m='3438020'>are</span> <span m='3438461'>identical.</span> <span m='3438902'>In</span>
  <span m='3439343'>the</span> <span m='3439784'>Buchi Automata,</span> <span m='3440225'>that's</span>
  <span m='3440666'>not</span> <span m='3441107'>necessarily</span> <span m='3441550'>true.</span>
  </p><p><span m='3443133'>In</span> <span m='3443564'>the</span> <span m='3443995'>Buchi
  Automata</span> <span m='3444430'>you also</span> <span m='3444730'>have to</span>
  <span m='3445030'>encapsulate</span> <span m='3445830'>which</span> <span m='3446120'>transitions</span>
  <span m='3446470'>you</span> <span m='3446820'>can make</span> <span m='3447010'>out</span>
  <span m='3447360'>of</span> <span m='3447510'>each</span> <span m='3447790'>Buchi</span>
  <span m='3448060'>state.</span> <span m='3448560'>So</span> <span m='3448980'>s1</span>
  <span m='3449180'>and</span> <span m='3449320'>s2</span> <span m='3450280'>couldn't</span>
  <span m='3450710'>have</span> <span m='3451250'>the</span> <span m='3451370'>same</span>
  <span m='3451910'>set</span> <span m='3452280'>of</span> <span m='3452650'>propositions</span>
  <span m='3453020'>that</span> <span m='3453370'>are</span> <span m='3453862'>[INAUDIBLE]</span>
  <span m='3454354'>hold.</span> <span m='3455830'>But</span> <span m='3456130'>out</span>
  <span m='3456410'>of</span> <span m='3456690'>s1--</span> <span m='3457290'>actually,</span>
  <span m='3457686'>back</span> <span m='3458082'>up.</span> <span m='3458815'>This</span>
  <span m='3459150'>is</span> <span m='3459410'>the</span> <span m='3459640'>Buchi
  Automata</span> <span m='3460045'>for</span> <span m='3460450'>FutureGlobally,</span>
  <span m='3462230'>which</span> <span m='3462530'>is</span> <span m='3462860'>what</span>
  <span m='3463280'>[INAUDIBLE]</span> <span m='3463595'>was</span> <span m='3463910'>talking</span>
  <span m='3464195'>about.</span> <span m='3464480'>So</span> <span m='3464630'>if
  I</span> <span m='3464920'>enter</span> <span m='3465210'>an</span> <span m='3465510'>f1,</span>
  <span m='3465875'>the</span> <span m='3466240'>star</span> <span m='3466500'>means</span>
  <span m='3466760'>I can have</span> <span m='3467170'>any</span> <span m='3469590'>transition</span>
  <span m='3469890'>that</span> <span m='3470190'>I</span> <span m='3470490'>want</span>
  <span m='3471050'>in</span> <span m='3471320'>s1.</span> <span m='3472560'>At</span>
  <span m='3472920'>some</span> <span m='3473130'>point,</span> <span m='3473430'>I
  make</span> <span m='3473500'>the</span> <span m='3473820'>transition</span> <span
  m='3474190'>p</span> <span m='3474560'>and whatever</span> <span m='3474930'>the</span>
  <span m='3475250'>s2,</span> <span m='3475800'>I</span> <span m='3475950'>have</span>
  <span m='3476336'>to take</span> <span m='3476722'>transition p</span> <span m='3477110'>forever.</span>
  </p><p><span m='3480240'>However,</span> <span m='3481582'>if</span> <span m='3482018'>I
  get</span> <span m='3482454'>a</span> <span m='3482890'>sequence</span> <span m='3483330'>of</span>
  <span m='3483520'>inputs,</span> <span m='3483960'>let's</span> <span m='3484270'>say</span>
  <span m='3484640'>I get</span> <span m='3485010'>p</span> <span m='3485380'>and</span>
  <span m='3485790'>then</span> <span m='3486140'>b,</span> <span m='3486590'>and</span>
  <span m='3486930'>p</span> <span m='3487270'>again,</span> <span m='3490200'>and</span>
  <span m='3490320'>then</span> <span m='3490610'>p</span> <span m='3490760'>again,</span>
  <span m='3491000'>it's not clear</span> <span m='3491330'>if</span> <span m='3491790'>I'm
  in</span> <span m='3492250'>s1</span> <span m='3492640'>or s2</span> <span m='3492730'>because</span>
  <span m='3493190'>in s1</span> <span m='3493480'>I can</span> <span m='3493740'>execute</span>
  <span m='3494000'>any kind of state</span> <span m='3494250'>I want.</span> <span
  m='3496070'>In</span> <span m='3496290'>s1</span> <span m='3496705'>I</span> <span
  m='3497120'>can</span> <span m='3497480'>execute</span> <span m='3497765'>any</span>
  <span m='3498050'>transition</span> <span m='3498500'>I</span> <span m='3498590'>want</span>
  <span m='3498950'>in s1.</span> <span m='3499140'>2</span> <span m='3499380'>I</span>
  <span m='3499630'>have</span> <span m='3499780'>to</span> <span m='3500000'>execute</span>
  <span m='3500440'>only</span> <span m='3500690'>p.</span> </p><p><span m='3501500'>So</span>
  <span m='3501680'>if I</span> <span m='3502093'>got a</span> <span m='3502506'>sequence</span>
  <span m='3502920'>of</span> <span m='3503230'>p's,</span> <span m='3503696'>I could
  be</span> <span m='3504162'>in either</span> <span m='3504628'>state.</span> <span
  m='3505560'>You</span> <span m='3505790'>need</span> <span m='3506810'>something</span>
  <span m='3507200'>else</span> <span m='3507470'>to</span> <span m='3507750'>activate</span>
  <span m='3507860'>PDDL2</span> <span m='3508340'>to</span> <span m='3508580'>basically</span>
  <span m='3509120'>to</span> <span m='3509390'>determine</span> <span m='3509720'>which</span>
  <span m='3509930'>state</span> <span m='3510180'>you're</span> <span m='3510400'>and</span>
  <span m='3510730'>which</span> <span m='3511110'>transitions you</span> <span m='3511600'>can
  make</span> <span m='3512030'>from that</span> <span m='3512430'>state.</span> <span
  m='3514644'>Does that</span> <span m='3515130'>make</span> <span m='3515616'>sense
  to</span> <span m='3516102'>everyone?</span> </p><p><span m='3520490'>So</span>
  <span m='3520760'>there's</span> <span m='3521180'>two ways</span> <span m='3521600'>we</span>
  <span m='3521840'>can</span> <span m='3522250'>transform</span> <span m='3522620'>PDDL2</span>
  <span m='3523610'>to</span> <span m='3523900'>encapsulate</span> <span m='3524815'>what</span>
  <span m='3525070'>a</span> <span m='3525280'>Buchi Automata</span> <span m='3526030'>encapsulates.</span>
  <span m='3527020'>The</span> <span m='3527270'>first</span> <span m='3527600'>thing</span>
  <span m='3527850'>is</span> <span m='3527980'>you can</span> <span m='3528410'>create</span>
  <span m='3528650'>new</span> <span m='3529025'>actions</span> <span m='3529400'>that</span>
  <span m='3529640'>can</span> <span m='3529740'>encapsulate</span> <span m='3530600'>the</span>
  <span m='3530720'>allowable</span> <span m='3531170'>transitions</span> <span m='3531640'>of
  each</span> <span m='3532102'>state.</span> <span m='3533490'>So</span> <span m='3533660'>basically,</span>
  <span m='3534520'>for</span> <span m='3534700'>every</span> <span m='3535160'>action
  you</span> <span m='3535530'>have in</span> <span m='3535910'>your</span> <span
  m='3535940'>traditional</span> <span m='3536360'>PDDL,</span> <span m='3536880'>you</span>
  <span m='3537320'>have</span> <span m='3537460'>create</span> <span m='3539950'>a</span>
  <span m='3540220'>repetitive</span> <span m='3540380'>action</span> <span m='3540760'>for</span>
  <span m='3541140'>each</span> <span m='3541270'>one of</span> <span m='3541683'>these</span>
  <span m='3542096'>states so</span> <span m='3542510'>you</span> <span m='3542600'>know</span>
  <span m='3542930'>exactly</span> <span m='3543140'>which</span> <span m='3543480'>transitions</span>
  <span m='3543820'>you can</span> <span m='3544160'>take out</span> <span m='3544310'>of</span>
  <span m='3544732'>that</span> <span m='3545154'>state.</span> </p><p><span m='3546420'>This
  can</span> <span m='3546680'>get</span> <span m='3547060'>long</span> <span m='3547420'>because</span>
  <span m='3547795'>you</span> <span m='3548170'>have</span> <span m='3548280'>to
  make</span> <span m='3548575'>a</span> <span m='3548870'>new</span> <span m='3549160'>action</span>
  <span m='3550070'>for</span> <span m='3550250'>every</span> <span m='3550550'>single</span>
  <span m='3550780'>one</span> <span m='3550940'>of</span> <span m='3551030'>these</span>
  <span m='3551210'>states</span> <span m='3551470'>for</span> <span m='3551700'>every</span>
  <span m='3552030'>action</span> <span m='3552462'>that you</span> <span m='3552894'>want
  to take.</span> <span m='3553760'>That</span> <span m='3553880'>is one</span> <span
  m='3554280'>way you</span> <span m='3554550'>can do it.</span> </p><p><span m='3555295'>Another</span>
  <span m='3555780'>way you can</span> <span m='3556230'>do</span> <span m='3556470'>it</span>
  <span m='3556880'>is</span> <span m='3557030'>introducing</span> <span m='3557670'>derived</span>
  <span m='3557990'>predicates.</span> <span m='3559250'>Derived</span> <span m='3559670'>predicates</span>
  <span m='3560005'>are</span> <span m='3560340'>predicates</span> <span m='3560560'>that</span>
  <span m='3560940'>don't</span> <span m='3561320'>depend</span> <span m='3561670'>the
  actions at</span> <span m='3561840'>all</span> <span m='3562050'>and</span> <span
  m='3562400'>just depend on some other</span> <span m='3562680'>formula</span> <span
  m='3563270'>in</span> <span m='3563440'>your</span> <span m='3563610'>plan.</span>
  <span m='3565380'>For</span> <span m='3565710'>example,</span> <span m='3566040'>we
  can have</span> <span m='3566290'>a</span> <span m='3566400'>derived</span> <span
  m='3566900'>predicate</span> <span m='3567100'>that</span> <span m='3567860'>explicitly</span>
  <span m='3568430'>tells</span> <span m='3568780'>you</span> <span m='3569150'>whether</span>
  <span m='3569390'>you're</span> <span m='3569630'>in</span> <span m='3569840'>s1</span>
  <span m='3570170'>or</span> <span m='3570290'>whether</span> <span m='3570740'>you're
  in</span> <span m='3571140'>s2.</span> </p><p><span m='3571540'>And</span> <span
  m='3571940'>you</span> <span m='3572150'>can use these</span> <span m='3572470'>predicates</span>
  <span m='3572790'>in</span> <span m='3573030'>your</span> <span m='3573190'>actions</span>
  <span m='3573590'>in</span> <span m='3573955'>PDDL2</span> <span m='3574320'>to</span>
  <span m='3574880'>make</span> <span m='3575120'>sure,</span> <span m='3575600'>even</span>
  <span m='3576060'>though</span> <span m='3576240'>which</span> <span m='3576790'>state,</span>
  <span m='3577090'>x1</span> <span m='3577525'>or</span> <span m='3577960'>x2,</span>
  <span m='3578120'>you're</span> <span m='3578544'>in</span> <span m='3578968'>in</span>
  <span m='3579392'>your</span> <span m='3579816'>Buchi Automata.</span> <span m='3580240'>And
  then, in your</span> <span m='3580550'>formulation</span> <span m='3581120'>of</span>
  <span m='3581240'>your</span> <span m='3581330'>plan,</span> <span m='3582080'>you</span>
  <span m='3582170'>set</span> <span m='3582380'>your</span> <span m='3583580'>final</span>
  <span m='3583910'>state</span> <span m='3584270'>to be</span> <span m='3584620'>one
  of the</span> <span m='3585000'>accepting</span> <span m='3585200'>states.</span>
  <span m='3586878'>I guess</span> <span m='3587296'>that</span> <span m='3587714'>answers
  one</span> <span m='3588132'>of the questions,</span> <span m='3588550'>though,</span>
  <span m='3588830'>how</span> <span m='3589280'>you</span> <span m='3589670'>go</span>
  <span m='3590020'>from</span> <span m='3590190'>being</span> <span m='3590600'>infinite</span>
  <span m='3591020'>to</span> <span m='3591410'>finite.</span> <span m='3591800'>The
  accepting</span> <span m='3592280'>state is</span> <span m='3592700'>usually</span>
  <span m='3593420'>what</span> <span m='3593570'>you</span> <span m='3594440'>place</span>
  <span m='3594690'>as</span> <span m='3594960'>your</span> <span m='3595160'>final</span>
  <span m='3595550'>state.</span> </p><p><span m='3595940'>AUDIENCE:</span> <span
  m='3596037'>Then</span> <span m='3596134'>in</span> <span m='3596231'>the</span>
  <span m='3596330'>derived</span> <span m='3596570'>predicates,</span> <span m='3597006'>you're</span>
  <span m='3597442'>purely</span> <span m='3597878'>in</span> <span m='3598314'>the</span>
  <span m='3598750'>pre-conditions?</span> <span m='3599520'>Or</span> <span m='3599855'>do
  they</span> <span m='3600190'>also</span> <span m='3600670'>appear in the effects.</span>
  </p><p><span m='3601020'>GUEST SPEAKER:</span> <span m='3601180'>They</span> <span
  m='3601340'>also</span> <span m='3601816'>appear in the</span> <span m='3602292'>effects</span>
  <span m='3602768'>because</span> <span m='3603244'>you</span> <span m='3603720'>need</span>
  <span m='3603920'>to</span> <span m='3604080'>know</span> <span m='3605010'>how</span>
  <span m='3605373'>to</span> <span m='3605736'>transition</span> <span m='3606100'>out
  of</span> <span m='3606530'>s1</span> <span m='3606710'>to</span> <span m='3607160'>s2.</span>
  <span m='3607610'>So</span> <span m='3607820'>you'd</span> <span m='3608230'>likely</span>
  <span m='3608460'>have</span> <span m='3608710'>a</span> <span m='3608990'>derived</span>
  <span m='3609372'>predicate</span> <span m='3609754'>for both</span> <span m='3610136'>s1</span>
  <span m='3610520'>and</span> <span m='3610820'>a</span> <span m='3611070'>derived</span>
  <span m='3611240'>predicate</span> <span m='3611635'>for</span> <span m='3612030'>s2.</span>
  <span m='3612690'>And</span> <span m='3613180'>that is</span> <span m='3613670'>also</span>
  <span m='3614350'>a</span> <span m='3614470'>lot</span> <span m='3614570'>of</span>
  <span m='3614630'>work</span> <span m='3614810'>to</span> <span m='3615040'>add</span>
  <span m='3615300'>to the</span> <span m='3615724'>PDDL2</span> <span m='3616148'>problem.</span>
  </p><p><span m='3616572'>But</span> <span m='3616996'>it's</span> <span m='3617420'>definitely</span>
  <span m='3617700'>shorter</span> <span m='3618020'>than the</span> <span m='3618260'>first</span>
  <span m='3618440'>way.</span> <span m='3618890'>And</span> <span m='3619340'>it
  definitely</span> <span m='3619790'>encapsulates</span> <span m='3619970'>everything,</span>
  <span m='3620350'>by</span> <span m='3620730'>the</span> <span m='3620910'>Buchi
  Automata</span> <span m='3621842'>[INAUDIBLE]</span> <span m='3622774'>Does anyone</span>
  <span m='3623240'>have any</span> <span m='3623706'>questions about that?</span>
  </p><p><span m='3626040'>AUDIENCE:</span> <span m='3626125'>So</span> <span m='3626420'>you're</span>
  <span m='3626650'>changing the</span> <span m='3627100'>action</span> <span m='3627550'>then?</span>
  </p><p><span m='3628000'>GUEST SPEAKER:</span> <span m='3628225'>Yeah.</span> <span
  m='3628450'>You're</span> <span m='3628755'>changing</span> <span m='3629460'>the</span>
  <span m='3629580'>action</span> <span m='3629990'>but</span> <span m='3630160'>you</span>
  <span m='3630220'>don't</span> <span m='3630570'>need</span> <span m='3630790'>make
  a</span> <span m='3630850'>new</span> <span m='3631140'>action</span> <span m='3632280'>for</span>
  <span m='3632430'>every</span> <span m='3632670'>state.</span> <span m='3633960'>In</span>
  <span m='3634440'>the</span> <span m='3634710'>first</span> <span m='3635010'>formulation,</span>
  <span m='3637630'>let's</span> <span m='3637790'>say</span> <span m='3638030'>I
  have</span> <span m='3638240'>some</span> <span m='3638430'>traditional</span> <span
  m='3638850'>action,</span> <span m='3639330'>like</span> <span m='3639800'>move</span>
  <span m='3640180'>blue</span> <span m='3640600'>block, or</span> <span m='3641020'>something.</span>
  <span m='3641340'>I have to create a move</span> <span m='3641760'>block</span>
  <span m='3642120'>action</span> <span m='3642720'>for</span> <span m='3642930'>each</span>
  <span m='3643140'>one</span> <span m='3643260'>of</span> <span m='3643350'>these</span>
  <span m='3644150'>states</span> <span m='3644450'>because</span> <span m='3644700'>I</span>
  <span m='3644790'>need</span> <span m='3644960'>to</span> <span m='3645090'>know</span>
  <span m='3645360'>exactly</span> <span m='3645810'>which</span> <span m='3646010'>transitions</span>
  <span m='3646450'>I can</span> <span m='3646730'>take</span> <span m='3646990'>out</span>
  <span m='3647406'>of that</span> <span m='3647822'>action.</span> </p><p><span m='3648240'>AUDIENCE:</span>
  <span m='3648273'>In</span> <span m='3648306'>the</span> <span m='3648340'>second</span>
  <span m='3648700'>example?</span> </p><p><span m='3649080'>GUEST SPEAKER:</span>
  <span m='3649175'>And</span> <span m='3649270'>in</span> <span m='3649365'>the</span>
  <span m='3649460'>second</span> <span m='3649840'>one</span> <span m='3650140'>I
  can</span> <span m='3650573'>just have</span> <span m='3651006'>one</span> <span
  m='3651440'>move</span> <span m='3651560'>block.</span> <span m='3652710'>But</span>
  <span m='3653210'>in my</span> <span m='3653710'>move</span> <span m='3654020'>block</span>
  <span m='3654285'>I'll have a</span> <span m='3654550'>derived</span> <span m='3654760'>predicate</span>
  <span m='3655050'>that</span> <span m='3655580'>tells</span> <span m='3655920'>me</span>
  <span m='3656190'>which</span> <span m='3656370'>state</span> <span m='3656640'>I'm</span>
  <span m='3656980'>in</span> <span m='3659100'>when</span> <span m='3659280'>I</span>
  <span m='3659690'>execute</span> <span m='3660130'>that</span> <span m='3660300'>action.</span>
  <span m='3665280'>The</span> <span m='3665370'>number</span> <span m='3665790'>of</span>
  <span m='3666160'>actions</span> <span m='3666440'>you have</span> <span m='3666660'>to</span>
  <span m='3667050'>write</span> <span m='3667210'>is</span> <span m='3667350'>less</span>
  <span m='3667740'>because</span> <span m='3668113'>you</span> <span m='3668860'>explicitly</span>
  <span m='3669060'>have</span> <span m='3669340'>predicates</span> <span m='3669620'>that
  are</span> <span m='3669770'>telling</span> <span m='3670090'>you</span> <span m='3670580'>which</span>
  <span m='3670770'>state</span> <span m='3671040'>that</span> <span m='3671539'>you're</span>
  <span m='3672038'>in.</span> </p><p><span m='3674533'>Now</span> <span m='3675032'>I'm
  going to</span> <span m='3675531'>hand it</span> <span m='3676030'>over</span> <span
  m='3676529'>to--</span> <span m='3677527'>if there are no more</span> <span m='3678026'>questions--</span>
  <span m='3678530'>hand it over to</span> <span m='3678800'>Mark.</span> <span m='3679254'>And
  he's going to</span> <span m='3679708'>talk</span> <span m='3680162'>about</span>
  <span m='3680616'>preferences.</span> </p><p><span m='3685172'>MARK:</span> <span
  m='3685397'>We're</span> <span m='3685623'>getting</span> <span m='3686074'>a</span>
  <span m='3686525'>little low</span> <span m='3686980'>on</span> <span m='3687300'>time.</span>
  <span m='3687750'>Now</span> <span m='3688070'>I'll</span> <span m='3688300'>transition</span>
  <span m='3688530'>to talking</span> <span m='3688805'>about--</span> <span m='3689280'>we</span>
  <span m='3689490'>talked</span> <span m='3689790'>about</span> <span m='3689970'>temporally</span>
  <span m='3690210'>extended</span> <span m='3690610'>goals.</span> <span m='3691370'>We
  said that</span> <span m='3691640'>goals</span> <span m='3692010'>are</span> <span
  m='3692240'>things</span> <span m='3692510'>that</span> <span m='3692660'>always</span>
  <span m='3693000'>have to</span> <span m='3693410'>be true.</span> </p><p><span
  m='3694230'>So now let's</span> <span m='3694640'>talk</span> <span m='3694940'>about</span>
  <span m='3695120'>preferences.</span> <span m='3695860'>Preferences</span> <span
  m='3696050'>are</span> <span m='3696390'>things</span> <span m='3696690'>that</span>
  <span m='3696820'>don't</span> <span m='3696970'>necessarily</span> <span m='3697250'>have
  to be</span> <span m='3697620'>true,</span> <span m='3698520'>but are</span> <span
  m='3698620'>things</span> <span m='3699090'>that</span> <span m='3699300'>you'd</span>
  <span m='3699540'>like</span> <span m='3699720'>to be true.</span> </p><p><span
  m='3701470'>In</span> <span m='3701740'>the</span> <span m='3702010'>classical</span>
  <span m='3702390'>planning</span> <span m='3702830'>problem,</span> <span m='3703050'>we</span>
  <span m='3703460'>can</span> <span m='3704090'>formulate it like</span> <span m='3704480'>that.</span>
  <span m='3704750'>We can</span> <span m='3705075'>set a</span> <span m='3705400'>state</span>
  <span m='3705650'>S,</span> <span m='3706100'>set a</span> <span m='3706420'>state</span>
  <span m='3706740'>s0,</span> <span m='3707560'>a</span> <span m='3708020'>set</span>
  <span m='3708230'>of</span> <span m='3708450'>operators,</span> <span m='3708860'>and</span>
  <span m='3709313'>a set</span> <span m='3709766'>of goal states.</span> <span m='3710220'>The</span>
  <span m='3710310'>problem</span> <span m='3710830'>is</span> <span m='3711600'>transition</span>
  <span m='3711855'>from</span> <span m='3712210'>the</span> <span m='3712280'>initial</span>
  <span m='3712560'>states</span> <span m='3712980'>and</span> <span m='3713190'>any</span>
  <span m='3713350'>state.</span> <span m='3713880'>But those</span> <span m='3714070'>are</span>
  <span m='3714140'>goal</span> <span m='3714390'>states</span> <span m='3714800'>using</span>
  <span m='3715210'>the operators</span> <span m='3715340'>[INAUDIBLE]</span> </p><p><span
  m='3717810'>Preference</span> <span m='3717870'>based</span> <span m='3718230'>planning</span>
  <span m='3718625'>problem</span> <span m='3719020'>introduces</span> <span m='3719560'>a</span>
  <span m='3719740'>traditional</span> <span m='3720480'>field R,</span> <span m='3721636'>which</span>
  <span m='3721972'>is a</span> <span m='3722310'>partial</span> <span m='3722580'>or</span>
  <span m='3722850'>total</span> <span m='3723420'>relation</span> <span m='3724160'>expressing</span>
  <span m='3724460'>preferences</span> <span m='3725840'>between</span> <span m='3726566'>plans.</span>
  <span m='3726942'>And this is a little</span> <span m='3727320'>preference</span>
  <span m='3728656'>symbol</span> <span m='3729114'>right</span> <span m='3729572'>there.</span>
  <span m='3730490'>That</span> <span m='3731070'>tells</span> <span m='3731340'>you,</span>
  <span m='3731580'>if there</span> <span m='3731845'>are</span> <span m='3732110'>multiple</span>
  <span m='3732310'>plans</span> <span m='3732690'>you need</span> <span m='3732930'>to</span>
  <span m='3733080'>accomplish</span> <span m='3733500'>your</span> <span m='3733620'>goal,</span>
  <span m='3734590'>which one</span> <span m='3734960'>do you</span> <span m='3735240'>want</span>
  <span m='3735510'>to</span> <span m='3735660'>use.</span> <span m='3737220'>And</span>
  <span m='3737340'>again,</span> <span m='3737860'>preferences</span> <span m='3738060'>are</span>
  <span m='3738200'>properties</span> <span m='3738590'>that</span> <span m='3738980'>are</span>
  <span m='3739370'>desired but</span> <span m='3739590'>not</span> <span m='3739840'>necessarily</span>
  <span m='3740050'>required.</span> </p><p><span m='3743740'>There</span> <span m='3744060'>are</span>
  <span m='3744525'>two</span> <span m='3744990'>[INAUDIBLE]</span> <span m='3745130'>different</span>
  <span m='3745350'>types</span> <span m='3745770'>of</span> <span m='3745910'>preference</span>
  <span m='3746320'>languages,</span> <span m='3747630'>quantitative</span> <span
  m='3747820'>and</span> <span m='3748286'>qualitative.</span> <span m='3748752'>As
  you</span> <span m='3749220'>would</span> <span m='3749320'>expect,</span> <span
  m='3749760'>in</span> <span m='3750240'>quantitative</span> <span m='3750560'>languages,</span>
  <span m='3751120'>we</span> <span m='3751260'>actually</span> <span m='3751560'>assign</span>
  <span m='3751860'>a</span> <span m='3752070'>numeric</span> <span m='3752730'>value</span>
  <span m='3753650'>to</span> <span m='3753910'>the</span> <span m='3754120'>different</span>
  <span m='3754260'>plans</span> <span m='3754575'>in</span> <span m='3754890'>order
  to</span> <span m='3755290'>compare</span> <span m='3755740'>them.</span> <span
  m='3756190'>So</span> <span m='3756640'>these plans</span> <span m='3757090'>are
  a</span> <span m='3757540'>weight of</span> <span m='3757970'>four,</span> <span
  m='3758230'>and a weight</span> <span m='3758280'>of</span> <span m='3758400'>two,</span>
  <span m='3758790'>and that tells</span> <span m='3759120'>you which</span> <span
  m='3759450'>one</span> <span m='3759550'>to</span> <span m='3759946'>prefer.</span>
  <span m='3760740'>Here</span> <span m='3760940'>are</span> <span m='3761300'>some</span>
  <span m='3761520'>languages that</span> <span m='3761950'>do</span> <span m='3762110'>that.</span>
  </p><p><span m='3762870'>For</span> <span m='3763170'>qualitative</span> <span m='3763410'>languages,</span>
  <span m='3764700'>they</span> <span m='3764890'>actually</span> <span m='3765150'>just</span>
  <span m='3765450'>have</span> <span m='3767440'>a</span> <span m='3767735'>plan</span>
  <span m='3768030'>with this</span> <span m='3768200'>property</span> <span m='3768420'>is
  preferred</span> <span m='3768720'>to</span> <span m='3769100'>this</span> <span
  m='3769490'>other</span> <span m='3769840'>plan</span> <span m='3770420'>with</span>
  <span m='3770550'>this</span> <span m='3770700'>property.</span> <span m='3771810'>But</span>
  <span m='3771930'>we</span> <span m='3772020'>don't</span> <span m='3772170'>actually</span>
  <span m='3772470'>know any</span> <span m='3773330'>information</span> <span m='3773600'>that</span>
  <span m='3773870'>knows</span> <span m='3774590'>how</span> <span m='3774950'>much</span>
  <span m='3775260'>we</span> <span m='3775520'>prefer one to</span> <span m='3775670'>the
  other,</span> <span m='3776097'>or something like that.</span> <span m='3776951'>An</span>
  <span m='3777380'>important</span> <span m='3777870'>element</span> <span m='3778050'>of</span>
  <span m='3778260'>this</span> <span m='3778680'>is</span> <span m='3778980'>when</span>
  <span m='3779326'>you</span> <span m='3779672'>have</span> <span m='3780020'>quantitative</span>
  <span m='3780285'>languages,</span> <span m='3780550'>they're</span> <span m='3781130'>totally</span>
  <span m='3781520'>comparable.</span> <span m='3782250'>Any</span> <span m='3782580'>two</span>
  <span m='3782790'>sets</span> <span m='3783120'>of</span> <span m='3783240'>plans</span>
  <span m='3783630'>you</span> <span m='3783720'>can</span> <span m='3783900'>determine</span>
  <span m='3784350'>which</span> <span m='3784530'>one</span> <span m='3784830'>is</span>
  <span m='3784940'>preferred.</span> </p><p><span m='3786160'>Whereas</span> <span
  m='3786400'>in</span> <span m='3786770'>qualitative</span> <span m='3787080'>languages,</span>
  <span m='3787430'>you could have</span> <span m='3787620'>situations</span> <span
  m='3788310'>where</span> <span m='3788550'>plan</span> <span m='3788820'>one</span>
  <span m='3789000'>is</span> <span m='3789120'>preferred</span> <span m='3789405'>to</span>
  <span m='3789690'>plan two,</span> <span m='3790355'>and</span> <span m='3790630'>plan
  one</span> <span m='3790770'>is</span> <span m='3790930'>also</span> <span m='3791280'>preferred</span>
  <span m='3791500'>to</span> <span m='3791780'>plan</span> <span m='3792060'>3,</span>
  <span m='3792720'>but</span> <span m='3792870'>that</span> <span m='3792930'>doesn't</span>
  <span m='3793170'>give</span> <span m='3793280'>you</span> <span m='3793390'>any</span>
  <span m='3793540'>information</span> <span m='3794040'>about whether</span> <span
  m='3794260'>plan</span> <span m='3794440'>two</span> <span m='3794740'>is</span>
  <span m='3795640'>preferred</span> <span m='3795990'>to plan</span> <span m='3796464'>three.</span>
  <span m='3796938'>So it's a little bit</span> <span m='3797412'>less</span> <span
  m='3797886'>expressive</span> <span m='3798360'>[INAUDIBLE].</span> </p><p><span
  m='3801210'>To</span> <span m='3801370'>go</span> <span m='3801560'>into</span>
  <span m='3802600'>how</span> <span m='3802800'>you</span> <span m='3803000'>actually</span>
  <span m='3803390'>express</span> <span m='3803950'>preferences</span> <span m='3804160'>in</span>
  <span m='3804660'>PDDL3,</span> <span m='3804990'>like</span> <span m='3805140'>we</span>
  <span m='3805240'>talked</span> <span m='3805490'>about</span> <span m='3805720'>temporally</span>
  <span m='3805910'>extended</span> <span m='3806320'>goals,</span> <span m='3806930'>there</span>
  <span m='3807210'>is a</span> <span m='3807490'>PDDL3</span> <span m='3807950'>syntax</span>
  <span m='3808180'>to</span> <span m='3808585'>do</span> <span m='3808990'>this.</span>
  <span m='3809800'>There's</span> <span m='3810050'>a</span> <span m='3811750'>preference</span>
  <span m='3812040'>label</span> <span m='3812330'>here that</span> <span m='3812605'>you
  can put on</span> <span m='3812880'>fluents</span> <span m='3813150'>to</span> <span
  m='3813680'>represent</span> <span m='3814850'>things</span> <span m='3815946'>you</span>
  <span m='3816360'>prefer.</span> <span m='3817110'>And</span> <span m='3817200'>then</span>
  <span m='3817340'>there's</span> <span m='3817490'>a</span> <span m='3817550'>function</span>
  <span m='3817940'>call</span> <span m='3818270'>is-violated</span> <span m='3818480'>that</span>
  <span m='3819200'>essentially</span> <span m='3819650'>returns</span> <span m='3820120'>the</span>
  <span m='3820250'>number of</span> <span m='3820550'>times</span> <span m='3820940'>that</span>
  <span m='3821350'>any fluent</span> <span m='3821760'>that has</span> <span m='3822170'>a</span>
  <span m='3822660'>preference</span> <span m='3823103'>label</span> <span m='3823990'>was</span>
  <span m='3824200'>not</span> <span m='3824380'>satisfied</span> <span m='3824850'>in
  your</span> <span m='3825220'>plan.</span> </p><p><span m='3825960'>For</span> <span
  m='3826040'>example,</span> <span m='3826620'>if</span> <span m='3826640'>you</span>
  <span m='3826710'>have</span> <span m='3826940'>a</span> <span m='3827320'>preference,</span>
  <span m='3827707'>"Traffic</span> <span m='3828094'>light</span> <span m='3828481'>is</span>
  <span m='3828870'>green until</span> <span m='3829300'>it turns red."</span> <span
  m='3829710'>Here's</span> <span m='3829990'>our</span> <span m='3830950'>PDDL3</span>
  <span m='3831200'>template.</span> <span m='3831620'>It extended</span> <span m='3832570'>this
  kid's</span> <span m='3832910'>preference,</span> <span m='3834378'>in</span> <span
  m='3834842'>which we</span> <span m='3835306'>label</span> <span m='3835770'>it
  with</span> <span m='3836234'>a</span> <span m='3836700'>preference label here.</span>
  <span m='3837030'>And this is just a name.</span> <span m='3838830'>And</span> <span
  m='3838990'>then</span> <span m='3839080'>or</span> <span m='3839770'>plan</span>
  <span m='3840940'>tries to</span> <span m='3841270'>minimize</span> <span m='3841810'>the</span>
  <span m='3841870'>number</span> <span m='3842140'>of</span> <span m='3842230'>times</span>
  <span m='3842710'>that</span> <span m='3843030'>this</span> <span m='3843665'>preference</span>
  <span m='3844160'>is</span> <span m='3844370'>violated.</span> <span m='3844990'>That's</span>
  <span m='3845200'>one</span> <span m='3845350'>way</span> <span m='3845500'>to</span>
  <span m='3845860'>express</span> <span m='3846145'>preferences</span> <span m='3847310'>directly</span>
  <span m='3847570'>in</span> <span m='3848015'>PDDL3.</span> </p><p><span m='3851530'>So</span>
  <span m='3851740'>now</span> <span m='3851970'>we talk</span> <span m='3852180'>about</span>
  <span m='3852560'>LDP.</span> <span m='3853950'>LDP</span> <span m='3854240'>is
  a</span> <span m='3854440'>different</span> <span m='3854810'>language</span> <span
  m='3855750'>that</span> <span m='3856140'>is</span> <span m='3856620'>quite</span>
  <span m='3856940'>expressive</span> <span m='3857460'>in</span> <span m='3857580'>terms</span>
  <span m='3857890'>of</span> <span m='3858040'>types of</span> <span m='3858510'>preferences</span>
  <span m='3858980'>you can</span> <span m='3859450'>represent.</span> <span m='3860390'>It
  is a</span> <span m='3860860'>quantitative</span> <span m='3861575'>language,</span>
  <span m='3861920'>which</span> <span m='3862210'>means we're</span> <span m='3862690'>going
  to</span> <span m='3863670'>have</span> <span m='3864085'>weights</span> <span m='3864500'>for</span>
  <span m='3864660'>each of our</span> <span m='3865160'>plans</span> <span m='3865660'>to</span>
  <span m='3866160'>express</span> <span m='3866260'>our</span> <span m='3866590'>preferences.</span>
  </p><p><span m='3867160'>We can</span> <span m='3867640'>actually</span> <span m='3867895'>express</span>
  <span m='3868150'>the</span> <span m='3868360'>strength</span> <span m='3868635'>of
  the</span> <span m='3868910'>preference.</span> <span m='3869290'>So</span> <span
  m='3869640'>Goal A</span> <span m='3869940'>is preferred</span> <span m='3870240'>twice</span>
  <span m='3870550'>or</span> <span m='3870780'>three</span> <span m='3871020'>times</span>
  <span m='3871330'>as</span> <span m='3871420'>much</span> <span m='3872140'>as</span>
  <span m='3872380'>Goal</span> <span m='3872832'>B.</span> <span m='3873736'>It's</span>
  <span m='3874190'>an</span> <span m='3874410'>extension of</span> <span m='3874910'>an
  older</span> <span m='3875230'>language</span> <span m='3875550'>named</span> <span
  m='3875870'>PP.</span> <span m='3876456'>Here</span> <span m='3876802'>is the</span>
  <span m='3877150'>paper</span> <span m='3877460'>if you</span> <span m='3877690'>want
  to</span> <span m='3878171'>actually</span> <span m='3878652'>check out</span> <span
  m='3879133'>these details.</span> </p><p><span m='3881060'>The</span> <span m='3881410'>formulas</span>
  <span m='3881830'>are</span> <span m='3881980'>constructed</span> <span m='3882310'>hierarchically.</span>
  <span m='3883180'>I'll</span> <span m='3883470'>go through quickly</span> <span
  m='3883910'>how</span> <span m='3884110'>we</span> <span m='3884260'>actually</span>
  <span m='3884620'>construct</span> <span m='3885920'>these</span> <span m='3886315'>preference</span>
  <span m='3886710'>formulas.</span> <span m='3887670'>The</span> <span m='3887730'>lowest</span>
  <span m='3888090'>level is</span> <span m='3888510'>called</span> <span m='3888850'>a</span>
  <span m='3888910'>Basic</span> <span m='3889240'>Design</span> <span m='3889630'>Formula,</span>
  <span m='3890080'>or</span> <span m='3890463'>BDF.</span> <span m='3891230'>That</span>
  <span m='3891460'>just</span> <span m='3891700'>expresses</span> <span m='3892190'>our</span>
  <span m='3892490'>temporally</span> <span m='3892790'>extended</span> <span m='3893130'>proposition.</span>
  <span m='3893810'>So</span> <span m='3893940'>this</span> <span m='3894060'>is</span>
  <span m='3894190'>just</span> <span m='3895060'>a</span> <span m='3895120'>straight
  up</span> <span m='3895390'>LTL,</span> <span m='3895645'>basically,</span> <span
  m='3895900'>that</span> <span m='3896230'>we</span> <span m='3896490'>saw</span>
  <span m='3896750'>in the first section</span> <span m='3897010'>of the</span> <span
  m='3897270'>presentation.</span> <span m='3898640'>I'm going to</span> <span m='3898910'>use</span>
  <span m='3899110'>that</span> <span m='3899610'>I'm cooking dinner</span> <span
  m='3900070'>example</span> <span m='3900550'>for</span> <span m='3901030'>these</span>
  <span m='3901510'>slides.</span> </p><p><span m='3902170'>In</span> <span m='3902470'>this</span>
  <span m='3902820'>case,</span> <span m='3903100'>we</span> <span m='3903250'>always</span>
  <span m='3903545'>use the</span> <span m='3903840'>future</span> <span m='3904120'>operators.</span>
  <span m='3904610'>At</span> <span m='3905023'>some point,</span> <span m='3905436'>I
  might</span> <span m='3905850'>want</span> <span m='3905970'>to</span> <span m='3906050'>cook</span>
  <span m='3906310'>this</span> <span m='3906530'>program</span> <span m='3906730'>plan.</span>
  <span m='3907040'>Maybe</span> <span m='3907280'>I want</span> <span m='3907480'>to</span>
  <span m='3907600'>order</span> <span m='3907780'>takeout</span> <span m='3908210'>to</span>
  <span m='3908600'>eat</span> <span m='3908990'>dinner.</span> </p><p><span m='3910160'>And</span>
  <span m='3910240'>then</span> <span m='3910320'>I</span> <span m='3910480'>have</span>
  <span m='3910750'>some</span> <span m='3911195'>eating</span> <span m='3911640'>spaghetti</span>
  <span m='3911740'>or</span> <span m='3911890'>eating</span> <span m='3912330'>pizza.</span>
  <span m='3912770'>Those</span> <span m='3912816'>are</span> <span m='3912862'>two</span>
  <span m='3912910'>different</span> <span m='3913210'>things,</span> <span m='3913650'>two</span>
  <span m='3913780'>different</span> <span m='3914030'>options</span> <span m='3914470'>that
  I could</span> <span m='3914680'>have in</span> <span m='3915086'>my plan.</span>
  </p><p><span m='3915492'>I don't have to have</span> <span m='3915900'>either of
  those.</span> <span m='3917481'>Those are just</span> <span m='3917938'>options</span>
  <span m='3918395'>that I could</span> <span m='3918852'>have.</span> <span m='3919766'>That's
  the</span> <span m='3920230'>lowest</span> <span m='3920560'>level.</span> </p><p><span
  m='3921070'>The</span> <span m='3921260'>next</span> <span m='3921510'>level</span>
  <span m='3921850'>is called</span> <span m='3922150'>Atomic</span> <span m='3922400'>Preference</span>
  <span m='3922700'>Formulas,</span> <span m='3923010'>or</span> <span m='3923270'>APFs.</span>
  <span m='3924590'>There</span> <span m='3924830'>are</span> <span m='3925430'>where</span>
  <span m='3925600'>we</span> <span m='3925750'>express</span> <span m='3926070'>our</span>
  <span m='3926220'>preferences</span> <span m='3926740'>between</span> <span m='3927100'>the</span>
  <span m='3927330'>BDFs</span> <span m='3927670'>that</span> <span m='3927790'>we</span>
  <span m='3928160'>formed</span> <span m='3928310'>in the</span> <span m='3928560'>previous</span>
  <span m='3928750'>slide.</span> <span m='3929920'>So</span> <span m='3930100'>in
  this</span> <span m='3930250'>example</span> <span m='3930535'>I'm</span> <span
  m='3930820'>using</span> <span m='3931060'>weight,</span> <span m='3931870'>specifically</span>
  <span m='3932340'>to</span> <span m='3932490'>represent</span> <span m='3932880'>preference,</span>
  <span m='3933270'>with</span> <span m='3933570'>lower</span> <span m='3933790'>weight</span>
  <span m='3933990'>being</span> <span m='3934360'>preferred.</span> </p><p><span
  m='3935870'>Here</span> <span m='3936240'>we're</span> <span m='3936620'>saying,
  we</span> <span m='3936840'>prefer</span> <span m='3937150'>to</span> <span m='3937260'>cook</span>
  <span m='3937540'>over</span> <span m='3937820'>ordering</span> <span m='3938080'>takeout.</span>
  <span m='3939860'>This</span> <span m='3940305'>is</span> <span m='3940379'>you</span>
  <span m='3940453'>where you</span> <span m='3940527'>have</span> <span m='3940601'>to</span>
  <span m='3940675'>cook,</span> <span m='3940750'>this</span> <span m='3941120'>is</span>
  <span m='3941550'>where</span> <span m='3941840'>you have to order</span> <span
  m='3942294'>takeout.</span> <span m='3942748'>And</span> <span m='3943202'>we</span>
  <span m='3943656'>apply</span> <span m='3944110'>weights</span> <span m='3944400'>to
  those</span> <span m='3944710'>two</span> <span m='3945020'>expressions.</span>
  </p><p><span m='3946030'>The first</span> <span m='3946370'>one's</span> <span m='3946630'>preferred,
  and</span> <span m='3946780'>how</span> <span m='3946960'>much</span> <span m='3947120'>it
  is</span> <span m='3947420'>preferred</span> <span m='3947840'>over</span> <span
  m='3948298'>this plan.</span> <span m='3949214'>And</span> <span m='3949672'>here</span>
  <span m='3950130'>is</span> <span m='3950588'>you prefer</span> <span m='3951046'>to
  eat spaghetti</span> <span m='3951510'>over</span> <span m='3951990'>eating</span>
  <span m='3952441'>pizza.</span> <span m='3953794'>So that's</span> <span m='3954245'>the
  second</span> <span m='3954696'>level.</span> </p><p><span m='3955150'>Third</span>
  <span m='3955810'>levels</span> <span m='3956360'>called</span> <span m='3956650'>General</span>
  <span m='3956980'>Purpose</span> <span m='3957320'>Formulas,</span> <span m='3957710'>or</span>
  <span m='3957870'>GPS.</span> <span m='3959060'>These</span> <span m='3959350'>are</span>
  <span m='3959440'>where</span> <span m='3959680'>we</span> <span m='3959920'>can</span>
  <span m='3960220'>do</span> <span m='3960550'>conjunctions or</span> <span m='3960760'>disjunctions,</span>
  <span m='3961420'>or</span> <span m='3961560'>qualification</span> <span m='3962650'>of</span>
  <span m='3962800'>our</span> <span m='3962920'>previous</span> <span m='3963340'>formulas.</span>
  <span m='3964200'>So</span> <span m='3964330'>for</span> <span m='3964510'>example,</span>
  <span m='3965560'>if</span> <span m='3965710'>we</span> <span m='3965800'>want</span>
  <span m='3966040'>to</span> <span m='3966350'>say--</span> <span m='3967110'>because</span>
  <span m='3967170'>in</span> <span m='3967410'>the previous</span> <span m='3967610'>slides</span>
  <span m='3967950'>we had</span> <span m='3968290'>two</span> <span m='3968540'>APFs.</span>
  <span m='3969093'>We</span> <span m='3969446'>had</span> <span m='3969800'>prefer</span>
  <span m='3970000'>to cook</span> <span m='3970590'>and</span> <span m='3970860'>prefer</span>
  <span m='3971170'>to</span> <span m='3971440'>eat spaghetti.</span> </p><p><span
  m='3973350'>And</span> <span m='3973720'>here</span> <span m='3973820'>we can</span>
  <span m='3974000'>express</span> <span m='3974320'>that</span> <span m='3974470'>we</span>
  <span m='3974560'>really</span> <span m='3974800'>don't</span> <span m='3975010'>care</span>
  <span m='3975310'>which</span> <span m='3975520'>one</span> <span m='3975670'>of</span>
  <span m='3975730'>these</span> <span m='3976220'>we</span> <span m='3977220'>want</span>
  <span m='3977380'>to</span> <span m='3977830'>satisfy.</span> <span m='3979110'>You</span>
  <span m='3979200'>can</span> <span m='3979320'>think of</span> <span m='3979540'>this</span>
  <span m='3979740'>as</span> <span m='3979980'>we</span> <span m='3980290'>actually</span>
  <span m='3980540'>tried to</span> <span m='3980810'>satisfy</span> <span m='3981290'>APF</span>
  <span m='3981570'>at</span> <span m='3981850'>the</span> <span m='3981940'>lowest</span>
  <span m='3982330'>weight.</span> <span m='3983010'>So</span> <span m='3983160'>if</span>
  <span m='3983220'>we</span> <span m='3983350'>have</span> <span m='3983630'>this</span>
  <span m='3983910'>"or"</span> <span m='3984240'>operating</span> <span m='3984550'>here,</span>
  <span m='3985130'>that</span> <span m='3985310'>means</span> <span m='3985550'>that</span>
  <span m='3985810'>our</span> <span m='3985990'>planner</span> <span m='3986255'>is</span>
  <span m='3986520'>going to</span> <span m='3986700'>try</span> <span m='3987150'>and</span>
  <span m='3987290'>satisfy the</span> <span m='3987520'>lowest</span> <span m='3987700'>weight</span>
  <span m='3988270'>among</span> <span m='3988570'>all these</span> <span m='3988890'>different</span>
  <span m='3989020'>options</span> <span m='3989230'>here,</span> <span m='3989515'>which</span>
  <span m='3989800'>means</span> <span m='3989950'>that</span> <span m='3990435'>he</span>
  <span m='3990920'>doesn't</span> <span m='3990970'>prefer</span> <span m='3991150'>to</span>
  <span m='3991240'>cook.</span> <span m='3991570'>That's</span> <span m='3991750'>its</span>
  <span m='3991930'>first</span> <span m='3992200'>goal.</span> </p><p><span m='3993610'>You</span>
  <span m='3993670'>can</span> <span m='3993790'>also</span> <span m='3995020'>use</span>
  <span m='3995140'>a</span> <span m='3995505'>handoff</span> <span m='3995870'>rigor,
  for</span> <span m='3996120'>example.</span> <span m='3996510'>And that's</span>
  <span m='3996730'>going</span> <span m='3997060'>to</span> <span m='3997325'>minimize</span>
  <span m='3998010'>the</span> <span m='3998110'>maximum</span> <span m='3998365'>weight</span>
  <span m='3998620'>against</span> <span m='3999005'>both</span> <span m='3999390'>of
  those</span> <span m='3999775'>options.</span> <span m='4000160'>Basically,</span>
  <span m='4000460'>what's it going to</span> <span m='4000870'>try</span> <span m='4001050'>and</span>
  <span m='4001210'>do--</span> <span m='4002076'>oops--</span> <span m='4003375'>what
  it's going to try and</span> <span m='4003810'>do</span> <span m='4004230'>is</span>
  <span m='4004560'>minimize</span> <span m='4006180'>the</span> <span m='4006510'>highest</span>
  <span m='4006660'>weight</span> <span m='4006740'>among</span> <span m='4006890'>these</span>
  <span m='4007245'>two options.</span> <span m='4007600'>So</span> <span m='4007780'>it's</span>
  <span m='4008210'>going</span> <span m='4008330'>to</span> <span m='4008510'>try</span>
  <span m='4011670'>and</span> <span m='4011750'>cook,</span> <span m='4012110'>and
  then</span> <span m='4012390'>it's going to try and eat</span> <span m='4012570'>spaghetti</span>
  <span m='4013270'>versus</span> <span m='4013670'>doing</span> <span m='4013850'>these
  other</span> <span m='4014030'>options.</span> <span m='4018100'>So</span> <span
  m='4018410'>those</span> <span m='4018720'>are</span> <span m='4019150'>GPFs.</span>
  </p><p><span m='4020020'>I'm now</span> <span m='4020210'>moving</span> <span m='4020510'>on</span>
  <span m='4020720'>to</span> <span m='4021890'>Aggregated</span> <span m='4022200'>Preference</span>
  <span m='4022400'>Formulas,</span> <span m='4022530'>which are the</span> <span
  m='4022790'>highest</span> <span m='4023210'>level.</span> <span m='4024380'>So</span>
  <span m='4025340'>with</span> <span m='4025610'>APFs,</span> <span m='4026570'>these</span>
  <span m='4026840'>define the</span> <span m='4027230'>order</span> <span m='4027560'>in
  which</span> <span m='4027860'>our</span> <span m='4028160'>different</span> <span
  m='4028580'>preferences are</span> <span m='4028750'>relaxed.</span> <span m='4029190'>You</span>
  <span m='4029270'>can,</span> <span m='4029530'>of</span> <span m='4029550'>course,</span>
  <span m='4029750'>express</span> <span m='4030160'>a</span> <span m='4030210'>lot</span>
  <span m='4030430'>of</span> <span m='4030510'>different</span> <span m='4030710'>preferences</span>
  <span m='4030965'>for</span> <span m='4031220'>your</span> <span m='4031490'>planner,</span>
  <span m='4032080'>but</span> <span m='4032290'>not</span> <span m='4032450'>all</span>
  <span m='4032750'>of</span> <span m='4032850'>them</span> <span m='4033000'>may
  be</span> <span m='4033430'>achievable,</span> <span m='4034220'>especially</span>
  <span m='4034670'>if</span> <span m='4034730'>you're</span> <span m='4034850'>trying</span>
  <span m='4035120'>to</span> <span m='4035210'>achieve a</span> <span m='4035620'>large
  number</span> <span m='4035920'>of</span> <span m='4036210'>preferences</span> <span
  m='4036500'>at</span> <span m='4036560'>the</span> <span m='4036620'>same.</span>
  <span m='4037170'>You</span> <span m='4037200'>may</span> <span m='4037330'>not</span>
  <span m='4037460'>actually</span> <span m='4037760'>be able to</span> <span m='4038060'>achieve</span>
  <span m='4038930'>all</span> <span m='4039120'>of</span> <span m='4039350'>those.</span>
  </p><p><span m='4040250'>So</span> <span m='4040910'>how</span> <span m='4041000'>do</span>
  <span m='4041090'>we</span> <span m='4041260'>produce</span> <span m='4041720'>our</span>
  <span m='4041860'>set</span> <span m='4042595'>in the</span> <span m='4042980'>correct</span>
  <span m='4043330'>order,</span> <span m='4043670'>in</span> <span m='4043750'>the</span>
  <span m='4043820'>preferred</span> <span m='4044250'>order</span> <span m='4044550'>so</span>
  <span m='4044980'>that</span> <span m='4045100'>our</span> <span m='4045220'>plan</span>
  <span m='4045460'>we</span> <span m='4045700'>end up with</span> <span m='4045980'>isn't</span>
  <span m='4046300'>even the most</span> <span m='4046520'>preferred</span> <span
  m='4047000'>plan?</span> <span m='4048640'>That's</span> <span m='4048840'>what</span>
  <span m='4049210'>APFs</span> <span m='4049510'>like</span> <span m='4049770'>to</span>
  <span m='4049920'>do.</span> <span m='4051050'>You</span> <span m='4051200'>can</span>
  <span m='4051380'>express,</span> <span m='4051950'>using</span> <span m='4052425'>this</span>
  <span m='4053440'>preference</span> <span m='4053800'>operator.</span> </p><p><span
  m='4056865'>First,</span> <span m='4057300'>I want to try</span> <span m='4057735'>and
  satisfy</span> <span m='4058170'>both of</span> <span m='4058430'>these</span> <span
  m='4058660'>in the</span> <span m='4059132'>previous slide.</span> <span m='4060550'>Then
  if I</span> <span m='4060780'>can't,</span> <span m='4061100'>I</span> <span m='4061490'>want
  to</span> <span m='4061520'>relax</span> <span m='4061810'>it</span> <span m='4062150'>so</span>
  <span m='4062300'>I</span> <span m='4062500'>only</span> <span m='4062740'>satisfy</span>
  <span m='4062810'>G2.</span> <span m='4063620'>And</span> <span m='4064080'>then
  if I</span> <span m='4064370'>can't</span> <span m='4064480'>do</span> <span m='4064550'>that,</span>
  <span m='4064850'>then</span> <span m='4065120'>I</span> <span m='4065250'>want
  to</span> <span m='4065505'>relax it</span> <span m='4065760'>so</span> <span m='4065960'>I
  only</span> <span m='4066080'>try and</span> <span m='4066425'>satisfy</span> <span
  m='4066800'>G1.</span> <span m='4067450'>So</span> <span m='4067570'>that</span>
  <span m='4067810'>gives</span> <span m='4067970'>us</span> <span m='4068030'>the</span>
  <span m='4068450'>order</span> <span m='4068690'>in</span> <span m='4068780'>which</span>
  <span m='4069620'>things</span> <span m='4069860'>are</span> <span m='4070000'>relaxed.</span>
  </p><p><span m='4070760'>It's</span> <span m='4071240'>important</span> <span m='4071630'>here</span>
  <span m='4071983'>that</span> <span m='4072690'>if</span> <span m='4072790'>you</span>
  <span m='4072830'>have</span> <span m='4073110'>these</span> <span m='4073220'>situations</span>
  <span m='4073490'>where</span> <span m='4073760'>you</span> <span m='4074200'>can't
  distinguish from</span> <span m='4074640'>one another,</span> <span m='4075080'>or</span>
  <span m='4075200'>you</span> <span m='4075260'>don't</span> <span m='4075440'>really</span>
  <span m='4075650'>care,</span> <span m='4076340'>we</span> <span m='4076480'>can</span>
  <span m='4076560'>establish</span> <span m='4076790'>some</span> <span m='4077120'>order.</span>
  <span m='4077390'>So</span> <span m='4077630'>at the</span> <span m='4077720'>very</span>
  <span m='4079510'>lowest</span> <span m='4079780'>type</span> <span m='4080050'>of</span>
  <span m='4080345'>level,</span> <span m='4080640'>we</span> <span m='4080850'>can</span>
  <span m='4081110'>sort</span> <span m='4081270'>them</span> <span m='4081500'>alphabetically,</span>
  <span m='4081650'>or</span> <span m='4081990'>something,</span> <span m='4082330'>just
  to</span> <span m='4082520'>provide</span> <span m='4082880'>some</span> <span m='4083150'>sort</span>
  <span m='4083550'>of</span> <span m='4083650'>order.</span> </p><p><span m='4088280'>This</span>
  <span m='4088460'>is</span> <span m='4088540'>just</span> <span m='4088750'>a</span>
  <span m='4088770'>review</span> <span m='4089230'>of</span> <span m='4089290'>what</span>
  <span m='4089410'>I've been</span> <span m='4089590'>talking</span> <span m='4089920'>about.</span>
  <span m='4091330'>BDFs</span> <span m='4091720'>are the</span> <span m='4092110'>lowest</span>
  <span m='4092380'>level,</span> <span m='4092800'>which</span> <span m='4093195'>express</span>
  <span m='4093590'>temporally</span> <span m='4094020'>extended</span> <span m='4094390'>propositions.</span>
  <span m='4095425'>We</span> <span m='4095780'>can apply</span> <span m='4096069'>preference</span>
  <span m='4096870'>to</span> <span m='4097080'>those</span> <span m='4097520'>using</span>
  <span m='4097960'>APFs.</span> <span m='4098840'>Then</span> <span m='4099080'>we</span>
  <span m='4099375'>can</span> <span m='4099670'>combine</span> <span m='4100210'>or</span>
  <span m='4100710'>join</span> <span m='4102079'>APFs</span> <span m='4102740'>using</span>
  <span m='4103819'>tell</span> <span m='4104170'>preference</span> <span m='4104410'>formulas.</span>
  <span m='4105470'>And</span> <span m='4105569'>finally,</span> <span m='4105729'>we</span>
  <span m='4105850'>can</span> <span m='4106189'>aggregate</span> <span m='4106399'>those</span>
  <span m='4106859'>preference</span> <span m='4107140'>formulas</span> <span m='4109210'>to</span>
  <span m='4109600'>determine</span> <span m='4110529'>the</span> <span m='4110819'>order</span>
  <span m='4111080'>in which</span> <span m='4111210'>you</span> <span m='4111399'>shouldn't</span>
  <span m='4111630'>relax</span> <span m='4111910'>the</span> <span m='4112090'>propositions</span>
  <span m='4113649'>to</span> <span m='4113960'>allow</span> <span m='4114220'>yourself</span>
  <span m='4114617'>to</span> <span m='4115014'>plan</span> <span m='4115411'>it right.</span>
  </p><p><span m='4115810'>So</span> <span m='4116060'>using</span> <span m='4116410'>this</span>
  <span m='4116979'>scheme</span> <span m='4117510'>in</span> <span m='4118010'>LPP,</span>
  <span m='4119050'>we're</span> <span m='4119260'>using</span> <span m='4119590'>both</span>
  <span m='4121083'>LTL</span> <span m='4121576'>syntax</span> <span m='4122069'>and</span>
  <span m='4122279'>rules</span> <span m='4122684'>that we</span> <span m='4123090'>talked
  about in the</span> <span m='4123360'>first</span> <span m='4123630'>section</span>
  <span m='4123979'>to</span> <span m='4124090'>express</span> <span m='4124540'>temporally</span>
  <span m='4124890'>extended</span> <span m='4125439'>preferences.</span> <span m='4126750'>The</span>
  <span m='4126850'>plans</span> <span m='4127279'>that's</span> <span m='4127479'>actually</span>
  <span m='4127870'>used</span> <span m='4128290'>to</span> <span m='4129510'>solve</span>
  <span m='4129950'>these types of</span> <span m='4130359'>problems</span> <span
  m='4130649'>is</span> <span m='4130819'>called</span> <span m='4131040'>P</span>
  <span m='4131380'>Plan.</span> <span m='4131830'>P</span> <span m='4132040'>Plans</span>
  <span m='4132319'>can actually</span> <span m='4132580'>handle</span> <span m='4132720'>templates,</span>
  <span m='4133120'>and the</span> <span m='4133240'>preferences,</span> <span m='4133495'>and</span>
  <span m='4133750'>a</span> <span m='4133950'>goal</span> <span m='4134245'>at the</span>
  <span m='4134540'>end,</span> <span m='4134630'>as</span> <span m='4134950'>well.</span>
  </p><p><span m='4135750'>And</span> <span m='4135850'>it</span> <span m='4135950'>does</span>
  <span m='4136090'>basically</span> <span m='4136899'>a</span> <span m='4137390'>best</span>
  <span m='4137729'>first</span> <span m='4137960'>search</span> <span m='4138399'>among
  all</span> <span m='4138620'>your</span> <span m='4138779'>different</span> <span
  m='4139229'>options.</span> <span m='4139656'>It's</span> <span m='4140083'>actually</span>
  <span m='4140510'>one</span> <span m='4140649'>of</span> <span m='4140710'>the</span>
  <span m='4140840'>planner</span> <span m='4141109'>that</span> <span m='4141220'>uses</span>
  <span m='4141420'>the</span> <span m='4141620'>left</span> <span m='4141720'>branch.</span>
  <span m='4141970'>But the one</span> <span m='4142430'>we</span> <span m='4142630'>showed</span>
  <span m='4143010'>uses</span> <span m='4143450'>progression</span> <span m='4143939'>to</span>
  <span m='4144330'>take</span> <span m='4144700'>LTL</span> <span m='4145310'>formulas</span>
  <span m='4145584'>at</span> <span m='4145859'>each</span> <span m='4146240'>point
  in the</span> <span m='4146680'>plan</span> <span m='4146979'>and</span> <span m='4147260'>determine</span>
  <span m='4147770'>whether</span> <span m='4148010'>you've</span> <span m='4148210'>satisfied</span>
  <span m='4148689'>those</span> <span m='4148890'>formulas</span> <span m='4149155'>or</span>
  <span m='4149420'>not.</span> <span m='4149649'>And if</span> <span m='4149989'>not,</span>
  <span m='4150329'>it will</span> <span m='4150670'>push them to the</span> <span
  m='4150760'>next</span> <span m='4151029'>state,</span> <span m='4152959'>so</span>
  <span m='4153229'>that</span> <span m='4153370'>in</span> <span m='4153640'>the</span>
  <span m='4153750'>next</span> <span m='4153979'>state</span> <span m='4154290'>you
  can</span> <span m='4154460'>evaluate</span> <span m='4154750'>whether you've</span>
  <span m='4155149'>satisfied</span> <span m='4155290'>those</span> <span m='4155680'>formulas.</span>
  <span m='4156460'>That's</span> <span m='4156640'>how</span> <span m='4157235'>it</span>
  <span m='4157691'>prunes</span> <span m='4158149'>the</span> <span m='4158460'>search</span>
  <span m='4158840'>space</span> <span m='4159119'>and</span> <span m='4159660'>tries</span>
  <span m='4160000'>to</span> <span m='4160270'>always</span> <span m='4160560'>find</span>
  <span m='4160729'>the</span> <span m='4160790'>most</span> <span m='4161069'>preferred</span>
  <span m='4161390'>plan</span> <span m='4161609'>to</span> <span m='4161700'>meet</span>
  <span m='4161819'>your</span> <span m='4161950'>goal.</span> </p><p><span m='4164290'>All</span>
  <span m='4164350'>right.</span> <span m='4165670'>So</span> <span m='4166720'>that's</span>
  <span m='4166870'>our</span> <span m='4166930'>presentation.</span> <span m='4168500'>Any</span>
  <span m='4168720'>questions</span> <span m='4169020'>from</span> <span m='4169505'>anyone?</span>
  </p><p><span m='4176295'>AUDIENCE:</span> <span m='4176537'>[INAUDIBLE]</span> <span
  m='4176780'>question.</span> <span m='4177265'>I have a</span> <span m='4177750'>question</span>
  <span m='4178235'>about</span> <span m='4178720'>[INAUDIBLE]</span> <span m='4179220'>presentation.</span>
  <span m='4179760'>You</span> <span m='4180220'>guys</span> <span m='4180680'>[INAUDIBLE]</span>
  <span m='4181600'>and</span> <span m='4182060'>then</span> <span m='4182410'>believes</span>
  <span m='4182879'>omega.</span> <span m='4183819'>Would</span> <span m='4184040'>you</span>
  <span m='4184149'>say that</span> <span m='4184434'>omega</span> <span m='4184720'>has</span>
  <span m='4185212'>to</span> <span m='4185704'>hold</span> <span m='4186688'>if</span>
  <span m='4187180'>p</span> <span m='4187672'>happens,</span> <span m='4188164'>and</span>
  <span m='4188656'>they</span> <span m='4189148'>have</span> <span m='4189640'>a</span>
  <span m='4190132'>conjunction</span> <span m='4190624'>in</span> <span m='4191116'>one</span>
  <span m='4191608'>state?</span> </p><p><span m='4192390'>ELLIE:</span> <span m='4192620'>Omega</span>
  <span m='4192851'>doesn't</span> <span m='4193312'>have to hold</span> <span m='4193773'>until
  we</span> <span m='4194234'>[INAUDIBLE].</span> <span m='4195620'>Omega</span> <span
  m='4195880'>just</span> <span m='4196130'>has</span> <span m='4196300'>to</span>
  <span m='4196782'>hold</span> <span m='4197264'>at</span> <span m='4197746'>the
  last</span> <span m='4198230'>state</span> <span m='4198470'>of</span> <span m='4198860'>p.</span>
  <span m='4199250'>Essentially</span> <span m='4199640'>what</span> <span m='4199860'>it's</span>
  <span m='4200090'>saying</span> <span m='4200355'>is</span> <span m='4200620'>omega</span>
  <span m='4201080'>releases</span> <span m='4201590'>p.</span> </p><p><span m='4202270'>So</span>
  <span m='4202430'>once</span> <span m='4202590'>omega</span> <span m='4202840'>happened,</span>
  <span m='4203850'>p has</span> <span m='4204200'>to</span> <span m='4204310'>happen</span>
  <span m='4204800'>at</span> <span m='4205010'>the</span> <span m='4205450'>state.</span>
  <span m='4205890'>And the</span> <span m='4206330'>omega</span> <span m='4206770'>has
  to</span> <span m='4207210'>release p.</span> <span m='4207940'>Now it</span> <span
  m='4208325'>happens,</span> <span m='4208710'>so</span> <span m='4209010'>p,</span>
  <span m='4209280'>you can</span> <span m='4209630'>don't</span> <span m='4209730'>you</span>
  <span m='4209980'>want.</span> <span m='4210280'>You can</span> <span m='4210610'>be</span>
  <span m='4211000'>true,</span> <span m='4211120'>you can be</span> <span m='4211540'>false.</span>
  </p><p><span m='4212620'>AUDIENCE:</span> <span m='4212870'>Sorry.</span> <span
  m='4213120'>So</span> <span m='4213463'>p</span> <span m='4213806'>has</span> <span
  m='4214150'>to</span> <span m='4214530'>hold</span> <span m='4215356'>until</span>
  <span m='4215770'>omega</span> <span m='4216254'>happens.</span> </p><p><span m='4216738'>ELLIE:</span>
  <span m='4216980'>Yep.</span> <span m='4217222'>And then</span> <span m='4217706'>omega--</span>
  </p><p><span m='4218190'>[INTERPOSING VOICES]</span> </p><p><span m='4219160'>AUDIENCE:</span>
  <span m='4219190'>So</span> <span m='4219220'>the</span> <span m='4219250'>definition</span>
  <span m='4219820'>is</span> <span m='4219940'>just</span> <span m='4220366'>switched</span>
  <span m='4220792'>to</span> <span m='4221218'>p</span> <span m='4222070'>[INAUDIBLE].</span>
  </p><p><span m='4222847'>ELLIE:</span> <span m='4223045'>This</span> <span m='4223244'>is</span>
  <span m='4223641'>an</span> <span m='4224040'>occasion.</span> <span m='4224180'>Occasionally,</span>
  <span m='4224475'>you</span> <span m='4224770'>have</span> <span m='4224950'>pR
  omega.</span> <span m='4229384'>But</span> <span m='4229862'>like</span> <span m='4230340'>intuitively--</span>
  </p><p><span m='4231296'>AUDIENCE:</span> <span m='4231417'>It's</span> <span m='4231538'>just</span>
  <span m='4231659'>the</span> <span m='4231780'>definition--</span> <span m='4232060'>oh--</span>
  </p><p><span m='4232522'>[INTERPOSING VOICES]</span> </p><p><span m='4234120'>AUDIENCE:</span>
  <span m='4234342'>That's</span> <span m='4234565'>all I was</span> <span m='4235010'>wondering</span>
  <span m='4235455'>because then I</span> <span m='4235900'>saw that and it was</span>
  <span m='4236345'>confusing.</span> <span m='4236790'>So that's all.</span> <span
  m='4237457'>OK,</span> <span m='4237680'>sorry.</span> </p><p><span m='4237970'>ELLIE:</span>
  <span m='4238165'>That's</span> <span m='4238360'>fine.</span> </p><p><span m='4244830'>MARK:</span>
  <span m='4244920'>Any</span> <span m='4245010'>other</span> <span m='4245451'>questions?</span>
  </p><p><span m='4248540'>AUDIENCE:</span> <span m='4248705'>Since</span> <span m='4248870'>there</span>
  <span m='4248960'>are</span> <span m='4249920'>multiple</span> <span m='4250250'>ways</span>
  <span m='4250580'>to</span> <span m='4250730'>express</span> <span m='4251290'>the</span>
  <span m='4251520'>same</span> <span m='4251975'>formula</span> <span m='4253340'>using</span>
  <span m='4255420'>the</span> <span m='4255540'>grammar,</span> <span m='4256660'>is</span>
  <span m='4256830'>there</span> <span m='4257125'>any</span> <span m='4257420'>notion</span>
  <span m='4257840'>of</span> <span m='4258050'>canonical</span> <span m='4258511'>forms,</span>
  <span m='4259433'>or</span> <span m='4260816'>a</span> <span m='4261277'>least</span>
  <span m='4261738'>complicated</span> <span m='4262200'>form,</span> <span m='4262330'>or
  something</span> <span m='4262762'>like that?</span> </p><p><span m='4263626'>MARK:</span>
  <span m='4263842'>Yeah,</span> <span m='4264058'>there</span> <span m='4264490'>is.</span>
  <span m='4264810'>Typically</span> <span m='4266470'>they</span> <span m='4267090'>actually--</span>
  <span m='4268754'>let</span> <span m='4269182'>me</span> <span m='4269610'>find</span>
  <span m='4269770'>the</span> <span m='4270110'>slide.</span> <span m='4270560'>So</span>
  <span m='4270820'>to</span> <span m='4271270'>simplify</span> <span m='4271720'>the</span>
  <span m='4272170'>algorithms</span> <span m='4273520'>they</span> <span m='4273900'>typically</span>
  <span m='4274280'>apply</span> <span m='4274690'>the kind of</span> <span m='4275100'>reductions</span>
  <span m='4275400'>that</span> <span m='4275700'>we</span> <span m='4275840'>showed</span>
  <span m='4276080'>in the</span> <span m='4276455'>slide</span> <span m='4276830'>to</span>
  <span m='4277130'>reduce the</span> <span m='4277350'>release</span> <span m='4277780'>and
  the</span> <span m='4278050'>globally</span> <span m='4278395'>and</span> <span
  m='4278980'>the</span> <span m='4279080'>future</span> <span m='4279560'>down</span>
  <span m='4279740'>to</span> <span m='4279980'>just</span> <span m='4280170'>the</span>
  <span m='4280490'>[INAUDIBLE]</span> <span m='4280520'>of</span> <span m='4280700'>an</span>
  <span m='4281130'>x.</span> <span m='4281560'>Otherwise,</span> <span m='4281990'>your</span>
  <span m='4282110'>algorithms going to be</span> <span m='4282465'>able</span> <span
  m='4283565'>to</span> <span m='4284040'>handle</span> <span m='4284515'>fewer</span>
  <span m='4284990'>cases.</span> <span m='4285250'>And then</span> <span m='4285390'>they
  apply</span> <span m='4285860'>the usual rules,</span> <span m='4286330'>trying</span>
  <span m='4286490'>to push</span> <span m='4286750'>nots</span> <span m='4287030'>out</span>
  <span m='4287080'>to the</span> <span m='4287410'>left-hand</span> <span m='4287650'>side.</span>
  </p><p><span m='4300760'>All</span> <span m='4301060'>right.</span> <span m='4301960'>Thanks,</span>
  <span m='4302260'>everyone.</span> </p><p><span m='4302560'>[APPLAUSE]</span> </p>
type: course
uid: 0ac9fa7ff5c52442a6306ad9559fb84c

---
None