---
about_this_resource_text: <p><strong>Description:</strong> This session continues
  discussion of finite volume methods, and works through an example of upwinding using
  a traffic jam simulation.</p> <p><strong>Instructor:</strong> Qiqi Wang</p> <p>The
  recording quality of this video is the best available from the source.</p>
course_id: 16-90-computational-methods-in-aerospace-engineering-spring-2014
embedded_media:
- id: Video-YouTube-Stream
  media_location: _xOt_kiBPbE
  parent_uid: c794a1410431b1c1beee633b24e3abc9
  title: Video-YouTube-Stream
  type: Video
  uid: 0be7912a0401181babf6f7eb8c6ad63d
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/_xOt_kiBPbE/default.jpg
  parent_uid: c794a1410431b1c1beee633b24e3abc9
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: c93c0153cc3f611c2be31bd2a6d7e9ee
- id: 3Play-3PlayYouTubeid-MP4
  media_location: _xOt_kiBPbE
  parent_uid: c794a1410431b1c1beee633b24e3abc9
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 5e6c5a6890cbf2a6e54b13a18123e217
- id: xOtkiBPbE.srt
  parent_uid: c794a1410431b1c1beee633b24e3abc9
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-11-numerical-methods-of-pdes-finite-volume-methods-2/xOtkiBPbE.srt
  title: 3play caption file
  type: null
  uid: ecb61d28126abf066ca7842e99ce8f0c
- id: xOtkiBPbE.pdf
  parent_uid: c794a1410431b1c1beee633b24e3abc9
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-11-numerical-methods-of-pdes-finite-volume-methods-2/xOtkiBPbE.pdf
  title: 3play pdf file
  type: null
  uid: ca4bd1f2524419b212b04ceaa94c6ec2
- id: Caption-3Play YouTube id-SRT
  parent_uid: c794a1410431b1c1beee633b24e3abc9
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 7cc4c23ed5f4292fb685c87cfc169f17
- id: Transcript-3Play YouTube id-PDF
  parent_uid: c794a1410431b1c1beee633b24e3abc9
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 7581a675d7008b7f88a375c978c93dde
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT16.90S14/MIT16_90S14_L11_300k.mp4
  parent_uid: c794a1410431b1c1beee633b24e3abc9
  title: Video-Internet Archive-MP4
  type: Video
  uid: 29b441909ffaa7d86e1ff894c2561ca7
inline_embed_id: 91221100session11:numericalmethodsofpdes:finitevolumemethods278193979
layout: video
order_index: null
parent_uid: 809ebf7c44bfb36e8786306747d7e32f
related_resources_text: ''
short_url: session-11-numerical-methods-of-pdes-finite-volume-methods-2
technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-11-numerical-methods-of-pdes-finite-volume-methods-2
template_type: Tabbed
title: 'Session 11: Numerical Methods of PDEs: Finite Volume Methods 2'
transcript: '<p><span m="30">The</span> <span m="130">following</span> <span m="600">content</span>
  <span m="1090">is</span> <span m="1210">provided</span> <span m="1660">under</span>
  <span m="1900">a</span> <span m="1950">Creative</span> <span m="2400">Commons</span>
  <span m="2820">license.</span> <span m="3780">Your</span> <span m="3880">support</span>
  <span m="4400">will</span> <span m="4570">help</span> <span m="4790">MIT</span>
  <span m="5280">OpenCourseWare</span> <span m="6020">continue</span> <span m="6510">to</span>
  <span m="6680">offer</span> <span m="6980">high</span> <span m="7200">quality</span>
  <span m="7680">educational</span> <span m="8350">resources</span> <span m="8920">for</span>
  <span m="9040">free.</span> <span m="10100">To</span> <span m="10130">make</span>
  <span m="10330">a</span> <span m="10370">donation</span> <span m="11090">or</span>
  <span m="11310">to</span> <span m="11430">view</span> <span m="11640">additional</span>
  <span m="12050">materials</span> <span m="12670">from</span> <span m="12850">hundreds</span>
  <span m="13180">of</span> <span m="13280">MIT</span> <span m="13650">courses,</span>
  <span m="14950">visit</span> <span m="15150">MIT</span> <span m="15670">OpenCourseWare</span>
  <span m="16580">at</span> <span m="16770">osw.mit.edu.</span></p><p><span m="31710">QIQI
  WANG: So</span> <span m="31970">today,</span> <span m="32110">we''re</span> <span
  m="32229">going</span> <span m="32350">to</span> <span m="32409">be</span> <span
  m="32470">continuing</span> <span m="33320">finite</span> <span m="33510">volume.</span>
  <span m="35600">We</span> <span m="35890">started</span> <span m="36330">on</span>
  <span m="36460">finite volume</span> <span m="37920">on</span> <span m="38080">Monday.</span>
  <span m="38410">And</span> <span m="38850">just</span> <span m="39120">a</span>
  <span m="39210">very</span> <span m="39490">quick</span> <span m="39810">recap,</span>
  <span m="40460">finite volume</span> <span m="41010">doesn''t</span> <span m="41290">solve</span>
  <span m="41710">all</span> <span m="41940">the</span> <span m="42030">differential</span>
  <span m="42420">equations,</span> <span m="43630">but</span> <span m="43800">it</span>
  <span m="44100">solves</span> <span m="44820">a</span> <span m="44930">class</span>
  <span m="45320">of</span> <span m="45450">differential</span> <span m="45900">equations</span>
  <span m="46270">that</span> <span m="46540">we</span> <span m="46850">care</span>
  <span m="47210">most,</span> <span m="48330">that</span> <span m="48510">is</span>
  <span m="49320">conservation</span> <span m="49950">laws.</span> <span m="51420">Conservation
  laws</span> <span m="53440">are</span> <span m="54080">differential</span> <span
  m="54600">equations</span> <span m="55220">that</span> <span m="55430">can</span>
  <span m="55620">be</span> <span m="55800">returned</span> <span m="56550">in</span>
  <span m="56750">this</span> <span m="57030">form.</span></p><p><span m="57820">And</span>
  <span m="58300">today,</span> <span m="58680">I''m</span> <span m="58700">just</span>
  <span m="58860">going</span> <span m="58980">to</span> <span m="59050">be</span>
  <span m="59160">more</span> <span m="59450">specific.</span> <span m="60640">Let''s</span>
  <span m="60940">say,</span> <span m="61150">rho</span> <span m="62150">is</span>
  <span m="63420">the</span> <span m="63550">density</span> <span m="64140">of</span>
  <span m="64349">a</span> <span m="64440">conservative</span> <span m="65040">quantity.</span>
  <span m="67440">The</span> <span m="68650">time</span> <span m="68810">derivative</span>
  <span m="69470">of</span> <span m="69620">rho</span> <span m="71660">plus</span>
  <span m="72830">the</span> <span m="73040">divergence</span> <span m="74060">of
  a</span> <span m="74490">flux,</span> <span m="75470">which</span> <span m="75690">is</span>
  <span m="75790">a</span> <span m="75850">function</span> <span m="76200">of</span>
  <span m="76310">rho,</span> <span m="76830">is</span> <span m="77100">equal</span>
  <span m="77400">to</span> <span m="77750">0.</span> <span m="78530">So</span> <span
  m="79950">this</span> <span m="80360">is</span> <span m="80990">a</span> <span m="81160">general</span>
  <span m="81640">conservation</span> <span m="82250">law</span> <span m="82560">when</span>
  <span m="82870">there</span> <span m="83010">is</span> <span m="83150">no</span>
  <span m="83340">[INAUDIBLE],</span> <span m="84040">when</span> <span m="84300">there</span>
  <span m="84440">is</span> <span m="84570">no</span> <span m="84760">generation</span>
  <span m="85650">or</span> <span m="86450">it''s</span> <span m="86710">appearing</span>
  <span m="87390">off</span> <span m="88800">any</span> <span m="90290">material</span>
  <span m="90870">within</span> <span m="91210">the</span> <span m="91280">control</span>
  <span m="91575">volume.</span> <span m="92860">Everything</span> <span m="93460">that</span>
  <span m="93700">increases</span> <span m="94250">has</span> <span m="94520">to</span>
  <span m="94640">come</span> <span m="95040">from</span> <span m="95440">outside</span>
  <span m="95610">the control</span> <span m="95980">volume.</span> <span m="96540">Anything
  that</span> <span m="96960">decreases</span> <span m="97590">has</span> <span m="97760">to</span>
  <span m="97860">go</span> <span m="100290">out of</span> <span m="100724">the control</span>
  <span m="101158">volume.</span></p><p><span m="102460">And</span> <span m="102900">this</span>
  <span m="103080">is</span> <span m="103570">the</span> <span m="104590">differential</span>
  <span m="107030">form.</span> <span m="109460">And in</span> <span m="109770">one</span>
  <span m="110080">dimension</span> <span m="110580">of</span> <span m="110730">cos,</span>
  <span m="111100">the</span> <span m="111210">divergence</span> <span m="111910">is</span>
  <span m="112020">just</span> <span m="112190">spatial</span> <span m="112590">derivative.</span>
  <span m="114210">It''s</span> <span m="114420">just</span> <span m="114640">a</span>
  <span m="114925">partial</span> <span m="116350">x</span> <span m="116690">of</span>
  <span m="117030">F</span> <span m="117280">of</span> <span m="117410">rho.</span></p><p><span
  m="118080">And</span> <span m="118280">today</span> <span m="118550">we</span> <span
  m="118710">have</span> <span m="118840">going</span> <span m="118960">to</span>
  <span m="119020">be</span> <span m="119110">solving</span> <span m="119720">one</span>
  <span m="119990">of</span> <span m="121000">the</span> <span m="121090">equations</span>
  <span m="121516">like</span> <span m="121942">this.</span> <span m="123650">And</span>
  <span m="124860">in</span> <span m="125130">order</span> <span m="125410">to</span>
  <span m="125540">apply</span> <span m="125930">finite</span> <span m="126330">volume,</span>
  <span m="127210">we</span> <span m="127380">need</span> <span m="127620">to</span>
  <span m="127810">make</span> <span m="128100">it</span> <span m="129930">an</span>
  <span m="130100">integral</span> <span m="130650">form.</span> <span m="131690">We</span>
  <span m="131860">have</span> <span m="132120">to</span> <span m="132260">really</span>
  <span m="135930">integrate</span> <span m="136700">this in</span> <span m="137190">space.</span>
  <span m="138220">And</span> <span m="143050">instead</span> <span m="143390">of</span>
  <span m="143510">a</span> <span m="143590">divergence</span> <span m="144300">operating</span>
  <span m="145010">space,</span> <span m="146220">we</span> <span m="146490">get</span>
  <span m="147120">this--</span> <span m="148780">d dt</span> <span m="149660">of
  an</span> <span m="150140">integral</span> <span m="150940">over</span> <span m="151390">any</span>
  <span m="151630">control</span> <span m="152000">volume.</span> <span m="152330">Let</span>
  <span m="152550">me</span> <span m="152660">describe</span> <span m="153170">it</span>
  <span m="153976">as</span> <span m="154690">omega.</span> <span m="155280">Omega</span>
  <span m="155760">is</span> <span m="156020">a</span> <span m="156090">control volume.</span></p><p><span
  m="158630">So</span> <span m="158830">we</span> <span m="159000">are</span> <span
  m="159260">basically</span> <span m="159750">integrating</span> <span m="160710">this</span>
  <span m="161010">whole</span> <span m="161310">thing</span> <span m="161910">in</span>
  <span m="162150">omega.</span> <span m="163110">And</span> <span m="163330">this</span>
  <span m="163460">is</span> <span m="163540">the</span> <span m="163630">first</span>
  <span m="163890">thing</span> <span m="164030">we</span> <span m="164180">get.</span>
  <span m="164930">And</span> <span m="165070">the</span> <span m="165140">second</span>
  <span m="165510">thing</span> <span m="165670">we</span> <span m="165810">get</span>
  <span m="166260">is that</span> <span m="167193">now</span> <span m="167586">we
  are</span> <span m="167980">doing</span> <span m="168200">this</span> <span m="168480">in</span>
  <span m="169360">impossibly</span> <span m="169836">multiple</span> <span m="170312">dimensions,</span>
  <span m="170788">like</span> <span m="171740">last week</span> <span m="172216">[INAUDIBLE].</span></p><p><span
  m="173650">Now</span> <span m="173770">if</span> <span m="173800">you</span> <span
  m="174130">integrate</span> <span m="174460">the</span> <span m="174900">divergence</span>
  <span m="176870">of</span> <span m="177500">something--</span> <span m="178862">you''re</span>
  <span m="179328">integrating</span> <span m="179794">a</span> <span m="180260">divergence</span>
  <span m="180726">of a</span> <span m="181192">vector</span> <span m="181658">field--</span>
  <span m="182130">in a</span> <span m="182340">control</span> <span m="182570">volume,</span>
  <span m="183340">what</span> <span m="183620">do you</span> <span m="183850">get?</span>
  <span m="187010">A</span> <span m="187100">listing</span> <span m="187580">something</span>
  <span m="188052">like</span> <span m="188996">the</span> <span m="189940">integral</span>
  <span m="190120">of</span> <span m="190220">a</span> <span m="190700">divergence</span>
  <span m="190790">of</span> <span m="191260">a</span> <span m="191730">vector</span>
  <span m="192200">in</span> <span m="192317">a</span> <span m="192435">control</span>
  <span m="192552">volume</span> <span m="192670">equal to</span> <span m="193140">something</span>
  <span m="193540">[INAUDIBLE].</span> <span m="204166">Something</span> <span m="204660">can
  relate</span> <span m="205110">a divergence.</span> <span m="209086">[INAUDIBLE]</span>
  <span m="209583">the</span> <span m="210080">divergence</span> <span m="210580">0.</span>
  <span m="214536">[INAUDIBLE]</span> <span m="215960">is</span> <span m="216260">so</span>
  <span m="216732">cool.</span></p><p><span m="219290">There</span> <span m="219450">are</span>
  <span m="220590">two</span> <span m="221057">theorems</span> <span m="221524">in</span>
  <span m="221757">method</span> <span m="221991">popular</span> <span m="222458">that
  I</span> <span m="222925">can see</span> <span m="223392">that</span> <span m="223859">are</span>
  <span m="224330">very</span> <span m="224610">important,</span> <span m="225210">both</span>
  <span m="225660">relating</span> <span m="227192">a</span> <span m="227628">spatial</span>
  <span m="228064">derivative</span> <span m="228950">to</span> <span m="229370">a
  spatial</span> <span m="229790">integral.</span> <span m="231470">And</span> <span
  m="231930">the</span> <span m="232416">divergence</span> <span m="233390">theorem</span>
  <span m="233790">is</span> <span m="234230">the</span> <span m="234310">more</span>
  <span m="234560">fundamental</span> <span m="234840">one.</span> <span m="236650">I</span>
  <span m="236800">can</span> <span m="236970">feel</span> <span m="237220">a</span>
  <span m="237270">more fundamental</span> <span m="237920">one,</span> <span m="238070">because</span>
  <span m="239630">it</span> <span m="239790">basically</span> <span m="240120">tells</span>
  <span m="240400">you</span> <span m="241710">the</span> <span m="242430">spatial</span>
  <span m="243310">integral</span> <span m="244060">of a</span> <span m="244150">divergence</span>
  <span m="246890">can</span> <span m="247210">be</span> <span m="247480">expressed</span>
  <span m="248550">with</span> <span m="248840">something</span> <span m="249260">that</span>
  <span m="249460">doesn''t</span> <span m="249880">involve</span> <span m="250930">derivative</span>
  <span m="251530">at</span> <span m="251660">all.</span> <span m="252530">It</span>
  <span m="253300">can</span> <span m="253800">be</span> <span m="253950">represented</span>
  <span m="254355">as</span> <span m="255510">the</span> <span m="255830">integral</span>
  <span m="256120">over</span> <span m="256370">the</span> <span m="256490">surface</span>
  <span m="257140">of</span> <span m="257250">the</span> <span m="257329">control</span>
  <span m="257670">volume.</span> <span m="258920">The</span> <span m="259040">surface</span>
  <span m="259510">normal</span> <span m="260140">starts</span> <span m="260570">with</span>
  <span m="261480">just</span> <span m="261860">the</span> <span m="263480">flux</span>
  <span m="263890">vector</span> <span m="265030">is equal</span> <span m="265476">to
  0.</span></p><p><span m="267710">So</span> <span m="268340">divergence</span> <span
  m="269240">theorem</span> <span m="270170">says</span> <span m="270470">that</span>
  <span m="271030">the</span> <span m="271170">integral</span> <span m="271650">of</span>
  <span m="271780">this</span> <span m="272480">is</span> <span m="272760">equal</span>
  <span m="273020">to</span> <span m="273140">this--</span> <span m="275860">divergence</span>
  <span m="276120">theorem.</span> <span m="279110">So what</span> <span m="279320">you
  see</span> <span m="279760">is that</span> <span m="280976">this</span> <span m="281320">is</span>
  <span m="281640">the</span> <span m="281740">2D or 3D</span> <span m="282240">version</span>
  <span m="282740">of</span> <span m="283240">the</span> <span m="283740">integral</span>
  <span m="283950">form</span> <span m="284400">of the</span> <span m="285366">conservation</span>
  <span m="285850">law.</span> <span m="287390">What</span> <span m="287620">we</span>
  <span m="287750">are saying</span> <span m="288060">is that</span> <span m="289500">now,</span>
  <span m="289990">again,</span> <span m="290350">this</span> <span m="290630">is
  the</span> <span m="290910">total</span> <span m="291200">amount</span> <span m="291490">of</span>
  <span m="293160">mass,</span> <span m="293760">or</span> <span m="294360">stuff,</span>
  <span m="294770">within</span> <span m="294980">the</span> <span m="295432">control
  volume.</span></p><p><span m="296336">And</span> <span m="296790">today</span> <span
  m="297080">we''re</span> <span m="297350">going to be</span> <span m="297470">doing</span>
  <span m="297950">half.</span> <span m="298400">We see that</span> <span m="298852">the</span>
  <span m="299304">total</span> <span m="299756">[INAUDIBLE]</span> <span m="300210">half</span>
  <span m="300520">within</span> <span m="300936">a control</span> <span m="301352">volume.</span>
  <span m="302600">And</span> <span m="303270">this</span> <span m="303678">is</span>
  <span m="304086">the</span> <span m="305310">flux</span> <span m="305880">through</span>
  <span m="306450">anywhere</span> <span m="306913">in</span> <span m="307376">the</span>
  <span m="307839">surface.</span> <span m="309230">So</span> <span m="309430">there</span>
  <span m="309550">is</span> <span m="309650">a</span> <span m="310700">normal.</span>
  <span m="312090">And</span> <span m="312280">this</span> <span m="312480">normal</span>
  <span m="312790">is</span> <span m="313200">also</span> <span m="313640">at</span>
  <span m="313770">normal</span> <span m="314750">of</span> <span m="315700">the</span>
  <span m="316120">control volume.</span> <span m="316540">So</span> <span m="316650">n
  points</span> <span m="317450">towards</span> <span m="317570">the</span> <span
  m="317930">outset.</span></p><p><span m="318776">So</span> <span m="319200">this</span>
  <span m="319360">F</span> <span m="319760">of</span> <span m="319990">rho</span>
  <span m="320060">is</span> <span m="320440">the</span> <span m="320650">flux</span>
  <span m="320880">towards</span> <span m="321230">the</span> <span m="321640">outset.</span>
  <span m="323855">That</span> <span m="324300">makes sense,</span> <span m="325200">because</span>
  <span m="325550">if</span> <span m="326290">F</span> <span m="326945">points</span>
  <span m="329110">outward--</span> <span m="330157">if</span> <span m="330564">the
  flux</span> <span m="330971">is</span> <span m="331380">towards</span> <span m="331550">the</span>
  <span m="331760">outside--</span> <span m="333350">then</span> <span m="333510">this</span>
  <span m="333760">term</span> <span m="334290">would</span> <span m="334440">be</span>
  <span m="335290">positive,</span> <span m="335870">because</span> <span m="336590">F</span>
  <span m="336880">is</span> <span m="337070">going to be</span> <span m="337340">aligned</span>
  <span m="337680">with</span> <span m="337960">n.</span> <span m="338240">This</span>
  <span m="338530">term is</span> <span m="338820">positive.</span> <span m="339890">And</span>
  <span m="340090">the</span> <span m="340220">time</span> <span m="340580">derivative</span>
  <span m="341000">will</span> <span m="341420">be</span> <span m="341840">negative</span>
  <span m="342260">because things</span> <span m="342680">are going</span> <span m="343120">out,</span>
  <span m="344020">the stuff</span> <span m="344120">should</span> <span m="344564">decrease.</span></p><p><span
  m="346340">If</span> <span m="346740">asked</span> <span m="347240">if</span> <span
  m="347430">the</span> <span m="347630">flux</span> <span m="348020">vector</span>
  <span m="348410">points</span> <span m="348760">inward,</span> <span m="349030">then</span>
  <span m="349468">it</span> <span m="349906">is going</span> <span m="350344">opposite</span>
  <span m="352100">to</span> <span m="352300">the</span> <span m="352520">outward</span>
  <span m="353170">point</span> <span m="353390">of</span> <span m="353500">normal,</span>
  <span m="354040">opposite</span> <span m="354410">to n.</span> <span m="355264">And</span>
  <span m="355641">this</span> <span m="356020">integral</span> <span m="356460">would
  be</span> <span m="356900">negative.</span> <span m="358420">So</span> <span m="358670">if</span>
  <span m="358930">this thing</span> <span m="359160">is</span> <span m="359400">negative,</span>
  <span m="359580">then we</span> <span m="360033">have to</span> <span m="360486">add
  to</span> <span m="360940">0</span> <span m="361120">so</span> <span m="361570">this
  can</span> <span m="361780">have some</span> <span m="362265">positive,</span> <span
  m="362750">which means</span> <span m="363235">the</span> <span m="363720">amount</span>
  <span m="364050">of</span> <span m="364180">stuff</span> <span m="364490">is going
  to</span> <span m="364950">increase</span> <span m="365950">as</span> <span m="366130">a</span>
  <span m="366190">function</span> <span m="366430">of</span> <span m="366580">time.</span>
  <span m="368218">Is</span> <span m="368654">it</span> <span m="369090">clear?</span></p><p><span
  m="369600">This</span> <span m="369990">is</span> <span m="370130">now</span> <span
  m="370380">generalizing</span> <span m="371130">that</span> <span m="371360">in</span>
  <span m="371960">2D</span> <span m="372370">or</span> <span m="372510">3D.</span>
  <span m="373450">And</span> <span m="373670">of</span> <span m="373770">course,</span>
  <span m="374160">we</span> <span m="374230">can</span> <span m="374630">still</span>
  <span m="374980">write</span> <span m="375230">that</span> <span m="375330">in</span>
  <span m="375480">1D.</span> <span m="376910">In</span> <span m="377100">the</span>
  <span m="377150">one</span> <span m="377500">dimensional</span> <span m="378880">special</span>
  <span m="379280">case,</span> <span m="380710">what</span> <span m="382550">is</span>
  <span m="382930">this</span> <span m="384170">partial</span> <span m="384550">omega?</span>
  <span m="384980">Partial</span> <span m="385110">omega</span> <span m="385460">is</span>
  <span m="385910">the</span> <span m="386120">boundary</span> <span m="386425">of</span>
  <span m="386730">omega.</span> <span m="387860">What</span> <span m="388080">is</span>
  <span m="388250">the</span> <span m="388350">boundary</span> <span m="389070">of
  the</span> <span m="389250">one</span> <span m="389690">dimensional</span> <span
  m="390170">control</span> <span m="390661">volume?</span></p><p><span m="394100">The</span>
  <span m="394250">point,</span> <span m="394840">or two</span> <span m="395020">points--</span>
  <span m="397020">two</span> <span m="397250">points,</span> <span m="397690">right?</span>
  <span m="398680">And</span> <span m="399100">the</span> <span m="399250">two</span>
  <span m="399540">points,</span> <span m="400030">I</span> <span m="400320">have</span>
  <span m="400580">R</span> <span m="401030">and</span> <span m="401310">L.</span>
  <span m="402970">And</span> <span m="403590">outward</span> <span m="404150">pointing</span>
  <span m="404890">normal</span> <span m="405500">is</span> <span m="405750">going</span>
  <span m="405960">to</span> <span m="406060">be</span> <span m="406270">just</span>
  <span m="406490">a</span> <span m="406790">1</span> <span m="407400">at</span> <span
  m="407770">the</span> <span m="407910">right hand</span> <span m="408345">side at</span>
  <span m="408780">R,</span> <span m="409170">is</span> <span m="409360">going</span>
  <span m="409480">to</span> <span m="409540">be</span> <span m="409600">minus</span>
  <span m="410000">1 at</span> <span m="410390">L.</span> <span m="411170">So</span>
  <span m="411560">I''m</span> <span m="411680">just</span> <span m="411830">going</span>
  <span m="411970">to</span> <span m="412040">be</span> <span m="412240">saying</span>
  <span m="412990">this</span> <span m="413180">is</span> <span m="413410">F</span>
  <span m="413710">of</span> <span m="413940">rho</span> <span m="415240">at</span>
  <span m="415770">R</span> <span m="416330">minus</span> <span m="416850">F</span>
  <span m="417100">of</span> <span m="417280">rho</span> <span m="418410">at</span>
  <span m="418690">L</span> <span m="419040">is</span> <span m="419452">equal to</span>
  <span m="419864">0.</span> <span m="420688">Or</span> <span m="421100">as</span>
  <span m="421420">we</span> <span m="421550">said</span> <span m="421936">on</span>
  <span m="422322">Monday,</span> <span m="422960">the</span> <span m="423960">time</span>
  <span m="424460">derivative</span> <span m="424960">of</span> <span m="425460">total
  stuff</span> <span m="425960">is</span> <span m="426460">equal</span> <span m="426960">to</span>
  <span m="427460">the stuff</span> <span m="427960">coming</span> <span m="428460">in
  from</span> <span m="428960">the</span> <span m="429460">left</span> <span m="429715">minus</span>
  <span m="429970">the</span> <span m="430456">stuff</span> <span m="430942">coming
  out</span> <span m="431428">from the</span> <span m="431914">right,</span> <span
  m="432886">if you moved</span> <span m="433372">both of</span> <span m="433858">this
  stuff</span> <span m="434344">[INAUDIBLE]</span> <span m="435316">side</span> <span
  m="435802">by</span> <span m="436288">side.</span></p><p><span m="438850">So</span>
  <span m="440240">this</span> <span m="440640">is</span> <span m="440760">the</span>
  <span m="440880">kind</span> <span m="441170">of</span> <span m="442720">differential</span>
  <span m="443180">equations</span> <span m="443690">we</span> <span m="443880">are</span>
  <span m="444070">solving,</span> <span m="445270">and</span> <span m="446510">the</span>
  <span m="446620">scheme</span> <span m="447820">is</span> <span m="448280">finite</span>
  <span m="448640">volume.</span> <span m="449630">And</span> <span m="449840">finite</span>
  <span m="450100">volume</span> <span m="451440">basically</span> <span m="452640">follows</span>
  <span m="453150">exactly</span> <span m="453680">this</span> <span m="454510">formula.</span>
  <span m="457120">Instead</span> <span m="457390">of</span> <span m="458590">integral</span>
  <span m="459260">over</span> <span m="459680">control volume,</span> <span m="460300">we</span>
  <span m="460780">are</span> <span m="461915">storing</span> <span m="462190">the</span>
  <span m="462390">average</span> <span m="462670">of</span> <span m="463145">the</span>
  <span m="463620">control volume,</span> <span m="464570">which</span> <span m="464760">is</span>
  <span m="464900">simply</span> <span m="465240">the</span> <span m="465450">integral</span>
  <span m="466080">divided</span> <span m="466180">by</span> <span m="466400">the
  size</span> <span m="466700">of</span> <span m="467175">the control</span> <span
  m="467650">volume.</span> <span m="470030">It</span> <span m="470210">could</span>
  <span m="470330">modify</span> <span m="471130">the</span> <span m="471410">cell</span>
  <span m="471690">average</span> <span m="472800">with</span> <span m="473020">the</span>
  <span m="473090">size</span> <span m="473380">of</span> <span m="473480">the</span>
  <span m="473570">cell,</span> <span m="473870">with the</span> <span m="474368">integral.</span>
  <span m="476360">And</span> <span m="476610">in order to</span> <span m="477000">think</span>
  <span m="477390">of</span> <span m="477530">the</span> <span m="477660">DDP</span>
  <span m="478330">of</span> <span m="478550">the</span> <span m="478680">cell</span>
  <span m="478960">average,</span> <span m="479420">you</span> <span m="479745">just</span>
  <span m="480070">divide</span> <span m="481120">this</span> <span m="482370">also</span>
  <span m="482730">by</span> <span m="483040">the</span> <span m="483100">cell</span>
  <span m="484061">volume,</span> <span m="484552">or cell</span> <span m="485043">size.</span>
  <span m="486025">So</span> <span m="486516">you get the</span> <span m="487010">evolution</span>
  <span m="487710">equation</span> <span m="488662">that</span> <span m="489138">allows</span>
  <span m="489614">you to</span> <span m="490090">control</span> <span m="490826">using</span>
  <span m="491182">finite</span> <span m="491540">volume.</span></p><p><span m="494010">Now</span>
  <span m="494970">this</span> <span m="495190">equation</span> <span m="495650">is</span>
  <span m="495820">not</span> <span m="496190">approximate</span> <span m="497030">This</span>
  <span m="497180">is</span> <span m="497310">exact.</span> <span m="499030">What</span>
  <span m="499210">we</span> <span m="499300">need</span> <span m="499480">to</span>
  <span m="499600">approximate</span> <span m="499740">in</span> <span m="500120">finite</span>
  <span m="500500">volume</span> <span m="501140">is</span> <span m="501390">this</span>
  <span m="501660">flux.</span> <span m="503290">This</span> <span m="503650">flux</span>
  <span m="504200">is</span> <span m="504510">a flux</span> <span m="505050">evaluated</span>
  <span m="505970">after</span> <span m="506320">the</span> <span m="506410">cell</span>
  <span m="506820">boundaries</span> <span m="507230">or</span> <span m="507540">cell</span>
  <span m="508012">[INAUDIBLE].</span> <span m="509428">And</span> <span m="509900">the</span>
  <span m="510372">finite volume</span> <span m="510844">is</span> <span m="511316">[INAUDIBLE].</span>
  <span m="512260">You</span> <span m="512740">only</span> <span m="512950">have the
  cell</span> <span m="513437">average.</span> <span m="513924">So you</span> <span
  m="514411">need to</span> <span m="514900">approximate</span> <span m="515650">the</span>
  <span m="516130">interface</span> <span m="516450">value</span> <span m="517214">from</span>
  <span m="517658">the</span> <span m="518102">cell average.</span> <span m="518990">And</span>
  <span m="519210">that</span> <span m="519659">is</span> <span m="519929">the</span>
  <span m="520100">approximation</span> <span m="520860">we</span> <span m="521020">have</span>
  <span m="521230">been</span> <span m="521460">talking</span> <span m="521730">about.</span></p><p><span
  m="525460">So</span> <span m="526020">that''s</span> <span m="526270">kind</span>
  <span m="526430">of</span> <span m="526550">a</span> <span m="526650">review.</span>
  <span m="527400">The</span> <span m="528320">first</span> <span m="528520">new</span>
  <span m="528720">thing</span> <span m="528950">we''re</span> <span m="529090">going</span>
  <span m="529240">to</span> <span m="529310">talk</span> <span m="529550">about</span>
  <span m="529810">is,</span> <span m="529980">actually,</span> <span m="530320">why</span>
  <span m="530740">do</span> <span m="530870">we</span> <span m="531050">use</span>
  <span m="531300">finite</span> <span m="531470">volume.</span> <span m="533960">We</span>
  <span m="534200">use</span> <span m="534420">finite</span> <span m="534650">volume</span>
  <span m="535660">because</span> <span m="536210">it</span> <span m="536370">captures</span>
  <span m="537380">shock waves,</span> <span m="539670">because</span> <span m="540060">if</span>
  <span m="540230">there</span> <span m="540410">is</span> <span m="540820">discontinuity</span>
  <span m="541960">in</span> <span m="542160">the</span> <span m="542260">solution,</span>
  <span m="543360">finite</span> <span m="543630">difference</span> <span m="544010">doesn''t</span>
  <span m="544280">work.</span> <span m="545440">I''m</span> <span m="545590">going</span>
  <span m="545710">to</span> <span m="545820">show</span> <span m="546120">you</span>
  <span m="546320">with a--</span> <span m="546762">what?</span> <span m="548530">Cancel.</span>
  <span m="550790">I''m</span> <span m="551010">still</span> <span m="554120">testing</span>
  <span m="554440">around</span> <span m="554960">with</span> <span m="555810">the</span>
  <span m="555910">code</span> <span m="556240">you</span> <span m="556400">wrote.</span>
  <span m="557522">But</span> <span m="558470">let</span> <span m="558590">me</span>
  <span m="558670">go</span> <span m="558900">to</span> <span m="559060">today''s</span>
  <span m="559460">directory,</span> <span m="560430">and</span> <span m="560600">I''m</span>
  <span m="560720">going</span> <span m="560890">to</span> <span m="561160">show you</span>
  <span m="561350">two</span> <span m="561590">demos.</span> <span m="564290">I''m</span>
  <span m="564530">going</span> <span m="564680">to</span> <span m="564800">show</span>
  <span m="565110">you</span> <span m="565990">a</span> <span m="567840">simulate--</span>
  <span m="568850">so</span> <span m="569200">first,</span> <span m="569490">I''m</span>
  <span m="569670">going</span> <span m="569830">to</span> <span m="570320">tell</span>
  <span m="570530">you</span> <span m="570650">what</span> <span m="570850">this</span>
  <span m="571010">is</span> <span m="571130">doing.</span></p><p><span m="571920">So</span>
  <span m="572560">I</span> <span m="572720">have</span> <span m="572890">two</span>
  <span m="573050">functions,</span> <span m="574760">one</span> <span m="575030">is</span>
  <span m="575140">simulate</span> <span m="575930">fv,</span> <span m="576730">and</span>
  <span m="577110">one</span> <span m="577430">is</span> <span m="577520">simulate</span>
  <span m="578310">fd.</span> <span m="579420">So</span> <span m="581630">these</span>
  <span m="581900">two</span> <span m="582060">functions</span> <span m="582540">are</span>
  <span m="583170">identical,</span> <span m="584850">except</span> <span m="585490">for</span>
  <span m="586090">this</span> <span m="586470">single</span> <span m="586878">letter.</span>
  <span m="588510">One</span> <span m="588750">is</span> <span m="588990">fd,</span>
  <span m="589460">one''s</span> <span m="589710">fv.</span> <span m="590320">But</span>
  <span m="590420">otherwise,</span> <span m="590695">I''m</span> <span m="590970">just</span>
  <span m="591335">doing the</span> <span m="591700">same.</span> <span m="591900">I''m</span>
  <span m="592180">using</span> <span m="592570">[INAUDIBLE]</span> <span m="592780">45</span>
  <span m="593230">to</span> <span m="593340">integrate</span> <span m="593640">in</span>
  <span m="593940">time.</span> <span m="596980">Conditions</span> <span m="597590">on</span>
  <span m="598210">that</span> <span m="598460">I''m</span> <span m="598930">[INAUDIBLE]</span>
  <span m="599550">having</span> <span m="600020">space,</span> <span m="600380">using</span>
  <span m="600600">either</span> <span m="601200">finite</span> <span m="601460">volume</span>
  <span m="601900">or finite</span> <span m="602322">difference.</span></p><p><span
  m="603920">I</span> <span m="604250">see</span> <span m="604430">there is a</span>
  <span m="605050">question on</span> <span m="605520">what this</span> <span m="605990">''''at''''</span>
  <span m="606460">do.</span> <span m="607870">This</span> <span m="608340">&quot;at&quot;</span>
  <span m="608810">is</span> <span m="609280">basically</span> <span m="610220">take
  a</span> <span m="610700">function</span> <span m="611495">I</span> <span m="611950">wrote,</span>
  <span m="612860">which</span> <span m="613150">is</span> <span m="613340">either</span>
  <span m="615880">du</span> <span m="616020">dp</span> <span m="616275">fv</span>
  <span m="617240">or</span> <span m="617490">du</span> <span m="617780">dp</span>
  <span m="618070">fd</span> <span m="619550">and</span> <span m="620030">feed</span>
  <span m="620350">that</span> <span m="620860">into</span> <span m="621260">the</span>
  <span m="621380">ODE</span> <span m="621730">45.</span> <span m="624340">Anytime</span>
  <span m="624620">you</span> <span m="624700">use</span> <span m="625095">ODE</span>
  <span m="625360">45</span> <span m="625700">you need</span> <span m="626040">this</span>
  <span m="626230">&quot;at&quot;</span> <span m="627000">to</span> <span m="627070">make</span>
  <span m="627300">it</span> <span m="627410">work.</span></p><p><span m="628490">Now</span>
  <span m="628560">the</span> <span m="628660">difference</span> <span m="629040">between</span>
  <span m="629310">finding</span> <span m="629510">fd</span> <span m="629790">and</span>
  <span m="630090">finding</span> <span m="630390">fv</span> <span m="630655">is</span>
  <span m="630920">that</span> <span m="632346">in this</span> <span m="632832">we''re
  using</span> <span m="633320">the standard</span> <span m="633640">finite</span>
  <span m="634042">difference</span> <span m="634444">to</span> <span m="634846">solve</span>
  <span m="635250">the</span> <span m="635610">differential form</span> <span m="635740">of</span>
  <span m="635980">the</span> <span m="636443">Burger''s</span> <span m="636906">equation.</span>
  <span m="641536">So</span> <span m="642000">du dp</span> <span m="642730">is</span>
  <span m="643140">equal</span> <span m="643400">to</span> <span m="644621">minus</span>
  <span m="645030">u</span> <span m="645990">times</span> <span m="646390">du</span>
  <span m="646883">dx.</span> <span m="647869">This is</span> <span m="648362">du
  dx.</span> <span m="648855">Now you should</span> <span m="649348">be familiar</span>
  <span m="649841">with this.</span> <span m="650827">I''m taking</span> <span m="651320">u</span>
  <span m="652340">minus</span> <span m="653305">a</span> <span m="653710">specific</span>
  <span m="654520">version</span> <span m="654880">of</span> <span m="655060">u--</span>
  <span m="655530">this is</span> <span m="656030">assuming</span> <span m="657530">[INAUDIBLE]</span>
  <span m="658530">conditions--</span> <span m="659030">divided by</span> <span m="659530">dx.</span>
  <span m="660270">So</span> <span m="662460">this</span> <span m="662890">is</span>
  <span m="663243">a</span> <span m="663596">[INAUDIBLE]</span> <span m="663950">space</span>
  <span m="664423">on</span> <span m="664896">a</span> <span m="665369">difference</span>
  <span m="666790">of</span> <span m="667100">du</span> <span m="667340">dx.</span>
  <span m="668400">So</span> <span m="668730">here</span> <span m="668990">I</span>
  <span m="669090">am</span> <span m="669190">solving</span> <span m="669640">the</span>
  <span m="669870">differential</span> <span m="670300">form</span> <span m="670570">of</span>
  <span m="670770">the</span> <span m="671505">equation</span> <span m="671930">of</span>
  <span m="672355">the finite</span> <span m="672780">difference.</span></p><p><span
  m="673620">In</span> <span m="673770">finite</span> <span m="674040">volume--</span>
  <span m="674780">let''s</span> <span m="674980">review</span> <span m="675290">what</span>
  <span m="675560">we</span> <span m="675690">do</span> <span m="675820">in</span>
  <span m="675980">finite</span> <span m="676448">volume.</span> <span m="678790">du</span>
  <span m="678950">dx</span> <span m="679480">[INAUDIBLE]</span> <span m="680160">flux.</span>
  <span m="680950">Now,</span> <span m="681340">this</span> <span m="681460">is</span>
  <span m="681710">not</span> <span m="682110">using the</span> <span m="682450">differential</span>
  <span m="682918">form,</span> <span m="683386">but using</span> <span m="683854">the</span>
  <span m="684088">[INAUDIBLE]</span> <span m="684322">form</span> <span m="684790">because
  we are</span> <span m="685258">computing</span> <span m="685726">the flux.</span>
  <span m="686670">And</span> <span m="689040">here,</span> <span m="689460">I''m</span>
  <span m="689520">assuming</span> <span m="690020">the</span> <span m="690520">opposite</span>
  <span m="691020">direction</span> <span m="691520">is</span> <span m="692020">always</span>
  <span m="693020">the</span> <span m="693130">left.</span> <span m="694410">Here,</span>
  <span m="694680">I''m</span> <span m="694950">assuming</span> <span m="695840">like</span>
  <span m="695960">I</span> <span m="696080">have</span> <span m="696280">an initial</span>
  <span m="696690">condition</span> <span m="697100">that</span> <span m="697230">is</span>
  <span m="697800">opposite,</span> <span m="698410">and</span> <span m="699676">it''s</span>
  <span m="700169">easy</span> <span m="700662">to</span> <span m="701155">illustrate</span>
  <span m="701648">using</span> <span m="702141">a case</span> <span m="702634">like
  that.</span></p><p><span m="703620">So</span> <span m="704120">the wind</span> <span
  m="704400">always</span> <span m="704700">come</span> <span m="704930">from</span>
  <span m="705140">the</span> <span m="705220">left,</span> <span m="705860">u is</span>
  <span m="706190">always</span> <span m="706770">positive.</span> <span m="707010">That</span>
  <span m="707488">means when</span> <span m="707966">[INAUDIBLE]</span> <span m="715620">it</span>
  <span m="715770">is</span> <span m="715940">a</span> <span m="716080">minus</span>
  <span m="716580">[INAUDIBLE].</span> <span m="719080">And</span> <span m="719580">I''m
  doing</span> <span m="720080">du dt</span> <span m="720580">equal</span> <span m="721080">to</span>
  <span m="722080">flux</span> <span m="722925">at</span> <span m="723400">the left</span>
  <span m="723875">minus</span> <span m="724350">flux</span> <span m="724825">at the
  right</span> <span m="725300">divided by</span> <span m="725780">dx.</span> <span
  m="726290">So</span> <span m="726450">this</span> <span m="726590">is</span> <span
  m="726700">finite</span> <span m="726870">volume.</span></p><p><span m="727990">So</span>
  <span m="728120">let''s</span> <span m="728380">see,</span> <span m="728730">what</span>
  <span m="728950">is</span> <span m="729080">the</span> <span m="730540">key</span>
  <span m="730800">difference</span> <span m="731350">between</span> <span m="731620">the</span>
  <span m="731690">results</span> <span m="732070">of</span> <span m="732150">these</span>
  <span m="732330">two</span> <span m="732490">schemes.</span> <span m="733790">And
  in</span> <span m="734070">either</span> <span m="734510">one,</span> <span m="734780">I''m</span>
  <span m="734980">starting</span> <span m="735660">with</span> <span m="736000">something</span>
  <span m="736240">positive,</span> <span m="736737">so</span> <span m="737234">sine
  x</span> <span m="737731">plus 1</span> <span m="738230">over</span> <span m="738490">2</span>
  <span m="738650">because</span> <span m="738750">I''m</span> <span m="739680">assuming</span>
  <span m="740100">also</span> <span m="740535">in</span> <span m="740970">finite</span>
  <span m="741020">difference</span> <span m="741295">and</span> <span m="741570">finite</span>
  <span m="741750">volume,</span> <span m="742170">the</span> <span m="742260">wind</span>
  <span m="742450">comes from</span> <span m="742886">the left.</span> <span m="743760">So
  that</span> <span m="743910">I''m doing</span> <span m="744440">[? backwarding ?]</span>
  <span m="745080">space</span> <span m="746830">is a</span> <span m="747303">finite
  difference or</span> <span m="747776">finite volume.</span></p><p><span m="750614">So</span>
  <span m="751087">I have</span> <span m="751560">a positive</span> <span m="752033">solution.</span>
  <span m="752506">I</span> <span m="752990">told</span> <span m="753220">them</span>
  <span m="753440">to</span> <span m="753590">see</span> <span m="753860">how</span>
  <span m="754040">it</span> <span m="754140">does.</span> <span m="755390">So</span>
  <span m="755710">I''m</span> <span m="756020">going to</span> <span m="756460">[INAUDIBLE]</span>
  <span m="756660">on a</span> <span m="756850">different</span> <span m="757270">sort,</span>
  <span m="757930">and</span> <span m="758110">somebody</span> <span m="758520">new</span>
  <span m="758640">will</span> <span m="758740">tell</span> <span m="758960">me,</span>
  <span m="759130">what</span> <span m="759370">is</span> <span m="759570">wrong</span>
  <span m="760070">with</span> <span m="760260">a</span> <span m="760300">finite</span>
  <span m="760560">difference</span> <span m="760870">solution.</span> <span m="762520">Watch</span>
  <span m="762740">carefully.</span> <span m="763570">I''m</span> <span m="763730">going</span>
  <span m="763860">to</span> <span m="763980">start.</span> <span m="764750">You</span>
  <span m="764850">need</span> <span m="764990">to</span> <span m="765070">tell</span>
  <span m="765280">me</span> <span m="765675">what''s</span> <span m="765960">going</span>
  <span m="766220">wrong.</span></p><p><span m="768390">So it</span> <span m="768550">looks</span>
  <span m="768870">like</span> <span m="769090">any</span> <span m="769410">Burger''s</span>
  <span m="769770">equation.</span> <span m="770670">I mean,</span> <span m="770990">we</span>
  <span m="771110">have</span> <span m="771230">a</span> <span m="771300">shock wave.</span>
  <span m="772236">Things</span> <span m="773172">are</span> <span m="773640">going.</span>
  <span m="774110">So</span> <span m="774950">what''s</span> <span m="775460">wrong</span>
  <span m="776282">with</span> <span m="776734">this?</span> <span m="778994">Is</span>
  <span m="779450">anything</span> <span m="779790">wrong?</span> <span m="781410">Solution</span>
  <span m="781858">[INAUDIBLE].</span> <span m="784100">Let</span> <span m="784230">me</span>
  <span m="784330">run</span> <span m="784570">again.</span> <span m="793952">Anything</span>
  <span m="794430">looks</span> <span m="794920">wrong?</span> <span m="798910">Many</span>
  <span m="799260">different</span> <span m="799530">circles</span> <span m="799810">it''d</span>
  <span m="800090">be</span> <span m="800566">tracing,</span> <span m="801042">but
  it''s</span> <span m="801518">not.</span></p><p><span m="801994">AUDIENCE:</span>
  <span m="802470">[INAUDIBLE]</span></p><p><span m="807720">QIQI WANG: You</span>
  <span m="807990">have</span> <span m="808300">sharp eyes.</span> <span m="808990">Now,</span>
  <span m="809290">let''s</span> <span m="809560">look</span> <span m="809800">at</span>
  <span m="809900">the</span> <span m="810000">finite</span> <span m="810350">volume</span>
  <span m="810770">solution.</span> <span m="812110">Exactly</span> <span m="812630">the</span>
  <span m="812750">same,</span> <span m="813470">but</span> <span m="813570">using</span>
  <span m="814039">finite</span> <span m="814508">volume.</span> <span m="818260">What''s</span>
  <span m="818730">the</span> <span m="818840">difference?</span> <span m="822380">This</span>
  <span m="822800">[INAUDIBLE]</span> <span m="823170">the</span> <span m="823506">shock
  wave</span> <span m="824180">is</span> <span m="824790">correct</span> <span m="825090">in</span>
  <span m="825230">this</span> <span m="825440">case.</span> <span m="825900">While</span>
  <span m="826540">the</span> <span m="826650">shock</span> <span m="827180">just</span>
  <span m="827480">[INAUDIBLE]</span> <span m="827750">it</span> <span m="827960">forms,</span>
  <span m="828800">the</span> <span m="829010">finite</span> <span m="829220">difference</span>
  <span m="829920">just</span> <span m="830140">stands</span> <span m="830490">there.</span>
  <span m="831760">The</span> <span m="831910">speed</span> <span m="832300">of</span>
  <span m="832400">the</span> <span m="832490">shock wave</span> <span m="833298">is</span>
  <span m="833766">finite</span> <span m="834234">difference,</span> <span m="835170">is</span>
  <span m="835510">wrong</span> <span m="836000">in</span> <span m="836477">finite</span>
  <span m="836954">difference.</span></p><p><span m="838310">So</span> <span m="838920">by</span>
  <span m="839310">using</span> <span m="839700">the</span> <span m="839870">differential</span>
  <span m="840550">form</span> <span m="840890">of</span> <span m="841358">the</span>
  <span m="842294">equation</span> <span m="843700">and</span> <span m="844720">disregarding</span>
  <span m="846290">the</span> <span m="846580">conservative</span> <span m="846860">form,</span>
  <span m="849410">you</span> <span m="849840">are</span> <span m="850110">not</span>
  <span m="850500">guaranteed</span> <span m="851560">to</span> <span m="851720">have</span>
  <span m="851960">the</span> <span m="852030">correct</span> <span m="853040">speed</span>
  <span m="853310">of the</span> <span m="853712">shock wave.</span> <span m="854918">It</span>
  <span m="855320">actually</span> <span m="855670">solves</span> <span m="856240">the</span>
  <span m="856460">other</span> <span m="856876">part</span> <span m="857292">correctly.</span>
  <span m="858540">The</span> <span m="858730">only</span> <span m="859010">part</span>
  <span m="859270">that</span> <span m="859450">it doesn''t</span> <span m="859946">capture</span>
  <span m="860442">correctly</span> <span m="860940">is</span> <span m="861280">how</span>
  <span m="861570">the</span> <span m="861670">shock wave</span> <span m="862640">is</span>
  <span m="862830">supposed</span> <span m="863150">to</span> <span m="863220">behave.</span>
  <span m="864460">And</span> <span m="864850">if</span> <span m="865040">we</span>
  <span m="865220">use</span> <span m="865440">finite</span> <span m="865670">volume,</span>
  <span m="866690">because</span> <span m="867360">we</span> <span m="867670">are</span>
  <span m="867870">looking</span> <span m="868340">at</span> <span m="869150">the</span>
  <span m="869810">conservative</span> <span m="870090">form</span> <span m="870440">of</span>
  <span m="870590">the</span> <span m="870680">differential</span> <span m="871190">equation</span>
  <span m="873250">of</span> <span m="873360">this</span> <span m="873550">form,</span>
  <span m="874080">the</span> <span m="875770">other</span> <span m="875970">integral</span>
  <span m="876580">form.</span> <span m="882460">This</span> <span m="882890">form</span>
  <span m="883210">of</span> <span m="883465">[INAUDIBLE]</span> <span m="884530">is</span>
  <span m="884700">to</span> <span m="884790">have</span> <span m="884990">shock waves.</span>
  <span m="886980">Solve</span> <span m="887320">this</span> <span m="887620">one,</span>
  <span m="888882">and</span> <span m="889333">you take</span> <span m="889784">the
  divergence</span> <span m="890686">of</span> <span m="891588">the</span> <span m="892040">[INAUDIBLE]</span>
  <span m="892450">that</span> <span m="892590">is</span> <span m="893240">discontinuous,</span>
  <span m="894518">for</span> <span m="894976">it</span> <span m="895892">acts</span>
  <span m="896350">derivative</span> <span m="896970">of</span> <span m="897100">something</span>
  <span m="897460">that</span> <span m="897610">is</span> <span m="897930">discontinuous.</span>
  <span m="899010">That</span> <span m="899190">is</span> <span m="899340">no</span>
  <span m="899490">longer</span> <span m="900390">a correct</span> <span m="900870">thing</span>
  <span m="901350">to</span> <span m="901440">do.</span> <span m="903760">And</span>
  <span m="903910">therefore,</span> <span m="904380">you</span> <span m="904580">get</span>
  <span m="905460">wrong</span> <span m="905810">behavior</span> <span m="906522">when</span>
  <span m="906880">there</span> <span m="907140">is</span> <span m="907510">discontinuity</span>
  <span m="908610">like</span> <span m="908870">shock waves.</span> <span m="913710">Any</span>
  <span m="913880">questions?</span></p><p><span m="920180">Oh,</span> <span m="920490">and</span>
  <span m="920630">by</span> <span m="920760">the</span> <span m="920850">way,</span>
  <span m="924480">another</span> <span m="924760">thing</span> <span m="925060">is</span>
  <span m="925340">this.</span> <span m="930290">I</span> <span m="930420">should</span>
  <span m="930600">let</span> <span m="930800">you</span> <span m="930920">look.</span>
  <span m="931670">In</span> <span m="931840">addition</span> <span m="932200">to</span>
  <span m="932290">the</span> <span m="932400">shock wave,</span> <span m="932860">there</span>
  <span m="933030">is</span> <span m="933560">another</span> <span m="933910">thing</span>
  <span m="934120">that</span> <span m="934300">is</span> <span m="934480">not</span>
  <span m="934720">right</span> <span m="935490">in</span> <span m="935660">the</span>
  <span m="935910">finite</span> <span m="936020">difference.</span> <span m="939390">Lets</span>
  <span m="939660">look</span> <span m="939870">again at</span> <span m="940320">the</span>
  <span m="940420">finite</span> <span m="940550">volume.</span> <span m="942281">The</span>
  <span m="942758">Burger''s equation''s</span> <span m="943235">a conservation</span>
  <span m="943712">law,</span> <span m="945150">which means</span> <span m="945560">that</span>
  <span m="945970">[INAUDIBLE]</span> <span m="947020">under</span> <span m="947310">the</span>
  <span m="947680">curve</span> <span m="948101">should be</span> <span m="948522">[INAUDIBLE].</span>
  <span m="950960">The</span> <span m="951090">integral</span> <span m="952120">of</span>
  <span m="952260">the</span> <span m="952575">solution</span> <span m="952890">u,</span>
  <span m="953470">of</span> <span m="953620">course,</span> <span m="953940">the</span>
  <span m="954040">whole</span> <span m="954060">domain,</span> <span m="954540">should</span>
  <span m="954850">be</span> <span m="956060">the</span> <span m="956230">same,</span>
  <span m="957160">because</span> <span m="957560">anything</span> <span m="957940">that</span>
  <span m="958320">comes</span> <span m="958700">out of</span> <span m="958990">here</span>
  <span m="959650">should come</span> <span m="959860">back</span> <span m="960205">into</span>
  <span m="960550">here.</span> <span m="960880">It''s like</span> <span m="961363">when
  you</span> <span m="961846">step out of</span> <span m="962330">the</span> <span
  m="962430">door,</span> <span m="962740">you come</span> <span m="963040">back.</span>
  <span m="963380">You''re</span> <span m="963540">not</span> <span m="963805">disappearing.</span>
  <span m="965170">But</span> <span m="965380">if</span> <span m="965530">you</span>
  <span m="965630">look</span> <span m="965890">at</span> <span m="965980">the</span>
  <span m="966050">finite</span> <span m="966400">difference,</span> <span m="970341">at
  this</span> <span m="970814">point,</span> <span m="971287">it</span> <span m="971760">[INAUDIBLE].</span>
  <span m="974130">Things just</span> <span m="974370">disappear</span> <span m="974900">out</span>
  <span m="975050">of</span> <span m="975140">nowhere.</span> <span m="977580">The</span>
  <span m="977700">solution</span> <span m="978320">is</span> <span m="978720">not</span>
  <span m="979601">conserved.</span></p><p><span m="982060">So</span> <span m="982730">two</span>
  <span m="982980">things</span> <span m="984020">that</span> <span m="984200">finite</span>
  <span m="984450">difference</span> <span m="985930">is</span> <span m="986140">missing.</span>
  <span m="986540">One</span> <span m="986890">is,</span> <span m="987120">it</span>
  <span m="987230">doesn''t</span> <span m="987916">have</span> <span m="988260">to</span>
  <span m="988690">behave</span> <span m="989130">as</span> <span m="989230">a</span>
  <span m="989270">shock wave.</span> <span m="990420">Two,</span> <span m="991580">it</span>
  <span m="991760">is</span> <span m="992040">the</span> <span m="992200">solution</span>
  <span m="992720">is</span> <span m="992980">not</span> <span m="993790">conservative.</span>
  <span m="996430">Any</span> <span m="996860">question</span> <span m="997210">on</span>
  <span m="997350">why</span> <span m="997670">we</span> <span m="997830">do</span>
  <span m="998304">finite</span> <span m="998778">volume?</span> <span m="1006020">So</span>
  <span m="1006150">this</span> <span m="1006330">is</span> <span m="1006440">why</span>
  <span m="1006780">we</span> <span m="1006910">do</span> <span m="1007050">finite</span>
  <span m="1007230">volume.</span></p><p><span m="1008100">And</span> <span m="1008430">the</span>
  <span m="1008870">next</span> <span m="1009510">question</span> <span m="1010920">is</span>
  <span m="1011270">another</span> <span m="1011990">question,</span> <span m="1013660">probably,</span>
  <span m="1014180">you</span> <span m="1014340">have</span> <span m="1014760">when</span>
  <span m="1015756">you are</span> <span m="1016254">going</span> <span m="1016752">through</span>
  <span m="1017250">the</span> <span m="1017340">last</span> <span m="1017660">lecture</span>
  <span m="1018710">and</span> <span m="1018940">reading</span> <span m="1019220">through</span>
  <span m="1019360">the</span> <span m="1019450">material</span> <span m="1020900">is,</span>
  <span m="1021160">why</span> <span m="1021780">the</span> <span m="1021900">hell</span>
  <span m="1022110">do</span> <span m="1022180">we</span> <span m="1022330">do</span>
  <span m="1023320">upwind?</span> <span m="1024092">Why</span> <span m="1024480">do</span>
  <span m="1024690">we</span> <span m="1024920">look</span> <span m="1025349">at</span>
  <span m="1025740">the upwind</span> <span m="1026453">direction?</span></p><p><span
  m="1027839">So</span> <span m="1028000">the</span> <span m="1028109">upwind</span>
  <span m="1028319">of</span> <span m="1028849">flux</span> <span m="1029460">is</span>
  <span m="1030170">this.</span> <span m="1031200">So</span> <span m="1031400">we</span>
  <span m="1031579">look</span> <span m="1031859">at</span> <span m="1032475">a</span>
  <span m="1032810">few</span> <span m="1032910">volumes.</span> <span m="1034690">k
  minus</span> <span m="1035020">1,</span> <span m="1036359">k</span> <span m="1036450">plus</span>
  <span m="1036750">1.</span> <span m="1037990">The</span> <span m="1038089">finite</span>
  <span m="1038230">volume,</span> <span m="1040200">we</span> <span m="1040550">store</span>
  <span m="1040950">the</span> <span m="1041030">average</span> <span m="1041450">value</span>
  <span m="1041710">in the</span> <span m="1042034">volumes.</span> <span m="1042750">So</span>
  <span m="1042869">we</span> <span m="1043010">have</span> <span m="1043349">k</span>
  <span m="1043400">minus</span> <span m="1043730">1/2</span> <span m="1044530">and
  k</span> <span m="1044810">plus</span> <span m="1045060">1/2</span> <span m="1045680">as</span>
  <span m="1046117">the</span> <span m="1047430">volume</span> <span m="1047680">interfaces</span>
  <span m="1048440">or</span> <span m="1048580">the</span> <span m="1048690">cell</span>
  <span m="1048980">interfaces.</span> <span m="1051430">And the</span> <span m="1051900">upwind</span>
  <span m="1052220">flux</span> <span m="1052750">is</span> <span m="1052920">basically</span>
  <span m="1053300">saying</span> <span m="1053850">F</span> <span m="1054940">at</span>
  <span m="1055320">k</span> <span m="1055940">minus</span> <span m="1056390">1/2</span>
  <span m="1057930">is</span> <span m="1058280">either</span> <span m="1059840">the</span>
  <span m="1060070">F</span> <span m="1060640">of</span> <span m="1061690">rho</span>
  <span m="1062860">at</span> <span m="1063300">k minus</span> <span m="1063740">1</span>
  <span m="1064970">or</span> <span m="1065340">F</span> <span m="1065685">of</span>
  <span m="1066030">rho</span> <span m="1066500">at</span> <span m="1066890">k,</span>
  <span m="1068740">depending</span> <span m="1069290">on</span> <span m="1069670">where</span>
  <span m="1070110">the</span> <span m="1070240">wind</span> <span m="1070610">comes</span>
  <span m="1070960">from,</span> <span m="1073530">depending</span> <span m="1074120">on</span>
  <span m="1075860">if,</span> <span m="1078224">should</span> <span m="1078700">say--</span>
  <span m="1081200">let</span> <span m="1082160">me</span> <span m="1082300">use</span>
  <span m="1083860">C</span> <span m="1084220">as</span> <span m="1084630">the</span>
  <span m="1086750">speed</span> <span m="1086990">of</span> <span m="1087120">the</span>
  <span m="1087210">wind.</span></p><p><span m="1088100">So</span> <span m="1088320">if</span>
  <span m="1088700">c</span> <span m="1088970">is</span> <span m="1089180">greater</span>
  <span m="1089590">than</span> <span m="1089840">zero,</span> <span m="1090390">the</span>
  <span m="1090590">winds</span> <span m="1091040">have</span> <span m="1091450">positive</span>
  <span m="1092100">speed,</span> <span m="1093500">which</span> <span m="1094440">means</span>
  <span m="1094690">the</span> <span m="1095070">wind</span> <span m="1095450">goes</span>
  <span m="1095710">towards</span> <span m="1095780">the</span> <span m="1096050">right.</span>
  <span m="1096807">And then</span> <span m="1097294">you look at</span> <span m="1097781">the
  upwind</span> <span m="1098268">direction,</span> <span m="1098755">you should be</span>
  <span m="1099242">looking at</span> <span m="1102620">when</span> <span m="1102840">you</span>
  <span m="1102970">are</span> <span m="1103040">computing the</span> <span m="1103520">upwind</span>
  <span m="1104000">value</span> <span m="1105167">of</span> <span m="1105544">the</span>
  <span m="1105921">plus</span> <span m="1106300">[INAUDIBLE]</span> <span m="1106710">minus
  2,</span> <span m="1107186">you should</span> <span m="1107662">look</span> <span
  m="1108138">towards the</span> <span m="1108614">left,</span> <span m="1109090">[INAUDIBLE].</span>
  <span m="1110994">So</span> <span m="1111470">when</span> <span m="1111980">k</span>
  <span m="1112510">is</span> <span m="1113010">greater--</span> <span m="1113630">so</span>
  <span m="1113940">when</span> <span m="1114200">C</span> <span m="1114630">is</span>
  <span m="1115330">less</span> <span m="1115880">than</span> <span m="1116120">0,</span>
  <span m="1120470">that</span> <span m="1120690">means the speed</span> <span m="1121165">of
  the</span> <span m="1121640">wing</span> <span m="1122060">is negative,</span> <span
  m="1124890">opposite</span> <span m="1125290">direction</span> <span m="1125790">is
  towards</span> <span m="1125890">the right.</span> <span m="1126490">The</span>
  <span m="1126976">winds are</span> <span m="1127462">[INAUDIBLE]</span> <span m="1130864">opposite</span>
  <span m="1131350">direction</span> <span m="1131836">for this,</span> <span m="1132322">you
  should be looking</span> <span m="1132808">at the</span> <span m="1133294">right</span>
  <span m="1133780">and</span> <span m="1134266">use</span> <span m="1134752">the
  k</span> <span m="1135724">value</span> <span m="1136210">instead.</span></p><p><span
  m="1138480">And</span> <span m="1138650">here,</span> <span m="1138900">c is</span>
  <span m="1139380">what?</span> <span m="1140830">c</span> <span m="1141980">is</span>
  <span m="1143630">this.</span> <span m="1145250">c is</span> <span m="1145410">the</span>
  <span m="1145510">c</span> <span m="1145970">that</span> <span m="1146320">appears</span>
  <span m="1147110">in</span> <span m="1149060">this.</span> <span m="1156430">c</span>
  <span m="1156660">is</span> <span m="1156800">the</span> <span m="1156880">value</span>
  <span m="1157850">that</span> <span m="1158510">appears</span> <span m="1160160">in</span>
  <span m="1160350">the</span> <span m="1160460">differential</span> <span m="1161310">form</span>
  <span m="1162440">of</span> <span m="1162770">the</span> <span m="1162980">equation,</span>
  <span m="1163880">over</span> <span m="1164330">here.</span> <span m="1166580">So</span>
  <span m="1167590">as you</span> <span m="1168050">can imagine,</span> <span m="1168510">if</span>
  <span m="1168970">we</span> <span m="1169190">have</span> <span m="1169560">[INAUDIBLE]</span>
  <span m="1170060">like</span> <span m="1170760">the</span> <span m="1171450">[INAUDIBLE]</span>
  <span m="1171810">vacuum</span> <span m="1171980">equation</span> <span m="1172520">we</span>
  <span m="1172700">have,</span> <span m="1174000">this</span> <span m="1174330">c</span>
  <span m="1175100">exactly</span> <span m="1175610">determines</span> <span m="1176610">whether</span>
  <span m="1176890">your</span> <span m="1177090">solution</span> <span m="1177480">moves</span>
  <span m="1177790">towards</span> <span m="1178100">the</span> <span m="1178170">left
  or</span> <span m="1178540">moves</span> <span m="1178850">towards the</span> <span
  m="1179334">right.</span> <span m="1180302">So if</span> <span m="1180786">this</span>
  <span m="1181270">c</span> <span m="1181540">is</span> <span m="1181750">positive,</span>
  <span m="1182160">the</span> <span m="1182605">solution will go to the</span> <span
  m="1183050">right</span> <span m="1183770">and</span> <span m="1183990">winds</span>
  <span m="1184270">go towards</span> <span m="1184570">the</span> <span m="1184800">right.</span>
  <span m="1185792">If</span> <span m="1186288">c is negative,</span> <span m="1186784">it</span>
  <span m="1187280">goes</span> <span m="1187730">the opposite</span> <span m="1187970">direction.</span></p><p><span
  m="1189830">But</span> <span m="1190270">in</span> <span m="1190660">general,</span>
  <span m="1191150">in</span> <span m="1191270">a</span> <span m="1191330">conservation</span>
  <span m="1192050">law,</span> <span m="1192320">how</span> <span m="1192770">do</span>
  <span m="1192960">we</span> <span m="1193270">convert</span> <span m="1194890">our</span>
  <span m="1195290">conservation</span> <span m="1196130">law,</span> <span m="1196400">which</span>
  <span m="1196760">is</span> <span m="1197400">partial F</span> <span m="1198330">rho</span>
  <span m="1198820">partial</span> <span m="1199120">x</span> <span m="1199990">equal</span>
  <span m="1200270">to</span> <span m="1200370">0,</span> <span m="1200840">into</span>
  <span m="1201000">to</span> <span m="1201120">that</span> <span m="1201360">form?</span>
  <span m="1201910">But</span> <span m="1202060">if</span> <span m="1202200">we</span>
  <span m="1202590">convert</span> <span m="1202820">this</span> <span m="1203245">into</span>
  <span m="1203670">this one,</span> <span m="1204150">what</span> <span m="1204540">is</span>
  <span m="1204800">c?</span> <span m="1209430">Can</span> <span m="1209900">we</span>
  <span m="1210040">always</span> <span m="1210420">convert</span> <span m="1212650">the</span>
  <span m="1213542">conservative</span> <span m="1214440">form</span> <span m="1215080">into
  this,</span> <span m="1216950">like</span> <span m="1217240">a</span> <span m="1217370">vacuum</span>
  <span m="1217800">scheme</span> <span m="1218282">looks like,</span> <span m="1219246">leaving</span>
  <span m="1219730">a vacuum</span> <span m="1220030">looking like</span> <span m="1220529">form?</span></p><p><span
  m="1223523">AUDIENCE: Just</span> <span m="1224022">take the</span> <span m="1224521">derivative.</span></p><p><span
  m="1225020">QIQI WANG: I</span> <span m="1225520">just</span> <span m="1225770">take</span>
  <span m="1226010">the</span> <span m="1226210">derivative,</span> <span m="1226920">exactly.</span>
  <span m="1227440">If</span> <span m="1227560">I</span> <span m="1227680">take</span>
  <span m="1228010">c</span> <span m="1229110">equal</span> <span m="1229480">to</span>
  <span m="1229590">partial--</span> <span m="1230480">not</span> <span m="1230740">partial.</span>
  <span m="1231750">I do</span> <span m="1232200">too</span> <span m="1232650">many</span>
  <span m="1232840">pd''s.</span> <span m="1234480">dF</span> <span m="1236100">d
  rho,</span> <span m="1238210">then</span> <span m="1238450">I</span> <span m="1238530">get</span>
  <span m="1238700">my</span> <span m="1238840">C.</span> <span m="1240500">In</span>
  <span m="1240640">the</span> <span m="1241020">Burger''s</span> <span m="1241220">equations,</span>
  <span m="1241670">c</span> <span m="1241940">is</span> <span m="1242210">[INAUDIBLE]</span>
  <span m="1242620">rho</span> <span m="1243555">because</span> <span m="1244560">F</span>
  <span m="1244930">is</span> <span m="1245370">equal</span> <span m="1245690">to</span>
  <span m="1246070">half</span> <span m="1246280">of</span> <span m="1246760">rho</span>
  <span m="1247100">square,</span> <span m="1247330">right?</span> <span m="1248590">So</span>
  <span m="1249010">when</span> <span m="1249310">I</span> <span m="1249390">take</span>
  <span m="1249600">derivative,</span> <span m="1250070">I just</span> <span m="1250280">get</span>
  <span m="1250700">[INAUDIBLE].</span> <span m="1251445">As you</span> <span m="1251880">see</span>
  <span m="1252300">if</span> <span m="1252480">you''re</span> <span m="1252580">looking
  at</span> <span m="1252810">all</span> <span m="1252970">the</span> <span m="1253470">equations,</span>
  <span m="1253970">you''ll see</span> <span m="1254300">what</span> <span m="1254410">we</span>
  <span m="1254530">did</span> <span m="1254790">[INAUDIBLE].</span></p><p><span m="1257530">And</span>
  <span m="1257970">by</span> <span m="1258300">the way, you</span> <span m="1258420">may
  be</span> <span m="1258890">thinking</span> <span m="1259368">of</span> <span m="1259846">why
  did</span> <span m="1260324">I</span> <span m="1260802">use these</span> <span m="1261280">here.</span>
  <span m="1261758">Because</span> <span m="1262720">if</span> <span m="1262880">you</span>
  <span m="1262990">look</span> <span m="1263210">at</span> <span m="1263670">a</span>
  <span m="1263925">gas</span> <span m="1264240">dynamic</span> <span m="1264820">equation,</span>
  <span m="1266010">the</span> <span m="1266110">C</span> <span m="1266480">you</span>
  <span m="1266800">get</span> <span m="1267210">is</span> <span m="1267600">going
  to be the</span> <span m="1268067">speed of</span> <span m="1268534">sound.</span>
  <span m="1271340">OK.</span></p><p><span m="1273500">OK.</span> <span m="1273870">Why</span>
  <span m="1274130">do</span> <span m="1274250">we</span> <span m="1274400">need</span>
  <span m="1274490">do</span> <span m="1275650">upwind?</span> <span m="1278140">I
  mean,</span> <span m="1278420">the</span> <span m="1278790">real</span> <span m="1279480">mathematical</span>
  <span m="1280550">reason</span> <span m="1281280">is</span> <span m="1281490">something</span>
  <span m="1281920">I''m</span> <span m="1282920">going</span> <span m="1283080">to</span>
  <span m="1283150">talk</span> <span m="1283470">about</span> <span m="1283910">[INAUDIBLE].</span>
  <span m="1284750">But,</span> <span m="1285170">like,</span> <span m="1285590">I</span>
  <span m="1285730">think</span> <span m="1287770">Dr.</span> <span m="1287960">[?
  Vikram ?]</span> <span m="1288110">[? Dag ?]</span> <span m="1288860">is</span>
  <span m="1289020">going</span> <span m="1289160">to</span> <span m="1289240">be</span>
  <span m="1289390">giving</span> <span m="1289620">the</span> <span m="1289710">lecture</span>
  <span m="1290230">right</span> <span m="1290490">after</span> <span m="1290630">the
  midterm.</span></p><p><span m="1291590">But</span> <span m="1291780">he''s</span>
  <span m="1292060">going</span> <span m="1292200">to</span> <span m="1292280">talking</span>
  <span m="1292520">about</span> <span m="1292930">stability.</span> <span m="1293710">And</span>
  <span m="1294160">this</span> <span m="1294330">is</span> <span m="1294490">for</span>
  <span m="1294720">stability.</span> <span m="1295630">I''m</span> <span m="1295790">just</span>
  <span m="1295970">going</span> <span m="1296130">to</span> <span m="1296960">demonstrate</span>
  <span m="1297770">it</span> <span m="1301190">empirically</span> <span m="1303010">in</span>
  <span m="1303935">the</span> <span m="1304330">shared</span> <span m="1304720">folder</span>
  <span m="1305160">we</span> <span m="1305440">had--</span> <span m="1307130">not</span>
  <span m="1307360">this</span> <span m="1307570">one--</span> <span m="1309780">we</span>
  <span m="1309970">had</span> <span m="1310290">from</span> <span m="1310570">last</span>
  <span m="1311015">lecture.</span></p><p><span m="1311460">OK.</span> <span m="1312250">So</span>
  <span m="1312420">I</span> <span m="1312510">had</span> <span m="1312700">a</span>
  <span m="1312760">driver</span> <span m="1313350">here.</span> <span m="1314500">And</span>
  <span m="1314780">I</span> <span m="1314960">have</span> <span m="1315220">a</span>
  <span m="1315320">bunch</span> <span m="1315630">of</span> <span m="1315800">people''s</span>
  <span m="1316110">schemes.</span> <span m="1317232">Who''s</span> <span m="1317700">scheme</span>
  <span m="1318010">is</span> <span m="1318080">working</span> <span m="1318510">by</span>
  <span m="1318630">the</span> <span m="1318730">way?</span> <span m="1319420">Who</span>
  <span m="1319840">knows?</span> <span m="1320680">Which</span> <span m="1320890">one
  of</span> <span m="1321160">them should</span> <span m="1321430">I</span> <span
  m="1321590">use?</span> <span m="1324920">Who</span> <span m="1325910">kind</span>
  <span m="1326303">of</span> <span m="1326696">knows</span> <span m="1327090">more
  or</span> <span m="1327130">less</span> <span m="1327874">your</span> <span m="1328308">script</span>
  <span m="1328742">is working?</span> <span m="1329610">OK.</span> <span m="1330140">Yours?</span>
  <span m="1330530">OK.</span> <span m="1331778">[INAUDIBLE]</span></p><p><span m="1332766">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="1336718">QIQI WANG: OK.</span> <span m="1337710">All
  right.</span> <span m="1338070">So</span> <span m="1338450">I''m going to</span>
  <span m="1338930">change</span> <span m="1339660">this</span> <span m="1339950">to--</span>
  <span m="1344690">OK.</span> <span m="1345790">Thanks.</span> <span m="1347200">So</span>
  <span m="1347440">I</span> <span m="1347550">can</span> <span m="1347800">run</span>
  <span m="1348070">it</span> <span m="1348180">here.</span> <span m="1351290">And</span>
  <span m="1351630">I</span> <span m="1351690">get</span> <span m="1352140">a</span>
  <span m="1353900">solution.</span> <span m="1354710">I</span> <span m="1354760">mean,</span>
  <span m="1354880">you</span> <span m="1355460">probably</span> <span m="1355720">didn''t</span>
  <span m="1355980">treat</span> <span m="1356110">the</span> <span m="1356200">boundary</span>
  <span m="1356470">condition</span> <span m="1356860">correctly,</span> <span m="1357360">but</span>
  <span m="1357420">that''s</span> <span m="1357580">fine.</span></p><p><span m="1358760">So</span>
  <span m="1358980">there</span> <span m="1359190">is</span> <span m="1359490">something</span>
  <span m="1359890">on</span> <span m="1359970">the</span> <span m="1360040">boundary</span>
  <span m="1360550">that</span> <span m="1360790">is</span> <span m="1363810">not</span>
  <span m="1364100">working</span> <span m="1364410">correctly.</span> <span m="1365420">I</span>
  <span m="1365480">think</span> <span m="1365750">that</span> <span m="1365870">you</span>
  <span m="1366040">might</span> <span m="1366500">have</span> <span m="1366970">set</span>
  <span m="1367250">the</span> <span m="1367880">[INAUDIBLE]</span> <span m="1368255">here</span>
  <span m="1368630">to be</span> <span m="1369111">0.</span> <span m="1370073">So
  you</span> <span m="1370554">just set the</span> <span m="1371035">[INAUDIBLE]</span>
  <span m="1371516">here to be 0</span> <span m="1371997">instead</span> <span m="1372478">of</span>
  <span m="1373440">[INAUDIBLE]</span> <span m="1373930">the</span> <span m="1374430">[INAUDIBLE]</span>
  <span m="1374765">blowing</span> <span m="1375100">with</span> <span m="1375580">the</span>
  <span m="1376060">[INAUDIBLE].</span> <span m="1377980">Because</span> <span m="1378940">I''m</span>
  <span m="1379180">having</span> <span m="1379340">a</span> <span m="1379550">[INAUDIBLE]</span>
  <span m="1380110">find</span> <span m="1380390">the</span> <span m="1380460">word,</span>
  <span m="1380690">so</span> <span m="1381560">[INAUDIBLE],</span> <span m="1382450">right?</span>
  <span m="1383450">[INAUDIBLE].</span> <span m="1384950">But</span> <span m="1385450">that''s</span>
  <span m="1385950">fine.</span></p><p><span m="1387540">OK.</span> <span m="1389710">So</span>
  <span m="1390060">I</span> <span m="1390330">think</span> <span m="1391420">it</span>
  <span m="1391560">should</span> <span m="1391910">be</span> <span m="1392060">relatively</span>
  <span m="1392640">easy</span> <span m="1392920">to</span> <span m="1393480">modify.</span>
  <span m="1395480">F--</span> <span m="1397980">yeah,</span> <span m="1398420">yeah,</span>
  <span m="1398770">yeah.</span> <span m="1399390">OK.</span> <span m="1399690">So</span>
  <span m="1399850">I</span> <span m="1399930">just</span> <span m="1400120">need</span>
  <span m="1400290">to</span> <span m="1400430">treat</span> <span m="1401200">the</span>
  <span m="1401330">last</span> <span m="1401680">one.</span> <span m="1402000">So</span>
  <span m="1402260">F_k_plus_half(and),</span> <span m="1407070">right?</span> <span
  m="1408620">The</span> <span m="1408760">last</span> <span m="1409000">one</span>
  <span m="1409340">is</span> <span m="1409610">equal</span> <span m="1410000">to--</span>
  <span m="1412800">OK.</span> <span m="1413130">I</span> <span m="1413190">will</span>
  <span m="1413320">just</span> <span m="1413520">cheat</span> <span m="1413750">here,</span>
  <span m="1415579">F_bad_k(and).</span> <span m="1418060">Because</span> <span m="1418360">I</span>
  <span m="1418440">know</span> <span m="1418600">my</span> <span m="1418750">solution</span>
  <span m="1419150">is</span> <span m="1419390">positive,</span> <span m="1419700">so
  I</span> <span m="1419960">just</span> <span m="1420220">take</span> <span m="1421950">the
  left</span> <span m="1422240">one.</span></p><p><span m="1426940">OK.</span> <span
  m="1427240">So</span> <span m="1427540">here</span> <span m="1427870">is</span>
  <span m="1428210">k_plus_half.</span></p><p><span m="1430130">AUDIENCE: That</span>
  <span m="1430610">should have</span> <span m="1431090">taken care of--</span></p><p><span
  m="1431570">QIQI WANG: Oh,</span> <span m="1431780">that</span> <span m="1432020">should</span>
  <span m="1432190">have</span> <span m="1432380">taken</span> <span m="1432780">care</span>
  <span m="1433140">of that.</span></p><p><span m="1434566">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="1449008">AUDIENCE: [INAUDIBLE]</span></p><p><span m="1452520">QIQI WANG: Sorry?</span>
  <span m="1456520">k_plus_half</span> <span m="1457020">of</span> <span m="1457520">i</span>
  <span m="1457973">minus--</span> <span m="1459700">that</span> <span m="1459900">is</span>
  <span m="1460070">end,</span> <span m="1460530">right?</span></p><p><span m="1460850">AUDIENCE:
  Yeah.</span> <span m="1461327">That''s</span> <span m="1461804">[INAUDIBLE].</span></p><p><span
  m="1464670">QIQI WANG: I</span> <span m="1464800">think</span> <span m="1465460">you</span>
  <span m="1465610">shouldn''t</span> <span m="1466150">be--</span> <span m="1468800">F_bar_k,</span>
  <span m="1469680">right?</span> <span m="1472650">OK.</span> <span m="1473500">And</span>
  <span m="1474100">else</span> <span m="1477750">it</span> <span m="1477940">is</span>
  <span m="1478260">equal</span> <span m="1478746">to</span> <span m="1480690">F_bar_k(1),</span>
  <span m="1483300">right?</span> <span m="1486760">OK.</span> <span m="1487100">So</span>
  <span m="1487270">let''s</span> <span m="1487560">see</span> <span m="1487740">if</span>
  <span m="1487840">that</span> <span m="1488010">works.</span></p><p><span m="1491450">Oh,</span>
  <span m="1491590">that</span> <span m="1491730">works.</span> <span m="1492110">OK,</span>
  <span m="1492470">nice.</span> <span m="1493350">OK.</span> <span m="1493910">So</span>
  <span m="1494100">we</span> <span m="1494410">have</span> <span m="1494600">this</span>
  <span m="1494660">scheme</span> <span m="1495000">over</span> <span m="1495240">here.</span>
  <span m="1495750">We</span> <span m="1495900">have</span> <span m="1496130">an</span>
  <span m="1496320">upwinding</span> <span m="1496680">scheme.</span> <span m="1497860">So</span>
  <span m="1499150">as</span> <span m="1499410">we</span> <span m="1499650">did in</span>
  <span m="1500140">finite</span> <span m="1501090">[INAUDIBLE],</span> <span m="1501620">will</span>
  <span m="1501760">know</span> <span m="1502030">that</span> <span m="1502930">backward</span>
  <span m="1503440">in</span> <span m="1503580">space</span> <span m="1504160">or</span>
  <span m="1504950">forward</span> <span m="1505230">in</span> <span m="1505530">space</span>
  <span m="1506120">anything</span> <span m="1506530">you</span> <span m="1506640">[INAUDIBLE]</span>
  <span m="1507560">have</span> <span m="1507930">a</span> <span m="1508490">one-sided</span>
  <span m="1508700">[INAUDIBLE],</span> <span m="1509380">you</span> <span m="1509540">get</span>
  <span m="1510280">first</span> <span m="1510650">order</span> <span m="1511110">accuracy.</span></p><p><span
  m="1512990">But</span> <span m="1513170">if</span> <span m="1513290">you</span>
  <span m="1513460">take</span> <span m="1513780">essential</span> <span m="1514340">difference</span>
  <span m="1515250">or</span> <span m="1515390">take</span> <span m="1516040">the</span>
  <span m="1516180">average</span> <span m="1517380">of</span> <span m="1517690">left</span>
  <span m="1517950">and</span> <span m="1518100">right,</span> <span m="1518380">you</span>
  <span m="1518470">get</span> <span m="1518710">secondary</span> <span m="1519450">accuracy.</span>
  <span m="1520410">So</span> <span m="1520590">why</span> <span m="1520890">don''t</span>
  <span m="1521050">we</span> <span m="1521260">use</span> <span m="1521520">that?</span>
  <span m="1523050">I''m</span> <span m="1523260">going</span> <span m="1523420">to</span>
  <span m="1523500">change</span> <span m="1523860">your</span> <span m="1523990">code</span>
  <span m="1526020">to</span> <span m="1526270">do</span> <span m="1526560">exactly</span>
  <span m="1527120">that.</span></p><p><span m="1528020">I''m</span> <span m="1528250">going</span>
  <span m="1528480">to</span> <span m="1528780">instead</span> <span m="1529340">of</span>
  <span m="1529520">doing</span> <span m="1529830">all</span> <span m="1530080">this</span>
  <span m="1530310">conditional</span> <span m="1531120">thing,</span> <span m="1531590">I''m</span>
  <span m="1531760">just</span> <span m="1531930">going</span> <span m="1532080">to</span>
  <span m="1532280">do</span> <span m="1533910">this</span> <span m="1534440">is</span>
  <span m="1534780">equal</span> <span m="1535170">to</span> <span m="1535490">half</span>
  <span m="1537620">of</span> <span m="1541210">F_bar_k</span> <span m="1542180">and</span>
  <span m="1542470">F_bar_k</span> <span m="1543360">plus</span> <span m="1543670">1.</span>
  <span m="1548040">This</span> <span m="1548290">thing''s</span> <span m="1548520">divided</span>
  <span m="1548770">by</span> <span m="1548880">2.</span> <span m="1549960">So</span>
  <span m="1550210">I''m</span> <span m="1550320">not</span> <span m="1550600">going</span>
  <span m="1550790">to</span> <span m="1551540">be</span> <span m="1551710">using</span>
  <span m="1552060">your</span> <span m="1552230">conditions.</span> <span m="1553100">I''m</span>
  <span m="1553280">just</span> <span m="1553420">going</span> <span m="1553580">to</span>
  <span m="1553830">do</span> <span m="1554650">k_plus_half</span> <span m="1555120">equal</span>
  <span m="1555590">to</span> <span m="1556320">actually</span> <span m="1556840">k_plus_half,</span>
  <span m="1558280">k_plus</span> <span m="1560120">k_plus</span> <span m="1560360">over</span>
  <span m="1560720">2.</span></p><p><span m="1562550">And</span> <span m="1563110">instead</span>
  <span m="1563530">of</span> <span m="1563690">doing</span> <span m="1564010">this</span>
  <span m="1564690">condition--</span> <span m="1567500">apologize</span> <span m="1568120">first</span>
  <span m="1568390">for</span> <span m="1568860">going</span> <span m="1569050">to</span>
  <span m="1569140">make</span> <span m="1569370">the</span> <span m="1569767">[INAUDIBLE]</span>
  <span m="1570960">unstable.</span> <span m="1571940">But</span> <span m="1572593">k_plus_half(and)</span>
  <span m="1575610">is</span> <span m="1575940">going</span> <span m="1576110">to</span>
  <span m="1576200">be</span> <span m="1576530">F_bar_k(and)</span> <span m="1578956">plus</span>
  <span m="1579690">F_bar_k(1)</span> <span m="1584000">divide</span> <span m="1584260">by</span>
  <span m="1584390">2.</span> <span m="1585200">So</span> <span m="1585280">now</span>
  <span m="1585950">if</span> <span m="1586120">I</span> <span m="1586240">do</span>
  <span m="1586420">this,</span> <span m="1586860">I</span> <span m="1587000">always</span>
  <span m="1587560">set</span> <span m="1589530">the</span> <span m="1589710">interface</span>
  <span m="1590330">value</span> <span m="1590690">to</span> <span m="1590820">be</span>
  <span m="1590940">the</span> <span m="1591090">average</span> <span m="1591960">between</span>
  <span m="1592310">the</span> <span m="1592410">two</span> <span m="1592710">[INAUDIBLE].</span>
  <span m="1593810">What</span> <span m="1593980">do</span> <span m="1594130">I</span>
  <span m="1594230">get?</span></p><p><span m="1598240">Now,</span> <span m="1598590">it</span>
  <span m="1598930">looks</span> <span m="1599180">like</span> <span m="1599450">correct.</span>
  <span m="1599980">Oh.</span> <span m="1603162">All</span> <span m="1603630">right.</span>
  <span m="1604650">So</span> <span m="1604900">what</span> <span m="1605240">we</span>
  <span m="1605450">see</span> <span m="1605600">here?</span> <span m="1605920">We</span>
  <span m="1606263">see here</span> <span m="1606950">in</span> <span m="1607150">the</span>
  <span m="1607230">beginning,</span> <span m="1608020">it</span> <span m="1608160">looks</span>
  <span m="1608380">fine.</span> <span m="1609130">Let''s</span> <span m="1610930">look</span>
  <span m="1612180">more</span> <span m="1612470">carefully</span> <span m="1613060">what</span>
  <span m="1613400">actually</span> <span m="1613790">happens.</span></p><p><span
  m="1614690">Let''s</span> <span m="1615060">set</span> <span m="1615190">dt</span>
  <span m="1616080">equal</span> <span m="1616510">to</span> <span m="1616680">0.001</span>
  <span m="1617990">to</span> <span m="1618190">be</span> <span m="1618370">more--</span>
  <span m="1619070">let''s</span> <span m="1619240">see what</span> <span m="1619330">happens.</span>
  <span m="1620130">OK.</span> <span m="1620770">Usually,</span> <span m="1621330">the</span>
  <span m="1621850">evolution-</span> <span m="1622890">let</span> <span m="1623430">me</span>
  <span m="1623520">[INAUDIBLE]</span> <span m="1624100">it,</span> <span m="1624250">so</span>
  <span m="1624400">it</span> <span m="1624560">doesn''t</span> <span m="1624890">[INAUDIBLE].</span>
  <span m="1628100">[INAUDIBLE]</span> <span m="1629110">I''m</span> <span m="1629390">going</span>
  <span m="1629560">to</span> <span m="1629640">do</span> <span m="1629980">ylim(0,2),</span>
  <span m="1633620">so</span> <span m="1633760">that</span> <span m="1633940">doesn''t</span>
  <span m="1634400">[INAUDIBLE].</span> <span m="1636530">OK.</span></p><p><span m="1637980">In
  the beginning,</span> <span m="1638316">we</span> <span m="1638652">see</span> <span
  m="1638990">it</span> <span m="1639446">is</span> <span m="1639902">behaving</span>
  <span m="1640358">correctly.</span> <span m="1641270">And I</span> <span m="1641450">am</span>
  <span m="1641900">probably</span> <span m="1642190">getting</span> <span m="1642350">secondary</span>
  <span m="1643430">accuracy, right?</span> <span m="1646345">But</span> <span m="1646816">as</span>
  <span m="1647290">soon</span> <span m="1647545">as</span> <span m="1648090">the</span>
  <span m="1648250">[INAUDIBLE]</span> <span m="1648680">is</span> <span m="1649000">formed,</span>
  <span m="1649810">something</span> <span m="1650280">bad</span> <span m="1650750">is
  going</span> <span m="1651220">to happen.</span> <span m="1653100">Now,</span> <span
  m="1653570">[INAUDIBLE].</span> <span m="1656838">All right.</span> <span m="1658329">[INAUDIBLE].</span></p><p><span
  m="1664293">So, yeah.</span> <span m="1666300">So we''ve</span> <span m="1666450">got</span>
  <span m="1666670">these</span> <span m="1666910">calculations.</span> <span m="1669214">And</span>
  <span m="1669695">it looks</span> <span m="1670176">pretty</span> <span m="1670657">much</span>
  <span m="1671140">like</span> <span m="1671893">in</span> <span m="1672306">[INAUDIBLE]</span>
  <span m="1672720">analysis</span> <span m="1673211">you</span> <span m="1673702">get</span>
  <span m="1674193">this</span> <span m="1675670">[INAUDIBLE]</span> <span m="1676280">phenomenon,</span>
  <span m="1676750">like</span> <span m="1677730">right</span> <span m="1678070">or</span>
  <span m="1678240">wrong</span> <span m="1679156">[INAUDIBLE].</span> <span m="1681700">So</span>
  <span m="1681860">this</span> <span m="1682100">is</span> <span m="1682270">actually</span>
  <span m="1682780">why</span> <span m="1683130">we</span> <span m="1685060">need</span>
  <span m="1685360">to</span> <span m="1685480">take</span> <span m="1685876">an</span>
  <span m="1686272">upwinding</span> <span m="1686670">scheme,</span> <span m="1691390">especially</span>
  <span m="1692020">if</span> <span m="1692310">you have</span> <span m="1692780">a</span>
  <span m="1693250">nonlinear</span> <span m="1693720">differential</span> <span m="1694190">equation</span>
  <span m="1695600">with</span> <span m="1696050">potentially</span> <span m="1696513">shock</span>
  <span m="1696976">waves.</span></p><p><span m="1702260">I</span> <span m="1702510">mean,</span>
  <span m="1702690">if</span> <span m="1702800">you</span> <span m="1702890">go</span>
  <span m="1703060">to</span> <span m="1703430">math</span> <span m="1703680">class,</span>
  <span m="1704050">I can</span> <span m="1704610">probably</span> <span m="1705480">talk</span>
  <span m="1705820">more</span> <span m="1706200">about</span> <span m="1707490">shock</span>
  <span m="1707840">waves</span> <span m="1708150">being</span> <span m="1708400">a</span>
  <span m="1708870">dissipated</span> <span m="1709340">phenomenon</span> <span m="1710280">and</span>
  <span m="1710750">a</span> <span m="1712280">second</span> <span m="1712610">order</span>
  <span m="1712870">scheme,</span> <span m="1713100">like</span> <span m="1713280">essential</span>
  <span m="1713330">difference</span> <span m="1713820">that</span> <span m="1714225">has</span>
  <span m="1714630">no</span> <span m="1714960">numerical</span> <span m="1715330">dissipation.</span>
  <span m="1715773">And</span> <span m="1716216">you need the</span> <span m="1716659">numerical</span>
  <span m="1717102">dissipation</span> <span m="1717545">[INAUDIBLE].</span> <span
  m="1720350">I''m</span> <span m="1720760">just</span> <span m="1720950">going</span>
  <span m="1721050">to</span> <span m="1721180">demonstrate</span> <span m="1721690">numerically.</span></p><p><span
  m="1722550">This</span> <span m="1723250">type</span> <span m="1723430">of</span>
  <span m="1723550">thing</span> <span m="1723680">is</span> <span m="1723800">going</span>
  <span m="1723930">to</span> <span m="1723990">happen</span> <span m="1724350">if</span>
  <span m="1724550">we</span> <span m="1724780">don''t</span> <span m="1725140">do</span>
  <span m="1725380">upwinding</span> <span m="1725970">and</span> <span m="1726150">you</span>
  <span m="1726240">have</span> <span m="1726390">shock</span> <span m="1726720">wave.</span>
  <span m="1729750">So</span> <span m="1730000">for</span> <span m="1730670">something</span>
  <span m="1730980">that</span> <span m="1731110">doesn''t</span> <span m="1731390">have</span>
  <span m="1731530">shock wave</span> <span m="1732020">it''s</span> <span m="1732620">probably</span>
  <span m="1734100">fine</span> <span m="1734580">as</span> <span m="1734770">long
  as</span> <span m="1734810">you use</span> <span m="1735636">an</span> <span m="1736050">appropriate</span>
  <span m="1736720">time</span> <span m="1736890">integrator.</span> <span m="1738650">OK.</span>
  <span m="1739365">So</span> <span m="1739740">today--</span> <span m="1741920">I
  mean,</span> <span m="1742250">this</span> <span m="1742420">is</span> <span m="1742790">why</span>
  <span m="1743210">upwinding--</span> <span m="1744290">we are</span> <span m="1744430">going</span>
  <span m="1744650">to</span> <span m="1744720">be</span> <span m="1744810">doing</span>
  <span m="1745080">something</span> <span m="1745440">like</span> <span m="1745660">this.</span></p><p><span
  m="1748690">So I tried</span> <span m="1748920">to</span> <span m="1749060">stimulate</span>
  <span m="1749685">distance.</span> <span m="1753976">This is</span> <span m="1754448">a
  lot</span> <span m="1754920">of parts,</span> <span m="1755240">right?</span> <span
  m="1756880">And if</span> <span m="1757190">you</span> <span m="1757670">do</span>
  <span m="1758150">a simulation</span> <span m="1758405">of</span> <span m="1758660">individual</span>
  <span m="1759129">parts,</span> <span m="1759598">yeah,</span> <span m="1760067">you</span>
  <span m="1760536">can do this.</span> <span m="1761005">But</span> <span m="1761239">[INAUDIBLE]</span>
  <span m="1761474">this</span> <span m="1761943">[INAUDIBLE]</span> <span m="1763350">it</span>
  <span m="1763820">really</span> <span m="1764260">looks like--</span> <span m="1765580">I
  mean,</span> <span m="1765870">each</span> <span m="1766015">[INAUDIBLE]</span>
  <span m="1766160">more</span> <span m="1766390">looks</span> <span m="1766660">more
  or</span> <span m="1767110">less like</span> <span m="1767340">a</span> <span m="1767390">molecule.</span></p><p><span
  m="1769086">So</span> <span m="1769558">you really</span> <span m="1770030">get</span>
  <span m="1770502">a</span> <span m="1770974">continuum</span> <span m="1771446">of</span>
  <span m="1771918">cars</span> <span m="1772390">or</span> <span m="1772862">[INAUDIBLE].</span>
  <span m="1773810">And</span> <span m="1774090">one</span> <span m="1774150">of</span>
  <span m="1774590">the</span> <span m="1774740">ideas</span> <span m="1775290">is</span>
  <span m="1775610">to</span> <span m="1775830">instead</span> <span m="1776596">of</span>
  <span m="1776980">treating</span> <span m="1777360">each</span> <span m="1777580">car</span>
  <span m="1778000">as</span> <span m="1778420">an</span> <span m="1778840">individual</span>
  <span m="1779690">agent</span> <span m="1780460">and</span> <span m="1781230">simulate</span>
  <span m="1781850">that,</span> <span m="1782580">we</span> <span m="1782720">just</span>
  <span m="1783030">look at</span> <span m="1784210">from</span> <span m="1784680">a</span>
  <span m="1785620">macroscopic</span> <span m="1786090">point</span> <span m="1786560">of
  view</span> <span m="1787030">and</span> <span m="1787500">simulate</span> <span
  m="1788450">this</span> <span m="1789400">like</span> <span m="1790050">gas</span>
  <span m="1790580">dynamics,</span> <span m="1791030">where</span> <span m="1791970">each</span>
  <span m="1792280">car</span> <span m="1792650">is</span> <span m="1792910">like</span>
  <span m="1793120">a</span> <span m="1793170">molecule.</span> <span m="1794850">OK.</span>
  <span m="1795780">And</span> <span m="1796360">so</span> <span m="1796600">a</span>
  <span m="1796640">macroscopic</span> <span m="1797670">description</span> <span
  m="1798520">of</span> <span m="1799050">the</span> <span m="1799670">cars</span>
  <span m="1800210">on</span> <span m="1800350">a</span> <span m="1800420">highway</span>
  <span m="1801020">is</span> <span m="1801520">just</span> <span m="1802470">P</span>
  <span m="1803310">as</span> <span m="1803550">a</span> <span m="1803610">function</span>
  <span m="1804170">of</span> <span m="1804420">x</span> <span m="1804890">and t,</span>
  <span m="1805360">right?</span></p><p><span m="1806570">So x</span> <span m="1807000">is</span>
  <span m="1807430">space.</span> <span m="1808290">t is</span> <span m="1808720">time.</span>
  <span m="1809385">And</span> <span m="1809700">P</span> <span m="1810090">is</span>
  <span m="1810410">the</span> <span m="1811920">number</span> <span m="1812490">of</span>
  <span m="1812740">cars</span> <span m="1813184">per</span> <span m="1814516">length</span>
  <span m="1815850">of</span> <span m="1816581">the highway.</span> <span m="1818790">So
  P</span> <span m="1819105">is</span> <span m="1819420">a</span> <span m="1819940">converse</span>
  <span m="1820220">quantity,</span> <span m="1820680">because</span> <span m="1820940">cars</span>
  <span m="1821373">are converse,</span> <span m="1821806">right?</span> <span m="1822239">Cars</span>
  <span m="1822672">are</span> <span m="1823105">not</span> <span m="1823540">disappearing</span>
  <span m="1824882">into</span> <span m="1826310">[INAUDIBLE].</span> <span m="1826780">Yeah.</span>
  <span m="1829255">Cars are</span> <span m="1829750">not</span> <span m="1829950">disappearing</span>
  <span m="1830660">as</span> <span m="1831140">airlines</span> <span m="1831600">sometimes</span>
  <span m="1832000">do.</span></p><p><span m="1835928">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="1841820">[INTERPOSING VOICES]</span></p><p><span m="1846239">QIQI WANG: OK.</span>
  <span m="1851450">So</span> <span m="1851620">we</span> <span m="1852090">are</span>
  <span m="1852210">also</span> <span m="1852540">assuming</span> <span m="1855180">the</span>
  <span m="1855330">velocity</span> <span m="1855860">of</span> <span m="1856020">cars</span>
  <span m="1857060">depends</span> <span m="1857470">on</span> <span m="1857590">the</span>
  <span m="1857680">density.</span> <span m="1859420">Well,</span> <span m="1859620">let''s</span>
  <span m="1859760">first</span> <span m="1859990">say</span> <span m="1860420">so</span>
  <span m="1860600">P equal to 0</span> <span m="1862190">is</span> <span m="1862630">an</span>
  <span m="1864710">empty</span> <span m="1865040">highway.</span> <span m="1865940">P
  equal to 1</span> <span m="1867210">is</span> <span m="1867710">this.</span></p><p><span
  m="1869170">OK.</span> <span m="1869960">P equal to 1</span> <span m="1870730">is</span>
  <span m="1871160">like</span> <span m="1871300">a parking lot.</span> <span m="1873112">P
  equal to 1</span> <span m="1874471">is like the</span> <span m="1874930">maximum</span>
  <span m="1876170">density</span> <span m="1876660">you can</span> <span m="1876750">pack</span>
  <span m="1877895">onto</span> <span m="1878310">a</span> <span m="1878410">highway.</span>
  <span m="1879240">OK.</span> <span m="1879730">So</span> <span m="1879920">this</span>
  <span m="1880060">is</span> <span m="1880140">P.</span> <span m="1880990">And</span>
  <span m="1881740">we</span> <span m="1882010">are</span> <span m="1882490">assuming</span>
  <span m="1882800">the</span> <span m="1882950">velocity</span> <span m="1883330">of</span>
  <span m="1883740">the</span> <span m="1883850">cars</span> <span m="1884320">is</span>
  <span m="1884480">a</span> <span m="1884580">functional</span> <span m="1885020">P.</span></p><p><span
  m="1886990">So</span> <span m="1888350">again,</span> <span m="1889120">a</span>
  <span m="1889250">velocity</span> <span m="1889580">equal</span> <span m="1890180">to</span>
  <span m="1890320">0</span> <span m="1890710">is</span> <span m="1890910">like</span>
  <span m="1891140">this.</span> <span m="1891840">So</span> <span m="1893356">this</span>
  <span m="1893770">car</span> <span m="1894010">cannot</span> <span m="1894410">move</span>
  <span m="1894730">when</span> <span m="1895624">the</span> <span m="1896071">density</span>
  <span m="1896518">is</span> <span m="1896965">at</span> <span m="1897412">[INAUDIBLE].</span>
  <span m="1898760">And</span> <span m="1901760">let''s</span> <span m="1902070">pick</span>
  <span m="1902340">the</span> <span m="1902470">unit</span> <span m="1903230">of</span>
  <span m="1903840">velocity,</span> <span m="1904600">so</span> <span m="1904650">that</span>
  <span m="1904860">velocity</span> <span m="1905110">equal to</span> <span m="1905500">1</span>
  <span m="1906380">is</span> <span m="1906600">something</span> <span m="1906940">like</span>
  <span m="1909540">65</span> <span m="1910170">miles</span> <span m="1910500">per</span>
  <span m="1910920">hour,</span> <span m="1911300">where</span> <span m="1912880">you</span>
  <span m="1913100">would</span> <span m="1913320">have--</span> <span m="1914260">or</span>
  <span m="1914510">80--</span> <span m="1915990">where</span> <span m="1916190">you</span>
  <span m="1916450">would be</span> <span m="1916800">driving</span> <span m="1917090">if</span>
  <span m="1918320">there</span> <span m="1918440">is</span> <span m="1918580">no</span>
  <span m="1918790">other</span> <span m="1919010">cars.</span> <span m="1921360">Or</span>
  <span m="1921830">85.</span> <span m="1922300">OK.</span> <span m="1924570">OK.</span>
  <span m="1926690">So</span> <span m="1926830">what</span> <span m="1927150">would</span>
  <span m="1927320">be</span> <span m="1927440">an</span> <span m="1927700">easy</span>
  <span m="1927850">way</span> <span m="1928180">or</span> <span m="1928820">intuitive</span>
  <span m="1929550">way</span> <span m="1929970">you</span> <span m="1930470">would
  model</span> <span m="1930970">u</span> <span m="1931470">as</span> <span m="1931970">a</span>
  <span m="1932470">function</span> <span m="1932970">P?</span></p><p><span m="1934970">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="1940140">QIQI WANG: Yeah.</span> <span m="1940620">It
  can</span> <span m="1941020">be</span> <span m="1941110">more</span> <span m="1941430">curved.</span>
  <span m="1941740">But</span> <span m="1942260">let''s</span> <span m="1942510">make
  it</span> <span m="1942790">simple.</span> <span m="1943800">Did you</span> <span
  m="1943950">want</span> <span m="1944110">to</span> <span m="1944220">[INAUDIBLE]?</span>
  <span m="1945400">So</span> <span m="1946260">would</span> <span m="1946450">you</span>
  <span m="1946550">[INAUDIBLE]</span> <span m="1947210">code</span> <span m="1947520">[INAUDIBLE]</span>
  <span m="1947720">like</span> <span m="1948160">something</span> <span m="1948510">like</span>
  <span m="1948770">this?</span> <span m="1948920">Or</span> <span m="1949100">would
  you</span> <span m="1949520">[INAUDIBLE]</span> <span m="1949940">coding</span>
  <span m="1950360">[INAUDIBLE]</span> <span m="1950780">like</span> <span m="1952490">U(P)=
  1 minus P?</span></p><p><span m="1958600">This</span> <span m="1958890">captures</span>
  <span m="1959390">the</span> <span m="1959490">right</span> <span m="1959720">behavior.</span>
  <span m="1961110">So</span> <span m="1961570">when</span> <span m="1961960">P is
  equal to 0,</span> <span m="1963080">you</span> <span m="1963290">drive</span> <span
  m="1963680">at</span> <span m="1964135">85</span> <span m="1964590">miles per</span>
  <span m="1965045">hour.</span> <span m="1965500">When</span> <span m="1965740">P
  is equal to 1,</span> <span m="1967550">even</span> <span m="1968040">if</span>
  <span m="1968200">you</span> <span m="1968330">want</span> <span m="1968550">to</span>
  <span m="1968660">drive</span> <span m="1969082">faster,</span> <span m="1969926">you''re</span>
  <span m="1970350">stuck,</span> <span m="1970772">right?</span> <span m="1972460">OK.</span>
  <span m="1973350">Now,</span> <span m="1973710">here''s</span> <span m="1974330">my</span>
  <span m="1974610">first</span> <span m="1974960">question.</span> <span m="1975280">What</span>
  <span m="1975490">is</span> <span m="1975650">the</span> <span m="1975760">flux?</span>
  <span m="1982900">What''s</span> <span m="1983330">F(P)?</span></p><p><span m="1990688">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="1993550">QIQI WANG: Integral--</span></p><p><span
  m="1994386">AUDIENCE: [INAUDIBLE]</span></p><p><span m="1998350">QIQI WANG: Yeah.</span>
  <span m="1998600">I</span> <span m="1998670">know</span> <span m="1998820">what</span>
  <span m="1998970">you''re</span> <span m="1999080">thinking.</span> <span m="1999500">You</span>
  <span m="1999740">are</span> <span m="1999890">thinking</span> <span m="2000170">about</span>
  <span m="2001180">U</span> <span m="2001520">being</span> <span m="2001860">the</span>
  <span m="2003138">d</span> <span m="2003564">f</span> <span m="2003990">in</span>
  <span m="2004420">P,</span> <span m="2004745">right?</span> <span m="2005070">So</span>
  <span m="2005330">it</span> <span m="2005550">has to be</span> <span m="2005945">the
  integral.</span> <span m="2006340">But</span> <span m="2007130">that''s</span> <span
  m="2007390">not</span> <span m="2009050">true.</span> <span m="2010360">It''s</span>
  <span m="2010960">easier</span> <span m="2011150">than</span> <span m="2011360">that.</span>
  <span m="2011610">You</span> <span m="2011900">are</span> <span m="2012050">thinking</span>
  <span m="2012470">more--</span> <span m="2012830">you''re</span> <span m="2013281">too
  smart.</span></p><p><span m="2015085">AUDIENCE: [INAUDIBLE]</span></p><p><span m="2016440">QIQI
  WANG: P</span> <span m="2016745">times</span> <span m="2017050">U.</span> <span
  m="2017390">That''s</span> <span m="2017800">that</span> <span m="2018130">correct</span>
  <span m="2018310">answer.</span> <span m="2018420">Can</span> <span m="2018800">you</span>
  <span m="2018880">say why</span> <span m="2019160">that</span> <span m="2019320">is</span>
  <span m="2019450">this</span> <span m="2019600">case?</span></p><p><span m="2021372">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="2023268">QIQI WANG: That''s</span> <span m="2023742">[INAUDIBLE].</span>
  <span m="2025170">Yeah.</span> <span m="2025340">Because</span> <span m="2026542">flux</span>
  <span m="2027030">is</span> <span m="2027390">number</span> <span m="2028050">of</span>
  <span m="2028920">cars,</span> <span m="2030190">the</span> <span m="2030430">amount</span>
  <span m="2030920">of</span> <span m="2031120">converse</span> <span m="2031580">quantity</span>
  <span m="2031990">that</span> <span m="2032290">flows</span> <span m="2032670">through</span>
  <span m="2033560">a</span> <span m="2033800">point</span> <span m="2034450">per</span>
  <span m="2034570">unit amount</span> <span m="2034770">of time,</span> <span m="2035918">right?</span>
  <span m="2036906">So</span> <span m="2038390">if</span> <span m="2038660">you</span>
  <span m="2039130">just</span> <span m="2039990">[INAUDIBLE]</span> <span m="2040200">the</span>
  <span m="2040320">control</span> <span m="2040700">volume</span> <span m="2041190">like</span>
  <span m="2041530">this,</span> <span m="2041855">this</span> <span m="2042180">is</span>
  <span m="2042280">my--</span> <span m="2042430">oh,</span> <span m="2042820">I shouldn''t</span>
  <span m="2043270">use green,</span> <span m="2043690">because you</span> <span m="2044110">can''t
  see.</span></p><p><span m="2046010">If</span> <span m="2046230">you</span> <span
  m="2046370">true</span> <span m="2046700">the</span> <span m="2046820">control</span>
  <span m="2047190">volume</span> <span m="2047620">like</span> <span m="2047890">this--</span>
  <span m="2050882">and</span> <span m="2051334">the</span> <span m="2051790">flux</span>
  <span m="2052239">of</span> <span m="2052340">this</span> <span m="2052510">[INAUDIBLE]</span>
  <span m="2052840">is</span> <span m="2052969">the</span> <span m="2053420">number</span>
  <span m="2053960">of</span> <span m="2054260">cars</span> <span m="2054590">that</span>
  <span m="2054920">goes</span> <span m="2055340">through</span> <span m="2055580">this</span>
  <span m="2055830">line</span> <span m="2056260">per unit amount</span> <span m="2056677">of
  time.</span> <span m="2057929">So this is</span> <span m="2058050">cars</span> <span
  m="2058430">that</span> <span m="2058810">have</span> <span m="2059100">density</span>
  <span m="2059469">of</span> <span m="2059600">rho</span> <span m="2060010">goes</span>
  <span m="2060380">through</span> <span m="2060440">the</span> <span m="2060520">[INAUDIBLE]</span>
  <span m="2060909">U.</span> <span m="2061741">Of</span> <span m="2062159">course,</span>
  <span m="2062800">the</span> <span m="2062960">flux</span> <span m="2063330">is
  going</span> <span m="2063489">to be</span> <span m="2063923">P</span> <span m="2064357">times
  U.</span></p><p><span m="2066530">The</span> <span m="2066659">flux</span> <span
  m="2067280">is</span> <span m="2067670">going</span> <span m="2067850">to</span>
  <span m="2067940">be</span> <span m="2069790">P</span> <span m="2070260">times</span>
  <span m="2070530">U,</span> <span m="2070880">which is</span> <span m="2072440">P</span>
  <span m="2072780">minus</span> <span m="2073120">P</span> <span m="2073400">squared</span>
  <span m="2073790">in</span> <span m="2073920">this</span> <span m="2074060">case.</span>
  <span m="2074479">Because</span> <span m="2074898">U</span> <span m="2075317">is</span>
  <span m="2075739">1 minus P.</span> <span m="2076029">P times</span> <span m="2076320">U</span>
  <span m="2076785">is</span> <span m="2077250">P</span> <span m="2077715">minus P</span>
  <span m="2078180">squared.</span> <span m="2081909">Is</span> <span m="2082030">it</span>
  <span m="2082100">clear?</span> <span m="2084270">Any</span> <span m="2084409">questions?</span></p><p><span
  m="2086699">So</span> <span m="2086929">we</span> <span m="2087219">derived</span>
  <span m="2087770">our</span> <span m="2087960">differential</span> <span m="2088320">equation,</span>
  <span m="2089239">dP</span> <span m="2089840">dt</span> <span m="2091564">plus</span>
  <span m="2092940">d</span> <span m="2094030">of</span> <span m="2094489">P--</span>
  <span m="2095280">I''m</span> <span m="2095630">just</span> <span m="2095739">going
  to</span> <span m="2095840">write</span> <span m="2096100">F(P),</span> <span m="2096460">it''s</span>
  <span m="2096790">easier.</span> <span m="2097670">F(P)</span> <span m="2099260">dx</span>
  <span m="2100210">is equal</span> <span m="2100630">to</span> <span m="2101050">0</span>
  <span m="2101880">where</span> <span m="2103580">F(P)</span> <span m="2104530">is</span>
  <span m="2104770">equal</span> <span m="2104960">to</span> <span m="2105620">P</span>
  <span m="2105890">minus P</span> <span m="2106160">squared.</span></p><p><span m="2108420">OK.</span>
  <span m="2108730">Now,</span> <span m="2109930">what</span> <span m="2110150">is</span>
  <span m="2110400">C?</span> <span m="2111290">What</span> <span m="2111540">is</span>
  <span m="2111800">the</span> <span m="2113750">[INAUDIBLE]</span> <span m="2114240">characteristic</span>
  <span m="2114655">C?</span> <span m="2119471">Now,</span> <span m="2119960">this</span>
  <span m="2120180">becomes</span> <span m="2120580">highly</span> <span m="2120920">[INAUDIBLE].</span>
  <span m="2123840">What</span> <span m="2124030">is</span> <span m="2124260">C?</span></p><p><span
  m="2125901">AUDIENCE: 1 minus</span> <span m="2126338">[INAUDIBLE].</span></p><p><span
  m="2127650">QIQI WANG: It''s</span> <span m="2127980">1 minus 2P.</span> <span m="2129530">It
  is</span> <span m="2130000">equal</span> <span m="2130230">to</span> <span m="2130400">dF</span>
  <span m="2131240">dP,</span> <span m="2131400">right?</span> <span m="2132980">So</span>
  <span m="2133170">derivative</span> <span m="2133455">of</span> <span m="2133740">P</span>
  <span m="2134040">is</span> <span m="2134180">1</span> <span m="2134744">[INAUDIBLE].</span>
  <span m="2137710">OK.</span> <span m="2138610">So</span> <span m="2138830">we</span>
  <span m="2139330">have</span> <span m="2140160">a</span> <span m="2140190">relation</span>
  <span m="2140730">like</span> <span m="2140970">this.</span> <span m="2143360">We</span>
  <span m="2143530">have</span> <span m="2143700">a</span> <span m="2143780">relation</span>
  <span m="2144260">of</span> <span m="2144500">F</span> <span m="2146010">versus</span>
  <span m="2146450">P.</span> <span m="2146770">P</span> <span m="2147130">is</span>
  <span m="2147420">all</span> <span m="2147580">the</span> <span m="2147650">way</span>
  <span m="2147840">from</span> <span m="2148080">0 to</span> <span m="2148456">1.</span></p><p><span
  m="2149210">F</span> <span m="2150230">is</span> <span m="2151100">something</span>
  <span m="2151530">like</span> <span m="2151870">this,</span> <span m="2153220">where</span>
  <span m="2153410">the</span> <span m="2153490">maximum</span> <span m="2154120">takes</span>
  <span m="2155190">1/4.</span> <span m="2157060">OK.</span> <span m="2157720">And</span>
  <span m="2157950">we</span> <span m="2158060">have</span> <span m="2158240">a</span>
  <span m="2158707">C</span> <span m="2161042">that</span> <span m="2161510">looks</span>
  <span m="2161810">like</span> <span m="2162040">this.</span> <span m="2162460">We</span>
  <span m="2162520">have</span> <span m="2162790">C</span> <span m="2163230">that</span>
  <span m="2163890">is</span> <span m="2164130">equal</span> <span m="2164450">to</span>
  <span m="2164540">1</span> <span m="2165280">when</span> <span m="2165590">there</span>
  <span m="2165710">is</span> <span m="2165830">no</span> <span m="2166030">cars</span>
  <span m="2166440">and</span> <span m="2166670">goes</span> <span m="2166990">all</span>
  <span m="2167270">the</span> <span m="2167340">way</span> <span m="2167550">to</span>
  <span m="2168220">minus</span> <span m="2168320">1</span> <span m="2168750">when</span>
  <span m="2169080">there</span> <span m="2169260">is</span> <span m="2169440">a</span>
  <span m="2169960">parking</span> <span m="2170310">lot</span> <span m="2170520">of</span>
  <span m="2170600">cars.</span> <span m="2173100">This</span> <span m="2173600">is</span>
  <span m="2174100">1</span> <span m="2174600">and</span> <span m="2175100">minus
  1.</span></p><p><span m="2178090">OK.</span> <span m="2179300">So</span> <span m="2180920">what</span>
  <span m="2181390">is</span> <span m="2181500">happening?</span> <span m="2182716">C,</span>
  <span m="2183170">again,</span> <span m="2183510">is</span> <span m="2183820">the</span>
  <span m="2184880">speed</span> <span m="2185200">of</span> <span m="2186150">the</span>
  <span m="2186300">local</span> <span m="2186720">solution.</span> <span m="2188360">It</span>
  <span m="2188520">is</span> <span m="2188680">intuitive</span> <span m="2188955">that</span>
  <span m="2190280">when</span> <span m="2190470">there</span> <span m="2190590">are</span>
  <span m="2190710">no</span> <span m="2190870">cars,</span> <span m="2191330">things</span>
  <span m="2191560">move</span> <span m="2191850">at</span> <span m="2192240">85</span>
  <span m="2192704">miles per</span> <span m="2193168">hour.</span></p><p><span m="2194096">So
  the</span> <span m="2194560">[INAUDIBLE]</span> <span m="2195024">should be</span>
  <span m="2195488">1.</span> <span m="2197350">What</span> <span m="2197600">happens</span>
  <span m="2197800">here?</span> <span m="2198560">When there</span> <span m="2198940">is</span>
  <span m="2199320">a parking</span> <span m="2199585">lot</span> <span m="2199850">of</span>
  <span m="2200220">cars,</span> <span m="2200360">things</span> <span m="2200685">move</span>
  <span m="2201010">backwards</span> <span m="2201769">at</span> <span m="2202258">85
  miles an</span> <span m="2202747">hour?</span></p><p><span m="2207637">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="2209110">QIQI WANG: Yes.</span> <span m="2209570">It''s</span>
  <span m="2210120">kind of</span> <span m="2210420">the--</span> <span m="2211950">so</span>
  <span m="2212230">this</span> <span m="2212660">C</span> <span m="2212980">here</span>
  <span m="2213220">is</span> <span m="2213470">not--</span> <span m="2213910">I mean,</span>
  <span m="2215110">if</span> <span m="2215600">you</span> <span m="2215680">look</span>
  <span m="2215900">into</span> <span m="2216080">physics</span> <span m="2216986">you''ve
  got</span> <span m="2217440">two kind</span> <span m="2217570">of</span> <span m="2217810">speeds,</span>
  <span m="2218150">like</span> <span m="2218380">a</span> <span m="2218510">group
  speed</span> <span m="2219006">and a</span> <span m="2219502">[INAUDIBLE]</span>
  <span m="2219751">speed,</span> <span m="2220000">right?</span> <span m="2220860">So</span>
  <span m="2221050">here,</span> <span m="2221395">the</span> <span m="2221740">cars</span>
  <span m="2222090">move</span> <span m="2222880">forward</span> <span m="2223370">always</span>
  <span m="2223740">have</span> <span m="2223890">a</span> <span m="2224010">positive
  speed.</span> <span m="2225520">But</span> <span m="2226160">it</span> <span m="2226310">doesn''t</span>
  <span m="2226735">mean</span> <span m="2227710">if</span> <span m="2227940">you</span>
  <span m="2228050">look</span> <span m="2228380">at</span> <span m="2228715">cars</span>
  <span m="2229050">in</span> <span m="2229230">the</span> <span m="2229330">backwards</span>
  <span m="2229940">[INAUDIBLE]</span> <span m="2230530">point</span> <span m="2230770">of</span>
  <span m="2230910">view,</span> <span m="2231410">it doesn''t</span> <span m="2231910">mean
  the</span> <span m="2232100">wave</span> <span m="2232740">that</span> <span m="2234100">appears</span>
  <span m="2235370">in</span> <span m="2235820">the</span> <span m="2236130">flow</span>
  <span m="2236380">of</span> <span m="2236570">traffic</span> <span m="2236950">is</span>
  <span m="2237315">going to</span> <span m="2237680">move forward.</span> <span m="2238910">Sometimes</span>
  <span m="2239540">you</span> <span m="2239620">are going</span> <span m="2239860">to</span>
  <span m="2239940">see</span> <span m="2240220">waves</span> <span m="2240690">actually</span>
  <span m="2241020">moving</span> <span m="2241380">backwards.</span> <span m="2242930">I</span>
  <span m="2243000">mean,</span> <span m="2243180">we''re waiting</span> <span m="2243310">to</span>
  <span m="2243650">see</span> <span m="2243870">some</span> <span m="2244130">examples</span>
  <span m="2244610">when it</span> <span m="2244820">actually</span> <span m="2245210">solves</span>
  <span m="2245570">that</span> <span m="2245800">numerically.</span></p><p><span
  m="2249110">OK.</span> <span m="2250550">So</span> <span m="2250730">the</span>
  <span m="2250870">task</span> <span m="2251970">for</span> <span m="2252170">you</span>
  <span m="2252590">is</span> <span m="2253030">to</span> <span m="2254330">hold</span>
  <span m="2254650">up</span> <span m="2255200">a</span> <span m="2255380">simulation</span>
  <span m="2256010">of</span> <span m="2256140">this</span> <span m="2256360">thing</span>
  <span m="2256570">in a</span> <span m="2256790">periodic</span> <span m="2257360">[INAUDIBLE]</span>
  <span m="2257840">solution.</span> <span m="2259540">So</span> <span m="2259860">let''s</span>
  <span m="2260110">say</span> <span m="2262110">this</span> <span m="2262340">is</span>
  <span m="2262470">our</span> <span m="2262640">highway.</span> <span m="2263290">This</span>
  <span m="2263480">is</span> <span m="2263690">our</span> <span m="2263930">highway.</span>
  <span m="2266280">It just</span> <span m="2266700">goes in</span> <span m="2266985">circles,</span>
  <span m="2267270">right?</span> <span m="2268380">Assuming</span> <span m="2268865">you</span>
  <span m="2269380">have</span> <span m="2269530">a</span> <span m="2269590">bunch
  of</span> <span m="2269930">cars</span> <span m="2270560">driving</span> <span m="2270800">in</span>
  <span m="2270900">circles.</span></p><p><span m="2271892">AUDIENCE: I could never</span>
  <span m="2272388">get off the</span> <span m="2272884">[INAUDIBLE].</span></p><p><span
  m="2273380">AUDIENCE: [INAUDIBLE]</span></p><p><span m="2274372">QIQI WANG: Huh?</span></p><p><span
  m="2274870">AUDIENCE: NASCAR.</span></p><p><span m="2275653">QIQI WANG: NASCAR,</span>
  <span m="2276126">yeah,</span> <span m="2276599">yeah,</span> <span m="2277072">right.</span>
  <span m="2277545">Yeah.</span> <span m="2279910">We</span> <span m="2280060">have</span>
  <span m="2280220">a</span> <span m="2280290">lot</span> <span m="2280480">of</span>
  <span m="2280590">cars</span> <span m="2280983">driving</span> <span m="2281376">in</span>
  <span m="2281770">home</span> <span m="2282045">circles.</span> <span m="2282320">And</span>
  <span m="2282791">let''s</span> <span m="2283262">just</span> <span m="2283733">[INAUDIBLE]</span>
  <span m="2284204">how</span> <span m="2284675">these</span> <span m="2285150">work.</span></p><p><span
  m="2285850">And</span> <span m="2286060">then</span> <span m="2286280">at</span>
  <span m="2286625">sometime,</span> <span m="2286970">we</span> <span m="2287160">are</span>
  <span m="2287510">going</span> <span m="2287690">to</span> <span m="2287840">put</span>
  <span m="2288090">a</span> <span m="2288240">red</span> <span m="2288470">light</span>
  <span m="2288980">over</span> <span m="2289220">here.</span> <span m="2290530">And</span>
  <span m="2291230">say,</span> <span m="2291470">OK,</span> <span m="2292744">the
  cars</span> <span m="2293201">stop here.</span> <span m="2295030">What</span> <span
  m="2295090">is</span> <span m="2295220">the</span> <span m="2295310">right</span>
  <span m="2295530">way</span> <span m="2295670">to model</span> <span m="2296080">that</span>
  <span m="2296300">numerically?</span></p><p><span m="2301040">You can</span> <span
  m="2301520">set</span> <span m="2301910">the</span> <span m="2302220">flux</span>
  <span m="2302683">[INAUDIBLE]</span> <span m="2303146">to 0, right?</span> <span
  m="2303610">I mean,</span> <span m="2303860">at</span> <span m="2304040">some</span>
  <span m="2304250">point,</span> <span m="2304815">that''s</span> <span m="2305140">a</span>
  <span m="2305260">[INAUDIBLE]</span> <span m="2305370">simulation.</span> <span
  m="2306243">And</span> <span m="2306606">for example,</span> <span m="2307120">time</span>
  <span m="2307220">equal</span> <span m="2307694">to 1,</span> <span m="2308168">that''s</span>
  <span m="2308642">[INAUDIBLE]</span> <span m="2309590">0</span> <span m="2310030">[INAUDIBLE]</span>
  <span m="2312665">before</span> <span m="2313146">the red</span> <span m="2313630">light.</span>
  <span m="2314130">And</span> <span m="2314630">at some</span> <span m="2315130">point,</span>
  <span m="2315630">let''s</span> <span m="2316130">set the</span> <span m="2316630">light</span>
  <span m="2317130">[INAUDIBLE].</span></p><p><span m="2319370">But</span> <span m="2319510">let''s</span>
  <span m="2320515">do</span> <span m="2320830">something</span> <span m="2321250">simple</span>
  <span m="2321640">in</span> <span m="2321700">the</span> <span m="2321840">beginning.</span>
  <span m="2322306">Let''s</span> <span m="2322772">just</span> <span m="2323238">[INAUDIBLE]</span>
  <span m="2324170">the</span> <span m="2324640">solution</span> <span m="2325150">of</span>
  <span m="2325400">[INAUDIBLE]</span> <span m="2326302">with no</span> <span m="2326753">red</span>
  <span m="2327204">lights or</span> <span m="2327655">anything like that.</span>
  <span m="2328110">I''m</span> <span m="2328290">going</span> <span m="2328420">to</span>
  <span m="2328810">give</span> <span m="2328990">you</span> <span m="2329190">the</span>
  <span m="2329685">initial</span> <span m="2330180">position.</span> <span m="2330675">And
  we''ll</span> <span m="2331170">see how</span> <span m="2331665">it</span> <span
  m="2332160">evolves.</span> <span m="2333650">And</span> <span m="2333900">then</span>
  <span m="2334070">we</span> <span m="2334715">are</span> <span m="2335070">using</span>
  <span m="2335240">final</span> <span m="2335710">volume.</span></p><p><span m="2337590">And</span>
  <span m="2338070">you</span> <span m="2338290">are</span> <span m="2338550">free</span>
  <span m="2338900">to</span> <span m="2339230">take--</span> <span m="2340570">the</span>
  <span m="2340860">[INAUDIBLE]</span> <span m="2341390">case</span> <span m="2341770">we</span>
  <span m="2342080">had</span> <span m="2342640">in</span> <span m="2342790">the</span>
  <span m="2342880">last</span> <span m="2343160">lecture</span> <span m="2350594">is</span>
  <span m="2351580">in</span> <span m="2351720">the</span> <span m="2351810">shared</span>
  <span m="2352550">folder.</span> <span m="2355050">And</span> <span m="2355410">I''m</span>
  <span m="2355560">just</span> <span m="2355740">going</span> <span m="2355880">to</span>
  <span m="2355950">make</span> <span m="2356280">another</span> <span m="2356680">shared</span>
  <span m="2357040">folder</span> <span m="2357400">here.</span> <span m="2363780">OK.</span>
  <span m="2364700">I''m</span> <span m="2366260">just</span> <span m="2366480">going</span>
  <span m="2366550">to</span> <span m="2366750">take</span> <span m="2367130">a</span>
  <span m="2367550">[INAUDIBLE]</span> <span m="2369860">and</span> <span m="2370160">the</span>
  <span m="2370320">du dt.</span></p><p><span m="2372210">I''m</span> <span m="2372360">just</span>
  <span m="2372460">going</span> <span m="2372630">to</span> <span m="2372710">take</span>
  <span m="2376740">the</span> <span m="2377480">[INAUDIBLE]</span> <span m="2377860">stamp</span>
  <span m="2378270">[INAUDIBLE]</span> <span m="2380356">to</span> <span m="2380740">this.</span>
  <span m="2381160">Because</span> <span m="2381500">I</span> <span m="2381580">know</span>
  <span m="2381760">it''s</span> <span m="2381950">working.</span> <span m="2383182">And</span>
  <span m="2384174">[INAUDIBLE]</span> <span m="2388142">start</span> <span m="2389140">by</span>
  <span m="2390330">modifying</span> <span m="2391507">[INAUDIBLE].</span> <span m="2398470">So</span>
  <span m="2398660">instead</span> <span m="2399030">of</span> <span m="2399400">u_bar,</span>
  <span m="2399760">you''re</span> <span m="2399880">going</span> <span m="2400030">to</span>
  <span m="2400140">solving</span> <span m="2400410">for</span> <span m="2400890">P_bar.</span>
  <span m="2405270">And</span> <span m="2405510">what</span> <span m="2405860">is
  the</span> <span m="2405950">first</span> <span m="2406250">thing</span> <span m="2406743">you</span>
  <span m="2407236">would</span> <span m="2407730">want changed</span> <span m="2413300">in</span>
  <span m="2413500">this?</span></p><p><span m="2415241">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="2421450">QIQI WANG: Oh, yeah.</span> <span m="2421860">Yeah,</span> <span m="2421930">make
  it</span> <span m="2422130">upwind.</span> <span m="2422790">Yeah,</span> <span
  m="2423100">right.</span> <span m="2423580">To</span> <span m="2424060">make</span>
  <span m="2424390">it</span> <span m="2424520">upwind</span> <span m="2425013">there
  are</span> <span m="2425506">[INAUDIBLE].</span> <span m="2427478">Huh?</span></p><p><span
  m="2428464">AUDIENCE: [INAUDIBLE]</span></p><p><span m="2430940">QIQI WANG: It''s</span>
  <span m="2431130">no</span> <span m="2431300">longer</span> <span m="2431600">that</span>
  <span m="2431850">equation.</span> <span m="2432150">The</span> <span m="2432620">equation</span>
  <span m="2432760">is</span> <span m="2432880">[INAUDIBLE].</span> <span m="2433370">But</span>
  <span m="2433530">there</span> <span m="2433980">is</span> <span m="2434200">only</span>
  <span m="2434270">one</span> <span m="2434580">line</span> <span m="2435110">we
  can</span> <span m="2435600">change</span> <span m="2436090">to solve  for</span>
  <span m="2436580">a different</span> <span m="2437070">equation</span> <span m="2437560">and
  find the volume.</span> <span m="2439030">What</span> <span m="2439280">line</span>
  <span m="2439480">is</span> <span m="2439630">that?</span></p><p><span m="2440428">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="2444820">QIQI WANG: Second</span> <span m="2445000">line.</span>
  <span m="2447290">The</span> <span m="2447570">only</span> <span m="2448010">thing</span>
  <span m="2448260">that</span> <span m="2448450">satisfies</span> <span m="2448915">a</span>
  <span m="2449380">different</span> <span m="2449700">equation</span> <span m="2450202">is
  the</span> <span m="2451350">flux.</span> <span m="2453640">You</span> <span m="2453840">change</span>
  <span m="2454190">the</span> <span m="2454350">flux,</span> <span m="2454720">you
  are</span> <span m="2455110">now</span> <span m="2455460">solving</span> <span m="2455860">a</span>
  <span m="2455950">different</span> <span m="2456040">equation.</span> <span m="2458150">OK.</span>
  <span m="2459790">Of course,</span> <span m="2460120">another</span> <span m="2460400">thing</span>
  <span m="2460540">is</span> <span m="2461070">what</span> <span m="2461460">is</span>
  <span m="2461710">upwind</span> <span m="2462160">direction</span> <span m="2462610">[INAUDIBLE].</span></p><p><span
  m="2465310">In</span> <span m="2465760">[INAUDIBLE]</span> <span m="2466440">equation,</span>
  <span m="2466810">we</span> <span m="2466850">know</span> <span m="2467260">U</span>
  <span m="2467730">is</span> <span m="2467920">positive</span> <span m="2468330">plus</span>
  <span m="2468670">[INAUDIBLE]</span> <span m="2469155">the</span> <span m="2469640">right.</span>
  <span m="2470010">U</span> <span m="2470492">is negative</span> <span m="2470974">[INAUDIBLE].</span>
  <span m="2471940">Now,</span> <span m="2472368">this is</span> <span m="2472796">different.</span>
  <span m="2475260">Now,</span> <span m="2475540">this</span> <span m="2475690">is</span>
  <span m="2475830">different,</span> <span m="2476290">because</span> <span m="2476830">we</span>
  <span m="2477280">have</span> <span m="2478180">[INAUDIBLE].</span> <span m="2479150">What</span>
  <span m="2479370">is</span> <span m="2479540">left and</span> <span m="2480033">what
  is</span> <span m="2480526">right</span> <span m="2481019">all depends</span> <span
  m="2481512">on the</span> <span m="2482005">[INAUDIBLE]</span> <span m="2483484">instead</span>
  <span m="2483977">of</span> <span m="2484470">the</span> <span m="2484963">[INAUDIBLE].</span>
  <span m="2491865">So</span> <span m="2492380">any</span> <span m="2492850">questions?</span></p><p><span
  m="2493948">OK.</span> <span m="2494446">If you</span> <span m="2494944">are done</span>
  <span m="2495442">with the--</span> <span m="2496940">If</span> <span m="2497110">you</span>
  <span m="2497260">get</span> <span m="2497550">the</span> <span m="2497993">solution</span>
  <span m="2498880">going,</span> <span m="2499220">try</span> <span m="2499671">to
  put</span> <span m="2500122">a</span> <span m="2500573">red</span> <span m="2501024">light</span>
  <span m="2502380">somewhere.</span> <span m="2503810">Let</span> <span m="2504430">me</span>
  <span m="2504710">kind</span> <span m="2504880">of</span> <span m="2505120">illustrate</span>
  <span m="2505790">how</span> <span m="2507740">I</span> <span m="2507810">should</span>
  <span m="2508050">modify</span> <span m="2508470">the</span> <span m="2508570">driver.</span>
  <span m="2513460">So</span> <span m="2514324">I have</span> <span m="2514798">this</span>
  <span m="2515272">here.</span> <span m="2518590">That,</span> <span m="2518840">I</span>
  <span m="2518920">didn''t</span> <span m="2519190">call</span> <span m="2519420">it</span>
  <span m="2519530">[INAUDIBLE].</span> <span m="2520110">Because</span> <span m="2520430">it''s</span>
  <span m="2520580">no</span> <span m="2520710">longer</span> <span m="2521010">[INAUDIBLE].</span>
  <span m="2522890">Let me</span> <span m="2523360">[INAUDIBLE].</span></p><p><span
  m="2527120">trafficDriver.</span> <span m="2528140">OK,</span> <span m="2528631">trafficDriver.</span>
  <span m="2532070">And</span> <span m="2532570">let</span> <span m="2532670">me</span>
  <span m="2532800">see.</span> <span m="2534230">So</span> <span m="2534420">in</span>
  <span m="2536510">this</span> <span m="2536860">ODE</span> <span m="2537170">45,</span>
  <span m="2539490">I''m</span> <span m="2539730">going</span> <span m="2539870">to</span>
  <span m="2539950">set</span> <span m="2540230">t0=(i-1)</span> <span m="2542550">times</span>
  <span m="2543010">dt</span> <span m="2544590">and</span> <span m="2544900">t1=i</span>
  <span m="2545777">times</span> <span m="2546154">dt.</span> <span m="2546910">So</span>
  <span m="2547080">this</span> <span m="2547250">is</span> <span m="2547420">like</span>
  <span m="2547630">the</span> <span m="2547710">beginning</span> <span m="2548280">and</span>
  <span m="2548560">end</span> <span m="2548820">of</span> <span m="2549010">this</span>
  <span m="2549080">interval.</span></p><p><span m="2550460">And</span> <span m="2550820">when</span>
  <span m="2551120">I''m</span> <span m="2551450">solving</span> <span m="2551970">it,</span>
  <span m="2552210">I''m</span> <span m="2552370">going</span> <span m="2552560">to</span>
  <span m="2552640">be</span> <span m="2552790">solving</span> <span m="2553170">it</span>
  <span m="2553240">from</span> <span m="2553706">t0</span> <span m="2554172">to</span>
  <span m="2554638">t1.</span> <span m="2555570">So</span> <span m="2555680">now</span>
  <span m="2556180">the</span> <span m="2556320">difference</span> <span m="2556890">is</span>
  <span m="2558280">if</span> <span m="2561020">I</span> <span m="2561130">look</span>
  <span m="2561530">at--</span> <span m="2568564">so let</span> <span m="2569045">me
  do</span> <span m="2569540">this.</span> <span m="2577336">OK.</span> <span m="2579220">So</span>
  <span m="2579460">I</span> <span m="2579560">just</span> <span m="2579750">want</span>
  <span m="2580030">to</span> <span m="2580160">be</span> <span m="2580300">able</span>
  <span m="2580610">to</span> <span m="2580810">passing</span> <span m="2582220">the</span>
  <span m="2582400">actual</span> <span m="2584670">time.</span> <span m="2585170">So</span>
  <span m="2585380">I''m</span> <span m="2585510">just</span> <span m="2585660">going</span>
  <span m="2585790">to</span> <span m="2585880">be</span> <span m="2586420">passing</span>
  <span m="2586770">also</span> <span m="2587220">time</span> <span m="2587660">into</span>
  <span m="2588980">this.</span></p><p><span m="2589870">So</span> <span m="2590040">I</span>
  <span m="2590170">also</span> <span m="2590670">have</span> <span m="2590930">a</span>
  <span m="2591190">time</span> <span m="2591440">into</span> <span m="2591660">this.</span>
  <span m="2592820">And</span> <span m="2593200">then</span> <span m="2593320">now</span>
  <span m="2595360">if--</span> <span m="2596380">OK,</span> <span m="2596600">so</span>
  <span m="2596860">let</span> <span m="2597340">me</span> <span m="2597420">just</span>
  <span m="2597670">go</span> <span m="2597890">through</span> <span m="2599130">what</span>
  <span m="2599390">you</span> <span m="2599470">need</span> <span m="2599640">to</span>
  <span m="2599720">modify.</span> <span m="2601090">So</span> <span m="2601290">first</span>
  <span m="2601510">of</span> <span m="2601640">all,</span> <span m="2601970">I''m</span>
  <span m="2602070">going</span> <span m="2602210">to</span> <span m="2602280">modify</span>
  <span m="2604932">this,</span> <span m="2606340">which</span> <span m="2606610">is</span>
  <span m="2606980">the</span> <span m="2607370">different</span> <span m="2607810">flux.</span>
  <span m="2608980">Right?</span></p><p><span m="2610360">Instead</span> <span m="2610750">of</span>
  <span m="2611410">half</span> <span m="2611790">of</span> <span m="2612040">u</span>
  <span m="2612290">squared,</span> <span m="2612490">I have</span> <span m="2612710">u</span>
  <span m="2613040">minus</span> <span m="2613270">u</span> <span m="2613390">squared.</span>
  <span m="2614670">OK.</span> <span m="2615210">k_plus_half</span> <span m="2615420">is</span>
  <span m="2615760">still</span> <span m="2616060">the</span> <span m="2616140">same.</span>
  <span m="2617360">I''m</span> <span m="2617800">going</span> <span m="2618050">to--</span>
  <span m="2620640">so</span> <span m="2620810">if</span> <span m="2621450">I</span>
  <span m="2621560">don''t</span> <span m="2621860">modify</span> <span m="2622330">anything,</span>
  <span m="2622840">I</span> <span m="2622960">think</span> <span m="2623260">it</span>
  <span m="2623440">all</span> <span m="2623590">wrong.</span></p><p><span m="2624110">But</span>
  <span m="2624330">like</span> <span m="2624730">once</span> <span m="2625090">a</span>
  <span m="2625180">shock</span> <span m="2625520">wave</span> <span m="2625720">forms,</span>
  <span m="2626090">it''ll</span> <span m="2626480">go</span> <span m="2626700">unstable.</span>
  <span m="2627430">So</span> <span m="2627560">let</span> <span m="2627690">me</span>
  <span m="2627790">try</span> <span m="2628080">it.</span> <span m="2630022">I doesn''t</span>
  <span m="2630460">even</span> <span m="2630750">wrong.</span> <span m="2635380">[INAUDIBLE]</span>
  <span m="2636290">dimension</span> <span m="2636800">matrices</span> <span m="2637590">being</span>
  <span m="2637760">concatenated</span> <span m="2638930">are</span> <span m="2639060">not</span>
  <span m="2639380">consistent.</span></p><p><span m="2648002">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="2650410">QIQI WANG: Oh,</span> <span m="2650720">OK.</span> <span m="2651010">I''m</span>
  <span m="2651245">[INAUDIBLE]</span> <span m="2651480">different</span> <span m="2651810">[INAUDIBLE].</span>
  <span m="2652070">Yes,</span> <span m="2652570">thank you.</span> <span m="2663846">I
  save</span> <span m="2664330">this.</span></p><p><span m="2667578">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="2670370">QIQI WANG: Oh,</span> <span m="2670610">i''m solving--</span> <span
  m="2670820">yeah--</span> <span m="2671286">from</span> <span m="2671752">t0</span>
  <span m="2672218">to t1.</span> <span m="2673150">Yeah,</span> <span m="2673320">thank
  you.</span> <span m="2674470">OK.</span> <span m="2675000">So</span> <span m="2675180">this</span>
  <span m="2675400">thing</span> <span m="2676300">goes.</span> <span m="2677050">And</span>
  <span m="2677680">we''re</span> <span m="2678170">going to</span> <span m="2678660">see</span>
  <span m="2679010">[INAUDIBLE]--</span> <span m="2681880">wait.</span> <span m="2682380">I</span>
  <span m="2682490">shouldn''t</span> <span m="2683390">initialize</span> <span m="2683940">it</span>
  <span m="2684060">to</span> <span m="2684200">2,</span> <span m="2684470">right?</span>
  <span m="2684710">Because</span> <span m="2685000">1</span> <span m="2685220">is</span>
  <span m="2685420">parking</span> <span m="2685840">lot.</span> <span m="2686300">What
  is 2?</span></p><p><span m="2687680">OK.</span> <span m="2687940">So</span> <span
  m="2688120">I need</span> <span m="2688370">to</span> <span m="2688510">also</span>
  <span m="2688740">modify</span> <span m="2688910">the initial</span> <span m="2689370">condition.</span>
  <span m="2690690">So</span> <span m="2690970">what</span> <span m="2691500">I</span>
  <span m="2691570">can</span> <span m="2691770">do</span> <span m="2691950">is</span>
  <span m="2692140">I</span> <span m="2692220">can set</span> <span m="2692840">this,</span>
  <span m="2693620">let''s say,</span> <span m="2693970">divide</span> <span m="2694280">by</span>
  <span m="2694530">4.</span> <span m="2695360">OK.</span> <span m="2695620">So</span>
  <span m="2695780">this</span> <span m="2695960">is</span> <span m="2696100">going</span>
  <span m="2696230">to</span> <span m="2696290">be</span> <span m="2696350">my</span>
  <span m="2696520">initial</span> <span m="2696790">condition</span> <span m="2697800">[INAUDIBLE].</span>
  <span m="2699940">OK.</span> <span m="2700320">I also</span> <span m="2700700">want</span>
  <span m="2700940">to--</span> <span m="2703510">my</span> <span m="2703980">ylim,</span>
  <span m="2704710">when</span> <span m="2705050">I</span> <span m="2705130">show</span>
  <span m="2705560">my</span> <span m="2705640">solution,</span> <span m="2706180">I</span>
  <span m="2706340">just</span> <span m="2706550">want</span> <span m="2706890">to</span>
  <span m="2707290">go</span> <span m="2707420">from</span> <span m="2707700">0</span>
  <span m="2707990">to</span> <span m="2708470">1, right?</span></p><p><span m="2709970">OK.</span>
  <span m="2710280">So</span> <span m="2710420">let</span> <span m="2710560">me</span>
  <span m="2710710">run</span> <span m="2710950">again.</span> <span m="2712640">OK.</span>
  <span m="2712950">So</span> <span m="2713120">this</span> <span m="2713320">is</span>
  <span m="2713460">how</span> <span m="2713610">my</span> <span m="2713750">solution</span>
  <span m="2714150">looks like.</span> <span m="2715374">This</span> <span m="2715782">part
  goes</span> <span m="2716190">really</span> <span m="2716570">fast.</span> <span
  m="2717968">[INAUDIBLE]</span> <span m="2719832">unstable.</span> <span m="2721700">And</span>
  <span m="2722250">I</span> <span m="2722370">need</span> <span m="2722560">to</span>
  <span m="2722660">change</span> <span m="2722990">this</span> <span m="2723160">to</span>
  <span m="2723310">upwinding.</span> <span m="2723890">But</span> <span m="2724490">we</span>
  <span m="2724660">have</span> <span m="2724930">the</span> <span m="2725390">[INAUDIBLE]</span>
  <span m="2725850">part</span> <span m="2726310">of the solution</span> <span m="2726770">correct.</span></p><p><span
  m="2727230">Every</span> <span m="2727500">[INAUDIBLE]</span> <span m="2728120">towards</span>
  <span m="2728500">a positive</span> <span m="2729260">direction</span> <span m="2730136">when
  the</span> <span m="2730574">[INAUDIBLE]</span> <span m="2731890">move</span> <span
  m="2732318">faster.</span> <span m="2732746">That''s</span> <span m="2733174">[INAUDIBLE]</span>
  <span m="2733602">car density,</span> <span m="2734030">cars</span> <span m="2734460">move
  slower.</span> <span m="2734910">So</span> <span m="2735360">sometimes,</span> <span
  m="2736710">a</span> <span m="2737160">shock</span> <span m="2737400">wave is</span>
  <span m="2737725">going to</span> <span m="2738050">form.</span> <span m="2739032">Because</span>
  <span m="2739390">the</span> <span m="2739760">faster</span> <span m="2740370">parts</span>
  <span m="2740910">is</span> <span m="2741160">going to</span> <span m="2741970">[INAUDIBLE]</span>
  <span m="2742375">to the</span> <span m="2742780">slower</span> <span m="2743180">parts</span>
  <span m="2744400">and</span> <span m="2744820">decelerate.</span> <span m="2746752">So
  it</span> <span m="2747235">becomes</span> <span m="2747718">a shock</span> <span
  m="2748201">wave.</span></p><p><span m="2751270">So</span> <span m="2751430">let''s</span>
  <span m="2751840">start</span> <span m="2752070">to</span> <span m="2752170">modify</span>
  <span m="2752570">this</span> <span m="2753430">to</span> <span m="2753790">an</span>
  <span m="2754230">upwinding</span> <span m="2754370">scheme.</span> <span m="2757640">We</span>
  <span m="2757810">computed</span> <span m="2758830">F_bar.</span> <span m="2759620">And</span>
  <span m="2759910">we</span> <span m="2760020">have</span> <span m="2760200">a</span>
  <span m="2760380">c.</span> <span m="2761210">c</span> <span m="2761500">is</span>
  <span m="2761690">equal</span> <span m="2761790">to</span> <span m="2762040">1-u_bar
  times 2.</span> <span m="2767730">OK.</span> <span m="2768760">And</span> <span
  m="2768970">the</span> <span m="2769050">c</span> <span m="2769560">at</span> <span
  m="2769810">k_plus_half</span> <span m="2774330">is</span> <span m="2774750">equal</span>
  <span m="2775190">to</span> <span m="2776410">c</span> <span m="2777260">plus--</span>
  <span m="2781250">OK.</span> <span m="2781720">Let</span> <span m="2782380">me</span>
  <span m="2782480">do</span> <span m="2782840">like this.</span></p><p><span m="2784150">So</span>
  <span m="2784340">in</span> <span m="2784710">the</span> <span m="2784810">condition,</span>
  <span m="2785620">instead</span> <span m="2786040">of</span> <span m="2786980">u_bar,</span>
  <span m="2790808">I''m</span> <span m="2791260">going</span> <span m="2791450">to</span>
  <span m="2791580">put</span> <span m="2792040">c.</span> <span m="2798640">OK.</span>
  <span m="2799140">Here,</span> <span m="2799380">too.</span> <span m="2800490">Instead</span>
  <span m="2800970">of</span> <span m="2801160">the</span> <span m="2801540">u_bar,</span>
  <span m="2802700">I''m</span> <span m="2802930">going</span> <span m="2803130">to</span>
  <span m="2803300">put c.</span> <span m="2807170">OK.</span></p><p><span m="2808930">So</span>
  <span m="2809160">this</span> <span m="2809450">completes</span> <span m="2809950">my</span>
  <span m="2810460">upwinding.</span> <span m="2811220">And</span> <span m="2811420">let''s</span>
  <span m="2811630">try</span> <span m="2812065">it</span> <span m="2812720">again.</span>
  <span m="2816400">We</span> <span m="2816470">still</span> <span m="2816750">have</span>
  <span m="2816940">the</span> <span m="2817385">solution.</span> <span m="2818275">But</span>
  <span m="2819610">the</span> <span m="2819730">lower</span> <span m="2819990">density</span>
  <span m="2820330">goes</span> <span m="2820670">faster.</span> <span m="2821110">High</span>
  <span m="2821550">density</span> <span m="2821990">goes</span> <span m="2822430">slower</span>
  <span m="2822755">[INAUDIBLE]</span> <span m="2825430">high</span> <span m="2825900">density,</span>
  <span m="2826370">but now</span> <span m="2826840">it''s</span> <span m="2827310">[INAUDIBLE]</span>
  <span m="2829310">stability.</span> <span m="2829844">So</span> <span m="2830318">that''s
  good.</span></p><p><span m="2833640">And</span> <span m="2833990">if</span> <span
  m="2834160">you</span> <span m="2834250">want</span> <span m="2834470">to get</span>
  <span m="2834710">better</span> <span m="2835040">solution,</span> <span m="2835830">I</span>
  <span m="2835960">can</span> <span m="2836200">change</span> <span m="2836510">this</span>
  <span m="2836700">to</span> <span m="2836900">256.</span> <span m="2838124">And</span>
  <span m="2838532">I round</span> <span m="2838940">this.</span> <span m="2840630">And</span>
  <span m="2841440">I</span> <span m="2841610">[INAUDIBLE]</span> <span m="2841890">the
  top</span> <span m="2842387">[INAUDIBLE].</span> <span m="2852060">OK.</span> <span
  m="2852340">So</span> <span m="2852520">now,</span> <span m="2853050">let''s</span>
  <span m="2853760">say</span> <span m="2855030">at</span> <span m="2855530">this</span>
  <span m="2855820">point,</span> <span m="2856360">so</span> <span m="2857480">at
  either</span> <span m="2857630">the</span> <span m="2857830">beginning</span> <span
  m="2858330">[INAUDIBLE],</span> <span m="2860700">I have time</span> <span m="2860810">equal
  to</span> <span m="2861065">1,</span> <span m="2861798">we</span> <span m="2862276">get
  a red light.</span></p><p><span m="2864190">And at</span> <span m="2864640">time</span>
  <span m="2864890">equal</span> <span m="2865000">to</span> <span m="2865280">2,</span>
  <span m="2865950">we</span> <span m="2866400">turn</span> <span m="2866680">the
  light</span> <span m="2866930">to</span> <span m="2867270">green.</span> <span m="2867900">[INAUDIBLE]</span>
  <span m="2868390">there.</span> <span m="2869860">OK.</span> <span m="2871820">So
  we do</span> <span m="2872310">that.</span> <span m="2874130">[INAUDIBLE]</span>
  <span m="2875080">then</span> <span m="2875530">that</span> <span m="2875980">[INAUDIBLE]</span>
  <span m="2876670">what</span> <span m="2877010">we</span> <span m="2877110">need</span>
  <span m="2877280">to</span> <span m="2877370">do</span> <span m="2879220">to</span>
  <span m="2879370">make</span> <span m="2879620">that</span> <span m="2879770">happen.</span>
  <span m="2881530">The</span> <span m="2881630">key</span> <span m="2881720">thing</span>
  <span m="2881960">is</span> <span m="2882280">now</span> <span m="2882630">you</span>
  <span m="2882890">have</span> <span m="2884040">time.</span> <span m="2884750">You</span>
  <span m="2884800">have</span> <span m="2885040">t</span> <span m="2885440">available</span>
  <span m="2886670">to</span> <span m="2886790">you.</span></p><p><span m="2887130">So
  you can</span> <span m="2887280">basically</span> <span m="2889152">do a</span>
  <span m="2890560">conditional</span> <span m="2891220">statement</span> <span m="2891290">on</span>
  <span m="2891480">t.</span> <span m="2892950">If</span> <span m="2893290">t</span>
  <span m="2893650">is</span> <span m="2894060">greater</span> <span m="2894170">than
  1</span> <span m="2894450">and</span> <span m="2894948">t is</span> <span m="2895446">less
  than</span> <span m="2895944">2,</span> <span m="2897936">set the</span> <span m="2898434">red
  light.</span> <span m="2902916">[INAUDIBLE].</span></p><p><span m="2903912">AUDIENCE:
  What about</span> <span m="2904410">[INAUDIBLE]?</span></p><p><span m="2909400">QIQI
  WANG: Oh.</span> <span m="2911600">Thank</span> <span m="2911850">you.</span> <span
  m="2912290">That</span> <span m="2912540">is</span> <span m="2912690">wrong.</span>
  <span m="2913050">So</span> <span m="2913270">it</span> <span m="2913390">should</span>
  <span m="2913540">be</span> <span m="2913670">F_bar_k.</span> <span m="2918690">Yeah,</span>
  <span m="2918940">it should be</span> <span m="2919408">F_bar_k.</span> <span m="2923620">Thanks.</span>
  <span m="2926350">Yeah.</span> <span m="2927420">I</span> <span m="2927800">should</span>
  <span m="2928010">just</span> <span m="2928370">rename</span> <span m="2928870">it</span>
  <span m="2928960">to</span> <span m="2929040">something</span> <span m="2929400">else,</span>
  <span m="2929720">so</span> <span m="2929960">that--</span> <span m="2934369">I''m
  just</span> <span m="2934830">going</span> <span m="2934950">to</span> <span m="2935140">rename</span>
  <span m="2935530">it</span> <span m="2935640">as</span> <span m="2937840">2t.</span>
  <span m="2942295">All right.</span></p><p><span m="2945760">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="2951700">QIQI WANG: Which one</span> <span m="2952690">[INAUDIBLE]?</span></p><p><span
  m="2954670">AUDIENCE: [INAUDIBLE]</span></p><p><span m="2959150">QIQI WANG: Sorry?</span></p><p><span
  m="2959900">AUDIENCE: [INAUDIBLE]</span></p><p><span m="2962400">QIQI WANG: This
  one?</span></p><p><span m="2962900">AUDIENCE: Yeah.</span> <span m="2963400">[INAUDIBLE]</span></p><p><span
  m="2966160">QIQI WANG: Yeah.</span> <span m="2966580">[INAUDIBLE]</span> <span m="2967170">plus</span>
  <span m="2967590">1, right?</span> <span m="2968430">So</span> <span m="2968710">because</span>
  <span m="2969280">I''m</span> <span m="2969420">looking,</span> <span m="2970230">I</span>
  <span m="2970460">[INAUDIBLE]</span> <span m="2970680">the</span> <span m="2970800">interface.</span>
  <span m="2971530">I</span> <span m="2971650">want</span> <span m="2971850">to</span>
  <span m="2971920">look</span> <span m="2972390">at the</span> <span m="2972860">interface</span>
  <span m="2973330">[INAUDIBLE]</span> <span m="2973800">decide</span> <span m="2975460">which</span>
  <span m="2975700">side</span> <span m="2976100">I should</span> <span m="2976810">upwind</span>
  <span m="2977180">the</span> <span m="2977580">flux</span> <span m="2977930">at</span>
  <span m="2978404">k_plus_half.</span> <span m="2982200">In</span> <span m="2982430">order</span>
  <span m="2982640">to</span> <span m="2982710">make</span> <span m="2982920">a</span>
  <span m="2983020">decision,</span> <span m="2983620">I</span> <span m="2983770">want</span>
  <span m="2984430">my</span> <span m="2987240">[INAUDIBLE]</span> <span m="2988030">speed</span>
  <span m="2988335">at</span> <span m="2988640">k_plus_half.</span></p><p><span m="2990440">And</span>
  <span m="2990890">the right way</span> <span m="2991340">to</span> <span m="2991790">[INAUDIBLE]</span>
  <span m="2991970">the other</span> <span m="2992670">[INAUDIBLE]</span> <span m="2993120">here</span>
  <span m="2993460">k_plus_half</span> <span m="2993941">is</span> <span m="2994422">take</span>
  <span m="2994903">the</span> <span m="2995384">average</span> <span m="2995865">of
  the</span> <span m="2996827">[INAUDIBLE]</span> <span m="2997308">speed</span> <span
  m="2997789">[INAUDIBLE]</span> <span m="2998270">at</span> <span m="2998751">k(and)</span>
  <span m="2999720">k plus</span> <span m="2999900">1.</span> <span m="3005000">Just</span>
  <span m="3005230">to</span> <span m="3005340">make</span> <span m="3005550">the</span>
  <span m="3005650">code</span> <span m="3005960">easier</span> <span m="3006340">to</span>
  <span m="3006460">understand,</span> <span m="3007120">I</span> <span m="3007220">just</span>
  <span m="3007400">want</span> <span m="3007720">to change--</span> <span m="3011560">I</span>
  <span m="3011630">think</span> <span m="3011890">I</span> <span m="3011950">want</span>
  <span m="3012250">to</span> <span m="3012790">replace--</span> <span m="3016730">oh.</span>
  <span m="3019680">I</span> <span m="3019800">think</span> <span m="3020100">I</span>
  <span m="3020160">want</span> <span m="3020430">to</span> <span m="3021640">replace</span>
  <span m="3022750">my</span> <span m="3023080">i</span> <span m="3023520">with</span>
  <span m="3023830">k.</span> <span m="3028000">[INAUDIBLE].</span> <span m="3032910">All</span>
  <span m="3033350">right.</span></p><p><span m="3035850">Yeah.</span> <span m="3036160">So</span>
  <span m="3036280">instead</span> <span m="3036590">of--</span> <span m="3037702">it''s</span>
  <span m="3038198">easier to</span> <span m="3038694">replace</span> <span m="3039960">[INAUDIBLE]</span>
  <span m="3040360">k_plus_half</span> <span m="3040940">than</span> <span m="3041412">[INAUDIBLE].</span></p><p><span
  m="3046132">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3048970">QIQI WANG: Why</span>
  <span m="3049120">did I</span> <span m="3049350">half</span> <span m="3049768">t?</span>
  <span m="3051440">I</span> <span m="3051510">wanted</span> <span m="3051700">to</span>
  <span m="3051800">half</span> <span m="3052190">t,</span> <span m="3052540">because</span>
  <span m="3054320">what</span> <span m="3054520">I</span> <span m="3054640">like</span>
  <span m="3054880">you to</span> <span m="3055120">do</span> <span m="3055310">now</span>
  <span m="3055800">is</span> <span m="3056050">to</span> <span m="3056530">set</span>
  <span m="3057010">a</span> <span m="3057320">[INAUDIBLE]</span> <span m="3057880">when</span>
  <span m="3058390">t</span> <span m="3059060">is</span> <span m="3059895">[INAUDIBLE].</span>
  <span m="3078210">OK.</span> <span m="3078710">So what</span> <span m="3079180">happens</span>
  <span m="3079680">on the</span> <span m="3080180">red light?</span></p><p><span
  m="3082180">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3083680">QIQI WANG: Huh?</span></p><p><span
  m="3084601">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3086710">QIQI WANG: Yeah,</span>
  <span m="3086840">the</span> <span m="3087060">[INAUDIBLE]</span> <span m="3087180">goes</span>
  <span m="3087643">to</span> <span m="3088106">0.</span> <span m="3088570">That''s</span>
  <span m="3088960">one</span> <span m="3089210">way</span> <span m="3089360">to say
  it.</span> <span m="3090040">Another</span> <span m="3090360">way</span> <span m="3090710">to
  say it</span> <span m="3091060">is no</span> <span m="3091350">cars</span> <span
  m="3091807">can</span> <span m="3092264">pass,</span> <span m="3092721">right?</span>
  <span m="3094549">If</span> <span m="3095010">no</span> <span m="3095300">cars can</span>
  <span m="3095777">pass,</span> <span m="3096254">then the</span> <span m="3096731">[INAUDIBLE]</span>
  <span m="3097208">pass</span> <span m="3097685">through the</span> <span m="3098162">red</span>
  <span m="3098639">light is</span> <span m="3099116">what?</span> <span m="3101030">0,</span>
  <span m="3101520">right?</span></p><p><span m="3104880">So</span> <span m="3105130">what</span>
  <span m="3105350">I</span> <span m="3105460">can</span> <span m="3105890">do</span>
  <span m="3106120">here</span> <span m="3106540">is</span> <span m="3106810">that</span>
  <span m="3108330">before</span> <span m="3108770">I</span> <span m="3108860">compute</span>
  <span m="3110070">k</span> <span m="3110340">minus</span> <span m="3110760">half,</span>
  <span m="3111150">I</span> <span m="3111370">just</span> <span m="3111690">want</span>
  <span m="3111960">to</span> <span m="3112080">say</span> <span m="3113190">if</span>
  <span m="3114200">k</span> <span m="3114500">is greater</span> <span m="3114870">than</span>
  <span m="3115130">1</span> <span m="3115795">t</span> <span m="3116080">is</span>
  <span m="3116430">less</span> <span m="3116640">than</span> <span m="3116820">2,</span>
  <span m="3119720">F_k_plus_half</span> <span m="3123380">at</span> <span m="3123570">the</span>
  <span m="3123700">end--</span> <span m="3124430">so</span> <span m="3124820">k_plus_half--</span>
  <span m="3125270">the</span> <span m="3125745">last one is</span> <span m="3126220">basically</span>
  <span m="3126695">the</span> <span m="3127170">right</span> <span m="3127495">hand</span>
  <span m="3127820">and</span> <span m="3128100">also the</span> <span m="3128497">left
  hand--</span> <span m="3129690">is</span> <span m="3129920">equal</span> <span m="3130510">to</span>
  <span m="3130610">0.</span> <span m="3132818">I think</span> <span m="3133300">I</span>
  <span m="3133782">[INAUDIBLE].</span></p><p><span m="3136680">OK.</span> <span m="3137000">That''s</span>
  <span m="3137478">it.</span> <span m="3139868">That''s</span> <span m="3140350">what</span>
  <span m="3140520">I</span> <span m="3140590">need</span> <span m="3140770">to</span>
  <span m="3140860">do.</span> <span m="3142360">Now,</span> <span m="3142650">in</span>
  <span m="3142780">the</span> <span m="3142870">trafficDriver,</span> <span m="3145288">let</span>
  <span m="3145774">me set it</span> <span m="3146260">to--</span> <span m="3148690">ah,</span>
  <span m="3149176">ah,</span> <span m="3149662">ah.</span> <span m="3151620">Let</span>
  <span m="3151770">me</span> <span m="3151870">copy</span> <span m="3152240">this</span>
  <span m="3152460">trafficDriver</span> <span m="3152770">for the</span> <span m="3153578">[INAUDIBLE].</span></p><p><span
  m="3159320">Yeah.</span> <span m="3159520">I</span> <span m="3159560">think</span>
  <span m="3159760">we''re</span> <span m="3159930">overwriting</span> <span m="3160620">[INAUDIBLE].</span>
  <span m="3161690">And</span> <span m="3161880">it''s</span> <span m="3162020">going</span>
  <span m="3162210">to</span> <span m="3162710">save</span> <span m="3162920">trafficDriver</span>
  <span m="3165960">[INAUDIBLE].</span> <span m="3174420">OK.</span> <span m="3178290">Now,</span>
  <span m="3178690">instead</span> <span m="3178890">of</span> <span m="3179110">1</span>
  <span m="3179220">over</span> <span m="3179450">dt,</span> <span m="3179650">I''m
  going</span> <span m="3179965">to</span> <span m="3180280">simulate it</span> <span
  m="3180745">for</span> <span m="3181210">five</span> <span m="3182170">time</span>
  <span m="3182650">units,</span> <span m="3183840">so</span> <span m="3184040">that</span>
  <span m="3184240">I</span> <span m="3184370">actually</span> <span m="3184760">see</span>
  <span m="3186880">the</span> <span m="3187100">light.</span></p><p><span m="3190640">OK.</span>
  <span m="3191100">We</span> <span m="3191240">see</span> <span m="3191570">the</span>
  <span m="3191690">same</span> <span m="3192060">thing</span> <span m="3192940">here</span>
  <span m="3193410">[INAUDIBLE].</span> <span m="3196362">At</span> <span m="3196854">sometimes,</span>
  <span m="3197840">the light</span> <span m="3198210">[INAUDIBLE].</span> <span m="3202450">Yeah,</span>
  <span m="3202900">OK.</span> <span m="3203390">See,</span> <span m="3205194">the
  lights</span> <span m="3205645">is in</span> <span m="3206100">effect</span> <span
  m="3206370">here.</span> <span m="3206660">All</span> <span m="3206890">the</span>
  <span m="3207010">[INAUDIBLE]</span> <span m="3207460">simulates</span> <span m="3208010">here.</span>
  <span m="3208590">And</span> <span m="3208810">then</span> <span m="3208900">we</span>
  <span m="3209030">have</span> <span m="3210150">even</span> <span m="3210600">[INAUDIBLE]</span>
  <span m="3211280">that</span> <span m="3211470">actually</span> <span m="3211860">goes</span>
  <span m="3212110">backward.</span></p><p><span m="3214690">OK.</span> <span m="3214990">Now,</span>
  <span m="3215310">there</span> <span m="3215440">is</span> <span m="3215630">no</span>
  <span m="3215990">cars</span> <span m="3217080">moving.</span> <span m="3218280">All
  the</span> <span m="3218739">cars</span> <span m="3219198">are stopped over</span>
  <span m="3219657">there.</span> <span m="3222870">So</span> <span m="3222950">this</span>
  <span m="3223120">is</span> <span m="3223210">a</span> <span m="3223350">parking</span>
  <span m="3223680">lot</span> <span m="3223950">while</span> <span m="3224700">there
  is</span> <span m="3225070">no</span> <span m="3225290">cars</span> <span m="3225680">here.</span>
  <span m="3226680">And</span> <span m="3226850">at</span> <span m="3227247">[INAUDIBLE]</span>
  <span m="3227445">equal to</span> <span m="3227644">2</span> <span m="3228041">or</span>
  <span m="3228440">[INAUDIBLE].</span></p><p><span m="3231684">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="3243660">QIQI WANG: Did I--</span> <span m="3245656">did</span> <span m="3246155">I--</span>
  <span m="3253640">what''s</span> <span m="3254139">happening?</span> <span m="3256140">OK.</span>
  <span m="3256460">If t is</span> <span m="3256920">greater</span> <span m="3257170">than
  1</span> <span m="3257644">and</span> <span m="3258118">t</span> <span m="3258592">is
  less</span> <span m="3259066">than 2--</span></p><p><span m="3260962">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="3263332">QIQI WANG: And</span> <span m="3263810">never</span>
  <span m="3264080">goes</span> <span m="3264580">passed 2,</span> <span m="3265080">are
  you sure?</span></p><p><span m="3270026">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="3293960">QIQI WANG: OK.</span> <span m="3294380">I think</span> <span m="3294836">I
  know</span> <span m="3295292">what''s happening.</span> <span m="3298028">So I</span>
  <span m="3298490">actually</span> <span m="3298930">have come to a</span> <span
  m="3299390">situation</span> <span m="3299920">where--</span> <span m="3302308">hm,</span>
  <span m="3302800">let me</span> <span m="3303292">think.</span></p><p><span m="3321988">AUDIENCE:
  [INAUDIBLE].</span> <span m="3324450">What</span></p><p><span m="3325330">QIQI WANG:
  Yeah.</span> <span m="3326896">Let</span> <span m="3327290">me</span> <span m="3327390">do</span>
  <span m="3327600">this.</span> <span m="3328590">I''m</span> <span m="3328790">actually</span>
  <span m="3329070">encountering</span> <span m="3330790">a</span> <span m="3330910">situation</span>
  <span m="3331610">that</span> <span m="3332050">cannot</span> <span m="3332580">be</span>
  <span m="3332730">handled</span> <span m="3333210">by</span> <span m="3333490">this</span>
  <span m="3333960">[INAUDIBLE].</span> <span m="3339610">What</span> <span m="3339870">is</span>
  <span m="3340160">happening</span> <span m="3340450">is</span> <span m="3340700">that</span>
  <span m="3341950">[INAUDIBLE]--</span> <span m="3345940">let</span> <span m="3346160">me</span>
  <span m="3346340">do this.</span> <span m="3346780">I</span> <span m="3347130">think</span>
  <span m="3348240">I</span> <span m="3348370">can</span> <span m="3348790">change</span>
  <span m="3349210">this</span> <span m="3349530">around</span> <span m="3350010">by</span>
  <span m="3350340">doing</span> <span m="3350796">this.</span> <span m="3354450">I
  can</span> <span m="3354650">change</span> <span m="3355060">this</span> <span m="3355290">around</span>
  <span m="3355460">by</span> <span m="3357400">not</span> <span m="3357770">letting</span>
  <span m="3358130">the</span> <span m="3358230">red</span> <span m="3358440">light</span>
  <span m="3359860">to</span> <span m="3360040">stop</span> <span m="3360390">for</span>
  <span m="3360530">that</span> <span m="3360740">long.</span></p><p><span m="3361280">So</span>
  <span m="3362690">I</span> <span m="3362870">only</span> <span m="3363170">let</span>
  <span m="3363430">the</span> <span m="3363560">red</span> <span m="3363790">light</span>
  <span m="3364589">to--</span> <span m="3370460">if</span> <span m="3370640">I</span>
  <span m="3370780">only</span> <span m="3371040">let</span> <span m="3371360">the</span>
  <span m="3371490">red</span> <span m="3371740">light</span> <span m="3372880">go</span>
  <span m="3373370">from</span> <span m="3373610">0.2,</span> <span m="3376730">I</span>
  <span m="3376820">think</span> <span m="3377810">I''m</span> <span m="3377950">going</span>
  <span m="3378110">to</span> <span m="3378190">get</span> <span m="3378390">rid</span>
  <span m="3378570">of</span> <span m="3378710">the</span> <span m="3379103">problem.</span>
  <span m="3379890">The</span> <span m="3380000">problem</span> <span m="3380410">is</span>
  <span m="3380560">that</span> <span m="3381213">when</span> <span m="3381586">the</span>
  <span m="3381960">red light</span> <span m="3383220">happens</span> <span m="3383640">here,</span>
  <span m="3384950">the</span> <span m="3385350">flux--</span> <span m="3388590">the</span>
  <span m="3388780">P</span> <span m="3389190">at</span> <span m="3389390">one</span>
  <span m="3389670">side</span> <span m="3389840">shock wave</span> <span m="3390310">is</span>
  <span m="3390770">1.</span> <span m="3391200">At</span> <span m="3391330">the</span>
  <span m="3391440">other</span> <span m="3391740">side</span> <span m="3391960">of</span>
  <span m="3392080">the shock</span> <span m="3392558">wave,</span> <span m="3393036">the
  P</span> <span m="3393514">is equal to</span> <span m="3393992">0.</span></p><p><span
  m="3397820">So</span> <span m="3398040">both values</span> <span m="3398670">of</span>
  <span m="3398850">P</span> <span m="3400200">[INAUDIBLE]</span> <span m="3400510">equal</span>
  <span m="3401494">to</span> <span m="3402970">0.</span> <span m="3404718">Because
  the</span> <span m="3405164">flux is</span> <span m="3405610">P times</span> <span
  m="3406010">1</span> <span m="3406170">minus</span> <span m="3406760">P</span> <span
  m="3407425">or</span> <span m="3407850">P</span> <span m="3408115">minus</span>
  <span m="3408380">P squared.</span> <span m="3409856">So</span> <span m="3410350">the</span>
  <span m="3410480">other</span> <span m="3410730">P</span> <span m="3410950">is</span>
  <span m="3411170">1</span> <span m="3411450">or</span> <span m="3411730">zero.</span>
  <span m="3412640">The flux</span> <span m="3412980">is</span> <span m="3413437">equal
  to</span> <span m="3413894">0.</span> <span m="3414810">That''s</span> <span m="3415030">why</span>
  <span m="3415510">no matter</span> <span m="3415948">if you</span> <span m="3416386">take</span>
  <span m="3416824">upwinding</span> <span m="3417262">or downwinding,</span> <span
  m="3418138">you''ll</span> <span m="3418580">get</span> <span m="3418800">0 flux.</span></p><p><span
  m="3419840">So</span> <span m="3420270">this is</span> <span m="3420620">a case</span>
  <span m="3420880">where</span> <span m="3421786">[INAUDIBLE]</span> <span m="3422239">upwinding</span>
  <span m="3422692">wouldn''t</span> <span m="3424051">work.</span> <span m="3424960">It''s</span>
  <span m="3425210">like</span> <span m="3425480">a</span> <span m="3425590">singular</span>
  <span m="3425850">case</span> <span m="3426110">where</span> <span m="3426556">[INAUDIBLE]</span>
  <span m="3427002">upwinding</span> <span m="3427894">wouldn''t</span> <span m="3428340">work</span>
  <span m="3429180">over</span> <span m="3429440">here.</span> <span m="3430800">So</span>
  <span m="3430870">what</span> <span m="3431140">I''m</span> <span m="3431280">going</span>
  <span m="3431410">to</span> <span m="3431480">do</span> <span m="3431760">here</span>
  <span m="3432920">is</span> <span m="3433230">am</span> <span m="3433400">going</span>
  <span m="3433550">to</span> <span m="3433730">set</span> <span m="3435456">something</span>
  <span m="3435920">artificial.</span> <span m="3436670">And</span> <span m="3436920">let''s</span>
  <span m="3437010">say</span> <span m="3441770">when</span> <span m="3442120">there</span>
  <span m="3442290">is</span> <span m="3442470">a</span> <span m="3442550">red</span>
  <span m="3442780">light,</span> <span m="3443445">I think I''m</span> <span m="3443780">just</span>
  <span m="3443980">going to</span> <span m="3444110">set</span> <span m="3444220">the
  flux</span> <span m="3445200">equal to</span> <span m="3445300">0.01.</span> <span
  m="3446880">So</span> <span m="3447110">that</span> <span m="3449890">there</span>
  <span m="3450030">is</span> <span m="3450250">a</span> <span m="3450350">small</span>
  <span m="3450720">leakage</span> <span m="3451230">of</span> <span m="3451360">cars</span>
  <span m="3452340">over</span> <span m="3452660">the</span> <span m="3452870">red</span>
  <span m="3452950">light,</span> <span m="3453790">so</span> <span m="3454280">that</span>
  <span m="3454470">we</span> <span m="3454590">actually</span> <span m="3454770">want</span>
  <span m="3454870">to</span> <span m="3455060">see</span> <span m="3455560">what</span>
  <span m="3456060">is</span> <span m="3457060">going</span> <span m="3457560">to
  happen</span> <span m="3458060">[INAUDIBLE].</span></p><p><span m="3461986">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="3468200">QIQI WANG: Yeah.</span> <span m="3468678">So
  if</span> <span m="3469156">you take</span> <span m="3470130">[INAUDIBLE],</span>
  <span m="3470858">you''re going</span> <span m="3471306">to learn</span> <span m="3471754">about</span>
  <span m="3472202">the entropy</span> <span m="3472650">conditions</span> <span m="3473819">of</span>
  <span m="3476633">[INAUDIBLE].</span> <span m="3478040">And</span> <span m="3478509">the</span>
  <span m="3478978">entropy</span> <span m="3479450">condition</span> <span m="3479710">tells
  you</span> <span m="3480122">that</span> <span m="3480946">there is</span> <span
  m="3482212">a</span> <span m="3483478">physical</span> <span m="3484150">solution.</span>
  <span m="3484800">There is a</span> <span m="3484900">non-physical</span> <span
  m="3485080">solution.</span></p><p><span m="3487072">And</span> <span m="3488570">over</span>
  <span m="3488680">here</span> <span m="3489030">[INAUDIBLE].</span> <span m="3489840">But</span>
  <span m="3490050">then</span> <span m="3490130">over here</span> <span m="3490350">it</span>
  <span m="3490500">is</span> <span m="3490740">a</span> <span m="3491180">physical</span>
  <span m="3491420">solution.</span> <span m="3492264">While</span> <span m="3493110">this</span>
  <span m="3493330">kind of an</span> <span m="3493807">[INAUDIBLE]</span> <span m="3495715">is</span>
  <span m="3496192">going to be</span> <span m="3496669">a non-physical</span> <span
  m="3497146">solution.</span> <span m="3500970">And</span> <span m="3502240">that</span>
  <span m="3502390">cannot</span> <span m="3502820">be</span> <span m="3503140">dealt</span>
  <span m="3503500">with</span> <span m="3504430">by</span> <span m="3505330">the</span>
  <span m="3505450">[INAUDIBLE]</span> <span m="3505950">scheme.</span> <span m="3507160">And</span>
  <span m="3507360">you</span> <span m="3507510">nee</span> <span m="3507770">a</span>
  <span m="3507990">more</span> <span m="3508220">complex</span> <span m="3510430">flux
  scheme</span> <span m="3511480">to</span> <span m="3511970">deal</span> <span m="3512170">with</span>
  <span m="3512400">situations</span> <span m="3512895">like that.</span></p><p><span
  m="3515370">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3519650">QIQI WANG: There</span>
  <span m="3519840">is</span> <span m="3519950">no</span> <span m="3520180">downwinding.</span>
  <span m="3521170">And</span> <span m="3522390">what</span> <span m="3522740">you</span>
  <span m="3522810">need</span> <span m="3523050">to</span> <span m="3523140">do</span>
  <span m="3524410">is</span> <span m="3524740">this.</span> <span m="3527860">What</span>
  <span m="3528370">you</span> <span m="3528460">need</span> <span m="3528850">do</span>
  <span m="3529630">is</span> <span m="3529920">you</span> <span m="3530040">need</span>
  <span m="3530645">add</span> <span m="3531010">something</span> <span m="3531490">called</span>
  <span m="3531830">numerical</span> <span m="3532276">dispositing</span> <span m="3534060">into</span>
  <span m="3534380">this.</span> <span m="3535340">So</span> <span m="3535520">you</span>
  <span m="3535860">need</span> <span m="3536000">to</span> <span m="3536090">do</span>
  <span m="3536670">F_k_plus_half</span> <span m="3540206">is equal</span> <span m="3540620">to</span>
  <span m="3541770">F_k_plus_half</span> <span m="3543935">plus</span> <span m="3545360">0.5</span>
  <span m="3546580">times</span> <span m="3548320">absolute</span> <span m="3548940">value</span>
  <span m="3549410">of</span> <span m="3549610">c.</span></p><p><span m="3553790">So</span>
  <span m="3553980">instead</span> <span m="3554370">of</span> <span m="3560130">taking</span>
  <span m="3560450">the</span> <span m="3560540">c''s,</span> <span m="3561340">you</span>
  <span m="3561480">want</span> <span m="3561680">to</span> <span m="3561820">take</span>
  <span m="3562090">the</span> <span m="3562220">absolute</span> <span m="3562720">value</span>
  <span m="3563100">of</span> <span m="3563260">c''s</span> <span m="3563580">and</span>
  <span m="3563760">divide</span> <span m="3564020">by</span> <span m="3564290">2.</span>
  <span m="3566170">So</span> <span m="3566340">this</span> <span m="3566530">is</span>
  <span m="3566700">like</span> <span m="3566940">a</span> <span m="3567370">very</span>
  <span m="3567760">similar</span> <span m="3568190">concept</span> <span m="3569190">to</span>
  <span m="3569530">upwinding.</span> <span m="3570502">But</span> <span m="3570990">it</span>
  <span m="3571090">operates</span> <span m="3571587">differently.</span> <span m="3573080">You</span>
  <span m="3573140">need</span> <span m="3573300">to</span> <span m="3573450">take</span>
  <span m="3573910">the</span> <span m="3574330">absolute</span> <span m="3575050">value</span>
  <span m="3575470">of</span> <span m="3575700">c,</span> <span m="3577265">but</span>
  <span m="3577670">multiply</span> <span m="3578340">that</span> <span m="3578720">with</span>
  <span m="3579816">u_bar</span> <span m="3586734">and</span> <span m="3587231">plus_half.</span></p><p><span
  m="3588722">So it''s</span> <span m="3589219">minus</span> <span m="3590213">[INAUDIBLE]</span>
  <span m="3591922">u_bar</span> <span m="3595200">minus</span> <span m="3595660">1</span>
  <span m="3597490">0,</span> <span m="3597790">minus 1.</span> <span m="3600910">So</span>
  <span m="3601450">you</span> <span m="3601570">need</span> <span m="3601780">to</span>
  <span m="3601900">kind</span> <span m="3602100">of--</span> <span m="3602980">so</span>
  <span m="3603300">instead</span> <span m="3603750">of</span> <span m="3603880">doing</span>
  <span m="3604120">upwinding,</span> <span m="3605910">you</span> <span m="3606040">need</span>
  <span m="3606250">to</span> <span m="3607480">use</span> <span m="3607770">a</span>
  <span m="3608251">numerical</span> <span m="3608732">dispositive</span> <span m="3610660">or</span>
  <span m="3610950">a</span> <span m="3611030">numerical</span> <span m="3616000">diffusion</span>
  <span m="3617480">to</span> <span m="3617930">basically</span> <span m="3618540">achieve</span>
  <span m="3618930">the</span> <span m="3619060">impact</span> <span m="3619460">of</span>
  <span m="3619580">upwinding,</span> <span m="3620022">but</span> <span m="3620464">do
  this</span> <span m="3620906">a little</span> <span m="3621348">bit</span> <span
  m="3621790">differently.</span> <span m="3622680">But</span> <span m="3622930">that''s</span>
  <span m="3623200">kind</span> <span m="3623410">of</span> <span m="3623720">beyond</span>
  <span m="3624840">the</span> <span m="3624920">scope</span> <span m="3625360">of
  this</span> <span m="3625800">class.</span></p><p><span m="3626680">So,</span> <span
  m="3627840">yeah,</span> <span m="3628550">If</span> <span m="3628720">you</span>
  <span m="3628810">want</span> <span m="3629030">to</span> <span m="3629130">learn</span>
  <span m="3629350">that,</span> <span m="3629540">you''re welcome</span> <span m="3629968">to</span>
  <span m="3630396">take</span> <span m="3630824">the</span> <span m="3631252">[INAUDIBLE].</span>
  <span m="3632110">We are</span> <span m="3632250">going to be</span> <span m="3632820">learning</span>
  <span m="3633160">all about</span> <span m="3633590">[INAUDIBLE]</span> <span m="3634090">speed.</span>
  <span m="3636675">So let''s</span> <span m="3637140">see if</span> <span m="3638070">this
  goes</span> <span m="3638846">[INAUDIBLE].</span> <span m="3644798">OK.</span> <span
  m="3645294">So we have</span> <span m="3645790">the</span> <span m="3646286">[INAUDIBLE].</span></p><p><span
  m="3651742">OK.</span> <span m="3652238">Now, the</span> <span m="3652734">cars
  are</span> <span m="3653230">starting</span> <span m="3653750">to move.</span> <span
  m="3657282">[INAUDIBLE]</span> <span m="3662518">the</span> <span m="3663010">light</span>
  <span m="3663320">goes green,</span> <span m="3663766">the cars</span> <span m="3664212">start
  to</span> <span m="3664658">move.</span> <span m="3672000">To</span> <span m="3672130">do</span>
  <span m="3672260">it</span> <span m="3672380">properly,</span> <span m="3672860">you</span>
  <span m="3672960">have</span> <span m="3673100">to</span> <span m="3673200">change</span>
  <span m="3673710">this</span> <span m="3674110">back</span> <span m="3675110">to
  the</span> <span m="3676110">central</span> <span m="3676530">average.</span> <span
  m="3677500">So</span> <span m="3678000">you</span> <span m="3678170">do</span> <span
  m="3678650">upwinding</span> <span m="3679130">or</span> <span m="3679610">add</span>
  <span m="3680058">numerical</span> <span m="3680506">dispositive,</span> <span m="3680954">but
  don''t do</span> <span m="3681402">both.</span> <span m="3681850">And</span> <span
  m="3682298">doing</span> <span m="3682750">both,</span> <span m="3684700">so</span>
  <span m="3684850">the</span> <span m="3684950">scheme</span> <span m="3685300">works,</span>
  <span m="3686050">but</span> <span m="3686370">it''s</span> <span m="3686540">not</span>
  <span m="3686830">as</span> <span m="3687110">accurate.</span> <span m="3688446">It''s</span>
  <span m="3689140">suffers</span> <span m="3689750">from</span> <span m="3692270">additional</span>
  <span m="3692790">numerical</span> <span m="3693160">dissipation.</span></p><p><span
  m="3694490">OK.</span> <span m="3695130">So</span> <span m="3695380">I</span> <span
  m="3695470">hope</span> <span m="3695730">you</span> <span m="3697980">have</span>
  <span m="3698230">fun</span> <span m="3698633">playing</span> <span m="3699036">with</span>
  <span m="3699440">this</span> <span m="3700610">small</span> <span m="3700930">example</span>
  <span m="3701420">here.</span> <span m="3703230">So</span> <span m="3703680">starting</span>
  <span m="3704120">from</span> <span m="3704480">our</span> <span m="3704780">next</span>
  <span m="3705290">lecture,</span> <span m="3706560">the</span> <span m="3706660">next</span>
  <span m="3706850">lecture</span> <span m="3707250">we''re</span> <span m="3707360">going</span>
  <span m="3707480">to</span> <span m="3707540">be</span> <span m="3708090">doing</span>
  <span m="3708440">a</span> <span m="3708560">review</span> <span m="3709550">for</span>
  <span m="3709640">the</span> <span m="3709720">midterm.</span> <span m="3710822">But</span>
  <span m="3711210">starting</span> <span m="3711580">from</span> <span m="3711790">after</span>
  <span m="3712080">the</span> <span m="3712160">midterm,</span> <span m="3712530">we''re</span>
  <span m="3712710">going</span> <span m="3712830">to</span> <span m="3712900">be</span>
  <span m="3713030">talking</span> <span m="3713300">about</span> <span m="3713975">first
  of all,</span> <span m="3714410">stability</span> <span m="3716150">of</span> <span
  m="3716920">solution</span> <span m="3717360">of</span> <span m="3717480">positive</span>
  <span m="3717800">differential</span> <span m="3718120">equations,</span> <span
  m="3718630">and</span> <span m="3718900">then</span> <span m="3719555">talk</span>
  <span m="3719880">about</span> <span m="3720320">finite</span> <span m="3720752">[INAUDIBLE]</span>
  <span m="3721184">method,</span> <span m="3722050">which</span> <span m="3722260">is</span>
  <span m="3722440">the</span> <span m="3722610">third</span> <span m="3723010">method</span>
  <span m="3723410">we are</span> <span m="3723480">going to</span> <span m="3723580">start</span>
  <span m="3723740">in fall</span> <span m="3724140">for</span> <span m="3724470">[INAUDIBLE].</span>
  <span m="3728430">All right.</span> <span m="3729330">We''ll</span> <span m="3729630">see
  you</span> <span m="3729930">next week.</span></p>'
type: course
uid: c794a1410431b1c1beee633b24e3abc9

---
None