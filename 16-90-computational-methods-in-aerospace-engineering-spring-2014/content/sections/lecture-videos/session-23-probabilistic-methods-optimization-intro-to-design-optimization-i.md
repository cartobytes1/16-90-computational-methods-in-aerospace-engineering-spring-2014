---
about_this_resource_text: <p><strong>Description:</strong> This session discusses
  the basics of a design optimization problem, as well as design optimization algorithms,
  and computing gradients.</p> <p><strong>Instructor:</strong> Karen Willcox</p><p>The
  recording quality of this video is the best available from the source.</p>
course_id: 16-90-computational-methods-in-aerospace-engineering-spring-2014
embedded_media:
- id: Video-YouTube-Stream
  media_location: FAKkYN2k_uk
  parent_uid: 90a1ac4713f47de217c82b87fab8f1d1
  title: Video-YouTube-Stream
  type: Video
  uid: ff7b1bc28fa8bd4e77d9a71d3d65f184
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/FAKkYN2k_uk/default.jpg
  parent_uid: 90a1ac4713f47de217c82b87fab8f1d1
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: f68ebb6692ca2068ba7945b798577a78
- id: 3Play-3PlayYouTubeid-MP4
  media_location: FAKkYN2k_uk
  parent_uid: 90a1ac4713f47de217c82b87fab8f1d1
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 905cc73f2c2052c1156508ae6a3e9480
- id: FAKkYN2k_uk.srt
  parent_uid: 90a1ac4713f47de217c82b87fab8f1d1
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-23-probabilistic-methods-optimization-intro-to-design-optimization-i/FAKkYN2k_uk.srt
  title: 3play caption file
  type: null
  uid: 1bac7c701b337fce3abd9c937d98d664
- id: FAKkYN2k_uk.pdf
  parent_uid: 90a1ac4713f47de217c82b87fab8f1d1
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-23-probabilistic-methods-optimization-intro-to-design-optimization-i/FAKkYN2k_uk.pdf
  title: 3play pdf file
  type: null
  uid: c9c4058d2b74632ccede7f5b7ff2b13a
- id: Caption-3Play YouTube id-SRT
  parent_uid: 90a1ac4713f47de217c82b87fab8f1d1
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 643caaadb284ae562cc2a129ce0e5ae5
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 90a1ac4713f47de217c82b87fab8f1d1
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: ac7387a7c21e4962d3918dd40ae8518f
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT16.90S14/MIT16_90S14_L23_300k.mp4
  parent_uid: 90a1ac4713f47de217c82b87fab8f1d1
  title: Video-Internet Archive-MP4
  type: Video
  uid: b5b913c8c4fc39cc845e461eaf008b59
inline_embed_id: 89897077session23:probabilisticmethods&optimization:introtodesignoptimizationi83119127
layout: video
order_index: null
parent_uid: 809ebf7c44bfb36e8786306747d7e32f
related_resources_text: ''
short_url: session-23-probabilistic-methods-optimization-intro-to-design-optimization-i
technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-23-probabilistic-methods-optimization-intro-to-design-optimization-i
template_type: Tabbed
title: 'Session 23: Probabilistic Methods & Optimization: Intro to design optimization
  I'
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
  <span m="12050">materials</span> <span m="12670">from</span> <span m="12850">hundreds</span>
  <span m="13180">of</span> <span m="13280">MIT</span> <span m="13650">courses,</span>
  <span m="14950">visit</span> <span m="15150">MIT</span> <span m="15670">OpenCourseWare</span>
  <span m="16580">at</span> <span m="16770">ocw.mit.edu.</span></p><p><span m="31510">PROFESSOR:
  OK.</span> <span m="32840">We</span> <span m="32910">can</span> <span m="33050">go</span>
  <span m="33160">ahead</span> <span m="33290">and</span> <span m="33400">get</span>
  <span m="33570">started.</span> <span m="34600">So</span> <span m="35660">today</span>
  <span m="36000">is</span> <span m="36160">going</span> <span m="36300">to</span>
  <span m="36380">be</span> <span m="36550">the</span> <span m="36620">first</span>
  <span m="36890">lecture</span> <span m="37360">on</span> <span m="38590">an</span>
  <span m="38730">introduction</span> <span m="39230">to</span> <span m="39330">design</span>
  <span m="39750">optimization.</span> <span m="42080">You</span> <span m="42180">guys</span>
  <span m="42330">ready?</span> <span m="44086">Can</span> <span m="44570">you</span>
  <span m="44630">talk</span> <span m="44790">about</span> <span m="44950">the</span>
  <span m="45010">project?</span> <span m="46810">I have</span> <span m="47020">office</span>
  <span m="47220">hours</span> <span m="47420">right</span> <span m="47570">after</span>
  <span m="47790">this,</span> <span m="47880">so</span> <span m="48340">we</span>
  <span m="48800">can--</span></p><p><span m="50640">So</span> <span m="50850">here</span>
  <span m="51020">are</span> <span m="51080">three</span> <span m="51260">things</span>
  <span m="51490">I''m</span> <span m="51600">going to</span> <span m="51680">try</span>
  <span m="51830">to</span> <span m="51900">cover</span> <span m="52110">today.</span>
  <span m="52570">We''ll</span> <span m="52750">talk</span> <span m="52960">about</span>
  <span m="53330">the</span> <span m="53400">basics</span> <span m="53750">of</span>
  <span m="53810">the</span> <span m="53880">design</span> <span m="54190">optimization</span>
  <span m="54760">problem,</span> <span m="55170">how</span> <span m="55270">you</span>
  <span m="55780">take</span> <span m="56060">a</span> <span m="56270">design</span>
  <span m="56630">problem</span> <span m="56970">and</span> <span m="57100">set</span>
  <span m="57240">it</span> <span m="57320">up</span> <span m="57430">as</span> <span
  m="57550">an</span> <span m="57640">optimization</span> <span m="58320">problem.</span>
  <span m="59720">Well</span> <span m="60100">talk</span> <span m="60350">about</span>
  <span m="60930">unconstrained</span> <span m="61420">optimization</span> <span m="62010">methods</span>
  <span m="62510">and</span> <span m="62650">how</span> <span m="62820">to</span>
  <span m="62980">compute</span> <span m="63480">the</span> <span m="63560">gradients</span>
  <span m="64120">that</span> <span m="64280">we</span> <span m="64379">will</span>
  <span m="64519">need</span> <span m="64879">for</span> <span m="64989">those</span>
  <span m="65330">optimization</span> <span m="65870">methods.</span> <span m="66920">And</span>
  <span m="67850">then</span> <span m="68040">in</span> <span m="68150">the</span>
  <span m="68230">next</span> <span m="68600">lecture,</span> <span m="69800">we''ll</span>
  <span m="70500">talk</span> <span m="70750">a</span> <span m="70790">little</span>
  <span m="71000">more</span> <span m="71180">about</span> <span m="71900">some</span>
  <span m="72100">of</span> <span m="72200">the</span> <span m="72940">different</span>
  <span m="74350">methods.</span> <span m="75430">We''ll maybe</span> <span m="75690">talk</span>
  <span m="75860">about</span> <span m="76140">some</span> <span m="76640">responsiveness</span>
  <span m="77360">modeling,</span> <span m="77740">so</span> <span m="78640">surrogate</span>
  <span m="79140">models</span> <span m="80740">and</span> <span m="81592">see</span>
  <span m="81930">what</span> <span m="82070">else</span> <span m="82340">we</span>
  <span m="82490">have</span> <span m="82990">time</span> <span m="83910">for.</span></p><p><span
  m="85296">So</span> <span m="85760">this</span> <span m="85960">is</span> <span
  m="86290">intended</span> <span m="87160">to</span> <span m="87340">be</span> <span
  m="87460">a</span> <span m="87540">little</span> <span m="87770">bit</span> <span
  m="88250">of</span> <span m="88560">just</span> <span m="88720">kind</span> <span
  m="88870">of</span> <span m="88950">a</span> <span m="89000">teaser</span> <span
  m="90320">for</span> <span m="90860">optimization</span> <span m="91590">methods.</span>
  <span m="93350">This</span> <span m="93490">is</span> <span m="93570">something</span>
  <span m="93890">that</span> <span m="94020">I</span> <span m="94060">use</span>
  <span m="94290">a</span> <span m="94350">lot</span> <span m="94830">in</span> <span
  m="95060">my</span> <span m="95410">research.</span> <span m="97735">So</span> <span
  m="99600">let''s just</span> <span m="99870">start</span> <span m="100320">off</span>
  <span m="100730">with</span> <span m="100930">thinking</span> <span m="101240">about</span>
  <span m="102520">the</span> <span m="102630">basics</span> <span m="103300">of</span>
  <span m="103640">writing</span> <span m="103960">a</span> <span m="104030">design</span>
  <span m="104490">problem</span> <span m="106960">as</span> <span m="107230">an</span>
  <span m="107330">optimization</span> <span m="108110">statement.</span></p><p><span
  m="110560">So</span> <span m="112520">the</span> <span m="112700">idea</span> <span
  m="113050">is</span> <span m="113200">that</span> <span m="113550">a</span> <span
  m="113600">design</span> <span m="113960">problem,</span> <span m="115250">as I
  said</span> <span m="115585">already,</span> <span m="121610">can</span> <span m="121900">be</span>
  <span m="122100">written</span> <span m="124420">as</span> <span m="124820">an</span>
  <span m="124920">optimization</span> <span m="125600">problem.</span> <span m="129800">And</span>
  <span m="129979">the</span> <span m="130060">reason</span> <span m="130300">that</span>
  <span m="130419">we''re</span> <span m="130550">doing</span> <span m="130850">this</span>
  <span m="131110">is</span> <span m="131280">because</span> <span m="132700">then</span>
  <span m="132870">we''ll</span> <span m="133040">be</span> <span m="133160">able</span>
  <span m="133360">to</span> <span m="133480">use</span> <span m="133680">numerical</span>
  <span m="134130">optimization</span> <span m="134820">methods</span> <span m="135170">to</span>
  <span m="135270">explore</span> <span m="135600">the</span> <span m="135670">design</span>
  <span m="136010">space.</span> <span m="136310">So</span> <span m="136390">what</span>
  <span m="136490">we</span> <span m="136580">saw</span> <span m="136730">in</span>
  <span m="136820">the</span> <span m="136900">last</span> <span m="137180">lecture</span>
  <span m="137590">were</span> <span m="137870">the</span> <span m="137980">design</span>
  <span m="138250">of</span> <span m="138330">experiments,</span> <span m="138950">which</span>
  <span m="139090">were</span> <span m="139170">basically</span> <span m="139580">sampling</span>
  <span m="140860">methods.</span></p><p><span m="141550">But</span> <span m="141720">what</span>
  <span m="141870">we</span> <span m="141980">saw</span> <span m="142270">is</span>
  <span m="142420">that</span> <span m="142560">if</span> <span m="142750">you</span>
  <span m="142890">have</span> <span m="143040">a</span> <span m="143090">lot</span>
  <span m="143320">of</span> <span m="143740">design</span> <span m="144140">variables,</span>
  <span m="145540">it get''s</span> <span m="145880">hard</span> <span m="146120">to</span>
  <span m="146230">explore</span> <span m="146570">the</span> <span m="146640">design</span>
  <span m="146980">space</span> <span m="147370">very</span> <span m="147570">much.</span>
  <span m="147850">Because</span> <span m="148090">you</span> <span m="148160">can''t</span>
  <span m="148450">[INAUDIBLE]</span> <span m="148700">to</span> <span m="148960">maybe</span>
  <span m="149220">too</span> <span m="149370">many</span> <span m="150050">levels.</span>
  <span m="151400">So</span> <span m="152300">one</span> <span m="152390">thing</span>
  <span m="152830">we</span> <span m="152950">can</span> <span m="153070">do</span>
  <span m="153250">is</span> <span m="153400">try</span> <span m="153540">to</span>
  <span m="153620">write</span> <span m="153770">the</span> <span m="153810">design</span>
  <span m="154100">problem</span> <span m="154360">as</span> <span m="154470">an</span>
  <span m="154550">optimization</span> <span m="155220">problem.</span></p><p><span
  m="156190">And</span> <span m="156440">in</span> <span m="156560">doing</span> <span
  m="156830">that,</span> <span m="157170">we</span> <span m="157330">would</span>
  <span m="157640">define</span> <span m="159460">a</span> <span m="159600">few</span>
  <span m="160270">mathematical</span> <span m="160940">elements.</span> <span m="161510">So</span>
  <span m="162450">the</span> <span m="162560">first</span> <span m="162910">are</span>
  <span m="163480">what</span> <span m="163740">are</span> <span m="163810">called</span>
  <span m="164520">objectives</span> <span m="165310">or</span> <span m="165440">objective</span>
  <span m="165930">functions</span> <span m="166970">sometimes.</span> <span m="168230">And</span>
  <span m="168800">these</span> <span m="169170">are</span> <span m="171420">what</span>
  <span m="171720">we</span> <span m="171850">are</span> <span m="171890">trying</span>
  <span m="172190">to</span> <span m="172310">achieve,</span> <span m="178040">so</span>
  <span m="178500">measures of</span> <span m="178590">performance</span> <span m="179320">of
  the</span> <span m="179420">design.</span> <span m="179800">We''ll</span> <span
  m="179940">talk</span> <span m="180080">about</span> <span m="180300">some</span>
  <span m="180410">examples</span> <span m="180990">in</span> <span m="181120">a</span>
  <span m="181230">second.</span></p><p><span m="183160">We''re</span> <span m="183230">going</span>
  <span m="183350">to</span> <span m="183410">have</span> <span m="184070">constraints.</span>
  <span m="188050">And</span> <span m="188480">constraints</span> <span m="189200">are</span>
  <span m="189260">going</span> <span m="189620">to</span> <span m="189730">be</span>
  <span m="190840">things</span> <span m="191130">that</span> <span m="191270">we</span>
  <span m="191370">can''t</span> <span m="191680">violate,</span> <span m="192340">so</span>
  <span m="192460">requirements</span> <span m="193270">on</span> <span m="193400">the</span>
  <span m="193500">design</span> <span m="193940">are</span> <span m="194090">cannot</span>
  <span m="194330">be</span> <span m="194770">violated.</span> <span m="195420">So</span>
  <span m="195550">these</span> <span m="195730">are</span> <span m="195760">going</span>
  <span m="195880">to</span> <span m="195970">be</span> <span m="198740">what</span>
  <span m="199010">we</span> <span m="199480">cannot</span> <span m="199740">violate.</span></p><p><span
  m="205300">We</span> <span m="205540">will</span> <span m="205740">have</span> <span
  m="207660">design</span> <span m="208190">variables.</span> <span m="214040">And</span>
  <span m="214370">those</span> <span m="214650">are</span> <span m="214790">the</span>
  <span m="214870">quantities</span> <span m="215410">that</span> <span m="215560">we</span>
  <span m="215690">can</span> <span m="215860">change.</span> <span m="216470">Those</span>
  <span m="216690">are the</span> <span m="216780">things</span> <span m="217100">that</span>
  <span m="217230">as</span> <span m="217350">a</span> <span m="217400">designer</span>
  <span m="217820">we</span> <span m="217920">have</span> <span m="218080">to</span>
  <span m="218170">make</span> <span m="218380">decisions</span> <span m="218860">about.</span>
  <span m="219310">The</span> <span m="219410">design</span> <span m="219800">variable</span>
  <span m="221190">are</span> <span m="221370">what</span> <span m="221540">we</span>
  <span m="221640">can</span> <span m="221840">change,</span> <span m="225620">what</span>
  <span m="225720">we</span> <span m="225810">can</span> <span m="225960">change and</span>
  <span m="226320">what</span> <span m="226480">we</span> <span m="226570">can</span>
  <span m="226840">control.</span></p><p><span m="229400">And</span> <span m="230130">lastly,</span>
  <span m="230560">we''re</span> <span m="230670">going</span> <span m="230800">to</span>
  <span m="230870">have</span> <span m="231220">parameters.</span> <span m="236070">And</span>
  <span m="236220">the</span> <span m="236290">word</span> <span m="236480">parameters</span>
  <span m="237100">is</span> <span m="237240">used</span> <span m="237600">often</span>
  <span m="237920">in</span> <span m="238030">different</span> <span m="238330">contexts.</span>
  <span m="238920">Sometimes</span> <span m="239350">people</span> <span m="239910">use</span>
  <span m="240140">the</span> <span m="240210">word</span> <span m="240390">parameter</span>
  <span m="240810">when they</span> <span m="241100">mean</span> <span m="241230">design</span>
  <span m="241560">variable.</span> <span m="241940">The</span> <span m="242020">way</span>
  <span m="242170">that</span> <span m="242320">I''ll</span> <span m="242490">use</span>
  <span m="242750">it</span> <span m="243320">is</span> <span m="243460">that</span>
  <span m="243600">a</span> <span m="243640">parameter</span> <span m="244100">is</span>
  <span m="244220">going</span> <span m="244340">to</span> <span m="244410">be</span>
  <span m="244550">other</span> <span m="244740">quantities</span> <span m="245560">that</span>
  <span m="245890">are</span> <span m="247310">taking</span> <span m="247640">on</span>
  <span m="247790">fixed</span> <span m="248790">value.</span></p><p><span m="249110">So</span>
  <span m="249540">they''re</span> <span m="250400">other</span> <span m="250590">quantities</span>
  <span m="251160">that</span> <span m="251300">affect</span> <span m="251880">the</span>
  <span m="255060">objective</span> <span m="255480">and</span> <span m="255650">the</span>
  <span m="255740">constraints.</span> <span m="258290">But</span> <span m="258550">they''re</span>
  <span m="258649">going</span> <span m="258769">to</span> <span m="258850">take</span>
  <span m="259130">on</span> <span m="260589">fixed</span> <span m="260760">values.</span>
  <span m="265020">So</span> <span m="265110">they''re</span> <span m="265310">not</span>
  <span m="265470">going</span> <span m="265590">to</span> <span m="265660">be</span>
  <span m="265810">varying</span> <span m="267200">as</span> <span m="267440">we</span>
  <span m="267570">search</span> <span m="267880">the</span> <span m="267980">design</span>
  <span m="268390">space.</span></p><p><span m="273330">OK.</span> <span m="274320">That''s</span>
  <span m="274480">the</span> <span m="274610">four</span> <span m="275080">elements</span>
  <span m="275580">of</span> <span m="275650">the</span> <span m="275740">optimization</span>
  <span m="276350">problem,</span> <span m="276700">objective</span> <span m="277070">functions,</span>
  <span m="277680">constraints,</span> <span m="278280">design</span> <span m="278610">variables,</span>
  <span m="278950">and</span> <span m="279070">parameters.</span> <span m="279540">And</span>
  <span m="279650">I''m</span> <span m="279740">going</span> <span m="279860">to</span>
  <span m="279930">go</span> <span m="280080">through</span> <span m="280330">each</span>
  <span m="280630">of</span> <span m="280740">these.</span> <span m="281600">And</span>
  <span m="281790">we''ll</span> <span m="281930">define</span> <span m="282250">it</span>
  <span m="282350">mathematically</span> <span m="283090">and</span> <span m="283210">also</span>
  <span m="283650">think</span> <span m="283830">about</span> <span m="284090">what</span>
  <span m="284230">it</span> <span m="284330">might</span> <span m="284800">be</span>
  <span m="285680">in</span> <span m="285920">terms</span> <span m="286320">of</span>
  <span m="289550">physical</span> <span m="289940">examples.</span></p><p><span m="290906">So</span>
  <span m="291390">let''s</span> <span m="291510">start</span> <span m="291780">off</span>
  <span m="292020">thinking</span> <span m="292410">about</span> <span m="292830">design</span>
  <span m="293190">variables.</span> <span m="296640">So</span> <span m="296790">again,</span>
  <span m="297120">the</span> <span m="297200">design</span> <span m="297570">variables,</span>
  <span m="298220">these</span> <span m="298340">are</span> <span m="298390">the</span>
  <span m="299260">qualities</span> <span m="299890">or</span> <span m="300880">the</span>
  <span m="302690">attributes</span> <span m="303250">of</span> <span m="303360">the</span>
  <span m="303450">design</span> <span m="303980">that</span> <span m="304260">we</span>
  <span m="304490">have</span> <span m="304660">control</span> <span m="305030">over</span>
  <span m="305240">as a</span> <span m="305410">designer,</span> <span m="306020">things</span>
  <span m="306140">that we</span> <span m="306800">can</span> <span m="306980">change.</span>
  <span m="308250">And</span> <span m="309020">we''re</span> <span m="309110">going</span>
  <span m="309250">to</span> <span m="309340">write</span> <span m="310900">the</span>
  <span m="311010">design</span> <span m="311400">variables</span> <span m="312700">in</span>
  <span m="312940">a</span> <span m="313020">vector,</span> <span m="314380">the</span>
  <span m="314630">design</span> <span m="314850">variable</span> <span m="315310">vector</span>
  <span m="315710">or</span> <span m="315860">the</span> <span m="315950">design</span>
  <span m="316380">vector.</span></p><p><span m="316870">We''re</span> <span m="317360">going</span>
  <span m="317510">to</span> <span m="317570">give</span> <span m="317670">it</span>
  <span m="317810">the</span> <span m="317890">symbol</span> <span m="318350">x.</span>
  <span m="319405">I''ll</span> <span m="319810">put a</span> <span m="320215">vector</span>
  <span m="320930">symbol</span> <span m="321420">above</span> <span m="321540">it</span>
  <span m="321990">just</span> <span m="322270">to</span> <span m="322350">denote</span>
  <span m="322810">that</span> <span m="323890">it''s</span> <span m="324120">a</span>
  <span m="324160">vector.</span> <span m="325350">And</span> <span m="325880">it''s</span>
  <span m="326050">going</span> <span m="326280">to</span> <span m="326360">contain</span>
  <span m="328840">n</span> <span m="329930">design</span> <span m="330330">variables,</span>
  <span m="332070">n</span> <span m="332300">dvs,</span> <span m="334150">that</span>
  <span m="334470">form</span> <span m="335000">the</span> <span m="335110">design</span>
  <span m="335580">space.</span> <span m="335850">So</span> <span m="336120">when</span>
  <span m="336310">we</span> <span m="336420">talk</span> <span m="336690">about</span>
  <span m="336910">the</span> <span m="336990">design</span> <span m="337460">space,</span>
  <span m="338510">we''re</span> <span m="338610">usually</span> <span m="338870">talking</span>
  <span m="339240">about</span> <span m="339810">the</span> <span m="339890">space</span>
  <span m="340190">that''s</span> <span m="340460">defined</span> <span m="341080">by</span>
  <span m="341340">these</span> <span m="341870">quantities</span> <span m="342460">in</span>
  <span m="342530">the</span> <span m="342600">design</span> <span m="342930">vector</span>
  <span m="343220">x,</span> <span m="344405">so</span> <span m="344800">n</span>
  <span m="345140">design</span> <span m="345480">variables</span> <span m="346130">that</span>
  <span m="346620">form</span> <span m="348760">the</span> <span m="349200">design</span>
  <span m="349650">space.</span></p><p><span m="353840">And</span> <span m="356300">so</span>
  <span m="356440">mathematically,</span> <span m="357140">the</span> <span m="357240">vector</span>
  <span m="357660">x</span> <span m="358810">will</span> <span m="359170">be</span>
  <span m="361940">x1,</span> <span m="362285">x2,</span> <span m="364342">down to</span>
  <span m="364770">x10.</span> <span m="368140">OK.</span> <span m="368640">And</span>
  <span m="368760">the</span> <span m="369690">idea</span> <span m="370100">is</span>
  <span m="370240">going</span> <span m="370510">to</span> <span m="370610">be</span>
  <span m="370800">that</span> <span m="370970">as</span> <span m="371150">we</span>
  <span m="371290">run</span> <span m="371470">the</span> <span m="371560">optimization</span>
  <span m="372560">algorithm,</span> <span m="374160">it''s</span> <span m="374290">going</span>
  <span m="374600">to</span> <span m="374790">be</span> <span m="375640">searching</span>
  <span m="376100">over</span> <span m="376250">different</span> <span m="376530">values</span>
  <span m="376780">of x.</span> <span m="377230">So</span> <span m="377310">this</span>
  <span m="377430">is</span> <span m="377530">what''s</span> <span m="377710">going</span>
  <span m="377830">to</span> <span m="377890">be</span> <span m="377970">changing.</span></p><p><span
  m="379300">And</span> <span m="379550">what</span> <span m="379690">you''ll</span>
  <span m="379820">see</span> <span m="380010">is</span> <span m="380160">that</span>
  <span m="380220">different</span> <span m="380500">optimization</span> <span m="381130">methods</span>
  <span m="381640">use</span> <span m="381980">different</span> <span m="382360">rules</span>
  <span m="383030">and</span> <span m="383130">different</span> <span m="383920">information</span>
  <span m="384215">to</span> <span m="384510">figure</span> <span m="384800">out</span>
  <span m="385000">how</span> <span m="385130">to</span> <span m="385220">move</span>
  <span m="385540">around</span> <span m="385920">in</span> <span m="386010">the</span>
  <span m="386080">design</span> <span m="386536">space.</span> <span m="387904">OK.</span>
  <span m="389728">So</span> <span m="391100">what</span> <span m="391290">are</span>
  <span m="391340">some</span> <span m="391520">examples?</span> <span m="394800">So</span>
  <span m="395870">if</span> <span m="396020">we</span> <span m="396120">think</span>
  <span m="396320">about</span> <span m="396960">aircraft</span> <span m="397470">conceptual</span>
  <span m="398010">design,</span> <span m="398570">say,</span> <span m="404510">what</span>
  <span m="404700">would</span> <span m="404830">be</span> <span m="404950">examples</span>
  <span m="405760">of</span> <span m="407220">physical</span> <span m="407580">quantities</span>
  <span m="408020">that</span> <span m="408170">might</span> <span m="408390">be</span>
  <span m="408590">in</span> <span m="408880">the</span> <span m="408960">vector</span>
  <span m="409260">x?</span></p><p><span m="413240">What?</span> <span m="414250">Weight.</span>
  <span m="415730">Weight</span> <span m="416760">normally</span> <span m="417170">would</span>
  <span m="417380">not</span> <span m="417680">be</span> <span m="417860">a</span>
  <span m="417910">design</span> <span m="418260">variable,</span> <span m="419120">because</span>
  <span m="419440">weight</span> <span m="419680">is</span> <span m="419840">not</span>
  <span m="420310">usually</span> <span m="420580">something</span> <span m="420820">that</span>
  <span m="420950">you</span> <span m="421020">can</span> <span m="421160">control</span>
  <span m="421600">directly.</span> <span m="424450">It''s</span> <span m="425520">something</span>
  <span m="425880">that</span> <span m="426040">typically</span> <span m="426400">would</span>
  <span m="426530">be</span> <span m="426610">computed</span> <span m="427000">as</span>
  <span m="427110">a</span> <span m="427160">function</span> <span m="427610">of</span>
  <span m="427970">other</span> <span m="428210">things</span> <span m="428570">that</span>
  <span m="428730">would</span> <span m="428870">be</span> <span m="429010">designed</span>
  <span m="429360">variables.</span> <span m="430300">So</span> <span m="430660">weight</span>
  <span m="431560">is</span> <span m="431740">going</span> <span m="431860">to</span>
  <span m="432160">often</span> <span m="432510">show</span> <span m="432730">up</span>
  <span m="432890">as</span> <span m="433220">an</span> <span m="433300">objective.</span></p><p><span
  m="434444">AUDIENCE: Wingspan.</span></p><p><span m="435220">PROFESSOR: Wingspan.</span>
  <span m="435440">Yeah.</span> <span m="436275">So</span> <span m="436680">wingspan</span>
  <span m="438310">would</span> <span m="438430">be</span> <span m="438890">one.</span>
  <span m="440650">What else?</span> <span m="442410">What</span> <span m="442600">is
  it?</span> <span m="444520">Number</span> <span m="444840">of rotors?</span></p><p><span
  m="445670">AUDIENCE: [INAUDIBLE]</span></p><p><span m="445970">PROFESSOR: Oh,</span>
  <span m="446390">motors,</span> <span m="446710">number of</span> <span m="446950">engines?</span>
  <span m="447382">Motors?</span></p><p><span m="449110">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="449980">PROFESSOR: OK.</span> <span m="451060">Sure,</span> <span m="451410">number</span>
  <span m="451640">of</span> <span m="451740">motors</span> <span m="452530">or</span>
  <span m="452700">engines.</span> <span m="454000">Yup.</span> <span m="455850">What
  else?</span></p><p><span m="456888">AUDIENCE:</span> <span m="457332">[INAUDIBLE]</span></p><p><span
  m="458220">PROFESSOR: Payload</span> <span m="458550">size?</span> <span m="459070">Yeah.</span>
  <span m="460310">Payload</span> <span m="461120">weight</span> <span m="461420">or</span>
  <span m="462520">payload</span> <span m="462910">size</span> <span m="463383">or</span>
  <span m="463856">payload</span> <span m="464330">number</span> <span m="464540">of</span>
  <span m="464620">passengers.</span></p><p><span m="466120">AUDIENCE: Color?</span></p><p><span
  m="466620">PROFESSOR: Color?</span> <span m="468620">Who said</span> <span m="469120">color?</span>
  <span m="472340">OK.</span> <span m="473080">I''m</span> <span m="473240">going</span>
  <span m="473360">to</span> <span m="473430">spell</span> <span m="473720">it with</span>
  <span m="473830">a</span> <span m="473900">U</span> <span m="474230">just</span>
  <span m="474500">to</span> <span m="476190">have</span> <span m="476440">my</span>
  <span m="476650">objection.</span> <span m="477990">Yeah.</span> <span m="478200">[INAUDIBLE]</span>
  <span m="479080">mark</span> <span m="479520">number</span> <span m="479960">whatever.</span>
  <span m="481330">OK.</span> <span m="481560">So</span> <span m="481740">all</span>
  <span m="482010">the</span> <span m="482100">things</span> <span m="483630">that</span>
  <span m="484480">I</span> <span m="484590">think</span> <span m="484750">you</span>
  <span m="484840">can</span> <span m="485000">directly</span> <span m="485860">control</span>
  <span m="486320">and</span> <span m="486650">make</span> <span m="486810">a</span>
  <span m="486850">decision</span> <span m="487250">about.</span> <span m="488476">And</span>
  <span m="488940">what you</span> <span m="489100">notice is</span> <span m="489710">that</span>
  <span m="490010">these</span> <span m="490200">quantities</span> <span m="490700">can</span>
  <span m="490870">be</span> <span m="491010">of</span> <span m="491100">different</span>
  <span m="491430">kinds.</span></p><p><span m="491800">So</span> <span m="491890">wingspan</span>
  <span m="492580">is</span> <span m="492740">going</span> <span m="492860">to</span>
  <span m="492920">be</span> <span m="493010">a</span> <span m="493060">continuous</span>
  <span m="494040">real</span> <span m="494350">variable</span> <span m="495330">that</span>
  <span m="495460">can</span> <span m="495570">take</span> <span m="495790">on</span>
  <span m="495950">values</span> <span m="496720">between</span> <span m="497070">0</span>
  <span m="497480">and</span> <span m="498160">whatever</span> <span m="498510">upper</span>
  <span m="498780">limit</span> <span m="499040">you</span> <span m="499140">set</span>
  <span m="499400">to</span> <span m="499550">it.</span> <span m="500310">Whereas,</span>
  <span m="500570">number</span> <span m="500790">of</span> <span m="500880">motors</span>
  <span m="501220">is</span> <span m="501330">a</span> <span m="501380">discrete</span>
  <span m="501780">variable,</span> <span m="502160">right?</span> <span m="502450">It
  can</span> <span m="502740">be</span> <span m="502850">1</span> <span m="503220">or</span>
  <span m="503330">2</span> <span m="503730">or</span> <span m="503780">3,</span>
  <span m="504160">but</span> <span m="504300">it</span> <span m="504380">can''t</span>
  <span m="504580">be</span> <span m="504700">2.5</span> <span m="505110">or</span>
  <span m="505520">2.53.</span></p><p><span m="508090">And</span> <span m="508530">as</span>
  <span m="508680">we</span> <span m="508760">talk</span> <span m="508940">about</span>
  <span m="509130">the</span> <span m="509220">optimization</span> <span m="509810">methods,</span>
  <span m="510290">you''ll</span> <span m="510320">see</span> <span m="510540">that</span>
  <span m="510750">particularly</span> <span m="511180">discrete</span> <span m="511535">or</span>
  <span m="511890">integer</span> <span m="512610">variables</span> <span m="513039">cause</span>
  <span m="513320">a lot</span> <span m="513520">of</span> <span m="513559">problems.</span>
  <span m="514080">It''s</span> <span m="514570">much</span> <span m="514890">harder</span>
  <span m="515130">to</span> <span m="515260">optimize</span> <span m="515770">a</span>
  <span m="515840">problem</span> <span m="516280">that''s</span> <span m="516470">got</span>
  <span m="516690">something</span> <span m="517275">like</span> <span m="517710">number</span>
  <span m="517950">of</span> <span m="518020">engines</span> <span m="518230">or</span>
  <span m="518419">number</span> <span m="518659">of</span> <span m="518750">motors</span>
  <span m="519080">in</span> <span m="519169">it.</span> <span m="520610">OK.</span>
  <span m="520710">So</span> <span m="520940">will be</span> <span m="521110">your</span>
  <span m="521630">design vector</span> <span m="522035">x.</span></p><p><span m="523250">Next,</span>
  <span m="523710">let''s</span> <span m="523950">talk</span> <span m="524169">about</span>
  <span m="524850">objectives</span> <span m="528130">or</span> <span m="528260">objective</span>
  <span m="528670">functions.</span> <span m="531382">So</span> <span m="531840">the</span>
  <span m="531990">objectives</span> <span m="533830">can</span> <span m="534200">be</span>
  <span m="534400">a</span> <span m="534610">vector</span> <span m="535240">as</span>
  <span m="535410">well.</span> <span m="537080">And it</span> <span m="537470">can</span>
  <span m="537590">be</span> <span m="537700">a</span> <span m="537750">vector</span>
  <span m="538010">j.</span> <span m="538170">And</span> <span m="538510">I''ll put</span>
  <span m="538790">the</span> <span m="539190">vector symbol</span> <span m="539570">on</span>
  <span m="539750">there</span> <span m="540040">to</span> <span m="540190">denote</span>
  <span m="540510">when</span> <span m="540610">I''m</span> <span m="540700">talking</span>
  <span m="541050">about</span> <span m="541370">a</span> <span m="541410">vector.</span>
  <span m="542660">And</span> <span m="542930">it''s</span> <span m="543110">going</span>
  <span m="543260">to</span> <span m="543350">be</span> <span m="545720">j</span>
  <span m="546120">of</span> <span m="547225">v</span> <span m="548050">system</span>
  <span m="548480">responses</span> <span m="549370">or</span> <span m="549630">characteristics.</span></p><p><span
  m="558860">And</span> <span m="559090">they''re</span> <span m="559200">going</span>
  <span m="559530">to</span> <span m="559640">be</span> <span m="561170">responses</span>
  <span m="561770">or</span> <span m="561880">characteristics</span> <span m="563146">that</span>
  <span m="564040">we''re</span> <span m="564240">trying</span> <span m="564480">to</span>
  <span m="564560">either</span> <span m="564790">minimize</span> <span m="566170">or</span>
  <span m="566390">maximize.</span> <span m="572100">OK.</span> <span m="576528">All</span>
  <span m="577020">right,</span> <span m="577280">so</span> <span m="577380">these</span>
  <span m="577760">are</span> <span m="577890">going</span> <span m="578020">to</span>
  <span m="578100">be</span> <span m="579550">measures</span> <span m="579850">of</span>
  <span m="579970">performance,</span> <span m="580830">costs,</span> <span m="581690">schedule,</span>
  <span m="583970">anything</span> <span m="584440">that</span> <span m="584560">we</span>
  <span m="584670">might</span> <span m="584960">want</span> <span m="585380">to</span>
  <span m="585700">push</span> <span m="586540">either</span> <span m="586750">as</span>
  <span m="586880">high</span> <span m="587110">as</span> <span m="587230">possible</span>
  <span m="587505">or</span> <span m="587780">as</span> <span m="588110">low as</span>
  <span m="588440">possible</span> <span m="589790">in</span> <span m="590670">making</span>
  <span m="590930">the</span> <span m="591020">decisions</span> <span m="591490">about</span>
  <span m="592410">our</span> <span m="592540">designs.</span> <span m="594532">So</span>
  <span m="595030">what</span> <span m="595528">might</span> <span m="596026">be</span>
  <span m="596530">some</span> <span m="596680">examples,</span> <span m="597180">again?</span></p><p><span
  m="600340">For</span> <span m="600450">the</span> <span m="600520">aircraft</span>
  <span m="600960">conceptual</span> <span m="601150">design</span> <span m="601730">example,</span>
  <span m="602525">what</span> <span m="602920">will</span> <span m="603080">be</span>
  <span m="604880">objective</span> <span m="605290">functions?</span> <span m="607030">Range.</span>
  <span m="607520">Yup.</span> <span m="610782">Range</span> <span m="611250">might
  be an</span> <span m="611460">objective</span> <span m="612120">if</span> <span
  m="612130">you</span> <span m="612420">wanted</span> <span m="612580">to</span>
  <span m="612760">maximize</span> <span m="613100">range.</span> <span m="615335">What
  is it?</span> <span m="616230">Speed.</span> <span m="616770">Yup,</span> <span
  m="617120">speed</span> <span m="617390">sometimes.</span> <span m="623160">Fuel</span>
  <span m="623340">consumption,</span> <span m="623930">fuel</span> <span m="624120">burn,</span>
  <span m="625154">yup.</span></p><p><span m="629600">So</span> <span m="629760">weight</span>
  <span m="630350">often</span> <span m="630990">shows</span> <span m="631280">up</span>
  <span m="631410">as</span> <span m="631530">an</span> <span m="631610">objective.</span>
  <span m="632060">Max</span> <span m="632300">take</span> <span m="632480">off</span>
  <span m="632810">weight</span> <span m="632890">is</span> <span m="633020">often</span>
  <span m="633490">used</span> <span m="633780">as</span> <span m="633900">a</span>
  <span m="635560">target</span> <span m="635820">for</span> <span m="636730">costs</span>
  <span m="637860">and</span> <span m="637980">fuel</span> <span m="638200">burn</span>
  <span m="638350">and</span> <span m="638440">everything</span> <span m="638730">kind</span>
  <span m="638920">of</span> <span m="639270">rolled</span> <span m="639640">up.</span>
  <span m="640696">Cost</span> <span m="641120">might be another</span> <span m="641440">one,</span>
  <span m="642160">operating</span> <span m="642660">costs,</span> <span m="643050">or</span>
  <span m="643110">it might</span> <span m="643450">be</span> <span m="643570">entire</span>
  <span m="644000">lifecycle</span> <span m="644510">cost.</span> <span m="645900">Could
  be</span> <span m="646140">environmental</span> <span m="647020">impact,</span>
  <span m="647590">could be noise</span> <span m="650475">or</span> <span m="650910">different</span>
  <span m="652870">kinds</span> <span m="653120">of</span> <span m="653210">things.</span></p><p><span
  m="654580">And</span> <span m="654670">so</span> <span m="654850">I</span> <span
  m="654900">most--</span> <span m="657240">this is</span> <span m="657490">right</span>
  <span m="657710">here.</span> <span m="658020">So</span> <span m="658120">we</span>
  <span m="658130">would</span> <span m="658270">write</span> <span m="659520">the</span>
  <span m="659630">vector</span> <span m="659940">j</span> <span m="661260">as</span>
  <span m="661700">being</span> <span m="662760">j1,</span> <span m="663150">j2,</span>
  <span m="665660">jz</span> <span m="666200">if</span> <span m="666320">we</span>
  <span m="666430">had</span> <span m="666640">z</span> <span m="666830">objectives.</span>
  <span m="668280">Turns</span> <span m="668520">out</span> <span m="668670">that</span>
  <span m="668840">most</span> <span m="669220">optimization</span> <span m="669940">algorithms</span>
  <span m="670560">work</span> <span m="670930">with</span> <span m="671070">a</span>
  <span m="671100">single</span> <span m="671540">objective,</span> <span m="674970">with</span>
  <span m="675120">a</span> <span m="675190">single</span> <span m="675550">scalar</span>
  <span m="676050">objective.</span></p><p><span m="678290">There</span> <span m="678550">are</span>
  <span m="678860">some</span> <span m="679180">ways</span> <span m="679420">to</span>
  <span m="679510">do</span> <span m="679640">multi-objective</span> <span m="680440">optimization</span>
  <span m="681100">if</span> <span m="681330">you</span> <span m="681490">have</span>
  <span m="681810">more</span> <span m="682030">than</span> <span m="682150">one</span>
  <span m="682290">objective</span> <span m="682730">and</span> <span m="682820">you</span>
  <span m="682880">want</span> <span m="683000">to</span> <span m="683060">look</span>
  <span m="683210">for</span> <span m="683350">designs</span> <span m="684060">that</span>
  <span m="684780">are</span> <span m="685440">at</span> <span m="685710">the</span>
  <span m="685790">same</span> <span m="686120">time</span> <span m="686610">trying</span>
  <span m="686820">to</span> <span m="686890">maximize</span> <span m="687420">range</span>
  <span m="687910">and</span> <span m="688200">minimize</span> <span m="689020">costs,</span>
  <span m="689660">say.</span> <span m="690200">There</span> <span m="690340">are</span>
  <span m="690420">ways</span> <span m="690600">to</span> <span m="690670">do</span>
  <span m="690770">it.</span> <span m="690970">But most</span> <span m="691490">optimization</span>
  <span m="692110">methods</span> <span m="692450">work</span> <span m="692690">with</span>
  <span m="692830">a</span> <span m="692880">single</span> <span m="693220">scalar</span>
  <span m="693680">objective.</span></p><p><span m="694640">And</span> <span m="694840">if</span>
  <span m="694950">that''s</span> <span m="695220">the</span> <span m="695310">case,</span>
  <span m="695680">then</span> <span m="695910">the</span> <span m="695990">way</span>
  <span m="696190">that</span> <span m="696320">you</span> <span m="696500">would</span>
  <span m="697320">normally</span> <span m="697620">proceed</span> <span m="698130">would</span>
  <span m="698310">be</span> <span m="698610">by</span> <span m="699630">weighting</span>
  <span m="700370">the</span> <span m="700450">different</span> <span m="702900">objectives.</span>
  <span m="703640">So</span> <span m="703740">you</span> <span m="703840">would</span>
  <span m="703940">have</span> <span m="704000">weight</span> <span m="704230">1</span>
  <span m="705590">times</span> <span m="705890">j1</span> <span m="706345">plus</span>
  <span m="706800">weight 2</span> <span m="706970">times</span> <span m="707230">j2</span>
  <span m="708130">and</span> <span m="708330">so</span> <span m="708530">on.</span>
  <span m="708730">So you</span> <span m="708810">would</span> <span m="709030">roll</span>
  <span m="709520">all</span> <span m="709800">of</span> <span m="709970">the</span>
  <span m="710070">different</span> <span m="710370">objectives</span> <span m="710730">up,</span>
  <span m="711640">weight</span> <span m="711960">them,</span> <span m="712320">add</span>
  <span m="712440">them</span> <span m="712570">together,</span> <span m="712950">and</span>
  <span m="713090">get</span> <span m="713200">a</span> <span m="713250">single</span>
  <span m="713970">objective</span> <span m="714380">function</span> <span m="714790">that</span>
  <span m="714920">would</span> <span m="715070">then</span> <span m="715240">use</span>
  <span m="715420">in your</span> <span m="715580">optimization</span> <span m="716190">algorithm.</span></p><p><span
  m="716980">And</span> <span m="717150">these</span> <span m="717350">weights</span>
  <span m="718340">would</span> <span m="718540">represent</span> <span m="719420">both</span>
  <span m="719810">some</span> <span m="720090">kind</span> <span m="720230">of</span>
  <span m="720290">a</span> <span m="720350">normalizing</span> <span m="721020">factor,</span>
  <span m="721440">because</span> <span m="721830">range</span> <span m="722130">is</span>
  <span m="722220">going</span> <span m="722340">to</span> <span m="722430">be</span>
  <span m="722560">measured</span> <span m="723010">in</span> <span m="723970">meters.</span>
  <span m="724380">And</span> <span m="724480">that''s</span> <span m="724610">going</span>
  <span m="724730">to</span> <span m="724800">be</span> <span m="724910">in</span>
  <span m="724980">the</span> <span m="725040">order</span> <span m="725260">of</span>
  <span m="725350">thousands.</span> <span m="726070">Whereas,</span> <span m="726360">speed</span>
  <span m="726790">would</span> <span m="726990">be</span> <span m="727510">measured</span>
  <span m="727760">maybe</span> <span m="728030">in</span> <span m="728200">meters</span>
  <span m="728540">per</span> <span m="728650">second</span> <span m="728880">or</span>
  <span m="729080">might be</span> <span m="729320">in the</span> <span m="729510">order
  of</span> <span m="729660">hundreds.</span> <span m="731740">Costs</span> <span
  m="732000">could</span> <span m="732140">be</span> <span m="732250">in</span> <span
  m="732350">dollars.</span></p><p><span m="732780">So</span> <span m="732810">these</span>
  <span m="732900">things</span> <span m="733090">have</span> <span m="733210">different</span>
  <span m="733550">units</span> <span m="733960">and</span> <span m="734060">different</span>
  <span m="736390">scales.</span> <span m="738090">But</span> <span m="738260">you</span>
  <span m="738390">could</span> <span m="738520">also</span> <span m="738750">use</span>
  <span m="738980">these</span> <span m="739170">weights</span> <span m="739550">to</span>
  <span m="739630">talk</span> <span m="739850">about</span> <span m="740020">your</span>
  <span m="740110">design</span> <span m="740390">of</span> <span m="740470">preference.</span>
  <span m="740960">I</span> <span m="741070">care</span> <span m="741340">more</span>
  <span m="741560">about</span> <span m="741850">cost</span> <span m="742230">than</span>
  <span m="742380">I</span> <span m="742450">do</span> <span m="742590">about</span>
  <span m="742890">noise.</span> <span m="743360">Or</span> <span m="743410">I</span>
  <span m="743480">care</span> <span m="743710">more</span> <span m="743890">about</span>
  <span m="744140">fuel</span> <span m="744400">burn</span> <span m="744630">than</span>
  <span m="744760">I</span> <span m="744840">do</span> <span m="744980">about</span>
  <span m="745310">noise.</span> <span m="745640">And</span> <span m="745770">you</span>
  <span m="746050">could use</span> <span m="746330">the</span> <span m="746420">weights
  in that</span> <span m="746830">way.</span></p><p><span m="748060">OK.</span> <span
  m="748340">So</span> <span m="748980">if</span> <span m="749080">we</span> <span
  m="749330">have</span> <span m="749540">multiple</span> <span m="749870">objective,</span>
  <span m="750370">either</span> <span m="750630">we have</span> <span m="750750">to</span>
  <span m="750880">roll</span> <span m="751050">them</span> <span m="751170">up</span>
  <span m="751340">into</span> <span m="751590">a</span> <span m="751650">scalar</span>
  <span m="752120">objective</span> <span m="752570">and you</span> <span m="752760">think</span>
  <span m="752960">about</span> <span m="753110">what</span> <span m="753280">these</span>
  <span m="753380">weights</span> <span m="753730">would</span> <span m="753900">be</span>
  <span m="754760">or</span> <span m="755570">there</span> <span m="755800">are</span>
  <span m="756030">some</span> <span m="757000">methods</span> <span m="757450">to</span>
  <span m="757570">do</span> <span m="757840">what''s</span> <span m="758040">called</span>
  <span m="758220">multi-objective</span> <span m="759130">optimization.</span> <span
  m="760920">I''ll add one</span> <span m="761240">more</span> <span m="761460">to</span>
  <span m="761520">the</span> <span m="761610">left.</span> <span m="762290">This
  is</span> <span m="762470">Professor</span> <span m="762735">[INAUDIBLE]</span>
  <span m="763470">preferred--</span> <span m="764971">does</span> <span m="765370">he</span>
  <span m="765840">talk</span> <span m="766040">about</span> <span m="766500">[INAUDIBLE]?</span></p><p><span
  m="770210">I</span> <span m="770330">think</span> <span m="770490">it''s</span>
  <span m="770620">payload</span> <span m="771000">fuel</span> <span m="771500">efficiency--</span>
  <span m="772975">no,</span> <span m="774610">payload</span> <span m="774950">fuel</span>
  <span m="775290">energy</span> <span m="775870">intensity.</span> <span m="777100">It''s</span>
  <span m="777290">a</span> <span m="777330">measure</span> <span m="777750">of</span>
  <span m="778080">fuel</span> <span m="778380">burned</span> <span m="778903">per</span>
  <span m="779670">person</span> <span m="780180">traveled</span> <span m="780710">1</span>
  <span m="782170">nautical</span> <span m="782510">mile</span> <span m="782830">or</span>
  <span m="783306">1kilometer.</span> <span m="784260">So it''s</span> <span m="784420">a</span>
  <span m="784460">measure</span> <span m="784720">of</span> <span m="784800">how</span>
  <span m="784970">far</span> <span m="785380">you</span> <span m="785510">fly,</span>
  <span m="785890">how</span> <span m="785960">many</span> <span m="786120">people</span>
  <span m="786430">you</span> <span m="786530">transport,</span> <span m="786950">how</span>
  <span m="787040">much</span> <span m="787300">fuel</span> <span m="787530">you</span>
  <span m="787680">burn,</span> <span m="788730">measure</span> <span m="789000">of</span>
  <span m="789060">efficiency.</span></p><p><span m="791170">OK.</span> <span m="791560">So</span>
  <span m="791960">design</span> <span m="792430">variables</span> <span m="793660">and</span>
  <span m="793940">objectives,</span> <span m="794560">design</span> <span m="794840">variables</span>
  <span m="795240">are</span> <span m="795290">what</span> <span m="795430">we</span>
  <span m="795530">can</span> <span m="795700">change.</span> <span m="796570">The</span>
  <span m="796700">objectives</span> <span m="797210">are</span> <span m="797270">going</span>
  <span m="797390">to</span> <span m="797470">be</span> <span m="797600">the</span>
  <span m="797850">measures</span> <span m="798470">of</span> <span m="798580">how</span>
  <span m="798770">good the</span> <span m="799040">design</span> <span m="799510">is</span>
  <span m="803810">that</span> <span m="804030">give</span> <span m="804200">us</span>
  <span m="804860">some</span> <span m="805670">direction</span> <span m="807070">for</span>
  <span m="807310">change.</span> <span m="808630">Then</span> <span m="808790">we''re</span>
  <span m="808940">also</span> <span m="809160">going</span> <span m="809280">to</span>
  <span m="809340">have</span> <span m="809540">constraints.</span></p><p><span m="813700">Again,</span>
  <span m="813990">we</span> <span m="814100">think</span> <span m="814310">constraints</span>
  <span m="814890">are</span> <span m="814980">what</span> <span m="815290">we</span>
  <span m="815710">cannot</span> <span m="816220">violate.</span> <span m="817660">So</span>
  <span m="818140">these</span> <span m="818380">are</span> <span m="818440">going</span>
  <span m="818780">to</span> <span m="819290">act</span> <span m="820901">as</span>
  <span m="821280">the</span> <span m="821370">boundaries</span> <span m="824860">of</span>
  <span m="826320">the</span> <span m="826450">design</span> <span m="826850">space.</span>
  <span m="827200">So</span> <span m="827345">here</span> <span m="827490">the</span>
  <span m="827770">design</span> <span m="828310">space</span> <span m="830030">is</span>
  <span m="830320">defined</span> <span m="830780">by</span> <span m="830890">those</span>
  <span m="831140">design</span> <span m="831590">variables.</span></p><p><span m="833148">So</span>
  <span m="834420">a</span> <span m="834610">nice</span> <span m="834880">visual</span>
  <span m="836150">picture</span> <span m="836460">that</span> <span m="836600">I</span>
  <span m="836710">like</span> <span m="836930">to</span> <span m="837030">have</span>
  <span m="837340">in</span> <span m="837470">mind</span> <span m="838390">is</span>
  <span m="838580">that</span> <span m="838990">the</span> <span m="839120">design</span>
  <span m="839440">space</span> <span m="839700">is</span> <span m="839790">like</span>
  <span m="839970">a</span> <span m="840040">landscape.</span> <span m="841201">So</span>
  <span m="841590">think</span> <span m="841940">of</span> <span m="842780">your</span>
  <span m="842990">landscape.</span> <span m="843540">It''s</span> <span m="844105">got</span>
  <span m="844520">hills,</span> <span m="845020">mountains.</span> <span m="845700">It''s</span>
  <span m="845830">got</span> <span m="846050">valleys.</span> <span m="846540">It''s</span>
  <span m="846650">got</span> <span m="846840">flat</span> <span m="847130">regions.</span></p><p><span
  m="848250">The</span> <span m="848350">dimensions</span> <span m="848780">of</span>
  <span m="848840">the</span> <span m="848910">landscape</span> <span m="849470">are</span>
  <span m="849580">the</span> <span m="849670">design</span> <span m="850070">variables.</span>
  <span m="850690">So</span> <span m="850840">you</span> <span m="851000">can</span>
  <span m="851200">think</span> <span m="851760">about</span> <span m="852090">two</span>
  <span m="852300">design</span> <span m="852640">variable,</span> <span m="853230">x1</span>
  <span m="853490">and</span> <span m="853750">x2.</span> <span m="854800">And</span>
  <span m="854950">then</span> <span m="855150">the</span> <span m="855270">height</span>
  <span m="856050">of</span> <span m="856210">the</span> <span m="856290">landscape</span>
  <span m="857220">is</span> <span m="857480">the</span> <span m="857620">objective</span>
  <span m="858010">function.</span> <span m="859250">Right?</span> <span m="859520">So</span>
  <span m="860100">the</span> <span m="860240">mountains,</span> <span m="860930">the</span>
  <span m="861040">hills,</span> <span m="861320">that''s</span> <span m="861580">places</span>
  <span m="861990">where</span> <span m="862130">the</span> <span m="862270">objective</span>
  <span m="863010">is</span> <span m="863310">high.</span> <span m="864870">And</span>
  <span m="865900">the</span> <span m="866130">places</span> <span m="866530">where</span>
  <span m="866620">you</span> <span m="866740">have</span> <span m="866960">valleys,</span>
  <span m="867330">that''s</span> <span m="867500">where</span> <span m="867600">the</span>
  <span m="867690">objective</span> <span m="868280">is</span> <span m="868540">low.</span></p><p><span
  m="868970">And</span> <span m="868990">so</span> <span m="869090">if</span> <span
  m="869170">you</span> <span m="869240">try</span> <span m="869380">to</span> <span
  m="869470">minimize,</span> <span m="870120">say,</span> <span m="870320">cost,</span>
  <span m="871220">good</span> <span m="871410">designs</span> <span m="871840">you''d</span>
  <span m="871940">be</span> <span m="872040">looking</span> <span m="872300">for</span>
  <span m="872420">them</span> <span m="872630">in</span> <span m="873020">the</span>
  <span m="873100">valley.</span> <span m="874110">And</span> <span m="874270">the</span>
  <span m="874350">regions</span> <span m="874830">where</span> <span m="875190">the</span>
  <span m="875330">space</span> <span m="875620">is</span> <span m="875770">flat,</span>
  <span m="876340">those</span> <span m="876560">are</span> <span m="876630">regions</span>
  <span m="877200">where</span> <span m="878050">changing</span> <span m="878390">the</span>
  <span m="878440">design</span> <span m="878850">doesn''t</span> <span m="879060">really</span>
  <span m="879260">change</span> <span m="879630">the</span> <span m="879690">cost</span>
  <span m="880040">or</span> <span m="880080">doesn''t</span> <span m="880360">change</span>
  <span m="880640">the</span> <span m="880720">weight</span> <span m="880880">or</span>
  <span m="880960">whatever</span> <span m="881210">the</span> <span m="881960">objective</span>
  <span m="882400">is.</span> <span m="883300">So</span> <span m="883310">then</span>
  <span m="883420">what</span> <span m="883530">are</span> <span m="883590">the</span>
  <span m="883670">constraints?</span></p><p><span m="884800">The</span> <span m="884900">constraints</span>
  <span m="885370">are</span> <span m="885410">going</span> <span m="885540">to</span>
  <span m="885610">come</span> <span m="885820">in</span> <span m="885950">and</span>
  <span m="886130">tell</span> <span m="886360">you</span> <span m="886540">where</span>
  <span m="886810">in</span> <span m="886900">the</span> <span m="886980">landscape</span>
  <span m="887275">are</span> <span m="887570">you</span> <span m="887770">allowed</span>
  <span m="887900">to be.</span> <span m="889229">So</span> <span m="890115">there''s</span>
  <span m="890560">going</span> <span m="890680">to</span> <span m="890750">be</span>
  <span m="890850">boundaries</span> <span m="891520">that</span> <span m="891690">say</span>
  <span m="891920">you</span> <span m="892030">can''t</span> <span m="892450">go</span>
  <span m="892770">on</span> <span m="893260">the</span> <span m="893440">side</span>
  <span m="894360">of</span> <span m="895330">the</span> <span m="895410">boundary.</span>
  <span m="895820">You</span> <span m="895910">have</span> <span m="896050">to</span>
  <span m="896160">stay</span> <span m="896410">within</span> <span m="896680">this</span>
  <span m="896850">region.</span> <span m="898360">It''s</span> <span m="898490">going</span>
  <span m="898610">to</span> <span m="898680">define</span> <span m="899150">regions</span>
  <span m="899620">where</span> <span m="899770">designs</span> <span m="900250">are</span>
  <span m="900350">allowable,</span> <span m="901070">where</span> <span m="901240">they</span>
  <span m="901960">satisfy</span> <span m="902930">different</span> <span m="903220">kinds</span>
  <span m="903430">of</span> <span m="903510">constraints.</span> <span m="903990">And
  it''s</span> <span m="904150">going</span> <span m="904270">to</span> <span m="904330">tell</span>
  <span m="904470">you</span> <span m="904610">regions</span> <span m="905030">where</span>
  <span m="905400">your</span> <span m="905540">designs</span> <span m="906350">are</span>
  <span m="906480">not</span> <span m="906800">allowable.</span></p><p><span m="909040">And</span>
  <span m="910240">what</span> <span m="910410">kind</span> <span m="910620">of</span>
  <span m="910710">constraints</span> <span m="911050">can</span> <span m="911390">you</span>
  <span m="913580">get?</span> <span m="914650">We''re</span> <span m="914810">going</span>
  <span m="914960">to</span> <span m="915030">have</span> <span m="916000">inequality</span>
  <span m="916650">constraints,</span> <span m="920140">which</span> <span m="920440">we''ll</span>
  <span m="920882">write</span> <span m="921324">as</span> <span m="923980">gj</span>
  <span m="926480">is less</span> <span m="926980">than or equal</span> <span m="927480">to
  0,</span> <span m="928480">for</span> <span m="928980">j</span> <span m="929390">for</span>
  <span m="929650">1</span> <span m="932230">to</span> <span m="932540">m1.</span>
  <span m="933060">So we''ll</span> <span m="933310">have</span> <span m="933620">m1</span>
  <span m="935210">inequality</span> <span m="935780">constraint.</span> <span m="936390">And
  the</span> <span m="936590">constraint</span> <span m="937190">is</span> <span m="937370">written</span>
  <span m="937700">that</span> <span m="938282">g,</span> <span m="939490">gj</span>
  <span m="940040">for</span> <span m="940160">the</span> <span m="940250">j</span>
  <span m="940570">constraint</span> <span m="941220">has</span> <span m="941540">to</span>
  <span m="941630">be</span> <span m="941780">less</span> <span m="942000">than</span>
  <span m="942130">or</span> <span m="942220">equal</span> <span m="942430">to</span>
  <span m="942500">0.</span></p><p><span m="943700">So</span> <span m="944100">this</span>
  <span m="944330">might</span> <span m="944640">be</span> <span m="944830">a</span>
  <span m="944910">constraint</span> <span m="945580">that''s</span> <span m="945810">something</span>
  <span m="946070">like</span> <span m="946360">[INAUDIBLE]</span> <span m="946650">speed.</span>
  <span m="947760">You</span> <span m="947870">need</span> <span m="948040">a</span>
  <span m="948070">constraint</span> <span m="948480">on</span> <span m="948600">[INAUDIBLE]</span>
  <span m="948930">speed.</span> <span m="949790">And you</span> <span m="949960">don''t</span>
  <span m="950450">require</span> <span m="950830">the</span> <span m="950930">speed</span>
  <span m="951580">to</span> <span m="951750">be</span> <span m="951890">anything</span>
  <span m="952160">in</span> <span m="952240">particular.</span> <span m="952710">But</span>
  <span m="952860">you''ve</span> <span m="952960">got</span> <span m="953080">to</span>
  <span m="953140">make</span> <span m="953330">sure</span> <span m="953490">that</span>
  <span m="955340">you</span> <span m="955430">stay</span> <span m="956480">above</span>
  <span m="956770">the</span> <span m="956870">constraint.</span> <span m="957240">You</span>
  <span m="957330">would</span> <span m="957450">bring</span> <span m="957620">everything</span>
  <span m="957960">over</span> <span m="958110">to</span> <span m="958200">the</span>
  <span m="958280">left-hand</span> <span m="958690">side</span> <span m="959060">and</span>
  <span m="959150">make</span> <span m="959360">the</span> <span m="959400">constraint</span>
  <span m="959870">less than</span> <span m="960140">equal</span> <span m="960440">to
  0.</span></p><p><span m="961440">Or</span> <span m="961650">if</span> <span m="961760">you</span>
  <span m="961910">had</span> <span m="962230">a</span> <span m="962300">constraint</span>
  <span m="962720">on</span> <span m="962850">cost,</span> <span m="964100">you</span>
  <span m="964230">would</span> <span m="964360">say</span> <span m="964610">that</span>
  <span m="964800">the</span> <span m="964860">cost</span> <span m="965390">minus</span>
  <span m="965880">the</span> <span m="965960">maximum</span> <span m="966220">cost</span>
  <span m="966646">you</span> <span m="967072">can incur</span> <span m="967500">had</span>
  <span m="967680">to</span> <span m="967770">be</span> <span m="967930">less than
  equal</span> <span m="968195">0.</span> <span m="968730">So</span> <span m="968990">inequality</span>
  <span m="969420">constraints</span> <span m="969950">often</span> <span m="970250">come</span>
  <span m="971050">when</span> <span m="971230">there''s</span> <span m="971380">some</span>
  <span m="971580">kind</span> <span m="971740">of</span> <span m="971840">limitation</span>
  <span m="972400">on</span> <span m="972500">the</span> <span m="972610">resources</span>
  <span m="973120">that</span> <span m="973270">you</span> <span m="973390">have</span>
  <span m="973750">or there''s</span> <span m="974000">some</span> <span m="974150">kind</span>
  <span m="974290">of</span> <span m="975880">physical</span> <span m="976390">limitation</span>
  <span m="977240">in</span> <span m="977820">terms</span> <span m="978740">of</span>
  <span m="978940">the</span> <span m="979020">physics.</span></p><p><span m="979990">And</span>
  <span m="980130">then</span> <span m="980220">we</span> <span m="980320">might</span>
  <span m="980490">also</span> <span m="980750">have</span> <span m="981290">equality</span>
  <span m="981890">constraints.</span> <span m="985380">And</span> <span m="985630">we''re</span>
  <span m="985690">going</span> <span m="985810">to</span> <span m="986330">give</span>
  <span m="986510">those</span> <span m="986880">the symbol</span> <span m="988570">h.</span>
  <span m="989440">So we''ll</span> <span m="989700">write</span> <span m="989940">hk</span>
  <span m="990650">equal</span> <span m="991040">to</span> <span m="991130">0.</span>
  <span m="992460">And</span> <span m="992820">in</span> <span m="992920">general,</span>
  <span m="993350">we''ll</span> <span m="993610">have</span> <span m="994700">m2</span>
  <span m="998410">equality</span> <span m="998920">constraint.</span> <span m="999440">So</span>
  <span m="999510">what''s</span> <span m="999680">an</span> <span m="999750">example</span>
  <span m="1000160">of</span> <span m="1000250">an</span> <span m="1000370">equality</span>
  <span m="1000880">constraint in</span> <span m="1001380">an aircraft</span> <span
  m="1001645">design</span> <span m="1002210">problem?</span></p><p><span m="1008550">Lift
  equals</span> <span m="1008870">weight,</span> <span m="1009360">yeah.</span> <span
  m="1009670">So that''s</span> <span m="1009910">kind</span> <span m="1010040">of</span>
  <span m="1010100">the</span> <span m="1010200">classic</span> <span m="1010590">one</span>
  <span m="1010730">that</span> <span m="1010850">shows</span> <span m="1011090">up</span>
  <span m="1011240">in</span> <span m="1011340">the</span> <span m="1011900">aircraft</span>
  <span m="1012230">design</span> <span m="1012580">problem,</span> <span m="1012860">lift</span>
  <span m="1013040">equals</span> <span m="1013300">weight</span> <span m="1013480">or</span>
  <span m="1013650">left</span> <span m="1013960">minus</span> <span m="1014240">weight</span>
  <span m="1014700">equals</span> <span m="1014860">0.</span> <span m="1017530">If</span>
  <span m="1017740">you</span> <span m="1017970">had</span> <span m="1018610">sophisticated--</span>
  <span m="1019140">like,</span> <span m="1019290">if</span> <span m="1019410">you</span>
  <span m="1019570">have</span> <span m="1020290">structural</span> <span m="1020800">models</span>
  <span m="1021140">in</span> <span m="1021220">there</span> <span m="1022490">and
  you''re</span> <span m="1022630">using</span> <span m="1022860">a</span> <span m="1022910">finite</span>
  <span m="1023160">element</span> <span m="1023490">analysis,</span> <span m="1024140">then</span>
  <span m="1024420">the</span> <span m="1024800">governing</span> <span m="1025170">equation</span>
  <span m="1026020">of</span> <span m="1026150">the</span> <span m="1026210">finite</span>
  <span m="1026670">element analysis</span> <span m="1027280">would</span> <span m="1027400">also</span>
  <span m="1027650">show</span> <span m="1027930">up</span> <span m="1028060">here,</span>
  <span m="1028640">the</span> <span m="1028800">laws</span> <span m="1029089">of</span>
  <span m="1030760">whatever</span> <span m="1031040">the</span> <span m="1031490">PDE</span>
  <span m="1031910">that</span> <span m="1032030">you</span> <span m="1032089">discretized.</span>
  <span m="1033180">Or</span> <span m="1033300">if there''s</span> <span m="1033440">a</span>
  <span m="1033530">CFD</span> <span m="1033990">model</span> <span m="1034969">or
  a</span> <span m="1035319">CFD</span> <span m="1035670">equation,</span> <span m="1035950">it''s</span>
  <span m="1036230">the</span> <span m="1036290">conservation</span> <span m="1036880">of</span>
  <span m="1036990">mass,</span> <span m="1037690">momentum,</span> <span m="1038589">energy,</span>
  <span m="1039079">and</span> <span m="1039130">so</span> <span m="1039319">on.</span></p><p><span
  m="1040589">So</span> <span m="1040800">often,</span> <span m="1041010">we</span>
  <span m="1041089">can</span> <span m="1041230">have</span> <span m="1041390">lots</span>
  <span m="1041660">and</span> <span m="1041760">lots</span> <span m="1042030">of</span>
  <span m="1043180">equality</span> <span m="1043650">constraints.</span> <span m="1044720">So
  you</span> <span m="1044869">have</span> <span m="1044970">inequality</span> <span
  m="1045510">constraints</span> <span m="1045900">and</span> <span m="1046079">we</span>
  <span m="1046220">have</span> <span m="1046359">equality</span> <span m="1046730">constraints.</span>
  <span m="1047300">And</span> <span m="1047390">then</span> <span m="1047500">we</span>
  <span m="1047579">can</span> <span m="1047730">also</span> <span m="1048170">have</span>
  <span m="1050030">design</span> <span m="1050450">variable</span> <span m="1050820">bounds.</span>
  <span m="1053010">And</span> <span m="1055470">even</span> <span m="1055790">though</span>
  <span m="1056080">these</span> <span m="1056300">things</span> <span m="1056570">are</span>
  <span m="1056640">kind</span> <span m="1056870">of</span> <span m="1056940">like</span>
  <span m="1057190">inequality</span> <span m="1057730">constraints,</span> <span
  m="1058350">they''re</span> <span m="1058450">usually</span> <span m="1058690">separated</span>
  <span m="1059240">out,</span> <span m="1059480">because</span> <span m="1059730">they''re</span>
  <span m="1059830">quite</span> <span m="1060080">often</span> <span m="1060350">treated</span>
  <span m="1060760">differently.</span></p><p><span m="1062010">And</span> <span m="1062540">the</span>
  <span m="1062690">design</span> <span m="1063030">variable</span> <span m="1063400">bounds</span>
  <span m="1063950">for</span> <span m="1064380">design</span> <span m="1064770">variable</span>
  <span m="1065160">xi--</span> <span m="1065820">remember,</span> <span m="1066170">our</span>
  <span m="1066420">design</span> <span m="1066740">vector</span> <span m="1067010">was</span>
  <span m="1067140">x1</span> <span m="1067490">x1</span> <span m="1067740">down to</span>
  <span m="1068570">xn.</span> <span m="1069590">We</span> <span m="1069770">might</span>
  <span m="1070120">bound</span> <span m="1071260">design</span> <span m="1071580">variable</span>
  <span m="1071930">xi</span> <span m="1072720">by a</span> <span m="1072820">lower</span>
  <span m="1073150">bound</span> <span m="1075160">and</span> <span m="1076040">by</span>
  <span m="1076510">an upper</span> <span m="1076790">bound,</span> <span m="1079830">right?</span>
  <span m="1080722">So</span> <span m="1081170">for</span> <span m="1081350">example,</span>
  <span m="1081780">wingspan</span> <span m="1081980">was</span> <span m="1082260">one</span>
  <span m="1082460">of</span> <span m="1083030">the</span> <span m="1083100">design</span>
  <span m="1083420">variables.</span> <span m="1083710">I</span> <span m="1084000">mean,</span>
  <span m="1084130">the</span> <span m="1084180">lower</span> <span m="1084370">bound</span>
  <span m="1085210">could</span> <span m="1085350">be</span> <span m="1085450">0.</span>
  <span m="1085870">But</span> <span m="1086040">it</span> <span m="1086130">might</span>
  <span m="1086350">even</span> <span m="1086620">be</span> <span m="1088030">bigger</span>
  <span m="1088240">than</span> <span m="1088390">0.</span></p><p><span m="1088730">And</span>
  <span m="1088820">the</span> <span m="1088910">upper</span> <span m="1089030">bound</span>
  <span m="1089410">might</span> <span m="1089650">be</span> <span m="1090270">the</span>
  <span m="1090380">limit</span> <span m="1090630">that</span> <span m="1090740">we</span>
  <span m="1090820">know</span> <span m="1090970">exists,</span> <span m="1091280">because</span>
  <span m="1091950">[INAUDIBLE]</span> <span m="1092510">in</span> <span m="1092590">the</span>
  <span m="1092710">[INAUDIBLE]</span> <span m="1093020">constraints,</span> <span
  m="1094120">the</span> <span m="1094590">80 meter</span> <span m="1095060">box</span>
  <span m="1095840">for</span> <span m="1096210">a</span> <span m="1097170">big</span>
  <span m="1097380">aircraft.</span> <span m="1098170">Or</span> <span m="1098350">it</span>
  <span m="1098430">may</span> <span m="1098620">be</span> <span m="1098780">that</span>
  <span m="1099010">we</span> <span m="1099180">know</span> <span m="1099490">we</span>
  <span m="1099630">want</span> <span m="1100000">designs</span> <span m="1100420">that</span>
  <span m="1100550">are</span> <span m="1100580">going</span> <span m="1100710">to</span>
  <span m="1100840">be</span> <span m="1101020">between</span> <span m="1102260">40</span>
  <span m="1102570">and</span> <span m="1102700">50,</span> <span m="1103060">and</span>
  <span m="1103200">so</span> <span m="1103280">we''re</span> <span m="1103340">going</span>
  <span m="1103460">to</span> <span m="1103520">put</span> <span m="1103650">those</span>
  <span m="1103850">bounds</span> <span m="1104220">on</span> <span m="1104430">so</span>
  <span m="1104520">we</span> <span m="1104580">don''t</span> <span m="1104820">waste</span>
  <span m="1105080">time</span> <span m="1105400">searching</span> <span m="1105850">for</span>
  <span m="1105940">designs</span> <span m="1106880">elsewhere.</span> <span m="1108000">So</span>
  <span m="1108200">we</span> <span m="1108310">may</span> <span m="1108690">have</span>
  <span m="1112050">lower</span> <span m="1112380">and</span> <span m="1112480">upper</span>
  <span m="1112640">bounds</span> <span m="1113180">for</span> <span m="1114640">some</span>
  <span m="1115050">or</span> <span m="1115210">all</span> <span m="1115420">of</span>
  <span m="1115520">our</span> <span m="1116090">design variables.</span></p><p><span
  m="1120150">OK.</span> <span m="1121930">So</span> <span m="1122350">now,</span>
  <span m="1122570">we</span> <span m="1122700">have</span> <span m="1122960">all</span>
  <span m="1123160">the</span> <span m="1123250">pieces.</span> <span m="1124750">I''m</span>
  <span m="1124840">going</span> <span m="1124960">to</span> <span m="1125040">call</span>
  <span m="1125230">the</span> <span m="1125320">parameters</span> <span m="1125750">p.</span>
  <span m="1130550">What</span> <span m="1130710">are</span> <span m="1130750">things</span>
  <span m="1131850">that</span> <span m="1132010">could</span> <span m="1132150">be</span>
  <span m="1132250">parameters?</span> <span m="1134520">Material</span> <span m="1135060">properties</span>
  <span m="1135550">could</span> <span m="1135700">be</span> <span m="1135850">parameters.</span></p><p><span
  m="1136770">Sometimes</span> <span m="1137340">speed</span> <span m="1137640">is</span>
  <span m="1137760">actually</span> <span m="1138030">a</span> <span m="1138090">parameter.</span>
  <span m="1139110">Often,</span> <span m="1139430">aircraft</span> <span m="1139840">are</span>
  <span m="1139890">designed</span> <span m="1140390">with</span> <span m="1140580">speed</span>
  <span m="1140980">being</span> <span m="1141320">fixed</span> <span m="1141880">and</span>
  <span m="1141990">not</span> <span m="1142230">something</span> <span m="1142520">that</span>
  <span m="1142640">you</span> <span m="1142750">can</span> <span m="1142930">vary.</span>
  <span m="1143380">So</span> <span m="1143590">often</span> <span m="1144810">mach</span>
  <span m="1145060">number</span> <span m="1145310">might</span> <span m="1145530">show</span>
  <span m="1145760">up</span> <span m="1145890">as</span> <span m="1146000">a</span>
  <span m="1146070">parameter--</span> <span m="1147000">anything</span> <span m="1147520">that''s</span>
  <span m="1147780">going</span> <span m="1147900">to</span> <span m="1147980">go</span>
  <span m="1148210">in</span> <span m="1148300">the</span> <span m="1148380">problem</span>
  <span m="1148800">that''s</span> <span m="1148990">going</span> <span m="1149120">to</span>
  <span m="1149190">affect</span> <span m="1149660">the</span> <span m="1149740">constraints</span>
  <span m="1150370">or</span> <span m="1150490">affect</span> <span m="1150960">the</span>
  <span m="1151260">objectives,</span> <span m="1151800">but</span> <span m="1152080">is</span>
  <span m="1152250">not</span> <span m="1152470">allowed</span> <span m="1152900">to</span>
  <span m="1153180">vary.</span></p><p><span m="1154430">So</span> <span m="1156650">putting</span>
  <span m="1156970">all</span> <span m="1157050">that</span> <span m="1157250">together,</span>
  <span m="1159200">what</span> <span m="1159350">does</span> <span m="1159470">the</span>
  <span m="1159590">optimization</span> <span m="1160230">problem</span> <span m="1160600">look</span>
  <span m="1160800">like?</span> <span m="1162410">Minimize</span> <span m="1163570">over</span>
  <span m="1163840">x</span> <span m="1165090">from</span> <span m="1165300">j</span>
  <span m="1165710">of x.</span> <span m="1167100">And</span> <span m="1167330">x</span>
  <span m="1167650">here</span> <span m="1167810">is</span> <span m="1167920">a</span>
  <span m="1167980">vector.</span> <span m="1168910">But</span> <span m="1169090">we''re
  going</span> <span m="1169220">to,</span> <span m="1169440">again,</span> <span
  m="1169770">consider</span> <span m="1170370">just a</span> <span m="1170470">scalar</span>
  <span m="1171290">objective</span> <span m="1171770">function.</span> <span m="1172350">So</span>
  <span m="1172370">if</span> <span m="1172440">we</span> <span m="1172500">have</span>
  <span m="1172590">lots</span> <span m="1172800">of</span> <span m="1172880">objectives,</span>
  <span m="1173460">we''re</span> <span m="1173520">going</span> <span m="1173640">to</span>
  <span m="1174590">roll</span> <span m="1174810">them</span> <span m="1174930">all</span>
  <span m="1175040">up</span> <span m="1175180">together</span> <span m="1176550">subject</span>
  <span m="1177160">to</span> <span m="1178710">the</span> <span m="1178810">constraints,</span>
  <span m="1179740">the</span> <span m="1179860">hk</span> <span m="1184310">of</span>
  <span m="1184530">x.</span></p><p><span m="1184850">And</span> <span m="1184940">actually,
  let me</span> <span m="1185380">write</span> <span m="1185600">explicitly</span>
  <span m="1186210">this</span> <span m="1186370">is</span> <span m="1186440">a</span>
  <span m="1186530">function</span> <span m="1186900">of</span> <span m="1187030">x</span>
  <span m="1188110">and</span> <span m="1188300">p.</span> <span m="1188620">And</span>
  <span m="1188730">it''s</span> <span m="1188880">quite</span> <span m="1189090">common</span>
  <span m="1189430">to</span> <span m="1189520">put</span> <span m="1189680">the</span>
  <span m="1189760">semi-colon</span> <span m="1190500">here</span> <span m="1191690">to</span>
  <span m="1191860">show</span> <span m="1192230">that</span> <span m="1193030">j,</span>
  <span m="1193315">the</span> <span m="1193600">objective,</span> <span m="1194130">depends</span>
  <span m="1194570">on</span> <span m="1194660">the</span> <span m="1194750">parameters.</span>
  <span m="1195260">But</span> <span m="1195410">the</span> <span m="1195490">parameters</span>
  <span m="1196000">are</span> <span m="1196390">kind of</span> <span m="1196780">different</span>
  <span m="1197240">to</span> <span m="1198420">the</span> <span m="1198510">design</span>
  <span m="1198880">variables.</span> <span m="1199540">But</span> <span m="1199600">the
  things</span> <span m="1199840">we</span> <span m="1199920">can</span> <span m="1200080">change,</span>
  <span m="1200420">these</span> <span m="1200540">are</span> <span m="1200580">just</span>
  <span m="1200800">things</span> <span m="1201060">that</span> <span m="1201210">affect</span>
  <span m="1201920">[INAUDIBLE],</span> <span m="1203240">but they</span> <span m="1203380">do</span>
  <span m="1203510">affect</span> <span m="1203680">j.</span></p><p><span m="1204680">So</span>
  <span m="1204800">the</span> <span m="1204870">same</span> <span m="1205130">thing</span>
  <span m="1205520">for</span> <span m="1205810">the</span> <span m="1207550">[INAUDIBLE]</span>
  <span m="1207780">vector</span> <span m="1208100">as</span> <span m="1208220">well.</span>
  <span m="1208570">For</span> <span m="1208720">the</span> <span m="1208800">constraints,</span>
  <span m="1209700">hk</span> <span m="1210520">is</span> <span m="1210890">equal</span>
  <span m="1211160">to</span> <span m="1211250">0.</span> <span m="1211730">And</span>
  <span m="1211840">that''s</span> <span m="1212420">k</span> <span m="1212660">equal</span>
  <span m="1212840">1,</span> <span m="1213790">2.</span> <span m="1214050">I think</span>
  <span m="1214240">we</span> <span m="1214340">had</span> <span m="1214470">m2</span>
  <span m="1215030">of</span> <span m="1215160">those.</span> <span m="1216540">So</span>
  <span m="1216720">gj--</span> <span m="1218900">again</span> <span m="1219250">there,
  a</span> <span m="1219480">function</span> <span m="1219890">of</span> <span m="1220560">x</span>
  <span m="1221020">and</span> <span m="1221480">p--</span> <span m="1222860">are</span>
  <span m="1223320">less</span> <span m="1223610">than</span> <span m="1223770">or</span>
  <span m="1223880">equal</span> <span m="1224110">to</span> <span m="1224210">0.</span>
  <span m="1226362">And j</span> <span m="1226840">goes</span> <span m="1227130">from</span>
  <span m="1227450">1</span> <span m="1228960">to</span> <span m="1229290">m1.</span></p><p><span
  m="1231160">And</span> <span m="1232200">then</span> <span m="1233310">the</span>
  <span m="1233730">xi</span> <span m="1237080">lie</span> <span m="1237390">between</span>
  <span m="1238150">the</span> <span m="1238620">lower</span> <span m="1238910">bound--</span>
  <span m="1239772">how did I</span> <span m="1240203">write</span> <span m="1240634">[INAUDIBLE]</span>
  <span m="1241065">that way--</span> <span m="1241930">and</span> <span m="1242110">the</span>
  <span m="1242230">upper</span> <span m="1242530">bound</span> <span m="1244350">for</span>
  <span m="1244550">the</span> <span m="1244630">design</span> <span m="1244980">variables</span>
  <span m="1245840">where</span> <span m="1247310">some</span> <span m="1247480">of</span>
  <span m="1247540">these</span> <span m="1247830">guys</span> <span m="1248170">might</span>
  <span m="1248360">be</span> <span m="1248450">minus</span> <span m="1248750">infinity</span>
  <span m="1249100">or</span> <span m="1249730">infinity</span> <span m="1250200">if</span>
  <span m="1250350">we</span> <span m="1250430">don''t</span> <span m="1250590">actually</span>
  <span m="1250860">have</span> <span m="1251040">bounds.</span> <span m="1253366">OK.</span>
  <span m="1254818">Yup.</span></p><p><span m="1255786">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="1259180">PROFESSOR: Yeah.</span> <span m="1260680">Yeah.</span> <span m="1261600">So</span>
  <span m="1262540">again,</span> <span m="1263340">whatever</span> <span m="1263650">the</span>
  <span m="1263740">problem,</span> <span m="1264040">however the</span> <span m="1264420">problem</span>
  <span m="1264700">shows</span> <span m="1265060">up,</span> <span m="1265290">we</span>
  <span m="1265390">can</span> <span m="1265570">always</span> <span m="1265780">write</span>
  <span m="1265930">it in</span> <span m="1266060">this</span> <span m="1266240">form.</span>
  <span m="1267130">So exactly,</span> <span m="1267575">if</span> <span m="1268020">we</span>
  <span m="1268190">actually</span> <span m="1268460">wanted</span> <span m="1268580">to</span>
  <span m="1268700">maximize</span> <span m="1269290">something,</span> <span m="1269610">if
  we</span> <span m="1269730">wanted</span> <span m="1269920">to</span> <span m="1269990">maximize</span>
  <span m="1270560">range,</span> <span m="1271000">we</span> <span m="1271110">would</span>
  <span m="1271230">just</span> <span m="1271420">minimize</span> <span m="1271940">negative</span>
  <span m="1272250">range.</span> <span m="1273470">So</span> <span m="1273630">any</span>
  <span m="1273800">objective</span> <span m="1274140">that</span> <span m="1274250">you</span>
  <span m="1274340">want</span> <span m="1274460">to</span> <span m="1274520">maximize,</span>
  <span m="1275200">you''re</span> <span m="1275280">going</span> <span m="1275390">to</span>
  <span m="1275430">multiply</span> <span m="1275910">with</span> <span m="1276080">a</span>
  <span m="1276120">negative</span> <span m="1276470">sign</span> <span m="1276770">and</span>
  <span m="1276920">try</span> <span m="1277050">to</span> <span m="1277130">minimize</span>
  <span m="1277570">it.</span></p><p><span m="1278390">How</span> <span m="1278600">about</span>
  <span m="1279050">the</span> <span m="1279680">inequality</span> <span m="1280310">constraints</span>
  <span m="1281650">gj</span> <span m="1282030">less than</span> <span m="1282310">equal</span>
  <span m="1282590">0?</span> <span m="1283155">You can</span> <span m="1283410">always</span>
  <span m="1283730">just</span> <span m="1284050">rearrange it</span> <span m="1284420">and
  turn it</span> <span m="1284790">around,</span> <span m="1285180">right?</span>
  <span m="1285640">Multiply</span> <span m="1285840">by</span> <span m="1286030">minus</span>
  <span m="1286090">1</span> <span m="1286450">on this</span> <span m="1286550">one.</span>
  <span m="1286670">And</span> <span m="1286890">flip</span> <span m="1286970">the
  sign</span> <span m="1287230">if</span> <span m="1287360">it''s</span> <span m="1287730">a</span>
  <span m="1290020">greater</span> <span m="1290320">than or</span> <span m="1290440">equal
  to</span> <span m="1290820">sign.</span></p><p><span m="1291530">So</span> <span
  m="1291850">the</span> <span m="1292020">fact</span> <span m="1292240">that</span>
  <span m="1293050">we</span> <span m="1293160">wrote</span> <span m="1293350">this</span>
  <span m="1293470">as</span> <span m="1293530">a</span> <span m="1293610">minimization</span>
  <span m="1294320">and</span> <span m="1294410">with</span> <span m="1294530">these</span>
  <span m="1294700">guys</span> <span m="1294920">being</span> <span m="1295080">less  than</span>
  <span m="1295360">equal</span> <span m="1295620">0,</span> <span m="1295920">let''s</span>
  <span m="1295970">go</span> <span m="1296090">to</span> <span m="1296150">the</span>
  <span m="1296210">standard</span> <span m="1296700">form</span> <span m="1297050">that</span>
  <span m="1297570">for</span> <span m="1297700">the</span> <span m="1297780">nonlinear</span>
  <span m="1298270">optimization</span> <span m="1299160">problem.</span> <span m="1299440">It''s</span>
  <span m="1299550">sometimes</span> <span m="1299890">called</span> <span m="1300050">NLP</span>
  <span m="1300280">for</span> <span m="1300760">Nonlinear</span> <span m="1301340">Program.</span>
  <span m="1303800">But</span> <span m="1304000">you</span> <span m="1304090">can</span>
  <span m="1304230">always</span> <span m="1304720">get</span> <span m="1305010">your</span>
  <span m="1305340">problem</span> <span m="1305920">into</span> <span m="1306170">this</span>
  <span m="1307000">form.</span></p><p><span m="1309580">So</span> <span m="1310966">I
  forgot</span> <span m="1311430">to</span> <span m="1311740">scroll</span> <span
  m="1312260">through</span> <span m="1312440">this</span> <span m="1312670">thing.</span>
  <span m="1317080">OK.</span> <span m="1317450">So</span> <span m="1318760">let''s</span>
  <span m="1318980">see,</span> <span m="1319200">any</span> <span m="1320760">questions?</span>
  <span m="1321520">It''s</span> <span m="1321640">clear?</span> <span m="1324340">Mathematical</span>
  <span m="1325110">statement.</span> <span m="1326220">This</span> <span m="1326360">is</span>
  <span m="1326910">a</span> <span m="1326970">design</span> <span m="1327360">problem</span>
  <span m="1327700">written</span> <span m="1327980">as an</span> <span m="1328260">optimization</span>
  <span m="1328730">problem,</span> <span m="1329030">finding</span> <span m="1329430">the</span>
  <span m="1329840">xs</span> <span m="1330660">that</span> <span m="1331070">minimize</span>
  <span m="1331540">my objective</span> <span m="1332225">while</span> <span m="1332570">satisfying</span>
  <span m="1333090">the</span> <span m="1333170">constraints.</span> <span m="1334750">And</span>
  <span m="1337490">that</span> <span m="1337630">will</span> <span m="1337720">be
  a</span> <span m="1337830">good</span> <span m="1338010">design.</span></p><p><span
  m="1342620">All right.</span> <span m="1342940">So</span> <span m="1343100">what</span>
  <span m="1343320">we''re</span> <span m="1343470">going</span> <span m="1343830">to</span>
  <span m="1344970">talk</span> <span m="1345260">about</span> <span m="1345560">now</span>
  <span m="1345980">are</span> <span m="1347280">how</span> <span m="1348280">we</span>
  <span m="1348780">might</span> <span m="1353520">go</span> <span m="1353670">about</span>
  <span m="1354000">solving</span> <span m="1355460">this</span> <span m="1355660">problem.</span>
  <span m="1358160">So</span> <span m="1363390">this</span> <span m="1363500">is</span>
  <span m="1363600">number</span> <span m="1363860">two.</span> <span m="1364450">And</span>
  <span m="1365200">I''m</span> <span m="1365880">going</span> <span m="1366010">to</span>
  <span m="1366080">focus</span> <span m="1366520">mostly</span> <span m="1366990">on</span>
  <span m="1367390">unconstrained</span> <span m="1368080">optimization</span> <span
  m="1368760">problems.</span> <span m="1369710">I''ll</span> <span m="1371610">talk</span>
  <span m="1371910">a</span> <span m="1371950">little</span> <span m="1372170">bit</span>
  <span m="1372290">about</span> <span m="1372550">how to</span> <span m="1372932">handle</span>
  <span m="1373314">the</span> <span m="1373696">constraints</span> <span m="1374080">maybe</span>
  <span m="1374340">in</span> <span m="1374440">the</span> <span m="1374510">next</span>
  <span m="1374800">lecture--</span> <span m="1375920">so</span> <span m="1376070">unconstrained</span>
  <span m="1376620">optimization.</span></p><p><span m="1378750">So</span> <span m="1381370">many</span>
  <span m="1381630">or</span> <span m="1381890">most--</span> <span m="1383270">so</span>
  <span m="1383430">let''s</span> <span m="1383630">say</span> <span m="1383740">many</span>
  <span m="1385320">optimization</span> <span m="1386120">algorithms,</span> <span
  m="1390200">in</span> <span m="1390310">fact,</span> <span m="1390470">almost</span>
  <span m="1390870">all</span> <span m="1391110">optimization</span> <span m="1391700">algorithms</span>
  <span m="1392020">are</span> <span m="1392340">iterative--</span> <span m="1398590">[INAUDIBLE]--</span>
  <span m="1399410">which</span> <span m="1400980">means</span> <span m="1401220">that</span>
  <span m="1401370">we''re</span> <span m="1401500">going</span> <span m="1401690">to</span>
  <span m="1401780">iterate</span> <span m="1402960">to</span> <span m="1403300">try</span>
  <span m="1403640">to solve</span> <span m="1403980">this</span> <span m="1404150">problem.</span>
  <span m="1404710">So what</span> <span m="1405075">do I mean by</span> <span m="1405440">that?</span>
  <span m="1405650">We''re</span> <span m="1405740">going</span> <span m="1405860">to</span>
  <span m="1405920">have</span> <span m="1406050">a</span> <span m="1406458">guess</span>
  <span m="1406866">for x.</span> <span m="1408090">We''re</span> <span m="1408180">going</span>
  <span m="1408300">to</span> <span m="1408360">update</span> <span m="1408830">that</span>
  <span m="1408960">guess</span> <span m="1409210">in</span> <span m="1409320">some</span>
  <span m="1409530">way.</span> <span m="1409710">And</span> <span m="1409810">we''re</span>
  <span m="1409900">going</span> <span m="1410030">to</span> <span m="1410100">keep</span>
  <span m="1410310">iterating,</span> <span m="1410820">keep</span> <span m="1411010">updating</span>
  <span m="1411410">the</span> <span m="1411490">guess for</span> <span m="1411800">x,</span>
  <span m="1412260">get a new guess for x,</span> <span m="1412720">new guess</span>
  <span m="1413180">for x,</span> <span m="1413640">new guess for x</span> <span m="1414560">until</span>
  <span m="1415360">we</span> <span m="1415510">think</span> <span m="1415800">we''ve</span>
  <span m="1415950">solved</span> <span m="1416980">this</span> <span m="1417240">problem.</span></p><p><span
  m="1418590">And</span> <span m="1419050">the</span> <span m="1419120">way</span>
  <span m="1419460">that</span> <span m="1419660">we</span> <span m="1419820">can</span>
  <span m="1420020">write</span> <span m="1422130">the</span> <span m="1422230">kinds</span>
  <span m="1422500">of</span> <span m="1422600">optimizations</span> <span m="1422975">algorithms</span>
  <span m="1423350">we''re</span> <span m="1423420">going</span> <span m="1423540">to</span>
  <span m="1423610">talk</span> <span m="1423860">about</span> <span m="1424720">is</span>
  <span m="1424960">that</span> <span m="1425310">xq</span> <span m="1428485">is</span>
  <span m="1428930">equal</span> <span m="1429260">to</span> <span m="1430480">x</span>
  <span m="1430940">q</span> <span m="1431140">minus</span> <span m="1431520">1</span>
  <span m="1433020">plus</span> <span m="1434010">alpha</span> <span m="1434490">q</span>
  <span m="1436230">times</span> <span m="1437155">xq.</span> <span m="1440420">And</span>
  <span m="1440570">this</span> <span m="1440690">is</span> <span m="1440780">going</span>
  <span m="1440900">to</span> <span m="1441000">be</span> <span m="1441110">true</span>
  <span m="1441550">for</span> <span m="1441840">q</span> <span m="1442160">equal</span>
  <span m="1442710">1,</span> <span m="1443100">2,</span> <span m="1443852">up</span>
  <span m="1444230">to</span> <span m="1444270">however</span> <span m="1444560">many</span>
  <span m="1444760">iterations</span> <span m="1445200">we have.</span> <span m="1446480">OK.</span>
  <span m="1446790">So</span> <span m="1446950">what</span> <span m="1447070">are</span>
  <span m="1447130">all</span> <span m="1447400">these</span> <span m="1447710">symbols?</span></p><p><span
  m="1448260">So</span> <span m="1448410">first of all,</span> <span m="1448890">q</span>
  <span m="1449100">is</span> <span m="1449380">going</span> <span m="1449570">to</span>
  <span m="1449640">be</span> <span m="1450580">the</span> <span m="1450690">iteration</span>
  <span m="1451230">number.</span> <span m="1454960">So</span> <span m="1455190">the</span>
  <span m="1455310">superscript</span> <span m="1457390">q</span> <span m="1457730">here</span>
  <span m="1458140">denotes</span> <span m="1458950">our</span> <span m="1459180">guess</span>
  <span m="1460100">for</span> <span m="1460600">whatever</span> <span m="1460950">quantity</span>
  <span m="1462033">or</span> <span m="1462386">our value</span> <span m="1462740">for</span>
  <span m="1462900">whatever</span> <span m="1463070">quantity</span> <span m="1464590">on</span>
  <span m="1464800">iteration</span> <span m="1465250">q.</span> <span m="1466160">And</span>
  <span m="1466390">specifically,</span> <span m="1467805">xq</span> <span m="1469430">is</span>
  <span m="1469640">going</span> <span m="1469780">to</span> <span m="1469860">be</span>
  <span m="1470070">our</span> <span m="1470910">guess</span> <span m="1472710">for</span>
  <span m="1474152">x</span> <span m="1475940">on</span> <span m="1476210">iteration</span>
  <span m="1476670">q.</span> <span m="1478044">OK.</span> <span m="1478502">So it''s</span>
  <span m="1478960">our</span> <span m="1479418">current</span> <span m="1481250">guess</span>
  <span m="1481620">for</span> <span m="1482057">the</span> <span m="1484242">design</span>
  <span m="1484680">variables.</span></p><p><span m="1486300">And</span> <span m="1486650">what</span>
  <span m="1486790">you</span> <span m="1486860">can</span> <span m="1487050">see</span>
  <span m="1487400">is</span> <span m="1487600">that</span> <span m="1488720">the</span>
  <span m="1488800">guess</span> <span m="1489240">on</span> <span m="1489420">iteration</span>
  <span m="1489900">q</span> <span m="1490710">is</span> <span m="1490900">going</span>
  <span m="1491080">to</span> <span m="1491160">be</span> <span m="1491260">given</span>
  <span m="1491630">by</span> <span m="1492650">the</span> <span m="1492750">guess</span>
  <span m="1493060">of</span> <span m="1493120">the</span> <span m="1493180">design</span>
  <span m="1493470">variables</span> <span m="1493850">on</span> <span m="1494260">t</span>
  <span m="1494460">minus</span> <span m="1494770">1,</span> <span m="1495110">so</span>
  <span m="1495220">what</span> <span m="1495350">we</span> <span m="1495470">had</span>
  <span m="1495640">before,</span> <span m="1496760">plus</span> <span m="1497050">this</span>
  <span m="1497340">update</span> <span m="1497650">turn.</span> <span m="1498880">And</span>
  <span m="1498990">this</span> <span m="1499130">update</span> <span m="1499520">turn</span>
  <span m="1499800">is</span> <span m="1499830">about</span> <span m="1500070">a</span>
  <span m="1500170">scalar</span> <span m="1501600">alpha</span> <span m="1501960">q.</span>
  <span m="1502900">And</span> <span m="1503370">it''s</span> <span m="1503490">got</span>
  <span m="1503660">a</span> <span m="1503690">vector</span> <span m="1504930">Sq.</span>
  <span m="1506562">So</span> <span m="1507030">let me</span> <span m="1507400">explain
  it,</span> <span m="1507530">and then we</span> <span m="1507730">can</span> <span
  m="1507870">write</span> <span m="1508040">it</span> <span m="1508140">down.</span></p><p><span
  m="1509070">This</span> <span m="1509240">thing</span> <span m="1509410">here</span>
  <span m="1509710">is</span> <span m="1509870">called the</span> <span m="1510180">search</span>
  <span m="1510720">direction.</span> <span m="1512440">And</span> <span m="1512570">this
  thing</span> <span m="1512870">here</span> <span m="1513050">is</span> <span m="1513150">going</span>
  <span m="1513270">to</span> <span m="1513340">be</span> <span m="1513510">out</span>
  <span m="1514320">scalar</span> <span m="1514430">[INAUDIBLE].</span> <span m="1515810">So</span>
  <span m="1515910">again,</span> <span m="1516120">what</span> <span m="1516220">I</span>
  <span m="1516270">want</span> <span m="1516440">you</span> <span m="1516600">to</span>
  <span m="1516670">do</span> <span m="1516840">is</span> <span m="1516980">I want</span>
  <span m="1517090">you to</span> <span m="1517210">picture</span> <span m="1517420">the</span>
  <span m="1517550">design</span> <span m="1517880">space as</span> <span m="1518180">being</span>
  <span m="1518340">like</span> <span m="1518500">a</span> <span m="1518550">landscape.</span>
  <span m="1519480">Right?</span> <span m="1519740">So</span> <span m="1519830">that''s</span>
  <span m="1520010">the</span> <span m="1520090">xs.</span></p><p><span m="1520610">And</span>
  <span m="1520710">again,</span> <span m="1523140">the</span> <span m="1523260">height</span>
  <span m="1523470">of</span> <span m="1523530">the</span> <span m="1523600">landscape</span>
  <span m="1524190">is</span> <span m="1524350">going</span> <span m="1524540">to</span>
  <span m="1524610">be</span> <span m="1525140">a</span> <span m="1525220">measure</span>
  <span m="1525520">of</span> <span m="1525710">j.</span> <span m="1526790">So</span>
  <span m="1526970">I''m</span> <span m="1527070">standing</span> <span m="1527540">in</span>
  <span m="1527630">the</span> <span m="1527710">landscape.</span> <span m="1529020">And</span>
  <span m="1529230">I''m</span> <span m="1529340">standing</span> <span m="1530280">at</span>
  <span m="1530910">point</span> <span m="1531270">x</span> <span m="1531565">q minus
  1.</span> <span m="1532180">We</span> <span m="1532270">can</span> <span m="1532410">[INAUDIBLE]</span>
  <span m="1532890">q equal</span> <span m="1533010">1.</span> <span m="1533370">So
  I''m</span> <span m="1533580">standing</span> <span m="1533970">at</span> <span
  m="1534060">a</span> <span m="1534110">point</span> <span m="1534410">x0.</span>
  <span m="1535630">And</span> <span m="1535750">I</span> <span m="1535790">want</span>
  <span m="1535960">to</span> <span m="1536060">figure</span> <span m="1536330">out</span>
  <span m="1536470">a</span> <span m="1536690">way to go.</span></p><p><span m="1537626">I''m
  going</span> <span m="1538000">to take</span> <span m="1538170">a</span> <span m="1538210">step.</span>
  <span m="1538495">I''m going to</span> <span m="1538780">move</span> <span m="1539280">in</span>
  <span m="1539360">the</span> <span m="1539430">landscape</span> <span m="1540490">to</span>
  <span m="1540630">get</span> <span m="1540790">my</span> <span m="1540920">next</span>
  <span m="1541210">one,</span> <span m="1541500">to get</span> <span m="1541640">my</span>
  <span m="1541790">x1.</span> <span m="1543100">And</span> <span m="1543260">the</span>
  <span m="1543320">way</span> <span m="1543580">I</span> <span m="1544560">move</span>
  <span m="1545140">is</span> <span m="1545320">that</span> <span m="1546120">first</span>
  <span m="1546350">of</span> <span m="1546440">all,</span> <span m="1546650">I''m</span>
  <span m="1546750">to</span> <span m="1546810">pick</span> <span m="1547030">a</span>
  <span m="1547100">direction</span> <span m="1547900">to</span> <span m="1548030">move</span>
  <span m="1548310">in.</span> <span m="1549270">So</span> <span m="1549390">if</span>
  <span m="1549640">q</span> <span m="1549920">is</span> <span m="1550120">my</span>
  <span m="1551020">search</span> <span m="1551470">direction,</span> <span m="1552030">so
  first</span> <span m="1552140">of all,</span> <span m="1552280">I''m going</span>
  <span m="1552430">to</span> <span m="1552590">look</span> <span m="1552770">around.</span>
  <span m="1553090">I''m</span> <span m="1553150">going</span> <span m="1553270">to</span>
  <span m="1553480">pick a</span> <span m="1553650">direction</span> <span m="1554090">to</span>
  <span m="1554190">move</span> <span m="1554430">in.</span></p><p><span m="1555170">And</span>
  <span m="1555310">maybe</span> <span m="1555630">you</span> <span m="1555770">have</span>
  <span m="1556350">some</span> <span m="1556480">intuition</span> <span m="1556950">that</span>
  <span m="1557060">if</span> <span m="1557160">I''m</span> <span m="1557300">trying</span>
  <span m="1557440">to</span> <span m="1557500">minimize</span> <span m="1557980">something,</span>
  <span m="1558810">I''m</span> <span m="1558960">going</span> <span m="1559080">to</span>
  <span m="1559230">try</span> <span m="1559460">to</span> <span m="1559550">pick</span>
  <span m="1559680">a</span> <span m="1559720">downhill</span> <span m="1560210">direction,</span>
  <span m="1560700">right?</span> <span m="1561386">So</span> <span m="1561730">I''m</span>
  <span m="1561880">looking</span> <span m="1562130">for</span> <span m="1562360">a</span>
  <span m="1563130">bottom</span> <span m="1563420">of</span> <span m="1563500">a</span>
  <span m="1563570">valley.</span> <span m="1564450">I''m</span> <span m="1564590">standing</span>
  <span m="1564930">at</span> <span m="1564990">a</span> <span m="1565020">point</span>
  <span m="1565220">in</span> <span m="1565280">the</span> <span m="1565330">landscape</span>
  <span m="1565900">I</span> <span m="1565960">might</span> <span m="1566190">want</span>
  <span m="1566340">to</span> <span m="1566750">walk</span> <span m="1567020">downhill.</span>
  <span m="1568640">So</span> <span m="1568780">I''m going</span> <span m="1568900">to</span>
  <span m="1568930">pick</span> <span m="1569100">a</span> <span m="1569150">direction</span>
  <span m="1569430">Sq.</span></p><p><span m="1570510">And</span> <span m="1570620">then</span>
  <span m="1570680">once</span> <span m="1570940">I''ve</span> <span m="1571100">picked</span>
  <span m="1571300">my</span> <span m="1571440">direction,</span> <span m="1572100">I</span>
  <span m="1572190">want</span> <span m="1572330">to</span> <span m="1572390">figure</span>
  <span m="1572650">out</span> <span m="1572900">how</span> <span m="1573190">far</span>
  <span m="1573530">to</span> <span m="1573660">walk</span> <span m="1573960">in</span>
  <span m="1574040">that</span> <span m="1574260">direction.</span> <span m="1575280">And</span>
  <span m="1575390">that''s</span> <span m="1575630">the</span> <span m="1575950">alpha</span>
  <span m="1576040">q.</span> <span m="1576465">So</span> <span m="1577740">the</span>
  <span m="1577960">Sq</span> <span m="1578180">is</span> <span m="1578310">the</span>
  <span m="1578410">direction.</span> <span m="1578920">And</span> <span m="1579010">then</span>
  <span m="1579100">alpha</span> <span m="1579290">q</span> <span m="1579550">is</span>
  <span m="1579710">going to be</span> <span m="1579790">the</span> <span m="1579870">size</span>
  <span m="1580280">of</span> <span m="1580380">step.</span></p><p><span m="1581440">So</span>
  <span m="1581570">this</span> <span m="1581720">is</span> <span m="1581770">scalar</span>
  <span m="1582270">in</span> <span m="1582530">that</span> <span m="1582670">direction.</span>
  <span m="1584100">So standing</span> <span m="1584360">in</span> <span m="1584440">the</span>
  <span m="1584510">landscape,</span> <span m="1585020">pick</span> <span m="1585190">a</span>
  <span m="1585240">direction.</span> <span m="1586400">Take</span> <span m="1586500">a</span>
  <span m="1586550">step</span> <span m="1586960">[INAUDIBLE]</span> <span m="1587600">alpha</span>
  <span m="1587940">q.</span> <span m="1588295">So that</span> <span m="1588650">gets</span>
  <span m="1588860">me</span> <span m="1589040">to</span> <span m="1589250">the</span>
  <span m="1589330">new</span> <span m="1589610">point</span> <span m="1589930">in
  the</span> <span m="1590050">landscape.</span> <span m="1591320">Then</span> <span
  m="1591510">I''m</span> <span m="1591570">going</span> <span m="1591690">to</span>
  <span m="1591760">stop,</span> <span m="1592140">and</span> <span m="1592240">I''m</span>
  <span m="1592300">going</span> <span m="1592420">to</span> <span m="1592490">look</span>
  <span m="1592690">around.</span></p><p><span m="1593600">I''m going</span> <span
  m="1594010">to find a</span> <span m="1594110">new</span> <span m="1594270">direction.</span>
  <span m="1595380">And</span> <span m="1595550">I''m</span> <span m="1595650">going</span>
  <span m="1595800">to</span> <span m="1595880">do the</span> <span m="1595960">same</span>
  <span m="1596200">thing,</span> <span m="1596710">figure</span> <span m="1596960">out</span>
  <span m="1597030">how</span> <span m="1597200">far to walk.</span> <span m="1597790">We''re
  just</span> <span m="1598100">going</span> <span m="1598230">to</span> <span m="1598300">keep</span>
  <span m="1598540">walking</span> <span m="1599180">around</span> <span m="1599570">the</span>
  <span m="1599640">landscape</span> <span m="1600300">picking</span> <span m="1600550">directions</span>
  <span m="1601350">and</span> <span m="1601830">figuring</span> <span m="1602260">out</span>
  <span m="1602540">how</span> <span m="1602850">far</span> <span m="1603100">to</span>
  <span m="1603210">walk</span> <span m="1603490">in</span> <span m="1603600">those</span>
  <span m="1603810">directions.</span></p><p><span m="1606500">OK.</span> <span m="1606940">And
  of</span> <span m="1606990">course,</span> <span m="1608160">then</span> <span m="1608340">the</span>
  <span m="1608430">trick</span> <span m="1608650">comes.</span> <span m="1608930">How</span>
  <span m="1609560">do</span> <span m="1609630">you</span> <span m="1609740">this?</span>
  <span m="1610160">And</span> <span m="1610260">that''s</span> <span m="1610330">what</span>
  <span m="1610470">the</span> <span m="1610540">different</span> <span m="1610860">optimization</span>
  <span m="1611810">algorithms</span> <span m="1612480">do,</span> <span m="1612650">different</span>
  <span m="1612990">ways</span> <span m="1613320">of</span> <span m="1613550">picking</span>
  <span m="1614050">search</span> <span m="1614550">directions</span> <span m="1615550">and</span>
  <span m="1617050">steps.</span></p><p><span m="1619320">OK.</span> <span m="1619680">So</span>
  <span m="1620440">Sq</span> <span m="1622590">is,</span> <span m="1623780">again,</span>
  <span m="1624020">our</span> <span m="1624970">vector</span> <span m="1625070">search</span>
  <span m="1625390">direction.</span> <span m="1627200">So it''s</span> <span m="1627430">got</span>
  <span m="1627510">the</span> <span m="1627580">same</span> <span m="1627810">dimension</span>
  <span m="1628230">as</span> <span m="1631292">x.</span> <span m="1631760">Somebody
  is</span> <span m="1632210">smoking</span> <span m="1632500">out the window.</span>
  <span m="1633572">Do you guys</span> <span m="1634058">smell it?</span></p><p><span
  m="1643780">[INAUDIBLE]</span> <span m="1644485">[AUDIO OUT]</span> <span m="1645850">is</span>
  <span m="1649410">[AUDIO OUT]</span> <span m="1655970">[INAUDIBLE]</span> <span
  m="1661283">q</span> <span m="1663220">and</span> <span m="1663510">alpha q</span>
  <span m="1663800">is a</span> <span m="1664170">strong</span> <span m="1664320">consideration,</span>
  <span m="1664725">too.</span> <span m="1670870">And</span> <span m="1671170">then
  the</span> <span m="1671270">other</span> <span m="1671400">thing</span> <span m="1671590">we''re</span>
  <span m="1671660">also</span> <span m="1671870">going</span> <span m="1672000">to</span>
  <span m="1672060">need</span> <span m="1672570">is</span> <span m="1672780">we''re</span>
  <span m="1672920">going to</span> <span m="1672960">need</span> <span m="1674300">an</span>
  <span m="1674530">x0,</span> <span m="1676240">which</span> <span m="1676590">is</span>
  <span m="1676650">going</span> <span m="1676770">to</span> <span m="1676840">be</span>
  <span m="1677060">our</span> <span m="1677280">initial</span> <span m="1677600">guess,</span>
  <span m="1678292">all</span> <span m="1678640">right?</span> <span m="1678900">So</span>
  <span m="1679010">we''re always</span> <span m="1679210">going</span> <span m="1679350">to</span>
  <span m="1679410">have</span> <span m="1679540">to</span> <span m="1679650">initialize</span>
  <span m="1680270">from</span> <span m="1680560">some</span> <span m="1681200">x0,</span>
  <span m="1682370">so</span> <span m="1682480">that</span> <span m="1682590">we</span>
  <span m="1682700">can</span> <span m="1682890">start</span> <span m="1683150">this</span>
  <span m="1683290">whole</span> <span m="1683440">process</span> <span m="1684245">of</span>
  <span m="1684640">walking</span> <span m="1685035">through</span> <span m="1685430">the</span>
  <span m="1685550">design</span> <span m="1685980">space.</span></p><p><span m="1689940">OK.</span>
  <span m="1706930">It''s</span> <span m="1707080">very</span> <span m="1707760">[INAUDIBLE]</span>
  <span m="1707960">wavy.</span> <span m="1708860">Actually,</span> <span m="1709280">that''s</span>
  <span m="1709700">a</span> <span m="1710120">[AUDIO OUT]</span> <span m="1713890">satisfy</span>
  <span m="1714060">this</span> <span m="1714180">problem.</span> <span m="1722050">[AUDIO
  OUT]</span> <span m="1725002">You can</span> <span m="1725790">[AUDIO OUT]</span>
  <span m="1726470">make</span> <span m="1726750">guarantees</span> <span m="1727640">about</span>
  <span m="1728640">whether</span> <span m="1729040">the</span> <span m="1730040">final</span>
  <span m="1730360">x that</span> <span m="1730710">comes</span> <span m="1730940">out</span>
  <span m="1731050">after you</span> <span m="1731525">iterate</span> <span m="1732950">satisfies</span>
  <span m="1735290">the</span> <span m="1735450">assumptions</span> <span m="1735760">[AUDIO
  OUT].</span> <span m="1738580">So there</span> <span m="1738930">are things</span>
  <span m="1739190">that</span> <span m="1739656">[AUDIO OUT]</span> <span m="1755210">[INAUDIBLE]</span>
  <span m="1757320">has</span> <span m="1757450">to</span> <span m="1757520">be</span>
  <span m="1757600">true.</span> <span m="1760160">So</span> <span m="1760320">[AUDIO
  OUT]</span> <span m="1761560">I just</span> <span m="1761670">want</span> <span
  m="1761790">to</span> <span m="1761850">minimize</span> <span m="1762380">j of x.</span>
  <span m="1762630">Forget</span> <span m="1762970">about</span> <span m="1763230">[INAUDIBLE].</span>
  <span m="1764146">It has</span> <span m="1764510">to be</span> <span m="1764720">true.</span></p><p><span
  m="1766800">Yeah,</span> <span m="1766980">what''s</span> <span m="1767170">that</span>
  <span m="1767370">mathematical</span> <span m="1767670">condition?</span> <span
  m="1770510">What has</span> <span m="1770760">to</span> <span m="1770830">be</span>
  <span m="1770910">there?</span> <span m="1772124">Yeah,</span> <span m="1772606">[INAUDIBLE].</span>
  <span m="1774534">[AUDIO OUT]</span> <span m="1781780">[INAUDIBLE]</span> <span
  m="1785110">depending</span> <span m="1785500">on</span> <span m="1786025">[AUDIO
  OUT],</span> <span m="1786670">we</span> <span m="1786940">can</span> <span m="1787370">guarantees</span>
  <span m="1787720">about</span> <span m="1788040">[AUDIO OUT]</span> <span m="1802030">additional</span>
  <span m="1802450">[INAUDIBLE]</span> <span m="1802650">that</span> <span m="1802780">you</span>
  <span m="1802880">need</span> <span m="1804230">[INAUDIBLE]</span> <span m="1804510">derivative</span>
  <span m="1805110">has</span> <span m="1805280">to</span> <span m="1805370">be</span>
  <span m="1805680">positive</span> <span m="1806370">for</span> <span m="1806470">a</span>
  <span m="1806530">minimum.</span></p><p><span m="1807420">And</span> <span m="1807530">we''ll</span>
  <span m="1807785">talk about</span> <span m="1808040">what that</span> <span m="1808190">means,</span>
  <span m="1808500">because</span> <span m="1808740">this</span> <span m="1808870">is</span>
  <span m="1808930">a</span> <span m="1809285">vector</span> <span m="1809640">[INAUDIBLE].</span>
  <span m="1810945">So</span> <span m="1811380">I call</span> <span m="1811815">these</span>
  <span m="1812250">S''s.</span> <span m="1812690">I</span> <span m="1812770">mean,</span>
  <span m="1812900">they''re</span> <span m="1813393">iterates.</span> <span m="1814380">They''re</span>
  <span m="1814630">on</span> <span m="1814800">the</span> <span m="1814880">way.</span>
  <span m="1815270">And</span> <span m="1815370">again,</span> <span m="1815600">depending</span>
  <span m="1815880">on</span> <span m="1815950">the</span> <span m="1816010">what</span>
  <span m="1816180">algorithm</span> <span m="1816380">we</span> <span m="1816520">use,</span>
  <span m="1817030">we</span> <span m="1817190">will</span> <span m="1817770">get</span>
  <span m="1818010">to</span> <span m="1818320">at</span> <span m="1818390">least</span>
  <span m="1818660">a</span> <span m="1819390">solution</span> <span m="1819710">of</span>
  <span m="1819780">that problem.</span></p><p><span m="1823060">I</span> <span m="1825210">want</span>
  <span m="1825360">to--</span> <span m="1827825">that''s strange--</span> <span m="1828775">I
  want to</span> <span m="1829250">show</span> <span m="1829470">you</span> <span
  m="1832535">this idea.</span> <span m="1843228">It''s a little</span> <span m="1843696">MATLAB</span>
  <span m="1844164">demo.</span> <span m="1846510">Because</span> <span m="1846800">I</span>
  <span m="1846850">think</span> <span m="1847040">it will</span> <span m="1847295">help
  you</span> <span m="1847550">think</span> <span m="1847750">about</span> <span m="1848310">some</span>
  <span m="1848430">of</span> <span m="1848490">the</span> <span m="1848580">issues.</span></p><p><span
  m="1848860">And then we''ll</span> <span m="1848970">start</span> <span m="1849450">talking</span>
  <span m="1849840">about</span> <span m="1851140">how</span> <span m="1851750">we</span>
  <span m="1852090">actually</span> <span m="1852490">can--</span> <span m="1854655">well,
  we''ll</span> <span m="1855090">talk</span> <span m="1855200">about</span> <span
  m="1856875">some</span> <span m="1857360">of the</span> <span m="1857530">mathematical</span>
  <span m="1858030">quantities</span> <span m="1858380">that</span> <span m="1858480">we''re</span>
  <span m="1858560">going</span> <span m="1858680">to</span> <span m="1858740">need</span>
  <span m="1859230">to</span> <span m="1859320">be</span> <span m="1859420">able</span>
  <span m="1859700">to</span> <span m="1859990">compute these</span> <span m="1860480">alphas</span>
  <span m="1860820">and</span> <span m="1860950">S''s.</span> <span m="1861000">And</span>
  <span m="1861370">then</span> <span m="1861470">we''ll</span> <span m="1861560">talk</span>
  <span m="1861720">about</span> <span m="1861930">the</span> <span m="1861960">different</span>
  <span m="1862250">methods</span> <span m="1862540">and</span> <span m="1862650">how</span>
  <span m="1863150">they</span> <span m="1863270">do</span> <span m="1863390">those.</span>
  <span m="1868450">So</span> <span m="1868680">[INAUDIBLE]</span> <span m="1869320">still</span>
  <span m="1874400">simple</span> <span m="1874720">[INAUDIBLE]</span> <span m="1875090">script</span>
  <span m="1875460">here</span> <span m="1875670">that</span> <span m="1875890">does</span>
  <span m="1876770">optimization.</span></p><p><span m="1879940">It</span> <span m="1880100">does</span>
  <span m="1880280">optimization</span> <span m="1881000">on</span> <span m="1881230">the</span>
  <span m="1881300">function.</span> <span m="1881710">This is the</span> <span m="1881770">peak</span>
  <span m="1882160">function</span> <span m="1882455">in</span> <span m="1882750">MATLAB.</span>
  <span m="1883730">So</span> <span m="1884790">this</span> <span m="1884920">is</span>
  <span m="1885000">the</span> <span m="1885090">landscape.</span> <span m="1886110">There</span>
  <span m="1886240">are</span> <span m="1886300">two</span> <span m="1886510">design</span>
  <span m="1886850">variables.</span></p><p><span m="1887210">Here,</span> <span m="1887350">they''re</span>
  <span m="1887440">called</span> <span m="1887670">x</span> <span m="1887990">and
  y.</span> <span m="1888330">So this</span> <span m="1888470">is</span> <span m="1888570">x1</span>
  <span m="1888660">and</span> <span m="1889100">x2.</span> <span m="1890200">And</span>
  <span m="1890390">this</span> <span m="1890480">is</span> <span m="1890680">j</span>
  <span m="1891610">on</span> <span m="1892040">the</span> <span m="1893570">vertical</span>
  <span m="1893940">axis.</span> <span m="1894320">So this</span> <span m="1894510">is</span>
  <span m="1894600">the</span> <span m="1894720">objective.</span></p><p><span m="1895385">And</span>
  <span m="1895710">we''re</span> <span m="1895850">going</span> <span m="1895970">to</span>
  <span m="1896030">try</span> <span m="1896150">to</span> <span m="1896220">maximize</span>
  <span m="1896820">just</span> <span m="1896970">because</span> <span m="1897170">it''s</span>
  <span m="1897280">easier</span> <span m="1897590">to</span> <span m="1897660">see</span>
  <span m="1897880">what''s</span> <span m="1898130">going</span> <span m="1898430">on</span>
  <span m="1898680">with</span> <span m="1898840">maximizing.</span> <span m="1899960">So</span>
  <span m="1900120">we''ve</span> <span m="1900170">asked</span> <span m="1900640">[INAUDIBLE]</span>
  <span m="1900930">constraint</span> <span m="1901305">to</span> <span m="1901680">[INAUDIBLE]</span>
  <span m="1901950">an</span> <span m="1902130">unconstrained</span> <span m="1902830">problem,</span>
  <span m="1903650">we''ve</span> <span m="1903960">asked</span> <span m="1904380">the</span>
  <span m="1904510">optimizer</span> <span m="1905080">to</span> <span m="1905220">find</span>
  <span m="1906020">the</span> <span m="1906140">design</span> <span m="1906790">vector</span>
  <span m="1907130">x,</span> <span m="1907640">which</span> <span m="1907830">in</span>
  <span m="1907900">this</span> <span m="1908040">case</span> <span m="1908240">is</span>
  <span m="1908380">xy,</span> <span m="1908765">two</span> <span m="1909150">components,</span>
  <span m="1910150">that</span> <span m="1910600">maximizes</span> <span m="1912210">the</span>
  <span m="1912320">objective</span> <span m="1912730">j</span> <span m="1913230">where</span>
  <span m="1913430">the</span> <span m="1913500">height</span> <span m="1913810">and</span>
  <span m="1914020">the color</span> <span m="1918870">are the</span> <span m="1918990">measure</span>
  <span m="1919430">of</span> <span m="1919600">j.</span> <span m="1920260">And</span>
  <span m="1920390">this</span> <span m="1920670">little</span> <span m="1921050">asterisk</span>
  <span m="1921550">sitting here</span> <span m="1921990">is</span> <span m="1922450">the</span>
  <span m="1922560">initial</span> <span m="1922850">guess</span> <span m="1923150">that</span>
  <span m="1923300">I</span> <span m="1923350">gave.</span></p><p><span m="1923670">When</span>
  <span m="1923930">I</span> <span m="1924020">called it,</span> <span m="1924400">I</span>
  <span m="1924470">gave</span> <span m="1924650">it an</span> <span m="1924770">initial</span>
  <span m="1925200">guess</span> <span m="1925641">of--</span> <span m="1926964">what
  did I</span> <span m="1927405">give it--</span> <span m="1928290">minus</span> <span
  m="1928650">1,</span> <span m="1928880">1.</span> <span m="1930920">OK.</span> <span
  m="1931230">So</span> <span m="1931490">this</span> <span m="1931670">is</span>
  <span m="1931760">x0.</span> <span m="1932560">And</span> <span m="1932760">I''m
  going to</span> <span m="1932940">start it</span> <span m="1933280">running</span>
  <span m="1933520">in</span> <span m="1933610">a</span> <span m="1933640">second.</span>
  <span m="1933950">And what</span> <span m="1934160">you''re</span> <span m="1934250">going</span>
  <span m="1934380">to</span> <span m="1934440">see</span> <span m="1934910">is</span>
  <span m="1935310">a</span> <span m="1935810">sequence</span> <span m="1936150">of</span>
  <span m="1936250">little</span> <span m="1936570">asterisk.</span> <span m="1937485">And</span>
  <span m="1937910">each</span> <span m="1938260">asterisk</span> <span m="1939170">is</span>
  <span m="1939420">a</span> <span m="1939540">new</span> <span m="1939990">guess</span>
  <span m="1940290">or</span> <span m="1940510">a</span> <span m="1940600">new</span>
  <span m="1940860">iterate.</span></p><p><span m="1941220">So</span> <span m="1941580">this</span>
  <span m="1941740">is</span> <span m="1941850">x0.</span> <span m="1942440">It''s</span>
  <span m="1942560">going to</span> <span m="1942620">compute</span> <span m="1943040">x1,</span>
  <span m="1943330">x2,</span> <span m="1944080">x3,</span> <span m="1944540">through
  the</span> <span m="1944760">script</span> <span m="1945540">all</span> <span m="1945780">the</span>
  <span m="1945850">way</span> <span m="1946200">until,</span> <span m="1946900">hopefully,</span>
  <span m="1948060">it''s</span> <span m="1948350">gets</span> <span m="1948500">up
  to</span> <span m="1948590">the</span> <span m="1948670">top</span> <span m="1948990">here.</span>
  <span m="1951330">So</span> <span m="1951750">we''ll</span> <span m="1951890">set</span>
  <span m="1952110">it</span> <span m="1952230">going.</span> <span m="1955880">And</span>
  <span m="1957730">you</span> <span m="1957900">can</span> <span m="1958120">see</span>
  <span m="1960250">it''s</span> <span m="1960870">doing</span> <span m="1961150">what</span>
  <span m="1961570">you</span> <span m="1961760">would</span> <span m="1961920">want</span>
  <span m="1962090">it to</span> <span m="1962230">do,</span> <span m="1962440">which</span>
  <span m="1962670">is</span> <span m="1962820">it was</span> <span m="1962980">asked</span>
  <span m="1963130">to</span> <span m="1963360">maximize.</span></p><p><span m="1964440">So
  it''s</span> <span m="1964640">looking</span> <span m="1964880">around.</span> <span
  m="1965200">It''s</span> <span m="1965330">picking</span> <span m="1965580">search</span>
  <span m="1965850">directions.</span> <span m="1966125">And</span> <span m="1966400">then
  it''s</span> <span m="1966670">deciding</span> <span m="1967510">how</span> <span
  m="1967680">far</span> <span m="1967920">to</span> <span m="1968000">step.</span>
  <span m="1968430">On</span> <span m="1968830">each</span> <span m="1969090">iteration,</span>
  <span m="1970060">it''s</span> <span m="1970180">moving</span> <span m="1970480">in</span>
  <span m="1970550">a</span> <span m="1970600">particular</span> <span m="1971170">direction</span>
  <span m="1971480">and</span> <span m="1971590">taking</span> <span m="1971830">a
  step.</span> <span m="1972660">And</span> <span m="1972770">you</span> <span m="1972840">can</span>
  <span m="1973010">see</span> <span m="1973210">that</span> <span m="1975800">it</span>
  <span m="1976480">gets</span> <span m="1976700">to</span> <span m="1976820">the</span>
  <span m="1977730">top</span> <span m="1977930">of</span> <span m="1978000">the</span>
  <span m="1978240">hole.</span></p><p><span m="1978500">So</span> <span m="1978630">this</span>
  <span m="1981250">is</span> <span m="1981330">an</span> <span m="1981420">optimization</span>
  <span m="1983430">method</span> <span m="1984130">that''s</span> <span m="1984310">called</span>
  <span m="1984740">Nelder-Mead</span> <span m="1984940">simplex.</span> <span m="1985460">And</span>
  <span m="1985570">I''ll</span> <span m="1986180">show</span> <span m="1986400">you</span>
  <span m="1986530">just</span> <span m="1986760">a</span> <span m="1986800">little</span>
  <span m="1987090">bit</span> <span m="1987610">about</span> <span m="1987860">it</span>
  <span m="1987950">later</span> <span m="1988190">on.</span> <span m="1988320">That''s</span>
  <span m="1988540">fminsearch</span> <span m="1989070">in</span> <span m="1989505">MATLAB.</span>
  <span m="1993114">And</span> <span m="1993511">we''ll</span> <span m="1993910">talk</span>
  <span m="1994070">in</span> <span m="1994240">the next lecture</span> <span m="1994530">about</span>
  <span m="1994920">how</span> <span m="1995030">to</span> <span m="1995110">call</span>
  <span m="1995405">the</span> <span m="1995700">MATLAB</span> <span m="1995840">optimization</span>
  <span m="1997250">functions,</span> <span m="1997630">because</span> <span m="1997950">they''re</span>
  <span m="1999000">really</span> <span m="1999300">powerful.</span> <span m="1999720">And</span>
  <span m="1999810">they</span> <span m="1999870">can</span> <span m="1999980">really</span>
  <span m="2000170">help</span> <span m="2000410">you</span> <span m="2000570">if</span>
  <span m="2000700">you''re</span> <span m="2001110">doing</span> <span m="2003550">design</span>
  <span m="2003810">problems.</span> <span m="2004330">But</span> <span m="2004540">that</span>
  <span m="2004660">one''s</span> <span m="2004800">fminsearch.</span> <span m="2005390">Do
  you want to</span> <span m="2005720">ask a question?</span> <span m="2006170">Yup.</span></p><p><span
  m="2007070">AUDIENCE: [INAUDIBLE]</span></p><p><span m="2008420">PROFESSOR: Yeah.</span>
  <span m="2008670">We''ll</span> <span m="2008870">do</span> <span m="2008940">that
  in</span> <span m="2009170">one</span> <span m="2009430">second.</span> <span m="2010040">Yeah.</span>
  <span m="2011860">I just</span> <span m="2012040">want</span> <span m="2012200">to</span>
  <span m="2012270">show</span> <span m="2012500">you</span> <span m="2014220">this--</span>
  <span m="2015620">oops--</span> <span m="2016510">still</span> <span m="2017040">running.</span>
  <span m="2019314">Hang on.</span> <span m="2020200">So</span> <span m="2020320">it''s</span>
  <span m="2020430">still</span> <span m="2020630">going.</span> <span m="2022150">So</span>
  <span m="2022310">fminsearches,</span> <span m="2023280">you''ll</span> <span m="2023570">see</span>
  <span m="2023830">it--</span> <span m="2024050">where</span> <span m="2024515">is</span>
  <span m="2024980">[INAUDIBLE]?</span> <span m="2026375">It''s</span> <span m="2026840">interesting</span>
  <span m="2027220">that</span> <span m="2027330">it''s</span> <span m="2027440">still</span>
  <span m="2027600">running.</span></p><p><span m="2028510">So</span> <span m="2028570">fminsearch,</span>
  <span m="2031630">this</span> <span m="2031760">is</span> <span m="2031850">why
  you</span> <span m="2032010">should always</span> <span m="2032265">put</span> <span
  m="2032630">maximum</span> <span m="2033600">iterations</span> <span m="2034120">in</span>
  <span m="2034280">your code.</span> <span m="2035270">Because</span> <span m="2035520">I''m</span>
  <span m="2035600">pretty</span> <span m="2035770">sure</span> <span m="2035960">it''s</span>
  <span m="2036060">at</span> <span m="2036140">the</span> <span m="2036210">top</span>
  <span m="2036400">of</span> <span m="2036470">the</span> <span m="2036560">hill,</span>
  <span m="2036860">but</span> <span m="2036980">the</span> <span m="2037040">[INAUDIBLE]</span>
  <span m="2037790">probably</span> <span m="2038110">fit</span> <span m="2038560">two</span>
  <span m="2038998">[INAUDIBLE].</span> <span m="2039436">Yup.</span></p><p><span
  m="2039874">AUDIENCE: [INAUDIBLE]</span></p><p><span m="2041190">PROFESSOR: No.</span>
  <span m="2041790">It</span> <span m="2041960">changes</span> <span m="2042400">each</span>
  <span m="2042620">iteration.</span> <span m="2043540">Yeah.</span> <span m="2044130">And</span>
  <span m="2044260">we''ll</span> <span m="2044350">talk</span> <span m="2044520">about</span>
  <span m="2044710">how</span> <span m="2045070">to</span> <span m="2045160">compute</span>
  <span m="2045640">it.</span> <span m="2046600">So</span> <span m="2046830">I</span>
  <span m="2046910">think</span> <span m="2047210">I''m</span> <span m="2047340">going</span>
  <span m="2047460">to</span> <span m="2047530">kill</span> <span m="2047800">that.</span>
  <span m="2048100">So</span> <span m="2048570">fminsearch is</span> <span m="2049460">actually--</span>
  <span m="2049690">it''s</span> <span m="2049810">called</span> <span m="2049909">a</span>
  <span m="2049989">Nelder-Mead</span> <span m="2050280">simplex.</span> <span m="2051992">It''s</span>
  <span m="2052449">kind</span> <span m="2052610">of</span> <span m="2052690">a</span>
  <span m="2052750">pattern</span> <span m="2053250">search.</span> <span m="2054199">So</span>
  <span m="2054330">it''s</span> <span m="2054480">sampling</span> <span m="2054830">the</span>
  <span m="2055030">design</span> <span m="2055179">space and</span> <span m="2055460">doing</span>
  <span m="2055650">a</span> <span m="2055710">pattern</span> <span m="2056000">search.</span></p><p><span
  m="2056190">And</span> <span m="2056280">we''ll</span> <span m="2056400">talk</span>
  <span m="2056630">about</span> <span m="2056850">that.</span> <span m="2057030">But</span>
  <span m="2057139">I also</span> <span m="2057290">just</span> <span m="2057570">want
  to--</span> <span m="2058776">oops,</span> <span m="2059460">not</span> <span m="2059590">that</span>
  <span m="2059719">one.</span> <span m="2063159">How</span> <span m="2063290">does</span>
  <span m="2063420">it</span> <span m="2063510">measure--</span> <span m="2064380">well,
  we''ll</span> <span m="2064510">talk</span> <span m="2064690">about</span> <span
  m="2064900">that</span> <span m="2065060">as well.</span> <span m="2065652">Yup,
  0.</span></p><p><span m="2068886">AUDIENCE: [INAUDIBLE]</span></p><p><span m="2070280">PROFESSOR:
  Nelder-Mead</span> <span m="2071659">simplex</span> <span m="2072020">is</span>
  <span m="2072170">the</span> <span m="2072239">method</span> <span m="2072679">that''s</span>
  <span m="2072889">implemented</span> <span m="2073400">in</span> <span m="2073710">fminsearch.</span>
  <span m="2077307">So</span> <span m="2077760">there''s</span> <span m="2077929">another</span>
  <span m="2078199">one--</span> <span m="2078500">oops,</span> <span m="2078929">now
  I''m</span> <span m="2079310">[INAUDIBLE]</span> <span m="2079349">the</span> <span
  m="2079389">wrong.</span> <span m="2079790">Actually,</span> <span m="2080580">[INAUDIBLE].</span>
  <span m="2081920">There''s</span> <span m="2082230">another</span> <span m="2082449">one</span>
  <span m="2082670">called</span> <span m="2082840">fminunc,</span> <span m="2083690">which</span>
  <span m="2083940">stands</span> <span m="2084290">for</span> <span m="2085540">minimization</span>
  <span m="2086239">unconstrained.</span> <span m="2088510">And</span> <span m="2088670">this</span>
  <span m="2088820">is</span> <span m="2088900">one</span> <span m="2089080">that</span>
  <span m="2089199">uses</span> <span m="2089500">gradient</span> <span m="2089860">information.</span></p><p><span
  m="2090380">And</span> <span m="2090489">again,</span> <span m="2090690">we''re</span>
  <span m="2090750">going</span> <span m="2090870">to</span> <span m="2090940">talk</span>
  <span m="2091150">about</span> <span m="2091960">how</span> <span m="2092130">that</span>
  <span m="2092340">works.</span> <span m="2094130">But</span> <span m="2094150">let</span>
  <span m="2094239">me</span> <span m="2094300">just</span> <span m="2094469">run</span>
  <span m="2094710">the</span> <span m="2094810">same,</span> <span m="2096330">so</span>
  <span m="2096480">you</span> <span m="2096570">can</span> <span m="2096730">see.</span>
  <span m="2096840">[INAUDIBLE]</span> <span m="2097550">after</span> <span m="2097880">49</span>
  <span m="2098450">iterations.</span> <span m="2098740">I don''t</span> <span m="2098850">know</span>
  <span m="2099040">why</span> <span m="2099290">it</span> <span m="2099380">was</span>
  <span m="2099560">continuing</span> <span m="2100520">to</span> <span m="2100680">go.</span>
  <span m="2102160">But</span> <span m="2102440">let''s</span> <span m="2102660">run</span>
  <span m="2102970">from</span> <span m="2103210">the</span> <span m="2103280">same</span>
  <span m="2103800">initial</span> <span m="2104160">condition.</span></p><p><span
  m="2115287">OK.</span> <span m="2116790">So it</span> <span m="2116910">takes</span>
  <span m="2117100">a</span> <span m="2117140">little</span> <span m="2117340">bit</span>
  <span m="2117500">longer</span> <span m="2117870">per</span> <span m="2119140">iteration.</span>
  <span m="2119670">But</span> <span m="2119830">did</span> <span m="2119950">you</span>
  <span m="2120020">see</span> <span m="2120240">how</span> <span m="2120560">it</span>
  <span m="2120710">basically</span> <span m="2121090">jumped</span> <span m="2122120">all</span>
  <span m="2122340">way</span> <span m="2122460">to</span> <span m="2122780">top of
  hill</span> <span m="2122840">in</span> <span m="2123010">the</span> <span m="2123080">second</span>
  <span m="2123350">iteration?</span> <span m="2124490">And</span> <span m="2124950">you''ll</span>
  <span m="2125310">see</span> <span m="2125460">it</span> <span m="2125540">when</span>
  <span m="2125630">we</span> <span m="2125710">talk</span> <span m="2125860">about</span>
  <span m="2126030">algorithms.</span> <span m="2126315">But</span> <span m="2126600">that''s</span>
  <span m="2126840">because</span> <span m="2127070">we</span> <span m="2127170">actually</span>
  <span m="2127380">computed</span> <span m="2127740">the</span> <span m="2127810">gradient</span>
  <span m="2128290">here</span> <span m="2129440">rather</span> <span m="2129700">than</span>
  <span m="2129880">just</span> <span m="2130070">sampling</span> <span m="2130600">locally,</span>
  <span m="2131050">which</span> <span m="2131220">is</span> <span m="2131310">what</span>
  <span m="2131490">now</span> <span m="2131680">the</span> <span m="2131770">Mead</span>
  <span m="2131990">simplex</span> <span m="2132600">does with</span> <span m="2132760">triangles</span>
  <span m="2133880">and</span> <span m="2134250">flipping</span> <span m="2134510">them</span>
  <span m="2134620">on</span> <span m="2134880">and</span> <span m="2135000">taking</span>
  <span m="2135210">a</span> <span m="2135250">long</span> <span m="2135390">time.</span></p><p><span
  m="2135670">This one</span> <span m="2135730">used a</span> <span m="2136150">gradient.</span>
  <span m="2137280">And</span> <span m="2137530">you</span> <span m="2137610">can</span>
  <span m="2137800">see</span> <span m="2138840">just</span> <span m="2139070">how</span>
  <span m="2139170">quickly</span> <span m="2139510">we</span> <span m="2139660">got</span>
  <span m="2140060">to</span> <span m="2140220">the</span> <span m="2140370">top of
  the</span> <span m="2140770">hill,</span> <span m="2141170">6</span> <span m="2141430">iteration,</span>
  <span m="2141960">24</span> <span m="2142540">function</span> <span m="2142790">evaluations.</span>
  <span m="2143350">And again,</span> <span m="2143470">we''ll</span> <span m="2143590">more</span>
  <span m="2143750">talk</span> <span m="2143900">about</span> <span m="2144100">the</span>
  <span m="2144160">different</span> <span m="2144540">aspects.</span></p><p><span
  m="2146030">But</span> <span m="2146170">this</span> <span m="2146290">is</span>
  <span m="2146410">definitely</span> <span m="2146920">a</span> <span m="2147020">message</span>
  <span m="2147430">that</span> <span m="2147580">if</span> <span m="2147690">you</span>
  <span m="2147770">can</span> <span m="2147950">compute</span> <span m="2148350">gradients--</span>
  <span m="2149630">which</span> <span m="2149690">we</span> <span m="2149780">can''t</span>
  <span m="2150010">always</span> <span m="2150290">do,</span> <span m="2150500">in</span>
  <span m="2150580">this</span> <span m="2150710">case</span> <span m="2150950">we</span>
  <span m="2151020">can</span> <span m="2151140">do</span> <span m="2151210">it</span>
  <span m="2151290">analytically--</span> <span m="2152420">you</span> <span m="2152530">can</span>
  <span m="2152660">get</span> <span m="2152830">really</span> <span m="2153170">quickly</span>
  <span m="2153680">to</span> <span m="2155290">an</span> <span m="2156420">optimal</span>
  <span m="2156820">solution.</span> <span m="2158540">And so</span> <span m="2158720">fminunc</span>
  <span m="2159110">and</span> <span m="2159370">fmincon</span> <span m="2160040">is</span>
  <span m="2160180">the</span> <span m="2160260">constrained</span> <span m="2161470">sort
  of</span> <span m="2161690">version</span> <span m="2162120">of</span> <span m="2162270">fminunc</span>
  <span m="2162780">can</span> <span m="2162930">be</span> <span m="2163030">really</span>
  <span m="2163220">powerful.</span></p><p><span m="2164190">So</span> <span m="2164390">let''s
  see,</span> <span m="2164660">Kevin</span> <span m="2164950">wanted</span> <span
  m="2165090">to</span> <span m="2165220">know</span> <span m="2165370">what</span>
  <span m="2165490">happened</span> <span m="2165780">if</span> <span m="2165900">we</span>
  <span m="2166000">started</span> <span m="2166240">from</span> <span m="2166380">a</span>
  <span m="2166420">different</span> <span m="2167050">solution.</span> <span m="2167824">So</span>
  <span m="2168600">what</span> <span m="2168750">would</span> <span m="2168880">you</span>
  <span m="2168980">like?</span> <span m="2178000">OK.</span> <span m="2180340">So</span>
  <span m="2180830">do you</span> <span m="2181320">want to</span> <span m="2181460">pick
  a--</span> <span m="2182250">so</span> <span m="2182390">somewhere</span> <span
  m="2182690">here?</span> <span m="2183620">So</span> <span m="2183800">like</span>
  <span m="2183980">minus</span> <span m="2184590">1,</span> <span m="2185990">minus</span>
  <span m="2186300">1?</span> <span m="2187545">Let''s</span> <span m="2187830">see.</span></p><p><span
  m="2190252">OK.</span> <span m="2191230">So</span> <span m="2191450">there''s</span>
  <span m="2191870">the</span> <span m="2191950">new</span> <span m="2192130">asterisk.</span>
  <span m="2194550">So</span> <span m="2194660">what do you</span> <span m="2194720">think''s</span>
  <span m="2194920">going</span> <span m="2195040">to</span> <span m="2195100">happen?</span>
  <span m="2200040">So it goes</span> <span m="2200440">to</span> <span m="2202230">the</span>
  <span m="2202340">local</span> <span m="2202650">peak.</span> <span m="2203460">It''s</span>
  <span m="2203730">going</span> <span m="2203850">to</span> <span m="2203940">convert</span>
  <span m="2204250">pretty</span> <span m="2204380">quickly.</span> <span m="2205350">So</span>
  <span m="2205890">while</span> <span m="2206570">an</span> <span m="2206690">advantage</span>
  <span m="2207160">of</span> <span m="2207210">gradient</span> <span m="2207650">based</span>
  <span m="2208090">optimization</span> <span m="2208660">is</span> <span m="2208770">that</span>
  <span m="2208900">it''s</span> <span m="2209090">super</span> <span m="2209160">efficient,</span>
  <span m="2209750">because</span> <span m="2210110">you use</span> <span m="2210190">the
  gradient</span> <span m="2210490">information</span> <span m="2210765">and</span>
  <span m="2211040">you</span> <span m="2211120">go</span> <span m="2211310">to the</span>
  <span m="2211860">[INAUDIBLE]</span> <span m="2218440">in the</span> <span m="2218720">design</span>
  <span m="2218970">space</span> <span m="2219990">and</span> <span m="2220670">[INAUDIBLE]</span>
  <span m="2221720">you</span> <span m="2222010">can</span> <span m="2222190">[INAUDIBLE].</span></p><p><span
  m="2222585">We''ll</span> <span m="2222980">talk about</span> <span m="2223770">[INAUDIBLE]</span>
  <span m="2223870">condition.</span> <span m="2225140">The</span> <span m="2225280">gradient</span>
  <span m="2225535">of</span> <span m="2225790">j equals</span> <span m="2226450">0</span>
  <span m="2227167">and</span> <span m="2228021">[INAUDIBLE].</span> <span m="2229285">We</span>
  <span m="2229720">can''t</span> <span m="2230155">tell the</span> <span m="2230590">difference</span>
  <span m="2231150">between</span> <span m="2231570">being</span> <span m="2231720">here,</span>
  <span m="2232340">being</span> <span m="2232560">here,</span> <span m="2232870">or</span>
  <span m="2233180">being</span> <span m="2233530">here.</span></p><p><span m="2235480">And</span>
  <span m="2235650">that''s</span> <span m="2235900">kind</span> <span m="2236040">of</span>
  <span m="2236110">a</span> <span m="2236160">drawback</span> <span m="2236570">of</span>
  <span m="2236660">a</span> <span m="2236720">local</span> <span m="2237960">method.</span>
  <span m="2238215">At best,</span> <span m="2238730">we</span> <span m="2239620">can</span>
  <span m="2239970">say</span> <span m="2240240">that</span> <span m="2240390">we</span>
  <span m="2240510">are</span> <span m="2240600">in</span> <span m="2240700">a</span>
  <span m="2240800">local</span> <span m="2241690">maximum</span> <span m="2242220">in</span>
  <span m="2242340">this</span> <span m="2242480">case.</span> <span m="2244010">So</span>
  <span m="2244270">we</span> <span m="2244370">have</span> <span m="2244500">to</span>
  <span m="2244560">be</span> <span m="2244620">careful</span> <span m="2244870">about
  where we</span> <span m="2245030">initialize.</span> <span m="2245960">And</span>
  <span m="2245990">you</span> <span m="2246250">probably</span> <span m="2246695">guess</span>
  <span m="2247140">if</span> <span m="2248150">we</span> <span m="2248240">start</span>
  <span m="2248460">close</span> <span m="2248680">to</span> <span m="2248780">this
  one,</span> <span m="2249150">we''re</span> <span m="2249250">going</span> <span
  m="2249560">end</span> <span m="2249870">up  up</span> <span m="2250070">there.</span>
  <span m="2250400">If</span> <span m="2250530">we</span> <span m="2250750">can</span>
  <span m="2250930">start</span> <span m="2251200">somewhere</span> <span m="2251410">over</span>
  <span m="2251560">here,</span> <span m="2251850">we</span> <span m="2251930">have</span>
  <span m="2252080">a good</span> <span m="2252130">chance</span> <span m="2252470">of</span>
  <span m="2252540">getting</span> <span m="2252750">up</span> <span m="2252880">here.</span>
  <span m="2253110">And</span> <span m="2253210">if</span> <span m="2253310">we</span>
  <span m="2253420">start</span> <span m="2253750">where</span> <span m="2253890">we</span>
  <span m="2254000">started,</span> <span m="2254860">we''re</span> <span m="2254950">going</span>
  <span m="2255070">to</span> <span m="2255130">go</span> <span m="2255240">here.</span>
  <span m="2256230">It''s one</span> <span m="2256360">of</span> <span m="2256420">the</span>
  <span m="2256480">drawbacks.</span> <span m="2256810">[INAUDIBLE],</span> <span
  m="2257090">do you have a question?</span></p><p><span m="2257750">AUDIENCE: Yeah.</span>
  <span m="2258230">I was going to ask</span> <span m="2258710">how</span> <span m="2259190">could
  you</span> <span m="2259670">know</span> <span m="2260150">how</span> <span m="2260630">far
  to go</span> <span m="2261110">[INAUDIBLE]?</span></p><p><span m="2263990">PROFESSOR:
  Yeah.</span> <span m="2264480">We''re</span> <span m="2264580">going</span> <span
  m="2264700">to</span> <span m="2264790">talk</span> <span m="2265020">about</span>
  <span m="2265280">that, yeah.</span> <span m="2265470">So</span> <span m="2265810">we''re</span>
  <span m="2265920">going</span> <span m="2266040">to</span> <span m="2266110">talk</span>
  <span m="2266270">about</span> <span m="2266600">how</span> <span m="2268110">it</span>
  <span m="2268250">chooses</span> <span m="2270160">x,</span> <span m="2270540">which</span>
  <span m="2270680">is</span> <span m="2270770">going</span> <span m="2270920">to</span>
  <span m="2271000">use</span> <span m="2271140">gradient</span> <span m="2271340">information.</span>
  <span m="2271890">But it''s</span> <span m="2272110">not</span> <span m="2272330">just</span>
  <span m="2272580">the</span> <span m="2272660">gradient</span> <span m="2272850">you''ll</span>
  <span m="2273300">see.</span> <span m="2274070">And</span> <span m="2274230">then</span>
  <span m="2274350">how</span> <span m="2274530">it</span> <span m="2274620">knows</span>
  <span m="2274920">how</span> <span m="2275090">far</span> <span m="2275370">to</span>
  <span m="2275440">go</span> <span m="2275650">is</span> <span m="2275820">that</span>
  <span m="2275970">once</span> <span m="2276270">it''s</span> <span m="2276480">picked</span>
  <span m="2277240">the</span> <span m="2277350">gradient</span> <span m="2277710">direction,</span>
  <span m="2278090">it</span> <span m="2278210">looks</span> <span m="2278600">to</span>
  <span m="2278700">see</span> <span m="2279030">the</span> <span m="2279110">shape</span>
  <span m="2279400">of</span> <span m="2279460">the</span> <span m="2279520">function</span>
  <span m="2279970">in</span> <span m="2280050">that</span> <span m="2280200">direction.</span>
  <span m="2280590">And we''ll</span> <span m="2280690">talk</span> <span m="2281050">about</span>
  <span m="2281250">how</span> <span m="2281390">it</span> <span m="2281470">actually</span>
  <span m="2281760">knows how far</span> <span m="2282206">to go.</span> <span m="2283098">Yeah.</span>
  <span m="2283544">Is</span> <span m="2283990">there</span> <span m="2284436">another</span>
  <span m="2284882">question?</span></p><p><span m="2287138">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="2289850">PROFESSOR: Yeah.</span> <span m="2291830">This</span> <span m="2292050">one</span>
  <span m="2292310">here?</span> <span m="2295750">Yeah.</span> <span m="2296230">It''s</span>
  <span m="2296450">not</span> <span m="2297160">quite</span> <span m="2297370">clear.</span>
  <span m="2297770">If</span> <span m="2297880">it</span> <span m="2297980">were</span>
  <span m="2298150">right</span> <span m="2298630">on</span> <span m="2299320">the</span>
  <span m="2299730">settle</span> <span m="2300140">point--</span> <span m="2304180">it''s</span>
  <span m="2304940">not</span> <span m="2305130">quite</span> <span m="2305320">clear.</span>
  <span m="2305810">And I''ll</span> <span m="2306050">see</span> <span m="2306200">if</span>
  <span m="2306310">I</span> <span m="2306420">can--</span> <span m="2308190">I</span>
  <span m="2308290">think</span> <span m="2308540">it''s</span> <span m="2309060">a</span>
  <span m="2309140">similar</span> <span m="2310560">question.</span></p><p><span
  m="2310900">If</span> <span m="2311010">I</span> <span m="2311090">started</span>
  <span m="2311450">over</span> <span m="2311630">here,</span> <span m="2312550">so</span>
  <span m="2312950">let''s</span> <span m="2313170">see,</span> <span m="2313360">x</span>
  <span m="2313730">will</span> <span m="2313890">be</span> <span m="2314130">close</span>
  <span m="2314450">to</span> <span m="2314540">minus</span> <span m="2314850">3.</span>
  <span m="2315140">And y</span> <span m="2315490">will be</span> <span m="2315840">close</span>
  <span m="2316360">to</span> <span m="2316620">3.</span> <span m="2316990">So</span>
  <span m="2317180">let''s</span> <span m="2317450">start it</span> <span m="2317610">at,</span>
  <span m="2322640">like,</span> <span m="2322840">minus</span> <span m="2323290">2.5</span>
  <span m="2324630">and</span> <span m="2329960">plus</span> <span m="2330050">2.5.</span>
  <span m="2330730">So I think that''s</span> <span m="2331080">over</span> <span
  m="2331260">in</span> <span m="2331360">a</span> <span m="2331420">corner</span>
  <span m="2331710">of</span> <span m="2331810">the</span> <span m="2331880">design
  space.</span> <span m="2333152">Do</span> <span m="2333610">you</span> <span m="2333780">see</span>
  <span m="2333990">any</span> <span m="2334820">potential</span> <span m="2335190">problems</span>
  <span m="2335610">here?</span></p><p><span m="2336720">It''s</span> <span m="2336900">really</span>
  <span m="2337110">flat,</span> <span m="2337570">right?</span> <span m="2337910">So</span>
  <span m="2338100">when</span> <span m="2338240">we</span> <span m="2338340">compute</span>
  <span m="2338640">the</span> <span m="2338710">gradient,</span> <span m="2339430">it''s</span>
  <span m="2339800">going</span> <span m="2339920">to</span> <span m="2339980">be</span>
  <span m="2340060">really</span> <span m="2340230">flat.</span> <span m="2340440">It''s</span>
  <span m="2340630">going</span> <span m="2340750">to</span> <span m="2340810">know</span>
  <span m="2341030">that</span> <span m="2341160">it''s</span> <span m="2341320">not</span>
  <span m="2341720">at</span> <span m="2341830">a</span> <span m="2342050">local</span>
  <span m="2342330">minimum,</span> <span m="2342750">because</span> <span m="2343180">the</span>
  <span m="2343400">second</span> <span m="2343810">road</span> <span m="2343900">is
  not</span> <span m="2344680">going</span> <span m="2344800">to</span> <span m="2344860">be</span>
  <span m="2345300">positive.</span> <span m="2346560">But</span> <span m="2346720">it</span>
  <span m="2346830">can</span> <span m="2347010">be</span> <span m="2347120">that</span>
  <span m="2347280">the</span> <span m="2347390">algorithm</span> <span m="2347920">has</span>
  <span m="2348290">difficulty</span> <span m="2348890">figuring</span> <span m="2349260">out</span>
  <span m="2349350">which</span> <span m="2349500">way</span> <span m="2349600">to</span>
  <span m="2349670">go,</span> <span m="2349880">which</span> <span m="2350230">might</span>
  <span m="2350460">also</span> <span m="2350670">be</span> <span m="2350780">the</span>
  <span m="2350850">same</span> <span m="2351050">thing</span> <span m="2351190">if</span>
  <span m="2351310">you</span> <span m="2351380">started</span> <span m="2351720">in</span>
  <span m="2351860">that</span> <span m="2352830">shoulder</span> <span m="2353270">between</span>
  <span m="2353660">the</span> <span m="2353750">two.</span></p><p><span m="2354970">But</span>
  <span m="2356032">so</span> <span m="2356380">it</span> <span m="2356520">turns</span>
  <span m="2356790">out,</span> <span m="2357130">I mean,</span> <span m="2357490">it''s</span>
  <span m="2357740">going</span> <span m="2357870">to</span> <span m="2357940">have</span>
  <span m="2358120">difficulty.</span> <span m="2358550">And</span> <span m="2358980">you
  can</span> <span m="2359270">see</span> <span m="2360750">it''s</span> <span m="2364120">probably</span>
  <span m="2364220">having</span> <span m="2364540">a few</span> <span m="2364810">issues.</span>
  <span m="2365140">It''s running</span> <span m="2365370">pretty</span> <span m="2365550">slowly,</span>
  <span m="2365990">which</span> <span m="2366220">means</span> <span m="2366470">it''s</span>
  <span m="2366600">probably</span> <span m="2366880">doing</span> <span m="2367170">a</span>
  <span m="2367240">lot</span> <span m="2367530">more</span> <span m="2368730">function</span>
  <span m="2369290">calls.</span></p><p><span m="2370970">But</span> <span m="2371430">these</span>
  <span m="2371700">algorithms</span> <span m="2372280">and</span> <span m="2372540">especially</span>
  <span m="2372880">MATLAB''s</span> <span m="2373640">optimization</span> <span m="2374290">toolbox</span>
  <span m="2374540">is</span> <span m="2374670">really</span> <span m="2375060">good.</span>
  <span m="2376110">So</span> <span m="2376260">they</span> <span m="2376410">have</span>
  <span m="2376630">ways</span> <span m="2377030">of</span> <span m="2377160">recovering.</span>
  <span m="2378050">So</span> <span m="2378520">that</span> <span m="2378710">when</span>
  <span m="2378820">things</span> <span m="2379110">go</span> <span m="2379280">wrong,</span>
  <span m="2379850">if</span> <span m="2379950">you</span> <span m="2380020">can''t</span>
  <span m="2380190">figure</span> <span m="2380380">out</span> <span m="2380480">where</span>
  <span m="2380590">to</span> <span m="2380660">go,</span> <span m="2381040">you</span>
  <span m="2381190">do</span> <span m="2381300">a</span> <span m="2381350">little</span>
  <span m="2381540">bit</span> <span m="2381720">of</span> <span m="2382000">sampling</span>
  <span m="2382880">and</span> <span m="2383180">there</span> <span m="2383370">are</span>
  <span m="2384050">many</span> <span m="2384350">ways</span> <span m="2384600">that</span>
  <span m="2384720">you</span> <span m="2384820">can</span> <span m="2384980">recover.</span>
  <span m="2385400">And</span> <span m="2385510">in</span> <span m="2385580">this</span>
  <span m="2385760">case,</span> <span m="2385970">we</span> <span m="2386030">managed</span>
  <span m="2386350">to</span> <span m="2386430">recover</span> <span m="2386750">and</span>
  <span m="2386840">actually</span> <span m="2387100">get</span> <span m="2387660">up</span>
  <span m="2387810">to</span> <span m="2387910">the</span> <span m="2387990">top.</span></p><p><span
  m="2390230">We''re</span> <span m="2390330">not</span> <span m="2390460">there</span>
  <span m="2390600">yet.</span> <span m="2392080">It''ll</span> <span m="2392260">get</span>
  <span m="2392460">there, though.</span> <span m="2392960">It</span> <span m="2393060">should</span>
  <span m="2393450">get</span> <span m="2393901">there.</span> <span m="2397960">It</span>
  <span m="2398270">is--</span> <span m="2398880">yeah,</span> <span m="2399230">you</span>
  <span m="2399390">can</span> <span m="2399570">see.</span> <span m="2400040">Even</span>
  <span m="2400170">though</span> <span m="2400350">it</span> <span m="2400490">managed</span>
  <span m="2400800">to</span> <span m="2400860">get</span> <span m="2400980">there,</span>
  <span m="2401140">I</span> <span m="2401170">mean,</span> <span m="2401580">I</span>
  <span m="2401620">don''t</span> <span m="2401720">know</span> <span m="2401780">if</span>
  <span m="2401860">you</span> <span m="2401940">looked</span> <span m="2402030">at</span>
  <span m="2402090">the</span> <span m="2402150">numbers</span> <span m="2402460">before.</span></p><p><span
  m="2404300">This</span> <span m="2404430">is</span> <span m="2404520">the</span>
  <span m="2404590">number</span> <span m="2405040">of</span> <span m="2405130">times</span>
  <span m="2405570">that</span> <span m="2405810">it calls</span> <span m="2406885">the</span>
  <span m="2407380">evaluation</span> <span m="2408120">of</span> <span m="2408220">the</span>
  <span m="2408330">surface.</span> <span m="2409480">And</span> <span m="2409670">usually,</span>
  <span m="2409890">it''s</span> <span m="2410040">on</span> <span m="2410160">the</span>
  <span m="2410250">order</span> <span m="2410600">of</span> <span m="2411110">3,</span>
  <span m="2412020">6,</span> <span m="2412670">but</span> <span m="2412820">you</span>
  <span m="2412880">can</span> <span m="2412970">see</span> <span m="2413120">it</span>
  <span m="2413250">took</span> <span m="2413670">27.</span> <span m="2414380">And</span>
  <span m="2414490">that second</span> <span m="2414630">iteration,</span> <span m="2415260">that''s</span>
  <span m="2415450">because</span> <span m="2415680">it</span> <span m="2415750">was</span>
  <span m="2415880">in</span> <span m="2415990">this</span> <span m="2416070">flat</span>
  <span m="2416420">region.</span></p><p><span m="2417660">But</span> <span m="2419030">you</span>
  <span m="2419170">can</span> <span m="2419300">see</span> <span m="2419400">that</span>
  <span m="2419510">whatever</span> <span m="2419770">MATLAB,</span> <span m="2420280">whatever</span>
  <span m="2420590">[INAUDIBLE]</span> <span m="2421080">built</span> <span m="2421400">in</span>
  <span m="2422980">to</span> <span m="2423130">try</span> <span m="2423490">and</span>
  <span m="2423830">sort</span> <span m="2423980">of</span> <span m="2424050">make</span>
  <span m="2424240">the</span> <span m="2424300">algorithm</span> <span m="2424700">robust,</span>
  <span m="2425080">actually</span> <span m="2425320">did manage to</span> <span m="2425750">recover</span>
  <span m="2426080">in that</span> <span m="2426230">[INAUDIBLE].</span> <span m="2427350">These</span>
  <span m="2427580">things</span> <span m="2427790">can</span> <span m="2427940">definitely</span>
  <span m="2428810">fail</span> <span m="2429180">to</span> <span m="2429240">converge.</span>
  <span m="2429830">They</span> <span m="2429910">can</span> <span m="2430030">come</span>
  <span m="2430170">back</span> <span m="2430330">without</span> <span m="2430580">finding</span>
  <span m="2430880">a</span> <span m="2430990">solution.</span></p><p><span m="2432430">So</span>
  <span m="2432520">there''s</span> <span m="2432910">all</span> <span m="2433070">kinds</span>
  <span m="2433390">of</span> <span m="2434160">problems</span> <span m="2434490">you</span>
  <span m="2434560">can</span> <span m="2434700">run</span> <span m="2434840">into.</span>
  <span m="2435260">But</span> <span m="2435320">conceptually,</span> <span m="2435810">this</span>
  <span m="2436370">is</span> <span m="2436580">what''s</span> <span m="2437110">going</span>
  <span m="2437390">on.</span> <span m="2437550">I</span> <span m="2437630">think</span>
  <span m="2437820">that</span> <span m="2438560">a</span> <span m="2438590">picture</span>
  <span m="2438910">of</span> <span m="2438990">a</span> <span m="2439050">landscape</span>
  <span m="2439580">is</span> <span m="2439710">a</span> <span m="2439770">really</span>
  <span m="2439990">good</span> <span m="2440190">one</span> <span m="2440400">to</span>
  <span m="2440510">have</span> <span m="2440690">in</span> <span m="2440770">your</span>
  <span m="2440860">mind</span> <span m="2441860">as</span> <span m="2442020">we</span>
  <span m="2442120">talk</span> <span m="2442310">about</span> <span m="2442540">the</span>
  <span m="2442620">math</span> <span m="2442990">of</span> <span m="2444230">the</span>
  <span m="2444340">algorithms</span> <span m="2445090">and</span> <span m="2445250">the</span>
  <span m="2445310">computing</span> <span m="2445690">of</span> <span m="2445790">the</span>
  <span m="2445890">alpha</span> <span m="2446420">and</span> <span m="2446560">the</span>
  <span m="2446700">x.</span> <span m="2448910">OK?</span> <span m="2455240">Is</span>
  <span m="2455390">there</span> <span m="2455500">any</span> <span m="2455640">good</span>
  <span m="2455800">way</span> <span m="2455940">to</span> <span m="2456040">approximate</span>
  <span m="2456630">the</span> <span m="2456700">landscape</span> <span m="2457140">if</span>
  <span m="2457300">the</span> <span m="2457400">function</span> <span m="2457770">is</span>
  <span m="2457870">too</span> <span m="2457990">expensive</span> <span m="2458440">to</span>
  <span m="2458510">call?</span></p><p><span m="2460010">AUDIENCE: [INAUDIBLE].</span>
  <span m="2461510">We''re</span> <span m="2462010">lucky</span> <span m="2462510">that
  we know</span> <span m="2463010">what it</span> <span m="2463510">looks like.</span>
  <span m="2464492">[INAUDIBLE]</span></p><p><span m="2471860">PROFESSOR: Yeah.</span>
  <span m="2472450">So</span> <span m="2472630">we</span> <span m="2472790">know</span>
  <span m="2472970">where</span> <span m="2473140">it</span> <span m="2473210">is.</span>
  <span m="2473420">And</span> <span m="2473520">we''re</span> <span m="2473630">visualizing</span>
  <span m="2474080">it.</span> <span m="2474400">But the</span> <span m="2474500">optimizer</span>
  <span m="2475070">didn''t</span> <span m="2475330">know</span> <span m="2475590">that.</span></p><p><span
  m="2476090">AUDIENCE: Right.</span></p><p><span m="2477090">PROFESSOR: So--</span></p><p><span
  m="2478090">AUDIENCE: [INAUDIBLE]</span> <span m="2479590">are</span> <span m="2480090">there</span>
  <span m="2480590">[INAUDIBLE].</span></p><p><span m="2488953">PROFESSOR: So</span>
  <span m="2490790">it</span> <span m="2491030">depends</span> <span m="2491470">on</span>
  <span m="2491590">your</span> <span m="2491710">problem.</span> <span m="2492690">If</span>
  <span m="2492830">your</span> <span m="2492950">problem</span> <span m="2493240">has</span>
  <span m="2493420">got</span> <span m="2493650">particular</span> <span m="2494070">structure,</span>
  <span m="2494680">it</span> <span m="2494850">may</span> <span m="2495050">be</span>
  <span m="2495170">that</span> <span m="2495340">you</span> <span m="2495420">can</span>
  <span m="2495530">come</span> <span m="2495720">up</span> <span m="2495890">with</span>
  <span m="2496080">an</span> <span m="2496120">approximations,</span> <span m="2498650">and</span>
  <span m="2498790">in</span> <span m="2498850">particular</span> <span m="2499280">what''s</span>
  <span m="2499450">called</span> <span m="2499660">complex</span> <span m="2500080">approximations</span>
  <span m="2500425">where</span> <span m="2500770">you</span> <span m="2500990">can</span>
  <span m="2501130">guarantee</span> <span m="2501700">something</span> <span m="2501960">about</span>
  <span m="2502160">the</span> <span m="2502270">solution.</span> <span m="2503060">So</span>
  <span m="2503170">that''s</span> <span m="2503300">going</span> <span m="2503420">to</span>
  <span m="2503510">depend</span> <span m="2503890">very</span> <span m="2504070">much</span>
  <span m="2504380">on</span> <span m="2504710">the</span> <span m="2504780">structure</span>
  <span m="2505060">of</span> <span m="2505120">your</span> <span m="2505230">problem.</span></p><p><span
  m="2505680">That''s what a</span> <span m="2505750">lot</span> <span m="2505900">of</span>
  <span m="2505960">people</span> <span m="2506150">in</span> <span m="2506230">operations</span>
  <span m="2506710">research</span> <span m="2507150">spend</span> <span m="2507240">a</span>
  <span m="2507300">lot</span> <span m="2507420">of</span> <span m="2507490">time</span>
  <span m="2507660">doing</span> <span m="2507890">is</span> <span m="2507970">taking</span>
  <span m="2508250">difficult</span> <span m="2508630">problems</span> <span m="2509480">and
  then</span> <span m="2509680">coming</span> <span m="2509960">up</span> <span m="2510110">with</span>
  <span m="2510380">approximations</span> <span m="2510670">or</span> <span m="2511060">relaxations</span>
  <span m="2511720">of</span> <span m="2511810">the</span> <span m="2511890">problem</span>
  <span m="2512280">that</span> <span m="2512390">they</span> <span m="2512520">can</span>
  <span m="2512730">then</span> <span m="2513420">say</span> <span m="2513750">something</span>
  <span m="2514320">rigorous</span> <span m="2514800">about</span> <span m="2515065">the</span>
  <span m="2515330">solution</span> <span m="2515720">and</span> <span m="2515870">how
  it</span> <span m="2516160">relates to</span> <span m="2516450">solution</span>
  <span m="2516890">[INAUDIBLE].</span> <span m="2517672">But</span> <span m="2518010">I</span>
  <span m="2518150">think</span> <span m="2518380">the</span> <span m="2518460">reality</span>
  <span m="2518840">is that</span> <span m="2518980">in</span> <span m="2519230">engineering</span>
  <span m="2519760">design</span> <span m="2520290">the</span> <span m="2520360">landscape</span>
  <span m="2520880">usually</span> <span m="2521260">looks</span> <span m="2521670">a</span>
  <span m="2521760">real</span> <span m="2521970">mess.</span> <span m="2522590">And</span>
  <span m="2522970">not</span> <span m="2523160">only</span> <span m="2523390">does</span>
  <span m="2523530">it</span> <span m="2523630">have</span> <span m="2523960">multiple</span>
  <span m="2524970">hills</span> <span m="2525240">and</span> <span m="2525330">mountains,</span>
  <span m="2525690">but</span> <span m="2525840">often</span> <span m="2526060">there''s</span>
  <span m="2526230">cliffs</span> <span m="2527230">or</span> <span m="2527430">part
  of a--</span> <span m="2528110">because</span> <span m="2528460">we''re</span> <span
  m="2528570">not</span> <span m="2528700">even</span> <span m="2528860">looking</span>
  <span m="2529060">constraints</span> <span m="2529525">here.</span></p><p><span
  m="2529990">Part of</span> <span m="2530060">the</span> <span m="2530140">design</span>
  <span m="2530490">space</span> <span m="2530880">where</span> <span m="2531600">there''s</span>
  <span m="2531770">like</span> <span m="2531950">a</span> <span m="2532040">region</span>
  <span m="2532490">where</span> <span m="2532640">there''s just</span> <span m="2532820">no</span>
  <span m="2533200">feasible</span> <span m="2533640">design.</span> <span m="2535790">And</span>
  <span m="2536540">basically,</span> <span m="2536980">people</span> <span m="2537360">apply</span>
  <span m="2537820">optimization</span> <span m="2538390">methods</span> <span m="2538740">to</span>
  <span m="2538820">try</span> <span m="2538970">to</span> <span m="2539050">improve</span>
  <span m="2539500">designs,</span> <span m="2540020">but</span> <span m="2540370">don''t</span>
  <span m="2540550">necessarily</span> <span m="2541120">worry</span> <span m="2541710">as</span>
  <span m="2541950">much</span> <span m="2542200">about</span> <span m="2542470">mathematical</span>
  <span m="2542620">optimality.</span> <span m="2543426">It''s</span> <span m="2543830">more</span>
  <span m="2544020">of</span> <span m="2544080">a</span> <span m="2544150">tool to</span>
  <span m="2544510">help</span> <span m="2545480">improve</span> <span m="2546370">design.</span>
  <span m="2546750">So</span> <span m="2547143">think</span> <span m="2547536">a little
  bit on</span> <span m="2547930">what you''re trying</span> <span m="2548110">to</span>
  <span m="2548200">do</span> <span m="2548300">as well.</span> <span m="2550050">Do
  you have</span> <span m="2550530">a question?</span></p><p><span m="2551490">AUDIENCE:
  [INAUDIBLE]</span> <span m="2552930">what happens</span> <span m="2553410">like</span>
  <span m="2553890">[INAUDIBLE]</span></p><p><span m="2561570">PROFESSOR: Yeah.</span></p><p><span
  m="2562435">AUDIENCE: [INAUDIBLE]</span> <span m="2563860">still</span> <span m="2564335">[INAUDIBLE].</span></p><p><span
  m="2566240">PROFESSOR: Yeah.</span> <span m="2567330">So</span> <span m="2568140">that</span>
  <span m="2568390">crinkled</span> <span m="2568740">up</span> <span m="2568880">wing</span>
  <span m="2569210">was</span> <span m="2569440">probably</span> <span m="2569880">like
  a</span> <span m="2570140">solution</span> <span m="2570720">wing.</span> <span
  m="2571420">It</span> <span m="2571540">was</span> <span m="2571650">horrible.</span>
  <span m="2572980">I</span> <span m="2573050">mean,</span> <span m="2573160">this</span>
  <span m="2573290">is</span> <span m="2573470">now--</span> <span m="2574270">that</span>
  <span m="2574430">was</span> <span m="2574560">a</span> <span m="2574610">design</span>
  <span m="2574990">problem</span> <span m="2575240">with</span> <span m="2575390">many</span>
  <span m="2575550">more</span> <span m="2576010">designs,</span> <span m="2576950">so</span>
  <span m="2577080">we</span> <span m="2577140">can''t</span> <span m="2577310">visualize</span>
  <span m="2577730">it.</span> <span m="2577810">But</span> <span m="2577940">even</span>
  <span m="2578150">just</span> <span m="2578280">thinking</span> <span m="2578450">about
  it</span> <span m="2578600">here, it</span> <span m="2578720">was</span> <span m="2578850">probably
  a</span> <span m="2579050">design</span> <span m="2579450">that</span> <span m="2579540">was</span>
  <span m="2579660">somewhere</span> <span m="2579920">down</span> <span m="2580120">here</span>
  <span m="2580290">because</span> <span m="2580380">it</span> <span m="2580540">was</span>
  <span m="2580660">so</span> <span m="2580840">awful.</span></p><p><span m="2582630">But</span>
  <span m="2583395">you know,</span> <span m="2583780">as</span> <span m="2584130">long</span>
  <span m="2584330">as</span> <span m="2584400">you</span> <span m="2584490">can</span>
  <span m="2584620">get</span> <span m="2584810">reliable</span> <span m="2585480">[INAUDIBLE]</span>
  <span m="2585890">gradients</span> <span m="2586350">using</span> <span m="2586560">[INAUDIBLE]</span>
  <span m="2587060">methods,</span> <span m="2587400">you</span> <span m="2587470">get</span>
  <span m="2587640">yourself</span> <span m="2588240">out</span> <span m="2588430">of</span>
  <span m="2588510">that</span> <span m="2588730">awful</span> <span m="2588880">place,</span>
  <span m="2589220">and</span> <span m="2589560">you</span> <span m="2589900">get</span>
  <span m="2590110">to a</span> <span m="2590240">good</span> <span m="2590700">one.</span>
  <span m="2591160">So</span> <span m="2591620">it</span> <span m="2592080">might</span>
  <span m="2592310">take</span> <span m="2592540">longer.</span> <span m="2595540">Yup.</span>
  <span m="2599020">OK.</span> <span m="2599380">So</span> <span m="2602120">Let''s</span>
  <span m="2602460">see</span> <span m="2603070">where</span> <span m="2603260">we</span>
  <span m="2603460">are.</span> <span m="2606148">So</span> <span m="2606596">I''ll</span>
  <span m="2607044">turn this off.</span></p><p><span m="2607990">OK.</span> <span
  m="2608380">So</span> <span m="2608850">[INAUDIBLE]</span> <span m="2609320">a couple</span>
  <span m="2609790">of</span> <span m="2610040">mathematical</span> <span m="2611903">things</span>
  <span m="2612384">that we</span> <span m="2612865">may</span> <span m="2613346">need</span>
  <span m="2614308">to</span> <span m="2615270">[INAUDIBLE]</span> <span m="2619190">concepts</span>
  <span m="2619500">that</span> <span m="2619610">we</span> <span m="2619700">need</span>
  <span m="2619880">before</span> <span m="2620110">we</span> <span m="2620210">actually</span>
  <span m="2620450">talk</span> <span m="2620570">about</span> <span m="2621290">what''s</span>
  <span m="2621550">going</span> <span m="2621750">on</span> <span m="2622020">in
  those</span> <span m="2622220">optimization</span> <span m="2622830">algorithms.</span>
  <span m="2624300">So we''re</span> <span m="2624755">going to</span> <span m="2625210">need</span>
  <span m="2625800">to think</span> <span m="2626281">about gradients.</span> <span
  m="2632534">So</span> <span m="2633015">let''s</span> <span m="2633496">just</span>
  <span m="2634100">think</span> <span m="2634370">about</span> <span m="2634630">what</span>
  <span m="2634780">the</span> <span m="2634850">gradient</span> <span m="2635480">is</span>
  <span m="2635730">in</span> <span m="2635850">this</span> <span m="2635960">case.</span></p><p><span
  m="2639500">And</span> <span m="2639840">so</span> <span m="2639920">what</span>
  <span m="2640060">we''re</span> <span m="2640170">talking</span> <span m="2640510">about</span>
  <span m="2641100">for</span> <span m="2642530">j</span> <span m="2643693">of x--</span>
  <span m="2645910">and</span> <span m="2646050">remember,</span> <span m="2646490">this</span>
  <span m="2646560">is a</span> <span m="2646660">scalar</span> <span m="2647960">objective,</span>
  <span m="2651900">but</span> <span m="2652100">this</span> <span m="2652280">is</span>
  <span m="2653866">n</span> <span m="2654328">dimensional</span> <span m="2655090">design</span>
  <span m="2655480">[INAUDIBLE].</span> <span m="2661830">So</span> <span m="2661950">we''re</span>
  <span m="2662070">talking</span> <span m="2662380">about</span> <span m="2662620">the</span>
  <span m="2662740">objective</span> <span m="2663170">function</span> <span m="2664470">j
  of x,</span> <span m="2665410">a</span> <span m="2665530">scalar</span> <span m="2666000">function</span>
  <span m="2666540">of n</span> <span m="2666820">design</span> <span m="2668270">variables.</span>
  <span m="2669840">Then</span> <span m="2670370">the</span> <span m="2670450">gradient</span>
  <span m="2676410">is</span> <span m="2676620">what?</span></p><p><span m="2677494">First</span>
  <span m="2677931">of all,</span> <span m="2678370">what dimension</span> <span m="2678740">does</span>
  <span m="2678910">the</span> <span m="2678970">gradient</span> <span m="2679360">have?</span>
  <span m="2684210">n</span> <span m="2684400">by</span> <span m="2684852">n?</span>
  <span m="2688020">What</span> <span m="2688150">do you</span> <span m="2688200">think</span>
  <span m="2688370">it is?</span> <span m="2688803">[INAUDIBLE]?</span> <span m="2689670">N?</span>
  <span m="2690622">n by--</span> <span m="2691574">n by</span> <span m="2692050">1.</span>
  <span m="2692970">It''s</span> <span m="2693140">a</span> <span m="2693200">vector
  of</span> <span m="2693620">link</span> <span m="2693870">n,</span> <span m="2694310">n
  by</span> <span m="2694450">1.</span> <span m="2695500">So</span> <span m="2695600">the</span>
  <span m="2695680">gradient--</span> <span m="2696055">but with the</span> <span
  m="2696430">gradients,</span> <span m="2696895">I''m</span> <span m="2697360">talking</span>
  <span m="2697600">about</span> <span m="2698070">the</span> <span m="2698160">gradient</span>
  <span m="2698620">of</span> <span m="2698880">j</span> <span m="2699370">with</span>
  <span m="2699570">respect</span> <span m="2699950">to</span> <span m="2700040">x.</span></p><p><span
  m="2701760">So you</span> <span m="2702010">should</span> <span m="2702486">write
  that</span> <span m="2702962">as</span> <span m="2703438">gradj.</span> <span m="2707246">You
  must</span> <span m="2707722">have seen</span> <span m="2708200">this</span> <span
  m="2708490">in</span> <span m="2708590">1802,</span> <span m="2709502">no?</span>
  <span m="2709930">Gradient?</span> <span m="2711738">Yeah.</span> <span m="2712642">You''re</span>
  <span m="2713100">frowning,</span> <span m="2713556">Jacobi.</span></p><p><span
  m="2714468">AUDIENCE: No,</span> <span m="2714924">I was</span> <span m="2715380">nodding.</span></p><p><span
  m="2715836">PROFESSOR: Oh, you were</span> <span m="2716292">nodding?</span> <span
  m="2716750">You</span> <span m="2716830">looked</span> <span m="2716980">like</span>
  <span m="2717120">you</span> <span m="2717200">frown</span> <span m="2717580">when
  I</span> <span m="2717962">[INAUDIBLE].</span> <span m="2719110">So</span> <span
  m="2719370">gradient</span> <span m="2720460">of</span> <span m="2721150">j,</span>
  <span m="2722330">which</span> <span m="2722610">is</span> <span m="2723120">the</span>
  <span m="2723210">vector</span> <span m="2723780">of</span> <span m="2724300">partial</span>
  <span m="2724700">derivatives,</span> <span m="2725100">right?</span> <span m="2725500">bj,</span>
  <span m="2726475">bx1,</span> <span m="2727960">bj</span> <span m="2728270">dx2</span>
  <span m="2730970">down</span> <span m="2731280">to</span> <span m="2732910">bj</span>
  <span m="2733170">dxn.</span> <span m="2737630">So</span> <span m="2738130">the</span>
  <span m="2738280">gradient</span> <span m="2739080">is--</span> <span m="2740450">it''s
  an</span> <span m="2740590">n</span> <span m="2740860">by</span> <span m="2740990">1</span>
  <span m="2741220">vector</span> <span m="2742596">[INAUDIBLE]</span> <span m="2743020">grad
  j,</span> <span m="2743750">which</span> <span m="2743930">is</span> <span m="2744140">just
  a</span> <span m="2744220">vector</span> <span m="2744690">of</span> <span m="2745340">partial</span>
  <span m="2745700">derivative.</span></p><p><span m="2747250">And</span> <span m="2747740">normally,</span>
  <span m="2748330">we''ll</span> <span m="2748550">be</span> <span m="2748720">interested</span>
  <span m="2749340">in</span> <span m="2749640">the</span> <span m="2749720">gradient</span>
  <span m="2750250">evaluated</span> <span m="2751260">at</span> <span m="2751400">a</span>
  <span m="2751440">particular</span> <span m="2751900">point,</span> <span m="2752380">because</span>
  <span m="2754500">you know,</span> <span m="2755000">again,</span> <span m="2755370">we''re</span>
  <span m="2755430">going</span> <span m="2755550">to</span> <span m="2755620">be</span>
  <span m="2755880">evaluating</span> <span m="2756400">the</span> <span m="2756520">gradient</span>
  <span m="2756980">at</span> <span m="2757110">the</span> <span m="2757180">point</span>
  <span m="2757390">we''re</span> <span m="2757510">standing</span> <span m="2757890">in</span>
  <span m="2757990">the</span> <span m="2758060">landscape.</span> <span m="2758800">And</span>
  <span m="2759170">so</span> <span m="2759370">we</span> <span m="2759490">would</span>
  <span m="2759620">write</span> <span m="2759880">that</span> <span m="2760100">maybe</span>
  <span m="2760720">as</span> <span m="2761616">gradj</span> <span m="2763410">evaluated</span>
  <span m="2764230">at</span> <span m="2764350">the</span> <span m="2764420">point</span>
  <span m="2764870">xk.</span> <span m="2767340">So</span> <span m="2767834">[INAUDIBLE]</span>
  <span m="2768328">going to use</span> <span m="2768822">q.</span> <span m="2769316">You
  can leave q</span> <span m="2769810">over</span> <span m="2769950">there,</span>
  <span m="2771330">which</span> <span m="2771640">would</span> <span m="2771810">mean</span>
  <span m="2772150">taking</span> <span m="2772600">these</span> <span m="2772800">partial</span>
  <span m="2773290">derivatives</span> <span m="2775230">and</span> <span m="2775390">evaluating</span>
  <span m="2776160">them</span> <span m="2776320">at</span> <span m="2776470">the</span>
  <span m="2776540">point</span> <span m="2777000">x</span> <span m="2778340">equal</span>
  <span m="2778650">to</span> <span m="2778860">xq.</span></p><p><span m="2784916">So
  you</span> <span m="2785412">guys</span> <span m="2785920">did</span> <span m="2786170">a</span>
  <span m="2786640">reading</span> <span m="2787080">problem</span> <span m="2787400">that</span>
  <span m="2787804">I know</span> <span m="2788208">was</span> <span m="2789016">lots</span>
  <span m="2789420">of</span> <span m="2789510">issues,</span> <span m="2789990">because</span>
  <span m="2790860">it</span> <span m="2791030">broke</span> <span m="2791340">the</span>
  <span m="2791500">MITX</span> <span m="2793630">platform''s</span> <span m="2793840">ability</span>
  <span m="2794410">to</span> <span m="2795450">take</span> <span m="2795700">pictures</span>
  <span m="2796070">as</span> <span m="2796220">an</span> <span m="2796310">answer.</span>
  <span m="2797480">But</span> <span m="2797630">you</span> <span m="2797720">computed</span>
  <span m="2798210">the</span> <span m="2798280">gradient</span> <span m="2798700">vector.</span>
  <span m="2800130">And</span> <span m="2800260">then</span> <span m="2800420">you</span>
  <span m="2801890">substituted</span> <span m="2802370">a</span> <span m="2802530">particular</span>
  <span m="2803080">value</span> <span m="2803600">of</span> <span m="2803820">the</span>
  <span m="2803890">design</span> <span m="2804200">vector x.</span> <span m="2804690">And
  then the</span> <span m="2805150">gradients</span> <span m="2805470">just</span>
  <span m="2805690">came out</span> <span m="2806000">to be</span> <span m="2806100">numbers,</span>
  <span m="2806600">right?</span> <span m="2807038">Yup.</span></p><p><span m="2810110">So</span>
  <span m="2810520">that''s</span> <span m="2810770">the</span> <span m="2810830">gradient.</span>
  <span m="2811510">So when we</span> <span m="2811750">talk</span> <span m="2811890">about</span>
  <span m="2812060">the</span> <span m="2812130">gradient</span> <span m="2813550">of</span>
  <span m="2813850">the</span> <span m="2813970">objective,</span> <span m="2814640">it''s</span>
  <span m="2814850">an</span> <span m="2815020">n</span> <span m="2815420">by</span>
  <span m="2815580">1</span> <span m="2815810">vector</span> <span m="2817110">that</span>
  <span m="2817290">contains</span> <span m="2817650">the</span> <span m="2817750">partial</span>
  <span m="2818050">derivative.</span> <span m="2819440">And</span> <span m="2819720">so</span>
  <span m="2820150">if</span> <span m="2820290">we</span> <span m="2820480">had</span>
  <span m="2820630">a</span> <span m="2820660">gradient</span> <span m="2820950">[INAUDIBLE]</span>
  <span m="2824920">have</span> <span m="2825530">[INAUDIBLE]</span> <span m="2827990">is
  also</span> <span m="2828260">going</span> <span m="2828410">to</span> <span m="2828490">be</span>
  <span m="2828660">a</span> <span m="2829050">vector</span> <span m="2829450">of</span>
  <span m="2829670">dimension</span> <span m="2830120">n.</span></p><p><span m="2833960">OK.</span>
  <span m="2834330">So</span> <span m="2836450">we</span> <span m="2836600">know</span>
  <span m="2836810">that</span> <span m="2837060">we</span> <span m="2837200">need</span>
  <span m="2838810">gradient</span> <span m="2839300">of j</span> <span m="2839610">equals</span>
  <span m="2839930">0</span> <span m="2840450">to</span> <span m="2840590">be</span>
  <span m="2840740">at</span> <span m="2841204">an</span> <span m="2843060">optimal</span>
  <span m="2843440">point.</span> <span m="2844520">Yup.</span> <span m="2844760">Minimum,</span>
  <span m="2845100">maximum,</span> <span m="2845620">all at</span> <span m="2845850">[INAUDIBLE]</span>
  <span m="2846150">point.</span> <span m="2847210">So</span> <span m="2847420">gradient
  of</span> <span m="2847720">j</span> <span m="2848000">equals</span> <span m="2848100">0</span>
  <span m="2848360">means</span> <span m="2848540">that</span> <span m="2848610">all
  these</span> <span m="2848700">partials</span> <span m="2849120">have</span> <span
  m="2849750">to</span> <span m="2849830">be</span> <span m="2849970">equal</span>
  <span m="2850190">to</span> <span m="2850260">0.</span></p><p><span m="2851710">But</span>
  <span m="2851950">we</span> <span m="2852060">also</span> <span m="2852540">said</span>
  <span m="2852870">that</span> <span m="2853040">if</span> <span m="2853190">we</span>
  <span m="2853280">wanted</span> <span m="2853520">to</span> <span m="2853600">be</span>
  <span m="2853710">sure</span> <span m="2853910">that</span> <span m="2854050">we''re</span>
  <span m="2854270">at</span> <span m="2854560">a</span> <span m="2854680">minimum,</span>
  <span m="2855980">we</span> <span m="2856130">need</span> <span m="2856260">to</span>
  <span m="2856330">look</span> <span m="2856490">at</span> <span m="2856550">the</span>
  <span m="2856610">second</span> <span m="2856910">derivative</span> <span m="2857480">information.</span>
  <span m="2858894">So</span> <span m="2859650">what</span> <span m="2860300">is</span>
  <span m="2860390">the</span> <span m="2860470">second</span> <span m="2860830">derivative</span>
  <span m="2861460">of</span> <span m="2861660">j</span> <span m="2862250">with</span>
  <span m="2862420">respect to</span> <span m="2862550">x?</span> <span m="2863170">What</span>
  <span m="2863350">dimension</span> <span m="2863420">does it</span> <span m="2863870">have?</span>
  <span m="2867470">n by n.</span> <span m="2868200">It''s</span> <span m="2868410">an</span>
  <span m="2868520">n by n</span> <span m="2869450">matrix.</span> <span m="2870050">And</span>
  <span m="2870150">it''s</span> <span m="2870260">called</span> <span m="2870500">the</span>
  <span m="2870570">Hessian.</span></p><p><span m="2873950">So the</span> <span m="2874250">Hessian</span>
  <span m="2874450">matrix</span> <span m="2875110">is</span> <span m="2875400">a</span>
  <span m="2875470">matrix</span> <span m="2876470">of</span> <span m="2877130">second</span>
  <span m="2877520">derivative.</span> <span m="2878794">So it''s</span> <span m="2879186">an</span>
  <span m="2879580">n</span> <span m="2879890">by n</span> <span m="2880200">matrix.</span>
  <span m="2883500">So</span> <span m="2883560">we</span> <span m="2883650">could</span>
  <span m="2883800">write</span> <span m="2884100">it</span> <span m="2884560">as</span>
  <span m="2885020">grad</span> <span m="2885480">squared</span> <span m="2885940">j.</span>
  <span m="2887720">And</span> <span m="2889220">so</span> <span m="2889640">it''s
  just</span> <span m="2891180">on</span> <span m="2891310">the</span> <span m="2891400">diagonal,</span>
  <span m="2892000">we''re</span> <span m="2892080">going</span> <span m="2892210">to</span>
  <span m="2892290">be</span> <span m="2893090">the</span> <span m="2893220">pure</span>
  <span m="2893600">partial.</span> <span m="2894180">Del</span> <span m="2894440">squared</span>
  <span m="2894690">j</span> <span m="2895190">del</span> <span m="2895340">x1</span>
  <span m="2895810">squared</span> <span m="2897130">del</span> <span m="2897430">squared</span>
  <span m="2897540">j</span> <span m="2897700">del</span> <span m="2898077">x2</span>
  <span m="2898831">squared</span> <span m="2900170">all</span> <span m="2900290">the</span>
  <span m="2900350">way</span> <span m="2900540">down</span> <span m="2900960">to</span>
  <span m="2902030">del</span> <span m="2902140">squared j</span> <span m="2902320">del</span>
  <span m="2902791">xn</span> <span m="2903262">squared.</span></p><p><span m="2906560">And</span>
  <span m="2906760">then</span> <span m="2907550">on</span> <span m="2907760">the</span>
  <span m="2907870">up</span> <span m="2908040">diagonals</span> <span m="2908360">are</span>
  <span m="2908820">they</span> <span m="2910146">mixed</span> <span m="2910588">terms,</span>
  <span m="2911030">del</span> <span m="2911450">squared</span> <span m="2911850">j</span>
  <span m="2912338">del</span> <span m="2912826">x</span> <span m="2913314">1</span>
  <span m="2914290">del</span> <span m="2914780">x1</span> <span m="2915120">del</span>
  <span m="2915572">x2</span> <span m="2916476">and</span> <span m="2916930">so on.</span>
  <span m="2917130">Del</span> <span m="2917586">squared</span> <span m="2918042">j</span>
  <span m="2919380">del</span> <span m="2919770">x1,</span> <span m="2920505">del</span>
  <span m="2920850">x10.</span> <span m="2924020">And</span> <span m="2926160">what''s</span>
  <span m="2926260">special</span> <span m="2926530">about this</span> <span m="2926770">matrix?</span></p><p><span
  m="2928960">It''s</span> <span m="2929120">symmetric.</span> <span m="2929830">Because</span>
  <span m="2930490">a</span> <span m="2931200">mixed</span> <span m="2931500">partial</span>
  <span m="2932980">with</span> <span m="2933140">respect</span> <span m="2933880">to</span>
  <span m="2934170">2,</span> <span m="2934610">1</span> <span m="2934690">is the
  same</span> <span m="2934950">as</span> <span m="2935040">the</span> <span m="2935130">next</span>
  <span m="2935430">partial</span> <span m="2935790">with</span> <span m="2935940">respect</span>
  <span m="2936380">to</span> <span m="2941450">1,</span> <span m="2941650">2.</span>
  <span m="2943820">So</span> <span m="2944635">n by n</span> <span m="2945090">matrix,</span>
  <span m="2945380">it''s</span> <span m="2946030">symmetric.</span> <span m="2948740">And</span>
  <span m="2949300">so</span> <span m="2949470">in</span> <span m="2949560">the</span>
  <span m="2949660">scalar</span> <span m="2950260">case,</span> <span m="2951690">if</span>
  <span m="2951850">you</span> <span m="2952000">wanted</span> <span m="2952510">to</span>
  <span m="2952650">minimize--</span> <span m="2953976">how</span> <span m="2954322">do</span>
  <span m="2954670">I</span> <span m="2954720">want</span> <span m="2954860">to</span>
  <span m="2954920">put</span> <span m="2955080">it?</span></p><p><span m="2957040">Let
  me</span> <span m="2957490">put it here.</span> <span m="2957940">So in</span> <span
  m="2958030">the</span> <span m="2958110">scalar case</span> <span m="2961080">if</span>
  <span m="2961240">I</span> <span m="2961450">asked</span> <span m="2961770">you</span>
  <span m="2963200">to</span> <span m="2963260">find</span> <span m="2963520">a</span>
  <span m="2963570">minimum</span> <span m="2965032">of</span> <span m="2965464">f
  of x</span> <span m="2966330">where</span> <span m="2966440">x was a</span> <span
  m="2966520">scalar</span> <span m="2967010">and f was</span> <span m="2967170">a
  scalar,</span> <span m="2968750">you would</span> <span m="2968900">have</span>
  <span m="2969200">two</span> <span m="2969270">conditions,</span> <span m="2969840">right?</span>
  <span m="2970090">You</span> <span m="2970190">would</span> <span m="2970400">say,</span>
  <span m="2971000">yes,</span> <span m="2971210">the x</span> <span m="2971465">equals</span>
  <span m="2971900">0.</span></p><p><span m="2975620">And</span> <span m="2975910">then</span>
  <span m="2976160">second</span> <span m="2976530">derivative,</span> <span m="2982325">[INAUDIBLE]</span>
  <span m="2983760">positive.</span> <span m="2986208">And</span> <span m="2986690">that</span>
  <span m="2986890">would</span> <span m="2987010">be</span> <span m="2987360">evaluated</span>
  <span m="2987930">at</span> <span m="2988050">the x,</span> <span m="2989700">the</span>
  <span m="2989830">optimum</span> <span m="2990330">point.</span> <span m="2990740">So
  we could</span> <span m="2991000">have made it</span> <span m="2991250">evaluate</span>
  <span m="2991590">it at</span> <span m="2991930">x star.</span></p><p><span m="2996030">So
  you''ve</span> <span m="2996090">seen all</span> <span m="2996230">this</span> <span
  m="2996630">before,</span> <span m="2996970">right?</span> <span m="2997310">This</span>
  <span m="2997340">is</span> <span m="2998420">1801</span> <span m="2999100">or</span>
  <span m="2999230">high</span> <span m="2999360">school</span> <span m="3000310">calculus.</span>
  <span m="3001420">So</span> <span m="3001690">in</span> <span m="3001860">our</span>
  <span m="3002060">case,</span> <span m="3003710">we</span> <span m="3003910">are</span>
  <span m="3004280">trying</span> <span m="3004530">to</span> <span m="3004600">minimize</span>
  <span m="3005180">j</span> <span m="3005630">which</span> <span m="3005900">isn''t</span>
  <span m="3006170">a</span> <span m="3006320">scalar,</span> <span m="3007046">but</span>
  <span m="3007410">now it''s a</span> <span m="3007440">function</span> <span m="3007870">of</span>
  <span m="3008090">the</span> <span m="3008690">design</span> <span m="3009100">vector</span>
  <span m="3009390">x.</span></p><p><span m="3010530">So</span> <span m="3010630">the</span>
  <span m="3010700">corresponding</span> <span m="3011350">condition</span> <span
  m="3011750">here</span> <span m="3012120">is</span> <span m="3012250">this</span>
  <span m="3012510">grad</span> <span m="3013140">j</span> <span m="3014300">evaluated</span>
  <span m="3014400">at</span> <span m="3014680">x star</span> <span m="3015102">equals</span>
  <span m="3015524">0.</span> <span m="3016790">We</span> <span m="3016890">can</span>
  <span m="3017020">put</span> <span m="3017190">a</span> <span m="3017550">[INAUDIBLE]</span>
  <span m="3017910">symbol</span> <span m="3018080">on</span> <span m="3018350">there</span>
  <span m="3018960">if</span> <span m="3019080">you</span> <span m="3019160">want</span>
  <span m="3019280">to</span> <span m="3019340">remind</span> <span m="3019660">yourself</span>
  <span m="3020130">that</span> <span m="3020920">this is</span> <span m="3021140">an</span>
  <span m="3021240">n by</span> <span m="3021570">1</span> <span m="3021740">vector,</span>
  <span m="3022190">and</span> <span m="3022490">[INAUDIBLE]</span> <span m="3022840">grad
  j</span> <span m="3023175">equals</span> <span m="3023510">0</span> <span m="3023730">means</span>
  <span m="3024170">putting all</span> <span m="3024595">those</span> <span m="3025020">entries</span>
  <span m="3025210">to 0.</span></p><p><span m="3026810">What''s</span> <span m="3027040">the</span>
  <span m="3027370">corresponding</span> <span m="3028110">case</span> <span m="3028380">here?</span>
  <span m="3029132">What''s</span> <span m="3029510">the</span> <span m="3030210">analogous</span>
  <span m="3030770">condition</span> <span m="3031510">to</span> <span m="3031660">second</span>
  <span m="3031930">derivative</span> <span m="3032320">being</span> <span m="3032770">positive?</span>
  <span m="3036235">Who''s</span> <span m="3036730">taken</span> <span m="3037060">1806?</span>
  <span m="3046610">Here</span> <span m="3046910">it''s</span> <span m="3047030">a</span>
  <span m="3047090">scalar.</span> <span m="3047350">And</span> <span m="3047610">it''s</span>
  <span m="3047700">got</span> <span m="3047830">to</span> <span m="3047890">be</span>
  <span m="3048000">positive.</span> <span m="3048740">Here, it''s a</span> <span
  m="3048820">matrix.</span></p><p><span m="3056780">What</span> <span m="3056910">have</span>
  <span m="3057000">you</span> <span m="3057100">ever</span> <span m="3057250">heard</span>
  <span m="3057450">about</span> <span m="3057680">matrices</span> <span m="3057970">and</span>
  <span m="3058350">being</span> <span m="3058560">positive.</span> <span m="3061000">Positive</span>
  <span m="3061430">definite,</span> <span m="3061810">yeah.</span> <span m="3062782">So
  the</span> <span m="3063270">condition</span> <span m="3063670">is</span> <span
  m="3063820">that</span> <span m="3063980">the</span> <span m="3064370">[INAUDIBLE]</span>
  <span m="3064770">matrix</span> <span m="3066910">grad squared</span> <span m="3067380">j,</span>
  <span m="3068230">again,</span> <span m="3068480">evaluated</span> <span m="3068920">at
  the</span> <span m="3070366">thing.</span> <span m="3070850">And</span> <span m="3071090">[INAUDIBLE]</span>
  <span m="3071270">write</span> <span m="3071480">it</span> <span m="3071600">that</span>
  <span m="3071760">way.</span></p><p><span m="3074780">In  symmetric</span> <span
  m="3075040">matrix,</span> <span m="3075410">all</span> <span m="3075780">eigenvalues</span>
  <span m="3076250">have</span> <span m="3076470">to</span> <span m="3076580">be</span>
  <span m="3076710">positive.</span> <span m="3077410">They''re</span> <span m="3077500">going
  to</span> <span m="3077640">be</span> <span m="3077750">real and</span> <span m="3078080">positive.</span>
  <span m="3079462">So</span> <span m="3079890">in</span> <span m="3079990">another</span>
  <span m="3080320">way,</span> <span m="3081976">for</span> <span m="3082390">any</span>
  <span m="3083370">vector,</span> <span m="3083710">say</span> <span m="3083920">y,</span>
  <span m="3084220">y</span> <span m="3084550">transposed</span> <span m="3085490">times
  this</span> <span m="3085940">matrix</span> <span m="3086470">times</span> <span
  m="3086710">y</span> <span m="3087010">has</span> <span m="3087150">to</span> <span
  m="3087240">be</span> <span m="3087330">strictly</span> <span m="3087620">positive,</span>
  <span m="3088060">which</span> <span m="3088100">you</span> <span m="3088180">can</span>
  <span m="3088360">show</span> <span m="3088580">that</span> <span m="3089020">it''s</span>
  <span m="3089460">equivalent</span> <span m="3089550">to the</span> <span m="3089660">eigenvalue</span>
  <span m="3090130">[INAUDIBLE].</span></p><p><span m="3091982">So</span> <span m="3093575">turns</span>
  <span m="3093900">out</span> <span m="3094180">the</span> <span m="3094260">eigenvalues</span>
  <span m="3094770">of</span> <span m="3094840">this</span> <span m="3094930">Hessian</span>
  <span m="3095330">matrix</span> <span m="3095930">tell</span> <span m="3096110">you</span>
  <span m="3096270">an</span> <span m="3096370">awful</span> <span m="3096650">lot</span>
  <span m="3096950">about</span> <span m="3097190">the</span> <span m="3097290">shape</span>
  <span m="3097600">of</span> <span m="3097700">your</span> <span m="3097820">design
  space.</span> <span m="3099410">And</span> <span m="3099760">maybe</span> <span
  m="3100010">intuitively,</span> <span m="3104600">I</span> <span m="3104950">find</span>
  <span m="3105170">it</span> <span m="3105240">conceptually</span> <span m="3105630">easy</span>
  <span m="3105840">to</span> <span m="3105920">think</span> <span m="3106080">about</span>
  <span m="3106280">maximizing.</span> <span m="3107180">If</span> <span m="3107310">I''m</span>
  <span m="3107430">standing</span> <span m="3107750">at</span> <span m="3107810">the</span>
  <span m="3107880">top</span> <span m="3108080">of</span> <span m="3108160">the</span>
  <span m="3108260">hill and</span> <span m="3108500">I''m</span> <span m="3108600">trying</span>
  <span m="3108780">to</span> <span m="3108840">maximize</span> <span m="3111270">and</span>
  <span m="3111500">think</span> <span m="3111710">about</span> <span m="3111930">the</span>
  <span m="3112030">eigenvalues</span> <span m="3113240">and</span> <span m="3113510">eigenvectors,</span>
  <span m="3114960">there''s</span> <span m="3115110">no</span> <span m="3115340">direction</span>
  <span m="3115820">I</span> <span m="3115880">can</span> <span m="3116090">move</span>
  <span m="3116350">where</span> <span m="3116750">things</span> <span m="3116970">are</span>
  <span m="3117010">going</span> <span m="3117130">to</span> <span m="3117190">increase,
  right?</span> <span m="3117950">So</span> <span m="3118330">that</span> <span m="3118500">means</span>
  <span m="3118660">all</span> <span m="3118840">the</span> <span m="3118960">eigenvector</span>
  <span m="3119420">directions</span> <span m="3120660">are</span> <span m="3120710">going</span>
  <span m="3120830">to</span> <span m="3120890">have</span> <span m="3121010">to</span>
  <span m="3121110">be</span> <span m="3121230">associated</span> <span m="3122180">with</span>
  <span m="3122400">decrease.</span></p><p><span m="3124020">And</span> <span m="3124190">so</span>
  <span m="3124860">this would</span> <span m="3125030">be</span> <span m="3125200">flipping,</span>
  <span m="3125660">right?</span> <span m="3127120">To</span> <span m="3127370">be
  the</span> <span m="3127440">maximum,</span> <span m="3128790">the</span> <span
  m="3129110">Hessian</span> <span m="3129220">would</span> <span m="3129360">have
  to be</span> <span m="3129500">negative</span> <span m="3129840">definite.</span>
  <span m="3131590">And</span> <span m="3132100">so</span> <span m="3132300">it</span>
  <span m="3132390">kind</span> <span m="3132530">of</span> <span m="3132590">makes</span>
  <span m="3132780">sense</span> <span m="3133090">that</span> <span m="3133150">the</span>
  <span m="3133240">eigenvalues</span> <span m="3133840">of</span> <span m="3133910">the</span>
  <span m="3133980">Hessian</span> <span m="3134300">are</span> <span m="3134370">going</span>
  <span m="3134490">to</span> <span m="3134610">relate</span> <span m="3135100">to</span>
  <span m="3135480">what</span> <span m="3135815">goes</span> <span m="3136150">on
  as</span> <span m="3136310">we</span> <span m="3136400">move</span> <span m="3136600">away</span>
  <span m="3136870">from</span> <span m="3137070">a</span> <span m="3137250">minimum</span>
  <span m="3138360">or</span> <span m="3138460">a</span> <span m="3138560">maximum</span>
  <span m="3138970">point.</span></p><p><span m="3140500">OK.</span> <span m="3140760">So</span>
  <span m="3141690">we''ve</span> <span m="3141740">got</span> <span m="3141860">gradient.</span>
  <span m="3142100">We''ve</span> <span m="3142430">Hessian.</span> <span m="3142570">We</span>
  <span m="3142835">need one</span> <span m="3143100">more thing,</span> <span m="3143630">which</span>
  <span m="3143850">is</span> <span m="3144120">your</span> <span m="3144460">old</span>
  <span m="3144640">friend</span> <span m="3145430">Taylor</span> <span m="3145670">series</span>
  <span m="3145910">expansion.</span> <span m="3146400">Yeah,</span> <span m="3146645">Greg.</span></p><p><span
  m="3147380">AUDIENCE: Can you</span> <span m="3147870">go over</span> <span m="3148360">that
  definition</span> <span m="3148850">[INAUDIBLE]?</span></p><p><span m="3149830">PROFESSOR:
  OK.</span> <span m="3150480">This</span> <span m="3150550">right</span> <span m="3151010">here?</span>
  <span m="3151510">Yeah.</span> <span m="3152470">So</span> <span m="3152700">let</span>
  <span m="3153110">me</span> <span m="3153200">write</span> <span m="3153370">it</span>
  <span m="3153460">out</span> <span m="3153650">here</span> <span m="3153990">to</span>
  <span m="3154110">be--</span> <span m="3160601">So</span> <span m="3161980">let''s</span>
  <span m="3162460">call</span> <span m="3162670">it</span> <span m="3162790">h.</span>
  <span m="3163660">So</span> <span m="3163780">let''s</span> <span m="3164020">write</span>
  <span m="3164802">the</span> <span m="3165204">Hessian--</span> <span m="3166410">I''m
  just</span> <span m="3166490">going to call</span> <span m="3166745">it</span> <span
  m="3167000">h,</span> <span m="3167110">so I</span> <span m="3167300">don''t have</span>
  <span m="3167700">to</span> <span m="3168560">keep</span> <span m="3168740">writing</span>
  <span m="3168940">grad squared j.</span></p><p><span m="3170270">So</span> <span
  m="3170460">the</span> <span m="3170540">condition</span> <span m="3170950">is</span>
  <span m="3171170">that</span> <span m="3171420">h</span> <span m="3173050">is</span>
  <span m="3173280">positive</span> <span m="3173780">definite.</span> <span m="3178570">And</span>
  <span m="3178740">what</span> <span m="3178900">that</span> <span m="3179070">means--</span>
  <span m="3179870">we</span> <span m="3180050">write</span> <span m="3180290">it</span>
  <span m="3180490">this way,</span> <span m="3180670">h</span> <span m="3181180">is</span>
  <span m="3181240">a</span> <span m="3181340">matrix.</span> <span m="3181950">What</span>
  <span m="3182400">that</span> <span m="3182590">means</span> <span m="3182855">is</span>
  <span m="3183120">that</span> <span m="3184490">v</span> <span m="3184930">transpose</span>
  <span m="3185800">hv</span> <span m="3187800">has</span> <span m="3187980">to</span>
  <span m="3188090">be</span> <span m="3188220">positive</span> <span m="3189880">for</span>
  <span m="3190130">av,</span> <span m="3191950">for</span> <span m="3192180">any</span>
  <span m="3192520">v</span> <span m="3192976">that''s</span> <span m="3193890">not</span>
  <span m="3194110">0.</span></p><p><span m="3195960">So we</span> <span m="3196440">take</span>
  <span m="3196700">any</span> <span m="3197450">vector</span> <span m="3197650">v</span>
  <span m="3198770">and</span> <span m="3198940">do</span> <span m="3199310">the</span>
  <span m="3199400">b</span> <span m="3199520">transpose</span> <span m="3199790">hv.</span>
  <span m="3200340">And</span> <span m="3201180">that</span> <span m="3201700">has</span>
  <span m="3201900">to</span> <span m="3201980">be</span> <span m="3202110">positive.</span>
  <span m="3202890">If</span> <span m="3202970">that''s</span> <span m="3203170">true,</span>
  <span m="3203330">then</span> <span m="3203530">h</span> <span m="3203880">is</span>
  <span m="3204060">positive</span> <span m="3204160">definite.</span> <span m="3204760">And</span>
  <span m="3205250">then,</span> <span m="3205610">because</span> <span m="3205820">h</span>
  <span m="3205940">is</span> <span m="3206170">symmetric</span> <span m="3206660">matrix,</span>
  <span m="3208210">that</span> <span m="3208610">is</span> <span m="3208910">the</span>
  <span m="3209010">same</span> <span m="3209280">condition</span> <span m="3209890">as</span>
  <span m="3210050">saying</span> <span m="3211040">all</span> <span m="3211760">the</span>
  <span m="3212510">eigenvalues</span> <span m="3214840">of</span> <span m="3214990">h--
  and there are</span> <span m="3215160">going</span> <span m="3215500">to</span>
  <span m="3215560">the</span> <span m="3215750">n</span> <span m="3216000">of</span>
  <span m="3216100">them--</span> <span m="3216890">have</span> <span m="3217060">to</span>
  <span m="3217160">also</span> <span m="3217480">be</span> <span m="3218880">positive.</span>
  <span m="3222970">It''s</span> <span m="3223140">a</span> <span m="3223190">property</span>
  <span m="3223610">of</span> <span m="3223830">the matrix.</span></p><p><span m="3225243">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="3231380">PROFESSOR: Yeah.</span></p><p><span m="3232380">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="3242150">PROFESSOR: So</span> <span m="3242350">if</span>
  <span m="3242500">not</span> <span m="3242710">all</span> <span m="3242780">the</span>
  <span m="3242890">eigenvalues</span> <span m="3243380">are</span> <span m="3243430">positive,</span>
  <span m="3244300">if</span> <span m="3244770">some</span> <span m="3244920">of</span>
  <span m="3244980">them</span> <span m="3245130">are</span> <span m="3245280">0,</span>
  <span m="3246090">then</span> <span m="3246250">it</span> <span m="3246360">means--</span></p><p><span
  m="3247358">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3250350">PROFESSOR: Well,</span>
  <span m="3250710">so if</span> <span m="3250800">some</span> <span m="3251000">of</span>
  <span m="3251060">the</span> <span m="3251140">eigenvalues</span> <span m="3251850">are</span>
  <span m="3252310">positive</span> <span m="3252470">and some</span> <span m="3252910">are</span>
  <span m="3252960">negative,</span> <span m="3253340">it means</span> <span m="3253640">you''re</span>
  <span m="3253700">at</span> <span m="3253770">a</span> <span m="3253990">settle</span>
  <span m="3254110">point.</span> <span m="3254790">You''ve</span> <span m="3255020">seen
  that</span> <span m="3255280">in the</span> <span m="3255753">1dk--</span></p><p><span
  m="3256699">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3260490">PROFESSOR: So</span>
  <span m="3261620">I</span> <span m="3261710">don''t</span> <span m="3261840">know</span>
  <span m="3261950">how</span> <span m="3262050">to</span> <span m="3262140">act</span>
  <span m="3262390">this</span> <span m="3262950">out.</span> <span m="3263350">But</span>
  <span m="3263500">in</span> <span m="3263610">a</span> <span m="3263680">landscape</span>
  <span m="3264220">if</span> <span m="3264450">I</span> <span m="3264510">a</span>
  <span m="3264700">settle</span> <span m="3264760">point</span> <span m="3265060">is</span>
  <span m="3265170">[INAUDIBLE]</span> <span m="3270860">point</span> <span m="3271120">means</span>
  <span m="3272190">that</span> <span m="3272660">the</span> <span m="3273500">[INAUDIBLE]</span>
  <span m="3273610">goes</span> <span m="3273820">this</span> <span m="3274050">way</span>
  <span m="3274300">in</span> <span m="3274390">one</span> <span m="3274550">direction,</span>
  <span m="3274980">but</span> <span m="3275420">this</span> <span m="3275650">way</span>
  <span m="3275770">in the</span> <span m="3275930">other.</span> <span m="3276080">So
  there''s</span> <span m="3276450">still a</span> <span m="3276510">direction</span>
  <span m="3276870">that</span> <span m="3276990">I</span> <span m="3277060">can</span>
  <span m="3277260">move</span> <span m="3277610">to</span> <span m="3277840">[INAUDIBLE].</span></p><p><span
  m="3278824">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3284730">PROFESSOR: So maybe</span>
  <span m="3284840">[INAUDIBLE]</span> <span m="3285370">said</span> <span m="3285550">another</span>
  <span m="3285790">way.</span> <span m="3286390">An</span> <span m="3286490">optimization</span>
  <span m="3286920">algorithm</span> <span m="3287340">that''s</span> <span m="3287470">trying</span>
  <span m="3287760">to</span> <span m="3288270">minimize</span> <span m="3288760">or</span>
  <span m="3288820">maximize</span> <span m="3289250">something</span> <span m="3289640">won''t</span>
  <span m="3291440">stop</span> <span m="3291720">at</span> <span m="3291800">those</span>
  <span m="3292020">points.</span> <span m="3292590">Because</span> <span m="3292850">it</span>
  <span m="3292930">will</span> <span m="3293060">be</span> <span m="3293270">up</span>
  <span m="3293400">to</span> <span m="3293480">find</span> <span m="3293680">a</span>
  <span m="3293710">direction</span> <span m="3294120">of</span> <span m="3294200">improvement.</span></p><p><span
  m="3295170">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3296625">PROFESSOR: No,</span>
  <span m="3297110">it''ll keep</span> <span m="3297600">going.</span></p><p><span
  m="3298556">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3300950">PROFESSOR: That''s</span>
  <span m="3301150">right.</span> <span m="3301530">Think</span> <span m="3301720">about</span>
  <span m="3302000">standing</span> <span m="3302320">on--</span> <span m="3303260">you''re</span>
  <span m="3303410">standing</span> <span m="3303720">on</span> <span m="3303820">the</span>
  <span m="3303980">edge</span> <span m="3304150">and</span> <span m="3304290">things</span>
  <span m="3304490">are</span> <span m="3304570">dropping</span> <span m="3305140">either</span>
  <span m="3305330">side</span> <span m="3306120">of</span> <span m="3306310">you.</span>
  <span m="3306990">But</span> <span m="3307150">if</span> <span m="3307240">you''re</span>
  <span m="3307330">looking</span> <span m="3307580">front,</span> <span m="3307930">you</span>
  <span m="3308000">can</span> <span m="3308110">keep</span> <span m="3308240">going</span>
  <span m="3308490">up</span> <span m="3308590">the hill.</span></p><p><span m="3310286">So
  it''s</span> <span m="3310710">just</span> <span m="3311500">going</span> <span
  m="3311660">to</span> <span m="3312250">constrain</span> <span m="3312510">the</span>
  <span m="3312570">directions</span> <span m="3313010">in</span> <span m="3313100">which</span>
  <span m="3314010">you move.</span> <span m="3315390">But</span> <span m="3315850">the</span>
  <span m="3316310">problem</span> <span m="3317266">with</span> <span m="3318222">[AUDIO
  OUT]</span> <span m="3321090">as</span> <span m="3321470">we</span> <span m="3321550">got</span>
  <span m="3321740">into</span> <span m="3321990">the</span> <span m="3322210">[AUDIO
  OUT]</span> <span m="3323590">regions</span> <span m="3324670">where</span> <span
  m="3324970">[AUDIO OUT]</span> <span m="3327710">you</span> <span m="3327830">might
  know</span> <span m="3328070">[AUDIO OUT]</span> <span m="3334270">if</span> <span
  m="3334480">you''re</span> <span m="3334650">minimal</span> <span m="3335050">and
  not unique,</span> <span m="3335540">then</span> <span m="3335550">there''s</span>
  <span m="3335720">actually a</span> <span m="3335860">ridge.</span> <span m="3336640">The
  top of</span> <span m="3336740">the mountain</span> <span m="3336810">would</span>
  <span m="3336930">be</span> <span m="3337030">the</span> <span m="3337100">ridge.</span></p><p><span
  m="3337550">And</span> <span m="3337770">so</span> <span m="3337900">there''s</span>
  <span m="3338150">a</span> <span m="3338210">direction</span> <span m="3338680">that</span>
  <span m="3338780">you</span> <span m="3338880">can</span> <span m="3339030">walk</span>
  <span m="3339280">along,</span> <span m="3339800">and</span> <span m="3340000">you''re
  not</span> <span m="3340210">changing</span> <span m="3340580">an</span> <span m="3340660">objective.</span>
  <span m="3341290">You''re</span> <span m="3341780">staying at</span> <span m="3342270">constant</span>
  <span m="3342720">elevation.</span> <span m="3344060">And</span> <span m="3344210">that</span>
  <span m="3344360">would</span> <span m="3344480">correspond</span> <span m="3345080">to</span>
  <span m="3345230">one</span> <span m="3345610">of</span> <span m="3345750">the</span>
  <span m="3345850">eigenvalues</span> <span m="3346280">being</span> <span m="3346710">0.</span></p><p><span
  m="3347140">But</span> <span m="3347260">in</span> <span m="3347340">that</span>
  <span m="3347520">case,</span> <span m="3347810">what</span> <span m="3347940">you''ve</span>
  <span m="3348050">got</span> <span m="3348230">is</span> <span m="3348310">a</span>
  <span m="3348340">whole</span> <span m="3348470">bunch</span> <span m="3348690">of</span>
  <span m="3348770">designs</span> <span m="3349180">that</span> <span m="3349290">are</span>
  <span m="3349320">equally</span> <span m="3349740">good.</span> <span m="3350640">And</span>
  <span m="3350790">so</span> <span m="3350860">that''s</span> <span m="3351050">actually</span>
  <span m="3351250">kind</span> <span m="3351430">of</span> <span m="3351500">nice</span>
  <span m="3351780">to</span> <span m="3351890">know.</span> <span m="3352140">Because</span>
  <span m="3352380">that</span> <span m="3352500">would</span> <span m="3352610">be</span>
  <span m="3352710">different</span> <span m="3353040">design</span> <span m="3353440">decisions</span>
  <span m="3353850">that</span> <span m="3353960">you</span> <span m="3354040">could</span>
  <span m="3354180">make</span> <span m="3354490">that</span> <span m="3354965">were</span>
  <span m="3355440">all</span> <span m="3355915">as</span> <span m="3356390">good
  in</span> <span m="3356690">cost</span> <span m="3357010">or</span> <span m="3357160">whatever</span>
  <span m="3357420">it</span> <span m="3357500">is</span> <span m="3357610">you''re</span>
  <span m="3357680">trying</span> <span m="3357860">to</span> <span m="3358050">do.</span></p><p><span
  m="3358900">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3360600">PROFESSOR: Yeah.</span>
  <span m="3361260">So,</span> <span m="3361590">yeah.</span></p><p><span m="3362906">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="3369120">PROFESSOR: That''s</span> <span m="3369350">right.</span></p><p><span
  m="3370274">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3376000">PROFESSOR: Yeah.</span>
  <span m="3376310">So</span> <span m="3376940">you don''t</span> <span m="3377040">have</span>
  <span m="3377150">to</span> <span m="3377250">worry</span> <span m="3377490">about</span>
  <span m="3377680">this</span> <span m="3377770">stuff.</span> <span m="3378070">This</span>
  <span m="3378180">stuff</span> <span m="3378430">is</span> <span m="3378540">taken</span>
  <span m="3378910">care</span> <span m="3379460">of</span> <span m="3379920">for</span>
  <span m="3380160">you</span> <span m="3380660">when</span> <span m="3380860">you</span>
  <span m="3380950">run</span> <span m="3381130">something</span> <span m="3381370">like</span>
  <span m="3381580">fminunc</span> <span m="3382100">and</span> <span m="3382480">fmincon.</span>
  <span m="3383780">But</span> <span m="3384140">what''s</span> <span m="3385060">important</span>
  <span m="3385730">is</span> <span m="3387630">to</span> <span m="3387840">understand
  that</span> <span m="3388150">there</span> <span m="3388360">are</span> <span m="3388900">sort
  of</span> <span m="3389170">rigorous</span> <span m="3389750">mathematical</span>
  <span m="3390250">conditions</span> <span m="3390660">that tell</span> <span m="3390840">you</span>
  <span m="3391010">when</span> <span m="3391160">you''re</span> <span m="3391280">at</span>
  <span m="3391710">optimal</span> <span m="3392140">solution.</span> <span m="3393430">And</span>
  <span m="3394880">if</span> <span m="3395100">your</span> <span m="3395220">problem</span>
  <span m="3396170">sort of</span> <span m="3396380">obeys</span> <span m="3396890">the</span>
  <span m="3396960">given</span> <span m="3397310">structure,</span> <span m="3397830">then</span>
  <span m="3398950">that''s</span> <span m="3399180">great.</span> <span m="3399570">And
  that</span> <span m="3399900">holds.</span></p><p><span m="3400640">In</span> <span
  m="3400810">reality,</span> <span m="3401500">remember</span> <span m="3401820">when
  we</span> <span m="3401920">had</span> <span m="3402030">our</span> <span m="3402100">list</span>
  <span m="3402300">of</span> <span m="3402370">design</span> <span m="3402660">variables</span>
  <span m="3403060">we</span> <span m="3403160">talked</span> <span m="3403420">about</span>
  <span m="3403660">having</span> <span m="3403880">variables</span> <span m="3404270">like</span>
  <span m="3404380">number</span> <span m="3404640">of</span> <span m="3404730">engines?</span>
  <span m="3405760">That''s</span> <span m="3405920">something</span> <span m="3406190">for</span>
  <span m="3406310">which</span> <span m="3406540">the</span> <span m="3407220">gradient</span>
  <span m="3407500">doesn''t</span> <span m="3407710">even</span> <span m="3407900">exist,</span>
  <span m="3408390">right?</span> <span m="3409100">It''s</span> <span m="3409180">not</span>
  <span m="3409360">differentiable.</span></p><p><span m="3410790">And so</span> <span
  m="3411325">in</span> <span m="3411610">many</span> <span m="3411850">cases,</span>
  <span m="3412790">our</span> <span m="3412950">problems</span> <span m="3413420">don''t</span>
  <span m="3413610">even</span> <span m="3413890">satisfy</span> <span m="3414470">the</span>
  <span m="3415320">requirements</span> <span m="3416100">for</span> <span m="3416180">the</span>
  <span m="3416270">algorithms</span> <span m="3416790">that</span> <span m="3416920">we</span>
  <span m="3417040">use.</span> <span m="3417480">And so there</span> <span m="3417700">are</span>
  <span m="3417760">very</span> <span m="3417980">few</span> <span m="3418220">guarantees.</span>
  <span m="3418950">But</span> <span m="3419080">they</span> <span m="3419170">can</span>
  <span m="3419310">still</span> <span m="3419700">help us</span> <span m="3420090">make</span>
  <span m="3420330">progress.</span></p><p><span m="3421384">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="3431264">PROFESSOR: That''s</span> <span m="3431760">the</span> <span m="3431860">optimal</span>
  <span m="3432210">solution?</span></p><p><span m="3432700">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="3438170">PROFESSOR: If</span> <span m="3438430">there''s</span> <span m="3438890">one</span>
  <span m="3439020">of</span> <span m="3439090">these</span> <span m="3439250">ridges,</span>
  <span m="3439650">if</span> <span m="3439760">there''s a</span> <span m="3439820">non-unique</span>
  <span m="3440270">solution,</span> <span m="3440696">yeah.</span> <span m="3441550">Yeah.</span></p><p><span
  m="3443224">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3449700">PROFESSOR: Yeah.</span>
  <span m="3450220">So</span> <span m="3450390">integers</span> <span m="3451440">becomes</span>
  <span m="3451740">a</span> <span m="3451850">whole</span> <span m="3452260">other</span>
  <span m="3452670">ball</span> <span m="3452840">game.</span> <span m="3452990">And</span>
  <span m="3453090">maybe I should</span> <span m="3453450">have said</span> <span
  m="3453700">right</span> <span m="3453920">off</span> <span m="3454060">the</span>
  <span m="3454160">bat</span> <span m="3454410">that</span> <span m="3454540">when</span>
  <span m="3454690">you</span> <span m="3454790">start</span> <span m="3455750">looking</span>
  <span m="3456060">at</span> <span m="3456490">the</span> <span m="3456610">gradient</span>
  <span m="3456870">and</span> <span m="3457050">the</span> <span m="3457120">Hessian</span>
  <span m="3457430">analysis,</span> <span m="3458514">[INAUDIBLE]</span> <span m="3458958">j
  of</span> <span m="3459402">x</span> <span m="3460290">needs</span> <span m="3460510">to</span>
  <span m="3460600">be</span> <span m="3460920">at</span> <span m="3461010">least</span>
  <span m="3461190">twice</span> <span m="3461430">differentiable</span> <span m="3462400">with</span>
  <span m="3462590">respect</span> <span m="3462880">to</span> <span m="3462950">x.</span>
  <span m="3463230">Or otherwise,</span> <span m="3463632">what we''re</span> <span
  m="3464034">writing here</span> <span m="3464436">doesn''t make sense.</span></p><p><span
  m="3465240">When</span> <span m="3465390">you</span> <span m="3465460">have</span>
  <span m="3465640">integers,</span> <span m="3468210">the</span> <span m="3468310">conditions</span>
  <span m="3468700">become</span> <span m="3468980">more</span> <span m="3469350">complicated.</span>
  <span m="3469960">And</span> <span m="3470080">how</span> <span m="3470240">you</span>
  <span m="3470340">solve</span> <span m="3470680">the</span> <span m="3470790">problem</span>
  <span m="3471130">becomes</span> <span m="3471460">more</span> <span m="3471590">complicated.</span>
  <span m="3472130">One</span> <span m="3472290">approach</span> <span m="3472820">is</span>
  <span m="3473080">to</span> <span m="3473440">let</span> <span m="3473750">the</span>
  <span m="3473810">integers</span> <span m="3474210">vary,</span> <span m="3474490">exactly</span>
  <span m="3474760">what</span> <span m="3474890">you''re</span> <span m="3474960">saying.</span>
  <span m="3475710">And</span> <span m="3476000">then at the</span> <span m="3476180">end,</span>
  <span m="3476420">you</span> <span m="3476570">round.</span> <span m="3477470">And</span>
  <span m="3477580">that</span> <span m="3477760">might</span> <span m="3477960">be</span>
  <span m="3478050">effective,</span> <span m="3478720">but</span> <span m="3478800">it''s</span>
  <span m="3478960">certainly</span> <span m="3479130">not</span> <span m="3479300">guaranteed</span>
  <span m="3479680">to</span> <span m="3479760">find</span> <span m="3479960">an</span>
  <span m="3479990">optimal</span> <span m="3480370">solution.</span></p><p><span
  m="3481270">There</span> <span m="3481500">are</span> <span m="3481870">specialized</span>
  <span m="3482670">optimization</span> <span m="3485390">solution</span> <span m="3485810">methods</span>
  <span m="3486460">that</span> <span m="3486660">are</span> <span m="3486710">tailored</span>
  <span m="3487030">for</span> <span m="3487365">integer</span> <span m="3487700">programs.</span>
  <span m="3488180">And</span> <span m="3488280">in</span> <span m="3488380">fact,</span>
  <span m="3488420">MATLAB</span> <span m="3488660">just</span> <span m="3489010">released</span>
  <span m="3489970">a</span> <span m="3490080">mixed</span> <span m="3490390">integer</span>
  <span m="3490730">program,</span> <span m="3491140">I</span> <span m="3491200">think,</span>
  <span m="3491390">as</span> <span m="3491490">part</span> <span m="3491700">of</span>
  <span m="3491780">their</span> <span m="3492350">latest</span> <span m="3492640">release</span>
  <span m="3492870">of</span> <span m="3492940">the</span> <span m="3493000">optimization</span>
  <span m="3493520">toolbox.</span> <span m="3494300">And</span> <span m="3494440">these</span>
  <span m="3494640">methods</span> <span m="3494970">will</span> <span m="3495100">handle</span>
  <span m="3495360">the</span> <span m="3495780">integer</span> <span m="3496130">variables</span>
  <span m="3496650">in</span> <span m="3496710">different</span> <span m="3496970">ways.</span></p><p><span
  m="3497200">It''s</span> <span m="3497260">something</span> <span m="3497500">called</span>
  <span m="3497835">[INAUDIBLE]</span> <span m="3498170">bound,</span> <span m="3498570">which</span>
  <span m="3498800">is</span> <span m="3499360">about</span> <span m="3499660">searching</span>
  <span m="3499990">down</span> <span m="3500220">different</span> <span m="3500520">integer</span>
  <span m="3500800">combinations.</span> <span m="3502170">But</span> <span m="3502370">yeah,</span>
  <span m="3503710">integer</span> <span m="3503970">variables</span> <span m="3504360">make</span>
  <span m="3504530">it</span> <span m="3505030">really</span> <span m="3505530">difficult.</span>
  <span m="3506530">Yeah, Alex.</span></p><p><span m="3508530">AUDIENCE: [INAUDIBLE]</span>
  <span m="3509030">j</span> <span m="3510530">[INAUDIBLE].</span></p><p><span m="3514000">PROFESSOR:
  Yeah,</span> <span m="3514360">so we''re</span> <span m="3514500">going</span> <span
  m="3514630">to</span> <span m="3514710">talk</span> <span m="3514920">about--</span>
  <span m="3515500">that''s</span> <span m="3516150">sort</span> <span m="3516270">of</span>
  <span m="3516340">number</span> <span m="3516600">three.</span> <span m="3517620">j</span>
  <span m="3518020">is</span> <span m="3518130">usually</span> <span m="3518340">going</span>
  <span m="3518460">to</span> <span m="3518520">be</span> <span m="3518580">computer</span>
  <span m="3518940">code</span> <span m="3519840">that</span> <span m="3520000">we</span>
  <span m="3520100">can</span> <span m="3520260">put</span> <span m="3520440">in</span>
  <span m="3520630">the</span> <span m="3520720">shape</span> <span m="3520950">of</span>
  <span m="3521050">the</span> <span m="3521180">aircraft</span> <span m="3521550">wing</span>
  <span m="3522020">or</span> <span m="3522285">the whole</span> <span m="3522550">aircraft,</span>
  <span m="3523060">and out</span> <span m="3523350">comes</span> <span m="3523790">range</span>
  <span m="3524180">or</span> <span m="3524570">cost</span> <span m="3524960">or</span>
  <span m="3525070">whatever</span> <span m="3525320">it</span> <span m="3525390">is,</span>
  <span m="3525600">that''s right.</span> <span m="3525720">So</span> <span m="3525940">we</span>
  <span m="3526080">can</span> <span m="3526240">usually</span> <span m="3526580">only</span>
  <span m="3526800">get</span> <span m="3526970">j of</span> <span m="3527070">x</span>
  <span m="3527740">through</span> <span m="3527930">simulation</span> <span m="3529040">not</span>
  <span m="3529360">necessarily</span> <span m="3529880">by</span> <span m="3530000">analytic.</span></p><p><span
  m="3530440">And so then</span> <span m="3530630">we''re</span> <span m="3530700">going</span>
  <span m="3530820">to</span> <span m="3530880">need</span> <span m="3531150">some</span>
  <span m="3531360">way</span> <span m="3531630">to</span> <span m="3531740">compute</span>
  <span m="3533060">gradients.</span> <span m="3533530">And</span> <span m="3533620">what''s</span>
  <span m="3533780">really</span> <span m="3533950">nice</span> <span m="3534190">is</span>
  <span m="3534310">finite</span> <span m="3534580">differences,</span> <span m="3535120">which</span>
  <span m="3535270">you</span> <span m="3535360">guys</span> <span m="3535590">saw</span>
  <span m="3536430">back</span> <span m="3536870">a few</span> <span m="3537310">months</span>
  <span m="3537750">ago,</span> <span m="3538190">is</span> <span m="3538390">what</span>
  <span m="3538510">we''re</span> <span m="3538580">going</span> <span m="3538710">to</span>
  <span m="3538790">use</span> <span m="3538940">to do that.</span> <span m="3540383">Yeah.</span></p><p><span
  m="3541345">AUDIENCE: Like</span> <span m="3541826">also,</span> <span m="3542307">one
  thing we</span> <span m="3542788">talked about</span> <span m="3543269">[INAUDIBLE].</span></p><p><span
  m="3551750">PROFESSOR: So</span> <span m="3551910">it''s</span> <span m="3552020">all</span>
  <span m="3552120">taken</span> <span m="3552700">care</span> <span m="3553090">of,</span>
  <span m="3554300">because</span> <span m="3554600">we''re</span> <span m="3554710">not</span>
  <span m="3554940">sampling.</span> <span m="3555790">We''re</span> <span m="3556070">actually</span>
  <span m="3557130">measuring</span> <span m="3557580">the</span> <span m="3557660">gradient.</span>
  <span m="3558600">And</span> <span m="3563030">I</span> <span m="3563120">mean,</span>
  <span m="3564293">they''re</span> <span m="3564696">going</span> <span m="3565100">to</span>
  <span m="3565170">be--</span> <span m="3566110">I</span> <span m="3566170">mean,</span>
  <span m="3566320">we''re</span> <span m="3566570">doing</span> <span m="3566740">something</span>
  <span m="3566980">different</span> <span m="3567290">here, right?</span> <span m="3567560">We''re</span>
  <span m="3567670">moving</span> <span m="3568030">through</span> <span m="3568170">the</span>
  <span m="3568260">landscape.</span></p><p><span m="3569770">We''re</span> <span
  m="3569930">not</span> <span m="3570790">sampling,</span> <span m="3571390">and</span>
  <span m="3571480">then</span> <span m="3571690">trying</span> <span m="3572170">to</span>
  <span m="3573090">say</span> <span m="3573950">how</span> <span m="3574190">this</span>
  <span m="3574300">variable</span> <span m="3574550">relates</span> <span m="3575000">to</span>
  <span m="3575070">this</span> <span m="3575140">one.</span> <span m="3575410">We''re</span>
  <span m="3575570">actually</span> <span m="3575770">just</span> <span m="3575930">looking</span>
  <span m="3576310">for</span> <span m="3576420">an</span> <span m="3576500">optimum</span>
  <span m="3576880">solution.</span> <span m="3578160">It''s</span> <span m="3578340">a</span>
  <span m="3578380">different</span> <span m="3578750">thing.</span></p><p><span m="3578920">So</span>
  <span m="3579030">whatever</span> <span m="3579300">interactions</span> <span m="3579860">are</span>
  <span m="3580800">there,</span> <span m="3581520">how</span> <span m="3581750">are
  they</span> <span m="3581950">affected?</span> <span m="3582290">They''re</span>
  <span m="3582410">reflected</span> <span m="3582670">in</span> <span m="3582780">the</span>
  <span m="3582860">shape</span> <span m="3583100">of</span> <span m="3583200">the</span>
  <span m="3583280">landscape.</span> <span m="3584710">The</span> <span m="3584820">shape</span>
  <span m="3585570">that</span> <span m="3585650">the</span> <span m="3585720">landscape</span>
  <span m="3586160">takes</span> <span m="3586990">is</span> <span m="3587240">a</span>
  <span m="3587280">manifestation</span> <span m="3588130">of</span> <span m="3588880">how</span>
  <span m="3589220">the</span> <span m="3589470">design</span> <span m="3589940">variables</span>
  <span m="3590220">relate</span> <span m="3590470">to</span> <span m="3590600">each</span>
  <span m="3590770">other</span> <span m="3590890">and</span> <span m="3590990">how</span>
  <span m="3591090">they</span> <span m="3591220">affect</span> <span m="3591490">the
  objective.</span></p><p><span m="3597346">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="3598810">PROFESSOR: Yeah.</span> <span m="3599300">There</span> <span m="3599620">are.</span>
  <span m="3600190">And I''ll</span> <span m="3601030">show</span> <span m="3601240">you</span>
  <span m="3601700">some</span> <span m="3601900">of</span> <span m="3602030">those.</span>
  <span m="3605000">The</span> <span m="3605130">problem is</span> <span m="3605540">actually</span>
  <span m="3605790">now</span> <span m="3605910">to</span> <span m="3605990">guarantee</span>
  <span m="3606430">a</span> <span m="3606480">global</span> <span m="3606530">maximum.</span>
  <span m="3607410">So</span> <span m="3607850">there</span> <span m="3608010">are</span>
  <span m="3608040">a</span> <span m="3608070">whole</span> <span m="3608210">bunch</span>
  <span m="3608440">of</span> <span m="3608530">methods</span> <span m="3608930">called</span>
  <span m="3609460">heuristic</span> <span m="3610100">methods.</span> <span m="3610550">So</span>
  <span m="3610760">genetic</span> <span m="3611090">algorithms--</span> <span m="3612470">which</span>
  <span m="3613430">Professor</span> <span m="3613760">[? Devic ?]</span> <span m="3614090">uses</span>
  <span m="3614290">a lot in his</span> <span m="3614790">research,</span> <span m="3615290">which</span>
  <span m="3615790">I happen to</span> <span m="3616310">not</span> <span m="3616590">particularly</span>
  <span m="3616930">care</span> <span m="3617120">for--</span> <span m="3617850">are</span>
  <span m="3618340">ways to</span> <span m="3618410">do</span> <span m="3618520">that.</span>
  <span m="3619230">And</span> <span m="3619500">I''ll</span> <span m="3620200">show</span>
  <span m="3620380">you</span> <span m="3621050">maybe</span> <span m="3621240">in</span>
  <span m="3621310">the</span> <span m="3621380">next</span> <span m="3621620">lecture.</span></p><p><span
  m="3622520">They</span> <span m="3622670">sort</span> <span m="3622820">of</span>
  <span m="3622900">spray</span> <span m="3623220">points</span> <span m="3623550">everywhere.</span>
  <span m="3624020">And</span> <span m="3624120">then</span> <span m="3624250">they</span>
  <span m="3624420">use</span> <span m="3624550">an</span> <span m="3624640">analogy</span>
  <span m="3625150">with</span> <span m="3625390">natural</span> <span m="3625740">selection</span>
  <span m="3626290">and</span> <span m="3626710">mutations.</span> <span m="3628320">And</span>
  <span m="3628760">designs</span> <span m="3629200">have</span> <span m="3629410">babies.</span>
  <span m="3630030">And</span> <span m="3630170">then</span> <span m="3631770">the</span>
  <span m="3631880">strong</span> <span m="3632200">babies</span> <span m="3632630">survive</span>
  <span m="3633060">and</span> <span m="3633170">the</span> <span m="3633300">other</span>
  <span m="3633460">ones</span> <span m="3633830">don''t.</span> <span m="3635040">So</span>
  <span m="3635140">there</span> <span m="3635240">will</span> <span m="3635340">be</span>
  <span m="3635440">[INAUDIBLE].</span></p><p><span m="3636340">And you know,</span>
  <span m="3636700">people</span> <span m="3637190">sort</span> <span m="3637320">of</span>
  <span m="3637400">claim</span> <span m="3637650">that''s</span> <span m="3637910">a</span>
  <span m="3637960">way</span> <span m="3638070">to</span> <span m="3638150">do</span>
  <span m="3638310">global</span> <span m="3639460">optimization.</span> <span m="3640230">The</span>
  <span m="3640280">problem</span> <span m="3640640">is</span> <span m="3640730">there
  are</span> <span m="3640860">no</span> <span m="3641220">guarantees</span> <span
  m="3641390">at all.</span> <span m="3642330">I''ll</span> <span m="3642460">show</span>
  <span m="3642600">you</span> <span m="3642720">another</span> <span m="3643010">one,</span>
  <span m="3643260">which</span> <span m="3643410">is</span> <span m="3643500">a</span>
  <span m="3643570">patent</span> <span m="3643910">search,</span> <span m="3644280">which</span>
  <span m="3644450">sort of</span> <span m="3644800">has</span> <span m="3645010">a</span>
  <span m="3645070">guarantee</span> <span m="3645630">of</span> <span m="3645770">eventually</span>
  <span m="3646120">finding</span> <span m="3646490">a</span> <span m="3646530">global</span>
  <span m="3646790">solution,</span> <span m="3647290">but</span> <span m="3647460">only</span>
  <span m="3648210">[INAUDIBLE]</span> <span m="3648280">that</span> <span m="3648320">you</span>
  <span m="3648630">search</span> <span m="3648980">forever.</span></p><p><span m="3650660">Yeah.</span>
  <span m="3651240">And</span> <span m="3651580">it''s</span> <span m="3651740">a</span>
  <span m="3651810">really</span> <span m="3652150">hard</span> <span m="3652430">problem.</span>
  <span m="3652710">If</span> <span m="3652820">you</span> <span m="3652910">know</span>
  <span m="3653050">something</span> <span m="3653370">about</span> <span m="3653520">the</span>
  <span m="3653580">structure</span> <span m="3653900">of</span> <span m="3653970">your</span>
  <span m="3654090">problem,</span> <span m="3654410">you</span> <span m="3654730">maybe</span>
  <span m="3655080">have</span> <span m="3655180">to</span> <span m="3655280">do</span>
  <span m="3655450">something.</span> <span m="3655825">And</span> <span m="3656200">certain</span>
  <span m="3656450">problems,</span> <span m="3656820">like</span> <span m="3656930">we
  were</span> <span m="3657030">talking</span> <span m="3657190">about</span> <span
  m="3657480">before,</span> <span m="3657620">have</span> <span m="3657790">the</span>
  <span m="3658040">nice</span> <span m="3658500">structure</span> <span m="3658820">where
  you</span> <span m="3658930">can</span> <span m="3659080">be</span> <span m="3659230">rigorous.</span></p><p><span
  m="3659640">If</span> <span m="3659740">you</span> <span m="3659870">have</span>
  <span m="3660110">truly</span> <span m="3660370">just</span> <span m="3660520">kind</span>
  <span m="3660650">of</span> <span m="3660710">this</span> <span m="3660880">black</span>
  <span m="3661130">box</span> <span m="3661520">complicated</span> <span m="3662040">aircraft</span>
  <span m="3662370">design</span> <span m="3662720">problem,</span> <span m="3663630">there</span>
  <span m="3664400">are</span> <span m="3664450">no</span> <span m="3664610">guarantees.</span>
  <span m="3665350">But</span> <span m="3665480">again,</span> <span m="3665680">often</span>
  <span m="3665940">what</span> <span m="3666090">you''re</span> <span m="3666180">trying</span>
  <span m="3666360">to</span> <span m="3666420">do</span> <span m="3666630">is</span>
  <span m="3666770">to</span> <span m="3666870">find</span> <span m="3667130">a</span>
  <span m="3667170">good</span> <span m="3667450">design</span> <span m="3667910">that</span>
  <span m="3668020">meets</span> <span m="3668230">all</span> <span m="3668320">the</span>
  <span m="3668390">constraints</span> <span m="3668880">that''s</span> <span m="3669070">better</span>
  <span m="3669290">than</span> <span m="3669440">what</span> <span m="3669590">you</span>
  <span m="3669690">could</span> <span m="3669870">do</span> <span m="3670010">by</span>
  <span m="3670200">hand.</span> <span m="3671102">So</span> <span m="3672455">[INAUDIBLE].</span></p><p><span
  m="3674260">Yeah.</span> <span m="3674480">It depends.</span> <span m="3674940">Are</span>
  <span m="3675040">you</span> <span m="3675050">an</span> <span m="3675160">engineer</span>
  <span m="3675810">trying</span> <span m="3676010">to</span> <span m="3676070">make</span>
  <span m="3676220">a</span> <span m="3676260">good</span> <span m="3676440">design</span>
  <span m="3676750">decision?</span> <span m="3677100">Or</span> <span m="3677180">are</span>
  <span m="3677240">you</span> <span m="3677340">a</span> <span m="3677370">mathematician</span>
  <span m="3677670">who</span> <span m="3678070">wants</span> <span m="3678310">to</span>
  <span m="3678410">guarantee</span> <span m="3678970">optimality?</span> <span m="3680490">And</span>
  <span m="3681420">where</span> <span m="3681705">do you fall</span> <span m="3681990">in
  that?</span> <span m="3683834">So</span> <span m="3684295">that''s</span> <span
  m="3684760">god.</span></p><p><span m="3685040">So you</span> <span m="3685150">guys</span>
  <span m="3685380">have</span> <span m="3685510">lots</span> <span m="3685730">of</span>
  <span m="3685790">questions.</span> <span m="3687020">You''re</span> <span m="3687150">trying</span>
  <span m="3687290">to</span> <span m="3687450">avoid</span> <span m="3687830">getting</span>
  <span m="3688030">Taylor</span> <span m="3688340">series</span> <span m="3688600">expansions</span>
  <span m="3689120">I</span> <span m="3689210">know.</span> <span m="3692680">Any</span>
  <span m="3692900">other</span> <span m="3693040">questions?</span></p><p><span m="3696230">So</span>
  <span m="3696310">Greg,</span> <span m="3696490">does this</span> <span m="3696900">sort
  of answer--</span> <span m="3697210">I</span> <span m="3697310">know I</span> <span
  m="3697540">didn''t</span> <span m="3697860">do</span> <span m="3698010">it</span>
  <span m="3698090">very</span> <span m="3698260">deeply.</span> <span m="3698600">But</span>
  <span m="3699442">it''s probably</span> <span m="3699970">enough.</span></p><p><span
  m="3700680">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3701530">PROFESSOR: So</span>
  <span m="3701940">just</span> <span m="3702730">the</span> <span m="3702930">last</span>
  <span m="3703890">mathematical</span> <span m="3704460">ingredient</span> <span
  m="3704980">that</span> <span m="3705150">we</span> <span m="3705280">need</span>
  <span m="3706880">or</span> <span m="3707040">that</span> <span m="3707190">we</span>
  <span m="3707290">will</span> <span m="3707390">need are</span> <span m="3707860">going</span>
  <span m="3708050">to</span> <span m="3708110">be</span> <span m="3708210">Taylor</span>
  <span m="3708570">series</span> <span m="3708850">expansions.</span> <span m="3709265">And</span>
  <span m="3709680">it''s just,</span> <span m="3710940">again,</span> <span m="3711140">same
  thing.</span> <span m="3711580">You''ve</span> <span m="3711750">seen</span> <span
  m="3712070">them</span> <span m="3712260">in</span> <span m="3712570">the</span>
  <span m="3712700">scalar</span> <span m="3713110">case.</span> <span m="3713510">But</span>
  <span m="3713620">let''s</span> <span m="3713790">just</span> <span m="3713930">make</span>
  <span m="3714110">sure</span> <span m="3714250">it''s</span> <span m="3714420">clear</span>
  <span m="3714920">in the</span> <span m="3716920">gradient</span> <span m="3717420">case.</span></p><p><span
  m="3718420">And</span> <span m="3718920">by the</span> <span m="3719420">way,</span>
  <span m="3720110">If</span> <span m="3720230">you</span> <span m="3720370">really</span>
  <span m="3720620">do</span> <span m="3720750">have</span> <span m="3720880">lots
  of</span> <span m="3721100">questions</span> <span m="3721490">and you</span> <span
  m="3721580">need</span> <span m="3721740">to</span> <span m="3721970">take</span>
  <span m="3722210">the</span> <span m="3722420">graduate</span> <span m="3722920">class
  set</span> <span m="3723842">[INAUDIBLE]</span> <span m="3724303">and I</span> <span
  m="3724764">teach--</span> <span m="3725225">which</span> <span m="3725686">we''re</span>
  <span m="3726150">just teaching</span> <span m="3726240">it this</span> <span m="3726330">semester,</span>
  <span m="3726810">and</span> <span m="3727065">it''s</span> <span m="3727320">offered</span>
  <span m="3727570">every</span> <span m="3727800">other</span> <span m="3727970">year.</span>
  <span m="3728220">But</span> <span m="3728470">it''s on</span> <span m="3728830">design</span>
  <span m="3729232">optimization,</span> <span m="3730440">a</span> <span m="3730540">whole</span>
  <span m="3730690">class on this</span> <span m="3730960">stuff,</span> <span m="3733200">which</span>
  <span m="3733370">is</span> <span m="3733550">fun.</span> <span m="3735152">Taylor</span>
  <span m="3735606">series</span> <span m="3736060">expansion.</span></p><p><span
  m="3739210">Again,</span> <span m="3739610">in</span> <span m="3739700">the</span>
  <span m="3739790">scalar</span> <span m="3740230">case,</span> <span m="3740570">let''s
  just</span> <span m="3740750">do</span> <span m="3741080">what</span> <span m="3741210">we</span>
  <span m="3741300">did</span> <span m="3741440">over</span> <span m="3741620">there</span>
  <span m="3741900">and</span> <span m="3742070">do the</span> <span m="3742290">analogy.</span>
  <span m="3743460">So in the</span> <span m="3743930">scalar</span> <span m="3744460">case,</span>
  <span m="3744930">if</span> <span m="3745040">I</span> <span m="3745170">had</span>
  <span m="3745500">some</span> <span m="3745908">f</span> <span m="3746316">of--</span>
  <span m="3747132">let me</span> <span m="3747540">use</span> <span m="3747640">z.</span>
  <span m="3747950">I probably</span> <span m="3748394">should have used</span> <span
  m="3748838">z over there.</span> <span m="3749726">It''s OK.</span></p><p><span
  m="3751060">If I have</span> <span m="3751230">some</span> <span m="3751460">f of
  z,</span> <span m="3751937">what is that?</span> <span m="3752414">It''s</span>
  <span m="3752891">f.</span> <span m="3753370">If</span> <span m="3753810">I''m</span>
  <span m="3753950">expanding</span> <span m="3754400">about</span> <span m="3754660">the</span>
  <span m="3754740">point</span> <span m="3755140">b0</span> <span m="3756250">plus</span>
  <span m="3757140">the</span> <span m="3757230">first</span> <span m="3757630">derivative</span>
  <span m="3759810">evaluated</span> <span m="3760620">at</span> <span m="3760730">the</span>
  <span m="3760870">point</span> <span m="3761355">b0</span> <span m="3762175">times</span>
  <span m="3762510">z</span> <span m="3762893">minus</span> <span m="3763276">z0</span>
  <span m="3766014">plus the</span> <span m="3766460">second</span> <span m="3766970">derivative</span>
  <span m="3768920">evaluated</span> <span m="3770382">at</span> <span m="3770730">the</span>
  <span m="3770850">point</span> <span m="3772050">z0</span> <span m="3773540">times</span>
  <span m="3775080">z</span> <span m="3775220">minus z0</span> <span m="3779620">squared</span>
  <span m="3780460">plus</span> <span m="3780880">blah, blah, blah.</span> <span m="3781170">Right?</span>
  <span m="3781617">So that''s</span> <span m="3782064">the Taylor</span> <span m="3782511">series</span>
  <span m="3782960">expansion</span> <span m="3783220">that</span> <span m="3783340">you''ve</span>
  <span m="3783610">seen.</span></p><p><span m="3784996">So</span> <span m="3785600">how</span>
  <span m="3785700">does</span> <span m="3785810">it</span> <span m="3785910">look</span>
  <span m="3786160">in</span> <span m="3786460">the</span> <span m="3786900">vector</span>
  <span m="3787240">case?</span> <span m="3795450">So</span> <span m="3795935">when</span>
  <span m="3796420">we</span> <span m="3796520">talk</span> <span m="3796700">about</span>
  <span m="3797050">Taylor</span> <span m="3797290">series</span> <span m="3797660">expansion,</span>
  <span m="3798370">we''re</span> <span m="3798490">talking</span> <span m="3798930">about</span>
  <span m="3800400">expanding</span> <span m="3800795">j</span> <span m="3801930">of</span>
  <span m="3802270">x,</span> <span m="3802730">where</span> <span m="3802910">again</span>
  <span m="3803170">x</span> <span m="3803520">is</span> <span m="3803660">now</span>
  <span m="3804420">this</span> <span m="3804710">n</span> <span m="3804930">dimensional</span>
  <span m="3805380">vector.</span> <span m="3806850">And</span> <span m="3807200">we''re</span>
  <span m="3807260">going</span> <span m="3807400">to</span> <span m="3807840">expand</span>
  <span m="3808430">it</span> <span m="3808560">around</span> <span m="3808970">the</span>
  <span m="3809040">point</span> <span m="3810228">x0</span> <span m="3812220">point
  in</span> <span m="3812410">the</span> <span m="3812490">landscape.</span></p><p><span
  m="3814430">OK.</span> <span m="3814890">So</span> <span m="3816290">what</span>
  <span m="3816450">does</span> <span m="3816520">the</span> <span m="3816600">first
  term</span> <span m="3817110">look</span> <span m="3817280">like?</span> <span m="3820140">Gradient
  of</span> <span m="3820520">j</span> <span m="3822780">evaluated</span> <span m="3823145">at</span>
  <span m="3823510">x0</span> <span m="3826760">multiplied</span> <span m="3827550">by</span>
  <span m="3835240">x</span> <span m="3835500">minus</span> <span m="3835760">x0.</span>
  <span m="3837370">OK.</span> <span m="3837740">So we have to</span> <span m="3837920">think</span>
  <span m="3838080">about</span> <span m="3838280">the</span> <span m="3838400">dimensions.</span>
  <span m="3840890">It always</span> <span m="3841170">helps</span> <span m="3841390">me</span>
  <span m="3841550">think</span> <span m="3841700">about the</span> <span m="3841860">dimensions.</span></p><p><span
  m="3842280">So</span> <span m="3842600">[INAUDIBLE]</span> <span m="3843460">n</span>
  <span m="3843860">by</span> <span m="3844000">1,</span> <span m="3844310">right?</span>
  <span m="3845860">What do</span> <span m="3846010">we</span> <span m="3846080">need</span>
  <span m="3846240">to</span> <span m="3846300">do</span> <span m="3846480">to this</span>
  <span m="3846560">thing?</span> <span m="3847796">Transpose.</span> <span m="3848240">So
  it''s</span> <span m="3848550">in</span> <span m="3848750">a</span> <span m="3848820">product</span>
  <span m="3850530">between</span> <span m="3851000">the</span> <span m="3852930">gradient</span>
  <span m="3853320">evaluated</span> <span m="3853680">at</span> <span m="3854040">x0</span>
  <span m="3856180">and</span> <span m="3856450">in</span> <span m="3856810">the</span>
  <span m="3857930">delta</span> <span m="3858080">x,</span> <span m="3859120">x minus</span>
  <span m="3859280">x0.</span></p><p><span m="3859910">Yup.</span> <span m="3862010">Scalar,</span>
  <span m="3862460">scalar,</span> <span m="3863500">1</span> <span m="3863710">by</span>
  <span m="3864000">n</span> <span m="3864300">times n</span> <span m="3864570">by</span>
  <span m="3864740">1.</span> <span m="3866990">That''s a</span> <span m="3867110">scalar.</span>
  <span m="3868010">OK.</span> <span m="3868350">How</span> <span m="3868440">about</span>
  <span m="3868720">the</span> <span m="3871290">second</span> <span m="3871550">derivative</span>
  <span m="3871970">term?</span> <span m="3872140">What do you</span> <span m="3872340">think</span>
  <span m="3872480">that</span> <span m="3872610">might</span> <span m="3872770">look</span>
  <span m="3872940">like?</span></p><p><span m="3876880">We''ll put</span> <span m="3877260">the</span>
  <span m="3878280">Hessian</span> <span m="3878620">in</span> <span m="3878730">the</span>
  <span m="3878800">middle.</span> <span m="3879270">And it''s</span> <span m="3879500">the</span>
  <span m="3879600">Hessian,</span> <span m="3880080">again,</span> <span m="3880300">evaluated</span>
  <span m="3880960">at--</span> <span m="3882700">let me</span> <span m="3883190">write
  it</span> <span m="3883270">thigs way--</span> <span m="3883800">x0.</span></p><p><span
  m="3888112">AUDIENCE: x</span> <span m="3888599">[INAUDIBLE]</span></p><p><span
  m="3891034">PROFESSOR: OK, good.</span> <span m="3891530">Yeah.</span> <span m="3891840">So</span>
  <span m="3892040">x minus</span> <span m="3892410">x0</span> <span m="3892870">on</span>
  <span m="3893110">that side.</span> <span m="3894140">And then</span> <span m="3894570">x</span>
  <span m="3895440">minus</span> <span m="3895990">x0</span> <span m="3898120">transpose.</span>
  <span m="3899690">And</span> <span m="3899720">again,</span> <span m="3900100">this</span>
  <span m="3900190">is</span> <span m="3900290">an</span> <span m="3901920">n by</span>
  <span m="3902160">n</span> <span m="3902400">and</span> <span m="3902510">n by</span>
  <span m="3902830">1</span> <span m="3903270">[INAUDIBLE]</span> <span m="3905400">a</span>
  <span m="3905480">scalar.</span> <span m="3906890">And</span> <span m="3907070">then</span>
  <span m="3907300">if</span> <span m="3907420">you</span> <span m="3907520">went</span>
  <span m="3907670">higher,</span> <span m="3907940">you</span> <span m="3908250">would</span>
  <span m="3908560">be</span> <span m="3911130">getting</span> <span m="3911590">a</span>
  <span m="3911960">tensor</span> <span m="3912080">for</span> <span m="3912450">the
  third</span> <span m="3912530">derivative.</span></p><p><span m="3914458">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="3916870">PROFESSOR: You</span> <span m="3917210">can.</span>
  <span m="3917500">And</span> <span m="3917790">in</span> <span m="3918000">fact</span>
  <span m="3918240">tensors</span> <span m="3918726">are</span> <span m="3919700">very</span>
  <span m="3919920">popular,</span> <span m="3920360">lots of</span> <span m="3920550">people</span>
  <span m="3920760">working</span> <span m="3921030">on</span> <span m="3921170">them</span>
  <span m="3921240">now.</span> <span m="3923180">I</span> <span m="3923290">don''t--</span>
  <span m="3923680">don''t</span> <span m="3923810">ask</span> <span m="3924040">me</span>
  <span m="3924220">anything</span> <span m="3924705">about them.</span> <span m="3929670">OK.</span>
  <span m="3930622">So</span> <span m="3934430">let</span> <span m="3934550">me</span>
  <span m="3934680">come</span> <span m="3935140">back</span> <span m="3936920">to</span>
  <span m="3937180">this.</span> <span m="3938540">Then</span> <span m="3938700">I</span>
  <span m="3938760">can</span> <span m="3938900">start</span> <span m="3939200">showing</span>
  <span m="3939690">you</span> <span m="3942780">some</span> <span m="3942910">of</span>
  <span m="3942980">the</span> <span m="3943080">optimization</span> <span m="3943380">measures.</span>
  <span m="3943680">I''ll</span> <span m="3943760">show</span> <span m="3943990">you</span>
  <span m="3944120">pictures of</span> <span m="3944230">some of</span> <span m="3944540">them</span>
  <span m="3944690">first.</span> <span m="3944860">And</span> <span m="3945315">then
  we''ll</span> <span m="3948960">look--</span> <span m="3949650">yeah.</span></p><p><span
  m="3950344">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3956766">PROFESSOR: No.</span>
  <span m="3957270">Yeah.</span> <span m="3957630">So I</span> <span m="3958075">could''ve
  written--</span> <span m="3958520">yeah.</span> <span m="3959190">So</span> <span
  m="3959350">that''s</span> <span m="3959660">just</span> <span m="3959830">the</span>
  <span m="3959900">point</span> <span m="3960100">about</span> <span m="3960300">which</span>
  <span m="3960450">we</span> <span m="3960630">were doing, the</span> <span m="3960800">Taylor</span>
  <span m="3961060">series</span> <span m="3961250">expansion.</span> <span m="3961770">And</span>
  <span m="3961850">what</span> <span m="3961990">you''ll</span> <span m="3962620">probably</span>
  <span m="3962850">guess</span> <span m="3963120">is that</span> <span m="3963330">it''s</span>
  <span m="3963460">actually</span> <span m="3963740">going to be</span> <span m="3963900">xq.</span>
  <span m="3965660">We''re</span> <span m="3965810">going</span> <span m="3965940">to</span>
  <span m="3966000">lock</span> <span m="3966300">locally.</span></p><p><span m="3967716">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="3969132">PROFESSOR: Yeah, well,</span> <span m="3969610">whatever.</span>
  <span m="3970020">q minus</span> <span m="3970472">1,</span> <span m="3972280">yeah.</span>
  <span m="3975680">OK.</span> <span m="3975970">So</span> <span m="3979676">we can</span>
  <span m="3980164">close</span> <span m="3980652">this.</span> <span m="3981630">So</span>
  <span m="3981830">actually</span> <span m="3982060">Professor</span> <span m="3982470">Johnson,</span>
  <span m="3982890">who''s</span> <span m="3983060">in</span> <span m="3983130">the</span>
  <span m="3983200">math</span> <span m="3983500">department</span> <span m="3984090">who</span>
  <span m="3985530">teaches</span> <span m="3985920">a</span> <span m="3985990">really</span>
  <span m="3986210">great</span> <span m="3986510">graduate</span> <span m="3986910">class</span>
  <span m="3987400">on</span> <span m="3987600">numerical</span> <span m="3988580">linear</span>
  <span m="3988820">algebra,</span> <span m="3989180">it actually</span> <span m="3989450">covers</span>
  <span m="3989660">lots</span> <span m="3989800">of</span> <span m="3989880">things.</span>
  <span m="3990230">He</span> <span m="3990350">has</span> <span m="3990630">this</span>
  <span m="3991600">NLopt</span> <span m="3992150">package</span> <span m="3992580">where</span>
  <span m="3992710">he''s</span> <span m="3992940">implemented</span> <span m="3993540">lots</span>
  <span m="3993770">of</span> <span m="3994020">optimization</span> <span m="3994720">algorithms.</span></p><p><span
  m="3994990">And</span> <span m="3995090">he</span> <span m="3995250">has</span>
  <span m="3995540">them</span> <span m="3995720">implemented.</span> <span m="3996130">And
  you</span> <span m="3996395">can</span> <span m="3996660">access</span> <span m="3997040">them
  in</span> <span m="3997130">MATLAB</span> <span m="3997690">or</span> <span m="3997760">Python</span>
  <span m="3998370">or</span> <span m="3999090">a</span> <span m="3999500">variety</span>
  <span m="3999910">of ways.</span> <span m="4000320">And</span> <span m="4000730">also</span>
  <span m="4001180">on the</span> <span m="4001560">website,</span> <span m="4001760">he
  was a really</span> <span m="4002010">nice kind of</span> <span m="4002350">description</span>
  <span m="4002990">of</span> <span m="4003270">the</span> <span m="4003710">algorithms
  and</span> <span m="4004150">what</span> <span m="4004390">kind</span> <span m="4004580">of</span>
  <span m="4004650">problems</span> <span m="4005070">they</span> <span m="4005180">work</span>
  <span m="4005440">for</span> <span m="4005770">and</span> <span m="4005870">issues</span>
  <span m="4006080">with</span> <span m="4006310">conversions</span> <span m="4006550">and
  stuff.</span> <span m="4007810">It''s</span> <span m="4008410">really</span> <span
  m="4008610">nice.</span></p><p><span m="4010050">But</span> <span m="4010230">[INAUDIBLE],</span>
  <span m="4010410">you</span> <span m="4010500">were</span> <span m="4010610">asking</span>
  <span m="4010910">about</span> <span m="4011190">some</span> <span m="4011320">of</span>
  <span m="4011380">the</span> <span m="4011450">different</span> <span m="4011740">kinds</span>
  <span m="4012020">of</span> <span m="4012120">methods.</span> <span m="4012710">So</span>
  <span m="4012800">this</span> <span m="4012970">is</span> <span m="4013650">sort</span>
  <span m="4013830">of</span> <span m="4015190">the</span> <span m="4015300">four</span>
  <span m="4015720">categories.</span> <span m="4016450">There</span> <span m="4016580">are</span>
  <span m="4016650">global</span> <span m="4017100">optimization</span> <span m="4017830">methods</span>
  <span m="4017930">that</span> <span m="4018260">sort of</span> <span m="4018590">strive</span>
  <span m="4018960">for</span> <span m="4019090">this,</span> <span m="4019420">being</span>
  <span m="4019580">able</span> <span m="4019780">to</span> <span m="4020590">find</span>
  <span m="4020800">the</span> <span m="4020860">global</span> <span m="4021220">optimum.</span></p><p><span
  m="4022680">There</span> <span m="4022830">are</span> <span m="4022890">local</span>
  <span m="4023240">methods.</span> <span m="4025400">And</span> <span m="4025500">I''ll</span>
  <span m="4026070">show</span> <span m="4026180">you</span> <span m="4026310">how</span>
  <span m="4026400">these</span> <span m="4026610">work.</span> <span m="4027010">And</span>
  <span m="4027310">in</span> <span m="4027450">the</span> <span m="4027520">local</span>
  <span m="4027830">methods,</span> <span m="4028230">there</span> <span m="4028340">can</span>
  <span m="4028520">be</span> <span m="4028640">ones</span> <span m="4028960">that</span>
  <span m="4029060">are</span> <span m="4029110">called</span> <span m="4029330">derivative-free</span>
  <span m="4031440">and</span> <span m="4031900">gradient-based.</span> <span m="4032280">So</span>
  <span m="4032730">these one use</span> <span m="4033180">gradients,</span> <span
  m="4033680">and these</span> <span m="4034084">ones don''t use</span> <span m="4034488">gradients.</span>
  <span m="4035700">And</span> <span m="4036010">then there</span> <span m="4036150">are</span>
  <span m="4036180">a</span> <span m="4036240">heuristic</span> <span m="4036525">methods,</span>
  <span m="4037170">things</span> <span m="4037490">like</span> <span m="4037690">the</span>
  <span m="4037760">genetic</span> <span m="4038110">algorithms</span> <span m="4038660">that</span>
  <span m="4038790">kind</span> <span m="4038930">of</span> <span m="4039020">use</span>
  <span m="4039160">a</span> <span m="4039210">bunch</span> <span m="4039440">of</span>
  <span m="4039570">roles</span> <span m="4040110">and</span> <span m="4040240">some</span>
  <span m="4040370">randomness</span> <span m="4041170">to</span> <span m="4041300">search</span>
  <span m="4041560">the</span> <span m="4041650">design</span> <span m="4041990">space.</span>
  <span m="4044930">Yup.</span></p><p><span m="4045910">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="4049350">PROFESSOR: So</span> <span m="4049480">non-linear</span> <span m="4050250">refers</span>
  <span m="4050590">to the</span> <span m="4050680">fact</span> <span m="4051000">that</span>
  <span m="4051390">j of</span> <span m="4051860">x</span> <span m="4052250">could</span>
  <span m="4052420">be</span> <span m="4052570">a</span> <span m="4052650">general</span>
  <span m="4052910">non-linear</span> <span m="4053300">function</span> <span m="4053880">and</span>
  <span m="4054080">that</span> <span m="4054400">the g</span> <span m="4054830">of
  x</span> <span m="4055290">and</span> <span m="4055750">h of</span> <span m="4056210">x--</span>
  <span m="4057590">yup.</span> <span m="4058050">To</span> <span m="4058230">be</span>
  <span m="4058370">a</span> <span m="4058470">linear</span> <span m="4058860">program,</span>
  <span m="4059610">j</span> <span m="4060050">would</span> <span m="4060190">have</span>
  <span m="4060360">to</span> <span m="4060460">be</span> <span m="4060560">a</span>
  <span m="4060650">linear</span> <span m="4060950">function</span> <span m="4061290">of</span>
  <span m="4061430">the</span> <span m="4061510">x''s.</span> <span m="4062690">So</span>
  <span m="4062880">just</span> <span m="4063360">w1</span> <span m="4063680">times</span>
  <span m="4063935">x1</span> <span m="4064190">plus</span> <span m="4064600">w2.</span>
  <span m="4065340">And</span> <span m="4065590">then</span> <span m="4066040">the</span>
  <span m="4067080">constraints</span> <span m="4067345">would</span> <span m="4067610">also</span>
  <span m="4067840">have</span> <span m="4068010">to</span> <span m="4068080">be</span>
  <span m="4068230">linear</span> <span m="4068550">functions</span> <span m="4068970">of</span>
  <span m="4069336">[INAUDIBLE].</span> <span m="4070070">And</span> <span m="4070230">if</span>
  <span m="4070300">you</span> <span m="4070370">have</span> <span m="4070460">a</span>
  <span m="4070520">linear</span> <span m="4070920">problem,</span> <span m="4071440">then</span>
  <span m="4071820">there''s</span> <span m="4071960">the</span> <span m="4072140">[INAUDIBLE]</span>
  <span m="4072600">simplex,</span> <span m="4073610">different</span> <span m="4073920">from</span>
  <span m="4074050">the</span> <span m="4074190">Nelder-Mead</span> <span m="4074340">simplex,</span>
  <span m="4075060">but</span> <span m="4075280">the</span> <span m="4075700">simplex</span>
  <span m="4076570">method</span> <span m="4076860">that''s</span> <span m="4078060">really</span>
  <span m="4078360">efficient,</span> <span m="4079640">can</span> <span m="4079800">solve</span>
  <span m="4080000">really</span> <span m="4080190">big</span> <span m="4080360">problems,</span>
  <span m="4080890">lots</span> <span m="4081150">of</span> <span m="4081280">theoretical</span>
  <span m="4081670">guarantees.</span></p><p><span m="4085940">All right.</span> <span
  m="4086280">So</span> <span m="4088280">he''s</span> <span m="4088520">the</span>
  <span m="4088610">Nelder-Mead</span> <span m="4088860">simplex.</span> <span m="4089090">So</span>
  <span m="4089280">this</span> <span m="4089560">was</span> <span m="4089640">fminsearch.</span>
  <span m="4090970">Remember,</span> <span m="4091190">that</span> <span m="4091310">was</span>
  <span m="4091440">the</span> <span m="4091520">very</span> <span m="4091740">first</span>
  <span m="4092050">one</span> <span m="4092230">that our</span> <span m="4092725">little</span>
  <span m="4093220">landscape</span> <span m="4094560">was</span> <span m="4096060">working</span>
  <span m="4096390">on.</span> <span m="4096609">So</span> <span m="4096720">this</span>
  <span m="4096870">is</span> <span m="4096970">a</span> <span m="4097050">local</span>
  <span m="4097620">method</span> <span m="4098600">that''s</span> <span m="4098819">derivative</span>
  <span m="4099229">free.</span> <span m="4100160">So</span> <span m="4100300">it''s
  not</span> <span m="4100520">using</span> <span m="4100710">any</span> <span m="4100880">gradient.</span></p><p><span
  m="4102229">And</span> <span m="4103700">how</span> <span m="4103830">does</span>
  <span m="4103970">it</span> <span m="4104069">work?</span> <span m="4104410">So</span>
  <span m="4104840">a</span> <span m="4105149">simplex is a</span> <span m="4105649">special</span>
  <span m="4106389">polytope</span> <span m="4106649">of</span> <span m="4106790">N</span>
  <span m="4106950">plus</span> <span m="4107220">1</span> <span m="4107399">vertices</span>
  <span m="4108060">in</span> <span m="4108359">N</span> <span m="4108439">dimensions.</span>
  <span m="4110279">For</span> <span m="4110399">me</span> <span m="4110609">it''s
  easiest</span> <span m="4111010">to</span> <span m="4111100">think</span> <span
  m="4111270">about</span> <span m="4111649">in 2D</span> <span m="4112140">[INAUDIBLE]</span>
  <span m="4112470">a</span> <span m="4112590">triangle.</span> <span m="4112939">So</span>
  <span m="4113399">simplex</span> <span m="4113710">is</span> <span m="4113970">a</span>
  <span m="4114060">triangle</span> <span m="4114350">in</span> <span m="4114540">2D.</span>
  <span m="4115510">And</span> <span m="4115819">here''s</span> <span m="4116020">how</span>
  <span m="4116420">this</span> <span m="4117729">Nelder-Mead</span> <span m="4118370">simplex</span>
  <span m="4118870">method</span> <span m="4119189">works.</span></p><p><span m="4120590">So</span>
  <span m="4120649">you</span> <span m="4120840">take</span> <span m="4121109">your</span>
  <span m="4121210">initial</span> <span m="4121520">guess</span> <span m="4121850">that,</span>
  <span m="4122180">again,</span> <span m="4122420">we</span> <span m="4122540">have</span>
  <span m="4122680">to</span> <span m="4122830">supply.</span> <span m="4123660">This</span>
  <span m="4123779">is</span> <span m="4123899">the</span> <span m="4123990">initial</span>
  <span m="4124279">point</span> <span m="4124609">in</span> <span m="4124750">the</span>
  <span m="4124830">landscape.</span> <span m="4125939">And you</span> <span m="4126189">form</span>
  <span m="4126410">an</span> <span m="4126470">initial</span> <span m="4126830">simplex.</span>
  <span m="4127910">So with</span> <span m="4128069">our 2D</span> <span m="4128450">landscape,</span>
  <span m="4129069">we''re</span> <span m="4129170">going</span> <span m="4129180">to</span>
  <span m="4129319">put</span> <span m="4129450">down</span> <span m="4129620">a</span>
  <span m="4129670">triangle,</span> <span m="4131069">initial</span> <span m="4131319">triangle.</span></p><p><span
  m="4132229">And</span> <span m="4132390">we''re</span> <span m="4132490">going</span>
  <span m="4132770">to</span> <span m="4132910">evaluate.</span> <span m="4133230">And</span>
  <span m="4133550">remember,</span> <span m="4133689">I''m</span> <span m="4133930">talking</span>
  <span m="4134060">about</span> <span m="4134340">unconstrained</span> <span m="4134910">optimization</span>
  <span m="4135185">here.</span> <span m="4135460">So there</span> <span m="4135744">are
  no</span> <span m="4136029">constraints.</span> <span m="4136749">So</span> <span
  m="4137109">you</span> <span m="4137350">evaluate</span> <span m="4138029">j,</span>
  <span m="4138769">the</span> <span m="4139140">objective,</span> <span m="4140450">at</span>
  <span m="4140580">each</span> <span m="4140830">one</span> <span m="4141340">of</span>
  <span m="4141640">the</span> <span m="4142510">points</span> <span m="4142939">in</span>
  <span m="4143010">the</span> <span m="4143100">triangle,</span> <span m="4143740">three.</span>
  <span m="4144100">So</span> <span m="4144290">in</span> <span m="4144399">two</span>
  <span m="4144550">dimensions,</span> <span m="4145000">we</span> <span m="4145069">have</span>
  <span m="4145180">three</span> <span m="4145410">points.</span></p><p><span m="4148720">So</span>
  <span m="4148729">that''s</span> <span m="4148939">what</span> <span m="4149170">can</span>
  <span m="4149500">keep the</span> <span m="4149569">function</span> <span m="4149960">value.</span>
  <span m="4150050">The</span> <span m="4150240">function</span> <span m="4150500">value
  here</span> <span m="4150910">is j.</span> <span m="4152569">[INAUDIBLE]</span>
  <span m="4152700">the</span> <span m="4152760">triangle--</span> <span m="4153330">the</span>
  <span m="4153399">triangle</span> <span m="4153700">can</span> <span m="4153810">be--</span></p><p><span
  m="4154090">AUDIENCE: [INAUDIBLE]</span></p><p><span m="4155710">PROFESSOR: Yeah.</span>
  <span m="4156130">I</span> <span m="4156170">mean,</span> <span m="4156560">yes.</span>
  <span m="4157580">In</span> <span m="4157689">terms</span> <span m="4157890">of</span>
  <span m="4157979">size?</span> <span m="4158680">You''ve</span> <span m="4158800">got</span>
  <span m="4158970">your</span> <span m="4159060">initial</span> <span m="4159350">point.</span>
  <span m="4159727">And you''re going to</span> <span m="4160104">put two</span> <span
  m="4160481">other down here.</span> <span m="4160859">There</span> <span m="4160979">would</span>
  <span m="4161100">be--</span> <span m="4162370">they''re</span> <span m="4162630">close</span>
  <span m="4162890">by</span> <span m="4163120">though.</span> <span m="4163559">It''s
  local.</span> <span m="4164439">So</span> <span m="4164600">they''re</span> <span
  m="4164920">close</span> <span m="4165240">by.</span> <span m="4165439">Maybe</span>
  <span m="4165689">not</span> <span m="4166899">super</span> <span m="4167109">close,</span>
  <span m="4167439">but</span> <span m="4167600">they''re</span> <span m="4167819">close
  by.</span></p><p><span m="4170380">And</span> <span m="4170479">you''ll</span> <span
  m="4170580">see</span> <span m="4170740">that''s</span> <span m="4170920">going</span>
  <span m="4171040">to</span> <span m="4171100">change.</span> <span m="4171460">So
  it doesn''t</span> <span m="4171830">actually</span> <span m="4172050">matter</span>
  <span m="4172300">too</span> <span m="4172460">much</span> <span m="4172770">what
  we start with.</span> <span m="4174550">We''re</span> <span m="4174680">going to</span>
  <span m="4174800">order</span> <span m="4175170">the</span> <span m="4175260">vertices</span>
  <span m="4176319">according</span> <span m="4176680">to</span> <span m="4176779">function</span>
  <span m="4177160">values</span> <span m="4179399">and</span> <span m="4179540">discard
  the</span> <span m="4179910">worse</span> <span m="4180080">one.</span> <span m="4180260">So
  if we''re</span> <span m="4180399">trying</span> <span m="4180590">to</span> <span
  m="4180660">minimize,</span> <span m="4182310">we</span> <span m="4182460">have</span>
  <span m="4183710">the</span> <span m="4183979">highest</span> <span m="4184390">value,</span>
  <span m="4184920">the</span> <span m="4185029">lowest</span> <span m="4185359">value,</span>
  <span m="4185710">and</span> <span m="4185830">the</span> <span m="4185899">middle</span>
  <span m="4186189">one.</span></p><p><span m="4187170">If</span> <span m="4187319">we''re</span>
  <span m="4187430">trying</span> <span m="4187689">to</span> <span m="4187760">minimize,</span>
  <span m="4188450">we</span> <span m="4188550">would</span> <span m="4188700">throw</span>
  <span m="4189090">out</span> <span m="4189510">the</span> <span m="4189790">one</span>
  <span m="4190020">with</span> <span m="4190090">the</span> <span m="4190160">highest</span>
  <span m="4190460">value,</span> <span m="4191890">right?</span> <span m="4193899">So</span>
  <span m="4194010">we''re</span> <span m="4194069">going</span> <span m="4194189">to</span>
  <span m="4194250">throw</span> <span m="4194540">away,</span> <span m="4195220">in
  this</span> <span m="4195485">case,</span> <span m="4195750">x</span> <span m="4196440">high.</span>
  <span m="4196870">Because</span> <span m="4197180">it''s</span> <span m="4197260">got
  the</span> <span m="4197360">highest</span> <span m="4197830">value,</span> <span
  m="4198140">and we''re</span> <span m="4198280">trying</span> <span m="4198430">to</span>
  <span m="4198490">minimize.</span></p><p><span m="4199520">And we''re</span> <span
  m="4199670">going</span> <span m="4199790">to</span> <span m="4199850">generate</span>
  <span m="4200260">a</span> <span m="4200310">new</span> <span m="4200550">point</span>
  <span m="4200980">by</span> <span m="4201100">what''s</span> <span m="4201350">called</span>
  <span m="4201660">reflection,</span> <span m="4202940">which</span> <span m="4203180">means</span>
  <span m="4203430">that</span> <span m="4203540">I''m</span> <span m="4203690">going</span>
  <span m="4204050">to</span> <span m="4205170">come</span> <span m="4205340">across</span>
  <span m="4205620">this</span> <span m="4205820">line</span> <span m="4206120">of</span>
  <span m="4206210">the</span> <span m="4206300">remaining</span> <span m="4206720">two
  and</span> <span m="4207100">reflect</span> <span m="4207460">the</span> <span m="4207540">triangle</span>
  <span m="4208020">over</span> <span m="4208400">and</span> <span m="4208800">generate</span>
  <span m="4209130">a</span> <span m="4209180">new</span> <span m="4209430">point</span>
  <span m="4209850">that''s</span> <span m="4210090">kind</span> <span m="4210250">of</span>
  <span m="4210320">on</span> <span m="4210410">the</span> <span m="4210480">opposite</span>
  <span m="4210940">side</span> <span m="4211150">of</span> <span m="4211210">the</span>
  <span m="4211270">simplex.</span> <span m="4212910">And</span> <span m="4213130">at</span>
  <span m="4213230">the</span> <span m="4213300">same</span> <span m="4213580">time,</span>
  <span m="4215480">I''m</span> <span m="4215600">also</span> <span m="4216150">going</span>
  <span m="4216700">to--</span> <span m="4219170">I''m</span> <span m="4219460">going
  to</span> <span m="4219600">[INAUDIBLE]</span> <span m="4219860">a new</span> <span
  m="4220040">point</span> <span m="4220250">over</span> <span m="4220370">here.</span>
  <span m="4220530">This</span> <span m="4221120">is</span> <span m="4221210">the</span>
  <span m="4221280">xr.</span></p><p><span m="4222670">I''m</span> <span m="4222740">going</span>
  <span m="4222860">to</span> <span m="4222950">run</span> <span m="4223270">the</span>
  <span m="4223350">function</span> <span m="4223810">there</span> <span m="4224090">and</span>
  <span m="4224280">see</span> <span m="4226150">whether</span> <span m="4226330">things</span>
  <span m="4226660">got</span> <span m="4226940">better</span> <span m="4227310">or</span>
  <span m="4227480">not.</span> <span m="4228910">So we''re</span> <span m="4229280">trying</span>
  <span m="4229410">to</span> <span m="4229490">minimize.</span> <span m="4229990">We''re</span>
  <span m="4230070">going</span> <span m="4230310">downhill.</span> <span m="4231090">Run</span>
  <span m="4231340">the</span> <span m="4231410">function</span> <span m="4231800">here</span>
  <span m="4232080">and</span> <span m="4232250">see</span> <span m="4232520">whether</span>
  <span m="4233520">this</span> <span m="4233690">is</span> <span m="4233800">actually</span>
  <span m="4234100">a</span> <span m="4234170">better</span> <span m="4234780">function</span>
  <span m="4235360">value.</span></p><p><span m="4236140">And</span> <span m="4236260">then</span>
  <span m="4236380">I''m</span> <span m="4236490">also</span> <span m="4236720">going</span>
  <span m="4236840">to</span> <span m="4236920">decide,</span> <span m="4237890">depending</span>
  <span m="4238290">on</span> <span m="4238440">how</span> <span m="4238750">steeply</span>
  <span m="4239005">down</span> <span m="4239260">the</span> <span m="4239620">hill</span>
  <span m="4239860">I''m</span> <span m="4240010">going,</span> <span m="4241210">whether</span>
  <span m="4241400">I</span> <span m="4241480">want</span> <span m="4241650">to</span>
  <span m="4241710">change</span> <span m="4242360">the</span> <span m="4242440">size</span>
  <span m="4242850">of</span> <span m="4242960">my</span> <span m="4243450">simplex.</span>
  <span m="4244910">And</span> <span m="4245120">if</span> <span m="4245200">things</span>
  <span m="4245420">are</span> <span m="4245460">going</span> <span m="4245740">really</span>
  <span m="4245980">well</span> <span m="4246320">and</span> <span m="4246440">I''m</span>
  <span m="4246580">generating</span> <span m="4247020">points</span> <span m="4247590">and</span>
  <span m="4247690">I''m</span> <span m="4247800">really</span> <span m="4248020">going</span>
  <span m="4248360">downhill</span> <span m="4248900">quickly,</span> <span m="4249550">I''m</span>
  <span m="4249620">going</span> <span m="4249740">to</span> <span m="4249800">make</span>
  <span m="4249970">the</span> <span m="4250040">simplex</span> <span m="4250490">bigger</span>
  <span m="4250790">and</span> <span m="4250920">bigger,</span> <span m="4251230">so</span>
  <span m="4251300">that</span> <span m="4251420">I</span> <span m="4251470">can</span>
  <span m="4251610">go</span> <span m="4251740">down hill</span> <span m="4252230">faster</span>
  <span m="4252570">and</span> <span m="4252690">faster.</span> <span m="4253730">But</span>
  <span m="4253920">if</span> <span m="4254230">this</span> <span m="4254510">guy''s</span>
  <span m="4254940">not</span> <span m="4255170">really</span> <span m="4255520">so</span>
  <span m="4255760">good,</span> <span m="4256060">then</span> <span m="4256190">I</span>
  <span m="4256250">might</span> <span m="4256630">shrink</span> <span m="4257040">the</span>
  <span m="4257110">simplex</span> <span m="4257630">so</span> <span m="4257720">that</span>
  <span m="4257850">I</span> <span m="4257990">look</span> <span m="4258420">more</span>
  <span m="4258690">locally.</span></p><p><span m="4259720">So</span> <span m="4259830">maybe</span>
  <span m="4260070">you</span> <span m="4260640">can</span> <span m="4260970">kind</span>
  <span m="4261170">of</span> <span m="4261460">visualize</span> <span m="4262170">that</span>
  <span m="4262630">what</span> <span m="4262830">this</span> <span m="4263000">optimization</span>
  <span m="4263580">algorithm</span> <span m="4263910">looks</span> <span m="4264130">like</span>
  <span m="4264350">is a</span> <span m="4264420">bunch</span> <span m="4264610">of</span>
  <span m="4264680">triangles</span> <span m="4265480">that</span> <span m="4265860">keep</span>
  <span m="4266230">flipping</span> <span m="4266660">over</span> <span m="4268220">just</span>
  <span m="4268400">by</span> <span m="4268690">measuring,</span> <span m="4269290">by</span>
  <span m="4269410">ordering</span> <span m="4269910">the</span> <span m="4270910">performance</span>
  <span m="4271410">of</span> <span m="4271480">the</span> <span m="4271550">vertices,</span>
  <span m="4272250">throwing</span> <span m="4272570">out</span> <span m="4272680">the</span>
  <span m="4272790">old</span> <span m="4272980">one,</span> <span m="4273260">generating</span>
  <span m="4273660">a</span> <span m="4273700">new</span> <span m="4273860">one</span>
  <span m="4274000">on</span> <span m="4274110">the</span> <span m="4274220">other</span>
  <span m="4274380">side,</span> <span m="4275190">walking</span> <span m="4275560">kind</span>
  <span m="4275700">of</span> <span m="4275770">through</span> <span m="4275890">the</span>
  <span m="4275980">design</span> <span m="4276370">space.</span> <span m="4276820">And</span>
  <span m="4276940">then</span> <span m="4277100">the</span> <span m="4277190">triangles</span>
  <span m="4277640">are</span> <span m="4278000">growing</span> <span m="4278540">or</span>
  <span m="4278620">shrinking</span> <span m="4279140">depending</span> <span m="4279600">on</span>
  <span m="4280520">how</span> <span m="4280740">well</span> <span m="4280930">things</span>
  <span m="4281940">are</span> <span m="4281970">going.</span> <span m="4283330">So</span>
  <span m="4283420">there''s</span> <span m="4283670">no</span> <span m="4283770">gradient.</span>
  <span m="4284240">All it is is</span> <span m="4284600">just</span> <span m="4284790">a</span>
  <span m="4284960">sampling</span> <span m="4285170">and</span> <span m="4285950">an</span>
  <span m="4286050">ordering.</span></p><p><span m="4286930">There</span> <span m="4287100">are</span>
  <span m="4287180">some</span> <span m="4287960">convergence</span> <span m="4288490">issues</span>
  <span m="4289920">in</span> <span m="4290120">this.</span> <span m="4290420">But</span>
  <span m="4290950">actually,</span> <span m="4291270">it''s</span> <span m="4291640">kind</span>
  <span m="4291810">of</span> <span m="4291900">a</span> <span m="4292050">simple</span>
  <span m="4292460">algorithm.</span> <span m="4293010">And</span> <span m="4293540">it''s</span>
  <span m="4293760">pretty</span> <span m="4293990">robust.</span> <span m="4298200">The</span>
  <span m="4298300">function doesn''t</span> <span m="4298750">have</span> <span m="4298870">to</span>
  <span m="4298940">be</span> <span m="4299010">differentiable,</span> <span m="4299720">right?</span>
  <span m="4299910">j of</span> <span m="4300170">x</span> <span m="4300410">doesn''t</span>
  <span m="4300620">have</span> <span m="4300760">to</span> <span m="4300860">be</span>
  <span m="4300990">smooth</span> <span m="4302380">as</span> <span m="4302520">long</span>
  <span m="4302830">as</span> <span m="4304150">a</span> <span m="4304260">better</span>
  <span m="4304530">point</span> <span m="4304960">has</span> <span m="4305170">a</span>
  <span m="4305990">lower</span> <span m="4306300">value</span> <span m="4306610">of</span>
  <span m="4306700">j</span> <span m="4306975">of x</span> <span m="4307250">than</span>
  <span m="4307870">another</span> <span m="4308150">one.</span> <span m="4309460">That''s</span>
  <span m="4310010">OK,</span> <span m="4310550">right?</span></p><p><span m="4313686">So</span>
  <span m="4314140">when</span> <span m="4314350">I</span> <span m="4314910">ran</span>
  <span m="4317550">fminsearch,</span> <span m="4318960">way</span> <span m="4319100">back</span>
  <span m="4319370">up</span> <span m="4319520">if</span> <span m="4319630">I</span>
  <span m="4319720">pull</span> <span m="4319920">it</span> <span m="4320020">up.</span>
  <span m="4320280">So you</span> <span m="4320390">can</span> <span m="4320550">see</span>
  <span m="4320750">here</span> <span m="4321070">in</span> <span m="4321170">the</span>
  <span m="4321230">MATLAB</span> <span m="4321430">output</span> <span m="4322686">it
  was</span> <span m="4326390">[INAUDIBLE]</span> <span m="4327320">things.</span>
  <span m="4328025">So</span> <span m="4328280">that</span> <span m="4328670">was</span>
  <span m="4328950">telling</span> <span m="4329330">me</span> <span m="4329800">what</span>
  <span m="4330050">was</span> <span m="4330190">going</span> <span m="4330500">on.</span>
  <span m="4331050">Every</span> <span m="4331260">time</span> <span m="4331430">it</span>
  <span m="4331520">was</span> <span m="4331700">evaluating</span> <span m="4332280">new</span>
  <span m="4332420">points,</span> <span m="4333300">so two new</span> <span m="4333740">points</span>
  <span m="4334040">each</span> <span m="4334190">time,</span> <span m="4335120">that
  was</span> <span m="4335580">the</span> <span m="4335650">simplex</span> <span m="4336100">expanding,</span>
  <span m="4336700">reflecting,</span> <span m="4337400">contracting,</span> <span
  m="4338080">knew</span> <span m="4338170">what</span> <span m="4338340">was</span>
  <span m="4338450">going</span> <span m="4338720">on</span> <span m="4339205">with
  points.</span></p><p><span m="4342600">OK.</span> <span m="4342890">So</span> <span
  m="4343280">that''s</span> <span m="4343480">a</span> <span m="4343530">derivative-free</span>
  <span m="4344330">method.</span> <span m="4345390">It uses</span> <span m="4345630">a</span>
  <span m="4345690">little</span> <span m="4345880">bit</span> <span m="4345980">of</span>
  <span m="4346060">sampling,</span> <span m="4346640">but</span> <span m="4346690">it</span>
  <span m="4346790">is</span> <span m="4347010">local.</span> <span m="4348680">And</span>
  <span m="4349150">that''s</span> <span m="4349360">fminsearch</span> <span m="4349985">in</span>
  <span m="4350370">MATLAB.</span></p><p><span m="4354260">This</span> <span m="4354470">one</span>
  <span m="4354670">is</span> <span m="4356100">sort</span> <span m="4356280">of</span>
  <span m="4356520">the</span> <span m="4356620">same--</span> <span m="4357560">I
  don''t know</span> <span m="4357670">it sort of</span> <span m="4357990">has</span>
  <span m="4358150">the</span> <span m="4358220">same</span> <span m="4358460">feeling.</span>
  <span m="4359440">But</span> <span m="4359590">it''s</span> <span m="4359790">a</span>
  <span m="4359840">global</span> <span m="4360230">optimization</span> <span m="4360880">method.</span>
  <span m="4361820">It''s</span> <span m="4362030">called</span> <span m="4362280">DIRECT.</span>
  <span m="4362770">And</span> <span m="4363000">DIRECT</span> <span m="4363260">stands</span>
  <span m="4363600">for</span> <span m="4363720">Dividing</span> <span m="4364210">Rectangles.</span>
  <span m="4365560">And</span> <span m="4366190">basically</span> <span m="4366590">what</span>
  <span m="4366730">it</span> <span m="4366820">does</span> <span m="4367070">is</span>
  <span m="4367170">it</span> <span m="4367320">divides</span> <span m="4367810">the</span>
  <span m="4367900">domain</span> <span m="4368240">into</span> <span m="4368460">these</span>
  <span m="4369490">rectangles</span> <span m="4370230">in</span> <span m="4370340">2D.</span>
  <span m="4370730">You''ll</span> <span m="4370900">have</span> <span m="4371090">rectangles</span>
  <span m="4371620">in</span> <span m="4371690">multiple</span> <span m="4372100">D.</span></p><p><span
  m="4372980">And</span> <span m="4373400">it</span> <span m="4373620">basically</span>
  <span m="4374050">figures</span> <span m="4374420">out</span> <span m="4374650">where</span>
  <span m="4374830">to</span> <span m="4374940">look.</span> <span m="4376330">So</span>
  <span m="4376680">if</span> <span m="4377020">this</span> <span m="4377120">one</span>
  <span m="4377370">is</span> <span m="4377470">interesting,</span> <span m="4378040">then</span>
  <span m="4378170">it</span> <span m="4378300">would</span> <span m="4378590">divide</span>
  <span m="4378980">that</span> <span m="4379190">more.</span> <span m="4379570">And</span>
  <span m="4379680">then</span> <span m="4379810">this</span> <span m="4379900">guy
  is</span> <span m="4380340">interesting,</span> <span m="4380770">so then</span>
  <span m="4381140">divide</span> <span m="4381430">that</span> <span m="4381580">one</span>
  <span m="4381740">more.</span> <span m="4381980">And</span> <span m="4382070">that</span>
  <span m="4382200">one''s</span> <span m="4382500">interesting</span> <span m="4382890">and</span>
  <span m="4382990">keep</span> <span m="4383190">dividing</span> <span m="4383570">and</span>
  <span m="4383670">dividing</span> <span m="4384050">and</span> <span m="4384150">dividing</span>
  <span m="4384570">more.</span></p><p><span m="4385280">And</span> <span m="4385410">it''s</span>
  <span m="4385560">got</span> <span m="4385850">all</span> <span m="4386130">different</span>
  <span m="4386510">roles</span> <span m="4387600">for</span> <span m="4387790">figuring</span>
  <span m="4388260">out</span> <span m="4388500">which</span> <span m="4388670">ones</span>
  <span m="4388940">to</span> <span m="4389040">divide</span> <span m="4389500">and</span>
  <span m="4389610">which</span> <span m="4389800">ones</span> <span m="4390470">not</span>
  <span m="4390720">to</span> <span m="4390820">divide</span> <span m="4391170">and</span>
  <span m="4391310">how</span> <span m="4393100">to</span> <span m="4395110">progress.</span>
  <span m="4396230">So</span> <span m="4396720">this</span> <span m="4396860">is</span>
  <span m="4396950">one</span> <span m="4397090">that</span> <span m="4397210">tries</span>
  <span m="4397440">to</span> <span m="4397520">go</span> <span m="4397680">at</span>
  <span m="4397740">global</span> <span m="4398100">optimization.</span> <span m="4399330">Problem</span>
  <span m="4399580">with</span> <span m="4399710">this</span> <span m="4399890">one</span>
  <span m="4400120">is</span> <span m="4400270">that</span> <span m="4400420">it</span>
  <span m="4400510">just</span> <span m="4400770">really</span> <span m="4400970">keeps</span>
  <span m="4401230">running</span> <span m="4401540">and</span> <span m="4401630">running</span>
  <span m="4401860">and</span> <span m="4401960">running</span> <span m="4402220">and</span>
  <span m="4402320">running</span> <span m="4402890">and</span> <span m="4403010">running.</span>
  <span m="4405200">So</span> <span m="4405330">we''ve</span> <span m="4405510">used</span>
  <span m="4405660">this a</span> <span m="4405820">couple</span> <span m="4406100">times.</span>
  <span m="4406995">But</span> <span m="4407460">it tends</span> <span m="4407750">to</span>
  <span m="4407810">just</span> <span m="4407980">take</span> <span m="4408220">so</span>
  <span m="4408320">long</span> <span m="4408560">to</span> <span m="4408670">run</span>
  <span m="4408890">that</span> <span m="4409360">it''s</span> <span m="4409590">not</span>
  <span m="4410160">particularly</span> <span m="4410460">useful.</span></p><p><span
  m="4413680">OK.</span> <span m="4413780">So</span> <span m="4414220">let''s</span>
  <span m="4414655">see</span> <span m="4415090">what</span> <span m="4415330">time</span>
  <span m="4415765">we have</span> <span m="4416200">left.</span> <span m="4416652">We
  have about 10</span> <span m="4417104">minutes.</span> <span m="4418008">So</span>
  <span m="4418460">let''s</span> <span m="4419200">at least</span> <span m="4419450">start</span>
  <span m="4419950">talking</span> <span m="4420330">about</span> <span m="4421170">the</span>
  <span m="4421270">gradient-based</span> <span m="4422790">method.</span> <span m="4424470">So</span>
  <span m="4424890">again,</span> <span m="4425210">this</span> <span m="4425380">is</span>
  <span m="4425490">what</span> <span m="4425720">we''ve</span> <span m="4425890">been</span>
  <span m="4426090">talking</span> <span m="4426440">about</span> <span m="4426850">starting</span>
  <span m="4427760">with</span> <span m="4427940">an</span> <span m="4428020">initial</span>
  <span m="4428710">guess,</span> <span m="4429170">x0.</span></p><p><span m="4432380">Then</span>
  <span m="4432510">we''ve</span> <span m="4432620">going</span> <span m="4433010">to</span>
  <span m="4433690">compute</span> <span m="4434140">two</span> <span m="4434290">things,</span>
  <span m="4434780">the</span> <span m="4434850">search</span> <span m="4435190">direction,</span>
  <span m="4435700">the</span> <span m="4435890">Sq,</span> <span m="4436410">and</span>
  <span m="4436590">then</span> <span m="4436700">the</span> <span m="4436820">alpha--</span>
  <span m="4437105">this</span> <span m="4437390">should</span> <span m="4437600">have</span>
  <span m="4437700">a q on</span> <span m="4438150">it--</span> <span m="4438990">how</span>
  <span m="4439120">far</span> <span m="4439420">we</span> <span m="4439530">step</span>
  <span m="4439750">in</span> <span m="4439820">that</span> <span m="4439950">direction.</span>
  <span m="4441130">And</span> <span m="4441370">with</span> <span m="4441490">a</span>
  <span m="4441530">gradient-based</span> <span m="4442220">method,</span> <span m="4443030">we''re</span>
  <span m="4443170">going</span> <span m="4443290">to</span> <span m="4443400">use</span>
  <span m="4444150">gradient</span> <span m="4444520">of</span> <span m="4444610">j</span>
  <span m="4446190">to</span> <span m="4446290">compute</span> <span m="4446600">this</span>
  <span m="4447060">Sq.</span> <span m="4448500">OK.</span></p><p><span m="4449520">And
  we''re</span> <span m="4449550">going</span> <span m="4449740">to</span> <span m="4449840">check</span>
  <span m="4450070">for</span> <span m="4450200">convergence.</span> <span m="4450940">We''ll</span>
  <span m="4451040">talk</span> <span m="4451220">about</span> <span m="4451420">what</span>
  <span m="4451540">that</span> <span m="4451700">might</span> <span m="4451870">mean</span>
  <span m="4452270">and</span> <span m="4452410">just keep</span> <span m="4452720">going</span>
  <span m="4453020">around</span> <span m="4453220">this</span> <span m="4453310">slope</span>
  <span m="4453700">until</span> <span m="4454490">we''re</span> <span m="4454640">done.</span>
  <span m="4456050">So</span> <span m="4457720">these</span> <span m="4457890">are</span>
  <span m="4457930">the</span> <span m="4458000">methods</span> <span m="4458360">that</span>
  <span m="4458520">we''ll</span> <span m="4458620">talk</span> <span m="4458870">about.</span>
  <span m="4459050">I</span> <span m="4459100">think</span> <span m="4459270">maybe</span>
  <span m="4459470">we''ll</span> <span m="4459680">just</span> <span m="4459930">talk</span>
  <span m="4460080">about</span> <span m="4460540">steepest</span> <span m="4460720">descent</span>
  <span m="4461080">right</span> <span m="4461260">now.</span> <span m="4461570">And</span>
  <span m="4461680">then</span> <span m="4461820">we</span> <span m="4461940">can</span>
  <span m="4462140">talk</span> <span m="4462290">about</span> <span m="4462500">the</span>
  <span m="4462620">other</span> <span m="4462780">ones</span> <span m="4463120">on</span>
  <span m="4463830">Monday.</span></p><p><span m="4464800">But</span> <span m="4465150">steepest</span>
  <span m="4465590">descent is</span> <span m="4466020">conjugate</span> <span m="4466430">gradient</span>
  <span m="4466840">of</span> <span m="4467240">first-order</span> <span m="4467440">method.</span>
  <span m="4468726">Newton</span> <span m="4469170">method,</span> <span m="4469520">which</span>
  <span m="4469750">I</span> <span m="4469790">think</span> <span m="4470010">you''ve</span>
  <span m="4470180">seen</span> <span m="4471170">maybe</span> <span m="4471450">in</span>
  <span m="4471890">the</span> <span m="4472330">scalar</span> <span m="4472520">case.</span>
  <span m="4472750">Have</span> <span m="4473120">you seen</span> <span m="4473490">the
  Newton</span> <span m="4473860">method</span> <span m="4474230">for</span> <span
  m="4474330">root finding</span> <span m="4475730">in the</span> <span m="4475840">scalar</span>
  <span m="4476120">case?</span></p><p><span m="4477510">You''ve</span> <span m="4477970">seen
  Newton</span> <span m="4478430">[INAUDIBLE]</span> <span m="4478890">in</span> <span
  m="4479350">[INAUDIBLE],</span> <span m="4480850">a</span> <span m="4480890">little</span>
  <span m="4481160">bit</span> <span m="4481310">different.</span> <span m="4482150">We''ll</span>
  <span m="4482460">see how Newton</span> <span m="4482930">method</span> <span m="4483310">looks</span>
  <span m="4483640">in</span> <span m="4483740">the</span> <span m="4484320">[INAUDIBLE]</span>
  <span m="4484700">case.</span> <span m="4485410">And</span> <span m="4485540">then</span>
  <span m="4485640">there</span> <span m="4485790">are</span> <span m="4485830">things</span>
  <span m="4486090">called</span> <span m="4486280">quasi-Newton</span> <span m="4486740">methods</span>
  <span m="4487120">that</span> <span m="4487280">kind</span> <span m="4487400">of</span>
  <span m="4487570">sit in</span> <span m="4487900">the</span> <span m="4487980">middle</span>
  <span m="4490760">between</span> <span m="4491050">the</span> <span m="4491130">two.</span></p><p><span
  m="4491970">So</span> <span m="4492370">let''s</span> <span m="4492550">look</span>
  <span m="4492700">at</span> <span m="4492940">steepest</span> <span m="4493020">descent.</span>
  <span m="4493500">It''s</span> <span m="4493590">the</span> <span m="4493670">simplest</span>
  <span m="4494190">thing</span> <span m="4494360">you</span> <span m="4494460">could</span>
  <span m="4494600">possibly</span> <span m="4495070">do,</span> <span m="4496340">possibly</span>
  <span m="4496750">think</span> <span m="4496910">about</span> <span m="4497160">doing.</span>
  <span m="4497860">And it</span> <span m="4498120">just</span> <span m="4498300">says</span>
  <span m="4499750">fix</span> <span m="4500190">this</span> <span m="4500460">search</span>
  <span m="4500760">direction</span> <span m="4501330">on</span> <span m="4501480">iteration</span>
  <span m="4502260">q</span> <span m="4503500">to</span> <span m="4503630">be</span>
  <span m="4503790">negative</span> <span m="4504940">the</span> <span m="4505040">gradient</span>
  <span m="4505420">of</span> <span m="4505510">j</span> <span m="4507980">evaluated</span>
  <span m="4508570">at</span> <span m="4509310">the</span> <span m="4509410">current</span>
  <span m="4509820">design</span> <span m="4510160">iterate,</span> <span m="4510760">Sq</span>
  <span m="4511190">minus</span> <span m="4511450">1.</span> <span m="4512240">So</span>
  <span m="4512260">why</span> <span m="4512590">would</span> <span m="4512730">you</span>
  <span m="4512790">pick</span> <span m="4512980">that</span> <span m="4513130">search</span>
  <span m="4513350">direction?</span></p><p><span m="4517470">It''s</span> <span m="4517700">the</span>
  <span m="4517790">steepest</span> <span m="4518220">descent,</span> <span m="4518590">yeah.</span>
  <span m="4519350">So</span> <span m="4519660">we</span> <span m="4519760">know</span>
  <span m="4519930">that</span> <span m="4520060">the</span> <span m="4520140">gradient</span>
  <span m="4520600">of</span> <span m="4520670">j</span> <span m="4521410">points</span>
  <span m="4521710">in</span> <span m="4521770">the</span> <span m="4521840">direction</span>
  <span m="4522210">of</span> <span m="4522990">maximum</span> <span m="4523910">local</span>
  <span m="4524280">increase</span> <span m="4524690">of</span> <span m="4524780">j.</span>
  <span m="4525070">Negative</span> <span m="4525450">gradient of</span> <span m="4525770">j</span>
  <span m="4525990">points</span> <span m="4526320">in</span> <span m="4526480">the</span>
  <span m="4526640">direction</span> <span m="4527000">of</span> <span m="4527110">steepest</span>
  <span m="4527340">descent.</span> <span m="4528300">So</span> <span m="4529070">here''s</span>
  <span m="4529300">the</span> <span m="4529450">algorithm.</span> <span m="4529990">But</span>
  <span m="4530470">again,</span> <span m="4530690">just</span> <span m="4530750">think</span>
  <span m="4530970">about</span> <span m="4531150">the</span> <span m="4531210">landscape.</span>
  <span m="4531780">What</span> <span m="4532290">are</span> <span m="4532330">you</span>
  <span m="4532440">doing?</span></p><p><span m="4532820">You''re standing</span>
  <span m="4533170">in</span> <span m="4533240">the</span> <span m="4533310">landscape.</span>
  <span m="4533610">You''re</span> <span m="4533910">looking</span> <span m="4534220">around.</span>
  <span m="4534580">You''re</span> <span m="4534650">finding</span> <span m="4534900">the</span>
  <span m="4534970">direction</span> <span m="4535300">of</span> <span m="4535430">steepest</span>
  <span m="4535770">descent.</span> <span m="4537110">And</span> <span m="4537220">you''re</span>
  <span m="4537280">going</span> <span m="4537400">to</span> <span m="4537460">go</span>
  <span m="4537620">in</span> <span m="4537690">that</span> <span m="4537830">direction.</span></p><p><span
  m="4538460">And</span> <span m="4538470">we''ll</span> <span m="4538620">have</span>
  <span m="4538750">to</span> <span m="4538820">talk</span> <span m="4539210">on</span>
  <span m="4539730">Monday</span> <span m="4540030">about</span> <span m="4540240">how</span>
  <span m="4540340">to</span> <span m="4540430">choose</span> <span m="4540680">the
  alpha.</span> <span m="4540975">But</span> <span m="4541410">we</span> <span m="4541510">find</span>
  <span m="4541740">the</span> <span m="4541800">direction</span> <span m="4542130">of</span>
  <span m="4542340">steepest</span> <span m="4542650">descent.</span> <span m="4544490">We</span>
  <span m="4544620">choose</span> <span m="4544890">the</span> <span m="4545000">alpha.</span></p><p><span
  m="4546520">We</span> <span m="4546630">take</span> <span m="4546820">a</span> <span
  m="4546860">step.</span> <span m="4547130">We</span> <span m="4547260">look</span>
  <span m="4547440">around.</span> <span m="4548230">We</span> <span m="4548340">find</span>
  <span m="4548550">the</span> <span m="4548590">direction</span> <span m="4548910">of</span>
  <span m="4549060">steepest</span> <span m="4549410">descent.</span> <span m="4549760">We</span>
  <span m="4549840">can</span> <span m="4549950">pick</span> <span m="4550140">a</span>
  <span m="4550260">new</span> <span m="4550330">gradient,</span> <span m="4553290">find</span>
  <span m="4553390">the</span> <span m="4553450">new</span> <span m="4553630">alpha,</span>
  <span m="4554130">take</span> <span m="4554340">a</span> <span m="4554390">step,</span>
  <span m="4554680">and</span> <span m="4555320">keep</span> <span m="4555980">repeating.</span></p><p><span
  m="4558538">AUDIENCE: [INAUDIBLE]</span></p><p><span m="4569640">PROFESSOR: That''s</span>
  <span m="4569860">right.</span> <span m="4571160">That''s</span> <span m="4571350">exactly</span>
  <span m="4571670">right.</span> <span m="4571860">And</span> <span m="4571980">I''ll</span>
  <span m="4572070">show</span> <span m="4572200">you</span> <span m="4572370">how</span>
  <span m="4572690">we</span> <span m="4572840">do</span> <span m="4572960">this</span>
  <span m="4573500">on</span> <span m="4573660">Monday.</span> <span m="4574050">That''s</span>
  <span m="4574270">exactly</span> <span m="4574400">right.</span> <span m="4574620">It
  becomes</span> <span m="4575010">[INAUDIBLE]</span> <span m="4575130">the</span>
  <span m="4575220">1D</span> <span m="4575520">search.</span> <span m="4575810">Because</span>
  <span m="4576030">once</span> <span m="4576220">you''ve</span> <span m="4576290">define</span>
  <span m="4576610">the</span> <span m="4576680">direction,</span> <span m="4577150">it''s</span>
  <span m="4577330">now</span> <span m="4577500">just</span> <span m="4577910">1D.</span></p><p><span
  m="4578820">So</span> <span m="4579300">that''s</span> <span m="4579620">the</span>
  <span m="4579700">first</span> <span m="4580010">gradient-based</span> <span m="4580530">optimization</span>
  <span m="4580815">algorithm.</span> <span m="4581820">It''s</span> <span m="4582180">really</span>
  <span m="4582400">simple.</span> <span m="4582700">It turns</span> <span m="4582970">out</span>
  <span m="4583220">that''s</span> <span m="4583410">not</span> <span m="4583560">a</span>
  <span m="4583610">great</span> <span m="4583880">algorithm,</span> <span m="4584370">that
  it</span> <span m="4584490">converges</span> <span m="4585790">really</span> <span
  m="4586040">slowly.</span> <span m="4587410">But</span> <span m="4587570">conjugate</span>
  <span m="4587980">gradient</span> <span m="4588460">is</span> <span m="4588630">actually</span>
  <span m="4588880">something</span> <span m="4589400">that''s</span> <span m="4590210">not</span>
  <span m="4590510">too</span> <span m="4590660">different.</span></p><p><span m="4591250">So</span>
  <span m="4591370">now</span> <span m="4591890">what</span> <span m="4592010">does</span>
  <span m="4592110">conjugate</span> <span m="4592230">gradient do?</span> <span m="4593020">The</span>
  <span m="4593130">first</span> <span m="4593560">search</span> <span m="4593900">direction</span>
  <span m="4595050">S</span> <span m="4595190">on</span> <span m="4595280">the</span>
  <span m="4595340">first</span> <span m="4595630">iteration</span> <span m="4596720">is</span>
  <span m="4596900">the</span> <span m="4596970">steepest</span> <span m="4597500">descent</span>
  <span m="4597660">direction.</span> <span m="4599120">Yeah.</span> <span m="4600100">But</span>
  <span m="4600250">then</span> <span m="4600390">on</span> <span m="4600520">subsequent</span>
  <span m="4601120">iterations,</span> <span m="4601820">the</span> <span m="4601920">search</span>
  <span m="4602110">direction</span> <span m="4602700">is</span> <span m="4602950">the</span>
  <span m="4603040">steepest</span> <span m="4603570">descent</span> <span m="4603940">direction</span>
  <span m="4604910">minus</span> <span m="4605090">squared</span> <span m="4605200">j</span>
  <span m="4606530">plus</span> <span m="4606805">this</span> <span m="4607080">term</span>
  <span m="4607500">that''s</span> <span m="4607750">beta</span> <span m="4608060">q</span>
  <span m="4608640">times</span> <span m="4608900">H</span> <span m="4609020">q minus</span>
  <span m="4609340">1,</span> <span m="4610080">so</span> <span m="4610450">the</span>
  <span m="4610560">steepest</span> <span m="4611040">descent</span> <span m="4611510">direction</span>
  <span m="4612020">modified</span> <span m="4613490">by</span> <span m="4614030">the</span>
  <span m="4614160">last</span> <span m="4615095">search</span> <span m="4615380">direction.</span></p><p><span
  m="4616900">And</span> <span m="4617230">the</span> <span m="4617300">beta</span>
  <span m="4617990">is</span> <span m="4618490">the</span> <span m="4618600">ratio</span>
  <span m="4619080">of</span> <span m="4619240">the</span> <span m="4619320">gradients</span>
  <span m="4619970">on the</span> <span m="4620250">last two--</span> <span m="4621240">the</span>
  <span m="4621630">ratio of</span> <span m="4621950">the</span> <span m="4622020">norm</span>
  <span m="4622190">are</span> <span m="4622250">the</span> <span m="4622310">gradients</span>
  <span m="4622570">from</span> <span m="4622690">the</span> <span m="4622750">last</span>
  <span m="4622970">two</span> <span m="4623300">search</span> <span m="4623680">directions.</span>
  <span m="4624990">So</span> <span m="4625910">what</span> <span m="4626100">is</span>
  <span m="4626340">going</span> <span m="4626660">on</span> <span m="4626800">here?</span>
  <span m="4627560">Again,</span> <span m="4627830">I</span> <span m="4627910">think</span>
  <span m="4628820">you</span> <span m="4628920">kind of</span> <span m="4629110">look</span>
  <span m="4629350">at the</span> <span m="4629440">math.</span></p><p><span m="4630640">But</span>
  <span m="4630790">basically,</span> <span m="4631150">what</span> <span m="4631410">is</span>
  <span m="4631560">happening</span> <span m="4631930">is</span> <span m="4632030">you</span>
  <span m="4632090">think</span> <span m="4632240">about</span> <span m="4632430">the</span>
  <span m="4632500">landscape.</span> <span m="4633180">So</span> <span m="4633390">I''m</span>
  <span m="4633560">standing</span> <span m="4633980">at</span> <span m="4634060">x0.</span>
  <span m="4635210">I</span> <span m="4635300">find</span> <span m="4635540">the</span>
  <span m="4635600">direction</span> <span m="4636010">the</span> <span m="4636090">steepest</span>
  <span m="4636600">descent.</span> <span m="4638360">I</span> <span m="4638500">move</span>
  <span m="4638720">in</span> <span m="4638800">that</span> <span m="4638960">direction.</span></p><p><span
  m="4640330">Now</span> <span m="4640450">when</span> <span m="4640580">I</span>
  <span m="4640650">get</span> <span m="4640810">to</span> <span m="4640890">the</span>
  <span m="4640970">second</span> <span m="4641290">iteration,</span> <span m="4641950">I</span>
  <span m="4642060">find</span> <span m="4642350">the</span> <span m="4642410">direction</span>
  <span m="4642860">of</span> <span m="4643200">steepest</span> <span m="4643290">descent.</span>
  <span m="4644560">But</span> <span m="4644830">I</span> <span m="4644880">also</span>
  <span m="4645140">look</span> <span m="4645330">over</span> <span m="4645520">my</span>
  <span m="4645680">shoulder,</span> <span m="4646140">and</span> <span m="4646250">I</span>
  <span m="4646330">see</span> <span m="4646600">where</span> <span m="4646780">did</span>
  <span m="4646910">I</span> <span m="4647000">come</span> <span m="4647260">from.</span>
  <span m="4648670">I</span> <span m="4648760">find</span> <span m="4648990">the</span>
  <span m="4649050">direction</span> <span m="4649380">of</span> <span m="4649690">the</span>
  <span m="4649930">steepest</span> <span m="4650220">descent.</span> <span m="4650340">And
  then</span> <span m="4650450">depending</span> <span m="4650800">on</span> <span
  m="4650910">where</span> <span m="4651050">I</span> <span m="4651130">came</span>
  <span m="4651390">from,</span> <span m="4651600">I''m</span> <span m="4651700">going</span>
  <span m="4651820">to</span> <span m="4651880">modify</span> <span m="4652430">that</span>
  <span m="4652590">direction</span> <span m="4652970">a</span> <span m="4653020">little</span>
  <span m="4653260">bit,</span> <span m="4654220">and</span> <span m="4654410">then</span>
  <span m="4654580">move.</span></p><p><span m="4656150">And</span> <span m="4656280">then</span>
  <span m="4656380">I''m</span> <span m="4656460">going</span> <span m="4656580">to</span>
  <span m="4656650">go,</span> <span m="4656920">and I''m going to</span> <span m="4657140">find</span>
  <span m="4657350">the</span> <span m="4657390">direction</span> <span m="4657670">of</span>
  <span m="4657800">steepest</span> <span m="4658160">descent.</span> <span m="4658320">I''m
  going</span> <span m="4658420">to</span> <span m="4658610">look</span> <span m="4658950">where</span>
  <span m="4659140">I just</span> <span m="4659330">came</span> <span m="4659590">from</span>
  <span m="4659820">and</span> <span m="4659990">modify</span> <span m="4660500">it</span>
  <span m="4660580">a</span> <span m="4660610">little</span> <span m="4660840">bit.</span>
  <span m="4661100">So</span> <span m="4661230">I''m</span> <span m="4661320">incorporating</span>
  <span m="4662260">information</span> <span m="4663630">about</span> <span m="4663960">where</span>
  <span m="4664130">I</span> <span m="4664210">came</span> <span m="4664560">from.</span></p><p><span
  m="4665850">And</span> <span m="4665880">if</span> <span m="4665970">you</span>
  <span m="4666050">look</span> <span m="4666190">at</span> <span m="4666270">this</span>
  <span m="4666410">example,</span> <span m="4667430">this</span> <span m="4667580">function</span>
  <span m="4668000">is</span> <span m="4668190">a</span> <span m="4668260">really</span>
  <span m="4668540">famous</span> <span m="4669010">example</span> <span m="4669660">that</span>
  <span m="4670030">is</span> <span m="4670100">an analytic</span> <span m="4670450">example</span>
  <span m="4670910">that''s</span> <span m="4671060">often</span> <span m="4671360">used
  as</span> <span m="4671840">optimization</span> <span m="4672830">algorithms.</span>
  <span m="4673190">It''s</span> <span m="4673340">called</span> <span m="4673450">the</span>
  <span m="4673660">Rosenbrock</span> <span m="4674060">function.</span> <span m="4674510">It''s</span>
  <span m="4674620">sometimes</span> <span m="4674930">called</span> <span m="4675110">the</span>
  <span m="4675180">banana</span> <span m="4675580">function,</span> <span m="4676380">because</span>
  <span m="4676610">it</span> <span m="4676670">looks</span> <span m="4676830">like</span>
  <span m="4676970">a</span> <span m="4677020">banana</span> <span m="4677580">with</span>
  <span m="4677770">really</span> <span m="4678080">steep</span> <span m="4678790">walls.</span></p><p><span
  m="4680010">And</span> <span m="4680350">what</span> <span m="4680490">you</span>
  <span m="4680550">can</span> <span m="4680700">see</span> <span m="4680890">here</span>
  <span m="4681040">on</span> <span m="4681190">the</span> <span m="4681270">left</span>
  <span m="4681620">is</span> <span m="4682050">the</span> <span m="4682330">steepest</span>
  <span m="4682720">descent</span> <span m="4683230">algorithm</span> <span m="4685750">starting</span>
  <span m="4686130">from</span> <span m="4686260">the</span> <span m="4686330">initial</span>
  <span m="4686610">point</span> <span m="4686870">here.</span> <span m="4687160">So</span>
  <span m="4687290">we</span> <span m="4687370">start</span> <span m="4687690">here.</span>
  <span m="4688450">We</span> <span m="4688550">compute</span> <span m="4688990">the</span>
  <span m="4689070">direction</span> <span m="4689430">of</span> <span m="4689580">steepest</span>
  <span m="4690000">descent.</span> <span m="4690460">These are</span> <span m="4690530">contours</span>
  <span m="4691090">of</span> <span m="4691150">objectives.</span> <span m="4691730">So</span>
  <span m="4691850">the</span> <span m="4691930">direction</span> <span m="4692240">of</span>
  <span m="4692810">steepest</span> <span m="4693110">descent</span> <span m="4693280">is</span>
  <span m="4693630">perpendicular</span> <span m="4693970">to</span> <span m="4694310">the</span>
  <span m="4694380">contours,</span> <span m="4694970">right?</span></p><p><span m="4695777">Yup.</span>
  <span m="4697180">Perpendicular</span> <span m="4697380">to</span> <span m="4697640">the</span>
  <span m="4697760">contours,</span> <span m="4698160">what</span> <span m="4698310">you</span>
  <span m="4698380">were</span> <span m="4698460">saying,</span> <span m="4698690">Dominic.</span>
  <span m="4699060">It</span> <span m="4699160">looks</span> <span m="4699360">along</span>
  <span m="4699650">here.</span> <span m="4699970">And</span> <span m="4700110">there''s</span>
  <span m="4700280">the</span> <span m="4700340">point</span> <span m="4700630">that</span>
  <span m="4700740">would</span> <span m="4700870">minimize.</span></p><p><span m="4701905">It</span>
  <span m="4702340">gets</span> <span m="4702550">to</span> <span m="4702640">the</span>
  <span m="4702730">new</span> <span m="4702920">point,</span> <span m="4703400">completes</span>
  <span m="4703760">the</span> <span m="4703820">direction of</span> <span m="4704240">steepest</span>
  <span m="4704580">descent,</span> <span m="4705520">moves</span> <span m="4705830">along</span>
  <span m="4706390">here.</span> <span m="4707260">It</span> <span m="4707695">gets</span>
  <span m="4708130">here,</span> <span m="4708630">completes</span> <span m="4708770">the</span>
  <span m="4708840">direction</span> <span m="4709190">of</span> <span m="4709490">steepest</span>
  <span m="4709680">descent,</span> <span m="4710260">steepest</span> <span m="4710400">descent,</span>
  <span m="4710930">steepest</span> <span m="4711350">descent,</span> <span m="4712090">steepest</span>
  <span m="4712390">descent,</span> <span m="4712680">can you see what''s</span> <span
  m="4712990">happening</span> <span m="4713350">to</span> <span m="4713430">this</span>
  <span m="4713540">guy?</span> <span m="4714480">It''s</span> <span m="4714650">going</span>
  <span m="4714780">to</span> <span m="4714890">take</span> <span m="4716260">hundreds</span>
  <span m="4716800">probably</span> <span m="4717060">of</span> <span m="4717200">little</span>
  <span m="4717460">tiny</span> <span m="4717810">steps</span> <span m="4718350">going</span>
  <span m="4718760">zz,</span> <span m="4719173">zz,</span> <span m="4719586">zz,
  zz,</span> <span m="4720000">as it</span> <span m="4720070">gets</span> <span m="4720320">to</span>
  <span m="4720470">the</span> <span m="4720750">optimum</span> <span m="4721180">solution.</span></p><p><span
  m="4722726">What does</span> <span m="4723169">conjugate</span> <span m="4723612">gradient
  do?</span> <span m="4724500">So</span> <span m="4724540">the</span> <span m="4724640">first</span>
  <span m="4725480">one</span> <span m="4725720">is</span> <span m="4725860">the</span>
  <span m="4725930">same,</span> <span m="4726300">the</span> <span m="4726360">first</span>
  <span m="4726825">iteration,</span> <span m="4727670">steepest</span> <span m="4727810">descent.</span>
  <span m="4728850">But</span> <span m="4729040">now,</span> <span m="4729490">when</span>
  <span m="4729620">we</span> <span m="4729700">get</span> <span m="4729840">to</span>
  <span m="4729940">this</span> <span m="4730190">point,</span> <span m="4731180">we</span>
  <span m="4731210">compute</span> <span m="4731620">the</span> <span m="4731690">direction</span>
  <span m="4732130">of</span> <span m="4732230">steepest</span> <span m="4732690">descent,</span>
  <span m="4733280">which</span> <span m="4733510">again</span> <span m="4733810">would</span>
  <span m="4733970">be</span> <span m="4735370">perpendicular</span> <span m="4736370">to</span>
  <span m="4736470">the</span> <span m="4736540">contour.</span> <span m="4737280">So</span>
  <span m="4737510">it</span> <span m="4737600">would</span> <span m="4737760">be</span>
  <span m="4738490">like</span> <span m="4738730">that.</span></p><p><span m="4739780">But</span>
  <span m="4739920">now,</span> <span m="4740110">we</span> <span m="4740230">also</span>
  <span m="4740540">look</span> <span m="4740810">back</span> <span m="4740980">over</span>
  <span m="4741210">our</span> <span m="4741310">shoulder,</span> <span m="4741830">see</span>
  <span m="4742000">where</span> <span m="4742130">we</span> <span m="4742260">came</span>
  <span m="4742590">from,</span> <span m="4743200">compute</span> <span m="4743540">that</span>
  <span m="4743760">data,</span> <span m="4745320">add</span> <span m="4745700">in
  that</span> <span m="4745870">beta</span> <span m="4747470">S1</span> <span m="4747940">term
  and</span> <span m="4748510">modify</span> <span m="4748795">it</span> <span m="4749080">a</span>
  <span m="4749120">little</span> <span m="4749330">bit.</span> <span m="4749660">So
  it</span> <span m="4749820">actually</span> <span m="4750020">takes</span> <span
  m="4750290">us</span> <span m="4750450">there.</span> <span m="4751470">Not</span>
  <span m="4751990">terribly</span> <span m="4752310">different,</span> <span m="4752750">right?</span></p><p><span
  m="4753600">But</span> <span m="4753740">enough</span> <span m="4754030">different.</span>
  <span m="4754610">Now,</span> <span m="4754850">we</span> <span m="4754940">get</span>
  <span m="4755130">here.</span> <span m="4755630">Steepest</span> <span m="4755940">descent,</span>
  <span m="4756230">again,</span> <span m="4756550">would</span> <span m="4756710">be</span>
  <span m="4757520">perpendicular.</span> <span m="4758010">It</span> <span m="4758090">would</span>
  <span m="4758200">be</span> <span m="4758340">here.</span> <span m="4758580">We</span>
  <span m="4758680">modify</span> <span m="4758970">it</span> <span m="4759260">a</span>
  <span m="4759300">little</span> <span m="4759530">bit.</span> <span m="4759750">We</span>
  <span m="4759840">skip</span> <span m="4760120">all</span> <span m="4760220">the</span>
  <span m="4760300">way</span> <span m="4760490">here</span> <span m="4761550">and</span>
  <span m="4761840">continue</span> <span m="4762220">on.</span></p><p><span m="4762420">So</span>
  <span m="4762550">conjugate</span> <span m="4762880">gradient</span> <span m="4763490">converted</span>
  <span m="4763860">in</span> <span m="4764000">1,</span> <span m="4764360">2,</span>
  <span m="4764980">3,</span> <span m="4765410">4,</span> <span m="4765950">5</span>
  <span m="4766500">iterations.</span> <span m="4767690">Whereas,</span> <span m="4767910">steepest</span>
  <span m="4768230">descent</span> <span m="4769000">[AUDIO OUT]</span> <span m="4775560">gradient</span>
  <span m="4776496">[AUDIO OUT]</span> <span m="4781920">much,</span> <span m="4782760">much</span>
  <span m="4782890">faster</span> <span m="4783230">[INAUDIBLE]</span> <span m="4783707">to
  converge.</span> <span m="4785140">And</span> <span m="4786450">[AUDIO OUT]</span>
  <span m="4789930">and</span> <span m="4790030">you</span> <span m="4790090">want</span>
  <span m="4790220">to</span> <span m="4790280">get</span> <span m="4790480">down,</span>
  <span m="4791360">don''t</span> <span m="4791700">use</span> <span m="4791970">steepest</span>
  <span m="4792280">descent.</span> <span m="4792690">Because</span> <span m="4793010">you''re</span>
  <span m="4793080">going to</span> <span m="4793220">end</span> <span m="4793460">up</span>
  <span m="4794490">going</span> <span m="4794810">back</span> <span m="4795020">and</span>
  <span m="4795140">forth</span> <span m="4795370">across</span> <span m="4795620">yourself.</span>
  <span m="4796600">Always</span> <span m="4796910">look</span> <span m="4797090">to</span>
  <span m="4797190">see</span> <span m="4797340">where</span> <span m="4797440">you</span>
  <span m="4797550">came</span> <span m="4797770">from</span> <span m="4798790">[INAUDIBLE].</span></p><p><span
  m="4800850">OK.</span> <span m="4801200">So</span> <span m="4801510">let''s</span>
  <span m="4801780">finish</span> <span m="4802050">there.</span> <span m="4802290">We''ll</span>
  <span m="4802450">talk</span> <span m="4802650">about</span> <span m="4802920">Newton''s</span>
  <span m="4803600">method</span> <span m="4804150">and</span> <span m="4804740">various</span>
  <span m="4805040">other</span> <span m="4805140">things.</span> <span m="4805310">We''ll</span>
  <span m="4805400">talk</span> <span m="4805530">about</span> <span m="4805710">computing</span>
  <span m="4806050">gradients</span> <span m="4806540">on</span> <span m="4806900">a</span>
  <span m="4807000">Monday</span> <span m="4807320">as</span> <span m="4807440">well.</span>
  <span m="4807850">But</span> <span m="4808260">if you</span> <span m="4808380">have</span>
  <span m="4808490">questions,</span> <span m="4808870">stick</span> <span m="4809050">around.</span>
  <span m="4809380">I''m going to do</span> <span m="4809570">office</span> <span
  m="4809860">hours</span> <span m="4810130">now</span> <span m="4810465">if you</span>
  <span m="4810800">questions</span> <span m="4811160">about</span> <span m="4811360">the</span>
  <span m="4811390">lecture</span> <span m="4811800">or</span> <span m="4813020">questions</span>
  <span m="4813390">about</span> <span m="4813580">the</span> <span m="4813680">project.</span></p>'
type: course
uid: 90a1ac4713f47de217c82b87fab8f1d1

---
None