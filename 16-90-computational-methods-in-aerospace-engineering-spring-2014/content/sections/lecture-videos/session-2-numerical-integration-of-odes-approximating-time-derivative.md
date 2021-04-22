---
about_this_resource_text: <p><strong>Description:</strong> This lecture covers the
  sources of error when solving an ODE and introduces accuracy, including forward
  Euler and midpoint rule.  The lecture introduces a 'contest' in which students work
  in pairs to solve the local order of accuracy.</p> <p><strong>Instructor:</strong>
  Qiqi Wang</p><p>The recording quality of this video is the best available from the
  source.</p>
course_id: 16-90-computational-methods-in-aerospace-engineering-spring-2014
embedded_media:
- id: Video-YouTube-Stream
  media_location: Yyb7I-n6rZI
  parent_uid: d3296ef767aec87922d4de3cd2722027
  title: Video-YouTube-Stream
  type: Video
  uid: a5f282791ce0b9115b85d434a085b873
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/Yyb7I-n6rZI/default.jpg
  parent_uid: d3296ef767aec87922d4de3cd2722027
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: f6207452b44e283c0542485b0626ed0b
- id: 3Play-3PlayYouTubeid-MP4
  media_location: Yyb7I-n6rZI
  parent_uid: d3296ef767aec87922d4de3cd2722027
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 189065922a28ca7ac8cf1fa077b4b88c
- id: Yyb7I-n6rZI.srt
  parent_uid: d3296ef767aec87922d4de3cd2722027
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-2-numerical-integration-of-odes-approximating-time-derivative/Yyb7I-n6rZI.srt
  title: 3play caption file
  type: null
  uid: b8cfac4d78b36c9a6594aa83549552f3
- id: Yyb7I-n6rZI.pdf
  parent_uid: d3296ef767aec87922d4de3cd2722027
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-2-numerical-integration-of-odes-approximating-time-derivative/Yyb7I-n6rZI.pdf
  title: 3play pdf file
  type: null
  uid: 86baf7ceeffc55546bcef8ab97057d17
- id: Caption-3Play YouTube id-SRT
  parent_uid: d3296ef767aec87922d4de3cd2722027
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 7cfd20d18a09cafb157738021e5b85de
- id: Transcript-3Play YouTube id-PDF
  parent_uid: d3296ef767aec87922d4de3cd2722027
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 72526cb733eff1556125b0dec880b745
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT16.90S14/MIT16_90S14_L02_300k.mp4
  parent_uid: d3296ef767aec87922d4de3cd2722027
  title: Video-Internet Archive-MP4
  type: Video
  uid: 9c5b692a81199a07c5e29a7ee92140f1
inline_embed_id: 7753405session2:numericalintegrationofodes:approximatingtimederivative11549741
layout: video
order_index: null
parent_uid: 809ebf7c44bfb36e8786306747d7e32f
related_resources_text: ''
short_url: session-2-numerical-integration-of-odes-approximating-time-derivative
technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-2-numerical-integration-of-odes-approximating-time-derivative
template_type: Tabbed
title: 'Session 2: Numerical Integration of ODEs: Approximating time derivative'
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
  <span m="11310">to</span> <span m="11430">view</span> <span m="11630">additional</span>
  <span m="12050">materials</span> <span m="12670">from</span> <span m="12860">hundreds</span>
  <span m="13180">of</span> <span m="13280">MIT</span> <span m="13650">courses,</span>
  <span m="14960">visit</span> <span m="15150">MIT</span> <span m="15670">OpenCourseWare</span>
  <span m="16580">at</span> <span m="16920">ocw.mit.edu.</span></p><p><span m="26246">PROFESSOR:
  All right,</span> <span m="27350">let''s</span> <span m="27790">get</span> <span
  m="28050">started.</span> <span m="31150">So</span> <span m="31430">here,</span>
  <span m="31740">as</span> <span m="31800">I</span> <span m="32040">said,</span>
  <span m="32493">I assume</span> <span m="32946">that</span> <span m="33400">everybody</span>
  <span m="33530">[INAUDIBLE]</span> <span m="34210">has</span> <span m="34670">already</span>
  <span m="35110">done</span> <span m="35380">the</span> <span m="35840">reading.</span>
  <span m="36760">OK,</span> <span m="37697">what</span> <span m="38184">I''m going</span>
  <span m="38671">to do</span> <span m="39160">today</span> <span m="39650">is</span>
  <span m="40020">not</span> <span m="40390">[INAUDIBLE]</span> <span m="41006">repeat</span>
  <span m="41700">any</span> <span m="42130">of the</span> <span m="42290">things</span>
  <span m="42540">you</span> <span m="42905">have</span> <span m="43270">already</span>
  <span m="43660">read.</span></p><p><span m="45060">But</span> <span m="45250">I</span>
  <span m="45440">also</span> <span m="45640">don''t</span> <span m="46200">assume</span>
  <span m="46810">you</span> <span m="47660">already</span> <span m="48340">mastered</span>
  <span m="48690">all</span> <span m="49050">the</span> <span m="49230">material</span>
  <span m="50070">[INAUDIBLE].</span> <span m="51330">So</span> <span m="51900">what</span>
  <span m="52210">I''m</span> <span m="52340">going</span> <span m="52480">to</span>
  <span m="52570">do</span> <span m="52990">is</span> <span m="53800">kind</span>
  <span m="53830">of</span> <span m="54620">[INAUDIBLE]</span> <span m="54890">to</span>
  <span m="54990">give</span> <span m="55330">you</span> <span m="55700">a</span>
  <span m="56106">view</span> <span m="56512">of</span> <span m="56920">more</span>
  <span m="57220">or less</span> <span m="57450">the</span> <span m="57530">same</span>
  <span m="58010">material,</span> <span m="58455">maybe a</span> <span m="58900">little
  bit</span> <span m="59345">more.</span> <span m="59790">But</span> <span m="60235">from
  a</span> <span m="60680">slightly different</span> <span m="61125">angle.</span>
  <span m="63564">And</span> <span m="64440">which</span> <span m="64620">means</span>
  <span m="64860">we are</span> <span m="64970">going to</span> <span m="65080">[INAUDIBLE]</span>
  <span m="65825">but</span> <span m="66301">like</span> <span m="67253">[INAUDIBLE]</span>
  <span m="69440">may</span> <span m="70000">look</span> <span m="70230">like</span>
  <span m="70400">this</span> <span m="70867">one.</span> <span m="71801">The</span>
  <span m="72270">syntax</span> <span m="72450">may</span> <span m="72910">be</span>
  <span m="73370">different</span> <span m="73830">and</span> <span m="74290">may</span>
  <span m="74620">denote</span> <span m="75110">things</span> <span m="75600">with</span>
  <span m="75830">a</span> <span m="75910">different</span> <span m="76360">symbol.</span></p><p><span
  m="76940">But,</span> <span m="77150">like,</span> <span m="77270">any</span> <span
  m="78090">[INAUDIBLE]</span> <span m="78340">is</span> <span m="78780">the</span>
  <span m="78910">same</span> <span m="79290">and</span> <span m="79930">you</span>
  <span m="80402">should be</span> <span m="80874">able to</span> <span m="81346">read
  the</span> <span m="81820">style.</span> <span m="82840">You</span> <span m="83300">should</span>
  <span m="83510">read</span> <span m="83630">what</span> <span m="84020">I''m</span>
  <span m="84230">going to</span> <span m="84410">be</span> <span m="84590">writing.</span>
  <span m="86420">And</span> <span m="86690">in</span> <span m="86860">addition</span>
  <span m="87280">to</span> <span m="87400">that,</span> <span m="87780">I''m</span>
  <span m="87940">going</span> <span m="88120">to</span> <span m="88270">ask</span>
  <span m="88590">you</span> <span m="89000">to</span> <span m="89460">work</span>
  <span m="89830">out</span> <span m="90160">some</span> <span m="90540">problems</span>
  <span m="91160">for</span> <span m="91270">yourself</span> <span m="91820">or</span>
  <span m="92110">actually</span> <span m="92547">in</span> <span m="92984">teams</span>
  <span m="93860">based</span> <span m="94430">on</span> <span m="94620">what</span>
  <span m="94750">you</span> <span m="95230">read</span> <span m="95725">and</span>
  <span m="96220">what</span> <span m="96480">I''m going</span> <span m="96850">to</span>
  <span m="97010">be</span> <span m="97350">discussing</span> <span m="97756">today.</span></p><p><span
  m="98568">So</span> <span m="98974">I</span> <span m="99380">brought</span> <span
  m="99635">these</span> <span m="99890">things.</span> <span m="100746">I''m</span>
  <span m="101174">going</span> <span m="101602">to</span> <span m="102030">be</span>
  <span m="102260">actually</span> <span m="102701">[INAUDIBLE].</span> <span m="108070">And</span>
  <span m="108500">I</span> <span m="108730">also</span> <span m="109080">brought</span>
  <span m="109300">[INAUDIBLE]</span> <span m="110170">each</span> <span m="110556">of
  you</span> <span m="110942">are</span> <span m="111330">going</span> <span m="111450">to</span>
  <span m="111530">be</span> <span m="111700">working</span> <span m="111950">[INAUDIBLE].</span>
  <span m="120270">OK,</span> <span m="120960">and</span> <span m="121260">[INAUDIBLE]</span>
  <span m="121610">say</span> <span m="121660">which</span> <span m="122110">is</span>
  <span m="122320">the</span> <span m="122420">most</span> <span m="122700">active</span>
  <span m="123970">[INAUDIBLE].</span></p><p><span m="126000">OK,</span> <span m="126300">to</span>
  <span m="126490">start</span> <span m="126800">this,</span> <span m="127600">I''m</span>
  <span m="127830">going</span> <span m="128000">to</span> <span m="128090">be--</span>
  <span m="130520">wait,</span> <span m="131020">OK.</span> <span m="132400">I''m</span>
  <span m="132850">going</span> <span m="132990">to</span> <span m="133080">be</span>
  <span m="133190">briefly</span> <span m="133830">reviewing</span> <span m="134560">what</span>
  <span m="134895">you read,</span> <span m="135230">which</span> <span m="135500">is</span>
  <span m="135870">how</span> <span m="136090">to</span> <span m="136190">basically</span>
  <span m="136330">write</span> <span m="136570">the</span> <span m="136770">function.</span>
  <span m="137890">And</span> <span m="138120">then</span> <span m="138450">in</span>
  <span m="138650">addition</span> <span m="139130">to</span> <span m="139560">writing</span>
  <span m="140060">down</span> <span m="140490">formulas,</span> <span m="140890">I''m</span>
  <span m="141080">going</span> <span m="141220">to</span> <span m="141290">be</span>
  <span m="141470">demonstrating</span> <span m="141750">things</span> <span m="142230">in</span>
  <span m="142660">MATLAB,</span> <span m="143960">OK?</span> <span m="144970">Discretize</span>
  <span m="145600">a</span> <span m="145700">function--</span> <span m="146230">let''s</span>
  <span m="147270">start</span> <span m="147630">with</span> <span m="148390">a</span>
  <span m="148510">function</span> <span m="149120">that,</span> <span m="149440">like,</span>
  <span m="149730">most</span> <span m="150050">of</span> <span m="150190">you</span>
  <span m="150920">very</span> <span m="151520">commonly</span> <span m="152010">see</span>
  <span m="152820">[INAUDIBLE]</span> <span m="153580">ODEs.</span></p><p><span m="154930">When</span>
  <span m="155190">you</span> <span m="155580">write</span> <span m="155840">down</span>
  <span m="157310">f--</span> <span m="158240">let</span> <span m="158710">me</span>
  <span m="158870">change</span> <span m="159160">to a</span> <span m="159290">different</span>
  <span m="159520">color.</span> <span m="164630">OK,</span> <span m="164980">if</span>
  <span m="165120">you</span> <span m="165250">write</span> <span m="165500">down</span>
  <span m="165800">F</span> <span m="166070">of</span> <span m="166220">T</span> <span
  m="167560">equal</span> <span m="167990">to</span> <span m="168120">E</span> <span
  m="168610">to</span> <span m="168710">the</span> <span m="169110">minus</span> <span
  m="169455">lambda</span> <span m="169800">T--</span> <span m="171410">OK,</span>
  <span m="171660">can</span> <span m="171850">somebody</span> <span m="172180">tell</span>
  <span m="172470">me</span> <span m="172600">why</span> <span m="173170">this</span>
  <span m="173440">function</span> <span m="174260">is</span> <span m="174630">commonly</span>
  <span m="175180">ODEs?</span> <span m="176880">It''s</span> <span m="177290">a</span>
  <span m="177560">solution</span> <span m="178270">to</span> <span m="178870">essentially</span>
  <span m="178950">the</span> <span m="179120">simplest</span> <span m="179290">ODE</span>
  <span m="180140">you</span> <span m="180270">can</span> <span m="180460">find</span>
  <span m="180690">in</span> <span m="180780">the</span> <span m="180870">world--</span>
  <span m="181980">df</span> <span m="182430">dt</span> <span m="183510">equal</span>
  <span m="183900">to</span> <span m="184040">what?</span></p><p><span m="186805">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="188740">PROFESSOR: Minus</span> <span m="189180">lambda</span>
  <span m="190160">times</span> <span m="190650">f</span> <span m="190920">of</span>
  <span m="191060">t,</span> <span m="191980">right?</span> <span m="192820">So</span>
  <span m="192930">if</span> <span m="193110">I</span> <span m="193260">solve</span>
  <span m="193630">this</span> <span m="194070">ordinary</span> <span m="194550">differential</span>
  <span m="195000">equation,</span> <span m="196090">I''m</span> <span m="196290">going</span>
  <span m="196420">to</span> <span m="196500">get</span> <span m="197580">this</span>
  <span m="197820">function.</span> <span m="199990">OK,</span> <span m="201110">if</span>
  <span m="201750">I</span> <span m="201880">draw</span> <span m="202220">the</span>
  <span m="202340">function,</span> <span m="203230">if</span> <span m="203410">I</span>
  <span m="203530">draw</span> <span m="203810">this</span> <span m="204000">function</span>
  <span m="204305">as</span> <span m="204610">a</span> <span m="204970">function</span>
  <span m="205160">of</span> <span m="205660">time,</span> <span m="207650">at</span>
  <span m="207960">t</span> <span m="208450">equal</span> <span m="208660">to</span>
  <span m="208780">0,</span> <span m="209120">the</span> <span m="209190">function</span>
  <span m="209680">has</span> <span m="209870">a</span> <span m="209920">value</span>
  <span m="210420">of</span> <span m="211030">1,</span> <span m="211570">right?</span>
  <span m="211940">This</span> <span m="212110">is</span> <span m="212280">f of</span>
  <span m="212660">t,</span> <span m="213040">this is</span> <span m="213435">t.</span></p><p><span
  m="214620">And</span> <span m="214830">how</span> <span m="215010">does</span> <span
  m="215200">the</span> <span m="215280">function</span> <span m="215640">look</span>
  <span m="215830">like</span> <span m="216090">for</span> <span m="216500">positive</span>
  <span m="216870">lambda?</span> <span m="220240">It''s</span> <span m="220470">going</span>
  <span m="220610">to</span> <span m="220680">decay</span> <span m="221460">exponentially.</span>
  <span m="222380">That</span> <span m="222670">is</span> <span m="222870">what</span>
  <span m="223180">we</span> <span m="223340">call</span> <span m="223650">exponential</span>
  <span m="223810">decay</span> <span m="224700">to</span> <span m="225155">the</span>
  <span m="225610">minus</span> <span m="226000">lambda</span> <span m="226170">t,</span>
  <span m="227160">right?</span> <span m="228600">OK,</span> <span m="229280">this</span>
  <span m="229610">function</span> <span m="230080">is</span> <span m="230260">a</span>
  <span m="230330">function.</span> <span m="232000">It</span> <span m="232150">is</span>
  <span m="232340">a</span> <span m="232460">continuous</span> <span m="232950">function,</span>
  <span m="233450">which</span> <span m="233690">means</span> <span m="234400">it</span>
  <span m="234590">is,</span> <span m="235180">in</span> <span m="235400">some</span>
  <span m="235480">sense,</span> <span m="235770">infinite</span> <span m="236300">dimensional.</span>
  <span m="237700">You</span> <span m="237900">need</span> <span m="238190">infinitely</span>
  <span m="239090">many</span> <span m="239460">numbers</span> <span m="239790">or</span>
  <span m="240242">infinitely</span> <span m="241970">much</span> <span m="242240">memory</span>
  <span m="243090">to</span> <span m="243470">memorize</span> <span m="244200">this</span>
  <span m="244410">function</span> <span m="244760">in a</span> <span m="245213">computer,</span>
  <span m="246120">right?</span></p><p><span m="246770">Because</span> <span m="247230">for</span>
  <span m="247640">every</span> <span m="248130">t,</span> <span m="248440">every</span>
  <span m="248770">single</span> <span m="249150">t,</span> <span m="249900">you</span>
  <span m="250090">have</span> <span m="250280">a</span> <span m="250440">function</span>
  <span m="250870">value</span> <span m="251765">f</span> <span m="252140">of</span>
  <span m="252280">p.</span> <span m="253910">But</span> <span m="254100">computers</span>
  <span m="254810">have</span> <span m="255090">finite</span> <span m="255440">memory,</span>
  <span m="256700">although</span> <span m="257019">we</span> <span m="257200">have</span>
  <span m="257390">a</span> <span m="257450">lot</span> <span m="257649">of</span>
  <span m="257750">memory,</span> <span m="258110">but</span> <span m="258420">still</span>
  <span m="258630">finite.</span> <span m="260040">So</span> <span m="260290">we</span>
  <span m="260480">need</span> <span m="260850">to</span> <span m="261019">find</span>
  <span m="261300">a</span> <span m="261360">way</span> <span m="261660">to</span>
  <span m="261829">represent</span> <span m="262460">this</span> <span m="262680">function</span>
  <span m="263180">using</span> <span m="263760">a</span> <span m="263980">finite</span>
  <span m="264510">number</span> <span m="264830">of</span> <span m="265030">bits</span>
  <span m="265690">in a</span> <span m="265890">computer.</span> <span m="267540">How</span>
  <span m="267700">do</span> <span m="267770">we</span> <span m="267870">do</span>
  <span m="268060">that?</span></p><p><span m="271360">OK,</span> <span m="271630">we</span>
  <span m="271760">do</span> <span m="271960">that</span> <span m="272420">by</span>
  <span m="272590">first</span> <span m="272910">selecting</span> <span m="273400">a</span>
  <span m="273510">range.</span> <span m="273910">We</span> <span m="274050">cannot</span>
  <span m="275140">discretize</span> <span m="275610">the</span> <span m="275690">function</span>
  <span m="276390">for</span> <span m="276760">infinite</span> <span m="276870">t.</span>
  <span m="277130">We</span> <span m="277300">have</span> <span m="277480">to</span>
  <span m="277710">select</span> <span m="278050">a</span> <span m="278130">range</span>
  <span m="278385">and</span> <span m="278640">let''s</span> <span m="278910">say</span>
  <span m="279180">from</span> <span m="279580">0</span> <span m="280070">to</span>
  <span m="280420">some</span> <span m="280570">big</span> <span m="281000">t.</span></p><p><span
  m="283070">Is</span> <span m="283260">that</span> <span m="283430">enough?</span>
  <span m="285910">No</span> <span m="286320">we</span> <span m="286670">also</span>
  <span m="287100">need</span> <span m="287370">to</span> <span m="287490">discretize</span>
  <span m="288100">this</span> <span m="288350">interval</span> <span m="289190">into</span>
  <span m="289610">small</span> <span m="290230">time</span> <span m="291260">steps.</span>
  <span m="292600">And</span> <span m="293510">the</span> <span m="293650">first</span>
  <span m="293910">time</span> <span m="294360">step is</span> <span m="294500">usually</span>
  <span m="294860">just</span> <span m="294990">0.</span> <span m="296420">The</span>
  <span m="296530">second</span> <span m="296910">time</span> <span m="297170">step</span>
  <span m="297400">is</span> <span m="297560">delta</span> <span m="297940">t</span>
  <span m="299220">and</span> <span m="299550">the</span> <span m="299640">2</span>
  <span m="299990">delta</span> <span m="300370">t,</span> <span m="301640">3</span>
  <span m="302050">delta</span> <span m="302260">t,</span> <span m="303360">4</span>
  <span m="303670">delta</span> <span m="303730">t,</span> <span m="304710">et</span>
  <span m="304900">cetera.</span></p><p><span m="305690">And</span> <span m="306060">at</span>
  <span m="306170">t</span> <span m="306760">is</span> <span m="307000">the</span>
  <span m="307100">last</span> <span m="307480">time</span> <span m="307760">step.</span>
  <span m="309800">All</span> <span m="310060">right,</span> <span m="310980">so</span>
  <span m="311130">this</span> <span m="311250">discretization,</span> <span m="312280">when</span>
  <span m="312590">I</span> <span m="313080">do</span> <span m="313320">this</span>
  <span m="313570">thing</span> <span m="313810">in</span> <span m="313880">MATLAB--</span>
  <span m="314270">let</span> <span m="314590">me</span> <span m="314910">actually</span>
  <span m="315410">start</span> <span m="315680">up</span> <span m="315800">MATLAB.</span>
  <span m="316674">And</span> <span m="317450">when</span> <span m="317610">I</span>
  <span m="317690">do</span> <span m="317910">it in</span> <span m="318020">MATLAB,</span>
  <span m="318870">it</span> <span m="319060">is</span> <span m="319200">usually</span>
  <span m="319610">how</span> <span m="319910">we</span> <span m="320150">actually</span>
  <span m="320560">draw</span> <span m="320815">the function</span> <span m="321070">in</span>
  <span m="321413">MATLAB,</span> <span m="322100">right?</span></p><p><span m="322420">I</span>
  <span m="322530">believe</span> <span m="322910">a</span> <span m="323030">lot</span>
  <span m="323210">of</span> <span m="323320">you</span> <span m="323500">have</span>
  <span m="323720">done</span> <span m="323920">this</span> <span m="324100">before</span>
  <span m="324330">in</span> <span m="324820">some</span> <span m="324980">other</span>
  <span m="325280">classes.</span> <span m="326220">Here,</span> <span m="326420">I''m</span>
  <span m="326570">just</span> <span m="326790">trying</span> <span m="327010">to</span>
  <span m="327120">warm</span> <span m="327350">you</span> <span m="327520">up</span>
  <span m="328760">and</span> <span m="329080">get</span> <span m="329330">you,</span>
  <span m="330600">if</span> <span m="330770">you''re</span> <span m="331020">not</span>
  <span m="331290">familiar,</span> <span m="331380">get</span> <span m="331850">you</span>
  <span m="331980">familiar</span> <span m="332310">again</span> <span m="332770">with</span>
  <span m="333230">how</span> <span m="333360">do</span> <span m="333590">we do</span>
  <span m="333730">things in</span> <span m="334210">computer.</span> <span m="336610">I
  think I</span> <span m="337090">started</span> <span m="337570">MATLAB.</span></p><p><span
  m="339020">Right,</span> <span m="339880">so</span> <span m="340060">OK.</span>
  <span m="340390">So</span> <span m="341130">let</span> <span m="341280">me</span>
  <span m="341650">set a</span> <span m="341720">big</span> <span m="341990">T</span>
  <span m="342370">equal to</span> <span m="342500">5.</span> <span m="343750">You
  see</span> <span m="344245">this?</span> <span m="344740">Is it</span> <span m="345050">big</span>
  <span m="345537">enough?</span> <span m="348460">Shall I</span> <span m="348820">change</span>
  <span m="349070">it</span> <span m="349180">to</span> <span m="349350">a little</span>
  <span m="349560">bit</span> <span m="349700">bigger?</span></p><p><span m="351040">Anybody</span>
  <span m="351530">want</span> <span m="351820">it</span> <span m="351900">bigger?</span>
  <span m="353970">No?</span> <span m="354910">Good?</span> <span m="355170">OK.</span></p><p><span
  m="357050">What</span> <span m="357200">[INAUDIBLE]</span> <span m="357310">do</span>
  <span m="357570">you</span> <span m="357700">want?</span> <span m="359810">What
  one?</span> <span m="360778">Good,</span> <span m="362230">OK.</span></p><p><span
  m="364046">And</span> <span m="364500">what</span> <span m="364870">I</span> <span
  m="364960">want--</span> <span m="365380">how</span> <span m="365440">I</span> <span
  m="366140">discretize</span> <span m="366820">the</span> <span m="366920">time</span>
  <span m="367390">is</span> <span m="367790">t</span> <span m="368370">equal</span>
  <span m="368590">0</span> <span m="368740">dt</span> <span m="369590">t,</span>
  <span m="371430">all</span> <span m="371560">right?</span> <span m="373010">This</span>
  <span m="373200">is</span> <span m="373340">going</span> <span m="373490">to</span>
  <span m="373560">give</span> <span m="373780">me</span> <span m="373960">a</span>
  <span m="374050">t</span> <span m="374640">1</span> <span m="375000">by</span> <span
  m="375190">51</span> <span m="375830">double.</span> <span m="376330">So</span>
  <span m="376500">if</span> <span m="376630">I</span> <span m="376730">click</span>
  <span m="377090">on it,</span> <span m="377320">it</span> <span m="377580">is</span>
  <span m="377910">going</span> <span m="378090">to</span> <span m="378200">show</span>
  <span m="378530">that</span> <span m="379080">the</span> <span m="379210">first
  one</span> <span m="379490">is</span> <span m="379785">0,</span> <span m="380080">the</span>
  <span m="380170">second</span> <span m="380460">one</span> <span m="380600">is</span>
  <span m="380820">0.1,</span> <span m="381320">et</span> <span m="381790">cetera,
  et cetera.</span> <span m="382260">And</span> <span m="382390">the</span> <span
  m="382470">last</span> <span m="382730">one</span> <span m="383020">should</span>
  <span m="383230">be--</span> <span m="385970">whoops--</span> <span m="387850">is</span>
  <span m="388120">5,</span> <span m="389200">all</span> <span m="389380">right?</span></p><p><span
  m="390780">And</span> <span m="391000">now</span> <span m="391290">the</span> <span
  m="391370">function</span> <span m="391830">value</span> <span m="392410">f of</span>
  <span m="392790">t</span> <span m="393230">is</span> <span m="393490">equal</span>
  <span m="393860">to</span> <span m="394720">any</span> <span m="394940">set</span>
  <span m="395270">of</span> <span m="395380">lambda</span> <span m="396170">of</span>
  <span m="396330">equal</span> <span m="396600">to</span> <span m="396680">1,</span>
  <span m="397260">OK?</span> <span m="397660">Lambda</span> <span m="397930">equal
  to</span> <span m="398230">1.</span> <span m="399540">And</span> <span m="400060">then</span>
  <span m="400210">my</span> <span m="400380">function</span> <span m="400780">value</span>
  <span m="401330">is</span> <span m="401640">equal to</span> <span m="401920">exponential</span>
  <span m="402720">of</span> <span m="402840">minus</span> <span m="403370">lambda</span>
  <span m="403980">times</span> <span m="404442">t.</span> <span m="405830">So</span>
  <span m="406020">that</span> <span m="406260">way,</span> <span m="406530">I</span>
  <span m="406690">computed</span> <span m="407490">discretized</span> <span m="408230">version</span>
  <span m="408620">of</span> <span m="408750">the</span> <span m="408860">function</span>
  <span m="409752">f.</span></p><p><span m="411560">How</span> <span m="411830">would
  I show</span> <span m="412090">the</span> <span m="412170">function?</span> <span
  m="413850">I</span> <span m="413950">can</span> <span m="414160">go</span> <span
  m="414310">to</span> <span m="414450">plot</span> <span m="415860">and</span> <span
  m="416100">to</span> <span m="416170">do</span> <span m="416360">this</span> <span
  m="416570">plot.</span> <span m="417120">Like</span> <span m="417390">here,</span>
  <span m="417730">I''m just</span> <span m="417800">going to</span> <span m="417950">use</span>
  <span m="418336">the</span> <span m="419110">command</span> <span m="419460">line</span>
  <span m="419680">version</span> <span m="420135">to</span> <span m="420590">log</span>
  <span m="421045">t</span> <span m="421500">and</span> <span m="421955">f.</span>
  <span m="424230">Yeah,</span> <span m="424550">this</span> <span m="424770">gives</span>
  <span m="425030">us</span> <span m="425700">exactly</span> <span m="426200">the</span>
  <span m="426290">function</span> <span m="426760">we</span> <span m="426870">expect,</span>
  <span m="427820">right?</span> <span m="428200">Exponentially</span> <span m="429010">decaying</span>
  <span m="429960">function.</span></p><p><span m="432970">And</span> <span m="433500">I</span>
  <span m="433640">would</span> <span m="433850">actually</span> <span m="434230">also</span>
  <span m="434550">prefer</span> <span m="435310">to</span> <span m="435950">plot</span>
  <span m="436310">this</span> <span m="438220">and</span> <span m="438600">look</span>
  <span m="439010">at</span> <span m="439170">what</span> <span m="439550">kind</span>
  <span m="439770">of</span> <span m="439940">discretization</span> <span m="440430">it
  is.</span> <span m="441900">So if</span> <span m="442100">I</span> <span m="442270">plot</span>
  <span m="442530">this</span> <span m="442790">function</span> <span m="443240">with</span>
  <span m="443410">a</span> <span m="443590">dash</span> <span m="444080">and</span>
  <span m="444260">the</span> <span m="444410">o,</span> <span m="444860">it is</span>
  <span m="445140">going</span> <span m="445270">to</span> <span m="445330">display</span>
  <span m="445510">a</span> <span m="445955">circle</span> <span m="447290">at</span>
  <span m="447630">every</span> <span m="448560">discretized</span> <span m="449250">point</span>
  <span m="449560">so</span> <span m="450000">that</span> <span m="450200">we</span>
  <span m="450310">are</span> <span m="450400">going</span> <span m="450520">to</span>
  <span m="450640">see</span> <span m="450900">that</span> <span m="451910">this</span>
  <span m="452170">function</span> <span m="452590">is</span> <span m="453010">actually</span>
  <span m="453430">a</span> <span m="453850">discretized</span> <span m="454500">function.</span>
  <span m="454760">It</span> <span m="455140">is</span> <span m="455300">not</span>
  <span m="455850">a</span> <span m="455970">continuous.</span></p><p><span m="456880">In</span>
  <span m="457050">MATLAB,</span> <span m="458030">the</span> <span m="458390">plot</span>
  <span m="458670">is</span> <span m="458810">approximated</span> <span m="459640">by</span>
  <span m="460180">drawing</span> <span m="460680">a</span> <span m="460850">linear</span>
  <span m="461320">line,</span> <span m="461690">drawing a</span> <span m="462010">line,</span>
  <span m="462320">between</span> <span m="462798">these</span> <span m="463276">circles.</span>
  <span m="464710">But</span> <span m="464880">because</span> <span m="465380">delta</span>
  <span m="465540">t</span> <span m="465710">is</span> <span m="465970">small,</span>
  <span m="466280">1.8,</span> <span m="467670">it</span> <span m="467890">looks</span>
  <span m="468160">like</span> <span m="468860">a</span> <span m="469080">small</span>
  <span m="469230">function,</span> <span m="470980">all</span> <span m="471130">right?</span>
  <span m="472480">OK,</span> <span m="473960">let''s</span> <span m="474300">try</span>
  <span m="474600">another</span> <span m="474940">one.</span></p><p><span m="476600">So</span>
  <span m="476970">here--</span> <span m="478440">let''s</span> <span m="478920">see.</span>
  <span m="479080">How do</span> <span m="479445">I</span> <span m="479810">insert</span>
  <span m="479950">another?</span> <span m="481600">Each</span> <span m="481850">option</span>
  <span m="482305">insert</span> <span m="482760">[INAUDIBLE]</span> <span m="484430">insert.</span>
  <span m="486680">OK,</span> <span m="487700">so</span> <span m="488150">let''s try</span>
  <span m="488430">another</span> <span m="488760">function.</span> <span m="490536">We</span>
  <span m="491000">did</span> <span m="491370">df</span> <span m="492440">dt</span>
  <span m="492940">equal</span> <span m="493150">to</span> <span m="494010">minus</span>
  <span m="494270">lambda</span> <span m="494750">u.</span></p><p><span m="495530">How</span>
  <span m="495770">about</span> <span m="496080">minus</span> <span m="498950">lambda</span>
  <span m="499250">f?</span> <span m="499400">How</span> <span m="499680">about</span>
  <span m="499960">minus</span> <span m="500440">ft</span> <span m="501400">squared?</span>
  <span m="503630">Anybody</span> <span m="504010">know</span> <span m="504240">how</span>
  <span m="504440">to</span> <span m="504580">solve</span> <span m="504870">this</span>
  <span m="505070">ODE</span> <span m="506020">analytically?</span></p><p><span m="514299">Anybody</span>
  <span m="514630">who</span> <span m="514789">reviews</span> <span m="515710">ODE</span>
  <span m="516860">before</span> <span m="517169">this</span> <span m="517309">class</span>
  <span m="517714">where you are</span> <span m="518120">reading</span> <span m="518419">the</span>
  <span m="518549">readings?</span> <span m="519173">The</span> <span m="519636">original</span>
  <span m="520100">variables?</span> <span m="520536">Good,</span> <span m="521409">we</span>
  <span m="521940">are</span> <span m="522010">going</span> <span m="522130">to</span>
  <span m="522190">be</span> <span m="522280">dividing</span> <span m="523460">f</span>
  <span m="523809">square</span> <span m="524090">on</span> <span m="524230">each</span>
  <span m="524470">side,</span> <span m="524920">right?</span></p><p><span m="525240">So</span>
  <span m="525380">we</span> <span m="525550">have</span> <span m="525840">df</span>
  <span m="527010">over--</span> <span m="527660">not on</span> <span m="527910">this--</span>
  <span m="528930">f</span> <span m="529570">square</span> <span m="530220">equal</span>
  <span m="530600">to</span> <span m="530690">minus</span> <span m="531240">dt,</span>
  <span m="532770">right?</span> <span m="533740">We''re</span> <span m="533910">going</span>
  <span m="534030">to</span> <span m="534100">be</span> <span m="534210">integrating</span>
  <span m="534790">both</span> <span m="535040">sides.</span> <span m="536040">And</span>
  <span m="536270">on</span> <span m="536400">this</span> <span m="536620">side,</span>
  <span m="536900">we</span> <span m="537010">get</span> <span m="537260">minus</span>
  <span m="538060">f</span> <span m="538450">1</span> <span m="538690">over</span>
  <span m="538880">f</span> <span m="539220">plus</span> <span m="539720">an</span>
  <span m="540080">arbitrary</span> <span m="540460">constant</span> <span m="541220">equal</span>
  <span m="541650">to</span> <span m="542380">minus</span> <span m="542840">t,</span>
  <span m="543710">right?</span></p><p><span m="546800">So</span> <span m="547060">we</span>
  <span m="547230">are</span> <span m="547300">going</span> <span m="547420">to</span>
  <span m="547480">get</span> <span m="548240">f</span> <span m="548470">of</span>
  <span m="548640">t</span> <span m="551120">is</span> <span m="551550">going</span>
  <span m="551710">to</span> <span m="551780">be</span> <span m="551910">equal</span>
  <span m="552160">to</span> <span m="552270">1</span> <span m="552920">over--</span>
  <span m="554830">we</span> <span m="555020">have</span> <span m="555720">t--</span>
  <span m="557780">here</span> <span m="558100">is</span> <span m="558260">actually</span>
  <span m="558520">plus</span> <span m="558570">t,</span> <span m="559540">right?</span>
  <span m="563530">Agree?</span> <span m="565480">OK,</span> <span m="565750">in</span>
  <span m="565860">particular,</span> <span m="566500">if</span> <span m="566610">I</span>
  <span m="567510">set</span> <span m="567690">the</span> <span m="567780">same</span>
  <span m="568170">initial</span> <span m="568620">condition,</span> <span m="569180">which</span>
  <span m="569320">is</span> <span m="569490">f of</span> <span m="569920">0</span>
  <span m="570260">equal</span> <span m="570530">to</span> <span m="570620">1,</span>
  <span m="573800">then</span> <span m="574370">it</span> <span m="574540">determines</span>
  <span m="575110">my</span> <span m="575240">constant</span> <span m="575655">c</span>
  <span m="576070">and</span> <span m="576400">my</span> <span m="576660">f of</span>
  <span m="576960">t</span> <span m="577390">is</span> <span m="577660">equal</span>
  <span m="578000">to</span> <span m="578110">1</span> <span m="578540">over,</span>
  <span m="578940">what?</span></p><p><span m="581060">One</span> <span m="581360">over</span>
  <span m="581450">t,</span> <span m="582120">right?</span> <span m="583420">OK,</span>
  <span m="583770">so</span> <span m="583860">let''s</span> <span m="585900">Test</span>
  <span m="587080">this</span> <span m="587280">function.</span> <span m="589270">And</span>
  <span m="589790">it</span> <span m="589940">is</span> <span m="590070">going</span>
  <span m="590190">to</span> <span m="590250">be</span> <span m="590360">useful</span>
  <span m="590580">later</span> <span m="590800">on,</span> <span m="591153">right?</span></p><p><span
  m="591860">So</span> <span m="592210">my</span> <span m="592530">f2</span> <span
  m="592810">is</span> <span m="593040">going</span> <span m="593200">to</span> <span
  m="593260">be</span> <span m="593360">1</span> <span m="593880">over</span> <span
  m="594296">t.</span> <span m="595130">OK,</span> <span m="595580">I''m</span> <span
  m="595740">going</span> <span m="595910">to</span> <span m="595990">be--</span>
  <span m="596540">let</span> <span m="596710">me</span> <span m="596800">hold</span>
  <span m="597140">on</span> <span m="598300">and</span> <span m="598730">plot</span>
  <span m="599490">t</span> <span m="601020">f2</span> <span m="604823">[INAUDIBLE].</span>
  <span m="607170">Oh,</span> <span m="607840">OK.</span></p><p><span m="608960">That''s</span>
  <span m="609200">one,</span> <span m="609440">right?</span> <span m="611020">I''m</span>
  <span m="611180">going</span> <span m="611330">to</span> <span m="611410">have</span>
  <span m="611840">serious</span> <span m="612190">trouble</span> <span m="613540">if</span>
  <span m="613740">I</span> <span m="613860">do</span> <span m="614080">this.</span>
  <span m="614830">So</span> <span m="615290">let</span> <span m="615540">me</span>
  <span m="616704">just do</span> <span m="617146">this</span> <span m="617590">again--</span>
  <span m="618630">equal</span> <span m="618710">to</span> <span m="618980">1</span>
  <span m="619260">divided</span> <span m="619620">by</span> <span m="619960">t</span>
  <span m="620300">plus</span> <span m="620550">1.</span></p><p><span m="621460">Yes,</span>
  <span m="621740">thank</span> <span m="621940">you</span> <span m="622030">for</span>
  <span m="622210">paying</span> <span m="622460">attention,</span> <span m="624212">OK?</span>
  <span m="625090">And</span> <span m="627400">plot</span> <span m="627830">t</span>
  <span m="628740">f2.</span> <span m="630350">Let</span> <span m="630580">me</span>
  <span m="630710">do</span> <span m="632880">dash dash</span> <span m="633652">and</span>
  <span m="634040">s.</span> <span m="634540">So,</span> <span m="634730">dash</span>
  <span m="634980">dash</span> <span m="635360">means</span> <span m="635690">the</span>
  <span m="636800">[INAUDIBLE]</span> <span m="637210">line</span> <span m="638060">and</span>
  <span m="638310">s</span> <span m="638600">means</span> <span m="638960">squares.</span></p><p><span
  m="639980">So we</span> <span m="640160">are</span> <span m="640240">going</span>
  <span m="640520">to</span> <span m="640940">see</span> <span m="641340">how</span>
  <span m="641520">different</span> <span m="642310">these</span> <span m="642550">are</span>
  <span m="642670">going</span> <span m="642790">to</span> <span m="642870">be.</span>
  <span m="643690">So,</span> <span m="643800">one</span> <span m="644080">function</span>
  <span m="644925">is</span> <span m="645370">the</span> <span m="645490">solution</span>
  <span m="645990">of</span> <span m="646450">df</span> <span m="646780">dt</span>
  <span m="647170">equal</span> <span m="647450">to</span> <span m="647730">minus</span>
  <span m="648180">f.</span> <span m="649180">The</span> <span m="649330">other</span>
  <span m="649590">is</span> <span m="649960">df</span> <span m="650330">dt equal</span>
  <span m="650710">to</span> <span m="651040">minus</span> <span m="651180">f</span>
  <span m="651450">square,</span> <span m="652346">right?</span></p><p><span m="654140">OK,</span>
  <span m="655130">so</span> <span m="655340">here</span> <span m="655710">is</span>
  <span m="656010">discretization</span> <span m="657090">function.</span> <span m="657620">But</span>
  <span m="657810">like,</span> <span m="658070">this</span> <span m="658240">is</span>
  <span m="658460">nothing</span> <span m="658870">new,</span> <span m="659343">right?</span>
  <span m="660290">We</span> <span m="660350">all</span> <span m="660530">know</span>
  <span m="660730">this.</span></p><p><span m="661860">What''s</span> <span m="662120">new</span>
  <span m="662620">is</span> <span m="663110">how</span> <span m="663390">do</span>
  <span m="663520">we</span> <span m="663760">approximate</span> <span m="664710">the</span>
  <span m="664960">derivative</span> <span m="666080">of</span> <span m="666280">these</span>
  <span m="666774">functions.</span> <span m="668750">Because</span> <span m="669190">if</span>
  <span m="669470">we</span> <span m="669610">can</span> <span m="669870">approximate</span>
  <span m="670680">the</span> <span m="670850">derivative</span> <span m="671370">of</span>
  <span m="671780">these</span> <span m="671940">function,</span> <span m="674150">then</span>
  <span m="674480">we</span> <span m="674600">can</span> <span m="674830">start</span>
  <span m="675040">to</span> <span m="675130">solve</span> <span m="675610">these</span>
  <span m="675860">ODEs</span> <span m="676480">numerically,</span> <span m="677930">right?</span>
  <span m="678350">These</span> <span m="678610">two</span> <span m="678820">ODEs</span>
  <span m="679520">I</span> <span m="679670">just</span> <span m="680060">showed</span>
  <span m="680270">you</span> <span m="681190">have</span> <span m="682090">exact</span>
  <span m="682550">solutions.</span></p><p><span m="684530">But the</span> <span m="684590">reason</span>
  <span m="685000">we</span> <span m="685120">take</span> <span m="685350">this</span>
  <span m="685510">class</span> <span m="685930">is</span> <span m="686060">because</span>
  <span m="686440">we</span> <span m="686570">want</span> <span m="686750">to</span>
  <span m="686930">solve</span> <span m="687340">ODEs</span> <span m="688780">that</span>
  <span m="689040">do</span> <span m="689160">not</span> <span m="689500">have</span>
  <span m="689950">analytical</span> <span m="690606">solutions.</span> <span m="693090">If</span>
  <span m="693330">we</span> <span m="693510">have</span> <span m="693690">a</span>
  <span m="693810">way</span> <span m="694050">to</span> <span m="694200">approximate</span>
  <span m="695070">the</span> <span m="695190">derivative</span> <span m="695780">of</span>
  <span m="696110">any</span> <span m="696370">function</span> <span m="696880">we</span>
  <span m="696940">want,</span> <span m="697800">then</span> <span m="698640">I''m</span>
  <span m="698770">going</span> <span m="698900">to</span> <span m="698980">show</span>
  <span m="699230">you</span> <span m="699360">that</span> <span m="699620">we</span>
  <span m="699740">can</span> <span m="699950">solve</span> <span m="701010">any</span>
  <span m="701340">differential</span> <span m="701700">equation</span> <span m="701800">we</span>
  <span m="702245">want.</span> <span m="703580">OK,</span> <span m="703890">so</span>
  <span m="704300">approximated</span> <span m="705020">derivative--</span> <span
  m="706560">not</span> <span m="707230">from</span> <span m="707880">analytical</span>
  <span m="708500">function,</span> <span m="709330">but</span> <span m="709580">from
  a</span> <span m="709720">function</span> <span m="710210">discretized</span> <span
  m="711850">like</span> <span m="712180">what</span> <span m="712430">we</span> <span
  m="712680">just</span> <span m="712880">had.</span></p><p><span m="713710">Right,</span>
  <span m="713960">so</span> <span m="714510">pretend</span> <span m="715930">we</span>
  <span m="716300">have</span> <span m="716600">MATLAB.</span> <span m="717120">We</span>
  <span m="717280">have</span> <span m="717530">this</span> <span m="717760">app.</span>
  <span m="718440">We</span> <span m="718600">have</span> <span m="718990">f2</span>
  <span m="719190">but</span> <span m="719370">we</span> <span m="719490">don''t</span>
  <span m="719840">know</span> <span m="720110">where</span> <span m="720420">they''re</span>
  <span m="720640">computed</span> <span m="721120">from.</span> <span m="721510">They</span>
  <span m="721670">are</span> <span m="721770">just</span> <span m="722120">some</span>
  <span m="722320">kind</span> <span m="722800">of</span> <span m="722920">discretized</span>
  <span m="723460">function.</span> <span m="724570">Now,</span> <span m="724980">how</span>
  <span m="725250">do</span> <span m="725380">we</span> <span m="725640">compute</span>
  <span m="726090">the</span> <span m="726340">derivatives?</span></p><p><span m="729830">OK,</span>
  <span m="730350">any</span> <span m="730570">ideas?</span> <span m="731830">Any</span>
  <span m="732120">ideas?</span> <span m="733310">Any</span> <span m="733540">ideas?</span></p><p><span
  m="734800">Any</span> <span m="735020">ideas?</span> <span m="736290">Any</span>
  <span m="736480">ideas?</span> <span m="736810">The</span> <span m="736910">linear</span>
  <span m="737260">definition</span> <span m="737720">of</span> <span m="737840">derivative--</span>
  <span m="738370">what</span> <span m="738560">is</span> <span m="738800">the</span>
  <span m="738870">linear</span> <span m="739580">definition</span> <span m="740080">of</span>
  <span m="740210">derivative?</span> <span m="755401">f2</span> <span m="756375">minus</span>
  <span m="757350">f1</span> <span m="757690">over</span> <span m="758020">f1--</span>
  <span m="761570">There</span> <span m="761740">is a</span> <span m="762163">[INAUDIBLE].</span></p><p><span
  m="763010">OK,</span> <span m="763410">you</span> <span m="764500">did,</span> <span
  m="765500">like,</span> <span m="765860">partial</span> <span m="766370">t''s.</span>
  <span m="766620">Anybody</span> <span m="767010">wants to</span> <span m="767496">[INAUDIBLE]</span>
  <span m="767982">what''s your name?</span> <span m="768468">[INAUDIBLE]</span> <span
  m="770412">OK,</span> <span m="770900">anybody</span> <span m="771210">wants</span>
  <span m="771420">to</span> <span m="771610">complete</span> <span m="772290">this</span>
  <span m="772520">[INAUDIBLE]</span> <span m="772690">answer</span> <span m="773644">by</span>
  <span m="774600">maybe</span> <span m="774990">changing</span> <span m="775320">something?</span></p><p><span
  m="796420">[INAUDIBLE]</span> <span m="796840">is</span> <span m="797110">f</span>
  <span m="797310">of</span> <span m="797570">t</span> <span m="797930">plus</span>
  <span m="798340">delta</span> <span m="798815">t</span> <span m="800240">minus</span>
  <span m="800660">f</span> <span m="800985">of t</span> <span m="801310">divided</span>
  <span m="801760">by</span> <span m="802600">delta</span> <span m="803072">t,</span>
  <span m="804016">right?</span> <span m="807800">And</span> <span m="808440">this</span>
  <span m="808790">is,</span> <span m="809070">of</span> <span m="809260">course,</span>
  <span m="809500">the</span> <span m="809620">definition</span> <span m="810170">of</span>
  <span m="810270">exact</span> <span m="810460">derivatives.</span> <span m="812620">But</span>
  <span m="813020">in</span> <span m="813180">the</span> <span m="813260">computer,</span>
  <span m="814600">we</span> <span m="814740">cannot</span> <span m="815250">take</span>
  <span m="815550">delta</span> <span m="815700">t and</span> <span m="816150">go</span>
  <span m="816470">to</span> <span m="816620">zero,</span> <span m="817086">right?</span>
  <span m="818020">That</span> <span m="818350">would</span> <span m="818510">again</span>
  <span m="818890">require</span> <span m="819260">infinite</span> <span m="819750">memory</span>
  <span m="820055">and</span> <span m="820360">infinite</span> <span m="820840">computation</span>
  <span m="821320">time.</span></p><p><span m="822760">We</span> <span m="822950">have</span>
  <span m="823140">to</span> <span m="823280">approximate</span> <span m="824110">it.</span>
  <span m="825530">We</span> <span m="825690">have</span> <span m="825850">to</span>
  <span m="825950">be</span> <span m="826100">satisfied</span> <span m="826740">with</span>
  <span m="827125">delta</span> <span m="827510">t</span> <span m="828460">being</span>
  <span m="828930">small</span> <span m="829170">enough.</span> <span m="830800">OK,</span>
  <span m="831400">so</span> <span m="831800">here,</span> <span m="832150">we</span>
  <span m="832320">have</span> <span m="832470">a</span> <span m="832540">function</span>
  <span m="833180">like</span> <span m="833480">this.</span></p><p><span m="834040">We</span>
  <span m="834200">have</span> <span m="834320">a</span> <span m="834380">function</span>
  <span m="834810">like</span> <span m="835030">this.</span> <span m="835840">Each--</span>
  <span m="836930">let''s</span> <span m="837110">look</span> <span m="837340">at</span>
  <span m="839080">this</span> <span m="839300">one,</span> <span m="840150">the</span>
  <span m="840220">one</span> <span m="840410">with</span> <span m="840650">squares.</span>
  <span m="841340">These</span> <span m="841580">two</span> <span m="841760">squares</span>
  <span m="842150">is</span> <span m="842380">based</span> <span m="842710">over</span>
  <span m="843010">delta</span> <span m="843160">t</span> <span m="844660">in</span>
  <span m="844840">the</span> <span m="845010">horizontal</span> <span m="845360">side.</span></p><p><span
  m="847360">On</span> <span m="847580">the</span> <span m="847660">vertical</span>
  <span m="848140">side,</span> <span m="848870">they</span> <span m="849300">are</span>
  <span m="849500">spaced</span> <span m="849800">by</span> <span m="850455">f2</span>
  <span m="851090">minus</span> <span m="851600">f1,</span> <span m="852300">right?</span>
  <span m="854750">So</span> <span m="854920">if</span> <span m="855140">we</span>
  <span m="855290">take</span> <span m="856310">the</span> <span m="857400">vertical</span>
  <span m="857950">distance,</span> <span m="858430">divide</span> <span m="858790">by</span>
  <span m="858940">the</span> <span m="859030">horizontal</span> <span m="859530">distance,</span>
  <span m="860430">that</span> <span m="860790">[INAUDIBLE]</span> <span m="861140">approximation</span>
  <span m="863310">of</span> <span m="863910">this,</span> <span m="865190">right?</span>
  <span m="865700">f</span> <span m="865990">of</span> <span m="866250">t</span> <span
  m="867190">plus</span> <span m="867330">delta</span> <span m="867870">t</span> <span
  m="868540">minus</span> <span m="868700">of of</span> <span m="869060">t</span>
  <span m="870230">over</span> <span m="870770">delta</span> <span m="871030">t,</span>
  <span m="874450">all</span> <span m="874570">right?</span></p><p><span m="876450">So</span>
  <span m="876620">that''s</span> <span m="877400">a</span> <span m="877520">good</span>
  <span m="877850">way</span> <span m="878210">of</span> <span m="878680">approximating</span>
  <span m="879460">the</span> <span m="879610">derivative.</span> <span m="880600">Now,</span>
  <span m="880970">anybody</span> <span m="881430">who</span> <span m="881630">can</span>
  <span m="882390">transform</span> <span m="883110">this</span> <span m="883310">formula</span>
  <span m="883820">into</span> <span m="884070">MATLAB?</span> <span m="888110">I</span>
  <span m="888350">have</span> <span m="888880">two</span> <span m="889060">functions,</span>
  <span m="889560">f</span> <span m="890040">and</span> <span m="890300">f2,</span>
  <span m="890510">in</span> <span m="890660">MATLAB.</span> <span m="891880">How</span>
  <span m="892090">do</span> <span m="892180">you</span> <span m="892310">guys</span>
  <span m="893210">transform</span> <span m="893790">this</span> <span m="893990">formula,</span>
  <span m="894460">which</span> <span m="894670">is--</span> <span m="894890">this</span>
  <span m="895180">is</span> <span m="895340">like</span> <span m="895550">one</span>
  <span m="895750">of</span> <span m="895840">the</span> <span m="895910">most</span>
  <span m="896140">important</span> <span m="896650">skills</span> <span m="896900">you</span>
  <span m="896980">are</span> <span m="897070">going to</span> <span m="897130">learn</span>
  <span m="897480">in</span> <span m="897620">this</span> <span m="897900">class--</span>
  <span m="898600">that</span> <span m="898950">is,</span> <span m="899410">how</span>
  <span m="899930">to</span> <span m="901410">incorporate,</span> <span m="902110">how</span>
  <span m="902350">to</span> <span m="902510">translate,</span> <span m="903300">a</span>
  <span m="903390">mathematical</span> <span m="904150">formula</span> <span m="904840">you</span>
  <span m="904990">can</span> <span m="905180">write</span> <span m="905430">down</span>
  <span m="905760">on</span> <span m="905860">a</span> <span m="905960">piece</span>
  <span m="906050">of</span> <span m="906160">paper</span> <span m="906540">into</span>
  <span m="907560">a</span> <span m="907710">code</span> <span m="908150">like</span>
  <span m="908420">MATLAB.</span> <span m="912040">[INAUDIBLE]</span> <span m="912330">see</span>
  <span m="912480">[INAUDIBLE]</span> <span m="913050">is</span> <span m="913160">that</span>
  <span m="913310">going</span> <span m="913430">to</span> <span m="913630">keep</span>
  <span m="913840">me</span> <span m="914160">a</span> <span m="914370">code</span>
  <span m="914862">I</span> <span m="915354">can type</span> <span m="915846">into</span>
  <span m="916340">MATLAB.</span></p><p><span m="917450">Like,</span> <span m="918420">here,</span>
  <span m="918630">I''m</span> <span m="918820">writing</span> <span m="919295">[INAUDIBLE]</span>
  <span m="919770">type.</span> <span m="919970">Please tell me</span> <span m="920400">what
  to</span> <span m="920830">type.</span> <span m="936710">Yeah,</span> <span m="937200">find</span>
  <span m="937450">the</span> <span m="937570">function--</span> <span m="938840">the</span>
  <span m="939010">difference</span> <span m="939350">between</span> <span m="939778">functions</span>
  <span m="940206">between</span> <span m="940634">one point</span> <span m="941062">and
  other</span> <span m="941490">points.</span> <span m="948883">Let</span> <span m="949356">me</span>
  <span m="949829">do a</span> <span m="950302">[INAUDIBLE].</span></p><p><span m="955980">Yes,</span>
  <span m="956370">the</span> <span m="956770">difference</span> <span m="957330">and</span>
  <span m="957580">the</span> <span m="957650">approximate</span> <span m="958380">derivative--</span>
  <span m="959570">OK.</span> <span m="962940">OK,</span> <span m="963540">you</span>
  <span m="963690">guys</span> <span m="963970">are</span> <span m="964080">good.</span>
  <span m="965690">So</span> <span m="965850">OK,</span> <span m="966130">so</span>
  <span m="966480">I''m</span> <span m="966660">going</span> <span m="966810">to</span>
  <span m="966890">do</span> <span m="967050">something</span> <span m="967400">new.</span>
  <span m="967600">I''m</span> <span m="968068">going to use</span> <span m="968536">if.</span></p><p><span
  m="969940">I''m</span> <span m="970410">going</span> <span m="970540">to</span>
  <span m="970600">use</span> <span m="971010">if</span> <span m="971260">of</span>
  <span m="971590">f.</span> <span m="972180">What</span> <span m="972420">is</span>
  <span m="972560">that</span> <span m="972700">going</span> <span m="972820">to</span>
  <span m="972880">give</span> <span m="973130">me?</span> <span m="973990">So</span>
  <span m="974150">let</span> <span m="974310">me</span> <span m="974420">just</span>
  <span m="974640">say</span> <span m="974830">df</span> <span m="975480">equal</span>
  <span m="975740">to</span> <span m="976080">diff</span> <span m="976320">f,</span>
  <span m="977000">OK?</span></p><p><span m="978090">And</span> <span m="978560">let</span>
  <span m="978790">me</span> <span m="979370">double</span> <span m="979750">click</span>
  <span m="980060">on</span> <span m="980230">df</span> <span m="980530">to</span>
  <span m="980670">show</span> <span m="980910">me</span> <span m="981060">what</span>
  <span m="981280">this</span> <span m="981500">is.</span> <span m="983150">And</span>
  <span m="983750">I''m</span> <span m="983930">going</span> <span m="984060">to</span>
  <span m="984200">see,</span> <span m="984550">compare</span> <span m="984960">this</span>
  <span m="985160">with</span> <span m="985440">f--</span> <span m="987200">f</span>
  <span m="987530">and</span> <span m="987700">df.</span> <span m="988600">So</span>
  <span m="988730">what</span> <span m="988940">I</span> <span m="989020">can</span>
  <span m="989210">see</span> <span m="989400">is</span> <span m="989510">that</span>
  <span m="989720">df</span> <span m="990220">gives</span> <span m="990530">me</span>
  <span m="991280">this</span> <span m="991810">minus</span> <span m="992270">this,</span>
  <span m="993070">right?</span></p><p><span m="994000">The</span> <span m="994140">first</span>
  <span m="994450">element</span> <span m="994820">of</span> <span m="994930">df</span>
  <span m="995380">is</span> <span m="995580">the</span> <span m="995830">second</span>
  <span m="996040">element</span> <span m="996170">of</span> <span m="996310">f</span>
  <span m="996810">minus</span> <span m="997020">the first</span> <span m="997240">element--</span>
  <span m="999710">sorry,</span> <span m="1000300">this</span> <span m="1000530">minus</span>
  <span m="1000880">this.</span> <span m="1001710">Or</span> <span m="1002310">what</span>
  <span m="1002550">I</span> <span m="1002630">can</span> <span m="1002870">do</span>
  <span m="1004620">is</span> <span m="1005520">the</span> <span m="1005640">same</span>
  <span m="1005970">thing</span> <span m="1006370">can</span> <span m="1006550">be</span>
  <span m="1006650">computed</span> <span m="1007180">by</span> <span m="1007530">f</span>
  <span m="1008790">of</span> <span m="1009060">2</span> <span m="1009345">to</span>
  <span m="1009630">end.</span> <span m="1009905">Do</span> <span m="1010180">you</span>
  <span m="1010300">know</span> <span m="1010470">what</span> <span m="1010630">this</span>
  <span m="1011400">means?</span> <span m="1012150">Exactly--</span> <span m="1013280">it</span>
  <span m="1013460">gives</span> <span m="1013740">me</span> <span m="1013900">all</span>
  <span m="1014060">the</span> <span m="1014160">angles</span> <span m="1014460">from</span>
  <span m="1014690">the</span> <span m="1014770">second</span> <span m="1015130">to</span>
  <span m="1015230">the</span> <span m="1015340">end</span> <span m="1015810">minus</span>
  <span m="1016290">f1,</span> <span m="1016680">2,</span> <span m="1017380">and</span>
  <span m="1017690">minus</span> <span m="1018040">1.</span></p><p><span m="1018380">What</span>
  <span m="1018590">will this</span> <span m="1018700">give me?</span> <span m="1022120">The</span>
  <span m="1022290">first</span> <span m="1022880">to</span> <span m="1023000">the</span>
  <span m="1023110">second</span> <span m="1023500">last--</span> <span m="1023930">so</span>
  <span m="1024109">this</span> <span m="1024560">gets</span> <span m="1024810">me</span>
  <span m="1025339">exactly</span> <span m="1025920">the</span> <span m="1026040">same</span>
  <span m="1026270">answer,</span> <span m="1027250">right?</span> <span m="1028500">And</span>
  <span m="1028810">of</span> <span m="1028940">course,</span> <span m="1029190">I</span>
  <span m="1029290">can</span> <span m="1029480">just</span> <span m="1029700">do</span>
  <span m="1029859">this</span> <span m="1031380">divided</span> <span m="1032040">by</span>
  <span m="1033750">et,</span> <span m="1035430">all</span> <span m="1035599">right?</span></p><p><span
  m="1037680">And</span> <span m="1040329">so</span> <span m="1040599">this</span>
  <span m="1041471">df</span> <span m="1041907">dt.</span> <span m="1042343">This</span>
  <span m="1042780">is</span> <span m="1042950">an</span> <span m="1043130">approximation</span>
  <span m="1044190">of</span> <span m="1044400">the</span> <span m="1044560">derivative.</span>
  <span m="1048060">OK,</span> <span m="1049490">and</span> <span m="1050100">this</span>
  <span m="1050390">is</span> <span m="1050720">an</span> <span m="1050910">approximation</span>
  <span m="1051740">of</span> <span m="1051880">the</span> <span m="1051960">derivative</span>
  <span m="1052780">at</span> <span m="1053530">which</span> <span m="1053870">point,</span>
  <span m="1054350">if</span> <span m="1055730">I</span> <span m="1055890">speak</span>
  <span m="1056290">to</span> <span m="1056770">this</span> <span m="1057270">formula</span>
  <span m="1063790">and</span> <span m="1063920">the</span> <span m="1064050">discrete</span>
  <span m="1064350">time</span> <span m="1064420">instances</span> <span m="1064590">instances,</span>
  <span m="1065280">but</span> <span m="1065490">like</span> <span m="1066190">[INAUDIBLE].</span>
  <span m="1066840">So</span> <span m="1067210">if</span> <span m="1068120">look</span>
  <span m="1068575">at</span> <span m="1070450">length</span> <span m="1071080">of</span>
  <span m="1071830">df</span> <span m="1072060">dt--</span></p><p><span m="1072820">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="1074920">PROFESSOR: Yes,</span> <span m="1075750">this</span>
  <span m="1076130">is</span> <span m="1076300">an</span> <span m="1076370">approximation</span>
  <span m="1077130">to</span> <span m="1077220">the</span> <span m="1077440">derivative</span>
  <span m="1077910">from</span> <span m="1078220">0</span> <span m="1078960">to</span>
  <span m="1079150">t</span> <span m="1079520">minus</span> <span m="1079890">delta</span>
  <span m="1080267">t,</span> <span m="1081400">right?</span> <span m="1081660">Because</span>
  <span m="1082630">here,</span> <span m="1082990">I''m</span> <span m="1083270">taking</span>
  <span m="1083690">the</span> <span m="1083790">difference</span> <span m="1084340">between</span>
  <span m="1084610">t</span> <span m="1084960">plus</span> <span m="1085410">delta</span>
  <span m="1085600">t,</span> <span m="1086400">which</span> <span m="1086780">goes</span>
  <span m="1087010">all</span> <span m="1087190">the</span> <span m="1087270">way</span>
  <span m="1087430">to</span> <span m="1087510">big</span> <span m="1087790">t,</span>
  <span m="1088360">minus</span> <span m="1088830">ft,</span> <span m="1089320">which</span>
  <span m="1089580">actually</span> <span m="1089910">doesn''t</span> <span m="1090290">go
  all</span> <span m="1090750">the way</span> <span m="1091190">to big</span> <span
  m="1091630">t,</span> <span m="1092070">right?</span> <span m="1092350">So</span>
  <span m="1092620">I</span> <span m="1092810">have</span> <span m="1093280">the</span>
  <span m="1093370">derivative</span> <span m="1094510">from</span> <span m="1094730">0</span>
  <span m="1095160">all</span> <span m="1095380">the</span> <span m="1095440">way</span>
  <span m="1095810">to</span> <span m="1096170">big t</span> <span m="1096600">minus</span>
  <span m="1096700">delta</span> <span m="1097110">t.</span> <span m="1097450">I</span>
  <span m="1097640">don''t</span> <span m="1097980">have</span> <span m="1098210">the</span>
  <span m="1098290">derivative</span> <span m="1098830">of</span> <span m="1098980">the</span>
  <span m="1099060">last</span> <span m="1099350">one</span> <span m="1099910">because</span>
  <span m="1100250">at</span> <span m="1100370">the</span> <span m="1100450">last</span>
  <span m="1100690">one,</span> <span m="1100880">I</span> <span m="1100980">do</span>
  <span m="1101170">not</span> <span m="1101450">have</span> <span m="1101912">f of</span>
  <span m="1102374">t plus</span> <span m="1102836">delta t.</span></p><p><span m="1106070">OK,</span>
  <span m="1107110">now</span> <span m="1107430">let</span> <span m="1107620">me</span>
  <span m="1108040">plot--</span> <span m="1111896">let me</span> <span m="1112370">make</span>
  <span m="1112650">another</span> <span m="1113040">figure.</span> <span m="1114890">I''m</span>
  <span m="1115080">going</span> <span m="1115180">to</span> <span m="1115370">plot</span>
  <span m="1116330">t1</span> <span m="1117280">1</span> <span m="1117630">to</span>
  <span m="1117760">n</span> <span m="1117980">minus</span> <span m="1118300">1</span>
  <span m="1118540">because</span> <span m="1118830">I</span> <span m="1118910">don''t</span>
  <span m="1119180">have</span> <span m="1119570">the</span> <span m="1119960">derivative</span>
  <span m="1120550">at</span> <span m="1120680">the</span> <span m="1120750">very</span>
  <span m="1121080">end</span> <span m="1121440">as</span> <span m="1121930">df</span>
  <span m="1122420">dt.</span> <span m="1124870">I''m</span> <span m="1125050">going
  to</span> <span m="1125190">plot</span> <span m="1125630">them</span> <span m="1126010">using</span>
  <span m="1126450">circles.</span> <span m="1129175">And</span> <span m="1131450">it''s</span>
  <span m="1131720">the</span> <span m="1131990">derivative--</span> <span m="1133010">yeah,</span>
  <span m="1133250">this</span> <span m="1133440">is</span> <span m="1133530">the</span>
  <span m="1133620">derivative.</span></p><p><span m="1134190">It</span> <span m="1134330">goes</span>
  <span m="1134610">all</span> <span m="1134800">the</span> <span m="1134890">way</span>
  <span m="1135450">to</span> <span m="1135600">close</span> <span m="1136070">minus</span>
  <span m="1136410">1</span> <span m="1137228">to</span> <span m="1137686">0.</span>
  <span m="1139060">And</span> <span m="1139140">you</span> <span m="1139240">can</span>
  <span m="1139470">see</span> <span m="1140770">it</span> <span m="1140960">is</span>
  <span m="1141190">roughly</span> <span m="1141740">an</span> <span m="1141950">approximation</span>
  <span m="1143170">of</span> <span m="1143420">the</span> <span m="1143650">slope</span>
  <span m="1144630">of</span> <span m="1144840">the</span> <span m="1144920">circle</span>
  <span m="1145430">line,</span> <span m="1146340">right?</span> <span m="1148380">The</span>
  <span m="1148500">slope</span> <span m="1148870">is</span> <span m="1149030">negative.</span>
  <span m="1149640">Therefore,</span> <span m="1149920">the</span> <span m="1150080">derivative</span>
  <span m="1150542">is</span> <span m="1151004">negative.</span></p><p><span m="1153320">Let''s</span>
  <span m="1153550">compare</span> <span m="1154080">this</span> <span m="1154740">against</span>
  <span m="1156010">the</span> <span m="1156150">real</span> <span m="1156490">derivative.</span>
  <span m="1158310">Now,</span> <span m="1158510">what</span> <span m="1158680">is</span>
  <span m="1158820">the</span> <span m="1158950">real</span> <span m="1159330">derivative</span>
  <span m="1160350">of</span> <span m="1160540">this</span> <span m="1160650">function?</span>
  <span m="1171540">The</span> <span m="1171780">real</span> <span m="1172200">derivative</span>
  <span m="1172780">of</span> <span m="1172930">this</span> <span m="1173120">function</span>
  <span m="1174930">if</span> <span m="1175200">f of</span> <span m="1175520">t</span>
  <span m="1175970">is</span> <span m="1176240">equal</span> <span m="1176490">to</span>
  <span m="1176570">minus--</span> <span m="1177420">e</span> <span m="1177570">to</span>
  <span m="1177690">the</span> <span m="1177780">minus</span> <span m="1178180">t,</span>
  <span m="1180710">df</span> <span m="1180820">dt</span> <span m="1181155">is</span>
  <span m="1181490">just</span> <span m="1181720">equal</span> <span m="1181975">to</span>
  <span m="1182230">negative</span> <span m="1182600">of</span> <span m="1183070">e</span>
  <span m="1183340">to the</span> <span m="1183420">minus</span> <span m="1183720">t,</span>
  <span m="1184410">right?</span></p><p><span m="1185590">OK,</span> <span m="1185920">so</span>
  <span m="1186090">let''s</span> <span m="1187640">take</span> <span m="1187940">this</span>
  <span m="1188370">bigger</span> <span m="1188690">two</span> <span m="1189250">and</span>
  <span m="1189730">hold</span> <span m="1190140">on.</span> <span m="1191040">And</span>
  <span m="1191310">the</span> <span m="1191380">plot</span> <span m="1191830">t</span>
  <span m="1193050">exponential</span> <span m="1193820">of</span> <span m="1193980">minus</span>
  <span m="1194350">t</span> <span m="1194840">negative--</span> <span m="1196142">let''s</span>
  <span m="1196574">plot</span> <span m="1197006">it using</span> <span m="1197440">black,</span>
  <span m="1198388">[INAUDIBLE]</span> <span m="1198862">black.</span> <span m="1201710">OK,</span>
  <span m="1202500">we</span> <span m="1202660">see</span> <span m="1203090">we</span>
  <span m="1203390">had</span> <span m="1203610">a</span> <span m="1203900">pretty</span>
  <span m="1204120">good</span> <span m="1204340">approximation</span> <span m="1205120">of</span>
  <span m="1205250">the</span> <span m="1205760">real</span> <span m="1206140">derivative.</span></p><p><span
  m="1206900">We</span> <span m="1207050">can</span> <span m="1207220">also</span>
  <span m="1207540">see</span> <span m="1207780">that</span> <span m="1208050">it</span>
  <span m="1208200">is</span> <span m="1208430">not</span> <span m="1209190">exact,</span>
  <span m="1210860">right?</span> <span m="1212084">So</span> <span m="1212506">if
  the</span> <span m="1212928">black</span> <span m="1213350">line</span> <span m="1213510">goes</span>
  <span m="1213800">right</span> <span m="1214090">through</span> <span m="1214370">the</span>
  <span m="1214752">center of the</span> <span m="1215134">circle,</span> <span m="1215516">then</span>
  <span m="1215900">I</span> <span m="1216150">have</span> <span m="1216460">a</span>
  <span m="1216710">very</span> <span m="1216960">good</span> <span m="1217190">approximation.</span>
  <span m="1217540">But,</span> <span m="1217890">like,</span> <span m="1218390">[INAUDIBLE].</span>
  <span m="1224390">All right,</span> <span m="1225390">so</span> <span m="1225820">we</span>
  <span m="1225970">can</span> <span m="1226160">see</span> <span m="1226360">we</span>
  <span m="1226640">do</span> <span m="1227083">have</span> <span m="1227969">some</span>
  <span m="1229300">approximation</span> <span m="1230150">error,</span> <span m="1232140">which</span>
  <span m="1232550">in</span> <span m="1232690">this</span> <span m="1232840">case,</span>
  <span m="1233090">we</span> <span m="1233220">call</span> <span m="1233600">truncation</span>
  <span m="1234076">error.</span></p><p><span m="1235980">OK,</span> <span m="1236290">so</span>
  <span m="1236500">this,</span> <span m="1237450">how</span> <span m="1237670">big</span>
  <span m="1238030">the</span> <span m="1238130">truncation</span> <span m="1238650">error</span>
  <span m="1238940">is,</span> <span m="1239600">is</span> <span m="1240840">the</span>
  <span m="1240980">real</span> <span m="1241410">meat</span> <span m="1242140">of</span>
  <span m="1242900">this</span> <span m="1243327">lecture,</span> <span m="1244610">OK?</span>
  <span m="1245250">Truncation</span> <span m="1245590">error.</span> <span m="1246690">And</span>
  <span m="1246900">here,</span> <span m="1247210">we</span> <span m="1247450">start</span>
  <span m="1248040">the</span> <span m="1248230">Taylor</span> <span m="1249120">series</span>
  <span m="1249530">analysis.</span> <span m="1250540">So,</span> <span m="1251560">Professor</span>
  <span m="1251980">Wilcox</span> <span m="1252460">last</span> <span m="1252640">lecture</span>
  <span m="1252710">said</span> <span m="1253330">you''re</span> <span m="1253600">going
  to</span> <span m="1253800">have</span> <span m="1254260">so much fun</span> <span
  m="1254610">with</span> <span m="1254840">Taylor</span> <span m="1255150">series.</span></p><p><span
  m="1256070">So</span> <span m="1256230">I</span> <span m="1256270">hope</span> <span
  m="1256620">you</span> <span m="1257130">have</span> <span m="1257420">already</span>
  <span m="1257800">started</span> <span m="1258860">looking</span> <span m="1259010">at</span>
  <span m="1259330">Taylor</span> <span m="1259650">series</span> <span m="1259920">and</span>
  <span m="1262170">it</span> <span m="1262320">is</span> <span m="1262510">important</span>
  <span m="1262970">you</span> <span m="1263400">guys</span> <span m="1263830">do</span>
  <span m="1263970">look</span> <span m="1264260">at</span> <span m="1264380">Taylor</span>
  <span m="1264740">series.</span> <span m="1265970">Because</span> <span m="1266350">of</span>
  <span m="1266450">the</span> <span m="1266530">importance,</span> <span m="1267330">I</span>
  <span m="1267830">use</span> <span m="1268180">red,</span> <span m="1268570">OK?</span>
  <span m="1270320">Taylor</span> <span m="1270410">series</span> <span m="1270840">analysis--</span>
  <span m="1273190">OK,</span> <span m="1273490">so</span> <span m="1273690">we</span>
  <span m="1273930">want</span> <span m="1274120">to</span> <span m="1274220">know</span>
  <span m="1274500">how</span> <span m="1275160">much</span> <span m="1275700">approximation</span>
  <span m="1276510">error</span> <span m="1277310">do</span> <span m="1277420">we</span>
  <span m="1277580">have</span> <span m="1278640">by</span> <span m="1279100">approximating</span>
  <span m="1280980">the</span> <span m="1281190">limit</span> <span m="1281930">with</span>
  <span m="1282310">this</span> <span m="1282490">finite</span> <span m="1282900">delta</span>
  <span m="1283000">t,</span> <span m="1284180">all</span> <span m="1284320">right?</span></p><p><span
  m="1285830">We</span> <span m="1286070">want</span> <span m="1286400">to</span>
  <span m="1286520">know</span> <span m="1286840">what</span> <span m="1287130">is</span>
  <span m="1287290">the</span> <span m="1287370">difference</span> <span m="1287880">between</span>
  <span m="1288670">df</span> <span m="1288920">dt</span> <span m="1290610">and</span>
  <span m="1292230">our</span> <span m="1292790">approximation.</span> <span m="1294740">So</span>
  <span m="1294890">this</span> <span m="1295110">is</span> <span m="1295250">at</span>
  <span m="1296150">some</span> <span m="1296400">t</span> <span m="1297070">and</span>
  <span m="1297290">this</span> <span m="1297470">approximation</span> <span m="1297875">is
  t</span> <span m="1298280">plus</span> <span m="1298682">delta</span> <span m="1299084">t</span>
  <span m="1299890">minus</span> <span m="1300390">f of</span> <span m="1300710">t.</span>
  <span m="1306360">OK,</span> <span m="1306740">how</span> <span m="1306920">do</span>
  <span m="1307130">I</span> <span m="1307240">figure</span> <span m="1307540">out</span>
  <span m="1307720">this</span> <span m="1307900">difference?</span> <span m="1311140">How</span>
  <span m="1311395">should</span> <span m="1311650">I</span> <span m="1311810">figure</span>
  <span m="1312120">out</span> <span m="1312320">this</span> <span m="1312460">difference?</span></p><p><span
  m="1313140">Then</span> <span m="1313350">we</span> <span m="1313500">can</span>
  <span m="1313690">compute</span> <span m="1314230">both</span> <span m="1314620">because--</span>
  <span m="1315030">yeah, we</span> <span m="1315360">can</span> <span m="1315510">compute</span>
  <span m="1315830">both.</span> <span m="1316800">And</span> <span m="1317110">then</span>
  <span m="1317230">we</span> <span m="1317360">can</span> <span m="1317600">prove</span>
  <span m="1317940">a</span> <span m="1318020">difference.</span> <span m="1318500">We</span>
  <span m="1318800">can</span> <span m="1319030">[INAUDIBLE]</span> <span m="1319290">this</span>
  <span m="1319550">line</span> <span m="1319760">with</span> <span m="1319880">this</span>
  <span m="1320050">line</span> <span m="1320220">[INAUDIBLE]</span> <span m="1320660">lambda.</span></p><p><span
  m="1320840">Like,</span> <span m="1322301">this</span> <span m="1322788">is</span>
  <span m="1323275">probably</span> <span m="1323762">0.05</span> <span m="1324249">or</span>
  <span m="1324740">something</span> <span m="1325490">like</span> <span m="1325910">that.</span>
  <span m="1326270">Yes,</span> <span m="1326550">this</span> <span m="1326710">is</span>
  <span m="1326840">a</span> <span m="1327340">translation</span> <span m="1327840">error,</span>
  <span m="1328340">right?</span> <span m="1330250">Because this</span> <span m="1330570">only</span>
  <span m="1330920">works</span> <span m="1331320">when</span> <span m="1331510">we</span>
  <span m="1331770">do</span> <span m="1332200">have</span> <span m="1332660">an</span>
  <span m="1334470">additional</span> <span m="1334970">solution,</span> <span m="1336020">right?</span>
  <span m="1342110">And</span> <span m="1344100">so</span> <span m="1344290">what--</span>
  <span m="1345130">is</span> <span m="1345640">there</span> <span m="1345930">any</span>
  <span m="1346220">way</span> <span m="1346560">to</span> <span m="1347030">activate</span>
  <span m="1348350">how</span> <span m="1348560">big</span> <span m="1348840">the</span>
  <span m="1348920">trunctation</span> <span m="1349245">error</span> <span m="1349570">is</span>
  <span m="1350600">in</span> <span m="1350810">a</span> <span m="1350860">more</span>
  <span m="1351410">general</span> <span m="1352010">way?</span></p><p><span m="1353910">AUDIENCE:
  Taylor</span> <span m="1354385">series.</span></p><p><span m="1355810">PROFESSOR:
  Taylor</span> <span m="1356040">series--</span> <span m="1356310">OK,</span> <span
  m="1357310">good.</span> <span m="1357980">Taylor</span> <span m="1358230">series--</span>
  <span m="1359920">what</span> <span m="1360110">is</span> <span m="1360220">Taylor</span>
  <span m="1360490">series?</span> <span m="1361540">Anybody</span> <span m="1361840">can</span>
  <span m="1362080">summarize</span> <span m="1362560">what</span> <span m="1362740">Taylor</span>
  <span m="1362990">series</span> <span m="1363350">is</span> <span m="1364056">in,</span>
  <span m="1364410">like,</span> <span m="1364640">one</span> <span m="1365030">sentence?</span></p><p><span
  m="1369066">AUDIENCE: [INAUDIBLE]</span></p><p><span m="1372450">PROFESSOR: Yeah,</span>
  <span m="1372690">an</span> <span m="1372840">approximation</span> <span m="1373730">of</span>
  <span m="1374010">a</span> <span m="1374460">function</span> <span m="1374880">at</span>
  <span m="1375590">some</span> <span m="1375810">point</span> <span m="1377750">using</span>
  <span m="1378240">the</span> <span m="1378340">values</span> <span m="1379500">and</span>
  <span m="1379590">derivatives</span> <span m="1380400">of</span> <span m="1380700">this</span>
  <span m="1380930">function</span> <span m="1381225">at</span> <span m="1381520">a</span>
  <span m="1381710">nearby</span> <span m="1382706">point,</span> <span m="1384200">right?</span>
  <span m="1385700">OK,</span> <span m="1386290">so</span> <span m="1386500">here,</span>
  <span m="1387760">what</span> <span m="1387980">we--</span> <span m="1389460">we
  have</span> <span m="1389870">three</span> <span m="1390335">things.</span> <span
  m="1390800">If</span> <span m="1390990">you</span> <span m="1391060">look</span>
  <span m="1391260">at</span> <span m="1391340">the</span> <span m="1391410">formula</span>
  <span m="1391870">we</span> <span m="1391910">have,</span> <span m="1392090">three</span>
  <span m="1392545">things.</span> <span m="1393000">[INAUDIBLE]</span></p><p><span
  m="1394365">The</span> <span m="1394820">derivative</span> <span m="1395730">at</span>
  <span m="1396185">t,</span> <span m="1396985">the</span> <span m="1397330">functionality</span>
  <span m="1397810">at</span> <span m="1398290">t</span> <span m="1398770">[INAUDIBLE]</span>
  <span m="1399730">the</span> <span m="1400210">functionality,</span> <span m="1400690">like,</span>
  <span m="1401170">we</span> <span m="1401300">have</span> <span m="1401510">two</span>
  <span m="1401720">points.</span> <span m="1402060">One</span> <span m="1402400">point
  is</span> <span m="1402680">at t,</span> <span m="1402870">the</span> <span m="1403368">other</span>
  <span m="1403866">points</span> <span m="1404364">[INAUDIBLE].</span></p><p><span
  m="1405360">At</span> <span m="1405858">[INAUDIBLE]</span> <span m="1406356">t,</span>
  <span m="1406860">we</span> <span m="1406960">have</span> <span m="1407180">a derivative</span>
  <span m="1407634">of</span> <span m="1408088">[INAUDIBLE].</span> <span m="1408996">At</span>
  <span m="1409450">another</span> <span m="1409860">point,</span> <span m="1410326">we</span>
  <span m="1410792">[INAUDIBLE].</span> <span m="1414054">We</span> <span m="1414520">can</span>
  <span m="1414986">employ</span> <span m="1415460">Taylor</span> <span m="1415780">series</span>
  <span m="1416100">in</span> <span m="1416480">two</span> <span m="1416660">ways.</span></p><p><span
  m="1417470">One</span> <span m="1417850">way</span> <span m="1418090">is</span>
  <span m="1418120">more</span> <span m="1418590">convenient.</span> <span m="1419530">The</span>
  <span m="1419650">other</span> <span m="1420010">[INAUDIBLE]</span> <span m="1420370">is</span>
  <span m="1420680">a</span> <span m="1420880">little</span> <span m="1421170">bit</span>
  <span m="1421630">more</span> <span m="1421960">inconvenient</span> <span m="1422640">but</span>
  <span m="1422880">still</span> <span m="1423060">works.</span> <span m="1425490">The</span>
  <span m="1425630">most</span> <span m="1425900">convenient</span> <span m="1426420">way</span>
  <span m="1426630">is</span> <span m="1426780">[INAUDIBLE]</span> <span m="1428752">f</span>
  <span m="1430640">at</span> <span m="1430895">t</span> <span m="1431150">plus delta</span>
  <span m="1431490">t</span> <span m="1431951">using</span> <span m="1432412">Taylor</span>
  <span m="1432873">series.</span> <span m="1434260">The</span> <span m="1434380">more</span>
  <span m="1434780">inconvenient</span> <span m="1435230">way</span> <span m="1435550">is</span>
  <span m="1436040">to</span> <span m="1436390">send</span> <span m="1436690">both</span>
  <span m="1437500">derivatives</span> <span m="1437830">and</span> <span m="1438030">the</span>
  <span m="1438524">value</span> <span m="1439512">[INAUDIBLE]</span> <span m="1440500">using</span>
  <span m="1440994">Taylor</span> <span m="1441490">series</span> <span m="1441990">[INAUDIBLE].</span>
  <span m="1444560">So</span> <span m="1444660">let''s</span> <span m="1445040">do</span>
  <span m="1445190">the</span> <span m="1445410">convenient</span> <span m="1445845">way</span>
  <span m="1446280">first.</span> <span m="1446980">And</span> <span m="1447240">I''m</span>
  <span m="1447310">going to</span> <span m="1447635">show you</span> <span m="1447960">and
  we''re going to</span> <span m="1448440">get something</span> <span m="1448935">similar</span>
  <span m="1449430">using</span> <span m="1449925">the slightly</span> <span m="1450420">more</span>
  <span m="1450710">convenient</span> <span m="1451157">way,</span> <span m="1452051">all
  right?</span></p><p><span m="1453840">So</span> <span m="1454120">the</span> <span
  m="1454220">easy</span> <span m="1454590">way--</span> <span m="1454920">let</span>
  <span m="1455230">me</span> <span m="1455420">use</span> <span m="1457030">green</span>
  <span m="1457550">to</span> <span m="1458200">denote</span> <span m="1458470">the</span>
  <span m="1458740">easy</span> <span m="1459000">way.</span> <span m="1460440">OK,</span>
  <span m="1460970">so</span> <span m="1461140">easy--</span> <span m="1464250">f</span>
  <span m="1465000">at</span> <span m="1465450">t</span> <span m="1465750">plus</span>
  <span m="1466470">delta</span> <span m="1466860">t.</span> <span m="1467730">So,</span>
  <span m="1468030">the start</span> <span m="1468420">of</span> <span m="1468590">Taylor</span>
  <span m="1468950">series--</span> <span m="1469960">the</span> <span m="1470090">Taylor</span>
  <span m="1470420">series</span> <span m="1471000">I</span> <span m="1471160">write</span>
  <span m="1471520">as</span> <span m="1471740">a</span> <span m="1472080">formula</span>
  <span m="1472640">is</span> <span m="1473250">k</span> <span m="1473950">goes</span>
  <span m="1474500">from</span> <span m="1475060">0</span> <span m="1475680">to--</span>
  <span m="1476890">let</span> <span m="1477050">me</span> <span m="1477160">actually--</span>
  <span m="1478860">equal</span> <span m="1479250">to</span> <span m="1479380">infinity</span>
  <span m="1481930">of</span> <span m="1482856">f</span> <span m="1483710">to</span>
  <span m="1483860">the</span> <span m="1483960">k-th</span> <span m="1484600">derivative</span>
  <span m="1485370">at</span> <span m="1485550">t</span> <span m="1487620">divided</span>
  <span m="1488160">by</span> <span m="1488510">k</span> <span m="1488870">factorial</span>
  <span m="1490520">delta</span> <span m="1490800">t</span> <span m="1491752">to the</span>
  <span m="1492230">k-th.</span> <span m="1493550">This</span> <span m="1493780">is</span>
  <span m="1494630">what</span> <span m="1494850">Taylor</span> <span m="1495110">series</span>
  <span m="1495450">is.</span></p><p><span m="1498130">And</span> <span m="1498390">in</span>
  <span m="1498530">this</span> <span m="1498750">case,</span> <span m="1499500">we</span>
  <span m="1499700">do</span> <span m="1499920">not</span> <span m="1500340">want</span>
  <span m="1500590">to</span> <span m="1500730">keep</span> <span m="1501210">anything</span>
  <span m="1503300">above</span> <span m="1505550">the</span> <span m="1505630">first</span>
  <span m="1505980">derivative.</span> <span m="1509350">So</span> <span m="1509550">I''m</span>
  <span m="1509710">just</span> <span m="1509920">going</span> <span m="1510050">to</span>
  <span m="1510160">be</span> <span m="1510320">writing</span> <span m="1511050">that--</span>
  <span m="1512120">I''m just</span> <span m="1512280">going</span> <span m="1512430">to</span>
  <span m="1512510">be</span> <span m="1512590">keeping</span> <span m="1512980">two</span>
  <span m="1513360">terms.</span> <span m="1513750">The</span> <span m="1513860">first</span>
  <span m="1514110">term</span> <span m="1514250">is</span> <span m="1514420">k</span>
  <span m="1514838">equal to</span> <span m="1515256">0.</span> <span m="1516510">What</span>
  <span m="1516710">is</span> <span m="1517020">f</span> <span m="1517580">to</span>
  <span m="1517750">the</span> <span m="1517940">0-th</span> <span m="1518370">derivative?</span></p><p><span
  m="1521170">It''s</span> <span m="1521430">just</span> <span m="1521750">f</span>
  <span m="1522050">itself,</span> <span m="1522750">right?</span> <span m="1523170">This</span>
  <span m="1523440">is</span> <span m="1523540">k equal</span> <span m="1523903">to</span>
  <span m="1524266">0.</span> <span m="1524630">What</span> <span m="1524850">is</span>
  <span m="1525070">0</span> <span m="1525400">factorial?</span> <span m="1527240">One.</span>
  <span m="1528050">What</span> <span m="1528240">is</span> <span m="1528530">delta</span>
  <span m="1528820">t</span> <span m="1529030">to</span> <span m="1529160">the</span>
  <span m="1529290">0-th?</span></p><p><span m="1531360">one.</span> <span m="1531950">OK,</span>
  <span m="1532380">so</span> <span m="1532570">that</span> <span m="1532850">is</span>
  <span m="1533010">the</span> <span m="1533100">first</span> <span m="1533370">term.</span>
  <span m="1534780">Now</span> <span m="1534970">let''s</span> <span m="1535330">do</span>
  <span m="1535500">k equal to</span> <span m="1535900">1.</span></p><p><span m="1536930">What</span>
  <span m="1537170">is</span> <span m="1537330">the</span> <span m="1537430">first</span>
  <span m="1537790">derivative</span> <span m="1538300">of</span> <span m="1538450">k?</span>
  <span m="1538870">It''s</span> <span m="1539210">df</span> <span m="1539390">dt.</span>
  <span m="1541820">What is</span> <span m="1542150">one</span> <span m="1542390">factorial?</span>
  <span m="1543510">It''s</span></p><p><span m="1543990">one</span> <span m="1544290">again.</span>
  <span m="1545070">And</span> <span m="1545370">delta</span> <span m="1545430">t</span>
  <span m="1545630">to</span> <span m="1545840">the</span> <span m="1545980">one--</span>
  <span m="1546640">that</span> <span m="1546850">is</span> <span m="1547110">delta</span>
  <span m="1547220">t.</span> <span m="1548890">Anything</span> <span m="1549440">above</span>
  <span m="1549850">that</span> <span m="1550760">has</span> <span m="1551030">a</span>
  <span m="1551210">delta</span> <span m="1551550">t</span> <span m="1552680">to</span>
  <span m="1552870">the at</span> <span m="1553070">least</span> <span m="1554410">second</span>
  <span m="1554580">order,</span> <span m="1554930">right?</span> <span m="1555195">right?</span>
  <span m="1555460">At</span> <span m="1555830">least</span> <span m="1556210">delta</span>
  <span m="1556560">t</span> <span m="1556950">squared.</span> <span m="1557366">square.</span></p><p><span
  m="1558200">So</span> <span m="1558360">I</span> <span m="1558540">am</span> <span
  m="1558690">going</span> <span m="1558840">to</span> <span m="1558960">write</span>
  <span m="1559380">all</span> <span m="1559700">these</span> <span m="1559950">terms</span>
  <span m="1560260">a</span> <span m="1560440">a</span> <span m="1560540">big</span>
  <span m="1560940">O</span> <span m="1561735">times</span> <span m="1562020">big</span>
  <span m="1562270">O</span> <span m="1562500">delta</span> <span m="1563000">t</span>
  <span m="1563370">squared.</span> <span m="1563740">Has</span> <span m="1563980">anybody</span>
  <span m="1564460">seen</span> <span m="1564755">this</span> <span m="1565050">big</span>
  <span m="1565340">O</span> <span m="1565706">[INAUDIBLE]?</span> <span m="1568750">You
  did,</span> <span m="1569050">OK.</span> <span m="1569933">What this</span> <span
  m="1570406">means</span> <span m="1570879">is</span> <span m="1571352">that</span>
  <span m="1571825">this</span> <span m="1572298">[INAUDIBLE]</span> <span m="1572771">compares</span>
  <span m="1573244">[INAUDIBLE]</span> <span m="1576090">as</span> <span m="1576320">long</span>
  <span m="1576560">as</span> <span m="1576900">all</span> <span m="1577250">these</span>
  <span m="1577470">terms</span> <span m="1577896">have</span> <span m="1578322">a</span>
  <span m="1578748">delta</span> <span m="1579174">t</span> <span m="1579600">squared</span>
  <span m="1580036">or</span> <span m="1580472">delta</span> <span m="1580910">t cube</span>
  <span m="1581400">or delta t</span> <span m="1581570">[INAUDIBLE].</span></p><p><span
  m="1582012">[INAUDIBLE]</span> <span m="1583780">more</span> <span m="1584290">of</span>
  <span m="1584680">the</span> <span m="1585141">[INAUDIBLE]</span> <span m="1586063">square.</span>
  <span m="1587446">OK,</span> <span m="1589760">which</span> <span m="1590540">is</span>
  <span m="1590820">true</span> <span m="1591150">for</span> <span m="1591390">all</span>
  <span m="1591580">the</span> <span m="1591700">other</span> <span m="1591940">terms</span>
  <span m="1592050">[INAUDIBLE].</span> <span m="1595040">Or</span> <span m="1595510">maybe</span>
  <span m="1595760">green is</span> <span m="1596260">a</span> <span m="1596320">little</span>
  <span m="1596560">bit</span> <span m="1596720">too--</span> <span m="1598660">doesn''t</span>
  <span m="1598940">show</span> <span m="1599020">really</span> <span m="1599560">well</span>
  <span m="1599840">on</span> <span m="1600030">this.</span> <span m="1600900">So</span>
  <span m="1601356">let me</span> <span m="1601812">see if</span> <span m="1602268">I
  can--</span> <span m="1603640">let me</span> <span m="1603830">change</span> <span
  m="1604170">to</span> <span m="1604330">this.</span></p><p><span m="1606040">OK,</span>
  <span m="1607440">yeah,</span> <span m="1607660">that''s</span> <span m="1608050">better.</span>
  <span m="1608440">All</span> <span m="1608895">right,</span> <span m="1609350">OK.</span>
  <span m="1611350">So,</span> <span m="1611580">once</span> <span m="1611850">we</span>
  <span m="1611980">do</span> <span m="1612220">that,</span> <span m="1612740">what</span>
  <span m="1613290">does</span> <span m="1613500">it</span> <span m="1613560">change?</span></p><p><span
  m="1615560">[INAUDIBLE]</span> <span m="1616060">action</span> <span m="1617060">[INAUDIBLE].</span>
  <span m="1625950">Yeah,</span> <span m="1626290">actually</span> <span m="1626590">don''t</span>
  <span m="1626800">know</span> <span m="1627270">[INAUDIBLE].</span> <span m="1631690">OK,</span>
  <span m="1632230">once</span> <span m="1632680">we</span> <span m="1632840">do</span>
  <span m="1633060">this,</span> <span m="1634070">we</span> <span m="1634250">can</span>
  <span m="1634620">plot</span> <span m="1634985">this</span> <span m="1635350">back</span>
  <span m="1635850">into</span> <span m="1637280">the</span> <span m="1637430">truncation</span>
  <span m="1637960">error</span> <span m="1638410">we call</span> <span m="1638720">tau.</span></p><p><span
  m="1640570">Tau</span> <span m="1640900">is</span> <span m="1641110">going</span>
  <span m="1641260">to</span> <span m="1641350">be</span> <span m="1641520">df</span>
  <span m="1642910">dt</span> <span m="1643620">at</span> <span m="1644070">t</span>
  <span m="1644790">minus</span> <span m="1646460">something</span> <span m="1647000">divided</span>
  <span m="1647340">by</span> <span m="1647480">delta</span> <span m="1647570">t.</span>
  <span m="1648040">And</span> <span m="1648230">that</span> <span m="1648430">something</span>
  <span m="1649050">is--</span> <span m="1649860">first</span> <span m="1650130">of</span>
  <span m="1650310">all,</span> <span m="1650560">it''s</span> <span m="1650740">a</span>
  <span m="1650840">Taylor</span> <span m="1651230">expansion</span> <span m="1653120">of</span>
  <span m="1654280">ft</span> <span m="1654990">plus</span> <span m="1655245">delta</span>
  <span m="1655500">t</span> <span m="1659966">minus</span> <span m="1660470">f of</span>
  <span m="1660760">t,</span> <span m="1662770">right?</span></p><p><span m="1665140">And</span>
  <span m="1665520">now</span> <span m="1665710">it''s</span> <span m="1665860">time</span>
  <span m="1666100">to</span> <span m="1666210">cancel</span> <span m="1666590">the</span>
  <span m="1667056">terms.</span> <span m="1668920">So</span> <span m="1669130">I''m</span>
  <span m="1669260">going</span> <span m="1669400">to</span> <span m="1669520">write</span>
  <span m="1670010">this</span> <span m="1670380">as</span> <span m="1670770">it</span>
  <span m="1670940">is</span> <span m="1671890">and,</span> <span m="1672400">first</span>
  <span m="1672700">of</span> <span m="1672860">all,</span> <span m="1673030">try</span>
  <span m="1673210">to</span> <span m="1673310">cancel</span> <span m="1673650">the</span>
  <span m="1673760">terms</span> <span m="1674030">here.</span> <span m="1674430">So</span>
  <span m="1674610">delta</span> <span m="1674770">t</span> <span m="1675040">is</span>
  <span m="1675120">[INAUDIBLE]</span> <span m="1675330">here.</span> <span m="1676130">This</span>
  <span m="1676530">ft</span> <span m="1677900">cancels</span> <span m="1678400">with</span>
  <span m="1678870">this</span> <span m="1679150">ft,</span> <span m="1679834">right?</span></p><p><span
  m="1681106">So</span> <span m="1681530">we</span> <span m="1681860">have</span>
  <span m="1682130">a</span> <span m="1682250">df</span> <span m="1684074">dt</span>
  <span m="1684530">times</span> <span m="1684920">delta</span> <span m="1685080">t</span>
  <span m="1685870">plus</span> <span m="1686170">O</span> <span m="1687370">delta</span>
  <span m="1687460">t</span> <span m="1688080">square,</span> <span m="1689780">OK?</span>
  <span m="1692650">And</span> <span m="1694030">this</span> <span m="1695020">delta</span>
  <span m="1695330">t</span> <span m="1695510">cancels</span> <span m="1695980">with</span>
  <span m="1696230">this</span> <span m="1696510">delta</span> <span m="1696935">t,</span>
  <span m="1698080">which</span> <span m="1698360">makes</span> <span m="1698650">this</span>
  <span m="1698940">cancel</span> <span m="1699290">with</span> <span m="1699773">this.</span>
  <span m="1701280">So</span> <span m="1701590">the</span> <span m="1702080">only</span>
  <span m="1702350">thing</span> <span m="1702540">we</span> <span m="1702670">get</span>
  <span m="1703000">is,</span> <span m="1703990">oh,</span> <span m="1704370">delta</span>
  <span m="1704810">t</span> <span m="1704950">square</span> <span m="1705200">divides</span>
  <span m="1705560">by</span> <span m="1706200">delta</span> <span m="1706480">t.</span></p><p><span
  m="1710180">[INAUDIBLE]</span> <span m="1712205">square,</span> <span m="1712610">delta</span>
  <span m="1713420">t</span> <span m="1713710">square</span> <span m="1714120">[INAUDIBLE]</span>
  <span m="1715760">all</span> <span m="1716250">the</span> <span m="1716726">terms</span>
  <span m="1717202">that has</span> <span m="1717680">delta t</span> <span m="1718070">square  or</span>
  <span m="1718530">higher.</span> <span m="1719470">Then</span> <span m="1719760">[INAUDIBLE]</span>
  <span m="1720480">divided</span> <span m="1720840">by delta</span> <span m="1721301">t.</span>
  <span m="1721762">What do we</span> <span m="1722223">get?</span></p><p><span m="1723145">STUDENT:
  [INAUDIBLE]</span></p><p><span m="1724070">PROFESSOR: Order</span> <span m="1724290">delta</span>
  <span m="1724545">t,</span> <span m="1724800">exactly.</span> <span m="1728480">All</span>
  <span m="1728700">right,</span> <span m="1729860">so</span> <span m="1730340">what</span>
  <span m="1730820">we</span> <span m="1730980">know</span> <span m="1731290">is</span>
  <span m="1731500">that</span> <span m="1733000">the</span> <span m="1733100">truncation</span>
  <span m="1733630">error,</span> <span m="1735250">whatever</span> <span m="1735620">it
  is,</span> <span m="1735700">is</span> <span m="1736210">order</span> <span m="1736680">delta</span>
  <span m="1736910">t,</span> <span m="1738440">which</span> <span m="1738690">means</span>
  <span m="1739370">it</span> <span m="1739600">decreases</span> <span m="1741810">f</span>
  <span m="1742580">delta</span> <span m="1743054">t.</span> <span m="1744950">So</span>
  <span m="1745610">[INAUDIBLE]</span> <span m="1745800">to</span> <span m="1746040">kind</span>
  <span m="1746230">of--</span> <span m="1747016">to</span> <span m="1747370">visualize</span>
  <span m="1748040">what</span> <span m="1748340">this</span> <span m="1748570">means,</span>
  <span m="1749930">if</span> <span m="1750140">I</span> <span m="1750260">go</span>
  <span m="1750480">back</span> <span m="1750650">to</span> <span m="1750790">here,</span>
  <span m="1751330">so</span> <span m="1751510">this</span> <span m="1751780">is</span>
  <span m="1752220">[INAUDIBLE]</span> <span m="1755910">0.05,</span> <span m="1756200">right?</span>
  <span m="1756645">[INAUDIBLE]</span> <span m="1760100">0.05.</span> <span m="1761760">This</span>
  <span m="1761940">for</span> <span m="1762100">delta</span> <span m="1762340">t</span>
  <span m="1763000">of</span> <span m="1763260">0.1.</span></p><p><span m="1765190">If</span>
  <span m="1765430">I</span> <span m="1765600">increase</span> <span m="1766240">delta</span>
  <span m="1766310">t</span> <span m="1767260">to</span> <span m="1767460">0.2--</span>
  <span m="1769100">let</span> <span m="1769600">me</span> <span m="1770060">exaggerate.</span>
  <span m="1770430">If</span> <span m="1770680">I</span> <span m="1771020">increase</span>
  <span m="1771320">delta</span> <span m="1771645">t</span> <span m="1771970">t</span>
  <span m="1772265">1,</span> <span m="1773980">what do</span> <span m="1774200">you
  think</span> <span m="1774260">this is</span> <span m="1774555">going to</span>
  <span m="1774850">get?</span> <span m="1778160">Yeah,</span> <span m="1778655">much
  bigger</span> <span m="1779150">of</span> <span m="1779645">course--</span> <span
  m="1780140">how much</span> <span m="1780635">bigger?</span></p><p><span m="1789730">No,
  no,</span> <span m="1790070">the</span> <span m="1790170">area</span> <span m="1790490">is</span>
  <span m="1790750">O</span> <span m="1791150">delta</span> <span m="1791550">t.</span>
  <span m="1793230">Let me</span> <span m="1793653">say,</span> <span m="1794076">if
  I</span> <span m="1794499">can make</span> <span m="1794922">this</span> <span m="1795345">[INAUDIBLE]</span>
  <span m="1795770">if</span> <span m="1796170">I</span> <span m="1796330">may</span>
  <span m="1796540">[INAUDIBLE]</span> <span m="1799610">Now</span> <span m="1799820">the</span>
  <span m="1800020">[INAUDIBLE]</span> <span m="1801200">0.05</span> <span m="1801470">[INAUDIBLE].</span>
  <span m="1804850">It''s</span> <span m="1805330">1.</span></p><p><span m="1805830">It</span>
  <span m="1805910">is</span> <span m="1806220">going</span> <span m="1806500">to
  be</span> <span m="1806760">o</span> <span m="1807050">delta</span> <span m="1807420">t,</span>
  <span m="1807560">which</span> <span m="1807770">means</span> <span m="1808280">delta</span>
  <span m="1808540">t</span> <span m="1808800">increase</span> <span m="1809230">by</span>
  <span m="1809340">a</span> <span m="1809570">factor</span> <span m="1809640">of</span>
  <span m="1809740">two.</span> <span m="1810250">This</span> <span m="1810500">area</span>
  <span m="1810730">increases</span> <span m="1811060">by a</span> <span m="1811450">factor</span>
  <span m="1811775">of</span> <span m="1812100">two.</span> <span m="1812710">Let''s</span>
  <span m="1813160">just</span> <span m="1813420">try</span> <span m="1813670">to</span>
  <span m="1814800">do</span> <span m="1815120">this</span> <span m="1815380">to</span>
  <span m="1815530">see if</span> <span m="1815970">what</span> <span m="1816200">I</span>
  <span m="1816290">said</span> <span m="1816510">is</span> <span m="1816670">true.</span>
  <span m="1817030">0.2--</span> <span m="1817900">OK,</span> <span m="1818660">I''m</span>
  <span m="1818830">going</span> <span m="1818980">to</span> <span m="1819060">be</span>
  <span m="1819220">repeating</span> <span m="1819970">what</span> <span m="1820170">I''m</span>
  <span m="1820310">going</span> <span m="1820450">to</span> <span m="1820530">be</span>
  <span m="1820700">doing.</span></p><p><span m="1821612">f</span> <span m="1822070">is</span>
  <span m="1822330">equal</span> <span m="1822797">to--</span> <span m="1824200">no,</span>
  <span m="1824470">I</span> <span m="1824530">need</span> <span m="1824710">to</span>
  <span m="1824830">do</span> <span m="1825100">t</span> <span m="1825290">plus</span>
  <span m="1826510">t</span> <span m="1826970">equal</span> <span m="1827407">to</span>
  <span m="1827844">this.</span> <span m="1828281">f</span> <span m="1828720">is</span>
  <span m="1828980">equal</span> <span m="1829370">to</span> <span m="1830260">this</span>
  <span m="1831550">and</span> <span m="1831860">the</span> <span m="1831950">df</span>
  <span m="1832330">dt</span> <span m="1833090">is</span> <span m="1833490">equal</span>
  <span m="1833950">to</span> <span m="1834320">this.</span> <span m="1836240">Right,</span>
  <span m="1837250">and</span> <span m="1837590">I''m</span> <span m="1837740">going</span>
  <span m="1837890">to do a</span> <span m="1837980">hold</span> <span m="1838450">on</span>
  <span m="1839110">and</span> <span m="1839485">the</span> <span m="1839860">plot.</span>
  <span m="1843110">I''m</span> <span m="1843330">going</span> <span m="1843480">to</span>
  <span m="1843580">be</span> <span m="1843660">plotting</span> <span m="1844250">t</span>
  <span m="1844540">from</span> <span m="1844740">1</span> <span m="1844990">to n</span>
  <span m="1845230">minus</span> <span m="1845370">1</span> <span m="1845610">df</span>
  <span m="1845910">dt.</span> <span m="1846390">And</span> <span m="1846540">this</span>
  <span m="1846710">time,</span> <span m="1846960">I</span> <span m="1847050">make</span>
  <span m="1847300">it</span> <span m="1847390">red.</span></p><p><span m="1849010">All</span>
  <span m="1849140">right,</span> <span m="1849940">so</span> <span m="1850420">o</span>
  <span m="1850880">means</span> <span m="1851010">I</span> <span m="1851120">still</span>
  <span m="1851330">want</span> <span m="1851460">to</span> <span m="1851530">plot</span>
  <span m="1851770">in</span> <span m="1851890">circles.</span> <span m="1852400">r</span>
  <span m="1852830">means</span> <span m="1852900">red.</span> <span m="1853632">So</span>
  <span m="1854000">Let''s</span> <span m="1854360">see</span> <span m="1855350">what</span>
  <span m="1855510">I</span> <span m="1855600">get.</span> <span m="1857754">Is</span>
  <span m="1858200">it</span> <span m="1858370">clear?</span></p><p><span m="1860690">The</span>
  <span m="1860920">blue</span> <span m="1862010">is</span> <span m="1862415">the</span>
  <span m="1862820">derivative</span> <span m="1863255">I</span> <span m="1863690">get</span>
  <span m="1864125">[INAUDIBLE]</span> <span m="1865870">delta</span> <span m="1866230">t</span>
  <span m="1866680">0.1.</span> <span m="1867670">The</span> <span m="1867820">red</span>
  <span m="1868175">is</span> <span m="1868530">the derivative</span> <span m="1868997">[INAUDIBLE]</span>
  <span m="1869464">delta</span> <span m="1869931">t</span> <span m="1870398">0.2.</span>
  <span m="1872740">The</span> <span m="1873200">error</span> <span m="1873636">[INAUDIBLE]</span>
  <span m="1874072">the difference</span> <span m="1874508">between</span> <span m="1874944">the</span>
  <span m="1875380">circle</span> <span m="1875730">and</span> <span m="1875910">the</span>
  <span m="1876020">black line.</span></p><p><span m="1876320">The</span> <span m="1876640">black</span>
  <span m="1876860">line is</span> <span m="1877350">the exact</span> <span m="1877760">[INAUDIBLE]</span>
  <span m="1878080">derivative,</span> <span m="1878970">which</span> <span m="1879280">is</span>
  <span m="1879480">only</span> <span m="1879660">available</span> <span m="1879955">if</span>
  <span m="1880250">we</span> <span m="1880400">have</span> <span m="1880640">[INAUDIBLE].</span>
  <span m="1883280">And</span> <span m="1883550">where</span> <span m="1883640">[INAUDIBLE]</span>
  <span m="1884120">the</span> <span m="1884480">difference</span> <span m="1884943">between</span>
  <span m="1885406">the</span> <span m="1885870">circles</span> <span m="1886120">[INAUDIBLE]</span>
  <span m="1886810">derivatives</span> <span m="1886950">and</span> <span m="1887220">the</span>
  <span m="1887660">black line.</span> <span m="1888100">This</span> <span m="1888540">is</span>
  <span m="1888940">real</span> <span m="1889420">derivative.</span></p><p><span m="1889900">It</span>
  <span m="1890090">grew</span> <span m="1890380">by</span> <span m="1890520">a</span>
  <span m="1890580">factor</span> <span m="1890820">of</span> <span m="1890950">two.</span>
  <span m="1892990">OK,</span> <span m="1894500">so</span> <span m="1894930">this</span>
  <span m="1895210">is</span> <span m="1895390">using</span> <span m="1895840">the</span>
  <span m="1895950">easy</span> <span m="1896375">way,</span> <span m="1897010">Taylor</span>
  <span m="1897340">series</span> <span m="1897700">analysis.</span> <span m="1898750">I''m</span>
  <span m="1898950">also</span> <span m="1899190">going</span> <span m="1899320">to</span>
  <span m="1899400">show</span> <span m="1899570">you</span> <span m="1899710">briefly</span>
  <span m="1899995">the</span> <span m="1900280">hard</span> <span m="1900520">way,</span>
  <span m="1900900">which</span> <span m="1901280">is</span> <span m="1901730">kind
  of</span> <span m="1902020">pointless</span> <span m="1902150">here.</span></p><p><span
  m="1902430">But</span> <span m="1902670">as</span> <span m="1903056">you</span>
  <span m="1903442">are</span> <span m="1903830">going</span> <span m="1903950">to</span>
  <span m="1904070">see</span> <span m="1904370">later</span> <span m="1904700">on</span>
  <span m="1904870">when</span> <span m="1905050">we</span> <span m="1905160">get</span>
  <span m="1905360">to</span> <span m="1905720">more</span> <span m="1906260">complex</span>
  <span m="1906720">schemes,</span> <span m="1908100">we</span> <span m="1908370">have</span>
  <span m="1908670">to</span> <span m="1908850">start</span> <span m="1909090">using</span>
  <span m="1909430">the</span> <span m="1909750">more</span> <span m="1910090">difficult</span>
  <span m="1910570">way</span> <span m="1910750">of</span> <span m="1910960">doing</span>
  <span m="1911250">Taylor</span> <span m="1911550">series.</span> <span m="1914030">I''m</span>
  <span m="1914270">going</span> <span m="1914420">to</span> <span m="1914560">rewrite</span>
  <span m="1915340">what</span> <span m="1915760">is</span> <span m="1915940">the</span>
  <span m="1916080">[INAUDIBLE]</span> <span m="1916540">error</span> <span m="1916870">we''re</span>
  <span m="1917080">interested</span> <span m="1917430">in</span> <span m="1917680">here--</span>
  <span m="1920210">f</span> <span m="1920570">of</span> <span m="1921007">t</span>
  <span m="1921444">plus delta</span> <span m="1921881">t</span> <span m="1922318">minus</span>
  <span m="1922755">f of</span> <span m="1923192">t</span> <span m="1924030">divided</span>
  <span m="1924380">by</span> <span m="1924600">delta</span> <span m="1924930">t,</span>
  <span m="1925340">right?</span> <span m="1925760">This</span> <span m="1926060">is</span>
  <span m="1926210">at</span> <span m="1926640">t.</span></p><p><span m="1927970">OK,</span>
  <span m="1929370">Taylor</span> <span m="1929710">series--</span> <span m="1930090">we''re</span>
  <span m="1930310">going</span> <span m="1930430">to</span> <span m="1930490">do</span>
  <span m="1930670">it</span> <span m="1930750">again,</span> <span m="1931220">but</span>
  <span m="1931410">we''re going</span> <span m="1931580">to</span> <span m="1931960">represent</span>
  <span m="1932740">f of</span> <span m="1933130">t</span> <span m="1934096">as</span>
  <span m="1935760">a</span> <span m="1936080">Taylor</span> <span m="1936220">series</span>
  <span m="1937760">of</span> <span m="1938090">k</span> <span m="1938380">goes</span>
  <span m="1938710">from</span> <span m="1939030">0</span> <span m="1939430">to</span>
  <span m="1939580">infinity</span> <span m="1941362">f</span> <span m="1941810">to</span>
  <span m="1942000">the</span> <span m="1942120">k-th</span> <span m="1943870">t</span>
  <span m="1944510">plus</span> <span m="1945170">delta</span> <span m="1945500">t</span>
  <span m="1946770">divided</span> <span m="1947160">by</span> <span m="1947390">k</span>
  <span m="1947700">factorial.</span> <span m="1948910">Here</span> <span m="1949340">should</span>
  <span m="1949430">be,</span> <span m="1949610">what?</span> <span m="1951780">So</span>
  <span m="1951930">I''m</span> <span m="1952070">extending</span> <span m="1953060">f</span>
  <span m="1953280">of</span> <span m="1953440">t</span> <span m="1954970">with</span>
  <span m="1955290">a</span> <span m="1955400">Taylor</span> <span m="1955770">series</span>
  <span m="1956140">that</span> <span m="1956330">is</span> <span m="1956710">based</span>
  <span m="1957010">on</span> <span m="1957150">t</span> <span m="1957200">plus</span>
  <span m="1957430">delta</span> <span m="1957927">t.</span></p><p><span m="1963394">But
  there</span> <span m="1963900">is</span> <span m="1964340">something</span> <span
  m="1964640">to</span> <span m="1964730">the</span> <span m="1964810">k</span> <span
  m="1965100">power.</span> <span m="1966330">And</span> <span m="1966740">what</span>
  <span m="1967050">is</span> <span m="1967190">this</span> <span m="1967390">something?</span>
  <span m="1977972">OK,</span> <span m="1978470">I''m just</span> <span m="1978950">going</span>
  <span m="1979100">to</span> <span m="1979190">write a</span> <span m="1979590">box</span>
  <span m="1979890">here.</span></p><p><span m="1980670">f</span> <span m="1981475">of</span>
  <span m="1981910">y</span> <span m="1982760">is</span> <span m="1983030">equal</span>
  <span m="1983410">to</span> <span m="1983680">summation</span> <span m="1984300">of</span>
  <span m="1984510">k</span> <span m="1984800">equal</span> <span m="1985090">to</span>
  <span m="1985580">0.</span> <span m="1986075">Taylor</span> <span m="1986570">series</span>
  <span m="1987140">k is</span> <span m="1987500">power</span> <span m="1987810">fx</span>
  <span m="1988380">k</span> <span m="1988870">factorial</span> <span m="1990600">what</span>
  <span m="1991320">to</span> <span m="1991420">the</span> <span m="1991500">k-th</span>
  <span m="1991997">power.</span> <span m="1993490">Let</span> <span m="1993580">me
  explain</span> <span m="1993730">to you</span> <span m="1994180">y</span> <span
  m="1995180">at</span> <span m="1995680">x.</span> <span m="1999890">Y</span> <span
  m="2000370">minus</span> <span m="2000860">x--</span> <span m="2001100">exactly,</span>
  <span m="2002720">right?</span></p><p><span m="2003770">Previously,</span> <span
  m="2004480">we</span> <span m="2004760">have</span> <span m="2005170">x</span> <span
  m="2005667">being</span> <span m="2006164">t,</span> <span m="2006661">y</span>
  <span m="2007160">being</span> <span m="2007820">t</span> <span m="2008150">plus</span>
  <span m="2008310">delta</span> <span m="2008794">t,</span> <span m="2010730">OK?</span>
  <span m="2012740">So</span> <span m="2013000">y</span> <span m="2013260">minus</span>
  <span m="2013570">x is</span> <span m="2013880">delta</span> <span m="2014380">t.</span>
  <span m="2017880">How about</span> <span m="2018190">in</span> <span m="2018310">this</span>
  <span m="2018510">case?</span></p><p><span m="2021060">Negative</span> <span m="2021530">delta</span>
  <span m="2021610">t,</span> <span m="2021830">exactly.</span> <span m="2027000">OK,</span>
  <span m="2027240">does</span> <span m="2027420">this</span> <span m="2027620">make</span>
  <span m="2027840">sense?</span> <span m="2034300">All</span> <span m="2034645">right,</span>
  <span m="2034990">yeah.</span> <span m="2035330">So</span> <span m="2035560">this</span>
  <span m="2035740">is</span> <span m="2035860">going</span> <span m="2035980">to</span>
  <span m="2036050">be</span> <span m="2036440">very</span> <span m="2037000">useful,</span>
  <span m="2037570">like</span> <span m="2037700">for</span> <span m="2038310">making</span>
  <span m="2039070">sure</span> <span m="2039200">you know</span> <span m="2039633">every</span>
  <span m="2041800">different</span> <span m="2042860">view,</span> <span m="2043740">every</span>
  <span m="2044000">different</span> <span m="2044530">manipulation</span> <span m="2045180">of</span>
  <span m="2045260">the</span> <span m="2045420">Taylor</span> <span m="2045830">series.</span>
  <span m="2045910">It''s</span> <span m="2046370">going to be</span> <span m="2046830">useful.</span></p><p><span
  m="2047840">I''m</span> <span m="2047970">going</span> <span m="2048100">to</span>
  <span m="2048170">show</span> <span m="2048330">you</span> <span m="2048500">another</span>
  <span m="2050010">manipulation</span> <span m="2050659">of</span> <span m="2050770">the</span>
  <span m="2050929">Taylor</span> <span m="2051199">series.</span> <span m="2053730">That</span>
  <span m="2054208">is,</span> <span m="2054686">if</span> <span m="2055170">I</span>
  <span m="2055290">take</span> <span m="2055920">a</span> <span m="2056030">derivative</span>
  <span m="2057690">to</span> <span m="2057909">both</span> <span m="2058670">sides</span>
  <span m="2059060">of</span> <span m="2059210">the</span> <span m="2059340">Taylor</span>
  <span m="2059803">series,</span> <span m="2060266">take</span> <span m="2060730">derivative</span>
  <span m="2065070">with</span> <span m="2065409">respect</span> <span m="2065920">to</span>
  <span m="2066120">y,</span> <span m="2067290">what</span> <span m="2067520">I''m</span>
  <span m="2067719">going</span> <span m="2067870">to</span> <span m="2067929">get--</span>
  <span m="2076280">if</span> <span m="2076440">I</span> <span m="2076540">take</span>
  <span m="2077000">derivatives</span> <span m="2077630">on</span> <span m="2077780">the</span>
  <span m="2077850">left</span> <span m="2078060">hand</span> <span m="2078219">side,</span>
  <span m="2078469">what</span> <span m="2078679">I''m</span> <span m="2078820">going</span>
  <span m="2078949">to</span> <span m="2079010">get?</span></p><p><span m="2081900">df</span>
  <span m="2082199">d--</span> <span m="2084420">yeah,</span> <span m="2085120">let</span>
  <span m="2085540">me</span> <span m="2085670">just</span> <span m="2085920">say,</span>
  <span m="2086190">yeah,</span> <span m="2087010">df</span> <span m="2087290">dy</span>
  <span m="2088550">is</span> <span m="2088840">equal</span> <span m="2088980">to</span>
  <span m="2089250">summation</span> <span m="2089962">k</span> <span m="2090320">equal</span>
  <span m="2090654">to</span> <span m="2090989">0</span> <span m="2091380">to</span>
  <span m="2092719">infinity.</span> <span m="2094230">What</span> <span m="2094460">is</span>
  <span m="2094920">this</span> <span m="2095420">term,</span> <span m="2095580">taking</span>
  <span m="2095889">derivative</span> <span m="2096144">y?</span> <span m="2099890">It''s</span>
  <span m="2100080">a</span> <span m="2100130">constant.</span> <span m="2100870">There</span>
  <span m="2101100">is</span> <span m="2101230">no</span> <span m="2101410">derivative.</span>
  <span m="2102050">So</span> <span m="2102230">this</span> <span m="2102540">term</span>
  <span m="2102770">doesn''t</span> <span m="2103090">depend</span> <span m="2103440">on</span>
  <span m="2103580">y.</span> <span m="2104110">Only</span> <span m="2104500">this</span>
  <span m="2104750">can</span> <span m="2104950">depends</span> <span m="2105270">on</span>
  <span m="2105390">y,</span> <span m="2106080">right?</span> <span m="2107660">So</span>
  <span m="2107890">what</span> <span m="2108110">I''m</span> <span m="2108230">going</span>
  <span m="2108350">to</span> <span m="2108420">get</span> <span m="2108680">is</span>
  <span m="2108970">k,</span> <span m="2109780">after</span> <span m="2110130">k-th</span>
  <span m="2110750">power</span> <span m="2111180">[INAUDIBLE],</span> <span m="2116140">write</span>
  <span m="2116790">x</span> <span m="2119910">divided</span> <span m="2120300">by</span>
  <span m="2120500">k</span> <span m="2120840">factorial.</span></p><p><span m="2122680">I''m</span>
  <span m="2122880">going</span> <span m="2123020">to</span> <span m="2123130">have</span>
  <span m="2123380">y</span> <span m="2123800">minus</span> <span m="2124210">x</span>
  <span m="2124600">to</span> <span m="2124720">the</span> <span m="2124930">k</span>
  <span m="2125200">minus</span> <span m="2125500">y</span> <span m="2125740">power</span>
  <span m="2126770">times</span> <span m="2127120">another</span> <span m="2127420">k</span>
  <span m="2127770">here.</span> <span m="2130630">So</span> <span m="2130820">this</span>
  <span m="2131120">is</span> <span m="2131270">what</span> <span m="2131440">happens</span>
  <span m="2131800">when</span> <span m="2132020">you</span> <span m="2132220">type</span>
  <span m="2132535">in</span> <span m="2132850">[INAUDIBLE]</span> <span m="2133580">derivative</span>
  <span m="2134550">as a</span> <span m="2135025">Taylor</span> <span m="2135500">series.</span>
  <span m="2137260">And</span> <span m="2137470">now,</span> <span m="2138140">if</span>
  <span m="2138420">you</span> <span m="2139310">expand</span> <span m="2140350">this</span>
  <span m="2140760">term</span> <span m="2142190">at</span> <span m="2142730">t plus</span>
  <span m="2143210">delta</span> <span m="2143660">t,</span> <span m="2144360">you</span>
  <span m="2144540">can</span> <span m="2144750">write</span> <span m="2145150">the</span>
  <span m="2145240">same</span> <span m="2145530">conclusion</span> <span m="2146026">as</span>
  <span m="2146522">we</span> <span m="2147020">previously</span> <span m="2147380">arrived,</span>
  <span m="2148420">which</span> <span m="2148690">is</span> <span m="2149580">our</span>
  <span m="2149960">scheme</span> <span m="2150320">has</span> <span m="2150490">a</span>
  <span m="2150550">truncation</span> <span m="2151080">error</span> <span m="2151410">of</span>
  <span m="2151894">order</span> <span m="2152378">delta</span> <span m="2152862">t.</span>
  <span m="2153346">All</span> <span m="2153830">right,</span> <span m="2154190">let''s</span>
  <span m="2154430">take</span> <span m="2154670">a</span> <span m="2154830">mini</span>
  <span m="2155090">break</span> <span m="2155520">of</span> <span m="2155820">like</span>
  <span m="2156155">five</span> <span m="2156490">minutes</span> <span m="2156970">and</span>
  <span m="2158140">then</span> <span m="2158400">come</span> <span m="2158660">back</span>
  <span m="2158920">to</span> <span m="2159020">our</span> <span m="2159370">lecture.</span></p><p><span
  m="2161795">All</span> <span m="2162280">right,</span> <span m="2162670">so</span>
  <span m="2164400">[INAUDIBLE]</span> <span m="2164890">to</span> <span m="2165290">you</span>
  <span m="2167895">a</span> <span m="2168340">small</span> <span m="2169030">entry</span>
  <span m="2169280">into what</span> <span m="2169710">we are</span> <span m="2170140">going
  to</span> <span m="2170570">be doing</span> <span m="2171070">with</span> <span
  m="2171430">Taylor</span> <span m="2171510">series.</span> <span m="2172630">It''s</span>
  <span m="2173010">not</span> <span m="2173310">going</span> <span m="2173460">to</span>
  <span m="2173540">be</span> <span m="2173800">obvious</span> <span m="2174340">in</span>
  <span m="2174450">the</span> <span m="2174610">beginning,</span> <span m="2174780">but</span>
  <span m="2175120">like,</span> <span m="2175780">this</span> <span m="2176050">is</span>
  <span m="2176170">going</span> <span m="2176616">to</span> <span m="2177062">be</span>
  <span m="2177510">getting</span> <span m="2177810">better and</span> <span m="2178146">better</span>
  <span m="2178482">method</span> <span m="2178820">to</span> <span m="2179120">exercise.</span>
  <span m="2180580">OK,</span> <span m="2181808">[INAUDIBLE].</span></p><p><span m="2183720">OK,</span>
  <span m="2184010">let''s</span> <span m="2184510">get</span> <span m="2184680">back</span>
  <span m="2184940">to</span> <span m="2185300">[INAUDIBLE]</span> <span m="2185570">again.</span>
  <span m="2186060">I''m</span> <span m="2186530">sure</span> <span m="2186740">I</span>
  <span m="2186870">lost</span> <span m="2187170">all</span> <span m="2187350">of</span>
  <span m="2187520">you</span> <span m="2187680">when</span> <span m="2187970">I</span>
  <span m="2188230">talk</span> <span m="2188390">about</span> <span m="2188775">Taylor</span>
  <span m="2189160">series</span> <span m="2190007">of</span> <span m="2190901">t</span>
  <span m="2191348">[INAUDIBLE]</span> <span m="2191795">plus delta</span> <span m="2192242">t.</span>
  <span m="2193140">But</span> <span m="2193770">let''s</span> <span m="2193980">not</span>
  <span m="2194240">get</span> <span m="2195000">[INAUDIBLE]</span> <span m="2195200">onto</span>
  <span m="2195500">this.</span> <span m="2196950">It</span> <span m="2197110">just</span>
  <span m="2197310">requires</span> <span m="2197770">you</span> <span m="2197920">to</span>
  <span m="2198180">go</span> <span m="2198370">back</span> <span m="2198650">and
  look</span> <span m="2199090">at</span> <span m="2199530">Taylor</span> <span m="2200410">series</span>
  <span m="2200740">with</span> <span m="2201620">a</span> <span m="2201870">little
  bit</span> <span m="2201970">more</span> <span m="2203040">familiarity.</span></p><p><span
  m="2205490">OK,</span> <span m="2206200">so</span> <span m="2206420">here</span>
  <span m="2206850">are--</span> <span m="2207210">I''m going to say a</span> <span
  m="2207560">little</span> <span m="2208140">bit</span> <span m="2208320">on</span>
  <span m="2208500">why</span> <span m="2211740">we</span> <span m="2211900">want</span>
  <span m="2212150">to</span> <span m="2212350">approximate</span> <span m="2213430">the</span>
  <span m="2213710">derivative</span> <span m="2215050">and</span> <span m="2215340">how</span>
  <span m="2215630">is</span> <span m="2215930">that</span> <span m="2216170">going</span>
  <span m="2216380">to</span> <span m="2217880">give</span> <span m="2218150">us</span>
  <span m="2219830">a way</span> <span m="2220450">of</span> <span m="2222660">solve</span>
  <span m="2223152">[INAUDIBLE].</span> <span m="2224630">OK,</span> <span m="2225720">so</span>
  <span m="2225910">remember,</span> <span m="2226420">we</span> <span m="2226650">are</span>
  <span m="2226810">approximating</span> <span m="2227830">the</span> <span m="2227970">derivative</span>
  <span m="2228670">df</span> <span m="2228780">dt</span> <span m="2229540">at</span>
  <span m="2229890">time</span> <span m="2230190">equal</span> <span m="2230400">to</span>
  <span m="2230725">t</span> <span m="2231600">at</span> <span m="2232010">f of</span>
  <span m="2232300">t</span> <span m="2232590">plus</span> <span m="2233305">delta</span>
  <span m="2233570">t</span> <span m="2234850">minus</span> <span m="2235105">f of</span>
  <span m="2235360">t,</span> <span m="2236420">right,</span> <span m="2237275">over</span>
  <span m="2237730">delta</span> <span m="2238000">t.</span> <span m="2238810">And</span>
  <span m="2239800">that''s</span> <span m="2240110">not</span> <span m="2241580">an</span>
  <span m="2241730">idea</span> <span m="2242100">I</span> <span m="2242270">proposed.</span>
  <span m="2242560">It''s</span> <span m="2242850">proposed</span> <span m="2243320">by--</span>
  <span m="2244730">sorry,</span> <span m="2245030">what was</span> <span m="2245410">your
  name</span> <span m="2245570">again?</span></p><p><span m="2246006">STUDENT: Ariya.</span></p><p><span
  m="2246878">PROFESSOR: Ariya,</span> <span m="2248190">OK.</span> <span m="2249980">OK,</span>
  <span m="2250760">so</span> <span m="2251730">yeah,</span> <span m="2251990">if</span>
  <span m="2252190">we</span> <span m="2252320">stick</span> <span m="2252570">to</span>
  <span m="2252680">this</span> <span m="2252890">scheme,</span> <span m="2254430">we</span>
  <span m="2254640">can</span> <span m="2255000">actually</span> <span m="2255780">start</span>
  <span m="2256140">to</span> <span m="2256230">integrate</span> <span m="2257330">ODEs.</span>
  <span m="2260140">OK,</span> <span m="2260430">let''s</span> <span m="2260650">call</span>
  <span m="2261090">this</span> <span m="2261960">0</span> <span m="2263150">equal</span>
  <span m="2263630">to</span> <span m="2264220">t0.</span> <span m="2264820">So</span>
  <span m="2265080">that''s</span> <span m="2265380">actually</span> <span m="2265950">how</span>
  <span m="2266740">each</span> <span m="2267320">time</span> <span m="2267645">step</span>
  <span m="2267970">has</span> <span m="2268190">a</span> <span m="2268310">name--</span>
  <span m="2268870">so,</span> <span m="2269140">t1</span> <span m="2269595">equal</span>
  <span m="2269870">to</span> <span m="2270480">delta</span> <span m="2270820">t,</span>
  <span m="2272250">p2</span> <span m="2272860">equal</span> <span m="2273330">to</span>
  <span m="2273580">2</span> <span m="2273790">delta</span> <span m="2273920">t,</span>
  <span m="2274840">et</span> <span m="2275000">cetera.</span></p><p><span m="2276160">And</span>
  <span m="2276350">the</span> <span m="2276410">function</span> <span m="2276900">values--</span>
  <span m="2277250">f</span> <span m="2277640">of</span> <span m="2278000">t</span>
  <span m="2278870">at</span> <span m="2279680">t</span> <span m="2280150">equal to</span>
  <span m="2280470">0.</span> <span m="2280990">I''m</span> <span m="2281370">going</span>
  <span m="2281490">to</span> <span m="2281560">call</span> <span m="2281810">it</span>
  <span m="2282120">f0.</span> <span m="2284170">The</span> <span m="2284280">function</span>
  <span m="2284610">value</span> <span m="2284950">at</span> <span m="2285170">f1,</span>
  <span m="2286030">I''m</span> <span m="2286210">going</span> <span m="2286340">to</span>
  <span m="2286430">call</span> <span m="2286750">it</span> <span m="2287900">t1</span>
  <span m="2288310">equal</span> <span m="2288620">to</span> <span m="2288850">f1.</span>
  <span m="2289700">The</span> <span m="2289890">function</span> <span m="2290350">value</span>
  <span m="2290830">at</span> <span m="2292240">t2,</span> <span m="2292690">I''m</span>
  <span m="2292840">going</span> <span m="2292970">to</span> <span m="2293050">call</span>
  <span m="2293290">it</span> <span m="2293440">f2.</span> <span m="2296460">Now</span>
  <span m="2296710">let''s</span> <span m="2297530">say</span> <span m="2298540">I</span>
  <span m="2298730">have</span> <span m="2298870">an</span> <span m="2298990">ODE</span>
  <span m="2299980">and</span> <span m="2300170">I</span> <span m="2300250">only</span>
  <span m="2300520">have</span> <span m="2300690">the</span> <span m="2300780">solution</span>
  <span m="2301390">at</span> <span m="2302420">t0,</span> <span m="2303080">t1,</span>
  <span m="2303560">t2.</span></p><p><span m="2305150">I</span> <span m="2305310">want</span>
  <span m="2305590">to</span> <span m="2305690">know</span> <span m="2305990">what</span>
  <span m="2306360">is</span> <span m="2306560">the</span> <span m="2306680">solution</span>
  <span m="2307240">at</span> <span m="2307350">the</span> <span m="2307420">next</span>
  <span m="2307800">time</span> <span m="2308242">stamp.</span> <span m="2310010">What</span>
  <span m="2310300">is</span> <span m="2310550">the</span> <span m="2310640">value</span>
  <span m="2311390">of</span> <span m="2311770">f3?</span> <span m="2315410">So</span>
  <span m="2315530">that</span> <span m="2315700">is</span> <span m="2315830">what</span>
  <span m="2316000">happens</span> <span m="2316350">when</span> <span m="2316520">we</span>
  <span m="2316710">solve</span> <span m="2317085">ODEs,</span> <span m="2317460">right?</span>
  <span m="2318110">We</span> <span m="2318300">start</span> <span m="2318720">with</span>
  <span m="2318910">the</span> <span m="2318990">initial</span> <span m="2319380">condition.</span>
  <span m="2320070">We</span> <span m="2320240">start</span> <span m="2320710">with</span>
  <span m="2321390">f0</span> <span m="2322130">that</span> <span m="2322280">is</span>
  <span m="2322450">given.</span> <span m="2324680">The</span> <span m="2324780">test</span>
  <span m="2325110">case</span> <span m="2325320">will</span> <span m="2325430">compute</span>
  <span m="2326060">what</span> <span m="2326540">f1</span> <span m="2326790">si.</span></p><p><span
  m="2328110">And</span> <span m="2328220">now,</span> <span m="2329040">once</span>
  <span m="2329310">I</span> <span m="2329400">computed</span> <span m="2329940">f1,</span>
  <span m="2330650">the</span> <span m="2330860">task</span> <span m="2331260">is</span>
  <span m="2331470">to</span> <span m="2331836">compute what</span> <span m="2332202">f2</span>
  <span m="2332570">is.</span> <span m="2333560">Once</span> <span m="2333800">I</span>
  <span m="2333950">compute</span> <span m="2334400">f2,</span> <span m="2335230">now</span>
  <span m="2335580">the</span> <span m="2335680">task</span> <span m="2336060">is</span>
  <span m="2336210">to</span> <span m="2336340">compute</span> <span m="2336880">what</span>
  <span m="2337180">f3.</span> <span m="2338870">How</span> <span m="2338960">do</span>
  <span m="2339070">I</span> <span m="2339150">compute</span> <span m="2339550">f3?</span></p><p><span
  m="2345900">Yeah,</span> <span m="2346180">how</span> <span m="2346410">do</span>
  <span m="2346520">I</span> <span m="2346620">compute</span> <span m="2347080">f3</span>
  <span m="2347610">using</span> <span m="2347960">Taylor</span> <span m="2348290">data</span>
  <span m="2348610">points.</span> <span m="2349390">So</span> <span m="2349480">here''s</span>
  <span m="2349850">what</span> <span m="2350010">is</span> <span m="2350170">given.</span>
  <span m="2350860">I</span> <span m="2351090">have</span> <span m="2351390">the</span>
  <span m="2351470">ODE.</span> <span m="2352750">I</span> <span m="2353030">have</span>
  <span m="2354090">df</span> <span m="2355570">df</span> <span m="2356870">equal</span>
  <span m="2357390">to</span> <span m="2360600">a</span> <span m="2360770">function</span>
  <span m="2361220">of</span> <span m="2361380">f.</span> <span m="2365710">Let''s</span>
  <span m="2366070">say--</span> <span m="2366460">I''m</span> <span m="2366620">going</span>
  <span m="2366760">to</span> <span m="2366920">say</span> <span m="2367140">minus</span>
  <span m="2367650">lambda</span> <span m="2368062">times</span> <span m="2368474">f.</span>
  <span m="2371740">So</span> <span m="2371970">here''s</span> <span m="2373970">my</span>
  <span m="2374110">single</span> <span m="2374290">ODE</span> <span m="2375260">I</span>
  <span m="2375400">need</span> <span m="2375610">to</span> <span m="2376150">integrate.</span></p><p><span
  m="2377930">And</span> <span m="2378400">I</span> <span m="2378590">can</span> <span
  m="2379000">approximate--</span> <span m="2380460">I</span> <span m="2380630">have</span>
  <span m="2380830">an</span> <span m="2380970">approximation</span> <span m="2381850">to</span>
  <span m="2381950">the</span> <span m="2382120">derivative.</span> <span m="2385300">And</span>
  <span m="2385500">I</span> <span m="2385530">also</span> <span m="2385880">have</span>
  <span m="2386120">f0,</span> <span m="2386730">f1,</span> <span m="2387350">f2.</span>
  <span m="2388185">How do</span> <span m="2388480">I</span> <span m="2388640">compute</span>
  <span m="2389050">f3?</span></p><p><span m="2394350">So</span> <span m="2394530">this</span>
  <span m="2394700">is</span> <span m="2394830">given.</span> <span m="2396190">This</span>
  <span m="2396460">is</span> <span m="2396630">given.</span> <span m="2398280">This</span>
  <span m="2398550">is</span> <span m="2398680">given.</span></p><p><span m="2399010">This</span>
  <span m="2399200">is</span> <span m="2399340">given.</span> <span m="2399670">This
  is</span> <span m="2399820">given.</span> <span m="2405620">How do</span> <span
  m="2405880">I</span> <span m="2405950">put</span> <span m="2406460">them</span>
  <span m="2406720">together</span> <span m="2407640">to</span> <span m="2408100">compute</span>
  <span m="2408330">[INAUDIBLE]?</span></p><p><span m="2409110">STUDENT: [INAUDIBLE]</span></p><p><span
  m="2421310">PROFESSOR: Right,</span> <span m="2421650">we</span> <span m="2422620">have</span>
  <span m="2425490">our</span> <span m="2425780">function</span> <span m="2426250">value</span>
  <span m="2426830">at</span> <span m="2427280">f2.</span> <span m="2427810">We</span>
  <span m="2427980">also</span> <span m="2428440">have</span> <span m="2428730">an</span>
  <span m="2429010">estimate</span> <span m="2430330">of</span> <span m="2430650">the</span>
  <span m="2430980">derivative</span> <span m="2431570">at</span> <span m="2431855">f2,</span>
  <span m="2433610">which</span> <span m="2434030">actually</span> <span m="2434530">involved</span>
  <span m="2435570">the</span> <span m="2435850">unknown.</span> <span m="2436530">So</span>
  <span m="2436660">let</span> <span m="2437250">me</span> <span m="2437400">write</span>
  <span m="2437720">down--</span> <span m="2438430">let</span> <span m="2438670">me</span>
  <span m="2438790">write</span> <span m="2439050">down--</span> <span m="2439510">this</span>
  <span m="2439640">is</span> <span m="2439760">important.</span> <span m="2440160">Let</span>
  <span m="2440350">me</span> <span m="2440430">write</span> <span m="2440650">down</span>
  <span m="2440870">what</span> <span m="2441050">is</span> <span m="2441230">the</span>
  <span m="2441330">derivative</span> <span m="2441645">estimate</span> <span m="2442343">at</span>
  <span m="2442726">f2--</span> <span m="2445090">at</span> <span m="2445470">t2,</span>
  <span m="2446180">sorry.</span></p><p><span m="2447100">It</span> <span m="2447290">is</span>
  <span m="2447460">equal</span> <span m="2447820">to</span> <span m="2448310">f</span>
  <span m="2449130">of</span> <span m="2449370">t</span> <span m="2449770">plus</span>
  <span m="2450070">delta</span> <span m="2450190">t,</span> <span m="2450400">which</span>
  <span m="2450610">is</span> <span m="2450750">t3,</span> <span m="2451060">right?</span>
  <span m="2451370">This is</span> <span m="2451855">t3</span> <span m="2454280">minus</span>
  <span m="2455280">f</span> <span m="2455640">at</span> <span m="2456390">t2</span>
  <span m="2458000">divided</span> <span m="2458470">by</span> <span m="2458870">delta</span>
  <span m="2459080">t.</span> <span m="2461760">This</span> <span m="2462120">actually</span>
  <span m="2462750">involves</span> <span m="2463320">an</span> <span m="2463800">unknown</span>
  <span m="2465720">in</span> <span m="2465910">the</span> <span m="2466000">derivative.</span>
  <span m="2470940">And</span> <span m="2471390">this</span> <span m="2472050">is</span>
  <span m="2473290">df</span> <span m="2473420">dt</span> <span m="2474010">by</span>
  <span m="2474670">the</span> <span m="2474880">differential</span> <span m="2475480">equation</span>
  <span m="2476070">is</span> <span m="2476380">equal</span> <span m="2476680">to</span>
  <span m="2476770">minus</span> <span m="2477310">lambda</span> <span m="2478676">times</span>
  <span m="2479040">f</span> <span m="2479620">at,</span> <span m="2479970">what?</span>
  <span m="2480800">Is</span> <span m="2482120">t2.</span> <span m="2487710">Now,</span>
  <span m="2488940">through</span> <span m="2489325">this,</span> <span m="2490340">by</span>
  <span m="2490580">plotting</span> <span m="2491310">both</span> <span m="2492150">the</span>
  <span m="2492380">approximation</span> <span m="2493320">of</span> <span m="2493470">the</span>
  <span m="2493550">derivative</span> <span m="2494270">and--</span> <span m="2495720">by</span>
  <span m="2496070">basically</span> <span m="2496400">putting</span> <span m="2496800">both</span>
  <span m="2497150">the</span> <span m="2497480">approximation</span> <span m="2498050">of</span>
  <span m="2498130">the</span> <span m="2498210">derivative</span> <span m="2498710">and</span>
  <span m="2499030">the</span> <span m="2499260">function</span> <span m="2499620">together,</span>
  <span m="2501590">we</span> <span m="2501830">converted</span> <span m="2502540">the</span>
  <span m="2502620">differential</span> <span m="2503230">equation</span> <span m="2503670">into</span>
  <span m="2504080">a</span> <span m="2504490">what</span> <span m="2505000">equation?</span></p><p><span
  m="2507082">STUDENT: [INAUDIBLE]</span></p><p><span m="2508070">PROFESSOR: Yeah,</span>
  <span m="2508350">into</span> <span m="2508550">a</span> <span m="2508610">difference</span>
  <span m="2509070">equation,</span> <span m="2509460">into</span> <span m="2509580">a</span>
  <span m="2509780">[INAUDIBLE]</span> <span m="2510420">equation.</span> <span m="2510830">We
  can</span> <span m="2511240">just</span> <span m="2512060">compute.</span> <span
  m="2514940">So</span> <span m="2515240">let</span> <span m="2515540">me</span> <span
  m="2515670">color</span> <span m="2516150">this.</span> <span m="2518240">This</span>
  <span m="2518450">is</span> <span m="2518660">unknown,</span> <span m="2521150">this</span>
  <span m="2521470">is</span> <span m="2521620">known,</span> <span m="2522560">and</span>
  <span m="2522770">this</span> <span m="2522940">is</span> <span m="2523080">known.</span></p><p><span
  m="2526090">We</span> <span m="2526240">can</span> <span m="2526460">just</span>
  <span m="2526820">move</span> <span m="2527540">all</span> <span m="2527770">the</span>
  <span m="2527880">unknowns</span> <span m="2528610">to</span> <span m="2528780">one</span>
  <span m="2529100">side.</span> <span m="2529710">So</span> <span m="2529990">f</span>
  <span m="2530270">of</span> <span m="2530470">t3</span> <span m="2530870">is</span>
  <span m="2531000">my</span> <span m="2531180">f3</span> <span m="2533100">is</span>
  <span m="2533530">equal</span> <span m="2534030">to</span> <span m="2535720">all</span>
  <span m="2535920">the</span> <span m="2536010">known</span> <span m="2536410">on</span>
  <span m="2536570">the</span> <span m="2536670">other</span> <span m="2536900">side.</span>
  <span m="2537910">f</span> <span m="2538180">of</span> <span m="2538600">t2</span>
  <span m="2538760">is</span> <span m="2538960">f2</span> <span m="2541090">minus</span>
  <span m="2542800">delta</span> <span m="2543320">t</span> <span m="2543990">times</span>
  <span m="2544360">lambda</span> <span m="2545000">times</span> <span m="2545336">f</span>
  <span m="2545672">of</span> <span m="2546010">t</span> <span m="2546270">to</span>
  <span m="2546650">[INAUDIBLE]</span> <span m="2546760">2.</span></p><p><span m="2549170">Right,</span>
  <span m="2550960">by</span> <span m="2551130">doing</span> <span m="2551560">this,</span>
  <span m="2552450">I</span> <span m="2552600">compute</span> <span m="2553470">F3</span>
  <span m="2554860">out</span> <span m="2555190">of</span> <span m="2555370">f2.</span>
  <span m="2558390">Now,</span> <span m="2558600">what</span> <span m="2558760">do</span>
  <span m="2558860">I</span> <span m="2558930">do</span> <span m="2559180">when</span>
  <span m="2559430">I--</span> <span m="2560280">now</span> <span m="2560590">I</span>
  <span m="2560720">have</span> <span m="2561150">f3.</span> <span m="2561410">What</span>
  <span m="2561620">do I</span> <span m="2561790">do</span> <span m="2562100">when</span>
  <span m="2562310">I</span> <span m="2562410">want</span> <span m="2562590">to</span>
  <span m="2562895">compute</span> <span m="2563200">f4?</span></p><p><span m="2565880">Same</span>
  <span m="2566160">thing,</span> <span m="2566470">right?</span> <span m="2566810">It''s</span>
  <span m="2567110">kind</span> <span m="2567310">of</span> <span m="2568050">recursive</span>
  <span m="2568840">because</span> <span m="2569220">my</span> <span m="2569440">f4</span>
  <span m="2570220">is</span> <span m="2570500">now</span> <span m="2571200">equal</span>
  <span m="2571530">to</span> <span m="2571710">f3</span> <span m="2572380">minus</span>
  <span m="2573282">delta</span> <span m="2573704">t</span> <span m="2574126">lambda</span>
  <span m="2574550">f3,</span> <span m="2576130">right?</span> <span m="2576560">And</span>
  <span m="2576790">I</span> <span m="2576850">just</span> <span m="2577040">could</span>
  <span m="2577200">go</span> <span m="2577400">on.</span> <span m="2578500">The</span>
  <span m="2578700">only</span> <span m="2579010">thing</span> <span m="2579530">I</span>
  <span m="2579730">need</span> <span m="2580470">is</span> <span m="2581060">to</span>
  <span m="2581250">plug</span> <span m="2581680">in</span> <span m="2583350">the</span>
  <span m="2584080">derivative</span> <span m="2584950">approximation</span> <span
  m="2585710">here</span> <span m="2586070">into</span> <span m="2586550">the</span>
  <span m="2586680">differential</span> <span m="2586930">equation.</span></p><p><span
  m="2594050">Let</span> <span m="2594680">me</span> <span m="2594800">do</span> <span
  m="2595030">it</span> <span m="2595170">again</span> <span m="2595830">using</span>
  <span m="2596230">another</span> <span m="2596670">different</span> <span m="2600262">scheme.</span>
  <span m="2605498">[INAUDIBLE]</span> <span m="2605974">me do</span> <span m="2606450">this</span>
  <span m="2606926">[INAUDIBLE].</span> <span m="2608370">OK,</span> <span m="2610280">different</span>
  <span m="2610630">scheme.</span></p><p><span m="2617300">OK,</span> <span m="2617570">another</span>
  <span m="2617890">way</span> <span m="2618050">to</span> <span m="2618220">approximate</span>
  <span m="2619370">the</span> <span m="2619530">function--</span> <span m="2621130">I</span>
  <span m="2621240">mean,</span> <span m="2621460">I</span> <span m="2621600">have</span>
  <span m="2621730">been</span> <span m="2621930">calling</span> <span m="2622230">the</span>
  <span m="2622300">function</span> <span m="2622660">f,</span> <span m="2623050">but</span>
  <span m="2623466">like,</span> <span m="2624300">because</span> <span m="2624680">we</span>
  <span m="2624800">started</span> <span m="2625290">by</span> <span m="2626620">discretizing</span>
  <span m="2627320">a</span> <span m="2627410">function.</span> <span m="2628520">But,</span>
  <span m="2628710">like,</span> <span m="2629060">in</span> <span m="2629410">[INAUDIBLE]</span>
  <span m="2629860">ODEs,</span> <span m="2630710">it</span> <span m="2630950">is</span>
  <span m="2631130">more</span> <span m="2632090">convention</span> <span m="2632720">to</span>
  <span m="2632840">call</span> <span m="2633190">the</span> <span m="2633290">solution</span>
  <span m="2634060">u.</span> <span m="2635130">So</span> <span m="2635290">from</span>
  <span m="2635530">now</span> <span m="2635740">on,</span> <span m="2635880">I''m</span>
  <span m="2636060">just</span> <span m="2636300">going</span> <span m="2636430">to</span>
  <span m="2636570">call my</span> <span m="2636972">function</span> <span m="2637374">as</span>
  <span m="2638180">u</span> <span m="2638490">of</span> <span m="2638650">t</span>
  <span m="2639106">instead of</span> <span m="2639562">f of t.</span></p><p><span
  m="2640020">This</span> <span m="2640210">is</span> <span m="2640390">just</span>
  <span m="2641116">a--</span> <span m="2642484">but,</span> <span m="2642940">like,</span>
  <span m="2643220">everything</span> <span m="2643590">else</span> <span m="2643830">is</span>
  <span m="2643990">the</span> <span m="2644080">same.</span> <span m="2645606">[INAUDIBLE]</span>
  <span m="2646500">with</span> <span m="2646810">this,</span> <span m="2647120">we''ll</span>
  <span m="2647330">just</span> <span m="2648190">call</span> <span m="2648330">it</span>
  <span m="2648480">u of</span> <span m="2648700">t.</span> <span m="2650170">OK,</span>
  <span m="2651220">u</span> <span m="2651500">of</span> <span m="2651958">t,</span>
  <span m="2654248">I</span> <span m="2654706">have</span> <span m="2655900">du</span>
  <span m="2656680">dt</span> <span m="2657600">equal</span> <span m="2658020">to</span>
  <span m="2658150">minus</span> <span m="2658610">lambda</span> <span m="2659200">times</span>
  <span m="2659950">u of</span> <span m="2660130">t.</span></p><p><span m="2661850">I''m</span>
  <span m="2662060">going</span> <span m="2662270">to</span> <span m="2662520">devise</span>
  <span m="2663420">another</span> <span m="2664330">scheme</span> <span m="2665590">of</span>
  <span m="2665940">approximating</span> <span m="2666830">the</span> <span m="2666910">derivative.</span>
  <span m="2668450">I</span> <span m="2668620">have</span> <span m="2669430">du</span>
  <span m="2670400">dt</span> <span m="2671230">at</span> <span m="2672250">a</span>
  <span m="2672420">certain</span> <span m="2672780">time</span> <span m="2673125">t</span>
  <span m="2673930">equal</span> <span m="2674440">to</span> <span m="2675320">u</span>
  <span m="2675820">at</span> <span m="2676230">t</span> <span m="2676590">plus</span>
  <span m="2677030">delta</span> <span m="2677190">t</span> <span m="2678020">minus</span>
  <span m="2678490">u</span> <span m="2678890">at</span> <span m="2681280">t</span>
  <span m="2681690">minus</span> <span m="2682150">delta</span> <span m="2682470">t</span>
  <span m="2683220">divided</span> <span m="2683640">by</span> <span m="2683840">2</span>
  <span m="2684340">delta</span> <span m="2684840">t.</span> <span m="2689780">OK,</span>
  <span m="2690050">so</span> <span m="2690180">let''s</span> <span m="2690570">do</span>
  <span m="2690770">two</span> <span m="2690990">things.</span></p><p><span m="2692190">One</span>
  <span m="2692350">is,</span> <span m="2693440">why</span> <span m="2694020">is</span>
  <span m="2694370">this</span> <span m="2695290">a</span> <span m="2695440">[INAUDIBLE]</span>
  <span m="2696110">approximation</span> <span m="2696920">to</span> <span m="2697080">the</span>
  <span m="2697310">derivative?</span> <span m="2699420">Two--</span> <span m="2700500">now,</span>
  <span m="2700770">if</span> <span m="2701080">this</span> <span m="2701280">is</span>
  <span m="2701430">a</span> <span m="2701490">valid</span> <span m="2701910">approximation</span>
  <span m="2702600">of</span> <span m="2702710">the</span> <span m="2702790">derivative,</span>
  <span m="2703440">how</span> <span m="2703660">do</span> <span m="2703790">I</span>
  <span m="2703900">make</span> <span m="2704170">this</span> <span m="2704470">a</span>
  <span m="2704770">[INAUDIBLE]</span> <span m="2706090">of</span> <span m="2706250">[INAUDIBLE]</span>
  <span m="2706723">ODE?</span> <span m="2710510">So,</span> <span m="2710640">anybody</span>
  <span m="2711440">have</span> <span m="2711960">an</span> <span m="2712180">idea</span>
  <span m="2712690">to</span> <span m="2712850">how</span> <span m="2713020">to</span>
  <span m="2713370">answer</span> <span m="2713590">either of</span> <span m="2713990">these</span>
  <span m="2714390">[INAUDIBLE]?</span> <span m="2715190">Yes?</span></p><p><span
  m="2715616">STUDENT: [INAUDIBLE]</span></p><p><span m="2719790">PROFESSOR: It''s</span>
  <span m="2720020">the</span> <span m="2720200">definition</span> <span m="2720850">of</span>
  <span m="2720960">the</span> <span m="2721030">derivative,</span> <span m="2721660">but</span>
  <span m="2721770">the</span> <span m="2721850">definition</span> <span m="2722380">of</span>
  <span m="2722470">the</span> <span m="2722540">derivative</span> <span m="2722865">is</span>
  <span m="2723190">also</span> <span m="2723490">[INAUDIBLE],</span> <span m="2723770">yes?</span></p><p><span
  m="2724264">STUDENT: [INAUDIBLE]</span></p><p><span m="2747976">PROFESSOR: Good.</span>
  <span m="2749970">After</span> <span m="2750120">the</span> <span m="2750340">[INAUDIBLE]</span>
  <span m="2751040">problems,</span> <span m="2752030">it</span> <span m="2752200">can</span>
  <span m="2752370">be</span> <span m="2752490">solved</span> <span m="2752850">using</span>
  <span m="2753160">Taylor</span> <span m="2753625">series</span> <span m="2754090">[INAUDIBLE].</span>
  <span m="2755950">OK,</span> <span m="2756390">it''s</span> <span m="2756850">good.</span></p><p><span
  m="2757310">So,</span> <span m="2757520">answer</span> <span m="2757810">to</span>
  <span m="2757920">the</span> <span m="2758020">first</span> <span m="2758330">question--</span>
  <span m="2759770">y</span> <span m="2761140">is</span> <span m="2763390">a</span>
  <span m="2763420">good</span> <span m="2763800">approximation.</span> <span m="2768990">OK,</span>
  <span m="2769430">to</span> <span m="2769610">answer</span> <span m="2769860">that,</span>
  <span m="2771070">again</span> <span m="2771560">we</span> <span m="2771740">use</span>
  <span m="2772290">Taylor</span> <span m="2772700">series.</span> <span m="2778080">u</span>
  <span m="2778490">at</span> <span m="2778960">t</span> <span m="2779160">plus</span>
  <span m="2779510">delta</span> <span m="2779860">t--</span> <span m="2780470">as</span>
  <span m="2780700">usual,</span> <span m="2781150">we</span> <span m="2781340">are</span>
  <span m="2781410">going</span> <span m="2781540">to</span> <span m="2781600">be</span>
  <span m="2781730">expanding</span> <span m="2782360">it</span> <span m="2782890">using</span>
  <span m="2783910">u</span> <span m="2784410">and</span> <span m="2784878">t</span>
  <span m="2786282">plus</span> <span m="2786750">du</span> <span m="2787690">dt</span>
  <span m="2788180">at</span> <span m="2788540">t</span> <span m="2789070">times</span>
  <span m="2789547">delta</span> <span m="2790024">t</span> <span m="2790980">plus</span>
  <span m="2791255">o</span> <span m="2791530">delta</span> <span m="2791680">t</span>
  <span m="2792170">square,</span> <span m="2792500">right?</span> <span m="2792880">This</span>
  <span m="2793090">is</span> <span m="2793640">the</span> <span m="2793760">same</span>
  <span m="2794070">thing</span> <span m="2794350">as</span> <span m="2794570">we</span>
  <span m="2794740">did</span> <span m="2795350">of</span> <span m="2795530">the</span>
  <span m="2795962">other</span> <span m="2796394">scheme.</span></p><p><span m="2796826">The</span>
  <span m="2797260">other</span> <span m="2797470">scheme</span> <span m="2798120">is</span>
  <span m="2798570">[INAUDIBLE],</span> <span m="2800010">right?</span> <span m="2801010">Remember</span>
  <span m="2801640">your</span> <span m="2802140">reading.</span> <span m="2804570">And</span>
  <span m="2805470">ut</span> <span m="2805750">minus</span> <span m="2807190">delta</span>
  <span m="2807590">t--</span> <span m="2807990">how</span> <span m="2808070">do</span>
  <span m="2808180">I</span> <span m="2808400">expand</span> <span m="2808690">that?</span>
  <span m="2813480">Yes.</span></p><p><span m="2813770">STUDENT: [INAUDIBLE]</span></p><p><span
  m="2818390">Good.</span> <span m="2818880">It''s</span> <span m="2819180">the</span>
  <span m="2819390">same</span> <span m="2819830">thing</span> <span m="2820200">except</span>
  <span m="2820740">for</span> <span m="2820900">the</span> <span m="2820970">distance</span>
  <span m="2821430">between</span> <span m="2822150">this</span> <span m="2822440">t</span>
  <span m="2822720">minus</span> <span m="2822870">delta</span> <span m="2823160">t</span>
  <span m="2823850">and</span> <span m="2824120">t</span> <span m="2825870">is</span>
  <span m="2826090">minus</span> <span m="2826330">delta</span> <span m="2826800">t,</span>
  <span m="2827600">right?</span> <span m="2828330">So</span> <span m="2828880">in</span>
  <span m="2829350">here,</span> <span m="2829690">the</span> <span m="2829770">distance</span>
  <span m="2830310">between</span> <span m="2830790">this</span> <span m="2831040">variable</span>
  <span m="2831750">and</span> <span m="2831890">this</span> <span m="2832100">variable</span>
  <span m="2832500">is</span> <span m="2832670">delta</span> <span m="2832950">t.</span>
  <span m="2833570">Here,</span> <span m="2833890">the</span> <span m="2833990">distance</span>
  <span m="2834440">between</span> <span m="2834690">this</span> <span m="2834870">variable</span>
  <span m="2835450">and</span> <span m="2835500">this</span> <span m="2835680">variable</span>
  <span m="2836010">is</span> <span m="2836340">minus</span> <span m="2836786">delta</span>
  <span m="2837232">t.</span></p><p><span m="2837680">Therefore,</span> <span m="2838500">all</span>
  <span m="2838830">the</span> <span m="2839120">values</span> <span m="2839690">and</span>
  <span m="2839860">derivative</span> <span m="2840570">is</span> <span m="2840760">the</span>
  <span m="2840920">same</span> <span m="2841410">except</span> <span m="2841675">for</span>
  <span m="2842400">here,</span> <span m="2842720">I</span> <span m="2842910">put</span>
  <span m="2843190">minus</span> <span m="2843510">delta</span> <span m="2843920">t.</span>
  <span m="2844720">And</span> <span m="2845140">o,</span> <span m="2845960">it</span>
  <span m="2846170">should</span> <span m="2846370">be</span> <span m="2846550">minus</span>
  <span m="2846990">delta</span> <span m="2847290">t</span> <span m="2847880">to</span>
  <span m="2848020">the</span> <span m="2848110">q.</span> <span m="2848445">But</span>
  <span m="2848780">does it</span> <span m="2849050">matter?</span> <span m="2851580">No,</span>
  <span m="2853660">in</span> <span m="2854040">the</span> <span m="2854160">big O</span>
  <span m="2854630">notation,</span> <span m="2855350">the</span> <span m="2855450">constant</span>
  <span m="2855840">coefficients,</span> <span m="2856480">[INAUDIBLE]</span> <span
  m="2856900">the</span> <span m="2856970">terms</span> <span m="2857080">doesn''t</span>
  <span m="2857240">matter,</span> <span m="2859090">right?</span> <span m="2859920">So</span>
  <span m="2860130">minus</span> <span m="2861560">O</span> <span m="2861820">delta</span>
  <span m="2862070">t</span> <span m="2862200">square</span> <span m="2862460">is</span>
  <span m="2862600">the</span> <span m="2862720">same</span> <span m="2863050">as</span>
  <span m="2863300">o</span> <span m="2863540">delta</span> <span m="2863630">t</span>
  <span m="2863850">square,</span> <span m="2864550">is</span> <span m="2864740">the</span>
  <span m="2864830">same</span> <span m="2865210">as</span> <span m="2865930">five</span>
  <span m="2866280">times</span> <span m="2867500">o</span> <span m="2867660">delta</span>
  <span m="2867810">t</span> <span m="2867940">square.</span> <span m="2868970">It''s</span>
  <span m="2869200">the</span> <span m="2869310">same</span> <span m="2869610">as</span>
  <span m="2869890">1</span> <span m="2869990">million</span> <span m="2870480">times</span>
  <span m="2870880">over</span> <span m="2871330">delta</span> <span m="2871510">t</span>
  <span m="2871680">square.</span> <span m="2872040">As</span> <span m="2872320">long</span>
  <span m="2872570">as</span> <span m="2872920">the</span> <span m="2873060">terms</span>
  <span m="2874010">have</span> <span m="2874550">delta</span> <span m="2874950">t</span>
  <span m="2875060">square</span> <span m="2875390">in</span> <span m="2875560">front</span>
  <span m="2875850">of</span> <span m="2876030">it,</span> <span m="2876790">no</span>
  <span m="2876960">matter</span> <span m="2877440">if</span> <span m="2877680">it''s</span>
  <span m="2878240">multiplied</span> <span m="2878840">by</span> <span m="2879050">1</span>
  <span m="2879120">million</span> <span m="2879550">or</span> <span m="2879840">1
  million</span> <span m="2880200">or</span> <span m="2880480">1</span> <span m="2880905">trillion,</span>
  <span m="2881330">it</span> <span m="2881450">doesn''t</span> <span m="2881660">matter.</span></p><p><span
  m="2881970">It''s</span> <span m="2882190">o</span> <span m="2882600">delta</span>
  <span m="2883070">t</span> <span m="2883270">squared.</span> <span m="2884220">If</span>
  <span m="2884440">it''s</span> <span m="2884590">multiplied</span> <span m="2885080">by</span>
  <span m="2885200">minus</span> <span m="2885600">1,</span> <span m="2885820">it''s</span>
  <span m="2886170">still</span> <span m="2886600">o</span> <span m="2887062">delta</span>
  <span m="2887524">t</span> <span m="2887986">squared,</span> <span m="2888450">right?</span>
  <span m="2890770">OK,</span> <span m="2891570">so</span> <span m="2891800">now,</span>
  <span m="2894270">when</span> <span m="2894490">I</span> <span m="2895210">plug</span>
  <span m="2895515">in</span> <span m="2895820">both</span> <span m="2896790">approximations</span>
  <span m="2897910">into</span> <span m="2898220">this</span> <span m="2898450">formula,</span>
  <span m="2900394">t</span> <span m="2900880">plus</span> <span m="2901370">delta</span>
  <span m="2901550">t</span> <span m="2902130">minus</span> <span m="2902550">u</span>
  <span m="2902970">t</span> <span m="2903810">minus</span> <span m="2903990">delta</span>
  <span m="2904220">t</span> <span m="2904960">over</span> <span m="2905340">2</span>
  <span m="2905720">delta</span> <span m="2906100">t,</span> <span m="2906880">is</span>
  <span m="2907160">equal</span> <span m="2907450">to--</span> <span m="2907610">these</span>
  <span m="2907870">two</span> <span m="2908060">terms</span> <span m="2908280">cancel</span>
  <span m="2908640">out.</span> <span m="2911020">These</span> <span m="2911470">two</span>
  <span m="2911650">terms--</span> <span m="2912360">they</span> <span m="2912560">actually</span>
  <span m="2912970">have</span> <span m="2913170">different</span> <span m="2913550">signs.</span></p><p><span
  m="2913970">So</span> <span m="2914080">they</span> <span m="2914220">become</span>
  <span m="2914710">[INAUDIBLE]</span> <span m="2915640">2</span> <span m="2915880">times</span>
  <span m="2916110">delta</span> <span m="2916520">t.</span> <span m="2917340">Du</span>
  <span m="2918390">dt</span> <span m="2919870">plus--</span> <span m="2921550">I''m</span>
  <span m="2921710">just</span> <span m="2921840">going</span> <span m="2921980">to</span>
  <span m="2922050">write</span> <span m="2922240">this</span> <span m="2922390">down.</span>
  <span m="2922780">What</span> <span m="2922950">is</span> <span m="2923090">this</span>
  <span m="2923280">plus?</span> <span m="2923730">What</span> <span m="2924000">is</span>
  <span m="2924220">the</span> <span m="2924380">difference</span> <span m="2924970">between</span>
  <span m="2925390">these</span> <span m="2925650">2</span> <span m="2926130">o</span>
  <span m="2926380">delta</span> <span m="2926570">t''s?</span> <span m="2929080">Do
  they</span> <span m="2929560">cancel</span> <span m="2929670">out?</span> <span
  m="2931910">No?</span></p><p><span m="2932678">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="2934430">PROFESSOR: It''s</span> <span m="2934720">still</span> <span m="2934850">o</span>
  <span m="2935000">delta</span> <span m="2935390">t</span> <span m="2936540">square.</span>
  <span m="2937020">Why?</span></p><p><span m="2938702">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="2940650">PROFESSOR: Exactly,</span> <span m="2941260">because</span> <span m="2941590">they</span>
  <span m="2941690">don''t</span> <span m="2941960">know</span> <span m="2942090">what</span>
  <span m="2942210">the</span> <span m="2942280">coefficients</span> <span m="2942860">are.</span>
  <span m="2943120">Maybe</span> <span m="2943480">one</span> <span m="2943800">of</span>
  <span m="2943910">these</span> <span m="2944130">[INAUDIBLE]</span> <span m="2944800">has</span>
  <span m="2944960">1</span> <span m="2945040">million</span> <span m="2945440">in
  front</span> <span m="2945863">of it.</span> <span m="2946710">The</span> <span
  m="2946930">other</span> <span m="2947220">o</span> <span m="2947400">del</span>
  <span m="2947520">t</span> <span m="2947780">has</span> <span m="2948090">a</span>
  <span m="2948810">0.001</span> <span m="2949740">in</span> <span m="2949900">front</span>
  <span m="2950286">of it.</span></p><p><span m="2951060">So</span> <span m="2951250">no</span>
  <span m="2951470">matter</span> <span m="2951830">the</span> <span m="2952020">summation</span>
  <span m="2952810">of</span> <span m="2952990">them</span> <span m="2953290">or</span>
  <span m="2953380">the</span> <span m="2953510">difference</span> <span m="2953820">between</span>
  <span m="2954130">them,</span> <span m="2954573">they</span> <span m="2955460">are</span>
  <span m="2955990">still</span> <span m="2956260">o</span> <span m="2956690">delta</span>
  <span m="2957120">t.</span> <span m="2957980">So</span> <span m="2958360">this</span>
  <span m="2958650">is</span> <span m="2958860">going</span> <span m="2959020">to</span>
  <span m="2959110">be--</span> <span m="2960750">these</span> <span m="2961000">two</span>
  <span m="2961160">cancel</span> <span m="2961550">out.</span> <span m="2962290">du</span>
  <span m="2963500">dt,</span> <span m="2964540">this</span> <span m="2964780">is</span>
  <span m="2964930">at</span> <span m="2965420">t,</span> <span m="2965910">plus--</span>
  <span m="2967380">again,</span> <span m="2967880">this</span> <span m="2968140">o</span>
  <span m="2968450">delta</span> <span m="2968760">t</span> <span m="2969130">squared</span>
  <span m="2969400">divided</span> <span m="2969640">by delta</span> <span m="2970030">t,</span>
  <span m="2970380">it</span> <span m="2970530">becomes</span> <span m="2970984">o</span>
  <span m="2971438">delta</span> <span m="2971892">t,</span> <span m="2973710">right?</span>
  <span m="2977940">OK,</span> <span m="2979290">so</span> <span m="2979550">this</span>
  <span m="2979930">is</span> <span m="2980860">still</span> <span m="2981240">a</span>
  <span m="2981320">good</span> <span m="2981630">approximation,</span> <span m="2982450">because</span>
  <span m="2982650">the</span> <span m="2982720">difference</span> <span m="2983120">between</span>
  <span m="2983435">them</span> <span m="2983750">is</span> <span m="2984010">o</span>
  <span m="2984478">delta</span> <span m="2984946">t.</span> <span m="2987290">And</span>
  <span m="2987630">it</span> <span m="2987810">is</span> <span m="2988000">actually</span>
  <span m="2989120">stronger</span> <span m="2989560">than</span> <span m="2989810">o</span>
  <span m="2989980">delta</span> <span m="2990100">t</span> <span m="2990480">because</span>
  <span m="2992340">in</span> <span m="2992530">these</span> <span m="2992720">two</span>
  <span m="2992920">Taylor</span> <span m="2993130">series</span> <span m="2993640">expansions,</span>
  <span m="2994140">you</span> <span m="2994250">can</span> <span m="2994490">expend</span>
  <span m="2995040">more</span> <span m="2995290">terms.</span></p><p><span m="2996540">And</span>
  <span m="2996840">you''re</span> <span m="2996960">going to</span> <span m="2997100">find</span>
  <span m="2997490">out</span> <span m="2997670">that</span> <span m="2997810">coefficients</span>
  <span m="2998490">before</span> <span m="2998820">[INAUDIBLE]</span> <span m="2998990">these</span>
  <span m="2999220">o</span> <span m="2999410">delta</span> <span m="2999570">t</span>
  <span m="2999760">squares</span> <span m="3000198">before</span> <span m="3000636">the</span>
  <span m="3001074">delta</span> <span m="3001512">t</span> <span m="3001950">squares</span>
  <span m="3002390">still</span> <span m="3002890">are</span> <span m="3003010">going</span>
  <span m="3003280">to</span> <span m="3003490">cancel</span> <span m="3003530">out.</span>
  <span m="3004910">So</span> <span m="3005100">you''re</span> <span m="3005260">going</span>
  <span m="3005380">to</span> <span m="3005450">get</span> <span m="3005860">o</span>
  <span m="3006310">delta</span> <span m="3006760">t</span> <span m="3007210">cubed</span>
  <span m="3008290">out</span> <span m="3008500">of</span> <span m="3008630">these</span>
  <span m="3008910">Taylor</span> <span m="3009320">series</span> <span m="3009700">[INAUDIBLE].</span>
  <span m="3010200">And</span> <span m="3010410">over</span> <span m="3010700">here,</span>
  <span m="3010880">you</span> <span m="3010980">can</span> <span m="3011100">actually</span>
  <span m="3011530">prove</span> <span m="3011880">that--</span> <span m="3012630">it''s</span>
  <span m="3013110">in</span> <span m="3013410">the</span> <span m="3013490">reading.</span>
  <span m="3014380">You</span> <span m="3014510">can</span> <span m="3014700">prove</span>
  <span m="3015050">that</span> <span m="3015690">this</span> <span m="3015970">is</span>
  <span m="3016190">not</span> <span m="3016510">only</span> <span m="3017090">o</span>
  <span m="3017410">delta</span> <span m="3017690">t</span> <span m="3017970">but</span>
  <span m="3018220">also</span> <span m="3018690">o</span> <span m="3018990">delta</span>
  <span m="3019160">t</span> <span m="3019435">square.</span></p><p><span m="3023020">It''s</span>
  <span m="3023180">a</span> <span m="3023220">confusing</span> <span m="3023770">[INAUDIBLE]</span>
  <span m="3024600">conflict</span> <span m="3025070">itself.</span> <span m="3025860">We''re</span>
  <span m="3025980">saying</span> <span m="3026400">that</span> <span m="3026600">this</span>
  <span m="3026770">is</span> <span m="3026980">both</span> <span m="3027320">o</span>
  <span m="3027530">delta</span> <span m="3027660">t</span> <span m="3027870">and</span>
  <span m="3028030">and</span> <span m="3028280">o</span> <span m="3028490">delta</span>
  <span m="3028640">t</span> <span m="3029020">square.</span> <span m="3030600">Do</span>
  <span m="3030810">I</span> <span m="3031090">contradict</span> <span m="3031690">myself?</span>
  <span m="3035560">No?</span> <span m="3036046">Hm?</span></p><p><span m="3036532">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="3038480">PROFESSOR: Yeah,</span> <span m="3038710">how</span>
  <span m="3039010">does it</span> <span m="3039110">go?</span> <span m="3040730">How</span>
  <span m="3040920">can</span> <span m="3041280">this</span> <span m="3042005">term</span>
  <span m="3042440">be</span> <span m="3042650">both</span> <span m="3043120">o delta</span>
  <span m="3043340">t</span> <span m="3043420">and o</span> <span m="3043720">delta</span>
  <span m="3044100">t</span> <span m="3044568">squared?</span> <span m="3047850">Again</span>
  <span m="3048080">[INAUDIBLE]</span> <span m="3049700">I</span> <span m="3049990">want--</span>
  <span m="3050730">somebody</span> <span m="3051080">else,</span> <span m="3051290">yeah.</span></p><p><span
  m="3051978">AUDIENCE: Because</span> <span m="3052456">o</span> <span m="3052934">delta</span>
  <span m="3053412">t</span> <span m="3053890">is the</span> <span m="3054368">[INAUDIBLE]</span>
  <span m="3055324">delta</span> <span m="3055802">t</span> <span m="3056280">squared</span>
  <span m="3056758">and</span> <span m="3057236">[INAUDIBLE]</span></p><p><span m="3059150">PROFESSOR:
  Yeah,</span> <span m="3059550">because</span> <span m="3059980">o</span> <span m="3060280">delta</span>
  <span m="3060440">t</span> <span m="3060600">actually</span> <span m="3060910">includes</span>
  <span m="3061220">o</span> <span m="3061716">delta</span> <span m="3062212">t</span>
  <span m="3062708">squared.</span> <span m="3063700">o</span> <span m="3064200">delta</span>
  <span m="3064380">t</span> <span m="3064460">means</span> <span m="3065720">it</span>
  <span m="3065910">can</span> <span m="3066080">contain</span> <span m="3066720">delta</span>
  <span m="3067085">t</span> <span m="3067450">terms,</span> <span m="3067735">delta</span>
  <span m="3068020">t</span> <span m="3068490">squared</span> <span m="3068950">terms,</span>
  <span m="3069410">and delta</span> <span m="3069870">t</span> <span m="3070330">[INAUDIBLE].</span>
  <span m="3071250">But</span> <span m="3071570">any</span> <span m="3071860">or</span>
  <span m="3072200">all</span> <span m="3072910">of</span> <span m="3073070">these</span>
  <span m="3073270">terms</span> <span m="3073630">can</span> <span m="3073990">have</span>
  <span m="3074270">zero</span> <span m="3074560">as</span> <span m="3074770">their</span>
  <span m="3075220">coefficient.</span> <span m="3078370">If</span> <span m="3078820">I</span>
  <span m="3078990">have</span> <span m="3079140">an</span> <span m="3079440">o</span>
  <span m="3079580">delta</span> <span m="3079760">t</span> <span m="3080025">term</span>
  <span m="3081890">and</span> <span m="3082150">it</span> <span m="3082260">happens</span>
  <span m="3082770">that</span> <span m="3083170">the</span> <span m="3083270">coefficient</span>
  <span m="3084200">before</span> <span m="3084620">the</span> <span m="3084790">delta
  t</span> <span m="3085250">term</span> <span m="3085560">is</span> <span m="3085810">zero,</span>
  <span m="3086900">then it</span> <span m="3087270">is</span> <span m="3087430">automatically</span>
  <span m="3088170">going</span> <span m="3088310">to</span> <span m="3088400">be</span>
  <span m="3088840">o</span> <span m="3089200">delta</span> <span m="3089290">t</span>
  <span m="3089510">squared,</span> <span m="3091580">right?</span></p><p><span m="3093390">So</span>
  <span m="3093840">I</span> <span m="3093910">can</span> <span m="3094150">say</span>
  <span m="3094380">that</span> <span m="3094740">o</span> <span m="3095440">1</span>
  <span m="3096260">is</span> <span m="3097310">a</span> <span m="3097450">superset</span>
  <span m="3098830">of</span> <span m="3099170">o</span> <span m="3099860">delta</span>
  <span m="3100190">t,</span> <span m="3100540">which</span> <span m="3100820">is</span>
  <span m="3100960">a</span> <span m="3101060">superset</span> <span m="3101730">of</span>
  <span m="3102330">o</span> <span m="3102700">delta</span> <span m="3102910">t</span>
  <span m="3103400">square,</span> <span m="3103750">which</span> <span m="3103950">is</span>
  <span m="3104080">a</span> <span m="3104180">superset</span> <span m="3104990">of</span>
  <span m="3105350">o</span> <span m="3105810">delta</span> <span m="3105980">t</span>
  <span m="3106360">cube,</span> <span m="3106890">et</span> <span m="3107000">cetera.</span>
  <span m="3115240">Any</span> <span m="3115560">questions?</span> <span m="3120060">Questions?</span></p><p><span
  m="3126350">All</span> <span m="3126540">right.</span> <span m="3126970">OK,</span>
  <span m="3128260">and</span> <span m="3128710">so</span> <span m="3128900">now,</span>
  <span m="3129810">the</span> <span m="3129990">second</span> <span m="3130370">question</span>
  <span m="3131070">is</span> <span m="3132070">how</span> <span m="3133290">to</span>
  <span m="3134180">make</span> <span m="3134700">a</span> <span m="3134780">scheme</span>
  <span m="3135150">out of</span> <span m="3135650">it.</span> <span m="3143190">We</span>
  <span m="3143520">already</span> <span m="3143960">have</span> <span m="3144440">an</span>
  <span m="3144680">approximation.</span> <span m="3145830">That</span> <span m="3146140">is</span>
  <span m="3146890">du</span> <span m="3147783">dt</span> <span m="3148216">at</span>
  <span m="3148650">t</span> <span m="3149210">is</span> <span m="3149636">equal</span>
  <span m="3150062">to</span> <span m="3150488">u</span> <span m="3150914">of</span>
  <span m="3151340">t plus</span> <span m="3151770">delta</span> <span m="3151950">t</span>
  <span m="3153144">minus u</span> <span m="3153596">of</span> <span m="3154048">t</span>
  <span m="3154500">minus delta</span> <span m="3154990">t divided</span> <span m="3155480">by
  t</span> <span m="3155970">delta</span> <span m="3156460">t.</span> <span m="3156950">We</span>
  <span m="3157150">have</span> <span m="3157350">a</span> <span m="3157410">differential</span>
  <span m="3157920">equation--</span> <span m="3158706">du</span> <span m="3159100">dt</span>
  <span m="3159530">equal</span> <span m="3159905">to</span> <span m="3160280">minus</span>
  <span m="3160680">lambda</span> <span m="3161140">u.</span> <span m="3161940">Again,</span>
  <span m="3162400">the</span> <span m="3162540">only</span> <span m="3162780">thing</span>
  <span m="3162920">you</span> <span m="3163010">need</span> <span m="3163160">to</span>
  <span m="3163270">do</span> <span m="3163460">is</span> <span m="3163680">to</span>
  <span m="3163790">plug</span> <span m="3164320">this</span> <span m="3164720">into</span>
  <span m="3165070">this.</span></p><p><span m="3166350">So</span> <span m="3166560">we</span>
  <span m="3166780">have</span> <span m="3167200">u</span> <span m="3167620">of</span>
  <span m="3168040">t</span> <span m="3168150">plus</span> <span m="3168460">delta</span>
  <span m="3168920">t</span> <span m="3169460">minus</span> <span m="3169960">u of</span>
  <span m="3170460">t</span> <span m="3170960">minus</span> <span m="3171460">delta
  t</span> <span m="3171960">divided</span> <span m="3172470">by</span> <span m="3173610">2</span>
  <span m="3173890">delta</span> <span m="3174286">t</span> <span m="3175080">is</span>
  <span m="3175340">equal</span> <span m="3175660">to</span> <span m="3175770">minus</span>
  <span m="3176156">lambda</span> <span m="3176542">u</span> <span m="3176930">at</span>
  <span m="3177300">t.</span> <span m="3180990">And</span> <span m="3181430">when</span>
  <span m="3181930">you</span> <span m="3182180">look</span> <span m="3182580">at</span>
  <span m="3182690">these</span> <span m="3182910">terms,</span> <span m="3183990">when</span>
  <span m="3184260">you</span> <span m="3184460">are</span> <span m="3184730">at</span>
  <span m="3185400">time</span> <span m="3185690">t,</span> <span m="3186600">when</span>
  <span m="3187190">the</span> <span m="3187300">solution</span> <span m="3187730">at</span>
  <span m="3187790">time</span> <span m="3188080">t</span> <span m="3188280">is</span>
  <span m="3188420">already</span> <span m="3188760">known</span> <span m="3189430">but</span>
  <span m="3189680">anything</span> <span m="3190390">beyond</span> <span m="3190990">t</span>
  <span m="3191280">is</span> <span m="3191520">unknown,</span> <span m="3192810">then</span>
  <span m="3193630">this</span> <span m="3193970">is</span> <span m="3194120">known</span>
  <span m="3194430">because</span> <span m="3194830">this</span> <span m="3195030">is</span>
  <span m="3195210">the</span> <span m="3195390">before</span> <span m="3195690">t.</span>
  <span m="3196470">This</span> <span m="3196760">is</span> <span m="3196890">known</span>
  <span m="3197200">because</span> <span m="3197510">this</span> <span m="3197690">at</span>
  <span m="3197810">t.</span> <span m="3198750">The</span> <span m="3198940">only</span>
  <span m="3199320">unknown</span> <span m="3202290">is</span> <span m="3203030">this.</span></p><p><span
  m="3204970">So</span> <span m="3205330">again,</span> <span m="3205810">we</span>
  <span m="3205970">are</span> <span m="3206310">going</span> <span m="3206510">to</span>
  <span m="3206610">rearrange</span> <span m="3207240">the</span> <span m="3207350">terms</span>
  <span m="3207730">and</span> <span m="3207940">say</span> <span m="3208290">u</span>
  <span m="3209303">t</span> <span m="3209726">plus</span> <span m="3210150">delta</span>
  <span m="3210510">t</span> <span m="3211210">is</span> <span m="3211610">equal</span>
  <span m="3212010">to</span> <span m="3212490">u</span> <span m="3213130">t</span>
  <span m="3213530">minus</span> <span m="3214160">delta</span> <span m="3214260">t</span>
  <span m="3216460">minus</span> <span m="3216990">2</span> <span m="3217370">delta</span>
  <span m="3217610">t</span> <span m="3217800">times</span> <span m="3217960">lambda</span>
  <span m="3218060">times</span> <span m="3218551">ut.</span> <span m="3221990">If</span>
  <span m="3222350">t</span> <span m="3222630">is</span> <span m="3222910">going</span>
  <span m="3223040">to</span> <span m="3223100">be</span> <span m="3223180">exactly</span>
  <span m="3223620">on</span> <span m="3223760">a</span> <span m="3223880">time</span>
  <span m="3224120">step,</span> <span m="3224580">what</span> <span m="3224740">I''m</span>
  <span m="3224860">going</span> <span m="3225000">to</span> <span m="3225160">say</span>
  <span m="3225520">is</span> <span m="3225780">that</span> <span m="3226470">u</span>
  <span m="3227080">of</span> <span m="3228690">i</span> <span m="3228750">plus</span>
  <span m="3229250">1</span> <span m="3230190">is</span> <span m="3230460">equal</span>
  <span m="3230900">to ui</span> <span m="3232250">minus</span> <span m="3232770">1</span>
  <span m="3233510">minus</span> <span m="3233980">2</span> <span m="3234320">delta</span>
  <span m="3234540">t</span> <span m="3234700">lambda</span> <span m="3235560">times</span>
  <span m="3235840">ui.</span> <span m="3239080">OK,</span> <span m="3239730">this</span>
  <span m="3241500">notation</span> <span m="3242290">is</span> <span m="3243220">assuming</span>
  <span m="3243750">I</span> <span m="3243960">have</span> <span m="3244300">discretized</span>
  <span m="3245350">u</span> <span m="3246810">into</span> <span m="3248710">a</span>
  <span m="3248860">uniform</span> <span m="3249320">grid</span> <span m="3249770">of</span>
  <span m="3250110">space</span> <span m="3250574">in delta</span> <span m="3251038">t.</span></p><p><span
  m="3251966">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3254290">PROFESSOR: Yeah.</span></p><p><span
  m="3254590">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3261700">PROFESSOR: The</span>
  <span m="3261820">question</span> <span m="3262040">is,</span> <span m="3263370">am</span>
  <span m="3263580">I</span> <span m="3263630">using</span> <span m="3263970">a</span>
  <span m="3264050">scheme</span> <span m="3264440">that</span> <span m="3264710">has</span>
  <span m="3264810">a</span> <span m="3264860">mathematical</span> <span m="3265860">definition?</span></p><p><span
  m="3266360">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3271630">PROFESSOR: Oh,</span>
  <span m="3271860">OK.</span> <span m="3272270">So</span> <span m="3272430">what</span>
  <span m="3272740">does a</span> <span m="3273070">scheme</span> <span m="3273413">mean?</span>
  <span m="3273756">A</span> <span m="3274100">scheme</span> <span m="3274650">is</span>
  <span m="3275080">a numerical</span> <span m="3275526">method,</span> <span m="3275972">a</span>
  <span m="3276420">method</span> <span m="3276830">that</span> <span m="3277010">you</span>
  <span m="3277400">can</span> <span m="3277790">implement</span> <span m="3278790">into</span>
  <span m="3279430">the</span> <span m="3279530">computer</span> <span m="3280740">to</span>
  <span m="3281460">solve a</span> <span m="3281840">differential</span> <span m="3282330">equation.</span>
  <span m="3283490">It</span> <span m="3283640">just</span> <span m="3283990">means</span>
  <span m="3284690">if</span> <span m="3284880">I</span> <span m="3285030">have</span>
  <span m="3285230">an</span> <span m="3285330">initial</span> <span m="3285600">condition,</span>
  <span m="3286180">a</span> <span m="3286500">scheme</span> <span m="3286690">must</span>
  <span m="3286920">be</span> <span m="3287040">able</span> <span m="3287370">to</span>
  <span m="3288140">tell</span> <span m="3288390">me</span> <span m="3288560">where</span>
  <span m="3288880">is</span> <span m="3289080">the</span> <span m="3289170">solution
  at</span> <span m="3289660">the</span> <span m="3290090">next</span> <span m="3290520">time
  step</span> <span m="3290950">and</span> <span m="3291040">then</span> <span m="3291240">tell</span>
  <span m="3291440">me</span> <span m="3291570">again,</span> <span m="3291790">what</span>
  <span m="3291980">is</span> <span m="3292110">the</span> <span m="3292230">solution</span>
  <span m="3292600">at</span> <span m="3292680">the</span> <span m="3292750">next</span>
  <span m="3293020">time step,</span> <span m="3293467">et cetera,</span> <span m="3293914">et
  cetera, right?</span> <span m="3294361">A</span> <span m="3294810">scheme</span>
  <span m="3295600">is</span> <span m="3295860">basically,</span> <span m="3296340">you</span>
  <span m="3296430">can</span> <span m="3296620">think</span> <span m="3296890">of</span>
  <span m="3297040">it</span> <span m="3297110">as</span> <span m="3297280">an</span>
  <span m="3298040">algorithm.</span></p><p><span m="3298300">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="3302764">PROFESSOR: Right.</span></p><p><span m="3304252">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="3307724">PROFESSOR: We''re making</span> <span m="3308220">what?</span></p><p><span
  m="3309088">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3316260">PROFESSOR: Exactly,</span>
  <span m="3316855">exactly,</span> <span m="3318160">yeah.</span> <span m="3321610">Good</span>
  <span m="3321890">question.</span> <span m="3322480">I</span> <span m="3323110">was</span>
  <span m="3323750">just</span> <span m="3324090">so</span> <span m="3324230">familiar</span>
  <span m="3324610">with</span> <span m="3324770">what</span> <span m="3325150">scheme</span>
  <span m="3325290">is,</span> <span m="3325660">I</span> <span m="3325770">didn''t</span>
  <span m="3326410">explain</span> <span m="3326870">it.</span> <span m="3327010">So</span>
  <span m="3327280">it''s</span> <span m="3327550">a good</span> <span m="3327890">catch.</span></p><p><span
  m="3329230">If</span> <span m="3329760">you</span> <span m="3329860">find</span>
  <span m="3330090">something</span> <span m="3330390">like</span> <span m="3330590">this,</span>
  <span m="3331260">please</span> <span m="3331550">to</span> <span m="3331730">raise</span>
  <span m="3332000">a</span> <span m="3332100">question.</span> <span m="3332500">Because</span>
  <span m="3332860">if</span> <span m="3333030">you</span> <span m="3333200">have</span>
  <span m="3333330">a</span> <span m="3333380">question,</span> <span m="3334160">your</span>
  <span m="3334810">classmates</span> <span m="3335600">probably</span> <span m="3335970">also</span>
  <span m="3336260">have</span> <span m="3336640">the</span> <span m="3336710">same</span>
  <span m="3337173">question.</span> <span m="3341640">OK,</span> <span m="3344880">so</span>
  <span m="3346820">here,</span> <span m="3347210">we</span> <span m="3348240">basically</span>
  <span m="3348900">derived</span> <span m="3349960">two</span> <span m="3350220">schemes.</span></p><p><span
  m="3351560">By</span> <span m="3351680">the</span> <span m="3351760">way,</span>
  <span m="3351890">this</span> <span m="3352230">scheme</span> <span m="3352530">is</span>
  <span m="3353550">the</span> <span m="3353640">midpoint</span> <span m="3354140">scheme.</span>
  <span m="3358860">We</span> <span m="3359100">have</span> <span m="3359340">tow</span>
  <span m="3359430">rite</span> <span m="3360130">two</span> <span m="3360370">schemes--</span>
  <span m="3361100">the</span> <span m="3361280">[INAUDIBLE]</span> <span m="3362030">scheme,</span>
  <span m="3363340">which</span> <span m="3363560">is</span> <span m="3365800">the</span>
  <span m="3366120">scheme</span> <span m="3366700">that</span> <span m="3367030">we</span>
  <span m="3367350">have--</span> <span m="3372980">yeah,</span> <span m="3373820">the</span>
  <span m="3374090">scheme</span> <span m="3374410">we</span> <span m="3374530">have</span>
  <span m="3374810">here.</span> <span m="3375850">We</span> <span m="3376350">can</span>
  <span m="3376570">run</span> <span m="3376790">it</span> <span m="3376900">in</span>
  <span m="3377060">general</span> <span m="3377450">as</span> <span m="3377800">f</span>
  <span m="3378110">of</span> <span m="3378420">i</span> <span m="3378680">plus</span>
  <span m="3379030">1</span> <span m="3379360">equal</span> <span m="3379780">to f</span>
  <span m="3380173">of</span> <span m="3380566">i</span> <span m="3380960">minus</span>
  <span m="3381390">delta</span> <span m="3381700">t</span> <span m="3382122">lambda</span>
  <span m="3382544">f</span> <span m="3382966">i.</span> <span m="3383390">So</span>
  <span m="3383540">this</span> <span m="3383710">is</span> <span m="3383800">the</span>
  <span m="3383900">Forward</span> <span m="3384270">Euler.</span></p><p><span m="3387740">This</span>
  <span m="3387920">is</span> <span m="3388040">called</span> <span m="3388300">a</span>
  <span m="3388360">forward</span> <span m="3388760">Euler</span> <span m="3389050">scheme</span>
  <span m="3390080">in</span> <span m="3390500">your</span> <span m="3390920">reading.</span>
  <span m="3392430">And</span> <span m="3392730">we</span> <span m="3392910">have</span>
  <span m="3393160">also</span> <span m="3393430">derived</span> <span m="3393880">the</span>
  <span m="3393960">midpoint</span> <span m="3394225">scheme</span> <span m="3394700">both</span>
  <span m="3395117">from--</span> <span m="3396370">they</span> <span m="3396500">are</span>
  <span m="3396790">different</span> <span m="3397390">only</span> <span m="3398380">by</span>
  <span m="3398680">that</span> <span m="3399010">they''re</span> <span m="3400100">different</span>
  <span m="3400710">in</span> <span m="3400890">how</span> <span m="3401130">to</span>
  <span m="3401320">approximate</span> <span m="3402670">the</span> <span m="3402830">derivative</span>
  <span m="3403390">in</span> <span m="3403540">time.</span> <span m="3404770">Once</span>
  <span m="3405010">you</span> <span m="3405110">have</span> <span m="3405390">an</span>
  <span m="3405520">approximation</span> <span m="3406230">of</span> <span m="3406540">the</span>
  <span m="3406780">derivative in</span> <span m="3407170">time,</span> <span m="3407460">you</span>
  <span m="3407680">plug</span> <span m="3407940">into</span> <span m="3408160">the</span>
  <span m="3408240">differential</span> <span m="3408630">equation.</span> <span m="3409080">You</span>
  <span m="3409260">can</span> <span m="3409590">[INAUDIBLE],</span> <span m="3411870">OK?</span></p><p><span
  m="3413510">Now</span> <span m="3413800">what</span> <span m="3413990">I</span>
  <span m="3414060">want</span> <span m="3414260">to</span> <span m="3414380">talk</span>
  <span m="3414630">about</span> <span m="3414920">next</span> <span m="3415270">is</span>
  <span m="3415810">what</span> <span m="3416060">is</span> <span m="3416260">the</span>
  <span m="3416470">local</span> <span m="3417090">order</span> <span m="3417630">of</span>
  <span m="3417900">accuracy.</span> <span m="3419090">And</span> <span m="3419320">I''m</span>
  <span m="3419460">going</span> <span m="3419580">to</span> <span m="3419680">say</span>
  <span m="3419850">that</span> <span m="3420030">the</span> <span m="3420100">local</span>
  <span m="3420360">order</span> <span m="3420680">of</span> <span m="3420850">accuracy</span>
  <span m="3422010">is</span> <span m="3423350">how</span> <span m="3423740">accurate</span>
  <span m="3425230">the</span> <span m="3425440">scheme</span> <span m="3426380">approximates</span>
  <span m="3427560">the</span> <span m="3427710">time</span> <span m="3428060">derivative.</span>
  <span m="3431690">It</span> <span m="3431920">is</span> <span m="3432460">related</span>
  <span m="3433140">to</span> <span m="3433340">what</span> <span m="3434360">tau</span>
  <span m="3434510">is.</span></p><p><span m="3436040">So</span> <span m="3436920">for</span>
  <span m="3437100">example,</span> <span m="3437560">in</span> <span m="3437790">forward</span>
  <span m="3438165">Euler,</span> <span m="3439580">how</span> <span m="3440760">is</span>
  <span m="3441380">o</span> <span m="3441880">delta</span> <span m="3442360">t,</span>
  <span m="3442840">right?</span> <span m="3443140">This</span> <span m="3443310">is</span>
  <span m="3443510">what</span> <span m="3443970">we</span> <span m="3444090">derived</span>
  <span m="3444710">right</span> <span m="3444980">before</span> <span m="3445280">we</span>
  <span m="3445380">take</span> <span m="3445590">the</span> <span m="3445660">break.</span>
  <span m="3448630">So</span> <span m="3448820">tau</span> <span m="3449630">is--</span>
  <span m="3451450">tau</span> <span m="3451690">in</span> <span m="3451950">forward</span>
  <span m="3452210">Euler</span> <span m="3452690">is</span> <span m="3454030">the</span>
  <span m="3454410">df</span> <span m="3455802">dt</span> <span m="3456730">at</span>
  <span m="3457658">t</span> <span m="3458122">minus--</span> <span m="3459520">let</span>
  <span m="3459840">me</span> <span m="3459920">call</span> <span m="3460130">it</span>
  <span m="3460210">u</span> <span m="3460520">because</span> <span m="3461140">it''s</span>
  <span m="3461520">a</span> <span m="3462280">small--</span> <span m="3463910">it''s</span>
  <span m="3464200">more</span> <span m="3464390">consistent</span> <span m="3464970">to</span>
  <span m="3465070">the</span> <span m="3465170">notes--</span> <span m="3466570">minus</span>
  <span m="3467110">u</span> <span m="3467610">at</span> <span m="3467920">t</span>
  <span m="3469030">plus</span> <span m="3469500">delta</span> <span m="3469690">t</span>
  <span m="3470260">minus</span> <span m="3470730">ut</span> <span m="3471670">divided</span>
  <span m="3472170">by</span> <span m="3472600">delta</span> <span m="3472996">t.</span>
  <span m="3473790">This</span> <span m="3474170">is</span> <span m="3474460">o</span>
  <span m="3475300">delta</span> <span m="3475490">t</span> <span m="3477570">for</span>
  <span m="3477990">forward</span> <span m="3478340">Euler.</span></p><p><span m="3480730">And</span>
  <span m="3481150">the</span> <span m="3481240">tau</span> <span m="3482520">is</span>
  <span m="3484370">the</span> <span m="3484490">same</span> <span m="3484780">derivative</span>
  <span m="3485430">minus</span> <span m="3485840">a</span> <span m="3485910">different</span>
  <span m="3486690">approximation</span> <span m="3487770">for</span> <span m="3487890">the</span>
  <span m="3488120">derivative,</span> <span m="3488750">ut</span> <span m="3489400">minus</span>
  <span m="3489640">delta</span> <span m="3489800">t</span> <span m="3490263">divided</span>
  <span m="3490726">by</span> <span m="3491190">2</span> <span m="3491470">delta</span>
  <span m="3491630">t.</span> <span m="3492680">This</span> <span m="3492980">is</span>
  <span m="3493150">actually</span> <span m="3493435">o</span> <span m="3494320">delta</span>
  <span m="3494490">t</span> <span m="3494550">square</span> <span m="3495930">for</span>
  <span m="3496080">the</span> <span m="3496180">midpoint</span> <span m="3498960">and</span>
  <span m="3499210">through</span> <span m="3499530">Taylor</span> <span m="3500060">series</span>
  <span m="3500210">analysis.</span> <span m="3503580">OK,</span> <span m="3504580">the</span>
  <span m="3504790">local</span> <span m="3505230">order</span> <span m="3505500">of</span>
  <span m="3505660">accuracy</span> <span m="3506350">is</span> <span m="3507550">the</span>
  <span m="3507690">exponent</span> <span m="3509400">on</span> <span m="3509600">top</span>
  <span m="3509820">of</span> <span m="3509990">delta</span> <span m="3510270">t</span>
  <span m="3511130">of</span> <span m="3511390">this</span> <span m="3512010">truncation</span>
  <span m="3512270">error.</span></p><p><span m="3515160">So</span> <span m="3515330">forward</span>
  <span m="3515660">Euler is</span> <span m="3516140">first</span> <span m="3516440">order</span>
  <span m="3516720">accurate</span> <span m="3517580">because</span> <span m="3518000">it''s</span>
  <span m="3518190">o</span> <span m="3518440">delta</span> <span m="3518590">t.</span>
  <span m="3519460">Midpoint</span> <span m="3519690">is</span> <span m="3520085">second</span>
  <span m="3520480">order</span> <span m="3520640">accurate</span> <span m="3521280">because</span>
  <span m="3521570">it''s</span> <span m="3521860">o</span> <span m="3522100">delta</span>
  <span m="3522190">t</span> <span m="3522640">square.</span> <span m="3527730">So</span>
  <span m="3527880">the</span> <span m="3527980">local</span> <span m="3528440">order</span>
  <span m="3528630">of</span> <span m="3528810">accuracy</span> <span m="3529480">is</span>
  <span m="3529860">1</span> <span m="3531120">for</span> <span m="3531310">forward</span>
  <span m="3531686">Euler.</span> <span m="3532440">The</span> <span m="3532580">local</span>
  <span m="3533050">one</span> <span m="3533260">of</span> <span m="3533450">accuracy</span>
  <span m="3534060">is</span> <span m="3534190">2 for</span> <span m="3534678">midpoint.</span></p><p><span
  m="3539560">Usually,</span> <span m="3541060">the</span> <span m="3541200">higher</span>
  <span m="3542870">the</span> <span m="3543180">order</span> <span m="3543340">is,</span>
  <span m="3543910">the</span> <span m="3544080">better</span> <span m="3544506">scheme
  is.</span> <span m="3546640">Why?</span> <span m="3549430">Because</span> <span
  m="3549770">you</span> <span m="3549870">can</span> <span m="3550040">make</span>
  <span m="3550230">the</span> <span m="3550330">scheme</span> <span m="3550610">more</span>
  <span m="3550860">accurate</span> <span m="3551270">by</span> <span m="3551460">only</span>
  <span m="3551790">increasing</span> <span m="3552660">or</span> <span m="3552780">decreasing</span>
  <span m="3553240">delta</span> <span m="3553670">t</span> <span m="3554630">a</span>
  <span m="3554750">little</span> <span m="3555010">bit.</span></p><p><span m="3557760">We</span>
  <span m="3557890">just</span> <span m="3558170">need an</span> <span m="3558380">analysis</span>
  <span m="3559020">of</span> <span m="3559250">forward</span> <span m="3559616">Euler.</span>
  <span m="3560350">If</span> <span m="3560570">I</span> <span m="3560700">make</span>
  <span m="3561010">delta</span> <span m="3561310">t</span> <span m="3562690">half</span>
  <span m="3563030">as</span> <span m="3563170">small,</span> <span m="3564630">how</span>
  <span m="3565220">much</span> <span m="3565540">smaller</span> <span m="3566560">the</span>
  <span m="3566680">truncation</span> <span m="3567150">error</span> <span m="3567430">is</span>
  <span m="3567550">going</span> <span m="3567680">to</span> <span m="3567750">be?</span>
  <span m="3569314">Half.</span></p><p><span m="3570600">Now,</span> <span m="3570820">if</span>
  <span m="3570980">I</span> <span m="3571110">have</span> <span m="3571250">a</span>
  <span m="3571330">midpoint,</span> <span m="3573370">if</span> <span m="3573570">I</span>
  <span m="3573700">decrease</span> <span m="3574540">the--</span> <span m="3576330">if</span>
  <span m="3576500">I</span> <span m="3576590">decrease</span> <span m="3577210">the</span>
  <span m="3577380">delta t</span> <span m="3577860">by</span> <span m="3578420">half,</span>
  <span m="3580180">how</span> <span m="3580320">much</span> <span m="3580760">more</span>
  <span m="3581020">accurate</span> <span m="3581770">is</span> <span m="3582040">the</span>
  <span m="3582130">midpoint</span> <span m="3582395">going to</span> <span m="3582660">be?</span>
  <span m="3584470">A</span> <span m="3584650">quarter--</span> <span m="3585410">exactly.</span>
  <span m="3586500">So--</span> <span m="3588220">yeah,</span> <span m="3588930">so</span>
  <span m="3590240">this</span> <span m="3590600">is</span> <span m="3590920">how</span>
  <span m="3591450">we</span> <span m="3591650">usually</span> <span m="3593410">kind</span>
  <span m="3593590">of</span> <span m="3594200">visualize</span> <span m="3595130">the</span>
  <span m="3595340">order</span> <span m="3595615">of</span> <span m="3595890">accuracy.</span>
  <span m="3597120">OK,</span> <span m="3597410">so</span> <span m="3597560">let''s</span>
  <span m="3597790">say</span> <span m="3598390">the</span> <span m="3598700">[INAUDIBLE]</span>
  <span m="3599145">is</span> <span m="3599590">delta</span> <span m="3600035">t.</span></p><p><span
  m="3602260">OK,</span> <span m="3602530">so</span> <span m="3602680">let''s</span>
  <span m="3602900">say</span> <span m="3603120">this</span> <span m="3603310">is</span>
  <span m="3603490">forward</span> <span m="3603760">Euler.</span> <span m="3606350">So</span>
  <span m="3606770">let''s</span> <span m="3606990">say</span> <span m="3607190">this</span>
  <span m="3607380">is</span> <span m="3608100">first</span> <span m="3608470">order</span>
  <span m="3609000">accurate.</span> <span m="3609740">This</span> <span m="3609950">is</span>
  <span m="3610590">delta</span> <span m="3610760">t</span> <span m="3611250">and</span>
  <span m="3611570">delta</span> <span m="3611630">t,</span> <span m="3611830">let''s</span>
  <span m="3611990">say,</span> <span m="3612300">is</span> <span m="3612610">1</span>
  <span m="3612890">here,</span> <span m="3613870">1 to</span> <span m="3614290">1</span>
  <span m="3614560">here,</span> <span m="3615820">1 to</span> <span m="3616140">o1</span>
  <span m="3616650">here,</span> <span m="3617440">1</span> <span m="3617850">to</span>
  <span m="3618340">oo1</span> <span m="3618560">here.</span> <span m="3621550">So</span>
  <span m="3621690">let''s</span> <span m="3621910">say</span> <span m="3622300">when</span>
  <span m="3622770">you</span> <span m="3622970">have</span> <span m="3623230">1</span>
  <span m="3623780">I</span> <span m="3623930">get</span> <span m="3624140">a</span>
  <span m="3624310">pretty</span> <span m="3624650">big</span> <span m="3624860">error</span>
  <span m="3625220">[INAUDIBLE].</span></p><p><span m="3627000">When</span> <span
  m="3627180">I</span> <span m="3627250">decrease</span> <span m="3627660">delta</span>
  <span m="3627800">t to</span> <span m="3628220">0.1,</span> <span m="3629510">what</span>
  <span m="3629650">do</span> <span m="3629720">you</span> <span m="3629790">think</span>
  <span m="3629990">the</span> <span m="3630100">error</span> <span m="3630450">is</span>
  <span m="3630560">going</span> <span m="3630680">to</span> <span m="3630740">become?</span>
  <span m="3634410">[INAUDIBLE],</span> <span m="3635210">right.</span> <span m="3635920">So</span>
  <span m="3636340">I</span> <span m="3636550">should</span> <span m="3636760">be</span>
  <span m="3637010">right</span> <span m="3637330">here,</span> <span m="3637790">right?</span>
  <span m="3638240">I</span> <span m="3638350">should</span> <span m="3638530">be</span>
  <span m="3638660">right</span> <span m="3638910">here</span> <span m="3640940">because</span>
  <span m="3641260">it''s</span> <span m="3641440">o</span> <span m="3641640">delta</span>
  <span m="3641750">t.</span> <span m="3642970">Now,</span> <span m="3643240">if</span>
  <span m="3643400">I</span> <span m="3643510">decrease</span> <span m="3644070">it</span>
  <span m="3644320">to</span> <span m="3644490">0.01,</span> <span m="3645050">[INAUDIBLE]</span>
  <span m="3645300">should</span> <span m="3645430">decrease</span> <span m="3645950">by</span>
  <span m="3646150">another</span> <span m="3646550">10</span> <span m="3646960">and</span>
  <span m="3647305">by</span> <span m="3647650">another</span> <span m="3648130">10.</span></p><p><span
  m="3648370">So</span> <span m="3648470">if</span> <span m="3648680">I</span> <span
  m="3648800">link</span> <span m="3649100">it,</span> <span m="3650100">it</span>
  <span m="3650260">will</span> <span m="3650370">be</span> <span m="3650520">a</span>
  <span m="3650880">line</span> <span m="3651600">with</span> <span m="3651760">a</span>
  <span m="3651850">slope</span> <span m="3653400">of</span> <span m="3653680">1</span>
  <span m="3654380">in</span> <span m="3654520">a</span> <span m="3654630">[INAUDIBLE]</span>
  <span m="3659040">All</span> <span m="3659230">right?</span> <span m="3660580">Now--</span>
  <span m="3660810">so</span> <span m="3661950">this</span> <span m="3662190">is</span>
  <span m="3662360">forward</span> <span m="3662670">Euler.</span> <span m="3663020">This</span>
  <span m="3663250">is</span> <span m="3663850">first</span> <span m="3664300">order</span>
  <span m="3664400">accurate.</span></p><p><span m="3665480">How</span> <span m="3665730">about</span>
  <span m="3666000">a</span> <span m="3666090">second</span> <span m="3666390">order</span>
  <span m="3666690">accurate</span> <span m="3667185">scheme?</span> <span m="3667680">So</span>
  <span m="3667990">again,</span> <span m="3668290">[INAUDIBLE]</span> <span m="3668740">delta</span>
  <span m="3669030">t</span> <span m="3669930">is</span> <span m="3670220">1,</span>
  <span m="3670710">0.1,</span> <span m="3671160">0.01,</span> <span m="3672480">0.001</span>
  <span m="3673960">here.</span> <span m="3674400">And</span> <span m="3674760">again,</span>
  <span m="3675220">if</span> <span m="3675710">I</span> <span m="3675880">am</span>
  <span m="3676180">[INAUDIBLE]</span> <span m="3676440">large</span> <span m="3676770">error</span>
  <span m="3677690">at</span> <span m="3677980">delta t</span> <span m="3678280">equal</span>
  <span m="3678530">to</span> <span m="3678590">1,</span> <span m="3679536">what do</span>
  <span m="3680010">you</span> <span m="3680120">think</span> <span m="3680550">is</span>
  <span m="3680760">the</span> <span m="3681220">error</span> <span m="3681360">going</span>
  <span m="3681510">to</span> <span m="3681590">be</span> <span m="3681740">at</span>
  <span m="3682238">delta</span> <span m="3682736">t</span> <span m="3683234">equal
  to</span> <span m="3683732">0.1?</span> <span m="3689210">[INAUDIBLE]</span></p><p><span
  m="3692696">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3698680">PROFESSOR: Why</span>
  <span m="3699070">should it</span> <span m="3699555">be here?</span> <span m="3701980">It''s</span>
  <span m="3702465">delta</span> <span m="3702950">t</span> <span m="3703435">square</span>
  <span m="3703920">[INAUDIBLE]</span> <span m="3705870">smaller.</span> <span m="3706340">Delta</span>
  <span m="3706817">t</span> <span m="3707294">square</span> <span m="3707771">is
  100</span> <span m="3708248">times</span> <span m="3708725">smaller.</span></p><p><span
  m="3710640">So</span> <span m="3711690">I</span> <span m="3711840">should</span>
  <span m="3712020">be</span> <span m="3712170">here</span> <span m="3713620">when</span>
  <span m="3713850">delta</span> <span m="3713970">t</span> <span m="3714240">decreased</span>
  <span m="3714600">by</span> <span m="3714700">a</span> <span m="3714740">factor</span>
  <span m="3714990">of</span> <span m="3715070">10.</span> <span m="3715720">I</span>
  <span m="3715840">should</span> <span m="3716020">be</span> <span m="3716170">here</span>
  <span m="3717130">when</span> <span m="3717310">delta</span> <span m="3717410">t</span>
  <span m="3717630">is</span> <span m="3717860">decreased</span> <span m="3718310">by</span>
  <span m="3718440">another</span> <span m="3718750">factor of</span> <span m="3719185">10.</span>
  <span m="3719620">If</span> <span m="3719830">I</span> <span m="3719950">link</span>
  <span m="3720270">it,</span> <span m="3721100">it</span> <span m="3721220">will</span>
  <span m="3721340">be</span> <span m="3721560">a</span> <span m="3721800">slope</span>
  <span m="3722290">like</span> <span m="3722700">this</span> <span m="3723070">and</span>
  <span m="3723310">I''m</span> <span m="3723590">kind</span> <span m="3723870">of</span>
  <span m="3724050">out of</span> <span m="3724360">touch</span> <span m="3724770">when</span>
  <span m="3725030">I''m</span> <span m="3725480">0.001.</span> <span m="3727590">So</span>
  <span m="3727810">you</span> <span m="3727920">can</span> <span m="3728110">see</span>
  <span m="3728280">that</span> <span m="3728480">second</span> <span m="3728775">order</span>
  <span m="3729070">scheme</span> <span m="3729365">is</span> <span m="3729820">something</span>
  <span m="3729920">much</span> <span m="3730670">better</span> <span m="3731120">than</span>
  <span m="3731340">the</span> <span m="3731410">first</span> <span m="3731700">order</span>
  <span m="3731970">scheme.</span></p><p><span m="3733370">Essentially,</span> <span
  m="3734080">I</span> <span m="3734250">have</span> <span m="3734420">the</span>
  <span m="3734490">luxury</span> <span m="3734940">of</span> <span m="3735150">making</span>
  <span m="3735510">delta</span> <span m="3735915">t</span> <span m="3736320">very</span>
  <span m="3736758">small--</span> <span m="3738950">OK,</span> <span m="3739520">so</span>
  <span m="3739720">going</span> <span m="3739970">back</span> <span m="3740170">to</span>
  <span m="3740260">MATLAB,</span> <span m="3742500">if</span> <span m="3742740">I</span>
  <span m="3742860">can</span> <span m="3743110">say</span> <span m="3743860">df</span>
  <span m="3744130">dt</span> <span m="3745360">equal</span> <span m="3745810">to--</span>
  <span m="3747050">now I</span> <span m="3747370">cannot</span> <span m="3747820">no</span>
  <span m="3748110">longer</span> <span m="3748240">do</span> <span m="3748560">this,</span>
  <span m="3748910">right?</span> <span m="3749830">I</span> <span m="3750020">have</span>
  <span m="3750290">to</span> <span m="3750400">do</span> <span m="3751140">f</span>
  <span m="3751465">of</span> <span m="3751900">3</span> <span m="3752360">to</span>
  <span m="3752610">n</span> <span m="3752980">[INAUDIBLE]</span> <span m="3753130">3</span>
  <span m="3753270">to</span> <span m="3753755">n</span> <span m="3757150">OK,</span>
  <span m="3757640">let</span> <span m="3758200">me</span> <span m="3759851">clear</span>
  <span m="3760270">the</span> <span m="3760400">workspace</span> <span m="3760550">so</span>
  <span m="3760800">that</span> <span m="3761240">you can</span> <span m="3761680">see</span>
  <span m="3762120">better.</span> <span m="3763964">[INAUDIBLE]</span> <span m="3764425">window</span>
  <span m="3764886">[INAUDIBLE].</span></p><p><span m="3766270">OK,</span> <span m="3767130">so</span>
  <span m="3767550">df</span> <span m="3768005">dt--</span> <span m="3769370">let</span>
  <span m="3769540">me</span> <span m="3769700">say</span> <span m="3771216">midpoint</span>
  <span m="3773020">is</span> <span m="3773310">equal</span> <span m="3773580">to</span>
  <span m="3773740">f</span> <span m="3774130">of</span> <span m="3774440">3</span>
  <span m="3774550">to</span> <span m="3774780">n</span> <span m="3776692">minus</span>
  <span m="3777570">f</span> <span m="3777960">of</span> <span m="3778140">1</span>
  <span m="3778440">to</span> <span m="3778690">n</span> <span m="3778940">minus</span>
  <span m="3779260">2.</span> <span m="3779990">What</span> <span m="3780150">does</span>
  <span m="3780270">this</span> <span m="3780490">mean?</span> <span m="3788300">I''m</span>
  <span m="3788450">picking</span> <span m="3788820">from</span> <span m="3789120">the</span>
  <span m="3789210">third</span> <span m="3789620">value</span> <span m="3790500">to</span>
  <span m="3790650">the</span> <span m="3790750">last</span> <span m="3791155">value--</span>
  <span m="3792370">minus</span> <span m="3792920">the</span> <span m="3793020">first</span>
  <span m="3793410">value</span> <span m="3793890">to</span> <span m="3794130">the</span>
  <span m="3794530">third</span> <span m="3795030">last</span> <span m="3795530">value.</span>
  <span m="3799530">OK.</span></p><p><span m="3800021">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="3803710">PROFESSOR: I''m</span> <span m="3804000">taking</span> <span m="3804320">the</span>
  <span m="3804490">different</span> <span m="3804990">space by</span> <span m="3805490">two.</span>
  <span m="3806990">OK,</span> <span m="3807390">so</span> <span m="3807590">that</span>
  <span m="3807830">is</span> <span m="3808390">like--</span> <span m="3808960">there</span>
  <span m="3809370">is</span> <span m="3809810">how</span> <span m="3810160">I</span>
  <span m="3810300">view</span> <span m="3811340">f</span> <span m="3811680">at</span>
  <span m="3811920">t</span> <span m="3812170">plus</span> <span m="3812590">delta</span>
  <span m="3812800">t minus</span> <span m="3813380">f</span> <span m="3813650">of</span>
  <span m="3813920">t</span> <span m="3814120">minus</span> <span m="3814530">delta</span>
  <span m="3814610">t.</span> <span m="3817510">So</span> <span m="3818170">I</span>
  <span m="3818330">should</span> <span m="3818580">divide</span> <span m="3818900">this</span>
  <span m="3819090">by</span> <span m="3819280">how</span> <span m="3819410">much?</span></p><p><span
  m="3821370">2</span> <span m="3821770">times</span> <span m="3822130">delta</span>
  <span m="3822460">t--</span> <span m="3822906">exactly.</span> <span m="3823800">And</span>
  <span m="3824030">here,</span> <span m="3824170">I</span> <span m="3824270">think</span>
  <span m="3824550">I''m</span> <span m="3824670">actually</span> <span m="3824990">doing</span>
  <span m="3825270">a</span> <span m="3825530">really</span> <span m="3825760">big</span>
  <span m="3825990">delta</span> <span m="3826360">t.</span> <span m="3826620">It
  doesn''t</span> <span m="3826830">matter.</span> <span m="3827320">[INAUDIBLE]</span>
  <span m="3827810">OK,</span> <span m="3828530">so</span> <span m="3828710">when</span>
  <span m="3828930">I</span> <span m="3829220">plot</span> <span m="3829620">it</span>
  <span m="3831690">I</span> <span m="3831860">should</span> <span m="3832050">be</span>
  <span m="3832150">plotting</span> <span m="3832480">it</span> <span m="3832880">against</span>
  <span m="3833310">the</span> <span m="3833540">t</span> <span m="3834785">going</span>
  <span m="3835200">from</span> <span m="3835520">2</span> <span m="3835820">to</span>
  <span m="3836000">n</span> <span m="3836430">minus 1,</span> <span m="3836930">right?</span>
  <span m="3837190">Because</span> <span m="3837640">this</span> <span m="3837910">is</span>
  <span m="3838150">now</span> <span m="3838510">my</span> <span m="3838895">t.</span></p><p><span
  m="3840570">2</span> <span m="3840830">to</span> <span m="3840970">n</span> <span
  m="3841120">minus</span> <span m="3841410">1</span> <span m="3841590">is my</span>
  <span m="3841730">t.</span> <span m="3842860">3</span> <span m="3843150">to</span>
  <span m="3843340">n</span> <span m="3843650">is my</span> <span m="3843790">t</span>
  <span m="3844160">plus</span> <span m="3844440">delta</span> <span m="3844580">t.</span>
  <span m="3845630">1</span> <span m="3845900">to</span> <span m="3846060">n</span>
  <span m="3846230">minus</span> <span m="3846520">2</span> <span m="3846670">is</span>
  <span m="3846850">t</span> <span m="3847340">minus</span> <span m="3847817">delta</span>
  <span m="3848294">t.</span> <span m="3849250">So</span> <span m="3849430">this</span>
  <span m="3849810">is my</span> <span m="3849980">t.</span> <span m="3850480">I''m</span>
  <span m="3850730">going</span> <span m="3850880">to</span> <span m="3851090">[INAUDIBLE]</span>
  <span m="3851340">this</span> <span m="3851570">against</span> <span m="3851870">df</span>
  <span m="3852220">dt</span> <span m="3853500">midpoint.</span> <span m="3854990">I''m</span>
  <span m="3855410">going</span> <span m="3855610">to</span> <span m="3855700">be</span>
  <span m="3856270">square</span> <span m="3856730">and</span> <span m="3857030">what</span>
  <span m="3857230">color</span> <span m="3857550">do</span> <span m="3857610">you</span>
  <span m="3857720">want?</span></p><p><span m="3860950">AUDIENCE: Pink.</span></p><p><span
  m="3861950">PROFESSOR: Pink?</span> <span m="3866250">Magenta?</span> <span m="3866440">OK,</span>
  <span m="3867200">[INAUDIBLE]</span> <span m="3868935">square,</span> <span m="3869710">OK.</span></p><p><span
  m="3870620">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3874710">PROFESSOR: Yes,</span>
  <span m="3875650">so</span> <span m="3876150">[INAUDIBLE]</span> <span m="3876650">even</span>
  <span m="3876980">though</span> <span m="3877250">[INAUDIBLE]</span> <span m="3877450">delta</span>
  <span m="3877630">t</span> <span m="3878096">[INAUDIBLE]</span> <span m="3878562">0.2</span>
  <span m="3879280">[INAUDIBLE]</span> <span m="3881388">kind</span> <span m="3881855">of</span>
  <span m="3882322">goes</span> <span m="3882790">right</span> <span m="3883238">through</span>
  <span m="3883686">the</span> <span m="3884134">exact</span> <span m="3884582">derivative.</span>
  <span m="3886380">OK,</span> <span m="3886760">so</span> <span m="3886970">this</span>
  <span m="3887270">is</span> <span m="3888022">how</span> <span m="3888700">a</span>
  <span m="3888790">second</span> <span m="3889110">order</span> <span m="3889360">scheme</span>
  <span m="3889750">is</span> <span m="3890550">better</span> <span m="3890950">than</span>
  <span m="3891150">a</span> <span m="3891250">first</span> <span m="3891510">order</span>
  <span m="3891750">scheme.</span> <span m="3893140">And</span> <span m="3893510">how</span>
  <span m="3893680">to</span> <span m="3893800">assess</span> <span m="3894170">that?</span>
  <span m="3895890">Taylor</span> <span m="3896510">analysis,</span> <span m="3898740">right?</span></p><p><span
  m="3900810">OK,</span> <span m="3902790">maybe</span> <span m="3903590">I</span>
  <span m="3903875">will</span> <span m="3904160">just</span> <span m="3904440">show</span>
  <span m="3904620">you</span> <span m="3905030">how</span> <span m="3905540">did</span>
  <span m="3905660">I</span> <span m="3905720">get</span> <span m="3906140">the</span>
  <span m="3906720">certain</span> <span m="3907050">order.</span> <span m="3907670">So</span>
  <span m="3907860">if</span> <span m="3908050">I</span> <span m="3908170">further</span>
  <span m="3908510">extend</span> <span m="3908960">this,</span> <span m="3910260">[INAUDIBLE]</span>
  <span m="3910470">what</span> <span m="3910660">I</span> <span m="3910750">get</span>
  <span m="3911020">is</span> <span m="3911280">the</span> <span m="3911630">d</span>
  <span m="3912220">square</span> <span m="3912600">u</span> <span m="3912920">dt</span>
  <span m="3914610">times</span> <span m="3914990">delta</span> <span m="3915330">t</span>
  <span m="3915610">squared</span> <span m="3916200">over</span> <span m="3916520">2,</span>
  <span m="3917510">right?</span> <span m="3918832">[INAUDIBLE]</span> <span m="3921660">squared</span>
  <span m="3922050">over</span> <span m="3922290">2</span> <span m="3922770">and</span>
  <span m="3922990">then</span> <span m="3923260">plus</span> <span m="3924190">the</span>
  <span m="3924300">cube.</span></p><p><span m="3925250">Here,</span> <span m="3925510">what</span>
  <span m="3925710">I</span> <span m="3925820">get</span> <span m="3926130">is</span>
  <span m="3926940">plus</span> <span m="3927390">d</span> <span m="3928122">square</span>
  <span m="3928490">u</span> <span m="3928870">dt</span> <span m="3931270">times</span>
  <span m="3931870">minus</span> <span m="3932300">delta</span> <span m="3932410">t</span>
  <span m="3932740">square,</span> <span m="3933000">which</span> <span m="3933170">is</span>
  <span m="3933300">the</span> <span m="3933410">same</span> <span m="3933720">as</span>
  <span m="3933970">delta</span> <span m="3934200">t</span> <span m="3934310">square,</span>
  <span m="3934880">over</span> <span m="3935190">two</span> <span m="3936286">plus</span>
  <span m="3936640">this</span> <span m="3936980">to the</span> <span m="3937190">cube.</span>
  <span m="3938080">And</span> <span m="3938240">you</span> <span m="3938320">can</span>
  <span m="3938500">see</span> <span m="3938670">when</span> <span m="3938970">I</span>
  <span m="3939060">subtract</span> <span m="3939790">the</span> <span m="3940020">u</span>
  <span m="3940220">of</span> <span m="3940580">t</span> <span m="3940880">plus</span>
  <span m="3940990">delta</span> <span m="3941100">t</span> <span m="3941320">by</span>
  <span m="3941550">u</span> <span m="3941950">[INAUDIBLE]</span> <span m="3942440">delta</span>
  <span m="3942930">t,</span> <span m="3944340">the</span> <span m="3945180">[INAUDIBLE]</span>
  <span m="3945730">order</span> <span m="3946070">term</span> <span m="3946290">cancel.</span>
  <span m="3947690">The</span> <span m="3947800">first</span> <span m="3948330">order</span>
  <span m="3948410">term,</span> <span m="3949670">because</span> <span m="3950090">they</span>
  <span m="3950220">are</span> <span m="3950310">the</span> <span m="3950390">same,</span>
  <span m="3950750">so</span> <span m="3950910">they</span> <span m="3951140">add</span>
  <span m="3951480">together.</span></p><p><span m="3953280">And</span> <span m="3953650">the</span>
  <span m="3954020">second</span> <span m="3954330">order</span> <span m="3954550">term</span>
  <span m="3954820">also</span> <span m="3955232">cancel.</span> <span m="3957390">The</span>
  <span m="3957490">third</span> <span m="3957770">order</span> <span m="3958020">term</span>
  <span m="3959010">again</span> <span m="3959490">is</span> <span m="3959640">going</span>
  <span m="3959780">to</span> <span m="3959850">have</span> <span m="3960060">different</span>
  <span m="3960400">signs</span> <span m="3960690">and</span> <span m="3961482">subtracting</span>
  <span m="3962350">them</span> <span m="3962550">actually</span> <span m="3963590">makes</span>
  <span m="3963860">them</span> <span m="3964050">bigger.</span> <span m="3965250">So</span>
  <span m="3965510">it</span> <span m="3965780">is</span> <span m="3965980">order</span>
  <span m="3966370">two.</span></p><p><span m="3966990">So</span> <span m="3967980">here,</span>
  <span m="3968440">I</span> <span m="3968640">can</span> <span m="3968930">modify</span>
  <span m="3969180">this</span> <span m="3969430">to</span> <span m="3970140">delta</span>
  <span m="3970310">t</span> <span m="3970660">cube</span> <span m="3971390">because</span>
  <span m="3971830">the</span> <span m="3971950">square</span> <span m="3972390">term</span>
  <span m="3972610">actually</span> <span m="3972920">cancel</span> <span m="3973340">each</span>
  <span m="3973743">other.</span> <span m="3974550">And</span> <span m="3975100">here</span>
  <span m="3975370">is</span> <span m="3975560">going</span> <span m="3975710">to</span>
  <span m="3975770">be</span> <span m="3975940">square.</span> <span m="3978740">All</span>
  <span m="3978900">right,</span> <span m="3979590">and</span> <span m="3979930">we</span>
  <span m="3980130">see</span> <span m="3980470">that</span> <span m="3982260">by</span>
  <span m="3982430">actually</span> <span m="3982780">observing</span> <span m="3983410">the</span>
  <span m="3984370">increased</span> <span m="3985060">accuracy.</span></p><p><span
  m="3988740">OK,</span> <span m="3989720">so</span> <span m="3990080">let''s--</span>
  <span m="3990745">we</span> <span m="3991120">have</span> <span m="3991740">a</span>
  <span m="3991970">little</span> <span m="3992180">bit</span> <span m="3992330">of</span>
  <span m="3992490">time.</span> <span m="3995310">Let''s</span> <span m="3995750">actually</span>
  <span m="3996500">start</span> <span m="3996910">the</span> <span m="3997060">contest.</span>
  <span m="3998260">And</span> <span m="3998610">I</span> <span m="3998730">would</span>
  <span m="3998960">actually</span> <span m="3999810">not</span> <span m="4000290">end</span>
  <span m="4000560">it</span> <span m="4001070">today.</span></p><p><span m="4001710">I</span>
  <span m="4002150">would</span> <span m="4002370">have</span> <span m="4002550">you</span>
  <span m="4002680">start</span> <span m="4002950">it</span> <span m="4003220">today</span>
  <span m="4003800">and</span> <span m="4004660">maybe</span> <span m="4005070">we''ll</span>
  <span m="4005780">come</span> <span m="4006060">back</span> <span m="4006710">and</span>
  <span m="4007170">report</span> <span m="4007670">your</span> <span m="4008380">findings</span>
  <span m="4008910">in</span> <span m="4009500">the</span> <span m="4009570">beginning</span>
  <span m="4010000">of</span> <span m="4010200">the</span> <span m="4010290">next</span>
  <span m="4010738">lecture.</span> <span m="4012980">All</span> <span m="4013150">right,</span>
  <span m="4014310">so</span> <span m="4014940">the</span> <span m="4015040">concept</span>
  <span m="4015650">is</span> <span m="4016120">like</span> <span m="4016340">this.</span>
  <span m="4018260">I</span> <span m="4018390">want</span> <span m="4018790">the</span>
  <span m="4018920">best</span> <span m="4020080">X</span> <span m="4020557">scheme.</span></p><p><span
  m="4023420">How</span> <span m="4023700">do</span> <span m="4023870">I</span> <span
  m="4023980">[INAUDIBLE]</span> <span m="4024310">my</span> <span m="4024430">best?</span>
  <span m="4026470">The</span> <span m="4026690">highest</span> <span m="4027540">local</span>
  <span m="4028200">order</span> <span m="4028680">of</span> <span m="4028910">accuracy--</span>
  <span m="4030780">OK,</span> <span m="4031160">what</span> <span m="4031300">does</span>
  <span m="4031430">that</span> <span m="4031590">mean?</span> <span m="4032220">I</span>
  <span m="4032360">want</span> <span m="4032580">to</span> <span m="4032790">o</span>
  <span m="4033045">delta</span> <span m="4033540">t</span> <span m="4034020">to</span>
  <span m="4034170">as</span> <span m="4034450">high</span> <span m="4035060">power</span>
  <span m="4035420">as</span> <span m="4035650">possible,</span> <span m="4037340">right?</span></p><p><span
  m="4040110">OK,</span> <span m="4040710">and the</span> <span m="4041060">X--</span>
  <span m="4041430">what does</span> <span m="4041680">X</span> <span m="4042140">mean?</span>
  <span m="4043160">X</span> <span m="4043490">means</span> <span m="4044220">one</span>
  <span m="4044593">of these--</span> <span m="4044966">one</span> <span m="4045340">of</span>
  <span m="4045430">these</span> <span m="4045630">four.</span> <span m="4046690">And</span>
  <span m="4047320">I''d</span> <span m="4047420">like</span> <span m="4048240">you</span>
  <span m="4048430">to</span> <span m="4048630">form</span> <span m="4049020">a</span>
  <span m="4049120">eteam</span> <span m="4049660">with</span> <span m="4050170">one</span>
  <span m="4050410">person</span> <span m="4050780">or</span> <span m="4050970">two</span>
  <span m="4051180">other</span> <span m="4051260">persons</span> <span m="4052370">and</span>
  <span m="4052700">commit</span> <span m="4053150">to</span> <span m="4053430">either</span>
  <span m="4053720">one,</span> <span m="4054200">two,</span> <span m="4054500">or</span>
  <span m="4054760">three</span> <span m="4055239">or</span> <span m="4055718">four</span>
  <span m="4061950">and</span> <span m="4062130">figure</span> <span m="4062490">out</span>
  <span m="4063130">how</span> <span m="4063450">do</span> <span m="4063540">you</span>
  <span m="4063620">design</span> <span m="4063760">a</span> <span m="4063920">scheme</span>
  <span m="4066620">to</span> <span m="4066740">make</span> <span m="4067030">it</span>
  <span m="4067220">as</span> <span m="4067620">accurate</span> <span m="4068310">as</span>
  <span m="4068781">possible.</span></p><p><span m="4069723">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="4077530">PROFESSOR: OK,</span> <span m="4078255">so</span> <span m="4078680">I''m</span>
  <span m="4080120">going</span> <span m="4080260">to</span> <span m="4080340">give</span>
  <span m="4080540">you</span> <span m="4080650">the</span> <span m="4080740">formula</span>
  <span m="4081360">now.</span> <span m="4082310">Best</span> <span m="4082990">implicit</span>
  <span m="4084340">one</span> <span m="4084630">step</span> <span m="4084910">scheme</span>
  <span m="4085700">means</span> <span m="4086040">I</span> <span m="4086180">want</span>
  <span m="4086640">u</span> <span m="4086935">at</span> <span m="4088380">[INAUDIBLE]</span>
  <span m="4090940">so</span> <span m="4091150">u</span> <span m="4091500">as</span>
  <span m="4091710">i</span> <span m="4091900">plus</span> <span m="4092260">1.</span>
  <span m="4093280">Or</span> <span m="4093500">let</span> <span m="4093790">me</span>
  <span m="4093870">actually</span> <span m="4094370">use</span> <span m="4094980">u</span>
  <span m="4095428">[INAUDIBLE]</span> <span m="4097670">t</span> <span m="4097935">plus</span>
  <span m="4098470">delta</span> <span m="4098950">t</span> <span m="4100819">equal</span>
  <span m="4101380">to</span> <span m="4101649">something</span> <span m="4103240">times</span>
  <span m="4105200">du</span> <span m="4106992">dt</span> <span m="4108670">at</span>
  <span m="4109069">t</span> <span m="4109517">plus</span> <span m="4109965">delta</span>
  <span m="4110413">t</span> <span m="4111310">plus</span> <span m="4111729">something</span>
  <span m="4112490">times</span> <span m="4112960">u</span> <span m="4113439">at</span>
  <span m="4113649">t</span> <span m="4113989">plus</span> <span m="4114670">something</span>
  <span m="4115014">times</span> <span m="4115359">du</span> <span m="4116347">dt</span>
  <span m="4117335">at</span> <span m="4117830">t.</span></p><p><span m="4119080">All
  right,</span> <span m="4119439">this</span> <span m="4119680">is</span> <span m="4120370">the</span>
  <span m="4120510">best</span> <span m="4121200">implicit</span> <span m="4122130">one</span>
  <span m="4122510">step</span> <span m="4122729">scheme</span> <span m="4123149">and</span>
  <span m="4123319">your</span> <span m="4123470">task</span> <span m="4123580">is</span>
  <span m="4123840">to</span> <span m="4124109">figure</span> <span m="4124300">out</span>
  <span m="4124479">what</span> <span m="4124774">teh</span> <span m="4125069">questions</span>
  <span m="4125550">are.</span> <span m="4129140">OK,</span> <span m="4129819">best</span>
  <span m="4130310">explicit</span> <span m="4130819">two</span> <span m="4130990">step</span>
  <span m="4131669">scheme--</span> <span m="4133109">it</span> <span m="4133330">means</span>
  <span m="4133760">this.</span> <span m="4138729">It</span> <span m="4139200">means</span>
  <span m="4140250">you</span> <span m="4140580">add</span> <span m="4140880">t</span>
  <span m="4141180">plus</span> <span m="4141510">delta</span> <span m="4141800">t</span>
  <span m="4142850">has</span> <span m="4143130">to</span> <span m="4143260">equal</span>
  <span m="4143810">to--</span> <span m="4144609">because</span> <span m="4145149">it</span>
  <span m="4145350">is</span> <span m="4145910">explicit,</span> <span m="4147430">it</span>
  <span m="4147670">does</span> <span m="4147800">not</span> <span m="4148229">allow</span>
  <span m="4148760">a</span> <span m="4148850">derivative</span> <span m="4149195">[INAUDIBLE]</span>
  <span m="4149540">order</span> <span m="4149950">t.</span></p><p><span m="4151590">So</span>
  <span m="4151800">you</span> <span m="4151950">have</span> <span m="4152180">to</span>
  <span m="4152640">do</span> <span m="4153149">a</span> <span m="4153260">question</span>
  <span m="4153689">mark</span> <span m="4154029">of</span> <span m="4154140">ut</span>
  <span m="4155270">plus a</span> <span m="4155680">question</span> <span m="4156135">mark</span>
  <span m="4156590">at</span> <span m="4157500">du</span> <span m="4158439">dt</span>
  <span m="4159130">at</span> <span m="4159479">t.</span> <span m="4160250">And</span>
  <span m="4160439">now,</span> <span m="4160729">because</span> <span m="4161220">it''s</span>
  <span m="4161439">two</span> <span m="4161779">step,</span> <span m="4163609">two</span>
  <span m="4163850">step</span> <span m="4164120">means</span> <span m="4164390">I</span>
  <span m="4164560">allow</span> <span m="4165729">one</span> <span m="4166229">more</span>
  <span m="4166479">step</span> <span m="4167380">to</span> <span m="4167550">be</span>
  <span m="4167740">used</span> <span m="4168920">in</span> <span m="4169430">determining</span>
  <span m="4170189">the</span> <span m="4170290">solution</span> <span m="4170780">t
  plus</span> <span m="4171270">delta</span> <span m="4171760">t,</span> <span m="4172740">which</span>
  <span m="4172910">means</span> <span m="4173880">I</span> <span m="4174069">can</span>
  <span m="4174450">use</span> <span m="4174950">u</span> <span m="4175330">at</span>
  <span m="4175600">t</span> <span m="4175905">minus</span> <span m="4176210">delta</span>
  <span m="4176642">t</span> <span m="4178370">and</span> <span m="4178880">du</span>
  <span m="4179529">dt</span> <span m="4180149">at</span> <span m="4180983">t</span>
  <span m="4181400">minus</span> <span m="4181819">delta</span> <span m="4182189">t.</span>
  <span m="4184689">All</span> <span m="4185189">right,</span> <span m="4185689">so</span>
  <span m="4185840">this</span> <span m="4186189">is</span> <span m="4186930">the</span>
  <span m="4187120">degrees</span> <span m="4187700">of</span> <span m="4187870">freedom</span>
  <span m="4188260">you</span> <span m="4188410">have</span> <span m="4188755">in
  your</span> <span m="4189100">best</span> <span m="4189560">explicit</span> <span
  m="4190060">two</span> <span m="4190520">step</span> <span m="4190980">scheme.</span>
  <span m="4193740">And</span> <span m="4193990">what</span> <span m="4194149">is</span>
  <span m="4194320">the</span> <span m="4194410">difference</span> <span m="4194820">between</span>
  <span m="4195573">explicit</span> <span m="4196380">two</span> <span m="4196570">step</span>
  <span m="4196880">scheme and</span> <span m="4197367">an</span> <span m="4197854">implicit</span>
  <span m="4198341">two step</span> <span m="4198828">scheme?</span></p><p><span m="4211510">Yes,</span>
  <span m="4212500">the</span> <span m="4212770">answer</span> <span m="4213090">is</span>
  <span m="4213660">you</span> <span m="4213830">can</span> <span m="4214090">use</span>
  <span m="4214920">du</span> <span m="4215530">dt</span> <span m="4215950">at</span>
  <span m="4216600">t</span> <span m="4217090">plus</span> <span m="4217580">delta</span>
  <span m="4217780">t.</span> <span m="4218280">So</span> <span m="4218460">I''m</span>
  <span m="4218610">going</span> <span m="4218730">to</span> <span m="4218850">circle</span>
  <span m="4219750">the</span> <span m="4219870">term</span> <span m="4220300">that</span>
  <span m="4220510">makes</span> <span m="4220870">a</span> <span m="4221110">scheme</span>
  <span m="4221940">implicit--</span> <span m="4224070">right,</span> <span m="4224450">so</span>
  <span m="4224620">implicit.</span> <span m="4228630">So</span> <span m="4228820">with</span>
  <span m="4229090">the</span> <span m="4229200">implicit</span> <span m="4229690">scheme,</span>
  <span m="4230730">you</span> <span m="4230910">are</span> <span m="4231130">allowed</span>
  <span m="4231380">to</span> <span m="4231520">use</span> <span m="4232576">u</span>
  <span m="4233012">plus</span> <span m="4233448">delta</span> <span m="4233884">t</span>
  <span m="4234760">equal</span> <span m="4235270">to--</span> <span m="4236630">the</span>
  <span m="4236700">increased</span> <span m="4237370">term</span> <span m="4237645">is</span>
  <span m="4237920">a</span> <span m="4238020">question</span> <span m="4238423">mark</span>
  <span m="4239230">times</span> <span m="4239580">du</span> <span m="4239890">dt</span>
  <span m="4240750">at</span> <span m="4241180">t</span> <span m="4241610">plus</span>
  <span m="4242040">delta</span> <span m="4242470">t.</span> <span m="4242900">If</span>
  <span m="4243140">I</span> <span m="4243430">don''t</span> <span m="4243720">have</span>
  <span m="4243920">this</span> <span m="4244090">term,</span> <span m="4244380">it
  will</span> <span m="4244843">be</span> <span m="4245306">explicit.</span></p><p><span
  m="4248050">All</span> <span m="4248290">the</span> <span m="4248380">other</span>
  <span m="4248610">terms</span> <span m="4248930">are</span> <span m="4249050">the</span>
  <span m="4249160">same--</span> <span m="4249430">question</span> <span m="4249793">mark</span>
  <span m="4250156">times</span> <span m="4250520">ut</span> <span m="4251300">times</span>
  <span m="4251650">question</span> <span m="4252020">mark</span> <span m="4252360">times</span>
  <span m="4252810">du</span> <span m="4253294">dt</span> <span m="4253778">at</span>
  <span m="4254262">t</span> <span m="4255230">plus</span> <span m="4255570">question</span>
  <span m="4255980">mark</span> <span m="4256828">u</span> <span m="4257276">at</span>
  <span m="4257724">t</span> <span m="4258172">minus</span> <span m="4259068">delta</span>
  <span m="4259520">t</span> <span m="4260340">plus</span> <span m="4260670">question</span>
  <span m="4261070">mark</span> <span m="4261420">times</span> <span m="4261863">du</span>
  <span m="4262750">dt</span> <span m="4263614">at</span> <span m="4264046">t</span>
  <span m="4264478">minus</span> <span m="4264910">delta</span> <span m="4265342">t.</span>
  <span m="4265780">So</span> <span m="4265940">let''s</span> <span m="4266390">just</span>
  <span m="4266590">choose</span> <span m="4266910">between</span> <span m="4267340">the</span>
  <span m="4267600">three--</span> <span m="4270560">the</span> <span m="4270700">first</span>
  <span m="4271000">three</span> <span m="4271550">options.</span> <span m="4274090">OK,</span>
  <span m="4274944">and</span> <span m="4276600">time</span> <span m="4276830">is</span>
  <span m="4276990">over,</span> <span m="4277420">but</span> <span m="4277877">I''d</span>
  <span m="4278334">like</span> <span m="4278791">you to</span> <span m="4279705">find</span>
  <span m="4280162">a</span> <span m="4280619">team mate.</span> <span m="4281080">Commit</span>
  <span m="4281500">to</span> <span m="4281700">one</span> <span m="4283940">of</span>
  <span m="4284100">these</span> <span m="4284680">axes</span> <span m="4285990">and</span>
  <span m="4286680">come</span> <span m="4286940">up</span> <span m="4287100">with</span>
  <span m="4287350">an</span> <span m="4287794">answer.</span> <span m="4288238">And</span>
  <span m="4288682">we''ll</span> <span m="4289126">star</span> <span m="4289570">to</span>
  <span m="4289870">discuss</span> <span m="4290170">this</span> <span m="4290770">in
  the</span> <span m="4291070">next</span> <span m="4291370">lecture.</span></p>'
type: course
uid: d3296ef767aec87922d4de3cd2722027

---
None