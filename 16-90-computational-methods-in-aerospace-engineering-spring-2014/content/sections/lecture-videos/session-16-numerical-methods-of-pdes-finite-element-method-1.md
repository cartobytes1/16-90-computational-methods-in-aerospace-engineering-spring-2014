---
about_this_resource_text: '<p><strong>Description:</strong> This abbreviated session
  begins to introduce the finite element method for 1-dimenional diffusion, including
  key ideas and its history. Due to technical difficulties, the video ends after the
  audio fails at around 14:45.</p> <p><strong>Instructor:</strong> Karen Willcox</p>  <p>The
  recording quality of this video is the best available from the source.</p><p>NOTE:
  Videos for the next several classes, Sessions 17&ndash;20, are not available.</p>'
course_id: 16-90-computational-methods-in-aerospace-engineering-spring-2014
embedded_media:
- id: Video-YouTube-Stream
  media_location: ZyoZukr_sUA
  parent_uid: 62c18c90f3799ce6175ed05989576c0c
  title: Video-YouTube-Stream
  type: Video
  uid: 6aafd1eaf0b673f28f46c8ea0a70bdaf
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/ZyoZukr_sUA/default.jpg
  parent_uid: 62c18c90f3799ce6175ed05989576c0c
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 752db1a243f49a607aee45490d6907e2
- id: 3Play-3PlayYouTubeid-MP4
  media_location: ZyoZukr_sUA
  parent_uid: 62c18c90f3799ce6175ed05989576c0c
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: a049c31ebc7a30e942ed9f4dc5488813
- id: ZyoZukr_sUA.srt
  parent_uid: 62c18c90f3799ce6175ed05989576c0c
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-16-numerical-methods-of-pdes-finite-element-method-1/ZyoZukr_sUA.srt
  title: 3play caption file
  type: null
  uid: fc07f86882b5d0b436fbff765911f28d
- id: ZyoZukr_sUA.pdf
  parent_uid: 62c18c90f3799ce6175ed05989576c0c
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-16-numerical-methods-of-pdes-finite-element-method-1/ZyoZukr_sUA.pdf
  title: 3play pdf file
  type: null
  uid: cfbf081a91664026418725774ef666bb
- id: Caption-3Play YouTube id-SRT
  parent_uid: 62c18c90f3799ce6175ed05989576c0c
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 7440d1f2c0cc35c954278768d7e74fa9
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 62c18c90f3799ce6175ed05989576c0c
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: f7767e90af304a7c06973ef41ff32748
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT16.90S14/MIT16_90S14_L16_300k.mp4
  parent_uid: 62c18c90f3799ce6175ed05989576c0c
  title: Video-Internet Archive-MP4
  type: Video
  uid: e3c9a4738f55fd861c3c4b8dc45aa3f8
inline_embed_id: 2718188session16:numericalmethodsofpdes:finiteelementmethod159591837
layout: video
order_index: null
parent_uid: 809ebf7c44bfb36e8786306747d7e32f
related_resources_text: ''
short_url: session-16-numerical-methods-of-pdes-finite-element-method-1
technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-16-numerical-methods-of-pdes-finite-element-method-1
template_type: Tabbed
title: 'Session 16: Numerical Methods of PDEs: Finite Element Method 1'
transcript: '<p><span m="30">The</span> <span m="130">following</span> <span m="600">content</span>
  <span m="1090">is</span> <span m="1210">provided</span> <span m="1660">under</span>
  <span m="1900">a</span> <span m="1950">Creative</span> <span m="2400">Commons</span>
  <span m="2820">license.</span> <span m="3780">Your</span> <span m="3880">support</span>
  <span m="4400">will</span> <span m="4560">help</span> <span m="4790">MIT</span>
  <span m="5280">OpenCourseWare</span> <span m="6020">continue</span> <span m="6510">to</span>
  <span m="6680">offer</span> <span m="6980">high</span> <span m="7200">quality</span>
  <span m="7680">educational</span> <span m="8350">resources</span> <span m="8920">for</span>
  <span m="9040">free.</span> <span m="10100">To</span> <span m="10130">make</span>
  <span m="10330">a</span> <span m="10370">donation</span> <span m="11090">or</span>
  <span m="11310">to</span> <span m="11430">view</span> <span m="11640">additional</span>
  <span m="12050">materials</span> <span m="12670">from</span> <span m="12850">hundreds</span>
  <span m="13180">of</span> <span m="13280">MIT</span> <span m="13650">courses,</span>
  <span m="14960">visit</span> <span m="15150">MIT</span> <span m="15670">OpenCourseWare</span>
  <span m="16580">at</span> <span m="16770">OCW.MIT.edu.</span></p><p><span m="26190">KAREN
  WILLCOX: All</span> <span m="26310">right.</span> <span m="26670">So</span> <span
  m="27730">let''s see.</span> <span m="27890">I</span> <span m="28030">have</span>
  <span m="28180">the</span> <span m="28250">graded</span> <span m="28630">projects</span>
  <span m="29300">here</span> <span m="29690">which</span> <span m="30010">maybe</span>
  <span m="30340">you</span> <span m="30420">guys</span> <span m="30620">can</span>
  <span m="30730">grab</span> <span m="30910">after</span> <span m="31100">class.</span>
  <span m="35306">Or you can</span> <span m="35760">grab</span> <span m="36020">them</span>
  <span m="36140">now</span> <span m="36420">if</span> <span m="36530">you</span>
  <span m="36630">want</span> <span m="36840">but</span> <span m="36940">it</span>
  <span m="37000">can</span> <span m="37130">take</span> <span m="37290">a</span>
  <span m="37340">while.</span> <span m="38600">Vikram,</span> <span m="38830">maybe</span>
  <span m="39040">you</span> <span m="39100">want</span> <span m="39220">to</span>
  <span m="39280">give</span> <span m="39490">the</span> <span m="40220">projects</span>
  <span m="40610">back.</span> <span m="41520">Just</span> <span m="41830">quietly</span>
  <span m="42210">ask</span> <span m="42420">people</span> <span m="42880">what</span>
  <span m="43020">their</span> <span m="43110">names</span> <span m="43370">are.</span></p><p><span
  m="47220">OK.</span> <span m="47590">So</span> <span m="47820">today,</span> <span
  m="48230">we''re</span> <span m="48460">going</span> <span m="48830">to</span> <span
  m="49580">talk</span> <span m="49800">about</span> <span m="50040">finite</span>
  <span m="50300">elements.</span> <span m="52220">You</span> <span m="52350">guys</span>
  <span m="52520">have</span> <span m="52620">read</span> <span m="52780">a</span>
  <span m="52810">little</span> <span m="53050">bit</span> <span m="53320">in</span>
  <span m="53540">the</span> <span m="53950">reading.</span> <span m="54530">I''m</span>
  <span m="54770">going</span> <span m="54900">to</span> <span m="55160">talk</span>
  <span m="55360">about</span> <span m="55570">a</span> <span m="55600">couple</span>
  <span m="55910">things</span> <span m="56580">first,</span> <span m="57320">just</span>
  <span m="57520">go</span> <span m="57680">through</span> <span m="57850">a</span>
  <span m="57900">couple</span> <span m="58170">of</span> <span m="58230">the</span>
  <span m="58290">very</span> <span m="58460">basic</span> <span m="58790">ideas.</span>
  <span m="59180">And</span> <span m="59300">then</span> <span m="59450">we''re</span>
  <span m="59550">going</span> <span m="59680">to</span> <span m="59760">do</span>
  <span m="59890">it</span> <span m="59970">interactively.</span> <span m="60670">You''re
  going</span> <span m="60750">to</span> <span m="60880">actually</span> <span m="61170">implement</span>
  <span m="62930">the</span> <span m="63040">one</span> <span m="63200">1D</span>
  <span m="63370">finite</span> <span m="63650">element</span> <span m="64140">codes.</span>
  <span m="64819">We''ll</span> <span m="65010">do</span> <span m="65150">it</span>
  <span m="65260">piece</span> <span m="65500">by</span> <span m="65650">piece</span>
  <span m="65970">together.</span> <span m="68570">So</span> <span m="70860">let me</span>
  <span m="71000">just</span> <span m="71190">put</span> <span m="71330">the</span>
  <span m="71430">topics</span> <span m="71940">up</span> <span m="74230">over</span>
  <span m="74480">here.</span></p><p><span m="80310">So again</span> <span m="80810">we''re</span>
  <span m="80890">going</span> <span m="81030">to</span> <span m="81090">talk</span>
  <span m="81190">about</span> <span m="81460">1D</span> <span m="81700">finite</span>
  <span m="82600">elements.</span> <span m="84940">We''re</span> <span m="85050">going</span>
  <span m="85180">to</span> <span m="85250">start</span> <span m="85610">off</span>
  <span m="86730">just</span> <span m="87080">with</span> <span m="87580">basically</span>
  <span m="88010">thinking</span> <span m="88300">about</span> <span m="88570">the</span>
  <span m="88780">key</span> <span m="88890">ideas.</span> <span m="92970">We''ll</span>
  <span m="95620">just</span> <span m="95890">look</span> <span m="96225">at</span>
  <span m="96560">a</span> <span m="96600">very</span> <span m="96980">brief</span>
  <span m="97520">history</span> <span m="98150">of</span> <span m="99120">finite</span>
  <span m="99370">elements.</span> <span m="100890">We''ll</span> <span m="102080">think</span>
  <span m="102300">about</span> <span m="102680">what</span> <span m="102910">1D</span>
  <span m="105040">linear</span> <span m="105480">elements</span> <span m="105735">look</span>
  <span m="105990">like.</span> <span m="110840">We''ll</span> <span m="111020">talk</span>
  <span m="111280">about</span> <span m="111590">the</span> <span m="111670">nodal</span>
  <span m="112030">bases.</span> <span m="118740">And</span> <span m="119060">then</span>
  <span m="119240">we</span> <span m="119360">will</span> <span m="119530">spend</span>
  <span m="119900">most</span> <span m="120260">of</span> <span m="120370">the</span>
  <span m="120440">session</span> <span m="121880">doing</span> <span m="124230">the</span>
  <span m="124330">derivation</span> <span m="126150">and</span> <span m="126320">implementation</span>
  <span m="127350">for</span> <span m="127800">the</span> <span m="127890">1D</span>
  <span m="128259">diffusion</span> <span m="128669">equation.</span> <span m="138430">Same</span>
  <span m="138770">derivation</span> <span m="139055">and</span> <span m="139340">implementation</span>
  <span m="141120">for</span> <span m="141460">1D</span> <span m="141640">diffusion.</span></p><p><span
  m="144310">OK.</span> <span m="144620">So</span> <span m="144760">by the</span>
  <span m="144970">end of</span> <span m="145380">today,</span> <span m="146200">you''ll</span>
  <span m="146360">more or</span> <span m="146715">less</span> <span m="147070">have</span>
  <span m="147400">a</span> <span m="147800">basic</span> <span m="148270">shell</span>
  <span m="148530">of</span> <span m="148610">a</span> <span m="148680">code</span>
  <span m="149140">that</span> <span m="150620">implements</span> <span m="151580">at</span>
  <span m="151690">least</span> <span m="151980">the</span> <span m="152335">meaty</span>
  <span m="152690">part</span> <span m="152930">of</span> <span m="153050">the</span>
  <span m="153410">finite</span> <span m="153680">element.</span> <span m="154070">I''m</span>
  <span m="154320">not quite</span> <span m="154520">sure</span> <span m="154590">how</span>
  <span m="154800">far we''ll get</span> <span m="155250">today.</span> <span m="155970">Then</span>
  <span m="156100">on</span> <span m="156240">Monday,</span> <span m="156870">I</span>
  <span m="156900">am</span> <span m="157080">unfortunately</span> <span m="157490">not
  going</span> <span m="157610">to</span> <span m="157670">be</span> <span m="157880">here.</span>
  <span m="158200">But Vikram</span> <span m="158650">is</span> <span m="158890">going
  to run</span> <span m="159160">the class session.</span> <span m="159740">And</span>
  <span m="159970">you</span> <span m="160030">guys</span> <span m="160220">will</span>
  <span m="160320">continue</span> <span m="160720">working</span> <span m="160980">with</span>
  <span m="161120">that</span> <span m="161300">code.</span> <span m="161920">Probably</span>
  <span m="162200">Monday</span> <span m="162660">you''ll</span> <span m="162840">implement</span>
  <span m="163190">the</span> <span m="163230">boundary</span> <span m="163530">condition</span>
  <span m="164880">and</span> <span m="165740">implement</span> <span m="166110">some</span>
  <span m="166570">quadrature</span> <span m="167030">schemes in it.</span> <span
  m="168410">And so then,</span> <span m="168580">by</span> <span m="168690">the</span>
  <span m="168810">end</span> <span m="168980">of</span> <span m="169250">class</span>
  <span m="169740">on</span> <span m="169840">Monday,</span> <span m="170250">you</span>
  <span m="170320">should</span> <span m="170440">have</span> <span m="170540">a</span>
  <span m="170590">working</span> <span m="171030">1D</span> <span m="171270">finite</span>
  <span m="171690">element</span> <span m="172120">code</span> <span m="172460">which</span>
  <span m="172670">will</span> <span m="173190">then</span> <span m="173550">hopefully</span>
  <span m="173850">be</span> <span m="173990">of</span> <span m="174110">help</span>
  <span m="174720">to</span> <span m="174870">do</span> <span m="175020">the</span>
  <span m="175110">2D</span> <span m="175510">that</span> <span m="175630">you</span>
  <span m="175690">have</span> <span m="175790">to</span> <span m="175850">do</span>
  <span m="175990">for</span> <span m="176140">the</span> <span m="176680">project.</span>
  <span m="177710">And</span> <span m="177970">on</span> <span m="178385">Wednesday</span>
  <span m="178800">of</span> <span m="178880">next</span> <span m="179090">week,</span>
  <span m="179410">Vikram</span> <span m="179510">will</span> <span m="179640">talk</span>
  <span m="179830">a</span> <span m="179860">little</span> <span m="180030">bit</span>
  <span m="180150">about</span> <span m="180230">2D</span> <span m="181000">finite</span>
  <span m="181400">elements.</span></p><p><span m="183444">So</span> <span m="185400">let''s</span>
  <span m="185740">just</span> <span m="186230">start</span> <span m="186580">off</span>
  <span m="186830">with</span> <span m="186980">key ideas.</span> <span m="187370">I''m</span>
  <span m="187470">just</span> <span m="187540">going</span> <span m="187660">to</span>
  <span m="187720">write</span> <span m="187910">over</span> <span m="188080">there</span>
  <span m="188280">for</span> <span m="188420">a</span> <span m="188480">bit</span>
  <span m="189360">because</span> <span m="189710">I</span> <span m="189800">want</span>
  <span m="189960">to</span> <span m="190480">put</span> <span m="190600">something</span>
  <span m="190830">up</span> <span m="190940">on</span> <span m="191030">the</span>
  <span m="191110">screen</span> <span m="191470">in</span> <span m="191700">a second.</span>
  <span m="193392">So</span> <span m="201090">remember</span> <span m="201480">on</span>
  <span m="201830">Monday,</span> <span m="202290">we</span> <span m="202490">talked</span>
  <span m="202800">about</span> <span m="203010">the</span> <span m="203070">method</span>
  <span m="203350">of</span> <span m="203440">weighted</span> <span m="203740">residuals.</span>
  <span m="204640">And</span> <span m="205230">again,</span> <span m="205690">just</span>
  <span m="205800">to</span> <span m="205890">sort of</span> <span m="206145">go</span>
  <span m="206400">over</span> <span m="206710">what</span> <span m="206920">the</span>
  <span m="207000">steps</span> <span m="207380">were</span> <span m="207560">in</span>
  <span m="207630">the</span> <span m="207700">method</span> <span m="207950">of</span>
  <span m="208040">weighted</span> <span m="208290">residuals.</span> <span m="209480">Kind</span>
  <span m="209670">of</span> <span m="210045">the</span> <span m="210330">fundamental</span>
  <span m="210910">idea</span> <span m="211255">is</span> <span m="211600">take</span>
  <span m="211970">the</span> <span m="212610">solution</span> <span m="213110">and
  to</span> <span m="213360">approximate</span> <span m="213720">it</span> <span m="214080">in</span>
  <span m="214170">a</span> <span m="214220">basis.</span> <span m="215426">Right?</span>
  <span m="215830">Remember</span> <span m="216110">we</span> <span m="216200">took</span>
  <span m="216380">the</span> <span m="216510">intradimensional</span> <span m="217730">PDE</span>
  <span m="218890">and</span> <span m="219120">we</span> <span m="219210">discretized</span>
  <span m="220250">it.</span> <span m="220530">And</span> <span m="220840">this</span>
  <span m="220990">is</span> <span m="221180">already</span> <span m="221570">different</span>
  <span m="221990">to</span> <span m="222090">what</span> <span m="222250">we</span>
  <span m="222350">do</span> <span m="222530">in</span> <span m="222650">finite</span>
  <span m="222930">difference</span> <span m="223290">or</span> <span m="223520">finite
  volume.</span> <span m="223910">We</span> <span m="224000">discretized</span> <span
  m="224620">it</span> <span m="224710">by</span> <span m="224840">saying</span> <span
  m="225660">let''s</span> <span m="225870">assume</span> <span m="226160">that</span>
  <span m="226300">a</span> <span m="226360">solution</span> <span m="226950">t of
  x</span> <span m="227240">lives</span> <span m="227580">in</span> <span m="227680">this</span>
  <span m="228000">finite</span> <span m="228350">dimensional</span> <span m="228810">space</span>
  <span m="229230">described</span> <span m="229680">as</span> <span m="230620">a</span>
  <span m="230750">weighted</span> <span m="231160">sum</span> <span m="231590">of</span>
  <span m="233470">basis</span> <span m="233840">functions.</span></p><p><span m="234810">Then</span>
  <span m="235130">we</span> <span m="235415">said</span> <span m="235700">how do</span>
  <span m="235970">we</span> <span m="236070">figure</span> <span m="236300">out</span>
  <span m="236390">the</span> <span m="236450">coefficient</span> <span m="237450">of</span>
  <span m="237820">the</span> <span m="238330">basis</span> <span m="238670">function?</span>
  <span m="239376">And</span> <span m="239730">we</span> <span m="239890">went</span>
  <span m="240060">through</span> <span m="240180">the</span> <span m="240260">derivation</span>
  <span m="240920">of</span> <span m="242300">choosing</span> <span m="242640">weighting</span>
  <span m="242930">functions</span> <span m="243430">to</span> <span m="243540">be</span>
  <span m="243650">the</span> <span m="243730">same</span> <span m="244740">functions</span>
  <span m="245270">that</span> <span m="245410">we</span> <span m="245600">used</span>
  <span m="246310">in</span> <span m="246440">the</span> <span m="246510">basis</span>
  <span m="246860">to</span> <span m="246950">approximate</span> <span m="247390">the</span>
  <span m="247470">solution.</span> <span m="248130">What</span> <span m="248270">was</span>
  <span m="248370">that</span> <span m="248500">called?</span> <span m="253280">What''s</span>
  <span m="253410">it</span> <span m="253490">called</span> <span m="253750">when</span>
  <span m="253910">you</span> <span m="254000">choose</span> <span m="254240">the</span>
  <span m="254310">weighting</span> <span m="254580">functions</span> <span m="254960">to</span>
  <span m="255100">be</span> <span m="255190">the</span> <span m="255270">same</span>
  <span m="255520">functions that</span> <span m="255980">you think</span> <span m="256360">[INAUDIBLE]?</span>
  <span m="257730">Galerkin.</span> <span m="258350">Yeah.</span> <span m="258700">It''s</span>
  <span m="258950">the Galerkin</span> <span m="259279">method.</span> <span m="261645">When</span>
  <span m="262019">we</span> <span m="262150">define</span> <span m="262470">the</span>
  <span m="262540">residual,</span> <span m="263150">multiplying</span> <span m="263640">by</span>
  <span m="263750">the</span> <span m="263840">weighting</span> <span m="264170">function</span>
  <span m="264490">using</span> <span m="264810">Galerkin.</span> <span m="266010">Integrating</span>
  <span m="266460">over</span> <span m="266580">the</span> <span m="266650">domain,</span>
  <span m="267110">setting</span> <span m="267410">that</span> <span m="267690">equal</span>
  <span m="267950">to zero.</span> <span m="268160">That''s</span> <span m="268320">the</span>
  <span m="268400">weighted</span> <span m="268670">residual.</span> <span m="269020">Those</span>
  <span m="269250">gave</span> <span m="269420">us</span> <span m="269670">the</span>
  <span m="271020">equations</span> <span m="271630">we</span> <span m="271780">solve</span>
  <span m="272310">to</span> <span m="272440">find</span> <span m="272690">the</span>
  <span m="272750">approximation.</span></p><p><span m="273960">So</span> <span m="274070">we''re</span>
  <span m="274170">more</span> <span m="274320">or</span> <span m="274490">less</span>
  <span m="274860">going</span> <span m="275240">to</span> <span m="275350">do</span>
  <span m="275640">the</span> <span m="275730">same</span> <span m="276040">thing</span>
  <span m="276380">now</span> <span m="276470">with</span> <span m="276620">finite</span>
  <span m="276780">elements.</span> <span m="277606">So what</span> <span m="278020">you</span>
  <span m="278130">are</span> <span m="278210">going</span> <span m="278330">to</span>
  <span m="278390">see</span> <span m="278590">today</span> <span m="278870">is</span>
  <span m="279020">that</span> <span m="279770">a</span> <span m="280170">finite</span>
  <span m="280360">element</span> <span m="280750">as</span> <span m="280900">we''re</span>
  <span m="280970">going</span> <span m="281090">to</span> <span m="281150">view</span>
  <span m="281440">it</span> <span m="281560">is</span> <span m="281710">based</span>
  <span m="281970">on</span> <span m="282100">the</span> <span m="282170">method</span>
  <span m="282470">of</span> <span m="282560">weighted</span> <span m="282870">residuals.</span>
  <span m="293820">But</span> <span m="294030">what</span> <span m="294410">is</span>
  <span m="294470">different</span> <span m="294970">is</span> <span m="295390">the</span>
  <span m="295490">first</span> <span m="295830">step.</span> <span m="296190">Before</span>
  <span m="296570">we</span> <span m="296730">start</span> <span m="298890">with</span>
  <span m="300290">the</span> <span m="300380">approximation</span> <span m="301000">of</span>
  <span m="301090">the</span> <span m="301160">solution,</span> <span m="301700">the</span>
  <span m="301760">very</span> <span m="301960">first</span> <span m="302230">thing</span>
  <span m="302420">we''re</span> <span m="302510">going</span> <span m="302630">to</span>
  <span m="302710">do</span> <span m="303000">is</span> <span m="303200">to</span>
  <span m="303310">discretize</span> <span m="304120">the</span> <span m="304230">domain</span>
  <span m="305420">into</span> <span m="305690">small</span> <span m="306110">cells.</span>
  <span m="307610">OK?</span> <span m="307830">So</span> <span m="307970">we''re</span>
  <span m="308060">going</span> <span m="308200">to</span> <span m="308270">divide</span>
  <span m="308620">up</span> <span m="308760">our</span> <span m="309020">domain--</span>
  <span m="309470">rather</span> <span m="309680">than</span> <span m="309830">thinking</span>
  <span m="310170">about</span> <span m="310500">the</span> <span m="310560">approximation</span>
  <span m="311230">of the</span> <span m="311380">solution</span> <span m="311990">globally</span>
  <span m="312510">over</span> <span m="312590">the</span> <span m="312730">whole</span>
  <span m="312950">domain,</span> <span m="313740">we''re</span> <span m="313850">going</span>
  <span m="314030">to</span> <span m="314140">discretize</span> <span m="314650">our</span>
  <span m="314810">domain</span> <span m="315120">into</span> <span m="315370">small</span>
  <span m="315600">cells,</span> <span m="317970">elements.</span> <span m="319970">That''s</span>
  <span m="320750">the element</span> <span m="321030">of</span> <span m="321520">the</span>
  <span m="321640">finite</span> <span m="321910">element</span> <span m="322250">method.</span>
  <span m="322670">They''ve</span> <span m="322850">been</span> <span m="323010">called--</span>
  <span m="323340">I</span> <span m="323390">think</span> <span m="323570">you</span>
  <span m="323650">guys</span> <span m="323830">called</span> <span m="324050">them
  cells</span> <span m="324520">when</span> <span m="324680">you</span> <span m="324740">talked</span>
  <span m="324950">about</span> <span m="325230">finite</span> <span m="325430">difference.</span>
  <span m="325810">Is that right?</span> <span m="327090">Nodes</span> <span m="327590">and</span>
  <span m="327740">cells?</span> <span m="328970">And</span> <span m="329110">for</span>
  <span m="329160">finite</span> <span m="329420">elements,</span> <span m="330230">the</span>
  <span m="330380">cells</span> <span m="330790">are</span> <span m="331420">referred</span>
  <span m="331720">to</span> <span m="331890">as</span> <span m="332040">elements.</span></p><p><span
  m="333310">Then</span> <span m="334970">once</span> <span m="335180">we''ve</span>
  <span m="335330">discretized</span> <span m="335730">the</span> <span m="335870">domain</span>
  <span m="336150">into</span> <span m="336320">small</span> <span m="336570">cells,</span>
  <span m="336940">then</span> <span m="337030">we''re just</span> <span m="337290">going</span>
  <span m="337410">to</span> <span m="337480">go</span> <span m="337710">and</span>
  <span m="337850">basically</span> <span m="338270">do</span> <span m="338440">what</span>
  <span m="338610">we</span> <span m="338710">did</span> <span m="338880">with</span>
  <span m="339000">negative</span> <span m="339300">weighted</span> <span m="339550">residuals.</span>
  <span m="340150">So</span> <span m="340260">now</span> <span m="341130">we''re</span>
  <span m="341250">going</span> <span m="341370">to</span> <span m="341440">think</span>
  <span m="341710">about</span> <span m="342150">approximating</span> <span m="343420">the</span>
  <span m="343490">solution</span> <span m="344220">in</span> <span m="344460">each</span>
  <span m="344800">element.</span> <span m="350980">So</span> <span m="351070">in</span>
  <span m="351140">each</span> <span m="351560">element,</span> <span m="352100">we''re</span>
  <span m="352230">going</span> <span m="352350">to</span> <span m="352440">say</span>
  <span m="352830">let''s</span> <span m="354140">assume</span> <span m="354570">that</span>
  <span m="354830">the</span> <span m="355150">solution</span> <span m="355620">can</span>
  <span m="355740">be</span> <span m="355860">approximated</span> <span m="356400">as</span>
  <span m="356570">a</span> <span m="356630">linear</span> <span m="357070">combination</span>
  <span m="357910">of</span> <span m="358470">basis</span> <span m="358810">functions.</span>
  <span m="359280">And we''re</span> <span m="359734">going to</span> <span m="360188">use
  polynomials</span> <span m="361550">just</span> <span m="361750">like</span> <span
  m="361920">we</span> <span m="362010">did</span> <span m="362180">on</span> <span
  m="362310">Monday.</span> <span m="363590">But</span> <span m="363730">now</span>
  <span m="363880">the</span> <span m="363950">polynomials</span> <span m="364480">are</span>
  <span m="364590">just</span> <span m="364670">going</span> <span m="364800">to</span>
  <span m="364870">be</span> <span m="365000">defined</span> <span m="365470">over</span>
  <span m="365690">the</span> <span m="366210">little</span> <span m="366650">element,</span>
  <span m="367130">the</span> <span m="367210">little</span> <span m="367490">piece</span>
  <span m="367730">of</span> <span m="367790">the</span> <span m="367880">domain.</span>
  <span m="368260">Not</span> <span m="368500">the</span> <span m="368590">whole</span>
  <span m="368790">domain.</span> <span m="372510">E.g.</span> <span m="373000">Here</span>
  <span m="373330">with</span> <span m="373640">polynomial</span> <span m="376430">functions.</span>
  <span m="376900">Again,</span> <span m="377130">just</span> <span m="377320">like</span>
  <span m="377450">we</span> <span m="377540">did</span> <span m="377750">on</span>
  <span m="377880">Monday</span> <span m="378350">but</span> <span m="378520">now</span>
  <span m="378850">to</span> <span m="378970">serve</span> <span m="379260">a</span>
  <span m="379610">small</span> <span m="379940">element</span> <span m="381530">polynomial</span>
  <span m="381990">function.</span></p><p><span m="383680">And</span> <span m="383840">then</span>
  <span m="383990">again,</span> <span m="384240">it''s</span> <span m="384330">going</span>
  <span m="384450">to</span> <span m="384510">be</span> <span m="384590">the</span>
  <span m="384670">same</span> <span m="384920">as</span> <span m="385020">what</span>
  <span m="385150">we</span> <span m="385240">did</span> <span m="385420">on</span>
  <span m="385550">Monday.</span> <span m="386090">Once</span> <span m="387100">we''ve
  done</span> <span m="387560">the</span> <span m="387630">approximation,</span> <span
  m="388350">we''re going to</span> <span m="388650">evaluate</span> <span m="390440">weighted</span>
  <span m="390750">residuals</span> <span m="391400">for</span> <span m="391490">each</span>
  <span m="391760">element.</span> <span m="398330">We''re</span> <span m="398440">going</span>
  <span m="398600">to</span> <span m="398910">use the</span> <span m="399090">Galerkin</span>
  <span m="399577">method</span> <span m="402500">to</span> <span m="402650">do</span>
  <span m="402830">that,</span> <span m="403300">to</span> <span m="403690">define</span>
  <span m="404370">the</span> <span m="404450">weighted</span> <span m="404720">residual.</span>
  <span m="405990">That''s</span> <span m="406230">going</span> <span m="406360">to</span>
  <span m="406450">give</span> <span m="406620">us</span> <span m="406780">a</span>
  <span m="406830">system</span> <span m="407160">of</span> <span m="407280">equations.</span>
  <span m="410280">And we''re</span> <span m="410780">going</span> <span m="411280">to
  solve</span> <span m="415160">to</span> <span m="415300">determine</span> <span
  m="415710">the</span> <span m="415790">weighting</span> <span m="416120">coefficient.</span>
  <span m="426880">Weighting</span> <span m="427250">coefficients.</span></p><p><span
  m="428340">So</span> <span m="429160">basically</span> <span m="429600">exactly</span>
  <span m="430080">what</span> <span m="430230">we</span> <span m="430330">did</span>
  <span m="430530">on</span> <span m="430620">Monday,</span> <span m="431180">except</span>
  <span m="431670">that</span> <span m="431830">first</span> <span m="432220">step</span>
  <span m="432440">which</span> <span m="432680">is</span> <span m="432890">discretize</span>
  <span m="433570">the</span> <span m="433650">domain</span> <span m="433920">to</span>
  <span m="434320">small</span> <span m="434670">cells.</span> <span m="435540">And</span>
  <span m="435690">then</span> <span m="435820">what</span> <span m="435960">you''re</span>
  <span m="436060">going</span> <span m="436380">to</span> <span m="436470">see</span>
  <span m="436780">is</span> <span m="437320">that</span> <span m="438250">idea</span>
  <span m="438500">of</span> <span m="438570">breaking</span> <span m="438900">the</span>
  <span m="438990">domain</span> <span m="439305">up into</span> <span m="439620">small</span>
  <span m="439790">cells,</span> <span m="440780">we''re</span> <span m="440870">going</span>
  <span m="441030">to</span> <span m="441090">make</span> <span m="441250">a</span>
  <span m="441290">very</span> <span m="441540">special</span> <span m="442080">choice</span>
  <span m="442490">for</span> <span m="442580">the</span> <span m="442660">polynomial</span>
  <span m="443110">basis</span> <span m="443420">functions.</span> <span m="443970">It''s</span>
  <span m="444100">going</span> <span m="444220">to</span> <span m="444290">be</span>
  <span m="444450">really</span> <span m="444690">neat</span> <span m="445140">because</span>
  <span m="445640">when</span> <span m="445800">we</span> <span m="445920">do</span>
  <span m="446070">the</span> <span m="446160">weighted</span> <span m="446400">residuals</span>
  <span m="446800">and we</span> <span m="446880">do</span> <span m="447050">all the</span>
  <span m="447150">integrals--</span> <span m="448160">like</span> <span m="448390">we
  mentioned</span> <span m="448560">a little bit, I think,</span> <span m="449090">in</span>
  <span m="449150">response</span> <span m="449460">to one</span> <span m="449580">of</span>
  <span m="449620">[INAUDIBLE]</span> <span m="449990">questions--</span> <span m="450920">a
  whole</span> <span m="451130">bunch</span> <span m="451340">of</span> <span m="451470">integrals
  are</span> <span m="451820">going</span> <span m="452010">to</span> <span m="452080">fall</span>
  <span m="452390">out.</span> <span m="452900">And</span> <span m="453470">it''ll</span>
  <span m="453610">turn</span> <span m="453790">out</span> <span m="454100">that</span>
  <span m="454220">everything</span> <span m="454500">has</span> <span m="454620">got</span>
  <span m="454740">a</span> <span m="454800">very</span> <span m="455790">special</span>
  <span m="456470">and</span> <span m="457220">really</span> <span m="458460">efficient</span>
  <span m="458980">and</span> <span m="459360">kind</span> <span m="459520">of neat</span>
  <span m="459770">structure</span> <span m="460140">to</span> <span m="460330">it.</span></p><p><span
  m="461480">AUDIENCE: Did you</span> <span m="461650">pick the same</span> <span
  m="462620">basis</span> <span m="463105">functions for</span> <span m="463590">the
  entire</span> <span m="464075">problem</span> <span m="464560">or for</span> <span
  m="465045">each</span> <span m="465530">individual</span> <span m="466015">cell?</span></p><p><span
  m="466990">KAREN WILLCOX: Yeah. So</span> <span m="467240">the</span> <span m="467310">question</span>
  <span m="467620">is</span> <span m="467790">do</span> <span m="467890">you</span>
  <span m="467970">pick</span> <span m="468190">the</span> <span m="468270">same</span>
  <span m="468680">basic</span> <span m="468820">functions</span> <span m="469240">for</span>
  <span m="469330">the</span> <span m="469410">entire</span> <span m="469810">problem,</span>
  <span m="470230">or for</span> <span m="470550">each</span> <span m="470870">individual
  cell?</span> <span m="471130">You''re</span> <span m="471210">going</span> <span
  m="471330">to</span> <span m="471450">see it</span> <span m="471580">in</span> <span
  m="471710">just a</span> <span m="471950">second.</span> <span m="473840">There</span>
  <span m="473890">are</span> <span m="473920">a</span> <span m="473950">lot</span>
  <span m="474090">of</span> <span m="474150">different</span> <span m="474380">ways</span>
  <span m="474770">to</span> <span m="474920">choose</span> <span m="475200">the</span>
  <span m="475270">basic</span> <span m="475510">function.</span> <span m="476090">Today</span>
  <span m="476410">we''re</span> <span m="476560">going</span> <span m="476820">to</span>
  <span m="476900">talk</span> <span m="477090">about</span> <span m="477480">a</span>
  <span m="477740">special</span> <span m="478070">choice</span> <span m="478400">that''s
  referred</span> <span m="478885">to as</span> <span m="479370">the nodal</span>
  <span m="479855">basis.</span> <span m="480340">And you''ll see</span> <span m="480825">exactly</span>
  <span m="481310">what they</span> <span m="481795">are.</span></p><p><span m="485680">Before</span>
  <span m="485940">I</span> <span m="486030">start,</span> <span m="486520">are there</span>
  <span m="486800">any</span> <span m="487330">kind</span> <span m="487530">of</span>
  <span m="488240">residual</span> <span m="488750">questions</span> <span m="489360">from</span>
  <span m="489670">method</span> <span m="489920">of</span> <span m="490000">weighted</span>
  <span m="490240">residuals?</span> <span m="491410">Residual</span> <span m="491680">questions.</span>
  <span m="492780">Are there</span> <span m="492960">any things</span> <span m="493370">about</span>
  <span m="493610">method</span> <span m="493810">of</span> <span m="493890">weighted</span>
  <span m="494150">residuals</span> <span m="494415">that</span> <span m="494740">is</span>
  <span m="495740">mysterious</span> <span m="496580">or</span> <span m="497180">uncomfortable?</span>
  <span m="499495">It''s</span> <span m="499960">pretty</span> <span m="500120">straightforward,</span>
  <span m="500395">right?</span></p><p>&nbsp;</p><p><span m="508110">So</span> <span
  m="510100">just</span> <span m="510230">before</span> <span m="510410">we</span>
  <span m="510640">start,</span> <span m="510850">I</span> <span m="510970">want</span>
  <span m="511160">to</span> <span m="511220">give</span> <span m="511420">you</span>
  <span m="512039">a</span> <span m="512080">little</span> <span m="512490">bit</span>
  <span m="512700">of</span> <span m="512820">a--</span> <span m="519770">I hate</span>
  <span m="519929">this WebEx</span> <span m="520100">thing.</span> <span m="520590">Because
  when</span> <span m="520710">you</span> <span m="520770">try</span> <span m="520919">to</span>
  <span m="521000">grab</span> <span m="521360">things,</span> <span m="523480">it
  goes</span> <span m="523909">down--</span> <span m="526370">little</span> <span
  m="526600">bit</span> <span m="526740">of</span> <span m="526870">a</span> <span
  m="527220">historical</span> <span m="528680">perspective.</span> <span m="529430">And</span>
  <span m="529540">actually</span> <span m="530380">I</span> <span m="530820">went</span>
  <span m="531260">to</span> <span m="531400">Wikipedia</span> <span m="531700">as
  you</span> <span m="532000">do,</span> <span m="532840">which</span> <span m="533680">actually</span>
  <span m="533900">doesn''t</span> <span m="534160">have</span> <span m="534490">a
  bad--</span> <span m="535480">this</span> <span m="535630">is</span> <span m="535690">the</span>
  <span m="535770">Wikipedia</span> <span m="536240">entry</span> <span m="536610">for</span>
  <span m="536800">finite</span> <span m="537140">element</span> <span m="537510">method,</span>
  <span m="538570">which</span> <span m="538900">actually</span> <span m="539200">surprised</span>
  <span m="539750">me.</span> <span m="540850">Look how</span> <span m="541290">many</span>
  <span m="541730">sections there are.</span> <span m="542170">Vikram,</span> <span
  m="542610">have you</span> <span m="542840">contributing</span> <span m="543320">to</span>
  <span m="543450">Wikipedia?</span></p><p><span m="544522">AUDIENCE: No.</span></p><p><span
  m="545935">[LAUGHTER]</span></p><p><span m="547348">KAREN WILLCOX: Aha.</span> <span
  m="550180">There''s</span> <span m="550360">actually</span> <span m="551590">quite</span>
  <span m="552000">a</span> <span m="552040">lot</span> <span m="552200">here.</span>
  <span m="552370">I</span> <span m="552450">didn''t</span> <span m="552650">read</span>
  <span m="552850">it</span> <span m="552950">all.</span> <span m="553220">So</span>
  <span m="553380">I</span> <span m="553460">can''t</span> <span m="553810">verify</span>
  <span m="555060">how</span> <span m="555250">good</span> <span m="555400">it</span>
  <span m="555500">is.</span> <span m="555710">Although</span> <span m="556160">Wikipedia</span>
  <span m="556460">appears</span> <span m="556700">to</span> <span m="556780">be</span>
  <span m="556920">pretty</span> <span m="557130">good,</span> <span m="557390">there''s</span>
  <span m="557490">enough</span> <span m="557720">of</span> <span m="557850">a</span>
  <span m="557920">community</span> <span m="558340">of</span> <span m="558510">people.</span>
  <span m="560994">So</span> <span m="561490">I</span> <span m="561770">was</span>
  <span m="561950">going</span> <span m="562080">to</span> <span m="562140">show</span>
  <span m="562280">you</span> <span m="562370">guys</span> <span m="562520">the</span>
  <span m="562570">history</span> <span m="562870">about</span> <span m="563160">technical</span>
  <span m="564190">discussion,</span> <span m="565680">general</span> <span m="565900">principles</span>
  <span m="566530">of</span> <span m="566580">weak</span> <span m="566780">formulation,</span>
  <span m="568070">discretization.</span> <span m="568660">Then</span> <span m="568790">you</span>
  <span m="568860">can</span> <span m="568980">see</span> <span m="569170">all</span>
  <span m="569500">the</span> <span m="569590">different</span> <span m="569900">kinds</span>
  <span m="570280">of</span> <span m="570820">finite</span> <span m="571150">element</span>
  <span m="571550">methods</span> <span m="573300">that</span> <span m="573530">exist.</span>
  <span m="575040">So</span> <span m="575160">that</span> <span m="575360">should</span>
  <span m="575510">give</span> <span m="575640">you</span> <span m="575730">a</span>
  <span m="575770">sense</span> <span m="576080">of</span> <span m="576160">just</span>
  <span m="576390">how</span> <span m="576940">big</span> <span m="577190">of</span>
  <span m="577290">a</span> <span m="577360">field</span> <span m="577760">of</span>
  <span m="578010">study</span> <span m="578260">this</span> <span m="578440">is.</span>
  <span m="578670">We''re</span> <span m="578750">going</span> <span m="578870">to</span>
  <span m="579000">be</span> <span m="579140">just</span> <span m="579350">a</span>
  <span m="579390">little</span> <span m="579770">tiny</span> <span m="580090">bit</span>
  <span m="580250">of</span> <span m="580350">it.</span> <span m="580930">[INAUDIBLE]</span>
  <span m="581350">for</span> <span m="581480">finite</span> <span m="581740">difference</span>
  <span m="582110">method</span> <span m="582360">application.</span></p><p><span
  m="583360">I</span> <span m="583480">just</span> <span m="583700">wanted</span>
  <span m="583970">to</span> <span m="584080">mention</span> <span m="587140">a</span>
  <span m="587220">little</span> <span m="587460">bit</span> <span m="587720">just</span>
  <span m="587910">about</span> <span m="588130">the</span> <span m="588220">history.</span>
  <span m="589400">So</span> <span m="589850">like</span> <span m="590020">it</span>
  <span m="590170">says</span> <span m="590310">here,</span> <span m="590480">it''s
  difficult to</span> <span m="590970">quote</span> <span m="591310">the</span> <span
  m="591380">date</span> <span m="591720">of</span> <span m="591800">the</span> <span
  m="591900">invention</span> <span m="592320">of</span> <span m="592390">the</span>
  <span m="592460">finite</span> <span m="592650">element</span> <span m="593050">method.</span>
  <span m="594840">More</span> <span m="595100">or</span> <span m="595160">less,</span>
  <span m="595520">its</span> <span m="595700">origins</span> <span m="596280">are</span>
  <span m="596440">actually</span> <span m="598650">from</span> <span m="598910">structures</span>
  <span m="599830">in both</span> <span m="600270">civil</span> <span m="600660">and</span>
  <span m="601070">aerospace</span> <span m="601990">aeronautical</span> <span m="602480">engineering.</span>
  <span m="602790">So</span> <span m="603100">it</span> <span m="603490">has</span>
  <span m="603810">roots in</span> <span m="604660">aeronautical</span> <span m="605110">engineering.</span>
  <span m="606490">And</span> <span m="607450">there</span> <span m="607630">were</span>
  <span m="607900">three</span> <span m="609070">kind</span> <span m="609280">of</span>
  <span m="609400">groups</span> <span m="611900">where</span> <span m="612210">if</span>
  <span m="612300">you</span> <span m="612420">trace</span> <span m="612750">back,</span>
  <span m="613000">that''s</span> <span m="613180">where</span> <span m="613350">things</span>
  <span m="613640">seem</span> <span m="613940">to</span> <span m="614490">have</span>
  <span m="615440">really</span> <span m="615670">originated.</span> <span m="616280">Courant</span>
  <span m="616730">is</span> <span m="616830">often</span> <span m="617670">the</span>
  <span m="617830">person</span> <span m="618210">whose</span> <span m="618450">is
  cited</span> <span m="618980">as</span> <span m="620030">being,</span> <span m="620320">I
  guess, the</span> <span m="620670">father</span> <span m="621810">of</span> <span
  m="621970">a</span> <span m="622010">lot</span> <span m="622140">of</span> <span
  m="622230">theories</span> <span m="622500">that</span> <span m="622590">led to
  finite</span> <span m="623040">elements.</span> <span m="623510">So</span> <span
  m="623610">he</span> <span m="623770">was</span> <span m="623930">at</span> <span
  m="624090">NYU</span> <span m="625550">and</span> <span m="625730">then</span> <span
  m="625830">established</span> <span m="626410">an</span> <span m="626480">Applied</span>
  <span m="626820">Math</span> <span m="628980">institute,</span> <span m="629480">the</span>
  <span m="629800">Courant</span> <span m="630180">Institute</span> <span m="630650">which</span>
  <span m="630800">still</span> <span m="630950">exists</span> <span m="631210">today.</span>
  <span m="631470">It is</span> <span m="631650">one</span> <span m="631750">of</span>
  <span m="631810">the</span> <span m="631880">best</span> <span m="632230">Applied</span>
  <span m="632520">Math</span> <span m="632885">computational</span> <span m="633250">places</span>
  <span m="634930">in</span> <span m="635300">the</span> <span m="635370">world.</span>
  <span m="635760">And</span> <span m="635880">as</span> <span m="636090">you</span>
  <span m="636160">can</span> <span m="636320">see</span> <span m="636580">here,</span>
  <span m="638320">I think</span> <span m="638460">this</span> <span m="638610">is</span>
  <span m="638890">a</span> <span m="638990">German</span> <span m="640540">mathematician.</span>
  <span m="641130">And</span> <span m="641270">also</span> <span m="641750">things</span>
  <span m="642010">were</span> <span m="642080">going</span> <span m="642340">on</span>
  <span m="642470">in</span> <span m="642590">China</span> <span m="643030">at the
  same</span> <span m="643320">time.</span></p><p><span m="645720">So</span> <span
  m="645870">there''s</span> <span m="646350">a</span> <span m="647100">little</span>
  <span m="647300">bit</span> <span m="647430">here.</span> <span m="647790">You</span>
  <span m="647900">can</span> <span m="648070">see</span> <span m="648250">there</span>
  <span m="648490">Rayleigh,</span> <span m="648520">Ritz,</span> <span m="648785">and</span>
  <span m="649370">Galerkin.</span> <span m="650190">Those are</span> <span m="650350">all</span>
  <span m="650430">names</span> <span m="650830">of</span> <span m="650910">mathematicians</span>
  <span m="651550">that</span> <span m="651680">you guys</span> <span m="651760">have</span>
  <span m="652190">seen</span> <span m="652480">in</span> <span m="652590">various</span>
  <span m="653000">methods,</span> <span m="654735">things</span> <span m="655120">that</span>
  <span m="655220">came</span> <span m="655480">up.</span> <span m="656880">Really</span>
  <span m="657220">the</span> <span m="657410">way the</span> <span m="657440">finite</span>
  <span m="657940">element</span> <span m="658350">method</span> <span m="659020">started</span>
  <span m="659510">to</span> <span m="659900">really</span> <span m="660240">sort</span>
  <span m="660420">of</span> <span m="660530">become</span> <span m="660960">like</span>
  <span m="661120">a</span> <span m="661170">computational</span> <span m="662860">powerhouse,</span>
  <span m="663770">I</span> <span m="663910">think,</span> <span m="664200">was</span>
  <span m="664490">here</span> <span m="664660">in</span> <span m="664750">the</span>
  <span m="664820">60s</span> <span m="665260">and</span> <span m="665410">70s.</span>
  <span m="665980">So</span> <span m="666240">Agyris</span> <span m="666400">at</span>
  <span m="667170">the</span> <span m="667290">University</span> <span m="667740">of</span>
  <span m="667890">Stuttgart.</span> <span m="669410">I</span> <span m="669510">think</span>
  <span m="669580">this is</span> <span m="669770">pronounced</span> <span m="670010">Clough.</span>
  <span m="670380">Is</span> <span m="670630">that</span> <span m="670800">right,</span>
  <span m="671650">Vikram?</span> <span m="672130">Yeah.</span> <span m="673000">Clough</span>
  <span m="673530">at</span> <span m="674060">UC</span> <span m="674430">Berkeley.</span>
  <span m="675650">And</span> <span m="675930">Zienkiewicz</span> <span m="677150">at</span>
  <span m="677570">University</span> <span m="677800">of</span> <span m="678130">Swansea.</span>
  <span m="678230">And in</span> <span m="678600">fact</span> <span m="678850">University</span>
  <span m="678950">of Swansea</span> <span m="679160">is</span> <span m="679300">where</span>
  <span m="679500">Professor</span> <span m="679700">[INAUDIBLE]</span> <span m="680070">did</span>
  <span m="680280">his</span> <span m="680680">PhD.</span> <span m="681880">And</span>
  <span m="682020">he</span> <span m="682130">was</span> <span m="682280">working</span>
  <span m="682800">with</span> <span m="684010">some</span> <span m="684110">of</span>
  <span m="684180">the</span> <span m="684250">later</span> <span m="684540">people</span>
  <span m="684940">there</span> <span m="685290">that</span> <span m="685460">were</span>
  <span m="685550">at</span> <span m="685610">the</span> <span m="685680">forefront</span>
  <span m="686120">of</span> <span m="686180">finite element methods</span> <span
  m="688130">and</span> <span m="688500">their</span> <span m="688660">development.</span></p><p><span
  m="690400">So</span> <span m="690420">it''s</span> <span m="690540">actually</span>
  <span m="690770">a</span> <span m="691020">really</span> <span m="691220">kind</span>
  <span m="691400">of</span> <span m="691480">neat</span> <span m="691740">story</span>
  <span m="692240">because</span> <span m="692610">it</span> <span m="692720">really</span>
  <span m="692930">comes</span> <span m="693200">from</span> <span m="693430">applied</span>
  <span m="693680">math.</span> <span m="694100">And</span> <span m="694510">you''re</span>
  <span m="694700">not</span> <span m="694810">going</span> <span m="694930">to</span>
  <span m="695000">see</span> <span m="695170">a</span> <span m="695220">whole</span>
  <span m="695520">lot</span> <span m="695690">of</span> <span m="695770">it</span>
  <span m="695880">in</span> <span m="696000">class.</span> <span m="696430">But</span>
  <span m="696610">there''s</span> <span m="697300">a</span> <span m="697400">lot</span>
  <span m="697600">of</span> <span m="697770">incredible</span> <span m="699190">analysis</span>
  <span m="700270">and</span> <span m="700640">theoretical</span> <span m="701090">results</span>
  <span m="701630">that</span> <span m="701830">go</span> <span m="702040">with</span>
  <span m="702910">finite</span> <span m="703760">element</span> <span m="704130">methods,</span>
  <span m="704870">a</span> <span m="705040">lot of</span> <span m="705120">guarantees</span>
  <span m="705610">that</span> <span m="705740">can</span> <span m="705900">be</span>
  <span m="706030">made.</span> <span m="706760">So</span> <span m="706880">there''s</span>
  <span m="707020">really</span> <span m="707290">a</span> <span m="707560">hardcore</span>
  <span m="708270">math</span> <span m="708740">component.</span> <span m="710000">But</span>
  <span m="710150">then</span> <span m="710280">it</span> <span m="710420">has</span>
  <span m="710550">gone</span> <span m="710900">on</span> <span m="711940">to</span>
  <span m="712150">be</span> <span m="712900">of</span> <span m="713080">such</span>
  <span m="713390">practical</span> <span m="713860">use.</span> <span m="714240">So</span>
  <span m="714250">it</span> <span m="714350">started</span> <span m="714690">off</span>
  <span m="714870">in</span> <span m="715080">structural</span> <span m="715510">problems</span>
  <span m="716220">but</span> <span m="716360">now</span> <span m="716580">is</span>
  <span m="716690">applied</span> <span m="717230">to fluid</span> <span m="717670">problems,</span>
  <span m="718100">acoustics,</span> <span m="719680">all</span> <span m="719850">kinds</span>
  <span m="720920">of</span> <span m="721000">things.</span> <span m="721950">You</span>
  <span m="722020">can</span> <span m="722140">see</span> <span m="722250">here</span>
  <span m="722390">NASA</span> <span m="722750">sponsored</span> <span m="723010">the</span>
  <span m="723110">original</span> <span m="723410">vision</span> <span m="723670">of</span>
  <span m="723740">NASTRAN.</span> <span m="724410">I</span> <span m="724850">actually
  didn''t</span> <span m="725020">know that until</span> <span m="725402">I read</span>
  <span m="725784">this.</span> <span m="726550">So</span> <span m="726650">now</span>
  <span m="726800">there''s</span> <span m="726940">a</span> <span m="726980">lot</span>
  <span m="727110">of</span> <span m="727180">software,</span> <span m="727700">things</span>
  <span m="727900">like</span> <span m="728030">NASTRAN</span> <span m="728400">ADINA</span>
  <span m="729070">is</span> <span m="729400">Professor</span> <span m="729750">Bathe</span>
  <span m="730420">from</span> <span m="730550">mechanical</span> <span m="730970">engineering</span>
  <span m="732570">package.</span> <span m="733350">Professor</span> <span m="733730">Strang</span>
  <span m="734220">in</span> <span m="734330">the</span> <span m="734410">math</span>
  <span m="734640">department</span> <span m="735170">also</span> <span m="735600">plays</span>
  <span m="736530">a</span> <span m="736640">really</span> <span m="736840">important</span>
  <span m="737290">role</span> <span m="737640">in</span> <span m="737800">some</span>
  <span m="737970">of</span> <span m="738110">the</span> <span m="739480">rigorous</span>
  <span m="739910">results</span> <span m="740290">early on.</span> <span m="741436">So</span>
  <span m="741820">there''s</span> <span m="741980">also</span> <span m="742220">a</span>
  <span m="742410">lot</span> <span m="742560">of</span> <span m="743710">connections</span>
  <span m="744240">to</span> <span m="744370">MIT.</span></p><p><span m="746620">So</span>
  <span m="747070">we''re</span> <span m="747230">going</span> <span m="747380">to</span>
  <span m="747450">see</span> <span m="747690">only</span> <span m="748120">just</span>
  <span m="748640">a</span> <span m="750420">little</span> <span m="750620">piece</span>
  <span m="753050">of</span> <span m="753230">the</span> <span m="753300">finite</span>
  <span m="753620">element</span> <span m="755900">method.</span> <span m="756854">But</span>
  <span m="757810">it</span> <span m="757970">is</span> <span m="758380">certainly,</span>
  <span m="758930">I</span> <span m="759000">think,</span> <span m="759260">one</span>
  <span m="759480">of</span> <span m="759580">the</span> <span m="759780">really</span>
  <span m="760030">great</span> <span m="760190">examples</span> <span m="760650">of</span>
  <span m="760750">where</span> <span m="760830">applied</span> <span m="761120">methods</span>
  <span m="761530">made</span> <span m="761810">enormous</span> <span m="762260">impact</span>
  <span m="763280">on</span> <span m="763910">real</span> <span m="764070">problems</span>
  <span m="764740">and</span> <span m="765260">particularly</span> <span m="765680">on</span>
  <span m="765800">engineering</span> <span m="766440">and</span> <span m="766550">engineering</span>
  <span m="766990">design.</span> <span m="770050">So</span> <span m="770390">let''s</span>
  <span m="770970">get</span> <span m="771290">into</span> <span m="771650">talking</span>
  <span m="772020">about</span> <span m="772560">how</span> <span m="773350">it</span>
  <span m="773550">works.</span> <span m="774260">We''re</span> <span m="774270">going</span>
  <span m="774400">to</span> <span m="774480">talk</span> <span m="774790">about</span>
  <span m="775280">1D</span> <span m="775680">linear</span> <span m="775970">elements.</span>
  <span m="776910">I''m</span> <span m="777070">just</span> <span m="777150">going</span>
  <span m="777270">to</span> <span m="777330">go</span> <span m="777510">over</span>
  <span m="777700">a</span> <span m="777750">few</span> <span m="777960">things</span>
  <span m="778380">that</span> <span m="779270">you</span> <span m="779430">guys</span>
  <span m="779780">read</span> <span m="780010">about</span> <span m="780500">just</span>
  <span m="780670">to</span> <span m="780750">make</span> <span m="780940">sure</span>
  <span m="781310">that</span> <span m="781580">the</span> <span m="781670">notation</span>
  <span m="782310">is</span> <span m="782420">clear</span> <span m="783000">and</span>
  <span m="783370">that</span> <span m="783530">the</span> <span m="783650">ideas</span>
  <span m="784030">are</span> <span m="784080">clear.</span> <span m="784640">And</span>
  <span m="784790">then</span> <span m="784910">we''re</span> <span m="784990">going</span>
  <span m="785110">to</span> <span m="785200">start</span> <span m="786310">together</span>
  <span m="787470">deriving</span> <span m="787950">and</span> <span m="788030">implementing</span>
  <span m="790330">the</span> <span m="790430">methods</span> <span m="790820">for</span>
  <span m="790940">the</span> <span m="791020">1D</span> <span m="791410">diffusion</span>
  <span m="791800">equation.</span></p><p><span m="799330">So</span> <span m="799500">we''re</span>
  <span m="799640">at</span> <span m="799730">number</span> <span m="799980">three.</span>
  <span m="802980">1D</span> <span m="803480">linear</span> <span m="803980">elements.</span>
  <span m="809920">OK.</span> <span m="810330">So</span> <span m="810530">I''m just</span>
  <span m="810630">going</span> <span m="810770">to</span> <span m="810880">draw</span>
  <span m="811510">a</span> <span m="812680">picture.</span> <span m="814790">And</span>
  <span m="815160">again</span> <span m="815340">this</span> <span m="815480">is</span>
  <span m="815550">the</span> <span m="815630">picture</span> <span m="815950">that</span>
  <span m="816130">was</span> <span m="816300">in</span> <span m="816420">the</span>
  <span m="816550">online</span> <span m="817000">reading.</span> <span m="819100">Board</span>
  <span m="819520">is</span> <span m="819660">not</span> <span m="819810">very</span>
  <span m="820040">clean.</span> <span m="827130">All</span> <span m="827230">right.</span>
  <span m="827460">So</span> <span m="827590">we''re</span> <span m="827690">thinking</span>
  <span m="828000">in</span> <span m="828140">1D.</span> <span m="829796">So</span>
  <span m="830254">draw</span> <span m="831630">this</span> <span m="833110">line</span>
  <span m="833460">that''s</span> <span m="833630">going</span> <span m="833750">to</span>
  <span m="833820">go</span> <span m="834600">in</span> <span m="834830">both</span>
  <span m="835090">directions.</span> <span m="835790">So</span> <span m="835890">this</span>
  <span m="835930">is</span> <span m="836020">the</span> <span m="836140">x</span>
  <span m="836380">direction.</span> <span m="838100">And</span> <span m="839740">I''m</span>
  <span m="839850">going</span> <span m="839970">to</span> <span m="840030">have</span>
  <span m="840220">nodes</span> <span m="840880">just</span> <span m="841070">like</span>
  <span m="841300">I</span> <span m="841380">had</span> <span m="841700">in</span>
  <span m="841900">finite</span> <span m="842250">difference.</span> <span m="844210">So
  I draw</span> <span m="844370">some</span> <span m="844510">nodes.</span> <span
  m="848260">This</span> <span m="848460">guy</span> <span m="848730">here</span>
  <span m="849060">is</span> <span m="849200">going</span> <span m="849320">to</span>
  <span m="849400">be</span> <span m="851110">node i.</span> <span m="853936">And</span>
  <span m="854410">this</span> <span m="854540">guy</span> <span m="854720">here</span>
  <span m="854930">is</span> <span m="855060">going</span> <span m="855190">to</span>
  <span m="855270">be</span> <span m="855390">node</span> <span m="855660">i</span>
  <span m="855830">plus one.</span> <span m="856942">So</span> <span m="857324">node</span>
  <span m="857706">i is</span> <span m="858090">located</span> <span m="858560">in</span>
  <span m="858985">at</span> <span m="859350">position</span> <span m="859810">xi.</span>
  <span m="861130">Node</span> <span m="861230">i plus</span> <span m="861510">one</span>
  <span m="862140">is</span> <span m="862740">located</span> <span m="863160">at</span>
  <span m="863300">position</span> <span m="863700">xi</span> <span m="864110">plus</span>
  <span m="864410">one.</span> <span m="865470">i minus one</span> <span m="866180">to</span>
  <span m="866280">the</span> <span m="866360">left</span> <span m="866840">and</span>
  <span m="867230">so</span> <span m="867510">on.</span></p><p><span m="868820">And</span>
  <span m="868980">then</span> <span m="869130">in</span> <span m="869470">between</span>
  <span m="869980">xi</span> <span m="870480">and xi</span> <span m="870690">plus</span>
  <span m="870910">one</span> <span m="871160">is</span> <span m="871460">element</span>
  <span m="871900">i.</span> <span m="873313">OK?</span> <span m="873784">So</span>
  <span m="875200">when</span> <span m="875350">we</span> <span m="875440">talk</span>
  <span m="875650">about</span> <span m="875940">element</span> <span m="876370">i,</span>
  <span m="877280">we''re</span> <span m="877410">talking</span> <span m="877620">about</span>
  <span m="877830">the</span> <span m="877920">region</span> <span m="878210">of</span>
  <span m="878300">the</span> <span m="878370">domain</span> <span m="879210">that</span>
  <span m="879410">lies</span> <span m="879840">between</span> <span m="881190">xi</span>
  <span m="881890">and</span> <span m="882030">xi</span> <span m="882440">plus</span>
  <span m="882610">one.</span> <span m="883510">And--</span></p>'
type: course
uid: 62c18c90f3799ce6175ed05989576c0c

---
None