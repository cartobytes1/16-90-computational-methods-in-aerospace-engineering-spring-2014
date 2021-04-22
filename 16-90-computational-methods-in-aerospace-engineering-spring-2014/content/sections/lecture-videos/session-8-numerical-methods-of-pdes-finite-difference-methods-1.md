---
about_this_resource_text: '<p><strong>Description:</strong> After a discussion of
  ODEs compared to PDEs, this session covers finite difference approximation and second
  order derivatives.</p> <p><strong>Instructor:</strong> Qiqi Wang</p> <p>The recording
  quality of this video is the best available from the source.</p><p>Note: There is
  no video for the next class, Session 9.</p>'
course_id: 16-90-computational-methods-in-aerospace-engineering-spring-2014
embedded_media:
- id: Video-YouTube-Stream
  media_location: A-qap-PTmgo
  parent_uid: 4a9655858eb464dc4374580245d3124b
  title: Video-YouTube-Stream
  type: Video
  uid: 83199034a4beccabba75e4333902465e
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/A-qap-PTmgo/default.jpg
  parent_uid: 4a9655858eb464dc4374580245d3124b
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 4900fb4d882dd917ceb81e9c5b2ec516
- id: 3Play-3PlayYouTubeid-MP4
  media_location: A-qap-PTmgo
  parent_uid: 4a9655858eb464dc4374580245d3124b
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: cb564fd6cf88abb2754a86387245b860
- id: A-qap-PTmgo.srt
  parent_uid: 4a9655858eb464dc4374580245d3124b
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-8-numerical-methods-of-pdes-finite-difference-methods-1/A-qap-PTmgo.srt
  title: 3play caption file
  type: null
  uid: 7b4bb7e99b309c728910c56a0753fd18
- id: A-qap-PTmgo.pdf
  parent_uid: 4a9655858eb464dc4374580245d3124b
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-8-numerical-methods-of-pdes-finite-difference-methods-1/A-qap-PTmgo.pdf
  title: 3play pdf file
  type: null
  uid: 97be39d186c55a99f4d89dc4399c63dc
- id: Caption-3Play YouTube id-SRT
  parent_uid: 4a9655858eb464dc4374580245d3124b
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: d0eaa07a72602cf2e05f96b4f8b14b63
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 4a9655858eb464dc4374580245d3124b
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 1c6f5c2672404d5502302b9b77d59aa6
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT16.90S14/MIT16_90S14_L08_300k.mp4
  parent_uid: 4a9655858eb464dc4374580245d3124b
  title: Video-Internet Archive-MP4
  type: Video
  uid: 034ee452b6833457c295e228ec4af534
inline_embed_id: 67702120session8:numericalmethodsofpdes:finitedifferencemethods173662112
layout: video
order_index: null
parent_uid: 809ebf7c44bfb36e8786306747d7e32f
related_resources_text: ''
short_url: session-8-numerical-methods-of-pdes-finite-difference-methods-1
technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-8-numerical-methods-of-pdes-finite-difference-methods-1
template_type: Tabbed
title: 'Session 8: Numerical Methods of PDEs: Finite Difference Methods 1'
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
  <span m="12050">materials</span> <span m="12670">from</span> <span m="12860">hundreds</span>
  <span m="13180">of</span> <span m="13280">MIT</span> <span m="13650">courses,</span>
  <span m="14960">visit</span> <span m="15150">MIT</span> <span m="15670">OpenCourseWare</span>
  <span m="16580">at</span> <span m="16920">ocw.mit.edu.</span></p><p>&nbsp;</p><p><span
  m="26170">QIQI WANG: All right.</span> <span m="26560">It''s</span> <span m="26770">up.</span>
  <span m="27320">We''ll</span> <span m="27700">look</span> <span m="27960">here</span>
  <span m="28180">and</span> <span m="28580">we''ll</span> <span m="29290">start.</span>
  <span m="31060">The</span> <span m="31210">first</span> <span m="31620">real</span>
  <span m="31910">lecture</span> <span m="32240">on</span> <span m="32970">how</span>
  <span m="33210">to</span> <span m="33850">use</span> <span m="34220">numerical</span>
  <span m="34660">methods</span> <span m="35060">on</span> <span m="35810">partial</span>
  <span m="35930">differential</span> <span m="36510">equations.</span> <span m="38190">So</span>
  <span m="38370">just</span> <span m="38580">a</span> <span m="38700">reminder,</span>
  <span m="39290">of</span> <span m="39650">the</span> <span m="39870">latter</span>
  <span m="41220">lecture.</span> <span m="41630">We</span> <span m="42070">did</span>
  <span m="42472">a--</span> <span m="44080">We</span> <span m="44300">looked</span>
  <span m="44590">at</span> <span m="44930">partial</span> <span m="45230">derivative</span>
  <span m="45690">equations</span> <span m="46328">in</span> <span m="46816">general,</span>
  <span m="47792">right?</span> <span m="48770">We</span> <span m="48950">looked</span>
  <span m="49150">at</span> <span m="49240">the</span> <span m="49310">behavior</span>
  <span m="50020">of</span> <span m="50390">a</span> <span m="50680">few</span> <span
  m="52080">simple</span> <span m="52340">differential</span> <span m="52750">equations,</span>
  <span m="53160">where</span> <span m="53800">we</span> <span m="53990">know</span>
  <span m="54420">how</span> <span m="54540">it</span> <span m="54650">behaves.</span>
  <span m="55490">We</span> <span m="55670">looked</span> <span m="55960">at</span>
  <span m="57690">[INAUDIBLE]</span> <span m="58250">equations,</span> <span m="59910">where</span>
  <span m="60630">the</span> <span m="60820">solution</span> <span m="61480">just</span>
  <span m="61710">keeps</span> <span m="61980">moving</span> <span m="62610">towards</span>
  <span m="62960">the</span> <span m="63130">right.</span> <span m="66730">We</span>
  <span m="66910">looked</span> <span m="67150">at</span> <span m="67270">a</span>
  <span m="67330">diffusion</span> <span m="67860">equation,</span> <span m="68670">where</span>
  <span m="69190">the</span> <span m="69380">solution</span> <span m="69760">[INAUDIBLE]</span>
  <span m="70520">diffuse</span> <span m="70810">result.</span> <span m="71240">It</span>
  <span m="71320">becomes</span> <span m="71860">that</span> <span m="72110">line</span>
  <span m="72440">afterwards.</span> <span m="73880">We</span> <span m="74050">also</span>
  <span m="74340">looked</span> <span m="74690">at</span> <span m="75680">Burgers''</span>
  <span m="76280">equation,</span> <span m="77430">which</span> <span m="77690">is</span>
  <span m="77910">the</span> <span m="78270">equation</span> <span m="78840">that</span>
  <span m="79410">can</span> <span m="79670">generate</span> <span m="80210">shock
  waves.</span> <span m="81640">Where</span> <span m="81840">the</span> <span m="81930">characteristics</span>
  <span m="84205">can</span> <span m="84700">go</span> <span m="85030">together</span>
  <span m="85740">they</span> <span m="85970">generate</span> <span m="86310">shock</span>
  <span m="86600">waves.</span> <span m="87170">When</span> <span m="87520">they</span>
  <span m="88050">become,</span> <span m="88300">or</span> <span m="88600">when they</span>
  <span m="88690">diverge</span> <span m="89030">from</span> <span m="89480">each</span>
  <span m="89660">other</span> <span m="89900">they</span> <span m="90354">expand,</span>
  <span m="90808">or the solution</span> <span m="91262">expands.</span> <span m="92170">And</span>
  <span m="92440">the wave</span> <span m="93412">will use</span> <span m="93750">a</span>
  <span m="93840">little</span> <span m="94100">bit</span> <span m="94280">of</span>
  <span m="95270">human</span> <span m="96470">kind</span> <span m="96670">of</span>
  <span m="96810">animation</span> <span m="98870">to</span> <span m="99390">really</span>
  <span m="100090">animate</span> <span m="101110">the</span> <span m="101200">solution</span>
  <span m="101690">of the</span> <span m="102184">partial</span> <span m="102678">differential</span>
  <span m="103172">equation.</span> <span m="105150">So</span> <span m="105300">this</span>
  <span m="105520">is</span> <span m="105710">a</span> <span m="107020">good</span>
  <span m="107430">inclusion</span> <span m="107970">on</span> <span m="108160">the</span>
  <span m="108460">innovative</span> <span m="109120">behavior</span> <span m="109620">of</span>
  <span m="109770">the</span> <span m="109850">differential</span> <span m="110210">equation.</span>
  <span m="111240">And</span> <span m="111340">so</span> <span m="112536">try to</span>
  <span m="113060">remember</span> <span m="113520">to</span> <span m="113740">us,</span>
  <span m="114220">because</span> <span m="114950">in</span> <span m="115140">this</span>
  <span m="115330">class,</span> <span m="115810">we</span> <span m="115890">are</span>
  <span m="116020">going</span> <span m="116160">to</span> <span m="116230">be</span>
  <span m="116470">using</span> <span m="116730">finite</span> <span m="117140">difference</span>
  <span m="117670">to</span> <span m="117790">solve</span> <span m="118110">them.</span>
  <span m="118970">And</span> <span m="119250">I''m</span> <span m="119410">going</span>
  <span m="119540">to</span> <span m="119730">ask</span> <span m="120010">you</span>
  <span m="120460">where</span> <span m="121700">the</span> <span m="121880">solution</span>
  <span m="122780">and</span> <span m="122940">body</span> <span m="123420">on the
  screen</span> <span m="123920">is</span> <span m="124170">correct</span> <span m="124520">or</span>
  <span m="124630">not.</span> <span m="125550">I mean,</span> <span m="125720">not</span>
  <span m="126000">all</span> <span m="126170">of</span> <span m="126270">them</span>
  <span m="126520">are</span> <span m="126650">going</span> <span m="126790">to</span>
  <span m="126850">be</span> <span m="126980">giving</span> <span m="127400">us</span>
  <span m="127580">the</span> <span m="127965">right answer,</span> <span m="128350">as
  you</span> <span m="129120">already saw</span> <span m="129549">in</span> <span
  m="129979">the</span> <span m="130080">audio</span> <span m="130250">section.</span>
  <span m="132420">And</span> <span m="133210">some</span> <span m="133560">of</span>
  <span m="133720">them</span> <span m="133960">are</span> <span m="134090">going</span>
  <span m="134270">to</span> <span m="134440">give</span> <span m="134650">me,</span>
  <span m="134950">in</span> <span m="135050">this</span> <span m="135220">case,</span>
  <span m="136470">answers that</span> <span m="136895">are</span> <span m="137320">correct
  in</span> <span m="137960">some</span> <span m="138260">parts.</span> <span m="138520">But</span>
  <span m="138850">not</span> <span m="139360">really</span> <span m="139740">correct</span>
  <span m="140120">in</span> <span m="140210">other</span> <span m="140490">parts.</span>
  <span m="140770">And</span> <span m="141020">I</span> <span m="141180">also</span>
  <span m="141550">ask</span> <span m="141790">you,</span> <span m="142010">like</span>
  <span m="142310">which</span> <span m="142590">part</span> <span m="142830">is</span>
  <span m="143020">correct,</span> <span m="143360">which</span> <span m="143520">part</span>
  <span m="143710">is</span> <span m="143840">not</span> <span m="144330">correct?</span></p><p><span
  m="144820">OK,</span> <span m="145190">so</span> <span m="145210">let''s</span>
  <span m="146286">first</span> <span m="146680">start</span> <span m="146980">with</span>
  <span m="147240">a</span> <span m="147360">finite</span> <span m="147810">difference</span>
  <span m="148390">approximation.</span> <span m="149520">In</span> <span m="149710">this</span>
  <span m="149870">case</span> <span m="150100">with</span> <span m="150250">partial</span>
  <span m="151160">derivatives.</span> <span m="152980">So</span> <span m="153110">let''s</span>
  <span m="153480">look</span> <span m="153810">at</span> <span m="154250">the</span>
  <span m="154330">simple</span> <span m="154650">case</span> <span m="154920">where</span>
  <span m="155270">my</span> <span m="156040">solution</span> <span m="156480">U</span>
  <span m="156890">is</span> <span m="157270">a</span> <span m="157650">function of</span>
  <span m="158060">(x, t).</span> <span m="159290">What</span> <span m="159720">are</span>
  <span m="159820">the</span> <span m="159910">partial</span> <span m="160190">derivatives?</span>
  <span m="164810">What</span> <span m="165110">is</span> <span m="165310">a</span>
  <span m="165370">partial</span> <span m="165640">derivative?</span> <span m="168790">Du,</span>
  <span m="169160">dx</span> <span m="169540">and</span> <span m="170600">du,</span>
  <span m="170730">dt.</span> <span m="171910">Right?</span> <span m="173020">Why</span>
  <span m="173320">do</span> <span m="173430">we</span> <span m="173570">call</span>
  <span m="173900">it</span> <span m="174120">a</span> <span m="174400">partial</span>
  <span m="174760">derivative?</span> <span m="175040">Because</span> <span m="175550">when</span>
  <span m="175890">we</span> <span m="176250">are</span> <span m="176350">taking</span>
  <span m="176760">derivative</span> <span m="177460">of</span> <span m="177700">one</span>
  <span m="177970">variable,</span> <span m="178530">we</span> <span m="178750">are</span>
  <span m="178930">holding</span> <span m="179890">the</span> <span m="180090">other</span>
  <span m="180340">one</span> <span m="180816">fixed.</span> <span m="183200">So</span>
  <span m="183610">in</span> <span m="183780">finite</span> <span m="184020">difference</span>
  <span m="184470">method,</span> <span m="184965">a</span> <span m="185460">good</span>
  <span m="185760">way</span> <span m="186140">to</span> <span m="186390">construct</span>
  <span m="187820">the</span> <span m="187950">grid</span> <span m="188920">to</span>
  <span m="189020">say</span> <span m="189320">is</span> <span m="189610">I</span>
  <span m="189740">think</span> <span m="189950">it''s</span> <span m="190090">the</span>
  <span m="190190">first</span> <span m="190450">time</span> <span m="190660">we</span>
  <span m="191050">look</span> <span m="191220">at</span> <span m="191300">the</span>
  <span m="191370">grid.</span> <span m="191990">Is</span> <span m="192290">to</span>
  <span m="192460">actually</span> <span m="193020">construct</span> <span m="193760">the</span>
  <span m="193840">grid</span> <span m="194160">first</span> <span m="194440">that,</span>
  <span m="195010">it</span> <span m="195170">is</span> <span m="195360">aligned</span>
  <span m="195870">with</span> <span m="196160">one</span> <span m="196390">of</span>
  <span m="196530">the</span> <span m="196620">variables.</span> <span m="198240">So</span>
  <span m="198460">that,</span> <span m="198710">if</span> <span m="198930">you</span>
  <span m="199040">look</span> <span m="199310">at</span> <span m="199420">a</span>
  <span m="199480">particular</span> <span m="199920">direction</span> <span m="200380">on</span>
  <span m="200480">the</span> <span m="200560">grid,</span> <span m="201240">one</span>
  <span m="201470">of</span> <span m="201610">the</span> <span m="201700">variables</span>
  <span m="203030">are</span> <span m="203350">naturally</span> <span m="203890">fixed.</span></p><p><span
  m="204990">So</span> <span m="205220">we</span> <span m="205600">use</span> <span
  m="206620">in</span> <span m="206790">the</span> <span m="206860">last</span> <span
  m="207140">naturally,</span> <span m="207630">if you</span> <span m="207770">remember,</span>
  <span m="208110">we</span> <span m="208250">used</span> <span m="209370">these</span>
  <span m="209710">two</span> <span m="209840">axes,</span> <span m="210350">x</span>
  <span m="210610">and</span> <span m="210800">t,</span> <span m="210910">to</span>
  <span m="211050">visualize</span> <span m="211560">the</span> <span m="211670">solution.</span>
  <span m="212580">Right?</span> <span m="213450">Now</span> <span m="213690">let''s</span>
  <span m="214060">use</span> <span m="214410">the</span> <span m="214520">same</span>
  <span m="214930">plot</span> <span m="215700">in</span> <span m="215840">one</span>
  <span m="216030">direction</span> <span m="216380">x,</span> <span m="216610">the</span>
  <span m="216750">other</span> <span m="216950">direction</span> <span m="217230">t,</span>
  <span m="217530">to</span> <span m="217670">visualize</span> <span m="218330">my</span>
  <span m="218550">mesh.</span> <span m="220860">I''m</span> <span m="221000">going</span>
  <span m="221140">to</span> <span m="221210">design</span> <span m="222820">my</span>
  <span m="223070">grid</span> <span m="223660">or</span> <span m="223870">mesh</span>
  <span m="224370">to</span> <span m="224560">be</span> <span m="224770">like</span>
  <span m="225040">this.</span> <span m="225770">I</span> <span m="225880">think</span>
  <span m="226090">in finite</span> <span m="226560">difference</span> <span m="227810">it''s</span>
  <span m="227990">more</span> <span m="228250">common</span> <span m="228505">to</span>
  <span m="228760">use</span> <span m="228990">the</span> <span m="229100">word</span>
  <span m="229360">grid.</span> <span m="230250">And</span> <span m="230550">the</span>
  <span m="230640">way</span> <span m="230820">you</span> <span m="230920">go</span>
  <span m="231080">to</span> <span m="231190">find</span> <span m="231450">a</span>
  <span m="231510">volume</span> <span m="231940">or</span> <span m="232120">finite</span>
  <span m="232880">element,</span> <span m="233610">we</span> <span m="234010">will</span>
  <span m="234200">use</span> <span m="234610">the</span> <span m="234850">mesh</span>
  <span m="235360">instead.</span> <span m="235860">And</span> <span m="236080">you''re</span>
  <span m="236230">going</span> <span m="236350">to</span> <span m="236490">see</span>
  <span m="236620">why</span> <span m="236830">that</span> <span m="237000">is</span>
  <span m="237360">the case.</span> <span m="238080">So</span> <span m="238270">we</span>
  <span m="238450">have</span> <span m="238620">a grid</span> <span m="239110">like</span>
  <span m="239350">this.</span></p><p><span m="244290">And</span> <span m="244590">you</span>
  <span m="244910">see</span> <span m="245110">that</span> <span m="246390">I''m</span>
  <span m="246910">describing</span> <span m="247860">both</span> <span m="248400">space</span>
  <span m="248780">and</span> <span m="248970">time</span> <span m="249340">separately.</span>
  <span m="250640">OK?</span> <span m="250940">I''m</span> <span m="251060">going</span>
  <span m="251190">to</span> <span m="251270">call</span> <span m="251620">this--</span>
  <span m="253350">this</span> <span m="253670">x</span> <span m="254060">is</span>
  <span m="254310">called a</span> <span m="254380">zero.</span> <span m="254880">This</span>
  <span m="254990">is</span> <span m="255210">delta</span> <span m="255480">x,</span>
  <span m="256300">2</span> <span m="256589">delta</span> <span m="256800">x,</span>
  <span m="257740">3</span> <span m="258130">delta</span> <span m="258290">x,</span>
  <span m="259149">4</span> <span m="259450">delta</span> <span m="259660">x.</span>
  <span m="260339">Et cetera.</span> <span m="261750">And</span> <span m="261910">my</span>
  <span m="262010">timestamp</span> <span m="262650">is</span> <span m="263230">0</span>
  <span m="263490">delta</span> <span m="263860">t,</span> <span m="264790">2</span>
  <span m="265080">delta</span> <span m="265300">t,</span> <span m="266360">3</span>
  <span m="266710">delta</span> <span m="266900">t,</span> <span m="267110">et cetera.</span>
  <span m="267760">Right?</span> <span m="269270">So--</span> <span m="270150">I</span>
  <span m="270360">have</span> <span m="270710">my</span> <span m="270890">solution</span>
  <span m="272120">right</span> <span m="272370">here</span> <span m="272540">on</span>
  <span m="272760">this</span> <span m="273000">grid.</span> <span m="274210">And</span>
  <span m="276040">for</span> <span m="276210">example</span> <span m="276680">here,</span>
  <span m="277320">my</span> <span m="277580">space</span> <span m="278300">is</span>
  <span m="278820">equal</span> <span m="279260">to--</span> <span m="280910">I''m</span>
  <span m="281010">also</span> <span m="281220">going to</span> <span m="281310">assign</span>
  <span m="282230">my</span> <span m="282370">grid</span> <span m="282670">points.</span>
  <span m="283350">So</span> <span m="283550">this</span> <span m="285880">is</span>
  <span m="286210">what</span> <span m="286430">I</span> <span m="286540">call</span>
  <span m="286910">u</span> <span m="287400">of</span> <span m="287740">4.</span>
  <span m="288790">And</span> <span m="289370">one,</span> <span m="289720">two,</span>
  <span m="290000">three,</span> <span m="290350">four,</span> <span m="291660">five.</span>
  <span m="292450">So</span> <span m="292960">remember</span> <span m="293380">this</span>
  <span m="293520">notation.</span> <span m="294070">My</span> <span m="294300">subscript,</span>
  <span m="295924">you</span> <span m="296416">know,</span> <span m="297892">the</span>
  <span m="298384">spatial</span> <span m="298876">grid,</span> <span m="299368">and</span>
  <span m="299860">my</span> <span m="300352">superscript</span> <span m="300844">5</span>
  <span m="301336">denotes</span> <span m="301830">which</span> <span m="302470">timestamp</span>
  <span m="302880">I</span> <span m="303220">mark.</span> <span m="305130">And</span>
  <span m="305450">here</span> <span m="305820">would</span> <span m="306030">be</span>
  <span m="306230">U</span> <span m="306520">of</span> <span m="306750">4,</span>
  <span m="307100">4.</span> <span m="307800">Here</span> <span m="307950">would</span>
  <span m="308130">be</span> <span m="308370">U</span> <span m="308710">of</span>
  <span m="309390">3,</span> <span m="310190">5,</span> <span m="310440">et</span>
  <span m="310441">cetera.</span></p><p><span m="315020">OK.</span> <span m="315640">So</span>
  <span m="315780">now</span> <span m="316080">I</span> <span m="316310">have</span>
  <span m="317950">the</span> <span m="318140">solution.</span> <span m="319440">I</span>
  <span m="319450">have</span> <span m="319640">the</span> <span m="319730">discretized</span>
  <span m="320510">solution</span> <span m="321030">leaving</span> <span m="321503">all</span>
  <span m="321976">these</span> <span m="322449">grid</span> <span m="322922">points.</span>
  <span m="323870">How</span> <span m="324030">do</span> <span m="324230">I</span>
  <span m="324350">approximate</span> <span m="325730">the</span> <span m="325940">spatial</span>
  <span m="326630">derivative</span> <span m="327450">of</span> <span m="327650">x</span>
  <span m="328720">at</span> <span m="329230">some</span> <span m="329530">grid</span>
  <span m="329790">point</span> <span m="330060">i,</span> <span m="330510">and</span>
  <span m="330860">some</span> <span m="331210">timestamp</span> <span m="331770">n?</span>
  <span m="333371">Any</span> <span m="333750">suggestions</span> <span m="334100">based
  on</span> <span m="334350">What</span> <span m="334745">you</span> <span m="335140">learned</span>
  <span m="335535">being</span> <span m="335930">finite</span> <span m="337980">in</span>
  <span m="339270">ODE?</span> <span m="343360">Taylor</span> <span m="343680">series,</span>
  <span m="344160">yes.</span> <span m="344640">But can</span> <span m="345120">somebody</span>
  <span m="345410">give</span> <span m="345630">me</span> <span m="345920">a</span>
  <span m="346310">suggestion</span> <span m="347367">of</span> <span m="347784">what</span>
  <span m="348201">should</span> <span m="348620">I</span> <span m="348880">use?</span></p><p><span
  m="351875">STUDENT:</span> <span m="352370">[INAUDIBLE].</span></p><p><span m="368210">QIQI
  WANG: 1</span> <span m="368610">delta x</span> <span m="368850">further</span> <span
  m="369170">towards</span> <span m="369490">the</span> <span m="369570">left</span>
  <span m="369820">or</span> <span m="369950">right?</span></p><p><span m="371186">STUDENT:</span>
  <span m="371669">[INAUDIBLE].</span></p><p><span m="374090">QIQI WANG: OK,</span>
  <span m="374420">let''s</span> <span m="374660">try</span> <span m="374920">to</span>
  <span m="375420">use the</span> <span m="375490">right.</span> <span m="376420">OK</span>
  <span m="377180">so</span> <span m="377570">I</span> <span m="378070">can--</span>
  <span m="380570">nope.</span> <span m="383770">I</span> <span m="384170">can</span>
  <span m="384380">approximate</span> <span m="384990">the</span> <span m="385100">partial</span>
  <span m="385440">derivative</span> <span m="385790">by--</span> <span m="387330">in</span>
  <span m="387460">this</span> <span m="387630">case,</span> <span m="387830">I''m</span>
  <span m="387990">fixing</span> <span m="388640">n,</span> <span m="388970">right?</span>
  <span m="389730">In</span> <span m="390190">partial</span> <span m="390270">derivatives,</span>
  <span m="390610">I</span> <span m="390950">fix</span> <span m="391530">the</span>
  <span m="391690">other</span> <span m="391920">variable.</span> <span m="392350">In</span>
  <span m="392500">this</span> <span m="392670">case,</span> <span m="392880">I</span>
  <span m="392990">fixed</span> <span m="393330">n,</span> <span m="393640">which</span>
  <span m="393820">is</span> <span m="394230">the</span> <span m="394400">same</span>
  <span m="394670">as</span> <span m="394820">fixing</span> <span m="395216">t.</span>
  <span m="396010">I</span> <span m="396180">took</span> <span m="396500">the</span>
  <span m="396580">difference</span> <span m="397170">in</span> <span m="397280">the</span>
  <span m="397450">x</span> <span m="397795">direction</span> <span m="398140">and</span>
  <span m="398170">the</span> <span m="398270">i</span> <span m="398630">direction,</span>
  <span m="399080">which</span> <span m="399310">is</span> <span m="399470">also</span>
  <span m="400290">in</span> <span m="400430">the</span> <span m="400520">x</span>
  <span m="400930">direction.</span> <span m="401750">So</span> <span m="401920">this</span>
  <span m="402320">is</span> <span m="402650">an</span> <span m="402870">approximation</span>
  <span m="404830">of</span> <span m="405240">the</span> <span m="406010">derivative</span>
  <span m="406480">in</span> <span m="406620">x.</span> <span m="407390">I</span>
  <span m="407510">can</span> <span m="407710">call</span> <span m="408010">this</span>
  <span m="408731">forward</span> <span m="411430">in</span> <span m="411870">space.</span>
  <span m="416130">OK.</span> <span m="416490">I</span> <span m="416620">can</span>
  <span m="416820">also--</span> <span m="418136">let</span> <span m="418500">me</span>
  <span m="418810">see.</span> <span m="419288">I''m</span> <span m="419766">going
  to</span> <span m="420244">insert</span> <span m="420722">page.</span> <span m="421678">Escape</span>
  <span m="423112">it</span> <span m="423590">turns</span> <span m="424068">out</span>
  <span m="425980">I</span> <span m="426458">want</span> <span m="426950">smaller</span>
  <span m="427280">than</span> <span m="427760">A4.</span> <span m="429728">Come</span>
  <span m="430220">on.</span> <span m="432188">I</span> <span m="432680">think</span>
  <span m="433172">this is</span> <span m="433664">good,</span> <span m="436130">OK.</span>
  <span m="436920">I</span> <span m="437080">can</span> <span m="437230">also</span>
  <span m="437540">do</span> <span m="437790">backward</span> <span m="438230">in</span>
  <span m="438380">space.</span> <span m="439870">Backward</span> <span m="440300">in</span>
  <span m="440440">space,</span> <span m="441000">I</span> <span m="441230">would</span>
  <span m="441460">get</span> <span m="442130">Uin</span> <span m="443090">minus</span>
  <span m="443490">Ui-1n</span> <span m="445150">over</span> <span m="445425">delta</span>
  <span m="445700">x.</span> <span m="446690">So</span> <span m="446960">this</span>
  <span m="447200">is</span> <span m="447730">backward</span> <span m="449930">in</span>
  <span m="450320">space.</span></p><p><span m="452100">When</span> <span m="452470">you
  see</span> <span m="452780">it as--</span> <span m="454580">forward</span> <span
  m="454940">order</span> <span m="455310">and</span> <span m="455480">backward</span>
  <span m="455700">order</span> <span m="456390">have</span> <span m="456780">different</span>
  <span m="456910">stability</span> <span m="458160">properties--</span> <span m="459260">this</span>
  <span m="459610">is</span> <span m="459790">also</span> <span m="460150">going</span>
  <span m="460320">to</span> <span m="460440">have</span> <span m="460720">different</span>
  <span m="461440">stability</span> <span m="461710">properties.</span> <span m="463350">And</span>
  <span m="463550">I</span> <span m="463680">can</span> <span m="463860">also</span>
  <span m="464170">do</span> <span m="465490">central</span> <span m="466020">difference.</span>
  <span m="467380">So</span> <span m="467650">central</span> <span m="468020">difference</span>
  <span m="468640">would</span> <span m="468860">be</span> <span m="470180">U</span>
  <span m="470710">of</span> <span m="471470">i plus</span> <span m="471640">1--</span>
  <span m="472220">that</span> <span m="472360">is</span> <span m="472480">towards</span>
  <span m="472790">the</span> <span m="472910">right--</span> <span m="473250">minus</span>
  <span m="474030">U</span> <span m="474320">of</span> <span m="474560">i-1--</span>
  <span m="474870">towards</span> <span m="475200">the</span> <span m="475310">left--</span>
  <span m="476360">divided</span> <span m="476780">by</span> <span m="476980">how</span>
  <span m="477110">much?</span></p><p><span m="478020">STUDENT:</span> <span m="478460">2.</span></p><p><span
  m="478900">QIQI WANG: 2</span> <span m="479130">delta</span> <span m="479220">x,</span>
  <span m="479650">because</span> <span m="479980">that</span> <span m="480140">is</span>
  <span m="480310">the</span> <span m="480390">space</span> <span m="480750">in-between</span>
  <span m="481200">them.</span> <span m="481990">So</span> <span m="482170">this</span>
  <span m="482330">is</span> <span m="482450">central</span> <span m="484080">in</span>
  <span m="484540">space.</span> <span m="487390">How about</span> <span m="487890">time?</span>
  <span m="488370">We</span> <span m="488520">also</span> <span m="488880">need</span>
  <span m="489090">to</span> <span m="489180">discretize</span> <span m="489990">time.</span>
  <span m="491560">We</span> <span m="491600">also</span> <span m="491870">need</span>
  <span m="492010">to</span> <span m="492120">discretize</span> <span m="493465">partial</span>
  <span m="493930">U</span> <span m="494195">partial</span> <span m="494460">t</span>
  <span m="495380">at</span> <span m="496670">i</span> <span m="497120">and n.</span>
  <span m="498458">How do</span> <span m="498904">I</span> <span m="499350">approximate</span>
  <span m="500080">that?</span></p><p><span m="501675">STUDENT:</span> <span m="502150">[INAUDIBLE]?</span></p><p><span
  m="504050">QIQI WANG: Exactly</span> <span m="504630">the</span> <span m="504740">same</span>
  <span m="505070">way</span> <span m="505300">as</span> <span m="505500">we</span>
  <span m="505660">did</span> <span m="506050">in</span> <span m="506200">ODEs.</span>
  <span m="508220">And</span> <span m="508480">we</span> <span m="508590">can</span>
  <span m="508790">approximate</span> <span m="509610">it</span> <span m="510550">as</span>
  <span m="511490">U</span> <span m="511810">of</span> <span m="512140">i</span> <span
  m="512350">n</span> <span m="512959">plus</span> <span m="513250">1</span> <span
  m="513850">minus</span> <span m="514429">U</span> <span m="514590">of</span> <span
  m="514870">i</span> <span m="515080">n,</span> <span m="516592">divided</span> <span
  m="517030">by</span> <span m="517340">delta</span> <span m="517680">t.</span> <span
  m="519260">And</span> <span m="519590">that</span> <span m="519929">could fall</span>
  <span m="520330">into</span> <span m="520700">what</span> <span m="521179">scheme</span>
  <span m="521490">we</span> <span m="521700">use</span> <span m="522059">in</span>
  <span m="524500">ODEs?</span> <span m="526960">This</span> <span m="527260">grid</span>
  <span m="527590">is going</span> <span m="528040">to forward</span> <span m="528450">Euler,</span>
  <span m="532740">and</span> <span m="532950">we</span> <span m="533050">are</span>
  <span m="533170">going to</span> <span m="533300">see</span> <span m="533630">later</span>
  <span m="533950">what</span> <span m="534800">other</span> <span m="535090">things</span>
  <span m="535475">we</span> <span m="535860">can</span> <span m="536245">use.</span>
  <span m="537340">So</span> <span m="539040">let''s</span> <span m="539420">try</span>
  <span m="539770">to</span> <span m="540830">implement</span> <span m="545620">one</span>
  <span m="545930">of</span> <span m="546040">the</span> <span m="546120">combinations.</span>
  <span m="546890">So</span> <span m="547260">which</span> <span m="547620">one--</span>
  <span m="549210">[INAUDIBLE]</span> <span m="550290">because</span> <span m="550590">that''s</span>
  <span m="550840">really the</span> <span m="551330">simplest</span> <span m="551730">type</span>
  <span m="552170">of</span> <span m="552610">[INAUDIBLE]</span> <span m="553050">scheme,</span>
  <span m="553490">I think.</span> <span m="554370">And</span> <span m="554810">you</span>
  <span m="555250">want both</span> <span m="555700">or</span> <span m="556176">one
  of these?</span></p><p><span m="557604">STUDENT:</span> <span m="558080">[INAUDIBLE]?</span></p><p><span
  m="559032">QIQI WANG: Huh?</span></p><p><span m="559984">STUDENT:</span> <span m="560460">[INAUDIBLE].</span></p><p><span
  m="561420">QIQI WANG: What?</span></p><p><span m="561880">STUDENT: Central</span>
  <span m="562340">in space one.</span></p><p><span m="562800">QIQI WANG: Central</span>
  <span m="563260">in space</span> <span m="563720">one.</span> <span m="564180">All</span>
  <span m="564380">right,</span> <span m="564580">good.</span> <span m="565770">Because</span>
  <span m="566950">you</span> <span m="567080">guys</span> <span m="567390">probably</span>
  <span m="567830">can</span> <span m="568500">do</span> <span m="568710">Taylor</span>
  <span m="568870">Series</span> <span m="569130">in your</span> <span m="569450">head</span>
  <span m="569803">and</span> <span m="570156">figure</span> <span m="570510">out</span>
  <span m="570660">the</span> <span m="571040">central</span> <span m="571290">difference</span>
  <span m="571710">is actually</span> <span m="572160">second-order</span> <span m="573350">accurate.</span>
  <span m="573870">It</span> <span m="574280">is</span> <span m="574690">better</span>
  <span m="575030">than</span> <span m="575350">the</span> <span m="575660">other</span>
  <span m="575980">two.</span> <span m="576300">So</span> <span m="576540">good.</span>
  <span m="577480">You</span> <span m="577580">have</span> <span m="577750">a</span>
  <span m="577820">good</span> <span m="578050">pick.</span></p><p><span m="579420">OK,</span>
  <span m="579970">so</span> <span m="580670">I''m</span> <span m="580850">going</span>
  <span m="581030">to</span> <span m="581100">go</span> <span m="581300">to</span>
  <span m="581410">Matlab.</span> <span m="583450">The</span> <span m="583550">first</span>
  <span m="583830">thing</span> <span m="584010">I</span> <span m="584110">want</span>
  <span m="584340">to</span> <span m="584540">show</span> <span m="584880">you</span>
  <span m="585030">in</span> <span m="585170">Matlab</span> <span m="586510">is--</span>
  <span m="588910">let</span> <span m="589080">me</span> <span m="589200">show</span>
  <span m="589400">you</span> <span m="589690">in</span> <span m="589820">the</span>
  <span m="589890">next</span> <span m="590160">class</span> <span m="591110">what</span>
  <span m="591370">the</span> <span m="591470">difference</span> <span m="591870">between</span>
  <span m="592150">finite</span> <span m="592470">difference</span> <span m="592830">and</span>
  <span m="593190">finite</span> <span m="593550">volume.</span> <span m="593910">But</span>
  <span m="594130">I''m</span> <span m="594430">just</span> <span m="594640">going</span>
  <span m="594800">to</span> <span m="594940">show</span> <span m="595650">really</span>
  <span m="596160">kind</span> <span m="596300">of</span> <span m="596430">how</span>
  <span m="596785">a</span> <span m="597140">finite</span> <span m="597540">different</span>
  <span m="598680">discretize</span> <span m="601870">a</span> <span m="601950">function.</span>
  <span m="602410">So</span> <span m="602770">when</span> <span m="603070">we</span>
  <span m="603170">have</span> <span m="603390">a</span> <span m="603600">function</span>
  <span m="603880">in</span> <span m="604160">space,</span> <span m="605490">we</span>
  <span m="605640">have</span> <span m="605840">to</span> <span m="605940">discretize</span>
  <span m="606200">it,</span> <span m="607050">right?</span> <span m="607630">So,</span>
  <span m="607790">because</span> <span m="608080">the</span> <span m="608140">function</span>
  <span m="608510">is</span> <span m="608650">really</span> <span m="608930">infinite-dimensional,</span>
  <span m="609790">we</span> <span m="609930">only</span> <span m="610230">have</span>
  <span m="610520">finite</span> <span m="611270">memory.</span></p><p><span m="612260">So</span>
  <span m="612360">if</span> <span m="612530">you</span> <span m="612650">draw</span>
  <span m="612850">a</span> <span m="613180">function</span> <span m="613700">like</span>
  <span m="613950">this,</span> <span m="614720">a</span> <span m="615190">finite</span>
  <span m="615660">difference</span> <span m="616230">only</span> <span m="616940">stores</span>
  <span m="617470">the</span> <span m="617560">values</span> <span m="618100">on</span>
  <span m="618230">the</span> <span m="618300">grid</span> <span m="618550">points.</span>
  <span m="619160">So</span> <span m="619570">the</span> <span m="619840">red</span>
  <span m="620120">circles</span> <span m="620240">are</span> <span m="620490">what</span>
  <span m="620800">it</span> <span m="621000">stores.</span> <span m="621690">What</span>
  <span m="622000">is</span> <span m="622670">in</span> <span m="622830">the</span>
  <span m="622900">middle</span> <span m="623400">are</span> <span m="623520">just</span>
  <span m="623600">forgotten</span> <span m="624250">by</span> <span m="624380">the</span>
  <span m="624580">computer.</span> <span m="626170">And</span> <span m="626500">all
  the</span> <span m="626830">derivatives</span> <span m="627460">have</span> <span
  m="627680">to</span> <span m="627780">be</span> <span m="627900">approximated</span>
  <span m="628800">by</span> <span m="629240">these</span> <span m="630290">discrete</span>
  <span m="630780">points.</span> <span m="631730">And</span> <span m="632010">this</span>
  <span m="632290">now</span> <span m="632600">seems</span> <span m="632970">natural</span>
  <span m="633320">to</span> <span m="633460">you</span> <span m="634040">for</span>
  <span m="634160">sure.</span> <span m="635340">But,</span> <span m="635740">as</span>
  <span m="635960">we</span> <span m="636100">go</span> <span m="636260">to</span>
  <span m="636370">find</span> <span m="636600">the</span> <span m="636700">volume,</span>
  <span m="637060">you are</span> <span m="637210">going</span> <span m="637330">to</span>
  <span m="637410">see</span> <span m="637560">how</span> <span m="637810">different</span>
  <span m="639510">discretization</span> <span m="640230">schemes</span> <span m="640720">are</span>
  <span m="640930">going</span> <span m="641070">to</span> <span m="641140">be</span>
  <span m="641340">discretizing</span> <span m="641510">a</span> <span m="642370">function.</span></p><p><span
  m="644520">OK</span> <span m="645310">so</span> <span m="646010">let''s</span> <span
  m="646390">try</span> <span m="646570">to</span> <span m="646690">implement</span>
  <span m="647310">a</span> <span m="647650">central</span> <span m="647990">difference</span>
  <span m="648360">plus</span> <span m="649030">forward</span> <span m="649310">Euler</span>
  <span m="650500">on</span> <span m="650840">the</span> <span m="651850">advection</span>
  <span m="652690">equation.</span> <span m="653020">So</span> <span m="653150">I</span>
  <span m="653260">haven''t</span> <span m="653400">said</span> <span m="653500">what</span>
  <span m="654010">equation</span> <span m="654280">I''m</span> <span m="654380">going</span>
  <span m="654500">to</span> <span m="654560">do</span> <span m="654850">yet.</span>
  <span m="655370">So</span> <span m="655530">I''m</span> <span m="655670">going</span>
  <span m="655860">to</span> <span m="656940">implement</span> <span m="657570">it</span>
  <span m="657750">on</span> <span m="657980">this</span> <span m="658200">equation.</span>
  <span m="658880">Partial</span> <span m="658950">U</span> <span m="659050">partial</span>
  <span m="659460">t</span> <span m="661224">plus</span> <span m="661665">partial</span>
  <span m="662106">U</span> <span m="662990">partial</span> <span m="663370">x</span>
  <span m="664080">is</span> <span m="664420">equal to</span> <span m="664880">zero.</span>
  <span m="666730">With</span> <span m="667170">a</span> <span m="667690">periodic</span>
  <span m="668350">boundary</span> <span m="668680">condition,</span> <span m="669576">you</span>
  <span m="670012">add</span> <span m="670450">0</span> <span m="671120">is</span>
  <span m="671480">equal</span> <span m="671900">to</span> <span m="672535">U at</span>
  <span m="673020">1.</span> <span m="675640">So</span> <span m="675830">this</span>
  <span m="676030">is</span> <span m="676230">a</span> <span m="676890">periodic</span>
  <span m="679950">boundary</span> <span m="680290">condition.</span> <span m="681040">So</span>
  <span m="681200">this</span> <span m="681350">is</span> <span m="681460">the</span>
  <span m="681560">same</span> <span m="681800">equation</span> <span m="682240">as</span>
  <span m="682470">we</span> <span m="683300">tried</span> <span m="683540">to</span>
  <span m="683830">animate</span> <span m="684120">last</span> <span m="684456">Thursday.</span>
  <span m="685130">Anybody</span> <span m="685510">who</span> <span m="685790">goes</span>
  <span m="686110">out</span> <span m="686425">of</span> <span m="686740">these</span>
  <span m="687090">doors</span> <span m="687480">comes back</span> <span m="688260">from</span>
  <span m="688470">inside</span> <span m="688820">here.</span> <span m="690060">So</span>
  <span m="690460">we</span> <span m="690640">should</span> <span m="690910">be</span>
  <span m="691080">seeing--</span> <span m="691610">this</span> <span m="691740">is</span>
  <span m="691880">the</span> <span m="691970">linear</span> <span m="692320">advection</span>
  <span m="692770">equation.</span> <span m="693920">And</span> <span m="694300">all</span>
  <span m="694550">the</span> <span m="694790">characteristic</span> <span m="695480">lines</span>
  <span m="696730">are</span> <span m="696940">parallel.</span> <span m="697910">The</span>
  <span m="698090">characteristic</span> <span m="698534">lines</span> <span m="698978">are</span>
  <span m="699422">like</span> <span m="699866">the</span> <span m="700310">colorful</span>
  <span m="700560">lines</span> <span m="700966">in</span> <span m="701372">the solution</span>
  <span m="701780">in</span> <span m="701950">the</span> <span m="702060">x and t</span>
  <span m="702390">diagram.</span></p><p><span m="705400">So</span> <span m="706790">all
  the</span> <span m="707040">characteristic</span> <span m="707490">points</span>
  <span m="708860">go</span> <span m="709180">towards</span> <span m="709610">the</span>
  <span m="709700">right,</span> <span m="712860">and</span> <span m="713180">along</span>
  <span m="713730">each</span> <span m="713920">characteristic</span> <span m="714620">line,</span>
  <span m="715310">the</span> <span m="715450">solution</span> <span m="715715">is</span>
  <span m="715980">constant.</span> <span m="719710">So</span> <span m="720200">let''s</span>
  <span m="720940">try</span> <span m="721090">to</span> <span m="721240">implement</span>
  <span m="722410">the</span> <span m="722660">forward</span> <span m="722920">order</span>
  <span m="723620">central</span> <span m="723910">difference</span> <span m="724460">and</span>
  <span m="724720">see</span> <span m="725120">how</span> <span m="725700">the</span>
  <span m="725820">solution</span> <span m="726280">looks</span> <span m="726560">like</span>
  <span m="727730">numerically.</span> <span m="730600">So</span> <span m="730750">I''m</span>
  <span m="730850">going</span> <span m="731030">to</span> <span m="732420">New file</span>
  <span m="732695">to</span> <span m="732970">Script.</span> <span m="734470">So</span>
  <span m="735470">central</span> <span m="736470">space,</span> <span m="738430">forward</span>
  <span m="739350">time.</span> <span m="741710">So</span> <span m="741840">this</span>
  <span m="741970">is</span> <span m="742030">my</span> <span m="742180">central</span>
  <span m="742510">space,</span> <span m="742975">forward</span> <span m="743440">time.</span>
  <span m="744370">I''m</span> <span m="744530">going</span> <span m="744650">to</span>
  <span m="744760">set</span> <span m="745070">up</span> <span m="745290">my</span>
  <span m="745480">number</span> <span m="745770">of</span> <span m="745880">grid</span>
  <span m="746130">points.</span> <span m="746760">Let''s</span> <span m="747220">just</span>
  <span m="747590">use</span> <span m="748100">100</span> <span m="748385">grid</span>
  <span m="748670">points</span> <span m="749000">in</span> <span m="749420">space.</span>
  <span m="753270">And</span> <span m="753540">because</span> <span m="754550">I</span>
  <span m="754800">have</span> <span m="755330">a</span> <span m="757130">domain</span>
  <span m="757580">from</span> <span m="757830">0</span> <span m="758090">to</span>
  <span m="758190">1,</span> <span m="758870">my</span> <span m="759170">delta</span>
  <span m="759450">x</span> <span m="759830">is</span> <span m="760130">equal</span>
  <span m="760380">to</span> <span m="760470">1</span> <span m="761020">divided</span>
  <span m="761440">by</span> <span m="762080">n.</span> <span m="763450">So</span>
  <span m="763640">this is</span> <span m="763800">my</span> <span m="764090">delta</span>
  <span m="764548">x.</span></p><p><span m="766840">Let</span> <span m="767020">me</span>
  <span m="767140">choose</span> <span m="767370">the</span> <span m="767510">initial</span>
  <span m="767930">solution</span> <span m="768410">that</span> <span m="768570">looks</span>
  <span m="769420">somewhat</span> <span m="769770">like</span> <span m="769970">Gaussian.</span>
  <span m="771320">OK,</span> <span m="771670">so</span> <span m="772040">we</span>
  <span m="772380">have</span> <span m="772550">a</span> <span m="772905">peak,</span>
  <span m="773260">and</span> <span m="773420">we see</span> <span m="773910">how</span>
  <span m="774080">the</span> <span m="774160">peak</span> <span m="774480">evolves.</span>
  <span m="775520">So</span> <span m="775730">let</span> <span m="775960">me,</span>
  <span m="776810">first</span> <span m="777080">of</span> <span m="777260">all,</span>
  <span m="777570">set</span> <span m="777650">my</span> <span m="777810">x</span>
  <span m="778690">equal</span> <span m="779120">to</span> <span m="779320">1:N</span>
  <span m="781000">times</span> <span m="781420">my</span> <span m="781600">dx.</span>
  <span m="782350">So</span> <span m="782520">I</span> <span m="782610">have</span>
  <span m="784260">a</span> <span m="784560">grid,</span> <span m="785360">and</span>
  <span m="785570">accessed</span> <span m="786040">the</span> <span m="786150">spacial</span>
  <span m="786590">location</span> <span m="786750">of the grid.</span> <span m="788880">And</span>
  <span m="789190">let''s</span> <span m="789280">set</span> <span m="790010">my</span>
  <span m="790150">u0</span> <span m="790860">my</span> <span m="790980">initial</span>
  <span m="791350">condition,</span> <span m="792900">to</span> <span m="793070">be</span>
  <span m="793240">exponential</span> <span m="794120">of</span> <span m="794390">minus</span>
  <span m="796270">x</span> <span m="797420">minus</span> <span m="798540">0.5</span>
  <span m="801820">squared,</span> <span m="803860">divided</span> <span m="804360">by</span>
  <span m="804790">0.1</span> <span m="806050">squared.</span> <span m="807550">And</span>
  <span m="808420">I</span> <span m="808520">have to</span> <span m="808730">do this</span>
  <span m="809000">divide.</span> <span m="810910">So</span> <span m="811050">we</span>
  <span m="811170">can</span> <span m="811370">take</span> <span m="811570">a</span>
  <span m="811640">look</span> <span m="811910">at</span> <span m="812030">how</span>
  <span m="812240">the</span> <span m="812350">solution</span> <span m="812770">looks</span>
  <span m="813030">like.</span></p><p><span m="813620">We</span> <span m="813750">can</span>
  <span m="813940">plot</span> <span m="814410">x</span> <span m="814710">and</span>
  <span m="814830">u0.</span> <span m="815460">And</span> <span m="815890">we</span>
  <span m="816040">are</span> <span m="816140">going</span> <span m="816300">to</span>
  <span m="816530">run</span> <span m="816780">the</span> <span m="816860">script</span>
  <span m="817210">to</span> <span m="817330">see</span> <span m="817770">how the</span>
  <span m="818040">solution</span> <span m="818396">looks like.</span> <span m="819110">So
  this</span> <span m="819350">is</span> <span m="819460">the</span> <span m="819540">initial</span>
  <span m="819770">condition.</span> <span m="821010">We</span> <span m="821150">have</span>
  <span m="821730">a</span> <span m="822450">Gaussian</span> <span m="822690">curve.</span>
  <span m="824341">The</span> <span m="824798">shape</span> <span m="825255">of</span>
  <span m="825712">the curve</span> <span m="826169">is</span> <span m="826630">exponential.</span>
  <span m="827540">1</span> <span m="827850">minus</span> <span m="829390">x</span>
  <span m="829675">minus</span> <span m="829960">0.5.</span> <span m="830447">So</span>
  <span m="830834">0.5</span> <span m="831221">is</span> <span m="831610">the</span>
  <span m="831950">central</span> <span m="832180">of the</span> <span m="832515">Gaussian.</span>
  <span m="833980">And</span> <span m="834170">the</span> <span m="834670">reason</span>
  <span m="835170">[INAUDIBLE]</span> <span m="836170">standard</span> <span m="836670">deviation</span>
  <span m="837170">can</span> <span m="837670">be plus</span> <span m="838170">1,</span>
  <span m="838670">[INAUDIBLE].</span> <span m="840280">The</span> <span m="840420">width</span>
  <span m="840490">of the</span> <span m="840830">Gaussian</span> <span m="841480">or</span>
  <span m="841670">half-width</span> <span m="842680">of</span> <span m="842990">the</span>
  <span m="843395">Gaussian.</span> <span m="844610">Any</span> <span m="844860">questions</span>
  <span m="845220">on</span> <span m="845390">this?</span> <span m="847740">No?</span>
  <span m="850010">OK.</span> <span m="851480">So</span> <span m="852590">let''s</span>
  <span m="853140">decide</span> <span m="853600">on</span> <span m="853720">a</span>
  <span m="853780">timestamp.</span> <span m="855940">What</span> <span m="856180">do</span>
  <span m="856657">you</span> <span m="857134">guys</span> <span m="857611">want</span>
  <span m="858088">on the</span> <span m="858565">timestamp?</span> <span m="862858">0.1?</span>
  <span m="863812">All right.</span></p><p><span m="868250">I</span> <span m="869610">goes</span>
  <span m="869880">from</span> <span m="870120">1</span> <span m="871240">to</span>
  <span m="871680">1/dt.</span> <span m="872290">So</span> <span m="872650">let''s</span>
  <span m="873010">simulate</span> <span m="873365">it</span> <span m="873720">for</span>
  <span m="873960">one</span> <span m="874290">time</span> <span m="874530">unit,</span>
  <span m="875400">because</span> <span m="875800">after</span> <span m="876110">one</span>
  <span m="876360">time</span> <span m="876850">unit,</span> <span m="878130">the</span>
  <span m="878620">speed</span> <span m="878850">of</span> <span m="879000">the</span>
  <span m="879230">solution</span> <span m="879640">going</span> <span m="879900">towards</span>
  <span m="880580">the</span> <span m="880680">right</span> <span m="880960">is</span>
  <span m="881200">1.</span> <span m="883680">That</span> <span m="883830">is</span>
  <span m="883960">because</span> <span m="884630">in</span> <span m="884790">my</span>
  <span m="884980">equation,</span> <span m="885800">I</span> <span m="886210">put</span>
  <span m="887710">if</span> <span m="887950">there</span> <span m="888600">should</span>
  <span m="888730">be</span> <span m="890830">a</span> <span m="890960">small</span>
  <span m="891280">c,</span> <span m="891610">then</span> <span m="891840">this</span>
  <span m="891940">c</span> <span m="892436">is</span> <span m="892932">equal</span>
  <span m="893430">to 1.</span> <span m="893920">So</span> <span m="894080">my</span>
  <span m="894590">speed</span> <span m="894800">of</span> <span m="894910">the</span>
  <span m="894990">solution</span> <span m="895240">going towards</span> <span m="895595">the</span>
  <span m="895950">right</span> <span m="896290">is</span> <span m="896400">equal
  to 1.</span> <span m="897250">So</span> <span m="897410">after</span> <span m="897700">one</span>
  <span m="897950">time</span> <span m="898200">unit,</span> <span m="898500">the</span>
  <span m="898610">solution</span> <span m="899050">should</span> <span m="899860">go</span>
  <span m="900300">through the</span> <span m="900620">domain</span> <span m="900920">once</span>
  <span m="901620">and</span> <span m="901900">end</span> <span m="902150">up</span>
  <span m="902400">exactly</span> <span m="902930">at</span> <span m="903040">the</span>
  <span m="903100">same</span> <span m="903360">location</span> <span m="904100">as</span>
  <span m="904530">the</span> <span m="904770">initial</span> <span m="905050">condition.</span></p><p><span
  m="908680">Now</span> <span m="910750">when</span> <span m="910990">I''m</span>
  <span m="911140">doing</span> <span m="911400">forward order,</span> <span m="912790">plus</span>
  <span m="913120">central</span> <span m="913390">difference,</span> <span m="914380">I</span>
  <span m="914530">need</span> <span m="914730">to</span> <span m="914850">first</span>
  <span m="916970">compute</span> <span m="918330">the</span> <span m="918510">dU/dx</span>
  <span m="919510">at</span> <span m="919900">each</span> <span m="920300">grid</span>
  <span m="920520">location.</span> <span m="921310">And</span> <span m="921570">dU/dx,</span>
  <span m="922910">at</span> <span m="923140">each</span> <span m="923300">grid</span>
  <span m="923490">location,</span> <span m="924390">is</span> <span m="924480">the</span>
  <span m="924590">difference</span> <span m="925090">between</span> <span m="925580">the</span>
  <span m="925670">solution</span> <span m="926290">towards</span> <span m="926520">the</span>
  <span m="926640">right</span> <span m="927610">minus</span> <span m="928050">the</span>
  <span m="928140">solution</span> <span m="928620">towards</span> <span m="928930">the</span>
  <span m="929000">left,</span> <span m="929950">divided</span> <span m="930300">by</span>
  <span m="930470">2</span> <span m="930710">delta</span> <span m="930960">x.</span>
  <span m="931620">And</span> <span m="931860">look</span> <span m="932050">carefully</span>
  <span m="932480">at</span> <span m="932640">how</span> <span m="932960">I''m</span>
  <span m="934480">computing</span> <span m="935130">the</span> <span m="935220">solution</span>
  <span m="935640">on</span> <span m="935730">the</span> <span m="935840">right</span>
  <span m="936050">and</span> <span m="936470">on</span> <span m="936630">the</span>
  <span m="936720">left.</span> <span m="937840">du dx</span> <span m="939310">is</span>
  <span m="939760">equal</span> <span m="940180">to--</span> <span m="942280">what</span>
  <span m="942490">I''m</span> <span m="942610">going</span> <span m="942740">to</span>
  <span m="942810">do</span> <span m="943040">is</span> <span m="943430">I''m</span>
  <span m="943590">going</span> <span m="943730">to</span> <span m="943810">do</span>
  <span m="944070">circshift</span> <span m="947060">of</span> <span m="947370">my</span>
  <span m="947860">u0,</span> <span m="949920">of</span> <span m="950270">my</span>
  <span m="950390">u.</span> <span m="950920">I''m</span> <span m="951980">first</span>
  <span m="952680">going to</span> <span m="952750">say</span> <span m="952830">u</span>
  <span m="953160">is</span> <span m="953645">equal</span> <span m="954130">to u0.</span>
  <span m="955255">[INAUDIBLE].</span> <span m="956470">I am</span> <span m="956560">going</span>
  <span m="956690">to</span> <span m="956770">do</span> <span m="956930">circshift</span>
  <span m="957500">of</span> <span m="957730">u,</span> <span m="958940">and</span>
  <span m="959170">I''m</span> <span m="959340">going</span> <span m="959500">to</span>
  <span m="959610">be</span> <span m="959800">shifting</span> <span m="961480">0</span>
  <span m="961850">on</span> <span m="962020">the</span> <span m="962110">first</span>
  <span m="962480">dimension</span> <span m="963510">and</span> <span m="963810">a</span>
  <span m="963860">-1</span> <span m="964570">on</span> <span m="964780">the</span>
  <span m="964860">second</span> <span m="965240">dimension.</span></p><p><span m="967620">So</span>
  <span m="967790">does</span> <span m="968120">this</span> <span m="968300">give</span>
  <span m="968590">me?</span> <span m="971410">I''m</span> <span m="971560">going</span>
  <span m="971690">to</span> <span m="971770">go</span> <span m="971930">back</span>
  <span m="972140">to</span> <span m="972220">Matlab</span> <span m="972630">and</span>
  <span m="972800">tell</span> <span m="973000">you</span> <span m="973493">what</span>
  <span m="973986">it gives</span> <span m="974480">us.</span> <span m="974660">So</span>
  <span m="975067">if</span> <span m="976290">I</span> <span m="976410">do</span>
  <span m="976720">1</span> <span m="977200">to</span> <span m="978480">10,</span>
  <span m="979310">for</span> <span m="979430">example,</span> <span m="979990">I''m</span>
  <span m="980020">going</span> <span m="980150">to</span> <span m="980240">get</span>
  <span m="980820">an</span> <span m="981000">array</span> <span m="981520">going</span>
  <span m="981760">from</span> <span m="981930">1</span> <span m="982100">to</span>
  <span m="982220">10.</span> <span m="984100">If</span> <span m="984280">I</span>
  <span m="984390">do</span> <span m="984580">circshift</span> <span m="986030">of</span>
  <span m="986310">1</span> <span m="986590">to</span> <span m="986810">10,</span>
  <span m="988490">I''m</span> <span m="988640">going</span> <span m="988770">to</span>
  <span m="988870">shift</span> <span m="989200">it--</span> <span m="989840">I''ll</span>
  <span m="990110">put</span> <span m="990190">0</span> <span m="990520">in</span>
  <span m="990620">the</span> <span m="990690">first</span> <span m="990960">dimension</span>
  <span m="991440">and</span> <span m="991890">1</span> <span m="992320">on</span>
  <span m="992530">the</span> <span m="992740">first</span> <span m="992970">dimension.</span>
  <span m="993650">This</span> <span m="993900">is</span> <span m="994240">what</span>
  <span m="994440">I''m</span> <span m="994540">going</span> <span m="994680">to</span>
  <span m="994740">get.</span> <span m="995990">I''m</span> <span m="996330">circularly</span>
  <span m="997322">picking</span> <span m="998314">these</span> <span m="999306">1</span>
  <span m="999802">to</span> <span m="1000300">10,</span> <span m="1000600">towards
  the right.</span> <span m="1001566">So instead</span> <span m="1002049">of 1 here,</span>
  <span m="1002532">I</span> <span m="1003015">get</span> <span m="1003500">[INAUDIBLE],</span>
  <span m="1003620">which is</span> <span m="1003750">why</span> <span m="1004100">this</span>
  <span m="1004360">method--</span> <span m="1004795">the</span> <span m="1005230">[INAUDIBLE]</span>
  <span m="1005665">method--</span> <span m="1006100">comes</span> <span m="1006535">out
  of the</span> <span m="1006970">[INAUDIBLE]</span> <span m="1007920">and</span>
  <span m="1008340">goes</span> <span m="1008610">here.</span> <span m="1009870">And</span>
  <span m="1009970">the</span> <span m="1010090">[INAUDIBLE]</span> <span m="1010850">is</span>
  <span m="1011080">that</span> <span m="1011570">[INAUDIBLE]</span> <span m="1013090">here.</span>
  <span m="1013500">Everybody''s</span> <span m="1014150">shifted</span> <span m="1014595">towards</span>
  <span m="1015040">the</span> <span m="1015400">right</span> <span m="1015910">1.</span></p><p><span
  m="1018710">Now</span> <span m="1019060">if</span> <span m="1019330">I</span> <span
  m="1019470">want</span> <span m="1020030">to</span> <span m="1020160">grab</span>
  <span m="1020650">the</span> <span m="1021650">i</span> <span m="1022150">plus</span>
  <span m="1022650">1</span> <span m="1023150">person</span> <span m="1024150">at</span>
  <span m="1024450">the</span> <span m="1024670">i</span> <span m="1025089">place,</span>
  <span m="1027020">this</span> <span m="1027280">is</span> <span m="1027640">the</span>
  <span m="1027839">opposite</span> <span m="1028339">of</span> <span m="1028480">what</span>
  <span m="1028961">I</span> <span m="1029442">need</span> <span m="1029923">to do.</span>
  <span m="1031849">What</span> <span m="1032099">I</span> <span m="1032180">need</span>
  <span m="1032369">to</span> <span m="1032460">do</span> <span m="1032859">is</span>
  <span m="1033140">I</span> <span m="1033230">need</span> <span m="1033410">to</span>
  <span m="1033500">put</span> <span m="1033790">-1</span> <span m="1034150">here</span>
  <span m="1034210">so</span> <span m="1034819">that</span> <span m="1035455">at</span>
  <span m="1035950">the</span> <span m="1036109">first</span> <span m="1036470">place,</span>
  <span m="1037069">I''m</span> <span m="1037319">going</span> <span m="1037450">to</span>
  <span m="1037520">be</span> <span m="1037700">grabbing</span> <span m="1037955">the</span>
  <span m="1038210">next</span> <span m="1038690">solution</span> <span m="1039170">and</span>
  <span m="1039650">the next</span> <span m="1040130">grid</span> <span m="1040610">point.</span>
  <span m="1042530">And</span> <span m="1042980">particularly</span> <span m="1043210">at</span>
  <span m="1043530">the</span> <span m="1043819">last</span> <span m="1044180">grid</span>
  <span m="1044659">point</span> <span m="1045619">I''m</span> <span m="1045880">grabbing</span>
  <span m="1047470">the</span> <span m="1047619">solution</span> <span m="1048946">[INAUDIBLE],</span>
  <span m="1050140">which is</span> <span m="1050590">actually</span> <span m="1051040">the</span>
  <span m="1051160">other</span> <span m="1051450">way</span> <span m="1051670">you''re</span>
  <span m="1052130">supposed to</span> <span m="1052590">do it on the</span> <span
  m="1053050">left</span> <span m="1053510">[INAUDIBLE],</span> <span m="1054430">which
  is</span> <span m="1054770">1.</span> <span m="1056085">So</span> <span m="1056510">this</span>
  <span m="1056740">is</span> <span m="1056870">the</span> <span m="1057010">way</span>
  <span m="1057350">you</span> <span m="1057780">can</span> <span m="1058210">[INAUDIBLE]</span>
  <span m="1058640">Ui</span> <span m="1058880">plus</span> <span m="1059135">1.</span>
  <span m="1060750">If</span> <span m="1061370">you</span> <span m="1061550">have</span>
  <span m="1061780">periodic</span> <span m="1062250">[INAUDIBLE].</span> <span m="1064600">What</span>
  <span m="1064710">about</span> <span m="1065360">Ui</span> <span m="1065740">minus</span>
  <span m="1066200">1?</span> <span m="1069420">This is</span> <span m="1069756">my</span>
  <span m="1070092">Ui</span> <span m="1070430">minus</span> <span m="1070560">1.</span>
  <span m="1071052">This is</span> <span m="1071544">my</span> <span m="1072036">Ui-1.</span>
  <span m="1076464">Any</span> <span m="1076956">questions</span> <span m="1077448">on</span>
  <span m="1077940">that?</span> <span m="1080400">Someone</span> <span m="1080892">said
  it</span> <span m="1081384">back there?</span></p><p><span m="1083844">STUDENT:</span>
  <span m="1084336">[INAUDIBLE]?</span></p><p><span m="1088764">QIQI WANG: Yeah.</span>
  <span m="1089256">On this</span> <span m="1089748">one,</span> <span m="1090240">things
  are</span> <span m="1090732">being rotated</span> <span m="1091224">towards</span>
  <span m="1091716">the left.</span> <span m="1094690">The</span> <span m="1094960">1</span>
  <span m="1095360">which is</span> <span m="1095695">here</span> <span m="1096030">now</span>
  <span m="1096871">was</span> <span m="1097352">the</span> <span m="1097833">end.</span>
  <span m="1099276">And</span> <span m="1099757">the</span> <span m="1100238">2</span>
  <span m="1100719">[INAUDIBLE]</span> <span m="1101681">here</span> <span m="1102162">now</span>
  <span m="1102643">is</span> <span m="1103130">here.</span> <span m="1103480">3</span>
  <span m="1103949">was</span> <span m="1104418">here,</span> <span m="1104887">here.</span>
  <span m="1109110">Yes?</span></p><p><span m="1109839">STUDENT:</span> <span m="1110328">[INAUDIBLE]?</span></p><p><span
  m="1121575">QIQI WANG: So</span> <span m="1122070">in</span> <span m="1122710">the</span>
  <span m="1122820">ODE</span> <span m="1123290">part,</span> <span m="1124210">why</span>
  <span m="1124520">didn''t</span> <span m="1124860">we</span> <span m="1125040">do</span>
  <span m="1125457">a</span> <span m="1125874">circshift?</span> <span m="1127000">The</span>
  <span m="1127120">answer</span> <span m="1127480">is</span> <span m="1127670">in
  the</span> <span m="1127810">ODE</span> <span m="1128300">part, we</span> <span
  m="1128480">didn''t</span> <span m="1128800">do</span> <span m="1129300">a</span>
  <span m="1129480">circshift,</span> <span m="1130220">because</span> <span m="1130890">we</span>
  <span m="1131220">don''t</span> <span m="1131540">have</span> <span m="1131860">the</span>
  <span m="1132010">solution</span> <span m="1132590">at</span> <span m="1132880">ndx.</span>
  <span m="1133540">So</span> <span m="1133770">when</span> <span m="1134380">we</span>
  <span m="1134510">are</span> <span m="1134670">at</span> <span m="1134790">the</span>
  <span m="1134910">end</span> <span m="1135270">timestamp,</span> <span m="1136070">we</span>
  <span m="1136290">don''t</span> <span m="1136610">have the</span> <span m="1136900">solution</span>
  <span m="1137384">at the</span> <span m="1137868">n plus 1</span> <span m="1138352">timestamp.</span>
  <span m="1140290">While</span> <span m="1140720">in</span> <span m="1140930">the</span>
  <span m="1141040">PV</span> <span m="1141590">part,</span> <span m="1144270">we</span>
  <span m="1144500">have</span> <span m="1144690">a</span> <span m="1144750">grid</span>
  <span m="1145210">like</span> <span m="1145320">this,</span> <span m="1146470">and</span>
  <span m="1146670">we</span> <span m="1146830">are</span> <span m="1146970">given</span>
  <span m="1147780">the</span> <span m="1147930">whole</span> <span m="1148340">initial</span>
  <span m="1148770">conditions.</span> <span m="1149330">So I''ve</span> <span m="1149720">given</span>
  <span m="1150460">the</span> <span m="1150660">whole</span> <span m="1150910">initial</span>
  <span m="1151270">condition</span> <span m="1151770">at</span> <span m="1151990">[?
  p ?]</span> <span m="1152250">equal to</span> <span m="1152510">0.</span> <span
  m="1153780">So we</span> <span m="1154120">have all the</span> <span m="1154200">data</span>
  <span m="1155170">at</span> <span m="1155655">this</span> <span m="1156140">timestamp.</span>
  <span m="1157110">Now</span> <span m="1157430">our</span> <span m="1157810">job
  is</span> <span m="1158110">to</span> <span m="1158510">go</span> <span m="1158740">from
  this</span> <span m="1159218">timestamp to</span> <span m="1159696">this</span>
  <span m="1160174">timestamp.</span> <span m="1160652">We</span> <span m="1161130">want</span>
  <span m="1161608">to</span> <span m="1162090">compute</span> <span m="1162390">from
  the</span> <span m="1162490">solution</span> <span m="1163090">here</span> <span
  m="1163720">all</span> <span m="1164210">the</span> <span m="1164700">solutions</span>
  <span m="1165190">on these</span> <span m="1165680">grid points.</span> <span m="1166170">And</span>
  <span m="1166660">then we</span> <span m="1167150">go</span> <span m="1167420">forward</span>
  <span m="1167700">and</span> <span m="1168010">forward</span> <span m="1168320">and</span>
  <span m="1168796">forward.</span></p><p><span m="1170700">So there</span> <span
  m="1171180">is</span> <span m="1171530">a</span> <span m="1172010">fundamental</span>
  <span m="1172970">difference</span> <span m="1173930">between</span> <span m="1174890">space</span>
  <span m="1175370">and</span> <span m="1175850">time.</span> <span m="1177300">In
  time,</span> <span m="1178690">you</span> <span m="1178955">don''t</span> <span
  m="1179220">know</span> <span m="1179475">what</span> <span m="1179730">is</span>
  <span m="1179860">going</span> <span m="1180100">to happen</span> <span m="1180380">tomorrow,</span>
  <span m="1180690">right?</span> <span m="1182580">In space,</span> <span m="1183330">we</span>
  <span m="1183540">have</span> <span m="1183790">access</span> <span m="1184095">to</span>
  <span m="1184400">the</span> <span m="1184860">solution</span> <span m="1186990">at</span>
  <span m="1187050">all the</span> <span m="1187320">spatial</span> <span m="1187810">locations.</span>
  <span m="1188792">At</span> <span m="1189283">the</span> <span m="1189774">current</span>
  <span m="1190265">timestamp,</span> <span m="1191250">and</span> <span m="1191440">if</span>
  <span m="1191620">you</span> <span m="1191760">stored</span> <span m="1192153">the
  past</span> <span m="1192546">timestamps,</span> <span m="1192940">also</span> <span
  m="1193230">at</span> <span m="1193520">the</span> <span m="1194012">past</span>
  <span m="1194996">timestamps</span> <span m="1195490">so you</span> <span m="1195550">know
  all</span> <span m="1196020">these things.</span></p><p><span m="1199900">So</span>
  <span m="1200390">that''s</span> <span m="1200530">the</span> <span m="1200710">difference</span>
  <span m="1201133">between</span> <span m="1203250">space</span> <span m="1203520">and</span>
  <span m="1203670">time.</span> <span m="1203830">Although,</span> <span m="1205010">doing</span>
  <span m="1205420">Taylor</span> <span m="1205720">series</span> <span m="1206100">analyses</span>
  <span m="1206600">on</span> <span m="1206710">them</span> <span m="1206910">are
  the</span> <span m="1207120">same.</span> <span m="1208190">But in</span> <span
  m="1208330">terms</span> <span m="1208580">of</span> <span m="1208720">coding,</span>
  <span m="1209740">they</span> <span m="1209900">are</span> <span m="1210330">different.</span>
  <span m="1210720">In</span> <span m="1210840">terms</span> <span m="1211070">of</span>
  <span m="1211200">the</span> <span m="1211360">order</span> <span m="1211730">of</span>
  <span m="1211950">computation,</span> <span m="1212590">they</span> <span m="1212720">are</span>
  <span m="1213180">different.</span></p><p><span m="1217470">So</span> <span m="1217950">going</span>
  <span m="1218200">back</span> <span m="1218420">to</span> <span m="1218520">our</span>
  <span m="1219030">Matlab</span> <span m="1219330">code, we</span> <span m="1219580">shift</span>
  <span m="1220840">towards</span> <span m="1221110">the</span> <span m="1221190">-1</span>
  <span m="1221690">direction</span> <span m="1222360">that</span> <span m="1222520">is</span>
  <span m="1222660">grabbing</span> <span m="1223100">Ui</span> <span m="1223290">plus</span>
  <span m="1223460">1.</span> <span m="1226040">If</span> <span m="1226290">we</span>
  <span m="1226460">shift</span> <span m="1226750">the</span> <span m="1226840">whole</span>
  <span m="1227070">thing</span> <span m="1227350">towards</span> <span m="1227766">the</span>
  <span m="1228182">positive 1</span> <span m="1228600">direction,</span> <span m="1229400">we</span>
  <span m="1229500">are</span> <span m="1229990">grabbing</span> <span m="1230500">ui.</span>
  <span m="1231660">And</span> <span m="1231870">if</span> <span m="1232050">we</span>
  <span m="1232170">divide</span> <span m="1232710">that</span> <span m="1232910">by</span>
  <span m="1233080">2dx,</span> <span m="1234570">we</span> <span m="1234750">are</span>
  <span m="1235060">computing</span> <span m="1235560">du dx,</span> <span m="1236560">right?</span></p><p><span
  m="1240750">So</span> <span m="1240890">now</span> <span m="1241150">we</span> <span
  m="1241290">have</span> <span m="1241570">du dx,</span> <span m="1242610">we</span>
  <span m="1242760">want</span> <span m="1242980">to</span> <span m="1243110">plug</span>
  <span m="1243690">this</span> <span m="1243960">into</span> <span m="1244290">this</span>
  <span m="1244500">equation.</span> <span m="1248066">dU/dt,</span> <span m="1249490">in</span>
  <span m="1249550">this</span> <span m="1249740">case,</span> <span m="1250280">is</span>
  <span m="1250530">equal</span> <span m="1250740">to</span> <span m="1251130">minus</span>
  <span m="1251520">of</span> <span m="1251992">du</span> <span m="1252464">dx.</span>
  <span m="1254460">This</span> <span m="1254790">is</span> <span m="1254970">what</span>
  <span m="1255140">this</span> <span m="1255290">equation</span> <span m="1255710">is.</span>
  <span m="1256550">If</span> <span m="1256850">you</span> <span m="1257160">shift
  du dx</span> <span m="1257470">towards</span> <span m="1257885">the</span> <span
  m="1258300">right-hand</span> <span m="1258715">side,</span> <span m="1259130">du</span>
  <span m="1259420">dt</span> <span m="1259710">would</span> <span m="1259930">be</span>
  <span m="1260480">minus</span> <span m="1260928">of</span> <span m="1261376">du</span>
  <span m="1261824">dx.</span> <span m="1263620">So</span> <span m="1263880">that''s</span>
  <span m="1264150">what</span> <span m="1264360">we</span> <span m="1264450">are</span>
  <span m="1264520">going</span> <span m="1264650">to</span> <span m="1264790">do.</span>
  <span m="1264900">du dt</span> <span m="1265090">is</span> <span m="1265570">equal</span>
  <span m="1266050">to</span> <span m="1266530">minus</span> <span m="1267010">du</span>
  <span m="1267490">dx</span> <span m="1269410">We</span> <span m="1269650">used</span>
  <span m="1270220">the</span> <span m="1270390">partial</span> <span m="1270750">differential</span>
  <span m="1271160">equation</span> <span m="1272220">to</span> <span m="1272360">convert</span>
  <span m="1272725">a</span> <span m="1273090">spatial</span> <span m="1273320">derivative</span>
  <span m="1275230">into</span> <span m="1275530">a</span> <span m="1276016">time</span>
  <span m="1276502">derivative.</span> <span m="1276990">This</span> <span m="1277390">is</span>
  <span m="1278230">the</span> <span m="1278450">result</span> <span m="1278920">of</span>
  <span m="1279100">using</span> <span m="1279560">the</span> <span m="1279660">partial</span>
  <span m="1279930">differential</span> <span m="1279990">equation.</span></p><p><span
  m="1284358">So</span> <span m="1284824">the</span> <span m="1285290">first step,</span>
  <span m="1285760">find</span> <span m="1285930">the</span> <span m="1286050">difference</span>
  <span m="1286190">approximation</span> <span m="1286460">of the</span> <span m="1286810">spatial</span>
  <span m="1287286">derivative,</span> <span m="1288714">the</span> <span m="1289190">partial</span>
  <span m="1289666">derivative</span> <span m="1290142">of</span> <span m="1290618">x.</span>
  <span m="1291094">Use</span> <span m="1291570">the</span> <span m="1292046">differential</span>
  <span m="1292530">equation</span> <span m="1292630">to</span> <span m="1293000">get
  the</span> <span m="1293428">time derivative.</span> <span m="1295140">And</span>
  <span m="1295660">anybody</span> <span m="1295790">want</span> <span m="1296080">to</span>
  <span m="1296563">suggest</span> <span m="1297046">what</span> <span m="1297530">is</span>
  <span m="1297940">next?</span> <span m="1303500">Are</span> <span m="1303670">we</span>
  <span m="1303840">back</span> <span m="1304200">into</span> <span m="1304310">the</span>
  <span m="1304480">ODE</span> <span m="1304960">world?</span> <span m="1306650">We</span>
  <span m="1306810">are</span> <span m="1306910">back</span> <span m="1307210">into</span>
  <span m="1307310">the</span> <span m="1307480">ODE</span> <span m="1307720">world.</span>
  <span m="1309430">We</span> <span m="1309610">have</span> <span m="1309860">computed</span>
  <span m="1310130">the</span> <span m="1310490">time</span> <span m="1310932">derivative</span>
  <span m="1312260">of</span> <span m="1312480">the</span> <span m="1312580">solution</span>
  <span m="1313060">at</span> <span m="1313540">all</span> <span m="1314020">the</span>
  <span m="1314430">grid</span> <span m="1314720">points</span> <span m="1314980">we</span>
  <span m="1315170">had.</span> <span m="1317740">We</span> <span m="1318220">can</span>
  <span m="1318700">use</span> <span m="1318990">forward</span> <span m="1319050">order.</span>
  <span m="1322296">From</span> <span m="1322690">the</span> <span m="1322810">cutoff,</span>
  <span m="1323570">we</span> <span m="1323750">can</span> <span m="1324000">use</span>
  <span m="1325272">[INAUDIBLE]</span> <span m="1325700">or</span> <span m="1327210">other</span>
  <span m="1327950">sexy</span> <span m="1328270">things</span> <span m="1328630">we</span>
  <span m="1328690">learned</span> <span m="1328940">in</span> <span m="1329680">the</span>
  <span m="1329760">ODE</span> <span m="1330100">section.</span></p><p><span m="1332030">So</span>
  <span m="1332380">let''s</span> <span m="1333320">do</span> <span m="1333490">the</span>
  <span m="1334000">most</span> <span m="1334410">elementary</span> <span m="1335050">thing</span>
  <span m="1335370">and</span> <span m="1335890">apply</span> <span m="1336220">forward</span>
  <span m="1336520">order.</span> <span m="1337220">u</span> <span m="1337610">is</span>
  <span m="1337910">going</span> <span m="1338050">to</span> <span m="1338140">equal</span>
  <span m="1338590">u</span> <span m="1339087">plus</span> <span m="1340081">dt</span>
  <span m="1340578">times</span> <span m="1341075">du</span> <span m="1341572">dt.</span>
  <span m="1342420">This</span> <span m="1342640">is</span> <span m="1343350">exactly</span>
  <span m="1343890">how</span> <span m="1344200">you</span> <span m="1344600">implement</span>
  <span m="1345516">forward</span> <span m="1345974">order</span> <span m="1346432">in</span>
  <span m="1346890">ODE.</span> <span m="1350600">So</span> <span m="1351880">we</span>
  <span m="1352080">already</span> <span m="1352450">plotted</span> <span m="1352910">the</span>
  <span m="1353190">solution</span> <span m="1353700">at</span> <span m="1353850">the</span>
  <span m="1353940">initial</span> <span m="1354250">condition.</span> <span m="1354720">Let''s</span>
  <span m="1355080">also</span> <span m="1355470">hold</span> <span m="1355810">on</span>
  <span m="1356360">so</span> <span m="1356520">that</span> <span m="1356800">we</span>
  <span m="1357000">don''t</span> <span m="1357320">lose</span> <span m="1357770">the</span>
  <span m="1357870">plot</span> <span m="1358250">of</span> <span m="1358370">the</span>
  <span m="1358450">initial</span> <span m="1358740">condition</span> <span m="1359230">and</span>
  <span m="1359600">also plot</span> <span m="1359970">my</span> <span m="1360160">x</span>
  <span m="1360960">and</span> <span m="1361200">u</span> <span m="1361530">at</span>
  <span m="1361750">t</span> <span m="1362090">equal</span> <span m="1362160">to</span>
  <span m="1362470">1.</span> <span m="1363502">And let''s</span> <span m="1363990">see</span>
  <span m="1364200">how</span> <span m="1364460">the</span> <span m="1364560">solution</span>
  <span m="1364970">will</span> <span m="1365060">look</span> <span m="1365300">like.</span>
  <span m="1367520">And</span> <span m="1367850">let''s</span> <span m="1368180">actually</span>
  <span m="1368530">plot</span> <span m="1368920">this in</span> <span m="1369180">red,</span>
  <span m="1369540">because</span> <span m="1369830">the</span> <span m="1369910">initial</span>
  <span m="1370160">condition</span> <span m="1370540">is</span> <span m="1370770">going</span>
  <span m="1370910">to</span> <span m="1370980">be--</span> <span m="1371880">let''s</span>
  <span m="1372120">plot the</span> <span m="1372360">initial</span> <span m="1372450">condition</span>
  <span m="1373240">black</span> <span m="1374110">and</span> <span m="1374540">the</span>
  <span m="1374960">solution</span> <span m="1375420">red</span> <span m="1375790">and</span>
  <span m="1376040">see</span> <span m="1376290">how</span> <span m="1376560">it</span>
  <span m="1376650">looks</span> <span m="1376850">like.</span> <span m="1380359">We</span>
  <span m="1380836">get</span> <span m="1383230">a</span> <span m="1383380">pretty</span>
  <span m="1383760">big</span> <span m="1383970">solution.</span></p><p><span m="1387580">This</span>
  <span m="1387880">may</span> <span m="1388050">not</span> <span m="1388340">be</span>
  <span m="1388460">the</span> <span m="1388580">fault</span> <span m="1388880">of</span>
  <span m="1389790">spatial</span> <span m="1390190">derivatives,</span> <span m="1390740">though,</span>
  <span m="1391560">because</span> <span m="1392110">we</span> <span m="1392280">know</span>
  <span m="1392490">forward</span> <span m="1392780">order</span> <span m="1394060">has</span>
  <span m="1394250">a</span> <span m="1394300">pretty</span> <span m="1394660">limited</span>
  <span m="1395170">stability</span> <span m="1395900">region.</span> <span m="1397330">But</span>
  <span m="1397520">we</span> <span m="1397640">know</span> <span m="1398460">forward</span>
  <span m="1398800">order</span> <span m="1399410">is</span> <span m="1399670">0</span>
  <span m="1400010">stable.</span> <span m="1401250">Which</span> <span m="1401530">means</span>
  <span m="1401780">what?</span> <span m="1403670">Which</span> <span m="1403900">means</span>
  <span m="1404120">there</span> <span m="1404270">it is</span> <span m="1404380">always</span>
  <span m="1404650">going</span> <span m="1405085">to</span> <span m="1405520">shrink</span>
  <span m="1405955">the</span> <span m="1406390">timestamp.</span> <span m="1407180">Which</span>
  <span m="1407410">means</span> <span m="1407690">it is</span> <span m="1407860">globally</span>
  <span m="1408380">accurate.</span> <span m="1408980">And</span> <span m="1409430">global</span>
  <span m="1409780">accuracy</span> <span m="1410360">means</span> <span m="1410680">when</span>
  <span m="1410840">you</span> <span m="1411250">make</span> <span m="1411500">the</span>
  <span m="1411580">timestamp</span> <span m="1412070">smaller,</span> <span m="1413300">the</span>
  <span m="1413390">solution</span> <span m="1413920">of</span> <span m="1414080">the</span>
  <span m="1414190">ODE</span> <span m="1414670">at</span> <span m="1414820">least</span>
  <span m="1415440">converges</span> <span m="1415860">to</span> <span m="1416780">the</span>
  <span m="1416860">[INAUDIBLE]</span> <span m="1417170">solution</span> <span m="1417330">of</span>
  <span m="1417410">the</span> <span m="1417790">ODE.</span> <span m="1418150">So</span>
  <span m="1418310">let''s</span> <span m="1418570">see</span> <span m="1418930">if</span>
  <span m="1419140">it</span> <span m="1419230">helps</span> <span m="1419510">in</span>
  <span m="1419620">this</span> <span m="1419800">case.</span> <span m="1420510">Let''s</span>
  <span m="1420740">make</span> <span m="1421200">delta</span> <span m="1421500">t</span>
  <span m="1421990">equal</span> <span m="1422270">to</span> <span m="1422650">0.001,</span>
  <span m="1424700">and</span> <span m="1424870">let''s</span> <span m="1425070">run</span>
  <span m="1425260">it</span> <span m="1425390">again.</span> <span m="1426220">Let</span>
  <span m="1426660">me</span> <span m="1427100">close</span> <span m="1427540">all</span>
  <span m="1427980">before</span> <span m="1428300">I do the</span> <span m="1428782">plot.</span></p><p><span
  m="1435048">This</span> <span m="1435530">time,</span> <span m="1436012">we</span>
  <span m="1436494">get</span> <span m="1436976">pretty</span> <span m="1437458">good.</span>
  <span m="1439870">We</span> <span m="1440230">do</span> <span m="1441033">see</span>
  <span m="1441486">the</span> <span m="1441940">solution</span> <span m="1443420">having</span>
  <span m="1444360">a</span> <span m="1444840">pretty</span> <span m="1445320">good</span>
  <span m="1445800">match with the</span> <span m="1446000">analytical</span> <span
  m="1446300">solution.</span> <span m="1447070">And</span> <span m="1447280">let''s</span>
  <span m="1447630">also</span> <span m="1448050">visualize</span> <span m="1448740">how</span>
  <span m="1449890">this</span> <span m="1450170">thing</span> <span m="1450440">progesses.</span>
  <span m="1450765">For</span> <span m="1451515">every</span> <span m="1452330">timestamp,</span>
  <span m="1453440">let</span> <span m="1453930">me</span> <span m="1454090">actually</span>
  <span m="1455070">do</span> <span m="1455220">the</span> <span m="1455350">plotting.</span>
  <span m="1456205">For</span> <span m="1456470">every</span> <span m="1456730">timestamp,</span>
  <span m="1459890">let</span> <span m="1460320">me</span> <span m="1461690">do</span>
  <span m="1461870">the</span> <span m="1461970">visualization</span> <span m="1462665">at</span>
  <span m="1463850">clf</span> <span m="1464450">which</span> <span m="1464640">means</span>
  <span m="1464900">clear</span> <span m="1465280">the</span> <span m="1465450">figure.</span>
  <span m="1466680">I''m</span> <span m="1466830">going</span> <span m="1466980">to</span>
  <span m="1467050">plot</span> <span m="1467560">the</span> <span m="1468150">initial</span>
  <span m="1468520">condition.</span> <span m="1469140">I''m</span> <span m="1469290">going</span>
  <span m="1469380">to</span> <span m="1469470">hold</span> <span m="1469690">on.</span>
  <span m="1471320">And</span> <span m="1471990">I''m</span> <span m="1472290">going</span>
  <span m="1472510">to</span> <span m="1473040">plot</span> <span m="1476330">the</span>
  <span m="1476650">solution.</span> <span m="1482100">So I''m</span> <span m="1482270">clearing
  the</span> <span m="1482690">figure,</span> <span m="1482780">plotting</span> <span
  m="1482900">the</span> <span m="1483230">initial</span> <span m="1483620">condition,</span>
  <span m="1484150">plotting</span> <span m="1484770">the</span> <span m="1485320">solution.</span>
  <span m="1486230">And</span> <span m="1486530">then</span> <span m="1486600">you</span>
  <span m="1486780">could</span> <span m="1487180">do</span> <span m="1487310">draw</span>
  <span m="1487560">now.</span> <span m="1488570">So</span> <span m="1488600">let''s</span>
  <span m="1488870">take</span> <span m="1489110">a</span> <span m="1489160">look</span>
  <span m="1489400">at</span> <span m="1489520">how--</span> <span m="1490390">let
  me</span> <span m="1490580">actually</span> <span m="1490940">pause</span> <span
  m="1491390">for</span> <span m="1491530">a</span> <span m="1491570">little</span>
  <span m="1491810">bit.</span> <span m="1492170">Pause</span> <span m="1492460">for</span>
  <span m="1492930">0.01</span> <span m="1493260">seconds</span> <span m="1493750">so
  that</span> <span m="1494240">we</span> <span m="1494730">can</span> <span m="1495150">actually</span>
  <span m="1495500">see</span> <span m="1495660">the</span> <span m="1495780">solution</span>
  <span m="1496230">moving.</span></p><p><span m="1501820">So</span> <span m="1501980">the</span>
  <span m="1502110">red</span> <span m="1502400">one</span> <span m="1503140">is</span>
  <span m="1503520">my</span> <span m="1503730">solution</span> <span m="1504780">as</span>
  <span m="1505050">my</span> <span m="1505386">time</span> <span m="1506060">goes</span>
  <span m="1506813">from</span> <span m="1507226">0</span> <span m="1507640">to</span>
  <span m="1508030">1.</span> <span m="1509990">So does it</span> <span m="1510320">look
  like</span> <span m="1510780">we</span> <span m="1511040">are</span> <span m="1511300">capturing</span>
  <span m="1511540">at</span> <span m="1511900">least</span> <span m="1512330">the</span>
  <span m="1512660">qualitative</span> <span m="1513610">behavior</span> <span m="1513930">of</span>
  <span m="1514250">the</span> <span m="1514713">analytical</span> <span m="1516318">solution?</span>
  <span m="1519070">Yes.</span> <span m="1521490">Although,</span> <span m="1522010">it</span>
  <span m="1522250">is</span> <span m="1522490">not</span> <span m="1522840">completely</span>
  <span m="1523302">satisfactory,</span> <span m="1524226">because</span> <span m="1525150">[INAUDIBLE]</span>
  <span m="1528090">and</span> <span m="1528440">the</span> <span m="1528510">solution</span>
  <span m="1528960">seems</span> <span m="1529280">to</span> <span m="1529430">be</span>
  <span m="1530270">growing</span> <span m="1530670">a</span> <span m="1530730">little</span>
  <span m="1530990">bit.</span></p><p><span m="1532373">STUDENT:</span> <span m="1532834">[INAUDIBLE].</span></p><p><span
  m="1538200">QIQI WANG: And</span> <span m="1538450">also,</span> <span m="1539930">another</span>
  <span m="1540290">concerning</span> <span m="1540880">point</span> <span m="1541607">you
  have</span> <span m="1542064">[INAUDIBLE]</span> <span m="1542978">is</span> <span
  m="1543435">that</span> <span m="1544350">the</span> <span m="1544490">solution</span>
  <span m="1544920">initially</span> <span m="1545350">was</span> <span m="1545460">all</span>
  <span m="1545810">positive.</span> <span m="1548024">And</span> <span m="1548510">you
  can</span> <span m="1548680">look at</span> <span m="1548960">my</span> <span m="1549450">analytical</span>
  <span m="1549940">graphing</span> <span m="1550430">for</span> <span m="1550920">the</span>
  <span m="1551410">initial</span> <span m="1551820">condition</span> <span m="1552295">where</span>
  <span m="1552770">[INAUDIBLE]</span> <span m="1553245">quantity.</span> <span m="1554195">It''s
  the</span> <span m="1554670">exponential of</span> <span m="1554880">something.</span>
  <span m="1555200">How</span> <span m="1555635">can it</span> <span m="1556070">not</span>
  <span m="1556300">be</span> <span m="1556789">positive?</span> <span m="1557767">But,</span>
  <span m="1558256">like</span> <span m="1558745">[INAUDIBLE],</span> <span m="1559234">it
  becomes</span> <span m="1559723">negative</span> <span m="1560212">at</span> <span
  m="1560701">some point.</span> <span m="1561190">So</span> <span m="1561520">it</span>
  <span m="1561973">overshoots</span> <span m="1563332">and</span> <span m="1563785">undershoots.</span>
  <span m="1565690">I</span> <span m="1565920">mean,</span> <span m="1566100">we''re</span>
  <span m="1566280">not</span> <span m="1566440">going</span> <span m="1566570">to</span>
  <span m="1566660">discuss</span> <span m="1567220">this</span> <span m="1568520">today.</span>
  <span m="1568870">But</span> <span m="1569390">we''re</span> <span m="1569580">going</span>
  <span m="1569700">to</span> <span m="1569760">be</span> <span m="1569820">discussing</span>
  <span m="1571040">the</span> <span m="1571240">reason</span> <span m="1572100">of</span>
  <span m="1572450">this</span> <span m="1573240">error,</span> <span m="1576830">both</span>
  <span m="1577640">on</span> <span m="1577920">Wednesday--</span> <span m="1579030">Professor</span>
  <span m="1579420">Wilcox</span> <span m="1579900">is</span> <span m="1580850">going</span>
  <span m="1580990">to</span> <span m="1581310">teach</span> <span m="1581560">on</span>
  <span m="1581680">Wednesday.</span> <span m="1582510">And</span> <span m="1584230">on</span>
  <span m="1585350">the</span> <span m="1585520">error</span> <span m="1586390">of</span>
  <span m="1587790">this</span> <span m="1588290">finite</span> <span m="1588660">difference</span>
  <span m="1588990">method.</span> <span m="1590421">How</span> <span m="1590900">to</span>
  <span m="1591190">analyze</span> <span m="1591450">this</span> <span m="1591710">error</span>
  <span m="1591940">and</span> <span m="1592403">convergence.</span> <span m="1593330">And</span>
  <span m="1593960">another,</span> <span m="1594580">very</span> <span m="1594890">related</span>
  <span m="1595160">issue</span> <span m="1596040">is</span> <span m="1596480">stability.</span>
  <span m="1598130">That</span> <span m="1598300">is</span> <span m="1598430">something</span>
  <span m="1598840">we</span> <span m="1598960">are</span> <span m="1599100">also</span>
  <span m="1599320">going</span> <span m="1599460">to</span> <span m="1599530">be</span>
  <span m="1599610">discussing</span> <span m="1600620">in</span> <span m="1600740">the</span>
  <span m="1600850">PDE</span> <span m="1601290">section.</span></p><p><span m="1602140">But</span>
  <span m="1603300">this</span> <span m="1603500">class,</span> <span m="1603930">we</span>
  <span m="1604040">are</span> <span m="1604100">just</span> <span m="1604370">happy</span>
  <span m="1604760">we</span> <span m="1605640">got a</span> <span m="1605940">solution.</span>
  <span m="1608120">And</span> <span m="1608610">we</span> <span m="1608750">can</span>
  <span m="1608920">also</span> <span m="1609270">see</span> <span m="1609850">that</span>
  <span m="1610060">the</span> <span m="1610150">solution</span> <span m="1610970">is</span>
  <span m="1611360">going</span> <span m="1611520">to</span> <span m="1611580">get</span>
  <span m="1612100">better</span> <span m="1612970">as</span> <span m="1613270">I</span>
  <span m="1613380">make</span> <span m="1613790">my</span> <span m="1614800">grid</span>
  <span m="1615080">to</span> <span m="1615250">be</span> <span m="1615380">finer.</span>
  <span m="1616630">Instead</span> <span m="1617010">of</span> <span m="1617220">100,</span>
  <span m="1617650">let''s</span> <span m="1618080">do</span> <span m="1618340">200,</span>
  <span m="1619690">and</span> <span m="1619930">we</span> <span m="1620080">run</span>
  <span m="1620330">the</span> <span m="1620420">same</span> <span m="1620720">thing.</span>
  <span m="1623540">It''s</span> <span m="1623770">going</span> <span m="1623930">to</span>
  <span m="1624010">get</span> <span m="1624370">slower,</span> <span m="1624752">but</span>
  <span m="1625900">the</span> <span m="1626020">rate</span> <span m="1626370">of</span>
  <span m="1626510">growth</span> <span m="1627010">is</span> <span m="1627430">going</span>
  <span m="1627600">to</span> <span m="1627680">be</span> <span m="1627910">not</span>
  <span m="1628190">as</span> <span m="1628410">severe</span> <span m="1629754">as</span>
  <span m="1630650">in</span> <span m="1630820">the</span> <span m="1630900">100</span>
  <span m="1631387">case.</span></p><p><span m="1643220">[INAUDIBLE].</span> <span
  m="1645682">Don''t</span> <span m="1646178">really</span> <span m="1646674">see</span>
  <span m="1647170">the</span> <span m="1647410">undershooting</span> <span m="1647910">[INAUDIBLE]</span>
  <span m="1651910">for</span> <span m="1653170">the</span> <span m="1653330">[INAUDIBLE]</span>
  <span m="1655150">Question?</span></p><p><span m="1655530">STUDENT:</span> <span
  m="1656022">[INAUDIBLE]</span> <span m="1656514">questions.</span> <span m="1657498">[INAUDIBLE]</span>
  <span m="1663402">Why didn''t</span> <span m="1663894">we</span> <span m="1664386">see
  the</span> <span m="1664878">[INAUDIBLE]?</span></p><p><span m="1676690">QIQI WANG:
  Right.</span> <span m="1676970">So</span> <span m="1677490">we</span> <span m="1678930">did</span>
  <span m="1679090">a</span> <span m="1679150">comparison</span> <span m="1679850">between--</span>
  <span m="1681080">actually,</span> <span m="1681430">let</span> <span m="1681570">me</span>
  <span m="1681680">ask you</span> <span m="1681910">a</span> <span m="1682040">question</span>
  <span m="1682420">about it</span> <span m="1682750">first.</span> <span m="1683310">So
  the</span> <span m="1683400">question</span> <span m="1683680">is</span> <span m="1683880">on</span>
  <span m="1684020">backward</span> <span m="1684486">difference,</span> <span m="1684952">what''s</span>
  <span m="1685418">the</span> <span m="1685884">central</span> <span m="1686350">difference?</span>
  <span m="1686490">So what</span> <span m="1686730">do</span> <span m="1686800">we</span>
  <span m="1686900">need</span> <span m="1687080">to</span> <span m="1687210">change</span>
  <span m="1687680">here</span> <span m="1688100">to</span> <span m="1688240">make</span>
  <span m="1688530">it</span> <span m="1688650">backward</span> <span m="1689150">difference?</span></p><p><span
  m="1694148">STUDENT:</span> <span m="1694646">The</span> <span m="1695144">ability</span>
  <span m="1695642">of</span> <span m="1696140">[INAUDIBLE]</span></p><p><span m="1699860">QIQI
  WANG: First</span> <span m="1700150">of</span> <span m="1700330">all,</span> <span
  m="1700960">it</span> <span m="1701240">just</span> <span m="1701460">needs</span>
  <span m="1701760">to</span> <span m="1701890">be</span> <span m="1702030">delta</span>
  <span m="1702270">x</span> <span m="1702750">not</span> <span m="1702980">2</span>
  <span m="1703170">delta</span> <span m="1703300">x.</span> <span m="1705670">And</span>
  <span m="1706450">instead</span> <span m="1706920">of</span> <span m="1707290">ui</span>
  <span m="1707630">plus</span> <span m="1707790">1</span> <span m="1708200">minus</span>
  <span m="1709000">ui</span> <span m="1709280">minus</span> <span m="1709390">1,</span>
  <span m="1710360">we</span> <span m="1710550">have</span> <span m="1710910">u</span>
  <span m="1711840">minus</span> <span m="1711990">ui</span> <span m="1712230">minus</span>
  <span m="1712630">1.</span> <span m="1713260">So</span> <span m="1713400">we''re</span>
  <span m="1713610">just</span> <span m="1713780">going</span> <span m="1713900">to</span>
  <span m="1713970">be</span> <span m="1714310">putting</span> <span m="1714600">u</span>
  <span m="1715013">here.</span> <span m="1715840">This</span> <span m="1716100">is</span>
  <span m="1716230">going</span> <span m="1716370">to</span> <span m="1716440">be</span>
  <span m="1716990">backward</span> <span m="1717320">difference.</span> <span m="1718420">And</span>
  <span m="1718640">when</span> <span m="1718820">you</span> <span m="1718990">run</span>
  <span m="1719230">backward</span> <span m="1719570">difference--</span> <span m="1720882">whoa.</span>
  <span m="1722310">Yeah,</span> <span m="1722786">we</span> <span m="1723262">get</span>
  <span m="1723738">a</span> <span m="1724214">similar</span> <span m="1724690">solution,</span>
  <span m="1725240">but</span> <span m="1725450">now</span> <span m="1727910">what
  does</span> <span m="1728310">the</span> <span m="1728410">solution</span> <span
  m="1728970">do?</span> <span m="1729190">Instead</span> <span m="1729650">of</span>
  <span m="1729950">growing</span> <span m="1731160">a</span> <span m="1731270">little</span>
  <span m="1731580">bit,</span> <span m="1732824">it</span> <span m="1733818">decays</span>
  <span m="1734315">a</span> <span m="1734812">little</span> <span m="1735309">bit.</span>
  <span m="1738800">And</span> <span m="1739060">we</span> <span m="1739410">see</span>
  <span m="1739560">we</span> <span m="1739780">have</span> <span m="1740120">the</span>
  <span m="1740200">same</span> <span m="1740620">number</span> <span m="1740850">of</span>
  <span m="1741020">grid</span> <span m="1741476">points.</span> <span m="1742390">That''s</span>
  <span m="1742680">where</span> <span m="1743167">the</span> <span m="1743654">difference</span>
  <span m="1744141">seems</span> <span m="1744628">to</span> <span m="1745115">have</span>
  <span m="1745602">more</span> <span m="1746089">undershoot</span> <span m="1746576">than</span>
  <span m="1747550">overshoot</span> <span m="1748037">of</span> <span m="1748524">the</span>
  <span m="1749011">backward</span> <span m="1749498">difference.</span> <span m="1750959">And</span>
  <span m="1751446">again,</span> <span m="1751933">Professor</span> <span m="1752420">Wilcox</span>
  <span m="1753590">is</span> <span m="1753980">going</span> <span m="1754140">to</span>
  <span m="1754260">discuss</span> <span m="1754730">the</span> <span m="1754980">accuracy</span>
  <span m="1755570">of</span> <span m="1755680">these</span> <span m="1755890">two</span>
  <span m="1756260">methods</span> <span m="1758435">on</span> <span m="1758870">Wednesday.</span></p><p><span
  m="1764420">So</span> <span m="1764650">this</span> <span m="1765810">is</span>
  <span m="1765960">the</span> <span m="1766050">implementation</span> <span m="1766900">of</span>
  <span m="1767620">the</span> <span m="1769810">central in</span> <span m="1770210">space</span>
  <span m="1770780">and</span> <span m="1771110">backwards</span> <span m="1771470">in</span>
  <span m="1771670">space</span> <span m="1772900">finite</span> <span m="1773150">difference</span>
  <span m="1773470">scheme.</span> <span m="1774820">And</span> <span m="1776790">we</span>
  <span m="1777010">also</span> <span m="1777310">discussed</span> <span m="1777430">in</span>
  <span m="1778110">the</span> <span m="1778390">last</span> <span m="1778730">lecture</span>
  <span m="1780810">how</span> <span m="1781060">to</span> <span m="1781290">solve--</span>
  <span m="1782630">what</span> <span m="1782940">is</span> <span m="1783080">the</span>
  <span m="1783170">behavior</span> <span m="1783970">of</span> <span m="1784910">a</span>
  <span m="1785080">diffusion</span> <span m="1785570">equation</span> <span m="1786310">when</span>
  <span m="1786550">we</span> <span m="1786720">have</span> <span m="1787390">diffusion</span>
  <span m="1787510">instead</span> <span m="1787950">of</span> <span m="1788070">advection.</span>
  <span m="1789760">We</span> <span m="1790000">have</span> <span m="1791050">a</span>
  <span m="1791190">differential</span> <span m="1791770">equation</span> <span m="1792220">that</span>
  <span m="1792370">is</span> <span m="1792540">like</span> <span m="1792780">this,</span>
  <span m="1793070">partial U</span> <span m="1793522">partial t</span> <span m="1794426">is</span>
  <span m="1794880">equal</span> <span m="1795270">to</span> <span m="1795390">k</span>
  <span m="1795720">times</span> <span m="1796050">partial</span> <span m="1796470">squared</span>
  <span m="1796725">u</span> <span m="1796980">partial</span> <span m="1797300">x</span>
  <span m="1797660">squared.</span></p><p><span m="1802740">And</span> <span m="1802900">we</span>
  <span m="1803020">can</span> <span m="1803160">even</span> <span m="1803500">have</span>
  <span m="1803770">a</span> <span m="1803890">mixed</span> <span m="1805970">differential</span>
  <span m="1806350">equation.</span> <span m="1806770">We</span> <span m="1807250">can</span>
  <span m="1807370">have</span> <span m="1807530">a</span> <span m="1807610">mix,</span>
  <span m="1808050">advection</span> <span m="1809130">and</span> <span m="1809410">diffusion.</span>
  <span m="1812360">So</span> <span m="1812550">how</span> <span m="1812750">do</span>
  <span m="1812810">we</span> <span m="1813940">approximate</span> <span m="1814940">this</span>
  <span m="1815300">term?</span> <span m="1815480">How</span> <span m="1815630">do</span>
  <span m="1815710">we</span> <span m="1815820">approximate</span> <span m="1816480">the</span>
  <span m="1816550">second</span> <span m="1816920">order</span> <span m="1817080">derivative?</span>
  <span m="1822520">Now</span> <span m="1822770">the</span> <span m="1822840">second</span>
  <span m="1823230">order</span> <span m="1823520">derivative</span> <span m="1824170">has</span>
  <span m="1825270">a</span> <span m="1826200">very</span> <span m="1826940">concise</span>
  <span m="1827910">approximation.</span> <span m="1828700">So</span> <span m="1828860">the</span>
  <span m="1828980">second</span> <span m="1829360">derivative</span> <span m="1829890">of</span>
  <span m="1830140">x</span> <span m="1831260">at</span> <span m="1831480">a</span>
  <span m="1831550">particular</span> <span m="1832110">grid</span> <span m="1832400">point</span>
  <span m="1832930">at</span> <span m="1833340">a</span> <span m="1833550">timestamp</span>
  <span m="1835170">can</span> <span m="1835410">be</span> <span m="1835520">approximated</span>
  <span m="1837510">as</span> <span m="1837760">this--</span> <span m="1839010">as</span>
  <span m="1839285">u</span> <span m="1839560">of</span> <span m="1840210">i</span>
  <span m="1840520">plus</span> <span m="1840850">1n</span> <span m="1841980">minus</span>
  <span m="1842610">2</span> <span m="1842885">Ui</span> <span m="1843160">n</span>
  <span m="1844268">plus</span> <span m="1844716">U</span> <span m="1845164">of</span>
  <span m="1845612">i-1</span> <span m="1846060">n.</span> <span m="1850760">Divided</span>
  <span m="1851270">by</span> <span m="1852390">delta</span> <span m="1852610">x</span>
  <span m="1854210">squared.</span></p><p><span m="1862060">Unlike</span> <span m="1863610">the</span>
  <span m="1863690">first</span> <span m="1864000">order</span> <span m="1864200">derivative,</span>
  <span m="1864850">you</span> <span m="1864960">have</span> <span m="1865220">the</span>
  <span m="1865310">choice</span> <span m="1865770">of</span> <span m="1867160">forward</span>
  <span m="1867710">and</span> <span m="1867920">backward</span> <span m="1868790">difference.</span>
  <span m="1870710">For</span> <span m="1871120">approximating</span> <span m="1871940">second</span>
  <span m="1872140">order</span> <span m="1872450">derivatives,</span> <span m="1873160">this</span>
  <span m="1873340">is</span> <span m="1873720">the</span> <span m="1873830">single</span>
  <span m="1874250">most</span> <span m="1875040">popular</span> <span m="1876040">scheme</span>
  <span m="1876630">we</span> <span m="1876830">use.</span> <span m="1877690">And</span>
  <span m="1878030">it</span> <span m="1878180">is</span> <span m="1878330">very</span>
  <span m="1878570">difficult</span> <span m="1878940">to</span> <span m="1879020">find</span>
  <span m="1879580">an</span> <span m="1881180">approximation</span> <span m="1881980">that</span>
  <span m="1883940">is</span> <span m="1884210">as</span> <span m="1884675">popular</span>
  <span m="1885140">as</span> <span m="1885490">this.</span> <span m="1885840">And</span>
  <span m="1885920">let</span> <span m="1886100">me</span> <span m="1886370">describe</span>
  <span m="1886790">to</span> <span m="1886900">you</span> <span m="1887010">why</span>
  <span m="1887420">this</span> <span m="1887630">is</span> <span m="1887790">the</span>
  <span m="1887890">case.</span> <span m="1888960">OK</span> <span m="1889430">We</span>
  <span m="1889620">are</span> <span m="1889750">approximating</span> <span m="1890500">the</span>
  <span m="1890580">second</span> <span m="1890960">order</span> <span m="1891240">derivative.</span>
  <span m="1893170">We</span> <span m="1893380">are</span> <span m="1893490">only</span>
  <span m="1893760">using</span> <span m="1894100">three</span> <span m="1894360">points,</span>
  <span m="1896900">the</span> <span m="1897030">center,</span> <span m="1897610">left,</span>
  <span m="1897920">and</span> <span m="1898090">right.</span> <span m="1899210">And</span>
  <span m="1899540">amazingly,</span> <span m="1900290">this</span> <span m="1900580">thing</span>
  <span m="1900880">has</span> <span m="1902240">second</span> <span m="1902650">order</span>
  <span m="1902970">accuracy,</span> <span m="1903560">has</span> <span m="1903770">very</span>
  <span m="1904110">good</span> <span m="1904420">accuracy.</span></p><p><span m="1908730">And</span>
  <span m="1908910">you</span> <span m="1909000">can</span> <span m="1909210">show</span>
  <span m="1909390">that</span> <span m="1909590">by</span> <span m="1909760">doing</span>
  <span m="1910060">Taylor</span> <span m="1910360">Series</span> <span m="1910710">on
  that--</span> <span m="1911030">it''s</span> <span m="1911710">U</span> <span m="1911940">of</span>
  <span m="1912190">i plus 1</span> <span m="1912440">n</span> <span m="1914270">can</span>
  <span m="1914510">be</span> <span m="1914680">expanded</span> <span m="1915000">as</span>
  <span m="1915320">U</span> <span m="1915730">of</span> <span m="1916160">i</span>
  <span m="1916590">n</span> <span m="1917480">plus</span> <span m="1917910">delta</span>
  <span m="1918050">x</span> <span m="1920420">times,</span> <span m="1921930">in</span>
  <span m="1922120">this</span> <span m="1922310">case,</span> <span m="1922620">the</span>
  <span m="1922710">partial</span> <span m="1923110">derivative</span> <span m="1923970">of</span>
  <span m="1924250">partial</span> <span m="1924520">U</span> <span m="1924580">partial</span>
  <span m="1924950">x</span> <span m="1925100">at</span> <span m="1925260">i</span>
  <span m="1925750">n,</span> <span m="1927710">plus</span> <span m="1928690">half</span>
  <span m="1929010">of</span> <span m="1929170">delta</span> <span m="1929380">x</span>
  <span m="1929730">squared</span> <span m="1930350">of</span> <span m="1931080">the</span>
  <span m="1931210">second</span> <span m="1931660">derivative</span> <span m="1932300">of</span>
  <span m="1932870">U</span> <span m="1934046">at</span> <span m="1935010">i</span>
  <span m="1935070">n.</span> <span m="1937710">I''m</span> <span m="1937880">going</span>
  <span m="1938020">to</span> <span m="1938100">be</span> <span m="1938200">expanding</span>
  <span m="1938750">more</span> <span m="1939010">terms.</span> <span m="1941050">It''s</span>
  <span m="1941430">the</span> <span m="1941560">third</span> <span m="1942010">of
  the</span> <span m="1942120">derivative</span> <span m="1942810">times</span> <span
  m="1944610">delta</span> <span m="1944830">x</span> <span m="1945120">cubed</span>
  <span m="1945950">divided</span> <span m="1946370">by</span> <span m="1946560">6.</span>
  <span m="1949610">And</span> <span m="1950410">I''m</span> <span m="1950620">just</span>
  <span m="1950840">going to</span> <span m="1951050">write</span> <span m="1951600">over</span>
  <span m="1951900">here</span> <span m="1952760">O</span> <span m="1953025">delta</span>
  <span m="1953290">x</span> <span m="1954760">to</span> <span m="1954900">the</span>
  <span m="1954980">4th.</span> <span m="1956930">Now</span> <span m="1957400">this</span>
  <span m="1958555">this</span> <span m="1958940">term.</span> <span m="1960060">I</span>
  <span m="1960230">am</span> <span m="1960340">also</span> <span m="1960680">going</span>
  <span m="1960820">to</span> <span m="1960900">be</span> <span m="1961010">expanding</span>
  <span m="1961660">this</span> <span m="1962053">term.</span> <span m="1962840">Ui-1</span>
  <span m="1964400">of</span> <span m="1964862">n</span> <span m="1965324">is</span>
  <span m="1965786">equal to</span> <span m="1966248">Ui</span> <span m="1966710">n.</span>
  <span m="1967640">In</span> <span m="1967800">this</span> <span m="1967970">case,</span>
  <span m="1968300">it''s</span> <span m="1968530">minus</span> <span m="1968900">delta</span>
  <span m="1969150">x</span> <span m="1969500">because</span> <span m="1969860">the</span>
  <span m="1969930">difference</span> <span m="1970310">between</span> <span m="1970630">the</span>
  <span m="1970900">i-1th</span> <span m="1971690">grid</span> <span m="1971940">point</span>
  <span m="1972210">and</span> <span m="1972470">the</span> <span m="1972720">i-th</span>
  <span m="1972960">grid point</span> <span m="1973520">is</span> <span m="1973830">minus</span>
  <span m="1974100">delta</span> <span m="1974370">x.</span></p><p><span m="1977930">The</span>
  <span m="1978080">second</span> <span m="1978510">derivative</span> <span m="1980240">term</span>
  <span m="1980480">is</span> <span m="1980740">plus</span> <span m="1981040">again,</span>
  <span m="1981380">because</span> <span m="1981740">we</span> <span m="1981880">are</span>
  <span m="1981990">taking</span> <span m="1982320">the</span> <span m="1982410">square</span>
  <span m="1982830">of</span> <span m="1983020">minus</span> <span m="1983480">delta</span>
  <span m="1983620">x.</span> <span m="1988290">The</span> <span m="1988410">third</span>
  <span m="1988700">derivative</span> <span m="1989230">is</span> <span m="1989390">minus</span>
  <span m="1989770">again,</span> <span m="1990250">because</span> <span m="1990590">we</span>
  <span m="1990700">are</span> <span m="1991010">taking</span> <span m="1991110">the</span>
  <span m="1991270">cube</span> <span m="1992881">of</span> <span m="1993410">delta</span>
  <span m="1993590">x.</span> <span m="1996870">And</span> <span m="1997150">again,</span>
  <span m="1997530">we</span> <span m="1997750">have</span> <span m="1998030">plus</span>
  <span m="1998410">delta</span> <span m="1998790">x to</span> <span m="1999170">the</span>
  <span m="1999450">4th.</span> <span m="2006260">Now</span> <span m="2006570">we</span>
  <span m="2006700">can</span> <span m="2006910">start</span> <span m="2007170">to</span>
  <span m="2007270">see</span> <span m="2007580">which</span> <span m="2008060">terms</span>
  <span m="2008375">start</span> <span m="2008690">to</span> <span m="2008800">cancel</span>
  <span m="2009250">out.</span> <span m="2012850">See</span> <span m="2013070">we</span>
  <span m="2013390">have</span> <span m="2013930">one</span> <span m="2014430">of</span>
  <span m="2014880">Ui</span> <span m="2015180">n</span> <span m="2015620">here</span>
  <span m="2016690">plus</span> <span m="2017160">another</span> <span m="2017590">Ui</span>
  <span m="2017810">n</span> <span m="2018160">here.</span> <span m="2018670">Now</span>
  <span m="2019050">we</span> <span m="2019210">have</span> <span m="2019450">minus</span>
  <span m="2019720">2</span> <span m="2020360">of</span> <span m="2020420">Uin.</span>
  <span m="2021580">So</span> <span m="2021800">this</span> <span m="2023220">and</span>
  <span m="2023530">these</span> <span m="2024060">cancel</span> <span m="2024610">together,</span>
  <span m="2025070">cancels</span> <span m="2025570">with</span> <span m="2025830">this</span>
  <span m="2025920">minus</span> <span m="2026407">2Uin.</span> <span m="2030790">All
  right,</span> <span m="2031110">this</span> <span m="2031270">is</span> <span m="2031390">one</span>
  <span m="2031720">term.</span></p><p><span m="2037570">This</span> <span m="2038010">and</span>
  <span m="2038210">this</span> <span m="2038480">is</span> <span m="2038680">added</span>
  <span m="2039000">up.</span> <span m="2039280">So</span> <span m="2039480">i plus
  1</span> <span m="2039590">i minus</span> <span m="2040090">1</span> <span m="2040520">is</span>
  <span m="2040720">added</span> <span m="2040820">up.</span> <span m="2041570">So</span>
  <span m="2041740">the</span> <span m="2041930">first</span> <span m="2042190">derivative</span>
  <span m="2042485">term</span> <span m="2042780">cancels.</span> <span m="2046990">The</span>
  <span m="2047160">third</span> <span m="2047540">derivative</span> <span m="2048100">term,</span>
  <span m="2048530">instead</span> <span m="2048920">of</span> <span m="2049060">canceling,</span>
  <span m="2049630">they</span> <span m="2049840">add</span> <span m="2050070">up.</span>
  <span m="2050894">So</span> <span m="2051380">they,</span> <span m="2052409">divided</span>
  <span m="2052909">by</span> <span m="2053184">delta</span> <span m="2053460">x</span>
  <span m="2053929">squared,</span> <span m="2054699">serves</span> <span m="2055060">as</span>
  <span m="2055330">an</span> <span m="2055460">approximation</span> <span m="2056409">of</span>
  <span m="2056659">partial squared</span> <span m="2057030">U</span> <span m="2057239">partial</span>
  <span m="2057510">x</span> <span m="2057630">squared.</span> <span m="2059290">It</span>
  <span m="2059429">is</span> <span m="2059570">a</span> <span m="2059630">consistent</span>
  <span m="2060260">approximation</span> <span m="2061440">for</span> <span m="2061600">partial</span>
  <span m="2062084">squared U</span> <span m="2062568">partial x.</span> <span m="2064989">And</span>
  <span m="2065170">usually,</span> <span m="2065580">when</span> <span m="2065770">you</span>
  <span m="2065909">have</span> <span m="2066150">three</span> <span m="2066489">terms--</span>
  <span m="2066860">when</span> <span m="2067130">you</span> <span m="2067310">are</span>
  <span m="2067409">playing</span> <span m="2067860">around</span> <span m="2068679">the</span>
  <span m="2068830">coefficient</span> <span m="2069389">of</span> <span m="2069620">three</span>
  <span m="2070550">neighbors,</span> <span m="2071800">you</span> <span m="2071980">can</span>
  <span m="2075810">make</span> <span m="2076020">sure</span> <span m="2076280">three</span>
  <span m="2076730">terms</span> <span m="2078440">add</span> <span m="2078670">up</span>
  <span m="2078870">to</span> <span m="2079020">what</span> <span m="2080210">you</span>
  <span m="2080280">want</span> <span m="2080480">it to</span> <span m="2080570">be.</span>
  <span m="2081810">You''ve</span> <span m="2082139">got rid of</span> <span m="2082409">the
  constant</span> <span m="2082679">terms.</span> <span m="2082810">You''ve</span>
  <span m="2082949">got</span> <span m="2083170">rid of</span> <span m="2083280">the</span>
  <span m="2083370">first</span> <span m="2083670">order</span> <span m="2083900">derivative</span>
  <span m="2084170">terms.</span> <span m="2084940">You</span> <span m="2085080">make</span>
  <span m="2085350">sure</span> <span m="2085550">that</span> <span m="2085929">the</span>
  <span m="2086090">second</span> <span m="2086469">order</span> <span m="2086659">derivative</span>
  <span m="2087110">turns</span> <span m="2087744">out</span> <span m="2088100">to</span>
  <span m="2088210">be</span> <span m="2088310">what</span> <span m="2088560">you</span>
  <span m="2088630">want</span> <span m="2088860">to</span> <span m="2088929">approximate.</span>
  <span m="2090230">But</span> <span m="2090389">in</span> <span m="2090530">this</span>
  <span m="2090730">case,</span> <span m="2091170">you</span> <span m="2091310">get</span>
  <span m="2091620">a</span> <span m="2091659">bonus.</span> <span m="2093380">The
  third</span> <span m="2093860">order</span> <span m="2094130">derivative</span>
  <span m="2094710">term</span> <span m="2095139">cancels</span> <span m="2095599">out
  too,</span> <span m="2096980">just</span> <span m="2097330">by</span> <span m="2097500">accident,</span>
  <span m="2098890">and</span> <span m="2099120">now,</span> <span m="2099570">you</span>
  <span m="2099790">only</span> <span m="2100050">get</span> <span m="2100410">a</span>
  <span m="2100540">delta x</span> <span m="2100740">to</span> <span m="2100860">the</span>
  <span m="2101280">4th,</span> <span m="2101940">which</span> <span m="2102200">after</span>
  <span m="2102480">dividing</span> <span m="2102980">by</span> <span m="2103200">delta
  x</span> <span m="2103350">squared,</span> <span m="2104500">you</span> <span m="2104850">get</span>
  <span m="2105010">a second-order</span> <span m="2105810">accurate</span> <span
  m="2106580">approximation</span> <span m="2108380">to</span> <span m="2108470">the</span>
  <span m="2108570">second</span> <span m="2109010">derivative.</span></p><p><span
  m="2114840">So</span> <span m="2114970">the</span> <span m="2115100">error,</span>
  <span m="2116050">which</span> <span m="2116330">is</span> <span m="2117190">the</span>
  <span m="2117450">actual</span> <span m="2118080">second</span> <span m="2118480">order</span>
  <span m="2118790">derivative</span> <span m="2119560">minus</span> <span m="2120930">the</span>
  <span m="2121050">finite</span> <span m="2121500">difference</span> <span m="2122120">approximation</span>
  <span m="2128690">goes</span> <span m="2129190">like</span> <span m="2130030">O</span>
  <span m="2130680">delta</span> <span m="2131010">x</span> <span m="2131980">squared.</span>
  <span m="2133550">And</span> <span m="2133750">this</span> <span m="2133930">is</span>
  <span m="2134980">pure</span> <span m="2136550">luckiness.</span> <span m="2140680">Any</span>
  <span m="2140860">questions</span> <span m="2141280">on</span> <span m="2141410">this?</span>
  <span m="2143100">This</span> <span m="2143320">scheme</span> <span m="2143530">is</span>
  <span m="2143978">what</span> <span m="2145770">we</span> <span m="2146750">are</span>
  <span m="2146950">going</span> <span m="2147120">to</span> <span m="2147200">be</span>
  <span m="2147370">using.</span></p><p><span m="2157090">Now</span> <span m="2157310">let''s</span>
  <span m="2158100">go</span> <span m="2158350">back</span> <span m="2158920">and</span>
  <span m="2159410">modify</span> <span m="2160200">our</span> <span m="2160470">code</span>
  <span m="2161315">to</span> <span m="2161660">also</span> <span m="2162240">do</span>
  <span m="2162360">second</span> <span m="2162720">order</span> <span m="2163010">derivatives.</span>
  <span m="2165020">So</span> <span m="2165200">we</span> <span m="2165440">have</span>
  <span m="2165840">du dx.</span> <span m="2167430">We</span> <span m="2167580">have</span>
  <span m="2167760">d2udx2</span> <span m="2171190">equal</span> <span m="2171580">to--</span>
  <span m="2171730">let</span> <span m="2171980">me</span> <span m="2172260">copy
  this.</span> <span m="2173810">And</span> <span m="2174920">we</span> <span m="2175100">have</span>
  <span m="2175370">a</span> <span m="2175410">Ui</span> <span m="2175760">plus</span>
  <span m="2176150">1,</span> <span m="2176870">which</span> <span m="2177160">is</span>
  <span m="2177390">circshift</span> <span m="2178530">of</span> <span m="2178770">U</span>
  <span m="2179680">towards</span> <span m="2179920">or</span> <span m="2180020">the</span>
  <span m="2180160">minus</span> <span m="2180550">direction.</span> <span m="2182330">We</span>
  <span m="2182510">minus</span> <span m="2183100">2</span> <span m="2183430">times</span>
  <span m="2183710">u</span> <span m="2184370">and</span> <span m="2184780">plus</span>
  <span m="2187960">u</span> <span m="2188230">of</span> <span m="2188580">i</span>
  <span m="2188760">minus</span> <span m="2189060">1.</span> <span m="2190500">And</span>
  <span m="2191040">divide it</span> <span m="2191520">by</span> <span m="2191880">delta</span>
  <span m="2192150">x</span> <span m="2192420">squared.</span> <span m="2194190">So</span>
  <span m="2194360">this</span> <span m="2194590">is</span> <span m="2194780">our</span>
  <span m="2195020">second</span> <span m="2195440">order</span> <span m="2195850">derivative.</span></p><p><span
  m="2198160">If</span> <span m="2198380">we</span> <span m="2198500">want</span>
  <span m="2198700">to</span> <span m="2198830">solve</span> <span m="2199690">the</span>
  <span m="2200050">diffusion</span> <span m="2200490">equation</span> <span m="2200830">over</span>
  <span m="2201040">here,</span> <span m="2202220">the</span> <span m="2202370">du
  dt</span> <span m="2203260">would</span> <span m="2203480">instead</span> <span
  m="2203860">of</span> <span m="2204080">being</span> <span m="2204300">minus</span>
  <span m="2204570">du</span> <span m="2204720">dx</span> <span m="2205370">we</span>
  <span m="2205580">have</span> <span m="2205820">the</span> <span m="2206970">positive</span>
  <span m="2207470">of</span> <span m="2207830">d2udx2.</span> <span m="2211670">And</span>
  <span m="2211790">let''s</span> <span m="2212040">put</span> <span m="2212310">a</span>
  <span m="2212750">cover</span> <span m="2213035">here,</span> <span m="2214886">a</span>
  <span m="2215340">0.1</span> <span m="2215800">cover</span> <span m="2216095">so
  that</span> <span m="2216390">it</span> <span m="2216480">diffuses</span> <span
  m="2216940">slower.</span> <span m="2218380">And then</span> <span m="2218770">let''s</span>
  <span m="2219090">look at</span> <span m="2219410">how</span> <span m="2220510">the</span>
  <span m="2220600">numerical</span> <span m="2221050">solution</span> <span m="2221510">looks</span>
  <span m="2221880">like.</span> <span m="2222450">Let''s</span> <span m="2222720">change</span>
  <span m="2223010">back</span> <span m="2223240">to 100.</span> <span m="2228060">Oops.</span>
  <span m="2229615">Again,</span> <span m="2230060">if</span> <span m="2230950">the</span>
  <span m="2231580">stability</span> <span m="2231950">is coming</span> <span m="2232360">up,</span>
  <span m="2232860">let</span> <span m="2233860">me</span> <span m="2233950">make</span>
  <span m="2234250">sure</span> <span m="2234510">we</span> <span m="2234660">have</span>
  <span m="2234910">a</span> <span m="2235240">small</span> <span m="2235480">enough</span>
  <span m="2235610">timestamp.</span></p><p><span m="2239560">So</span> <span m="2240060">we</span>
  <span m="2240190">can</span> <span m="2240370">see</span> <span m="2240710">are</span>
  <span m="2240950">the</span> <span m="2241030">solution</span> <span m="2241550">of</span>
  <span m="2241740">this</span> <span m="2242540">PDE</span> <span m="2245450">agrees</span>
  <span m="2245890">with</span> <span m="2246170">the</span> <span m="2246290">analytical</span>
  <span m="2246960">behavior</span> <span m="2247490">of</span> <span m="2247945">the</span>
  <span m="2248400">PDE,</span> <span m="2249310">which</span> <span m="2249600">is</span>
  <span m="2249860">the</span> <span m="2250040">solution</span> <span m="2250500">diffuses</span>
  <span m="2251280">out.</span> <span m="2251620">It</span> <span m="2252074">becomes</span>
  <span m="2252528">less</span> <span m="2252982">sharp.</span> <span m="2254800">And</span>
  <span m="2255140">we</span> <span m="2255250">can</span> <span m="2255420">even</span>
  <span m="2255710">combine</span> <span m="2256250">these</span> <span m="2256450">two</span>
  <span m="2256710">terms.</span> <span m="2256970">We</span> <span m="2257130">can</span>
  <span m="2258250">du dx</span> <span m="2259110">plus</span> <span m="2259540">this,</span>
  <span m="2260790">or</span> <span m="2261140">we</span> <span m="2261270">can</span>
  <span m="2261480">do</span> <span m="2261660">a</span> <span m="2262080">convection</span>
  <span m="2262500">diffusion</span> <span m="2262770">equation.</span> <span m="2266510">And</span>
  <span m="2267650">we</span> <span m="2267790">can</span> <span m="2268000">see</span>
  <span m="2268290">the</span> <span m="2268400">solution</span> <span m="2269320">diffuses</span>
  <span m="2270216">and</span> <span m="2271330">also,</span> <span m="2273150">in</span>
  <span m="2273320">this</span> <span m="2273500">case,</span> <span m="2273800">it''s</span>
  <span m="2273980">shifting</span> <span m="2274390">towards</span> <span m="2274720">the</span>
  <span m="2274800">left,</span> <span m="2275570">because</span> <span m="2277130">I</span>
  <span m="2277180">think</span> <span m="2277430">that</span> <span m="2277590">the</span>
  <span m="2277690">right</span> <span m="2277950">convection-diffusion</span> <span
  m="2278750">equation</span> <span m="2279060">should</span> <span m="2279240">be</span>
  <span m="2279420">minus</span> <span m="2279920">du</span> <span m="2280420">dx.</span>
  <span m="2281920">Let</span> <span m="2282420">me</span> <span m="2282920">make</span>
  <span m="2283420">sure that</span> <span m="2283920">is the</span> <span m="2284420">case.</span></p><p><span
  m="2284640">So</span> <span m="2285250">we</span> <span m="2285400">have</span>
  <span m="2285630">a</span> <span m="2285720">solution</span> <span m="2286150">that</span>
  <span m="2286300">is</span> <span m="2286450">diffusion</span> <span m="2287930">by</span>
  <span m="2288130">the</span> <span m="2288230">diffusion</span> <span m="2288690">terms,</span>
  <span m="2289300">and</span> <span m="2289480">also</span> <span m="2289800">advects</span>
  <span m="2290230">toward</span> <span m="2290510">light</span> <span m="2291320">by</span>
  <span m="2291770">this</span> <span m="2292670">advection.</span> <span m="2304290">Now</span>
  <span m="2304480">let''s</span> <span m="2304750">take</span> <span m="2304960">just</span>
  <span m="2305300">a</span> <span m="2305550">5</span> <span m="2305780">minute</span>
  <span m="2306040">break</span> <span m="2306640">before</span> <span m="2307010">we</span>
  <span m="2307900">go</span> <span m="2308130">to</span> <span m="2308340">the</span>
  <span m="2308820">matrix</span> <span m="2309430">form.</span> <span m="2310240">We
  did find</span> <span m="2310640">a</span> <span m="2311105">difference</span> <span
  m="2311570">[INAUDIBLE].</span> <span m="2312830">Before</span> <span m="2313080">we</span>
  <span m="2313180">go</span> <span m="2313370">into</span> <span m="2313520">the</span>
  <span m="2313620">matrix</span> <span m="2314070">form</span> <span m="2314530">of</span>
  <span m="2314720">this</span> <span m="2314970">finite</span> <span m="2315350">difference</span>
  <span m="2315730">method--</span> <span m="2316490">and</span> <span m="2316680">we</span>
  <span m="2317450">see</span> <span m="2317600">the</span> <span m="2317650">matrix</span>
  <span m="2318000">form</span> <span m="2318240">is</span> <span m="2318735">going
  to</span> <span m="2319230">come up a</span> <span m="2319320">lot,</span> <span
  m="2319600">and</span> <span m="2319660">it''s</span> <span m="2320110">going to
  be</span> <span m="2321010">very</span> <span m="2321230">useful</span> <span m="2321505">in,</span>
  <span m="2322197">for</span> <span m="2322614">example,</span> <span m="2323450">in
  physics</span> <span m="2323950">scemes</span> <span m="2324450">of</span> <span
  m="2325950">finite</span> <span m="2326450">difference</span> <span m="2326950">methods.</span>
  <span m="2328450">All right.</span> <span m="2328700">OK.</span> <span m="2329060">Let''s</span>
  <span m="2329260">continue.</span> <span m="2330750">So the</span> <span m="2331060">really</span>
  <span m="2331360">[INAUDIBLE]</span> <span m="2332720">like</span> <span m="2334180">you</span>
  <span m="2334620">haven''t</span> <span m="2335260">seen</span> <span m="2335510">before.</span></p><p><span
  m="2337390">There</span> <span m="2337570">is,</span> <span m="2338874">as</span>
  <span m="2339311">I</span> <span m="2339750">said,</span> <span m="2340150">unlike</span>
  <span m="2341300">discretization</span> <span m="2342120">in</span> <span m="2342220">time,</span>
  <span m="2342510">you</span> <span m="2342690">only</span> <span m="2343010">have</span>
  <span m="2343840">one</span> <span m="2344220">stamp</span> <span m="2344560">of</span>
  <span m="2344700">information,</span> <span m="2345300">right?</span> <span m="2345530">You</span>
  <span m="2345660">can</span> <span m="2345850">only</span> <span m="2346190">view</span>
  <span m="2347250">things</span> <span m="2347540">one</span> <span m="2347770">step</span>
  <span m="2348050">at</span> <span m="2348170">a</span> <span m="2348330">time.</span>
  <span m="2348640">You</span> <span m="2348810">don''t</span> <span m="2349300">really</span>
  <span m="2349790">know</span> <span m="2350020">what</span> <span m="2350250">happens</span>
  <span m="2350890">tomorrow,</span> <span m="2351450">what</span> <span m="2351660">happens</span>
  <span m="2352100">at</span> <span m="2352180">the</span> <span m="2352290">next</span>
  <span m="2352600">timestamp.</span> <span m="2353225">So</span> <span m="2353650">you</span>
  <span m="2353760">have</span> <span m="2353920">to</span> <span m="2354020">go</span>
  <span m="2354270">one</span> <span m="2354480">step</span> <span m="2354730">at</span>
  <span m="2354860">a time.</span></p><p><span m="2356640">We</span> <span m="2356890">find</span>
  <span m="2357100">a</span> <span m="2357190">difference</span> <span m="2357940">when</span>
  <span m="2358220">we</span> <span m="2358360">discretize</span> <span m="2358970">things</span>
  <span m="2359140">in</span> <span m="2359560">space</span> <span m="2360820">we</span>
  <span m="2361220">actually</span> <span m="2361840">have</span> <span m="2362200">much</span>
  <span m="2362600">more</span> <span m="2362890">data</span> <span m="2363270">than</span>
  <span m="2363550">we</span> <span m="2363720">have</span> <span m="2364060">in</span>
  <span m="2364340">ODE</span> <span m="2365730">discreditization</span> <span m="2366440">because</span>
  <span m="2366770">we</span> <span m="2366910">have</span> <span m="2367390">the
  entire</span> <span m="2367750">timestamp.</span> <span m="2368630">At</span> <span
  m="2368750">every</span> <span m="2369010">grid</span> <span m="2369250">point</span>
  <span m="2369520">we</span> <span m="2369720">have</span> <span m="2370070">the</span>
  <span m="2370160">solution</span> <span m="2371620">in</span> <span m="2371810">our</span>
  <span m="2372020">head.</span> <span m="2373520">OK.</span> <span m="2374770">That</span>
  <span m="2375090">makes</span> <span m="2375450">it</span> <span m="2375650">possible</span>
  <span m="2376360">to</span> <span m="2377880">write</span> <span m="2378400">and
  find</span> <span m="2378740">a</span> <span m="2378850">difference</span> <span
  m="2380450">in</span> <span m="2380610">a</span> <span m="2380660">matrix</span>
  <span m="2381070">form.</span></p><p><span m="2382330">OK.</span> <span m="2383030">So</span>
  <span m="2383670">when</span> <span m="2383930">we</span> <span m="2384070">write</span>
  <span m="2384510">the</span> <span m="2384630">finite</span> <span m="2384920">difference</span>
  <span m="2385380">in</span> <span m="2385470">the</span> <span m="2385550">matrix</span>
  <span m="2385960">form,</span> <span m="2386630">we</span> <span m="2386830">first</span>
  <span m="2388240">need</span> <span m="2388490">to</span> <span m="2388670">write</span>
  <span m="2389090">our</span> <span m="2389340">solution</span> <span m="2389970">in</span>
  <span m="2390150">a</span> <span m="2390200">vector</span> <span m="2390593">form.</span>
  <span m="2391380">We</span> <span m="2391440">know</span> <span m="2391850">our</span>
  <span m="2392100">solution--</span> <span m="2393600">let''s</span> <span m="2393670">say</span>
  <span m="2393790">we</span> <span m="2393940">know</span> <span m="2394300">our</span>
  <span m="2394360">solution</span> <span m="2394810">yields</span> <span m="2395600">at</span>
  <span m="2395990">the</span> <span m="2396130">first</span> <span m="2396410">grid</span>
  <span m="2396610">point,</span> <span m="2396970">u</span> <span m="2397230">at
  the</span> <span m="2397760">second</span> <span m="2398080">grid</span> <span m="2398320">point,</span>
  <span m="2398880">u</span> <span m="2399160">at</span> <span m="2399320">the</span>
  <span m="2399390">n-th</span> <span m="2399690">grid</span> <span m="2399900">point.</span>
  <span m="2400330">We</span> <span m="2400700">have</span> <span m="2400930">them</span>
  <span m="2401090">all,</span> <span m="2401790">right?</span> <span m="2404020">So</span>
  <span m="2404210">that</span> <span m="2404400">is</span> <span m="2404550">what</span>
  <span m="2404770">we</span> <span m="2404970">have.</span></p><p><span m="2407410">Can
  we</span> <span m="2408470">compute</span> <span m="2410820">not</span> <span m="2411220">d</span>
  <span m="2411490">but</span> <span m="2411740">partial--</span> <span m="2413050">partial</span>
  <span m="2413370">u</span> <span m="2413810">partial</span> <span m="2414220">x</span>
  <span m="2414570">at</span> <span m="2414690">the</span> <span m="2414820">first</span>
  <span m="2415020">grid</span> <span m="2415230">point,</span> <span m="2415950">partial</span>
  <span m="2416390">u</span> <span m="2416660">partial</span> <span m="2417010">x</span>
  <span m="2417360">at</span> <span m="2417500">the</span> <span m="2417570">second</span>
  <span m="2417930">grid</span> <span m="2418150">point?</span> <span m="2418740">Is</span>
  <span m="2418920">that</span> <span m="2419160">true</span> <span m="2419370">of
  partial u,</span> <span m="2419800">partial</span> <span m="2420620">x</span> <span
  m="2420960">at</span> <span m="2421220">the</span> <span m="2421360">last</span>
  <span m="2421720">grid</span> <span m="2422010">point?</span> <span m="2427080">As</span>
  <span m="2427557">a</span> <span m="2428040">joint</span> <span m="2428560">matrix--</span>
  <span m="2430170">I</span> <span m="2430300">said</span> <span m="2430580">joint</span>
  <span m="2430850">matrix</span> <span m="2431390">because</span> <span m="2431660">sometimes</span>
  <span m="2432510">when</span> <span m="2432740">you</span> <span m="2432950">have,</span>
  <span m="2433590">let''s</span> <span m="2433900">say,</span> <span m="2434420">a</span>
  <span m="2434530">million</span> <span m="2434910">grid</span> <span m="2435190">points,</span>
  <span m="2436240">how</span> <span m="2436430">big</span> <span m="2436720">is</span>
  <span m="2436950">the</span> <span m="2437040">matrix</span> <span m="2437460">going</span>
  <span m="2437620">to</span> <span m="2437700">be?</span> <span m="2441700">It''s</span>
  <span m="2442350">going</span> <span m="2442510">to</span> <span m="2442590">be</span>
  <span m="2442710">a</span> <span m="2442820">million</span> <span m="2443340">by</span>
  <span m="2443520">million</span> <span m="2443920">matrix,</span> <span m="2444384">right?</span>
  <span m="2448560">It''s</span> <span m="2448650">going</span> <span m="2448770">to</span>
  <span m="2448840">be</span> <span m="2448920">a</span> <span m="2448970">million</span>
  <span m="2449320">by</span> <span m="2449450">million</span> <span m="2449730">matrix.</span>
  <span m="2450210">Think of</span> <span m="2450430">n</span> <span m="2450580">as</span>
  <span m="2450790">a million.</span></p><p><span m="2452340">And</span> <span m="2452580">this</span>
  <span m="2452770">is</span> <span m="2452910">why--</span> <span m="2453520">I</span>
  <span m="2453590">don''t</span> <span m="2453760">know</span> <span m="2453880">if</span>
  <span m="2454370">some</span> <span m="2454550">of</span> <span m="2454690">you</span>
  <span m="2454840">have</span> <span m="2455690">heard</span> <span m="2455970">of</span>
  <span m="2456130">the</span> <span m="2456240">term</span> <span m="2456770">spark</span>
  <span m="2457140">matrix.</span> <span m="2458910">That</span> <span m="2459150">is</span>
  <span m="2459310">why</span> <span m="2459890">spark</span> <span m="2460210">matrices</span>
  <span m="2460485">are</span> <span m="2460880">invented</span> <span m="2461350">because</span>
  <span m="2462580">usually</span> <span m="2463120">people</span> <span m="2463430">don''t</span>
  <span m="2463660">have</span> <span m="2463970">enough</span> <span m="2464270">memory</span>
  <span m="2464680">to</span> <span m="2464820">store</span> <span m="2465530">those</span>
  <span m="2465870">million</span> <span m="2466240">by</span> <span m="2466440">million</span>
  <span m="2467010">rate.</span> <span m="2468500">I''m</span> <span m="2468640">going</span>
  <span m="2468780">to</span> <span m="2468850">talk</span> <span m="2469280">about</span>
  <span m="2469340">that</span> <span m="2469530">later.</span> <span m="2469900">But</span>
  <span m="2470860">sometimes</span> <span m="2471290">you</span> <span m="2471420">have</span>
  <span m="2471580">this</span> <span m="2471740">joint</span> <span m="2471950">matrix.</span></p><p><span
  m="2472822">Now,</span> <span m="2473540">what</span> <span m="2474050">is</span>
  <span m="2474320">this</span> <span m="2474490">joint</span> <span m="2474700">matrix?</span>
  <span m="2475790">What</span> <span m="2476160">are</span> <span m="2476270">the</span>
  <span m="2476390">elements</span> <span m="2477110">in</span> <span m="2477400">this</span>
  <span m="2477670">joint</span> <span m="2477890">matrix?</span> <span m="2478970">If</span>
  <span m="2479400">it</span> <span m="2479580">is</span> <span m="2479720">a central</span>
  <span m="2480140">difference--</span> <span m="2480610">let</span> <span m="2480800">me</span>
  <span m="2480940">write</span> <span m="2481200">down</span> <span m="2481380">the</span>
  <span m="2481460">central</span> <span m="2481770">difference</span> <span m="2482214">formula</span>
  <span m="2483102">here.</span> <span m="2483990">Let</span> <span m="2484170">me</span>
  <span m="2484280">write</span> <span m="2484570">it</span> <span m="2484650">here</span>
  <span m="2485111">so</span> <span m="2485572">that</span> <span m="2486033">it''s</span>
  <span m="2487416">down</span> <span m="2488338">here</span> <span m="2489260">now.</span>
  <span m="2491302">In</span> <span m="2491720">a</span> <span m="2491880">central</span>
  <span m="2492360">difference,</span> <span m="2492910">partial</span> <span m="2493140">u,</span>
  <span m="2494750">partial</span> <span m="2495130">x</span> <span m="2495550">at</span>
  <span m="2496170">i</span> <span m="2496670">is</span> <span m="2497050">equal</span>
  <span m="2497430">to</span> <span m="2499010">u</span> <span m="2499470">or</span>
  <span m="2499960">i plus</span> <span m="2500310">1</span> <span m="2500720">minus</span>
  <span m="2501100">Ui</span> <span m="2501600">minus</span> <span m="2502010">1</span>
  <span m="2502320">divided</span> <span m="2502730">by</span> <span m="2502930">2</span>
  <span m="2503240">delta</span> <span m="2503460">x.</span></p><p><span m="2507440">And</span>
  <span m="2507710">let''s</span> <span m="2507790">assume</span> <span m="2508180">again</span>
  <span m="2508930">we</span> <span m="2509140">have</span> <span m="2509620">here</span>
  <span m="2509900">[INAUDIBLE]</span> <span m="2510090">boundary</span> <span m="2510570">condition</span>
  <span m="2511916">so</span> <span m="2512872">that</span> <span m="2514070">if</span>
  <span m="2514330">i</span> <span m="2514670">is</span> <span m="2514850">equal</span>
  <span m="2515110">to</span> <span m="2515480">n,</span> <span m="2515830">then</span>
  <span m="2516210">i</span> <span m="2516590">plus</span> <span m="2516970">1</span>
  <span m="2517090">would be equal</span> <span m="2517420">to</span> <span m="2520980">1.</span>
  <span m="2524320">If</span> <span m="2525170">i</span> <span m="2525610">is equal</span>
  <span m="2525680">to</span> <span m="2525770">n,</span> <span m="2526130">if</span>
  <span m="2526270">i</span> <span m="2526770">is</span> <span m="2527010">the</span>
  <span m="2527390">last</span> <span m="2527770">grid point,</span> <span m="2528530">then</span>
  <span m="2529030">your</span> <span m="2529280">neighbor</span> <span m="2530160">who</span>
  <span m="2530280">was</span> <span m="2530630">y--</span> <span m="2531302">which</span>
  <span m="2531640">actually,</span> <span m="2531915">the</span> <span m="2532190">first</span>
  <span m="2532575">y</span> <span m="2532960">of</span> <span m="2533880">the</span>
  <span m="2533960">other</span> <span m="2534150">end.</span> <span m="2536360">So</span>
  <span m="2536690">n</span> <span m="2536860">plus</span> <span m="2537160">y</span>
  <span m="2537605">is</span> <span m="2538050">equal</span> <span m="2538440">to</span>
  <span m="2538926">y.</span></p><p><span m="2541280">What</span> <span m="2541510">is</span>
  <span m="2541660">the</span> <span m="2541750">first</span> <span m="2542090">line</span>
  <span m="2542380">of</span> <span m="2542480">the</span> <span m="2542580">matrix?</span>
  <span m="2543978">[INAUDIBLE]</span> <span m="2544444">boundary</span> <span m="2544910">condition.</span>
  <span m="2547535">What</span> <span m="2548170">happens</span> <span m="2548440">if</span>
  <span m="2548510">I</span> <span m="2548870">want</span> <span m="2549160">to approximate</span>
  <span m="2549540">of</span> <span m="2549920">e</span> <span m="2550090">to</span>
  <span m="2550565">the</span> <span m="2551040">x at</span> <span m="2551427">what,
  when</span> <span m="2551814">i</span> <span m="2552201">equals</span> <span m="2552590">to</span>
  <span m="2553080">what?</span></p><p><span m="2554060">STUDENT: [INAUDIBLE]</span></p><p><span
  m="2560440">QIQI WANG: Yeah.</span> <span m="2560940">I have</span> <span m="2561200">0</span>
  <span m="2561570">here</span> <span m="2561830">because</span> <span m="2563090">this</span>
  <span m="2563330">formula</span> <span m="2563740">do</span> <span m="2563870">not</span>
  <span m="2564060">depend</span> <span m="2564370">on</span> <span m="2564470">u</span>
  <span m="2564760">and</span> <span m="2565030">i,</span> <span m="2565300">right?</span>
  <span m="2566700">Now</span> <span m="2566980">when</span> <span m="2567170">I</span>
  <span m="2567270">go</span> <span m="2567480">to</span> <span m="2567580">the</span>
  <span m="2567690">second</span> <span m="2568070">one,</span> <span m="2568360">what</span>
  <span m="2568530">is</span> <span m="2568650">the</span> <span m="2568720">modify</span>
  <span m="2569140">on</span> <span m="2569240">u2?</span> <span m="2570415">The</span>
  <span m="2570720">modify</span> <span m="2571310">on</span> <span m="2571420">u2</span>
  <span m="2571460">is</span> <span m="2571630">1</span> <span m="2572360">over</span>
  <span m="2573070">2</span> <span m="2573270">down</span> <span m="2573370">x,</span>
  <span m="2574580">right?</span> <span m="2576590">And</span> <span m="2576800">is</span>
  <span m="2576970">there</span> <span m="2577190">any</span> <span m="2577420">other</span>
  <span m="2577590">than</span> <span m="2577870">0s?</span></p><p><span m="2578906">STUDENT:
  [INAUDIBLE].</span></p><p><span m="2580175">QIQI WANG: All</span> <span m="2580600">the</span>
  <span m="2580980">way</span> <span m="2581150">up</span> <span m="2581450">to</span>
  <span m="2581550">the end</span> <span m="2582470">because</span> <span m="2582920">I</span>
  <span m="2583070">have</span> <span m="2583360">periodic</span> <span m="2583490">boundary</span>
  <span m="2584080">condition,</span> <span m="2584560">I</span> <span m="2584770">have</span>
  <span m="2585100">this.</span> <span m="2588850">OK.</span> <span m="2589360">How</span>
  <span m="2589500">about</span> <span m="2589650">the</span> <span m="2589720">second</span>
  <span m="2590030">line?</span> <span m="2590300">The</span> <span m="2590380">second</span>
  <span m="2590640">one</span> <span m="2590750">is</span> <span m="2590900">actually
  a</span> <span m="2591170">easier</span> <span m="2592065">way</span> <span m="2592510">to</span>
  <span m="2592610">do</span> <span m="2592780">it.</span> <span m="2593900">When</span>
  <span m="2594120">i</span> <span m="2594310">is</span> <span m="2594370">equal</span>
  <span m="2594710">to</span> <span m="2595050">2?</span> <span m="2601580">When</span>
  <span m="2601780">i</span> <span m="2601970">is</span> <span m="2602150">equal</span>
  <span m="2602470">2,</span> <span m="2603330">du dx</span> <span m="2603430">at</span>
  <span m="2603730">2</span> <span m="2604150">is</span> <span m="2604330">equal</span>
  <span m="2604820">to</span> <span m="2604920">y.</span> <span m="2610910">It''s</span>
  <span m="2611080">equal</span> <span m="2611190">to</span> <span m="2611420">u3</span>
  <span m="2611780">minus</span> <span m="2612140">u1</span> <span m="2612380">divided</span>
  <span m="2613110">by</span> <span m="2613270">2</span> <span m="2613390">down</span>
  <span m="2613840">x.</span> <span m="2615290">So</span> <span m="2615560">u3</span>
  <span m="2615960">and</span> <span m="2616280">u1,</span> <span m="2617600">which</span>
  <span m="2617830">is</span> <span m="2617990">based</span> <span m="2618220">on</span>
  <span m="2618430">this--</span> <span m="2618840">so</span> <span m="2619090">this</span>
  <span m="2619480">guy</span> <span m="2619660">is</span> <span m="2619860">now</span>
  <span m="2620110">empty.</span> <span m="2620540">This</span> <span m="2620880">guy</span>
  <span m="2621060">is</span> <span m="2621200">now</span> <span m="2621430">empty,</span>
  <span m="2622280">right?</span></p><p><span m="2623980">We</span> <span m="2624160">would</span>
  <span m="2624350">get</span> <span m="2624600">minus</span> <span m="2625170">1</span>
  <span m="2625500">over</span> <span m="2625720">2</span> <span m="2625940">down</span>
  <span m="2626100">x</span> <span m="2626410">here</span> <span m="2626810">because</span>
  <span m="2627430">u1</span> <span m="2627710">is</span> <span m="2628930">being</span>
  <span m="2629560">minused</span> <span m="2631020">and</span> <span m="2631210">u3</span>
  <span m="2631870">is</span> <span m="2632060">being</span> <span m="2632320">plussed.</span>
  <span m="2634090">So</span> <span m="2634250">we</span> <span m="2634490">have</span>
  <span m="2634710">1</span> <span m="2634910">over</span> <span m="2635210">2</span>
  <span m="2635645">down</span> <span m="2636080">x over</span> <span m="2636300">here.</span>
  <span m="2637210">We</span> <span m="2637380">have</span> <span m="2637580">0</span>
  <span m="2637810">in</span> <span m="2637900">the</span> <span m="2637970">middle,</span>
  <span m="2638540">0,</span> <span m="2639510">and</span> <span m="2640140">0.</span>
  <span m="2640730">Everything</span> <span m="2641110">else</span> <span m="2641320">is</span>
  <span m="2641430">0.</span> <span m="2642020">So</span> <span m="2642330">I</span>
  <span m="2642665">think</span> <span m="2643000">under</span> <span m="2643270">[INAUDIBLE]</span>
  <span m="2644340">each</span> <span m="2644660">line</span> <span m="2645050">there</span>
  <span m="2645210">is</span> <span m="2645330">only</span> <span m="2645570">going</span>
  <span m="2645700">to</span> <span m="2645760">be</span> <span m="2645900">two</span>
  <span m="2646140">non-zeros,</span> <span m="2647540">only</span> <span m="2647810">two</span>
  <span m="2648040">non-zeros</span> <span m="2648915">because</span> <span m="2649290">each</span>
  <span m="2649590">derivative</span> <span m="2650416">only</span> <span m="2650830">depends</span>
  <span m="2651170">on</span> <span m="2651550">two</span> <span m="2651930">neighbors.</span>
  <span m="2652690">That</span> <span m="2653040">means</span> <span m="2655490">we</span>
  <span m="2655730">should</span> <span m="2655890">only</span> <span m="2656090">have</span>
  <span m="2656260">two</span> <span m="2656420">non-zeros.</span></p><p><span m="2658561">If
  you have</span> <span m="2659060">more</span> <span m="2659340">sets</span> <span
  m="2659590">over</span> <span m="2659940">here,</span> <span m="2660290">then</span>
  <span m="2661020">they</span> <span m="2661170">are</span> <span m="2661250">going</span>
  <span m="2661370">to</span> <span m="2661430">be</span> <span m="2661520">more</span>
  <span m="2661790">non-zeros.</span> <span m="2664318">Two</span> <span m="2664800">terms
  means</span> <span m="2665270">two</span> <span m="2665420">non-zeros</span> <span
  m="2665730">for each</span> <span m="2665990">line.</span> <span m="2666610">And</span>
  <span m="2667050">for</span> <span m="2667420">the</span> <span m="2667540">third</span>
  <span m="2667900">one,</span> <span m="2669670">my</span> <span m="2669890">minus</span>
  <span m="2670420">is</span> <span m="2670600">going</span> <span m="2670750">to</span>
  <span m="2670830">be</span> <span m="2671050">operating</span> <span m="2671610">on</span>
  <span m="2671750">u2.</span> <span m="2672840">My</span> <span m="2673070">plus</span>
  <span m="2673690">is</span> <span m="2674000">going</span> <span m="2674140">to</span>
  <span m="2674200">be</span> <span m="2674310">operating</span> <span m="2674890">on</span>
  <span m="2675040">u4.</span> <span m="2675450">And</span> <span m="2675926">for</span>
  <span m="2676402">the</span> <span m="2676940">fourth</span> <span m="2677690">line,</span>
  <span m="2678100">my</span> <span m="2678420">minus</span> <span m="2678880">is</span>
  <span m="2679070">going</span> <span m="2679240">to</span> <span m="2679320">be</span>
  <span m="2679400">operated</span> <span m="2679970">on</span> <span m="2680230">u3.</span>
  <span m="2681340">My</span> <span m="2681710">plus</span> <span m="2682080">is</span>
  <span m="2682360">going</span> <span m="2682490">to</span> <span m="2682550">be</span>
  <span m="2682620">operated</span> <span m="2683090">on</span> <span m="2683280">u5,</span>
  <span m="2684520">and</span> <span m="2685280">et cetera,</span> <span m="2685560">et</span>
  <span m="2686030">cetera.</span></p><p><span m="2686730">So</span> <span m="2686870">diagonally,</span>
  <span m="2687150">it''s</span> <span m="2687570">always</span> <span m="2687940">0</span>
  <span m="2688540">towards</span> <span m="2688850">the</span> <span m="2688910">very</span>
  <span m="2689200">last</span> <span m="2689470">line.</span> <span m="2690410">The</span>
  <span m="2690530">sub-diagonal</span> <span m="2691330">is</span> <span m="2691550">always</span>
  <span m="2691910">going</span> <span m="2692050">to</span> <span m="2692110">be</span>
  <span m="2692180">minus</span> <span m="2692700">2,</span> <span m="2695030">minus</span>
  <span m="2695640">1</span> <span m="2695860">over</span> <span m="2696040">2</span>
  <span m="2696180">delta</span> <span m="2696400">x</span> <span m="2696970">until
  the</span> <span m="2697260">last</span> <span m="2697730">line.</span> <span m="2698980">And</span>
  <span m="2699390">the</span> <span m="2700100">upper</span> <span m="2700410">diagonal</span>
  <span m="2700920">is</span> <span m="2701230">always</span> <span m="2701580">going</span>
  <span m="2701740">to</span> <span m="2701830">be</span> <span m="2702940">1</span>
  <span m="2703200">over</span> <span m="2703380">2</span> <span m="2703560">delta</span>
  <span m="2703730">x.</span> <span m="2705400">Am</span> <span m="2705550">I</span>
  <span m="2705640">missing</span> <span m="2705980">something</span> <span m="2706330">here?</span></p><p><span
  m="2707584">STUDENT: [INAUDIBLE].</span></p><p><span m="2710480">QIQI WANG: So</span>
  <span m="2710610">the</span> <span m="2710710">last</span> <span m="2711050">one,</span>
  <span m="2711600">the</span> <span m="2711720">positive,</span> <span m="2712450">is</span>
  <span m="2712650">over</span> <span m="2712890">here</span> <span m="2713190">because</span>
  <span m="2713900">of</span> <span m="2714550">the</span> <span m="2714750">periodic</span>
  <span m="2715246">boundary</span> <span m="2715742">condition.</span> <span m="2716240">Yes?</span></p><p><span
  m="2716570">STUDENT: [INAUDIBLE].</span></p><p><span m="2721040">QIQI WANG: Exactly.</span>
  <span m="2721620">Because</span> <span m="2721980">we</span> <span m="2722465">also</span>
  <span m="2722950">need</span> <span m="2723040">a</span> <span m="2723436">periodic</span>
  <span m="2723832">boundary</span> <span m="2724230">condition,</span> <span m="2725020">this</span>
  <span m="2725320">point,</span> <span m="2725706">instead</span> <span m="2726092">of</span>
  <span m="2726480">lying</span> <span m="2726930">over</span> <span m="2727350">here,</span>
  <span m="2727890">there</span> <span m="2727940">is</span> <span m="2728070">no</span>
  <span m="2728320">longer</span> <span m="2729540">anything</span> <span m="2730566">[INAUDIBLE]</span>
  <span m="2730950">anymore.</span> <span m="2732309">It is</span> <span m="2732762">actually</span>
  <span m="2733215">the</span> <span m="2733668">first</span> <span m="2734121">element</span>
  <span m="2734574">of the  left.</span> <span m="2735350">This entry,</span> <span
  m="2736264">no</span> <span m="2736721">matter</span> <span m="2737180">how matrix</span>
  <span m="2737280">multiply</span> <span m="2737370">with</span> <span m="2737837">a</span>
  <span m="2738304">vector?</span> <span m="2738771">This</span> <span m="2739238">entry</span>
  <span m="2739705">is going</span> <span m="2740172">to be</span> <span m="2740640">multiplied</span>
  <span m="2741115">[INAUDIBLE]</span> <span m="2745390">instead</span> <span m="2745865">of</span>
  <span m="2746340">U n</span> <span m="2746815">plus</span> <span m="2747770">1,</span>
  <span m="2748050">which</span> <span m="2748516">[INAUDIBLE].</span></p><p><span
  m="2754110">Any</span> <span m="2754260">question</span> <span m="2754590">on</span>
  <span m="2754740">this</span> <span m="2754980">[INAUDIBLE]</span> <span m="2755461">matrix?</span>
  <span m="2758350">So</span> <span m="2758690">all of</span> <span m="2758770">this</span>
  <span m="2758900">matrix</span> <span m="2759320">is</span> <span m="2759730">really</span>
  <span m="2759970">a</span> <span m="2760020">million</span> <span m="2760360">by</span>
  <span m="2760580">million.</span> <span m="2761444">But</span> <span m="2761908">it</span>
  <span m="2762372">only</span> <span m="2762836">compares</span> <span m="2763300">two</span>
  <span m="2763360">a million,</span> <span m="2763570">1, 0</span> <span m="2763760">entries.</span>
  <span m="2764870">Most</span> <span m="2765150">computers</span> <span m="2765670">have</span>
  <span m="2765880">enough</span> <span m="2766310">memory</span> <span m="2766680">to
  store</span> <span m="2766965">a</span> <span m="2767250">million</span> <span m="2768776">non-zero</span>
  <span m="2769244">entries.</span> <span m="2770650">All</span> <span m="2770820">right.</span>
  <span m="2771290">So</span> <span m="2771470">this is</span> <span m="2771660">central</span>
  <span m="2772080">difference.</span> <span m="2772530">Let''s</span> <span m="2772790">just</span>
  <span m="2772990">do</span> <span m="2773090">an</span> <span m="2773270">exercise</span>
  <span m="2773920">of</span> <span m="2774150">how,</span> <span m="2774690">if</span>
  <span m="2774900">we</span> <span m="2775190">do</span> <span m="2775510">a--</span>
  <span m="2776362">oh, I</span> <span m="2776790">haven''t</span> <span m="2777080">talked</span>
  <span m="2777270">about</span> <span m="2777500">upwind</span> <span m="2777830">yet,</span>
  <span m="2779342">so</span> <span m="2781070">backward</span> <span m="2785170">in</span>
  <span m="2785590">space</span> <span m="2789150">difference.</span></p><p><span
  m="2789861">STUDENT: [INAUDIBLE].</span></p><p><span m="2791825">QIQI WANG: Huh?</span></p><p><span
  m="2792316">STUDENT: [INAUDIBLE]</span></p><p><span m="2797226">QIQI WANG: Towards
  the</span> <span m="2797717">upwind</span> <span m="2798208">of the</span> <span
  m="2798700">[INAUDIBLE].</span> <span m="2799460">Good</span> <span m="2799650">guess.</span>
  <span m="2801510">Right.</span> <span m="2801930">So</span> <span m="2802250">if</span>
  <span m="2803910">I</span> <span m="2804050">do</span> <span m="2804210">a</span>
  <span m="2804290">backward</span> <span m="2804390">in</span> <span m="2804870">space,</span>
  <span m="2805600">I''m</span> <span m="2805890">going</span> <span m="2806060">to</span>
  <span m="2806150">be</span> <span m="2806470">writing</span> <span m="2806900">the</span>
  <span m="2807010">same</span> <span m="2807330">thing,</span> <span m="2807880">partial</span>
  <span m="2807960">u</span> <span m="2808850">partial</span> <span m="2809140">x</span>
  <span m="2809530">at</span> <span m="2809950">1,</span> <span m="2810370">partial</span>
  <span m="2810760">u,</span> <span m="2811080">partial</span> <span m="2811250">x</span>
  <span m="2811400">at</span> <span m="2811820">2</span> <span m="2812210">essential,</span>
  <span m="2813110">partial</span> <span m="2813270">u</span> <span m="2813360">partial</span>
  <span m="2813710">x</span> <span m="2813920">at</span> <span m="2814070">n.</span>
  <span m="2819462">I</span> <span m="2819890">think</span> <span m="2820140">I</span>
  <span m="2820527">used</span> <span m="2820914">a</span> <span m="2821301">small--</span>
  <span m="2821690">yeah.</span> <span m="2821985">I used</span> <span m="2822280">a</span>
  <span m="2822400">small</span> <span m="2822680">n--</span> <span m="2827590">is</span>
  <span m="2827860">equal</span> <span m="2828220">to</span> <span m="2829880">a</span>
  <span m="2830030">joint</span> <span m="2830470">matrix</span> <span m="2831000">of</span>
  <span m="2831150">the</span> <span m="2831240">same</span> <span m="2831570">size</span>
  <span m="2832480">times</span> <span m="2832740">u1,</span> <span m="2833680">u2,</span>
  <span m="2833940">et</span> <span m="2834200">cetera.</span> <span m="2834970">So</span>
  <span m="2835970">nothing</span> <span m="2836430">has</span> <span m="2836640">changed,</span>
  <span m="2837130">except</span> <span m="2837560">for</span> <span m="2838220">the</span>
  <span m="2838350">content</span> <span m="2838940">of</span> <span m="2839060">the</span>
  <span m="2839140">matrix.</span></p><p><span m="2840870">And</span> <span m="2842510">a</span>
  <span m="2843540">backwards</span> <span m="2844110">space</span> <span m="2844630">difference</span>
  <span m="2845150">is</span> <span m="2845380">partial</span> <span m="2845650">u</span>
  <span m="2845905">partial</span> <span m="2846160">x</span> <span m="2846860">at</span>
  <span m="2847180">i</span> <span m="2848010">is</span> <span m="2848220">equal</span>
  <span m="2848570">to</span> <span m="2848990">Ui</span> <span m="2849320">minus</span>
  <span m="2849640">Ui</span> <span m="2850140">minus</span> <span m="2850390">1</span>
  <span m="2851180">divided</span> <span m="2851640">by</span> <span m="2851990">delta
  x.</span> <span m="2855430">All right.</span> <span m="2855690">Somebody</span>
  <span m="2856020">help</span> <span m="2856180">me</span> <span m="2856440">fill</span>
  <span m="2856670">in</span> <span m="2857160">the</span> <span m="2857270">blanks.</span>
  <span m="2860480">Fill</span> <span m="2860880">the</span> <span m="2861230">blanks</span>
  <span m="2861800">of</span> <span m="2862030">a</span> <span m="2862100">million</span>
  <span m="2862450">by</span> <span m="2862580">million</span> <span m="2862920">matrix.</span>
  <span m="2867780">Doesn''t</span> <span m="2868140">take</span> <span m="2868600">that</span>
  <span m="2868900">much</span> <span m="2869100">time</span> <span m="2869565">to</span>
  <span m="2870030">fill</span> <span m="2870495">in,</span> <span m="2870960">actually.</span>
  <span m="2873730">What</span> <span m="2873860">is</span> <span m="2873990">the</span>
  <span m="2874140">first</span> <span m="2874520">top</span> <span m="2874890">level</span>
  <span m="2875200">entry?</span></p><p><span m="2876072">STUDENT: One over delta
  x.</span></p><p><span m="2877490">QIQI WANG: One</span> <span m="2877820">over</span>
  <span m="2877920">delta</span> <span m="2877980">x.</span> <span m="2878210">It</span>
  <span m="2878460">is</span> <span m="2878770">no</span> <span m="2878920">longer</span>
  <span m="2879310">0</span> <span m="2880720">because</span> <span m="2881690">the</span>
  <span m="2881990">du dx</span> <span m="2882480">at</span> <span m="2882780">ix</span>
  <span m="2883030">usually</span> <span m="2883380">depends</span> <span m="2883510">on</span>
  <span m="2883820">Ui.</span> <span m="2885880">In</span> <span m="2886090">the</span>
  <span m="2886170">last</span> <span m="2886460">case,</span> <span m="2886930">the</span>
  <span m="2887090">du dx</span> <span m="2887450">at</span> <span m="2887610">i</span>
  <span m="2887980">does</span> <span m="2888190">not</span> <span m="2888410">depend</span>
  <span m="2888680">on</span> <span m="2888790">Ui.</span> <span m="2890250">So</span>
  <span m="2890600">we</span> <span m="2890810">have</span> <span m="2891060">one</span>
  <span m="2891350">other</span> <span m="2891500">entry</span> <span m="2892220">because</span>
  <span m="2892570">we</span> <span m="2892690">have</span> <span m="2892870">two</span>
  <span m="2893040">elements</span> <span m="2893510">in</span> <span m="2893600">each</span>
  <span m="2894020">derivative.</span> <span m="2894850">What</span> <span m="2895050">is</span>
  <span m="2895230">the</span> <span m="2895390">other</span> <span m="2895670">non-zero</span>
  <span m="2896130">entry?</span></p><p><span m="2897520">STUDENT: At</span> <span
  m="2898000">the very</span> <span m="2898480">end.</span></p><p><span m="2898960">QIQI
  WANG: At</span> <span m="2899120">the</span> <span m="2899180">very</span> <span
  m="2899650">end.</span> <span m="2900080">That one</span> <span m="2900310">is</span>
  <span m="2900820">the</span> <span m="2900930">same.</span> <span m="2902322">All</span>
  <span m="2902980">the</span> <span m="2903090">others</span> <span m="2903400">are</span>
  <span m="2903530">0''s.</span> <span m="2904970">How</span> <span m="2905230">about</span>
  <span m="2905300">the</span> <span m="2905620">second</span> <span m="2905930">line?</span>
  <span m="2908710">We</span> <span m="2908880">have</span> <span m="2909090">diagonals</span>
  <span m="2909505">to</span> <span m="2909920">be</span> <span m="2910590">always</span>
  <span m="2912080">1</span> <span m="2912390">over</span> <span m="2912580">delta</span>
  <span m="2912710">x</span> <span m="2913200">because</span> <span m="2914100">we</span>
  <span m="2914290">always</span> <span m="2914610">have</span> <span m="2914840">1</span>
  <span m="2915050">over</span> <span m="2915580">delta</span> <span m="2915740">x</span>
  <span m="2916180">multiplied</span> <span m="2917626">by</span> <span m="2918108">Ui.</span>
  <span m="2918590">That</span> <span m="2918810">going to</span> <span m="2919070">be</span>
  <span m="2919320">du dxi.</span> <span m="2921600">And</span> <span m="2921930">we</span>
  <span m="2922000">have</span> <span m="2922750">1</span> <span m="2923110">minues--</span>
  <span m="2923580">sorry.</span></p><p><span m="2924870">We</span> <span m="2925000">have</span>
  <span m="2925170">minus</span> <span m="2925560">of</span> <span m="2925710">1</span>
  <span m="2925920">over</span> <span m="2926070">delta</span> <span m="2926290">x</span>
  <span m="2927110">always</span> <span m="2927590">towards</span> <span m="2927920">the</span>
  <span m="2927990">left</span> <span m="2929580">because</span> <span m="2930610">the</span>
  <span m="2930800">value</span> <span m="2931290">at</span> <span m="2931420">the</span>
  <span m="2931490">left</span> <span m="2931870">is</span> <span m="2932060">always</span>
  <span m="2932440">multiplied</span> <span m="2933060">by</span> <span m="2934438">minus</span>
  <span m="2934912">1  over</span> <span m="2935386">delta</span> <span m="2935860">x.</span>
  <span m="2939178">All</span> <span m="2939660">right?</span> <span m="2941930">OK.</span>
  <span m="2942370">Another</span> <span m="2942710">x.</span></p><p><span m="2943920">So</span>
  <span m="2944120">OK.</span> <span m="2944380">So</span> <span m="2945060">how</span>
  <span m="2945100">about</span> <span m="2945410">let''s</span> <span m="2946080">try</span>
  <span m="2946370">to,</span> <span m="2946830">in</span> <span m="2947250">MATLAB,</span>
  <span m="2947720">try</span> <span m="2947980">to</span> <span m="2952710">construct</span>
  <span m="2954070">the</span> <span m="2954360">matrix</span> <span m="2954810">form.</span>
  <span m="2956380">When</span> <span m="2956580">we</span> <span m="2956690">construct</span>
  <span m="2957080">the</span> <span m="2957140">matrix</span> <span m="2957500">form,</span>
  <span m="2957830">we</span> <span m="2958000">don''t</span> <span m="2958370">need</span>
  <span m="2958540">to</span> <span m="2958640">do</span> <span m="2958910">it</span>
  <span m="2959290">in</span> <span m="2959490">every</span> <span m="2959960">concept.</span>
  <span m="2960210">We</span> <span m="2960530">an</span> <span m="2960850">do</span>
  <span m="2960980">it</span> <span m="2961985">well</span> <span m="2962320">in</span>
  <span m="2962788">advance.</span> <span m="2964660">So</span> <span m="2964880">after</span>
  <span m="2965240">we</span> <span m="2965410">settle</span> <span m="2965820">initial</span>
  <span m="2966110">conditions,</span> <span m="2966520">let''s</span> <span m="2966960">actually--</span>
  <span m="2967330">before</span> <span m="2967690">we</span> <span m="2967840">settle</span>
  <span m="2968040">our</span> <span m="2968170">initial</span> <span m="2968420">conditions,</span>
  <span m="2968990">we</span> <span m="2969100">know</span> <span m="2969570">what</span>
  <span m="2969830">n</span> <span m="2970330">is,</span> <span m="2970830">we</span>
  <span m="2970990">try</span> <span m="2971390">to</span> <span m="2971743">set</span>
  <span m="2972096">up</span> <span m="2972540">matrix</span> <span m="2972988">a.</span></p><p><span
  m="2976130">OK.</span> <span m="2977700">Let''s</span> <span m="2977900">call</span>
  <span m="2978140">it</span> <span m="2978260">a</span> <span m="2978580">ddt.</span>
  <span m="2979290">So</span> <span m="2979350">that</span> <span m="2979540">is</span>
  <span m="2979740">the</span> <span m="2980580">matrix</span> <span m="2981070">that</span>
  <span m="2981300">gives</span> <span m="2981520">me--</span> <span m="2981770">sorry--</span>
  <span m="2982520">ddx,</span> <span m="2983720">that</span> <span m="2984040">gives</span>
  <span m="2984270">me</span> <span m="2985410">derivative</span> <span m="2985960">to</span>
  <span m="2986110">x.</span> <span m="2988620">So</span> <span m="2988750">let</span>
  <span m="2988900">me</span> <span m="2989020">see</span> <span m="2989210">what</span>
  <span m="2989430">I</span> <span m="2989510">did.</span> <span m="2990060">Here</span>
  <span m="2990260">is</span> <span m="2990410">actually</span> <span m="2990680">backward</span>
  <span m="2991050">in</span> <span m="2991150">space.</span> <span m="2991540">So</span>
  <span m="2991680">let''s</span> <span m="2992260">try</span> <span m="2992420">to</span>
  <span m="2992580">reproduce</span> <span m="2993050">backward</span> <span m="2993470">in
  space.</span></p><p><span m="2998290">This</span> <span m="2998510">is</span> <span
  m="2998610">the</span> <span m="2998680">matrix</span> <span m="2999080">I</span>
  <span m="2999220">have.</span> <span m="3000500">I</span> <span m="3000590">already</span>
  <span m="3000970">have</span> <span m="3001230">delta</span> <span m="3001310">x</span>
  <span m="3001420">computed.</span> <span m="3001790">Yes,</span> <span m="3002155">I
  do.</span> <span m="3003520">So</span> <span m="3003790">then</span> <span m="3004300">I</span>
  <span m="3004550">need</span> <span m="3005510">two</span> <span m="3005820">matrices.</span>
  <span m="3007310">One</span> <span m="3007800">matrix,</span> <span m="3008250">the</span>
  <span m="3008340">first</span> <span m="3008630">matrix,</span> <span m="3009170">is</span>
  <span m="3009760">this</span> <span m="3010050">guy.</span> <span m="3013200">I</span>
  <span m="3013390">need,</span> <span m="3014120">first</span> <span m="3014440">of</span>
  <span m="3014600">all,</span> <span m="3014780">this</span> <span m="3014960">matrix.</span>
  <span m="3015890">And</span> <span m="3016170">somehow</span> <span m="3016600">if</span>
  <span m="3016790">I</span> <span m="3016920">can</span> <span m="3017300">add</span>
  <span m="3017810">that</span> <span m="3018190">matrix</span> <span m="3019540">to</span>
  <span m="3020890">the</span> <span m="3021010">second</span> <span m="3021390">matrix,</span>
  <span m="3021970">if</span> <span m="3022170">I</span> <span m="3022270">can</span>
  <span m="3022500">add</span> <span m="3022940">that</span> <span m="3023160">matrix</span>
  <span m="3023730">to</span> <span m="3024000">this</span> <span m="3024280">matrix</span>
  <span m="3024730">plus</span> <span m="3025180">this</span> <span m="3025420">little</span>
  <span m="3025740">element</span> <span m="3026090">over</span> <span m="3026310">here,</span>
  <span m="3027160">then</span> <span m="3027460">I</span> <span m="3027690">have</span>
  <span m="3028640">the entire</span> <span m="3029030">matrix.</span></p><p><span
  m="3031200">So</span> <span m="3031370">let''s</span> <span m="3031560">look</span>
  <span m="3031800">at</span> <span m="3031930">the</span> <span m="3032000">diagonals,</span>
  <span m="3035240">the</span> <span m="3035370">blue</span> <span m="3035630">one.</span>
  <span m="3036322">Can</span> <span m="3036670">everybody</span> <span m="3037060">tell</span>
  <span m="3037340">me,</span> <span m="3037870">is</span> <span m="3038060">there</span>
  <span m="3038804">an</span> <span m="3039268">easy</span> <span m="3039732">way</span>
  <span m="3040196">to</span> <span m="3040660">[INAUDIBLE]</span> <span m="3041124">the
  blue matrix?</span></p><p><span m="3041588">STUDENT: [INAUDIBLE].</span></p><p><span
  m="3042980">QIQI WANG: Huh?</span> <span m="3044760">It''s</span> <span m="3044920">identity,</span>
  <span m="3045968">it''s</span> <span m="3046456">identity</span> <span m="3046944">matrix</span>
  <span m="3048408">times</span> <span m="3049390">one</span> <span m="3049660">over</span>
  <span m="3049780">delta</span> <span m="3050130">x.</span> <span m="3052140">That
  one</span> <span m="3052380">is</span> <span m="3052540">actually</span> <span m="3053035">super</span>
  <span m="3053530">easy.</span> <span m="3061945">How</span> <span m="3062450">about</span>
  <span m="3062910">the</span> <span m="3063100">other</span> <span m="3063360">one?</span>
  <span m="3063570">How</span> <span m="3063670">about</span> <span m="3063850">the</span>
  <span m="3063930">black</span> <span m="3064430">one?</span></p><p><span m="3066430">STUDENT:
  [INAUDIBLE].</span></p><p><span m="3069480">QIQI WANG: Yes.</span> <span m="3069840">I</span>
  <span m="3069980">can</span> <span m="3070140">use</span> <span m="3070400">my</span>
  <span m="3070560">x.</span> <span m="3071310">I</span> <span m="3071460">can</span>
  <span m="3071590">use</span> <span m="3071810">diag</span> <span m="3072280">if</span>
  <span m="3072450">I</span> <span m="3072580">don''t</span> <span m="3072800">have</span>
  <span m="3073530">this</span> <span m="3073800">one.</span> <span m="3074150">I''m</span>
  <span m="3074350">going</span> <span m="3074490">to</span> <span m="3074640">see</span>
  <span m="3074860">later</span> <span m="3075300">on</span> <span m="3075500">if</span>
  <span m="3075910">I</span> <span m="3076420">have</span> <span m="3076690">not</span>
  <span m="3077070">periodic</span> <span m="3077270">boundary</span> <span m="3077320">condition.</span>
  <span m="3078472">Periodic</span> <span m="3078954">boundary</span> <span m="3079436">condition</span>
  <span m="3079918">is actually this.</span> <span m="3080400">If I</span> <span m="3080882">don''t
  have</span> <span m="3081364">periodic</span> <span m="3081846">boundary</span>
  <span m="3082328">condition,</span> <span m="3082810">[INAUDIBLE]</span> <span m="3084738">then</span>
  <span m="3085220">diag</span> <span m="3085710">is</span> <span m="3085930">a</span>
  <span m="3086000">very</span> <span m="3086820">good</span> <span m="3087130">way
  to do it.</span> <span m="3088190">In</span> <span m="3088350">this</span> <span
  m="3088550">case,</span> <span m="3088940">I''m</span> <span m="3088980">going</span>
  <span m="3089100">to</span> <span m="3089210">use</span> <span m="3089470">the</span>
  <span m="3089560">same</span> <span m="3090020">function,</span> <span m="3090330">the</span>
  <span m="3090430">third</span> <span m="3090500">shift</span> <span m="3092170">I</span>
  <span m="3092320">just</span> <span m="3092620">used</span> <span m="3093950">to</span>
  <span m="3094300">centrally</span> <span m="3094820">shift</span> <span m="3095220">the</span>
  <span m="3095310">solution</span> <span m="3095770">itself.</span> <span m="3096420">I</span>
  <span m="3096840">can</span> <span m="3097260">also</span> <span m="3097580">shift</span>
  <span m="3098062">the</span> <span m="3098544">matrix.</span> <span m="3099508">I</span>
  <span m="3099990">can take</span> <span m="3100472">this</span> <span m="3100954">matrix,</span>
  <span m="3102882">shift</span> <span m="3103364">it</span> <span m="3103846">to
  the left</span> <span m="3104340">or</span> <span m="3104740">towards</span> <span
  m="3106030">the</span> <span m="3106170">bottom.</span> <span m="3106562">It''s</span>
  <span m="3107346">the</span> <span m="3107740">same</span> <span m="3107980">way.</span>
  <span m="3108260">I''m</span> <span m="3108490">going</span> <span m="3108580">to</span>
  <span m="3108983">get</span> <span m="3109386">the</span> <span m="3109890">back</span>
  <span m="3110298">matrix.</span></p><p><span m="3112410">It</span> <span m="3112570">is</span>
  <span m="3112750">equal</span> <span m="3113070">to</span> <span m="3113600">i</span>
  <span m="3114590">of</span> <span m="3115090">n</span> <span m="3115590">divided</span>
  <span m="3116180">by</span> <span m="3116410">delta</span> <span m="3116810">x.</span>
  <span m="3117800">So</span> <span m="3117950">that</span> <span m="3118190">gives</span>
  <span m="3118370">me</span> <span m="3118610">the</span> <span m="3118720">blue</span>
  <span m="3119140">one.</span> <span m="3121020">I''m</span> <span m="3121190">going</span>
  <span m="3121270">to</span> <span m="3121620">minus</span> <span m="3123100">in</span>
  <span m="3124000">by</span> <span m="3124650">dx.</span> <span m="3125340">But</span>
  <span m="3125670">I''m</span> <span m="3125890">going</span> <span m="3126040">to</span>
  <span m="3126180">circshift</span> <span m="3128376">the</span> <span m="3128770">whole</span>
  <span m="3128930">matrix</span> <span m="3130010">by</span> <span m="3131630">left</span>
  <span m="3132020">2</span> <span m="3132450">towards</span> <span m="3132640">the</span>
  <span m="3132730">bottom.</span> <span m="3133490">Towards</span> <span m="3133590">the</span>
  <span m="3133850">bottom</span> <span m="3134290">is</span> <span m="3134470">[INAUDIBLE]</span>
  <span m="3135880">in</span> <span m="3136350">the</span> <span m="3136820">third</span>
  <span m="3137290">direction,</span> <span m="3137760">1</span> <span m="3138230">in</span>
  <span m="3138700">the</span> <span m="3139170">other</span> <span m="3139640">direction,</span>
  <span m="3140110">0</span> <span m="3140580">in</span> <span m="3141050">the</span>
  <span m="3141520">[INAUDIBLE]</span> <span m="3141700">direction.</span> <span m="3141820">So
  I''m going</span> <span m="3141940">to</span> <span m="3142080">shift</span> <span
  m="3142460">it</span> <span m="3143370">by</span> <span m="3143540">1</span> <span
  m="3143970">and</span> <span m="3144220">0.</span></p><p><span m="3146380">OK.</span>
  <span m="3147770">That</span> <span m="3148010">is</span> <span m="3148200">my</span>
  <span m="3150380">plan</span> <span m="3150560">a</span> <span m="3150640">difference</span>
  <span m="3150990">matrix.</span> <span m="3154400">Now</span> <span m="3154550">how</span>
  <span m="3154740">do</span> <span m="3154870">I</span> <span m="3154930">apply</span>
  <span m="3155350">it?</span> <span m="3156740">How to</span> <span m="3157050">apply</span>
  <span m="3157390">it--</span> <span m="3158540">when</span> <span m="3158790">I</span>
  <span m="3158860">computed</span> <span m="3159190">du</span> <span m="3159520">dx,</span>
  <span m="3164160">When</span> <span m="3164330">I</span> <span m="3164390">compute</span>
  <span m="3164790">du</span> <span m="3164870">dx--</span> <span m="3165680">let</span>
  <span m="3165890">me</span> <span m="3165970">first</span> <span m="3166280">do</span>
  <span m="3166380">one</span> <span m="3166670">thing.</span> <span m="3169840">I</span>
  <span m="3169980">want</span> <span m="3170200">to</span> <span m="3170300">make</span>
  <span m="3170590">my</span> <span m="3170790">everything</span> <span m="3171320">to</span>
  <span m="3171440">be</span> <span m="3171540">a</span> <span m="3171620">color</span>
  <span m="3172000">matrix</span> <span m="3172440">first</span> <span m="3172820">because</span>
  <span m="3173790">by</span> <span m="3174000">default,</span> <span m="3174530">if</span>
  <span m="3174690">I</span> <span m="3174830">do</span> <span m="3175080">1</span>
  <span m="3175410">to</span> <span m="3175570">n,</span> <span m="3175830">it''s</span>
  <span m="3175990">a</span> <span m="3176100">row</span> <span m="3176290">matrix.</span>
  <span m="3177250">Where</span> <span m="3177650">if</span> <span m="3177860">I</span>
  <span m="3177980">want</span> <span m="3178260">to</span> <span m="3178360">multiply</span>
  <span m="3178610">the</span> <span m="3178840">matrices</span> <span m="3179130">that</span>
  <span m="3179570">way,</span> <span m="3180890">I</span> <span m="3181330">need</span>
  <span m="3181770">my</span> <span m="3182210">solutions</span> <span m="3182760">to</span>
  <span m="3182940">be</span> <span m="3183450">like</span> <span m="3183690">a</span>
  <span m="3183830">column.</span> <span m="3185000">So</span> <span m="3185880">initially,</span>
  <span m="3186420">I</span> <span m="3186540">want</span> <span m="3186710">to</span>
  <span m="3186810">construct</span> <span m="3187250">this</span> <span m="3187440">by</span>
  <span m="3187630">columns.</span> <span m="3188950">And</span> <span m="3189390">everything</span>
  <span m="3189560">should</span> <span m="3189760">be</span> <span m="3190155">in</span>
  <span m="3190550">columns.</span> <span m="3191340">And</span> <span m="3192830">this</span>
  <span m="3193050">is</span> <span m="3193190">no</span> <span m="3193350">longer</span>
  <span m="3193630">true</span> <span m="3193870">anymore.</span> <span m="3194300">I''m
  going to</span> <span m="3194730">remove</span> <span m="3195110">this.</span></p><p><span
  m="3197335">I''m going to</span> <span m="3197780">just</span> <span m="3198020">do</span>
  <span m="3198240">a</span> <span m="3198595">linear</span> <span m="3198950">advection</span>
  <span m="3199350">equation</span> <span m="3199610">first.</span> <span m="3200600">But</span>
  <span m="3200730">my</span> <span m="3200900">du</span> <span m="3201350">dx</span>
  <span m="3201910">is</span> <span m="3202190">equal</span> <span m="3202520">to</span>
  <span m="3203080">a_ddx</span> <span m="3205190">times</span> <span m="3205628">u.</span>
  <span m="3207380">That''s</span> <span m="3207630">how</span> <span m="3207810">easy</span>
  <span m="3208120">it</span> <span m="3208190">is</span> <span m="3209400">to</span>
  <span m="3209880">apply</span> <span m="3210840">this</span> <span m="3211010">on</span>
  <span m="3211120">a</span> <span m="3211380">difference</span> <span m="3211660">matrix.</span>
  <span m="3212800">Also,</span> <span m="3213420">I</span> <span m="3213560">have</span>
  <span m="3213820">the</span> <span m="3213910">final</span> <span m="3214190">difference</span>
  <span m="3214510">matrix,</span> <span m="3215690">I</span> <span m="3215870">don''t</span>
  <span m="3217230">need</span> <span m="3217380">to</span> <span m="3217480">do</span>
  <span m="3217710">anything</span> <span m="3218310">at</span> <span m="3218713">each</span>
  <span m="3219116">concept</span> <span m="3219520">other</span> <span m="3219720">than</span>
  <span m="3219950">just</span> <span m="3220575">applying</span> <span m="3221215">the</span>
  <span m="3221620">matrix</span> <span m="3222770">just</span> <span m="3223140">as</span>
  <span m="3223290">if</span> <span m="3223580">it is</span> <span m="3224330">the</span>
  <span m="3224380">mathematical</span> <span m="3225210">operator.</span></p><p><span
  m="3227260">I</span> <span m="3227380">just</span> <span m="3227620">think</span>
  <span m="3227840">this</span> <span m="3228030">matrix</span> <span m="3228230">is</span>
  <span m="3228340">my</span> <span m="3228660">actual</span> <span m="3228860">[INAUDIBLE].</span>
  <span m="3230080">I</span> <span m="3230570">apply</span> <span m="3231340">on</span>
  <span m="3231595">top of</span> <span m="3231850">u,</span> <span m="3232270">I</span>
  <span m="3232420">get</span> <span m="3232920">partial</span> <span m="3233520">u</span>
  <span m="3233982">partial</span> <span m="3234444">x.</span> <span m="3235830">So</span>
  <span m="3236010">this</span> <span m="3236320">a</span> <span m="3236720">serves</span>
  <span m="3237110">like</span> <span m="3237410">a</span> <span m="3237580">mathematical</span>
  <span m="3237865">operator.</span> <span m="3239214">I''m</span> <span m="3239591">going
  to</span> <span m="3239970">round</span> <span m="3240275">this.</span> <span m="3243430">I''m</span>
  <span m="3243620">going</span> <span m="3243750">to</span> <span m="3243820">get</span>
  <span m="3244070">the</span> <span m="3244160">same</span> <span m="3244590">solution.</span>
  <span m="3246450">Of</span> <span m="3246570">course,</span> <span m="3246840">this
  is</span> <span m="3247110">backward</span> <span m="3247480">in</span> <span m="3247610">space.</span>
  <span m="3248000">I</span> <span m="3248110">got</span> <span m="3248380">a</span>
  <span m="3248520">solution</span> <span m="3248930">that</span> <span m="3249120">moves</span>
  <span m="3249500">towards</span> <span m="3249860">the</span> <span m="3249950">right</span>
  <span m="3250140">but</span> <span m="3250800">also</span> <span m="3251660">the</span>
  <span m="3251770">case.</span> <span m="3253370">So</span> <span m="3253780">this</span>
  <span m="3253970">is</span> <span m="3256500">what</span> <span m="3256660">I</span>
  <span m="3256770">have</span> <span m="3257070">as</span> <span m="3257260">a</span>
  <span m="3257340">backwards</span> <span m="3257770">difference.</span></p><p><span
  m="3259150">And</span> <span m="3259340">I</span> <span m="3259742">can</span> <span
  m="3261590">modify</span> <span m="3261820">this.</span> <span m="3264240">So</span>
  <span m="3264540">I''m</span> <span m="3264700">going</span> <span m="3264860">to</span>
  <span m="3264990">[INAUDIBLE]</span> <span m="3265393">this out.</span> <span m="3266200">This</span>
  <span m="3266490">is</span> <span m="3266640">backward</span> <span m="3267081">difference.</span>
  <span m="3269290">I''m</span> <span m="3269480">going</span> <span m="3269640">to</span>
  <span m="3269820">do</span> <span m="3270100">central.</span> <span m="3271680">And</span>
  <span m="3271980">in the</span> <span m="3272405">central,</span> <span m="3273510">the</span>
  <span m="3273650">difference</span> <span m="3274230">is</span> <span m="3274490">I</span>
  <span m="3274630">need</span> <span m="3274810">to</span> <span m="3274910">circshift</span>
  <span m="3275810">both.</span> <span m="3277635">I</span> <span m="3278110">need</span>
  <span m="3278350">to</span> <span m="3278450">circshift</span> <span m="3279060">this</span>
  <span m="3279970">in</span> <span m="3280210">the</span> <span m="3280490">opposite</span>
  <span m="3280700">direction.</span> <span m="3282215">And</span> <span m="3282930">instead</span>
  <span m="3283280">of</span> <span m="3283560">dividing</span> <span m="3283900">by</span>
  <span m="3284250">1</span> <span m="3284590">delta</span> <span m="3284680">x,</span>
  <span m="3285970">actually,</span> <span m="3286290">let</span> <span m="3288490">me</span>
  <span m="3288570">divide</span> <span m="3289000">this</span> <span m="3289240">by</span>
  <span m="3289640">2</span> <span m="3290140">delta</span> <span m="3290840">x.</span>
  <span m="3293642">So</span> <span m="3294110">this</span> <span m="3294300">is</span>
  <span m="3294620">going</span> <span m="3294760">to</span> <span m="3294820">be</span>
  <span m="3294890">my</span> <span m="3295490">central</span> <span m="3295790">difference,</span>
  <span m="3296540">right?</span> <span m="3300050">Agreed?</span></p><p><span m="3302890">If</span>
  <span m="3303050">you</span> <span m="3303150">look</span> <span m="3303380">at</span>
  <span m="3303500">this,</span> <span m="3306700">I</span> <span m="3306870">have</span>
  <span m="3308040">one</span> <span m="3308830">identity</span> <span m="3309620">matrix.</span>
  <span m="3310636">shifted</span> <span m="3311010">towards</span> <span m="3311335">the</span>
  <span m="3311660">right.</span> <span m="3311940">And</span> <span m="3312435">I</span>
  <span m="3312930">have another</span> <span m="3313425">one</span> <span m="3313920">shifted
  towards</span> <span m="3314415">the left.</span> <span m="3315900">So</span> <span
  m="3316040">I</span> <span m="3316120">get</span> <span m="3316917">two</span> <span
  m="3317334">matrices</span> <span m="3318170">subtracted.</span> <span m="3318820">I</span>
  <span m="3318950">get</span> <span m="3319220">the</span> <span m="3320450">central</span>
  <span m="3320710">difference.</span> <span m="3321762">Let me</span> <span m="3322150">look</span>
  <span m="3322520">at</span> <span m="3323070">delta</span> <span m="3323470">behavior.</span>
  <span m="3324820">Looks</span> <span m="3325130">like</span> <span m="3325360">the</span>
  <span m="3325460">same</span> <span m="3325770">as</span> <span m="3325900">the</span>
  <span m="3325990">central</span> <span m="3326320">difference.</span> <span m="3327222">It</span>
  <span m="3327673">does,</span> <span m="3328124">right?</span> <span m="3328575">I
  have</span> <span m="3329026">a</span> <span m="3329480">solution</span> <span m="3329840">where</span>
  <span m="3330330">we</span> <span m="3330820">go to right.</span> <span m="3331310">It</span>
  <span m="3331800">doesn''t really</span> <span m="3332290">decay</span> <span m="3332780">at
  all.</span> <span m="3333270">But</span> <span m="3333760">[INAUDIBLE]</span> <span
  m="3334250">a little</span> <span m="3334740">bit.</span></p><p><span m="3342090">[INAUDIBLE]</span>
  <span m="3342580">if</span> <span m="3343080">the</span> <span m="3343320">maximum</span>
  <span m="3343813">occasionally</span> <span m="3344306">gets</span> <span m="3344799">greater</span>
  <span m="3345292">than</span> <span m="3345785">1,</span> <span m="3346278">it</span>
  <span m="3346771">still</span> <span m="3347264">shifts</span> <span m="3349730">down</span>
  <span m="3349960">a</span> <span m="3350020">little</span> <span m="3350280">bit.</span>
  <span m="3351726">All</span> <span m="3352140">right.</span> <span m="3353610">Any</span>
  <span m="3353780">questions</span> <span m="3355380">on</span> <span m="3355530">the</span>
  <span m="3355600">matrix</span> <span m="3356020">form</span> <span m="3356320">of</span>
  <span m="3356480">these</span> <span m="3356730">two</span> <span m="3358511">final</span>
  <span m="3358950">difference</span> <span m="3359330">operators?</span> <span m="3364620">No?</span>
  <span m="3364820">Whenever</span> <span m="3365230">you</span> <span m="3365390">need</span>
  <span m="3365710">them,</span> <span m="3366270">I''m</span> <span m="3366720">basically</span>
  <span m="3367090">constructing</span> <span m="3368700">a final</span> <span m="3369200">difference</span>
  <span m="3369610">operator</span> <span m="3370270">just</span> <span m="3370570">like</span>
  <span m="3370620">a</span> <span m="3371400">mathematical</span> <span m="3372390">operator,</span>
  <span m="3373010">just</span> <span m="3373260">like</span> <span m="3373480">ddx.</span>
  <span m="3376480">And</span> <span m="3377280">when</span> <span m="3377480">I</span>
  <span m="3377550">need</span> <span m="3377810">it,</span> <span m="3378040">I</span>
  <span m="3378570">can</span> <span m="3378870">just</span> <span m="3379050">apply</span>
  <span m="3379450">it.</span></p><p><span m="3384800">The</span> <span m="3384970">interesting</span>
  <span m="3385390">thing</span> <span m="3385640">is</span> <span m="3385840">that</span>
  <span m="3386690">the</span> <span m="3386940">operator</span> <span m="3387480">I</span>
  <span m="3387620">have</span> <span m="3388980">already</span> <span m="3390060">contains</span>
  <span m="3391300">the</span> <span m="3391410">boundary</span> <span m="3391760">condition.</span>
  <span m="3395960">The</span> <span m="3396320">operator</span> <span m="3396760">I</span>
  <span m="3396920">have</span> <span m="3397520">here,</span> <span m="3398205">the</span>
  <span m="3398490">periodic</span> <span m="3398840">boundary</span> <span m="3399155">condition</span>
  <span m="3400330">is</span> <span m="3400890">encoding</span> <span m="3402420">into</span>
  <span m="3402840">the</span> <span m="3403660">operator</span> <span m="3404090">[INAUDIBLE].</span>
  <span m="3407120">If</span> <span m="3407310">I</span> <span m="3407430">didn''t</span>
  <span m="3407750">have</span> <span m="3407950">periodic</span> <span m="3408405">boundary</span>
  <span m="3408860">condition,</span> <span m="3409770">would I</span> <span m="3409950">still
  have</span> <span m="3410200">this?</span> <span m="3411830">No.</span> <span m="3413510">I</span>
  <span m="3413610">wouldn''t</span> <span m="3413880">be</span> <span m="3414030">able</span>
  <span m="3414250">to</span> <span m="3414410">say,</span> <span m="3415080">if</span>
  <span m="3415220">I</span> <span m="3415340">want</span> <span m="3415560">to--</span>
  <span m="3416580">I</span> <span m="3416650">wouldn''t</span> <span m="3416720">be</span>
  <span m="3416950">able to</span> <span m="3417070">say</span> <span m="3417240">if</span>
  <span m="3417731">I only</span> <span m="3418222">graph</span> <span m="3419204">the</span>
  <span m="3419695">solution</span> <span m="3420186">towards</span> <span m="3420677">the</span>
  <span m="3421168">left,</span> <span m="3421660">I</span> <span m="3421720">just
  need to grab</span> <span m="3422177">the one</span> <span m="3423548">at</span>
  <span m="3424005">the</span> <span m="3424462">right</span> <span m="3424919">hand.</span>
  <span m="3425376">I</span> <span m="3425840">wouldn''t</span> <span m="3426090">be</span>
  <span m="3426566">able to say</span> <span m="3427042">that.</span></p><p><span
  m="3427994">So</span> <span m="3428470">what if</span> <span m="3428770">we--</span>
  <span m="3428910">let''s</span> <span m="3429310">say</span> <span m="3430070">we</span>
  <span m="3430250">have</span> <span m="3430460">a</span> <span m="3430560">boundary</span>
  <span m="3430960">condition</span> <span m="3431453">at</span> <span m="3431946">the</span>
  <span m="3432440">left,</span> <span m="3432640">but</span> <span m="3432740">if</span>
  <span m="3432890">it</span> <span m="3433040">is not</span> <span m="3433450">periodic,</span>
  <span m="3434195">what</span> <span m="3434460">if</span> <span m="3434890">we</span>
  <span m="3435110">have</span> <span m="3435310">a</span> <span m="3435370">boundary</span>
  <span m="3435822">condition</span> <span m="3436274">that</span> <span m="3436726">says</span>
  <span m="3437180">u</span> <span m="3437580">at</span> <span m="3438047">0</span>
  <span m="3438981">equal to 1?</span> <span m="3439450">OK.</span> <span m="3439860">So</span>
  <span m="3439980">let''s</span> <span m="3440260">see.</span> <span m="3442440">U</span>
  <span m="3443604">at</span> <span m="3444390">x</span> <span m="3444830">equal</span>
  <span m="3445130">to</span> <span m="3445360">0</span> <span m="3445690">at</span>
  <span m="3446020">net</span> <span m="3446850">equal</span> <span m="3447290">to</span>
  <span m="3447768">1.</span> <span m="3450640">This</span> <span m="3450830">is</span>
  <span m="3450990">consistent</span> <span m="3451750">with</span> <span m="3453096">our</span>
  <span m="3453770">matching</span> <span m="3454160">question,</span> <span m="3454490">because</span>
  <span m="3454800">in</span> <span m="3455220">this</span> <span m="3455330">matching</span>
  <span m="3455510">equation,</span> <span m="3456310">the</span> <span m="3456450">characteristics</span>
  <span m="3457340">move</span> <span m="3457720">towards</span> <span m="3458070">the</span>
  <span m="3458190">right.</span></p><p><span m="3459500">So</span> <span m="3459650">if</span>
  <span m="3459770">you</span> <span m="3459860">didn''t</span> <span m="3460240">have</span>
  <span m="3460760">periodic</span> <span m="3460930">boundary</span> <span m="3461360">condition,</span>
  <span m="3462430">you</span> <span m="3462600">need</span> <span m="3462770">to</span>
  <span m="3463170">specify</span> <span m="3464050">the</span> <span m="3464160">solution.</span>
  <span m="3465280">You</span> <span m="3465410">need</span> <span m="3465550">to</span>
  <span m="3465680">specify</span> <span m="3466200">the</span> <span m="3466330">solution</span>
  <span m="3466940">also</span> <span m="3467570">here</span> <span m="3468550">and</span>
  <span m="3469000">here,</span> <span m="3469560">right?</span> <span m="3470090">You</span>
  <span m="3470220">need</span> <span m="3470370">to</span> <span m="3470470">specify</span>
  <span m="3470930">the</span> <span m="3471620">solution</span> <span m="3472090">where</span>
  <span m="3472700">the</span> <span m="3472860">characteristics</span> <span m="3474290">originate.</span>
  <span m="3476290">Because</span> <span m="3476790">if</span> <span m="3477290">I''m</span>
  <span m="3477790">here,</span> <span m="3478290">I</span> <span m="3478790">have
  the initial</span> <span m="3479290">condition that</span> <span m="3479755">p is
  equal</span> <span m="3480220">to 0.</span> <span m="3481150">You</span> <span m="3481400">also</span>
  <span m="3481620">need</span> <span m="3482058">to</span> <span m="3482496">specify</span>
  <span m="3482934">those</span> <span m="3483372">conditions</span> <span m="3483810">here,</span>
  <span m="3484690">either</span> <span m="3485310">boundary</span> <span m="3485650">conditions.</span>
  <span m="3486108">That is when</span> <span m="3486566">x</span> <span m="3487024">is</span>
  <span m="3487482">equal</span> <span m="3487940">to</span> <span m="3488398">0</span>
  <span m="3489780">or</span> <span m="3490070">x is at the</span> <span m="3490506">left</span>
  <span m="3490942">end</span> <span m="3491378">of the</span> <span m="3491814">domain,</span>
  <span m="3492250">[INAUDIBLE]</span> <span m="3492980">equal</span> <span m="3493437">to</span>
  <span m="3493894">0.</span></p><p><span m="3497190">So</span> <span m="3497370">this</span>
  <span m="3497710">is</span> <span m="3499770">the</span> <span m="3499920">left</span>
  <span m="3500510">boundary</span> <span m="3500740">condition.</span> <span m="3504273">All
  right?</span> <span m="3505260">OK.</span> <span m="3507230">In</span> <span m="3507420">that</span>
  <span m="3507590">case,</span> <span m="3507940">how</span> <span m="3508130">do</span>
  <span m="3508230">we</span> <span m="3508360">deal</span> <span m="3508590">with</span>
  <span m="3508760">that?</span> <span m="3510880">How</span> <span m="3510980">do</span>
  <span m="3511160">we</span> <span m="3511400">encode</span> <span m="3511980">that</span>
  <span m="3512300">boundary</span> <span m="3512600">condition</span> <span m="3513410">into
  the</span> <span m="3513900">matrix,</span> <span m="3514540">into</span> <span
  m="3514810">the</span> <span m="3515670">matrix</span> <span m="3516130">form</span>
  <span m="3516500">of</span> <span m="3517098">finite</span> <span m="3517566">difference.</span>
  <span m="3519910">Let''s</span> <span m="3520070">look</span> <span m="3520320">at</span>
  <span m="3520811">this.</span> <span m="3523540">Let''s</span> <span m="3524380">take</span>
  <span m="3524610">a</span> <span m="3524660">look</span> <span m="3524870">at</span>
  <span m="3524960">the</span> <span m="3525030">matrix.</span></p><p><span m="3526120">And</span>
  <span m="3526910">the</span> <span m="3527130">only</span> <span m="3527470">thing</span>
  <span m="3527710">we</span> <span m="3527830">need</span> <span m="3527990">to</span>
  <span m="3528120">change</span> <span m="3529950">is</span> <span m="3531320">which</span>
  <span m="3531600">one?</span> <span m="3532000">Which</span> <span m="3532220">row</span>
  <span m="3532490">of</span> <span m="3532760">the</span> <span m="3533130">matrix</span>
  <span m="3533610">do we</span> <span m="3534090">need to</span> <span m="3534570">change?</span>
  <span m="3535050">If we</span> <span m="3535530">need to</span> <span m="3536010">change
  one</span> <span m="3536490">at all.</span> <span m="3537930">We</span> <span m="3538180">only</span>
  <span m="3538520">need to change</span> <span m="3538905">the first</span> <span
  m="3539290">row,</span> <span m="3539640">right?</span> <span m="3540040">Because</span>
  <span m="3540440">all</span> <span m="3540840">the</span> <span m="3541120">other</span>
  <span m="3541270">rows</span> <span m="3541560">of</span> <span m="3541880">the</span>
  <span m="3542273">matrix</span> <span m="3542666">are</span> <span m="3543060">still</span>
  <span m="3543320">exactly</span> <span m="3543800">the</span> <span m="3543920">same</span>
  <span m="3544260">because</span> <span m="3544590">they</span> <span m="3544700">are</span>
  <span m="3544960">the interior.</span> <span m="3546150">Only</span> <span m="3546490">the</span>
  <span m="3546580">first</span> <span m="3546950">row</span> <span m="3547710">involves</span>
  <span m="3548140">the</span> <span m="3548230">boundary.</span></p><p><span m="3548860">So</span>
  <span m="3549050">let''s</span> <span m="3549290">look</span> <span m="3549500">at</span>
  <span m="3549570">the</span> <span m="3549640">first</span> <span m="3549910">row.</span>
  <span m="3552170">The</span> <span m="3552200">first</span> <span m="3552510">row</span>
  <span m="3552770">has</span> <span m="3553250">partial</span> <span m="3553520">u,</span>
  <span m="3553790">partial</span> <span m="3554850">x</span> <span m="3555420">at</span>
  <span m="3556290">r</span> <span m="3556620">equal</span> <span m="3557040">to</span>
  <span m="3557120">1</span> <span m="3557490">at</span> <span m="3557860">n</span>
  <span m="3558160">[INAUDIBLE].</span> <span m="3560430">Originally,</span> <span
  m="3561180">it</span> <span m="3561350">is</span> <span m="3561590">equal</span>
  <span m="3561920">to</span> <span m="3562020">u</span> <span m="3562590">of</span>
  <span m="3563220">i</span> <span m="3563530">minus</span> <span m="3563930">1,</span>
  <span m="3564180">which</span> <span m="3564430">is</span> <span m="3564620">in</span>
  <span m="3564750">this</span> <span m="3564900">case</span> <span m="3565100">is</span>
  <span m="3565250">0</span> <span m="3566770">minus</span> <span m="3567250">u1</span>
  <span m="3568060">divided</span> <span m="3568380">by</span> <span m="3568560">delta</span>
  <span m="3568820">x.</span></p><p><span m="3569620">This</span> <span m="3569870">is</span>
  <span m="3570000">my</span> <span m="3570230">backward--</span> <span m="3573255">again,</span>
  <span m="3576710">this</span> <span m="3577050">is</span> <span m="3577170">my</span>
  <span m="3577380">backward</span> <span m="3578680">in</span> <span m="3579030">space.</span>
  <span m="3581220">This--</span> <span m="3585234">yeah.</span> <span m="3585702">It''s</span>
  <span m="3586640">the</span> <span m="3586790">other</span> <span m="3586990">way</span>
  <span m="3587130">around.</span> <span m="3587490">Thank</span> <span m="3587720">you.</span>
  <span m="3588310">It</span> <span m="3588460">is</span> <span m="3588610">u1</span>
  <span m="3588730">minus</span> <span m="3589890">u0.</span> <span m="3590790">Yes.</span></p><p><span
  m="3596800">OK.</span> <span m="3597330">In</span> <span m="3597490">the</span>
  <span m="3597950">previous</span> <span m="3598260">[INAUDIBLE]</span> <span m="3598750">we</span>
  <span m="3599240">said</span> <span m="3599730">the</span> <span m="3600220">domain
  is</span> <span m="3600520">periodic.</span> <span m="3600880">So</span> <span m="3601290">0</span>
  <span m="3601750">is</span> <span m="3602070">just</span> <span m="3602390">U n,</span>
  <span m="3602760">right?</span> <span m="3603512">So</span> <span m="3604040">what</span>
  <span m="3604260">this</span> <span m="3604440">is</span> <span m="3604780">is</span>
  <span m="3605120">that</span> <span m="3605380">we</span> <span m="3606710">have</span>
  <span m="3606965">a</span> <span m="3607220">boundary</span> <span m="3607570">condition</span>
  <span m="3608010">that</span> <span m="3608450">is given</span> <span m="3608800">to
  us.</span> <span m="3610600">You</span> <span m="3610850">know</span> <span m="3611330">what</span>
  <span m="3611530">exactly</span> <span m="3611986">U0</span> <span m="3612442">is.</span>
  <span m="3614270">We</span> <span m="3614430">know</span> <span m="3614780">that</span>
  <span m="3615020">your</span> <span m="3615210">0</span> <span m="3615780">is</span>
  <span m="3616270">equal</span> <span m="3616700">to</span> <span m="3617890">1.</span>
  <span m="3620280">Then</span> <span m="3621480">the</span> <span m="3621640">derivative</span>
  <span m="3622250">is</span> <span m="3622430">u1</span> <span m="3622846">over</span>
  <span m="3623262">delta</span> <span m="3623920">x</span> <span m="3624350">minus</span>
  <span m="3625770">1</span> <span m="3626060">over</span> <span m="3626140">delta</span>
  <span m="3626200">x.</span></p><p><span m="3629840">We</span> <span m="3630020">have</span>
  <span m="3630270">a</span> <span m="3630360">term</span> <span m="3630820">that</span>
  <span m="3631890">doesn''t</span> <span m="3632750">depend</span> <span m="3633160">linearly</span>
  <span m="3633880">on</span> <span m="3634100">the</span> <span m="3634190">solution.</span>
  <span m="3637420">Or,</span> <span m="3638850">if</span> <span m="3639070">you</span>
  <span m="3639220">look</span> <span m="3639470">at</span> <span m="3639550">the</span>
  <span m="3639620">matrix</span> <span m="3640040">form,</span> <span m="3642140">we</span>
  <span m="3642843">have</span> <span m="3643256">multiple</span> <span m="3643670">conditions</span>
  <span m="3645030">all</span> <span m="3645200">the</span> <span m="3645310">way.</span>
  <span m="3646130">We</span> <span m="3646280">don''t</span> <span m="3646750">have</span>
  <span m="3647060">this.</span> <span m="3647680">But</span> <span m="3647830">in</span>
  <span m="3647910">addition</span> <span m="3648370">to</span> <span m="3648430">the</span>
  <span m="3648490">matrix,</span> <span m="3648920">we</span> <span m="3649080">have</span>
  <span m="3649425">something else.</span> <span m="3652750">Obviously,</span> <span
  m="3653250">we</span> <span m="3653520">have</span> <span m="3654180">a</span> <span
  m="3654590">negative</span> <span m="3654950">of</span> <span m="3655310">1</span>
  <span m="3655490">over</span> <span m="3655810">delta</span> <span m="3655910">x</span>
  <span m="3656780">sitting</span> <span m="3656950">over</span> <span m="3657360">here</span>
  <span m="3658530">as</span> <span m="3659150">an</span> <span m="3659360">additional</span>
  <span m="3660130">vector</span> <span m="3660830">to</span> <span m="3660990">this</span>
  <span m="3663510">matrix.</span></p><p><span m="3664870">Let</span> <span m="3665520">me</span>
  <span m="3665680">make</span> <span m="3666000">a</span> <span m="3666090">new</span>
  <span m="3666320">page.</span> <span m="3671830">OK.</span> <span m="3672130">I''m</span>
  <span m="3672320">going</span> <span m="3672460">to</span> <span m="3672540">draw</span>
  <span m="3672760">what</span> <span m="3673000">the</span> <span m="3673070">matrix</span>
  <span m="3673560">is</span> <span m="3673730">going</span> <span m="3673880">to</span>
  <span m="3673940">look</span> <span m="3674170">like.</span> <span m="3676020">When</span>
  <span m="3676320">we</span> <span m="3676500">have</span> <span m="3676870">a</span>
  <span m="3676940">boundary</span> <span m="3677270">condition,</span> <span m="3678830">like</span>
  <span m="3679670">partial</span> <span m="3680150">u,</span> <span m="3680510">partial</span>
  <span m="3680700">x</span> <span m="3680840">at</span> <span m="3681270">1,</span>
  <span m="3682030">partial</span> <span m="3682440">u,</span> <span m="3682800">partial</span>
  <span m="3683236">x</span> <span m="3683672">at</span> <span m="3684108">2,</span>
  <span m="3685420">partial</span> <span m="3685580">u,</span> <span m="3685770">partial</span>
  <span m="3686230">x</span> <span m="3686915">at</span> <span m="3687270">n</span>
  <span m="3690490">is</span> <span m="3690850">equal</span> <span m="3691320">to</span>
  <span m="3692680">a</span> <span m="3693050">similar</span> <span m="3693510">matrix</span>
  <span m="3698670">at</span> <span m="3699170">minus</span> <span m="3699630">delta</span>
  <span m="3699840">x</span> <span m="3700370">on</span> <span m="3700570">the</span>
  <span m="3700630">sun</span> <span m="3700890">diagonal.</span></p><p><span m="3704888">I</span>
  <span m="3705372">want to</span> <span m="3705950">leave</span> <span m="3706180">enough</span>
  <span m="3706500">space</span> <span m="3706890">for</span> <span m="3707080">the</span>
  <span m="3707160">vector</span> <span m="3707580">ends</span> <span m="3707790">on</span>
  <span m="3707870">the</span> <span m="3707960">right.</span> <span m="3709650">My</span>
  <span m="3709880">u1--</span> <span m="3711190">I''ll</span> <span m="3711540">think
  I''ll</span> <span m="3711800">use</span> <span m="3712060">the</span> <span m="3712280">big</span>
  <span m="3712685">U</span> <span m="3713090">for</span> <span m="3713180">the</span>
  <span m="3713270">first</span> <span m="3713768">U</span> <span m="3714266">n.</span>
  <span m="3716760">This</span> <span m="3717000">is</span> <span m="3717090">the</span>
  <span m="3717440">big</span> <span m="3717610">U</span> <span m="3721110">plus</span>
  <span m="3723020">something</span> <span m="3723540">else.</span> <span m="3724510">And</span>
  <span m="3724740">that</span> <span m="3724970">something</span> <span m="3725360">else</span>
  <span m="3726310">is</span> <span m="3726640">going</span> <span m="3726800">to</span>
  <span m="3726870">be</span> <span m="3726990">0</span> <span m="3727370">almost</span>
  <span m="3727950">everywhere</span> <span m="3729750">except</span> <span m="3730270">for</span>
  <span m="3730540">the</span> <span m="3730620">first</span> <span m="3731080">row,</span>
  <span m="3731550">which</span> <span m="3731660">is</span> <span m="3731770">minus</span>
  <span m="3732820">1</span> <span m="3733090">over</span> <span m="3733180">delta</span>
  <span m="3733470">x.</span> <span m="3734790">And</span> <span m="3735170">it is</span>
  <span m="3735520">going</span> <span m="3735660">to</span> <span m="3735720">be</span>
  <span m="3735860">the</span> <span m="3735970">0</span> <span m="3736840">everywhere</span>
  <span m="3737340">because</span> <span m="3737840">I don''t</span> <span m="3738340">need</span>
  <span m="3738840">to</span> <span m="3739340">modify</span> <span m="3739840">anything.</span></p><p><span
  m="3744480">How</span> <span m="3744670">id</span> <span m="3744780">I</span> <span
  m="3745170">achieve</span> <span m="3745330">this?</span> <span m="3746700">I</span>
  <span m="3746910">plucked</span> <span m="3747840">the</span> <span m="3747980">boundary</span>
  <span m="3748420">condition</span> <span m="3749000">into</span> <span m="3750250">the</span>
  <span m="3750530">finite</span> <span m="3750920">difference</span> <span m="3751490">formula</span>
  <span m="3753560">at</span> <span m="3753940">the</span> <span m="3754150">grid</span>
  <span m="3754390">point</span> <span m="3754750">that</span> <span m="3754900">is</span>
  <span m="3755040">close</span> <span m="3755680">to</span> <span m="3755810">the</span>
  <span m="3755890">boundary.</span> <span m="3757651">All</span> <span m="3758150">right?</span>
  <span m="3758490">That is</span> <span m="3758785">a</span> <span m="3759080">general</span>
  <span m="3759556">technique</span> <span m="3760032">of</span> <span m="3760510">locking</span>
  <span m="3761050">in</span> <span m="3761760">the</span> <span m="3761890">value</span>
  <span m="3762400">of</span> <span m="3762530">the</span> <span m="3762600">boundary</span>
  <span m="3762890">condition</span> <span m="3763540">into</span> <span m="3763800">the</span>
  <span m="3765060">[INAUDIBLE]</span> <span m="3765560">difference</span> <span m="3766060">here.</span></p><p><span
  m="3771140">So</span> <span m="3771320">let''s</span> <span m="3772210">modify</span>
  <span m="3772810">what</span> <span m="3773030">we</span> <span m="3773180">did</span>
  <span m="3774580">under</span> <span m="3774870">here.</span> <span m="3775870">So</span>
  <span m="3776370">let''s</span> <span m="3780660">copy</span> <span m="3781070">this.</span>
  <span m="3782400">I</span> <span m="3782500">think</span> <span m="3783120">I</span>
  <span m="3783210">should</span> <span m="3783510">rename</span> <span m="3784040">this</span>
  <span m="3785252">as</span> <span m="3785720">backward</span> <span m="3786720">because</span>
  <span m="3787830">this</span> <span m="3788050">is</span> <span m="3788320">backwards.</span>
  <span m="3790440">And</span> <span m="3790810">I''m</span> <span m="3790970">going</span>
  <span m="3791150">to</span> <span m="3791220">do</span> <span m="3791950">probably</span>
  <span m="3793380">another</span> <span m="3793730">one</span> <span m="3795210">and</span>
  <span m="3795430">say</span> <span m="3795550">boundary</span> <span m="3795860">condition</span>
  <span m="3797340">backwards</span> <span m="3797625">space</span> <span m="3799558">forward</span>
  <span m="3799970">time.</span> <span m="3801670">That''s</span> <span m="3802080">correct.</span></p><p><span
  m="3803310">So</span> <span m="3803460">what</span> <span m="3803850">do</span>
  <span m="3804090">I</span> <span m="3804180">need</span> <span m="3804350">to</span>
  <span m="3804440">do?</span> <span m="3804780">I</span> <span m="3804900">need</span>
  <span m="3805100">to</span> <span m="3805210">change--</span> <span m="3807490">oh,</span>
  <span m="3807950">OK.</span> <span m="3808640">I</span> <span m="3808770">need</span>
  <span m="3808960">to</span> <span m="3809070">change</span> <span m="3809630">the</span>
  <span m="3809920">operator.</span> <span m="3811380">I</span> <span m="3811510">need</span>
  <span m="3811690">to</span> <span m="3811810">change</span> <span m="3812270">the</span>
  <span m="3812430">operator</span> <span m="3813550">to</span> <span m="3814030">include</span>
  <span m="3815325">the</span> <span m="3815720">boundary</span> <span m="3815820">condition.</span>
  <span m="3818030">How</span> <span m="3818190">do</span> <span m="3818290">I</span>
  <span m="3818370">do</span> <span m="3818560">that?</span> <span m="3820460">If</span>
  <span m="3820650">you</span> <span m="3820740">look</span> <span m="3821120">at</span>
  <span m="3821390">what</span> <span m="3821530">the</span> <span m="3821590">matrix</span>
  <span m="3821980">is</span> <span m="3822160">like,</span> <span m="3822810">I</span>
  <span m="3822920">still</span> <span m="3823320">have</span> <span m="3823640">the</span>
  <span m="3823790">diagonal</span> <span m="3824080">term</span> <span m="3824300">to</span>
  <span m="3824600">be</span> <span m="3824780">exactly</span> <span m="3825000">the</span>
  <span m="3825210">same.</span> <span m="3826310">I</span> <span m="3826450">still</span>
  <span m="3826790">have</span> <span m="3827010">my</span> <span m="3827230">identity</span>
  <span m="3827910">of</span> <span m="3828215">n</span> <span m="3828860">divided</span>
  <span m="3829130">by</span> <span m="3829320">delta</span> <span m="3829350">x.</span></p><p><span
  m="3830590">So</span> <span m="3833430">that</span> <span m="3833660">is</span>
  <span m="3833860">this</span> <span m="3834310">part.</span> <span m="3836560">Now,</span>
  <span m="3837060">I</span> <span m="3837260">also</span> <span m="3837720">have</span>
  <span m="3838330">my</span> <span m="3838640">rare</span> <span m="3839030">part,</span>
  <span m="3839800">which</span> <span m="3840070">is</span> <span m="3840240">not</span>
  <span m="3840690">exactly</span> <span m="3841260">a</span> <span m="3841575">circular</span>
  <span m="3842320">shift</span> <span m="3842700">of</span> <span m="3844560">identity</span>
  <span m="3845010">matrix.</span> <span m="3846360">So</span> <span m="3846580">here</span>
  <span m="3846900">I''m</span> <span m="3847170">going</span> <span m="3847290">to</span>
  <span m="3847400">use</span> <span m="3847880">the</span> <span m="3848570">function</span>
  <span m="3848950">code</span> <span m="3849365">diag.</span> <span m="3852390">Diag,</span>
  <span m="3855320">it''s</span> <span m="3855470">a</span> <span m="3855520">function</span>
  <span m="3855960">that</span> <span m="3856630">you</span> <span m="3856820">need</span>
  <span m="3856980">to</span> <span m="3857150">give</span> <span m="3857370">to me.</span>
  <span m="3858710">What</span> <span m="3859040">are</span> <span m="3859150">the</span>
  <span m="3859280">elements</span> <span m="3859840">of</span> <span m="3859940">a</span>
  <span m="3860200">diagonal</span> <span m="3861430">and</span> <span m="3861840">how</span>
  <span m="3862311">much</span> <span m="3863724">I</span> <span m="3864195">shifted.</span></p><p><span
  m="3865140">If</span> <span m="3865495">a</span> <span m="3865850">is</span> <span
  m="3866210">equal</span> <span m="3866420">to 0,</span> <span m="3866940">then</span>
  <span m="3867430">elements aren''t</span> <span m="3867920">exactly</span> <span
  m="3868340">on</span> <span m="3868550">the</span> <span m="3868630">diagonal.</span>
  <span m="3869626">If</span> <span m="3870124">a is equal</span> <span m="3870622">to</span>
  <span m="3871120">minus</span> <span m="3871618">1</span> <span m="3872116">then
  I get</span> <span m="3872614">exactly</span> <span m="3873112">what I want</span>
  <span m="3873610">because</span> <span m="3874110">it''s minus</span> <span m="3874350">1</span>
  <span m="3874470">shifted</span> <span m="3878880">towards</span> <span m="3879200">the</span>
  <span m="3879270">opposite</span> <span m="3879370">diagonal,</span> <span m="3880322">which</span>
  <span m="3880670">is</span> <span m="3880780">1</span> <span m="3881250">shifted
  towards</span> <span m="3881570">the</span> <span m="3881973">lower diagonal.</span>
  <span m="3882780">So</span> <span m="3882830">the</span> <span m="3882920">elements</span>
  <span m="3883430">would</span> <span m="3883610">be</span> <span m="3885850">once</span>
  <span m="3886730">with</span> <span m="3887100">m</span> <span m="3887375">minus</span>
  <span m="3887650">1</span> <span m="3887920">elements</span> <span m="3890530">divided</span>
  <span m="3890880">by</span> <span m="3891070">delta</span> <span m="3891340">x--</span>
  <span m="3891820">these</span> <span m="3892120">are</span> <span m="3892290">the</span>
  <span m="3892470">values--</span> <span m="3893690">and</span> <span m="3894910">minus</span>
  <span m="3895300">1</span> <span m="3895520">towards</span> <span m="3895550">the</span>
  <span m="3896280">shift.</span></p><p><span m="3897830">OK.</span> <span m="3898670">So</span>
  <span m="3898840">this</span> <span m="3902110">is</span> <span m="3902260">what</span>
  <span m="3902440">the</span> <span m="3902520">matrix</span> <span m="3903020">is</span>
  <span m="3903210">going</span> <span m="3903340">to</span> <span m="3903410">be</span>
  <span m="3903510">like.</span> <span m="3904020">I''m</span> <span m="3904230">going</span>
  <span m="3904430">to</span> <span m="3904590">paste</span> <span m="3905000">it
  here</span> <span m="3906230">and</span> <span m="3906640">take</span> <span m="3906860">a</span>
  <span m="3906910">look</span> <span m="3907160">at</span> <span m="3907240">the</span>
  <span m="3907310">matrix.</span> <span m="3909420">The</span> <span m="3909560">100</span>
  <span m="3909840">by</span> <span m="3910020">100</span> <span m="3910290">double</span>
  <span m="3911240">on</span> <span m="3911730">the</span> <span m="3912220">diagonal</span>
  <span m="3912710">[INAUDIBLE].</span> <span m="3916630">I get</span> <span m="3917030">what</span>
  <span m="3917210">I</span> <span m="3917320">want,</span> <span m="3918220">and</span>
  <span m="3918530">I</span> <span m="3918600">also</span> <span m="3918980">don''t</span>
  <span m="3919360">have</span> <span m="3920160">this--</span> <span m="3923520">I
  don''t</span> <span m="3924000">have</span> <span m="3924480">a</span> <span m="3924960">minus</span>
  <span m="3925440">100</span> <span m="3925920">over</span> <span m="3926400">here</span>
  <span m="3929080">in</span> <span m="3929640">the</span> <span m="3929740">periodic</span>
  <span m="3930300">case.</span></p><p><span m="3934090">Now,</span> <span m="3934320">let''s</span>
  <span m="3934510">run</span> <span m="3934750">it</span> <span m="3934920">to</span>
  <span m="3935040">see</span> <span m="3935210">what</span> <span m="3935480">we</span>
  <span m="3935630">have.</span> <span m="3938050">OK.</span> <span m="3938570">We</span>
  <span m="3947950">still</span> <span m="3948040">see</span> <span m="3948170">these</span>
  <span m="3948510">things</span> <span m="3948893">going</span> <span m="3949276">over
  here.</span> <span m="3949660">What</span> <span m="3949880">happens</span> <span
  m="3950090">on</span> <span m="3950572">my</span> <span m="3951054">left?</span>
  <span m="3952500">Oh,</span> <span m="3952990">OK.</span> <span m="3954920">Did</span>
  <span m="3955050">I</span> <span m="3955140">forget</span> <span m="3955470">something?</span>
  <span m="3958320">I</span> <span m="3958340">forgot</span> <span m="3958560">the</span>
  <span m="3958730">boundary</span> <span m="3958830">condition.</span> <span m="3959980">So</span>
  <span m="3960280">I</span> <span m="3960580">forgot</span> <span m="3960900">to</span>
  <span m="3961220">add</span> <span m="3961950">the</span> <span m="3962390">vector</span>
  <span m="3963070">v</span> <span m="3963515">when</span> <span m="3963960">I applied</span>
  <span m="3964405">this</span> <span m="3964850">derivative.</span> <span m="3965740">The</span>
  <span m="3965910">end</span> <span m="3966265">result</span> <span m="3966620">here</span>
  <span m="3966790">is</span> <span m="3966930">I</span> <span m="3967150">have</span>
  <span m="3967523">a</span> <span m="3967896">boundary</span> <span m="3968270">condition</span>
  <span m="3968610">of</span> <span m="3968885">0</span> <span m="3969160">here.</span></p><p><span
  m="3970660">I''m</span> <span m="3971660">setting</span> <span m="3972160">the</span>
  <span m="3972660">boundary</span> <span m="3973160">condition</span> <span m="3973660">to</span>
  <span m="3974160">be</span> <span m="3974430">0.</span> <span m="3975115">[INAUDIBLE].</span>
  <span m="3976570">As</span> <span m="3976790">this</span> <span m="3977060">thing</span>
  <span m="3977330">advances</span> <span m="3977740">towards</span> <span m="3977850">the</span>
  <span m="3978120">right,</span> <span m="3978530">it''s</span> <span m="3978970">going
  to</span> <span m="3979410">be</span> <span m="3979730">no longer</span> <span m="3979800">[INAUDIBLE]</span>
  <span m="3980210">towards</span> <span m="3980620">the</span> <span m="3981030">left.</span>
  <span m="3981850">So</span> <span m="3982780">yeah.</span> <span m="3983815">So</span>
  <span m="3985120">I</span> <span m="3985240">did forget</span> <span m="3985410">something.</span>
  <span m="3985720">But</span> <span m="3986930">we</span> <span m="3987070">still</span>
  <span m="3987480">have</span> <span m="3987810">such</span> <span m="3988090">a</span>
  <span m="3988250">boundary</span> <span m="3988380">condition</span> <span m="3988520">that</span>
  <span m="3988880">is</span> <span m="3989240">not</span> <span m="3989935">periodic.</span>
  <span m="3991660">Because</span> <span m="3992045">you see</span> <span m="3992430">this</span>
  <span m="3992890">[INAUDIBLE]</span> <span m="3993296">go out,</span> <span m="3993702">I''m
  still going</span> <span m="3994110">to</span> <span m="3994350">have</span> <span
  m="3994915">0</span> <span m="3995330">here.</span></p><p><span m="3996880">OK.</span>
  <span m="3997260">So</span> <span m="3997390">let''s</span> <span m="3997720">add</span>
  <span m="3998100">to the</span> <span m="3998240">b.</span> <span m="4000958">My</span>
  <span m="4001411">b_ddx</span> <span m="4003640">is</span> <span m="4003990">going</span>
  <span m="4004130">to</span> <span m="4004220">be</span> <span m="4004620">0n1.</span>
  <span m="4007850">And</span> <span m="4008280">my</span> <span m="4008510">b_ddx,</span>
  <span m="4009900">the</span> <span m="4010130">first</span> <span m="4010380">element</span>
  <span m="4010710">is</span> <span m="4011040">going</span> <span m="4011190">to
  be</span> <span m="4011290">1</span> <span m="4011650">minus</span> <span m="4011870">delta</span>
  <span m="4012357">x.</span> <span m="4014305">Minus.</span> <span m="4015766">All
  right.</span> <span m="4016260">When</span> <span m="4016500">I</span> <span m="4016600">apply</span>
  <span m="4017030">it</span> <span m="4017355">ddx</span> <span m="4017680">is this</span>
  <span m="4018110">plus</span> <span m="4018600">[INAUDIBLE].</span> <span m="4020940">Yeah.</span>
  <span m="4021230">This</span> <span m="4021460">is</span> <span m="4021650">still
  going</span> <span m="4021880">towards</span> <span m="4022090">the</span> <span
  m="4022270">right,</span> <span m="4022870">and</span> <span m="4022990">it</span>
  <span m="4023090">doesn''t</span> <span m="4023350">come</span> <span m="4023550">back</span>
  <span m="4024006">from</span> <span m="4024462">the</span> <span m="4024920">left.</span></p><p><span
  m="4024960">So now</span> <span m="4025270">let''s</span> <span m="4026840">look</span>
  <span m="4027160">at</span> <span m="4027440">what</span> <span m="4027690">if</span>
  <span m="4027940">we</span> <span m="4028100">do</span> <span m="4028350">have</span>
  <span m="4028520">a</span> <span m="4028570">non-trivial</span> <span m="4029140">boundary</span>
  <span m="4029470">condition.</span> <span m="4032285">Why?</span> <span m="4033752">What</span>
  <span m="4034241">happens?</span> <span m="4040110">Ah,</span> <span m="4040890">undefine</span>
  <span m="4041325">the</span> <span m="4042015">functional</span> <span m="4042270">variable,</span>
  <span m="4043056">b_ddx.</span> <span m="4045380">All right.</span> <span m="4045760">I''m</span>
  <span m="4046110">going to</span> <span m="4046280">round</span> <span m="4046666">it.</span>
  <span m="4047440">All</span> <span m="4047620">right.</span> <span m="4050035">So</span>
  <span m="4050520">we</span> <span m="4050680">have</span> <span m="4051000">a</span>
  <span m="4051220">boundary</span> <span m="4051635">condition</span> <span m="4052050">of</span>
  <span m="4052465">b</span> <span m="4052880">equal</span> <span m="4053090">to</span>
  <span m="4053563">1</span> <span m="4054036">over</span> <span m="4054509">here</span>
  <span m="4054982">as you can</span> <span m="4055455">see.</span> <span m="4056401">This</span>
  <span m="4056880">is</span> <span m="4057270">the</span> <span m="4057400">behavior</span>
  <span m="4057900">of</span> <span m="4058400">the</span> <span m="4058900">differential</span>
  <span m="4059400">equation</span> <span m="4059900">[INAUDIBLE]</span> <span m="4060400">so</span>
  <span m="4060900">we''ll</span> <span m="4061400">see</span> <span m="4062400">everything</span>
  <span m="4062760">that</span> <span m="4062900">wraps</span> <span m="4063100">towards</span>
  <span m="4063594">the right.</span></p><p><span m="4064582">And</span> <span m="4066064">[INAUDIBLE]</span>
  <span m="4068040">there</span> <span m="4068534">shouldn''t</span> <span m="4069028">be</span>
  <span m="4069522">a discontinuity</span> <span m="4070016">over</span> <span m="4070510">here,</span>
  <span m="4071004">but the</span> <span m="4071498">[INAUDIBLE]</span> <span m="4071992">actually</span>
  <span m="4072486">moves</span> <span m="4072990">this</span> <span m="4073670">discontinuity</span>
  <span m="4074150">out,</span> <span m="4074824">and</span> <span m="4075288">you</span>
  <span m="4076216">get</span> <span m="4076680">this</span> <span m="4077144">finite</span>
  <span m="4079422">jump</span> <span m="4079894">from</span> <span m="4080366">0
  to</span> <span m="4080838">1</span> <span m="4081310">over here.</span> <span m="4081782">But</span>
  <span m="4082254">you</span> <span m="4082726">still</span> <span m="4083198">the</span>
  <span m="4083670">boundary</span> <span m="4084170">condition</span> <span m="4084590">being</span>
  <span m="4085010">forced</span> <span m="4085290">correctly</span> <span m="4085930">as</span>
  <span m="4086390">things</span> <span m="4086660">do</span> <span m="4086990">move</span>
  <span m="4087310">towards</span> <span m="4087720">the</span> <span m="4087840">right.</span>
  <span m="4089190">All</span> <span m="4089640">right?</span> <span m="4091290">So</span>
  <span m="4091500">the</span> <span m="4091610">right</span> <span m="4091800">way</span>
  <span m="4091940">to</span> <span m="4092640">put</span> <span m="4092840">boundary</span>
  <span m="4093340">conditions,</span> <span m="4095020">one</span> <span m="4095360">right</span>
  <span m="4095580">way</span> <span m="4095720">to</span> <span m="4095820">put</span>
  <span m="4096010">the</span> <span m="4096210">boundary</span> <span m="4096545">conditions</span>
  <span m="4096880">is</span> <span m="4097170">to</span> <span m="4098334">substitute</span>
  <span m="4099300">the</span> <span m="4099470">boundary</span> <span m="4099810">value</span>
  <span m="4100160">into</span> <span m="4100620">the</span> <span m="4101020">differential</span>
  <span m="4101569">operator,</span> <span m="4102080">into</span> <span m="4102359">the</span>
  <span m="4103040">discrete</span> <span m="4103500">highest</span> <span m="4104290">differential</span>
  <span m="4104830">operator</span> <span m="4106240">and</span> <span m="4106960">derive</span>
  <span m="4108580">not</span> <span m="4108779">only</span> <span m="4108939">a</span>
  <span m="4109240">more</span> <span m="4109540">refined</span> <span m="4109830">matrix</span>
  <span m="4110270">form,</span> <span m="4110960">but</span> <span m="4111340">also</span>
  <span m="4111810">a</span> <span m="4112130">vector</span> <span m="4112370">that</span>
  <span m="4112920">added</span> <span m="4113250">on</span> <span m="4113439">to</span>
  <span m="4113910">the</span> <span m="4114200">matrix</span> <span m="4114490">form.</span></p><p><span
  m="4114710">STUDENT: [INAUDIBLE].</span></p><p><span m="4126950">QIQI WANG: OK.</span>
  <span m="4127279">So</span> <span m="4127500">the</span> <span m="4127600">question</span>
  <span m="4127850">is,</span> <span m="4128960">this</span> <span m="4129120">form</span>
  <span m="4129569">o</span> <span m="4129770">the</span> <span m="4129870">boundary</span>
  <span m="4130120">condition</span> <span m="4130649">looks</span> <span m="4131010">like</span>
  <span m="4131670">we</span> <span m="4131930">are</span> <span m="4132100">asking</span>
  <span m="4132810">a</span> <span m="4133229">[INAUDIBLE]</span> <span m="4133929">into</span>
  <span m="4134279">the</span> <span m="4134460">differential</span> <span m="4134800">equation.</span>
  <span m="4136760">And</span> <span m="4137040">you</span> <span m="4137516">are</span>
  <span m="4137992">absolutely</span> <span m="4138468">correct.</span> <span m="4140372">I
  think not only</span> <span m="4140848">in this case, but in</span> <span m="4141330">several</span>
  <span m="4141689">others</span> <span m="4141930">[INAUDIBLE]</span> <span m="4144156">of</span>
  <span m="4144649">laying</span> <span m="4145000">the</span> <span m="4145100">boundary</span>
  <span m="4145210">condition,</span> <span m="4147779">it''s</span> <span m="4148080">essentially</span>
  <span m="4148890">adding</span> <span m="4149319">a</span> <span m="4149479">[INAUDIBLE],</span>
  <span m="4149979">like</span> <span m="4150479">[INAUDIBLE]</span> <span m="4150979">boundary</span>
  <span m="4151479">condition.</span> <span m="4152979">So</span> <span m="4153479">sometimes</span>
  <span m="4153979">[INAUDIBLE]</span> <span m="4154479">the boundary condition</span>
  <span m="4154909">is</span> <span m="4155340">like</span> <span m="4155540">knowing</span>
  <span m="4155760">how</span> <span m="4156019">to</span> <span m="4156279">add</span>
  <span m="4157160">the</span> <span m="4157260">fore</span> <span m="4157545">onto</span>
  <span m="4157830">the</span> <span m="4158020">right-hand</span> <span m="4158510">side</span>
  <span m="4158899">near</span> <span m="4159370">the</span> <span m="4159841">boundary</span>
  <span m="4160312">to--</span> <span m="4161729">so</span> <span m="4161910">that</span>
  <span m="4162290">your</span> <span m="4162490">emergence</span> <span m="4162550">solution</span>
  <span m="4162930">converges</span> <span m="4164020">to</span> <span m="4164170">the</span>
  <span m="4164260">analytical</span> <span m="4164790">solution</span> <span m="4165220">with</span>
  <span m="4165500">that</span> <span m="4165689">boundary</span> <span m="4166148">condition.</span>
  <span m="4168902">All right?</span> <span m="4169361">Did I</span> <span m="4169820">answer</span>
  <span m="4170279">your question?</span> <span m="4170700">Does that?</span></p><p><span
  m="4171191">STUDENT: [INAUDIBLE].</span></p><p><span m="4183479">QIQI WANG: So</span>
  <span m="4184170">the</span> <span m="4184490">graph</span> <span m="4184640">I</span>
  <span m="4184819">have</span> <span m="4185080">is--</span> <span m="4186970">the</span>
  <span m="4187450">graph</span> <span m="4187819">I</span> <span m="4188290">have</span>
  <span m="4188761">is</span> <span m="4189232">not</span> <span m="4189703">with</span>
  <span m="4190174">the</span> <span m="4190645">boundary</span> <span m="4191116">condition
  but due to</span> <span m="4191587">the minor</span> <span m="4192058">difference</span>
  <span m="4192529">here.</span> <span m="4193950">Yeah,</span> <span m="4194160">the</span>
  <span m="4194260">scheme</span> <span m="4194700">is</span> <span m="4194930">on</span>
  <span m="4195230">the--</span> <span m="4195690">gives you a</span> <span m="4196150">truncation</span>
  <span m="4196610">error.</span> <span m="4197070">It</span> <span m="4197530">is
  marked</span> <span m="4197990">on the</span> <span m="4198450">[INAUDIBLE]</span>
  <span m="4200770">derivative</span> <span m="4201340">exactly</span> <span m="4201830">on</span>
  <span m="4202325">that</span> <span m="4202820">truncation</span> <span m="4203810">error.</span>
  <span m="4204305">[INAUDIBLE]</span> <span m="4206270">smooths</span> <span m="4206630">out</span>
  <span m="4206770">any</span> <span m="4206870">discontinuities,</span> <span m="4207750">if</span>
  <span m="4208190">there''s</span> <span m="4208630">computation</span> <span m="4209070">error,</span>
  <span m="4209530">you can</span> <span m="4209950">actually</span> <span m="4210365">see</span>
  <span m="4210780">that a</span> <span m="4211040">truncation</span> <span m="4211300">error</span>
  <span m="4211390">looks</span> <span m="4212320">like</span> <span m="4212812">a</span>
  <span m="4213304">diffusion</span> <span m="4213796">here.</span> <span m="4216260">It</span>
  <span m="4216450">looks</span> <span m="4216700">like</span> <span m="4216840">you''re
  diffusing</span> <span m="4217210">your</span> <span m="4217880">solution</span>
  <span m="4218270">out</span> <span m="4218740">instead</span> <span m="4219190">of</span>
  <span m="4219340">just</span> <span m="4219600">advecting</span> <span m="4219930">it.</span>
  <span m="4221230">And</span> <span m="4222010">the</span> <span m="4222090">behavior</span>
  <span m="4222590">of</span> <span m="4222760">the</span> <span m="4222850">central</span>
  <span m="4223150">difference</span> <span m="4223530">scheme</span> <span m="4223700">is</span>
  <span m="4223860">very</span> <span m="4224140">different.</span></p><p><span m="4230840">All
  right.</span> <span m="4234520">OK.</span> <span m="4236260">I''m</span> <span m="4236520">just</span>
  <span m="4236790">going</span> <span m="4237020">to</span> <span m="4237220">very</span>
  <span m="4237500">quickly</span> <span m="4241000">also</span> <span m="4242450">give
  you</span> <span m="4242940">the</span> <span m="4243010">finite</span> <span m="4243330">difference</span>
  <span m="4243730">form,</span> <span m="4244230">the</span> <span m="4245110">matrix</span>
  <span m="4245590">form</span> <span m="4245820">of</span> <span m="4245950">the</span>
  <span m="4246030">second</span> <span m="4246380">order</span> <span m="4246530">derivative.</span>
  <span m="4248460">The matrix</span> <span m="4248840">form</span> <span m="4249130">of</span>
  <span m="4249280">the</span> <span m="4249380">second</span> <span m="4249770">order</span>
  <span m="4250000">derivative</span> <span m="4250640">is</span> <span m="4251500">if</span>
  <span m="4251660">you</span> <span m="4251790">have</span> <span m="4253240">the</span>
  <span m="4253420">second</span> <span m="4253820">order</span> <span m="4254130">derivative</span>
  <span m="4255060">of</span> <span m="4255290">u</span> <span m="4255590">at</span>
  <span m="4255910">1</span> <span m="4256650">and</span> <span m="4256910">the</span>
  <span m="4256990">second</span> <span m="4257290">order</span> <span m="4257770">derivative</span>
  <span m="4258420">of</span> <span m="4258550">u</span> <span m="4259000">at</span>
  <span m="4259450">n--</span> <span m="4265020">again,</span> <span m="4265540">is</span>
  <span m="4265740">equal</span> <span m="4266140">to</span> <span m="4266340">this</span>
  <span m="4266600">joint</span> <span m="4266900">matrix.</span> <span m="4268470">And</span>
  <span m="4268680">again,</span> <span m="4268990">let''s</span> <span m="4269220">assume</span>
  <span m="4269600">is</span> <span m="4269970">periodic</span> <span m="4270560">boundary</span>
  <span m="4270820">conditions</span> <span m="4271115">so</span> <span m="4271410">that</span>
  <span m="4271530">we</span> <span m="4271660">don''t</span> <span m="4271930">have</span>
  <span m="4272160">to</span> <span m="4272290">worry</span> <span m="4272610">about</span>
  <span m="4272900">the</span> <span m="4273010">boundary</span> <span m="4273430">conditions</span>
  <span m="4273720">for</span> <span m="4273890">now.</span></p><p><span m="4283940">OK.</span>
  <span m="4284270">So</span> <span m="4284440">the</span> <span m="4284550">second</span>
  <span m="4285040">derivative,</span> <span m="4285450">partial</span> <span m="4285860">u,</span>
  <span m="4286800">partial</span> <span m="4287090">square</span> <span m="4287330">u,</span>
  <span m="4287470">partial</span> <span m="4287770">x</span> <span m="4289052">at</span>
  <span m="4289520">i</span> <span m="4289970">is</span> <span m="4290390">equal</span>
  <span m="4290675">to</span> <span m="4291880">three</span> <span m="4292340">terms.</span>
  <span m="4293100">We</span> <span m="4293330">have</span> <span m="4293700">a</span>
  <span m="4294140">u</span> <span m="4294580">of</span> <span m="4295020">i</span>
  <span m="4295110">plus</span> <span m="4295500">1</span> <span m="4297220">over</span>
  <span m="4297580">delta</span> <span m="4297920">x</span> <span m="4298300">squared</span>
  <span m="4299210">minus</span> <span m="4299495">2Ui</span> <span m="4301140">over</span>
  <span m="4301550">delta</span> <span m="4301890">x</span> <span m="4302260">squared</span>
  <span m="4303442">plus</span> <span m="4303840">Ui</span> <span m="4304420">plus</span>
  <span m="4304780">1</span> <span m="4305170">over</span> <span m="4305600">delta</span>
  <span m="4305880">x</span> <span m="4306240">squared,</span> <span m="4306790">right?</span>
  <span m="4307790">[INAUDIBLE]</span> <span m="4313740">the</span> <span m="4313800">same</span>
  <span m="4314100">as</span> <span m="4314599">the</span> <span m="4315098">second
  order</span> <span m="4315597">[INAUDIBLE].</span></p><p><span m="4319090">So</span>
  <span m="4319590">Ui</span> <span m="4320010">plus</span> <span m="4320430">1 minus</span>
  <span m="4320850">2Ui</span> <span m="4321070">plus</span> <span m="4321747">Ui</span>
  <span m="4322521">plus</span> <span m="4322910">1,</span> <span m="4323540">everything</span>
  <span m="4323940">divided</span> <span m="4324340">by</span> <span m="4325786">delta</span>
  <span m="4326268">x</span> <span m="4326750">squared.</span> <span m="4328200">Now</span>
  <span m="4328370">if</span> <span m="4328570">we</span> <span m="4328690">have</span>
  <span m="4329030">periodic</span> <span m="4329170">boundary</span> <span m="4329340">condition,</span>
  <span m="4329720">how</span> <span m="4330140">do</span> <span m="4330350">I</span>
  <span m="4330430">fit</span> <span m="4330670">this</span> <span m="4331180">into</span>
  <span m="4331650">the</span> <span m="4332110">matrix?</span></p><p><span m="4337870">STUDENT:
  [INAUDIBLE].</span></p><p><span m="4347222">QIQI WANG: Sorry?</span></p><p><span
  m="4348158">STUDENT: [INAUDIBLE].</span></p><p><span m="4351910">QIQI WANG: The
  derivative.</span> <span m="4352120">Oh,</span> <span m="4352250">the</span> <span
  m="4352480">derivative.</span> <span m="4352590">Yes.</span> <span m="4353090">Thank</span>
  <span m="4353320">you.</span> <span m="4354680">Yes.</span> <span m="4356840">Yes.</span>
  <span m="4358760">OK.</span> <span m="4364080">All</span> <span m="4364390">of</span>
  <span m="4364470">these</span> <span m="4364962">terms</span> <span m="4365946">going
  to</span> <span m="4366440">that</span> <span m="4366796">matrix.</span> <span m="4367510">So</span>
  <span m="4367660">let''s</span> <span m="4367870">start</span> <span m="4368090">with</span>
  <span m="4368350">the</span> <span m="4368798">diagonals.</span> <span m="4372390">The</span>
  <span m="4372480">diagonals</span> <span m="4372850">are</span> <span m="4373150">all</span>
  <span m="4373660">the</span> <span m="4373780">same.</span> <span m="4374660">They</span>
  <span m="4375100">are</span> <span m="4375540">coefficients</span> <span m="4375955">on
  this</span> <span m="4376370">term.</span> <span m="4376550">This</span> <span m="4376950">term</span>
  <span m="4377080">goes</span> <span m="4377170">into the</span> <span m="4377470">diagonals.</span>
  <span m="4381970">Yeah.</span> <span m="4382730">This</span> <span m="4382940">term</span>
  <span m="4383140">goes</span> <span m="4383340">into</span> <span m="4383790">the</span>
  <span m="4383990">diagonals.</span></p><p><span m="4384976">And</span> <span m="4385470">let
  me color</span> <span m="4385850">that</span> <span m="4386110">by blue.</span>
  <span m="4386370">This</span> <span m="4386560">2</span> <span m="4386870">over</span>
  <span m="4387210">delta</span> <span m="4387320">x</span> <span m="4387734">squared--</span></p><p><span
  m="4388148">STUDENT: [INAUDIBLE].</span></p><p><span m="4388976">QIQI WANG: Negative.</span>
  <span m="4390540">Thank</span> <span m="4390810">you.</span> <span m="4392304">Delta</span>
  <span m="4392802">x</span> <span m="4393300">square</span> <span m="4393800">all</span>
  <span m="4394030">the</span> <span m="4394090">way</span> <span m="4394240">to</span>
  <span m="4394420">here</span> <span m="4395405">minus</span> <span m="4395830">2</span>
  <span m="4396160">over</span> <span m="4396530">delta</span> <span m="4396956">x</span>
  <span m="4397382">square.</span> <span m="4398660">Now,</span> <span m="4399330">where</span>
  <span m="4400050">does</span> <span m="4401580">this</span> <span m="4401920">go,</span>
  <span m="4402790">Ui</span> <span m="4403120">I</span> <span m="4403250">plus</span>
  <span m="4403550">1?</span> <span m="4405915">Both</span> <span m="4407510">with</span>
  <span m="4407760">their</span> <span m="4408080">upper</span> <span m="4408570">diagonal</span>
  <span m="4409390">goes</span> <span m="4409670">over</span> <span m="4409940">here.</span>
  <span m="4410270">It''s</span> <span m="4410500">1</span> <span m="4410850">over</span>
  <span m="4411140">delta</span> <span m="4411450">x</span> <span m="4411730">squared,</span>
  <span m="4412880">1</span> <span m="4413220">over</span> <span m="4413330">delta</span>
  <span m="4413730">x</span> <span m="4413970">squared''</span> <span m="4414770">all</span>
  <span m="4415010">the</span> <span m="4415100">way</span> <span m="4415390">to</span>
  <span m="4416103">1</span> <span m="4416586">over</span> <span m="4417070">delta</span>
  <span m="4417440">x</span> <span m="4417840">square,</span> <span m="4418360">and</span>
  <span m="4419220">here,</span> <span m="4419850">1</span> <span m="4420130">over</span>
  <span m="4420250">delta x</span> <span m="4420320">squared.</span> <span m="4421420">Because</span>
  <span m="4422660">when</span> <span m="4423010">i</span> <span m="4423480">is</span>
  <span m="4424190">equal</span> <span m="4424480">to</span> <span m="4424920">n,</span>
  <span m="4425090">i</span> <span m="4425410">plus 1</span> <span m="4425600">is</span>
  <span m="4425750">actually</span> <span m="4426070">equal</span> <span m="4426310">to--</span>
  <span m="4427260">it''s</span> <span m="4427500">the</span> <span m="4427610">same</span>
  <span m="4427940">as</span> <span m="4428170">ux1.</span></p><p><span m="4430810">OK.</span>
  <span m="4431780">And</span> <span m="4432380">lastly,</span> <span m="4435410">let''s</span>
  <span m="4435890">fill</span> <span m="4436160">in</span> <span m="4436430">the--</span>
  <span m="4437414">OK.</span> <span m="4438398">Let''s</span> <span m="4438890">fill</span>
  <span m="4439150">in</span> <span m="4439530">this</span> <span m="4440640">i</span>
  <span m="4440920">minus</span> <span m="4441320">1.</span> <span m="4441930">This</span>
  <span m="4442140">is</span> <span m="4442260">i</span> <span m="4442570">minus 1.</span>
  <span m="4444526">And</span> <span m="4445000">fill</span> <span m="4445100">in</span>
  <span m="4445350">the</span> <span m="4446010">i</span> <span m="4446280">minus</span>
  <span m="4446730">1</span> <span m="4448140">term</span> <span m="4448600">we</span>
  <span m="4449500">have</span> <span m="4449730">on</span> <span m="4449860">the</span>
  <span m="4449930">lower</span> <span m="4450240">diagonal,</span> <span m="4450470">it''s</span>
  <span m="4451100">the</span> <span m="4451210">same</span> <span m="4451560">as</span>
  <span m="4451750">the</span> <span m="4451840">i plus</span> <span m="4452100">1</span>
  <span m="4452330">term,</span> <span m="4453400">1</span> <span m="4453680">over</span>
  <span m="4453790">delta</span> <span m="4454120">x</span> <span m="4454410">squared,</span>
  <span m="4454810">1</span> <span m="4455210">over</span> <span m="4455410">delta</span>
  <span m="4455640">x square,</span> <span m="4456470">and</span> <span m="4457040">1</span>
  <span m="4457260">over</span> <span m="4457510">delta</span> <span m="4457840">x</span>
  <span m="4458060">square.</span> <span m="4458640">The</span> <span m="4459910">first</span>
  <span m="4460270">term</span> <span m="4460550">is</span> <span m="4460720">actually</span>
  <span m="4461070">over</span> <span m="4461390">here.</span></p><p><span m="4464030">It</span>
  <span m="4464190">is</span> <span m="4465120">in</span> <span m="4465320">order</span>
  <span m="4465540">to</span> <span m="4465650">get</span> <span m="4465840">the</span>
  <span m="4465920">second</span> <span m="4466250">derivative</span> <span m="4466740">for</span>
  <span m="4466890">the</span> <span m="4466960">first</span> <span m="4467270">grid
  point.</span> <span m="4467680">You</span> <span m="4467800">have</span> <span m="4467960">to</span>
  <span m="4468140">graph</span> <span m="4468860">all</span> <span m="4469070">the</span>
  <span m="4469150">way</span> <span m="4469380">from</span> <span m="4469680">the</span>
  <span m="4469790">last</span> <span m="4470140">grid</span> <span m="4470570">point.</span>
  <span m="4472460">OK.</span> <span m="4472990">So</span> <span m="4473160">this</span>
  <span m="4473360">is</span> <span m="4474910">the</span> <span m="4475070">matrix</span>
  <span m="4475420">form</span> <span m="4475800">of</span> <span m="4475960">the</span>
  <span m="4476060">second</span> <span m="4476410">order</span> <span m="4476680">derivative.</span>
  <span m="4478270">OK.</span> <span m="4479510">So</span> <span m="4479910">next</span>
  <span m="4480180">class,</span> <span m="4480550">we''re</span> <span m="4480820">going
  to</span> <span m="4481040">look</span> <span m="4481460">at</span> <span m="4482490">how</span>
  <span m="4483720">the</span> <span m="4483990">finite</span> <span m="4484110">difference</span>
  <span m="4484540">schemes</span> <span m="4484810">converge</span> <span m="4485750">as</span>
  <span m="4486220">we</span> <span m="4487980">make</span> <span m="4489130">the</span>
  <span m="4489300">grid</span> <span m="4489640">point</span> <span m="4490460">more</span>
  <span m="4490880">and</span> <span m="4491050">make</span> <span m="4491290">the</span>
  <span m="4491380">spacing</span> <span m="4492080">smaller,</span> <span m="4492910">and</span>
  <span m="4493200">also</span> <span m="4493590">stop</span> <span m="4493820">to</span>
  <span m="4493920">look at</span> <span m="4495230">two-dimensional</span> <span
  m="4495380">problems.</span> <span m="4497780">All right.</span> <span m="4498980">Thank
  you.</span></p>'
type: course
uid: 4a9655858eb464dc4374580245d3124b

---
None