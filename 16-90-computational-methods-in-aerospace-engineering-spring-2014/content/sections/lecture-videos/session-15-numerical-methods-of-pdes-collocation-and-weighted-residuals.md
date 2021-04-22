---
about_this_resource_text: <p><strong>Description:</strong> This session continues
  exploring the finite element method for PDEs. Professor Willcox works through a
  model problem and discusses the collocation method and method of weighted residuals.</p>
  <p><strong>Instructor:</strong> Karen Willcox</p> <p>The recording quality of this
  video is the best available from the source.</p>
course_id: 16-90-computational-methods-in-aerospace-engineering-spring-2014
embedded_media:
- id: Video-YouTube-Stream
  media_location: le8rBOOV-Xs
  parent_uid: d043f5ddc59e8303ffe8b0fff282f32a
  title: Video-YouTube-Stream
  type: Video
  uid: a088c33b918e5d4cb07c7104c572cac2
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/le8rBOOV-Xs/default.jpg
  parent_uid: d043f5ddc59e8303ffe8b0fff282f32a
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 1da20f2d64f2695c870ac6127a1b7720
- id: 3Play-3PlayYouTubeid-MP4
  media_location: le8rBOOV-Xs
  parent_uid: d043f5ddc59e8303ffe8b0fff282f32a
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 5247d4998d7a4a40b08984bef35640af
- id: le8rBOOV-Xs.srt
  parent_uid: d043f5ddc59e8303ffe8b0fff282f32a
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-15-numerical-methods-of-pdes-collocation-and-weighted-residuals/le8rBOOV-Xs.srt
  title: 3play caption file
  type: null
  uid: 723cbb0ad8b67ee0a42c60877fc7ea64
- id: le8rBOOV-Xs.pdf
  parent_uid: d043f5ddc59e8303ffe8b0fff282f32a
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-15-numerical-methods-of-pdes-collocation-and-weighted-residuals/le8rBOOV-Xs.pdf
  title: 3play pdf file
  type: null
  uid: fa68aba3eaf8a97bd4a2ce7d552c192b
- id: Caption-3Play YouTube id-SRT
  parent_uid: d043f5ddc59e8303ffe8b0fff282f32a
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 61ed443c9a57f9fca92f170440d54da9
- id: Transcript-3Play YouTube id-PDF
  parent_uid: d043f5ddc59e8303ffe8b0fff282f32a
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 76f314f7df104db561f20a17e93b70c4
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT16.90S14/MIT16_90S14_L15_300k.mp4
  parent_uid: d043f5ddc59e8303ffe8b0fff282f32a
  title: Video-Internet Archive-MP4
  type: Video
  uid: 67aa42b2f36af3252bfab4d4ed737d05
inline_embed_id: 53321494session15:numericalmethodsofpdes:collocationandweightedresiduals67364729
layout: video
order_index: null
parent_uid: 809ebf7c44bfb36e8786306747d7e32f
related_resources_text: ''
short_url: session-15-numerical-methods-of-pdes-collocation-and-weighted-residuals
technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-15-numerical-methods-of-pdes-collocation-and-weighted-residuals
template_type: Tabbed
title: 'Session 15: Numerical Methods of PDEs: Collocation and Weighted Residuals'
transcript: '<p><span m="30">The</span> <span m="130">following</span> <span m="600">content</span>
  <span m="1090">is</span> <span m="1210">provided</span> <span m="1660">under</span>
  <span m="1900">a</span> <span m="1950">Creative</span> <span m="2400">Commons</span>
  <span m="2820">license.</span> <span m="3780">Your</span> <span m="3880">support</span>
  <span m="4390">will</span> <span m="4560">help</span> <span m="4790">MIT</span>
  <span m="5280">OpenCourseWare</span> <span m="6020">continue</span> <span m="6510">to</span>
  <span m="6680">offer</span> <span m="6980">high</span> <span m="7200">quality</span>
  <span m="7680">educational</span> <span m="8350">resources</span> <span m="8920">for</span>
  <span m="9040">free.</span> <span m="10100">To</span> <span m="10130">make</span>
  <span m="10330">a</span> <span m="10370">donation</span> <span m="11090">or</span>
  <span m="11310">to</span> <span m="11430">view</span> <span m="11640">additional</span>
  <span m="12050">materials</span> <span m="12670">from</span> <span m="12860">hundreds</span>
  <span m="13180">of</span> <span m="13280">MIT</span> <span m="13650">courses,</span>
  <span m="14950">visit</span> <span m="15150">MIT</span> <span m="15670">OpenCourseWare</span>
  <span m="16580">at</span> <span m="16770">ocw.mit.edu.</span></p><p><span m="26300">PROFESSOR:
  All</span> <span m="26400">right.</span> <span m="26730">So</span> <span m="27170">you</span>
  <span m="27270">guys</span> <span m="27430">have</span> <span m="27570">read</span>
  <span m="27730">all</span> <span m="27850">about</span> <span m="28140">method of</span>
  <span m="28440">weighted</span> <span m="28730">residuals.</span> <span m="29890">Yes?</span>
  <span m="30920">Makes</span> <span m="31210">perfect</span> <span m="31540">sense.</span>
  <span m="33970">Yes?</span> <span m="35800">We</span> <span m="35920">need</span>
  <span m="36020">to</span> <span m="36090">go</span> <span m="36240">through</span>
  <span m="36470">things</span> <span m="36890">today?</span> <span m="38230">A</span>
  <span m="38330">little</span> <span m="38560">bit.</span> <span m="38910">OK.</span>
  <span m="39360">Just</span> <span m="39520">a</span> <span m="39560">little</span>
  <span m="39750">bit.</span> <span m="40710">All</span> <span m="40770">right.</span></p><p><span
  m="41540">So--</span> <span m="44710">actually,</span> <span m="44960">but</span>
  <span m="45240">before</span> <span m="45590">we</span> <span m="45730">do</span>
  <span m="45950">that,</span> <span m="49100">I</span> <span m="49130">want</span>
  <span m="49480">to--</span> <span m="61450">[INAUDIBLE]</span> <span m="64069">[?
  Let''s ?]</span> <span m="64470">put</span> <span m="64629">up</span> <span m="64769">a</span>
  <span m="64800">list</span> <span m="64989">of</span> <span m="65069">topics</span>
  <span m="65430">that</span> <span m="65470">we''re</span> <span m="65560">going</span>
  <span m="65680">to</span> <span m="65750">talk</span> <span m="66010">about</span>
  <span m="66520">today.</span></p><p><span m="67710">So</span> <span m="71740">I</span>
  <span m="71840">want</span> <span m="72020">to</span> <span m="72100">start</span>
  <span m="72440">by</span> <span m="72580">just</span> <span m="74510">talking</span>
  <span m="74760">about</span> <span m="74910">the</span> <span m="74980">measurable</span>
  <span m="75310">outcomes</span> <span m="75860">for</span> <span m="75950">the</span>
  <span m="76030">module.</span> <span m="76410">Remind</span> <span m="76820">you</span>
  <span m="76940">of</span> <span m="77060">what</span> <span m="77200">it</span>
  <span m="77300">is</span> <span m="77510">we''re</span> <span m="77630">going</span>
  <span m="77830">to</span> <span m="77900">do.</span> <span m="78730">Then</span>
  <span m="78990">we''re</span> <span m="79100">going</span> <span m="79220">to</span>
  <span m="79290">introduce</span> <span m="79720">the</span> <span m="79760">model</span>
  <span m="80100">problem.</span> <span m="80530">You</span> <span m="80690">read</span>
  <span m="80920">this</span> <span m="81300">in</span> <span m="83940">the</span>
  <span m="84790">pre-class</span> <span m="85170">reading.</span> <span m="85870">But</span>
  <span m="86010">it''s</span> <span m="86140">the</span> <span m="86230">steady</span>
  <span m="86590">1D</span> <span m="87030">diffusion.</span> <span m="88510">And</span>
  <span m="89570">we''ll</span> <span m="89750">do</span> <span m="89890">a</span>
  <span m="89980">few</span> <span m="90380">things</span> <span m="91110">in</span>
  <span m="91340">general,</span> <span m="91820">but</span> <span m="92040">more</span>
  <span m="92370">or</span> <span m="92420">less</span> <span m="92730">we''re</span>
  <span m="92820">going</span> <span m="93140">to</span> <span m="93250">develop</span>
  <span m="93780">the</span> <span m="94780">[INAUDIBLE]</span> <span m="95820">by</span>
  <span m="95940">thinking</span> <span m="96230">about</span> <span m="96450">this</span>
  <span m="96550">specific</span> <span m="97110">example.</span> <span m="98510">We''re</span>
  <span m="98670">going</span> <span m="98790">to</span> <span m="98880">talk</span>
  <span m="99160">about</span> <span m="99690">the</span> <span m="99810">idea</span>
  <span m="100110">of</span> <span m="100180">approximating</span> <span m="101020">the</span>
  <span m="101100">solution</span> <span m="103000">with</span> <span m="103250">basis</span>
  <span m="103610">functions,</span> <span m="104250">which</span> <span m="104500">is</span>
  <span m="105490">a</span> <span m="105580">fundamentally</span> <span m="106260">different</span>
  <span m="106650">way</span> <span m="107493">of</span> <span m="108380">doing the</span>
  <span m="108510">approximation</span> <span m="109350">compared</span> <span m="109640">to</span>
  <span m="109730">what</span> <span m="109880">you''ve</span> <span m="109990">already</span>
  <span m="110190">seen</span> <span m="110460">in</span> <span m="110580">finite</span>
  <span m="110870">difference</span> <span m="111300">and</span> <span m="111470">finite</span>
  <span m="111950">volume.</span> <span m="112940">Then</span> <span m="113230">we''ll</span>
  <span m="114160">look</span> <span m="114500">at</span> <span m="114600">the</span>
  <span m="114670">collocation</span> <span m="115410">method.</span> <span m="118610">And</span>
  <span m="118880">then</span> <span m="119120">finally,</span> <span m="119620">we''ll</span>
  <span m="119820">get</span> <span m="120040">to</span> <span m="120180">the</span>
  <span m="120260">method</span> <span m="120550">of</span> <span m="120650">weighted</span>
  <span m="121010">residuals.</span></p><p><span m="126240">OK.</span> <span m="126730">So</span>
  <span m="129310">what</span> <span m="129539">I''m</span> <span m="129650">going</span>
  <span m="129770">to</span> <span m="129850">do</span> <span m="130389">on</span>
  <span m="130539">the</span> <span m="130620">board</span> <span m="131039">is</span>
  <span m="131210">more</span> <span m="131430">or</span> <span m="131480">less</span>
  <span m="131750">paralleling</span> <span m="132600">what''s</span> <span m="132840">in</span>
  <span m="132960">the notes.</span> <span m="135715">And</span> <span m="136180">so</span>
  <span m="136330">I</span> <span m="136420">can</span> <span m="136590">go</span>
  <span m="136790">quickly</span> <span m="137210">on</span> <span m="137330">the</span>
  <span m="137410">thoughts</span> <span m="137792">that</span> <span m="138174">are</span>
  <span m="138940">already</span> <span m="139250">clear,</span> <span m="139630">and</span>
  <span m="139930">we</span> <span m="140010">can</span> <span m="140150">spend</span>
  <span m="141930">more</span> <span m="142140">time</span> <span m="142360">on</span>
  <span m="142450">the</span> <span m="142520">parts</span> <span m="143230">that</span>
  <span m="143440">you</span> <span m="144080">have</span> <span m="144240">found</span>
  <span m="144500">to</span> <span m="144590">be</span> <span m="144690">confusing.</span></p><p><span
  m="147917">OK.</span> <span m="148380">So</span> <span m="148580">I''m</span> <span
  m="148670">not</span> <span m="148780">going</span> <span m="148900">to</span> <span
  m="148990">put</span> <span m="149170">the</span> <span m="149240">screen</span>
  <span m="149520">down</span> <span m="149720">because</span> <span m="149880">it''ll</span>
  <span m="150030">take</span> <span m="150210">a</span> <span m="150240">while</span>
  <span m="150380">to</span> <span m="150450">get</span> <span m="150600">the</span>
  <span m="150680">projector</span> <span m="151010">on,</span> <span m="151360">but</span>
  <span m="151710">I</span> <span m="151780">just</span> <span m="151940">want</span>
  <span m="152090">to</span> <span m="152180">remind</span> <span m="152600">you</span>
  <span m="152830">that</span> <span m="153790">there''s</span> <span m="154240">the</span>
  <span m="154290">measurable</span> <span m="154630">outcome</span> <span m="155060">list</span>
  <span m="156600">embedded</span> <span m="156760">on</span> <span m="156870">the</span>
  <span m="157250">MIT</span> <span m="157920">site.</span> <span m="158260">It''s
  also</span> <span m="158610">on</span> <span m="159020">the</span> <span m="159210">mitosis.mitx.mit.edu</span>
  <span m="159565">site.</span></p><p><span m="162760">And</span> <span m="162960">so</span>
  <span m="163090">we''re</span> <span m="163560">into</span> <span m="163830">a</span>
  <span m="163890">new</span> <span m="164130">module</span> <span m="165000">now.</span>
  <span m="165320">There</span> <span m="165460">are</span> <span m="165510">four</span>
  <span m="165760">modules</span> <span m="166110">in</span> <span m="166210">the</span>
  <span m="166290">class.</span> <span m="166670">The first one</span> <span m="167140">was</span>
  <span m="167340">integration</span> <span m="167870">methods</span> <span m="168260">for</span>
  <span m="168650">ODEs.</span> <span m="169430">The</span> <span m="169520">second</span>
  <span m="169820">one</span> <span m="170150">was</span> <span m="170860">finite</span>
  <span m="171140">difference</span> <span m="171550">and</span> <span m="171690">finite</span>
  <span m="171770">volume</span> <span m="172090">methods.</span> <span m="173020">And</span>
  <span m="173150">the</span> <span m="173210">third</span> <span m="173470">one</span>
  <span m="173650">now,</span> <span m="173910">which</span> <span m="174170">is</span>
  <span m="175060">finite</span> <span m="175410">element</span> <span m="175740">methods</span>
  <span m="176080">for</span> <span m="176230">PDE.</span></p><p><span m="177390">And</span>
  <span m="177660">so</span> <span m="177810">I</span> <span m="177870">think</span>
  <span m="178080">it''s</span> <span m="178220">really</span> <span m="178400">helpful</span>
  <span m="178860">for</span> <span m="179000">you</span> <span m="179100">to</span>
  <span m="179160">go</span> <span m="179290">back</span> <span m="179580">and--</span>
  <span m="180590">well</span> <span m="180940">to</span> <span m="181010">go</span>
  <span m="181170">forward</span> <span m="181550">at</span> <span m="181620">this</span>
  <span m="181780">point--</span> <span m="182060">and</span> <span m="182220">look
  at</span> <span m="182310">the</span> <span m="182440">outcomes,</span> <span m="183000">and</span>
  <span m="183140">think</span> <span m="183380">about</span> <span m="183720">specifically</span>
  <span m="184310">what</span> <span m="184450">it</span> <span m="184550">is</span>
  <span m="184770">you''re</span> <span m="184860">going</span> <span m="184990">to</span>
  <span m="185340">have</span> <span m="185530">to</span> <span m="185630">be</span>
  <span m="185720">able</span> <span m="185930">to</span> <span m="186030">do.</span>
  <span m="186330">Because</span> <span m="186710">as you</span> <span m="186850">are</span>
  <span m="186900">going</span> <span m="187200">through</span> <span m="187460">all</span>
  <span m="187660">the</span> <span m="187750">notes,</span> <span m="188100">and</span>
  <span m="188190">I</span> <span m="188230">know</span> <span m="188380">there</span>
  <span m="188500">are</span> <span m="188530">a</span> <span m="188590">lot</span>
  <span m="188790">of</span> <span m="188850">notes</span> <span m="189220">for</span>
  <span m="189290">this</span> <span m="189430">section,</span> <span m="190360">it
  will</span> <span m="190450">help you</span> <span m="190740">think</span> <span
  m="190960">about</span> <span m="191180">what</span> <span m="191280">are</span>
  <span m="191370">the</span> <span m="191460">specific</span> <span m="191930">skills</span>
  <span m="192290">that</span> <span m="192380">need</span> <span m="192785">to</span>
  <span m="193190">take</span> <span m="193410">away.</span> <span m="193760">There''ll</span>
  <span m="193900">be</span> <span m="195060">homework</span> <span m="195120">problems</span>
  <span m="195570">and</span> <span m="195720">a</span> <span m="195780">project</span>
  <span m="196170">that</span> <span m="196290">will</span> <span m="196410">help</span>
  <span m="196620">you</span> <span m="196720">do</span> <span m="196860">that,</span>
  <span m="197080">too.</span></p><p><span m="197930">But</span> <span m="198630">for</span>
  <span m="198720">example,</span> <span m="199240">describe</span> <span m="199520">how</span>
  <span m="199630">the</span> <span m="199720">method</span> <span m="199980">of</span>
  <span m="200080">weighted</span> <span m="200360">residuals</span> <span m="200910">can</span>
  <span m="201050">be</span> <span m="201150">used</span> <span m="201370">to</span>
  <span m="201450">calculate</span> <span m="201970">an</span> <span m="202060">approximate</span>
  <span m="202620">solution</span> <span m="203160">to the PDE,</span> <span m="203720">we''re</span>
  <span m="204100">going</span> <span m="204250">to</span> <span m="204310">cover</span>
  <span m="204540">that</span> <span m="204710">today.</span> <span m="205540">Then</span>
  <span m="205980">to be</span> <span m="206100">able</span> <span m="206260">to</span>
  <span m="206340">describe</span> <span m="206820">the</span> <span m="206890">differences</span>
  <span m="207550">between</span> <span m="207860">the</span> <span m="207930">method</span>
  <span m="208190">of</span> <span m="208290">weighted</span> <span m="208570">residuals</span>
  <span m="209240">and</span> <span m="209310">the</span> <span m="209380">collocation</span>
  <span m="210060">method,</span> <span m="211040">and</span> <span m="211920">the</span>
  <span m="212040">least</span> <span m="212290">squares</span> <span m="212470">method</span>
  <span m="212770">for</span> <span m="213130">approximating</span> <span m="213390">a</span>
  <span m="213460">PDE.</span></p><p><span m="213900">So</span> <span m="214060">there''s</span>
  <span m="214710">a</span> <span m="214790">lot</span> <span m="214920">of</span>
  <span m="215010">really</span> <span m="215220">specific</span> <span m="216420">outcomes.</span>
  <span m="217630">I think there''s</span> <span m="217960">probably</span> <span
  m="218380">about</span> <span m="218810">12</span> <span m="219130">outcomes</span>
  <span m="219300">that</span> <span m="219470">are</span> <span m="219670">associated</span>
  <span m="220050">with</span> <span m="220150">this</span> <span m="220280">module.</span>
  <span m="220580">Go and</span> <span m="220830">take</span> <span m="221010">a</span>
  <span m="221050">look</span> <span m="221240">at</span> <span m="221330">them,</span>
  <span m="221530">and</span> <span m="221620">I</span> <span m="221670">think</span>
  <span m="221850">that</span> <span m="221960">will</span> <span m="222520">hopefully</span>
  <span m="222860">help you</span> <span m="224820">divide</span> <span m="225100">up</span>
  <span m="225220">the</span> <span m="225290">material,</span> <span m="225760">and</span>
  <span m="225890">think</span> <span m="226090">about</span> <span m="226370">what</span>
  <span m="226500">it</span> <span m="226610">is</span> <span m="227600">that</span>
  <span m="228990">you</span> <span m="229110">need</span> <span m="229260">to</span>
  <span m="229330">be</span> <span m="229410">able</span> <span m="229590">to</span>
  <span m="229700">do.</span></p><p><span m="230830">But</span> <span m="231130">let''s</span>
  <span m="231920">start</span> <span m="232300">off</span> <span m="232770">by</span>
  <span m="234430">thinking</span> <span m="234700">about</span> <span m="234970">our</span>
  <span m="235100">model</span> <span m="235440">problem.</span> <span m="237250">So</span>
  <span m="237470">a</span> <span m="237670">model</span> <span m="237720">problem</span>
  <span m="238110">just</span> <span m="238300">means</span> <span m="238570">a</span>
  <span m="238620">simple</span> <span m="239020">problem</span> <span m="240800">that''</span>
  <span m="241690">we''re</span> <span m="241800">going</span> <span m="241920">to</span>
  <span m="242050">use</span> <span m="242530">to</span> <span m="243170">develop</span>
  <span m="243650">things</span> <span m="244070">on.</span> <span m="245450">And</span>
  <span m="245760">so</span> <span m="246160">the</span> <span m="246230">model</span>
  <span m="246550">problem</span> <span m="247310">again</span> <span m="247590">is</span>
  <span m="248686">steady</span> <span m="250060">1D</span> <span m="250900">heat</span>
  <span m="251210">diffusion</span> <span m="251660">in a rod.</span></p><p><span
  m="257730">And</span> <span m="258399">the</span> <span m="258490">PDE</span> <span
  m="259060">should</span> <span m="259250">be</span> <span m="259850">pretty</span>
  <span m="260060">familiar</span> <span m="261300">[INAUDIBLE]</span> <span m="261430">you</span>
  <span m="261839">by</span> <span m="262019">now.</span> <span m="262665">It''s</span>
  <span m="263140">d by dx of k</span> <span m="265515">[? ct dx ?]</span> <span m="268850">equal</span>
  <span m="269160">to</span> <span m="269330">minus</span> <span m="269830">2.</span>
  <span m="271830">We''re</span> <span m="271990">thinking</span> <span m="272290">about</span>
  <span m="272900">a</span> <span m="273000">1D</span> <span m="273310">domain.</span>
  <span m="275074">So</span> <span m="275515">here''s our</span> <span m="275960">domain.</span>
  <span m="277100">That''s</span> <span m="277340">the</span> <span m="277420">x</span>
  <span m="277680">direction.</span> <span m="279700">The</span> <span m="279800">domain</span>
  <span m="280130">is</span> <span m="280240">going</span> <span m="280370">to</span>
  <span m="280430">have</span> <span m="280690">links</span> <span m="281150">l.</span>
  <span m="282070">So</span> <span m="282460">we''ll</span> <span m="282640">have</span>
  <span m="283070">x</span> <span m="283390">in</span> <span m="283470">general</span>
  <span m="283820">going</span> <span m="284170">from</span> <span m="284380">minus</span>
  <span m="284780">l</span> <span m="284950">over</span> <span m="285190">to</span>
  <span m="285500">plus</span> <span m="285970">l</span> <span m="286170">over</span>
  <span m="286665">2.</span> <span m="289140">The</span> <span m="289240">k</span>
  <span m="289680">sitting</span> <span m="289960">in</span> <span m="290090">here</span>
  <span m="290670">in</span> <span m="290950">general</span> <span m="291810">is</span>
  <span m="292030">going</span> <span m="292190">to</span> <span m="292260">be</span>
  <span m="292370">a</span> <span m="292430">function</span> <span m="292770">of</span>
  <span m="292870">x,</span> <span m="293230">although</span> <span m="293520">you''ll</span>
  <span m="293710">see</span> <span m="293940">that</span> <span m="294220">just</span>
  <span m="294420">to</span> <span m="294490">make</span> <span m="294660">things</span>
  <span m="294890">simple</span> <span m="295140">in</span> <span m="295210">the</span>
  <span m="295290">beginning</span> <span m="296590">we''ll</span> <span m="296920">at</span>
  <span m="297020">some</span> <span m="297260">point</span> <span m="297500">make</span>
  <span m="297800">k</span> <span m="297870">constant.</span> <span m="298540">That''s</span>
  <span m="298780">the</span> <span m="298950">thermal</span> <span m="299240">conductivity</span>
  <span m="299930">of</span> <span m="300050">the</span> <span m="300130">material</span>
  <span m="300760">that</span> <span m="300900">the</span> <span m="300990">rod</span>
  <span m="301220">is</span> <span m="301340">made</span> <span m="301600">out</span>
  <span m="301820">of.</span> <span m="307370">And</span> <span m="308090">this</span>
  <span m="308440">q</span> <span m="309140">on</span> <span m="309690">the</span>
  <span m="309770">right</span> <span m="309940">hand</span> <span m="310170">side</span>
  <span m="310720">also</span> <span m="311460">can</span> <span m="311660">be</span>
  <span m="311790">a</span> <span m="311850">function</span> <span m="312220">of</span>
  <span m="312310">x,</span> <span m="313370">is</span> <span m="313800">the</span>
  <span m="313890">heat</span> <span m="314150">source.</span> <span m="315010">And</span>
  <span m="315080">it''s</span> <span m="315220">actually</span> <span m="315480">heat</span>
  <span m="315680">source</span> <span m="316020">per unit</span> <span m="316320">[INAUDIBLE]</span>
  <span m="318296">to</span> <span m="318790">get units right.</span></p><p><span
  m="324718">OK, so</span> <span m="326210">simple</span> <span m="326560">problem</span>
  <span m="327190">set</span> <span m="327420">up.</span> <span m="330930">PDE</span>
  <span m="332440">specify</span> <span m="332850">heat</span> <span m="333020">source.</span>
  <span m="333910">We''re</span> <span m="334070">also</span> <span m="334270">going</span>
  <span m="334390">to</span> <span m="334450">need</span> <span m="334610">to</span>
  <span m="334690">apply</span> <span m="334910">boundary</span> <span m="335240">conditions</span>
  <span m="335850">when</span> <span m="335990">we</span> <span m="336140">actually</span>
  <span m="336430">get</span> <span m="336750">to</span> <span m="337590">specifying</span>
  <span m="337890">a</span> <span m="338190">particular</span> <span m="338580">problem.</span></p><p><span
  m="340110">So</span> <span m="340420">there''s</span> <span m="341350">one</span>
  <span m="341740">particular</span> <span m="342150">problem</span> <span m="343300">that</span>
  <span m="343500">we</span> <span m="343630">will</span> <span m="344240">use.</span>
  <span m="344680">One</span> <span m="344840">that</span> <span m="344940">we</span>
  <span m="345030">can</span> <span m="345170">compute</span> <span m="345450">the</span>
  <span m="345550">analytical</span> <span m="346040">solution</span> <span m="346530">for
  it.</span> <span m="346840">Because</span> <span m="347130">if</span> <span m="347230">we</span>
  <span m="347360">can</span> <span m="347540">compute</span> <span m="347840">an</span>
  <span m="348060">analytical</span> <span m="348690">solution,</span> <span m="349680">we''ll</span>
  <span m="349980">be able to look</span> <span m="350240">at</span> <span m="350330">errors</span>
  <span m="350710">and</span> <span m="350870">things</span> <span m="351170">when</span>
  <span m="351330">we</span> <span m="352000">look</span> <span m="352170">at</span>
  <span m="352280">the</span> <span m="352350">numerical</span> <span m="352780">approximation.</span>
  <span m="354450">So for</span> <span m="354530">the</span> <span m="354610">particular</span>
  <span m="355180">case</span> <span m="356032">where k</span> <span m="356460">is</span>
  <span m="356590">a</span> <span m="356630">constant</span> <span m="357350">and</span>
  <span m="357470">equal</span> <span m="357750">to</span> <span m="357920">1,</span>
  <span m="359390">the</span> <span m="359950">length</span> <span m="360250">of</span>
  <span m="360360">the</span> <span m="360490">rod</span> <span m="360830">is</span>
  <span m="361050">2,</span> <span m="361500">so</span> <span m="361750">that</span>
  <span m="361900">x</span> <span m="362120">goes</span> <span m="362380">from</span>
  <span m="362550">minus</span> <span m="362940">1</span> <span m="363620">to</span>
  <span m="363770">plus</span> <span m="364170">1,</span> <span m="365220">and</span>
  <span m="365870">the</span> <span m="365940">heat</span> <span m="367240">source</span>
  <span m="367820">is</span> <span m="368607">q of x</span> <span m="369740">being</span>
  <span m="370100">50</span> <span m="370580">e</span> <span m="370840">to</span>
  <span m="370900">the</span> <span m="371020">x.</span> <span m="371190">And again,</span>
  <span m="371500">this</span> <span m="371650">is</span> <span m="371750">the</span>
  <span m="371830">same</span> <span m="372020">example</span> <span m="372420">that''s</span>
  <span m="372590">in the</span> <span m="372660">notes.</span> <span m="374810">And</span>
  <span m="375430">boundary</span> <span m="375850">conditions,</span> <span m="377410">the</span>
  <span m="377510">temperature</span> <span m="379030">at</span> <span m="379780">the</span>
  <span m="380510">right</span> <span m="380840">end</span> <span m="381060">of</span>
  <span m="381150">the</span> <span m="381260">rod</span> <span m="381700">is</span>
  <span m="381860">set</span> <span m="382080">to</span> <span m="382210">be</span>
  <span m="382340">100,</span> <span m="383950">and</span> <span m="384320">the</span>
  <span m="384380">temperature</span> <span m="384880">at</span> <span m="385140">the</span>
  <span m="386050">left</span> <span m="386390">end</span> <span m="386580">of the</span>
  <span m="386930">rod</span> <span m="387185">is set</span> <span m="387440">to</span>
  <span m="387570">be</span> <span m="387720">100.</span></p><p><span m="389340">OK,
  so</span> <span m="389840">for</span> <span m="389980">that</span> <span m="390270">particular</span>
  <span m="391760">case</span> <span m="392780">we</span> <span m="392950">have</span>
  <span m="393100">an</span> <span m="393210">analytical</span> <span m="393890">solution</span>
  <span m="394480">you</span> <span m="395291">can get</span> <span m="395752">by</span>
  <span m="398060">integrating</span> <span m="398600">the</span> <span m="399087">PDE.</span>
  <span m="400550">And</span> <span m="400650">that turns</span> <span m="400950">out</span>
  <span m="401200">to</span> <span m="401350">be</span> <span m="402690">t of x</span>
  <span m="404860">is</span> <span m="405100">minus</span> <span m="405510">50x</span>
  <span m="405989">to the x,</span> <span m="407905">plus</span> <span m="409821">50x</span>
  <span m="411250">the</span> <span m="411370">hyperbolic</span> <span m="412040">sign</span>
  <span m="412920">of</span> <span m="413350">1,</span> <span m="416370">plus</span>
  <span m="417150">100,</span> <span m="418680">plus</span> <span m="419020">50</span>
  <span m="419620">times</span> <span m="420540">the hyperbolic</span> <span m="420845">cosign</span>
  <span m="422570">of</span> <span m="422870">1.</span> <span m="425060">OK,</span>
  <span m="425500">so that''s</span> <span m="425700">just</span> <span m="425890">what</span>
  <span m="426060">comes</span> <span m="426320">out</span> <span m="426530">of</span>
  <span m="427280">this</span> <span m="427410">analytic.</span></p><p><span m="429340">[INAUDIBLE]</span>
  <span m="429760">and</span> <span m="429940">that''s</span> <span m="430170">maybe</span>
  <span m="430550">a little</span> <span m="431000">bit hard</span> <span m="431390">to</span>
  <span m="431690">think</span> <span m="431950">about,</span> <span m="432500">so</span>
  <span m="432620">let''s</span> <span m="432820">just</span> <span m="433020">sketch</span>
  <span m="433490">what</span> <span m="433800">t of x</span> <span m="434450">looks
  like</span> <span m="434730">as</span> <span m="434820">a</span> <span m="434920">function</span>
  <span m="435230">of</span> <span m="435340">x.</span> <span m="436620">So</span>
  <span m="436770">there''s</span> <span m="437410">x</span> <span m="437860">going</span>
  <span m="438260">from</span> <span m="438650">minus</span> <span m="439120">1</span>
  <span m="440350">to</span> <span m="440520">1.</span> <span m="443270">We''ve</span>
  <span m="443470">taken</span> <span m="443830">x</span> <span m="444130">equal</span>
  <span m="444530">to</span> <span m="444970">0--</span> <span m="446850">I mean</span>
  <span m="447060">x</span> <span m="447260">equal</span> <span m="447450">to</span>
  <span m="447540">minus</span> <span m="447910">1.</span> <span m="448160">Then</span>
  <span m="448280">we</span> <span m="448350">should</span> <span m="448500">be</span>
  <span m="448570">getting</span> <span m="448930">the</span> <span m="449200">boundary</span>
  <span m="449500">condition</span> <span m="449880">back,</span> <span m="450150">t
  is</span> <span m="450420">100.</span> <span m="451450">So</span> <span m="451640">if</span>
  <span m="451780">we</span> <span m="451930">make</span> <span m="452190">this</span>
  <span m="452380">100</span> <span m="456460">on</span> <span m="456660">my</span>
  <span m="456800">t-axis,</span> <span m="458570">then</span> <span m="458790">the</span>
  <span m="458870">solution</span> <span m="459330">looks</span> <span m="460470">something</span>
  <span m="460770">like</span> <span m="460990">this.</span> <span m="461350">And</span>
  <span m="461450">it</span> <span m="461550">comes</span> <span m="461630">back</span>
  <span m="461870">to</span> <span m="462060">100</span> <span m="462560">at the other</span>
  <span m="463060">end.</span></p><p><span m="468250">OK.</span> <span m="468580">So</span>
  <span m="468910">that''s</span> <span m="469160">an</span> <span m="469400">analytic</span>
  <span m="470050">solution</span> <span m="470540">that</span> <span m="470650">we</span>
  <span m="470740">can</span> <span m="470910">compute.</span> <span m="471270">And</span>
  <span m="471370">again,</span> <span m="471570">we''re</span> <span m="471660">just</span>
  <span m="471850">doing</span> <span m="472080">that</span> <span m="472300">because</span>
  <span m="472690">when</span> <span m="472840">we</span> <span m="472940">start</span>
  <span m="473250">looking</span> <span m="473500">at the</span> <span m="473590">[?
  miracle ?]</span> <span m="474010">approximations,</span> <span m="474720">we''re</span>
  <span m="474860">going to</span> <span m="474890">want</span> <span m="475110">something</span>
  <span m="475350">to</span> <span m="475450">compare</span> <span m="475840">to.</span>
  <span m="476070">So</span> <span m="477480">a simple</span> <span m="478470">problem</span>
  <span m="478800">where we</span> <span m="479030">can</span> <span m="479190">actually</span>
  <span m="479460">and</span> <span m="479710">integrate</span> <span m="480130">things</span>
  <span m="480380">analytically.</span></p><p><span m="484690">OK?</span> <span m="486210">Yep.</span>
  <span m="487920">Think I''ve told</span> <span m="488190">you</span> <span m="488300">anything.</span></p><p><span
  m="489170">All</span> <span m="489240">right.</span> <span m="490296">So</span>
  <span m="490690">let''s</span> <span m="490920">now</span> <span m="491120">start</span>
  <span m="491470">thinking</span> <span m="491880">about</span> <span m="492880">the</span>
  <span m="492990">solution</span> <span m="493400">approximation.</span> <span m="495620">Can</span>
  <span m="495790">I--</span> <span m="498130">again,</span> <span m="498380">everything</span>
  <span m="498770">I''m</span> <span m="499350">writing</span> <span m="500170">is</span>
  <span m="500400">scanned</span> <span m="500886">in</span> <span m="501372">online,</span>
  <span m="501858">so--</span> <span m="503320">I</span> <span m="503410">know</span>
  <span m="503540">it''s</span> <span m="503680">good</span> <span m="503850">to</span>
  <span m="503910">copy</span> <span m="504190">stuff</span> <span m="504460">down</span>
  <span m="504700">and</span> <span m="504830">help</span> <span m="505298">follow</span>
  <span m="506234">along,</span> <span m="506702">but</span> <span m="507170">also</span>
  <span m="507420">you</span> <span m="507570">will</span> <span m="508710">have</span>
  <span m="508830">copies</span> <span m="509130">of</span> <span m="509190">the</span>
  <span m="509250">full</span> <span m="509510">notes.</span></p><p><span m="509720">So</span>
  <span m="509920">now</span> <span m="509970">let''s</span> <span m="510170">start</span>
  <span m="510460">thinking</span> <span m="510700">up</span> <span m="510830">this</span>
  <span m="511020">idea</span> <span m="511510">of</span> <span m="512440">approximating</span>
  <span m="513240">the</span> <span m="513299">solution.</span> <span m="513940">So
  first</span> <span m="518130">let</span> <span m="518360">me</span> <span m="518975">ask,</span>
  <span m="521200">if</span> <span m="521370">we</span> <span m="521480">were</span>
  <span m="521559">going</span> <span m="521679">to</span> <span m="521750">solve</span>
  <span m="522590">this</span> <span m="522870">problem</span> <span m="523830">using</span>
  <span m="524179">finite</span> <span m="524530">differences,</span> <span m="525110">what</span>
  <span m="525270">would</span> <span m="525480">we</span> <span m="525630">do?</span>
  <span m="533880">We''d run</span> <span m="534050">to</span> <span m="534380">Alex</span>
  <span m="534730">and</span> <span m="534820">ask</span> <span m="535030">him</span>
  <span m="535130">to</span> <span m="535210">help</span> <span m="535480">us?</span>
  <span m="536520">What</span> <span m="536650">would</span> <span m="536790">we</span>
  <span m="536900">do</span> <span m="537090">if</span> <span m="537260">we</span>
  <span m="537410">wanted</span> <span m="537560">to</span> <span m="537670">solve</span>
  <span m="537910">this</span> <span m="538050">problem</span> <span m="538340">using</span>
  <span m="538550">finite</span> <span m="538790">differences?</span></p><p><span
  m="543540">We''d</span> <span m="543670">break</span> <span m="543940">up</span>
  <span m="544050">the</span> <span m="544140">domain</span> <span m="544570">into</span>
  <span m="544780">a</span> <span m="544830">bunch</span> <span m="545140">of</span>
  <span m="545780">cells,</span> <span m="546610">and</span> <span m="546740">then</span>
  <span m="546870">what?</span> <span m="547380">How</span> <span m="547650">would</span>
  <span m="547790">we</span> <span m="547920">approximate</span> <span m="548305">things?</span></p><p><span
  m="553680">AUDIENCE: [INAUDIBLE]</span></p><p><span m="565157">PROFESSOR: Yeah.</span>
  <span m="565656">Good.</span> <span m="566160">So</span> <span m="566310">we</span>
  <span m="566420">would</span> <span m="566570">decide</span> <span m="567130">what</span>
  <span m="567320">kind</span> <span m="567540">of</span> <span m="567650">a</span>
  <span m="567960">scheme</span> <span m="568300">we</span> <span m="568400">wanted</span>
  <span m="568670">to</span> <span m="568800">use,</span> <span m="569280">and</span>
  <span m="569400">we</span> <span m="569480">would</span> <span m="569590">approximate</span>
  <span m="570090">the</span> <span m="570150">derivatives.</span> <span m="571010">And</span>
  <span m="571420">that''s kind of</span> <span m="571500">the</span> <span m="572260">key</span>
  <span m="572430">part</span> <span m="572950">of</span> <span m="573600">[INAUDIBLE],</span>
  <span m="574190">is</span> <span m="574290">that</span> <span m="574420">we</span>
  <span m="574540">would</span> <span m="575070">take</span> <span m="575290">this--</span>
  <span m="575450">we''d</span> <span m="575650">take</span> <span m="576010">k</span>
  <span m="576150">equal</span> <span m="576650">1</span> <span m="576915">constant.</span>
  <span m="577180">So basically</span> <span m="577590">we''ve</span> <span m="577760">got
  a</span> <span m="577790">second</span> <span m="578060">derivative</span> <span
  m="578410">the</span> <span m="578570">t</span> <span m="578780">sitting</span>
  <span m="579050">here.</span> <span m="579760">We</span> <span m="579930">would</span>
  <span m="580020">approximate</span> <span m="580560">it</span> <span m="580690">using</span>
  <span m="581170">our</span> <span m="581320">favorite</span> <span m="581780">finite</span>
  <span m="582240">difference</span> <span m="582650">[INAUDIBLE].</span> <span m="582760">So</span>
  <span m="582880">maybe</span> <span m="583150">the</span> <span m="583952">central</span>
  <span m="584290">difference</span> <span m="585510">for the</span> <span m="585660">second</span>
  <span m="585900">derivative.</span></p><p><span m="587250">So</span> <span m="588050">I</span>
  <span m="588110">think</span> <span m="588290">it''s</span> <span m="588440">really</span>
  <span m="588680">key</span> <span m="588840">to</span> <span m="588900">keep</span>
  <span m="589090">in</span> <span m="589170">mind</span> <span m="589350">that</span>
  <span m="589410">finite</span> <span m="589640">element</span> <span m="590450">departs</span>
  <span m="591040">from that mentality</span> <span m="592032">right</span> <span
  m="592530">from</span> <span m="592660">the</span> <span m="592740">beginning.</span>
  <span m="593410">That</span> <span m="594300">with</span> <span m="594460">finite</span>
  <span m="594730">elements,</span> <span m="595340">we''re</span> <span m="595480">not</span>
  <span m="595860">going</span> <span m="596240">to</span> <span m="596650">approximate</span>
  <span m="598550">the</span> <span m="599580">derivative</span> <span m="600060">here.</span>
  <span m="600260">We''re not going to</span> <span m="600450">approximate</span>
  <span m="601350">this</span> <span m="601610">operator,</span> <span m="602110">this</span>
  <span m="603230">d</span> <span m="603380">squared</span> <span m="603790">by</span>
  <span m="604160">dx</span> <span m="604455">squared</span> <span m="604750">that''s</span>
  <span m="605060">acting on</span> <span m="605280">t.</span> <span m="606390">With</span>
  <span m="606710">finite</span> <span m="607180">elements, we''re</span> <span m="607280">going</span>
  <span m="607400">to</span> <span m="607510">assume</span> <span m="608020">a</span>
  <span m="608090">form</span> <span m="608810">for</span> <span m="609200">the</span>
  <span m="609300">solution</span> <span m="609605">t,</span> <span m="610830">and</span>
  <span m="610940">approximate</span> <span m="611260">the</span> <span m="611580">solution.</span>
  <span m="611930">We''re</span> <span m="612010">going</span> <span m="612130">to</span>
  <span m="612200">assume</span> <span m="612480">a</span> <span m="612540">form</span>
  <span m="612800">for</span> <span m="612900">the</span> <span m="612970">solution</span>
  <span m="613530">t,</span> <span m="614030">and</span> <span m="614410">we''re</span>
  <span m="614550">going</span> <span m="614670">to</span> <span m="614740">substitute</span>
  <span m="615180">in</span> <span m="615260">and</span> <span m="615603">do</span>
  <span m="615946">a bit of</span> <span m="616290">mathematical</span> <span m="616840">magic,</span>
  <span m="617990">and</span> <span m="618200">then</span> <span m="618400">solve</span>
  <span m="618910">to</span> <span m="620080">find</span> <span m="620875">an attribute</span>
  <span m="621470">solution.</span> <span m="624140">So</span> <span m="624700">it''s</span>
  <span m="625070">already</span> <span m="625640">quite</span> <span m="625920">different</span>
  <span m="627250">to</span> <span m="627680">finite</span> <span m="628090">differences.</span></p><p><span
  m="629738">So</span> <span m="630150">how</span> <span m="630330">do</span> <span
  m="630430">we</span> <span m="630550">get</span> <span m="630840">started?</span>
  <span m="632390">We</span> <span m="632550">start</span> <span m="632920">off</span>
  <span m="633180">by--</span> <span m="633720">and</span> <span m="633830">let''s</span>
  <span m="634030">call</span> <span m="634300">this</span> <span m="634520">2a--</span>
  <span m="635980">we''re</span> <span m="636110">going</span> <span m="636280">to</span>
  <span m="636340">say,</span> <span m="636960">to</span> <span m="637070">approximate</span>
  <span m="637640">the</span> <span m="637710">solution</span> <span m="638350">[INAUDIBLE]</span>
  <span m="639016">used</span> <span m="639890">a</span> <span m="640040">sum</span>
  <span m="641850">of</span> <span m="642100">weighted</span> <span m="642450">functions.</span>
  <span m="646179">OK.</span> <span m="646980">We</span> <span m="647140">know</span>
  <span m="647360">that</span> <span m="647740">t</span> <span m="647920">is</span>
  <span m="648050">a</span> <span m="648100">function</span> <span m="648490">of</span>
  <span m="648660">x.</span> <span m="651480">t</span> <span m="651950">varies</span>
  <span m="652330">continuously</span> <span m="653920">along</span> <span m="654210">the</span>
  <span m="654300">domain</span> <span m="654750">here.</span> <span m="655055">A</span>
  <span m="655360">function of x.</span> <span m="656020">That''s</span> <span m="656230">an</span>
  <span m="656430">infinite</span> <span m="656830">dimensional</span> <span m="657360">problem,</span>
  <span m="657820">right?</span> <span m="658630">t is a continuous</span> <span m="659210">function.</span>
  <span m="660470">Best</span> <span m="660840">rather</span> <span m="661260">write</span>
  <span m="661630">our</span> <span m="661940">approximate</span> <span m="662600">solution,</span>
  <span m="664000">which</span> <span m="664270">I''m</span> <span m="664320">going</span>
  <span m="664560">to</span> <span m="664960">call</span> <span m="665290">t tilde</span>
  <span m="665773">of x.</span> <span m="666740">So</span> <span m="666900">this</span>
  <span m="667130">guy</span> <span m="667555">here</span> <span m="667980">is</span>
  <span m="668405">the</span> <span m="668830">approximation</span> <span m="671130">of</span>
  <span m="671830">my</span> <span m="672040">exact</span> <span m="672440">solution,</span>
  <span m="672870">t of x.</span> <span m="675570">And</span> <span m="675790">I''m</span>
  <span m="675890">going</span> <span m="676020">to</span> <span m="676140">write</span>
  <span m="676470">it as--</span> <span m="678248">I''m just going</span> <span m="678650">to
  leave a</span> <span m="679000">bit</span> <span m="679150">of</span> <span m="679250">space</span>
  <span m="679590">here--</span> <span m="680200">the</span> <span m="680300">sum</span>
  <span m="681120">from</span> <span m="681320">i</span> <span m="681800">equals</span>
  <span m="681950">1</span> <span m="682325">to</span> <span m="682700">capital</span>
  <span m="682990">N</span> <span m="684233">of</span> <span m="685100">some</span>
  <span m="685400">ai''s</span> <span m="687344">times</span> <span m="687830">some</span>
  <span m="688160">ci''s</span> <span m="689360">that</span> <span m="689510">are</span>
  <span m="689620">a</span> <span m="689670">function</span> <span m="690050">of</span>
  <span m="690180">a.</span></p><p><span m="694250">What</span> <span m="694480">are</span>
  <span m="694540">these</span> <span m="694730">guys</span> <span m="695010">here?</span>
  <span m="697200">These</span> <span m="697400">things</span> <span m="697710">here</span>
  <span m="698260">are</span> <span m="698660">no-end</span> <span m="699170">functions,</span>
  <span m="699880">they</span> <span m="700010">are things</span> <span m="700300">that</span>
  <span m="700400">I''m</span> <span m="700510">going</span> <span m="700630">to</span>
  <span m="700830">specify.</span> <span m="704870">And</span> <span m="705290">what</span>
  <span m="705470">you''ll</span> <span m="705700">see</span> <span m="705860">is</span>
  <span m="706100">that</span> <span m="706330">these</span> <span m="706430">things</span>
  <span m="706630">are</span> <span m="706720">going</span> <span m="706840">to</span>
  <span m="706910">be</span> <span m="707040">referred</span> <span m="707430">to</span>
  <span m="708650">later</span> <span m="708930">on</span> <span m="709130">as</span>
  <span m="709480">basis</span> <span m="709940">functions.</span> <span m="714580">These</span>
  <span m="714770">things</span> <span m="715020">are</span> <span m="715130">no-end</span>
  <span m="715660">functions</span> <span m="716170">of</span> <span m="716260">x.</span>
  <span m="716770">So we''re</span> <span m="716920">going to</span> <span m="717130">specify</span>
  <span m="717660">them.</span> <span m="717870">The</span> <span m="718040">ci''s,</span>
  <span m="718580">there''s N of them--</span> <span m="719500">capital</span> <span
  m="719860">N</span> <span m="720070">of</span> <span m="720170">them.</span> <span
  m="721150">And the ai''s</span> <span m="721410">here,</span> <span m="723120">these</span>
  <span m="723320">are</span> <span m="723540">unknown</span> <span m="724110">[INAUDIBLE].</span></p><p><span
  m="728970">OK,</span> <span m="729270">so</span> <span m="729760">what</span> <span
  m="730130">I''ve said</span> <span m="730440">is that</span> <span m="731736">t
  of x,</span> <span m="733590">an</span> <span m="733750">infinite</span> <span m="734760">dimensional</span>
  <span m="735230">problem,</span> <span m="735685">t</span> <span m="736140">is</span>
  <span m="736360">some</span> <span m="736630">continuous,</span> <span m="737330">or</span>
  <span m="737580">some</span> <span m="737820">function,</span> <span m="738230">whether</span>
  <span m="738400">it</span> <span m="738510">be continuous,</span> <span m="738940">some</span>
  <span m="739120">function</span> <span m="739500">of</span> <span m="739855">x</span>
  <span m="740210">on</span> <span m="740570">the</span> <span m="740650">domain.</span>
  <span m="741770">Let''s</span> <span m="741990">approximate</span> <span m="742740">it</span>
  <span m="743670">as</span> <span m="744270">a</span> <span m="744370">finite</span>
  <span m="745510">sum</span> <span m="746250">from</span> <span m="746370">i equals</span>
  <span m="746710">1</span> <span m="746940">to</span> <span m="747420">n</span> <span
  m="747880">of some</span> <span m="748430">weight,</span> <span m="748880">so</span>
  <span m="749030">some</span> <span m="749200">coefficient--</span> <span m="749890">ai''s--</span>
  <span m="750400">just</span> <span m="750490">constant,</span> <span m="751490">times</span>
  <span m="751920">some</span> <span m="752120">functions</span> <span m="752470">that</span>
  <span m="752560">we''re</span> <span m="752620">going</span> <span m="752740">to</span>
  <span m="753000">specify.</span></p><p><span m="754282">So</span> <span m="754700">with--</span>
  <span m="755300">can</span> <span m="755420">you</span> <span m="755490">see</span>
  <span m="755630">that</span> <span m="755760">we''ve</span> <span m="755940">discretized</span>
  <span m="756560">the</span> <span m="756640">problem</span> <span m="757130">in</span>
  <span m="757210">a</span> <span m="757260">different</span> <span m="757600">way</span>
  <span m="757810">than</span> <span m="757900">we</span> <span m="758160">did in
  finite</span> <span m="758550">differences.</span> <span m="759150">We</span> <span
  m="759370">have</span> <span m="759470">discretized</span> <span m="759660">the</span>
  <span m="760070">problem</span> <span m="760530">because</span> <span m="760810">now</span>
  <span m="761050">we</span> <span m="761200">have</span> <span m="761520">how</span>
  <span m="761650">many</span> <span m="761870">unknowns?</span> <span m="764210">n.</span>
  <span m="764780">We</span> <span m="764910">have</span> <span m="765040">n</span>
  <span m="765350">degrees</span> <span m="765660">of</span> <span m="765750">freedom.</span>
  <span m="766130">n</span> <span m="766470">[INAUDIBLE]</span> <span m="767230">ai''s</span>
  <span m="768420">that</span> <span m="768550">we</span> <span m="768670">can</span>
  <span m="768860">use</span> <span m="769310">to</span> <span m="769730">create</span>
  <span m="770180">our</span> <span m="770590">approximate</span> <span m="771250">solution.</span>
  <span m="773350">And</span> <span m="774200">I''ve</span> <span m="774350">left
  a bit</span> <span m="774640">a</span> <span m="774730">space</span> <span m="775080">here</span>
  <span m="775260">because</span> <span m="775480">I''m</span> <span m="775580">going</span>
  <span m="775700">to</span> <span m="775780">write</span> <span m="776160">this</span>
  <span m="776770">in.</span> <span m="776870">I''m</span> <span m="776910">going</span>
  <span m="777180">to</span> <span m="777290">write in</span> <span m="777580">100</span>
  <span m="778740">plus</span> <span m="779260">that</span> <span m="779450">extension.</span></p><p><span
  m="780210">Why</span> <span m="780360">do</span> <span m="780430">you</span> <span
  m="780570">think</span> <span m="780830">I</span> <span m="780890">wrote</span>
  <span m="781140">the</span> <span m="781250">100?</span> <span m="785530">I heard</span>
  <span m="785670">the</span> <span m="785850">b word.</span></p><p><span m="786415">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="786750">PROFESSOR: The</span> <span m="786860">boundary</span>
  <span m="787140">conditions.</span> <span m="787575">Yeah.</span> <span m="788010">In
  this</span> <span m="788190">particular</span> <span m="788610">example</span> <span
  m="789890">that</span> <span m="790060">we''re</span> <span m="790170">considering,</span>
  <span m="791630">the</span> <span m="792180">boundary</span> <span m="792460">conditions</span>
  <span m="794020">[INAUDIBLE]</span> <span m="794080">conditions</span> <span m="794450">that</span>
  <span m="794550">specified</span> <span m="795380">to</span> <span m="795520">be</span>
  <span m="795860">t</span> <span m="796210">equal</span> <span m="796520">100</span>
  <span m="796830">at</span> <span m="796930">either end.</span> <span m="797810">So</span>
  <span m="797930">let''s</span> <span m="798130">put</span> <span m="798290">the</span>
  <span m="798390">100</span> <span m="799410">out</span> <span m="799580">in</span>
  <span m="799670">front,</span> <span m="800160">and</span> <span m="800320">then</span>
  <span m="800470">the</span> <span m="800570">rest</span> <span m="800840">it there,</span>
  <span m="802510">the some of</span> <span m="803180">the</span> <span m="803590">ai</span>
  <span m="804055">times</span> <span m="804520">the ci''s</span> <span m="804780">is</span>
  <span m="804840">going to satisy</span> <span m="805280">0--</span> <span m="805970">0</span>
  <span m="806230">temperature</span> <span m="806525">at</span> <span m="806820">either</span>
  <span m="806900">end.</span> <span m="807400">Right?</span></p><p><span m="809540">OK
  so</span> <span m="809970">in</span> <span m="810100">this</span> <span m="810260">particular</span>
  <span m="810690">example,</span> <span m="811420">this</span> <span m="811540">guy--</span>
  <span m="811940">this</span> <span m="812140">100</span> <span m="812860">is</span>
  <span m="813570">chosen</span> <span m="814220">to</span> <span m="814340">satisfy</span>
  <span m="814880">a</span> <span m="815796">outbound</span> <span m="816240">[? preconditions
  ?]</span> <span m="816530">here</span> <span m="819630">for</span> <span m="819790">our</span>
  <span m="819880">model</span> <span m="820140">problem.</span></p><p><span m="823480">OK.</span>
  <span m="823850">So</span> <span m="824070">by</span> <span m="824260">writing</span>
  <span m="824760">this--</span> <span m="825310">and this</span> <span m="825910">sort</span>
  <span m="826050">of</span> <span m="826120">approximation</span> <span m="827000">of</span>
  <span m="827110">the</span> <span m="827190">temperature--</span> <span m="828640">it''s</span>
  <span m="828810">a</span> <span m="828880">simple</span> <span m="829190">equation,</span>
  <span m="829570">but</span> <span m="829670">I''m</span> <span m="829760">spending</span>
  <span m="830150">a little bit of</span> <span m="830350">time</span> <span m="830580">because</span>
  <span m="830810">it''s really</span> <span m="831000">important</span> <span m="831350">it''s</span>
  <span m="831410">clear</span> <span m="831690">in</span> <span m="831770">your</span>
  <span m="831880">mind,</span> <span m="832220">because</span> <span m="832420">this</span>
  <span m="832560">is</span> <span m="832690">really</span> <span m="832990">kind</span>
  <span m="833365">of</span> <span m="833740">one of the--</span> <span m="833810">what''s</span>
  <span m="834900">the</span> <span m="834990">first</span> <span m="835310">key</span>
  <span m="835570">step</span> <span m="836020">of</span> <span m="836170">making</span>
  <span m="837530">this</span> <span m="837660">approximation.</span> <span m="838390">We''ve</span>
  <span m="838650">turned</span> <span m="838910">the</span> <span m="839030">problem</span>
  <span m="839630">of</span> <span m="840790">determining</span> <span m="844085">t
  tilde</span> <span m="844548">of x,</span> <span m="846870">the</span> <span m="846970">approximation,</span>
  <span m="847940">which</span> <span m="848120">again</span> <span m="848470">is</span>
  <span m="849010">really</span> <span m="849240">an</span> <span m="849380">infinite</span>
  <span m="850170">dimensional</span> <span m="850750">problem,</span> <span m="852060">into</span>
  <span m="852410">the</span> <span m="852530">problem</span> <span m="853090">of</span>
  <span m="853760">determining</span> <span m="855270">the</span> <span m="855370">coefficients,</span>
  <span m="858750">the</span> <span m="858880">a1,</span> <span m="859110">a2,</span>
  <span m="860775">up</span> <span m="861250">to</span> <span m="862330">a</span>
  <span m="862730">n</span> <span m="864380">where</span> <span m="864510">we</span>
  <span m="865030">have</span> <span m="865240">now</span> <span m="865410">just</span>
  <span m="865700">capital</span> <span m="866130">N</span> <span m="866340">unknown.</span>
  <span m="869120">Kevin, yeah?</span></p><p><span m="871080">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="880390">PROFESSOR: Yeah,</span> <span m="880900">so</span> <span m="881155">if</span>
  <span m="881410">you</span> <span m="881540">had</span> <span m="881890">like</span>
  <span m="882040">100</span> <span m="882470">here</span> <span m="882950">and</span>
  <span m="883480">200</span> <span m="884070">somewhere</span> <span m="884410">else</span>
  <span m="884610">or</span> <span m="884700">something?</span> <span m="886130">There''s</span>
  <span m="886360">various</span> <span m="886710">ways</span> <span m="887350">that</span>
  <span m="887550">you</span> <span m="887650">can</span> <span m="887780">handle</span>
  <span m="887890">it.</span> <span m="887980">And</span> <span m="888230">we''ll</span>
  <span m="888470">talk</span> <span m="889600">probably</span> <span m="889870">in</span>
  <span m="890120">two weeks of</span> <span m="890470">times</span> <span m="890840">about</span>
  <span m="891620">how</span> <span m="891740">to</span> <span m="891840">do</span>
  <span m="891970">boundary</span> <span m="892290">conditions</span> <span m="895060">and</span>
  <span m="895180">the</span> <span m="895240">finite</span> <span m="895510">element</span>
  <span m="895850">method.</span> <span m="896960">But</span> <span m="897130">one</span>
  <span m="897650">approach</span> <span m="898070">that</span> <span m="898210">we</span>
  <span m="898320">could</span> <span m="898600">use</span> <span m="898910">just</span>
  <span m="899100">with</span> <span m="899210">the</span> <span m="899320">simple</span>
  <span m="899620">idea</span> <span m="899870">here is,</span> <span m="900120">you</span>
  <span m="900430">could,</span> <span m="900640">for</span> <span m="900730">example,</span>
  <span m="901240">have</span> <span m="901390">a</span> <span m="901430">linear</span>
  <span m="901750">function</span> <span m="903030">that</span> <span m="903230">went</span>
  <span m="903420">from</span> <span m="903580">100</span> <span m="904470">to</span>
  <span m="904650">200</span> <span m="905340">and</span> <span m="905460">then</span>
  <span m="905650">plus</span> <span m="905990">the</span> <span m="906110">rest.</span>
  <span m="907580">Right?</span> <span m="907960">So</span> <span m="908060">you</span>
  <span m="908170">could</span> <span m="908320">still</span> <span m="908510">get</span>
  <span m="908700">the</span> <span m="909040">boundary</span> <span m="909280">conditions</span>
  <span m="909620">back.</span> <span m="910300">But</span> <span m="910450">yeah,</span>
  <span m="911280">we''ll</span> <span m="911480">talk</span> <span m="913760">once</span>
  <span m="914040">we''ve</span> <span m="914180">been</span> <span m="914350">through</span>
  <span m="914470">the</span> <span m="914560">theory</span> <span m="914810">about</span>
  <span m="914990">how</span> <span m="915070">to</span> <span m="915160">handle</span>
  <span m="915400">boundary</span> <span m="915630">conditions</span> <span m="916020">more</span>
  <span m="916170">generally.</span> <span m="916430">Yep.</span></p><p><span m="918350">Generally</span>
  <span m="918980">speaking</span> <span m="919700">we</span> <span m="920010">will</span>
  <span m="920160">do</span> <span m="920320">something</span> <span m="920590">so</span>
  <span m="920860">that</span> <span m="921150">those</span> <span m="922326">ci''s</span>
  <span m="922720">will</span> <span m="922820">satisfy</span> <span m="923290">0.</span>
  <span m="924350">[INAUDIBLE].</span></p><p><span m="928590">OK.</span> <span m="928940">So</span>
  <span m="929840">now</span> <span m="930170">the</span> <span m="930250">question</span>
  <span m="930540">that</span> <span m="930650">you</span> <span m="930730">should</span>
  <span m="930870">be</span> <span m="930970">asking</span> <span m="931250">yourself</span>
  <span m="931560">is,</span> <span m="932370">what</span> <span m="932540">are</span>
  <span m="932590">these?</span> <span m="932840">I said</span> <span m="933120">they</span>
  <span m="933240">were</span> <span m="933370">no-end</span> <span m="933960">basis</span>
  <span m="934120">functions.</span> <span m="935690">They</span> <span m="935850">are</span>
  <span m="936070">things</span> <span m="936170">that we</span> <span m="936260">specify.</span>
  <span m="937040">So</span> <span m="937520">you</span> <span m="937680">guys</span>
  <span m="937880">have</span> <span m="938030">seen</span> <span m="938310">this</span>
  <span m="938510">kind</span> <span m="938730">of</span> <span m="938820">idea,</span>
  <span m="939240">this</span> <span m="939530">expanding</span> <span m="940200">a</span>
  <span m="940260">solution</span> <span m="942040">as</span> <span m="942240">a</span>
  <span m="943060">sum</span> <span m="943280">of</span> <span m="943380">weighted</span>
  <span m="943640">functions.</span> <span m="944260">You''ve</span> <span m="944380">seen
  that</span> <span m="944540">before, right?</span></p><p><span m="947270">When</span>
  <span m="947660">have</span> <span m="947770">you</span> <span m="947860">seen?</span>
  <span m="949510">Fourier</span> <span m="949850">series.</span> <span m="950280">Good,
  yes.</span> <span m="951920">So--</span> <span m="951990">I mean</span> <span m="952110">this</span>
  <span m="952240">is</span> <span m="952480">no</span> <span m="952760">different</span>
  <span m="953140">really</span> <span m="953400">to</span> <span m="953540">Fourier</span>
  <span m="953870">series,</span> <span m="954280">right?</span> <span m="954910">What</span>
  <span m="955320">are</span> <span m="955590">the</span> <span m="955660">ci''s</span>
  <span m="956220">in</span> <span m="956550">Fourier</span> <span m="956820">series?</span>
  <span m="959470">Sines</span> <span m="959820">and</span> <span m="959930">cosines</span>
  <span m="960280">of</span> <span m="960320">different</span> <span m="960650">frequencies.</span>
  <span m="961410">So</span> <span m="961550">the</span> <span m="961630">idea</span>
  <span m="962020">of</span> <span m="962100">decomposing</span> <span m="962960">a</span>
  <span m="963020">signal</span> <span m="964030">into</span> <span m="964820">a</span>
  <span m="965080">sum of</span> <span m="965190">harmonic</span> <span m="965650">components--</span>
  <span m="965945">I</span> <span m="966240">mean,</span> <span m="967060">signal</span>
  <span m="967350">processing--</span> <span m="967800">the</span> <span m="967870">entire</span>
  <span m="968200">field</span> <span m="970050">of</span> <span m="970260">signal</span>
  <span m="970510">processing</span> <span m="970980">kind</span> <span m="971120">of</span>
  <span m="971200">hinges</span> <span m="971540">on</span> <span m="971690">that</span>
  <span m="971900">idea.</span></p><p><span m="973090">Here</span> <span m="973330">we''re</span>
  <span m="973410">not</span> <span m="973600">going</span> <span m="973780">to</span>
  <span m="973860">use</span> <span m="975320">sines</span> <span m="975610">and</span>
  <span m="975870">cosines.</span> <span m="976270">We''re</span> <span m="976390">going
  to use</span> <span m="976610">polynomials.</span> <span m="979430">So</span> <span
  m="979910">ci</span> <span m="980100">of</span> <span m="980250">x</span> <span
  m="980505">are</span> <span m="980760">going to be polynomials</span> <span m="981410">[?
  in x. ?]</span> <span m="981510">In</span> <span m="981590">other</span> <span m="981950">words,</span>
  <span m="982180">c</span> <span m="982410">are going</span> <span m="982530">to</span>
  <span m="982620">be</span> <span m="982730">constant</span> <span m="983510">plus</span>
  <span m="984290">maybe</span> <span m="984510">a</span> <span m="984610">linear</span>
  <span m="984990">term</span> <span m="985280">in</span> <span m="985390">x</span>
  <span m="985660">plus</span> <span m="985930">maybe</span> <span m="986140">a</span>
  <span m="986510">quadratic</span> <span m="986970">term</span> <span m="987130">in
  x,</span> <span m="987500">and</span> <span m="987680">so</span> <span m="987860">on.</span>
  <span m="988560">And</span> <span m="988720">the</span> <span m="988790">reason</span>
  <span m="989100">that</span> <span m="989230">we''re</span> <span m="989360">going</span>
  <span m="989720">to</span> <span m="989860">use</span> <span m="990150">polynomials</span>
  <span m="990890">is</span> <span m="991080">because</span> <span m="991890">that</span>
  <span m="992130">sets</span> <span m="992180">the groundwork</span> <span m="992620">for</span>
  <span m="992700">the</span> <span m="992770">finite</span> <span m="993040">element</span>
  <span m="994420">method.</span> <span m="994730">Finite</span> <span m="995010">element</span>
  <span m="995170">method</span> <span m="995570">works</span> <span m="995970">with
  polynomials,</span> <span m="996770">basic</span> <span m="997040">functions.</span>
  <span m="997700">So</span> <span m="997800">we''re</span> <span m="997900">going</span>
  <span m="998000">to</span> <span m="998100">start</span> <span m="998240">off</span>
  <span m="998590">by</span> <span m="998700">thinking about</span> <span m="999184">polynomials.</span></p><p><span
  m="1001120">OK?</span> <span m="1002040">Good?</span> <span m="1002870">Straightforward,</span>
  <span m="1003400">right?</span> <span m="1003650">Easy.</span></p><p><span m="1008110">OK.</span>
  <span m="1008991">So</span> <span m="1012220">let''s</span> <span m="1012520">just</span>
  <span m="1012920">be</span> <span m="1013070">more</span> <span m="1013310">specific</span>
  <span m="1014020">for</span> <span m="1014280">our</span> <span m="1016150">particular</span>
  <span m="1016540">example</span> <span m="1017530">of</span> <span m="1017940">what</span>
  <span m="1018180">we</span> <span m="1018310">want</span> <span m="1019180">to</span>
  <span m="1019910">choose</span> <span m="1020390">for</span> <span m="1020620">the</span>
  <span m="1021390">ci''s.</span> <span m="1021750">And</span> <span m="1021890">again,</span>
  <span m="1022110">I</span> <span m="1022150">want</span> <span m="1022270">to</span>
  <span m="1022340">be</span> <span m="1022420">clear,</span> <span m="1023430">there</span>
  <span m="1023580">are</span> <span m="1023690">many</span> <span m="1026180">choices</span>
  <span m="1026720">for</span> <span m="1026859">ci,</span> <span m="1027430">and</span>
  <span m="1027550">this</span> <span m="1027720">is</span> <span m="1030161">a</span>
  <span m="1030640">decision</span> <span m="1031540">that</span> <span m="1031700">you</span>
  <span m="1031869">make.</span> <span m="1034755">So</span> <span m="1035250">this</span>
  <span m="1035520">is</span> <span m="1035740">[INAUDIBLE]</span> <span m="1036750">choosing</span>
  <span m="1037300">the</span> <span m="1037740">ci''s.</span> <span m="1042770">So</span>
  <span m="1042960">again,</span> <span m="1043310">here</span> <span m="1043599">we''re</span>
  <span m="1043720">go</span> <span m="1046690">to</span> <span m="1046839">use</span>
  <span m="1047079">polynomials,</span> <span m="1049060">and</span> <span m="1049210">that''s</span>
  <span m="1049410">because</span> <span m="1050140">we''re</span> <span m="1050280">interested</span>
  <span m="1050650">in</span> <span m="1052680">the</span> <span m="1052740">finite</span>
  <span m="1053010">element</span> <span m="1053460">method.</span> <span m="1053670">And</span>
  <span m="1054000">you will</span> <span m="1054160">see</span> <span m="1055720">on</span>
  <span m="1056860">Wednesday</span> <span m="1058740">exactly</span> <span m="1059130">what</span>
  <span m="1059270">the</span> <span m="1059340">basis</span> <span m="1059640">functions</span>
  <span m="1060110">look</span> <span m="1060310">like</span> <span m="1060520">in</span>
  <span m="1060620">finite</span> <span m="1060800">element.</span> <span m="1062530">But</span>
  <span m="1063350">for</span> <span m="1063520">now,</span> <span m="1064440">not</span>
  <span m="1065160">yet</span> <span m="1065360">the</span> <span m="1065470">finite</span>
  <span m="1065640">element,</span> <span m="1066670">we</span> <span m="1068080">need</span>
  <span m="1071290">basis</span> <span m="1071620">functions</span> <span m="1071965">that</span>
  <span m="1072310">satisfy</span> <span m="1073200">the</span> <span m="1073290">boundary</span>
  <span m="1073650">conditions.</span> <span m="1074250">But</span> <span m="1074280">because</span>
  <span m="1074650">we</span> <span m="1074780">subtracted</span> <span m="1075160">it</span>
  <span m="1075310">off,</span> <span m="1075720">or because</span> <span m="1075990">we</span>
  <span m="1076660">added</span> <span m="1077100">in</span> <span m="1077250">the</span>
  <span m="1077320">100</span> <span m="1077890">here,</span> <span m="1079000">you</span>
  <span m="1079150">can</span> <span m="1079310">see</span> <span m="1079480">it''s</span>
  <span m="1079630">what</span> <span m="1079750">I</span> <span m="1079800">was</span>
  <span m="1079950">saying</span> <span m="1080190">earlier,</span> <span m="1080980">we''re</span>
  <span m="1081070">going</span> <span m="1081190">to</span> <span m="1081300">set</span>
  <span m="1081540">these</span> <span m="1081770">guys</span> <span m="1082250">now</span>
  <span m="1083790">to</span> <span m="1083970">be</span> <span m="1086610">0.</span>
  <span m="1086810">So they''re</span> <span m="1087380">going</span> <span m="1087520">to</span>
  <span m="1087580">be</span> <span m="1087650">0</span> <span m="1088060">at</span>
  <span m="1088390">the end of the</span> <span m="1088480">domain,</span> <span m="1088840">right?</span></p><p><span
  m="1091250">So</span> <span m="1091790">if</span> <span m="1092020">we--</span>
  <span m="1092510">I</span> <span m="1092760">think we''re</span> <span m="1092850">going</span>
  <span m="1092970">to</span> <span m="1093030">choose</span> <span m="1093320">polynomials,</span>
  <span m="1093790">so</span> <span m="1094260">what''s</span> <span m="1094660">the</span>
  <span m="1094730">simplest</span> <span m="1095150">polynomial</span> <span m="1095650">we</span>
  <span m="1095750">could</span> <span m="1095900">choose?</span> <span m="1096260">We
  could</span> <span m="1096400">choose</span> <span m="1096460">[INAUDIBLE]</span>
  <span m="1096690">equal</span> <span m="1097030">constant.</span> <span m="1097910">That''s</span>
  <span m="1098350">not very</span> <span m="1098790">useful.</span> <span m="1098910">What''s</span>
  <span m="1099160">the</span> <span m="1099220">next</span> <span m="1099430">one?</span>
  <span m="1101760">x plus b.</span> <span m="1102180">You</span> <span m="1102430">could</span>
  <span m="1102570">use</span> <span m="1102710">a</span> <span m="1102770">linear</span>
  <span m="1103190">function,</span> <span m="1103740">but</span> <span m="1104260">what''s
  the</span> <span m="1104330">linear</span> <span m="1104660">function</span> <span
  m="1105130">that</span> <span m="1105270">satisfies</span> <span m="1105880">this</span>
  <span m="1106040">condition?</span></p><p><span m="1106994">AUDIENCE: [INAUDIBLE].</span></p><p><span
  m="1107950">PROFESSOR: Zero</span> <span m="1108330">everywhere.</span> <span m="1108650">So</span>
  <span m="1108720">that''s</span> <span m="1108880">not</span> <span m="1109020">very</span>
  <span m="1109190">useful.</span></p><p><span m="1110380">So</span> <span m="1110570">it</span>
  <span m="1110660">turns</span> <span m="1110900">out</span> <span m="1111140">that</span>
  <span m="1111320">the</span> <span m="1111400">first</span> <span m="1111710">one</span>
  <span m="1111890">that</span> <span m="1112080">would</span> <span m="1112290">give</span>
  <span m="1112450">us</span> <span m="1112640">anything--</span> <span m="1113770">what''s</span>
  <span m="1113910">that?</span></p><p><span m="1114718">AUDIENCE: [INAUDIBLE].</span></p><p><span
  m="1115930">PROFESSOR: Yeah.</span> <span m="1116500">The</span> <span m="1116620">first
  one</span> <span m="1116780">that would</span> <span m="1117010">give</span> <span
  m="1117170">us</span> <span m="1117300">anything</span> <span m="1117750">interesting</span>
  <span m="1118140">would</span> <span m="1118250">be</span> <span m="1118320">quadratic,</span>
  <span m="1118930">or</span> <span m="1119150">a</span> <span m="1119860">parabolic</span>
  <span m="1120510">function.</span></p><p><span m="1120880">So</span> <span m="1122780">we''ll</span>
  <span m="1123010">choose</span> <span m="1124340">a</span> <span m="1124450">quadratic</span>
  <span m="1125140">function</span> <span m="1126140">and--</span> <span m="1129080">again</span>
  <span m="1129450">there</span> <span m="1129640">is</span> <span m="1129820">a</span>
  <span m="1129860">variety</span> <span m="1130300">of</span> <span m="1130420">things</span>
  <span m="1130710">we</span> <span m="1130820">could</span> <span m="1131080">do--</span>
  <span m="1131380">but</span> <span m="1131550">here''s</span> <span m="1131800">one--</span>
  <span m="1132240">here''s</span> <span m="1132790">a</span> <span m="1132830">quadratic</span>
  <span m="1133350">function,</span> <span m="1133890">which</span> <span m="1134170">may</span>
  <span m="1134300">be</span> <span m="1134380">[INAUDIBLE]</span> <span m="1136170">well</span>
  <span m="1136250">it could be</span> <span m="1136340">scaled.</span> <span m="1136890">1</span>
  <span m="1137150">plus x,</span> <span m="1137620">1</span> <span m="1137820">minus</span>
  <span m="1138060">x,</span> <span m="1139010">that''s</span> <span m="1139210">a</span>
  <span m="1139260">quadratic.</span> <span m="1139990">So c1,</span> <span m="1141720">the</span>
  <span m="1141800">first</span> <span m="1142250">basis</span> <span m="1142610">function</span>
  <span m="1143000">in</span> <span m="1143100">our</span> <span m="1143360">extension,</span>
  <span m="1144500">the</span> <span m="1144610">function</span> <span m="1145010">of</span>
  <span m="1145130">x,</span> <span m="1146180">and</span> <span m="1146340">[INAUDIBLE]</span>
  <span m="1146560">is</span> <span m="1146670">1</span> <span m="1146850">plus</span>
  <span m="1146980">x,</span> <span m="1147250">1</span> <span m="1147410">minus</span>
  <span m="1147680">x.</span> <span m="1147890">That</span> <span m="1148070">clearly</span>
  <span m="1148420">satisfies</span> <span m="1149560">the</span> <span m="1149630">boundary</span>
  <span m="1149900">conditions,</span> <span m="1150540">the</span> <span m="1150570">0</span>
  <span m="1150770">boundary</span> <span m="1151010">conditions</span> <span m="1151410">at</span>
  <span m="1151530">either</span> <span m="1151750">end.</span> <span m="1152290">Yep.</span></p><p><span
  m="1153590">And</span> <span m="1153770">then</span> <span m="1155080">let''s</span>
  <span m="1155280">also</span> <span m="1156430">look</span> <span m="1156670">at</span>
  <span m="1156740">cubic.</span> <span m="1159330">So</span> <span m="1159480">that''s</span>
  <span m="1159650">going</span> <span m="1159770">to</span> <span m="1159840">be</span>
  <span m="1159960">our</span> <span m="1160150">second</span> <span m="1160530">one.</span>
  <span m="1162170">And</span> <span m="1163030">there</span> <span m="1163120">are</span>
  <span m="1163150">a</span> <span m="1163190">variety</span> <span m="1163640">of</span>
  <span m="1163730">cubics</span> <span m="1164100">we</span> <span m="1164200">could</span>
  <span m="1164400">choose,</span> <span m="1164910">but</span> <span m="1165110">let''s</span>
  <span m="1165420">choose</span> <span m="1165770">the</span> <span m="1165860">one</span>
  <span m="1166315">that</span> <span m="1166770">does</span> <span m="1167225">x,</span>
  <span m="1167680">1</span> <span m="1167890">plus x,</span> <span m="1168180">1</span>
  <span m="1168410">minus x.</span> <span m="1169560">And</span> <span m="1169720">again,</span>
  <span m="1170280">clearly</span> <span m="1170620">if</span> <span m="1170740">we</span>
  <span m="1170890">satisfy</span> <span m="1171646">[INAUDIBLE]</span> <span m="1172954">x</span>
  <span m="1173390">equal--</span> <span m="1174050">if</span> <span m="1174190">we</span>
  <span m="1174360">substitute</span> <span m="1174690">x</span> <span m="1174900">equal</span>
  <span m="1175100">minus</span> <span m="1175420">1,</span> <span m="1175630">or</span>
  <span m="1175720">x</span> <span m="1175890">equal</span> <span m="1176200">1</span>
  <span m="1176470">in</span> <span m="1176580">there,</span> <span m="1176770">we''re</span>
  <span m="1176850">going</span> <span m="1176980">to</span> <span m="1177050">get</span>
  <span m="1177290">c2</span> <span m="1178330">equal to</span> <span m="1178490">0.</span>
  <span m="1178800">So if</span> <span m="1179130">we</span> <span m="1179260">sketched</span>
  <span m="1179760">out</span> <span m="1180160">physically</span> <span m="1181810">what</span>
  <span m="1181960">these</span> <span m="1182130">guys</span> <span m="1182430">look</span>
  <span m="1182690">like,</span> <span m="1184210">we</span> <span m="1184430">sketch</span>
  <span m="1184810">c</span> <span m="1185190">as a</span> <span m="1185290">function</span>
  <span m="1185680">of</span> <span m="1185820">x,</span> <span m="1186920">then</span>
  <span m="1187480">the</span> <span m="1187550">quadratic</span> <span m="1188060">looks</span>
  <span m="1188300">something</span> <span m="1188660">like</span> <span m="1188940">that,</span>
  <span m="1190390">and</span> <span m="1190570">the</span> <span m="1190640">cubic</span>
  <span m="1190950">looks</span> <span m="1192470">something</span> <span m="1192890">like</span>
  <span m="1193050">that.</span> <span m="1193660">So that''s</span> <span m="1193820">c1</span>
  <span m="1194140">of x,</span> <span m="1195130">and</span> <span m="1195450">this
  is</span> <span m="1197000">c2</span> <span m="1197480">of</span> <span m="1197960">x.</span>
  <span m="1199880">Right,</span> <span m="1200130">that''s</span> <span m="1200590">0.</span></p><p><span
  m="1204730">OK.</span> <span m="1205673">So</span> <span m="1206660">those</span>
  <span m="1206830">are</span> <span m="1206870">the</span> <span m="1206970">choices</span>
  <span m="1207430">we</span> <span m="1207580">make.</span> <span m="1208780">And</span>
  <span m="1209190">so</span> <span m="1211660">in</span> <span m="1211790">this</span>
  <span m="1211880">simple</span> <span m="1212250">example</span> <span m="1212880">we''re</span>
  <span m="1213000">going</span> <span m="1213120">to</span> <span m="1213280">use</span>
  <span m="1213500">only</span> <span m="1213690">two</span> <span m="1213990">degrees</span>
  <span m="1214340">of</span> <span m="1214420">freedom</span> <span m="1214980">to</span>
  <span m="1215070">describe</span> <span m="1215520">the</span> <span m="1215590">approximate</span>
  <span m="1216150">solution.</span> <span m="1217390">And</span> <span m="1217580">with</span>
  <span m="1217800">those</span> <span m="1218060">two</span> <span m="1218240">degrees</span>
  <span m="1218600">of</span> <span m="1218730">freedom,</span> <span m="1220220">what</span>
  <span m="1220320">is</span> <span m="1220470">our</span> <span m="1220650">approximation?</span></p><p><span
  m="1222140">Our approximation</span> <span m="1223220">is</span> <span m="1224850">t</span>
  <span m="1225870">tilde</span> <span m="1226290">of</span> <span m="1226785">x</span>
  <span m="1227280">being</span> <span m="1227790">100,</span> <span m="1229320">plus</span>
  <span m="1230630">that</span> <span m="1230870">sum,</span> <span m="1231390">which</span>
  <span m="1231590">in</span> <span m="1231670">this</span> <span m="1231860">case</span>
  <span m="1232150">is</span> <span m="1232250">going</span> <span m="1232370">to</span>
  <span m="1232460">be</span> <span m="1232650">a1</span> <span m="1234130">times</span>
  <span m="1234400">c1</span> <span m="1234890">of</span> <span m="1234980">x,</span>
  <span m="1235670">where</span> <span m="1235780">c1</span> <span m="1236030">is</span>
  <span m="1236190">1</span> <span m="1236380">plus x,</span> <span m="1236730">1</span>
  <span m="1236910">minus</span> <span m="1237290">x,</span> <span m="1238600">plus</span>
  <span m="1239530">a2</span> <span m="1240330">times</span> <span m="1240760">c2</span>
  <span m="1240790">of</span> <span m="1241020">x,</span> <span m="1242010">where</span>
  <span m="1242210">c2</span> <span m="1242640">is</span> <span m="1242930">x,</span>
  <span m="1243390">1 plus x,</span> <span m="1243750">1 minus x.</span></p><p><span
  m="1245660">OK,</span> <span m="1245920">so</span> <span m="1246080">physically</span>
  <span m="1246590">we''re</span> <span m="1246750">saying</span> <span m="1247730">the</span>
  <span m="1247830">solution</span> <span m="1248300">is</span> <span m="1248520">100--</span>
  <span m="1249630">so</span> <span m="1249750">first</span> <span m="1250170">of
  all,</span> <span m="1251020">just shift it</span> <span m="1251380">up.</span>
  <span m="1251700">100.</span> <span m="1252880">Then</span> <span m="1253160">take</span>
  <span m="1253970">some</span> <span m="1254200">amount</span> <span m="1254870">of</span>
  <span m="1255830">a</span> <span m="1255930">function</span> <span m="1256240">that</span>
  <span m="1256330">looks</span> <span m="1256510">like</span> <span m="1256690">this,</span>
  <span m="1258740">plus</span> <span m="1259400">some</span> <span m="1259640">amount--</span>
  <span m="1260130">some</span> <span m="1260330">other</span> <span m="1260650">amount--</span>
  <span m="1261640">of</span> <span m="1261790">a</span> <span m="1261830">function</span>
  <span m="1262160">that</span> <span m="1262260">looks</span> <span m="1262430">like</span>
  <span m="1262630">this.</span> <span m="1262880">Add</span> <span m="1263260">them</span>
  <span m="1263430">together.</span> <span m="1264590">And</span> <span m="1264700">now</span>
  <span m="1264880">we''re</span> <span m="1264940">going</span> <span m="1265060">to</span>
  <span m="1265130">say,</span> <span m="1265440">what''s</span> <span m="1265750">the</span>
  <span m="1265870">right--</span> <span m="1266960">what</span> <span m="1267100">are</span>
  <span m="1267160">the</span> <span m="1267250">right</span> <span m="1267540">weightings?</span>
  <span m="1268100">What</span> <span m="1268230">are</span> <span m="1268290">the</span>
  <span m="1268390">a1''s</span> <span m="1268890">and</span> <span m="1269000">a2''s</span>
  <span m="1269480">that</span> <span m="1269620">we</span> <span m="1269780">should</span>
  <span m="1269990">choose</span> <span m="1271170">so</span> <span m="1271430">that</span>
  <span m="1271620">the</span> <span m="1271700">function</span> <span m="1271975">that</span>
  <span m="1272250">we</span> <span m="1272410">get</span> <span m="1273570">is</span>
  <span m="1273840">somehow</span> <span m="1274590">reasonably</span> <span m="1275380">a</span>
  <span m="1275440">solution</span> <span m="1275960">of</span> <span m="1276080">that</span>
  <span m="1276400">model</span> <span m="1276780">problem</span> <span m="1277740">that</span>
  <span m="1277890">looks</span> <span m="1278090">something</span> <span m="1278450">like</span>
  <span m="1278660">this.</span></p><p><span m="1281300">Yep.</span> <span m="1283210">And</span>
  <span m="1283370">that''s</span> <span m="1283620">now</span> <span m="1283810">what</span>
  <span m="1283940">we''re</span> <span m="1284020">going</span> <span m="1284140">to</span>
  <span m="1284200">talk</span> <span m="1284410">about</span> <span m="1284630">with</span>
  <span m="1284800">numbers</span> <span m="1285140">3</span> <span m="1285360">and</span>
  <span m="1285500">4.</span> <span m="1285840">The</span> <span m="1285910">collocation</span>
  <span m="1286640">method</span> <span m="1287160">and</span> <span m="1287300">the</span>
  <span m="1287370">method</span> <span m="1287620">of</span> <span m="1287710">weighted</span>
  <span m="1288000">residuals</span> <span m="1288720">are</span> <span m="1288810">two</span>
  <span m="1289100">different</span> <span m="1289580">ways</span> <span m="1290870">that</span>
  <span m="1291070">we</span> <span m="1291170">can</span> <span m="1291320">come</span>
  <span m="1291540">up</span> <span m="1291670">with</span> <span m="1291810">the</span>
  <span m="1291880">conditions</span> <span m="1292710">to</span> <span m="1292810">help</span>
  <span m="1293060">us</span> <span m="1293320">choose</span> <span m="1293780">a1</span>
  <span m="1294160">and</span> <span m="1294280">a2</span> <span m="1295690">so</span>
  <span m="1295840">that</span> <span m="1296060">in</span> <span m="1296270">different</span>
  <span m="1296660">ways</span> <span m="1297090">we</span> <span m="1297220">get</span>
  <span m="1297390">a</span> <span m="1297430">solution</span> <span m="1298820">that</span>
  <span m="1299050">is</span> <span m="1301000">a</span> <span m="1301120">good,</span>
  <span m="1301480">or</span> <span m="1301730">just</span> <span m="1301930">a</span>
  <span m="1301980">different</span> <span m="1302290">kind</span> <span m="1302440">of</span>
  <span m="1302510">an</span> <span m="1303080">approximation,</span> <span m="1303900">of</span>
  <span m="1303990">the</span> <span m="1304160">problem</span> <span m="1304400">we''re</span>
  <span m="1304530">actually</span> <span m="1304770">trying</span> <span m="1304990">to</span>
  <span m="1305060">solve.</span></p><p><span m="1306920">OK?</span> <span m="1308222">Yep.</span>
  <span m="1310130">All right.</span> <span m="1310740">Any questions</span> <span
  m="1311290">so</span> <span m="1311460">far,</span> <span m="1311750">questions</span>
  <span m="1312270">based</span> <span m="1312530">on things</span> <span m="1313010">that</span>
  <span m="1313140">are in the notes</span> <span m="1313500">that</span> <span m="1313940">weren''t
  clear?</span> <span m="1318607">No?</span> <span m="1320550">All right.</span></p><p><span
  m="1322250">So that''s</span> <span m="1322470">kind of</span> <span m="1322550">the</span>
  <span m="1323230">easy</span> <span m="1323590">part.</span> <span m="1325075">So</span>
  <span m="1325570">now</span> <span m="1325650">let''s</span> <span m="1325910">talk</span>
  <span m="1326370">about</span> <span m="1328100">the</span> <span m="1328210">two</span>
  <span m="1328350">different</span> <span m="1328840">ways</span> <span m="1330560">that</span>
  <span m="1330730">we</span> <span m="1330820">can</span> <span m="1331000">come</span>
  <span m="1331260">up</span> <span m="1331470">with</span> <span m="1334700">conditions</span>
  <span m="1335160">that</span> <span m="1335280">will</span> <span m="1335380">let</span>
  <span m="1335530">us</span> <span m="1335670">solve</span> <span m="1336390">for
  a1</span> <span m="1336970">and</span> <span m="1337387">a2.</span></p><p><span
  m="1338640">And</span> <span m="1338980">the</span> <span m="1339040">first</span>
  <span m="1339420">one</span> <span m="1340400">is</span> <span m="1340740">going</span>
  <span m="1340880">to</span> <span m="1340970">be</span> <span m="1341370">the</span>
  <span m="1341440">collocation</span> <span m="1342100">method.</span> <span m="1344854">So</span>
  <span m="1346690">number</span> <span m="1346980">three,</span> <span m="1347380">collocation.</span>
  <span m="1349545">Collocation.</span></p><p><span m="1362160">OK.</span> <span m="1362590">So</span>
  <span m="1362810">again,</span> <span m="1363370">what</span> <span m="1363550">are</span>
  <span m="1363590">we</span> <span m="1363710">doing</span> <span m="1364070">here?</span>
  <span m="1364480">We''re</span> <span m="1364680">saying</span> <span m="1365910">for</span>
  <span m="1366320">the</span> <span m="1366450">approximate</span> <span m="1367120">solution</span>
  <span m="1368405">t</span> <span m="1368870">tilde</span> <span m="1369335">of</span>
  <span m="1369800">x</span> <span m="1372130">being</span> <span m="1372490">100</span>
  <span m="1373823">plus</span> <span m="1374256">the</span> <span m="1374690">[?
  extension ?]</span> <span m="1375760">[INAUDIBLE]</span> <span m="1377430">in of</span>
  <span m="1378183">ai</span> <span m="1379170">times</span> <span m="1379250">the</span>
  <span m="1379520">ci of x,</span> <span m="1380190">where</span> <span m="1380660">we''re,</span>
  <span m="1381200">in</span> <span m="1381320">our</span> <span m="1381440">simple</span>
  <span m="1381690">example,</span> <span m="1382160">choosing</span> <span m="1382580">[?
  n equal 2 ?]</span> <span m="1383840">and</span> <span m="1384260">the</span> <span
  m="1384370">ci''s</span> <span m="1385210">to be these two guys here,</span> <span
  m="1385890">quadratic</span> <span m="1386240">and</span> <span m="1386590">the</span>
  <span m="1386650">cubic.</span> <span m="1388070">We</span> <span m="1388440">need</span>
  <span m="1389354">now</span> <span m="1391210">to</span> <span m="1391370">determine</span>
  <span m="1393122">the</span> <span m="1393530">ai''s.</span> <span m="1395774">a1,</span>
  <span m="1396252">a2,</span> <span m="1397686">up to</span> <span m="1398164">an.</span>
  <span m="1398642">In</span> <span m="1399120">this</span> <span m="1399598">case,</span>
  <span m="1400080">just</span> <span m="1400310">a1</span> <span m="1400690">and</span>
  <span m="1400800">a2.</span></p><p><span m="1402890">OK.</span> <span m="1403180">So</span>
  <span m="1403390">first</span> <span m="1403650">question,</span> <span m="1404820">how</span>
  <span m="1405510">many</span> <span m="1405660">conditions</span> <span m="1406080">do</span>
  <span m="1406170">we</span> <span m="1406230">need</span> <span m="1406380">to</span>
  <span m="1406450">come</span> <span m="1406660">up</span> <span m="1406800">with?</span>
  <span m="1409870">Two.</span> <span m="1410770">In</span> <span m="1410920">general,</span>
  <span m="1411250">n</span> <span m="1411520">conditions.</span> <span m="1412050">Right?</span>
  <span m="1412290">We</span> <span m="1412380">have</span> <span m="1412610">n</span>
  <span m="1412850">unknowns.</span> <span m="1413430">We</span> <span m="1413520">said</span>
  <span m="1413650">that</span> <span m="1413850">over</span> <span m="1414010">here.</span>
  <span m="1414890">We</span> <span m="1415010">turned</span> <span m="1415210">our</span>
  <span m="1415540">infinite</span> <span m="1415710">dimensional</span> <span m="1416320">problem</span>
  <span m="1416740">of solving</span> <span m="1417030">the</span> <span m="1417100">PDE</span>
  <span m="1417590">into</span> <span m="1417810">a</span> <span m="1417850">problem</span>
  <span m="1418110">with</span> <span m="1418270">n</span> <span m="1418510">degrees</span>
  <span m="1418840">of</span> <span m="1418950">freedom.</span> <span m="1419890">So</span>
  <span m="1419900">now</span> <span m="1420070">we</span> <span m="1420170">somehow</span>
  <span m="1420460">need</span> <span m="1420760">n</span> <span m="1421320">conditions.</span>
  <span m="1422810">And</span> <span m="1423230">in</span> <span m="1423350">this</span>
  <span m="1423500">example</span> <span m="1423970">here</span> <span m="1424300">where</span>
  <span m="1424540">we have</span> <span m="1424720">just</span> <span m="1424940">two</span>
  <span m="1425080">basic</span> <span m="1425420">functions,</span> <span m="1425880">we</span>
  <span m="1425970">need</span> <span m="1426200">two</span> <span m="1426390">conditions</span>
  <span m="1427100">that will let</span> <span m="1427520">us</span> <span m="1427840">solve</span>
  <span m="1428160">for</span> <span m="1428320">a1</span> <span m="1428640">and</span>
  <span m="1428800">a2.</span></p><p><span m="1430230">So</span> <span m="1430350">what</span>
  <span m="1430490">is</span> <span m="1430640">collocation</span> <span m="1431410">say?</span>
  <span m="1432590">Collocation</span> <span m="1434010">says</span> <span m="1435490">let''s</span>
  <span m="1435830">pick</span> <span m="1438490">n</span> <span m="1439080">points.</span>
  <span m="1440820">We</span> <span m="1440960">draw</span> <span m="1441260">my</span>
  <span m="1441520">rod</span> <span m="1442990">back</span> <span m="1443300">up</span>
  <span m="1443430">here</span> <span m="1446465">from l</span> <span m="1446960">over
  2,</span> <span m="1447610">minus</span> <span m="1447800">l</span> <span m="1447890">over</span>
  <span m="1448060">2,</span> <span m="1448260">to</span> <span m="1448910">l</span>
  <span m="1449100">over 2.</span> <span m="1451070">Let''s pick</span> <span m="1452500">some</span>
  <span m="1452670">points.</span> <span m="1453120">In</span> <span m="1453290">particular,</span>
  <span m="1453960">let''s</span> <span m="1454260">take</span> <span m="1454730">n
  points,</span> <span m="1455190">so</span> <span m="1455360">let''s</span> <span
  m="1455500">pick</span> <span m="1455760">two</span> <span m="1456080">points</span>
  <span m="1456460">in</span> <span m="1456540">the</span> <span m="1456630">domain,</span>
  <span m="1458290">this</span> <span m="1458490">point</span> <span m="1458790">and</span>
  <span m="1458850">this</span> <span m="1459050">point.</span> <span m="1460360">And</span>
  <span m="1460560">let''s</span> <span m="1460960">enforce</span> <span m="1461650">the</span>
  <span m="1462560">PDE</span> <span m="1462940">at those points.</span> <span m="1463170">Let''s
  make</span> <span m="1463390">sure</span> <span m="1464190">that</span> <span m="1464340">the</span>
  <span m="1464400">PDE</span> <span m="1464840">is</span> <span m="1465000">satisfied.</span></p><p><span
  m="1466880">Everyone</span> <span m="1466980">know what the PDE</span> <span m="1467320">is?</span>
  <span m="1467480">d by dx of</span> <span m="1467860">kdtdx</span> <span m="1469010">equals</span>
  <span m="1469230">minus</span> <span m="1469530">2.</span> <span m="1470710">Let''s</span>
  <span m="1471890">have</span> <span m="1472130">the</span> <span m="1472220">solution</span>
  <span m="1473020">satisfy</span> <span m="1473660">the</span> <span m="1473810">PDE</span>
  <span m="1474255">at</span> <span m="1474700">those points.</span> <span m="1476035">OK?</span>
  <span m="1477820">And by</span> <span m="1477980">forcing</span> <span m="1478430">that--</span>
  <span m="1478863">forcing</span> <span m="1479590">the</span> <span m="1479790">PDE</span>
  <span m="1480580">to</span> <span m="1480670">be</span> <span m="1480780">satisfied</span>
  <span m="1481420">with</span> <span m="1481570">the</span> <span m="1481690">approximate</span>
  <span m="1482070">solution</span> <span m="1482270">at</span> <span m="1482430">those</span>
  <span m="1482620">two</span> <span m="1482740">points,</span> <span m="1483050">we''re</span>
  <span m="1483200">going</span> <span m="1483390">to</span> <span m="1483530">two</span>
  <span m="1483885">conditions.</span> <span m="1485100">Right?</span> <span m="1485960">Two</span>
  <span m="1486090">mathematical</span> <span m="1486630">conditions.</span> <span
  m="1487090">Two</span> <span m="1487720">equations,</span> <span m="1488260">two</span>
  <span m="1488440">unknowns,</span> <span m="1488910">we</span> <span m="1489020">should</span>
  <span m="1489200">be</span> <span m="1489320">able</span> <span m="1489560">to</span>
  <span m="1489670">solve.</span></p><p><span m="1490756">So</span> <span m="1491100">that''s</span>
  <span m="1491360">the</span> <span m="1491460">idea</span> <span m="1491760">with</span>
  <span m="1491890">collocation.</span> <span m="1492400">You</span> <span m="1492470">guys</span>
  <span m="1492680">have seen--</span> <span m="1492740">did</span> <span m="1493030">you</span>
  <span m="1493190">guys</span> <span m="1493280">see</span> <span m="1493490">collocation</span>
  <span m="1494090">in</span> <span m="1494966">aerodynamics?</span> <span m="1496670">[INAUDIBLE],</span>
  <span m="1497365">yeah.</span> <span m="1497690">What</span> <span m="1497810">do</span>
  <span m="1497870">you</span> <span m="1497950">do?</span> <span m="1498150">You</span>
  <span m="1498290">have</span> <span m="1498520">the</span> <span m="1498620">collocation</span>
  <span m="1499260">point</span> <span m="1499900">at--</span> <span m="1500600">which--</span>
  <span m="1500880">I</span> <span m="1501010">always forget</span> <span m="1501270">which</span>
  <span m="1501430">way</span> <span m="1501610">it is--</span> <span m="1501770">you</span>
  <span m="1501890">have</span> <span m="1502200">c over 4</span> <span m="1502300">and</span>
  <span m="1502640">3c</span> <span m="1503064">over 4,</span> <span m="1503488">right?</span>
  <span m="1504336">[INAUDIBLE]</span></p><p><span m="1505690">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="1511680">PROFESSOR: At</span> <span m="1512175">3,</span> <span m="1512670">[INAUDIBLE].</span>
  <span m="1513630">So</span> <span m="1513860">it''s the</span> <span m="1513930">same</span>
  <span m="1514160">idea.</span> <span m="1514600">The</span> <span m="1514670">collocation</span>
  <span m="1515240">point</span> <span m="1515500">is</span> <span m="1515590">the</span>
  <span m="1515680">point</span> <span m="1516010">at</span> <span m="1516160">which</span>
  <span m="1516500">you</span> <span m="1517330">enforce</span> <span m="1517750">the</span>
  <span m="1517830">condition.</span> <span m="1518820">So it''s</span> <span m="1519500">exactly</span>
  <span m="1519950">the same</span> <span m="1520170">idea.</span></p><p><span m="1522010">OK,</span>
  <span m="1522470">so</span> <span m="1523030">how</span> <span m="1523220">does</span>
  <span m="1523420">that</span> <span m="1523560">work out</span> <span m="1525550">mathematically?</span>
  <span m="1526590">So</span> <span m="1526850">that''s</span> <span m="1527060">what</span>
  <span m="1527140">collcation--</span> <span m="1527960">that''s</span> <span m="1528150">what</span>
  <span m="1529084">collocation</span> <span m="1529551">means.</span> <span m="1530020">We''re
  going</span> <span m="1530200">to</span> <span m="1530290">enforce</span> <span
  m="1530672">the</span> <span m="1531054">PDE</span> <span m="1532660">at</span>
  <span m="1533500">n</span> <span m="1533820">point.</span> <span m="1535080">OK.</span>
  <span m="1536100">How</span> <span m="1536230">are</span> <span m="1536260">we</span>
  <span m="1536350">going</span> <span m="1536480">to</span> <span m="1536580">write</span>
  <span m="1536810">that?</span> <span m="1537120">So</span> <span m="1539230">let''s</span>
  <span m="1539470">again</span> <span m="1539890">write</span> <span m="1540160">down</span>
  <span m="1540600">the</span> <span m="1540780">example</span> <span m="1541035">that</span>
  <span m="1541290">we''re</span> <span m="1542230">considering,</span> <span m="1542870">which</span>
  <span m="1543060">is</span> <span m="1543230">the</span> <span m="1543310">1d</span>
  <span m="1544080">heat</span> <span m="1544540">equation.</span> <span m="1547130">And</span>
  <span m="1547310">I''ll</span> <span m="1547480">write</span> <span m="1547700">it</span>
  <span m="1548070">in</span> <span m="1548210">the</span> <span m="1548270">general</span>
  <span m="1548670">form</span> <span m="1549010">here</span> <span m="1549440">with</span>
  <span m="1549870">the</span> <span m="1551590">k</span> <span m="1551860">still</span>
  <span m="1552150">in</span> <span m="1552300">there.</span> <span m="1553840">d
  by dx</span> <span m="1555633">of</span> <span m="1556340">k</span> <span m="1556742">dt</span>
  <span m="1557144">dx</span> <span m="1560020">equals to</span> <span m="1560470">minus</span>
  <span m="1560810">q.</span></p><p><span m="1563660">OK,</span> <span m="1564080">so</span>
  <span m="1564220">now</span> <span m="1564590">we''re</span> <span m="1564770">going</span>
  <span m="1564890">to</span> <span m="1564980">define</span> <span m="1567580">something</span>
  <span m="1567920">very</span> <span m="1568240">important,</span> <span m="1572830">which</span>
  <span m="1572990">is</span> <span m="1573410">the</span> <span m="1573510">residual.</span>
  <span m="1575730">And</span> <span m="1575740">this</span> <span m="1575860">is</span>
  <span m="1575970">a</span> <span m="1576070">really</span> <span m="1577800">important</span>
  <span m="1578610">concept</span> <span m="1579220">that</span> <span m="1579360">we''re</span>
  <span m="1579470">going</span> <span m="1579590">to</span> <span m="1579680">use</span>
  <span m="1580910">repeatedly</span> <span m="1581470">all</span> <span m="1581570">the</span>
  <span m="1581640">way</span> <span m="1581790">through</span> <span m="1582070">this</span>
  <span m="1582350">finite</span> <span m="1582560">element</span> <span m="1583380">module.</span></p><p><span
  m="1585660">So</span> <span m="1585890">what</span> <span m="1586060">is</span>
  <span m="1586190">the</span> <span m="1586300">residual?</span> <span m="1587790">We''re
  going to call</span> <span m="1588230">it</span> <span m="1588670">capital</span>
  <span m="1589420">R.</span> <span m="1591220">It''s</span> <span m="1591390">going</span>
  <span m="1591520">to</span> <span m="1591600">be</span> <span m="1591750">a</span>
  <span m="1591820">function</span> <span m="1592340">of</span> <span m="1592625">our</span>
  <span m="1592910">approximate</span> <span m="1593770">solution,</span> <span m="1595100">and</span>
  <span m="1595340">it''s</span> <span m="1595510">a</span> <span m="1595550">function</span>
  <span m="1595910">of</span> <span m="1596030">x.</span> <span m="1599620">And</span>
  <span m="1600460">for</span> <span m="1600560">this</span> <span m="1601520">1D</span>
  <span m="1601860">heat</span> <span m="1602030">equation,</span> <span m="1602630">what''s</span>
  <span m="1602740">the</span> <span m="1602840">residual?</span> <span m="1603370">It''s</span>
  <span m="1603570">d by dx</span> <span m="1605460">of</span> <span m="1605930">[?
  kdtdx ?]</span> <span m="1607680">tilde</span> <span m="1608460">dx</span> <span
  m="1610190">plus</span> <span m="1610580">[? q. ?]</span></p><p><span m="1617530">OK,</span>
  <span m="1618005">so</span> <span m="1620100">1D</span> <span m="1620240">heat</span>
  <span m="1620380">equation,</span> <span m="1620980">d by dx of</span> <span m="1621710">of</span>
  <span m="1621840">kdtdx</span> <span m="1622301">equals</span> <span m="1622762">minus</span>
  <span m="1623223">2.</span> <span m="1625530">The</span> <span m="1625730">residual</span>
  <span m="1626350">for</span> <span m="1626460">that</span> <span m="1626610">equation,</span>
  <span m="1628020">which</span> <span m="1628100">is</span> <span m="1628250">a</span>
  <span m="1628320">function</span> <span m="1628720">of</span> <span m="1628980">the</span>
  <span m="1629330">approximate</span> <span m="1629740">solution,</span> <span m="1630490">t</span>
  <span m="1630986">tilde--</span> <span m="1631978">so</span> <span m="1632474">you
  want</span> <span m="1632970">to mark that this is your</span> <span m="1633040">approximate</span>
  <span m="1633540">solution</span> <span m="1634090">to remind</span> <span m="1634578">yourself--</span>
  <span m="1639458">function</span> <span m="1639950">of</span> <span m="1640030">the</span>
  <span m="1640110">approximate</span> <span m="1640630">solution</span> <span m="1641090">n</span>
  <span m="1641540">of</span> <span m="1641990">x</span> <span m="1642440">is</span>
  <span m="1642840">d by dx</span> <span m="1643334">of</span> <span m="1643828">kd</span>
  <span m="1644322">t</span> <span m="1644816">tilde</span> <span m="1645310">dx</span>
  <span m="1645804">plus</span> <span m="1646298">q.</span></p><p><span m="1647780">So</span>
  <span m="1648280">does</span> <span m="1648340">someone want to give</span> <span
  m="1648520">me</span> <span m="1648780">in</span> <span m="1649183">words,</span>
  <span m="1649990">what</span> <span m="1650610">is</span> <span m="1650770">the</span>
  <span m="1650870">residual?</span> <span m="1651780">Use</span> <span m="1652230">some</span>
  <span m="1652680">words</span> <span m="1653130">to</span> <span m="1653390">describe</span>
  <span m="1654348">it.</span></p><p><span m="1657701">AUDIENCE: [INAUDIBLE].</span></p><p><span
  m="1662012">PROFESSOR: Yeah,</span> <span m="1662491">good.</span> <span m="1663710">So</span>
  <span m="1663900">the</span> <span m="1664010">residual</span> <span m="1664710">is</span>
  <span m="1665570">the</span> <span m="1665680">amount</span> <span m="1666030">that</span>
  <span m="1666120">the</span> <span m="1666220">approximate</span> <span m="1666720">solution</span>
  <span m="1667350">doesn''t</span> <span m="1667900">satisfy</span> <span m="1668400">the</span>
  <span m="1668850">PDE.</span> <span m="1669750">In other words, if</span> <span
  m="1669870">we</span> <span m="1669960">come</span> <span m="1670120">back</span>
  <span m="1670320">to</span> <span m="1670410">our</span> <span m="1670530">original</span>
  <span m="1670860">PDE,</span> <span m="1671860">we</span> <span m="1671990">brought</span>
  <span m="1672180">everything</span> <span m="1672720">to</span> <span m="1672790">the</span>
  <span m="1672880">left</span> <span m="1673070">hand</span> <span m="1673260">side.</span>
  <span m="1673550">So it</span> <span m="1674015">would read</span> <span m="1674480">d
  by dx</span> <span m="1674945">of</span> <span m="1675410">kdtdx</span> <span m="1675875">plus</span>
  <span m="1676340">q</span> <span m="1676770">equals 0.</span> <span m="1679554">Then</span>
  <span m="1680020">if</span> <span m="1680200">we</span> <span m="1680560">take,</span>
  <span m="1680700">instead</span> <span m="1680810">of</span> <span m="1681040">t,</span>
  <span m="1681570">the</span> <span m="1682130">actual</span> <span m="1682570">solution,</span>
  <span m="1683010">if</span> <span m="1683120">we</span> <span m="1683220">take</span>
  <span m="1683460">an</span> <span m="1683520">approximate</span> <span m="1684090">solution,</span>
  <span m="1684690">t tilde,</span> <span m="1685810">we</span> <span m="1686030">substituted</span>
  <span m="1686422">it</span> <span m="1686814">in,</span> <span m="1687600">the</span>
  <span m="1687710">residual</span> <span m="1688170">is</span> <span m="1688270">how</span>
  <span m="1688390">much</span> <span m="1688630">we</span> <span m="1688720">get</span>
  <span m="1688910">that''s</span> <span m="1689060">different</span> <span m="1689370">from</span>
  <span m="1689560">0.</span> <span m="1691280">So</span> <span m="1691460">it</span>
  <span m="1691560">tells</span> <span m="1691900">us</span> <span m="1692330">by</span>
  <span m="1692580">how</span> <span m="1692820">much</span> <span m="1693670">the</span>
  <span m="1693780">approximate</span> <span m="1694350">solution,</span> <span m="1694685">t
  tilde,</span> <span m="1695950">does</span> <span m="1696140">not</span> <span m="1696600">satisfy</span>
  <span m="1697100">the</span> <span m="1697180">[INAUDIBLE]</span> <span m="1697646">equation.</span></p><p><span
  m="1699980">Yes?</span> <span m="1701140">So</span> <span m="1701350">someone</span>
  <span m="1701825">tell</span> <span m="1702300">me, how is</span> <span m="1702560">the</span>
  <span m="1702670">residual--</span> <span m="1703410">is</span> <span m="1703830">the</span>
  <span m="1703930">residual</span> <span m="1704280">the</span> <span m="1704370">same</span>
  <span m="1704670">thing</span> <span m="1704880">as</span> <span m="1705070">the</span>
  <span m="1705210">error?</span> <span m="1706280">If</span> <span m="1706430">I
  define</span> <span m="1706830">the</span> <span m="1707010">error</span> <span
  m="1707660">to</span> <span m="1707810">be</span> <span m="1708050">the</span> <span
  m="1708120">difference</span> <span m="1708900">between</span> <span m="1709440">the</span>
  <span m="1709530">exact</span> <span m="1710030">solution,</span> <span m="1710325">t,</span>
  <span m="1711960">and</span> <span m="1712460">the</span> <span m="1712530">approximate</span>
  <span m="1713060">solution</span> <span m="1713450">t tilde,</span> <span m="1713860">is</span>
  <span m="1714130">the</span> <span m="1714230">residual</span> <span m="1714730">the</span>
  <span m="1714800">same</span> <span m="1715040">thing</span> <span m="1715240">as</span>
  <span m="1715360">the</span> <span m="1715837">error?</span></p><p><span m="1720130">Not</span>
  <span m="1720370">the</span> <span m="1720440">same</span> <span m="1720630">thing.</span>
  <span m="1720955">So</span> <span m="1721280">how</span> <span m="1721470">is</span>
  <span m="1721580">it</span> <span m="1721670">different?</span></p><p><span m="1724630">AUDIENCE:
  [INAUDIBLE].</span></p><p><span m="1732130">PROFESSOR: Yes.</span> <span m="1732350">So
  let''s</span> <span m="1732880">think</span> <span m="1733110">about</span> <span
  m="1733340">that.</span> <span m="1733570">So</span> <span m="1733750">if</span>
  <span m="1733860">we</span> <span m="1734030">define</span> <span m="1734790">the</span>
  <span m="1734940">error</span> <span m="1736650">to be</span> <span m="1737120">t</span>
  <span m="1740500">minus</span> <span m="1741517">t tilde,</span> <span m="1744716">this
  will</span> <span m="1745180">be</span> <span m="1745460">our--</span> <span m="1746175">is</span>
  <span m="1746540">this</span> <span m="1746630">thing</span> <span m="1746850">a</span>
  <span m="1746900">function</span> <span m="1747550">over</span> <span m="1747740">the</span>
  <span m="1747810">whole</span> <span m="1747950">domain?</span> <span m="1753190">Is</span>
  <span m="1753370">e</span> <span m="1753560">a</span> <span m="1753640">function</span>
  <span m="1753930">of</span> <span m="1754010">x?</span></p><p><span m="1755820">Yeah.</span>
  <span m="1756540">Right.</span> <span m="1758010">So</span> <span m="1758190">e</span>
  <span m="1758230">is a function</span> <span m="1758580">of</span> <span m="1758740">x</span>
  <span m="1759550">if it''s</span> <span m="1759660">t</span> <span m="1759900">of
  x minus</span> <span m="1760230">t tilde</span> <span m="1760632">of x.</span> <span
  m="1761840">Yeah?</span></p><p><span m="1763050">How about</span> <span m="1763370">the
  residual?</span> <span m="1763860">Is</span> <span m="1763950">the</span> <span
  m="1764000">residual</span> <span m="1764370">a</span> <span m="1764780">function</span>
  <span m="1765170">of x?</span></p><p><span m="1766990">Yeah.</span> <span m="1767340">So</span>
  <span m="1767450">they''re</span> <span m="1767630">actually</span> <span m="1767940">both--</span>
  <span m="1768530">they''re</span> <span m="1768700">both</span> <span m="1769050">functions</span>
  <span m="1769740">that</span> <span m="1769900">we</span> <span m="1770050">could</span>
  <span m="1770300">plot--</span> <span m="1771840">we could plot</span> <span m="1772510">over</span>
  <span m="1772700">the</span> <span m="1772780">whole</span> <span m="1772960">the</span>
  <span m="1773050">domain</span> <span m="1773300">x.</span> <span m="1773650">We</span>
  <span m="1773740">could</span> <span m="1773910">plot</span> <span m="1774610">e
  of x</span> <span m="1775842">and</span> <span m="1776270">we could plot</span>
  <span m="1777080">r of</span> <span m="1777547">t tilde,</span> <span m="1778014">x.</span>
  <span m="1778950">So</span> <span m="1779070">they''re</span> <span m="1779170">both</span>
  <span m="1779660">functions</span> <span m="1780050">that are</span> <span m="1780160">defined</span>
  <span m="1780580">over</span> <span m="1781056">the</span> <span m="1781532">whole</span>
  <span m="1782008">domain.</span></p><p><span m="1782960">But</span> <span m="1783320">they''re</span>
  <span m="1783460">measuring</span> <span m="1783850">different</span> <span m="1784220">things,</span>
  <span m="1784590">right?</span></p><p><span m="1788937">AUDIENCE: [INAUDIBLE].</span></p><p><span
  m="1797160">PROFESSOR: Yeah.</span> <span m="1798280">That''s</span> <span m="1798470">exactly</span>
  <span m="1798760">right.</span> <span m="1799230">The</span> <span m="1799560">error</span>
  <span m="1799700">is measuring</span> <span m="1801300">how</span> <span m="1801620">wrong</span>
  <span m="1802030">is</span> <span m="1802670">t--</span> <span m="1803430">t of
  x.</span> <span m="1803810">What''s</span> <span m="1804010">the</span> <span m="1804130">error</span>
  <span m="1804440">in</span> <span m="1804640">t.</span> <span m="1805700">But</span>
  <span m="1805860">the</span> <span m="1805950">residual</span> <span m="1806990">is</span>
  <span m="1807100">measuring</span> <span m="1807630">how</span> <span m="1807780">far</span>
  <span m="1808080">is</span> <span m="1808180">the</span> <span m="1808270">equation</span>
  <span m="1808810">from</span> <span m="1808980">being</span> <span m="1809170">satisfied.</span>
  <span m="1810350">What''s</span> <span m="1811040">really</span> <span m="1811460">amazing</span>
  <span m="1811870">about</span> <span m="1812140">the</span> <span m="1812240">residual?</span>
  <span m="1813642">Yeah?</span></p><p><span m="1814088">AUDIENCE: [INAUDIBLE].</span></p><p><span
  m="1814980">PROFESSOR: Exactly</span> <span m="1815540">right.</span> <span m="1816040">Which</span>
  <span m="1816220">is</span> <span m="1816350">real--</span> <span m="1816590">isn''t</span>
  <span m="1816690">that</span> <span m="1816770">cool?</span> <span m="1818920">And</span>
  <span m="1819080">that''s</span> <span m="1819440">kind</span> <span m="1819640">of--</span>
  <span m="1820110">I</span> <span m="1820220">mean,</span> <span m="1820350">I</span>
  <span m="1820440">think</span> <span m="1820870">in</span> <span m="1820990">a</span>
  <span m="1821080">way</span> <span m="1821290">that''s</span> <span m="1821550">kind</span>
  <span m="1821820">of</span> <span m="1821890">like</span> <span m="1822170">the</span>
  <span m="1822310">amazing</span> <span m="1822660">breakthrough</span> <span m="1823110">here,</span>
  <span m="1823410">is</span> <span m="1823650">that</span> <span m="1824910">yeah</span>
  <span m="1825160">we''d</span> <span m="1825320">love</span> <span m="1825520">to</span>
  <span m="1825600">know</span> <span m="1825760">the</span> <span m="1825890">error,</span>
  <span m="1826300">but</span> <span m="1826440">if</span> <span m="1826550">we</span>
  <span m="1826640">knew</span> <span m="1826820">the</span> <span m="1826920">error</span>
  <span m="1827260">we</span> <span m="1827380">would</span> <span m="1827520">know</span>
  <span m="1827800">the</span> <span m="1827900">true</span> <span m="1828110">solution,</span>
  <span m="1828600">so</span> <span m="1829090">then</span> <span m="1829880">why</span>
  <span m="1830190">would</span> <span m="1830400">we</span> <span m="1830500">be</span>
  <span m="1830590">doing</span> <span m="1830830">all</span> <span m="1830970">of</span>
  <span m="1831070">this?</span> <span m="1831710">The</span> <span m="1831840">really</span>
  <span m="1832200">cool</span> <span m="1832440">thing</span> <span m="1832590">about</span>
  <span m="1832780">the</span> <span m="1832840">residual</span> <span m="1833140">is</span>
  <span m="1833440">that</span> <span m="1833570">we</span> <span m="1833690">don''t</span>
  <span m="1833930">need</span> <span m="1834160">to</span> <span m="1834260">know</span>
  <span m="1834700">the</span> <span m="1834790">true</span> <span m="1835490">solution.</span>
  <span m="1836540">We</span> <span m="1836680">can</span> <span m="1836880">take</span>
  <span m="1837140">our</span> <span m="1837290">approximate</span> <span m="1837860">solution.</span>
  <span m="1838640">We</span> <span m="1838840">know</span> <span m="1839180">the</span>
  <span m="1839780">equation</span> <span m="1840260">that</span> <span m="1840460">should</span>
  <span m="1840910">satisfy.</span> <span m="1842300">And</span> <span m="1842420">we</span>
  <span m="1842520">can</span> <span m="1842750">measure</span> <span m="1843370">how</span>
  <span m="1843590">far</span> <span m="1843890">off</span> <span m="1844120">it</span>
  <span m="1844250">is.</span></p><p><span m="1845210">Now</span> <span m="1845900">just</span>
  <span m="1846120">because</span> <span m="1846410">the</span> <span m="1846520">residual</span>
  <span m="1847370">is</span> <span m="1847590">small,</span> <span m="1848100">doesn''t</span>
  <span m="1848440">mean</span> <span m="1848640">the</span> <span m="1848740">error</span>
  <span m="1848950">is</span> <span m="1849010">going</span> <span m="1849130">to</span>
  <span m="1849210">be</span> <span m="1849350">small.</span> <span m="1850310">And</span>
  <span m="1850440">that''s</span> <span m="1850650">a</span> <span m="1850720">whole</span>
  <span m="1851070">kind</span> <span m="1851280">of</span> <span m="1851380">field</span>
  <span m="1851680">of</span> <span m="1851750">study.</span> <span m="1852010">Depending</span>
  <span m="1852430">on</span> <span m="1852570">the</span> <span m="1852640">PDE</span>
  <span m="1853360">that</span> <span m="1853580">you''re</span> <span m="1855500">studying,</span>
  <span m="1856550">for</span> <span m="1856690">this</span> <span m="1856860">particular</span>
  <span m="1857260">PDE,</span> <span m="1857690">it</span> <span m="1857800">turns</span>
  <span m="1858010">out</span> <span m="1858130">the</span> <span m="1858210">residual</span>
  <span m="1858620">and</span> <span m="1858700">the</span> <span m="1858770">error</span>
  <span m="1859100">will</span> <span m="1859300">be</span> <span m="1860050">nicely</span>
  <span m="1860550">related.</span> <span m="1861210">But</span> <span m="1861380">if</span>
  <span m="1861480">you</span> <span m="1861580">have</span> <span m="1861710">a</span>
  <span m="1861750">nasty</span> <span m="1862230">PDE,</span> <span m="1863240">the</span>
  <span m="1863380">residual</span> <span m="1863870">might</span> <span m="1864140">not</span>
  <span m="1864330">be</span> <span m="1864460">a</span> <span m="1864530">good</span>
  <span m="1864690">indication</span> <span m="1865160">of</span> <span m="1865250">what''s</span>
  <span m="1865430">going</span> <span m="1865740">on.</span> <span m="1866030">But</span>
  <span m="1866160">it''s</span> <span m="1866280">still</span> <span m="1866510">a</span>
  <span m="1866550">very</span> <span m="1866970">powerful</span> <span m="1867450">thing</span>
  <span m="1868220">that</span> <span m="1868360">can</span> <span m="1868520">give</span>
  <span m="1868660">you</span> <span m="1868810">a</span> <span m="1868860">sense</span>
  <span m="1869370">of</span> <span m="1869660">how</span> <span m="1870150">good</span>
  <span m="1870380">is</span> <span m="1870470">your</span> <span m="1870570">approximate</span>
  <span m="1871070">solution</span> <span m="1871390">without</span> <span m="1871650">actually</span>
  <span m="1871900">knowing</span> <span m="1872170">the</span> <span m="1872320">truth.</span>
  <span m="1872590">And we''re going</span> <span m="1872870">to</span> <span m="1872950">use</span>
  <span m="1873210">this</span> <span m="1873628">idea</span> <span m="1874046">of</span>
  <span m="1874464">a</span> <span m="1874882">residual</span> <span m="1875720">over</span>
  <span m="1876070">and</span> <span m="1876180">over</span> <span m="1876690">and</span>
  <span m="1876820">over</span> <span m="1877050">again,</span> <span m="1877500">because</span>
  <span m="1877790">we</span> <span m="1877880">don''t</span> <span m="1878120">need</span>
  <span m="1878270">to</span> <span m="1878350">know</span> <span m="1878580">the</span>
  <span m="1878740">actual</span> <span m="1879570">solution.</span></p><p><span m="1883740">Sometimes</span>
  <span m="1884140">I</span> <span m="1884190">know</span> <span m="1884350">the</span>
  <span m="1884450">residual</span> <span m="1884840">can</span> <span m="1884980">be
  something</span> <span m="1885240">that</span> <span m="1885370">gets</span> <span
  m="1885610">people</span> <span m="1885860">tripped</span> <span m="1886080">up,</span>
  <span m="1886200">because they''re</span> <span m="1886620">kind</span> <span m="1886780">of--</span>
  <span m="1887395">it''s</span> <span m="1887830">pretty</span> <span m="1888030">neat,</span>
  <span m="1888250">right?</span> <span m="1888820">Take</span> <span m="1889050">the</span>
  <span m="1889140">approximation,</span> <span m="1889960">substitute</span> <span
  m="1890280">it</span> <span m="1890600">into</span> <span m="1890840">the</span>
  <span m="1890980">PDE,</span> <span m="1891400">and</span> <span m="1891610">see</span>
  <span m="1892040">how</span> <span m="1892190">well</span> <span m="1892410">you''re</span>
  <span m="1892510">doing.</span> <span m="1893650">Not</span> <span m="1893850">the</span>
  <span m="1893930">same</span> <span m="1894180">thing</span> <span m="1894370">as</span>
  <span m="1894490">the</span> <span m="1894690">error.</span></p><p><span m="1898586">So</span>
  <span m="1899560">one</span> <span m="1899870">thing--</span> <span m="1901770">so,</span>
  <span m="1902250">no</span> <span m="1902510">it''s</span> <span m="1902690">not
  the</span> <span m="1903040">same</span> <span m="1903310">as</span> <span m="1903430">the
  error,</span> <span m="1903590">but one thing</span> <span m="1903770">we</span>
  <span m="1903900">do</span> <span m="1904010">know</span> <span m="1904210">is</span>
  <span m="1904310">that</span> <span m="1904400">what</span> <span m="1904510">happens</span>
  <span m="1904870">if</span> <span m="1904990">I</span> <span m="1905150">substitute</span>
  <span m="1905650">an</span> <span m="1905780">exact</span> <span m="1906160">solution</span>
  <span m="1906620">here,</span> <span m="1908490">residual</span> <span m="1908890">is</span>
  <span m="1909030">0</span> <span m="1909390">everywhere.</span> <span m="1910881">Yeah.
  OK.</span></p><p><span m="1913370">All</span> <span m="1913520">right.</span> <span
  m="1913880">So</span> <span m="1915670">how</span> <span m="1915980">is</span> <span
  m="1916130">that</span> <span m="1916400">going</span> <span m="1916830">to</span>
  <span m="1916950">help</span> <span m="1917320">us</span> <span m="1921770">with</span>
  <span m="1921930">our</span> <span m="1922440">collocation</span> <span m="1923100">method?</span>
  <span m="1924550">So</span> <span m="1924910">we</span> <span m="1925130">defined</span>
  <span m="1925800">the</span> <span m="1927250">residual.</span> <span m="1929420">And</span>
  <span m="1933224">what</span> <span m="1933700">we''re</span> <span m="1933780">going</span>
  <span m="1933910">to</span> <span m="1934000">do--</span> <span m="1934250">you
  can</span> <span m="1934560">see</span> <span m="1934990">now</span> <span m="1935420">what</span>
  <span m="1935520">we''re</span> <span m="1935590">going</span> <span m="1935710">to</span>
  <span m="1935780">do</span> <span m="1935890">with</span> <span m="1936020">the</span>
  <span m="1936080">collocation</span> <span m="1936690">method,</span> <span m="1937020">is</span>
  <span m="1937170">when</span> <span m="1937290">I</span> <span m="1937390">said</span>
  <span m="1937670">that we</span> <span m="1937800">enforce</span> <span m="1938350">the</span>
  <span m="1938440">PDE,</span> <span m="1938970">in</span> <span m="1939250">point</span>
  <span m="1939640">what</span> <span m="1939770">we''re</span> <span m="1939850">going</span>
  <span m="1939990">to</span> <span m="1940050">do</span> <span m="1940280">is</span>
  <span m="1940450">we''re</span> <span m="1940550">going</span> <span m="1940690">to</span>
  <span m="1940940">set</span> <span m="1941310">the</span> <span m="1941480">residual</span>
  <span m="1942060">to</span> <span m="1942270">be</span> <span m="1942450">0</span>
  <span m="1943122">at</span> <span m="1943460">n</span> <span m="1943690">point.</span></p><p><span
  m="1944335">So</span> <span m="1944680">in other</span> <span m="1944860">words</span>
  <span m="1945080">we''re</span> <span m="1945150">going</span> <span m="1945280">to</span>
  <span m="1945360">pick</span> <span m="1945655">n.</span> <span m="1945950">In</span>
  <span m="1946410">our</span> <span m="1946560">case</span> <span m="1946910">2</span>
  <span m="1947180">values</span> <span m="1947330">of</span> <span m="1947540">x.</span>
  <span m="1948670">Right?</span> <span m="1948950">So</span> <span m="1949020">remember</span>
  <span m="1949240">we</span> <span m="1949340">said</span> <span m="1949540">that</span>
  <span m="1949730">the residual</span> <span m="1950110">was</span> <span m="1950330">a</span>
  <span m="1950420">function</span> <span m="1950900">of</span> <span m="1951020">x,</span>
  <span m="1951650">something?</span> <span m="1952700">We''re</span> <span m="1952800">going</span>
  <span m="1952920">to</span> <span m="1952990">pick</span> <span m="1953330">two</span>
  <span m="1953560">values</span> <span m="1953900">of</span> <span m="1954020">x.</span>
  <span m="1955060">We''re</span> <span m="1955160">going</span> <span m="1955280">to</span>
  <span m="1955360">set</span> <span m="1955550">the</span> <span m="1955640">residual</span>
  <span m="1956530">to be</span> <span m="1956730">0</span> <span m="1957100">at</span>
  <span m="1957230">those</span> <span m="1957460">particular</span> <span m="1957850">points.</span>
  <span m="1958220">Pin</span> <span m="1958440">them</span> <span m="1958580">down.</span>
  <span m="1959660">And</span> <span m="1959800">that''s</span> <span m="1960000">going</span>
  <span m="1960120">to</span> <span m="1960210">give</span> <span m="1960360">us</span>
  <span m="1960520">the</span> <span m="1960610">two</span> <span m="1960810">conditions</span>
  <span m="1961320">that</span> <span m="1961460">we</span> <span m="1961560">need</span>
  <span m="1962570">to</span> <span m="1962720">solve</span> <span m="1963240">for</span>
  <span m="1963420">the</span> <span m="1963510">two</span> <span m="1963710">coefficients,</span>
  <span m="1964450">a1</span> <span m="1964900">and</span> <span m="1965030">a2,</span>
  <span m="1965460">that</span> <span m="1965640">are</span> <span m="1965690">multiplying</span>
  <span m="1966220">our</span> <span m="1966290">basic</span> <span m="1966630">function.</span></p><p><span
  m="1969070">OK?</span> <span m="1969690">That</span> <span m="1970970">logic</span>
  <span m="1971280">is</span> <span m="1971420">clear?</span> <span m="1971790">Yep.</span>
  <span m="1972260">So</span> <span m="1972720">we</span> <span m="1972820">can</span>
  <span m="1972930">just</span> <span m="1973130">work</span> <span m="1973370">through</span>
  <span m="1974550">the</span> <span m="1974660">math</span> <span m="1974910">that</span>
  <span m="1975020">actually</span> <span m="1975290">does</span> <span m="1975540">this.</span>
  <span m="1975820">And</span> <span m="1975940">I</span> <span m="1976020">won''t</span>
  <span m="1976740">go</span> <span m="1976970">in</span> <span m="1979340">too</span>
  <span m="1979550">much</span> <span m="1979770">detail,</span> <span m="1980300">but</span>
  <span m="1980370">if</span> <span m="1980510">you</span> <span m="1980660">want</span>
  <span m="1980800">me</span> <span m="1980900">to</span> <span m="1981340">back</span>
  <span m="1981710">up</span> <span m="1981830">and</span> <span m="1982020">do</span>
  <span m="1982200">any</span> <span m="1982350">more</span> <span m="1982640">of
  the</span> <span m="1982760">detail,</span> <span m="1983840">can</span> <span m="1984060">do.</span></p><p><span
  m="1984310">So</span> <span m="1984610">in</span> <span m="1984700">our</span> <span
  m="1984840">example,</span> <span m="1986060">remember</span> <span m="1986810">we</span>
  <span m="1987080">set</span> <span m="1988730">k</span> <span m="1989025">to</span>
  <span m="1989320">be 1</span> <span m="1989793">and</span> <span m="1990740">q</span>
  <span m="1991190">was</span> <span m="1991628">50e</span> <span m="1992066">to the
  x.</span> <span m="1992942">So</span> <span m="1993380">this</span> <span m="1993510">is</span>
  <span m="1993590">a</span> <span m="1993640">situation</span> <span m="1994090">where</span>
  <span m="1994190">we</span> <span m="1994310">do</span> <span m="1994530">have</span>
  <span m="1994690">the</span> <span m="1994790">exact</span> <span m="1995120">solution</span>
  <span m="1995490">but</span> <span m="1995610">we</span> <span m="1995680">don''t</span>
  <span m="1995820">want</span> <span m="1995940">to</span> <span m="1996020">use</span>
  <span m="1996270">it.</span> <span m="1997080">And</span> <span m="1997210">again,</span>
  <span m="1997540">just</span> <span m="1997700">to</span> <span m="1997780">remind</span>
  <span m="1998160">you</span> <span m="1998390">that</span> <span m="1998590">our</span>
  <span m="1998870">approximate</span> <span m="1999295">solution</span> <span m="2000063">is</span>
  <span m="2000406">this</span> <span m="2000750">expansion</span> <span m="2001380">that</span>
  <span m="2001480">looks</span> <span m="2001700">like</span> <span m="2002000">100</span>
  <span m="2003510">plus</span> <span m="2004130">some</span> <span m="2004330">amount,</span>
  <span m="2004850">a1</span> <span m="2005540">times</span> <span m="2006030">our</span>
  <span m="2006500">quadratic</span> <span m="2007070">basic</span> <span m="2007400">function,</span>
  <span m="2008160">c1,</span> <span m="2009540">plus</span> <span m="2010410">some</span>
  <span m="2010590">amount</span> <span m="2010980">a2,</span> <span m="2012590">times</span>
  <span m="2013230">our</span> <span m="2013576">cubic</span> <span m="2014270">basis</span>
  <span m="2014660">function,</span> <span m="2016240">c2.</span> <span m="2018080">And</span>
  <span m="2018240">actually</span> <span m="2018490">let</span> <span m="2019040">me</span>
  <span m="2019160">write</span> <span m="2019390">that</span> <span m="2019550">out.</span>
  <span m="2020350">It''s</span> <span m="2020460">100</span> <span m="2021130">plus</span>
  <span m="2021480">a1,</span> <span m="2023550">1</span> <span m="2023800">plus</span>
  <span m="2024000">x,</span> <span m="2025110">1</span> <span m="2025490">minus</span>
  <span m="2025850">x,</span> <span m="2027940">plus</span> <span m="2028810">a to
  x,</span> <span m="2030440">1 plus</span> <span m="2030660">x,</span> <span m="2031420">1</span>
  <span m="2031680">minus</span> <span m="2032070">x.</span></p><p><span m="2036730">OK.</span>
  <span m="2037130">So</span> <span m="2037560">here''s</span> <span m="2037830">our</span>
  <span m="2038000">residual.</span> <span m="2038470">It''s</span> <span m="2038940">d
  by dx--</span> <span m="2039760">the k is</span> <span m="2040320">just</span> <span
  m="2040480">1,</span> <span m="2040780">so</span> <span m="2040970">it''s</span>
  <span m="2041280">actually</span> <span m="2041490">second</span> <span m="2041800">derivative</span>
  <span m="2042280">of</span> <span m="2042410">the</span> <span m="2042500">approximate</span>
  <span m="2043060">solution</span> <span m="2043525">plus</span> <span m="2043990">q.</span>
  <span m="2045380">So</span> <span m="2045920">we''re</span> <span m="2046020">going</span>
  <span m="2046330">to</span> <span m="2046420">need</span> <span m="2048340">a</span>
  <span m="2048980">second</span> <span m="2049310">derivative</span> <span m="2050040">of</span>
  <span m="2050389">our</span> <span m="2050460">approximate</span> <span m="2051130">solution</span>
  <span m="2052420">with</span> <span m="2052650">respect</span> <span m="2053090">to</span>
  <span m="2053190">x.</span> <span m="2055535">So</span> <span m="2059290">the</span>
  <span m="2059380">100</span> <span m="2059770">is going</span> <span m="2059889">to</span>
  <span m="2059960">go</span> <span m="2060179">away</span> <span m="2060659">from</span>
  <span m="2060860">this</span> <span m="2060940">guy.</span> <span m="2061350">What</span>
  <span m="2061469">am</span> <span m="2061550">I</span> <span m="2061639">going</span>
  <span m="2061790">to</span> <span m="2061860">get?</span> <span m="2062090">Only</span>
  <span m="2062320">the</span> <span m="2062400">quadratic</span> <span m="2062850">terms
  are</span> <span m="2063110">going</span> <span m="2063260">to</span> <span m="2063350">stick</span>
  <span m="2063560">around,</span> <span m="2063969">right?</span> <span m="2064010">I''m</span>
  <span m="2064310">going</span> <span m="2064429">to</span> <span m="2064500">get</span>
  <span m="2064710">a</span> <span m="2065449">minus</span> <span m="2065770">x</span>
  <span m="2066010">squared</span> <span m="2066530">multiplying</span> <span m="2068239">a1.</span>
  <span m="2069060">So when I</span> <span m="2069110">differentiate</span> <span
  m="2069690">that--</span> <span m="2070510">where</span> <span m="2070730">I differentiate</span>
  <span m="2070989">that</span> <span m="2071219">twice,</span> <span m="2071580">I''m</span>
  <span m="2071670">going</span> <span m="2071790">to</span> <span m="2071850">get</span>
  <span m="2072010">minus</span> <span m="2073090">[? 2a1. ?]</span> <span m="2074570">And</span>
  <span m="2074710">then</span> <span m="2074880">from</span> <span m="2075080">this</span>
  <span m="2075170">guy</span> <span m="2075530">here</span> <span m="2076000">I''m</span>
  <span m="2076170">going</span> <span m="2076300">to</span> <span m="2076380">have</span>
  <span m="2077040">the</span> <span m="2078010">cubic</span> <span m="2078380">term--</span>
  <span m="2080048">is</span> <span m="2080469">that</span> <span m="2080659">me</span>
  <span m="2080810">beeping?</span> <span m="2082070">Oh</span> <span m="2082500">that''s</span>
  <span m="2082600">you.</span> <span m="2083499">OK.</span> <span m="2083989">It''s
  your</span> <span m="2084460">shoe</span> <span m="2084540">beeping?</span></p><p><span
  m="2085319">AUDIENCE: [INAUDIBLE].</span></p><p><span m="2087184">PROFESSOR: OK.</span>
  <span m="2088525">All right.</span></p><p><span m="2089870">Cubic</span> <span m="2090139">term.</span>
  <span m="2090680">We''re going to</span> <span m="2090960">have</span> <span m="2091250">minus</span>
  <span m="2091750">x</span> <span m="2092240">cubed</span> <span m="2092730">times</span>
  <span m="2093000">a</span> <span m="2093270">a2.</span> <span m="2095199">So we''re</span>
  <span m="2095239">going</span> <span m="2095370">to</span> <span m="2095429">get</span>
  <span m="2095710">minus</span> <span m="2097389">[? 6a2 ?]</span> <span m="2099300">times</span>
  <span m="2099916">x</span> <span m="2100590">coming</span> <span m="2100910">out,</span>
  <span m="2101090">and</span> <span m="2101240">then</span> <span m="2101300">the</span>
  <span m="2101665">quadratic</span> <span m="2102030">terms actually</span> <span
  m="2102250">drop</span> <span m="2102440">away</span> <span m="2102690">in</span>
  <span m="2102800">that</span> <span m="2105520">last</span> <span m="2105760">one.</span>
  <span m="2107810">OK.</span> <span m="2108200">So</span> <span m="2108690">there''s</span>
  <span m="2108960">the</span> <span m="2110810">second</span> <span m="2111070">derivative</span>
  <span m="2111710">of</span> <span m="2111870">the</span> <span m="2112330">approximate</span>
  <span m="2112660">solution.</span> <span m="2113370">And</span> <span m="2113500">you</span>
  <span m="2113580">know,</span> <span m="2113830">again,</span> <span m="2114290">we''ve</span>
  <span m="2114520">still got</span> <span m="2114810">these</span> <span m="2115070">constants</span>
  <span m="2115640">hanging</span> <span m="2115880">around,</span> <span m="2116200">because
  we</span> <span m="2116390">don''t</span> <span m="2116500">know</span> <span m="2116590">what</span>
  <span m="2116740">they</span> <span m="2116960">are</span> <span m="2117090">yet.</span>
  <span m="2119316">So</span> <span m="2119790">we</span> <span m="2119910">can</span>
  <span m="2120070">substitute</span> <span m="2120530">that in</span> <span m="2120750">to</span>
  <span m="2121085">our</span> <span m="2121420">expression</span> <span m="2121840">for</span>
  <span m="2121970">the</span> <span m="2122080">residual,</span> <span m="2123710">which</span>
  <span m="2123830">again</span> <span m="2124210">is</span> <span m="2124250">a function</span>
  <span m="2124570">of</span> <span m="2124760">our</span> <span m="2125030">approximate</span>
  <span m="2125490">solution</span> <span m="2126020">and</span> <span m="2126190">x.</span>
  <span m="2127680">And</span> <span m="2128100">it''s</span> <span m="2128390">just--</span>
  <span m="2130490">that</span> <span m="2130600">second</span> <span m="2130880">derivative</span>
  <span m="2131470">is</span> <span m="2131660">1</span> <span m="2132105">plus</span>
  <span m="2132550">q.</span> <span m="2133460">So</span> <span m="2133590">it''s</span>
  <span m="2133840">going</span> <span m="2133970">to</span> <span m="2134040">be</span>
  <span m="2134150">minus</span> <span m="2134860">2a</span> <span m="2135180">1,</span>
  <span m="2135620">minus</span> <span m="2136100">6a2</span> <span m="2137660">times</span>
  <span m="2137980">x,</span> <span m="2138920">plus</span> <span m="2139390">q,</span>
  <span m="2139820">which</span> <span m="2139920">is</span> <span m="2140040">50e</span>
  <span m="2140513">to the x.</span></p><p><span m="2144770">OK.</span> <span m="2145040">So</span>
  <span m="2145150">there''s the</span> <span m="2145350">expression</span> <span
  m="2146070">for</span> <span m="2146290">the</span> <span m="2146380">residual</span>
  <span m="2146870">for</span> <span m="2147050">this</span> <span m="2147260">problem.</span></p><p><span
  m="2149250">So</span> <span m="2149370">you</span> <span m="2149540">look</span>
  <span m="2149720">at</span> <span m="2149810">this</span> <span m="2150050">and</span>
  <span m="2150230">you</span> <span m="2150330">immediately</span> <span m="2150850">see,</span>
  <span m="2151430">well,</span> <span m="2153460">there''s</span> <span m="2153620">no</span>
  <span m="2153810">way</span> <span m="2154030">the</span> <span m="2154100">residual</span>
  <span m="2154420">can</span> <span m="2154530">be</span> <span m="2154640">0</span>
  <span m="2154950">everywhere,</span> <span m="2155410">right?</span> <span m="2155980">There''s</span>
  <span m="2156140">no</span> <span m="2156310">way</span> <span m="2156600">that</span>
  <span m="2156770">this</span> <span m="2157160">linear</span> <span m="2157760">term--</span>
  <span m="2158090">no</span> <span m="2158190">matter</span> <span m="2158370">what</span>
  <span m="2158550">we</span> <span m="2158640">choose</span> <span m="2158930">for</span>
  <span m="2159060">a1</span> <span m="2159140">and</span> <span m="2159310">a2,</span>
  <span m="2159770">there''s</span> <span m="2159940">no</span> <span m="2160090">way</span>
  <span m="2160250">we</span> <span m="2160390">can</span> <span m="2160530">make</span>
  <span m="2160710">it</span> <span m="2160780">equal</span> <span m="2161000">to</span>
  <span m="2161070">50x</span> <span m="2161450">to the x</span> <span m="2162100">for</span>
  <span m="2162210">all</span> <span m="2162360">values</span> <span m="2162670">of</span>
  <span m="2162770">x</span> <span m="2163100">between</span> <span m="2163450">minus</span>
  <span m="2163750">1</span> <span m="2163930">and</span> <span m="2164030">1.</span>
  <span m="2165120">So that</span> <span m="2165290">immediately</span> <span m="2165730">tells</span>
  <span m="2166030">you</span> <span m="2166220">that</span> <span m="2166330">those</span>
  <span m="2166590">two</span> <span m="2166780">basis</span> <span m="2167130">functions</span>
  <span m="2167620">we</span> <span m="2167790">used</span> <span m="2168390">are</span>
  <span m="2168490">not</span> <span m="2168800">rich</span> <span m="2169130">enough</span>
  <span m="2169530">to</span> <span m="2169640">describe</span> <span m="2170120">the</span>
  <span m="2170190">solution</span> <span m="2170930">exactly,</span> <span m="2171870">which</span>
  <span m="2172010">is</span> <span m="2172110">not</span> <span m="2172250">really</span>
  <span m="2172460">a</span> <span m="2172550">surprise,</span> <span m="2173130">right?</span></p><p><span
  m="2174200">But</span> <span m="2174350">now</span> <span m="2174520">the</span>
  <span m="2174580">question</span> <span m="2174910">is,</span> <span m="2175140">what</span>
  <span m="2175330">are</span> <span m="2175390">good</span> <span m="2175680">choices</span>
  <span m="2176350">that</span> <span m="2176500">we</span> <span m="2176600">can</span>
  <span m="2176790">make</span> <span m="2177240">for</span> <span m="2177510">a1</span>
  <span m="2178020">and</span> <span m="2178140">a2</span> <span m="2178820">so</span>
  <span m="2179060">that</span> <span m="2179340">we</span> <span m="2179420">get</span>
  <span m="2179540">a</span> <span m="2179570">decent</span> <span m="2180300">solution?</span>
  <span m="2182040">And</span> <span m="2182660">again,</span> <span m="2184190">what</span>
  <span m="2184430">are</span> <span m="2184490">we</span> <span m="2184590">going</span>
  <span m="2184720">to</span> <span m="2184810">do?</span> <span m="2185050">With</span>
  <span m="2185190">the</span> <span m="2185250">collocation</span> <span m="2185590">method</span>
  <span m="2186340">we''re</span> <span m="2186470">going</span> <span m="2186770">to</span>
  <span m="2186870">pick</span> <span m="2188670">a</span> <span m="2188700">couple</span>
  <span m="2188970">of</span> <span m="2189050">points</span> <span m="2189450">for</span>
  <span m="2189630">x.</span> <span m="2191790">And</span> <span m="2191840">we''re</span>
  <span m="2191900">going</span> <span m="2192020">to</span> <span m="2192150">set</span>
  <span m="2192250">the</span> <span m="2192320">residual</span> <span m="2192870">to</span>
  <span m="2193020">0</span> <span m="2193560">at</span> <span m="2194020">those</span>
  <span m="2194150">points.</span> <span m="2195120">That''s</span> <span m="2195320">going</span>
  <span m="2195440">to</span> <span m="2195500">give</span> <span m="2195630">us</span>
  <span m="2195760">the</span> <span m="2195840">condition.</span> <span m="2197190">And</span>
  <span m="2198050">then</span> <span m="2198140">we''ll</span> <span m="2198380">solve</span>
  <span m="2198750">for a1</span> <span m="2199140">and</span> <span m="2199360">a2.</span></p><p><span
  m="2203121">So--</span> <span m="2209037">yep?</span></p><p><span m="2211009">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="2214980">PROFESSOR: So</span> <span m="2215200">if</span>
  <span m="2215350">the</span> <span m="2215450">source</span> <span m="2215840">was</span>
  <span m="2216050">0--</span> <span m="2216900">if</span> <span m="2217090">q</span>
  <span m="2217240">were</span> <span m="2217360">equal</span> <span m="2217430">to
  0,</span> <span m="2219520">and</span> <span m="2219720">this</span> <span m="2219920">were</span>
  <span m="2220070">the</span> <span m="2220200">residual,</span> <span m="2222240">what</span>
  <span m="2222430">would</span> <span m="2222540">you</span> <span m="2222810">choose</span>
  <span m="2223070">for</span> <span m="2223270">a1</span> <span m="2223400">and</span>
  <span m="2223897">a2?</span> <span m="2228870">You</span> <span m="2229060">could</span>
  <span m="2229330">put them</span> <span m="2229673">to be 0.</span> <span m="2230360">So</span>
  <span m="2231170">you</span> <span m="2231310">could</span> <span m="2231450">make</span>
  <span m="2231690">the</span> <span m="2231740">residual</span> <span m="2232430">0</span>
  <span m="2232850">everywhere.</span> <span m="2233520">What would</span> <span m="2233700">then--</span>
  <span m="2234060">what</span> <span m="2234210">would</span> <span m="2234330">our</span>
  <span m="2234480">approximate</span> <span m="2234800">solution</span> <span m="2235330">be</span>
  <span m="2235470">then?</span></p><p><span m="2236065">AUDIENCE: [INAUDIBLE].</span></p><p><span
  m="2238190">PROFESSOR: Yeah,</span> <span m="2238540">t</span> <span m="2238910">equal
  100.</span> <span m="2239390">So if you</span> <span m="2239700">think</span> <span
  m="2239840">about</span> <span m="2240010">the</span> <span m="2240070">physical</span>
  <span m="2240430">problem,</span> <span m="2240760">if</span> <span m="2240890">you</span>
  <span m="2240990">had</span> <span m="2241170">0</span> <span m="2241410">heat</span>
  <span m="2241760">source</span> <span m="2242160">and</span> <span m="2242430">you
  pin</span> <span m="2242700">the</span> <span m="2242780">temperature</span> <span
  m="2243240">to</span> <span m="2243330">be</span> <span m="2243430">100</span> <span
  m="2243680">and 100</span> <span m="2244020">on either end,</span> <span m="2244490">that</span>
  <span m="2244610">would</span> <span m="2244710">be</span> <span m="2244820">the</span>
  <span m="2244990">solution.</span> <span m="2246210">So</span> <span m="2246320">there''s</span>
  <span m="2246490">an</span> <span m="2246560">example</span> <span m="2247190">of</span>
  <span m="2247410">a</span> <span m="2247640">source</span> <span m="2248810">where--</span>
  <span m="2249300">I mean, it''s kind of</span> <span m="2249450">a</span> <span
  m="2249490">trivial</span> <span m="2249820">solution</span> <span m="2250180">but--</span>
  <span m="2250770">of</span> <span m="2250930">a</span> <span m="2250990">source</span>
  <span m="2251240">where</span> <span m="2251590">you</span> <span m="2251790">could</span>
  <span m="2252000">get</span> <span m="2252150">the exact solution.</span></p><p><span
  m="2252680">Yeah?</span></p><p><span m="2255130">AUDIENCE: [INAUDIBLE].</span></p><p><span
  m="2265440">PROFESSOR: Yeah.</span></p><p><span m="2267310">AUDIENCE: [INAUDIBLE].</span></p><p><span
  m="2269310">PROFESSOR: Yeah.</span> <span m="2269720">So the</span> <span m="2270090">question</span>
  <span m="2270480">is,</span> <span m="2271070">if</span> <span m="2271200">we</span>
  <span m="2271320">have</span> <span m="2271520">a</span> <span m="2271560">q</span>
  <span m="2272270">that</span> <span m="2272650">basically</span> <span m="2273140">we</span>
  <span m="2273240">can''t</span> <span m="2273470">do</span> <span m="2273550">the</span>
  <span m="2273660">integration</span> <span m="2274310">by</span> <span m="2274980">hand,</span>
  <span m="2276500">what</span> <span m="2276710">would</span> <span m="2276840">we</span>
  <span m="2276950">do?</span> <span m="2277350">That''s</span> <span m="2277600">a</span>
  <span m="2277640">very</span> <span m="2277900">good</span> <span m="2278080">question,</span>
  <span m="2278470">and</span> <span m="2278810">we''re</span> <span m="2278990">going</span>
  <span m="2279110">to</span> <span m="2279390">talk</span> <span m="2279590">about</span>
  <span m="2279820">that,</span> <span m="2280030">too.</span></p><p><span m="2283300">You''re</span>
  <span m="2283810">going</span> <span m="2283990">to see some--</span> <span m="2284610">in</span>
  <span m="2284910">fact</span> <span m="2285120">you''ve</span> <span m="2285190">already</span>
  <span m="2285530">seen,</span> <span m="2286020">probably</span> <span m="2286370">in</span>
  <span m="2286470">the</span> <span m="2286710">pre-reading,</span> <span m="2286960">some</span>
  <span m="2287130">of the</span> <span m="2287230">integrals</span> <span m="2287580">that</span>
  <span m="2287690">show</span> <span m="2287930">up</span> <span m="2288050">with</span>
  <span m="2288280">two.</span> <span m="2288950">If</span> <span m="2289090">you</span>
  <span m="2289170">can''t</span> <span m="2289380">integrate</span> <span m="2289790">analytically</span>
  <span m="2290370">there''s</span> <span m="2290520">something</span> <span m="2290770">called</span>
  <span m="2290940">Gaussian</span> <span m="2291330">quadrature.</span> <span m="2292190">So</span>
  <span m="2292330">quadrature</span> <span m="2292615">is</span> <span m="2292900">a</span>
  <span m="2293000">way</span> <span m="2293140">to numerically</span> <span m="2293880">do</span>
  <span m="2294050">integrals</span> <span m="2294560">that are</span> <span m="2294900">basically</span>
  <span m="2295240">too</span> <span m="2295340">hard</span> <span m="2295660">to</span>
  <span m="2295720">do</span> <span m="2295870">analytically.</span> <span m="2297110">So</span>
  <span m="2297290">that''s</span> <span m="2297500">going</span> <span m="2297620">to</span>
  <span m="2297690">be</span> <span m="2297810">in</span> <span m="2297920">the</span>
  <span m="2298010">pre-reading</span> <span m="2298490">that''s</span> <span m="2298710">due</span>
  <span m="2299000">next</span> <span m="2299330">Monday,</span> <span m="2299870">and</span>
  <span m="2300250">probably</span> <span m="2300670">[INAUDIBLE]</span> <span m="2301090">will
  be covering</span> <span m="2301520">it</span> <span m="2301790">in</span> <span
  m="2302060">class</span> <span m="2302130">I would</span> <span m="2302290">say</span>
  <span m="2302450">probably</span> <span m="2303290">on</span> <span m="2303500">Monday.</span>
  <span m="2304470">So</span> <span m="2304910">there</span> <span m="2305120">are</span>
  <span m="2305190">ways</span> <span m="2305430">that</span> <span m="2305550">basically</span>
  <span m="2305860">we</span> <span m="2305950">can</span> <span m="2306130">numerically</span>
  <span m="2306680">integrate</span> <span m="2307140">things</span> <span m="2307310">that</span>
  <span m="2307400">we</span> <span m="2307470">can''t</span> <span m="2307660">do</span>
  <span m="2307740">by</span> <span m="2307880">hand.</span></p><p><span m="2308806">PROFESSOR:
  Yep?.</span></p><p><span m="2309732">AUDIENCE: [INAUDIBLE].</span></p><p><span m="2312510">PROFESSOR:
  Yeah.</span> <span m="2312860">So in that</span> <span m="2313240">case,</span>
  <span m="2313500">is</span> <span m="2313640">there''s</span> <span m="2313800">going
  to</span> <span m="2313890">be--</span> <span m="2314290">what</span> <span m="2314620">you''ll</span>
  <span m="2314800">see</span> <span m="2315050">is,</span> <span m="2315160">when</span>
  <span m="2315640">we</span> <span m="2315750">actually</span> <span m="2315980">get</span>
  <span m="2316240">to</span> <span m="2316590">talking</span> <span m="2316680">about</span>
  <span m="2316870">the</span> <span m="2317160">finite element</span> <span m="2317240">method,</span>
  <span m="2317400">that</span> <span m="2317550">there''s</span> <span m="2317680">a</span>
  <span m="2317720">bunch</span> <span m="2317920">of</span> <span m="2318000">integrals</span>
  <span m="2318430">we</span> <span m="2318530">have</span> <span m="2318690">to</span>
  <span m="2318780">do.</span> <span m="2319490">By</span> <span m="2319610">using</span>
  <span m="2319940">quadrature</span> <span m="2320580">you''re</span> <span m="2320820">going
  to</span> <span m="2321030">actually</span> <span m="2321420">end up</span> <span
  m="2321680">having</span> <span m="2321830">to</span> <span m="2322250">approximate</span>
  <span m="2322440">the</span> <span m="2322510">integrals,</span> <span m="2323020">but</span>
  <span m="2323180">be</span> <span m="2323340">doing</span> <span m="2323900">integrals</span>
  <span m="2324440">over</span> <span m="2324670">sort of</span> <span m="2325580">small</span>
  <span m="2325950">elements.</span> <span m="2326350">But</span> <span m="2326500">yes,</span>
  <span m="2326670">the</span> <span m="2326760">quadrature</span> <span m="2327150">is</span>
  <span m="2327260">going</span> <span m="2327380">to</span> <span m="2327440">introduce</span>
  <span m="2327760">a</span> <span m="2327820">little</span> <span m="2327990">bit</span>
  <span m="2328100">of</span> <span m="2328180">additional</span> <span m="2329240">error.</span>
  <span m="2330008">Yeah.</span> <span m="2331412">Yeah.</span></p><p><span m="2336570">OK.</span>
  <span m="2337070">So</span> <span m="2337530">we</span> <span m="2337680">have</span>
  <span m="2337880">the</span> <span m="2337960">expression</span> <span m="2338490">for</span>
  <span m="2338620">the</span> <span m="2338700">residual.</span> <span m="2339520">And</span>
  <span m="2339775">so</span> <span m="2340120">now</span> <span m="2340310">what</span>
  <span m="2340430">we''re</span> <span m="2340490">going</span> <span m="2340610">to</span>
  <span m="2340670">do</span> <span m="2340830">is</span> <span m="2341040">pick</span>
  <span m="2342400">n</span> <span m="2342690">equal</span> <span m="2342900">[? two
  ?]</span> <span m="2343190">collocation</span> <span m="2343890">points.</span>
  <span m="2345422">So</span> <span m="2345910">again,</span> <span m="2346410">just</span>
  <span m="2346610">to</span> <span m="2346710">remind</span> <span m="2347160">you,</span>
  <span m="2348740">collocation</span> <span m="2351920">method</span> <span m="2353210">says</span>
  <span m="2355460">enforce</span> <span m="2355970">the</span> <span m="2356070">PDE</span>
  <span m="2359592">at</span> <span m="2360560">n</span> <span m="2360760">equals</span>
  <span m="2361110">two</span> <span m="2361330">points.</span> <span m="2362070">And</span>
  <span m="2362440">enforcing</span> <span m="2362920">the</span> <span m="2363000">PDE,</span>
  <span m="2363550">what</span> <span m="2363680">does</span> <span m="2363790">that</span>
  <span m="2363970">mean?</span> <span m="2364450">Enforce</span> <span m="2364570">the</span>
  <span m="2364830">PDE</span> <span m="2365540">means</span> <span m="2366590">i.e.</span>
  <span m="2368010">set</span> <span m="2368290">the</span> <span m="2368620">residual</span>
  <span m="2372140">equal to</span> <span m="2372630">0</span> <span m="2374674">at</span>
  <span m="2375140">two--</span> <span m="2375430">and</span> <span m="2375830">by</span>
  <span m="2375950">points</span> <span m="2378180">we</span> <span m="2378630">mean</span>
  <span m="2379020">two</span> <span m="2379170">values</span> <span m="2379550">of</span>
  <span m="2379660">x--</span> <span m="2379960">two</span> <span m="2380390">points</span>
  <span m="2380740">in</span> <span m="2380830">the</span> <span m="2380980">domain.</span>
  <span m="2383060">And</span> <span m="2383530">here''s</span> <span m="2383880">our</span>
  <span m="2383990">domain.</span> <span m="2386180">There''s</span> <span m="2386520">x.</span>
  <span m="2388330">Remember,</span> <span m="2388740">we''re going</span> <span m="2389040">from--</span>
  <span m="2390480">we''ve</span> <span m="2390880">got</span> <span m="2391080">[INAUDIBLE]</span>
  <span m="2391220">so it</span> <span m="2391290">goes</span> <span m="2391470">from</span>
  <span m="2391620">minus</span> <span m="2391980">1</span> <span m="2392380">to</span>
  <span m="2392540">1.</span> <span m="2392860">So</span> <span m="2393180">there''s</span>
  <span m="2394600">0</span> <span m="2394720">in</span> <span m="2394810">the</span>
  <span m="2394880">middle.</span> <span m="2396400">And</span> <span m="2396730">the</span>
  <span m="2396790">collocation</span> <span m="2397380">points</span> <span m="2397740">we''re</span>
  <span m="2397970">going</span> <span m="2398090">to choose</span> <span m="2399880">there</span>
  <span m="2400490">and</span> <span m="2400980">there.</span> <span m="2402290">That''s</span>
  <span m="2402540">minus</span> <span m="2402910">one</span> <span m="2403120">third</span>
  <span m="2403720">and</span> <span m="2404200">plus</span> <span m="2404480">on
  third.</span> <span m="2406050">And those</span> <span m="2406360">are</span> <span
  m="2406630">the</span> <span m="2406720">collocation</span> <span m="2407270">points</span>
  <span m="2407570">that</span> <span m="2407790">spread</span> <span m="2408020">things</span>
  <span m="2408310">out</span> <span m="2408460">the</span> <span m="2408520">most,</span>
  <span m="2408910">kind of</span> <span m="2409090">away</span> <span m="2409380">from</span>
  <span m="2409610">putting up</span> <span m="2409950">the</span> <span m="2410020">boundary</span>
  <span m="2410310">conditions</span> <span m="2410750">here</span> <span m="2411060">at
  minus</span> <span m="2411340">1</span> <span m="2411520">and</span> <span m="2411610">1.</span></p><p><span
  m="2415580">So</span> <span m="2415690">[INAUDIBLE]</span> <span m="2416130">that</span>
  <span m="2416280">we</span> <span m="2416360">don''t</span> <span m="2416600">really</span>
  <span m="2416810">use</span> <span m="2416970">the</span> <span m="2417040">collocation</span>
  <span m="2417640">method.</span> <span m="2418400">It''s</span> <span m="2418520">not</span>
  <span m="2418690">a</span> <span m="2418730">good</span> <span m="2418880">idea.</span>
  <span m="2419410">One</span> <span m="2419590">of</span> <span m="2419650">the</span>
  <span m="2419730">reasons</span> <span m="2420050">we''re</span> <span m="2420140">doing</span>
  <span m="2420430">it</span> <span m="2420540">is</span> <span m="2420670">because</span>
  <span m="2420940">it''s</span> <span m="2421110">a</span> <span m="2421160">good</span>
  <span m="2421880">stepping</span> <span m="2422300">stone</span> <span m="2422570">to</span>
  <span m="2422650">see</span> <span m="2423110">how</span> <span m="2423350">the</span>
  <span m="2423530">weighted</span> <span m="2424230">residual</span> <span m="2424950">works.</span>
  <span m="2426100">But</span> <span m="2426940">that''s</span> <span m="2427170">a</span>
  <span m="2427230">good</span> <span m="2427370">question,</span> <span m="2427690">because</span>
  <span m="2428150">in</span> <span m="2428310">some</span> <span m="2428470">cases</span>
  <span m="2428700">people</span> <span m="2428940">do</span> <span m="2429040">use</span>
  <span m="2429360">collocation,</span> <span m="2429440">and</span> <span m="2429900">aerodynamics</span>
  <span m="2430520">is</span> <span m="2430620">a</span> <span m="2430690">good</span>
  <span m="2430890">example.</span> <span m="2432070">And</span> <span m="2432330">the</span>
  <span m="2432430">reason</span> <span m="2432860">you</span> <span m="2432940">use</span>
  <span m="2433240">the</span> <span m="2433380">3/4</span> <span m="2433790">quad</span>
  <span m="2434020">point</span> <span m="2434410">is</span> <span m="2434660">because</span>
  <span m="2435450">for</span> <span m="2435660">a</span> <span m="2435720">particular</span>
  <span m="2436230">kind</span> <span m="2436750">of</span> <span m="2436930">left</span>
  <span m="2437150">distribution,</span> <span m="2437930">that</span> <span m="2438450">integrates</span>
  <span m="2438930">you</span> <span m="2439060">exactly.</span> <span m="2440540">And</span>
  <span m="2440830">in</span> <span m="2440930">fact,</span> <span m="2441370">your</span>
  <span m="2441730">question</span> <span m="2442090">is</span> <span m="2442290">somewhat</span>
  <span m="2442710">related</span> <span m="2443060">to</span> <span m="2443150">the</span>
  <span m="2443220">question</span> <span m="2443530">about</span> <span m="2443870">numerical</span>
  <span m="2444300">integration.</span> <span m="2444930">When we</span> <span m="2445030">see</span>
  <span m="2445110">quadrature,</span> <span m="2446300">you''re going to see</span>
  <span m="2446670">it''s the</span> <span m="2446920">same--</span> <span m="2447890">it''s</span>
  <span m="2448180">going to be</span> <span m="2448250">different</span> <span m="2448560">settings,</span>
  <span m="2448960">I</span> <span m="2449000">don''t want</span> <span m="2449130">to</span>
  <span m="2449190">confuse</span> <span m="2449500">you</span> <span m="2449560">about</span>
  <span m="2449780">quadrature--</span> <span m="2450770">when</span> <span m="2450890">you</span>
  <span m="2451010">do</span> <span m="2451110">numerical</span> <span m="2451670">integration,</span>
  <span m="2453240">we''re going</span> <span m="2453360">to</span> <span m="2453430">put</span>
  <span m="2453760">points</span> <span m="2454840">in</span> <span m="2454960">the</span>
  <span m="2455490">integration</span> <span m="2456110">domain.</span> <span m="2457000">And</span>
  <span m="2457150">those</span> <span m="2457350">points</span> <span m="2457740">are</span>
  <span m="2457790">chosen</span> <span m="2458760">in</span> <span m="2458860">a</span>
  <span m="2458920">particular</span> <span m="2459400">way</span> <span m="2459660">so</span>
  <span m="2459820">that</span> <span m="2459940">we</span> <span m="2460110">can</span>
  <span m="2460370">integrate</span> <span m="2460890">certain</span> <span m="2461200">functions</span>
  <span m="2461634">exactly.</span></p><p><span m="2463370">So</span> <span m="2463840">it''s--</span>
  <span m="2464510">here</span> <span m="2464970">they''ve</span> <span m="2465120">chosen</span>
  <span m="2465360">to</span> <span m="2465440">be</span> <span m="2465540">spaced</span>
  <span m="2465960">out--</span> <span m="2466260">there''s</span> <span m="2466400">actually</span>
  <span m="2466660">all</span> <span m="2466760">these</span> <span m="2466950">rules,</span>
  <span m="2467210">they''re</span> <span m="2467450">called</span> <span m="2468460">quadrature</span>
  <span m="2469000">rules,</span> <span m="2469370">and</span> <span m="2469440">they''re</span>
  <span m="2469580">all</span> <span m="2469720">these</span> <span m="2469940">different</span>
  <span m="2470880">kinds</span> <span m="2471280">of</span> <span m="2471490">points,</span>
  <span m="2472550">and</span> <span m="2472710">they</span> <span m="2472970">actually</span>
  <span m="2473270">tend</span> <span m="2473430">to</span> <span m="2473500">be</span>
  <span m="2473610">named</span> <span m="2473900">after</span> <span m="2474100">mathematicians</span>
  <span m="2474810">who</span> <span m="2474900">discovered</span> <span m="2475370">them--</span>
  <span m="2475580">different</span> <span m="2475900">patterns</span> <span m="2476850">of</span>
  <span m="2477070">points</span> <span m="2477790">where</span> <span m="2478565">it
  says,</span> <span m="2478980">space</span> <span m="2479400">things</span> <span
  m="2479640">evenly,</span> <span m="2480090">or</span> <span m="2481810">distribute</span>
  <span m="2482200">them</span> <span m="2482360">out.</span> <span m="2483640">That''s</span>
  <span m="2483780">actually</span> <span m="2483990">a</span> <span m="2484060">pretty</span>
  <span m="2484240">interesting</span> <span m="2484740">area</span> <span m="2485165">of</span>
  <span m="2485590">study.</span> <span m="2485950">In</span> <span m="2486050">fact,</span>
  <span m="2486130">Alex</span> <span m="2486560">I</span> <span m="2486630">would</span>
  <span m="2486980">say</span> <span m="2487150">knows</span> <span m="2487350">a</span>
  <span m="2487400">lot</span> <span m="2487550">more</span> <span m="2487690">about</span>
  <span m="2487960">these</span> <span m="2488160">things</span> <span m="2488380">than</span>
  <span m="2488480">I</span> <span m="2488930">do.</span> <span m="2489380">Is that
  true, Alex?</span> <span m="2491330">What''s</span> <span m="2491500">your</span>
  <span m="2491620">favorite</span> <span m="2493420">set</span> <span m="2493540">of</span>
  <span m="2493620">points?</span></p><p><span m="2494440">AUDIENCE: [INAUDIBLE].</span></p><p><span
  m="2496080">PROFESSOR: [INAUDIBLE]?</span></p><p><span m="2497076">So</span> <span
  m="2497430">depending</span> <span m="2497890">on</span> <span m="2497970">the</span>
  <span m="2498030">function</span> <span m="2498320">you''re</span> <span m="2498420">trying</span>
  <span m="2498560">to</span> <span m="2498630">integrate,</span> <span m="2499060">there</span>
  <span m="2499230">are sort of</span> <span m="2499490">optimal</span> <span m="2499860">choices</span>
  <span m="2500100">of</span> <span m="2500170">where</span> <span m="2500270">you</span>
  <span m="2500430">might</span> <span m="2500650">put</span> <span m="2500770">the</span>
  <span m="2500810">point.</span></p><p><span m="2503088">AUDIENCE: [INAUDIBLE].</span></p><p><span
  m="2506990">PROFESSOR: Yeah,</span> <span m="2507230">something</span> <span m="2507470">about</span>
  <span m="2507670">the</span> <span m="2507750">solution</span> <span m="2508290">or</span>
  <span m="2508580">something</span> <span m="2508990">about</span> <span m="2509260">the</span>
  <span m="2509340">basis</span> <span m="2509800">function</span> <span m="2510420">that</span>
  <span m="2510580">you''re</span> <span m="2510700">using</span> <span m="2512190">to</span>
  <span m="2512420">represent</span> <span m="2512910">the</span> <span m="2512980">solution.</span></p><p><span
  m="2516480">AUDIENCE: [INAUDIBLE].</span></p><p><span m="2526190">PROFESSOR: Yeah.</span>
  <span m="2526530">So</span> <span m="2526610">that''s</span> <span m="2527050">a</span>
  <span m="2527110">really</span> <span m="2527330">good--</span></p><p><span m="2527560">AUDIENCE:
  [INAUDIBLE].</span></p><p><span m="2528720">PROFESSOR: --that''s</span> <span m="2528900">a</span>
  <span m="2528950">really</span> <span m="2529110">good</span> <span m="2529230">question.</span></p><p><span
  m="2529520">So</span> <span m="2529680">if</span> <span m="2530050">you''re</span>
  <span m="2530160">trying</span> <span m="2530290">to</span> <span m="2530360">approximate</span>
  <span m="2530950">things,</span> <span m="2531160">but you know</span> <span m="2531260">there''s</span>
  <span m="2531670">something</span> <span m="2532000">in</span> <span m="2532090">the</span>
  <span m="2532160">middle</span> <span m="2532410">that</span> <span m="2532540">you</span>
  <span m="2532640">would</span> <span m="2532810">really</span> <span m="2533080">care</span>
  <span m="2533350">about--</span> <span m="2534170">so</span> <span m="2534280">now</span>
  <span m="2534460">what</span> <span m="2534580">you''re</span> <span m="2534670">talking</span>
  <span m="2534950">about</span> <span m="2535190">is</span> <span m="2535290">an</span>
  <span m="2535370">adaptive</span> <span m="2535860">strategy.</span> <span m="2537180">And</span>
  <span m="2537240">again,</span> <span m="2537570">this</span> <span m="2537720">is</span>
  <span m="2537900">a</span> <span m="2537960">very</span> <span m="2538900">current</span>
  <span m="2539180">area</span> <span m="2539450">of</span> <span m="2539510">research.</span>
  <span m="2539910">In</span> <span m="2540030">fact,</span> <span m="2540330">a</span>
  <span m="2540390">lot</span> <span m="2540540">of</span> <span m="2540700">[? professor
  ?]</span> <span m="2541552">[INAUDIBLE]</span> <span m="2541980">research</span>
  <span m="2542280">[? facilities ?]</span> <span m="2542690">I</span> <span m="2542770">think</span>
  <span m="2542950">mention</span> <span m="2543290">there</span> <span m="2543420">at
  the</span> <span m="2543490">beginning</span> <span m="2543880">that</span> <span
  m="2544020">uses</span> <span m="2544300">adjoint</span> <span m="2544766">methods.</span>
  <span m="2546630">So that</span> <span m="2546910">would</span> <span m="2547060">be</span>
  <span m="2547930">bringing</span> <span m="2548290">in</span> <span m="2548410">information</span>
  <span m="2549000">that</span> <span m="2549130">tells</span> <span m="2549540">you</span>
  <span m="2549710">where</span> <span m="2550190">the</span> <span m="2550300">regions</span>
  <span m="2550640">in</span> <span m="2550720">the</span> <span m="2550810">domain</span>
  <span m="2551320">that</span> <span m="2551460">are</span> <span m="2551500">most</span>
  <span m="2551840">sensitive</span> <span m="2552380">to</span> <span m="2552510">what</span>
  <span m="2552660">it</span> <span m="2552760">is</span> <span m="2553180">you care
  about,</span> <span m="2554020">where might</span> <span m="2554240">you</span>
  <span m="2554600">put</span> <span m="2554960">more</span> <span m="2555210">points.</span>
  <span m="2557010">People</span> <span m="2557220">who</span> <span m="2557350">choose</span>
  <span m="2557740">points</span> <span m="2558410">to</span> <span m="2558560">do</span>
  <span m="2558730">this</span> <span m="2559535">quadrature,</span> <span m="2559960">or</span>
  <span m="2560350">this numerical integration,</span> <span m="2561540">sometimes</span>
  <span m="2562474">will</span> <span m="2562908">choose</span> <span m="2563342">to</span>
  <span m="2563776">adapt in these ways.</span> <span m="2564210">And</span> <span
  m="2565180">what</span> <span m="2565330">you</span> <span m="2565430">would</span>
  <span m="2565570">like</span> <span m="2565860">is,</span> <span m="2566050">you</span>
  <span m="2566120">would</span> <span m="2566240">like</span> <span m="2566440">kind</span>
  <span m="2566590">of</span> <span m="2566660">general</span> <span m="2567040">rules</span>
  <span m="2567380">that</span> <span m="2567600">work</span> <span m="2567980">well,</span>
  <span m="2568390">but</span> <span m="2568560">then</span> <span m="2568740">you</span>
  <span m="2568820">would</span> <span m="2568930">like</span> <span m="2569230">to
  be able</span> <span m="2569350">to</span> <span m="2569450">adapt</span> <span
  m="2570770">depending</span> <span m="2571110">on</span> <span m="2571220">your</span>
  <span m="2572090">particular</span> <span m="2572490">problem</span> <span m="2572740">of</span>
  <span m="2572840">interest.</span> <span m="2573830">And</span> <span m="2574170">there</span>
  <span m="2574270">are</span> <span m="2574300">definitely</span> <span m="2574600">a</span>
  <span m="2574640">lot</span> <span m="2574770">of</span> <span m="2574840">adaptive</span>
  <span m="2575190">strategies</span> <span m="2575620">out</span> <span m="2575820">there,</span>
  <span m="2575970">but</span> <span m="2576110">it''s</span> <span m="2576260">also</span>
  <span m="2576895">an area</span> <span m="2577300">that a</span> <span m="2577360">lot</span>
  <span m="2577480">of</span> <span m="2577570">people</span> <span m="2577850">are
  working on.</span></p><p><span m="2580360">Good</span> <span m="2580430">question.</span></p><p><span
  m="2583460">So</span> <span m="2583600">you</span> <span m="2583670">guys</span>
  <span m="2583910">are</span> <span m="2583960">all</span> <span m="2584150">ready</span>
  <span m="2584360">for</span> <span m="2584490">the</span> <span m="2584570">lecture</span>
  <span m="2585596">on</span> <span m="2586020">quadrature.</span> <span m="2586320">In
  fact,</span> <span m="2586780">when</span> <span m="2586870">we</span> <span m="2586960">come</span>
  <span m="2587160">to</span> <span m="2587250">talk</span> <span m="2587410">about</span>
  <span m="2587590">Monte</span> <span m="2587790">Carlo</span> <span m="2588200">integration--</span>
  <span m="2589390">Monte</span> <span m="2589590">Carlo</span> <span m="2589920">methods--</span>
  <span m="2590570">I</span> <span m="2590630">mean,</span> <span m="2591100">evaluating</span>
  <span m="2591590">means</span> <span m="2591990">and</span> <span m="2592100">variances.</span>
  <span m="2592600">That''s</span> <span m="2592690">just</span> <span m="2592930">integration</span>
  <span m="2593450">as</span> <span m="2593570">well.</span> <span m="2593870">That''s</span>
  <span m="2594080">all just</span> <span m="2594380">about</span> <span m="2594690">putting</span>
  <span m="2595130">points</span> <span m="2595440">in</span> <span m="2595510">a</span>
  <span m="2595570">domain.</span> <span m="2596690">And</span> <span m="2596790">what</span>
  <span m="2596900">you''re</span> <span m="2596960">going</span> <span m="2597080">to</span>
  <span m="2597140">see</span> <span m="2597290">is</span> <span m="2597380">Monte
  Carlo</span> <span m="2597870">does it</span> <span m="2598120">randomly,</span>
  <span m="2598500">but</span> <span m="2599190">in</span> <span m="2599490">some</span>
  <span m="2599660">cases</span> <span m="2600070">you</span> <span m="2600170">can</span>
  <span m="2600420">do</span> <span m="2600800">better</span> <span m="2601120">by</span>
  <span m="2601910">putting</span> <span m="2602210">them</span> <span m="2602370">in</span>
  <span m="2602450">a</span> <span m="2602490">very</span> <span m="2602740">spec--</span>
  <span m="2603210">putting the points</span> <span m="2603540">in</span> <span m="2603600">a</span>
  <span m="2603640">very</span> <span m="2603800">specific</span> <span m="2604260">way.</span></p><p><span
  m="2608350">OK.</span> <span m="2609010">But here</span> <span m="2609370">we''re
  going to do</span> <span m="2609690">just</span> <span m="2609890">[INAUDIBLE]</span>
  <span m="2610060">we''re</span> <span m="2610310">in</span> <span m="2610410">1D,</span>
  <span m="2610660">so,</span> <span m="2611260">in</span> <span m="2611400">1D</span>
  <span m="2611720">you</span> <span m="2611830">can</span> <span m="2611970">usually</span>
  <span m="2612230">get</span> <span m="2612370">away</span> <span m="2612650">with</span>
  <span m="2613646">pretty much</span> <span m="2614000">anything.</span></p><p><span
  m="2614880">We''re</span> <span m="2615000">going</span> <span m="2615140">to</span>
  <span m="2616680">just</span> <span m="2616940">put</span> <span m="2617130">them</span>
  <span m="2617270">at</span> <span m="2617360">minus</span> <span m="2617680">a</span>
  <span m="2617730">third</span> <span m="2618610">and</span> <span m="2619300">a</span>
  <span m="2619550">third.</span> <span m="2619740">So what that</span> <span m="2620100">is,</span>
  <span m="2620360">again,</span> <span m="2620660">[? sit ?]</span> <span m="2621060">the
  residual.</span> <span m="2622670">And</span> <span m="2623950">I''m</span> <span
  m="2625190">purposely</span> <span m="2625590">writing</span> <span m="2625980">out</span>
  <span m="2626110">all</span> <span m="2626390">the</span> <span m="2626480">functional</span>
  <span m="2627110">dependencies.</span> <span m="2628340">I</span> <span m="2628530">keep</span>
  <span m="2628810">writing</span> <span m="2629670">r of</span> <span m="2630100">t</span>
  <span m="2630370">tilde</span> <span m="2630800">comma</span> <span m="2631230">x</span>
  <span m="2631940">because</span> <span m="2632110">it</span> <span m="2632210">helps</span>
  <span m="2632460">me</span> <span m="2632690">remember</span> <span m="2633200">that</span>
  <span m="2633360">residual</span> <span m="2633750">is</span> <span m="2633820">a</span>
  <span m="2633880">function</span> <span m="2634220">of</span> <span m="2634320">x.</span>
  <span m="2635286">And so</span> <span m="2635770">what</span> <span m="2635930">I''m</span>
  <span m="2636070">doing</span> <span m="2636300">here</span> <span m="2636620">is</span>
  <span m="2636780">I''m</span> <span m="2636950">evaluating</span> <span m="2637650">the</span>
  <span m="2637730">residual</span> <span m="2638300">at</span> <span m="2639150">the</span>
  <span m="2639260">point</span> <span m="2639560">x</span> <span m="2639850">equal</span>
  <span m="2640140">to</span> <span m="2640410">minus</span> <span m="2640600">one</span>
  <span m="2640720">third,</span> <span m="2641210">that''s</span> <span m="2641400">a</span>
  <span m="2641650">point on my</span> <span m="2641930">domain.</span> <span m="2643400">So</span>
  <span m="2643560">that</span> <span m="2643750">means</span> <span m="2644310">substitute</span>
  <span m="2644930">x</span> <span m="2645130">equal</span> <span m="2645360">minus</span>
  <span m="2645740">one</span> <span m="2645990">third</span> <span m="2646380">into</span>
  <span m="2646640">my</span> <span m="2646790">expression</span> <span m="2648150">for</span>
  <span m="2648310">the</span> <span m="2648400">residual,</span> <span m="2649110">which</span>
  <span m="2649270">gives</span> <span m="2649842">this</span> <span m="2651020">50e</span>
  <span m="2651210">to the</span> <span m="2652710">minus</span> <span m="2653060">one
  third,</span> <span m="2654300">and</span> <span m="2654745">put</span> <span m="2655190">that</span>
  <span m="2655270">equal</span> <span m="2655590">to</span> <span m="2656010">0.</span></p><p><span
  m="2657270">Right?</span> <span m="2657690">So there''s</span> <span m="2658000">the</span>
  <span m="2658080">first</span> <span m="2658350">condition.</span> <span m="2659500">And</span>
  <span m="2659740">then</span> <span m="2660320">the</span> <span m="2660400">second</span>
  <span m="2660820">condition</span> <span m="2662150">is</span> <span m="2662410">original</span>
  <span m="2663110">evaluated</span> <span m="2663750">plus</span> <span m="2664130">one
  third.</span> <span m="2664850">Again,</span> <span m="2665330">substitute</span>
  <span m="2665870">that</span> <span m="2666100">in</span> <span m="2667140">to</span>
  <span m="2667870">the</span> <span m="2667970">expression.</span> <span m="2669700">So</span>
  <span m="2669900">we''re just</span> <span m="2670080">changing</span> <span m="2670430">the</span>
  <span m="2670510">sign</span> <span m="2670920">here.</span> <span m="2671200">And</span>
  <span m="2671400">then this</span> <span m="2671560">is</span> <span m="2671660">going</span>
  <span m="2671790">to</span> <span m="2671870">be</span> <span m="2672500">50e</span>
  <span m="2673370">to</span> <span m="2673450">the</span> <span m="2673540">plus</span>
  <span m="2673875">one third.</span> <span m="2675670">And</span> <span m="2675820">that''s</span>
  <span m="2676010">been</span> <span m="2676150">set</span> <span m="2676380">equal</span>
  <span m="2676840">to 0.</span></p><p><span m="2680060">So</span> <span m="2681280">now</span>
  <span m="2681480">you</span> <span m="2681630">can</span> <span m="2681810">see</span>
  <span m="2682060">we</span> <span m="2682410">reduced--</span> <span m="2682960">we</span>
  <span m="2683050">keep</span> <span m="2683310">sort</span> <span m="2683530">of</span>
  <span m="2683700">reducing</span> <span m="2684130">the</span> <span m="2684210">problem.</span>
  <span m="2684700">The</span> <span m="2684800">first</span> <span m="2685020">thing</span>
  <span m="2685140">we</span> <span m="2685240">did</span> <span m="2685470">was</span>
  <span m="2686200">assume</span> <span m="2686600">the</span> <span m="2687830">functions--</span>
  <span m="2689400">these</span> <span m="2689630">guys--</span> <span m="2690380">that
  we</span> <span m="2690550">want</span> <span m="2690750">to</span> <span m="2690810">approximate</span>
  <span m="2691290">the</span> <span m="2691360">solution</span> <span m="2691820">in.</span>
  <span m="2692760">Then</span> <span m="2692920">we</span> <span m="2693010">take--</span>
  <span m="2693200">we''ve got</span> <span m="2694250">two</span> <span m="2694960">degrees</span>
  <span m="2695310">of</span> <span m="2695400">freedom</span> <span m="2695790">to</span>
  <span m="2695970">unknown,</span> <span m="2696560">so</span> <span m="2696740">let''s</span>
  <span m="2696940">use</span> <span m="2697050">a</span> <span m="2697130">collocation</span>
  <span m="2697780">method.</span> <span m="2698140">We</span> <span m="2698500">set
  the</span> <span m="2698580">residual</span> <span m="2699110">to</span> <span m="2699220">be</span>
  <span m="2699370">0</span> <span m="2699620">at</span> <span m="2700460">two</span>
  <span m="2700630">points.</span> <span m="2701180">We</span> <span m="2701310">chose</span>
  <span m="2701690">these</span> <span m="2701940">two</span> <span m="2702090">points.</span>
  <span m="2703120">We''ve</span> <span m="2703410">enforced</span> <span m="2703670">these</span>
  <span m="2703860">conditions.</span> <span m="2704205">Now</span> <span m="2704550">we</span>
  <span m="2704820">have</span> <span m="2705050">two</span> <span m="2705220">equations,</span>
  <span m="2705880">two</span> <span m="2705930">unknowns.</span> <span m="2707280">We</span>
  <span m="2707400">could</span> <span m="2707600">solve</span> <span m="2707900">that--</span>
  <span m="2708140">you could</span> <span m="2708360">probably</span> <span m="2708650">solve</span>
  <span m="2708860">that</span> <span m="2710140">analytically,</span> <span m="2711560">or</span>
  <span m="2711810">using</span> <span m="2712400">mathematical,</span> <span m="2712920">or</span>
  <span m="2713020">whatever</span> <span m="2713290">you</span> <span m="2713430">like.</span>
  <span m="2713970">And</span> <span m="2714170">what</span> <span m="2714310">you</span>
  <span m="2714410">find</span> <span m="2714760">is</span> <span m="2714870">that</span>
  <span m="2715050">a1</span> <span m="2715190">and</span> <span m="2715530">a2--</span>
  <span m="2717010">26.4</span> <span m="2718310">and</span> <span m="2718600">8.5.</span></p><p><span
  m="2721320">So</span> <span m="2721400">those</span> <span m="2721560">numbers</span>
  <span m="2722020">don''t</span> <span m="2723100">mean</span> <span m="2723420">a</span>
  <span m="2723490">whole</span> <span m="2723690">lot</span> <span m="2723910">to</span>
  <span m="2724150">us, but</span> <span m="2725660">again,</span> <span m="2726000">what''s</span>
  <span m="2726320">the</span> <span m="2727000">key?</span> <span m="2727290">The
  key is</span> <span m="2727440">that</span> <span m="2727670">this</span> <span
  m="2727910">is</span> <span m="2728080">our</span> <span m="2729530">approximation</span>
  <span m="2730200">of</span> <span m="2730300">the</span> <span m="2730380">solution.</span>
  <span m="2731330">So</span> <span m="2731360">we''re</span> <span m="2731520">saying</span>
  <span m="2731980">that</span> <span m="2733560">by</span> <span m="2733950">the</span>
  <span m="2734020">collocation</span> <span m="2734620">method,</span> <span m="2734920">the
  approximate</span> <span m="2735570">solution</span> <span m="2736110">of</span>
  <span m="2736270">t tilde</span> <span m="2736740">is</span> <span m="2736920">100</span>
  <span m="2737670">plus</span> <span m="2739510">26.4</span> <span m="2740620">times</span>
  <span m="2741370">something</span> <span m="2741470">that</span> <span m="2741760">looks</span>
  <span m="2741980">like</span> <span m="2742190">that--</span> <span m="2742560">a</span>
  <span m="2742670">quadtratic--</span> <span m="2744170">minus</span> <span m="2746056">plus</span>
  <span m="2746470">8.5</span> <span m="2747120">times</span> <span m="2747540">something</span>
  <span m="2747610">that</span> <span m="2747870">looks</span> <span m="2748040">like
  that</span> <span m="2748170">[? cubed. ?]</span> <span m="2749660">And</span> <span
  m="2749790">when</span> <span m="2749900">you</span> <span m="2749990">add</span>
  <span m="2750120">those</span> <span m="2750350">together</span> <span m="2751085">you
  get</span> <span m="2751430">something</span> <span m="2752060">that</span> <span
  m="2754870">is</span> <span m="2755480">at</span> <span m="2755560">least</span>
  <span m="2755840">an</span> <span m="2755920">approximate</span> <span m="2756470">solution</span>
  <span m="2757080">to</span> <span m="2757250">the</span> <span m="2757695">PDE.</span></p><p><span
  m="2759920">So</span> <span m="2760060">I</span> <span m="2760090">want</span> <span
  m="2760220">to</span> <span m="2760300">take</span> <span m="2760500">a</span> <span
  m="2760550">look</span> <span m="2760730">at</span> <span m="2760790">what</span>
  <span m="2760910">that</span> <span m="2761150">solution</span> <span m="2761990">looks</span>
  <span m="2762240">like.</span> <span m="2763122">While I</span> <span m="2763490">put
  the</span> <span m="2763590">projector</span> <span m="2763980">on,</span> <span
  m="2766170">are</span> <span m="2766310">there</span> <span m="2766400">questions</span>
  <span m="2766870">about</span> <span m="2767130">the</span> <span m="2767190">collocation</span>
  <span m="2767730">method?</span> <span m="2769980">If</span> <span m="2770130">we</span>
  <span m="2770230">were</span> <span m="2770370">actually</span> <span m="2770650">using</span>
  <span m="2770850">collocation</span> <span m="2771410">method,</span> <span m="2771820">we</span>
  <span m="2771830">would</span> <span m="2772000">use</span> <span m="2772150">more</span>
  <span m="2772330">than</span> <span m="2772500">two</span> <span m="2774210">points</span>
  <span m="2774640">typically.</span> <span m="2777750">My</span> <span m="2777880">simple</span>
  <span m="2778220">example.</span></p><p><span m="2786265">So--</span> <span m="2787756">so
  I have a code</span> <span m="2788750">here</span> <span m="2789140">that</span>
  <span m="2789360">actually</span> <span m="2789700">implements--</span> <span m="2793310">I</span>
  <span m="2793440">guess I should</span> <span m="2793929">plug my laptop</span>
  <span m="2794418">in.</span></p><p><span m="2810580">OK.</span> <span m="2810810">So</span>
  <span m="2810930">the</span> <span m="2811070">code</span> <span m="2811560">here
  that''s</span> <span m="2811770">going</span> <span m="2811900">to</span> <span
  m="2811970">implement it,</span> <span m="2813470">there</span> <span m="2813530">are</span>
  <span m="2813590">the</span> <span m="2813670">two</span> <span m="2813850">basis</span>
  <span m="2814170">functions,</span> <span m="2815100">c1</span> <span m="2815230">is</span>
  <span m="2815710">1</span> <span m="2816100">minus</span> <span m="2816355">x,</span>
  <span m="2816610">1</span> <span m="2816820">plus x.</span> <span m="2817560">c2</span>
  <span m="2817740">is</span> <span m="2818020">x</span> <span m="2818610">times</span>
  <span m="2819020">that--</span> <span m="2821190">the</span> <span m="2821290">cubic.</span>
  <span m="2822540">And</span> <span m="2825860">the</span> <span m="2825960">collocation</span>
  <span m="2826540">method</span> <span m="2826830">just</span> <span m="2827120">gets</span>
  <span m="2827360">implemented</span> <span m="2827920">here.</span> <span m="2828770">It''s</span>
  <span m="2829010">kind</span> <span m="2829180">of</span> <span m="2829580">hardwired</span>
  <span m="2830240">because</span> <span m="2830500">all the</span> <span m="2830660">derivations</span>
  <span m="2832480">have</span> <span m="2832590">been</span> <span m="2832790">done--</span>
  <span m="2835450">sort of</span> <span m="2835690">done</span> <span m="2835940">offline.</span></p><p><span
  m="2836480">But</span> <span m="2836590">let''s</span> <span m="2836760">just</span>
  <span m="2836960">run</span> <span m="2837460">this.</span> <span m="2840960">Won''t</span>
  <span m="2841460">run</span> <span m="2841960">that</span> <span m="2842368">yet.</span></p><p><span
  m="2844000">OK.</span> <span m="2844540">So</span> <span m="2844680">one</span>
  <span m="2844800">of</span> <span m="2844860">the</span> <span m="2844960">parts</span>
  <span m="2845340">that</span> <span m="2845500">we''re</span> <span m="2845690">looking</span>
  <span m="2846060">at</span> <span m="2846230">here--</span> <span m="2846880">so</span>
  <span m="2847350">here first,</span> <span m="2848040">of</span> <span m="2848130">all,</span>
  <span m="2848580">is</span> <span m="2849770">a</span> <span m="2849890">plot</span>
  <span m="2850940">of</span> <span m="2853080">the</span> <span m="2853170">temperature</span>
  <span m="2854150">versus</span> <span m="2854460">x.</span> <span m="2855742">And</span>
  <span m="2856310">the</span> <span m="2856410">solid</span> <span m="2856790">blue</span>
  <span m="2857020">is</span> <span m="2857160">the</span> <span m="2857270">exact</span>
  <span m="2857740">line,</span> <span m="2858040">that''s</span> <span m="2858290">the</span>
  <span m="2858390">one</span> <span m="2858590">that</span> <span m="2858710">we</span>
  <span m="2858830">computed</span> <span m="2859190">analytically</span> <span m="2859655">for</span>
  <span m="2860120">this</span> <span m="2860300">problem,</span> <span m="2860690">we</span>
  <span m="2860780">can</span> <span m="2860930">do</span> <span m="2861060">that.</span>
  <span m="2861800">And</span> <span m="2862200">a</span> <span m="2862230">dashed</span>
  <span m="2862510">line</span> <span m="2862670">is</span> <span m="2862770">what</span>
  <span m="2862880">we</span> <span m="2862960">got</span> <span m="2863100">with</span>
  <span m="2863230">collocation.</span></p><p><span m="2864560">OK,</span> <span m="2864860">so</span>
  <span m="2865030">it</span> <span m="2865110">actually</span> <span m="2865310">doesn''t</span>
  <span m="2865520">do</span> <span m="2865640">too</span> <span m="2865780">badly,</span>
  <span m="2866150">right?</span> <span m="2866420">We</span> <span m="2866960">sort</span>
  <span m="2867130">of</span> <span m="2867200">assumed</span> <span m="2867760">this</span>
  <span m="2868010">[INAUDIBLE]</span> <span m="2868220">of</span> <span m="2868280">the</span>
  <span m="2868360">solution</span> <span m="2868990">with</span> <span m="2869490">the</span>
  <span m="2869590">solution</span> <span m="2869940">being</span> <span m="2870090">100</span>
  <span m="2870590">plus</span> <span m="2871070">a</span> <span m="2871430">quadratic</span>
  <span m="2871840">plus a cubic.</span> <span m="2873040">We</span> <span m="2873170">figured</span>
  <span m="2873470">out</span> <span m="2873840">just with</span> <span m="2874040">two</span>
  <span m="2874260">degrees</span> <span m="2874570">of</span> <span m="2874640">freedom</span>
  <span m="2874970">what</span> <span m="2875140">good</span> <span m="2875340">choices</span>
  <span m="2875720">for</span> <span m="2875930">a1</span> <span m="2876110">and</span>
  <span m="2876360">a2</span> <span m="2876460">would</span> <span m="2876580">be.</span>
  <span m="2876680">It''s</span> <span m="2876920">actually</span> <span m="2877240">not</span>
  <span m="2877460">too</span> <span m="2877580">bad.</span> <span m="2878444">Right?</span></p><p><span
  m="2880610">So</span> <span m="2880650">there''s</span> <span m="2880820">a</span>
  <span m="2880890">plot</span> <span m="2881300">of</span> <span m="2882340">the</span>
  <span m="2884000">actual</span> <span m="2884490">compared</span> <span m="2885020">to</span>
  <span m="2887680">the</span> <span m="2887780">collocation''s</span> <span m="2888370">approximate</span>
  <span m="2888880">solution.</span></p><p><span m="2890280">Here''s</span> <span
  m="2890510">a</span> <span m="2890570">plot</span> <span m="2891050">of</span> <span
  m="2891660">the</span> <span m="2891860">error.</span> <span m="2892323">So that''s</span>
  <span m="2893250">t minus</span> <span m="2893730">t</span> <span m="2893880">tilde.</span>
  <span m="2894400">We</span> <span m="2894510">can</span> <span m="2894680">compute</span>
  <span m="2894980">again</span> <span m="2895190">in</span> <span m="2895270">this</span>
  <span m="2895360">case</span> <span m="2895660">because</span> <span m="2895860">we</span>
  <span m="2895980">happen</span> <span m="2896230">to</span> <span m="2896350">have</span>
  <span m="2896730">the</span> <span m="2896830">exact</span> <span m="2897180">solution.</span>
  <span m="2898320">You</span> <span m="2898430">can</span> <span m="2898590">see</span>
  <span m="2898810">that</span> <span m="2899492">error</span> <span m="2899974">is</span>
  <span m="2900456">0</span> <span m="2904020">on</span> <span m="2904460">either</span>
  <span m="2904790">end.</span> <span m="2905210">And</span> <span m="2906320">you</span>
  <span m="2906450">could</span> <span m="2906580">see</span> <span m="2906790">from</span>
  <span m="2906920">the</span> <span m="2907010">previous</span> <span m="2907440">part</span>
  <span m="2907820">that</span> <span m="2908010">the</span> <span m="2908770">exact</span>
  <span m="2908960">solution--</span> <span m="2909230">the</span> <span m="2909690">approximate</span>
  <span m="2910150">solution</span> <span m="2910460">was</span> <span m="2910600">always</span>
  <span m="2910830">under-predicting</span> <span m="2911490">in</span> <span m="2911620">temperature</span>
  <span m="2912720">[INAUDIBLE]</span> <span m="2912810">to be</span> <span m="2912890">exact.</span>
  <span m="2913420">So you</span> <span m="2913770">see</span> <span m="2913940">that</span>
  <span m="2914060">with</span> <span m="2914160">the</span> <span m="2914650">error</span>
  <span m="2914890">being</span> <span m="2915050">negative.</span> <span m="2916510">OK?</span></p><p><span
  m="2917910">Now</span> <span m="2918110">for</span> <span m="2918360">this</span>
  <span m="2918390">problem</span> <span m="2918660">we</span> <span m="2918740">can</span>
  <span m="2918910">look</span> <span m="2919090">at</span> <span m="2919180">these</span>
  <span m="2919440">because</span> <span m="2919690">we</span> <span m="2919790">do</span>
  <span m="2919980">actually</span> <span m="2920230">know</span> <span m="2920390">what</span>
  <span m="2920520">the</span> <span m="2920610">exact</span> <span m="2920950">solution</span>
  <span m="2921380">is.</span> <span m="2921570">We''re</span> <span m="2921760">not
  going</span> <span m="2921880">to</span> <span m="2921940">be</span> <span m="2922020">able
  to do that</span> <span m="2922530">in</span> <span m="2922630">general.</span>
  <span m="2923200">But</span> <span m="2923390">what</span> <span m="2923580">we</span>
  <span m="2923700">could</span> <span m="2924040">plot</span> <span m="2924730">is</span>
  <span m="2926050">the</span> <span m="2926200">residual.</span> <span m="2927240">So</span>
  <span m="2927440">again,</span> <span m="2928070">what</span> <span m="2928220">is</span>
  <span m="2928380">this?</span> <span m="2928800">This is</span> <span m="2929250">r</span>
  <span m="2929530">of</span> <span m="2930030">t tilde</span> <span m="2931080">comma</span>
  <span m="2931340">x.</span> <span m="2931790">And now</span> <span m="2931850">we''re</span>
  <span m="2932240">taking</span> <span m="2932560">the</span> <span m="2932640">t
  tilde</span> <span m="2933940">that</span> <span m="2934300">we</span> <span m="2934970">determined.</span>
  <span m="2935660">We</span> <span m="2935760">specified</span> <span m="2936310">the</span>
  <span m="2936370">form</span> <span m="2936640">of</span> <span m="2936730">it.</span>
  <span m="2936960">We</span> <span m="2937060">chose</span> <span m="2937380">a1</span>
  <span m="2937660">and</span> <span m="2937780">a2.</span> <span m="2939120">And</span>
  <span m="2939180">remember,</span> <span m="2939520">it''s</span> <span m="2939550">a</span>
  <span m="2939600">function</span> <span m="2939930">of</span> <span m="2940050">x.</span>
  <span m="2940390">So</span> <span m="2940490">here''s</span> <span m="2940640">the</span>
  <span m="2940740">residual</span> <span m="2941530">plotted out as</span> <span
  m="2941770">a</span> <span m="2941870">function</span> <span m="2942110">of</span>
  <span m="2942410">x.</span> <span m="2942710">And now</span> <span m="2942910">you</span>
  <span m="2943050">should</span> <span m="2943190">be</span> <span m="2943270">able
  to see,</span> <span m="2943600">this</span> <span m="2943710">is</span> <span m="2943980">where
  you can</span> <span m="2944190">make sure you</span> <span m="2944460">did</span>
  <span m="2944690">things</span> <span m="2944990">correctly.</span> <span m="2946410">This
  guy</span> <span m="2946850">should</span> <span m="2947040">be</span> <span m="2947160">0</span>
  <span m="2947590">where?</span> <span m="2948320">Here at</span> <span m="2948600">minus</span>
  <span m="2948950">a</span> <span m="2949286">third,</span> <span m="2949622">and</span>
  <span m="2949960">here</span> <span m="2950290">at plus</span> <span m="2950530">a
  third.</span> <span m="2951000">The</span> <span m="2951110">two</span> <span m="2951310">points</span>
  <span m="2951770">at</span> <span m="2951870">which</span> <span m="2952100">we</span>
  <span m="2952630">asked</span> <span m="2952920">the</span> <span m="2953000">residual</span>
  <span m="2953380">will</span> <span m="2953470">be</span> <span m="2953580">0,</span>
  <span m="2955380">and then</span> <span m="2955680">everywhere</span> <span m="2956040">else</span>
  <span m="2956220">it</span> <span m="2956430">ends up</span> <span m="2956620">being</span>
  <span m="2957210">non-zero.</span> <span m="2958664">Yep.</span></p><p><span m="2963440">OK.</span>
  <span m="2963790">So</span> <span m="2966860">that</span> <span m="2967090">is</span>
  <span m="2967680">it for</span> <span m="2967770">collocation</span> <span m="2968255">method.</span>
  <span m="2970680">Any</span> <span m="2972920">questions?</span> <span m="2975400">Good?</span>
  <span m="2975900">It''s</span> <span m="2976040">clear?</span></p><p><span m="2980030">All
  right.</span> <span m="2980480">So now</span> <span m="2980680">we''re</span> <span
  m="2980750">going</span> <span m="2980880">to</span> <span m="2980960">talk</span>
  <span m="2981110">about</span> <span m="2982170">the</span> <span m="2982270">weighted</span>
  <span m="2982530">residuals</span> <span m="2983416">method--</span> <span m="2984302">the
  method of</span> <span m="2984745">weighted</span> <span m="2985188">residuals.</span>
  <span m="2986080">And</span> <span m="2986450">this</span> <span m="2986600">is</span>
  <span m="2986760">really</span> <span m="2987400">the</span> <span m="2987500">method</span>
  <span m="2987900">that</span> <span m="2988130">we</span> <span m="2988340">want</span>
  <span m="2988720">to</span> <span m="2989750">focus</span> <span m="2990030">in</span>
  <span m="2990150">on</span> <span m="2990350">because</span> <span m="2990760">this</span>
  <span m="2990980">is</span> <span m="2991110">going</span> <span m="2991230">to</span>
  <span m="2991300">be</span> <span m="2991390">the</span> <span m="2991470">launching</span>
  <span m="2991830">point</span> <span m="2992080">for</span> <span m="2992220">finite</span>
  <span m="2992410">elements.</span></p><p><span m="2993710">But</span> <span m="2993890">again,</span>
  <span m="2994130">we were</span> <span m="2994300">talking</span> <span m="2994550">about</span>
  <span m="2994780">collocation</span> <span m="2995480">just</span> <span m="2995620">sort</span>
  <span m="2995740">of</span> <span m="2996070">as</span> <span m="2996280">a</span>
  <span m="2996340">way</span> <span m="2996580">for</span> <span m="2996730">you</span>
  <span m="2996880">to</span> <span m="2997170">start</span> <span m="2997490">thinking</span>
  <span m="2997830">about</span> <span m="2998090">what</span> <span m="2998200">it</span>
  <span m="2998290">means</span> <span m="2998660">to</span> <span m="2998780">approximate</span>
  <span m="3000362">a</span> <span m="3000720">solution</span> <span m="3001520">with</span>
  <span m="3001670">a</span> <span m="3001710">finite</span> <span m="3002020">number</span>
  <span m="3002240">of</span> <span m="3002330">basis</span> <span m="3002650">functions,</span>
  <span m="3003180">and</span> <span m="3003790">also</span> <span m="3004250">to</span>
  <span m="3004390">think</span> <span m="3004610">about</span> <span m="3005030">there
  being</span> <span m="3005520">different</span> <span m="3005950">ways</span> <span
  m="3006230">for</span> <span m="3006510">you</span> <span m="3006630">to</span>
  <span m="3006850">actually</span> <span m="3007230">come</span> <span m="3007430">up</span>
  <span m="3007540">with</span> <span m="3007650">the</span> <span m="3007720">coefficients.</span></p><p><span
  m="3008310">Yeah,</span> <span m="3008807">[? Libby? ?]</span></p><p><span m="3011789">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="3025530">PROFESSOR: Maybe</span> <span m="3026140">start</span>
  <span m="3026440">with</span> <span m="3026590">the</span> <span m="3026982">error.</span>
  <span m="3027766">You</span> <span m="3028160">have</span> <span m="3028230">to
  deal with the fact</span> <span m="3028470">that</span> <span m="3028580">error</span>
  <span m="3028963">is</span> <span m="3029346">0</span> <span m="3029730">at</span>
  <span m="3030020">the</span> <span m="3030350">end</span> <span m="3030680">point.</span></p><p><span
  m="3033024">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3038990">PROFESSOR: So</span>
  <span m="3039130">let''s</span> <span m="3040050">try to put them</span> <span m="3040544">side</span>
  <span m="3041038">by</span> <span m="3041532">side.</span></p><p><span m="3043508">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="3046480">PROFESSOR: Yeah.</span> <span m="3048250">Yeah,</span>
  <span m="3049180">that''s</span> <span m="3049310">exactly</span> <span m="3049720">right.</span></p><p><span
  m="3051660">So</span> <span m="3051690">if</span> <span m="3051760">we</span> <span
  m="3051850">start</span> <span m="3052160">with</span> <span m="3052340">the</span>
  <span m="3053430">error,</span> <span m="3056000">shold the error--</span> <span
  m="3058310">it''s</span> <span m="3058470">warming</span> <span m="3058780">up--</span>
  <span m="3058940">yeah?</span></p><p><span m="3059585">AUDIENCE: [INAUDIBLE].</span></p><p><span
  m="3059980">PROFESSOR: Yeah.</span> <span m="3060826">By</span> <span m="3061250">construction</span>
  <span m="3061515">the</span> <span m="3061780">error</span> <span m="3062180">is</span>
  <span m="3062580">0, right?</span> <span m="3062980">Because</span> <span m="3063380">we</span>
  <span m="3063750">constructed</span> <span m="3064320">the</span> <span m="3064400">basis</span>
  <span m="3064690">functions</span> <span m="3065180">to</span> <span m="3065290">be</span>
  <span m="3065460">0</span> <span m="3065825">at</span> <span m="3066190">either</span>
  <span m="3066530">end.</span> <span m="3067327">So no matter</span> <span m="3067734">what</span>
  <span m="3068141">value we choose for</span> <span m="3068550">a1</span> <span m="3068740">and</span>
  <span m="3069105">a2,</span> <span m="3069820">the approximate</span> <span m="3070550">solution</span>
  <span m="3070990">will</span> <span m="3071130">be</span> <span m="3071600">exact</span>
  <span m="3072070">at</span> <span m="3072180">the</span> <span m="3072250">boundary</span>
  <span m="3072620">condition.</span></p><p><span m="3073360">What</span> <span m="3073530">about</span>
  <span m="3073710">the</span> <span m="3073790">residual?</span></p><p><span m="3076100">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="3080610">PROFESSOR: Yeah.</span> <span m="3081690">Say
  it a bit louder.</span></p><p><span m="3082130">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="3084330">PROFESSOR: Yeah.</span> <span m="3084900">So it''s specifically</span>
  <span m="3085670">what</span> <span m="3086940">do you</span> <span m="3087140">think
  is</span> <span m="3087420">not</span> <span m="3087790">what</span> <span m="3087980">it</span>
  <span m="3088090">should</span> <span m="3088300">be</span> <span m="3088540">at</span>
  <span m="3088760">the end point.</span> <span m="3089220">So I''ll put this up</span>
  <span m="3089680">[INAUDIBLE].</span></p><p><span m="3091060">So derivatives.</span>
  <span m="3091210">Yeah,</span> <span m="3091340">exactly right.</span> <span m="3092930">So</span>
  <span m="3093430">it basically is</span> <span m="3093890">telling</span> <span
  m="3094180">you</span> <span m="3094350">that--</span> <span m="3096000">and</span>
  <span m="3096760">you can</span> <span m="3096940">kind of--</span> <span m="3097070">you
  can</span> <span m="3097340">see</span> <span m="3097530">it</span> <span m="3097830">physically</span>
  <span m="3097980">in</span> <span m="3098310">the</span> <span m="3098380">shape,</span>
  <span m="3098650">but you</span> <span m="3099000">can also see it</span> <span
  m="3099350">mathematically</span> <span m="3099940">because</span> <span m="3100440">it</span>
  <span m="3100570">has</span> <span m="3100990">this</span> <span m="3101290">form.</span>
  <span m="3102750">When you take</span> <span m="3103190">a</span> <span m="3103420">derivative,</span>
  <span m="3103870">as soon</span> <span m="3104300">as</span> <span m="3104430">you
  move away</span> <span m="3105530">a</span> <span m="3105630">little</span> <span
  m="3105830">bit,</span> <span m="3106475">things are going to go</span> <span m="3106970">astray</span>
  <span m="3107400">because</span> <span m="3107610">second derivative</span> <span
  m="3108080">is</span> <span m="3108250">not</span> <span m="3108420">right.</span>
  <span m="3108730">and</span> <span m="3108950">at</span> <span m="3109280">the</span>
  <span m="3109430">endpoint,</span> <span m="3110650">the</span> <span m="3111350">derivatives</span>
  <span m="3111695">are</span> <span m="3112040">not</span> <span m="3112335">what</span>
  <span m="3112990">they</span> <span m="3113080">should</span> <span m="3113310">be.</span></p><p><span
  m="3114472">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3117298">PROFESSOR: Yeah,
  it''s not--</span> <span m="3121070">would</span> <span m="3121270">only--</span>
  <span m="3121810">no,</span> <span m="3122100">come</span> <span m="3122330">on,</span>
  <span m="3122630">[INAUDIBLE]</span> <span m="3123055">turn it off.</span></p><p><span
  m="3124330">We''ve</span> <span m="3124470">only</span> <span m="3124640">got</span>
  <span m="3124790">two</span> <span m="3124960">degrees</span> <span m="3125270">of</span>
  <span m="3125360">freedom,</span> <span m="3125783">right?</span> <span m="3126630">We</span>
  <span m="3126830">see</span> <span m="3127070">the</span> <span m="3127190">solution</span>
  <span m="3127620">is</span> <span m="3127720">a</span> <span m="3127760">constant</span>
  <span m="3128800">plus</span> <span m="3129240">a</span> <span m="3129680">quadratic</span>
  <span m="3130110">term</span> <span m="3130350">plus</span> <span m="3130590">the</span>
  <span m="3130935">cubic term.</span> <span m="3131280">We''ve only got</span> <span
  m="3131660">two</span> <span m="3131750">degrees</span> <span m="3131960">of</span>
  <span m="3132050">freedom.</span> <span m="3132510">So</span> <span m="3132650">you</span>
  <span m="3132780">only</span> <span m="3132910">get</span> <span m="3133100">to</span>
  <span m="3134610">pick</span> <span m="3134890">two</span> <span m="3135080">things,</span>
  <span m="3135350">right,</span> <span m="3136360">to</span> <span m="3136700">put</span>
  <span m="3136880">them</span> <span m="3137030">down.</span> <span m="3137340">And</span>
  <span m="3137440">we</span> <span m="3137550">said,</span> <span m="3137780">let''s</span>
  <span m="3137960">make</span> <span m="3138150">a</span> <span m="3138200">residual</span>
  <span m="3139526">be 0 at</span> <span m="3139970">minus</span> <span m="3140280">a
  third</span> <span m="3140410">and plus</span> <span m="3140780">a third.</span>
  <span m="3141930">I</span> <span m="3142020">guess</span> <span m="3142190">we</span>
  <span m="3142290">could</span> <span m="3142490">have</span> <span m="3142640">chosen</span>
  <span m="3143180">to</span> <span m="3143290">make</span> <span m="3143520">a</span>
  <span m="3143560">residual</span> <span m="3144200">0</span> <span m="3144530">at</span>
  <span m="3144835">the</span> <span m="3145140">two end points.</span> <span m="3147380">I</span>
  <span m="3147420">don''t</span> <span m="3147550">know</span> <span m="3147710">what</span>
  <span m="3148080">solution--</span> <span m="3148730">maybe</span> <span m="3148990">Alex</span>
  <span m="3149150">can</span> <span m="3149310">quickly</span> <span m="3150040">figure</span>
  <span m="3150310">out</span> <span m="3150870">in his head</span> <span m="3151135">what</span>
  <span m="3151400">solution</span> <span m="3151710">that</span> <span m="3151870">would</span>
  <span m="3151980">have</span> <span m="3152110">been.</span></p><p><span m="3152320">That</span>
  <span m="3152450">would be</span> <span m="3152560">kind</span> <span m="3152800">of</span>
  <span m="3152880">a</span> <span m="3152950">bizarre</span> <span m="3154850">choice,</span>
  <span m="3155280">but</span> <span m="3157670">I''m</span> <span m="3157790">not--</span>
  <span m="3158260">I''m</span> <span m="3158400">not</span> <span m="3158530">sure</span>
  <span m="3158680">is that--</span> <span m="3158920">I''m</span> <span m="3159080">just
  wondering</span> <span m="3159510">if that</span> <span m="3159650">might</span>
  <span m="3159810">give</span> <span m="3159940">a</span> <span m="3160050">0</span>
  <span m="3161610">solution</span> <span m="3162130">everywhere.</span> <span m="3163310">But</span>
  <span m="3163490">you</span> <span m="3163810">can''t</span> <span m="3164250">you</span>
  <span m="3164340">can''t</span> <span m="3164580">kind</span> <span m="3164750">of</span>
  <span m="3164870">have</span> <span m="3165060">everything.</span> <span m="3165540">You</span>
  <span m="3165690">only</span> <span m="3165830">got--</span> <span m="3166090">we</span>
  <span m="3166250">only</span> <span m="3166390">got</span> <span m="3166560">the</span>
  <span m="3166630">residual</span> <span m="3167040">at the</span> <span m="3167480">minus</span>
  <span m="3167880">one third</span> <span m="3168070">and</span> <span m="3168250">the</span>
  <span m="3168320">plus</span> <span m="3168400">one third</span> <span m="3168740">collocation
  point.</span></p><p><span m="3172470">There</span> <span m="3172640">seems</span>
  <span m="3172840">to</span> <span m="3172940">be</span> <span m="3173080">a</span>
  <span m="3173180">lag,</span> <span m="3173565">a big lag,</span> <span m="3174790">in</span>
  <span m="3174890">the</span> <span m="3174980">projector--</span> <span m="3175330">there</span>
  <span m="3175380">we</span> <span m="3175500">go,</span> <span m="3175980">get it</span>
  <span m="3176380">off.</span></p><p><span m="3179840">OK.</span> <span m="3179940">So</span>
  <span m="3182000">any</span> <span m="3182240">other</span> <span m="3182360">questions</span>
  <span m="3182810">about</span> <span m="3183930">collocation?</span></p><p><span
  m="3186778">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3197890">PROFESSOR: Yeah,</span>
  <span m="3198160">so that''s</span> <span m="3198350">a</span> <span m="3198400">good</span>
  <span m="3198540">question.</span> <span m="3198980">If</span> <span m="3198990">you</span>
  <span m="3199080">look</span> <span m="3199250">at</span> <span m="3199320">the</span>
  <span m="3199400">residual</span> <span m="3199890">could</span> <span m="3200100">you</span>
  <span m="3200200">tell</span> <span m="3200460">whether</span> <span m="3200630">you''re</span>
  <span m="3200780">using</span> <span m="3201280">too</span> <span m="3201500">low</span>
  <span m="3201750">of</span> <span m="3202080">an</span> <span m="3202170">approximation?</span>
  <span m="3202900">In other words,</span> <span m="3203690">can</span> <span m="3203970">you</span>
  <span m="3204110">tell</span> <span m="3204410">by</span> <span m="3204530">looking</span>
  <span m="3204750">at</span> <span m="3204820">the</span> <span m="3204890">residual</span>
  <span m="3205400">how</span> <span m="3205550">bad</span> <span m="3205780">the</span>
  <span m="3205900">error</span> <span m="3206160">might</span> <span m="3206450">be</span>
  <span m="3207060">in</span> <span m="3207250">the</span> <span m="3207380">solution?</span>
  <span m="3208480">And</span> <span m="3208530">the</span> <span m="3208600">answer</span>
  <span m="3208970">is,</span> <span m="3209490">yes.</span> <span m="3209870">And</span>
  <span m="3209990">there''s</span> <span m="3210220">some</span> <span m="3210880">beautiful</span>
  <span m="3211410">theory--</span> <span m="3212020">again, it''s going</span> <span
  m="3212470">to</span> <span m="3212550">depend</span> <span m="3212820">on</span>
  <span m="3212930">PDE</span> <span m="3213570">that</span> <span m="3213740">you''re</span>
  <span m="3213840">talking</span> <span m="3214200">about--</span> <span m="3214840">this</span>
  <span m="3215110">theory</span> <span m="3215570">that</span> <span m="3215810">basically</span>
  <span m="3216300">says</span> <span m="3216690">that</span> <span m="3217200">it</span>
  <span m="3217360">relates</span> <span m="3217840">the</span> <span m="3217930">norm</span>
  <span m="3218360">of the</span> <span m="3218690">residual--</span> <span m="3219590">how
  big is</span> <span m="3219840">the</span> <span m="3219930">residual</span> <span
  m="3220970">integrated</span> <span m="3221500">over</span> <span m="3221670">the</span>
  <span m="3221760">domain--</span> <span m="3222650">compared</span> <span m="3222860">to</span>
  <span m="3223070">how</span> <span m="3223280">big is</span> <span m="3223710">the</span>
  <span m="3223830">error</span> <span m="3224530">integrated</span> <span m="3224875">over</span>
  <span m="3225220">the</span> <span m="3225290">domain.</span> <span m="3225600">And</span>
  <span m="3225720">they''re</span> <span m="3225850">related</span> <span m="3226290">by</span>
  <span m="3227930">a</span> <span m="3228000">constant,</span> <span m="3228610">which</span>
  <span m="3228930">depends</span> <span m="3229320">on</span> <span m="3230680">the</span>
  <span m="3230780">properties</span> <span m="3231230">of</span> <span m="3231340">the</span>
  <span m="3231430">PDE</span> <span m="3231770">you''re solving.</span></p><p><span
  m="3233100">And</span> <span m="3233270">that</span> <span m="3233330">comes back</span>
  <span m="3233660">to</span> <span m="3233760">what</span> <span m="3233880">I</span>
  <span m="3233940">was</span> <span m="3235420">talking</span> <span m="3235770">about</span>
  <span m="3236790">earlier,</span> <span m="3237220">that</span> <span m="3237470">for</span>
  <span m="3237630">a nice</span> <span m="3238000">PDE</span> <span m="3238370">like</span>
  <span m="3238550">this</span> <span m="3238680">1D</span> <span m="3239000">diffusion,</span>
  <span m="3239280">it</span> <span m="3239560">actually</span> <span m="3239800">turns
  out that</span> <span m="3240280">looking</span> <span m="3240580">at</span> <span
  m="3240660">the</span> <span m="3240730">residual</span> <span m="3241490">is</span>
  <span m="3241610">a</span> <span m="3241740">really</span> <span m="3242020">good</span>
  <span m="3242200">way</span> <span m="3242530">to</span> <span m="3242880">understand</span>
  <span m="3243370">what</span> <span m="3243500">would</span> <span m="3243630">be</span>
  <span m="3243770">happening</span> <span m="3244050">with</span> <span m="3244190">the</span>
  <span m="3244280">error.</span> <span m="3246380">For</span> <span m="3246570">nastier</span>
  <span m="3246840">PDEs,</span> <span m="3247420">that''s</span> <span m="3247600">not</span>
  <span m="3247770">so</span> <span m="3247860">much.</span></p><p><span m="3248340">But</span>
  <span m="3249010">what</span> <span m="3249160">you''re</span> <span m="3249510">sort
  of</span> <span m="3249710">asking</span> <span m="3250050">about</span> <span m="3250330">is</span>
  <span m="3250560">to</span> <span m="3250790">a</span> <span m="3250860">lot</span>
  <span m="3251060">of</span> <span m="3251190">the</span> <span m="3251280">theory</span>
  <span m="3251770">of</span> <span m="3252140">the</span> <span m="3252360">error</span>
  <span m="3252600">analysis</span> <span m="3253340">in</span> <span m="3253440">the
  finite</span> <span m="3253530">element</span> <span m="3253900">method--</span>
  <span m="3255240">that</span> <span m="3255590">people</span> <span m="3255900">do</span>
  <span m="3256060">a</span> <span m="3256180">lot</span> <span m="3256400">of</span>
  <span m="3256500">very</span> <span m="3256870">rigorous</span> <span m="3257510">analysis</span>
  <span m="3258080">of</span> <span m="3258190">error</span> <span m="3259040">based</span>
  <span m="3259370">on</span> <span m="3259490">being</span> <span m="3259620">able</span>
  <span m="3259850">to</span> <span m="3259970">compute</span> <span m="3260320">the</span>
  <span m="3260400">residual.</span> <span m="3262040">And</span> <span m="3262240">in</span>
  <span m="3262340">fact,</span> <span m="3262770">the</span> <span m="3262890">residuals</span>
  <span m="3263640">also</span> <span m="3264250">can</span> <span m="3264520">then
  start</span> <span m="3265050">being</span> <span m="3265180">an</span> <span m="3265240">indicator</span>
  <span m="3265700">for</span> <span m="3265920">figuring</span> <span m="3266310">out</span>
  <span m="3266490">how</span> <span m="3266580">to</span> <span m="3266670">do</span>
  <span m="3266780">things</span> <span m="3267000">like</span> <span m="3267140">[INAUDIBLE]</span>
  <span m="3267370">refinement,</span> <span m="3267806">and</span> <span m="3268680">all</span>
  <span m="3268790">these</span> <span m="3268960">things</span> <span m="3269170">are</span>
  <span m="3269220">kind</span> <span m="3269710">of</span> <span m="3269820">related.</span>
  <span m="3270600">And</span> <span m="3270700">then</span> <span m="3271820">the</span>
  <span m="3271910">theory</span> <span m="3272400">with</span> <span m="3272640">adjoint</span>
  <span m="3273000">methods.</span></p><p><span m="3273880">So</span> <span m="3274320">if</span>
  <span m="3274450">you''re</span> <span m="3274560">interested</span> <span m="3275010">in
  that stuff</span> <span m="3275250">you</span> <span m="3275440">have to take</span>
  <span m="3275650">[? 16920 ?],</span> <span m="3276220">which</span> <span m="3276420">Professor</span>
  <span m="3276630">[? Wong ?]</span> <span m="3277410">will be</span> <span m="3277500">teaching</span>
  <span m="3277810">in</span> <span m="3277920">the</span> <span m="3278040">fall,
  which</span> <span m="3278880">is</span> <span m="3279300">the grad</span> <span
  m="3279720">class on</span> <span m="3280140">numerical</span> <span m="3280590">methods</span>
  <span m="3281040">of</span> <span m="3281070">PDEs.</span> <span m="3281170">I don''t
  know</span> <span m="3281250">how</span> <span m="3281410">much</span> <span m="3281700">you</span>
  <span m="3281790">get into that stuff.</span></p><p><span m="3282740">AUDIENCE:
  [INAUDIBLE].</span></p><p><span m="3285250">PROFESSOR: Little</span> <span m="3285410">bit</span>
  <span m="3285530">more</span> <span m="3285640">than</span> <span m="3285750">here.</span>
  <span m="3285850">But</span> <span m="3286000">you have to</span> <span m="3286170">take</span>
  <span m="3286380">that</span> <span m="3286470">class</span> <span m="3286810">so
  that</span> <span m="3286930">then</span> <span m="3287060">you</span> <span m="3287130">can</span>
  <span m="3287240">take</span> <span m="3287400">[? 16930 ?]</span> <span m="3289070">which</span>
  <span m="3289450">really</span> <span m="3289670">would</span> <span m="3289840">get</span>
  <span m="3289990">you</span> <span m="3290110">into</span> <span m="3290340">it.</span>
  <span m="3290840">Right?</span> <span m="3295340">Yeah.</span></p><p><span m="3298160">OK.</span>
  <span m="3298820">That''s</span> <span m="3299190">good.</span> <span m="3299390">That''s</span>
  <span m="3299560">great</span> <span m="3299790">questions.</span></p><p><span m="3302710">So</span>
  <span m="3302920">now,</span> <span m="3303270">if you</span> <span m="3303620">guys
  are</span> <span m="3304340">ready,</span> <span m="3304630">we</span> <span m="3304770">can</span>
  <span m="3304920">talk</span> <span m="3305120">about</span> <span m="3305460">the</span>
  <span m="3305580">method</span> <span m="3305930">of</span> <span m="3306110">weighted</span>
  <span m="3306410">residuals,</span> <span m="3306960">which</span> <span m="3307030">hopefully</span>
  <span m="3307400">won''t</span> <span m="3308050">be</span> <span m="3308210">too</span>
  <span m="3308390">much</span> <span m="3308660">of</span> <span m="3308790">a</span>
  <span m="3309250">jump</span> <span m="3309690">from</span> <span m="3309910">where</span>
  <span m="3310070">we</span> <span m="3310240">are,</span> <span m="3310550">but</span>
  <span m="3310720">it</span> <span m="3312100">is</span> <span m="3312220">a</span>
  <span m="3312290">different</span> <span m="3312840">philosophy.</span> <span m="3315410">So</span>
  <span m="3315570">everything</span> <span m="3315980">is</span> <span m="3316130">the</span>
  <span m="3316230">same</span> <span m="3316710">up</span> <span m="3316840">until</span>
  <span m="3317010">the</span> <span m="3317100">point</span> <span m="3317370">that</span>
  <span m="3317510">we</span> <span m="3318440">define</span> <span m="3318970">this</span>
  <span m="3319190">residual.</span> <span m="3321020">But where</span> <span m="3321400">we''re</span>
  <span m="3321550">going</span> <span m="3321930">to</span> <span m="3322590">kind</span>
  <span m="3322770">of</span> <span m="3323880">take</span> <span m="3324050">a</span>
  <span m="3324100">fork</span> <span m="3324410">in</span> <span m="3324490">the</span>
  <span m="3324590">road</span> <span m="3324910">is,</span> <span m="3325120">now</span>
  <span m="3326390">we''re</span> <span m="3326540">going</span> <span m="3326660">to</span>
  <span m="3326750">use</span> <span m="3327020">a</span> <span m="3327070">different</span>
  <span m="3327550">strategy</span> <span m="3328640">for</span> <span m="3329200">coming</span>
  <span m="3329620">up</span> <span m="3329740">with</span> <span m="3329890">the</span>
  <span m="3329960">two</span> <span m="3330180">conditions</span> <span m="3330830">to</span>
  <span m="3330920">figure</span> <span m="3331140">out</span> <span m="3331270">what</span>
  <span m="3331390">those</span> <span m="3331620">two</span> <span m="3331790">degrees</span>
  <span m="3332060">of</span> <span m="3332130">freedom</span> <span m="3332420">are.</span></p><p><span
  m="3333920">OK?</span> <span m="3334920">So same</span> <span m="3335230">idea--</span>
  <span m="3335640">approximating</span> <span m="3336170">the</span> <span m="3336250">solution</span>
  <span m="3337530">with</span> <span m="3337720">the</span> <span m="3337800">basis</span>
  <span m="3338140">functions</span> <span m="3338750">and</span> <span m="3338840">[?
  the extension ?].</span> <span m="3340220">But</span> <span m="3340370">now</span>
  <span m="3340600">what''s</span> <span m="3340790">different</span> <span m="3341150">is,</span>
  <span m="3341510">how</span> <span m="3341720">do</span> <span m="3341820">we</span>
  <span m="3341930">come</span> <span m="3342160">up</span> <span m="3342300">with</span>
  <span m="3342430">the</span> <span m="3342490">conditions</span> <span m="3344010">to</span>
  <span m="3344130">determine</span> <span m="3344560">the</span> <span m="3344630">functions
  a1</span> <span m="3345030">and</span> <span m="3345472">a2.</span></p><p><span
  m="3348130">And--</span> <span m="3351194">so--</span> <span m="3353010">method</span>
  <span m="3353320">of</span> <span m="3353440">weighted</span> <span m="3353750">residuals.</span></p><p><span
  m="3364770">OK.</span> <span m="3365220">So</span> <span m="3365630">in</span> <span
  m="3365710">order</span> <span m="3365990">to</span> <span m="3368300">move</span>
  <span m="3368510">forward--</span> <span m="3368920">in other</span> <span m="3369020">words,</span>
  <span m="3370376">in order</span> <span m="3370790">to</span> <span m="3370860">find</span>
  <span m="3371100">these</span> <span m="3371260">two</span> <span m="3371400">conditions,</span>
  <span m="3372000">we''re</span> <span m="3372140">going</span> <span m="3372290">to</span>
  <span m="3372370">define</span> <span m="3372670">something</span> <span m="3373000">else.</span>
  <span m="3373270">We''re</span> <span m="3373340">going</span> <span m="3373460">to</span>
  <span m="3373530">define</span> <span m="3374840">what''s</span> <span m="3375080">called</span>
  <span m="3375590">a</span> <span m="3375730">weighted</span> <span m="3376420">residual.</span></p><p><span
  m="3381010">OK?</span> <span m="3381290">So</span> <span m="3381380">we</span> <span
  m="3381470">defined</span> <span m="3383410">the</span> <span m="3383530">residual--</span>
  <span m="3383810">it</span> <span m="3384230">still</span> <span m="3384470">sits</span>
  <span m="3384700">over</span> <span m="3384880">here--</span> <span m="3385690">which</span>
  <span m="3385900">is</span> <span m="3386350">the</span> <span m="3386430">thing
  that</span> <span m="3386840">we</span> <span m="3387000">get</span> <span m="3387270">when</span>
  <span m="3387400">we</span> <span m="3387500">substitute</span> <span m="3388000">the</span>
  <span m="3388260">approximate</span> <span m="3388880">solution</span> <span m="3390010">into</span>
  <span m="3390870">the</span> <span m="3391390">PDE.</span> <span m="3394270">Now</span>
  <span m="3394450">I''m</span> <span m="3394560">going</span> <span m="3394690">to</span>
  <span m="3394770">define</span> <span m="3395500">the</span> <span m="3395630">weighted</span>
  <span m="3396500">residual,</span> <span m="3397170">and</span> <span m="3397260">I''m</span>
  <span m="3397350">going</span> <span m="3397480">to</span> <span m="3397550">call</span>
  <span m="3397970">it--</span> <span m="3400860">and</span> <span m="3401000">actually,</span>
  <span m="3401440">I</span> <span m="3401550">was</span> <span m="3401730">realizing</span>
  <span m="3402490">when</span> <span m="3402640">I</span> <span m="3402710">was</span>
  <span m="3402910">going</span> <span m="3403180">through</span> <span m="3403400">that</span>
  <span m="3403620">the</span> <span m="3403750">notation</span> <span m="3404280">in</span>
  <span m="3404410">the</span> <span m="3404480">notes</span> <span m="3405940">jumped</span>
  <span m="3406290">around</span> <span m="3406590">a</span> <span m="3406620">little</span>
  <span m="3406860">bit--</span> <span m="3408081">so</span> <span m="3408490">let''s</span>
  <span m="3408600">call</span> <span m="3408860">this</span> <span m="3409120">capital</span>
  <span m="3409530">R</span> <span m="3410010">sub</span> <span m="3410290">i.</span>
  <span m="3411610">It''s</span> <span m="3411750">going</span> <span m="3411870">to</span>
  <span m="3411950">be</span> <span m="3412090">a</span> <span m="3412150">function</span>
  <span m="3412710">of</span> <span m="3413170">the</span> <span m="3413360">approximate</span>
  <span m="3413980">solution</span> <span m="3415858">t tilde,</span> <span m="3419850">but</span>
  <span m="3420010">not</span> <span m="3420250">a</span> <span m="3420280">function</span>
  <span m="3420660">of</span> <span m="3420780">x</span> <span m="3421180">because</span>
  <span m="3421480">we''re</span> <span m="3421600">going</span> <span m="3421720">to</span>
  <span m="3421860">integrate</span> <span m="3422570">things</span> <span m="3422840">out</span>
  <span m="3423110">of</span> <span m="3423210">x.</span></p><p><span m="3423570">So</span>
  <span m="3423730">we''re</span> <span m="3423810">going</span> <span m="3423930">to</span>
  <span m="3424000">define</span> <span m="3424460">it as</span> <span m="3425010">the</span>
  <span m="3425140">integral</span> <span m="3425780">over</span> <span m="3426750">the</span>
  <span m="3426860">domain.</span> <span m="3427540">And</span> <span m="3427590">again,</span>
  <span m="3427970">the</span> <span m="3428050">domain</span> <span m="3428370">in
  our</span> <span m="3428630">simple</span> <span m="3428870">problem</span> <span
  m="3429270">is</span> <span m="3429400">just</span> <span m="3429620">x</span> <span
  m="3429870">from</span> <span m="3430120">minus</span> <span m="3430430">1</span>
  <span m="3430670">to</span> <span m="3430790">1.</span> <span m="3431970">We''re</span>
  <span m="3432090">going</span> <span m="3432210">to</span> <span m="3432340">take</span>
  <span m="3432710">a</span> <span m="3432780">[? weighting ?]</span> <span m="3433220">function,</span>
  <span m="3433810">which</span> <span m="3434170">we''ll</span> <span m="3434390">write</span>
  <span m="3434610">as</span> <span m="3434760">wi,</span> <span m="3436580">it''s</span>
  <span m="3436770">a</span> <span m="3436820">function</span> <span m="3437160">of</span>
  <span m="3437290">x.</span> <span m="3438276">And</span> <span m="3438770">we''re</span>
  <span m="3438800">going</span> <span m="3438930">to</span> <span m="3439000">take</span>
  <span m="3439250">our</span> <span m="3439450">residual--</span> <span m="3442660">you</span>
  <span m="3442770">know</span> <span m="3442920">what, I''m</span> <span m="3443030">going</span>
  <span m="3443150">to</span> <span m="3443220">give</span> <span m="3443390">this</span>
  <span m="3443560">a</span> <span m="3443640">little r</span> <span m="3444300">just</span>
  <span m="3448190">to</span> <span m="3448320">make</span> <span m="3448500">sure</span>
  <span m="3448650">that</span> <span m="3448810">they''re</span> <span m="3448930">different.</span>
  <span m="3457940">And</span> <span m="3458210">that''s</span> <span m="3458320">going</span>
  <span m="3458440">to</span> <span m="3458510">be</span> <span m="3458620">integrated</span>
  <span m="3458895">over</span> <span m="3460720">ex.</span> <span m="3462010">So
  again,</span> <span m="3462160">little</span> <span m="3462540">r</span> <span m="3463030">sub</span>
  <span m="3463240">i</span> <span m="3464480">is</span> <span m="3464620">going</span>
  <span m="3464740">to</span> <span m="3464820">be</span> <span m="3465010">our</span>
  <span m="3465300">i''th</span> <span m="3466580">weighted</span> <span m="3466910">residual.</span>
  <span m="3467205">And</span> <span m="3467500">what</span> <span m="3467620">you''re</span>
  <span m="3467730">going</span> <span m="3467860">to</span> <span m="3467920">see</span>
  <span m="3468210">is</span> <span m="3468370">that</span> <span m="3468500">we''re</span>
  <span m="3468560">going</span> <span m="3468690">to</span> <span m="3468750">need</span>
  <span m="3469090">n</span> <span m="3469360">of</span> <span m="3469450">these</span>
  <span m="3469730">things.</span> <span m="3472130">So</span> <span m="3472210">again,</span>
  <span m="3472520">we''re</span> <span m="3472630">looking</span> <span m="3472880">for</span>
  <span m="3473030">n</span> <span m="3473350">conditions</span> <span m="3474060">to</span>
  <span m="3474170">find</span> <span m="3474450">out</span> <span m="3474650">n,</span>
  <span m="3475590">a</span> <span m="3475690">non-coefficient,</span> <span m="3478290">and</span>
  <span m="3478450">it''s</span> <span m="3478600">defined</span> <span m="3479030">to</span>
  <span m="3479140">be</span> <span m="3479330">the</span> <span m="3479450">integral</span>
  <span m="3480520">of</span> <span m="3482410">a</span> <span m="3482550">weighting</span>
  <span m="3483000">function,</span> <span m="3484020">which is</span> <span m="3484180">our</span>
  <span m="3484290">wi,</span> <span m="3491890">times</span> <span m="3492850">this</span>
  <span m="3492990">guy</span> <span m="3493350">here,</span> <span m="3493610">which</span>
  <span m="3493850">is</span> <span m="3494070">our</span> <span m="3495190">residual.</span>
  <span m="3497750">And</span> <span m="3498040">we''re integrating</span> <span m="3498580">over</span>
  <span m="3498760">the</span> <span m="3498830">domain.</span> <span m="3499750">Here''s</span>
  <span m="3500130">x</span> <span m="3501220">going</span> <span m="3501550">from</span>
  <span m="3501830">minus</span> <span m="3502220">1</span> <span m="3502680">to</span>
  <span m="3502800">1.</span> <span m="3506160">OK.</span> <span m="3506420">So</span>
  <span m="3506720">residual</span> <span m="3507090">is a</span> <span m="3507180">function</span>
  <span m="3507480">of</span> <span m="3507570">x,</span> <span m="3508040">weighted</span>
  <span m="3508400">residual</span> <span m="3509050">is</span> <span m="3509230">not</span>
  <span m="3509430">a</span> <span m="3509460">function</span> <span m="3509740">of</span>
  <span m="3509810">x</span> <span m="3509990">because</span> <span m="3510160">I''ve</span>
  <span m="3510500">integrated</span> <span m="3511110">over,</span> <span m="3511815">and</span>
  <span m="3512150">the</span> <span m="3512250">integration</span> <span m="3512790">is</span>
  <span m="3512930">weighted</span> <span m="3513300">by</span> <span m="3513480">some</span>
  <span m="3513710">weighting</span> <span m="3513990">function</span> <span m="3514250">wi.</span>
  <span m="3516020">But</span> <span m="3516180">the</span> <span m="3516260">weight</span>
  <span m="3516500">of</span> <span m="3516700">residual</span> <span m="3517210">is</span>
  <span m="3517300">still</span> <span m="3517510">a</span> <span m="3517580">function</span>
  <span m="3517940">of</span> <span m="3518020">our</span> <span m="3518120">approximate</span>
  <span m="3518578">solution</span> <span m="3519036">t tilde.</span></p><p><span
  m="3521790">OK.</span> <span m="3522500">So now</span> <span m="3522670">what</span>
  <span m="3522810">does</span> <span m="3522990">the</span> <span m="3524420">method</span>
  <span m="3524700">of</span> <span m="3524780">weighted</span> <span m="3525040">residuals</span>
  <span m="3525325">do?</span> <span m="3527380">It says</span> <span m="3529490">let''s
  choose n</span> <span m="3530480">different</span> <span m="3530850">weighting</span>
  <span m="3531140">functions,</span> <span m="3531720">w1,</span> <span m="3532070">w2,</span>
  <span m="3532440">up to</span> <span m="3533650">wn.</span> <span m="3535200">Let''s</span>
  <span m="3535610">define</span> <span m="3536220">the</span> <span m="3536820">n</span>
  <span m="3537620">corresponding</span> <span m="3538500">weighted</span> <span m="3538780">residuals,</span>
  <span m="3539830">and let''s set</span> <span m="3540140">each</span> <span m="3540410">of</span>
  <span m="3540500">those</span> <span m="3540730">weighted</span> <span m="3541000">residuals</span>
  <span m="3541530">equal</span> <span m="3541800">to</span> <span m="3541880">0.</span>
  <span m="3542910">Each</span> <span m="3543160">time</span> <span m="3543490">we</span>
  <span m="3543590">set</span> <span m="3543780">a</span> <span m="3544160">weighted
  residual</span> <span m="3544640">to</span> <span m="3544790">0</span> <span m="3545060">we''re</span>
  <span m="3545140">going</span> <span m="3545260">to</span> <span m="3545320">get</span>
  <span m="3545450">one</span> <span m="3545650">condition,</span> <span m="3546150">right?</span>
  <span m="3547470">So</span> <span m="3547590">we''ll</span> <span m="3547650">do</span>
  <span m="3547750">that</span> <span m="3547970">n</span> <span m="3548210">times</span>
  <span m="3548830">with</span> <span m="3549090">n</span> <span m="3549710">different</span>
  <span m="3550070">weighting</span> <span m="3550420">functions,</span> <span m="3551020">and</span>
  <span m="3551130">that</span> <span m="3551280">will</span> <span m="3551380">give</span>
  <span m="3551570">us</span> <span m="3551750">the</span> <span m="3551920">n</span>
  <span m="3552490">conditions</span> <span m="3553000">we</span> <span m="3553100">need</span>
  <span m="3554130">to</span> <span m="3554280">compute</span> <span m="3554830">our
  n</span> <span m="3555620">a</span> <span m="3555810">coefficients.</span></p><p><span
  m="3558650">Yes?</span> <span m="3561890">Seems</span> <span m="3562100">like</span>
  <span m="3562180">kind</span> <span m="3562360">of</span> <span m="3562420">a</span>
  <span m="3562500">bizarre</span> <span m="3562870">thing</span> <span m="3563060">to</span>
  <span m="3563150">them.</span> <span m="3564680">It''s</span> <span m="3564800">OK?</span>
  <span m="3567710">You guys are</span> <span m="3568050">so</span> <span m="3568110">quiet.</span>
  <span m="3568450">Does</span> <span m="3568540">that</span> <span m="3568680">mean</span>
  <span m="3570260">that</span> <span m="3570450">you</span> <span m="3571270">think</span>
  <span m="3571430">this</span> <span m="3571590">is</span> <span m="3572860">very</span>
  <span m="3573170">easy,</span> <span m="3573540">or</span> <span m="3574106">kind
  of</span> <span m="3574532">weird?</span> <span m="3576240">We</span> <span m="3576400">don''t</span>
  <span m="3576530">know.</span></p><p><span m="3581850">So let''s</span> <span m="3582110">write</span>
  <span m="3582330">it</span> <span m="3582420">out</span> <span m="3582600">a</span>
  <span m="3582630">little</span> <span m="3582973">bit</span> <span m="3583316">and</span>
  <span m="3583660">see.</span> <span m="3585390">So</span> <span m="3585770">again,</span>
  <span m="3586060">the</span> <span m="3586130">method</span> <span m="3586380">of</span>
  <span m="3586460">weighted</span> <span m="3586810">residuals--</span> <span m="3587690">we''re
  going to</span> <span m="3588160">require</span> <span m="3591205">n</span> <span
  m="3592130">weighted</span> <span m="3592720">residuals</span> <span m="3600370">to</span>
  <span m="3600500">be</span> <span m="3600680">0.</span> <span m="3602544">So</span>
  <span m="3603180">that</span> <span m="3603390">means</span> <span m="3606510">we''re</span>
  <span m="3606650">going</span> <span m="3606770">to</span> <span m="3606830">have</span>
  <span m="3607070">to</span> <span m="3607180">choose</span> <span m="3611130">n</span>
  <span m="3611860">weighting</span> <span m="3612330">function.</span> <span m="3620140">Those</span>
  <span m="3620300">are</span> <span m="3620490">the w1,</span> <span m="3621990">w2,</span>
  <span m="3625490">up to</span> <span m="3628000">wn.</span> <span m="3629845">They''re</span>
  <span m="3630280">all</span> <span m="3630430">functions</span> <span m="3630660">of</span>
  <span m="3630740">x.</span> <span m="3633380">And</span> <span m="3633710">we''re</span>
  <span m="3633840">going</span> <span m="3634170">to</span> <span m="3634260">then</span>
  <span m="3635165">get,</span> <span m="3635650">again,</span> <span m="3636110">n</span>
  <span m="3636320">equations</span> <span m="3640760">to</span> <span m="3640970">determine</span>
  <span m="3641245">these</span> <span m="3641520">coefficients,</span> <span m="3645400">a1,</span>
  <span m="3645600">a2,</span> <span m="3648028">to a</span> <span m="3648520">n.</span></p><p><span
  m="3660340">OK.</span> <span m="3661255">So</span> <span m="3661690">first</span>
  <span m="3661850">thing</span> <span m="3662050">we</span> <span m="3662110">need</span>
  <span m="3662220">to</span> <span m="3662280">do</span> <span m="3662460">is</span>
  <span m="3662620">choose</span> <span m="3662950">n</span> <span m="3663260">weighting</span>
  <span m="3663550">function.</span> <span m="3664220">So this</span> <span m="3664350">is</span>
  <span m="3664420">the</span> <span m="3664500">first</span> <span m="3664720">question,</span>
  <span m="3665120">is</span> <span m="3665390">now</span> <span m="3666590">what</span>
  <span m="3666760">do</span> <span m="3666820">we</span> <span m="3666970">choose</span>
  <span m="3667460">for</span> <span m="3667630">the</span> <span m="3667720">wi''s?</span>
  <span m="3671810">What</span> <span m="3672010">do</span> <span m="3672120">we choose</span>
  <span m="3672390">here?</span></p><p><span m="3674260">So the</span> <span m="3674390">answer</span>
  <span m="3674690">is</span> <span m="3675060">that there</span> <span m="3675540">is</span>
  <span m="3675720">a</span> <span m="3675760">variety</span> <span m="3676140">of</span>
  <span m="3676240">things</span> <span m="3676500">we</span> <span m="3676640">can</span>
  <span m="3676840">choose,</span> <span m="3677440">but</span> <span m="3677690">there''s</span>
  <span m="3678050">a</span> <span m="3678080">very</span> <span m="3678440">special</span>
  <span m="3680830">choice</span> <span m="3681280">that</span> <span m="3681610">results</span>
  <span m="3682190">in</span> <span m="3682280">what''s</span> <span m="3682570">called</span>
  <span m="3683050">a</span> <span m="3683180">Galerkin</span> <span m="3684930">method.</span>
  <span m="3688340">What</span> <span m="3688430">does</span> <span m="3688520">the</span>
  <span m="3688590">Galerkin</span> <span m="3689020">method</span> <span m="3689840">say</span>
  <span m="3690240">to</span> <span m="3690340">do</span> <span m="3690610">for</span>
  <span m="3690860">the</span> <span m="3690960">weighting</span> <span m="3691230">functions?</span>
  <span m="3691730">You guys</span> <span m="3692230">read</span> <span m="3692730">about
  this.</span></p><p><span m="3695230">AUDIENCE: [INAUDIBLE].</span></p><p><span m="3698030">PROFESSOR:
  Yeah.</span> <span m="3698720">Exactly</span> <span m="3699160">right.</span> <span
  m="3699770">Let</span> <span m="3699980">the</span> <span m="3700050">weighting</span>
  <span m="3700460">function</span> <span m="3701540">be</span> <span m="3701760">the</span>
  <span m="3701840">same</span> <span m="3702580">basis</span> <span m="3702970">function</span>
  <span m="3703710">that</span> <span m="3703840">you''re</span> <span m="3703970">using</span>
  <span m="3704350">to</span> <span m="3704440">approximate</span> <span m="3704930">the</span>
  <span m="3705010">solution.</span> <span m="3706444">OK?</span> <span m="3707250">So
  the</span> <span m="3707390">same</span> <span m="3707820">[INAUDIBLE],</span> <span
  m="3710660">that</span> <span m="3710820">we</span> <span m="3711000">used--</span>
  <span m="3711460">we''ve</span> <span m="3711680">erased</span> <span m="3711950">it</span>
  <span m="3712080">now--</span> <span m="3712400">but that</span> <span m="3712540">we</span>
  <span m="3712670">used</span> <span m="3712950">in</span> <span m="3713030">our</span>
  <span m="3713190">in our expansion</span> <span m="3713710">of</span> <span m="3713820">t
  tilde--</span> <span m="3714930">choose</span> <span m="3715220">the</span> <span
  m="3715310">same</span> <span m="3715870">basis</span> <span m="3716270">function</span>
  <span m="3717560">to</span> <span m="3717670">be</span> <span m="3717830">the</span>
  <span m="3717930">weighting</span> <span m="3718320">functions</span> <span m="3718830">that</span>
  <span m="3718960">you</span> <span m="3719090">use</span> <span m="3720170">to</span>
  <span m="3720280">define</span> <span m="3720590">your</span> <span m="3720680">weighted</span>
  <span m="3720960">residuals.</span></p><p><span m="3723100">Turns</span> <span m="3723220">out</span>
  <span m="3723290">don''t</span> <span m="3723540">have</span> <span m="3723810">to</span>
  <span m="3723930">do</span> <span m="3724090">that.</span> <span m="3724420">There''s</span>
  <span m="3725570">a</span> <span m="3725600">bunch</span> <span m="3725810">of</span>
  <span m="3725920">other</span> <span m="3726530">methods.</span> <span m="3727250">If</span>
  <span m="3727410">[INAUDIBLE]</span> <span m="3727550">Galerkin</span> <span m="3727630">methods,</span>
  <span m="3728180">we</span> <span m="3728320">can</span> <span m="3728490">choose</span>
  <span m="3728810">different</span> <span m="3729240">weighting</span> <span m="3729490">functions.</span>
  <span m="3730100">But</span> <span m="3730220">we''re</span> <span m="3730420">only</span>
  <span m="3730590">in</span> <span m="3730680">this</span> <span m="3730800">class</span>
  <span m="3731100">going</span> <span m="3731230">to</span> <span m="3731300">consider</span>
  <span m="3731660">Galerkin</span> <span m="3732250">methods</span> <span m="3733150">where</span>
  <span m="3733310">you</span> <span m="3733450">choose</span> <span m="3733870">the</span>
  <span m="3733960">weighting</span> <span m="3734350">functions</span> <span m="3734980">to</span>
  <span m="3735080">be</span> <span m="3735220">the</span> <span m="3735310">same</span>
  <span m="3735850">basis</span> <span m="3736170">functions</span> <span m="3736820">that</span>
  <span m="3736970">we''re</span> <span m="3737070">using</span> <span m="3737420">to</span>
  <span m="3737530">approximate</span> <span m="3738110">the</span> <span m="3738190">solution.</span></p><p><span
  m="3739918">So the Galerkin</span> <span m="3740350">method</span> <span m="3740870">is</span>
  <span m="3741230">a</span> <span m="3741270">very</span> <span m="3741590">special</span>
  <span m="3741980">choice</span> <span m="3742390">that</span> <span m="3742880">says</span>
  <span m="3743150">choose</span> <span m="3746530">wj</span> <span m="3750010">to</span>
  <span m="3750120">be</span> <span m="3750220">equal</span> <span m="3750490">to</span>
  <span m="3750580">[? cj. ?]</span> <span m="3752460">And</span> <span m="3752590">it</span>
  <span m="3752660">turns</span> <span m="3752910">out</span> <span m="3753030">that</span>
  <span m="3753130">this</span> <span m="3753360">choice</span> <span m="3753860">has</span>
  <span m="3755610">really</span> <span m="3755860">good</span> <span m="3756030">properties</span>
  <span m="3757760">for</span> <span m="3757980">some</span> <span m="3758935">PDEs.</span>
  <span m="3760360">And</span> <span m="3760490">again,</span> <span m="3760700">if</span>
  <span m="3760790">you</span> <span m="3760870">take</span> <span m="3761030">[?
  16920 ?]</span> <span m="3761890">with</span> <span m="3762470">Professor</span>
  <span m="3762510">[? Wong ?]</span> <span m="3762760">in</span> <span m="3762860">the</span>
  <span m="3762920">fall,</span> <span m="3763240">you</span> <span m="3763390">would</span>
  <span m="3763630">see</span> <span m="3764630">how</span> <span m="3764990">this</span>
  <span m="3765200">plays</span> <span m="3765450">out</span> <span m="3765650">from</span>
  <span m="3765800">an</span> <span m="3765910">energy</span> <span m="3766970">perspective.</span></p><p><span
  m="3768600">OK.</span> <span m="3768860">So</span> <span m="3768970">this</span>
  <span m="3769170">just</span> <span m="3769330">means</span> <span m="3769650">the</span>
  <span m="3769730">same</span> <span m="3770000">functions</span> <span m="3770450">that
  you</span> <span m="3770550">use</span> <span m="3770740">to</span> <span m="3770830">approximate</span>
  <span m="3771440">the</span> <span m="3771500">solution,</span> <span m="3772380">they''re
  going</span> <span m="3772520">to</span> <span m="3772590">be</span> <span m="3772770">used</span>
  <span m="3773220">to</span> <span m="3773470">weight</span> <span m="3773920">the</span>
  <span m="3774110">residuals.</span></p><p><span m="3776980">OK.</span> <span m="3777330">So</span>
  <span m="3777510">for</span> <span m="3777710">our</span> <span m="3777930">example,</span>
  <span m="3778740">what</span> <span m="3778860">does</span> <span m="3778950">that</span>
  <span m="3779140">mean?</span> <span m="3780490">That</span> <span m="3780620">means--</span>
  <span m="3781000">coming</span> <span m="3781250">back</span> <span m="3781460">to</span>
  <span m="3781550">what</span> <span m="3781700">we</span> <span m="3781800">were</span>
  <span m="3781880">doing</span> <span m="3782130">before--</span> <span m="3784330">that</span>
  <span m="3784540">means</span> <span m="3785010">that</span> <span m="3785510">the</span>
  <span m="3785590">first</span> <span m="3785970">weighting</span> <span m="3786300">function</span>
  <span m="3787250">would</span> <span m="3787480">be</span> <span m="3787740">our
  c1,</span> <span m="3788850">which</span> <span m="3789090">was</span> <span m="3789340">1
  minus x,</span> <span m="3790130">1</span> <span m="3790430">plus x.</span> <span
  m="3792090">And</span> <span m="3792540">the</span> <span m="3792600">second</span>
  <span m="3794500">weighting</span> <span m="3794860">function</span> <span m="3795410">would</span>
  <span m="3795590">be</span> <span m="3795740">the</span> <span m="3795840">cubic,</span>
  <span m="3796310">which</span> <span m="3796490">is</span> <span m="3797150">x times</span>
  <span m="3797530">all of that.</span> <span m="3801630">And</span> <span m="3801820">then</span>
  <span m="3803680">the</span> <span m="3803780">first</span> <span m="3804280">weighted</span>
  <span m="3804580">residual,</span> <span m="3805380">1,</span> <span m="3806250">which</span>
  <span m="3806450">is</span> <span m="3806540">a</span> <span m="3806590">function</span>
  <span m="3807020">of</span> <span m="3807260">t tilde,</span> <span m="3808600">would</span>
  <span m="3808840">be</span> <span m="3809290">the</span> <span m="3809430">integral</span>
  <span m="3809610">from</span> <span m="3810160">minus</span> <span m="3810520">1</span>
  <span m="3810790">to</span> <span m="3810960">1</span> <span m="3811530">of</span>
  <span m="3812540">w1</span> <span m="3812650">of x</span> <span m="3814490">times</span>
  <span m="3815948">r</span> <span m="3816920">of</span> <span m="3817410">t,</span>
  <span m="3817990">xdx.</span></p><p><span m="3823070">And</span> <span m="3823980">the</span>
  <span m="3824050">second</span> <span m="3824420">weighted</span> <span m="3824750">residual</span>
  <span m="3827260">would</span> <span m="3827490">be</span> <span m="3829450">the</span>
  <span m="3829540">second</span> <span m="3830180">weighting</span> <span m="3830550">function</span>
  <span m="3832150">multiplied</span> <span m="3834600">by</span> <span m="3835100">the</span>
  <span m="3835220">residual</span> <span m="3835920">integrated</span> <span m="3837570">over
  x</span> <span m="3838070">from</span> <span m="3838300">minus</span> <span m="3838590">1</span>
  <span m="3838830">to</span> <span m="3838980">1.</span></p><p><span m="3843170">OK.</span>
  <span m="3843430">I</span> <span m="3843460">don''t</span> <span m="3843590">want</span>
  <span m="3843710">to</span> <span m="3843800">work</span> <span m="3844050">through</span>
  <span m="3844320">all</span> <span m="3844560">the</span> <span m="3844640">math</span>
  <span m="3844930">on</span> <span m="3845030">the</span> <span m="3845110">board.</span>
  <span m="3845520">But</span> <span m="3845780">basically</span> <span m="3846230">you</span>
  <span m="3846300">can</span> <span m="3846430">see</span> <span m="3846550">what''s</span>
  <span m="3846730">going</span> <span m="3846850">to</span> <span m="3846910">happen</span>
  <span m="3847230">here,</span> <span m="3847430">right?</span> <span m="3847670">We''re</span>
  <span m="3847770">going</span> <span m="3847900">to</span> <span m="3847990">substitute</span>
  <span m="3848180">in</span> <span m="3848260">w1</span> <span m="3849300">as</span>
  <span m="3849950">1 minus</span> <span m="3850245">x,</span> <span m="3850540">1</span>
  <span m="3850700">plus x.</span> <span m="3851810">We</span> <span m="3851940">have</span>
  <span m="3852140">the</span> <span m="3852250">expression</span> <span m="3853260">for</span>
  <span m="3853340">this</span> <span m="3853430">guy</span> <span m="3853710">that</span>
  <span m="3853840">we</span> <span m="3853960">derived</span> <span m="3854320">before</span>
  <span m="3854950">that</span> <span m="3855300">was</span> <span m="3856210">minus</span>
  <span m="3856660">2a1</span> <span m="3857790">minus</span> <span m="3858140">6a2x</span>
  <span m="3858710">plus</span> <span m="3859120">50</span> <span m="3859500">e to
  the x.</span> <span m="3861250">So</span> <span m="3861410">now</span> <span m="3861720">at</span>
  <span m="3861830">that</span> <span m="3862000">point</span> <span m="3862350">it''s</span>
  <span m="3862530">just</span> <span m="3863370">multiplying</span> <span m="3863880">things</span>
  <span m="3864140">together</span> <span m="3864470">and</span> <span m="3864560">integrating.</span>
  <span m="3866340">And</span> <span m="3866580">you</span> <span m="3866640">could</span>
  <span m="3866770">do</span> <span m="3866920">it</span> <span m="3867010">all</span>
  <span m="3867160">by</span> <span m="3867360">hand</span> <span m="3867730">for</span>
  <span m="3867860">this</span> <span m="3867980">example,</span> <span m="3868250">or</span>
  <span m="3868520">you</span> <span m="3868810">could</span> <span m="3869100">again</span>
  <span m="3869360">throw it into</span> <span m="3869550">[? Mathematica ?]</span>
  <span m="3870100">or</span> <span m="3870240">something</span> <span m="3870520">and</span>
  <span m="3870800">get</span> <span m="3870960">it</span> <span m="3871070">out.</span></p><p><span
  m="3872200">And</span> <span m="3872410">then</span> <span m="3873532">what are
  we going</span> <span m="3873994">to do?</span> <span m="3874920">We''re</span>
  <span m="3875040">going</span> <span m="3875470">to</span> <span m="3875680">set</span>
  <span m="3877680">our</span> <span m="3878120">1</span> <span m="3880200">equal</span>
  <span m="3880520">to</span> <span m="3880590">0,</span> <span m="3881070">and we''re</span>
  <span m="3881250">going</span> <span m="3881380">to</span> <span m="3881460">set</span>
  <span m="3882080">our 2</span> <span m="3884090">equal</span> <span m="3884380">to</span>
  <span m="3884440">0.</span> <span m="3884860">It''s</span> <span m="3885000">going</span>
  <span m="3885130">to</span> <span m="3885220">give</span> <span m="3885370">us</span>
  <span m="3885600">two</span> <span m="3885850">conditions,</span> <span m="3887020">two</span>
  <span m="3887250">unknowns.</span> <span m="3888620">Solve</span> <span m="3889030">those.</span>
  <span m="3889600">And</span> <span m="3889730">we''re</span> <span m="3889810">going</span>
  <span m="3889980">to</span> <span m="3890040">come</span> <span m="3890270">out</span>
  <span m="3890750">with,</span> <span m="3892350">in this</span> <span m="3892680">case,</span>
  <span m="3892970">a</span> <span m="3893050">solution</span> <span m="3893510">that</span>
  <span m="3893670">says</span> <span m="3894050">a1</span> <span m="3894180">is 27.6</span>
  <span m="3896420">and</span> <span m="3896868">a2</span> <span m="3897764">is</span>
  <span m="3898660">8.9.</span></p><p><span m="3902760">OK,</span> <span m="3903000">so</span>
  <span m="3903120">I</span> <span m="3903240">skipped</span> <span m="3903450">over</span>
  <span m="3903560">a</span> <span m="3903590">lot</span> <span m="3903780">of</span>
  <span m="3904230">messy</span> <span m="3904590">math there,</span> <span m="3904950">but
  I don''t</span> <span m="3905240">think</span> <span m="3905530">there''s</span>
  <span m="3905710">anything</span> <span m="3906660">conceptually</span> <span m="3907070">difficult.</span>
  <span m="3909480">Two</span> <span m="3911340">conditions</span> <span m="3911930">now</span>
  <span m="3912170">coming</span> <span m="3912560">from</span> <span m="3913320">setting</span>
  <span m="3913620">a</span> <span m="3913680">weighted</span> <span m="3914020">residuals</span>
  <span m="3914720">equal to 0,</span> <span m="3916200">where</span> <span m="3916380">the</span>
  <span m="3916420">weighted</span> <span m="3916720">residuals</span> <span m="3917220">correspond</span>
  <span m="3917950">to</span> <span m="3918050">taking</span> <span m="3918280">the</span>
  <span m="3918360">residual,</span> <span m="3919030">multiplying</span> <span m="3919580">it</span>
  <span m="3919680">by</span> <span m="3919810">the</span> <span m="3919900">basis</span>
  <span m="3920280">function,</span> <span m="3921330">the Galerkin,</span> <span
  m="3922550">integrating</span> <span m="3922890">over</span> <span m="3923050">the</span>
  <span m="3923120">domain.</span> <span m="3925630">Plugging</span> <span m="3925920">through</span>
  <span m="3926050">all</span> <span m="3926150">the</span> <span m="3926220">math,</span>
  <span m="3927140">solving</span> <span m="3927390">the</span> <span m="3927530">equation,</span>
  <span m="3928270">gets</span> <span m="3928550">us</span> <span m="3928730">this</span>
  <span m="3928850">solution</span> <span m="3929540">which</span> <span m="3929760">says</span>
  <span m="3930080">that</span> <span m="3930350">by</span> <span m="3930510">the</span>
  <span m="3930610">method</span> <span m="3930980">of</span> <span m="3931070">weighted</span>
  <span m="3931430">residuals</span> <span m="3932980">for</span> <span m="3933110">this</span>
  <span m="3933560">choice</span> <span m="3933990">of</span> <span m="3934110">the</span>
  <span m="3934190">basis</span> <span m="3934560">function--</span> <span m="3936430">the
  cubic</span> <span m="3937150">and the</span> <span m="3937600">quadtratic--</span>
  <span m="3938050">in</span> <span m="3938140">a</span> <span m="3938400">Galerkin</span>
  <span m="3938840">method</span> <span m="3940130">the</span> <span m="3940270">solution</span>
  <span m="3940650">we</span> <span m="3940770">get</span> <span m="3941260">is--</span>
  <span m="3942710">the</span> <span m="3942810">approximate</span> <span m="3943180">solution</span>
  <span m="3943550">is</span> <span m="3943660">100</span> <span m="3944121">plus</span>
  <span m="3944582">27.6</span> <span m="3947350">amount</span> <span m="3947830">of
  our</span> <span m="3948490">quadratic</span> <span m="3949000">basis</span> <span
  m="3949330">function,</span> <span m="3950500">plus</span> <span m="3950930">8.9</span>
  <span m="3951770">amount</span> <span m="3952190">of</span> <span m="3952680">our</span>
  <span m="3953020">cubic basis</span> <span m="3953220">function.</span></p><p><span
  m="3955350">So</span> <span m="3955490">the</span> <span m="3955570">different</span>
  <span m="3955980">solution</span> <span m="3956740">to</span> <span m="3956890">what</span>
  <span m="3957110">we</span> <span m="3957260">got</span> <span m="3957830">with</span>
  <span m="3958990">collocation,</span> <span m="3959600">right?</span> <span m="3961240">We</span>
  <span m="3961680">got to it through</span> <span m="3961810">a</span> <span m="3961840">different</span>
  <span m="3962790">route.</span></p><p><span m="3966385">So I''ll</span> <span m="3966850">follow
  it</span> <span m="3967170">up,</span> <span m="3967330">and</span> <span m="3967430">we</span>
  <span m="3967520">can</span> <span m="3967670">look</span> <span m="3967860">at</span>
  <span m="3967950">that</span> <span m="3968150">solution</span> <span m="3968650">and</span>
  <span m="3968740">we</span> <span m="3968860">can</span> <span m="3969010">compare</span>
  <span m="3970128">it</span> <span m="3972940">to</span> <span m="3973090">a</span>
  <span m="3973130">collocation,</span> <span m="3973700">but first,</span> <span
  m="3974120">questions</span> <span m="3974570">about</span> <span m="3974900">method
  weighted</span> <span m="3975530">residuals.</span> <span m="3976760">Does that</span>
  <span m="3976900">make</span> <span m="3977080">sense?</span></p><p><span m="3979054">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="3994190">PROFESSOR: Yeah.</span> <span m="3994610">So
  that''s</span> <span m="3994850">a</span> <span m="3994910">good--</span> <span
  m="3995250">that''s</span> <span m="3995510">a</span> <span m="3995570">good</span>
  <span m="3995770">question.</span> <span m="3998070">The</span> <span m="3998310">answer</span>
  <span m="3998580">is</span> <span m="3998680">going</span> <span m="3998800">to</span>
  <span m="3998880">be,</span> <span m="3999000">it''s</span> <span m="3999110">going</span>
  <span m="3999230">to</span> <span m="3999500">depend</span> <span m="3999860">on</span>
  <span m="3999960">the</span> <span m="4000090">problem.</span> <span m="4001425">So
  there''s</span> <span m="4002760">no</span> <span m="4003650">general</span> <span
  m="4004270">guidelines</span> <span m="4004770">that I can give you.</span></p><p><span
  m="4007120">[AUDIO OUT]</span> <span m="4008860">you''re</span> <span m="4009010">[INAUDIBLE]</span>
  <span m="4009310">exactly</span> <span m="4009700">right</span> <span m="4009950">is</span>
  <span m="4010120">that,</span> <span m="4010490">because</span> <span m="4011425">the--</span>
  <span m="4011920">what</span> <span m="4012070">came</span> <span m="4012260">out</span>
  <span m="4012350">of</span> <span m="4012410">the</span> <span m="4012470">collocation</span>
  <span m="4012960">method,</span> <span m="4013230">and we''ll see it</span> <span
  m="4013550">in a second--</span> <span m="4014030">the</span> <span m="4014120">residual</span>
  <span m="4014530">was--</span> <span m="4015340">I forget</span> <span m="4015460">whether</span>
  <span m="4015530">it</span> <span m="4015630">was</span> <span m="4015950">positive</span>
  <span m="4016280">or</span> <span m="4016350">negative</span> <span m="4016710">everywhere,</span>
  <span m="4017120">but it always</span> <span m="4017430">had</span> <span m="4017570">one</span>
  <span m="4017840">sign.</span> <span m="4018540">And</span> <span m="4018670">we''re</span>
  <span m="4018740">going</span> <span m="4018860">to</span> <span m="4018940">see</span>
  <span m="4019170">that</span> <span m="4019290">the</span> <span m="4019360">method</span>
  <span m="4019640">of</span> <span m="4019730">weighted</span> <span m="4020030">residuals</span>
  <span m="4020966">actually</span> <span m="4021434">kind</span> <span m="4021902">of</span>
  <span m="4022370">balances</span> <span m="4022500">out.</span> <span m="4022790">Now
  that''s</span> <span m="4023150">going</span> <span m="4023270">to</span> <span
  m="4023340">make</span> <span m="4023560">sense,</span> <span m="4023910">because</span>
  <span m="4024170">what</span> <span m="4024330">are</span> <span m="4024380">we</span>
  <span m="4024520">doing</span> <span m="4025070">when</span> <span m="4025436">we--</span>
  <span m="4025802">when</span> <span m="4026170">we</span> <span m="4026290">take</span>
  <span m="4026510">the</span> <span m="4026600">residual,</span> <span m="4028330">and</span>
  <span m="4028540">we</span> <span m="4028660">weight</span> <span m="4028935">it,</span>
  <span m="4029210">and</span> <span m="4029400">then</span> <span m="4029520">we</span>
  <span m="4029630">integrated</span> <span m="4029970">it.</span> <span m="4030830">I</span>
  <span m="4031030">think</span> <span m="4031320">of this</span> <span m="4031680">as</span>
  <span m="4032560">kind</span> <span m="4032940">of</span> <span m="4033020">like--</span>
  <span m="4033190">it''s kind of like we''re</span> <span m="4033270">asking</span>
  <span m="4033690">the</span> <span m="4033790">residual</span> <span m="4034440">to</span>
  <span m="4034590">be</span> <span m="4034750">0</span> <span m="4035060">on</span>
  <span m="4035390">average</span> <span m="4036530">over</span> <span m="4036780">the</span>
  <span m="4036860">domain,</span> <span m="4038190">but</span> <span m="4039020">on</span>
  <span m="4039210">average</span> <span m="4039650">weighted</span> <span m="4040690">by</span>
  <span m="4041150">w1.</span> <span m="4042100">Right?</span> <span m="4043760">Because</span>
  <span m="4046300">if this were</span> <span m="4047236">gone</span> <span m="4047704">and</span>
  <span m="4048172">I just</span> <span m="4048640">integrated</span> <span m="4049108">it
  and set it</span> <span m="4049576">equal to 0, it would be like saying</span> <span
  m="4050530">[INAUDIBLE]</span> <span m="4050710">the residual</span> <span m="4050995">on
  average</span> <span m="4051662">0 over the</span> <span m="4052044">domain.</span>
  <span m="4052426">So it''s</span> <span m="4052970">like</span> <span m="4053040">taking</span>
  <span m="4053300">an</span> <span m="4053440">average,</span> <span m="4053810">but</span>
  <span m="4054420">weighting</span> <span m="4054890">it by w1.</span></p><p><span
  m="4055830">So yeah,</span> <span m="4056040">I''m</span> <span m="4056290">going</span>
  <span m="4056420">to</span> <span m="4056680">expect</span> <span m="4057300">this</span>
  <span m="4057580">to</span> <span m="4057690">come</span> <span m="4057980">out</span>
  <span m="4058200">with</span> <span m="4058370">something</span> <span m="4058800">that''s</span>
  <span m="4058990">going</span> <span m="4059110">to</span> <span m="4059180">be</span>
  <span m="4059420">more</span> <span m="4059700">evenly</span> <span m="4060040">distributed,</span>
  <span m="4060720">rather</span> <span m="4060850">than</span> <span m="4060990">with</span>
  <span m="4061140">collocation</span> <span m="4061944">where</span> <span m="4062346">had</span>
  <span m="4062748">all of one sign.</span> <span m="4063150">But</span> <span m="4063290">there''s</span>
  <span m="4063450">not--</span> <span m="4063720">I</span> <span m="4063790">mean</span>
  <span m="4063910">you</span> <span m="4063970">want</span> <span m="4064090">to</span>
  <span m="4064150">be</span> <span m="4064270">careful</span> <span m="4064700">about--</span>
  <span m="4067670">I</span> <span m="4067750">think</span> <span m="4067900">you</span>
  <span m="4067970">want to</span> <span m="4068080">be</span> <span m="4068170">careful</span>
  <span m="4068480">because</span> <span m="4068680">it''s</span> <span m="4068790">going</span>
  <span m="4068910">to</span> <span m="4068970">depend</span> <span m="4069320">on</span>
  <span m="4069780">the</span> <span m="4069870">problem.</span></p><p><span m="4070740">You''ll</span>
  <span m="4070890">see</span> <span m="4071110">when</span> <span m="4071250">I</span>
  <span m="4071300">[INAUDIBLE]</span> <span m="4071820">in</span> <span m="4072010">a</span>
  <span m="4072090">second</span> <span m="4072510">that</span> <span m="4072770">it
  actually</span> <span m="4072990">turns</span> <span m="4073220">out</span> <span
  m="4073350">our</span> <span m="4073510">residual</span> <span m="4074490">will</span>
  <span m="4074830">be</span> <span m="4075426">0</span> <span m="4077090">at</span>
  <span m="4077270">a</span> <span m="4077330">particular</span> <span m="4077770">point</span>
  <span m="4078030">x.</span> <span m="4078430">Not</span> <span m="4078640">because</span>
  <span m="4078880">we</span> <span m="4078970">set</span> <span m="4079170">it</span>
  <span m="4079260">that</span> <span m="4079410">way,</span> <span m="4079690">but</span>
  <span m="4079730">because</span> <span m="4080000">that''s how it</span> <span m="4080290">comes</span>
  <span m="4080540">out.</span> <span m="4080880">So</span> <span m="4081010">another</span>
  <span m="4081260">[INAUDIBLE]</span> <span m="4081610">check</span> <span m="4081920">would</span>
  <span m="4082040">be</span> <span m="4082120">to</span> <span m="4082190">go</span>
  <span m="4082330">back</span> <span m="4082640">and</span> <span m="4082750">plug</span>
  <span m="4082970">that</span> <span m="4083210">point</span> <span m="4083470">in
  and</span> <span m="4083690">make</span> <span m="4083890">sure</span> <span m="4084120">that</span>
  <span m="4084230">the</span> <span m="4084310">residual--</span> <span m="4084800">actually</span>
  <span m="4084920">worried</span> <span m="4085100">about</span> <span m="4085310">getting
  the integration</span> <span m="4086120">wrong.</span> <span m="4087310">Take</span>
  <span m="4087540">that</span> <span m="4087690">point,</span> <span m="4087940">x,</span>
  <span m="4088390">plug</span> <span m="4088650">it</span> <span m="4088730">in,</span>
  <span m="4088890">and</span> <span m="4089000">make</span> <span m="4089170">sure</span>
  <span m="4089340">that</span> <span m="4089570">indeed</span> <span m="4090420">the</span>
  <span m="4090640">0</span> <span m="4090700">is</span> <span m="4090850">satisfied.</span></p><p><span
  m="4094236">But</span> <span m="4095170">I</span> <span m="4095470">said</span>
  <span m="4095960">earlier</span> <span m="4096050">we</span> <span m="4096149">don''t</span>
  <span m="4096410">really</span> <span m="4096620">use</span> <span m="4097270">the</span>
  <span m="4097340">collocation</span> <span m="4097920">method,</span> <span m="4098260">but</span>
  <span m="4098380">we</span> <span m="4098460">do</span> <span m="4098560">use</span>
  <span m="4098689">method</span> <span m="4098960">of</span> <span m="4099040">weighted</span>
  <span m="4099290">residuals,</span> <span m="4099840">that</span> <span m="4099990">it''s</span>
  <span m="4100160">going</span> <span m="4100380">to</span> <span m="4100439">be,</span>
  <span m="4100590">because</span> <span m="4100790">it</span> <span m="4100859">actually
  turns</span> <span m="4101229">out to</span> <span m="4101430">have</span> <span
  m="4101580">really</span> <span m="4101770">great</span> <span m="4102010">properties.</span>
  <span m="4103260">It</span> <span m="4103430">wins</span> <span m="4103729">for</span>
  <span m="4103890">this</span> <span m="4104100">problem,</span> <span m="4104700">and</span>
  <span m="4104710">that''s</span> <span m="4104960">not</span> <span m="4105660">really</span>
  <span m="4107620">a</span> <span m="4107649">coincidence.</span> <span m="4108439">And</span>
  <span m="4108729">in</span> <span m="4108800">fact</span> <span m="4109050">it</span>
  <span m="4109210">forms</span> <span m="4110240">the</span> <span m="4110370">basis</span>
  <span m="4110760">of</span> <span m="4110880">what</span> <span m="4111069">we''re</span>
  <span m="4111170">going</span> <span m="4111290">to</span> <span m="4111359">do</span>
  <span m="4111490">with</span> <span m="4111700">the</span> <span m="4111740">finite</span>
  <span m="4111990">element</span> <span m="4112380">method,</span> <span m="4112830">which</span>
  <span m="4112960">is</span> <span m="4113060">incredibly</span> <span m="4113490">powerful.</span></p><p><span
  m="4119939">OK.</span> <span m="4120270">So</span> <span m="4120439">I</span> <span
  m="4120569">am</span> <span m="4120810">going</span> <span m="4120930">to</span>
  <span m="4121029">run</span> <span m="4121250">the</span> <span m="4121359">same</span>
  <span m="4121950">script</span> <span m="4122470">that</span> <span m="4122609">I</span>
  <span m="4122700">ran</span> <span m="4123069">before.</span> <span m="4125013">But</span>
  <span m="4125500">now</span> <span m="4125770">I</span> <span m="4126069">also</span>
  <span m="4126430">have</span> <span m="4127180">the</span> <span m="4127899">implementation</span>
  <span m="4128760">of</span> <span m="4129170">the</span> <span m="4129560">weighted</span>
  <span m="4129979">residual</span> <span m="4130939">method.</span></p><p><span m="4131930">So</span>
  <span m="4135932">here</span> <span m="4136396">are--</span> <span m="4137788">so</span>
  <span m="4138260">this</span> <span m="4138550">is</span> <span m="4138640">basically,</span>
  <span m="4139250">this</span> <span m="4139450">is</span> <span m="4140420">the</span>
  <span m="4140450">combination</span> <span m="4141100">of</span> <span m="4141420">all</span>
  <span m="4141620">those</span> <span m="4141840">integrals</span> <span m="4142290">over
  there--</span> <span m="4142540">amounts</span> <span m="4143069">of</span> <span
  m="4143180">the</span> <span m="4143279">[INAUDIBLE]</span> <span m="4143790">matrix--</span>
  <span m="4144770">this</span> <span m="4144990">k here,</span> <span m="4145590">this
  matrix,</span> <span m="4146790">and the</span> <span m="4146859">coefficients</span>
  <span m="4147510">being</span> <span m="4147790">[INAUDIBLE]</span> <span m="4149319">times</span>
  <span m="4149640">b.</span> <span m="4150420">So all the</span> <span m="4150630">integrations</span>
  <span m="4151180">amount</span> <span m="4151420">to that.</span></p><p><span m="4152175">And
  so</span> <span m="4152550">we''re</span> <span m="4152620">going</span> <span m="4152740">to</span>
  <span m="4152890">run</span> <span m="4153120">it</span> <span m="4153350">and</span>
  <span m="4153660">plot.</span> <span m="4155022">So</span> <span m="4155479">let</span>
  <span m="4155660">me--</span> <span m="4157540">clear</span> <span m="4157920">all,
  close all--</span></p><p><span m="4166422">OK.</span> <span m="4166819">So just</span>
  <span m="4167050">like</span> <span m="4167300">we</span> <span m="4167430">looked</span>
  <span m="4167660">at</span> <span m="4167810">before,</span> <span m="4168450">we</span>
  <span m="4168490">can</span> <span m="4168770">look</span> <span m="4169359">at</span>
  <span m="4169470">the</span> <span m="4171540">temperature</span> <span m="4173270">as</span>
  <span m="4173410">a</span> <span m="4173460">function</span> <span m="4173779">of</span>
  <span m="4173880">x.</span> <span m="4175649">Solid</span> <span m="4175970">lines,</span>
  <span m="4176250">just like before,</span> <span m="4176810">is the</span> <span
  m="4176939">exact</span> <span m="4177240">solution.</span> <span m="4178490">Dash</span>
  <span m="4178750">line</span> <span m="4179060">is</span> <span m="4179319">the</span>
  <span m="4179560">method</span> <span m="4179850">of</span> <span m="4179930">weighted</span>
  <span m="4180149">residual</span> <span m="4180500">solutions.</span></p><p><span
  m="4180990">So remember,</span> <span m="4181200">we''ve got</span> <span m="4181310">the</span>
  <span m="4181370">same</span> <span m="4181600">degrees</span> <span m="4181890">of</span>
  <span m="4181960">freedom</span> <span m="4182260">as</span> <span m="4182359">we</span>
  <span m="4182470">had</span> <span m="4182790">for</span> <span m="4182960">collocation,</span>
  <span m="4183590">right?</span> <span m="4183840">Still</span> <span m="4184160">any
  two</span> <span m="4184300">degrees</span> <span m="4184609">of</span> <span m="4184680">freedom.</span>
  <span m="4186090">And</span> <span m="4186770">our</span> <span m="4186970">same</span>
  <span m="4187370">basis</span> <span m="4187729">functions.</span> <span m="4188350">The</span>
  <span m="4188439">only</span> <span m="4188580">thing</span> <span m="4188729">we''ve</span>
  <span m="4188880">changed</span> <span m="4189229">is</span> <span m="4189340">the</span>
  <span m="4189420">way</span> <span m="4189660">we</span> <span m="4190390">choose</span>
  <span m="4190660">how</span> <span m="4190870">much</span> <span m="4191220">of</span>
  <span m="4191310">each</span> <span m="4191510">basis</span> <span m="4191830">function</span>
  <span m="4192270">to</span> <span m="4192390">put</span> <span m="4192569">in.</span>
  <span m="4193680">And</span> <span m="4194820">you</span> <span m="4194900">can</span>
  <span m="4195020">kind</span> <span m="4195180">of</span> <span m="4195290">see</span>
  <span m="4195630">visually--</span> <span m="4195920">I''ll put them</span> <span
  m="4196030">both</span> <span m="4196370">up together--</span> <span m="4196700">you
  can see visually</span> <span m="4197030">it</span> <span m="4197360">does</span>
  <span m="4197620">pretty</span> <span m="4197780">well.</span> <span m="4198010">And</span>
  <span m="4198100">actually</span> <span m="4198250">what</span> <span m="4198480">Kevin</span>
  <span m="4198670">was</span> <span m="4198800">just</span> <span m="4198970">observing,</span>
  <span m="4199910">it''s</span> <span m="4200130">not</span> <span m="4200500">always</span>
  <span m="4201020">under.</span> <span m="4201410">It</span> <span m="4201500">actually</span>
  <span m="4201750">is</span> <span m="4201890">under</span> <span m="4202230">a</span>
  <span m="4202270">little</span> <span m="4202470">bit</span> <span m="4202630">here,</span>
  <span m="4203030">and</span> <span m="4203230">over</span> <span m="4203470">a</span>
  <span m="4203510">little</span> <span m="4203710">bit</span> <span m="4203910">there,</span>
  <span m="4204250">and</span> <span m="4204420">in</span> <span m="4204710">under</span>
  <span m="4204950">a</span> <span m="4205010">little</span> <span m="4205220">bit</span>
  <span m="4205450">here.</span> <span m="4206190">It''s kind of just</span> <span
  m="4207090">the</span> <span m="4207170">way</span> <span m="4207720">it</span>
  <span m="4207970">came</span> <span m="4208230">out</span> <span m="4208470">for</span>
  <span m="4208570">this</span> <span m="4209680">problem.</span></p><p><span m="4211650">So</span>
  <span m="4211790">there''s</span> <span m="4211880">the</span> <span m="4212480">temperature</span>
  <span m="4212920">compared</span> <span m="4213220">to</span> <span m="4213290">the</span>
  <span m="4213390">exact</span> <span m="4213890">solution.</span> <span m="4215140">We</span>
  <span m="4215300">can</span> <span m="4215710">look</span> <span m="4215910">at</span>
  <span m="4216060">the</span> <span m="4216300">error</span> <span m="4218050">as</span>
  <span m="4218180">a</span> <span m="4218230">function</span> <span m="4218490">of</span>
  <span m="4218590">x</span> <span m="4218750">again</span> <span m="4218980">because</span>
  <span m="4219250">we</span> <span m="4219350">have</span> <span m="4219540">the</span>
  <span m="4219680">exact</span> <span m="4219950">solution</span> <span m="4220290">here.</span>
  <span m="4220510">And</span> <span m="4220600">again</span> <span m="4220870">we</span>
  <span m="4220960">can</span> <span m="4221130">see</span> <span m="4221290">it''s</span>
  <span m="4221920">negative,</span> <span m="4222400">then</span> <span m="4222490">it''s</span>
  <span m="4222650">positive,</span> <span m="4223170">then it''s</span> <span m="4223490">negative.</span>
  <span m="4226560">And</span> <span m="4227890">we</span> <span m="4228240">can</span>
  <span m="4228650">look</span> <span m="4228940">at</span> <span m="4229440">the</span>
  <span m="4230030">residual.</span></p><p><span m="4232250">And</span> <span m="4232410">so</span>
  <span m="4232520">now,</span> <span m="4232790">remember</span> <span m="4233080">with</span>
  <span m="4233250">collocation,</span> <span m="4233870">what</span> <span m="4233990">did</span>
  <span m="4234080">we</span> <span m="4234210">see?</span> <span m="4234440">We</span>
  <span m="4234560">saw</span> <span m="4234820">with</span> <span m="4235030">the</span>
  <span m="4235090">collocation</span> <span m="4235700">method</span> <span m="4236000">that</span>
  <span m="4236110">the</span> <span m="4236180">residual</span> <span m="4236680">was</span>
  <span m="4236950">0</span> <span m="4237540">at</span> <span m="4237760">the</span>
  <span m="4237820">collocation</span> <span m="4238450">point,</span> <span m="4238820">because</span>
  <span m="4239060">those</span> <span m="4239320">were</span> <span m="4239450">the</span>
  <span m="4240170">conditions</span> <span m="4240660">that</span> <span m="4240780">we</span>
  <span m="4240900">imposed</span> <span m="4241620">to</span> <span m="4241690">get</span>
  <span m="4241840">the</span> <span m="4241900">coefficient.</span></p><p><span m="4243340">Here</span>
  <span m="4243665">it turns</span> <span m="4243990">out</span> <span m="4244140">that</span>
  <span m="4244230">the</span> <span m="4244340">residual</span> <span m="4244890">is</span>
  <span m="4245120">0</span> <span m="4246950">minus</span> <span m="4247310">0.4</span>
  <span m="4248510">and</span> <span m="4249325">at</span> <span m="4249650">plus
  0.5.</span> <span m="4250800">But</span> <span m="4250830">that</span> <span m="4250950">just</span>
  <span m="4251120">kind</span> <span m="4251310">of</span> <span m="4251390">fell</span>
  <span m="4251680">out.</span> <span m="4252390">And</span> <span m="4252530">again,</span>
  <span m="4252750">if</span> <span m="4252860">you''re</span> <span m="4252960">looking</span>
  <span m="4253280">for</span> <span m="4253470">check</span> <span m="4253820">to</span>
  <span m="4253900">make</span> <span m="4254080">sure</span> <span m="4254260">you</span>
  <span m="4254350">did</span> <span m="4254540">the</span> <span m="4254630">integrations</span>
  <span m="4255230">right,</span> <span m="4255500">you</span> <span m="4255570">can</span>
  <span m="4255740">always</span> <span m="4256590">take</span> <span m="4256820">your</span>
  <span m="4257000">residual,</span> <span m="4258400">substitute</span> <span m="4258880">in</span>
  <span m="4259040">whatever</span> <span m="4259290">these</span> <span m="4259480">values</span>
  <span m="4259840">are,</span> <span m="4260060">and</span> <span m="4260150">make</span>
  <span m="4260300">it</span> <span m="4260620">came out</span> <span m="4261020">to
  0.</span> <span m="4262060">But</span> <span m="4262170">again,</span> <span m="4262370">that</span>
  <span m="4262510">just</span> <span m="4262700">fell</span> <span m="4262960">out.</span>
  <span m="4263350">What</span> <span m="4263550">we</span> <span m="4263680">actually</span>
  <span m="4264110">ask</span> <span m="4264480">for</span> <span m="4264880">was</span>
  <span m="4265130">that this</span> <span m="4265560">residual,</span> <span m="4266800">when</span>
  <span m="4267710">weighted</span> <span m="4268460">by</span> <span m="4269190">this</span>
  <span m="4269360">guy</span> <span m="4270060">and</span> <span m="4270180">an</span>
  <span m="4270380">integrator</span> <span m="4271050">over the</span> <span m="4271120">domain,</span>
  <span m="4271750">is</span> <span m="4271920">0.</span> <span m="4273160">And</span>
  <span m="4273780">this</span> <span m="4274090">residual,</span> <span m="4274810">when</span>
  <span m="4275050">weighted</span> <span m="4275380">by</span> <span m="4275580">this</span>
  <span m="4275790">guy--</span> <span m="4276243">the cubic--</span> <span m="4277150">an
  integrator</span> <span m="4277430">of the</span> <span m="4277970">domain--</span>
  <span m="4278230">that</span> <span m="4278660">is</span> <span m="4278850">0.</span></p><p><span
  m="4286090">And</span> <span m="4286360">so</span> <span m="4286810">then</span>
  <span m="4288670">finally--</span> <span m="4292430">let''s see--</span> <span m="4294880">plot</span>
  <span m="4295370">the</span> <span m="4295460">comparisons.</span> <span m="4296820">So
  I</span> <span m="4296930">put</span> <span m="4297090">them</span> <span m="4297210">all
  on</span> <span m="4297480">the</span> <span m="4297570">same</span> <span m="4297995">plot.</span>
  <span m="4301790">So</span> <span m="4302290">there</span> <span m="4302780">in</span>
  <span m="4303320">black</span> <span m="4303620">is</span> <span m="4303730">the</span>
  <span m="4303810">exact</span> <span m="4304150">solution.</span> <span m="4305040">The</span>
  <span m="4305160">red</span> <span m="4305410">is</span> <span m="4305590">the</span>
  <span m="4305690">method</span> <span m="4305990">of</span> <span m="4306060">weighted</span>
  <span m="4306320">residuals.</span> <span m="4307040">The</span> <span m="4307140">blue
  is</span> <span m="4307470">collocation.</span></p><p><span m="4308910">Turns</span>
  <span m="4309030">out</span> <span m="4309190">method</span> <span m="4309340">of</span>
  <span m="4309500">weighted</span> <span m="4309550">residuals</span> <span m="4309710">did</span>
  <span m="4310130">better</span> <span m="4310550">for</span> <span m="4310650">this</span>
  <span m="4310840">problem,</span> <span m="4311200">but</span> <span m="4311290">again</span>
  <span m="4311760">we want</span> <span m="4311990">to</span> <span m="4312050">be</span>
  <span m="4312110">careful</span> <span m="4312410">about</span> <span m="4312690">making</span>
  <span m="4313000">general</span> <span m="4316270">assumptions.</span> <span m="4316650">They</span>
  <span m="4316740">both</span> <span m="4316910">have</span> <span m="4317020">the</span>
  <span m="4317090">same</span> <span m="4317350">number</span> <span m="4317590">of</span>
  <span m="4317660">degrees</span> <span m="4318010">of</span> <span m="4318100">freedom.</span>
  <span m="4318490">They</span> <span m="4318620">only</span> <span m="4318840">differ</span>
  <span m="4319140">in</span> <span m="4319260">the</span> <span m="4319330">choice</span>
  <span m="4319640">of</span> <span m="4319720">those</span> <span m="4319950">coefficients.</span></p><p><span
  m="4322960">Here''s</span> <span m="4323350">a</span> <span m="4323410">plot</span>
  <span m="4323710">of</span> <span m="4323800">the</span> <span m="4323890">difference</span>
  <span m="4324310">errors.</span> <span m="4328280">And</span> <span m="4328420">again,</span>
  <span m="4328720">I</span> <span m="4328760">would</span> <span m="4328930">say</span>
  <span m="4329270">the</span> <span m="4329350">method</span> <span m="4329770">of
  weighted individuals</span> <span m="4329890">is</span> <span m="4330050">kind of</span>
  <span m="4330320">more</span> <span m="4330520">balanced,</span> <span m="4331710">again,</span>
  <span m="4332050">because</span> <span m="4332340">we</span> <span m="4332460">are</span>
  <span m="4332870">asking</span> <span m="4333320">for</span> <span m="4333440">this</span>
  <span m="4334370">weighted</span> <span m="4334870">residual</span> <span m="4336520">to</span>
  <span m="4336650">be</span> <span m="4336850">zero.</span> <span m="4338440">And</span>
  <span m="4338730">then</span> <span m="4338900">lastly,</span> <span m="4339780">here</span>
  <span m="4340060">are</span> <span m="4340190">the plots</span> <span m="4340810">of</span>
  <span m="4341080">the</span> <span m="4341210">residuals</span> <span m="4343220">as</span>
  <span m="4343510">a</span> <span m="4343570">function</span> <span m="4344210">of</span>
  <span m="4344830">x.</span> <span m="4345210">And</span> <span m="4345310">now</span>
  <span m="4345500">you</span> <span m="4345600">can</span> <span m="4345720">see</span>
  <span m="4345840">clearly</span> <span m="4346080">what</span> <span m="4346210">I</span>
  <span m="4346250">was</span> <span m="4346460">saying.</span> <span m="4346890">There''s</span>
  <span m="4347060">the</span> <span m="4347130">collocation</span> <span m="4349480">[INAUDIBLE]</span>
  <span m="4349875">to 0</span> <span m="4350270">at the collation point.</span> <span
  m="4351450">The</span> <span m="4351540">method</span> <span m="4351770">of</span>
  <span m="4351850">weighted</span> <span m="4352100">residuals</span> <span m="4352590">happens</span>
  <span m="4353040">to</span> <span m="4353120">be</span> <span m="4353320">0</span>
  <span m="4353710">at</span> <span m="4353790">a</span> <span m="4353820">couple</span>
  <span m="4354090">of</span> <span m="4354170">other</span> <span m="4354340">points.</span></p><p><span
  m="4358180">OK?</span> <span m="4361150">More</span> <span m="4361370">questions.</span></p><p><span
  m="4365310">I''d say it''s</span> <span m="4365760">really</span> <span m="4366050">important</span>
  <span m="4366470">that</span> <span m="4366610">you</span> <span m="4366700">feel</span>
  <span m="4366910">very</span> <span m="4367090">comfortable</span> <span m="4367570">with</span>
  <span m="4367730">the</span> <span m="4367790">method</span> <span m="4368040">of
  weighted</span> <span m="4368410">residuals.</span> <span m="4370130">The</span>
  <span m="4370270">idea--</span> <span m="4370720">and</span> <span m="4371020">let
  me</span> <span m="4371250">just</span> <span m="4371440">say</span> <span m="4371710">it</span>
  <span m="4371800">again,</span> <span m="4372050">the</span> <span m="4372150">idea</span>
  <span m="4372410">that</span> <span m="4372560">we''re</span> <span m="4372680">going</span>
  <span m="4373120">to</span> <span m="4373780">take</span> <span m="4374030">the</span>
  <span m="4374070">PDE--</span> <span m="4375490">we''re</span> <span m="4375590">not</span>
  <span m="4375770">going</span> <span m="4375890">to</span> <span m="4375950">mess</span>
  <span m="4376160">around</span> <span m="4376370">with</span> <span m="4376480">the</span>
  <span m="4376550">derivatives,</span> <span m="4377060">we''re</span> <span m="4377130">going</span>
  <span m="4377260">to</span> <span m="4377370">instead</span> <span m="4377770">say,</span>
  <span m="4378080">let''s</span> <span m="4378270">approximate</span> <span m="4378860">the</span>
  <span m="4378930">solution</span> <span m="4380600">and</span> <span m="4380750">an</span>
  <span m="4380840">expansion</span> <span m="4381490">with</span> <span m="4381620">a</span>
  <span m="4381660">finite</span> <span m="4382030">number</span> <span m="4382240">of</span>
  <span m="4382330">basis</span> <span m="4382660">function.</span> <span m="4384180">We''re</span>
  <span m="4384290">going</span> <span m="4384420">to</span> <span m="4384500">choose</span>
  <span m="4384950">the</span> <span m="4385050">form</span> <span m="4385380">of</span>
  <span m="4385450">the</span> <span m="4385520">basis</span> <span m="4385880">functions--</span>
  <span m="4386600">and</span> <span m="4387150">they were even</span> <span m="4387390">talking</span>
  <span m="4387620">about</span> <span m="4387810">polynomial</span> <span m="4388350">basis</span>
  <span m="4388700">function.</span></p><p><span m="4390280">Now</span> <span m="4390440">we</span>
  <span m="4390520">need</span> <span m="4390650">to</span> <span m="4390710">figure</span>
  <span m="4391020">out</span> <span m="4391200">a</span> <span m="4391250">way</span>
  <span m="4391680">to</span> <span m="4392470">determine</span> <span m="4392820">the</span>
  <span m="4392880">coefficients--</span> <span m="4393770">how</span> <span m="4393950">much</span>
  <span m="4394280">of</span> <span m="4394360">each</span> <span m="4394560">basis</span>
  <span m="4394870">function.</span> <span m="4396060">And so</span> <span m="4396280">the</span>
  <span m="4396370">way</span> <span m="4396530">we''re</span> <span m="4396630">going</span>
  <span m="4396750">to</span> <span m="4396820">do</span> <span m="4397010">that</span>
  <span m="4397420">is</span> <span m="4398060">choose</span> <span m="4398380">weighting</span>
  <span m="4398750">functions,</span> <span m="4399480">and</span> <span m="4399630">with</span>
  <span m="4399770">Galerkin</span> <span m="4400045">methods</span> <span m="4400320">we''ll</span>
  <span m="4401080">choose</span> <span m="4401370">those</span> <span m="4401560">weighting</span>
  <span m="4401830">functions</span> <span m="4402280">to</span> <span m="4402380">be</span>
  <span m="4402490">the</span> <span m="4402580">same</span> <span m="4403090">basis</span>
  <span m="4403460">function</span> <span m="4404360">that</span> <span m="4404520">we''re</span>
  <span m="4404610">approximating</span> <span m="4405170">the</span> <span m="4405240">solution</span>
  <span m="4405740">with.</span> <span m="4406690">We''ll weight</span> <span m="4407350">the
  residual</span> <span m="4408510">with</span> <span m="4408700">the</span> <span
  m="4408790">weighting</span> <span m="4409090">function,</span> <span m="4409500">integrate
  it</span> <span m="4410000">over</span> <span m="4410190">the</span> <span m="4410270">domain,</span>
  <span m="4411330">define</span> <span m="4411800">the</span> <span m="4411870">weighted</span>
  <span m="4412190">residuals,</span> <span m="4413270">set those equal to 0,</span>
  <span m="4414440">and get</span> <span m="4414640">the</span> <span m="4414700">conditions</span>
  <span m="4415240">we</span> <span m="4415350">need</span> <span m="4416230">to</span>
  <span m="4416290">find</span> <span m="4416470">the</span> <span m="4416540">coefficients</span>
  <span m="4417320">on</span> <span m="4417480">our</span> <span m="4417610">expansion.</span>
  <span m="4420210">All those sets.</span></p><p><span m="4421340">And</span> <span
  m="4421480">what</span> <span m="4421610">we''ve</span> <span m="4421810">done</span>
  <span m="4422330">today</span> <span m="4423020">is</span> <span m="4424420">define</span>
  <span m="4425400">global</span> <span m="4425870">basis</span> <span m="4426200">functions,</span>
  <span m="4426515">right?</span> <span m="4427150">So</span> <span m="4427330">my</span>
  <span m="4427760">c1</span> <span m="4428420">was</span> <span m="4428610">a</span>
  <span m="4428660">quadratic</span> <span m="4429250">that varied</span> <span m="4429660">over</span>
  <span m="4429820">the whole</span> <span m="4430170">domain,</span> <span m="4430630">and</span>
  <span m="4430820">my</span> <span m="4430950">c2</span> <span m="4431170">was a
  cubic</span> <span m="4431600">that</span> <span m="4431730">varied</span> <span
  m="4432035">over</span> <span m="4432340">the whole</span> <span m="4432410">domain.</span></p><p><span
  m="4433360">Finite</span> <span m="4433510">element</span> <span m="4433630">method--</span>
  <span m="4434450">you''re</span> <span m="4434670">all ready</span> <span m="4435010">for</span>
  <span m="4435190">it</span> <span m="4435260">now--</span> <span m="4435905">is
  just a,</span> <span m="4436330">I</span> <span m="4436440">guess</span> <span m="4436590">kind</span>
  <span m="4436780">of</span> <span m="4436870">a</span> <span m="4436930">simple,</span>
  <span m="4437440">but</span> <span m="4437690">really</span> <span m="4437960">pretty</span>
  <span m="4439590">huge</span> <span m="4440090">next</span> <span m="4440350">step,</span>
  <span m="4440670">which</span> <span m="4440730">is</span> <span m="4440860">to</span>
  <span m="4440950">say,</span> <span m="4441630">let''s</span> <span m="4441820">not</span>
  <span m="4442010">do</span> <span m="4442130">this</span> <span m="4442300">on</span>
  <span m="4442390">the</span> <span m="4442470">whole</span> <span m="4442640">domain,</span>
  <span m="4443060">let''s</span> <span m="4443270">divide</span> <span m="4443610">domain</span>
  <span m="4444120">up</span> <span m="4444260">into</span> <span m="4444410">little</span>
  <span m="4444630">pieces,</span> <span m="4445780">and</span> <span m="4445920">let''s</span>
  <span m="4446140">use</span> <span m="4446330">this</span> <span m="4446510">idea.</span>
  <span m="4446770">Let''s</span> <span m="4447130">define</span> <span m="4447630">basis</span>
  <span m="4447960">functions--</span> <span m="4448510">special</span> <span m="4448780">basis</span>
  <span m="4449080">functions</span> <span m="4449530">that</span> <span m="4449650">are</span>
  <span m="4449700">polynomials</span> <span m="4450560">just</span> <span m="4450840">on</span>
  <span m="4450970">the</span> <span m="4451020">little</span> <span m="4451240">pieces.</span>
  <span m="4453640">And</span> <span m="4453830">then we''re</span> <span m="4453890">going</span>
  <span m="4454010">to</span> <span m="4454080">have</span> <span m="4454220">coefficients</span>
  <span m="4454720">that go with those.</span></p><p><span m="4456220">Yeah,</span>
  <span m="4456720">[? Tran? ?]</span></p><p><span m="4458720">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="4461840">PROFESSOR: Yeah.</span> <span m="4462110">So that''s</span> <span m="4462340">a</span>
  <span m="4462380">good--</span> <span m="4462620">[INAUDIBLE]</span> <span m="4463200">In
  that</span> <span m="4463450">case,</span> <span m="4463700">the</span> <span m="4463780">weighted</span>
  <span m="4463930">residual--</span> <span m="4464090">we''re</span> <span m="4464270">going</span>
  <span m="4464610">to</span> <span m="4464730">see</span> <span m="4465110">all that</span>
  <span m="4465410">on</span> <span m="4465970">Wednesday.</span></p><p><span m="4467450">So</span>
  <span m="4467570">what''s</span> <span m="4467760">going</span> <span m="4467880">to</span>
  <span m="4467960">happen</span> <span m="4468260">now</span> <span m="4468800">is</span>
  <span m="4469080">that</span> <span m="4470470">this</span> <span m="4470570">weighted</span>
  <span m="4470940">residual</span> <span m="4471090">is</span> <span m="4471260">actually</span>
  <span m="4471460">going</span> <span m="4471580">to</span> <span m="4471640">have</span>
  <span m="4471740">very</span> <span m="4471960">special</span> <span m="4472340">structure,</span>
  <span m="4473630">because</span> <span m="4473920">the</span> <span m="4474020">way</span>
  <span m="4474260">we''re</span> <span m="4474350">going</span> <span m="4474470">to</span>
  <span m="4474530">define</span> <span m="4474860">the</span> <span m="4474930">basis</span>
  <span m="4475260">functions</span> <span m="4476010">is</span> <span m="4476170">that
  they''re going</span> <span m="4476300">to</span> <span m="4476370">be</span> <span
  m="4476500">local</span> <span m="4477130">on</span> <span m="4477420">elements--</span>
  <span m="4478700">the</span> <span m="4478810">finite</span> <span m="4479150">elements</span>
  <span m="4479640">of</span> <span m="4479720">the</span> <span m="4479880">finite</span>
  <span m="4480340">element</span> <span m="4480700">method.</span> <span m="4482160">And</span>
  <span m="4482300">so</span> <span m="4482400">when</span> <span m="4482560">we</span>
  <span m="4482670">do</span> <span m="4482800">the</span> <span m="4482920">integration,</span>
  <span m="4483760">a</span> <span m="4483800">whole</span> <span m="4483970">bunch</span>
  <span m="4484230">of</span> <span m="4484300">it''s</span> <span m="4484540">going</span>
  <span m="4484950">to</span> <span m="4485370">disappear,</span> <span m="4485860">and</span>
  <span m="4485950">we''re</span> <span m="4486010">going</span> <span m="4486140">to</span>
  <span m="4486200">be</span> <span m="4486280">integrating</span> <span m="4486850">locally</span>
  <span m="4488070">just</span> <span m="4488410">over</span> <span m="4488650">the</span>
  <span m="4488770">elements.</span> <span m="4489370">But</span> <span m="4489510">what</span>
  <span m="4489630">you''re</span> <span m="4489710">going</span> <span m="4489820">to</span>
  <span m="4489920">see</span> <span m="4490150">is</span> <span m="4490320">that</span>
  <span m="4490570">there</span> <span m="4490730">ends</span> <span m="4490990">up</span>
  <span m="4491150">being</span> <span m="4491600">a</span> <span m="4491650">little</span>
  <span m="4491840">bit</span> <span m="4491940">of</span> <span m="4492030">interaction</span>
  <span m="4493680">between</span> <span m="4494050">one</span> <span m="4494230">element</span>
  <span m="4494590">and</span> <span m="4494700">its</span> <span m="4494890">neighbors</span>
  <span m="4495530">because</span> <span m="4495810">of the</span> <span m="4496150">way</span>
  <span m="4496340">the</span> <span m="4496400">basic</span> <span m="4496670">functions</span>
  <span m="4497030">are going to</span> <span m="4497260">come</span> <span m="4497410">out.</span></p><p><span
  m="4498210">So</span> <span m="4498540">we''ll</span> <span m="4498800">work</span>
  <span m="4499120">through</span> <span m="4499220">all</span> <span m="4499400">those</span>
  <span m="4499660">integrals.</span> <span m="4500340">I</span> <span m="4500410">think</span>
  <span m="4500600">you</span> <span m="4500850">read</span> <span m="4501540">maybe</span>
  <span m="4501700">a</span> <span m="4501800">little</span> <span m="4502030">bit</span>
  <span m="4502190">of</span> <span m="4502290">it</span> <span m="4502530">already.</span>
  <span m="4505300">How far</span> <span m="4505410">did</span> <span m="4505540">you</span>
  <span m="4505610">guys</span> <span m="4505780">get</span> <span m="4505940">in</span>
  <span m="4506020">the</span> <span m="4506110">reading?</span> <span m="4507030">You</span>
  <span m="4507290">saw</span> <span m="4507490">the</span> <span m="4507800">linear,</span>
  <span m="4508320">[INAUDIBLE]?</span></p><p><span m="4511410">Yeah.</span> <span
  m="4512800">Yeah,</span> <span m="4513000">we''re</span> <span m="4513090">going</span>
  <span m="4513210">to</span> <span m="4513270">work</span> <span m="4513450">through</span>
  <span m="4513880">all</span> <span m="4514110">of</span> <span m="4514190">that.</span>
  <span m="4514400">And</span> <span m="4514510">you''ll</span> <span m="4514640">see</span>
  <span m="4514790">that''s</span> <span m="4515030">what''s</span> <span m="4515230">incredibly</span>
  <span m="4515880">powerful</span> <span m="4516310">with</span> <span m="4516440">the</span>
  <span m="4516510">finite</span> <span m="4516760">element</span> <span m="4517070">method,</span>
  <span m="4517360">is</span> <span m="4517460">this</span> <span m="4517630">idea</span>
  <span m="4518030">of</span> <span m="4518160">using</span> <span m="4518990">a</span>
  <span m="4519100">polynomial</span> <span m="4519710">basis</span> <span m="4520170">and</span>
  <span m="4520260">a</span> <span m="4520330">local</span> <span m="4520710">element,</span>
  <span m="4521500">we''re</span> <span m="4521590">going</span> <span m="4521710">to</span>
  <span m="4521780">get</span> <span m="4521910">these</span> <span m="4522020">integrals</span>
  <span m="4522580">with</span> <span m="4522780">so</span> <span m="4523120">much</span>
  <span m="4523350">structure</span> <span m="4524390">that</span> <span m="4524570">we</span>
  <span m="4525170">can</span> <span m="4525320">handle--</span> <span m="4525550">it''s</span>
  <span m="4526580">going to sort of</span> <span m="4526940">all</span> <span m="4527265">work
  out</span> <span m="4528040">in</span> <span m="4528150">a</span> <span m="4528220">really</span>
  <span m="4528430">neat</span> <span m="4528630">way.</span></p><p><span m="4529834">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="4534040">PROFESSOR: That''s</span> <span m="4534230">exactly</span>
  <span m="4534540">right.</span> <span m="4534740">We''re</span> <span m="4534800">still</span>
  <span m="4535050">integrating</span> <span m="4535470">a weighted</span> <span m="4535770">residual</span>
  <span m="4536490">over the</span> <span m="4536860">whole</span> <span m="4537050">domain,
  but</span> <span m="4537200">a whole</span> <span m="4537270">lot of it''s</span>
  <span m="4537420">going</span> <span m="4537550">to</span> <span m="4537620">go</span>
  <span m="4537830">away,</span> <span m="4538510">and</span> <span m="4538960">it''s</span>
  <span m="4539090">going</span> <span m="4539210">to</span> <span m="4539320">turn</span>
  <span m="4539540">out</span> <span m="4539840">that we get</span> <span m="4541340">sort</span>
  <span m="4541500">of these</span> <span m="4541640">special</span> <span m="4542020">patterns</span>
  <span m="4542790">that show up</span> <span m="4543070">because</span> <span m="4543340">of</span>
  <span m="4543400">the</span> <span m="4543460">way</span> <span m="4543600">which</span>
  <span m="4543790">is</span> <span m="4543920">a</span> <span m="4543960">basis</span>
  <span m="4544230">functions.</span> <span m="4544690">And you''ll</span> <span m="4544940">see
  all of</span> <span m="4545420">that.</span> <span m="4547056">We''ll do all of
  that.</span> <span m="4547520">I</span> <span m="4547680">think on</span> <span
  m="4547860">Wednesday</span> <span m="4548400">we''ll</span> <span m="4549300">sort</span>
  <span m="4549440">of</span> <span m="4549540">work</span> <span m="4549780">through</span>
  <span m="4550080">all the steps</span> <span m="4550150">of the</span> <span m="4550460">finite</span>
  <span m="4550945">element</span> <span m="4551430">method and</span> <span m="4551570">have</span>
  <span m="4551730">you</span> <span m="4551950">go along and do it,</span> <span
  m="4552722">so</span> <span m="4553110">actually</span> <span m="4553310">bring</span>
  <span m="4553530">your</span> <span m="4553710">laptops if you can so you can do</span>
  <span m="4554710">some stuff on Matlab.</span></p><p><span m="4557710">OK.</span>
  <span m="4558710">Yeah, Ben?</span></p><p><span m="4562140">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="4569493">PROFESSOR: You know, that''s a good question.</span></p><p><span m="4570942">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="4574810">PROFESSOR: That''s</span> <span m="4574990">a
  good</span> <span m="4575150">question.</span> <span m="4575510">The</span> <span
  m="4575610">question</span> <span m="4575760">is,</span> <span m="4576130">is the</span>
  <span m="4576490">fact</span> <span m="4576770">that</span> <span m="4577830">the</span>
  <span m="4577940">method</span> <span m="4578220">of</span> <span m="4578330">weighted</span>
  <span m="4578610">residuals,</span> <span m="4579340">the</span> <span m="4579430">resulting</span>
  <span m="4580330">residual</span> <span m="4580960">crosses</span> <span m="4581590">0</span>
  <span m="4582010">in</span> <span m="4582330">time,</span> <span m="4583606">is
  that</span> <span m="4584050">a</span> <span m="4584150">coincidence,</span> <span
  m="4584740">or</span> <span m="4584900">is</span> <span m="4584980">it</span> <span
  m="4585080">always</span> <span m="4585280">going</span> <span m="4585400">to</span>
  <span m="4585470">happen?</span></p><p><span m="4586560">I</span> <span m="4586870">think</span>
  <span m="4587930">that''s</span> <span m="4588100">a</span> <span m="4588140">very</span>
  <span m="4588340">interesting</span> <span m="4588640">question,</span> <span m="4588920">and
  I''m</span> <span m="4589200">actually</span> <span m="4589630">not</span> <span
  m="4589970">sure,</span> <span m="4590230">because</span> <span m="4590450">I</span>
  <span m="4591970">was</span> <span m="4592160">wondering</span> <span m="4592500">actually,</span>
  <span m="4592770">is</span> <span m="4592950">there</span> <span m="4593080">a</span>
  <span m="4593150">way</span> <span m="4593350">to</span> <span m="4593460">figure</span>
  <span m="4593730">out</span> <span m="4593930">where</span> <span m="4594060">we</span>
  <span m="4594160">could</span> <span m="4594330">have</span> <span m="4594820">put</span>
  <span m="4595010">the</span> <span m="4595080">collocation</span> <span m="4595670">points</span>
  <span m="4597140">for</span> <span m="4597340">this</span> <span m="4597590">problem.</span>
  <span m="4598030">We</span> <span m="4598130">could</span> <span m="4598240">have</span>
  <span m="4598330">put</span> <span m="4598450">the</span> <span m="4598520">collocation</span>
  <span m="4599130">points</span> <span m="4599780">in</span> <span m="4600250">a
  particular point</span> <span m="4601360">and</span> <span m="4601460">gotten the</span>
  <span m="4601560">same</span> <span m="4601750">answer</span> <span m="4602086">that
  we got</span> <span m="4602422">with</span> <span m="4602760">the method of weighted</span>
  <span m="4602990">residuals.</span> <span m="4604000">And it''s</span> <span m="4604170">going</span>
  <span m="4604290">to</span> <span m="4604350">have</span> <span m="4604470">something</span>
  <span m="4604750">to</span> <span m="4604840">do</span> <span m="4605030">with</span>
  <span m="4605250">the</span> <span m="4605330">50e</span> <span m="4605780">to the
  x</span> <span m="4606150">that''s</span> <span m="4606520">in</span> <span m="4606630">the</span>
  <span m="4606740">[INAUDIBLE]</span> <span m="4607120">function.</span> <span m="4607850">I</span>
  <span m="4608000">just think</span> <span m="4608330">the</span> <span m="4608410">fact</span>
  <span m="4608650">that</span> <span m="4608770">it</span> <span m="4608870">crosses</span>
  <span m="4609220">twice</span> <span m="4609540">is</span> <span m="4609660">not</span>
  <span m="4609850">a</span> <span m="4609890">coincidence.</span> <span m="4611820">I</span>
  <span m="4611920">think</span> <span m="4611960">it</span> <span m="4612040">probably</span>
  <span m="4612380">has</span> <span m="4612650">to</span> <span m="4612750">cross</span>
  <span m="4613800">twice,</span> <span m="4614660">but I don''t--</span></p><p><span
  m="4616100">AUDIENCE: [INAUDIBLE]</span></p><p><span m="4626200">PROFESSOR: You</span>
  <span m="4626300">feel</span> <span m="4626440">like</span> <span m="4626560">it''s</span>
  <span m="4626670">kind</span> <span m="4626810">of</span> <span m="4626870">like</span>
  <span m="4627010">a</span> <span m="4627060">fundamental</span> <span m="4627508">theorem?</span></p><p><span
  m="4628404">AUDIENCE: [INAUDIBLE]</span></p><p><span m="4630650">PROFESSOR: Maybe</span>
  <span m="4630870">it''s</span> <span m="4631090">a</span> <span m="4631150">great</span>
  <span m="4631760">question</span> <span m="4632190">for</span> <span m="4632300">the</span>
  <span m="4632390">final.</span> <span m="4635460">Really</span> <span m="4635720">good</span>
  <span m="4635910">final</span> <span m="4636150">questions</span> <span m="4636490">are</span>
  <span m="4636560">when</span> <span m="4636660">the</span> <span m="4636740">professors</span>
  <span m="4637160">don''t</span> <span m="4637330">know</span> <span m="4637460">the</span>
  <span m="4637570">answer</span> <span m="4637860">What</span> <span m="4638040">do</span>
  <span m="4638100">you</span> <span m="4638160">think,</span> <span m="4638660">[?
  Xixi.? ?]</span></p><p><span m="4639660">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="4652380">PROFESSOR: Yeah.</span> <span m="4652540">Well</span> <span m="4652650">the</span>
  <span m="4652720">thing</span> <span m="4652890">is,</span> <span m="4653000">we</span>
  <span m="4653110">have</span> <span m="4653240">an</span> <span m="4653320">expression</span>
  <span m="4653820">for</span> <span m="4653940">the</span> <span m="4654040">residual,</span>
  <span m="4654880">which</span> <span m="4655060">we</span> <span m="4655210">wrote</span>
  <span m="4655450">out,</span> <span m="4655820">which</span> <span m="4656130">was--</span>
  <span m="4657730">what''s</span> <span m="4657820">the</span> <span m="4657990">expression</span>
  <span m="4658480">for</span> <span m="4658830">our residuall--</span> <span m="4658980">it''s</span>
  <span m="4659330">minus</span> <span m="4659710">2a1</span> <span m="4660540">minus</span>
  <span m="4660810">6a2x</span> <span m="4661750">plus</span> <span m="4661950">50e</span>
  <span m="4662410">to the x.</span> <span m="4662870">So</span> <span m="4662970">I</span>
  <span m="4663040">guess</span> <span m="4663240">you</span> <span m="4663330">can</span>
  <span m="4663520">figure</span> <span m="4663790">out</span> <span m="4664150">how</span>
  <span m="4664290">many</span> <span m="4664710">crossings</span> <span m="4664920">are</span>
  <span m="4664970">possible</span> <span m="4666850">because</span> <span m="4667650">of</span>
  <span m="4667760">the</span> <span m="4667870">degrees</span> <span m="4668270">of</span>
  <span m="4668350">freedom</span> <span m="4668680">that</span> <span m="4668820">we</span>
  <span m="4668940">have.</span></p><p><span m="4672980">It</span> <span m="4673100">actually</span>
  <span m="4673300">turns</span> <span m="4673580">out</span> <span m="4673720">that</span>
  <span m="4673860">even</span> <span m="4674050">though</span> <span m="4674340">things
  seem</span> <span m="4674510">like</span> <span m="4674780">coincidences,</span>
  <span m="4675200">there</span> <span m="4675360">are almost</span> <span m="4675690">no</span>
  <span m="4675820">coincidences.</span> <span m="4676810">In</span> <span m="4676950">these</span>
  <span m="4677130">kinds</span> <span m="4677390">of</span> <span m="4677500">problems,</span>
  <span m="4677960">it''s</span> <span m="4678120">usually</span> <span m="4678340">that</span>
  <span m="4678500">there''s</span> <span m="4678640">so</span> <span m="4678770">much</span>
  <span m="4678960">structure</span> <span m="4679340">in</span> <span m="4679410">the</span>
  <span m="4679490">problem</span> <span m="4680212">that you could have--</span>
  <span m="4681820">but--</span> <span m="4683446">yeah.</span></p><p><span m="4685856">OK.</span>
  <span m="4686340">If</span> <span m="4686763">you have--</span> <span m="4687730">if
  there are</span> <span m="4687780">parts</span> <span m="4688070">of</span> <span
  m="4688150">the</span> <span m="4688240">method</span> <span m="4688510">of</span>
  <span m="4688590">weighted</span> <span m="4688840">residuals</span> <span m="4689370">that</span>
  <span m="4689510">are a little bi</span> <span m="4690040">uncomfortable</span>
  <span m="4690540">for</span> <span m="4690620">you,</span> <span m="4690800">I</span>
  <span m="4690900">would</span> <span m="4691290">strongly</span> <span m="4691760">suggest</span>
  <span m="4692090">you</span> <span m="4692170">talk</span> <span m="4692420">to</span>
  <span m="4692510">me,</span> <span m="4692750">or to Alex,</span> <span m="4693540">[?
  Xixi, ?]</span> <span m="4693750">or to</span> <span m="4694168">[? Bikram ?],</span>
  <span m="4695004">before Wednesday,</span> <span m="4695840">because</span> <span
  m="4695940">otherwise</span> <span m="4696190">things</span> <span m="4696390">are</span>
  <span m="4696420">going</span> <span m="4696540">to</span> <span m="4696610">get</span>
  <span m="4697140">dramatically</span> <span m="4697670">worse</span> <span m="4697820">for
  you on</span> <span m="4698230">Wednesday.</span> <span m="4698660">Make</span>
  <span m="4698810">sure</span> <span m="4698960">that</span> <span m="4699090">this--</span>
  <span m="4699960">really--</span> <span m="4700290">make</span> <span m="4700480">sure--</span>
  <span m="4700820">that''s</span> <span m="4701000">why</span> <span m="4701120">I</span>
  <span m="4701270">went kind of</span> <span m="4701490">slowly</span> <span m="4701840">through</span>
  <span m="4702010">this</span> <span m="4702170">lecture,</span> <span m="4702450">is</span>
  <span m="4702730">because</span> <span m="4702970">it''s</span> <span m="4703110">really</span>
  <span m="4703330">important</span> <span m="4703770">that</span> <span m="4703870">you</span>
  <span m="4703970">have</span> <span m="4704100">all</span> <span m="4704200">these</span>
  <span m="4704520">steps kind of</span> <span m="4704950">clear in your mind.</span></p><p><span
  m="4706240">And please</span> <span m="4706620">if</span> <span m="4706710">you</span>
  <span m="4706810">have</span> <span m="4706920">a</span> <span m="4706960">chance</span>
  <span m="4707380">to</span> <span m="4707540">even</span> <span m="4707990">just
  listen</span> <span m="4708320">to</span> <span m="4708440">a</span> <span m="4708480">few</span>
  <span m="4708660">minutes,</span> <span m="4709790">especially</span> <span m="4709820">those
  of you</span> <span m="4709930">who said you like</span> <span m="4710210">the</span>
  <span m="4710310">audio</span> <span m="4710880">recording--</span> <span m="4711980">if</span>
  <span m="4712410">the</span> <span m="4712450">combination</span> <span m="4713020">of</span>
  <span m="4713110">what''s</span> <span m="4713320">on</span> <span m="4713400">the</span>
  <span m="4713480">screen</span> <span m="4713860">and</span> <span m="4713990">me</span>
  <span m="4714120">talking</span> <span m="4714520">is</span> <span m="4714710">good</span>
  <span m="4714850">enough</span> <span m="4715110">then</span> <span m="4715270">I</span>
  <span m="4715320">can</span> <span m="4715480">keep</span> <span m="4715700">using</span>
  <span m="4715790">the</span> <span m="4715860">blackboard,</span> <span m="4715930">but
  if not please let me know.</span></p>'
type: course
uid: d043f5ddc59e8303ffe8b0fff282f32a

---
None