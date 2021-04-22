---
about_this_resource_text: <p><strong>Description:</strong> The video reviews accuracy
  and stability concepts, and then covers nonlinear systems in detail.</p> <p><strong>Instructors:</strong>
  Qiqi Wang</p><p>The recording quality of this video is the best available from the
  source.</p>
course_id: 16-90-computational-methods-in-aerospace-engineering-spring-2014
embedded_media:
- id: Video-YouTube-Stream
  media_location: nKNFP1PiIdo
  parent_uid: 746f4122d95cc3c2ef335f714bb892a4
  title: Video-YouTube-Stream
  type: Video
  uid: 11413375941f096f757da4d3496ffa5d
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/nKNFP1PiIdo/default.jpg
  parent_uid: 746f4122d95cc3c2ef335f714bb892a4
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 4a75c29b3567fc28301441baea123196
- id: 3Play-3PlayYouTubeid-MP4
  media_location: nKNFP1PiIdo
  parent_uid: 746f4122d95cc3c2ef335f714bb892a4
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: cab5f3ecb6ae8611aa951fa6a3d569bc
- id: nKNFP1PiIdo.srt
  parent_uid: 746f4122d95cc3c2ef335f714bb892a4
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-5-numerical-integration-of-odes-nonlinear-systems/nKNFP1PiIdo.srt
  title: 3play caption file
  type: null
  uid: e07b362cc5ebb2bcca2199df88aa0531
- id: nKNFP1PiIdo.pdf
  parent_uid: 746f4122d95cc3c2ef335f714bb892a4
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-5-numerical-integration-of-odes-nonlinear-systems/nKNFP1PiIdo.pdf
  title: 3play pdf file
  type: null
  uid: 8c8855c5c1eb65265d51515cb13c7468
- id: Caption-3Play YouTube id-SRT
  parent_uid: 746f4122d95cc3c2ef335f714bb892a4
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: d3f24c173d62cc068a2fbbc4b5391026
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 746f4122d95cc3c2ef335f714bb892a4
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: db0d39ec2aa25ed887df22ae988fe128
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT16.90S14/MIT16_90S14_L05_300k.mp4
  parent_uid: 746f4122d95cc3c2ef335f714bb892a4
  title: Video-Internet Archive-MP4
  type: Video
  uid: d10d41e53ce4991fe58e124045047dbb
inline_embed_id: 25849250session5:numericalintegrationofodes:nonlinearsystems77042570
layout: video
order_index: null
parent_uid: 809ebf7c44bfb36e8786306747d7e32f
related_resources_text: ''
short_url: session-5-numerical-integration-of-odes-nonlinear-systems
technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-5-numerical-integration-of-odes-nonlinear-systems
template_type: Tabbed
title: 'Session 5: Numerical Integration of ODEs: Nonlinear Systems'
transcript: '<p><span m="30">The</span> <span m="130">following</span> <span m="600">content</span>
  <span m="1090">is</span> <span m="1200">provided</span> <span m="1660">under</span>
  <span m="1900">a</span> <span m="1950">Creative</span> <span m="2400">Commons</span>
  <span m="2820">license.</span> <span m="3770">Your</span> <span m="3880">support</span>
  <span m="4400">will</span> <span m="4570">help</span> <span m="4790">MIT</span>
  <span m="5280">OpenCourseWare</span> <span m="6020">continue</span> <span m="6510">to</span>
  <span m="6680">offer</span> <span m="6980">high</span> <span m="7200">quality</span>
  <span m="7680">educational</span> <span m="8350">resources</span> <span m="8920">for</span>
  <span m="9040">free.</span> <span m="10100">To</span> <span m="10130">make</span>
  <span m="10330">a</span> <span m="10380">donation,</span> <span m="11090">or</span>
  <span m="11310">to</span> <span m="11430">view</span> <span m="11630">additional</span>
  <span m="12050">materials</span> <span m="12670">from</span> <span m="12850">hundreds</span>
  <span m="13180">of</span> <span m="13280">MIT</span> <span m="13650">courses,</span>
  <span m="14960">visit</span> <span m="15150">MIT</span> <span m="15670">OpenCourseWare</span>
  <span m="16580">at</span> <span m="16920">ocw.mit.edu.</span></p><p><span m="26920">All</span>
  <span m="27070">right,</span> <span m="27380">OK,</span> <span m="27810">let''s</span>
  <span m="28080">start.</span> <span m="29070">1690,</span> <span m="30370">Numerical</span>
  <span m="30780">Matters.</span> <span m="39450">Local</span> <span m="39850">accuracy</span>
  <span m="41150">and</span> <span m="41400">global</span> <span m="41770">accuracy,</span>
  <span m="42330">again,</span> <span m="42930">this</span> <span m="43120">is</span>
  <span m="43260">an</span> <span m="46320">distinction</span> <span m="46910">between</span>
  <span m="47300">local</span> <span m="47570">accuracy</span> <span m="48200">and</span>
  <span m="48500">the</span> <span m="48680">global</span> <span m="49010">accuracy.</span>
  <span m="50390">What</span> <span m="50590">is</span> <span m="50760">the</span>
  <span m="50890">distinction?</span> <span m="52360">What</span> <span m="53240">is</span>
  <span m="53800">that</span> <span m="54120">we</span> <span m="54340">ultimately</span>
  <span m="54990">want</span> <span m="55630">in</span> <span m="55850">a</span> <span
  m="55970">numerical</span> <span m="56270">method?</span></p><p><span m="58520">Do</span>
  <span m="58640">we</span> <span m="58900">ultimately</span> <span m="59490">want</span>
  <span m="59740">global</span> <span m="60060">accuracy</span> <span m="60540">or</span>
  <span m="60710">local</span> <span m="61030">accuracy?</span> <span m="63930">We</span>
  <span m="64180">ultimately</span> <span m="64680">want</span> <span m="64930">global</span>
  <span m="65420">accuracy,</span> <span m="66030">right?</span> <span m="66600">Local</span>
  <span m="67010">accuracy,</span> <span m="67600">actually,</span> <span m="69460">I</span>
  <span m="69540">mean</span> <span m="70020">if</span> <span m="70240">a</span> <span
  m="70470">scheme</span> <span m="70740">only</span> <span m="71090">has</span> <span
  m="71330">local</span> <span m="71790">accuracy,</span> <span m="73030">it''s</span>
  <span m="73560">useless.</span> <span m="75820">It</span> <span m="75990">is</span>
  <span m="76140">useful</span> <span m="76710">only</span> <span m="76910">[? if
  it has ?]</span> <span m="77480">global</span> <span m="77870">accuracy.</span>
  <span m="78360">Global</span> <span m="78720">accuracy</span> <span m="79090">means</span>
  <span m="79990">the</span> <span m="80120">solution</span> <span m="81390">using</span>
  <span m="82100">numerical</span> <span m="82570">method</span> <span m="82990">actually</span>
  <span m="83470">matches</span> <span m="85000">the</span> <span m="85160">true</span>
  <span m="85560">solution</span> <span m="86060">as</span> <span m="86280">my</span>
  <span m="86470">delta</span> <span m="86830">t</span> <span m="87490">goes</span>
  <span m="87720">to</span> <span m="88150">0.</span> <span m="88580">So</span> <span
  m="88910">global</span> <span m="89300">accuracy</span> <span m="89820">is</span>
  <span m="89990">what</span> <span m="90180">we</span> <span m="90330">want.</span></p><p><span
  m="93980">But</span> <span m="94190">how</span> <span m="94430">can</span> <span
  m="94590">we</span> <span m="94800">analyze</span> <span m="95500">global</span>
  <span m="95720">accuracy?</span> <span m="96890">We</span> <span m="97030">can</span>
  <span m="97410">only</span> <span m="98250">look</span> <span m="98740">at</span>
  <span m="98910">global</span> <span m="99210">accuracy</span> <span m="99620">when</span>
  <span m="99950">we</span> <span m="100120">of</span> <span m="100330">apply the</span>
  <span m="100690">scheme</span> <span m="101030">to</span> <span m="101120">solve</span>
  <span m="101480">a</span> <span m="101570">differential equation.</span> <span m="102750">Right?</span>
  <span m="104620">Is</span> <span m="104890">there</span> <span m="105210">a</span>
  <span m="105290">way</span> <span m="106600">to</span> <span m="106770">show</span>
  <span m="107150">global</span> <span m="107590">accuracy</span> <span m="108100">without</span>
  <span m="108730">actually</span> <span m="109290">coding</span> <span m="109760">it</span>
  <span m="110135">up</span> <span m="110510">and</span> <span m="110870">solve</span>
  <span m="111360">a</span> <span m="111510">particular</span> <span m="111970">differential
  equation?</span> <span m="118160">Is</span> <span m="118420">there</span> <span
  m="118600">a</span> <span m="118630">way</span> <span m="118830">to</span> <span
  m="118970">show</span> <span m="119550">global</span> <span m="119880">accuracy</span>
  <span m="120310">without</span> <span m="122750">applying this</span> <span m="123710">definition?</span></p><p><span
  m="126330">AUDIENCE: [INAUDIBLE]</span></p><p>&nbsp;</p><p><span m="136030">PROFESSOR:
  OK,</span> <span m="136290">so</span> <span m="136680">global</span> <span m="137040">accuracy</span>
  <span m="137560">means</span> <span m="138170">V</span> <span m="138580">at</span>
  <span m="138990">a</span> <span m="139100">particular</span> <span m="139710">time</span>
  <span m="141690">converges</span> <span m="142470">to</span> <span m="142720">u</span>
  <span m="143230">at</span> <span m="143510">t.</span> <span m="144280">So</span>
  <span m="144720">Vt</span> <span m="145170">is</span> <span m="145296">the</span>
  <span m="145423">numerical</span> <span m="145550">solution.</span> <span m="146750">ut</span>
  <span m="146840">is</span> <span m="148020">some</span> <span m="148280">true</span>
  <span m="148520">solution</span> <span m="148950">I</span> <span m="149050">may</span>
  <span m="149330">or</span> <span m="149470">may</span> <span m="149640">not know,</span>
  <span m="150050">depending</span> <span m="150440">on</span> <span m="150520">what</span>
  <span m="150660">equation it</span> <span m="151060">is.</span> <span m="153430">So</span>
  <span m="153790">this</span> <span m="154080">is</span> <span m="154260">global</span>
  <span m="154600">accuracy.</span></p><p><span m="155330">I</span> <span m="155420">mean,</span>
  <span m="155560">of</span> <span m="155700">course</span> <span m="155910">I</span>
  <span m="155970">can</span> <span m="156210">check</span> <span m="156450">global</span>
  <span m="156600">accuracy</span> <span m="156840">by</span> <span m="157340">applying</span>
  <span m="157840">my</span> <span m="158340">scheme to</span> <span m="158480">a</span>
  <span m="158550">particular</span> <span m="158900">differential equation.</span>
  <span m="160330">But</span> <span m="160580">is</span> <span m="160830">there</span>
  <span m="161230">a</span> <span m="161330">way</span> <span m="162480">I</span>
  <span m="162650">can</span> <span m="162910">know</span> <span m="163270">if</span>
  <span m="163460">a</span> <span m="163540">scheme</span> <span m="163870">is</span>
  <span m="164080">globally</span> <span m="164580">accurate</span> <span m="165040">or</span>
  <span m="165160">not</span> <span m="165490">without</span> <span m="165990">[INAUDIBLE]</span>
  <span m="166490">apply?</span> <span m="167060">Yes?</span></p><p><span m="167831">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="170660">PROFESSOR: Yes.</span> <span m="171200">That''s</span>
  <span m="171600">the</span> <span m="171790">answer</span> <span m="172140">I''m</span>
  <span m="172270">looking</span> <span m="172640">for.</span> <span m="172940">If</span>
  <span m="173590">the</span> <span m="173770">scheme</span> <span m="174250">is</span>
  <span m="174880">locally</span> <span m="175500">accurate,</span> <span m="176740">which</span>
  <span m="177250">is</span> <span m="177460">also</span> <span m="177720">consistent,</span>
  <span m="178920">and</span> <span m="179810">it is</span> <span m="180190">0</span>
  <span m="180570">stable,</span> <span m="182080">then</span> <span m="182470">I</span>
  <span m="182630">know</span> <span m="182930">whatever</span> <span m="183540">differential
  equation</span> <span m="184350">I</span> <span m="184620">applied it</span> <span
  m="184950">to,</span> <span m="186260">I''m</span> <span m="186410">going</span>
  <span m="186530">to</span> <span m="186610">get</span> <span m="187050">global</span>
  <span m="187590">accuracy.</span> <span m="190240">This</span> <span m="190460">is</span>
  <span m="190580">a</span> <span m="190670">good</span> <span m="190850">thing</span>
  <span m="191020">because</span> <span m="191320">it</span> <span m="191460">is</span>
  <span m="191670">independent</span> <span m="192470">of</span> <span m="192590">what</span>
  <span m="192750">differential</span> <span m="193080">equation</span> <span m="193470">I</span>
  <span m="193860">look</span> <span m="194070">at.</span></p><p><span m="197340">If</span>
  <span m="197590">I</span> <span m="197720">can</span> <span m="198740">show</span>
  <span m="199260">local</span> <span m="199880">accuracy,</span> <span m="201220">which</span>
  <span m="201660">doesn''t</span> <span m="201960">require</span> <span m="202420">me</span>
  <span m="202560">to</span> <span m="202650">implement</span> <span m="203160">anything,</span>
  <span m="203880">I</span> <span m="204100">just</span> <span m="205110">do</span>
  <span m="205541">what?</span> <span m="208130">How</span> <span m="208380">do I</span>
  <span m="208600">show</span> <span m="208780">local</span> <span m="209550">accuracy?</span></p><p><span
  m="210506">AUDIENCE: Parallel</span> <span m="210984">theory?</span></p><p><span
  m="212160">PROFESSOR: Parallel</span> <span m="212200">theory</span> <span m="212610">is</span>
  <span m="212780">right.</span> <span m="214150">You</span> <span m="214330">can</span>
  <span m="214560">show</span> <span m="214780">local</span> <span m="215200">accuracy</span>
  <span m="215650">by</span> <span m="215790">applying</span> <span m="215860">parallel</span>
  <span m="216200">theory</span> <span m="216360">as</span> <span m="216800">analysis.</span>
  <span m="218130">And</span> <span m="218620">can</span> <span m="218880">you</span>
  <span m="219000">also</span> <span m="219280">show</span> <span m="219650">zero
  stability</span> <span m="220480">without</span> <span m="221480">implementing</span>
  <span m="222510">anything?</span></p><p><span m="224910">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="229230">PROFESSOR: Exactly.</span> <span m="229870">You</span> <span m="229980">can</span>
  <span m="230190">plug in</span> <span m="230770">the</span> <span m="230940">du
  dt</span> <span m="231530">equal to</span> <span m="231820">0.</span> <span m="232180">So</span>
  <span m="232560">0</span> <span m="232850">stability</span> <span m="233560">is</span>
  <span m="234510">if</span> <span m="234780">a</span> <span m="235222">scheme</span>
  <span m="235664">can</span> <span m="236106">solve this.</span> <span m="236990">Usually,</span>
  <span m="237390">whatever</span> <span m="237720">scheme</span> <span m="238020">you</span>
  <span m="238190">have,</span> <span m="238960">you''re</span> <span m="239340">plugging</span>
  <span m="239930">this</span> <span m="240300">previous</span> <span m="241160">differential
  equation</span> <span m="241600">into</span> <span m="242120">the</span> <span m="242220">scheme.</span>
  <span m="242930">You</span> <span m="243060">can</span> <span m="243190">analyze</span>
  <span m="243890">this</span> <span m="244120">behavior</span> <span m="244750">analytically.</span>
  <span m="246090">You</span> <span m="246260">can</span> <span m="246480">plug in</span>
  <span m="247270">an</span> <span m="247500">exponentially</span> <span m="249100">growing</span>
  <span m="249530">solution</span> <span m="250440">to</span> <span m="250640">see</span>
  <span m="251140">if</span> <span m="251900">that</span> <span m="252200">solution</span>
  <span m="252550">is possible.</span></p><p><span m="254480">If</span> <span m="254790">an</span>
  <span m="254970">exponentially</span> <span m="255710">growing</span> <span m="256170">solution</span>
  <span m="256560">is</span> <span m="256709">possible,</span> <span m="257209">then</span>
  <span m="257579">the</span> <span m="257680">scheme</span> <span m="258060">is</span>
  <span m="258450">not</span> <span m="258740">zero</span> <span m="259185">stable.</span>
  <span m="260965">If</span> <span m="261410">an</span> <span m="261860">exponentially</span>
  <span m="262019">growing</span> <span m="262430">solution</span> <span m="267440">is</span>
  <span m="267580">possible,</span> <span m="268200">then</span> <span m="268370">it''s</span>
  <span m="268540">not</span> <span m="268790">zero stable.</span> <span m="269670">If</span>
  <span m="269820">an</span> <span m="270295">exponentially</span> <span m="270770">growing</span>
  <span m="271245">solution</span> <span m="271720">is not</span> <span m="271980">possible,</span>
  <span m="272800">then</span> <span m="273020">the</span> <span m="273100">scheme</span>
  <span m="273430">is</span> <span m="273770">zero stable.</span></p><p><span m="275480">Now</span>
  <span m="276130">you</span> <span m="276260">can</span> <span m="276450">show</span>
  <span m="276740">local</span> <span m="276930">order</span> <span m="277260">of</span>
  <span m="277410">accuracy</span> <span m="277920">and</span> <span m="278160">zero</span>
  <span m="278230">stability</span> <span m="279040">all</span> <span m="279320">without</span>
  <span m="279810">implementing</span> <span m="280590">the</span> <span m="280690">scheme</span>
  <span m="280880">on</span> <span m="281070">any</span> <span m="281340">differential
  equation.</span> <span m="283520">And</span> <span m="284155">once</span> <span
  m="284420">you</span> <span m="284560">have</span> <span m="284820">these</span>
  <span m="285030">tools</span> <span m="285360">through</span> <span m="285630">the</span>
  <span m="286290">[INAUDIBLE]</span> <span m="286580">equivalence</span> <span m="287070">theorem,</span>
  <span m="288190">you</span> <span m="288350">know</span> <span m="288820">the</span>
  <span m="288920">scheme</span> <span m="289300">is</span> <span m="289650">globally</span>
  <span m="290300">accurate</span> <span m="291830">when</span> <span m="292140">it</span>
  <span m="292260">is</span> <span m="292410">applied</span> <span m="292890">to</span>
  <span m="293080">any</span> <span m="293933">differential equation.</span> <span
  m="296790">Is</span> <span m="296920">it</span> <span m="297030">clear,</span> <span
  m="297810">the</span> <span m="298000">relationship</span> <span m="298630">between</span>
  <span m="299370">these</span> <span m="299770">three?</span></p><p><span m="304150">Global</span>
  <span m="304720">accuracy</span> <span m="305450">is</span> <span m="305800">what</span>
  <span m="306090">we</span> <span m="306220">want.</span> <span m="307740">This</span>
  <span m="308170">is</span> <span m="308510">what</span> <span m="308840">we</span>
  <span m="309000">want.</span> <span m="310640">What</span> <span m="312640">we</span>
  <span m="313330">want.</span> <span m="315632">And</span> <span m="316010">the</span>
  <span m="316230">zero</span> <span m="316750">stability</span> <span m="317250">and</span>
  <span m="317470">local</span> <span m="318100">accuracy</span> <span m="318410">is</span>
  <span m="318710">easy</span> <span m="319080">to</span> <span m="319260">analyze.</span>
  <span m="325750">And</span> <span m="326250">once</span> <span m="326550">we</span>
  <span m="326710">have</span> <span m="327050">the</span> <span m="327150">two</span>
  <span m="327490">easy</span> <span m="327840">to</span> <span m="328040">analyze</span>
  <span m="328990">things,</span> <span m="329940">we</span> <span m="330130">check</span>
  <span m="330540">these, then</span> <span m="330740">we</span> <span m="330860">automatically</span>
  <span m="331215">know</span> <span m="331570">global</span> <span m="332310">accuracy.</span>
  <span m="336050">So</span> <span m="336390">the</span> <span m="336600">relationship</span>
  <span m="337110">between</span> <span m="337440">these</span> <span m="338530">three</span>
  <span m="339160">are</span> <span m="339580">this</span> <span m="339920">simple.</span>
  <span m="340180">So</span> <span m="340440">when</span> <span m="340760">we</span>
  <span m="340920">have</span> <span m="341120">these</span> <span m="341320">two,</span>
  <span m="341600">that</span> <span m="341810">leads</span> <span m="342140">to</span>
  <span m="342390">global</span> <span m="342850">accuracy.</span></p><p><span m="345920">So
  we</span> <span m="346080">discussed</span> <span m="346350">zero stability.</span>
  <span m="348300">But</span> <span m="348960">zero stability</span> <span m="349760">is</span>
  <span m="349920">a</span> <span m="351330">pretty</span> <span m="351600">weak</span>
  <span m="351860">criterion.</span> <span m="353220">So</span> <span m="353420">zero
  stability</span> <span m="354200">means</span> <span m="355540">it</span> <span
  m="355970">can</span> <span m="356970">solve</span> <span m="357470">du</span> <span
  m="357720">dt.</span> <span m="358470">Yes,</span> <span m="359140">if</span> <span
  m="359310">a</span> <span m="359620">scheme</span> <span m="360040">is</span> <span
  m="361250">locally</span> <span m="361640">accurate</span> <span m="362100">and</span>
  <span m="362400">zero</span> <span m="362650">stable,</span> <span m="363780">we</span>
  <span m="364030">are</span> <span m="364200">going</span> <span m="364410">to</span>
  <span m="364530">have</span> <span m="365520">global</span> <span m="365890">accuracy.</span>
  <span m="366840">But</span> <span m="367050">sometimes,</span> <span m="368020">global</span>
  <span m="368550">accuracy</span> <span m="369500">may</span> <span m="369660">not</span>
  <span m="370170">be</span> <span m="370830">enough.</span></p><p><span m="371490">I''m</span>
  <span m="371700">going</span> <span m="371820">to</span> <span m="371890">show</span>
  <span m="372100">an</span> <span m="372240">example</span> <span m="372590">of</span>
  <span m="372650">why</span> <span m="372850">global accuracy</span> <span m="373140">is</span>
  <span m="373400">not</span> <span m="373835">enough.</span> <span m="375140">So</span>
  <span m="375290">global accuracy</span> <span m="375610">only</span> <span m="376025">says</span>
  <span m="376440">that</span> <span m="376730">[INAUDIBLE]</span> <span m="377290">equal</span>
  <span m="377560">to</span> <span m="377910">zero.</span> <span m="379365">[INAUDIBLE]</span>
  <span m="380335">solution</span> <span m="380820">[INAUDIBLE]</span> <span m="381790">analytical</span>
  <span m="382275">[INAUDIBLE],</span> <span m="383250">right?</span> <span m="384650">It</span>
  <span m="384820">doesn''t</span> <span m="385140">say</span> <span m="385260">anything</span>
  <span m="385700">on</span> <span m="388090">if</span> <span m="388290">my</span>
  <span m="388722">[INAUDIBLE]</span> <span m="389154">is</span> <span m="389586">finite,</span>
  <span m="390520">how</span> <span m="391130">big</span> <span m="391840">the</span>
  <span m="391980">error</span> <span m="392330">is.</span> <span m="395650">It</span>
  <span m="395880">also</span> <span m="395970">doesn''t</span> <span m="396290">say</span>
  <span m="397230">how</span> <span m="397860">[INAUDIBLE]</span> <span m="398140">my</span>
  <span m="398640">solution is.</span></p><p><span m="402650">And</span> <span m="402980">it</span>
  <span m="403330">turns out</span> <span m="404090">we</span> <span m="404280">can</span>
  <span m="404480">get</span> <span m="404850">[INAUDIBLE]</span> <span m="406580">solutions</span>
  <span m="408260">for</span> <span m="408460">finite</span> <span m="408720">delta</span>
  <span m="408880">t</span> <span m="409740">even</span> <span m="410600">if</span>
  <span m="411140">a</span> <span m="411460">scheme</span> <span m="412420">is</span>
  <span m="412810">local order</span> <span m="413070">of</span> <span m="413300">accuracy</span>
  <span m="414234">and</span> <span m="415168">zero stable.</span> <span m="416569">I''m
  going to</span> <span m="417036">show you</span> <span m="417503">such an</span>
  <span m="417970">example.</span></p><p><span m="419070">The</span> <span m="419340">example
  is</span> <span m="420400">using</span> <span m="420720">a</span> <span m="421040">second</span>
  <span m="421360">order</span> <span m="422750">accurate</span> <span m="423290">scheme</span>
  <span m="425870">and</span> <span m="426260">also</span> <span m="426560">zero stable.</span>
  <span m="427360">Can</span> <span m="427630">you</span> <span m="427760">guys</span>
  <span m="428000">think</span> <span m="428230">of</span> <span m="428440">a</span>
  <span m="428840">zero stable</span> <span m="429630">scheme</span> <span m="429820">that</span>
  <span m="430540">is</span> <span m="430800">second</span> <span m="431180">order</span>
  <span m="431560">accurate?</span> <span m="436480">What</span> <span m="436760">scheme</span>
  <span m="437020">have</span> <span m="437270">you learned</span> <span m="438210">that</span>
  <span m="438680">is</span> <span m="439150">second</span> <span m="439620">[? order
  ?]</span> <span m="440090">[? accurate? ?]</span></p><p><span m="440410">AUDIENCE:
  Midpoint.</span></p><p><span m="441210">PROFESSOR: Midpoint.</span> <span m="441480">Exactly.</span>
  <span m="441730">Midpoint</span> <span m="442110">is</span> <span m="442540">locally</span>
  <span m="442960">accurate.</span> <span m="443520">It''s</span> <span m="443910">zero</span>
  <span m="443970">stable.</span> <span m="445060">And</span> <span m="445380">in</span>
  <span m="445500">something</span> <span m="445900">we</span> <span m="446050">implemented</span>
  <span m="446850">last</span> <span m="447370">lecture,</span> <span m="448030">right?</span>
  <span m="449480">So</span> <span m="449600">let</span> <span m="449750">me</span>
  <span m="449860">go</span> <span m="450160">back</span> <span m="450470">to</span>
  <span m="450560">my</span> <span m="450760">Dropbox.</span> <span m="453760">[INAUDIBLE].</span>
  <span m="462260">Wait,</span> <span m="462740">where</span> <span m="463010">is</span>
  <span m="463130">my</span> <span m="463320">shared</span> <span m="463790">folder?</span>
  <span m="469706">[INAUDIBLE]</span> <span m="470200">up</span> <span m="470430">there,</span>
  <span m="470890">but,</span> <span m="471140">like--</span> <span m="476400">OK,</span>
  <span m="476730">it''s</span> <span m="476860">over</span> <span m="477050">here.</span>
  <span m="481240">OK.</span></p><p><span m="482595">I would</span> <span m="483330">ask</span>
  <span m="483600">you,</span> <span m="484000">who</span> <span m="484320">has</span>
  <span m="485620">completed</span> <span m="486780">these</span> <span m="487160">implementation</span>
  <span m="489040">we</span> <span m="489305">started</span> <span m="489680">last</span>
  <span m="490690">class?</span> <span m="492290">Of</span> <span m="492430">course</span>
  <span m="492705">[INAUDIBLE]</span> <span m="493400">here</span> <span m="493650">I
  have</span> <span m="494055">finished.</span> <span m="494820">Who else</span> <span
  m="495190">did it?</span> <span m="496573">Can</span> <span m="496803">you</span>
  <span m="497495">raise your--</span></p><p><span m="498417">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="499800">PROFESSOR: No,</span> <span m="500030">not</span> <span m="500230">including</span>
  <span m="500620">[INAUDIBLE].</span> <span m="502760">Great,</span> <span m="503150">great.</span>
  <span m="503480">So</span> <span m="503720">we</span> <span m="504050">have</span>
  <span m="504360">a</span> <span m="504570">bunch</span> <span m="504770">of</span>
  <span m="505210">people</span> <span m="505635">who</span> <span m="506060">did</span>
  <span m="506485">this.</span> <span m="507760">Anybody</span> <span m="507990">willing</span>
  <span m="508560">to</span> <span m="509040">try</span> <span m="509210">their</span>
  <span m="509470">code</span> <span m="512990">here?</span> <span m="514490">No?</span></p><p><span
  m="518420">AUDIENCE: [INAUDIBLE]</span></p><p><span m="521190">PROFESSOR: [INAUDIBLE]</span></p><p><span
  m="521990">AUDIENCE: The first two.</span></p><p><span m="523409">PROFESSOR: The
  first two..</span> <span m="524458">All right.</span> <span m="526250">So</span>
  <span m="526480">I''m</span> <span m="526650">going</span> <span m="526850">to</span>
  <span m="527090">copy</span> <span m="529000">your</span> <span m="529340">code</span>
  <span m="529810">into</span> <span m="530290">today''s</span> <span m="530710">folder.</span>
  <span m="532790">And</span> <span m="533010">which</span> <span m="533170">one</span>
  <span m="533330">should</span> <span m="533460">I</span> <span m="533550">run?</span></p><p><span
  m="534720">AUDIENCE: [INAUDIBLE]</span></p><p><span m="536001">PROFESSOR: [INAUDIBLE],</span>
  <span m="536430">OK.</span> <span m="537990">Thank</span> <span m="538190">you.</span>
  <span m="548330">Right.</span> <span m="549460">So</span> <span m="549830">I</span>
  <span m="549900">see</span> <span m="550160">you</span> <span m="550500">did</span>
  <span m="551180">[INAUDIBLE]</span> <span m="555394">and midpoint.</span> <span
  m="557610">OK,</span> <span m="557930">you</span> <span m="558050">are</span> <span
  m="558150">also</span> <span m="558440">doing</span> <span m="558690">this.</span>
  <span m="558880">So</span> <span m="559090">I''m</span> <span m="559270">just</span>
  <span m="559470">going</span> <span m="559610">to</span> <span m="559720">use--</span>
  <span m="561900">I</span> <span m="562040">see</span> <span m="562250">you</span>
  <span m="562450">did</span> <span m="562785">this</span> <span m="563515">double</span>
  <span m="564300">percentage</span> <span m="565610">thing.</span> <span m="565930">Does</span>
  <span m="566280">everybody</span> <span m="567120">know</span> <span m="567460">how</span>
  <span m="567630">to use</span> <span m="567800">that?</span></p><p><span m="568800">Yeah,
  so</span> <span m="569080">basically,</span> <span m="569470">[INAUDIBLE]</span>
  <span m="569830">according</span> <span m="570230">to</span> <span m="570330">sections.</span>
  <span m="571300">So</span> <span m="571740">I</span> <span m="571820">think</span>
  <span m="572000">it''s</span> <span m="572110">Control-Enter,</span> <span m="572586">right?</span>
  <span m="574014">To</span> <span m="574490">just</span> <span m="574740">around</span>
  <span m="574820">these</span> <span m="575470">sections?</span> <span m="576820">I</span>
  <span m="576920">think</span> <span m="577130">it''s</span> <span m="577270">already</span>
  <span m="577540">done.</span> <span m="578480">And</span> <span m="578690">I</span>
  <span m="578800">can</span> <span m="579040">run</span> <span m="580006">midpoint.</span>
  <span m="582910">[INAUDIBLE].</span> <span m="585660">That''s</span> <span m="585840">nice.</span></p><p><span
  m="588500">What</span> <span m="588710">if</span> <span m="588950">I</span> <span
  m="589550">change</span> <span m="589970">the</span> <span m="590230">delta</span>
  <span m="590440">t</span> <span m="590770">to</span> <span m="590940">0.5?</span>
  <span m="594400">OK,</span> <span m="594740">what</span> <span m="595040">if</span>
  <span m="595330">I</span> <span m="595756">change</span> <span m="596182">delta
  t</span> <span m="596610">to</span> <span m="596780">0.5, and I''m</span> <span
  m="596930">going</span> <span m="597080">to</span> <span m="597460">close</span>
  <span m="597820">all</span> <span m="598640">in</span> <span m="598760">the</span>
  <span m="598830">beginning</span> <span m="599150">of</span> <span m="599250">this</span>
  <span m="599380">so</span> <span m="599560">that,</span> <span m="599790">like,</span>
  <span m="600520">I''m going to  close</span> <span m="600990">my</span> <span m="601110">[INAUDIBLE].</span>
  <span m="603240">I''m going</span> <span m="603440">to run</span> <span m="603650">it</span>
  <span m="603750">again.</span> <span m="606480">I</span> <span m="606610">get</span>
  <span m="606880">this.</span></p><p><span m="616420">And</span> <span m="616690">this</span>
  <span m="617000">doesn''t</span> <span m="617270">actually</span> <span m="617640">defeat</span>
  <span m="618040">the</span> <span m="618160">purpose</span> <span m="618620">of</span>
  <span m="619450">the</span> <span m="620110">analysis</span> <span m="620640">of</span>
  <span m="620870">the</span> <span m="621020">scheme</span> <span m="621260">being</span>
  <span m="621520">globally</span> <span m="622010">accurate.</span> <span m="623330">The</span>
  <span m="623720">scheme</span> <span m="624130">is still</span> <span m="624370">globally</span>
  <span m="624850">accurate</span> <span m="625240">because,</span> <span m="626750">as</span>
  <span m="626990">I</span> <span m="627100">decrease</span> <span m="627530">my</span>
  <span m="627680">delta</span> <span m="627810">t,</span> <span m="628370">as</span>
  <span m="628630">I</span> <span m="628760">make</span> <span m="629080">delta</span>
  <span m="629250">t</span> <span m="629600">equal to</span> <span m="629700">0.3,</span>
  <span m="630940">for</span> <span m="631080">example,</span> <span m="632510">the</span>
  <span m="632620">oscillation</span> <span m="633120">gets</span> <span m="633310">smaller.</span>
  <span m="634280">My</span> <span m="634450">solution</span> <span m="634840">gets</span>
  <span m="635020">better.</span></p><p><span m="635770">If</span> <span m="635920">I</span>
  <span m="636030">decrease</span> <span m="636400">to</span> <span m="636530">0.2,</span>
  <span m="637630">the</span> <span m="637760">solution</span> <span m="638240">gets</span>
  <span m="638460">still</span> <span m="638958">better.</span> <span m="639954">[INAUDIBLE]</span>
  <span m="641448">it gets</span> <span m="641950">better</span> <span m="642170">and</span>
  <span m="642270">better.</span> <span m="643150">And</span> <span m="643280">when</span>
  <span m="643460">I</span> <span m="643620">decrease</span> <span m="644070">it</span>
  <span m="644200">to</span> <span m="644320">0.1,</span> <span m="646200">it''s</span>
  <span m="647170">almost</span> <span m="647590">invisible.</span> <span m="649390">But</span>
  <span m="649580">I''m going to</span> <span m="649760">assure</span> <span m="650070">you.</span></p><p><span
  m="650380">If</span> <span m="651320">I let</span> <span m="651610">these</span>
  <span m="652103">things</span> <span m="652596">drop</span> <span m="653090">further,
  the oscillation</span> <span m="653460">is</span> <span m="653780">going</span>
  <span m="653920">to</span> <span m="654050">show</span> <span m="654170">up.</span>
  <span m="655080">You want to</span> <span m="655772">try?</span> <span m="656756">To</span>
  <span m="657250">try,</span> <span m="657530">OK?</span> <span m="659060">p is</span>
  <span m="659560">equal</span> <span m="659810">to</span> <span m="659870">100,</span>
  <span m="660358">let''s see.</span> <span m="662800">If</span> <span m="663070">p</span>
  <span m="663496">is equal to</span> <span m="663922">100,</span> <span m="665200">oh,
  you</span> <span m="665400">did</span> <span m="665600">the</span> <span m="665710">[INAUDIBLE]</span>
  <span m="666240">thing.</span> <span m="666650">I''m</span> <span m="666790">going</span>
  <span m="666970">to</span> <span m="667250">remove</span> <span m="667640">the</span>
  <span m="667730">[INAUDIBLE]</span> <span m="668120">him</span> <span m="668260">and</span>
  <span m="668460">do</span> <span m="669400">axis equal.</span> <span m="674640">That''s</span>
  <span m="675110">too</span> <span m="675270">much.</span></p><p><span m="676770">[LAUGHTER]</span></p><p><span
  m="680757">p is equal to</span> <span m="681244">50.</span> <span m="683679">What?</span>
  <span m="684170">OK.</span> <span m="689090">Did I change</span> <span m="689580">anything?</span>
  <span m="703860">Why</span> <span m="704110">do</span> <span m="704260">I</span>
  <span m="704360">get</span> <span m="704620">this?</span> <span m="706620">Do I
  need to do</span> <span m="707120">this</span> <span m="707620">again?</span> <span
  m="708120">Or not?</span> <span m="711530">Why</span> <span m="711770">do</span>
  <span m="711920">I</span> <span m="712010">get</span> <span m="712270">a--</span></p><p><span
  m="713252">AUDIENCE: [INAUDIBLE]</span></p><p>&nbsp;</p><p><span m="720620">PROFESSOR:
  Variables.</span> <span m="724530">The</span> <span m="724600">first</span> <span
  m="724940">one,</span> <span m="725110">OK?</span> <span m="726340">I</span> <span
  m="726660">ran it,</span> <span m="726930">and then</span> <span m="727290">we''re
  on</span> <span m="727390">the</span> <span m="727530">next</span> <span m="727986">point.</span>
  <span m="728900">Oh,</span> <span m="729130">there</span> <span m="729410">it is.</span>
  <span m="730570">So</span> <span m="730620">let</span> <span m="730770">me</span>
  <span m="731460">go</span> <span m="731610">back</span> <span m="731980">to</span>
  <span m="732100">my</span> <span m="732270">p equal</span> <span m="732535">to</span>
  <span m="732800">50.</span> <span m="734660">You</span> <span m="734830">see</span>
  <span m="735010">what</span> <span m="735280">I</span> <span m="735360">get</span>
  <span m="736690">over</span> <span m="736980">here?</span> <span m="739600">I</span>
  <span m="739720">don''t</span> <span m="740000">get</span> <span m="740170">a</span>
  <span m="740230">solution</span> <span m="740650">that</span> <span m="740800">is</span>
  <span m="741060">smooth.</span> <span m="741410">I get</span> <span m="741760">a</span>
  <span m="741930">solution</span> <span m="742910">that--</span> <span m="745960">[INAUDIBLE].</span></p><p><span
  m="756505">So</span> <span m="756980">what</span> <span m="757160">happens--</span>
  <span m="759660">still, it</span> <span m="760170">doesn''t</span> <span m="760470">defeat</span>
  <span m="760730">the</span> <span m="760830">purpose</span> <span m="761220">of</span>
  <span m="761360">being</span> <span m="761740">globally</span> <span m="762240">accurate.</span>
  <span m="762670">If I</span> <span m="763010">make</span> <span m="763870">delta</span>
  <span m="764330">t equal</span> <span m="764710">to 0.05,</span> <span m="765710">this</span>
  <span m="766030">oscillation</span> <span m="766590">becomes</span> <span m="767260">smaller.</span>
  <span m="768220">We</span> <span m="768310">can</span> <span m="768420">still</span>
  <span m="768870">see</span> <span m="769140">it,</span> <span m="770020">but</span>
  <span m="770250">it</span> <span m="770660">becomes</span> <span m="771060">smaller.</span>
  <span m="772650">But</span> <span m="773620">when</span> <span m="774000">I</span>
  <span m="774100">increase</span> <span m="774700">t</span> <span m="775310">to</span>
  <span m="775490">be</span> <span m="775670">100</span> <span m="776140">again,</span>
  <span m="778540">this</span> <span m="778750">is</span> <span m="778890">going</span>
  <span m="779040">to</span> <span m="779140">show</span> <span m="779390">up</span>
  <span m="779540">again.</span> <span m="780376">I mean,</span> <span m="781630">I</span>
  <span m="782050">see</span> <span m="782310">something</span> <span m="782680">is</span>
  <span m="782830">wrong.</span> <span m="786910">OK.</span> <span m="787250">So</span>
  <span m="787470">I''ll</span> <span m="788630">do</span> <span m="788770">that</span>
  <span m="788950">later.</span></p><p><span m="789540">But</span> <span m="789680">the</span>
  <span m="789760">point</span> <span m="790110">is</span> <span m="790600">clear,</span>
  <span m="790980">right,</span> <span m="791860">although</span> <span m="792310">the</span>
  <span m="792390">skin</span> <span m="792900">is</span> <span m="794100">zero</span>
  <span m="794410">stable,</span> <span m="795250">it</span> <span m="795380">is</span>
  <span m="795550">second</span> <span m="795910">order</span> <span m="796050">accurate,</span>
  <span m="796830">the</span> <span m="797090">midpoint</span> <span m="797330">scheme.</span>
  <span m="799505">But it</span> <span m="799940">doesn''t</span> <span m="800390">really</span>
  <span m="800690">give</span> <span m="801020">the</span> <span m="801200">desired</span>
  <span m="802180">behavior.</span> <span m="804746">It''s</span> <span m="805230">even</span>
  <span m="805630">worse</span> <span m="805910">than</span> <span m="806090">the</span>
  <span m="806180">forward Euler</span> <span m="806890">which</span> <span m="807100">is</span>
  <span m="807210">only</span> <span m="807460">first</span> <span m="807710">order</span>
  <span m="807880">accurate.</span></p><p><span m="809340">If</span> <span m="809540">you</span>
  <span m="809790">look</span> <span m="810040">at</span> <span m="810150">the</span>
  <span m="810210">forward Euler,</span> <span m="810930">with</span> <span m="811910">a</span>
  <span m="812500">delta t</span> <span m="812770">of</span> <span m="813185">0.5,</span>
  <span m="813600">which shows</span> <span m="814240">horrible</span> <span m="814710">behavior</span>
  <span m="814985">for</span> <span m="815260">midpoints,</span> <span m="816030">right?</span>
  <span m="819725">I get an error somewhere.</span> <span m="821150">Oh,</span> <span
  m="822575">I need</span> <span m="823050">to</span> <span m="823650">run</span>
  <span m="824160">this</span> <span m="824430">first,</span> <span m="824924">and</span>
  <span m="825418">run this.</span> <span m="826900">So</span> <span m="827360">yeah,</span>
  <span m="827590">forward Euler</span> <span m="828220">works</span> <span m="828490">fine</span>
  <span m="828980">with</span> <span m="829180">a</span> <span m="829620">delta</span>
  <span m="830085">t</span> <span m="830550">equal to</span> <span m="831015">0.5.</span>
  <span m="833340">So</span> <span m="833470">in</span> <span m="833610">this</span>
  <span m="833800">case,</span> <span m="836290">forward Euler</span> <span m="836830">actually</span>
  <span m="837130">works</span> <span m="837390">better</span> <span m="837670">than</span>
  <span m="837830">midpoint,</span> <span m="838560">even</span> <span m="838860">though</span>
  <span m="839010">midpoint</span> <span m="839490">is</span> <span m="839640">a</span>
  <span m="841550">second</span> <span m="841910">order</span> <span m="842580">accurate</span>
  <span m="842900">scheme.</span></p><p><span m="846240">So</span> <span m="846400">why</span>
  <span m="846880">is</span> <span m="847250">this</span> <span m="847560">the</span>
  <span m="847640">case?</span> <span m="848360">Both</span> <span m="848680">schemes</span>
  <span m="849520">are</span> <span m="849930">zero</span> <span m="850150">stable.</span>
  <span m="852642">Midpoint</span> <span m="853360">is</span> <span m="853810">more</span>
  <span m="854150">accurate,</span> <span m="854760">supposedly</span> <span m="855340">more</span>
  <span m="855580">accurate</span> <span m="855855">than</span> <span m="856130">forward
  Euler.</span> <span m="857890">But</span> <span m="858100">applied</span> <span
  m="858490">to</span> <span m="858670">this</span> <span m="859160">specific</span>
  <span m="859435">equation,</span> <span m="861120">unlike</span> <span m="861380">the</span>
  <span m="861640">equation</span> <span m="861990">we</span> <span m="862250">saw</span>
  <span m="862700">last</span> <span m="863010">week,</span> <span m="863720">the</span>
  <span m="863810">pendulum</span> <span m="864320">equation--</span> <span m="865780">on</span>
  <span m="865920">the</span> <span m="866050">pendulum</span> <span m="866450">equation,</span>
  <span m="866770">midpoint</span> <span m="866950">actually</span> <span m="867285">works</span>
  <span m="867620">much, much</span> <span m="867880">better</span> <span m="868872">than</span>
  <span m="869370">forward Euler</span> <span m="869750">for</span> <span m="870080">a</span>
  <span m="870500">large</span> <span m="870920">[INAUDIBLE].</span></p><p><span m="871340">Here,</span>
  <span m="871750">a</span> <span m="871990">forward Euler</span> <span m="872325">works</span>
  <span m="872660">better</span> <span m="872980">than</span> <span m="873250">midpoint</span>
  <span m="873707">or</span> <span m="874164">[INAUDIBLE].</span> <span m="876450">The</span>
  <span m="876590">reason</span> <span m="877230">is</span> <span m="878160">linked</span>
  <span m="878640">with</span> <span m="879140">eigenvalue</span> <span m="879550">stability.</span>
  <span m="883740">It</span> <span m="883940">turns</span> <span m="884230">out</span>
  <span m="884610">that</span> <span m="885810">the</span> <span m="885960">particular</span>
  <span m="886470">case,</span> <span m="887070">we</span> <span m="887120">are</span>
  <span m="887220">looking</span> <span m="887580">at,</span> <span m="890380">for</span>
  <span m="890580">which</span> <span m="891170">forward Euler</span> <span m="891850">is</span>
  <span m="892020">actually</span> <span m="892420">eigenvalue</span> <span m="892745">stable,</span>
  <span m="893880">and</span> <span m="894180">the</span> <span m="894250">midpoint</span>
  <span m="894810">is</span> <span m="895030">not</span> <span m="895790">eigenvalue</span>
  <span m="896150">stable.</span></p><p><span m="896950">So</span> <span m="897150">eigenvalue</span>
  <span m="897475">stability</span> <span m="898380">is</span> <span m="898560">a</span>
  <span m="898650">requirement</span> <span m="899780">that</span> <span m="900150">is</span>
  <span m="900750">more</span> <span m="901580">strict,</span> <span m="902070">more</span>
  <span m="902410">stringent,</span> <span m="903270">than</span> <span m="903580">0</span>
  <span m="903970">stability.</span> <span m="904500">Although</span> <span m="904830">midpoint</span>
  <span m="905460">is</span> <span m="905700">zero stable ,</span> <span m="906600">it</span>
  <span m="906760">is</span> <span m="906980">not</span> <span m="907430">eigenvalue</span>
  <span m="907890">stable</span> <span m="908390">for</span> <span m="908660">that</span>
  <span m="909050">particular</span> <span m="909520">equation.</span> <span m="912250">OK,</span>
  <span m="912500">any</span> <span m="912740">questions</span> <span m="913730">before
  we</span> <span m="914225">move on?</span></p><p><span m="916700">AUDIENCE: [INAUDIBLE]</span></p><p>&nbsp;</p><p><span
  m="924130">PROFESSOR: Exactly.</span> <span m="924670">Good</span> <span m="924890">question.</span>
  <span m="925730">So</span> <span m="926550">zero stability</span> <span m="929250">is</span>
  <span m="929890">per</span> <span m="930230">scheme.</span> <span m="930940">A</span>
  <span m="931340">scheme</span> <span m="932030">is</span> <span m="932270">either</span>
  <span m="932690">zero</span> <span m="932960">stable</span> <span m="933370">or</span>
  <span m="933630">not.</span> <span m="935390">It''s</span> <span m="935710">independent</span>
  <span m="936290">of</span> <span m="936400">the</span> <span m="936470">differential
  equation,</span> <span m="937070">because</span> <span m="937360">it</span> <span
  m="937450">just</span> <span m="938270">tells</span> <span m="938530">you, can</span>
  <span m="938610">scheme</span> <span m="938930">solve</span> <span m="939510">this</span>
  <span m="939890">previous</span> <span m="940220">differential equation</span> <span
  m="940890">or</span> <span m="940970">not.</span></p><p><span m="941730">Eigenvalue</span>
  <span m="942330">stability,</span> <span m="942940">on</span> <span m="943060">the</span>
  <span m="943160">other</span> <span m="943370">hand,</span> <span m="943870">depends</span>
  <span m="944160">not only</span> <span m="944520">on</span> <span m="944600">the</span>
  <span m="944680">scheme,</span> <span m="945220">but</span> <span m="945460">also</span>
  <span m="945780">on</span> <span m="945920">the</span> <span m="946060">equation.</span>
  <span m="947530">In</span> <span m="947710">the</span> <span m="947810">simplest</span>
  <span m="948290">case,</span> <span m="948690">eigenvalue</span> <span m="949240">stability</span>
  <span m="949860">looks</span> <span m="950240">at,</span> <span m="950750">are</span>
  <span m="950980">you</span> <span m="951300">able</span> <span m="951700">to</span>
  <span m="951840">solve</span> <span m="953590">this</span> <span m="953880">equation?</span>
  <span m="956700">So</span> <span m="957460">you</span> <span m="957630">can</span>
  <span m="957810">see</span> <span m="958260">zero stability</span> <span m="959170">is</span>
  <span m="960080">like</span> <span m="960230">a</span> <span m="960703">standard</span>
  <span m="961176">case</span> <span m="961649">of</span> <span m="962122">eigenvalue</span>
  <span m="962595">stability,</span> <span m="963541">where lambda</span> <span m="964020">is</span>
  <span m="964180">equal</span> <span m="964290">to</span> <span m="964930">zero.</span></p><p><span
  m="966470">So</span> <span m="967100">if</span> <span m="967530">a</span> <span
  m="967910">scheme</span> <span m="968670">is</span> <span m="969050">eigenvalue</span>
  <span m="969590">stable</span> <span m="970370">for</span> <span m="971150">lambda</span>
  <span m="971430">equal</span> <span m="971510">to</span> <span m="971990">zero,</span>
  <span m="972470">then it is</span> <span m="972990">zero</span> <span m="973180">stable.</span>
  <span m="974160">But</span> <span m="974650">a</span> <span m="975140">scheme</span>
  <span m="975630">being</span> <span m="976120">zero stable</span> <span m="976400">doesn''t</span>
  <span m="976740">mean it is</span> <span m="977040">always</span> <span m="977540">eigenvalue</span>
  <span m="978198">stable</span> <span m="979074">for</span> <span m="979512">all  differential
  equations</span> <span m="979950">like</span> <span m="980150">that.</span> <span
  m="982170">OK,</span> <span m="982810">so</span> <span m="982960">let''s</span>
  <span m="983840">start</span> <span m="984590">discussing</span> <span m="985030">eigenvalue</span>
  <span m="985880">stability.</span> <span m="986370">And</span> <span m="986640">at</span>
  <span m="986790">the</span> <span m="986880">end</span> <span m="987060">of</span>
  <span m="987160">the</span> <span m="987230">lecture,</span> <span m="987590">I''m</span>
  <span m="987820">also</span> <span m="988090">going</span> <span m="988210">to</span>
  <span m="988300">start</span> <span m="988610">talking</span> <span m="988850">about</span>
  <span m="990080">implicit</span> <span m="990740">schemes</span> <span m="991990">and</span>
  <span m="992220">the</span> <span m="992290">Newton Raphson iteration.</span> <span
  m="993770">All</span> <span m="993960">right.</span></p><p><span m="995130">So</span>
  <span m="995340">eigenvalue</span> <span m="995685">stability</span> <span m="996330">analysis,</span>
  <span m="997000">the</span> <span m="997100">first</span> <span m="997300">thing</span>
  <span m="997460">I</span> <span m="997520">want</span> <span m="997710">to</span>
  <span m="997800">show</span> <span m="998080">you</span> <span m="998280">is</span>
  <span m="998740">this</span> <span m="999370">link.</span> <span m="1000260">If</span>
  <span m="1000440">you</span> <span m="1000550">go</span> <span m="1000790">to</span>
  <span m="1000930">this</span> <span m="1001190">link,</span> <span m="1001830">which</span>
  <span m="1002010">I</span> <span m="1002200">already</span> <span m="1002670">opened,</span>
  <span m="1003110">I</span> <span m="1003220">think,</span> <span m="1004890">you''re</span>
  <span m="1005100">going</span> <span m="1005240">to</span> <span m="1005390">get</span>
  <span m="1006190">to</span> <span m="1006300">the</span> <span m="1006390">website</span>
  <span m="1006920">called</span> <span m="1007250">mathlets.org.</span> <span m="1009400">And</span>
  <span m="1009930">it hosts</span> <span m="1010970">a</span> <span m="1011090">bunch</span>
  <span m="1011380">of</span> <span m="1011930">what</span> <span m="1012240">they</span>
  <span m="1012580">call</span> <span m="1012780">Mathlets.</span> <span m="1013050">They</span>
  <span m="1013180">are</span> <span m="1013250">basically</span> <span m="1013660">Java</span>
  <span m="1014130">applets</span> <span m="1014510">that</span> <span m="1014890">allows</span>
  <span m="1015490">you</span> <span m="1015610">to</span> <span m="1016520">visualize</span>
  <span m="1017220">these</span> <span m="1018030">various</span> <span m="1018450">things.</span></p><p><span
  m="1019360">And</span> <span m="1019620">if</span> <span m="1019730">you</span>
  <span m="1019820">click</span> <span m="1020250">on</span> <span m="1020390">it,</span>
  <span m="1020730">it</span> <span m="1020840">is</span> <span m="1021020">going</span>
  <span m="1021140">to</span> <span m="1021200">open</span> <span m="1021520">a</span>
  <span m="1021600">window.</span> <span m="1022670">You</span> <span m="1022830">need</span>
  <span m="1022980">a</span> <span m="1023070">statue</span> <span m="1023600">like</span>
  <span m="1023630">Java</span> <span m="1024730">security</span> <span m="1025349">or</span>
  <span m="1025520">something</span> <span m="1025800">like</span> <span m="1026060">add</span>
  <span m="1026270">exception</span> <span m="1026819">to</span> <span m="1026950">mathlets.org.</span>
  <span m="1029369">Otherwise,</span> <span m="1029910">your</span> <span m="1030180">browser</span>
  <span m="1030560">may</span> <span m="1030810">actually</span> <span m="1031180">block</span>
  <span m="1032010">the</span> <span m="1032160">thing.</span> <span m="1033089">But</span>
  <span m="1033300">once</span> <span m="1033609">you</span> <span m="1034030">have</span>
  <span m="1034310">it--</span> <span m="1034609">let</span> <span m="1034810">me</span>
  <span m="1034900">make</span> <span m="1035160">it</span> <span m="1035290">full
  screen.</span> <span m="1039750">OK.</span> <span m="1041660">Right.</span></p><p><span
  m="1043060">So</span> <span m="1043290">what</span> <span m="1043579">it</span>
  <span m="1043720">shows</span> <span m="1044170">you</span> <span m="1045790">is</span>
  <span m="1046640">for</span> <span m="1046990">what</span> <span m="1047349">lambda--</span>
  <span m="1048420">remember,</span> <span m="1049520">we</span> <span m="1049710">are</span>
  <span m="1049790">talking</span> <span m="1050070">about</span> <span m="1050220">eigenvalue</span>
  <span m="1050380">stability--</span> <span m="1054830">is a</span> <span m="1055293">scheme</span>
  <span m="1056530">stable</span> <span m="1057240">or</span> <span m="1057380">not</span>
  <span m="1057805">for this</span> <span m="1058230">equation.</span> <span m="1059080">So</span>
  <span m="1059240">we</span> <span m="1059380">have</span> <span m="1059560">a</span>
  <span m="1059630">lambda</span> <span m="1059920">here.</span> <span m="1061760">In</span>
  <span m="1061930">the</span> <span m="1062040">mathlet,</span> <span m="1062405">a</span>
  <span m="1062770">lambda</span> <span m="1063230">can</span> <span m="1063530">only</span>
  <span m="1063920">be</span> <span m="1064230">real</span> <span m="1064590">values,</span>
  <span m="1065950">but</span> <span m="1066050">complex</span> <span m="1066485">values.</span></p><p><span
  m="1067790">So</span> <span m="1068790">this is</span> <span m="1069360">the</span>
  <span m="1069470">space</span> <span m="1069970">of</span> <span m="1070140">our</span>
  <span m="1071040">lambda</span> <span m="1071390">times</span> <span m="1072050">delta</span>
  <span m="1072360">t.</span> <span m="1076500">We</span> <span m="1076960">can</span>
  <span m="1077420">think</span> <span m="1077890">of a</span> <span m="1078100">point</span>
  <span m="1078490">here</span> <span m="1079430">is</span> <span m="1079730">1, 0.</span>
  <span m="1080500">That</span> <span m="1081344">means</span> <span m="1082188">lambda</span>
  <span m="1082610">times</span> <span m="1083317">delta</span> <span m="1083724">t</span>
  <span m="1084131">equals  to 1.</span> <span m="1084540">So,</span> <span m="1084770">for</span>
  <span m="1084880">example,</span> <span m="1085430">at</span> <span m="1086420">this</span>
  <span m="1086630">point,</span> <span m="1087140">this</span> <span m="1087390">lambda</span>
  <span m="1087730">is equal to</span> <span m="1088184">10.</span> <span m="1089092">Delta</span>
  <span m="1089546">t</span> <span m="1090000">is equal</span> <span m="1090300">to</span>
  <span m="1090721">0.1.</span> <span m="1091563">Then</span> <span m="1091984">you''re
  at this</span> <span m="1092405">point.</span> <span m="1092830">If</span> <span
  m="1093010">lambda</span> <span m="1093345">is</span> <span m="1093680">equal</span>
  <span m="1094000">to</span> <span m="1094750">minus</span> <span m="1095231">1,</span>
  <span m="1096193">[INAUDIBLE].</span></p><p><span m="1100530">The</span> <span m="1100720">blue</span>
  <span m="1101132">regions</span> <span m="1101544">here</span> <span m="1102370">shows
  you</span> <span m="1103120">that</span> <span m="1104090">for</span> <span m="1105060">what</span>
  <span m="1105490">values</span> <span m="1105970">of</span> <span m="1106090">lambda,</span>
  <span m="1106930">for</span> <span m="1107080">what</span> <span m="1108040">combinations</span>
  <span m="1108180">of</span> <span m="1108678">lambda</span> <span m="1109176">and</span>
  <span m="1109674">delta</span> <span m="1110172">t--</span> <span m="1110670">actually,
  it</span> <span m="1111170">only</span> <span m="1111590">includes</span> <span
  m="1112490">the</span> <span m="1112940">lambda.</span> <span m="1113390">What</span>
  <span m="1113750">lambda</span> <span m="1114010">times</span> <span m="1114750">delta</span>
  <span m="1115120">t</span> <span m="1115610">is,</span> <span m="1116040">for a</span>
  <span m="1116420">particular</span> <span m="1116888">scheme,</span> <span m="1117824">eigenvalue</span>
  <span m="1118760">stable. So</span> <span m="1119230">here</span> <span m="1119750">is</span>
  <span m="1119990">the</span> <span m="1120070">forward Euler.</span></p><p><span
  m="1121940">For</span> <span m="1122310">forward Euler,</span> <span m="1124650">the</span>
  <span m="1124790">scheme</span> <span m="1125060">is</span> <span m="1125250">stable</span>
  <span m="1125740">only</span> <span m="1126220">if</span> <span m="1126640">lambda</span>
  <span m="1127060">[INAUDIBLE]</span> <span m="1127480">times delta</span> <span
  m="1127900">t</span> <span m="1128130">was</span> <span m="1128617">using</span>
  <span m="1129591">this</span> <span m="1130300">very</span> <span m="1130430">small</span>
  <span m="1130862">circle.</span> <span m="1132158">OK,</span> <span m="1132590">what</span>
  <span m="1132840">does</span> <span m="1133190">this</span> <span m="1133380">mean?</span>
  <span m="1135860">This</span> <span m="1136150">means</span> <span m="1136828">that</span>
  <span m="1138740">if</span> <span m="1139050">you</span> <span m="1139360">have</span>
  <span m="1140210">a</span> <span m="1140330">lambda</span> <span m="1140950">greater</span>
  <span m="1141340">than</span> <span m="1141550">zero,</span> <span m="1142456">would</span>
  <span m="1142909">forward Euler</span> <span m="1144270">ever</span> <span m="1144610">be</span>
  <span m="1144810">stable?</span></p><p><span m="1146680">No.</span> <span m="1149200">Actually,</span>
  <span m="1151350">I</span> <span m="1151480">would</span> <span m="1151630">expect,</span>
  <span m="1152090">if</span> <span m="1152330">lambda</span> <span m="1152700">is</span>
  <span m="1152910">greater</span> <span m="1153380">than</span> <span m="1153450">zero,</span>
  <span m="1154060">even</span> <span m="1154410">the</span> <span m="1154600">analytic</span>
  <span m="1155340">solution</span> <span m="1155840">of</span> <span m="1155970">the</span>
  <span m="1156398">PDE</span> <span m="1157254">is</span> <span m="1157682">unstable.</span>
  <span m="1158540">Why?</span> <span m="1159830">What is</span> <span m="1160020">is</span>
  <span m="1160180">the</span> <span m="1160310">analytic</span> <span m="1160665">solution</span>
  <span m="1161020">for</span> <span m="1161120">TDE?</span></p><p><span m="1162010">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="1163790">PROFESSOR:</span> <span m="1163870">e</span>
  <span m="1163950">to</span> <span m="1164030">the</span> <span m="1164250">lambda</span>
  <span m="1164700">t,</span> <span m="1165020">right?</span> <span m="1166160">Each
  of the</span> <span m="1166320">lambda t</span> <span m="1166760">is</span> <span
  m="1167190">the</span> <span m="1167370">analytic</span> <span m="1167766">solution</span>
  <span m="1168162">of</span> <span m="1168560">[INAUDIBLE]</span> <span m="1169840">unstable
  by</span> <span m="1169990">itself.</span> <span m="1171210">So</span> <span m="1172490">actually,</span>
  <span m="1172970">not</span> <span m="1173320">the</span> <span m="1173460">only</span>
  <span m="1173860">real</span> <span m="1174290">one, but</span> <span m="1174910">also</span>
  <span m="1175490">the</span> <span m="1175940">whole</span> <span m="1176520">[INAUDIBLE]</span>
  <span m="1177460">the</span> <span m="1177950">analytical</span> <span m="1178590">OD</span>
  <span m="1179970">is</span> <span m="1180180">unstable.</span></p><p><span m="1183550">Because</span>
  <span m="1183940">if</span> <span m="1184130">the</span> <span m="1184520">lambda</span>
  <span m="1184715">is</span> <span m="1184910">here,</span> <span m="1186598">then</span>
  <span m="1187020">the</span> <span m="1187315">lambda</span> <span m="1187610">is</span>
  <span m="1188494">1 plus</span> <span m="1188918">i,</span> <span m="1190190">how</span>
  <span m="1190510">does</span> <span m="1190795">the</span> <span m="1191080">solution</span>
  <span m="1191460">look</span> <span m="1191930">like?</span> <span m="1195220">It''s
  an</span> <span m="1195590">oscillatory</span> <span m="1196710">growing</span>
  <span m="1197180">solution,</span> <span m="1197680">right?</span> <span m="1198490">The</span>
  <span m="1198610">imaginary</span> <span m="1199065">part</span> <span m="1200070">determines</span>
  <span m="1200980">the</span> <span m="1201070">frequency</span> <span m="1201550">of</span>
  <span m="1201700">the</span> <span m="1201770">oscillation.</span> <span m="1202310">But</span>
  <span m="1202726">real</span> <span m="1203142">part</span> <span m="1203990">determines</span>
  <span m="1204150">the rate of</span> <span m="1204440">growth.</span> <span m="1205570">As
  long as</span> <span m="1205865">the</span> <span m="1206160">real</span> <span
  m="1206320">part</span> <span m="1206655">is</span> <span m="1206990">greater</span>
  <span m="1207275">than</span> <span m="1207560">zero,</span> <span m="1208250">it''s</span>
  <span m="1208470">a</span> <span m="1208680">growing</span> <span m="1209035">oscillatory</span>
  <span m="1210080">solution.</span></p><p><span m="1213210">So</span> <span m="1213580">that</span>
  <span m="1213723">means,</span> <span m="1213866">for</span> <span m="1214010">the</span>
  <span m="1214230">whole</span> <span m="1215890">[INAUDIBLE]</span> <span m="1217160">of</span>
  <span m="1217600">the</span> <span m="1218040">complex</span> <span m="1218480">[INAUDIBLE],</span>
  <span m="1219155">the</span> <span m="1219480">analytical</span> <span m="1219930">solution</span>
  <span m="1220020">[INAUDIBLE]</span> <span m="1220300">is</span> <span m="1220580">unstable.</span>
  <span m="1222220">So</span> <span m="1222440">you</span> <span m="1222630">shouldn''t</span>
  <span m="1222950">really</span> <span m="1223240">expect</span> <span m="1224040">a
  numerical</span> <span m="1224390">solution</span> <span m="1224740">to</span> <span
  m="1225550">make</span> <span m="1225890">it</span> <span m="1226010">stable.</span>
  <span m="1227360">I   mean,</span> <span m="1227800">you''re going to</span> <span
  m="1227970">see</span> <span m="1228160">some,  the numerical scheme</span> <span
  m="1228310">actually</span> <span m="1228890">does</span> <span m="1229040">make</span>
  <span m="1229380">some of them</span> <span m="1229770">stable,</span> <span m="1230540">but</span>
  <span m="1231020">you shouldn''t</span> <span m="1231990">expect it.</span></p><p><span
  m="1234340">What is</span> <span m="1234640">more</span> <span m="1234850">intriguing</span>
  <span m="1235230">is</span> <span m="1235580">that,</span> <span m="1236550">even</span>
  <span m="1236970">on</span> <span m="1237170">the</span> <span m="1237410">[INAUDIBLE]</span>
  <span m="1239910">for</span> <span m="1240040">which</span> <span m="1240860">the</span>
  <span m="1240950">analytical</span> <span m="1241390">behavior</span> <span m="1241890">of</span>
  <span m="1242280">the</span> <span m="1242460">ODE</span> <span m="1243840">is</span>
  <span m="1244190">either</span> <span m="1245650">just</span> <span m="1245920">a</span>
  <span m="1245970">monotonic</span> <span m="1246565">detail</span> <span m="1246850">[INAUDIBLE]</span>
  <span m="1248820">on the</span> <span m="1249100">real</span> <span m="1249520">axis</span>
  <span m="1250440">into</span> <span m="1251560">something</span> <span m="1251815">negative</span>
  <span m="1252754">times</span> <span m="1253742">t.</span> <span m="1255720">So
  is</span> <span m="1255930">du dt</span> <span m="1256900">equal</span> <span m="1257970">to</span>
  <span m="1258400">negative</span> <span m="1258670">lambda</span> <span m="1259070">times</span>
  <span m="1259530">u.</span> <span m="1261830">The</span> <span m="1261960">solution</span>
  <span m="1262370">is</span> <span m="1262530">u</span> <span m="1263160">equal</span>
  <span m="1263660">to</span> <span m="1264020">u</span> <span m="1264350">to the</span>
  <span m="1264680">negative</span> <span m="1265151">[INAUDIBLE]</span> <span m="1265622">times</span>
  <span m="1266093">t.</span> <span m="1267035">So you get a monotonic case.</span></p><p><span
  m="1267980">If</span> <span m="1268200">you</span> <span m="1268330">are</span>
  <span m="1268420">over</span> <span m="1268820">here,</span> <span m="1269155">we''ll</span>
  <span m="1269490">have</span> <span m="1269690">a</span> <span m="1269770">negative</span>
  <span m="1270040">real</span> <span m="1270320">time,</span> <span m="1270712">and</span>
  <span m="1271104">a</span> <span m="1271496">non-zero</span> <span m="1271890">imaginary</span>
  <span m="1272120">[INAUDIBLE],</span> <span m="1272530">then</span> <span m="1272840">you</span>
  <span m="1272960">have</span> <span m="1273140">an</span> <span m="1274060">oscillating</span>
  <span m="1276110">and</span> <span m="1276230">decaying</span> <span m="1276647">solution.</span>
  <span m="1277900">So</span> <span m="1278070">you</span> <span m="1278250">would</span>
  <span m="1278360">also</span> <span m="1278950">expect</span> <span m="1279360">it</span>
  <span m="1279770">to</span> <span m="1280180">be</span> <span m="1280590">stable.</span>
  <span m="1280730">But</span> <span m="1280870">forward Euler,</span> <span m="1281430">actually,</span>
  <span m="1282390">is</span> <span m="1282870">only</span> <span m="1283160">stable</span>
  <span m="1283910">within</span> <span m="1284280">this</span> <span m="1284510">region</span>
  <span m="1284938">[INAUDIBLE]</span> <span m="1285794">lamba</span> <span m="1286222">delta</span>
  <span m="1286650">[INAUDIBLE]</span> <span m="1286990">over</span> <span m="1287350">here,</span>
  <span m="1287540">it''s</span> <span m="1287780">unstable.</span></p><p><span m="1294410">OK,</span>
  <span m="1295330">so</span> <span m="1295440">that</span> <span m="1296330">is</span>
  <span m="1296550">interesting.</span> <span m="1298190">I''m</span> <span m="1298360">just</span>
  <span m="1298520">going</span> <span m="1298640">to</span> <span m="1298840">do</span>
  <span m="1299020">a</span> <span m="1299100">very</span> <span m="1299410">brief</span>
  <span m="1299820">analysis</span> <span m="1300510">of</span> <span m="1300680">showing</span>
  <span m="1301110">why</span> <span m="1301430">that</span> <span m="1301620">is</span>
  <span m="1301770">the</span> <span m="1301850">case.</span> <span m="1303110">Forward
  Euler,</span> <span m="1303880">V</span> <span m="1304530">of</span> <span m="1304870">n</span>
  <span m="1305310">plus</span> <span m="1305790">1</span> <span m="1306100">minus</span>
  <span m="1306460">V</span> <span m="1306700">n</span> <span m="1307070">over</span>
  <span m="1307370">delta</span> <span m="1307720">t</span> <span m="1308720">applied</span>
  <span m="1310360">to</span> <span m="1310770">half</span> <span m="1310990">of</span>
  <span m="1311150">V</span> <span m="1311370">n,</span> <span m="1312310">which,</span>
  <span m="1312580">in</span> <span m="1312720">this</span> <span m="1312900">case,</span>
  <span m="1313200">is</span> <span m="1313380">lambda</span> <span m="1313600">times</span>
  <span m="1313940">V</span> <span m="1314430">n.</span></p><p><span m="1319330">So</span>
  <span m="1319600">let''s</span> <span m="1319910">move</span> <span m="1322440">all
  the</span> <span m="1323290">knowns</span> <span m="1324110">to</span> <span m="1324260">the</span>
  <span m="1324360">right</span> <span m="1324540">hand side.</span> <span m="1324920">So</span>
  <span m="1325070">this</span> <span m="1325340">term</span> <span m="1325590">is</span>
  <span m="1325780">known,</span> <span m="1326105">and</span> <span m="1326430">this</span>
  <span m="1326970">term</span> <span m="1327110">is</span> <span m="1327240">known.</span>
  <span m="1327730">So</span> <span m="1327930">move</span> <span m="1328220">this</span>
  <span m="1328410">to</span> <span m="1328540">the</span> <span m="1328710">right</span>
  <span m="1328960">hand</span> <span m="1329130">side.</span> <span m="1329850">We</span>
  <span m="1330120">have</span> <span m="1331290">V n</span> <span m="1331920">plus</span>
  <span m="1332210">1</span> <span m="1332610">over</span> <span m="1332950">delta</span>
  <span m="1333290">t</span> <span m="1334080">is</span> <span m="1334410">equal</span>
  <span m="1334820">to</span> <span m="1335100">V n</span> <span m="1336740">over</span>
  <span m="1337130">the</span> <span m="1337210">delta t</span> <span m="1337840">plus</span>
  <span m="1338280">lambda</span> <span m="1338535">times</span> <span m="1338790">v
  n.</span></p><p><span m="1339965">And</span> <span m="1340750">the</span> <span
  m="1340897">[INAUDIBLE]</span> <span m="1341818">is,</span> <span m="1343730">if</span>
  <span m="1344020">we</span> <span m="1344300">[INAUDIBLE],</span> <span m="1346530">V
  n</span> <span m="1347080">plus</span> <span m="1347440">1</span> <span m="1347900">would</span>
  <span m="1348140">be</span> <span m="1348340">equal</span> <span m="1348730">to</span>
  <span m="1349490">1</span> <span m="1350080">plus</span> <span m="1350870">delta</span>
  <span m="1351030">t</span> <span m="1351240">lambda</span> <span m="1353290">times</span>
  <span m="1353480">v n.</span> <span m="1358330">We</span> <span m="1358450">can</span>
  <span m="1358610">easily</span> <span m="1358930">see</span> <span m="1359470">if</span>
  <span m="1360110">lambda</span> <span m="1360500">is</span> <span m="1360890">greater</span>
  <span m="1361280">than</span> <span m="1361940">0,</span> <span m="1363540">we</span>
  <span m="1363680">have</span> <span m="1363950">a</span> <span m="1364340">growing</span>
  <span m="1364760">solution.</span> <span m="1365550">If</span> <span m="1365750">lambda</span>
  <span m="1366380">is</span> <span m="1366680">greater</span> <span m="1367120">than</span>
  <span m="1367560">zero,</span> <span m="1368233">this</span> <span m="1368686">term
  is</span> <span m="1369139">greater than 1,</span> <span m="1369592">we</span> <span
  m="1370045">grow.</span></p><p><span m="1371410">What</span> <span m="1371610">if</span>
  <span m="1371820">lambda</span> <span m="1372250">delta</span> <span m="1372680">t</span>
  <span m="1373540">is</span> <span m="1373970">less than minus</span> <span m="1374400">2?</span>
  <span m="1382330">We</span> <span m="1382630">get</span> <span m="1383760">an</span>
  <span m="1384065">oscillatory</span> <span m="1385220">growing</span> <span m="1385650">solution</span>
  <span m="1386080">because</span> <span m="1386510">1</span> <span m="1386940">plus</span>
  <span m="1387320">delta</span> <span m="1387780">t</span> <span m="1388120">lambda</span>
  <span m="1388465">would</span> <span m="1388810">be</span> <span m="1389080">less</span>
  <span m="1389290">than</span> <span m="1389420">minus</span> <span m="1389560">1.</span>
  <span m="1390530">And</span> <span m="1390810">the</span> <span m="1391120">next</span>
  <span m="1392050">iteration</span> <span m="1392660">I''m</span> <span m="1392810">going</span>
  <span m="1392940">to</span> <span m="1393010">get</span> <span m="1394280">a</span>
  <span m="1394470">solution</span> <span m="1394910">of</span> <span m="1395070">the</span>
  <span m="1395230">opposite</span> <span m="1395830">sign,</span> <span m="1396220">but
  larger than</span> <span m="1397610">what</span> <span m="1397780">it</span> <span
  m="1397900">is</span> <span m="1398120">at</span> <span m="1398310">the n</span>
  <span m="1398580">times</span> <span m="1399386">f.</span> <span m="1399790">That</span>
  <span m="1399990">is</span> <span m="1400160">why</span> <span m="1402050">forward
  Euler</span> <span m="1402680">is</span> <span m="1403080">unstable</span> <span
  m="1403820">when</span> <span m="1404080">we</span> <span m="1404270">have</span>
  <span m="1404590">a</span> <span m="1405090">lambda</span> <span m="1405590">delta
  t</span> <span m="1406090">less</span> <span m="1406590">than</span> <span m="1407090">minus
  2.</span> <span m="1410180">Same</span> <span m="1410450">thing</span> <span m="1410650">happens</span>
  <span m="1411441">when</span> <span m="1411882">lambda</span> <span m="1412764">is</span>
  <span m="1413205">imaginary</span> <span m="1414462">and</span> <span m="1416350">1</span>
  <span m="1416820">plus</span> <span m="1417070">delta</span> <span m="1417500">t</span>
  <span m="1417930">lambda</span> <span m="1418360">has</span> <span m="1418780">a</span>
  <span m="1419040">modulus</span> <span m="1419510">of</span> <span m="1419710">greater</span>
  <span m="1420060">than</span> <span m="1420260">1,</span> <span m="1422870">that</span>
  <span m="1423030">means</span> <span m="1423498">we</span> <span m="1423966">are</span>
  <span m="1424434">[INAUDIBLE].</span></p><p><span m="1428180">So</span> <span m="1428300">that''s</span>
  <span m="1428550">how</span> <span m="1428730">you</span> <span m="1428830">do</span>
  <span m="1429130">eigenvalue</span> <span m="1430010">stability</span> <span m="1430490">analysis.</span>
  <span m="1431830">You</span> <span m="1432960">plug in</span> <span m="1434080">f</span>
  <span m="1434430">of</span> <span m="1434907">u</span> <span m="1435861">for</span>
  <span m="1436338">the</span> <span m="1436815">lambda</span> <span m="1437292">u</span>
  <span m="1437769">into the</span> <span m="1438246">differential</span> <span m="1438723">equation.</span>
  <span m="1439200">You</span> <span m="1439540">collect</span> <span m="1439980">all</span>
  <span m="1440190">the</span> <span m="1440330">terms</span> <span m="1441210">that</span>
  <span m="1441650">is</span> <span m="1441950">[INAUDIBLE].</span></p><p><span m="1446910">And</span>
  <span m="1447070">in</span> <span m="1447180">general,</span> <span m="1447690">you</span>
  <span m="1448060">plug</span> <span m="1448410">in</span> <span m="1448990">the</span>
  <span m="1449150">solution</span> <span m="1449850">that</span> <span m="1450030">is</span>
  <span m="1450380">exponentially</span> <span m="1451130">growing</span> <span m="1451660">to</span>
  <span m="1452025">see</span> <span m="1452390">if</span> <span m="1455090">the</span>
  <span m="1455380">script</span> <span m="1455670">scheme</span> <span m="1456120">allows</span>
  <span m="1456870">an</span> <span m="1457310">exponentially</span> <span m="1457920">growing</span>
  <span m="1458185">solution.</span> <span m="1460780">That</span> <span m="1460970">is</span>
  <span m="1461170">how</span> <span m="1461960">you</span> <span m="1462180">would</span>
  <span m="1462637">analyze</span> <span m="1463551">eigenvalue</span> <span m="1464008">stability,</span>
  <span m="1465836">similar</span> <span m="1466293">to</span> <span m="1467210">how</span>
  <span m="1467680">you would</span> <span m="1468151">analyze</span> <span m="1469093">zero
  stability.</span> <span m="1470980">Any</span> <span m="1471100">questions?</span></p><p><span
  m="1472721">AUDIENCE: [INAUDIBLE]</span></p><p><span m="1477700">PROFESSOR: Yeah,</span>
  <span m="1477820">the</span> <span m="1478170">absolute</span> <span m="1478720">value</span>
  <span m="1479030">of</span> <span m="1479160">that</span> <span m="1479340">one</span>
  <span m="1479824">has</span> <span m="1480308">to</span> <span m="1480792">be</span>
  <span m="1481276">less</span> <span m="1481760">than</span> <span m="1482244">or
  equal</span> <span m="1482728">to</span> <span m="1483212">1.</span> <span m="1484180">Yes.</span>
  <span m="1485148">Yep?</span></p><p><span m="1486116">AUDIENCE: So, when you said</span>
  <span m="1487084">that</span> <span m="1487580">the</span> <span m="1488315">[INAUDIBLE]</span>
  <span m="1489225">has</span> <span m="1489680">to</span> <span m="1490135">be</span>
  <span m="1491045">less</span> <span m="1491500">than</span> <span m="1491800">minus</span>
  <span m="1492300">2,</span> <span m="1493300">[INAUDIBLE]?</span></p><p><span m="1495300">PROFESSOR:
  [INAUDIBLE]</span></p><p><span m="1498744">AUDIENCE: OK.</span> <span m="1499230">Yeah.</span>
  <span m="1500202">[INAUDIBLE]</span></p><p><span m="1506040">PROFESSOR: OK,</span>
  <span m="1506320">good question.</span> <span m="1506950">When</span> <span m="1507200">you</span>
  <span m="1507360">are</span> <span m="1507480">implementing</span> <span m="1508060">forward
  Euler</span> <span m="1508480">on</span> <span m="1508680">the</span> <span m="1508770">real</span>
  <span m="1509080">thing,</span> <span m="1509760">how</span> <span m="1509970">do</span>
  <span m="1510060">you</span> <span m="1510220">know</span> <span m="1510700">[INAUDIBLE]?</span>
  <span m="1514890">It''s</span> <span m="1515080">a</span> <span m="1515170">good</span>
  <span m="1515350">question.</span></p><p><span m="1518180">So</span> <span m="1518430">most</span>
  <span m="1518730">of</span> <span m="1518840">the</span> <span m="1518920">time,</span>
  <span m="1519430">you</span> <span m="1519570">can</span> <span m="1521110">analyze</span>
  <span m="1521650">the</span> <span m="1521880">eigenvalues--</span> <span m="1524130">let</span>
  <span m="1524510">me</span> <span m="1524590">back</span> <span m="1525460">up.</span>
  <span m="1526010">Let</span> <span m="1526230">me</span> <span m="1526390">say,</span>
  <span m="1527870">if</span> <span m="1528090">you</span> <span m="1528210">look</span>
  <span m="1528590">at</span> <span m="1528930">a</span> <span m="1529990">scalar</span>
  <span m="1530590">differential equation,</span> <span m="1531090">if</span> <span
  m="1532010">you</span> <span m="1532100">look</span> <span m="1532330">at,</span>
  <span m="1532460">like,</span> <span m="1532700">just</span> <span m="1532880">one</span>
  <span m="1533300">single</span> <span m="1533640">differential equation,</span>
  <span m="1534630">not</span> <span m="1534800">a</span> <span m="1535225">[? coupled
  ?]</span> <span m="1535650">system</span> <span m="1536020">of</span> <span m="1536150">differential
  equations,</span> <span m="1538280">even</span> <span m="1538520">if</span> <span
  m="1538690">the</span> <span m="1538800">equation</span> <span m="1539070">is</span>
  <span m="1539210">non-linear,</span> <span m="1540050">you</span> <span m="1540170">can</span>
  <span m="1540310">usually</span> <span m="1540630">linearize</span> <span m="1541450">the</span>
  <span m="1541560">differential equation</span> <span m="1542480">and</span> <span
  m="1542720">look</span> <span m="1543020">at</span> <span m="1543640">what</span>
  <span m="1543920">lambda</span> <span m="1544890">is</span> <span m="1545380">for</span>
  <span m="1545580">linearized</span> <span m="1546400">differential equation.</span>
  <span m="1548340">And</span> <span m="1548560">the</span> <span m="1548620">key</span>
  <span m="1549090">is</span> <span m="1549330">not</span> <span m="1550040">to</span>
  <span m="1550370">manipulate</span> <span m="1551010">lambda,</span> <span m="1551950">but</span>
  <span m="1552190">ensure</span> <span m="1552840">that</span> <span m="1553160">delta</span>
  <span m="1553580">t</span> <span m="1554400">is</span> <span m="1554660">small</span>
  <span m="1554890">enough.</span></p><p><span m="1558000">So</span> <span m="1558100">let''s</span>
  <span m="1558360">look</span> <span m="1558550">at</span> <span m="1558930">here.</span>
  <span m="1559890">Imagine</span> <span m="1560310">[INAUDIBLE]</span> <span m="1561560">lambda</span>
  <span m="1561810">delta t.</span> <span m="1562770">But</span> <span m="1563390">imagine</span>
  <span m="1563990">your</span> <span m="1564570">lambda</span> <span m="1564740">is</span>
  <span m="1565150">taken</span> <span m="1565560">over</span> <span m="1565970">here.</span>
  <span m="1566790">If</span> <span m="1566830">your</span> <span m="1567330">lambda</span>
  <span m="1567570">is,</span> <span m="1567900">let''s</span> <span m="1568100">say,</span>
  <span m="1568730">minus</span> <span m="1569200">[INAUDIBLE].</span> <span m="1573160">Can</span>
  <span m="1573430">forward Euler</span> <span m="1573730">be</span> <span m="1573950">stable?</span>
  <span m="1576565">No?</span></p><p><span m="1580218">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="1581630">PROFESSOR: If</span> <span m="1581810">my</span> <span m="1581970">lambda</span>
  <span m="1582310">is</span> <span m="1582500">here,</span> <span m="1583943">can</span>
  <span m="1584424">forward Euler</span> <span m="1584905">be stable?</span></p><p><span
  m="1585867">AUDIENCE: [INAUDIBLE]</span></p><p><span m="1588920">PROFESSOR: We</span>
  <span m="1589130">still</span> <span m="1589540">have</span> <span m="1589920">delta
  t,</span> <span m="1590625">right?</span> <span m="1593425">If</span> <span m="1593910">lambda</span>
  <span m="1594395">is here,</span> <span m="1594880">what is to make</span> <span
  m="1594950">delta t</span> <span m="1595360">with</span> <span m="1595570">a</span>
  <span m="1595790">0.1?</span> <span m="1597720">Then</span> <span m="1598010">lambda</span>
  <span m="1598370">has</span> <span m="1598580">delta t</span> <span m="1599046">which</span>
  <span m="1599512">[INAUDIBLE]</span> <span m="1599980">way</span> <span m="1600240">over
  to</span> <span m="1600500">here,</span> <span m="1601280">into</span> <span m="1601580">the</span>
  <span m="1601800">stability</span> <span m="1602185">region.</span> <span m="1604180">And</span>
  <span m="1604370">we</span> <span m="1604470">are</span> <span m="1604580">fine,</span>
  <span m="1605075">right?</span> <span m="1606870">OK,</span> <span m="1607140">what</span>
  <span m="1607560">if</span> <span m="1607920">lambda</span> <span m="1608280">is</span>
  <span m="1609100">minus</span> <span m="1609750">500</span> <span m="1610573">plus</span>
  <span m="1611520">1,000</span> <span m="1612110">times</span> <span m="1612420">i.</span></p><p><span
  m="1613335">AUDIENCE: [INAUDIBLE]</span></p><p><span m="1617140">PROFESSOR: Yeah,</span>
  <span m="1617250">even</span> <span m="1617690">if</span> <span m="1618956">lambda</span>
  <span m="1619444">is</span> <span m="1620420">minus</span> <span m="1620860">500</span>
  <span m="1621450">[INAUDIBLE]</span> <span m="1623210">to</span> <span m="1623590">make</span>
  <span m="1623780">the</span> <span m="1624060">delta</span> <span m="1624400">t
  equal to</span> <span m="1624590">0.0001,</span> <span m="1627180">you''re</span>
  <span m="1627390">going</span> <span m="1627510">to</span> <span m="1627570">be</span>
  <span m="1628030">fine.</span> <span m="1629136">You''re going to</span> <span m="1629589">shrink</span>
  <span m="1630042">your</span> <span m="1630495">eigenvalues</span> <span m="1630948">times</span>
  <span m="1631854">delta</span> <span m="1632307">t into</span> <span m="1632760">here.</span>
  <span m="1632920">And you''re</span> <span m="1633110">fine.</span></p><p><span
  m="1636010">OK,</span> <span m="1636140">what</span> <span m="1636260">pieces</span>
  <span m="1636545">are</span> <span m="1636940">not</span> <span m="1637180">fine?</span>
  <span m="1639370">What</span> <span m="1639670">are</span> <span m="1639750">the</span>
  <span m="1639820">cases</span> <span m="1640120">where,</span> <span m="1640870">no</span>
  <span m="1641060">matter</span> <span m="1641360">how</span> <span m="1641540">small</span>
  <span m="1641800">you</span> <span m="1641920">make</span> <span m="1642160">the</span>
  <span m="1642250">delta</span> <span m="1642390">t,</span> <span m="1642530">you''re</span>
  <span m="1643020">going to</span> <span m="1643510">be</span> <span m="1644000">unstable?</span></p><p><span
  m="1644980">AUDIENCE: [INAUDIBLE]</span></p><p><span m="1647930">PROFESSOR: Right,</span>
  <span m="1648800">if</span> <span m="1649260">lambda</span> <span m="1650130">has</span>
  <span m="1650440">a</span> <span m="1650700">positive</span> <span m="1651145">real</span>
  <span m="1651590">cost,</span> <span m="1652035">if lambda</span> <span m="1652480">is
  always here, and</span> <span m="1652630">no</span> <span m="1652780">matter</span>
  <span m="1653160">how</span> <span m="1653580">small</span> <span m="1653850">you</span>
  <span m="1653990">shrink</span> <span m="1654420">it,</span> <span m="1654990">you
  get a small</span> <span m="1655397">delta t--</span> <span m="1655804">because</span>
  <span m="1656211">delta t</span> <span m="1656620">has to be</span> <span m="1656810">real,</span>
  <span m="1657485">right?</span> <span m="1658790">The</span> <span m="1659130">constant
  has to be real.</span> <span m="1659900">You''re going to shrink it to</span> <span
  m="1660770">over</span> <span m="1661050">here,</span> <span m="1661465">but</span>
  <span m="1661880">it''s</span> <span m="1662220">still unstable,</span> <span m="1662625">right?</span>
  <span m="1663840">OK,</span> <span m="1664080">what are</span> <span m="1664340">the</span>
  <span m="1664520">cases</span> <span m="1665603">where</span> <span m="1666086">forward
  Euler</span> <span m="1666570">is</span> <span m="1666840">not working?</span></p><p><span
  m="1668235">AUDIENCE: [INAUDIBLE]</span></p><p><span m="1671490">PROFESSOR: If it''s</span>
  <span m="1671960">just</span> <span m="1672390">an</span> <span m="1672560">oscillation,</span>
  <span m="1673250">if</span> <span m="1674856">the</span> <span m="1675290">eigenvalue</span>
  <span m="1676000">lambda</span> <span m="1676830">is</span> <span m="1677280">just</span>
  <span m="1677620">a</span> <span m="1677990">dual</span> <span m="1678450">imaginary</span>
  <span m="1678840">value,</span> <span m="1680910">it''s</span> <span m="1681620">a</span>
  <span m="1681905">non-decaying</span> <span m="1682620">oscillation.</span> <span
  m="1683620">So</span> <span m="1683770">if</span> <span m="1684070">the</span> <span
  m="1684260">analytical</span> <span m="1684635">solution</span> <span m="1685610">is</span>
  <span m="1685690">a</span> <span m="1685965">non-decaying</span> <span m="1686500">oscillation,</span>
  <span m="1688540">just</span> <span m="1688820">like</span> <span m="1689680">what</span>
  <span m="1689930">we</span> <span m="1690140">had</span> <span m="1690870">on</span>
  <span m="1691370">[INAUDIBLE],</span> <span m="1692050">like</span> <span m="1692483">the</span>
  <span m="1692916">pendulum,</span> <span m="1696040">if</span> <span m="1696260">we</span>
  <span m="1696390">have</span> <span m="1696690">a</span> <span m="1697025">pendulum</span>
  <span m="1697360">that</span> <span m="1697760">has</span> <span m="1697970">no</span>
  <span m="1698290">density,</span> <span m="1699155">forward Euler</span> <span m="1699790">would</span>
  <span m="1700280">never</span> <span m="1700540">be</span> <span m="1700800">eigenvalue</span>
  <span m="1701290">stable.</span></p><p><span m="1702740">And</span> <span m="1702940">that''s</span>
  <span m="1703180">what</span> <span m="1703400">we</span> <span m="1703530">saw,</span>
  <span m="1703900">right?</span> <span m="1704680">I mean,</span> <span m="1705070">even</span>
  <span m="1705460">when</span> <span m="1705770">we</span> <span m="1705880">made</span>
  <span m="1706160">delta t</span> <span m="1706270">to</span> <span m="1706645">be</span>
  <span m="1707020">small,</span> <span m="1707650">it''s</span> <span m="1708140">still</span>
  <span m="1708270">mildly</span> <span m="1708630">growing.</span> <span m="1713040">So</span>
  <span m="1713210">yes,</span> <span m="1713520">forward</span> <span m="1713950">Euler</span>
  <span m="1714180">will work</span> <span m="1714520">if</span> <span m="1714750">you</span>
  <span m="1715010">could</span> <span m="1715190">have</span> <span m="1715290">a</span>
  <span m="1715510">positive</span> <span m="1716350">real</span> <span m="1716690">eigenvalue,</span>
  <span m="1717160">or</span> <span m="1717490">you could</span> <span m="1717760">have</span>
  <span m="1717890">a</span> <span m="1718040">zero</span> <span m="1718460">real</span>
  <span m="1718910">eigenvalue.</span> <span m="1719630">Otherwise,</span> <span m="1720170">you</span>
  <span m="1720250">can</span> <span m="1720360">always</span> <span m="1720840">shrink</span>
  <span m="1721240">your</span> <span m="1721380">delta t</span> <span m="1722450">so</span>
  <span m="1722640">that</span> <span m="1723130">the</span> <span m="1723340">scheme</span>
  <span m="1723630">is</span> <span m="1723760">stable.</span></p><p><span m="1725140">Let''s</span>
  <span m="1725460">look</span> <span m="1725730">at</span> <span m="1725840">another</span>
  <span m="1726250">scheme,</span> <span m="1726650">midpoint.</span> <span m="1729650">OK,</span>
  <span m="1730430">what</span> <span m="1730590">happens</span> <span m="1730920">on</span>
  <span m="1731090">midpoint?</span> <span m="1731590">What</span> <span m="1731810">is</span>
  <span m="1732220">the</span> <span m="1732330">stability</span> <span m="1732710">region</span>
  <span m="1733100">of</span> <span m="1733260">midpoint?</span> <span m="1738970">It
  lies</span> <span m="1739600">exactly</span> <span m="1739910">on the</span> <span
  m="1740713">imaginary</span> <span m="1741520">axis</span> <span m="1742125">from</span>
  <span m="1743232">[INAUDIBLE].</span> <span m="1747660">So</span> <span m="1748620">the</span>
  <span m="1748880">case</span> <span m="1749330">we</span> <span m="1749500">have
  to</span> <span m="1749770">analyzed</span> <span m="1750270">saying</span> <span
  m="1750660">two</span> <span m="1750870">oscillations</span> <span m="1752720">would</span>
  <span m="1752960">never</span> <span m="1753260">work</span> <span m="1753993">for</span>
  <span m="1754426">forward Euler,</span> <span m="1754860">would never</span> <span
  m="1755000">be</span> <span m="1755210">stable</span> <span m="1755680">for</span>
  <span m="1755890">forward Euler,</span> <span m="1757020">it</span> <span m="1757280">works</span>
  <span m="1757660">perfectly</span> <span m="1757860">fine</span> <span m="1758345">for</span>
  <span m="1758830">midpoint.</span></p><p><span m="1761860">That''s</span> <span
  m="1762160">why,</span> <span m="1762490">when</span> <span m="1762670">we</span>
  <span m="1762780">did</span> <span m="1762950">the</span> <span m="1763060">pendulum</span>
  <span m="1763520">case,</span> <span m="1764200">midpoint</span> <span m="1764430">worked</span>
  <span m="1764790">so</span> <span m="1764940">well.</span> <span m="1766440">It</span>
  <span m="1766830">was,</span> <span m="1767280">like,</span> <span m="1768130">amazingly</span>
  <span m="1768410">better</span> <span m="1768690">than</span> <span m="1769514">forward
  Euler.</span> <span m="1770340">But</span> <span m="1770570">when</span> <span m="1770910">we</span>
  <span m="1771180">applied</span> <span m="1772010">to</span> <span m="1774530">this</span>
  <span m="1774850">case,</span> <span m="1776280">forward Euler</span> <span m="1777088">works</span>
  <span m="1777964">better</span> <span m="1779278">because-- try to</span> <span
  m="1779720">guess</span> <span m="1780280">where</span> <span m="1780650">the</span>
  <span m="1780780">eigenvalues</span> <span m="1781410">are</span> <span m="1782646">for</span>
  <span m="1783753">the</span> <span m="1784860">case</span> <span m="1785720">we</span>
  <span m="1786580">had</span> <span m="1787080">on</span> <span m="1787920">[INAUDIBLE].</span></p><p><span
  m="1789780">Anybody</span> <span m="1789930">wants</span> <span m="1790120">to</span>
  <span m="1790230">take a</span> <span m="1790450">guess of what</span> <span m="1791650">lambda</span>
  <span m="1792360">is</span> <span m="1793290">for</span> <span m="1793420">that</span>
  <span m="1793630">problem?</span> <span m="1805100">Something</span> <span m="1805480">with</span>
  <span m="1805640">a</span> <span m="1805680">very</span> <span m="1805980">small</span>
  <span m="1806230">imaginary</span> <span m="1806350">component?</span></p><p><span
  m="1807844">AUDIENCE: [INAUDIBLE]</span></p><p><span m="1813830">PROFESSOR: [INAUDIBLE]</span>
  <span m="1815000">means</span> <span m="1816470">you have</span> <span m="1816710">negative</span>
  <span m="1817500">real</span> <span m="1818180">part, right?</span></p><p><span
  m="1818777">AUDIENCE: Yeah.</span> <span m="1819711">[INAUDIBLE]</span></p><p><span
  m="1823914">PROFESSOR: If you look</span> <span m="1824680">midpoint,</span> <span
  m="1826090">as</span> <span m="1826320">long</span> <span m="1826640">as</span>
  <span m="1826860">the</span> <span m="1826960">eigenvalue</span> <span m="1827140">lambda</span>
  <span m="1828020">has</span> <span m="1828460">a</span> <span m="1829165">non-zero</span>
  <span m="1831620">[INAUDIBLE],</span> <span m="1833620">then it wouldn''t</span>
  <span m="1834010">be</span> <span m="1834560">stable,</span> <span m="1835960">no</span>
  <span m="1836170">matter</span> <span m="1836470">how</span> <span m="1836770">small</span>
  <span m="1837240">you make</span> <span m="1837685">delta</span> <span m="1838130">t--</span>
  <span m="1839020">I mean,</span> <span m="1839310">if the</span> <span m="1839680">eigenvalue</span>
  <span m="1840500">is</span> <span m="1840950">here, over here,</span> <span m="1841850">no</span>
  <span m="1842300">matter</span> <span m="1842750">how</span> <span m="1843080">small</span>
  <span m="1843410">you</span> <span m="1843822">make</span> <span m="1844234">delta</span>
  <span m="1844646">t</span> <span m="1845060">[INAUDIBLE]</span> <span m="1846110">was</span>
  <span m="1846370">the</span> <span m="1846803">origin.</span> <span m="1847670">But
  no</span> <span m="1847955">matter</span> <span m="1848490">how</span> <span m="1848840">much
  you shrink</span> <span m="1849190">it, you will</span> <span m="1850110">never</span>
  <span m="1850670">be</span> <span m="1851000">exactly</span> <span m="1851770">on</span>
  <span m="1852230">the</span> <span m="1853150">imaginary</span> <span m="1853610">axis</span>
  <span m="1854070">between</span> <span m="1854990">[INAUDIBLE],</span> <span m="1855450">right?</span></p><p><span
  m="1856500">So</span> <span m="1856540">as</span> <span m="1856900">long</span>
  <span m="1857190">as</span> <span m="1859370">the</span> <span m="1859510">solution</span>
  <span m="1859890">is</span> <span m="1860010">not</span> <span m="1862740">pure</span>
  <span m="1862990">oscillation,</span> <span m="1864055">midpoint</span> <span m="1865190">wouldn''t</span>
  <span m="1865380">work.</span> <span m="1867430">So</span> <span m="1867760">forward
  Euler</span> <span m="1868070">and</span> <span m="1868310">midpoint</span> <span
  m="1868950">are</span> <span m="1869070">like</span> <span m="1869930">two</span>
  <span m="1870440">schemes</span> <span m="1871135">that</span> <span m="1871440">have</span>
  <span m="1871640">complimentary</span> <span m="1873160">values,</span> <span m="1873700">but</span>
  <span m="1873910">they</span> <span m="1874070">never</span> <span m="1874680">overlap.</span>
  <span m="1877710">A</span> <span m="1877900">question</span> <span m="1878230">would</span>
  <span m="1878350">either</span> <span m="1878700">work</span> <span m="1878960">for</span>
  <span m="1879870">forward Euler,</span> <span m="1880470">or it''ll</span> <span
  m="1880900">work</span> <span m="1881230">for</span> <span m="1881400">midpoint</span>
  <span m="1882420">with</span> <span m="1882680">a</span> <span m="1882830">small</span>
  <span m="1883090">enough</span> <span m="1883400">time</span> <span m="1883600">stamp.</span></p><p><span
  m="1887970">If</span> <span m="1888730">the</span> <span m="1888870">lambda</span>
  <span m="1889710">is</span> <span m="1890330">exactly</span> <span m="1890690">on
  the</span> <span m="1891050">imaginary</span> <span m="1891630">axis,</span> <span
  m="1892700">with</span> <span m="1893560">a</span> <span m="1893990">small</span>
  <span m="1894420">enough</span> <span m="1895100">delta</span> <span m="1895580">t,
  you can</span> <span m="1896060">make</span> <span m="1896360">midpoint</span> <span
  m="1896753">work.</span> <span m="1897146">If</span> <span m="1897540">it</span>
  <span m="1897760">has</span> <span m="1898137">a</span> <span m="1898514">negative</span>
  <span m="1899270">real</span> <span m="1899730">part</span> <span m="1902160">with</span>
  <span m="1902340">a</span> <span m="1902500">small</span> <span m="1902770">enough</span>
  <span m="1903440">[? timestamp, ?]</span> <span m="1905540">you''re</span> <span
  m="1905790">going</span> <span m="1905960">to</span> <span m="1906060">make</span>
  <span m="1906850">lambda times</span> <span m="1907646">delta</span> <span m="1908092">t</span>
  <span m="1908538">into</span> <span m="1908984">this</span> <span m="1909430">region.</span></p><p><span
  m="1911220">What</span> <span m="1911470">we''re</span> <span m="1911760">not</span>
  <span m="1911930">concerned</span> <span m="1912402">about is</span> <span m="1912874">where</span>
  <span m="1913346">lambda</span> <span m="1913820">has a</span> <span m="1914180">positive</span>
  <span m="1914550">real</span> <span m="1914790">part</span> <span m="1915267">because</span>
  <span m="1915744">the</span> <span m="1916221">differential</span> <span m="1916698">equation</span>
  <span m="1917175">is</span> <span m="1917652">unstable,</span> <span m="1918130">and</span>
  <span m="1918330">we</span> <span m="1918595">don''t</span> <span m="1918860">want
  to solve it</span> <span m="1919100">anyway.</span> <span m="1921550">I</span> <span
  m="1921620">mean,</span> <span m="1921790">we</span> <span m="1922030">don''t</span>
  <span m="1922240">expect</span> <span m="1922630">it</span> <span m="1922730">to</span>
  <span m="1922820">be</span> <span m="1923292">stable.</span> <span m="1925180">Yeah,</span>
  <span m="1926040">right.</span> <span m="1927720">So</span> <span m="1928640">right.</span></p><p><span
  m="1928950">So</span> <span m="1929140">we</span> <span m="1930230">don''t</span>
  <span m="1930630">really</span> <span m="1930960">expect</span> <span m="1931960">our</span>
  <span m="1932045">scheme</span> <span m="1932130">to</span> <span m="1932250">be</span>
  <span m="1932585">stable.</span> <span m="1934580">If</span> <span m="1935080">it''s</span>
  <span m="1935240">stable, then it</span> <span m="1935420">is</span> <span m="1935550">artificially</span>
  <span m="1936170">stable</span> <span m="1937070">because</span> <span m="1937350">the</span>
  <span m="1937470">real</span> <span m="1937730">solution</span> <span m="1938180">here</span>
  <span m="1938370">is</span> <span m="1938460">going</span> <span m="1938620">to</span>
  <span m="1938700">be</span> <span m="1938800">unstable.</span> <span m="1942350">Backward
  Euler,</span> <span m="1943290">[INAUDIBLE]</span> <span m="1949280">OK, we can
  see</span> <span m="1949640">that,</span> <span m="1949880">for any</span> <span
  m="1950175">differential</span> <span m="1950470">equation</span> <span m="1950760">that</span>
  <span m="1951050">is</span> <span m="1952890">actually</span> <span m="1953420">stable,</span>
  <span m="1955440">backward Euler</span> <span m="1955740">is</span> <span m="1956213">stable.</span></p><p><span
  m="1957160">The</span> <span m="1957280">blue</span> <span m="1957535">region</span>
  <span m="1958290">is</span> <span m="1959290">[INAUDIBLE]</span> <span m="1961290">no</span>
  <span m="1961520">matter</span> <span m="1961900">how</span> <span m="1962210">big</span>
  <span m="1962920">delta</span> <span m="1963050">t</span> <span m="1963300">is--</span>
  <span m="1963855">you</span> <span m="1964270">can</span> <span m="1964480">make</span>
  <span m="1965260">delta</span> <span m="1965420">t</span> <span m="1965860">equal
  to</span> <span m="1966300">1,000</span> <span m="1966590">if</span> <span m="1966750">you</span>
  <span m="1966810">like,</span> <span m="1967230">backward Euler</span> <span m="1968218">is</span>
  <span m="1968712">[INAUDIBLE]</span> <span m="1969206">stable.</span> <span m="1972120">So</span>
  <span m="1972700">even</span> <span m="1973160">in</span> <span m="1973635">this</span>
  <span m="1974110">region,</span> <span m="1975060">where</span> <span m="1975110">the</span>
  <span m="1975370">real</span> <span m="1975730">differential</span> <span m="1976010">equation</span>
  <span m="1977080">is</span> <span m="1977480">unstable,</span> <span m="1978520">artificially</span>
  <span m="1979370">makes</span> <span m="1979960">the</span> <span m="1980520">solution</span>
  <span m="1981360">stable,</span> <span m="1982120">which</span> <span m="1983190">actually</span>
  <span m="1983640">gives</span> <span m="1983850">you a</span> <span m="1983960">wrong</span>
  <span m="1984310">answer,</span> <span m="1984804">but</span> <span m="1985298">[INAUDIBLE]</span>
  <span m="1985792">stable.</span></p><p><span m="1986286">[LAUGHTER]</span></p><p><span
  m="1986780">All</span> <span m="1986820">right.</span> <span m="1989200">Trapezoidal</span>
  <span m="1990080">rule.</span> <span m="1991500">That</span> <span m="1993150">is,</span>
  <span m="1994150">like,</span> <span m="1994590">yeah,</span> <span m="1994980">you
  said</span> <span m="1995550">that''s</span> <span m="1995900">what</span> <span
  m="1996285">we want</span> <span m="1996670">because,</span> <span m="1997605">if
  you</span> <span m="1998100">look at the</span> <span m="1998595">stability</span>
  <span m="1999090">ratio</span> <span m="1999585">of</span> <span m="2000575">trapezoidal</span>
  <span m="2001070">rule, it</span> <span m="2001290">is</span> <span m="2001780">exactly</span>
  <span m="2002560">the</span> <span m="2002700">same</span> <span m="2003090">stability</span>
  <span m="2003580">region</span> <span m="2004070">as</span> <span m="2004370">the</span>
  <span m="2004510">analytical</span> <span m="2005740">ODE.</span> <span m="2007770">It</span>
  <span m="2008380">doesn''t</span> <span m="2008730">always</span> <span m="2009080">mean</span>
  <span m="2009440">you''re</span> <span m="2009680">going</span> <span m="2009820">to</span>
  <span m="2009980">get</span> <span m="2010770">the</span> <span m="2011240">expected</span>
  <span m="2011710">behavior</span> <span m="2013560">because</span> <span m="2013840">you''re</span>
  <span m="2014250">going to</span> <span m="2014540">see</span> <span m="2014982">is</span>
  <span m="2015866">my lambda delta  t</span> <span m="2016310">is</span> <span m="2016450">always</span>
  <span m="2016710">here,</span> <span m="2017664">the</span> <span m="2018620">rate</span>
  <span m="2019000">of decay</span> <span m="2019330">of</span> <span m="2019920">the</span>
  <span m="2020834">trapezoidal</span> <span m="2021291">rule</span> <span m="2021750">versus
  the real</span> <span m="2022150">ODE</span> <span m="2022810">is going to be</span>
  <span m="2023310">very</span> <span m="2023810">different.</span> <span m="2024810">So</span>
  <span m="2025310">like,</span> <span m="2025810">at</span> <span m="2026100">least
  in terms of</span> <span m="2026595">stability reading,</span> <span m="2027420">it</span>
  <span m="2027610">is</span> <span m="2027910">exactly</span> <span m="2028710">what</span>
  <span m="2028990">you</span> <span m="2029080">have</span> <span m="2029530">for
  the</span> <span m="2029967">analytical</span> <span m="2031280">ODE.</span></p><p><span
  m="2033630">And</span> <span m="2033860">the</span> <span m="2033950">wrong</span>
  <span m="2034160">[INAUDIBLE]</span> <span m="2034610">schemes</span> <span m="2035290">is</span>
  <span m="2035490">something</span> <span m="2035910">you</span> <span m="2036040">are</span>
  <span m="2036130">going</span> <span m="2036330">to</span> <span m="2036420">learn</span>
  <span m="2036920">later</span> <span m="2037300">on</span> <span m="2038086">for</span>
  <span m="2038980">this</span> <span m="2039270">week''s</span> <span m="2039780">reading.</span>
  <span m="2040490">But</span> <span m="2040760">you''re</span> <span m="2040880">going
  to see</span> <span m="2041160">these</span> <span m="2041590">weird</span> <span
  m="2042000">shapes.</span> <span m="2044150">The</span> <span m="2044270">[INAUDIBLE]</span>
  <span m="2044450">schemes</span> <span m="2044740">are</span> <span m="2047280">explicit</span>
  <span m="2047710">schemes.</span> <span m="2049000">So</span> <span m="2049710">for
  non-linear</span> <span m="2049960">differential equations,</span> <span m="2051400">you''re</span>
  <span m="2051570">going</span> <span m="2051690">to</span> <span m="2051820">see</span>
  <span m="2051929">very</span> <span m="2052619">soon</span> <span m="2052999">that</span>
  <span m="2053380">explicit</span> <span m="2053730">schemes</span> <span m="2054555">are</span>
  <span m="2055030">a</span> <span m="2055400">lot easier</span> <span m="2055550">to</span>
  <span m="2056080">implement</span> <span m="2056719">than</span> <span m="2057719">implicit</span>
  <span m="2057889">schemes.</span></p><p><span m="2059440">And,</span> <span m="2060800">for
  example,</span> <span m="2062739">is</span> <span m="2063070">great</span> <span
  m="2063566">because</span> <span m="2064560">it</span> <span m="2064750">combines</span>
  <span m="2064765">the</span> <span m="2064780">advantage</span> <span m="2065150">of</span>
  <span m="2065615">forward Euler</span> <span m="2066080">and</span> <span m="2066705">midpoint.</span>
  <span m="2068980">Why?</span> <span m="2071020">Because</span> <span m="2072409">as</span>
  <span m="2072750">long</span> <span m="2073340">as</span> <span m="2073820">my</span>
  <span m="2075320">lambda</span> <span m="2075880">has</span> <span m="2076139">a</span>
  <span m="2076969">non-positive</span> <span m="2079380">real</span> <span m="2079650">part,</span>
  <span m="2082770">as</span> <span m="2083095">long</span> <span m="2083420">as</span>
  <span m="2083760">I make</span> <span m="2084120">delta</span> <span m="2084480">t</span>
  <span m="2084920">small enough,</span> <span m="2086030">I''m</span> <span m="2086930">going
  to</span> <span m="2087380">get</span> <span m="2087830">into the stability region.</span></p><p><span
  m="2089639">Forward Euler</span> <span m="2090330">requires</span> <span m="2090820">me</span>
  <span m="2090989">to have</span> <span m="2091179">a</span> <span m="2091444">negative</span>
  <span m="2092280">real</span> <span m="2094010">part.</span> <span m="2094590">Midpoint</span>
  <span m="2094730">requires</span> <span m="2094780">me to</span> <span m="2094830">have</span>
  <span m="2095199">a</span> <span m="2095489">zero</span> <span m="2096000">real</span>
  <span m="2096170">part.</span> <span m="2097510">[INAUDIBLE]</span> <span m="2097965">requires</span>
  <span m="2098420">me</span> <span m="2098875">to</span> <span m="2099330">have</span>
  <span m="2099790">either</span> <span m="2100220">0</span> <span m="2100700">or</span>
  <span m="2101470">negative</span> <span m="2101890">real</span> <span m="2102110">part.</span>
  <span m="2103350">And</span> <span m="2103550">I</span> <span m="2103630">can</span>
  <span m="2103830">make</span> <span m="2104080">delta t</span> <span m="2104470">small
  enough.</span> <span m="2104650">It</span> <span m="2105000">is</span> <span m="2105476">going
  to work.</span> <span m="2109284">All</span> <span m="2109760">right.</span> <span
  m="2110750">Questions?</span> <span m="2114220">Yeah?</span></p><p><span m="2116000">AUDIENCE:
  [INAUDIBLE]</span></p><p>&nbsp;</p><p><span m="2138000">PROFESSOR: Eigenvalue</span>
  <span m="2138710">stability</span> <span m="2142070">concerns</span> <span m="2142590">about</span>
  <span m="2143780">an</span> <span m="2143920">equation</span> <span m="2144580">that</span>
  <span m="2144750">is</span> <span m="2144990">dx dt</span> <span m="2146560">equal
  to</span> <span m="2146937">lambda</span> <span m="2147314">x.</span> <span m="2148500">We</span>
  <span m="2148640">are</span> <span m="2148690">looking</span> <span m="2149020">at,</span>
  <span m="2149480">if</span> <span m="2149690">I</span> <span m="2149880">apply</span>
  <span m="2150860">the</span> <span m="2151030">scheme,</span> <span m="2152420">we</span>
  <span m="2153010">[? sub ?]</span> <span m="2153430">delta t</span> <span m="2153580">to</span>
  <span m="2153840">this</span> <span m="2154100">equation.</span> <span m="2156250">Am</span>
  <span m="2156470">I</span> <span m="2156560">going</span> <span m="2156720">to</span>
  <span m="2156780">get</span> <span m="2156940">a</span> <span m="2157080">growing</span>
  <span m="2157430">solution,</span> <span m="2158180">or</span> <span m="2158370">I''m</span>
  <span m="2158660">going</span> <span m="2158800">to</span> <span m="2158860">get</span>
  <span m="2159030">a</span> <span m="2159180">stable</span> <span m="2159340">solution?</span></p><p><span
  m="2163340">AUDIENCE: Is</span> <span m="2163840">there</span> <span m="2164340">a</span>
  <span m="2164825">way</span> <span m="2165310">[INAUDIBLE]?</span></p><p><span m="2179190">PROFESSOR:
  The</span> <span m="2179620">stability</span> <span m="2180080">region</span> <span
  m="2180340">is</span> <span m="2180600">different</span> <span m="2180940">for each</span>
  <span m="2181714">[INAUDIBLE].</span></p><p><span m="2182101">AUDIENCE: OK.</span></p><p><span
  m="2182490">PROFESSOR: So</span> <span m="2182560">you</span> <span m="2182720">have</span>
  <span m="2182980">to--</span> <span m="2183726">yeah,</span> <span m="2184202">it''s</span>
  <span m="2184680">separate</span> <span m="2185110">from</span> <span m="2185410">the</span>
  <span m="2185640">[INAUDIBLE]</span> <span m="2186068">solution.</span> <span m="2186924">For</span>
  <span m="2187780">each</span> <span m="2188210">combination</span> <span m="2188820">of</span>
  <span m="2189030">scheme</span> <span m="2190112">and</span> <span m="2190936">lambda</span>
  <span m="2191530">delta</span> <span m="2191972">t,</span> <span m="2193740">you</span>
  <span m="2193890">have</span> <span m="2194130">an</span> <span m="2194280">answer</span>
  <span m="2194620">of yes</span> <span m="2194890">or</span> <span m="2195010">no.</span></p><p><span
  m="2197250">AUDIENCE: [INAUDIBLE]</span> <span m="2200220">eigenvalue.</span> <span
  m="2201210">[INAUDIBLE]</span> <span m="2203685">eigenvalue.</span> <span m="2204675">[INAUDIBLE]</span>
  <span m="2209130">eigenvalue.</span> <span m="2210615">[INAUDIBLE]</span></p><p>&nbsp;</p><p><span
  m="2251150">PROFESSOR: Yes.</span></p><p><span m="2251680">AUDIENCE: [INAUDIBLE]</span>
  <span m="2256000">and</span> <span m="2256150">then</span> <span m="2256700">you</span>
  <span m="2257490">linearize</span> <span m="2257755">it. But</span> <span m="2258020">because
  of</span> <span m="2258090">your</span> <span m="2259400">error</span> <span m="2260323">[INAUDIBLE].</span>
  <span m="2263780">This</span> <span m="2263930">sort</span> <span m="2264410">of</span>
  <span m="2264887">method</span> <span m="2266320">[INAUDIBLE].</span></p><p><span
  m="2278840">PROFESSOR: I</span> <span m="2278960">don''t</span> <span m="2279140">have</span>
  <span m="2279360">a</span> <span m="2280060">definite</span> <span m="2280150">answer
  to</span> <span m="2280320">that,</span> <span m="2280650">but</span> <span m="2281644">it''s</span>
  <span m="2282141">possible.</span> <span m="2282640">And</span> <span m="2283100">what</span>
  <span m="2283480">I</span> <span m="2283970">want</span> <span m="2284180">to</span>
  <span m="2284270">emphasize</span> <span m="2284860">is</span> <span m="2284990">that,</span>
  <span m="2285740">if</span> <span m="2285980">you</span> <span m="2286110">linearize</span>
  <span m="2286160">the</span> <span m="2286640">equation,</span> <span m="2287730">and</span>
  <span m="2288190">eigenvalue</span> <span m="2289160">stability</span> <span m="2289883">shows</span>
  <span m="2290306">that</span> <span m="2290730">it</span> <span m="2290880">is</span>
  <span m="2291210">unstable,</span> <span m="2292980">then</span> <span m="2293065">it''s</span>
  <span m="2293540">very</span> <span m="2293760">likely,</span> <span m="2294210">when</span>
  <span m="2294970">you</span> <span m="2295180">apply</span> <span m="2295370">to</span>
  <span m="2295590">your</span> <span m="2296066">[? normal ?]</span> <span m="2296542">equation,</span>
  <span m="2297018">that</span> <span m="2297494">it''s going to</span> <span m="2297970">be</span>
  <span m="2298450">unstable.</span></p><p><span m="2299190">So</span> <span m="2299750">eigenvalue</span>
  <span m="2299930">stability,</span> <span m="2300470">I would</span> <span m="2301258">say</span>
  <span m="2304360">before</span> <span m="2304640">you</span> <span m="2305200">apply
  the</span> <span m="2305650">scheme</span> <span m="2306100">to</span> <span m="2306590">differential</span>
  <span m="2307040">equation,</span> <span m="2308550">it''s</span> <span m="2309490">a</span>
  <span m="2309990">good</span> <span m="2310130">idea</span> <span m="2310560">to</span>
  <span m="2310640">check</span> <span m="2310940">eigenvalue</span> <span m="2311325">stability.</span>
  <span m="2312480">And</span> <span m="2312980">this</span> <span m="2313150">also</span>
  <span m="2313460">gives</span> <span m="2313700">you</span> <span m="2313820">a</span>
  <span m="2314060">guidance</span> <span m="2314560">of</span> <span m="2315000">when</span>
  <span m="2315300">you</span> <span m="2315410">see</span> <span m="2315700">something</span>
  <span m="2316465">being</span> <span m="2317740">unstable.</span> <span m="2319020">Is
  it</span> <span m="2319580">because</span> <span m="2319870">you</span> <span m="2319950">are</span>
  <span m="2320160">using</span> <span m="2320480">the</span> <span m="2320560">wrong</span>
  <span m="2320910">scheme?</span> <span m="2322200">Or</span> <span m="2322380">is</span>
  <span m="2322480">it</span> <span m="2322550">because</span> <span m="2322940">you</span>
  <span m="2323060">have</span> <span m="2323350">a</span> <span m="2323510">too</span>
  <span m="2323760">large</span> <span m="2323890">[INAUDIBLE].</span> <span m="2325854">Right?</span>
  <span m="2326840">You</span> <span m="2327784">can</span> <span m="2328248">take</span>
  <span m="2328712">a</span> <span m="2329176">look at these</span> <span m="2329640">eigenvalues</span>
  <span m="2330104">and</span> <span m="2330568">figure out</span> <span m="2331500">which</span>
  <span m="2331740">case</span> <span m="2332070">it is.</span> <span m="2336490">Any</span>
  <span m="2336770">other</span> <span m="2336860">questions?</span></p><p><span m="2340100">OK,</span>
  <span m="2340410">let</span> <span m="2341300">me</span> <span m="2341390">give</span>
  <span m="2341620">you</span> <span m="2342533">a</span> <span m="2343016">challenge.</span>
  <span m="2344950">Now,</span> <span m="2345250">if</span> <span m="2345480">I</span>
  <span m="2345935">get</span> <span m="2346390">a</span> <span m="2347300">couple</span>
  <span m="2348528">differential</span> <span m="2349012">equations</span> <span m="2350464">[INAUDIBLE]</span>
  <span m="2354820">where</span> <span m="2355304">y is</span> <span m="2355788">equal</span>
  <span m="2356272">to</span> <span m="2356756">x,</span> <span m="2357250">where</span>
  <span m="2357500">x</span> <span m="2357760">can</span> <span m="2358471">range</span>
  <span m="2358922">all the</span> <span m="2359373">way</span> <span m="2359824">from
  0</span> <span m="2360275">to</span> <span m="2360726">t.</span> <span m="2361180">For</span>
  <span m="2361320">what</span> <span m="2361670">x</span> <span m="2362110">[INAUDIBLE]</span>
  <span m="2362220">delta</span> <span m="2362340">t</span> <span m="2363050">is</span>
  <span m="2364250">forward Euler</span> <span m="2364320">table.</span> <span m="2365760">For</span>
  <span m="2366100">what</span> <span m="2366390">values</span> <span m="2366780">of</span>
  <span m="2366890">[INAUDIBLE]</span> <span m="2367750">is</span> <span m="2369040">backward</span>
  <span m="2369340">Euler</span> <span m="2369796">table.</span> <span m="2370252">And
  for what</span> <span m="2370708">value of</span> <span m="2371164">epsilon</span>
  <span m="2371620">is it midpoint stable?</span></p><p><span m="2372210">I mean,</span>
  <span m="2372330">not</span> <span m="2372620">for</span> <span m="2373036">epsilon,</span>
  <span m="2373870">but</span> <span m="2374550">for</span> <span m="2374765">what</span>
  <span m="2374980">combination</span> <span m="2375410">of</span> <span m="2375840">epsilon</span>
  <span m="2376270">and</span> <span m="2376700">delta t is</span> <span m="2377000">each</span>
  <span m="2377230">of</span> <span m="2377360">these</span> <span m="2377450">[INAUDIBLE].</span>
  <span m="2378584">Form groups of</span> <span m="2379006">two or</span> <span m="2379600">three,</span>
  <span m="2379990">and</span> <span m="2380423">figure</span> <span m="2381290">this
  out.</span> <span m="2383530">All right.</span></p><p><span m="2384910">A</span>
  <span m="2385400">lot</span> <span m="2385680">of</span> <span m="2385800">you</span>
  <span m="2386000">have</span> <span m="2386250">got</span> <span m="2386950">the</span>
  <span m="2387210">answer,</span> <span m="2388020">or</span> <span m="2388090">almost</span>
  <span m="2388970">get</span> <span m="2389160">the</span> <span m="2389260">answer,</span>
  <span m="2389930">and</span> <span m="2390530">let</span> <span m="2390953">me</span>
  <span m="2393180">do</span> <span m="2393350">it</span> <span m="2393630">here</span>
  <span m="2394090">to</span> <span m="2394460">make</span> <span m="2394680">sure</span>
  <span m="2394810">everybody</span> <span m="2395330">is</span> <span m="2395630">on</span>
  <span m="2395790">the</span> <span m="2395870">same</span> <span m="2396120">page.</span>
  <span m="2398080">First</span> <span m="2398200">of</span> <span m="2398350">all,</span>
  <span m="2398740">the</span> <span m="2398840">first</span> <span m="2399150">step</span>
  <span m="2399440">is</span> <span m="2399610">to</span> <span m="2399760">write</span>
  <span m="2400080">the</span> <span m="2400160">differential</span> <span m="2400710">equation</span>
  <span m="2401300">into</span> <span m="2401650">a</span> <span m="2401720">matrix</span>
  <span m="2402140">form.</span> <span m="2406660">The</span> <span m="2406770">du
  dt</span> <span m="2407610">of</span> <span m="2407870">x</span> <span m="2408120">and</span>
  <span m="2408300">y,</span> <span m="2409240">let''s</span> <span m="2409550">write</span>
  <span m="2409880">it</span> <span m="2410950">in</span> <span m="2411210">a</span>
  <span m="2411300">similar</span> <span m="2411880">way</span> <span m="2412230">as</span>
  <span m="2412260">du dt</span> <span m="2412730">equals</span> <span m="2413490">lambda</span>
  <span m="2413760">u.</span> <span m="2414545">But</span> <span m="2415020">here,</span>
  <span m="2415390">the</span> <span m="2415460">lambda</span> <span m="2415870">is</span>
  <span m="2416010">no</span> <span m="2416160">longer</span> <span m="2416430">a</span>
  <span m="2416480">number.</span> <span m="2416980">It</span> <span m="2417150">is</span>
  <span m="2417350">a</span> <span m="2417720">matrix.</span></p><p><span m="2420560">And</span>
  <span m="2420680">what</span> <span m="2420920">is</span> <span m="2421110">the</span>
  <span m="2421190">matrix?</span> <span m="2423180">Just</span> <span m="2423350">fill</span>
  <span m="2423580">in</span> <span m="2423680">the</span> <span m="2423750">blanks.</span>
  <span m="2425180">dx dt</span> <span m="2425830">minus</span> <span m="2426240">y</span>
  <span m="2426590">minus</span> <span m="2426960">epsilon</span> <span m="2427290">x.</span>
  <span m="2427680">So</span> <span m="2427900">minus</span> <span m="2428310">epsilon</span>
  <span m="2428620">x</span> <span m="2429450">minus</span> <span m="2429810">1y.</span>
  <span m="2431490">dy dt</span> <span m="2431870">equal</span> <span m="2432110">to</span>
  <span m="2432470">x,</span> <span m="2432780">so</span> <span m="2433120">1x</span>
  <span m="2433930">plus</span> <span m="2434740">0y.</span></p><p><span m="2437840">OK,</span>
  <span m="2438180">so</span> <span m="2438340">I</span> <span m="2438440">get</span>
  <span m="2438650">a</span> <span m="2438700">matrix</span> <span m="2439330">here.</span>
  <span m="2440300">And</span> <span m="2440510">how</span> <span m="2440740">do</span>
  <span m="2440890">I</span> <span m="2440980">go</span> <span m="2441230">from</span>
  <span m="2441480">the</span> <span m="2441550">matrix</span> <span m="2442110">to</span>
  <span m="2442290">eigenvalue</span> <span m="2442780">stability?</span> <span m="2447190">Take</span>
  <span m="2447480">the</span> <span m="2447600">eigenvalue.</span> <span m="2449710">Take</span>
  <span m="2449950">the</span> <span m="2450050">eigenvalue.</span> <span m="2450920">So</span>
  <span m="2451240">the</span> <span m="2451400">eigenvalue</span> <span m="2452040">of</span>
  <span m="2452190">this</span> <span m="2452340">matrix,</span> <span m="2453440">and</span>
  <span m="2455170">I</span> <span m="2455330">may</span> <span m="2455520">be</span>
  <span m="2455680">lazy,</span> <span m="2456130">so</span> <span m="2456420">let</span>
  <span m="2456580">me</span> <span m="2456690">do</span> <span m="2456860">it</span>
  <span m="2457342">in</span> <span m="2457824">Matlab.</span></p><p><span m="2458788">[LAUGHTER]</span></p><p><span
  m="2460240">OK?</span> <span m="2464060">Yeah,</span> <span m="2464820">so</span>
  <span m="2465100">for</span> <span m="2465330">this</span> <span m="2465590">2 by
  2</span> <span m="2466120">matrix,</span> <span m="2466590">you</span> <span m="2466700">can</span>
  <span m="2466940">do</span> <span m="2467130">it</span> <span m="2467330">by</span>
  <span m="2467570">hand.</span> <span m="2467940">But</span> <span m="2468080">if</span>
  <span m="2468470">you</span> <span m="2468650">get</span> <span m="2468870">a</span>
  <span m="2468980">large</span> <span m="2469290">matrix,</span> <span m="2469600">what
  do</span> <span m="2469760">you</span> <span m="2470250">do?</span> <span m="2475750">Let</span>
  <span m="2476290">me</span> <span m="2476400">do</span> <span m="2476560">the</span>
  <span m="2476670">bad</span> <span m="2476890">example.</span></p><p><span m="2477923">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="2484210">PROFESSOR: OK,</span> <span m="2484500">I''m</span>
  <span m="2484660">just</span> <span m="2484850">going</span> <span m="2485000">to</span>
  <span m="2485070">make</span> <span m="2485370">epsilon</span> <span m="2486400">go</span>
  <span m="2486680">all the way</span> <span m="2486930">from</span> <span m="2487240">0</span>
  <span m="2487500">to</span> <span m="2487915">10.</span> <span m="2489160">So</span>
  <span m="2489465">linked space</span> <span m="2490156">is</span> <span m="2490930">putting
  a</span> <span m="2491120">bunch</span> <span m="2491400">of</span> <span m="2491480">epsilon.</span>
  <span m="2493672">And</span> <span m="2494150">the</span> <span m="2494230">matrix</span>
  <span m="2494740">here</span> <span m="2496360">is</span> <span m="2497040">going</span>
  <span m="2497230">to</span> <span m="2497320">be</span> <span m="2497500">like</span>
  <span m="2497750">this.</span> <span m="2498300">So</span> <span m="2498450">let</span>
  <span m="2499140">me</span> <span m="2499260">do</span> <span m="2499620">this.</span>
  <span m="2500130">Let</span> <span m="2500485">me</span> <span m="2501310">put</span>
  <span m="2506110">e</span> <span m="2506390">to</span> <span m="2506520">be</span>
  <span m="2507020">a</span> <span m="2507160">symbolic</span> <span m="2507640">variable.</span>
  <span m="2508910">And</span> <span m="2509330">the</span> <span m="2509440">matrix</span>
  <span m="2510270">is</span> <span m="2511320">what?</span> <span m="2512310">Minus</span>
  <span m="2512770">e</span> <span m="2514070">minus</span> <span m="2514440">1,</span>
  <span m="2515660">1,</span> <span m="2516170">0.</span> <span m="2517080">So</span>
  <span m="2517750">that''s</span> <span m="2518510">what</span> <span m="2518640">the</span>
  <span m="2518730">matrix</span> <span m="2519120">is.</span> <span m="2519840">And</span>
  <span m="2520070">e</span> <span m="2520400">means</span> <span m="2520730">epsilon.</span></p><p><span
  m="2522000">And</span> <span m="2522550">you</span> <span m="2522710">can</span>
  <span m="2523000">do</span> <span m="2523250">the</span> <span m="2523410">eigenvalue</span>
  <span m="2524320">of</span> <span m="2525000">this</span> <span m="2525470">matrix.</span>
  <span m="2526650">It</span> <span m="2526810">gives</span> <span m="2527120">you</span>
  <span m="2527470">the</span> <span m="2527540">formula,</span> <span m="2528020">which</span>
  <span m="2528410">you</span> <span m="2528600">guys</span> <span m="2529180">have</span>
  <span m="2530080">figured</span> <span m="2530350">out.</span> <span m="2531090">Minus</span>
  <span m="2531790">epsilon</span> <span m="2532540">over</span> <span m="2532800">2</span>
  <span m="2533850">plus</span> <span m="2534340">or</span> <span m="2534470">minus</span>
  <span m="2536050">the</span> <span m="2536150">square</span> <span m="2536600">root</span>
  <span m="2536990">of--</span> <span m="2538000">I mean, to</span> <span m="2538250">the</span>
  <span m="2538360">1/2</span> <span m="2538650">power</span> <span m="2538950">is</span>
  <span m="2539090">basically</span> <span m="2539380">square</span> <span m="2539850">root,</span>
  <span m="2540050">right,</span> <span m="2541810">of</span> <span m="2542180">this</span>
  <span m="2542280">thing.</span></p><p><span m="2543770">So</span> <span m="2543930">let</span>
  <span m="2544140">me</span> <span m="2545160">just</span> <span m="2546600">again</span>
  <span m="2547490">say,</span> <span m="2548750">epsilon</span> <span m="2549143">e</span>
  <span m="2549536">is</span> <span m="2549930">equal</span> <span m="2550380">to</span>
  <span m="2550950">linked space</span> <span m="2552920">of</span> <span m="2553320">0,</span>
  <span m="2553770">10,</span> <span m="2554025">100.</span> <span m="2555560">And</span>
  <span m="2556090">I''m</span> <span m="2556300">going</span> <span m="2556450">to</span>
  <span m="2556550">say</span> <span m="2556800">lambda</span> <span m="2557070">1,</span>
  <span m="2559090">the</span> <span m="2559190">first</span> <span m="2559480">eigenvalue</span>
  <span m="2560250">is--</span> <span m="2561320">I''m just going to</span> <span
  m="2561540">copy</span> <span m="2562320">the</span> <span m="2562400">formula</span>
  <span m="2563010">here</span> <span m="2563300">and</span> <span m="2563630">paste</span>
  <span m="2563900">it.</span> <span m="2567700">And</span> <span m="2567990">I</span>
  <span m="2568060">need</span> <span m="2568280">to</span> <span m="2568450">convert</span>
  <span m="2569250">the</span> <span m="2569380">products</span> <span m="2570040">into</span>
  <span m="2570530">dot</span> <span m="2571100">and</span> <span m="2572940">exponenting</span>
  <span m="2573660">to</span> <span m="2573770">dot</span> <span m="2574400">exponential.</span></p><p><span
  m="2575540">And</span> <span m="2577120">everything</span> <span m="2577550">else</span>
  <span m="2577780">is</span> <span m="2577910">going</span> <span m="2578040">to</span>
  <span m="2578100">be</span> <span m="2578210">fine.</span> <span m="2579490">I''m</span>
  <span m="2579680">going</span> <span m="2579830">to</span> <span m="2580273">also</span>
  <span m="2581000">look</span> <span m="2581240">at</span> <span m="2581390">the</span>
  <span m="2581460">second</span> <span m="2587470">eigenvalue.</span> <span m="2589770">I''m
  going to</span> <span m="2589930">paste</span> <span m="2590040">it</span> <span
  m="2590775">and</span> <span m="2591220">also</span> <span m="2591610">do</span>
  <span m="2591800">the</span> <span m="2592020">dot</span> <span m="2592360">product</span>
  <span m="2593060">and</span> <span m="2593840">dot</span> <span m="2594060">explanation.</span>
  <span m="2595520">OK,</span> <span m="2596230">I</span> <span m="2596410">have</span>
  <span m="2596790">L1</span> <span m="2597045">and</span> <span m="2597300">L2.</span>
  <span m="2597890">Let</span> <span m="2598060">me</span> <span m="2598170">plot</span>
  <span m="2598580">them.</span></p><p><span m="2601840">I''m</span> <span m="2602020">going</span>
  <span m="2602210">to</span> <span m="2602570">plot</span> <span m="2602900">a</span>
  <span m="2603540">line</span> <span m="2603860">and</span> <span m="2604040">dot.</span>
  <span m="2604680">So</span> <span m="2604880">what</span> <span m="2605260">you</span>
  <span m="2605680">get is,</span> <span m="2606110">in</span> <span m="2606290">the</span>
  <span m="2606440">complex</span> <span m="2606710">plan,</span> <span m="2607250">let</span>
  <span m="2607410">me</span> <span m="2607610">do</span> <span m="2607810">x</span>
  <span m="2608160">is</span> <span m="2608390">equal--</span> <span m="2610710">in</span>
  <span m="2610870">a</span> <span m="2610910">complex</span> <span m="2611380">plan,</span>
  <span m="2611620">I''m</span> <span m="2611820">plotting</span> <span m="2613280">the</span>
  <span m="2613660">trajectory</span> <span m="2614440">of</span> <span m="2614770">lambda,</span>
  <span m="2615300">of</span> <span m="2615660">lambda</span> <span m="2615900">1,</span>
  <span m="2616555">as</span> <span m="2616880">my</span> <span m="2617050">epsilon</span>
  <span m="2617530">goes</span> <span m="2617730">from</span> <span m="2618040">0</span>
  <span m="2619534">to</span> <span m="2620530">10.</span> <span m="2622530">I''m</span>
  <span m="2622750">going</span> <span m="2622900">to</span> <span m="2623170">say</span>
  <span m="2623510">hold</span> <span m="2623860">on</span> <span m="2625630">and</span>
  <span m="2626950">plot</span> <span m="2628150">the</span> <span m="2628250">evolution</span>
  <span m="2628930">of</span> <span m="2629200">lambda</span> <span m="2629580">2.</span></p><p><span
  m="2632540">Actually,</span> <span m="2632860">I</span> <span m="2632930">want</span>
  <span m="2633140">to</span> <span m="2633200">plot it in</span> <span m="2633495">a</span>
  <span m="2633790">different</span> <span m="2634192">color.</span> <span m="2636160">So</span>
  <span m="2636360">you</span> <span m="2636470">get</span> <span m="2636910">a</span>
  <span m="2637348">[INAUDIBLE]</span> <span m="2639980">of</span> <span m="2640393">lambda</span>
  <span m="2640806">1,</span> <span m="2641220">but</span> <span m="2641720">this</span>
  <span m="2642160">way,</span> <span m="2643074">[INAUDIBLE].</span> <span m="2644445">And</span>
  <span m="2644902">remember,</span> <span m="2645359">this is, in</span> <span m="2645816">the
  context</span> <span m="2646280">[INAUDIBLE],</span> <span m="2646700">the</span>
  <span m="2647624">two</span> <span m="2648086">eigenvalues,</span> <span m="2649940">right?</span>
  <span m="2651350">OK,</span> <span m="2651720">anybody</span> <span m="2652260">remind</span>
  <span m="2652700">me</span> <span m="2652900">what</span> <span m="2653140">is</span>
  <span m="2653320">the</span> <span m="2653440">stability</span> <span m="2653990">region</span>
  <span m="2654350">of</span> <span m="2654550">forward Euler?</span></p><p><span
  m="2655742">AUDIENCE: [INAUDIBLE]</span></p><p><span m="2659390">PROFESSOR: Yeah,
  so</span> <span m="2659960">a</span> <span m="2660170">circle</span> <span m="2660530">around</span>
  <span m="2660800">negative</span> <span m="2661170">1.</span> <span m="2663115">So</span>
  <span m="2663580">a</span> <span m="2664510">circle</span> <span m="2664980">around</span>
  <span m="2665650">negative</span> <span m="2666070">1,</span> <span m="2666910">right?</span>
  <span m="2668150">Going</span> <span m="2668490">to</span> <span m="2668650">the</span>
  <span m="2668750">Matlab</span> <span m="2669110">plot,</span> <span m="2671060">it''s
  a circle around</span> <span m="2671800">here.</span> <span m="2674620">But</span>
  <span m="2674800">remember,</span> <span m="2675940">the</span> <span m="2676200">stability</span>
  <span m="2676780">region</span> <span m="2677486">is</span> <span m="2677922">a</span>
  <span m="2678360">stability</span> <span m="2678700">region</span> <span m="2678990">of</span>
  <span m="2679360">what?</span> <span m="2680566">Of lambda</span> <span m="2681004">t.</span>
  <span m="2681880">Lambda</span> <span m="2682318">times</span> <span m="2682760">t.</span>
  <span m="2683890">Well</span> <span m="2684180">here,</span> <span m="2684630">I''m</span>
  <span m="2684820">just</span> <span m="2685030">plotting</span> <span m="2685470">the</span>
  <span m="2685560">lambda.</span> <span m="2686988">So what does that</span> <span
  m="2687464">mean?</span></p><p><span m="2689368">If</span> <span m="2689850">I</span>
  <span m="2690250">have,</span> <span m="2691015">let''s</span> <span m="2691280">see,</span>
  <span m="2691560">epsilon</span> <span m="2691840">equal</span> <span m="2692230">to</span>
  <span m="2692620">10,</span> <span m="2693400">one</span> <span m="2693630">of</span>
  <span m="2693740">my</span> <span m="2693920">eigenvalues</span> <span m="2694370">is</span>
  <span m="2694530">here.</span> <span m="2695900">Is</span> <span m="2696140">there</span>
  <span m="2696280">any</span> <span m="2696670">hope?</span> <span m="2697360">I
  mean,</span> <span m="2697780">the</span> <span m="2698200">[INAUDIBLE].</span>
  <span m="2699040">Is</span> <span m="2699230">there</span> <span m="2699450">any</span>
  <span m="2699640">hope</span> <span m="2700300">of</span> <span m="2700610">making</span>
  <span m="2700930">forward Euler</span> <span m="2701530">stable?</span></p><p><span
  m="2702496">AUDIENCE: [INAUDIBLE]</span></p><p><span m="2704430">PROFESSOR: How?</span></p><p><span
  m="2705783">AUDIENCE: [INAUDIBLE]</span></p><p><span m="2708040">PROFESSOR: By</span>
  <span m="2708410">a</span> <span m="2708690">big</span> <span m="2708840">delta</span>
  <span m="2709010">t</span> <span m="2709315">equal</span> <span m="2709620">to</span>
  <span m="2709650">how</span> <span m="2709960">much?</span> <span m="2711930">Or</span>
  <span m="2712230">a small</span> <span m="2712440">delta</span> <span m="2712550">t?</span>
  <span m="2714140">A small</span> <span m="2714420">delta</span> <span m="2714510">t</span>
  <span m="2714800">equal</span> <span m="2715200">to</span> <span m="2715300">how</span>
  <span m="2715670">much?</span> <span m="2717122">Huh?</span></p><p><span m="2720510">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="2722940">PROFESSOR: [INAUDIBLE]</span></p><p><span
  m="2727272">AUDIENCE: [INAUDIBLE]</span></p><p><span m="2729950">PROFESSOR: As long
  as</span> <span m="2730440">I</span> <span m="2730660">can</span> <span m="2730770">make</span>
  <span m="2731130">this</span> <span m="2731490">point</span> <span m="2731690">with</span>
  <span m="2732480">being</span> <span m="2733040">the</span> <span m="2733240">[INAUDIBLE],</span>
  <span m="2735280">where</span> <span m="2735890">the</span> <span m="2736160">[INAUDIBLE]</span>
  <span m="2736450">here</span> <span m="2736670">is</span> <span m="2737020">minus</span>
  <span m="2737260">2,</span> <span m="2737410">right?</span> <span m="2738150">So</span>
  <span m="2738450">as</span> <span m="2738800">long as  I can</span> <span m="2738990">have</span>
  <span m="2739350">a</span> <span m="2739440">delta t</span> <span m="2739640">that</span>
  <span m="2740210">is</span> <span m="2740520">less</span> <span m="2740790">than</span>
  <span m="2741060">1, 2,</span> <span m="2742116">I can</span> <span m="2743068">make</span>
  <span m="2744020">forward Euler</span> <span m="2744940">stable.</span> <span m="2745950">Any</span>
  <span m="2746150">questions on</span> <span m="2746650">that?</span></p><p><span
  m="2747940">AUDIENCE: [INAUDIBLE]</span></p><p><span m="2756230">PROFESSOR: Yeah,</span>
  <span m="2756480">right,</span> <span m="2756780">sure.</span></p><p><span m="2763952">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="2775176">PROFESSOR: OK,</span> <span m="2776010">you</span>
  <span m="2776140">have</span> <span m="2776500">beat</span> <span m="2776980">me.</span></p><p><span
  m="2778246">AUDIENCE: [INAUDIBLE]</span> <span m="2790340">that</span> <span m="2790990">lambda</span>
  <span m="2791670">[INAUDIBLE].</span></p><p><span m="2795770">PROFESSOR: Yeah,</span>
  <span m="2796190">right.</span> <span m="2797240">OK,</span> <span m="2797600">thank</span>
  <span m="2797810">you.</span></p><p><span m="2798960">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="2803610">PROFESSOR: Right.</span> <span m="2804075">So we have to</span> <span
  m="2804540">make</span> <span m="2804810">[INAUDIBLE]</span> <span m="2813590">stability</span>
  <span m="2813880">region.</span> <span m="2816717">So,</span> <span m="2817204">question?</span>
  <span m="2819640">OK.</span> <span m="2821990">And</span> <span m="2822320">so</span>
  <span m="2822580">we</span> <span m="2822840">can see,</span> <span m="2823210">when</span>
  <span m="2826120">epsilon</span> <span m="2826150">is</span> <span m="2826270">very</span>
  <span m="2826370">large,</span> <span m="2826670">it''s</span> <span m="2827155">difficult</span>
  <span m="2827640">to-- you</span> <span m="2827800">have</span> <span m="2827980">to</span>
  <span m="2828080">have</span> <span m="2828220">a</span> <span m="2828280">small</span>
  <span m="2828720">delta</span> <span m="2829161">t</span> <span m="2829602">to</span>
  <span m="2830043">shrink</span> <span m="2830484">it</span> <span m="2830925">[INAUDIBLE].</span>
  <span m="2831370">Another</span> <span m="2831810">case</span> <span m="2832250">is
  when</span> <span m="2832750">epsilon</span> <span m="2833570">is</span> <span m="2833650">very</span>
  <span m="2833870">small,</span> <span m="2834780">actually</span> <span m="2835260">adds</span>
  <span m="2835670">epsilon</span> <span m="2835940">equal to</span> <span m="2835970">zero.</span></p><p><span
  m="2836830">I</span> <span m="2836980">get</span> <span m="2837760">two</span> <span
  m="2838450">eigenvalues</span> <span m="2838710">equal</span> <span m="2839530">to</span>
  <span m="2840350">[INAUDIBLE].</span> <span m="2843800">How</span> <span m="2843940">can</span>
  <span m="2844160">I</span> <span m="2844260">make</span> <span m="2845440">the</span>
  <span m="2845540">case</span> <span m="2845930">stable</span> <span m="2846060">for</span>
  <span m="2846340">forward Euler?</span></p><p><span m="2854450">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="2856120">PROFESSOR: I</span> <span m="2856300">can</span> <span m="2856470">never</span>
  <span m="2856870">make</span> <span m="2857140">forward Euler</span> <span m="2857380">stable.</span>
  <span m="2859010">I</span> <span m="2859190">can</span> <span m="2859400">make</span>
  <span m="2859640">delta</span> <span m="2859780">t</span> <span m="2860140">goes</span>
  <span m="2860500">to</span> <span m="2860570">very,</span> <span m="2860990">very</span>
  <span m="2861120">small,</span> <span m="2861560">[INAUDIBLE]</span> <span m="2861950">shrink</span>
  <span m="2863180">over</span> <span m="2863410">here.</span> <span m="2863600">But</span>
  <span m="2863740">they</span> <span m="2863840">are</span> <span m="2863890">still</span>
  <span m="2864380">on</span> <span m="2864640">the</span> <span m="2865270">[INAUDIBLE].</span>
  <span m="2867180">And</span> <span m="2867560">remember</span> <span m="2868010">forward
  Euler,</span> <span m="2872010">it</span> <span m="2872550">doesn''t</span> <span
  m="2873040">include</span> <span m="2874630">any point on the</span> <span m="2875020">imaginary</span>
  <span m="2875350">axis</span> <span m="2875610">other</span> <span m="2876087">than</span>
  <span m="2877041">0.</span></p><p><span m="2877520">So</span> <span m="2878620">when</span>
  <span m="2879360">1</span> <span m="2879740">epsilon</span> <span m="2880030">is</span>
  <span m="2880240">very</span> <span m="2880700">small,</span> <span m="2881030">it''s</span>
  <span m="2882290">impossible</span> <span m="2882740">to</span> <span m="2882830">make</span>
  <span m="2883010">forward Euler</span> <span m="2883550">stable.</span> <span m="2884170">And</span>
  <span m="2884390">when</span> <span m="2884730">epsilon</span> <span m="2885260">is</span>
  <span m="2885420">very</span> <span m="2885790">small,</span> <span m="2887580">it</span>
  <span m="2887830">takes</span> <span m="2888210">a</span> <span m="2888300">very,</span>
  <span m="2888810">very</span> <span m="2889000">small</span> <span m="2889300">delta</span>
  <span m="2889520">t</span> <span m="2890170">[INAUDIBLE].</span> <span m="2893752">So</span>
  <span m="2894250">when</span> <span m="2894930">a</span> <span m="2895060">system</span>
  <span m="2895540">is</span> <span m="2896660">[INAUDIBLE],</span> <span m="2900085">it''s</span>
  <span m="2901150">almost</span> <span m="2902060">pure</span> <span m="2902290">oscillation.</span>
  <span m="2904250">It</span> <span m="2904670">also</span> <span m="2905200">takes</span>
  <span m="2905800">a</span> <span m="2905970">lot</span> <span m="2906410">of</span>
  <span m="2906780">[INAUDIBLE]</span> <span m="2907735">for</span> <span m="2908050">very</span>
  <span m="2908230">small</span> <span m="2908380">delta</span> <span m="2908620">t</span>
  <span m="2908840">for</span> <span m="2908980">forward</span> <span m="2909220">Euler</span>
  <span m="2911775">to</span> <span m="2912470">accurately</span> <span m="2913940">resolve</span>
  <span m="2914170">its</span> <span m="2914745">behavior.</span> <span m="2915150">Yes?</span></p><p><span
  m="2915918">AUDIENCE: [INAUDIBLE]</span></p><p><span m="2923570">PROFESSOR: Good</span>
  <span m="2923830">question.</span> <span m="2924602">Does</span> <span m="2924990">both</span>
  <span m="2925320">Eigenvalues</span> <span m="2926070">need</span> <span m="2926310">to</span>
  <span m="2926420">be</span> <span m="2926600">in</span> <span m="2926690">the stability</span>
  <span m="2927100">region?</span></p><p><span m="2928684">AUDIENCE: [INAUDIBLE]</span></p><p>&nbsp;</p><p><span
  m="2950570">PROFESSOR: Yes.</span> <span m="2951270">Both</span> <span m="2951810">eigenvalues,</span>
  <span m="2951980">or</span> <span m="2952410">all of the</span> <span m="2952650">eigenvalues,</span>
  <span m="2953470">in this</span> <span m="2953930">case,</span> <span m="2954390">with</span>
  <span m="2954640">two</span> <span m="2955087">eigenvalues,</span> <span m="2955534">[INAUDIBLE]</span>
  <span m="2956430">all</span> <span m="2956760">of</span> <span m="2956860">the</span>
  <span m="2956990">eigenvalues</span> <span m="2957976">have</span> <span m="2958470">to</span>
  <span m="2958590">be</span> <span m="2958690">in</span> <span m="2958770">the</span>
  <span m="2958970">[INAUDIBLE]</span> <span m="2959280">region.</span> <span m="2961330">And</span>
  <span m="2962950">the</span> <span m="2963280">eigenvalues</span> <span m="2963970">of</span>
  <span m="2964050">a</span> <span m="2964140">matrix</span> <span m="2964700">doesn''t</span>
  <span m="2965180">always</span> <span m="2968178">conjugate</span> <span m="2968652">each
  other.</span> <span m="2969126">And in</span> <span m="2969600">this case,</span>
  <span m="2970550">[INAUDIBLE]</span> <span m="2971250">conjugate</span> <span m="2971630">each</span>
  <span m="2972030">other.</span> <span m="2972430">And</span> <span m="2973320">as</span>
  <span m="2973530">our</span> <span m="2973670">epsilon</span> <span m="2974480">[INAUDIBLE].</span>
  <span m="2981180">And</span> <span m="2981300">if</span> <span m="2981400">you</span>
  <span m="2981510">have</span> <span m="2981680">a</span> <span m="2981750">bigger</span>
  <span m="2982050">matrix,</span> <span m="2982430">that''s</span> <span m="2983414">even</span>
  <span m="2983898">more</span> <span m="2984140">[INAUDIBLE].</span></p><p><span
  m="2984866">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3037540">PROFESSOR: Right.</span>
  <span m="3038280">The</span> <span m="3038390">instability</span> <span m="3038820">analysis</span>
  <span m="3039250">of</span> <span m="3039510">the</span> <span m="3039935">analytical</span>
  <span m="3040810">system,</span> <span m="3042240">the</span> <span m="3042450">analytical</span>
  <span m="3042880">system</span> <span m="3044260">is</span> <span m="3044720">stable</span>
  <span m="3045180">for</span> <span m="3045660">the</span> <span m="3046115">whole</span>
  <span m="3046570">[INAUDIBLE].</span> <span m="3046820">So you are</span> <span
  m="3046930">looking</span> <span m="3047160">at</span> <span m="3047420">the most
  dangerous</span> <span m="3047870">[INAUDIBLE].</span></p><p><span m="3052670">Where</span>
  <span m="3052880">we</span> <span m="3053040">have</span> <span m="3053200">a</span>
  <span m="3053250">numerical</span> <span m="3053820">scheme,</span> <span m="3054210">the</span>
  <span m="3054700">most</span> <span m="3055080">dangerous</span> <span m="3055480">ones</span>
  <span m="3055800">are</span> <span m="3055930">not</span> <span m="3056260">necessarily</span>
  <span m="3057460">the</span> <span m="3057640">one</span> <span m="3057950">that</span>
  <span m="3058170">lies</span> <span m="3058480">towards</span> <span m="3058620">the</span>
  <span m="3058840">right.</span> <span m="3061060">It made be the</span> <span m="3061160">ones</span>
  <span m="3061470">that</span> <span m="3061720">lies</span> <span m="3062546">more</span>
  <span m="3062960">towards</span> <span m="3063275">the</span> <span m="3063590">left.</span>
  <span m="3064750">Or</span> <span m="3065055">most</span> <span m="3065360">[? low,
  ?]</span> <span m="3066290">most</span> <span m="3066660">dangerous,</span> <span
  m="3069410">of</span> <span m="3069650">the</span> <span m="3069770">stability</span>
  <span m="3070060">region.</span> <span m="3070720">They are</span> <span m="3070900">not</span>
  <span m="3071140">necessarily</span> <span m="3071600">the</span> <span m="3072030">ones</span>
  <span m="3072475">that</span> <span m="3072920">is</span> <span m="3073365">closest</span>
  <span m="3073810">to</span> <span m="3073930">the</span> <span m="3074530">imaginary</span>
  <span m="3074870">axis.</span></p><p><span m="3077370">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="3087500">PROFESSOR: Yeah.</span></p><p><span m="3089000">AUDIENCE: [INAUDIBLE]</span></p><p>&nbsp;</p><p><span
  m="3121304">PROFESSOR: Yeah,</span> <span m="3121796">for</span> <span m="3122288">nonlinear</span>
  <span m="3123030">problems,</span> <span m="3123763">sometimes</span> <span m="3124136">[?
  they are ?]</span> <span m="3125080">very</span> <span m="3125250">extremely</span>
  <span m="3125330">important</span> <span m="3126570">to</span> <span m="3126730">adapt</span>
  <span m="3127130">the</span> <span m="3127475">timestamp</span> <span m="3128710">according</span>
  <span m="3129180">to--</span> <span m="3129650">because</span> <span m="3130050">they</span>
  <span m="3130110">have</span> <span m="3130300">different</span> <span m="3130660">[?
  phase, ?]</span> <span m="3131020">and</span> <span m="3131150">different</span>
  <span m="3131440">parts</span> <span m="3131630">of</span> <span m="3131710">the</span>
  <span m="3131800">solution,</span> <span m="3132140">when</span> <span m="3132330">you</span>
  <span m="3132460">linearize</span> <span m="3132570">the</span> <span m="3133390">nonlinear</span>
  <span m="3133830">equations,</span> <span m="3134710">you get</span> <span m="3135590">different</span>
  <span m="3136030">eigenvalues.</span></p><p><span m="3137796">So</span> <span m="3138284">when
  you get</span> <span m="3138772">the big</span> <span m="3139260">eigenvalues,</span>
  <span m="3140236">or</span> <span m="3141220">[INAUDIBLE],</span> <span m="3141765">it''s</span>
  <span m="3142050">important</span> <span m="3142517">to</span> <span m="3142594">make</span>
  <span m="3142750">[? them ?]</span> <span m="3142828">small.</span> <span m="3145320">Any</span>
  <span m="3145470">other</span> <span m="3145670">questions?</span> <span m="3148440">OK.</span>
  <span m="3149420">Let</span> <span m="3149630">me</span> <span m="3149750">pose</span>
  <span m="3150080">another</span> <span m="3150910">change</span> <span m="3151340">question.</span>
  <span m="3161530">Oh,</span> <span m="3161770">right.</span> <span m="3162270">OK.</span>
  <span m="3163710">Yes,</span> <span m="3164230">what</span> <span m="3164390">about</span>
  <span m="3164570">midpoint?</span></p><p><span m="3166610">If</span> <span m="3167040">you</span>
  <span m="3167130">look</span> <span m="3167400">at</span> <span m="3167860">the</span>
  <span m="3168020">eigenvalues,</span> <span m="3170470">will they</span> <span m="3170640">work</span>
  <span m="3170750">for</span> <span m="3171020">midpoint?</span> <span m="3178320">Only</span>
  <span m="3178780">when</span> <span m="3179140">epsilon</span> <span m="3179430">is</span>
  <span m="3179720">equal</span> <span m="3180140">to</span> <span m="3180560">0.</span>
  <span m="3181370">Only</span> <span m="3181700">when</span> <span m="3181920">epsilon</span>
  <span m="3181980">is</span> <span m="3182460">equal</span> <span m="3182836">to</span>
  <span m="3183212">0, we</span> <span m="3183590">get</span> <span m="3183950">equal</span>
  <span m="3184190">eigenvalues.</span> <span m="3184730">And</span> <span m="3185193">for</span>
  <span m="3185656">what</span> <span m="3186120">delta</span> <span m="3186280">t</span>
  <span m="3186470">would</span> <span m="3186630">midpoint</span> <span m="3187130">be</span>
  <span m="3187630">stable?</span> <span m="3196280">Less</span> <span m="3196460">or
  equal</span> <span m="3196530">to</span> <span m="3196830">1,</span> <span m="3197800">right?</span>
  <span m="3198670">Because</span> <span m="3198730">the</span> <span m="3199160">stability</span>
  <span m="3199760">region</span> <span m="3200240">for</span> <span m="3200760">midpoint,</span>
  <span m="3202350">when</span> <span m="3202520">looking</span> <span m="3202790">at</span>
  <span m="3202890">lambda</span> <span m="3203145">times</span> <span m="3203760">delta</span>
  <span m="3204120">t,</span> <span m="3204450">that</span> <span m="3204941">[INAUDIBLE]</span>
  <span m="3205432">midpoint</span> <span m="3205923">to</span> <span m="3206414">midpoint.</span></p><p><span
  m="3207400">If</span> <span m="3207610">you make</span> <span m="3207780">delta</span>
  <span m="3207850">t</span> <span m="3208240">lambda</span> <span m="3208470">equal</span>
  <span m="3208560">to</span> <span m="3208740">1,</span> <span m="3209320">then</span>
  <span m="3209820">the</span> <span m="3210100">[INAUDIBLE]</span> <span m="3210470">pinpoints</span>
  <span m="3210760">was</span> <span m="3211050">[INAUDIBLE]</span> <span m="3212270">into</span>
  <span m="3212650">the</span> <span m="3212890">[INAUDIBLE].</span> <span m="3213510">If</span>
  <span m="3214340">you</span> <span m="3214410">make</span> <span m="3214660">delta</span>
  <span m="3214760">t</span> <span m="3214890">greater</span> <span m="3215240">than</span>
  <span m="3215470">1,</span> <span m="3215670">you will</span> <span m="3216390">push</span>
  <span m="3216760">this</span> <span m="3217000">point</span> <span m="3217780">in</span>
  <span m="3217970">the</span> <span m="3218050">lambda</span> <span m="3218410">delta</span>
  <span m="3218690">t</span> <span m="3218965">[INAUDIBLE]</span> <span m="3219240">out
  of</span> <span m="3219840">the</span> <span m="3220420">[INAUDIBLE].</span></p><p><span
  m="3226650">You''ll</span> <span m="3226890">find</span> <span m="3227110">a</span>
  <span m="3227330">scheme</span> <span m="3227600">where</span> <span m="3230260">it</span>
  <span m="3230470">will</span> <span m="3230600">be</span> <span m="3231320">stable</span>
  <span m="3231860">for</span> <span m="3232540">all</span> <span m="3232860">of</span>
  <span m="3233050">the</span> <span m="3233670">actions--</span> <span m="3238282">trapezoidal,</span>
  <span m="3238781">right?</span> <span m="3239280">Because</span> <span m="3240130">the</span>
  <span m="3240330">trapezoidal</span> <span m="3241200">rule</span> <span m="3241590">has</span>
  <span m="3241900">a</span> <span m="3242260">stability</span> <span m="3242560">region</span>
  <span m="3243030">that</span> <span m="3243340">covers</span> <span m="3243745">the</span>
  <span m="3244150">whole</span> <span m="3244562">left panel.</span> <span m="3245798">And
  we are looking at the</span> <span m="3246210">whole left</span> <span m="3246530">panel</span>
  <span m="3246946">over</span> <span m="3247362">here.</span> <span m="3248610">What
  else?</span></p><p><span m="3252640">The</span> <span m="3252870">[INAUDIBLE]</span>
  <span m="3253530">is</span> <span m="3253750">called</span> <span m="3253950">a</span>
  <span m="3254060">[INAUDIBLE].</span> <span m="3255290">OK,</span> <span m="3256550">that</span>
  <span m="3258010">has</span> <span m="3258120">a</span> <span m="3258340">stability</span>
  <span m="3258650">region</span> <span m="3259215">somewhere</span> <span m="3259470">like</span>
  <span m="3259670">[INAUDIBLE]</span> <span m="3262040">or</span> <span m="3262510">something</span>
  <span m="3262980">like</span> <span m="3263450">that.</span> <span m="3266070">We</span>
  <span m="3266360">can</span> <span m="3266440">have</span> <span m="3266650">a</span>
  <span m="3266800">small</span> <span m="3267110">delta t</span> <span m="3267520">that</span>
  <span m="3268180">would</span> <span m="3268460">bring the</span> <span m="3268860">whole</span>
  <span m="3269776">thing</span> <span m="3270234">into</span> <span m="3270692">the</span>
  <span m="3271150">[INAUDIBLE].</span></p><p><span m="3272530">OK,</span> <span m="3273230">yes?</span></p><p><span
  m="3274664">AUDIENCE: [INAUDIBLE].</span></p><p><span m="3278010">PROFESSOR: How</span>
  <span m="3278430">do</span> <span m="3278530">you</span> <span m="3278760">find</span>
  <span m="3279130">a</span> <span m="3279220">stability</span> <span m="3279320">region</span>
  <span m="3279370">for</span> <span m="3279650">various</span> <span m="3280125">methods?</span>
  <span m="3280600">Good</span> <span m="3280840">point.</span> <span m="3281960">I</span>
  <span m="3282120">have</span> <span m="3282310">showed</span> <span m="3282660">you</span>
  <span m="3282840">how</span> <span m="3283060">to</span> <span m="3283190">find</span>
  <span m="3283410">the</span> <span m="3283500">stability</span> <span m="3283765">region</span>
  <span m="3284030">for</span> <span m="3284110">forward Euler.</span> <span m="3287440">I</span>
  <span m="3287600">have</span> <span m="3287880">showed</span> <span m="3288060">you</span>
  <span m="3288220">how</span> <span m="3288410">to</span> <span m="3288530">find</span>
  <span m="3288930">the</span> <span m="3289020">stability</span> <span m="3289390">region</span>
  <span m="3289710">for</span> <span m="3290174">forward Euler</span> <span m="3292030">by</span>
  <span m="3292160">basically</span> <span m="3292540">plugging</span> <span m="3292875">du
  dt</span> <span m="3293210">for</span> <span m="3293910">the</span> <span m="3293980">lambda</span>
  <span m="3294255">u</span> <span m="3296000">into</span> <span m="3296280">the</span>
  <span m="3296380">scheme.</span></p><p><span m="3297960">I''m</span> <span m="3298110">going
  to</span> <span m="3298290">show you</span> <span m="3298560">another</span> <span
  m="3298810">example</span> <span m="3299910">of</span> <span m="3300090">doing</span>
  <span m="3300360">this</span> <span m="3300550">for</span> <span m="3300660">midpoint,</span>
  <span m="3302020">all</span> <span m="3302150">right?</span> <span m="3302890">OK,</span>
  <span m="3303220">if</span> <span m="3303320">you</span> <span m="3303430">have</span>
  <span m="3303740">a</span> <span m="3303910">midpoint,</span> <span m="3304890">you</span>
  <span m="3305060">have</span> <span m="3305540">a</span> <span m="3306012">Vn</span>
  <span m="3306956">plus</span> <span m="3307430">1</span> <span m="3309280">equal</span>
  <span m="3309690">to</span> <span m="3309850">Vn</span> <span m="3310130">minus</span>
  <span m="3310480">1</span> <span m="3311190">plus</span> <span m="3311615">2</span>
  <span m="3312040">delta</span> <span m="3312380">t</span> <span m="3312910">times</span>
  <span m="3313420">half</span> <span m="3313860">of</span> <span m="3314160">Vn.</span>
  <span m="3318400">I</span> <span m="3318510">can</span> <span m="3318690">do</span>
  <span m="3318810">this</span> <span m="3318980">example,</span> <span m="3319500">but</span>
  <span m="3319540">you''ve</span> <span m="3319620">got</span> <span m="3319790">to</span>
  <span m="3320650">help</span> <span m="3320890">me.</span> <span m="3322100">What''s</span>
  <span m="3322240">next?</span> <span m="3325080">When</span> <span m="3325330">I</span>
  <span m="3325750">analyze</span> <span m="3326230">eigenvalue</span> <span m="3326495">stability,</span>
  <span m="3326980">what</span> <span m="3327440">do</span> <span m="3327550">I</span>
  <span m="3327620">do</span> <span m="3327730">next?</span> <span m="3330910">What</span>
  <span m="3331280">is</span> <span m="3331450">eigenvalue</span> <span m="3331950">stability?</span></p><p><span
  m="3335540">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3342570">PROFESSOR: Yes.</span>
  <span m="3342880">Eigenvalue</span> <span m="3343940">basically</span> <span m="3344850">shows</span>
  <span m="3345145">is</span> <span m="3345440">the</span> <span m="3345760">skill</span>
  <span m="3346120">[INAUDIBLE]</span> <span m="3346590">for</span> <span m="3347180">[INAUDIBLE]</span>
  <span m="3347440">equal</span> <span m="3347730">to</span> <span m="3347960">lambda</span>
  <span m="3348260">u.</span> <span m="3350270">So</span> <span m="3350530">basically,</span>
  <span m="3350940">we</span> <span m="3351070">are</span> <span m="3351250">asking,</span>
  <span m="3351740">is</span> <span m="3352030">the</span> <span m="3352170">scheme</span>
  <span m="3352660">stable</span> <span m="3353020">for</span> <span m="3353330">this</span>
  <span m="3354110">differential</span> <span m="3354520">equation.</span></p><p><span
  m="3355770">So</span> <span m="3356660">when</span> <span m="3356850">we</span>
  <span m="3356970">look</span> <span m="3357230">at</span> <span m="3357420">these</span>
  <span m="3357690">as</span> <span m="3357880">f</span> <span m="3357930">of</span>
  <span m="3358270">u,</span> <span m="3358870">we</span> <span m="3359100">get</span>
  <span m="3359340">lambda</span> <span m="3359826">times</span> <span m="3360312">Vn.</span>
  <span m="3363720">OK,</span> <span m="3364180">so</span> <span m="3364430">I''m</span>
  <span m="3364950">going</span> <span m="3365080">to</span> <span m="3365160">write</span>
  <span m="3365420">it</span> <span m="3365540">down</span> <span m="3365760">again.</span>
  <span m="3367740">This</span> <span m="3368090">is</span> <span m="3369540">what</span>
  <span m="3369860">we</span> <span m="3370030">want</span> <span m="3370240">to</span>
  <span m="3370370">analyze</span> <span m="3371270">[INAUDIBLE]</span> <span m="3373350">exponentially</span>
  <span m="3374080">growing</span> <span m="3374880">solution</span> <span m="3375290">or</span>
  <span m="3375490">not.</span> <span m="3377950">How</span> <span m="3378180">do</span>
  <span m="3378310">I</span> <span m="3378360">analyze</span> <span m="3379010">if</span>
  <span m="3379280">it</span> <span m="3379480">[INAUDIBLE]</span> <span m="3379600">the</span>
  <span m="3379930">exponentially</span> <span m="3380230">growing</span> <span m="3380530">solution</span>
  <span m="3382400">or</span> <span m="3382480">not?</span></p><p><span m="3386500">I''m</span>
  <span m="3386650">going</span> <span m="3386780">to</span> <span m="3386850">try</span>
  <span m="3387100">one.</span> <span m="3388340">I''m</span> <span m="3388500">going</span>
  <span m="3388660">to</span> <span m="3389290">try</span> <span m="3389360">to</span>
  <span m="3389710">say</span> <span m="3390370">Vm</span> <span m="3390990">plus</span>
  <span m="3391260">1</span> <span m="3391740">is equal to</span> <span m="3392230">V0</span>
  <span m="3392730">times</span> <span m="3393660">Z</span> <span m="3393920">to</span>
  <span m="3394020">the</span> <span m="3394100">n plus 1.</span> <span m="3395530">Vn</span>
  <span m="3396360">equal</span> <span m="3396480">to</span> <span m="3396640">V0</span>
  <span m="3396810">times</span> <span m="3397525">[INAUDIBLE]</span> <span m="3399330">minus</span>
  <span m="3399470">1</span> <span m="3399770">equal</span> <span m="3399980">to</span>
  <span m="3400200">V0</span> <span m="3400520">times</span> <span m="3400840">Z</span>
  <span m="3401110">to</span> <span m="3401190">the</span> <span m="3401290">n</span>
  <span m="3401740">minus</span> <span m="3402085">1.</span> <span m="3402750">I''m
  just going to</span> <span m="3402840">try</span> <span m="3403030">1,</span> <span
  m="3403910">try</span> <span m="3404170">an</span> <span m="3404430">exponential</span>
  <span m="3404790">growing</span> <span m="3405200">solution</span> <span m="3405560">to</span>
  <span m="3405660">see</span> <span m="3406360">if</span> <span m="3406640">it</span>
  <span m="3406770">is</span> <span m="3406920">possible</span> <span m="3407560">for</span>
  <span m="3407720">Z</span> <span m="3408570">to</span> <span m="3408710">be</span>
  <span m="3408840">something</span> <span m="3409250">greater</span> <span m="3409570">than</span>
  <span m="3409780">1</span> <span m="3410090">or</span> <span m="3410720">less</span>
  <span m="3410970">than</span> <span m="3411080">minus</span> <span m="3411160">1,</span>
  <span m="3411840">or</span> <span m="3412130">having</span> <span m="3412630">an</span>
  <span m="3413030">imaginary</span> <span m="3413670">having</span> <span m="3413980">a</span>
  <span m="3414435">complex</span> <span m="3414890">value</span> <span m="3415800">that</span>
  <span m="3416576">has</span> <span m="3417032">a</span> <span m="3417488">modulus</span>
  <span m="3417944">greater than 1.</span> <span m="3418400">But if it''s</span> <span
  m="3418860">one</span> <span m="3419160">of</span> <span m="3419280">these</span>
  <span m="3419470">cases,</span> <span m="3420080">I''m</span> <span m="3420340">going</span>
  <span m="3420480">to</span> <span m="3420540">get</span> <span m="3420730">an</span>
  <span m="3420800">unstable</span> <span m="3420930">scheme.</span></p><p><span m="3423390">OK,</span>
  <span m="3423740">let</span> <span m="3423880">me</span> <span m="3423980">plug</span>
  <span m="3424350">this</span> <span m="3424520">in,</span> <span m="3424800">and</span>
  <span m="3425010">I''m</span> <span m="3425110">going</span> <span m="3425240">to</span>
  <span m="3425310">cancel</span> <span m="3425700">all of</span> <span m="3425880">these</span>
  <span m="3425970">zeroes.</span> <span m="3427130">What</span> <span m="3427350">I''m</span>
  <span m="3427460">going</span> <span m="3427580">to</span> <span m="3427650">get</span>
  <span m="3427970">is</span> <span m="3428360">Z</span> <span m="3428530">to</span>
  <span m="3428650">the n</span> <span m="3428940">plus</span> <span m="3429230">1</span>
  <span m="3429550">power.</span> <span m="3430120">Power</span> <span m="3431240">is</span>
  <span m="3431440">equal</span> <span m="3431770">to</span> <span m="3432020">z</span>
  <span m="3432430">to the</span> <span m="3432750">n</span> <span m="3433070">minus</span>
  <span m="3433350">1</span> <span m="3433650">power.</span> <span m="3434500">I mean,</span>
  <span m="3435030">these</span> <span m="3435320">are</span> <span m="3435460">time</span>
  <span m="3435730">steps.</span> <span m="3436460">These</span> <span m="3436620">are
  time</span> <span m="3437010">steps.</span></p><p><span m="3437670">Now</span> <span
  m="3440690">what I get is to</span> <span m="3440830">the</span> <span m="3440930">powers.</span>
  <span m="3442650">I''m</span> <span m="3442990">going</span> <span m="3443130">to</span>
  <span m="3443190">do</span> <span m="3443520">parenthesis</span> <span m="3444530">to</span>
  <span m="3444650">denote</span> <span m="3444780">time steps</span> <span m="3445580">and</span>
  <span m="3445850">the</span> <span m="3446070">ones</span> <span m="3446350">without</span>
  <span m="3446500">parentheses</span> <span m="3446920">to</span> <span m="3447090">denote</span>
  <span m="3447240">power.</span> <span m="3449230">Oh,</span> <span m="3449610">this</span>
  <span m="3449780">is</span> <span m="3449950">a</span> <span m="3449980">plus,</span>
  <span m="3450480">sorry.</span> <span m="3451730">Plus</span> <span m="3452160">2</span>
  <span m="3452616">delta</span> <span m="3453072">t</span> <span m="3453984">times</span>
  <span m="3454440">lambda</span> <span m="3454680">Z</span> <span m="3454770">to
  the</span> <span m="3454890">n.</span> <span m="3457030">OK,</span> <span m="3457270">what</span>
  <span m="3457430">do</span> <span m="3457510">I</span> <span m="3457580">do</span>
  <span m="3457690">next?</span></p><p><span m="3462780">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="3465630">PROFESSOR: Factor</span> <span m="3465900">out</span> <span m="3466105">Z</span>
  <span m="3466310">to</span> <span m="3467240">the</span> <span m="3467350">n minus</span>
  <span m="3467800">1.</span> <span m="3469140">I''m</span> <span m="3469310">going</span>
  <span m="3469430">to</span> <span m="3469500">get</span> <span m="3469750">a</span>
  <span m="3469830">quadratic</span> <span m="3470420">equation</span> <span m="3472550">equal</span>
  <span m="3472870">to</span> <span m="3472940">1</span> <span m="3473440">plus</span>
  <span m="3473810">2</span> <span m="3474120">delta</span> <span m="3474440">t</span>
  <span m="3474907">lambda</span> <span m="3475841">times</span> <span m="3476308">z.</span>
  <span m="3479720">OK,</span> <span m="3480280">now</span> <span m="3481560">I</span>
  <span m="3481700">can''t</span> <span m="3481950">get</span> <span m="3482210">the</span>
  <span m="3482310">solution</span> <span m="3482760">for</span> <span m="3482900">z</span>
  <span m="3483280">to</span> <span m="3483430">see</span> <span m="3483870">if</span>
  <span m="3484100">it</span> <span m="3484370">can</span> <span m="3484690">lead</span>
  <span m="3485220">to an</span> <span m="3486580">exponentially</span> <span m="3487240">growing</span>
  <span m="3487640">solution</span> <span m="3488060">or</span> <span m="3488160">not.</span>
  <span m="3489260">So</span> <span m="3489940">I</span> <span m="3490330">believe</span>
  <span m="3490900">I</span> <span m="3491010">get</span> <span m="3491930">2</span>
  <span m="3493860">lambda</span> <span m="3494230">delta</span> <span m="3494430">t</span>
  <span m="3494740">plus</span> <span m="3495605">minus</span> <span m="3496790">square</span>
  <span m="3497242">root</span> <span m="3499960">of</span> <span m="3502440">4</span>
  <span m="3502720">lambda</span> <span m="3502890">squared</span> <span m="3503260">delta</span>
  <span m="3503440">t</span> <span m="3503840">squared</span> <span m="3505811">plus</span>
  <span m="3506725">4.</span></p><p><span m="3518710">So</span> <span m="3520880">let</span>
  <span m="3521050">me</span> <span m="3521940">go</span> <span m="3522940">[INAUDIBLE].</span>
  <span m="3524440">OK,</span> <span m="3524940">so this</span> <span m="3525440">is</span>
  <span m="3525940">the</span> <span m="3526440">Z</span> <span m="3526940">I got.</span>
  <span m="3528660">I</span> <span m="3528840">want</span> <span m="3529550">this</span>
  <span m="3529840">Z</span> <span m="3531298">to</span> <span m="3532770">have</span>
  <span m="3533270">a</span> <span m="3533770">modulus</span> <span m="3534270">less</span>
  <span m="3534770">or</span> <span m="3535270">equal</span> <span m="3535770">to</span>
  <span m="3536270">1.</span> <span m="3549466">[INAUDIBLE]</span> <span m="3556078">And</span>
  <span m="3556486">this</span> <span m="3556894">2,</span> <span m="3557302">divided</span>
  <span m="3557710">by</span> <span m="3558030">2,</span> <span m="3559020">if</span>
  <span m="3560010">lambda</span> <span m="3561990">is--</span> <span m="3563770">so</span>
  <span m="3564310">let''s</span> <span m="3564650">proceed.</span> <span m="3564990">If</span>
  <span m="3565260">lambda</span> <span m="3565820">is a</span> <span m="3565960">real</span>
  <span m="3566250">value,</span> <span m="3567050">if</span> <span m="3567450">lambda</span>
  <span m="3567750">is</span> <span m="3568050">anything</span> <span m="3569010">real,</span>
  <span m="3571440">and</span> <span m="3571760">nonzero,</span> <span m="3572600">then</span>
  <span m="3572860">lambda</span> <span m="3572970">squared</span> <span m="3573425">is
  going to</span> <span m="3573700">be</span> <span m="3573970">something</span> <span
  m="3574330">positive.</span></p><p><span m="3575050">And what</span> <span m="3575325">I
  get is</span> <span m="3575950">something</span> <span m="3576390">greater</span>
  <span m="3576660">than</span> <span m="3577005">4.</span> <span m="3578280">And</span>
  <span m="3578480">the</span> <span m="3578680">square</span> <span m="3579010">root</span>
  <span m="3579680">is</span> <span m="3580020">going</span> <span m="3580360">to</span>
  <span m="3580650">be</span> <span m="3581144">something greater</span> <span m="3581638">than</span>
  <span m="3582132">2.</span> <span m="3586084">So</span> <span m="3586760">because</span>
  <span m="3587460">I</span> <span m="3587630">have</span> <span m="3587900">a</span>
  <span m="3588020">plus</span> <span m="3588560">or</span> <span m="3588920">minus,</span>
  <span m="3590490">one</span> <span m="3590850">of</span> <span m="3591040">them</span>
  <span m="3591360">is going to</span> <span m="3591850">have</span> <span m="3592020">a</span>
  <span m="3592150">magnitude</span> <span m="3593400">greater</span> <span m="3593680">than</span>
  <span m="3593985">2.</span> <span m="3595156">When divided</span> <span m="3595590">by
  2, I''m going to get</span> <span m="3595790">something</span> <span m="3596120">greater</span>
  <span m="3596490">than</span> <span m="3596670">1.</span></p><p><span m="3598660">So</span>
  <span m="3598890">for</span> <span m="3599040">any</span> <span m="3599420">real</span>
  <span m="3599810">lambda,</span> <span m="3600250">I''m</span> <span m="3600420">going</span>
  <span m="3600550">to</span> <span m="3600610">be</span> <span m="3600720">on</span>
  <span m="3600890">unstable.</span> <span m="3604000">And</span> <span m="3604140">you
  can also figure</span> <span m="3604475">out,</span> <span m="3605742">for</span>
  <span m="3606420">complex</span> <span m="3606960">values</span> <span m="3607480">of</span>
  <span m="3607650">lambda,</span> <span m="3610080">what</span> <span m="3610370">values</span>
  <span m="3610880">is</span> <span m="3611010">going</span> <span m="3611130">to</span>
  <span m="3611190">make</span> <span m="3611460">it</span> <span m="3611740">stable,</span>
  <span m="3611910">what value</span> <span m="3612250">is</span> <span m="3612720">not</span>
  <span m="3613130">going to</span> <span m="3613540">make it</span> <span m="3613950">stable.</span>
  <span m="3614360">And</span> <span m="3614530">in</span> <span m="3614660">fact,</span>
  <span m="3615400">[INAUDIBLE]</span> <span m="3618700">for</span> <span m="3618900">all</span>
  <span m="3619380">the</span> <span m="3619520">values</span> <span m="3620050">of</span>
  <span m="3620230">lambda</span> <span m="3620470">delta</span> <span m="3620600">t,</span>
  <span m="3621785">that</span> <span m="3622180">will</span> <span m="3622800">make</span>
  <span m="3623445">this</span> <span m="3624520">Z</span> <span m="3625115">having</span>
  <span m="3625720">a</span> <span m="3626020">modulus</span> <span m="3626300">of</span>
  <span m="3626550">exactly</span> <span m="3627050">31.</span></p><p><span m="3631080">So
  if</span> <span m="3631150">this</span> <span m="3631405">has a value</span> <span
  m="3631660">exactly</span> <span m="3631990">31,</span> <span m="3634520">my</span>
  <span m="3634730">[? schema ?]</span> <span m="3635220">is going</span> <span m="3635560">to</span>
  <span m="3635640">be</span> <span m="3636300">exactly</span> <span m="3637040">on</span>
  <span m="3637230">the</span> <span m="3637340">boundary</span> <span m="3637950">of</span>
  <span m="3638645">stability.</span> <span m="3641140">So</span> <span m="3641270">if</span>
  <span m="3641450">I</span> <span m="3641620">have</span> <span m="3641850">all</span>
  <span m="3642180">this</span> <span m="3642510">level</span> <span m="3642730">1,</span>
  <span m="3643150">I''m going to be</span> <span m="3643640">stable.</span> <span
  m="3644130">If</span> <span m="3644310">I</span> <span m="3644440">have</span> <span
  m="3644600">1</span> <span m="3644910">z</span> <span m="3645350">that is</span>
  <span m="3645830">greater</span> <span m="3646260">than</span> <span m="3646660">1,</span>
  <span m="3647060">if</span> <span m="3647460">I have</span> <span m="3647860">[INAUDIBLE]</span>
  <span m="3649990">modulus,</span> <span m="3652430">[INAUDIBLE],</span> <span m="3653910">I''m
  on the</span> <span m="3653980">boundary.</span></p><p><span m="3654940">So</span>
  <span m="3655100">by</span> <span m="3655290">[INAUDIBLE],</span> <span m="3658270">I''m</span>
  <span m="3659166">going to</span> <span m="3660960">compute</span> <span m="3661500">the</span>
  <span m="3661600">boundary</span> <span m="3662280">of</span> <span m="3662440">the</span>
  <span m="3662680">stability</span> <span m="3663120">region,</span> <span m="3663470">which</span>
  <span m="3663820">gives</span> <span m="3664010">me</span> <span m="3664892">something</span>
  <span m="3665112">like</span> <span m="3665333">this.</span> <span m="3666656">So</span>
  <span m="3667100">if</span> <span m="3667320">I</span> <span m="3667420">take</span>
  <span m="3667877">the</span> <span m="3668334">boundary</span> <span m="3669248">[INAUDIBLE]</span>
  <span m="3671540">modulus</span> <span m="3672225">1,</span> <span m="3672520">I''m
  going to</span> <span m="3673000">block</span> <span m="3673500">its</span> <span
  m="3673800">boundary</span> <span m="3674100">of</span> <span m="3674770">stability.</span>
  <span m="3675935">[INAUDIBLE]</span> <span m="3678410">Yeah?</span></p><p><span
  m="3680390">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3731180">PROFESSOR: Yeah,</span>
  <span m="3731410">Professor</span> <span m="3731670">Wilcox</span> <span m="3731760">is</span>
  <span m="3732260">saying</span> <span m="3732630">that,</span> <span m="3733370">when</span>
  <span m="3734320">you</span> <span m="3734450">look</span> <span m="3734780">at</span>
  <span m="3734940">this</span> <span m="3735200">equation,</span> <span m="3737010">and</span>
  <span m="3737865">plug</span> <span m="3738190">in</span> <span m="3738966">Z is</span>
  <span m="3739432">equal</span> <span m="3739900">to</span> <span m="3739990">e</span>
  <span m="3740110">to</span> <span m="3740440">the</span> <span m="3740905">ith</span>
  <span m="3741370">theta,</span> <span m="3741480">you''re</span> <span m="3741590">going</span>
  <span m="3741720">to</span> <span m="3741810">get</span> <span m="3742950">Z</span>
  <span m="3743160">squared,</span> <span m="3743420">which</span> <span m="3743600">is</span>
  <span m="3743740">e</span> <span m="3743950">to</span> <span m="3744010">the</span>
  <span m="3744450">2i</span> <span m="3744740">theta</span> <span m="3745380">is</span>
  <span m="3745590">equal</span> <span m="3745820">to 1</span> <span m="3746200">plus</span>
  <span m="3747310">2</span> <span m="3747620">times</span> <span m="3748310">delta</span>
  <span m="3748480">t</span> <span m="3748680">lambda</span> <span m="3749880">times</span>
  <span m="3750280">z,</span> <span m="3750630">which</span> <span m="3750850">is</span>
  <span m="3750990">e</span> <span m="3751360">to</span> <span m="3751560">the</span>
  <span m="3751870">ith</span> <span m="3752345">theta.</span></p><p><span m="3753770">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="3760430">PROFESSOR: Right.</span> <span m="3760660">And
  then--</span></p><p><span m="3762109">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3771780">PROFESSOR:
  Right,</span> <span m="3772310">and</span> <span m="3773870">you</span> <span m="3773930">can
  figure</span> <span m="3774040">out the</span> <span m="3774470">stability</span>
  <span m="3774960">boundary</span> <span m="3775410">for</span> <span m="3776402">delta</span>
  <span m="3776898">t</span> <span m="3777394">lambda</span> <span m="3777890">using</span>
  <span m="3778882">[INAUDIBLE].</span> <span m="3792103">All right.</span> <span
  m="3792590">OK.</span></p><p><span m="3793300">Let</span> <span m="3793520">me</span>
  <span m="3793630">show</span> <span m="3793930">you</span> <span m="3793990">one</span>
  <span m="3794340">last</span> <span m="3794640">thing.</span> <span m="3797180">What</span>
  <span m="3797330">if</span> <span m="3797440">you</span> <span m="3797540">have</span>
  <span m="3797700">a</span> <span m="3797760">du dt</span> <span m="3798290">equal</span>
  <span m="3799210">to</span> <span m="3799800">minus</span> <span m="3800410">u</span>
  <span m="3800780">squared?</span> <span m="3806550">We</span> <span m="3806680">get</span>
  <span m="3806850">a</span> <span m="3806900">non-linear</span> <span m="3807160">equation.</span>
  <span m="3810540">For</span> <span m="3810730">what</span> <span m="3811070">scheme</span>
  <span m="3811650">would this</span> <span m="3811970">be</span> <span m="3812110">stable?</span>
  <span m="3812570">What</span> <span m="3813025">scheme</span> <span m="3813480">this</span>
  <span m="3813690">would</span> <span m="3813840">be</span> <span m="3813990">unstable?</span></p><p><span
  m="3823020">The</span> <span m="3823150">analysis</span> <span m="3823800">of</span>
  <span m="3824010">this</span> <span m="3824220">scheme</span> <span m="3824705">lies</span>
  <span m="3825675">in</span> <span m="3826645">linearization.</span> <span m="3828100">OK,</span>
  <span m="3828430">so</span> <span m="3828580">let''s</span> <span m="3828790">say,</span>
  <span m="3829220">if</span> <span m="3829390">I</span> <span m="3829510">have</span>
  <span m="3829680">a</span> <span m="3830098">u</span> <span m="3830516">of</span>
  <span m="3830934">0</span> <span m="3831770">at</span> <span m="3832030">t equal
  to 0</span> <span m="3832290">equal</span> <span m="3832520">to</span> <span m="3832800">1.</span>
  <span m="3834170">OK.</span> <span m="3835560">What</span> <span m="3835730">if</span>
  <span m="3835920">I</span> <span m="3836080">linearize</span> <span m="3836740">this</span>
  <span m="3836920">question?</span> <span m="3837790">What</span> <span m="3838010">if</span>
  <span m="3838200">I</span> <span m="3838400">say,</span> <span m="3839040">u,</span>
  <span m="3841150">I''m</span> <span m="3841380">going</span> <span m="3841540">to</span>
  <span m="3841610">put</span> <span m="3841920">[INAUDIBLE]</span> <span m="3842660">a</span>
  <span m="3843090">u</span> <span m="3843520">to</span> <span m="3844380">u</span>
  <span m="3845010">plus</span> <span m="3846440">delta</span> <span m="3847380">u,</span>
  <span m="3847910">or</span> <span m="3848750">plus a</span> <span m="3848870">very</span>
  <span m="3849250">small</span> <span m="3849684">v.</span></p><p><span m="3853270">What</span>
  <span m="3853480">is</span> <span m="3853660">the</span> <span m="3853760">result</span>
  <span m="3854240">of</span> <span m="3854380">the</span> <span m="3854490">linearization?</span>
  <span m="3857510">The</span> <span m="3857650">linearization</span> <span m="3858440">can</span>
  <span m="3858680">be</span> <span m="3858800">seen</span> <span m="3859790">by</span>
  <span m="3859970">plugging</span> <span m="3860750">both</span> <span m="3861025">the
  u</span> <span m="3861300">and</span> <span m="3861700">the</span> <span m="3862100">u</span>
  <span m="3862500">plus</span> <span m="3862590">V</span> <span m="3863410">into</span>
  <span m="3863620">the</span> <span m="3863710">differential</span> <span m="3864170">equation.</span>
  <span m="3866470">If</span> <span m="3866690">you</span> <span m="3866810">plug</span>
  <span m="3867310">just</span> <span m="3867500">the u,</span> <span m="3867650">you</span>
  <span m="3868060">get</span> <span m="3868340">this.</span> <span m="3868720">If</span>
  <span m="3868900">you</span> <span m="3869000">plus</span> <span m="3869390">u</span>
  <span m="3869740">plus</span> <span m="3870410">v,</span> <span m="3871760">you</span>
  <span m="3871980">get</span> <span m="3872400">du</span> <span m="3872820">plus</span>
  <span m="3873440">V</span> <span m="3874380">dt</span> <span m="3875320">equal</span>
  <span m="3875790">to</span> <span m="3876260">minus</span> <span m="3876790">u</span>
  <span m="3877540">plus</span> <span m="3877980">V</span> <span m="3878473">squared.</span>
  <span m="3880940">And</span> <span m="3881180">here</span> <span m="3881550">is</span>
  <span m="3881630">linearization</span> <span m="3882083">V</span> <span m="3882990">is</span>
  <span m="3884000">very</span> <span m="3885950">small.</span></p><p><span m="3887670">And</span>
  <span m="3887850">because</span> <span m="3888220">v</span> <span m="3888440">is</span>
  <span m="3888570">very</span> <span m="3888840">small,</span> <span m="3889710">you</span>
  <span m="3889770">can</span> <span m="3890140">derive</span> <span m="3890750">du</span>
  <span m="3891730">dt</span> <span m="3892340">plus</span> <span m="3892750">dv dt.</span>
  <span m="3893670">This</span> <span m="3893870">is</span> <span m="3894020">just</span>
  <span m="3894595">factorizing</span> <span m="3895150">u</span> <span m="3895966">plus</span>
  <span m="3896332">v</span> <span m="3896700">out</span> <span m="3896950">of</span>
  <span m="3897090">the</span> <span m="3897260">derivative,</span> <span m="3898320">is</span>
  <span m="3898570">equal</span> <span m="3898860">to</span> <span m="3898960">minus</span>
  <span m="3899260">u</span> <span m="3899680">squared</span> <span m="3900100">minus</span>
  <span m="3900600">2</span> <span m="3900970">uV,</span> <span m="3901650">minus</span>
  <span m="3902150">V</span> <span m="3902670">squared.</span> <span m="3903050">But</span>
  <span m="3903240">because</span> <span m="3903720">V</span> <span m="3903950">is</span>
  <span m="3904080">very</span> <span m="3904360">small,</span> <span m="3905180">this</span>
  <span m="3905510">term</span> <span m="3905810">is</span> <span m="3906010">negligible.</span>
  <span m="3908920">This</span> <span m="3909220">term</span> <span m="3909630">is</span>
  <span m="3910710">very,</span> <span m="3911640">very</span> <span m="3912200">small,</span>
  <span m="3912550">or</span> <span m="3912790">very</span> <span m="3913220">square</span>
  <span m="3913630">small.</span> <span m="3918250">OK.</span></p><p><span m="3919340">Now,</span>
  <span m="3920470">when</span> <span m="3920670">you</span> <span m="3920790">look</span>
  <span m="3921040">at</span> <span m="3921690">the</span> <span m="3921870">answer</span>
  <span m="3922090">to</span> <span m="3922340">the</span> <span m="3922460">equation</span>
  <span m="3922880">has</span> <span m="3922930">a</span> <span m="3923100">du</span>
  <span m="3923160">dt.</span> <span m="3924235">The</span> <span m="3924530">right</span>
  <span m="3924860">hand</span> <span m="3925160">side</span> <span m="3925220">has</span>
  <span m="3925420">a</span> <span m="3925490">minus</span> <span m="3925780">u</span>
  <span m="3926010">squared.</span> <span m="3926776">The</span> <span m="3927160">right
  hand</span> <span m="3927370">side</span> <span m="3927450">has a minus</span> <span
  m="3927640">u</span> <span m="3927890">squared.</span> <span m="3928710">These</span>
  <span m="3929110">two</span> <span m="3929290">terms</span> <span m="3929530">cancel</span>
  <span m="3929740">out</span> <span m="3930130">because of the</span> <span m="3930250">answer</span>
  <span m="3930643">to the</span> <span m="3931036">equation.</span> <span m="3932260">The</span>
  <span m="3932440">only</span> <span m="3932700">thing</span> <span m="3932850">you</span>
  <span m="3933000">get</span> <span m="3933430">is</span> <span m="3933720">the</span>
  <span m="3933830">linearized</span> <span m="3934380">equation</span> <span m="3934655">dv</span>
  <span m="3934930">dt</span> <span m="3936780">equal</span> <span m="3937090">or</span>
  <span m="3937200">minus</span> <span m="3937650">2u</span> <span m="3938200">times</span>
  <span m="3938455">t.</span> <span m="3949724">No,</span> <span m="3950230">yes?</span>
  <span m="3951751">No,</span> <span m="3952160">yes?</span></p><p><span m="3954360">That''s</span>
  <span m="3954670">how</span> <span m="3954910">you</span> <span m="3955050">would</span>
  <span m="3955190">linearize</span> <span m="3955535">a</span> <span m="3955880">nonlinear</span>
  <span m="3956135">equation--</span> <span m="3957820">by</span> <span m="3957960">perturbing</span>
  <span m="3959010">the</span> <span m="3959130">variable</span> <span m="3960300">into</span>
  <span m="3960740">the</span> <span m="3960830">variable</span> <span m="3961810">something</span>
  <span m="3963110">very</span> <span m="3963330">small</span> <span m="3964170">and</span>
  <span m="3965150">remove</span> <span m="3965750">all</span> <span m="3965960">other</span>
  <span m="3966300">very,</span> <span m="3966760">very</span> <span m="3967030">small</span>
  <span m="3967580">terms,</span> <span m="3969650">and</span> <span m="3969940">the</span>
  <span m="3970020">very,</span> <span m="3970510">very,</span> <span m="3970800">very</span>
  <span m="3970970">small</span> <span m="3971440">[INAUDIBLE],</span> <span m="3972380">if</span>
  <span m="3972460">you</span> <span m="3972570">have</span> <span m="3972910">cubic</span>
  <span m="3973030">terms.</span></p><p><span m="3976370">So</span> <span m="3976520">now</span>
  <span m="3976750">we</span> <span m="3976880">have</span> <span m="3977605">the</span>
  <span m="3978080">linearized</span> <span m="3978170">equation,</span> <span m="3978540">which</span>
  <span m="3978730">is</span> <span m="3978860">linear</span> <span m="3979280">with</span>
  <span m="3979440">respect</span> <span m="3979780">to</span> <span m="3979910">V.</span>
  <span m="3984416">Can</span> <span m="3984648">somebody</span> <span m="3984880">tell</span>
  <span m="3985080">me,</span> <span m="3985280">if</span> <span m="3985400">I</span>
  <span m="3985500">use</span> <span m="3985940">forward Euler,</span> <span m="3987260">when</span>
  <span m="3988200">would</span> <span m="3988350">this</span> <span m="3988650">scheme</span>
  <span m="3988870">be</span> <span m="3989000">stable?</span> <span m="3989470">When</span>
  <span m="3989780">would</span> <span m="3992110">my</span> <span m="3992310">forward
  Euler</span> <span m="3992600">be</span> <span m="3992790">stable?</span></p><p><span
  m="4006740">AUDIENCE: [INAUDIBLE]</span></p><p><span m="4014030">PROFESSOR: Good.</span>
  <span m="4014360">In</span> <span m="4014580">this</span> <span m="4014930">case,</span>
  <span m="4015350">this</span> <span m="4015650">is</span> <span m="4015790">my</span>
  <span m="4015970">lambda.</span> <span m="4018390">I''m solving</span> <span m="4018745">dv
  dt</span> <span m="4019100">equal</span> <span m="4019230">to</span> <span m="4019310">minus</span>
  <span m="4019670">2u</span> <span m="4019840">times</span> <span m="4020040">v.</span>
  <span m="4021050">My</span> <span m="4021600">minus</span> <span m="4022020">2u</span>
  <span m="4022490">is</span> <span m="4022650">my</span> <span m="4022820">lambda.</span>
  <span m="4023620">This</span> <span m="4023950">is</span> <span m="4024140">where,</span>
  <span m="4024480">like,</span> <span m="4025220">you</span> <span m="4025410">have</span>
  <span m="4025520">a</span> <span m="4025580">question</span> <span m="4026056">of</span>
  <span m="4026532">adaptive</span> <span m="4027008">timestamping,</span> <span m="4027484">right?</span>
  <span m="4027960">This</span> <span m="4028300">is</span> <span m="4028420">when</span>
  <span m="4028690">lambda</span> <span m="4029010">actually</span> <span m="4029330">depends</span>
  <span m="4029890">on</span> <span m="4030210">the</span> <span m="4030330">solution</span>
  <span m="4030716">U</span> <span m="4031102">of</span> <span m="4031490">the</span>
  <span m="4031850">nonlinear</span> <span m="4032590">equation.</span> <span m="4033420">As</span>
  <span m="4033600">I solve</span> <span m="4033850">the</span> <span m="4033930">nonlinear</span>
  <span m="4034330">equation,</span> <span m="4035140">my</span> <span m="4035390">lambda</span>
  <span m="4035650">of</span> <span m="4035910">the</span> <span m="4036240">linearized</span>
  <span m="4036570">equation</span> <span m="4037030">actually</span> <span m="4037910">changes.</span></p><p><span
  m="4040140">So</span> <span m="4040330">in</span> <span m="4040450">the</span> <span
  m="4040520">beginning,</span> <span m="4041090">I</span> <span m="4041140">mean,</span>
  <span m="4041270">the</span> <span m="4041350">solution</span> <span m="4041740">of</span>
  <span m="4041840">this</span> <span m="4042030">equation</span> <span m="4042430">looks</span>
  <span m="4042660">like</span> <span m="4042860">this.</span> <span m="4044720">Actually,</span>
  <span m="4045840">we</span> <span m="4046050">figured</span> <span m="4046370">out</span>
  <span m="4046580">ut,</span> <span m="4047280">I</span> <span m="4047360">think,</span>
  <span m="4047620">is</span> <span m="4047790">equal</span> <span m="4048120">to</span>
  <span m="4049140">1</span> <span m="4049460">over</span> <span m="4049950">t</span>
  <span m="4050170">plus 1 or</span> <span m="4050400">something</span> <span m="4050650">like</span>
  <span m="4050820">that,</span> <span m="4051070">right?</span> <span m="4051780">In</span>
  <span m="4051930">the</span> <span m="4052650">first</span> <span m="4052860">or</span>
  <span m="4052970">second</span> <span m="4053270">lecture</span> <span m="4053640">we</span>
  <span m="4053930">figured that</span> <span m="4054130">out.</span> <span m="4054720">So</span>
  <span m="4055710">in</span> <span m="4055840">the</span> <span m="4055910">beginning,</span>
  <span m="4058180">u</span> <span m="4058530">is</span> <span m="4058780">large,</span>
  <span m="4059320">and</span> <span m="4059520">minus</span> <span m="4059810">2u</span>
  <span m="4060330">is</span> <span m="4060720">kind</span> <span m="4060900">of</span>
  <span m="4061110">on</span> <span m="4061380">the</span> <span m="4061620">negative</span>
  <span m="4062050">side,</span> <span m="4062445">and big.</span></p><p><span m="4062840">We</span>
  <span m="4062990">need</span> <span m="4063160">to</span> <span m="4063290">use</span>
  <span m="4063620">a</span> <span m="4063840">smaller</span> <span m="4064220">timestamp.</span>
  <span m="4065320">And</span> <span m="4065550">later</span> <span m="4065940">on,</span>
  <span m="4066160">as</span> <span m="4066380">you</span> <span m="4066590">become</span>
  <span m="4066980">smaller</span> <span m="4067270">and</span> <span m="4067370">smaller,</span>
  <span m="4067850">we</span> <span m="4068080">are</span> <span m="4068290">allowed
  to</span> <span m="4068570">use</span> <span m="4068930">larger</span> <span m="4069280">timestamps</span>
  <span m="4069810">for</span> <span m="4070180">forward Euler</span> <span m="4070570">to</span>
  <span m="4070680">be</span> <span m="4071170">stable.</span> <span m="4072150">This</span>
  <span m="4072490">is</span> <span m="4072680">a</span> <span m="4072770">case</span>
  <span m="4073160">where</span> <span m="4073840">we</span> <span m="4074000">actually</span>
  <span m="4074380">can</span> <span m="4074580">benefit</span> <span m="4075070">from</span>
  <span m="4075500">adaptive</span> <span m="4075986">timestamps.</span> <span m="4077930">The</span>
  <span m="4078350">case</span> <span m="4079680">is</span> <span m="4080190">minus</span>
  <span m="4080660">2u</span> <span m="4081580">has</span> <span m="4081800">to</span>
  <span m="4081960">be</span> <span m="4082290">less</span> <span m="4083030">than</span>
  <span m="4083470">0,</span> <span m="4083980">equal</span> <span m="4084425">to</span>
  <span m="4084870">0,</span> <span m="4085420">and</span> <span m="4085760">greater</span>
  <span m="4086025">than or</span> <span m="4086290">equal</span> <span m="4086410">to</span>
  <span m="4086600">minus</span> <span m="4086650">2,</span> <span m="4087410">minus</span>
  <span m="4087750">2u</span> <span m="4088620">times</span> <span m="4088770">delta</span>
  <span m="4089170">t</span> <span m="4089440">because</span> <span m="4089760">I</span>
  <span m="4089790">am</span> <span m="4089960">lambda</span> <span m="4090412">delta</span>
  <span m="4090864">t.</span> <span m="4094960">This</span> <span m="4095370">is</span>
  <span m="4095580">the</span> <span m="4095720">stability</span> <span m="4098204">for</span>
  <span m="4098620">forward Euler.</span></p><p><span m="4102319">Questions</span>
  <span m="4102770">on</span> <span m="4102880">this?</span> <span m="4104140">Is</span>
  <span m="4104300">it</span> <span m="4104399">clear</span> <span m="4105750">how</span>
  <span m="4106029">did</span> <span m="4106170">I linearize</span> <span m="4106830">this</span>
  <span m="4107250">and</span> <span m="4107749">apply</span> <span m="4108248">eigenvalue</span>
  <span m="4108747">stability?</span> <span m="4117230">All</span> <span m="4117729">right.</span>
  <span m="4119350">OK.</span></p><p><span m="4121490">Now</span> <span m="4123229">the</span>
  <span m="4123399">last</span> <span m="4123790">thing</span> <span m="4124029">I</span>
  <span m="4124229">want</span> <span m="4124560">to</span> <span m="4126399">do,</span>
  <span m="4127270">not</span> <span m="4127529">sure</span> <span m="4127670">I</span>
  <span m="4127770">have</span> <span m="4127960">time,</span> <span m="4128359">but,</span>
  <span m="4128569">like,</span> <span m="4129350">I</span> <span m="4129620">am</span>
  <span m="4129720">going</span> <span m="4129870">to</span> <span m="4129939">pose</span>
  <span m="4130240">these</span> <span m="4130689">as a</span> <span m="4130790">question--</span>
  <span m="4132310">is</span> <span m="4132510">how</span> <span m="4132750">do</span>
  <span m="4132899">I</span> <span m="4132990">apply</span> <span m="4133335">backward
  Euler</span> <span m="4134760">on</span> <span m="4134930">this</span> <span m="4135120">problem.</span>
  <span m="4136689">How</span> <span m="4136779">do</span> <span m="4136910">I</span>
  <span m="4137010">apply</span> <span m="4137689">backward</span> <span m="4138109">Euler</span>
  <span m="4138997">on</span> <span m="4140330">this</span> <span m="4140580">problem.</span></p><p><span
  m="4144410">What</span> <span m="4144600">is</span> <span m="4144720">backward</span>
  <span m="4145040">Euler?</span> <span m="4145340">Can</span> <span m="4145479">somebody</span>
  <span m="4145810">help</span> <span m="4146000">me</span> <span m="4146149">write</span>
  <span m="4146410">down</span> <span m="4146609">what</span> <span m="4146779">backward</span>
  <span m="4147279">Euler</span> <span m="4147779">is?</span> <span m="4155380">OK,</span>
  <span m="4155649">what</span> <span m="4155830">backward</span> <span m="4156050">Euler</span>
  <span m="4156180">is?</span> <span m="4162630">What</span> <span m="4162890">is</span>
  <span m="4163020">forward</span> <span m="4163490">Euler?</span> <span m="4165370">If</span>
  <span m="4165550">I</span> <span m="4165630">use</span> <span m="4165830">forward</span>
  <span m="4166315">Euler,</span> <span m="4166800">what</span> <span m="4167285">would
  it be</span> <span m="4167770">equal to?</span></p><p><span m="4170680">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="4176029">PROFESSOR: Forward Euler</span> <span
  m="4176290">would</span> <span m="4176910">be</span> <span m="4177319">e f</span>
  <span m="4177729">of u</span> <span m="4177990">to</span> <span m="4178460">the</span>
  <span m="4178609">n.</span> <span m="4180609">What</span> <span m="4180979">would</span>
  <span m="4181250">backward</span> <span m="4181569">Euler</span> <span m="4182064">be?</span>
  <span m="4192459">For</span> <span m="4192970">f</span> <span m="4193410">of</span>
  <span m="4193700">u</span> <span m="4193990">n</span> <span m="4194470">is</span>
  <span m="4194950">Forward Euler.</span></p><p><span m="4196308">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="4200180">PROFESSOR: Yeah,</span> <span m="4200500">backward</span> <span m="4200770">Euler</span>
  <span m="4201280">is</span> <span m="4201620">f</span> <span m="4201696">of</span>
  <span m="4201773">u</span> <span m="4201850">to</span> <span m="4202050">the</span>
  <span m="4202370">n</span> <span m="4202470">times</span> <span m="4202980">1.</span>
  <span m="4208200">So</span> <span m="4208390">that</span> <span m="4208660">that</span>
  <span m="4208950">is</span> <span m="4209080">backward</span> <span m="4209410">Euler.</span>
  <span m="4210130">And</span> <span m="4210380">in</span> <span m="4210540">this</span>
  <span m="4211010">particular</span> <span m="4211460">case,</span> <span m="4211920">I''m</span>
  <span m="4211970">going</span> <span m="4212100">to</span> <span m="4212170">get</span>
  <span m="4212450">minus</span> <span m="4212800">u</span> <span m="4213140">n</span>
  <span m="4213420">plus</span> <span m="4213700">1</span> <span m="4215850">squared.</span>
  <span m="4220120">I''m</span> <span m="4220270">going</span> <span m="4220400">to</span>
  <span m="4220470">get</span> <span m="4220670">an</span> <span m="4220820">equation</span>
  <span m="4221280">that</span> <span m="4221470">looks</span> <span m="4221710">like</span>
  <span m="4221930">this.</span> <span m="4223350">How do I</span> <span m="4223850">solve</span>
  <span m="4224020">that</span> <span m="4224380">equation?</span></p><p><span m="4230110">If</span>
  <span m="4230250">I</span> <span m="4230330">get</span> <span m="4230750">any</span>
  <span m="4231030">answer</span> <span m="4232120">that</span> <span m="4232330">is</span>
  <span m="4233070">good,</span> <span m="4233600">I''m</span> <span m="4233860">going</span>
  <span m="4234020">to</span> <span m="4234110">end this</span> <span m="4234586">class.</span>
  <span m="4241210">u n</span> <span m="4241710">is</span> <span m="4241890">known,</span>
  <span m="4242270">right?</span> <span m="4242560">I''m</span> <span m="4243030">at</span>
  <span m="4243350">the</span> <span m="4243500">nth</span> <span m="4244090">concept.</span>
  <span m="4244560">So</span> <span m="4245170">u n</span> <span m="4245560">is</span>
  <span m="4245760">known.</span> <span m="4246420">Let</span> <span m="4246980">me</span>
  <span m="4247230">put</span> <span m="4247650">unknown</span> <span m="4248070">in</span>
  <span m="4248490">read.</span> <span m="4249240">u n</span> <span m="4249515">plus</span>
  <span m="4249790">1</span> <span m="4251210">and</span> <span m="4251460">the</span>
  <span m="4251540">known</span> <span m="4252040">in</span> <span m="4252360">blue.</span></p><p><span
  m="4275800">Yeah,</span> <span m="4276040">that makes</span> <span m="4276290">it</span>
  <span m="4276370">a</span> <span m="4276720">quadratic</span> <span m="4277070">equation.</span>
  <span m="4279364">We</span> <span m="4279850">get</span> <span m="4280310">an</span>
  <span m="4280530">unknown</span> <span m="4280790">square,</span> <span m="4281722">a</span>
  <span m="4282188">linear,</span> <span m="4283120">and</span> <span m="4283586">a</span>
  <span m="4284052">[INAUDIBLE].</span> <span m="4285160">So</span> <span m="4285530">we</span>
  <span m="4285960">can</span> <span m="4286390">see</span> <span m="4286820">we need
  to</span> <span m="4287250">solve a</span> <span m="4287680">quadratic</span> <span
  m="4288110">equation now</span> <span m="4288540">in</span> <span m="4288760">order</span>
  <span m="4289070">to</span> <span m="4290040">go</span> <span m="4290210">from</span>
  <span m="4290390">one</span> <span m="4290710">step</span> <span m="4291080">to</span>
  <span m="4291180">the</span> <span m="4291240">next</span> <span m="4291510">step.</span>
  <span m="4293600">We</span> <span m="4293740">need</span> <span m="4293920">to solve</span>
  <span m="4294600">[INAUDIBLE]</span> <span m="4294980">nonlinear</span> <span m="4295560">equation</span>
  <span m="4296485">to</span> <span m="4296800">go</span> <span m="4297050">from</span>
  <span m="4297310">one</span> <span m="4297580">step</span> <span m="4297770">to</span>
  <span m="4297860">the</span> <span m="4298080">next</span> <span m="4298560">step.</span></p><p><span
  m="4299520">And</span> <span m="4299720">what</span> <span m="4300000">if this</span>
  <span m="4300382">is</span> <span m="4300764">q?</span> <span m="4301850">Then I</span>
  <span m="4302328">need</span> <span m="4302806">to</span> <span m="4303284">solve</span>
  <span m="4303762">a</span> <span m="4304240">[INAUDIBLE].</span> <span m="4305200">What
  is</span> <span m="4305560">this</span> <span m="4306046">for?</span> <span m="4307018">I  need
  to</span> <span m="4307504">solve</span> <span m="4307990">[INAUDIBLE].</span></p><p><span
  m="4311890">What</span> <span m="4312100">if this</span> <span m="4312290">is</span>
  <span m="4313670">final</span> <span m="4314141">u</span> <span m="4314612">times</span>
  <span m="4315554">exponential</span> <span m="4316025">u.</span> <span m="4318860">So</span>
  <span m="4319010">this</span> <span m="4319300">is</span> <span m="4319550">what</span>
  <span m="4319910">we</span> <span m="4320030">are</span> <span m="4320080">going</span>
  <span m="4320200">to</span> <span m="4320260">be</span> <span m="4320380">reading</span>
  <span m="4322020">from</span> <span m="4322540">now</span> <span m="4322970">to</span>
  <span m="4323180">Monday.</span> <span m="4324860">You</span> <span m="4324980">are</span>
  <span m="4325130">going to be</span> <span m="4325380">reading</span> <span m="4325870">about</span>
  <span m="4326700">one</span> <span m="4327030">of</span> <span m="4327140">the</span>
  <span m="4327220">most</span> <span m="4327480">important</span> <span m="4328080">techniques</span>
  <span m="4329016">in</span> <span m="4329484">numerical</span> <span m="4329952">analysis--</span>
  <span m="4330420">that</span> <span m="4330600">is</span> <span m="4330850">how</span>
  <span m="4331140">to solve</span> <span m="4332400">a</span> <span m="4332670">general</span>
  <span m="4332995">nonlinear</span> <span m="4333320">equation</span> <span m="4334280">like</span>
  <span m="4334760">this--</span> <span m="4335720">something</span> <span m="4335990">that</span>
  <span m="4336260">is</span> <span m="4336757">even</span> <span m="4337254">more</span>
  <span m="4337751">complex</span> <span m="4338248">than</span> <span m="4338745">a</span>
  <span m="4339242">quadratic</span> <span m="4340236">equation,</span> <span m="4340740">more</span>
  <span m="4340980">complex</span> <span m="4341442">than</span> <span m="4341904">cubic</span>
  <span m="4342366">equation,</span> <span m="4342830">something</span> <span m="4342950">that
  you may</span> <span m="4343150">not</span> <span m="4343430">have</span> <span
  m="4343700">analytical</span> <span m="4344005">solutions.</span></p><p><span m="4345220">And</span>
  <span m="4345660">it</span> <span m="4345850">is</span> <span m="4346040">extremely</span>
  <span m="4346920">useful</span> <span m="4347480">[INAUDIBLE]</span> <span m="4349270">of</span>
  <span m="4349970">nonlinear</span> <span m="4350340">equations,</span> <span m="4351284">such</span>
  <span m="4351756">as</span> <span m="4352228">[INAUDIBLE]</span> <span m="4353172">over</span>
  <span m="4353644">here.</span> <span m="4354700">So</span> <span m="4354900">I''ll</span>
  <span m="4355210">see</span> <span m="4355400">you</span> <span m="4355550">on</span>
  <span m="4356150">Monday.</span></p>'
type: course
uid: 746f4122d95cc3c2ef335f714bb892a4

---
None