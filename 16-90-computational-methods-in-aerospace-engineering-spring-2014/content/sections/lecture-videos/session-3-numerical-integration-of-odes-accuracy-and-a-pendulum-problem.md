---
about_this_resource_text: <p><strong>Description:</strong> This session reviews the
  previous class on accuracy and discusses the student contest answers for the local
  order of accuracy problem. The session also implements a scheme for a real-life
  problem.</p> <p><strong>Instructor:</strong> Qiqi Wang</p><p>The recording quality
  of this video is the best available from the source.</p>
course_id: 16-90-computational-methods-in-aerospace-engineering-spring-2014
embedded_media:
- id: Video-YouTube-Stream
  media_location: BzQNgoTu5C4
  parent_uid: 48c8ddc2d7fc1355559c6992247518ef
  title: Video-YouTube-Stream
  type: Video
  uid: b88b76e43618c9a60a38227c7d67bc63
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/BzQNgoTu5C4/default.jpg
  parent_uid: 48c8ddc2d7fc1355559c6992247518ef
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: e4227965fdbc0df3bd261b573370a811
- id: 3Play-3PlayYouTubeid-MP4
  media_location: BzQNgoTu5C4
  parent_uid: 48c8ddc2d7fc1355559c6992247518ef
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 6edb9cb8ba6f2385e5f83a873ae7ca71
- id: BzQNgoTu5C4.srt
  parent_uid: 48c8ddc2d7fc1355559c6992247518ef
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-3-numerical-integration-of-odes-accuracy-and-a-pendulum-problem/BzQNgoTu5C4.srt
  title: 3play caption file
  type: null
  uid: 4a09df41a818fc07608ef4286e052c0c
- id: BzQNgoTu5C4.pdf
  parent_uid: 48c8ddc2d7fc1355559c6992247518ef
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-3-numerical-integration-of-odes-accuracy-and-a-pendulum-problem/BzQNgoTu5C4.pdf
  title: 3play pdf file
  type: null
  uid: a7b91abe1653f9181f902af790eaedba
- id: Caption-3Play YouTube id-SRT
  parent_uid: 48c8ddc2d7fc1355559c6992247518ef
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 3bc8f21ab57d158a76d754f5c511a855
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 48c8ddc2d7fc1355559c6992247518ef
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: ffad22933661cd619846ca975a0963a5
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT16.90S14/MIT16_90S14_L03_300k.mp4
  parent_uid: 48c8ddc2d7fc1355559c6992247518ef
  title: Video-Internet Archive-MP4
  type: Video
  uid: a88daff9f3a4b571ecbbc8badd604c70
inline_embed_id: 43952160session3:numericalintegrationofodes:accuracyandapendulumproblem71131745
layout: video
order_index: null
parent_uid: 809ebf7c44bfb36e8786306747d7e32f
related_resources_text: ''
short_url: session-3-numerical-integration-of-odes-accuracy-and-a-pendulum-problem
technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-3-numerical-integration-of-odes-accuracy-and-a-pendulum-problem
template_type: Tabbed
title: 'Session 3: Numerical Integration of ODEs: Accuracy and a pendulum problem'
transcript: '<p><span m="30">The</span> <span m="130">following</span> <span m="600">content</span>
  <span m="1090">is</span> <span m="1200">provided</span> <span m="1660">under</span>
  <span m="1900">a</span> <span m="1950">Creative</span> <span m="2400">Commons</span>
  <span m="2820">license.</span> <span m="3780">Your</span> <span m="3880">support</span>
  <span m="4400">will</span> <span m="4570">help</span> <span m="4790">MIT</span>
  <span m="5280">OpenCourseWare</span> <span m="6020">continue</span> <span m="6510">to</span>
  <span m="6680">offer</span> <span m="6980">high</span> <span m="7200">quality</span>
  <span m="7680">educational</span> <span m="8350">resources</span> <span m="8920">for</span>
  <span m="9040">free.</span> <span m="10100">To</span> <span m="10130">make</span>
  <span m="10330">a</span> <span m="10380">donation</span> <span m="11090">or</span>
  <span m="11310">to</span> <span m="11430">view</span> <span m="11640">additional</span>
  <span m="12050">materials</span> <span m="12670">from</span> <span m="12850">hundreds</span>
  <span m="13180">of</span> <span m="13280">MIT</span> <span m="13650">courses,</span>
  <span m="14950">visit</span> <span m="15150">MIT</span> <span m="15670">OpenCourseWare</span>
  <span m="16580">at</span> <span m="16920">[? ocw.mit.edu. ?]</span></p><p><span
  m="25854">QIQI WANG:</span> <span m="26350">All</span> <span m="26540">right.</span>
  <span m="26950">So</span> <span m="28350">last</span> <span m="28560">time</span>
  <span m="28790">I</span> <span m="28960">did</span> <span m="29270">this</span>
  <span m="29560">using</span> <span m="30090">the</span> <span m="30440">video</span>
  <span m="30740">recording,</span> <span m="31360">there</span> <span m="31480">was</span>
  <span m="31610">some</span> <span m="31880">complaints</span> <span m="32150">about</span>
  <span m="32409">the</span> <span m="32630">audio</span> <span m="33000">quality,</span>
  <span m="33540">so</span> <span m="33980">I''m</span> <span m="34170">wearing</span>
  <span m="34455">this</span> <span m="34740">today.</span> <span m="34860">It</span>
  <span m="35140">feels</span> <span m="35410">a</span> <span m="35450">little</span>
  <span m="35660">bit</span> <span m="35800">weird,</span> <span m="36110">but</span>
  <span m="36420">I''ll</span> <span m="36555">see</span> <span m="36690">how</span>
  <span m="38240">much</span> <span m="38600">better</span> <span m="38910">the</span>
  <span m="39270">audio</span> <span m="39600">quality</span> <span m="40032">came</span>
  <span m="40464">through.</span> <span m="41760">And</span> <span m="43060">you</span>
  <span m="43310">can</span> <span m="43620">ask</span> <span m="43900">your</span>
  <span m="44180">questions</span> <span m="44460">[INAUDIBLE].</span></p><p><span
  m="47320">All</span> <span m="47440">right.</span> <span m="48646">Can</span> <span
  m="49050">you</span> <span m="49250">pass</span> <span m="49530">this</span> <span
  m="49810">on,</span> <span m="50040">like</span> <span m="50260">everybody</span>
  <span m="50910">have</span> <span m="51170">one</span> <span m="51400">piece?</span>
  <span m="52630">So</span> <span m="52800">the</span> <span m="52970">purpose</span>
  <span m="53430">of</span> <span m="53770">this</span> <span m="53835">is</span>
  <span m="53900">for</span> <span m="54345">you</span> <span m="54790">to</span>
  <span m="55235">just</span> <span m="55680">write</span> <span m="56466">down</span>
  <span m="56860">anything</span> <span m="57430">that</span> <span m="57600">is</span>
  <span m="57790">not</span> <span m="58220">clear</span> <span m="59770">onto</span>
  <span m="60150">this</span> <span m="60440">piece</span> <span m="60600">of</span>
  <span m="60710">paper,</span> <span m="61760">and</span> <span m="62170">hand</span>
  <span m="62270">it</span> <span m="62520">to</span> <span m="62650">me</span> <span
  m="63160">after</span> <span m="63520">the</span> <span m="63620">lecture.</span>
  <span m="65060">What</span> <span m="65280">I''m</span> <span m="65390">going</span>
  <span m="65480">to</span> <span m="65570">do</span> <span m="65770">is,</span> <span
  m="66030">I''m</span> <span m="66160">going</span> <span m="66280">to</span> <span
  m="66520">draft</span> <span m="66630">these</span> <span m="67090">questions</span>
  <span m="67310">in</span> <span m="67790">the</span> <span m="68030">next</span>
  <span m="68270">section</span> <span m="68750">so</span> <span m="69230">that</span>
  <span m="72040">you''re</span> <span m="72240">not</span> <span m="72560">going</span>
  <span m="72803">to</span> <span m="73047">stay</span> <span m="73534">confused</span>
  <span m="73777">on</span> <span m="74021">what</span> <span m="74508">might</span>
  <span m="74995">confuse</span> <span m="75482">you.</span> <span m="76723">So</span>
  <span m="77216">this</span> <span m="77710">important</span> <span m="78176">[?
  Monte ?]</span> <span m="78642">cuts.</span> <span m="79110">You</span> <span m="79250">can</span>
  <span m="79550">write</span> <span m="79900">anything</span> <span m="80300">that</span>
  <span m="80500">is</span> <span m="80960">[? Monte, ?]</span> <span m="81420">and</span>
  <span m="81750">I''m</span> <span m="81960">going</span> <span m="82140">to</span>
  <span m="82240">be</span> <span m="82750">lacking</span> <span m="83580">them</span>
  <span m="83946">and</span> <span m="84312">try</span> <span m="84496">to</span>
  <span m="84680">earmark</span> <span m="86220">your</span> <span m="86620">[? Monte
  ?]</span> <span m="87540">points.</span></p><p><span m="90930">So</span> <span m="92580">we</span>
  <span m="92730">are</span> <span m="92890">continuing</span> <span m="93750">our</span>
  <span m="93940">discussion</span> <span m="96010">integration</span> <span m="96720">of</span>
  <span m="97010">ordinary</span> <span m="97560">differential</span> <span m="98260">equations.</span>
  <span m="100814">Let''s</span> <span m="101291">just</span> <span m="101770">do</span>
  <span m="101830">a</span> <span m="101970">brief</span> <span m="102110">review</span>
  <span m="102970">of</span> <span m="103220">what</span> <span m="103510">we</span>
  <span m="103750">did</span> <span m="104600">in</span> <span m="104760">the</span>
  <span m="104860">last</span> <span m="105360">lecture.</span> <span m="106410">So</span>
  <span m="106450">we</span> <span m="106630">are</span> <span m="106880">solving</span>
  <span m="107770">differential</span> <span m="108180">equations</span> <span m="108860">like</span>
  <span m="109530">du</span> <span m="109900">over</span> <span m="110220">dt</span>
  <span m="110910">equal</span> <span m="111070">to</span> <span m="111230">f</span>
  <span m="111540">of</span> <span m="112023">u.</span> <span m="113472">All</span>
  <span m="113955">right.</span> <span m="115410">We</span> <span m="115730">discretized</span>
  <span m="116200">the</span> <span m="116670">time</span> <span m="118190">into</span>
  <span m="119210">t0</span> <span m="119960">equal</span> <span m="119980">to</span>
  <span m="120180">0,</span> <span m="120340">t1</span> <span m="120400">equal</span>
  <span m="120820">to</span> <span m="121050">delta</span> <span m="121380">t,</span>
  <span m="122330">t2</span> <span m="123280">equal</span> <span m="123570">to</span>
  <span m="124000">2</span> <span m="124110">delta</span> <span m="124710">t,</span>
  <span m="124810">et</span> <span m="125040">cetera.</span> <span m="126640">We</span>
  <span m="126870">discretized</span> <span m="127680">the</span> <span m="127780">solution,</span>
  <span m="128350">u,</span> <span m="129190">into</span> <span m="129490">u0</span>
  <span m="130070">equally</span> <span m="130515">to</span> <span m="130960">u</span>
  <span m="131560">at</span> <span m="132320">t0,</span> <span m="132590">et</span>
  <span m="133400">cetera</span> <span m="133940">and</span> <span m="134520">ui</span>
  <span m="135880">denoted</span> <span m="136390">as</span> <span m="136790">the</span>
  <span m="136880">solution,</span> <span m="137430">u</span> <span m="138185">at</span>
  <span m="138510">ti.</span></p><p><span m="140540">Forward</span> <span m="140990">Euler,</span>
  <span m="142520">solves</span> <span m="142790">the</span> <span m="142980">equation</span>
  <span m="143450">like</span> <span m="143690">this.</span> <span m="145020">It</span>
  <span m="145190">is</span> <span m="145360">basically</span> <span m="146470">taking--</span>
  <span m="149080">I''m</span> <span m="149310">going</span> <span m="149470">to</span>
  <span m="149550">change</span> <span m="149830">the</span> <span m="149920">color.</span>
  <span m="150180">It</span> <span m="150440">is</span> <span m="150850">essentially</span>
  <span m="152420">taking</span> <span m="153000">this</span> <span m="153240">differential</span>
  <span m="153890">equation</span> <span m="154390">and</span> <span m="154710">approximate</span>
  <span m="156900">the</span> <span m="157010">time</span> <span m="157370">derivative</span>
  <span m="158860">into</span> <span m="159410">ui</span> <span m="160200">plus</span>
  <span m="160560">1</span> <span m="160980">minus</span> <span m="161360">ui</span>
  <span m="162170">divided</span> <span m="162730">by</span> <span m="162970">delta</span>
  <span m="163140">t.</span> <span m="163370">And</span> <span m="164810">on</span>
  <span m="164970">the</span> <span m="165080">right-hand</span> <span m="165470">side,</span>
  <span m="166330">it</span> <span m="166770">is</span> <span m="167230">the</span>
  <span m="167320">same</span> <span m="167560">thing.</span> <span m="168340">So</span>
  <span m="168540">this</span> <span m="168730">is</span> <span m="168860">forward</span>
  <span m="169080">Euler.</span></p><p><span m="171340">A</span> <span m="171810">midpoint</span>
  <span m="172280">rule,</span> <span m="172950">we</span> <span m="173140">are</span>
  <span m="173230">going</span> <span m="173360">to</span> <span m="173430">be</span>
  <span m="173560">doing</span> <span m="174900">something</span> <span m="175340">very</span>
  <span m="175760">similar,</span> <span m="176770">but</span> <span m="176930">instead,</span>
  <span m="180430">I''m</span> <span m="180720">going</span> <span m="180920">to</span>
  <span m="181040">discretize</span> <span m="182150">the</span> <span m="182270">time</span>
  <span m="182670">derivative</span> <span m="183150">term</span> <span m="183430">in</span>
  <span m="183560">a</span> <span m="183630">different</span> <span m="183970">way.</span>
  <span m="184320">I''m</span> <span m="184510">going</span> <span m="184630">to</span>
  <span m="184700">discretize</span> <span m="185380">the</span> <span m="185450">time</span>
  <span m="185820">derivative</span> <span m="186075">term</span> <span m="186330">into</span>
  <span m="187136">ui</span> <span m="187540">plus</span> <span m="187855">1</span>
  <span m="188170">minus</span> <span m="189000">ui</span> <span m="189520">minus</span>
  <span m="189870">1</span> <span m="190180">divided</span> <span m="190570">by</span>
  <span m="190750">what?</span></p><p><span m="191090">AUDIENCE:</span> <span m="191520">[INAUDIBLE].</span></p><p><span
  m="192380">QIQI WANG:</span> <span m="192810">2</span> <span m="193070">delta</span>
  <span m="193546">t.</span> <span m="194022">Exactly.</span> <span m="194500">So</span>
  <span m="194700">this</span> <span m="195070">is</span> <span m="195380">a</span>
  <span m="195570">consistent</span> <span m="196270">approximation</span> <span m="197200">of</span>
  <span m="197350">the</span> <span m="197470">time</span> <span m="197810">derivative.</span>
  <span m="199050">So</span> <span m="199240">that''s</span> <span m="199490">the</span>
  <span m="199630">only</span> <span m="199900">difference</span> <span m="200310">between</span>
  <span m="200575">forward</span> <span m="200840">Euler</span> <span m="201740">and</span>
  <span m="202040">midpoint</span> <span m="202440">rule.</span></p><p><span m="204210">And</span>
  <span m="204400">how</span> <span m="204590">to</span> <span m="204720">analyze</span>
  <span m="205320">the</span> <span m="205490">accuracy</span> <span m="206190">of</span>
  <span m="206330">these</span> <span m="206530">two</span> <span m="206670">methods?</span>
  <span m="208540">Taylor</span> <span m="208940">series</span> <span m="209400">expansion.</span>
  <span m="210170">In</span> <span m="210370">midpoint</span> <span m="210660">rule,</span>
  <span m="211270">we</span> <span m="211520">are</span> <span m="211650">expanding</span>
  <span m="212545">ui</span> <span m="212840">plus</span> <span m="213150">1</span>
  <span m="213910">equal</span> <span m="214300">to</span> <span m="214410">ui</span>
  <span m="215880">plus--</span> <span m="216370">you</span> <span m="216620">should</span>
  <span m="216870">become</span> <span m="217270">very</span> <span m="217750">familiar</span>
  <span m="218180">with</span> <span m="218410">this</span> <span m="221120">as</span>
  <span m="222130">you</span> <span m="222220">learn</span> <span m="222460">more.</span>
  <span m="223070">So</span> <span m="223170">ui</span> <span m="223710">prime,</span>
  <span m="224400">which</span> <span m="224620">is</span> <span m="225030">a</span>
  <span m="225250">shorthand</span> <span m="225690">for</span> <span m="225830">denoting</span>
  <span m="226600">du</span> <span m="226975">dt</span> <span m="227800">at</span>
  <span m="228440">ti</span> <span m="228850">time</span> <span m="229050">delta</span>
  <span m="230310">t</span> <span m="231110">plus</span> <span m="231940">half</span>
  <span m="232370">of</span> <span m="232720">ui</span> <span m="233490">double</span>
  <span m="233860">prime,</span> <span m="234380">which</span> <span m="234670">means</span>
  <span m="235120">du</span> <span m="235690">d</span> <span m="235900">squared</span>
  <span m="236120">u,</span> <span m="236390">dt</span> <span m="236740">squared,</span>
  <span m="237200">the</span> <span m="237290">second</span> <span m="237690">derivative</span>
  <span m="238170">of</span> <span m="238580">u</span> <span m="239400">times</span>
  <span m="239820">dt</span> <span m="240230">squared</span> <span m="240720">plus</span>
  <span m="242590">all</span> <span m="242810">the</span> <span m="242940">other</span>
  <span m="243280">terms.</span> <span m="243620">The</span> <span m="243710">third</span>
  <span m="243950">term</span> <span m="244280">is</span> <span m="244640">ui</span>
  <span m="245590">triple</span> <span m="245970">prime</span> <span m="246420">delta</span>
  <span m="246710">t</span> <span m="247690">cubed</span> <span m="248180">plus</span>
  <span m="248770">et</span> <span m="248980">cetera.</span> <span m="251710">Is</span>
  <span m="251890">a</span> <span m="252000">little</span> <span m="252250">bit</span>
  <span m="252420">too</span> <span m="252880">wide,</span> <span m="253335">maybe.</span></p><p><span
  m="255155">AUDIENCE:</span> <span m="255610">[INAUDIBLE].</span></p><p><span m="256975">QIQI
  WANG:</span> <span m="257430">You</span> <span m="257560">can''t</span> <span m="257740">see.</span>
  <span m="258079">Let</span> <span m="259070">me</span> <span m="259209">change</span>
  <span m="259720">this</span> <span m="259950">to</span> <span m="260110">a</span>
  <span m="260200">little</span> <span m="260490">bit</span> <span m="260959">darker</span>
  <span m="261410">green.</span> <span m="262730">And</span> <span m="263130">ui</span>
  <span m="263760">minus</span> <span m="264190">1</span> <span m="264920">is</span>
  <span m="265270">equal</span> <span m="265660">to--</span> <span m="266020">let</span>
  <span m="266260">me</span> <span m="266500">scroll</span> <span m="266850">this</span>
  <span m="267030">up</span> <span m="267190">a</span> <span m="267250">little</span>
  <span m="267480">bit--</span> <span m="268240">is</span> <span m="268660">ui</span>
  <span m="269870">minus</span> <span m="270660">ui</span> <span m="271000">prime</span>
  <span m="271420">delta</span> <span m="271590">t.</span> <span m="271700">Why</span>
  <span m="272090">minus?</span> <span m="275760">I''m</span> <span m="275890">going</span>
  <span m="276120">backwards.</span> <span m="277510">I</span> <span m="277670">should</span>
  <span m="278100">test</span> <span m="278580">delta</span> <span m="278740">t</span>
  <span m="279505">to</span> <span m="279770">minus</span> <span m="279910">delta</span>
  <span m="280170">t,</span> <span m="281350">right?</span> <span m="282640">This</span>
  <span m="282870">is</span> <span m="283050">why</span> <span m="283380">there</span>
  <span m="283560">is</span> <span m="283670">a</span> <span m="283720">minus</span>
  <span m="284070">here.</span> <span m="284760">And</span> <span m="285160">this</span>
  <span m="285340">term</span> <span m="285650">should</span> <span m="286120">have</span>
  <span m="286400">also</span> <span m="287260">a</span> <span m="287330">minus</span>
  <span m="287680">here</span> <span m="290550">because</span> <span m="291290">minus</span>
  <span m="291580">delta</span> <span m="291640">t</span> <span m="292200">is</span>
  <span m="292510">squared.</span> <span m="293050">So</span> <span m="293330">I</span>
  <span m="293570">have,</span> <span m="293900">again,</span> <span m="294390">altered</span>
  <span m="294790">it</span> <span m="294930">here.</span></p><p><span m="296300">And</span>
  <span m="296700">this</span> <span m="296860">term?</span> <span m="298710">Should</span>
  <span m="299210">I</span> <span m="299430">have</span> <span m="299570">a</span>
  <span m="299620">minus</span> <span m="299950">here?</span> <span m="301370">Yes.</span>
  <span m="302300">Because</span> <span m="302850">when</span> <span m="303090">I</span>
  <span m="303200">cube</span> <span m="303650">it,</span> <span m="304600">the</span>
  <span m="304690">negative</span> <span m="305060">sign</span> <span m="305390">is</span>
  <span m="305850">preserved</span> <span m="306090">[INAUDIBLE].</span> <span m="308100">So</span>
  <span m="308300">when</span> <span m="308590">I</span> <span m="309070">take</span>
  <span m="309450">the</span> <span m="309760">subtraction</span> <span m="310390">between</span>
  <span m="311140">ui</span> <span m="311370">plus</span> <span m="311635">1</span>
  <span m="311900">and</span> <span m="312130">ui</span> <span m="312560">minus</span>
  <span m="312940">1,</span> <span m="313380">this</span> <span m="313780">got</span>
  <span m="313950">canceled</span> <span m="314840">this</span> <span m="315190">gets</span>
  <span m="315540">doubled,</span> <span m="316390">this</span> <span m="317010">gets</span>
  <span m="317240">canceled,</span> <span m="318590">and</span> <span m="319200">this</span>
  <span m="319560">gets</span> <span m="320110">doubled.</span></p><p><span m="321990">So</span>
  <span m="322180">what</span> <span m="322430">I</span> <span m="322530">ended</span>
  <span m="322970">up</span> <span m="323140">having</span> <span m="324010">is</span>
  <span m="326820">ui</span> <span m="327800">prime</span> <span m="330430">plus</span>
  <span m="332290">1/6</span> <span m="333770">of</span> <span m="334080">ui</span>
  <span m="334590">triple</span> <span m="334960">prime</span> <span m="335950">delta</span>
  <span m="336150">t</span> <span m="336525">squared.</span> <span m="336900">I</span>
  <span m="336970">mean,</span> <span m="337130">this</span> <span m="337300">cube</span>
  <span m="337700">cancels</span> <span m="338170">with</span> <span m="338470">this</span>
  <span m="338730">delta</span> <span m="338990">t</span> <span m="339250">and</span>
  <span m="339685">delta</span> <span m="339902">t</span> <span m="340120">squared</span>
  <span m="341210">equal</span> <span m="341810">to</span> <span m="341940">f</span>
  <span m="342205">of</span> <span m="342470">ui.</span> <span m="344090">And</span>
  <span m="344410">this</span> <span m="344710">is</span> <span m="347490">n</span>
  <span m="347770">plus</span> <span m="348675">0</span> <span m="349140">delta</span>
  <span m="349570">t</span> <span m="350045">cubed,</span> <span m="350282">so</span>
  <span m="350520">this</span> <span m="350890">is</span> <span m="351190">the</span>
  <span m="351590">leading</span> <span m="352140">term</span> <span m="352400">of</span>
  <span m="352510">the</span> <span m="352580">truncation</span> <span m="352845">error.</span></p><p><span
  m="356270">Remember</span> <span m="356620">my</span> <span m="356830">origin</span>
  <span m="357300">original</span> <span m="357440">differential</span> <span m="357950">equation.</span>
  <span m="362890">My</span> <span m="363140">origin</span> <span m="363620">or</span>
  <span m="363760">differential</span> <span m="364280">equation</span> <span m="364690">is</span>
  <span m="364940">du</span> <span m="365110">dt</span> <span m="365440">equals</span>
  <span m="365770">f</span> <span m="366045">of</span> <span m="366320">u.</span>
  <span m="367460">The</span> <span m="367610">midpoint</span> <span m="368090">rule</span>
  <span m="368500">gives</span> <span m="368810">me</span> <span m="369120">du</span>
  <span m="369542">dt</span> <span m="370386">plus</span> <span m="371230">something</span>
  <span m="371740">times</span> <span m="372030">delta</span> <span m="372265">t</span>
  <span m="372500">squared</span> <span m="373910">and</span> <span m="374180">plus</span>
  <span m="374460">an</span> <span m="374580">even</span> <span m="374870">smaller</span>
  <span m="375230">terms</span> <span m="375686">equals</span> <span m="376142">f</span>
  <span m="376598">of</span> <span m="377054">u.</span> <span m="377970">So</span>
  <span m="378170">these</span> <span m="378610">additional</span> <span m="379330">term</span>
  <span m="381470">that</span> <span m="381720">is</span> <span m="381910">append</span>
  <span m="383000">from</span> <span m="383350">the</span> <span m="383460">discretization</span>
  <span m="384640">is</span> <span m="384850">the</span> <span m="384920">truncation</span>
  <span m="385470">error</span> <span m="385900">of</span> <span m="386110">the</span>
  <span m="386270">scheme,</span> <span m="387820">is</span> <span m="388070">the</span>
  <span m="388240">error</span> <span m="389260">made</span> <span m="389570">by</span>
  <span m="389710">the</span> <span m="389820">scheme,</span> <span m="390130">is</span>
  <span m="390320">the</span> <span m="390500">approximation.</span> <span m="391450">How</span>
  <span m="391610">much</span> <span m="394100">accuracy</span> <span m="394650">do</span>
  <span m="394780">I</span> <span m="394890">lose</span> <span m="395750">by</span>
  <span m="396230">approximating</span> <span m="397160">the</span> <span m="397300">derivative</span>
  <span m="397920">using</span> <span m="400590">discretization</span> <span m="401600">scheme?</span></p><p><span
  m="402900">All</span> <span m="403340">right.</span> <span m="403550">This</span>
  <span m="403750">is</span> <span m="403850">the</span> <span m="404280">truncation</span>
  <span m="404550">error.</span> <span m="404615">And</span> <span m="404680">if</span>
  <span m="404890">you</span> <span m="405020">do</span> <span m="405180">forward</span>
  <span m="405430">Euler,</span> <span m="406050">this</span> <span m="406290">truncation</span>
  <span m="406760">error,</span> <span m="407615">would</span> <span m="407950">it</span>
  <span m="408410">be</span> <span m="408530">delta</span> <span m="408685">t</span>
  <span m="408840">squared?</span> <span m="411300">No.</span> <span m="411940">It</span>
  <span m="412170">will</span> <span m="412300">be</span> <span m="413280">on</span>
  <span m="413340">the</span> <span m="413400">order</span> <span m="413680">of</span>
  <span m="413880">delta</span> <span m="414310">t.</span> <span m="414580">So</span>
  <span m="414660">forward</span> <span m="414880">Euler</span> <span m="415120">is</span>
  <span m="415560">less</span> <span m="416260">accurate</span> <span m="417630">than</span>
  <span m="418020">midpoint.</span> <span m="419564">All</span> <span m="420011">right.</span>
  <span m="420690">What</span> <span m="420860">we</span> <span m="420940">are</span>
  <span m="421020">talking</span> <span m="421280">about</span> <span m="421540">is</span>
  <span m="422360">this</span> <span m="422440">is</span> <span m="422520">called</span>
  <span m="423020">local</span> <span m="423140">truncation</span> <span m="423597">error.</span>
  <span m="424970">The</span> <span m="425130">reason</span> <span m="425470">why</span>
  <span m="425700">we</span> <span m="425850">call</span> <span m="426080">it</span>
  <span m="426210">local</span> <span m="426530">truncation</span> <span m="426670">error</span>
  <span m="427562">is</span> <span m="428008">going</span> <span m="428454">to</span>
  <span m="428900">be</span> <span m="429125">clear</span> <span m="429350">in</span>
  <span m="429490">the</span> <span m="429570">next</span> <span m="429870">section</span>
  <span m="430690">because</span> <span m="431060">there</span> <span m="431220">is</span>
  <span m="431810">a</span> <span m="431950">different</span> <span m="432860">way</span>
  <span m="433070">of</span> <span m="433330">assessing</span> <span m="433780">the</span>
  <span m="434160">error</span> <span m="434400">is</span> <span m="434555">the</span>
  <span m="434710">global</span> <span m="434975">error,</span> <span m="436300">and</span>
  <span m="436490">we''re</span> <span m="436570">going</span> <span m="436660">to</span>
  <span m="436760">be</span> <span m="436840">talking</span> <span m="437120">about</span>
  <span m="437290">that</span> <span m="437550">next</span> <span m="437890">one.</span>
  <span m="438387">Yes.</span></p><p><span m="438884">AUDIENCE:</span> <span m="439381">[INAUDIBLE].</span></p><p><span
  m="452800">QIQI WANG:</span> <span m="453320">Good</span> <span m="453625">question.</span>
  <span m="453930">So</span> <span m="454010">the</span> <span m="454130">question</span>
  <span m="454490">here</span> <span m="454730">is,</span> <span m="455800">why</span>
  <span m="456240">did</span> <span m="456390">I</span> <span m="456660">start</span>
  <span m="457078">expanding</span> <span m="457496">here.</span> <span m="458750">What</span>
  <span m="459120">if</span> <span m="459220">I</span> <span m="459460">happened</span>
  <span m="459780">to</span> <span m="459990">expand</span> <span m="460370">all</span>
  <span m="460570">the</span> <span m="460670">way</span> <span m="461000">here?</span>
  <span m="461980">I</span> <span m="462470">can</span> <span m="462960">write</span>
  <span m="463290">a</span> <span m="463685">hundred</span> <span m="464080">terms</span>
  <span m="464520">after</span> <span m="464662">this.</span> <span m="465090">There</span>
  <span m="465260">is</span> <span m="465520">infinitely</span> <span m="465740">many</span>
  <span m="466100">terms</span> <span m="466300">in</span> <span m="466430">the</span>
  <span m="466865">[INAUDIBLE]</span> <span m="469480">I</span> <span m="469680">stopped</span>
  <span m="470160">over</span> <span m="470625">here</span> <span m="471090">because</span>
  <span m="472920">I</span> <span m="473370">did</span> <span m="473800">this,</span>
  <span m="474240">and</span> <span m="474430">I</span> <span m="474540">know</span>
  <span m="474880">that</span> <span m="475220">this</span> <span m="475480">term</span>
  <span m="475725">is</span> <span m="475970">not</span> <span m="476300">attainable.</span>
  <span m="479890">If</span> <span m="479970">a</span> <span m="480070">term</span>
  <span m="480170">is</span> <span m="480360">not</span> <span m="480630">unattainable</span>
  <span m="481034">then</span> <span m="482650">this</span> <span m="482910">is</span>
  <span m="483170">going</span> <span m="483605">to</span> <span m="484040">be</span>
  <span m="484257">the</span> <span m="484475">leading</span> <span m="484910">term</span>
  <span m="485780">in</span> <span m="486030">your</span> <span m="487720">local</span>
  <span m="487980">truncation</span> <span m="488462">error.</span></p><p><span m="489910">The</span>
  <span m="490020">way</span> <span m="490230">you</span> <span m="490360">do</span>
  <span m="490590">your</span> <span m="490940">own</span> <span m="491230">is</span>
  <span m="491600">if</span> <span m="491820">I</span> <span m="491990">do</span>
  <span m="492310">an</span> <span m="492650">analysis</span> <span m="492840">of</span>
  <span m="492970">a</span> <span m="493470">scheme</span> <span m="493970">I''ve</span>
  <span m="494095">never</span> <span m="494220">seen</span> <span m="494410">before,</span>
  <span m="495920">I</span> <span m="497360">would</span> <span m="497620">expand</span>
  <span m="497860">it</span> <span m="499060">somewhere</span> <span m="499210">maybe</span>
  <span m="499900">onto</span> <span m="500340">here,</span> <span m="501360">and</span>
  <span m="501540">then</span> <span m="501750">dug</span> <span m="501950">it</span>
  <span m="502195">in</span> <span m="502440">to</span> <span m="502620">see</span>
  <span m="503730">if</span> <span m="505510">I</span> <span m="505720">get</span>
  <span m="507150">something</span> <span m="507560">that</span> <span m="507680">is</span>
  <span m="507800">not</span> <span m="507990">canceled.</span> <span m="508970">What</span>
  <span m="509140">happens</span> <span m="509480">if</span> <span m="509675">I</span>
  <span m="509870">see</span> <span m="510080">everything</span> <span m="510523">cancels?</span>
  <span m="512740">What</span> <span m="512909">if</span> <span m="513070">I</span>
  <span m="513220">see</span> <span m="513390">everything</span> <span m="513470">cancels,</span>
  <span m="514512">and</span> <span m="514860">all</span> <span m="515179">I</span>
  <span m="515470">have</span> <span m="515750">is</span> <span m="516230">exactly</span>
  <span m="516630">the</span> <span m="517025">[? C. ?]</span> <span m="517420">Why</span>
  <span m="517815">I</span> <span m="518210">might</span> <span m="518299">have</span>
  <span m="518499">an</span> <span m="518700">[? o ?]</span> <span m="519010">delta</span>
  <span m="519320">dt?</span></p><p><span m="520980">AUDIENCE:</span> <span m="521169">[INAUDIBLE].</span></p><p><span
  m="522639">QIQI WANG:</span> <span m="523130">I</span> <span m="523464">should</span>
  <span m="523799">expand</span> <span m="524130">more.</span> <span m="524285">Exactly.</span>
  <span m="525300">That</span> <span m="525560">means</span> <span m="525800">that</span>
  <span m="526250">delta</span> <span m="526580">t2</span> <span m="528380">may</span>
  <span m="528780">be</span> <span m="529180">the</span> <span m="529280">leading</span>
  <span m="530490">term</span> <span m="530700">of</span> <span m="530800">the</span>
  <span m="530890">truncation</span> <span m="531460">error,</span> <span m="533245">but</span>
  <span m="533720">would</span> <span m="533885">it</span> <span m="534050">be</span>
  <span m="534170">the</span> <span m="534603">leading</span> <span m="535036">term</span>
  <span m="535470">of</span> <span m="535735">truncation</span> <span m="536000">error</span>
  <span m="536435">if</span> <span m="536507">it</span> <span m="536579">is</span>
  <span m="536652">given</span> <span m="536870">less</span> <span m="537420">than</span>
  <span m="537710">delta</span> <span m="537870">t2?</span> <span m="539430">I</span>
  <span m="539510">don''t</span> <span m="539670">know.</span> <span m="540970">I</span>
  <span m="541080">only</span> <span m="541270">know</span> <span m="541660">that</span>
  <span m="541920">the</span> <span m="542300">scheme</span> <span m="542756">is</span>
  <span m="543212">at</span> <span m="543441">least</span> <span m="543670">third</span>
  <span m="543860">order</span> <span m="544150">accurate</span> <span m="544595">[INAUDIBLE].</span>
  <span m="546820">Only</span> <span m="547230">when</span> <span m="547460">I</span>
  <span m="547880">expand</span> <span m="548260">it</span> <span m="548730">more</span>
  <span m="548886">terms,</span> <span m="549043">I</span> <span m="549121">can</span>
  <span m="549200">know</span> <span m="549430">it</span> <span m="549610">happened</span>
  <span m="550040">in</span> <span m="550130">what</span> <span m="550490">order</span>
  <span m="550870">of</span> <span m="551080">accuracy</span> <span m="551524">this</span>
  <span m="551968">means.</span></p><p><span m="554190">All</span> <span m="554230">right.</span>
  <span m="555110">So</span> <span m="555280">when</span> <span m="555600">you</span>
  <span m="556010">[? file ?]</span> <span m="556540">a</span> <span m="556620">scheme,</span>
  <span m="557550">when</span> <span m="557720">you''re</span> <span m="557850">not</span>
  <span m="558060">sure,</span> <span m="560190">expand</span> <span m="560470">it</span>
  <span m="560725">to</span> <span m="560980">whatever</span> <span m="561510">you</span>
  <span m="561640">like</span> <span m="561960">and</span> <span m="562160">see</span>
  <span m="562470">if</span> <span m="562833">everything</span> <span m="563196">cancels.</span>
  <span m="563560">If</span> <span m="564420">everything</span> <span m="564800">does</span>
  <span m="565050">cancel,</span> <span m="565520">then</span> <span m="565850">it</span>
  <span m="566030">means</span> <span m="566280">you</span> <span m="566700">need</span>
  <span m="566980">to</span> <span m="567240">go</span> <span m="567450">back</span>
  <span m="567750">and</span> <span m="567930">expand</span> <span m="568490">more</span>
  <span m="568870">terms.</span> <span m="570990">Is</span> <span m="571310">it</span>
  <span m="571380">clear?</span></p><p><span m="575520">In</span> <span m="575680">the</span>
  <span m="575750">last</span> <span m="576010">lecture,</span> <span m="577480">I</span>
  <span m="577720">asked</span> <span m="577990">you</span> <span m="578180">to</span>
  <span m="578390">do</span> <span m="578670">this</span> <span m="579330">to</span>
  <span m="579570">find</span> <span m="579900">out</span> <span m="580180">who</span>
  <span m="580280">the</span> <span m="580430">best</span> <span m="581300">X</span>
  <span m="581710">schemes.</span> <span m="582872">Can</span> <span m="583290">I</span>
  <span m="584270">have</span> <span m="584430">a</span> <span m="584520">show</span>
  <span m="584670">of</span> <span m="584820">hand</span> <span m="585090">of</span>
  <span m="585300">who</span> <span m="585630">did</span> <span m="586064">this?</span>
  <span m="587800">Who</span> <span m="587940">did</span> <span m="588050">this?</span>
  <span m="591260">Who</span> <span m="591380">attempted?</span> <span m="593730">Good.</span>
  <span m="596400">Who</span> <span m="596860">attempted</span> <span m="597440">the</span>
  <span m="597520">first</span> <span m="597810">one?</span></p><p><span m="600552">Let</span>
  <span m="601009">me</span> <span m="601466">see,</span> <span m="601930">1,</span>
  <span m="602230">2,</span> <span m="602530">3,</span> <span m="602922">4,</span>
  <span m="603314">5.</span> <span m="606650">I</span> <span m="606790">don''t</span>
  <span m="607040">need</span> <span m="607320">you</span> <span m="607490">to</span>
  <span m="607630">be</span> <span m="607890">successful,</span> <span m="608580">just</span>
  <span m="608870">tell</span> <span m="609110">me</span> <span m="609310">what</span>
  <span m="609590">is</span> <span m="609790">the</span> <span m="610010">best</span>
  <span m="610330">you</span> <span m="610630">got.</span></p><p><span m="614690">AUDIENCE:</span>
  <span m="615000">The</span> <span m="615490">first</span> <span m="615980">order</span>
  <span m="616470">[INAUDIBLE].</span></p><p><span m="616960">QIQI WANG:</span> <span
  m="617450">No.</span> <span m="617940">What</span> <span m="618070">is</span> <span
  m="618240">the</span> <span m="618480">scheme?</span> <span m="619320">So</span>
  <span m="619800">I</span> <span m="619930">want</span> <span m="620280">the</span>
  <span m="620500">product</span> <span m="620810">is,</span> <span m="621120">what</span>
  <span m="621330">is</span> <span m="621570">the--</span></p><p><span m="622190">AUDIENCE:</span>
  <span m="622460">[INAUDIBLE]</span> <span m="622800">coefficients?</span></p><p><span
  m="623670">QIQI WANG:</span> <span m="623920">Yes.</span></p><p><span m="624390">AUDIENCE:</span>
  <span m="624570">I</span> <span m="625008">just</span> <span m="625446">got</span>
  <span m="625884">r1.</span></p><p><span m="626322">QIQI WANG:</span> <span m="626760">Did</span>
  <span m="627198">you</span> <span m="627636">get--</span></p><p><span m="628580">AUDIENCE:</span>
  <span m="629080">I</span> <span m="629206">got</span> <span m="629333">u</span>
  <span m="629460">of</span> <span m="629765">t</span> <span m="630070">sub</span>
  <span m="630445">delta</span> <span m="630820">t.</span></p><p><span m="630970">QIQI
  WANG: Good.</span> <span m="631310">You</span> <span m="631510">get</span> <span
  m="632460">u</span> <span m="633616">of</span> <span m="634448">[INAUDIBLE]?</span></p><p><span
  m="635840">AUDIENCE:</span> <span m="636290">Yeah.</span></p><p><span m="637210">QIQI
  WANG:</span> <span m="637570">--t</span> <span m="637730">plus</span> <span m="637890">delta</span>
  <span m="638180">t.</span></p><p><span m="638640">AUDIENCE:</span> <span m="639100">--is</span>
  <span m="639560">equal</span> <span m="640020">to</span> <span m="640480">u</span>
  <span m="640940">prime.</span></p><p><span m="641400">QIQI WANG:</span> <span m="641610">--is</span>
  <span m="641710">equal</span> <span m="641810">to</span> <span m="641880">u</span>
  <span m="642020">prime</span> <span m="642440">at--</span></p><p><span m="642770">AUDIENCE:</span>
  <span m="643050">--t</span> <span m="643540">plus</span> <span m="644030">delta</span>
  <span m="644520">t.</span></p><p><span m="644940">QIQI WANG:</span> <span m="645090">--t</span>
  <span m="645140">plus</span> <span m="645190">delta</span> <span m="645240">t.</span></p><p><span
  m="645520">AUDIENCE:</span> <span m="645980">--plus</span> <span m="646133">u</span>
  <span m="646286">of</span> <span m="646440">t.</span></p><p><span m="646900">QIQI
  WANG:</span> <span m="647360">--plus</span> <span m="647640">u</span> <span m="647920">of</span>
  <span m="648060">t.</span></p><p><span m="648170">AUDIENCE:</span> <span m="648450">--plus</span>
  <span m="648650">u</span> <span m="648800">prime</span> <span m="649230">of</span>
  <span m="649445">t.</span></p><p><span m="649660">QIQI WANG:</span> <span m="650090">--plus</span>
  <span m="650360">u</span> <span m="650808">prime</span> <span m="651256">of</span>
  <span m="651704">t.</span> <span m="655160">Anybody</span> <span m="655620">get</span>
  <span m="655840">anything</span> <span m="656270">different,</span> <span m="656700">or</span>
  <span m="656870">everybody</span> <span m="657320">agrees</span> <span m="657440">with</span>
  <span m="657940">that?</span> <span m="662910">Five</span> <span m="663090">people</span>
  <span m="663470">got</span> <span m="663640">the</span> <span m="663720">same</span>
  <span m="663940">thing?</span></p><p><span m="664940">AUDIENCE:</span> <span m="665440">[INAUDIBLE].</span></p><p><span
  m="667652">QIQI WANG:</span> <span m="668080">OK.</span> <span m="669610">Let</span>
  <span m="669790">me</span> <span m="669930">write</span> <span m="670180">this</span>
  <span m="670430">in</span> <span m="670570">a</span> <span m="670630">more</span>
  <span m="672110">concise</span> <span m="672550">manner.</span> <span m="672870">t</span>
  <span m="673260">plus</span> <span m="673390">delta</span> <span m="673690">t</span>
  <span m="673920">is</span> <span m="674290">[? as ?]</span> <span m="674375">in</span>
  <span m="674460">f</span> <span m="674530">times</span> <span m="674860">x.</span>
  <span m="676650">t</span> <span m="677010">is</span> <span m="677180">at</span>
  <span m="677280">the</span> <span m="677340">current</span> <span m="677706">time</span>
  <span m="678072">set.</span> <span m="678440">So</span> <span m="678500">let</span>
  <span m="678660">me</span> <span m="678850">denote</span> <span m="679360">everything,</span>
  <span m="680050">t</span> <span m="680490">plus</span> <span m="680690">[INAUDIBLE]</span>
  <span m="681160">i</span> <span m="681405">plus</span> <span m="681650">1,</span>
  <span m="682782">i</span> <span m="683150">plus</span> <span m="683440">1,</span>
  <span m="683730">and</span> <span m="683950">this</span> <span m="684120">is</span>
  <span m="684290">i</span> <span m="684530">and</span> <span m="684820">i.</span>
  <span m="689136">So</span> <span m="689570">it''s</span> <span m="689840">just</span>
  <span m="690290">clearer</span> <span m="690910">not</span> <span m="691380">having</span>
  <span m="691770">all</span> <span m="692000">the</span> <span m="692340">tn,</span>
  <span m="692680">t</span> <span m="693020">plus</span> <span m="693150">delta</span>
  <span m="693470">t.</span> <span m="694460">If</span> <span m="694700">I</span>
  <span m="694850">know--</span> <span m="695903">come</span> <span m="696356">on.</span>
  <span m="696810">Come</span> <span m="697260">on.</span></p><p><span m="699450">And</span>
  <span m="699730">you</span> <span m="699860">are</span> <span m="699940">sure</span>
  <span m="700190">there</span> <span m="700320">is</span> <span m="700420">no</span>
  <span m="700600">delta</span> <span m="700890">t</span> <span m="701195">in</span>
  <span m="701500">front</span> <span m="701770">of</span> <span m="702060">this?</span>
  <span m="706110">I</span> <span m="706200">mean,</span> <span m="706470">forward</span>
  <span m="706930">Euler,</span> <span m="707140">and</span> <span m="707490">at</span>
  <span m="707530">midpoint,</span> <span m="708010">I</span> <span m="708110">have</span>
  <span m="708250">delta</span> <span m="708390">t''s.</span> <span m="710660">Yeah?</span></p><p><span
  m="710980">AUDIENCE:</span> <span m="711442">[INAUDIBLE].</span></p><p><span m="712828">QIQI
  WANG:</span> <span m="713290">OK.</span> <span m="713630">All</span> <span m="713790">the</span>
  <span m="713880">derivative</span> <span m="714420">terms</span> <span m="714730">should</span>
  <span m="714900">have</span> <span m="715160">delta</span> <span m="715460">t.</span></p><p><span
  m="717040">AUDIENCE:</span> <span m="717290">[INAUDIBLE].</span></p><p><span m="718631">QIQI
  WANG:</span> <span m="719080">You</span> <span m="719190">don''t</span> <span m="719340">have</span>
  <span m="719470">that?</span></p><p><span m="721630">AUDIENCE:</span> <span m="721760">[INAUDIBLE].</span></p><p><span
  m="732940">QIQI WANG:</span> <span m="733350">I</span> <span m="733821">was</span>
  <span m="734292">listing</span> <span m="734763">delta</span> <span m="734998">t''s.</span>
  <span m="736510">Sorry</span> <span m="736680">for</span> <span m="736970">that,</span>
  <span m="737270">but</span> <span m="739040">if</span> <span m="739490">I</span>
  <span m="739580">do</span> <span m="739790">the</span> <span m="739970">theta</span>
  <span m="740240">series</span> <span m="740510">and</span> <span m="740790">I</span>
  <span m="741070">just</span> <span m="741300">[? carefully ?],</span> <span m="741530">correctly,</span>
  <span m="742040">I</span> <span m="742130">should</span> <span m="742340">test</span>
  <span m="742670">that.</span> <span m="743310">And</span> <span m="743460">if</span>
  <span m="743620">you</span> <span m="743740">got</span> <span m="743930">something</span>
  <span m="744230">different,</span> <span m="745606">let</span> <span m="746044">me</span>
  <span m="746482">write</span> <span m="746920">it</span> <span m="747139">here.</span>
  <span m="747800">You''ve</span> <span m="747970">got</span> <span m="748180">something</span>
  <span m="748600">ui</span> <span m="749050">plus</span> <span m="749360">1</span>
  <span m="750410">equal</span> <span m="750930">to</span> <span m="751660">1/2</span>
  <span m="752330">of</span> <span m="752560">ui</span> <span m="753210">plus</span>
  <span m="753653">1</span> <span m="754096">prime</span> <span m="754540">delta</span>
  <span m="754850">t</span> <span m="755720">plus</span> <span m="756030">ui</span>
  <span m="757380">plus,</span> <span m="758045">you</span> <span m="758300">also</span>
  <span m="758700">get</span> <span m="759250">1/2</span> <span m="759570">here.</span>
  <span m="761740">Yes?</span> <span m="762000">You</span> <span m="762260">got</span>
  <span m="762530">something</span> <span m="762790">different?</span></p><p><span
  m="763260">AUDIENCE:</span> <span m="763730">[INAUDIBLE].</span></p><p><span m="767020">QIQI
  WANG:</span> <span m="767490">u</span> <span m="767660">prime</span> <span m="768080">of</span>
  <span m="768220">delta</span> <span m="768360">t.</span> <span m="768520">You</span>
  <span m="768720">get</span> <span m="768960">negative</span> <span m="769320">1/2</span>
  <span m="770260">here.</span> <span m="771750">All</span> <span m="771930">right.</span>
  <span m="772250">So</span> <span m="772450">we</span> <span m="772560">get</span>
  <span m="772790">three</span> <span m="773030">answers.</span> <span m="775840">Is</span>
  <span m="776460">that</span> <span m="776630">all?</span> <span m="778680">Anybody</span>
  <span m="779020">get</span> <span m="779230">anything</span> <span m="779570">different?</span>
  <span m="782970">Good.</span> <span m="783480">We</span> <span m="783670">have</span>
  <span m="783880">five</span> <span m="784110">people</span> <span m="784420">got</span>
  <span m="784720">three</span> <span m="785100">answers,</span> <span m="785610">so</span>
  <span m="785790">at</span> <span m="785970">least</span> <span m="786120">there</span>
  <span m="786490">are</span> <span m="786670">some</span> <span m="787116">agreements.</span></p><p><span
  m="791880">Who</span> <span m="792190">did</span> <span m="793130">the</span> <span
  m="793260">second</span> <span m="793530">one,</span> <span m="793820">best</span>
  <span m="794210">explicit,</span> <span m="794580">two-step</span> <span m="795340">scheme?</span>
  <span m="796120">Who</span> <span m="796300">attempted</span> <span m="797190">the</span>
  <span m="797300">second</span> <span m="797580">one?</span> <span m="798274">You?</span>
  <span m="799696">So</span> <span m="800170">we</span> <span m="800644">have</span>
  <span m="802066">1,</span> <span m="802540">2,</span> <span m="803014">3,</span>
  <span m="803490">4,</span> <span m="803905">5,</span> <span m="804320">6,</span>
  <span m="804735">7.</span> <span m="805591">More</span> <span m="806032">people</span>
  <span m="806252">did</span> <span m="806473">this.</span> <span m="807800">What</span>
  <span m="808050">is</span> <span m="808200">the</span> <span m="808290">best</span>
  <span m="808510">scheme</span> <span m="808850">you</span> <span m="809190">guys</span>
  <span m="809530">have</span> <span m="810030">got?</span></p><p><span m="813530">AUDIENCE:</span>
  <span m="814030">[INAUDIBLE].</span></p><p><span m="818600">QIQI WANG:</span> <span
  m="819010">The</span> <span m="819120">question</span> <span m="819450">is,</span>
  <span m="820140">can</span> <span m="820510">she--</span> <span m="820825">what''s</span>
  <span m="821140">your</span> <span m="821440">name?</span></p><p><span m="821740">AUDIENCE:</span>
  <span m="822225">[INAUDIBLE].</span></p><p><span m="823195">QIQI WANG:</span> <span
  m="823680">OK.</span> <span m="824300">Tren''s</span> <span m="824732">question</span>
  <span m="825164">is,</span> <span m="827330">can</span> <span m="827580">we</span>
  <span m="828000">express</span> <span m="828730">the</span> <span m="829170">derivatives</span>
  <span m="829880">as</span> <span m="830510">f</span> <span m="830880">as</span>
  <span m="831110">well?</span> <span m="831960">The</span> <span m="832120">answer</span>
  <span m="832360">is</span> <span m="832530">yes.</span> <span m="833330">So</span>
  <span m="833360">whenever</span> <span m="833900">I</span> <span m="834040">see</span>
  <span m="834290">a</span> <span m="834410">derivative,</span> <span m="835170">I</span>
  <span m="835290">can</span> <span m="835500">plug</span> <span m="835840">in</span>
  <span m="836180">the</span> <span m="836270">derivative</span> <span m="836870">into</span>
  <span m="837110">the</span> <span m="837210">differential</span> <span m="837670">equation.</span>
  <span m="838640">The</span> <span m="838750">differential</span> <span m="839200">equation</span>
  <span m="839640">is</span> <span m="839830">u</span> <span m="840050">prime</span>
  <span m="840415">equal</span> <span m="840780">to</span> <span m="841040">fu.</span>
  <span m="841900">So</span> <span m="842050">whenever</span> <span m="842570">I</span>
  <span m="842820">have</span> <span m="843140">f</span> <span m="843540">prime</span>
  <span m="843960">of</span> <span m="844050">i</span> <span m="844135">plus</span>
  <span m="844220">1,</span> <span m="844720">I</span> <span m="844810">can</span>
  <span m="844950">replace</span> <span m="845460">this</span> <span m="845580">as</span>
  <span m="846400">f</span> <span m="846760">of</span> <span m="847070">ui</span>
  <span m="848270">plus</span> <span m="848520">1.</span> <span m="849150">Whenever</span>
  <span m="849600">I</span> <span m="849770">have</span> <span m="850160">f</span>
  <span m="850590">prime</span> <span m="850990">of</span> <span m="851600">i,</span>
  <span m="851990">I</span> <span m="852380">can</span> <span m="852510">replace</span>
  <span m="853010">this</span> <span m="853180">as</span> <span m="853480">f</span>
  <span m="853904">of</span> <span m="854328">ui.</span></p><p><span m="855860">So</span>
  <span m="855980">what</span> <span m="856190">is</span> <span m="856330">your</span>
  <span m="856550">answer</span> <span m="856820">of</span> <span m="856990">the</span>
  <span m="857070">best</span> <span m="858020">explicit</span> <span m="861840">two-step</span>
  <span m="862340">scheme?</span></p><p><span m="862590">AUDIENCE:</span> <span m="863067">[INAUDIBLE].</span></p><p><span
  m="871653">QIQI WANG:</span> <span m="872140">Negative</span> <span m="872440">4ui?</span>
  <span m="873200">OK.</span></p><p><span m="873510">AUDIENCE:</span> <span m="873996">[INAUDIBLE].</span></p><p><span
  m="889770">QIQI WANG:</span> <span m="890270">f</span> <span m="890360">ui</span>
  <span m="891890">and--</span></p><p><span m="892390">AUDIENCE:</span> <span m="892890">--plus</span>
  <span m="893390">2</span> <span m="893890">f</span> <span m="894390">times</span>
  <span m="894890">u</span> <span m="895390">[? sub ?]</span> <span m="895890">i</span>
  <span m="896390">minus</span> <span m="896890">1.</span></p><p><span m="899674">QIQI
  WANG:</span> <span m="900140">OK.</span> <span m="900560">Good.</span> <span m="903190">Anybody</span>
  <span m="903750">who</span> <span m="903970">get</span> <span m="904190">anything</span>
  <span m="904570">different</span> <span m="905020">for</span> <span m="905180">best</span>
  <span m="905460">explicit</span> <span m="905700">two-step</span> <span m="906260">scheme?</span>
  <span m="910690">You</span> <span m="910800">all</span> <span m="910900">got</span>
  <span m="911070">the</span> <span m="911100">same</span> <span m="911130">thing?</span></p><p><span
  m="912021">AUDIENCE:</span> <span m="912462">[INAUDIBLE]</span></p><p><span m="912903">QIQI
  WANG:</span> <span m="913344">Delta</span> <span m="913785">t''s.</span> <span m="915350">And</span>
  <span m="915620">I</span> <span m="915710">guess</span> <span m="917360">delta</span>
  <span m="917850">t</span> <span m="918130">here.</span> <span m="918490">You</span>
  <span m="918650">must</span> <span m="919073">have</span> <span m="919496">that</span>
  <span m="919708">too.</span> <span m="919920">All</span> <span m="920040">right.</span>
  <span m="921270">Oh,</span> <span m="921530">wow.</span> <span m="922190">That''s</span>
  <span m="922380">amazing.</span> <span m="922800">Everybody</span> <span m="923278">got</span>
  <span m="923756">this?</span> <span m="925190">No</span> <span m="925510">disagreements?</span>
  <span m="928130">So</span> <span m="928650">the</span> <span m="929240">explicit</span>
  <span m="929720">two-step</span> <span m="930400">people</span> <span m="930810">are</span>
  <span m="931780">more</span> <span m="932280">in</span> <span m="932790">agreement</span>
  <span m="933220">than</span> <span m="933960">implicit</span> <span m="934450">one-step</span>
  <span m="934690">people.</span></p><p><span m="936160">Who</span> <span m="936380">did</span>
  <span m="936710">best</span> <span m="937090">implicit</span> <span m="938040">two-step</span>
  <span m="938660">scheme?</span> <span m="938950">Who</span> <span m="939396">attempted?</span>
  <span m="940290">You</span> <span m="940390">also</span> <span m="940530">did</span>
  <span m="940790">that?</span> <span m="941010">OK,</span> <span m="941290">great.</span>
  <span m="943290">And</span> <span m="943540">what</span> <span m="943700">is</span>
  <span m="943790">the</span> <span m="944180">answer?</span></p><p><span m="948012">AUDIENCE:</span>
  <span m="948491">[INAUDIBLE].</span></p><p><span m="948970">QIQI WANG:</span> <span
  m="949450">OK,</span> <span m="949790">you.</span></p><p><span m="951462">AUDIENCE:</span>
  <span m="951880">[INAUDIBLE].</span></p><p><span m="962680">QIQI WANG:</span> <span
  m="963080">I''m</span> <span m="963400">going</span> <span m="963560">to</span>
  <span m="963800">append</span> <span m="964170">a</span> <span m="964640">delta</span>
  <span m="964875">to</span> <span m="965110">for</span> <span m="965345">you.</span>
  <span m="965950">Plus--</span></p><p><span m="966930">AUDIENCE:</span> <span m="967420">[INAUDIBLE].</span></p><p><span
  m="980650">QIQI WANG:</span> <span m="981170">Wonderful.</span> <span m="982120">So</span>
  <span m="983340">can</span> <span m="983570">you</span> <span m="983660">tell</span>
  <span m="983870">me</span> <span m="983980">how</span> <span m="984210">you</span>
  <span m="984340">did</span> <span m="984560">that?</span></p><p><span m="985264">AUDIENCE:</span>
  <span m="985748">I</span> <span m="986232">did</span> <span m="986716">a</span>
  <span m="987200">bunch</span> <span m="987684">of</span> <span m="988168">Taylor</span>
  <span m="988652">[INAUDIBLE].</span></p><p><span m="991556">QIQI WANG:</span> <span
  m="992050">Nice.</span> <span m="994980">I</span> <span m="995220">get</span> <span
  m="995500">to</span> <span m="995680">have</span> <span m="995940">you</span> <span
  m="996290">show</span> <span m="996570">me</span> <span m="996740">how</span> <span
  m="997140">you</span> <span m="997260">did</span> <span m="997450">that</span> <span
  m="997944">later</span> <span m="998438">on.</span> <span m="999920">Who</span>
  <span m="1000160">the</span> <span m="1000390">best</span> <span m="1000760">explicit</span>
  <span m="1001240">three-step</span> <span m="1001745">scheme?</span> <span m="1002670">Anybody</span>
  <span m="1002890">try</span> <span m="1003210">that?</span> <span m="1006280">You</span>
  <span m="1006530">also</span> <span m="1006830">tried</span> <span m="1007060">that?</span>
  <span m="1007360">OK,</span> <span m="1007760">great.</span> <span m="1008590">I''m</span>
  <span m="1008830">going</span> <span m="1008960">to</span> <span m="1009050">have</span>
  <span m="1009240">you</span> <span m="1009330">as</span> <span m="1009730">an</span>
  <span m="1010103">instructor</span> <span m="1010476">here.</span> <span m="1012340">What</span>
  <span m="1012520">is</span> <span m="1012610">the</span> <span m="1012710">answer</span>
  <span m="1013040">for</span> <span m="1013170">that?</span></p><p><span m="1013906">AUDIENCE:</span>
  <span m="1014362">[INAUDIBLE].</span></p><p><span m="1020480">QIQI WANG:</span>
  <span m="1020690">Minus</span> <span m="1021020">what?</span> <span m="1021340">Sorry?</span></p><p><span
  m="1021600">AUDIENCE:</span> <span m="1022078">[INAUDIBLE].</span></p><p><span m="1028292">QIQI
  WANG:</span> <span m="1028770">18</span> <span m="1029248">and</span> <span m="1029730">sorry,</span>
  <span m="1030730">what?</span></p><p><span m="1031020">AUDIENCE:</span> <span m="1031508">9.</span></p><p><span
  m="1033948">QIQI WANG:</span> <span m="1034440">9.</span></p><p><span m="1034940">AUDIENCE:</span>
  <span m="1035421">9,</span> <span m="1036864">18,</span> <span m="1037826">10,</span>
  <span m="1038788">and</span> <span m="1039750">3.</span></p><p><span m="1040231">QIQI
  WANG:</span> <span m="1040712">18,</span> <span m="1041674">10,</span> <span m="1043599">and</span>
  <span m="1044150">3.</span> <span m="1044880">So</span> <span m="1045060">what</span>
  <span m="1045300">is</span> <span m="1045460">multiplied</span> <span m="1046119">on</span>
  <span m="1046260">this</span> <span m="1046470">one?</span></p><p><span m="1046967">AUDIENCE:</span>
  <span m="1047464">[INAUDIBLE]</span></p><p><span m="1064859">QIQI WANG:</span> <span
  m="1065370">ui</span> <span m="1065670">minus</span> <span m="1065800">2</span>
  <span m="1066100">and</span> <span m="1066968">ui</span> <span m="1067402">minus</span>
  <span m="1067836">2</span> <span m="1068270">prime.</span> <span m="1068950">So</span>
  <span m="1069150">all</span> <span m="1069280">the</span> <span m="1069360">primes</span>
  <span m="1069760">have</span> <span m="1070248">delta</span> <span m="1070736">t,</span>
  <span m="1071712">I</span> <span m="1072200">guess.</span> <span m="1076600">Great.</span>
  <span m="1079070">So</span> <span m="1079250">I''m</span> <span m="1079400">going</span>
  <span m="1079590">to</span> <span m="1080850">do</span> <span m="1081220">some</span>
  <span m="1081580">analysis</span> <span m="1082400">of</span> <span m="1082680">what</span>
  <span m="1083730">this</span> <span m="1084000">is.</span> <span m="1084230">I''m</span>
  <span m="1084380">going</span> <span m="1084500">to</span> <span m="1084580">go</span>
  <span m="1084720">back</span> <span m="1084950">to</span> <span m="1085270">this.</span>
  <span m="1086140">So</span> <span m="1086930">I</span> <span m="1087378">saved</span>
  <span m="1087826">the</span> <span m="1088274">documents.</span> <span m="1088722">Even</span>
  <span m="1089170">if</span> <span m="1089620">I</span> <span m="1089810">lose</span>
  <span m="1089930">it,</span> <span m="1090050">I''m</span> <span m="1090210">going</span>
  <span m="1090340">to</span> <span m="1090420">go</span> <span m="1090570">back</span>
  <span m="1090820">to</span> <span m="1090910">this.</span> <span m="1092470">But</span>
  <span m="1095530">what</span> <span m="1095790">I</span> <span m="1095850">want</span>
  <span m="1096200">to</span> <span m="1096250">show</span> <span m="1096780">right</span>
  <span m="1097090">now</span> <span m="1098620">is</span> <span m="1100680">first</span>
  <span m="1100960">of</span> <span m="1101080">all,</span> <span m="1102110">I''m</span>
  <span m="1102280">sure</span> <span m="1102640">some</span> <span m="1102790">of</span>
  <span m="1102890">you</span> <span m="1103075">did</span> <span m="1103260">this,</span>
  <span m="1103530">so</span> <span m="1103800">you</span> <span m="1104060">know</span>
  <span m="1104480">already</span> <span m="1104760">how</span> <span m="1104960">to</span>
  <span m="1105070">do</span> <span m="1105260">this.</span> <span m="1106300">But</span>
  <span m="1106460">I</span> <span m="1106490">also</span> <span m="1106870">want</span>
  <span m="1107130">to</span> <span m="1108420">see</span> <span m="1108670">especially</span>
  <span m="1109260">resolve</span> <span m="1110040">the</span> <span m="1110440">disagreement</span>
  <span m="1110805">on</span> <span m="1111170">the</span> <span m="1111545">first</span>
  <span m="1111732">one.</span></p><p><span m="1111920">So</span> <span m="1112630">that</span>
  <span m="1112870">is</span> <span m="1113000">what</span> <span m="1113160">I''m</span>
  <span m="1113280">going</span> <span m="1113410">to</span> <span m="1113500">do</span>
  <span m="1113710">first.</span> <span m="1114570">What</span> <span m="1114770">is</span>
  <span m="1114910">the</span> <span m="1115010">best</span> <span m="1115780">implicit,</span>
  <span m="1116520">one-step</span> <span m="1117125">scheme?</span> <span m="1117850">I''m</span>
  <span m="1118200">going</span> <span m="1118340">to</span> <span m="1118410">be</span>
  <span m="1119180">having</span> <span m="1119590">a</span> <span m="1119690">demonstration</span>
  <span m="1120410">of</span> <span m="1120970">that</span> <span m="1121270">right</span>
  <span m="1121540">now,</span> <span m="1123950">and</span> <span m="1124150">then</span>
  <span m="1124680">I''m</span> <span m="1124850">going</span> <span m="1124970">to</span>
  <span m="1125050">show</span> <span m="1125220">you</span> <span m="1125330">how</span>
  <span m="1125560">to</span> <span m="1125780">implement</span> <span m="1126270">a</span>
  <span m="1126760">scheme</span> <span m="1127370">once</span> <span m="1127580">you</span>
  <span m="1127700">derive</span> <span m="1128040">it.</span> <span m="1128650">You</span>
  <span m="1128750">derived</span> <span m="1129130">a</span> <span m="1129200">lot</span>
  <span m="1129380">of</span> <span m="1129490">schemes,</span> <span m="1129920">now</span>
  <span m="1130310">how</span> <span m="1130530">do</span> <span m="1130760">I</span>
  <span m="1131220">put</span> <span m="1131420">this</span> <span m="1131630">scheme</span>
  <span m="1132120">into</span> <span m="1133060">a</span> <span m="1133150">code,</span>
  <span m="1133640">into</span> <span m="1134745">a</span> <span m="1135010">production,</span>
  <span m="1135600">into</span> <span m="1135880">something</span> <span m="1136740">actually</span>
  <span m="1137120">wrong.</span></p><p><span m="1138610">So</span> <span m="1138800">first</span>
  <span m="1139040">of</span> <span m="1139180">all</span> <span m="1139420">the</span>
  <span m="1139530">best</span> <span m="1140180">implicit</span> <span m="1141370">one-step</span>
  <span m="1141720">scheme.</span> <span m="1142700">All</span> <span m="1142880">right.</span>
  <span m="1144280">I''m</span> <span m="1144470">going</span> <span m="1144670">to</span>
  <span m="1149580">append</span> <span m="1150020">something</span> <span m="1150990">after</span>
  <span m="1151340">this.</span> <span m="1156030">The</span> <span m="1156190">best</span>
  <span m="1158510">one-step</span> <span m="1159246">scheme.</span> <span m="1161630">So</span>
  <span m="1161800">the</span> <span m="1161900">scheme</span> <span m="1162900">has</span>
  <span m="1163220">to</span> <span m="1163380">be</span> <span m="1163850">ui</span>
  <span m="1164570">plus</span> <span m="1164920">1</span> <span m="1165840">equal</span>
  <span m="1166010">to</span> <span m="1166640">something</span> <span m="1167580">times</span>
  <span m="1168300">ui.</span> <span m="1169756">All</span> <span m="1170160">right.</span>
  <span m="1173180">Did</span> <span m="1173310">I</span> <span m="1173400">say</span>
  <span m="1174770">implicit,</span> <span m="1175460">one-step</span> <span m="1176055">scheme.</span>
  <span m="1177330">So</span> <span m="1177770">one-step</span> <span m="1178230">scheme</span>
  <span m="1178860">means</span> <span m="1179280">everything</span> <span m="1179800">has</span>
  <span m="1179980">to</span> <span m="1180120">be</span> <span m="1180280">written</span>
  <span m="1180560">in</span> <span m="1180660">terms</span> <span m="1180890">of</span>
  <span m="1181060">i</span> <span m="1181180">plus</span> <span m="1181470">1</span>
  <span m="1181780">and</span> <span m="1182020">i.</span> <span m="1184220">And</span>
  <span m="1185320">it</span> <span m="1185870">can</span> <span m="1186100">depend</span>
  <span m="1186490">on</span> <span m="1186850">ui,</span> <span m="1187990">ui</span>
  <span m="1188410">prime,</span> <span m="1189420">and</span> <span m="1189730">ui</span>
  <span m="1190530">plus</span> <span m="1190770">1</span> <span m="1190990">prime.</span>
  <span m="1191290">This</span> <span m="1191550">is</span> <span m="1192050">because</span>
  <span m="1192500">it</span> <span m="1192620">can</span> <span m="1192820">be</span>
  <span m="1193300">implicit.</span> <span m="1193780">If</span> <span m="1193960">it''s</span>
  <span m="1194120">explicit,</span> <span m="1194740">then</span> <span m="1194920">it</span>
  <span m="1195100">has</span> <span m="1195280">to</span> <span m="1195732">always</span>
  <span m="1195845">depend</span> <span m="1195958">on</span> <span m="1196071">i.</span></p><p><span
  m="1197090">All</span> <span m="1197507">right.</span> <span m="1199530">So</span>
  <span m="1199700">let</span> <span m="1199930">me</span> <span m="1200070">put</span>
  <span m="1200300">in</span> <span m="1200530">three</span> <span m="1203250">unknowns,</span>
  <span m="1204250">x</span> <span m="1204845">plus</span> <span m="1205150">y</span>
  <span m="1205920">plus</span> <span m="1206760">z.</span> <span m="1208020">And</span>
  <span m="1208250">these</span> <span m="1208430">are</span> <span m="1210290">unknowns.</span>
  <span m="1212490">And</span> <span m="1212770">what</span> <span m="1213290">do</span>
  <span m="1213440">I</span> <span m="1213570">do</span> <span m="1213920">to</span>
  <span m="1214570">make</span> <span m="1215070">the</span> <span m="1215240">scheme</span>
  <span m="1215640">as</span> <span m="1216010">accurate</span> <span m="1216590">as</span>
  <span m="1216780">possible?</span></p><p><span m="1217706">AUDIENCE:</span> <span
  m="1218132">Minimize</span> <span m="1218558">the</span> <span m="1218984">error?</span></p><p><span
  m="1219410">QIQI WANG:</span> <span m="1219840">Minimize</span> <span m="1220500">the</span>
  <span m="1220630">error.</span> <span m="1221030">Exactly.</span> <span m="1221820">And</span>
  <span m="1222210">the</span> <span m="1222350">error</span> <span m="1223190">can</span>
  <span m="1223460">only</span> <span m="1223700">be</span> <span m="1223850">[? appends
  ?]</span> <span m="1224330">from</span> <span m="1224640">Taylor</span> <span m="1224945">series</span>
  <span m="1225250">expansion</span> <span m="1225668">All</span> <span m="1226086">right.</span>
  <span m="1227340">So</span> <span m="1227490">Taylor</span> <span m="1228320">series</span>
  <span m="1228630">expansion,</span> <span m="1230340">again,</span> <span m="1230640">there</span>
  <span m="1230770">are</span> <span m="1230840">two</span> <span m="1231100">options.</span>
  <span m="1231980">One</span> <span m="1232180">option</span> <span m="1232620">is</span>
  <span m="1232880">to</span> <span m="1232980">expand</span> <span m="1233770">all</span>
  <span m="1234040">the</span> <span m="1234170">i</span> <span m="1234640">plus</span>
  <span m="1235010">1''s</span> <span m="1235930">at</span> <span m="1236774">i.</span>
  <span m="1237620">So</span> <span m="1237930">for</span> <span m="1238090">example,</span>
  <span m="1238550">ui</span> <span m="1239290">plus</span> <span m="1239610">1</span>
  <span m="1239930">is</span> <span m="1240220">equal</span> <span m="1240450">to</span>
  <span m="1240510">ui</span> <span m="1241410">plus</span> <span m="1242150">ui</span>
  <span m="1242640">prime</span> <span m="1243140">delta</span> <span m="1243310">t</span>
  <span m="1244040">plus</span> <span m="1245000">1/2</span> <span m="1245330">of</span>
  <span m="1246100">ui</span> <span m="1246255">double</span> <span m="1246410">prime</span>
  <span m="1246840">delta</span> <span m="1246980">t</span> <span m="1247160">square</span>
  <span m="1248520">plus--</span> <span m="1249380">I</span> <span m="1249520">can</span>
  <span m="1249760">do</span> <span m="1249890">more</span> <span m="1250180">terms--</span>
  <span m="1252010">triple</span> <span m="1252140">prime</span> <span m="1252620">delta</span>
  <span m="1252900">t</span> <span m="1253180">cubed</span> <span m="1253553">plus</span>
  <span m="1254300">o</span> <span m="1254590">delta</span> <span m="1254790">t</span>
  <span m="1255240">fourth.</span></p><p><span m="1257370">But</span> <span m="1258180">actually,</span>
  <span m="1258690">in</span> <span m="1258820">this</span> <span m="1259050">case,</span>
  <span m="1259650">another</span> <span m="1260430">equally</span> <span m="1261480">convenient</span>
  <span m="1262030">way</span> <span m="1262290">is</span> <span m="1262550">to</span>
  <span m="1262640">expand</span> <span m="1263300">ui''s</span> <span m="1264330">in</span>
  <span m="1264500">terms</span> <span m="1264760">of</span> <span m="1264920">ui''s</span>
  <span m="1265180">plus</span> <span m="1265630">1''s</span> <span m="1266660">because</span>
  <span m="1267070">there</span> <span m="1267220">are</span> <span m="1267330">as</span>
  <span m="1267610">many</span> <span m="1267920">terms</span> <span m="1269570">that</span>
  <span m="1269950">is</span> <span m="1271640">i</span> <span m="1271770">plus</span>
  <span m="1272000">1</span> <span m="1272110">as</span> <span m="1272620">there</span>
  <span m="1272890">are</span> <span m="1272970">many</span> <span m="1273210">terms</span>
  <span m="1273530">of</span> <span m="1273670">ui.</span> <span m="1274136">So</span>
  <span m="1274602">it</span> <span m="1274836">is</span> <span m="1275070">equally</span>
  <span m="1276930">convenient,</span> <span m="1277370">so</span> <span m="1277470">equally</span>
  <span m="1278830">cumbersome,</span> <span m="1279730">whichever</span> <span m="1280220">way</span>
  <span m="1280420">you</span> <span m="1280660">think</span> <span m="1280880">about</span>
  <span m="1281140">it.</span> <span m="1282590">u</span> <span m="1283060">prime</span>
  <span m="1283550">of</span> <span m="1284010">i</span> <span m="1284240">plus</span>
  <span m="1284470">1,</span> <span m="1284940">I</span> <span m="1285150">can</span>
  <span m="1285910">also</span> <span m="1286280">do</span> <span m="1286540">a</span>
  <span m="1286680">Taylor</span> <span m="1286960">series</span> <span m="1287330">expansion</span>
  <span m="1289070">also</span> <span m="1289820">by</span> <span m="1289970">just</span>
  <span m="1290130">taking</span> <span m="1290400">the</span> <span m="1290480">derivative.</span></p><p><span
  m="1291780">Now,</span> <span m="1293000">I''m</span> <span m="1293170">going</span>
  <span m="1293320">to</span> <span m="1293460">write</span> <span m="1293800">everything</span>
  <span m="1294350">[? correspondence ?]</span> <span m="1294650">here,</span> <span
  m="1294940">but</span> <span m="1296450">every</span> <span m="1296900">term</span>
  <span m="1297650">has</span> <span m="1298170">one</span> <span m="1298590">more</span>
  <span m="1299050">derivative</span> <span m="1300050">than</span> <span m="1300480">what</span>
  <span m="1300810">is</span> <span m="1301140">above.</span> <span m="1305150">So</span>
  <span m="1305330">when</span> <span m="1305550">I</span> <span m="1305710">have</span>
  <span m="1306880">third</span> <span m="1307120">derivative</span> <span m="1307500">here,</span>
  <span m="1307690">I</span> <span m="1308030">actually</span> <span m="1308290">have</span>
  <span m="1308890">fourth</span> <span m="1309260">derivative.</span> <span m="1311170">And</span>
  <span m="1311950">this</span> <span m="1312080">is</span> <span m="1312150">still</span>
  <span m="1312600">to</span> <span m="1312831">the</span> <span m="1313063">fourth.</span>
  <span m="1313990">So</span> <span m="1314080">all</span> <span m="1314250">the</span>
  <span m="1314410">delta</span> <span m="1314490">t''s</span> <span m="1314570">to</span>
  <span m="1314730">the</span> <span m="1315080">power</span> <span m="1315360">is</span>
  <span m="1315500">the</span> <span m="1315640">same,</span> <span m="1315975">but</span>
  <span m="1316310">all</span> <span m="1316510">the</span> <span m="1316650">derivatives</span>
  <span m="1316980">have</span> <span m="1317460">one</span> <span m="1317680">more</span>
  <span m="1318070">order</span> <span m="1319140">because</span> <span m="1319500">I''m</span>
  <span m="1319670">expanding</span> <span m="1320400">the</span> <span m="1320480">derivatives.</span></p><p><span
  m="1321960">And</span> <span m="1322210">when</span> <span m="1322410">I</span>
  <span m="1322520">should</span> <span m="1322760">take</span> <span m="1322970">the</span>
  <span m="1323050">second</span> <span m="1323410">load</span> <span m="1323520">of</span>
  <span m="1323680">derivatives,</span> <span m="1324290">I</span> <span m="1324440">should</span>
  <span m="1324600">be</span> <span m="1324690">taking</span> <span m="1325000">the</span>
  <span m="1325070">second</span> <span m="1325440">derivative</span> <span m="1326000">of</span>
  <span m="1326190">the</span> <span m="1326360">derivative,</span> <span m="1326980">which</span>
  <span m="1327210">is</span> <span m="1327360">the</span> <span m="1327530">third</span>
  <span m="1327920">derivative.</span> <span m="1328700">All</span> <span m="1329090">right.</span>
  <span m="1332262">Is</span> <span m="1332730">it</span> <span m="1333150">clear</span>
  <span m="1333420">why</span> <span m="1333800">I''m</span> <span m="1334020">having</span>
  <span m="1334410">one</span> <span m="1334780">more</span> <span m="1335005">derivative</span>
  <span m="1335230">here?</span></p><p><span m="1339360">Now,</span> <span m="1339730">this</span>
  <span m="1339940">is</span> <span m="1340100">all</span> <span m="1340340">I</span>
  <span m="1340470">need</span> <span m="1340670">to</span> <span m="1340850">expand.</span>
  <span m="1342360">And</span> <span m="1343080">to</span> <span m="1343190">figure</span>
  <span m="1343470">out</span> <span m="1343620">the</span> <span m="1343720">error,</span>
  <span m="1344130">we</span> <span m="1344310">need</span> <span m="1344510">to</span>
  <span m="1345330">plug</span> <span m="1346050">these</span> <span m="1346550">extensions</span>
  <span m="1347750">into</span> <span m="1348190">the</span> <span m="1348280">formula.</span>
  <span m="1349480">We</span> <span m="1349700">also</span> <span m="1350060">need</span>
  <span m="1350240">to</span> <span m="1350330">plot</span> <span m="1350660">something</span>
  <span m="1350980">else</span> <span m="1351452">in</span> <span m="1351924">the</span>
  <span m="1352396">formula.</span> <span m="1355320">Oh,</span> <span m="1355670">in</span>
  <span m="1355810">this</span> <span m="1355970">case,</span> <span m="1356250">we</span>
  <span m="1356370">don''t</span> <span m="1356610">need</span> <span m="1356940">to</span>
  <span m="1357270">plug</span> <span m="1357480">anything</span> <span m="1357780">else.</span>
  <span m="1358620">If</span> <span m="1361720">I</span> <span m="1361830">were</span>
  <span m="1361970">writing</span> <span m="1362290">the</span> <span m="1362390">scheme</span>
  <span m="1363000">not</span> <span m="1363350">as</span> <span m="1363690">u</span>
  <span m="1364000">prime,</span> <span m="1364340">but</span> <span m="1364746">as</span>
  <span m="1365152">X,</span> <span m="1365560">then</span> <span m="1365870">I</span>
  <span m="1365970">also</span> <span m="1366240">need</span> <span m="1366420">to</span>
  <span m="1366520">plug</span> <span m="1366725">in</span> <span m="1366930">the</span>
  <span m="1367010">differential</span> <span m="1367490">equation</span> <span m="1367830">into</span>
  <span m="1368030">the</span> <span m="1368230">formula.</span> <span m="1368630">But</span>
  <span m="1368810">I''m</span> <span m="1369040">already</span> <span m="1369900">writing</span>
  <span m="1370720">the</span> <span m="1370880">scheme</span> <span m="1371700">in</span>
  <span m="1371890">terms</span> <span m="1372250">of</span> <span m="1372935">u</span>
  <span m="1373320">prime,</span> <span m="1373760">then</span> <span m="1374060">I</span>
  <span m="1374180">don''t</span> <span m="1374380">need</span> <span m="1374770">to</span>
  <span m="1375160">plug</span> <span m="1375300">anything</span> <span m="1375326">else</span>
  <span m="1375353">into</span> <span m="1375380">the</span> <span m="1375525">formula.</span>
  <span m="1375960">I</span> <span m="1376070">just</span> <span m="1376270">need</span>
  <span m="1376450">to</span> <span m="1376630">plug</span> <span m="1376790">in</span>
  <span m="1376950">the</span> <span m="1377060">Taylor</span> <span m="1377545">expansions.</span></p><p><span
  m="1379910">When</span> <span m="1380090">I</span> <span m="1380180">plug</span>
  <span m="1380415">in</span> <span m="1380650">the</span> <span m="1380760">Taylor</span>
  <span m="1380980">expansions,</span> <span m="1382100">what</span> <span m="1382340">I</span>
  <span m="1382450">get</span> <span m="1382900">is,</span> <span m="1385640">I''m</span>
  <span m="1385830">going</span> <span m="1385990">to</span> <span m="1386120">write</span>
  <span m="1386390">down</span> <span m="1386580">the</span> <span m="1386650">truncation</span>
  <span m="1387150">error,</span> <span m="1387560">which</span> <span m="1388040">is</span>
  <span m="1389960">the</span> <span m="1390140">left-hand</span> <span m="1390510">side.</span>
  <span m="1392140">Well,</span> <span m="1392310">this</span> <span m="1392520">case,</span>
  <span m="1393200">it</span> <span m="1393480">is</span> <span m="1393650">actually</span>
  <span m="1394260">the</span> <span m="1394460">truncation</span> <span m="1395070">era</span>
  <span m="1396380">times</span> <span m="1396870">delta</span> <span m="1397030">t</span>
  <span m="1397170">is</span> <span m="1397540">equal</span> <span m="1397943">to</span>
  <span m="1398346">this.</span> <span m="1398548">I''m</span> <span m="1398750">going</span>
  <span m="1398910">to</span> <span m="1398980">let</span> <span m="1399210">you</span>
  <span m="1399300">know</span> <span m="1399540">why</span> <span m="1400690">I''m</span>
  <span m="1400850">writing</span> <span m="1401170">this.</span> <span m="1401900">But</span>
  <span m="1402540">the</span> <span m="1402690">truncation</span> <span m="1403000">error</span>
  <span m="1403310">times</span> <span m="1403510">delta</span> <span m="1403650">t</span>
  <span m="1403780">is</span> <span m="1404145">the</span> <span m="1404510">left-hand</span>
  <span m="1404950">side</span> <span m="1405410">minus</span> <span m="1405700">the</span>
  <span m="1405990">right-hand</span> <span m="1406260">side.</span></p><p><span m="1411340">And</span>
  <span m="1412200">let</span> <span m="1412410">me</span> <span m="1412560">just</span>
  <span m="1412780">write</span> <span m="1413220">down</span> <span m="1413580">term</span>
  <span m="1414062">by</span> <span m="1414544">term.</span> <span m="1415510">The</span>
  <span m="1415610">first</span> <span m="1415900">term</span> <span m="1417240">is</span>
  <span m="1417760">ui</span> <span m="1420010">plus,</span> <span m="1420295">which</span>
  <span m="1420437">is</span> <span m="1420580">this.</span> <span m="1420780">Let</span>
  <span m="1420950">me</span> <span m="1421290">actually</span> <span m="1422200">start</span>
  <span m="1422655">by</span> <span m="1423110">changing</span> <span m="1423565">the</span>
  <span m="1424020">color.</span> <span m="1425840">It</span> <span m="1426100">is</span>
  <span m="1426655">ui</span> <span m="1428530">plus</span> <span m="1429720">ui</span>
  <span m="1430260">prime</span> <span m="1430750">times</span> <span m="1430960">delta</span>
  <span m="1431360">t</span> <span m="1432145">plus</span> <span m="1432630">ui</span>
  <span m="1433270">double</span> <span m="1433580">prime</span> <span m="1434020">times</span>
  <span m="1434560">delta</span> <span m="1434780">t</span> <span m="1435150">squared</span>
  <span m="1435580">over</span> <span m="1435900">2.</span> <span m="1438290">plus</span>
  <span m="1439620">ui</span> <span m="1440170">triple</span> <span m="1440710">prime</span>
  <span m="1446700">delta</span> <span m="1446970">t</span> <span m="1447960">cubed</span>
  <span m="1448510">over</span> <span m="1448680">6</span> <span m="1449480">plus</span>
  <span m="1450320">our</span> <span m="1450740">delta</span> <span m="1450930">t</span>
  <span m="1451070">to</span> <span m="1451210">the</span> <span m="1451350">fourth.</span></p><p><span
  m="1454940">The</span> <span m="1455020">second</span> <span m="1455440">term</span>
  <span m="1455890">is</span> <span m="1457000">minus</span> <span m="1457490">x</span>
  <span m="1457820">times</span> <span m="1458160">ui--</span> <span m="1459110">let</span>
  <span m="1459210">me</span> <span m="1459480">changes</span> <span m="1461160">the</span>
  <span m="1461430">color</span> <span m="1461790">to</span> <span m="1462150">this--</span>
  <span m="1462740">minus</span> <span m="1463000">x</span> <span m="1463540">times</span>
  <span m="1463930">ui.</span></p><p><span m="1466680">Now,</span> <span m="1466900">what</span>
  <span m="1467030">is</span> <span m="1467170">the</span> <span m="1467270">third</span>
  <span m="1467540">term?</span> <span m="1467950">It''s</span> <span m="1468270">minus</span>
  <span m="1468800">y</span> <span m="1469270">times</span> <span m="1469610">ui</span>
  <span m="1469950">prime.</span> <span m="1471120">So</span> <span m="1471330">it</span>
  <span m="1471460">is</span> <span m="1471700">minus</span> <span m="1473120">y</span>
  <span m="1473790">times</span> <span m="1474420">ui</span> <span m="1475100">prime.</span>
  <span m="1475610">I''m</span> <span m="1475780">writing</span> <span m="1476100">down</span>
  <span m="1476380">here</span> <span m="1476630">so</span> <span m="1476760">that</span>
  <span m="1476950">everything</span> <span m="1477590">responding</span> <span m="1478010">to</span>
  <span m="1478130">prime</span> <span m="1478525">is</span> <span m="1478920">on</span>
  <span m="1479010">this</span> <span m="1479430">column.</span> <span m="1482000">And</span>
  <span m="1482400">the</span> <span m="1482470">third</span> <span m="1483030">term</span>
  <span m="1483420">is</span> <span m="1483680">minus</span> <span m="1483910">z</span>
  <span m="1484450">times</span> <span m="1484940">ui</span> <span m="1485260">plus</span>
  <span m="1485550">1</span> <span m="1485750">prime,</span> <span m="1486490">and</span>
  <span m="1486630">we</span> <span m="1486880">again</span> <span m="1487290">plug</span>
  <span m="1487745">in</span> <span m="1488200">the</span> <span m="1488330">Taylor</span>
  <span m="1488780">expansion.</span> <span m="1491920">But</span> <span m="1492190">everything</span>
  <span m="1492600">starts</span> <span m="1493290">at</span> <span m="1493560">the</span>
  <span m="1493640">prime,</span> <span m="1494160">so</span> <span m="1494350">I</span>
  <span m="1494510">have</span> <span m="1494670">a</span> <span m="1494750">minus</span>
  <span m="1495040">z</span> <span m="1496050">times</span> <span m="1496390">ui</span>
  <span m="1497430">prime</span> <span m="1497730">here.</span> <span m="1499495">I</span>
  <span m="1499940">have</span> <span m="1501372">minus</span> <span m="1503200">ui</span>
  <span m="1503580">dot</span> <span m="1504480">double</span> <span m="1504620">prime</span>
  <span m="1504895">times</span> <span m="1505890">z</span> <span m="1506145">delta</span>
  <span m="1506400">t.</span></p><p><span m="1507790">So</span> <span m="1507980">this</span>
  <span m="1508140">is</span> <span m="1508250">double</span> <span m="1508510">prime.</span>
  <span m="1509420">This</span> <span m="1509550">is</span> <span m="1510110">z</span>
  <span m="1510740">times</span> <span m="1511010">this,</span> <span m="1511970">and</span>
  <span m="1512290">I</span> <span m="1512370">also</span> <span m="1512680">have</span>
  <span m="1512970">this.</span> <span m="1513430">I</span> <span m="1513630">have</span>
  <span m="1513840">minus</span> <span m="1515220">ui</span> <span m="1516590">triple</span>
  <span m="1516790">prime</span> <span m="1517980">times</span> <span m="1519480">1/2</span>
  <span m="1519880">of</span> <span m="1520080">z</span> <span m="1520860">delta</span>
  <span m="1520940">t</span> <span m="1521650">to</span> <span m="1521720">the</span>
  <span m="1521820">cube.</span> <span m="1523170">And</span> <span m="1523620">I</span>
  <span m="1524070">don''t</span> <span m="1524520">even</span> <span m="1524890">need</span>
  <span m="1525190">to</span> <span m="1525520">write</span> <span m="1525800">this.</span>
  <span m="1526040">I''m</span> <span m="1526170">just</span> <span m="1526370">going</span>
  <span m="1526510">to</span> <span m="1526650">write</span> <span m="1529500">to</span>
  <span m="1529650">this</span> <span m="1530540">as</span> <span m="1531270">o</span>
  <span m="1531530">delta</span> <span m="1532870">t</span> <span m="1532980">cubed</span>
  <span m="1534790">times</span> <span m="1536210">z.</span></p><p><span m="1537190">All</span>
  <span m="1537580">right.</span></p><p><span m="1539660">AUDIENCE:</span> <span m="1540158">[INAUDIBLE].</span></p><p><span
  m="1544640">QIQI WANG:</span> <span m="1545140">Up</span> <span m="1545690">more?</span></p><p><span
  m="1546160">AUDIENCE:</span> <span m="1546526">No,</span> <span m="1546892">the</span>
  <span m="1547014">other</span> <span m="1547137">way.</span></p><p><span m="1547260">QIQI
  WANG:</span> <span m="1547370">The</span> <span m="1547455">other</span> <span m="1547540">way.</span>
  <span m="1548680">Scroll</span> <span m="1549010">up.</span> <span m="1550160">Right.</span>
  <span m="1551750">So</span> <span m="1551880">what</span> <span m="1552420">I''m</span>
  <span m="1552540">doing</span> <span m="1552770">is</span> <span m="1553050">I''m</span>
  <span m="1553220">expanding</span> <span m="1553800">this</span> <span m="1554000">term</span>
  <span m="1554450">as</span> <span m="1554900">the</span> <span m="1555130">first</span>
  <span m="1555620">line,</span> <span m="1556360">this</span> <span m="1556620">term</span>
  <span m="1556810">at</span> <span m="1556940">the</span> <span m="1557030">second</span>
  <span m="1557370">line,</span> <span m="1557750">this</span> <span m="1558020">term</span>
  <span m="1558510">as</span> <span m="1558673">the</span> <span m="1558836">third</span>
  <span m="1559000">line,</span> <span m="1559270">and</span> <span m="1559530">this</span>
  <span m="1559660">is</span> <span m="1559720">the</span> <span m="1560190">fourth</span>
  <span m="1560430">line.</span> <span m="1561750">I''m</span> <span m="1561890">just</span>
  <span m="1562070">writing</span> <span m="1562420">things</span> <span m="1562950">down,</span>
  <span m="1564783">and</span> <span m="1565206">it''s</span> <span m="1565630">different</span>
  <span m="1565950">lines,</span> <span m="1566440">and</span> <span m="1566670">I''m</span>
  <span m="1566860">also</span> <span m="1567150">aligning</span> <span m="1569100">the</span>
  <span m="1570160">same</span> <span m="1570450">derivatives</span> <span m="1570930">of</span>
  <span m="1571020">u</span> <span m="1571330">on</span> <span m="1571450">the</span>
  <span m="1571870">same</span> <span m="1572290">color.</span> <span m="1573130">Is</span>
  <span m="1573550">it</span> <span m="1573690">clear?</span></p><p><span m="1577870">So</span>
  <span m="1580030">how</span> <span m="1580270">do</span> <span m="1580400">I</span>
  <span m="1580520">choose</span> <span m="1580820">the</span> <span m="1580890">coefficients?</span>
  <span m="1585390">I''m</span> <span m="1585590">going</span> <span m="1585850">to</span>
  <span m="1586170">choose</span> <span m="1586710">coefficients</span> <span m="1587590">to</span>
  <span m="1587710">cancel</span> <span m="1588230">as</span> <span m="1588540">many</span>
  <span m="1588810">terms</span> <span m="1589320">as</span> <span m="1589720">possible.</span>
  <span m="1592380">I''m</span> <span m="1592560">going</span> <span m="1592710">to</span>
  <span m="1592830">choose,</span> <span m="1594160">first</span> <span m="1594440">of</span>
  <span m="1594580">all,</span> <span m="1596110">the</span> <span m="1596240">first</span>
  <span m="1596630">priority</span> <span m="1597480">is</span> <span m="1597620">to</span>
  <span m="1597810">cancel</span> <span m="1598670">anything</span> <span m="1600290">that</span>
  <span m="1600560">is</span> <span m="1601850">ui,</span> <span m="1602670">anything</span>
  <span m="1603140">multiplied</span> <span m="1603570">on</span> <span m="1603780">ui.</span>
  <span m="1604470">So</span> <span m="1604640">what</span> <span m="1604940">x</span>
  <span m="1605490">should</span> <span m="1605690">I</span> <span m="1605790">choose?</span></p><p><span
  m="1606742">AUDIENCE:</span> <span m="1607218">[INAUDIBLE].</span></p><p><span m="1608170">QIQI
  WANG:</span> <span m="1608650">Exactly.</span> <span m="1609330">x</span> <span
  m="1610020">has</span> <span m="1610310">to</span> <span m="1610460">be</span> <span
  m="1610840">equal</span> <span m="1611190">to</span> <span m="1611280">1</span>
  <span m="1611550">because</span> <span m="1612350">I</span> <span m="1612510">want</span>
  <span m="1613270">these</span> <span m="1613830">two</span> <span m="1614030">terms,</span>
  <span m="1614540">I</span> <span m="1614700">want</span> <span m="1614950">them</span>
  <span m="1615110">to</span> <span m="1615200">be</span> <span m="1615280">canceled.</span>
  <span m="1617590">The</span> <span m="1617760">only</span> <span m="1618000">way</span>
  <span m="1618140">to</span> <span m="1618240">cancel</span> <span m="1618640">this</span>
  <span m="1618950">is</span> <span m="1619260">we</span> <span m="1619753">choose</span>
  <span m="1619999">x</span> <span m="1620246">equal</span> <span m="1620410">to</span>
  <span m="1620575">1.</span> <span m="1620740">Is</span> <span m="1621030">it</span>
  <span m="1621525">clear?</span> <span m="1624610">And</span> <span m="1624930">what</span>
  <span m="1628630">should</span> <span m="1628790">I</span> <span m="1628910">do</span>
  <span m="1629230">to</span> <span m="1629450">ensure</span> <span m="1629970">that</span>
  <span m="1630560">this</span> <span m="1630970">term</span> <span m="1631450">also</span>
  <span m="1631680">cancels?</span></p><p><span m="1633660">AUDIENCE:</span> <span
  m="1634155">[INAUDIBLE].</span></p><p><span m="1643460">QIQI WANG:</span> <span
  m="1643600">What?</span> <span m="1644440">Somebody?</span></p><p><span m="1644870">AUDIENCE:</span>
  <span m="1645338">[INAUDIBLE].</span></p><p><span m="1646742">QIQI WANG:</span>
  <span m="1647210">y</span> <span m="1647530">plus</span> <span m="1647820">z</span>
  <span m="1648310">equal</span> <span m="1648350">to</span> <span m="1648790">1.</span></p><p><span
  m="1649230">AUDIENCE:</span> <span m="1649560">[INAUDIBLE].</span></p><p><span m="1649890">QIQI
  WANG:</span> <span m="1650250">Equal</span> <span m="1650407">to</span> <span m="1650565">delta
  t.</span> <span m="1650880">Exactly.</span> <span m="1651410">y</span> <span m="1651770">plus</span>
  <span m="1652020">z</span> <span m="1652580">has</span> <span m="1652830">to</span>
  <span m="1653150">equal</span> <span m="1653300">to</span> <span m="1653510">delta</span>
  <span m="1653880">t</span> <span m="1654270">in</span> <span m="1654470">order</span>
  <span m="1654970">for</span> <span m="1655030">this,</span> <span m="1656250">this,</span>
  <span m="1656730">and</span> <span m="1657010">this</span> <span m="1657180">to</span>
  <span m="1657300">cancel.</span> <span m="1658440">y</span> <span m="1658970">plus</span>
  <span m="1659250">z</span> <span m="1659505">has</span> <span m="1660360">equal</span>
  <span m="1660760">to</span> <span m="1661130">delta</span> <span m="1661613">t.</span>
  <span m="1662096">Do</span> <span m="1662579">we</span> <span m="1662740">have</span>
  <span m="1662901">a</span> <span m="1663062">question?</span> <span m="1664030">No?</span>
  <span m="1666170">All</span> <span m="1666400">right.</span> <span m="1668740">What</span>
  <span m="1669130">can</span> <span m="1669330">we</span> <span m="1669470">do</span>
  <span m="1669850">to</span> <span m="1670040">cancel</span> <span m="1670560">this?</span></p><p><span
  m="1677826">AUDIENCE:</span> <span m="1678318">[INAUDIBLE].</span></p><p><span m="1681270">QIQI
  WANG:</span> <span m="1681770">We</span> <span m="1682040">need</span> <span m="1682350">to</span>
  <span m="1682790">have</span> <span m="1683400">minus</span> <span m="1683700">z</span>
  <span m="1684000">delta</span> <span m="1684530">t</span> <span m="1685160">to</span>
  <span m="1685350">cancel</span> <span m="1685810">with</span> <span m="1686280">the</span>
  <span m="1686635">last</span> <span m="1686990">delta</span> <span m="1687255">t</span>
  <span m="1687520">squared</span> <span m="1687960">over</span> <span m="1688250">2.</span>
  <span m="1689460">So</span> <span m="1689690">we</span> <span m="1689930">have</span>
  <span m="1692720">z</span> <span m="1693150">delta</span> <span m="1693580">t</span>
  <span m="1693955">has</span> <span m="1694330">to</span> <span m="1695096">equal</span>
  <span m="1695480">to</span> <span m="1696910">delta</span> <span m="1697360">t</span>
  <span m="1697480">squared</span> <span m="1697730">over</span> <span m="1697970">2,</span>
  <span m="1698710">which</span> <span m="1698970">means</span> <span m="1699440">z</span>
  <span m="1699720">has</span> <span m="1699940">to</span> <span m="1700220">equal</span>
  <span m="1700500">to</span> <span m="1700900">1/2</span> <span m="1701150">of</span>
  <span m="1701400">delta</span> <span m="1701640">t.</span> <span m="1706960">Now,</span>
  <span m="1707390">the</span> <span m="1707460">question</span> <span m="1707790">is,</span>
  <span m="1708100">can</span> <span m="1708280">I</span> <span m="1708330">cancel</span>
  <span m="1708590">more?</span> <span m="1710010">Can</span> <span m="1710250">I</span>
  <span m="1710320">make</span> <span m="1710610">sure</span> <span m="1711070">I</span>
  <span m="1711150">can</span> <span m="1711644">cancel</span> <span m="1712138">more?</span>
  <span m="1713620">No.</span> <span m="1714040">I</span> <span m="1714420">only</span>
  <span m="1714720">have</span> <span m="1714970">three</span> <span m="1715280">terms</span>
  <span m="1715340">to</span> <span m="1715650">play</span> <span m="1715960">around</span>
  <span m="1716320">with.</span> <span m="1718372">I</span> <span m="1718760">only</span>
  <span m="1719170">have</span> <span m="1719520">three</span> <span m="1720210">unknowns,</span>
  <span m="1720760">x,</span> <span m="1720970">y,</span> <span m="1721180">and</span>
  <span m="1721330">z.</span></p><p><span m="1723320">So</span> <span m="1723530">I</span>
  <span m="1723650">can</span> <span m="1723900">only</span> <span m="1724970">satisfy</span>
  <span m="1725560">three</span> <span m="1726070">equations.</span> <span m="1726550">On</span>
  <span m="1726780">[INAUDIBLE]</span> <span m="1728670">that</span> <span m="1728920">of</span>
  <span m="1729026">the</span> <span m="1729133">three</span> <span m="1729240">equations.</span>
  <span m="1730060">There</span> <span m="1730250">is</span> <span m="1730720">[INAUDIBLE]</span>
  <span m="1731080">that</span> <span m="1731510">satisfy</span> <span m="1731940">automatically.</span>
  <span m="1733660">So</span> <span m="1733920">unless</span> <span m="1734360">I''m</span>
  <span m="1734700">super</span> <span m="1735010">lucky,</span> <span m="1735450">I</span>
  <span m="1735610">can</span> <span m="1735800">only</span> <span m="1736050">tune</span>
  <span m="1736510">the</span> <span m="1736700">three</span> <span m="1737430">unknowns</span>
  <span m="1737650">to</span> <span m="1738080">satisfy</span> <span m="1738970">three</span>
  <span m="1739590">linear</span> <span m="1739980">equations.</span> <span m="1742980">All</span>
  <span m="1743480">right.</span></p><p><span m="1746130">So</span> <span m="1746340">in</span>
  <span m="1746470">this</span> <span m="1746660">case,</span> <span m="1747360">it</span>
  <span m="1747580">is</span> <span m="1747900">pretty</span> <span m="1748180">clear</span>
  <span m="1748610">that</span> <span m="1749170">z</span> <span m="1749780">has</span>
  <span m="1750120">to</span> <span m="1750230">equal</span> <span m="1750620">to</span>
  <span m="1751840">1/2</span> <span m="1752120">of</span> <span m="1752410">t</span>
  <span m="1753180">and</span> <span m="1753530">y</span> <span m="1753850">because</span>
  <span m="1754210">of</span> <span m="1754320">the</span> <span m="1754390">second</span>
  <span m="1754730">equation</span> <span m="1755180">also</span> <span m="1755610">has</span>
  <span m="1755870">to</span> <span m="1756035">be</span> <span m="1756201">equal</span>
  <span m="1756367">to</span> <span m="1756615">1/2</span> <span m="1756864">of</span>
  <span m="1757361">t.</span> <span m="1759350">Or</span> <span m="1759720">I</span>
  <span m="1759920">can</span> <span m="1760240">just</span> <span m="1760630">take</span>
  <span m="1760880">these</span> <span m="1761100">three</span> <span m="1761430">equations</span>
  <span m="1761910">and</span> <span m="1762130">make</span> <span m="1762360">it</span>
  <span m="1762470">a</span> <span m="1762520">matrix.</span> <span m="1765920">I</span>
  <span m="1766050">can</span> <span m="1766260">take</span> <span m="1766530">these</span>
  <span m="1766780">three</span> <span m="1767080">equations</span> <span m="1768350">and</span>
  <span m="1768660">particularly,</span> <span m="1770440">I</span> <span m="1770920">can</span>
  <span m="1771170">make,</span> <span m="1773820">if</span> <span m="1774070">I</span>
  <span m="1774200">can--</span> <span m="1776450">well,</span> <span m="1777230">let</span>
  <span m="1777360">me</span> <span m="1777470">see.</span> <span m="1779050">If</span>
  <span m="1779260">I</span> <span m="1779360">can</span> <span m="1779660">divide</span>
  <span m="1781430">the</span> <span m="1781600">second</span> <span m="1782190">and</span>
  <span m="1782360">third</span> <span m="1782680">equations</span> <span m="1783150">by</span>
  <span m="1783720">delta</span> <span m="1783800">t</span> <span m="1786290">so</span>
  <span m="1786500">that</span> <span m="1787070">the</span> <span m="1787310">unknowns</span>
  <span m="1787760">are</span> <span m="1787930">x</span> <span m="1788860">and</span>
  <span m="1789090">y</span> <span m="1789300">over</span> <span m="1789470">delta</span>
  <span m="1789750">t</span> <span m="1790360">and</span> <span m="1790650">z</span>
  <span m="1790810">over</span> <span m="1791010">delta</span> <span m="1791120">t.</span>
  <span m="1791990">If</span> <span m="1792160">I</span> <span m="1792260">make</span>
  <span m="1792560">them</span> <span m="1792850">as</span> <span m="1793020">the</span>
  <span m="1793140">unknowns,</span> <span m="1794560">then</span> <span m="1795640">I</span>
  <span m="1795810">can</span> <span m="1796400">write</span> <span m="1796770">the</span>
  <span m="1796900">equation</span> <span m="1797270">as</span> <span m="1802310">x,</span>
  <span m="1802737">y,</span> <span m="1803164">z</span> <span m="1804920">equal</span>
  <span m="1805370">to</span> <span m="1806140">1,</span> <span m="1806606">1,</span>
  <span m="1808200">and</span> <span m="1808510">1/2.</span></p><p><span m="1809470">How</span>
  <span m="1809620">can</span> <span m="1809770">I</span> <span m="1809830">do</span>
  <span m="1810000">that?</span> <span m="1810600">How</span> <span m="1810740">can</span>
  <span m="1810920">I</span> <span m="1811070">fill</span> <span m="1811300">in</span>
  <span m="1811530">this</span> <span m="1811730">matrix?</span></p><p><span m="1812172">AUDIENCE:</span>
  <span m="1812614">[INAUDIBLE].</span></p><p><span m="1813056">QIQI WANG:</span>
  <span m="1813500">Well,</span> <span m="1813770">the</span> <span m="1813900">first</span>
  <span m="1814180">line</span> <span m="1814420">is</span> <span m="1814640">1,</span>
  <span m="1814756">0,</span> <span m="1814873">0.</span> <span m="1814990">Thank</span>
  <span m="1816020">you.</span> <span m="1816840">It''s</span> <span m="1817045">just</span>
  <span m="1817250">the</span> <span m="1817340">first</span> <span m="1817610">equation</span>
  <span m="1818000">x</span> <span m="1818300">equal</span> <span m="1818730">to</span>
  <span m="1818945">1.</span> <span m="1819160">What</span> <span m="1819325">about</span>
  <span m="1819490">the</span> <span m="1819580">second</span> <span m="1819920">line?</span>
  <span m="1820270">I</span> <span m="1820350">mean,</span> <span m="1820580">this</span>
  <span m="1820830">is</span> <span m="1821080">not</span> <span m="1821320">y,</span>
  <span m="1821732">z,</span> <span m="1821938">but</span> <span m="1822144">y</span>
  <span m="1822556">over</span> <span m="1822970">delta</span> <span m="1823110">t</span>
  <span m="1823250">and</span> <span m="1823540">z</span> <span m="1823788">over</span>
  <span m="1824036">delta</span> <span m="1824532">t.</span> <span m="1825028">What</span>
  <span m="1825524">is</span> <span m="1825648">the</span> <span m="1825772">second</span>
  <span m="1825896">line?</span></p><p><span m="1827012">AUDIENCE:</span> <span m="1827508">[INAUDIBLE].</span></p><p><span
  m="1828996">QIQI WANG:</span> <span m="1829500">0,</span> <span m="1829800">1,</span>
  <span m="1830440">1.</span> <span m="1830770">Exactly.</span> <span m="1831830">And</span>
  <span m="1832040">what</span> <span m="1832220">is</span> <span m="1832350">the</span>
  <span m="1832835">third</span> <span m="1833320">line?</span> <span m="1835260">0,</span>
  <span m="1835590">0,</span> <span m="1836050">1.</span> <span m="1836750">I</span>
  <span m="1837050">mean,</span> <span m="1837340">this</span> <span m="1837680">looks</span>
  <span m="1839020">obvious,</span> <span m="1839350">but</span> <span m="1840010">as</span>
  <span m="1840320">you</span> <span m="1840470">get</span> <span m="1840810">to</span>
  <span m="1841520">more</span> <span m="1842030">complex</span> <span m="1842500">schemes,</span>
  <span m="1842980">as</span> <span m="1844900">what''s</span> <span m="1845270">your</span>
  <span m="1845360">name</span> <span m="1845500">again?</span></p><p><span m="1846270">AUDIENCE:</span>
  <span m="1846733">Jacobi.</span></p><p><span m="1847196">QIQI WANG:</span> <span
  m="1847660">Jacobi.</span> <span m="1848010">Jacobi</span> <span m="1848680">has</span>
  <span m="1848850">discovered</span> <span m="1849140">in</span> <span m="1849430">his</span>
  <span m="1849902">[? one ?]</span> <span m="1850374">contact</span> <span m="1850846">schemes,</span>
  <span m="1852490">you</span> <span m="1852710">cannot</span> <span m="1853420">just</span>
  <span m="1853670">by</span> <span m="1853820">looking</span> <span m="1854150">at</span>
  <span m="1854230">equations</span> <span m="1854850">and</span> <span m="1855060">get</span>
  <span m="1855420">all</span> <span m="1855600">the</span> <span m="1855780">coefficients.</span>
  <span m="1856310">You</span> <span m="1856380">have</span> <span m="1856600">to</span>
  <span m="1856710">solve</span> <span m="1857010">a</span> <span m="1857110">matrix</span>
  <span m="1857450">equation</span> <span m="1857840">like</span> <span m="1858050">that.</span>
  <span m="1858920">And</span> <span m="1859250">in</span> <span m="1859430">MATLAB,</span>
  <span m="1860010">let</span> <span m="1860140">me</span> <span m="1860360">set</span>
  <span m="1860550">up</span> <span m="1860740">this</span> <span m="1861120">matrix.</span>
  <span m="1861880">This</span> <span m="1862260">matrix</span> <span m="1862850">is</span>
  <span m="1865200">1,</span> <span m="1865495">0,</span> <span m="1865790">0,</span>
  <span m="1867490">the</span> <span m="1867640">first</span> <span m="1867920">line.</span>
  <span m="1868390">The</span> <span m="1868560">second</span> <span m="1868770">line</span>
  <span m="1868895">is</span> <span m="1869020">0,</span> <span m="1869400">1,</span>
  <span m="1869720">1.</span> <span m="1870657">The</span> <span m="1871134">third</span>
  <span m="1871611">line</span> <span m="1872090">0,</span> <span m="1872390">0,</span>
  <span m="1872740">1.</span> <span m="1874020">This</span> <span m="1874200">is</span>
  <span m="1874310">the</span> <span m="1874390">matrix.</span> <span m="1875460">Exactly.</span>
  <span m="1875660">The</span> <span m="1876100">matrix.</span></p><p><span m="1877320">And</span>
  <span m="1877470">the</span> <span m="1877550">right</span> <span m="1877750">answer</span>
  <span m="1878360">is</span> <span m="1879660">1,</span> <span m="1880260">1,</span>
  <span m="1881011">and</span> <span m="1881502">1/2.</span> <span m="1882484">Yeah,</span>
  <span m="1882975">that''s</span> <span m="1883138">the</span> <span m="1883302">right-hand</span>
  <span m="1883466">side.</span> <span m="1884448">And</span> <span m="1884939">by</span>
  <span m="1885430">a</span> <span m="1886200">backslash</span> <span m="1886970">c,</span>
  <span m="1887902">does</span> <span m="1888370">everybody</span> <span m="1888780">know</span>
  <span m="1889100">what</span> <span m="1889310">the</span> <span m="1889770">backslash</span>
  <span m="1889990">means?</span> <span m="1893590">Yes.</span> <span m="1894010">It''s</span>
  <span m="1894195">matrix</span> <span m="1894380">division.</span> <span m="1894860">It</span>
  <span m="1895320">is</span> <span m="1895430">solving</span> <span m="1896820">this</span>
  <span m="1897180">equation.</span> <span m="1897600">It</span> <span m="1897750">is</span>
  <span m="1897870">solving</span> <span m="1898470">ax</span> <span m="1899290">equal</span>
  <span m="1899480">to</span> <span m="1899670">b.</span> <span m="1900000">It</span>
  <span m="1900340">solves</span> <span m="1900720">for</span> <span m="1901083">x,</span>
  <span m="1901810">and</span> <span m="1901890">I</span> <span m="1901980">push.</span>
  <span m="1903460">It</span> <span m="1903690">give</span> <span m="1904000">me</span>
  <span m="1904250">the</span> <span m="1904330">coefficients,</span> <span m="1904920">1,</span>
  <span m="1905510">1/2,</span> <span m="1905930">1/2,</span> <span m="1906850">which</span>
  <span m="1907100">means</span> <span m="1908230">x</span> <span m="1908550">equal</span>
  <span m="1908880">1,</span> <span m="1910360">y</span> <span m="1910690">over</span>
  <span m="1910950">delta</span> <span m="1911180">t</span> <span m="1911270">equal</span>
  <span m="1911600">to</span> <span m="1911690">1/2,</span> <span m="1912030">which</span>
  <span m="1912230">means</span> <span m="1912500">y</span> <span m="1912900">equal</span>
  <span m="1913330">to</span> <span m="1913473">1/2</span> <span m="1913616">delta</span>
  <span m="1913760">t,</span> <span m="1914190">and</span> <span m="1914570">z</span>
  <span m="1914870">also</span> <span m="1915180">equal</span> <span m="1915285">to</span>
  <span m="1915390">1/2</span> <span m="1915868">delta</span> <span m="1916346">t.</span></p><p><span
  m="1917302">All</span> <span m="1917780">right.</span> <span m="1918410">So</span>
  <span m="1918740">some</span> <span m="1919010">of</span> <span m="1919270">the</span>
  <span m="1919530">scheme</span> <span m="1920340">we</span> <span m="1920580">have</span>
  <span m="1920900">is</span> <span m="1923170">ui</span> <span m="1923770">plus</span>
  <span m="1924170">1</span> <span m="1925040">equal</span> <span m="1925560">to</span>
  <span m="1925780">ui</span> <span m="1927040">plus</span> <span m="1927970">1/2</span>
  <span m="1928110">delta</span> <span m="1928180">t</span> <span m="1928235">ui</span>
  <span m="1928290">prime</span> <span m="1928753">plus</span> <span m="1930380">1/2</span>
  <span m="1930730">delta</span> <span m="1930900">t</span> <span m="1931540">ui</span>
  <span m="1932450">plus</span> <span m="1932810">1</span> <span m="1933030">prime.</span></p><p><span
  m="1936240">All</span> <span m="1936705">right.</span> <span m="1937635">So</span>
  <span m="1938100">good.</span> <span m="1938330">I</span> <span m="1938460">think</span>
  <span m="1938730">we</span> <span m="1938970">resolved</span> <span m="1939430">the</span>
  <span m="1939560">conflict.</span> <span m="1942920">There</span> <span m="1943210">is</span>
  <span m="1943530">only</span> <span m="1943920">one</span> <span m="1944280">scheme</span>
  <span m="1944730">that</span> <span m="1944950">satisfy</span> <span m="1946470">this</span>
  <span m="1946750">matrix</span> <span m="1947170">equation.</span> <span m="1948940">And</span>
  <span m="1949230">there</span> <span m="1949380">is</span> <span m="1949590">only</span>
  <span m="1949870">one</span> <span m="1950200">scheme</span> <span m="1950920">that</span>
  <span m="1951250">can</span> <span m="1951450">make</span> <span m="1951690">sure</span>
  <span m="1952060">the</span> <span m="1952140">first</span> <span m="1952390">term</span>
  <span m="1952820">cancels,</span> <span m="1952950">the</span> <span m="1953010">second</span>
  <span m="1953320">term</span> <span m="1953720">cancels,</span> <span m="1954090">the</span>
  <span m="1954560">third</span> <span m="1955030">term</span> <span m="1955290">cancels.</span>
  <span m="1956406">All</span> <span m="1956834">right.</span> <span m="1957690">And</span>
  <span m="1957940">remember</span> <span m="1958560">z</span> <span m="1959010">is</span>
  <span m="1959490">1/2</span> <span m="1960210">delta</span> <span m="1960360">t.</span>
  <span m="1960460">So</span> <span m="1960800">what</span> <span m="1961030">is</span>
  <span m="1961370">the</span> <span m="1962050">truncation</span> <span m="1962380">error</span>
  <span m="1962700">here?</span> <span m="1965480">What</span> <span m="1965670">is</span>
  <span m="1965820">the</span> <span m="1965900">truncation</span> <span m="1966150">error?</span>
  <span m="1966400">What</span> <span m="1966770">is</span> <span m="1966920">the</span>
  <span m="1967170">other</span> <span m="1967630">of</span> <span m="1967890">the</span>
  <span m="1967960">truncation</span> <span m="1968520">error</span> <span m="1969020">of</span>
  <span m="1969250">the</span> <span m="1969700">scheme?</span> <span m="1970150">What</span>
  <span m="1971470">local</span> <span m="1971760">[? order of accuracy ?]</span>
  <span m="1973200">does</span> <span m="1973370">the</span> <span m="1973605">scheme</span>
  <span m="1973840">have?</span></p><p><span m="1974310">AUDIENCE:</span> <span m="1974780">[INAUDIBLE].</span></p><p><span
  m="1976190">QIQI WANG:</span> <span m="1976660">Second</span> <span m="1976860">order</span>
  <span m="1977570">delta</span> <span m="1977780">t</span> <span m="1977990">square.</span>
  <span m="1978360">Because</span> <span m="1978990">this</span> <span m="1984680">is</span>
  <span m="1985140">square,</span> <span m="1985620">so</span> <span m="1985950">sorry.</span>
  <span m="1986210">This</span> <span m="1986360">is</span> <span m="1986520">square,</span>
  <span m="1986730">but</span> <span m="1987460">z</span> <span m="1987820">is</span>
  <span m="1988130">equal</span> <span m="1988300">to</span> <span m="1988390">1/2</span>
  <span m="1988640">of</span> <span m="1988750">delta</span> <span m="1989230">t,</span>
  <span m="1989710">so</span> <span m="1989890">this</span> <span m="1989955">term</span>
  <span m="1990020">is</span> <span m="1990200">delta</span> <span m="1990655">t</span>
  <span m="1990882">too.</span> <span m="1991110">So</span> <span m="1991340">the</span>
  <span m="1991420">truncation</span> <span m="1991880">of</span> <span m="1991980">the</span>
  <span m="1992060">leading</span> <span m="1992480">term</span> <span m="1992890">of</span>
  <span m="1993530">the</span> <span m="1993630">delta</span> <span m="1993860">t</span>
  <span m="1994070">times</span> <span m="1994380">tau</span> <span m="1994720">is</span>
  <span m="1995030">delta</span> <span m="1995230">t</span> <span m="1995675">too,</span>
  <span m="1996120">which</span> <span m="1996340">means</span> <span m="1996670">tau</span>
  <span m="1997530">is</span> <span m="1997850">delta</span> <span m="1997930">t</span>
  <span m="1998080">square.</span></p><p><span m="1999240">All</span> <span m="1999710">right.</span>
  <span m="2001590">And</span> <span m="2001790">why</span> <span m="2002210">did</span>
  <span m="2002380">I</span> <span m="2002520">say</span> <span m="2002810">this</span>
  <span m="2003210">is</span> <span m="2003980">delta</span> <span m="2004490">t</span>
  <span m="2004580">tau?</span> <span m="2005520">This</span> <span m="2005850">is</span>
  <span m="2005960">because</span> <span m="2007930">if</span> <span m="2011170">you</span>
  <span m="2011260">look</span> <span m="2011540">at</span> <span m="2011640">how</span>
  <span m="2012060">accurate</span> <span m="2012850">I</span> <span m="2013020">am</span>
  <span m="2013340">approximating</span> <span m="2014280">the</span> <span m="2014430">derivative,</span>
  <span m="2015590">I</span> <span m="2015640">mean,</span> <span m="2016470">I''m</span>
  <span m="2016660">approximating</span> <span m="2016995">the</span> <span m="2017880">average</span>
  <span m="2018610">of</span> <span m="2018720">the</span> <span m="2018810">derivative</span>
  <span m="2019460">between</span> <span m="2019820">i</span> <span m="2020120">and</span>
  <span m="2020420">i</span> <span m="2020720">plus</span> <span m="2020950">1</span>
  <span m="2021390">set.</span> <span m="2022220">I''m</span> <span m="2022440">basically</span>
  <span m="2022970">approximating</span> <span m="2023860">the</span> <span m="2024000">average</span>
  <span m="2024660">of</span> <span m="2024950">the</span> <span m="2025330">i-th</span>
  <span m="2025710">derivative</span> <span m="2026500">and</span> <span m="2026650">i-th</span>
  <span m="2026780">plus</span> <span m="2026900">1</span> <span m="2027160">derivative.</span>
  <span m="2027840">It</span> <span m="2028630">is</span> <span m="2029170">equal</span>
  <span m="2029600">to</span> <span m="2030550">what?</span> <span m="2031560">ui</span>
  <span m="2032080">plus</span> <span m="2032420">1</span> <span m="2032770">minus</span>
  <span m="2033050">ui</span> <span m="2033340">divided</span> <span m="2033550">by</span>
  <span m="2033986">delta</span> <span m="2034422">t.</span></p><p><span m="2037540">And</span>
  <span m="2038480">if</span> <span m="2038780">you</span> <span m="2038970">look</span>
  <span m="2039290">at</span> <span m="2039510">the</span> <span m="2039580">truncation</span>
  <span m="2040180">error</span> <span m="2040650">of</span> <span m="2041120">this</span>
  <span m="2041480">scheme,</span> <span m="2043210">so</span> <span m="2043590">if</span>
  <span m="2043770">I</span> <span m="2043910">do</span> <span m="2044170">this</span>
  <span m="2044440">rigorously,</span> <span m="2044780">this</span> <span m="2045120">is</span>
  <span m="2045588">delta</span> <span m="2045822">t</span> <span m="2046056">cube</span>
  <span m="2046524">here.</span> <span m="2047460">And</span> <span m="2047990">if</span>
  <span m="2048540">you</span> <span m="2048699">transform,</span> <span m="2050600">go</span>
  <span m="2051060">from</span> <span m="2051340">this</span> <span m="2051520">equation</span>
  <span m="2051870">to</span> <span m="2052040">this</span> <span m="2052175">equation,</span>
  <span m="2052429">you</span> <span m="2052670">have</span> <span m="2052870">to</span>
  <span m="2053050">divide</span> <span m="2053310">everything</span> <span m="2053650">out</span>
  <span m="2053740">by</span> <span m="2053830">delta</span> <span m="2054232">t.</span>
  <span m="2054634">So</span> <span m="2055440">you</span> <span m="2055719">get</span>
  <span m="2055760">delta</span> <span m="2056020">t</span> <span m="2056250">squared.</span>
  <span m="2056929">So</span> <span m="2057060">the</span> <span m="2057159">truncation</span>
  <span m="2057650">error</span> <span m="2057810">of</span> <span m="2057969">this</span>
  <span m="2058090">scheme</span> <span m="2058679">is</span> <span m="2059050">delta</span>
  <span m="2059489">t</span> <span m="2059690">squared.</span></p><p><span m="2061965">All</span>
  <span m="2062420">right.</span> <span m="2062550">I''m</span> <span m="2062810">basically</span>
  <span m="2063290">taking</span> <span m="2063770">these</span> <span m="2064250">two</span>
  <span m="2064730">terms,</span> <span m="2065690">dividing</span> <span m="2066170">by</span>
  <span m="2066650">delta</span> <span m="2067130">t,</span> <span m="2067610">and</span>
  <span m="2068090">getting</span> <span m="2068335">this.</span> <span m="2068580">Well,</span>
  <span m="2068960">I''m</span> <span m="2069433">moving</span> <span m="2069906">this</span>
  <span m="2070379">term</span> <span m="2070852">to</span> <span m="2071325">here</span>
  <span m="2071798">and</span> <span m="2071955">divide</span> <span m="2072113">by</span>
  <span m="2072271">delta</span> <span m="2072507">t</span> <span m="2072744">to</span>
  <span m="2072980">get</span> <span m="2073217">this.</span> <span m="2075110">And</span>
  <span m="2075420">what</span> <span m="2075908">is</span> <span m="2076152">that</span>
  <span m="2076396">here?</span> <span m="2076884">Because</span> <span m="2077372">I''m</span>
  <span m="2077860">dividing</span> <span m="2078022">by</span> <span m="2078185">delta</span>
  <span m="2078348">t,</span> <span m="2078840">I</span> <span m="2078918">get</span>
  <span m="2078996">delta</span> <span m="2079074">t</span> <span m="2079152">squared.</span>
  <span m="2079230">So</span> <span m="2079420">the</span> <span m="2079520">scheme</span>
  <span m="2079860">is</span> <span m="2081780">second</span> <span m="2082060">order</span>
  <span m="2082310">accurate.</span> <span m="2091820">Any</span> <span m="2091980">questions?</span>
  <span m="2094850">No?</span> <span m="2095790">Here?</span></p><p><span m="2099530">Let''s</span>
  <span m="2101370">try</span> <span m="2101660">to</span> <span m="2102800">implement</span>
  <span m="2104320">the</span> <span m="2104550">scheme</span> <span m="2106800">into</span>
  <span m="2107210">one</span> <span m="2107540">of</span> <span m="2107670">the</span>
  <span m="2108560">very</span> <span m="2108890">simple</span> <span m="2109220">problems.</span>
  <span m="2112070">Let''s</span> <span m="2112410">do</span> <span m="2112590">a</span>
  <span m="2112650">pendulum</span> <span m="2113740">problem.</span> <span m="2115490">In</span>
  <span m="2115680">a</span> <span m="2116005">pendulum</span> <span m="2116330">problem,</span>
  <span m="2117270">we</span> <span m="2117530">have</span> <span m="2117730">a</span>
  <span m="2117800">pendulum</span> <span m="2119210">that</span> <span m="2119410">is</span>
  <span m="2119660">vibrating</span> <span m="2120600">on</span> <span m="2121070">a</span>
  <span m="2121540">small</span> <span m="2122010">angle.</span> <span m="2122480">So</span>
  <span m="2122950">today</span> <span m="2123290">we</span> <span m="2123520">restrict</span>
  <span m="2123970">ourselves</span> <span m="2124530">to</span> <span m="2124710">small</span>
  <span m="2125010">angles</span> <span m="2127190">so</span> <span m="2127360">that</span>
  <span m="2127530">the</span> <span m="2127740">equation</span> <span m="2128050">is</span>
  <span m="2128120">not</span> <span m="2128240">going</span> <span m="2128360">to</span>
  <span m="2128490">be</span> <span m="2128690">linear.</span> <span m="2129350">And</span>
  <span m="2129950">we''re</span> <span m="2130250">going</span> <span m="2130390">to</span>
  <span m="2130460">be</span> <span m="2130560">going</span> <span m="2130920">to</span>
  <span m="2131020">[? nulling ?]</span> <span m="2131350">equations,</span> <span
  m="2131490">and</span> <span m="2131780">we''re</span> <span m="2132250">going</span>
  <span m="2132720">to</span> <span m="2133190">see</span> <span m="2133425">why</span>
  <span m="2133660">[? nulling ?]</span> <span m="2134130">equations</span> <span
  m="2135070">is</span> <span m="2135450">going</span> <span m="2135640">to</span>
  <span m="2135720">be</span> <span m="2136420">more</span> <span m="2136660">complex</span>
  <span m="2138800">especially</span> <span m="2139170">for</span> <span m="2139350">implicit</span>
  <span m="2139860">schemes.</span></p><p><span m="2140570">So</span> <span m="2140680">if</span>
  <span m="2141170">it''s</span> <span m="2141820">explicit</span> <span m="2142030">scheme,</span>
  <span m="2143490">actually,</span> <span m="2144220">I''m</span> <span m="2144460">going</span>
  <span m="2144590">to</span> <span m="2144670">show</span> <span m="2144900">you</span>
  <span m="2145420">later</span> <span m="2145710">that</span> <span m="2146185">it''s</span>
  <span m="2146480">very</span> <span m="2146850">easy</span> <span m="2147140">to</span>
  <span m="2147580">do</span> <span m="2148020">a</span> <span m="2148460">non-linear</span>
  <span m="2148900">scheme,</span> <span m="2149240">but</span> <span m="2149690">for</span>
  <span m="2149940">implicit</span> <span m="2150715">method,</span> <span m="2152190">like</span>
  <span m="2152840">the</span> <span m="2153000">one</span> <span m="2153230">we</span>
  <span m="2153420">just</span> <span m="2153600">derived,</span> <span m="2155060">one</span>
  <span m="2155420">that</span> <span m="2155710">actually</span> <span m="2156470">involves</span>
  <span m="2158190">a</span> <span m="2159680">u</span> <span m="2159920">prime</span>
  <span m="2160300">of</span> <span m="2160450">i</span> <span m="2160570">plus</span>
  <span m="2160890">1,</span> <span m="2161150">it</span> <span m="2161410">is</span>
  <span m="2161850">going</span> <span m="2162020">to</span> <span m="2162100">be</span>
  <span m="2162240">much</span> <span m="2162530">more</span> <span m="2162740">difficult</span>
  <span m="2163210">to</span> <span m="2163366">do</span> <span m="2163523">a</span>
  <span m="2163680">non-linear</span> <span m="2164150">scheme.</span> <span m="2165560">But</span>
  <span m="2165730">here</span> <span m="2166430">the</span> <span m="2166550">variable</span>
  <span m="2167160">is</span> <span m="2167530">theta.</span> <span m="2169550">And</span>
  <span m="2169910">what</span> <span m="2170130">determines</span> <span m="2171490">the</span>
  <span m="2173610">acceleration</span> <span m="2174560">of</span> <span m="2174930">theta?</span>
  <span m="2175590">What</span> <span m="2175780">is</span> <span m="2176010">the</span>
  <span m="2176110">second</span> <span m="2176560">derivative</span> <span m="2177070">of</span>
  <span m="2177190">theta?</span> <span m="2177526">What''s</span> <span m="2177862">that</span>
  <span m="2178200">going</span> <span m="2178520">to</span> <span m="2178766">be</span>
  <span m="2179012">determining?</span></p><p><span m="2182456">AUDIENCE:</span> <span
  m="2182948">[INAUDIBLE].</span></p><p><span m="2193772">QIQI WANG:</span> <span
  m="2194270">Force</span> <span m="2194570">balance,</span> <span m="2195070">right.</span>
  <span m="2195380">What</span> <span m="2195580">is</span> <span m="2195760">the</span>
  <span m="2195870">acceleration</span> <span m="2196710">of</span> <span m="2196850">this</span>
  <span m="2196990">ball?</span> <span m="2198500">Let</span> <span m="2198700">me</span>
  <span m="2199120">just</span> <span m="2199250">ask,</span> <span m="2199660">what</span>
  <span m="2199860">is</span> <span m="2200020">the</span> <span m="2200200">gradual</span>
  <span m="2200570">acceleration</span> <span m="2201067">of</span> <span m="2201315">this</span>
  <span m="2201564">ball?</span></p><p><span m="2202061">AUDIENCE:</span> <span m="2202558">[INAUDIBLE].</span></p><p><span
  m="2207528">QIQI WANG:</span> <span m="2208025">[INAUDIBLE].</span> <span m="2211520">This</span>
  <span m="2211830">is</span> <span m="2211970">[INAUDIBLE],</span> <span m="2212400">so</span>
  <span m="2212830">the</span> <span m="2213010">only</span> <span m="2213285">way</span>
  <span m="2213560">to</span> <span m="2213880">accelerate</span> <span m="2214350">is</span>
  <span m="2214828">along</span> <span m="2215306">the</span> <span m="2215784">[?
  duct. ?]</span> <span m="2217140">So</span> <span m="2217615">it</span> <span m="2218090">is</span>
  <span m="2218590">[INAUDIBLE].</span> <span m="2222450">is</span> <span m="2222610">acceleration?</span></p><p><span
  m="2230594">AUDIENCE:</span> <span m="2231093">[INAUDIBLE].</span></p><p><span m="2235085">QIQI
  WANG:</span> <span m="2235600">It</span> <span m="2235830">can</span> <span m="2236210">be</span>
  <span m="2236510">moving.</span> <span m="2236580">Let''s</span> <span m="2237010">assume</span>
  <span m="2237440">there</span> <span m="2237730">is</span> <span m="2237880">no</span>
  <span m="2238030">friction.</span> <span m="2238513">The</span> <span m="2238996">only</span>
  <span m="2239480">force</span> <span m="2239820">it</span> <span m="2240273">has</span>
  <span m="2240726">is</span> <span m="2243630">the</span> <span m="2244130">gravity</span>
  <span m="2244490">force</span> <span m="2245090">and</span> <span m="2245470">the</span>
  <span m="2246610">tension</span> <span m="2248300">of</span> <span m="2249005">its</span>
  <span m="2249380">spring,</span> <span m="2251180">which</span> <span m="2251570">is</span>
  <span m="2251870">[? non-elastic. ?]</span></p><p><span m="2261710">AUDIENCE:</span>
  <span m="2262202">g</span> <span m="2262694">sine</span> <span m="2263186">theta.</span></p><p><span
  m="2263678">QIQI WANG:</span> <span m="2264180">g</span> <span m="2264550">sine</span>
  <span m="2264980">theta.</span> <span m="2265450">Why</span> <span m="2265870">is</span>
  <span m="2265980">that</span> <span m="2266160">g</span> <span m="2266290">sine</span>
  <span m="2266610">theta?</span></p><p><span m="2268540">AUDIENCE:</span> <span m="2269020">[INAUDIBLE].</span></p><p><span
  m="2277180">QIQI WANG:</span> <span m="2277660">Yeah.</span> <span m="2278940">a</span>
  <span m="2279330">is</span> <span m="2279620">equal</span> <span m="2279950">to</span>
  <span m="2280200">F</span> <span m="2280560">over</span> <span m="2281020">m.</span>
  <span m="2284300">It''s</span> <span m="2284640">force</span> <span m="2285010">over</span>
  <span m="2285420">mass,</span> <span m="2286040">and</span> <span m="2286300">what</span>
  <span m="2286470">is</span> <span m="2286660">the</span> <span m="2286930">force?</span>
  <span m="2289320">The</span> <span m="2289460">force</span> <span m="2289870">is</span>
  <span m="2290450">actually</span> <span m="2290730">here.</span> <span m="2291010">This</span>
  <span m="2291405">is</span> <span m="2291800">the</span> <span m="2292010">force</span>
  <span m="2294200">in</span> <span m="2294370">interaction.</span> <span m="2295190">So</span>
  <span m="2295710">it</span> <span m="2295880">is</span> <span m="2296160">mg</span>
  <span m="2297580">sine</span> <span m="2297950">theta</span> <span m="2298120">over</span>
  <span m="2300020">m,</span> <span m="2300610">which</span> <span m="2300860">is</span>
  <span m="2301060">exactly</span> <span m="2301670">g</span> <span m="2301840">sine</span>
  <span m="2302310">theta.</span> <span m="2302740">So</span> <span m="2302930">you</span>
  <span m="2303040">are</span> <span m="2303130">right.</span> <span m="2305626">Sorry.</span>
  <span m="2306089">What''s</span> <span m="2306552">your</span> <span m="2306783">name</span>
  <span m="2307015">again?</span></p><p><span m="2307478">AUDIENCE:</span> <span m="2307941">Libby.</span></p><p><span
  m="2308867">QIQI WANG:</span> <span m="2309330">Libby.</span> <span m="2309565">OK.</span>
  <span m="2309800">Libby</span> <span m="2309990">is</span> <span m="2310180">right.</span>
  <span m="2312060">So</span> <span m="2312190">this</span> <span m="2312380">is</span>
  <span m="2312580">acceleration.</span> <span m="2313640">And</span> <span m="2314000">what</span>
  <span m="2314170">is</span> <span m="2314270">the</span> <span m="2317300">acceleration</span>
  <span m="2317940">in</span> <span m="2318110">theta?</span> <span m="2318330">What</span>
  <span m="2318415">is</span> <span m="2318500">the</span> <span m="2318870">second</span>
  <span m="2319240">derivative</span> <span m="2319710">of</span> <span m="2319830">theta?</span>
  <span m="2322280">Just</span> <span m="2322490">a</span> <span m="2322560">geometric</span>
  <span m="2323220">relation</span> <span m="2323670">between</span> <span m="2323930">this</span>
  <span m="2324190">and</span> <span m="2324690">deceleration.</span></p><p><span
  m="2333126">AUDIENCE:</span> <span m="2333618">[INAUDIBLE].</span></p><p><span m="2336078">QIQI
  WANG:</span> <span m="2336570">Divide</span> <span m="2337560">by</span> <span m="2337760">L.</span>
  <span m="2337990">Exactly.</span> <span m="2338640">So</span> <span m="2338840">this</span>
  <span m="2339080">is</span> <span m="2339360">a</span> <span m="2339700">over</span>
  <span m="2340110">L.</span> <span m="2341920">So</span> <span m="2342220">it</span>
  <span m="2342350">is</span> <span m="2342570">going</span> <span m="2342730">to</span>
  <span m="2342800">be</span> <span m="2343170">g</span> <span m="2344590">sine</span>
  <span m="2344980">theta</span> <span m="2345866">over</span> <span m="2346342">L.</span>
  <span m="2347294">All</span> <span m="2347770">right.</span> <span m="2350630">And</span>
  <span m="2351650">we</span> <span m="2351820">are</span> <span m="2351930">going</span>
  <span m="2352100">to</span> <span m="2352190">be</span> <span m="2352720">linearizing</span>
  <span m="2353760">this</span> <span m="2353960">equation</span> <span m="2354500">because</span>
  <span m="2354820">sine</span> <span m="2355070">theta,</span> <span m="2355320">when</span>
  <span m="2355750">theta</span> <span m="2356030">is</span> <span m="2356160">very</span>
  <span m="2356440">small,</span> <span m="2357840">is</span> <span m="2358100">what?</span>
  <span m="2358530">Again,</span> <span m="2358930">Taylor</span> <span m="2359230">series</span>
  <span m="2359710">expansion</span> <span m="2360456">sine</span> <span m="2360830">theta</span>
  <span m="2361860">is</span> <span m="2362300">equal</span> <span m="2362730">to</span>
  <span m="2364210">sine</span> <span m="2364625">theta</span> <span m="2365040">at</span>
  <span m="2365280">0</span> <span m="2365540">plus</span> <span m="2366310">theta</span>
  <span m="2367620">times</span> <span m="2368680">the</span> <span m="2368820">derivative</span>
  <span m="2369400">of</span> <span m="2369540">sine</span> <span m="2369870">theta</span>
  <span m="2370030">at</span> <span m="2370380">0,</span> <span m="2370710">which</span>
  <span m="2370910">is</span> <span m="2371040">equal</span> <span m="2371260">to</span>
  <span m="2371360">1,</span> <span m="2373272">which</span> <span m="2373750">is</span>
  <span m="2373880">cosine</span> <span m="2374343">theta</span> <span m="2374806">at</span>
  <span m="2375269">0,</span> <span m="2375732">et</span> <span m="2376195">cetera.</span>
  <span m="2376970">So</span> <span m="2377140">this</span> <span m="2377410">term</span>
  <span m="2377620">is</span> <span m="2377750">0.</span> <span m="2378360">This</span>
  <span m="2379250">term</span> <span m="2379642">is</span> <span m="2380034">theta,</span>
  <span m="2380820">so</span> <span m="2381150">it</span> <span m="2381300">is</span>
  <span m="2381660">approximately</span> <span m="2382320">equal</span> <span m="2382793">to</span>
  <span m="2383266">theta.</span></p><p><span m="2387050">I</span> <span m="2387130">mean,</span>
  <span m="2387290">this</span> <span m="2387470">is</span> <span m="2389020">probably</span>
  <span m="2390130">sine</span> <span m="2390520">theta</span> <span m="2391190">can</span>
  <span m="2391340">be</span> <span m="2391440">approximated</span> <span m="2392310">by</span>
  <span m="2392520">theta</span> <span m="2392800">a</span> <span m="2392860">lot</span>
  <span m="2393030">of</span> <span m="2393130">times,</span> <span m="2393573">but</span>
  <span m="2394460">in</span> <span m="2394510">order</span> <span m="2394640">to</span>
  <span m="2395640">know</span> <span m="2395850">this</span> <span m="2396200">is,</span>
  <span m="2396550">again,</span> <span m="2397050">a</span> <span m="2397190">result</span>
  <span m="2397350">of</span> <span m="2397540">Taylor''s</span> <span m="2397660">rule</span>
  <span m="2397995">expansion.</span> <span m="2401800">So</span> <span m="2401990">sine</span>
  <span m="2402200">theta</span> <span m="2402720">can</span> <span m="2402860">be</span>
  <span m="2402900">an</span> <span m="2402940">approximate</span> <span m="2403385">of</span>
  <span m="2403830">theta,</span> <span m="2404610">and</span> <span m="2405000">now</span>
  <span m="2405420">I''m</span> <span m="2405590">going</span> <span m="2405720">to</span>
  <span m="2405860">write</span> <span m="2406170">the</span> <span m="2406320">question</span>
  <span m="2408060">theta</span> <span m="2408400">double</span> <span m="2408730">dot</span>
  <span m="2409150">is</span> <span m="2409220">equal</span> <span m="2409410">to</span>
  <span m="2409600">g</span> <span m="2409880">theta</span> <span m="2410110">over</span>
  <span m="2410420">L</span> <span m="2410700">in</span> <span m="2410880">a</span>
  <span m="2410960">pretty</span> <span m="2411360">strange</span> <span m="2411700">way.</span>
  <span m="2412720">I''m</span> <span m="2412940">going</span> <span m="2413070">to</span>
  <span m="2413190">write</span> <span m="2413460">it</span> <span m="2413570">as</span>
  <span m="2414280">theta</span> <span m="2414660">doubled</span> <span m="2415080">dot</span>
  <span m="2416790">equal</span> <span m="2417240">to--</span> <span m="2425700">no,</span>
  <span m="2425960">I''m</span> <span m="2426040">not</span> <span m="2426280">going</span>
  <span m="2426410">to</span> <span m="2426480">write</span> <span m="2426645">it</span>
  <span m="2426810">like</span> <span m="2427020">this.</span> <span m="2430620">I''m</span>
  <span m="2430840">going</span> <span m="2431030">to</span> <span m="2431130">be</span>
  <span m="2431270">writing</span> <span m="2431710">this</span> <span m="2431960">as</span>
  <span m="2432300">d</span> <span m="2432750">theta</span> <span m="2433750">dt</span>
  <span m="2435240">equal</span> <span m="2435610">to</span> <span m="2435865">theta</span>
  <span m="2436120">dot,</span> <span m="2437060">which</span> <span m="2437330">is</span>
  <span m="2438230">just</span> <span m="2438430">a</span> <span m="2438530">definition</span>
  <span m="2439080">of</span> <span m="2439650">theta</span> <span m="2439930">dot.</span>
  <span m="2440500">It''s</span> <span m="2440800">equivalent.</span></p><p><span
  m="2443310">d</span> <span m="2443440">theta</span> <span m="2444120">dot</span>
  <span m="2445060">dt</span> <span m="2446980">is</span> <span m="2447230">actually</span>
  <span m="2447720">equal</span> <span m="2448060">to,</span> <span m="2448200">again,</span>
  <span m="2448740">the</span> <span m="2449500">second</span> <span m="2449930">derivative,</span>
  <span m="2451690">which</span> <span m="2451940">is</span> <span m="2452130">equal</span>
  <span m="2452520">to</span> <span m="2453840">g</span> <span m="2454920">theta</span>
  <span m="2455810">provided</span> <span m="2456230">by</span> <span m="2456370">L.</span>
  <span m="2459390">You</span> <span m="2459560">may</span> <span m="2459720">be</span>
  <span m="2459840">asking,</span> <span m="2460580">why</span> <span m="2461180">am</span>
  <span m="2461360">I</span> <span m="2461460">doing</span> <span m="2461830">this?</span>
  <span m="2462600">Again,</span> <span m="2463000">I''m</span> <span m="2463140">sorry.</span>
  <span m="2463570">So</span> <span m="2463800">there</span> <span m="2463980">is</span>
  <span m="2464100">a</span> <span m="2464160">negative</span> <span m="2464600">sign</span>
  <span m="2465060">on</span> <span m="2465520">this.</span> <span m="2465635">I</span>
  <span m="2465750">have</span> <span m="2465865">forgotten</span> <span m="2465980">because--</span>
  <span m="2468550">so</span> <span m="2468620">if</span> <span m="2469080">theta</span>
  <span m="2469440">is</span> <span m="2469560">positive,</span> <span m="2469991">the</span>
  <span m="2470422">acceleration</span> <span m="2470853">is</span> <span m="2471284">in</span>
  <span m="2471715">the</span> <span m="2472146">negative</span> <span m="2472363">direction,</span>
  <span m="2472580">so</span> <span m="2472720">I''m</span> <span m="2472940">using</span>
  <span m="2473180">a</span> <span m="2473290">negative</span> <span m="2473560">sign.</span>
  <span m="2476880">Yeah,</span> <span m="2477070">if</span> <span m="2477260">you</span>
  <span m="2477360">discover</span> <span m="2477800">something</span> <span m="2478050">like</span>
  <span m="2478240">this,</span> <span m="2478723">please</span> <span m="2480172">shout.</span></p><p><span
  m="2484250">I''m</span> <span m="2484480">writing</span> <span m="2484840">it</span>
  <span m="2484960">this</span> <span m="2485190">way</span> <span m="2485430">because</span>
  <span m="2487820">remember</span> <span m="2488320">the</span> <span m="2488430">schemes</span>
  <span m="2489030">we</span> <span m="2489280">have</span> <span m="2489510">been</span>
  <span m="2489780">deriving</span> <span m="2491100">are</span> <span m="2491720">also</span>
  <span m="2491960">first-order</span> <span m="2492735">ODEs.</span> <span m="2494700">What</span>
  <span m="2494960">are</span> <span m="2495070">first-order</span> <span m="2495690">ODE</span>
  <span m="2495810">mean?</span> <span m="2498550">It</span> <span m="2498740">means</span>
  <span m="2499060">I</span> <span m="2499210">can</span> <span m="2499410">only</span>
  <span m="2499670">have</span> <span m="2499890">first-order</span> <span m="2500280">derivatives</span>
  <span m="2500840">through</span> <span m="2501800">time.</span> <span m="2502906">All</span>
  <span m="2503280">right.</span> <span m="2504730">So</span> <span m="2504890">if</span>
  <span m="2505060">I</span> <span m="2505200">have</span> <span m="2505360">a</span>
  <span m="2505430">second-order</span> <span m="2505880">ODE</span> <span m="2506600">here,</span>
  <span m="2506960">I</span> <span m="2507090">need</span> <span m="2507290">to</span>
  <span m="2507390">convert</span> <span m="2507950">it</span> <span m="2508260">into</span>
  <span m="2508600">a</span> <span m="2508750">first-order</span> <span m="2509320">ODE.</span>
  <span m="2510970">Actually,</span> <span m="2511300">I</span> <span m="2511370">cannot</span>
  <span m="2511900">convert</span> <span m="2512240">it</span> <span m="2512400">into</span>
  <span m="2512700">first-order</span> <span m="2513210">ODE.</span> <span m="2514480">I</span>
  <span m="2514670">have</span> <span m="2514820">to</span> <span m="2514910">convert</span>
  <span m="2515350">it</span> <span m="2515470">into</span> <span m="2516360">two</span>
  <span m="2516770">coupled</span> <span m="2518040">first-order</span> <span m="2518550">ODEs.</span></p><p><span
  m="2520440">Whenever</span> <span m="2520920">you</span> <span m="2521070">have</span>
  <span m="2521210">a</span> <span m="2521270">second-order</span> <span m="2521890">ODE,</span>
  <span m="2522110">you</span> <span m="2522320">can</span> <span m="2522530">always</span>
  <span m="2523030">convert</span> <span m="2523505">it</span> <span m="2523742">into</span>
  <span m="2523980">two</span> <span m="2524455">first-order</span> <span m="2524930">ODEs.</span>
  <span m="2525530">Whenever</span> <span m="2525910">you</span> <span m="2526020">have</span>
  <span m="2526160">a</span> <span m="2526230">third-order</span> <span m="2526950">ODE,</span>
  <span m="2527260">you</span> <span m="2527693">can</span> <span m="2527909">always</span>
  <span m="2528126">convert</span> <span m="2528343">it</span> <span m="2528451">into</span>
  <span m="2528560">three</span> <span m="2528825">first-order</span> <span m="2529440">ODEs</span>
  <span m="2530460">by</span> <span m="2530810">introducing</span> <span m="2533180">basically</span>
  <span m="2533590">a</span> <span m="2533630">separate</span> <span m="2534020">variable,</span>
  <span m="2534370">theta</span> <span m="2535440">dot.</span> <span m="2536690">So</span>
  <span m="2536890">here</span> <span m="2537400">I</span> <span m="2537590">am</span>
  <span m="2537870">having</span> <span m="2538480">theta</span> <span m="2538820">and</span>
  <span m="2539020">theta</span> <span m="2539160">dot</span> <span m="2539620">as</span>
  <span m="2539890">two</span> <span m="2540050">variables.</span> <span m="2541630">The</span>
  <span m="2541730">derivative</span> <span m="2542510">of</span> <span m="2542710">both</span>
  <span m="2543000">theta</span> <span m="2543220">and</span> <span m="2543500">theta</span>
  <span m="2543850">dot</span> <span m="2544950">is</span> <span m="2545140">a</span>
  <span m="2545200">function</span> <span m="2545560">of</span> <span m="2545660">theta</span>
  <span m="2545980">and</span> <span m="2546170">theta</span> <span m="2546572">dot.</span></p><p><span
  m="2551510">Is</span> <span m="2551640">it</span> <span m="2551720">clear?</span>
  <span m="2553310">Let</span> <span m="2553840">me</span> <span m="2553940">do</span>
  <span m="2554130">this.</span> <span m="2555130">Let</span> <span m="2555250">me</span>
  <span m="2555490">go</span> <span m="2555870">to</span> <span m="2556020">MATLAB</span>
  <span m="2557690">and</span> <span m="2558320">start</span> <span m="2558630">to</span>
  <span m="2559560">write</span> <span m="2559920">this.</span> <span m="2562160">Let</span>
  <span m="2562330">me</span> <span m="2562420">do</span> <span m="2562600">this.</span>
  <span m="2563080">I''m</span> <span m="2563450">going</span> <span m="2563590">to</span>
  <span m="2563730">create</span> <span m="2564080">an</span> <span m="2564390">empty</span>
  <span m="2564873">file</span> <span m="2565356">here.</span> <span m="2565840">I''m</span>
  <span m="2566000">going</span> <span m="2566120">to</span> <span m="2566210">find</span>
  <span m="2566550">out</span> <span m="2566740">why</span> <span m="2566910">MATLAB</span>
  <span m="2567300">doesn''t</span> <span m="2567550">listen</span> <span m="2567890">to</span>
  <span m="2568381">me.</span> <span m="2570840">It''s</span> <span m="2570900">called</span>
  <span m="2571373">pendulum.m.</span> <span m="2575010">Open</span> <span m="2576381">Pendulum.</span>
  <span m="2579960">That''s</span> <span m="2580170">good.</span> <span m="2583590">So</span>
  <span m="2584210">when</span> <span m="2585030">Windows</span> <span m="2585460">doesn''t</span>
  <span m="2585710">work,</span> <span m="2586040">you</span> <span m="2586180">can</span>
  <span m="2586673">always</span> <span m="2587166">rely</span> <span m="2587413">on</span>
  <span m="2587660">MATLAB.</span></p><p><span m="2589020">So</span> <span m="2589160">what</span>
  <span m="2589640">do</span> <span m="2589730">we</span> <span m="2589840">do?</span>
  <span m="2592540">We</span> <span m="2592680">want</span> <span m="2592890">to</span>
  <span m="2593110">code</span> <span m="2593370">up</span> <span m="2593550">this</span>
  <span m="2593860">differential</span> <span m="2594190">equation</span> <span m="2594630">first.</span>
  <span m="2595070">Whatever</span> <span m="2595550">scheme</span> <span m="2596180">we</span>
  <span m="2596430">use,</span> <span m="2597010">we</span> <span m="2597210">need</span>
  <span m="2597400">to</span> <span m="2597950">have</span> <span m="2598140">a</span>
  <span m="2598210">function</span> <span m="2598740">that</span> <span m="2598960">computes</span>
  <span m="2600030">f</span> <span m="2600250">of</span> <span m="2600390">u.</span>
  <span m="2601730">The</span> <span m="2601820">function</span> <span m="2602230">should</span>
  <span m="2603300">do</span> <span m="2603390">like</span> <span m="2603710">this.</span>
  <span m="2604180">You</span> <span m="2604340">give</span> <span m="2604640">me</span>
  <span m="2604920">u,</span> <span m="2605650">the</span> <span m="2605780">function</span>
  <span m="2606170">returns</span> <span m="2607330">f</span> <span m="2607540">of</span>
  <span m="2607925">u</span> <span m="2608310">or</span> <span m="2608710">du</span>
  <span m="2609145">dt.</span> <span m="2612070">I</span> <span m="2612190">just</span>
  <span m="2612450">call</span> <span m="2612730">this</span> <span m="2612960">function</span>
  <span m="2614670">du</span> <span m="2614830">dt</span> <span m="2615720">equal</span>
  <span m="2616050">to</span> <span m="2616190">f</span> <span m="2616630">of</span>
  <span m="2617070">u.</span></p><p><span m="2619740">And</span> <span m="2620070">what</span>
  <span m="2620190">is</span> <span m="2620470">u?</span> <span m="2621590">u</span>
  <span m="2621900">actually</span> <span m="2622370">contains</span> <span m="2624200">theta</span>
  <span m="2625670">and</span> <span m="2626676">theta</span> <span m="2627550">dot.</span>
  <span m="2630270">Let</span> <span m="2630730">me</span> <span m="2630820">do</span>
  <span m="2631010">this.</span> <span m="2631650">Theta</span> <span m="2631790">equal</span>
  <span m="2632290">to</span> <span m="2632440">this</span> <span m="2632540">first</span>
  <span m="2632930">element</span> <span m="2633360">of</span> <span m="2633540">u.</span>
  <span m="2636600">Theta</span> <span m="2636860">dot</span> <span m="2637770">is</span>
  <span m="2638000">equal</span> <span m="2638260">to</span> <span m="2638360">the</span>
  <span m="2638470">second</span> <span m="2638925">element</span> <span m="2639380">of</span>
  <span m="2639835">u.</span> <span m="2643010">I''m</span> <span m="2643210">going</span>
  <span m="2643370">to</span> <span m="2643980">be</span> <span m="2644150">computing</span>
  <span m="2645176">theta</span> <span m="2645950">double</span> <span m="2646280">dot--</span>
  <span m="2646720">I''m</span> <span m="2646870">just</span> <span m="2647090">going</span>
  <span m="2647200">to</span> <span m="2647340">call</span> <span m="2647680">this</span>
  <span m="2648020">d</span> <span m="2648180">dot--</span> <span m="2649910">is</span>
  <span m="2653610">equal</span> <span m="2653990">to</span> <span m="2655070">minus</span>
  <span m="2655710">g</span> <span m="2656060">times</span> <span m="2656410">theta</span>
  <span m="2657530">divided</span> <span m="2657810">by</span> <span m="2657930">L.</span>
  <span m="2659660">L</span> <span m="2660590">is</span> <span m="2660860">equal</span>
  <span m="2661080">to</span> <span m="2661160">minus</span> <span m="2661950">g</span>
  <span m="2663200">times</span> <span m="2663680">theta</span> <span m="2664900">divided</span>
  <span m="2665250">by</span> <span m="2665390">5.</span></p><p><span m="2669040">So</span>
  <span m="2669090">now</span> <span m="2669760">what</span> <span m="2670060">I</span>
  <span m="2670290">need</span> <span m="2670460">to</span> <span m="2670570">return</span>
  <span m="2670810">is</span> <span m="2671266">du</span> <span m="2671722">dt.</span>
  <span m="2672180">And</span> <span m="2672400">what</span> <span m="2672580">is</span>
  <span m="2672730">du</span> <span m="2673168">dt</span> <span m="2673606">now?</span>
  <span m="2674920">Remember</span> <span m="2675230">u</span> <span m="2675530">is</span>
  <span m="2675830">theta</span> <span m="2676180">and</span> <span m="2676340">theta</span>
  <span m="2676758">dot.</span> <span m="2678430">So</span> <span m="2678620">du</span>
  <span m="2678975">dt</span> <span m="2679330">is</span> <span m="2679500">actually</span>
  <span m="2679810">theta</span> <span m="2680670">dot</span> <span m="2681150">and</span>
  <span m="2681500">theta</span> <span m="2682110">double</span> <span m="2683056">dot.</span>
  <span m="2689330">That''s</span> <span m="2689530">all.</span> <span m="2690190">That</span>
  <span m="2690480">function</span> <span m="2691020">encodes</span> <span m="2692170">the</span>
  <span m="2692310">differential</span> <span m="2692880">equation.</span> <span m="2693620">If</span>
  <span m="2693820">it</span> <span m="2693865">will</span> <span m="2693910">give</span>
  <span m="2694160">me</span> <span m="2694280">a</span> <span m="2694340">u,</span>
  <span m="2694910">I''m</span> <span m="2695160">going</span> <span m="2695320">to</span>
  <span m="2695390">return</span> <span m="2695620">a</span> <span m="2696040">du</span>
  <span m="2696460">dt.</span> <span m="2696880">Here</span> <span m="2697050">u</span>
  <span m="2697320">is</span> <span m="2697460">a</span> <span m="2697570">[? matter
  ?]</span> <span m="2697820">of</span> <span m="2697930">2.</span> <span m="2698180">du</span>
  <span m="2698485">dt</span> <span m="2698790">is</span> <span m="2698930">going</span>
  <span m="2699250">to</span> <span m="2699570">be</span> <span m="2699760">a</span>
  <span m="2700090">[? matter ?]</span> <span m="2700200">of</span> <span m="2700310">2.</span>
  <span m="2702140">Clear</span> <span m="2703270">what</span> <span m="2703400">this</span>
  <span m="2703440">function</span> <span m="2703810">does?</span></p><p><span m="2706960">Now,</span>
  <span m="2707940">let''s</span> <span m="2708580">see</span> <span m="2714740">what</span>
  <span m="2715120">forward</span> <span m="2715470">Euler</span> <span m="2715680">does.</span>
  <span m="2716530">Let''s</span> <span m="2716830">define</span> <span m="2716940">dt</span>
  <span m="2717840">equals</span> <span m="2718260">0.1,</span> <span m="2719100">and</span>
  <span m="2719310">we</span> <span m="2719420">want</span> <span m="2719610">to</span>
  <span m="2719690">simulate</span> <span m="2720250">this</span> <span m="2720480">thing</span>
  <span m="2720700">for</span> <span m="2721130">how</span> <span m="2721560">long?</span></p><p><span
  m="2722850">AUDIENCE:</span> <span m="2722930">[INAUDIBLE].</span></p><p><span m="2725280">QIQI
  WANG:</span> <span m="2725620">60</span> <span m="2725910">seconds.</span> <span
  m="2726373">All</span> <span m="2726836">right.</span> <span m="2729660">I</span>
  <span m="2729960">have</span> <span m="2730110">to</span> <span m="2730580">initialize</span>
  <span m="2731990">a</span> <span m="2732160">u0.</span> <span m="2733990">So</span>
  <span m="2734140">what</span> <span m="2735440">u0</span> <span m="2735740">you</span>
  <span m="2735880">want?</span> <span m="2736280">I</span> <span m="2736610">mean,</span>
  <span m="2736920">it</span> <span m="2737050">has</span> <span m="2737210">to</span>
  <span m="2737280">be</span> <span m="2737400">a</span> <span m="2737460">theta</span>
  <span m="2737920">and</span> <span m="2738170">d</span> <span m="2738310">theta</span>
  <span m="2738750">dt.</span> <span m="2740950">Anybody?</span></p><p><span m="2741230">AUDIENCE:</span>
  <span m="2741510">[INAUDIBLE].</span></p><p><span m="2745316">QIQI WANG:</span>
  <span m="2745740">If</span> <span m="2746600">you</span> <span m="2746690">look</span>
  <span m="2746960">at</span> <span m="2747150">this,</span> <span m="2747900">when</span>
  <span m="2749980">I</span> <span m="2750010">am</span> <span m="2750160">approximating</span>
  <span m="2751000">sine</span> <span m="2751420">theta</span> <span m="2751720">as</span>
  <span m="2751980">theta,</span> <span m="2754920">is</span> <span m="2755130">it</span>
  <span m="2755290">in</span> <span m="2755640">degrees</span> <span m="2755930">or</span>
  <span m="2756356">radius?</span> <span m="2758060">It</span> <span m="2758220">can</span>
  <span m="2758380">be</span> <span m="2758560">either,</span> <span m="2758760">right?</span>
  <span m="2759930">It</span> <span m="2760080">can</span> <span m="2760240">be</span>
  <span m="2760380">either,</span> <span m="2760730">so</span> <span m="2760810">it</span>
  <span m="2760890">doesn''t</span> <span m="2761080">matter.</span> <span m="2762860">Oh,</span>
  <span m="2763070">yes,</span> <span m="2763360">it</span> <span m="2763440">doesn''t</span>
  <span m="2763640">matter</span> <span m="2763880">because</span> <span m="2764200">it''s</span>
  <span m="2764340">a</span> <span m="2764400">linear</span> <span m="2764770">equation.</span></p><p><span
  m="2765780">It''s</span> <span m="2765950">a</span> <span m="2766010">linear</span>
  <span m="2766320">equation,</span> <span m="2766790">which</span> <span m="2766950">means</span>
  <span m="2768170">if</span> <span m="2768350">I</span> <span m="2768460">change</span>
  <span m="2768810">a</span> <span m="2768880">unit,</span> <span m="2770060">I''m</span>
  <span m="2770190">just</span> <span m="2770400">scaling</span> <span m="2770830">everything</span>
  <span m="2771580">by</span> <span m="2772150">the</span> <span m="2772490">unit</span>
  <span m="2772740">conversion</span> <span m="2773210">factor.</span> <span m="2774110">And</span>
  <span m="2774520">the</span> <span m="2774915">linear</span> <span m="2775112">equation</span>
  <span m="2775310">still</span> <span m="2775640">should</span> <span m="2775790">be</span>
  <span m="2775900">satisfied.</span> <span m="2778000">That''s</span> <span m="2778540">like</span>
  <span m="2778810">the</span> <span m="2778870">definition</span> <span m="2779390">of</span>
  <span m="2779500">the</span> <span m="2779570">linear</span> <span m="2779850">equation.</span>
  <span m="2780670">If</span> <span m="2780820">you</span> <span m="2780930">scale</span>
  <span m="2781195">everything</span> <span m="2781660">by</span> <span m="2781910">some</span>
  <span m="2782265">factor,</span> <span m="2782620">it''s</span> <span m="2783050">still</span>
  <span m="2783476">satisfied.</span></p><p><span m="2784330">So</span> <span m="2784950">it</span>
  <span m="2785090">can</span> <span m="2785290">be</span> <span m="2785430">either</span>
  <span m="2786890">degrees</span> <span m="2787340">or</span> <span m="2788510">radius.</span></p><p><span
  m="2789850">AUDIENCE:</span> <span m="2790295">0.</span></p><p><span m="2791185">QIQI
  WANG:</span> <span m="2791630">0.</span> <span m="2794900">And</span> <span m="2795140">1?</span></p><p><span
  m="2795440">AUDIENCE:</span> <span m="2795883">[? It''s ?]</span> <span m="2796030">really</span>
  <span m="2796178">boring.</span></p><p><span m="2796326">QIQI WANG:</span> <span
  m="2796770">It''s</span> <span m="2796910">really</span> <span m="2797120">boring.</span>
  <span m="2797460">OK.</span></p><p><span m="2797820">AUDIENCE:</span> <span m="2798300">[INAUDIBLE].</span></p><p><span
  m="2799740">QIQI WANG:</span> <span m="2800140">So</span> <span m="2800350">this</span>
  <span m="2800610">is</span> <span m="2800870">my</span> <span m="2801140">initial</span>
  <span m="2801470">condition.</span> <span m="2802375">And</span> <span m="2802780">here''s</span>
  <span m="2803090">the</span> <span m="2803436">forward</span> <span m="2803782">Euler.</span>
  <span m="2805100">Did</span> <span m="2805370">you</span> <span m="2805820">see</span>
  <span m="2806270">this?</span> <span m="2807220">Actually,</span> <span m="2808080">I</span>
  <span m="2808220">think</span> <span m="2808480">I</span> <span m="2808550">should</span>
  <span m="2808740">do</span> <span m="2808900">this.</span> <span m="2809270">I</span>
  <span m="2809490">should</span> <span m="2811550">make</span> <span m="2811790">another</span>
  <span m="2812200">file</span> <span m="2813200">so</span> <span m="2813220">that</span>
  <span m="2813600">you</span> <span m="2813690">don''t</span> <span m="2813880">have</span>
  <span m="2814060">to</span> <span m="2814730">look</span> <span m="2815060">at</span>
  <span m="2815840">the</span> <span m="2815910">bottom.</span> <span m="2825820">forwardeuler.m.</span>
  <span m="2830090">I</span> <span m="2830190">have</span> <span m="2830340">to</span>
  <span m="2830430">open</span> <span m="2830926">forwardeuler.m.</span> <span m="2834100">So</span>
  <span m="2834440">I''m</span> <span m="2834600">going</span> <span m="2834760">to</span>
  <span m="2834850">be</span> <span m="2835010">setting</span> <span m="2835440">u0</span>
  <span m="2838440">1,</span> <span m="2839940">0.</span> <span m="2841060">I''m</span>
  <span m="2841210">going</span> <span m="2841330">to</span> <span m="2841840">set</span>
  <span m="2842240">dt</span> <span m="2842640">equal</span> <span m="2843040">to</span>
  <span m="2843440">0.1,</span> <span m="2843650">t</span> <span m="2844470">equal</span>
  <span m="2845290">to</span> <span m="2845700">60,</span> <span m="2846930">and</span>
  <span m="2847330">I''m</span> <span m="2847383">going</span> <span m="2847436">to</span>
  <span m="2847490">forward</span> <span m="2848160">t</span> <span m="2848640">equal</span>
  <span m="2848995">to</span> <span m="2849350">0,</span> <span m="2851540">0,</span>
  <span m="2853034">dt</span> <span m="2853938">t.</span> <span m="2856200">So</span>
  <span m="2856380">this</span> <span m="2856570">is</span> <span m="2856630">a</span>
  <span m="2856730">loop.</span></p><p><span m="2859190">I''m</span> <span m="2859420">going</span>
  <span m="2859550">to</span> <span m="2859620">compute</span> <span m="2860990">du</span>
  <span m="2861080">dt</span> <span m="2862500">is</span> <span m="2862740">equal</span>
  <span m="2863140">to</span> <span m="2868200">actually,</span> <span m="2868630">I</span>
  <span m="2868870">think</span> <span m="2869507">pendulum</span> <span m="2870670">of</span>
  <span m="2870960">u0.</span> <span m="2874340">And</span> <span m="2875970">what</span>
  <span m="2876180">is</span> <span m="2876320">forward</span> <span m="2876610">Euler?</span>
  <span m="2877900">Forward</span> <span m="2878240">Euler</span> <span m="2878580">is</span>
  <span m="2878820">my</span> <span m="2878960">u</span> <span m="2879470">at</span>
  <span m="2879630">the</span> <span m="2879700">next</span> <span m="2879980">step</span>
  <span m="2880660">is</span> <span m="2880880">equal</span> <span m="2881120">u0</span>
  <span m="2882262">plus</span> <span m="2884190">u</span> <span m="2884420">dt</span>
  <span m="2884930">times</span> <span m="2885866">dt.</span> <span m="2891270">And</span>
  <span m="2892390">when</span> <span m="2892610">I</span> <span m="2892710">go</span>
  <span m="2892900">to</span> <span m="2893010">the</span> <span m="2893110">next</span>
  <span m="2893360">step,</span> <span m="2893890">u0</span> <span m="2894560">should</span>
  <span m="2894780">be</span> <span m="2894900">set</span> <span m="2895340">to</span>
  <span m="2895780">u.</span></p><p><span m="2897540">All</span> <span m="2897700">right.</span>
  <span m="2899210">And</span> <span m="2899420">now</span> <span m="2900140">what</span>
  <span m="2900310">I</span> <span m="2900380">want</span> <span m="2900570">to</span>
  <span m="2900660">do</span> <span m="2901170">is</span> <span m="2901430">I</span>
  <span m="2901580">want</span> <span m="2901880">to</span> <span m="2902610">record</span>
  <span m="2903650">the</span> <span m="2903840">history.</span> <span m="2905650">All</span>
  <span m="2906090">right.</span> <span m="2906900">I</span> <span m="2907010">want</span>
  <span m="2907170">to</span> <span m="2907240">record</span> <span m="2907580">the</span>
  <span m="2907640">history.</span> <span m="2909060">What</span> <span m="2909270">I</span>
  <span m="2909330">want</span> <span m="2909500">to</span> <span m="2909580">do</span>
  <span m="2909730">is</span> <span m="2910000">history</span> <span m="2910480">is</span>
  <span m="2910790">equal</span> <span m="2911400">to</span> <span m="2911700">an</span>
  <span m="2911930">empty</span> <span m="2912265">array,</span> <span m="2914810">and</span>
  <span m="2915470">the</span> <span m="2915810">history</span> <span m="2916720">is</span>
  <span m="2917175">equal</span> <span m="2917630">to</span> <span m="2918540">history</span>
  <span m="2921306">u0.</span> <span m="2923550">I''m</span> <span m="2923720">going</span>
  <span m="2923780">to</span> <span m="2923940">run</span> <span m="2924100">this.</span>
  <span m="2925716">It</span> <span m="2926150">doesn''t</span> <span m="2926545">run.</span>
  <span m="2928220">I''m</span> <span m="2928370">going</span> <span m="2928620">to</span>
  <span m="2929071">forward</span> <span m="2929522">Euler.</span> <span m="2932190">It''s</span>
  <span m="2932400">done,</span> <span m="2933190">and</span> <span m="2933380">I</span>
  <span m="2933510">have</span> <span m="2934340">an</span> <span m="2934500">array</span>
  <span m="2934800">history,</span> <span m="2935610">and</span> <span m="2935820">I</span>
  <span m="2935900">can</span> <span m="2936110">plot</span> <span m="2937760">history.</span>
  <span m="2940010">It</span> <span m="2940200">is</span> <span m="2940380">done</span>
  <span m="2940560">to</span> <span m="2940920">give</span> <span m="2941120">me</span>
  <span m="2941230">a</span> <span m="2941360">history</span> <span m="2942590">of</span>
  <span m="2942850">the</span> <span m="2943050">numerical</span> <span m="2943590">solutions.</span>
  <span m="2947480">Does</span> <span m="2947630">it</span> <span m="2947720">look</span>
  <span m="2947890">good?</span> <span m="2950830">No.</span></p><p><span m="2952570">So</span>
  <span m="2952790">this</span> <span m="2953000">is</span> <span m="2953130">forward</span>
  <span m="2953440">Euler,</span> <span m="2954090">and</span> <span m="2954570">I''m</span>
  <span m="2954890">using</span> <span m="2955970">a</span> <span m="2956450">pretty</span>
  <span m="2956780">big</span> <span m="2957040">time</span> <span m="2957270">step.</span>
  <span m="2959230">Let''s</span> <span m="2959620">see</span> <span m="2959860">what</span>
  <span m="2961030">can</span> <span m="2961300">I</span> <span m="2961660">do</span>
  <span m="2961850">better</span> <span m="2962330">if</span> <span m="2962510">I</span>
  <span m="2962590">use</span> <span m="2962900">a</span> <span m="2963090">smaller</span>
  <span m="2963430">time</span> <span m="2963925">step.</span> <span m="2969870">You</span>
  <span m="2970310">see,</span> <span m="2971480">this</span> <span m="2971650">is</span>
  <span m="2971730">better.</span> <span m="2973550">And</span> <span m="2973680">a</span>
  <span m="2973940">difficult</span> <span m="2974290">solution</span> <span m="2974800">should</span>
  <span m="2975060">be</span> <span m="2975780">an</span> <span m="2976080">oscillating</span>
  <span m="2977030">pendulum</span> <span m="2978210">with</span> <span m="2978630">no</span>
  <span m="2979220">increase</span> <span m="2980630">in</span> <span m="2980840">the</span>
  <span m="2980950">magnitude</span> <span m="2981630">of</span> <span m="2981770">the</span>
  <span m="2981840">oscillation.</span> <span m="2984480">And</span> <span m="2984670">now</span>
  <span m="2984870">can</span> <span m="2985050">I</span> <span m="2985140">do</span>
  <span m="2985310">even</span> <span m="2985600">better</span> <span m="2987240">by</span>
  <span m="2988920">having</span> <span m="2989410">an</span> <span m="2989760">even</span>
  <span m="2990140">smaller</span> <span m="2990470">delta</span> <span m="2990800">t?</span></p><p><span
  m="2997660">All</span> <span m="2997950">right.</span></p><p><span m="2998310">AUDIENCE:</span>
  <span m="2998800">It''s</span> <span m="2999290">still</span> <span m="2999780">working.</span></p><p><span
  m="3000270">QIQI WANG:</span> <span m="3000460">Still</span> <span m="3000820">working?</span>
  <span m="3004131">Am</span> <span m="3004610">I</span> <span m="3004950">having</span>
  <span m="3005240">a</span> <span m="3005310">reasonable</span> <span m="3005830">delta</span>
  <span m="3006000">t?</span> <span m="3006805">Yeah.</span> <span m="3007200">It</span>
  <span m="3007440">should</span> <span m="3007570">be--</span> <span m="3017153">It</span>
  <span m="3017660">actually</span> <span m="3018030">takes</span> <span m="3018805">a</span>
  <span m="3019110">pretty</span> <span m="3019480">absurd</span> <span m="3020120">value</span>
  <span m="3020480">of</span> <span m="3020670">delta</span> <span m="3020740">t</span>
  <span m="3020940">to</span> <span m="3021350">make</span> <span m="3021610">this</span>
  <span m="3022660">like</span> <span m="3024120">not</span> <span m="3024470">even</span>
  <span m="3024820">super</span> <span m="3025170">accurate.</span> <span m="3025990">And</span>
  <span m="3026140">you</span> <span m="3026500">can</span> <span m="3026860">visually</span>
  <span m="3027205">see</span> <span m="3027550">the</span> <span m="3027830">empty</span>
  <span m="3028300">array</span> <span m="3028770">still</span> <span m="3029710">growing.</span>
  <span m="3031570">It</span> <span m="3031750">is</span> <span m="3031920">visually</span>
  <span m="3032370">different</span> <span m="3032900">from</span> <span m="3033190">the</span>
  <span m="3033320">analytical</span> <span m="3033860">solution</span> <span m="3035020">of</span>
  <span m="3035190">the</span> <span m="3035485">ODE.</span></p><p><span m="3040180">So</span>
  <span m="3041360">let''s</span> <span m="3041660">go</span> <span m="3041830">back</span>
  <span m="3042220">and</span> <span m="3043760">try</span> <span m="3045380">to</span>
  <span m="3045510">implement</span> <span m="3046120">something</span> <span m="3046570">that</span>
  <span m="3046850">is</span> <span m="3047000">better.</span> <span m="3049150">Just</span>
  <span m="3049960">name</span> <span m="3050300">a</span> <span m="3050390">scheme</span>
  <span m="3050800">that</span> <span m="3050940">is</span> <span m="3051140">better</span>
  <span m="3051440">than</span> <span m="3051650">forward</span> <span m="3051830">Euler.</span></p><p><span
  m="3052280">AUDIENCE:</span> <span m="3052700">Midpoint.</span></p><p><span m="3052910">QIQI
  WANG:</span> <span m="3053120">Midpoint.</span> <span m="3055390">Sure,</span> <span
  m="3055760">let''s</span> <span m="3055990">do</span> <span m="3056140">midpoint.</span>
  <span m="3057610">To</span> <span m="3057890">avoid</span> <span m="3060980">repetitive</span>
  <span m="3061470">work,</span> <span m="3061970">let</span> <span m="3062170">me</span>
  <span m="3062290">just</span> <span m="3062720">rename</span> <span m="3063690">the</span>
  <span m="3063840">Forward</span> <span m="3063990">Euler</span> <span m="3064480">using</span>
  <span m="3064900">Midpoint.</span> <span m="3067300">And</span> <span m="3067440">just</span>
  <span m="3067680">copying</span> <span m="3067955">the</span> <span m="3068230">Forward</span>
  <span m="3068560">Euler</span> <span m="3069700">and</span> <span m="3069960">to</span>
  <span m="3070050">rename</span> <span m="3070510">it</span> <span m="3070630">as</span>
  <span m="3070870">Midpoint.</span> <span m="3071580">I''m</span> <span m="3071860">going</span>
  <span m="3072040">to</span> <span m="3072190">load</span> <span m="3072820">this</span>
  <span m="3072960">guy.</span> <span m="3074800">I''m</span> <span m="3075080">opening</span>
  <span m="3075568">midpoint.m.</span> <span m="3078010">So</span> <span m="3078160">this</span>
  <span m="3078370">is</span> <span m="3078500">Forward</span> <span m="3078730">Euler,</span>
  <span m="3080270">but</span> <span m="3080660">I''m</span> <span m="3080860">going</span>
  <span m="3081050">to</span> <span m="3081280">change</span> <span m="3081600">it</span>
  <span m="3081710">to</span> <span m="3084650">Midpoint.</span></p><p><span m="3090290">How</span>
  <span m="3090620">should</span> <span m="3091080">midpoint</span> <span m="3091620">be</span>
  <span m="3091740">different.</span> <span m="3095640">What</span> <span m="3096380">is</span>
  <span m="3096500">the</span> <span m="3096600">difference</span> <span m="3097260">between</span>
  <span m="3097545">midpoint</span> <span m="3098070">and</span> <span m="3098200">forward</span>
  <span m="3098480">Euler?</span></p><p><span m="3099208">AUDIENCE:</span> <span m="3099676">[INAUDIBLE].</span></p><p><span
  m="3104830">QIQI WANG:</span> <span m="3105330">If</span> <span m="3105520">you</span>
  <span m="3105630">look</span> <span m="3105900">at</span> <span m="3106000">the</span>
  <span m="3106070">formula,</span> <span m="3106830">midpoint,</span> <span m="3114330">instead</span>
  <span m="3115040">of</span> <span m="3115770">ui</span> <span m="3116110">plus</span>
  <span m="3116450">1</span> <span m="3116790">equal</span> <span m="3117290">to</span>
  <span m="3117430">ui,</span> <span m="3119120">plus</span> <span m="3119300">delta</span>
  <span m="3119460">t</span> <span m="3119660">times</span> <span m="3119950">fu,</span>
  <span m="3120770">I</span> <span m="3120930">have</span> <span m="3121130">ui</span>
  <span m="3121490">plus</span> <span m="3121690">1</span> <span m="3121980">equal</span>
  <span m="3122290">to</span> <span m="3122470">ui</span> <span m="3122850">minus</span>
  <span m="3123330">1</span> <span m="3123620">plus</span> <span m="3124460">2</span>
  <span m="3124750">delta</span> <span m="3124850">t</span> <span m="3125080">times</span>
  <span m="3125530">fu.</span> <span m="3127790">So</span> <span m="3128050">two</span>
  <span m="3128290">things,</span> <span m="3129010">instead</span> <span m="3129450">of</span>
  <span m="3130280">ui,</span> <span m="3130560">I</span> <span m="3131020">need</span>
  <span m="3131230">ui</span> <span m="3131510">minus</span> <span m="3131720">1.</span>
  <span m="3132630">Instead</span> <span m="3133070">of</span> <span m="3133570">just</span>
  <span m="3134520">f</span> <span m="3134770">of</span> <span m="3134910">ui,</span>
  <span m="3135450">I</span> <span m="3135560">need</span> <span m="3135790">2f</span>
  <span m="3136240">of</span> <span m="3136586">ui.</span> <span m="3137280">The</span>
  <span m="3137390">second</span> <span m="3137740">one</span> <span m="3138360">is</span>
  <span m="3138620">easy</span> <span m="3138910">the</span> <span m="3139050">change.</span>
  <span m="3140340">I</span> <span m="3140460">can</span> <span m="3140670">just</span>
  <span m="3140940">multiply</span> <span m="3141440">by</span> <span m="3141590">2.</span></p><p><span
  m="3142810">Now,</span> <span m="3143380">how</span> <span m="3143810">do</span>
  <span m="3144160">I</span> <span m="3144335">do</span> <span m="3144510">about</span>
  <span m="3144760">this?</span> <span m="3147810">How</span> <span m="3147940">can</span>
  <span m="3148150">I</span> <span m="3148230">get</span> <span m="3149390">ui</span>
  <span m="3149830">minus</span> <span m="3150150">1?</span></p><p><span m="3152925">AUDIENCE:</span>
  <span m="3153424">[INAUDIBLE].</span></p><p><span m="3161408">QIQI WANG:</span>
  <span m="3161907">Good</span> <span m="3162410">point.</span> <span m="3162550">I</span>
  <span m="3162620">need</span> <span m="3162820">to</span> <span m="3162930">do</span>
  <span m="3163110">one</span> <span m="3163410">step</span> <span m="3163820">of</span>
  <span m="3163970">forward</span> <span m="3164270">Euler</span> <span m="3165250">or</span>
  <span m="3165590">something</span> <span m="3166460">to</span> <span m="3166600">get</span>
  <span m="3166990">me</span> <span m="3167180">one</span> <span m="3167520">actually</span>
  <span m="3167870">at</span> <span m="3168120">time</span> <span m="3168330">step</span>
  <span m="3168700">first.</span> <span m="3169070">So</span> <span m="3169300">let</span>
  <span m="3169470">me</span> <span m="3169580">do</span> <span m="3169800">this.</span>
  <span m="3170220">Let</span> <span m="3170340">me</span> <span m="3170470">do</span>
  <span m="3170770">one</span> <span m="3171100">step</span> <span m="3171400">of</span>
  <span m="3171510">forward</span> <span m="3171815">Euler.</span> <span m="3172350">u</span>
  <span m="3172570">dt</span> <span m="3173340">equal</span> <span m="3173500">to</span>
  <span m="3173740">pendulum</span> <span m="3174644">of</span> <span m="3175550">u0.</span>
  <span m="3177190">I''ll</span> <span m="3177360">just</span> <span m="3177720">put</span>
  <span m="3177860">a</span> <span m="3177950">comment</span> <span m="3178430">here,</span>
  <span m="3178896">one</span> <span m="3179362">step</span> <span m="3179828">of</span>
  <span m="3180294">forward</span> <span m="3180760">Euler.</span> <span m="3183090">And</span>
  <span m="3183460">the</span> <span m="3183570">u</span> <span m="3184950">is</span>
  <span m="3185410">equal</span> <span m="3185820">to</span> <span m="3186750">u0</span>
  <span m="3187350">plus</span> <span m="3187830">du</span> <span m="3188237">dt</span>
  <span m="3189460">times</span> <span m="3189796">dt.</span> <span m="3190840">u0</span>
  <span m="3191360">is</span> <span m="3191600">equal</span> <span m="3191930">to</span>
  <span m="3193190">u.</span> <span m="3195380">Is</span> <span m="3195550">that</span>
  <span m="3195710">enough?</span></p><p><span m="3199119">AUDIENCE:</span> <span
  m="3199606">[INAUDIBLE].</span></p><p><span m="3203306">QIQI WANG:</span> <span
  m="3203770">Exactly.</span> <span m="3204590">I</span> <span m="3204750">also</span>
  <span m="3205210">need</span> <span m="3205500">to</span> <span m="3205795">store</span>
  <span m="3206090">something</span> <span m="3206490">else.</span> <span m="3207920">I</span>
  <span m="3208050">need</span> <span m="3208210">to</span> <span m="3208320">do</span>
  <span m="3208490">this.</span> <span m="3209540">See,</span> <span m="3209920">I</span>
  <span m="3210090">need</span> <span m="3210350">to</span> <span m="3210480">store</span>
  <span m="3211200">an</span> <span m="3211450">extra</span> <span m="3212510">step.</span>
  <span m="3213340">That</span> <span m="3213570">is</span> <span m="3213720">why</span>
  <span m="3215220">I</span> <span m="3215340">think</span> <span m="3215630">now</span>
  <span m="3215880">we</span> <span m="3216010">get</span> <span m="3216310">to</span>
  <span m="3216490">why</span> <span m="3216990">it''s</span> <span m="3217390">called</span>
  <span m="3217790">a</span> <span m="3218030">two-step</span> <span m="3218980">scheme</span>
  <span m="3219790">because</span> <span m="3220230">you</span> <span m="3220330">need</span>
  <span m="3220730">to</span> <span m="3220880">store</span> <span m="3221580">two</span>
  <span m="3221670">steps</span> <span m="3222060">in</span> <span m="3222780">your</span>
  <span m="3222980">computer''s</span> <span m="3223540">memory.</span> <span m="3224630">While</span>
  <span m="3224930">for</span> <span m="3225060">the</span> <span m="3225130">forward</span>
  <span m="3225485">Euler</span> <span m="3225840">scheme,</span> <span m="3226090">you</span>
  <span m="3226290">only</span> <span m="3226590">need</span> <span m="3226760">to</span>
  <span m="3226970">store</span> <span m="3227180">u0.</span> <span m="3228140">You</span>
  <span m="3228620">only</span> <span m="3228810">need</span> <span m="3228970">to</span>
  <span m="3229080">store</span> <span m="3229410">one</span> <span m="3229680">step</span>
  <span m="3229965">in</span> <span m="3230250">your</span> <span m="3230460">memory.</span></p><p><span
  m="3231310">So</span> <span m="3231620">implement</span> <span m="3232005">of</span>
  <span m="3232660">midpoint</span> <span m="3233230">scheme,</span> <span m="3234310">the</span>
  <span m="3234560">two-step</span> <span m="3234780">scheme,</span> <span m="3235170">you</span>
  <span m="3235280">need</span> <span m="3235450">to</span> <span m="3235570">store</span>
  <span m="3235680">two</span> <span m="3235820">time</span> <span m="3236450">steps</span>
  <span m="3238160">in</span> <span m="3238380">your</span> <span m="3240450">memory.</span>
  <span m="3240980">You</span> <span m="3241080">have</span> <span m="3241180">to</span>
  <span m="3241280">store</span> <span m="3241410">u0</span> <span m="3241960">and</span>
  <span m="3242180">u00.</span> <span m="3243100">So</span> <span m="3243370">here</span>
  <span m="3243750">I''m</span> <span m="3244010">just</span> <span m="3244160">going</span>
  <span m="3244555">to</span> <span m="3244950">use</span> <span m="3245180">u00,</span>
  <span m="3246060">and</span> <span m="3246250">u00</span> <span m="3246640">equal</span>
  <span m="3246860">to</span> <span m="3247282">u0,</span> <span m="3247704">and</span>
  <span m="3248548">u0</span> <span m="3248970">equal</span> <span m="3249450">to</span>
  <span m="3249868">u.</span> <span m="3252530">You</span> <span m="3252670">keep</span>
  <span m="3253080">two</span> <span m="3253760">previous</span> <span m="3254080">time</span>
  <span m="3254330">steps</span> <span m="3255570">in</span> <span m="3255720">memory.</span>
  <span m="3259730">So</span> <span m="3260250">this</span> <span m="3260740">is</span>
  <span m="3260930">going</span> <span m="3261060">to</span> <span m="3261140">work,</span>
  <span m="3261590">and</span> <span m="3262230">let</span> <span m="3262450">me</span>
  <span m="3262790">go</span> <span m="3262970">back</span> <span m="3263680">to</span>
  <span m="3264380">0.1</span> <span m="3265750">L</span> <span m="3266040">of</span>
  <span m="3266330">t,</span> <span m="3267340">for</span> <span m="3267840">which</span>
  <span m="3268030">forward</span> <span m="3268110">Euler</span> <span m="3268350">did</span>
  <span m="3268440">a</span> <span m="3269290">pretty</span> <span m="3269510">crazy</span>
  <span m="3269920">job.</span> <span m="3270300">It</span> <span m="3270730">went</span>
  <span m="3271020">over</span> <span m="3271330">to</span> <span m="3271590">something</span>
  <span m="3271920">like</span> <span m="3272140">1,000</span> <span m="3272566">or</span>
  <span m="3272992">something.</span></p><p><span m="3275030">Let''s</span> <span
  m="3275920">try</span> <span m="3276140">midpoint.</span> <span m="3280140">Let</span>
  <span m="3280640">me</span> <span m="3281140">Close</span> <span m="3282126">All.</span>
  <span m="3285084">Did</span> <span m="3285577">I</span> <span m="3286070">Close</span>
  <span m="3286563">All?</span> <span m="3291900">Midpoint,</span> <span m="3292500">but</span>
  <span m="3292590">I</span> <span m="3292670">didn''t</span> <span m="3292970">plot</span>
  <span m="3293380">it.</span> <span m="3295840">Plot</span> <span m="3297850">History.</span>
  <span m="3303006">How</span> <span m="3303490">about</span> <span m="3303790">this?</span>
  <span m="3305191">Is</span> <span m="3305660">this</span> <span m="3305900">much</span>
  <span m="3306000">better?</span> <span m="3308105">It''s</span> <span m="3308400">pretty.</span>
  <span m="3311040">So</span> <span m="3311230">let</span> <span m="3311350">me</span>
  <span m="3311870">actually</span> <span m="3312300">plot</span> <span m="3312655">it</span>
  <span m="3313010">not</span> <span m="3313280">just</span> <span m="3313510">the</span>
  <span m="3313640">history.</span> <span m="3314300">Let</span> <span m="3314480">me</span>
  <span m="3314580">actually</span> <span m="3314960">make</span> <span m="3315820">the</span>
  <span m="3315910">primes</span> <span m="3316590">to</span> <span m="3316700">be</span>
  <span m="3316890">accurate.</span> <span m="3317890">Let</span> <span m="3318090">me</span>
  <span m="3318190">make</span> <span m="3318640">0</span> <span m="3318880">dt</span>
  <span m="3319520">t.</span> <span m="3327010">Let</span> <span m="3327150">me</span>
  <span m="3327250">actually</span> <span m="3327650">plot</span> <span m="3328560">the</span>
  <span m="3328760">x-axis</span> <span m="3329560">as</span> <span m="3329790">the</span>
  <span m="3329890">real</span> <span m="3330390">time</span> <span m="3331120">instead</span>
  <span m="3331510">of</span> <span m="3331930">time</span> <span m="3332320">steps.</span>
  <span m="3332960">If</span> <span m="3333110">I</span> <span m="3333210">plot</span>
  <span m="3333590">x-axis</span> <span m="3334060">as</span> <span m="3334370">unset,</span>
  <span m="3334540">it</span> <span m="3334930">would</span> <span m="3335160">be</span>
  <span m="3335470">like</span> <span m="3335650">1,</span> <span m="3336040">2,</span>
  <span m="3336280">3,</span> <span m="3336694">4,</span> <span m="3337108">et</span>
  <span m="3337315">cetera.</span> <span m="3337522">[? It''s ?]</span> <span m="3337936">the</span>
  <span m="3338039">number</span> <span m="3338143">of</span> <span m="3338194">time</span>
  <span m="3338246">steps.</span></p><p><span m="3338350">Now,</span> <span m="3338650">this</span>
  <span m="3338810">is</span> <span m="3338970">plotting</span> <span m="3339280">[INAUDIBLE]</span>
  <span m="3344930">solution</span> <span m="3345480">of</span> <span m="3345630">the</span>
  <span m="3345730">ODE.</span> <span m="3346940">So</span> <span m="3347360">here</span>
  <span m="3347780">we</span> <span m="3348030">get</span> <span m="3349346">visibly</span>
  <span m="3351120">the</span> <span m="3351240">same</span> <span m="3351620">answer</span>
  <span m="3352050">as</span> <span m="3353090">an</span> <span m="3353270">original</span>
  <span m="3353730">solution,</span> <span m="3354350">which</span> <span m="3354690">is</span>
  <span m="3355830">sinusoidal</span> <span m="3356180">oscillations.</span> <span
  m="3361920">We</span> <span m="3362010">got</span> <span m="3362200">half</span>
  <span m="3362410">an</span> <span m="3362540">hour</span> <span m="3362690">left,</span>
  <span m="3363080">but</span> <span m="3363310">I</span> <span m="3363370">want</span>
  <span m="3363620">to</span> <span m="3363900">take</span> <span m="3364160">a</span>
  <span m="3364330">short</span> <span m="3364610">break</span> <span m="3365050">now</span>
  <span m="3366256">to</span> <span m="3366658">get</span> <span m="3367060">our</span>
  <span m="3367470">minds</span> <span m="3367957">back.</span> <span m="3369420">And</span>
  <span m="3369910">next</span> <span m="3370330">what</span> <span m="3370410">we''re</span>
  <span m="3370780">going</span> <span m="3370900">to</span> <span m="3370960">be</span>
  <span m="3371050">doing</span> <span m="3371510">is</span> <span m="3371913">[INAUDIBLE].</span>
  <span m="3375310">I''ll</span> <span m="3375784">see</span> <span m="3376258">how</span>
  <span m="3376732">it</span> <span m="3377206">goes.</span></p><p><span m="3378755">Let''s</span>
  <span m="3379180">continue.</span> <span m="3379340">Is</span> <span m="3379790">everybody</span>
  <span m="3380370">back?</span> <span m="3383250">Before</span> <span m="3383390">I</span>
  <span m="3383850">try</span> <span m="3384300">your</span> <span m="3384690">schemes,</span>
  <span m="3385270">let</span> <span m="3385360">me</span> <span m="3385470">just</span>
  <span m="3385810">show</span> <span m="3386180">how</span> <span m="3386480">easy</span>
  <span m="3386900">it</span> <span m="3387030">is</span> <span m="3387460">to</span>
  <span m="3389880">change</span> <span m="3390280">what</span> <span m="3390600">we</span>
  <span m="3390840">did</span> <span m="3391690">with</span> <span m="3392000">the</span>
  <span m="3392130">linear</span> <span m="3392560">differential</span> <span m="3393030">equation,</span>
  <span m="3394550">change</span> <span m="3394740">it</span> <span m="3394930">to</span>
  <span m="3395040">a</span> <span m="3395270">non-linear</span> <span m="3395460">one.</span>
  <span m="3398330">To</span> <span m="3398450">change</span> <span m="3398700">it</span>
  <span m="3398790">to</span> <span m="3398910">a</span> <span m="3399390">non-linear</span>
  <span m="3399505">one,</span> <span m="3399620">we</span> <span m="3399720">just</span>
  <span m="3400400">keep</span> <span m="3400730">the</span> <span m="3400840">sine</span>
  <span m="3401260">theta</span> <span m="3402330">here.</span> <span m="3403570">Just</span>
  <span m="3403770">replace</span> <span m="3404820">this</span> <span m="3405530">with</span>
  <span m="3406390">sine</span> <span m="3406610">of</span> <span m="3406730">theta.</span>
  <span m="3408320">As</span> <span m="3408460">soon</span> <span m="3409060">as</span>
  <span m="3409210">we</span> <span m="3409360">change</span> <span m="3409730">this</span>
  <span m="3409940">to</span> <span m="3410100">sine</span> <span m="3410450">of</span>
  <span m="3410570">theta,</span> <span m="3411460">we</span> <span m="3411650">lose</span>
  <span m="3412100">the</span> <span m="3412300">analytical</span> <span m="3412850">solution.</span></p><p><span
  m="3416040">I</span> <span m="3416150">don''t</span> <span m="3416310">know</span>
  <span m="3416420">how</span> <span m="3416540">to</span> <span m="3416660">solve</span>
  <span m="3416890">this</span> <span m="3417060">anymore.</span> <span m="3418000">Do</span>
  <span m="3418090">you?</span> <span m="3420010">But</span> <span m="3420350">once</span>
  <span m="3420710">we</span> <span m="3420890">have</span> <span m="3421080">a</span>
  <span m="3421150">computer,</span> <span m="3423810">what</span> <span m="3424210">I</span>
  <span m="3424370">need</span> <span m="3424570">to</span> <span m="3424670">change</span>
  <span m="3425075">is</span> <span m="3425480">let</span> <span m="3425660">me</span>
  <span m="3425820">open</span> <span m="3426230">my</span> <span m="3426420">pendulum.m.</span>
  <span m="3430740">What</span> <span m="3430940">do</span> <span m="3431020">I</span>
  <span m="3431050">need</span> <span m="3431220">to</span> <span m="3431310">do?</span>
  <span m="3436290">I</span> <span m="3436430">just</span> <span m="3436680">need</span>
  <span m="3436850">to</span> <span m="3436960">replace</span> <span m="3437580">theta</span>
  <span m="3438330">with</span> <span m="3438540">sine</span> <span m="3438720">of</span>
  <span m="3438780">theta.</span></p><p><span m="3440890">And</span> <span m="3441440">let</span>
  <span m="3441650">me</span> <span m="3441760">do</span> <span m="3441920">this</span>
  <span m="3442140">again.</span> <span m="3443700">Midpoint.</span> <span m="3445720">I</span>
  <span m="3445800">get</span> <span m="3446590">a</span> <span m="3446710">solution</span>
  <span m="3447770">as</span> <span m="3448060">easy</span> <span m="3448450">as</span>
  <span m="3448740">I''m</span> <span m="3448910">solving</span> <span m="3449250">the</span>
  <span m="3449330">linear</span> <span m="3449620">equations.</span> <span m="3450730">And</span>
  <span m="3450810">when</span> <span m="3451000">I</span> <span m="3451250">plot</span>
  <span m="3451610">it,</span> <span m="3453870">I</span> <span m="3453980">want</span>
  <span m="3454180">to</span> <span m="3454430">plot</span> <span m="3458710">this</span>
  <span m="3459325">with</span> <span m="3459670">history.</span> <span m="3463440">Here</span>
  <span m="3463500">I</span> <span m="3463535">get</span> <span m="3463552">the</span>
  <span m="3463570">solution</span> <span m="3464000">to</span> <span m="3464100">non-linear</span>
  <span m="3464520">equation.</span> <span m="3464960">I</span> <span m="3465437">mean,</span>
  <span m="3465914">it</span> <span m="3466391">may</span> <span m="3466870">look</span>
  <span m="3467135">similar,</span> <span m="3467400">but</span> <span m="3468100">let</span>
  <span m="3468410">me</span> <span m="3468540">zoom</span> <span m="3468770">in</span>
  <span m="3469080">a</span> <span m="3469160">little</span> <span m="3469400">bit</span>
  <span m="3469570">to</span> <span m="3469680">see.</span> <span m="3471200">Oh,</span>
  <span m="3471410">man,</span> <span m="3471720">MATLAB</span> <span m="3471840">doesn''t</span>
  <span m="3471970">listen</span> <span m="3472250">to</span> <span m="3472370">me.</span></p><p><span
  m="3474240">I''m</span> <span m="3474480">going</span> <span m="3474640">to</span>
  <span m="3474730">the</span> <span m="3475010">x</span> <span m="3475370">lim,</span>
  <span m="3475780">which</span> <span m="3476080">is</span> <span m="3476190">kind</span>
  <span m="3476340">of</span> <span m="3476450">a</span> <span m="3476550">scale</span>
  <span m="3476950">to</span> <span m="3477100">x</span> <span m="3477530">limit</span>
  <span m="3479070">to</span> <span m="3479660">0</span> <span m="3479810">and</span>
  <span m="3480030">5</span> <span m="3481380">here.</span> <span m="3481800">And</span>
  <span m="3483350">well,</span> <span m="3483590">it</span> <span m="3483690">doesn''t</span>
  <span m="3483940">really</span> <span m="3484250">show</span> <span m="3484750">a</span>
  <span m="3484810">lot</span> <span m="3485100">of</span> <span m="3485220">difference,</span>
  <span m="3485610">but</span> <span m="3486000">let</span> <span m="3486410">me</span>
  <span m="3486660">change</span> <span m="3488320">the</span> <span m="3488670">initial</span>
  <span m="3489040">condition.</span> <span m="3492740">Open</span> <span m="3493660">midpoint</span>
  <span m="3494580">to</span> <span m="3495040">m.</span> <span m="3497270">Let</span>
  <span m="3497460">me</span> <span m="3497580">change</span> <span m="3497950">the</span>
  <span m="3498230">initial</span> <span m="3498300">condition</span> <span m="3498710">to</span>
  <span m="3498840">how</span> <span m="3498960">much?</span> <span m="3501140">1</span>
  <span m="3501680">is</span> <span m="3503810">like</span> <span m="3504020">60</span>
  <span m="3504480">degrees.</span></p><p><span m="3504960">AUDIENCE:</span> <span
  m="3505200">[INAUDIBLE].</span></p><p><span m="3507640">QIQI WANG:</span> <span
  m="3508130">[? Reads ?]</span> <span m="3509010">very</span> <span m="3509290">close</span>
  <span m="3509590">to</span> <span m="3509730">pi,</span> <span m="3510210">so</span>
  <span m="3510370">you</span> <span m="3510500">get</span> <span m="3510740">like--</span>
  <span m="3510970">so</span> <span m="3511240">for</span> <span m="3511510">a</span>
  <span m="3511790">let''s</span> <span m="3512010">try</span> <span m="3512320">it.</span>
  <span m="3516144">Let</span> <span m="3516622">me</span> <span m="3517100">plot</span>
  <span m="3517578">it</span> <span m="3518056">again.</span> <span m="3519970">Oh,</span>
  <span m="3520190">yeah.</span> <span m="3521010">So</span> <span m="3521620">we</span>
  <span m="3522220">get</span> <span m="3522960">[INAUDIBLE]</span> <span m="3532030">So</span>
  <span m="3532240">it</span> <span m="3532520">will</span> <span m="3532660">stay</span>
  <span m="3532800">close</span> <span m="3533055">to</span> <span m="3533310">the</span>
  <span m="3533450">top</span> <span m="3533590">for</span> <span m="3533910">a</span>
  <span m="3534377">while</span> <span m="3534844">and</span> <span m="3535311">then</span>
  <span m="3535778">drop</span> <span m="3536011">down</span> <span m="3536245">and</span>
  <span m="3536712">stay</span> <span m="3536867">at</span> <span m="3537023">[? 0
  ?]</span> <span m="3537179">for</span> <span m="3537334">a</span> <span m="3537490">while</span>
  <span m="3537646">and</span> <span m="3538113">then</span> <span m="3538580">[?
  conditions ?]</span> <span m="3539047">the</span> <span m="3539514">other</span>
  <span m="3539990">part</span> <span m="3540350">of</span> <span m="3540513">the</span>
  <span m="3540676">chart.</span> <span m="3540840">To</span> <span m="3541085">get</span>
  <span m="3541330">over</span> <span m="3541660">the</span> <span m="3541800">middle</span>
  <span m="3542190">of</span> <span m="3542385">the</span> <span m="3542580">area</span>
  <span m="3543053">[INAUDIBLE].</span></p><p><span m="3546560">So</span> <span m="3547600">you</span>
  <span m="3547700">get</span> <span m="3548010">some</span> <span m="3548150">very</span>
  <span m="3548290">nonlinear</span> <span m="3549210">behaviors</span> <span m="3549920">where</span>
  <span m="3550650">you</span> <span m="3550760">have</span> <span m="3550960">a</span>
  <span m="3551040">big</span> <span m="3551330">initial</span> <span m="3552120">[?
  areas ?]</span> <span m="3552330">as</span> <span m="3552465">easy</span> <span
  m="3552600">as</span> <span m="3552800">you''re</span> <span m="3553010">solving</span>
  <span m="3553416">a</span> <span m="3553822">linear</span> <span m="3554230">equation.</span>
  <span m="3554930">And</span> <span m="3555110">that</span> <span m="3555230">is</span>
  <span m="3555370">why</span> <span m="3555630">we</span> <span m="3555960">use</span>
  <span m="3556330">numerical</span> <span m="3556812">methods.</span> <span m="3558740">This</span>
  <span m="3558960">is</span> <span m="3559100">when</span> <span m="3559280">we</span>
  <span m="3559420">don''t</span> <span m="3559630">have</span> <span m="3560890">an</span>
  <span m="3561010">easy</span> <span m="3561400">way</span> <span m="3561610">to</span>
  <span m="3561720">get</span> <span m="3562100">analytical</span> <span m="3562450">solutions,</span>
  <span m="3563330">and</span> <span m="3563500">it</span> <span m="3563610">is</span>
  <span m="3563740">certainly</span> <span m="3564110">true</span> <span m="3564560">for</span>
  <span m="3564700">most</span> <span m="3565080">of</span> <span m="3565190">the</span>
  <span m="3565280">engineering</span> <span m="3565790">problems</span> <span m="3566250">we</span>
  <span m="3566390">are</span> <span m="3566480">dealing</span> <span m="3566830">with.</span>
  <span m="3569680">And</span> <span m="3570170">it''s</span> <span m="3570340">quite</span>
  <span m="3570540">rare</span> <span m="3570840">you</span> <span m="3570930">can</span>
  <span m="3571120">find</span> <span m="3571310">any</span> <span m="3571470">of</span>
  <span m="3571575">the</span> <span m="3571680">solutions.</span> <span m="3572170">And</span>
  <span m="3572310">most</span> <span m="3572480">of</span> <span m="3572580">the</span>
  <span m="3572720">time</span> <span m="3573040">you</span> <span m="3573160">have</span>
  <span m="3573625">to</span> <span m="3574090">use</span> <span m="3574555">numerical</span>
  <span m="3575020">solutions.</span></p><p><span m="3578370">So</span> <span m="3578510">let''s</span>
  <span m="3578710">go</span> <span m="3578840">back</span> <span m="3579150">and</span>
  <span m="3579350">start</span> <span m="3579655">to</span> <span m="3579960">try--</span>
  <span m="3581130">we</span> <span m="3581520">did</span> <span m="3581700">forward</span>
  <span m="3581870">Euler.</span> <span m="3582510">We</span> <span m="3582640">did</span>
  <span m="3583220">midpoint</span> <span m="3583570">rule.</span> <span m="3584290">Let''s</span>
  <span m="3584540">try</span> <span m="3584740">best</span> <span m="3585230">implicit</span>
  <span m="3585880">one-step</span> <span m="3586846">scheme.</span> <span m="3588290">And</span>
  <span m="3590440">I</span> <span m="3590560">think</span> <span m="3590810">I</span>
  <span m="3590870">remember</span> <span m="3591580">what</span> <span m="3591810">it</span>
  <span m="3591950">is.</span> <span m="3593480">Please</span> <span m="3593750">correct</span>
  <span m="3594090">me</span> <span m="3594270">if</span> <span m="3594420">I''m</span>
  <span m="3594630">wrong.</span> <span m="3595190">ui</span> <span m="3595520">plus</span>
  <span m="3595700">1</span> <span m="3596192">equal</span> <span m="3597176">to</span>
  <span m="3597668">ui</span> <span m="3598652">plus</span> <span m="3599144">1/2</span>
  <span m="3599640">of</span> <span m="3599830">delta</span> <span m="3599940">t</span>
  <span m="3600800">ui</span> <span m="3601270">prime</span> <span m="3601800">plus</span>
  <span m="3602240">1/2</span> <span m="3602637">of</span> <span m="3603034">delta</span>
  <span m="3603431">t</span> <span m="3603830">ui</span> <span m="3604760">plus</span>
  <span m="3605100">1</span> <span m="3605380">prime.</span></p><p><span m="3609210">This</span>
  <span m="3609560">is</span> <span m="3610390">the</span> <span m="3610520">one</span>
  <span m="3610690">we</span> <span m="3610790">just</span> <span m="3610990">derived</span>
  <span m="3611460">from</span> <span m="3613560">writing</span> <span m="3613960">down</span>
  <span m="3614180">all</span> <span m="3614410">the</span> <span m="3614550">rows,</span>
  <span m="3615040">having</span> <span m="3615340">all</span> <span m="3615510">the</span>
  <span m="3615600">columns</span> <span m="3616080">aligned</span> <span m="3616580">and</span>
  <span m="3618630">canceled</span> <span m="3619060">three</span> <span m="3619400">of</span>
  <span m="3619560">the</span> <span m="3619640">most</span> <span m="3619870">important</span>
  <span m="3620350">terms.</span> <span m="3622630">And</span> <span m="3622790">we</span>
  <span m="3622870">get</span> <span m="3623080">this.</span> <span m="3623410">We</span>
  <span m="3623540">get</span> <span m="3623790">x</span> <span m="3624240">being</span>
  <span m="3624500">1,</span> <span m="3625010">y</span> <span m="3625310">being</span>
  <span m="3625830">1/2</span> <span m="3626320">L</span> <span m="3626510">of</span>
  <span m="3626730">t,</span> <span m="3627122">z</span> <span m="3627514">being</span>
  <span m="3627906">1/2</span> <span m="3628004">L</span> <span m="3628103">of</span>
  <span m="3628201">t.</span></p><p><span m="3630420">Now,</span> <span m="3630700">let''s</span>
  <span m="3630930">try</span> <span m="3631180">this,</span> <span m="3632190">and</span>
  <span m="3633240">for</span> <span m="3633610">this,</span> <span m="3634100">I</span>
  <span m="3634330">have</span> <span m="3634570">to</span> <span m="3634730">say</span>
  <span m="3635190">for</span> <span m="3635400">now</span> <span m="3635900">I</span>
  <span m="3636040">am</span> <span m="3636210">going</span> <span m="3636440">to</span>
  <span m="3636810">go</span> <span m="3636990">back</span> <span m="3638140">cowardly</span>
  <span m="3638540">to</span> <span m="3638940">a</span> <span m="3639405">linear</span>
  <span m="3639870">equation.</span> <span m="3642150">And</span> <span m="3645390">we</span>
  <span m="3645570">are</span> <span m="3645650">going</span> <span m="3645770">to</span>
  <span m="3645830">be</span> <span m="3645910">talking</span> <span m="3646240">about</span>
  <span m="3646500">how</span> <span m="3646670">to</span> <span m="3646780">do</span>
  <span m="3646960">the</span> <span m="3647060">same</span> <span m="3647960">with</span>
  <span m="3651850">nonlinear</span> <span m="3652320">equations.</span> <span m="3653526">I</span>
  <span m="3653930">think</span> <span m="3655000">three</span> <span m="3655310">lectures</span>
  <span m="3655660">from</span> <span m="3655940">now</span> <span m="3656370">or</span>
  <span m="3656822">something</span> <span m="3657048">like</span> <span m="3657274">that,</span>
  <span m="3658630">we</span> <span m="3658790">are</span> <span m="3658860">going</span>
  <span m="3658980">to</span> <span m="3659040">be</span> <span m="3659290">using</span>
  <span m="3659580">something</span> <span m="3659990">called</span> <span m="3660270">the</span>
  <span m="3660370">Newton-Raphson.</span> <span m="3661710">But</span> <span m="3661890">for</span>
  <span m="3662200">now,</span> <span m="3663960">let''s</span> <span m="3664170">stick</span>
  <span m="3664740">to</span> <span m="3665040">linear</span> <span m="3665790">equations.</span></p><p><span
  m="3669350">What</span> <span m="3669570">we</span> <span m="3669730">have</span>
  <span m="3670180">is</span> <span m="3670480">we</span> <span m="3670720">have</span>
  <span m="3672290">u</span> <span m="3674060">prime</span> <span m="3676860">is</span>
  <span m="3677343">equal</span> <span m="3677826">to</span> <span m="3681250">something</span>
  <span m="3681960">times</span> <span m="3682410">ui.</span> <span m="3683240">ui</span>
  <span m="3683510">is</span> <span m="3683940">2</span> <span m="3684160">by</span>
  <span m="3684330">1</span> <span m="3684590">vector.</span> <span m="3687930">ui</span>
  <span m="3688870">prime</span> <span m="3690720">is</span> <span m="3691150">going</span>
  <span m="3691330">to</span> <span m="3691430">be</span> <span m="3692380">1,</span>
  <span m="3693650">0,</span> <span m="3694690">0,</span> <span m="3695910">minus</span>
  <span m="3697946">g</span> <span m="3698810">over</span> <span m="3699230">L</span>
  <span m="3700510">times</span> <span m="3700750">ui.</span> <span m="3703910">Why</span>
  <span m="3704470">is</span> <span m="3704720">that</span> <span m="3704930">true?</span>
  <span m="3705940">You</span> <span m="3706050">just</span> <span m="3706290">need</span>
  <span m="3706620">to</span> <span m="3706710">look</span> <span m="3706950">at</span>
  <span m="3707030">the</span> <span m="3707100">code.</span> <span m="3709000">du</span>
  <span m="3709140">dt</span> <span m="3710330">equal</span> <span m="3710740">to</span>
  <span m="3710860">theta</span> <span m="3711220">dot,</span> <span m="3711600">which</span>
  <span m="3711800">is</span> <span m="3711920">u2.</span> <span m="3714130">And</span>
  <span m="3714790">theta</span> <span m="3715140">d</span> <span m="3715460">dot,</span>
  <span m="3716330">which</span> <span m="3716690">is</span> <span m="3717060">u1</span>
  <span m="3718080">times</span> <span m="3718900">minus</span> <span m="3719390">g</span>
  <span m="3719640">over</span> <span m="3719860">L.</span></p><p><span m="3724880">This</span>
  <span m="3725150">is</span> <span m="3725270">the</span> <span m="3725390">same</span>
  <span m="3725730">as</span> <span m="3725970">saying</span> <span m="3726850">du</span>
  <span m="3727090">dt</span> <span m="3728030">equal</span> <span m="3728320">to</span>
  <span m="3729510">u2,</span> <span m="3731460">u1</span> <span m="3732740">times</span>
  <span m="3733660">minus</span> <span m="3735350">g</span> <span m="3736530">over</span>
  <span m="3737220">L.</span> <span m="3739130">I</span> <span m="3739550">can</span>
  <span m="3739720">basically</span> <span m="3740100">rephrase</span> <span m="3740650">all</span>
  <span m="3740870">of</span> <span m="3740990">this</span> <span m="3741250">by</span>
  <span m="3742100">this.</span> <span m="3748450">Or</span> <span m="3748670">all</span>
  <span m="3748840">the</span> <span m="3748920">stuff</span> <span m="3749740">I</span>
  <span m="3749830">just</span> <span m="3749990">commented</span> <span m="3750430">out,</span>
  <span m="3750710">made</span> <span m="3750980">green</span> <span m="3751460">is</span>
  <span m="3751940">just</span> <span m="3752430">this.</span> <span m="3755870">Agreed?</span></p><p><span
  m="3758120">And</span> <span m="3758390">this</span> <span m="3758860">is</span>
  <span m="3759080">just</span> <span m="3759450">saying</span> <span m="3759840">that</span>
  <span m="3763104">du</span> <span m="3763600">dt</span> <span m="3763800">is</span>
  <span m="3763990">equal</span> <span m="3764340">to</span> <span m="3764620">this</span>
  <span m="3764860">matrix</span> <span m="3766010">times</span> <span m="3766797">u.</span>
  <span m="3767960">And</span> <span m="3768190">this</span> <span m="3768330">is</span>
  <span m="3768470">going</span> <span m="3768720">back</span> <span m="3768930">and</span>
  <span m="3769080">forth</span> <span m="3769280">between</span> <span m="3769550">the</span>
  <span m="3769620">formula</span> <span m="3770540">and</span> <span m="3770710">the</span>
  <span m="3770780">code,</span> <span m="3772450">the</span> <span m="3772720">formula</span>
  <span m="3773490">and</span> <span m="3773660">the</span> <span m="3773770">code.</span>
  <span m="3775970">Doing</span> <span m="3776260">this</span> <span m="3776510">is</span>
  <span m="3776670">the</span> <span m="3776750">same</span> <span m="3777050">as</span>
  <span m="3777230">a</span> <span m="3777320">matrix</span> <span m="3778290">multiplication.</span></p><p><span
  m="3781680">Now,</span> <span m="3784980">the</span> <span m="3785110">same</span>
  <span m="3785380">thing</span> <span m="3785580">happens</span> <span m="3785920">for</span>
  <span m="3786140">ui</span> <span m="3786410">plus</span> <span m="3786690">1</span>
  <span m="3787190">prime.</span> <span m="3795762">Agreed?</span> <span m="3798570">So</span>
  <span m="3798760">now</span> <span m="3799520">if</span> <span m="3799780">you</span>
  <span m="3799940">plot</span> <span m="3800500">this</span> <span m="3800740">into</span>
  <span m="3800970">the</span> <span m="3801080">equation,</span> <span m="3803120">we</span>
  <span m="3803590">removed</span> <span m="3804240">all</span> <span m="3804630">the</span>
  <span m="3804760">primes</span> <span m="3805330">and</span> <span m="3805620">replaced</span>
  <span m="3806360">all</span> <span m="3806510">the</span> <span m="3806740">primes</span>
  <span m="3807280">with</span> <span m="3808200">ui</span> <span m="3808710">and</span>
  <span m="3808830">ui</span> <span m="3809010">plus</span> <span m="3809110">1.</span>
  <span m="3810770">We</span> <span m="3810930">can</span> <span m="3811060">actually</span>
  <span m="3812030">collect</span> <span m="3812460">the</span> <span m="3812540">terms.</span>
  <span m="3813360">We</span> <span m="3813540">can</span> <span m="3813770">say</span>
  <span m="3815810">ui</span> <span m="3816990">plus</span> <span m="3817320">1</span>
  <span m="3818710">equal</span> <span m="3819190">to--</span> <span m="3821466">I''m</span>
  <span m="3821890">going</span> <span m="3822240">to</span> <span m="3822540">use</span>
  <span m="3822820">ui</span> <span m="3823310">plus</span> <span m="3824290">1/2</span>
  <span m="3824780">delta</span> <span m="3824960">t</span> <span m="3825460">times</span>
  <span m="3825760">ui</span> <span m="3826050">prime,</span> <span m="3826580">which</span>
  <span m="3826740">I</span> <span m="3827460">am</span> <span m="3827610">going</span>
  <span m="3827750">to</span> <span m="3827860">write</span> <span m="3828080">like</span>
  <span m="3828310">this</span> <span m="3832810">plus--</span> <span m="3835640">and</span>
  <span m="3835870">switching</span> <span m="3836270">to</span> <span m="3836440">red,</span>
  <span m="3836820">and</span> <span m="3837060">you''re</span> <span m="3837230">going</span>
  <span m="3837285">to</span> <span m="3837340">see</span> <span m="3837540">why</span>
  <span m="3837800">I</span> <span m="3837850">am</span> <span m="3837980">doing</span>
  <span m="3838280">this--</span> <span m="3843390">ui</span> <span m="3844800">plus</span>
  <span m="3845090">1.</span> <span m="3847910">This</span> <span m="3848090">is</span>
  <span m="3848210">really</span> <span m="3848380">important.</span> <span m="3848860">It</span>
  <span m="3849010">is</span> <span m="3849150">ui</span> <span m="3849410">plus</span>
  <span m="3849800">1.</span></p><p><span m="3851240">Why</span> <span m="3851860">am</span>
  <span m="3852010">I</span> <span m="3852080">using</span> <span m="3852360">different</span>
  <span m="3852610">colors?</span> <span m="3856050">What</span> <span m="3856310">is</span>
  <span m="3856470">the</span> <span m="3856570">difference</span> <span m="3856990">between</span>
  <span m="3857290">the</span> <span m="3857360">blue</span> <span m="3857620">terms</span>
  <span m="3857960">and</span> <span m="3858050">the</span> <span m="3858130">red</span>
  <span m="3858330">terms?</span></p><p><span m="3858800">AUDIENCE:</span> <span m="3859270">[INAUDIBLE].</span></p><p><span
  m="3860210">QIQI WANG:</span> <span m="3860680">Yes.</span></p><p><span m="3861922">AUDIENCE:</span>
  <span m="3862403">[INAUDIBLE].</span></p><p><span m="3863846">QIQI WANG:</span>
  <span m="3864330">The</span> <span m="3864450">current</span> <span m="3864825">step</span>
  <span m="3865200">versus</span> <span m="3865530">next</span> <span m="3865790">step.</span>
  <span m="3866630">The</span> <span m="3866800">known</span> <span m="3867430">versus</span>
  <span m="3867930">unknown.</span> <span m="3870930">When</span> <span m="3871200">I</span>
  <span m="3871360">have</span> <span m="3871760">the</span> <span m="3871910">i-th</span>
  <span m="3872090">step</span> <span m="3872430">when</span> <span m="3872620">I</span>
  <span m="3872690">want</span> <span m="3872940">to</span> <span m="3873030">go</span>
  <span m="3873350">to</span> <span m="3873460">the</span> <span m="3873550">next</span>
  <span m="3873820">step,</span> <span m="3874080">ui</span> <span m="3874530">plus</span>
  <span m="3874855">1</span> <span m="3875180">is</span> <span m="3875340">unknown.</span>
  <span m="3876300">ui</span> <span m="3876550">is</span> <span m="3876820">known.</span></p><p><span
  m="3878820">All</span> <span m="3878950">right.</span> <span m="3879170">So</span>
  <span m="3879540">what</span> <span m="3879760">I</span> <span m="3879850">can</span>
  <span m="3880090">do</span> <span m="3880240">is</span> <span m="3880480">I</span>
  <span m="3880590">can</span> <span m="3880870">rearrange</span> <span m="3891460">and</span>
  <span m="3891670">say</span> <span m="3894080">that</span> <span m="3895720">something</span>
  <span m="3896055">times</span> <span m="3896760">ui</span> <span m="3897190">plus</span>
  <span m="3897470">1</span> <span m="3897800">is</span> <span m="3898060">equal</span>
  <span m="3898500">to</span> <span m="3899420">something</span> <span m="3899903">times</span>
  <span m="3900386">ui.</span> <span m="3902801">Can</span> <span m="3903770">somebody</span>
  <span m="3904140">tell</span> <span m="3904340">me</span> <span m="3904470">what</span>
  <span m="3904750">these</span> <span m="3904970">two</span> <span m="3905140">matrices</span>
  <span m="3905700">are?</span> <span m="3905940">If</span> <span m="3906090">I</span>
  <span m="3906210">move</span> <span m="3906660">all</span> <span m="3906840">the</span>
  <span m="3906920">red</span> <span m="3907195">terms</span> <span m="3907470">to</span>
  <span m="3907620">the</span> <span m="3907720">left</span> <span m="3908510">and</span>
  <span m="3909170">let</span> <span m="3909730">me</span> <span m="3909830">actually</span>
  <span m="3910300">write</span> <span m="3910600">it</span> <span m="3910975">as</span>
  <span m="3911270">blue</span> <span m="3911590">because</span> <span m="3913084">[?
  there-- ?]</span> <span m="3914580">and</span> <span m="3915976">all</span> <span
  m="3916390">the</span> <span m="3916460">blue</span> <span m="3916700">terms</span>
  <span m="3916970">to</span> <span m="3917070">the</span> <span m="3917180">right,</span>
  <span m="3917810">what</span> <span m="3918010">do</span> <span m="3918100">I</span>
  <span m="3918190">get?</span> <span m="3919160">What</span> <span m="3919430">is</span>
  <span m="3919600">the</span> <span m="3919710">red</span> <span m="3919920">matrix?</span>
  <span m="3920390">What</span> <span m="3920560">is</span> <span m="3920710">the</span>
  <span m="3920790">blue</span> <span m="3920960">matrix?</span></p><p><span m="3935025">The</span>
  <span m="3935510">red</span> <span m="3935890">matrix.</span></p><p><span m="3936480">AUDIENCE:</span>
  <span m="3936882">[INAUDIBLE]</span></p><p><span m="3938088">QIQI WANG:</span> <span
  m="3938490">1.</span></p><p><span m="3939884">AUDIENCE:</span> <span m="3940381">[INAUDIBLE].</span></p><p><span
  m="3964237">QIQI WANG:</span> <span m="3964760">Great.</span> <span m="3965820">The</span>
  <span m="3966000">two</span> <span m="3966310">1''s</span> <span m="3966800">are</span>
  <span m="3967200">because</span> <span m="3968130">ui</span> <span m="3969650">can</span>
  <span m="3970060">be</span> <span m="3970180">represented</span> <span m="3970950">as</span>
  <span m="3971250">identity</span> <span m="3971860">matrix</span> <span m="3973250">times</span>
  <span m="3973340">ui.</span> <span m="3974060">Identity</span> <span m="3974490">matrix</span>
  <span m="3974705">is</span> <span m="3974920">1,</span> <span m="3975230">0,</span>
  <span m="3975580">0,</span> <span m="3975920">1.</span> <span m="3977890">Now,</span>
  <span m="3978180">these</span> <span m="3978470">two</span> <span m="3978670">terms</span>
  <span m="3979030">are</span> <span m="3979140">basically</span> <span m="3979640">this</span>
  <span m="3979840">matrix</span> <span m="3980236">times</span> <span m="3981030">delta</span>
  <span m="3981220">t</span> <span m="3981330">over</span> <span m="3981620">2.</span>
  <span m="3986060">Any</span> <span m="3986230">questions</span> <span m="3986600">about</span>
  <span m="3986820">this</span> <span m="3986990">matrix?</span> <span m="3987580">I</span>
  <span m="3987670">mean,</span> <span m="3987820">this</span> <span m="3987980">is</span>
  <span m="3988080">just</span> <span m="3988170">combining</span> <span m="3988760">these</span>
  <span m="3988950">two</span> <span m="3989423">terms.</span></p><p><span m="3993680">How</span>
  <span m="3993840">about</span> <span m="3994030">the</span> <span m="3994150">red</span>
  <span m="3994420">one?</span></p><p><span m="3997560">AUDIENCE:</span> <span m="3998050">[INAUDIBLE].</span></p><p><span
  m="4000928">QIQI WANG:</span> <span m="4001382">1.</span></p><p><span m="4002290">AUDIENCE:</span>
  <span m="4002744">[INAUDIBLE]</span></p><p><span m="4003652">QIQI WANG:</span> <span
  m="4004110">Negative</span> <span m="4004980">delta</span> <span m="4005120">t</span>
  <span m="4005380">over</span> <span m="4005620">2,</span> <span m="4005840">yeah.</span>
  <span m="4006580">Exactly.</span> <span m="4007340">It</span> <span m="4007410">is</span>
  <span m="4007550">basically</span> <span m="4007960">taking</span> <span m="4008260">this</span>
  <span m="4008440">matrix</span> <span m="4008920">takes</span> <span m="4009190">the</span>
  <span m="4009330">negative</span> <span m="4009870">sign.</span> <span m="4010690">And</span>
  <span m="4010970">here?</span></p><p><span m="4011340">AUDIENCE:</span> <span m="4011810">[INAUDIBLE].</span></p><p><span
  m="4015570">QIQI WANG:</span> <span m="4016040">1.</span> <span m="4016520">Great.</span>
  <span m="4017740">So</span> <span m="4018230">to</span> <span m="4018360">implement</span>
  <span m="4019010">the</span> <span m="4019110">scheme,</span> <span m="4020340">we</span>
  <span m="4020780">need</span> <span m="4021220">this.</span> <span m="4022100">We</span>
  <span m="4022540">need</span> <span m="4022780">to</span> <span m="4023340">basically</span>
  <span m="4024910">multiply</span> <span m="4025380">this</span> <span m="4025570">matrix</span>
  <span m="4025970">with</span> <span m="4026210">ui</span> <span m="4026870">and</span>
  <span m="4027410">invert</span> <span m="4028100">this</span> <span m="4028350">matrix.</span>
  <span m="4029430">All</span> <span m="4029930">right.</span> <span m="4031450">Clear?</span>
  <span m="4033680">I''m</span> <span m="4034030">going</span> <span m="4034240">to</span>
  <span m="4034610">make</span> <span m="4034870">another</span> <span m="4035280">file.</span>
  <span m="4037990">I''m</span> <span m="4038620">going</span> <span m="4038850">to</span>
  <span m="4039050">call</span> <span m="4039430">it--</span> <span m="4043230">this</span>
  <span m="4044170">scheme</span> <span m="4044980">by</span> <span m="4045130">the</span>
  <span m="4045230">way,</span> <span m="4046330">the</span> <span m="4046910">best</span>
  <span m="4047590">one</span> <span m="4047910">step</span> <span m="4048280">implicit</span>
  <span m="4048770">schemes</span> <span m="4049140">you</span> <span m="4049260">guys</span>
  <span m="4049530">invented</span> <span m="4049960">is</span> <span m="4050170">called</span>
  <span m="4050470">the</span> <span m="4050620">trapezoidal</span> <span m="4050940">rule.</span>
  <span m="4056310">Not</span> <span m="4056550">tx,</span> <span m="4056860">t.</span>
  <span m="4057460">Sorry--</span> <span m="4060285">dot</span> <span m="4061740">m.</span>
  <span m="4063680">Yes.</span></p><p><span m="4073260">Oh,</span> <span m="4073590">I</span>
  <span m="4073710">should</span> <span m="4074000">be</span> <span m="4074460">copying.</span>
  <span m="4082560">this.</span> <span m="4084410">Trapezoidal</span> <span m="4085130">rule</span>
  <span m="4085350">is</span> <span m="4085490">a</span> <span m="4085590">one-step</span>
  <span m="4086280">scheme,</span> <span m="4086865">is</span> <span m="4087140">a</span>
  <span m="4087540">single-step</span> <span m="4088010">scheme,</span> <span m="4088220">so</span>
  <span m="4088390">I</span> <span m="4088560">don''t</span> <span m="4088790">need</span>
  <span m="4088910">to</span> <span m="4089100">do</span> <span m="4089240">any</span>
  <span m="4089480">forward</span> <span m="4089710">Euler</span> <span m="4090000">or</span>
  <span m="4090200">anything</span> <span m="4090510">like</span> <span m="4090740">that.</span>
  <span m="4092050">All</span> <span m="4092250">right.</span> <span m="4093080">And</span>
  <span m="4093470">I''m</span> <span m="4093610">going</span> <span m="4093750">to</span>
  <span m="4093950">be</span> <span m="4094620">doing</span> <span m="4094980">t</span>
  <span m="4095285">equal</span> <span m="4095590">to</span> <span m="4095980">0</span>
  <span m="4096250">to</span> <span m="4096520">dt</span> <span m="4096970">equal</span>
  <span m="4097420">to</span> <span m="4097870">t.</span> <span m="4098320">[? I''m
  ?]</span> <span m="4098770">going</span> <span m="4099220">to</span> <span m="4099445">type</span>
  <span m="4099670">m</span> <span m="4099899">first.</span></p><p><span m="4102680">What</span>
  <span m="4102950">I''m</span> <span m="4103080">going</span> <span m="4103229">to</span>
  <span m="4103300">do</span> <span m="4103580">is</span> <span m="4103939">I''m</span>
  <span m="4104100">going</span> <span m="4104229">to</span> <span m="4104580">talk</span>
  <span m="4104790">to</span> <span m="4104870">construct</span> <span m="4105590">two</span>
  <span m="4105790">matrices.</span> <span m="4107460">One</span> <span m="4107770">matrix,</span>
  <span m="4108270">I</span> <span m="4108439">call</span> <span m="4108770">it</span>
  <span m="4110120">A.</span> <span m="4113220">Let</span> <span m="4113710">me</span>
  <span m="4113790">just</span> <span m="4113990">call</span> <span m="4114200">it</span>
  <span m="4114310">red</span> <span m="4114649">matrix</span> <span m="4118290">and</span>
  <span m="4118560">the</span> <span m="4118630">blue</span> <span m="4118880">matrix.</span>
  <span m="4124290">The</span> <span m="4124520">red</span> <span m="4124810">matrix</span>
  <span m="4126149">is</span> <span m="4126920">1</span> <span m="4127678">minus</span>
  <span m="4128057">delta</span> <span m="4128439">t,</span> <span m="4128550">delta</span>
  <span m="4128779">t</span> <span m="4129529">over</span> <span m="4129800">2--</span>
  <span m="4131479">I''m</span> <span m="4131740">just</span> <span m="4131920">going</span>
  <span m="4132010">to</span> <span m="4132452">type</span> <span m="4132894">it.</span>
  <span m="4133779">1</span> <span m="4134080">delta</span> <span m="4134154">t</span>
  <span m="4134229">over</span> <span m="4134470">2,</span> <span m="4134649">delta</span>
  <span m="4135066">t</span> <span m="4136319">over</span> <span m="4136630">2.</span>
  <span m="4138600">I</span> <span m="4138750">think</span> <span m="4139250">that</span>
  <span m="4139409">I</span> <span m="4139569">get</span> <span m="4139740">a</span>
  <span m="4139779">minus</span> <span m="4140140">here.</span> <span m="4140390">That</span>
  <span m="4140510">will</span> <span m="4140630">be</span> <span m="4140740">over</span>
  <span m="4141040">2</span> <span m="4141490">times</span> <span m="4142314">g</span>
  <span m="4143304">over</span> <span m="4143799">L.</span> <span m="4146279">and</span>
  <span m="4147475">1.</span></p><p><span m="4149260">The</span> <span m="4149399">blue</span>
  <span m="4149720">matrix</span> <span m="4150300">is</span> <span m="4150740">roughly</span>
  <span m="4151149">the</span> <span m="4151279">same,</span> <span m="4152439">but</span>
  <span m="4153520">there</span> <span m="4153700">is</span> <span m="4153800">a</span>
  <span m="4153840">minus</span> <span m="4154170">sign</span> <span m="4154460">here,</span>
  <span m="4154790">and</span> <span m="4155010">there</span> <span m="4155109">is</span>
  <span m="4155210">a</span> <span m="4155350">plus</span> <span m="4155720">sign</span>
  <span m="4156138">here.</span> <span m="4157810">All</span> <span m="4158229">right.</span>
  <span m="4164569">Then</span> <span m="4165109">what</span> <span m="4165380">do</span>
  <span m="4165500">I</span> <span m="4165600">do</span> <span m="4165810">next?</span>
  <span m="4171000">u</span> <span m="4171239">is</span> <span m="4171479">equal</span>
  <span m="4172170">to</span> <span m="4173290">what?</span></p><p><span m="4177290">AUDIENCE:</span>
  <span m="4177790">[INAUDIBLE].</span></p><p><span m="4180526">QIQI WANG:</span>
  <span m="4180960">Inverse</span> <span m="4181660">of</span> <span m="4181810">the</span>
  <span m="4181939">red</span> <span m="4182240">matrix</span> <span m="4187923">times</span>
  <span m="4188750">blue</span> <span m="4189399">matrix</span> <span m="4190700">times</span>
  <span m="4191720">u0.</span> <span m="4193149">So</span> <span m="4193260">actually</span>
  <span m="4193630">here</span> <span m="4193880">I</span> <span m="4193970">need</span>
  <span m="4194140">to</span> <span m="4194220">do</span> <span m="4194440">u0</span>
  <span m="4195340">transpose</span> <span m="4195890">because</span> <span m="4196280">u0</span>
  <span m="4196430">is</span> <span m="4196950">a</span> <span m="4197150">row</span>
  <span m="4197410">matrix.</span> <span m="4197900">I</span> <span m="4197980">need</span>
  <span m="4198160">to</span> <span m="4198260">make</span> <span m="4198530">it</span>
  <span m="4198650">a</span> <span m="4198770">column</span> <span m="4199050">matrix,</span>
  <span m="4200280">and</span> <span m="4203160">the</span> <span m="4203260">whole</span>
  <span m="4203470">thing</span> <span m="4203810">has</span> <span m="4204040">to</span>
  <span m="4204210">be</span> <span m="4204640">transposed</span> <span m="4205240">again.</span>
  <span m="4208650">All</span> <span m="4208800">right.</span> <span m="4209520">And</span>
  <span m="4210540">I''m</span> <span m="4210710">going</span> <span m="4210860">to</span>
  <span m="4210940">be</span> <span m="4211190">doing</span> <span m="4211700">history</span>
  <span m="4212300">is</span> <span m="4212750">equal</span> <span m="4213244">to</span>
  <span m="4213738">history</span> <span m="4215220">is</span> <span m="4215714">0</span>
  <span m="4217196">and</span> <span m="4217690">u0</span> <span m="4218184">equal
  to</span> <span m="4218678">[? u. ?]</span></p><p><span m="4223620">Is</span> <span
  m="4223960">it</span> <span m="4224050">clear</span> <span m="4224330">what</span>
  <span m="4224520">I</span> <span m="4224610">did?</span> <span m="4228130">Anybody</span>
  <span m="4228660">have</span> <span m="4228900">any</span> <span m="4229160">comments</span>
  <span m="4229690">on</span> <span m="4229860">this?</span> <span m="4230240">Is</span>
  <span m="4230520">it</span> <span m="4230770">a</span> <span m="4231160">good</span>
  <span m="4231380">way</span> <span m="4231580">of</span> <span m="4231780">doing</span>
  <span m="4232010">matrix</span> <span m="4232690">inverse?</span></p><p><span m="4234073">AUDIENCE:</span>
  <span m="4234534">[INAUDIBLE].</span></p><p><span m="4236378">QIQI WANG:</span>
  <span m="4236840">Yes.</span> <span m="4237210">u</span> <span m="4237530">is</span>
  <span m="4237700">ui</span> <span m="4237880">plus</span> <span m="4238280">1.</span></p><p><span
  m="4239444">AUDIENCE:</span> <span m="4239921">[INAUDIBLE].</span></p><p><span m="4244900">QIQI
  WANG:</span> <span m="4245370">Yes.</span></p><p><span m="4246654">AUDIENCE:</span>
  <span m="4247126">[INAUDIBLE].</span></p><p><span m="4252790">QIQI WANG:</span>
  <span m="4253270">Good</span> <span m="4253580">point.</span></p><p><span m="4254080">AUDIENCE:</span>
  <span m="4254580">[INAUDIBLE].</span></p><p><span m="4259890">QIQI WANG:</span>
  <span m="4260380">Inverse</span> <span m="4261000">red</span> <span m="4262210">matrix</span>
  <span m="4262500">is</span> <span m="4262790">equal</span> <span m="4263237">to</span>
  <span m="4263684">inverse</span> <span m="4264131">red</span> <span m="4264580">matrix.</span></p><p><span
  m="4266580">AUDIENCE:</span> <span m="4267080">[INAUDIBLE].</span></p><p><span m="4271020">QIQI
  WANG:</span> <span m="4271430">Sure.</span> <span m="4271680">I</span> <span m="4271850">can</span>
  <span m="4272010">also</span> <span m="4272320">combine</span> <span m="4272720">blue</span>
  <span m="4273210">matrix.</span></p><p><span m="4273480">AUDIENCE:</span> <span
  m="4273970">[INAUDIBLE].</span></p><p><span m="4274950">QIQI WANG:</span> <span
  m="4275440">Sure.</span> <span m="4275920">A</span> <span m="4276190">good</span>
  <span m="4276420">suggestion.</span> <span m="4282370">I''m</span> <span m="4282530">just</span>
  <span m="4282750">going</span> <span m="4282900">to</span> <span m="4282980">be</span>
  <span m="4283300">u</span> <span m="4283797">equal</span> <span m="4284294">to</span>
  <span m="4284791">a</span> <span m="4285540">times--</span> <span m="4287590">all</span>
  <span m="4288040">right.</span> <span m="4288630">And</span> <span m="4288880">let</span>
  <span m="4289040">me</span> <span m="4289150">actually</span> <span m="4289550">make</span>
  <span m="4289850">u0</span> <span m="4291140">a</span> <span m="4291270">column</span>
  <span m="4291620">matrix</span> <span m="4292140">by</span> <span m="4292610">replacing</span>
  <span m="4293250">this</span> <span m="4293490">with</span> <span m="4293700">this.</span>
  <span m="4294190">All</span> <span m="4294420">right.</span> <span m="4295510">So</span>
  <span m="4295670">I</span> <span m="4295790">don''t</span> <span m="4296060">need</span>
  <span m="4296240">to</span> <span m="4296340">do</span> <span m="4296610">all</span>
  <span m="4296810">of</span> <span m="4296950">this.</span> <span m="4299790">Here,</span>
  <span m="4300150">instead</span> <span m="4300560">of</span> <span m="4301000">when</span>
  <span m="4301240">I</span> <span m="4301340">recall</span> <span m="4301660">the</span>
  <span m="4301750">history,</span> <span m="4302220">I</span> <span m="4302620">transpose</span>
  <span m="4303070">it.</span> <span m="4304870">Great.</span> <span m="4305370">Let''s</span>
  <span m="4305580">see</span> <span m="4305810">how</span> <span m="4306520">it</span>
  <span m="4306600">works.</span></p><p><span m="4308386">Trapezoidal.</span> <span
  m="4316260">Yeah.</span> <span m="4319100">Let''s</span> <span m="4319290">plot</span>
  <span m="4319752">this</span> <span m="4320214">again.</span> <span m="4322524">It</span>
  <span m="4322990">works</span> <span m="4323280">perfectly.</span> <span m="4324666">All</span>
  <span m="4325110">right.</span> <span m="4326300">So</span> <span m="4326620">good</span>
  <span m="4326840">job,</span> <span m="4327070">guys.</span> <span m="4328210">The</span>
  <span m="4328420">scheme</span> <span m="4328710">you</span> <span m="4328840">came</span>
  <span m="4329130">up</span> <span m="4329330">with</span> <span m="4329670">works.</span></p><p><span
  m="4331790">That''s</span> <span m="4333730">it</span> <span m="4334290">for</span>
  <span m="4334530">today.</span> <span m="4335260">And</span> <span m="4337430">so</span>
  <span m="4337590">next</span> <span m="4337870">class,</span> <span m="4338360">what</span>
  <span m="4338520">I</span> <span m="4338590">want</span> <span m="4338770">to</span>
  <span m="4338840">do</span> <span m="4339030">is</span> <span m="4339460">bring</span>
  <span m="4339865">your</span> <span m="4340067">own</span> <span m="4340270">computer</span>
  <span m="4340675">because</span> <span m="4340877">we''re</span> <span m="4341080">going</span>
  <span m="4341200">to</span> <span m="4341260">be</span> <span m="4341360">doing</span>
  <span m="4341710">something--</span> <span m="4343680">next</span> <span m="4344020">class,</span>
  <span m="4344730">not</span> <span m="4346920">I''m</span> <span m="4347250">going</span>
  <span m="4347390">to</span> <span m="4347460">code</span> <span m="4347750">up</span>
  <span m="4348150">things</span> <span m="4348400">like</span> <span m="4348610">this.</span>
  <span m="4349430">Instead</span> <span m="4350070">I''m</span> <span m="4350300">going</span>
  <span m="4350460">to</span> <span m="4350560">ask</span> <span m="4350850">you</span>
  <span m="4351850">to</span> <span m="4351980">code</span> <span m="4352300">up</span>
  <span m="4353120">something</span> <span m="4353420">like</span> <span m="4353640">this,</span>
  <span m="4355050">and</span> <span m="4355220">you</span> <span m="4355380">are</span>
  <span m="4355470">going</span> <span m="4355640">to</span> <span m="4356330">be</span>
  <span m="4356400">working</span> <span m="4356820">class</span> <span m="4357320">and</span>
  <span m="4359480">hopefully,</span> <span m="4360070">show</span> <span m="4360270">things</span>
  <span m="4360510">on</span> <span m="4360650">this</span> <span m="4360950">screen.</span></p>'
type: course
uid: 48c8ddc2d7fc1355559c6992247518ef

---
None