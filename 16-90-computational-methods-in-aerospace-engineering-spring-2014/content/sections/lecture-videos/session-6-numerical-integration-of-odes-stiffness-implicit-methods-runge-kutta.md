---
about_this_resource_text: <p><strong>Description:</strong> This video begins with
  questions from the students. These are followed by a discussion of stiffness, explicit
  and implicit schemes using an in-class example. Finally, the video introduces Runge-Kutta
  methods.</p> <p><strong>Instructor:</strong> Qiqi Wang</p><p>The recording quality
  of this video is the best available from the source.</p>
course_id: 16-90-computational-methods-in-aerospace-engineering-spring-2014
embedded_media:
- id: Video-YouTube-Stream
  media_location: 8ulQDwKTBOc
  parent_uid: 947c6f55aad148935a11bb3b8680890e
  title: Video-YouTube-Stream
  type: Video
  uid: c98094def58203a585253d86eb47ffd3
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/8ulQDwKTBOc/default.jpg
  parent_uid: 947c6f55aad148935a11bb3b8680890e
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 7e701991bfcfe8144e67769e6524e61b
- id: 3Play-3PlayYouTubeid-MP4
  media_location: 8ulQDwKTBOc
  parent_uid: 947c6f55aad148935a11bb3b8680890e
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: df6e9e2674cd39179d78597960d03989
- id: 8ulQDwKTBOc.srt
  parent_uid: 947c6f55aad148935a11bb3b8680890e
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-6-numerical-integration-of-odes-stiffness-implicit-methods-runge-kutta/8ulQDwKTBOc.srt
  title: 3play caption file
  type: null
  uid: 21a63b1dfcbf2ddc3e46e69c0b71d10d
- id: 8ulQDwKTBOc.pdf
  parent_uid: 947c6f55aad148935a11bb3b8680890e
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-6-numerical-integration-of-odes-stiffness-implicit-methods-runge-kutta/8ulQDwKTBOc.pdf
  title: 3play pdf file
  type: null
  uid: 77913edf990d6634eda1ac5ac6b7e3f7
- id: Caption-3Play YouTube id-SRT
  parent_uid: 947c6f55aad148935a11bb3b8680890e
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 0b01d0bdae127f31c94ef26fe85c4811
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 947c6f55aad148935a11bb3b8680890e
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 7158ca61b774637d249cbe59b7baec2a
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT16.90S14/MIT16_90S14_L06_300k.mp4
  parent_uid: 947c6f55aad148935a11bb3b8680890e
  title: Video-Internet Archive-MP4
  type: Video
  uid: db57b4d47a3412c84bd74dd61e2256af
inline_embed_id: 47072343session6:numericalintegrationofodes:stiffness,implicitmethods,runge-kutta91250820
layout: video
order_index: null
parent_uid: 809ebf7c44bfb36e8786306747d7e32f
related_resources_text: ''
short_url: session-6-numerical-integration-of-odes-stiffness-implicit-methods-runge-kutta
technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-6-numerical-integration-of-odes-stiffness-implicit-methods-runge-kutta
template_type: Tabbed
title: 'Session 6: Numerical Integration of ODEs: Stiffness, Implicit Methods, Runge-Kutta'
transcript: '<p><span m="30">The</span> <span m="130">following</span> <span m="600">content</span>
  <span m="1090">is</span> <span m="1200">provided</span> <span m="1660">under</span>
  <span m="1900">a</span> <span m="1950">Creative</span> <span m="2400">Commons</span>
  <span m="2820">license.</span> <span m="3780">Your</span> <span m="3880">support</span>
  <span m="4400">will</span> <span m="4570">help</span> <span m="4790">MIT</span>
  <span m="5280">OpenCourseWare</span> <span m="6020">continue</span> <span m="6510">to</span>
  <span m="6670">offer</span> <span m="6980">high</span> <span m="7200">quality</span>
  <span m="7680">educational</span> <span m="8350">resources</span> <span m="8920">for</span>
  <span m="9040">free.</span> <span m="10100">To</span> <span m="10130">make</span>
  <span m="10330">a</span> <span m="10370">donation</span> <span m="11090">or</span>
  <span m="11310">to</span> <span m="11430">view</span> <span m="11640">additional</span>
  <span m="12050">materials</span> <span m="12670">from</span> <span m="12860">hundreds</span>
  <span m="13180">of</span> <span m="13280">MIT</span> <span m="13650">courses,</span>
  <span m="14960">visit</span> <span m="15150">MIT</span> <span m="15670">OpenCourseWare</span>
  <span m="16580">at</span> <span m="16780">ocw.mit.edu.</span></p><p><span m="26090">PROFESSOR:
  OK.</span> <span m="26480">So</span> <span m="26690">let''s</span> <span m="27560">start.</span>
  <span m="29700">So</span> <span m="29900">first</span> <span m="30370">of</span>
  <span m="30460">all,</span> <span m="30570">it looks like</span> <span m="31160">there</span>
  <span m="31330">are</span> <span m="31860">many</span> <span m="32189">questions</span>
  <span m="32860">regarding</span> <span m="33270">the</span> <span m="33580">reading</span>
  <span m="34080">and</span> <span m="34270">homework.</span> <span m="35510">So</span>
  <span m="37530">if</span> <span m="37800">possible,</span> <span m="38680">I</span>
  <span m="38770">like</span> <span m="39060">to answer</span> <span m="39460">some</span>
  <span m="39680">of</span> <span m="39950">your</span> <span m="40550">more</span>
  <span m="40900">[INAUDIBLE]</span> <span m="41220">questions.</span> <span m="42180">Anyone</span>
  <span m="42520">want</span> <span m="42860">to</span> <span m="43030">raise</span>
  <span m="43230">a</span> <span m="43370">question</span> <span m="43780">I</span>
  <span m="44271">can answer?</span> <span m="47220">Yes.</span></p><p><span m="47500">AUDIENCE:
  So something</span> <span m="47984">that we</span> <span m="48468">were running</span>
  <span m="48952">into</span> <span m="49436">was the</span> <span m="49920">definition
  of</span> <span m="50404">local</span> <span m="50888">ordered</span> <span m="51372">[INAUDIBLE].</span>
  <span m="52340">Local</span> <span m="52635">and</span> <span m="52930">stationary</span>
  <span m="53758">and</span> <span m="55000">global</span> <span m="55240">[INAUDIBLE]</span>
  <span m="56082">and</span> <span m="56574">how</span> <span m="57066">to</span>
  <span m="57558">figure out</span> <span m="58542">[INAUDIBLE].</span> <span m="60020">OK.</span>
  <span m="60868">So</span> <span m="62140">what</span> <span m="62350">we ended up</span>
  <span m="62650">doing</span> <span m="62820">was</span> <span m="63310">finding</span>
  <span m="63800">[INAUDIBLE]</span> <span m="64290">by</span> <span m="64780">taking</span>
  <span m="65270">dd</span> <span m="65760">plus</span> <span m="66250">1</span> <span
  m="66870">minus</span> <span m="67140">[INAUDIBLE].</span></p><p><span m="69240">PROFESSOR:
  Yeah.</span></p><p><span m="69750">AUDIENCE: And</span> <span m="69920">then</span>
  <span m="70391">saying</span> <span m="70862">that that</span> <span m="71333">was
  the</span> <span m="71804">[INAUDIBLE]</span> <span m="72746">location</span> <span
  m="73217">of it.</span></p><p><span m="74160">PROFESSOR: OK.</span> <span m="74800">Yeah.</span></p><p><span
  m="75360">AUDIENCE: And</span> <span m="75540">then</span> <span m="75690">that</span>
  <span m="75910">was</span> <span m="76070">equal to--</span> <span m="76850">whatever</span>
  <span m="77200">order</span> <span m="77605">[INAUDIBLE]</span> <span m="78010">that
  was</span> <span m="78280">was equal</span> <span m="78748">to the order</span>
  <span m="79216">of</span> <span m="79684">delta</span> <span m="80152">t</span>
  <span m="80620">times</span> <span m="81088">[INAUDIBLE]</span> <span m="81556">plus</span>
  <span m="82024">1</span> <span m="82492">where</span> <span m="82960">t</span> <span
  m="83428">is the</span> <span m="83896">local</span> <span m="84364">order</span>
  <span m="84832">[INAUDIBLE].</span></p><p><span m="85300">PROFESSOR: That''s</span>
  <span m="85710">exactly</span> <span m="86270">what</span> <span m="86490">you</span>
  <span m="86570">should</span> <span m="86770">be</span> <span m="86880">doing is</span>
  <span m="87260">finding</span> <span m="87480">the</span> <span m="87650">local</span>
  <span m="87830">order</span> <span m="88090">of</span> <span m="88565">axis.</span>
  <span m="89990">Did</span> <span m="90130">anybody</span> <span m="90460">else</span>
  <span m="92120">understand</span> <span m="92800">what</span> <span m="93794">[INAUDIBLE]?</span>
  <span m="95285">OK.</span> <span m="95782">[INAUDIBLE]</span> <span m="96780">saying.</span>
  <span m="98590">So</span> <span m="99040">that''s</span> <span m="99370">exactly</span>
  <span m="99810">the</span> <span m="99940">right</span> <span m="100170">way</span>
  <span m="100350">of</span> <span m="100530">finding</span> <span m="100810">out</span>
  <span m="100980">the</span> <span m="101070">local</span> <span m="101440">order</span>
  <span m="101820">of</span> <span m="102000">axis.</span></p><p><span m="103900">Looking</span>
  <span m="104290">at</span> <span m="104400">the</span> <span m="104470">schema</span>
  <span m="104780">as</span> <span m="105090">[INAUDIBLE]</span> <span m="105375">n</span>
  <span m="105660">plus</span> <span m="105850">1</span> <span m="106690">minus</span>
  <span m="106945">the</span> <span m="107200">[INAUDIBLE]</span> <span m="107606">of
  the</span> <span m="108012">[INAUDIBLE].</span> <span m="108420">That</span> <span
  m="108620">is</span> <span m="108840">you''re</span> <span m="108960">tau.</span>
  <span m="109470">That</span> <span m="109770">is your</span> <span m="110010">[INAUDIBLE]</span>
  <span m="110340">area.</span> <span m="111450">And</span> <span m="111740">tau</span>
  <span m="112470">should</span> <span m="112750">be</span> <span m="112920">on</span>
  <span m="113100">the</span> <span m="113230">order</span> <span m="113940">delta</span>
  <span m="114370">t</span> <span m="114800">to the</span> <span m="115060">t</span>
  <span m="115350">plus</span> <span m="115750">1</span> <span m="116370">where</span>
  <span m="116810">p</span> <span m="117830">is</span> <span m="118110">a</span> <span
  m="118160">local</span> <span m="118530">order</span> <span m="118940">of</span>
  <span m="119433">[INAUDIBLE].</span> <span m="120419">OK.</span> <span m="120912">That''s</span>
  <span m="121405">basically</span> <span m="121898">repeating what</span> <span m="122391">[INAUDIBLE].</span></p><p><span
  m="124370">AUDIENCE: And how</span> <span m="124630">does that</span> <span m="125123">relate</span>
  <span m="125616">to the global</span> <span m="126109">order?</span></p><p><span
  m="127590">PROFESSOR: How</span> <span m="127750">does</span> <span m="127960">that</span>
  <span m="128120">relate</span> <span m="128419">to</span> <span m="128500">the</span>
  <span m="128639">global</span> <span m="129000">order</span> <span m="129220">of</span>
  <span m="129510">[INAUDIBLE]?</span> <span m="129800">Anybody</span> <span m="130169">want</span>
  <span m="131070">to</span> <span m="131180">attempt to answer</span> <span m="131470">that?</span></p><p><span
  m="133112">AUDIENCE: [INAUDIBLE]</span></p><p><span m="134930">PROFESSOR: So</span>
  <span m="135140">say</span> <span m="135650">that there</span> <span m="135960">is
  an</span> <span m="136270">if.</span></p><p><span m="137683">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="140509">PROFESSOR: If</span> <span m="140980">[INAUDIBLE]</span> <span m="142760">under</span>
  <span m="143120">what</span> <span m="143380">conditions</span> <span m="144000">does</span>
  <span m="144190">[INAUDIBLE]</span> <span m="144671">theorem hold?</span></p><p><span
  m="146114">AUDIENCE: [INAUDIBLE]</span></p><p><span m="148520">PROFESSOR: 0</span>
  <span m="149100">stable,</span> <span m="149530">right?</span> <span m="150010">As</span>
  <span m="150230">long</span> <span m="150350">as</span> <span m="150650">t</span>
  <span m="150890">is</span> <span m="151050">great</span> <span m="151320">or</span>
  <span m="151440">equal to</span> <span m="151700">1,</span> <span m="152076">which</span>
  <span m="152452">usually it</span> <span m="152830">is,</span> <span m="154390">you</span>
  <span m="154580">have</span> <span m="154720">a</span> <span m="154790">consistency.</span>
  <span m="156130">So</span> <span m="156730">consistency is</span> <span m="157040">usually
  is</span> <span m="157830">not</span> <span m="158170">that</span> <span m="158360">much
  of</span> <span m="158780">problem</span> <span m="159620">when</span> <span m="160050">you</span>
  <span m="160180">already</span> <span m="160540">have</span> <span m="160960">the</span>
  <span m="161030">local</span> <span m="161190">order of</span> <span m="161530">[INAUDIBLE].</span>
  <span m="162910">0</span> <span m="163200">stable</span> <span m="163340">is</span>
  <span m="163760">something</span> <span m="164070">you</span> <span m="164170">have</span>
  <span m="164460">to</span> <span m="165230">separately.</span> <span m="166590">But</span>
  <span m="166740">as long</span> <span m="166910">as</span> <span m="167220">the</span>
  <span m="167320">schema</span> <span m="167660">is</span> <span m="167850">0</span>
  <span m="167960">stable,</span> <span m="169600">then</span> <span m="169910">the</span>
  <span m="169980">local</span> <span m="170220">order</span> <span m="170560">of</span>
  <span m="170750">accuracy</span> <span m="171520">is</span> <span m="171790">equal</span>
  <span m="172060">to</span> <span m="172350">the</span> <span m="172560">global</span>
  <span m="172830">order of</span> <span m="173180">accuracy</span> <span m="174530">as</span>
  <span m="174780">long</span> <span m="174990">as</span> <span m="175210">that</span>
  <span m="175450">order of</span> <span m="175780">accuracy</span> <span m="176095">is</span>
  <span m="176410">great of</span> <span m="176770">equal to</span> <span m="177130">1.</span>
  <span m="180540">Is</span> <span m="180840">that</span> <span m="181090">clear?</span></p><p><span
  m="183062">AUDIENCE: Could you repeat that</span> <span m="183555">one more time?</span></p><p><span
  m="185040">PROFESSOR: If</span> <span m="185250">a</span> <span m="185450">[INAUDIBLE]</span>
  <span m="185630">is</span> <span m="185800">0</span> <span m="186090">stable,</span>
  <span m="187670">then</span> <span m="188070">the</span> <span m="188180">local</span>
  <span m="188580">order</span> <span m="188770">of</span> <span m="188890">accuracy</span>
  <span m="189460">is</span> <span m="189650">the</span> <span m="189740">same</span>
  <span m="190110">as</span> <span m="190290">the</span> <span m="190540">global</span>
  <span m="190980">order</span> <span m="191270">of</span> <span m="191732">accuracy.</span></p><p><span
  m="194042">AUDIENCE: [INAUDIBLE]</span></p><p><span m="200160">PROFESSOR: Exactly.</span>
  <span m="200720">When</span> <span m="201450">a</span> <span m="201730">scheme</span>
  <span m="201900">is</span> <span m="202180">not</span> <span m="202550">0</span>
  <span m="202850">stable,</span> <span m="203336">it''s</span> <span m="203822">[INAUDIBLE]</span>
  <span m="204794">equal to</span> <span m="205280">0.</span> <span m="205700">And</span>
  <span m="206030">there</span> <span m="206220">is</span> <span m="206340">no</span>
  <span m="206640">global</span> <span m="207070">order of</span> <span m="207475">accuracy</span>
  <span m="207880">at all.</span> <span m="209880">Yes.</span></p><p><span m="210635">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="216080">PROFESSOR: Yes.</span> <span m="216520">If</span>
  <span m="216960">a schema</span> <span m="217610">is</span> <span m="217860">not</span>
  <span m="218270">0 stable,</span> <span m="218790">then</span> <span m="219330">the</span>
  <span m="219460">scheme</span> <span m="219710">doesn''t</span> <span m="220181">work.</span>
  <span m="223310">Remember</span> <span m="225151">when</span> <span m="225550">we</span>
  <span m="225810">had</span> <span m="226230">the</span> <span m="227070">supposedly</span>
  <span m="227490">most</span> <span m="227880">accurate</span> <span m="229026">two-step</span>
  <span m="229980">scheme,</span> <span m="230540">[INAUDIBLE]</span> <span m="230855">scheme?</span>
  <span m="231870">What</span> <span m="232070">happens</span> <span m="232410">when</span>
  <span m="232840">we</span> <span m="232980">rebuilt</span> <span m="233490">the</span>
  <span m="233580">delta t?</span> <span m="233840">The</span> <span m="234100">error,</span>
  <span m="234500">instead of</span> <span m="234900">decreasing,</span> <span m="235350">it</span>
  <span m="235800">increases.</span></p><p><span m="238050">So</span> <span m="238210">that''s</span>
  <span m="238460">what</span> <span m="238620">happens</span> <span m="239110">with</span>
  <span m="239460">a</span> <span m="240180">not</span> <span m="240330">0 stable</span>
  <span m="240600">scheme,</span> <span m="241840">where</span> <span m="242020">you</span>
  <span m="242240">refine</span> <span m="242580">your</span> <span m="242920">time</span>
  <span m="243210">step.</span> <span m="244070">Instead</span> <span m="244170">of</span>
  <span m="244300">the</span> <span m="244430">error</span> <span m="244560">decreasing,</span>
  <span m="245090">you</span> <span m="245220">have an</span> <span m="245480">increasing</span>
  <span m="245890">error.</span> <span m="247530">All right.</span> <span m="250270">Any</span>
  <span m="250440">other</span> <span m="250590">questions?</span></p><p><span m="254034">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="266270">PROFESSOR: OK.</span> <span m="266630">So</span>
  <span m="266930">the</span> <span m="267020">question</span> <span m="267320">is</span>
  <span m="268340">can</span> <span m="268560">we</span> <span m="268690">go</span>
  <span m="269040">over</span> <span m="271370">eigenvalues</span> <span m="272070">[INAUDIBLE]</span>
  <span m="272680">again?</span> <span m="273680">[INAUDIBLE]</span> <span m="274180">page--</span>
  <span m="275180">yes.</span> <span m="278450">All</span> <span m="278600">right.</span>
  <span m="279650">So</span> <span m="280050">in</span> <span m="280260">doing</span>
  <span m="280490">eigenvalues,</span> <span m="281050">stability</span> <span m="281650">you</span>
  <span m="281860">plug in</span> <span m="282347">du dt</span> <span m="283810">equal</span>
  <span m="284240">to</span> <span m="284430">lambda</span> <span m="284790">u,</span>
  <span m="285470">right?</span> <span m="286300">So</span> <span m="286510">that</span>
  <span m="286700">is</span> <span m="286850">the</span> <span m="287010">question</span>
  <span m="287530">you</span> <span m="287940">use</span> <span m="288280">to</span>
  <span m="288380">analyze</span> <span m="289090">eigenvalue</span> <span m="289410">stability.</span></p><p><span
  m="291560">Then</span> <span m="291890">you</span> <span m="292060">write</span>
  <span m="292300">down</span> <span m="292540">an</span> <span m="292620">equation</span>
  <span m="293090">of</span> <span m="293370">Un</span> <span m="294010">plus</span>
  <span m="294350">1.</span> <span m="295063">Again,</span> <span m="295790">if</span>
  <span m="296030">it''s</span> <span m="296250">a</span> <span m="297940">midpoint</span>
  <span m="298350">rule,</span> <span m="299130">then</span> <span m="300280">the</span>
  <span m="300550">scheme</span> <span m="300960">I''m</span> <span m="301220">plugging</span>
  <span m="301960">is</span> <span m="302240">plus</span> <span m="302570">2</span>
  <span m="302820">delta</span> <span m="303030">t</span> <span m="303200">times</span>
  <span m="305200">f</span> <span m="305590">of</span> <span m="305840">Vn.</span>
  <span m="306470">And</span> <span m="306660">in</span> <span m="306780">this</span>
  <span m="306980">case,</span> <span m="307470">f</span> <span m="307550">of</span>
  <span m="307670">Vn</span> <span m="308330">is</span> <span m="308620">lambda</span>
  <span m="309140">times</span> <span m="309630">the</span> <span m="310120">Vn</span>
  <span m="310610">right?</span> <span m="311830">So</span> <span m="312000">that</span>
  <span m="312170">is</span> <span m="312320">the</span> <span m="312430">equation</span>
  <span m="312950">you</span> <span m="313100">get</span> <span m="313955">by</span>
  <span m="314380">plugging</span> <span m="314640">in</span> <span m="315100">the</span>
  <span m="315430">differential</span> <span m="315920">equation</span> <span m="316320">into</span>
  <span m="316830">a</span> <span m="316990">scheme.</span></p><p><span m="319530">Now,</span>
  <span m="319810">the</span> <span m="319890">next</span> <span m="320140">thing</span>
  <span m="320320">to</span> <span m="320430">do</span> <span m="320650">is</span>
  <span m="321070">to</span> <span m="321200">assume</span> <span m="321810">my</span>
  <span m="322040">Vn.</span> <span m="322924">And</span> <span m="325060">actually</span>
  <span m="325492">V n</span> <span m="325924">plus 1,</span> <span m="326356">Vn
  minus</span> <span m="327160">1,</span> <span m="327460">and</span> <span m="327710">all</span>
  <span m="327910">other</span> <span m="328180">terms</span> <span m="328620">in</span>
  <span m="328710">your</span> <span m="328890">scheme</span> <span m="329270">satisfies</span>
  <span m="330960">an</span> <span m="331530">exponentially</span> <span m="332660">growing</span>
  <span m="333750">pattern.</span> <span m="336270">So</span> <span m="337270">when</span>
  <span m="337540">I</span> <span m="337570">whatever</span> <span m="337680">time</span>
  <span m="337770">stamp</span> <span m="338040">it</span> <span m="338250">is,</span>
  <span m="338540">it</span> <span m="338830">is</span> <span m="339050">equal</span>
  <span m="339360">to</span> <span m="339500">the</span> <span m="339700">0</span>
  <span m="339960">time stamp</span> <span m="341310">times</span> <span m="341910">a</span>
  <span m="342170">growth</span> <span m="342570">factor</span> <span m="343170">to</span>
  <span m="344082">whatever</span> <span m="344544">time</span> <span m="345006">stamp</span>
  <span m="345470">[INAUDIBLE].</span></p><p><span m="348090">So</span> <span m="348270">once</span>
  <span m="348560">you</span> <span m="348930">plug</span> <span m="349680">all</span>
  <span m="349960">of</span> <span m="350120">these</span> <span m="350560">into</span>
  <span m="350910">the</span> <span m="351030">scheme,</span> <span m="352500">you</span>
  <span m="352660">can</span> <span m="352880">find</span> <span m="353210">the</span>
  <span m="353910">quadratic</span> <span m="354300">equation</span> <span m="354940">for</span>
  <span m="355090">z</span> <span m="355450">if</span> <span m="355930">it''s</span>
  <span m="356100">a</span> <span m="356180">two-step</span> <span m="356630">scheme.</span>
  <span m="356970">If</span> <span m="357120">it''s</span> <span m="357250">a</span>
  <span m="357300">one-step</span> <span m="357830">scheme,</span> <span m="358050">you</span>
  <span m="358260">find</span> <span m="359090">just</span> <span m="359865">a</span>
  <span m="360320">linear</span> <span m="360370">equation</span> <span m="360730">for</span>
  <span m="360907">z.</span> <span m="361440">If</span> <span m="362150">it''s</span>
  <span m="362300">a</span> <span m="362480">three-step</span> <span m="362940">scheme,</span>
  <span m="363270">you''re</span> <span m="363390">going</span> <span m="363510">to</span>
  <span m="363590">find</span> <span m="363890">out</span> <span m="364020">with</span>
  <span m="364140">a</span> <span m="365930">cubic</span> <span m="366310">equation</span>
  <span m="366740">for</span> <span m="366890">z,</span> <span m="368150">et cetera.</span></p><p><span
  m="369940">And</span> <span m="370160">then</span> <span m="371000">the</span> <span
  m="371140">next</span> <span m="371690">is</span> <span m="372030">to</span> <span
  m="372350">see,</span> <span m="376270">does</span> <span m="376620">that</span>
  <span m="376900">equation</span> <span m="377280">allow</span> <span m="377670">any</span>
  <span m="378116">z,</span> <span m="378562">any</span> <span m="379010">solution,</span>
  <span m="380384">who''s</span> <span m="381300">modulus</span> <span m="382100">is</span>
  <span m="382460">greater</span> <span m="383100">than</span> <span m="383300">1?</span>
  <span m="384890">If</span> <span m="385170">that</span> <span m="385390">equation</span>
  <span m="386210">for</span> <span m="386380">particular</span> <span m="386990">combination</span>
  <span m="387850">of</span> <span m="388500">delta</span> <span m="388780">t</span>
  <span m="388950">and</span> <span m="389150">lambda--</span> <span m="390170">delta
  t</span> <span m="390350">and</span> <span m="390450">lambda</span> <span m="391040">is</span>
  <span m="391180">always</span> <span m="391530">multiplied</span> <span m="391750">together.</span>
  <span m="393380">So</span> <span m="393820">for</span> <span m="394070">whatever</span>
  <span m="394390">delta t</span> <span m="394955">times</span> <span m="395330">lambda</span>
  <span m="397200">if</span> <span m="398030">this</span> <span m="398380">equation</span>
  <span m="398790">allows</span> <span m="398850">for</span> <span m="398920">z</span>
  <span m="399735">that</span> <span m="399990">has</span> <span m="400210">a</span>
  <span m="400270">modulus</span> <span m="400800">greater</span> <span m="401060">than</span>
  <span m="401240">1,</span> <span m="401800">then</span> <span m="402550">it</span>
  <span m="402710">is</span> <span m="402900">not</span> <span m="403330">eigenvalue</span>
  <span m="403870">stable.</span> <span m="405800">The</span> <span m="405980">combination</span>
  <span m="406530">of</span> <span m="406660">the</span> <span m="406730">scheme</span>
  <span m="407260">and</span> <span m="407620">that</span> <span m="407960">lambda</span>
  <span m="408210">delta t</span> <span m="408661">is</span> <span m="409112">not</span>
  <span m="409563">eigenvalue</span> <span m="410014">stable.</span> <span m="410465">Yeah.</span></p><p><span
  m="410916">AUDIENCE: When you</span> <span m="411370">say </span> <span m="411650">the</span>
  <span m="411890">modulus</span> <span m="413090">greater than</span> <span m="413570">or
  equal</span> <span m="414050">to 1,</span> <span m="415970">I guess</span> <span
  m="416450">whenever</span> <span m="416930">I see</span> <span m="417420">modulus</span>
  <span m="418269">[INAUDIBLE].</span></p><p><span m="423900">PROFESSOR: OK.</span>
  <span m="424830">So</span> <span m="425140">the</span> <span m="425340">question</span>
  <span m="425710">is</span> <span m="426010">modulus</span> <span m="426310">is.</span>
  <span m="428100">Here</span> <span m="428310">the</span> <span m="428780">modulus</span>
  <span m="429020">is</span> <span m="429740">off</span> <span m="430100">a</span>
  <span m="430530">[INAUDIBLE]</span> <span m="430930">number.</span></p><p><span
  m="431190">AUDIENCE: Oh,</span> <span m="431604">so do you</span> <span m="432018">mean
  like</span> <span m="432432">[INAUDIBLE]?</span></p><p><span m="433260">PROFESSOR:
  Yeah.</span> <span m="433430">The</span> <span m="433640">[INAUDIBLE]</span> <span
  m="433900">to it</span> <span m="435100">is</span> <span m="435350">the</span> <span
  m="435440">real</span> <span m="435840">of</span> <span m="436246">z</span> <span
  m="436652">squared</span> <span m="437058">plus</span> <span m="437870">imaginary</span>
  <span m="438135">of</span> <span m="438730">d</span> <span m="438940">squared.</span>
  <span m="439650">What</span> <span m="439870">is</span> <span m="440020">the</span>
  <span m="440120">significance</span> <span m="440740">of</span> <span m="440900">that?</span>
  <span m="441120">The</span> <span m="441210">significance</span> <span m="441840">of</span>
  <span m="442020">that</span> <span m="442240">is</span> <span m="442550">that</span>
  <span m="443260">if</span> <span m="443680">that</span> <span m="444140">modulus</span>
  <span m="444810">is</span> <span m="445020">greater</span> <span m="445360">than</span>
  <span m="445560">1,</span> <span m="446930">then</span> <span m="447570">z</span>
  <span m="447870">to</span> <span m="447980">the</span> <span m="448070">nth</span>
  <span m="448400">power</span> <span m="448750">is</span> <span m="448990">going</span>
  <span m="449110">to</span> <span m="449170">grow</span> <span m="449490">larger</span>
  <span m="449880">and</span> <span m="449990">larger</span> <span m="450400">as</span>
  <span m="450640">you</span> <span m="450740">make</span> <span m="451050">n</span>
  <span m="451280">larger.</span> <span m="452620">If</span> <span m="452790">the</span>
  <span m="452860">modulus</span> <span m="453350">is</span> <span m="453530">less</span>
  <span m="454060">than</span> <span m="454300">1,</span> <span m="454900">then</span>
  <span m="455290">z</span> <span m="455720">to</span> <span m="455810">the</span>
  <span m="455890">nth</span> <span m="456080">power</span> <span m="456340">is</span>
  <span m="456480">going</span> <span m="456620">to</span> <span m="456690">become</span>
  <span m="457030">smaller</span> <span m="457530">as</span> <span m="457750">a</span>
  <span m="457880">take</span> <span m="458255">n to</span> <span m="458630">infinity.</span></p><p><span
  m="459970">What</span> <span m="460170">happens</span> <span m="460560">if</span>
  <span m="460700">the</span> <span m="460780">modulus</span> <span m="461200">of</span>
  <span m="461380">these</span> <span m="461765">equal to</span> <span m="462150">1?</span>
  <span m="463680">Then</span> <span m="463850">the</span> <span m="463920">modulus</span>
  <span m="464230">of</span> <span m="464490">these</span> <span m="464810">always</span>
  <span m="465130">going</span> <span m="465260">to</span> <span m="465320">be</span>
  <span m="465460">equal to</span> <span m="465953">1</span> <span m="466446">whatever</span>
  <span m="466939">[INAUDIBLE].</span> <span m="470390">OK.</span> <span m="470680">Any</span>
  <span m="470880">other</span> <span m="471080">question?</span> <span m="473290">Yeah.</span></p><p><span
  m="473999">AUDIENCE: [INAUDIBLE]</span></p><p><span m="480570">PROFESSOR: OK.</span>
  <span m="480980">So</span> <span m="481190">last</span> <span m="481980">week''s</span>
  <span m="482340">[INAUDIBLE],</span> <span m="482710">why</span> <span m="483020">does</span>
  <span m="483280">du dt</span> <span m="483680">[INAUDIBLE]</span> <span m="485808">negative</span>
  <span m="486240">lambda</span> <span m="486600">times</span> <span m="486920">u.</span>
  <span m="487886">So</span> <span m="489050">in</span> <span m="489240">analyzing</span>
  <span m="489870">eigenvalue</span> <span m="490470">stability,</span> <span m="493440">you</span>
  <span m="493750">are</span> <span m="493840">looking</span> <span m="494170">at</span>
  <span m="494250">equation</span> <span m="494700">of</span> <span m="494910">this</span>
  <span m="495070">form.</span> <span m="495540">Right?</span> <span m="496040">So</span>
  <span m="496190">if</span> <span m="496410">I</span> <span m="496580">write</span>
  <span m="496890">down</span> <span m="497300">equal</span> <span m="497460">to</span>
  <span m="497740">lambda</span> <span m="498530">minus</span> <span m="498920">lambda</span>
  <span m="499280">times</span> <span m="499520">u,</span> <span m="499660">it</span>
  <span m="499820">is</span> <span m="500070">still</span> <span m="500810">in</span>
  <span m="500970">this</span> <span m="501220">form.</span></p><p><span m="503520">It''s</span>
  <span m="503740">just</span> <span m="503970">the</span> <span m="504060">sign</span>
  <span m="504390">of</span> <span m="504510">the</span> <span m="504590">lambdas</span>
  <span m="505200">are</span> <span m="505990">kind of</span> <span m="506680">wrong.</span>
  <span m="507220">I mean,</span> <span m="507360">you can--</span> <span m="508492">maybe
  I</span> <span m="508860">should</span> <span m="509120">use</span> <span m="509310">another</span>
  <span m="509640">symbol.</span> <span m="510120">Maybe</span> <span m="510410">I</span>
  <span m="510490">should</span> <span m="510980">say</span> <span m="511420">dudt</span>
  <span m="512390">equal</span> <span m="512740">to</span> <span m="512809">minus</span>
  <span m="513070">theta</span> <span m="513650">times u.</span> <span m="515299">In</span>
  <span m="515460">that</span> <span m="515640">case,</span> <span m="516370">then</span>
  <span m="516580">you</span> <span m="516720">just</span> <span m="516890">have to</span>
  <span m="517230">[INAUDIBLE]</span> <span m="517570">lambda</span> <span m="517940">equal</span>
  <span m="518159">to</span> <span m="518360">minus</span> <span m="518679">theta.</span>
  <span m="519070">And</span> <span m="519250">you</span> <span m="519380">can</span>
  <span m="519610">do</span> <span m="519740">the</span> <span m="519870">analysis</span>
  <span m="520510">the</span> <span m="520610">same</span> <span m="520850">way.</span>
  <span m="526336">Does</span> <span m="526812">that</span> <span m="527288">answer
  your</span> <span m="527764">question?</span></p><p><span m="528716">AUDIENCE: Yeah.</span>
  <span m="529192">[INAUDIBLE]</span></p><p><span m="530620">PROFESSOR: OK.</span>
  <span m="532540">Any</span> <span m="532710">other</span> <span m="532890">question?</span>
  <span m="535780">No?</span> <span m="537440">[INAUDIBLE]</span> <span m="537850">more.</span>
  <span m="538330">OK.</span> <span m="541060">OK.</span> <span m="541340">So</span>
  <span m="541560">for</span> <span m="541690">the</span> <span m="541780">reading</span>
  <span m="542140">recap,</span> <span m="543380">we</span> <span m="543560">have</span>
  <span m="543930">read</span> <span m="544280">about</span> <span m="545600">stiffness</span>
  <span m="546640">and</span> <span m="546880">the</span> <span m="546980">Newton-Raphson.</span>
  <span m="547810">Let</span> <span m="547960">me</span> <span m="548410">recap</span>
  <span m="548900">what</span> <span m="549070">they</span> <span m="549210">are.</span>
  <span m="550540">Stiffness</span> <span m="551490">are</span> <span m="551660">really</span>
  <span m="552010">orders</span> <span m="552650">of</span> <span m="552810">magnitude</span>
  <span m="553070">distance</span> <span m="553330">in</span> <span m="553813">timescales.</span>
  <span m="555840">OK.</span></p><p><span m="557265">So a</span> <span m="557740">stiff</span>
  <span m="558060">problem</span> <span m="559340">means</span> <span m="559850">there</span>
  <span m="559980">is</span> <span m="560440">one</span> <span m="561470">timescale
  that</span> <span m="561650">is</span> <span m="561780">a</span> <span m="561830">very,</span>
  <span m="562410">very</span> <span m="562640">small</span> <span m="563850">compared</span>
  <span m="564540">to</span> <span m="564780">the timescale</span> <span m="565750">of</span>
  <span m="566235">the main</span> <span m="566720">phenomenon</span> <span m="567540">we</span>
  <span m="567680">want</span> <span m="567870">to</span> <span m="567960">simulate.</span>
  <span m="571030">Maybe</span> <span m="571650">we</span> <span m="571760">want</span>
  <span m="572010">to</span> <span m="572170">simulate</span> <span m="573140">some</span>
  <span m="573450">phenomenon</span> <span m="574040">that</span> <span m="574210">is</span>
  <span m="574330">interesting.</span> <span m="574840">But</span> <span m="575010">in</span>
  <span m="575270">order</span> <span m="575590">to</span> <span m="575750">simulate</span>
  <span m="576290">that,</span> <span m="577900">there</span> <span m="578320">is</span>
  <span m="578590">something</span> <span m="578870">of</span> <span m="578990">a</span>
  <span m="579080">hidden</span> <span m="579480">timescale</span> <span m="580000">that</span>
  <span m="580180">is</span> <span m="580460">much,</span> <span m="580920">much</span>
  <span m="581070">faster</span> <span m="581780">than</span> <span m="582100">the</span>
  <span m="582180">one</span> <span m="582510">we</span> <span m="582740">are</span>
  <span m="582940">interested</span> <span m="583280">in.</span></p><p><span m="584030">And</span>
  <span m="584240">I''m</span> <span m="584370">going</span> <span m="584490">to</span>
  <span m="584580">show</span> <span m="584800">you</span> <span m="585510">two</span>
  <span m="585860">examples</span> <span m="586470">of</span> <span m="586730">what</span>
  <span m="588090">that</span> <span m="588890">very</span> <span m="589230">small</span>
  <span m="589530">timescale</span> <span m="589975">is.</span> <span m="592200">And</span>
  <span m="593808">so</span> <span m="594210">that</span> <span m="595130">is</span>
  <span m="595430">expressed</span> <span m="595930">in terms</span> <span m="596430">of</span>
  <span m="596930">physical</span> <span m="597270">phenomenon,</span> <span m="598353">two
  different</span> <span m="598776">timescales.</span> <span m="599622">we''re</span>
  <span m="600045">presenting</span> <span m="600470">maybe</span> <span m="600700">two</span>
  <span m="600960">different</span> <span m="601245">physical</span> <span m="601530">phenomenon</span>
  <span m="603100">that</span> <span m="603410">you</span> <span m="603520">have</span>
  <span m="603680">to</span> <span m="604070">simulate</span> <span m="604460">at
  the</span> <span m="604530">same</span> <span m="604800">time.</span> <span m="605510">In</span>
  <span m="605700">terms</span> <span m="605950">of</span> <span m="606110">mathematics,</span>
  <span m="606820">where</span> <span m="606950">you</span> <span m="607150">write</span>
  <span m="607410">down</span> <span m="607840">OD,</span> <span m="608320">when</span>
  <span m="608570">you</span> <span m="608710">write</span> <span m="608950">an</span>
  <span m="609060">Ordinary</span> <span m="609660">Differential</span> <span m="610050">equation,</span>
  <span m="611850">you</span> <span m="612340">already</span> <span m="613300">kind</span>
  <span m="613480">of</span> <span m="613650">abstracted</span> <span m="614630">from</span>
  <span m="615020">the</span> <span m="615150">physics.</span> <span m="615940">So</span>
  <span m="616160">in</span> <span m="616360">that</span> <span m="616610">case,</span>
  <span m="618490">how</span> <span m="618660">do</span> <span m="618750">you</span>
  <span m="618810">interpret</span> <span m="619390">[INAUDIBLE]?</span></p><p><span
  m="621120">OK.</span> <span m="621590">We</span> <span m="621710">can</span> <span
  m="621900">say</span> <span m="622130">that</span> <span m="622430">when</span>
  <span m="622820">you</span> <span m="623430">transform</span> <span m="624310">a</span>
  <span m="624570">physical</span> <span m="625090">phenomenon</span> <span m="625670">into</span>
  <span m="625900">an</span> <span m="626010">ordinary</span> <span m="626670">differential</span>
  <span m="627110">equation,</span> <span m="627900">the</span> <span m="628040">timescale</span>
  <span m="629400">is</span> <span m="629610">really</span> <span m="630290">translated</span>
  <span m="630860">into</span> <span m="631050">eigenvalues.</span> <span m="632490">And</span>
  <span m="632920">we</span> <span m="633090">are</span> <span m="633340">also</span>
  <span m="633520">going to</span> <span m="633660">see</span> <span m="633950">examples.</span>
  <span m="635175">So</span> <span m="635640">if</span> <span m="635900">you</span>
  <span m="636050">have</span> <span m="636250">two</span> <span m="636400">timescales,</span>
  <span m="637600">one</span> <span m="638000">slow,</span> <span m="638410">one</span>
  <span m="638880">fast,</span> <span m="640180">we</span> <span m="640290">are</span>
  <span m="640360">going</span> <span m="640490">to</span> <span m="640630">see</span>
  <span m="640890">two</span> <span m="641324">eigenvalues</span> <span m="643060">where</span>
  <span m="643320">you</span> <span m="643760">write</span> <span m="644110">down</span>
  <span m="644974">the</span> <span m="645398">equation</span> <span m="646670">in</span>
  <span m="646850">its</span> <span m="647020">matrix</span> <span m="647430">form</span>
  <span m="648050">and</span> <span m="648320">[INAUDIBLE]</span> <span m="648480">do</span>
  <span m="648910">eigenvalue</span> <span m="649340">analysis</span> <span m="650140">of
  the</span> <span m="650540">matrix.</span></p><p><span m="651790">So</span> <span
  m="652260">we''re</span> <span m="652730">going to</span> <span m="653200">see one</span>
  <span m="653300">large</span> <span m="653650">eigenvalue,</span> <span m="654023">one</span>
  <span m="654396">small</span> <span m="654770">eigenvalue.</span> <span m="656320">And</span>
  <span m="656490">the</span> <span m="656720">fast</span> <span m="657070">process</span>
  <span m="657900">responds</span> <span m="658400">to</span> <span m="658570">the</span>
  <span m="658830">larger</span> <span m="659020">one</span> <span m="659210">or</span>
  <span m="659330">the</span> <span m="659390">smaller</span> <span m="659680">one,</span>
  <span m="661455">what do you</span> <span m="661950">think?</span></p><p><span m="663930">AUDIENCE:
  Large?</span></p><p><span m="664920">PROFESSOR: The</span> <span m="665020">large,</span>
  <span m="665450">why?</span></p><p><span m="666674">AUDIENCE: Because it''s</span>
  <span m="667156">[INAUDIBLE].</span></p><p><span m="677280">PROFESSOR: Exactly.</span>
  <span m="679050">So</span> <span m="679210">the</span> <span m="679320">large</span>
  <span m="679740">eigenvalue</span> <span m="680190">corresponds</span> <span m="680530">to</span>
  <span m="680830">the</span> <span m="680920">fast</span> <span m="681560">process.</span>
  <span m="682740">So</span> <span m="682760">if</span> <span m="682990">you</span>
  <span m="683090">think</span> <span m="683380">of</span> <span m="683540">dudt</span>
  <span m="684640">equal</span> <span m="685030">to</span> <span m="685140">lambda</span>
  <span m="685550">u,</span> <span m="687780">what</span> <span m="688260">unit</span>
  <span m="688940">does</span> <span m="689270">lambda</span> <span m="689650">have?</span>
  <span m="691980">That''s</span> <span m="692220">another</span> <span m="692520">way</span>
  <span m="692660">to</span> <span m="692770">think</span> <span m="692990">about</span>
  <span m="693250">it.</span> <span m="694200">What</span> <span m="694470">unit</span>
  <span m="694620">does</span> <span m="695820">lambda</span> <span m="696170">have?</span>
  <span m="697640">In</span> <span m="697890">engineering,</span> <span m="698420">one</span>
  <span m="698600">of</span> <span m="698710">the</span> <span m="698780">most important</span>
  <span m="699280">things is</span> <span m="699780">to look</span> <span m="700280">at</span>
  <span m="700780">the units</span> <span m="701280">of everything,</span> <span m="701780">right?</span>
  <span m="702280">Huh?</span></p><p><span m="703280">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="704530">PROFESSOR: Yes.</span> <span m="704910">The</span> <span m="705080">unit</span>
  <span m="705485">of lambda</span> <span m="705890">is</span> <span m="706700">1</span>
  <span m="707190">over</span> <span m="707690">the</span> <span m="707810">unit</span>
  <span m="707900">[INAUDIBLE].</span> <span m="708275">It''s</span> <span m="708650">1</span>
  <span m="708900">over</span> <span m="708960">[INAUDIBLE].</span> <span m="710730">Lambda</span>
  <span m="711320">really</span> <span m="711620">has a</span> <span m="712054">unit
  of</span> <span m="712488">frequency</span> <span m="712922">or</span> <span m="713790">rate,</span>
  <span m="714256">right?</span> <span m="716240">Actually,</span> <span m="716515">lambda</span>
  <span m="716790">is</span> <span m="717262">a--</span> <span m="718206">imaginary</span>
  <span m="718678">lambda</span> <span m="719150">it is</span> <span m="719622">exactly
  the</span> <span m="720094">[INAUDIBLE]</span> <span m="720566">frequency</span>
  <span m="721038">of the</span> <span m="721510">solution, right?</span> <span m="722454">So</span>
  <span m="722926">lambda</span> <span m="723410">has</span> <span m="723610">the
  unit of</span> <span m="723900">frequency.</span></p><p><span m="725724">A</span>
  <span m="726180">very fast</span> <span m="727150">process</span> <span m="727590">is</span>
  <span m="727740">going</span> <span m="727880">to</span> <span m="727960">have</span>
  <span m="728080">a</span> <span m="728140">high</span> <span m="728340">frequency,</span>
  <span m="728860">therefore</span> <span m="729390">a</span> <span m="729560">large</span>
  <span m="730020">eigenvalue.</span> <span m="731080">And</span> <span m="731250">a</span>
  <span m="731290">very</span> <span m="731550">slow</span> <span m="731870">process</span>
  <span m="732460">is</span> <span m="732660">going</span> <span m="732800">to</span>
  <span m="732860">have</span> <span m="733000">a</span> <span m="733080">low</span>
  <span m="733330">frequency,</span> <span m="733970">and</span> <span m="734190">therefore</span>
  <span m="735900">a</span> <span m="736050">small</span> <span m="736335">eigenvalue.</span>
  <span m="738356">All right,</span> <span m="738790">does it</span> <span m="739220">make</span>
  <span m="739370">sense?</span> <span m="740130">So</span> <span m="740360">stiffness</span>
  <span m="740910">can</span> <span m="741160">either</span> <span m="741410">be</span>
  <span m="741550">interpreted</span> <span m="742030">in</span> <span m="742180">terms</span>
  <span m="742410">of</span> <span m="742650">order of</span> <span m="742990">magnitude</span>
  <span m="743430">difference</span> <span m="743770">in</span> <span m="743860">timescales</span>
  <span m="744970">or</span> <span m="745400">order</span> <span m="745790">of</span>
  <span m="745920">magnitude</span> <span m="746370">difference</span> <span m="747747">in</span>
  <span m="748665">eigenvalues.</span></p><p><span m="750960">OK.</span> <span m="751570">You</span>
  <span m="751790">also</span> <span m="753590">read</span> <span m="753820">about</span>
  <span m="754050">Newton-Raphson.</span> <span m="755540">And</span> <span m="756230">Newton-Raphson</span>
  <span m="756750">is</span> <span m="756830">the</span> <span m="756900">matter</span>
  <span m="757240">of</span> <span m="757380">solving</span> <span m="759150">nonlinear</span>
  <span m="759890">equations</span> <span m="760620">using</span> <span m="761080">increasing</span>
  <span m="761415">schemes.</span> <span m="763910">So</span> <span m="764280">the</span>
  <span m="764640">[INAUDIBLE]</span> <span m="765090">is,</span> <span m="765650">as</span>
  <span m="765810">you''re</span> <span m="765890">going to</span> <span m="766010">see,</span>
  <span m="766660">is</span> <span m="767050">going</span> <span m="767180">to</span>
  <span m="767240">benefit</span> <span m="767710">a</span> <span m="767810">lot</span>
  <span m="769270">from</span> <span m="770130">using</span> <span m="770550">an</span>
  <span m="770740">implicit</span> <span m="771035">scheme</span> <span m="771330">instead
  of</span> <span m="772042">explicit</span> <span m="772400">scheme.</span></p><p><span
  m="773930">And</span> <span m="774120">when</span> <span m="774270">you</span> <span
  m="774410">have</span> <span m="774560">a</span> <span m="774630">nonlinear</span>
  <span m="775210">equation</span> <span m="776820">and</span> <span m="777130">you</span>
  <span m="777260">want</span> <span m="777530">to</span> <span m="777650">use</span>
  <span m="778160">an</span> <span m="778370">explicit</span> <span m="779050">scheme,</span>
  <span m="779726">as</span> <span m="780122">you</span> <span m="780520">dismay</span>
  <span m="780910">discover</span> <span m="781480">when</span> <span m="781720">you</span>
  <span m="781960">are</span> <span m="782820">doing</span> <span m="783000">the</span>
  <span m="783070">homework</span> <span m="783390">question,</span> <span m="784630">at</span>
  <span m="785090">every</span> <span m="785590">time</span> <span m="785970">stamp</span>
  <span m="786650">you</span> <span m="786810">need to</span> <span m="787050">solve</span>
  <span m="787450">a</span> <span m="787860">nonlinear</span> <span m="788306">equation,</span>
  <span m="788752">a</span> <span m="789200">nonlinear</span> <span m="789720">algebraic</span>
  <span m="790015">equation.</span> <span m="791320">In</span> <span m="791450">the</span>
  <span m="791540">homework,</span> <span m="792365">the</span> <span m="792770">equation</span>
  <span m="792830">happens</span> <span m="793260">to</span> <span m="793380">be</span>
  <span m="793470">a</span> <span m="793720">quadratic</span> <span m="794070">equation,</span>
  <span m="794330">and you</span> <span m="794810">can solve it using</span> <span
  m="795290">[INAUDIBLE].</span> <span m="796730">But</span> <span m="796980">in</span>
  <span m="797180">general,</span> <span m="798050">that</span> <span m="798440">nonlinear</span>
  <span m="798780">equation</span> <span m="799610">you</span> <span m="799740">have</span>
  <span m="800040">solved</span> <span m="800510">every</span> <span m="801050">single</span>
  <span m="801620">time</span> <span m="801990">stamp</span> <span m="803410">is</span>
  <span m="803720">not</span> <span m="803950">going</span> <span m="804110">to</span>
  <span m="804210">happen</span> <span m="804650">to</span> <span m="804810">be</span>
  <span m="804970">an</span> <span m="805230">equation</span> <span m="805570">with</span>
  <span m="805810">an</span> <span m="805950">analytical</span> <span m="806550">solution.</span>
  <span m="807680">And</span> <span m="807880">a</span> <span m="807910">Newton-Raphson</span>
  <span m="809260">is</span> <span m="809740">a</span> <span m="809840">method</span>
  <span m="811930">people</span> <span m="812210">have</span> <span m="812450">invented</span>
  <span m="812980">centuries</span> <span m="813420">ago</span> <span m="813750">to</span>
  <span m="814160">solve</span> <span m="814830">such</span> <span m="815250">nonlinear</span>
  <span m="815740">equations</span> <span m="817070">numerically.</span> <span m="819010">All
  right,</span> <span m="819870">any</span> <span m="820220">questions</span> <span
  m="820780">before</span> <span m="821130">we</span> <span m="822530">dive</span>
  <span m="822990">into</span> <span m="823230">stiffness</span> <span m="823790">and</span>
  <span m="823940">using</span> <span m="824425">Raphson?</span></p><p><span m="827340">All
  right.</span> <span m="828148">Stiffness.</span> <span m="830640">The</span> <span
  m="830790">first</span> <span m="831310">[INAUDIBLE]</span> <span m="831740">when</span>
  <span m="831940">we</span> <span m="832170">illustrated</span> <span m="832520">stiffness</span>
  <span m="833306">is</span> <span m="833742">this guy.</span> <span m="835050">So</span>
  <span m="835490">we</span> <span m="836430">did in</span> <span m="836790">the</span>
  <span m="837160">first lecture,</span> <span m="838665">[INAUDIBLE].</span> <span
  m="840440">Right?</span> <span m="841350">And</span> <span m="843170">this</span>
  <span m="843560">is</span> <span m="843730">a</span> <span m="843780">very,</span>
  <span m="844450">very</span> <span m="844700">similar</span> <span m="845165">set</span>
  <span m="845630">up.</span> <span m="845890">And to</span> <span m="846220">remind</span>
  <span m="846670">you,</span> <span m="846860">we</span> <span m="846960">have</span>
  <span m="847140">the</span> <span m="847450">same</span> <span m="847940">[INAUDIBLE]</span>
  <span m="848360">over</span> <span m="848780">here.</span></p><p><span m="849600">But</span>
  <span m="849770">instead</span> <span m="849980">of</span> <span m="850140">an</span>
  <span m="850310">aluminum</span> <span m="850710">cube,</span> <span m="851980">we</span>
  <span m="852120">have</span> <span m="853000">two</span> <span m="853480">metal</span>
  <span m="853950">plates</span> <span m="855765">sticked</span> <span m="856230">together</span>
  <span m="856760">like</span> <span m="857188">[INAUDIBLE].</span> <span m="858900">So</span>
  <span m="859650">this</span> <span m="859770">blue</span> <span m="860060">[INAUDIBLE]</span>
  <span m="860834">is</span> <span m="861221">very</span> <span m="861610">[INAUDIBLE].</span>
  <span m="862860">And</span> <span m="862970">one</span> <span m="863140">is</span>
  <span m="864210">copper,</span> <span m="864530">the</span> <span m="864730">other</span>
  <span m="864910">is</span> <span m="865530">aluminum.</span> <span m="866760">They
  are</span> <span m="866980">2 inch</span> <span m="867430">by 2 inch</span> <span
  m="869730">big.</span> <span m="870180">And</span> <span m="870800">each</span>
  <span m="871000">only</span> <span m="871270">is</span> <span m="871570">a</span>
  <span m="871660">[INAUDIBLE],</span> <span m="874250">so</span> <span m="874520">one</span>
  <span m="874790">aluminum,</span> <span m="875915">one</span> <span m="877056">copper.</span></p><p><span
  m="878810">And</span> <span m="878960">I''m going</span> <span m="879280">to heat</span>
  <span m="880300">only</span> <span m="880890">this</span> <span m="881000">aluminum</span>
  <span m="882360">with</span> <span m="882580">a</span> <span m="882750">heat</span>
  <span m="883310">lamp.</span> <span m="883570">So I''m going</span> <span m="883640">to
  turn</span> <span m="884020">on the heat</span> <span m="884400">lamp.</span> <span
  m="885000">And</span> <span m="885240">there</span> <span m="885380">are</span>
  <span m="885570">two</span> <span m="885720">thermal</span> <span m="885830">[INAUDIBLE]</span>
  <span m="885990">that</span> <span m="886100">matches</span> <span m="886957">the</span>
  <span m="888150">[INAUDIBLE].</span> <span m="892210">What</span> <span m="892680">differential</span>
  <span m="893350">equation</span> <span m="894010">would you</span> <span m="894360">use</span>
  <span m="894860">to</span> <span m="895290">model</span> <span m="897330">this</span>
  <span m="897590">problem?</span></p><p><span m="898790">When</span> <span m="899050">I''m</span>
  <span m="899780">heating</span> <span m="900090">only</span> <span m="900570">the</span>
  <span m="900660">aluminum,</span> <span m="901000">how would</span> <span m="901390">the</span>
  <span m="901890">[INAUDIBLE]</span> <span m="902336">of this</span> <span m="902782">and
  this</span> <span m="904120">going</span> <span m="904330">to</span> <span m="904490">behave?</span>
  <span m="905005">How would</span> <span m="905320">that</span> <span m="906520">be</span>
  <span m="906670">[INAUDIBLE]?</span> <span m="909700">You can</span> <span m="910110">discuss</span>
  <span m="911040">in pairs</span> <span m="911830">or</span> <span m="912320">in</span>
  <span m="912810">groups</span> <span m="913300">of three.</span> <span m="914114">And</span>
  <span m="914578">we''ll</span> <span m="915042">see</span> <span m="915970">really</span>
  <span m="916270">answer</span> <span m="916580">the question</span> <span m="916700">of</span>
  <span m="919900">if</span> <span m="920070">we</span> <span m="920160">want</span>
  <span m="920310">to</span> <span m="920470">predict</span> <span m="920810">it,</span>
  <span m="921490">is</span> <span m="921810">it a</span> <span m="922290">stiff</span>
  <span m="922460">problem?</span> <span m="924690">If</span> <span m="925130">so,</span>
  <span m="925330">why?</span> <span m="925960">If</span> <span m="926280">not,</span>
  <span m="926860">why</span> <span m="927010">not?</span> <span m="928850">You can</span>
  <span m="929340">use</span> <span m="929570">a computer</span> <span m="929710">to
  look</span> <span m="930176">up any</span> <span m="930642">concepts</span> <span
  m="931108">or anything</span> <span m="931574">like that.</span></p><p><span m="933438">You
  can</span> <span m="933904">see</span> <span m="934370">the</span> <span m="934836">two</span>
  <span m="935310">colors,</span> <span m="935870">one</span> <span m="936110">is</span>
  <span m="936400">bronze--</span> <span m="937830">sorry, sorry,</span> <span m="938210">one</span>
  <span m="938530">is copper.</span> <span m="939410">One is</span> <span m="939830">a</span>
  <span m="940250">copper</span> <span m="940670">temperature.</span> <span m="940930">One
  is</span> <span m="941020">a aluminum</span> <span m="941457">temperature.</span>
  <span m="943500">So we</span> <span m="946850">have</span> <span m="947180">some</span>
  <span m="947400">very</span> <span m="947910">good</span> <span m="948160">conclusions</span>
  <span m="948560">here.</span> <span m="949850">Why</span> <span m="950110">don''t</span>
  <span m="950380">you</span> <span m="950600">just</span> <span m="952080">help</span>
  <span m="952355">us</span> <span m="952630">understand</span> <span m="953090">[INAUDIBLE]?</span></p><p><span
  m="961450">AUDIENCE: So</span> <span m="962884">this is</span> <span m="963362">a</span>
  <span m="963840">stuff problem,</span> <span m="964060">because</span> <span m="965200">there
  are</span> <span m="965580">two</span> <span m="966070">different</span> <span m="966410">things
  that</span> <span m="966750">are happening.</span> <span m="966960">We</span> <span
  m="967450">have the</span> <span m="968920">convection,</span> <span m="969480">which</span>
  <span m="969850">we</span> <span m="970220">[INAUDIBLE]</span> <span m="970450">the</span>
  <span m="970890">heat</span> <span m="971330">[INAUDIBLE]</span> <span m="971770">and
  the metal</span> <span m="972220">and then the</span> <span m="972650">metal in</span>
  <span m="972760">the</span> <span m="972880">air,</span> <span m="973250">and</span>
  <span m="973710">then the</span> <span m="974170">conduction</span> <span m="974630">between</span>
  <span m="975080">the</span> <span m="975170">two</span> <span m="975360">metals.</span>
  <span m="977020">The</span> <span m="977500">metals</span> <span m="977660">are</span>
  <span m="977730">both very</span> <span m="978160">conductive.</span> <span m="978830">So</span>
  <span m="979195">that</span> <span m="979560">process</span> <span m="979870">happens</span>
  <span m="980200">much</span> <span m="980530">faster</span> <span m="980830">than</span>
  <span m="981910">the</span> <span m="982030">rate</span> <span m="982340">of</span>
  <span m="982814">convection.</span></p><p><span m="985660">PROFESSOR: All right.</span>
  <span m="986110">Does that</span> <span m="986280">make</span> <span m="986490">sense?</span>
  <span m="991900">All right,</span> <span m="992160">thank</span> <span m="992420">you.</span>
  <span m="994870">So</span> <span m="994950">we</span> <span m="995100">have</span>
  <span m="995380">to</span> <span m="995620">physical</span> <span m="995950">phenomenon,</span>
  <span m="997280">convection</span> <span m="997630">and</span> <span m="997980">conduction.</span>
  <span m="1000620">And</span> <span m="1001280">if</span> <span m="1001480">you''d</span>
  <span m="1003150">think</span> <span m="1003410">carefully,</span> <span m="1003900">the
  two</span> <span m="1003920">metals</span> <span m="1004490">I</span> <span m="1004550">exposed</span>
  <span m="1004970">over</span> <span m="1005250">here,</span> <span m="1007110">within</span>
  <span m="1007520">like</span> <span m="1007910">the</span> <span m="1008080">common</span>
  <span m="1008420">metals,</span> <span m="1008770">are</span> <span m="1009110">the</span>
  <span m="1009400">most</span> <span m="1009890">heat</span> <span m="1010328">conductive</span>
  <span m="1010766">ones</span> <span m="1012080">that you</span> <span m="1012518">can</span>
  <span m="1012960">reasonably</span> <span m="1013290">[INAUDIBLE],</span> <span
  m="1014590">aluminum</span> <span m="1015033">and copper.</span></p><p><span m="1017250">So</span>
  <span m="1018060">I</span> <span m="1018370">deliberately</span> <span m="1019290">made</span>
  <span m="1020730">the rate</span> <span m="1020970">of conduction</span> <span m="1022002">to</span>
  <span m="1022400">be</span> <span m="1022590">very</span> <span m="1023080">fast.</span>
  <span m="1025200">I deliberately</span> <span m="1025790">made</span> <span m="1026010">the</span>
  <span m="1026420">conduction</span> <span m="1026830">to</span> <span m="1027240">be</span>
  <span m="1027380">very</span> <span m="1027640">fast.</span> <span m="1028270">And</span>
  <span m="1028410">I also</span> <span m="1028720">made</span> <span m="1029200">them</span>
  <span m="1029550">very</span> <span m="1029890">thick.</span> <span m="1031802">So
  if</span> <span m="1032280">you</span> <span m="1032560">look</span> <span m="1032829">at--</span>
  <span m="1035420">let me</span> <span m="1035950">start</span> <span m="1037950">writing</span>
  <span m="1038440">some</span> <span m="1038630">equations.</span></p><p><span m="1042880">OK.</span>
  <span m="1043650">So</span> <span m="1043819">if</span> <span m="1044079">you</span>
  <span m="1044630">look</span> <span m="1045050">at</span> <span m="1045810">the</span>
  <span m="1045970">conduction,</span> <span m="1047440">rate</span> <span m="1047700">of</span>
  <span m="1047790">conduction,</span> <span m="1050400">the</span> <span m="1050630">rate</span>
  <span m="1050850">of</span> <span m="1050980">conduction,</span> <span m="1052295">heat</span>
  <span m="1052690">conduction,</span> <span m="1053130">is</span> <span m="1053270">equal</span>
  <span m="1053530">to</span> <span m="1053610">what?</span> <span m="1053870">Can</span>
  <span m="1054130">somebody</span> <span m="1054640">tell</span> <span m="1054830">me?</span>
  <span m="1059680">There</span> <span m="1059900">is</span> <span m="1060020">definitely</span>
  <span m="1060370">a</span> <span m="1060440">k</span> <span m="1060810">somewhere,</span>
  <span m="1062380">the</span> <span m="1062700">conductivity</span> <span m="1066570">times</span>
  <span m="1066940">the</span> <span m="1067030">area</span> <span m="1069240">times</span>
  <span m="1069470">delta</span> <span m="1069590">t</span> <span m="1070120">over</span>
  <span m="1070550">delta--</span> <span m="1071870">in</span> <span m="1072040">this</span>
  <span m="1072210">[INAUDIBLE].</span> <span m="1072790">Let''s</span> <span m="1073020">say</span>
  <span m="1073820">the</span> <span m="1073970">direction</span> <span m="1075240">across</span>
  <span m="1076040">the</span> <span m="1076160">plates</span> <span m="1077100">are</span>
  <span m="1077450">x.</span> <span m="1078310">So</span> <span m="1078610">it</span>
  <span m="1078780">is</span> <span m="1079000">delta</span> <span m="1079458">t over</span>
  <span m="1079916">delta x.</span></p><p><span m="1083580">OK.</span> <span m="1084490">And</span>
  <span m="1088580">changing</span> <span m="1091080">the</span> <span m="1092200">Q-dot</span>
  <span m="1092730">is</span> <span m="1092940">also</span> <span m="1093960">equal</span>
  <span m="1094440">to--</span> <span m="1095270">actually,</span> <span m="1095730">I</span>
  <span m="1095820">shouldn''t</span> <span m="1096120">say</span> <span m="1096460">this.</span>
  <span m="1097050">I should</span> <span m="1097370">say</span> <span m="1100100">the</span>
  <span m="1101630">mass</span> <span m="1102080">of</span> <span m="1102410">each</span>
  <span m="1102920">plate</span> <span m="1104910">times</span> <span m="1105215">the</span>
  <span m="1108240">thermal</span> <span m="1109010">capacitance,</span> <span m="1110940">mc,</span>
  <span m="1111960">times</span> <span m="1112250">the</span> <span m="1116268">partial</span>
  <span m="1116734">T,</span> <span m="1117666">partial</span> <span m="1118132">T.</span>
  <span m="1119070">So</span> <span m="1119140">this</span> <span m="1119320">is</span>
  <span m="1119480">the</span> <span m="1119620">rate</span> <span m="1119950">of</span>
  <span m="1120100">temperature</span> <span m="1120550">change</span> <span m="1121840">is</span>
  <span m="1122160">also</span> <span m="1122590">equal</span> <span m="1123070">to</span>
  <span m="1124190">Q-dot</span> <span m="1125950">convection</span> <span m="1127290">minus</span>
  <span m="1128080">this</span> <span m="1128430">is</span> <span m="1128630">the</span>
  <span m="1128760">conduction,</span> <span m="1131680">Q</span> <span m="1131880">conduction.</span>
  <span m="1132830">So</span> <span m="1133010">this</span> <span m="1133190">is</span>
  <span m="1133350">for</span> <span m="1133620">the</span> <span m="1135150">aluminum</span>
  <span m="1135440">plate.</span></p><p><span m="1138270">And</span> <span m="1138440">if</span>
  <span m="1138560">you</span> <span m="1138670">just</span> <span m="1138960">look</span>
  <span m="1139370">at</span> <span m="1140390">if,</span> <span m="1140780">let''s</span>
  <span m="1141010">say,</span> <span m="1141200">we</span> <span m="1141440">isolate</span>
  <span m="1142040">these</span> <span m="1142240">two</span> <span m="1142680">phenomenons</span>
  <span m="1143690">if</span> <span m="1143890">we</span> <span m="1144050">only</span>
  <span m="1144400">look</span> <span m="1144720">at</span> <span m="1144990">the</span>
  <span m="1145190">conduction,</span> <span m="1146380">what</span> <span m="1146590">we</span>
  <span m="1146750">get</span> <span m="1147040">is</span> <span m="1147330">partial</span>
  <span m="1147830">T</span> <span m="1148330">partial</span> <span m="1148830">T</span>
  <span m="1149330">equal</span> <span m="1149490">to</span> <span m="1150730">kA</span>
  <span m="1152620">divided</span> <span m="1153030">by</span> <span m="1153370">mc</span>
  <span m="1154800">delta</span> <span m="1155150">T</span> <span m="1155500">over</span>
  <span m="1155820">delta</span> <span m="1156120">x.</span> <span m="1157330">So</span>
  <span m="1163140">remember</span> <span m="1163650">our</span> <span m="1163890">eigenvalue</span>
  <span m="1164510">analysis?</span> <span m="1165820">This</span> <span m="1166240">part</span>
  <span m="1167490">would</span> <span m="1167660">become</span> <span m="1168090">our</span>
  <span m="1168890">eigenvalue.</span></p><p><span m="1170260">If</span> <span m="1170770">we</span>
  <span m="1170910">already</span> <span m="1171370">have</span> <span m="1171660">the</span>
  <span m="1172090">conduction</span> <span m="1172360">process,</span> <span m="1173400">then</span>
  <span m="1173830">this</span> <span m="1174180">would</span> <span m="1174360">be</span>
  <span m="1174730">our lambda.</span> <span m="1177790">OK.</span> <span m="1178130">I</span>
  <span m="1178270">think</span> <span m="1178620">I</span> <span m="1178830">get</span>
  <span m="1179020">a</span> <span m="1179060">minus</span> <span m="1179450">sign</span>
  <span m="1180000">here.</span> <span m="1180550">So</span> <span m="1180620">this</span>
  <span m="1180840">will</span> <span m="1180970">be</span> <span m="1181120">our</span>
  <span m="1181310">lambda.</span> <span m="1182000">So</span> <span m="1182160">we</span>
  <span m="1182320">have</span> <span m="1182530">a</span> <span m="1182630">large</span>
  <span m="1183040">k.</span> <span m="1184240">OK</span> <span m="1184480">We</span>
  <span m="1184690">have</span> <span m="1184920">our</span> <span m="1185030">large</span>
  <span m="1185380">A.</span> <span m="1186520">But</span> <span m="1186700">have</span>
  <span m="1186880">a</span> <span m="1186940">large</span> <span m="1187270">[INAUDIBLE]</span>
  <span m="1188466">compared to--</span> <span m="1188830">we</span> <span m="1188970">have</span>
  <span m="1189140">a</span> <span m="1189220">large</span> <span m="1189550">A</span>
  <span m="1189840">compared</span> <span m="1190220">to</span> <span m="1190310">our</span>
  <span m="1190540">delta</span> <span m="1190640">x,</span> <span m="1191580">two</span>
  <span m="1191750">[INAUDIBLE].</span></p><p><span m="1194630">So</span> <span m="1194830">we</span>
  <span m="1195110">have</span> <span m="1195510">deliberately</span> <span m="1196150">made</span>
  <span m="1196570">these</span> <span m="1196970">to be</span> <span m="1197320">large.</span>
  <span m="1198680">And</span> <span m="1199150">if</span> <span m="1199670">you</span>
  <span m="1199780">plug in</span> <span m="1200230">the</span> <span m="1200300">numbers,</span>
  <span m="1200830">this</span> <span m="1201170">is</span> <span m="1202160">significantly</span>
  <span m="1202920">larger,</span> <span m="1204192">about</span> <span m="1204570">one</span>
  <span m="1204910">to</span> <span m="1205230">two</span> <span m="1205560">orders</span>
  <span m="1206190">of</span> <span m="1206430">magnitude</span> <span m="1206670">larger</span>
  <span m="1207720">than</span> <span m="1208130">the</span> <span m="1208340">forced</span>
  <span m="1209120">convection</span> <span m="1209680">rate</span> <span m="1210660">[INAUDIBLE]</span>
  <span m="1211460">table.</span> <span m="1214030">So</span> <span m="1214240">this</span>
  <span m="1215530">is</span> <span m="1215620">a</span> <span m="1215770">stiff</span>
  <span m="1216090">process</span> <span m="1217220">in</span> <span m="1217440">terms</span>
  <span m="1217700">of</span> <span m="1218010">physics,</span> <span m="1218810">because</span>
  <span m="1219280">we</span> <span m="1219470">have</span> <span m="1219750">a</span>
  <span m="1219830">very</span> <span m="1220320">fast</span> <span m="1220710">speed</span>
  <span m="1220960">conduction</span> <span m="1221690">and</span> <span m="1221960">a</span>
  <span m="1222040">relatively</span> <span m="1222670">slow</span> <span m="1222950">speed</span>
  <span m="1223230">convection.</span></p><p><span m="1226510">In</span> <span m="1226770">terms</span>
  <span m="1227000">of</span> <span m="1227150">mathematics,</span> <span m="1228410">let</span>
  <span m="1228630">me</span> <span m="1228740">say</span> <span m="1229440">this</span>
  <span m="1229760">is</span> <span m="1229910">the</span> <span m="1230140">aluminum.</span>
  <span m="1232630">This</span> <span m="1232980">is</span> <span m="1233460">delta</span>
  <span m="1233660">squared</span> <span m="1234130">delta</span> <span m="1234490">T</span>
  <span m="1235160">is</span> <span m="1235450">equal</span> <span m="1235930">to</span>
  <span m="1236120">the</span> <span m="1236620">T</span> <span m="1236880">aluminum</span>
  <span m="1237540">minus</span> <span m="1238040">T</span> <span m="1238934">copper.</span>
  <span m="1241970">So</span> <span m="1242120">we</span> <span m="1242350">have</span>
  <span m="1243774">m</span> <span m="1244640">aluminum</span> <span m="1245400">c</span>
  <span m="1245690">of</span> <span m="1245860">aluminum</span> <span m="1246220">equal</span>
  <span m="1246580">to</span> <span m="1246940">this.</span> <span m="1247750">And</span>
  <span m="1248030">we</span> <span m="1248230">have</span> <span m="1248550">aluminum</span>
  <span m="1249530">equal</span> <span m="1250420">to,</span> <span m="1250570">let
  me</span> <span m="1250650">say--</span> <span m="1252030">and</span> <span m="1252360">let''s</span>
  <span m="1252970">set</span> <span m="1253210">this</span> <span m="1253380">k</span>
  <span m="1253620">to</span> <span m="1253740">be</span> <span m="1253860">the</span>
  <span m="1253970">average</span> <span m="1255640">rate</span> <span m="1255910">of</span>
  <span m="1256000">conductivity</span> <span m="1257270">in</span> <span m="1257510">the</span>
  <span m="1257660">aluminum</span> <span m="1258180">and</span> <span m="1258330">the</span>
  <span m="1258390">copper.</span></p><p><span m="1259100">So</span> <span m="1259240">we</span>
  <span m="1259390">replaced</span> <span m="1260000">our</span> <span m="1260210">delta</span>
  <span m="1260595">T</span> <span m="1263610">by</span> <span m="1265150">TA</span>
  <span m="1265990">minus</span> <span m="1266520">Tc.</span> <span m="1268830">All</span>
  <span m="1269000">right.</span> <span m="1269230">So</span> <span m="1269370">this</span>
  <span m="1269570">is</span> <span m="1270500">conduction.</span> <span m="1271450">And</span>
  <span m="1271850">we</span> <span m="1271970">also</span> <span m="1272360">have</span>
  <span m="1272980">convection.</span> <span m="1276130">And</span> <span m="1276320">the</span>
  <span m="1276410">rate</span> <span m="1276600">of</span> <span m="1276690">convection,</span>
  <span m="1277015">can</span> <span m="1277340">somebody</span> <span m="1277610">tell</span>
  <span m="1277820">me</span> <span m="1277930">what</span> <span m="1278210">the</span>
  <span m="1278310">rate</span> <span m="1278510">of</span> <span m="1278760">convection</span>
  <span m="1279120">is?</span></p><p><span m="1284490">We</span> <span m="1284680">have</span>
  <span m="1285120">the</span> <span m="1286490">convection</span> <span m="1287040">coefficient</span>
  <span m="1288050">times</span> <span m="1288540">A,</span> <span m="1288977">area--</span>
  <span m="1290490">sorry--</span> <span m="1293830">times</span> <span m="1294190">the</span>
  <span m="1294290">difference</span> <span m="1294780">between</span> <span m="1297450">the</span>
  <span m="1297670">T</span> <span m="1298070">error.</span> <span m="1298660">So</span>
  <span m="1298820">let</span> <span m="1298960">me</span> <span m="1299070">just</span>
  <span m="1299570">say</span> <span m="1299960">to</span> <span m="1300720">[INAUDIBLE]</span>
  <span m="1301100">T</span> <span m="1301670">error</span> <span m="1303190">minus</span>
  <span m="1303660">T</span> <span m="1304040">aluminum</span> <span m="1305570">and</span>
  <span m="1306160">divided</span> <span m="1306760">by</span> <span m="1307790">aluminum</span>
  <span m="1308620">mass</span> <span m="1309190">and</span> <span m="1310040">the
  heat</span> <span m="1310540">capacitance.</span> <span m="1311780">And</span> <span
  m="1312460">our</span> <span m="1313350">copper</span> <span m="1314260">is</span>
  <span m="1314630">going</span> <span m="1314780">to</span> <span m="1314870">satisfy</span>
  <span m="1315430">a</span> <span m="1315530">similar</span> <span m="1316010">equation,</span>
  <span m="1316680">where</span> <span m="1317100">the</span> <span m="1319140">heat</span>
  <span m="1319350">conduction</span> <span m="1319890">is</span> <span m="1320130">the</span>
  <span m="1320230">same.</span> <span m="1320900">So</span> <span m="1321220">what</span>
  <span m="1321390">this</span> <span m="1321540">is</span> <span m="1323624">c</span>
  <span m="1324100">instead.</span> <span m="1325710">And</span> <span m="1326050">we</span>
  <span m="1326310">have</span> <span m="1326570">TA</span> <span m="1327090">minus</span>
  <span m="1327330">TC</span> <span m="1327835">here</span> <span m="1328380">divided</span>
  <span m="1329010">by</span> <span m="1329190">delta</span> <span m="1329310">x.</span></p><p><span
  m="1330310">And</span> <span m="1330530">here</span> <span m="1330900">we</span>
  <span m="1331180">have</span> <span m="1331790">a</span> <span m="1331940">removal</span>
  <span m="1332460">of</span> <span m="1332810">heat.</span> <span m="1335830">So</span>
  <span m="1336030">this</span> <span m="1336190">is</span> <span m="1336320">hot</span>
  <span m="1336640">air.</span> <span m="1337420">And</span> <span m="1337780">we</span>
  <span m="1337920">have</span> <span m="1338110">a</span> <span m="1338200">removal</span>
  <span m="1338730">of</span> <span m="1338940">heat.</span> <span m="1340110">Cold</span>
  <span m="1340570">air</span> <span m="1342330">divided</span> <span m="1342660">by</span>
  <span m="1343310">Mc</span> <span m="1343715">Cc.</span> <span m="1345770">OK.</span></p><p><span
  m="1346600">So</span> <span m="1347470">as you''re</span> <span m="1347890">going
  to see,</span> <span m="1348840">we</span> <span m="1348990">are going</span> <span
  m="1349130">to get</span> <span m="1349840">a</span> <span m="1350020">2 by 2</span>
  <span m="1350420">matrix.</span> <span m="1354000">We are</span> <span m="1354070">going</span>
  <span m="1354190">to</span> <span m="1354260">get</span> <span m="1354440">a</span>
  <span m="1354500">2</span> <span m="1354700">by</span> <span m="1354840">2</span>
  <span m="1355020">matrix.</span> <span m="1356080">And</span> <span m="1356200">the</span>
  <span m="1356270">2</span> <span m="1356440">by</span> <span m="1356590">2</span>
  <span m="1356770">matrix</span> <span m="1359100">is</span> <span m="1359390">going</span>
  <span m="1359570">to</span> <span m="1359710">have</span> <span m="1362470">the</span>
  <span m="1362590">2</span> <span m="1362770">by</span> <span m="1362920">2</span>
  <span m="1363130">matrix.</span> <span m="1363830">We</span> <span m="1364050">write</span>
  <span m="1364300">down</span> <span m="1365150">the</span> <span m="1365640">T of</span>
  <span m="1366400">the</span> <span m="1366790">aluminum</span> <span m="1367350">temperature</span>
  <span m="1368110">and</span> <span m="1368740">copper</span> <span m="1369280">temperature</span>
  <span m="1370220">is</span> <span m="1370580">going</span> <span m="1370740">to</span>
  <span m="1370800">be</span> <span m="1370900">equal</span> <span m="1371220">to</span>
  <span m="1371530">if</span> <span m="1371800">you</span> <span m="1372060">regroup</span>
  <span m="1372580">the</span> <span m="1372670">terms.</span></p><p><span m="1373690">And</span>
  <span m="1374980">we</span> <span m="1375220">know</span> <span m="1375530">that</span>
  <span m="1376490">this</span> <span m="1376970">term</span> <span m="1378270">is</span>
  <span m="1378600">going</span> <span m="1378780">to</span> <span m="1378860">be</span>
  <span m="1379120">large.</span> <span m="1380650">So</span> <span m="1381050">let</span>
  <span m="1381230">me</span> <span m="1381340">call</span> <span m="1381710">this</span>
  <span m="1383620">big</span> <span m="1383950">A.</span> <span m="1385230">And</span>
  <span m="1386070">these</span> <span m="1386430">terms</span> <span m="1386770">are</span>
  <span m="1386850">going</span> <span m="1386970">to</span> <span m="1387030">be</span>
  <span m="1387120">small.</span> <span m="1389970">Let</span> <span m="1390550">me</span>
  <span m="1390650">color</span> <span m="1391180">these</span> <span m="1391590">small</span>
  <span m="1391860">terms</span> <span m="1392090">by</span> <span m="1392563">blue.</span></p><p><span
  m="1393510">OK.</span> <span m="1393870">So</span> <span m="1394070">this</span>
  <span m="1394330">term</span> <span m="1394610">is</span> <span m="1394760">going</span>
  <span m="1394910">to</span> <span m="1394980">be</span> <span m="1395890">small.</span>
  <span m="1396800">This</span> <span m="1397150">term</span> <span m="1397630">is</span>
  <span m="1397850">going</span> <span m="1397980">to</span> <span m="1398050">be</span>
  <span m="1398160">small.</span> <span m="1399310">And</span> <span m="1399625">let</span>
  <span m="1399940">me</span> <span m="1400355">color</span> <span m="1400770">the</span>
  <span m="1400860">last</span> <span m="1401570">terms in</span> <span m="1401790">red.</span>
  <span m="1402840">So</span> <span m="1403080">this</span> <span m="1403400">term</span>
  <span m="1403780">is</span> <span m="1404070">going</span> <span m="1404220">to</span>
  <span m="1404300">be</span> <span m="1404650">large.</span></p><p><span m="1407700">So</span>
  <span m="1408890">let</span> <span m="1409100">me</span> <span m="1409190">just</span>
  <span m="1409620">write</span> <span m="1410470">qualitatively</span> <span m="1411260">here.</span>
  <span m="1411840">We</span> <span m="1412070">have</span> <span m="1412360">a</span>
  <span m="1412570">minus</span> <span m="1413180">large</span> <span m="1413580">term</span>
  <span m="1414180">over</span> <span m="1414420">here</span> <span m="1415960">and</span>
  <span m="1416580">a</span> <span m="1416810">minus</span> <span m="1417380">small</span>
  <span m="1417805">term</span> <span m="1419930">minus</span> <span m="1420520">a</span>
  <span m="1422010">small</span> <span m="1422430">term</span> <span m="1423360">in</span>
  <span m="1423810">blue.</span> <span m="1425100">So</span> <span m="1425390">this</span>
  <span m="1425660">is</span> <span m="1425880">a</span> <span m="1426020">multiplied</span>
  <span m="1426780">by</span> <span m="1429060">Ta</span> <span m="1430020">and</span>
  <span m="1430430">the</span> <span m="1430520">Tc.</span></p><p><span m="1433790">So</span>
  <span m="1434020">on</span> <span m="1434210">top</span> <span m="1434450">of</span>
  <span m="1434620">Ta,</span> <span m="1434970">we</span> <span m="1435150">have</span>
  <span m="1435360">a</span> <span m="1435620">negative</span> <span m="1436260">large</span>
  <span m="1436600">term</span> <span m="1436760">and</span> <span m="1436820">negative</span>
  <span m="1437380">small</span> <span m="1437610">term.</span> <span m="1439300">On</span>
  <span m="1439580">top</span> <span m="1439930">of</span> <span m="1440200">Tc</span>
  <span m="1440950">here,</span> <span m="1441280">we</span> <span m="1441540">have</span>
  <span m="1441820">a</span> <span m="1443900">plus</span> <span m="1444630">large
  term.</span> <span m="1446280">And</span> <span m="1446540">in</span> <span m="1446640">the</span>
  <span m="1446730">second</span> <span m="1447040">equation,</span> <span m="1447480">the</span>
  <span m="1447560">evolution</span> <span m="1448240">of</span> <span m="1448400">the</span>
  <span m="1448480">copper</span> <span m="1448860">temperature,</span> <span m="1449470">we</span>
  <span m="1449850">have</span> <span m="1450400">a</span> <span m="1452170">large</span>
  <span m="1452570">term</span> <span m="1453410">in front</span> <span m="1453650">of</span>
  <span m="1453900">here</span> <span m="1454750">and</span> <span m="1455370">nothing</span>
  <span m="1456630">in</span> <span m="1456830">the</span> <span m="1458210">small</span>
  <span m="1458520">term.</span> <span m="1459760">And</span> <span m="1460090">in</span>
  <span m="1460180">terms</span> <span m="1460610">of the</span> <span m="1460980">copper</span>
  <span m="1461380">temperature,</span> <span m="1461880">we</span> <span m="1462070">have
  a</span> <span m="1462460">minus</span> <span m="1462970">large term</span> <span
  m="1464550">and</span> <span m="1464820">a</span> <span m="1465090">minus</span>
  <span m="1465690">small term.</span></p><p><span m="1470320">So</span> <span m="1471060">the</span>
  <span m="1471210">matrix</span> <span m="1472220">looks</span> <span m="1472500">like</span>
  <span m="1472710">this.</span> <span m="1475580">That''s</span> <span m="1475800">how</span>
  <span m="1475960">the</span> <span m="1476050">matrix</span> <span m="1476470">would</span>
  <span m="1476620">look</span> <span m="1476920">like</span> <span m="1480810">when</span>
  <span m="1481350">you</span> <span m="1481480">write</span> <span m="1481680">these</span>
  <span m="1481860">two</span> <span m="1482000">equations</span> <span m="1482590">in</span>
  <span m="1482730">terms</span> <span m="1483065">of</span> <span m="1483400">matrix</span>
  <span m="1483840">form.</span> <span m="1488150">Now,</span> <span m="1488510">if</span>
  <span m="1488750">you</span> <span m="1488910">do</span> <span m="1489130">the</span>
  <span m="1489260">eigenvalue</span> <span m="1489910">analysis</span> <span m="1490910">of</span>
  <span m="1491180">a</span> <span m="1491250">matrix</span> <span m="1492310">that</span>
  <span m="1492470">looks</span> <span m="1492680">like</span> <span m="1492870">this,</span>
  <span m="1496070">you</span> <span m="1496600">can</span> <span m="1496810">take</span>
  <span m="1497160">the--</span> <span m="1499290">what</span> <span m="1499540">happens</span>
  <span m="1499880">to</span> <span m="1500010">the</span> <span m="1500130">eigenvalue</span>
  <span m="1500750">if</span> <span m="1501210">S</span> <span m="1502050">infinitesimally</span>
  <span m="1502990">small</span> <span m="1503449">compared</span> <span m="1503908">to
  L?</span> <span m="1507580">Let''s</span> <span m="1507790">say</span> <span m="1507870">what</span>
  <span m="1508070">is</span> <span m="1508230">the</span> <span m="1508380">eigenvalue</span>
  <span m="1509710">of</span> <span m="1510110">minus</span> <span m="1510510">L,</span>
  <span m="1510860">minus</span> <span m="1511310">L,</span> <span m="1512060">L and</span>
  <span m="1512310">L?</span></p><p><span m="1521594">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="1524460">PROFESSOR: Yes.</span> <span m="1525020">Or</span> <span m="1525360">it</span>
  <span m="1525530">is</span> <span m="1525790">L,</span> <span m="1526130">because</span>
  <span m="1526410">eigenvalues</span> <span m="1527090">are</span> <span m="1527220">linear.</span>
  <span m="1527654">It''s</span> <span m="1528088">an L</span> <span m="1528522">times
  the</span> <span m="1528956">eigenvalue</span> <span m="1529390">of</span> <span
  m="1530260">this</span> <span m="1530520">matrix.</span> <span m="1532213">And what</span>
  <span m="1532674">is the eigenvalue</span> <span m="1533135">of</span> <span m="1533600">that</span>
  <span m="1533790">matrix?</span> <span m="1534474">We</span> <span m="1534948">can
  try to--</span></p><p><span m="1535422">AUDIENCE: Well,</span> <span m="1535896">at
  least</span> <span m="1536370">one of them</span> <span m="1536844">[INAUDIBLE].</span></p><p><span
  m="1543010">PROFESSOR: OK.</span> <span m="1543370">At</span> <span m="1543540">least</span>
  <span m="1543670">one</span> <span m="1543860">of</span> <span m="1543950">them</span>
  <span m="1544120">are 0.</span> <span m="1544550">Because</span> <span m="1544930">this</span>
  <span m="1545100">matrix</span> <span m="1545480">is</span> <span m="1545580">[INAUDIBLE],</span>
  <span m="1545830">right?</span> <span m="1546530">The</span> <span m="1546650">first</span>
  <span m="1546970">line is</span> <span m="1547430">negative</span> <span m="1547840">of
  the</span> <span m="1547940">second line.</span> <span m="1550630">What about</span>
  <span m="1551050">the</span> <span m="1551090">other</span> <span m="1551340">one?</span></p><p><span
  m="1551470">AUDIENCE: 0 minus 2.</span></p><p><span m="1552740">PROFESSOR: 0</span>
  <span m="1553110">minus</span> <span m="1553670">2</span> <span m="1553930">exactly.</span>
  <span m="1557380">Wait,</span> <span m="1557660">is</span> <span m="1557800">it</span>
  <span m="1557900">minus</span> <span m="1558300">2?</span> <span m="1559300">Yes,</span>
  <span m="1559590">it</span> <span m="1559740">is</span> <span m="1559840">minus</span>
  <span m="1560130">2.</span> <span m="1560580">OK.</span> <span m="1561110">So</span>
  <span m="1561320">it</span> <span m="1561440">is</span> <span m="1561640">0</span>
  <span m="1562500">or</span> <span m="1563040">minus</span> <span m="1563450">2,</span>
  <span m="1564180">right?</span> <span m="1565480">Minus</span> <span m="1565790">2L.</span>
  <span m="1566560">So</span> <span m="1567090">you</span> <span m="1567250">can</span>
  <span m="1567430">see</span> <span m="1567670">the</span> <span m="1567830">eigenvalues,</span>
  <span m="1569090">one</span> <span m="1569370">of</span> <span m="1569520">them</span>
  <span m="1569710">is</span> <span m="1569890">0.</span> <span m="1570350">The</span>
  <span m="1570500">other</span> <span m="1570730">is</span> <span m="1570890">minus
  2.</span></p><p><span m="1572600">And</span> <span m="1572800">if</span> <span m="1573030">you</span>
  <span m="1573890">add</span> <span m="1574380">these</span> <span m="1575020">small
  terms</span> <span m="1576190">the</span> <span m="1576370">eigenvalue--</span>
  <span m="1578510">because</span> <span m="1579790">the</span> <span m="1579950">small</span>
  <span m="1580230">items</span> <span m="1580590">are</span> <span m="1580700">just</span>
  <span m="1581240">minus</span> <span m="1581970">S</span> <span m="1582340">on</span>
  <span m="1582660">the</span> <span m="1582780">diagonal,</span> <span m="1583883">right?</span>
  <span m="1584930">So</span> <span m="1585080">how</span> <span m="1585310">do</span>
  <span m="1585430">they</span> <span m="1585590">affect</span> <span m="1586240">the</span>
  <span m="1586430">eigenvalues?</span> <span m="1587110">It''s</span> <span m="1587876">a</span>
  <span m="1588260">test</span> <span m="1588630">to your</span> <span m="1589111">linear
  algebra.</span></p><p><span m="1590554">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="1592960">PROFESSOR: It</span> <span m="1593150">is</span> <span m="1593400">going</span>
  <span m="1593590">to</span> <span m="1593750">be</span> <span m="1593860">put a</span>
  <span m="1594240">minus</span> <span m="1594600">S</span> <span m="1594920">on</span>
  <span m="1595160">both</span> <span m="1595440">of</span> <span m="1595540">the</span>
  <span m="1595670">eigenvalues.</span> <span m="1599430">It is</span> <span m="1599890">the</span>
  <span m="1600010">eigenvalue</span> <span m="1600660">of an</span> <span m="1600940">identity</span>
  <span m="1601390">matrix</span> <span m="1601860">times</span> <span m="1602314">S</span>
  <span m="1602768">times</span> <span m="1603222">minus S.</span> <span m="1604130">The</span>
  <span m="1604260">eigenvalues</span> <span m="1604880">of</span> <span m="1605100">identity</span>
  <span m="1605540">matrix</span> <span m="1605950">is</span> <span m="1611770">1,</span>
  <span m="1613150">right?</span> <span m="1615970">So</span> <span m="1617500">let</span>
  <span m="1617660">me</span> <span m="1617780">see--</span> <span m="1618250">[INAUDIBLE].</span>
  <span m="1624360">I''m</span> <span m="1624530">not</span> <span m="1624730">sure.</span>
  <span m="1625180">Let</span> <span m="1625310">me</span> <span m="1625420">take</span>
  <span m="1625640">it</span> <span m="1625730">back.</span> <span m="1626060">I''m</span>
  <span m="1626270">not</span> <span m="1626470">sure</span> <span m="1626600">exactly</span>
  <span m="1627130">what</span> <span m="1627608">the</span> <span m="1628086">eigenvalues</span>
  <span m="1629042">are.</span></p><p><span m="1631440">OK.</span> <span m="1632250">So</span>
  <span m="1632580">when</span> <span m="1632940">I''m</span> <span m="1633120">adding</span>
  <span m="1633530">a</span> <span m="1633830">[INAUDIBLE]</span> <span m="1634020">matrix,</span>
  <span m="1634550">I''m</span> <span m="1634760">basically</span> <span m="1635170">perturbing</span>
  <span m="1635780">this</span> <span m="1636050">by</span> <span m="1636640">minus</span>
  <span m="1637040">S.</span> <span m="1639500">So</span> <span m="1639680">this</span>
  <span m="1639970">is</span> <span m="1640520">going</span> <span m="1640680">to</span>
  <span m="1640760">be</span> <span m="1640900">my</span> <span m="1641070">eigenvalues.</span>
  <span m="1642200">And</span> <span m="1642490">because</span> <span m="1642820">I</span>
  <span m="1642990">have</span> <span m="1643270">a</span> <span m="1643440">small</span>
  <span m="1643740">eigenvalue,</span> <span m="1644260">I</span> <span m="1644450">have</span>
  <span m="1644630">a</span> <span m="1644720">large</span> <span m="1645000">eigenvalue,</span>
  <span m="1645620">I would</span> <span m="1646108">get</span> <span m="1646596">a</span>
  <span m="1647084">[INAUDIBLE].</span></p><p><span m="1650770">So</span> <span m="1650920">basically,</span>
  <span m="1651310">we</span> <span m="1651450">are</span> <span m="1651530">looking</span>
  <span m="1651920">at</span> <span m="1652900">the</span> <span m="1652990">example</span>
  <span m="1653560">of</span> <span m="1653740">a</span> <span m="1654005">[INAUDIBLE]</span>
  <span m="1654560">problem.</span> <span m="1655480">We</span> <span m="1655640">can</span>
  <span m="1655770">analyze</span> <span m="1656420">from</span> <span m="1656770">the</span>
  <span m="1657130">perspective</span> <span m="1657840">of</span> <span m="1657990">physics.</span>
  <span m="1658580">We</span> <span m="1658800">have</span> <span m="1659020">a</span>
  <span m="1659160">fast</span> <span m="1659720">conduction</span> <span m="1660330">of</span>
  <span m="1660570">slow</span> <span m="1660980">convection.</span> <span m="1662060">And</span>
  <span m="1662140">if</span> <span m="1662280">we</span> <span m="1662430">put</span>
  <span m="1662690">these</span> <span m="1663090">physically</span> <span m="1663520">into</span>
  <span m="1664080">equations</span> <span m="1664750">and</span> <span m="1664970">analyze</span>
  <span m="1665430">the</span> <span m="1665560">eigenvalues,</span> <span m="1666540">we</span>
  <span m="1666680">can</span> <span m="1666900">get</span> <span m="1669290">a</span>
  <span m="1669440">slow</span> <span m="1669790">eigenvalue</span> <span m="1671120">and</span>
  <span m="1671400">a</span> <span m="1672190">fast</span> <span m="1673400">eigenvalue.</span></p><p><span
  m="1676380">The</span> <span m="1676580">orders</span> <span m="1677090">of</span>
  <span m="1677230">magnitude</span> <span m="1677820">difference</span> <span m="1678250">in</span>
  <span m="1678320">eigenvalues</span> <span m="1679020">is</span> <span m="1679360">also</span>
  <span m="1679810">going to indicate</span> <span m="1681020">the</span> <span m="1681130">system</span>
  <span m="1681520">is</span> <span m="1681660">going</span> <span m="1681800">to</span>
  <span m="1681870">be</span> <span m="1682140">stiff.</span> <span m="1684864">Questions
  on</span> <span m="1685320">this?</span> <span m="1685740">Maybe</span> <span m="1687780">you</span>
  <span m="1687970">don''t</span> <span m="1688450">quite</span> <span m="1688690">get</span>
  <span m="1688900">through</span> <span m="1689080">the</span> <span m="1689170">mathematics,</span>
  <span m="1689840">but</span> <span m="1692590">it</span> <span m="1692740">is</span>
  <span m="1693000">going</span> <span m="1693130">to</span> <span m="1693210">be</span>
  <span m="1693480">leading</span> <span m="1693820">to</span> <span m="1693920">the</span>
  <span m="1694040">same</span> <span m="1694310">conclusion.</span></p><p><span m="1697810">AUDIENCE:
  Does the name</span> <span m="1698310">derive</span> <span m="1698810">from</span>
  <span m="1699310">[INAUDIBLE]?</span></p><p><span m="1701810">PROFESSOR: Good</span>
  <span m="1702010">question.</span> <span m="1702490">Does the</span> <span m="1702880">name</span>
  <span m="1703340">derive</span> <span m="1703420">from</span> <span m="1704592">stiff</span>
  <span m="1704990">springs?</span> <span m="1707610">So</span> <span m="1707700">let</span>
  <span m="1707860">me</span> <span m="1707950">actually</span> <span m="1708380">give</span>
  <span m="1708670">you--</span> <span m="1709890">the</span> <span m="1710010">answer</span>
  <span m="1710290">is</span> <span m="1710440">yes.</span> <span m="1711060">The</span>
  <span m="1711210">name</span> <span m="1711500">does</span> <span m="1711750">derive</span>
  <span m="1712100">from</span> <span m="1712570">stiff</span> <span m="1712870">springs.</span></p><p><span
  m="1713710">And</span> <span m="1714130">it''s</span> <span m="1714740">actually</span>
  <span m="1715070">going</span> <span m="1715260">to</span> <span m="1715340">be</span>
  <span m="1715480">a</span> <span m="1715580">homework</span> <span m="1716020">question.</span>
  <span m="1716500">But</span> <span m="1716690">like</span> <span m="1716960">I</span>
  <span m="1717470">can</span> <span m="1717920">kind</span> <span m="1718100">of</span>
  <span m="1718545">hint</span> <span m="1718820">you</span> <span m="1719470">a</span>
  <span m="1719580">little</span> <span m="1719830">bit</span> <span m="1720970">right</span>
  <span m="1721300">now.</span> <span m="1723200">So</span> <span m="1723380">what</span>
  <span m="1723580">if</span> <span m="1723720">you</span> <span m="1723850">have</span>
  <span m="1724010">a</span> <span m="1724090">system</span> <span m="1724440">like</span>
  <span m="1724650">this?</span> <span m="1730520">What</span> <span m="1730600">if</span>
  <span m="1730750">you</span> <span m="1730840">have</span> <span m="1731080">a</span>
  <span m="1731170">system</span> <span m="1731570">like</span> <span m="1731800">this?</span></p><p><span
  m="1732060">Instead</span> <span m="1732430">of</span> <span m="1732600">a</span>
  <span m="1733060">thermal</span> <span m="1733400">problem,</span> <span m="1733950">let''s</span>
  <span m="1734400">think</span> <span m="1734700">of</span> <span m="1734990">a</span>
  <span m="1735950">pendulum.</span> <span m="1737820">So a</span> <span m="1737920">pendulum</span>
  <span m="1738500">is</span> <span m="1739100">we</span> <span m="1739390">have</span>
  <span m="1739890">a</span> <span m="1740000">mass</span> <span m="1740560">over</span>
  <span m="1740870">here,</span> <span m="1741230">right?</span> <span m="1742190">And</span>
  <span m="1744040">a</span> <span m="1744180">regular</span> <span m="1745030">pendulum</span>
  <span m="1746190">would</span> <span m="1746390">have an</span> <span m="1746720">inelastic</span>
  <span m="1749156">string</span> <span m="1749640">attached</span> <span m="1750240">to</span>
  <span m="1750360">the</span> <span m="1750440">mass.</span></p><p><span m="1751650">But</span>
  <span m="1751860">what</span> <span m="1752080">if</span> <span m="1752240">you</span>
  <span m="1752360">think</span> <span m="1752700">of</span> <span m="1752930">you</span>
  <span m="1753100">have</span> <span m="1753610">a</span> <span m="1755650">spring</span>
  <span m="1756250">here,</span> <span m="1757320">so</span> <span m="1757510">that</span>
  <span m="1758150">the</span> <span m="1758290">distance</span> <span m="1758940">between</span>
  <span m="1759310">the</span> <span m="1759450">hinge</span> <span m="1759880">and</span>
  <span m="1760050">the</span> <span m="1760110">mass</span> <span m="1760580">can</span>
  <span m="1761010">actually</span> <span m="1761790">become</span> <span m="1762170">longer
  or</span> <span m="1762590">shorter.</span> <span m="1767420">So</span> <span m="1767590">if</span>
  <span m="1767790">you</span> <span m="1767920">have</span> <span m="1768070">a</span>
  <span m="1768140">system</span> <span m="1768450">like</span> <span m="1768670">this,</span>
  <span m="1770130">in</span> <span m="1770340">what</span> <span m="1770590">condition--</span>
  <span m="1771210">so</span> <span m="1771260">let''s</span> <span m="1771480">say</span>
  <span m="1771730">the</span> <span m="1771890">stiffness</span> <span m="1772410">of</span>
  <span m="1772610">the</span> <span m="1772710">spring</span> <span m="1772950">is</span>
  <span m="1773270">K.</span> <span m="1775500">Would</span> <span m="1775760">you</span>
  <span m="1775980">have</span> <span m="1776420">a</span> <span m="1777640">stiff</span>
  <span m="1778040">system</span> <span m="1779980">in</span> <span m="1780140">terms</span>
  <span m="1780360">of</span> <span m="1780530">ODEs?</span> <span m="1781220">Or</span>
  <span m="1781540">you</span> <span m="1781900">have</span> <span m="1782170">a</span>
  <span m="1782260">non-stiff</span> <span m="1782610">system?</span></p><p><span
  m="1783220">In</span> <span m="1783390">what</span> <span m="1783630">condition</span>
  <span m="1784070">would</span> <span m="1784170">you</span> <span m="1784280">have</span>
  <span m="1784420">a stiff</span> <span m="1784590">system?</span> <span m="1785180">In</span>
  <span m="1785270">what</span> <span m="1785550">condition</span> <span m="1785810">would
  you</span> <span m="1786180">have</span> <span m="1786320">a</span> <span m="1786450">non-stiff</span>
  <span m="1786680">system.</span></p><p><span m="1788420">AUDIENCE: [INAUDIBLE]</span>
  <span m="1789800">stiffness</span> <span m="1790260">[INAUDIBLE].</span></p><p><span
  m="1791180">PROFESSOR: It</span> <span m="1791280">depends</span> <span m="1791545">on
  the</span> <span m="1791810">stiffness</span> <span m="1792270">of</span> <span
  m="1792430">the</span> <span m="1792530">spring,</span> <span m="1792990">exactly.</span>
  <span m="1793490">We</span> <span m="1793610">have</span> <span m="1793860">two</span>
  <span m="1794250">physical</span> <span m="1794890">processes</span> <span m="1795500">over</span>
  <span m="1795730">here.</span> <span m="1795960">One</span> <span m="1796270">is</span>
  <span m="1796610">the</span> <span m="1797050">motion</span> <span m="1797550">of</span>
  <span m="1797740">the</span> <span m="1797820">pendulum</span> <span m="1798140">driven</span>
  <span m="1798860">by</span> <span m="1799020">gravity.</span> <span m="1800130">The</span>
  <span m="1800350">other</span> <span m="1800720">is</span> <span m="1801200">the</span>
  <span m="1801370">oscillation</span> <span m="1802020">of</span> <span m="1802150">the</span>
  <span m="1802270">spring.</span></p><p><span m="1804110">If</span> <span m="1804350">the</span>
  <span m="1804460">spring</span> <span m="1804770">is</span> <span m="1804920">very</span>
  <span m="1805370">stiff,</span> <span m="1807450">then</span> <span m="1807660">the</span>
  <span m="1807720">frequency</span> <span m="1808330">of</span> <span m="1808460">the</span>
  <span m="1808540">oscillation</span> <span m="1811290">is going</span> <span m="1811720">to</span>
  <span m="1811910">be</span> <span m="1812010">very</span> <span m="1812290">high,</span>
  <span m="1813680">which</span> <span m="1813900">means</span> <span m="1814230">the</span>
  <span m="1814360">timescale</span> <span m="1815060">of</span> <span m="1815260">the</span>
  <span m="1816190">oscillation</span> <span m="1816920">is</span> <span m="1817220">going</span>
  <span m="1817390">to</span> <span m="1817470">be</span> <span m="1817560">much</span>
  <span m="1817860">faster</span> <span m="1819010">than</span> <span m="1819500">the</span>
  <span m="1819650">motion</span> <span m="1820030">of</span> <span m="1820140">the</span>
  <span m="1820230">pendulum</span> <span m="1820890">due</span> <span m="1821060">to</span>
  <span m="1821200">gravity.</span> <span m="1823230">And</span> <span m="1823550">then</span>
  <span m="1823630">we</span> <span m="1823810">get</span> <span m="1824220">two</span>
  <span m="1824570">very</span> <span m="1824870">different</span> <span m="1825280">timescales.</span>
  <span m="1826360">Therefore,</span> <span m="1826790">we</span> <span m="1826900">get</span>
  <span m="1827040">a</span> <span m="1827330">stiff</span> <span m="1827560">system.</span></p><p><span
  m="1832490">So</span> <span m="1832820">that</span> <span m="1833050">is</span>
  <span m="1833220">an</span> <span m="1833360">example</span> <span m="1833850">of,</span>
  <span m="1834000">like,</span> <span m="1834320">how</span> <span m="1834690">does</span>
  <span m="1834850">the</span> <span m="1835190">name</span> <span m="1835450">stiff</span>
  <span m="1836610">really</span> <span m="1836910">comes</span> <span m="1837270">into</span>
  <span m="1837550">the</span> <span m="1837660">picture</span> <span m="1838076">of
  all this</span> <span m="1839740">if</span> <span m="1840040">you</span> <span m="1840550">have,</span>
  <span m="1841010">let''s say,</span> <span m="1841780">a</span> <span m="1841830">large</span>
  <span m="1842090">structure</span> <span m="1842550">where</span> <span m="1842940">you</span>
  <span m="1843220">are</span> <span m="1843330">interested</span> <span m="1843840">in</span>
  <span m="1844390">the</span> <span m="1844540">motion</span> <span m="1844900">of</span>
  <span m="1845020">the</span> <span m="1845140">whole.</span> <span m="1846390">But</span>
  <span m="1847560">inside</span> <span m="1847800">the structure,</span> <span m="1848650">there</span>
  <span m="1848850">are</span> <span m="1849020">some</span> <span m="1849250">very</span>
  <span m="1849730">stiff</span> <span m="1850020">components,</span> <span m="1851050">I
  mean,</span> <span m="1851470">really stiff</span> <span m="1851890">in</span> <span
  m="1852310">terms of</span> <span m="1853550">physically stiff</span> <span m="1853630">components.</span>
  <span m="1857400">When</span> <span m="1857630">you</span> <span m="1857750">derive</span>
  <span m="1858330">the</span> <span m="1858470">whole</span> <span m="1858880">ODE,</span>
  <span m="1859290">you</span> <span m="1859560">discover</span> <span m="1860070">two</span>
  <span m="1860760">timescales.</span></p><p><span m="1861620">One is</span> <span
  m="1862047">the timescale</span> <span m="1862901">you''re</span> <span m="1863330">interested</span>
  <span m="1863685">in.</span> <span m="1864360">But</span> <span m="1864590">there</span>
  <span m="1864740">is</span> <span m="1864970">a</span> <span m="1865350">much</span>
  <span m="1866650">shorter</span> <span m="1867200">timescale,</span> <span m="1867640">much</span>
  <span m="1868070">higher</span> <span m="1868380">frequency</span> <span m="1868700">timescale</span>
  <span m="1869185">due</span> <span m="1869670">to</span> <span m="1869810">the</span>
  <span m="1870080">stiff</span> <span m="1870570">component</span> <span m="1871510">inside</span>
  <span m="1872380">the</span> <span m="1872490">system.</span> <span m="1873770">And</span>
  <span m="1873930">therefore,</span> <span m="1874300">you</span> <span m="1874390">get</span>
  <span m="1874590">a</span> <span m="1874630">very</span> <span m="1875520">difficult</span>
  <span m="1876050">problem</span> <span m="1876450">to</span> <span m="1876550">solve.</span>
  <span m="1877000">And</span> <span m="1877270">[INAUDIBLE]</span> <span m="1878500">this</span>
  <span m="1878760">problem.</span> <span m="1882270">Does that</span> <span m="1882540">make</span>
  <span m="1882720">sense?</span> <span m="1885570">Yeah</span></p><p><span m="1886336">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="1891940">PROFESSOR: Yeah.</span> <span m="1892330">I</span>
  <span m="1892430">guess</span> <span m="1892770">my</span> <span m="1893000">interpretation</span>
  <span m="1893710">is</span> <span m="1894040">that</span> <span m="1894840">it''s</span>
  <span m="1895290">stiff,</span> <span m="1895780">because</span> <span m="1896150">of</span>
  <span m="1896290">the</span> <span m="1896410">stiffness</span> <span m="1896980">of</span>
  <span m="1897110">the</span> <span m="1897660">spring.</span> <span m="1898770">I</span>
  <span m="1898870">mean,</span> <span m="1900710">yeah,</span> <span m="1900980">it''s</span>
  <span m="1901310">hard to</span> <span m="1901560">solve.</span> <span m="1902020">But</span>
  <span m="1902260">it''s</span> <span m="1902450">because</span> <span m="1902960">of</span>
  <span m="1903090">the</span> <span m="1903260">stiffness</span> <span m="1903620">of
  the</span> <span m="1903980">system</span> <span m="1904463">it is</span> <span
  m="1904946">hard</span> <span m="1905429">to solve.</span> <span m="1908327">It''s</span>
  <span m="1908810">like</span> <span m="1908830">hard</span> <span m="1909120">to
  solve</span> <span m="1909670">is</span> <span m="1909790">a</span> <span m="1909870">result</span>
  <span m="1910420">of</span> <span m="1911550">it being stiff.</span> <span m="1918730">Any</span>
  <span m="1918930">other</span> <span m="1919110">questions?</span></p><p><span m="1920438">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="1922214">PROFESSOR: You</span> <span m="1922660">got</span>
  <span m="1922970">it?</span></p><p><span m="1923313">AUDIENCE: Yup.</span></p><p><span
  m="1924000">PROFESSOR: OK.</span> <span m="1925580">So</span> <span m="1926200">before</span>
  <span m="1926480">I</span> <span m="1926540">give</span> <span m="1926740">you</span>
  <span m="1926860">another</span> <span m="1927190">example</span> <span m="1928670">of</span>
  <span m="1929260">this</span> <span m="1929450">system,</span> <span m="1929850">let''s</span>
  <span m="1930140">talk</span> <span m="1930380">about</span> <span m="1930630">how</span>
  <span m="1930850">to</span> <span m="1931050">solve</span> <span m="1931310">it.</span>
  <span m="1932430">OK.</span> <span m="1933830">As</span> <span m="1934050">you</span>
  <span m="1934120">read in</span> <span m="1934600">your</span> <span m="1934790">reading,</span>
  <span m="1936300">in</span> <span m="1936500">order</span> <span m="1936730">to</span>
  <span m="1936840">solve</span> <span m="1937180">a</span> <span m="1937350">stiff</span>
  <span m="1937600">system,</span> <span m="1938370">you</span> <span m="1938580">really</span>
  <span m="1939330">need</span> <span m="1940060">implicit</span> <span m="1940660">methods.</span>
  <span m="1942460">Why</span> <span m="1942810">is</span> <span m="1943000">that</span>
  <span m="1943160">the</span> <span m="1943230">case?</span></p><p><span m="1944250">Because</span>
  <span m="1944570">in</span> <span m="1944690">explicit</span> <span m="1945290">method,</span>
  <span m="1946370">it</span> <span m="1946560">is</span> <span m="1946760">only</span>
  <span m="1947150">stable</span> <span m="1947840">for</span> <span m="1948260">a</span>
  <span m="1948300">limited</span> <span m="1948760">region</span> <span m="1949160">of</span>
  <span m="1949400">lambda</span> <span m="1949820">delta t.</span> <span m="1953120">And</span>
  <span m="1953310">if</span> <span m="1955020">there</span> <span m="1955380">is</span>
  <span m="1955860">some</span> <span m="1957300">phenomenon</span> <span m="1958990">in</span>
  <span m="1959170">your</span> <span m="1959360">system</span> <span m="1960660">that</span>
  <span m="1960820">is</span> <span m="1960960">very</span> <span m="1961320">fast,</span>
  <span m="1962490">much,</span> <span m="1962590">much</span> <span m="1962850">faster</span>
  <span m="1963430">than</span> <span m="1964160">the</span> <span m="1964410">phenomenons</span>
  <span m="1965040">you</span> <span m="1965150">want</span> <span m="1965350">to</span>
  <span m="1965450">resolve--</span> <span m="1967430">OK,</span> <span m="1967700">for</span>
  <span m="1967810">example,</span> <span m="1969830">in</span> <span m="1970250">this</span>
  <span m="1970420">case,</span> <span m="1970900">we</span> <span m="1971040">may</span>
  <span m="1971530">want</span> <span m="1971850">to</span> <span m="1972010">resolve</span>
  <span m="1973180">the scale</span> <span m="1973635">of</span> <span m="1974090">how
  the</span> <span m="1974320">temperature</span> <span m="1974751">rise</span> <span
  m="1975182">and how the</span> <span m="1975613">temperature</span> <span m="1976044">[INAUDIBLE].</span>
  <span m="1977340">That</span> <span m="1977530">is</span> <span m="1977700">the</span>
  <span m="1977800">scale</span> <span m="1978230">of</span> <span m="1978390">the
  convection.</span></p><p><span m="1979890">But</span> <span m="1980070">in</span>
  <span m="1980290">order</span> <span m="1980590">for you to</span> <span m="1981056">solve
  it,</span> <span m="1981990">you have</span> <span m="1982120">to resolve--</span>
  <span m="1983290">one</span> <span m="1983700">of</span> <span m="1983830">your</span>
  <span m="1983960">lambdas</span> <span m="1985080">is</span> <span m="1985380">the</span>
  <span m="1985480">lambda</span> <span m="1985970">corresponding</span> <span m="1986440">to</span>
  <span m="1986580">a</span> <span m="1986610">much,</span> <span m="1987060">much</span>
  <span m="1987200">faster</span> <span m="1987650">process.</span> <span m="1988660">What</span>
  <span m="1988880">does</span> <span m="1988990">this</span> <span m="1989200">mean</span>
  <span m="1989570">in</span> <span m="1989780">terms</span> <span m="1990110">of</span>
  <span m="1990400">the</span> <span m="1990500">plot?</span> <span m="1991740">It</span>
  <span m="1991930">means</span> <span m="1992250">that</span> <span m="1992600">if</span>
  <span m="1992840">you</span> <span m="1992940">have</span> <span m="1993350">the</span>
  <span m="1993460">stability</span> <span m="1993880">region</span> <span m="1994250">like</span>
  <span m="1994470">this--</span> <span m="1995110">so</span> <span m="1995190">this</span>
  <span m="1995380">is</span> <span m="1995470">the</span> <span m="1995560">peanut</span>
  <span m="1996000">shape</span> <span m="1996250">of</span> <span m="1996410">the</span>
  <span m="1996700">active</span> <span m="1997130">[INAUDIBLE],</span> <span m="1997420">that''s</span>
  <span m="1997810">one</span> <span m="1998040">of</span> <span m="1998180">the</span>
  <span m="1998270">best</span> <span m="1999060">explicit</span> <span m="1999491">schemes</span>
  <span m="1999922">out there.</span></p><p><span m="2002080">But</span> <span m="2003190">if</span>
  <span m="2003420">you</span> <span m="2003530">have</span> <span m="2003770">a</span>
  <span m="2003840">lambda</span> <span m="2004490">that</span> <span m="2004720">is</span>
  <span m="2004980">a thousand</span> <span m="2005620">times</span> <span m="2007690">the</span>
  <span m="2007900">process,</span> <span m="2008600">the</span> <span m="2008970">frequency</span>
  <span m="2009470">of</span> <span m="2009590">the</span> <span m="2009670">process</span>
  <span m="2010130">you</span> <span m="2010230">are</span> <span m="2010310">interested</span>
  <span m="2010830">in,</span> <span m="2012370">that</span> <span m="2012700">means</span>
  <span m="2013010">you</span> <span m="2013130">have</span> <span m="2013440">to</span>
  <span m="2013570">have</span> <span m="2013760">a</span> <span m="2013830">delta</span>
  <span m="2014230">t</span> <span m="2015360">that</span> <span m="2015540">is</span>
  <span m="2015670">a thousand</span> <span m="2016170">times</span> <span m="2016510">smaller</span>
  <span m="2017510">than</span> <span m="2017960">you</span> <span m="2018470">would</span>
  <span m="2019590">want</span> <span m="2019920">to</span> <span m="2020020">use.</span>
  <span m="2021080">Because</span> <span m="2021740">if</span> <span m="2021920">you</span>
  <span m="2022040">want</span> <span m="2022240">to</span> <span m="2022300">really</span>
  <span m="2022670">resolve</span> <span m="2023260">the</span> <span m="2023340">process</span>
  <span m="2023740">you</span> <span m="2023860">want</span> <span m="2024100">to</span>
  <span m="2024170">resolve</span> <span m="2024570">very</span> <span m="2024830">well,</span>
  <span m="2025800">you</span> <span m="2026020">kind</span> <span m="2026230">of</span>
  <span m="2026410">only</span> <span m="2026760">need</span> <span m="2027150">a
  lambda</span> <span m="2028102">times</span> <span m="2028930">the</span> <span
  m="2029330">smaller</span> <span m="2029720">lambda</span> <span m="2030230">times</span>
  <span m="2030420">delta t</span> <span m="2031270">to</span> <span m="2031440">be</span>
  <span m="2031560">in</span> <span m="2031650">a</span> <span m="2031750">reasonable</span>
  <span m="2032240">range.</span> <span m="2033480">But</span> <span m="2034180">that</span>
  <span m="2034520">wouldn''t</span> <span m="2034800">be</span> <span m="2034920">stable,</span>
  <span m="2036750">because</span> <span m="2037310">of</span> <span m="2037430">the</span>
  <span m="2037510">existence</span> <span m="2038290">of</span> <span m="2038570">a</span>
  <span m="2038670">very</span> <span m="2039080">large</span> <span m="2039505">eigenvalue.</span></p><p><span
  m="2040780">So</span> <span m="2041630">in</span> <span m="2041880">order</span>
  <span m="2042110">to</span> <span m="2042240">make</span> <span m="2042680">all</span>
  <span m="2043150">the</span> <span m="2043230">lambda</span> <span m="2043580">delta</span>
  <span m="2043770">t''s</span> <span m="2044250">to</span> <span m="2044360">be</span>
  <span m="2044480">within</span> <span m="2044930">the</span> <span m="2045120">stability</span>
  <span m="2045520">region--</span> <span m="2045960">and</span> <span m="2046010">remember,</span>
  <span m="2046380">you</span> <span m="2046660">have</span> <span m="2046880">to</span>
  <span m="2047030">make</span> <span m="2047660">all</span> <span m="2047970">the</span>
  <span m="2048060">lambda</span> <span m="2048530">delta</span> <span m="2048699">t''s</span>
  <span m="2048880">within</span> <span m="2049190">the stability</span> <span m="2049659">region.</span>
  <span m="2049989">Otherwise,</span> <span m="2050540">you''re</span> <span m="2050780">scheme</span>
  <span m="2050960">is</span> <span m="2051120">going</span> <span m="2051270">to</span>
  <span m="2051360">be</span> <span m="2051850">not</span> <span m="2052706">eigenvalue</span>
  <span m="2053193">stable.</span> <span m="2054170">So</span> <span m="2054330">in</span>
  <span m="2054540">order</span> <span m="2054800">for</span> <span m="2054940">you</span>
  <span m="2055000">to</span> <span m="2055100">do</span> <span m="2055310">that,</span>
  <span m="2055530">you</span> <span m="2055670">would</span> <span m="2055880">have</span>
  <span m="2056110">to</span> <span m="2056210">have</span> <span m="2056429">a delta</span>
  <span m="2056719">t</span> <span m="2057010">that</span> <span m="2057210">is</span>
  <span m="2057960">some</span> <span m="2058170">times</span> <span m="2059004">ridiculously</span>
  <span m="2059840">small.</span></p><p><span m="2062650">OK.</span> <span m="2062989">So</span>
  <span m="2063190">that</span> <span m="2063420">is</span> <span m="2063810">explicit.</span>
  <span m="2065929">And</span> <span m="2066810">for</span> <span m="2068370">explicit</span>
  <span m="2068960">schemes,</span> <span m="2070270">all</span> <span m="2070550">of</span>
  <span m="2070699">the schemes</span> <span m="2071449">only</span> <span m="2071820">have</span>
  <span m="2072060">a</span> <span m="2072159">limited</span> <span m="2073330">stability</span>
  <span m="2073816">region.</span> <span m="2075760">But</span> <span m="2075980">if</span>
  <span m="2076130">you</span> <span m="2076230">have</span> <span m="2076480">an</span>
  <span m="2076630">implicit</span> <span m="2077040">scheme,</span> <span m="2078000">the</span>
  <span m="2078270">story''s</span> <span m="2078790">much</span> <span m="2079050">different.</span></p><p><span
  m="2080100">You</span> <span m="2080300">typically</span> <span m="2080940">have</span>
  <span m="2081360">a</span> <span m="2081469">stability</span> <span m="2081780">region</span>
  <span m="2082120">that</span> <span m="2082290">looks</span> <span m="2082500">like</span>
  <span m="2082739">this.</span> <span m="2082900">It</span> <span m="2083420">is</span>
  <span m="2084210">stable</span> <span m="2085270">for</span> <span m="2085820">an</span>
  <span m="2086050">infinitely</span> <span m="2086429">large</span> <span m="2086940">region.</span>
  <span m="2088719">OK.</span> <span m="2090520">You</span> <span m="2091330">can</span>
  <span m="2091560">easily</span> <span m="2092030">make</span> <span m="2092380">this</span>
  <span m="2092670">scheme</span> <span m="2092889">to</span> <span m="2092989">be</span>
  <span m="2093080">a</span> <span m="2093150">stable</span> <span m="2093630">for</span>
  <span m="2094046">an</span> <span m="2094462">infinitely</span> <span m="2094880">region,</span>
  <span m="2095989">so</span> <span m="2096190">that</span> <span m="2096909">even</span>
  <span m="2097230">if</span> <span m="2097730">some</span> <span m="2097990">of</span>
  <span m="2098110">the lambda</span> <span m="2098840">are</span> <span m="2099010">very</span>
  <span m="2099490">large,</span> <span m="2101280">you can</span> <span m="2101420">still</span>
  <span m="2101680">have</span> <span m="2101880">a</span> <span m="2101970">stable</span>
  <span m="2102240">scheme.</span> <span m="2103300">You</span> <span m="2103430">can</span>
  <span m="2103640">still</span> <span m="2103910">use</span> <span m="2104130">a</span>
  <span m="2104350">delta</span> <span m="2104550">t</span> <span m="2104880">as</span>
  <span m="2105210">large</span> <span m="2106532">as</span> <span m="2106980">the</span>
  <span m="2107140">timescale</span> <span m="2107470">you are</span> <span m="2107945">interested</span>
  <span m="2108420">in.</span> <span m="2110320">Does it</span> <span m="2110800">make</span>
  <span m="2111050">sense?</span></p><p><span m="2114970">Now,</span> <span m="2116570">implicit</span>
  <span m="2117020">method</span> <span m="2117360">has</span> <span m="2117610">a</span>
  <span m="2117670">lot</span> <span m="2117870">of</span> <span m="2117960">benefits.</span>
  <span m="2120160">But it</span> <span m="2120270">also</span> <span m="2120740">have</span>
  <span m="2121010">some</span> <span m="2121270">disadvantage,</span> <span m="2122530">especially</span>
  <span m="2122800">for</span> <span m="2123220">[INAUDIBLE]</span> <span m="2123630">your</span>
  <span m="2123780">system.</span> <span m="2125180">As</span> <span m="2125410">you</span>
  <span m="2125630">saw,</span> <span m="2126070">[INAUDIBLE]</span> <span m="2126500">system</span>
  <span m="2127890">each</span> <span m="2128130">step</span> <span m="2128390">involves</span>
  <span m="2128800">solving</span> <span m="2129280">a</span> <span m="2129760">nonlinear</span>
  <span m="2129850">equation.</span></p><p><span m="2130840">So</span> <span m="2131040">for</span>
  <span m="2131210">example,</span> <span m="2132170">I''m</span> <span m="2132270">using</span>
  <span m="2132610">the</span> <span m="2132750">most</span> <span m="2133480">simple</span>
  <span m="2133920">scheme</span> <span m="2134530">backward</span> <span m="2134660">[INAUDIBLE].</span>
  <span m="2139280">In</span> <span m="2139460">backward</span> <span m="2139690">[INAUDIBLE],</span>
  <span m="2141620">the</span> <span m="2141790">difference</span> <span m="2142520">between</span>
  <span m="2142960">V</span> <span m="2143240">n plus 1</span> <span m="2143730">Vn</span>
  <span m="2144390">minus</span> <span m="2145120">over</span> <span m="2145400">delta</span>
  <span m="2145580">t</span> <span m="2146120">is</span> <span m="2146450">equal</span>
  <span m="2146790">to</span> <span m="2146880">the</span> <span m="2146990">right-hand</span>
  <span m="2147320">side</span> <span m="2147650">of</span> <span m="2147860">V n</span>
  <span m="2148190">plus</span> <span m="2148490">1</span> <span m="2148820">instead</span>
  <span m="2149340">Vn.</span> <span m="2150030">If</span> <span m="2150480">it''s</span>
  <span m="2150720">Vn,</span> <span m="2151100">then</span> <span m="2151290">it''s</span>
  <span m="2151650">forward</span> <span m="2151755">[INAUDIBLE].</span> <span m="2151860">But</span>
  <span m="2152150">if</span> <span m="2152550">it''s</span> <span m="2152720">Vn
  plus</span> <span m="2153030">1,</span> <span m="2153280">it''s</span> <span m="2153440">backward</span>
  <span m="2153680">[INAUDIBLE].</span> <span m="2154750">It</span> <span m="2154910">looks</span>
  <span m="2155200">like</span> <span m="2155450">a</span> <span m="2155510">very</span>
  <span m="2155800">innocent</span> <span m="2156240">difference.</span> <span m="2157830">But</span>
  <span m="2158150">if</span> <span m="2158440">f</span> <span m="2158800">is</span>
  <span m="2158940">nonlinear,</span> <span m="2159960">this</span> <span m="2160360">is</span>
  <span m="2160770">hell</span> <span m="2161253">a lot</span> <span m="2161736">different.</span></p><p><span
  m="2162220">Because</span> <span m="2163810">the</span> <span m="2164090">unknowns</span>
  <span m="2164320">are</span> <span m="2166330">also</span> <span m="2167470">within
  here.</span> <span m="2168320">So</span> <span m="2168500">this</span> <span m="2168820">is</span>
  <span m="2168950">unknown.</span> <span m="2169846">V n plus</span> <span m="2170192">1</span>
  <span m="2170710">is</span> <span m="2170900">unknown.</span> <span m="2171780">Only</span>
  <span m="2172140">Vn</span> <span m="2172610">is</span> <span m="2172740">known.</span></p><p><span
  m="2173470">If</span> <span m="2173760">this</span> <span m="2173960">is</span>
  <span m="2174090">Vn,</span> <span m="2174710">I</span> <span m="2174830">can</span>
  <span m="2175070">evaluate</span> <span m="2176190">f</span> <span m="2176420">of</span>
  <span m="2176550">Vn.</span> <span m="2176920">But</span> <span m="2177310">if</span>
  <span m="2178040">this</span> <span m="2178240">is</span> <span m="2178400">V n</span>
  <span m="2178700">plus 1,</span> <span m="2179280">I</span> <span m="2179400">don''t</span>
  <span m="2179750">know</span> <span m="2179980">what</span> <span m="2180150">V
  n plus</span> <span m="2180626">1 is.</span> <span m="2181580">So</span> <span m="2181730">I</span>
  <span m="2181780">cannot</span> <span m="2182260">evaluate</span> <span m="2182850">this.</span>
  <span m="2184010">I</span> <span m="2184170">have</span> <span m="2184330">to</span>
  <span m="2184450">solve</span> <span m="2184810">the</span> <span m="2184910">whole</span>
  <span m="2185160">thing</span> <span m="2186010">as</span> <span m="2186240">a</span>
  <span m="2186330">nonlinear</span> <span m="2187100">equation.</span></p><p><span
  m="2189230">OK.</span> <span m="2191990">On</span> <span m="2192130">the</span>
  <span m="2192220">other</span> <span m="2192420">the</span> <span m="2192640">day,</span>
  <span m="2192860">we</span> <span m="2192980">said</span> <span m="2193270">if</span>
  <span m="2193600">f</span> <span m="2193910">is</span> <span m="2194120">a</span>
  <span m="2194230">linear</span> <span m="2194680">equation,</span> <span m="2194990">if</span>
  <span m="2195170">f</span> <span m="2195450">is</span> <span m="2195600">linear,</span>
  <span m="2196420">we</span> <span m="2196590">can</span> <span m="2197250">express</span>
  <span m="2197940">this</span> <span m="2198150">in a matrix</span> <span m="2198850">form</span>
  <span m="2199710">and</span> <span m="2200480">rearrange</span> <span m="2201170">the</span>
  <span m="2201320">equation</span> <span m="2202110">and</span> <span m="2202340">compute
  it</span> <span m="2202820">by</span> <span m="2202970">solving</span> <span m="2203420">a</span>
  <span m="2203500">linear</span> <span m="2203780">equation.</span> <span m="2204650">But</span>
  <span m="2204860">if</span> <span m="2205040">f</span> <span m="2205350">is</span>
  <span m="2205570">nonlinear,</span> <span m="2207380">how do you</span> <span m="2207700">do</span>
  <span m="2207860">it?</span> <span m="2211190">Of course</span> <span m="2211570">the</span>
  <span m="2211690">answer</span> <span m="2211840">is</span> <span m="2212280">Newton-Raphson.</span></p><p><span
  m="2213590">But</span> <span m="2213750">to</span> <span m="2213870">understand</span>
  <span m="2214690">what</span> <span m="2215168">Newton-Raphson</span> <span m="2215646">does,</span>
  <span m="2216602">I</span> <span m="2217080">think</span> <span m="2217330">it</span>
  <span m="2217470">benefits</span> <span m="2218290">first</span> <span m="2218540">to</span>
  <span m="2218640">review</span> <span m="2219230">what</span> <span m="2219480">we</span>
  <span m="2219640">would</span> <span m="2219880">do</span> <span m="2220010">in</span>
  <span m="2220170">the</span> <span m="2220270">linear</span> <span m="2220460">case.</span>
  <span m="2224120">In linear</span> <span m="2224650">case,</span> <span m="2224990">f</span>
  <span m="2225080">of</span> <span m="2225400">V</span> <span m="2225650">n plus</span>
  <span m="2226120">1</span> <span m="2227220">can</span> <span m="2227580">be</span>
  <span m="2228210">represented</span> <span m="2229000">using</span> <span m="2230740">a</span>
  <span m="2230850">matrix</span> <span m="2231780">times</span> <span m="2232200">the</span>
  <span m="2232620">n plus 1.</span> <span m="2236190">OK.</span> <span m="2236860">Then</span>
  <span m="2237220">what</span> <span m="2237390">we</span> <span m="2237510">can</span>
  <span m="2237770">do</span> <span m="2238320">is</span> <span m="2238590">the</span>
  <span m="2238680">following.</span></p><p><span m="2240910">We</span> <span m="2240980">can</span>
  <span m="2241300">move</span> <span m="2241920">all the</span> <span m="2242340">known</span>
  <span m="2242630">terms</span> <span m="2243660">on</span> <span m="2243870">the</span>
  <span m="2244020">left-hand</span> <span m="2244370">side,</span> <span m="2245270">I
  over</span> <span m="2245660">delta</span> <span m="2246000">t</span> <span m="2247570">minus</span>
  <span m="2248230">A</span> <span m="2248990">times</span> <span m="2249440">V</span>
  <span m="2249720">n plus 1</span> <span m="2251150">equals</span> <span m="2252330">to</span>
  <span m="2252620">the--</span> <span m="2253450">this</span> <span m="2253670">is</span>
  <span m="2253810">unknown</span> <span m="2254320">equal</span> <span m="2254640">to</span>
  <span m="2254740">the</span> <span m="2254880">knowns,</span> <span m="2255870">which</span>
  <span m="2256090">is</span> <span m="2256210">Vn</span> <span m="2256890">divided</span>
  <span m="2257310">by</span> <span m="2257590">delta</span> <span m="2258000">t.</span>
  <span m="2259060">So</span> <span m="2259180">we</span> <span m="2259510">are</span>
  <span m="2259918">moving</span> <span m="2260734">[INAUDIBLE]</span> <span m="2261550">this
  is</span> <span m="2261810">[INAUDIBLE]</span> <span m="2263145">and</span> <span
  m="2263590">moving</span> <span m="2263880">this</span> <span m="2264050">term,</span>
  <span m="2264300">which</span> <span m="2264761">is now</span> <span m="2265222">here,</span>
  <span m="2265683">onto the</span> <span m="2266144">left-hand</span> <span m="2266605">side.</span>
  <span m="2268450">Once</span> <span m="2268925">we</span> <span m="2269400">arrive
  at</span> <span m="2269875">a</span> <span m="2270350">matrix</span> <span m="2270770">form,</span>
  <span m="2271251">we</span> <span m="2271732">can use</span> <span m="2272213">[INAUDIBLE]</span>
  <span m="2272694">matrix</span> <span m="2273175">and</span> <span m="2273656">solve</span>
  <span m="2274137">for the</span> <span m="2274618">Vn plus</span> <span m="2275099">1</span>
  <span m="2276550">right?</span></p><p><span m="2280800">Now,</span> <span m="2281070">let''s</span>
  <span m="2282140">dive</span> <span m="2282440">into</span> <span m="2282640">the</span>
  <span m="2282760">nonlinear case.</span> <span m="2287220">OK.</span> <span m="2287480">We</span>
  <span m="2287610">don''t</span> <span m="2287800">know</span> <span m="2287970">how</span>
  <span m="2288120">to</span> <span m="2288240">solve</span> <span m="2288470">the</span>
  <span m="2288540">nonlinear</span> <span m="2288970">equation.</span> <span m="2290030">So</span>
  <span m="2290190">why</span> <span m="2290500">don''t</span> <span m="2290730">we</span>
  <span m="2290900">approximate it</span> <span m="2293050">using</span> <span m="2293390">a</span>
  <span m="2293450">linear</span> <span m="2293760">equation?</span></p><p><span m="2296050">Why</span>
  <span m="2296260">don''t</span> <span m="2296440">we</span> <span m="2296600">approximate</span>
  <span m="2298080">the</span> <span m="2298220">nonlinear</span> <span m="2298840">term</span>
  <span m="2299180">f of</span> <span m="2299660">V</span> <span m="2299810">n plus
  1.</span> <span m="2300420">Try</span> <span m="2300910">something</span> <span
  m="2301220">linear.</span> <span m="2303420">How</span> <span m="2303520">do</span>
  <span m="2303600">you</span> <span m="2303660">do</span> <span m="2303850">that?</span></p><p><span
  m="2305320">AUDIENCE: [INAUDIBLE]</span></p><p><span m="2308750">PROFESSOR: Small</span>
  <span m="2309120">perturbation</span> <span m="2310440">Taylor</span> <span m="2310800">series.</span>
  <span m="2312590">This</span> <span m="2312860">is</span> <span m="2313100">another</span>
  <span m="2313580">use</span> <span m="2313850">of</span> <span m="2313990">Taylor</span>
  <span m="2314270">series</span> <span m="2315220">completely</span> <span m="2315740">different</span>
  <span m="2316370">from</span> <span m="2317120">how</span> <span m="2317280">we</span>
  <span m="2317470">used</span> <span m="2317770">it in</span> <span m="2318676">discretizing</span>
  <span m="2319130">ordinary</span> <span m="2319680">differential</span> <span m="2320160">equations.</span>
  <span m="2322130">We</span> <span m="2322570">linearize</span> <span m="2324450">f
  of</span> <span m="2324830">V</span> <span m="2325200">n</span> <span m="2326530">plus</span>
  <span m="2326890">1</span> <span m="2329000">at</span> <span m="2329900">some</span>
  <span m="2330160">kind</span> <span m="2330360">of</span> <span m="2330510">initial</span>
  <span m="2331050">guess.</span></p><p><span m="2331800">So</span> <span m="2333660">we</span>
  <span m="2334090">first</span> <span m="2334330">guess</span> <span m="2334540">what</span>
  <span m="2334800">V</span> <span m="2334910">n plus 1</span> <span m="2335060">is.</span>
  <span m="2336050">And</span> <span m="2336230">usually,</span> <span m="2336670">a</span>
  <span m="2336950">good</span> <span m="2337820">first</span> <span m="2338100">initial</span>
  <span m="2338240">guess</span> <span m="2338610">is</span> <span m="2338690">just</span>
  <span m="2338860">Vn.</span> <span m="2340670">Because</span> <span m="2341370">if</span>
  <span m="2341600">I</span> <span m="2341710">know</span> <span m="2341880">I''m</span>
  <span m="2342010">taking</span> <span m="2342330">small</span> <span m="2342570">time
  steps,</span> <span m="2344390">then</span> <span m="2344760">I</span> <span m="2344840">know</span>
  <span m="2345340">the</span> <span m="2345440">next</span> <span m="2345780">time</span>
  <span m="2346030">step</span> <span m="2346620">I</span> <span m="2346780">have</span>
  <span m="2346890">a</span> <span m="2347550">V n plus</span> <span m="2347820">1</span>
  <span m="2348315">that is</span> <span m="2348810">really</span> <span m="2349050">similar</span>
  <span m="2349470">to what</span> <span m="2349862">Vn</span> <span m="2350254">is.</span></p><p><span
  m="2351040">So</span> <span m="2351270">I''m</span> <span m="2351430">going</span>
  <span m="2351570">to</span> <span m="2351760">set</span> <span m="2352800">f of</span>
  <span m="2353090">Vn plus</span> <span m="2353280">1</span> <span m="2353630">equal</span>
  <span m="2354170">to</span> <span m="2354370">Vn</span> <span m="2355295">equal</span>
  <span m="2355630">to</span> <span m="2355910">f</span> <span m="2356060">of</span>
  <span m="2356240">Vn</span> <span m="2358602">plus</span> <span m="2362330">delta</span>
  <span m="2362640">V</span> <span m="2363650">where</span> <span m="2363940">delta</span>
  <span m="2364120">V</span> <span m="2364350">is</span> <span m="2365445">V n plus</span>
  <span m="2365760">1</span> <span m="2366390">minus</span> <span m="2366850">Vn</span>
  <span m="2368650">times</span> <span m="2370450">the</span> <span m="2370740">derivative</span>
  <span m="2371360">of V.</span> <span m="2372590">So</span> <span m="2372730">instead</span>
  <span m="2373150">of</span> <span m="2373320">writing</span> <span m="2373650">it</span>
  <span m="2373770">like</span> <span m="2374020">this,</span> <span m="2374620">I''m</span>
  <span m="2374810">going</span> <span m="2374950">to</span> <span m="2375060">write</span>
  <span m="2375330">a</span> <span m="2375380">matrix,</span> <span m="2376330">partial</span>
  <span m="2376590">f</span> <span m="2377150">partial</span> <span m="2378020">V</span>
  <span m="2378940">at</span> <span m="2379520">Vn</span> <span m="2380370">times</span>
  <span m="2381358">delta</span> <span m="2381856">V.</span> <span m="2383350">So</span>
  <span m="2383500">I''m</span> <span m="2383610">going</span> <span m="2383730">to</span>
  <span m="2383830">write it</span> <span m="2384060">like</span> <span m="2384360">this.</span></p><p><span
  m="2386730">Now,</span> <span m="2387230">in</span> <span m="2387620">this</span>
  <span m="2388330">Taylor</span> <span m="2388790">series</span> <span m="2388980">expansion,</span>
  <span m="2389622">I</span> <span m="2390084">only</span> <span m="2390546">can</span>
  <span m="2391010">write a</span> <span m="2391100">problem.</span> <span m="2391560">Because</span>
  <span m="2391850">I''m</span> <span m="2392120">ignoring</span> <span m="2392360">the</span>
  <span m="2392600">[INAUDIBLE].</span> <span m="2394020">Now,</span> <span m="2394270">in</span>
  <span m="2394460">this</span> <span m="2394730">Taylor</span> <span m="2395070">series</span>
  <span m="2395470">expansion,</span> <span m="2395920">what</span> <span m="2396100">is</span>
  <span m="2396230">known?</span> <span m="2396510">What</span> <span m="2396710">is</span>
  <span m="2396830">unknown?</span> <span m="2402040">This</span> <span m="2402355">is</span>
  <span m="2402670">known,</span> <span m="2403350">right?</span></p><p><span m="2404940">And</span>
  <span m="2405560">the</span> <span m="2405810">unknown--</span> <span m="2408330">well,</span>
  <span m="2409110">the</span> <span m="2409340">unknown</span> <span m="2409860">is</span>
  <span m="2410140">only</span> <span m="2410490">this.</span> <span m="2410990">The</span>
  <span m="2411170">matrix</span> <span m="2411680">is</span> <span m="2411920">also</span>
  <span m="2412300">known.</span> <span m="2416570">So</span> <span m="2416740">somehow</span>
  <span m="2417610">we</span> <span m="2417870">reduced</span> <span m="2418790">the</span>
  <span m="2418930">nonlinear</span> <span m="2419530">equation</span> <span m="2419840">into</span>
  <span m="2420180">a</span> <span m="2420300">linear</span> <span m="2420720">question.</span></p><p><span
  m="2421090">Because</span> <span m="2421500">all</span> <span m="2421895">the terms</span>
  <span m="2422290">that</span> <span m="2422500">involves</span> <span m="2422950">the</span>
  <span m="2423110">unknown</span> <span m="2424350">is</span> <span m="2425030">linear,</span>
  <span m="2428590">right?</span> <span m="2430870">That''s</span> <span m="2432460">write</span>
  <span m="2432690">this</span> <span m="2432860">down</span> <span m="2433080">and</span>
  <span m="2433230">convince</span> <span m="2433660">ourselves.</span> <span m="2435890">Let''s</span>
  <span m="2436290">plug</span> <span m="2436770">this</span> <span m="2437190">into</span>
  <span m="2437580">the</span> <span m="2437700">original</span> <span m="2438150">equation.</span></p><p><span
  m="2439269">AUDIENCE: [INAUDIBLE]</span></p><p><span m="2451010">PROFESSOR: Yes.</span></p><p><span
  m="2452756">AUDIENCE: [INAUDIBLE]</span></p><p><span m="2454650">PROFESSOR: So</span>
  <span m="2455350">half</span> <span m="2455560">of</span> <span m="2455800">[INAUDIBLE]</span>
  <span m="2456640">is</span> <span m="2456910">unknown.</span> <span m="2457110">But</span>
  <span m="2457495">once</span> <span m="2457880">we</span> <span m="2458650">[INAUDIBLE]</span>
  <span m="2459710">like this,</span> <span m="2459940">we</span> <span m="2460280">found</span>
  <span m="2460620">the</span> <span m="2460860">only</span> <span m="2461460">unknown</span>
  <span m="2461850">in</span> <span m="2462318">terms</span> <span m="2462786">of</span>
  <span m="2463254">a linear</span> <span m="2463722">term</span> <span m="2464190">is</span>
  <span m="2464658">[INAUDIBLE].</span> <span m="2470330">So</span> <span m="2470470">let''s
  do</span> <span m="2470970">this.</span> <span m="2472150">Let''s</span> <span m="2472480">plug</span>
  <span m="2472740">into</span> <span m="2473050">the</span> <span m="2473190">scheme.</span></p><p><span
  m="2473920">What</span> <span m="2474100">we</span> <span m="2474250">found</span>
  <span m="2474680">is</span> <span m="2474940">that</span> <span m="2477660">so</span>
  <span m="2478670">Vn</span> <span m="2479210">plus</span> <span m="2479510">1 minus</span>
  <span m="2479690">Vn</span> <span m="2480396">is</span> <span m="2480750">my</span>
  <span m="2480960">delta</span> <span m="2481260">v,</span> <span m="2481560">right?</span>
  <span m="2481860">My</span> <span m="2481990">delta</span> <span m="2482320">V</span>
  <span m="2482590">is</span> <span m="2482740">unknown.</span> <span m="2484696">Delta</span>
  <span m="2485130">V</span> <span m="2485840">divide</span> <span m="2486150">by</span>
  <span m="2486330">delta</span> <span m="2486660">t</span> <span m="2489530">is</span>
  <span m="2490030">equal</span> <span m="2490900">to</span> <span m="2491400">this.</span>
  <span m="2492510">So</span> <span m="2492740">the</span> <span m="2492820">first</span>
  <span m="2493100">term</span> <span m="2493320">is</span> <span m="2493550">known.</span>
  <span m="2496270">And</span> <span m="2496680">the</span> <span m="2497200">Jacobi</span>
  <span m="2498100">is</span> <span m="2498400">known.</span> <span m="2498690">The</span>
  <span m="2498890">Jacobi</span> <span m="2499320">is the</span> <span m="2499410">derivative</span>
  <span m="2500010">of</span> <span m="2500160">f</span> <span m="2500570">to</span>
  <span m="2500840">V.</span> <span m="2502370">And</span> <span m="2503520">my</span>
  <span m="2503970">delta</span> <span m="2504420">V</span> <span m="2504800">is</span>
  <span m="2504960">over</span> <span m="2505160">here.</span></p><p><span m="2507970">OK.</span>
  <span m="2508320">Now,</span> <span m="2509330">I</span> <span m="2509490">can</span>
  <span m="2510470">solve</span> <span m="2510720">this</span> <span m="2510890">equation</span>
  <span m="2511250">using</span> <span m="2511620">exactly</span> <span m="2512040">the</span>
  <span m="2512160">same</span> <span m="2512480">way</span> <span m="2512830">which</span>
  <span m="2513050">I</span> <span m="2513220">solved</span> <span m="2516130">the</span>
  <span m="2516300">linear</span> <span m="2516670">equation.</span> <span m="2517500">I</span>
  <span m="2517630">can</span> <span m="2517820">say</span> <span m="2518050">I,</span>
  <span m="2518640">which</span> <span m="2518840">is</span> <span m="2518980">identity</span>
  <span m="2519540">over</span> <span m="2519800">delta</span> <span m="2519930">t</span>
  <span m="2520070">minus</span> <span m="2521540">my</span> <span m="2522185">Jacobi,</span>
  <span m="2522870">partial</span> <span m="2522990">f</span> <span m="2523280">partial</span>
  <span m="2523670">V</span> <span m="2524390">at</span> <span m="2524680">Vn</span>
  <span m="2526220">times</span> <span m="2528190">my</span> <span m="2528420">delta</span>
  <span m="2528530">V</span> <span m="2529720">is</span> <span m="2530070">equal</span>
  <span m="2530490">to</span> <span m="2532800">f of</span> <span m="2533297">Vn.</span>
  <span m="2536780">OK.</span> <span m="2537160">Now,</span> <span m="2537510">I</span>
  <span m="2537640">can</span> <span m="2537920">solve</span> <span m="2538180">for</span>
  <span m="2538350">the</span> <span m="2538450">delta</span> <span m="2538650">V.</span>
  <span m="2541020">And</span> <span m="2541490">I''m</span> <span m="2541690">going</span>
  <span m="2541840">to</span> <span m="2542020">say</span> <span m="2542280">my</span>
  <span m="2543130">f</span> <span m="2543395">Vn</span> <span m="2543660">plus</span>
  <span m="2543990">1</span> <span m="2545890">[INAUDIBLE],</span> <span m="2546230">which</span>
  <span m="2546590">is</span> <span m="2546690">my</span> <span m="2546820">guess,</span>
  <span m="2548200">is</span> <span m="2548520">equal</span> <span m="2549030">to</span>
  <span m="2549820">Vn</span> <span m="2550740">plus</span> <span m="2552120">this</span>
  <span m="2552620">quantity</span> <span m="2553260">I</span> <span m="2553320">just</span>
  <span m="2553730">solved</span> <span m="2554050">for,</span> <span m="2554725">delta</span>
  <span m="2555180">V.</span></p><p><span m="2558370">This</span> <span m="2559290">Vn
  plus</span> <span m="2559550">1</span> <span m="2560200">[INAUDIBLE]</span> <span
  m="2560600">hopefully</span> <span m="2561370">is</span> <span m="2561910">a</span>
  <span m="2562030">better</span> <span m="2562600">approximation</span> <span m="2563440">to</span>
  <span m="2563570">V</span> <span m="2563890">n plus</span> <span m="2564110">1</span>
  <span m="2564560">than</span> <span m="2564830">my</span> <span m="2564930">initial</span>
  <span m="2565400">guess</span> <span m="2565670">Vn.</span> <span m="2568910">But</span>
  <span m="2569120">how</span> <span m="2569310">can</span> <span m="2569540">I</span>
  <span m="2570020">be</span> <span m="2570180">sure?</span> <span m="2570630">How</span>
  <span m="2570800">can</span> <span m="2570960">I</span> <span m="2571030">be</span>
  <span m="2571200">certain</span> <span m="2571670">it</span> <span m="2571810">is</span>
  <span m="2571980">actually</span> <span m="2572360">better?</span></p><p><span m="2577850">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="2579770">PROFESSOR: I</span> <span m="2579930">calculate</span>
  <span m="2580760">the</span> <span m="2580900">residual,</span> <span m="2581520">exactly.</span>
  <span m="2586750">Now,</span> <span m="2586970">I</span> <span m="2587200">have</span>
  <span m="2587590">this</span> <span m="2587810">quantity.</span> <span m="2589090">I</span>
  <span m="2589230">can</span> <span m="2589450">plug</span> <span m="2589940">this</span>
  <span m="2590140">quantity</span> <span m="2590760">into</span> <span m="2592980">the</span>
  <span m="2593140">equation.</span> <span m="2595060">I''m</span> <span m="2595240">going</span>
  <span m="2595380">to</span> <span m="2595480">say</span> <span m="2595860">is</span>
  <span m="2596200">it</span> <span m="2596830">equal</span> <span m="2597350">to</span>
  <span m="2598360">f</span> <span m="2598730">of</span> <span m="2600570">V</span>
  <span m="2600980">n plus 1</span> <span m="2601800">tilde.</span></p><p><span m="2604070">If</span>
  <span m="2605120">this</span> <span m="2605460">v tilde</span> <span m="2606000">n
  plus</span> <span m="2606250">1,</span> <span m="2606510">when</span> <span m="2606980">I</span>
  <span m="2607060">plug</span> <span m="2607430">it</span> <span m="2607540">in,</span>
  <span m="2607840">is</span> <span m="2608280">equal</span> <span m="2608950">to</span>
  <span m="2609050">the</span> <span m="2609160">right-hand</span> <span m="2609530">side,</span>
  <span m="2610460">more</span> <span m="2610930">approximately</span> <span m="2611860">than</span>
  <span m="2612220">if</span> <span m="2612410">I</span> <span m="2612520">plug</span>
  <span m="2613050">in</span> <span m="2613900">Vn</span> <span m="2614620">as</span>
  <span m="2614980">V</span> <span m="2615340">n</span> <span m="2615700">tilde</span>
  <span m="2616010">plus 1.</span> <span m="2618430">Then</span> <span m="2619450">I</span>
  <span m="2619510">know</span> <span m="2619980">I</span> <span m="2620310">have</span>
  <span m="2620440">a</span> <span m="2620500">better</span> <span m="2620850">approximation.</span>
  <span m="2622030">If</span> <span m="2622340">this</span> <span m="2622660">is</span>
  <span m="2622990">almost</span> <span m="2623430">exactly</span> <span m="2623910">equal,</span>
  <span m="2624230">then</span> <span m="2624410">I</span> <span m="2624540">know</span>
  <span m="2625230">I</span> <span m="2625460">already</span> <span m="2625900">got</span>
  <span m="2626110">a</span> <span m="2626140">very</span> <span m="2626350">good</span>
  <span m="2626500">answer.</span> <span m="2631840">What</span> <span m="2632180">if</span>
  <span m="2632920">I</span> <span m="2633020">improved,</span> <span m="2634140">but</span>
  <span m="2634440">still</span> <span m="2634810">didn''t</span> <span m="2635140">have</span>
  <span m="2635790">an</span> <span m="2636065">as</span> <span m="2636560">accurate</span>
  <span m="2636710">answer</span> <span m="2636880">as</span> <span m="2637140">I</span>
  <span m="2637470">want?</span></p><p><span m="2638770">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="2644770">PROFESSOR: Yes.</span> <span m="2645250">I</span> <span m="2645390">keep</span>
  <span m="2645820">iterating.</span> <span m="2646450">Now,</span> <span m="2646940">I''m</span>
  <span m="2647150">going</span> <span m="2647300">to</span> <span m="2647390">define</span>
  <span m="2647690">another</span> <span m="2648050">delta n.</span> <span m="2649650">So</span>
  <span m="2650110">if</span> <span m="2650870">not</span> <span m="2651863">good</span>
  <span m="2652830">enough,</span> <span m="2655540">I''m</span> <span m="2655710">going</span>
  <span m="2655840">to</span> <span m="2655960">say,</span> <span m="2656330">OK,</span>
  <span m="2657630">what</span> <span m="2657850">I</span> <span m="2657960">really</span>
  <span m="2658340">want</span> <span m="2658760">is</span> <span m="2659050">equal</span>
  <span m="2659420">to</span> <span m="2659550">my</span> <span m="2659760">guess</span>
  <span m="2660766">plus</span> <span m="2661560">my</span> <span m="2662020">new</span>
  <span m="2662340">delta</span> <span m="2662560">V.</span></p><p><span m="2663330">This</span>
  <span m="2663750">is</span> <span m="2664000">a</span> <span m="2664090">new</span>
  <span m="2665580">delta</span> <span m="2665840">V.</span> <span m="2666660">And</span>
  <span m="2667010">do</span> <span m="2667130">this</span> <span m="2667310">again.</span>
  <span m="2669310">And</span> <span m="2669470">do</span> <span m="2669590">this</span>
  <span m="2669810">again.</span> <span m="2670210">How</span> <span m="2670340">do</span>
  <span m="2670430">I</span> <span m="2670510">do</span> <span m="2670690">this</span>
  <span m="2670870">again?</span></p><p><span m="2674100">The</span> <span m="2674300">unknown,</span>
  <span m="2675240">which</span> <span m="2675380">is</span> <span m="2675570">f</span>
  <span m="2675940">Vn</span> <span m="2676140">plus 1,</span> <span m="2676980">now</span>
  <span m="2677440">is</span> <span m="2677770">equal</span> <span m="2678230">to</span>
  <span m="2679610">f</span> <span m="2679990">of</span> <span m="2680430">v tilde</span>
  <span m="2681380">n plus</span> <span m="2681570">1.</span> <span m="2681920">Now,</span>
  <span m="2682250">this</span> <span m="2682440">is</span> <span m="2682600">known,</span>
  <span m="2683000">because</span> <span m="2683360">I</span> <span m="2683480">already</span>
  <span m="2683770">computed</span> <span m="2684770">the</span> <span m="2684900">better</span>
  <span m="2685360">approximation.</span> <span m="2687250">Plus</span> <span m="2687860">the</span>
  <span m="2688000">derivative</span> <span m="2688810">of</span> <span m="2689070">f</span>
  <span m="2689220">to</span> <span m="2689530">V</span> <span m="2690780">at</span>
  <span m="2691170">this</span> <span m="2691760">tilde</span> <span m="2692100">V</span>
  <span m="2692210">n plus 1</span> <span m="2693900">times</span> <span m="2695010">my
  new</span> <span m="2695960">delta V--</span> <span m="2700528">so</span> <span
  m="2701030">this</span> <span m="2701250">is</span> <span m="2701470">iteration</span>
  <span m="2702100">two.</span></p><p><span m="2706440">And</span> <span m="2706710">previously,</span>
  <span m="2708970">this</span> <span m="2709430">is</span> <span m="2709930">iteration</span>
  <span m="2710870">number</span> <span m="2711230">one.</span> <span m="2713160">And</span>
  <span m="2713450">here</span> <span m="2713710">is</span> <span m="2713930">my</span>
  <span m="2714120">iteration</span> <span m="2714540">number</span> <span m="2714820">two.</span>
  <span m="2715180">In</span> <span m="2715410">iteration</span> <span m="2715490">number
  two,</span> <span m="2715880">I</span> <span m="2716376">constructed</span> <span
  m="2716872">a</span> <span m="2717368">new</span> <span m="2717864">Taylor</span>
  <span m="2718360">series</span> <span m="2718780">expansion,</span> <span m="2719300">I</span>
  <span m="2719790">constructed</span> <span m="2720200">a new</span> <span m="2720470">approximation</span>
  <span m="2721300">based</span> <span m="2721600">on</span> <span m="2722410">my</span>
  <span m="2723020">updated</span> <span m="2723910">guess.</span></p><p><span m="2727790">And</span>
  <span m="2728000">then</span> <span m="2728900">the</span> <span m="2729010">next</span>
  <span m="2729270">thing</span> <span m="2729460">is</span> <span m="2729620">the</span>
  <span m="2729740">same.</span> <span m="2730140">I''m</span> <span m="2730350">going</span>
  <span m="2730500">to</span> <span m="2730710">plug in</span> <span m="2731220">this</span>
  <span m="2731450">equation</span> <span m="2732810">into</span> <span m="2734030">the</span>
  <span m="2734190">formula.</span> <span m="2735220">And</span> <span m="2735290">the</span>
  <span m="2735350">formula</span> <span m="2736110">is</span> <span m="2737790">V</span>
  <span m="2738130">n</span> <span m="2738620">plus</span> <span m="2738980">1</span>
  <span m="2744990">minus</span> <span m="2746770">Vn.</span> <span m="2748080">Now,</span>
  <span m="2748360">my</span> <span m="2748550">V n</span> <span m="2748900">plus</span>
  <span m="2749220">1</span> <span m="2749610">is</span> <span m="2749920">equal</span>
  <span m="2750200">to</span> <span m="2750330">this,</span> <span m="2750700">right?</span></p><p><span
  m="2751480">So</span> <span m="2751670">I</span> <span m="2751810">actually</span>
  <span m="2752290">have</span> <span m="2754614">a</span> <span m="2755580">V</span>
  <span m="2755870">tilde</span> <span m="2756986">n</span> <span m="2757400">plus</span>
  <span m="2757690">1</span> <span m="2757960">minus</span> <span m="2758450">Vn</span>
  <span m="2758800">plus</span> <span m="2759228">my</span> <span m="2759656">delta
  V</span> <span m="2760940">divided</span> <span m="2761420">by</span> <span m="2761660">delta</span>
  <span m="2761940">t</span> <span m="2762700">is</span> <span m="2762990">equal</span>
  <span m="2763400">to--</span> <span m="2764360">oh,</span> <span m="2764840">let</span>
  <span m="2764990">me</span> <span m="2765110">actually</span> <span m="2765470">color</span>
  <span m="2765760">the terms</span> <span m="2766420">that</span> <span m="2766560">is</span>
  <span m="2766750">known</span> <span m="2767080">and</span> <span m="2767330">unknown.</span>
  <span m="2767800">These</span> <span m="2768040">are</span> <span m="2768340">known</span>
  <span m="2768820">equal</span> <span m="2769275">to</span> <span m="2769730">f</span>
  <span m="2770060">of</span> <span m="2770390">v tilde</span> <span m="2771280">n</span>
  <span m="2771480">plus</span> <span m="2771760">1</span> <span m="2773290">plus</span>
  <span m="2774620">the</span> <span m="2774790">same</span> <span m="2775330">thing</span>
  <span m="2776020">times</span> <span m="2776740">the</span> <span m="2777120">unknown</span>
  <span m="2777350">delta</span> <span m="2777710">V.</span> <span m="2778183">Sorry,</span>
  <span m="2779130">should</span> <span m="2779330">be</span> <span m="2779630">blue.</span>
  <span m="2787170">And</span> <span m="2787380">again,</span> <span m="2787790">I''m</span>
  <span m="2787940">going</span> <span m="2788060">to</span> <span m="2788130">move</span>
  <span m="2788610">all</span> <span m="2788950">the</span> <span m="2789050">known
  terms</span> <span m="2790580">into</span> <span m="2790820">one</span> <span m="2791070">side</span>
  <span m="2791470">and</span> <span m="2791660">the</span> <span m="2791780">unknown</span>
  <span m="2791990">terms</span> <span m="2792760">to</span> <span m="2792870">the</span>
  <span m="2792990">other</span> <span m="2793230">side.</span></p><p><span m="2798290">It''s</span>
  <span m="2798540">equal</span> <span m="2798890">to</span> <span m="2799175">f</span>
  <span m="2799860">of</span> <span m="2800180">V tilde</span> <span m="2800590">n
  plus</span> <span m="2800930">1,</span> <span m="2802280">which</span> <span m="2802380">is</span>
  <span m="2802510">known,</span> <span m="2803030">minus</span> <span m="2804060">delta</span>
  <span m="2804220">t</span> <span m="2804830">of</span> <span m="2806280">[INAUDIBLE]</span>
  <span m="2806744">minus</span> <span m="2807208">Vn.</span> <span m="2808600">I''m</span>
  <span m="2808740">going</span> <span m="2808860">to</span> <span m="2808920">solve</span>
  <span m="2809200">for</span> <span m="2809390">that</span> <span m="2809490">delta</span>
  <span m="2809770">V</span> <span m="2809980">again.</span> <span m="2812500">Once</span>
  <span m="2812730">I</span> <span m="2812840">solve</span> <span m="2813150">my</span>
  <span m="2813620">delta</span> <span m="2813780">V,</span> <span m="2814280">I''m</span>
  <span m="2814780">going</span> <span m="2814940">to</span> <span m="2815070">update</span>
  <span m="2815770">my</span> <span m="2816000">guess</span> <span m="2817290">to</span>
  <span m="2817530">be</span> <span m="2818920">my</span> <span m="2820300">first</span>
  <span m="2820590">iteration</span> <span m="2821060">guess</span> <span m="2821797">plus</span>
  <span m="2822930">the</span> <span m="2823190">update</span> <span m="2823550">again.</span></p><p><span
  m="2824680">And</span> <span m="2824860">then</span> <span m="2825210">here</span>
  <span m="2825550">goes</span> <span m="2825870">my</span> <span m="2826080">iteration</span>
  <span m="2826560">number</span> <span m="2826910">three.</span> <span m="2828130">I''m</span>
  <span m="2828300">going</span> <span m="2828430">to</span> <span m="2828500">keep</span>
  <span m="2828790">iterating</span> <span m="2829694">until</span> <span m="2830600">the</span>
  <span m="2830760">residual</span> <span m="2832320">drops</span> <span m="2832820">to</span>
  <span m="2833850">into</span> <span m="2834130">a</span> <span m="2834210">tolerance</span>
  <span m="2834580">level</span> <span m="2835070">that</span> <span m="2835400">I</span>
  <span m="2835530">think</span> <span m="2835850">is</span> <span m="2836050">small
  enough.</span> <span m="2841510">So</span> <span m="2841820">the</span> <span m="2842000">Newton-Raphson</span>
  <span m="2842870">iteration</span> <span m="2843380">is</span> <span m="2843710">really</span>
  <span m="2844380">another</span> <span m="2844880">way</span> <span m="2845120">of</span>
  <span m="2845310">using</span> <span m="2845750">Taylor</span> <span m="2846020">series</span>
  <span m="2846410">analysis</span> <span m="2850210">by</span> <span m="2850320">using
  the</span> <span m="2850710">fact</span> <span m="2850970">that</span> <span m="2851600">we</span>
  <span m="2851920">are</span> <span m="2852150">able</span> <span m="2852600">to</span>
  <span m="2853960">solve</span> <span m="2855380">these</span> <span m="2856260">increases</span>
  <span m="2856606">scheme</span> <span m="2857300">equations.</span></p><p><span
  m="2858000">So</span> <span m="2858180">if</span> <span m="2858540">we</span> <span
  m="2858680">derive</span> <span m="2859370">a</span> <span m="2859560">algebraic</span>
  <span m="2859890">equation</span> <span m="2860320">using</span> <span m="2860410">implicit</span>
  <span m="2860810">scheme,</span> <span m="2861710">we</span> <span m="2861870">know</span>
  <span m="2862070">how</span> <span m="2862200">to</span> <span m="2862300">solve</span>
  <span m="2862560">that</span> <span m="2862760">if it''s a</span> <span m="2863248">linear
  equation.</span> <span m="2865200">We</span> <span m="2865340">don''t</span> <span
  m="2865540">know</span> <span m="2865680">how</span> <span m="2865780">to solve</span>
  <span m="2866110">that</span> <span m="2866660">if</span> <span m="2866830">it''s</span>
  <span m="2866980">a nonlinear</span> <span m="2867510">equation.</span> <span m="2867830">But</span>
  <span m="2868010">we</span> <span m="2868140">can</span> <span m="2868320">approximate</span>
  <span m="2869070">it</span> <span m="2869100">using a</span> <span m="2869545">linear</span>
  <span m="2869990">equation</span> <span m="2871180">and</span> <span m="2871430">approximate</span>
  <span m="2872120">it</span> <span m="2872250">again</span> <span m="2872600">and</span>
  <span m="2872730">again.</span> <span m="2873790">When</span> <span m="2874080">I</span>
  <span m="2874750">have</span> <span m="2874950">a</span> <span m="2875140">better</span>
  <span m="2875500">estimate,</span> <span m="2876300">then</span> <span m="2876630">the</span>
  <span m="2876790">Taylor</span> <span m="2877110">series</span> <span m="2877490">approximation</span>
  <span m="2878180">is</span> <span m="2878360">even</span> <span m="2878680">better.</span>
  <span m="2879600">And</span> <span m="2879750">that</span> <span m="2879990">should</span>
  <span m="2880130">give</span> <span m="2880360">me</span> <span m="2881382">an</span>
  <span m="2881720">even</span> <span m="2882020">a</span> <span m="2882120">better</span>
  <span m="2882480">approximation</span> <span m="2882835">at the</span> <span m="2883190">next
  step.</span></p><p><span m="2886076">All right</span> <span m="2886560">is</span>
  <span m="2886660">it</span> <span m="2886720">clear?</span> <span m="2888990">I</span>
  <span m="2889050">mean,</span> <span m="2889170">one</span> <span m="2889670">of</span>
  <span m="2889800">the</span> <span m="2890160">Newton-Raphson</span> <span m="2890740">iterations</span>
  <span m="2891480">is</span> <span m="2891720">one</span> <span m="2891970">of</span>
  <span m="2892180">the</span> <span m="2892400">most</span> <span m="2892950">useful</span>
  <span m="2895480">numerical</span> <span m="2895930">techniques</span> <span m="2897566">that</span>
  <span m="2898050">really</span> <span m="2898400">goes</span> <span m="2899060">well</span>
  <span m="2899370">beyond</span> <span m="2900410">this</span> <span m="2900690">subject.</span>
  <span m="2906260">It</span> <span m="2906410">really</span> <span m="2906830">accomplishes</span>
  <span m="2907560">what</span> <span m="2908640">you can--</span> <span m="2909400">if</span>
  <span m="2909560">you</span> <span m="2909630">go</span> <span m="2909840">to</span>
  <span m="2909940">MATLAB,</span> <span m="2910480">you</span> <span m="2910640">can</span>
  <span m="2910840">use</span> <span m="2911110">fsolve.</span></p><p><span m="2911990">fsolve</span>
  <span m="2912500">usually</span> <span m="2913340">helps you</span> <span m="2913820">solve</span>
  <span m="2914450">nonlinear</span> <span m="2914820">equations.</span> <span m="2915686">But</span>
  <span m="2916182">fsolve</span> <span m="2916680">only</span> <span m="2916950">works</span>
  <span m="2917590">if</span> <span m="2917840">you</span> <span m="2917960">have</span>
  <span m="2919030">a small</span> <span m="2919130">amount</span> <span m="2919590">of</span>
  <span m="2919730">equations</span> <span m="2920180">you want to solve.</span> <span
  m="2923260">When</span> <span m="2923420">we</span> <span m="2923540">go</span>
  <span m="2923770">to</span> <span m="2924625">[INAUDIBLE]</span> <span m="2925010">when</span>
  <span m="2925240">we</span> <span m="2925370">want</span> <span m="2925540">to</span>
  <span m="2925760">solve--</span> <span m="2926800">[INAUDIBLE]</span> <span m="2927150">had</span>
  <span m="2927440">[INAUDIBLE]</span> <span m="2927830">you''re</span> <span m="2927970">going</span>
  <span m="2928090">to</span> <span m="2928160">find</span> <span m="2928430">out</span>
  <span m="2928980">maybe</span> <span m="2929340">we</span> <span m="2929560">have</span>
  <span m="2930650">millions</span> <span m="2931200">of</span> <span m="2931330">equations</span>
  <span m="2932070">we</span> <span m="2932250">want</span> <span m="2932420">to</span>
  <span m="2932510">solve</span> <span m="2932900">at the</span> <span m="2933335">same
  time.</span> <span m="2934640">And</span> <span m="2934900">the</span> <span m="2935160">fsolve</span>
  <span m="2935690">it</span> <span m="2935810">going</span> <span m="2935980">to
  be</span> <span m="2936670">helpful</span> <span m="2937230">in</span> <span m="2937530">the</span>
  <span m="2937650">situation.</span></p><p><span m="2938980">And</span> <span m="2939470">in</span>
  <span m="2939660">these</span> <span m="2939900">cases,</span> <span m="2940320">you</span>
  <span m="2940380">really</span> <span m="2940840">need</span> <span m="2941390">Newton-Raphson</span>
  <span m="2941750">equations</span> <span m="2943042">[INAUDIBLE].</span> <span m="2947560">Any</span>
  <span m="2948030">other</span> <span m="2948190">questions</span> <span m="2948980">on</span>
  <span m="2949130">Newton-Raphson.</span> <span m="2953504">Do you</span> <span m="2953990">guys</span>
  <span m="2954210">know</span> <span m="2954390">how</span> <span m="2954550">to</span>
  <span m="2954740">implement</span> <span m="2955260">a</span> <span m="2955320">Newton-Raphson</span>
  <span m="2956390">equation?</span> <span m="2958630">Sure?</span></p><p><span m="2959720">Because</span>
  <span m="2962575">I just</span> <span m="2963060">got</span> <span m="2963440">some</span>
  <span m="2963660">consensus</span> <span m="2964110">right before</span> <span m="2964564">class</span>
  <span m="2966380">on</span> <span m="2966630">some</span> <span m="2966830">of</span>
  <span m="2966980">the</span> <span m="2967080">questions.</span> <span m="2968020">When</span>
  <span m="2968240">you</span> <span m="2969130">try</span> <span m="2969330">to</span>
  <span m="2969520">solve--</span> <span m="2970270">let</span> <span m="2971020">me</span>
  <span m="2971350">say</span> <span m="2972420">one</span> <span m="2972680">word.</span>
  <span m="2974250">When</span> <span m="2974440">you</span> <span m="2974630">try</span>
  <span m="2974840">to</span> <span m="2975010">solve</span> <span m="2975360">this</span>
  <span m="2975550">equation,</span> <span m="2976090">you</span> <span m="2976290">want</span>
  <span m="2976480">to</span> <span m="2976590">solve</span> <span m="2976890">a</span>
  <span m="2976990">matrix</span> <span m="2978070">times</span> <span m="2978220">delta</span>
  <span m="2978410">v</span> <span m="2979090">equal</span> <span m="2979610">to</span>
  <span m="2980060">a</span> <span m="2980540">residual.</span> <span m="2980970">So
  this</span> <span m="2981130">is</span> <span m="2981240">the</span> <span m="2981850">residual,</span>
  <span m="2982105">right?</span></p><p><span m="2984620">It</span> <span m="2984820">is</span>
  <span m="2985000">really</span> <span m="2985890">important</span> <span m="2987460">to</span>
  <span m="2987650">construct</span> <span m="2988230">the</span> <span m="2988400">A</span>
  <span m="2988730">in</span> <span m="2988820">the</span> <span m="2988930">right</span>
  <span m="2989250">way.</span> <span m="2991760">Because</span> <span m="2992330">if</span>
  <span m="2992520">you</span> <span m="2992610">don''t</span> <span m="2992810">be</span>
  <span m="2992910">careful,</span> <span m="2993390">you</span> <span m="2993610">will</span>
  <span m="2993790">get</span> <span m="2994080">A</span> <span m="2994536">transposed</span>
  <span m="2994992">instead</span> <span m="2995448">of A.</span> <span m="2997730">OK.</span>
  <span m="2998630">And</span> <span m="2998870">when</span> <span m="2999120">you</span>
  <span m="2999585">solve</span> <span m="3000050">delta</span> <span m="3000270">V</span>
  <span m="3000740">equal to</span> <span m="3001100">A</span> <span m="3001410">inverse</span>
  <span m="3001675">times R,</span> <span m="3002880">it</span> <span m="3003090">is</span>
  <span m="3003250">really</span> <span m="3003560">important</span> <span m="3004040">that</span>
  <span m="3004260">A</span> <span m="3004490">inverse</span> <span m="3004980">is
  on</span> <span m="3005510">the</span> <span m="3005600">left-hand</span> <span
  m="3005870">side</span> <span m="3005990">of R</span> <span m="3006410">instead
  of</span> <span m="3006830">on the</span> <span m="3007250">right-hand</span> <span
  m="3007726">side.</span> <span m="3008680">Because</span> <span m="3009020">in</span>
  <span m="3009120">linear</span> <span m="3009370">algebra,</span> <span m="3009870">the</span>
  <span m="3010020">order</span> <span m="3010420">really</span> <span m="3010660">matters.</span></p><p><span
  m="3012680">OK.</span> <span m="3013370">And</span> <span m="3015060">how</span>
  <span m="3015660">the</span> <span m="3015890">entries</span> <span m="3016930">in</span>
  <span m="3017110">a</span> <span m="3017160">matrix</span> <span m="3017550">A</span>
  <span m="3018100">is</span> <span m="3019010">placed</span> <span m="3020110">is</span>
  <span m="3020350">also</span> <span m="3020890">important.</span> <span m="3024840">Let</span>
  <span m="3025030">me</span> <span m="3025110">make</span> <span m="3025340">a</span>
  <span m="3025400">new</span> <span m="3025570">page</span> <span m="3026270">just</span>
  <span m="3026460">to</span> <span m="3026570">make</span> <span m="3027170">my</span>
  <span m="3027310">point.</span> <span m="3027720">This</span> <span m="3029860">I</span>
  <span m="3029970">think</span> <span m="3030320">can</span> <span m="3030540">save</span>
  <span m="3030830">a</span> <span m="3030940">lot</span> <span m="3031170">of</span>
  <span m="3031880">headaches.</span></p><p><span m="3035350">If</span> <span m="3035690">delta</span>
  <span m="3035820">V</span> <span m="3036930">is</span> <span m="3038010">arranged</span>
  <span m="3038540">at</span> <span m="3038770">V1,</span> <span m="3039690">V2,</span>
  <span m="3040390">et cetera</span> <span m="3040880">to</span> <span m="3041070">Vn</span>
  <span m="3042430">and</span> <span m="3042770">R</span> <span m="3043310">is</span>
  <span m="3043800">arranged</span> <span m="3044290">as</span> <span m="3044910">R1</span>
  <span m="3045950">et cetera</span> <span m="3046450">to</span> <span m="3046670">Rn,</span>
  <span m="3049540">and</span> <span m="3049880">the</span> <span m="3050240">A</span>
  <span m="3051220">is</span> <span m="3051480">arranged</span> <span m="3051740">as</span>
  <span m="3053900">the</span> <span m="3054030">derivative</span> <span m="3054890">of</span>
  <span m="3055090">R1</span> <span m="3055930">to</span> <span m="3056960">V1</span>
  <span m="3057450">et cetera</span> <span m="3058010">to</span> <span m="3058140">derivative</span>
  <span m="3058800">of</span> <span m="3059100">R1</span> <span m="3061520">to</span>
  <span m="3061760">Vn</span> <span m="3063540">and</span> <span m="3063880">the</span>
  <span m="3063960">derivative</span> <span m="3064760">of</span> <span m="3064980">Rn</span>
  <span m="3067950">to</span> <span m="3068450">V1</span> <span m="3069600">derivative</span>
  <span m="3070020">of</span> <span m="3070430">Rn</span> <span m="3071510">to</span>
  <span m="3071790">Vn.</span> <span m="3074250">It</span> <span m="3074440">is</span>
  <span m="3074630">important</span> <span m="3075140">you</span> <span m="3075310">[INAUDIBLE]</span>
  <span m="3076590">rather</span> <span m="3077050">than</span> <span m="3077480">the</span>
  <span m="3077866">transport</span> <span m="3078252">of the</span> <span m="3078640">matrix.</span>
  <span m="3080270">Because</span> <span m="3081150">it''s</span> <span m="3081800">correct</span>
  <span m="3082440">Taylor</span> <span m="3082690">series</span> <span m="3082760">expansion</span>
  <span m="3083240">is</span> <span m="3085170">this</span> <span m="3085460">matrix</span>
  <span m="3087070">times</span> <span m="3087430">this</span> <span m="3087866">vector.</span></p><p><span
  m="3088738">If</span> <span m="3089174">you</span> <span m="3089610">do the</span>
  <span m="3089810">transpose</span> <span m="3090380">of</span> <span m="3090490">this
  matrix,</span> <span m="3091630">then you</span> <span m="3091960">would be</span>
  <span m="3092360">modifying</span> <span m="3093420">the</span> <span m="3093630">derivative</span>
  <span m="3094330">of</span> <span m="3095190">Rn</span> <span m="3095915">to</span>
  <span m="3096780">[INAUDIBLE]</span> <span m="3099270">Vn,</span> <span m="3099770">which</span>
  <span m="3099950">is</span> <span m="3100060">going to be</span> <span m="3100690">[INAUDIBLE].</span>
  <span m="3106260">And</span> <span m="3106460">then</span> <span m="3106710">you</span>
  <span m="3106840">do</span> <span m="3107210">delta V</span> <span m="3107510">equal</span>
  <span m="3107680">to</span> <span m="3109620">A</span> <span m="3109890">inverse</span>
  <span m="3110384">times</span> <span m="3111866">R.</span> <span m="3114336">So</span>
  <span m="3114830">just</span> <span m="3115324">want</span> <span m="3115818">to
  make</span> <span m="3116312">sure</span> <span m="3116806">you have</span> <span
  m="3117300">the</span> <span m="3117794">right</span> <span m="3118782">denominator</span>
  <span m="3119770">and</span> <span m="3120264">the</span> <span m="3121260">[INAUDIBLE]</span>
  <span m="3122979">inside the</span> <span m="3123442">matrix.</span> <span m="3125300">Is</span>
  <span m="3125760">this</span> <span m="3125960">clear?</span> <span m="3128780">When</span>
  <span m="3128930">you</span> <span m="3129240">do</span> <span m="3129390">this</span>
  <span m="3129710">in</span> <span m="3130030">MATLAB,</span> <span m="3130510">it''s</span>
  <span m="3130760">A</span> <span m="3131570">backslash</span> <span m="3131895">R.</span>
  <span m="3132930">That</span> <span m="3133350">gives</span> <span m="3133630">you</span>
  <span m="3135450">A</span> <span m="3135830">inverse</span> <span m="3136260">times
  R.</span> <span m="3143050">Questions?</span> <span m="3145690">No?</span></p><p><span
  m="3149020">OK.</span> <span m="3151330">So</span> <span m="3151580">the</span>
  <span m="3151720">rest</span> <span m="3152080">of</span> <span m="3152440">the</span>
  <span m="3152800">20</span> <span m="3153110">minutes,</span> <span m="3153480">I</span>
  <span m="3153700">want</span> <span m="3153930">to</span> <span m="3154110">have</span>
  <span m="3154330">some fun.</span> <span m="3156160">So</span> <span m="3156630">I</span>
  <span m="3157500">want</span> <span m="3157740">to</span> <span m="3158290">kind</span>
  <span m="3158480">of</span> <span m="3158590">have</span> <span m="3158830">you</span>
  <span m="3160130">try</span> <span m="3160960">in</span> <span m="3161190">your</span>
  <span m="3161480">own</span> <span m="3162130">computer</span> <span m="3162760">a</span>
  <span m="3162890">real</span> <span m="3163270">example</span> <span m="3163840">of</span>
  <span m="3164240">a</span> <span m="3164340">stiff</span> <span m="3164400">system.</span>
  <span m="3165950">And</span> <span m="3166100">I</span> <span m="3166190">have</span>
  <span m="3166430">a</span> <span m="3167450">joystick</span> <span m="3168140">over</span>
  <span m="3168370">here,</span> <span m="3168920">so</span> <span m="3168940">you</span>
  <span m="3169000">can</span> <span m="3169190">use.</span></p><p><span m="3169730">And</span>
  <span m="3170040">if</span> <span m="3170680">some</span> <span m="3170880">of</span>
  <span m="3171050">you</span> <span m="3171650">have</span> <span m="3172900">Simulink</span>
  <span m="3173450">installed</span> <span m="3173885">on your</span> <span m="3174320">computer,</span>
  <span m="3176500">feel</span> <span m="3176700">free</span> <span m="3176950">to</span>
  <span m="3177280">grab</span> <span m="3177540">your</span> <span m="3177640">computer,</span>
  <span m="3178110">come</span> <span m="3178340">to</span> <span m="3178540">here,</span>
  <span m="3178760">and</span> <span m="3179700">see</span> <span m="3180200">what</span>
  <span m="3180410">is</span> <span m="3180610">your</span> <span m="3180890">own</span>
  <span m="3181070">implementation</span> <span m="3182240">of</span> <span m="3182600">the</span>
  <span m="3182680">system.</span> <span m="3183800">So</span> <span m="3183890">this</span>
  <span m="3184070">is</span> <span m="3184190">system is</span> <span m="3184400">like</span>
  <span m="3184670">this.</span> <span m="3185270">So</span> <span m="3185400">let''</span>
  <span m="3185590">build</span> <span m="3185830">a</span> <span m="3185880">MATLAB</span>
  <span m="3186320">flight</span> <span m="3186590">simulator.</span></p><p><span
  m="3188240">OK.</span> <span m="3188710">[INAUDIBLE]</span> <span m="3189180">build</span>
  <span m="3189650">a</span> <span m="3190120">flight simulation</span> <span m="3190590">in
  MATLAB.</span> <span m="3193290">In</span> <span m="3193660">class,</span> <span
  m="3194000">I</span> <span m="3194090">won''t</span> <span m="3194380">be</span>
  <span m="3194480">able</span> <span m="3195180">to</span> <span m="3195790">simulate</span>
  <span m="3196240">the</span> <span m="3196330">whole</span> <span m="3196490">airplane.</span>
  <span m="3197280">I''m</span> <span m="3197390">only</span> <span m="3197750">to</span>
  <span m="3198090">be</span> <span m="3198290">able</span> <span m="3198540">to</span>
  <span m="3198670">simulate</span> <span m="3199370">the</span> <span m="3199825">pitch</span>
  <span m="3200280">motions,</span> <span m="3201190">the</span> <span m="3201310">longitudinal</span>
  <span m="3202940">motion</span> <span m="3203280">of the</span> <span m="3203420">airplane,</span>
  <span m="3204240">so</span> <span m="3204410">no</span> <span m="3204610">turning.</span>
  <span m="3205790">All</span> <span m="3206160">right.</span></p><p><span m="3207270">So</span>
  <span m="3207470">OK.</span> <span m="3208020">So</span> <span m="3208200">assume</span>
  <span m="3208540">the</span> <span m="3208690">[INAUDIBLE]</span> <span m="3209155">coefficient</span>
  <span m="3210780">is</span> <span m="3210970">equal</span> <span m="3211410">to</span>
  <span m="3212570">2</span> <span m="3212760">pi times</span> <span m="3213100">alpha.</span>
  <span m="3213960">So we''re</span> <span m="3214390">assuming</span> <span m="3214890">we</span>
  <span m="3215080">have</span> <span m="3215950">[INAUDIBLE]</span> <span m="3216215">air</span>
  <span m="3216480">foil--</span> <span m="3219650">if</span> <span m="3220020">you</span>
  <span m="3220140">do</span> <span m="3220320">think</span> <span m="3220550">[INAUDIBLE]</span>
  <span m="3220890">theory,</span> <span m="3221360">that</span> <span m="3221510">is</span>
  <span m="3221870">exactly</span> <span m="3222380">what</span> <span m="3222600">I''m
  going</span> <span m="3222800">to</span> <span m="3222880">get,</span> <span m="3224054">2
  pi</span> <span m="3224486">times</span> <span m="3224920">alpha</span> <span m="3225200">angle</span>
  <span m="3225460">of attack.</span> <span m="3228440">And</span> <span m="3230690">we</span>
  <span m="3230900">have</span> <span m="3231350">the</span> <span m="3231470">lift</span>
  <span m="3231870">and</span> <span m="3232080">drag</span> <span m="3233150">to</span>
  <span m="3233270">be</span> <span m="3233400">proportional</span> <span m="3234160">to</span>
  <span m="3234280">Cd</span> <span m="3234890">and</span> <span m="3236850">proportional</span>
  <span m="3237570">to</span> <span m="3238590">Cd</span> <span m="3240210">and</span>
  <span m="3240380">Cl.</span></p><p><span m="3242460">And</span> <span m="3243500">the</span>
  <span m="3243790">dynamics</span> <span m="3244430">is</span> <span m="3244640">that</span>
  <span m="3245680">dvdt,</span> <span m="3246930">the</span> <span m="3247100">derivative</span>
  <span m="3247790">of</span> <span m="3247970">my</span> <span m="3248120">velocity,</span>
  <span m="3248920">is</span> <span m="3249210">equal</span> <span m="3249690">to</span>
  <span m="3249870">minus</span> <span m="3250270">D,</span> <span m="3251370">the</span>
  <span m="3251450">drag</span> <span m="3253694">times</span> <span m="3254120">the</span>
  <span m="3254550">gravity</span> <span m="3255180">component</span> <span m="3255850">in</span>
  <span m="3255980">the</span> <span m="3256070">backwards</span> <span m="3256570">reaction.</span>
  <span m="3257510">So</span> <span m="3257750">if</span> <span m="3258000">the</span>
  <span m="3258070">my</span> <span m="3258260">airplane</span> <span m="3260760">has</span>
  <span m="3261340">a</span> <span m="3261620">drag,</span> <span m="3262400">has</span>
  <span m="3262590">a</span> <span m="3262660">pitch</span> <span m="3263100">of</span>
  <span m="3263520">theta,</span> <span m="3264480">I''m</span> <span m="3264740">going</span>
  <span m="3264900">to</span> <span m="3265060">have</span> <span m="3266590">deceleration</span>
  <span m="3267380">mg</span> <span m="3267950">cosine</span> <span m="3268110">theta.</span></p><p><span
  m="3270190">And</span> <span m="3270870">the</span> <span m="3271040">rate</span>
  <span m="3271280">of</span> <span m="3271410">change</span> <span m="3271710">of</span>
  <span m="3271890">theta,</span> <span m="3272190">which</span> <span m="3272490">is</span>
  <span m="3272610">my</span> <span m="3272860">pitch,</span> <span m="3273200">is</span>
  <span m="3273870">proportional</span> <span m="3274540">to</span> <span m="3274650">the</span>
  <span m="3274760">lift</span> <span m="3275840">minus</span> <span m="3278750">the</span>
  <span m="3278880">gravity</span> <span m="3279400">component</span> <span m="3280000">in</span>
  <span m="3280120">the</span> <span m="3280220">cosine</span> <span m="3280580">direction.</span>
  <span m="3281630">So</span> <span m="3281800">that</span> <span m="3281980">is</span>
  <span m="3282120">my</span> <span m="3282560">dynamic.</span> <span m="3283848">So</span>
  <span m="3284282">see</span> <span m="3284716">[INAUDIBLE],</span> <span m="3285150">I</span>
  <span m="3285340">have</span> <span m="3285620">two</span> <span m="3285850">couple</span>
  <span m="3286230">differential</span> <span m="3286670">equations</span> <span m="3287040">already</span>
  <span m="3287400">where</span> <span m="3287730">the</span> <span m="3287870">terms</span>
  <span m="3288280">d and</span> <span m="3288620">l</span> <span m="3288960">are</span>
  <span m="3291000">expressing</span> <span m="3291700">in</span> <span m="3291800">terms</span>
  <span m="3292040">of</span> <span m="3292170">these.</span></p><p><span m="3293710">Now,</span>
  <span m="3296510">the</span> <span m="3296680">rate</span> <span m="3296910">of</span>
  <span m="3297050">change</span> <span m="3297500">of</span> <span m="3300230">alpha,</span>
  <span m="3301610">that</span> <span m="3301920">is</span> <span m="3302840">the</span>
  <span m="3302930">angle</span> <span m="3303170">of</span> <span m="3303310">attack,</span>
  <span m="3304350">I</span> <span m="3304520">am</span> <span m="3304680">going</span>
  <span m="3304920">to</span> <span m="3305450">model</span> <span m="3305870">this</span>
  <span m="3306160">as</span> <span m="3306420">input</span> <span m="3306950">minus</span>
  <span m="3307436">alpha</span> <span m="3308500">divided</span> <span m="3308940">by</span>
  <span m="3309340">Tau.</span> <span m="3310180">So</span> <span m="3310350">that</span>
  <span m="3311370">is</span> <span m="3311510">the</span> <span m="3311580">model</span>
  <span m="3311940">of</span> <span m="3312000">the</span> <span m="3312800">longitudinal</span>
  <span m="3313620">stability.</span> <span m="3314790">OK.</span> <span m="3315560">So</span>
  <span m="3315730">this</span> <span m="3315960">is</span> <span m="3316270">the</span>
  <span m="3316390">case</span> <span m="3316860">where</span> <span m="3317430">I</span>
  <span m="3317590">actually</span> <span m="3318030">have</span> <span m="3318340">a</span>
  <span m="3318370">longitudinal</span> <span m="3319240">stability.</span></p><p><span
  m="3320100">Otherwise,</span> <span m="3320890">the</span> <span m="3321440">sign</span>
  <span m="3321820">would</span> <span m="3321910">be</span> <span m="3322490">the</span>
  <span m="3322660">other</span> <span m="3322920">way.</span> <span m="3324090">So</span>
  <span m="3324490">alpha</span> <span m="3324890">is</span> <span m="3325000">my</span>
  <span m="3325120">input.</span> <span m="3325630">I''m</span> <span m="3325770">going</span>
  <span m="3325960">to</span> <span m="3326250">use</span> <span m="3326550">the</span>
  <span m="3326640">[INAUDIBLE],</span> <span m="3326915">add</span> <span m="3327190">my</span>
  <span m="3327633">input</span> <span m="3328520">in.</span> <span m="3329390">And</span>
  <span m="3329580">alpha is</span> <span m="3330080">the</span> <span m="3330580">angle</span>
  <span m="3331080">of attack.</span></p><p><span m="3333080">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="3337840">PROFESSOR: Tau</span> <span m="3338420">is</span> <span m="3338640">a</span>
  <span m="3338740">value</span> <span m="3339280">I''m</span> <span m="3339470">going</span>
  <span m="3339620">to</span> <span m="3339720">set.</span> <span m="3341720">Tau</span>
  <span m="3341930">is</span> <span m="3342140">going</span> <span m="3342300">to</span>
  <span m="3342380">be--</span> <span m="3342960">so</span> <span m="3343300">what</span>
  <span m="3343460">do</span> <span m="3343530">you</span> <span m="3343590">think</span>
  <span m="3344190">the</span> <span m="3344280">value</span> <span m="3344590">of</span>
  <span m="3344650">Tau</span> <span m="3345570">should</span> <span m="3345780">be</span>
  <span m="3346150">if</span> <span m="3346330">I</span> <span m="3346490">have</span>
  <span m="3346660">a</span> <span m="3346720">very</span> <span m="3347130">stable</span>
  <span m="3347600">system,</span> <span m="3348100">if</span> <span m="3348340">my</span>
  <span m="3348510">Cd</span> <span m="3349110">is</span> <span m="3349270">way</span>
  <span m="3350000">in front</span> <span m="3350735">of</span> <span m="3351090">my</span>
  <span m="3351480">aerodynamic</span> <span m="3352130">sample?</span></p><p><span
  m="3356026">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3361870">PROFESSOR: So</span>
  <span m="3362020">if</span> <span m="3362160">I</span> <span m="3362290">have</span>
  <span m="3362420">a</span> <span m="3362470">very</span> <span m="3363150">stable</span>
  <span m="3363700">system,</span> <span m="3364430">Tau</span> <span m="3364670">should</span>
  <span m="3364770">be</span> <span m="3364950">very</span> <span m="3365240">large</span>
  <span m="3365490">or</span> <span m="3365540">very</span> <span m="3365790">small?</span></p><p><span
  m="3367125">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3367570">PROFESSOR: Large?</span>
  <span m="3368905">Are you</span> <span m="3369350">sure?</span> <span m="3372436">So</span>
  <span m="3373330">what</span> <span m="3373500">happens</span> <span m="3373830">if</span>
  <span m="3373950">I</span> <span m="3374040">have</span> <span m="3374240">a</span>
  <span m="3374300">very</span> <span m="3375170">stable</span> <span m="3375480">system?</span>
  <span m="3375860">If</span> <span m="3376770">I</span> <span m="3376880">pitch</span>
  <span m="3377240">the</span> <span m="3377622">airplane</span> <span m="3378770">off,</span>
  <span m="3379860">is</span> <span m="3380220">it</span> <span m="3380500">going
  to</span> <span m="3380720">come</span> <span m="3380950">back</span> <span m="3381870">fast</span>
  <span m="3382230">or</span> <span m="3382630">come</span> <span m="3382780">back</span>
  <span m="3383070">very--</span></p><p><span m="3383491">AUDIENCE: Fast.</span></p><p><span
  m="3384333">PROFESSOR: Fast,</span> <span m="3385600">right.</span> <span m="3386020">So</span>
  <span m="3386210">if</span> <span m="3387630">I</span> <span m="3387750">have</span>
  <span m="3387900">a</span> <span m="3387940">very</span> <span m="3388220">stable</span>
  <span m="3388600">system,</span> <span m="3389380">Tau</span> <span m="3389580">is</span>
  <span m="3389760">going to be</span> <span m="3389880">very small.</span> <span
  m="3391720">If</span> <span m="3391930">I</span> <span m="3391970">have</span> <span
  m="3392440">a</span> <span m="3392920">marginally</span> <span m="3393610">stable</span>
  <span m="3393980">system,</span> <span m="3395312">Tau is</span> <span m="3395756">going
  to be</span> <span m="3396200">very large.</span> <span m="3397090">So</span> <span
  m="3397300">Tau</span> <span m="3397770">has</span> <span m="3398970">the</span>
  <span m="3400460">unit</span> <span m="3400840">of</span> <span m="3401280">pi.</span>
  <span m="3402600">It''s</span> <span m="3402810">really</span> <span m="3403070">kind</span>
  <span m="3403250">of</span> <span m="3403480">how</span> <span m="3403620">long</span>
  <span m="3404060">that it</span> <span m="3404436">takes</span> <span m="3404812">for
  the</span> <span m="3405190">airplane</span> <span m="3405520">to</span> <span m="3405976">cut</span>
  <span m="3406432">to</span> <span m="3408260">static</span> <span m="3408710">stability.</span></p><p><span
  m="3410350">I have two</span> <span m="3410650">files.</span> <span m="3411625">One</span>
  <span m="3412090">is</span> <span m="3412350">the</span> <span m="3412710">longitudinal</span>
  <span m="3414180">[INAUDIBLE]</span> <span m="3414665">n.</span> <span m="3416120">So</span>
  <span m="3416610">this</span> <span m="3416830">function</span> <span m="3417510">is</span>
  <span m="3417710">really</span> <span m="3418290">[INAUDIBLE]</span> <span m="3419130">exactly</span>
  <span m="3419720">the</span> <span m="3419870">same</span> <span m="3421330">differential</span>
  <span m="3421740">equation</span> <span m="3422201">I just</span> <span m="3422662">showed</span>
  <span m="3423123">on the</span> <span m="3423584">slide.</span> <span m="3424506">So</span>
  <span m="3424970">I</span> <span m="3425130">have</span> <span m="3425370">four</span>
  <span m="3425560">variables.</span> <span m="3426730">They</span> <span m="3426890">are</span>
  <span m="3428290">the</span> <span m="3428580">velocity,</span> <span m="3430240">the</span>
  <span m="3430660">pitch angle,</span> <span m="3431080">the</span> <span m="3431360">angle</span>
  <span m="3431720">of attack,</span> <span m="3433157">and</span> <span m="3433636">my</span>
  <span m="3434115">altitude.</span></p><p><span m="3437468">I have all the</span>
  <span m="3437947">[INAUDIBLE]</span> <span m="3438426">defined</span> <span m="3438905">here.</span>
  <span m="3439384">I have my</span> <span m="3439863">Cl</span> <span m="3440342">equal</span>
  <span m="3440821">to</span> <span m="3441310">2pi</span> <span m="3441780">times
  alpha.</span> <span m="3442262">I can</span> <span m="3442744">do the drag</span>
  <span m="3443226">in this.</span> <span m="3444190">[INAUDIBLE].</span> <span m="3450456">And</span>
  <span m="3450938">I</span> <span m="3451420">have</span> <span m="3451902">the</span>
  <span m="3452400">dvdt,</span> <span m="3453350">the</span> <span m="3453790">theta</span>
  <span m="3454020">dt,</span> <span m="3454330">the alpha dt,</span> <span m="3455320">and</span>
  <span m="3455815">[INAUDIBLE].</span> <span m="3465818">So</span> <span m="3466266">if
  you</span> <span m="3466714">guys</span> <span m="3467170">implement</span> <span
  m="3468270">your own</span> <span m="3468570">computer</span> <span m="3468680">using</span>
  <span m="3469916">[INAUDIBLE]</span> <span m="3470740">style,</span> <span m="3473170">[INAUDIBLE].</span></p><p><span
  m="3486890">And here,</span> <span m="3487340">I</span> <span m="3487500">have</span>
  <span m="3487650">Tau</span> <span m="3487850">equal to</span> <span m="3488060">0.001.</span>
  <span m="3489070">Does</span> <span m="3489550">that</span> <span m="3489790">mean</span>
  <span m="3491150">I</span> <span m="3491350">have</span> <span m="3491590">a</span>
  <span m="3491943">very stable</span> <span m="3492296">system</span> <span m="3492870">or</span>
  <span m="3493170">a</span> <span m="3493470">not</span> <span m="3493790">very stable</span>
  <span m="3494224">system?</span> <span m="3496394">I got</span> <span m="3496830">a</span>
  <span m="3497130">very stable</span> <span m="3497380">system, right.</span> <span
  m="3498366">I get</span> <span m="3498859">a very stable</span> <span m="3499352">[INAUDIBLE].</span></p><p><span
  m="3511677">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3521044">PROFESSOR: And</span>
  <span m="3521537">if you</span> <span m="3522030">succeeded</span> <span m="3522550">[INAUDIBLE]</span>
  <span m="3527180">you can</span> <span m="3528180">[INAUDIBLE]</span> <span m="3528680">input</span>
  <span m="3529180">[INAUDIBLE]</span> <span m="3529680">alpha</span> <span m="3530180">[INAUDIBLE].</span>
  <span m="3530680">It''s kind of like</span> <span m="3531180">visualizing</span>
  <span m="3532058">[INAUDIBLE].</span> <span m="3534990">For</span> <span m="3535490">example,</span>
  <span m="3535990">I can</span> <span m="3536490">[INAUDIBLE].</span> <span m="3555148">It
  just</span> <span m="3555600">kind of</span> <span m="3555660">visualizes</span>
  <span m="3556250">[INAUDIBLE].</span> <span m="3557770">This is</span> <span m="3557840">a</span>
  <span m="3558160">[INAUDIBLE].</span> <span m="3565000">I think</span> <span m="3565495">I</span>
  <span m="3566485">[INAUDIBLE].</span></p><p><span m="3574900">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="3586159">PROFESSOR: [INAUDIBLE]</span> <span m="3587630">your</span> <span m="3587750">own</span>
  <span m="3588220">[INAUDIBLE]</span> <span m="3592076">on</span> <span m="3592460">the</span>
  <span m="3592580">joystick,</span> <span m="3592950">you can</span> <span m="3593300">really</span>
  <span m="3593620">control</span> <span m="3594026">your aircraft.</span> <span m="3595244">You
  can</span> <span m="3595650">really</span> <span m="3595860">control</span> <span
  m="3596352">your</span> <span m="3596844">[INAUDIBLE]</span> <span m="3597336">simulated</span>
  <span m="3597828">[INAUDIBLE].</span> <span m="3603740">So let''s</span> <span m="3603890">do
  this.</span> <span m="3604880">Just</span> <span m="3605040">for</span> <span m="3605200">the</span>
  <span m="3605300">rest</span> <span m="3605530">of</span> <span m="3605670">the</span>
  <span m="3606152">five minutes,</span> <span m="3606634">I''ll just</span> <span
  m="3607116">let you</span> <span m="3607598">have fun</span> <span m="3608080">for</span>
  <span m="3608562">yourself.</span> <span m="3609044">And</span> <span m="3609530">one</span>
  <span m="3609770">thing</span> <span m="3609920">I</span> <span m="3610070">want</span>
  <span m="3610310">to show</span> <span m="3610810">you</span> <span m="3611310">is</span>
  <span m="3611810">that--</span> <span m="3613090">so</span> <span m="3613590">here,</span>
  <span m="3613970">I</span> <span m="3614290">[INAUDIBLE].</span></p><p><span m="3615040">And</span>
  <span m="3615250">the way</span> <span m="3615610">I</span> <span m="3615710">did
  is</span> <span m="3617024">[INAUDIBLE]</span> <span m="3617486">can save</span>
  <span m="3617948">this file.</span> <span m="3622110">And</span> <span m="3625050">the</span>
  <span m="3625160">way</span> <span m="3625480">I</span> <span m="3627460">[INAUDIBLE]</span>
  <span m="3627770">the joystick</span> <span m="3628020">input</span> <span m="3628700">is</span>
  <span m="3628940">by</span> <span m="3629290">setting</span> <span m="3629700">[INAUDIBLE]</span>
  <span m="3630010">equal</span> <span m="3630140">to</span> <span m="3630310">[INAUDIBLE].</span>
  <span m="3633410">That</span> <span m="3633660">actually</span> <span m="3633860">gives</span>
  <span m="3634090">you</span> <span m="3634640">a</span> <span m="3634920">joystick.</span></p><p><span
  m="3637440">It''s</span> <span m="3637950">like</span> <span m="3638140">a</span>
  <span m="3638220">handle.</span> <span m="3638750">It  gives</span> <span m="3639130">you</span>
  <span m="3639470">a</span> <span m="3639910">joystick</span> <span m="3640350">handle.</span>
  <span m="3641230">And</span> <span m="3641670">in</span> <span m="3641880">[INAUDIBLE]</span>
  <span m="3645750">from</span> <span m="3645980">the</span> <span m="3646080">dropbox,</span>
  <span m="3647250">what</span> <span m="3647490">I</span> <span m="3647610">did is</span>
  <span m="3648100">the</span> <span m="3648525">input</span> <span m="3648950">equal
  to</span> <span m="3649120">axis.</span> <span m="3655840">So I</span> <span m="3656320">did
  the</span> <span m="3656800">input</span> <span m="3657530">[INAUDIBLE]</span> <span
  m="3658040">to</span> <span m="3659012">axis</span> <span m="3659360">[INAUDIBLE]</span>
  <span m="3659770">2.</span> <span m="3660600">So</span> <span m="3661390">this</span>
  <span m="3661670">is</span> <span m="3661890">the</span> <span m="3662540">axis</span>
  <span m="3663560">when</span> <span m="3663820">I</span> <span m="3664340">[INAUDIBLE].</span></p><p><span
  m="3668442">And</span> <span m="3670330">the</span> <span m="3670770">[INAUDIBLE]</span>
  <span m="3671040">is</span> <span m="3671320">the</span> <span m="3671600">third</span>
  <span m="3672080">axis.</span> <span m="3672572">And</span> <span m="3673064">it
  happens to be</span> <span m="3673556">this one.</span> <span m="3674540">The</span>
  <span m="3675032">first</span> <span m="3675524">axis</span> <span m="3676016">I
  think we</span> <span m="3677000">[INAUDIBLE].</span> <span m="3678480">If you guys</span>
  <span m="3678930">have</span> <span m="3679313">time,</span> <span m="3679696">that''d</span>
  <span m="3680080">help me</span> <span m="3680350">explain</span> <span m="3680600">this</span>
  <span m="3680860">to you</span> <span m="3681165">something</span> <span m="3682070">more
  like</span> <span m="3682370">real</span> <span m="3682740">simulator,</span> <span
  m="3683110">that''s</span> <span m="3683435">be</span> <span m="3683760">great.</span></p><p><span
  m="3685962">OK.</span> <span m="3689770">This</span> <span m="3690020">is</span>
  <span m="3690430">[INAUDIBLE].</span> <span m="3693080">[INAUDIBLE]</span> <span
  m="3693860">my</span> <span m="3694820">view</span> <span m="3695080">which</span>
  <span m="3695410">is</span> <span m="3695520">the</span> <span m="3695570">[INAUDIBLE]</span>
  <span m="3696250">of</span> <span m="3696640">the</span> <span m="3697030">velocity,</span>
  <span m="3698900">each</span> <span m="3699150">angle,</span> <span m="3699390">angle</span>
  <span m="3699740">of</span> <span m="3699970">attack,</span> <span m="3700427">and</span>
  <span m="3700884">altitude</span> <span m="3701800">is</span> <span m="3702190">equal</span>
  <span m="3702620">to</span> <span m="3703360">the last</span> <span m="3704100">variable</span>
  <span m="3704660">plus</span> <span m="3705440">delta</span> <span m="3705680">t</span>
  <span m="3706110">times</span> <span m="3707660">the</span> <span m="3707770">function</span>
  <span m="3708075">[INAUDIBLE].</span> <span m="3710510">And</span> <span m="3710760">I''ve</span>
  <span m="3710800">[INAUDIBLE]</span> <span m="3711920">and</span> <span m="3712860">did</span>
  <span m="3713040">the</span> <span m="3713140">display.</span> <span m="3717700">The</span>
  <span m="3717985">[INAUDIBLE]</span> <span m="3718410">is</span> <span m="3718790">asking</span>
  <span m="3719266">[INAUDIBLE]</span> <span m="3719742">the whole</span> <span m="3720218">thing.</span>
  <span m="3721170">But</span> <span m="3721646">[INAUDIBLE]</span> <span m="3722598">that</span>
  <span m="3724030">[INAUDIBLE]</span> <span m="3726310">very</span> <span m="3726660">much</span>
  <span m="3727170">depends</span> <span m="3727530">on</span> <span m="3728730">this</span>
  <span m="3729040">thing,</span> <span m="3729810">very</span> <span m="3730120">much</span>
  <span m="3730350">depend</span> <span m="3730780">on my</span> <span m="3731210">Tau.</span></p><p><span
  m="3732500">So</span> <span m="3733380">right now,</span> <span m="3733540">my</span>
  <span m="3733670">Tau</span> <span m="3734530">is</span> <span m="3734960">plus
  1.</span> <span m="3735180">It''s</span> <span m="3736060">stable,</span> <span
  m="3736410">but</span> <span m="3736760">not</span> <span m="3737030">that</span>
  <span m="3737270">stable.</span> <span m="3738400">If</span> <span m="3738580">I</span>
  <span m="3738700">[INAUDIBLE]</span> <span m="3739050">it</span> <span m="3739180">to</span>
  <span m="3739490">0.001,</span> <span m="3740240">it''s</span> <span m="3740480">going</span>
  <span m="3740620">to</span> <span m="3740700">be</span> <span m="3740800">a</span>
  <span m="3740870">more</span> <span m="3741120">stable</span> <span m="3741550">system.</span>
  <span m="3743270">But what</span> <span m="3743590">does</span> <span m="3743690">that</span>
  <span m="3743920">mean?</span> <span m="3745142">That</span> <span m="3745618">means</span>
  <span m="3746094">it''s</span> <span m="3746570">[INAUDIBLE],</span> <span m="3747010">right?</span></p><p><span
  m="3747600">It</span> <span m="3747700">has</span> <span m="3748010">a</span> <span
  m="3748250">smaller</span> <span m="3748610">timescale</span> <span m="3749320">that
  is</span> <span m="3750670">much</span> <span m="3751040">smaller</span> <span m="3751300">than</span>
  <span m="3751800">the</span> <span m="3751890">one I''m</span> <span m="3752160">interested</span>
  <span m="3752390">in,</span> <span m="3752770">which</span> <span m="3753150">is</span>
  <span m="3753530">the</span> <span m="3753960">[INAUDIBLE]</span> <span m="3755220">the</span>
  <span m="3755640">longitudinal</span> <span m="3756060">motion</span> <span m="3756350">of</span>
  <span m="3756490">aircraft.</span> <span m="3758190">So</span> <span m="3758360">if</span>
  <span m="3758520">I</span> <span m="3758650">set</span> <span m="3758910">to be</span>
  <span m="3759350">that</span> <span m="3760640">value</span> <span m="3761100">in</span>
  <span m="3761350">MATLAB</span> <span m="3761710">for</span> <span m="3762030">[INAUDIBLE].</span>
  <span m="3763311">If</span> <span m="3763740">I</span> <span m="3763880">want</span>
  <span m="3764180">to</span> <span m="3765230">simulate</span> <span m="3766710">[INAUDIBLE],</span>
  <span m="3772650">what</span> <span m="3772820">happens</span> <span m="3773300">is</span>
  <span m="3773510">my</span> <span m="3774840">altitude</span> <span m="3775200">is</span>
  <span m="3775460">10</span> <span m="3775880">to</span> <span m="3776300">the</span>
  <span m="3777560">16.</span></p><p><span m="3778854">And</span> <span m="3780750">basically,</span>
  <span m="3782290">the</span> <span m="3782500">airplane</span> <span m="3782950">goes</span>
  <span m="3783875">unstable.</span> <span m="3784960">Not</span> <span m="3785280">unstable</span>
  <span m="3785730">physically,</span> <span m="3786620">but</span> <span m="3786890">unstable</span>
  <span m="3787510">numerically.</span> <span m="3788370">It''s</span> <span m="3788850">not</span>
  <span m="3789040">the</span> <span m="3789190">airplane</span> <span m="3789540">goes</span>
  <span m="3789790">unstable.</span> <span m="3790430">But</span> <span m="3790620">it''s</span>
  <span m="3790770">my</span> <span m="3791340">[INAUDIBLE]</span> <span m="3791940">integrator</span>
  <span m="3792493">goes</span> <span m="3792836">unstable.</span> <span m="3795340">It</span>
  <span m="3795520">is</span> <span m="3795800">particularly</span> <span m="3796400">unstable</span>
  <span m="3796870">in</span> <span m="3796980">the</span> <span m="3797150">pitch</span>
  <span m="3797980">direction.</span> <span m="3799400">Because</span> <span m="3800300">in</span>
  <span m="3800470">the</span> <span m="3800600">pitch</span> <span m="3801725">dimension,</span>
  <span m="3802463">i have</span> <span m="3802916">a timescale</span> <span m="3803822">that
  is</span> <span m="3804275">much, much</span> <span m="3804730">smaller.</span></p><p><span
  m="3806290">So</span> <span m="3806470">if</span> <span m="3806680">you</span> <span
  m="3806840">guys</span> <span m="3807100">are</span> <span m="3807220">interested,</span>
  <span m="3809050">take</span> <span m="3809390">the</span> <span m="3809590">[INAUDIBLE]</span>
  <span m="3809850">I have</span> <span m="3810110">and</span> <span m="3812280">[INAUDIBLE]</span>
  <span m="3813480">integrate</span> <span m="3813760">on</span> <span m="3814020">it</span>
  <span m="3815030">using</span> <span m="3815430">Newton-Raphson.</span> <span m="3817570">That</span>
  <span m="3817830">way</span> <span m="3819750">if</span> <span m="3820070">somebody</span>
  <span m="3820470">is</span> <span m="3820580">able</span> <span m="3820830">to</span>
  <span m="3820920">do</span> <span m="3821120">that</span> <span m="3821940">and</span>
  <span m="3822290">bring</span> <span m="3822940">the</span> <span m="3823090">demo</span>
  <span m="3823530">next</span> <span m="3823970">class,</span> <span m="3825308">that''s</span>
  <span m="3825766">fantastic.</span> <span m="3827140">And</span> <span m="3827415">that
  also</span> <span m="3827690">saves</span> <span m="3828390">you</span> <span m="3828710">the
  homework</span> <span m="3829176">this week.</span> <span m="3829642">Because</span>
  <span m="3830108">the homework</span> <span m="3830574">this week</span> <span m="3831040">is
  going to be</span> <span m="3831506">about that.</span></p><p><span m="3834310">So</span>
  <span m="3835300">if</span> <span m="3835790">you</span> <span m="3836150">do</span>
  <span m="3836430">that</span> <span m="3837540">before</span> <span m="3837930">next
  class,</span> <span m="3838892">you can</span> <span m="3839373">demo in</span>
  <span m="3839854">class,</span> <span m="3840816">and</span> <span m="3841300">you</span>
  <span m="3841460">already</span> <span m="3841630">solved</span> <span m="3842126">a
  big</span> <span m="3842622">part of</span> <span m="3843614">this</span> <span
  m="3844110">week''s</span> <span m="3844606">homework.</span> <span m="3845600">All
  right.</span> <span m="3847612">OK.</span> <span m="3848030">And</span> <span m="3849070">what</span>
  <span m="3849410">you</span> <span m="3849780">[INAUDIBLE]</span> <span m="3849910">is
  already</span> <span m="3850370">in the</span> <span m="3851570">[INAUDIBLE].</span>
  <span m="3853070">So</span> <span m="3853370">I will</span> <span m="3853670">see</span>
  <span m="3853970">you all</span> <span m="3854570">Wednesday.</span></p>'
type: course
uid: 947c6f55aad148935a11bb3b8680890e

---
None