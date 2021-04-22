---
about_this_resource_text: <p><strong>Description:</strong> This session introduces
  finite volume methods, comparing to finite difference. After discussing scalar conservation
  laws, and shockwaves, the session introduces an example of upwinding.</p> <p><strong>Instructor:</strong>
  Qiqi Wang</p><p>The recording quality of this video is the best available from the
  source.</p>
course_id: 16-90-computational-methods-in-aerospace-engineering-spring-2014
embedded_media:
- id: Video-YouTube-Stream
  media_location: 6hewlsfqltY
  parent_uid: 3a8bbc2c8709aba5e65bf7332373e1c2
  title: Video-YouTube-Stream
  type: Video
  uid: 7be572720e88bbac594fad5a16766f3e
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/6hewlsfqltY/default.jpg
  parent_uid: 3a8bbc2c8709aba5e65bf7332373e1c2
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 27fa88d7c8db89f1952065d4008dff29
- id: 3Play-3PlayYouTubeid-MP4
  media_location: 6hewlsfqltY
  parent_uid: 3a8bbc2c8709aba5e65bf7332373e1c2
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 9d0fd715efdcfb5dabaa01bb233e7df8
- id: 6hewlsfqltY.srt
  parent_uid: 3a8bbc2c8709aba5e65bf7332373e1c2
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-10-numerical-methods-of-pdes-finite-volume-methods-1/6hewlsfqltY.srt
  title: 3play caption file
  type: null
  uid: b047e2b510d38d02e9e4dc558dba4710
- id: 6hewlsfqltY.pdf
  parent_uid: 3a8bbc2c8709aba5e65bf7332373e1c2
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-10-numerical-methods-of-pdes-finite-volume-methods-1/6hewlsfqltY.pdf
  title: 3play pdf file
  type: null
  uid: e664099cec83dbbbb4951896bdab226b
- id: Caption-3Play YouTube id-SRT
  parent_uid: 3a8bbc2c8709aba5e65bf7332373e1c2
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: fcac275c1379bdbca6be9f56c5a687bb
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 3a8bbc2c8709aba5e65bf7332373e1c2
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: f1d112ee0087f4d055efb18a8cc420ab
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT16.90S14/MIT16_90S14_L10_300k.mp4
  parent_uid: 3a8bbc2c8709aba5e65bf7332373e1c2
  title: Video-Internet Archive-MP4
  type: Video
  uid: 89ded005a5488b07572e52a7640cbbd8
inline_embed_id: 49241796session10:numericalmethodsofpdes:finitevolumemethods135571114
layout: video
order_index: null
parent_uid: 809ebf7c44bfb36e8786306747d7e32f
related_resources_text: ''
short_url: session-10-numerical-methods-of-pdes-finite-volume-methods-1
technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-10-numerical-methods-of-pdes-finite-volume-methods-1
template_type: Tabbed
title: 'Session 10: Numerical Methods of PDEs: Finite Volume Methods 1'
transcript: '<p><span m="30">The</span> <span m="130">following</span> <span m="600">content</span>
  <span m="1090">is</span> <span m="1210">provided</span> <span m="1660">under</span>
  <span m="1900">a</span> <span m="1950">Creative</span> <span m="2400">Commons</span>
  <span m="2820">license.</span> <span m="3770">Your</span> <span m="3880">support</span>
  <span m="4400">will</span> <span m="4570">help</span> <span m="4790">MIT</span>
  <span m="5280">OpenCourseWare</span> <span m="6020">continue</span> <span m="6510">to</span>
  <span m="6680">offer</span> <span m="6980">high</span> <span m="7200">quality</span>
  <span m="7680">educational</span> <span m="8350">resources</span> <span m="8920">for</span>
  <span m="9040">free.</span> <span m="10100">To</span> <span m="10130">make</span>
  <span m="10330">a</span> <span m="10380">donation</span> <span m="11090">or</span>
  <span m="11310">to</span> <span m="11430">view</span> <span m="11640">additional</span>
  <span m="12050">materials</span> <span m="12670">from</span> <span m="12850">hundreds</span>
  <span m="13180">of</span> <span m="13280">MIT</span> <span m="13650">courses,</span>
  <span m="14960">visit</span> <span m="15150">MIT</span> <span m="15670">OpenCourseWare</span>
  <span m="16580">at</span> <span m="16920">ocw.mit.edu.</span></p><p><span m="26090">QIQI
  WANG: OK.</span> <span m="26400">So</span> <span m="27150">today</span> <span m="27570">is</span>
  <span m="27800">our</span> <span m="27950">lecture</span> <span m="28360">on</span>
  <span m="28806">finite</span> <span m="29698">volume</span> <span m="30144">method.</span>
  <span m="31040">So</span> <span m="31230">we</span> <span m="31380">talked</span>
  <span m="31640">about</span> <span m="31980">finite</span> <span m="32259">difference</span>
  <span m="32610">method.</span> <span m="33800">And</span> <span m="34380">we</span>
  <span m="34610">are</span> <span m="34780">going</span> <span m="35040">to</span>
  <span m="35120">be</span> <span m="35210">talking</span> <span m="35540">about</span>
  <span m="35850">finite</span> <span m="36135">volume</span> <span m="36420">method</span>
  <span m="37070">and</span> <span m="37210">finite element</span> <span m="37530">method.</span>
  <span m="38320">So</span> <span m="38670">I''m</span> <span m="38870">going</span>
  <span m="39090">to--</span> <span m="39730">there</span> <span m="39900">is</span>
  <span m="40080">a</span> <span m="40230">request</span> <span m="41120">for</span>
  <span m="41230">me</span> <span m="41330">to</span> <span m="41430">go</span> <span
  m="41690">over</span> <span m="42640">what</span> <span m="43400">did</span> <span
  m="43620">I</span> <span m="43860">do</span> <span m="44290">on</span> <span m="44540">the</span>
  <span m="44810">matrix</span> <span m="45300">form</span> <span m="45680">of</span>
  <span m="45820">the</span> <span m="45900">two</span> <span m="46140">dimensional</span>
  <span m="46710">finite</span> <span m="47030">difference.</span> <span m="47640">So</span>
  <span m="47810">I''ll</span> <span m="47900">go</span> <span m="48080">over</span>
  <span m="48290">that.</span> <span m="49060">But</span> <span m="49120">before</span>
  <span m="49440">I</span> <span m="49540">do</span> <span m="49760">that,</span>
  <span m="50620">let</span> <span m="50720">me</span> <span m="50960">show</span>
  <span m="51300">you</span> <span m="52650">what</span> <span m="52880">is</span>
  <span m="53040">the</span> <span m="53130">difference</span> <span m="53940">between</span>
  <span m="54270">finite</span> <span m="54630">volume</span> <span m="54870">method</span>
  <span m="55310">and</span> <span m="55430">finite</span> <span m="55700">difference</span>
  <span m="56030">method.</span></p><p><span m="57830">Because</span> <span m="58470">there</span>
  <span m="58630">are</span> <span m="58800">two</span> <span m="60240">concepts,</span>
  <span m="61120">they</span> <span m="61840">are</span> <span m="61890">two</span>
  <span m="62080">conceptually</span> <span m="62860">different</span> <span m="63380">methods</span>
  <span m="63900">of</span> <span m="64080">describing</span> <span m="64440">and</span>
  <span m="64800">discretizing</span> <span m="65390">partial</span> <span m="65821">differential</span>
  <span m="66252">equations.</span> <span m="69920">So</span> <span m="70100">I</span>
  <span m="70210">have</span> <span m="70480">a</span> <span m="70570">few</span>
  <span m="70820">demos.</span> <span m="71420">I</span> <span m="71670">have</span>
  <span m="71910">a</span> <span m="72210">finite</span> <span m="72460">volume</span>
  <span m="72570">demo.</span> <span m="73480">I</span> <span m="73580">have</span>
  <span m="73710">a</span> <span m="73860">finite</span> <span m="74070">difference</span>
  <span m="74310">demo.</span> <span m="77000">I</span> <span m="77160">have</span>
  <span m="77430">also</span> <span m="77490">a</span> <span m="77710">finite</span>
  <span m="78070">element</span> <span m="78380">demo.</span> <span m="78680">So</span>
  <span m="78930">they</span> <span m="79040">are</span> <span m="79410">really</span>
  <span m="80430">three</span> <span m="80740">different</span> <span m="81320">conceptually</span>
  <span m="81970">different</span> <span m="82402">methods</span> <span m="83700">of</span>
  <span m="83850">solving</span> <span m="84010">PDEs.</span></p><p><span m="85180">So</span>
  <span m="85880">first I</span> <span m="86250">have</span> <span m="86470">a</span>
  <span m="86550">finite</span> <span m="86870">difference</span> <span m="87230">demo.</span>
  <span m="88230">So</span> <span m="88740">let me</span> <span m="88950">explain</span>
  <span m="89410">what</span> <span m="89530">is</span> <span m="89660">happening</span>
  <span m="90080">here.</span> <span m="91920">We</span> <span m="92060">are</span>
  <span m="92180">representing</span> <span m="92740">a</span> <span m="92830">function</span>
  <span m="94900">of</span> <span m="95368">x,</span> <span m="96772">a</span> <span
  m="97240">function of space</span> <span m="98180">in solving</span> <span m="98770">partial</span>
  <span m="99070">differential</span> <span m="99410">equations.</span> <span m="100102">And</span>
  <span m="100450">this</span> <span m="100650">function</span> <span m="101070">is</span>
  <span m="101270">going to</span> <span m="101360">evolve</span> <span m="101710">as
  a function</span> <span m="101860">of time.</span> <span m="103720">But in</span>
  <span m="104185">order</span> <span m="104650">to</span> <span m="105120">[INAUDIBLE]</span>
  <span m="106190">that</span> <span m="106490">function</span> <span m="106890">of</span>
  <span m="107070">x,</span> <span m="108120">we</span> <span m="108250">need</span>
  <span m="108420">to</span> <span m="108520">discretize</span> <span m="108750">it.</span>
  <span m="109674">Because</span> <span m="110136">a function</span> <span m="110598">is</span>
  <span m="111060">an infinite</span> <span m="111522">dimension</span> <span m="111984">[INAUDIBLE].</span>
  <span m="116850">Like</span> <span m="117080">that.</span> <span m="119415">Huh?</span></p><p><span
  m="121290">AUDIENCE: [INAUDIBLE].</span></p><p><span m="123700">QIQI WANG: I</span>
  <span m="124196">think</span> <span m="126180">I--</span> <span m="130770">I</span>
  <span m="131230">think</span> <span m="131440">there</span> <span m="131660">is</span>
  <span m="131800">something</span> <span m="132170">I</span> <span m="132260">can</span>
  <span m="132580">get</span> <span m="132900">rid of.</span> <span m="134134">I just
  don''t</span> <span m="134621">know--</span> <span m="141439">Advanced</span> <span
  m="141926">Settings.</span> <span m="144848">Monitor.</span> <span m="150220">Yeah.</span>
  <span m="150696">I don''t</span> <span m="151172">know why.</span> <span m="154028">Oh.</span>
  <span m="154504">That</span> <span m="154980">went</span> <span m="155150">away?</span>
  <span m="156620">Oh</span> <span m="156840">OK.</span></p><p><span m="158240">[INTERPOSING
  VOICES]</span></p><p><span m="160200">AUDIENCE: Don''t close</span> <span m="160690">that
  dialogue</span> <span m="161180">box.</span></p><p><span m="161670">QIQI WANG: OK.</span>
  <span m="167363">Advanced</span> <span m="167846">Settings.</span> <span m="170261">Monitor.</span>
  <span m="171230">I</span> <span m="171260">think</span> <span m="171540">I</span>
  <span m="171580">didn''t</span> <span m="171900">do</span> <span m="172060">anything</span>
  <span m="172480">except</span> <span m="172890">for--</span></p><p><span m="173653">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="174146">QIQI WANG: Yeah, just</span> <span m="174639">like</span>
  <span m="175132">that.</span> <span m="175625">Yeah.</span></p><p><span m="176700">AUDIENCE:
  [INAUDIBLE].</span></p><p>&nbsp;</p><p><span m="179560">QIQI WANG: OK.</span> <span
  m="182690">Wow.</span></p><p><span m="183674">[LAUGHTER]</span></p><p><span m="187120">I</span>
  <span m="187290">have</span> <span m="187470">no</span> <span m="187630">idea.</span>
  <span m="190000">This</span> <span m="190380">is</span> <span m="190790">weird.</span>
  <span m="191400">Technology.</span> <span m="192744">OK.</span></p><p><span m="194090">So
  I</span> <span m="194280">have a</span> <span m="194660">function</span> <span m="194810">of
  x.</span> <span m="195350">I need</span> <span m="195580">to</span> <span m="195920">discretize</span>
  <span m="196260">it.</span> <span m="197880">Can</span> <span m="198070">somebody</span>
  <span m="198360">come</span> <span m="198640">and</span> <span m="198800">draw</span>
  <span m="199010">me</span> <span m="199260">a</span> <span m="199440">function?</span>
  <span m="200010">And</span> <span m="200740">visualize</span> <span m="201400">how</span>
  <span m="202243">this is</span> <span m="202686">kind</span> <span m="203130">of</span>
  <span m="203330">different,</span> <span m="203806">how finite</span> <span m="204282">difference</span>
  <span m="204920">discretizes</span> <span m="205120">a function.</span> <span m="206700">So</span>
  <span m="207230">can</span> <span m="207400">somebody</span> <span m="207700">come</span>
  <span m="207950">up</span> <span m="208180">and</span> <span m="208350">draw</span>
  <span m="208510">a function?</span> <span m="209320">And</span> <span m="209520">maybe</span>
  <span m="209800">you can</span> <span m="209990">describe</span> <span m="210360">to
  me before you</span> <span m="210640">draw  the</span> <span m="211010">function</span>
  <span m="211380">of</span> <span m="211750">how finite</span> <span m="212120">difference</span>
  <span m="212260">discretizes</span> <span m="213670">the</span> <span m="214140">function,</span>
  <span m="214430">how</span> <span m="214860">will you</span> <span m="215290">[INAUDIBLE]</span>
  <span m="215720">that</span> <span m="216150">function.</span></p><p><span m="222550">How
  would</span> <span m="222920">the--</span> <span m="223530">in</span> <span m="223710">a</span>
  <span m="223970">finite</span> <span m="224000">difference</span> <span m="224330">method,</span>
  <span m="224640">how do</span> <span m="225130">we</span> <span m="225620">represent,</span>
  <span m="226110">like,</span> <span m="226600">obviously a</span> <span m="227090">function?</span>
  <span m="228070">Let me</span> <span m="228560">see.</span> <span m="228930">These</span>
  <span m="229320">blue</span> <span m="229710">lines</span> <span m="230100">are
  where</span> <span m="230490">the</span> <span m="230750">grid</span> <span m="231237">is.</span>
  <span m="234160">[INAUDIBLE],</span> <span m="234450">Right.</span> <span m="236330">OK.</span>
  <span m="237270">So  who</span> <span m="237740">wants to draw it</span> <span m="238210">for</span>
  <span m="238680">me?</span> <span m="241040">We just</span> <span m="241300">did</span>
  <span m="241390">the</span> <span m="241490">project.</span> <span m="241970">It''s</span>
  <span m="242180">a</span> <span m="242230">time</span> <span m="242480">to</span>
  <span m="242580">relax</span> <span m="242990">a</span> <span m="243060">little</span>
  <span m="243320">bit.</span> <span m="243795">So</span> <span m="244270">[INAUDIBLE]</span>
  <span m="244745">the</span> <span m="245220">difference in</span> <span m="245695">[INAUDIBLE].</span></p><p><span
  m="248750">[INTERPOSING VOICES]</span></p><p><span m="268360">QIQI WANG: All</span>
  <span m="268670">right.</span> <span m="269830">Good.</span> <span m="270310">So</span>
  <span m="270450">when</span> <span m="270610">we</span> <span m="270840">draw</span>
  <span m="271020">a</span> <span m="271190">function,</span> <span m="272140">it</span>
  <span m="272300">looks</span> <span m="272560">like this.</span> <span m="273532">Right?</span>
  <span m="274990">[? If this ?]</span> <span m="275350">curve</span> <span m="275760">is
  the</span> <span m="276217">function</span> <span m="276674">[INAUDIBLE]</span>
  <span m="277131">a little bit, right?</span> <span m="277800">On</span> <span m="278080">the--</span>
  <span m="278270">if not</span> <span m="278725">the</span> <span m="279180">[INAUDIBLE].</span>
  <span m="280090">In finite</span> <span m="280570">difference,</span> <span m="281040">we</span>
  <span m="281260">forget</span> <span m="281430">about</span> <span m="281670">that</span>
  <span m="282015">the</span> <span m="282360">function is.</span> <span m="283110">We</span>
  <span m="283330">only</span> <span m="283520">remember</span> <span m="284790">the</span>
  <span m="284870">value</span> <span m="285550">of</span> <span m="285710">the</span>
  <span m="285790">function</span> <span m="286570">at</span> <span m="287010">these</span>
  <span m="287380">distinct</span> <span m="287590">points.</span> <span m="289680">This</span>
  <span m="289970">is</span> <span m="291210">finite</span> <span m="291510">difference,</span>
  <span m="291850">though.</span></p><p><span m="293580">Do</span> <span m="294080">we</span>
  <span m="294350">all</span> <span m="294600">have</span> <span m="294770">a</span>
  <span m="294820">mental</span> <span m="295150">picture</span> <span m="295460">of</span>
  <span m="295600">what</span> <span m="295770">this</span> <span m="296130">does?</span>
  <span m="296890">What</span> <span m="296960">finite</span> <span m="297050">difference</span>
  <span m="297380">does?</span> <span m="298800">And</span> <span m="299030">then</span>
  <span m="299280">when</span> <span m="299430">you</span> <span m="299670">have</span>
  <span m="299780">approximated</span> <span m="300230">derivative,</span> <span m="300470">right?</span>
  <span m="302000">For example</span> <span m="302140">the</span> <span m="302340">derivative</span>
  <span m="302680">here,</span> <span m="303730">we</span> <span m="303890">can</span>
  <span m="304160">approximate</span> <span m="304720">it</span> <span m="305040">either</span>
  <span m="305370">as</span> <span m="305700">the</span> <span m="305840">slope</span>
  <span m="306610">of</span> <span m="307050">this</span> <span m="307330">line</span>
  <span m="308270">or</span> <span m="308620">as</span> <span m="308780">the</span>
  <span m="308890">slope</span> <span m="309300">of</span> <span m="309450">this</span>
  <span m="309670">line.</span> <span m="310530">Depending</span> <span m="310960">on
  if</span> <span m="311390">we do</span> <span m="311851">backwards</span> <span
  m="312312">[INAUDIBLE]</span> <span m="312773">or</span> <span m="313234">[INAUDIBLE].</span>
  <span m="315430">And</span> <span m="316290">in</span> <span m="316440">particular</span>
  <span m="316830">we</span> <span m="316970">may</span> <span m="317170">approximate</span>
  <span m="318450">the derivative</span> <span m="318980">here,</span> <span m="319340">[INAUDIBLE]</span>
  <span m="321730">taking</span> <span m="322130">this</span> <span m="322490">slope.</span>
  <span m="322740">If it''s</span> <span m="323165">backwards</span> <span m="323590">[INAUDIBLE]</span>
  <span m="324015">then</span> <span m="324440">we are</span> <span m="324840">taking
  this</span> <span m="325100">slope</span> <span m="325562">[INAUDIBLE].</span> <span
  m="327631">So there</span> <span m="328072">are some</span> <span m="328513">approximations</span>
  <span m="328954">[INAUDIBLE].</span> <span m="330720">This</span> <span m="330950">is
  what</span> <span m="331150">finite</span> <span m="331530">difference</span> <span
  m="331910">does.</span></p><p><span m="332670">OK.</span> <span m="333260">So</span>
  <span m="333730">can</span> <span m="333910">I</span> <span m="333980">invite</span>
  <span m="334330">somebody</span> <span m="334800">to</span> <span m="335940">do</span>
  <span m="336100">something</span> <span m="336660">that</span> <span m="336830">is</span>
  <span m="337050">completely</span> <span m="337530">unpredictable?</span> <span
  m="338390">Because</span> <span m="338680">we</span> <span m="338810">are</span>
  <span m="338890">going</span> <span m="339020">to</span> <span m="339080">be</span>
  <span m="339310">looking</span> <span m="339630">at</span> <span m="339690">the</span>
  <span m="339770">same</span> <span m="340860">thing.</span> <span m="341590">But</span>
  <span m="341830">we''re</span> <span m="342110">going</span> <span m="342250">to
  be</span> <span m="342580">using</span> <span m="342860">the</span> <span m="342950">same</span>
  <span m="343260">grid.</span> <span m="343950">I''m</span> <span m="344170">also</span>
  <span m="344350">going</span> <span m="344510">to</span> <span m="344866">ask</span>
  <span m="345222">somebody</span> <span m="345580">to draw</span> <span m="345870">me
  a function.</span> <span m="346165">But</span> <span m="346460">now</span> <span
  m="346680">we</span> <span m="346770">have</span> <span m="346920">a</span> <span
  m="346970">visual</span> <span m="347245">of</span> <span m="347520">how</span>
  <span m="347960">finite</span> <span m="348362">volume</span> <span m="348764">is</span>
  <span m="349570">going</span> <span m="350100">to</span> <span m="350900">discretize</span>
  <span m="351120">this</span> <span m="351760">function.</span> <span m="352550">OK.</span>
  <span m="352910">I''m</span> <span m="353020">going</span> <span m="353190">to</span>
  <span m="353350">type</span> <span m="354631">FvDemo.</span> <span m="358050">It''s</span>
  <span m="358270">the</span> <span m="358380">same</span> <span m="358660">plot</span>
  <span m="361070">before--</span> <span m="361690">yes,</span> <span m="362070">I''m
  going</span> <span m="362450">to ask you</span> <span m="362830">to draw</span>
  <span m="363160">the function</span> <span m="363653">of the same</span> <span m="364146">plot.</span>
  <span m="364920">But can somebody</span> <span m="365322">draw--</span></p><p><span
  m="366530">[INTERPOSING VOICES]</span></p><p>&nbsp;</p><p><span m="377210">QIQI
  WANG: And</span> <span m="377420">let''s</span> <span m="377610">see</span> <span
  m="377710">how a finite</span> <span m="378440">volume</span> <span m="378840">is</span>
  <span m="379305">going to</span> <span m="379770">discretize</span> <span m="380235">the
  function.</span> <span m="381630">Whoa.</span> <span m="384880">OK.</span></p><p><span
  m="388702">AUDIENCE: [INAUDIBLE].</span></p><p><span m="390530">QIQI WANG: OK.</span>
  <span m="390570">Well,</span> <span m="390790">we all</span> <span m="391095">see</span>
  <span m="391400">the function</span> <span m="391750">in</span> <span m="391820">the</span>
  <span m="391900">background,</span> <span m="392175">OK?</span> <span m="393080">See</span>
  <span m="393250">that?</span> <span m="394140">This</span> <span m="394390">is</span>
  <span m="394520">how</span> <span m="394940">finite</span> <span m="395060">volume</span>
  <span m="396740">[INAUDIBLE]</span> <span m="396930">this</span> <span m="397250">function</span>
  <span m="397510">if we</span> <span m="397932">do that.</span> <span m="399620">What
  do</span> <span m="399800">we</span> <span m="400100">do?</span> <span m="402280">What</span>
  <span m="402580">does</span> <span m="402750">finite</span> <span m="402810">volume</span>
  <span m="403120">do?</span> <span m="406120">[INAUDIBLE]</span> <span m="407020">the
  function</span> <span m="407880">value</span> <span m="408080">anywhere?</span></p><p><span
  m="414500">Would somebody</span> <span m="414730">describe</span> <span m="415270">to</span>
  <span m="415330">me</span> <span m="415580">what</span> <span m="416370">we</span>
  <span m="416540">did?</span> <span m="417802">What finite</span> <span m="418288">volume
  did?</span> <span m="422662">And</span> <span m="423160">we''re</span> <span m="423190">taking</span>
  <span m="423530">like</span> <span m="423780">an</span> <span m="425515">average</span>
  <span m="425940">value</span> <span m="426530">in</span> <span m="427210">between</span>
  <span m="427550">the</span> <span m="427927">points,</span> <span m="429060">each</span>
  <span m="429540">two</span> <span m="429840">grid</span> <span m="430100">points.</span>
  <span m="433100">Right?</span> <span m="434050">In</span> <span m="434280">finite</span>
  <span m="434470">difference,</span> <span m="435000">we</span> <span m="435220">talked</span>
  <span m="435480">about</span> <span m="435830">grid points.</span> <span m="437040">Because</span>
  <span m="437450">we</span> <span m="437540">are</span> <span m="437760">exploring</span>
  <span m="438030">the</span> <span m="438600">value</span> <span m="439220">of the
  function</span> <span m="440192">at</span> <span m="440550">these</span> <span m="440900">grid</span>
  <span m="441170">points.</span> <span m="442170">In finite</span> <span m="442610">volume,</span>
  <span m="443310">we are</span> <span m="443740">talking about</span> <span m="444450">cells</span>
  <span m="445450">or</span> <span m="445630">controlled</span> <span m="445995">volumes,</span>
  <span m="446843">right?</span> <span m="447809">Each</span> <span m="448775">space</span>
  <span m="449258">is</span> <span m="449741">in two</span> <span m="450230">points,</span>
  <span m="450990">or</span> <span m="451110">controlled</span> <span m="451490">volume.</span>
  <span m="453640">We</span> <span m="454500">are</span> <span m="454730">discretizing</span>
  <span m="456125">the function</span> <span m="456920">by</span> <span m="457130">storing
  the</span> <span m="457390">average</span> <span m="458050">value</span> <span m="458550">of</span>
  <span m="458710">the</span> <span m="458780">function</span> <span m="460000">inside</span>
  <span m="460760">each</span> <span m="461430">controlled</span> <span m="461765">volume,</span>
  <span m="462100">or</span> <span m="462280">inside</span> <span m="462420">each</span>
  <span m="462885">cell.</span> <span m="465210">OK?</span></p><p><span m="466140">So</span>
  <span m="466450">in</span> <span m="466936">particular,</span> <span m="467422">if
  we</span> <span m="467910">look</span> <span m="468150">at</span> <span m="468380">this
  one,</span> <span m="469320">we will</span> <span m="469550">have</span> <span m="470046">the</span>
  <span m="470542">[INAUDIBLE].</span> <span m="472030">But</span> <span m="472190">[INAUDIBLE]</span>
  <span m="472940">for</span> <span m="473700">the</span> <span m="473840">average</span>
  <span m="474540">difference.</span> <span m="477450">OK.</span> <span m="477940">And</span>
  <span m="478200">as</span> <span m="478350">we</span> <span m="478500">see,</span>
  <span m="480580">when</span> <span m="480910">we</span> <span m="481270">use</span>
  <span m="481610">finite</span> <span m="482024">volume,</span> <span m="482438">we</span>
  <span m="482852">need</span> <span m="483266">to</span> <span m="483680">evolve</span>
  <span m="484340">these</span> <span m="484570">averages.</span> <span m="485960">And</span>
  <span m="487490">we</span> <span m="487680">know</span> <span m="487890">the</span>
  <span m="488210">function</span> <span m="488760">value.</span> <span m="489670">In</span>
  <span m="489890">finite</span> <span m="490090">difference,</span> <span m="490530">when
  we look at</span> <span m="490740">the function</span> <span m="491480">value,</span>
  <span m="491850">and</span> <span m="492010">the</span> <span m="492100">function</span>
  <span m="492420">value,</span> <span m="492850">of course,</span> <span m="493275">will
  satisfy</span> <span m="493880">the</span> <span m="493970">PDE.</span> <span m="495030">And</span>
  <span m="495270">the PDE</span> <span m="497060">in order</span> <span m="497250">to</span>
  <span m="497640">solve</span> <span m="497770">the</span> <span m="497860">PDE,</span>
  <span m="499230">we need</span> <span m="499410">to</span> <span m="499690">approximate</span>
  <span m="501130">the</span> <span m="501250">spatial</span> <span m="501740">derivative.</span></p><p><span
  m="502860">Here,</span> <span m="503250">we need</span> <span m="503690">to evolve</span>
  <span m="503945">this</span> <span m="504200">average.</span> <span m="507370">And</span>
  <span m="507770">we</span> <span m="507850">are</span> <span m="508100">going to</span>
  <span m="508180">look</span> <span m="508530">at</span> <span m="508880">what</span>
  <span m="509320">the</span> <span m="509450">differential</span> <span m="510270">equations</span>
  <span m="510530">on</span> <span m="510720">this average</span> <span m="511390">can</span>
  <span m="511630">[INAUDIBLE],</span> <span m="512419">how</span> <span m="512780">these</span>
  <span m="512980">averages</span> <span m="513329">cannot</span> <span m="513679">satisfy</span>
  <span m="514864">the</span> <span m="515316">PDE.</span> <span m="516672">It</span>
  <span m="517124">satisfies</span> <span m="517580">something</span> <span m="517950">else.</span>
  <span m="519558">And</span> <span m="519960">this</span> <span m="520200">is</span>
  <span m="520330">what</span> <span m="520510">finite</span> <span m="520953">volume
  does.</span> <span m="521840">It</span> <span m="522090">is</span> <span m="522289">going</span>
  <span m="522409">to</span> <span m="522570">derive</span> <span m="524290">from</span>
  <span m="524760">the</span> <span m="524870">PDE</span> <span m="525644">a</span>
  <span m="526420">different</span> <span m="526860">set of</span> <span m="527260">equations</span>
  <span m="528080">than</span> <span m="528430">describe</span> <span m="528530">the
  evolution</span> <span m="529030">of</span> <span m="529110">these</span> <span
  m="529260">averages.</span> <span m="531180">And</span> <span m="531750">so</span>
  <span m="532270">this</span> <span m="532300">equation</span> <span m="533416">set</span>
  <span m="533800">describes</span> <span m="534460">the</span> <span m="534610">evolution</span>
  <span m="535210">of</span> <span m="535300">the</span> <span m="535420">averages.</span></p><p><span
  m="537680">OK.</span> <span m="538590">So</span> <span m="538730">this</span> <span
  m="538910">is</span> <span m="539050">a</span> <span m="539730">conceptual</span>
  <span m="540180">difference</span> <span m="540570">between</span> <span m="540860">finite</span>
  <span m="541180">difference</span> <span m="541510">and</span> <span m="541840">finite</span>
  <span m="542160">volume.</span> <span m="543660">And</span> <span m="543900">when</span>
  <span m="544130">we</span> <span m="544250">start</span> <span m="545310">finite</span>
  <span m="546100">element,</span> <span m="548210">I''m</span> <span m="548390">also</span>
  <span m="548790">going</span> <span m="549060">to--</span> <span m="551640">well,</span>
  <span m="552430">let</span> <span m="552610">me</span> <span m="552710">not</span>
  <span m="552970">show you</span> <span m="553180">today.</span> <span m="553580">OK?</span>
  <span m="554170">If</span> <span m="554330">you''re</span> <span m="554480">interested</span>
  <span m="554930">in it,</span> <span m="555100">you</span> <span m="555250">can</span>
  <span m="555420">just</span> <span m="555790">go</span> <span m="556350">run</span>
  <span m="556650">it</span> <span m="556790">at</span> <span m="556930">home.</span>
  <span m="557250">I''m</span> <span m="557410">going</span> <span m="557540">to</span>
  <span m="557600">give</span> <span m="557810">you</span> <span m="558320">the three</span>
  <span m="558650">scripts.</span> <span m="560170">If</span> <span m="560260">interested,</span>
  <span m="560530">you can</span> <span m="560780">run</span> <span m="561040">it
  at</span> <span m="561540">home</span> <span m="561640">and</span> <span m="561720">see</span>
  <span m="561930">what</span> <span m="562180">you get.</span> <span m="564010">[INAUDIBLE]</span>
  <span m="564250">who</span> <span m="564400">don''t</span> <span m="564470">have</span>
  <span m="564620">a</span> <span m="564680">tablet,</span> <span m="565040">you</span>
  <span m="565120">can</span> <span m="565360">go</span> <span m="565550">with</span>
  <span m="565690">your</span> <span m="565830">mouse</span> <span m="566726">on the</span>
  <span m="567172">function.</span></p><p><span m="568750">So</span> <span m="569260">I''m</span>
  <span m="569430">going</span> <span m="569610">to</span> <span m="570720">give</span>
  <span m="570850">you</span> <span m="570950">the</span> <span m="571060">scripts</span>
  <span m="571520">later</span> <span m="571830">on.</span> <span m="573380">But</span>
  <span m="573590">right</span> <span m="573840">now</span> <span m="574110">let</span>
  <span m="574310">me</span> <span m="574440">first</span> <span m="575050">focus</span>
  <span m="575510">on</span> <span m="577120">and</span> <span m="577230">go</span>
  <span m="577450">to</span> <span m="577990">our</span> <span m="578380">last</span>
  <span m="579110">lecture</span> <span m="579280">folder</span> <span m="581030">which</span>
  <span m="581220">is</span> <span m="581340">09.</span> <span m="582620">And</span>
  <span m="582840">I''m</span> <span m="582980">going</span> <span m="583130">to</span>
  <span m="583240">show you</span> <span m="583600">a</span> <span m="583720">little</span>
  <span m="583990">bit</span> <span m="584180">of</span> <span m="584430">what</span>
  <span m="584880">exactly</span> <span m="585630">we</span> <span m="585880">did.</span>
  <span m="587930">The</span> <span m="588030">two</span> <span m="588270">dimensional</span>
  <span m="589260">advection</span> <span m="589790">question.</span></p><p><span
  m="592040">OK.</span> <span m="593080">So</span> <span m="593280">this</span> <span
  m="593430">is</span> <span m="593530">the</span> <span m="593640">two</span> <span
  m="593800">dimensional</span> <span m="594280">advection</span> <span m="594730">equation.</span>
  <span m="595900">I</span> <span m="596020">think</span> <span m="596430">Professor</span>
  <span m="596840">Willcox</span> <span m="597860">ran</span> <span m="598340">that</span>
  <span m="599350">last</span> <span m="601100">class,</span> <span m="601670">right?</span>
  <span m="602710">We</span> <span m="602900">have</span> <span m="604540">this</span>
  <span m="604910">wavelike</span> <span m="605130">thing</span> <span m="605600">going</span>
  <span m="605880">on</span> <span m="606030">there.</span> <span m="606910">Of course,
  this</span> <span m="607090">is</span> <span m="607280">not</span> <span m="607490">as</span>
  <span m="607836">advanced</span> <span m="608182">as</span> <span m="608530">your</span>
  <span m="608990">project.</span> <span m="609877">Because</span> <span m="610364">we
  are</span> <span m="610851">looking</span> <span m="611338">at the constant</span>
  <span m="611825">cx</span> <span m="612312">and</span> <span m="614130">cy.</span>
  <span m="615280">We''re not</span> <span m="615540">looking</span> <span m="615720">at</span>
  <span m="615960">a</span> <span m="616080">cx</span> <span m="616340">and</span>
  <span m="616600">cy</span> <span m="617120">responding</span> <span m="617610">to
  the</span> <span m="618060">[INAUDIBLE].</span> <span m="619240">So this is</span>
  <span m="619540">actually</span> <span m="619970">a simpler</span> <span m="620450">script</span>
  <span m="621160">than</span> <span m="621900">what</span> <span m="622180">you</span>
  <span m="622660">guys</span> <span m="622960">wrote</span> <span m="627310">in</span>
  <span m="627790">the</span> <span m="627910">project.</span></p><p><span m="628956">But</span>
  <span m="629300">one</span> <span m="629540">thing I''m doing</span> <span m="630040">differently</span>
  <span m="630600">from</span> <span m="630860">the</span> <span m="630970">project</span>
  <span m="631300">is</span> <span m="631630">that</span> <span m="631950">I''m</span>
  <span m="632320">using</span> <span m="635010">implicit</span> <span m="635560">methods</span>
  <span m="635900">in</span> <span m="636160">solving</span> <span m="636570">this</span>
  <span m="637070">equation.</span> <span m="640570">[INAUDIBLE].</span> <span m="645800">So</span>
  <span m="646080">in</span> <span m="647100">using</span> <span m="647450">the</span>
  <span m="647540">implicit</span> <span m="648526">time-integration</span> <span
  m="648872">method,</span> <span m="649850">I</span> <span m="650080">have</span>
  <span m="650380">to</span> <span m="650520">use</span> <span m="650880">the</span>
  <span m="650970">matrix</span> <span m="651470">form</span> <span m="652520">of</span>
  <span m="652730">the</span> <span m="652830">finite</span> <span m="653100">difference.</span>
  <span m="655974">Right?</span> <span m="657890">Does</span> <span m="658130">everybody</span>
  <span m="658500">understand</span> <span m="658900">why</span> <span m="659800">by</span>
  <span m="659980">switching</span> <span m="660530">from</span> <span m="660850">explicit</span>
  <span m="661245">to</span> <span m="661640">implicit</span> <span m="662290">I</span>
  <span m="662440">need</span> <span m="662660">to</span> <span m="662930">use</span>
  <span m="663170">the</span> <span m="663250">matrix</span> <span m="663670">form</span>
  <span m="664160">of the finite</span> <span m="664650">difference?</span> <span
  m="667100">You</span> <span m="667230">don''t?</span></p><p><span m="670949">AUDIENCE:
  [INAUDIBLE].</span> <span m="675819">Does</span> <span m="676306">the matrix</span>
  <span m="676810">only</span> <span m="676990">have</span> <span m="677230">a</span>
  <span m="677670">times</span> <span m="677820">b</span> <span m="678310">plus</span>
  <span m="678800">something</span> <span m="679290">else</span> <span m="679780">times</span>
  <span m="680270">[INAUDIBLE]?</span></p><p><span m="681250">QIQI WANG: Exactly.</span>
  <span m="682450">The</span> <span m="682760">reason</span> <span m="683150">I</span>
  <span m="683540">have</span> <span m="683780">to</span> <span m="683900">use</span>
  <span m="684150">the</span> <span m="684190">matrix</span> <span m="684590">form</span>
  <span m="684960">is</span> <span m="685200">because</span> <span m="686020">in</span>
  <span m="686190">an</span> <span m="686390">implicit</span> <span m="686960">time-integration</span>
  <span m="687445">scheme,</span> <span m="689350">the</span> <span m="689490">spatial</span>
  <span m="689800">derivative</span> <span m="690700">is</span> <span m="691060">operated</span>
  <span m="692020">not</span> <span m="692510">only</span> <span m="693050">on</span>
  <span m="693350">time step</span> <span m="693690">n</span> <span m="694400">but</span>
  <span m="694710">also</span> <span m="695030">on</span> <span m="695260">time step</span>
  <span m="695590">n</span> <span m="695830">plus</span> <span m="696120">1,</span>
  <span m="697090">which</span> <span m="697320">is</span> <span m="697500">not</span>
  <span m="697990">known</span> <span m="698450">before</span> <span m="699050">I</span>
  <span m="699930">do</span> <span m="700190">the</span> <span m="700340">time step.</span>
  <span m="703150">I</span> <span m="703360">have</span> <span m="703550">a</span>
  <span m="703830">spatial</span> <span m="704290">differential</span> <span m="704870">operator</span>
  <span m="705860">operating</span> <span m="706680">on</span> <span m="706890">some</span>
  <span m="707130">unknown</span> <span m="708060">solution.</span> <span m="710260">So</span>
  <span m="710400">I</span> <span m="710480">cannot</span> <span m="711150">compute</span>
  <span m="711740">it</span> <span m="711910">explicitly.</span> <span m="713670">I</span>
  <span m="713880">have</span> <span m="714140">to</span> <span m="714250">move</span>
  <span m="714940">that</span> <span m="715360">curve</span> <span m="716240">to</span>
  <span m="716410">the</span> <span m="716530">left</span> <span m="716870">hand</span>
  <span m="717020">side</span> <span m="717220">of</span> <span m="717320">the</span>
  <span m="717410">question</span> <span m="717820">and</span> <span m="718160">solve</span>
  <span m="718480">it.</span></p><p><span m="721570">So</span> <span m="722950">let</span>
  <span m="723110">me</span> <span m="723250">make</span> <span m="723550">a</span>
  <span m="723620">new</span> <span m="723820">page</span> <span m="724200">and</span>
  <span m="725130">show</span> <span m="725380">you</span> <span m="725610">what</span>
  <span m="725900">this</span> <span m="726350">is.</span> <span m="728850">Page options.</span>
  <span m="730850">Insert.</span> <span m="736575">OK. It''s</span> <span m="737060">more
  like this.</span> <span m="738030">[INAUDIBLE].</span> <span m="739980">OK.</span>
  <span m="741940">So</span> <span m="742320">in</span> <span m="742510">an</span>
  <span m="742730">explicit</span> <span m="743440">scheme</span> <span m="744190">which</span>
  <span m="744410">would</span> <span m="744520">be</span> <span m="744800">partial
  u-partial t</span> <span m="747520">equals</span> <span m="748230">to,</span> <span
  m="749200">for</span> <span m="749330">example,</span> <span m="751520">a</span>
  <span m="751620">simplified</span> <span m="752180">version</span> <span m="752490">of</span>
  <span m="752620">what</span> <span m="752770">you</span> <span m="752850">guys</span>
  <span m="753120">did</span> <span m="755040">is</span> <span m="755320">this,</span>
  <span m="755950">right?</span> <span m="756340">This</span> <span m="756520">is</span>
  <span m="756680">like</span> <span m="756880">the</span> <span m="756960">simplified</span>
  <span m="757450">version</span> <span m="757790">of</span> <span m="758200">what</span>
  <span m="758350">you</span> <span m="758440">did.</span> <span m="759970">And</span>
  <span m="760600">if</span> <span m="760890">I</span> <span m="760990">do</span>
  <span m="761200">explicit</span> <span m="761600">time step,</span> <span m="762200">and</span>
  <span m="762840">if</span> <span m="763100">I</span> <span m="763210">use</span>
  <span m="763510">forward</span> <span m="763810">Euler,</span> <span m="764940">then</span>
  <span m="765660">I</span> <span m="765810">can</span> <span m="766120">do</span>
  <span m="766360">U</span> <span m="766640">of</span> <span m="766790">n</span> <span
  m="766940">plus</span> <span m="767220">one</span> <span m="767590">minus</span>
  <span m="767830">Un</span> <span m="768265">over</span> <span m="768700">delta</span>
  <span m="768880">t.</span> <span m="769090">That</span> <span m="769320">is</span>
  <span m="769520">an</span> <span m="769910">approximation</span> <span m="770040">of</span>
  <span m="770533">the</span> <span m="771026">time</span> <span m="771520">derivative.</span></p><p><span
  m="775470">OK.</span> <span m="776080">I</span> <span m="776250">can</span> <span
  m="776490">do</span> <span m="776620">matrix</span> <span m="777090">form.</span>
  <span m="777430">I</span> <span m="777520">can</span> <span m="777770">do</span>
  <span m="777970">non-matrix</span> <span m="778620">form.</span> <span m="778940">But</span>
  <span m="779160">whatever</span> <span m="779690">I</span> <span m="779810">do,</span>
  <span m="780200">I''m</span> <span m="780570">making--</span> <span m="783505">I''m</span>
  <span m="783980">either</span> <span m="784455">evaluating</span> <span m="784930">distance</span>
  <span m="786360">in</span> <span m="786640">matrix</span> <span m="786920">form</span>
  <span m="788070">or</span> <span m="788410">not in matrix</span> <span m="788890">form.</span>
  <span m="789370">But I''m</span> <span m="789850">actually</span> <span m="790290">computing</span>
  <span m="790741">the</span> <span m="791192">differential</span> <span m="791643">operator</span>
  <span m="792094">operated</span> <span m="792545">on</span> <span m="793000">Un,</span>
  <span m="793454">which is</span> <span m="793908">known.</span> <span m="794816">The</span>
  <span m="795270">fact</span> <span m="795725">that</span> <span m="796180">Un is</span>
  <span m="796650">known</span> <span m="797141">makes it</span> <span m="797632">possible
  for</span> <span m="798123">me to</span> <span m="798614">evaluate</span> <span
  m="799105">this</span> <span m="799596">without</span> <span m="800440">[INAUDIBLE]</span>
  <span m="801400">the</span> <span m="801880">matrix</span> <span m="802360">A.</span>
  <span m="803800">Right?</span> <span m="806200">This</span> <span m="806480">is</span>
  <span m="806750">explicit.</span></p><p><span m="809380">But</span> <span m="809640">what</span>
  <span m="815840">if</span> <span m="816070">I</span> <span m="816230">need</span>
  <span m="816500">to</span> <span m="816600">do</span> <span m="816840">this?</span>
  <span m="818280">What</span> <span m="818540">if</span> <span m="818750">I</span>
  <span m="819380">want</span> <span m="819710">to</span> <span m="820210">use</span>
  <span m="820955">an</span> <span m="821220">implicit</span> <span m="821970">method?</span>
  <span m="823250">For</span> <span m="823490">example,</span> <span m="824190">if</span>
  <span m="824320">I</span> <span m="824430">need</span> <span m="824620">to</span>
  <span m="824720">do</span> <span m="824950">backward</span> <span m="825220">Euler,</span>
  <span m="828010">then</span> <span m="828220">the</span> <span m="828290">difference</span>
  <span m="828790">is</span> <span m="828990">that</span> <span m="829840">these</span>
  <span m="831240">spatial</span> <span m="833520">finite</span> <span m="833710">difference</span>
  <span m="834447">operator</span> <span m="834834">is</span> <span m="835221">operated</span>
  <span m="835610">on</span> <span m="836110">not Un</span> <span m="836610">but</span>
  <span m="837110">Un</span> <span m="837610">plus one.</span> <span m="841220">Well,</span>
  <span m="843580">yes.</span> <span m="845250">Where</span> <span m="845730">a</span>
  <span m="846370">is</span> <span m="847550">finite</span> <span m="849750">difference,</span>
  <span m="852760">approximation</span> <span m="853720">of</span> <span m="853910">minus</span>
  <span m="854450">partial u-partial x</span> <span m="855580">minus</span> <span
  m="856070">partial u-partial y.</span> <span m="859120">Right?</span></p><p><span
  m="860554">OK.</span> <span m="861040">So</span> <span m="861200">in</span> <span
  m="861460">this</span> <span m="861770">case,</span> <span m="862410">I do</span>
  <span m="862770">not</span> <span m="863220">know</span> <span m="863480">what</span>
  <span m="863660">we have</span> <span m="864045">for</span> <span m="864430">[INAUDIBLE].</span>
  <span m="865200">Therefore,</span> <span m="866185">I cannot</span> <span m="867003">just</span>
  <span m="867466">evaluate--</span> <span m="868855">I</span> <span m="869318">can</span>
  <span m="869781">no</span> <span m="870250">longer</span> <span m="870840">do--</span>
  <span m="872120">most</span> <span m="872500">of</span> <span m="872670">you</span>
  <span m="873000">did,</span> <span m="873580">which</span> <span m="873940">is</span>
  <span m="874572">taking</span> <span m="875004">a bunch</span> <span m="875436">of</span>
  <span m="875870">indexing</span> <span m="876827">with</span> <span m="877284">this</span>
  <span m="877741">U</span> <span m="878200">and</span> <span m="878530">subtract</span>
  <span m="879520">from</span> <span m="880920">doing</span> <span m="881190">the</span>
  <span m="881280">indexing</span> <span m="881870">or</span> <span m="882000">doing</span>
  <span m="882510">the</span> <span m="883430">circular</span> <span m="883900">shifting</span>
  <span m="884480">of</span> <span m="884670">U</span> <span m="885043">and</span>
  <span m="885416">subtracting</span> <span m="885790">it</span> <span m="885880">from
  each</span> <span m="886220">other.</span> <span m="886980">I</span> <span m="887090">cannot</span>
  <span m="887460">do that.</span> <span m="887895">Because I don''t</span> <span
  m="888330">have the</span> <span m="888765">n plus one.</span></p><p><span m="889900">What</span>
  <span m="890150">I</span> <span m="890240">need</span> <span m="890470">to</span>
  <span m="890570">do</span> <span m="890770">instead</span> <span m="892070">is</span>
  <span m="892410">to</span> <span m="892700">move</span> <span m="893250">all</span>
  <span m="893620">the</span> <span m="893700">Un</span> <span m="894560">plus</span>
  <span m="894880">one</span> <span m="895230">terms,</span> <span m="896300">is</span>
  <span m="896550">I</span> <span m="896660">need</span> <span m="896930">to</span>
  <span m="897040">move</span> <span m="897960">all</span> <span m="898380">these</span>
  <span m="898830">blue</span> <span m="899210">terms</span> <span m="899800">to</span>
  <span m="900020">the</span> <span m="900140">left</span> <span m="900490">hand</span>
  <span m="900660">side</span> <span m="900930">of</span> <span m="901030">the</span>
  <span m="901140">equation</span> <span m="902250">and</span> <span m="902770">move</span>
  <span m="903290">the</span> <span m="903500">green</span> <span m="903940">terms</span>
  <span m="904320">to</span> <span m="904430">the</span> <span m="904570">right</span>
  <span m="904830">hand</span> <span m="904980">side</span> <span m="905180">of</span>
  <span m="905270">the</span> <span m="905360">equation.</span> <span m="906870">So</span>
  <span m="906960">this</span> <span m="907150">is</span> <span m="907260">what</span>
  <span m="907460">I</span> <span m="907550">need</span> <span m="907750">to</span>
  <span m="907850">do.</span> <span m="908190">I need</span> <span m="908550">to</span>
  <span m="908680">move</span> <span m="909060">these</span> <span m="909330">to</span>
  <span m="909460">this side.</span> <span m="910670">So</span> <span m="910750">what</span>
  <span m="910980">I</span> <span m="911150">end</span> <span m="911400">up</span>
  <span m="911680">getting</span> <span m="913370">is</span> <span m="914110">identity</span>
  <span m="914940">over</span> <span m="915210">delta</span> <span m="915530">t</span>
  <span m="916520">minus</span> <span m="917320">A</span> <span m="918526">of</span>
  <span m="918880">Un</span> <span m="919400">plus</span> <span m="919740">one</span>
  <span m="920470">is</span> <span m="920730">equal</span> <span m="921060">to</span>
  <span m="921770">Un</span> <span m="922430">over</span> <span m="922710">delta</span>
  <span m="922810">t.</span></p><p><span m="924440">So</span> <span m="924770">I</span>
  <span m="925574">[? initially ?]</span> <span m="925976">was</span> <span m="926380">so</span>
  <span m="926780">busy</span> <span m="927266">[INAUDIBLE]</span> <span m="927752">I</span>
  <span m="928238">did not</span> <span m="928724">[INAUDIBLE]</span> <span m="930182">must
  have</span> <span m="930668">[? deflated ?]</span> <span m="931154">A,</span> <span
  m="932620">constructed.</span> <span m="934720">Right?</span> <span m="935160">So
  that</span> <span m="935310">is</span> <span m="935450">why,</span> <span m="936060">when</span>
  <span m="936360">I</span> <span m="936450">am</span> <span m="936710">solving--</span>
  <span m="938500">when</span> <span m="938700">I''m</span> <span m="938870">using</span>
  <span m="939260">an</span> <span m="939470">implicit</span> <span m="940040">scheme,</span>
  <span m="941000">I</span> <span m="941160">need</span> <span m="941370">to</span>
  <span m="941470">have</span> <span m="941700">the</span> <span m="941750">matrix</span>
  <span m="942130">form</span> <span m="942460">of</span> <span m="943310">the</span>
  <span m="943420">finite</span> <span m="943813">difference</span> <span m="944600">operator.</span></p><p><span
  m="947920">OK</span> <span m="948190">so</span> <span m="948340">this</span> <span
  m="948530">is</span> <span m="949050">how</span> <span m="949500">I</span> <span
  m="949670">did</span> <span m="949980">it</span> <span m="950660">in</span> <span
  m="950830">the</span> <span m="951120">finite</span> <span m="951220">difference</span>
  <span m="951570">matrix.</span> <span m="953564">I</span> <span m="954052">am</span>
  <span m="954540">taking--</span> <span m="958940">so</span> <span m="959755">I</span>
  <span m="960190">am</span> <span m="961060">constructing</span> <span m="962370">the</span>
  <span m="962690">same</span> <span m="962960">derivative</span> <span m="965040">matrix</span>
  <span m="966540">I</span> <span m="967040">constructed</span> <span m="967540">in
  the</span> <span m="968040">[INAUDIBLE]</span> <span m="968540">case.</span> <span
  m="970030">This is--</span> <span m="971020">if</span> <span m="971220">you</span>
  <span m="971480">let</span> <span m="971800">me--</span> <span m="973300">OK.</span>
  <span m="976800">Let</span> <span m="977050">me</span> <span m="977180">run</span>
  <span m="977510">this.</span> <span m="977950">I</span> <span m="978120">get</span>
  <span m="978330">a</span> <span m="978410">grid</span> <span m="979000">that</span>
  <span m="979190">looks</span> <span m="979390">like</span> <span m="979600">this.</span>
  <span m="980640">And</span> <span m="982120">then</span> <span m="983070">when</span>
  <span m="983260">I</span> <span m="983370">run</span> <span m="983640">this,</span>
  <span m="986800">getting--</span> <span m="990030">If</span> <span m="990580">I</span>
  <span m="990920">do</span> <span m="991150">a</span> <span m="991220">spy</span>
  <span m="991630">on</span> <span m="991780">Ax,</span> <span m="993690">I''m</span>
  <span m="993940">getting</span> <span m="994440">the</span> <span m="994530">same</span>
  <span m="994810">matrix</span> <span m="995290">as</span> <span m="995490">we</span>
  <span m="995660">get</span> <span m="996352">in a</span> <span m="996700">one-dimensional</span>
  <span m="997440">case.</span> <span m="998768">On the</span> <span m="999267">y</span>
  <span m="999766">diagonal,</span> <span m="1000764">I think</span> <span m="1001263">we</span>
  <span m="1001762">have</span> <span m="1002760">something</span> <span m="1003259">on
  the</span> <span m="1003758">diagonal</span> <span m="1004257">[INAUDIBLE].</span>
  <span m="1007550">Remember</span> <span m="1007890">this?</span> <span m="1009520">And</span>
  <span m="1013680">Ay</span> <span m="1014840">has</span> <span m="1015110">the</span>
  <span m="1015240">same</span> <span m="1015600">structure.</span> <span m="1016070">It</span>
  <span m="1016210">is</span> <span m="1017030">almost</span> <span m="1017700">identical,</span>
  <span m="1018460">except</span> <span m="1018780">for</span> <span m="1018940">the</span>
  <span m="1019418">dimension are a little bit</span> <span m="1019896">different</span>
  <span m="1020852">because the</span> <span m="1021330">y</span> <span m="1021560">direction</span>
  <span m="1022180">has</span> <span m="1022450">a</span> <span m="1022540">different</span>
  <span m="1023280">number</span> <span m="1023570">of</span> <span m="1023650">grid</span>
  <span m="1023880">points</span> <span m="1024329">as</span> <span m="1024589">the</span>
  <span m="1024680">x</span> <span m="1025140">direction.</span></p><p><span m="1026060">Then</span>
  <span m="1026550">I</span> <span m="1026670">did</span> <span m="1026890">something</span>
  <span m="1027310">interesting.</span> <span m="1029540">I did</span> <span m="1033076">a</span>
  <span m="1033550">run</span> <span m="1034436">of</span> <span m="1034879">Ax</span>
  <span m="1036208">with</span> <span m="1037099">Iy.</span> <span m="1039588">So</span>
  <span m="1040075">Iy</span> <span m="1041049">is just</span> <span m="1041536">an
  identity</span> <span m="1042023">matrix.</span> <span m="1043484">So</span> <span
  m="1043971">I did</span> <span m="1044458">a</span> <span m="1044945">[INAUDIBLE]</span>
  <span m="1045432">of</span> <span m="1045919">Ax</span> <span m="1046406">in</span>
  <span m="1046893">Iy.</span> <span m="1049350">To</span> <span m="1049600">show</span>
  <span m="1050020">what</span> <span m="1051020">[? connect a product ?]</span> <span
  m="1051990">does,</span> <span m="1053340">I</span> <span m="1053450">think</span>
  <span m="1053900">I</span> <span m="1054020">just</span> <span m="1054480">want</span>
  <span m="1054760">to</span> <span m="1055950">do</span> <span m="1056280">a</span>
  <span m="1056710">spy</span> <span m="1058878">of</span> <span m="1059300">the</span>
  <span m="1059500">product.</span> <span m="1062430">This</span> <span m="1062800">is</span>
  <span m="1062960">what</span> <span m="1063440">gets me.</span> <span m="1064280">OK.</span>
  <span m="1065210">You</span> <span m="1065330">see,</span> <span m="1066360">what</span>
  <span m="1066590">I''m</span> <span m="1066780">getting--</span> <span m="1068320">let</span>
  <span m="1068490">me</span> <span m="1068590">zoom</span> <span m="1068810">in.</span>
  <span m="1071183">Let me</span> <span m="1071646">zoom in</span> <span m="1072109">using</span>
  <span m="1072572">my pen.</span> <span m="1073498">I think it''s a</span> <span
  m="1073961">little better.</span> <span m="1075350">So</span> <span m="1075480">what</span>
  <span m="1076180">I''m</span> <span m="1076350">getting</span> <span m="1076940">is</span>
  <span m="1077380">a</span> <span m="1077740">bi-diagonal</span> <span m="1078400">matrix.</span>
  <span m="1080064">But</span> <span m="1080552">the</span> <span m="1081040">[INAUDIBLE]</span>
  <span m="1082601">I''m</span> <span m="1083020">replacing</span> <span m="1083650">each</span>
  <span m="1084100">element</span> <span m="1086420">in</span> <span m="1086890">Ax</span>
  <span m="1087490">with</span> <span m="1088080">that</span> <span m="1088430">identity</span>
  <span m="1088930">matrix.</span> <span m="1093430">So now</span> <span m="1093899">this</span>
  <span m="1094368">[INAUDIBLE]</span> <span m="1095306">this</span> <span m="1095775">is</span>
  <span m="1096244">a</span> <span m="1096713">series</span> <span m="1097182">of</span>
  <span m="1097651">dots.</span> <span m="1098470">Each dot</span> <span m="1098825">is</span>
  <span m="1099180">one entry</span> <span m="1099430">of a</span> <span m="1099905">matrix.</span>
  <span m="1102890">There</span> <span m="1103200">is</span> <span m="1103470">a</span>
  <span m="1103740">bunch</span> <span m="1104070">of</span> <span m="1104260">elements</span>
  <span m="1104722">over</span> <span m="1105184">here.</span> <span m="1105646">And</span>
  <span m="1106110">there is a bunch</span> <span m="1106230">of elements</span> <span
  m="1106710">over</span> <span m="1107190">here.</span></p><p><span m="1108630">So</span>
  <span m="1108790">when</span> <span m="1109040">I''m</span> <span m="1109160">eventually</span>
  <span m="1109710">doing is,</span> <span m="1111380">OK.</span> <span m="1111925">If
  I</span> <span m="1112230">modify</span> <span m="1112730">something</span> <span
  m="1113060">with this</span> <span m="1113325">matrix,</span> <span m="1114230">I''m</span>
  <span m="1114470">subtracting--</span> <span m="1115140">so</span> <span m="1116900">let</span>
  <span m="1117100">me</span> <span m="1117210">look</span> <span m="1117390">at</span>
  <span m="1117490">this one--</span> <span m="1118806">I''m</span> <span m="1119230">subtracting</span>
  <span m="1119600">the</span> <span m="1119670">value</span> <span m="1120360">corresponding</span>
  <span m="1120600">to</span> <span m="1121380">this</span> <span m="1121740">column</span>
  <span m="1124470">from</span> <span m="1125230">the</span> <span m="1125420">elements</span>
  <span m="1125970">corresponding</span> <span m="1126570">to</span> <span m="1126650">this</span>
  <span m="1126890">column.</span> <span m="1128960">So I''m</span> <span m="1129220">subtracting</span>
  <span m="1130540">two</span> <span m="1130810">values</span> <span m="1133050">that</span>
  <span m="1133410">are</span> <span m="1133900">spaced</span> <span m="1134761">apart</span>
  <span m="1137710">with</span> <span m="1137980">the</span> <span m="1138080">spacing</span>
  <span m="1138440">exactly</span> <span m="1138500">equal</span> <span m="1138875">to</span>
  <span m="1139250">the</span> <span m="1139550">number</span> <span m="1144330">of</span>
  <span m="1146920">x</span> <span m="1147250">elements.</span> <span m="1148710">Right?</span></p><p><span
  m="1151920">So</span> <span m="1152415">in</span> <span m="1152910">terms</span>
  <span m="1153130">of</span> <span m="1153400">spacing,</span> <span m="1154470">if</span>
  <span m="1154710">I</span> <span m="1154890">have--</span> <span m="1155350">let
  me</span> <span m="1155755">insert</span> <span m="1156160">another</span> <span
  m="1156490">one.</span> <span m="1166025">If</span> <span m="1166480">I''m</span>
  <span m="1166790">organizing</span> <span m="1172072">U2 1,</span> <span m="1173028">U2
  2,</span> <span m="1173984">et</span> <span m="1174462">cetera,</span> <span m="1175418">U</span>
  <span m="1175896">2nx,</span> <span m="1177262">et</span> <span m="1177610">cetera,</span>
  <span m="1178600">to</span> <span m="1179060">Uny1,</span> <span m="1181700">et</span>
  <span m="1182070">cetera,</span> <span m="1182730">Uny2.</span> <span m="1184730">So</span>
  <span m="1184910">if</span> <span m="1185100">I''m</span> <span m="1185210">organizing</span>
  <span m="1185595">my</span> <span m="1185980">array</span> <span m="1186792">like</span>
  <span m="1187200">this</span> <span m="1188300">and</span> <span m="1188630">I''m</span>
  <span m="1188820">going</span> <span m="1189360">through--</span> <span m="1193522">[INAUDIBLE].</span></p><p><span
  m="1209770">OK.</span> <span m="1210620">And</span> <span m="1210910">if</span>
  <span m="1211170">I''m</span> <span m="1212100">organizing</span> <span m="1212920">my</span>
  <span m="1213120">array</span> <span m="1213620">like</span> <span m="1213860">this,</span>
  <span m="1215230">I''m</span> <span m="1215370">organizing</span> <span m="1215675">my</span>
  <span m="1215980">array</span> <span m="1216370">as</span> <span m="1217540">this</span>
  <span m="1217940">one</span> <span m="1218320">goes</span> <span m="1218510">to</span>
  <span m="1218680">this</span> <span m="1218950">one</span> <span m="1219260">goes</span>
  <span m="1219480">to</span> <span m="1219590">this</span> <span m="1219840">one</span>
  <span m="1220040">goes</span> <span m="1220170">to</span> <span m="1220340">this</span>
  <span m="1220540">one.</span> <span m="1220710">So</span> <span m="1221120">I''m</span>
  <span m="1221470">storing</span> <span m="1221700">this first</span> <span m="1221940">in</span>
  <span m="1222020">memory</span> <span m="1222840">and</span> <span m="1223090">then</span>
  <span m="1223500">this</span> <span m="1223790">one</span> <span m="1224050">and</span>
  <span m="1224220">then</span> <span m="1224420">this</span> <span m="1224610">one.</span>
  <span m="1225280">And</span> <span m="1225960">then</span> <span m="1226730">you</span>
  <span m="1226950">want</span> <span m="1227220">to</span> <span m="1227400">two
  in</span> <span m="1227520">memory</span> <span m="1228170">and</span> <span m="1228490">following</span>
  <span m="1228970">this.</span> <span m="1229930">So</span> <span m="1230200">I</span>
  <span m="1230360">am</span> <span m="1230660">storing</span> <span m="1232050">one</span>
  <span m="1232380">column</span> <span m="1232720">the</span> <span m="1233050">other</span>
  <span m="1233300">column</span> <span m="1233762">then</span> <span m="1234224">another</span>
  <span m="1234686">column,</span> <span m="1235148">et cetera.</span> <span m="1237000">Then</span>
  <span m="1238390">if</span> <span m="1238660">my</span> <span m="1239020">two elements</span>
  <span m="1239492">are</span> <span m="1239964">spaced</span> <span m="1240436">apart</span>
  <span m="1242330">with</span> <span m="1243193">ny</span> <span m="1243666">elements</span>
  <span m="1244139">in memory,</span> <span m="1245085">then it</span> <span m="1245558">is
  the</span> <span m="1246031">exact</span> <span m="1246504">same,</span> <span m="1246977">the</span>
  <span m="1247450">adjacent</span> <span m="1247923">elements</span> <span m="1248400">in
  the</span> <span m="1248690">x direction.</span> <span m="1253530">That</span> <span
  m="1253800">is</span> <span m="1254030">how</span> <span m="1254793">my</span> <span
  m="1255236">elements</span> <span m="1255679">are</span> <span m="1256122">stored</span>
  <span m="1256565">in</span> <span m="1257280">memory.</span></p><p><span m="1259030">So</span>
  <span m="1260860">which</span> <span m="1261170">means,</span> <span m="1261975">if
  I''m</span> <span m="1262430">taking</span> <span m="1262906">derivative</span>
  <span m="1263382">in the</span> <span m="1263858">x direction,</span> <span m="1265140">my</span>
  <span m="1265270">spacing</span> <span m="1265450">should</span> <span m="1265500">be</span>
  <span m="1266420">ny.</span> <span m="1267930">And</span> <span m="1268460">what</span>
  <span m="1268700">happens</span> <span m="1269080">if</span> <span m="1269300">I</span>
  <span m="1269570">take</span> <span m="1272060">the</span> <span m="1272260">derivative</span>
  <span m="1273190">in</span> <span m="1273430">the</span> <span m="1273520">y</span>
  <span m="1273780">direction?</span> <span m="1275700">What</span> <span m="1275970">if</span>
  <span m="1276285">I</span> <span m="1276600">do</span> <span m="1276800">kron</span>
  <span m="1277420">of</span> <span m="1277515">Ix</span> <span m="1277870">with</span>
  <span m="1278220">Ay?</span> <span m="1291150">Oh.</span> <span m="1291450">OK.</span>
  <span m="1292370">Yes,</span> <span m="1292680">I</span> <span m="1292830">mean</span>
  <span m="1292980">this.</span></p><p><span m="1295650">OK.</span> <span m="1296860">When</span>
  <span m="1297060">I</span> <span m="1297160">go</span> <span m="1297390">to</span>
  <span m="1297530">something</span> <span m="1297870">like</span> <span m="1298090">this,</span>
  <span m="1301170">so</span> <span m="1301240">if</span> <span m="1301420">you</span>
  <span m="1301520">look</span> <span m="1301760">at</span> <span m="1301880">each</span>
  <span m="1302650">block--</span> <span m="1303050">so I''m</span> <span m="1303330">getting</span>
  <span m="1303630">a</span> <span m="1303710">periodic</span> <span m="1304760">structure.</span>
  <span m="1306034">And</span> <span m="1306820">each</span> <span m="1307310">block</span>
  <span m="1311251">[INAUDIBLE]</span> <span m="1313880">is</span> <span m="1314718">exactly</span>
  <span m="1316350">the</span> <span m="1316520">same as the</span> <span m="1316905">one
  dimensional</span> <span m="1317290">derivative</span> <span m="1317570">matrix.</span>
  <span m="1319250">And</span> <span m="1319740">once</span> <span m="1320170">we
  zoom</span> <span m="1320600">in</span> <span m="1321890">over</span> <span m="1322160">here--</span>
  <span m="1322815">oh,</span> <span m="1323100">you can''t</span> <span m="1323340">see</span>
  <span m="1323765">anymore.</span> <span m="1324615">But</span> <span m="1325040">these</span>
  <span m="1325300">are</span> <span m="1325560">individual</span> <span m="1325740">dots.</span>
  <span m="1326930">So</span> <span m="1327650">when</span> <span m="1327860">we</span>
  <span m="1327980">take the</span> <span m="1328390">derivative</span> <span m="1329000">in</span>
  <span m="1329130">the</span> <span m="1329240">y</span> <span m="1329460">direction,</span>
  <span m="1330040">we</span> <span m="1330150">are</span> <span m="1330340">taking</span>
  <span m="1330815">[INAUDIBLE]</span> <span m="1332240">adjacent</span> <span m="1332650">values</span>
  <span m="1333550">in the</span> <span m="1333850">array,</span> <span m="1334860">which</span>
  <span m="1336370">is</span> <span m="1336590">the</span> <span m="1336940">adjacent</span>
  <span m="1337412">value</span> <span m="1338830">actually</span> <span m="1339130">in
  the y</span> <span m="1339575">direction.</span> <span m="1341355">So</span> <span
  m="1341800">adjacent</span> <span m="1342240">values in</span> <span m="1342690">the
  x</span> <span m="1343140">direction</span> <span m="1343590">are</span> <span m="1344040">actually</span>
  <span m="1344487">spaced</span> <span m="1344934">over</span> <span m="1345381">by</span>
  <span m="1345830">ny</span> <span m="1346050">in</span> <span m="1346270">the</span>
  <span m="1346741">memory.</span> <span m="1348154">So</span> <span m="1348625">these</span>
  <span m="1350040">values in</span> <span m="1350400">the y-direction</span> <span
  m="1351220">are</span> <span m="1351670">spaced</span> <span m="1352120">with only</span>
  <span m="1352600">one in</span> <span m="1353046">memory.</span> <span m="1353940">That</span>
  <span m="1354110">is</span> <span m="1354270">why</span> <span m="1354540">we</span>
  <span m="1355020">need</span> <span m="1355946">to</span> <span m="1356410">use</span>
  <span m="1356660">the</span> <span m="1356920">kron</span> <span m="1357370">in
  the matrix</span> <span m="1357820">form.</span></p><p><span m="1361420">OK.</span>
  <span m="1361790">Questions on</span> <span m="1362262">that?</span> <span m="1368880">OK.</span>
  <span m="1370070">Now</span> <span m="1370240">let''s</span> <span m="1371900">go</span>
  <span m="1372090">to</span> <span m="1372310">our</span> <span m="1372610">finite</span>
  <span m="1373710">volume</span> <span m="1374825">analysis.</span> <span m="1377300">OK.</span>
  <span m="1377390">In finding</span> <span m="1377570">the</span> <span m="1377710">volume,</span>
  <span m="1378240">we</span> <span m="1378450">are</span> <span m="1378830">ultimately</span>
  <span m="1379290">going</span> <span m="1379750">to</span> <span m="1380210">two
  dimensional</span> <span m="1380670">too.</span> <span m="1381590">Today,</span>
  <span m="1381730">we</span> <span m="1381910">are</span> <span m="1382110">just</span>
  <span m="1382280">going</span> <span m="1382410">to</span> <span m="1383210">focus</span>
  <span m="1383440">on</span> <span m="1383500">one dimension</span> <span m="1383840">finite</span>
  <span m="1384140">volume.</span> <span m="1385650">And</span> <span m="1386000">again,</span>
  <span m="1392090">in</span> <span m="1392320">finite</span> <span m="1392580">volume--</span>
  <span m="1395130">OK.</span> <span m="1395380">Let</span> <span m="1395500">me</span>
  <span m="1395610">go</span> <span m="1395810">back</span> <span m="1396150">to</span>
  <span m="1396360">our</span> <span m="1396710">last</span> <span m="1397178">[INAUDIBLE].</span>
  <span m="1399990">In finite</span> <span m="1400230">volume,</span> <span m="1400820">we</span>
  <span m="1401160">draw</span> <span m="1401440">a</span> <span m="1401520">function.</span>
  <span m="1402210">And</span> <span m="1402350">obviously</span> <span m="1402670">in</span>
  <span m="1402945">the</span> <span m="1403220">function</span> <span m="1403750">we</span>
  <span m="1404195">are</span> <span m="1404640">only</span> <span m="1405900">storing</span>
  <span m="1407090">the</span> <span m="1407340">averages</span> <span m="1407920">inside</span>
  <span m="1408414">each cell.</span></p><p><span m="1410390">All</span> <span m="1410670">right.</span>
  <span m="1410950">So</span> <span m="1413610">let''s</span> <span m="1414130">look</span>
  <span m="1414460">at</span> <span m="1414790">why</span> <span m="1415370">that</span>
  <span m="1415650">is,</span> <span m="1416390">what</span> <span m="1416640">kind</span>
  <span m="1416830">of</span> <span m="1416930">equations</span> <span m="1417986">can</span>
  <span m="1418382">finite</span> <span m="1418780">volume</span> <span m="1418910">solve?</span>
  <span m="1419575">And</span> <span m="1419920">why</span> <span m="1420380">does</span>
  <span m="1420740">it</span> <span m="1421100">solve</span> <span m="1421400">this</span>
  <span m="1421600">kind of</span> <span m="1421960">equations</span> <span m="1422300">well?</span>
  <span m="1423690">Finite</span> <span m="1423900">volume</span> <span m="1425010">only</span>
  <span m="1425460">works</span> <span m="1426490">if</span> <span m="1426700">you</span>
  <span m="1426860">have</span> <span m="1427140">a</span> <span m="1427350">conservation</span>
  <span m="1428040">law.</span> <span m="1429650">Finite</span> <span m="1429730">volume</span>
  <span m="1430060">is</span> <span m="1430250">not</span> <span m="1430710">for</span>
  <span m="1431340">all</span> <span m="1431580">differential</span> <span m="1431920">equations.</span>
  <span m="1433630">It</span> <span m="1433920">works</span> <span m="1434530">only</span>
  <span m="1434900">when</span> <span m="1435150">you</span> <span m="1435430">have</span>
  <span m="1436340">something</span> <span m="1436900">that</span> <span m="1437080">can</span>
  <span m="1437280">be</span> <span m="1437390">formulated</span> <span m="1438090">in</span>
  <span m="1438486">terms</span> <span m="1439280">of</span> <span m="1439400">conservation</span>
  <span m="1439810">laws.</span></p><p><span m="1440650">And</span> <span m="1440820">what</span>
  <span m="1441000">does</span> <span m="1441100">conservation</span> <span m="1441420">law</span>
  <span m="1441740">mean?</span> <span m="1442126">Conservation</span> <span m="1442512">laws</span>
  <span m="1442900">mean</span> <span m="1443635">the</span> <span m="1444590">equations</span>
  <span m="1444860">that are</span> <span m="1445230">in</span> <span m="1446120">this</span>
  <span m="1446410">form.</span> <span m="1452180">OK.</span> <span m="1452470">You</span>
  <span m="1452740">can have</span> <span m="1452950">a</span> <span m="1453030">[INAUDIBLE].</span>
  <span m="1453540">But</span> <span m="1453710">like</span> <span m="1454446">you
  can</span> <span m="1454942">have a</span> <span m="1455438">[INAUDIBLE]</span>
  <span m="1455934">here.</span> <span m="1456930">All</span> <span m="1457060">right.</span>
  <span m="1457740">So</span> <span m="1457890">this</span> <span m="1458100">is</span>
  <span m="1458370">conservation</span> <span m="1458680">laws.</span> <span m="1460890">It''s</span>
  <span m="1461140">some</span> <span m="1461525">kind of</span> <span m="1461910">a</span>
  <span m="1462390">conservative</span> <span m="1462820">quantity.</span> <span m="1464970">Can</span>
  <span m="1465150">be</span> <span m="1465600">mass,</span> <span m="1466087">momentum</span>
  <span m="1467550">energy,</span> <span m="1469020">some</span> <span m="1469210">molecules,</span>
  <span m="1470242">number</span> <span m="1470644">of</span> <span m="1471046">[INAUDIBLE],</span>
  <span m="1471860">number of</span> <span m="1472313">people.</span> <span m="1474580">Something</span>
  <span m="1475020">that</span> <span m="1475210">can be</span> <span m="1475700">described</span>
  <span m="1476190">as</span> <span m="1477660">conservative.</span></p><p><span m="1480600">This
  F</span> <span m="1482080">is</span> <span m="1482340">the</span> <span m="1482580">flux.</span>
  <span m="1484236">The</span> <span m="1484650">flux</span> <span m="1485030">is</span>
  <span m="1485900">the</span> <span m="1486160">number</span> <span m="1486850">of</span>
  <span m="1487990">quantities</span> <span m="1488290">u</span> <span m="1489376">that</span>
  <span m="1490130">goes</span> <span m="1490550">through</span> <span m="1490980">a</span>
  <span m="1491080">boundary</span> <span m="1492140">per</span> <span m="1492320">unit</span>
  <span m="1492500">amount</span> <span m="1492570">of time.</span> <span m="1494301">OK.</span>
  <span m="1494770">That''s</span> <span m="1495020">what</span> <span m="1495380">flux
  means.</span> <span m="1497812">All right.</span> <span m="1499650">And</span> <span
  m="1499790">the</span> <span m="1500177">specific</span> <span m="1500564">force,</span>
  <span m="1501340">the</span> <span m="1501450">force</span> <span m="1501950">is</span>
  <span m="1502260">how</span> <span m="1502550">much</span> <span m="1503120">quantity,</span>
  <span m="1504600">again</span> <span m="1504930">described</span> <span m="1505190">in
  u,</span> <span m="1506242">is</span> <span m="1506640">generated,</span> <span
  m="1509075">comes</span> <span m="1509570">out</span> <span m="1510520">from</span>
  <span m="1510730">nowhere,</span> <span m="1512330">per</span> <span m="1512460">unit</span>
  <span m="1512910">amount of</span> <span m="1513360">time.</span></p><p><span m="1514260">This
  is</span> <span m="1514710">a</span> <span m="1514880">case,</span> <span m="1515240">for</span>
  <span m="1515420">example,</span> <span m="1515810">if</span> <span m="1516060">you
  have</span> <span m="1516510">some kind</span> <span m="1516960">of a--</span> <span
  m="1517410">if u</span> <span m="1517650">is describing</span> <span m="1518092">the</span>
  <span m="1518534">amount</span> <span m="1518976">of</span> <span m="1519420">molecules</span>
  <span m="1520455">and</span> <span m="1520820">F</span> <span m="1521560">is</span>
  <span m="1522507">the</span> <span m="1522974">number</span> <span m="1523441">of
  molecules</span> <span m="1523908">generated</span> <span m="1524375">in an amount</span>
  <span m="1524842">of time</span> <span m="1525776">if you</span> <span m="1526243">have
  a chemical</span> <span m="1526710">reaction</span> <span m="1527050">or things</span>
  <span m="1527506">like</span> <span m="1527962">that.</span> <span m="1529330">All
  right.</span> <span m="1532070">And if</span> <span m="1532270">u</span> <span m="1532490">is</span>
  <span m="1532896">describing</span> <span m="1534520">momentum,</span> <span m="1535552">then</span>
  <span m="1535944">F</span> <span m="1536730">is</span> <span m="1536990">the</span>
  <span m="1537395">flux</span> <span m="1537800">of momentum</span> <span m="1539650">through</span>
  <span m="1539940">the</span> <span m="1540060">boundary.</span> <span m="1541500">And</span>
  <span m="1541970">S</span> <span m="1542440">would</span> <span m="1542910">be something</span>
  <span m="1543380">like</span> <span m="1543850">the</span> <span m="1544070">[INAUDIBLE]</span>
  <span m="1544200">of</span> <span m="1544677">gravity.</span> <span m="1546108">Something</span>
  <span m="1546585">like that.</span> <span m="1548493">Right?</span> <span m="1548970">Is
  it clear</span> <span m="1549240">what</span> <span m="1549420">the conservation</span>
  <span m="1549865">law</span> <span m="1550310">means?</span></p><p><span m="1555160">The</span>
  <span m="1555320">conservation</span> <span m="1556100">law</span> <span m="1556420">really</span>
  <span m="1557230">makes</span> <span m="1557700">even</span> <span m="1558010">more</span>
  <span m="1558250">sense</span> <span m="1559000">if</span> <span m="1559300">you</span>
  <span m="1559690">try</span> <span m="1559940">to</span> <span m="1560200">integrate</span>
  <span m="1560800">it.</span> <span m="1561560">OK?</span> <span m="1562270">So</span>
  <span m="1562450">this</span> <span m="1562640">is</span> <span m="1562760">the</span>
  <span m="1562850">differential</span> <span m="1563590">form.</span> <span m="1569350">Now</span>
  <span m="1569690">if</span> <span m="1570030">you</span> <span m="1570180">try</span>
  <span m="1570410">to</span> <span m="1570510">integrate</span> <span m="1571220">the</span>
  <span m="1571280">conservation</span> <span m="1571910">law,</span> <span m="1572560">it</span>
  <span m="1572770">even</span> <span m="1573040">makes</span> <span m="1573280">more</span>
  <span m="1573490">sense.</span> <span m="1574170">And</span> <span m="1574380">by
  integrate,</span> <span m="1575220">I don''t</span> <span m="1576540">mean</span>
  <span m="1576910">integrating</span> <span m="1577290">time.</span> <span m="1577610">I</span>
  <span m="1577670">mean</span> <span m="1577930">integrating</span> <span m="1578300">space.</span>
  <span m="1580250">So</span> <span m="1580370">let''s</span> <span m="1580830">integrate</span>
  <span m="1581580">over</span> <span m="1582444">any</span> <span m="1582918">control</span>
  <span m="1583392">volume.</span> <span m="1584340">And</span> <span m="1584830">control</span>
  <span m="1585130">volume</span> <span m="1585280">is</span> <span m="1585460">described</span>
  <span m="1587140">as</span> <span m="1587310">an</span> <span m="1587650">interval</span>
  <span m="1587940">from</span> <span m="1588100">L</span> <span m="1588570">to</span>
  <span m="1588910">R.</span> <span m="1589890">L is the</span> <span m="1589990">left
  hand</span> <span m="1590240">of</span> <span m="1590410">the</span> <span m="1590580">interval.</span>
  <span m="1591100">R</span> <span m="1591390">is</span> <span m="1591590">the</span>
  <span m="1591700">right</span> <span m="1591890">hand</span> <span m="1592040">of</span>
  <span m="1592130">the</span> <span m="1592588">interval.</span> <span m="1593962">So
  the</span> <span m="1594420">integral</span> <span m="1595180">of</span> <span m="1595370">left
  hand</span> <span m="1595700">side</span> <span m="1596030">has</span> <span m="1596250">to</span>
  <span m="1596390">be</span> <span m="1596570">equal</span> <span m="1596920">to</span>
  <span m="1597040">the</span> <span m="1597180">integral</span> <span m="1597770">of
  the</span> <span m="1598080">right</span> <span m="1598320">hand</span> <span m="1598490">side</span>
  <span m="1600450">of</span> <span m="1600720">S,</span> <span m="1601960">both</span>
  <span m="1602385">are</span> <span m="1602810">dx.</span></p><p><span m="1604890">So</span>
  <span m="1605740">let''s</span> <span m="1606170">do</span> <span m="1606360">some</span>
  <span m="1606560">manipulation</span> <span m="1608610">to</span> <span m="1609130">this</span>
  <span m="1610262">integral</span> <span m="1610650">form.</span> <span m="1612250">So</span>
  <span m="1612410">first</span> <span m="1612630">of</span> <span m="1612770">all,</span>
  <span m="1613930">the</span> <span m="1614375">integrative</span> <span m="1615710">time</span>
  <span m="1615850">derivative</span> <span m="1616260">in</span> <span m="1616380">space.</span>
  <span m="1618665">Because</span> <span m="1619122">time</span> <span m="1619579">and</span>
  <span m="1620036">space</span> <span m="1620493">are</span> <span m="1620950">two</span>
  <span m="1621320">independent</span> <span m="1622260">variables,</span> <span m="1624590">the</span>
  <span m="1624830">integral</span> <span m="1625750">in</span> <span m="1625950">space</span>
  <span m="1627320">[INAUDIBLE]</span> <span m="1628240">with</span> <span m="1629020">the</span>
  <span m="1629140">derivative</span> <span m="1629400">in</span> <span m="1629680">time.</span>
  <span m="1632910">So</span> <span m="1633090">the</span> <span m="1633190">integral</span>
  <span m="1633590">in space</span> <span m="1634740">of a</span> <span m="1635150">time</span>
  <span m="1635490">derivative</span> <span m="1635840">is</span> <span m="1636420">equal</span>
  <span m="1637620">to</span> <span m="1637750">the</span> <span m="1637870">time</span>
  <span m="1638240">derivative</span> <span m="1639050">of</span> <span m="1639280">the</span>
  <span m="1639430">integral</span> <span m="1639620">in</span> <span m="1639950">space.</span>
  <span m="1643880">The</span> <span m="1643980">first</span> <span m="1644360">term</span>
  <span m="1645170">can</span> <span m="1646130">be</span> <span m="1646340">written</span>
  <span m="1646570">as</span> <span m="1647037">this.</span> <span m="1649840">And</span>
  <span m="1650070">this</span> <span m="1650290">is</span> <span m="1650490">the</span>
  <span m="1650990">time</span> <span m="1651090">derivative</span> <span m="1651660">of</span>
  <span m="1653130">[INAUDIBLE]</span> <span m="1653860">using that</span> <span m="1654120">control</span>
  <span m="1654470">volume.</span> <span m="1656100">If</span> <span m="1656483">U</span>
  <span m="1657250">is</span> <span m="1657510">density,</span> <span m="1658100">then</span>
  <span m="1658570">this is</span> <span m="1659040">the</span> <span m="1659130">amount</span>
  <span m="1659440">of</span> <span m="1659590">mass</span> <span m="1660260">inside</span>
  <span m="1660410">the</span> <span m="1660590">control</span> <span m="1661003">volume.</span>
  <span m="1661830">If</span> <span m="1662216">U</span> <span m="1662602">is</span>
  <span m="1662990">the</span> <span m="1663200">density</span> <span m="1663720">of</span>
  <span m="1663960">[INAUDIBLE]</span> <span m="1665388">like</span> <span m="1666816">molecules,</span>
  <span m="1667768">density</span> <span m="1668244">is the total</span> <span m="1668720">number</span>
  <span m="1669140">of</span> <span m="1669640">molecules</span> <span m="1669850">in</span>
  <span m="1670260">that</span> <span m="1670670">control</span> <span m="1670960">volume.</span></p><p><span
  m="1672630">OK.</span> <span m="1673390">The</span> <span m="1673500">second</span>
  <span m="1673860">term.</span> <span m="1675340">The</span> <span m="1675440">second</span>
  <span m="1675740">term</span> <span m="1676000">is</span> <span m="1676150">not</span>
  <span m="1676350">a</span> <span m="1676410">timed</span> <span m="1676850">derivative.</span>
  <span m="1677525">It is a</span> <span m="1677900">spatial</span> <span m="1678180">derivative.</span>
  <span m="1679980">Now what</span> <span m="1680290">is</span> <span m="1680450">the</span>
  <span m="1680570">spatial</span> <span m="1681300">integral</span> <span m="1681490">of</span>
  <span m="1682130">the spatial</span> <span m="1682500">derivative?</span> <span
  m="1686110">The</span> <span m="1686300">function</span> <span m="1686570">itself.</span>
  <span m="1687080">Exactly.</span> <span m="1687670">So</span> <span m="1687800">it
  is</span> <span m="1688050">F</span> <span m="1688280">of</span> <span m="1688940">U</span>
  <span m="1691200">at</span> <span m="1692380">R</span> <span m="1693100">minus</span>
  <span m="1693820">F</span> <span m="1694270">of</span> <span m="1694727">U</span>
  <span m="1695184">at</span> <span m="1696578">L.</span> <span m="1698012">All</span>
  <span m="1698490">right?</span> <span m="1700460">And</span> <span m="1700670">let''s</span>
  <span m="1701370">actually</span> <span m="1701890">move</span> <span m="1702200">this</span>
  <span m="1702410">to</span> <span m="1702540">the</span> <span m="1702640">right</span>
  <span m="1702830">hand</span> <span m="1703000">side.</span> <span m="1703480">Because</span>
  <span m="1703860">it</span> <span m="1703990">makes</span> <span m="1704250">more</span>
  <span m="1704450">sense.</span> <span m="1705720">Let''s</span> <span m="1706240">move</span>
  <span m="1706640">it to the</span> <span m="1706800">right</span> <span m="1707240">hand</span>
  <span m="1707340">side</span> <span m="1707620">and</span> <span m="1707900">put</span>
  <span m="1708120">a</span> <span m="1708160">minus</span> <span m="1708550">sign</span>
  <span m="1708810">here,</span> <span m="1709070">put a</span> <span m="1709260">plus</span>
  <span m="1709590">sign here.</span></p><p><span m="1710910">OK.</span> <span m="1711270">So</span>
  <span m="1711450">this</span> <span m="1711670">is</span> <span m="1712980">the</span>
  <span m="1713160">result</span> <span m="1713670">of</span> <span m="1713820">the</span>
  <span m="1713920">spatial</span> <span m="1714420">derivative</span> <span m="1714685">term.</span>
  <span m="1716630">And</span> <span m="1717060">the</span> <span m="1717280">[INAUDIBLE]</span>
  <span m="1717790">that''s</span> <span m="1718080">[INAUDIBLE].</span> <span m="1723310">OK.</span>
  <span m="1724250">So</span> <span m="1724420">this</span> <span m="1724680">is</span>
  <span m="1724890">what</span> <span m="1725260">the</span> <span m="1725350">integral</span>
  <span m="1726000">is</span> <span m="1726350">going</span> <span m="1726801">to
  give us.</span> <span m="1730410">Now</span> <span m="1730550">let''s</span> <span
  m="1730860">try</span> <span m="1731120">to interpret</span> <span m="1731430">that</span>
  <span m="1731875">integral.</span> <span m="1732765">The</span> <span m="1733210">time</span>
  <span m="1733520">derivative</span> <span m="1733760">of the</span> <span m="1734420">total</span>
  <span m="1734670">quantity</span> <span m="1735330">within</span> <span m="1735560">the</span>
  <span m="1735710">control</span> <span m="1735990">volume</span> <span m="1737620">is</span>
  <span m="1738090">equal</span> <span m="1738320">to</span> <span m="1738420">the</span>
  <span m="1738760">flux at</span> <span m="1739170">the</span> <span m="1739587">left</span>
  <span m="1740840">minus</span> <span m="1741330">the</span> <span m="1741430">flux</span>
  <span m="1741850">at the</span> <span m="1742100">right.</span> <span m="1744230">This</span>
  <span m="1744660">is</span> <span m="1744890">what</span> <span m="1745590">goes</span>
  <span m="1746060">into</span> <span m="1746390">the</span> <span m="1746460">control</span>
  <span m="1746840">volume.</span> <span m="1747622">This</span> <span m="1748024">is</span>
  <span m="1748426">what</span> <span m="1748830">goes</span> <span m="1749220">on</span>
  <span m="1749490">the control</span> <span m="1749790">volume.</span></p><p><span
  m="1755190">So</span> <span m="1755580">makes</span> <span m="1755990">sense?</span>
  <span m="1757280">The</span> <span m="1757490">rate of change</span> <span m="1758350">of</span>
  <span m="1758610">the</span> <span m="1758720">amount</span> <span m="1758910">of</span>
  <span m="1759130">stuff</span> <span m="1759466">inside</span> <span m="1759802">the
  control</span> <span m="1760140">volume</span> <span m="1760730">is</span> <span
  m="1760960">equal</span> <span m="1761290">to the</span> <span m="1761390">rate</span>
  <span m="1761760">of</span> <span m="1762040">change for the</span> <span m="1762320">stuff</span>
  <span m="1762570">going in</span> <span m="1763820">minus</span> <span m="1764230">the</span>
  <span m="1764370">rate</span> <span m="1764650">of</span> <span m="1764920">stuff</span>
  <span m="1765320">coming</span> <span m="1765610">out</span> <span m="1767610">plus</span>
  <span m="1768640">the</span> <span m="1768850">rate</span> <span m="1769160">of</span>
  <span m="1769340">stuff</span> <span m="1769835">generated</span> <span m="1770330">inside
  the</span> <span m="1770825">control</span> <span m="1771320">volume.</span> <span
  m="1775280">So this is</span> <span m="1775780">the</span> <span m="1775980">integral</span>
  <span m="1776730">form.</span> <span m="1782742">This</span> <span m="1783220">is</span>
  <span m="1783380">the</span> <span m="1783490">integral</span> <span m="1783820">form</span>
  <span m="1784610">of</span> <span m="1785110">the conservation</span> <span m="1785610">law.</span></p><p><span
  m="1788610">Now</span> <span m="1789500">why</span> <span m="1789840">is</span>
  <span m="1789970">it</span> <span m="1790110">important?</span> <span m="1791670">And</span>
  <span m="1791870">how</span> <span m="1792170">does</span> <span m="1792370">it</span>
  <span m="1792490">relate</span> <span m="1792930">to</span> <span m="1793300">finite</span>
  <span m="1793470">volume</span> <span m="1793680">method?</span> <span m="1799476">Because</span>
  <span m="1799970">this</span> <span m="1800250">is</span> <span m="1800850">the</span>
  <span m="1801110">equation</span> <span m="1801330">we</span> <span m="1801450">are</span>
  <span m="1801560">solving</span> <span m="1801780">in finite</span> <span m="1801850">volume
  method.</span> <span m="1803990">This</span> <span m="1804260">is</span> <span m="1804450">the</span>
  <span m="1804580">equation</span> <span m="1804900">we''re</span> <span m="1805130">solving</span>
  <span m="1805340">in</span> <span m="1805450">finite</span> <span m="1805880">difference</span>
  <span m="1806310">method.</span> <span m="1806740">Right?</span> <span m="1807130">We</span>
  <span m="1807280">stick</span> <span m="1807630">with this</span> <span m="1807915">kind</span>
  <span m="1808200">of equation.</span> <span m="1810254">Because</span> <span m="1810715">in
  finite</span> <span m="1811176">difference</span> <span m="1811637">method,</span>
  <span m="1812100">the</span> <span m="1812290">U,</span> <span m="1812910">we</span>
  <span m="1813230">are</span> <span m="1813570">storing</span> <span m="1814050">the</span>
  <span m="1814150">value</span> <span m="1814990">of</span> <span m="1815280">the</span>
  <span m="1815723">solution</span> <span m="1816166">U</span> <span m="1816610">at</span>
  <span m="1816770">individual</span> <span m="1817900">points.</span> <span m="1818890">Right?</span>
  <span m="1820050">And</span> <span m="1820390">that</span> <span m="1820580">is</span>
  <span m="1820710">why</span> <span m="1822560">we</span> <span m="1822820">need</span>
  <span m="1822890">to</span> <span m="1823313">approximate</span> <span m="1824160">the</span>
  <span m="1824480">distance,</span> <span m="1826390">approximate</span> <span m="1826860">the</span>
  <span m="1827332">spatial</span> <span m="1827804">derivatives</span> <span m="1828276">[?
  and it ?]</span> <span m="1828748">kind of</span> <span m="1829220">a finite</span>
  <span m="1829692">difference</span> <span m="1830164">method.</span> <span m="1831580">And</span>
  <span m="1831790">then</span> <span m="1832010">we</span> <span m="1832140">can</span>
  <span m="1832630">do</span> <span m="1833210">[INAUDIBLE]</span> <span m="1836818">for
  U</span> <span m="1837280">[INAUDIBLE].</span></p><p><span m="1839160">With finite</span>
  <span m="1839370">volume</span> <span m="1839540">method,</span> <span m="1840770">we</span>
  <span m="1840960">are</span> <span m="1841100">not</span> <span m="1842230">interested</span>
  <span m="1842870">in</span> <span m="1843020">the</span> <span m="1843110">solution</span>
  <span m="1843820">at</span> <span m="1844150">individual</span> <span m="1844410">grid</span>
  <span m="1844670">points.</span> <span m="1846720">Instead,</span> <span m="1847310">we
  are</span> <span m="1847580">storing</span> <span m="1848000">the</span> <span m="1848270">average</span>
  <span m="1849070">of</span> <span m="1849200">the</span> <span m="1849290">solutions.</span>
  <span m="1852090">And</span> <span m="1852220">the</span> <span m="1852380">average</span>
  <span m="1852710">of</span> <span m="1853080">the</span> <span m="1853180">solutions,</span>
  <span m="1855340">what</span> <span m="1855530">is</span> <span m="1855720">a</span>
  <span m="1855760">mathematical</span> <span m="1856560">description</span> <span
  m="1857110">of an</span> <span m="1857480">average</span> <span m="1858000">of</span>
  <span m="1858120">a solution</span> <span m="1859050">in a control</span> <span
  m="1859515">volume?</span> <span m="1862770">What</span> <span m="1863060">is</span>
  <span m="1863300">the</span> <span m="1863480">average</span> <span m="1864080">when</span>
  <span m="1864320">we</span> <span m="1864570">look</span> <span m="1864890">at</span>
  <span m="1865390">the</span> <span m="1865890">amount</span> <span m="1866390">of</span>
  <span m="1866890">stuff</span> <span m="1867390">[INAUDIBLE]?</span></p><p><span
  m="1871880">Yeah.</span> <span m="1873650">It''s</span> <span m="1873750">the</span>
  <span m="1874110">amount</span> <span m="1874265">of</span> <span m="1874420">stuff</span>
  <span m="1874576">in space.</span> <span m="1875974">If I</span> <span m="1876440">ask
  you</span> <span m="1876660">to</span> <span m="1876770">write</span> <span m="1877750">a</span>
  <span m="1878210">mathematical</span> <span m="1878380">formula</span> <span m="1879820">of</span>
  <span m="1880240">the</span> <span m="1880340">value</span> <span m="1880920">of</span>
  <span m="1881030">the</span> <span m="1881481">average</span> <span m="1881932">as</span>
  <span m="1882383">a</span> <span m="1882834">function</span> <span m="1883285">of--</span>
  <span m="1884187">in terms</span> <span m="1884640">of the</span> <span m="1884740">function</span>
  <span m="1885005">within</span> <span m="1885270">these</span> <span m="1886300">intervals,</span>
  <span m="1887040">what</span> <span m="1887330">is it?</span></p><p><span m="1891113">AUDIENCE:
  [INAUDIBLE].</span></p><p><span m="1894110">QIQI WANG: Exactly.</span> <span m="1894690">The</span>
  <span m="1895000">average</span> <span m="1895810">would</span> <span m="1896040">be</span>
  <span m="1896220">equal</span> <span m="1896380">to</span> <span m="1896710">the</span>
  <span m="1896890">integral</span> <span m="1897270">of</span> <span m="1897600">this</span>
  <span m="1897700">function</span> <span m="1899030">from</span> <span m="1899360">0.6</span>
  <span m="1899835">is</span> <span m="1900310">0.7</span> <span m="1901735">divided</span>
  <span m="1902210">by</span> <span m="1902685">the</span> <span m="1903160">width</span>
  <span m="1903635">of the</span> <span m="1904110">integral,</span> <span m="1904585">which
  is</span> <span m="1905060">0.1.</span> <span m="1907450">That</span> <span m="1907700">is</span>
  <span m="1907860">what</span> <span m="1908080">the</span> <span m="1908220">average</span>
  <span m="1908780">means.</span> <span m="1910280">And</span> <span m="1910630">now</span>
  <span m="1911060">we</span> <span m="1911380">have</span> <span m="1911640">derived</span>
  <span m="1912426">the</span> <span m="1912822">integral</span> <span m="1913220">form</span>
  <span m="1913440">of</span> <span m="1913620">the</span> <span m="1913690">differential</span>
  <span m="1914040">equation.</span> <span m="1915596">And</span> <span m="1916090">it</span>
  <span m="1916350">describes</span> <span m="1917234">the</span> <span m="1917676">evolution</span>
  <span m="1918118">of</span> <span m="1918560">the</span> <span m="1918920">integral.</span>
  <span m="1919190">Do</span> <span m="1919460">we</span> <span m="1919690">have the</span>
  <span m="1919880">evolution</span> <span m="1920410">of</span> <span m="1920520">the</span>
  <span m="1920640">average?</span></p><p><span m="1925870">Of</span> <span m="1926090">course.</span>
  <span m="1926420">We</span> <span m="1926750">just</span> <span m="1927120">divide</span>
  <span m="1927740">this</span> <span m="1928000">thing</span> <span m="1928280">by</span>
  <span m="1928820">R minus</span> <span m="1929095">L,</span> <span m="1930000">right?</span>
  <span m="1931130">We</span> <span m="1931270">just</span> <span m="1931560">divide</span>
  <span m="1932070">the</span> <span m="1932160">whole</span> <span m="1932410">thing</span>
  <span m="1932660">by</span> <span m="1933150">R</span> <span m="1933210">minus</span>
  <span m="1933570">L.</span> <span m="1933950">Then</span> <span m="1939850">this</span>
  <span m="1940750">whole term</span> <span m="1941280">actually--</span> <span m="1941960">let</span>
  <span m="1942130">me</span> <span m="1942250">include</span> <span m="1942600">the</span>
  <span m="1942950">time</span> <span m="1943430">derivative--</span> <span m="1944840">this</span>
  <span m="1945140">is</span> <span m="1945350">the</span> <span m="1945460">d dt</span>
  <span m="1947940">of</span> <span m="1948300">the</span> <span m="1948470">U</span>
  <span m="1949110">average.</span> <span m="1952000">Right?</span> <span m="1952850">This</span>
  <span m="1953280">whole term</span> <span m="1953490">would</span> <span m="1953910">be</span>
  <span m="1954050">the</span> <span m="1954230">time</span> <span m="1954600">derivative</span>
  <span m="1955910">of</span> <span m="1956180">the</span> <span m="1956370">average</span>
  <span m="1957430">value</span> <span m="1957900">of</span> <span m="1958070">the</span>
  <span m="1958140">function</span> <span m="1958606">between</span> <span m="1959072">L
  and R.</span> <span m="1962800">The time</span> <span m="1962940">derivative</span>
  <span m="1963345">of</span> <span m="1963750">the</span> <span m="1963990">average</span>
  <span m="1964420">value</span> <span m="1964720">between</span> <span m="1965500">L</span>
  <span m="1965770">and</span> <span m="1965860">R</span> <span m="1966210">is</span>
  <span m="1966535">just</span> <span m="1966860">equal</span> <span m="1967280">to</span>
  <span m="1968540">the</span> <span m="1968730">amount</span> <span m="1968970">of</span>
  <span m="1969090">stuff</span> <span m="1969390">going</span> <span m="1969870">in</span>
  <span m="1970450">minus</span> <span m="1970660">the amount of</span> <span m="1970780">stuff</span>
  <span m="1971010">going</span> <span m="1971270">out</span> <span m="1973290">divided</span>
  <span m="1974120">by</span> <span m="1974850">L</span> <span m="1975040">over</span>
  <span m="1975410">R.</span> <span m="1976060">Plus</span> <span m="1976480">the</span>
  <span m="1976680">average</span> <span m="1977340">amount</span> <span m="1977660">of</span>
  <span m="1978160">stuff</span> <span m="1978240">generated</span> <span m="1978620">in</span>
  <span m="1979010">the</span> <span m="1979400">control</span> <span m="1979840">volume.</span>
  <span m="1982702">Right?</span></p><p><span m="1984140">So</span> <span m="1985040">the</span>
  <span m="1985210">reason</span> <span m="1985680">we</span> <span m="1985920">derive</span>
  <span m="1986010">the integral</span> <span m="1986880">form</span> <span m="1987356">from
  the</span> <span m="1987832">differential</span> <span m="1988310">form</span> <span
  m="1988490">is</span> <span m="1988930">because</span> <span m="1990690">this</span>
  <span m="1991450">integral</span> <span m="1991800">form</span> <span m="1992390">is</span>
  <span m="1992520">what</span> <span m="1992830">is</span> <span m="1993090">satisfied</span>
  <span m="1993520">by</span> <span m="1994010">the</span> <span m="1994446">finite</span>
  <span m="1995320">volume</span> <span m="1995720">method,</span> <span m="1996546">by</span>
  <span m="1997002">the</span> <span m="1997458">volume</span> <span m="1997914">average.</span>
  <span m="2000650">So</span> <span m="2000750">we</span> <span m="2000930">use</span>
  <span m="2001780">this</span> <span m="2002020">form</span> <span m="2002710">for
  the finite</span> <span m="2003137">volume method.</span> <span m="2004420">Now</span>
  <span m="2004670">this</span> <span m="2004940">form</span> <span m="2005230">has</span>
  <span m="2005600">distinct</span> <span m="2006300">advantage</span> <span m="2006980">over</span>
  <span m="2007270">this</span> <span m="2007380">form.</span> <span m="2009010">Why?</span>
  <span m="2012380">Why is</span> <span m="2012520">sometimes</span> <span m="2014740">this</span>
  <span m="2014990">form</span> <span m="2015450">valid</span> <span m="2015896">while</span>
  <span m="2016790">this</span> <span m="2017010">form</span> <span m="2017395">is</span>
  <span m="2017780">invalid?</span> <span m="2018780">Can</span> <span m="2019280">you
  guys</span> <span m="2019780">think of a</span> <span m="2020280">case?</span></p><p><span
  m="2021780">AUDIENCE: [INAUDIBLE].</span></p><p><span m="2024350">QIQI WANG: Yeah.</span>
  <span m="2024823">Of course,</span> <span m="2025296">this</span> <span m="2025770">has</span>
  <span m="2026030">derivatives</span> <span m="2026290">[INAUDIBLE].</span> <span
  m="2027060">This</span> <span m="2027310">has</span> <span m="2027810">a</span>
  <span m="2028020">spatial</span> <span m="2028290">derivative.</span> <span m="2028560">This</span>
  <span m="2029020">does not</span> <span m="2029480">have a spatial</span> <span
  m="2029940">derivative.</span> <span m="2032188">Right?</span> <span m="2033160">So
  in</span> <span m="2033350">what</span> <span m="2033760">cases</span> <span m="2034259">can</span>
  <span m="2034758">you not</span> <span m="2035257">have a derivative?</span></p><p><span
  m="2036255">AUDIENCE: [INAUDIBLE].</span></p><p><span m="2038750">QIQI WANG: Yeah.</span>
  <span m="2038960">We can</span> <span m="2039300">have</span> <span m="2039570">singularities.</span>
  <span m="2039680">What</span> <span m="2039850">kind</span> <span m="2040140">of</span>
  <span m="2040370">singularities</span> <span m="2044026">have</span> <span m="2044480">we
  seen</span> <span m="2048395">that</span> <span m="2048890">have</span> <span m="2049385">no
  derivative?</span></p><p><span m="2051860">AUDIENCE: [INAUDIBLE].</span></p><p><span
  m="2053345">QIQI WANG: Huh.</span></p><p><span m="2054335">AUDIENCE: [INAUDIBLE].</span></p><p><span
  m="2055325">QIQI WANG: [INAUDIBLE].</span> <span m="2057310">Shocks.</span> <span
  m="2059090">Shocks.</span> <span m="2059720">Right?</span> <span m="2060090">We</span>
  <span m="2060250">saw--</span> <span m="2060780">when</span> <span m="2061050">you</span>
  <span m="2061280">say</span> <span m="2061673">shocks</span> <span m="2062460">in</span>
  <span m="2062580">solving</span> <span m="2062760">this</span> <span m="2062920">kind</span>
  <span m="2063090">of</span> <span m="2063179">differential</span> <span m="2063540">equation.</span>
  <span m="2065380">Once</span> <span m="2065440">we have</span> <span m="2065670">a</span>
  <span m="2065760">shock</span> <span m="2066100">wave,</span> <span m="2067100">you</span>
  <span m="2067239">have</span> <span m="2067400">a</span> <span m="2067510">discontinuity</span>
  <span m="2068540">over</span> <span m="2068810">x.</span> <span m="2070449">Do you</span>
  <span m="2070911">accept</span> <span m="2071373">you can</span> <span m="2071835">take</span>
  <span m="2072300">the</span> <span m="2072570">derivative</span> <span m="2072840">of</span>
  <span m="2073290">a</span> <span m="2073710">shock wave?</span> <span m="2074550">No.</span>
  <span m="2075816">Actually,</span> <span m="2076170">I''m</span> <span m="2076409">going</span>
  <span m="2076510">to</span> <span m="2076730">show</span> <span m="2077080">you.</span>
  <span m="2078270">If</span> <span m="2078530">it</span> <span m="2078790">applies</span>
  <span m="2079050">to you</span> <span m="2079239">to</span> <span m="2079600">define</span>
  <span m="2079810">a different</span> <span m="2079949">method</span> <span m="2080250">to</span>
  <span m="2080727">solve</span> <span m="2081204">a</span> <span m="2081681">differential</span>
  <span m="2082158">equation</span> <span m="2082639">with</span> <span m="2082909">a</span>
  <span m="2083000">shock</span> <span m="2083300">wave,</span> <span m="2084740">sometimes</span>
  <span m="2085220">you can</span> <span m="2085700">still</span> <span m="2086180">[INAUDIBLE].</span>
  <span m="2090500">And</span> <span m="2090739">you</span> <span m="2091010">only</span>
  <span m="2091550">get</span> <span m="2091980">correct</span> <span m="2092234">solution</span>
  <span m="2092489">when</span> <span m="2092920">you</span> <span m="2093199">use</span>
  <span m="2093370">finite</span> <span m="2093449">volume method,</span> <span m="2093770">because</span>
  <span m="2094250">finite</span> <span m="2094460">volume</span> <span m="2094945">method</span>
  <span m="2096400">doesn''t</span> <span m="2096889">care if</span> <span m="2097309">it
  has</span> <span m="2097729">shock</span> <span m="2098149">waves or</span> <span
  m="2098569">not.</span> <span m="2098990">It</span> <span m="2099230">solves</span>
  <span m="2099770">the</span> <span m="2099960">integral</span> <span m="2100300">form</span>
  <span m="2100660">of the</span> <span m="2101157">equation,</span> <span m="2101654">which</span>
  <span m="2102151">is</span> <span m="2102650">immune</span> <span m="2102970">to</span>
  <span m="2103270">shock</span> <span m="2103450">waves,</span> <span m="2105650">and</span>
  <span m="2105790">not</span> <span m="2106110">even</span> <span m="2106380">taking</span>
  <span m="2106730">spatial</span> <span m="2106970">derivative.</span> <span m="2108750">As</span>
  <span m="2109000">long</span> <span m="2109260">as</span> <span m="2109440">I</span>
  <span m="2109550">can</span> <span m="2109780">integrate,</span> <span m="2111310">I</span>
  <span m="2111420">can</span> <span m="2111620">solve</span> <span m="2111850">the</span>
  <span m="2111980">equation.</span> <span m="2113280">And</span> <span m="2113590">the</span>
  <span m="2113710">solutions</span> <span m="2114270">with</span> <span m="2114540">shock</span>
  <span m="2114790">waves</span> <span m="2114990">have</span> <span m="2115470">their
  integral.</span></p><p><span m="2117580">All</span> <span m="2117690">right.</span>
  <span m="2119310">So</span> <span m="2119970">before</span> <span m="2120230">we</span>
  <span m="2120370">go</span> <span m="2120620">into</span> <span m="2120870">finite</span>
  <span m="2121130">volume</span> <span m="2121390">method</span> <span m="2122060">and</span>
  <span m="2122240">look</span> <span m="2122560">at</span> <span m="2122940">its</span>
  <span m="2123160">solution,</span> <span m="2123550">let''s</span> <span m="2123840">review</span>
  <span m="2126960">how</span> <span m="2127660">the</span> <span m="2127890">solutions</span>
  <span m="2128640">behave.</span> <span m="2129880">And</span> <span m="2130960">I</span>
  <span m="2131060">think</span> <span m="2131400">we</span> <span m="2131510">can</span>
  <span m="2131920">do</span> <span m="2132120">that</span> <span m="2132360">review</span>
  <span m="2133890">best</span> <span m="2134390">if</span> <span m="2134700">we</span>
  <span m="2134820">just</span> <span m="2135110">ran</span> <span m="2135460">the</span>
  <span m="2135530">Burgers</span> <span m="2135880">equation</span> <span m="2136350">phase</span>
  <span m="2136600">again.</span> <span m="2138460">All</span> <span m="2138600">right.</span>
  <span m="2139620">So</span> <span m="2140742">Burgers''</span> <span m="2141200">equation.</span>
  <span m="2143710">I''m</span> <span m="2143920">going</span> <span m="2144070">to</span>
  <span m="2144150">draw</span> <span m="2144380">the</span> <span m="2144480">initial</span>
  <span m="2144800">condition</span> <span m="2145420">this</span> <span m="2145640">time.</span>
  <span m="2146530">I</span> <span m="2147770">haven''t</span> <span m="2147950">drawn</span>
  <span m="2148070">it.</span> <span m="2149290">So</span> <span m="2149480">I''m</span>
  <span m="2149670">just</span> <span m="2149870">going</span> <span m="2150020">to</span>
  <span m="2150110">draw</span> <span m="2150500">something</span> <span m="2150890">that
  goes</span> <span m="2151250">up</span> <span m="2151560">and</span> <span m="2151750">goes</span>
  <span m="2152070">down</span> <span m="2152420">and goes up</span> <span m="2152930">again.</span>
  <span m="2154050">OK.</span> <span m="2154490">And</span> <span m="2155636">let''s</span>
  <span m="2156040">look</span> <span m="2156370">at</span> <span m="2156490">how</span>
  <span m="2158770">the</span> <span m="2158990">solution</span> <span m="2159500">evolves.</span></p><p><span
  m="2161310">OK.</span> <span m="2161920">So</span> <span m="2162080">this</span>
  <span m="2162260">is</span> <span m="2162350">a</span> <span m="2162460">typical</span>
  <span m="2162870">conservation</span> <span m="2163280">law.</span> <span m="2163756">[INAUDIBLE]</span>
  <span m="2164820">is one</span> <span m="2165130">of</span> <span m="2165440">the</span>
  <span m="2165680">simplest</span> <span m="2165960">conservation</span> <span m="2166240">laws.</span>
  <span m="2167390">And</span> <span m="2167550">remember,</span> <span m="2168040">the</span>
  <span m="2168140">solution</span> <span m="2168740">moves</span> <span m="2170230">with</span>
  <span m="2170440">a</span> <span m="2170760">speed</span> <span m="2171120">proportional</span>
  <span m="2171540">to</span> <span m="2172660">the</span> <span m="2172840">value</span>
  <span m="2173320">itself.</span> <span m="2174600">So</span> <span m="2174830">if</span>
  <span m="2175010">I</span> <span m="2175130">have</span> <span m="2175270">a</span>
  <span m="2175360">high</span> <span m="2175610">value</span> <span m="2176455">and</span>
  <span m="2176720">a</span> <span m="2176980">positive</span> <span m="2177360">value,</span>
  <span m="2177650">I</span> <span m="2177800">move</span> <span m="2178020">toward</span>
  <span m="2178210">the right.</span> <span m="2178720">If</span> <span m="2179020">I</span>
  <span m="2179220">have</span> <span m="2179380">a</span> <span m="2179510">negative</span>
  <span m="2179680">value,</span> <span m="2179975">I</span> <span m="2180270">move</span>
  <span m="2180560">towards</span> <span m="2181042">the left.</span> <span m="2182488">Right?</span>
  <span m="2182970">This is</span> <span m="2183452">even more</span> <span m="2183940">dramatic</span>
  <span m="2184300">than the case</span> <span m="2184520">where</span> <span m="2185090">everybody''s</span>
  <span m="2185570">[INAUDIBLE].</span></p><p><span m="2190870">This</span> <span
  m="2191040">is</span> <span m="2191210">the</span> <span m="2191430">solution</span>
  <span m="2191750">we</span> <span m="2191950">are</span> <span m="2192080">[INAUDIBLE].</span>
  <span m="2194840">So</span> <span m="2197570">if</span> <span m="2197690">I</span>
  <span m="2197850">have</span> <span m="2198020">something</span> <span m="2198350">moving</span>
  <span m="2198890">towards</span> <span m="2199150">the</span> <span m="2199410">right</span>
  <span m="2199840">and</span> <span m="2200255">I have</span> <span m="2200670">something</span>
  <span m="2200840">moving</span> <span m="2201105">towards</span> <span m="2202510">the</span>
  <span m="2202690">left,</span> <span m="2203640">and</span> <span m="2204310">you</span>
  <span m="2204510">can</span> <span m="2204960">very</span> <span m="2205550">clearly</span>
  <span m="2206010">see</span> <span m="2206460">a</span> <span m="2206860">shock
  wave</span> <span m="2206970">forming</span> <span m="2207424">over here.</span>
  <span m="2211060">And</span> <span m="2211210">we</span> <span m="2211350">can</span>
  <span m="2212400">know</span> <span m="2213020">what</span> <span m="2213560">the</span>
  <span m="2213700">solution</span> <span m="2214350">is</span> <span m="2217300">really</span>
  <span m="2217500">intuitively</span> <span m="2217955">because</span> <span m="2219320">we</span>
  <span m="2219560">know</span> <span m="2220050">at</span> <span m="2220430">each</span>
  <span m="2221490">point,</span> <span m="2222410">the</span> <span m="2222560">solution</span>
  <span m="2223060">moves</span> <span m="2226030">proportional</span> <span m="2226860">to</span>
  <span m="2227080">the</span> <span m="2227170">value,</span> <span m="2228860">which</span>
  <span m="2229290">if</span> <span m="2229500">you</span> <span m="2229620">look</span>
  <span m="2230245">at</span> <span m="2230590">the</span> <span m="2231090">plot</span>
  <span m="2231470">with</span> <span m="2231750">[? accuracy ?]</span> <span m="2232760">in</span>
  <span m="2233210">space</span> <span m="2234170">while</span> <span m="2234860">at</span>
  <span m="2235150">the</span> <span m="2235300">same time,</span> <span m="2236870">then</span>
  <span m="2237130">the</span> <span m="2237550">characeristic lines--</span> <span
  m="2241100">which</span> <span m="2241280">are</span> <span m="2241480">straight</span>
  <span m="2241950">lines</span> <span m="2242280">in space</span> <span m="2242580">and</span>
  <span m="2242730">time--</span> <span m="2244070">the</span> <span m="2244200">flow--</span>
  <span m="2246263">or</span> <span m="2246724">I should</span> <span m="2247185">say</span>
  <span m="2247650">the</span> <span m="2247740">inverse</span> <span m="2248210">flow</span>
  <span m="2248620">because</span> <span m="2249140">their</span> <span m="2249270">speed</span>
  <span m="2250220">is</span> <span m="2250470">delta</span> <span m="2250780">x</span>
  <span m="2250990">over</span> <span m="2251380">delta</span> <span m="2251960">y.</span>
  <span m="2254130">So</span> <span m="2254600">the delta</span> <span m="2254925">in</span>
  <span m="2255250">the</span> <span m="2255500">x</span> <span m="2255790">axis</span>
  <span m="2256030">over</span> <span m="2256440">the</span> <span m="2256695">delta</span>
  <span m="2256950">in the</span> <span m="2257420">y</span> <span m="2257890">axis.</span></p><p><span
  m="2258830">AUDIENCE: [INAUDIBLE].</span></p><p><span m="2260220">QIQI WANG: [INAUDIBLE]</span>
  <span m="2260230">is</span> <span m="2260510">always</span> <span m="2260760">delta</span>
  <span m="2261190">x</span> <span m="2261300">over delta y.</span> <span m="2262110">In</span>
  <span m="2262360">this</span> <span m="2262590">case,</span> <span m="2262670">delta</span>
  <span m="2262880">x</span> <span m="2263730">is</span> <span m="2264850">[INAUDIBLE]</span>
  <span m="2265020">delta</span> <span m="2265110">y.</span> <span m="2266356">Delta</span>
  <span m="2266774">t</span> <span m="2267192">[INAUDIBLE].</span> <span m="2267610">Delta</span>
  <span m="2267810">x</span> <span m="2267910">over</span> <span m="2268390">delta</span>
  <span m="2268480">t</span> <span m="2268730">is</span> <span m="2269040">kind</span>
  <span m="2269400">of</span> <span m="2269760">the</span> <span m="2270110">inverse.</span>
  <span m="2271080">Does</span> <span m="2271565">that make sense?</span> <span m="2273020">I
  mean,</span> <span m="2273320">a</span> <span m="2273510">speed</span> <span m="2273630">equal</span>
  <span m="2273770">zero</span> <span m="2274500">is like a</span> <span m="2274982">vertical
  line.</span> <span m="2276910">A</span> <span m="2277040">vertical</span> <span
  m="2277440">line</span> <span m="2278035">has</span> <span m="2278340">no</span>
  <span m="2278390">delta</span> <span m="2278470">x</span> <span m="2278680">but</span>
  <span m="2278930">lots</span> <span m="2279402">of</span> <span m="2279874">delta</span>
  <span m="2280346">t.</span> <span m="2281020">So</span> <span m="2281350">it''s
  low</span> <span m="2281820">speed.</span> <span m="2283500">And</span> <span m="2283920">the
  line that is</span> <span m="2286540">very</span> <span m="2286780">shallow</span>
  <span m="2287590">is</span> <span m="2287770">the</span> <span m="2287870">high</span>
  <span m="2288330">speed line</span> <span m="2288826">because</span> <span m="2289322">it</span>
  <span m="2289820">has a</span> <span m="2290120">lot</span> <span m="2290210">delta</span>
  <span m="2290645">x</span> <span m="2291080">over</span> <span m="2291360">small</span>
  <span m="2291600">delta</span> <span m="2291970">t.</span> <span m="2292710">So</span>
  <span m="2293436">we</span> <span m="2293842">see</span> <span m="2294248">these</span>
  <span m="2295060">are</span> <span m="2295270">high speed.</span> <span m="2297785">And
  these</span> <span m="2298250">near</span> <span m="2298570">vertical</span> <span
  m="2298830">lines</span> <span m="2299090">are</span> <span m="2299410">low</span>
  <span m="2299800">speed.</span> <span m="2300950">And</span> <span m="2301250">these</span>
  <span m="2301630">lines</span> <span m="2302570">sloping</span> <span m="2302980">towards</span>
  <span m="2303250">the</span> <span m="2303300">left</span> <span m="2303620">are</span>
  <span m="2304037">negative</span> <span m="2304454">speed.</span> <span m="2304871">They
  are</span> <span m="2305290">moving towards</span> <span m="2305550">the left.</span>
  <span m="2307110">Right?</span></p><p><span m="2308460">OK.</span> <span m="2309460">The</span>
  <span m="2309690">solution</span> <span m="2310160">behaves</span> <span m="2310630">like
  this.</span> <span m="2312398">The</span> <span m="2312840">characteristics</span>
  <span m="2313282">are</span> <span m="2313724">proportional</span> <span m="2314830">to</span>
  <span m="2315360">the</span> <span m="2315590">solution</span> <span m="2315900">itself.</span>
  <span m="2317180">The</span> <span m="2317320">redder</span> <span m="2317750">it
  is,</span> <span m="2320310">the larger</span> <span m="2320745">the</span> <span
  m="2321180">position</span> <span m="2321615">is.</span> <span m="2322485">And</span>
  <span m="2322920">the</span> <span m="2323180">more</span> <span m="2323465">quantity,</span>
  <span m="2324600">the</span> <span m="2325025">larger</span> <span m="2325450">the</span>
  <span m="2325680">speed</span> <span m="2325890">is.</span> <span m="2327160">The</span>
  <span m="2327430">bluer</span> <span m="2328180">the</span> <span m="2328310">solution</span>
  <span m="2328780">is,</span> <span m="2329650">the</span> <span m="2329860">more</span>
  <span m="2330210">negative</span> <span m="2330440">the solution</span> <span m="2331130">is.</span>
  <span m="2331600">And</span> <span m="2331690">the solution</span> <span m="2332030">moves</span>
  <span m="2332710">backwards</span> <span m="2333050">at</span> <span m="2333110">a</span>
  <span m="2333510">negative</span> <span m="2334440">velocity.</span> <span m="2336220">This</span>
  <span m="2336430">is</span> <span m="2336580">how the</span> <span m="2336660">solution</span>
  <span m="2336900">behaves</span> <span m="2338810">in</span> <span m="2338950">a</span>
  <span m="2339010">Burgers</span> <span m="2339350">equation.</span></p><p><span
  m="2342360">And</span> <span m="2343670">we</span> <span m="2343900">also</span>
  <span m="2344220">have</span> <span m="2344420">this</span> <span m="2344990">shock
  wave</span> <span m="2345450">that</span> <span m="2345896">moves</span> <span m="2348030">at</span>
  <span m="2348530">an</span> <span m="2348860">average</span> <span m="2349190">velocity</span>
  <span m="2349310">of</span> <span m="2349630">[? 6.54 ?].</span> <span m="2354820">Right?</span>
  <span m="2354910">So</span> <span m="2355110">we</span> <span m="2355500">this</span>
  <span m="2355650">shock wave</span> <span m="2356020">moves</span> <span m="2356340">kind</span>
  <span m="2356605">of</span> <span m="2356870">slowly</span> <span m="2357500">towards</span>
  <span m="2357810">the</span> <span m="2357910">right.</span> <span m="2358200">Because</span>
  <span m="2359228">if</span> <span m="2359646">you</span> <span m="2360064">look</span>
  <span m="2361440">at</span> <span m="2361770">the</span> <span m="2362100">average</span>
  <span m="2363130">left</span> <span m="2363420">value</span> <span m="2363710">and</span>
  <span m="2363770">right</span> <span m="2363930">value,</span> <span m="2364419">it''s</span>
  <span m="2364908">slightly</span> <span m="2365397">positive.</span> <span m="2366864">So</span>
  <span m="2367353">the shock</span> <span m="2367842">waves</span> <span m="2368331">moves</span>
  <span m="2368820">slightly</span> <span m="2369309">towards</span> <span m="2369798">the
  right.</span></p><p><span m="2370780">OK.</span> <span m="2371050">That''s</span>
  <span m="2371310">how</span> <span m="2371500">the</span> <span m="2371580">solution</span>
  <span m="2372320">for</span> <span m="2372470">the</span> <span m="2372550">Burgers''</span>
  <span m="2372900">equation</span> <span m="2373200">behaves.</span> <span m="2373720">And</span>
  <span m="2374680">we</span> <span m="2374820">need</span> <span m="2375080">to</span>
  <span m="2376880">have</span> <span m="2377020">a</span> <span m="2377080">method</span>
  <span m="2378080">to</span> <span m="2378400">solve</span> <span m="2379470">the</span>
  <span m="2379600">Burgers</span> <span m="2380010">equation.</span> <span m="2381060">And</span>
  <span m="2381300">we''re</span> <span m="2381560">interested</span> <span m="2382190">not</span>
  <span m="2382430">only</span> <span m="2382720">in</span> <span m="2382810">the</span>
  <span m="2383060">smooth</span> <span m="2383380">part</span> <span m="2383590">of</span>
  <span m="2383680">the</span> <span m="2383780">solution,</span> <span m="2384300">but</span>
  <span m="2384490">also</span> <span m="2385310">in the</span> <span m="2386730">discontinuous</span>
  <span m="2388060">part</span> <span m="2388330">of</span> <span m="2388390">the</span>
  <span m="2388490">solution.</span></p><p><span m="2391630">OK</span> <span m="2393440">let</span>
  <span m="2393940">me</span> <span m="2394440">just</span> <span m="2399530">do</span>
  <span m="2399860">another</span> <span m="2400280">case</span> <span m="2400760">and</span>
  <span m="2401080">ask</span> <span m="2401390">you</span> <span m="2401790">how
  the</span> <span m="2401870">solution is</span> <span m="2402160">going</span> <span
  m="2402450">to</span> <span m="2402650">behave.</span> <span m="2407890">All</span>
  <span m="2408060">right.</span> <span m="2408460">So</span> <span m="2408650">if</span>
  <span m="2408840">I</span> <span m="2409020">have</span> <span m="2411148">a</span>
  <span m="2411570">function</span> <span m="2412050">u</span> <span m="2412300">of</span>
  <span m="2412640">x</span> <span m="2413470">for</span> <span m="2413640">the</span>
  <span m="2413690">Burgers</span> <span m="2414220">equation,</span> <span m="2414760">the</span>
  <span m="2414900">Burgers</span> <span m="2415180">equation</span> <span m="2415450">is</span>
  <span m="2415740">partial u-partial t</span> <span m="2418940">plus</span> <span
  m="2419230">U</span> <span m="2419610">times</span> <span m="2420160">partial-partial
  x</span> <span m="2422210">equals</span> <span m="2422630">zero.</span> <span m="2425970">Or</span>
  <span m="2426830">in</span> <span m="2427050">a</span> <span m="2427120">conservative</span>
  <span m="2427890">form,</span> <span m="2428990">it''s</span> <span m="2429340">partial
  u-partial t</span> <span m="2432530">plus</span> <span m="2432900">partial u over</span>
  <span m="2433280">partial x</span> <span m="2433980">and</span> <span m="2434790">half</span>
  <span m="2435130">of</span> <span m="2435310">u</span> <span m="2435540">squared</span>
  <span m="2436090">equal</span> <span m="2436430">to</span> <span m="2436770">zero.</span>
  <span m="2438105">Right? So</span> <span m="2438550">this</span> <span m="2438942">is--</span>
  <span m="2439334">this</span> <span m="2439726">form</span> <span m="2440120">is</span>
  <span m="2440605">[INAUDIBLE]</span> <span m="2441575">u squared</span> <span m="2442060">out
  of</span> <span m="2442545">the spatial</span> <span m="2443030">derivative.</span></p><p><span
  m="2447400">After</span> <span m="2447630">a</span> <span m="2447670">while,</span>
  <span m="2448170">can anybody</span> <span m="2448670">tell me</span> <span m="2449170">how
  the solution</span> <span m="2449670">is going</span> <span m="2450170">to look?</span>
  <span m="2454600">Yeah?</span></p><p><span m="2455329">AUDIENCE: Is this</span>
  <span m="2455828">periodic?</span></p><p><span m="2457824">QIQI WANG: Let''s say</span>
  <span m="2458323">they are</span> <span m="2458822">periodic,</span></p><p><span
  m="2459820">AUDIENCE: [INAUDIBLE].</span></p><p><span m="2462820">QIQI WANG: Yeah.</span></p><p><span
  m="2463553">AUDIENCE: The shock waves</span> <span m="2464046">are formed</span>
  <span m="2464539">and</span> <span m="2465032">[INAUDIBLE].</span></p><p><span m="2469970">QIQI
  WANG: Yes.</span> <span m="2470250">Exactly.</span> <span m="2471914">So</span>
  <span m="2472330">this</span> <span m="2472690">part</span> <span m="2473060">moves</span>
  <span m="2473400">at</span> <span m="2473866">a positive</span> <span m="2474332">speed.</span>
  <span m="2474800">This</span> <span m="2475070">part moves</span> <span m="2475535">at
  a</span> <span m="2476000">negative</span> <span m="2476465">speed.</span> <span
  m="2476930">So</span> <span m="2477740">you</span> <span m="2477800">can</span>
  <span m="2477960">really</span> <span m="2478680">see</span> <span m="2479360">the</span>
  <span m="2479460">solution</span> <span m="2480200">later</span> <span m="2480610">on</span>
  <span m="2480900">should</span> <span m="2481110">become</span> <span m="2481660">something</span>
  <span m="2481970">like</span> <span m="2482250">this.</span> <span m="2485260">And</span>
  <span m="2485650">later</span> <span m="2486070">on,</span> <span m="2486330">the</span>
  <span m="2486440">shock</span> <span m="2486790">wave</span> <span m="2487370">should</span>
  <span m="2487760">form.</span> <span m="2488100">I</span> <span m="2488220">actually</span>
  <span m="2488620">don''t</span> <span m="2488810">know</span> <span m="2489030">if</span>
  <span m="2489400">it''s</span> <span m="2489550">moving</span> <span m="2489920">towards</span>
  <span m="2490290">the</span> <span m="2490860">left</span> <span m="2491150">or</span>
  <span m="2491270">moving</span> <span m="2491530">towards the</span> <span m="2491890">right.</span>
  <span m="2492170">But the</span> <span m="2492650">shock wave</span> <span m="2493130">is
  going to form</span> <span m="2493610">over here.</span></p><p><span m="2495050">AUDIENCE:
  [INAUDIBLE].</span></p><p><span m="2496490">QIQI WANG: Uh huh.</span></p><p><span
  m="2497450">AUDIENCE: [INAUDIBLE].</span></p><p><span m="2503210">QIQI WANG: Yeah.</span>
  <span m="2503710">Good point.</span> <span m="2504366">This</span> <span m="2504702">part</span>
  <span m="2505040">is</span> <span m="2505390">a</span> <span m="2505430">little
  bit</span> <span m="2505700">[? difficult ?].</span> <span m="2506630">So</span>
  <span m="2507095">the positive</span> <span m="2507560">part is</span> <span m="2508025">still</span>
  <span m="2508490">dominant</span> <span m="2509030">and</span> <span m="2509270">the</span>
  <span m="2509741">shock</span> <span m="2510212">wave is going</span> <span m="2510683">to
  move</span> <span m="2511154">towards the right.</span> <span m="2512100">Good</span>
  <span m="2512240">point.</span> <span m="2513290">OK.</span> <span m="2513820">So</span>
  <span m="2513980">this</span> <span m="2514190">is</span> <span m="2514340">how</span>
  <span m="2515720">the</span> <span m="2515900">equation</span> <span m="2516240">behaves.</span>
  <span m="2516675">And</span> <span m="2517110">let''s</span> <span m="2519180">see</span>
  <span m="2519360">how</span> <span m="2519610">do</span> <span m="2519700">we</span>
  <span m="2519890">solve</span> <span m="2520300">it</span> <span m="2521340">using</span>
  <span m="2522370">a</span> <span m="2522490">finite</span> <span m="2522790">volume</span>
  <span m="2523290">method.</span></p><p><span m="2530420">OK.</span> <span m="2534740">So</span>
  <span m="2535000">let</span> <span m="2535240">me</span> <span m="2535380">write</span>
  <span m="2535730">down</span> <span m="2535960">the</span> <span m="2536060">equation</span>
  <span m="2536480">again.</span> <span m="2536945">Partial u-partial t</span> <span
  m="2538340">plus</span> <span m="2538805">partial-partial x</span> <span m="2541270">of</span>
  <span m="2541770">half</span> <span m="2542080">of</span> <span m="2542230">u</span>
  <span m="2542420">squared</span> <span m="2543040">equal to</span> <span m="2543480">zero.</span>
  <span m="2544750">Right?</span> <span m="2545380">Or</span> <span m="2545840">in</span>
  <span m="2546220">the</span> <span m="2546290">more</span> <span m="2546590">general</span>
  <span m="2547120">form,</span> <span m="2548510">I</span> <span m="2548670">should</span>
  <span m="2548870">be</span> <span m="2549020">writing</span> <span m="2550454">partial
  u-partial t</span> <span m="2551330">plus</span> <span m="2552740">partial F</span>
  <span m="2553780">of</span> <span m="2553920">u</span> <span m="2554110">partial</span>
  <span m="2554310">x</span> <span m="2554950">equal</span> <span m="2555260">to</span>
  <span m="2555500">zero.</span> <span m="2556280">And</span> <span m="2557350">to</span>
  <span m="2557570">specialize</span> <span m="2558490">this</span> <span m="2558820">general</span>
  <span m="2559450">conservation</span> <span m="2560060">law</span> <span m="2560700">into</span>
  <span m="2561010">the</span> <span m="2561120">Burgers</span> <span m="2561630">equation,</span>
  <span m="2562210">we</span> <span m="2562340">just</span> <span m="2562620">need</span>
  <span m="2562750">to</span> <span m="2562850">set</span> <span m="2563200">F</span>
  <span m="2563430">of</span> <span m="2563610">u</span> <span m="2563880">equal</span>
  <span m="2564360">to</span> <span m="2565540">half</span> <span m="2565830">of</span>
  <span m="2565970">u</span> <span m="2566130">squared.</span></p><p><span m="2569620">OK.</span>
  <span m="2570580">And</span> <span m="2572290">again,</span> <span m="2572610">you</span>
  <span m="2572690">find the</span> <span m="2572870">volume.</span> <span m="2573330">We</span>
  <span m="2573520">are</span> <span m="2573680">solving</span> <span m="2575130">for</span>
  <span m="2575400">the</span> <span m="2575520">derivative.</span> <span m="2577750">OK.</span>
  <span m="2578030">Now</span> <span m="2578240">we</span> <span m="2578630">need</span>
  <span m="2578800">to,</span> <span m="2579080">we</span> <span m="2579270">are</span>
  <span m="2579360">solving</span> <span m="2582070">the--</span> <span m="2583430">we</span>
  <span m="2583640">are</span> <span m="2583730">tracking</span> <span m="2584350">the</span>
  <span m="2584470">evolution</span> <span m="2585770">of</span> <span m="2586080">this</span>
  <span m="2586760">Uk</span> <span m="2587430">average.</span> <span m="2590150">And</span>
  <span m="2590340">the</span> <span m="2590460">Uk</span> <span m="2590860">average</span>
  <span m="2592190">is</span> <span m="2592560">defined</span> <span m="2592950">as</span>
  <span m="2594230">one</span> <span m="2594630">over</span> <span m="2594900">delta</span>
  <span m="2595250">x.</span> <span m="2596000">So</span> <span m="2596180">delta</span>
  <span m="2596500">x</span> <span m="2596800">in</span> <span m="2596900">this</span>
  <span m="2597090">case</span> <span m="2598070">is</span> <span m="2598330">the</span>
  <span m="2598430">size</span> <span m="2599040">of</span> <span m="2599330">each</span>
  <span m="2599620">control</span> <span m="2600076">volume.</span> <span m="2600990">OK?</span>
  <span m="2607170">Control</span> <span m="2609078">volume.</span> <span m="2611470">OK.</span>
  <span m="2612540">Times</span> <span m="2614010">the</span> <span m="2614190">integral</span>
  <span m="2616460">from</span> <span m="2616860">the</span> <span m="2616960">left</span>
  <span m="2617520">of</span> <span m="2618100">the</span> <span m="2618270">k-th</span>
  <span m="2618680">control</span> <span m="2619300">volume</span> <span m="2619550">to</span>
  <span m="2619660">the</span> <span m="2619820">right</span> <span m="2620210">of</span>
  <span m="2620400">the k-th</span> <span m="2620892">control</span> <span m="2621384">volume.</span>
  <span m="2623352">OK.</span> <span m="2624340">And</span> <span m="2624470">the</span>
  <span m="2624750">size</span> <span m="2624850">of the</span> <span m="2624930">control</span>
  <span m="2625430">volume</span> <span m="2625620">is</span> <span m="2625760">of
  course</span> <span m="2625910">equal</span> <span m="2626185">to</span> <span m="2626520">Rk</span>
  <span m="2627011">minus</span> <span m="2627502">Lk.</span></p><p><span m="2629960">OK.</span>
  <span m="2630180">The</span> <span m="2630270">integral</span> <span m="2630860">is</span>
  <span m="2631150">the</span> <span m="2631290">u</span> <span m="2631760">of</span>
  <span m="2631980">x</span> <span m="2632870">and</span> <span m="2633100">t</span>
  <span m="2634410">dx.</span> <span m="2639280">This</span> <span m="2639560">is</span>
  <span m="2640460">my</span> <span m="2640720">cell</span> <span m="2641230">average.</span>
  <span m="2644400">And</span> <span m="2646120">in</span> <span m="2646380">general,</span>
  <span m="2646910">this</span> <span m="2646980">is</span> <span m="2647480">delta</span>
  <span m="2647750">xk,</span> <span m="2648600">right?</span> <span m="2648810">Because</span>
  <span m="2649120">each</span> <span m="2649544">control volume</span> <span m="2649968">can
  be</span> <span m="2650392">different.</span> <span m="2651240">And</span> <span
  m="2651810">here</span> <span m="2652080">we</span> <span m="2652280">are</span>
  <span m="2652380">just</span> <span m="2652570">going</span> <span m="2652700">to</span>
  <span m="2652770">talk</span> <span m="2653070">about</span> <span m="2654120">the</span>
  <span m="2654330">case</span> <span m="2654740">with</span> <span m="2655060">a</span>
  <span m="2655150">uniform,</span> <span m="2657250">uniform</span> <span m="2658200">mesh.</span>
  <span m="2660210">And</span> <span m="2660400">the</span> <span m="2660460">uniform</span>
  <span m="2660960">mesh</span> <span m="2661540">responds</span> <span m="2662190">to</span>
  <span m="2662650">delta</span> <span m="2663530">Xk</span> <span m="2663870">or</span>
  <span m="2664210">r</span> <span m="2664550">equal</span> <span m="2665040">to</span>
  <span m="2665530">delta</span> <span m="2666020">x.</span> <span m="2667000">And</span>
  <span m="2667550">the</span> <span m="2668120">L</span> <span m="2668510">of</span>
  <span m="2668907">k</span> <span m="2670100">is</span> <span m="2670490">equal</span>
  <span m="2670890">to</span> <span m="2672190">k</span> <span m="2672780">minus</span>
  <span m="2673040">one</span> <span m="2673140">times delta x.</span> <span m="2675430">And</span>
  <span m="2675730">the</span> <span m="2675890">r</span> <span m="2676310">of</span>
  <span m="2676510">k</span> <span m="2676800">is</span> <span m="2677090">equal</span>
  <span m="2677420">to</span> <span m="2678312">k</span> <span m="2678650">times</span>
  <span m="2678840">delta</span> <span m="2679140">x.</span></p><p><span m="2680996">All
  right.</span> <span m="2681460">So the</span> <span m="2681590">L</span> <span m="2681910">of</span>
  <span m="2682080">1,</span> <span m="2682840">the</span> <span m="2682950">left</span>
  <span m="2683360">boundary</span> <span m="2683790">of</span> <span m="2684010">the
  first</span> <span m="2684280">[INAUDIBLE]</span> <span m="2684640">is</span> <span
  m="2684960">at</span> <span m="2685210">zero.</span> <span m="2688112">The</span>
  <span m="2688560">right</span> <span m="2689390">boundary</span> <span m="2693100">of</span>
  <span m="2693260">the</span> <span m="2693320">k-th</span> <span m="2693890">control</span>
  <span m="2694010">volume</span> <span m="2694370">is</span> <span m="2694560">always</span>
  <span m="2695640">the</span> <span m="2695720">same</span> <span m="2696190">as</span>
  <span m="2696530">the</span> <span m="2696610">left</span> <span m="2696930">boundary</span>
  <span m="2697120">of</span> <span m="2697190">the</span> <span m="2697570">next</span>
  <span m="2697950">control volume.</span> <span m="2700090">That</span> <span m="2700730">has</span>
  <span m="2701010">to</span> <span m="2701110">be</span> <span m="2701240">satisfied</span>
  <span m="2701696">for finite</span> <span m="2702152">volume method.</span> <span
  m="2703520">You</span> <span m="2703680">have</span> <span m="2703910">to</span>
  <span m="2704020">divide</span> <span m="2704440">the</span> <span m="2704730">entire</span>
  <span m="2705260">space,</span> <span m="2705540">the entire</span> <span m="2705966">domain</span>
  <span m="2707670">into</span> <span m="2708160">non-overlapping</span> <span m="2713390">into</span>
  <span m="2713700">non-overlapping</span> <span m="2714650">control</span> <span
  m="2715000">volumes</span> <span m="2715800">and</span> <span m="2716110">leave</span>
  <span m="2716420">no</span> <span m="2717820">empty</span> <span m="2718190">space</span>
  <span m="2718490">in</span> <span m="2718600">between.</span> <span m="2719640">You</span>
  <span m="2719840">have</span> <span m="2720040">to</span> <span m="2720690">basically</span>
  <span m="2721330">partition</span> <span m="2721920">the</span> <span m="2722000">entire</span>
  <span m="2722270">[? combination ?]</span> <span m="2722540">domain</span> <span
  m="2723470">into</span> <span m="2724140">non-overlapping</span> <span m="2725382">control</span>
  <span m="2725853">volumes.</span> <span m="2727737">And</span> <span m="2728210">you</span>
  <span m="2728360">can''t</span> <span m="2728590">leave</span> <span m="2728780">anything
  open.</span></p><p><span m="2730710">OK.</span> <span m="2731440">So</span> <span
  m="2731610">now</span> <span m="2731890">let''s</span> <span m="2732700">take</span>
  <span m="2732940">a</span> <span m="2733000">look</span> <span m="2733320">at</span>
  <span m="2733570">what</span> <span m="2733800">is</span> <span m="2733960">the</span>
  <span m="2734060">time</span> <span m="2734510">derivative</span> <span m="2736520">of</span>
  <span m="2737880">this</span> <span m="2738130">average?</span> <span m="2740200">To
  figure out</span> <span m="2740520">the</span> <span m="2740600">time</span> <span
  m="2741000">derivative</span> <span m="2741600">of</span> <span m="2741770">this</span>
  <span m="2742000">average,</span> <span m="2744180">we</span> <span m="2744420">have</span>
  <span m="2744580">to</span> <span m="2744730">use</span> <span m="2745210">the</span>
  <span m="2745320">integral</span> <span m="2745980">form</span> <span m="2746850">of</span>
  <span m="2747070">the</span> <span m="2747880">conservation</span> <span m="2748340">law.</span>
  <span m="2749090">It is</span> <span m="2749380">equal</span> <span m="2749680">to</span>
  <span m="2749770">one</span> <span m="2750120">over</span> <span m="2750320">delta</span>
  <span m="2750590">k</span> <span m="2752070">times</span> <span m="2752680">d/dt</span>
  <span m="2754560">of</span> <span m="2755140">Lk</span> <span m="2756126">Rk</span>
  <span m="2757112">Uxk</span> <span m="2758930">dx.</span> <span m="2761160">And</span>
  <span m="2761420">by</span> <span m="2761640">applying</span> <span m="2762310">the</span>
  <span m="2762390">integral</span> <span m="2763080">form</span> <span m="2763360">of</span>
  <span m="2763500">the</span> <span m="2764100">conversion</span> <span m="2764740">law,</span>
  <span m="2766260">we</span> <span m="2766450">get</span> <span m="2767320">the</span>
  <span m="2767480">flux</span> <span m="2769980">at</span> <span m="2770700">the</span>
  <span m="2771160">right hand</span> <span m="2771580">side</span> <span m="2772610">minus</span>
  <span m="2773150">the</span> <span m="2773260">flux</span> <span m="2773970">at</span>
  <span m="2774290">the</span> <span m="2774610">left</span> <span m="2775000">hand
  side</span> <span m="2775410">of</span> <span m="2775500">the</span> <span m="2775570">control</span>
  <span m="2775930">volume</span> <span m="2777080">divided</span> <span m="2777494">by--</span>
  <span m="2778736">oh,</span> <span m="2779150">we</span> <span m="2779490">don''t</span>
  <span m="2779740">need</span> <span m="2779890">to</span> <span m="2780000">divide</span>
  <span m="2780510">anything</span> <span m="2780850">because</span> <span m="2781340">we</span>
  <span m="2781520">are</span> <span m="2782120">looking</span> <span m="2782380">at</span>
  <span m="2782450">the</span> <span m="2782530">derivative</span> <span m="2783010">of</span>
  <span m="2783080">the</span> <span m="2783200">integral.</span> <span m="2783650">Right?</span>
  <span m="2784350">And</span> <span m="2784720">plus</span> <span m="2784810">the</span>
  <span m="2785690">integral</span> <span m="2787850">L</span> <span m="2788150">to
  R</span> <span m="2788720">of</span> <span m="2789770">a</span> <span m="2789900">[INAUDIBLE]</span>
  <span m="2792860">which</span> <span m="2793110">is</span> <span m="2793380">zero</span>
  <span m="2794760">in</span> <span m="2794940">the</span> <span m="2795010">Burgers</span>
  <span m="2795460">equation</span> <span m="2795810">case.</span> <span m="2796640">Because</span>
  <span m="2797050">in</span> <span m="2797150">the</span> <span m="2797220">Burgers</span>
  <span m="2797580">equation,</span> <span m="2798580">we</span> <span m="2798750">don''t</span>
  <span m="2798970">have</span> <span m="2799220">any</span> <span m="2800073">source</span>
  <span m="2800466">then.</span> <span m="2800940">The</span> <span m="2801020">source
  is</span> <span m="2801443">zero.</span></p><p><span m="2803560">OK.</span> <span
  m="2804680">Now</span> <span m="2806150">we</span> <span m="2806480">have</span>
  <span m="2807090">an</span> <span m="2807420">evolution</span> <span m="2807820">equation</span>
  <span m="2809230">for</span> <span m="2809360">the</span> <span m="2809570">cell</span>
  <span m="2809890">average.</span> <span m="2812400">And</span> <span m="2812810">up</span>
  <span m="2813180">to</span> <span m="2813550">here,</span> <span m="2813810">we''ve</span>
  <span m="2814070">made</span> <span m="2814380">no</span> <span m="2814830">approximations.</span>
  <span m="2815762">Right?</span> <span m="2817630">In finite</span> <span m="2818060">difference,</span>
  <span m="2818450">we are</span> <span m="2818690">approximating</span> <span m="2819055">the</span>
  <span m="2819420">spatial derivative.</span> <span m="2820920">But here,</span>
  <span m="2821080">we don''t</span> <span m="2821567">need to make</span> <span m="2822054">any</span>
  <span m="2822541">approximations</span> <span m="2824002">in getting</span> <span
  m="2824489">to here.</span> <span m="2826930">And the flux</span> <span m="2830610">in</span>
  <span m="2831040">this</span> <span m="2831420">case</span> <span m="2831880">is</span>
  <span m="2832286">half</span> <span m="2832692">of</span> <span m="2833100">u</span>
  <span m="2833450">squared</span> <span m="2833936">at</span> <span m="2834422">the</span>
  <span m="2835100">cell</span> <span m="2835550">boundaries.</span></p><p><span m="2838260">Now</span>
  <span m="2838680">this</span> <span m="2838860">is</span> <span m="2839100">the</span>
  <span m="2839290">point</span> <span m="2839640">we</span> <span m="2839890">have</span>
  <span m="2840080">to</span> <span m="2840190">start</span> <span m="2840490">making</span>
  <span m="2840940">approximations.</span> <span m="2842510">Because</span> <span
  m="2842990">unlike</span> <span m="2844780">in</span> <span m="2844940">finite</span>
  <span m="2845200">difference,</span> <span m="2845670">we</span> <span m="2845970">have</span>
  <span m="2846810">the</span> <span m="2846920">value</span> <span m="2847450">of</span>
  <span m="2847590">the</span> <span m="2847630">function</span> <span m="2847910">x</span>
  <span m="2848344">at</span> <span m="2848778">[? these ?]</span> <span m="2849212">points.</span>
  <span m="2850080">But</span> <span m="2850200">here</span> <span m="2850450">we</span>
  <span m="2850570">don''t.</span> <span m="2854109">We</span> <span m="2854566">don''t</span>
  <span m="2855480">have</span> <span m="2855910">the</span> <span m="2856070">solution</span>
  <span m="2856370">at</span> <span m="2856670">either</span> <span m="2857162">Lk</span>
  <span m="2858640">or</span> <span m="2859020">Rk.</span> <span m="2860900">Right?</span>
  <span m="2861260">We</span> <span m="2861520">don''t</span> <span m="2861960">have</span>
  <span m="2862220">the</span> <span m="2862360">solution</span> <span m="2864210">at</span>
  <span m="2864710">the</span> <span m="2864860">control</span> <span m="2865330">volume</span>
  <span m="2865735">boundaries.</span> <span m="2866950">We</span> <span m="2867190">only</span>
  <span m="2867640">have</span> <span m="2867880">the</span> <span m="2868310">cell</span>
  <span m="2868750">average</span> <span m="2869270">solution</span> <span m="2869700">values.</span></p><p><span
  m="2870900">So</span> <span m="2870970">we</span> <span m="2871190">have</span>
  <span m="2871490">to</span> <span m="2871710">approximate,</span> <span m="2875050">we</span>
  <span m="2875230">have</span> <span m="2875460">to</span> <span m="2875580">do</span>
  <span m="2875850">the</span> <span m="2875970">finite</span> <span m="2876610">volume</span>
  <span m="2881040">approximation.</span> <span m="2887370">I</span> <span m="2887750">have</span>
  <span m="2888120">to</span> <span m="2888260">approximate</span> <span m="2889240">the</span>
  <span m="2889420">flux</span> <span m="2892480">at</span> <span m="2893720">rk.</span>
  <span m="2895480">I</span> <span m="2895630">have</span> <span m="2895870">to</span>
  <span m="2896100">approximate</span> <span m="2897160">it</span> <span m="2897330">as</span>
  <span m="2898242">F</span> <span m="2900070">of</span> <span m="2900890">a</span>
  <span m="2901080">function.</span> <span m="2903480">The</span> <span m="2903670">most</span>
  <span m="2904100">simple</span> <span m="2904540">cases</span> <span m="2905990">u</span>
  <span m="2906740">bar</span> <span m="2907120">of</span> <span m="2907500">x</span>
  <span m="2908570">Uk</span> <span m="2909010">minus</span> <span m="2909100">one</span>
  <span m="2910190">and</span> <span m="2910530">u</span> <span m="2910740">bar</span>
  <span m="2911020">of</span> <span m="2911350">k.</span> <span m="2913740">F</span>
  <span m="2914218">at--</span> <span m="2916610">sorry,</span> <span m="2917420">this</span>
  <span m="2917630">has</span> <span m="2917810">to</span> <span m="2917940">be</span>
  <span m="2918160">at</span> <span m="2918430">Lk</span> <span m="2918920">because</span>
  <span m="2919230">I''m on</span> <span m="2919700">the</span> <span m="2919840">left.</span>
  <span m="2920800">Rk</span> <span m="2921400">has</span> <span m="2921600">to</span>
  <span m="2921720">be</span> <span m="2921870">approximated</span> <span m="2922355">as</span>
  <span m="2924030">a</span> <span m="2924290">flux</span> <span m="2924550">of</span>
  <span m="2924840">Uk</span> <span m="2926350">and</span> <span m="2926620">Uk</span>
  <span m="2927050">plus</span> <span m="2927410">one.</span></p><p><span m="2928155">So</span>
  <span m="2928620">let</span> <span m="2928730">me</span> <span m="2928930">draw</span>
  <span m="2929140">what</span> <span m="2929410">is</span> <span m="2929580">happening</span>
  <span m="2930080">here.</span> <span m="2933500">So</span> <span m="2933900">I</span>
  <span m="2934210">have</span> <span m="2934860">a</span> <span m="2935000">bunch</span>
  <span m="2935290">of</span> <span m="2935660">cells.</span> <span m="2936830">This</span>
  <span m="2936960">is,</span> <span m="2937100">let''s</span> <span m="2937340">say,</span>
  <span m="2937640">k</span> <span m="2937780">minus</span> <span m="2938130">1.</span>
  <span m="2938500">This is</span> <span m="2938830">k.</span> <span m="2940310">k</span>
  <span m="2940630">plus one.</span> <span m="2941570">k</span> <span m="2942030">plus</span>
  <span m="2942300">two.</span> <span m="2943142">Right?</span> <span m="2944830">OK.</span></p><p><span
  m="2946550">So</span> <span m="2948990">this</span> <span m="2949230">point</span>
  <span m="2950050">is</span> <span m="2950450">the</span> <span m="2950880">left</span>
  <span m="2951420">boundary</span> <span m="2951970">of</span> <span m="2952210">k
  minus</span> <span m="2952650">one.</span> <span m="2953630">Here</span> <span m="2954090">is</span>
  <span m="2954370">the</span> <span m="2954530">right</span> <span m="2954830">boundary</span>
  <span m="2955270">of</span> <span m="2955490">k minus</span> <span m="2955890">one.</span>
  <span m="2956530">But</span> <span m="2956760">it</span> <span m="2956930">is</span>
  <span m="2957260">also</span> <span m="2957605">corresponding</span> <span m="2958560">to</span>
  <span m="2958680">the</span> <span m="2958790">left</span> <span m="2959070">boundary</span>
  <span m="2959260">of</span> <span m="2959330">k.</span> <span m="2961630">This</span>
  <span m="2961910">point</span> <span m="2962190">is</span> <span m="2962310">the</span>
  <span m="2962430">right</span> <span m="2962670">boundary</span> <span m="2962960">of</span>
  <span m="2963050">k</span> <span m="2963315">but</span> <span m="2963580">also</span>
  <span m="2963980">corresponds</span> <span m="2964580">to</span> <span m="2964700">the</span>
  <span m="2964830">left</span> <span m="2965160">boundary</span> <span m="2965550">of</span>
  <span m="2965700">k</span> <span m="2965870">plus one.</span> <span m="2967370">This</span>
  <span m="2967630">point</span> <span m="2968000">is</span> <span m="2968250">the</span>
  <span m="2968380">right</span> <span m="2968660">boundary</span> <span m="2969120">of</span>
  <span m="2969440">k</span> <span m="2969610">plus</span> <span m="2969910">one</span>
  <span m="2970140">but is</span> <span m="2970410">also</span> <span m="2970760">the</span>
  <span m="2970840">left</span> <span m="2971080">boundary</span> <span m="2971370">of</span>
  <span m="2971530">k</span> <span m="2971660">plus</span> <span m="2971900">two.</span>
  <span m="2972680">This</span> <span m="2972990">point</span> <span m="2973350">is</span>
  <span m="2973660">the</span> <span m="2973810">right</span> <span m="2974100">boundary</span>
  <span m="2974390">of</span> <span m="2974490">k plus</span> <span m="2974970">two</span>
  <span m="2975240">but</span> <span m="2975680">also</span> <span m="2975820">the</span>
  <span m="2975950">left boundary</span> <span m="2976540">of</span> <span m="2976680">k
  plus 3.</span></p><p><span m="2980300">I need</span> <span m="2981770">to</span>
  <span m="2982090">attach</span> <span m="2982516">a</span> <span m="2982942">flux</span>
  <span m="2983370">value</span> <span m="2983910">at</span> <span m="2984220">each</span>
  <span m="2984560">of</span> <span m="2984750">these</span> <span m="2984960">boundaries</span>
  <span m="2985685">in</span> <span m="2986150">order</span> <span m="2986640">to</span>
  <span m="2986860">solve</span> <span m="2987290">this</span> <span m="2987780">equation.</span>
  <span m="2988760">For this equation,</span> <span m="2989250">I</span> <span m="2989570">need</span>
  <span m="2990070">to</span> <span m="2990566">not only</span> <span m="2992054">resolve</span>
  <span m="2992550">the cell</span> <span m="2993046">average</span> <span m="2994038">in</span>
  <span m="2994534">each</span> <span m="2995030">cell,</span> <span m="2995526">I
  need</span> <span m="2996022">to have</span> <span m="2996518">the</span> <span
  m="2997014">flux</span> <span m="2997510">at these</span> <span m="2998006">boundary</span>
  <span m="2998502">points.</span> <span m="3001478">But</span> <span m="3001990">I</span>
  <span m="3002100">don''t</span> <span m="3002360">have</span> <span m="3002470">the
  solution</span> <span m="3002955">at these</span> <span m="3003440">boundary points.</span>
  <span m="3004410">All</span> <span m="3004780">I</span> <span m="3004980">have</span>
  <span m="3006380">is</span> <span m="3006820">the</span> <span m="3006930">cell</span>
  <span m="3007320">average</span> <span m="3009140">inside</span> <span m="3010810">of</span>
  <span m="3011130">the</span> <span m="3011250">cells.</span></p><p><span m="3013930">How</span>
  <span m="3014200">do</span> <span m="3014400">I</span> <span m="3014500">approximate</span>
  <span m="3014980">the</span> <span m="3015460">flux</span> <span m="3015940">at
  these</span> <span m="3016420">boundaries?</span> <span m="3017860">It makes</span>
  <span m="3018340">no sense</span> <span m="3018840">to</span> <span m="3019273">approximate</span>
  <span m="3020572">the</span> <span m="3021005">flux</span> <span m="3021440">at
  this</span> <span m="3021690">point</span> <span m="3022168">using</span> <span
  m="3022646">the</span> <span m="3023124">cell</span> <span m="3023602">averages</span>
  <span m="3025036">around</span> <span m="3026470">that</span> <span m="3026820">cell
  boundary.</span> <span m="3029730">At the</span> <span m="3030215">left</span> <span
  m="3030700">hand</span> <span m="3031185">side of</span> <span m="3031670">[INAUDIBLE],</span>
  <span m="3032155">and</span> <span m="3032640">this is</span> <span m="3033125">[?
  like the cell interface ?].</span> <span m="3034580">On the left hand</span> <span
  m="3035065">side</span> <span m="3035550">interface</span> <span m="3036035">is</span>
  <span m="3036520">[INAUDIBLE]</span> <span m="3037490">right</span> <span m="3037975">of</span>
  <span m="3038460">the interface</span> <span m="3038945">[INAUDIBLE].</span> <span
  m="3039430">So</span> <span m="3039940">I</span> <span m="3040260">need</span> <span
  m="3040420">to</span> <span m="3040560">approximate</span> <span m="3041880">the</span>
  <span m="3042140">flux</span> <span m="3043750">using</span> <span m="3045030">the</span>
  <span m="3045610">values.</span></p><p><span m="3047590">OK.</span> <span m="3048740">The</span>
  <span m="3049380">easiest</span> <span m="3049990">way</span> <span m="3050320">to</span>
  <span m="3050570">approximate</span> <span m="3050990">it</span> <span m="3051410">is</span>
  <span m="3051832">what</span> <span m="3052254">we</span> <span m="3052676">call</span>
  <span m="3053100">first</span> <span m="3053380">order</span> <span m="3053610">upwinds.</span>
  <span m="3054550">And</span> <span m="3055020">upwind</span> <span m="3056900">means</span>
  <span m="3058960">the</span> <span m="3060480">reverse</span> <span m="3061230">of</span>
  <span m="3061380">the</span> <span m="3061490">direction</span> <span m="3062610">towards</span>
  <span m="3063150">which</span> <span m="3063470">the</span> <span m="3063560">solution</span>
  <span m="3064030">goes.</span> <span m="3066450">OK.</span> <span m="3068160">In</span>
  <span m="3070070">this</span> <span m="3070260">situation,</span> <span m="3074279">can
  somebody</span> <span m="3074750">tell me</span> <span m="3074940">what</span> <span
  m="3075260">is</span> <span m="3075580">the upwind</span> <span m="3075970">direction?</span>
  <span m="3078050">Yeah?</span></p><p><span m="3080172">AUDIENCE: [INAUDIBLE].</span></p><p><span
  m="3082050">QIQI WANG: This</span> <span m="3082400">direction</span> <span m="3082770">is</span>
  <span m="3082980">the</span> <span m="3083070">upwind</span> <span m="3083230">direction?</span>
  <span m="3084580">Always?</span> <span m="3087918">It</span> <span m="3088381">depends.</span>
  <span m="3089310">Right.</span> <span m="3090440">The</span> <span m="3090760">upwind</span>
  <span m="3091000">direction</span> <span m="3092540">in</span> <span m="3092690">the</span>
  <span m="3092780">Burgers</span> <span m="3093260">equation</span> <span m="3093720">actually</span>
  <span m="3094160">means</span> <span m="3095070">almost</span> <span m="3095900">all</span>
  <span m="3096080">[INAUDIBLE]</span> <span m="3096310">conservation</span> <span
  m="3096470">laws</span> <span m="3097550">ends</span> <span m="3097840">on the solution.</span>
  <span m="3102098">In</span> <span m="3102574">this</span> <span m="3103050">part,</span>
  <span m="3105440">the</span> <span m="3105580">solution</span> <span m="3105970">was</span>
  <span m="3106230">here</span> <span m="3106730">and now</span> <span m="3107000">moved</span>
  <span m="3107270">here.</span> <span m="3108800">The</span> <span m="3108900">solution</span>
  <span m="3109310">is</span> <span m="3110480">[INAUDIBLE]</span> <span m="3111070">towards</span>
  <span m="3111530">the right.</span> <span m="3112680">It''s</span> <span m="3113100">kind</span>
  <span m="3113456">of</span> <span m="3114170">blown,</span> <span m="3115060">like</span>
  <span m="3115320">blown by</span> <span m="3115820">the wind,</span> <span m="3116320">and</span>
  <span m="3116820">that</span> <span m="3117320">comes</span> <span m="3117820">from
  the</span> <span m="3118320">left.</span></p><p><span m="3121090">So</span> <span
  m="3121220">what</span> <span m="3121380">is the</span> <span m="3121510">optimum</span>
  <span m="3121940">direction</span> <span m="3122310">for</span> <span m="3122780">this</span>
  <span m="3123030">part</span> <span m="3123420">in</span> <span m="3123810">the</span>
  <span m="3124200">red</span> <span m="3124570">region?</span> <span m="3126180">It''s</span>
  <span m="3126360">towards</span> <span m="3126570">the</span> <span m="3127032">left,</span>
  <span m="3127494">right?</span> <span m="3128880">What</span> <span m="3129342">is</span>
  <span m="3129804">the</span> <span m="3130270">optimum</span> <span m="3130390">direction</span>
  <span m="3130560">over here</span> <span m="3131018">in the</span> <span m="3131476">blue
  region?</span> <span m="3133308">Towards</span> <span m="3133770">the</span> <span
  m="3133890">right,</span> <span m="3134420">right?</span> <span m="3134720">The</span>
  <span m="3134870">wind is</span> <span m="3135330">coming</span> <span m="3135790">from</span>
  <span m="3136250">the right.</span> <span m="3137690">So</span> <span m="3137860">the</span>
  <span m="3137960">wind</span> <span m="3138290">is</span> <span m="3138710">going</span>
  <span m="3139180">this</span> <span m="3139650">way,</span> <span m="3140590">if
  this were the wind.</span> <span m="3142050">So</span> <span m="3142290">upwind</span>
  <span m="3142670">direction</span> <span m="3143090">is</span> <span m="3143700">looking
  where</span> <span m="3143940">the</span> <span m="3144020">wind</span> <span m="3144330">is</span>
  <span m="3144480">coming</span> <span m="3144830">from.</span> <span m="3147090">And</span>
  <span m="3147290">in</span> <span m="3147370">the</span> <span m="3147440">Burgers</span>
  <span m="3147810">equation,</span> <span m="3148150">the</span> <span m="3148260">upwind</span>
  <span m="3148570">direction</span> <span m="3149090">is</span> <span m="3149320">towards</span>
  <span m="3150250">minus</span> <span m="3150670">x</span> <span m="3151230">if</span>
  <span m="3152000">u is</span> <span m="3152180">positive.</span> <span m="3153204">It</span>
  <span m="3153636">is</span> <span m="3154070">plus</span> <span m="3154310">x</span>
  <span m="3155080">if</span> <span m="3155330">u</span> <span m="3155540">is negative.</span>
  <span m="3157350">This</span> <span m="3157540">is</span> <span m="3157690">upwind.</span></p><p><span
  m="3160100">It</span> <span m="3160230">makes</span> <span m="3160910">a</span>
  <span m="3161030">lot</span> <span m="3161260">of</span> <span m="3161440">sense</span>
  <span m="3161820">to</span> <span m="3162940">do</span> <span m="3163190">upwind</span>
  <span m="3163660">because</span> <span m="3164080">that''s</span> <span m="3164370">where</span>
  <span m="3164610">the</span> <span m="3164700">solution</span> <span m="3166240">comes</span>
  <span m="3166560">from,</span> <span m="3167030">right?</span> <span m="3167400">So</span>
  <span m="3169530">you</span> <span m="3169690">want</span> <span m="3169950">to--</span>
  <span m="3172270">I''m</span> <span m="3172500">going</span> <span m="3172640">to</span>
  <span m="3172730">talk</span> <span m="3172970">about</span> <span m="3173280">upwinding,</span>
  <span m="3174880">why</span> <span m="3174990">upwinding</span> <span m="3175070">makes</span>
  <span m="3175360">sense</span> <span m="3175670">really</span> <span m="3177260">later</span>
  <span m="3177590">when</span> <span m="3177950">we</span> <span m="3178060">talk</span>
  <span m="3178300">about</span> <span m="3178580">stability.</span> <span m="3180350">OK.</span>
  <span m="3181270">So</span> <span m="3181460">upwinding</span> <span m="3181640">schemes.</span>
  <span m="3182660">At</span> <span m="3183030">this</span> <span m="3183270">point,</span>
  <span m="3183500">I</span> <span m="3183550">just</span> <span m="3183840">need</span>
  <span m="3184010">to</span> <span m="3184160">tell</span> <span m="3184380">you</span>
  <span m="3184610">it</span> <span m="3184770">gives</span> <span m="3185020">stability.</span>
  <span m="3187330">And</span> <span m="3187630">in</span> <span m="3187910">the</span>
  <span m="3188180">upwinding</span> <span m="3188660">scheme,</span> <span m="3189910">I''m</span>
  <span m="3190080">just</span> <span m="3190380">going</span> <span m="3190550">to</span>
  <span m="3190670">say</span> <span m="3191290">F</span> <span m="3193120">of</span>
  <span m="3193730">k--</span> <span m="3194722">so F</span> <span m="3195220">at</span>
  <span m="3197790">the</span> <span m="3198070">interface--</span> <span m="3199010">so</span>
  <span m="3199090">I''m</span> <span m="3199210">going</span> <span m="3199360">to</span>
  <span m="3199670">define</span> <span m="3200330">F</span> <span m="3200580">of</span>
  <span m="3200760">k</span> <span m="3201000">plus</span> <span m="3201390">1/2,</span>
  <span m="3203430">defined</span> <span m="3204440">as</span> <span m="3206000">F</span>
  <span m="3207330">at</span> <span m="3208700">the</span> <span m="3208900">right</span>
  <span m="3209440">boundary</span> <span m="3210300">of</span> <span m="3210510">the</span>
  <span m="3210600">k</span> <span m="3211000">value,</span> <span m="3212020">which</span>
  <span m="3212230">is</span> <span m="3212540">also</span> <span m="3213630">the</span>
  <span m="3213790">same</span> <span m="3214310">as</span> <span m="3214690">the</span>
  <span m="3214780">left</span> <span m="3215170">boundary</span> <span m="3215660">of</span>
  <span m="3215860">the</span> <span m="3215930">k plus</span> <span m="3216480">one</span>
  <span m="3218290">cell.</span> <span m="3219630">It</span> <span m="3220120">is</span>
  <span m="3220596">the</span> <span m="3221072">flux</span> <span m="3222620">at</span>
  <span m="3222870">the</span> <span m="3223090">interface</span> <span m="3223415">between</span>
  <span m="3223740">the</span> <span m="3224200">k and</span> <span m="3224660">k
  plus</span> <span m="3225120">one</span> <span m="3225580">cell.</span> <span m="3225790">Right?</span>
  <span m="3226200">I</span> <span m="3226520">call</span> <span m="3226790">it</span>
  <span m="3226860">k plus</span> <span m="3227310">1/2,</span> <span m="3227770">because
  it''s</span> <span m="3228256">kind of</span> <span m="3228742">a halfway</span>
  <span m="3229228">between</span> <span m="3229714">the k and</span> <span m="3230200">k
  plus  1</span> <span m="3230686">cell.</span> <span m="3232150">Right?</span></p><p><span
  m="3234850">And</span> <span m="3236220">the</span> <span m="3236400">first</span>
  <span m="3236740">order</span> <span m="3236990">upwind</span> <span m="3237340">scheme</span>
  <span m="3237810">is</span> <span m="3238240">to</span> <span m="3238380">compute</span>
  <span m="3239010">F</span> <span m="3239230">of</span> <span m="3239350">k plus</span>
  <span m="3239780">1/2</span> <span m="3240230">is</span> <span m="3240730">equal</span>
  <span m="3241250">to</span> <span m="3242490">2</span> <span m="3242660">cases.</span>
  <span m="3244610">It is</span> <span m="3244990">either</span> <span m="3246530">F</span>
  <span m="3247030">of u</span> <span m="3247490">bar</span> <span m="3247950">at
  k,</span> <span m="3248280">which</span> <span m="3249650">in</span> <span m="3249810">the</span>
  <span m="3249900">Burgers</span> <span m="3250270">equation</span> <span m="3250910">is</span>
  <span m="3251430">just</span> <span m="3253160">u bar</span> <span m="3254010">of</span>
  <span m="3254190">k</span> <span m="3254970">squared</span> <span m="3255340">over</span>
  <span m="3255590">2.</span> <span m="3257890">If</span> <span m="3260830">the</span>
  <span m="3260980">minus</span> <span m="3261330">direction</span> <span m="3262320">is</span>
  <span m="3262550">the upwind</span> <span m="3263035">direction,</span> <span m="3267885">I''m</span>
  <span m="3268380">here</span> <span m="3269040">again</span> <span m="3269300">at--</span>
  <span m="3270810">I''m</span> <span m="3270950">going</span> <span m="3271080">to</span>
  <span m="3271160">draw</span> <span m="3272880">the</span> <span m="3272970">same</span>
  <span m="3273480">cells</span> <span m="3273830">again.</span> <span m="3275480">So
  k</span> <span m="3275830">minus</span> <span m="3276190">1,</span> <span m="3276710">k,</span>
  <span m="3278100">plus</span> <span m="3278380">one.</span></p><p><span m="3279580">OK.</span>
  <span m="3280710">I</span> <span m="3280980">am</span> <span m="3281210">looking</span>
  <span m="3281760">at</span> <span m="3283460">k</span> <span m="3283750">plus</span>
  <span m="3284100">1/2,</span> <span m="3284530">which</span> <span m="3284730">is</span>
  <span m="3284860">the</span> <span m="3285010">interface</span> <span m="3285270">between</span>
  <span m="3285530">k and</span> <span m="3286007">k plus 1.</span> <span m="3288869">I
  am going</span> <span m="3289350">to</span> <span m="3289710">use</span> <span m="3290396">the</span>
  <span m="3290740">average</span> <span m="3291040">method</span> <span m="3291560">of</span>
  <span m="3292052">k</span> <span m="3292544">to approximate</span> <span m="3293036">here.</span>
  <span m="3294512">If</span> <span m="3295004">k</span> <span m="3295500">is</span>
  <span m="3295780">the upwind</span> <span m="3296236">direction</span> <span m="3297148">of</span>
  <span m="3297604">the cell,</span> <span m="3300800">which</span> <span m="3301060">means</span>
  <span m="3301400">if</span> <span m="3301670">the</span> <span m="3301770">wind</span>
  <span m="3302260">travels</span> <span m="3302760">towards</span> <span m="3303090">the</span>
  <span m="3303210">right,</span> <span m="3306740">if</span> <span m="3307000">locally</span>
  <span m="3307780">u</span> <span m="3308130">is</span> <span m="3308340">greater</span>
  <span m="3308690">than</span> <span m="3308920">zero.</span> <span m="3313300">And</span>
  <span m="3313910">here</span> <span m="3315200">locally--</span> <span m="3317220">I</span>
  <span m="3317390">can</span> <span m="3317700">say</span> <span m="3317880">locally</span>
  <span m="3318390">u</span> <span m="3318810">is</span> <span m="3319230">greater</span>
  <span m="3319650">than</span> <span m="3320070">zero</span> <span m="3320490">if</span>
  <span m="3321630">the</span> <span m="3321830">average</span> <span m="3325300">between</span>
  <span m="3325850">the</span> <span m="3325930">two cells</span> <span m="3326660">is</span>
  <span m="3326820">greater</span> <span m="3327190">than</span> <span m="3327450">zero.</span>
  <span m="3329480">And</span> <span m="3330850">else,</span> <span m="3331870">I''m</span>
  <span m="3332090">going</span> <span m="3332300">to</span> <span m="3333190">approximate</span>
  <span m="3334090">it</span> <span m="3334400">using</span> <span m="3335370">the</span>
  <span m="3335670">upwind</span> <span m="3336130">direction,</span> <span m="3336850">which</span>
  <span m="3336960">is</span> <span m="3337130">now</span> <span m="3337430">towards</span>
  <span m="3337710">the</span> <span m="3337830">right.</span> <span m="3340220">It</span>
  <span m="3340720">is</span> <span m="3341220">this.</span></p><p><span m="3345220">Does
  it</span> <span m="3345720">make</span> <span m="3346000">any</span> <span m="3346150">sense?</span>
  <span m="3347720">This</span> <span m="3347920">is</span> <span m="3348070">what</span>
  <span m="3349150">I''m</span> <span m="3349270">going</span> <span m="3349450">to</span>
  <span m="3349560">write</span> <span m="3349820">in</span> <span m="3349910">the</span>
  <span m="3350020">code.</span> <span m="3352130">OK.</span> <span m="3352670">This</span>
  <span m="3352770">is</span> <span m="3352880">what</span> <span m="3353940">I''m</span>
  <span m="3354110">going</span> <span m="3354290">to</span> <span m="3354390">implement</span>
  <span m="3356230">in</span> <span m="3356360">my</span> <span m="3357010">code.</span>
  <span m="3357320">That</span> <span m="3357740">is,</span> <span m="3358160">in</span>
  <span m="3358580">the</span> <span m="3359000">[INAUDIBLE]</span> <span m="3359420">code</span>
  <span m="3359690">[INAUDIBLE].</span> <span m="3363162">The</span> <span m="3363658">F</span>
  <span m="3364154">at</span> <span m="3364650">interface</span> <span m="3366640">is</span>
  <span m="3366830">either</span> <span m="3367300">the</span> <span m="3367490">flux</span>
  <span m="3367896">at the</span> <span m="3368302">left value</span> <span m="3368710">or
  the</span> <span m="3369060">right</span> <span m="3369413">value</span> <span m="3370120">where</span>
  <span m="3370420">[? it is ?].</span> <span m="3375530">Any</span> <span m="3375690">questions
  on this?</span> <span m="3381020">No?</span> <span m="3381250">OK.</span></p><p><span
  m="3382610">Let''s</span> <span m="3383890">do</span> <span m="3384050">it</span>
  <span m="3384508">then.</span> <span m="3386800">What</span> <span m="3387010">I''m</span>
  <span m="3387160">going</span> <span m="3387320">to</span> <span m="3387380">do</span>
  <span m="3387660">is</span> <span m="3388350">I''m</span> <span m="3388520">going</span>
  <span m="3388710">to</span> <span m="3389440">pull</span> <span m="3389730">up</span>
  <span m="3389940">a</span> <span m="3390400">skeleton.</span> <span m="3391480">And</span>
  <span m="3391790">I''m</span> <span m="3391970">going</span> <span m="3392180">to</span>
  <span m="3392550">ask</span> <span m="3392840">you</span> <span m="3393930">to</span>
  <span m="3394470">fill</span> <span m="3394710">in</span> <span m="3394830">the</span>
  <span m="3394900">blanks.</span> <span m="3396830">So</span> <span m="3397210">I''m</span>
  <span m="3397490">going</span> <span m="3397720">to</span> <span m="3397840">go</span>
  <span m="3398120">to</span> <span m="3398240">the</span> <span m="3398390">shared</span>
  <span m="3398870">border.</span> <span m="3400010">Open</span> <span m="3400290">your</span>
  <span m="3400460">computers</span> <span m="3401050">if</span> <span m="3401190">you</span>
  <span m="3401310">haven''t.</span> <span m="3403056">I''m</span> <span m="3403510">going</span>
  <span m="3403800">to</span> <span m="3404510">create</span> <span m="3404915">an</span>
  <span m="3405560">order</span> <span m="3407260">2014.</span> <span m="3409639">Today
  is</span> <span m="3410122">the</span> <span m="3410605">10th,</span> <span m="3411090">right?</span></p><p><span
  m="3414802">OK.</span> <span m="3415270">I''m</span> <span m="3415430">going</span>
  <span m="3415570">to</span> <span m="3415660">start</span> <span m="3415950">from</span>
  <span m="3416210">scratch.</span> <span m="3419360">I''m</span> <span m="3419390">going</span>
  <span m="3419540">to</span> <span m="3419630">make</span> <span m="3419870">a</span>
  <span m="3420000">function</span> <span m="3421710">just</span> <span m="3422010">called</span>
  <span m="3422270">the</span> <span m="3422440">du dt</span> <span m="3422970">Burgers.</span>
  <span m="3425260">OK.</span> <span m="3426250">And</span> <span m="3426940">like</span>
  <span m="3427717">our--</span> <span m="3429560">so</span> <span m="3429740">we''re</span>
  <span m="3429940">assuming</span> <span m="3430140">PDEs.</span> <span m="3431400">But</span>
  <span m="3431630">as</span> <span m="3431900">long</span> <span m="3432130">as</span>
  <span m="3432310">we</span> <span m="3432410">can</span> <span m="3432570">convert</span>
  <span m="3433280">the</span> <span m="3433450">PDEs</span> <span m="3433710">into</span>
  <span m="3433960">a set</span> <span m="3434450">of</span> <span m="3434560">ODEs,</span>
  <span m="3434730">we</span> <span m="3434970">know</span> <span m="3435360">how</span>
  <span m="3435570">to</span> <span m="3435800">integrate</span> <span m="3436560">it</span>
  <span m="3436990">at</span> <span m="3437130">this</span> <span m="3437310">point.</span>
  <span m="3438670">I''m</span> <span m="3438810">sure</span> <span m="3439080">you</span>
  <span m="3439200">guys</span> <span m="3439480">all</span> <span m="3439600">can.</span></p><p><span
  m="3443470">So</span> <span m="3443660">what</span> <span m="3443920">is</span>
  <span m="3444150">it</span> <span m="3444630">going</span> <span m="3444820">to</span>
  <span m="3444910">be?</span> <span m="3445050">The</span> <span m="3445220">input</span>
  <span m="3445660">is</span> <span m="3445970">the</span> <span m="3446080">u bars.</span>
  <span m="3447910">And</span> <span m="3448230">the output</span> <span m="3448650">is</span>
  <span m="3448870">d</span> <span m="3449270">u</span> <span m="3449670">bar</span>
  <span m="3450360">dt.</span> <span m="3455470">And</span> <span m="3455680">what</span>
  <span m="3455840">I</span> <span m="3455900">need</span> <span m="3456080">to</span>
  <span m="3456260">do</span> <span m="3456730">is</span> <span m="3457120">I</span>
  <span m="3457200">need</span> <span m="3457370">to</span> <span m="3457910">compute</span>
  <span m="3459290">from</span> <span m="3459640">the</span> <span m="3459710">u bars</span>
  <span m="3461500">the</span> <span m="3461660">du</span> <span m="3461820">bar</span>
  <span m="3461960">dt.</span> <span m="3466230">So</span> <span m="3466390">what</span>
  <span m="3466600">do I</span> <span m="3466710">do</span> <span m="3466880">first?</span>
  <span m="3470240">I''m</span> <span m="3470490">first</span> <span m="3470750">going</span>
  <span m="3470910">to</span> <span m="3471060">do</span> <span m="3471500">F bar</span>
  <span m="3473420">is</span> <span m="3473640">equal</span> <span m="3474000">to</span>
  <span m="3474210">u</span> <span m="3474570">bar</span> <span m="3475730">squared</span>
  <span m="3475840">over</span> <span m="3476130">two.</span> <span m="3477150">What</span>
  <span m="3477340">am</span> <span m="3477490">I</span> <span m="3477570">doing</span>
  <span m="3477920">here?</span></p><p><span m="3483760">AUDIENCE: [INAUDIBLE].</span></p><p><span
  m="3486360">QIQI WANG: Computing</span> <span m="3486820">the</span> <span m="3487280">flux.</span>
  <span m="3487740">This</span> <span m="3488240">is</span> <span m="3488940">the</span>
  <span m="3489340">only</span> <span m="3489950">thing</span> <span m="3490180">I</span>
  <span m="3490240">need to</span> <span m="3490350">change</span> <span m="3491930">if</span>
  <span m="3492120">I</span> <span m="3492230">switch</span> <span m="3492720">from</span>
  <span m="3493090">the</span> <span m="3493180">Burgers</span> <span m="3493644">equation</span>
  <span m="3494108">to</span> <span m="3494572">some</span> <span m="3495036">other
  equation.</span> <span m="3497360">OK?</span> <span m="3498450">This is</span> <span
  m="3498930">really</span> <span m="3499460">defining</span> <span m="3500180">the</span>
  <span m="3500290">flux.</span> <span m="3500770">If</span> <span m="3500970">I</span>
  <span m="3501090">have</span> <span m="3501260">a</span> <span m="3501340">flux</span>
  <span m="3501740">that</span> <span m="3501920">is</span> <span m="3503170">equal</span>
  <span m="3503510">to</span> <span m="3503620">another</span> <span m="3503980">form,</span>
  <span m="3504820">this</span> <span m="3504980">is</span> <span m="3505980">what</span>
  <span m="3506150">I</span> <span m="3506210">need</span> <span m="3506370">to</span>
  <span m="3506460">change.</span> <span m="3508080">OK.</span> <span m="3509260">And</span>
  <span m="3509620">here,</span> <span m="3510230">I''m</span> <span m="3510420">going</span>
  <span m="3510590">to</span> <span m="3510680">have</span> <span m="3510860">you</span>
  <span m="3511090">fill in</span> <span m="3511290">the</span> <span m="3511380">blanks.</span>
  <span m="3515610">Compute</span> <span m="3516560">the</span> <span m="3517110">flux</span>
  <span m="3517600">at</span> <span m="3518053">cell</span> <span m="3518960">interfaces.</span>
  <span m="3522340">So</span> <span m="3522520">I</span> <span m="3522610">need</span>
  <span m="3522760">to</span> <span m="3522880">compute</span> <span m="3523345">F.</span>
  <span m="3527530">Let</span> <span m="3528070">me</span> <span m="3528150">call</span>
  <span m="3528400">this</span> <span m="3528860">F</span> <span m="3529130">of</span>
  <span m="3529270">[INAUDIBLE]</span> <span m="3529640">k.</span> <span m="3530700">So</span>
  <span m="3530900">this</span> <span m="3531260">is</span> <span m="3531520">F</span>
  <span m="3531960">at</span> <span m="3532640">k</span> <span m="3533978">plus</span>
  <span m="3535320">1/2</span> <span m="3536500">equal</span> <span m="3536950">to</span>
  <span m="3537330">blah,</span> <span m="3537570">blah,</span> <span m="3537890">blah.</span>
  <span m="3538440">This</span> <span m="3538600">is</span> <span m="3539200">what</span>
  <span m="3539410">you</span> <span m="3539490">need</span> <span m="3539660">to</span>
  <span m="3539780">do.</span> <span m="3540460">OK?</span></p><p><span m="3543670">And</span>
  <span m="3544180">then</span> <span m="3544940">what</span> <span m="3545200">I''m</span>
  <span m="3545340">going</span> <span m="3545540">to</span> <span m="3545950">write</span>
  <span m="3546290">down</span> <span m="3546760">is</span> <span m="3547650">this</span>
  <span m="3547970">is</span> <span m="3548200">the</span> <span m="3548300">finite</span>
  <span m="3548630">volume</span> <span m="3548710">method.</span> <span m="3549860">This</span>
  <span m="3551320">is</span> <span m="3551740">the</span> <span m="3551880">same</span>
  <span m="3552430">for</span> <span m="3552770">all</span> <span m="3553250">finite</span>
  <span m="3553770">volume</span> <span m="3554010">methods.</span> <span m="3559600">What</span>
  <span m="3559830">is</span> <span m="3560010">it?</span> <span m="3561580">It</span>
  <span m="3561720">is</span> <span m="3562150">the</span> <span m="3562410">d</span>
  <span m="3562670">u</span> <span m="3562950">bar</span> <span m="3563940">dt</span>
  <span m="3565680">equal</span> <span m="3566136">to--</span> <span m="3567050">according</span>
  <span m="3567550">to</span> <span m="3567730">our</span> <span m="3568010">formula--</span>
  <span m="3569840">du</span> <span m="3570250">bar</span> <span m="3570680">dt</span>
  <span m="3572130">is</span> <span m="3572350">equal to</span> <span m="3572450">one</span>
  <span m="3573020">over</span> <span m="3573200">delta</span> <span m="3573500">x</span>
  <span m="3574722">times</span> <span m="3575218">the</span> <span m="3575714">F,</span>
  <span m="3578200">the</span> <span m="3578440">flux,</span> <span m="3579213">at</span>
  <span m="3579636">the</span> <span m="3580060">right boundary</span> <span m="3580350">of</span>
  <span m="3580520">k,</span> <span m="3580998">which is</span> <span m="3581476">k
  plus</span> <span m="3581954">1/2,</span> <span m="3583388">minus</span> <span m="3583866">the</span>
  <span m="3584344">F at</span> <span m="3584822">the</span> <span m="3585300">left</span>
  <span m="3585710">boundary</span> <span m="3586193">of k,</span> <span m="3586676">which</span>
  <span m="3587159">is</span> <span m="3587642">F</span> <span m="3588125">of</span>
  <span m="3588608">k</span> <span m="3589091">minus 1/2.</span> <span m="3590540">Right?</span></p><p><span
  m="3595260">So</span> <span m="3595500">this</span> <span m="3595730">is</span>
  <span m="3596300">F</span> <span m="3597190">k</span> <span m="3597990">plus</span>
  <span m="3599370">1/2</span> <span m="3599980">minus</span> <span m="3600490">F</span>
  <span m="3601030">k</span> <span m="3601500">minus</span> <span m="3602610">1/2</span>
  <span m="3603620">divided</span> <span m="3604060">by</span> <span m="3604870">delta</span>
  <span m="3605010">x.</span> <span m="3606950">And</span> <span m="3607230">I</span>
  <span m="3607320">need</span> <span m="3607520">to</span> <span m="3607580">compute</span>
  <span m="3607850">F</span> <span m="3608100">of</span> <span m="3608700">k</span>
  <span m="3609390">minus</span> <span m="3610420">1/2.</span> <span m="3611520">It''s</span>
  <span m="3611850">basically</span> <span m="3612630">a</span> <span m="3613063">[INAUDIBLE]</span>
  <span m="3613496">of</span> <span m="3613930">F</span> <span m="3614110">k plus</span>
  <span m="3614390">1/2.</span> <span m="3616570">Let''s</span> <span m="3617010">assume</span>
  <span m="3617100">they</span> <span m="3617400">are</span> <span m="3617490">periodic</span>
  <span m="3617810">boundaries</span> <span m="3618130">for</span> <span m="3618320">now.</span>
  <span m="3618980">So</span> <span m="3619170">how</span> <span m="3619440">should</span>
  <span m="3619640">I</span> <span m="3619670">compute</span> <span m="3619950">F</span>
  <span m="3620230">of</span> <span m="3620590">k</span> <span m="3621220">minus</span>
  <span m="3621450">1/2</span> <span m="3621880">from</span> <span m="3622180">F</span>
  <span m="3622210">of</span> <span m="3622350">k</span> <span m="3622440">plus 1/2?</span></p><p><span
  m="3628480">I''m</span> <span m="3628630">going</span> <span m="3628760">to</span>
  <span m="3628820">use</span> <span m="3629150">circshift,</span> <span m="3630131">right?</span>
  <span m="3633980">And</span> <span m="3634050">which</span> <span m="3634310">direction</span>
  <span m="3634420">should I</span> <span m="3634880">shift it?</span> <span m="3642750">So</span>
  <span m="3643030">I</span> <span m="3643140">already</span> <span m="3643620">have</span>
  <span m="3644140">F</span> <span m="3645027">of</span> <span m="3646895">k--</span>
  <span m="3649697">I</span> <span m="3650170">already</span> <span m="3650570">have</span>
  <span m="3651030">F</span> <span m="3651490">of</span> <span m="3651950">k</span>
  <span m="3652410">plus</span> <span m="3652800">1/2</span> <span m="3653200">over
  here.</span> <span m="3653790">I need</span> <span m="3654190">to</span> <span m="3655498">have--</span>
  <span m="3656860">so</span> <span m="3657314">if I</span> <span m="3657770">already
  have</span> <span m="3657910">F of</span> <span m="3658320">k</span> <span m="3659180">up
  here, I</span> <span m="3659630">need</span> <span m="3659880">to</span> <span m="3660285">shift
  it</span> <span m="3661500">towards</span> <span m="3661630">the</span> <span m="3662040">right</span>
  <span m="3662540">to</span> <span m="3663040">get--</span> <span m="3663815">so</span>
  <span m="3664260">that''s</span> <span m="3664370">the same point I have,</span>
  <span m="3664870">F of</span> <span m="3665370">k minus</span> <span m="3665870">1/2.</span></p><p><span
  m="3674250">So</span> <span m="3674650">we</span> <span m="3675000">assume--</span>
  <span m="3676120">let''s</span> <span m="3676340">assume</span> <span m="3676640">it''s</span>
  <span m="3676800">a</span> <span m="3676980">row</span> <span m="3677270">vector,</span>
  <span m="3677740">so</span> <span m="3677910">that</span> <span m="3678190">when</span>
  <span m="3678390">I</span> <span m="3678470">shift it,</span> <span m="3678970">I
  shift</span> <span m="3679429">it to</span> <span m="3679888">0</span> <span m="3680347">and
  1.</span> <span m="3680806">OK.</span> <span m="3683560">And</span> <span m="3685570">let''s</span>
  <span m="3685980">assume</span> <span m="3687970">my</span> <span m="3688210">boundary</span>
  <span m="3688660">goes</span> <span m="3688950">from</span> <span m="3689210">0</span>
  <span m="3689350">to</span> <span m="3689560">1.</span> <span m="3690306">OK.</span>
  <span m="3691750">So</span> <span m="3691960">if</span> <span m="3692180">I</span>
  <span m="3692420">have</span> <span m="3692820">a</span> <span m="3693090">boundary
  that</span> <span m="3693360">goes</span> <span m="3693730">from</span> <span m="3694250">0</span>
  <span m="3694590">to 1,</span> <span m="3694890">my delta</span> <span m="3695150">x</span>
  <span m="3695460">is</span> <span m="3695780">equal</span> <span m="3696160">to</span>
  <span m="3696310">the</span> <span m="3696530">length</span> <span m="3696900">of</span>
  <span m="3697020">the</span> <span m="3697110">domain</span> <span m="3697780">divided</span>
  <span m="3698230">by</span> <span m="3699210">the</span> <span m="3699310">length</span>
  <span m="3699730">of</span> <span m="3700480">u</span> <span m="3700600">bar,</span>
  <span m="3701300">how</span> <span m="3701410">many</span> <span m="3701860">control</span>
  <span m="3702360">volumes</span> <span m="3702910">I</span> <span m="3703090">have.</span>
  <span m="3704470">So</span> <span m="3704610">that''s</span> <span m="3704830">my</span>
  <span m="3705010">delta</span> <span m="3705300">x.</span></p><p><span m="3706280">The</span>
  <span m="3706370">size</span> <span m="3706670">of</span> <span m="3706850">each</span>
  <span m="3707040">control</span> <span m="3707330">volume?</span> <span m="3708430">I</span>
  <span m="3708590">have</span> <span m="3708870">F</span> <span m="3709070">of</span>
  <span m="3709220">k plus</span> <span m="3709673">1/2,</span> <span m="3710126">F
  of</span> <span m="3710580">k</span> <span m="3710710">minus</span> <span m="3711050">1/2.</span>
  <span m="3711430">Then</span> <span m="3711710">I</span> <span m="3711800">get</span>
  <span m="3713660">the du</span> <span m="3713860">bar</span> <span m="3713970">dt.</span>
  <span m="3716290">OK.</span> <span m="3716900">Go</span> <span m="3717170">ahead</span>
  <span m="3717470">and</span> <span m="3718920">just</span> <span m="3719910">copy</span>
  <span m="3721240">what</span> <span m="3721540">I</span> <span m="3721810">wrote</span>
  <span m="3722110">here.</span> <span m="3723150">Just</span> <span m="3723440">rename</span>
  <span m="3723930">it</span> <span m="3724080">to</span> <span m="3724200">whatever.</span>
  <span m="3725930">Just</span> <span m="3726230">rename</span> <span m="3726630">it</span>
  <span m="3726790">to</span> <span m="3727310">dudtBurgers</span> <span m="3728750">underscore</span>
  <span m="3729160">your</span> <span m="3729660">name.</span> <span m="3731292">You
  can</span> <span m="3731700">do it in</span> <span m="3731960">the</span> <span
  m="3732060">same</span> <span m="3732280">directory.</span> <span m="3736330">And
  tell me what</span> <span m="3736440">you get.</span></p><p><span m="3737210">All</span>
  <span m="3737690">right.</span> <span m="3737940">Anybody</span> <span m="3738370">have</span>
  <span m="3738640">anything</span> <span m="3739142">I</span> <span m="3739524">did</span>
  <span m="3740290">wrong?</span> <span m="3740640">I just</span> <span m="3741100">wrote</span>
  <span m="3741380">a</span> <span m="3741480">script.</span> <span m="3743920">So</span>
  <span m="3744110">it''s</span> <span m="3744570">writing</span> <span m="3745820">[INAUDIBLE].</span>
  <span m="3751440">So this</span> <span m="3751939">is</span> <span m="3752438">basically</span>
  <span m="3752937">making</span> <span m="3753436">[INAUDIBLE].</span> <span m="3758426">OK.</span>
  <span m="3760422">And</span> <span m="3760921">using</span> <span m="3761420">all
  the</span> <span m="3761919">input</span> <span m="3762418">[INAUDIBLE].</span>
  <span m="3765888">So</span> <span m="3766377">[INAUDIBLE].</span> <span m="3778602">All
  right?</span> <span m="3779091">So I''m</span> <span m="3779580">[INAUDIBLE].</span></p><p><span
  m="3796394">AUDIENCE: [INAUDIBLE].</span></p><p><span m="3806360">QIQI WANG: OK.</span>
  <span m="3808640">You can</span> <span m="3809114">try.</span> <span m="3811960">All
  right.</span></p><p><span m="3814325">AUDIENCE: [INAUDIBLE].</span></p><p><span
  m="3816220">QIQI WANG: OK.</span></p><p><span m="3821160">AUDIENCE: [INAUDIBLE].</span>
  <span m="3826740">The function</span> <span m="3827220">in--</span></p><p><span
  m="3827700">QIQI WANG: Oh. Oh. OK.</span> <span m="3832674">Oops.</span> <span m="3834658">I</span>
  <span m="3835160">added</span> <span m="3835510">just--</span></p><p><span m="3839136">AUDIENCE:
  [INAUDIBLE].</span></p><p><span m="3841480">QIQI WANG: OK.</span> <span m="3841860">So</span>
  <span m="3842240">this</span> <span m="3842570">is--</span> <span m="3847350">let''s
  see.</span> <span m="3848096">[INAUDIBLE].</span> <span m="3850576">So  I</span>
  <span m="3851072">goes</span> <span m="3851568">from</span> <span m="3852064">one</span>
  <span m="3852560">to the</span> <span m="3853060">length</span> <span m="3853560">of</span>
  <span m="3854060">u bar</span> <span m="3854560">minus 1.</span> <span m="3856560">If</span>
  <span m="3857060">u bar</span> <span m="3857560">is</span> <span m="3858030">[INAUDIBLE].</span>
  <span m="3864710">You</span> <span m="3865205">also put</span> <span m="3865700">I</span>
  <span m="3865920">here.</span></p><p><span m="3866648">AUDIENCE: [INAUDIBLE].</span></p><p><span
  m="3868790">QIQI WANG: OK.</span></p><p><span m="3869730">AUDIENCE: It''s be a</span>
  <span m="3870200">good idea.</span></p><p><span m="3870670">QIQI WANG: Yeah.</span>
  <span m="3873730">I</span> <span m="3873760">think</span> <span m="3874010">I</span>
  <span m="3874440">need</span> <span m="3874610">to</span> <span m="3874730">close</span>
  <span m="3875090">this</span> <span m="3875260">so</span> <span m="3875370">that</span>
  <span m="3875560">I</span> <span m="3875590">don''t</span> <span m="3875830">get</span>
  <span m="3875970">a</span> <span m="3876450">[INAUDIBLE].</span> <span m="3878150">OK.</span>
  <span m="3878590">It''s</span> <span m="3878920">updated.</span> <span m="3883620">OK.</span>
  <span m="3885130">Let''s</span> <span m="3885410">run the</span> <span m="3885780">script</span>
  <span m="3886250">again.</span> <span m="3887135">The</span> <span m="3887510">driver.</span>
  <span m="3889920">Run.</span> <span m="3902730">Ah.</span> <span m="3905250">OK.</span>
  <span m="3905708">This is--</span></p><p><span m="3906166">[INTERPOSING VOICES]</span></p><p><span
  m="3909830">QIQI WANG: OK.</span> <span m="3910290">Update</span> <span m="3910440">it</span>
  <span m="3910660">again.</span></p><p><span m="3912297">AUDIENCE: [INAUDIBLE].</span></p><p><span
  m="3915291">[INTERPOSING VOICES]</span></p><p>&nbsp;</p><p><span m="3926280">QIQI
  WANG: Oh,</span> <span m="3926600">you</span> <span m="3926800">must--</span> <span
  m="3928720">OK.</span> <span m="3929060">So</span> <span m="3929270">that''s</span>
  <span m="3929480">my</span> <span m="3929630">problem.</span> <span m="3930170">I</span>
  <span m="3930320">need</span> <span m="3930530">to</span> <span m="3930610">change</span>
  <span m="3931110">it</span> <span m="3931270">so</span> <span m="3931410">that</span>
  <span m="3931850">I</span> <span m="3932290">[? deleted ?]</span> <span m="3932600">a</span>
  <span m="3932930">column</span> <span m="3933400">vector.</span> <span m="3937080">Let</span>
  <span m="3937260">me</span> <span m="3937430">[? delete ?]</span> <span m="3937730">a</span>
  <span m="3938030">column</span> <span m="3938260">vector</span> <span m="3938350">and</span>
  <span m="3938828">[INAUDIBLE]</span> <span m="3939306">a</span> <span m="3939784">column</span>
  <span m="3940262">vector.</span> <span m="3941220">OK.</span> <span m="3941610">Now</span>
  <span m="3941850">let''s see.</span> <span m="3947808">Ah.</span> <span m="3948290">You''re
  returning</span> <span m="3948640">a</span> <span m="3949000">vector</span> <span
  m="3949140">of</span> <span m="3949370">length</span> <span m="3950280">63.</span>
  <span m="3952090">But</span> <span m="3952280">the</span> <span m="3952370">length</span>
  <span m="3952830">I</span> <span m="3952950">should</span> <span m="3953040">get</span>
  <span m="3953300">is</span> <span m="3953450">64.</span></p><p><span m="3955796">AUDIENCE:
  Oh, right.</span> <span m="3956288">So</span> <span m="3956780">it''s</span> <span
  m="3957272">returning</span> <span m="3957764">[INAUDIBLE].</span></p><p>&nbsp;</p><p><span
  m="3973016">QIQI WANG: Ah.</span> <span m="3974500">We are</span> <span m="3974940">assuming</span>
  <span m="3975430">the</span> <span m="3975710">domain</span> <span m="3975980">is</span>
  <span m="3976250">periodic.</span> <span m="3977510">So</span> <span m="3977970">at</span>
  <span m="3978730">the</span> <span m="3980940">last</span> <span m="3981230">control</span>
  <span m="3981580">volume,</span> <span m="3983280">if</span> <span m="3983510">we</span>
  <span m="3983590">need</span> <span m="3983740">to</span> <span m="3983830">take</span>
  <span m="3984940">towards</span> <span m="3985180">the</span> <span m="3985320">right,</span>
  <span m="3985740">we should</span> <span m="3986020">be</span> <span m="3986140">taking</span>
  <span m="3986460">the</span> <span m="3986550">first</span> <span m="3986850">value.</span>
  <span m="3988610">Right?</span> <span m="3990940">OK.</span> <span m="3991250">Let</span>
  <span m="3991470">me</span> <span m="3991600">see,</span> <span m="3991790">I</span>
  <span m="3991920">see</span> <span m="3993122">to</span> <span m="3993570">[? copy
  ?]</span> <span m="3999780">the network,</span> <span m="4001290">oh.</span></p><p><span
  m="4004110">AUDIENCE: [INAUDIBLE].</span></p><p><span m="4005610">QIQI WANG: Into</span>
  <span m="4005910">the</span> <span m="4006030">[INAUDIBLE]</span> <span m="4006530">[?
  space ?].</span> <span m="4014450">Let</span> <span m="4014640">me</span> <span
  m="4014750">see.</span> <span m="4037354">Hm.</span> <span m="4039820">OK.</span>
  <span m="4040300">For</span> <span m="4040410">the</span> <span m="4040540">last</span>
  <span m="4040790">cell,</span> <span m="4043284">here</span> <span m="4043765">I</span>
  <span m="4044246">think</span> <span m="4044727">I</span> <span m="4045689">[INAUDIBLE]</span>
  <span m="4051541">from</span> <span m="4052020">the</span> <span m="4052310">[INAUDIBLE],</span>
  <span m="4052793">I think</span> <span m="4053276">that</span> <span m="4053759">will</span>
  <span m="4054242">end</span> <span m="4056660">after--</span> <span m="4058010">so
  let</span> <span m="4058220">me see.</span> <span m="4059400">For</span> <span m="4059610">r</span>
  <span m="4059760">equals</span> <span m="4060236">from 1 to</span> <span m="4060712">10,</span>
  <span m="4061188">i n.</span> <span m="4062140">Yet,</span> <span m="4062850">if</span>
  <span m="4063060">I</span> <span m="4063170">do</span> <span m="4063420">i</span>
  <span m="4063590">again,</span> <span m="4064060">it</span> <span m="4064160">is</span>
  <span m="4064250">still 10.</span> <span m="4064728">It is</span> <span m="4065206">not
  11.</span></p><p><span m="4066162">AUDIENCE: [INAUDIBLE].</span></p><p><span m="4068560">QIQI
  WANG: Yes.</span></p><p><span m="4069828">AUDIENCE: [INAUDIBLE].</span></p><p><span
  m="4076750">QIQI WANG: OK.</span> <span m="4077160">[INAUDIBLE]</span> <span m="4077636">update.</span>
  <span m="4079064">[INAUDIBLE]</span> <span m="4079540">update.</span> <span m="4082400">OK.</span>
  <span m="4082620">Let</span> <span m="4082930">me</span> <span m="4083430">do this</span>
  <span m="4083930">again.</span> <span m="4089660">Oh.</span> <span m="4090360">I</span>
  <span m="4090450">need</span> <span m="4090700">a</span> <span m="4090770">minus</span>
  <span m="4091230">sign</span> <span m="4091530">here.</span> <span m="4092810">Right?</span></p><p><span
  m="4093245">[LAUGHTER]</span></p><p><span m="4094990">Is</span> <span m="4095170">that</span>
  <span m="4095340">right?</span> <span m="4097330">OK.</span> <span m="4097760">I</span>
  <span m="4097880">need</span> <span m="4098060">a</span> <span m="4098109">minus</span>
  <span m="4098520">sign</span> <span m="4098779">in</span> <span m="4098950">my--</span>
  <span m="4099779">OK.</span> <span m="4100080">I</span> <span m="4100170">need</span>
  <span m="4100310">a</span> <span m="4100380">minus</span> <span m="4100640">sign</span>
  <span m="4100996">in my</span> <span m="4101352">script</span> <span m="4101710">because--</span></p><p><span
  m="4102140">AUDIENCE: Yeah.</span></p><p><span m="4103427">QIQI WANG: Right?</span>
  <span m="4103859">Is</span> <span m="4103970">that</span> <span m="4104200">right?</span>
  <span m="4104930">Let</span> <span m="4105109">me</span> <span m="4105200">see.</span>
  <span m="4106300">So</span> <span m="4107540">it</span> <span m="4107620">is</span>
  <span m="4107779">equal</span> <span m="4108270">to</span> <span m="4110603">the</span>
  <span m="4111040">right</span> <span m="4111399">value</span> <span m="4111809">minus</span>
  <span m="4112219">the</span> <span m="4112629">left</span> <span m="4113039">one,</span>
  <span m="4113450">which</span> <span m="4113670">I</span> <span m="4113990">may
  be--</span></p><p><span m="4118340">AUDIENCE: Yes,</span> <span m="4118620">it</span>
  <span m="4119003">would</span> <span m="4119386">be--</span></p><p><span m="4119770">QIQI
  WANG:</span> <span m="4120120">Should</span> <span m="4120250">have</span> <span
  m="4120649">been</span> <span m="4121000">the</span> <span m="4121220">left</span>
  <span m="4121649">value</span> <span m="4122029">minus</span> <span m="4122600">the</span>
  <span m="4122840">right</span> <span m="4123319">one.</span> <span m="4123760">Sorry.</span>
  <span m="4124630">I</span> <span m="4124760">have</span> <span m="4124890">been</span>
  <span m="4125090">deriving</span> <span m="4125620">it</span> <span m="4125970">incorrectly.</span>
  <span m="4127380">So</span> <span m="4127550">yes.</span> <span m="4130069">So</span>
  <span m="4130630">for</span> <span m="4130890">the</span> <span m="4131689">time</span>
  <span m="4131939">derivative</span> <span m="4132149">of</span> <span m="4132619">the</span>
  <span m="4133090">average</span> <span m="4133349">is</span> <span m="4133609">equal</span>
  <span m="4134036">to</span> <span m="4134890">what</span> <span m="4135240">comes</span>
  <span m="4135729">in from</span> <span m="4136100">the</span> <span m="4136270">left</span>
  <span m="4136729">minus</span> <span m="4137210">what</span> <span m="4137529">goes</span>
  <span m="4137840">out</span> <span m="4138260">from</span> <span m="4138510">the</span>
  <span m="4138640">right.</span> <span m="4139950">So</span> <span m="4140170">I</span>
  <span m="4140350">need</span> <span m="4140850">a--</span> <span m="4141560">yes,</span>
  <span m="4142000">I</span> <span m="4142149">need</span> <span m="4142330">a</span>
  <span m="4142410">minus.</span> <span m="4143029">So</span> <span m="4143250">don''t</span>
  <span m="4143590">change</span> <span m="4143890">your</span> <span m="4144000">code.</span>
  <span m="4145000">I</span> <span m="4145140">just</span> <span m="4145880">put</span>
  <span m="4146040">a</span> <span m="4146210">minus sign</span> <span m="4146750">here.</span></p><p><span
  m="4147590">All</span> <span m="4147870">right.</span> <span m="4148540">Now</span>
  <span m="4148850">it looks</span> <span m="4149160">like</span> <span m="4150620">it''s</span>
  <span m="4150910">behaving</span> <span m="4152582">a</span> <span m="4153040">little</span>
  <span m="4153460">bit</span> <span m="4153710">weirder</span> <span m="4154490">at</span>
  <span m="4154760">the</span> <span m="4154939">end.</span> <span m="4155510">Otherwise</span>
  <span m="4155979">it seems</span> <span m="4156470">to</span> <span m="4156609">be</span>
  <span m="4156750">working.</span></p><p><span m="4157642">AUDIENCE: [INAUDIBLE].</span></p><p><span
  m="4162572">QIQI WANG: Let me--</span> <span m="4163069">OK</span> <span m="4168149">Right.</span>
  <span m="4168460">So</span> <span m="4168569">we</span> <span m="4168689">do</span>
  <span m="4168950">see</span> <span m="4169160">a</span> <span m="4169270">shock
  wave</span> <span m="4169880">developing,</span> <span m="4170490">right?</span>
  <span m="4171649">So</span> <span m="4171899">let</span> <span m="4172569">me</span>
  <span m="4172700">change</span> <span m="4173149">the</span> <span m="4173524">delta
  t</span> <span m="4174140">to</span> <span m="4174250">be</span> <span m="4174390">a</span>
  <span m="4174470">little</span> <span m="4174800">smaller.</span> <span m="4177810">And</span>
  <span m="4178020">then</span> <span m="4178149">run it</span> <span m="4178569">again.</span>
  <span m="4181250">Ooh.</span> <span m="4182790">Right?</span> <span m="4183080">That''s</span>
  <span m="4183319">the</span> <span m="4183479">correct</span> <span m="4183700">behavior</span>
  <span m="4184170">of</span> <span m="4184340">the Burgers</span> <span m="4184790">equation.</span>
  <span m="4186359">Right?</span> <span m="4187870">OK.</span> <span m="4189170">Very</span>
  <span m="4189420">nice.</span></p><p><span m="4190310">So</span> <span m="4190479">who
  else--</span> <span m="4194149">I</span> <span m="4194210">think</span> <span m="4194530">the--</span>
  <span m="4196090">let''s</span> <span m="4196510">see.</span> <span m="4197342">Yeah.</span>
  <span m="4197760">OK.</span> <span m="4199210">Let</span> <span m="4199310">me</span>
  <span m="4199450">run it</span> <span m="4199750">again.</span> <span m="4203150">All</span>
  <span m="4203410">right.</span> <span m="4205960">Great.</span> <span m="4209320">That''s</span>
  <span m="4209560">great.</span> <span m="4210260">And</span> <span m="4211440">let</span>
  <span m="4211630">me</span> <span m="4211760">see</span> <span m="4212020">if</span>
  <span m="4212160">I</span> <span m="4212310">can</span> <span m="4212760">break</span>
  <span m="4213170">it</span> <span m="4213380">without</span> <span m="4214200">betraying</span>
  <span m="4214470">initial</span> <span m="4215090">conditions.</span> <span m="4217010">And</span>
  <span m="4217980">let</span> <span m="4218180">me</span> <span m="4218680">take</span>
  <span m="4218940">it</span> <span m="4219030">as</span> <span m="4219290">x</span>
  <span m="4219680">is</span> <span m="4219955">zero</span> <span m="4220230">equal</span>
  <span m="4220635">to</span> <span m="4221040">draw</span> <span m="4221475">periodic</span>
  <span m="4221910">function.</span> <span m="4225850">Do I have</span> <span m="4226325">that?</span>
  <span m="4227280">Oh no.</span> <span m="4227510">I</span> <span m="4227630">don''t</span>
  <span m="4227820">have</span> <span m="4228000">that</span> <span m="4228070">in</span>
  <span m="4229090">here.</span> <span m="4229340">So</span> <span m="4229550">I''m</span>
  <span m="4229780">just going</span> <span m="4230276">to copy it.</span></p><p><span
  m="4243668">AUDIENCE: [INAUDIBLE].</span></p><p><span m="4249124">QIQI WANG: Draw</span>
  <span m="4249620">periodic</span> <span m="4250116">function.</span></p><p><span
  m="4252252">AUDIENCE: [INAUDIBLE].</span></p><p><span m="4254188">[INTERPOSING VOICES]</span></p><p>&nbsp;</p><p><span
  m="4262430">[INTERPOSING VOICES]</span></p><p>&nbsp;</p><p><span m="4273680">QIQI
  WANG: Let me</span> <span m="4273980">do</span> <span m="4274474">that.</span> <span
  m="4283380">OK.</span> <span m="4283660">Let</span> <span m="4283800">me</span>
  <span m="4283960">do something.</span> <span m="4298750">Anyway,</span> <span m="4300510">OK.</span>
  <span m="4300850">So</span> <span m="4302160">I</span> <span m="4302270">see</span>
  <span m="4302300">a</span> <span m="4302330">lot</span> <span m="4302500">of</span>
  <span m="4302620">you are</span> <span m="4302850">doing</span> <span m="4303180">good</span>
  <span m="4303565">work.</span> <span m="4305680">Anybody</span> <span m="4306240">else?</span>
  <span m="4306920">I</span> <span m="4307070">can</span> <span m="4307350">try</span>
  <span m="4307710">your</span> <span m="4308160">solution.</span> <span m="4309780">OK.</span>
  <span m="4320250">Ah.</span></p><p><span m="4322390">[LAUGHTER]</span></p><p>&nbsp;</p><p><span
  m="4327200">OK.</span> <span m="4328770">I think</span> <span m="4329040">I''m going</span>
  <span m="4329320">over</span> <span m="4329600">time.</span> <span m="4329950">I</span>
  <span m="4330100">had</span> <span m="4330270">a</span> <span m="4330350">lot</span>
  <span m="4330540">of</span> <span m="4330670">fun</span> <span m="4330980">trying</span>
  <span m="4331150">your</span> <span m="4331520">scripts.</span> <span m="4332530">But</span>
  <span m="4333240">let''s</span> <span m="4333850">meet</span> <span m="4334400">on</span>
  <span m="4334670">Wednesday</span> <span m="4335250">and</span> <span m="4335760">talk</span>
  <span m="4335990">about</span> <span m="4336270">more</span> <span m="4336580">of
  the</span> <span m="4336840">finite</span> <span m="4337010">volume</span> <span
  m="4337270">method.</span> <span m="4339054">So</span> <span m="4340840">if</span>
  <span m="4341070">you</span> <span m="4341140">want</span> <span m="4341320">to</span>
  <span m="4341390">stay,</span> <span m="4341770">I''m</span> <span m="4341910">going</span>
  <span m="4342030">to</span> <span m="4342140">try</span> <span m="4342650">a</span>
  <span m="4342700">little</span> <span m="4342980">bit</span> <span m="4343540">more</span>
  <span m="4344040">of your</span> <span m="4344540">scripts.</span> <span m="4348040">[INAUDIBLE].</span>
  <span m="4356904">Oops.</span> <span m="4358380">OK.</span></p><p><span m="4360309">AUDIENCE:
  [INAUDIBLE].</span></p><p><span m="4367211">QIQI WANG: Oops.</span> <span m="4370190">All</span>
  <span m="4370420">right.</span> <span m="4373070">OK</span> <span m="4373405">.</span>
  <span m="4373740">Anyway</span> <span m="4374200">so</span> <span m="4374390">once</span>
  <span m="4374620">you</span> <span m="4374740">have</span> <span m="4374960">a</span>
  <span m="4375030">script,</span> <span m="4375440">you</span> <span m="4375500">can</span>
  <span m="4375660">always</span> <span m="4376390">try</span> <span m="4376570">my</span>
  <span m="4376760">driver</span> <span m="4377330">and</span> <span m="4377620">see</span>
  <span m="4377810">how</span> <span m="4378480">they</span> <span m="4378610">work.</span>
  <span m="4379900">All</span> <span m="4380030">right.</span> <span m="4381530">I''ll</span>
  <span m="4381740">see</span> <span m="4381850">you</span> <span m="4381920">on</span>
  <span m="4382020">Wednesday.</span> <span m="4383271">Yes.</span> <span m="4383690">If</span>
  <span m="4383980">you</span> <span m="4384090">didn''t</span> <span m="4384390">send</span>
  <span m="4384520">me</span> <span m="4384660">a</span> <span m="4384800">project</span>
  <span m="4385243">here,</span> <span m="4386130">please put it</span> <span m="4386410">over
  here.</span> <span m="4387904">And</span> <span m="4388402">the</span> <span m="4388900">homework</span>
  <span m="4389398">[INAUDIBLE]</span> <span m="4391390">with</span> <span m="4391690">the</span>
  <span m="4391990">homework.</span></p>'
type: course
uid: 3a8bbc2c8709aba5e65bf7332373e1c2

---
None