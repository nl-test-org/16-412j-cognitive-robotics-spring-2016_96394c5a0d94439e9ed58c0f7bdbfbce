---
about_this_resource_text: ''
course_id: 16-412j-cognitive-robotics-spring-2016
embedded_media:
- id: Video-YouTube-Stream
  media_location: _4u9W1xOuts
  parent_uid: 3f0fe2b01ecb407895fd5a906b8602cc
  title: Video-YouTube-Stream
  type: Video
  uid: 956be66b84b51d25dd6d42b2062f7587
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/_4u9W1xOuts/default.jpg
  parent_uid: 3f0fe2b01ecb407895fd5a906b8602cc
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 22ef864b56b9805bdf706511f9f2bd61
- id: 3Play-3PlayYouTubeid-MP4
  media_location: _4u9W1xOuts
  parent_uid: 3f0fe2b01ecb407895fd5a906b8602cc
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 17a0f9a80e52db3f7cfc2576a36d4d52
- id: 4u9W1xOuts.srt
  parent_uid: 3f0fe2b01ecb407895fd5a906b8602cc
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-412j-cognitive-robotics-spring-2016/videos-for-advanced-lectures/advanced-lecture-1/4u9W1xOuts.srt
  title: 3play caption file
  type: null
  uid: 5b18b503129d5f82bbe59d29e350ecef
- id: 4u9W1xOuts.pdf
  parent_uid: 3f0fe2b01ecb407895fd5a906b8602cc
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-412j-cognitive-robotics-spring-2016/videos-for-advanced-lectures/advanced-lecture-1/4u9W1xOuts.pdf
  title: 3play pdf file
  type: null
  uid: f91a6a37aad9eb041e4d420bb1f76cf9
- id: Caption-3Play YouTube id-SRT
  parent_uid: 3f0fe2b01ecb407895fd5a906b8602cc
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: e2a66a26700a2e4e6addb1e12f4c57b9
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 3f0fe2b01ecb407895fd5a906b8602cc
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 896c477cdbfaf8254752903ebbca9bfe
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT16.412S16/MIT16_412S16_Lec1_Incremental_Path_Planning_300k.mp4
  parent_uid: 3f0fe2b01ecb407895fd5a906b8602cc
  title: Video-Internet Archive-MP4
  type: Video
  uid: 4be850e0824011c6176359824806b354
inline_embed_id: 84026246advancedlecture172355883
layout: video
order_index: null
parent_uid: d55ba1f51999fdb2f0dba10fa56076dc
related_resources_text: ''
short_url: advanced-lecture-1
technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-412j-cognitive-robotics-spring-2016/videos-for-advanced-lectures/advanced-lecture-1
template_type: Tabbed
title: 'Advanced Lecture 1: Incremental Path Planning'
transcript: <p><span m="1580">The</span> <span m="1670">following</span> <span m="2120">content</span>
  <span m="2600">is</span> <span m="2720">provided</span> <span m="3170">under</span>
  <span m="3380">a</span> <span m="3470">Creative</span> <span m="3920">Commons</span>
  <span m="4310">License.</span> <span m="5340">Your</span> <span m="5420">support</span>
  <span m="5900">will</span> <span m="6050">help</span> <span m="6320">MIT</span>
  <span m="6800">OpenCourseWare</span> <span m="7550">continue</span> <span m="8029">to</span>
  <span m="8180">offer</span> <span m="8510">high</span> <span m="8720">quality</span>
  <span m="9200">educational</span> <span m="9860">resources</span> <span m="10430">for</span>
  <span m="10580">free.</span> <span m="11640">To</span> <span m="11740">make</span>
  <span m="11840">a</span> <span m="11900">donation</span> <span m="12650">or</span>
  <span m="12830">to</span> <span m="12950">view</span> <span m="13160">additional</span>
  <span m="13550">materials</span> <span m="14180">from</span> <span m="14360">hundreds</span>
  <span m="14690">of</span> <span m="14810">MIT</span> <span m="15170">courses,</span>
  <span m="16470">visit</span> <span m="16670">MIT</span> <span m="17180">OpenCourseWare</span>
  <span m="18110">at</span> <span m="18310">ocw.mit.edu.</span></p><p><span m="23020">JOE
  LEAVITT:</span> <span m="23460">Good afternoon.</span> <span m="23580">My name</span>
  <span m="23730">is</span> <span m="23880">Joe</span> <span m="24110">Leavitt.</span>
  <span m="24770">My group</span> <span m="24960">members</span> <span m="25270">are</span>
  <span m="25370">Ben</span> <span m="25850">Ayton,</span> <span m="26060">Jess</span>
  <span m="26420">Noss,</span> <span m="26950">Erlend</span> <span m="27190">Harbitz,</span>
  <span m="27390">Jake</span> <span m="27630">Barnwell,</span> <span m="27880">and</span>
  <span m="28380">Sam</span> <span m="28650">Pinto,</span> <span m="29600">and</span>
  <span m="29780">we're</span> <span m="29870">going</span> <span m="29990">to</span>
  <span m="30050">introduce</span> <span m="30410">you</span> <span m="30560">to</span>
  <span m="30680">the</span> <span m="30770">topic</span> <span m="31650">incremental</span>
  <span m="31950">path</span> <span m="32290">planning.</span> <span m="34850">Listed</span>
  <span m="35330">on</span> <span m="35480">screen</span> <span m="35810">are</span>
  <span m="36070">just</span> <span m="36340">some</span> <span m="36560">of</span>
  <span m="36620">the</span> <span m="36680">references</span> <span m="37160">we</span>
  <span m="37240">used</span> <span m="37530">in</span> <span m="37710">putting</span>
  <span m="37940">together</span> <span m="38360">this</span> <span m="38570">lecture.</span>
  <span m="39620">The</span> <span m="39680">top</span> <span m="39950">three</span>
  <span m="40470">are</span> <span m="40680">the</span> <span m="41270">main</span>
  <span m="41510">references</span> <span m="41740">we used in</span> <span m="42630">developing</span>
  <span m="43190">our</span> <span m="44050">material</span> <span m="44510">on</span>
  <span m="44740">the</span> <span m="45040">D* Lite</span> <span m="45260">algorithm,</span>
  <span m="46320">but</span> <span m="46730">also take</span> <span m="46930">note</span>
  <span m="47120">of</span> <span m="47450">the</span> <span m="47780">bottom</span>
  <span m="48170">reference,</span> <span m="48980">which</span> <span m="49550">is</span>
  <span m="50120">a</span> <span m="50300">paper</span> <span m="50630">done</span>
  <span m="51250">within</span> <span m="51515">Professor</span> <span m="51780">William's</span>
  <span m="51900">group</span> <span m="52400">here</span> <span m="52530">at</span>
  <span m="52630">MIT.</span> <span m="53180">It</span> <span m="53557">talks</span>
  <span m="53934">about</span> <span m="54311">all-pairs,</span> <span m="55130">shortest
  paths</span> <span m="56180">incremental</span> <span m="56600">search</span> <span
  m="56900">method.</span></p><p><span m="57860">So</span> <span m="58070">if you're</span>
  <span m="58400">interested</span> <span m="58750">in</span> <span m="58850">more</span>
  <span m="59180">incremental</span> <span m="59510">search</span> <span m="59880">methods</span>
  <span m="60060">than</span> <span m="60470">those</span> <span m="60680">we're</span>
  <span m="60740">going</span> <span m="60860">to</span> <span m="60920">talk</span>
  <span m="61100">about</span> <span m="61310">today,</span> <span m="61740">please</span>
  <span m="61910">get</span> <span m="62050">into</span> <span m="62230">this.</span>
  <span m="62550">Especially if you're</span> <span m="62980">going to</span> <span
  m="63410">go</span> <span m="63560">ahead</span> <span m="63740">and</span> <span
  m="63860">do</span> <span m="64440">our</span> <span m="64760">P set,</span> <span
  m="65540">these</span> <span m="65690">references</span> <span m="66230">will</span>
  <span m="66570">be</span> <span m="67040">very</span> <span m="67250">helpful</span>
  <span m="67540">to</span> <span m="67690">you.</span></p><p><span m="70570">So</span>
  <span m="71730">today,</span> <span m="72090">we're</span> <span m="72210">going</span>
  <span m="72480">to</span> <span m="72960">first</span> <span m="73210">Monday</span>
  <span m="73590">problem,</span> <span m="74010">then</span> <span m="74270">we're</span>
  <span m="74350">going</span> <span m="74490">to</span> <span m="74540">introduce</span>
  <span m="74950">the</span> <span m="75050">idea</span> <span m="75300">of</span>
  <span m="75420">incremental</span> <span m="75750">search.</span> <span m="76260">Then
  we're going to go</span> <span m="76920">into</span> <span m="77070">detail</span>
  <span m="77580">on</span> <span m="77820">the D*</span> <span m="78180">Lite</span>
  <span m="78480">algorithm,</span> <span m="79060">which</span> <span m="79110">is</span>
  <span m="79740">type</span> <span m="79860">of</span> <span m="80270">incremental</span>
  <span m="80680">path</span> <span m="80940">planning,</span> <span m="81285">an</span>
  <span m="81630">algorithm</span> <span m="81850">used</span> <span m="81930">for</span>
  <span m="82070">incremental</span> <span m="82335">path</span> <span m="82600">planning,</span>
  <span m="83790">run</span> <span m="84060">through</span> <span m="84240">an</span>
  <span m="84330">example</span> <span m="84660">of</span> <span m="84990">D* Lite,</span>
  <span m="85540">talk about</span> <span m="85815">when it</span> <span m="86540">is</span>
  <span m="86870">good</span> <span m="87110">to</span> <span m="87240">use</span>
  <span m="87600">incremental</span> <span m="87730">path</span> <span m="87930">planning</span>
  <span m="88600">when</span> <span m="88830">other</span> <span m="89850">path planners</span>
  <span m="90450">might</span> <span m="90660">be</span> <span m="91620">better,</span>
  <span m="92280">and</span> <span m="92400">then</span> <span m="92640">I'll go</span>
  <span m="92840">into</span> <span m="93030">some</span> <span m="93240">algorithm</span>
  <span m="93630">extensions</span> <span m="94110">and</span> <span m="94200">related</span>
  <span m="94430">topics,</span> <span m="94970">and</span> <span m="95130">some</span>
  <span m="95660">applications</span> <span m="96220">in</span> <span m="96320">mobile</span>
  <span m="96600">robotics.</span></p><p><span m="98250">So</span> <span m="98650">in
  order</span> <span m="98850">to</span> <span m="99250">motivate the</span> <span
  m="99460">problem,</span> <span m="100480">we're</span> <span m="100500">going</span>
  <span m="100650">to</span> <span m="100710">use</span> <span m="101280">a</span>
  <span m="101910">robot</span> <span m="102390">living</span> <span m="102650">in</span>
  <span m="102750">a</span> <span m="102810">grid</span> <span m="103110">world.</span>
  <span m="103900">It's at a</span> <span m="103980">start</span> <span m="104340">location</span>
  <span m="105260">trying</span> <span m="105510">to</span> <span m="105570">get</span>
  <span m="105750">to</span> <span m="105900">a</span> <span m="105960">goal</span>
  <span m="106200">location.</span> <span m="107640">It</span> <span m="107710">can</span>
  <span m="107880">move</span> <span m="108240">up,</span> <span m="108580">down,</span>
  <span m="108880">left,</span> <span m="109100">or</span> <span m="109200">right,</span>
  <span m="109320">or</span> <span m="109410">diagonally.</span> <span m="110520">And</span>
  <span m="111470">it</span> <span m="111870">can</span> <span m="112050">only</span>
  <span m="112350">see</span> <span m="112650">the eight cells</span> <span m="113550">around</span>
  <span m="113910">it,</span> <span m="114130">as it's</span> <span m="114340">moving</span>
  <span m="114600">through</span> <span m="114750">this</span> <span m="114930">grid</span>
  <span m="115350">world.</span> <span m="116010">And</span> <span m="116330">we're</span>
  <span m="116430">going</span> <span m="116550">to</span> <span m="116610">give</span>
  <span m="117030">some</span> <span m="117830">pretty</span> <span m="118110">fine</span>
  <span m="118420">map</span> <span m="118630">of</span> <span m="118710">the</span>
  <span m="118800">world.</span> <span m="119100">This</span> <span m="119250">is</span>
  <span m="119390">a</span> <span m="119430">map</span> <span m="119720">that</span>
  <span m="119790">has</span> <span m="120330">the</span> <span m="120450">world</span>
  <span m="120720">before</span> <span m="121050">it</span> <span m="121110">starts</span>
  <span m="121470">moving.</span></p><p><span m="122270">And it's</span> <span m="122480">possibly</span>
  <span m="123220">moving</span> <span m="123510">through</span> <span m="123900">some</span>
  <span m="124140">of</span> <span m="124200">these,</span> <span m="125520">new</span>
  <span m="125730">obstacles</span> <span m="126065">could appear, or</span> <span
  m="126810">obstacles</span> <span m="127290">could</span> <span m="127440">go</span>
  <span m="127620">away.</span> <span m="128650">And</span> <span m="128720">the</span>
  <span m="128820">idea</span> <span m="129120">is</span> <span m="129270">that</span>
  <span m="129479">it's</span> <span m="129720">going</span> <span m="130050">to</span>
  <span m="130860">make</span> <span m="131100">observations</span> <span m="131760">as
  it's</span> <span m="132000">moving</span> <span m="132260">to</span> <span m="132390">this</span>
  <span m="132570">world</span> <span m="132900">and</span> <span m="133120">update
  its</span> <span m="133450">plane to</span> <span m="133860">get</span> <span m="134070">to</span>
  <span m="134230">the goal</span> <span m="134630">based on what it</span> <span
  m="135180">sees</span> <span m="136470">as</span> <span m="136680">it's</span> <span
  m="136800">moving</span> <span m="137100">along.</span></p><p><span m="140750">So</span>
  <span m="142190">I must correct myself.</span> <span m="143870">The</span> <span
  m="143990">map</span> <span m="144350">that</span> <span m="144470">you're</span>
  <span m="144560">seeing</span> <span m="144780">now</span> <span m="145290">is the
  map</span> <span m="145530">that the</span> <span m="145670">robot</span> <span
  m="146120">has</span> <span m="146360">ahead</span> <span m="146510">of</span> <span
  m="146540">time.</span> <span m="146900">The</span> <span m="147350">previous</span>
  <span m="147750">map</span> <span m="147880">is</span> <span m="148100">what</span>
  <span m="148370">the</span> <span m="148460">environment</span> <span m="148880">actually</span>
  <span m="149180">looks</span> <span m="149390">like.</span> <span m="150510">So
  as it</span> <span m="150950">starts</span> <span m="151390">moving,</span> <span
  m="152120">it's</span> <span m="152270">going</span> <span m="152420">to</span>
  <span m="152480">make</span> <span m="152660">a</span> <span m="152690">plan</span>
  <span m="153320">to</span> <span m="153410">get</span> <span m="153620">from</span>
  <span m="153890">the</span> <span m="153980">start</span> <span m="154310">to the
  goal,</span> <span m="154750">and</span> <span m="154870">that's</span> <span m="155000">what</span>
  <span m="155090">we</span> <span m="155180">want</span> <span m="155420">it to</span>
  <span m="155510">do.</span> <span m="156470">And</span> <span m="156950">it's</span>
  <span m="157130">going</span> <span m="157250">to</span> <span m="157310">move</span>
  <span m="157550">to</span> <span m="157670">the</span> <span m="157740">next</span>
  <span m="157970">position</span> <span m="158550">and</span> <span m="158670">then</span>
  <span m="158750">realize</span> <span m="159140">that</span> <span m="159230">there's</span>
  <span m="159410">an</span> <span m="159500">obstacle</span> <span m="159980">in</span>
  <span m="160070">the</span> <span m="160130">path</span> <span m="160450">that it</span>
  <span m="160640">previously</span> <span m="161120">planned,</span> <span m="161770">and</span>
  <span m="161980">now it</span> <span m="162110">must</span> <span m="162350">replan</span>
  <span m="162980">in</span> <span m="163100">order</span> <span m="163370">to</span>
  <span m="164240">find</span> <span m="164660">a</span> <span m="164840">valid</span>
  <span m="165150">path</span> <span m="165500">to</span> <span m="165560">the</span>
  <span m="165650">goal.</span></p><p><span m="167250">And</span> <span m="167360">so</span>
  <span m="167530">now,</span> <span m="167820">it</span> <span m="168030">replans,</span>
  <span m="168480">and</span> <span m="168700">continues</span> <span m="169360">to</span>
  <span m="169490">move</span> <span m="169700">on</span> <span m="169790">the</span>
  <span m="169850">new</span> <span m="170000">plan,</span> <span m="170400">and</span>
  <span m="170840">now it</span> <span m="170950">finds</span> <span m="171330">another</span>
  <span m="171650">obstacle</span> <span m="172130">that it has to replan</span> <span
  m="172880">around,</span> <span m="173180">and</span> <span m="173660">it</span>
  <span m="173750">does</span> <span m="173930">the</span> <span m="174020">same</span>
  <span m="174260">thing.</span> <span m="174810">And</span> <span m="174920">then
  it</span> <span m="175080">continues</span> <span m="175530">to</span> <span m="175610">walk</span>
  <span m="175880">through</span> <span m="176990">until</span> <span m="177050">it</span>
  <span m="177455">gets</span> <span m="177860">to a</span> <span m="177980">point</span>
  <span m="178340">where</span> <span m="179270">we</span> <span m="179390">have</span>
  <span m="179660">a</span> <span m="179770">change in the</span> <span m="180170">environment.</span>
  <span m="181140">The change is</span> <span m="182060">represented</span> <span
  m="182540">by</span> <span m="182660">these</span> <span m="182900">two</span> <span
  m="183470">cells</span> <span m="183740">going black</span> <span m="184010">here,</span>
  <span m="185240">and</span> <span m="185330">now</span> <span m="185570">its</span>
  <span m="185720">original</span> <span m="185990">plane</span> <span m="186200">is</span>
  <span m="186320">no</span> <span m="186440">longer</span> <span m="186710">valid</span>
  <span m="187010">again.</span> <span m="187420">And</span> <span m="187540">what</span>
  <span m="187620">we</span> <span m="187760">want it</span> <span m="187970">to</span>
  <span m="188090">do</span> <span m="188240">is</span> <span m="188330">to</span>
  <span m="188420">replan</span> <span m="188675">to</span> <span m="188930">find</span>
  <span m="189350">a</span> <span m="189410">new</span> <span m="189590">valid</span>
  <span m="189980">optimal</span> <span m="190400">path</span> <span m="190720">to</span>
  <span m="190880">the goal.</span></p><p><span m="193580">This</span> <span m="193790">is</span>
  <span m="193850">just</span> <span m="194010">showing</span> <span m="194210">here</span>
  <span m="194420">what</span> <span m="194600">happened</span> <span m="194880">to</span>
  <span m="195050">our</span> <span m="195110">environment.</span> <span m="197190">And</span>
  <span m="197240">then</span> <span m="197945">the</span> <span m="198230">robot</span>
  <span m="198590">replans</span> <span m="200990">and</span> <span m="201260">continues</span>
  <span m="201740">to</span> <span m="201810">march</span> <span m="202070">towards</span>
  <span m="202340">the</span> <span m="202430">goal</span> <span m="202935">So</span>
  <span m="203260">this</span> <span m="203480">is</span> <span m="203660">the</span>
  <span m="203720">behavior</span> <span m="204110">we</span> <span m="204230">want</span>
  <span m="204470">from</span> <span m="204530">a</span> <span m="204650">mobile</span>
  <span m="204980">robot,</span> <span m="205310">whether</span> <span m="205640">it's</span>
  <span m="206345">a two-dimensional</span> <span m="206780">path-planning problem,</span>
  <span m="207250">or</span> <span m="207830">we're</span> <span m="207950">talking</span>
  <span m="208220">about</span> <span m="208370">multi-dimensional</span> <span m="210200">robot</span>
  <span m="210830">arms,</span> <span m="212160">planning,</span> <span m="213120">working</span>
  <span m="213320">with</span> <span m="213530">humans</span> <span m="214230">on</span>
  <span m="214760">a</span> <span m="214790">manufacturing</span> <span m="215510">environment,</span>
  <span m="216410">or</span> <span m="217490">an activity-planning</span> <span m="218150">process.</span>
  <span m="219440">The</span> <span m="219580">idea</span> <span m="219680">is that
  we want</span> <span m="220070">the</span> <span m="220160">robot</span> <span m="220540">to</span>
  <span m="220600">be able to</span> <span m="220840">account</span> <span m="221160">for</span>
  <span m="221360">new</span> <span m="221540">obstacles</span> <span m="222170">or</span>
  <span m="222290">changes</span> <span m="222890">in</span> <span m="223720">its</span>
  <span m="223900">representation</span> <span m="224580">of</span> <span m="224660">the</span>
  <span m="224750">environment</span> <span m="225280">and continue</span> <span m="225530">to</span>
  <span m="225820">plan</span> <span m="227050">on the</span> <span m="227210">fly</span>
  <span m="227450">quickly</span> <span m="227960">and</span> <span m="228050">optimally.</span></p><p><span
  m="230150">So</span> <span m="231200">there's</span> <span m="231600">methods</span>
  <span m="231790">that</span> <span m="231990">accomplish</span> <span m="232550">this.</span>
  <span m="233510">One</span> <span m="234260">method</span> <span m="235100">used</span>
  <span m="235410">to</span> <span m="235540">in path</span> <span m="235900">planning</span>
  <span m="236330">is</span> <span m="237190">rapidly</span> <span m="237950">exploring</span>
  <span m="238210">random</span> <span m="238590">trees,</span> <span m="239030">or</span>
  <span m="239470">RRTs.</span> <span m="240620">RRTs</span> <span m="241360">are</span>
  <span m="241880">basically going</span> <span m="242120">to</span> <span m="242300">plan,</span>
  <span m="243460">replan,</span> <span m="243930">on</span> <span m="244070">every</span>
  <span m="244250">time</span> <span m="244610">step</span> <span m="244760">based</span>
  <span m="245000">on</span> <span m="245150">changes</span> <span m="245540">in</span>
  <span m="245660">the</span> <span m="245750">environment.</span> <span m="246680">And</span>
  <span m="248060">one</span> <span m="248240">problem</span> <span m="248570">in
  my</span> <span m="248690">experience</span> <span m="249110">here,</span> <span
  m="249420">though,</span> <span m="249590">is</span> <span m="249690">that</span>
  <span m="249710">RRTs</span> <span m="250340">are</span> <span m="251080">suboptimal,</span>
  <span m="253265">even though</span> <span m="253700">fast.</span></p><p><span m="262198">See,</span>
  <span m="262680">here you see the</span> <span m="262770">robot</span> <span m="263710">has</span>
  <span m="264415">come up with a plan.</span> <span m="264830">It's</span> <span
  m="265090">seeing new</span> <span m="265350">obstacles,</span> <span m="265670">the</span>
  <span m="266140">table</span> <span m="266610">in front of it.</span> <span m="267080">The
  coffee cup.</span> <span m="267550">And its</span> <span m="268163">planning for
  those</span> <span m="268576">things,</span> <span m="268990">so the</span> <span
  m="269210">plan it</span> <span m="269656">came</span> <span m="270548">up with</span>
  <span m="271440">is</span> <span m="272370">clearly</span> <span m="272850">not</span>
  <span m="273070">optimal.</span></p><p><span m="278730">So</span> <span m="279600">we</span>
  <span m="279720">can</span> <span m="279990">perform</span> <span m="280350">some</span>
  <span m="280440">additional</span> <span m="280940">computation.</span> <span m="281400">We</span>
  <span m="281490">can</span> <span m="281640">use</span> <span m="282230">a method</span>
  <span m="282750">that</span> <span m="283200">builds</span> <span m="283560">upon
  the</span> <span m="284040">RRT,</span> <span m="284670">RRT*,</span> <span m="285360">that</span>
  <span m="285660">it</span> <span m="286200">finds</span> <span m="286500">an</span>
  <span m="286590">optimal</span> <span m="286950">path,</span> <span m="287310">but</span>
  <span m="287400">that</span> <span m="287760">requires</span> <span m="287880">a
  pretty</span> <span m="287920">significant</span> <span m="288570">amount</span>
  <span m="288750">of</span> <span m="288840">offline</span> <span m="289290">computation</span>
  <span m="289750">time,</span> <span m="290360">and</span> <span m="290580">then</span>
  <span m="290740">you</span> <span m="290820">can</span> <span m="290940">accomplish</span>
  <span m="291330">something</span> <span m="292130">that</span> <span m="292650">looks</span>
  <span m="292860">a</span> <span m="292890">little</span> <span m="293190">more</span>
  <span m="293400">normal.</span> <span m="294900">Again,</span> <span m="295280">we</span>
  <span m="295759">have</span> <span m="296238">to</span> <span m="296717">allow</span>
  <span m="297196">the</span> <span m="297675">robot</span> <span m="298154">to</span>
  <span m="298633">perform a lot of the</span> <span m="299112">computation off-line.</span></p><p><span
  m="304390">So</span> <span m="305440">how</span> <span m="305660">do</span> <span
  m="305710">we</span> <span m="306880">accomplish</span> <span m="307570">what</span>
  <span m="307750">we</span> <span m="308350">want</span> <span m="308550">to?</span>
  <span m="308820">We want to</span> <span m="309520">compute</span> <span m="310180">quickly.</span>
  <span m="310990">We</span> <span m="311050">want</span> <span m="311250">to</span>
  <span m="311420">compute</span> <span m="311600">optimally,</span> <span m="312410">and</span>
  <span m="312570">then</span> <span m="312700">have</span> <span m="312890">the</span>
  <span m="312940">robot</span> <span m="313270">continue</span> <span m="313630">to</span>
  <span m="313750">move</span> <span m="314080">as</span> <span m="314340">it's</span>
  <span m="314560">received</span> <span m="314850">new</span> <span m="315284">information</span>
  <span m="315718">coming to the environment.</span></p><p><span m="317890">Some</span>
  <span m="318040">problems</span> <span m="318320">we're</span> <span m="318440">facing,</span>
  <span m="319370">there's</span> <span m="319660">changing</span> <span m="319990">environmental</span>
  <span m="320470">conditions.</span> <span m="321600">There's sensor</span> <span
  m="322060">limitations.</span> <span m="322390">You</span> <span m="322720">might</span>
  <span m="322870">not</span> <span m="323020">be</span> <span m="323110">able</span>
  <span m="323230">to</span> <span m="323290">see</span> <span m="323500">everything</span>
  <span m="323765">in the</span> <span m="324030">environment</span> <span m="324370">around</span>
  <span m="324700">you,</span> <span m="325270">and</span> <span m="325360">then</span>
  <span m="325480">we</span> <span m="325570">have</span> <span m="325800">limited</span>
  <span m="325880">computation time.</span> <span m="329860">And</span> <span m="329960">the</span>
  <span m="330050">solution</span> <span m="330620">that</span> <span m="330770">we're</span>
  <span m="330950">going</span> <span m="331160">to</span> <span m="331220">explore</span>
  <span m="331670">here</span> <span m="332090">is</span> <span m="332450">to</span>
  <span m="332900">reuse</span> <span m="333320">that</span> <span m="333620">from</span>
  <span m="333750">the</span> <span m="333800">previous</span> <span m="334160">search,</span>
  <span m="335510">in</span> <span m="335630">order</span> <span m="335870">to</span>
  <span m="336020">speed</span> <span m="336290">up</span> <span m="336410">the</span>
  <span m="336500">search</span> <span m="336770">process,</span> <span m="337580">and</span>
  <span m="337780">continue</span> <span m="338290">to</span> <span m="338810">plan</span>
  <span m="339170">optimally.</span></p><p><span m="340516">And</span> <span m="340890">the
  method</span> <span m="341260">we're</span> <span m="341390">going</span> <span
  m="341510">to</span> <span m="341570">use</span> <span m="341780">to</span> <span
  m="341840">accomplish</span> <span m="342350">this</span> <span m="342710">is</span>
  <span m="343100">incremental</span> <span m="343550">search.</span> <span m="344760">So</span>
  <span m="344780">now,</span> <span m="344900">we're</span> <span m="344960">going</span>
  <span m="345080">to</span> <span m="345220">talk</span> <span m="345650">about</span>
  <span m="345860">what</span> <span m="346070">incremental</span> <span m="346490">search</span>
  <span m="346790">means.</span> <span m="349170">First</span> <span m="349430">to</span>
  <span m="349610">show</span> <span m="349910">you</span> <span m="350290">kind</span>
  <span m="350480">of</span> <span m="350750">how</span> <span m="350930">powerful</span>
  <span m="351420">incremental</span> <span m="351740">search</span> <span m="352220">can
  be,</span> <span m="353090">this is</span> <span m="353420">one</span> <span m="353660">example</span>
  <span m="354020">of an incremental</span> <span m="354520">search</span> <span m="354830">method,</span>
  <span m="355290">incremental</span> <span m="355610">all-pairs</span> <span m="355970">shortest</span>
  <span m="356220">paths,</span> <span m="357030">which</span> <span m="357430">allows</span>
  <span m="357450">you</span> <span m="357620">to</span> <span m="358520">online</span>
  <span m="359150">compute</span> <span m="359390">paths</span> <span m="359660">between</span>
  <span m="359990">any</span> <span m="360870">start</span> <span m="361190">and goal</span>
  <span m="361610">location.</span></p><p><span m="363310">The</span> <span m="363410">idea
  is</span> <span m="363740">that</span> <span m="363860">you</span> <span m="364010">have
  a</span> <span m="364180">robot</span> <span m="364470">that's</span> <span m="364760">trying</span>
  <span m="365000">to</span> <span m="365100">move</span> <span m="365330">around</span>
  <span m="365790">one</span> <span m="366000">obstacle.</span> <span m="366590">That's</span>
  <span m="366710">what you</span> <span m="366800">see</span> <span m="366980">in</span>
  <span m="367100">the</span> <span m="367160">upper</span> <span m="368220">sequence</span>
  <span m="368610">of</span> <span m="368760">events</span> <span m="369110">there.</span>
  <span m="369380">And</span> <span m="369600">another</span> <span m="369920">obstacle</span>
  <span m="370380">is</span> <span m="370430">added, and</span> <span m="370850">now</span>
  <span m="371150">it has</span> <span m="371330">to</span> <span m="371420">plan</span>
  <span m="371630">around</span> <span m="372010">this</span> <span m="372050">new</span>
  <span m="372230">obstacle.</span> <span m="373120">In</span> <span m="373420">using</span>
  <span m="373660">this</span> <span m="373820">algorithm,</span> <span m="374420">you</span>
  <span m="374920">have</span> <span m="375080">a</span> <span m="375140">significant</span>
  <span m="375770">increase</span> <span m="376220">in</span> <span m="376310">performance</span>
  <span m="376970">and</span> <span m="377270">computation</span> <span m="377605">time</span>
  <span m="378950">using</span> <span m="379370">the</span> <span m="379670">all-pairs</span>
  <span m="380120">shortest</span> <span m="380450">paths</span> <span m="380870">versus</span>
  <span m="381230">an</span> <span m="381320">RRT.</span> <span m="382550">RRT</span>
  <span m="382700">can</span> <span m="382870">act</span> <span m="383020">as</span>
  <span m="383420">another</span> <span m="383630">version</span> <span m="383930">of</span>
  <span m="384030">an RRT,</span> <span m="384380">where</span> <span m="384510">you're</span>
  <span m="384710">planning</span> <span m="385010">basically</span> <span m="385550">from</span>
  <span m="385790">both the goal</span> <span m="386110">and</span> <span m="386480">start
  and</span> <span m="386870">connecting</span> <span m="387350">your</span> <span
  m="388520">paths.</span></p><p><span m="390080">It's on the</span> <span m="390410">order</span>
  <span m="390730">of</span> <span m="391050">what</span> <span m="391250">you</span>
  <span m="392540">get</span> <span m="392690">with</span> <span m="392840">RRT,</span>
  <span m="393230">but</span> <span m="393380">this</span> <span m="394160">RRT</span>
  <span m="394520">connect</span> <span m="395550">algorithm</span> <span m="396780">doesn't</span>
  <span m="397610">give you an</span> <span m="398030">optimal</span> <span m="398450">result.</span>
  <span m="398660">And</span> <span m="399020">then it's</span> <span m="399380">even</span>
  <span m="399740">fast than</span> <span m="400470">another</span> <span m="401150">algorithm</span>
  <span m="401765">probablistic</span> <span m="402520">road</span> <span m="402770">mapping,</span>
  <span m="403050">where you're</span> <span m="403140">randomly</span> <span m="403380">sampling</span>
  <span m="403635">the</span> <span m="403890">environment,</span> <span m="404320">and</span>
  <span m="404750">connecting</span> <span m="405860">points</span> <span m="406360">to
  produce</span> <span m="406500">a</span> <span m="406820">path.</span> <span m="408380">So</span>
  <span m="408530">the</span> <span m="408650">idea</span> <span m="408950">here</span>
  <span m="409100">is</span> <span m="409220">that</span> <span m="409760">we</span>
  <span m="409850">can</span> <span m="410270">really</span> <span m="410540">leverage</span>
  <span m="410870">this</span> <span m="411050">idea</span> <span m="411650">of</span>
  <span m="412010">reusing</span> <span m="412520">results</span> <span m="412880">from</span>
  <span m="413000">previous</span> <span m="413330">searches</span> <span m="413810">to</span>
  <span m="414050">accomplish</span> <span m="414950">fast</span> <span m="415580">replanning</span>
  <span m="416730">online.</span></p><p><span m="420381">So</span> <span m="420830">the
  whole</span> <span m="421205">idea of incremental search</span> <span m="421580">is</span>
  <span m="421740">that</span> <span m="421930">we're</span> <span m="421990">going</span>
  <span m="422110">to</span> <span m="422170">form</span> <span m="422440">a</span>
  <span m="422540">normal</span> <span m="422770">graph</span> <span m="423070">search,</span>
  <span m="425290">just</span> <span m="425470">like</span> <span m="425640">anybody's</span>
  <span m="427170">used</span> <span m="427410">to.</span> <span m="428150">And</span>
  <span m="428290">then</span> <span m="429310">we're</span> <span m="429460">going</span>
  <span m="429640">to</span> <span m="430260">repeat</span> <span m="430620">as</span>
  <span m="430930">the</span> <span m="430990">robot</span> <span m="431410">moves</span>
  <span m="431620">through</span> <span m="431800">the</span> <span m="431920">environment,</span>
  <span m="432460">or</span> <span m="432720">you're</span> <span m="433150">executing</span>
  <span m="433640">your</span> <span m="433750">plan,</span> <span m="434610">you're</span>
  <span m="434990">going to</span> <span m="435210">execute</span> <span m="435670">the</span>
  <span m="435730">next</span> <span m="435970">point in the</span> <span m="436350">plan,</span>
  <span m="436830">or the</span> <span m="436900">next</span> <span m="437410">action</span>
  <span m="437840">in</span> <span m="437910">the</span> <span m="437980">plan.</span>
  <span m="439540">We're</span> <span m="439660">going</span> <span m="439900">to</span>
  <span m="440850">receive</span> <span m="441460">changes</span> <span m="442270">from</span>
  <span m="442510">the</span> <span m="442600">environment,</span> <span m="443130">either</span>
  <span m="443350">through</span> <span m="443500">our</span> <span m="443590">sensors</span>
  <span m="445180">or</span> <span m="445480">information</span> <span m="446380">from</span>
  <span m="446530">the</span> <span m="446620">outside.</span> <span m="447470">And
  then</span> <span m="447840">we're</span> <span m="447970">going</span> <span m="448090">to</span>
  <span m="448300">use</span> <span m="448600">that</span> <span m="448990">information</span>
  <span m="449510">to</span> <span m="449570">update</span> <span m="449870">our</span>
  <span m="449970">previous</span> <span m="450280">search</span> <span m="450580">results</span>
  <span m="451370">instead</span> <span m="451600">of</span> <span m="451840">completely</span>
  <span m="452320">replanning,</span> <span m="453400">and</span> <span m="453580">then</span>
  <span m="453790">continue</span> <span m="454360">to</span> <span m="454770">form</span>
  <span m="455170">that</span> <span m="455370">loop,</span> <span m="456190">until</span>
  <span m="456460">you</span> <span m="456610">reach</span> <span m="456830">your</span>
  <span m="456920">goal.</span></p><p><span m="458950">So</span> <span m="459160">before</span>
  <span m="459370">we</span> <span m="459620">get</span> <span m="459750">into too
  many of the</span> <span m="460120">details</span> <span m="460810">of</span> <span
  m="461020">how</span> <span m="461550">we're</span> <span m="461650">going</span>
  <span m="461860">to</span> <span m="461980">accomplish</span> <span m="462520">this,</span>
  <span m="462820">first,</span> <span m="463050">we</span> <span m="463130">want</span>
  <span m="463290">to</span> <span m="463470">review</span> <span m="463780">the</span>
  <span m="464035">graph search</span> <span m="464290">problem.</span> <span m="464963">So</span>
  <span m="465306">in</span> <span m="465650">graph search,</span> <span m="467170">you</span>
  <span m="467350">have</span> <span m="467770">a</span> <span m="467830">graph</span>
  <span m="468610">consisting</span> <span m="469300">of</span> <span m="470060">vertices</span>
  <span m="470350">or</span> <span m="470700">nodes.</span> <span m="471030">We're</span>
  <span m="471260">going</span> <span m="471410">to</span> <span m="471580">use</span>
  <span m="472090">nodes</span> <span m="472480">throughout this</span> <span m="472960">lecture</span>
  <span m="473780">to talk</span> <span m="474010">about</span> <span m="474990">the</span>
  <span m="475670">vertices</span> <span m="476040">or</span> <span m="476140">nodes</span>
  <span m="476440">in</span> <span m="476590">the</span> <span m="476650">graph</span>
  <span m="477340">that</span> <span m="477670">are</span> <span m="477850">connected</span>
  <span m="478240">by</span> <span m="478450">edges.</span></p><p><span m="479530">And</span>
  <span m="479650">then,</span> <span m="480460">there's</span> <span m="480640">an
  edge</span> <span m="480880">weighting</span> <span m="481140">function</span> <span
  m="481510">that</span> <span m="481630">describes</span> <span m="482080">the</span>
  <span m="482140">cost</span> <span m="482560">going</span> <span m="482860">from</span>
  <span m="483190">one</span> <span m="483400">node</span> <span m="483670">to</span>
  <span m="483850">another.</span> <span m="484800">And</span> <span m="484890">then,</span>
  <span m="485250">a</span> <span m="485530">heuristic</span> <span m="485650">function</span>
  <span m="487090">is</span> <span m="487480">an</span> <span m="487540">estimate</span>
  <span m="487930">of</span> <span m="487990">the</span> <span m="488050">cost</span>
  <span m="488380">to</span> <span m="488470">get</span> <span m="488680">from</span>
  <span m="488970">a</span> <span m="489340">current</span> <span m="489670">node
  to the goal</span> <span m="490000">node.</span> <span m="491620">And</span> <span
  m="491740">then</span> <span m="492040">we a</span> <span m="492190">start</span>
  <span m="492550">vertex and a</span> <span m="493000">gold</span> <span m="493190">vertex.</span></p><p><span
  m="498108">In</span> <span m="498580">the graph search</span> <span m="499070">problem,</span>
  <span m="499450">we're</span> <span m="499570">also</span> <span m="499810">going</span>
  <span m="499930">to</span> <span m="499990">have</span> <span m="500230">this</span>
  <span m="500440">idea</span> <span m="501070">of</span> <span m="501530">a</span>
  <span m="501760">g</span> <span m="502020">value, or</span> <span m="502320">a</span>
  <span m="502490">cost</span> <span m="502720">so</span> <span m="502930">far.</span>
  <span m="503310">We're</span> <span m="503430">going</span> <span m="503530">to</span>
  <span m="503650">use</span> <span m="503890">term</span> <span m="504110">g</span>
  <span m="504340">value,</span> <span m="505160">which</span> <span m="505240">is</span>
  <span m="505330">essentially</span> <span m="506500">the</span> <span m="506620">cost</span>
  <span m="506980">that</span> <span m="507130">it's</span> <span m="507240">taken</span>
  <span m="507510">to</span> <span m="507610">get</span> <span m="507820">to</span>
  <span m="507970">some</span> <span m="508180">predecessor</span> <span m="508495">node,</span>
  <span m="509070">plus</span> <span m="509370">the</span> <span m="509460">cost</span>
  <span m="509960">of the node</span> <span m="510250">that</span> <span m="510430">you're</span>
  <span m="510560">actually</span> <span m="511780">expanding.</span></p><p><span
  m="512200">So</span> <span m="514630">you</span> <span m="514750">would</span> <span
  m="514860">have</span> <span m="515110">this</span> <span m="515400">W</span> <span
  m="515770">start</span> <span m="516130">to</span> <span m="516220">S1</span> <span
  m="516830">cost</span> <span m="517059">to</span> <span m="517120">get</span> <span
  m="517480">from</span> <span m="517630">start</span> <span m="517909">to</span>
  <span m="518169">S1.</span> <span m="518549">And</span> <span m="518690">then</span>
  <span m="519130">the</span> <span m="519240">g</span> <span m="519514">value for</span>
  <span m="519789">S</span> <span m="520119">goal</span> <span m="520450">would</span>
  <span m="520570">be</span> <span m="521110">the</span> <span m="521230">weight</span>
  <span m="521470">from S1</span> <span m="522070">of</span> <span m="522130">the</span>
  <span m="522220">goal</span> <span m="522549">plus the</span> <span m="522880">S1's</span>
  <span m="523179">g</span> <span m="523500">value.</span></p><p><span m="526300">Yes,</span>
  <span m="526560">go ahead.</span></p><p><span m="526940">AUDIENCE:</span> <span
  m="527010">What is</span> <span m="527220">W?</span></p><p><span m="528025">JOE
  LEAVITT:</span> <span m="528212">W</span> <span m="528400">is</span> <span m="529120">the</span>
  <span m="529240">weighting</span> <span m="529600">function</span> <span m="530380">that</span>
  <span m="530500">I</span> <span m="530560">talked</span> <span m="530770">about</span>
  <span m="530980">previously</span> <span m="531430">here.</span> <span m="531640">So</span>
  <span m="532300">the</span> <span m="532390">weighting</span> <span m="532660">function</span>
  <span m="533030">describes</span> <span m="533500">the</span> <span m="533590">cost</span>
  <span m="534280">to</span> <span m="534500">get</span> <span m="534700">from</span>
  <span m="536290">one</span> <span m="536560">node</span> <span m="536890">to</span>
  <span m="537070">another</span> <span m="537480">along</span> <span m="537840">any
  edge in a</span> <span m="538220">graph.</span> <span m="540510">And</span> <span
  m="540610">then</span> <span m="540700">we'd</span> <span m="540820">use</span>
  <span m="541120">those</span> <span m="541390">waiting</span> <span m="541690">functions</span>
  <span m="542260">to</span> <span m="542590">develop</span> <span m="543320">the</span>
  <span m="543580">idea</span> <span m="543830">of</span> <span m="543960">the G</span>
  <span m="544210">value.</span></p><p><span m="545410">So</span> <span m="546170">W</span>
  <span m="546610">is just</span> <span m="546850">the</span> <span m="548375">edge</span>
  <span m="548720">cost.</span> <span m="550840">And</span> <span m="550930">then</span>
  <span m="551685">our</span> <span m="551990">heuristic</span> <span m="552460">value,</span>
  <span m="555020">like,</span> <span m="555800">we</span> <span m="556140">use</span>
  <span m="556290">our</span> <span m="556520">heuristic</span> <span m="556610">function</span>
  <span m="557080">to</span> <span m="557230">establish</span> <span m="557495">a</span>
  <span m="557760">heuristic</span> <span m="557990">value</span> <span m="558280">from</span>
  <span m="558460">one</span> <span m="558940">goal to another,</span> <span m="559530">and</span>
  <span m="559910">we're</span> <span m="559980">going</span> <span m="560120">to</span>
  <span m="560230">call</span> <span m="560530">that</span> <span m="560760">our</span>
  <span m="561010">h</span> <span m="561250">value, or h.</span> <span m="562540">And</span>
  <span m="562630">then</span> <span m="562750">the</span> <span m="562840">total</span>
  <span m="563350">estimated</span> <span m="563860">cost</span> <span m="564340">to</span>
  <span m="564490">get</span> <span m="564670">from</span> <span m="565365">a node</span>
  <span m="565640">that</span> <span m="565860">we're</span> <span m="565960">currently</span>
  <span m="566260">expanding</span> <span m="566860">in a graph</span> <span m="566920">search</span>
  <span m="567240">is</span> <span m="568790">f,</span> <span m="569110">which</span>
  <span m="569350">is</span> <span m="569530">your</span> <span m="569740">cost</span>
  <span m="570380">so</span> <span m="570520">far,</span> <span m="571960">plus</span>
  <span m="573070">your</span> <span m="573280">estimated</span> <span m="573670">cost</span>
  <span m="574000">to</span> <span m="574090">go.</span> <span m="574620">I think
  I</span> <span m="574860">might</span> <span m="574920">have</span> <span m="575190">messed</span>
  <span m="575280">that</span> <span m="575900">up</span> <span m="576120">in there.</span>
  <span m="576430">Call g</span> <span m="576770">value</span> <span m="577100">associated</span>
  <span m="577430">cost</span> <span m="578050">so</span> <span m="578230">far,</span>
  <span m="578460">not</span> <span m="578580">cost</span> <span m="578860">to</span>
  <span m="578920">go,</span> <span m="579250">and</span> <span m="579400">then h
  is an</span> <span m="579820">estimate of</span> <span m="580210">cost</span> <span
  m="580480">to go.</span></p><p><span m="584730">So</span> <span m="585060">in</span>
  <span m="585180">order</span> <span m="585420">to</span> <span m="585720">reason</span>
  <span m="586770">about</span> <span m="587220">a</span> <span m="587270">real-world</span>
  <span m="587880">environment,</span> <span m="588340">we</span> <span m="588390">first</span>
  <span m="588600">have</span> <span m="588750">to</span> <span m="588840">take</span>
  <span m="589030">that</span> <span m="589140">environment</span> <span m="589670">and</span>
  <span m="589920">convert</span> <span m="590290">it</span> <span m="590410">to</span>
  <span m="590960">a graph, so we can</span> <span m="591290">form</span> <span m="591570">graph
  search, and</span> <span m="592130">then</span> <span m="592260">do</span> <span
  m="592470">everything</span> <span m="592830">we're</span> <span m="592920">talking</span>
  <span m="593310">about.</span> <span m="594330">Some of the examples,</span> <span
  m="594650">we're</span> <span m="595030">going to</span> <span m="595180">talk</span>
  <span m="595410">about,</span> <span m="595650">and some of the ones</span> <span
  m="596030">we've</span> <span m="596270">already</span> <span m="596460">talked</span>
  <span m="596730">about,</span> <span m="597110">we're</span> <span m="597360">using</span>
  <span m="597570">this</span> <span m="597720">notion</span> <span m="598020">of</span>
  <span m="598110">a</span> <span m="598170">grid</span> <span m="598440">world.</span>
  <span m="599510">You</span> <span m="599660">can</span> <span m="599830">have</span>
  <span m="600250">a</span> <span m="600910">four</span> <span m="601130">connected</span>
  <span m="601870">graph</span> <span m="602440">or</span> <span m="602580">a</span>
  <span m="602610">grid,</span> <span m="603590">where</span> <span m="603930">a</span>
  <span m="603960">robot</span> <span m="604380">can</span> <span m="604530">move
  up,</span> <span m="604890">down,</span> <span m="605180">left, or</span> <span
  m="605370">right,</span> <span m="605670">basically</span> <span m="605940">in</span>
  <span m="606150">x or y</span> <span m="606720">directions,</span> <span m="607380">or</span>
  <span m="607620">an eight</span> <span m="607890">connected</span> <span m="608215">graph,</span>
  <span m="608540">where you can</span> <span m="608640">also</span> <span m="609020">move</span>
  <span m="609360">along the diagonals.</span></p><p><span m="609920">And</span> <span
  m="610190">then</span> <span m="610480">had</span> <span m="610710">here,</span>
  <span m="610920">we</span> <span m="610980">just</span> <span m="611130">showed</span>
  <span m="611370">the</span> <span m="611530">graphs</span> <span m="612450">associated</span>
  <span m="613050">with</span> <span m="613620">those, with the nodes</span> <span
  m="613860">and</span> <span m="614130">edges.</span> <span m="616120">And</span>
  <span m="616360">then</span> <span m="616670">you</span> <span m="616920">would
  have</span> <span m="617300">an</span> <span m="617960">associated</span> <span
  m="618490">admissible</span> <span m="618910">heuristic</span> <span m="619510">with</span>
  <span m="619660">those</span> <span m="620260">if you're going to form a</span>
  <span m="620710">heuristic</span> <span m="620890">search.</span></p><p><span m="623650">So</span>
  <span m="624080">just</span> <span m="624320">know</span> <span m="624670">up</span>
  <span m="624780">front</span> <span m="625090">that</span> <span m="625360">any</span>
  <span m="625640">time</span> <span m="626300">we're</span> <span m="626450">moving</span>
  <span m="626750">from</span> <span m="627200">a</span> <span m="627950">real</span>
  <span m="628100">world</span> <span m="628400">environment,</span> <span m="628820">that</span>
  <span m="629000">we're</span> <span m="629120">trying</span> <span m="629330">to</span>
  <span m="629390">reason</span> <span m="629750">about</span> <span m="629890">these</span>
  <span m="629990">search</span> <span m="630370">methods,</span> <span m="630530">we
  have to</span> <span m="630800">develop</span> <span m="631996">an</span> <span
  m="632400">associated</span> <span m="632960">graph.</span> <span m="634690">And</span>
  <span m="635150">one</span> <span m="635310">more</span> <span m="635460">thing</span>
  <span m="636270">that</span> <span m="636570">is</span> <span m="636720">important</span>
  <span m="637200">as</span> <span m="637380">far</span> <span m="637530">as understanding</span>
  <span m="638130">incremental</span> <span m="638520">searches,</span> <span m="638880">is</span>
  <span m="639060">the</span> <span m="639300">notion</span> <span m="640110">or</span>
  <span m="640170">idea</span> <span m="640590">of</span> <span m="640800">relaxation.</span></p><p><span
  m="642360">We're</span> <span m="642450">going</span> <span m="642870">use</span>
  <span m="643575">Dijkstra's</span> <span m="643980">algorithm.</span> <span m="645320">Everybody</span>
  <span m="645750">here</span> <span m="646080">familiar</span> <span m="646650">with</span>
  <span m="646770">Dijkstra's</span> <span m="647150">algorithm,</span> <span m="647445">I'm
  assuming,</span> <span m="647970">in</span> <span m="648140">the</span> <span m="648220">past.</span>
  <span m="649550">We're</span> <span m="649650">going</span> <span m="649810">to</span>
  <span m="650160">use</span> <span m="650550">Dijkstra's</span> <span m="650915">algorithm</span>
  <span m="651450">to</span> <span m="652020">kind of illustrate the idea of</span>
  <span m="652500">relaxation</span> <span m="652830">and</span> <span m="653160">remind</span>
  <span m="653580">everybody</span> <span m="653780">of</span> <span m="653850">what</span>
  <span m="654030">that</span> <span m="654210">means,</span> <span m="654810">because</span>
  <span m="655095">it's</span> <span m="655380">an important</span> <span m="655590">concept</span>
  <span m="656070">when</span> <span m="656520">we're</span> <span m="656610">talking</span>
  <span m="657190">about incremental</span> <span m="657560">search</span> <span m="657850">algorithms.</span></p><p><span
  m="658972">So</span> <span m="659310">essentially,</span> <span m="659730">in</span>
  <span m="660050">Dijkstra's</span> <span m="660230">algorithm,</span> <span m="661130">it's
  a single</span> <span m="661630">source,</span> <span m="662060">shortest</span>
  <span m="662320">path</span> <span m="662580">algorithm,</span> <span m="663230">a</span>
  <span m="663520">best</span> <span m="663980">first</span> <span m="664180">search.</span>
  <span m="664980">So we're</span> <span m="665250">going to</span> <span m="665370">make
  eight</span> <span m="665790">expanding nodes</span> <span m="666600">according</span>
  <span m="667050">to</span> <span m="667230">their</span> <span m="667410">best</span>
  <span m="667850">g</span> <span m="668070">value,</span> <span m="668640">or cost</span>
  <span m="668930">so</span> <span m="669120">far.</span> <span m="670830">And</span>
  <span m="671190">we</span> <span m="671310">have</span> <span m="671520">our</span>
  <span m="671910">start</span> <span m="672320">node</span> <span m="672800">initialized</span>
  <span m="673170">to</span> <span m="673350">zero</span> <span m="673625">cost</span>
  <span m="675220">so</span> <span m="675420">far,</span> <span m="676130">because</span>
  <span m="676620">at your</span> <span m="676970">start,</span> <span m="677670">haven't</span>
  <span m="677900">accrued</span> <span m="678390">any</span> <span m="678600">cost.</span>
  <span m="679440">And</span> <span m="679560">then, every other node</span> <span
  m="679810">is</span> <span m="680080">going to</span> <span m="680290">be</span>
  <span m="680555">initialized</span> <span m="680820">to</span> <span m="681110">infinity.</span>
  <span m="682130">And</span> <span m="682200">the</span> <span m="682320">idea</span>
  <span m="682620">is</span> <span m="682920">we're going to</span> <span m="682980">find</span>
  <span m="683280">the</span> <span m="683340">shortest</span> <span m="683730">distance</span>
  <span m="684180">to</span> <span m="684270">all</span> <span m="684540">of</span>
  <span m="684630">the</span> <span m="684750">other</span> <span m="684990">nodes</span>
  <span m="685190">by relaxing</span> <span m="686570">the</span> <span m="687810">cost</span>
  <span m="689070">to</span> <span m="689310">those</span> <span m="689610">nodes</span>
  <span m="690060">from</span> <span m="690280">infinity</span> <span m="690810">down</span>
  <span m="691080">to</span> <span m="691200">their</span> <span m="691350">actual</span>
  <span m="691710">shortest</span> <span m="693300">or</span> <span m="693450">lowest</span>
  <span m="693810">cost</span> <span m="694140">value.</span></p><p><span m="695610">So</span>
  <span m="695730">we</span> <span m="695820">start</span> <span m="696150">by</span>
  <span m="696470">expanding</span> <span m="696770">the</span> <span m="697090">start</span>
  <span m="697390">node,</span> <span m="698770">and</span> <span m="698790">then</span>
  <span m="698940">you</span> <span m="699030">find</span> <span m="699300">the</span>
  <span m="699390">cost</span> <span m="701130">so</span> <span m="701310">far</span>
  <span m="701560">to each of the</span> <span m="703000">children</span> <span m="703860">nodes
  of the start</span> <span m="704190">node.</span> <span m="704640">So</span> <span
  m="704760">you have</span> <span m="705510">an</span> <span m="705960">edge</span>
  <span m="706110">way</span> <span m="706250">to one,</span> <span m="706610">and</span>
  <span m="707022">so</span> <span m="707434">the</span> <span m="707846">node</span>
  <span m="708260">on the</span> <span m="708520">bottom</span> <span m="708785">as
  a</span> <span m="709050">value of 1.</span> <span m="710170">Similarly</span> <span
  m="710580">for</span> <span m="710760">the middle</span> <span m="711030">node</span>
  <span m="711420">at</span> <span m="711810">5, and the</span> <span m="711870">top</span>
  <span m="712110">node for</span> <span m="712520">3.</span></p><p><span m="713580">Now,</span>
  <span m="714240">the</span> <span m="714330">next</span> <span m="714540">node</span>
  <span m="714740">we're</span> <span m="714840">going</span> <span m="715050">to</span>
  <span m="715170">expand,</span> <span m="715440">can</span> <span m="715710">anybody
  tell me</span> <span m="715830">what the</span> <span m="716070">next</span> <span
  m="716200">node</span> <span m="716850">we're</span> <span m="717090">going to</span>
  <span m="717420">expand</span> <span m="717750">based</span> <span m="718040">on</span>
  <span m="718290">performing</span> <span m="718735">best first</span> <span m="719180">search</span>
  <span m="719370">here</span> <span m="720310">using cost</span> <span m="721230">so</span>
  <span m="721460">far?</span></p><p><span m="722970">AUDIENCE:</span> <span m="723073">The</span>
  <span m="723176">1?</span> <span m="724410">1?</span></p><p><span m="725580">JOE
  LEAVITT:</span> <span m="725760">Yes.</span> <span m="725940">So</span> <span m="726150">the</span>
  <span m="726240">node</span> <span m="726450">labeled</span> <span m="726840">1</span>
  <span m="727140">here,</span> <span m="727470">that</span> <span m="727860">has</span>
  <span m="728090">a</span> <span m="728200">g value of</span> <span m="728320">1</span>
  <span m="728820">is</span> <span m="728920">the</span> <span m="728990">lowest</span>
  <span m="729280">out of</span> <span m="729510">1,</span> <span m="729880">3,</span>
  <span m="730180">and 5,</span> <span m="730470">and</span> <span m="730875">infinity.</span>
  <span m="732090">So</span> <span m="732270">we're</span> <span m="732330">going</span>
  <span m="732450">to</span> <span m="732510">go</span> <span m="732630">ahead</span>
  <span m="732810">and</span> <span m="732900">expand</span> <span m="733290">1</span>
  <span m="733560">next.</span> <span m="735110">And</span> <span m="735510">now,</span>
  <span m="735690">we</span> <span m="735810">find</span> <span m="736170">that</span>
  <span m="737070">using</span> <span m="737610">this</span> <span m="737850">value</span>
  <span m="738330">of</span> <span m="738470">1</span> <span m="739650">plus</span>
  <span m="740060">3</span> <span m="740370">equals</span> <span m="740790">4,</span>
  <span m="741330">which</span> <span m="741540">is</span> <span m="741690">less</span>
  <span m="741990">than</span> <span m="742140">what</span> <span m="742230">we</span>
  <span m="742380">previously</span> <span m="742830">had</span> <span m="743000">here
  as</span> <span m="743240">4.</span> <span m="743710">So now the</span> <span m="744210">center
  node</span> <span m="744470">has</span> <span m="744600">been relaxed</span> <span
  m="744690">from</span> <span m="745110">a value of 5</span> <span m="746020">down</span>
  <span m="746360">to</span> <span m="746720">4.</span></p><p><span m="747060">So</span>
  <span m="747330">now</span> <span m="749110">the</span> <span m="749380">shortest</span>
  <span m="749630">path</span> <span m="750090">we</span> <span m="750450">found</span>
  <span m="750720">to the</span> <span m="750830">center</span> <span m="751110">node</span>
  <span m="751470">is</span> <span m="751860">4.</span> <span m="752480">And we're
  going to continue</span> <span m="753060">to</span> <span m="753150">perform</span>
  <span m="753600">this</span> <span m="755220">by</span> <span m="756090">going</span>
  <span m="756390">through</span> <span m="756600">each</span> <span m="756840">node</span>
  <span m="757140">in</span> <span m="757260">order</span> <span m="757680">of the</span>
  <span m="757980">lowest</span> <span m="758340">cost.</span> <span m="760200">And</span>
  <span m="760410">similarly,</span> <span m="760950">you</span> <span m="761100">saw</span>
  <span m="761430">how</span> <span m="761880">the</span> <span m="762060">top</span>
  <span m="762310">node</span> <span m="762570">was</span> <span m="762780">relaxed</span>
  <span m="762840">to</span> <span m="763250">6</span> <span m="763690">by</span>
  <span m="763860">going</span> <span m="764130">through</span> <span m="764750">1,</span>
  <span m="765110">3,</span> <span m="765425">and</span> <span m="765740">2,</span>
  <span m="766250">where</span> <span m="766400">as</span> <span m="766530">previously,</span>
  <span m="766890">it</span> <span m="767250">had</span> <span m="767400">a</span>
  <span m="767460">lowest</span> <span m="767790">cost</span> <span m="768060">of</span>
  <span m="768120">7</span> <span m="768510">going through</span> <span m="768950">3</span>
  <span m="769320">and</span> <span m="769440">4.</span> <span m="770920">And</span>
  <span m="771200">if we</span> <span m="771350">format</span> <span m="771720">through</span>
  <span m="771870">the</span> <span m="771960">whole</span> <span m="772140">graph</span>
  <span m="772790">until</span> <span m="772950">all</span> <span m="773400">nodes</span>
  <span m="773640">have</span> <span m="773700">been</span> <span m="774225">unexpanded,</span>
  <span m="774790">then</span> <span m="774980">we've</span> <span m="775240">relaxed</span>
  <span m="775740">every</span> <span m="776040">node</span> <span m="776310">in</span>
  <span m="776370">the</span> <span m="776430">graph</span> <span m="776780">to</span>
  <span m="776920">its</span> <span m="777070">shortest</span> <span m="778170">path</span>
  <span m="778570">value.</span></p><p><span m="779460">And</span> <span m="779580">then,</span>
  <span m="780600">we</span> <span m="780690">can</span> <span m="780810">just</span>
  <span m="780960">do</span> <span m="781110">a</span> <span m="781180">greedy</span>
  <span m="781380">search</span> <span m="782600">from</span> <span m="782950">a chosen</span>
  <span m="783320">goal</span> <span m="783590">node,</span> <span m="785670">back</span>
  <span m="785910">through</span> <span m="786120">the</span> <span m="786180">graph</span>
  <span m="786800">to</span> <span m="786930">find</span> <span m="787180">shortest</span>
  <span m="787590">path.</span></p><p><span m="790680">AUDIENCE:</span> <span m="790785">Is</span>
  <span m="790890">the</span> <span m="790950">term</span> <span m="791250">relaxation</span>
  <span m="792360">standard?</span> <span m="793770">Because</span> <span m="794990">the</span>
  <span m="795400">fact that</span> <span m="795810">you're</span> <span m="795990">bringing</span>
  <span m="796380">numbers</span> <span m="796520">from infinity</span> <span m="797880">double
  to</span> <span m="798540">small</span> <span m="798960">value</span> <span m="799850">sounds</span>
  <span m="800150">more</span> <span m="800300">like</span> <span m="800510">tightening</span>
  <span m="800892">as</span> <span m="801274">opposed to</span> <span m="801656">relaxation.</span>
  <span m="802040">So</span> <span m="802300">I</span> <span m="802430">was</span>
  <span m="802600">just</span> <span m="802770">wondering</span> <span m="802960">if</span>
  <span m="803020">people use</span> <span m="803360">it</span> <span m="804090">as
  like, a</span> <span m="804500">standard--</span></p><p><span m="805830">JOE LEAVITT:</span>
  <span m="805890">I'm</span> <span m="805950">not</span> <span m="806130">sure</span>
  <span m="806310">if</span> <span m="806420">it</span> <span m="806520">is</span>
  <span m="806790">in</span> <span m="807510">all</span> <span m="807870">areas,</span>
  <span m="808440">but</span> <span m="811050">I</span> <span m="811140">have</span>
  <span m="811350">seen</span> <span m="811760">it</span> <span m="811950">in</span>
  <span m="812280">multiple</span> <span m="812740">places.</span> <span m="813230">When</span>
  <span m="813500">you're</span> <span m="813580">talking</span> <span m="814010">about</span>
  <span m="814290">graph</span> <span m="814570">search,</span> <span m="815080">specifically</span>
  <span m="815395">with</span> <span m="815710">respect</span> <span m="815860">to</span>
  <span m="816150">Dijkstra's</span> <span m="816600">algorithm,</span> <span m="818940">that</span>
  <span m="819240">is</span> <span m="819510">where</span> <span m="819750">the</span>
  <span m="819850">term</span> <span m="820020">relaxation</span> <span m="820710">is</span>
  <span m="820830">used.</span> <span m="821670">And</span> <span m="822350">we're</span>
  <span m="822540">going to</span> <span m="822740">use</span> <span m="822880">that</span>
  <span m="823090">as we go throughout</span> <span m="823690">and talk</span> <span
  m="823890">about</span> <span m="824370">incremental search.</span> <span m="825660">We're</span>
  <span m="825930">kind</span> <span m="826110">of</span> <span m="826200">repairing</span>
  <span m="826690">the</span> <span m="826920">results</span> <span m="827310">because</span>
  <span m="827490">of</span> <span m="827650">new</span> <span m="828360">edge</span>
  <span m="828840">weights and</span> <span m="828930">things</span> <span m="829140">like</span>
  <span m="829320">that.</span> <span m="829490">We're</span> <span m="829560">going</span>
  <span m="829680">to</span> <span m="829800">figure</span> <span m="830070">out</span>
  <span m="830160">which</span> <span m="830310">nodes</span> <span m="830400">we</span>
  <span m="830730">have</span> <span m="830910">to</span> <span m="831420">relax</span>
  <span m="831900">back</span> <span m="832140">down</span> <span m="832430">to</span>
  <span m="832540">their</span> <span m="832750">shortest</span> <span m="833080">value
  to be</span> <span m="833570">able to</span> <span m="833810">find</span> <span
  m="834183">the new</span> <span m="834556">shortest</span> <span m="834930">path.</span></p><p><span
  m="836790">So</span> <span m="837170">that's</span> <span m="837400">the term we're</span>
  <span m="837650">going to use</span> <span m="837870">here</span> <span m="838320">if
  it's</span> <span m="838440">not</span> <span m="838620">used</span> <span m="839250">universally.</span>
  <span m="840590">I</span> <span m="841590">can't</span> <span m="841770">say</span>
  <span m="841920">for</span> <span m="842190">certain.</span> <span m="842730">But</span>
  <span m="844200">we</span> <span m="844320">will use</span> <span m="845100">relaxation</span>
  <span m="845610">to</span> <span m="845670">talk</span> <span m="845850">about</span>
  <span m="846330">reducing--</span> <span m="847920">it's</span> <span m="848560">kind</span>
  <span m="848760">of</span> <span m="849540">related</span> <span m="849930">to--</span>
  <span m="850860">think</span> <span m="851060">about like,</span> <span m="851370">a
  tension</span> <span m="851780">spring.</span> <span m="853830">As</span> <span
  m="854070">you</span> <span m="856890">reduce</span> <span m="857180">the</span>
  <span m="857280">constraints</span> <span m="857760">on</span> <span m="857920">it,</span>
  <span m="858340">it'll slowly</span> <span m="858540">relax</span> <span m="858730">to</span>
  <span m="859320">its</span> <span m="859860">completely</span> <span m="860460">relaxed</span>
  <span m="860880">position.</span> <span m="861300">That's</span> <span m="861470">kind</span>
  <span m="861650">of</span> <span m="861700">the</span> <span m="861840">idea</span>
  <span m="862180">here.</span></p><p><span m="865704">So</span> <span m="866190">now
  that</span> <span m="866480">we</span> <span m="866600">have</span> <span m="867820">talked</span>
  <span m="868170">about</span> <span m="868340">the ideas</span> <span m="869020">of</span>
  <span m="869390">relaxation and</span> <span m="869630">graph</span> <span m="870040">search,</span>
  <span m="871430">how</span> <span m="871730">do we</span> <span m="872180">reuse</span>
  <span m="872540">the</span> <span m="872810">results</span> <span m="873860">from</span>
  <span m="874070">a</span> <span m="874130">previous</span> <span m="874520">search</span>
  <span m="875110">in</span> <span m="875210">a</span> <span m="875270">new</span>
  <span m="875450">search</span> <span m="875830">field</span> <span m="876110">to</span>
  <span m="878515">employ</span> <span m="878790">an</span> <span m="879860">incremental</span>
  <span m="880175">search</span> <span m="880490">method</span> <span m="880850">where
  you have</span> <span m="881300">done</span> <span m="881480">a</span> <span m="881510">search,</span>
  <span m="881870">you</span> <span m="881960">found</span> <span m="882200">the</span>
  <span m="882260">shortest</span> <span m="882560">path,</span> <span m="883430">and</span>
  <span m="883520">now,</span> <span m="884060">you</span> <span m="884150">had</span>
  <span m="884270">some</span> <span m="884420">changes</span> <span m="884780">to</span>
  <span m="884840">your</span> <span m="885090">graph,</span> <span m="885760">and</span>
  <span m="886850">you</span> <span m="887080">want</span> <span m="887260">to</span>
  <span m="887370">use</span> <span m="887670">your</span> <span m="888250">previous</span>
  <span m="888620">results</span> <span m="889280">to</span> <span m="889820">come</span>
  <span m="890010">up</span> <span m="890110">with</span> <span m="890250">your new</span>
  <span m="890340">shortest</span> <span m="890650">path.</span></p><p><span m="891470">So</span>
  <span m="891670">the way we're</span> <span m="891930">going</span> <span m="892070">to</span>
  <span m="892130">do</span> <span m="892310">that,</span> <span m="893060">is we're</span>
  <span m="893270">going</span> <span m="893370">to</span> <span m="893470">store</span>
  <span m="893810">our optimal</span> <span m="894140">results</span> <span m="894620">from</span>
  <span m="895010">a</span> <span m="895100">previous</span> <span m="897080">search.</span>
  <span m="898520">This</span> <span m="898670">can</span> <span m="898760">be</span>
  <span m="898820">done</span> <span m="899030">in a number</span> <span m="899130">of</span>
  <span m="899500">ways.</span> <span m="899760">It's</span> <span m="899900">going</span>
  <span m="900020">to</span> <span m="900080">depend</span> <span m="900410">on</span>
  <span m="900530">the</span> <span m="900650">algorithm.</span> <span m="902460">But</span>
  <span m="902990">you</span> <span m="903110">can</span> <span m="903620">soar</span>
  <span m="904610">like,</span> <span m="904820">a</span> <span m="904850">list</span>
  <span m="905090">of</span> <span m="905300">shortest</span> <span m="905660">paths</span>
  <span m="906020">as</span> <span m="906380">an</span> <span m="906560">incremental</span>
  <span m="906915">all-pairs</span> <span m="907270">shortest</span> <span m="907670">paths</span>
  <span m="908000">problem.</span> <span m="909210">The one</span> <span m="909470">we're</span>
  <span m="909620">going</span> <span m="909740">to</span> <span m="909800">talk</span>
  <span m="910010">most</span> <span m="910250">about is</span> <span m="910500">storing</span>
  <span m="910880">g</span> <span m="911330">values,</span> <span m="912620">and</span>
  <span m="913280">that's</span> <span m="913510">what's</span> <span m="913790">done</span>
  <span m="914060">in a</span> <span m="914150">D*</span> <span m="914430">Lite</span>
  <span m="914680">algorithm,</span> <span m="916090">where you're</span> <span m="916730">finding</span>
  <span m="917030">the</span> <span m="917120">shortest</span> <span m="917540">distance</span>
  <span m="918020">from</span> <span m="918560">any</span> <span m="918690">given</span>
  <span m="918950">node</span> <span m="921140">that</span> <span m="921440">you've</span>
  <span m="921930">expanded so</span> <span m="922040">far</span> <span m="922450">in
  your</span> <span m="922550">search</span> <span m="922815">to</span> <span m="923080">the
  goal node.</span></p><p><span m="925160">And</span> <span m="925280">then,</span>
  <span m="926080">you'll</span> <span m="926300">use</span> <span m="926540">that</span>
  <span m="926750">data</span> <span m="927020">to</span> <span m="927080">find</span>
  <span m="927350">out,</span> <span m="927500">find the</span> <span m="927620">shortest</span>
  <span m="927800">path.</span> <span m="928710">And</span> <span m="928810">then</span>
  <span m="929030">when</span> <span m="929210">you</span> <span m="929270">go</span>
  <span m="929520">to</span> <span m="929610">perform</span> <span m="929990">your</span>
  <span m="930140">next</span> <span m="930440">iteration,</span> <span m="931520">you'll</span>
  <span m="931910">look</span> <span m="932090">for</span> <span m="932370">inconsistencies</span>
  <span m="933200">in</span> <span m="933290">that</span> <span m="933410">graph.</span>
  <span m="934280">And</span> <span m="934400">then</span> <span m="934920">in</span>
  <span m="934980">order</span> <span m="935190">to</span> <span m="935270">find</span>
  <span m="935900">a</span> <span m="936170">new</span> <span m="936290">shortest</span>
  <span m="936650">path,</span> <span m="937030">we'll</span> <span m="937150">leverage</span>
  <span m="937500">that</span> <span m="937680">previous</span> <span m="938000">data</span>
  <span m="938370">and the inconsistencies</span> <span m="940540">for</span> <span
  m="940960">relaxations</span> <span m="941650">to</span> <span m="941750">come</span>
  <span m="941930">up</span> <span m="942170">with</span> <span m="942410">a new</span>
  <span m="943300">optimal</span> <span m="943680">solution.</span></p><p><span m="945920">And</span>
  <span m="946010">that's</span> <span m="946190">all</span> <span m="946280">we're</span>
  <span m="946370">showing</span> <span m="946670">here.</span> <span m="946880">On</span>
  <span m="946940">the</span> <span m="947000">right</span> <span m="947240">side</span>
  <span m="947450">of</span> <span m="947510">these two</span> <span m="947800">graphics</span>
  <span m="948310">is</span> <span m="948470">you</span> <span m="948570">have</span>
  <span m="948710">the</span> <span m="948850">initial</span> <span m="949310">search.</span>
  <span m="950290">You</span> <span m="950420">have</span> <span m="950570">an</span>
  <span m="950660">obstacle</span> <span m="951110">that</span> <span m="951980">is</span>
  <span m="952100">now</span> <span m="952400">in</span> <span m="952500">a</span>
  <span m="952550">place</span> <span m="952880">that</span> <span m="953000">was</span>
  <span m="953450">wasn't</span> <span m="953660">there</span> <span m="953840">previously,</span>
  <span m="954800">which causes</span> <span m="955130">you</span> <span m="955650">to
  update</span> <span m="955980">edge weights</span> <span m="956790">in</span> <span
  m="957030">the</span> <span m="957190">graph</span> <span m="957500">associated</span>
  <span m="958100">with</span> <span m="958250">this</span> <span m="958430">grid</span>
  <span m="958750">world.</span> <span m="959470">And</span> <span m="959620">then</span>
  <span m="960320">using</span> <span m="960650">these</span> <span m="960860">values</span>
  <span m="961430">which</span> <span m="961580">represent</span> <span m="962220">the</span>
  <span m="962850">g</span> <span m="963160">values</span> <span m="963780">in</span>
  <span m="963890">the</span> <span m="963950">graph</span> <span m="964220">search,</span>
  <span m="965690">you</span> <span m="966050">only</span> <span m="967250">update</span>
  <span m="967640">the ones</span> <span m="968030">you need</span> <span m="968420">to</span>
  <span m="968630">update</span> <span m="968840">to find a new</span> <span m="969060">optimal</span>
  <span m="969500">path.</span> <span m="971870">And so</span> <span m="972200">completely</span>
  <span m="972980">reperforming</span> <span m="973780">our</span> <span m="973940">search.</span></p><p><span
  m="976830">So</span> <span m="977440">what</span> <span m="977590">incremental</span>
  <span m="977680">search methods</span> <span m="977820">exist,</span> <span m="979470">now
  that we've</span> <span m="979910">kind</span> <span m="980120">of</span> <span
  m="980230">talked</span> <span m="980420">about</span> <span m="980640">what</span>
  <span m="980810">they</span> <span m="980990">are</span> <span m="982850">and</span>
  <span m="983390">what</span> <span m="983780">we</span> <span m="983870">can</span>
  <span m="984050">do</span> <span m="984200">with</span> <span m="984370">them?</span>
  <span m="985350">So</span> <span m="985700">the</span> <span m="985800">whole</span>
  <span m="986020">idea</span> <span m="986510">of</span> <span m="987070">this</span>
  <span m="987380">slide</span> <span m="987650">here</span> <span m="987890">is</span>
  <span m="988070">to</span> <span m="988150">show you</span> <span m="988580">that</span>
  <span m="989640">incremental</span> <span m="990100">search</span> <span m="990540">can</span>
  <span m="990670">be</span> <span m="990830">used</span> <span m="991070">across</span>
  <span m="991430">many</span> <span m="991670">domains.</span> <span m="992090">It's</span>
  <span m="992210">not</span> <span m="992360">just</span> <span m="992540">specific</span>
  <span m="992620">to path planning.</span> <span m="994810">It's</span> <span m="994940">used</span>
  <span m="995755">in</span> <span m="996210">temporal</span> <span m="996520">planning</span>
  <span m="996860">to</span> <span m="997070">determine</span> <span m="997520">temporal</span>
  <span m="997730">consistency.</span> <span m="998840">It</span> <span m="998960">can</span>
  <span m="999090">be</span> <span m="999230">used</span> <span m="999490">propositional</span>
  <span m="1000130">satisfiability.</span> <span m="1004130">Instead</span> <span
  m="1004480">of</span> <span m="1004750">every</span> <span m="1004930">time</span>
  <span m="1005200">you're</span> <span m="1007290">updating</span> <span m="1008240">another</span>
  <span m="1008510">algorithm,</span> <span m="1008870">you</span> <span m="1008950">can</span>
  <span m="1009140">use</span> <span m="1009340">your</span> <span m="1009430">previous</span>
  <span m="1009790">results.</span></p><p><span m="1010960">And</span> <span m="1012635">the
  one</span> <span m="1013050">we're</span> <span m="1013120">going</span> <span m="1013240">to</span>
  <span m="1013300">focus on</span> <span m="1013440">today</span> <span m="1013880">is</span>
  <span m="1013970">D* Lite,</span> <span m="1014860">which</span> <span m="1015130">is</span>
  <span m="1015290">specific to</span> <span m="1015710">mobile and</span> <span m="1016090">robots.</span>
  <span m="1017300">But the</span> <span m="1017830">ideas</span> <span m="1018310">and</span>
  <span m="1018400">concepts</span> <span m="1018790">we're</span> <span m="1018880">going</span>
  <span m="1019000">to</span> <span m="1019060">talk</span> <span m="1019270">about</span>
  <span m="1019510">there</span> <span m="1019850">are</span> <span m="1020410">applicable</span>
  <span m="1021120">elsewhere,</span> <span m="1021385">and</span> <span m="1021650">you</span>
  <span m="1021760">can</span> <span m="1021910">use</span> <span m="1022380">to</span>
  <span m="1023440">help</span> <span m="1023650">you</span> <span m="1023920">learn</span>
  <span m="1024060">about</span> <span m="1024450">and</span> <span m="1024650">expand</span>
  <span m="1024986">your</span> <span m="1025322">knowledge</span> <span m="1025660">in</span>
  <span m="1025790">other</span> <span m="1026190">incremental</span> <span m="1027400">search.</span></p><p><span
  m="1029175">So</span> <span m="1029630">the</span> <span m="1029880">D*</span> <span
  m="1030250">incremental</span> <span m="1030565">path planning</span> <span m="1030880">approach.</span>
  <span m="1031609">The</span> <span m="1031670">whole</span> <span m="1031819">idea</span>
  <span m="1032119">behind</span> <span m="1032510">it</span> <span m="1033010">is</span>
  <span m="1033140">that</span> <span m="1033230">we're</span> <span m="1033319">going</span>
  <span m="1033440">to</span> <span m="1033500">take</span> <span m="1034849">the</span>
  <span m="1035010">idea</span> <span m="1035339">of</span> <span m="1035540">incremental</span>
  <span m="1035900">search</span> <span m="1036349">that</span> <span m="1036730">we</span>
  <span m="1036800">just</span> <span m="1036980">talked</span> <span m="1037220">it</span>
  <span m="1037339">about,</span> <span m="1037980">and</span> <span m="1038079">we're</span>
  <span m="1038180">going to</span> <span m="1038280">combine</span> <span m="1038640">it</span>
  <span m="1038740">with</span> <span m="1038760">heuristic</span> <span m="1039200">search,</span>
  <span m="1040619">which</span> <span m="1040880">is</span> <span m="1041119">an</span>
  <span m="1041240">optimal</span> <span m="1041599">solution.</span> <span m="1042599">And</span>
  <span m="1043619">the idea is that</span> <span m="1043849">two</span> <span m="1044000">things</span>
  <span m="1045589">are</span> <span m="1046314">orthogonal</span> <span m="1046569">so</span>
  <span m="1046880">we</span> <span m="1047450">can</span> <span m="1047599">combine</span>
  <span m="1047960">them,</span> <span m="1048560">and</span> <span m="1048650">then</span>
  <span m="1048770">we</span> <span m="1048890">can</span> <span m="1049070">form</span>
  <span m="1049520">efficient</span> <span m="1050010">incremental</span> <span m="1050360">path</span>
  <span m="1050690">planning,</span> <span m="1051490">getting</span> <span m="1051790">both</span>
  <span m="1052020">an</span> <span m="1052130">optimal</span> <span m="1052390">result,</span>
  <span m="1053030">and</span> <span m="1053480">quickly</span> <span m="1054650">getting</span>
  <span m="1054890">a</span> <span m="1054950">new</span> <span m="1055280">path</span>
  <span m="1055670">when</span> <span m="1055920">things</span> <span m="1056240">change</span>
  <span m="1056630">in the</span> <span m="1056690">environment</span> <span m="1057290">without
  having</span> <span m="1057410">to completely replan.</span></p><p><span m="1058650">And</span>
  <span m="1059006">so</span> <span m="1059362">what</span> <span m="1059720">that</span>
  <span m="1059930">looks</span> <span m="1060140">like,</span> <span m="1060935">when</span>
  <span m="1062330">we</span> <span m="1062450">have</span> <span m="1062660">a</span>
  <span m="1062690">grid</span> <span m="1062930">world,</span> <span m="1063680">which</span>
  <span m="1063860">is</span> <span m="1063920">shown</span> <span m="1064280">in
  four</span> <span m="1064580">instances</span> <span m="1065090">here</span> <span
  m="1065350">up on</span> <span m="1065470">the</span> <span m="1065540">board,</span>
  <span m="1066920">and</span> <span m="1067040">we're</span> <span m="1067160">trying</span>
  <span m="1067370">to</span> <span m="1067490">plan</span> <span m="1067790">from</span>
  <span m="1067960">a</span> <span m="1068000">start</span> <span m="1068470">node</span>
  <span m="1068690">to a goal</span> <span m="1068930">node,</span> <span m="1069340">and
  showing</span> <span m="1069590">each</span> <span m="1069780">of</span> <span m="1069860">these</span>
  <span m="1070640">sections.</span> <span m="1071510">And</span> <span m="1071910">in</span>
  <span m="1072170">the</span> <span m="1072260">upper</span> <span m="1072470">left</span>
  <span m="1073340">or</span> <span m="1073490">on</span> <span m="1073640">the</span>
  <span m="1073700">left</span> <span m="1073940">axis,</span> <span m="1074480">we</span>
  <span m="1074600">have--</span> <span m="1075522">whether</span> <span m="1076466">we're</span>
  <span m="1076940">performing</span> <span m="1077360">a</span> <span m="1078340">complete</span>
  <span m="1078700">search</span> <span m="1079030">or an</span> <span m="1079220">incremental</span>
  <span m="1079460">search.</span> <span m="1080000">And on</span> <span m="1080270">the</span>
  <span m="1080570">horizontal</span> <span m="1081050">axis,</span> <span m="1081890">whether</span>
  <span m="1082130">it's</span> <span m="1082280">an</span> <span m="1082370">uninformed</span>
  <span m="1082820">search</span> <span m="1083120">or</span> <span m="1083240">a</span>
  <span m="1083460">heuristic</span> <span m="1083690">search.</span></p><p><span
  m="1084320">So</span> <span m="1084440">the</span> <span m="1084560">upper</span>
  <span m="1084770">left</span> <span m="1085730">is</span> <span m="1086640">a</span>
  <span m="1086690">complete</span> <span m="1087110">search,</span> <span m="1087680">just
  using</span> <span m="1088060">best-first</span> <span m="1088970">search</span>
  <span m="1089270">and</span> <span m="1089610">no</span> <span m="1090110">heuristics.</span>
  <span m="1090410">And</span> <span m="1090710">what it's</span> <span m="1090890">showing</span>
  <span m="1091260">is</span> <span m="1091320">all</span> <span m="1091550">the</span>
  <span m="1091650">nodes that are</span> <span m="1092110">expanded,</span> <span
  m="1092510">and</span> <span m="1092620">trying</span> <span m="1092840">to</span>
  <span m="1092900">find</span> <span m="1093500">a</span> <span m="1093530">path</span>
  <span m="1093830">from</span> <span m="1093980">the</span> <span m="1094070">start</span>
  <span m="1094450">to the</span> <span m="1094740">goal.</span> <span m="1096046">In
  the upper right</span> <span m="1096700">is</span> <span m="1096860">a</span> <span
  m="1096950">heuristic search,</span> <span m="1097320">A*.</span> <span m="1099035">Employing</span>
  <span m="1099710">the</span> <span m="1100050">heuristic,</span> <span m="1100340">we're</span>
  <span m="1100460">able</span> <span m="1100770">to</span> <span m="1101050">collapse</span>
  <span m="1101330">the</span> <span m="1101440">number</span> <span m="1101680">of</span>
  <span m="1101790">nodes</span> <span m="1102410">expanded</span> <span m="1102840">by</span>
  <span m="1103010">quite</span> <span m="1103250">a</span> <span m="1103290">bit.</span></p><p><span
  m="1104200">In</span> <span m="1104680">the</span> <span m="1104750">bottom</span>
  <span m="1105050">left</span> <span m="1105890">is</span> <span m="1106490">an</span>
  <span m="1106970">incremental</span> <span m="1107360">search</span> <span m="1107660">method</span>
  <span m="1108620">that's</span> <span m="1108890">using</span> <span m="1110270">uninformed</span>
  <span m="1111290">search</span> <span m="1111620">or</span> <span m="1111900">best-first</span>
  <span m="1112380">search</span> <span m="1113180">as</span> <span m="1113330">an</span>
  <span m="1113390">underlying</span> <span m="1114320">search</span> <span m="1114610">algorithm,</span>
  <span m="1115070">so</span> <span m="1115250">it's</span> <span m="1115370">going</span>
  <span m="1115520">to</span> <span m="1115580">expand the</span> <span m="1115910">same</span>
  <span m="1116240">nodes</span> <span m="1116660">as the</span> <span m="1116960">best-first</span>
  <span m="1117720">search.</span> <span m="1118650">And</span> <span m="1119050">then
  in the bottom right,</span> <span m="1119350">you see</span> <span m="1121000">an</span>
  <span m="1121420">incremental</span> <span m="1122330">heuristic</span> <span m="1122585">search,</span>
  <span m="1123560">the</span> <span m="1123900">lifelong</span> <span m="1124730">planning</span>
  <span m="1125120">A*</span> <span m="1125900">algorithm,</span> <span m="1126780">which</span>
  <span m="1126800">is</span> <span m="1126920">kind</span> <span m="1127070">of</span>
  <span m="1127160">the</span> <span m="1127220">baseline</span> <span m="1127760">for</span>
  <span m="1127990">the</span> <span m="1128250">D*</span> <span m="1128500">Lite</span>
  <span m="1128860">we're</span> <span m="1129220">going to talk about,</span> <span
  m="1130130">that</span> <span m="1130430">the</span> <span m="1131160">initial</span>
  <span m="1131540">search</span> <span m="1131870">will</span> <span m="1132150">expand</span>
  <span m="1132590">the same nodes</span> <span m="1133280">as</span> <span m="1133550">the
  heuristic search,</span> <span m="1133740">since it's</span> <span m="1134085">using</span>
  <span m="1134430">A*</span> <span m="1134790">as its</span> <span m="1135510">baseline.</span></p><p><span
  m="1138210">So</span> <span m="1138260">now</span> <span m="1138920">let's</span>
  <span m="1139790">say</span> <span m="1140140">the</span> <span m="1140230">robot</span>
  <span m="1140610">moves.</span> <span m="1141000">We get an</span> <span m="1141340">update</span>
  <span m="1141770">to</span> <span m="1141920">the</span> <span m="1142010">environment.</span>
  <span m="1142490">There's a</span> <span m="1142660">bunch of</span> <span m="1142890">changed</span>
  <span m="1143340">edges.</span> <span m="1145730">And</span> <span m="1146240">now</span>
  <span m="1146590">best-first</span> <span m="1146850">search,</span> <span m="1147740">as</span>
  <span m="1147860">you</span> <span m="1147920">can</span> <span m="1148070">see,</span>
  <span m="1148280">is</span> <span m="1148745">going to have</span> <span m="1149495">to</span>
  <span m="1149780">expand</span> <span m="1150590">pretty</span> <span m="1150770">much</span>
  <span m="1151040">the</span> <span m="1151130">same</span> <span m="1151340">number,</span>
  <span m="1151760">if</span> <span m="1151910">not</span> <span m="1152120">more</span>
  <span m="1152410">nodes,</span> <span m="1152720">then</span> <span m="1153055">our</span>
  <span m="1153390">previous</span> <span m="1153830">search.</span> <span m="1154820">And</span>
  <span m="1154910">A*</span> <span m="1155150">also</span> <span m="1155390">is</span>
  <span m="1156050">going</span> <span m="1156170">to</span> <span m="1156920">expand</span>
  <span m="1157230">about</span> <span m="1157430">the same number of nodes</span>
  <span m="1157850">as it did</span> <span m="1158220">previously.</span></p><p><span
  m="1158960">The</span> <span m="1159650">incremental</span> <span m="1160070">search</span>
  <span m="1160370">method</span> <span m="1160970">using</span> <span m="1161480">best-first</span>
  <span m="1161790">search,</span> <span m="1162920">by</span> <span m="1163100">using</span>
  <span m="1163420">previous</span> <span m="1163760">results,</span> <span m="1164210">reduces</span>
  <span m="1164690">significantly</span> <span m="1165290">the</span> <span m="1165350">number</span>
  <span m="1165620">of</span> <span m="1165690">nodes</span> <span m="1165860">that</span>
  <span m="1165980">needs</span> <span m="1166100">to</span> <span m="1166220">be</span>
  <span m="1166340">expanded.</span> <span m="1167420">And</span> <span m="1167550">then,</span>
  <span m="1168020">lifelong</span> <span m="1168650">planning</span> <span m="1168850">A*,</span>
  <span m="1169140">the</span> <span m="1169430">incremental</span> <span m="1169730">search</span>
  <span m="1170160">plus the</span> <span m="1170230">heuristic</span> <span m="1170550">search,</span>
  <span m="1172700">reduces</span> <span m="1173100">that</span> <span m="1173250">number</span>
  <span m="1173520">by</span> <span m="1173760">even</span> <span m="1174090">more.</span></p><p><span
  m="1175400">Even</span> <span m="1175745">when</span> <span m="1176090">there's</span>
  <span m="1176410">quite</span> <span m="1176820">a</span> <span m="1177010">few</span>
  <span m="1177170">changes</span> <span m="1177590">in the</span> <span m="1177980">environment,
  you</span> <span m="1178130">have</span> <span m="1178380">very</span> <span m="1178620">few</span>
  <span m="1178730">nodes</span> <span m="1178880">that you</span> <span m="1179090">need</span>
  <span m="1179280">to expand on</span> <span m="1179600">the</span> <span m="1180070">next</span>
  <span m="1180280">search</span> <span m="1180680">in</span> <span m="1180800">order</span>
  <span m="1181010">to</span> <span m="1181940">find</span> <span m="1182850">a</span>
  <span m="1182960">new</span> <span m="1183500">optimal</span> <span m="1183890">path.</span>
  <span m="1185384">With that,</span> <span m="1186200">I'll</span> <span m="1187420">turn
  it</span> <span m="1188010">over</span> <span m="1188240">to</span> <span m="1188530">Ben</span>
  <span m="1188680">to</span> <span m="1189040">talk about the</span> <span m="1189180">D*</span>
  <span m="1189380">Lite</span> <span m="1189872">algorithm.</span></p><p><span m="1192824">BEN
  AYTON:</span> <span m="1193320">Thanks.</span> <span m="1193790">So</span> <span
  m="1194000">I'll</span> <span m="1194120">be</span> <span m="1194330">walking you</span>
  <span m="1194600">through</span> <span m="1194780">the</span> <span m="1195070">D*</span>
  <span m="1195230">Light</span> <span m="1195420">algorithm</span> <span m="1195780">today.</span>
  <span m="1196800">Now</span> <span m="1197140">as we're</span> <span m="1197295">emphasizing,</span>
  <span m="1197760">the</span> <span m="1198020">D*</span> <span m="1198290">Lite</span>
  <span m="1198440">is</span> <span m="1198650">not</span> <span m="1198800">the</span>
  <span m="1199010">only</span> <span m="1199315">incremental</span> <span m="1199980">algorithm,</span>
  <span m="1200350">as</span> <span m="1200990">we</span> <span m="1201080">mentioned</span>
  <span m="1201440">previously.</span> <span m="1202190">But</span> <span m="1202460">it</span>
  <span m="1202700">is</span> <span m="1203025">a</span> <span m="1203350">widely</span>
  <span m="1203680">used</span> <span m="1203850">incremental</span> <span m="1204591">algorithm,</span>
  <span m="1205042">and</span> <span m="1205493">you'll</span> <span m="1205944">see</span>
  <span m="1206395">it's</span> <span m="1206850">quite</span> <span m="1207060">efficient
  in</span> <span m="1207990">what</span> <span m="1208140">it</span> <span m="1208250">does.</span></p><p><span
  m="1209180">D*</span> <span m="1209510">Lite</span> <span m="1209890">is</span>
  <span m="1210130">an</span> <span m="1210310">algorithm</span> <span m="1210590">that</span>
  <span m="1210710">searches</span> <span m="1211430">from</span> <span m="1211670">a</span>
  <span m="1211810">single</span> <span m="1212180">start</span> <span m="1212440">node</span>
  <span m="1212690">to</span> <span m="1212890">a</span> <span m="1212960">single</span>
  <span m="1213320">goal</span> <span m="1213510">node.</span> <span m="1214480">But</span>
  <span m="1214640">as</span> <span m="1214820">we</span> <span m="1215240">see</span>
  <span m="1215510">changes</span> <span m="1216080">occur</span> <span m="1216280">in
  the path</span> <span m="1216640">along</span> <span m="1216995">the</span> <span
  m="1217350">way,</span> <span m="1217950">we'll</span> <span m="1218180">adjust</span>
  <span m="1218500">that.</span> <span m="1220020">So</span> <span m="1220100">it's</span>
  <span m="1220250">nice</span> <span m="1220820">to</span> <span m="1221030">think</span>
  <span m="1221480">about</span> <span m="1221880">D*</span> <span m="1222340">Lite</span>
  <span m="1222620">from</span> <span m="1222890">two</span> <span m="1223100">perspectives.</span>
  <span m="1224370">One</span> <span m="1224480">is</span> <span m="1224600">to</span>
  <span m="1224690">think</span> <span m="1224900">about</span> <span m="1225220">it</span>
  <span m="1225430">as</span> <span m="1225680">a</span> <span m="1225770">modification</span>
  <span m="1226260">of</span> <span m="1226370">the</span> <span m="1226440">principle</span>
  <span m="1226860">space.</span></p><p><span m="1228170">Now,</span> <span m="1228590">you'll</span>
  <span m="1228740">see</span> <span m="1229010">that</span> <span m="1229110">D*</span>
  <span m="1229280">Lite</span> <span m="1229770">in its</span> <span m="1229910">first</span>
  <span m="1230240">iteration</span> <span m="1230500">or</span> <span m="1230760">its</span>
  <span m="1230910">first</span> <span m="1231200">run</span> <span m="1231480">through</span>
  <span m="1231770">before</span> <span m="1232040">any modifications</span> <span
  m="1233210">behaves</span> <span m="1233560">very</span> <span m="1233750">similar</span>
  <span m="1234045">to</span> <span m="1234340">A*,</span> <span m="1234950">and</span>
  <span m="1235040">that's</span> <span m="1235220">where</span> <span m="1235340">it's</span>
  <span m="1235490">nice</span> <span m="1235790">to</span> <span m="1235950">keep</span>
  <span m="1236180">that</span> <span m="1236480">main model in mind.</span> <span
  m="1237510">And</span> <span m="1237610">you'll</span> <span m="1237620">see</span>
  <span m="1237770">that</span> <span m="1237950">in an example</span> <span m="1238220">further</span>
  <span m="1238910">along.</span></p><p><span m="1241040">The</span> <span m="1241355">second</span>
  <span m="1241670">perspective</span> <span m="1242640">to look</span> <span m="1242800">at</span>
  <span m="1242940">A*</span> <span m="1243680">is</span> <span m="1243920">from</span>
  <span m="1244070">the</span> <span m="1244130">perspective</span> <span m="1244730">of</span>
  <span m="1245220">Dijkstra's</span> <span m="1245590">algorithm,</span> <span m="1247040">from</span>
  <span m="1247190">which</span> <span m="1247370">we</span> <span m="1247460">see</span>
  <span m="1247610">many of the</span> <span m="1247970">principles</span> <span m="1248590">of</span>
  <span m="1248720">relaxation</span> <span m="1249560">that we covered</span> <span
  m="1250170">beforehand.</span> <span m="1251690">From</span> <span m="1251900">this</span>
  <span m="1252080">perspective,</span> <span m="1252900">we</span> <span m="1252950">see</span>
  <span m="1253160">that</span> <span m="1253330">when</span> <span m="1253410">we</span>
  <span m="1253510">do reparations</span> <span m="1254600">to</span> <span m="1254760">the</span>
  <span m="1254860">graph</span> <span m="1255560">or</span> <span m="1255680">changes</span>
  <span m="1256240">to</span> <span m="1256570">the graph,</span> <span m="1257200">our</span>
  <span m="1257680">methods</span> <span m="1258250">of</span> <span m="1258590">repairs
  the</span> <span m="1258830">graph</span> <span m="1259610">is</span> <span m="1259730">essentially</span>
  <span m="1260120">to</span> <span m="1260210">relax</span> <span m="1260810">down</span>
  <span m="1261240">our</span> <span m="1261400">changed</span> <span m="1261780">edge</span>
  <span m="1262000">weights</span> <span m="1262340">until</span> <span m="1262610">they</span>
  <span m="1262760">reach</span> <span m="1263000">their</span> <span m="1263180">truth.</span></p><p><span
  m="1264080">Now,</span> <span m="1264200">where</span> <span m="1264410">we</span>
  <span m="1264560">differ</span> <span m="1264950">from</span> <span m="1265100">Dijkstra's</span>
  <span m="1265520">algorithm</span> <span m="1266320">with</span> <span m="1266510">something</span>
  <span m="1266820">like</span> <span m="1267080">D*</span> <span m="1267170">Lite</span>
  <span m="1267470">is</span> <span m="1268130">selecting</span> <span m="1269150">only</span>
  <span m="1270050">the</span> <span m="1270500">nodes</span> <span m="1270890">that</span>
  <span m="1271010">we</span> <span m="1271130">want</span> <span m="1271280">to</span>
  <span m="1271400">hit</span> <span m="1271670">efficiently.</span> <span m="1272570">So</span>
  <span m="1273320">whereas</span> <span m="1273800">Dijkstra's</span> <span m="1274460">algorithm</span>
  <span m="1275950">tried</span> <span m="1276390">to fit</span> <span m="1276775">the
  entire graph,</span> <span m="1277160">we</span> <span m="1277320">only</span> <span
  m="1277550">want</span> <span m="1277760">to</span> <span m="1278210">travel</span>
  <span m="1278890">from</span> <span m="1279220">a</span> <span m="1279260">single</span>
  <span m="1279590">start</span> <span m="1279830">node</span> <span m="1280250">to
  a single</span> <span m="1280655">goal</span> <span m="1281060">node.</span> <span
  m="1281750">And</span> <span m="1282170">so D*</span> <span m="1282290">Lite</span>
  <span m="1282560">behaves</span> <span m="1283130">like</span> <span m="1283400">Dijkstra's,</span>
  <span m="1283930">but</span> <span m="1284185">a</span> <span m="1284440">guided</span>
  <span m="1284860">Dijkstra's.</span></p><p><span m="1286970">So</span> <span m="1287650">I'd</span>
  <span m="1287750">like</span> <span m="1287900">to</span> <span m="1288020">just</span>
  <span m="1288260">remind</span> <span m="1288740">you</span> <span m="1288860">of</span>
  <span m="1288950">several</span> <span m="1289300">concepts</span> <span m="1289730">from</span>
  <span m="1289870">A*</span> <span m="1290400">first,</span> <span m="1290840">because</span>
  <span m="1291020">it's</span> <span m="1291140">easier</span> <span m="1291390">to</span>
  <span m="1291520">introduce</span> <span m="1291890">them</span> <span m="1292010">in</span>
  <span m="1292070">that</span> <span m="1292220">context.</span> <span m="1292950">And</span>
  <span m="1293050">then</span> <span m="1293150">we'll</span> <span m="1293180">modify</span>
  <span m="1293885">them a little bit.</span> <span m="1295070">So</span> <span m="1295920">Joe</span>
  <span m="1296230">mentioned</span> <span m="1296560">before</span> <span m="1297040">that
  for</span> <span m="1297370">A*,</span> <span m="1298340">we're</span> <span m="1298490">searching</span>
  <span m="1298940">from</span> <span m="1299180">a</span> <span m="1299570">start
  node</span> <span m="1299840">to</span> <span m="1300300">a</span> <span m="1300656">goal</span>
  <span m="1301012">node.</span> <span m="1301370">We're</span> <span m="1301460">sorting</span>
  <span m="1301940">the</span> <span m="1302090">nodes</span> <span m="1302510">in
  our</span> <span m="1302870">queue</span> <span m="1303380">by</span> <span m="1303650">total</span>
  <span m="1304070">cost,</span> <span m="1304400">which</span> <span m="1304550">is</span>
  <span m="1304640">the</span> <span m="1304740">sum</span> <span m="1305140">of</span>
  <span m="1305410">what</span> <span m="1305570">we're</span> <span m="1305730">calling</span>
  <span m="1306030">g,</span> <span m="1306680">which</span> <span m="1307130">are</span>
  <span m="1308600">costs</span> <span m="1309010">to</span> <span m="1309080">get</span>
  <span m="1309320">to</span> <span m="1309790">a</span> <span m="1310080">single</span>
  <span m="1310240">node,</span> <span m="1310495">and our</span> <span m="1310750">heuristic,</span>
  <span m="1311670">which</span> <span m="1312010">is</span> <span m="1312230">the</span>
  <span m="1312410">cost</span> <span m="1312710">to</span> <span m="1312770">get</span>
  <span m="1312980">from</span> <span m="1313160">a</span> <span m="1313220">node,</span>
  <span m="1313640">s,</span> <span m="1313910">to</span> <span m="1314100">the</span>
  <span m="1314500">goal</span> <span m="1314900">node,</span> <span m="1315090">your
  s.</span></p><p><span m="1318740">Now,</span> <span m="1319220">what we</span> <span
  m="1319310">don't</span> <span m="1319700">usually</span> <span m="1320210">consider</span>
  <span m="1320860">with</span> <span m="1321170">A*,</span> <span m="1321320">but</span>
  <span m="1321600">is</span> <span m="1322040">very</span> <span m="1322340">important</span>
  <span m="1322700">for</span> <span m="1322820">D*,</span> <span m="1323260">is how</span>
  <span m="1323470">to</span> <span m="1323540">distinguish</span> <span m="1324290">between</span>
  <span m="1324740">ties</span> <span m="1325580">when</span> <span m="1325730">two</span>
  <span m="1325940">different</span> <span m="1326230">nodes</span> <span m="1326570">on</span>
  <span m="1326820">the</span> <span m="1326870">search</span> <span m="1327125">cube</span>
  <span m="1327800">have</span> <span m="1327980">the</span> <span m="1328070">same</span>
  <span m="1328490">total</span> <span m="1328880">cost.</span> <span m="1329940">So</span>
  <span m="1329990">here's</span> <span m="1330300">what</span> <span m="1330390">we're</span>
  <span m="1330470">doing</span> <span m="1330980">is</span> <span m="1331070">we're</span>
  <span m="1331250">introducing</span> <span m="1332010">a</span> <span m="1332150">couplet,</span>
  <span m="1333210">which</span> <span m="1333280">consists</span> <span m="1333560">of</span>
  <span m="1333650">two</span> <span m="1333950">values.</span> <span m="1334770">The</span>
  <span m="1334790">first,</span> <span m="1335350">which</span> <span m="1335500">I'm</span>
  <span m="1335630">calling</span> <span m="1335840">f1</span> <span m="1336380">here</span>
  <span m="1336740">for</span> <span m="1336970">any</span> <span m="1337080">given</span>
  <span m="1337420">state,</span> <span m="1337940">is</span> <span m="1338120">the</span>
  <span m="1338210">same</span> <span m="1338810">as</span> <span m="1338900">what</span>
  <span m="1339050">we're</span> <span m="1339200">usually</span> <span m="1339640">used</span>
  <span m="1339860">to.</span> <span m="1340370">It's</span> <span m="1340490">the</span>
  <span m="1340550">linear</span> <span m="1340850">combination</span> <span m="1341600">of</span>
  <span m="1341780">your</span> <span m="1342080">cost</span> <span m="1342500">to</span>
  <span m="1342780">reach</span> <span m="1343175">the goal node</span> <span m="1343570">and</span>
  <span m="1343850">heuristic</span> <span m="1344080">function.</span></p><p><span
  m="1345000">But</span> <span m="1345740">we</span> <span m="1345890">also</span>
  <span m="1346220">introduced</span> <span m="1346610">a</span> <span m="1346700">second</span>
  <span m="1347900">value</span> <span m="1348770">for</span> <span m="1348920">this</span>
  <span m="1349070">couplet</span> <span m="1349430">that's</span> <span m="1349640">used</span>
  <span m="1349940">in</span> <span m="1350030">the</span> <span m="1350120">case</span>
  <span m="1350380">for</span> <span m="1350530">only</span> <span m="1350870">those</span>
  <span m="1351140">to</span> <span m="1351350">draw.</span> <span m="1352250">And</span>
  <span m="1352370">that</span> <span m="1352520">is</span> <span m="1352580">simply</span>
  <span m="1353300">the</span> <span m="1353350">cost</span> <span m="1353750">to</span>
  <span m="1353840">go,</span> <span m="1354180">that g</span> <span m="1354580">value.</span>
  <span m="1355290">So the</span> <span m="1355640">order</span> <span m="1355980">of</span>
  <span m="1356060">expansion</span> <span m="1356660">of</span> <span m="1356820">nodes</span>
  <span m="1357110">from</span> <span m="1357480">the</span> <span m="1357830">q</span>
  <span m="1358155">will</span> <span m="1358480">order</span> <span m="1358710">them</span>
  <span m="1359180">in</span> <span m="1359330">terms</span> <span m="1359810">of</span>
  <span m="1360400">f1</span> <span m="1361040">first,</span> <span m="1361880">and</span>
  <span m="1361970">if</span> <span m="1362120">two</span> <span m="1362260">nodes</span>
  <span m="1362500">at</span> <span m="1362910">the</span> <span m="1363030">front
  of</span> <span m="1363410">the</span> <span m="1363690">cube</span> <span m="1364050">tie</span>
  <span m="1364335">in</span> <span m="1364620">terms</span> <span m="1364790">of
  their</span> <span m="1365060">f1</span> <span m="1365270">value,</span> <span m="1365970">we</span>
  <span m="1366120">select</span> <span m="1366490">the</span> <span m="1366720">node</span>
  <span m="1367250">with</span> <span m="1367370">the</span> <span m="1367460">lowest</span>
  <span m="1367785">g value.</span></p><p><span m="1369110">So</span> <span m="1370040">looking</span>
  <span m="1370310">at</span> <span m="1370370">our</span> <span m="1370530">graph</span>
  <span m="1370850">down</span> <span m="1371150">here,</span> <span m="1372200">we're</span>
  <span m="1372350">looking</span> <span m="1372710">at</span> <span m="1372970">our</span>
  <span m="1373130">states</span> <span m="1373480">s1</span> <span m="1374170">here</span>
  <span m="1374815">and</span> <span m="1375130">s2</span> <span m="1375420">here.</span>
  <span m="1376250">Can</span> <span m="1376370">anyone</span> <span m="1376700">tell</span>
  <span m="1376910">me</span> <span m="1377060">the</span> <span m="1377180">total</span>
  <span m="1378050">cost</span> <span m="1378800">for our</span> <span m="1379970">node</span>
  <span m="1380480">s1</span> <span m="1381350">which,</span> <span m="1381500">remember,</span>
  <span m="1381890">is</span> <span m="1382040">a</span> <span m="1382100">couplet</span>
  <span m="1382410">of</span> <span m="1382490">two</span> <span m="1383240">different</span>
  <span m="1383510">values?</span></p><p><span m="1391230">5,</span> <span m="1391620">3.</span>
  <span m="1393220">So</span> <span m="1394340">five,</span> <span m="1394780">yes,</span>
  <span m="1395310">is</span> <span m="1395440">our</span> <span m="1395560">cost</span>
  <span m="1395860">to</span> <span m="1396010">reach</span> <span m="1396790">this</span>
  <span m="1398070">node</span> <span m="1398410">one,</span> <span m="1398980">plus</span>
  <span m="1399220">the</span> <span m="1399550">heuristic,</span> <span m="1399900">which</span>
  <span m="1400080">is</span> <span m="1400220">2</span> <span m="1400510">here.</span>
  <span m="1401170">And also,</span> <span m="1401770">3</span> <span m="1402170">is</span>
  <span m="1402360">our</span> <span m="1402560">second value,</span> <span m="1403360">because</span>
  <span m="1403510">it's</span> <span m="1403660">only our</span> <span m="1403970">g</span>
  <span m="1404387">value</span> <span m="1404804">there.</span> <span m="1405640">And</span>
  <span m="1405730">so</span> <span m="1406090">what</span> <span m="1406430">would</span>
  <span m="1406550">the</span> <span m="1406970">value</span> <span m="1407300">be
  by the</span> <span m="1407605">same</span> <span m="1407910">logic</span> <span
  m="1408110">for</span> <span m="1408280">s2</span> <span m="1408470">down here?</span></p><p><span
  m="1410960">AUDIENCE:</span> <span m="1411209">5,</span> <span m="1411458">2.</span></p><p><span
  m="1412460">BEN AYTON:</span> <span m="1412526">5,</span> <span m="1412592">2.</span>
  <span m="1412660">That's</span> <span m="1412770">exactly</span> <span m="1413250">right.</span>
  <span m="1415050">And</span> <span m="1415150">so,</span> <span m="1415690">bearing</span>
  <span m="1416020">in</span> <span m="1416110">mind</span> <span m="1416380">what</span>
  <span m="1416570">I told you</span> <span m="1416860">before,</span> <span m="1417540">where
  should we</span> <span m="1417700">take</span> <span m="1417950">off</span> <span
  m="1418270">the q</span> <span m="1418570">first?</span></p><p><span m="1420852">AUDIENCE:</span>
  <span m="1421081">S2?</span></p><p><span m="1422230">BEN AYTON:</span> <span m="1422320">That's</span>
  <span m="1422410">exactly right,</span> <span m="1423150">because</span> <span m="1423750">the</span>
  <span m="1423870">first</span> <span m="1424190">value,</span> <span m="1424550">f1,</span>
  <span m="1425260">for these</span> <span m="1425330">two</span> <span m="1425550">nodes</span>
  <span m="1425670">is</span> <span m="1425970">exactly</span> <span m="1426530">the</span>
  <span m="1426640">same.</span> <span m="1427060">But the</span> <span m="1427350">second</span>
  <span m="1427640">value</span> <span m="1428220">is</span> <span m="1428450">lower</span>
  <span m="1429030">is</span> <span m="1429440">f(s)2.</span></p><p><span m="1432210">I'd</span>
  <span m="1432300">also</span> <span m="1432540">like</span> <span m="1432660">to</span>
  <span m="1432780">introduce</span> <span m="1433200">the</span> <span m="1433320">concept</span>
  <span m="1434250">of</span> <span m="1434460">successors</span> <span m="1435230">and</span>
  <span m="1435390">predecessors</span> <span m="1435765">of</span> <span m="1436140">any
  given</span> <span m="1436590">node.</span> <span m="1438390">In</span> <span m="1438540">general,</span>
  <span m="1439210">a</span> <span m="1439610">graph</span> <span m="1439980">consists</span>
  <span m="1440100">of directed</span> <span m="1440280">edges.</span> <span m="1441210">And</span>
  <span m="1441465">we</span> <span m="1441720">could</span> <span m="1441870">have</span>
  <span m="1442080">a graph with</span> <span m="1442440">undirected</span> <span
  m="1442790">edges,</span> <span m="1443070">but</span> <span m="1443370">we</span>
  <span m="1443490">can</span> <span m="1443640">think</span> <span m="1443940">of</span>
  <span m="1444350">as</span> <span m="1444600">just</span> <span m="1444840">any
  edge</span> <span m="1445590">being</span> <span m="1445890">directed</span> <span
  m="1446195">in</span> <span m="1446500">both</span> <span m="1446750">direction.</span>
  <span m="1447960">So</span> <span m="1448110">here,</span> <span m="1448230">we</span>
  <span m="1448330">define</span> <span m="1448640">the</span> <span m="1448740">concept</span>
  <span m="1449160">of</span> <span m="1449250">a</span> <span m="1449340">successor</span>
  <span m="1450030">of</span> <span m="1450160">a</span> <span m="1450270">node,</span>
  <span m="1450900">which</span> <span m="1451080">is</span> <span m="1451330">every</span>
  <span m="1451630">node</span> <span m="1451890">can</span> <span m="1452070">be</span>
  <span m="1452310">reached</span> <span m="1452970">from</span> <span m="1453590">a
  given</span> <span m="1453940">node,</span> <span m="1454290">along</span> <span
  m="1455460">edges</span> <span m="1455810">that can</span> <span m="1456110">be</span>
  <span m="1456550">found.</span></p><p><span m="1457430">So</span> <span m="1457650">the</span>
  <span m="1457950">successors</span> <span m="1458220">of</span> <span m="1458490">this</span>
  <span m="1458620">given</span> <span m="1458840">red</span> <span m="1459040">node</span>
  <span m="1459200">are</span> <span m="1459680">these</span> <span m="1459930">two</span>
  <span m="1460300">blue</span> <span m="1460580">nodes</span> <span m="1460800">here.</span>
  <span m="1462770">We</span> <span m="1462990">also</span> <span m="1463320">introduced</span>
  <span m="1463740">the</span> <span m="1463820">concept</span> <span m="1464150">of</span>
  <span m="1464250">predecessors,</span> <span m="1465600">which</span> <span m="1465780">is</span>
  <span m="1465920">every</span> <span m="1466140">node</span> <span m="1466450">from</span>
  <span m="1466740">which</span> <span m="1467100">that</span> <span m="1467340">node</span>
  <span m="1467670">can</span> <span m="1468010">be</span> <span m="1468190">reached,</span>
  <span m="1468990">meaning</span> <span m="1469570">nodes</span> <span m="1469920">from</span>
  <span m="1470100">which</span> <span m="1470250">we</span> <span m="1470310">can</span>
  <span m="1470460">follow</span> <span m="1470820">our</span> <span m="1470910">directed</span>
  <span m="1471320">edge</span> <span m="1471930">to</span> <span m="1472220">our</span>
  <span m="1472450">node.</span> <span m="1473170">So</span> <span m="1473470">for</span>
  <span m="1473830">our</span> <span m="1474060">red node,</span> <span m="1474310">the</span>
  <span m="1474520">predecessors</span> <span m="1475690">are</span> <span m="1475900">these</span>
  <span m="1476050">two</span> <span m="1476550">nodes.</span></p><p><span m="1477260">What</span>
  <span m="1477400">I'd</span> <span m="1477490">like</span> <span m="1478110">to</span>
  <span m="1478210">emphasize</span> <span m="1478650">here</span> <span m="1478800">is</span>
  <span m="1478920">comparing</span> <span m="1479470">the</span> <span m="1479560">two,</span>
  <span m="1480180">that</span> <span m="1480400">this</span> <span m="1480770">node</span>
  <span m="1481020">here</span> <span m="1481500">was</span> <span m="1481710">both</span>
  <span m="1481950">the</span> <span m="1482040">processor</span> <span m="1482760">and</span>
  <span m="1482940">the</span> <span m="1483030">successor</span> <span m="1483720">of</span>
  <span m="1484190">our</span> <span m="1484550">red node.</span> <span m="1485120">And</span>
  <span m="1485490">that's</span> <span m="1485670">fine.</span> <span m="1486395">That
  occurs when we</span> <span m="1487560">have</span> <span m="1488080">undirected</span>
  <span m="1488350">edges</span> <span m="1488970">or</span> <span m="1489190">edges</span>
  <span m="1489460">that</span> <span m="1489730">direct</span> <span m="1490050">in
  both</span> <span m="1490546">directions.</span></p><p><span m="1493030">So</span>
  <span m="1493140">think about</span> <span m="1493430">D*</span> <span m="1493720">Lite</span>
  <span m="1495010">in</span> <span m="1495100">the</span> <span m="1495190">sense</span>
  <span m="1495490">that</span> <span m="1495640">is</span> <span m="1495880">a</span>
  <span m="1496270">repeated</span> <span m="1496660">best-first</span> <span m="1497290">search,</span>
  <span m="1497790">which</span> <span m="1497980">is</span> <span m="1498220">where
  the</span> <span m="1498340">A*</span> <span m="1498650">principles</span> <span
  m="1499120">come</span> <span m="1499370">in</span> <span m="1499510">through</span>
  <span m="1499870">a</span> <span m="1500230">graph</span> <span m="1501130">with</span>
  <span m="1501370">changing</span> <span m="1501930">edge</span> <span m="1502530">weights</span>
  <span m="1502880">as</span> <span m="1503215">that</span> <span m="1503550">graph
  is</span> <span m="1503970">traversed,</span> <span m="1504850">meaning</span> <span
  m="1505330">that</span> <span m="1505600">as</span> <span m="1505810">we</span>
  <span m="1505960">travel</span> <span m="1506305">from our</span> <span m="1506650">start</span>
  <span m="1507070">node</span> <span m="1507280">to</span> <span m="1507565">our
  goal</span> <span m="1507850">node</span> <span m="1508600">along</span> <span m="1509920">a</span>
  <span m="1509980">path</span> <span m="1510310">that</span> <span m="1510430">we</span>
  <span m="1510620">are</span> <span m="1510680">planning,</span> <span m="1511780">we</span>
  <span m="1511870">can</span> <span m="1512020">see</span> <span m="1512260">that</span>
  <span m="1512380">edge</span> <span m="1512650">weights</span> <span m="1513030">are</span>
  <span m="1513290">changing.</span></p><p><span m="1514060">And</span> <span m="1514150">in</span>
  <span m="1514240">this</span> <span m="1514420">example,</span> <span m="1514970">I'm</span>
  <span m="1515200">modeling</span> <span m="1515430">an</span> <span m="1515710">obstacle</span>
  <span m="1517120">coming</span> <span m="1517360">in</span> <span m="1517480">place</span>
  <span m="1517940">between</span> <span m="1518290">this</span> <span m="1518460">node</span>
  <span m="1518720">here</span> <span m="1519070">and the goal,</span> <span m="1520060">which</span>
  <span m="1520210">means</span> <span m="1520540">that</span> <span m="1520700">we</span>
  <span m="1520840">have</span> <span m="1520990">removed</span> <span m="1521500">that</span>
  <span m="1521740">edge.</span> <span m="1522500">And</span> <span m="1522610">that's</span>
  <span m="1522770">effectively</span> <span m="1523360">the</span> <span m="1523450">same</span>
  <span m="1524170">as</span> <span m="1524260">changing</span> <span m="1524660">an</span>
  <span m="1524760">edge</span> <span m="1524980">weight.</span> <span m="1525400">We're</span>
  <span m="1525610">just</span> <span m="1525800">modeling</span> <span m="1526380">it</span>
  <span m="1526690">as</span> <span m="1526840">changing</span> <span m="1527290">this</span>
  <span m="1527440">edge weight to</span> <span m="1527540">infinity,</span> <span
  m="1528730">which</span> <span m="1528880">means</span> <span m="1529360">that</span>
  <span m="1529540">edge</span> <span m="1529825">can't</span> <span m="1530110">be</span>
  <span m="1530500">traveled along.</span></p><p><span m="1531796">And</span> <span
  m="1532230">as</span> <span m="1532480">I</span> <span m="1532540">mentioned</span>
  <span m="1532810">before,</span> <span m="1533250">we</span> <span m="1533380">also</span>
  <span m="1533820">view</span> <span m="1534010">this as</span> <span m="1534170">replanning</span>
  <span m="1534940">through</span> <span m="1535210">relaxation</span> <span m="1535600">of
  path</span> <span m="1535990">costs.</span> <span m="1537470">So</span> <span m="1537550">once</span>
  <span m="1537790">we</span> <span m="1537920">have</span> <span m="1538000">moved</span>
  <span m="1538300">to</span> <span m="1538420">this</span> <span m="1538660">point,</span>
  <span m="1539570">how</span> <span m="1539800">do</span> <span m="1539890">we</span>
  <span m="1540130">find</span> <span m="1540700">the</span> <span m="1540790">path</span>
  <span m="1541120">from</span> <span m="1541330">here</span> <span m="1541630">to</span>
  <span m="1541750">here</span> <span m="1542790">when</span> <span m="1543040">this</span>
  <span m="1543830">edge</span> <span m="1544030">has</span> <span m="1544490">been
  removed,</span> <span m="1545530">essentially?</span></p><p><span m="1548690">So</span>
  <span m="1549470">we</span> <span m="1549680">want</span> <span m="1549890">to</span>
  <span m="1549980">make</span> <span m="1550400">D*</span> <span m="1550670">Lite</span>
  <span m="1551050">efficient.</span> <span m="1551750">And</span> <span m="1551840">it's</span>
  <span m="1551960">a</span> <span m="1552230">repeated</span> <span m="1552500">search</span>
  <span m="1552890">through</span> <span m="1553180">the</span> <span m="1553290">graph</span>
  <span m="1554060">as</span> <span m="1554240">we</span> <span m="1554360">traverse</span>
  <span m="1554850">it.</span> <span m="1555800">So</span> <span m="1556280">you'll</span>
  <span m="1556460">see</span> <span m="1556940">that</span> <span m="1557120">since</span>
  <span m="1557390">we're</span> <span m="1557660">using</span> <span m="1558170">these</span>
  <span m="1558410">g</span> <span m="1558720">values,</span> <span m="1560140">if</span>
  <span m="1560300">we</span> <span m="1560830">maintain</span> <span m="1563285">a</span>
  <span m="1563540">formulation</span> <span m="1563940">where</span> <span m="1564640">we're</span>
  <span m="1564950">measuring</span> <span m="1565640">the</span> <span m="1565790">distance</span>
  <span m="1566510">to</span> <span m="1566690">go</span> <span m="1567170">or</span>
  <span m="1568120">to</span> <span m="1568370">reach</span> <span m="1568650">a</span>
  <span m="1568760">node</span> <span m="1568980">from</span> <span m="1569330">our</span>
  <span m="1569450">start</span> <span m="1569810">node,</span> <span m="1570320">this</span>
  <span m="1570470">is</span> <span m="1570560">not</span> <span m="1570800">preserved</span>
  <span m="1571460">when</span> <span m="1571610">we</span> <span m="1571760">move</span>
  <span m="1572360">our</span> <span m="1572480">start</span> <span m="1572710">node.</span>
  <span m="1573240">And</span> <span m="1573370">we</span> <span m="1573470">move</span>
  <span m="1573740">our</span> <span m="1573860">start</span> <span m="1574110">node</span>
  <span m="1574280">when we're</span> <span m="1574650">updating</span> <span m="1574975">the</span>
  <span m="1575300">position</span> <span m="1575780">of</span> <span m="1576200">our</span>
  <span m="1576620">vehicle.</span></p><p><span m="1577040">So</span> <span m="1577370">let
  me show this</span> <span m="1577560">through</span> <span m="1578210">an</span>
  <span m="1578300">example</span> <span m="1578840">here.</span> <span m="1579800">The</span>
  <span m="1580055">g</span> <span m="1580310">value, or</span> <span m="1580790">cost</span>
  <span m="1581110">to</span> <span m="1581210">get</span> <span m="1581450">from</span>
  <span m="1581630">one</span> <span m="1581750">start</span> <span m="1582170">node</span>
  <span m="1582860">to</span> <span m="1583250">our</span> <span m="1583440">current</span>
  <span m="1583820">node, s,</span> <span m="1584240">here</span> <span m="1584690">is</span>
  <span m="1584780">the</span> <span m="1584840">combination</span> <span m="1585380">of</span>
  <span m="1585440">these</span> <span m="1585680">two</span> <span m="1585890">edges.</span>
  <span m="1586460">And</span> <span m="1586550">so,</span> <span m="1586760">it sums
  to</span> <span m="1587110">4.</span> <span m="1588030">Now</span> <span m="1588510">when
  we move</span> <span m="1588910">along</span> <span m="1589130">that</span> <span
  m="1589590">path</span> <span m="1590350">that we've</span> <span m="1590750">planned</span>
  <span m="1591260">to</span> <span m="1591410">this</span> <span m="1591590">next</span>
  <span m="1591920">node,</span> <span m="1592150">the</span> <span m="1592410">g
  value</span> <span m="1593270">to</span> <span m="1593390">get</span> <span m="1593570">to</span>
  <span m="1593870">that</span> <span m="1594050">same</span> <span m="1594540">node</span>
  <span m="1595340">is</span> <span m="1595460">here</span> <span m="1595790">too.</span>
  <span m="1596630">So</span> <span m="1596780">this</span> <span m="1596960">isn't</span>
  <span m="1597100">preserved.</span> <span m="1598010">And</span> <span m="1598100">that</span>
  <span m="1598220">means</span> <span m="1598430">that</span> <span m="1598550">we'd</span>
  <span m="1598670">have</span> <span m="1598880">to</span> <span m="1599300">potentially</span>
  <span m="1599600">reformulate</span> <span m="1600320">things</span> <span m="1600650">in
  our</span> <span m="1600950">cue,</span> <span m="1601490">which</span> <span m="1601790">would
  be</span> <span m="1601940">very</span> <span m="1602210">inefficient.</span></p><p><span
  m="1603840">So</span> <span m="1603870">what</span> <span m="1604050">we</span>
  <span m="1604160">do</span> <span m="1604400">is</span> <span m="1604520">we</span>
  <span m="1604670">reformulate</span> <span m="1605540">our</span> <span m="1605690">search.</span>
  <span m="1606230">And it's</span> <span m="1606595">perfectly valid</span> <span
  m="1606960">to</span> <span m="1607280">reformulate</span> <span m="1608430">our</span>
  <span m="1608550">search</span> <span m="1608900">to search</span> <span m="1608960">in
  the</span> <span m="1609110">opposite</span> <span m="1609560">direction.</span>
  <span m="1610460">We're</span> <span m="1610610">essentially</span> <span m="1611120">measuring</span>
  <span m="1612140">for</span> <span m="1612320">our</span> <span m="1612470">g values</span>
  <span m="1613130">now</span> <span m="1613640">the</span> <span m="1613730">cost</span>
  <span m="1614120">to</span> <span m="1614540">reach</span> <span m="1615170">the</span>
  <span m="1615320">goal</span> <span m="1615800">from a</span> <span m="1616210">specific.</span>
  <span m="1616920">And</span> <span m="1617570">instead</span> <span m="1618010">of</span>
  <span m="1618220">heuristics,</span> <span m="1618770">then</span> <span m="1619040">measure</span>
  <span m="1619790">the</span> <span m="1619970">costs</span> <span m="1620660">to</span>
  <span m="1620840">get</span> <span m="1621080">from</span> <span m="1621360">this</span>
  <span m="1621550">specific</span> <span m="1621870">node,</span> <span m="1622330">or</span>
  <span m="1622630">to</span> <span m="1622780">get</span> <span m="1623160">from</span>
  <span m="1623540">the start node</span> <span m="1623950">to our</span> <span m="1624150">specific</span>
  <span m="1624605">node.</span> <span m="1625060">And so we</span> <span m="1625260">search</span>
  <span m="1625670">from</span> <span m="1625840">the</span> <span m="1625990">goal</span>
  <span m="1626440">backwards</span> <span m="1626860">through the graph.</span></p><p><span
  m="1628040">In</span> <span m="1628160">this</span> <span m="1628340">case,</span>
  <span m="1628640">we</span> <span m="1628760">see</span> <span m="1629170">that</span>
  <span m="1629220">regardless</span> <span m="1629800">of whether</span> <span m="1630120">our</span>
  <span m="1630540">start</span> <span m="1630825">node,</span> <span m="1632140">we</span>
  <span m="1632260">preserve</span> <span m="1632950">our</span> <span m="1633030">g
  values,</span> <span m="1633160">and</span> <span m="1633800">our</span> <span m="1633950">cost</span>
  <span m="1634730">to</span> <span m="1634850">travel</span> <span m="1635150">from</span>
  <span m="1635330">s</span> <span m="1635710">to</span> <span m="1635870">that</span>
  <span m="1636276">goal.</span> <span m="1637090">That's what we like,</span> <span
  m="1637620">and</span> <span m="1637640">we</span> <span m="1637760">we'll</span>
  <span m="1638240">keep</span> <span m="1638480">that</span> <span m="1639350">reformulation</span>
  <span m="1640610">to</span> <span m="1640700">maximize</span> <span m="1641150">efficiency.</span>
  <span m="1643490">So</span> <span m="1643590">here,</span> <span m="1643680">I</span>
  <span m="1643710">want</span> <span m="1643820">to</span> <span m="1643880">give</span>
  <span m="1644060">you</span> <span m="1644210">a</span> <span m="1644300">kind</span>
  <span m="1644630">of</span> <span m="1645470">overall</span> <span m="1646010">understanding</span>
  <span m="1646640">of</span> <span m="1646730">the</span> <span m="1646950">D* Lite</span>
  <span m="1647420">algorithm</span> <span m="1647890">before</span> <span m="1648150">we</span>
  <span m="1648600">dive into</span> <span m="1648670">specifics</span> <span m="1649230">of</span>
  <span m="1649370">what</span> <span m="1649510">it's doing.</span></p><p><span m="1650850">First</span>
  <span m="1651210">we want</span> <span m="1651430">to</span> <span m="1651630">initialize</span>
  <span m="1652310">all</span> <span m="1652550">nodes</span> <span m="1652860">as</span>
  <span m="1652980">unexpanded.</span> <span m="1653900">And</span> <span m="1653990">what</span>
  <span m="1654110">exactly,</span> <span m="1654590">it means</span> <span m="1655010">expand</span>
  <span m="1655285">a</span> <span m="1655560">node</span> <span m="1655870">neighbor
  or</span> <span m="1656220">cover.</span> <span m="1657840">And then we're</span>
  <span m="1658250">doing</span> <span m="1658520">a</span> <span m="1658630">best-first</span>
  <span m="1659270">search</span> <span m="1659920">from</span> <span m="1660350">the</span>
  <span m="1660430">goal</span> <span m="1660760">node</span> <span m="1660890">to</span>
  <span m="1661160">the</span> <span m="1661280">start</span> <span m="1661600">node</span>
  <span m="1662210">until</span> <span m="1662480">the</span> <span m="1662540">start</span>
  <span m="1662990">node</span> <span m="1663290">is</span> <span m="1663470">consistent</span>
  <span m="1664070">with</span> <span m="1664190">its</span> <span m="1664340">neighbors.</span>
  <span m="1665410">And I'll</span> <span m="1665870">again</span> <span m="1666110">say</span>
  <span m="1666410">what</span> <span m="1666560">that</span> <span m="1666740">means</span>
  <span m="1667110">later.</span></p><p><span m="1668000">We</span> <span m="1668090">then</span>
  <span m="1668360">move</span> <span m="1668720">our</span> <span m="1668890">start</span>
  <span m="1669190">node</span> <span m="1669390">to</span> <span m="1669650">the</span>
  <span m="1669770">next</span> <span m="1670070">best</span> <span m="1670370">vertex,</span>
  <span m="1671030">essentially</span> <span m="1672170">our</span> <span m="1673000">node</span>
  <span m="1673460">moving</span> <span m="1673730">along</span> <span m="1673970">the</span>
  <span m="1674090">plan</span> <span m="1674480">that</span> <span m="1674660">we</span>
  <span m="1675010">created.</span> <span m="1675580">And</span> <span m="1675740">then</span>
  <span m="1676170">we</span> <span m="1676340">have</span> <span m="1676460">to</span>
  <span m="1676550">see</span> <span m="1676805">if</span> <span m="1677060">any</span>
  <span m="1677300">of</span> <span m="1677390">those</span> <span m="1677540">edge</span>
  <span m="1677760">costs</span> <span m="1678170">change.</span> <span m="1679220">We</span>
  <span m="1679320">track how</span> <span m="1679490">our</span> <span m="1679895">heuristics</span>
  <span m="1680300">change,</span> <span m="1680840">and</span> <span m="1680930">then</span>
  <span m="1681200">update</span> <span m="1681680">the</span> <span m="1681910">source</span>
  <span m="1682530">nodes of</span> <span m="1682770">those</span> <span m="1683000">changed</span>
  <span m="1683300">edges.</span> <span m="1683530">And</span> <span m="1684110">we</span>
  <span m="1684290">essentially</span> <span m="1685130">repeat</span> <span m="1685520">this</span>
  <span m="1685730">process</span> <span m="1686690">until,</span> <span m="1686990">again,</span>
  <span m="1687050">we've</span> <span m="1687620">converged</span> <span m="1688190">to</span>
  <span m="1688340">a</span> <span m="1688400">solution,</span> <span m="1688685">and</span>
  <span m="1689300">we</span> <span m="1689430">keep</span> <span m="1689640">moving.</span></p><p><span
  m="1691890">So</span> <span m="1692120">this</span> <span m="1692290">best-first</span>
  <span m="1692870">search,</span> <span m="1693290">the</span> <span m="1693440">A*</span>
  <span m="1693880">Lite</span> <span m="1694170">part</span> <span m="1694390">of</span>
  <span m="1694580">the</span> <span m="1694700">algorithm,</span> <span m="1695450">is</span>
  <span m="1695630">where</span> <span m="1695910">most</span> <span m="1696200">of
  the</span> <span m="1696610">computation is</span> <span m="1696880">going to be</span>
  <span m="1697150">occurring.</span> <span m="1698840">However,</span> <span m="1700150">the</span>
  <span m="1700370">incremental</span> <span m="1701000">component</span> <span m="1701540">is</span>
  <span m="1701690">actually</span> <span m="1702080">how</span> <span m="1702650">can</span>
  <span m="1702780">we</span> <span m="1703110">adjust</span> <span m="1703770">our</span>
  <span m="1703950">edge</span> <span m="1704160">costs</span> <span m="1705560">to</span>
  <span m="1705680">make</span> <span m="1705890">sure</span> <span m="1706130">that</span>
  <span m="1706290">we're</span> <span m="1706910">using</span> <span m="1707360">most</span>
  <span m="1707660">of</span> <span m="1707720">the</span> <span m="1707840">information</span>
  <span m="1708320">that</span> <span m="1708410">we</span> <span m="1708500">previously</span>
  <span m="1708950">gathered</span> <span m="1709340">as</span> <span m="1709640">efficiently</span>
  <span m="1709850">as</span> <span m="1710090">possible.</span></p><p><span m="1711570">So</span>
  <span m="1711640">I'm</span> <span m="1712090">going to</span> <span m="1712370">walk</span>
  <span m="1712670">you</span> <span m="1712790">through</span> <span m="1713120">various</span>
  <span m="1713450">steps</span> <span m="1713930">of</span> <span m="1713990">this.</span>
  <span m="1714670">First,</span> <span m="1714970">I'd</span> <span m="1715070">like</span>
  <span m="1715180">to</span> <span m="1715310">walk</span> <span m="1715640">you</span>
  <span m="1715760">through</span> <span m="1716450">this</span> <span m="1716630">step
  of</span> <span m="1716990">moving to the</span> <span m="1717710">next</span> <span
  m="1717950">best</span> <span m="1718270">vertex,</span> <span m="1719050">just</span>
  <span m="1719210">so</span> <span m="1719330">you</span> <span m="1719480">understand</span>
  <span m="1720080">that.</span> <span m="1722050">So</span> <span m="1722230">we</span>
  <span m="1722300">can</span> <span m="1722450">extract</span> <span m="1723050">a</span>
  <span m="1723260">path,</span> <span m="1724100">given</span> <span m="1724670">the</span>
  <span m="1725090">path</span> <span m="1725450">costs</span> <span m="1725690">that</span>
  <span m="1726020">have,</span> <span m="1726470">through</span> <span m="1726920">this</span>
  <span m="1727100">simple</span> <span m="1727460">argument,</span> <span m="1728280">which</span>
  <span m="1728530">says</span> <span m="1729140">that</span> <span m="1729330">we</span>
  <span m="1729460">map</span> <span m="1729930">the</span> <span m="1730080">successor,</span>
  <span m="1732080">by</span> <span m="1732260">which</span> <span m="1732470">I</span>
  <span m="1732560">mean</span> <span m="1732800">we</span> <span m="1733430">restate</span>
  <span m="1734690">what</span> <span m="1734920">the</span> <span m="1735070">start</span>
  <span m="1735300">node</span> <span m="1735560">is,</span> <span m="1736670">because</span>
  <span m="1736940">we're</span> <span m="1737060">moving</span> <span m="1737360">from</span>
  <span m="1737540">one</span> <span m="1737690">state</span> <span m="1737960">to</span>
  <span m="1738020">the</span> <span m="1738080">next</span> <span m="1738380">state,</span>
  <span m="1738810">which</span> <span m="1738830">becomes</span> <span m="1739160">the</span>
  <span m="1739250">new</span> <span m="1739600">start</span> <span m="1740130">node,</span>
  <span m="1741200">by</span> <span m="1741410">this</span> <span m="1741620">form,</span>
  <span m="1742310">which</span> <span m="1742430">essentially</span> <span m="1742970">says</span>
  <span m="1743810">that</span> <span m="1744200">we're</span> <span m="1744350">taking</span>
  <span m="1745220">the</span> <span m="1745370">best</span> <span m="1745820">path</span>
  <span m="1746360">in</span> <span m="1746480">the</span> <span m="1746570">sense</span>
  <span m="1746930">that</span> <span m="1747080">we're</span> <span m="1747230">minimizing</span>
  <span m="1748820">the</span> <span m="1748910">total</span> <span m="1749300">cost</span>
  <span m="1751310">that</span> <span m="1751490">would</span> <span m="1751610">be</span>
  <span m="1751730">gained</span> <span m="1752730">traveling</span> <span m="1753380">by</span>
  <span m="1753620">that</span> <span m="1753830">path</span> <span m="1754330">to</span>
  <span m="1754540">this</span> <span m="1754720">node.</span></p><p><span m="1756210">So</span>
  <span m="1756260">in a sense,</span> <span m="1757350">the</span> <span m="1757730">g</span>
  <span m="1757950">value</span> <span m="1758740">to</span> <span m="1758930">get</span>
  <span m="1759260">to</span> <span m="1759510">this</span> <span m="1759910">node,</span>
  <span m="1760940">to</span> <span m="1761180">the</span> <span m="1761360">red</span>
  <span m="1761650">from</span> <span m="1761930">the</span> <span m="1762000">green,</span>
  <span m="1762290">or</span> <span m="1762570">color</span> <span m="1762840">stretching</span>
  <span m="1763190">back</span> <span m="1763520">through</span> <span m="1763700">the</span>
  <span m="1763830">graph,</span> <span m="1765190">by</span> <span m="1765380">this</span>
  <span m="1765750">path here,</span> <span m="1766730">is</span> <span m="1767000">7.</span>
  <span m="1767620">But to</span> <span m="1767750">get</span> <span m="1767910">to</span>
  <span m="1768040">this node</span> <span m="1768710">from</span> <span m="1768950">the</span>
  <span m="1769010">lower</span> <span m="1769400">node</span> <span m="1769786">is</span>
  <span m="1770560">10.</span> <span m="1771310">And</span> <span m="1771440">so our</span>
  <span m="1771760">g</span> <span m="1772040">value</span> <span m="1772880">that</span>
  <span m="1773000">is</span> <span m="1773180">optimal</span> <span m="1773900">is</span>
  <span m="1774060">7</span> <span m="1774430">in</span> <span m="1774590">this</span>
  <span m="1774740">case,</span> <span m="1775130">and</span> <span m="1775680">know
  that we</span> <span m="1775970">pick the</span> <span m="1776600">successor</span>
  <span m="1777470">as</span> <span m="1777600">the</span> <span m="1778060">green
  node up here.</span></p><p><span m="1781240">So</span> <span m="1782000">now</span>
  <span m="1782240">to</span> <span m="1782330">walk</span> <span m="1782570">through</span>
  <span m="1782750">some</span> <span m="1782960">principles</span> <span m="1784190">that
  appear</span> <span m="1784520">in</span> <span m="1784860">both</span> <span m="1785060">of</span>
  <span m="1785150">these</span> <span m="1785330">steps.</span> <span m="1788210">I</span>
  <span m="1788270">want</span> <span m="1788420">to</span> <span m="1788510">show</span>
  <span m="1788810">how</span> <span m="1789230">we</span> <span m="1789440">handle</span>
  <span m="1789770">weight</span> <span m="1789980">changes</span> <span m="1790430">locally.</span>
  <span m="1791250">And</span> <span m="1791380">we</span> <span m="1791510">do</span>
  <span m="1791710">this</span> <span m="1792000">because</span> <span m="1792200">we</span>
  <span m="1792300">don't</span> <span m="1792430">want</span> <span m="1792550">to</span>
  <span m="1792620">track</span> <span m="1792875">weight</span> <span m="1793130">changes</span>
  <span m="1793260">throughout</span> <span m="1793760">the</span> <span m="1793890">entire</span>
  <span m="1794185">graph.</span> <span m="1794710">We</span> <span m="1795010">want
  to</span> <span m="1795270">handle</span> <span m="1795480">this</span> <span m="1795610">efficiently</span>
  <span m="1796090">and</span> <span m="1796260">separate</span> <span m="1796910">them,</span>
  <span m="1797180">so</span> <span m="1797360">we</span> <span m="1797450">only</span>
  <span m="1797520">need</span> <span m="1797670">to</span> <span m="1797810">handle</span>
  <span m="1798170">the</span> <span m="1798290">changes</span> <span m="1799050">that</span>
  <span m="1799280">really</span> <span m="1799670">impact our</span> <span m="1800130">problem.</span></p><p><span
  m="1801380">So</span> <span m="1801470">this</span> <span m="1801650">is</span>
  <span m="1801740">the</span> <span m="1801830">same</span> <span m="1802130">formula</span>
  <span m="1802580">that</span> <span m="1802700">defines</span> <span m="1803210">our
  successor,</span> <span m="1803890">or</span> <span m="1804230">our</span> <span
  m="1804480">g</span> <span m="1804740">values</span> <span m="1805150">for</span>
  <span m="1805370">a</span> <span m="1805570">given</span> <span m="1805850">node.</span>
  <span m="1807450">But</span> <span m="1807560">we</span> <span m="1807690">can</span>
  <span m="1807800">see</span> <span m="1808160">that this</span> <span m="1808360">may</span>
  <span m="1808610">no</span> <span m="1808820">longer</span> <span m="1809210">hold</span>
  <span m="1809820">when</span> <span m="1809980">edge</span> <span m="1810230">weights</span>
  <span m="1810560">change.</span> <span m="1810815">The</span> <span m="1811570">example</span>
  <span m="1812090">that</span> <span m="1812240">I</span> <span m="1812330">have</span>
  <span m="1812600">here</span> <span m="1813020">is</span> <span m="1813140">that</span>
  <span m="1813230">I've</span> <span m="1813350">changed</span> <span m="1813890">edge</span>
  <span m="1814140">weight</span> <span m="1814610">cost</span> <span m="1815330">from</span>
  <span m="1815540">6</span> <span m="1816800">to</span> <span m="1817040">1.</span>
  <span m="1818120">And</span> <span m="1818300">so</span> <span m="1818630">now</span>
  <span m="1818940">we</span> <span m="1819080">can</span> <span m="1819260">reach</span>
  <span m="1819600">the</span> <span m="1819740">red</span> <span m="1820190">node,</span>
  <span m="1820670">searching</span> <span m="1821030">back</span> <span m="1821420">through</span>
  <span m="1821550">graph</span> <span m="1822040">by a</span> <span m="1822230">new</span>
  <span m="1822410">optimal</span> <span m="1822770">path,</span> <span m="1823090">coming</span>
  <span m="1823670">down</span> <span m="1823880">from</span> <span m="1824090">this</span>
  <span m="1824300">node</span> <span m="1824570">here,</span> <span m="1825260">which</span>
  <span m="1825440">would</span> <span m="1825570">make</span> <span m="1826260">our</span>
  <span m="1826410">new g value five</span> <span m="1827230">instead.</span></p><p><span
  m="1828710">So</span> <span m="1830340">this</span> <span m="1830480">hasn't</span>
  <span m="1830710">been</span> <span m="1830870">preserved.</span> <span m="1833450">And</span>
  <span m="1833570">then</span> <span m="1833750">these</span> <span m="1833930">changes</span>
  <span m="1834400">then</span> <span m="1834620">propagate</span> <span m="1835250">to</span>
  <span m="1835450">our</span> <span m="1835910">predecessors,</span> <span m="1836660">because</span>
  <span m="1836930">the</span> <span m="1837140">costs</span> <span m="1838070">for</span>
  <span m="1838230">the</span> <span m="1838280">processors</span> <span m="1839510">are</span>
  <span m="1839630">each</span> <span m="1839870">dependent</span> <span m="1840470">on</span>
  <span m="1840680">the</span> <span m="1840800">g value</span> <span m="1841250">for</span>
  <span m="1841670">their</span> <span m="1841970">successor.</span> <span m="1843140">And</span>
  <span m="1843260">so</span> <span m="1843690">when</span> <span m="1843950">we</span>
  <span m="1844280">hit</span> <span m="1844550">a</span> <span m="1844910">node,
  we</span> <span m="1845030">have</span> <span m="1845180">to</span> <span m="1845240">propagate
  that</span> <span m="1845640">change</span> <span m="1846080">all</span> <span m="1846210">the</span>
  <span m="1846370">way</span> <span m="1846800">back</span> <span m="1847190">through</span>
  <span m="1847340">the</span> <span m="1847820">graph.</span></p><p><span m="1848300">So
  to</span> <span m="1848780">do</span> <span m="1849050">this</span> <span m="1849320">efficiently,</span>
  <span m="1850550">we</span> <span m="1850650">take</span> <span m="1850780">an A*</span>
  <span m="1850870">like</span> <span m="1851300">approach,</span> <span m="1852110">where</span>
  <span m="1852230">we</span> <span m="1852390">update</span> <span m="1852840">the
  lowest</span> <span m="1853130">cost</span> <span m="1854060">nodes</span> <span
  m="1854420">first,</span> <span m="1855030">and</span> <span m="1855140">we</span>
  <span m="1855260">don't</span> <span m="1855360">expand</span> <span m="1855920">a</span>
  <span m="1856050">node</span> <span m="1856760">until</span> <span m="1857470">it
  is</span> <span m="1857750">the</span> <span m="1858110">next</span> <span m="1858560">lowest</span>
  <span m="1858980">cost.</span> <span m="1863030">To</span> <span m="1863090">help</span>
  <span m="1863330">us</span> <span m="1863480">do</span> <span m="1863750">this,</span>
  <span m="1864080">we're</span> <span m="1864200">going</span> <span m="1864320">to</span>
  <span m="1864380">store</span> <span m="1864870">additional</span> <span m="1865320">fact.</span>
  <span m="1865930">We'll</span> <span m="1866110">call</span> <span m="1866350">this</span>
  <span m="1866730">rhs.</span> <span m="1867765">Now</span> <span m="1868220">the</span>
  <span m="1868633">meaning</span> <span m="1869046">behind</span> <span m="1869460">rhs,</span>
  <span m="1870960">it</span> <span m="1871140">comes</span> <span m="1871400">from</span>
  <span m="1871970">the</span> <span m="1872120">term</span> <span m="1872450">right-hand</span>
  <span m="1872930">side,</span> <span m="1873590">which</span> <span m="1873740">in
  the paper</span> <span m="1874160">world,</span> <span m="1874400">was</span> <span
  m="1874580">first</span> <span m="1874880">introduced</span> <span m="1875155">and</span>
  <span m="1875530">made</span> <span m="1875690">more</span> <span m="1875990">sense</span>
  <span m="1876260">than</span> <span m="1876410">it</span> <span m="1876470">does</span>
  <span m="1876790">so</span> <span m="1876950">here.</span></p><p><span m="1877880">What</span>
  <span m="1878060">you can</span> <span m="1878270">think</span> <span m="1878560">of</span>
  <span m="1878680">your</span> <span m="1878850">rhs</span> <span m="1879380">value</span>
  <span m="1879860">as is</span> <span m="1880490">essentially</span> <span m="1881180">you're</span>
  <span m="1881360">corrected</span> <span m="1881625">your</span> <span m="1881890">g</span>
  <span m="1882320">costs.</span> <span m="1883180">When</span> <span m="1883755">edge</span>
  <span m="1884300">costs</span> <span m="1884920">change,</span> <span m="1885770">how</span>
  <span m="1886130">G</span> <span m="1886440">should</span> <span m="1886750">be</span>
  <span m="1887235">signed</span> <span m="1887720">so that</span> <span m="1888210">it's</span>
  <span m="1889100">correct</span> <span m="1889580">for a</span> <span m="1889967">different
  graph.</span> <span m="1890741">And</span> <span m="1891130">when</span> <span m="1891670">your</span>
  <span m="1891950">rhs</span> <span m="1892490">value</span> <span m="1893020">is</span>
  <span m="1893210">not</span> <span m="1893510">equal</span> <span m="1893780">to</span>
  <span m="1893900">your</span> <span m="1894050">g</span> <span m="1894280">value,</span>
  <span m="1895040">that</span> <span m="1895190">means</span> <span m="1895460">that</span>
  <span m="1895540">we</span> <span m="1895700">have</span> <span m="1895940">what</span>
  <span m="1896030">is</span> <span m="1896150">called a</span> <span m="1896450">local</span>
  <span m="1896930">inconsistency.</span> <span m="1898460">So</span> <span m="1899090">given</span>
  <span m="1899420">the</span> <span m="1899510">logic</span> <span m="1899960">that</span>
  <span m="1900200">your</span> <span m="1900400">rhs</span> <span m="1900990">value</span>
  <span m="1901370">should</span> <span m="1901730">be</span> <span m="1902000">what
  your</span> <span m="1902260">g</span> <span m="1902590">value</span> <span m="1903190">would</span>
  <span m="1903370">be</span> <span m="1903590">corrected</span> <span m="1904250">to</span>
  <span m="1904400">be,</span> <span m="1905360">what</span> <span m="1905600">would</span>
  <span m="1905720">your</span> <span m="1905870">rhs</span> <span m="1906110">value</span>
  <span m="1906540">be</span> <span m="1906960">for</span> <span m="1907140">this</span>
  <span m="1907410">graph here?</span></p><p><span m="1914420">AUDIENCE:</span> <span
  m="1914585">5?</span></p><p><span m="1915230">BEN AYTON:</span> <span m="1915470">5,</span>
  <span m="1915710">yes.</span> <span m="1916890">So</span> <span m="1917960">this</span>
  <span m="1918500">is</span> <span m="1918590">the</span> <span m="1918650">same</span>
  <span m="1918920">graph</span> <span m="1919190">that I</span> <span m="1919320">presented</span>
  <span m="1919640">previously,</span> <span m="1920330">and</span> <span m="1920420">I</span>
  <span m="1920510">walked</span> <span m="1920700">through</span> <span m="1920900">how</span>
  <span m="1921060">g</span> <span m="1921230">should</span> <span m="1921740">be</span>
  <span m="1922010">5.</span> <span m="1922822">rhs</span> <span m="1923230">should</span>
  <span m="1923430">be</span> <span m="1923870">5</span> <span m="1924240">here.</span>
  <span m="1925841">And</span> <span m="1926310">what</span> <span m="1926480">we're</span>
  <span m="1926600">tracking</span> <span m="1927170">is</span> <span m="1927770">rhs</span>
  <span m="1928050">and</span> <span m="1928496">g</span> <span m="1928942">differently.</span>
  <span m="1930280">So</span> <span m="1930430">g</span> <span m="1930840">is what
  it</span> <span m="1930980">should</span> <span m="1931310">be,</span> <span m="1931500">but</span>
  <span m="1931610">we</span> <span m="1931730">haven't</span> <span m="1932000">got</span>
  <span m="1932120">the</span> <span m="1932410">dated</span> <span m="1932850">g</span>
  <span m="1933560">to</span> <span m="1933680">be</span> <span m="1933800">5</span>
  <span m="1934160">yet.</span></p><p><span m="1935540">So</span> <span m="1935630">we</span>
  <span m="1935750">have</span> <span m="1935900">two</span> <span m="1936230">different</span>
  <span m="1936560">types</span> <span m="1936970">of</span> <span m="1937030">local</span>
  <span m="1937370">consistencies</span> <span m="1938060">that</span> <span m="1938320">we</span>
  <span m="1938420">distinguish</span> <span m="1938900">between.</span> <span m="1940340">We</span>
  <span m="1940460">have</span> <span m="1940610">what</span> <span m="1940760">we</span>
  <span m="1940880">call</span> <span m="1941320">local</span> <span m="1941950">overconsistency,</span>
  <span m="1943320">where</span> <span m="1943550">g</span> <span m="1943700">is</span>
  <span m="1944000">greater</span> <span m="1944370">than your</span> <span m="1944640">rhs</span>
  <span m="1944910">value.</span> <span m="1946260">This</span> <span m="1946490">is</span>
  <span m="1946910">going</span> <span m="1947060">to</span> <span m="1947150">behave</span>
  <span m="1947630">more</span> <span m="1947900">similarly</span> <span m="1948580">to</span>
  <span m="1948740">Dijkstra's</span> <span m="1949160">algorithm,</span> <span m="1950210">where</span>
  <span m="1950820">the</span> <span m="1952670">value</span> <span m="1953000">that</span>
  <span m="1953140">we're</span> <span m="1953270">associating</span> <span m="1953615">to</span>
  <span m="1953960">any given</span> <span m="1954230">node</span> <span m="1954830">now</span>
  <span m="1955060">is</span> <span m="1955190">higher</span> <span m="1955580">than</span>
  <span m="1955700">it</span> <span m="1955760">should</span> <span m="1956060">be,</span>
  <span m="1956390">and</span> <span m="1956780">we're</span> <span m="1956960">relaxing</span>
  <span m="1957800">down</span> <span m="1958100">to</span> <span m="1958190">the</span>
  <span m="1958280">true</span> <span m="1958510">value.</span></p><p><span m="1959880">However,</span>
  <span m="1960110">we</span> <span m="1960200">have</span> <span m="1960320">a</span>
  <span m="1960380">lovely</span> <span m="1960820">underconsistent</span> <span m="1961580">case</span>
  <span m="1961910">that</span> <span m="1962000">we</span> <span m="1962120">have</span>
  <span m="1962460">to handle</span> <span m="1962610">slightly differently.</span>
  <span m="1964620">So now</span> <span m="1965060">I'm going</span> <span m="1965500">to</span>
  <span m="1965650">walk</span> <span m="1965920">through</span> <span m="1966440">updating</span>
  <span m="1966980">and</span> <span m="1967070">expanding</span> <span m="1967385">nodes.</span>
  <span m="1968740">What I mean by</span> <span m="1969320">updating</span> <span
  m="1969680">a node</span> <span m="1970040">is</span> <span m="1970516">recomputing</span>
  <span m="1970992">the</span> <span m="1971470">rhs</span> <span m="1972050">value,</span>
  <span m="1972770">and</span> <span m="1972870">then</span> <span m="1973010">placing</span>
  <span m="1973540">that</span> <span m="1973720">node</span> <span m="1974030">on</span>
  <span m="1974210">the</span> <span m="1974300">priority</span> <span m="1974880">queue,</span>
  <span m="1975470">if</span> <span m="1975680">that</span> <span m="1975830">node</span>
  <span m="1976140">is</span> <span m="1976430">locally</span> <span m="1976750">inconsistent.</span></p><p><span
  m="1979130">So</span> <span m="1979220">to</span> <span m="1979370">give</span>
  <span m="1979520">an</span> <span m="1979610">example</span> <span m="1980120">here,</span>
  <span m="1981810">I've</span> <span m="1981860">changed</span> <span m="1982310">this</span>
  <span m="1982420">value,</span> <span m="1984320">moving</span> <span m="1985250">from</span>
  <span m="1985460">6</span> <span m="1985790">at the bottom</span> <span m="1986630">to</span>
  <span m="1986810">1,</span> <span m="1987350">and</span> <span m="1987500">recomputing</span>
  <span m="1988100">rhs,</span> <span m="1988910">as</span> <span m="1989060">we</span>
  <span m="1989150">did</span> <span m="1989420">beforehand.</span> <span m="1990950">Now</span>
  <span m="1991210">we</span> <span m="1991450">see</span> <span m="1991800">that
  the node is</span> <span m="1992260">locally</span> <span m="1992710">inconsistent.</span>
  <span m="1993980">In</span> <span m="1994070">this</span> <span m="1994280">case,</span>
  <span m="1994570">it's</span> <span m="1994860">locally</span> <span m="1996720">underconsistent.</span>
  <span m="1998530">And</span> <span m="1998990">so we place</span> <span m="1999310">that</span>
  <span m="1999870">on the</span> <span m="2000240">priority</span> <span m="2000560">queue.</span></p><p><span
  m="2003170">The</span> <span m="2003840">priority</span> <span m="2004160">queue</span>
  <span m="2004480">values</span> <span m="2004840">are</span> <span m="2005410">based</span>
  <span m="2006160">on</span> <span m="2006730">this</span> <span m="2007000">new</span>
  <span m="2007330">formula.</span> <span m="2008990">This</span> <span m="2009250">new</span>
  <span m="2009460">formula</span> <span m="2010000">essentially</span> <span m="2010720">handles</span>
  <span m="2011590">how</span> <span m="2011950">we</span> <span m="2012200">see</span>
  <span m="2012625">G</span> <span m="2013050">and</span> <span m="2013280">rhs.</span>
  <span m="2014890">In</span> <span m="2015010">essence,</span> <span m="2015530">we</span>
  <span m="2015580">want</span> <span m="2015790">to</span> <span m="2015880">take</span>
  <span m="2016180">the</span> <span m="2016340">minimum</span> <span m="2016790">value</span>
  <span m="2017280">of</span> <span m="2017570">one</span> <span m="2017830">of these,</span>
  <span m="2018970">so</span> <span m="2019120">that</span> <span m="2019270">we</span>
  <span m="2019360">can</span> <span m="2019480">handle</span> <span m="2019960">it</span>
  <span m="2022030">the</span> <span m="2022150">first</span> <span m="2022510">time</span>
  <span m="2023040">that</span> <span m="2023200">it will</span> <span m="2023410">cause</span>
  <span m="2023710">changes that</span> <span m="2024210">propagate</span> <span m="2024560">through
  the graph.</span></p><p><span m="2025890">And</span> <span m="2026250">so</span>
  <span m="2026740">this</span> <span m="2027170">is</span> <span m="2027300">essentially</span>
  <span m="2027650">our</span> <span m="2028000">ordering</span> <span m="2028330">on
  our</span> <span m="2028585">priority</span> <span m="2028840">queue</span> <span
  m="2029155">which</span> <span m="2029470">is</span> <span m="2029860">essentially</span>
  <span m="2030250">the</span> <span m="2030370">same</span> <span m="2031240">coupling</span>
  <span m="2031990">that</span> <span m="2032200">we</span> <span m="2032290">saw</span>
  <span m="2033100">for</span> <span m="2033340">A*.</span> <span m="2034740">But</span>
  <span m="2034990">here,</span> <span m="2035410">we</span> <span m="2035530">just</span>
  <span m="2035740">have</span> <span m="2036110">g of</span> <span m="2036550">s</span>
  <span m="2036700">replaced by</span> <span m="2037050">the</span> <span m="2037200">minimum</span>
  <span m="2037730">of</span> <span m="2037850">g of s and</span> <span m="2038125">rhs</span>
  <span m="2038400">of s.</span> <span m="2040770">And</span> <span m="2040930">so,</span>
  <span m="2041650">here</span> <span m="2042160">your</span> <span m="2042330">minimum
  of</span> <span m="2042830">g and rhs</span> <span m="2044480">is</span> <span m="2044640">5,</span>
  <span m="2044940">plus a</span> <span m="2045400">heuristic,</span> <span m="2045970">leads</span>
  <span m="2046240">to</span> <span m="2046470">a</span> <span m="2047290">total</span>
  <span m="2047680">cost</span> <span m="2048070">associated</span> <span m="2048550">with</span>
  <span m="2048710">this</span> <span m="2048870">node</span> <span m="2049159">of</span>
  <span m="2049420">9,</span> <span m="2049760">5.</span></p><p><span m="2051969">So</span>
  <span m="2052120">we</span> <span m="2052210">expand</span> <span m="2053260">our</span>
  <span m="2053510">five prior</span> <span m="2053750">nodes</span> <span m="2054280">by</span>
  <span m="2054400">then</span> <span m="2054580">taking</span> <span m="2054980">them</span>
  <span m="2055290">off</span> <span m="2055540">the</span> <span m="2055719">priority</span>
  <span m="2056219">queue</span> <span m="2056949">and</span> <span m="2057130">changing</span>
  <span m="2057639">g.</span> <span m="2059260">Now</span> <span m="2059530">I said</span>
  <span m="2059739">here</span> <span m="2059889">that</span> <span m="2060100">we</span>
  <span m="2060199">have</span> <span m="2060360">an inconsistent.</span> <span m="2062290">And</span>
  <span m="2062320">so,</span> <span m="2064179">we</span> <span m="2064469">update</span>
  <span m="2065050">this</span> <span m="2065409">in much the</span> <span m="2065760">way</span>
  <span m="2066130">that we</span> <span m="2066280">would</span> <span m="2066429">expect.</span>
  <span m="2067449">Your</span> <span m="2067699">g</span> <span m="2068009">values</span>
  <span m="2068320">are</span> <span m="2068409">relaxing</span> <span m="2069010">down</span>
  <span m="2069400">to</span> <span m="2069520">your</span> <span m="2069889">rhs</span>
  <span m="2070230">values,</span> <span m="2070916">and</span> <span m="2071260">so</span>
  <span m="2071380">we</span> <span m="2071500">just</span> <span m="2071710">set</span>
  <span m="2072100">g</span> <span m="2072610">to be</span> <span m="2072790">equal</span>
  <span m="2073199">to</span> <span m="2073679">rhs.</span></p><p><span m="2075320">In</span>
  <span m="2075429">this</span> <span m="2075610">case,</span> <span m="2076090">our</span>
  <span m="2076270">node</span> <span m="2076510">is</span> <span m="2076630">now</span>
  <span m="2076870">locally</span> <span m="2077320">consistent,</span> <span m="2077920">and</span>
  <span m="2078060">it's</span> <span m="2078210">going to stay that way.</span> <span
  m="2079780">So</span> <span m="2080110">can</span> <span m="2080300">anyone</span>
  <span m="2080590">think</span> <span m="2080830">of</span> <span m="2080920">some</span>
  <span m="2081100">good</span> <span m="2081370">reasons</span> <span m="2082270">why</span>
  <span m="2082719">I go</span> <span m="2082960">through</span> <span m="2083170">the</span>
  <span m="2083230">process</span> <span m="2083800">of</span> <span m="2083889">changing</span>
  <span m="2084580">rhs</span> <span m="2085270">and</span> <span m="2085360">keeping</span>
  <span m="2085570">track</span> <span m="2085780">of</span> <span m="2085870">that</span>
  <span m="2086139">new</span> <span m="2086380">value,</span> <span m="2087170">only</span>
  <span m="2087400">to</span> <span m="2087630">put</span> <span m="2087980">on</span>
  <span m="2088420">the</span> <span m="2088670">queue,</span> <span m="2088880">and</span>
  <span m="2089139">then</span> <span m="2089500">take</span> <span m="2089710">it</span>
  <span m="2089770">off</span> <span m="2089949">again,</span> <span m="2090370">instead</span>
  <span m="2090610">of</span> <span m="2090699">just</span> <span m="2091239">recomputing</span>
  <span m="2091949">what</span> <span m="2092210">g of</span> <span m="2092500">s
  should</span> <span m="2092830">be</span> <span m="2093239">in</span> <span m="2093340">the</span>
  <span m="2093400">first</span> <span m="2093699">place?</span> <span m="2094953">Does
  anyone have</span> <span m="2095445">any ideas?</span></p><p><span m="2099873">AUDIENCE:</span>
  <span m="2100119">[INAUDIBLE]</span></p><p>&nbsp;</p><p><span m="2105790">BEN AYTON:</span>
  <span m="2105875">What</span> <span m="2105960">you</span> <span m="2106050">can</span>
  <span m="2106230">think</span> <span m="2106470">of</span> <span m="2106830">is</span>
  <span m="2107060">that</span> <span m="2108450">you're</span> <span m="2108660">putting</span>
  <span m="2109440">something</span> <span m="2110060">on the</span> <span m="2110490">queue.</span>
  <span m="2110960">If we</span> <span m="2111870">update</span> <span m="2112350">that</span>
  <span m="2112570">value</span> <span m="2114600">immediately,</span> <span m="2115630">there</span>
  <span m="2115740">are</span> <span m="2115880">multiple</span> <span m="2116180">nodes</span>
  <span m="2117150">that</span> <span m="2117300">could</span> <span m="2117550">change</span>
  <span m="2118800">the</span> <span m="2118950">same</span> <span m="2119380">node
  that</span> <span m="2119840">we</span> <span m="2119940">just</span> <span m="2120320">considered.</span>
  <span m="2121170">By,</span> <span m="2121420">which</span> <span m="2121530">I</span>
  <span m="2121620">mean</span> <span m="2122320">more</span> <span m="2122660">work</span>
  <span m="2122960">changes</span> <span m="2123560">as</span> <span m="2123700">they</span>
  <span m="2123840">propagate</span> <span m="2124800">back</span> <span m="2125130">through</span>
  <span m="2125310">the</span> <span m="2125430">graph,</span> <span m="2126330">could</span>
  <span m="2126570">lead</span> <span m="2126900">to</span> <span m="2127020">changes</span>
  <span m="2127590">in</span> <span m="2127820">rhs</span> <span m="2128400">value</span>
  <span m="2129440">of</span> <span m="2129670">that specific</span> <span m="2130120">node.</span></p><p><span
  m="2131200">And</span> <span m="2131390">so,</span> <span m="2131730">what</span>
  <span m="2131910">we</span> <span m="2132060">would</span> <span m="2132170">need</span>
  <span m="2132340">to</span> <span m="2132420">do</span> <span m="2132780">if</span>
  <span m="2132910">we</span> <span m="2133050">can</span> <span m="2133250">recompute</span>
  <span m="2133650">g of s</span> <span m="2134520">every</span> <span m="2134820">time,</span>
  <span m="2135840">is</span> <span m="2136170">put</span> <span m="2136450">it on
  the</span> <span m="2136790">queue</span> <span m="2139760">to</span> <span m="2139860">signal</span>
  <span m="2140220">that</span> <span m="2140400">we're</span> <span m="2140780">recomputing</span>
  <span m="2141450">g of s,</span> <span m="2142440">and</span> <span m="2142580">do</span>
  <span m="2142770">that</span> <span m="2143720">recomputation,</span> <span m="2144130">and</span>
  <span m="2144540">then</span> <span m="2146310">new</span> <span m="2146520">changes</span>
  <span m="2146870">we've</span> <span m="2147010">done,</span> <span m="2147730">perform</span>
  <span m="2148140">that</span> <span m="2148270">again,</span> <span m="2148830">do</span>
  <span m="2148980">that</span> <span m="2149160">again</span> <span m="2149580">and</span>
  <span m="2149670">again</span> <span m="2150090">and</span> <span m="2150210">again</span>
  <span m="2150600">and</span> <span m="2150690">again.</span> <span m="2150930">And</span>
  <span m="2151230">we</span> <span m="2151380">want</span> <span m="2151600">to</span>
  <span m="2151920">avoid</span> <span m="2152370">that</span> <span m="2152520">situation.</span></p><p><span
  m="2153910">So</span> <span m="2154050">what we're</span> <span m="2154140">going</span>
  <span m="2154290">to</span> <span m="2154410">do</span> <span m="2154610">is</span>
  <span m="2154710">we're</span> <span m="2154830">going</span> <span m="2154950">to</span>
  <span m="2155370">keep</span> <span m="2155670">our</span> <span m="2155970">rhs
  as</span> <span m="2156300">essentially</span> <span m="2156555">a</span> <span
  m="2156810">temp</span> <span m="2157160">value</span> <span m="2157670">that</span>
  <span m="2157830">can</span> <span m="2158010">be</span> <span m="2158160">adjusted</span>
  <span m="2158610">when it's</span> <span m="2158970">in</span> <span m="2159150">the</span>
  <span m="2159270">queue.</span> <span m="2159990">So</span> <span m="2160160">when</span>
  <span m="2160290">something</span> <span m="2160680">is on the queue,</span> <span
  m="2160870">it's</span> <span m="2161580">on</span> <span m="2161820">there</span>
  <span m="2162120">once,</span> <span m="2162900">and</span> <span m="2163020">it</span>
  <span m="2163080">can</span> <span m="2163200">be</span> <span m="2163350">updated</span>
  <span m="2163645">and</span> <span m="2163940">taken</span> <span m="2164360">off.</span>
  <span m="2165570">But</span> <span m="2165750">we</span> <span m="2165900">know</span>
  <span m="2166130">when it's</span> <span m="2166340">been</span> <span m="2166470">taken</span>
  <span m="2166800">off,</span> <span m="2167380">that</span> <span m="2167470">it's</span>
  <span m="2167700">been</span> <span m="2167800">taken</span> <span m="2168030">for</span>
  <span m="2168240">the</span> <span m="2168330">correct</span> <span m="2168650">time,</span>
  <span m="2169070">and</span> <span m="2169230">won't</span> <span m="2169390">need
  to be</span> <span m="2169740">handled</span> <span m="2170210">again.</span></p><p><span
  m="2171210">AUDIENCE:</span> <span m="2171315">So</span> <span m="2171820">if</span>
  <span m="2172220">I</span> <span m="2172620">understand</span> <span m="2172810">this</span>
  <span m="2172970">correctly,</span> <span m="2174130">so if</span> <span m="2174520">you</span>
  <span m="2174660">had</span> <span m="2174870">a</span> <span m="2174940">single</span>
  <span m="2176660">edge</span> <span m="2177270">cost</span> <span m="2178300">that</span>
  <span m="2178530">we</span> <span m="2179010">changed,</span> <span m="2180195">then</span>
  <span m="2180630">you</span> <span m="2180900">could just</span> <span m="2181130">do</span>
  <span m="2181250">what</span> <span m="2181450">you just</span> <span m="2181710">said,</span>
  <span m="2182210">in terms</span> <span m="2182340">of,</span> <span m="2182730">you</span>
  <span m="2182940">could</span> <span m="2183150">just</span> <span m="2183540">update</span>
  <span m="2183720">the</span> <span m="2183850">thing,</span> <span m="2184160">and</span>
  <span m="2184380">probably</span> <span m="2184880">should</span> <span m="2185080">be</span>
  <span m="2185400">predecessor</span> <span m="2185680">rate.</span></p><p><span
  m="2186480">BEN AYTON:</span> <span m="2186660">Yes.</span> <span m="2186840">So
  if you</span> <span m="2187090">knew</span> <span m="2187390">for</span> <span m="2187500">sure</span>
  <span m="2187710">that</span> <span m="2187860">nothing</span> <span m="2188360">else
  was</span> <span m="2188760">coming</span> <span m="2189120">back</span> <span m="2189500">and
  down,</span> <span m="2190500">then</span> <span m="2190930">we</span> <span m="2191040">could</span>
  <span m="2191160">just</span> <span m="2191400">do</span> <span m="2191580">that</span>
  <span m="2191760">change and</span> <span m="2192150">propagate</span> <span m="2192630">to
  all the</span> <span m="2192900">predecessors,</span> <span m="2193830">because</span>
  <span m="2194040">nothing</span> <span m="2194490">upstream</span> <span m="2195150">of</span>
  <span m="2195300">that</span> <span m="2195480">node</span> <span m="2195870">is
  affected.</span></p><p><span m="2196980">AUDIENCE:</span> <span m="2197055">So</span>
  <span m="2197130">am I understanding</span> <span m="2197470">correctly--</span>
  <span m="2198150">so</span> <span m="2198450">you're</span> <span m="2198630">basically</span>
  <span m="2199050">running</span> <span m="2200240">the</span> <span m="2200500">programming,</span>
  <span m="2202440">because</span> <span m="2202770">you're</span> <span m="2203330">keeping</span>
  <span m="2204320">the</span> <span m="2205010">costs</span> <span m="2205380">to
  goal</span> <span m="2207150">to devote,</span> <span m="2207840">and</span> <span
  m="2207990">then</span> <span m="2208140">what</span> <span m="2208320">you're</span>
  <span m="2208410">doing</span> <span m="2208710">is</span> <span m="2208830">every</span>
  <span m="2209010">time</span> <span m="2209250">you</span> <span m="2209310">have</span>
  <span m="2210060">an</span> <span m="2210270">edge</span> <span m="2210630">that</span>
  <span m="2210780">changes</span> <span m="2212030">to a</span> <span m="2212160">value</span>
  <span m="2212580">that</span> <span m="2212790">could</span> <span m="2213000">potentially</span>
  <span m="2213540">make</span> <span m="2214160">that</span> <span m="2214310">node</span>
  <span m="2214590">better</span> <span m="2214860">than it was</span> <span m="2215130">before,</span>
  <span m="2215370">so</span> <span m="2215765">if</span> <span m="2216160">it</span>
  <span m="2216220">changes</span> <span m="2216750">the</span> <span m="2216870">value</span>
  <span m="2217200">of</span> <span m="2217290">that node</span> <span m="2217672">to</span>
  <span m="2218820">something</span> <span m="2219660">better</span> <span m="2220295">than
  it was before,</span> <span m="2223000">you</span> <span m="2223240">would</span>
  <span m="2223680">change</span> <span m="2224100">that</span> <span m="2224310">node,</span>
  <span m="2225090">and</span> <span m="2225270">then</span> <span m="2227020">queue</span>
  <span m="2227870">all</span> <span m="2228140">the</span> <span m="2228420">predecessors,</span>
  <span m="2229260">because</span> <span m="2229500">those</span> <span m="2229755">be</span>
  <span m="2230010">changed</span> <span m="2230480">as</span> <span m="2230600">well.</span></p><p><span
  m="2230940">BEN AYTON:</span> <span m="2231045">Yes.</span></p><p><span m="2232145">AUDIENCE:</span>
  <span m="2232233">I</span> <span m="2232321">mean,</span> <span m="2232410">if</span>
  <span m="2232750">those nodes</span> <span m="2233120">do</span> <span m="2233490">not</span>
  <span m="2233670">change,</span> <span m="2234800">you don't do</span> <span m="2235170">anything.</span>
  <span m="2236070">You're moving from the</span> <span m="2236280">queue.</span>
  <span m="2237140">They</span> <span m="2237450">also</span> <span m="2237830">change</span>
  <span m="2237990">a better bell and</span> <span m="2238320">keep</span> <span m="2238650">propagating</span>
  <span m="2238920">until you have</span> <span m="2239250">nothing</span> <span m="2239490">else
  to</span> <span m="2239640">[INAUDIBLE].</span></p><p><span m="2240870">BEN AYTON:</span>
  <span m="2241065">Yeah.</span> <span m="2241260">But</span> <span m="2241460">we</span>
  <span m="2241750">only</span> <span m="2243420">do</span> <span m="2243740">the</span>
  <span m="2244020">propagation,</span> <span m="2244710">or</span> <span m="2246460">we</span>
  <span m="2246720">queue</span> <span m="2247040">changes</span> <span m="2247550">that</span>
  <span m="2247730">occur</span> <span m="2248160">earlier</span> <span m="2248430">in</span>
  <span m="2248550">the</span> <span m="2248680">graph,</span> <span m="2249030">but
  we</span> <span m="2249780">only</span> <span m="2250140">actually</span> <span
  m="2251890">perform</span> <span m="2252780">the</span> <span m="2252870">change</span>
  <span m="2253500">resetting</span> <span m="2254030">the g</span> <span m="2254280">value,</span>
  <span m="2255060">when it's</span> <span m="2255530">expanded.</span></p><p><span
  m="2256390">AUDIENCE:</span> <span m="2256503">And</span> <span m="2256616">then</span>
  <span m="2257910">the</span> <span m="2258000">reason</span> <span m="2258330">for</span>
  <span m="2258460">that</span> <span m="2258570">is</span> <span m="2259140">for</span>
  <span m="2259320">efficiency</span> <span m="2260640">when</span> <span m="2260870">you</span>
  <span m="2261030">have</span> <span m="2261570">more</span> <span m="2261960">than</span>
  <span m="2262110">one</span> <span m="2262800">edge</span> <span m="2263190">changing?</span></p><p><span
  m="2264190">BEN AYTON:</span> <span m="2264240">Yes.</span></p><p><span m="2264350">AUDIENCE:</span>
  <span m="2264476">So</span> <span m="2264602">you</span> <span m="2264730">could
  basically</span> <span m="2264900">have</span> <span m="2265140">multiple</span>
  <span m="2265710">paths</span> <span m="2267030">affecting</span> <span m="2267490">the</span>
  <span m="2267570">same</span> <span m="2267820">node.</span> <span m="2268680">And</span>
  <span m="2269370">in</span> <span m="2269580">this</span> <span m="2270080">situation,</span>
  <span m="2270730">if</span> <span m="2270900">you</span> <span m="2271050">actually</span>
  <span m="2271380">allow</span> <span m="2271650">your</span> <span m="2271920">changes</span>
  <span m="2272430">will</span> <span m="2272570">occur</span> <span m="2273000">and</span>
  <span m="2273510">multiple</span> <span m="2274040">edges,</span> <span m="2275030">that's</span>
  <span m="2275160">when</span> <span m="2275640">the</span> <span m="2275770">importance</span>
  <span m="2276220">of</span> <span m="2276310">the</span> <span m="2276570">queue</span>
  <span m="2276920">comes.</span></p><p><span m="2277140">BEN AYTON:</span> <span
  m="2277220">That's</span> <span m="2277300">exactly.</span></p><p><span m="2277810">AUDIENCE:</span>
  <span m="2277862">Which</span> <span m="2277914">is</span> <span m="2277966">actually,</span>
  <span m="2278020">it</span> <span m="2278340">prevents</span> <span m="2278820">you</span>
  <span m="2278910">from</span> <span m="2279460">redoing</span> <span m="2280140">the</span>
  <span m="2280260">same</span> <span m="2280620">work</span> <span m="2280880">over</span>
  <span m="2281170">and</span> <span m="2281290">over</span> <span m="2281420">again.</span></p><p><span
  m="2281620">BEN AYTON:</span> <span m="2281840">That's</span> <span m="2282060">exactly
  right.</span> <span m="2282300">Because if</span> <span m="2282690">another</span>
  <span m="2282990">change</span> <span m="2283380">came</span> <span m="2283580">through,</span>
  <span m="2284000">then we'd</span> <span m="2284170">put all</span> <span m="2284300">the</span>
  <span m="2284430">predecessors</span> <span m="2284520">back</span> <span m="2284850">in
  the queue</span> <span m="2284940">again,</span> <span m="2285150">and we'd</span>
  <span m="2285890">do</span> <span m="2286190">all</span> <span m="2286450">of</span>
  <span m="2286650">our</span> <span m="2286910">updates for all of them</span> <span
  m="2287400">as well.</span> <span m="2287880">We're</span> <span m="2288070">avoiding</span>
  <span m="2288380">that</span> <span m="2288450">process.</span></p><p><span m="2289520">AUDIENCE:</span>
  <span m="2289580">And</span> <span m="2289640">the</span> <span m="2289810">queue</span>
  <span m="2290360">ensures</span> <span m="2290730">that</span> <span m="2291270">we're</span>
  <span m="2291420">only</span> <span m="2291740">updating--</span> <span m="2293290">and</span>
  <span m="2293626">I</span> <span m="2293962">think</span> <span m="2294300">that'll</span>
  <span m="2294790">cover</span> <span m="2295020">it.</span> <span m="2295935">But</span>
  <span m="2296280">in</span> <span m="2296370">the</span> <span m="2296430">manner
  in</span> <span m="2296840">which</span> <span m="2297090">we</span> <span m="2297260">terminate,</span>
  <span m="2297810">we</span> <span m="2297930">don't</span> <span m="2298140">necessarily--</span>
  <span m="2298710">we</span> <span m="2298770">don't</span> <span m="2298920">expand</span>
  <span m="2299230">every</span> <span m="2299320">node</span> <span m="2299670">in</span>
  <span m="2299760">the</span> <span m="2299850">queue.</span> <span m="2300100">We</span>
  <span m="2300200">only</span> <span m="2300400">expand</span> <span m="2300720">those</span>
  <span m="2300930">we</span> <span m="2301050">need</span> <span m="2301290">in order</span>
  <span m="2301520">to</span> <span m="2301580">find the</span> <span m="2301890">shortest,</span>
  <span m="2303180">and</span> <span m="2303300">then</span> <span m="2303720">we</span>
  <span m="2303840">retain</span> <span m="2304170">the</span> <span m="2304260">queue</span>
  <span m="2304590">for</span> <span m="2304830">that</span> <span m="2305040">search</span>
  <span m="2305380">in</span> <span m="2305460">case</span> <span m="2305760">we</span>
  <span m="2305820">need</span> <span m="2306000">to</span> <span m="2306300">update</span>
  <span m="2306720">those</span> <span m="2307132">in</span> <span m="2307544">the</span>
  <span m="2308370">next</span> <span m="2308550">round</span> <span m="2308760">of</span>
  <span m="2308820">the</span> <span m="2308870">search.</span></p><p><span m="2309490">BEN
  AYTON:</span> <span m="2309570">Right.</span></p><p><span m="2321410">So</span>
  <span m="2321800">I have</span> <span m="2322220">to</span> <span m="2322560">correct</span>
  <span m="2322880">a mistake in</span> <span m="2323210">my language</span> <span
  m="2323650">that</span> <span m="2324140">I</span> <span m="2324200">said</span>
  <span m="2324380">before.</span> <span m="2325450">I</span> <span m="2325570">said</span>
  <span m="2325770">that</span> <span m="2325900">the</span> <span m="2326320">node</span>
  <span m="2326510">in</span> <span m="2326840">my</span> <span m="2327090">examples</span>
  <span m="2327420">that I</span> <span m="2327660">gave</span> <span m="2328040">before</span>
  <span m="2328410">was</span> <span m="2328640">highly</span> <span m="2328810">consistent,</span>
  <span m="2329140">[INAUDIBLE]</span> <span m="2329595">wasn't</span> <span m="2329930">consistent.</span>
  <span m="2330280">I</span> <span m="2330590">apologize</span> <span m="2330940">for</span>
  <span m="2331030">that</span> <span m="2331430">mistake.</span> <span m="2332220">Other</span>
  <span m="2333200">consistency</span> <span m="2333980">is</span> <span m="2334150">the</span>
  <span m="2334530">easy</span> <span m="2334820">case</span> <span m="2335930">that</span>
  <span m="2336020">we're</span> <span m="2336170">handling</span> <span m="2336530">here,</span>
  <span m="2336800">where</span> <span m="2337070">when</span> <span m="2337510">we</span>
  <span m="2337660">expand</span> <span m="2337930">that node,</span> <span m="2338990">we</span>
  <span m="2339140">have</span> <span m="2339320">to</span> <span m="2339620">take</span>
  <span m="2340120">g of</span> <span m="2340380">s</span> <span m="2341440">and</span>
  <span m="2341680">set</span> <span m="2342050">that</span> <span m="2342390">to</span>
  <span m="2342530">be</span> <span m="2342730">equal</span> <span m="2342940">to</span>
  <span m="2343060">the</span> <span m="2343330">rhs</span> <span m="2343600">value</span>
  <span m="2344110">for</span> <span m="2344350">expansion.</span></p><p><span m="2346080">And</span>
  <span m="2346130">then</span> <span m="2346670">we</span> <span m="2347120">propagate</span>
  <span m="2347890">that</span> <span m="2348060">effect</span> <span m="2349310">to</span>
  <span m="2349560">all</span> <span m="2349820">of the</span> <span m="2349910">predecessors</span>
  <span m="2350450">at</span> <span m="2350560">that</span> <span m="2350850">point,</span>
  <span m="2351170">which</span> <span m="2351380">means</span> <span m="2352670">we</span>
  <span m="2353090">update</span> <span m="2353600">the</span> <span m="2353660">predecessors</span>
  <span m="2354320">and</span> <span m="2354550">put those</span> <span m="2354860">on</span>
  <span m="2355140">the</span> <span m="2355480">queue</span> <span m="2356180">if</span>
  <span m="2356660">it</span> <span m="2357010">hasn't</span> <span m="2357440">had</span>
  <span m="2357755">an</span> <span m="2358070">impact</span> <span m="2358610">on</span>
  <span m="2358790">them.</span> <span m="2360370">This</span> <span m="2360620">means</span>
  <span m="2360980">that</span> <span m="2361160">the</span> <span m="2361850">node</span>
  <span m="2362150">is not</span> <span m="2362710">low key</span> <span m="2363030">inconsistent,</span>
  <span m="2363420">and it's</span> <span m="2363675">going to</span> <span m="2363930">remain</span>
  <span m="2364520">that</span> <span m="2364670">way</span> <span m="2364880">in
  that fashion.</span></p><p><span m="2366650">The</span> <span m="2366760">underconsistent</span>
  <span m="2367010">case,</span> <span m="2368770">which</span> <span m="2368870">was</span>
  <span m="2368960">the</span> <span m="2369110">opposite</span> <span m="2369540">of</span>
  <span m="2369670">what</span> <span m="2369840">I</span> <span m="2369890">showed,</span>
  <span m="2370840">is</span> <span m="2371070">the</span> <span m="2371150">more</span>
  <span m="2371450">difficult</span> <span m="2372650">case.</span> <span m="2373890">In
  this</span> <span m="2374200">case,</span> <span m="2374580">the</span> <span m="2374630">old</span>
  <span m="2374870">path cost</span> <span m="2376160">was</span> <span m="2376380">better</span>
  <span m="2376790">than the</span> <span m="2377163">new</span> <span m="2377536">rhs</span>
  <span m="2377910">value.</span> <span m="2378220">Rhs</span> <span m="2378585">value</span>
  <span m="2378950">has</span> <span m="2379230">increased</span> <span m="2379780">to</span>
  <span m="2379980">above</span> <span m="2380423">[INAUDIBLE].</span> <span m="2381310">In</span>
  <span m="2381410">this</span> <span m="2381530">case,</span> <span m="2382200">we</span>
  <span m="2382250">can</span> <span m="2382400">no</span> <span m="2382580">longer</span>
  <span m="2383270">relax</span> <span m="2383860">down</span> <span m="2384470">to</span>
  <span m="2384690">that g</span> <span m="2385060">value</span> <span m="2386090">from</span>
  <span m="2386300">our</span> <span m="2386420">Dijkstra's</span> <span m="2386860">algorithm</span>
  <span m="2387270">respective.</span> <span m="2388280">So</span> <span m="2388430">we</span>
  <span m="2388520">have</span> <span m="2388670">to</span> <span m="2388970">think</span>
  <span m="2389180">of</span> <span m="2389270">a</span> <span m="2389360">new</span>
  <span m="2389660">way</span> <span m="2389950">to handle this.</span></p><p><span
  m="2391890">What</span> <span m="2392030">we</span> <span m="2392180">do</span>
  <span m="2392690">is</span> <span m="2392840">we</span> <span m="2392990">essentially</span>
  <span m="2393860">set</span> <span m="2394690">our</span> <span m="2394950">g</span>
  <span m="2395210">value</span> <span m="2396100">to</span> <span m="2396510">be</span>
  <span m="2396770">equal</span> <span m="2397250">to</span> <span m="2397716">infinity.</span>
  <span m="2398650">And</span> <span m="2399360">this</span> <span m="2399500">is</span>
  <span m="2399620">an</span> <span m="2399800">extra</span> <span m="2400160">step</span>
  <span m="2400710">that's</span> <span m="2400910">going</span> <span m="2401090">to</span>
  <span m="2401180">cause</span> <span m="2402380">the</span> <span m="2402500">node
  to</span> <span m="2402870">go</span> <span m="2402980">back</span> <span m="2403300">on</span>
  <span m="2403430">the</span> <span m="2403530">queue</span> <span m="2403920">an</span>
  <span m="2404090">additional</span> <span m="2404540">time.</span> <span m="2405260">But</span>
  <span m="2405440">what</span> <span m="2405590">this</span> <span m="2405770">mechanism</span>
  <span m="2406500">assures</span> <span m="2407580">is</span> <span m="2407750">that</span>
  <span m="2408140">that</span> <span m="2408440">node</span> <span m="2408740">goes</span>
  <span m="2409090">back</span> <span m="2409400">on</span> <span m="2409520">the</span>
  <span m="2409640">queue</span> <span m="2410290">at</span> <span m="2410510">most</span>
  <span m="2411140">one</span> <span m="2411410">additional</span> <span m="2411830">time,
  which</span> <span m="2412170">means</span> <span m="2412510">that for</span> <span
  m="2412830">D*</span> <span m="2413060">Lite,</span> <span m="2413180">we</span>
  <span m="2413410">only</span> <span m="2413610">ever</span> <span m="2414110">examine</span>
  <span m="2414460">any</span> <span m="2414790">node</span> <span m="2415120">at</span>
  <span m="2415180">most</span> <span m="2416080">twice</span> <span m="2416740">on</span>
  <span m="2417105">the</span> <span m="2417470">queue.</span></p><p><span m="2419270">Once</span>
  <span m="2419600">we've</span> <span m="2420000">set</span> <span m="2420490">g
  of s</span> <span m="2420880">to be equal</span> <span m="2421250">to</span> <span
  m="2421400">infinity,</span> <span m="2422220">then</span> <span m="2422460">we</span>
  <span m="2422600">can</span> <span m="2422720">essentially</span> <span m="2423170">relax</span>
  <span m="2423620">down</span> <span m="2424040">to</span> <span m="2424250">the
  rhs</span> <span m="2424850">value</span> <span m="2425270">from</span> <span m="2425480">the</span>
  <span m="2425540">perspective</span> <span m="2426040">that</span> <span m="2426160">we</span>
  <span m="2426300">had</span> <span m="2426460">before.</span> <span m="2428120">So</span>
  <span m="2428340">we</span> <span m="2428960">set</span> <span m="2429380">g of</span>
  <span m="2429690">s</span> <span m="2429840">to be equal</span> <span m="2430130">to</span>
  <span m="2430280">infinity,</span> <span m="2431180">and</span> <span m="2431280">we</span>
  <span m="2431300">update</span> <span m="2431890">all</span> <span m="2432140">the
  predecessors</span> <span m="2432430">of</span> <span m="2432740">s</span> <span
  m="2433180">and</span> <span m="2433450">s</span> <span m="2433980">itself</span>
  <span m="2434420">this</span> <span m="2434600">time.</span> <span m="2435110">As</span>
  <span m="2435230">I</span> <span m="2435320">was</span> <span m="2435410">saying</span>
  <span m="2435680">before,</span> <span m="2435990">we</span> <span m="2436180">need
  to put</span> <span m="2436370">that</span> <span m="2436530">node node</span> <span
  m="2436760">back</span> <span m="2437090">on</span> <span m="2437210">the</span>
  <span m="2437330">cue</span> <span m="2437585">so</span> <span m="2437840">that</span>
  <span m="2437990">we</span> <span m="2438110">handle</span> <span m="2438560">it</span>
  <span m="2438730">when</span> <span m="2439010">rhs</span> <span m="2439250">has</span>
  <span m="2439640">hit</span> <span m="2439945">its</span> <span m="2440250">minimal</span>
  <span m="2440490">value.</span></p><p><span m="2441500">And</span> <span m="2441680">this</span>
  <span m="2441800">means</span> <span m="2442340">that</span> <span m="2442550">that
  node</span> <span m="2442830">is</span> <span m="2442990">now</span> <span m="2443180">going
  to</span> <span m="2443450">locally</span> <span m="2443810">consistent</span> <span
  m="2444530">or</span> <span m="2444830">overconsistent.</span> <span m="2446628">And
  we handle</span> <span m="2448110">overconsistency</span> <span m="2448910">in</span>
  <span m="2448980">the</span> <span m="2449070">case</span> <span m="2449370">that</span>
  <span m="2449825">I've shown you</span> <span m="2450280">before.</span> <span m="2451190">So</span>
  <span m="2451580">to</span> <span m="2451730">give</span> <span m="2451910">you</span>
  <span m="2452090">an</span> <span m="2452270">idea</span> <span m="2453200">of</span>
  <span m="2453320">how</span> <span m="2453670">exactly</span> <span m="2454040">this</span>
  <span m="2454220">works,</span> <span m="2454940">I'm</span> <span m="2455350">showing</span>
  <span m="2455635">you an</span> <span m="2455920">example</span> <span m="2456250">here.</span>
  <span m="2457910">We</span> <span m="2457970">start</span> <span m="2458240">off</span>
  <span m="2458360">with</span> <span m="2458510">this</span> <span m="2459370">graph,</span>
  <span m="2459760">and</span> <span m="2460640">we</span> <span m="2460880">introduce</span>
  <span m="2461180">two</span> <span m="2461420">changes.</span> <span m="2462980">We</span>
  <span m="2463310">have increased</span> <span m="2464600">this</span> <span m="2464820">edge</span>
  <span m="2465160">cost</span> <span m="2465700">to</span> <span m="2465890">5.</span>
  <span m="2466750">And</span> <span m="2466910">so</span> <span m="2467250">rhs</span>
  <span m="2467530">has</span> <span m="2467940">now</span> <span m="2468500">increased</span>
  <span m="2468755">to</span> <span m="2469010">a</span> <span m="2469220">total</span>
  <span m="2469670">of</span> <span m="2469770">10.</span> <span m="2470500">But</span>
  <span m="2470900">I've</span> <span m="2471205">also</span> <span m="2471510">changed</span>
  <span m="2471930">a</span> <span m="2472350">value</span> <span m="2473540">here</span>
  <span m="2474710">for</span> <span m="2475060">edges</span> <span m="2475340">that</span>
  <span m="2475520">you can't</span> <span m="2475850">can</span> <span m="2476120">see.</span>
  <span m="2476780">But</span> <span m="2476970">assume</span> <span m="2477170">that
  the</span> <span m="2477380">rhs</span> <span m="2477770">value of</span> <span
  m="2477890">this</span> <span m="2478560">node</span> <span m="2478930">has</span>
  <span m="2479120">also</span> <span m="2479420">changed.</span></p><p><span m="2481260">So</span>
  <span m="2481310">now</span> <span m="2481470">we</span> <span m="2481550">can</span>
  <span m="2481670">put</span> <span m="2482150">all</span> <span m="2482470">of</span>
  <span m="2482560">these</span> <span m="2483170">nodes</span> <span m="2483450">on
  a cable</span> <span m="2484490">ordered</span> <span m="2485050">in</span> <span
  m="2485210">this</span> <span m="2485390">way,</span> <span m="2486060">computed</span>
  <span m="2486970">using</span> <span m="2487220">the</span> <span m="2487280">formula</span>
  <span m="2487670">that</span> <span m="2487860">we've</span> <span m="2487920">seen</span>
  <span m="2488310">for</span> <span m="2488540">it.</span> <span m="2492020">We</span>
  <span m="2492320">expand</span> <span m="2493380">the node</span> <span m="2493890">s1</span>
  <span m="2494440">first.</span> <span m="2495335">And</span> <span m="2495630">because</span>
  <span m="2496450">it's</span> <span m="2496690">underconsistent,</span> <span m="2498430">we</span>
  <span m="2498560">set</span> <span m="2498930">g</span> <span m="2499190">to be</span>
  <span m="2499450">equal</span> <span m="2499810">to</span> <span m="2499960">infinity.</span>
  <span m="2502060">Then</span> <span m="2502270">we</span> <span m="2502420">propagate</span>
  <span m="2502840">to</span> <span m="2503050">all</span> <span m="2503350">predecessors</span>
  <span m="2508780">and</span> <span m="2509035">s1</span> <span m="2509290">itself,</span>
  <span m="2510800">meaning</span> <span m="2511170">those</span> <span m="2511460">go</span>
  <span m="2511740">back</span> <span m="2512050">on</span> <span m="2512190">the
  queue.</span> <span m="2513040">Now,</span> <span m="2513370">assuming</span> <span
  m="2513730">that</span> <span m="2513880">node</span> <span m="2514120">changes</span>
  <span m="2514570">of</span> <span m="2514680">any</span> <span m="2514930">relevance</span>
  <span m="2515110">happen</span> <span m="2515590">in these</span> <span m="2516050">nodes,</span>
  <span m="2517110">we</span> <span m="2517410">recompute</span> <span m="2518060">the</span>
  <span m="2518440">costs</span> <span m="2519910">for</span> <span m="2520410">s1,</span>
  <span m="2521000">which</span> <span m="2521160">has</span> <span m="2521260">now</span>
  <span m="2521440">changed</span> <span m="2522240">to</span> <span m="2522370">14,
  10,</span> <span m="2523090">because</span> <span m="2523290">we're</span> <span
  m="2523390">using</span> <span m="2523730">the</span> <span m="2523800">minimum</span>
  <span m="2524380">of</span> <span m="2524840">infinity and</span> <span m="2525250">10,</span>
  <span m="2525555">which</span> <span m="2525860">is</span> <span m="2526120">10
  plus</span> <span m="2526960">14,</span> <span m="2528010">going</span> <span m="2528340">behind</span>
  <span m="2529150">the</span> <span m="2529720">node</span> <span m="2530000">s2.</span></p><p><span
  m="2532070">Next,</span> <span m="2532400">we</span> <span m="2532460">expand</span>
  <span m="2533030">this</span> <span m="2533180">node</span> <span m="2533780">s2.</span>
  <span m="2534320">And</span> <span m="2534610">because</span> <span m="2534830">that</span>
  <span m="2535390">was</span> <span m="2535590">an</span> <span m="2536085">overconsistent</span>
  <span m="2536580">case,</span> <span m="2536970">we</span> <span m="2537070">can</span>
  <span m="2537080">just</span> <span m="2537260">set</span> <span m="2537610">g</span>
  <span m="2538050">to be equal</span> <span m="2538430">to</span> <span m="2538570">our</span>
  <span m="2538760">rhs</span> <span m="2539120">value.</span> <span m="2540040">We</span>
  <span m="2540330">then</span> <span m="2540550">have</span> <span m="2541480">to</span>
  <span m="2541730">propagate that to its</span> <span m="2541880">predecessors,</span>
  <span m="2542900">which</span> <span m="2543080">includes</span> <span m="2543650">s1,</span>
  <span m="2544730">which has</span> <span m="2544980">updated</span> <span m="2545140">its</span>
  <span m="2545400">rhs</span> <span m="2545660">value.</span></p><p><span m="2547490">So</span>
  <span m="2547760">if we</span> <span m="2547880">didn't</span> <span m="2548120">do</span>
  <span m="2548330">this,</span> <span m="2548810">we</span> <span m="2550220">wouldn't</span>
  <span m="2550930">have</span> <span m="2551210">handled</span> <span m="2551690">this</span>
  <span m="2551870">effect</span> <span m="2552200">correctly.</span> <span m="2554420">When</span>
  <span m="2554540">we</span> <span m="2554660">set</span> <span m="2554890">our</span>
  <span m="2555140">rhs</span> <span m="2555450">value</span> <span m="2555830">here,</span>
  <span m="2556530">we then have</span> <span m="2556700">to</span> <span m="2557090">put</span>
  <span m="2557390">this</span> <span m="2557820">node</span> <span m="2558380">back</span>
  <span m="2558710">on</span> <span m="2558890">the</span> <span m="2558950">queue.</span>
  <span m="2559890">So</span> <span m="2560120">previously,</span> <span m="2562300">s1</span>
  <span m="2562550">was</span> <span m="2563270">already</span> <span m="2563690">on</span>
  <span m="2563860">the</span> <span m="2563990">queue,</span> <span m="2564460">but</span>
  <span m="2564770">the</span> <span m="2564920">effect</span> <span m="2565220">has</span>
  <span m="2565370">to</span> <span m="2565440">be</span> <span m="2565580">propagated</span>
  <span m="2565940">to</span> <span m="2566300">this</span> <span m="2566550">node,</span>
  <span m="2567110">which</span> <span m="2567290">puts</span> <span m="2567590">it</span>
  <span m="2567740">on</span> <span m="2567950">the</span> <span m="2568010">queue</span>
  <span m="2568250">again,</span> <span m="2569030">which</span> <span m="2569190">would</span>
  <span m="2569340">mean</span> <span m="2570170">adjusting</span> <span m="2570770">the
  values,</span> <span m="2571460">because</span> <span m="2571760">rhs</span> <span
  m="2572010">has</span> <span m="2572180">been</span> <span m="2572390">reduced</span>
  <span m="2572720">by</span> <span m="2572900">1.</span> <span m="2573230">Both the</span>
  <span m="2574060">costs</span> <span m="2574310">here have</span> <span m="2574680">been</span>
  <span m="2574810">reduced by</span> <span m="2575170">1.</span></p><p><span m="2576580">Then</span>
  <span m="2576870">we</span> <span m="2577160">expand</span> <span m="2577680">that</span>
  <span m="2577930">node.</span> <span m="2578930">We</span> <span m="2579110">have
  an</span> <span m="2579550">overconsistent</span> <span m="2579900">case.</span>
  <span m="2580660">We're</span> <span m="2580760">setting</span> <span m="2581070">g</span>
  <span m="2581410">to be</span> <span m="2581775">equal</span> <span m="2582140">to</span>
  <span m="2582540">rhs.</span> <span m="2583310">And</span> <span m="2583430">finally,</span>
  <span m="2584630">we've</span> <span m="2584780">completed</span> <span m="2585190">our</span>
  <span m="2585290">graph search</span> <span m="2585500">problem.</span> <span m="2589120">So</span>
  <span m="2589260">now</span> <span m="2589620">what we</span> <span m="2589710">have</span>
  <span m="2589890">to</span> <span m="2589980">handle</span> <span m="2590470">is
  an</span> <span m="2590580">additional</span> <span m="2591090">complication</span>
  <span m="2591840">that</span> <span m="2591960">occurs</span> <span m="2592440">between</span>
  <span m="2592980">several</span> <span m="2593460">steps,</span> <span m="2594260">tracking</span>
  <span m="2594670">how our</span> <span m="2595065">heuristics have</span> <span
  m="2595460">changed.</span></p><p><span m="2597810">So</span> <span m="2598290">we</span>
  <span m="2598810">want</span> <span m="2599070">to</span> <span m="2599430">carry
  over</span> <span m="2599820">prior</span> <span m="2600210">queue,</span> <span
  m="2600560">which was</span> <span m="2601020">what was</span> <span m="2601110">mentioned</span>
  <span m="2601440">previously,</span> <span m="2602420">between</span> <span m="2602750">our
  different</span> <span m="2603040">searches</span> <span m="2603530">as</span> <span
  m="2603720">our</span> <span m="2603840">stock</span> <span m="2604180">node</span>
  <span m="2604510">moves.</span> <span m="2605940">But</span> <span m="2606600">the</span>
  <span m="2606720">problem</span> <span m="2607230">is</span> <span m="2607890">that</span>
  <span m="2608070">we're</span> <span m="2608220">moving</span> <span m="2608790">from</span>
  <span m="2609210">our</span> <span m="2609360">start</span> <span m="2609750">node</span>
  <span m="2610000">to</span> <span m="2610430">a</span> <span m="2610670">different</span>
  <span m="2610880">point.</span> <span m="2611790">Recall</span> <span m="2612160">that
  our</span> <span m="2612270">heuristic</span> <span m="2612900">value</span> <span
  m="2613290">is</span> <span m="2613410">measured</span> <span m="2614220">from</span>
  <span m="2614610">any</span> <span m="2614850">given</span> <span m="2615130">node</span>
  <span m="2615810">to</span> <span m="2616050">the</span> <span m="2616140">stock</span>
  <span m="2616470">node.</span> <span m="2616960">So when</span> <span m="2617280">our</span>
  <span m="2617440">stock node</span> <span m="2617910">has</span> <span m="2618090">changed,</span>
  <span m="2618860">the</span> <span m="2618960">heuristic</span> <span m="2619380">value</span>
  <span m="2620040">is</span> <span m="2620160">not</span> <span m="2620460">going</span>
  <span m="2620610">to</span> <span m="2620730">be</span> <span m="2621150">the</span>
  <span m="2621240">same</span> <span m="2621450">value</span> <span m="2622400">to
  the</span> <span m="2622740">new</span> <span m="2622920">stock</span> <span m="2623040">mode.</span></p><p><span
  m="2624090">So</span> <span m="2624300">we</span> <span m="2624420">want</span>
  <span m="2624840">what's</span> <span m="2625170">already</span> <span m="2625680">on</span>
  <span m="2625890">the</span> <span m="2626010">queue</span> <span m="2626430">to
  be</span> <span m="2626580">comparable</span> <span m="2627630">to</span> <span
  m="2627750">what</span> <span m="2628470">is</span> <span m="2629330">being computed</span>
  <span m="2629770">for our</span> <span m="2630050">new value,</span> <span m="2630260">so</span>
  <span m="2630880">we</span> <span m="2630900">can</span> <span m="2631080">use</span>
  <span m="2631380">the</span> <span m="2631470">math</span> <span m="2631800">and
  the</span> <span m="2631860">algebra</span> <span m="2631930">that</span> <span
  m="2632490">we've</span> <span m="2632590">already</span> <span m="2632840">done.</span>
  <span m="2634500">So</span> <span m="2634860">how</span> <span m="2635010">we</span>
  <span m="2635130">handle</span> <span m="2635580">this</span> <span m="2635790">is</span>
  <span m="2635910">we</span> <span m="2636060">introduce</span> <span m="2636540">something</span>
  <span m="2636930">called</span> <span m="2637170">the</span> <span m="2637290">key</span>
  <span m="2637590">modifier,</span> <span m="2639150">where</span> <span m="2639360">we</span>
  <span m="2639480">move</span> <span m="2639990">from</span> <span m="2640260">the</span>
  <span m="2640350">previous</span> <span m="2640605">start</span> <span m="2640860">node,</span>
  <span m="2641580">which here I</span> <span m="2641850">indicated</span> <span m="2642030">as</span>
  <span m="2642260">s</span> <span m="2642720">last,</span> <span m="2643320">to</span>
  <span m="2643470">the</span> <span m="2643590">new</span> <span m="2643890">start</span>
  <span m="2644180">node,</span> <span m="2645030">all</span> <span m="2645240">the</span>
  <span m="2645430">heuristics</span> <span m="2646170">for</span> <span m="2646470">admissible</span>
  <span m="2647340">heuristic</span> <span m="2647840">are</span> <span m="2648060">lowered</span>
  <span m="2648450">by</span> <span m="2648660">at</span> <span m="2648810">most</span>
  <span m="2649270">a heuristic</span> <span m="2649830">from</span> <span m="2650190">the</span>
  <span m="2650630">last</span> <span m="2651030">start</span> <span m="2651370">node
  to the</span> <span m="2651560">new</span> <span m="2651800">start</span> <span
  m="2652030">node.</span></p><p><span m="2653190">So</span> <span m="2653340">now,</span>
  <span m="2653780">when we</span> <span m="2654070">add</span> <span m="2654400">new</span>
  <span m="2654700">nodes</span> <span m="2655090">to</span> <span m="2655170">the</span>
  <span m="2655260">queue,</span> <span m="2656100">instead</span> <span m="2656520">of</span>
  <span m="2656880">subtracting</span> <span m="2657690">that</span> <span m="2657930">value</span>
  <span m="2658380">from</span> <span m="2658560">everything</span> <span m="2659010">that's</span>
  <span m="2659220">already</span> <span m="2659820">on</span> <span m="2660060">the
  queue,</span> <span m="2660930">what</span> <span m="2661080">we</span> <span m="2661200">do</span>
  <span m="2661350">is</span> <span m="2661530">we</span> <span m="2661650">just</span>
  <span m="2662010">increase</span> <span m="2662570">for</span> <span m="2662870">all</span>
  <span m="2663150">nodes</span> <span m="2663520">that</span> <span m="2663700">we
  put</span> <span m="2664020">on</span> <span m="2664260">the</span> <span m="2664390">queue,</span>
  <span m="2665430">their</span> <span m="2666090">values,</span> <span m="2667260">by</span>
  <span m="2667800">this</span> <span m="2668370">new</span> <span m="2668670">modifier.</span>
  <span m="2669840">Because</span> <span m="2670080">essentially</span> <span m="2670500">when
  we're</span> <span m="2670810">taking</span> <span m="2671370">off</span> <span
  m="2671580">of</span> <span m="2671730">the</span> <span m="2671820">queue,</span>
  <span m="2672360">all</span> <span m="2672570">that</span> <span m="2672660">matters</span>
  <span m="2673080">is</span> <span m="2673170">the</span> <span m="2673290">relative</span>
  <span m="2673760">differences</span> <span m="2674370">between</span> <span m="2674730">the</span>
  <span m="2674820">two.</span> <span m="2675670">And</span> <span m="2675690">so,</span>
  <span m="2676170">instead</span> <span m="2676410">of</span> <span m="2676490">subtracting</span>
  <span m="2676945">a</span> <span m="2677400">value</span> <span m="2677760">from</span>
  <span m="2678180">everything</span> <span m="2678630">on</span> <span m="2678810">the</span>
  <span m="2678970">queue,</span> <span m="2679250">adding</span> <span m="2679595">that</span>
  <span m="2679940">value</span> <span m="2680360">to</span> <span m="2680490">all</span>
  <span m="2680730">new</span> <span m="2681100">values</span> <span m="2681320">that
  occur on the queue</span> <span m="2682220">will achieve</span> <span m="2682490">the</span>
  <span m="2682550">same</span> <span m="2682730">purpose.</span></p><p><span m="2683840">And</span>
  <span m="2684180">so</span> <span m="2684520">our</span> <span m="2684820">key</span>
  <span m="2684950">modifier</span> <span m="2685710">is</span> <span m="2685890">initialized</span>
  <span m="2686340">to</span> <span m="2686490">0</span> <span m="2687160">at</span>
  <span m="2687380">the</span> <span m="2687510">start of the</span> <span m="2687750">algorithm,</span>
  <span m="2688990">and</span> <span m="2689160">is</span> <span m="2689460">increased</span>
  <span m="2690030">every</span> <span m="2690240">time</span> <span m="2690600">that</span>
  <span m="2690810">we</span> <span m="2691350">update</span> <span m="2691880">our</span>
  <span m="2692010">start</span> <span m="2693390">by</span> <span m="2693750">this</span>
  <span m="2693960">new</span> <span m="2694260">value,</span> <span m="2694890">by</span>
  <span m="2695340">the</span> <span m="2695460">heuristic</span> <span m="2695970">between
  the</span> <span m="2696130">last</span> <span m="2696510">start node and the</span>
  <span m="2696900">new</span> <span m="2697310">start</span> <span m="2697560">node.</span>
  <span m="2698430">And</span> <span m="2698520">then</span> <span m="2698610">we</span>
  <span m="2698820">update</span> <span m="2699360">our</span> <span m="2699510">total</span>
  <span m="2699870">cost</span> <span m="2700890">to</span> <span m="2701040">include</span>
  <span m="2701395">the</span> <span m="2701750">edition</span> <span m="2702120">of</span>
  <span m="2702330">the</span> <span m="2702420">key</span> <span m="2702740">modifier</span>
  <span m="2702860">fire</span> <span m="2703530">for</span> <span m="2703780">our</span>
  <span m="2704000">f1</span> <span m="2704210">term.</span></p><p><span m="2706446">So</span>
  <span m="2706900">now</span> <span m="2706960">we've</span> <span m="2707080">covered</span>
  <span m="2707580">all</span> <span m="2707940">of</span> <span m="2708090">the</span>
  <span m="2708630">D*</span> <span m="2709080">Lite</span> <span m="2709510">algorithm</span>
  <span m="2711480">basics.</span> <span m="2711980">And</span> <span m="2712360">we</span>
  <span m="2712560">can</span> <span m="2712710">actually</span> <span m="2713010">walk</span>
  <span m="2713220">through</span> <span m="2713400">the</span> <span m="2713530">slide</span>
  <span m="2713840">that I showed you</span> <span m="2714240">before</span> <span
  m="2715230">with</span> <span m="2715470">the math.</span> <span m="2716490">So</span>
  <span m="2716650">when</span> <span m="2716730">we</span> <span m="2716820">start,</span>
  <span m="2717180">we initialize</span> <span m="2718350">all</span> <span m="2718860">of</span>
  <span m="2718950">our</span> <span m="2719100">g</span> <span m="2719580">values
  to be</span> <span m="2719940">equal</span> <span m="2720180">to infinity,</span>
  <span m="2720450">and</span> <span m="2720720">all of</span> <span m="2720990">our</span>
  <span m="2721110">rhs</span> <span m="2721500">values</span> <span m="2721690">to</span>
  <span m="2721920">be</span> <span m="2722290">equal</span> <span m="2722660">to</span>
  <span m="2722780">infinity,</span> <span m="2723270">except</span> <span m="2723700">at
  the</span> <span m="2723900">goal node.</span> <span m="2724800">And</span> <span
  m="2724890">that's</span> <span m="2725060">to</span> <span m="2725170">ensure</span>
  <span m="2725450">that</span> <span m="2725660">we</span> <span m="2725820">always</span>
  <span m="2726030">have</span> <span m="2726220">a node</span> <span m="2726480">to
  start</span> <span m="2726930">from</span> <span m="2727170">our</span> <span m="2727290">search.</span></p><p><span
  m="2729740">We</span> <span m="2729930">best-first</span> <span m="2730500">search</span>
  <span m="2731380">from the goal</span> <span m="2731700">node</span> <span m="2732180">to</span>
  <span m="2732300">the</span> <span m="2732590">start</span> <span m="2732920">node
  until</span> <span m="2733130">that's</span> <span m="2733290">locally</span> <span
  m="2733710">consistent</span> <span m="2734250">and</span> <span m="2734480">expanded.</span>
  <span m="2735080">We</span> <span m="2735210">should now</span> <span m="2735450">know</span>
  <span m="2735820">what that</span> <span m="2736010">means.</span> <span m="2736780">And</span>
  <span m="2736960">that</span> <span m="2737130">signal</span> <span m="2737730">that</span>
  <span m="2737880">we</span> <span m="2737990">have</span> <span m="2738130">found</span>
  <span m="2738600">our</span> <span m="2738720">best</span> <span m="2738970">path,</span>
  <span m="2740030">we</span> <span m="2740310">move</span> <span m="2740610">according</span>
  <span m="2741000">to</span> <span m="2741150">our</span> <span m="2741240">movement</span>
  <span m="2741630">rule,</span> <span m="2742920">and</span> <span m="2743040">then</span>
  <span m="2743370">if any of our</span> <span m="2743710">edge</span> <span m="2743990">costs</span>
  <span m="2744290">have</span> <span m="2744670">changed,</span> <span m="2745410">we</span>
  <span m="2745590">update</span> <span m="2746040">our</span> <span m="2746160">key</span>
  <span m="2746460">modifier,</span> <span m="2746610">and</span> <span m="2747600">update</span>
  <span m="2748050">our</span> <span m="2748500">rhs</span> <span m="2748740">and
  queue</span> <span m="2749070">positions</span> <span m="2750030">for</span> <span
  m="2750180">the</span> <span m="2750300">source</span> <span m="2750565">nodes</span>
  <span m="2750830">of</span> <span m="2751320">change</span> <span m="2751710">in
  edge</span> <span m="2752160">costs,</span> <span m="2752790">meaning</span> <span
  m="2753120">the</span> <span m="2753250">nodes</span> <span m="2753540">from</span>
  <span m="2753780">which</span> <span m="2754120">those</span> <span m="2754510">edges</span>
  <span m="2755120">originated.</span></p><p><span m="2756840">And</span> <span m="2756990">then,</span>
  <span m="2757440">we</span> <span m="2757650">simply</span> <span m="2758040">repeat</span>
  <span m="2758550">from two,</span> <span m="2759240">following</span> <span m="2759540">best-first</span>
  <span m="2759810">through the</span> <span m="2760560">principles</span> <span m="2762420">that</span>
  <span m="2762670">I've</span> <span m="2762780">walked</span> <span m="2763020">you</span>
  <span m="2763170">through</span> <span m="2763780">for</span> <span m="2763920">overconsistent</span>
  <span m="2764230">and</span> <span m="2764770">underconsistent</span> <span m="2765440">nodes.</span>
  <span m="2766390">And</span> <span m="2766770">as</span> <span m="2766920">a</span>
  <span m="2767215">reminder</span> <span m="2767510">down here,</span> <span m="2768090">we</span>
  <span m="2768210">always</span> <span m="2768600">search</span> <span m="2769530">or</span>
  <span m="2770010">sort</span> <span m="2770850">by</span> <span m="2771020">this</span>
  <span m="2771220">very</span> <span m="2771570">long</span> <span m="2772560">couplet</span>
  <span m="2772950">of</span> <span m="2773370">two</span> <span m="2773790">values.</span></p><p><span
  m="2775050">So</span> <span m="2775590">now,</span> <span m="2775860">we're</span>
  <span m="2775920">going</span> <span m="2776040">to</span> <span m="2776130">walk
  through</span> <span m="2776440">an</span> <span m="2776550">example</span> <span
  m="2776960">of</span> <span m="2777250">[INAUDIBLE].</span></p><p><span m="2783440">JESS
  NOSS:</span> <span m="2783850">OK.</span> <span m="2787434">So again,</span> <span
  m="2787890">here's</span> <span m="2787960">the</span> <span m="2788313">pseudo</span>
  <span m="2788666">code</span> <span m="2789020">that</span> <span m="2789110">Ben
  was</span> <span m="2789370">just</span> <span m="2789550">presenting.</span> <span
  m="2790530">And</span> <span m="2790960">we're</span> <span m="2791390">going to</span>
  <span m="2791820">go through</span> <span m="2792250">a quick</span> <span m="2792500">example</span>
  <span m="2792990">with</span> <span m="2793200">five</span> <span m="2793510">nodes,</span>
  <span m="2794870">so</span> <span m="2794990">this</span> <span m="2795140">isn't</span>
  <span m="2795380">going</span> <span m="2795650">to</span> <span m="2795800">show</span>
  <span m="2796100">all</span> <span m="2796400">of</span> <span m="2796480">the</span>
  <span m="2796760">properties</span> <span m="2797330">of</span> <span m="2797690">why</span>
  <span m="2798020">you</span> <span m="2798080">would</span> <span m="2798260">want</span>
  <span m="2798440">to</span> <span m="2798500">use</span> <span m="2798680">incremental</span>
  <span m="2799190">path</span> <span m="2799440">planning,</span> <span m="2799790">because</span>
  <span m="2800120">when you</span> <span m="2800240">have</span> <span m="2800450">only</span>
  <span m="2800630">five</span> <span m="2800900">nodes,</span> <span m="2801160">you're</span>
  <span m="2801230">going</span> <span m="2801350">to</span> <span m="2801410">end</span>
  <span m="2801590">updating</span> <span m="2802290">a</span> <span m="2802460">lot</span>
  <span m="2802670">of</span> <span m="2802900">them a lot of</span> <span m="2803060">the
  time.</span> <span m="2803760">But</span> <span m="2804060">after</span> <span m="2804240">the</span>
  <span m="2804360">example,</span> <span m="2804580">you'll</span> <span m="2804980">see</span>
  <span m="2805640">how</span> <span m="2805990">it makes</span> <span m="2806130">more
  of</span> <span m="2806370">a</span> <span m="2806540">difference</span> <span m="2806860">on
  a</span> <span m="2806930">larger</span> <span m="2807260">graph.</span></p><p><span
  m="2808510">So in</span> <span m="2808740">this graph, we're</span> <span m="2809040">going</span>
  <span m="2809220">to</span> <span m="2809300">have</span> <span m="2810320">prior
  nodes</span> <span m="2810635">that</span> <span m="2810950">go</span> <span m="2811160">A,
  B, C, D,</span> <span m="2812660">and</span> <span m="2813080">G</span> <span m="2813440">is</span>
  <span m="2813530">our goal node.</span> <span m="2813970">The</span> <span m="2814110">robot</span>
  <span m="2814380">will start</span> <span m="2814650">at</span> <span m="2815000">node</span>
  <span m="2815280">A,</span> <span m="2815690">and its</span> <span m="2816070">goal</span>
  <span m="2816440">is</span> <span m="2816630">to find the</span> <span m="2816690">shortest</span>
  <span m="2816870">path</span> <span m="2817220">to</span> <span m="2817580">node</span>
  <span m="2817940">G,</span> <span m="2818480">except</span> <span m="2818600">that
  the</span> <span m="2818690">graph might</span> <span m="2819260">change</span>
  <span m="2819555">as</span> <span m="2819850">the</span> <span m="2820150">robot</span>
  <span m="2820280">goes</span> <span m="2820520">through,</span> <span m="2820880">or
  the</span> <span m="2820940">robot</span> <span m="2821160">might</span> <span m="2821350">gain</span>
  <span m="2821780">new</span> <span m="2822080">information.</span></p><p><span m="2823670">So
  initially,</span> <span m="2824060">the robot thinks</span> <span m="2824270">that</span>
  <span m="2825290">every</span> <span m="2825570">node</span> <span m="2826070">is</span>
  <span m="2826250">available.</span> <span m="2827420">And</span> <span m="2827520">it</span>
  <span m="2827620">knows</span> <span m="2827690">that</span> <span m="2827840">the</span>
  <span m="2827960">path</span> <span m="2828260">lengths</span> <span m="2828560">are</span>
  <span m="2828680">all</span> <span m="2828890">1,</span> <span m="2829160">except</span>
  <span m="2829460">for</span> <span m="2829940">from</span> <span m="2830270">D</span>
  <span m="2830600">to G,</span> <span m="2830865">the</span> <span m="2831130">path
  length</span> <span m="2831370">is</span> <span m="2831690">10.</span> <span m="2832676">So
  this is a</span> <span m="2833170">bi-directional</span> <span m="2833930">graph.</span>
  <span m="2834230">Every</span> <span m="2834470">edge</span> <span m="2834740">goes</span>
  <span m="2835130">both</span> <span m="2835340">directions.</span> <span m="2836610">And</span>
  <span m="2836960">the</span> <span m="2837370">heuristic,</span> <span m="2837590">as</span>
  <span m="2837730">Ben</span> <span m="2838070">described,</span> <span m="2838580">will</span>
  <span m="2839990">be</span> <span m="2840680">with</span> <span m="2841430">respect</span>
  <span m="2841780">to</span> <span m="2841910">the</span> <span m="2842150">start</span>
  <span m="2842510">node.</span> <span m="2843200">In</span> <span m="2843300">this</span>
  <span m="2843450">case,</span> <span m="2843670">we'll just</span> <span m="2843900">say</span>
  <span m="2844170">that</span> <span m="2844290">the</span> <span m="2844760">heuristic
  is the</span> <span m="2844850">number</span> <span m="2845210">of</span> <span
  m="2845300">nodes</span> <span m="2845870">to the start</span> <span m="2846260">node.</span>
  <span m="2846380">So we're</span> <span m="2846890">ignoring</span> <span m="2847250">the</span>
  <span m="2847310">fact</span> <span m="2847670">that</span> <span m="2847880">this</span>
  <span m="2848060">edge length</span> <span m="2848510">is</span> <span m="2848670">10.</span></p><p><span
  m="2849825">So</span> <span m="2850340">first,</span> <span m="2850610">we'll initialize</span>
  <span m="2852080">all</span> <span m="2852350">the</span> <span m="2852810">g</span>
  <span m="2853125">and</span> <span m="2853440">rhs</span> <span m="2853640">values.</span>
  <span m="2854510">So</span> <span m="2854600">we</span> <span m="2854750">have</span>
  <span m="2855170">infinity</span> <span m="2855460">at</span> <span m="2855750">every</span>
  <span m="2856110">node,</span> <span m="2856560">except</span> <span m="2856820">for</span>
  <span m="2857210">the</span> <span m="2857330">goal</span> <span m="2857620">node,</span>
  <span m="2857820">which</span> <span m="2858060">has</span> <span m="2858190">an</span>
  <span m="2858410">rhs</span> <span m="2858640">value</span> <span m="2858950">of</span>
  <span m="2859290">0.</span> <span m="2860480">So</span> <span m="2860570">this</span>
  <span m="2860720">means</span> <span m="2861020">that</span> <span m="2861290">all</span>
  <span m="2861500">of the</span> <span m="2861700">nodes</span> <span m="2861920">are</span>
  <span m="2861980">correctly</span> <span m="2862400">locally</span> <span m="2862790">consistent,</span>
  <span m="2863420">because</span> <span m="2863690">their</span> <span m="2863820">g</span>
  <span m="2863900">and</span> <span m="2864380">rhs</span> <span m="2864620">values</span>
  <span m="2864920">are</span> <span m="2865060">the</span> <span m="2865180">same,</span>
  <span m="2865580">except</span> <span m="2865770">the</span> <span m="2866090">goal</span>
  <span m="2866350">node.</span> <span m="2867270">So</span> <span m="2867420">we</span>
  <span m="2867685">put the</span> <span m="2867950">goal</span> <span m="2868140">node</span>
  <span m="2868470">on the</span> <span m="2868650">queue</span> <span m="2869630">using</span>
  <span m="2870020">the</span> <span m="2871850">formula</span> <span m="2872400">that
  is</span> <span m="2872822">on</span> <span m="2873244">Ben's</span> <span m="2873666">slide,</span>
  <span m="2874088">which I'll put</span> <span m="2874510">here</span> <span m="2874660">for</span>
  <span m="2875100">reference.</span> <span m="2876700">So</span> <span m="2878420">the</span>
  <span m="2878510">key</span> <span m="2883410">is</span> <span m="2883570">going
  to be</span> <span m="2883910">these</span> <span m="2884280">two terms.</span></p><p><span
  m="2884970">First,</span> <span m="2885250">we</span> <span m="2885710">have the</span>
  <span m="2885930">minimum</span> <span m="2886240">of</span> <span m="2888660">g</span>
  <span m="2888860">and rhs</span> <span m="2891380">plus</span> <span m="2891740">the</span>
  <span m="2892120">heuristic</span> <span m="2892360">value</span> <span m="2894100">plus</span>
  <span m="2894820">the</span> <span m="2896670">key</span> <span m="2896860">modifier,</span>
  <span m="2897650">which</span> <span m="2897700">is</span> <span m="2897790">initially</span>
  <span m="2898180">0.</span> <span m="2900220">And</span> <span m="2900370">then</span>
  <span m="2900550">we</span> <span m="2900670">have</span> <span m="2901230">the</span>
  <span m="2901300">second</span> <span m="2901600">term,</span> <span m="2901970">which</span>
  <span m="2901990">is</span> <span m="2902070">just</span> <span m="2902320">the</span>
  <span m="2902410">minimum,</span> <span m="2902870">g</span> <span m="2903060">of</span>
  <span m="2903551">rhs.</span> <span m="2907970">So</span> <span m="2908140">you</span>
  <span m="2908200">can</span> <span m="2908330">see</span> <span m="2908540">how</span>
  <span m="2908750">we</span> <span m="2908870">would get</span> <span m="2909350">3,
  0</span> <span m="2910130">here,</span> <span m="2910580">because</span> <span m="2910953">the</span>
  <span m="2911326">3</span> <span m="2911700">comes from</span> <span m="2911890">the</span>
  <span m="2912180">heuristic,</span> <span m="2912680">and</span> <span m="2912980">everything</span>
  <span m="2913370">else</span> <span m="2913570">was</span> <span m="2913760">0,</span>
  <span m="2914210">so</span> <span m="2914570">we just added a bunch of</span> <span
  m="2914930">0's.</span></p><p><span m="2918348">So</span> <span m="2918826">that's
  everything</span> <span m="2919310">what</span> <span m="2919460">happens</span>
  <span m="2919860">for the</span> <span m="2919970">initialization.</span> <span
  m="2920930">And now we</span> <span m="2921230">have</span> <span m="2922100">one
  node</span> <span m="2922460">on the</span> <span m="2922790">queue.</span> <span
  m="2922950">So we'll</span> <span m="2923230">have</span> <span m="2923450">to dequeue
  first.</span> <span m="2927015">This</span> <span m="2927160">is</span> <span m="2927305">an</span>
  <span m="2927450">easy question.</span></p><p><span m="2927590">AUDIENCE:</span>
  <span m="2927735">The node on the queue.</span></p><p><span m="2928170">JESS NOSS:</span>
  <span m="2928215">The</span> <span m="2928260">one</span> <span m="2928420">node
  on the</span> <span m="2928720">queue.</span> <span m="2929110">So</span> <span
  m="2929490">we</span> <span m="2929970">dequeue G.</span> <span m="2930640">So</span>
  <span m="2931000">we're</span> <span m="2931440">going</span> <span m="2931590">out</span>
  <span m="2931770">to</span> <span m="2931940">update</span> <span m="2932190">its</span>
  <span m="2932460">g value.</span> <span m="2933400">So</span> <span m="2933730">as</span>
  <span m="2933950">Ben said,</span> <span m="2934330">the</span> <span m="2934600">rhs</span>
  <span m="2934870">value is</span> <span m="2935500">sort</span> <span m="2935740">of</span>
  <span m="2935860">a</span> <span m="2935940">look</span> <span m="2936190">ahead.</span>
  <span m="2937180">You</span> <span m="2937510">can</span> <span m="2937620">also</span>
  <span m="2937750">think</span> <span m="2937910">of</span> <span m="2938030">rhs</span>
  <span m="2938240">as</span> <span m="2938550">being</span> <span m="2941950">the</span>
  <span m="2942040">shortest</span> <span m="2942400">path</span> <span m="2942650">that
  we</span> <span m="2942820">found</span> <span m="2943090">so</span> <span m="2943330">far,</span>
  <span m="2944020">and</span> <span m="2944180">G</span> <span m="2944450">is the</span>
  <span m="2944530">guaranteed</span> <span m="2945100">shortest</span> <span m="2945500">path
  to that node.</span> <span m="2946500">So this</span> <span m="2946630">one is</span>
  <span m="2946760">trivial.</span> <span m="2947430">The shortest</span> <span m="2947630">path</span>
  <span m="2948160">from</span> <span m="2948400">this</span> <span m="2948580">node
  to itself</span> <span m="2949420">has</span> <span m="2949560">length</span> <span
  m="2949900">0,</span> <span m="2950800">because</span> <span m="2951220">its the
  same node.</span></p><p><span m="2953140">So</span> <span m="2953260">now</span>
  <span m="2953560">we're going</span> <span m="2953860">to</span> <span m="2954280">update</span>
  <span m="2954683">the</span> <span m="2955086">rhs</span> <span m="2955970">values</span>
  <span m="2956270">and its</span> <span m="2956850">neighbors.</span> <span m="2958970">So</span>
  <span m="2959290">it</span> <span m="2959620">has</span> <span m="2959820">two neighbors,</span>
  <span m="2960220">C and D,</span> <span m="2961110">and in</span> <span m="2961680">each</span>
  <span m="2962080">case,</span> <span m="2962440">the</span> <span m="2962580">rhs</span>
  <span m="2962750">value</span> <span m="2963300">will</span> <span m="2964434">be</span>
  <span m="2964836">the</span> <span m="2965238">minimum--</span> <span m="2970100">this</span>
  <span m="2970220">is</span> <span m="2970340">not</span> <span m="2970890">actual</span>
  <span m="2971190">math,</span> <span m="2971450">but its the</span> <span m="2971570">minimum</span>
  <span m="2972670">of</span> <span m="2973610">the</span> <span m="2974080">edge</span>
  <span m="2974400">cost,</span> <span m="2975420">the</span> <span m="2975560">d</span>
  <span m="2975770">value</span> <span m="2976280">of</span> <span m="2976430">a</span>
  <span m="2976490">neighbor</span> <span m="2978090">plus</span> <span m="2978470">the</span>
  <span m="2978560">edge</span> <span m="2978910">cost.</span> <span m="2982590">Which</span>
  <span m="2982770">is</span> <span m="2982860">the</span> <span m="2982950">same</span>
  <span m="2983250">thing</span> <span m="2983670">as</span> <span m="2984030">the</span>
  <span m="2984120">edge</span> <span m="2984390">weight</span> <span m="2984960">or</span>
  <span m="2985980">the</span> <span m="2986070">weight</span> <span m="2986320">w.</span></p><p><span
  m="2988730">So</span> <span m="2988920">we</span> <span m="2989580">rhs</span> <span
  m="2989850">is</span> <span m="2990140">10</span> <span m="2991370">here,</span>
  <span m="2991710">because</span> <span m="2992050">it's the</span> <span m="2992300">distance</span>
  <span m="2992595">from</span> <span m="2992890">g to do,</span> <span m="2993180">and</span>
  <span m="2993400">then it's</span> <span m="2993810">one,</span> <span m="2994990">which</span>
  <span m="2995230">is</span> <span m="2995650">G to C.</span> <span m="2997010">So</span>
  <span m="2997140">again,</span> <span m="2997350">we</span> <span m="2997410">can</span>
  <span m="2997590">calculate</span> <span m="2998100">keys</span> <span m="2998430">for</span>
  <span m="2998580">those.</span> <span m="2999800">So</span> <span m="2999950">now
  we'll</span> <span m="3000170">dequeue</span> <span m="3000510">another</span> <span
  m="3000710">node.</span> <span m="3001100">What</span> <span m="3001550">should
  we</span> <span m="3001740">dequeue</span> <span m="3002227">next?</span></p><p><span
  m="3005636">AUDIENCE:</span> <span m="3005879">C.</span></p><p><span m="3006610">JESS
  NOSS:</span> <span m="3006680">C.</span> <span m="3006750">Because</span> <span
  m="3006820">it</span> <span m="3006890">has</span> <span m="3006960">a</span> <span
  m="3007330">smaller</span> <span m="3007750">key.</span> <span m="3009450">So we
  dequeue</span> <span m="3010060">C.</span> <span m="3010630">We update</span> <span
  m="3010890">its</span> <span m="3011020">g value.</span> <span m="3011400">So this
  is</span> <span m="3011670">saying,</span> <span m="3013020">now</span> <span m="3013190">we</span>
  <span m="3013250">know</span> <span m="3013580">that</span> <span m="3014810">the</span>
  <span m="3014990">shortest</span> <span m="3015380">path</span> <span m="3015680">to</span>
  <span m="3015770">C</span> <span m="3016340">actually</span> <span m="3016760">has
  length</span> <span m="3017240">1.</span> <span m="3018640">And</span> <span m="3018740">we</span>
  <span m="3018830">can</span> <span m="3018950">also</span> <span m="3019310">compare</span>
  <span m="3019520">this</span> <span m="3020220">to</span> <span m="3020510">A*</span>
  <span m="3020800">star</span> <span m="3021020">algorithm</span> <span m="3021690">by</span>
  <span m="3021830">drawing</span> <span m="3022150">a</span> <span m="3022180">search</span>
  <span m="3022510">tree.</span> <span m="3023760">So</span> <span m="3023840">in</span>
  <span m="3023930">the</span> <span m="3023990">beginning,</span> <span m="3024810">we</span>
  <span m="3024900">had</span> <span m="3026740">A*.</span></p><p><span m="3034010">In</span>
  <span m="3034110">the</span> <span m="3034200">beginning,</span> <span m="3034640">we</span>
  <span m="3034930">just</span> <span m="3035100">had</span> <span m="3035460">node</span>
  <span m="3035770">G,</span> <span m="3036180">because</span> <span m="3036370">we
  were</span> <span m="3036470">searching</span> <span m="3036920">from</span> <span
  m="3037150">G</span> <span m="3037580">backward</span> <span m="3037840">through
  the goal.</span> <span m="3039780">And</span> <span m="3040460">then</span> <span
  m="3040650">we</span> <span m="3040860">expanded</span> <span m="3041270">that</span>
  <span m="3041380">back</span> <span m="3043470">to</span> <span m="3043590">get</span>
  <span m="3044010">C</span> <span m="3046020">and</span> <span m="3046200">D.</span>
  <span m="3047200">And</span> <span m="3047420">then A*</span> <span m="3047820">to
  keep</span> <span m="3048030">track</span> <span m="3048390">of</span> <span m="3049350">the</span>
  <span m="3050060">path</span> <span m="3050300">length</span> <span m="3050570">to
  that</span> <span m="3051170">node</span> <span m="3051860">plus</span> <span m="3052260">the</span>
  <span m="3052410">heuristic</span> <span m="3053220">at each node.</span> <span
  m="3053490">So</span> <span m="3053910">the</span> <span m="3054000">pathway</span>
  <span m="3054630">to</span> <span m="3054750">C</span> <span m="3055780">was</span>
  <span m="3056210">1</span> <span m="3056500">plus</span> <span m="3056790">the</span>
  <span m="3056940">heuristic</span> <span m="3057750">2,</span> <span m="3058920">give
  us the</span> <span m="3059230">value of</span> <span m="3059640">3.</span> <span
  m="3060325">So if we</span> <span m="3060700">go</span> <span m="3060960">back</span>
  <span m="3061200">a moment,</span> <span m="3061470">we</span> <span m="3062130">can
  see--</span> <span m="3066018">is that OK?</span></p><p><span m="3069906">So</span>
  <span m="3070400">you can see that</span> <span m="3071190">this</span> <span m="3071430">3</span>
  <span m="3071820">is the same</span> <span m="3072180">as the</span> <span m="3072600">first</span>
  <span m="3072840">point of the</span> <span m="3073020">key,</span> <span m="3074540">and</span>
  <span m="3074900">path</span> <span m="3075130">length</span> <span m="3075720">one</span>
  <span m="3075990">is</span> <span m="3076080">the</span> <span m="3076140">same</span>
  <span m="3076520">as</span> <span m="3076730">the</span> <span m="3077010">second
  part of the key.</span> <span m="3078490">And then</span> <span m="3079490">similarly</span>
  <span m="3080190">at</span> <span m="3080350">D,</span> <span m="3080792">we</span>
  <span m="3081234">have</span> <span m="3081676">the</span> <span m="3082120">path
  length, which</span> <span m="3082680">is</span> <span m="3082830">10,</span> <span
  m="3085595">plus the</span> <span m="3086088">2,</span> <span m="3087570">give us</span>
  <span m="3088980">12.</span> <span m="3089685">So</span> <span m="3089940">this</span>
  <span m="3090210">12</span> <span m="3090480">is</span> <span m="3090940">the</span>
  <span m="3091400">12</span> <span m="3091860">here, and then the</span> <span m="3092350">10</span>
  <span m="3092560">is</span> <span m="3092870">the path length.</span></p><p><span
  m="3094702">And</span> <span m="3095160">so</span> <span m="3095310">you</span>
  <span m="3095460">can</span> <span m="3095550">see</span> <span m="3095760">how</span>
  <span m="3096030">if</span> <span m="3096260">we</span> <span m="3096330">were</span>
  <span m="3096450">doing</span> <span m="3096760">this</span> <span m="3097170">the</span>
  <span m="3097465">A*,</span> <span m="3097760">you would</span> <span m="3098150">also</span>
  <span m="3098730">dequeue</span> <span m="3099110">C</span> <span m="3099440">next.</span>
  <span m="3106048">OK.</span> <span m="3106530">So</span> <span m="3106790">now,</span>
  <span m="3107030">we</span> <span m="3107320">dequeue</span> <span m="3107450">C,</span>
  <span m="3107840">and</span> <span m="3108200">we're</span> <span m="3108290">going</span>
  <span m="3108620">to</span> <span m="3108950">update</span> <span m="3110170">the</span>
  <span m="3110380">rhs</span> <span m="3110670">and its</span> <span m="3110960">neighbors.</span>
  <span m="3112460">So</span> <span m="3112700">B is pretty</span> <span m="3112960">simple.</span>
  <span m="3113520">Previously,</span> <span m="3113830">it's</span> <span m="3114090">rhs</span>
  <span m="3114410">was</span> <span m="3114710">infinity.</span> <span m="3114990">Now</span>
  <span m="3115265">the shortest</span> <span m="3115850">path</span> <span m="3116050">to</span>
  <span m="3116250">B</span> <span m="3116510">that we've</span> <span m="3116660">found</span>
  <span m="3117730">so</span> <span m="3117920">far</span> <span m="3118190">has</span>
  <span m="3118370">length</span> <span m="3118610">2.</span> <span m="3120410">So</span>
  <span m="3120900">here</span> <span m="3121390">we</span> <span m="3121880">have</span>
  <span m="3122220">B</span> <span m="3122300">was</span> <span m="3122570">a</span>
  <span m="3122980">path length</span> <span m="3123750">2,</span> <span m="3124120">plus</span>
  <span m="3124510">a</span> <span m="3124900">heuristic</span> <span m="3125390">of</span>
  <span m="3125540">1</span> <span m="3125795">gives</span> <span m="3126050">us</span>
  <span m="3126370">3.</span></p><p><span m="3129770">But</span> <span m="3130000">what</span>
  <span m="3130305">about</span> <span m="3130610">D?</span> <span m="3130810">Previously,</span>
  <span m="3131090">its rhs value</span> <span m="3131370">was 10,</span> <span m="3132120">but
  do we</span> <span m="3132290">now have</span> <span m="3132590">a</span> <span
  m="3132760">shorter</span> <span m="3132980">path to</span> <span m="3133250">D,</span>
  <span m="3133430">given</span> <span m="3133820">that we're</span> <span m="3135050">expanding</span>
  <span m="3135390">C?</span> <span m="3140150">Or is</span> <span m="3140370">10</span>
  <span m="3140590">still the</span> <span m="3140690">shortest</span> <span m="3140880">path?</span></p><p><span
  m="3143850">AUDIENCE:</span> <span m="3143971">That</span> <span m="3144092">is</span>
  <span m="3144215">the shortest path, through C.</span></p><p><span m="3146380">JESS
  NOSS:</span> <span m="3146570">Yeah.</span> <span m="3146760">So now that we're</span>
  <span m="3147210">expanding C,</span> <span m="3147630">we</span> <span m="3147970">see
  that you</span> <span m="3148290">can</span> <span m="3148440">actually</span> <span
  m="3148770">get</span> <span m="3149000">to</span> <span m="3149260">D</span> <span
  m="3149730">in only</span> <span m="3150060">two</span> <span m="3150320">units
  instead of</span> <span m="3150580">10 units.</span> <span m="3150830">So that's
  better.</span> <span m="3153940">So</span> <span m="3154090">we'll update</span>
  <span m="3154550">the</span> <span m="3154865">rhs</span> <span m="3155520">value</span>
  <span m="3155830">to</span> <span m="3156190">2.</span> <span m="3157780">And</span>
  <span m="3157800">that</span> <span m="3157910">means</span> <span m="3158040">that</span>
  <span m="3158160">we're</span> <span m="3158310">going</span> <span m="3158550">to</span>
  <span m="3158790">change</span> <span m="3161040">D's</span> <span m="3161820">key</span>
  <span m="3162670">accordingly.</span> <span m="3164190">And</span> <span m="3164370">the</span>
  <span m="3164430">way</span> <span m="3164610">that</span> <span m="3165050">maps
  to</span> <span m="3165390">A*</span> <span m="3166380">is,</span> <span m="3166730">so
  if you already have</span> <span m="3167160">the</span> <span m="3167480">path length</span>
  <span m="3167800">is</span> <span m="3168040">2,</span> <span m="3168400">plus the</span>
  <span m="3168655">heuristic</span> <span m="3168910">is</span> <span m="3169550">2,</span>
  <span m="3170055">gives</span> <span m="3170370">us</span> <span m="3170620">4.</span>
  <span m="3171890">And</span> <span m="3172280">the</span> <span m="3172500">fact
  that we're</span> <span m="3172710">changing</span> <span m="3173910">the</span>
  <span m="3174030">key</span> <span m="3174500">to 4, 2</span> <span m="3174790">means</span>
  <span m="3175350">that</span> <span m="3175500">we're</span> <span m="3175650">never</span>
  <span m="3175920">going</span> <span m="3176160">to</span> <span m="3176550">expand
  this D,</span> <span m="3177210">because</span> <span m="3177480">A*</span> <span
  m="3177900">uses</span> <span m="3178200">an</span> <span m="3178290">extended</span>
  <span m="3178770">set,</span> <span m="3179520">so</span> <span m="3179700">it would</span>
  <span m="3179850">always</span> <span m="3180090">expand</span> <span m="3181140">this</span>
  <span m="3181380">D</span> <span m="3182070">with</span> <span m="3182240">a</span>
  <span m="3182400">shorter</span> <span m="3182850">cost</span> <span m="3183420">before</span>
  <span m="3183690">this</span> <span m="3183900">one.</span> <span m="3184810">So</span>
  <span m="3185310">that's</span> <span m="3185690">indicated</span> <span m="3186300">by--</span>
  <span m="3186520">removed by</span> <span m="3186960">changing</span> <span m="3187430">the
  key</span> <span m="3187780">on the queue.</span></p><p><span m="3190400">So</span>
  <span m="3190890">what</span> <span m="3191010">do</span> <span m="3191110">we</span>
  <span m="3191190">do</span> <span m="3191370">next?</span> <span m="3192734">Which
  node</span> <span m="3193206">do we</span> <span m="3193678">dequeue?</span></p><p><span
  m="3197454">AUDIENCE:</span> <span m="3197690">B.</span></p><p><span m="3198398">JESS
  NOSS:</span> <span m="3198639">B?</span> <span m="3198880">Yeah, because it</span>
  <span m="3199100">has the smaller key.</span> <span m="3202710">So</span> <span
  m="3203120">we'll</span> <span m="3203465">dequeue</span> <span m="3203810">B.</span>
  <span m="3204290">We'll update</span> <span m="3204640">its g</span> <span m="3204990">value,</span>
  <span m="3205590">which</span> <span m="3205740">is</span> <span m="3206000">again</span>
  <span m="3206300">saying</span> <span m="3206750">that</span> <span m="3207440">we</span>
  <span m="3207650">know</span> <span m="3208210">now that the</span> <span m="3208310">shortest</span>
  <span m="3208680">path</span> <span m="3208970">to</span> <span m="3209110">B</span>
  <span m="3209300">is</span> <span m="3209480">2.</span> <span m="3211940">So we</span>
  <span m="3212360">dequeue</span> <span m="3212765">B,</span> <span m="3213170">and</span>
  <span m="3213290">then</span> <span m="3213560">we</span> <span m="3214040">expand
  it.</span> <span m="3215480">How many</span> <span m="3215960">neighbors</span>
  <span m="3216440">does B</span> <span m="3216920">have?</span></p><p><span m="3218609">AUDIENCE:</span>
  <span m="3218840">Three.</span></p><p><span m="3220930">JESS NOSS:</span> <span
  m="3221055">Three.</span> <span m="3221180">So</span> <span m="3221470">we're</span>
  <span m="3221570">actually</span> <span m="3222020">expanding</span> <span m="3222920">to
  all three</span> <span m="3223400">of</span> <span m="3223910">those</span> <span
  m="3224110">neighbors.</span> <span m="3225090">We</span> <span m="3225240">have</span>
  <span m="3225730">A,</span> <span m="3227096">C,</span> <span m="3228072">and</span>
  <span m="3228560">D.</span> <span m="3229536">Can we still see this?</span> <span
  m="3231488">We</span> <span m="3231976">can.</span> <span m="3235400">So</span>
  <span m="3235730">at</span> <span m="3235900">A,</span> <span m="3236160">it's</span>
  <span m="3236420">pretty</span> <span m="3236780">simple.</span> <span m="3237150">We</span>
  <span m="3237390">have the</span> <span m="3237570">rhs</span> <span m="3237970">value
  is 3,</span> <span m="3238820">because it's</span> <span m="3239000">the</span>
  <span m="3239120">shortest</span> <span m="3239510">path</span> <span m="3239990">through</span>
  <span m="3240530">GCB</span> <span m="3240900">to</span> <span m="3241270">A.</span>
  <span m="3243470">So</span> <span m="3243710">that's</span> <span m="3244710">3,</span>
  <span m="3245050">plus the</span> <span m="3245360">heuristic</span> <span m="3245890">0</span>
  <span m="3246350">plus</span> <span m="3246570">3.</span></p><p><span m="3249040">What</span>
  <span m="3249180">about--</span> <span m="3251220">oh,</span> <span m="3251540">see,</span>
  <span m="3251840">it</span> <span m="3251900">doesn't</span> <span m="3252200">change,</span>
  <span m="3252650">because--</span> <span m="3254060">you</span> <span m="3254150">could</span>
  <span m="3254360">go</span> <span m="3255160">through</span> <span m="3255520">B</span>
  <span m="3255855">and back to</span> <span m="3256190">C,</span> <span m="3256580">but--</span>
  <span m="3257040">oh,</span> <span m="3257210">C</span> <span m="3257400">shouldn't</span>
  <span m="3257650">actually</span> <span m="3258070">be</span> <span m="3258410">on
  here.</span> <span m="3258740">Sorry.</span> <span m="3260120">C</span> <span m="3260540">shouldn't</span>
  <span m="3260960">be on</span> <span m="3261110">here,</span> <span m="3261290">because</span>
  <span m="3261440">we</span> <span m="3261530">don't</span> <span m="3261710">want</span>
  <span m="3261870">a</span> <span m="3261950">loop in</span> <span m="3262426">our
  path.</span></p><p><span m="3266710">OK.</span> <span m="3267450">So</span> <span
  m="3267830">at</span> <span m="3268210">D,</span> <span m="3268590">can</span> <span
  m="3269080">we</span> <span m="3269200">do</span> <span m="3269350">better</span>
  <span m="3269680">than</span> <span m="3270610">this</span> <span m="3270860">path</span>
  <span m="3271020">length of 2?</span></p><p><span m="3275508">AUDIENCE:</span> <span
  m="3275744">No.</span></p><p><span m="3276930">JESS NOSS:</span> <span m="3277050">No.</span>
  <span m="3277380">Because what</span> <span m="3277540">happened</span> <span m="3277800">was</span>
  <span m="3277920">originally,</span> <span m="3278400">we</span> <span m="3278470">had</span>
  <span m="3278620">the</span> <span m="3278710">path length</span> <span m="3279130">of</span>
  <span m="3279270">10</span> <span m="3279705">through G,</span> <span m="3280140">and</span>
  <span m="3280390">then we</span> <span m="3280530">had</span> <span m="3280660">the</span>
  <span m="3280700">path</span> <span m="3280950">length</span> <span m="3281310">of
  2,</span> <span m="3281640">3</span> <span m="3281870">C,</span> <span m="3282530">and</span>
  <span m="3282740">this</span> <span m="3282880">path through</span> <span m="3283205">B</span>
  <span m="3283530">is</span> <span m="3283650">not</span> <span m="3283860">as good.
  So</span> <span m="3284280">we're going to</span> <span m="3284590">keep</span>
  <span m="3286080">the</span> <span m="3286260">same</span> <span m="3286620">rhs</span>
  <span m="3287085">value and</span> <span m="3287550">key at D.</span> <span m="3290230">And</span>
  <span m="3290330">we</span> <span m="3290450">can</span> <span m="3290600">see</span>
  <span m="3290780">that</span> <span m="3292080">in</span> <span m="3292290">a lot
  of he A*,</span> <span m="3292520">where</span> <span m="3292760">we</span> <span
  m="3292890">would</span> <span m="3293070">have,</span> <span m="3293920">if</span>
  <span m="3294070">we</span> <span m="3294200">did</span> <span m="3294460">do</span>
  <span m="3294720">GCBD,</span> <span m="3296275">we</span> <span m="3297180">would</span>
  <span m="3297350">have</span> <span m="3297540">a</span> <span m="3297600">pathway</span>
  <span m="3298110">of</span> <span m="3298230">3,</span> <span m="3298410">plus the
  heuristic</span> <span m="3298770">of 2</span> <span m="3298920">is</span> <span
  m="3299370">5.</span> <span m="3302160">But</span> <span m="3302310">we</span> <span
  m="3302400">would</span> <span m="3302520">never</span> <span m="3302760">actually</span>
  <span m="3303060">want</span> <span m="3303240">to</span> <span m="3303300">expand</span>
  <span m="3304010">that</span> <span m="3304280">D,</span> <span m="3305170">because</span>
  <span m="3305615">it's not</span> <span m="3306060">as</span> <span m="3306320">good
  as this one.</span></p><p><span m="3308470">OK.</span> <span m="3309330">Now what
  would we</span> <span m="3309610">dequeue?</span> <span m="3310750">Looks</span>
  <span m="3311300">like we</span> <span m="3311510">have</span> <span m="3311760">two
  nodes in our</span> <span m="3312035">queue</span> <span m="3312310">currently.</span></p><p><span
  m="3314944">JOE LEAVITT:</span> <span m="3315187">A.</span></p><p><span m="3316402">JESS
  NOSS:</span> <span m="3316645">A.</span> <span m="3318346">So</span> <span m="3318840">we</span>
  <span m="3319050">dequeue</span> <span m="3319510">A.</span> <span m="3321350">That's</span>
  <span m="3321660">where we trying</span> <span m="3322070">to</span> <span m="3322370">get</span>
  <span m="3322550">to,</span> <span m="3322750">because</span> <span m="3322960">that's
  the current</span> <span m="3323060">start</span> <span m="3323480">node.</span>
  <span m="3324440">So</span> <span m="3324850">we</span> <span m="3325060">set the
  g value</span> <span m="3325200">to</span> <span m="3325460">3,</span> <span m="3326090">which</span>
  <span m="3326910">means</span> <span m="3327260">that that's</span> <span m="3327770">actually</span>
  <span m="3328070">the</span> <span m="3328160">shortest</span> <span m="3328590">path.</span>
  <span m="3330410">And</span> <span m="3330580">we're</span> <span m="3330980">done.</span>
  <span m="3331540">We</span> <span m="3331860">found the</span> <span m="3332180">shortest</span>
  <span m="3332640">path.</span> <span m="3332960">Well, we're done,</span> <span
  m="3333230">except</span> <span m="3333530">that</span> <span m="3334250">the</span>
  <span m="3334340">path</span> <span m="3334590">might</span> <span m="3334790">have
  to</span> <span m="3335050">change.</span> <span m="3335920">So</span> <span m="3336090">one</span>
  <span m="3336210">thing</span> <span m="3336390">you</span> <span m="3336440">notice</span>
  <span m="3336830">here</span> <span m="3337160">is</span> <span m="3337280">that</span>
  <span m="3337430">we</span> <span m="3337550">never</span> <span m="3337790">have</span>
  <span m="3337980">to</span> <span m="3338130">actually</span> <span m="3338760">set</span>
  <span m="3339170">D's</span> <span m="3339490">g</span> <span m="3339810">value.</span>
  <span m="3340550">So</span> <span m="3340750">it's</span> <span m="3340860">possible,</span>
  <span m="3341310">maybe</span> <span m="3341630">there's</span> <span m="3342240">still
  a</span> <span m="3342890">shorter</span> <span m="3343220">path</span> <span m="3343490">to</span>
  <span m="3343580">D,</span> <span m="3343910">but it</span> <span m="3344000">doesn't</span>
  <span m="3344270">matter.</span> <span m="3346720">So</span> <span m="3346930">now</span>
  <span m="3347090">the</span> <span m="3347490">robot will</span> <span m="3347890">move</span>
  <span m="3348320">to</span> <span m="3348560">its</span> <span m="3348920">next</span>
  <span m="3349160">best</span> <span m="3349970">place,</span> <span m="3350420">which
  is</span> <span m="3350660">B,</span> <span m="3351433">and</span> <span m="3351876">we'll</span>
  <span m="3352320">update</span> <span m="3352560">the heuristics</span> <span m="3352925">accordingly,</span>
  <span m="3353290">because</span> <span m="3354200">this</span> <span m="3354350">is</span>
  <span m="3354500">our</span> <span m="3354620">new</span> <span m="3354930">start</span>
  <span m="3355230">node.</span></p><p><span m="3355480">So</span> <span m="3355630">now,</span>
  <span m="3356370">again,</span> <span m="3356590">our</span> <span m="3357260">heuristic</span>
  <span m="3357860">is</span> <span m="3358080">the</span> <span m="3358160">number</span>
  <span m="3358430">of</span> <span m="3358520">nodes</span> <span m="3358820">away</span>
  <span m="3359260">from that</span> <span m="3359470">green</span> <span m="3359650">node.</span>
  <span m="3361460">And</span> <span m="3361550">we're</span> <span m="3361670">keeping</span>
  <span m="3362210">the</span> <span m="3362300">same</span> <span m="3362570">items</span>
  <span m="3362990">on the</span> <span m="3363140">queue</span> <span m="3363320">from</span>
  <span m="3363470">before.</span> <span m="3365850">But</span> <span m="3365930">we</span>
  <span m="3366050">also</span> <span m="3366320">have</span> <span m="3366530">to</span>
  <span m="3367200">update</span> <span m="3367540">the</span> <span m="3368010">key</span>
  <span m="3368480">modifier.</span> <span m="3369890">So now</span> <span m="3370240">what</span>
  <span m="3370505">happens is an</span> <span m="3370770">obstacle</span> <span m="3371140">appears.</span>
  <span m="3371750">So there's</span> <span m="3372120">an</span> <span m="3372450">obstacle</span>
  <span m="3372800">at</span> <span m="3373125">C</span> <span m="3373450">that</span>
  <span m="3373770">the</span> <span m="3374070">robot</span> <span m="3374370">can</span>
  <span m="3374736">now</span> <span m="3375102">see</span> <span m="3375470">because
  it's moved</span> <span m="3375890">closer</span> <span m="3376140">to</span> <span
  m="3376340">node</span> <span m="3376640">C,</span> <span m="3376780">but it couldn't</span>
  <span m="3377120">see it</span> <span m="3377560">before.</span></p><p><span m="3379320">So</span>
  <span m="3380660">now,</span> <span m="3380850">we're</span> <span m="3380970">going</span>
  <span m="3381120">to</span> <span m="3381190">indicate</span> <span m="3381940">that</span>
  <span m="3382300">by</span> <span m="3382580">keeping</span> <span m="3382900">all</span>
  <span m="3383060">the</span> <span m="3383180">edges,</span> <span m="3383650">but</span>
  <span m="3383720">changing</span> <span m="3384140">their</span> <span m="3384270">rates</span>
  <span m="3384610">to</span> <span m="3384780">infinity.</span> <span m="3386070">And</span>
  <span m="3386170">that</span> <span m="3386210">means</span> <span m="3386510">that</span>
  <span m="3386870">the</span> <span m="3386960">robot</span> <span m="3387260">could</span>
  <span m="3387440">try</span> <span m="3387620">to</span> <span m="3387710">get</span>
  <span m="3387850">to</span> <span m="3387980">see,</span> <span m="3388350">but
  it</span> <span m="3388440">wouldn't</span> <span m="3388670">ever</span> <span
  m="3388870">get</span> <span m="3389120">there.</span> <span m="3390840">So</span>
  <span m="3390930">what we do</span> <span m="3391130">next</span> <span m="3391420">in
  the</span> <span m="3391670">algorithm</span> <span m="3391950">is</span> <span
  m="3392930">we're</span> <span m="3393140">going</span> <span m="3393410">to</span>
  <span m="3393740">update</span> <span m="3394130">all</span> <span m="3394460">of
  the</span> <span m="3394700">rhs</span> <span m="3394980">values</span> <span m="3395410">associated</span>
  <span m="3396170">with</span> <span m="3396790">the</span> <span m="3397100">source</span>
  <span m="3397660">nodes</span> <span m="3397990">of</span> <span m="3398295">these</span>
  <span m="3398600">edges.</span> <span m="3398690">And in this</span> <span m="3398840">case,</span>
  <span m="3399140">the</span> <span m="3399320">edges</span> <span m="3399470">go</span>
  <span m="3399620">both</span> <span m="3399860">directions,</span> <span m="3400430">so</span>
  <span m="3400660">all</span> <span m="3400930">four of</span> <span m="3401330">these</span>
  <span m="3402110">nodes</span> <span m="3402380">are</span> <span m="3402500">affected</span>
  <span m="3402890">by</span> <span m="3403060">the infinities.</span></p><p><span
  m="3405300">So</span> <span m="3405440">let's</span> <span m="3405770">start</span>
  <span m="3406060">with node</span> <span m="3406520">C.</span> <span m="3406820">What</span>
  <span m="3406960">would</span> <span m="3407100">be</span> <span m="3407570">its</span>
  <span m="3407930">new</span> <span m="3408200">rhs</span> <span m="3408470">value,</span>
  <span m="3408800">given</span> <span m="3408930">that</span> <span m="3409130">rhs</span>
  <span m="3409700">is</span> <span m="3410030">the</span> <span m="3410260">minimum</span>
  <span m="3411830">from</span> <span m="3412400">one</span> <span m="3412610">of</span>
  <span m="3412700">its</span> <span m="3412850">neighbors</span> <span m="3414110">to</span>
  <span m="3414290">it</span> <span m="3414590">of the</span> <span m="3414710">g
  plus</span> <span m="3415340">edge</span> <span m="3415580">cost?</span></p><p><span
  m="3418540">AUDIENCE:</span> <span m="3418755">Infinity.</span></p><p><span m="3419400">JESS
  NOSS:</span> <span m="3419580">Infinity.</span> <span m="3419760">because</span>
  <span m="3419990">all of the</span> <span m="3420140">edge</span> <span m="3420450">costs</span>
  <span m="3420745">going to C</span> <span m="3421040">are</span> <span m="3421360">infinity.</span>
  <span m="3423290">So</span> <span m="3423470">what</span> <span m="3423560">would</span>
  <span m="3423710">be</span> <span m="3424220">the</span> <span m="3424400">key?</span>
  <span m="3426570">The tricky part</span> <span m="3427140">here</span> <span m="3427340">is</span>
  <span m="3427460">the</span> <span m="3427520">first</span> <span m="3427760">part
  of the key is</span> <span m="3428160">the</span> <span m="3428600">minimum</span>
  <span m="3428940">of g</span> <span m="3429200">and</span> <span m="3429510">rhs.</span>
  <span m="3436184">So</span> <span m="3436662">the</span> <span m="3437140">minimum</span>
  <span m="3437618">of</span> <span m="3438100">g or rhs</span> <span m="3438600">is</span>
  <span m="3438830">what?</span></p><p><span m="3440534">AUDIENCE:</span> <span m="3440676">So</span>
  <span m="3440818">it'd</span> <span m="3440960">be</span> <span m="3441060">3,</span>
  <span m="3441460">1?</span> <span m="3443118">Yeah.</span></p><p><span m="3443986">JESS
  NOSS:</span> <span m="3444203">Yeah,</span> <span m="3444770">3,</span> <span m="3445040">1,</span>
  <span m="3445340">because</span> <span m="3447570">the</span> <span m="3447670">minimum</span>
  <span m="3448070">of</span> <span m="3448540">g and rhs</span> <span m="3448940">is</span>
  <span m="3449050">g,</span> <span m="3449440">which is</span> <span m="3449660">1.</span>
  <span m="3450020">The</span> <span m="3450410">heuristic</span> <span m="3450710">is
  1,</span> <span m="3451010">and</span> <span m="3451820">the</span> <span m="3451910">key</span>
  <span m="3452090">modifier</span> <span m="3452660">is</span> <span m="3452810">1.</span>
  <span m="3454130">OK.</span> <span m="3454370">How</span> <span m="3454550">about</span>
  <span m="3454970">node</span> <span m="3455200">B?</span> <span m="3455530">What's
  the</span> <span m="3455720">new</span> <span m="3456060">rhs</span> <span m="3456370">value?</span>
  <span m="3460350">So it has</span> <span m="3460930">a</span> <span m="3461830">neighbor</span>
  <span m="3462250">here</span> <span m="3462490">with</span> <span m="3462660">g
  as</span> <span m="3463010">infinity,</span> <span m="3463690">a</span> <span m="3463770">neighbor</span>
  <span m="3464080">here</span> <span m="3464390">of g is</span> <span m="3464720">1,</span>
  <span m="3464910">except the edge length is</span> <span m="3465170">infinity.</span>
  <span m="3466454">And</span> <span m="3466906">then this</span> <span m="3467360">guy</span>
  <span m="3467770">with g</span> <span m="3468190">is 3.</span></p><p><span m="3472861">AUDIENCE:</span>
  <span m="3473020">So</span> <span m="3473179">it's</span> <span m="3473340">infinity,</span>
  <span m="3473819">4?</span></p><p><span m="3475740">JESS NOSS:</span> <span m="3475965">4.</span>
  <span m="3476810">Yeah,</span> <span m="3477120">because</span> <span m="3477510">currently,</span>
  <span m="3478370">we</span> <span m="3478490">still</span> <span m="3478720">think</span>
  <span m="3479100">that</span> <span m="3479640">you</span> <span m="3479730">can</span>
  <span m="3479880">get to</span> <span m="3480180">A</span> <span m="3480590">and</span>
  <span m="3480940">B</span> <span m="3481290">units.</span> <span m="3482100">So</span>
  <span m="3483150">this</span> <span m="3483300">is</span> <span m="3483420">actually</span>
  <span m="3483690">going to</span> <span m="3483990">be 4.</span> <span m="3484400">So</span>
  <span m="3484410">this</span> <span m="3484560">is</span> <span m="3484680">one</span>
  <span m="3484830">of</span> <span m="3484910">the</span> <span m="3485000">sillier</span>
  <span m="3485740">things</span> <span m="3486050">that</span> <span m="3486210">D*</span>
  <span m="3486440">does,</span> <span m="3486910">but</span> <span m="3487110">luckily,</span>
  <span m="3487430">it</span> <span m="3487500">doesn't</span> <span m="3487770">do</span>
  <span m="3487970">this</span> <span m="3488070">very</span> <span m="3488340">much,</span>
  <span m="3488670">so</span> <span m="3489030">it</span> <span m="3489150">doesn't</span>
  <span m="3489390">actually</span> <span m="3490245">really</span> <span m="3490620">cost</span>
  <span m="3490910">too</span> <span m="3491010">much</span> <span m="3491280">time.</span></p><p><span
  m="3492750">And</span> <span m="3492910">then</span> <span m="3493310">how</span>
  <span m="3493660">about</span> <span m="3494020">D?</span> <span m="3494870">What</span>
  <span m="3495300">would be</span> <span m="3495450">the</span> <span m="3495670">new</span>
  <span m="3495910">rhs</span> <span m="3496407">value?</span></p><p><span m="3505860">AUDIENCE:</span>
  <span m="3505953">5,</span> <span m="3506046">3?</span> <span m="3507650">rhs.</span></p><p><span
  m="3509940">JESS NOSS:</span> <span m="3510065">So</span> <span m="3510780">it</span>
  <span m="3510800">has</span> <span m="3511190">been</span> <span m="3511460">3</span>
  <span m="3511650">neighbors.</span> <span m="3512480">This</span> <span m="3512800">edge</span>
  <span m="3513115">length</span> <span m="3513430">is</span> <span m="3513560">infinity</span>
  <span m="3513830">is</span> <span m="3513980">useless,</span> <span m="3514250">so
  that's</span> <span m="3514520">useless.</span> <span m="3515500">This</span> <span
  m="3515610">one has</span> <span m="3515905">g of 0</span> <span m="3516200">plus</span>
  <span m="3516510">10 would</span> <span m="3517380">be</span> <span m="3517510">10.</span>
  <span m="3518450">Yes,</span> <span m="3518720">so this is</span> <span m="3518870">the</span>
  <span m="3518990">best one.</span> <span m="3519230">G is</span> <span m="3519500">2,</span>
  <span m="3519610">plus</span> <span m="3519860">edge</span> <span m="3520160">length
  of</span> <span m="3520430">1.</span> <span m="3522490">So</span> <span m="3522915">that
  would give</span> <span m="3523340">us 3.</span> <span m="3524285">So now</span>
  <span m="3524680">what</span> <span m="3524910">do we</span> <span m="3525180">dequeue?</span></p><p><span
  m="3530870">AUDIENCE:</span> <span m="3530915">C?</span></p><p><span m="3531460">JESS
  NOSS:</span> <span m="3531665">C.</span> <span m="3531870">So this</span> <span
  m="3532060">is</span> <span m="3532150">one</span> <span m="3532300">of</span> <span
  m="3532360">those</span> <span m="3532580">tie breaking</span> <span m="3533040">cases,</span>
  <span m="3533520">where</span> <span m="3533680">both</span> <span m="3533920">of</span>
  <span m="3534010">them</span> <span m="3534490">have</span> <span m="3535330">the</span>
  <span m="3535390">first</span> <span m="3535690">value is</span> <span m="3536230">3,</span>
  <span m="3537010">but</span> <span m="3537850">C</span> <span m="3538120">has a
  better</span> <span m="3538220">second value in its</span> <span m="3538430">key,</span>
  <span m="3539100">so</span> <span m="3539490">we'll</span> <span m="3539690">dequeue</span>
  <span m="3539900">C.</span> <span m="3542482">Is</span> <span m="3542890">this</span>
  <span m="3543220">over or</span> <span m="3543720">under</span> <span m="3544472">consistent?</span>
  <span m="3547364">So</span> <span m="3547846">the definitions</span> <span m="3548328">of</span>
  <span m="3548810">over</span> <span m="3549070">and under</span> <span m="3549380">consistent</span>
  <span m="3549980">that</span> <span m="3550110">we</span> <span m="3550260">had</span>
  <span m="3550460">earlier,</span> <span m="3551180">we</span> <span m="3552521">had</span>
  <span m="3554760">if</span> <span m="3555120">g</span> <span m="3555420">is</span>
  <span m="3556140">greater</span> <span m="3556560">than</span> <span m="3557680">rhs,</span>
  <span m="3560360">then that's</span> <span m="3563320">overconsistent,</span> <span
  m="3564680">and</span> <span m="3564810">we</span> <span m="3564950">set</span>
  <span m="3565290">g</span> <span m="3565740">equal to</span> <span m="3565990">rhs</span>
  <span m="3566660">when we're updating</span> <span m="3566960">g.</span> <span m="3567860">So</span>
  <span m="3568080">that was the case that we've</span> <span m="3568170">seen</span>
  <span m="3568410">so</span> <span m="3568620">far.</span> <span m="3570630">But</span>
  <span m="3570750">then</span> <span m="3570950">if</span> <span m="3571110">g</span>
  <span m="3571365">is</span> <span m="3571620">less</span> <span m="3571890">than</span>
  <span m="3572030">rhs,</span> <span m="3573950">it's</span> <span m="3575390">underconsistent,</span>
  <span m="3577960">and</span> <span m="3578200">we</span> <span m="3578290">set</span>
  <span m="3578530">g</span> <span m="3578942">to infinity.</span> <span m="3580180">So</span>
  <span m="3580330">what is this?</span></p><p><span m="3583790">AUDIENCE:</span>
  <span m="3584035">Underconsistent.</span></p><p><span m="3585260">JESS NOSS:</span>
  <span m="3585505">Underconsistent.</span> <span m="3586540">So the</span> <span
  m="3586660">reason</span> <span m="3587190">intuitively</span> <span m="3587850">why</span>
  <span m="3588100">we're going to set</span> <span m="3588210">g</span> <span m="3588580">to
  infinity</span> <span m="3588700">is</span> <span m="3589420">because</span> <span
  m="3589780">we're saying</span> <span m="3590080">there's</span> <span m="3590280">some
  sort</span> <span m="3590560">of</span> <span m="3590690">contradiction</span> <span
  m="3591450">here.</span> <span m="3592110">This</span> <span m="3592310">one</span>
  <span m="3592520">doesn't</span> <span m="3592790">make</span> <span m="3593000">any</span>
  <span m="3593180">sense.</span> <span m="3593610">It's</span> <span m="3593660">less</span>
  <span m="3593900">than</span> <span m="3594030">the</span> <span m="3594100">rhs</span>
  <span m="3594230">value,</span> <span m="3594650">so</span> <span m="3595220">we're</span>
  <span m="3595310">going</span> <span m="3595430">to</span> <span m="3595500">just</span>
  <span m="3596600">reset g</span> <span m="3597060">and</span> <span m="3597150">sort
  of start</span> <span m="3597460">over</span> <span m="3597650">with</span> <span
  m="3597800">this node.</span> <span m="3598760">So we set that to</span> <span m="3599540">infinity.</span></p><p><span
  m="3601080">And</span> <span m="3601130">in</span> <span m="3601190">this</span>
  <span m="3601370">case,</span> <span m="3601640">we</span> <span m="3601730">don't</span>
  <span m="3601970">actually</span> <span m="3602270">need</span> <span m="3602750">to</span>
  <span m="3602850">add</span> <span m="3603030">the node</span> <span m="3603340">back
  onto the</span> <span m="3603710">queue, because it's now</span> <span m="3603930">consistent.</span>
  <span m="3604884">It's</span> <span m="3605361">now</span> <span m="3605840">locally</span>
  <span m="3606321">consistent.</span> <span m="3608730">So</span> <span m="3609310">next,
  we'll</span> <span m="3609730">dequeue</span> <span m="3610180">the one with</span>
  <span m="3610550">the</span> <span m="3610640">smallest</span> <span m="3611120">key,</span>
  <span m="3611760">which is</span> <span m="3612130">B.</span> <span m="3612820">B</span>
  <span m="3613220">is</span> <span m="3613620">also</span> <span m="3614260">underconsistent,</span>
  <span m="3614640">so</span> <span m="3615070">we're</span> <span m="3615230">going</span>
  <span m="3615590">to</span> <span m="3615990">set</span> <span m="3616580">its</span>
  <span m="3616730">g</span> <span m="3617180">value back</span> <span m="3617460">to</span>
  <span m="3617640">infinity.</span> <span m="3618120">So</span> <span m="3618420">this
  is</span> <span m="3618735">sort of</span> <span m="3619050">resetting</span> <span
  m="3619550">the weird</span> <span m="3619810">thing</span> <span m="3620410">we</span>
  <span m="3620570">did</span> <span m="3620710">earlier</span> <span m="3620980">that
  didn't make any</span> <span m="3621420">sense.</span></p><p><span m="3623830">We're</span>
  <span m="3624200">going</span> <span m="3624320">to</span> <span m="3624380">update</span>
  <span m="3625330">its</span> <span m="3625670">neighbors'</span> <span m="3626100">rhs</span>
  <span m="3626400">values.</span> <span m="3627830">So</span> <span m="3628040">what
  would be</span> <span m="3628310">the new</span> <span m="3628490">rhs</span> <span
  m="3628770">value for</span> <span m="3628960">A,</span> <span m="3630420">now</span>
  <span m="3630630">that we</span> <span m="3630820">know</span> <span m="3631120">that</span>
  <span m="3632040">we</span> <span m="3633140">don't</span> <span m="3633320">actually</span>
  <span m="3633590">have</span> <span m="3634070">a</span> <span m="3634220">path
  B?</span></p><p><span m="3636745">AUDIENCE:</span> <span m="3636982">Infinity?</span></p><p><span
  m="3637695">JESS NOSS:</span> <span m="3637932">Infinity.</span> <span m="3638170">Yeah.</span>
  <span m="3640550">And</span> <span m="3640770">then,</span> <span m="3641465">how
  about rhs</span> <span m="3641810">value</span> <span m="3641990">to</span> <span
  m="3642380">D?</span> <span m="3642770">Because</span> <span m="3643160">currently,</span>
  <span m="3643830">D</span> <span m="3644070">got</span> <span m="3644210">its</span>
  <span m="3644540">rhs</span> <span m="3644770">value by</span> <span m="3645000">going</span>
  <span m="3645820">from</span> <span m="3645990">A to</span> <span m="3646210">B</span>
  <span m="3646360">to D.</span></p><p><span m="3653602">AUDIENCE:</span> <span m="3653851">10.</span></p><p><span
  m="3654600">JESS NOSS:</span> <span m="3654785">10.</span> <span m="3655260">'Cause</span>
  <span m="3655470">now</span> <span m="3655670">the</span> <span m="3655790">only</span>
  <span m="3656000">way--</span> <span m="3657950">rhs</span> <span m="3658250">is
  10.</span> <span m="3658710">The key</span> <span m="3659150">would</span> <span
  m="3659320">have</span> <span m="3660120">that</span> <span m="3660580">one</span>
  <span m="3660790">also.</span> <span m="3663580">Is that</span> <span m="3663750">right?</span>
  <span m="3665454">Yeah.</span> <span m="3666060">Because</span> <span m="3666370">currently,</span>
  <span m="3667320">the</span> <span m="3667630">best</span> <span m="3667860">path
  to</span> <span m="3668115">D,</span> <span m="3668370">and</span> <span m="3669280">actually,</span>
  <span m="3670200">the best path to D</span> <span m="3670600">you</span> <span m="3670840">can</span>
  <span m="3671020">see</span> <span m="3671860">is</span> <span m="3672400">from</span>
  <span m="3672670">G</span> <span m="3672955">to D,</span> <span m="3673240">because
  you can't</span> <span m="3673840">go</span> <span m="3674020">through</span> <span
  m="3674478">C</span> <span m="3674936">anymore.</span></p><p><span m="3677230">So
  now,</span> <span m="3677510">we'll</span> <span m="3677760">dequeue</span> <span
  m="3677980">node A,</span> <span m="3678405">because it has</span> <span m="3678830">the</span>
  <span m="3679070">smallest</span> <span m="3679310">key.</span> <span m="3681130">It</span>
  <span m="3681280">was</span> <span m="3681430">also</span> <span m="3681730">underconsistent,</span>
  <span m="3681940">so we would</span> <span m="3682265">set</span> <span m="3682590">G</span>
  <span m="3682800">to</span> <span m="3682900">infinity.</span> <span m="3686020">So
  we'll</span> <span m="3686420">propagate</span> <span m="3686860">that</span> <span
  m="3687040">to</span> <span m="3687150">its</span> <span m="3687310">neighbors.</span>
  <span m="3689410">And</span> <span m="3689750">if</span> <span m="3690090">we</span>
  <span m="3690190">continue</span> <span m="3690670">doing</span> <span m="3691000">this,</span>
  <span m="3692590">then we</span> <span m="3692770">find--</span> <span m="3695510">eventually,</span>
  <span m="3695805">we</span> <span m="3696100">dequeue</span> <span m="3696420">this
  node,</span> <span m="3696780">and</span> <span m="3697440">in</span> <span m="3697710">this
  case,</span> <span m="3697980">we</span> <span m="3698100">had</span> <span m="3698260">to</span>
  <span m="3698380">dequeue</span> <span m="3698740">everything,</span> <span m="3699190">so</span>
  <span m="3699460">now</span> <span m="3700145">the node's</span> <span m="3700470">are
  locally</span> <span m="3700810">consistent.</span> <span m="3702520">So</span>
  <span m="3702990">what's</span> <span m="3703470">the best path that</span> <span
  m="3703570">we've</span> <span m="3703720">found</span> <span m="3704280">from</span>
  <span m="3704530">B to the</span> <span m="3704740">goal?</span></p><p><span m="3710860">AUDIENCE:</span>
  <span m="3711110">B,</span> <span m="3711360">D,</span> <span m="3711600">G?</span></p><p><span
  m="3711990">JESS NOSS:</span> <span m="3712087">B,</span> <span m="3712184">D,</span>
  <span m="3712281">G.</span> <span m="3712380">And that's</span> <span m="3712770">also
  the only</span> <span m="3713140">path in this</span> <span m="3713595">case.</span>
  <span m="3715308">And</span> <span m="3715767">we</span> <span m="3716226">had</span>
  <span m="3716685">to update</span> <span m="3717144">these</span> <span m="3717603">neighbors.</span>
  <span m="3718521">OK.</span> <span m="3718980">So</span> <span m="3719220">here's</span>
  <span m="3719370">our new</span> <span m="3719700">shortest</span> <span m="3720120">path.</span>
  <span m="3720530">Now,</span> <span m="3720820">the robot</span> <span m="3720910">will</span>
  <span m="3721280">move</span> <span m="3721580">to node</span> <span m="3721650">D.</span>
  <span m="3723510">But</span> <span m="3723870">now,</span> <span m="3724340">what's</span>
  <span m="3724490">going to happen--</span> <span m="3724690">I think we</span> <span
  m="3725045">updated</span> <span m="3725400">our</span> <span m="3725640">heuristics.</span>
  <span m="3726370">But</span> <span m="3726470">now</span> <span m="3726630">what</span>
  <span m="3726690">happens</span> <span m="3727290">is it</span> <span m="3727710">turns</span>
  <span m="3728100">out it's</span> <span m="3728250">a</span> <span m="3728530">moving</span>
  <span m="3728760">obstacle,</span> <span m="3728880">and</span> <span m="3728940">it</span>
  <span m="3729270">starts</span> <span m="3729850">following</span> <span m="3730350">the
  robot.</span> <span m="3730880">So</span> <span m="3731110">now the</span> <span
  m="3731450">obstacle</span> <span m="3731790">has</span> <span m="3731980">moved
  to</span> <span m="3732350">there.</span> <span m="3733230">So</span> <span m="3733420">as
  humans,</span> <span m="3733920">we</span> <span m="3734010">can</span> <span m="3734190">see</span>
  <span m="3734470">that,</span> <span m="3734730">obviously,</span> <span m="3735270">the</span>
  <span m="3735360">shortest</span> <span m="3735750">path</span> <span m="3736150">is
  through</span> <span m="3736380">C,</span> <span m="3736890">but</span> <span m="3737010">the</span>
  <span m="3737130">algorithm</span> <span m="3737580">doesn't</span> <span m="3737820">know</span>
  <span m="3738030">this</span> <span m="3738240">yet.</span></p><p><span m="3740040">So</span>
  <span m="3740250">what</span> <span m="3740460">would</span> <span m="3740550">we</span>
  <span m="3740700">do</span> <span m="3740880">next?</span> <span m="3746990">So
  we</span> <span m="3747490">just</span> <span m="3747990">updated</span> <span m="3748650">our</span>
  <span m="3749030">edge</span> <span m="3749250">weights.</span> <span m="3749790">So</span>
  <span m="3749920">now</span> <span m="3750210">all</span> <span m="3750500">the</span>
  <span m="3750590">edges</span> <span m="3750920">to B</span> <span m="3751050">are</span>
  <span m="3751250">infinity.</span> <span m="3751890">But some</span> <span m="3752220">of</span>
  <span m="3752280">the</span> <span m="3752370">edges</span> <span m="3752660">to</span>
  <span m="3752780">C</span> <span m="3753070">are</span> <span m="3753482">no longer</span>
  <span m="3753894">infinity.</span> <span m="3754720">So we need</span> <span m="3755120">to</span>
  <span m="3755230">update</span> <span m="3755510">the</span> <span m="3755790">rhs</span>
  <span m="3756300">values</span> <span m="3757260">accordingly.</span> <span m="3759760">So
  we'll</span> <span m="3760235">update</span> <span m="3760710">all</span> <span
  m="3760980">of the</span> <span m="3761070">rhs</span> <span m="3761325">values</span>
  <span m="3761970">that</span> <span m="3762090">were</span> <span m="3762240">affected</span>
  <span m="3762720">by</span> <span m="3762940">this</span> <span m="3763110">change.</span>
  <span m="3764580">In</span> <span m="3764670">this</span> <span m="3764850">case,</span>
  <span m="3765570">G's</span> <span m="3765840">rhs</span> <span m="3766030">value</span>
  <span m="3766470">never</span> <span m="3766800">changes</span> <span m="3767055">because</span>
  <span m="3767310">the</span> <span m="3767450">distance</span> <span m="3767910">from
  G to</span> <span m="3768000">itself</span> <span m="3768570">is</span> <span m="3768690">always</span>
  <span m="3768900">0.</span> <span m="3770100">And</span> <span m="3770400">this
  one</span> <span m="3770690">doesn't</span> <span m="3770940">change</span> <span
  m="3771420">because</span> <span m="3773480">we</span> <span m="3773610">still</span>
  <span m="3773810">use</span> <span m="3774020">the</span> <span m="3774130">G value</span>
  <span m="3774600">here.</span></p><p><span m="3779310">OK. So now again,</span>
  <span m="3779710">we</span> <span m="3779880">can</span> <span m="3779990">start</span>
  <span m="3780270">dequeuing</span> <span m="3780550">and</span> <span m="3780830">planning</span>
  <span m="3781240">a</span> <span m="3781320">new</span> <span m="3781640">path,</span>
  <span m="3782000">so</span> <span m="3782360">we'll</span> <span m="3782788">dequeue</span>
  <span m="3783216">this node.</span> <span m="3783644">We'll</span> <span m="3784072">propagate</span>
  <span m="3784500">to its</span> <span m="3784875">neighbors.</span> <span m="3786760">Dequeue</span>
  <span m="3787040">that</span> <span m="3787620">one.</span> <span m="3788870">Update</span>
  <span m="3789180">the</span> <span m="3789390">rhs</span> <span m="3789480">values.</span>
  <span m="3790620">But</span> <span m="3790910">in</span> <span m="3791260">this</span>
  <span m="3791400">case,</span> <span m="3793150">we</span> <span m="3793170">don't--</span>
  <span m="3793908">let</span> <span m="3794406">me</span> <span m="3795402">go</span>
  <span m="3795900">back step.</span> <span m="3796900">So we</span> <span m="3797070">dequeue</span>
  <span m="3797570">this node,</span> <span m="3798070">and we update</span> <span
  m="3798290">its</span> <span m="3798620">G value,</span> <span m="3798810">but</span>
  <span m="3799245">we</span> <span m="3799680">don't</span> <span m="3799860">actually</span>
  <span m="3800160">need</span> <span m="3800430">to</span> <span m="3800730">continue</span>
  <span m="3800990">dequeuing</span> <span m="3801740">things.</span> <span m="3803910">We</span>
  <span m="3804060">should--</span> <span m="3805090">oh,</span> <span m="3805460">this</span>
  <span m="3805680">rhs</span> <span m="3805860">value should be</span> <span m="3805980">updated.</span>
  <span m="3806960">Oh,</span> <span m="3807450">it</span> <span m="3807890">is</span>
  <span m="3808160">updated.</span> <span m="3808730">Why is this</span> <span m="3809110">rhs</span>
  <span m="3809400">infinity?</span></p><p><span m="3812680">AUDIENCE:</span> <span
  m="3812833">All</span> <span m="3812986">edges</span> <span m="3813140">to it</span>
  <span m="3813390">are</span> <span m="3813610">infinity.</span></p><p><span m="3814570">JESS
  NOSS:</span> <span m="3814755">Yeah.</span> <span m="3814940">All</span> <span m="3815190">edges</span>
  <span m="3815340">to it</span> <span m="3815690">are</span> <span m="3815870">infinity.</span>
  <span m="3816070">You can't</span> <span m="3816515">get</span> <span m="3816960">there.</span>
  <span m="3817405">But we don't</span> <span m="3817850">actually</span> <span m="3818300">have</span>
  <span m="3818520">to</span> <span m="3818640">bother</span> <span m="3819740">expanding</span>
  <span m="3820210">B,</span> <span m="3821550">because we've</span> <span m="3821830">already
  found the</span> <span m="3822130">shortest</span> <span m="3822550">path.</span>
  <span m="3823340">So this</span> <span m="3823830">gives</span> <span m="3824320">you
  sort of</span> <span m="3824820">a hint</span> <span m="3825030">at</span> <span
  m="3825450">when</span> <span m="3825690">D*</span> <span m="3825990">might</span>
  <span m="3826110">be</span> <span m="3826320">efficient.</span> <span m="3827010">Because
  even</span> <span m="3827250">if</span> <span m="3827310">there</span> <span m="3827430">were</span>
  <span m="3827520">a</span> <span m="3827550">whole</span> <span m="3827770">bunch</span>
  <span m="3828000">of</span> <span m="3828090">nodes</span> <span m="3828360">over
  there,</span> <span m="3828470">I wouldn't</span> <span m="3828700">need</span>
  <span m="3828850">to</span> <span m="3829290">consider</span> <span m="3829650">them,</span>
  <span m="3830025">because</span> <span m="3830400">we</span> <span m="3830700">found
  the</span> <span m="3831115">shortest</span> <span m="3831530">path.</span></p><p><span
  m="3832360">So now, the</span> <span m="3832530">robot</span> <span m="3833370">can</span>
  <span m="3834000">move</span> <span m="3834240">up</span> <span m="3834360">to</span>
  <span m="3834510">C.</span> <span m="3837040">And let's say the</span> <span m="3837160">obstacle
  chases</span> <span m="3837390">the</span> <span m="3837775">robot</span> <span
  m="3838160">again.</span> <span m="3839500">Do</span> <span m="3839680">we</span>
  <span m="3840270">need</span> <span m="3840550">to find a new path?</span> <span
  m="3844254">No.</span> <span m="3844720">So intuitively,</span> <span m="3845140">we
  don't,</span> <span m="3845590">because the</span> <span m="3845890">obstacle's</span>
  <span m="3846620">not</span> <span m="3846730">in</span> <span m="3846820">the</span>
  <span m="3846910">way</span> <span m="3847120">of</span> <span m="3847270">our</span>
  <span m="3847450">current</span> <span m="3847790">best path.</span> <span m="3849330">But</span>
  <span m="3849550">we</span> <span m="3849760">can also</span> <span m="3850030">see</span>
  <span m="3850570">algorithmically</span> <span m="3851140">why</span> <span m="3851320">that's</span>
  <span m="3851590">the</span> <span m="3851680">case.</span></p><p><span m="3853500">So</span>
  <span m="3853870">first of all,</span> <span m="3854050">we'll</span> <span m="3854150">update
  all of our</span> <span m="3854410">rhs</span> <span m="3854710">values</span> <span
  m="3855020">accordingly,</span> <span m="3855820">because</span> <span m="3856090">we've</span>
  <span m="3856210">changed</span> <span m="3856810">all</span> <span m="3857130">of</span>
  <span m="3857450">the</span> <span m="3857610">edge</span> <span m="3857865">weights.</span>
  <span m="3860788">But</span> <span m="3861250">the</span> <span m="3861370">reason</span>
  <span m="3863160">algorithmically</span> <span m="3863920">why</span> <span m="3864130">we</span>
  <span m="3864220">don't</span> <span m="3864460">actually</span> <span m="3864790">need</span>
  <span m="3864970">to</span> <span m="3865090">consider</span> <span m="3865570">any</span>
  <span m="3865720">of</span> <span m="3865800">these</span> <span m="3866040">change</span>
  <span m="3866300">values</span> <span m="3867190">is</span> <span m="3867420">because</span>
  <span m="3868260">this</span> <span m="3868675">node</span> <span m="3868940">has</span>
  <span m="3869380">the</span> <span m="3869470">smallest</span> <span m="3869950">key,</span>
  <span m="3871000">which</span> <span m="3871180">means</span> <span m="3871540">that</span>
  <span m="3872110">this</span> <span m="3872290">is the node</span> <span m="3872730">that</span>
  <span m="3872890">has</span> <span m="3873160">the</span> <span m="3873400">shortest</span>
  <span m="3873810">path</span> <span m="3874240">to</span> <span m="3874440">G</span>
  <span m="3874840">anyway.</span> <span m="3876420">It</span> <span m="3876730">is</span>
  <span m="3876970">smaller</span> <span m="3877360">key</span> <span m="3877600">than</span>
  <span m="3877720">all</span> <span m="3877970">the</span> <span m="3878080">other</span>
  <span m="3878290">nodes</span> <span m="3878590">that are on the</span> <span m="3878960">queue.</span>
  <span m="3879810">So</span> <span m="3880060">dequeuing</span> <span m="3880570">things</span>
  <span m="3880900">wouldn't</span> <span m="3881110">actually</span> <span m="3881470">help</span>
  <span m="3881680">us find the</span> <span m="3881780">shorter path.</span> <span
  m="3884796">So</span> <span m="3885240">the</span> <span m="3885330">robot</span>
  <span m="3885690">can</span> <span m="3885770">move</span> <span m="3885980">to</span>
  <span m="3886060">the</span> <span m="3886180">goal,</span> <span m="3886530">and</span>
  <span m="3886880">we've</span> <span m="3887080">succeeded.</span></p><p><span m="3890008">Any</span>
  <span m="3890496">questions on that?</span> <span m="3896840">OK.</span> <span m="3897195">So</span>
  <span m="3897460">now</span> <span m="3897720">then</span> <span m="3898030">we'll</span>
  <span m="3898310">talk</span> <span m="3898550">about</span> <span m="3899270">sometimes</span>
  <span m="3899840">when</span> <span m="3899960">you</span> <span m="3900150">would
  want</span> <span m="3900380">to use</span> <span m="3900730">incremental</span>
  <span m="3900890">path planning,</span> <span m="3902500">other</span> <span m="3902830">than</span>
  <span m="3903050">this</span> <span m="3903250">five</span> <span m="3903490">node</span>
  <span m="3903936">graph.</span></p><p><span m="3906912">ERLEND HARBITZ:</span> <span
  m="3907131">Thanks.</span> <span m="3907350">So</span> <span m="3907720">as</span>
  <span m="3907840">Jess</span> <span m="3908090">said,</span> <span m="3909470">there</span>
  <span m="3909860">are</span> <span m="3910250">sometimes</span> <span m="3910690">good</span>
  <span m="3910880">reasons</span> <span m="3911830">to</span> <span m="3911980">use</span>
  <span m="3912170">incremental</span> <span m="3912270">path planning, but</span>
  <span m="3913020">there</span> <span m="3913120">are</span> <span m="3913220">also</span>
  <span m="3913320">good</span> <span m="3913340">reasons</span> <span m="3913670">not</span>
  <span m="3914030">to</span> <span m="3914330">in</span> <span m="3914420">certain</span>
  <span m="3914720">circumstances.</span> <span m="3916080">In</span> <span m="3916160">certain</span>
  <span m="3916370">circumstances,</span> <span m="3916730">we</span> <span m="3917090">can</span>
  <span m="3917130">actually</span> <span m="3917470">formulate</span> <span m="3917880">graph</span>
  <span m="3918190">problems,</span> <span m="3918740">where a</span> <span m="3919120">problem</span>
  <span m="3919370">is</span> <span m="3919720">worse</span> <span m="3920180">by
  using</span> <span m="3920500">incremental</span> <span m="3920670">planning.</span></p><p><span
  m="3922640">Remember</span> <span m="3923420">that</span> <span m="3923600">I</span>
  <span m="3923690">said</span> <span m="3924080">that</span> <span m="3924360">D*</span>
  <span m="3924680">Lite</span> <span m="3925200">puts</span> <span m="3925620">any
  node</span> <span m="3925950">on the</span> <span m="3926380">queue</span> <span
  m="3927050">at</span> <span m="3927290">most</span> <span m="3927590">twice.</span>
  <span m="3928540">And</span> <span m="3928690">so we</span> <span m="3928790">can</span>
  <span m="3928930">compare</span> <span m="3929320">that</span> <span m="3929750">to</span>
  <span m="3930320">A*,</span> <span m="3930860">or</span> <span m="3930980">something</span>
  <span m="3931280">like</span> <span m="3931460">that,</span> <span m="3932140">that</span>
  <span m="3932240">does</span> <span m="3932270">full</span> <span m="3932660">replanning</span>
  <span m="3933740">whenever</span> <span m="3933890">a</span> <span m="3934000">search</span>
  <span m="3934680">occurs.</span> <span m="3935660">That pus</span> <span m="3935900">every</span>
  <span m="3936140">node</span> <span m="3936650">on</span> <span m="3936770">the</span>
  <span m="3936830">search</span> <span m="3937250">queue</span> <span m="3937460">at</span>
  <span m="3937785">most</span> <span m="3938110">once.</span> <span m="3939110">So</span>
  <span m="3939290">D*</span> <span m="3939440">Lite</span> <span m="3940100">is</span>
  <span m="3940310">most</span> <span m="3940670">beneficial</span> <span m="3942170">when</span>
  <span m="3942710">putting</span> <span m="3943220">the</span> <span m="3943280">nodes</span>
  <span m="3943730">on</span> <span m="3943970">the</span> <span m="3944060">queue,</span>
  <span m="3944870">potentially</span> <span m="3945380">more</span> <span m="3945620">than</span>
  <span m="3945830">once,</span> <span m="3947116">leads</span> <span m="3947520">to</span>
  <span m="3948510">less</span> <span m="3948950">nodes</span> <span m="3949170">being</span>
  <span m="3949640">examined</span> <span m="3949930">overall.</span></p><p><span
  m="3953300">So</span> <span m="3953990">here is</span> <span m="3954440">essentially</span>
  <span m="3954860">what</span> <span m="3954980">I</span> <span m="3955080">just</span>
  <span m="3955280">said.</span> <span m="3957710">So</span> <span m="3958310">A*</span>
  <span m="3958880">might</span> <span m="3959180">perform</span> <span m="3959630">better</span>
  <span m="3960350">for</span> <span m="3960470">certain</span> <span m="3960950">problems</span>
  <span m="3961860">if</span> <span m="3962810">we</span> <span m="3963020">only</span>
  <span m="3963440">have</span> <span m="3963710">to</span> <span m="3964260">consider</span>
  <span m="3965890">a</span> <span m="3965930">small</span> <span m="3966230">amount</span>
  <span m="3966440">of</span> <span m="3966560">nodes</span> <span m="3967240">anyway.</span>
  <span m="3968060">So</span> <span m="3968270">putting</span> <span m="3968575">nodes</span>
  <span m="3969650">on</span> <span m="3969860">the</span> <span m="3970100">graph</span>
  <span m="3970400">twice</span> <span m="3971030">would</span> <span m="3971150">actually</span>
  <span m="3971510">lead</span> <span m="3971710">to</span> <span m="3971990">more</span>
  <span m="3972270">expansions.</span> <span m="3973970">And so,</span> <span m="3974420">to</span>
  <span m="3974510">get</span> <span m="3974990">at</span> <span m="3975100">an</span>
  <span m="3976140">intuition</span> <span m="3976880">of</span> <span m="3977950">why</span>
  <span m="3978210">that</span> <span m="3978400">might</span> <span m="3978590">occur</span>
  <span m="3979040">if</span> <span m="3979460">changes</span> <span m="3980030">are</span>
  <span m="3980270">close</span> <span m="3980690">to</span> <span m="3980780">the</span>
  <span m="3980900">start</span> <span m="3981140">node,</span> <span m="3982710">I</span>
  <span m="3982820">want</span> <span m="3983130">to</span> <span m="3983330">show</span>
  <span m="3983590">you an</span> <span m="3984020">example here.</span></p><p><span
  m="3985130">So</span> <span m="3985400">here, we're</span> <span m="3985510">actually</span>
  <span m="3985820">showing</span> <span m="3986140">an</span> <span m="3986280">example</span>
  <span m="3987050">that's</span> <span m="3987410">derived</span> <span m="3987860">from</span>
  <span m="3988390">[INAUDIBLE].</span> <span m="3989340">So</span> <span m="3989660">we're</span>
  <span m="3989870">searching</span> <span m="3990380">forwards</span> <span m="3990920">here</span>
  <span m="3991520">from</span> <span m="3991760">the start</span> <span m="3992060">node</span>
  <span m="3992360">to the goal node.</span> <span m="3992540">And that's</span> <span
  m="3993140">just</span> <span m="3993390">a</span> <span m="3993500">different</span>
  <span m="3993770">reformulation,</span> <span m="3994560">so</span> <span m="3994700">don't</span>
  <span m="3994880">let that</span> <span m="3995120">confuse</span> <span m="3995410">you
  too much.</span> <span m="3997730">When</span> <span m="3997850">we</span> <span
  m="3997970">walk</span> <span m="3998300">forward</span> <span m="3999150">through
  A*</span> <span m="3999960">with</span> <span m="4000170">a</span> <span m="4000250">good</span>
  <span m="4000550">heuristic,</span> <span m="4001330">we</span> <span m="4001450">might</span>
  <span m="4001660">move</span> <span m="4001990">directly</span> <span m="4002470">from</span>
  <span m="4002630">the</span> <span m="4002670">start</span> <span m="4002950">node</span>
  <span m="4003280">to</span> <span m="4003550">goal</span> <span m="4003730">node,</span>
  <span m="4004168">and find that path.</span></p><p><span m="4005920">Now,</span>
  <span m="4006140">if a</span> <span m="4006270">change</span> <span m="4006710">occurs</span>
  <span m="4007300">somewhere</span> <span m="4008500">upstream</span> <span m="4009600">of
  the</span> <span m="4009900">start</span> <span m="4010210">node,</span> <span m="4010760">when</span>
  <span m="4011100">we</span> <span m="4011330">replanning,</span> <span m="4012520">we</span>
  <span m="4012640">essentially</span> <span m="4013150">have</span> <span m="4013300">to</span>
  <span m="4013520">replan</span> <span m="4016260">the</span> <span m="4016390">sections</span>
  <span m="4017170">that</span> <span m="4017320">are</span> <span m="4017470">beyond</span>
  <span m="4018790">the</span> <span m="4019330">change</span> <span m="4019700">that's
  occurred.</span> <span m="4020890">So</span> <span m="4021430">everything</span>
  <span m="4021820">that's</span> <span m="4022030">here,</span> <span m="4023830">to</span>
  <span m="4024100">an</span> <span m="4024420">extent,</span> <span m="4025150">it's</span>
  <span m="4025570">relatively</span> <span m="4025985">insensitive</span> <span m="4027340">to</span>
  <span m="4027430">this</span> <span m="4027610">change.</span> <span m="4028540">It</span>
  <span m="4028650">could</span> <span m="4028910">occur</span> <span m="4029320">that</span>
  <span m="4029960">we</span> <span m="4030220">would</span> <span m="4030460">have</span>
  <span m="4030700">to take</span> <span m="4031380">an</span> <span m="4031430">entirely</span>
  <span m="4031760">different</span> <span m="4032140">route.</span> <span m="4032410">But</span>
  <span m="4032510">for</span> <span m="4032680">the</span> <span m="4032770">most</span>
  <span m="4033250">part,</span> <span m="4034090">it's</span> <span m="4034520">likely</span>
  <span m="4035110">that</span> <span m="4035320">changes</span> <span m="4035740">are</span>
  <span m="4035800">going</span> <span m="4036040">to</span> <span m="4036580">couple</span>
  <span m="4037000">to our</span> <span m="4037300">existing</span> <span m="4037620">path</span>
  <span m="4038570">and</span> <span m="4038690">so</span> <span m="4038810">forth.</span>
  <span m="4039836">And</span> <span m="4040310">so</span> <span m="4040450">we</span>
  <span m="4040570">have</span> <span m="4040750">an</span> <span m="4040810">efficient</span>
  <span m="4041260">search</span> <span m="4042700">that</span> <span m="4042940">will</span>
  <span m="4043180">just</span> <span m="4043930">go</span> <span m="4044170">around</span>
  <span m="4045250">from</span> <span m="4047020">the</span> <span m="4047170">path</span>
  <span m="4047500">that we've</span> <span m="4047740">already</span> <span m="4047990">planned</span>
  <span m="4049210">to</span> <span m="4049410">our</span> <span m="4049640">goal
  node.</span></p><p><span m="4051140">So</span> <span m="4051250">in</span> <span
  m="4051370">this</span> <span m="4051560">sense,</span> <span m="4052060">we</span>
  <span m="4052210">have</span> <span m="4052360">an</span> <span m="4052450">example</span>
  <span m="4053200">where</span> <span m="4053380">incremental</span> <span m="4053950">path
  planning</span> <span m="4055210">would</span> <span m="4055360">be</span> <span
  m="4056200">very</span> <span m="4056500">efficient.</span> <span m="4058960">In</span>
  <span m="4059080">this</span> <span m="4059260">case,</span> <span m="4059900">which</span>
  <span m="4060070">is</span> <span m="4060160">a</span> <span m="4060220">different</span>
  <span m="4060580">one,</span> <span m="4061180">we</span> <span m="4061330">introduce</span>
  <span m="4061780">an</span> <span m="4061910">obstacle</span> <span m="4062770">very</span>
  <span m="4063130">near</span> <span m="4063490">our</span> <span m="4063610">start</span>
  <span m="4063900">node.</span> <span m="4064660">This</span> <span m="4064870">means</span>
  <span m="4065530">that</span> <span m="4065740">most</span> <span m="4066250">of</span>
  <span m="4066370">our</span> <span m="4066550">existing</span> <span m="4067060">path</span>
  <span m="4067790">is</span> <span m="4068000">to charge.</span> <span m="4069320">So</span>
  <span m="4069370">where</span> <span m="4069520">we</span> <span m="4069640">start</span>
  <span m="4070480">out</span> <span m="4071040">from</span> <span m="4072950">our</span>
  <span m="4073540">start</span> <span m="4073930">node</span> <span m="4074260">to</span>
  <span m="4074500">our</span> <span m="4074820">goal</span> <span m="4075190">node,</span>
  <span m="4075880">we</span> <span m="4076000">have</span> <span m="4076120">to</span>
  <span m="4076180">do</span> <span m="4076510">a</span> <span m="4076600">lot</span>
  <span m="4076780">of</span> <span m="4076890">recomputation</span> <span m="4077620">from</span>
  <span m="4077800">scratch.</span></p><p><span m="4079160">And so</span> <span m="4079470">an</span>
  <span m="4079780">incremental</span> <span m="4080590">searching</span> <span m="4081040">algorithm</span>
  <span m="4082150">is</span> <span m="4082240">going</span> <span m="4082390">to</span>
  <span m="4082450">have to</span> <span m="4082750">undo</span> <span m="4083260">all</span>
  <span m="4083470">searches</span> <span m="4083800">that</span> <span m="4083890">we've</span>
  <span m="4084040">already</span> <span m="4084340">done,</span> <span m="4085200">and</span>
  <span m="4085330">then</span> <span m="4085840">search</span> <span m="4086430">through</span>
  <span m="4086920">almost</span> <span m="4087310">the</span> <span m="4087430">entirety</span>
  <span m="4087940">of</span> <span m="4088030">the</span> <span m="4088120">graph</span>
  <span m="4088580">again.</span> <span m="4089890">So intuitively,</span> <span m="4090930">in</span>
  <span m="4091030">this</span> <span m="4091240">case,</span> <span m="4092500">just</span>
  <span m="4092690">restarting</span> <span m="4093280">with</span> <span m="4093490">A*</span>
  <span m="4093710">from a</span> <span m="4094210">blank</span> <span m="4094600">slate,</span>
  <span m="4095180">which</span> <span m="4095340">we would</span> <span m="4095500">search</span>
  <span m="4095890">directly</span> <span m="4097090">down</span> <span m="4097420">to</span>
  <span m="4097540">the</span> <span m="4097680">goal,</span> <span m="4098300">instead
  of</span> <span m="4098560">doing</span> <span m="4099200">reparations</span> <span
  m="4099970">that</span> <span m="4100200">would</span> <span m="4100450">send</span>
  <span m="4100620">us in</span> <span m="4100920">one</span> <span m="4101210">path,</span>
  <span m="4102160">would</span> <span m="4102340">be</span> <span m="4103120">a</span>
  <span m="4103210">better</span> <span m="4103510">idea</span> <span m="4104170">in</span>
  <span m="4104260">this</span> <span m="4104410">case.</span></p><p><span m="4105660">So
  since we're</span> <span m="4105950">powering</span> <span m="4106600">from</span>
  <span m="4107050">the</span> <span m="4107140">start</span> <span m="4108100">to</span>
  <span m="4108399">the</span> <span m="4108550">goal,</span> <span m="4109250">in</span>
  <span m="4109430">this</span> <span m="4109590">example</span> <span m="4109790">that</span>
  <span m="4110200">we're</span> <span m="4110430">showing,</span> <span m="4111490">it's</span>
  <span m="4111880">worse</span> <span m="4112600">to</span> <span m="4112720">use</span>
  <span m="4113050">incremental</span> <span m="4113149">path</span> <span m="4113540">planning</span>
  <span m="4113800">algorithms</span> <span m="4114910">when</span> <span m="4115569">your</span>
  <span m="4116080">changes</span> <span m="4116640">happen</span> <span m="4117040">near</span>
  <span m="4117370">your</span> <span m="4117490">start</span> <span m="4117819">node.</span>
  <span m="4118720">For</span> <span m="4118870">something</span> <span m="4119560">like</span>
  <span m="4120270">D*</span> <span m="4120660">Lite,</span> <span m="4121060">we</span>
  <span m="4121260">search</span> <span m="4121899">back</span> <span m="4122200">from</span>
  <span m="4122439">the</span> <span m="4122540">goal</span> <span m="4122850">node</span>
  <span m="4123399">to</span> <span m="4123640">the</span> <span m="4123760">start</span>
  <span m="4124100">node,</span> <span m="4124760">it's</span> <span m="4125220">better</span>
  <span m="4125770">if</span> <span m="4126000">changes</span> <span m="4126410">occur</span>
  <span m="4126819">nearer</span> <span m="4127130">to</span> <span m="4127270">the</span>
  <span m="4127359">start</span> <span m="4127750">node,</span> <span m="4128410">which
  for</span> <span m="4128710">our</span> <span m="4129100">vehicles</span> <span
  m="4129279">that we</span> <span m="4129700">normally</span> <span m="4130180">see</span>
  <span m="4130720">that</span> <span m="4131420">have</span> <span m="4131859">limited</span>
  <span m="4132340">sensor</span> <span m="4132819">horizons,</span> <span m="4133160">is</span>
  <span m="4133399">what's</span> <span m="4133590">going to</span> <span m="4134050">occur</span>
  <span m="4134529">in</span> <span m="4134609">the most</span> <span m="4134830">case.</span>
  <span m="4135740">So</span> <span m="4135819">in those</span> <span m="4136029">type
  of</span> <span m="4136149">situations,</span> <span m="4137760">incremental</span>
  <span m="4137930">path</span> <span m="4138280">planning is</span> <span m="4138630">going
  to be</span> <span m="4138930">very efficient.</span></p><p><span m="4141450">AUDIENCE:</span>
  <span m="4141589">So</span> <span m="4141729">I understand how this</span> <span
  m="4142390">could</span> <span m="4142540">be</span> <span m="4142630">a</span>
  <span m="4142720">problem</span> <span m="4143050">for</span> <span m="4143529">LPA*</span>
  <span m="4144149">and</span> <span m="4144620">D*</span> <span m="4144910">Lite</span>
  <span m="4145620">over</span> <span m="4145779">finding</span> <span m="4146319">a</span>
  <span m="4146380">single</span> <span m="4146740">path,</span> <span m="4147122">where</span>
  <span m="4147504">you have like a</span> <span m="4147886">single</span> <span m="4148270">source</span>
  <span m="4148930">or</span> <span m="4149840">destination</span> <span m="4150670">or</span>
  <span m="4150729">something</span> <span m="4151000">like</span> <span m="4151210">that.</span>
  <span m="4151740">But</span> <span m="4152040">what</span> <span m="4152340">if
  it's</span> <span m="4153100">incremental,</span> <span m="4153790">all-pairs</span>
  <span m="4154130">shortest-paths,</span> <span m="4154300">where</span> <span m="4154689">you've</span>
  <span m="4155080">computed--</span> <span m="4157479">I'd assume</span> <span m="4158140">you
  wouldn't</span> <span m="4158470">experience</span> <span m="4158800">the same</span>
  <span m="4159130">problems</span> <span m="4159750">if</span> <span m="4160010">your</span>
  <span m="4160210">algorithm was</span> <span m="4160680">computing</span> <span
  m="4160979">choice paths</span> <span m="4161460">between</span> <span m="4162029">all</span>
  <span m="4162189">pairs</span> <span m="4162490">of</span> <span m="4162600">nodes</span>
  <span m="4162880">indirect.</span></p><p><span m="4164040">ERLEND HARBITZ:</span>
  <span m="4164179">Yeah.</span> <span m="4164634">It</span> <span m="4164950">already</span>
  <span m="4165410">exists.</span> <span m="4169189">Well,</span> <span m="4169529">that</span>
  <span m="4169810">depends.</span> <span m="4173720">When</span> <span m="4173990">you're</span>
  <span m="4174510">redoing</span> <span m="4174850">recomputation,</span> <span m="4179470">between</span>
  <span m="4180120">all</span> <span m="4180430">the</span> <span m="4180550">nodes</span>
  <span m="4181309">in the path,</span> <span m="4181760">it</span> <span m="4182229">depends</span>
  <span m="4182970">if</span> <span m="4183170">our</span> <span m="4183380">obstacle</span>
  <span m="4184840">has</span> <span m="4185050">changed</span> <span m="4185830">[INAUDIBLE]</span>
  <span m="4186200">of something</span> <span m="4186490">there</span> <span m="4186750">that</span>
  <span m="4186870">we</span> <span m="4186990">to</span> <span m="4187140">conceive.</span>
  <span m="4187850">And</span> <span m="4187939">by</span> <span m="4188060">that</span>
  <span m="4188290">I</span> <span m="4188380">mean</span> <span m="4188710">imagining</span>
  <span m="4189250">this</span> <span m="4189430">graph</span> <span m="4189790">we've</span>
  <span m="4189910">computed,</span> <span m="4190540">D,</span> <span m="4191752">the</span>
  <span m="4192210">paths</span> <span m="4192645">and path</span> <span m="4193080">costs,</span>
  <span m="4193540">to get</span> <span m="4193750">from</span> <span m="4193990">every</span>
  <span m="4194260">single</span> <span m="4194680">node</span> <span m="4195140">to
  every</span> <span m="4195370">single</span> <span m="4195792">other node.</span></p><p><span
  m="4197060">Now, if</span> <span m="4197480">introducing</span> <span m="4198270">an</span>
  <span m="4198300">obstacle</span> <span m="4198770">here</span> <span m="4199520">only</span>
  <span m="4200120">changed</span> <span m="4201350">the</span> <span m="4201690">path</span>
  <span m="4201960">cost</span> <span m="4202230">to get</span> <span m="4202460">from</span>
  <span m="4202700">our stock node</span> <span m="4202940">to our</span> <span m="4203310">goal</span>
  <span m="4203590">node</span> <span m="4203950">from</span> <span m="4204140">example,</span>
  <span m="4205280">then</span> <span m="4206580">replanning</span> <span m="4207690">that</span>
  <span m="4208110">specific</span> <span m="4208910">pair</span> <span m="4209300">of
  paths</span> <span m="4209920">from</span> <span m="4210080">start</span> <span
  m="4210460">node</span> <span m="4210680">to the goal node</span> <span m="4211620">would</span>
  <span m="4211940">use</span> <span m="4212240">data</span> <span m="4212570">that</span>
  <span m="4212720">already</span> <span m="4213110">exists</span> <span m="4213530">from</span>
  <span m="4213710">the</span> <span m="4213860">other</span> <span m="4214070">nodes</span>
  <span m="4214320">to</span> <span m="4214480">the</span> <span m="4214720">goal
  node.</span> <span m="4215000">We</span> <span m="4215120">already</span> <span
  m="4215350">have</span> <span m="4215690">that.</span></p><p><span m="4216155">But
  if</span> <span m="4216430">introducing</span> <span m="4216980">an</span> <span
  m="4217070">obstacle</span> <span m="4217490">would</span> <span m="4217640">cause</span>
  <span m="4217940">changes</span> <span m="4218450">throughout</span> <span m="4218900">the</span>
  <span m="4219050">entire</span> <span m="4219345">graph,</span> <span m="4220250">then</span>
  <span m="4220340">we</span> <span m="4220460">can</span> <span m="4221270">potentially</span>
  <span m="4221720">create</span> <span m="4222340">what</span> <span m="4222510">would</span>
  <span m="4223090">have</span> <span m="4223240">to</span> <span m="4223340">be a</span>
  <span m="4223660">very</span> <span m="4224090">well-connected</span> <span m="4224930">graph,</span>
  <span m="4225890">where</span> <span m="4226430">again,</span> <span m="4226740">incremental</span>
  <span m="4227400">path</span> <span m="4227740">planning would probably perform</span>
  <span m="4228080">worse</span> <span m="4228420">in that</span> <span m="4228880">case.</span></p><p><span
  m="4229230">AUDIENCE:</span> <span m="4229405">Yeah.</span> <span m="4229580">So
  you could</span> <span m="4229930">still</span> <span m="4230280">end</span> <span
  m="4230430">up in</span> <span m="4230540">the</span> <span m="4230610">same</span>
  <span m="4230900">situation</span> <span m="4231040">[INAUDIBLE].</span></p><p><span
  m="4235580">ERLEND HARBITZ:</span> <span m="4235707">Now</span> <span m="4236420">these</span>
  <span m="4236720">algorithms</span> <span m="4237080">are</span> <span m="4237350">interesting,</span>
  <span m="4237950">because</span> <span m="4238190">they</span> <span m="4238480">allow
  for some</span> <span m="4238940">extensions</span> <span m="4239920">that</span>
  <span m="4240050">allow us</span> <span m="4240140">to do</span> <span m="4240370">some</span>
  <span m="4242210">some</span> <span m="4242360">very</span> <span m="4243350">different</span>
  <span m="4243770">things</span> <span m="4244040">quite</span> <span m="4244310">easily.</span>
  <span m="4245850">One</span> <span m="4245870">example</span> <span m="4246530">is</span>
  <span m="4246980">greedy</span> <span m="4247380">mapping,</span> <span m="4248600">in</span>
  <span m="4248690">terms</span> <span m="4249080">of</span> <span m="4249200">how</span>
  <span m="4249410">can</span> <span m="4249620">we</span> <span m="4249980">design</span>
  <span m="4250490">algorithm</span> <span m="4251660">using</span> <span m="4251960">what</span>
  <span m="4252080">we</span> <span m="4252200">know</span> <span m="4252390">about</span>
  <span m="4252910">incremental</span> <span m="4252990">path</span> <span m="4253330">planning,</span>
  <span m="4254100">to</span> <span m="4254310">hit</span> <span m="4254660">every</span>
  <span m="4254960">single</span> <span m="4255320">node</span> <span m="4255590">on</span>
  <span m="4255905">our</span> <span m="4256220">graph.</span> <span m="4257810">And</span>
  <span m="4258260">what</span> <span m="4258500">we</span> <span m="4258650">do</span>
  <span m="4258950">is</span> <span m="4259130">then</span> <span m="4259290">we</span>
  <span m="4259520">introduce</span> <span m="4260030">a</span> <span m="4260550">faux</span>
  <span m="4260865">goal</span> <span m="4261180">node,</span> <span m="4262080">essentially</span>
  <span m="4262435">a node</span> <span m="4263020">that</span> <span m="4263120">doesn't</span>
  <span m="4263420">exist</span> <span m="4264860">that</span> <span m="4265010">we</span>
  <span m="4265130">can</span> <span m="4265250">never</span> <span m="4265550">reach.</span></p><p><span
  m="4266610">And</span> <span m="4266720">we</span> <span m="4270410">add</span>
  <span m="4271020">to</span> <span m="4271250">our</span> <span m="4271460">initial</span>
  <span m="4272000">beliefs,</span> <span m="4272570">our</span> <span m="4272790">initial</span>
  <span m="4273170">understanding</span> <span m="4274040">of</span> <span m="4274330">the</span>
  <span m="4274480">graph</span> <span m="4275510">connections</span> <span m="4276040">between</span>
  <span m="4276530">all</span> <span m="4276800">nodes</span> <span m="4277085">to</span>
  <span m="4277370">this</span> <span m="4277760">faux</span> <span m="4278030">goal</span>
  <span m="4278300">node.</span> <span m="4278670">Now,</span> <span m="4278910">it's</span>
  <span m="4279110">false</span> <span m="4279710">in</span> <span m="4279860">the</span>
  <span m="4279950">sense</span> <span m="4280460">that</span> <span m="4280760">whenever</span>
  <span m="4281100">we</span> <span m="4281250">move</span> <span m="4281590">our</span>
  <span m="4281870">start</span> <span m="4282230">node</span> <span m="4283010">to</span>
  <span m="4283460">one</span> <span m="4283670">of</span> <span m="4283810">the nodes
  that</span> <span m="4284080">we've</span> <span m="4284240">examined</span> <span
  m="4284630">before,</span> <span m="4285530">what</span> <span m="4285680">happens</span>
  <span m="4286040">in</span> <span m="4286100">terms</span> <span m="4286370">of</span>
  <span m="4286490">the</span> <span m="4286580">changes</span> <span m="4287180">of</span>
  <span m="4287260">the</span> <span m="4287570">edge</span> <span m="4287930">costs</span>
  <span m="4288340">is</span> <span m="4289220">removing</span> <span m="4290510">that</span>
  <span m="4291370">edge</span> <span m="4291660">that</span> <span m="4291800">connected</span>
  <span m="4292280">that</span> <span m="4292480">node</span> <span m="4292750">to</span>
  <span m="4292990">the</span> <span m="4293100">goal node.</span></p><p><span m="4294200">So</span>
  <span m="4294410">what this</span> <span m="4294560">means</span> <span m="4295070">in</span>
  <span m="4295220">principle</span> <span m="4295940">is</span> <span m="4296090">that</span>
  <span m="4296240">our</span> <span m="4296390">vehicle,</span> <span m="4297020">our</span>
  <span m="4297320">poor</span> <span m="4297620">vehicle,</span> <span m="4298470">can</span>
  <span m="4298780">never</span> <span m="4298970">reach the goal</span> <span m="4299410">node.</span>
  <span m="4300820">Whenever</span> <span m="4301250">it</span> <span m="4301310">reaches</span>
  <span m="4301630">a</span> <span m="4301700">node</span> <span m="4302060">that</span>
  <span m="4302220">it</span> <span m="4302330">thinks</span> <span m="4302660">it</span>
  <span m="4302710">can</span> <span m="4302840">get</span> <span m="4303050">to</span>
  <span m="4303150">the goal node</span> <span m="4303590">from,</span> <span m="4304700">that</span>
  <span m="4304940">path</span> <span m="4305295">disappears.</span> <span m="4305960">But</span>
  <span m="4306280">what</span> <span m="4306500">that</span> <span m="4306620">causes</span>
  <span m="4306910">it</span> <span m="4307200">to</span> <span m="4307370">do</span>
  <span m="4307810">is</span> <span m="4308070">when it's</span> <span m="4308540">replanning,</span>
  <span m="4309680">it</span> <span m="4310160">finds</span> <span m="4310700">a path</span>
  <span m="4311540">to</span> <span m="4311865">a node</span> <span m="4312400">that</span>
  <span m="4312490">we</span> <span m="4312630">haven't</span> <span m="4312890">visited</span>
  <span m="4313175">before,</span> <span m="4313460">because</span> <span m="4313820">it</span>
  <span m="4314270">thinks</span> <span m="4314810">there</span> <span m="4315150">is
  a path</span> <span m="4315350">that leads</span> <span m="4315970">from</span>
  <span m="4316210">that</span> <span m="4316520">node</span> <span m="4316780">to
  the</span> <span m="4316980">goal node.</span></p><p><span m="4317410">And</span>
  <span m="4317840">so</span> <span m="4318050">this</span> <span m="4318210">means</span>
  <span m="4318470">that it's</span> <span m="4318660">efficient,</span> <span m="4319025">but</span>
  <span m="4319390">replanning</span> <span m="4320030">a</span> <span m="4320120">root</span>
  <span m="4320360">from</span> <span m="4320690">his</span> <span m="4320840">current</span>
  <span m="4321170">understanding</span> <span m="4322310">to</span> <span m="4322640">a
  node</span> <span m="4323160">that it</span> <span m="4323340">hasn't</span> <span
  m="4323590">examined</span> <span m="4324020">before.</span> <span m="4324990">And
  so</span> <span m="4325070">it</span> <span m="4325190">can</span> <span m="4325340">apply</span>
  <span m="4326090">something</span> <span m="4326480">like</span> <span m="4326640">the</span>
  <span m="4326970">D*</span> <span m="4327410">Lite</span> <span m="4327670">or</span>
  <span m="4327920">LPA*</span> <span m="4329720">with</span> <span m="4329930">this</span>
  <span m="4330140">formalism</span> <span m="4331580">in</span> <span m="4331700">order</span>
  <span m="4331940">to</span> <span m="4332120">search</span> <span m="4332840">through</span>
  <span m="4333320">the</span> <span m="4333440">graph</span> <span m="4334160">in</span>
  <span m="4334280">its</span> <span m="4334430">entirety</span> <span m="4335380">and</span>
  <span m="4335480">make</span> <span m="4335660">sure</span> <span m="4335930">that</span>
  <span m="4336110">in</span> <span m="4336340">a</span> <span m="4337370">greedily</span>
  <span m="4337970">efficient</span> <span m="4338390">manner,</span> <span m="4339110">we</span>
  <span m="4339260">hit</span> <span m="4340030">every</span> <span m="4340260">single</span>
  <span m="4340540">node</span> <span m="4340975">in the graph.</span></p><p><span
  m="4343590">AUDIENCE:</span> <span m="4343750">Is</span> <span m="4343910">this</span>
  <span m="4344070">[INAUDIBLE]</span> <span m="4346030">TSP</span> <span m="4346700">problem,</span>
  <span m="4347110">or the</span> <span m="4347180">traveling</span> <span m="4347560">solutions</span>
  <span m="4348050">problem?</span></p><p><span m="4349300">ERLEND HARBITZ:</span>
  <span m="4349515">I'm</span> <span m="4349730">not very</span> <span m="4350100">familiar</span>
  <span m="4350530">with the</span> <span m="4350960">TSP</span> <span m="4351390">problem.</span></p><p><span
  m="4352955">AUDIENCE:</span> <span m="4353172">You</span> <span m="4353390">try
  to--</span> <span m="4354320">and you</span> <span m="4354520">try</span> <span
  m="4354800">to</span> <span m="4355370">cover</span> <span m="4356390">all</span>
  <span m="4356570">the</span> <span m="4356630">Cs,</span> <span m="4356970">and</span>
  <span m="4357110">try</span> <span m="4357260">to</span> <span m="4357380">come</span>
  <span m="4357590">up</span> <span m="4357740">with</span> <span m="4357890">a</span>
  <span m="4357940">route</span> <span m="4358200">that is the</span> <span m="4358850">most</span>
  <span m="4359090">efficient,</span> <span m="4359980">and</span> <span m="4360450">try</span>
  <span m="4360840">to</span> <span m="4360950">visit</span> <span m="4361390">every</span>
  <span m="4361600">known</span> <span m="4362083">C</span> <span m="4362566">value</span>
  <span m="4363050">once.</span></p><p><span m="4364070">ERLEND HARBITZ:</span> <span
  m="4364250">OK.</span> <span m="4364430">Then in that</span> <span m="4364730">case,</span>
  <span m="4365000">yes.</span> <span m="4365350">It's</span> <span m="4365500">not</span>
  <span m="4365750">going</span> <span m="4365930">to</span> <span m="4366050">be</span>
  <span m="4366640">globally efficient.</span> <span m="4368610">As</span> <span m="4368820">you</span>
  <span m="4368890">said,</span> <span m="4369080">it's</span> <span m="4369200">going</span>
  <span m="4369320">to</span> <span m="4369380">be</span> <span m="4369470">an</span>
  <span m="4369530">approximation</span> <span m="4370220">for</span> <span m="4370490">it.</span>
  <span m="4370910">In</span> <span m="4371000">a</span> <span m="4371030">sense,</span>
  <span m="4371690">from</span> <span m="4372030">each</span> <span m="4372140">node</span>
  <span m="4372490">that</span> <span m="4372660">you visited,</span> <span m="4372970">you're</span>
  <span m="4373260">searching</span> <span m="4373640">for</span> <span m="4373790">the</span>
  <span m="4373910">next</span> <span m="4374330">best</span> <span m="4374570">choice.</span>
  <span m="4376030">So</span> <span m="4376300">it's</span> <span m="4376440">possible</span>
  <span m="4376880">you</span> <span m="4376970">can</span> <span m="4377120">corner</span>
  <span m="4377480">yourself.</span> <span m="4378540">But</span> <span m="4378680">it's</span>
  <span m="4378890">a</span> <span m="4378980">way</span> <span m="4379370">that</span>
  <span m="4379520">we</span> <span m="4379800">use what</span> <span m="4380120">we
  already</span> <span m="4380420">implemented</span> <span m="4382260">and</span>
  <span m="4382390">the</span> <span m="4382620">methods that</span> <span m="4382820">we've</span>
  <span m="4383030">already</span> <span m="4383300">established</span> <span m="4383930">to
  tackle</span> <span m="4384205">a</span> <span m="4384480">different type</span>
  <span m="4384745">of problem.</span></p><p><span m="4386430">AUDIENCE:</span> <span
  m="4386540">And</span> <span m="4386950">all</span> <span m="4387190">this</span>
  <span m="4387800">[INAUDIBLE]</span> <span m="4388210">usually</span> <span m="4388670">if</span>
  <span m="4388960">you</span> <span m="4390010">have</span> <span m="4390200">a</span>
  <span m="4390330">strategy</span> <span m="4390650">which</span> <span m="4390950">is</span>
  <span m="4391130">visit</span> <span m="4391360">the</span> <span m="4391670">closest</span>
  <span m="4392546">unvisited</span> <span m="4392962">node,</span> <span m="4393794">instead</span>
  <span m="4394210">of</span> <span m="4394470">making this</span> <span m="4395060">whole</span>
  <span m="4395270">incremental</span> <span m="4395600">path</span> <span m="4395810">from
  this study.</span> <span m="4397130">If</span> <span m="4397240">your</span> <span
  m="4397370">policy</span> <span m="4397820">is,</span> <span m="4398570">always</span>
  <span m="4399060">move to the</span> <span m="4399180">closest</span> <span m="4399420">unvisited</span>
  <span m="4399620">node,</span> <span m="4401000">how</span> <span m="4401300">worse</span>
  <span m="4401600">does</span> <span m="4401885">that get</span> <span m="4402870">compared</span>
  <span m="4403220">to</span> <span m="4403290">this?</span></p><p><span m="4408850">ERLEND
  HARBITZ:</span> <span m="4408890">I</span> <span m="4408930">think</span> <span
  m="4409090">it</span> <span m="4409400">would</span> <span m="4409610">behave</span>
  <span m="4410270">quite</span> <span m="4410600">similarly.</span> <span m="4411480">What
  we're just</span> <span m="4411850">trying</span> <span m="4412100">to</span> <span
  m="4412160">show</span> <span m="4412430">here</span> <span m="4412680">is</span>
  <span m="4412820">that</span> <span m="4412970">we</span> <span m="4413210">can</span>
  <span m="4414080">implement</span> <span m="4414800">that</span> <span m="4415040">problem</span>
  <span m="4415930">as</span> <span m="4416160">an</span> <span m="4416460">extension
  if this</span> <span m="4416760">happened.</span> <span m="4417360">It</span> <span
  m="4417500">may</span> <span m="4417660">be</span> <span m="4417770">an</span> <span
  m="4417910">efficient</span> <span m="4418340">way</span> <span m="4418490">to</span>
  <span m="4418610">do</span> <span m="4418790">it.</span></p><p><span m="4420950">AUDIENCE:</span>
  <span m="4421000">[INAUDIBLE]</span> <span m="4421475">probably</span> <span m="4421730">like,</span>
  <span m="4422180">zigzag.</span></p><p><span m="4423960">ERLEND HARBITZ:</span>
  <span m="4424100">Also,</span> <span m="4425110">if</span> <span m="4425750">you're</span>
  <span m="4426470">just</span> <span m="4426680">going</span> <span m="4426920">to</span>
  <span m="4428750">the</span> <span m="4428870">nearest</span> <span m="4429200">connected</span>
  <span m="4429680">node,</span> <span m="4431060">if you</span> <span m="4431330">corner</span>
  <span m="4431660">yourself</span> <span m="4433950">as</span> <span m="4434110">we</span>
  <span m="4434210">showed</span> <span m="4434420">here,</span> <span m="4435440">then</span>
  <span m="4435650">you</span> <span m="4435740">could</span> <span m="4435860">potentially</span>
  <span m="4436170">run</span> <span m="4436480">into</span> <span m="4436930">issues</span>
  <span m="4437200">if your</span> <span m="4437550">algorithm</span> <span m="4437680">doesn't</span>
  <span m="4437980">then</span> <span m="4438280">do an</span> <span m="4438690">extended</span>
  <span m="4439070">search</span> <span m="4439340">for</span> <span m="4439670">it.</span>
  <span m="4440180">If it</span> <span m="4440420">only</span> <span m="4440620">considers</span>
  <span m="4441300">nodes</span> <span m="4442100">in its</span> <span m="4442370">immediate</span>
  <span m="4442530">neighborhood</span> <span m="4443080">that hasn't</span> <span
  m="4443425">visited,</span> <span m="4444410">once it</span> <span m="4444640">corners</span>
  <span m="4445140">itself</span> <span m="4445470">and doesn't know</span> <span
  m="4445730">where to go.</span></p><p><span m="4447530">AUDIENCE:</span> <span m="4447635">Just</span>
  <span m="4447740">keep going</span> <span m="4448020">through</span> <span m="4448450">the</span>
  <span m="4448640">graph</span> <span m="4449000">until</span> <span m="4449060">you</span>
  <span m="4449410">hit</span> <span m="4449980">the</span> <span m="4450050">next</span>
  <span m="4450340">inhibited</span> <span m="4450810">node,</span> <span m="4451460">assuming</span>
  <span m="4451680">that</span> <span m="4451820">you</span> <span m="4451880">know</span>
  <span m="4452070">how many</span> <span m="4452250">invocations</span> <span m="4453060">you</span>
  <span m="4453200">have to do.</span></p><p><span m="4455400">AUDIENCE:</span> <span
  m="4455545">Sort</span> <span m="4455690">of like</span> <span m="4455870">the</span>
  <span m="4455930">random</span> <span m="4456270">walk type</span> <span m="4456740">approach?</span></p><p><span
  m="4458100">AUDIENCE:</span> <span m="4458185">Well,</span> <span m="4458270">I
  mean, kind</span> <span m="4458420">of</span> <span m="4458510">like the</span>
  <span m="4458900">greedy</span> <span m="4459200">version</span> <span m="4459470">of</span>
  <span m="4459590">it.</span> <span m="4460070">You</span> <span m="4460150">kind</span>
  <span m="4460280">of</span> <span m="4460640">start</span> <span m="4460890">from</span>
  <span m="4461120">a node,</span> <span m="4461930">and</span> <span m="4462050">then</span>
  <span m="4462320">you keep</span> <span m="4462560">searching,</span> <span m="4462990">you'll</span>
  <span m="4463100">see,</span> <span m="4463520">what</span> <span m="4463730">is</span>
  <span m="4463800">the</span> <span m="4463850">next</span> <span m="4464270">unvisited</span>
  <span m="4464726">node,</span> <span m="4465182">and you</span> <span m="4465638">pick
  that.</span> <span m="4467690">Kind of</span> <span m="4468115">like--</span> <span
  m="4468700">[INAUDIBLE]</span> <span m="4468980">some</span> <span m="4471430">you</span>
  <span m="4471510">see what you have</span> <span m="4471620">covered.</span> <span
  m="4472140">You see</span> <span m="4472370">what's</span> <span m="4472580">the</span>
  <span m="4472670">next</span> <span m="4472980">best</span> <span m="4473220">move.</span>
  <span m="4473960">You</span> <span m="4474080">make</span> <span m="4474340">that</span>
  <span m="4474993">move.</span> <span m="4475486">And</span> <span m="4475980">you're</span>
  <span m="4476380">done.</span> <span m="4479950">[INAUDIBLE]</span> <span m="4487680">So</span>
  <span m="4488510">you</span> <span m="4488810">probably don't</span> <span m="4489110">have
  this</span> <span m="4489290">[INAUDIBLE].</span></p><p><span m="4498270">ERLEND
  HARBITZ:</span> <span m="4498370">This</span> <span m="4498470">basically</span>
  <span m="4498670">ensures</span> <span m="4499170">you're</span> <span m="4499230">going</span>
  <span m="4499320">to find</span> <span m="4499740">the shortest</span> <span m="4499990">path</span>
  <span m="4500630">back</span> <span m="4500960">to</span> <span m="4501130">the
  next unvisited</span> <span m="4501621">node,</span> <span m="4502112">I guess.</span>
  <span m="4508990">We</span> <span m="4509170">also</span> <span m="4509440">can</span>
  <span m="4509590">use</span> <span m="4510180">these</span> <span m="4510440">incremental
  path planning</span> <span m="4510870">algorithms</span> <span m="4511730">for</span>
  <span m="4512500">anytime</span> <span m="4512760">planners.</span> <span m="4514540">And</span>
  <span m="4514750">the</span> <span m="4515230">benefit</span> <span m="4515660">of
  an</span> <span m="4515950">anytime</span> <span m="4516100">planner</span> <span
  m="4516350">is</span> <span m="4517240">that</span> <span m="4517900">we</span>
  <span m="4518490">quickly</span> <span m="4519230">reach a</span> <span m="4519520">plan</span>
  <span m="4520330">which</span> <span m="4520570">is</span> <span m="4521080">suboptimal.</span>
  <span m="4522730">And</span> <span m="4522850">then</span> <span m="4523000">from</span>
  <span m="4523240">there,</span> <span m="4524050">we</span> <span m="4524320">are</span>
  <span m="4524770">repairing</span> <span m="4525100">this</span> <span m="4525360">plan</span>
  <span m="4526660">to</span> <span m="4527030">approach</span> <span m="4527150">optimality.</span></p><p><span
  m="4528480">And</span> <span m="4528580">this</span> <span m="4528700">is</span>
  <span m="4528820">useful</span> <span m="4530080">in</span> <span m="4530170">the</span>
  <span m="4530260">real</span> <span m="4530440">world</span> <span m="4531430">where</span>
  <span m="4532000">you</span> <span m="4532110">want to</span> <span m="4532370">get</span>
  <span m="4532570">a</span> <span m="4532600">solution</span> <span m="4533060">that</span>
  <span m="4533140">comes</span> <span m="4533410">out</span> <span m="4533680">quickly,</span>
  <span m="4534100">and</span> <span m="4534610">we</span> <span m="4534710">want</span>
  <span m="4534730">to</span> <span m="4534790">start</span> <span m="4535270">along</span>
  <span m="4535300">our</span> <span m="4535630">solution,</span> <span m="4537050">and</span>
  <span m="4537110">then</span> <span m="4537360">repair it</span> <span m="4537790">as</span>
  <span m="4538100">we go.</span> <span m="4538900">And once</span> <span m="4539110">we</span>
  <span m="4539220">start</span> <span m="4539540">it,</span> <span m="4539830">we</span>
  <span m="4539950">need o save</span> <span m="4540370">some</span> <span m="4540560">more</span>
  <span m="4540760">time</span> <span m="4541390">if</span> <span m="4541520">your</span>
  <span m="4541650">reparations</span> <span m="4542230">might</span> <span m="4542460">lead</span>
  <span m="4542710">to</span> <span m="4542950">small</span> <span m="4543700">changes</span>
  <span m="4544050">and</span> <span m="4544425">that type of thing.</span> <span
  m="4545206">And</span> <span m="4545572">this</span> <span m="4545940">can be</span>
  <span m="4546190">handled</span> <span m="4546520">quite</span> <span m="4546700">efficiently</span>
  <span m="4547630">using</span> <span m="4547885">an</span> <span m="4548140">incremental</span>
  <span m="4548586">path</span> <span m="4549032">planning.</span></p><p><span m="4550450">So</span>
  <span m="4550550">what</span> <span m="4550600">happens</span> <span m="4551080">is</span>
  <span m="4551560">we</span> <span m="4551740">apply</span> <span m="4552760">something,</span>
  <span m="4553270">idea,</span> <span m="4555010">called</span> <span m="4556500">inflated</span>
  <span m="4556850">heuristics.</span> <span m="4557940">And</span> <span m="4558310">so</span>
  <span m="4558810">these</span> <span m="4559180">inflated</span> <span m="4559550">heuristics</span>
  <span m="4560140">are</span> <span m="4560290">essentially</span> <span m="4560830">increasing</span>
  <span m="4561630">our</span> <span m="4561790">heuristic</span> <span m="4562090">values</span>
  <span m="4562480">that</span> <span m="4562600">exist</span> <span m="4562990">on
  our</span> <span m="4563390">graph,</span> <span m="4563740">in our</span> <span
  m="4563890">true</span> <span m="4564010">graph,</span> <span m="4565150">by</span>
  <span m="4565660">a</span> <span m="4565720">cost</span> <span m="4565920">of</span>
  <span m="4566030">scale</span> <span m="4566270">factor.</span> <span m="4567130">And
  this</span> <span m="4567250">is</span> <span m="4567340">typically</span> <span
  m="4567700">very</span> <span m="4568000">large,</span> <span m="4568570">so</span>
  <span m="4568830">differences</span> <span m="4569620">in</span> <span m="4570560">heuristics</span>
  <span m="4571550">become</span> <span m="4571890">very large.</span></p><p><span
  m="4573290">This</span> <span m="4573340">means</span> <span m="4573580">that</span>
  <span m="4573730">once</span> <span m="4573980">we</span> <span m="4574090">start</span>
  <span m="4574770">along</span> <span m="4575010">a</span> <span m="4575210">path,</span>
  <span m="4577630">we</span> <span m="4578080">continue</span> <span m="4578540">along
  it.</span> <span m="4580030">And</span> <span m="4580270">that</span> <span m="4580540">causes</span>
  <span m="4580870">us</span> <span m="4580990">to</span> <span m="4581110">very</span>
  <span m="4581500">quickly</span> <span m="4581980">find</span> <span m="4582580">the</span>
  <span m="4582640">first</span> <span m="4583170">path</span> <span m="4583690">that</span>
  <span m="4584110">actually</span> <span m="4584590">works.</span> <span m="4585550">Then,</span>
  <span m="4585850">we</span> <span m="4586020">can view</span> <span m="4587070">reducing</span>
  <span m="4587530">those</span> <span m="4587810">heuristics</span> <span m="4588580">back</span>
  <span m="4588870">to</span> <span m="4589030">their</span> <span m="4589240">original</span>
  <span m="4589690">values</span> <span m="4590260">as</span> <span m="4590830">essentially</span>
  <span m="4592720">a</span> <span m="4592780">form</span> <span m="4593680">of</span>
  <span m="4593800">changing</span> <span m="4594460">our</span> <span m="4594780">[INAUDIBLE]
  causes</span> <span m="4596110">or--</span> <span m="4597640">so</span> <span m="4598030">it's
  a form of</span> <span m="4598380">replanning.</span> <span m="4599920">And</span>
  <span m="4600040">then</span> <span m="4600190">by</span> <span m="4600430">applying</span>
  <span m="4600820">the</span> <span m="4600910">principles</span> <span m="4601510">of</span>
  <span m="4601630">an</span> <span m="4601840">incremental</span> <span m="4602200">planner,</span>
  <span m="4603230">we</span> <span m="4603300">can</span> <span m="4603560">efficiently</span>
  <span m="4604280">use</span> <span m="4604570">the</span> <span m="4604660">data</span>
  <span m="4604900">that</span> <span m="4605050">we</span> <span m="4605200">already</span>
  <span m="4605620">have</span> <span m="4606880">in</span> <span m="4607000">order</span>
  <span m="4607210">to</span> <span m="4607360">perform</span> <span m="4607840">the</span>
  <span m="4607930">search</span> <span m="4609090">and</span> <span m="4609220">repair</span>
  <span m="4609475">our</span> <span m="4609730">solution</span> <span m="4609995">as</span>
  <span m="4610260">we</span> <span m="4610742">go.</span></p><p><span m="4613640">Finally,</span>
  <span m="4614380">we</span> <span m="4614470">want</span> <span m="4614710">to</span>
  <span m="4615160">make</span> <span m="4615700">explicit</span> <span m="4615840">to</span>
  <span m="4616070">you</span> <span m="4616240">guys</span> <span m="4617320">how</span>
  <span m="4618010">we</span> <span m="4618130">can</span> <span m="4618250">actually</span>
  <span m="4618640">apply</span> <span m="4619210">these</span> <span m="4619450">algorithms</span>
  <span m="4620470">to</span> <span m="4621255">mobile robotics.</span> <span m="4622930">Because</span>
  <span m="4623130">it</span> <span m="4623200">may</span> <span m="4623350">not</span>
  <span m="4623590">immediately</span> <span m="4624340">clear</span> <span m="4625150">how</span>
  <span m="4625300">we</span> <span m="4625390">go</span> <span m="4625600">from</span>
  <span m="4625960">a</span> <span m="4626380">full</span> <span m="4626800">space</span>
  <span m="4628240">to</span> <span m="4628570">a</span> <span m="4628780">graph.</span>
  <span m="4629680">Joe</span> <span m="4630280">on</span> <span m="4630370">this</span>
  <span m="4630900">kind of</span> <span m="4631240">briefly</span> <span m="4631830">when</span>
  <span m="4631930">he</span> <span m="4631990">talked</span> <span m="4632170">about</span>
  <span m="4632340">we</span> <span m="4632760">discretize</span> <span m="4633350">the</span>
  <span m="4633460">world.</span> <span m="4634150">But</span> <span m="4634230">we</span>
  <span m="4634330">want to</span> <span m="4634480">give</span> <span m="4634720">you</span>
  <span m="4634810">guys</span> <span m="4635090">some ideas</span> <span m="4635350">of</span>
  <span m="4635560">how</span> <span m="4635800">we</span> <span m="4635860">might</span>
  <span m="4636100">do</span> <span m="4636310">this</span> <span m="4636460">cleverly.</span></p><p><span
  m="4638500">So</span> <span m="4638980">in</span> <span m="4639100">order</span>
  <span m="4639250">to</span> <span m="4639460">build</span> <span m="4640010">a</span>
  <span m="4640140">graph</span> <span m="4640480">system</span> <span m="4641980">out</span>
  <span m="4642270">of</span> <span m="4643030">our</span> <span m="4643180">world</span>
  <span m="4643480">state,</span> <span m="4644050">we</span> <span m="4644290">differentiate</span>
  <span m="4645010">between</span> <span m="4645650">holonomic</span> <span m="4646030">systems</span>
  <span m="4646390">and</span> <span m="4646560">nonholonomic</span> <span m="4647090">systems,</span>
  <span m="4648110">which their</span> <span m="4648530">difference</span> <span m="4648720">is</span>
  <span m="4649270">just</span> <span m="4649630">in</span> <span m="4649780">terms</span>
  <span m="4650110">of</span> <span m="4650350">whether</span> <span m="4650650">your</span>
  <span m="4651370">constraints</span> <span m="4651850">are</span> <span m="4651940">differential</span>
  <span m="4652440">in nature</span> <span m="4652630">or</span> <span m="4653120">not.</span></p><p><span
  m="4655500">Then we</span> <span m="4655700">are</span> <span m="4655840">going</span>
  <span m="4655960">to</span> <span m="4656030">outline</span> <span m="4656530">three</span>
  <span m="4656830">methods</span> <span m="4657160">here</span> <span m="4657370">very</span>
  <span m="4657580">briefly,</span> <span m="4658280">cell</span> <span m="4658480">decomposition,</span>
  <span m="4659700">using</span> <span m="4659820">a</span> <span m="4660010">visibility</span>
  <span m="4660250">graph,</span> <span m="4660565">and</span> <span m="4661270">sampling-based</span>
  <span m="4662320">construction</span> <span m="4662500">methods.</span> <span m="4664280">So</span>
  <span m="4664360">for</span> <span m="4664560">cell decomposition</span> <span m="4665640">methods,</span>
  <span m="4666970">we</span> <span m="4667250">might</span> <span m="4667490">to</span>
  <span m="4667830">do</span> <span m="4668050">what you</span> <span m="4668420">would</span>
  <span m="4668700">expect,</span> <span m="4669520">take</span> <span m="4670150">the</span>
  <span m="4670240">free</span> <span m="4670540">space</span> <span m="4671350">in</span>
  <span m="4671500">this</span> <span m="4672130">region</span> <span m="4672445">and</span>
  <span m="4672760">split</span> <span m="4673150">it up</span> <span m="4673300">into</span>
  <span m="4673480">various</span> <span m="4673780">different</span> <span m="4674020">cells.</span>
  <span m="4675040">And</span> <span m="4675130">each of those</span> <span m="4675310">cells</span>
  <span m="4675655">is going to</span> <span m="4676000">represent</span> <span m="4676530">a</span>
  <span m="4676880">node</span> <span m="4677010">in our graph.</span> <span m="4678910">And
  how</span> <span m="4679360">we can do this</span> <span m="4679600">is</span> <span
  m="4679930">we</span> <span m="4680050">split</span> <span m="4680540">the</span>
  <span m="4680680">region</span> <span m="4681100">up</span> <span m="4682630">based</span>
  <span m="4682960">on</span> <span m="4683380">each</span> <span m="4683650">of</span>
  <span m="4683970">the</span> <span m="4684150">vertices</span> <span m="4684630">of</span>
  <span m="4684890">obstacles.</span></p><p><span m="4686680">So</span> <span m="4687100">we</span>
  <span m="4687250">draw</span> <span m="4687820">a</span> <span m="4687940">line</span>
  <span m="4689350">vertically</span> <span m="4691320">from</span> <span m="4691900">each
  of our vertices</span> <span m="4693940">that</span> <span m="4694570">goes</span>
  <span m="4694900">in</span> <span m="4694990">the</span> <span m="4695050">direction</span>
  <span m="4695610">away</span> <span m="4695980">from</span> <span m="4696190">the</span>
  <span m="4696310">obstacle.</span> <span m="4697060">So</span> <span m="4697270">at
  the</span> <span m="4697390">top</span> <span m="4697630">here,</span> <span m="4697930">it's</span>
  <span m="4698020">going</span> <span m="4698740">up and out</span> <span m="4698980">of</span>
  <span m="4699070">the</span> <span m="4699220">obstacle.</span> <span m="4700560">But</span>
  <span m="4700760">in</span> <span m="4700960">the</span> <span m="4701560">lower</span>
  <span m="4701860">left</span> <span m="4702070">corner</span> <span m="4702640">there,</span>
  <span m="4703570">both</span> <span m="4704200">up</span> <span m="4704500">and</span>
  <span m="4704710">down,</span> <span m="4705540">don't</span> <span m="4706010">intercept</span>
  <span m="4706305">the obstacles.</span> <span m="4706600">We</span> <span m="4706720">draw</span>
  <span m="4706930">them</span> <span m="4707020">in its</span> <span m="4707390">entirely.</span></p><p><span
  m="4708400">So</span> <span m="4708490">we</span> <span m="4708580">can</span> <span
  m="4708670">continue</span> <span m="4709090">this</span> <span m="4709270">throughout</span>
  <span m="4709540">the</span> <span m="4709690">entirety</span> <span m="4709975">of
  the</span> <span m="4710500">state</span> <span m="4710830">space,</span> <span
  m="4712110">and</span> <span m="4712210">then we</span> <span m="4712300">can</span>
  <span m="4712420">attribute</span> <span m="4713020">to</span> <span m="4713320">each</span>
  <span m="4713980">essential</span> <span m="4714450">cell</span> <span m="4715260">that
  we've</span> <span m="4715490">defined</span> <span m="4715930">through these</span>
  <span m="4716110">regions,</span> <span m="4716950">a</span> <span m="4716980">single</span>
  <span m="4717410">point</span> <span m="4717780">that</span> <span m="4717940">represents</span>
  <span m="4718920">the midpoint</span> <span m="4720570">of</span> <span m="4720730">that
  cell,</span> <span m="4721480">which</span> <span m="4721660">is</span> <span m="4721750">going</span>
  <span m="4721900">to</span> <span m="4722020">be</span> <span m="4722770">our</span>
  <span m="4723160">graph</span> <span m="4724090">node,</span> <span m="4725200">because</span>
  <span m="4725470">we</span> <span m="4725620">attribute</span> <span m="4726040">a</span>
  <span m="4726070">single</span> <span m="4726430">set of</span> <span m="4726820">coordinates</span>
  <span m="4727360">to</span> <span m="4727510">each of our</span> <span m="4727730">graph
  nodes.</span></p><p><span m="4730370">And</span> <span m="4730420">we</span> <span
  m="4730570">also,</span> <span m="4731140">to</span> <span m="4731320">make</span>
  <span m="4731560">sure</span> <span m="4731830">that</span> <span m="4731980">our</span>
  <span m="4732130">transitions</span> <span m="4732730">between</span> <span m="4733240">these</span>
  <span m="4733390">cells</span> <span m="4733900">are</span> <span m="4734080">consistent,</span>
  <span m="4735790">additional</span> <span m="4736350">nodes</span> <span m="4736870">at</span>
  <span m="4736980">the</span> <span m="4737070">midpoint</span> <span m="4738160">of</span>
  <span m="4738310">each</span> <span m="4738520">of</span> <span m="4738640">these</span>
  <span m="4739300">lines</span> <span m="4739660">that</span> <span m="4739750">we've</span>
  <span m="4739900">drawn,</span> <span m="4740830">where</span> <span m="4741400">we</span>
  <span m="4741490">make</span> <span m="4741700">the</span> <span m="4741790">distinction</span>
  <span m="4742390">that</span> <span m="4742540">from</span> <span m="4742780">here,</span>
  <span m="4743110">we've</span> <span m="4743230">actually</span> <span m="4743590">drawn</span>
  <span m="4743880">two</span> <span m="4744120">lines.</span> <span m="4744680">So</span>
  <span m="4744770">we</span> <span m="4744950">draw</span> <span m="4745290">the
  midpoint</span> <span m="4745450">between</span> <span m="4745920">all</span> <span
  m="4746080">of</span> <span m="4746200">those.</span> <span m="4747580">This</span>
  <span m="4747760">allows</span> <span m="4748150">us</span> <span m="4748300">to</span>
  <span m="4748450">essentially</span> <span m="4749020">create</span> <span m="4749320">a</span>
  <span m="4749390">graph through</span> <span m="4749760">the</span> <span m="4750130">entire</span>
  <span m="4750730">system,</span> <span m="4751740">and</span> <span m="4751840">we</span>
  <span m="4751960">connect</span> <span m="4754630">each</span> <span m="4754900">node</span>
  <span m="4755230">at</span> <span m="4755320">the</span> <span m="4755380">center</span>
  <span m="4755880">of</span> <span m="4755930">any given</span> <span m="4756400">cell</span>
  <span m="4757360">to</span> <span m="4757990">nodes that</span> <span m="4758300">are
  on the</span> <span m="4758580">boundary</span> <span m="4759285">of any</span>
  <span m="4759590">given cell.</span></p><p><span m="4761530">This</span> <span m="4761680">allows</span>
  <span m="4762040">us</span> <span m="4762430">to</span> <span m="4762520">create</span>
  <span m="4762910">a</span> <span m="4763140">full</span> <span m="4763400">graph</span>
  <span m="4764130">through</span> <span m="4764300">the</span> <span m="4764520">system,</span>
  <span m="4765000">that</span> <span m="4765160">we</span> <span m="4765250">can</span>
  <span m="4765430">move</span> <span m="4765865">through,</span> <span m="4766300">guaranteeing</span>
  <span m="4766810">that</span> <span m="4767050">none</span> <span m="4767410">of</span>
  <span m="4767610">these paths,</span> <span m="4768520">if</span> <span m="4768680">we</span>
  <span m="4768880">follow them</span> <span m="4769300">exactly</span> <span m="4770760">collide</span>
  <span m="4771030">with</span> <span m="4771300">the obstacles.</span> <span m="4773800">Now,</span>
  <span m="4773920">this</span> <span m="4774040">works</span> <span m="4774310">in</span>
  <span m="4774400">environments</span> <span m="4774940">where</span> <span m="4775270">the
  obstacles</span> <span m="4775550">are</span> <span m="4775730">2D</span> <span
  m="4775985">polygons,</span> <span m="4776240">and</span> <span m="4776430">the</span>
  <span m="4777100">path</span> <span m="4777460">is far</span> <span m="4777690">from
  optimal,</span> <span m="4778020">as</span> <span m="4778410">we</span> <span m="4778660">can</span>
  <span m="4778780">see,</span> <span m="4779460">but</span> <span m="4779610">we</span>
  <span m="4779740">can</span> <span m="4780070">plan</span> <span m="4780325">an</span>
  <span m="4780580">optimal</span> <span m="4780930">path</span> <span m="4781670">over</span>
  <span m="4781920">the</span> <span m="4782080">graph that</span> <span m="4782490">we</span>
  <span m="4782620">have</span> <span m="4782800">defined.</span> <span m="4784810">And</span>
  <span m="4784960">this</span> <span m="4785110">only</span> <span m="4785410">works</span>
  <span m="4785710">on</span> <span m="4786030">holonomic</span> <span m="4786270">systems.</span></p><p><span
  m="4788300">We</span> <span m="4788380">can</span> <span m="4788500">also</span>
  <span m="4788740">define</span> <span m="4789510">what</span> <span m="4789860">is</span>
  <span m="4790030">called a</span> <span m="4790460">visibility graph,</span> <span
  m="4790890">where we</span> <span m="4791170">essentially</span> <span m="4791620">draw</span>
  <span m="4791830">a</span> <span m="4791950">boundary</span> <span m="4792850">between</span>
  <span m="4793540">both</span> <span m="4794050">our</span> <span m="4794230">vehicle</span>
  <span m="4794590">down</span> <span m="4794830">there</span> <span m="4795010">at</span>
  <span m="4795100">that</span> <span m="4795160">bottom</span> <span m="4795460">left,</span>
  <span m="4796210">and</span> <span m="4796360">boundaries</span> <span m="4796810">around</span>
  <span m="4797110">our</span> <span m="4797230">obstacles.</span> <span m="4798470">These</span>
  <span m="4798650">boundaries</span> <span m="4799210">are</span> <span m="4799360">sufficiently</span>
  <span m="4800080">sized</span> <span m="4800770">so</span> <span m="4801100">that</span>
  <span m="4801670">if</span> <span m="4801880">the</span> <span m="4802030">center</span>
  <span m="4802710">of</span> <span m="4805220">the</span> <span m="4805460">vehicle</span>
  <span m="4805910">that</span> <span m="4805990">we're</span> <span m="4806230">defining</span>
  <span m="4806500">is</span> <span m="4807040">along</span> <span m="4807310">the</span>
  <span m="4807790">extended</span> <span m="4808530">edge</span> <span m="4808750">of</span>
  <span m="4808870">the</span> <span m="4809290">obstacle,</span> <span m="4810130">that
  the</span> <span m="4810580">vehicle</span> <span m="4810970">will</span> <span
  m="4811485">not</span> <span m="4811780">collide</span> <span m="4812650">with</span>
  <span m="4812870">that</span> <span m="4813380">obstacle.</span></p><p><span m="4815090">Then</span>
  <span m="4815440">for</span> <span m="4815650">each</span> <span m="4815860">of</span>
  <span m="4816070">the</span> <span m="4816550">vertices</span> <span m="4817900">of</span>
  <span m="4818440">the</span> <span m="4818820">extended</span> <span m="4819430">boundary</span>
  <span m="4819890">that we've</span> <span m="4820230">defined,</span> <span m="4821170">we</span>
  <span m="4821350">add in</span> <span m="4821680">a</span> <span m="4821770">new</span>
  <span m="4822640">node,</span> <span m="4823780">and</span> <span m="4823870">we</span>
  <span m="4824050">draw</span> <span m="4824710">all</span> <span m="4825010">lines</span>
  <span m="4825400">between</span> <span m="4825880">all</span> <span m="4826150">nodes,</span>
  <span m="4826930">which</span> <span m="4827260">can</span> <span m="4827590">be</span>
  <span m="4827740">connected</span> <span m="4828310">without</span> <span m="4828670">intersecting</span>
  <span m="4829830">the</span> <span m="4830090">extended</span> <span m="4830375">obstacles,</span>
  <span m="4832000">which</span> <span m="4832180">we've</span> <span m="4832300">drawn</span>
  <span m="4832760">here.</span> <span m="4833920">And</span> <span m="4834010">this</span>
  <span m="4834190">leads</span> <span m="4834550">to</span> <span m="4835000">a</span>
  <span m="4835450">graph</span> <span m="4835705">that</span> <span m="4835960">we</span>
  <span m="4836140">can,</span> <span m="4836380">again,</span> <span m="4837140">plan
  over.</span></p><p><span m="4839710">This, again,</span> <span m="4840530">works
  in</span> <span m="4840910">environments</span> <span m="4841320">where</span> <span
  m="4841520">the</span> <span m="4841770">obstacles are</span> <span m="4842170">2D</span>
  <span m="4842520">polygons.</span> <span m="4842810">But what's</span> <span m="4843070">nice</span>
  <span m="4843350">about</span> <span m="4843670">this</span> <span m="4843810">system</span>
  <span m="4844790">is</span> <span m="4844930">that</span> <span m="4845080">we</span>
  <span m="4845380">do</span> <span m="4845680">get</span> <span m="4846080">an optimal</span>
  <span m="4846320">path,</span> <span m="4846810">provided</span> <span m="4847200">that
  we assume</span> <span m="4848860">that</span> <span m="4849280">we assume that
  our</span> <span m="4849570">extension</span> <span m="4850220">of the</span> <span
  m="4850440">robot</span> <span m="4851040">itself</span> <span m="4852330">is</span>
  <span m="4853870">valid,</span> <span m="4854440">or</span> <span m="4854740">doesn't</span>
  <span m="4855460">act</span> <span m="4855895">too</span> <span m="4856480">much--</span>
  <span m="4859280">isn't</span> <span m="4859510">too</span> <span m="4859750">excessive</span>
  <span m="4860130">for</span> <span m="4860510">constraint.</span></p><p><span m="4863560">Finally,</span>
  <span m="4864880">going</span> <span m="4865150">back</span> <span m="4865450">to</span>
  <span m="4865960">some</span> <span m="4866190">of</span> <span m="4866250">the</span>
  <span m="4866410">random</span> <span m="4866710">sampling</span> <span m="4867100">methods</span>
  <span m="4867970">that</span> <span m="4868330">we</span> <span m="4868450">mentioned</span>
  <span m="4868750">at</span> <span m="4868810">the</span> <span m="4868900">very</span>
  <span m="4869200">beginning</span> <span m="4869590">of</span> <span m="4869710">this</span>
  <span m="4869860">lecture,</span> <span m="4870830">we've</span> <span m="4871030">introduced</span>
  <span m="4871690">sampling-based</span> <span m="4872400">roadmap</span> <span m="4872860">construction,</span>
  <span m="4874240">wherein</span> <span m="4874690">we</span> <span m="4874840">choose</span>
  <span m="4875410">nodes</span> <span m="4876460">randomly</span> <span m="4877270">or</span>
  <span m="4877450">deterministically</span> <span m="4878440">throughout</span> <span
  m="4879070">our</span> <span m="4879340">environment.</span> <span m="4879685">The</span>
  <span m="4880030">difference</span> <span m="4880360">here,</span> <span m="4880660">though,</span>
  <span m="4880990">is</span> <span m="4881140">that</span> <span m="4881410">we then</span>
  <span m="4881830">create</span> <span m="4882160">a</span> <span m="4882240">graph</span>
  <span m="4882750">out</span> <span m="4882980">of</span> <span m="4883210">this</span>
  <span m="4883360">system,</span> <span m="4883850">and</span> <span m="4884190">that
  we</span> <span m="4884530">reason</span> <span m="4885020">over</span> <span m="4885310">that</span>
  <span m="4885490">graph</span> <span m="4886000">using</span> <span m="4886300">something</span>
  <span m="4886610">like</span> <span m="4886750">an incremental</span> <span m="4887203">planning</span>
  <span m="4887656">algorithm.</span></p><p><span m="4889921">And</span> <span m="4890380">so</span>
  <span m="4890830">when</span> <span m="4891040">we</span> <span m="4891130">create</span>
  <span m="4891610">that</span> <span m="4891960">graph,</span> <span m="4892270">after</span>
  <span m="4892570">we've</span> <span m="4892720">sampled,</span> <span m="4893680">we</span>
  <span m="4893800">can</span> <span m="4893980">use</span> <span m="4894550">the</span>
  <span m="4894930">[INAUDIBLE]</span> <span m="4895310">neighbors</span> <span m="4895930">of</span>
  <span m="4896110">each node,</span> <span m="4897160">or</span> <span m="4897580">we</span>
  <span m="4897700">can</span> <span m="4897880">connect</span> <span m="4898340">each</span>
  <span m="4898570">node</span> <span m="4900220">to</span> <span m="4900950">every
  node</span> <span m="4901620">within</span> <span m="4901730">a</span> <span m="4901950">certain</span>
  <span m="4902480">radius,</span> <span m="4903250">which is</span> <span m="4903470">what</span>
  <span m="4903940">we've</span> <span m="4904110">drawn here.</span></p><p><span
  m="4906650">Finally,</span> <span m="4906970">in order</span> <span m="4907290">to</span>
  <span m="4908190">actually</span> <span m="4909430">move</span> <span m="4909800">between</span>
  <span m="4910105">nodes,</span> <span m="4910880">we</span> <span m="4911870">need
  to</span> <span m="4912700">have</span> <span m="4912960">some</span> <span m="4913180">knowledge
  about</span> <span m="4913350">the</span> <span m="4913430">dynamics</span> <span
  m="4914060">of</span> <span m="4914220">the</span> <span m="4914290">vehicle,</span>
  <span m="4914830">which</span> <span m="4914950">is</span> <span m="4915040">what
  we're</span> <span m="4915390">discussing here.</span> <span m="4916460">And</span>
  <span m="4917080">one</span> <span m="4917260">method</span> <span m="4917530">that</span>
  <span m="4917680">we</span> <span m="4917770">can</span> <span m="4917950">do</span>
  <span m="4918160">this</span> <span m="4918430">for</span> <span m="4918550">nonholonomic</span>
  <span m="4919240">systems</span> <span m="4920660">is</span> <span m="4920920">we</span>
  <span m="4921070">can</span> <span m="4922690">distinguish</span> <span m="4923470">between</span>
  <span m="4924670">different</span> <span m="4925030">paths</span> <span m="4925540">that</span>
  <span m="4925750">use</span> <span m="4925970">turning</span> <span m="4926320">right,</span>
  <span m="4926620">turning</span> <span m="4926950">left,</span> <span m="4927160">and</span>
  <span m="4927250">traveling</span> <span m="4927670">in</span> <span m="4927760">straight</span>
  <span m="4928150">lines.</span></p><p><span m="4929260">It</span> <span m="4929350">turns</span>
  <span m="4929620">out</span> <span m="4929800">that</span> <span m="4929980">the</span>
  <span m="4930070">shortest</span> <span m="4930460">path</span> <span m="4930730">between</span>
  <span m="4931090">two</span> <span m="4931360">points</span> <span m="4931720">can</span>
  <span m="4931840">be</span> <span m="4931960">defined</span> <span m="4932600">using</span>
  <span m="4933010">one</span> <span m="4933190">of</span> <span m="4933310">these</span>
  <span m="4933460">systems.</span> <span m="4936160">And</span> <span m="4936220">so</span>
  <span m="4936790">we</span> <span m="4937000">just</span> <span m="4937150">have</span>
  <span m="4937300">to</span> <span m="4937390">search</span> <span m="4937810">over</span>
  <span m="4938080">a</span> <span m="4938110">finite</span> <span m="4938620">number</span>
  <span m="4939040">of</span> <span m="4939160">options</span> <span m="4939510">in</span>
  <span m="4939860">order</span> <span m="4940140">to find</span> <span m="4940750">the</span>
  <span m="4940900">best</span> <span m="4941260">path</span> <span m="4941670">that</span>
  <span m="4941980">can</span> <span m="4942160">connect</span> <span m="4942370">any</span>
  <span m="4942870">two</span> <span m="4943150">nodes.</span> <span m="4946720">Hopefully,</span>
  <span m="4947500">that</span> <span m="4947620">has</span> <span m="4947790">given</span>
  <span m="4948070">you</span> <span m="4948240">some</span> <span m="4948643">intuition</span>
  <span m="4949450">into</span> <span m="4949640">how</span> <span m="4949920">we</span>
  <span m="4950100">can</span> <span m="4950290">apply</span> <span m="4950750">these</span>
  <span m="4952600">incremental</span> <span m="4953390">path</span> <span m="4953756">planning</span>
  <span m="4954490">[INAUDIBLE]</span> <span m="4955010">systems.</span> <span m="4955910">Are</span>
  <span m="4956210">there</span> <span m="4956510">any</span> <span m="4956810">questions?</span></p><p><span
  m="4959810">[APPLAUSE]</span></p><p>&nbsp;</p>
type: course
uid: 3f0fe2b01ecb407895fd5a906b8602cc

---
None