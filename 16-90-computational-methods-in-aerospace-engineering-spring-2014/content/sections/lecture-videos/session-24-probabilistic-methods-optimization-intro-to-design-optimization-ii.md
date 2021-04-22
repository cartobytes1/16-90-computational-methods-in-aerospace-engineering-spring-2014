---
about_this_resource_text: <p><strong>Description:</strong> This session continues
  the discussion of design optimization, including unconstrained optimization algorithms.
  The instructor then covers computing gradients, the 1D search, surrogate models
  and least squares fitting a response surface.</p> <p><strong>Instructor:</strong>
  Karen Willcox</p><p>The recording quality of this video is the best available from
  the source.</p>
course_id: 16-90-computational-methods-in-aerospace-engineering-spring-2014
embedded_media:
- id: Video-YouTube-Stream
  media_location: 1SY0C9IfyeU
  parent_uid: 47ffea42d4f2e6dfdc2a41e8d4e19d81
  title: Video-YouTube-Stream
  type: Video
  uid: 8b013104aaa4658324af4fdc842f3511
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/1SY0C9IfyeU/default.jpg
  parent_uid: 47ffea42d4f2e6dfdc2a41e8d4e19d81
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: bdf12a13a94190bc0f2dc130e300d6dc
- id: 3Play-3PlayYouTubeid-MP4
  media_location: 1SY0C9IfyeU
  parent_uid: 47ffea42d4f2e6dfdc2a41e8d4e19d81
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 211464f4c666d5c74dbf59ecc9770986
- id: 1SY0C9IfyeU.srt
  parent_uid: 47ffea42d4f2e6dfdc2a41e8d4e19d81
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-24-probabilistic-methods-optimization-intro-to-design-optimization-ii/1SY0C9IfyeU.srt
  title: 3play caption file
  type: null
  uid: 6adc5566e8faf584cff20ef39911768c
- id: 1SY0C9IfyeU.pdf
  parent_uid: 47ffea42d4f2e6dfdc2a41e8d4e19d81
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-24-probabilistic-methods-optimization-intro-to-design-optimization-ii/1SY0C9IfyeU.pdf
  title: 3play pdf file
  type: null
  uid: 68ed2f2eaefc9deb714ae03fccb7dc32
- id: Caption-3Play YouTube id-SRT
  parent_uid: 47ffea42d4f2e6dfdc2a41e8d4e19d81
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: b8f77b08b823cde6a6a5c32b931c70b8
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 47ffea42d4f2e6dfdc2a41e8d4e19d81
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: d30ad2a7e1a025e5e645a84736260aa1
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT16.90S14/MIT16_90S14_L24_300k.mp4
  parent_uid: 47ffea42d4f2e6dfdc2a41e8d4e19d81
  title: Video-Internet Archive-MP4
  type: Video
  uid: be585f936390b402e13614223ee471ee
inline_embed_id: 15713307session24:probabilisticmethods&optimization:introtodesignoptimizationii2536321
layout: video
order_index: null
parent_uid: 809ebf7c44bfb36e8786306747d7e32f
related_resources_text: ''
short_url: session-24-probabilistic-methods-optimization-intro-to-design-optimization-ii
technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-24-probabilistic-methods-optimization-intro-to-design-optimization-ii
template_type: Tabbed
title: 'Session 24: Probabilistic Methods & Optimization: Intro to design optimization
  II'
transcript: '<p><span m="30">The</span> <span m="130">following</span> <span m="600">content</span>
  <span m="1090">is</span> <span m="1210">provided</span> <span m="1660">under</span>
  <span m="1900">a</span> <span m="1950">Creative</span> <span m="2400">Commons</span>
  <span m="2820">license.</span> <span m="3780">Your</span> <span m="3880">support</span>
  <span m="4400">will</span> <span m="4560">help</span> <span m="4790">MIT</span>
  <span m="5280">OpenCourseWare</span> <span m="6020">continue</span> <span m="6510">to</span>
  <span m="6680">offer</span> <span m="6980">high</span> <span m="7200">quality</span>
  <span m="7680">educational</span> <span m="8350">resources</span> <span m="8920">for</span>
  <span m="9040">free.</span> <span m="10100">To</span> <span m="10130">make</span>
  <span m="10330">a</span> <span m="10380">donation</span> <span m="11090">or</span>
  <span m="11310">to</span> <span m="11430">view</span> <span m="11630">additional</span>
  <span m="12050">materials</span> <span m="12670">from</span> <span m="12850">hundreds</span>
  <span m="13180">of</span> <span m="13280">MIT</span> <span m="13650">courses,</span>
  <span m="14960">visit</span> <span m="15150">MIT</span> <span m="15670">OpenCourseWare</span>
  <span m="16580">at</span> <span m="16920">ocw.mit.edu.</span></p><p><span m="31220">KAREN
  WILLCOX: OK</span> <span m="31780">everybody,</span> <span m="32119">let''s</span>
  <span m="32350">get</span> <span m="32680">started.</span> <span m="35250">So</span>
  <span m="35400">if you</span> <span m="35500">came</span> <span m="35670">in late,</span>
  <span m="36090">project</span> <span m="36740">three</span> <span m="37210">is</span>
  <span m="37600">here.</span> <span m="38130">It''s</span> <span m="38230">graded</span>
  <span m="38550">in</span> <span m="38700">here.</span> <span m="40630">You''re</span>
  <span m="40910">going to have</span> <span m="40960">project</span> <span m="41320">two</span>
  <span m="41480">back</span> <span m="42590">tomorrow.</span> <span m="43770">Yeah.</span></p><p><span
  m="47940">The</span> <span m="48050">project</span> <span m="48380">threes</span>
  <span m="48710">were</span> <span m="48840">really</span> <span m="49110">good.</span>
  <span m="49650">The</span> <span m="49730">one</span> <span m="50190">thing</span>
  <span m="50430">that</span> <span m="50660">seemed</span> <span m="50820">to</span>
  <span m="50880">trip</span> <span m="51150">up--</span> <span m="51330">well,</span>
  <span m="51440">there</span> <span m="51660">was</span> <span m="51840">a</span>
  <span m="51900">few</span> <span m="52070">things</span> <span m="52260">that</span>
  <span m="52350">tripped</span> <span m="52560">up</span> <span m="52680">some</span>
  <span m="52840">people,</span> <span m="53100">but</span> <span m="53270">the</span>
  <span m="53350">one</span> <span m="53540">thing</span> <span m="53700">that</span>
  <span m="53840">seemed to</span> <span m="54270">trip up</span> <span m="54580">a
  few</span> <span m="54770">people</span> <span m="55790">was</span> <span m="55920">just</span>
  <span m="56210">the</span> <span m="56450">computation</span> <span m="57150">of</span>
  <span m="57250">the</span> <span m="57350">number</span> <span m="57780">of</span>
  <span m="57900">samples</span> <span m="58380">given</span> <span m="58580">the</span>
  <span m="58650">Monte</span> <span m="58850">Carlo</span> <span m="59220">simulation</span>
  <span m="60120">to</span> <span m="60450">achieve</span> <span m="61080">the</span>
  <span m="62090">required</span> <span m="62880">stated</span> <span m="63230">accuracy</span>
  <span m="63710">of</span> <span m="63880">plus or</span> <span m="64160">minus</span>
  <span m="64560">.01</span> <span m="65470">on</span> <span m="65590">the</span>
  <span m="65670">probability</span> <span m="66260">estimate.</span></p><p><span
  m="67655">So</span> <span m="68120">some</span> <span m="68320">people</span> <span
  m="68530">got</span> <span m="68720">it</span> <span m="68930">really</span> <span
  m="69190">well.</span> <span m="69760">Some</span> <span m="69840">people</span>
  <span m="70500">got</span> <span m="70760">it,</span> <span m="70930">but</span>
  <span m="71150">their</span> <span m="71430">explanations</span> <span m="72130">were</span>
  <span m="72260">a</span> <span m="72350">little</span> <span m="72610">bit</span>
  <span m="73460">muddled</span> <span m="74080">in</span> <span m="74270">some</span>
  <span m="74410">of their</span> <span m="74570">words.</span> <span m="74820">And
  then</span> <span m="75020">some</span> <span m="75150">people</span> <span m="75540">didn''t</span>
  <span m="75850">get</span> <span m="75960">it</span> <span m="76060">quite</span>
  <span m="76320">right.</span> <span m="77340">And</span> <span m="78120">I</span>
  <span m="78230">think</span> <span m="78430">it''s</span> <span m="78670">a</span>
  <span m="78730">really</span> <span m="78940">important</span> <span m="79400">thing,</span>
  <span m="79890">and</span> <span m="79990">it''s</span> <span m="80000">really</span>
  <span m="80160">important</span> <span m="80450">thing</span> <span m="80610">to</span>
  <span m="80710">make</span> <span m="80960">sure</span> <span m="81340">it''s</span>
  <span m="81540">very</span> <span m="81830">clear</span> <span m="82220">in</span>
  <span m="82350">your</span> <span m="82550">mind.</span></p><p><span m="83970">And</span>
  <span m="85480">one</span> <span m="85700">thing</span> <span m="85860">that</span>
  <span m="85990">I</span> <span m="86130">would</span> <span m="86290">recommend</span>
  <span m="86770">is</span> <span m="86900">that</span> <span m="87030">whenever</span>
  <span m="87280">you''re</span> <span m="87380">talking</span> <span m="87660">about</span>
  <span m="87960">mean</span> <span m="88460">and</span> <span m="88730">variance</span>
  <span m="89390">or</span> <span m="89490">mean</span> <span m="89650">and standard</span>
  <span m="90080">variation</span> <span m="91400">that</span> <span m="91560">you</span>
  <span m="91640">make</span> <span m="91800">sure</span> <span m="91930">it''s</span>
  <span m="92040">very</span> <span m="92230">clear</span> <span m="92510">in</span>
  <span m="92570">your</span> <span m="92670">mind</span> <span m="93130">of</span>
  <span m="93280">which</span> <span m="93500">random</span> <span m="93940">variable</span>
  <span m="94350">you''re</span> <span m="94450">talking</span> <span m="94760">about,</span>
  <span m="95600">because</span> <span m="95840">just</span> <span m="96000">saying</span>
  <span m="96420">mean</span> <span m="96830">or</span> <span m="96930">just</span>
  <span m="97100">saying</span> <span m="97460">variance</span> <span m="99490">doesn''t</span>
  <span m="99530">necessarily</span> <span m="99990">tell</span> <span m="100830">me</span>
  <span m="101140">or</span> <span m="101450">you</span> <span m="101950">anything</span>
  <span m="102640">when</span> <span m="102830">there''s</span> <span m="102990">lots</span>
  <span m="103190">of</span> <span m="103260">variances</span> <span m="103910">floating</span>
  <span m="104270">around.</span></p><p><span m="105560">In</span> <span m="105730">this</span>
  <span m="107760">particular</span> <span m="108100">example,</span> <span m="108740">there''s</span>
  <span m="108880">the</span> <span m="108920">variance</span> <span m="109330">of</span>
  <span m="109400">the</span> <span m="109530">output</span> <span m="110140">of</span>
  <span m="110260">the</span> <span m="110340">simulation</span> <span m="111620">that</span>
  <span m="111730">we''re</span> <span m="111820">trying</span> <span m="112070">to</span>
  <span m="112180">estimate,</span> <span m="112790">which</span> <span m="112990">is</span>
  <span m="113080">how</span> <span m="113190">far</span> <span m="113440">the</span>
  <span m="113510">ball</span> <span m="113930">flies.</span> <span m="115340">So
  how</span> <span m="115740">far the</span> <span m="115820">ball</span> <span m="116040">flies</span>
  <span m="116510">is a</span> <span m="116630">random</span> <span m="116920">variable</span>
  <span m="117370">that''s</span> <span m="117540">got</span> <span m="117670">its</span>
  <span m="117800">own</span> <span m="118000">variance.</span> <span m="119410">But</span>
  <span m="119530">then</span> <span m="119680">the</span> <span m="119760">probability</span>
  <span m="120510">estimates</span> <span m="121280">themselves</span> <span m="122190">have</span>
  <span m="122320">got</span> <span m="122510">variances</span> <span m="123270">because</span>
  <span m="123520">the</span> <span m="123590">probability</span> <span m="124170">estimates</span>
  <span m="124710">are</span> <span m="124810">random</span> <span m="125130">variables</span>
  <span m="126440">because</span> <span m="126680">you''re</span> <span m="126780">estimating</span>
  <span m="127350">them</span> <span m="127480">using</span> <span m="127720">Monte</span>
  <span m="127820">Carlo,</span> <span m="128150">which</span> <span m="128350">is
  a</span> <span m="128440">random</span> <span m="128810">process.</span></p><p><span
  m="130030">So</span> <span m="130210">when</span> <span m="130410">you''re</span>
  <span m="130570">asked</span> <span m="132840">to</span> <span m="133130">get</span>
  <span m="133370">the</span> <span m="135870">probability</span> <span m="136740">estimate</span>
  <span m="137890">to</span> <span m="138030">within</span> <span m="138590">plus
  or</span> <span m="138930">minus</span> <span m="139580">0.01</span> <span m="141390">with</span>
  <span m="142280">99%</span> <span m="143510">confidence,</span> <span m="147320">then</span>
  <span m="147500">that</span> <span m="147790">says</span> <span m="148510">we</span>
  <span m="148660">want</span> <span m="148830">to</span> <span m="148900">look</span>
  <span m="149240">at</span> <span m="149540">the</span> <span m="150340">variance</span>
  <span m="151370">of</span> <span m="151700">the</span> <span m="151790">probability</span>
  <span m="152380">estimate.</span> <span m="153130">How</span> <span m="153270">much</span>
  <span m="153510">does</span> <span m="153600">the</span> <span m="153670">probability</span>
  <span m="154170">estimate</span> <span m="154485">itself</span> <span m="155690">vary?</span>
  <span m="156770">And the</span> <span m="157270">variance</span> <span m="157950">of</span>
  <span m="158130">that</span> <span m="158540">estimator--</span> <span m="158950">so
  what''s</span> <span m="159360">that</span> <span m="159540">estimator?</span> <span
  m="160030">Let''s</span> <span m="160200">call it</span> <span m="160570">p</span>
  <span m="160840">hat</span> <span m="161970">is</span> <span m="162130">the</span>
  <span m="162260">estimator</span> <span m="162650">of</span> <span m="162730">the</span>
  <span m="162800">probability.</span> <span m="164160">Well,</span> <span m="164290">we</span>
  <span m="164400">know</span> <span m="164550">that</span> <span m="164730">saying</span>
  <span m="165170">by</span> <span m="165340">the central</span> <span m="165570">limit</span>
  <span m="165930">theorem, it''s</span> <span m="166290">distributed</span> <span
  m="167040">as</span> <span m="167180">a</span> <span m="167230">normal</span> <span
  m="168720">distribution</span> <span m="169710">with</span> <span m="170020">mean</span>
  <span m="170420">equal</span> <span m="170920">to</span> <span m="172480">the</span>
  <span m="172590">probability</span> <span m="173280">that</span> <span m="173430">we''re</span>
  <span m="173890">actually</span> <span m="174250">trying</span> <span m="174800">to</span>
  <span m="176100">estimate,</span> <span m="177240">and</span> <span m="177450">variance</span>
  <span m="178230">of</span> <span m="178640">that</span> <span m="178850">probability</span>
  <span m="179790">p</span> <span m="180010">of</span> <span m="180100">a,</span>
  <span m="182220">1</span> <span m="182530">minus</span> <span m="182860">p of</span>
  <span m="183335">a</span> <span m="187610">over</span> <span m="187880">n.</span>
  <span m="189798">Yup.</span></p><p><span m="190274">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="197414">KAREN WILLCOX: We''ll also</span> <span m="197890">put the lights on.</span>
  <span m="198410">That</span> <span m="198480">will</span> <span m="198826">help.</span>
  <span m="199520">Do you</span> <span m="199850">mind going</span> <span m="200180">into</span>
  <span m="200430">my</span> <span m="201740">office</span> <span m="202080">and</span>
  <span m="202180">grabbing</span> <span m="202460">some of</span> <span m="202590">the</span>
  <span m="202680">big</span> <span m="202870">chalk</span> <span m="203130">that''s</span>
  <span m="203340">on--</span> <span m="204735">great,</span> <span m="205200">thanks.</span>
  <span m="206130">I</span> <span m="206230">hate</span> <span m="206430">the</span>
  <span m="206540">little</span> <span m="206760">chalk.</span> <span m="207170">We''ll</span>
  <span m="207580">get some</span> <span m="207990">bigger</span> <span m="208330">chalk.</span>
  <span m="209590">Can you</span> <span m="210010">see a bit</span> <span m="210150">better</span>
  <span m="210470">now?</span> <span m="211370">So</span> <span m="212270">this</span>
  <span m="212400">is</span> <span m="213310">the</span> <span m="213410">variance,</span>
  <span m="214190">but</span> <span m="214340">it''s the</span> <span m="214650">variance</span>
  <span m="215150">of</span> <span m="215280">what?</span> <span m="215490">It''s</span>
  <span m="215610">the</span> <span m="215690">variance</span> <span m="216360">of</span>
  <span m="217260">this</span> <span m="217440">estimator,</span> <span m="218100">p</span>
  <span m="218350">hat of a,</span> <span m="218660">and</span> <span m="219020">this</span>
  <span m="219160">is</span> <span m="219260">the</span> <span m="219340">mean</span>
  <span m="219760">of</span> <span m="219980">p</span> <span m="220120">hat</span>
  <span m="220280">of</span> <span m="220350">a.</span></p><p><span m="221140">So
  again,</span> <span m="221480">just</span> <span m="221690">any</span> <span m="221870">time</span>
  <span m="222080">you</span> <span m="222190">write</span> <span m="222450">variance,</span>
  <span m="223140">variance</span> <span m="223540">of</span> <span m="223660">what?</span>
  <span m="224140">Variance of what</span> <span m="224620">random</span> <span m="224920">variable?</span>
  <span m="226180">And</span> <span m="227080">I</span> <span m="227120">sort</span>
  <span m="227280">of</span> <span m="227530">got</span> <span m="227700">the</span>
  <span m="227770">feeling</span> <span m="228010">some</span> <span m="228150">people</span>
  <span m="228350">who</span> <span m="228700">knew</span> <span m="229010">it</span>
  <span m="229400">had</span> <span m="229520">to</span> <span m="229580">be</span>
  <span m="229720">this</span> <span m="229930">thing,</span> <span m="230280">but</span>
  <span m="230640">with</span> <span m="231310">defining</span> <span m="231710">this</span>
  <span m="231800">thing</span> <span m="232130">as</span> <span m="232280">the</span>
  <span m="232320">variance,</span> <span m="233760">and</span> <span m="233880">then</span>
  <span m="234020">just</span> <span m="234560">randomly</span> <span m="235600">or</span>
  <span m="235940">magically</span> <span m="236440">dividing</span> <span m="236800">by</span>
  <span m="236970">n,</span> <span m="237150">but</span> <span m="237340">make</span>
  <span m="237550">sure</span> <span m="237750">that</span> <span m="237860">this</span>
  <span m="238440">is</span> <span m="238620">really</span> <span m="239210">clear</span>
  <span m="239500">in</span> <span m="239570">your</span> <span m="239700">mind</span>
  <span m="240610">that</span> <span m="240770">the</span> <span m="240830">estimator</span>
  <span m="241420">itself</span> <span m="241800">is</span> <span m="241900">a</span>
  <span m="241970">random</span> <span m="242240">variable.</span> <span m="242940">And
  then</span> <span m="243380">in</span> <span m="243660">order</span> <span m="243890">to</span>
  <span m="244010">figure</span> <span m="244270">out</span> <span m="244330">how</span>
  <span m="244470">many</span> <span m="244630">samples</span> <span m="245060">you</span>
  <span m="245160">take,</span> <span m="245620">we''ve got</span> <span m="245840">to</span>
  <span m="245910">control</span> <span m="246340">the</span> <span m="246420">variance</span>
  <span m="247130">of</span> <span m="248160">the</span> <span m="248540">estimator.</span>
  <span m="249800">And</span> <span m="249980">then</span> <span m="250160">because</span>
  <span m="250430">we</span> <span m="250540">know</span> <span m="250670">this</span>
  <span m="250830">thing</span> <span m="250990">is</span> <span m="251130">normally</span>
  <span m="251480">distributed,</span> <span m="252595">and</span> <span m="252860">we</span>
  <span m="253040">want</span> <span m="253250">99%</span> <span m="253600">confidence,</span>
  <span m="254410">that''s</span> <span m="254970">plus</span> <span m="255270">or</span>
  <span m="255340">minus</span> <span m="255630">3</span> <span m="255800">sigma</span>
  <span m="256110">or</span> <span m="256476">plus or</span> <span m="256842">minus</span>
  <span m="257209">2.58,</span> <span m="258145">some of you</span> <span m="258470">computed,</span>
  <span m="259860">so</span> <span m="259970">we</span> <span m="260050">need</span>
  <span m="260200">to</span> <span m="260269">make</span> <span m="260540">sure</span>
  <span m="260779">that</span> <span m="261100">this</span> <span m="262850">sigma,</span>
  <span m="263380">square root</span> <span m="263750">of</span> <span m="263840">this</span>
  <span m="265590">times</span> <span m="266200">3</span> <span m="266510">or</span>
  <span m="266610">times</span> <span m="266910">2.58</span> <span m="268426">falls</span>
  <span m="268850">within</span> <span m="269030">plus</span> <span m="269280">or</span>
  <span m="269520">minus--</span> <span m="271530">is</span> <span m="271710">less</span>
  <span m="271920">than</span> <span m="272150">0.01.</span></p><p><span m="273244">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="276960">KAREN WILLCOX: Less than</span> <span
  m="277270">here?</span></p><p><span m="277626">AUDIENCE: Yeah.</span></p><p><span
  m="278340">KAREN WILLCOX: So</span> <span m="278450">that''s</span> <span m="278740">through
  the</span> <span m="278910">central</span> <span m="279370">limit</span> <span m="279610">theorem,</span>
  <span m="281650">because</span> <span m="281990">we</span> <span m="282090">know</span>
  <span m="282310">that</span> <span m="282670">we</span> <span m="282790">can</span>
  <span m="282970">write</span> <span m="283230">the</span> <span m="283420">estimate</span>
  <span m="283920">of</span> <span m="283980">the</span> <span m="284050">probability--</span>
  <span m="287240">remember,</span> <span m="287530">we</span> <span m="287640">could</span>
  <span m="287870">write</span> <span m="288050">it</span> <span m="288180">as</span>
  <span m="288370">1</span> <span m="288550">over</span> <span m="289000">n,</span>
  <span m="289450">the</span> <span m="289900">sum</span> <span m="290365">from</span>
  <span m="290830">i equals 1</span> <span m="291295">to</span> <span m="291760">n</span>
  <span m="292280">of</span> <span m="292820">i</span> <span m="293490">of</span>
  <span m="294410">ai.</span></p><p><span m="296954">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="302738">KAREN WILLCOX: Yeah,</span> <span m="303510">so</span> <span m="303600">this</span>
  <span m="303890">is</span> <span m="303990">another</span> <span m="304440">important</span>
  <span m="304810">thing</span> <span m="305050">to</span> <span m="305380">keep</span>
  <span m="305730">in</span> <span m="305820">mind</span> <span m="306070">is</span>
  <span m="306230">the</span> <span m="306370">output</span> <span m="306710">itself</span>
  <span m="307170">doesn''t</span> <span m="307400">have</span> <span m="307550">to</span>
  <span m="307630">be</span> <span m="307720">normally</span> <span m="308090">distributed,</span>
  <span m="309310">but</span> <span m="309450">the</span> <span m="309520">estimator</span>
  <span m="310160">for</span> <span m="310280">the</span> <span m="310430">probability</span>
  <span m="312620">does</span> <span m="312800">have</span> <span m="312920">a</span>
  <span m="312970">normal</span> <span m="313780">distribution.</span> <span m="314480">And</span>
  <span m="314490">the</span> <span m="314580">reason</span> <span m="314850">it</span>
  <span m="314950">does</span> <span m="315320">is</span> <span m="315490">because</span>
  <span m="316310">we</span> <span m="316460">can</span> <span m="316600">write</span>
  <span m="316840">it</span> <span m="317360">as--</span> <span m="318686">this</span>
  <span m="319130">is</span> <span m="319210">like</span> <span m="319370">a</span>
  <span m="319420">sample</span> <span m="319860">mean</span> <span m="320140">of</span>
  <span m="320220">an</span> <span m="320320">indicator</span> <span m="320850">function,</span>
  <span m="321330">something</span> <span m="321560">that''s</span> <span m="321840">either</span>
  <span m="321920">0</span> <span m="322410">or</span> <span m="322900">1.</span>
  <span m="323710">And so</span> <span m="323950">by</span> <span m="324010">central</span>
  <span m="324190">limit</span> <span m="324350">theorem,</span> <span m="324760">this</span>
  <span m="324920">thing</span> <span m="326230">for</span> <span m="326430">big</span>
  <span m="326710">enough</span> <span m="326930">n</span> <span m="327270">has</span>
  <span m="327570">a</span> <span m="327920">normal</span> <span m="328230">distribution.</span></p><p><span
  m="328690">The</span> <span m="328770">same</span> <span m="329090">is</span> <span
  m="329280">true</span> <span m="329660">for</span> <span m="331000">the</span> <span
  m="331090">estimator</span> <span m="331530">for</span> <span m="331650">the</span>
  <span m="331800">mean,</span> <span m="333070">because</span> <span m="333390">that''s</span>
  <span m="334560">1</span> <span m="334700">over</span> <span m="334830">n,</span>
  <span m="336030">the</span> <span m="336140">sum</span> <span m="336490">from</span>
  <span m="336650">i equal</span> <span m="337120">1</span> <span m="338230">to</span>
  <span m="338350">n--</span> <span m="338770">then we called this</span> <span m="338840">thing</span>
  <span m="339060">y,</span> <span m="339250">but</span> <span m="339380">I</span>
  <span m="339440">think</span> <span m="339590">we</span> <span m="339680">called
  it</span> <span m="339920">y bar</span> <span m="340120">in the</span> <span m="340556">notes.</span>
  <span m="342740">The</span> <span m="342840">distribution</span> <span m="343560">of</span>
  <span m="343860">y</span> <span m="344140">bar,</span> <span m="344890">the</span>
  <span m="345030">estimator</span> <span m="345330">for</span> <span m="345480">the</span>
  <span m="345540">mean</span> <span m="345910">also</span> <span m="346300">has</span>
  <span m="346420">a</span> <span m="346460">normal</span> <span m="346720">distribution.</span>
  <span m="348442">So</span> <span m="348850">remember,</span> <span m="349150">we</span>
  <span m="349260">saw</span> <span m="349490">estimators</span> <span m="350210">for</span>
  <span m="350540">mean,</span> <span m="351310">for</span> <span m="351440">probability,</span>
  <span m="352280">and</span> <span m="352720">for</span> <span m="353015">variance.</span>
  <span m="354260">These</span> <span m="354560">two</span> <span m="354790">have</span>
  <span m="355080">normal</span> <span m="355330">distributions</span> <span m="356120">regardless</span>
  <span m="356780">of</span> <span m="357310">the</span> <span m="357400">distribution</span>
  <span m="357900">of</span> <span m="357970">the</span> <span m="358100">output,</span>
  <span m="359290">but</span> <span m="359430">the</span> <span m="359610">variance</span>
  <span m="360150">doesn''t.</span> <span m="361650">Is</span> <span m="361900">that</span>
  <span m="362100">clear?</span></p><p><span m="363420">And</span> <span m="363620">again,</span>
  <span m="363780">that''s</span> <span m="364000">why</span> <span m="364140">I</span>
  <span m="364200">think</span> <span m="364380">it''s</span> <span m="364530">important</span>
  <span m="364810">to</span> <span m="364930">say</span> <span m="365050">variance</span>
  <span m="365640">of</span> <span m="365770">what,</span> <span m="366160">or</span>
  <span m="366310">distribution</span> <span m="366500">of</span> <span m="366590">what.</span>
  <span m="366930">This</span> <span m="367090">is</span> <span m="367530">the</span>
  <span m="367640">distribution</span> <span m="368230">of</span> <span m="368390">the</span>
  <span m="368480">random</span> <span m="368810">variable,</span> <span m="369660">which</span>
  <span m="369750">is</span> <span m="369880">the</span> <span m="370050">estimator</span>
  <span m="370600">of</span> <span m="370780">the</span> <span m="370850">probability.</span>
  <span m="372360">It''s</span> <span m="373620">sort</span> <span m="373790">of</span>
  <span m="373870">got</span> <span m="374020">nothing--</span> <span m="374320">it''s</span>
  <span m="374470">got</span> <span m="374540">nothing</span> <span m="374780">to</span>
  <span m="374850">do</span> <span m="375040">with</span> <span m="375200">the</span>
  <span m="375270">variance</span> <span m="375820">of</span> <span m="376730">the</span>
  <span m="376840">range</span> <span m="377080">of</span> <span m="377140">the</span>
  <span m="377220">ball</span> <span m="377485">in</span> <span m="377750">this</span>
  <span m="378217">case,</span> <span m="379620">or</span> <span m="379750">even</span>
  <span m="379880">the</span> <span m="379960">shape</span> <span m="380200">of</span>
  <span m="380350">the</span> <span m="380440">distribution.</span> <span m="381870">But</span>
  <span m="381930">what</span> <span m="382050">it</span> <span m="382190">does</span>
  <span m="382510">depend</span> <span m="382930">on</span> <span m="383160">is</span>
  <span m="383410">the</span> <span m="383630">probability</span> <span m="383930">we''re</span>
  <span m="384140">trying to</span> <span m="384280">estimate.</span> <span m="385950">And</span>
  <span m="386225">so</span> <span m="388510">we</span> <span m="388680">use</span>
  <span m="388870">this</span> <span m="389070">result</span> <span m="389680">to</span>
  <span m="389790">figure</span> <span m="390100">out</span> <span m="390340">how</span>
  <span m="390430">many</span> <span m="390580">samples</span> <span m="390960">to</span>
  <span m="391060">take,</span> <span m="391340">but</span> <span m="391620">we</span>
  <span m="391730">don''t</span> <span m="391960">have</span> <span m="392160">an</span>
  <span m="392280">estimate</span> <span m="392700">for</span> <span m="392810">this</span>
  <span m="392990">guy.</span></p><p><span m="393372">So</span> <span m="394520">a</span>
  <span m="394780">trick</span> <span m="395060">that</span> <span m="396780">helps</span>
  <span m="397030">people</span> <span m="397350">realize</span> <span m="397630">is</span>
  <span m="397910">that</span> <span m="398120">we</span> <span m="398240">know</span>
  <span m="398430">the</span> <span m="398530">worst</span> <span m="398910">case</span>
  <span m="399210">for</span> <span m="399320">this.</span> <span m="400030">So</span>
  <span m="400170">what</span> <span m="400320">value</span> <span m="400620">of</span>
  <span m="400780">p</span> <span m="401050">will</span> <span m="401230">give</span>
  <span m="401410">us</span> <span m="402430">the</span> <span m="402550">biggest</span>
  <span m="402870">variance?</span> <span m="405860">p</span> <span m="406340">equal
  1/2?</span> <span m="408260">If</span> <span m="408750">p</span> <span m="409050">is</span>
  <span m="409180">1/2,</span> <span m="409680">this</span> <span m="410430">1/2</span>
  <span m="410740">times</span> <span m="411005">1/2</span> <span m="411650">is</span>
  <span m="411790">0.25.</span> <span m="412480">That''s</span> <span m="412650">the</span>
  <span m="412910">biggest</span> <span m="413200">value</span> <span m="413500">that</span>
  <span m="413680">p1</span> <span m="413985">minus</span> <span m="414290">p</span>
  <span m="414410">can</span> <span m="414600">take.</span> <span m="416380">There''s</span>
  <span m="416840">0</span> <span m="416900">at</span> <span m="417200">either</span>
  <span m="417480">end</span> <span m="418156">and</span> <span m="418990">0.25</span>
  <span m="419520">in</span> <span m="419580">the</span> <span m="419650">middle.</span></p><p><span
  m="420620">So</span> <span m="421130">one</span> <span m="421440">strategy</span>
  <span m="422050">is</span> <span m="422270">to</span> <span m="422400">compute</span>
  <span m="422690">this</span> <span m="423410">using</span> <span m="423820">p equal</span>
  <span m="424270">1/2,</span> <span m="424590">which</span> <span m="424760">is</span>
  <span m="424860">the</span> <span m="424950">worst</span> <span m="425270">case,</span>
  <span m="427210">and</span> <span m="427410">I</span> <span m="427470">would</span>
  <span m="427600">just</span> <span m="427760">do</span> <span m="427900">plus or</span>
  <span m="428200">minus</span> <span m="428490">3</span> <span m="428680">sigma.</span>
  <span m="429420">It''s a little bit</span> <span m="429820">conservative,</span>
  <span m="430470">and</span> <span m="430560">that</span> <span m="430720">gives</span>
  <span m="430910">you</span> <span m="430980">something</span> <span m="431440">like</span>
  <span m="432340">22,500</span> <span m="434590">is</span> <span m="434770">the n</span>
  <span m="435080">that</span> <span m="435300">you need.</span> <span m="436120">And</span>
  <span m="436530">then you</span> <span m="436670">know you''ll</span> <span m="437070">be</span>
  <span m="437230">OK</span> <span m="437570">for</span> <span m="437740">anything.</span>
  <span m="438670">And</span> <span m="438720">it</span> <span m="438800">turns</span>
  <span m="439030">out</span> <span m="439190">one</span> <span m="439340">of</span>
  <span m="439410">them,</span> <span m="439490">the</span> <span m="439990">probability</span>
  <span m="440560">came</span> <span m="440770">out</span> <span m="440880">to be</span>
  <span m="441090">like</span> <span m="441270">0.52</span> <span m="441790">or</span>
  <span m="442190">something.</span> <span m="443130">And</span> <span m="443260">that</span>
  <span m="443430">would</span> <span m="443540">be</span> <span m="443630">the</span>
  <span m="443720">worst</span> <span m="443970">case,</span> <span m="444270">and</span>
  <span m="444360">you''d</span> <span m="444460">be</span> <span m="444530">a</span>
  <span m="444620">little</span> <span m="444800">bit</span> <span m="445000">conservative</span>
  <span m="445355">here,</span> <span m="446210">but</span> <span m="446380">that''s</span>
  <span m="446590">fine.</span> <span m="446930">You''d still</span> <span m="447060">be</span>
  <span m="447150">meeting</span> <span m="447420">your</span> <span m="447490">plus</span>
  <span m="447720">or</span> <span m="447830">minus</span> <span m="448100">0.01.</span></p><p><span
  m="452430">So</span> <span m="452600">just</span> <span m="452830">make</span> <span
  m="453120">sure</span> <span m="453390">make</span> <span m="453570">sure</span>
  <span m="453720">that</span> <span m="453840">that''s</span> <span m="454070">really</span>
  <span m="454410">clear</span> <span m="454810">in your</span> <span m="454950">mind</span>
  <span m="456020">as</span> <span m="456190">you</span> <span m="456280">go</span>
  <span m="456470">through</span> <span m="456880">how</span> <span m="458260">you</span>
  <span m="458390">take</span> <span m="458690">all</span> <span m="458780">these</span>
  <span m="458940">different</span> <span m="459230">pieces</span> <span m="459520">that</span>
  <span m="459620">you''re</span> <span m="459720">clear</span> <span m="460050">about,</span>
  <span m="460960">the</span> <span m="461060">distribution</span> <span m="461630">and</span>
  <span m="461740">what</span> <span m="461960">is</span> <span m="462140">normally</span>
  <span m="462520">distributed</span> <span m="463030">and</span> <span m="463130">what</span>
  <span m="463260">isn''t,</span> <span m="464330">and</span> <span m="464480">then</span>
  <span m="464650">you</span> <span m="464760">can</span> <span m="464960">work</span>
  <span m="465230">from</span> <span m="465480">this</span> <span m="465650">variance</span>
  <span m="466620">to</span> <span m="467110">identifying</span> <span m="467840">the</span>
  <span m="468940">plus or</span> <span m="469170">minus</span> <span m="469430">3</span>
  <span m="469610">sigma</span> <span m="469930">to</span> <span m="470300">give</span>
  <span m="470670">99%</span> <span m="470860">confidence</span> <span m="471120">and</span>
  <span m="471380">then</span> <span m="471490">translate</span> <span m="471900">that</span>
  <span m="472800">into</span> <span m="473050">an</span> <span m="473210">n.</span></p><p><span
  m="474780">OK.</span> <span m="475110">So if you</span> <span m="475510">didn''t</span>
  <span m="475830">get</span> <span m="475970">it</span> <span m="476030">quite</span>
  <span m="476230">right,</span> <span m="476450">take</span> <span m="476660">a</span>
  <span m="476700">look</span> <span m="476860">at</span> <span m="476930">it.</span>
  <span m="477030">And</span> <span m="477120">then</span> <span m="477250">if</span>
  <span m="477390">it''s</span> <span m="477690">not</span> <span m="477880">clear,</span>
  <span m="478550">I''m</span> <span m="478990">going</span> <span m="479130">to</span>
  <span m="479200">do</span> <span m="480040">sort of</span> <span m="480190">a</span>
  <span m="480290">summary</span> <span m="480720">of</span> <span m="480820">everything</span>
  <span m="481200">on</span> <span m="481480">Wednesday,</span> <span m="481980">and</span>
  <span m="482090">we</span> <span m="482170">can</span> <span m="482580">go</span>
  <span m="482760">through</span> <span m="483000">it again</span> <span m="483290">in
  more</span> <span m="483580">detail</span> <span m="483760">then</span> <span m="483940">if</span>
  <span m="484030">you</span> <span m="484100">want to.</span> <span m="485080">And</span>
  <span m="485190">I''ll also</span> <span m="485470">post some</span> <span m="485860">solutions</span>
  <span m="487640">tonight</span> <span m="487970">or tomorrow.</span> <span m="490740">But</span>
  <span m="490880">any</span> <span m="491460">other</span> <span m="491650">questions?</span></p><p><span
  m="498630">OK.</span> <span m="499200">So</span> <span m="500900">today</span> <span
  m="501230">we''re</span> <span m="501400">going</span> <span m="501670">to</span>
  <span m="501780">finish</span> <span m="502190">talking</span> <span m="502730">about</span>
  <span m="505275">unconstrained</span> <span m="506230">optimization.</span> <span
  m="506970">We''ll</span> <span m="507110">just</span> <span m="507160">pick</span>
  <span m="507460">up</span> <span m="507670">where</span> <span m="507860">we</span>
  <span m="507970">left</span> <span m="508270">off</span> <span m="508660">on</span>
  <span m="509420">last</span> <span m="509780">Wednesday.</span> <span m="512669">And</span>
  <span m="513400">we''ll</span> <span m="513559">talk a</span> <span m="513690">lot</span>
  <span m="513809">about</span> <span m="514260">how</span> <span m="514450">we</span>
  <span m="514570">compute</span> <span m="515000">gradients.</span> <span m="516520">We</span>
  <span m="516640">might</span> <span m="516840">talk</span> <span m="517020">a</span>
  <span m="517070">bit</span> <span m="517200">about</span> <span m="517409">the</span>
  <span m="517480">1D</span> <span m="517750">search</span> <span m="518169">if we</span>
  <span m="518299">have</span> <span m="518460">time.</span> <span m="519580">And</span>
  <span m="519780">then</span> <span m="519860">we''ll</span> <span m="519980">finish</span>
  <span m="520299">up</span> <span m="520419">by</span> <span m="520539">talking</span>
  <span m="520900">about</span> <span m="521400">response</span> <span m="521779">surface</span>
  <span m="522159">modelling.</span></p><p><span m="527150">If you</span> <span m="527290">remember</span>
  <span m="527920">where</span> <span m="528280">we</span> <span m="530020">left</span>
  <span m="530370">off</span> <span m="530820">last</span> <span m="531230">Wednesday,</span>
  <span m="539830">so</span> <span m="540310">first</span> <span m="540590">up,</span>
  <span m="541110">this</span> <span m="541280">is</span> <span m="541410">a</span>
  <span m="541470">basic</span> <span m="542070">optimization</span> <span m="542730">problem</span>
  <span m="542970">we''ve</span> <span m="543090">been</span> <span m="543220">talking</span>
  <span m="543540">about.</span> <span m="543840">Remember,</span> <span m="544140">minimize</span>
  <span m="544720">some</span> <span m="544850">objective</span> <span m="545460">j</span>
  <span m="546420">that''s</span> <span m="546610">a</span> <span m="546660">function</span>
  <span m="547050">of</span> <span m="547230">design</span> <span m="547630">variables</span>
  <span m="548180">x,</span> <span m="549010">and</span> <span m="549150">we</span>
  <span m="549250">have</span> <span m="549870">x1,</span> <span m="550190">x2,</span>
  <span m="550430">up</span> <span m="550540">to</span> <span m="550978">xn</span>
  <span m="553170">design</span> <span m="553510">variables.</span> <span m="554540">Parameters</span>
  <span m="555015">p</span> <span m="557030">subject</span> <span m="557560">to</span>
  <span m="558010">inequality</span> <span m="558590">constraints</span> <span m="559290">that</span>
  <span m="559420">we</span> <span m="559560">write</span> <span m="560000">as</span>
  <span m="560440">dJ</span> <span m="560730">is</span> <span m="561020">less</span>
  <span m="561290">than or</span> <span m="561370">equal to</span> <span m="561650">0,</span>
  <span m="562540">and</span> <span m="562910">equality</span> <span m="563280">constraints</span>
  <span m="563770">that</span> <span m="563890">we</span> <span m="564020">write</span>
  <span m="564295">as</span> <span m="564570">hk</span> <span m="565470">equal</span>
  <span m="565810">to</span> <span m="565880">0.</span> <span m="566140">And in</span>
  <span m="566320">general,</span> <span m="566450">we</span> <span m="566770">might</span>
  <span m="566920">have</span> <span m="567160">m1</span> <span m="568290">inequality</span>
  <span m="568810">constraints</span> <span m="569360">and</span> <span m="569635">m2</span>
  <span m="569910">equality</span> <span m="570390">constraints,</span> <span m="570910">and
  then</span> <span m="571040">we</span> <span m="571160">might</span> <span m="571320">also</span>
  <span m="571550">have</span> <span m="571690">bounds</span> <span m="572470">on</span>
  <span m="572620">the</span> <span m="572700">design</span> <span m="573070">space.</span></p><p><span
  m="573960">So</span> <span m="574070">we</span> <span m="574140">saw</span> <span
  m="574380">this</span> <span m="574610">last</span> <span m="574880">Wednesday.</span>
  <span m="576140">And we</span> <span m="576310">also</span> <span m="576530">talked</span>
  <span m="576840">about</span> <span m="577800">the</span> <span m="577880">general</span>
  <span m="578200">process</span> <span m="579020">of</span> <span m="579790">optimization.</span>
  <span m="580550">And</span> <span m="580600">remember,</span> <span m="580890">I</span>
  <span m="580970">said</span> <span m="581200">think</span> <span m="581370">of</span>
  <span m="581450">it</span> <span m="581550">as</span> <span m="581660">a</span>
  <span m="581720">landscape</span> <span m="582660">where</span> <span m="582970">the</span>
  <span m="583050">directions</span> <span m="583510">in the</span> <span m="583970">landscape</span>
  <span m="584420">are the</span> <span m="584510">design</span> <span m="584860">variables,</span>
  <span m="585930">and</span> <span m="586070">the</span> <span m="586140">height</span>
  <span m="586830">of</span> <span m="587020">the</span> <span m="587080">landscape</span>
  <span m="587600">represents</span> <span m="588040">the</span> <span m="588120">objective</span>
  <span m="588490">function.</span> <span m="589480">If</span> <span m="589630">you''re</span>
  <span m="590150">maximizing,</span> <span m="590840">your</span> <span m="590930">goal</span>
  <span m="591240">is</span> <span m="591360">to</span> <span m="591440">get</span>
  <span m="591710">to</span> <span m="591820">the</span> <span m="591900">top</span>
  <span m="592160">of</span> <span m="592370">the</span> <span m="592800">highest</span>
  <span m="593350">mountain</span> <span m="593625">or</span> <span m="593900">highest</span>
  <span m="594245">hill</span> <span m="594590">in</span> <span m="594660">the</span>
  <span m="594730">landscape.</span> <span m="595250">If  you''re</span> <span m="595320">minimizing,</span>
  <span m="596020">your</span> <span m="596110">goal</span> <span m="596390">is</span>
  <span m="596550">to</span> <span m="596650">get</span> <span m="596880">to</span>
  <span m="597300">the</span> <span m="597400">bottom</span> <span m="597680">of</span>
  <span m="597780">the</span> <span m="597860">lowest</span> <span m="598230">valley.</span></p><p><span
  m="599390">And</span> <span m="599560">the</span> <span m="599590">way</span> <span
  m="599880">that that</span> <span m="600140">works</span> <span m="600600">is</span>
  <span m="600710">that</span> <span m="600980">we</span> <span m="601440">start with</span>
  <span m="601900">some</span> <span m="602090">initial</span> <span m="602440">guess</span>
  <span m="602780">that</span> <span m="603135">we denote</span> <span m="603490">x</span>
  <span m="604530">with</span> <span m="604660">a</span> <span m="604690">superscript</span>
  <span m="604985">0.</span> <span m="605630">That''s the</span> <span m="605820">initial</span>
  <span m="606480">guess.</span> <span m="607560">We</span> <span m="607710">look</span>
  <span m="607880">around.</span> <span m="609070">For</span> <span m="609200">a</span>
  <span m="609250">gradient-based</span> <span m="610070">method,</span> <span m="610490">we''re</span>
  <span m="610580">going to</span> <span m="610720">also</span> <span m="611050">compute</span>
  <span m="611540">the</span> <span m="611650">gradient</span> <span m="614050">of</span>
  <span m="614340">the</span> <span m="614450">objective</span> <span m="615960">of</span>
  <span m="616110">where</span> <span m="616300">we''re</span> <span m="616390">standing</span>
  <span m="616650">in</span> <span m="616760">the</span> <span m="616830">landscape.</span>
  <span m="618000">Look</span> <span m="618230">around,</span> <span m="618580">find</span>
  <span m="619620">the</span> <span m="619730">search</span> <span m="620030">direction.</span>
  <span m="621970">Once</span> <span m="622210">we''ve</span> <span m="622360">found</span>
  <span m="622530">that</span> <span m="622680">search</span> <span m="622900">direction,</span>
  <span m="623640">look</span> <span m="624000">along</span> <span m="624130">that</span>
  <span m="624290">search</span> <span m="624550">direction.</span> <span m="625250">Perform</span>
  <span m="625540">what''s</span> <span m="625830">called</span> <span m="626050">the</span>
  <span m="626130">1D</span> <span m="626470">search</span> <span m="626860">and</span>
  <span m="626970">take</span> <span m="627230">a</span> <span m="627520">step</span>
  <span m="627720">alpha.</span> <span m="629300">Compute</span> <span m="629720">a
  new</span> <span m="629930">design,</span> <span m="630570">figure</span> <span
  m="630800">out</span> <span m="630890">whether</span> <span m="631040">we''ve</span>
  <span m="631160">converged,</span> <span m="631650">and</span> <span m="631760">keep</span>
  <span m="631950">going.</span></p><p><span m="632280">So</span> <span m="632420">we''re</span>
  <span m="632540">walking</span> <span m="632870">around</span> <span m="633180">the</span>
  <span m="633260">landscape</span> <span m="635510">iterating</span> <span m="636170">with</span>
  <span m="636566">our</span> <span m="637780">design</span> <span m="638210">variables.</span>
  <span m="639310">And</span> <span m="639600">what</span> <span m="639710">we</span>
  <span m="639800">talked</span> <span m="640040">about</span> <span m="640290">on</span>
  <span m="640380">Wednesday</span> <span m="640830">was</span> <span m="641090">the</span>
  <span m="641330">steepest</span> <span m="641400">descent</span> <span m="641790">method,</span>
  <span m="642200">which</span> <span m="642480">says</span> <span m="642630">always</span>
  <span m="642900">choose</span> <span m="643460">the</span> <span m="643600">search</span>
  <span m="643890">direction</span> <span m="644490">to</span> <span m="644620">be</span>
  <span m="644850">the</span> <span m="645500">negative</span> <span m="645855">of</span>
  <span m="646630">gradient</span> <span m="646940">of</span> <span m="647040">j.</span>
  <span m="647400">So</span> <span m="647520">that''s</span> <span m="647710">the</span>
  <span m="647790">direction</span> <span m="648100">of</span> <span m="648200">steepest</span>
  <span m="648580">descent.</span> <span m="649630">And</span> <span m="649810">we</span>
  <span m="649980">also</span> <span m="650150">saw</span> <span m="650460">conjugate</span>
  <span m="650900">gradient,</span> <span m="651540">where</span> <span m="651670">we</span>
  <span m="651780">modify</span> <span m="652310">the</span> <span m="652410">search</span>
  <span m="652700">direction</span> <span m="653130">according</span> <span m="653560">to</span>
  <span m="653720">where</span> <span m="654330">we</span> <span m="654460">have</span>
  <span m="654600">come</span> <span m="654890">from.</span> <span m="655820">And</span>
  <span m="656020">remember</span> <span m="656330">that</span> <span m="656510">we</span>
  <span m="656890">saw</span> <span m="657990">that</span> <span m="658380">steepest</span>
  <span m="658580">descent--</span> <span m="659870">in</span> <span m="660050">this</span>
  <span m="660190">plot</span> <span m="660690">where</span> <span m="660810">the</span>
  <span m="660880">objective</span> <span m="661200">function</span> <span m="662050">is</span>
  <span m="662260">represented</span> <span m="662650">with</span> <span m="662780">the</span>
  <span m="662850">contours,</span> <span m="663940">the</span> <span m="664050">steepest</span>
  <span m="664400">descent</span> <span m="665130">direction</span> <span m="665570">is</span>
  <span m="665720">always</span> <span m="666090">perpendicular</span> <span m="666680">to</span>
  <span m="666760">the</span> <span m="666820">contours.</span> <span m="667930">And</span>
  <span m="668020">we</span> <span m="668120">saw</span> <span m="668340">that</span>
  <span m="668450">as</span> <span m="668630">we</span> <span m="668740">approached</span>
  <span m="669060">the</span> <span m="669180">optimum,</span> <span m="669830">steepest</span>
  <span m="670100">descent</span> <span m="670670">starts</span> <span m="670950">to
  take</span> <span m="671380">this</span> <span m="671665">zig-zagging</span> <span
  m="671950">path</span> <span m="672250">with</span> <span m="672430">really,</span>
  <span m="672740">really</span> <span m="672840">small</span> <span m="673130">steps.</span>
  <span m="674350">Whereas</span> <span m="674640">conjugate</span> <span m="674920">gradient,</span>
  <span m="675720">which</span> <span m="676040">modifies</span> <span m="676810">each</span>
  <span m="677030">search</span> <span m="677340">direction</span> <span m="677980">depending</span>
  <span m="678360">on</span> <span m="678500">the</span> <span m="678570">previous</span>
  <span m="679030">search</span> <span m="679280">direction,</span> <span m="680400">is</span>
  <span m="680520">able</span> <span m="680780">to</span> <span m="680890">converge</span>
  <span m="681640">much</span> <span m="681870">more</span> <span m="682030">quickly.</span>
  <span m="682470">And</span> <span m="682640">in</span> <span m="682700">this</span>
  <span m="682810">case,</span> <span m="683030">it''s</span> <span m="683160">just</span>
  <span m="683720">[? a quick consideration. ?]</span></p><p><span m="685620">OK,</span>
  <span m="685870">so</span> <span m="686140">that''s</span> <span m="686320">where</span>
  <span m="686470">we</span> <span m="686850">are</span> <span m="687130">stopped</span>
  <span m="687560">on</span> <span m="687710">Wednesday.</span> <span m="689120">So</span>
  <span m="689200">I</span> <span m="689260">want</span> <span m="689420">to</span>
  <span m="689480">mention</span> <span m="689860">just</span> <span m="690140">really</span>
  <span m="690330">quickly</span> <span m="691860">a</span> <span m="691920">couple</span>
  <span m="692240">other</span> <span m="692540">methods.</span> <span m="693900">So</span>
  <span m="694080">if</span> <span m="694180">I</span> <span m="694260">go</span>
  <span m="694440">back</span> <span m="694990">actually,</span> <span m="696780">we</span>
  <span m="696910">talked</span> <span m="697140">about</span> <span m="697380">first</span>
  <span m="697700">order</span> <span m="697940">method</span> <span m="698360">that</span>
  <span m="698540">use</span> <span m="698730">just</span> <span m="698900">gradient</span>
  <span m="699210">information,</span> <span m="699890">and</span> <span m="699980">that</span>
  <span m="700110">was</span> <span m="700280">steepest</span> <span m="700560">descent</span>
  <span m="700790">and</span> <span m="700870">conjugate</span> <span m="701310">gradient.</span>
  <span m="702300">So</span> <span m="702420">there are</span> <span m="702580">also</span>
  <span m="702890">second</span> <span m="703340">order</span> <span m="703540">method</span>
  <span m="704230">that</span> <span m="704510">use</span> <span m="705510">not</span>
  <span m="705720">just</span> <span m="705920">the</span> <span m="705990">first</span>
  <span m="706340">derivative,</span> <span m="707430">but</span> <span m="707590">also</span>
  <span m="707830">second</span> <span m="708160">derivative</span> <span m="708460">information.</span>
  <span m="709040">And</span> <span m="709180">remember,</span> <span m="709580">we</span>
  <span m="709710">also</span> <span m="709970">derived</span> <span m="710280">on</span>
  <span m="710420">Wednesday</span> <span m="710850">that</span> <span m="710990">the</span>
  <span m="711120">second</span> <span m="711450">derivative</span> <span m="712690">of</span>
  <span m="713380">j</span> <span m="714240">is</span> <span m="714510">an</span>
  <span m="714690">n</span> <span m="714930">by</span> <span m="715130">n</span> <span
  m="715250">matrix.</span> <span m="716040">That</span> <span m="716160">was</span>
  <span m="716290">the</span> <span m="716500">Hessian</span> <span m="716810">matrix,</span>
  <span m="717240">the</span> <span m="717300">matrix</span> <span m="717650">of</span>
  <span m="717740">second</span> <span m="718060">derivative</span> <span m="718500">that</span>
  <span m="718710">handled</span> <span m="718790">the</span> <span m="718860">pure</span>
  <span m="719230">second</span> <span m="719660">on</span> <span m="719780">the</span>
  <span m="719870">diagonal,</span> <span m="720950">and</span> <span m="721110">then</span>
  <span m="721250">all</span> <span m="721390">the</span> <span m="722070">cross</span>
  <span m="722375">terms</span> <span m="722680">on</span> <span m="723030">the off</span>
  <span m="723380">diagonals.</span></p><p><span m="724658">So</span> <span m="725084">how</span>
  <span m="725510">does</span> <span m="725840">Newton''s</span> <span m="726470">method</span>
  <span m="726990">work?</span> <span m="727400">Well,</span> <span m="729120">if</span>
  <span m="729270">you</span> <span m="729330">think</span> <span m="729490">about</span>
  <span m="729650">a</span> <span m="729740">Taylor</span> <span m="730080">series--</span>
  <span m="730610">and</span> <span m="730730">again,</span> <span m="731150">we</span>
  <span m="731280">derived</span> <span m="731560">this</span> <span m="731640">on</span>
  <span m="731880">Wednesday.</span> <span m="733070">The</span> <span m="733180">Taylor</span>
  <span m="733510">series</span> <span m="734170">in</span> <span m="734480">the</span>
  <span m="734630">case</span> <span m="735120">of</span> <span m="735300">a</span>
  <span m="735360">scalar</span> <span m="735930">objective</span> <span m="737250">that</span>
  <span m="737430">depends</span> <span m="737900">on</span> <span m="738240">a</span>
  <span m="738320">vector</span> <span m="739320">of</span> <span m="739480">design</span>
  <span m="739800">variables,</span> <span m="740300">so</span> <span m="740420">x
  is an</span> <span m="740920">n-dimensional</span> <span m="741720">vector.</span>
  <span m="742270">If</span> <span m="742600">we</span> <span m="742930">expand</span>
  <span m="743300">j</span> <span m="743670">of</span> <span m="743850">x</span> <span
  m="744110">about</span> <span m="744560">the</span> <span m="744650">point</span>
  <span m="745680">j</span> <span m="746140">of</span> <span m="746920">x0,</span>
  <span m="748150">then</span> <span m="748310">the</span> <span m="748380">first</span>
  <span m="748870">term</span> <span m="749400">is</span> <span m="750450">the</span>
  <span m="750540">gradient</span> <span m="751970">times</span> <span m="752570">delta</span>
  <span m="752880">x.</span> <span m="753295">Delta x</span> <span m="753710">is x</span>
  <span m="754080">minus</span> <span m="754270">x0.</span> <span m="755600">And</span>
  <span m="755720">then</span> <span m="755810">remember,</span> <span m="756110">the</span>
  <span m="756180">second</span> <span m="756550">term</span> <span m="756810">was</span>
  <span m="757010">this</span> <span m="757070">quadratic</span> <span m="757630">term</span>
  <span m="757740">that</span> <span m="758080">looked</span> <span m="758310">like</span>
  <span m="758645">delta x</span> <span m="758980">transposed</span> <span m="759450">times</span>
  <span m="759895">the Hessian</span> <span m="760460">times</span> <span m="760710">delta</span>
  <span m="761090">x.</span> <span m="762230">Remember,</span> <span m="762510">we</span>
  <span m="762870">did</span> <span m="763010">that</span> <span m="763110">on</span>
  <span m="763260">Wednesday.</span></p><p><span m="764880">And</span> <span m="765180">this</span>
  <span m="765300">is</span> <span m="765400">an</span> <span m="765480">approximation,</span>
  <span m="766230">because</span> <span m="766530">we''re</span> <span m="766640">truncating</span>
  <span m="767240">all</span> <span m="767320">the</span> <span m="767390">third</span>
  <span m="767650">order</span> <span m="767910">terms</span> <span m="768350">and</span>
  <span m="768630">higher.</span> <span m="770138">So</span> <span m="771066">we can</span>
  <span m="771530">use this</span> <span m="771970">Taylor</span> <span m="772370">series</span>
  <span m="772590">expansion,</span> <span m="773220">and</span> <span m="773350">we</span>
  <span m="773460">can</span> <span m="773710">say,</span> <span m="774830">differentiate</span>
  <span m="775490">both</span> <span m="775710">sides.</span> <span m="776832">So</span>
  <span m="778190">grad</span> <span m="778605">J</span> <span m="779020">of x</span>
  <span m="779880">can</span> <span m="780030">be</span> <span m="780240">approximated</span>
  <span m="780930">by</span> <span m="781180">grad</span> <span m="781665">J of</span>
  <span m="782150">x0</span> <span m="782996">plus the</span> <span m="783420">Hessian</span>
  <span m="784920">evaluated</span> <span m="785050">at</span> <span m="785480">x0</span>
  <span m="786000">times</span> <span m="786488">delta</span> <span m="786976">x.</span>
  <span m="788440">Yeah.</span> <span m="789030">And</span> <span m="789190">what</span>
  <span m="789310">are</span> <span m="789370">we</span> <span m="789490">looking</span>
  <span m="789770">for?</span> <span m="790090">We''re</span> <span m="790100">looking</span>
  <span m="790320">for</span> <span m="790460">a</span> <span m="790530">place</span>
  <span m="790850">with</span> <span m="790970">the</span> <span m="791010">gradient</span>
  <span m="791350">of</span> <span m="791440">j is</span> <span m="791890">0.</span>
  <span m="792430">Remember,</span> <span m="793090">that</span> <span m="793230">was</span>
  <span m="793410">the</span> <span m="793530">condition</span> <span m="794160">for</span>
  <span m="794300">finding</span> <span m="794640">a</span> <span m="794690">minimum</span>
  <span m="795220">or a</span> <span m="795360">maximum,</span> <span m="796840">or</span>
  <span m="797230">it</span> <span m="797620">could</span> <span m="797820">also be</span>
  <span m="798090">a</span> <span m="798150">saddle</span> <span m="798480">point.</span></p><p><span
  m="799310">So</span> <span m="799510">if</span> <span m="799650">we</span> <span
  m="800140">set</span> <span m="800360">this</span> <span m="800490">left</span>
  <span m="800800">hand side</span> <span m="801200">equal</span> <span m="801440">to</span>
  <span m="801610">0,</span> <span m="802830">then</span> <span m="803560">what''s</span>
  <span m="803950">left</span> <span m="804320">is</span> <span m="805220">this</span>
  <span m="805440">condition</span> <span m="805850">here.</span> <span m="807260">And</span>
  <span m="807400">so</span> <span m="807490">now</span> <span m="807680">we</span>
  <span m="807800">can</span> <span m="807990">rearrange</span> <span m="808660">and</span>
  <span m="808860">say</span> <span m="809030">that</span> <span m="809190">the</span>
  <span m="809280">delta</span> <span m="809650">x,</span> <span m="810910">the</span>
  <span m="811120">step</span> <span m="811590">that</span> <span m="811750">we</span>
  <span m="811870">take</span> <span m="813210">is</span> <span m="813400">going</span>
  <span m="813710">to</span> <span m="813820">be</span> <span m="815100">the</span>
  <span m="815240">inverse</span> <span m="815750">of</span> <span m="815860">the</span>
  <span m="815960">Hessian</span> <span m="817550">at</span> <span m="817680">the</span>
  <span m="817760">point</span> <span m="818020">we''re</span> <span m="818300">standing</span>
  <span m="818580">at</span> <span m="819530">times</span> <span m="820010">the</span>
  <span m="820080">gradient</span> <span m="820740">of</span> <span m="822320">the</span>
  <span m="822470">objective</span> <span m="822990">at</span> <span m="823090">that</span>
  <span m="823250">point</span> <span m="824120">with</span> <span m="824210">a</span>
  <span m="824270">minus</span> <span m="824570">sign.</span> <span m="826180">OK,</span>
  <span m="826490">so</span> <span m="826590">remember</span> <span m="828575">[INAUDIBLE]</span>
  <span m="829250">in the</span> <span m="829525">steepest</span> <span m="830000">descent</span>
  <span m="833800">method,</span> <span m="835080">we</span> <span m="835240">said</span>
  <span m="835410">that</span> <span m="835580">the</span> <span m="835690">search</span>
  <span m="836110">direction</span> <span m="836590">was</span> <span m="837065">just
  equal</span> <span m="837540">to</span> <span m="837600">minus</span> <span m="837860">grad</span>
  <span m="838120">J.</span> <span m="842422">And we''re</span> <span m="842900">writing</span>
  <span m="843378">that</span> <span m="844334">x</span> <span m="844812">at</span>
  <span m="845290">q</span> <span m="846246">plus</span> <span m="846730">1</span>
  <span m="848160">is</span> <span m="848380">equal</span> <span m="848700">to</span>
  <span m="849830">x</span> <span m="850760">at</span> <span m="851225">q</span> <span
  m="852155">plus</span> <span m="852620">alpha</span> <span m="853550">q--</span>
  <span m="854480">let me</span> <span m="854945">write that</span> <span m="855410">as
  a</span> <span m="855500">subscript--</span> <span m="856922">times</span> <span
  m="857870">[? x ?]</span> <span m="859770">q.</span></p><p><span m="865710">OK.</span>
  <span m="865940">So</span> <span m="866060">that''s</span> <span m="866780">what</span>
  <span m="866930">we''ve</span> <span m="867560">been</span> <span m="867790">saying</span>
  <span m="868120">is</span> <span m="868230">that</span> <span m="868440">the</span>
  <span m="869600">new</span> <span m="869920">guess</span> <span m="870240">of the</span>
  <span m="870380">design</span> <span m="871070">is</span> <span m="871160">the</span>
  <span m="871280">old</span> <span m="871470">one</span> <span m="871880">plus</span>
  <span m="872080">[INAUDIBLE]</span> <span m="872490">term.</span> <span m="873960">In</span>
  <span m="874450">the</span> <span m="874610">steepest</span> <span m="874720">descent</span>
  <span m="875260">method,</span> <span m="876140">where</span> <span m="876290">it''s</span>
  <span m="876450">just</span> <span m="876660">minus</span> <span m="877092">gradient
  of</span> <span m="877524">J.</span> <span m="877956">So</span> <span m="878390">now</span>
  <span m="878540">you</span> <span m="878620">can</span> <span m="878800">see</span>
  <span m="878950">with</span> <span m="879140">Newton''s</span> <span m="879600">method,</span>
  <span m="880850">we</span> <span m="881320">have</span> <span m="881650">that</span>
  <span m="881770">the</span> <span m="881850">delta</span> <span m="882160">x,</span>
  <span m="882760">which</span> <span m="883000">is</span> <span m="883140">this</span>
  <span m="883240">guy</span> <span m="883460">here,</span> <span m="884070">the</span>
  <span m="884180">alpha q</span> <span m="884620">times</span> <span m="885800">[?
  this ?]</span> <span m="885900">[? direction ?]</span> <span m="886165">[? s ?]</span>
  <span m="886430">q</span> <span m="887520">is</span> <span m="887780">the</span>
  <span m="888270">negative</span> <span m="888750">of the</span> <span m="888910">inverse</span>
  <span m="889330">of</span> <span m="889400">the</span> <span m="889480">Hessian</span>
  <span m="889920">times</span> <span m="890200">gradient</span> <span m="890677">of
  J.</span></p><p><span m="892108">AUDIENCE: [INAUDIBLE]</span></p><p><span m="896878">KAREN
  WILLCOX: Yeah,</span> <span m="897355">so we''ll have</span> <span m="897832">to
  check</span> <span m="898309">that</span> <span m="898800">when</span> <span m="899070">we</span>
  <span m="899190">converge,</span> <span m="900634">when</span> <span m="901052">we</span>
  <span m="901470">get</span> <span m="901720">to--</span> <span m="906157">we''ll</span>
  <span m="906650">check that</span> <span m="907143">on convergence.</span> <span
  m="909620">Yeah.</span> <span m="910970">Typically you</span> <span m="911400">don''t</span>
  <span m="911560">check it</span> <span m="911925">as you</span> <span m="912290">go</span>
  <span m="912470">along,</span> <span m="912940">but</span> <span m="914460">it</span>
  <span m="914960">actually</span> <span m="915200">depends</span> <span m="915460">a</span>
  <span m="915510">little</span> <span m="915690">bit</span> <span m="915810">on</span>
  <span m="915910">the</span> <span m="915970">algorithm.</span> <span m="916320">The</span>
  <span m="916670">next ones that</span> <span m="916970">you''ll</span> <span m="917140">see,</span>
  <span m="917840">you''ll</span> <span m="917990">see</span> <span m="918120">that</span>
  <span m="918270">the</span> <span m="919060">desire</span> <span m="919370">for</span>
  <span m="919470">Hessian</span> <span m="919530">to</span> <span m="919850">be</span>
  <span m="919950">positive</span> <span m="920330">definite</span> <span m="920730">is</span>
  <span m="921850">worked</span> <span m="922321">in.</span></p><p><span m="926090">OK,</span>
  <span m="926340">so</span> <span m="926470">how</span> <span m="926580">does</span>
  <span m="926720">Newton''s</span> <span m="927120">method</span> <span m="927540">work?</span>
  <span m="929050">This</span> <span m="929160">says</span> <span m="929430">S,</span>
  <span m="929800">but</span> <span m="929950">it</span> <span m="930050">really</span>
  <span m="930410">should</span> <span m="930640">be</span> <span m="930900">alpha</span>
  <span m="931380">times</span> <span m="931630">S</span> <span m="932270">in</span>
  <span m="932580">the</span> <span m="932650">way</span> <span m="932830">I</span>
  <span m="933190">defined</span> <span m="933600">the</span> <span m="933680">update</span>
  <span m="934080">in</span> <span m="934250">delta</span> <span m="934672">x.</span>
  <span m="935094">So</span> <span m="935940">maybe</span> <span m="936160">you can</span>
  <span m="936390">see</span> <span m="936520">that</span> <span m="936660">if</span>
  <span m="936770">you''re</span> <span m="936870">trying</span> <span m="937060">to</span>
  <span m="937190">optimize</span> <span m="937710">a</span> <span m="937760">quadratic</span>
  <span m="938450">function,</span> <span m="939680">this</span> <span m="939850">extension</span>
  <span m="940260">is</span> <span m="940910">exact.</span> <span m="941890">There''s</span>
  <span m="942050">no</span> <span m="942200">approximation</span> <span m="942830">here.</span>
  <span m="943820">And</span> <span m="944160">in</span> <span m="944230">that</span>
  <span m="944420">case,</span> <span m="944710">Newton''s</span> <span m="945030">method</span>
  <span m="945560">would</span> <span m="946720">converge</span> <span m="947190">in</span>
  <span m="947310">one</span> <span m="947560">step.</span> <span m="947820">So</span>
  <span m="948080">that</span> <span m="948300">means</span> <span m="948490">that</span>
  <span m="948580">if</span> <span m="948690">I</span> <span m="948870">was</span>
  <span m="949020">trying</span> <span m="949150">to</span> <span m="949220">optimize</span>
  <span m="949600">some</span> <span m="949770">kind</span> <span m="949910">of</span>
  <span m="949980">a</span> <span m="950020">quadratic</span> <span m="950630">function,</span>
  <span m="951030">or</span> <span m="951700">the</span> <span m="951810">landscape</span>
  <span m="952200">would</span> <span m="952320">be</span> <span m="952410">like</span>
  <span m="952590">a</span> <span m="952640">bowl,</span> <span m="953400">no</span>
  <span m="953520">matter</span> <span m="953730">where</span> <span m="953980">I</span>
  <span m="954080">started,</span> <span m="955270">I</span> <span m="955400">would</span>
  <span m="955570">get</span> <span m="955900">to</span> <span m="956050">the</span>
  <span m="956830">optimum</span> <span m="957300">in</span> <span m="957580">one</span>
  <span m="958210">step</span> <span m="958940">with</span> <span m="959380">Newton''s</span>
  <span m="959850">method.</span></p><p><span m="961260">But if</span> <span m="961730">the</span>
  <span m="961820">function''s</span> <span m="962350">not</span> <span m="962480">actually</span>
  <span m="962950">quadratic,</span> <span m="964410">then</span> <span m="966140">what</span>
  <span m="966280">we''re</span> <span m="966370">basically</span> <span m="966820">doing</span>
  <span m="967200">is</span> <span m="967670">computing</span> <span m="968060">an</span>
  <span m="968140">approximation</span> <span m="970160">of</span> <span m="970530">the</span>
  <span m="971120">function</span> <span m="972000">here</span> <span m="972580">as</span>
  <span m="972680">a</span> <span m="972720">quadratic.</span> <span m="974070">So</span>
  <span m="974440">however</span> <span m="974850">it</span> <span m="974920">would</span>
  <span m="975060">look,</span> <span m="975340">it</span> <span m="975420">would</span>
  <span m="975570">look</span> <span m="975820">maybe</span> <span m="976240">something</span>
  <span m="976500">like</span> <span m="976700">this,</span> <span m="976930">we''d</span>
  <span m="977060">be</span> <span m="977150">approximating</span> <span m="977800">here.</span>
  <span m="978160">We</span> <span m="978300">would</span> <span m="978530">solve</span>
  <span m="978810">Newton''s</span> <span m="979070">method.</span> <span m="979580">We</span>
  <span m="979610">would</span> <span m="979780">jump</span> <span m="980110">to</span>
  <span m="980210">there.</span> <span m="981300">We</span> <span m="981440">would</span>
  <span m="981580">create</span> <span m="981940">a</span> <span m="981990">new</span>
  <span m="982490">approximation</span> <span m="984190">locally</span> <span m="984640">that</span>
  <span m="984770">might</span> <span m="984930">look</span> <span m="985090">like</span>
  <span m="985290">this,</span> <span m="986120">and</span> <span m="986240">then</span>
  <span m="986340">we</span> <span m="986440">would</span> <span m="986600">come</span>
  <span m="986860">in and</span> <span m="987030">eventually</span> <span m="987560">we</span>
  <span m="987690">would</span> <span m="988580">converge.</span> <span m="989644">So</span>
  <span m="990056">if</span> <span m="990470">J is</span> <span m="990840">not</span>
  <span m="991080">quadratic,</span> <span m="992200">you</span> <span m="992600">just</span>
  <span m="992850">keep</span> <span m="993080">performing</span> <span m="993520">Taylor</span>
  <span m="993790">series,</span> <span m="994270">getting</span> <span m="994500">a</span>
  <span m="994550">new</span> <span m="994730">point,</span> <span m="995470">and</span>
  <span m="995610">then</span> <span m="995720">repeating</span> <span m="996180">until</span>
  <span m="996940">it''s</span> <span m="997220">converged.</span></p><p><span m="998410">So</span>
  <span m="998860">this turns</span> <span m="999070">out</span> <span m="999200">to</span>
  <span m="999290">be</span> <span m="999420">a</span> <span m="999480">really</span>
  <span m="999660">efficient</span> <span m="1000080">technique</span> <span m="1000430">if</span>
  <span m="1000550">you</span> <span m="1000630">start</span> <span m="1000970">near</span>
  <span m="1001150">the</span> <span m="1001230">solution,</span> <span m="1001750">if</span>
  <span m="1001860">you''re</span> <span m="1001970">starting</span> <span m="1002440">sort</span>
  <span m="1002560">of</span> <span m="1002650">close</span> <span m="1002990">to</span>
  <span m="1003100">one</span> <span m="1003260">of</span> <span m="1003340">the</span>
  <span m="1003710">local</span> <span m="1004820">bowls</span> <span m="1005170">of</span>
  <span m="1005270">attraction</span> <span m="1005720">if</span> <span m="1005830">you''re</span>
  <span m="1005950">minimizing.</span> <span m="1007140">But</span> <span m="1007290">the</span>
  <span m="1007370">problem</span> <span m="1007750">is</span> <span m="1007970">that</span>
  <span m="1008100">you</span> <span m="1008200">can</span> <span m="1008390">see</span>
  <span m="1008590">that</span> <span m="1008720">now</span> <span m="1008910">we</span>
  <span m="1009010">need</span> <span m="1009250">not</span> <span m="1009450">just</span>
  <span m="1009670">gradients,</span> <span m="1010350">but</span> <span m="1010700">we</span>
  <span m="1010840">need</span> <span m="1011040">also</span> <span m="1011780">the</span>
  <span m="1011900">second</span> <span m="1012190">derivative.</span> <span m="1012810">I''m</span>
  <span m="1012920">going</span> <span m="1013040">to</span> <span m="1013130">talk</span>
  <span m="1013520">in</span> <span m="1013670">a</span> <span m="1013720">second</span>
  <span m="1014120">about</span> <span m="1014810">how</span> <span m="1015010">to</span>
  <span m="1015100">estimate</span> <span m="1016780">the</span> <span m="1016860">gradients</span>
  <span m="1017300">even</span> <span m="1017490">if</span> <span m="1017650">is</span>
  <span m="1017780">actually</span> <span m="1018760">in</span> <span m="1018930">many</span>
  <span m="1019170">cases</span> <span m="1020860">getting</span> <span m="1021100">this</span>
  <span m="1021170">Hessian</span> <span m="1021870">ends up</span> <span m="1022220">to</span>
  <span m="1022310">be</span> <span m="1023070">much</span> <span m="1023340">too</span>
  <span m="1023440">expensive.</span></p><p><span m="1024865">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="1027240">KAREN WILLCOX: How</span> <span m="1027720">do we</span> <span m="1028069">define</span>
  <span m="1028410">convergence?</span></p><p><span m="1029069">AUDIENCE: [INAUDIBLE].</span>
  <span m="1030377">Yeah,</span> <span m="1030813">so</span> <span m="1031250">for</span>
  <span m="1031440">an</span> <span m="1031879">unconstrained</span> <span m="1032589">problem,</span>
  <span m="1032909">remember</span> <span m="1033280">we''re</span> <span m="1033380">looking</span>
  <span m="1033619">for</span> <span m="1033740">two</span> <span m="1034220">conditions.</span>
  <span m="1034750">We''re</span> <span m="1034829">looking</span> <span m="1035109">for</span>
  <span m="1035250">the</span> <span m="1035319">gradient</span> <span m="1035710">of</span>
  <span m="1035839">j</span> <span m="1036300">equal</span> <span m="1036550">to</span>
  <span m="1036650">0.</span> <span m="1037829">And</span> <span m="1038260">we''re</span>
  <span m="1038400">looking</span> <span m="1038650">for</span> <span m="1038750">Hessian</span>
  <span m="1038819">to</span> <span m="1039170">be</span> <span m="1039690">positive</span>
  <span m="1040050">definite.</span> <span m="1042630">Or</span> <span m="1042880">positive</span>
  <span m="1043310">semi-definite</span> <span m="1043970">depending</span> <span
  m="1044280">on</span> <span m="1044740">the</span> <span m="1045060">uniqueness.</span></p><p><span
  m="1047319">That''s</span> <span m="1047650">in</span> <span m="1047810">theory.
  It</span> <span m="1048300">turns</span> <span m="1048560">out</span> <span m="1048750">that</span>
  <span m="1048950">in</span> <span m="1049220">implementation,</span> <span m="1050010">it</span>
  <span m="1050100">can</span> <span m="1050280">be</span> <span m="1050370">a</span>
  <span m="1050450">little</span> <span m="1050620">bit</span> <span m="1050780">tricky</span>
  <span m="1052140">to</span> <span m="1053430">monitor</span> <span m="1053580">convergence.</span>
  <span m="1054320">So</span> <span m="1054790">often</span> <span m="1055950">you</span>
  <span m="1056130">would</span> <span m="1056870">look</span> <span m="1057290">for</span>
  <span m="1057720">the</span> <span m="1057810">sequence</span> <span m="1058350">of</span>
  <span m="1058450">the</span> <span m="1058510">design</span> <span m="1058840">variables</span>
  <span m="1059320">to</span> <span m="1059400">stop</span> <span m="1059650">changing.</span>
  <span m="1060150">In</span> <span m="1060260">other</span> <span m="1060380">words,</span>
  <span m="1060650">when the</span> <span m="1060750">updates</span> <span m="1061140">become</span>
  <span m="1061430">really</span> <span m="1061640">small.</span> <span m="1062700">And</span>
  <span m="1062810">that''s</span> <span m="1062980">when</span> <span m="1063090">you</span>
  <span m="1063160">would</span> <span m="1063340">terminate,</span> <span m="1063780">and</span>
  <span m="1063890">then</span> <span m="1064010">you</span> <span m="1064090">would</span>
  <span m="1064230">try</span> <span m="1064380">to</span> <span m="1064470">check</span>
  <span m="1064750">the</span> <span m="1064920">optimality</span> <span m="1065372">condition.</span></p><p><span
  m="1068540">So</span> <span m="1069630">let''s</span> <span m="1070830">talk</span>
  <span m="1071160">about</span> <span m="1071400">how</span> <span m="1071560">to</span>
  <span m="1071660">estimate</span> <span m="1072640">the</span> <span m="1072800">gradient.</span>
  <span m="1077520">And</span> <span m="1077640">this</span> <span m="1077850">actually</span>
  <span m="1078280">will</span> <span m="1083660">connect</span> <span m="1084110">back
  to</span> <span m="1084570">some</span> <span m="1084830">stuff</span> <span m="1085030">that</span>
  <span m="1085180">you</span> <span m="1085470">saw</span> <span m="1085780">earlier</span>
  <span m="1086240">in the</span> <span m="1086510">semester.</span> <span m="1091800">So
  we''re</span> <span m="1092010">onto</span> <span m="1092200">number</span> <span
  m="1092440">two,</span> <span m="1092740">which</span> <span m="1092980">is</span>
  <span m="1093130">computing</span> <span m="1093820">gradients.</span> <span m="1102814">So,</span>
  <span m="1104260">generally</span> <span m="1108010">we''re</span> <span m="1108420">going
  to</span> <span m="1108910">need</span> <span m="1111150">definitely</span> <span
  m="1111750">grad</span> <span m="1112155">j,</span> <span m="1112560">which</span>
  <span m="1112760">remember</span> <span m="1113110">was</span> <span m="1114620">the</span>
  <span m="1114720">partial</span> <span m="1117036">derivatives of</span> <span m="1117460">j</span>
  <span m="1117900">with</span> <span m="1118100">respect</span> <span m="1118360">to</span>
  <span m="1118620">all</span> <span m="1118870">of</span> <span m="1119050">the</span>
  <span m="1122100">design</span> <span m="1122570">variables.</span> <span m="1128470">And</span>
  <span m="1129670">we</span> <span m="1129840">might</span> <span m="1131130">need</span>
  <span m="1134380">the</span> <span m="1134876">second</span> <span m="1135372">derivatives.</span>
  <span m="1135870">If</span> <span m="1135970">we</span> <span m="1136040">wanted</span>
  <span m="1136180">to</span> <span m="1136280">do</span> <span m="1136480">the</span>
  <span m="1136570">Newton</span> <span m="1136820">method,</span> <span m="1138588">then</span>
  <span m="1139030">we</span> <span m="1139170">might</span> <span m="1139450">also</span>
  <span m="1139660">need</span> <span m="1139970">the</span> <span m="1140020">second</span>
  <span m="1140397">derivatives.</span> <span m="1140774">And I won''t</span> <span
  m="1141151">write it out,</span> <span m="1141530">but</span> <span m="1141550">again,</span>
  <span m="1141820">remember</span> <span m="1142020">that</span> <span m="1142190">was</span>
  <span m="1142615">the</span> <span m="1143040">n by n</span> <span m="1143465">matrix</span>
  <span m="1143890">of</span> <span m="1147940">second</span> <span m="1148860">order</span>
  <span m="1149820">partials.</span></p><p><span m="1151838">So</span> <span m="1154820">methods</span>
  <span m="1155290">to</span> <span m="1155430">compute</span> <span m="1155720">gradient.</span>
  <span m="1156280">Any</span> <span m="1156430">ideas?</span> <span m="1159556">Finite</span>
  <span m="1160010">difference,</span> <span m="1160450">yup.</span> <span m="1160730">So</span>
  <span m="1161107">that''s</span> <span m="1162240">finite</span> <span m="1162480">difference,</span>
  <span m="1163070">which</span> <span m="1163200">we''ll</span> <span m="1163710">talk</span>
  <span m="1163940">about.</span> <span m="1165490">That''s</span> <span m="1165740">probably</span>
  <span m="1166170">the</span> <span m="1166250">most</span> <span m="1166500">commonly</span>
  <span m="1166895">used</span> <span m="1167620">in</span> <span m="1167950">practice</span>
  <span m="1168430">that</span> <span m="1168570">people</span> <span m="1168790">are</span>
  <span m="1168950">using.</span> <span m="1171500">Any</span> <span m="1171740">other</span>
  <span m="1171910">ideas?</span></p><p><span m="1179310">If</span> <span m="1179470">you</span>
  <span m="1179590">could,</span> <span m="1179930">what</span> <span m="1180630">would</span>
  <span m="1180770">be</span> <span m="1180940">the</span> <span m="1181010">most</span>
  <span m="1181250">reliable</span> <span m="1181610">way</span> <span m="1181740">to</span>
  <span m="1181810">get</span> <span m="1182010">gradient?</span> <span m="1185070">Differentiate,</span>
  <span m="1185440">yeah.</span> <span m="1186203">So</span> <span m="1186596">analytical</span>
  <span m="1186990">gradients,</span> <span m="1187570">if</span> <span m="1188016">you</span>
  <span m="1188462">can.</span> <span m="1191430">If</span> <span m="1191720">you</span>
  <span m="1191890">have</span> <span m="1192100">a</span> <span m="1192150">code,</span>
  <span m="1193400">or if</span> <span m="1193560">you</span> <span m="1193630">have</span>
  <span m="1193730">a</span> <span m="1193790">model</span> <span m="1194290">that</span>
  <span m="1194470">analytic,</span> <span m="1194913">that''s all</span> <span m="1195356">functions
  you</span> <span m="1195800">can</span> <span m="1195900">differentiate,</span>
  <span m="1196500">then</span> <span m="1197050">differentiate.</span> <span m="1197730">Analytic</span>
  <span m="1198100">gradients</span> <span m="1198800">is</span> <span m="1199130">definitely</span>
  <span m="1199810">the</span> <span m="1199890">way</span> <span m="1200040">to</span>
  <span m="1200170">go.</span></p><p><span m="1202520">Have you guys</span> <span
  m="1202990">heard of</span> <span m="1204870">the</span> <span m="1204970">adjoint</span>
  <span m="1205210">method,</span> <span m="1205730">that Professor</span> <span m="1205800">Wong</span>
  <span m="1206050">talked about?</span> <span m="1207320">[INAUDIBLE].</span> <span
  m="1210450">So</span> <span m="1210690">this</span> <span m="1210840">is</span>
  <span m="1210930">a</span> <span m="1210980">really</span> <span m="1211190">powerful</span>
  <span m="1211680">way</span> <span m="1212040">to</span> <span m="1212210">get</span>
  <span m="1213110">gradients</span> <span m="1213810">when</span> <span m="1214010">you</span>
  <span m="1214140">have</span> <span m="1215100">particularly</span> <span m="1215460">CFD</span>
  <span m="1216000">models</span> <span m="1216410">or</span> <span m="1216510">[?
  panelement ?]</span> <span m="1216950">models</span> <span m="1217230">that have</span>
  <span m="1217320">got lots and lots</span> <span m="1217820">and lots</span> <span
  m="1218320">of</span> <span m="1218820">design</span> <span m="1219140">variables.</span>
  <span m="1219660">So</span> <span m="1219710">like</span> <span m="1219890">if</span>
  <span m="1219980">you''re</span> <span m="1220080">trying</span> <span m="1220260">to</span>
  <span m="1220340">do</span> <span m="1221316">shape</span> <span m="1221710">optimization</span>
  <span m="1222320">of</span> <span m="1222410">an</span> <span m="1222490">aircraft</span>
  <span m="1222860">wing</span> <span m="1223130">and</span> <span m="1223370">your</span>
  <span m="1223630">design</span> <span m="1223930">variables</span> <span m="1224500">were</span>
  <span m="1224670">all</span> <span m="1225000">the</span> <span m="1225640">surface</span>
  <span m="1225960">points</span> <span m="1226430">or</span> <span m="1226520">all
  the</span> <span m="1228570">properties</span> <span m="1228950">of</span> <span
  m="1229382">the</span> <span m="1231220">sections</span> <span m="1231850">in</span>
  <span m="1231920">a</span> <span m="1231980">wing,</span> <span m="1232230">so</span>
  <span m="1232430">you</span> <span m="1232520">have</span> <span m="1232620">hundreds</span>
  <span m="1232970">and</span> <span m="1233060">hundreds</span> <span m="1233270">of</span>
  <span m="1233370">design</span> <span m="1233620">variables,</span> <span m="1234050">people</span>
  <span m="1234536">use</span> <span m="1235510">what''s</span> <span m="1236360">the</span>
  <span m="1236480">adjoint</span> <span m="1237200">method</span> <span m="1237430">to
  come up</span> <span m="1237910">with</span> <span m="1238030">gradients.</span></p><p><span
  m="1239540">Has anybody</span> <span m="1239870">heard</span> <span m="1239990">of</span>
  <span m="1240080">automatic</span> <span m="1240430">differentiation?</span> <span
  m="1247860">So</span> <span m="1247980">this</span> <span m="1248130">is</span>
  <span m="1248240">something</span> <span m="1248560">that''s</span> <span m="1248830">becoming</span>
  <span m="1249450">kind</span> <span m="1249570">of</span> <span m="1249630">increasingly</span>
  <span m="1250500">popular,</span> <span m="1251560">where</span> <span m="1252260">people</span>
  <span m="1252590">write</span> <span m="1252960">these</span> <span m="1254150">automatic</span>
  <span m="1254580">differentiation</span> <span m="1255300">codes,</span> <span m="1256270">and</span>
  <span m="1256420">basically</span> <span m="1256840">you</span> <span m="1256980">take</span>
  <span m="1257320">your</span> <span m="1257580">code--</span> <span m="1258272">so</span>
  <span m="1258620">you</span> <span m="1258790">take</span> <span m="1258970">your</span>
  <span m="1259270">code</span> <span m="1259750">that</span> <span m="1260550">takes</span>
  <span m="1260880">in</span> <span m="1261210">x</span> <span m="1262410">and</span>
  <span m="1262540">puts</span> <span m="1262760">out</span> <span m="1262970">J,</span>
  <span m="1264040">and</span> <span m="1264160">you</span> <span m="1264230">feed</span>
  <span m="1264580">it</span> <span m="1264720">through</span> <span m="1265000">this</span>
  <span m="1265250">automatic</span> <span m="1265810">differentiator,</span> <span
  m="1266500">and</span> <span m="1266640">it</span> <span m="1266770">gives</span>
  <span m="1266980">you</span> <span m="1267130">back</span> <span m="1267350">a</span>
  <span m="1267400">code</span> <span m="1267800">that</span> <span m="1268420">takes</span>
  <span m="1268700">in</span> <span m="1268750">x</span> <span m="1269170">and gives</span>
  <span m="1269310">you</span> <span m="1269410">grad</span> <span m="1269850">J.</span>
  <span m="1272220">Sort</span> <span m="1272500">of</span> <span m="1272720">somewhere</span>
  <span m="1273150">at the</span> <span m="1273580">intersection</span> <span m="1274050">of</span>
  <span m="1274140">computer</span> <span m="1274470">science</span> <span m="1274770">and</span>
  <span m="1274870">computational</span> <span m="1275360">science,</span> <span m="1275660">I</span>
  <span m="1275720">guess.</span> <span m="1276100">They''re</span> <span m="1276230">write</span>
  <span m="1276460">these</span> <span m="1276560">codes</span> <span m="1276690">that</span>
  <span m="1277310">will</span> <span m="1277470">go</span> <span m="1277790">through</span>
  <span m="1278050">your</span> <span m="1278510">code and</span> <span m="1278860">differentiate</span>
  <span m="1279300">it</span> <span m="1279740">line</span> <span m="1279980">by</span>
  <span m="1280110">line</span> <span m="1280440">by</span> <span m="1280570">line,</span>
  <span m="1281040">and</span> <span m="1281240">use</span> <span m="1281480">the</span>
  <span m="1281570">chain</span> <span m="1281880">rule,</span> <span m="1284090">and</span>
  <span m="1284460">basically</span> <span m="1284970">automatically</span> <span
  m="1285460">differentiate</span> <span m="1285855">it.</span></p><p><span m="1286730">And</span>
  <span m="1286840">so there''s</span> <span m="1287090">an</span> <span m="1287180">example</span>
  <span m="1287740">of</span> <span m="1287800">this</span> <span m="1288050">in</span>
  <span m="1288450">[? EETS ?].</span> <span m="1288850">There''s</span> <span m="1288990">a</span>
  <span m="1289040">big</span> <span m="1289200">model</span> <span m="1289500">called</span>
  <span m="1289650">the</span> <span m="1289750">MIT</span> <span m="1290150">GCM,</span>
  <span m="1290750">which</span> <span m="1290820">is</span> <span m="1290920">the</span>
  <span m="1291040">MIT</span> <span m="1291320">Global</span> <span m="1291630">Circulation</span>
  <span m="1292210">Model.</span> <span m="1292553">I don''t</span> <span m="1292896">know
  if</span> <span m="1293240">anybody''s</span> <span m="1293640">heard</span> <span
  m="1293995">of</span> <span m="1294350">it.</span> <span m="1294950">Nicholas,</span>
  <span m="1295050">you work</span> <span m="1295370">over in</span> <span m="1295490">[?
  EETS ?],</span> <span m="1296090">right?</span> <span m="1296330">Have you--</span></p><p><span
  m="1297268">AUDIENCE: [INAUDIBLE]</span></p><p><span m="1301390">KAREN WILLCOX:
  MIT''s</span> <span m="1301580">been</span> <span m="1301910">building</span> <span
  m="1302210">for</span> <span m="1302360">a</span> <span m="1302440">long</span>
  <span m="1302850">time</span> <span m="1303560">this</span> <span m="1303830">really</span>
  <span m="1304180">massive</span> <span m="1304680">community</span> <span m="1305080">model</span>
  <span m="1305440">that''s</span> <span m="1305620">doing</span> <span m="1305820">a</span>
  <span m="1305890">lot</span> <span m="1306060">of</span> <span m="1306720">modeling</span>
  <span m="1307040">of</span> <span m="1307120">the</span> <span m="1307220">ocean
  and</span> <span m="1307700">atmosphere</span> <span m="1307965">and</span> <span
  m="1308230">interactions</span> <span m="1308870">for</span> <span m="1308970">climate</span>
  <span m="1309240">change.</span> <span m="1309850">And</span> <span m="1309950">so</span>
  <span m="1310050">they''ve</span> <span m="1310250">used</span> <span m="1310540">automatic</span>
  <span m="1311270">differentiation</span> <span m="1312220">so</span> <span m="1312290">that</span>
  <span m="1312450">you</span> <span m="1312530">can</span> <span m="1312650">take</span>
  <span m="1312840">this</span> <span m="1312940">massive</span> <span m="1314790">model</span>
  <span m="1315730">and</span> <span m="1316190">come</span> <span m="1316280">up</span>
  <span m="1316400">with</span> <span m="1316860">gradients.</span> <span m="1317815">And
  it''s</span> <span m="1318210">symbolic</span> <span m="1318610">differentiation</span>
  <span m="1319160">too,</span> <span m="1319380">right?</span> <span m="1319680">Isn''t
  it</span> <span m="1320020">Mathematica?</span></p><p><span m="1322126">There''s
  a lot of</span> <span m="1322570">different</span> <span m="1322810">ways</span>
  <span m="1323050">you</span> <span m="1323110">can</span> <span m="1323210">come</span>
  <span m="1323380">up</span> <span m="1323490">with</span> <span m="1323630">gradients.</span>
  <span m="1323860">[? And there''s ?]</span> <span m="1324340">[? another one ?]</span>
  <span m="1325690">[INAUDIBLE]</span> <span m="1326470">something</span> <span m="1326680">called</span>
  <span m="1326930">the</span> <span m="1327190">complex</span> <span m="1327680">step</span>
  <span m="1328163">method,</span> <span m="1329130">which</span> <span m="1329405">I''m
  afraid</span> <span m="1329680">we</span> <span m="1329900">don''t</span> <span
  m="1330040">have</span> <span m="1330150">time</span> <span m="1330330">to</span>
  <span m="1330410">talk</span> <span m="1330620">about.</span> <span m="1331045">It''s</span>
  <span m="1331470">a</span> <span m="1331660">pretty</span> <span m="1331890">neat</span>
  <span m="1334470">trick.</span> <span m="1334800">I</span> <span m="1334850">can''t</span>
  <span m="1334970">remember</span> <span m="1335230">the</span> <span m="1335290">formula.</span>
  <span m="1335520">Do</span> <span m="1335760">you know</span> <span m="1335830">the</span>
  <span m="1336230">formula,</span> <span m="1336701">Alex?</span></p><p><span m="1337643">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="1339060">KAREN WILLCOX: Yeah.</span> <span m="1339600">I</span>
  <span m="1339860">don''t want to</span> <span m="1340100">write</span> <span m="1340220">it</span>
  <span m="1340290">down</span> <span m="1340460">and</span> <span m="1340570">get</span>
  <span m="1340670">it</span> <span m="1340790">wrong,</span> <span m="1341180">but</span>
  <span m="1342390">if</span> <span m="1342570">you</span> <span m="1342630">can</span>
  <span m="1342770">take</span> <span m="1343020">your</span> <span m="1343530">model,</span>
  <span m="1343950">your</span> <span m="1344325">J</span> <span m="1344700">of x</span>
  <span m="1345500">and</span> <span m="1346290">put</span> <span m="1346500">in</span>
  <span m="1346620">a</span> <span m="1346680">complex</span> <span m="1347370">x--</span>
  <span m="1349200">maybe</span> <span m="1349380">you</span> <span m="1349440">can</span>
  <span m="1349550">find</span> <span m="1349730">the</span> <span m="1349760">formula.</span>
  <span m="1350350">Anyway,</span> <span m="1350500">it''s</span> <span m="1350650">a</span>
  <span m="1350690">really</span> <span m="1350870">neat</span> <span m="1351180">trick</span>
  <span m="1351510">where</span> <span m="1351600">you</span> <span m="1351700">can</span>
  <span m="1351840">pretend</span> <span m="1352020">that</span> <span m="1352080">your</span>
  <span m="1352320">variables</span> <span m="1352710">are</span> <span m="1352790">complex,</span>
  <span m="1353850">and</span> <span m="1353940">then</span> <span m="1354030">it</span>
  <span m="1354180">turns</span> <span m="1354340">out</span> <span m="1354440">that</span>
  <span m="1354540">the</span> <span m="1354580">gradient</span> <span m="1354900">ends</span>
  <span m="1355220">up</span> <span m="1355310">being the</span> <span m="1355550">imaginary</span>
  <span m="1355805">part.</span> <span m="1358200">So</span> <span m="1358350">that''s</span>
  <span m="1358530">also</span> <span m="1358750">neat.</span></p><p><span m="1358810">And
  if</span> <span m="1358980">your</span> <span m="1359290">code''s</span> <span m="1360190">written
  in</span> <span m="1360550">Fortran,</span> <span m="1361300">this</span> <span
  m="1361470">can</span> <span m="1361610">be</span> <span m="1361740">a</span> <span
  m="1361800">neat</span> <span m="1362100">trick.</span> <span m="1362720">Do you
  guys</span> <span m="1362870">even</span> <span m="1363050">know</span> <span m="1363220">Fortran?</span>
  <span m="1365200">You know,</span> <span m="1365300">Professor</span> <span m="1365540">[?
  Jolley ?]</span> <span m="1365900">still</span> <span m="1366220">writes</span>
  <span m="1366650">all</span> <span m="1366740">of</span> <span m="1366800">his</span>
  <span m="1366940">codes</span> <span m="1367140">in</span> <span m="1367210">Fortran.</span></p><p><span
  m="1367928">AUDIENCE: [INAUDIBLE]</span></p><p><span m="1370370">KAREN WILLCOX:
  You''re</span> <span m="1370470">painfully</span> <span m="1370900">aware?</span>
  <span m="1372050">So in</span> <span m="1372130">Fortran,</span> <span m="1372260">you</span>
  <span m="1372870">can</span> <span m="1372980">define</span> <span m="1373270">complex</span>
  <span m="1373725">variables.</span></p><p><span m="1374635">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="1378280">KAREN WILLCOX: The</span> <span m="1378390">imaginary</span> <span m="1378640">part</span>
  <span m="1379200">of</span> <span m="1379390">J,</span> <span m="1381110">x</span>
  <span m="1381510">of</span> <span m="1381910">[? pi ?]</span> <span m="1382160">times</span>
  <span m="1382360">[? a ?]</span> <span m="1382690">[? h ?]</span> <span m="1384300">is
  equal</span> <span m="1384610">to</span> <span m="1384670">the</span> <span m="1384730">gradient?</span></p><p><span
  m="1385270">AUDIENCE: [INAUDIBLE]</span></p><p><span m="1387220">KAREN WILLCOX:
  Divided</span> <span m="1387560">by</span> <span m="1387640">[? J ?]</span> <span
  m="1387920">is</span> <span m="1388010">equal to the</span> <span m="1388360">gradient.</span>
  <span m="1389780">Yeah,</span> <span m="1390220">so</span> <span m="1391188">[INAUDIBLE].</span>
  <span m="1393124">It</span> <span m="1393610">turns</span> <span m="1393830">out</span>
  <span m="1393960">if</span> <span m="1394000">you</span> <span m="1394640">take</span>
  <span m="1394830">a</span> <span m="1394900">complex</span> <span m="1395180">step,</span>
  <span m="1396660">if</span> <span m="1396750">you</span> <span m="1396820">take</span>
  <span m="1397060">your</span> <span m="1397320">variable</span> <span m="1397750">x</span>
  <span m="1398120">and</span> <span m="1398250">add a</span> <span m="1398460">complex</span>
  <span m="1398910">step,</span> <span m="1399180">and</span> <span m="1399270">then</span>
  <span m="1399390">divide</span> <span m="1399770">by</span> <span m="1401040">that</span>
  <span m="1401400">h,</span> <span m="1401894">it</span> <span m="1402388">turns
  out</span> <span m="1403376">the</span> <span m="1403870">imaginary</span> <span
  m="1404500">part</span> <span m="1404680">of</span> <span m="1404760">that</span>
  <span m="1404900">result</span> <span m="1405280">ends up</span> <span m="1405560">giving</span>
  <span m="1405790">you the</span> <span m="1405880">gradient.</span></p><p><span
  m="1408350">OK,</span> <span m="1408660">but</span> <span m="1408810">anyway.</span>
  <span m="1410310">Finite</span> <span m="1410580">differences</span> <span m="1410910">is</span>
  <span m="1411450">the</span> <span m="1411520">most</span> <span m="1411700">commonly</span>
  <span m="1412120">used</span> <span m="1412430">because</span> <span m="1412780">it''s</span>
  <span m="1413050">sort</span> <span m="1413300">of</span> <span m="1413470">the</span>
  <span m="1413860">general</span> <span m="1414140">purpose</span> <span m="1414500">one.
  So</span> <span m="1414750">let''s</span> <span m="1414970">just</span> <span m="1415690">look</span>
  <span m="1415950">at</span> <span m="1416040">how</span> <span m="1416710">finite</span>
  <span m="1416970">differences</span> <span m="1420860">work.</span> <span m="1421330">And</span>
  <span m="1421450">these</span> <span m="1421670">formulas</span> <span m="1422170">should</span>
  <span m="1422490">look</span> <span m="1422810">somewhat</span> <span m="1423380">familiar,</span>
  <span m="1423840">although</span> <span m="1424070">you</span> <span m="1424290">saw</span>
  <span m="1424450">them</span> <span m="1424570">in</span> <span m="1424650">a</span>
  <span m="1424710">different</span> <span m="1425210">setting.</span> <span m="1425730">Remember,</span>
  <span m="1426060">you saw</span> <span m="1426530">finite</span> <span m="1426970">differences</span>
  <span m="1428415">when</span> <span m="1428870">we</span> <span m="1429040">were</span>
  <span m="1429760">approximating</span> <span m="1430710">partial</span> <span m="1431045">derivatives</span>
  <span m="1431640">in</span> <span m="1431760">the</span> <span m="1431860">[? PEs
  ?],</span> <span m="1432325">right?</span> <span m="1432790">Remember</span> <span
  m="1433320">way</span> <span m="1433500">back?</span> <span m="1434330">You''re</span>
  <span m="1434410">look</span> <span m="1434570">at</span> <span m="1434660">the</span>
  <span m="1434730">convection</span> <span m="1435190">equation</span> <span m="1435583">or</span>
  <span m="1435976">the</span> <span m="1436370">convection</span> <span m="1436680">diffusion</span>
  <span m="1437030">equation,</span> <span m="1437520">where</span> <span m="1437660">you</span>
  <span m="1437760">had</span> <span m="1437960">things</span> <span m="1438210">like</span>
  <span m="1438530">du</span> <span m="1438950">dx,</span> <span m="1439790">or</span>
  <span m="1440210">[INAUDIBLE]</span> <span m="1440450">squared</span> <span m="1441000">[INAUDIBLE]</span>
  <span m="1441770">squared,</span> <span m="1442330">and you</span> <span m="1442460">used</span>
  <span m="1442970">finite</span> <span m="1443170">differences?</span></p><p><span
  m="1443680">The</span> <span m="1443740">exact</span> <span m="1444180">same</span>
  <span m="1445290">idea</span> <span m="1445630">can</span> <span m="1445790">be</span>
  <span m="1445900">applied</span> <span m="1446260">now</span> <span m="1446420">to</span>
  <span m="1446510">find</span> <span m="1446770">the</span> <span m="1446830">gradient</span>
  <span m="1447320">of</span> <span m="1447440">J</span> <span m="1447780">with</span>
  <span m="1447970">respect</span> <span m="1448610">to</span> <span m="1448670">design</span>
  <span m="1448990">variables</span> <span m="1449403">x.</span> <span m="1450230">So</span>
  <span m="1450400">for</span> <span m="1450580">example,</span> <span m="1450895">if</span>
  <span m="1451210">we</span> <span m="1451310">were</span> <span m="1451390">looking</span>
  <span m="1451680">for</span> <span m="1451980">dJ</span> <span m="1453784">dx</span>
  <span m="1455137">i</span> <span m="1457060">at</span> <span m="1457420">some</span>
  <span m="1457940">point,</span> <span m="1458330">let''s just</span> <span m="1458590">call</span>
  <span m="1458820">it</span> <span m="1459284">x0,</span> <span m="1461140">then</span>
  <span m="1461730">we</span> <span m="1461820">would</span> <span m="1461940">just</span>
  <span m="1462260">take</span> <span m="1462752">J</span> <span m="1464228">and</span>
  <span m="1465960">we''d</span> <span m="1466170">have</span> <span m="1466450">x1,</span>
  <span m="1467320">x2,</span> <span m="1469030">all</span> <span m="1469180">the</span>
  <span m="1469250">way,</span> <span m="1469430">and</span> <span m="1469620">we</span>
  <span m="1469720">would</span> <span m="1469830">have</span> <span m="1470090">xi</span>
  <span m="1471690">plus</span> <span m="1472030">delta</span> <span m="1472512">xi.</span>
  <span m="1473960">So we''re</span> <span m="1474130">going to</span> <span m="1474390">perturb</span>
  <span m="1474970">the</span> <span m="1475150">ith</span> <span m="1476360">design</span>
  <span m="1476640">variable.</span> <span m="1479230">And</span> <span m="1479240">then</span>
  <span m="1479330">we</span> <span m="1479410">would</span> <span m="1479500">have</span>
  <span m="1479790">xi</span> <span m="1480350">plus</span> <span m="1480550">1</span>
  <span m="1481390">all</span> <span m="1481510">the</span> <span m="1481570">way</span>
  <span m="1481720">up</span> <span m="1481870">to</span> <span m="1482305">xn.</span>
  <span m="1482820">They</span> <span m="1482920">would</span> <span m="1483060">all</span>
  <span m="1483410">be</span> <span m="1483760">fixed.</span></p><p><span m="1485490">And
  we''re going to</span> <span m="1485540">differentiate</span> <span m="1485990">that</span>
  <span m="1487810">with</span> <span m="1491385">the</span> <span m="1491850">baseline</span>
  <span m="1492320">point,</span> <span m="1496059">xi</span> <span m="1496973">up</span>
  <span m="1497430">to</span> <span m="1498066">xn.</span> <span m="1501390">And</span>
  <span m="1501490">all</span> <span m="1501650">that''s</span> <span m="1502000">going</span>
  <span m="1502120">to</span> <span m="1502200">be</span> <span m="1502580">divided</span>
  <span m="1502960">by</span> <span m="1503914">delta</span> <span m="1504391">xi.</span>
  <span m="1506300">And so</span> <span m="1506490">this</span> <span m="1506620">thing</span>
  <span m="1506770">here</span> <span m="1507254">is the</span> <span m="1507738">numerator.</span>
  <span m="1510160">So</span> <span m="1511240">this</span> <span m="1511430">is</span>
  <span m="1511770">the</span> <span m="1512080">baseline</span> <span m="1512360">point,</span>
  <span m="1513990">the</span> <span m="1514476">x0</span> <span m="1517520">would</span>
  <span m="1517590">be</span> <span m="1517720">right</span> <span m="1517890">here.</span>
  <span m="1523309">So</span> <span m="1523770">there''s the</span> <span m="1523870">baseline</span>
  <span m="1524340">point.</span></p><p><span m="1526290">And then</span> <span m="1526770">if</span>
  <span m="1527250">we</span> <span m="1527330">want</span> <span m="1527520">to</span>
  <span m="1527580">estimate</span> <span m="1528190">the</span> <span m="1528680">gradient</span>
  <span m="1529990">in</span> <span m="1530130">the</span> <span m="1530200">direction</span>
  <span m="1530650">xi,</span> <span m="1531470">we just</span> <span m="1531690">take</span>
  <span m="1531900">xi</span> <span m="1532040">and we</span> <span m="1532475">perturb
  it</span> <span m="1532910">by delta</span> <span m="1533345">xi,</span> <span m="1534650">take</span>
  <span m="1535170">the</span> <span m="1535420">difference</span> <span m="1535840">between</span>
  <span m="1536140">the function</span> <span m="1536480">[INAUDIBLE]</span> <span
  m="1537100">perturbed</span> <span m="1537660">point</span> <span m="1538310">minus</span>
  <span m="1539260">the</span> <span m="1539370">baseline</span> <span m="1540200">divided</span>
  <span m="1540500">by</span> <span m="1540620">delta</span> <span m="1541060">xi.</span>
  <span m="1542380">Yeah.</span> <span m="1543470">So</span> <span m="1543680">again,</span>
  <span m="1544010">it</span> <span m="1544110">looks</span> <span m="1544140">pretty</span>
  <span m="1544300">similar</span> <span m="1544750">to</span> <span m="1544850">what</span>
  <span m="1544990">you</span> <span m="1545090">saw when</span> <span m="1545355">we</span>
  <span m="1545620">talked</span> <span m="1545880">about</span> <span m="1546860">finite</span>
  <span m="1547050">differences</span> <span m="1547480">earlier.</span> <span m="1548832">So
  this</span> <span m="1549180">would</span> <span m="1549390">be a</span> <span m="1549730">one-sided</span>
  <span m="1550510">difference.</span></p><p><span m="1555010">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="1558982">KAREN WILLCOX: Different</span> <span m="1559480">ways</span> <span
  m="1559710">of</span> <span m="1559790">computing</span> <span m="1560050">the</span>
  <span m="1560120">finite</span> <span m="1560400">difference?</span> <span m="1560670">Yeah,</span>
  <span m="1560900">exactly.</span> <span m="1561155">So</span> <span m="1561410">that''s
  a</span> <span m="1561900">one-sided.</span> <span m="1562660">You</span> <span
  m="1562780">could</span> <span m="1562920">also</span> <span m="1563170">do a</span>
  <span m="1563565">two-sided</span> <span m="1564320">difference</span> <span m="1566010">with</span>
  <span m="1566580">the</span> <span m="1566880">same</span> <span m="1567834">partial.</span>
  <span m="1570219">So</span> <span m="1570696">it would</span> <span m="1571173">be
  J</span> <span m="1571650">dx</span> <span m="1572127">i</span> <span m="1573090">evaluated</span>
  <span m="1573570">at</span> <span m="1576040">the</span> <span m="1576340">point</span>
  <span m="1576730">x0</span> <span m="1577390">could</span> <span m="1577550">be</span>
  <span m="1578380">J</span> <span m="1579320">x1,</span> <span m="1579790">x2,</span>
  <span m="1581670">to</span> <span m="1582753">xi</span> <span m="1583679">plus</span>
  <span m="1584142">delta</span> <span m="1584605">xi</span> <span m="1588310">minus</span>
  <span m="1589430">J</span> <span m="1589680">x1,</span> <span m="1590390">x2,</span>
  <span m="1591750">xi</span> <span m="1592190">minus</span> <span m="1592510">delta</span>
  <span m="1592630">xi.</span> <span m="1596896">All</span> <span m="1597370">divided</span>
  <span m="1597850">out</span> <span m="1598070">by</span> <span m="1598220">2.</span>
  <span m="1599771">[INAUDIBLE]</span> <span m="1600945">central</span> <span m="1601340">difference.</span>
  <span m="1602466">So</span> <span m="1602810">you</span> <span m="1602960">can</span>
  <span m="1603447">evaluate</span> <span m="1603934">the</span> <span m="1605882">derivative</span>
  <span m="1606369">at the</span> <span m="1606860">same</span> <span m="1607100">point</span>
  <span m="1607800">using</span> <span m="1608030">the</span> <span m="1608100">point</span>
  <span m="1608460">in</span> <span m="1608590">one</span> <span m="1608800">side,</span>
  <span m="1609390">or</span> <span m="1609540">you</span> <span m="1609660">could</span>
  <span m="1609800">use</span> <span m="1610420">one</span> <span m="1610770">little</span>
  <span m="1611120">step</span> <span m="1611270">forward,</span> <span m="1611500">one</span>
  <span m="1611620">little</span> <span m="1611680">step</span> <span m="1611980">back,</span>
  <span m="1613080">and do</span> <span m="1613280">it</span> <span m="1613360">like
  a</span> <span m="1613690">central</span> <span m="1613960">difference.</span></p><p><span
  m="1616765">And</span> <span m="1617220">if</span> <span m="1618130">you</span>
  <span m="1618260">wanted</span> <span m="1618390">to</span> <span m="1618460">do</span>
  <span m="1618820">higher</span> <span m="1619180">order,</span> <span m="1619640">you</span>
  <span m="1619730">could</span> <span m="1619890">take</span> <span m="1620600">more</span>
  <span m="1620800">points.</span> <span m="1622730">But</span> <span m="1622900">now</span>
  <span m="1623260">here''s</span> <span m="1623640">the</span> <span m="1625620">catch.</span>
  <span m="1626050">So</span> <span m="1626220">if</span> <span m="1626310">we</span>
  <span m="1626480">want</span> <span m="1626680">to</span> <span m="1626740">estimate</span>
  <span m="1629156">[? compute ?]</span> <span m="1634940">to</span> <span m="1635070">compute</span>
  <span m="1635400">grad</span> <span m="1635730">J</span> <span m="1637418">at</span>
  <span m="1637840">whatever</span> <span m="1638210">the</span> <span m="1638310">current</span>
  <span m="1638720">point</span> <span m="1639030">is</span> <span m="1639150">in</span>
  <span m="1639250">the</span> <span m="1639340">design</span> <span m="1639740">space,</span>
  <span m="1642110">how</span> <span m="1642310">many</span> <span m="1643150">function</span>
  <span m="1643600">calls</span> <span m="1643970">do</span> <span m="1644100">we</span>
  <span m="1644200">need</span> <span m="1644620">if</span> <span m="1644810">we</span>
  <span m="1644970">use a</span> <span m="1645070">one-sided</span> <span m="1645800">difference?</span>
  <span m="1646600">How many</span> <span m="1646950">times do</span> <span m="1647160">we</span>
  <span m="1647250">need</span> <span m="1647360">to</span> <span m="1647460">run</span>
  <span m="1647690">our</span> <span m="1647820">model?</span> <span m="1656310">2n</span>
  <span m="1656790">if</span> <span m="1656950">we</span> <span m="1659005">were to</span>
  <span m="1659500">use this</span> <span m="1659710">one.</span> <span m="1659890">How</span>
  <span m="1660010">about</span> <span m="1660420">this</span> <span m="1660830">one?</span>
  <span m="1661080">Well,</span> <span m="1661280">almost</span> <span m="1661670">2n.</span>
  <span m="1662900">n</span> <span m="1664960">plus</span> <span m="1665140">1?</span>
  <span m="1666430">So</span> <span m="1666580">1</span> <span m="1666810">for</span>
  <span m="1666920">the</span> <span m="1667130">baseline</span> <span m="1667650">and</span>
  <span m="1667800">then</span> <span m="1667950">it''s</span> <span m="1668250">going</span>
  <span m="1668370">to</span> <span m="1668440">be</span> <span m="1668530">a</span>
  <span m="1668610">little</span> <span m="1668800">step in</span> <span m="1669070">x1,</span>
  <span m="1669800">a</span> <span m="1669870">little</span> <span m="1670100">step</span>
  <span m="1670190">in</span> <span m="1670250">x2,</span> <span m="1670540">a little</span>
  <span m="1670850">step in</span> <span m="1671300">x3,</span> <span m="1671640">all</span>
  <span m="1671650">the</span> <span m="1671710">way</span> <span m="1671930">through</span>
  <span m="1672360">xn.</span> <span m="1675400">So with a</span> <span m="1675860">one-sided,</span>
  <span m="1679880">we</span> <span m="1680050">would</span> <span m="1680190">need</span>
  <span m="1680390">n</span> <span m="1680550">plus</span> <span m="1680860">1.</span>
  <span m="1681180">And</span> <span m="1681360">for a</span> <span m="1681760">two-sided,</span>
  <span m="1683540">we</span> <span m="1683690">would</span> <span m="1683940">just
  need</span> <span m="1684120">2n.</span> <span m="1684750">We</span> <span m="1685065">don''t</span>
  <span m="1685530">have</span> <span m="1685700">the</span> <span m="1685810">baseline.</span>
  <span m="1689470">Function</span> <span m="1689820">evaluations.</span></p><p><span
  m="1690420">Now remember,</span> <span m="1690720">each</span> <span m="1691000">function</span>
  <span m="1691340">evaluation</span> <span m="1695720">in</span> <span m="1695830">the</span>
  <span m="1695900">course</span> <span m="1696330">of</span> <span m="1696390">your</span>
  <span m="1696480">simulation</span> <span m="1697050">code,</span> <span m="1697410">which</span>
  <span m="1697630">could</span> <span m="1697820">take</span> <span m="1698270">minutes</span>
  <span m="1698670">or</span> <span m="1698780">hours</span> <span m="1699150">or</span>
  <span m="1699270">even</span> <span m="1699460">days.</span> <span m="1700360">So</span>
  <span m="1701920">if</span> <span m="1701990">you</span> <span m="1702090">have</span>
  <span m="1702320">100</span> <span m="1702670">design</span> <span m="1702990">variables,</span>
  <span m="1703690">each</span> <span m="1703880">time</span> <span m="1704900">you</span>
  <span m="1704980">want</span> <span m="1705120">a</span> <span m="1705150">gradient,</span>
  <span m="1706270">you''re going to</span> <span m="1706590">have</span> <span m="1706700">to</span>
  <span m="1706760">do</span> <span m="1706990">of</span> <span m="1707110">the</span>
  <span m="1707200">order</span> <span m="1707470">of</span> <span m="1707540">100</span>
  <span m="1708290">calls</span> <span m="1708640">to your</span> <span m="1708780">function.</span>
  <span m="1709250">And remember,</span> <span m="1709380">you''re</span> <span m="1709620">going
  to</span> <span m="1709880">need</span> <span m="1709920">gradients</span> <span
  m="1710300">at</span> <span m="1710680">each</span> <span m="1711610">point</span>
  <span m="1711910">in</span> <span m="1712000">the</span> <span m="1712080">design</span>
  <span m="1712430">space</span> <span m="1712770">when</span> <span m="1712900">you''re</span>
  <span m="1712990">trying</span> <span m="1713120">to</span> <span m="1713200">figure</span>
  <span m="1713450">out</span> <span m="1713580">where to</span> <span m="1713700">move.</span></p><p><span
  m="1714426">So it</span> <span m="1714790">can</span> <span m="1715020">get</span>
  <span m="1715180">expensive</span> <span m="1715700">pretty</span> <span m="1715890">quickly.</span>
  <span m="1717020">How</span> <span m="1717150">about</span> <span m="1719790">if</span>
  <span m="1719900">you</span> <span m="1720000">wanted</span> <span m="1720140">to</span>
  <span m="1720290">compute</span> <span m="1720610">the</span> <span m="1720710">Hessian
  by</span> <span m="1721170">finite</span> <span m="1721490">differences?</span>
  <span m="1728880">Well,</span> <span m="1729190">we</span> <span m="1729290">didn''t</span>
  <span m="1729640">write</span> <span m="1729870">down</span> <span m="1730060">the</span>
  <span m="1730130">formula,</span> <span m="1730670">but</span> <span m="1731740">you</span>
  <span m="1732190">remember</span> <span m="1732510">the</span> <span m="1732650">formula</span>
  <span m="1733060">for</span> <span m="1733170">the</span> <span m="1733300">second</span>
  <span m="1734250">derivative,</span> <span m="1734630">right?</span> <span m="1734980">If
  we were</span> <span m="1735330">computing</span> <span m="1738115">that</span>
  <span m="1738576">guy,</span> <span m="1739500">then it</span> <span m="1739850">would
  be</span> <span m="1740754">J,</span> <span m="1741206">and we</span> <span m="1741660">would</span>
  <span m="1741820">do</span> <span m="1742060">xi--</span> <span m="1742643">probably
  don''t</span> <span m="1742986">want to</span> <span m="1743330">write</span> <span
  m="1743550">out</span> <span m="1743710">all</span> <span m="1743810">the</span>
  <span m="1743870">arguments.</span> <span m="1744400">xi</span> <span m="1746280">minus</span>
  <span m="1746700">2J</span> <span m="1747205">at</span> <span m="1747500">the</span>
  <span m="1747570">nominal</span> <span m="1747970">point</span> <span m="1750314">minus</span>
  <span m="1750790">J</span> <span m="1752700">doing</span> <span m="1753020">xi</span>
  <span m="1755530">minus--</span> <span m="1756216">do you</span> <span m="1756560">remember</span>
  <span m="1756850">that</span> <span m="1757020">formula?</span> <span m="1758358">Divided</span>
  <span m="1758822">by</span> <span m="1759286">delta x</span> <span m="1759750">squared.</span>
  <span m="1761300">The</span> <span m="1763800">central</span> <span m="1764130">finite</span>
  <span m="1764380">difference</span> <span m="1764740">for</span> <span m="1764820">the</span>
  <span m="1764880">second</span> <span m="1765210">order</span> <span m="1765720">derivative.</span>
  <span m="1766310">Do</span> <span m="1766680">you guys</span> <span m="1766940">remember</span>
  <span m="1767180">that?</span> <span m="1769360">Am I</span> <span m="1769840">confusing</span>
  <span m="1770050">you,</span> <span m="1770150">or is</span> <span m="1770220">it</span>
  <span m="1770350">OK</span> <span m="1770590">to</span> <span m="1770670">not</span>
  <span m="1770870">write</span> <span m="1771050">out</span> <span m="1771170">all
  the</span> <span m="1771650">x''s?</span> <span m="1772130">Is that</span> <span
  m="1772240">all right?</span> <span m="1772720">Yeah.</span></p><p><span m="1774160">So</span>
  <span m="1776560">to</span> <span m="1777040">compute</span> <span m="1777530">second</span>
  <span m="1777910">derivative,</span> <span m="1779550">first</span> <span m="1779790">of</span>
  <span m="1779870">all</span> <span m="1780030">you''re</span> <span m="1780130">going</span>
  <span m="1780260">to</span> <span m="1780390">need</span> <span m="1781540">the</span>
  <span m="1781910">point</span> <span m="1782270">in front</span> <span m="1782620">and
  the</span> <span m="1782710">point</span> <span m="1782930">behind.</span> <span
  m="1783220">But</span> <span m="1783330">how</span> <span m="1783740">many</span>
  <span m="1784320">entries</span> <span m="1784640">in</span> <span m="1784730">the</span>
  <span m="1784800">matrix?</span></p><p><span m="1786395">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="1788940">KAREN WILLCOX: Yeah,</span> <span m="1789180">it''s n</span> <span m="1789330">by</span>
  <span m="1789610">n.</span> <span m="1789780">It</span> <span m="1789860">turns</span>
  <span m="1790070">out it''s</span> <span m="1790240">symmetric,</span> <span m="1790980">so</span>
  <span m="1791220">you</span> <span m="1791330">don''t</span> <span m="1791570">need--</span>
  <span m="1792150">remember</span> <span m="1792640">it''s</span> <span m="1793130">symmetric,</span>
  <span m="1793540">so you</span> <span m="1793650">only</span> <span m="1793770">need</span>
  <span m="1793920">to</span> <span m="1793990">compute</span> <span m="1795550">the</span>
  <span m="1795630">diagonal</span> <span m="1796030">and</span> <span m="1796170">the
  upper</span> <span m="1796670">triangle.</span> <span m="1797540">It</span> <span
  m="1797750">still</span> <span m="1797970">turns</span> <span m="1798270">out</span>
  <span m="1798540">to</span> <span m="1798650">be</span> <span m="1800230">n</span>
  <span m="1800900">plus</span> <span m="1801070">1</span> <span m="1802150">over</span>
  <span m="1802290">2</span> <span m="1802660">entries,</span> <span m="1804060">and</span>
  <span m="1804250">then</span> <span m="1804650">you</span> <span m="1804750">need</span>
  <span m="1804990">the</span> <span m="1805060">extra</span> <span m="1805340">function</span>
  <span m="1805740">evaluation,</span> <span m="1806700">so</span> <span m="1806840">then</span>
  <span m="1806970">you</span> <span m="1807090">would</span> <span m="1807220">need</span>
  <span m="1807750">two</span> <span m="1807950">for</span> <span m="1808100">each</span>
  <span m="1808280">of</span> <span m="1808360">these.</span> <span m="1808610">So
  it</span> <span m="1808910">basically</span> <span m="1809350">ends</span> <span
  m="1809480">up</span> <span m="1809670">being</span> <span m="1809940">[INAUDIBLE]</span>
  <span m="1810350">n</span> <span m="1810600">squared.</span></p><p><span m="1811770">And
  so if</span> <span m="1812170">you</span> <span m="1812230">have</span> <span m="1812320">100</span>
  <span m="1812640">design</span> <span m="1812960">variables,</span> <span m="1814370">that''s</span>
  <span m="1814770">100</span> <span m="1815200">squared,</span> <span m="1816270">10,000</span>
  <span m="1817240">calls to</span> <span m="1817610">your</span> <span m="1817770">function</span>
  <span m="1818290">to</span> <span m="1818380">get</span> <span m="1818500">a</span>
  <span m="1818580">Hessian</span> <span m="1818880">matrix</span> <span m="1819340">of</span>
  <span m="1819450">the</span> <span m="1819540">order</span> <span m="1820930">every</span>
  <span m="1821230">iteration.</span> <span m="1822360">Which</span> <span m="1822370">is</span>
  <span m="1822450">why</span> <span m="1822560">I</span> <span m="1822640">say</span>
  <span m="1822850">the</span> <span m="1822920">Newton</span> <span m="1823100">method</span>
  <span m="1823450">is</span> <span m="1823570">powerful,</span> <span m="1824270">but</span>
  <span m="1824620">if</span> <span m="1824780">you''re</span> <span m="1824980">doing</span>
  <span m="1825240">gradients</span> <span m="1825660">by</span> <span m="1825760">finite</span>
  <span m="1826020">difference,</span> <span m="1826490">almost</span> <span m="1826870">it
  means</span> <span m="1827250">you can''t</span> <span m="1827460">afford</span>
  <span m="1827550">to use</span> <span m="1828300">the</span> <span m="1828480">Newton</span>
  <span m="1830210">method.</span></p><p><span m="1832660">But</span> <span m="1832790">the</span>
  <span m="1832870">good</span> <span m="1833000">news</span> <span m="1833230">is</span>
  <span m="1833390">that</span> <span m="1833600">MATLAB</span> <span m="1833980">takes</span>
  <span m="1834200">care</span> <span m="1834440">of</span> <span m="1834530">all</span>
  <span m="1834660">of</span> <span m="1834740">this</span> <span m="1834930">for</span>
  <span m="1835290">you.</span> <span m="1840140">We</span> <span m="1840240">can</span>
  <span m="1840400">have</span> <span m="1840560">a</span> <span m="1840620">look</span>
  <span m="1841120">at</span> <span m="1843700">how</span> <span m="1844974">MATLAB</span>
  <span m="1846120">does</span> <span m="1846480">that</span> <span m="1847200">for</span>
  <span m="1847480">you.</span> <span m="1849050">Is</span> <span m="1849280">this</span>
  <span m="1849470">clear</span> <span m="1849810">how</span> <span m="1849920">you</span>
  <span m="1850440">estimate</span> <span m="1850640">the</span> <span m="1850800">gradients?</span>
  <span m="1852560">Yup?</span> <span m="1855690">So</span> <span m="1856185">let
  me</span> <span m="1856680">pull this.</span> <span m="1859650">So</span> <span
  m="1866580">I</span> <span m="1867075">showed</span> <span m="1867570">you</span>
  <span m="1868070">already</span> <span m="1868680">on</span> <span m="1871070">Wednesday.</span>
  <span m="1881843">[INAUDIBLE]</span> <span m="1892280">So</span> <span m="1892777">I</span>
  <span m="1893290">showed</span> <span m="1893480">you</span> <span m="1893590">already</span>
  <span m="1894050">on</span> <span m="1896900">Wednesday</span> <span m="1897650">this</span>
  <span m="1897910">little</span> <span m="1898160">[? piece ?].</span> <span m="1898555">You
  might</span> <span m="1898950">remember</span> <span m="1899210">when we</span>
  <span m="1899460">looked</span> <span m="1899760">at</span> <span m="1899900">the</span>
  <span m="1908370">landscape</span> <span m="1908625">and we</span> <span m="1908880">saw
  the</span> <span m="1909200">little</span> <span m="1909520">asterisks</span> <span
  m="1910140">climbing</span> <span m="1910530">around.</span> <span m="1911676">So</span>
  <span m="1912060">I</span> <span m="1912170">showed</span> <span m="1912520">you</span>
  <span m="1916350">[INAUDIBLE],</span> <span m="1919490">but</span> <span m="1919740">here''s</span>
  <span m="1920260">the</span> <span m="1920350">call.</span></p><p><span m="1921230">So</span>
  <span m="1921670">remember</span> <span m="1922040">I</span> <span m="1922140">talked</span>
  <span m="1922420">about</span> <span m="1923370">[? Effman ?]</span> <span m="1923570">unc,</span>
  <span m="1924740">which</span> <span m="1924970">is</span> <span m="1925410">the</span>
  <span m="1925800">unconstrained</span> <span m="1926215">gradient-based</span> <span
  m="1927990">optimization</span> <span m="1928730">method</span> <span m="1929110">in</span>
  <span m="1930097">MATLAB.</span> <span m="1931071">And I</span> <span m="1931560">also</span>
  <span m="1931670">talked</span> <span m="1931780">about</span> <span m="1931940">[?
  Effman ?]</span> <span m="1932270">search,</span> <span m="1933320">which</span>
  <span m="1933350">I said</span> <span m="1933440">was</span> <span m="1933520">the</span>
  <span m="1933670">[INAUDIBLE]</span> <span m="1934140">simplex.</span> <span m="1934550">Remember</span>
  <span m="1934760">that</span> <span m="1934880">was</span> <span m="1935010">the</span>
  <span m="1935070">triangles</span> <span m="1935740">that</span> <span m="1935870">were</span>
  <span m="1935960">flipping</span> <span m="1936260">around</span> <span m="1936600">and</span>
  <span m="1936700">going</span> <span m="1936900">through</span> <span m="1937120">the
  design</span> <span m="1937340">space.</span> <span m="1937660">So</span> <span
  m="1938060">the</span> <span m="1938230">thing</span> <span m="1938370">with</span>
  <span m="1938490">[? Naldemede ?]</span> <span m="1939425">simplex</span> <span
  m="1939760">is you</span> <span m="1940230">don''t</span> <span m="1940440">need
  gradients.</span> <span m="1940940">It doesn''t</span> <span m="1941060">need</span>
  <span m="1941220">gradients.</span> <span m="1941710">It</span> <span m="1941770">just</span>
  <span m="1941970">does</span> <span m="1942280">these</span> <span m="1942550">three</span>
  <span m="1942930">triangles</span> <span m="1943410">and</span> <span m="1943530">all</span>
  <span m="1943600">these</span> <span m="1943770">rules</span> <span m="1944150">to</span>
  <span m="1944250">contract</span> <span m="1944510">them.</span> <span m="1945420">It''s</span>
  <span m="1945580">only</span> <span m="1945790">ever</span> <span m="1945960">looking</span>
  <span m="1946200">at</span> <span m="1946270">the</span> <span m="1946340">three</span>
  <span m="1946550">points</span> <span m="1946920">in</span> <span m="1947000">order</span>
  <span m="1947250">in</span> <span m="1947360">the</span> <span m="1947430">design.</span></p><p><span
  m="1948282">So</span> <span m="1948710">if</span> <span m="1948810">you</span> <span
  m="1948830">have</span> <span m="1948940">a</span> <span m="1948980">function</span>
  <span m="1949410">that''s</span> <span m="1949590">not</span> <span m="1949800">differentiable,</span>
  <span m="1950430">you</span> <span m="1950550">can</span> <span m="1950710">still</span>
  <span m="1950900">use</span> <span m="1951100">[? Effman ?]</span> <span m="1951460">search.</span>
  <span m="1951930">But</span> <span m="1952060">if</span> <span m="1952170">you</span>
  <span m="1952250">have</span> <span m="1952380">something</span> <span m="1952740">that''s</span>
  <span m="1953270">not</span> <span m="1953560">differentiable</span> <span m="1954200">and</span>
  <span m="1954310">you</span> <span m="1954380">try</span> <span m="1954580">to</span>
  <span m="1954690">use</span> <span m="1955120">it</span> <span m="1955250">[? Effman
  ?]</span> <span m="1955586">unc,</span> <span m="1956590">MATLAB''s</span> <span
  m="1956970">going</span> <span m="1957100">to</span> <span m="1957160">be</span>
  <span m="1957240">trying</span> <span m="1957600">to</span> <span m="1957720">compute</span>
  <span m="1958110">gradients--</span> <span m="1959200">not</span> <span m="1959610">second</span>
  <span m="1959700">derivatives</span> <span m="1960230">but</span> <span m="1960800">first</span>
  <span m="1961040">derivatives--</span> <span m="1962260">and</span> <span m="1962690">could</span>
  <span m="1962920">get</span> <span m="1963070">itself</span> <span m="1964040">into</span>
  <span m="1964220">trouble.</span></p><p><span m="1964985">But</span> <span m="1965260">the</span>
  <span m="1965530">really</span> <span m="1965700">nice</span> <span m="1965800">thing</span>
  <span m="1966040">with</span> <span m="1966180">these</span> <span m="1966980">MATLAB</span>
  <span m="1967500">functions</span> <span m="1968110">is</span> <span m="1968290">that</span>
  <span m="1968830">you</span> <span m="1968980">basically</span> <span m="1969490">supply</span>
  <span m="1970520">a</span> <span m="1970610">function,</span> <span m="1971520">that</span>
  <span m="1971720">given</span> <span m="1972020">x</span> <span m="1972710">computes</span>
  <span m="1973210">J.</span> <span m="1974800">And</span> <span m="1976250">you</span>
  <span m="1976440">supply</span> <span m="1976930">an</span> <span m="1977000">initial</span>
  <span m="1977410">guess,</span> <span m="1978830">an</span> <span m="1978920">initial</span>
  <span m="1979270">point</span> <span m="1979470">in</span> <span m="1979540">the</span>
  <span m="1979610">landscape,</span> <span m="1980530">and</span> <span m="1980630">that''s</span>
  <span m="1980780">actually</span> <span m="1981060">the</span> <span m="1981180">only</span>
  <span m="1981440">thing</span> <span m="1981620">you</span> <span m="1981700">have</span>
  <span m="1981830">to</span> <span m="1981920">give it.</span> <span m="1982330">If</span>
  <span m="1982440">you</span> <span m="1982500">don''t</span> <span m="1982620">want</span>
  <span m="1982770">to</span> <span m="1982830">give it</span> <span m="1983040">anything</span>
  <span m="1983460">more,</span> <span m="1983700">MATLAB</span> <span m="1983900">will</span>
  <span m="1984110">take</span> <span m="1984270">care</span> <span m="1984420">of</span>
  <span m="1984510">everything</span> <span m="1984960">else</span> <span m="1985170">for</span>
  <span m="1985513">you.</span> <span m="1986200">You</span> <span m="1986310">can</span>
  <span m="1986440">give</span> <span m="1986580">it</span> <span m="1987110">just</span>
  <span m="1987420">that</span> <span m="1987980">black</span> <span m="1988240">box</span>
  <span m="1988850">function,</span> <span m="1989370">given</span> <span m="1989610">x</span>
  <span m="1989970">computes</span> <span m="1990430">J,</span> <span m="1991374">and</span>
  <span m="1991846">an initial</span> <span m="1992320">guess.</span></p><p><span
  m="1993580">If</span> <span m="1993740">you know a</span> <span m="1994030">little</span>
  <span m="1994190">bit</span> <span m="1994360">more</span> <span m="1994620">about</span>
  <span m="1994890">what''s</span> <span m="1995110">going</span> <span m="1995410">on,</span>
  <span m="1995860">you</span> <span m="1995990">can</span> <span m="1996360">also</span>
  <span m="1996980">choose</span> <span m="1997310">to</span> <span m="1997400">manage</span>
  <span m="1997740">options.</span> <span m="1998320">So</span> <span m="1998420">you</span>
  <span m="1998540">can</span> <span m="1998670">do</span> <span m="1998770">things</span>
  <span m="1999000">like</span> <span m="1999230">turn</span> <span m="1999450">on</span>
  <span m="1999960">see</span> <span m="2000120">more</span> <span m="2000380">information</span>
  <span m="2000830">about</span> <span m="2001050">the</span> <span m="2001130">iteration.</span>
  <span m="2002550">You</span> <span m="2002670">can</span> <span m="2002890">play</span>
  <span m="2003090">with</span> <span m="2003240">tolerances.</span> <span m="2004430">You</span>
  <span m="2004590">can</span> <span m="2004730">even</span> <span m="2009300">specify</span>
  <span m="2009900">exactly</span> <span m="2010370">which</span> <span m="2011680">methods</span>
  <span m="2013570">you</span> <span m="2013780">want</span> <span m="2013980">to</span>
  <span m="2014080">use.</span> <span m="2014690">So</span> <span m="2015950">here''s
  the</span> <span m="2016170">documentation</span> <span m="2016630">for</span> <span
  m="2017050">[? Effman ?]</span> <span m="2017850">unc.</span> <span m="2018305">So
  you</span> <span m="2018760">see there,</span> <span m="2019030">there''s</span>
  <span m="2019520">just the</span> <span m="2019610">basic</span> <span m="2019920">call,</span>
  <span m="2020800">giving</span> <span m="2021020">it</span> <span m="2021090">a</span>
  <span m="2021130">function</span> <span m="2021510">and</span> <span m="2021640">an</span>
  <span m="2021720">initial</span> <span m="2023030">guess.</span></p><p><span m="2026170">So</span>
  <span m="2026340">you</span> <span m="2026410">see</span> <span m="2026640">all</span>
  <span m="2027180">these</span> <span m="2027520">different</span> <span m="2027780">options</span>
  <span m="2028170">in</span> <span m="2028270">here.</span> <span m="2029080">So</span>
  <span m="2029270">you</span> <span m="2029500">can</span> <span m="2029810">have</span>
  <span m="2029980">the</span> <span m="2030070">option</span> <span m="2030370">to</span>
  <span m="2030460">supply</span> <span m="2030800">a</span> <span m="2030850">gradient.</span>
  <span m="2032030">So</span> <span m="2032110">if</span> <span m="2032210">you</span>
  <span m="2032380">had</span> <span m="2032860">a</span> <span m="2032900">function</span>
  <span m="2033350">that</span> <span m="2033460">was</span> <span m="2033710">analytic</span>
  <span m="2034590">and</span> <span m="2034740">you</span> <span m="2034820">could</span>
  <span m="2034950">differentiate</span> <span m="2035290">it,</span> <span m="2035880">it</span>
  <span m="2036370">would</span> <span m="2036520">be</span> <span m="2036620">a</span>
  <span m="2036690">really</span> <span m="2037010">good</span> <span m="2037160">idea</span>
  <span m="2037710">to</span> <span m="2037820">give</span> <span m="2038300">that</span>
  <span m="2038530">gradient</span> <span m="2039140">to</span> <span m="2039240">MATLAB</span>
  <span m="2040490">as</span> <span m="2040680">well</span> <span m="2040940">as</span>
  <span m="2041260">giving</span> <span m="2041530">it</span> <span m="2041700">the</span>
  <span m="2041730">function.</span> <span m="2042260">Or</span> <span m="2042510">if</span>
  <span m="2042660">you</span> <span m="2042790">would</span> <span m="2042910">use</span>
  <span m="2043090">automatic</span> <span m="2043410">differentiation</span> <span
  m="2044230">and</span> <span m="2044440">come</span> <span m="2044590">up</span>
  <span m="2044670">with</span> <span m="2044780">a</span> <span m="2044840">code</span>
  <span m="2045240">that</span> <span m="2045640">computed</span> <span m="2046150">gradients,</span>
  <span m="2047090">and</span> <span m="2047300">you''re</span> <span m="2047420">able</span>
  <span m="2047660">to</span> <span m="2048050">specify</span> <span m="2048310">that</span>
  <span m="2048570">as</span> <span m="2048940">an</span> <span m="2049020">additional</span>
  <span m="2050199">option.</span></p><p><span m="2057392">And</span> <span m="2058368">last</span>
  <span m="2058856">thing I</span> <span m="2059360">just want</span> <span m="2059500">to</span>
  <span m="2059600">show</span> <span m="2059750">you</span> <span m="2059920">is</span>
  <span m="2060179">the methods.</span> <span m="2068659">Check</span> <span m="2068870">it</span>
  <span m="2070070">in</span> <span m="2070210">here.</span> <span m="2070510">I''m
  not</span> <span m="2070979">sure if it''s</span> <span m="2071449">telling</span>
  <span m="2071790">us</span> <span m="2071969">what</span> <span m="2072620">the</span>
  <span m="2072710">methods</span> <span m="2073341">are.</span> <span m="2083442">[INAUDIBLE]</span>
  <span m="2100298">and have a look,</span> <span m="2100762">see what</span> <span
  m="2101226">method it is.</span></p><p><span m="2103546">So</span> <span m="2104010">again,</span>
  <span m="2104130">I</span> <span m="2104240">didn''t</span> <span m="2104850">talk</span>
  <span m="2105100">about</span> <span m="2105360">them,</span> <span m="2105540">but</span>
  <span m="2105710">there''s</span> <span m="2105830">a</span> <span m="2105880">class</span>
  <span m="2106920">of</span> <span m="2107120">methods</span> <span m="2107340">called</span>
  <span m="2107815">quasi</span> <span m="2108290">Newton</span> <span m="2109240">methods,</span>
  <span m="2110190">which</span> <span m="2110440">in</span> <span m="2110825">a way</span>
  <span m="2111210">are</span> <span m="2111300">kind</span> <span m="2111500">of</span>
  <span m="2111570">like</span> <span m="2111750">the</span> <span m="2112260">best</span>
  <span m="2112610">of</span> <span m="2112700">both</span> <span m="2113158">worlds</span>
  <span m="2113616">between</span> <span m="2114074">the</span> <span m="2114532">first</span>
  <span m="2114990">order</span> <span m="2115300">and</span> <span m="2115440">the</span>
  <span m="2115510">second</span> <span m="2115770">order</span> <span m="2117123">methods.</span>
  <span m="2118480">So</span> <span m="2120740">if</span> <span m="2120880">you</span>
  <span m="2120970">remember</span> <span m="2121300">here</span> <span m="2121430">back</span>
  <span m="2121670">in the</span> <span m="2121710">Newton''s</span> <span m="2121810">method,</span>
  <span m="2122630">[INAUDIBLE]</span> <span m="2125030">design</span> <span m="2126310">space</span>
  <span m="2126610">to</span> <span m="2126730">be</span> <span m="2126900">the</span>
  <span m="2126990">inverse</span> <span m="2127280">of</span> <span m="2127380">the</span>
  <span m="2127510">Hessian</span> <span m="2127980">times</span> <span m="2128240">the</span>
  <span m="2128645">gradient.</span> <span m="2129050">But</span> <span m="2129160">then</span>
  <span m="2129320">we</span> <span m="2129430">said</span> <span m="2129600">that</span>
  <span m="2129990">[? computation ?]</span> <span m="2130620">was</span> <span m="2130810">really</span>
  <span m="2131210">too</span> <span m="2131330">expensive.</span></p><p><span m="2132095">So</span>
  <span m="2132540">what</span> <span m="2132870">a</span> <span m="2132910">quasi</span>
  <span m="2133200">Newton</span> <span m="2133470">method</span> <span m="2133870">does</span>
  <span m="2134180">is</span> <span m="2134280">that</span> <span m="2134420">it</span>
  <span m="2134580">basically</span> <span m="2135050">introduces</span> <span m="2135500">an</span>
  <span m="2135590">approximation</span> <span m="2136280">for</span> <span m="2136380">the
  Hessian.</span> <span m="2136760">That''s</span> <span m="2137140">this</span> <span
  m="2137370">A</span> <span m="2137560">thing</span> <span m="2137770">here.</span>
  <span m="2139250">And</span> <span m="2139420">it</span> <span m="2139530">builds</span>
  <span m="2139820">up</span> <span m="2140010">this</span> <span m="2140130">approximation</span>
  <span m="2140850">using</span> <span m="2141080">the</span> <span m="2141150">gradients</span>
  <span m="2141410">that</span> <span m="2141670">it''s</span> <span m="2141920">computing</span>
  <span m="2142420">anyway.</span> <span m="2142970">So don''t</span> <span m="2143570">worry</span>
  <span m="2143740">about</span> <span m="2143920">the</span> <span m="2144000">details</span>
  <span m="2144500">of</span> <span m="2144780">what</span> <span m="2145240">is</span>
  <span m="2145340">on</span> <span m="2145500">here,</span> <span m="2145720">because</span>
  <span m="2145940">it''s</span> <span m="2146120">a little bit</span> <span m="2146360">beyond</span>
  <span m="2146780">what</span> <span m="2147020">I</span> <span m="2147150">want</span>
  <span m="2147410">you</span> <span m="2147530">guys</span> <span m="2148690">to</span>
  <span m="2148810">be</span> <span m="2148900">comfortable</span> <span m="2149400">with.</span>
  <span m="2150030">But</span> <span m="2151260">more</span> <span m="2151470">or</span>
  <span m="2151520">less</span> <span m="2151790">every</span> <span m="2152050">time</span>
  <span m="2152450">we</span> <span m="2152580">compute a</span> <span m="2152970">gradient,</span>
  <span m="2154120">we</span> <span m="2154230">can</span> <span m="2154370">also</span>
  <span m="2154720">use</span> <span m="2155530">differences</span> <span m="2156010">between</span>
  <span m="2156340">gradients</span> <span m="2156620">to</span> <span m="2156900">get</span>
  <span m="2157160">approximations</span> <span m="2157595">to</span> <span m="2158030">Hessians.</span>
  <span m="2159420">And</span> <span m="2160270">I''m</span> <span m="2160400">pretty</span>
  <span m="2161090">sure</span> <span m="2161230">that''s</span> <span m="2161410">the</span>
  <span m="2161797">method</span> <span m="2162960">that''s</span> <span m="2163300">sitting</span>
  <span m="2164090">underneath</span> <span m="2164500">here in</span> <span m="2164991">MATLAB.</span></p><p><span
  m="2165973">AUDIENCE: [INAUDIBLE]</span></p><p><span m="2170400">KAREN WILLCOX:
  [INAUDIBLE].</span> <span m="2170960">OK.</span></p><p><span m="2173894">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="2188710">KAREN WILLCOX: So</span> <span m="2188840">we''re</span>
  <span m="2188950">not</span> <span m="2189120">guaranteed</span> <span m="2189610">because</span>
  <span m="2189800">it</span> <span m="2189880">depends</span> <span m="2190190">on</span>
  <span m="2190280">the</span> <span m="2190360">problem.</span> <span m="2191710">So
  if</span> <span m="2191910">you</span> <span m="2191990">have</span> <span m="2192090">a</span>
  <span m="2192160">problem</span> <span m="2192660">where</span> <span m="2192820">there''s</span>
  <span m="2192930">a</span> <span m="2193010">direction</span> <span m="2194050">where</span>
  <span m="2194320">the</span> <span m="2194810">curvature</span> <span m="2195120">is</span>
  <span m="2195430">flat,</span> <span m="2195760">then</span> <span m="2195880">you''re</span>
  <span m="2195940">going to</span> <span m="2196050">have</span> <span m="2196160">a</span>
  <span m="2196200">singular</span> <span m="2196510">Hessian.</span> <span m="2197230">And</span>
  <span m="2197330">then</span> <span m="2197440">you</span> <span m="2197510">just</span>
  <span m="2197660">have</span> <span m="2197760">to</span> <span m="2197850">be</span>
  <span m="2197930">careful.</span></p><p><span m="2198370">AUDIENCE: [INAUDIBLE]</span>
  <span m="2199765">Yeah.</span> <span m="2200695">If</span> <span m="2201160">J</span>
  <span m="2201625">were</span> <span m="2202090">linear</span> <span m="2202555">in</span>
  <span m="2203485">any</span> <span m="2203950">design</span> <span m="2204420">variable,</span>
  <span m="2204530">when you</span> <span m="2204590">differentiate</span> <span m="2204845">twice</span>
  <span m="2205280">you</span> <span m="2205430">would</span> <span m="2205560">get
  0.</span> <span m="2206390">And</span> <span m="2206805">you</span> <span m="2207220">have</span>
  <span m="2207360">to</span> <span m="2208050">be</span> <span m="2208150">very</span>
  <span m="2208320">careful</span> <span m="2209056">if</span> <span m="2209870">you</span>
  <span m="2209990">have</span> <span m="2210550">[INAUDIBLE]</span> <span m="2211050">inverse</span>
  <span m="2211230">of the</span> <span m="2211410">Hessian.</span> <span m="2212700">But</span>
  <span m="2212830">there</span> <span m="2212960">are</span> <span m="2213280">ways</span>
  <span m="2213530">you</span> <span m="2213590">can</span> <span m="2213710">handle</span>
  <span m="2213950">that,</span> <span m="2214412">more</span> <span m="2214874">advanced</span>
  <span m="2215798">optimizations.</span></p><p><span m="2217650">OK.</span> <span
  m="2219344">So I''m</span> <span m="2219841">not going to</span> <span m="2220340">talk</span>
  <span m="2220610">about</span> <span m="2221060">constrained</span> <span m="2221510">methods,</span>
  <span m="2222410">but</span> <span m="2222860">I</span> <span m="2222960">did</span>
  <span m="2223170">want</span> <span m="2223330">to</span> <span m="2223500">just</span>
  <span m="2223750">show</span> <span m="2224010">you</span> <span m="2227280">briefly,</span>
  <span m="2227840">and</span> <span m="2228050">show</span> <span m="2228210">you
  also</span> <span m="2228440">in</span> <span m="2228902">MATLAB</span> <span m="2230290">how</span>
  <span m="2232790">constrained</span> <span m="2233085">methods</span> <span m="2233930">work.</span>
  <span m="2234210">So</span> <span m="2234310">there''s</span> <span m="2234640">something</span>
  <span m="2234980">called</span> <span m="2235190">the</span> <span m="2235330">[?
  buns ?]</span> <span m="2235700">function.</span> <span m="2236070">Actually the</span>
  <span m="2236340">optimization</span> <span m="2236610">community</span> <span m="2237010">loves</span>
  <span m="2237360">these</span> <span m="2237630">little</span> <span m="2237810">simple</span>
  <span m="2238140">problems.</span> <span m="2238630">Remember I</span> <span m="2238680">talked</span>
  <span m="2238880">about</span> <span m="2239070">[? Rosenbrot ?]</span> <span m="2239750">the</span>
  <span m="2239860">other</span> <span m="2239990">day</span> <span m="2240240">and
  called</span> <span m="2240535">it the</span> <span m="2240830">banana</span> <span
  m="2240870">function.</span></p><p><span m="2241440">So</span> <span m="2241862">there''s
  another</span> <span m="2242284">one</span> <span m="2243130">called</span> <span
  m="2243330">the</span> <span m="2243440">[? buns ?]</span> <span m="2244020">function,</span>
  <span m="2244800">which</span> <span m="2244940">is</span> <span m="2245020">actually</span>
  <span m="2245220">a</span> <span m="2245260">constrained</span> <span m="2245535">problem.</span>
  <span m="2246180">So it</span> <span m="2246550">turns out</span> <span m="2246780">this
  is</span> <span m="2246880">the</span> <span m="2246990">objective,</span> <span
  m="2247910">which</span> <span m="2248460">I</span> <span m="2248550">know</span>
  <span m="2248700">doesn''t</span> <span m="2248940">really</span> <span m="2249150">mean</span>
  <span m="2249310">anything,</span> <span m="2249670">but</span> <span m="2249850">the</span>
  <span m="2251070">difference</span> <span m="2251430">of</span> <span m="2251550">this</span>
  <span m="2251720">one</span> <span m="2251920">is</span> <span m="2252000">it''s</span>
  <span m="2252140">got</span> <span m="2252300">constraints.</span> <span m="2253890">And
  so if</span> <span m="2254240">we</span> <span m="2254390">look</span> <span m="2254640">at</span>
  <span m="2254790">the</span> <span m="2255690">visualization,</span> <span m="2256400">here''s</span>
  <span m="2256620">the</span> <span m="2256720">design</span> <span m="2257140">space,</span>
  <span m="2257950">design</span> <span m="2258220">variables</span> <span m="2258490">x1</span>
  <span m="2258680">and</span> <span m="2258910">x2.</span> <span m="2259360">And</span>
  <span m="2259640">now the</span> <span m="2259920">contours,</span> <span m="2260255">they''re</span>
  <span m="2260590">called</span> <span m="2260850">contours</span> <span m="2261240">of</span>
  <span m="2261390">the</span> <span m="2261520">objective</span> <span m="2261920">function.</span>
  <span m="2262920">And</span> <span m="2263200">then the</span> <span m="2263270">constraints</span>
  <span m="2264430">are</span> <span m="2264620">saying</span> <span m="2265280">the</span>
  <span m="2265360">solution</span> <span m="2265870">has</span> <span m="2266150">to</span>
  <span m="2266260">lie</span> <span m="2266490">above</span> <span m="2266850">this</span>
  <span m="2266930">one,</span> <span m="2267500">has</span> <span m="2267800">to</span>
  <span m="2268010">lie</span> <span m="2268240">to</span> <span m="2268330">the</span>
  <span m="2268400">left</span> <span m="2268690">of</span> <span m="2268790">this</span>
  <span m="2268970">one,</span> <span m="2269360">and</span> <span m="2269530">has</span>
  <span m="2269710">to</span> <span m="2269830">lie</span> <span m="2270170">above</span>
  <span m="2270510">this</span> <span m="2270680">constraint.</span></p><p><span m="2271392">So</span>
  <span m="2271750">again,</span> <span m="2272200">when</span> <span m="2272280">I
  was</span> <span m="2272450">talking</span> <span m="2272620">about</span> <span
  m="2272760">the</span> <span m="2272830">landscape,</span> <span m="2273170">remember</span>
  <span m="2273370">I</span> <span m="2273450">said</span> <span m="2273660">think</span>
  <span m="2273820">of</span> <span m="2273910">the</span> <span m="2273980">constraints</span>
  <span m="2274240">as</span> <span m="2274500">being</span> <span m="2274640">like</span>
  <span m="2274810">the</span> <span m="2274890">keep-out</span> <span m="2275340">regions,</span>
  <span m="2276530">telling</span> <span m="2276840">you</span> <span m="2277010">where</span>
  <span m="2277330">in</span> <span m="2277420">the</span> <span m="2278720">design</span>
  <span m="2279210">space</span> <span m="2279550">you</span> <span m="2279670">can</span>
  <span m="2279830">be.</span> <span m="2280450">And</span> <span m="2280600">so in</span>
  <span m="2280710">this</span> <span m="2280910">case</span> <span m="2281210">our</span>
  <span m="2281820">possible</span> <span m="2283050">design</span> <span m="2283410">region</span>
  <span m="2283780">is</span> <span m="2283920">this</span> <span m="2284020">thing</span>
  <span m="2284340">here</span> <span m="2285700">traced</span> <span m="2286110">out</span>
  <span m="2286520">by</span> <span m="2286600">the</span> <span m="2286680">constraints.</span></p><p><span
  m="2287740">So it turns</span> <span m="2288020">out this</span> <span m="2288190">problem</span>
  <span m="2288520">has</span> <span m="2288780">two</span> <span m="2289120">local</span>
  <span m="2289650">solutions.</span> <span m="2291000">One</span> <span m="2291200">is</span>
  <span m="2291390">also</span> <span m="2291600">the</span> <span m="2291750">global</span>
  <span m="2292340">solution.</span> <span m="2294130">If</span> <span m="2294220">we</span>
  <span m="2294290">try and</span> <span m="2294490">minimize,</span> <span m="2294950">the</span>
  <span m="2295020">global</span> <span m="2295320">solution</span> <span m="2295680">is</span>
  <span m="2295800">actually</span> <span m="2296090">up</span> <span m="2296240">here</span>
  <span m="2296790">in</span> <span m="2296860">the</span> <span m="2296930">corner
  of</span> <span m="2297260">the design</span> <span m="2297660">space,</span> <span
  m="2298990">which</span> <span m="2299180">you</span> <span m="2299270">can</span>
  <span m="2299440">see</span> <span m="2299630">from</span> <span m="2299780">the</span>
  <span m="2299850">colors.</span> <span m="2300140">It''s</span> <span m="2300370">the</span>
  <span m="2300480">bluest</span> <span m="2300884">color.</span> <span m="2302500">But</span>
  <span m="2302630">there''s</span> <span m="2302780">also</span> <span m="2303110">a</span>
  <span m="2303190">local</span> <span m="2303970">optimum</span> <span m="2304510">that</span>
  <span m="2304710">sits</span> <span m="2304970">here</span> <span m="2306070">on</span>
  <span m="2307370">this</span> <span m="2307530">constraint</span> <span m="2307860">down</span>
  <span m="2308190">here</span> <span m="2308560">at</span> <span m="2308630">about</span>
  <span m="2309510">50,</span> <span m="2309790">20.</span> <span m="2310810">And</span>
  <span m="2311090">I should</span> <span m="2311380">say</span> <span m="2311670">that</span>
  <span m="2311780">there</span> <span m="2312020">are</span> <span m="2312170">bounds</span>
  <span m="2312530">on</span> <span m="2312690">the</span> <span m="2312740">design</span>
  <span m="2313070">variables,</span> <span m="2314180">which</span> <span m="2314250">is</span>
  <span m="2314360">why</span> <span m="2315330">this</span> <span m="2315670">global</span>
  <span m="2315950">solution</span> <span m="2316225">sits</span> <span m="2316500">up</span>
  <span m="2316680">here,</span> <span m="2316900">because</span> <span m="2317190">the</span>
  <span m="2317470">design</span> <span m="2317780">variables</span> <span m="2318170">are</span>
  <span m="2318290">at their</span> <span m="2318667">bounds.</span></p><p><span m="2319421">So</span>
  <span m="2319800">that''s</span> <span m="2320020">a</span> <span m="2320100">simple</span>
  <span m="2320460">constrained</span> <span m="2321220">problem.</span> <span m="2323848">And</span>
  <span m="2324290">I</span> <span m="2324350">just</span> <span m="2324550">want</span>
  <span m="2324710">to</span> <span m="2324770">show</span> <span m="2325050">you</span>
  <span m="2325520">running</span> <span m="2336955">the</span> <span m="2337410">algorithm.</span>
  <span m="2337650">So</span> <span m="2337830">[? fman ?]</span> <span m="2338010">[?
  con ?]</span> <span m="2338340">is</span> <span m="2338670">the</span> <span m="2339142">MATLAB</span>
  <span m="2343060">function</span> <span m="2343500">that</span> <span m="2343610">does</span>
  <span m="2343810">constrained</span> <span m="2344250">optimization.</span> <span
  m="2344880">And</span> <span m="2344990">again,</span> <span m="2345190">it''s</span>
  <span m="2345410">really</span> <span m="2345760">super</span> <span m="2346040">simple</span>
  <span m="2346580">to</span> <span m="2346730">use.</span> <span m="2347110">At</span>
  <span m="2347230">a</span> <span m="2347260">minimum,</span> <span m="2347750">all</span>
  <span m="2347890">you</span> <span m="2347990">have</span> <span m="2348140">to</span>
  <span m="2348220">do</span> <span m="2348480">is</span> <span m="2349200">give</span>
  <span m="2349420">it</span> <span m="2349650">a</span> <span m="2350750">function</span>
  <span m="2351510">that</span> <span m="2351880">given</span> <span m="2352240">x</span>
  <span m="2352720">returns</span> <span m="2353000">J of x,</span> <span m="2354170">give
  it</span> <span m="2354530">an initial</span> <span m="2354890">guess</span> <span
  m="2355590">to</span> <span m="2355750">start</span> <span m="2356080">with,</span>
  <span m="2357230">and</span> <span m="2357410">give</span> <span m="2357570">it</span>
  <span m="2357800">a</span> <span m="2357840">function</span> <span m="2358300">that</span>
  <span m="2358420">given</span> <span m="2358640">x</span> <span m="2359100">returns</span>
  <span m="2359490">the</span> <span m="2359560">constraints,</span> <span m="2360450">the</span>
  <span m="2360760">g of x</span> <span m="2361070">or</span> <span m="2361380">the</span>
  <span m="2361490">h</span> <span m="2361590">of</span> <span m="2361730">x</span>
  <span m="2362080">if</span> <span m="2362190">you</span> <span m="2362300">have</span>
  <span m="2362490">them.</span> <span m="2363720">So</span> <span m="2363850">given</span>
  <span m="2364040">x,</span> <span m="2364520">return</span> <span m="2364810">J</span>
  <span m="2365000">of x,</span> <span m="2365370">return</span> <span m="2365710">g
  of x</span> <span m="2366370">and</span> <span m="2366490">h of</span> <span m="2366775">x,</span>
  <span m="2367830">and</span> <span m="2368320">an</span> <span m="2368420">initial</span>
  <span m="2368720">guess.</span></p><p><span m="2369490">And</span> <span m="2369690">there</span>
  <span m="2369780">are</span> <span m="2369850">lots</span> <span m="2370060">more</span>
  <span m="2370250">options</span> <span m="2370620">that</span> <span m="2370760">you</span>
  <span m="2370900">can</span> <span m="2371530">set</span> <span m="2371810">if</span>
  <span m="2371960">you</span> <span m="2372070">want</span> <span m="2372390">to.</span>
  <span m="2373610">And you</span> <span m="2373810">can look</span> <span m="2374255">at
  lots more</span> <span m="2374700">things,</span> <span m="2375020">but</span> <span
  m="2376530">in</span> <span m="2376660">the</span> <span m="2376730">simplest</span>
  <span m="2377120">implementation--</span> <span m="2377450">and</span> <span m="2377780">then</span>
  <span m="2377900">MATLAB</span> <span m="2378250">will</span> <span m="2378360">take</span>
  <span m="2378610">care</span> <span m="2379000">of</span> <span m="2379090">finite</span>
  <span m="2379430">differencing</span> <span m="2380140">for</span> <span m="2380400">you</span>
  <span m="2380700">to</span> <span m="2380800">do</span> <span m="2380910">the</span>
  <span m="2380990">gradient,</span> <span m="2381730">the</span> <span m="2381840">step</span>
  <span m="2382090">size,</span> <span m="2382410">everything.</span> <span m="2383380">Everything</span>
  <span m="2383790">you</span> <span m="2383890">have</span> <span m="2384370">to</span>
  <span m="2384730">worry</span> <span m="2385070">about.</span> <span m="2385850">But</span>
  <span m="2385980">of</span> <span m="2386060">course,</span> <span m="2386350">again,</span>
  <span m="2386690">if</span> <span m="2386730">you</span> <span m="2386850">have</span>
  <span m="2387000">an</span> <span m="2387070">efficient</span> <span m="2387430">way</span>
  <span m="2387680">of computing</span> <span m="2388160">gradients,</span> <span
  m="2389190">you</span> <span m="2389300">have</span> <span m="2389420">the</span>
  <span m="2389520">option</span> <span m="2389860">to</span> <span m="2389940">specify</span>
  <span m="2391400">the</span> <span m="2391500">gradients</span> <span m="2392120">and</span>
  <span m="2396370">make</span> <span m="2396570">things</span> <span m="2396820">run</span>
  <span m="2397070">a</span> <span m="2397150">lot</span> <span m="2397400">more</span>
  <span m="2397630">reliably</span> <span m="2398200">and</span> <span m="2398300">a</span>
  <span m="2398350">lot</span> <span m="2398520">more</span> <span m="2398660">efficiently.</span></p><p><span
  m="2399840">So</span> <span m="2404070">just</span> <span m="2404280">go</span>
  <span m="2404400">back</span> <span m="2404640">up</span> <span m="2404750">here,</span>
  <span m="2406314">so</span> <span m="2407230">this</span> <span m="2407750">one''s</span>
  <span m="2407990">actually</span> <span m="2408310">using--</span> <span m="2410910">this</span>
  <span m="2411070">is</span> <span m="2411160">a</span> <span m="2411210">quasi</span>
  <span m="2411540">Newton</span> <span m="2411800">method.</span> <span m="2412600">There''s</span>
  <span m="2412800">also</span> <span m="2413060">a</span> <span m="2413110">Newton</span>
  <span m="2413390">method</span> <span m="2413870">that</span> <span m="2414040">[INAUDIBLE].</span>
  <span m="2415870">I</span> <span m="2415920">think</span> <span m="2416070">there</span>
  <span m="2416190">are</span> <span m="2416220">actually</span> <span m="2416420">three</span>
  <span m="2416760">levels</span> <span m="2417200">of</span> <span m="2417480">optimization</span>
  <span m="2418390">in</span> <span m="2418660">[? fman ?]</span> <span m="2418930">[?
  con ?],</span> <span m="2420080">two</span> <span m="2420550">different</span> <span
  m="2420850">kinds</span> <span m="2421130">of</span> <span m="2421260">quasi</span>
  <span m="2421500">Newton</span> <span m="2421750">method,</span> <span m="2422420">and</span>
  <span m="2423400">there''s</span> <span m="2424250">a</span> <span m="2424570">Newton</span>
  <span m="2425060">method</span> <span m="2425940">that''s in</span> <span m="2426380">there.</span>
  <span m="2426710">In</span> <span m="2426810">order</span> <span m="2426960">to</span>
  <span m="2427060">run</span> <span m="2427180">the</span> <span m="2427250">Newton</span>
  <span m="2427410">method,</span> <span m="2427750">you</span> <span m="2427850">have</span>
  <span m="2428000">to</span> <span m="2428080">actually</span> <span m="2428400">supply</span>
  <span m="2428780">a</span> <span m="2428860">gradient</span> <span m="2430050">for</span>
  <span m="2430410">it,</span> <span m="2430600">so</span> <span m="2430690">that</span>
  <span m="2430800">it</span> <span m="2430880">doesn''t</span> <span m="2431110">do</span>
  <span m="2431230">all</span> <span m="2431310">that</span> <span m="2431460">finite</span>
  <span m="2431690">differencing</span> <span m="2432020">thing</span> <span m="2432230">for</span>
  <span m="2432370">the</span> <span m="2432470">Hessian.</span></p><p><span m="2434830">And</span>
  <span m="2435010">what</span> <span m="2435530">we</span> <span m="2436290">can</span>
  <span m="2436520">look</span> <span m="2436770">at,</span> <span m="2438030">what</span>
  <span m="2438160">we''re</span> <span m="2438250">looking</span> <span m="2438470">at</span>
  <span m="2438550">here</span> <span m="2438730">are</span> <span m="2438770">different</span>
  <span m="2439090">initial</span> <span m="2439360">conditions.</span> <span m="2439760">So
  here''s</span> <span m="2439960">that</span> <span m="2440150">[? buns ?]</span>
  <span m="2441350">function</span> <span m="2441780">that</span> <span m="2441930">I</span>
  <span m="2442030">was</span> <span m="2442710">showing</span> <span m="2443430">you.</span>
  <span m="2444810">And</span> <span m="2445160">in</span> <span m="2445220">this</span>
  <span m="2445290">particular</span> <span m="2445620">case,</span> <span m="2445950">we</span>
  <span m="2445960">initialize</span> <span m="2446450">here,</span> <span m="2447430">and</span>
  <span m="2447750">what''s</span> <span m="2448130">being</span> <span m="2448350">ported</span>
  <span m="2448650">are</span> <span m="2448710">the</span> <span m="2449280">steps</span>
  <span m="2449620">that</span> <span m="2449750">the</span> <span m="2450520">optimizer''s</span>
  <span m="2451030">taking</span> <span m="2451380">in</span> <span m="2451500">the</span>
  <span m="2451680">design</span> <span m="2452080">space.</span> <span m="2453000">I''m</span>
  <span m="2453130">not</span> <span m="2453240">going</span> <span m="2453360">to</span>
  <span m="2453420">talk</span> <span m="2453750">about</span> <span m="2454020">the</span>
  <span m="2454120">algorithms</span> <span m="2454600">at</span> <span m="2454690">all,</span>
  <span m="2455100">but</span> <span m="2455620">just</span> <span m="2455890">to</span>
  <span m="2456030">get</span> <span m="2456170">a</span> <span m="2456210">sense</span>
  <span m="2456510">that</span> <span m="2456680">when you</span> <span m="2456820">have</span>
  <span m="2456960">constraints,</span> <span m="2457420">things</span> <span m="2457630">are</span>
  <span m="2457670">much</span> <span m="2457900">more</span> <span m="2458040">difficult,</span>
  <span m="2458720">because</span> <span m="2458870">it''s</span> <span m="2458970">not</span>
  <span m="2459160">just</span> <span m="2459340">about</span> <span m="2459550">going</span>
  <span m="2459780">downhill.</span> <span m="2461040">But</span> <span m="2461200">here</span>
  <span m="2461720">we</span> <span m="2461830">could</span> <span m="2462000">just</span>
  <span m="2462190">go</span> <span m="2462350">downhill,</span> <span m="2462690">and</span>
  <span m="2462790">you</span> <span m="2462860">can</span> <span m="2463010">see</span>
  <span m="2463150">more</span> <span m="2463360">or</span> <span m="2463410">less</span>
  <span m="2463660">this</span> <span m="2463750">looks</span> <span m="2464110">kind</span>
  <span m="2464260">of</span> <span m="2464330">like</span> <span m="2464500">a</span>
  <span m="2464710">steepest</span> <span m="2464790">descent</span> <span m="2465200">direction.</span></p><p><span
  m="2467090">But</span> <span m="2467220">then</span> <span m="2467340">when</span>
  <span m="2467460">you</span> <span m="2467530">get</span> <span m="2467720">here</span>
  <span m="2468090">and</span> <span m="2468200">you''re</span> <span m="2468340">right</span>
  <span m="2468720">kind</span> <span m="2468960">of</span> <span m="2469080">actually</span>
  <span m="2469380">on</span> <span m="2469970">the</span> <span m="2470080">wrong</span>
  <span m="2470300">side</span> <span m="2470500">of</span> <span m="2470570">the</span>
  <span m="2470630">constraint,</span> <span m="2471840">you</span> <span m="2471940">can''t</span>
  <span m="2472110">just</span> <span m="2472270">go</span> <span m="2472390">downhill,</span>
  <span m="2472830">because</span> <span m="2472980">you''ve</span> <span m="2473040">got
  to</span> <span m="2473180">worry</span> <span m="2473370">about</span> <span m="2473590">the</span>
  <span m="2473650">constraint.</span> <span m="2473930">And</span> <span m="2474210">you</span>
  <span m="2474270">can</span> <span m="2474410">see</span> <span m="2474550">what</span>
  <span m="2474700">it''s</span> <span m="2474900">doing</span> <span m="2475230">is</span>
  <span m="2475380">it''s</span> <span m="2475510">kind</span> <span m="2475650">of</span>
  <span m="2475720">following</span> <span m="2476060">the</span> <span m="2476130">constraint</span>
  <span m="2477620">and</span> <span m="2477880">skipping</span> <span m="2478160">around.</span>
  <span m="2478540">So</span> <span m="2478650">things</span> <span m="2478920">get</span>
  <span m="2479010">a</span> <span m="2479040">lot</span> <span m="2479320">harder</span>
  <span m="2479540">when</span> <span m="2479660">you</span> <span m="2479760">have</span>
  <span m="2479890">constraints,</span> <span m="2480410">because</span> <span m="2480510">you</span>
  <span m="2480590">have</span> <span m="2480720">to</span> <span m="2480810">worry</span>
  <span m="2480990">about</span> <span m="2481270">descent,</span> <span m="2482150">but</span>
  <span m="2482310">also</span> <span m="2482580">about</span> <span m="2482860">satisfying</span>
  <span m="2483430">the</span> <span m="2483520">constraints.</span> <span m="2486112">But</span>
  <span m="2486550">again,</span> <span m="2486780">if</span> <span m="2486910">you</span>
  <span m="2487020">take</span> <span m="2487260">optimization</span> <span m="2487575">class</span>
  <span m="2488140">you''ll</span> <span m="2488490">learn</span> <span m="2489140">lots</span>
  <span m="2489640">of</span> <span m="2490140">stuff</span> <span m="2490640">there.</span></p><p><span
  m="2491640">AUDIENCE: [INAUDIBLE]</span></p><p><span m="2495140">KAREN WILLCOX:
  Yeah.</span> <span m="2495440">So it</span> <span m="2495570">depends</span> <span
  m="2495980">on</span> <span m="2496070">the</span> <span m="2496190">algorithm.</span>
  <span m="2497900">Some</span> <span m="2498140">algorithms</span> <span m="2498710">will</span>
  <span m="2498890">allow</span> <span m="2499400">it</span> <span m="2499660">to</span>
  <span m="2499860">violate</span> <span m="2500280">the</span> <span m="2500360">constraints</span>
  <span m="2500810">a</span> <span m="2500860">little</span> <span m="2501060">bit</span>
  <span m="2501170">along</span> <span m="2501420">the</span> <span m="2501520">way.</span>
  <span m="2502310">Some</span> <span m="2502630">will</span> <span m="2502740">not.</span>
  <span m="2504150">And</span> <span m="2504250">there</span> <span m="2504390">are</span>
  <span m="2504490">all</span> <span m="2504990">lots</span> <span m="2505490">of</span>
  <span m="2505550">different</span> <span m="2505780">ways</span> <span m="2505940">of</span>
  <span m="2506020">handling</span> <span m="2506340">constraints.</span> <span m="2506930">There</span>
  <span m="2507040">are</span> <span m="2507090">things</span> <span m="2507300">called</span>
  <span m="2507646">penalty</span> <span m="2507992">methods.</span> <span m="2508340">There</span>
  <span m="2508440">are</span> <span m="2508470">things</span> <span m="2508710">called</span>
  <span m="2508860">barrier</span> <span m="2509270">methods.</span> <span m="2510570">There
  are</span> <span m="2510740">interior</span> <span m="2511220">point--</span> <span
  m="2512020">the</span> <span m="2512330">barrier</span> <span m="2512570">methods</span>
  <span m="2512900">related</span> <span m="2513100">to interior</span> <span m="2513520">point</span>
  <span m="2513740">methods</span> <span m="2513950">that</span> <span m="2514040">force</span>
  <span m="2514470">things</span> <span m="2514740">to</span> <span m="2514840">stay</span>
  <span m="2515700">away</span> <span m="2516210">inside</span> <span m="2516640">the</span>
  <span m="2516720">constraints.</span> <span m="2517650">It</span> <span m="2517840">just</span>
  <span m="2517940">depends</span> <span m="2518200">on</span> <span m="2518690">what</span>
  <span m="2518910">algorithm</span> <span m="2519340">you</span> <span m="2520518">use.</span></p><p><span
  m="2521760">But</span> <span m="2521930">that</span> <span m="2522190">sort</span>
  <span m="2522450">of</span> <span m="2522750">relates</span> <span m="2523250">to</span>
  <span m="2523330">the</span> <span m="2523420">next</span> <span m="2523720">part</span>
  <span m="2524000">that</span> <span m="2524130">I</span> <span m="2524190">want</span>
  <span m="2524340">to</span> <span m="2524420">show</span> <span m="2524600">you,</span>
  <span m="2524860">which</span> <span m="2525040">is</span> <span m="2525220">now</span>
  <span m="2525460">when</span> <span m="2525580">you</span> <span m="2525650">think</span>
  <span m="2525880">about</span> <span m="2526680">convergence,</span> <span m="2527530">so</span>
  <span m="2527640">here</span> <span m="2527890">is</span> <span m="2527960">the</span>
  <span m="2528070">objective</span> <span m="2528530">function</span> <span m="2528910">value.</span>
  <span m="2529910">This</span> <span m="2530170">is</span> <span m="2531480">the</span>
  <span m="2532380">iteration.</span> <span m="2533210">So</span> <span m="2533680">you</span>
  <span m="2533820">can</span> <span m="2533950">see</span> <span m="2534080">the</span>
  <span m="2534210">objective is</span> <span m="2534670">coming</span> <span m="2534990">down,</span>
  <span m="2535510">but</span> <span m="2535660">you</span> <span m="2535740">don''t</span>
  <span m="2536150">just</span> <span m="2536330">want</span> <span m="2536470">to</span>
  <span m="2536540">worry</span> <span m="2536850">about</span> <span m="2537630">what''s</span>
  <span m="2537810">happening</span> <span m="2538110">now</span> <span m="2538300">with</span>
  <span m="2538420">the</span> <span m="2538530">objective.</span> <span m="2538910">You</span>
  <span m="2539010">also</span> <span m="2539180">have</span> <span m="2539280">to</span>
  <span m="2539370">look</span> <span m="2539540">at</span> <span m="2539630">the</span>
  <span m="2539700">constraint</span> <span m="2540160">violation.</span> <span m="2541390">And</span>
  <span m="2541580">here</span> <span m="2541910">it</span> <span m="2542010">[? skips
  ?]</span> <span m="2542310">[? forward ?].</span> <span m="2542590">It</span> <span
  m="2542690">looks</span> <span m="2542900">like</span> <span m="2543050">we</span>
  <span m="2543160">found</span> <span m="2543380">a</span> <span m="2543430">pretty</span>
  <span m="2543650">good</span> <span m="2543830">design,</span> <span m="2544840">but</span>
  <span m="2544980">actually</span> <span m="2545990">the</span> <span m="2546100">constraint</span>
  <span m="2546510">is</span> <span m="2546610">violated.</span> <span m="2547560">So</span>
  <span m="2547700">this</span> <span m="2547840">would</span> <span m="2547950">be</span>
  <span m="2548070">like</span> <span m="2548310">an</span> <span m="2548650">aircraft</span>
  <span m="2549170">wing</span> <span m="2549380">that</span> <span m="2549510">exceeds</span>
  <span m="2549900">the</span> <span m="2549970">maximum</span> <span m="2550350">stress</span>
  <span m="2550610">constraint,</span> <span m="2551920">which</span> <span m="2552060">would</span>
  <span m="2552160">be</span> <span m="2552250">no</span> <span m="2552420">good.</span>
  <span m="2552620">And</span> <span m="2552720">so</span> <span m="2552790">that''s</span>
  <span m="2552920">why</span> <span m="2553000">we</span> <span m="2553100">have</span>
  <span m="2553250">to</span> <span m="2553330">keep</span> <span m="2553650">going.</span>
  <span m="2554810">And</span> <span m="2554970">actually</span> <span m="2555260">you</span>
  <span m="2555320">can</span> <span m="2555450">see</span> <span m="2555660">a</span>
  <span m="2555740">little</span> <span m="2555960">bit</span> <span m="2556060">of</span>
  <span m="2556120">an</span> <span m="2556210">increase</span> <span m="2556720">here</span>
  <span m="2556880">in</span> <span m="2556970">the</span> <span m="2557080">objective</span>
  <span m="2557670">to</span> <span m="2557790">get</span> <span m="2557970">the</span>
  <span m="2558020">constraint</span> <span m="2558710">violation</span> <span m="2559180">satisfied.</span></p><p><span
  m="2561210">And</span> <span m="2561370">I''ll</span> <span m="2561460">say</span>
  <span m="2561660">that</span> <span m="2561760">when</span> <span m="2562450">we</span>
  <span m="2562560">try</span> <span m="2562720">to</span> <span m="2562820">apply</span>
  <span m="2563090">these</span> <span m="2563270">kinds</span> <span m="2563510">of</span>
  <span m="2563590">methods</span> <span m="2564030">to</span> <span m="2564160">realistic</span>
  <span m="2564640">aircraft</span> <span m="2564980">design</span> <span m="2565320">problems</span>
  <span m="2565880">that</span> <span m="2566010">have</span> <span m="2566200">lots</span>
  <span m="2566510">of</span> <span m="2566650">variables,</span> <span m="2567230">they</span>
  <span m="2567340">have</span> <span m="2567700">even</span> <span m="2568010">lots</span>
  <span m="2568390">and lots</span> <span m="2568650">of</span> <span m="2568780">constraints.</span>
  <span m="2569880">And</span> <span m="2569980">satisfying</span> <span m="2570530">constraints</span>
  <span m="2571170">can</span> <span m="2571390">be</span> <span m="2572130">sometimes</span>
  <span m="2572880">just about</span> <span m="2573120">the</span> <span m="2573210">most</span>
  <span m="2573410">challenging</span> <span m="2574805">thing</span> <span m="2575100">for</span>
  <span m="2575210">the</span> <span m="2575310">optimizer.</span> <span m="2575590">So</span>
  <span m="2576596">it</span> <span m="2576960">can</span> <span m="2577090">often</span>
  <span m="2577300">find</span> <span m="2577570">good</span> <span m="2577730">solutions,</span>
  <span m="2578020">but</span> <span m="2578310">then</span> <span m="2578410">it</span>
  <span m="2578470">turns out</span> <span m="2578920">that</span> <span m="2579050">they</span>
  <span m="2579170">don''t</span> <span m="2580190">necessarily</span> <span m="2580600">satisfy</span>
  <span m="2581080">the</span> <span m="2581140">constraints.</span></p><p><span m="2581850">You</span>
  <span m="2581860">see</span> <span m="2582000">another</span> <span m="2582290">one</span>
  <span m="2582510">here.</span> <span m="2583960">In</span> <span m="2584040">this</span>
  <span m="2584170">case,</span> <span m="2584480">we</span> <span m="2584570">started</span>
  <span m="2584900">with</span> <span m="2585030">an</span> <span m="2585220">infeasible</span>
  <span m="2585920">design,</span> <span m="2586350">one that</span> <span m="2586750">violated</span>
  <span m="2587410">these</span> <span m="2587680">constraints,</span> <span m="2588075">or</span>
  <span m="2588470">violated</span> <span m="2589030">this</span> <span m="2589210">constraint.</span>
  <span m="2590360">So</span> <span m="2590490">you</span> <span m="2590570">see</span>
  <span m="2590750">first</span> <span m="2591090">of</span> <span m="2591160">all</span>
  <span m="2591280">the</span> <span m="2591380">optimizer</span> <span m="2591880">tries</span>
  <span m="2592170">to</span> <span m="2592260">get</span> <span m="2592370">it</span>
  <span m="2592440">back</span> <span m="2592630">to</span> <span m="2592710">the</span>
  <span m="2592780">feasible</span> <span m="2593190">region.</span> <span m="2593580">It</span>
  <span m="2593680">tries</span> <span m="2593900">to</span> <span m="2594360">make</span>
  <span m="2594540">sure</span> <span m="2594630">the</span> <span m="2594700">constraint
  is</span> <span m="2595150">satisfied.</span> <span m="2595670">And</span> <span
  m="2595790">then it</span> <span m="2596180">starts</span> <span m="2596740">searching.</span>
  <span m="2597910">And</span> <span m="2598070">actually</span> <span m="2598320">most</span>
  <span m="2598610">of</span> <span m="2598680">these</span> <span m="2598840">designs</span>
  <span m="2599280">are</span> <span m="2599370">infeasible.</span> <span m="2599750">It''s</span>
  <span m="2600130">only</span> <span m="2600600">at</span> <span m="2600760">the
  end that</span> <span m="2600890">we</span> <span m="2600980">come</span> <span
  m="2601800">here</span> <span m="2602000">to</span> <span m="2602120">the</span>
  <span m="2602220">local</span> <span m="2603900">optimum.</span> <span m="2606330">And</span>
  <span m="2606500">so</span> <span m="2606640">again,</span> <span m="2608410">there''s</span>
  <span m="2608720">the</span> <span m="2609010">function</span> <span m="2609410">value.</span>
  <span m="2610050">And</span> <span m="2610100">you</span> <span m="2610160">can</span>
  <span m="2610300">see</span> <span m="2610460">we</span> <span m="2610580">start</span>
  <span m="2610910">off</span> <span m="2611320">violating</span> <span m="2611790">the</span>
  <span m="2611860">constraint.</span> <span m="2612155">We</span> <span m="2612450">satisfy</span>
  <span m="2612820">it,</span> <span m="2613260">and then</span> <span m="2613420">we</span>
  <span m="2613480">go</span> <span m="2613620">back</span> <span m="2613870">outside</span>
  <span m="2614510">the</span> <span m="2614590">constraint,</span> <span m="2615130">and
  then</span> <span m="2615230">eventually</span> <span m="2615770">come</span> <span
  m="2616790">back</span> <span m="2617000">to</span> <span m="2617120">it</span>
  <span m="2617290">at the</span> <span m="2617732">end.</span></p><p><span m="2619060">And</span>
  <span m="2619320">then</span> <span m="2619380">the last</span> <span m="2620405">one</span>
  <span m="2623350">starts</span> <span m="2624820">again</span> <span m="2625060">over</span>
  <span m="2625210">here,</span> <span m="2625520">where</span> <span m="2625620">two</span>
  <span m="2625700">constraints</span> <span m="2626210">are</span> <span m="2626260">violated.</span>
  <span m="2627070">And</span> <span m="2627090">you</span> <span m="2627300">can</span>
  <span m="2627460">see</span> <span m="2627680">even</span> <span m="2627780">though</span>
  <span m="2628150">two</span> <span m="2628240">constraints</span> <span m="2628580">are</span>
  <span m="2628630">violated,</span> <span m="2629090">this one''s</span> <span m="2629380">actually</span>
  <span m="2630650">able</span> <span m="2630870">to</span> <span m="2630950">get</span>
  <span m="2631090">to</span> <span m="2631180">that</span> <span m="2631370">solution</span>
  <span m="2632120">pretty</span> <span m="2632930">easily.</span> <span m="2633760">One</span>
  <span m="2633930">thing</span> <span m="2634060">you</span> <span m="2634120">notice</span>
  <span m="2634370">is</span> <span m="2634470">none</span> <span m="2634690">of</span>
  <span m="2634750">the</span> <span m="2634820">ones</span> <span m="2635060">that</span>
  <span m="2635170">I</span> <span m="2635260">started</span> <span m="2635770">actually</span>
  <span m="2636070">found</span> <span m="2636350">the</span> <span m="2636420">global</span>
  <span m="2637370">optimum.</span> <span m="2639180">They</span> <span m="2639340">all</span>
  <span m="2639560">converge</span> <span m="2640300">to</span> <span m="2640430">the</span>
  <span m="2641840">local</span> <span m="2642200">optimum.</span> <span m="2642610">And</span>
  <span m="2642700">again,</span> <span m="2642910">if</span> <span m="2643010">you</span>
  <span m="2643070">like</span> <span m="2643220">to</span> <span m="2643290">think</span>
  <span m="2643470">more</span> <span m="2643640">in</span> <span m="2643740">3D,</span>
  <span m="2644490">remember</span> <span m="2644790">that</span> <span m="2644950">landscape</span>
  <span m="2645420">where</span> <span m="2645560">there</span> <span m="2645620">was</span>
  <span m="2645740">the</span> <span m="2645820">big</span> <span m="2646050">mountain</span>
  <span m="2646520">and the</span> <span m="2646710">two</span> <span m="2646820">smaller</span>
  <span m="2646880">peaks.</span> <span m="2648230">In</span> <span m="2648360">this</span>
  <span m="2648540">case,</span> <span m="2649100">we</span> <span m="2649280">started</span>
  <span m="2649600">here,</span> <span m="2649940">we</span> <span m="2650040">started</span>
  <span m="2650340">here,</span> <span m="2650600">and we</span> <span m="2650700">started</span>
  <span m="2650970">here,</span> <span m="2651220">and</span> <span m="2651330">they</span>
  <span m="2651370">all</span> <span m="2651570">ended</span> <span m="2651770">up</span>
  <span m="2652450">over</span> <span m="2652560">here.</span> <span m="2652950">Probably
  we</span> <span m="2653310">would</span> <span m="2653480">have</span> <span m="2653620">to</span>
  <span m="2653700">start</span> <span m="2653880">on</span> <span m="2653960">the</span>
  <span m="2654060">other</span> <span m="2654220">side</span> <span m="2654520">of</span>
  <span m="2654670">this</span> <span m="2654890">ridge</span> <span m="2655190">here</span>
  <span m="2655500">in</span> <span m="2655570">order</span> <span m="2655750">to</span>
  <span m="2655870">get</span> <span m="2656040">up</span> <span m="2656540">into</span>
  <span m="2656720">the</span> <span m="2657200">global</span> <span m="2659480">optimum.</span></p><p><span
  m="2664470">OK.</span> <span m="2664890">So</span> <span m="2666640">I</span> <span
  m="2666750">know</span> <span m="2666900">you</span> <span m="2667040">don''t</span>
  <span m="2668540">really</span> <span m="2668740">know</span> <span m="2668980">very</span>
  <span m="2669210">much</span> <span m="2669490">about</span> <span m="2671211">constraint</span>
  <span m="2671650">optimization,</span> <span m="2672390">but</span> <span m="2672570">you</span>
  <span m="2672650">could</span> <span m="2672780">all be</span> <span m="2672950">[?
  dangerous ?]</span> <span m="2673360">[? utilize ?]</span> <span m="2674270">for</span>
  <span m="2674360">the</span> <span m="2674440">next</span> <span m="2674690">year</span>
  <span m="2674930">if</span> <span m="2675040">you</span> <span m="2675150">wanted</span>
  <span m="2675490">to</span> <span m="2675600">be.</span> <span m="2677490">It''s</span>
  <span m="2677680">actually</span> <span m="2677940">a</span> <span m="2678140">really</span>
  <span m="2678560">powerful</span> <span m="2679050">thing</span> <span m="2679250">if</span>
  <span m="2679390">you''re</span> <span m="2679480">trying</span> <span m="2679620">to</span>
  <span m="2679690">do</span> <span m="2679790">a</span> <span m="2679840">design</span>
  <span m="2680180">problem,</span> <span m="2681440">or</span> <span m="2682710">you</span>
  <span m="2682980">have</span> <span m="2683150">simulation</span> <span m="2683580">code</span>
  <span m="2683780">and</span> <span m="2683870">you</span> <span m="2683930">want</span>
  <span m="2684060">to</span> <span m="2684120">explore</span> <span m="2684480">what''s</span>
  <span m="2684690">going</span> <span m="2684900">on</span> <span m="2684990">with</span>
  <span m="2685110">the</span> <span m="2685180">parameters.</span> <span m="2685933">The</span>
  <span m="2686346">toolbox</span> <span m="2687150">in</span> <span m="2687220">MATLAB</span>
  <span m="2687580">is</span> <span m="2688450">really</span> <span m="2688740">good.</span>
  <span m="2690060">And</span> <span m="2690190">then if</span> <span m="2690350">you</span>
  <span m="2690430">say</span> <span m="2690600">for</span> <span m="2690690">grad</span>
  <span m="2690900">school,</span> <span m="2691090">you</span> <span m="2691190">can</span>
  <span m="2691350">take</span> <span m="2691880">the</span> <span m="2691910">graduate</span>
  <span m="2692240">class</span> <span m="2692490">that</span> <span m="2692610">I</span>
  <span m="2692660">teach</span> <span m="2693040">that</span> <span m="2693530">goes</span>
  <span m="2693730">into</span> <span m="2693920">this</span> <span m="2694020">stuff</span>
  <span m="2694290">in</span> <span m="2694400">much,</span> <span m="2695320">much</span>
  <span m="2695470">more</span> <span m="2695640">detail.</span></p><p><span m="2696578">AUDIENCE:
  Is there</span> <span m="2697516">anything</span> <span m="2697985">MATLAB,</span>
  <span m="2698923">like</span> <span m="2699861">other--</span></p><p><span m="2700800">KAREN
  WILLCOX: Yeah.</span> <span m="2701780">Absolutely.</span> <span m="2702270">So</span>
  <span m="2703250">there''s</span> <span m="2703490">all</span> <span m="2704190">kind</span>
  <span m="2704530">of</span> <span m="2705290">optimization</span> <span m="2705950">toolboxes.</span>
  <span m="2706450">I</span> <span m="2706520">mentioned</span> <span m="2706930">Professor</span>
  <span m="2707260">Johnson</span> <span m="2708390">in</span> <span m="2708560">[INAUDIBLE],</span>
  <span m="2708945">where</span> <span m="2709230">he''s</span> <span m="2709440">implemented</span>
  <span m="2709950">a</span> <span m="2710030">lot</span> <span m="2710260">of</span>
  <span m="2711050">some</span> <span m="2711240">of</span> <span m="2711370">the</span>
  <span m="2712230">less</span> <span m="2712510">mainstream</span> <span m="2713150">optimization</span>
  <span m="2713770">methods.</span> <span m="2714260">That''s</span> <span m="2714750">nice.</span>
  <span m="2715090">And</span> <span m="2715180">then</span> <span m="2715350">there''s</span>
  <span m="2717850">all</span> <span m="2718020">kinds</span> <span m="2718280">of</span>
  <span m="2718390">other</span> <span m="2719750">toolboxes,</span> <span m="2720580">things</span>
  <span m="2720680">like</span> <span m="2720890">CPLEX</span> <span m="2721280">that</span>
  <span m="2721390">a</span> <span m="2721430">lot</span> <span m="2721570">of</span>
  <span m="2721650">optimization</span> <span m="2722150">people</span> <span m="2722650">use.</span>
  <span m="2725390">What</span> <span m="2725560">are</span> <span m="2725740">some</span>
  <span m="2725880">of</span> <span m="2725950">the</span> <span m="2726010">big</span>
  <span m="2726150">ones?</span> <span m="2726320">I</span> <span m="2726420">would</span>
  <span m="2726560">say</span> <span m="2726750">though</span> <span m="2726910">MATLAB</span>
  <span m="2727360">has</span> <span m="2727530">really</span> <span m="2727730">started</span>
  <span m="2728070">to</span> <span m="2728280">sort</span> <span m="2728400">of</span>
  <span m="2728490">dominate</span> <span m="2728830">the</span> <span m="2728890">market</span>
  <span m="2729260">in</span> <span m="2729450">a</span> <span m="2729560">way</span>
  <span m="2729900">because</span> <span m="2730640">MATLAB''s</span> <span m="2730990">optimization</span>
  <span m="2731520">toolbox</span> <span m="2731850">has</span> <span m="2732000">become</span>
  <span m="2732550">really</span> <span m="2732860">good,</span> <span m="2733580">especially</span>
  <span m="2734010">in the last</span> <span m="2734440">10</span> <span m="2734660">years.</span>
  <span m="2735550">And</span> <span m="2735730">I</span> <span m="2735790">think</span>
  <span m="2736990">the</span> <span m="2737080">gradient</span> <span m="2738170">pace,</span>
  <span m="2738480">they</span> <span m="2738630">have</span> <span m="2738760">the</span>
  <span m="2738840">state</span> <span m="2739060">of</span> <span m="2739130">the</span>
  <span m="2739545">art,</span> <span m="2739960">the</span> <span m="2740130">Newton</span>
  <span m="2740490">methods</span> <span m="2740900">with</span> <span m="2741040">all</span>
  <span m="2741260">the</span> <span m="2741750">bells</span> <span m="2742020">and</span>
  <span m="2742120">whistles</span> <span m="2742440">on them.</span></p><p><span
  m="2743440">And</span> <span m="2743660">then there</span> <span m="2743750">are</span>
  <span m="2743780">also a</span> <span m="2743820">lot</span> <span m="2743980">of</span>
  <span m="2744560">user-contributed</span> <span m="2747590">algorithms.</span> <span
  m="2751200">I''ll</span> <span m="2751370">show</span> <span m="2751590">you.</span>
  <span m="2752125">Let me see</span> <span m="2752470">if</span> <span m="2752640">I</span>
  <span m="2752730">can</span> <span m="2752900">run</span> <span m="2753060">it,</span>
  <span m="2753950">something</span> <span m="2754190">that</span> <span m="2754310">I</span>
  <span m="2754370">don''t</span> <span m="2755350">approve</span> <span m="2755710">of.</span></p><p><span
  m="2756545">AUDIENCE: [INAUDIBLE]</span></p><p><span m="2768680">KAREN WILLCOX:
  That''s</span> <span m="2768900">right.</span> <span m="2769330">Yeah.</span> <span
  m="2770220">I</span> <span m="2770370">gave</span> <span m="2770540">you</span>
  <span m="2770610">the--</span></p><p><span m="2770850">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="2773538">KAREN WILLCOX: I</span> <span m="2773990">gave</span> <span m="2774260">you</span>
  <span m="2774330">the</span> <span m="2774430">link</span> <span m="2774610">to</span>
  <span m="2774690">that</span> <span m="2774920">in</span> <span m="2775230">the</span>
  <span m="2775555">last</span> <span m="2775880">lecture</span> <span m="2776070">notes,</span>
  <span m="2776476">to</span> <span m="2776882">Professor Johnson''s</span> <span
  m="2777288">website.</span> <span m="2777694">And</span> <span m="2778100">actually</span>
  <span m="2778590">since</span> <span m="2778920">you said</span> <span m="2779100">Python,</span>
  <span m="2779530">also</span> <span m="2779670">pyOpt.</span> <span m="2780604">Right</span>
  <span m="2781011">now</span> <span m="2781780">pyOpt</span> <span m="2782410">is</span>
  <span m="2782650">starting</span> <span m="2783020">to</span> <span m="2783110">create</span>
  <span m="2783460">all</span> <span m="2783610">the</span> <span m="2783750">optimization</span>
  <span m="2784290">algorithms</span> <span m="2784690">in</span> <span m="2784780">Python.</span></p><p><span
  m="2787205">AUDIENCE: [INAUDIBLE]</span></p><p><span m="2788660">KAREN WILLCOX:
  What</span> <span m="2788800">about</span> <span m="2789680">[? Julian ?]?</span></p><p><span
  m="2791160">AUDIENCE: [INAUDIBLE]</span></p><p><span m="2792120">KAREN WILLCOX:
  Is that</span> <span m="2792600">Professor</span> <span m="2793080">Edelman''s</span>
  <span m="2793580">stuff?</span></p><p><span m="2794080">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="2809189">KAREN WILLCOX: Oh, once</span> <span m="2809672">you graduate?</span>
  <span m="2811130">But</span> <span m="2811240">that''s</span> <span m="2811440">part</span>
  <span m="2811640">of</span> <span m="2811700">their</span> <span m="2811790">model</span>
  <span m="2812140">is</span> <span m="2812330">for you</span> <span m="2812540">to</span>
  <span m="2812630">convince</span> <span m="2813040">your</span> <span m="2813180">employers</span>
  <span m="2814580">to--</span> <span m="2815580">but</span> <span m="2815690">that''s</span>
  <span m="2816330">why</span> <span m="2816450">you</span> <span m="2816550">stay</span>
  <span m="2816790">in</span> <span m="2816870">academia</span> <span m="2817368">is</span>
  <span m="2817866">you get</span> <span m="2818364">perpetual</span> <span m="2818862">very
  cheap</span> <span m="2819360">MATLAB.</span> <span m="2819858">It''s</span> <span
  m="2820360">one</span> <span m="2820510">of</span> <span m="2820570">the</span>
  <span m="2820660">great</span> <span m="2820960">perks</span> <span m="2821280">of</span>
  <span m="2821360">being</span> <span m="2821540">an</span> <span m="2821640">academic.</span></p><p><span
  m="2822140">AUDIENCE: [INAUDIBLE]</span></p><p><span m="2826640">KAREN WILLCOX:
  So</span> <span m="2827140">I</span> <span m="2827250">want</span> <span m="2827400">to</span>
  <span m="2827460">show</span> <span m="2827570">you</span> <span m="2827710">something</span>
  <span m="2828050">again</span> <span m="2828570">of</span> <span m="2828800">which</span>
  <span m="2829020">I</span> <span m="2829100">definitely</span> <span m="2829440">don''t</span>
  <span m="2829610">approve,</span> <span m="2830000">but</span> <span m="2830160">again</span>
  <span m="2830430">this</span> <span m="2831080">triggered</span> <span m="2831290">in</span>
  <span m="2831360">my</span> <span m="2831510">mind</span> <span m="2831730">because</span>
  <span m="2831930">I</span> <span m="2831980">said</span> <span m="2832210">user-contributed</span>
  <span m="2832980">toolboxes.</span> <span m="2833850">There''s a</span> <span m="2834070">whole</span>
  <span m="2834250">class</span> <span m="2834600">of</span> <span m="2835480">optimization--</span>
  <span m="2836260">I''m going to</span> <span m="2836400">use</span> <span m="2836490">the</span>
  <span m="2836590">word</span> <span m="2836740">&quot;optimization&quot;</span>
  <span m="2837045">in</span> <span m="2837350">quotes--</span> <span m="2838060">methods</span>
  <span m="2838480">that</span> <span m="2838610">don''t</span> <span m="2838910">use</span>
  <span m="2839150">gradient,</span> <span m="2839770">that</span> <span m="2839950">don''t</span>
  <span m="2840120">really</span> <span m="2840330">have</span> <span m="2840600">any</span>
  <span m="2841290">convergence</span> <span m="2841625">theory.</span> <span m="2843410">A</span>
  <span m="2843790">couple</span> <span m="2844030">of</span> <span m="2844090">them</span>
  <span m="2844290">have</span> <span m="2845990">some</span> <span m="2846756">theories</span>
  <span m="2847520">associated</span> <span m="2847840">with</span> <span m="2848010">them.</span>
  <span m="2849620">They''re</span> <span m="2849930">typically called</span> <span
  m="2850420">heuristic</span> <span m="2851270">algorithms</span> <span m="2851810">because</span>
  <span m="2852080">they</span> <span m="2852240">use</span> <span m="2852470">rules</span>
  <span m="2853380">to</span> <span m="2853510">search</span> <span m="2853760">the</span>
  <span m="2853850">design</span> <span m="2854200">space.</span></p><p><span m="2854560">And</span>
  <span m="2854670">one</span> <span m="2854820">of</span> <span m="2854980">the</span>
  <span m="2855060">most</span> <span m="2855400">popular</span> <span m="2856380">in</span>
  <span m="2856510">aerospace</span> <span m="2856860">engineering</span> <span m="2857310">is
  something</span> <span m="2857460">called</span> <span m="2857735">a</span> <span
  m="2858010">genetic</span> <span m="2858130">algorithm,</span> <span m="2859330">which</span>
  <span m="2859580">basically</span> <span m="2860970">uses</span> <span m="2861460">all</span>
  <span m="2861650">the</span> <span m="2861740">rules</span> <span m="2862040">of</span>
  <span m="2862120">natural</span> <span m="2862490">selection,</span> <span m="2863620">and</span>
  <span m="2863690">mimics</span> <span m="2863870">the</span> <span m="2863950">rules</span>
  <span m="2864120">of</span> <span m="2864190">natural</span> <span m="2864470">selection</span>
  <span m="2865280">to</span> <span m="2866200">optimize</span> <span m="2866710">the</span>
  <span m="2866780">design</span> <span m="2867110">space.</span> <span m="2867545">So</span>
  <span m="2867980">this</span> <span m="2868260">is</span> <span m="2868670">the</span>
  <span m="2868760">function</span> <span m="2869040">that</span> <span m="2869140">we
  were</span> <span m="2869310">looking</span> <span m="2869590">at</span> <span m="2869780">on</span>
  <span m="2870070">Wednesday.</span> <span m="2870570">And</span> <span m="2870660">remember,</span>
  <span m="2871320">we</span> <span m="2871530">did</span> <span m="2871680">a gradient-based</span>
  <span m="2872530">method,</span> <span m="2872980">or</span> <span m="2873200">we</span>
  <span m="2873290">did</span> <span m="2873620">the</span> <span m="2873850">[? naldamete
  ?]</span> <span m="2874080">simplex,</span> <span m="2874470">where</span> <span
  m="2874560">we</span> <span m="2874630">had</span> <span m="2874750">a</span> <span
  m="2874790">little</span> <span m="2875040">asterisk,</span> <span m="2876270">but</span>
  <span m="2876400">with</span> <span m="2876540">our</span> <span m="2876650">initial</span>
  <span m="2876950">guess,</span> <span m="2877740">and</span> <span m="2877880">then</span>
  <span m="2878230">the</span> <span m="2878330">asterisk</span> <span m="2878730">marched</span>
  <span m="2879180">and</span> <span m="2879300">found</span> <span m="2879670">the</span>
  <span m="2879770">top</span> <span m="2879980">of</span> <span m="2880040">the</span>
  <span m="2880130">hill,</span> <span m="2880510">or got</span> <span m="2880680">to</span>
  <span m="2880760">one</span> <span m="2881640">of</span> <span m="2881710">the</span>
  <span m="2881790">tops</span> <span m="2882040">of</span> <span m="2882130">the</span>
  <span m="2882200">hills</span> <span m="2882460">depending</span> <span m="2882710">on</span>
  <span m="2882770">where</span> <span m="2882890">it</span> <span m="2883000">started.</span></p><p><span
  m="2884250">So</span> <span m="2884410">a</span> <span m="2884560">genetic</span>
  <span m="2884750">algorithm</span> <span m="2885190">is</span> <span m="2885280">a</span>
  <span m="2885330">population-based</span> <span m="2887150">method,</span> <span
  m="2887600">which</span> <span m="2887670">means</span> <span m="2887910">you</span>
  <span m="2887970">don''t</span> <span m="2888130">have</span> <span m="2888300">one</span>
  <span m="2888550">design</span> <span m="2888930">on</span> <span m="2889030">each</span>
  <span m="2889190">iteration,</span> <span m="2889660">but</span> <span m="2889810">you</span>
  <span m="2889910">have</span> <span m="2890120">many.</span> <span m="2891210">And</span>
  <span m="2891430">I</span> <span m="2891470">don''t</span> <span m="2891600">know</span>
  <span m="2891670">how</span> <span m="2891760">many</span> <span m="2891900">there</span>
  <span m="2892050">are</span> <span m="2892190">in</span> <span m="2892250">this</span>
  <span m="2892410">population,</span> <span m="2892970">maybe</span> <span m="2893180">20</span>
  <span m="2893720">or</span> <span m="2893860">30.</span> <span m="2894810">So</span>
  <span m="2894930">there</span> <span m="2895140">are</span> <span m="2895220">20</span>
  <span m="2895540">or</span> <span m="2895640">30</span> <span m="2896140">initial</span>
  <span m="2896690">guesses,</span> <span m="2897180">and</span> <span m="2897430">that''s
  the</span> <span m="2897590">population.</span> <span m="2899060">And</span> <span
  m="2899080">when</span> <span m="2899210">I</span> <span m="2899300">set</span>
  <span m="2899580">it</span> <span m="2900400">running,</span> <span m="2900700">what</span>
  <span m="2900820">you''re</span> <span m="2900910">going</span> <span m="2901030">to</span>
  <span m="2901130">see</span> <span m="2901340">is</span> <span m="2901520">that</span>
  <span m="2901650">each</span> <span m="2902030">iteration,</span> <span m="2903380">it''s</span>
  <span m="2903640">evolving</span> <span m="2904160">this</span> <span m="2904300">population.</span></p><p><span
  m="2905270">So</span> <span m="2905300">if</span> <span m="2905480">there</span>
  <span m="2905700">are,</span> <span m="2906650">let''s say</span> <span m="2906940">there
  are 30</span> <span m="2907370">there,</span> <span m="2908100">on</span> <span
  m="2908220">the</span> <span m="2908280">next</span> <span m="2908550">iteration</span>
  <span m="2908960">it''s</span> <span m="2909060">going</span> <span m="2909180">to</span>
  <span m="2909240">be</span> <span m="2909330">30</span> <span m="2909660">more</span>
  <span m="2910230">and</span> <span m="2910340">then</span> <span m="2910460">30</span>
  <span m="2910700">more</span> <span m="2910960">and</span> <span m="2911110">30</span>
  <span m="2911330">more,</span> <span m="2912180">and</span> <span m="2912300">the</span>
  <span m="2912370">way</span> <span m="2912550">it''s</span> <span m="2912720">evolving</span>
  <span m="2913460">it''s</span> <span m="2913910">taking</span> <span m="2915190">designs</span>
  <span m="2915890">and</span> <span m="2916000">then</span> <span m="2916150">the</span>
  <span m="2916230">parents</span> <span m="2916730">and</span> <span m="2916820">they''re</span>
  <span m="2916930">having</span> <span m="2917170">children,</span> <span m="2918390">then</span>
  <span m="2918600">it''s</span> <span m="2918780">figuring</span> <span m="2919170">out</span>
  <span m="2919290">which</span> <span m="2919470">children</span> <span m="2919740">to</span>
  <span m="2919810">keep</span> <span m="2920080">and</span> <span m="2920180">which</span>
  <span m="2920340">ones</span> <span m="2920620">to</span> <span m="2920660">not</span>
  <span m="2921073">keep.</span> <span m="2921900">And</span> <span m="2921930">it''s</span>
  <span m="2922110">introducing</span> <span m="2922370">a</span> <span m="2922630">mutation</span>
  <span m="2923460">that</span> <span m="2923690">causes</span> <span m="2923990">designs</span>
  <span m="2924360">to</span> <span m="2924430">jump</span> <span m="2924650">around.</span>
  <span m="2925800">So</span> <span m="2926230">there''s</span> <span m="2926370">a</span>
  <span m="2926440">whole</span> <span m="2926920">sort</span> <span m="2927110">of</span>
  <span m="2927480">thing.</span> <span m="2927810">And</span> <span m="2927920">Professor</span>
  <span m="2928390">[? Divic ?]</span> <span m="2929330">knows</span> <span m="2929500">a</span>
  <span m="2929770">lot</span> <span m="2930010">about</span> <span m="2930260">genetic</span>
  <span m="2930590">algorithms.</span> <span m="2931910">So</span> <span m="2932790">if</span>
  <span m="2932940">you''re</span> <span m="2933070">interested,</span> <span m="2933880">you</span>
  <span m="2934060">could</span> <span m="2934210">ask</span> <span m="2934460">him.</span>
  <span m="2934610">But</span> <span m="2934720">let</span> <span m="2934820">me</span>
  <span m="2935620">set</span> <span m="2935740">it</span> <span m="2935860">running,</span>
  <span m="2936440">and</span> <span m="2936610">you''ll</span> <span m="2936780">see</span>
  <span m="2936930">you''ll</span> <span m="2937060">see</span> <span m="2937240">what</span>
  <span m="2937370">I</span> <span m="2937440">mean.</span></p><p><span m="2938406">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="2941310">KAREN WILLCOX: Yeah,</span> <span m="2941530">the</span>
  <span m="2941610">heuristic</span> <span m="2942060">is</span> <span m="2942190">all</span>
  <span m="2942460">the</span> <span m="2942540">things</span> <span m="2942970">about--</span>
  <span m="2945550">you</span> <span m="2945690">take</span> <span m="2945990">designs</span>
  <span m="2946580">and</span> <span m="2946970">you</span> <span m="2947150">have</span>
  <span m="2947260">to</span> <span m="2947350">encode</span> <span m="2947720">them</span>
  <span m="2947840">with</span> <span m="2947980">chromosomes.</span> <span m="2949240">And</span>
  <span m="2949320">then</span> <span m="2949480">there</span> <span m="2949670">are</span>
  <span m="2949750">heuristics</span> <span m="2949990">about</span> <span m="2950390">the</span>
  <span m="2951160">different</span> <span m="2951450">mating</span> <span m="2951850">strategies</span>
  <span m="2952710">and</span> <span m="2953110">then the</span> <span m="2953270">mutations.</span>
  <span m="2954220">So</span> <span m="2954290">there''s</span> <span m="2954570">a</span>
  <span m="2954620">lot</span> <span m="2954770">of--</span> <span m="2955480">and</span>
  <span m="2955610">at</span> <span m="2955680">the</span> <span m="2955780">end</span>
  <span m="2955910">of</span> <span m="2955980">the</span> <span m="2956050">day,</span>
  <span m="2956520">you</span> <span m="2957450">don''t</span> <span m="2957590">have</span>
  <span m="2957720">guarantees</span> <span m="2958060">about</span> <span m="2958280">optimality.</span>
  <span m="2958740">But</span> <span m="2959660">if</span> <span m="2959820">you</span>
  <span m="2959960">have</span> <span m="2960090">a</span> <span m="2960150">problem</span>
  <span m="2961160">where</span> <span m="2961390">you</span> <span m="2961520">can</span>
  <span m="2961790">compute</span> <span m="2962080">gradients,</span> <span m="2963270">maybe</span>
  <span m="2963560">where</span> <span m="2963700">the</span> <span m="2963780">models</span>
  <span m="2964280">are</span> <span m="2964400">not</span> <span m="2967160">differentiable,</span>
  <span m="2967920">and</span> <span m="2968090">you</span> <span m="2968160">just</span>
  <span m="2968320">kind</span> <span m="2968440">of</span> <span m="2968500">want</span>
  <span m="2968620">to</span> <span m="2968680">spray</span> <span m="2968970">points</span>
  <span m="2969330">everywhere</span> <span m="2969920">and</span> <span m="2970240">[?
  work ?]</span> <span m="2970440">as</span> <span m="2970580">well</span> <span m="2970740">as</span>
  <span m="2970830">you</span> <span m="2970910">can,</span> <span m="2971160">maybe</span>
  <span m="2971606">something like</span> <span m="2972052">this</span> <span m="2972500">is
  OK.</span> <span m="2972900">I</span> <span m="2973000">wouldn''t</span> <span m="2973220">call
  it</span> <span m="2973390">optimization.</span></p><p><span m="2973890">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="2976880">KAREN WILLCOX: Yeah,</span> <span m="2977080">if</span>
  <span m="2977150">you</span> <span m="2977220">want</span> <span m="2977350">to</span>
  <span m="2977410">avoid</span> <span m="2977705">local--</span> <span m="2978000">but</span>
  <span m="2978230">I</span> <span m="2978360">think</span> <span m="2978950">you</span>
  <span m="2979120">avoid</span> <span m="2979370">local</span> <span m="2979590">minima</span>
  <span m="2979930">by</span> <span m="2980050">not</span> <span m="2980260">getting</span>
  <span m="2980450">to</span> <span m="2980520">any</span> <span m="2980710">minimum</span>
  <span m="2981040">at all.</span> <span m="2983100">They</span> <span m="2983280">work</span>
  <span m="2983590">great</span> <span m="2983950">for</span> <span m="2984070">when
  you</span> <span m="2984200">have</span> <span m="2984930">2D.</span> <span m="2985320">But
  you</span> <span m="2985763">see</span> <span m="2986206">the</span> <span m="2986650">idea</span>
  <span m="2986880">how</span> <span m="2987570">dramatically</span> <span m="2988140">different</span>
  <span m="2988560">it</span> <span m="2989053">is.</span> <span m="2990040">There''s</span>
  <span m="2990570">simulated</span> <span m="2990980">annealing</span> <span m="2991390">which</span>
  <span m="2991640">does</span> <span m="2991870">have</span> <span m="2992480">some</span>
  <span m="2993750">theory</span> <span m="2994140">associated</span> <span m="2994450">with</span>
  <span m="2994600">it.</span> <span m="2994730">There''s</span> <span m="2994850">particle</span>
  <span m="2995250">swarm</span> <span m="2995550">optimization.</span> <span m="2996280">There''s</span>
  <span m="2996410">ant</span> <span m="2996650">colonies.</span> <span m="2997150">There''s</span>
  <span m="2997440">lots</span> <span m="2997530">of</span> <span m="2998070">analogies</span>
  <span m="2998710">with</span> <span m="2999130">nature.</span> <span m="2999480">So</span>
  <span m="2999610">there''s</span> <span m="2999750">this</span> <span m="2999810">whole</span>
  <span m="3000080">other</span> <span m="3000540">class</span> <span m="3001570">of</span>
  <span m="3001760">optimization</span> <span m="3002320">algorithms</span> <span
  m="3002990">which</span> <span m="3003080">can</span> <span m="3003250">be</span>
  <span m="3003350">kind</span> <span m="3003530">of</span> <span m="3003590">fun.</span>
  <span m="3007310">OK.</span> <span m="3009690">And</span> <span m="3009960">so</span>
  <span m="3010220">if</span> <span m="3010350">you</span> <span m="3010440">wanted</span>
  <span m="3010620">to</span> <span m="3010700">find</span> <span m="3011000">those,</span>
  <span m="3011580">you</span> <span m="3011690">could</span> <span m="3011830">probably</span>
  <span m="3012050">go</span> <span m="3012250">find</span> <span m="3012400">other</span>
  <span m="3012760">toolboxes</span> <span m="3012940">as</span> <span m="3013387">well.</span></p><p><span
  m="3016520">OK,</span> <span m="3016930">so</span> <span m="3018550">I</span> <span
  m="3018640">think</span> <span m="3018830">I''ll</span> <span m="3019000">skip</span>
  <span m="3019280">over</span> <span m="3019840">the</span> <span m="3020050">1D</span>
  <span m="3020460">search.</span> <span m="3020900">It''s</span> <span m="3021070">not</span>
  <span m="3021620">all</span> <span m="3021830">that</span> <span m="3022000">important.</span>
  <span m="3022700">But</span> <span m="3022710">I</span> <span m="3022760">want</span>
  <span m="3022890">to</span> <span m="3022950">spend</span> <span m="3023220">the</span>
  <span m="3023300">last</span> <span m="3023720">little</span> <span m="3023990">bit</span>
  <span m="3024240">just</span> <span m="3024460">talking</span> <span m="3024750">about</span>
  <span m="3025476">surrogate</span> <span m="3026330">modeling</span> <span m="3026800">and</span>
  <span m="3027100">reduced</span> <span m="3027360">[INAUDIBLE]</span> <span m="3027610">models.</span>
  <span m="3030250">So</span> <span m="3031450">maybe</span> <span m="3031730">you</span>
  <span m="3031830">have</span> <span m="3031980">a</span> <span m="3032040">sense</span>
  <span m="3032620">that</span> <span m="3032990">when</span> <span m="3033140">we</span>
  <span m="3033290">run</span> <span m="3033570">an</span> <span m="3033660">optimization</span>
  <span m="3034280">algorithm,</span> <span m="3034590">we</span> <span m="3034670">have</span>
  <span m="3034780">to</span> <span m="3034840">call</span> <span m="3035040">the</span>
  <span m="3035120">code</span> <span m="3035410">lots</span> <span m="3035640">of</span>
  <span m="3035710">times.</span> <span m="3037590">Every</span> <span m="3037860">time</span>
  <span m="3038150">we</span> <span m="3038230">want</span> <span m="3038360">to</span>
  <span m="3038420">evaluate</span> <span m="3039190">the</span> <span m="3039470">objective</span>
  <span m="3040050">or</span> <span m="3040140">the</span> <span m="3040200">constraints,</span>
  <span m="3040810">and</span> <span m="3040910">any</span> <span m="3041210">time</span>
  <span m="3041400">we</span> <span m="3041480">want</span> <span m="3041620">to</span>
  <span m="3041680">get</span> <span m="3041790">a</span> <span m="3041820">gradient,</span>
  <span m="3042490">we</span> <span m="3042590">may</span> <span m="3042750">have</span>
  <span m="3042860">to</span> <span m="3043300">call</span> <span m="3043560">it</span>
  <span m="3043690">n</span> <span m="3043960">times.</span> <span m="3045720">Also,</span>
  <span m="3046020">you''ve</span> <span m="3046200">seen</span> <span m="3046420">in</span>
  <span m="3046510">the</span> <span m="3046570">Monte</span> <span m="3046900">Carlo</span>
  <span m="3047230">simulation</span> <span m="3047740">that</span> <span m="3047840">you</span>
  <span m="3047920">had</span> <span m="3048060">to</span> <span m="3048120">call</span>
  <span m="3048280">the</span> <span m="3048350">code</span> <span m="3048930">22,000</span>
  <span m="3049710">times</span> <span m="3051280">when</span> <span m="3051440">you</span>
  <span m="3051500">were</span> <span m="3051590">running</span> <span m="3051860">the</span>
  <span m="3051930">simulations</span> <span m="3052610">for</span> <span m="3052730">each</span>
  <span m="3053960">ball,</span> <span m="3054790">each</span> <span m="3055040">pitch</span>
  <span m="3055270">that</span> <span m="3055390">you</span> <span m="3055470">were</span>
  <span m="3056130">analyzing.</span></p><p><span m="3057275">So</span> <span m="3057760">it</span>
  <span m="3057890">turns</span> <span m="3058150">out</span> <span m="3058350">that</span>
  <span m="3058490">when</span> <span m="3058590">you</span> <span m="3058790">have</span>
  <span m="3059220">CFD</span> <span m="3059720">models</span> <span m="3060340">or</span>
  <span m="3060720">finite</span> <span m="3060860">element</span> <span m="3061270">models</span>
  <span m="3061670">or</span> <span m="3062830">realistic</span> <span m="3063350">models</span>
  <span m="3063640">of</span> <span m="3063710">aircraft</span> <span m="3064545">or</span>
  <span m="3064820">spacecraft</span> <span m="3065390">or</span> <span m="3065440">whatever</span>
  <span m="3065710">it</span> <span m="3065780">is</span> <span m="3065890">you''re</span>
  <span m="3065990">modeling,</span> <span m="3066340">it just gets</span> <span m="3066740">too</span>
  <span m="3066880">expensive.</span> <span m="3068110">And</span> <span m="3068270">so</span>
  <span m="3068570">we</span> <span m="3068770">use</span> <span m="3069130">what</span>
  <span m="3069310">is</span> <span m="3069450">called</span> <span m="3069780">surrogate</span>
  <span m="3070290">model.</span> <span m="3070860">So</span> <span m="3071010">the</span>
  <span m="3071110">word</span> <span m="3071480">&quot;surrogate&quot;</span> <span
  m="3072100">means</span> <span m="3072440">that</span> <span m="3072560">we''re</span>
  <span m="3072680">going</span> <span m="3073030">to</span> <span m="3073210">replace</span>
  <span m="3073750">the</span> <span m="3073880">real</span> <span m="3074150">model</span>
  <span m="3075340">with</span> <span m="3076380">an</span> <span m="3077070">approximation.</span>
  <span m="3078500">And</span> <span m="3078610">the</span> <span m="3078700">idea</span>
  <span m="3079030">is</span> <span m="3079120">that</span> <span m="3079280">the</span>
  <span m="3079350">approximation</span> <span m="3080010">should</span> <span m="3080170">be</span>
  <span m="3080290">something</span> <span m="3080710">that''s</span> <span m="3080960">much</span>
  <span m="3081390">cheaper</span> <span m="3082890">than</span> <span m="3083620">the</span>
  <span m="3083740">model</span> <span m="3084000">that</span> <span m="3084110">we''re</span>
  <span m="3084200">trying</span> <span m="3084390">to</span> <span m="3084460">optimize,</span>
  <span m="3085730">but</span> <span m="3085880">hopefully</span> <span m="3086210">it''s</span>
  <span m="3086350">good</span> <span m="3086520">enough</span> <span m="3086810">so</span>
  <span m="3086930">that</span> <span m="3087040">we</span> <span m="3087150">can</span>
  <span m="3087320">make</span> <span m="3087530">good</span> <span m="3087690">design</span>
  <span m="3088070">decisions</span> <span m="3088580">and</span> <span m="3089040">find</span>
  <span m="3089320">good</span> <span m="3089460">designs,</span> <span m="3089970">and</span>
  <span m="3090060">then</span> <span m="3090190">maybe</span> <span m="3090480">go</span>
  <span m="3090590">back</span> <span m="3090800">and</span> <span m="3090900">analyze</span>
  <span m="3091260">them</span> <span m="3091380">with</span> <span m="3092470">our</span>
  <span m="3092510">more</span> <span m="3092810">sophisticated</span> <span m="3093450">model.</span></p><p><span
  m="3094680">So</span> <span m="3095080">I</span> <span m="3095160">like</span> <span
  m="3095300">to</span> <span m="3095370">think</span> <span m="3095530">of</span>
  <span m="3095640">surrogate</span> <span m="3096000">models</span> <span m="3096370">in
  these</span> <span m="3096840">three</span> <span m="3097090">different</span> <span
  m="3097460">categories.</span> <span m="3098300">There</span> <span m="3098380">are</span>
  <span m="3098460">data</span> <span m="3098730">fit</span> <span m="3098940">models</span>
  <span m="3099510">like</span> <span m="3099840">regression</span> <span m="3100360">models,</span>
  <span m="3100600">and</span> <span m="3100700">we''ll</span> <span m="3100900">talk</span>
  <span m="3101100">a</span> <span m="3101160">little</span> <span m="3101320">bit</span>
  <span m="3101450">more</span> <span m="3101590">about</span> <span m="3101810">these</span>
  <span m="3101940">ones.</span> <span m="3103870">There</span> <span m="3104010">are</span>
  <span m="3104070">simplified</span> <span m="3104670">physics</span> <span m="3105030">models,</span>
  <span m="3105600">which</span> <span m="3105840">actually</span> <span m="3106110">we</span>
  <span m="3106230">use</span> <span m="3106370">in</span> <span m="3106460">engineering</span>
  <span m="3106950">all</span> <span m="3107060">the</span> <span m="3107160">time,</span>
  <span m="3107623">that</span> <span m="3108550">maybe</span> <span m="3108820">we</span>
  <span m="3108940">want</span> <span m="3109060">to</span> <span m="3109120">design</span>
  <span m="3109610">according</span> <span m="3110030">to</span> <span m="3110840">a</span>
  <span m="3111000">Navier-Stokes</span> <span m="3111560">equation</span> <span m="3112360">of,</span>
  <span m="3113920">in</span> <span m="3114320">this</span> <span m="3114720">case,</span>
  <span m="3114890">of</span> <span m="3114950">a</span> <span m="3115010">supersonic</span>
  <span m="3115620">business</span> <span m="3116020">jet.</span> <span m="3116830">But</span>
  <span m="3117030">we</span> <span m="3117120">could</span> <span m="3117220">also</span>
  <span m="3117480">use</span> <span m="3117830">like</span> <span m="3117980">a</span>
  <span m="3118030">paddle</span> <span m="3118440">method,</span> <span m="3119090">or</span>
  <span m="3119290">even</span> <span m="3119640">just</span> <span m="3119990">a</span>
  <span m="3120030">simple</span> <span m="3121030">empirical</span> <span m="3122710">very</span>
  <span m="3122900">high-level</span> <span m="3123300">model</span> <span m="3123600">of</span>
  <span m="3123680">the</span> <span m="3123830">aircraft</span> <span m="3124260">so</span>
  <span m="3124330">we can</span> <span m="3124620">simplify</span> <span m="3125190">the</span>
  <span m="3125270">physics.</span></p><p><span m="3126180">And</span> <span m="3126290">then</span>
  <span m="3126390">there</span> <span m="3126530">are</span> <span m="3126580">things</span>
  <span m="3126930">that</span> <span m="3127040">are</span> <span m="3127100">called</span>
  <span m="3127470">projection-based</span> <span m="3128300">reduced</span> <span
  m="3128600">model,</span> <span m="3129940">which</span> <span m="3130350">is</span>
  <span m="3130760">basically</span> <span m="3131140">a</span> <span m="3131210">mathematical</span>
  <span m="3131920">way</span> <span m="3132170">of</span> <span m="3132260">coming</span>
  <span m="3132610">up</span> <span m="3133010">with</span> <span m="3134250">simpler</span>
  <span m="3134680">models.</span> <span m="3135570">This little</span> <span m="3135850">diagram</span>
  <span m="3136250">here</span> <span m="3136420">is</span> <span m="3136520">supposed</span>
  <span m="3137030">to</span> <span m="3137560">represent</span> <span m="3138260">an</span>
  <span m="3138420">x</span> <span m="3138780">dot</span> <span m="3139110">equal</span>
  <span m="3139440">x plus</span> <span m="3139820">b</span> <span m="3140060">u.</span>
  <span m="3141510">If</span> <span m="3141750">you guys</span> <span m="3141830">didn''t</span>
  <span m="3142050">see</span> <span m="3142220">state</span> <span m="3142510">space</span>
  <span m="3142810">systems</span> <span m="3143330">[INAUDIBLE]</span> <span m="3144140">anymore,</span>
  <span m="3144290">right?</span> <span m="3144600">No.</span> <span m="3146512">So</span>
  <span m="3146990">mathematical</span> <span m="3147560">ways</span> <span m="3147860">for</span>
  <span m="3148560">reducing</span> <span m="3149040">systems</span> <span m="3150810">that</span>
  <span m="3151020">I</span> <span m="3151120">won''t</span> <span m="3151740">talk</span>
  <span m="3151940">about.</span> <span m="3152160">But</span> <span m="3152310">I</span>
  <span m="3152390">do</span> <span m="3152560">lots</span> <span m="3152780">of</span>
  <span m="3152860">research</span> <span m="3153250">in</span> <span m="3153480">that</span>
  <span m="3154630">third</span> <span m="3154810">category.</span></p><p><span m="3156640">So</span>
  <span m="3157550">if</span> <span m="3157690">we</span> <span m="3157800">just</span>
  <span m="3158000">want</span> <span m="3158340">to</span> <span m="3158460">think</span>
  <span m="3158660">a</span> <span m="3158700">little</span> <span m="3158860">bit</span>
  <span m="3158980">about</span> <span m="3159400">the</span> <span m="3159500">data</span>
  <span m="3159770">fit</span> <span m="3160260">category,</span> <span m="3161480">so</span>
  <span m="3161530">the</span> <span m="3161610">idea</span> <span m="3162010">is</span>
  <span m="3162120">going</span> <span m="3162240">to</span> <span m="3162330">be</span>
  <span m="3162460">that</span> <span m="3162580">we''re</span> <span m="3162650">going</span>
  <span m="3162770">to</span> <span m="3162970">sample</span> <span m="3163640">our</span>
  <span m="3163920">simulation</span> <span m="3164420">at some</span> <span m="3164550">number</span>
  <span m="3164940">of design</span> <span m="3165190">points.</span> <span m="3165600">So
  we might</span> <span m="3165810">use</span> <span m="3165980">one</span> <span
  m="3166110">of</span> <span m="3166200">the</span> <span m="3166370">design</span>
  <span m="3166680">of</span> <span m="3166760">experiments</span> <span m="3167380">method</span>
  <span m="3167700">that</span> <span m="3167810">we</span> <span m="3167900">talked</span>
  <span m="3168170">about</span> <span m="3168440">last</span> <span m="3168750">week</span>
  <span m="3169730">to</span> <span m="3169890">somehow</span> <span m="3170230">select</span>
  <span m="3170670">some</span> <span m="3171460">points.</span> <span m="3172570">So</span>
  <span m="3172670">we''re</span> <span m="3172740">going</span> <span m="3172860">to</span>
  <span m="3172970">run</span> <span m="3173640">our</span> <span m="3173960">expensive</span>
  <span m="3174310">model</span> <span m="3174650">at a</span> <span m="3174740">bunch</span>
  <span m="3174960">of</span> <span m="3175100">points,</span> <span m="3175420">and
  then</span> <span m="3175740">we''re going to</span> <span m="3175790">fit a</span>
  <span m="3176180">model</span> <span m="3176740">using</span> <span m="3177190">that</span>
  <span m="3177420">sample</span> <span m="3177790">information.</span> <span m="3179650">We</span>
  <span m="3179840">could</span> <span m="3180150">try</span> <span m="3180340">to</span>
  <span m="3180430">fit</span> <span m="3180620">a</span> <span m="3180660">model</span>
  <span m="3181010">everywhere,</span> <span m="3182250">or</span> <span m="3182620">we</span>
  <span m="3182780">might</span> <span m="3183010">want</span> <span m="3183200">to</span>
  <span m="3183260">do</span> <span m="3183900">more</span> <span m="3184160">of</span>
  <span m="3184240">a</span> <span m="3184290">local</span> <span m="3184660">fit.</span>
  <span m="3185600">And</span> <span m="3185810">then</span> <span m="3185930">you</span>
  <span m="3186040">could</span> <span m="3186180">also</span> <span m="3186450">think</span>
  <span m="3186640">about</span> <span m="3186910">updating</span> <span m="3187310">the</span>
  <span m="3187380">model</span> <span m="3187670">when</span> <span m="3188460">you</span>
  <span m="3188520">get</span> <span m="3188670">new</span> <span m="3188830">points.</span></p><p><span
  m="3189760">But</span> <span m="3189880">I</span> <span m="3189920">want</span>
  <span m="3190050">to</span> <span m="3190130">talk</span> <span m="3191090">specifically</span>
  <span m="3192670">about</span> <span m="3194510">response</span> <span m="3195080">surface</span>
  <span m="3196970">modeling,</span> <span m="3198240">and</span> <span m="3199020">see</span>
  <span m="3199520">how</span> <span m="3203280">one</span> <span m="3203440">would</span>
  <span m="3203650">come</span> <span m="3203840">up</span> <span m="3203980">with</span>
  <span m="3204140">a</span> <span m="3205090">surrogate</span> <span m="3205520">model</span>
  <span m="3209740">using</span> <span m="3210100">a</span> <span m="3210460">response</span>
  <span m="3210925">surface.</span> <span m="3211390">Because</span> <span m="3211620">again,</span>
  <span m="3211930">that''s where</span> <span m="3212090">we''ll</span> <span m="3212340">use</span>
  <span m="3213650">some</span> <span m="3213810">of</span> <span m="3213890">the</span>
  <span m="3213980">mathematical</span> <span m="3214690">techniques</span> <span
  m="3215190">that</span> <span m="3215520">you</span> <span m="3215620">guys</span>
  <span m="3215810">should</span> <span m="3215960">have</span> <span m="3216080">seen</span>
  <span m="3216400">before.</span></p><p><span m="3219340">So</span> <span m="3219440">we</span>
  <span m="3219610">skipped</span> <span m="3219980">over</span> <span m="3221770">number</span>
  <span m="3222030">three.</span> <span m="3222450">We</span> <span m="3222540">didn''t</span>
  <span m="3222800">talk</span> <span m="3223010">about</span> <span m="3223320">the</span>
  <span m="3223390">1D</span> <span m="3223560">search.</span> <span m="3225790">And</span>
  <span m="3225970">number</span> <span m="3226160">four</span> <span m="3226460">was</span>
  <span m="3226580">really</span> <span m="3226800">just</span> <span m="3227800">a</span>
  <span m="3227890">brief</span> <span m="3228320">intro</span> <span m="3228760">to</span>
  <span m="3229420">what</span> <span m="3229600">is</span> <span m="3229720">a</span>
  <span m="3229770">surrogate</span> <span m="3230220">model,</span> <span m="3230510">and
  what are</span> <span m="3230680">the</span> <span m="3230760">different</span>
  <span m="3231080">times.</span> <span m="3231660">So we''re</span> <span m="3232050">at</span>
  <span m="3232640">number</span> <span m="3232920">five,</span> <span m="3233570">on</span>
  <span m="3233720">a</span> <span m="3233790">response</span> <span m="3234195">surface</span>
  <span m="3234600">model.</span></p><p><span m="3238576">OK,</span> <span m="3239280">so</span>
  <span m="3239700">the</span> <span m="3240120">setup</span> <span m="3240720">is</span>
  <span m="3241030">that</span> <span m="3243430">we''re</span> <span m="3243590">going</span>
  <span m="3243710">to</span> <span m="3243790">have--</span> <span m="3245775">let''s
  just</span> <span m="3246180">draw</span> <span m="3247314">the</span> <span m="3247801">[?
  block ?]</span> <span m="3248288">diagram.</span> <span m="3250730">So</span> <span
  m="3250850">this</span> <span m="3250990">is</span> <span m="3251090">our</span>
  <span m="3251480">expensive</span> <span m="3252080">model</span> <span m="3256160">where</span>
  <span m="3256430">we</span> <span m="3256580">can</span> <span m="3256780">supply</span>
  <span m="3257075">x,</span> <span m="3257940">and</span> <span m="3258090">out</span>
  <span m="3258570">comes</span> <span m="3258963">J of x.</span> <span m="3259750">Therefore</span>
  <span m="3259910">with</span> <span m="3260000">a</span> <span m="3260080">constraint</span>
  <span m="3260530">problem,</span> <span m="3260860">it</span> <span m="3261190">would</span>
  <span m="3261350">also</span> <span m="3261590">be</span> <span m="3261730">g</span>
  <span m="3262150">and h</span> <span m="3262360">coming</span> <span m="3262680">out</span>
  <span m="3262770">of</span> <span m="3262830">there.</span> <span m="3264216">So</span>
  <span m="3264680">that''s</span> <span m="3264940">our</span> <span m="3265080">expensive</span>
  <span m="3265600">model.</span> <span m="3266550">And</span> <span m="3267060">basically</span>
  <span m="3267440">what</span> <span m="3267600">we</span> <span m="3267700">want</span>
  <span m="3267840">to</span> <span m="3267910">do</span> <span m="3268150">is</span>
  <span m="3268260">come</span> <span m="3268450">up</span> <span m="3268580">with</span>
  <span m="3268710">a</span> <span m="3268870">surrogate</span> <span m="3269420">model</span>
  <span m="3271830">said</span> <span m="3272060">that</span> <span m="3272160">when</span>
  <span m="3272300">we</span> <span m="3276160">supply</span> <span m="3276630">x,</span>
  <span m="3277220">what''s</span> <span m="3277480">going</span> <span m="3277610">to</span>
  <span m="3277670">come</span> <span m="3277910">out</span> <span m="3278100">will</span>
  <span m="3278240">be</span> <span m="3278500">some</span> <span m="3278800">J</span>
  <span m="3279020">hat,</span> <span m="3280880">where</span> <span m="3281160">this</span>
  <span m="3281320">guy</span> <span m="3281710">is</span> <span m="3282390">hopefully</span>
  <span m="3282530">a</span> <span m="3282860">good</span> <span m="3283030">approximation</span>
  <span m="3283950">of</span> <span m="3285264">J.</span></p><p><span m="3288006">And</span>
  <span m="3288920">one</span> <span m="3289240">simple</span> <span m="3289850">but</span>
  <span m="3290320">pretty</span> <span m="3290540">powerful</span> <span m="3291320">and</span>
  <span m="3291540">commonly</span> <span m="3291875">used</span> <span m="3292210">way</span>
  <span m="3292360">to</span> <span m="3292430">do</span> <span m="3292600">that</span>
  <span m="3292800">is</span> <span m="3292990">with</span> <span m="3293190">what''s</span>
  <span m="3293410">called</span> <span m="3294530">a</span> <span m="3294800">response</span>
  <span m="3295450">surface</span> <span m="3295810">model.</span> <span m="3298242">So</span>
  <span m="3301230">response</span> <span m="3305220">surface</span> <span m="3305620">model,</span>
  <span m="3306080">or</span> <span m="3306310">RSM.</span> <span m="3314040">So</span>
  <span m="3314410">if</span> <span m="3315290">we</span> <span m="3315660">wanted</span>
  <span m="3315870">to</span> <span m="3315950">do</span> <span m="3317680">just</span>
  <span m="3317830">a</span> <span m="3317940">first</span> <span m="3318340">order</span>
  <span m="3318960">RSM,</span> <span m="3322560">then</span> <span m="3322800">what</span>
  <span m="3322930">we''re</span> <span m="3323040">going</span> <span m="3323330">to</span>
  <span m="3323560">say</span> <span m="3323970">is</span> <span m="3324200">that</span>
  <span m="3324780">this</span> <span m="3325010">J</span> <span m="3325430">hat,</span>
  <span m="3327560">which</span> <span m="3327660">is</span> <span m="3327730">a</span>
  <span m="3327810">function</span> <span m="3328230">of</span> <span m="3328310">x,</span>
  <span m="3330760">is</span> <span m="3330950">just</span> <span m="3331140">going</span>
  <span m="3331270">to</span> <span m="3331370">be</span> <span m="3331780">some</span>
  <span m="3332210">constant,</span> <span m="3332810">let''s</span> <span m="3333010">call</span>
  <span m="3333280">it</span> <span m="3333430">a0,</span> <span m="3335022">plus</span>
  <span m="3336420">the</span> <span m="3336890">sum</span> <span m="3337170">from</span>
  <span m="3337300">i equal</span> <span m="3337860">1</span> <span m="3338140">to</span>
  <span m="3338300">n</span> <span m="3338595">of</span> <span m="3338890">some</span>
  <span m="3339450">ai</span> <span m="3340160">times</span> <span m="3340590">xi.</span>
  <span m="3341020">In</span> <span m="3341450">other</span> <span m="3341710">words,
  it''s</span> <span m="3341880">just</span> <span m="3342100">a</span> <span m="3342160">linear</span>
  <span m="3342620">model.</span> <span m="3343720">It''s</span> <span m="3343780">a</span>
  <span m="3343820">constant</span> <span m="3344540">plus</span> <span m="3344860">a</span>
  <span m="3344910">constant</span> <span m="3345670">a1</span> <span m="3346330">times</span>
  <span m="3346630">x1,</span> <span m="3346940">plus</span> <span m="3347250">a2</span>
  <span m="3347650">times</span> <span m="3348050">x2.</span> <span m="3349430">So</span>
  <span m="3349560">it''s</span> <span m="3349890">going</span> <span m="3350010">to</span>
  <span m="3350100">replace</span> <span m="3351990">the</span> <span m="3352080">expensive</span>
  <span m="3352530">model</span> <span m="3352880">with</span> <span m="3353020">a</span>
  <span m="3353070">linear</span> <span m="3353590">approximation.</span> <span m="3354590">That</span>
  <span m="3354710">would</span> <span m="3354810">be</span> <span m="3354920">a</span>
  <span m="3354970">first</span> <span m="3355350">order</span> <span m="3355990">response</span>
  <span m="3358270">surface</span> <span m="3358540">model.</span></p><p><span m="3360630">Turns</span>
  <span m="3360870">out</span> <span m="3361120">this</span> <span m="3361280">is</span>
  <span m="3361370">not</span> <span m="3363460">such</span> <span m="3363790">a</span>
  <span m="3364130">good</span> <span m="3364300">idea,</span> <span m="3364620">and</span>
  <span m="3364990">we''ll</span> <span m="3365140">look</span> <span m="3365330">at</span>
  <span m="3365420">it</span> <span m="3365490">graphically</span> <span m="3365940">in</span>
  <span m="3366000">a</span> <span m="3366070">second</span> <span m="3366410">and</span>
  <span m="3366520">you''ll</span> <span m="3366710">see</span> <span m="3366990">why.</span>
  <span m="3368322">So</span> <span m="3368720">more</span> <span m="3368900">often</span>
  <span m="3369120">than</span> <span m="3369240">not,</span> <span m="3369630">people</span>
  <span m="3369890">used</span> <span m="3370950">a</span> <span m="3371020">second</span>
  <span m="3371430">order</span> <span m="3371970">or</span> <span m="3372160">a</span>
  <span m="3372210">quadratic</span> <span m="3378944">response</span> <span m="3379422">surface.</span>
  <span m="3380860">And</span> <span m="3382662">it''s</span> <span m="3383100">the</span>
  <span m="3383210">same</span> <span m="3383470">idea</span> <span m="3383810">that</span>
  <span m="3385820">the</span> <span m="3385930">approximate</span> <span m="3386580">model</span>
  <span m="3387150">they</span> <span m="3387410">had</span> <span m="3387790">is</span>
  <span m="3388080">going</span> <span m="3388250">to</span> <span m="3388340">be,</span>
  <span m="3390520">again,</span> <span m="3390810">a</span> <span m="3390860">constant,</span>
  <span m="3391770">and then</span> <span m="3392070">it''s</span> <span m="3392200">going</span>
  <span m="3392340">to</span> <span m="3392410">be</span> <span m="3393300">the</span>
  <span m="3393490">linear</span> <span m="3393910">term,</span> <span m="3394880">so</span>
  <span m="3395270">the</span> <span m="3395480">sum</span> <span m="3395700">from</span>
  <span m="3395780">i equal</span> <span m="3396180">1 to</span> <span m="3396510">n</span>
  <span m="3396982">of</span> <span m="3397454">ai</span> <span m="3398400">xi''s,</span>
  <span m="3399210">and then</span> <span m="3399360">it''s</span> <span m="3399580">going</span>
  <span m="3399700">to</span> <span m="3399760">be</span> <span m="3399870">all</span>
  <span m="3399900">the</span> <span m="3401280">quadratic</span> <span m="3401750">terms,</span>
  <span m="3401910">so</span> <span m="3402340">i</span> <span m="3402770">equals</span>
  <span m="3403110">1</span> <span m="3403390">to</span> <span m="3403880">n,</span>
  <span m="3404180">j</span> <span m="3404646">equals</span> <span m="3405580">1</span>
  <span m="3405890">to</span> <span m="3406000">n</span> <span m="3406800">of</span>
  <span m="3407600">b</span> <span m="3408130">i</span> <span m="3409078">J</span>
  <span m="3410026">x</span> <span m="3411922">i</span> <span m="3412870">x</span>
  <span m="3413344">J.</span> <span m="3413818">And actually</span> <span m="3414292">maybe
  this should be</span> <span m="3414770">J equal</span> <span m="3415270">i</span>
  <span m="3415770">to</span> <span m="3416270">n.</span></p><p><span m="3424600">So
  again,</span> <span m="3425090">we''re</span> <span m="3425190">just</span> <span
  m="3425330">replacing</span> <span m="3426020">our</span> <span m="3426340">J</span>
  <span m="3426660">of x</span> <span m="3426980">with</span> <span m="3427180">a</span>
  <span m="3427210">model,</span> <span m="3427930">and</span> <span m="3428110">in</span>
  <span m="3428190">this</span> <span m="3428370">case,</span> <span m="3428690">second</span>
  <span m="3428930">order</span> <span m="3429120">case,</span> <span m="3429450">we''re</span>
  <span m="3429530">saying</span> <span m="3429730">the</span> <span m="3429790">model</span>
  <span m="3430130">is</span> <span m="3430595">quadratic.</span> <span m="3431060">It</span>
  <span m="3431150">can</span> <span m="3431260">have</span> <span m="3431410">a constant</span>
  <span m="3431763">term,</span> <span m="3432470">it</span> <span m="3432550">can</span>
  <span m="3432670">linear</span> <span m="3432830">terms,</span> <span m="3433350">and</span>
  <span m="3433610">then</span> <span m="3433710">it</span> <span m="3433790">can</span>
  <span m="3433930">have</span> <span m="3434280">all</span> <span m="3434520">these</span>
  <span m="3434850">quadratic</span> <span m="3435130">terms</span> <span m="3436730">in</span>
  <span m="3436910">the</span> <span m="3437050">xi,</span> <span m="3437620">xj,</span>
  <span m="3438770">xi</span> <span m="3438960">squared,</span> <span m="3439860">x1</span>
  <span m="3440040">squared,</span> <span m="3440590">x1,</span> <span m="3440970">x2.</span></p><p><span
  m="3441752">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3444212">KAREN WILLCOX:
  Well,</span> <span m="3444710">because</span> <span m="3445280">we</span> <span
  m="3445380">don''t</span> <span m="3445500">need</span> <span m="3445680">1,</span>
  <span m="3445940">2</span> <span m="3446313">and</span> <span m="3446686">2,</span>
  <span m="3447060">1.</span> <span m="3449230">Yeah.</span> <span m="3450670">I</span>
  <span m="3450750">mean,</span> <span m="3450950">you</span> <span m="3451110">can</span>
  <span m="3451320">write</span> <span m="3451450">1 there</span> <span m="3451870">if</span>
  <span m="3451970">you</span> <span m="3452070">wanted</span> <span m="3452290">to,</span>
  <span m="3453330">but</span> <span m="3453630">because</span> <span m="3454230">x1,</span>
  <span m="3454600">x2</span> <span m="3454930">is the</span> <span m="3455020">same</span>
  <span m="3455160">as</span> <span m="3455420">x2,</span> <span m="3455530">x1,</span>
  <span m="3455690">we</span> <span m="3455910">would</span> <span m="3456060">just
  lump</span> <span m="3456516">them.</span> <span m="3456972">[INAUDIBLE]</span></p><p><span
  m="3459530">OK,</span> <span m="3459850">so</span> <span m="3462990">here</span>
  <span m="3463250">we''ve</span> <span m="3463410">got</span> <span m="3464390">that</span>
  <span m="3464630">the</span> <span m="3465116">ai''s</span> <span m="3467060">are</span>
  <span m="3467546">unknown</span> <span m="3469010">coefficients.</span> <span m="3474050">And</span>
  <span m="3474220">here</span> <span m="3474570">we</span> <span m="3474730">have</span>
  <span m="3475170">the</span> <span m="3475300">ai''s</span> <span m="3476940">and</span>
  <span m="3477230">the</span> <span m="3477450">bij''s</span> <span m="3478165">are</span>
  <span m="3478420">unknown</span> <span m="3480070">coefficients.</span> <span m="3483250">So</span>
  <span m="3483320">we''ve</span> <span m="3483470">said</span> <span m="3483620">that</span>
  <span m="3483750">we</span> <span m="3484330">want</span> <span m="3484640">to</span>
  <span m="3484730">approximate</span> <span m="3486570">our</span> <span m="3486660">model</span>
  <span m="3487420">with</span> <span m="3487570">a</span> <span m="3487610">linear
  or a</span> <span m="3488070">quadratic</span> <span m="3488560">function.</span>
  <span m="3489630">Now</span> <span m="3489750">the</span> <span m="3489820">question</span>
  <span m="3490090">is</span> <span m="3490220">how</span> <span m="3490350">do</span>
  <span m="3490430">we</span> <span m="3490520">come</span> <span m="3490640">up</span>
  <span m="3490840">with</span> <span m="3491080">coefficients</span> <span m="3491395">for</span>
  <span m="3491710">that</span> <span m="3491880">approximation.</span> <span m="3493160">And</span>
  <span m="3493280">that''s</span> <span m="3493540">where</span> <span m="3494170">this</span>
  <span m="3494480">sampling</span> <span m="3496060">comes</span> <span m="3496350">into</span>
  <span m="3496600">play.</span></p><p><span m="3504770">What</span> <span m="3504920">we''re</span>
  <span m="3505010">going</span> <span m="3505130">to</span> <span m="3505210">do</span>
  <span m="3505340">is</span> <span m="3505980">we''re</span> <span m="3506100">going
  to</span> <span m="3506310">generate</span> <span m="3506730">samples</span> <span
  m="3507360">using</span> <span m="3508100">our</span> <span m="3508150">favorite</span>
  <span m="3508490">design</span> <span m="3508740">of</span> <span m="3508820">experiments</span>
  <span m="3509440">method,</span> <span m="3509740">or</span> <span m="3509820">maybe</span>
  <span m="3510110">we''re</span> <span m="3510250">just</span> <span m="3510350">going</span>
  <span m="3510450">to</span> <span m="3510520">run</span> <span m="3510680">Monte</span>
  <span m="3510870">Carlo</span> <span m="3511175">and</span> <span m="3511480">sample</span>
  <span m="3511770">randomly.</span> <span m="3513540">We''re going to</span> <span
  m="3513830">generate</span> <span m="3514060">a</span> <span m="3514100">bunch</span>
  <span m="3514300">of</span> <span m="3514360">samples,</span> <span m="3515110">and</span>
  <span m="3515280">then</span> <span m="3515420">we''re</span> <span m="3515520">going</span>
  <span m="3515870">to</span> <span m="3515980">use</span> <span m="3516310">least</span>
  <span m="3516530">squares</span> <span m="3517030">fitting</span> <span m="3517840">to</span>
  <span m="3517950">try</span> <span m="3518060">to</span> <span m="3518120">estimate</span>
  <span m="3518540">those</span> <span m="3518850">coefficients</span> <span m="3519550">and</span>
  <span m="3519650">come</span> <span m="3519830">up</span> <span m="3519970">with</span>
  <span m="3520365">the</span> <span m="3520930">response</span> <span m="3521370">surface</span>
  <span m="3521520">model.</span></p><p><span m="3524630">The</span> <span m="3524720">next</span>
  <span m="3524950">step</span> <span m="3525540">is</span> <span m="3525900">going</span>
  <span m="3526030">to</span> <span m="3526100">be</span> <span m="3527010">how</span>
  <span m="3527990">to</span> <span m="3530016">determine</span> <span m="3533690">the</span>
  <span m="3533990">ai</span> <span m="3534860">and</span> <span m="3535140">the</span>
  <span m="3535310">bij</span> <span m="3537950">coefficients.</span> <span m="3544330">So</span>
  <span m="3544530">let''s</span> <span m="3544900">say</span> <span m="3545250">that</span>
  <span m="3545500">we</span> <span m="3545680">have</span> <span m="3548160">generated</span>
  <span m="3551210">n</span> <span m="3551770">samples,</span> <span m="3555070">and</span>
  <span m="3555350">each</span> <span m="3555540">sample</span> <span m="3556140">is</span>
  <span m="3556270">going</span> <span m="3556560">to</span> <span m="3556650">have--</span>
  <span m="3562218">we''ll</span> <span m="3562690">call</span> <span m="3563000">it</span>
  <span m="3563470">j--</span> <span m="3564410">there''s</span> <span m="3564580">going</span>
  <span m="3564710">to</span> <span m="3564780">be</span> <span m="3564900">a</span>
  <span m="3564970">pair</span> <span m="3567250">consisting</span> <span m="3567530">of</span>
  <span m="3569220">the</span> <span m="3569310">design</span> <span m="3569780">variables</span>
  <span m="3570590">that</span> <span m="3570730">we</span> <span m="3570830">sampled,</span>
  <span m="3571500">the</span> <span m="3571560">value</span> <span m="3571860">of</span>
  <span m="3572185">x</span> <span m="3572510">that</span> <span m="3572680">we</span>
  <span m="3572800">sampled,</span> <span m="3573230">and that''s</span> <span m="3573480">again</span>
  <span m="3573760">the n</span> <span m="3574030">by</span> <span m="3574160">1</span>
  <span m="3574340">vector,</span> <span m="3574890">and</span> <span m="3575010">then</span>
  <span m="3575100">the</span> <span m="3575170">corresponding</span> <span m="3577240">value</span>
  <span m="3577500">of</span> <span m="3577650">the</span> <span m="3577950">objective.</span>
  <span m="3579220">So</span> <span m="3579470">we''ll</span> <span m="3579550">have</span>
  <span m="3579730">x1,</span> <span m="3580340">j1,</span> <span m="3580625">we''ll</span>
  <span m="3580910">have</span> <span m="3581326">x2,</span> <span m="3582160">j2,</span>
  <span m="3584590">all</span> <span m="3584720">the</span> <span m="3584790">way</span>
  <span m="3585030">up</span> <span m="3585290">to</span> <span m="3586094">xn,</span>
  <span m="3587840">jn.</span> <span m="3589570">So</span> <span m="3589780">I</span>
  <span m="3589890">ran</span> <span m="3590950">my</span> <span m="3591420">expensive</span>
  <span m="3591940">model</span> <span m="3592370">n</span> <span m="3592690">times.</span>
  <span m="3593210">So</span> <span m="3593520">I</span> <span m="3593640">just</span>
  <span m="3593810">collected</span> <span m="3594170">all</span> <span m="3594270">the</span>
  <span m="3594350">data.</span> <span m="3595000">I</span> <span m="3595390">collected</span>
  <span m="3595680">all</span> <span m="3595760">the</span> <span m="3595840">conditions</span>
  <span m="3596290">that</span> <span m="3596410">I</span> <span m="3596490">ran</span>
  <span m="3596730">it</span> <span m="3596810">at,</span> <span m="3597120">and</span>
  <span m="3597270">I</span> <span m="3597320">collected</span> <span m="3597650">all</span>
  <span m="3597760">the</span> <span m="3597870">results</span> <span m="3598260">that</span>
  <span m="3598350">I</span> <span m="3598390">got</span> <span m="3598560">out</span>
  <span m="3598690">of</span> <span m="3598770">it.</span> <span m="3599255">Is</span>
  <span m="3599740">that</span> <span m="3599950">clear?</span> <span m="3600750">Yeah?</span></p><p><span
  m="3609570">Let''s</span> <span m="3609800">think</span> <span m="3610030">about</span>
  <span m="3613240">this</span> <span m="3613350">guy</span> <span m="3613650">here,</span>
  <span m="3613940">so</span> <span m="3614245">just</span> <span m="3614550">a</span>
  <span m="3614660">first</span> <span m="3614990">order</span> <span m="3619500">[INAUDIBLE]</span>
  <span m="3619690">J</span> <span m="3620172">of x</span> <span m="3621620">equal</span>
  <span m="3622030">a0</span> <span m="3623990">plus the</span> <span m="3624400">sum</span>
  <span m="3625200">from</span> <span m="3625576">i</span> <span m="3625952">equal</span>
  <span m="3626330">1</span> <span m="3626945">to</span> <span m="3627220">n</span>
  <span m="3627515">of</span> <span m="3627810">ai</span> <span m="3628280">xi.</span>
  <span m="3631100">How</span> <span m="3631220">many</span> <span m="3631570">pieces
  of</span> <span m="3632020">data</span> <span m="3632280">do</span> <span m="3632390">we</span>
  <span m="3632480">need</span> <span m="3632730">at a</span> <span m="3632790">minimum?</span>
  <span m="3642020">How</span> <span m="3642110">many</span> <span m="3642290">unknown</span>
  <span m="3642650">coefficients</span> <span m="3642990">are</span> <span m="3643330">there</span>
  <span m="3643660">in the</span> <span m="3643990">model?</span> <span m="3645640">n</span>
  <span m="3645840">plus</span> <span m="3646070">1.</span> <span m="3646260">Little</span>
  <span m="3646500">n</span> <span m="3646670">plus</span> <span m="3646930">1.</span>
  <span m="3647210">So</span> <span m="3647350">we</span> <span m="3647440">need</span>
  <span m="3647810">big N</span> <span m="3648230">to</span> <span m="3648320">be</span>
  <span m="3648460">at</span> <span m="3648540">least</span> <span m="3648770">little</span>
  <span m="3648950">n plus</span> <span m="3649370">1.</span> <span m="3650310">But</span>
  <span m="3650440">in</span> <span m="3650520">m</span> <span m="3650820">what</span>
  <span m="3650930">we</span> <span m="3651070">would</span> <span m="3651220">do</span>
  <span m="3651370">is</span> <span m="3651490">we</span> <span m="3651590">would</span>
  <span m="3651730">generate</span> <span m="3652070">more</span> <span m="3652510">than</span>
  <span m="3653860">little</span> <span m="3653890">n</span> <span m="3654210">plus</span>
  <span m="3654450">1,</span> <span m="3655140">and</span> <span m="3655230">then
  we</span> <span m="3655310">would</span> <span m="3655470">do</span> <span m="3655660">a</span>
  <span m="3656380">regression.</span> <span m="3656660">We would</span> <span m="3656940">do
  a</span> <span m="3657230">least</span> <span m="3657520">squares</span> <span m="3657840">fit.</span>
  <span m="3658890">You</span> <span m="3658990">guys</span> <span m="3659440">did
  least</span> <span m="3659730">squares</span> <span m="3660080">fir</span> <span
  m="3660250">somewhere,</span> <span m="3660575">yes?</span> <span m="3662140">1806?</span>
  <span m="3662550">Did you do it</span> <span m="3662960">anywhere else?</span> <span
  m="3663678">[INAUDIBLE]</span></p><p><span m="3664594">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="3665970">KAREN WILLCOX: High</span> <span m="3666190">school.</span> <span m="3667100">Did</span>
  <span m="3667200">everybody</span> <span m="3667690">here</span> <span m="3668130">remember</span>
  <span m="3668490">their</span> <span m="3668660">high</span> <span m="3668780">school</span>
  <span m="3669130">regression?</span> <span m="3669450">No?</span></p><p><span m="3670242">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="3673550">KAREN WILLCOX: You can</span> <span m="3673680">do</span>
  <span m="3673750">them on</span> <span m="3673960">your</span> <span m="3674430">calculator?</span>
  <span m="3675540">MATLAB</span> <span m="3675860">backslash,</span> <span m="3676800">like</span>
  <span m="3677480">the</span> <span m="3677710">most</span> <span m="3678140">amazing</span>
  <span m="3678650">operator?</span> <span m="3680660">OK.</span> <span m="3680890">So,</span>
  <span m="3681230">well,</span> <span m="3681480">let''s</span> <span m="3681890">think</span>
  <span m="3682070">about</span> <span m="3682310">what</span> <span m="3682510">it</span>
  <span m="3682620">would</span> <span m="3682810">look</span> <span m="3683070">like.</span>
  <span m="3683360">So</span> <span m="3686025">I always</span> <span m="3686510">like
  to</span> <span m="3686880">think</span> <span m="3687150">of the</span> <span m="3687190">least
  squares</span> <span m="3687530">fitting</span> <span m="3687720">from</span> <span
  m="3687980">just</span> <span m="3688700">the</span> <span m="3688800">matrix</span>
  <span m="3689560">system.</span> <span m="3690070">Let</span> <span m="3690200">me</span>
  <span m="3690310">draw</span> <span m="3690690">it</span> <span m="3691070">over</span>
  <span m="3691230">here</span> <span m="3691470">so there''s</span> <span m="3691730">plenty
  of</span> <span m="3692228">room.</span></p><p><span m="3699210">This</span> <span
  m="3699360">is</span> <span m="3699590">a</span> <span m="3699700">matrix</span>
  <span m="3699920">system,</span> <span m="3700215">and</span> <span m="3700510">if</span>
  <span m="3700730">we</span> <span m="3700920">have</span> <span m="3701430">exactly</span>
  <span m="3701970">the</span> <span m="3702050">right</span> <span m="3702170">number</span>
  <span m="3702350">of</span> <span m="3702420">data</span> <span m="3702680">points,</span>
  <span m="3703090">the</span> <span m="3703160">matrix</span> <span m="3703530">will</span>
  <span m="3703620">be</span> <span m="3703750">square.</span> <span m="3704750">And</span>
  <span m="3704880">if</span> <span m="3704980">we</span> <span m="3705120">have</span>
  <span m="3705410">more</span> <span m="3705720">data</span> <span m="3705960">points</span>
  <span m="3706350">than</span> <span m="3706490">unknowns,</span> <span m="3707060">the</span>
  <span m="3707120">matrix</span> <span m="3707360">will</span> <span m="3707470">have</span>
  <span m="3707850">more</span> <span m="3708565">rows</span> <span m="3708960">than</span>
  <span m="3709150">columns,</span> <span m="3710510">and</span> <span m="3710790">it
  will</span> <span m="3711160">be an</span> <span m="3711530">overdetermined</span>
  <span m="3712240">system,</span> <span m="3712630">and</span> <span m="3712760">you
  would</span> <span m="3712910">do</span> <span m="3713120">a</span> <span m="3713410">least</span>
  <span m="3713580">square</span> <span m="3713790">solution.</span></p><p><span m="3715528">So</span>
  <span m="3716950">we''ll</span> <span m="3718180">set</span> <span m="3718360">up</span>
  <span m="3718490">a</span> <span m="3718560">matrix</span> <span m="3718960">system.</span>
  <span m="3725120">First</span> <span m="3725220">of</span> <span m="3725290">all,</span>
  <span m="3725490">the</span> <span m="3725520">unknowns,</span> <span m="3726150">so</span>
  <span m="3726240">the</span> <span m="3726310">things</span> <span m="3726540">we''re</span>
  <span m="3727030">solving</span> <span m="3727520">for</span> <span m="3727880">are</span>
  <span m="3728300">these</span> <span m="3729050">[INAUDIBLE]</span> <span m="3730770">a0,</span>
  <span m="3731245">a1,</span> <span m="3732723">a2,</span> <span m="3733709">down</span>
  <span m="3734202">to</span> <span m="3734695">a</span> <span m="3735190">n,</span>
  <span m="3736140">little</span> <span m="3736330">n.</span> <span m="3744550">Those</span>
  <span m="3744780">are the</span> <span m="3744880">unknowns.</span> <span m="3745910">And</span>
  <span m="3746020">then</span> <span m="3746160">each</span> <span m="3746500">row</span>
  <span m="3746820">in</span> <span m="3746890">the</span> <span m="3746960">matrix</span>
  <span m="3747420">system,</span> <span m="3748550">this</span> <span m="3748690">is</span>
  <span m="3748780">going</span> <span m="3748900">to</span> <span m="3748970">correspond</span>
  <span m="3749540">one</span> <span m="3749940">of</span> <span m="3750050">the</span>
  <span m="3750200">sample</span> <span m="3750620">points.</span></p><p><span m="3751880">So</span>
  <span m="3752190">the</span> <span m="3752260">first</span> <span m="3752590">sample</span>
  <span m="3753310">point</span> <span m="3754160">says</span> <span m="3755370">that</span>
  <span m="3755810">x--</span> <span m="3757180">when</span> <span m="3757330">I</span>
  <span m="3757400">feed</span> <span m="3757690">it</span> <span m="3757780">in</span>
  <span m="3758260">x</span> <span m="3758880">superscript</span> <span m="3759170">one</span>
  <span m="3759660">into</span> <span m="3759800">the</span> <span m="3759890">model,</span>
  <span m="3760870">I</span> <span m="3760980">get</span> <span m="3761150">out</span>
  <span m="3761380">J1.</span> <span m="3763050">So</span> <span m="3764990">here''s</span>
  <span m="3765210">J1,</span> <span m="3765625">and</span> <span m="3766380">here''s</span>
  <span m="3767060">the</span> <span m="3767220">expansion.</span> <span m="3767770">And</span>
  <span m="3767930">when</span> <span m="3768210">I feed</span> <span m="3768640">in</span>
  <span m="3769825">x1,</span> <span m="3770730">so</span> <span m="3770800">the</span>
  <span m="3770870">first</span> <span m="3771060">thing</span> <span m="3771210">I</span>
  <span m="3771260">do</span> <span m="3771440">is</span> <span m="3771560">I get</span>
  <span m="3771840">1</span> <span m="3772200">times</span> <span m="3772490">a0</span>
  <span m="3774230">plus</span> <span m="3778980">a1</span> <span m="3780310">times</span>
  <span m="3782070">x1</span> <span m="3783180">in</span> <span m="3783330">the</span>
  <span m="3784070">first</span> <span m="3784320">sample</span> <span m="3784600">point.</span>
  <span m="3785740">So</span> <span m="3785930">this</span> <span m="3786090">guy</span>
  <span m="3786200">here</span> <span m="3786460">is</span> <span m="3786570">going</span>
  <span m="3786690">to</span> <span m="3786760">be</span> <span m="3787170">x1,1</span>
  <span m="3789020">where the</span> <span m="3789300">superscript</span> <span m="3790480">is</span>
  <span m="3790680">the</span> <span m="3790740">sample</span> <span m="3791110">number,</span>
  <span m="3791450">and the</span> <span m="3791610">subscript</span> <span m="3792070">is</span>
  <span m="3792180">the</span> <span m="3792260">design</span> <span m="3792540">variable</span>
  <span m="3792820">number.</span> <span m="3793190">Yup.</span> <span m="3794918">And
  that''s</span> <span m="3795350">x2,1,</span> <span m="3799671">xn,1.</span> <span
  m="3802233">Is</span> <span m="3802656">everybody</span> <span m="3803460">with</span>
  <span m="3803650">me?</span> <span m="3803730">I</span> <span m="3803810">just</span>
  <span m="3804010">wrote</span> <span m="3804230">down the</span> <span m="3804690">equation</span>
  <span m="3807650">1</span> <span m="3807920">times</span> <span m="3808140">a0</span>
  <span m="3808390">plus</span> <span m="3809740">the</span> <span m="3809830">first</span>
  <span m="3810100">component</span> <span m="3810530">of</span> <span m="3810630">sample</span>
  <span m="3811080">1</span> <span m="3811770">times</span> <span m="3812080">a1</span>
  <span m="3812300">plus</span> <span m="3812860">the</span> <span m="3813190">second</span>
  <span m="3813550">component</span> <span m="3813970">of</span> <span m="3814040">sample</span>
  <span m="3814390">1</span> <span m="3814860">times</span> <span m="3815080">a2,</span>
  <span m="3815230">plus,</span> <span m="3815690">plus,</span> <span m="3815830">plus</span>
  <span m="3816990">the</span> <span m="3817100">nth</span> <span m="3817430">component
  of</span> <span m="3817880">sample</span> <span m="3818140">a1</span> <span m="3818320">times</span>
  <span m="3818570">a n</span> <span m="3819410">equals</span> <span m="3820258">to</span>
  <span m="3821094">J1.</span></p><p><span m="3824950">[INAUDIBLE]</span> <span m="3825070">exactly</span>
  <span m="3825460">does</span> <span m="3825660">this</span> <span m="3826080">equation</span>
  <span m="3826640">apply</span> <span m="3826880">to</span> <span m="3827010">the</span>
  <span m="3827080">first</span> <span m="3827360">[? here ?],</span> <span m="3827520">and</span>
  <span m="3827630">I</span> <span m="3827680">could</span> <span m="3827860">write</span>
  <span m="3828100">down</span> <span m="3828410">so that</span> <span m="3828520">this</span>
  <span m="3828960">is</span> <span m="3829070">the</span> <span m="3829160">first</span>
  <span m="3829490">sample,</span> <span m="3832330">which</span> <span m="3832550">we</span>
  <span m="3832660">called</span> <span m="3833510">x</span> <span m="3834830">superscript</span>
  <span m="3835270">1.</span> <span m="3835710">So then</span> <span m="3836000">I</span>
  <span m="3836100">would</span> <span m="3836170">do</span> <span m="3836360">the</span>
  <span m="3836450">second</span> <span m="3836775">sample,</span> <span m="3837310">and</span>
  <span m="3837520">it</span> <span m="3837620">would</span> <span m="3837730">just</span>
  <span m="3837890">look</span> <span m="3838030">like</span> <span m="3838220">this.</span>
  <span m="3842684">x2,1,</span> <span m="3844100">x2,2,</span> <span m="3845486">xn,2,</span>
  <span m="3848630">and</span> <span m="3848780">that''s</span> <span m="3849040">going</span>
  <span m="3849320">to</span> <span m="3849400">be</span> <span m="3849830">equal</span>
  <span m="3850010">to</span> <span m="3850120">J2.</span> <span m="3851470">And</span>
  <span m="3851580">then</span> <span m="3851680">I</span> <span m="3851730">would</span>
  <span m="3851860">keep</span> <span m="3852030">going.</span></p><p><span m="3852560">So</span>
  <span m="3852570">I''m</span> <span m="3852670">always</span> <span m="3852860">going</span>
  <span m="3852980">to</span> <span m="3853050">have</span> <span m="3853670">1''s</span>
  <span m="3855230">in</span> <span m="3855390">this</span> <span m="3855580">column,</span>
  <span m="3857040">because</span> <span m="3857270">that</span> <span m="3857500">1</span>
  <span m="3857810">is</span> <span m="3857990">always</span> <span m="3858250">going</span>
  <span m="3858310">to</span> <span m="3858350">multiply</span> <span m="3858740">a0.</span>
  <span m="3860450">Down</span> <span m="3860680">here</span> <span m="3860860">eventually</span>
  <span m="3861200">I''m</span> <span m="3861270">going</span> <span m="3861390">to</span>
  <span m="3861450">have</span> <span m="3861780">x,</span> <span m="3862772">first</span>
  <span m="3863130">component</span> <span m="3863620">of</span> <span m="3863760">the</span>
  <span m="3863910">nth</span> <span m="3864245">sample,</span> <span m="3865200">and</span>
  <span m="3865340">here</span> <span m="3865560">I''ll</span> <span m="3865600">have</span>
  <span m="3865940">x,</span> <span m="3866450">nth</span> <span m="3866860">component</span>
  <span m="3867470">of</span> <span m="3867650">the</span> <span m="3867730">big Nth</span>
  <span m="3868210">sample,</span> <span m="3868970">and</span> <span m="3869100">everything</span>
  <span m="3869380">in</span> <span m="3869480">between.</span> <span m="3871860">Yup.</span>
  <span m="3873690">So</span> <span m="3873810">this</span> <span m="3873990">is a</span>
  <span m="3874472">big</span> <span m="3874954">N</span> <span m="3875436">by</span>
  <span m="3877096">little</span> <span m="3877472">n</span> <span m="3877850">plus</span>
  <span m="3878090">1</span> <span m="3878680">matrix.</span> <span m="3880860">This</span>
  <span m="3881050">is</span> <span m="3881210">a</span> <span m="3881580">little</span>
  <span m="3881760">n plus</span> <span m="3882050">1</span> <span m="3882510">vector,</span>
  <span m="3882950">and</span> <span m="3883060">this</span> <span m="3883200">is</span>
  <span m="3883680">a</span> <span m="3884640">big</span> <span m="3889358">N</span>
  <span m="3890834">vector.</span> <span m="3893310">Yeah.</span></p><p><span m="3894670">And</span>
  <span m="3894790">if</span> <span m="3894870">we</span> <span m="3894960">have</span>
  <span m="3895120">exactly</span> <span m="3895890">little</span> <span m="3896100">n
  plus</span> <span m="3896490">1</span> <span m="3896760">samples,</span> <span m="3897140">again,</span>
  <span m="3897400">this</span> <span m="3897640">matrix</span> <span m="3898010">would</span>
  <span m="3898120">be</span> <span m="3898230">square,</span> <span m="3898640">and</span>
  <span m="3898730">we</span> <span m="3898830">would</span> <span m="3898980">just</span>
  <span m="3899170">invert</span> <span m="3899430">it,</span> <span m="3899760">and</span>
  <span m="3899910">it</span> <span m="3899980">would</span> <span m="3900080">give</span>
  <span m="3900180">us</span> <span m="3900260">the</span> <span m="3900350">coefficients.</span>
  <span m="3901830">If</span> <span m="3902250">we</span> <span m="3902340">have</span>
  <span m="3902480">more</span> <span m="3902730">samples</span> <span m="3903210">than</span>
  <span m="3903320">we</span> <span m="3903400">have</span> <span m="3903560">unknowns,</span>
  <span m="3905040">then</span> <span m="3905460">again</span> <span m="3905740">it''s</span>
  <span m="3906070">just a</span> <span m="3906150">least</span> <span m="3906360">squares</span>
  <span m="3906870">solution,</span> <span m="3907910">which</span> <span m="3908140">you</span>
  <span m="3908280">can</span> <span m="3908420">do</span> <span m="3908600">with</span>
  <span m="3908760">matrix</span> <span m="3908930">with</span> <span m="3909307">MATLAB''s</span>
  <span m="3909684">backslash,</span> <span m="3910440">or</span> <span m="3910650">you</span>
  <span m="3910830">can</span> <span m="3911060">remember</span> <span m="3912560">the</span>
  <span m="3912640">formula</span> <span m="3914990">involving</span> <span m="3915100">ax</span>
  <span m="3915500">equals</span> <span m="3915860">b,</span> <span m="3916370">and</span>
  <span m="3916645">it''s</span> <span m="3916920">overdetermined,</span> <span m="3917920">then</span>
  <span m="3918180">you</span> <span m="3918300">do</span> <span m="3918570">a</span>
  <span m="3919000">transposed</span> <span m="3920230">ax</span> <span m="3921520">equals</span>
  <span m="3921810">a</span> <span m="3921930">transposed</span> <span m="3922330">b,</span>
  <span m="3922895">and</span> <span m="3923210">then</span> <span m="3923600">take</span>
  <span m="3924020">the</span> <span m="3924440">inverse of</span> <span m="3924510">this,</span>
  <span m="3924630">and take it</span> <span m="3925100">to</span> <span m="3925230">the</span>
  <span m="3925970">lefthand</span> <span m="3926330">side.</span> <span m="3929390">[INAUDIBLE]</span></p><p><span
  m="3931710">OK,</span> <span m="3932040">and if</span> <span m="3932150">we''re</span>
  <span m="3932260">doing</span> <span m="3932360">a</span> <span m="3932480">quadratic</span>
  <span m="3933700">response</span> <span m="3933965">surface,</span> <span m="3934687">so</span>
  <span m="3935601">if I</span> <span m="3936058">was</span> <span m="3936515">setting</span>
  <span m="3936972">J hat</span> <span m="3937429">of x</span> <span m="3937886">is
  this</span> <span m="3938343">plus this</span> <span m="3938800">plus</span> <span
  m="3939260">the</span> <span m="3939420">term,</span> <span m="3940680">the</span>
  <span m="3940820">b</span> <span m="3941130">ij</span> <span m="3942252">xi</span>
  <span m="3943650">xj,</span> <span m="3945760">how would</span> <span m="3945980">the</span>
  <span m="3946100">system</span> <span m="3946490">change?</span> <span m="3948410">What
  would</span> <span m="3948650">I</span> <span m="3948700">have</span> <span m="3948840">to</span>
  <span m="3948950">do?</span> <span m="3955360">Would</span> <span m="3955520">there
  be</span> <span m="3955730">more</span> <span m="3955980">unknowns?</span> <span
  m="3958011">Yeah,</span> <span m="3958500">so</span> <span m="3959010">there</span>
  <span m="3959130">would</span> <span m="3959260">be</span> <span m="3959360">the</span>
  <span m="3959740">b1,1,</span> <span m="3960982">b1,2,</span> <span m="3962000">b1,3,</span>
  <span m="3963340">all the</span> <span m="3963410">b''s.</span> <span m="3964780">So</span>
  <span m="3964960">more</span> <span m="3965150">unknown</span> <span m="3965730">means</span>
  <span m="3966060">more</span> <span m="3967840">columns</span> <span m="3968300">in</span>
  <span m="3968360">the</span> <span m="3968420">matrix.</span> <span m="3969630">So</span>
  <span m="3969760">what</span> <span m="3970120">would</span> <span m="3970330">be--</span>
  <span m="3970680">if I</span> <span m="3971000">put b1,1</span> <span m="3971600">here,</span>
  <span m="3971900">what</span> <span m="3972370">entry</span> <span m="3972690">would</span>
  <span m="3972850">go</span> <span m="3973030">in</span> <span m="3973920">here?</span></p><p><span
  m="3977118">AUDIENCE: [INAUDIBLE]</span></p><p><span m="3978540">KAREN WILLCOX:
  X1,1</span> <span m="3980420">squared,</span> <span m="3981980">because</span> <span
  m="3982200">in</span> <span m="3982390">the</span> <span m="3983650">expansion,</span>
  <span m="3984300">it''s</span> <span m="3984440">b1,1</span> <span m="3985520">times</span>
  <span m="3985800">x1</span> <span m="3986290">squared.</span> <span m="3987640">And</span>
  <span m="3987770">we</span> <span m="3987870">would</span> <span m="3988010">be</span>
  <span m="3988110">evaluating</span> <span m="3988670">that</span> <span m="3988880">for</span>
  <span m="3988990">the</span> <span m="3989060">first</span> <span m="3989350">sample.</span>
  <span m="3990410">So we''d</span> <span m="3990630">end</span> <span m="3990750">up</span>
  <span m="3990860">with</span> <span m="3991080">x1,1</span> <span m="3992110">squared</span>
  <span m="3992500">x1,1</span> <span m="3994030">times</span> <span m="3994270">x2,1.</span>
  <span m="3994950">You''d end</span> <span m="3995150">up</span> <span m="3995240">with</span>
  <span m="3995370">all</span> <span m="3995650">the</span> <span m="3995720">quadratic</span>
  <span m="3996190">terms</span> <span m="3996510">matched</span> <span m="3996870">out.</span>
  <span m="3997280">So it</span> <span m="3997420">looks just</span> <span m="3997630">the</span>
  <span m="3997780">same.</span></p><p><span m="4000042">The</span> <span m="4000510">regression''s</span>
  <span m="4001070">not</span> <span m="4001280">really--</span> <span m="4003060">sometimes</span>
  <span m="4003260">it seems</span> <span m="4003680">more</span> <span m="4003830">complicated,</span>
  <span m="4004310">but</span> <span m="4004410">I</span> <span m="4004450">think</span>
  <span m="4004650">if</span> <span m="4004770">you</span> <span m="4005150">just</span>
  <span m="4005340">write</span> <span m="4005510">out</span> <span m="4005620">the</span>
  <span m="4005690">matrix</span> <span m="4006070">system</span> <span m="4006420">and</span>
  <span m="4006540">think</span> <span m="4006720">about</span> <span m="4007020">it</span>
  <span m="4007130">as</span> <span m="4009250">an overdetermined</span> <span m="4009980">set</span>
  <span m="4010100">of</span> <span m="4010170">equations,</span> <span m="4010760">it</span>
  <span m="4010890">becomes</span> <span m="4011500">clearer.</span> <span m="4011700">And</span>
  <span m="4011830">then</span> <span m="4011930">you</span> <span m="4012120">can</span>
  <span m="4012250">also</span> <span m="4012480">see</span> <span m="4012750">we''re</span>
  <span m="4012820">going</span> <span m="4012940">to</span> <span m="4013000">have</span>
  <span m="4013100">more</span> <span m="4013350">unknowns.</span> <span m="4013700">We''re
  going</span> <span m="4013830">to</span> <span m="4013890">add</span> <span m="4014020">more</span>
  <span m="4014180">columns.</span> <span m="4014540">If</span> <span m="4014630">we</span>
  <span m="4014700">want</span> <span m="4014840">it to</span> <span m="4015070">stay</span>
  <span m="4015280">overdetermined,</span> <span m="4016750">or</span> <span m="4016880">at</span>
  <span m="4016940">least</span> <span m="4017170">determined,</span> <span m="4017660">we
  would</span> <span m="4017840">have</span> <span m="4017970">to</span> <span m="4018320">get</span>
  <span m="4018560">more</span> <span m="4018720">samples,</span> <span m="4019500">which</span>
  <span m="4019630">is</span> <span m="4019730">what</span> <span m="4019840">we</span>
  <span m="4019920">talked</span> <span m="4020170">about.</span></p><p><span m="4022670">So</span>
  <span m="4026090">let</span> <span m="4026220">me</span> <span m="4026770">show</span>
  <span m="4027000">you</span> <span m="4027460">how</span> <span m="4028560">that</span>
  <span m="4028700">works.</span> <span m="4028970">Is this</span> <span m="4029430">clear?</span>
  <span m="4029880">Is this notation</span> <span m="4030330">clear?</span></p><p><span
  m="4034162">AUDIENCE: [INAUDIBLE]</span></p><p><span m="4039122">KAREN WILLCOX:
  Say it</span> <span m="4039618">a bit</span> <span m="4040114">louder.</span></p><p><span
  m="4041106">AUDIENCE: [INAUDIBLE]</span></p><p><span m="4047580">KAREN WILLCOX:
  Yeah,</span> <span m="4047970">that''s</span> <span m="4048150">right.</span> <span
  m="4048593">And in</span> <span m="4049036">fact,</span> <span m="4049480">using</span>
  <span m="4049780">a</span> <span m="4050080">first</span> <span m="4050350">order</span>
  <span m="4050580">response</span> <span m="4050870">surface</span> <span m="4051880">is</span>
  <span m="4052000">a</span> <span m="4052070">really</span> <span m="4052320">bad</span>
  <span m="4052530">idea,</span> <span m="4053025">and we''ll</span> <span m="4053520">see
  it</span> <span m="4054140">graphically.</span> <span m="4055106">So it</span> <span
  m="4055572">turns out</span> <span m="4056040">linear</span> <span m="4056340">approximations</span>
  <span m="4057020">in</span> <span m="4057100">optimization</span> <span m="4057740">are</span>
  <span m="4057800">not</span> <span m="4057950">a</span> <span m="4057990">good</span>
  <span m="4058130">idea.</span> <span m="4059580">Maybe you</span> <span m="4059700">can</span>
  <span m="4059850">think</span> <span m="4060050">about</span> <span m="4060270">why</span>
  <span m="4060450">that</span> <span m="4060660">would</span> <span m="4060810">be</span>
  <span m="4061560">with</span> <span m="4061690">a</span> <span m="4061740">linear</span>
  <span m="4061950">approximation.</span></p><p><span m="4064510">You</span> <span
  m="4064620">think</span> <span m="4064910">about</span> <span m="4065090">what</span>
  <span m="4065190">we''re</span> <span m="4065280">doing,</span> <span m="4065480">we''ve
  got</span> <span m="4065710">this</span> <span m="4065860">landscape,</span> <span
  m="4067210">we</span> <span m="4067440">build</span> <span m="4067750">a</span>
  <span m="4067800">linear</span> <span m="4068180">approximation</span> <span m="4068560">and</span>
  <span m="4069000">say</span> <span m="4069280">&quot;optimize.&quot;</span> <span
  m="4070410">Find</span> <span m="4070630">a</span> <span m="4070680">new</span>
  <span m="4070830">point,</span> <span m="4071210">and</span> <span m="4071710">build
  a</span> <span m="4072210">new</span> <span m="4072710">linear</span> <span m="4072940">approximation.</span>
  <span m="4073220">But</span> <span m="4073500">where</span> <span m="4073850">is
  the</span> <span m="4073930">linear</span> <span m="4074170">approximation</span>
  <span m="4074770">always</span> <span m="4074970">going</span> <span m="4075090">to</span>
  <span m="4075180">send</span> <span m="4075665">you?</span> <span m="4078575">It''s</span>
  <span m="4079060">always</span> <span m="4079190">going to</span> <span m="4079320">send</span>
  <span m="4079460">you</span> <span m="4080640">far</span> <span m="4080920">away</span>
  <span m="4081300">in</span> <span m="4081920">some</span> <span m="4082190">direction,</span>
  <span m="4082880">kind</span> <span m="4082990">of</span> <span m="4083070">by</span>
  <span m="4083360">definition.</span></p><p><span m="4084305">So I</span> <span m="4084650">build</span>
  <span m="4084720">a linear</span> <span m="4084860">approximation</span> <span m="4085340">here.</span>
  <span m="4085510">If it''s</span> <span m="4085660">sloping</span> <span m="4086010">this</span>
  <span m="4086180">way,</span> <span m="4086310">it''s</span> <span m="4086410">going</span>
  <span m="4086530">to</span> <span m="4086690">take you</span> <span m="4086880">all</span>
  <span m="4087080">the</span> <span m="4087160">way</span> <span m="4087310">to</span>
  <span m="4087390">that</span> <span m="4087590">side of</span> <span m="4087750">the</span>
  <span m="4087810">design</span> <span m="4088170">space.</span> <span m="4089480">If</span>
  <span m="4089630">it''s</span> <span m="4089810">sloping</span> <span m="4089990">the</span>
  <span m="4090140">other</span> <span m="4090270">way,</span> <span m="4090440">so
  it''s</span> <span m="4090840">always</span> <span m="4091230">going</span> <span
  m="4091350">to</span> <span m="4091410">send</span> <span m="4091660">you</span>
  <span m="4092326">[INAUDIBLE].</span> <span m="4093160">So</span> <span m="4093270">you</span>
  <span m="4093390">could</span> <span m="4093540">combine</span> <span m="4093920">it</span>
  <span m="4094040">with</span> <span m="4094190">a</span> <span m="4094230">strategy</span>
  <span m="4094495">that--</span> <span m="4096090">that''s</span> <span m="4096260">what</span>
  <span m="4096330">a trust</span> <span m="4096614">region</span> <span m="4096899">does.</span></p><p><span
  m="4097479">But</span> <span m="4097609">actually</span> <span m="4097819">it turns</span>
  <span m="4098140">out that</span> <span m="4098240">quadratic</span> <span m="4098720">approximation,</span>
  <span m="4099930">because</span> <span m="4100229">they</span> <span m="4100380">embed</span>
  <span m="4100790">the</span> <span m="4100880">information</span> <span m="4101330">of</span>
  <span m="4101410">curvature,</span> <span m="4101890">which</span> <span m="4102080">we</span>
  <span m="4102170">know</span> <span m="4102330">is</span> <span m="4102460">really</span>
  <span m="4102670">important</span> <span m="4103220">for</span> <span m="4103689">optimality</span>
  <span m="4104229">conditions,</span> <span m="4106552">are</span> <span m="4108031">far,</span>
  <span m="4108524">far</span> <span m="4109020">better</span> <span m="4109229">choices</span>
  <span m="4109750">and</span> <span m="4111010">more</span> <span m="4113580">commonly</span>
  <span m="4114080">used.</span> <span m="4118240">Put</span> <span m="4118500">up</span>
  <span m="4118700">on</span> <span m="4119170">[? stellar ?],</span> <span m="4121350">it</span>
  <span m="4121529">goes</span> <span m="4121869">through</span> <span m="4122550">what</span>
  <span m="4123479">we</span> <span m="4123609">just wrote</span> <span m="4123960">on</span>
  <span m="4124060">the</span> <span m="4124140">board.</span> <span m="4125100">But</span>
  <span m="4125580">Let</span> <span m="4125760">me</span> <span m="4125930">just</span>
  <span m="4129779">get</span> <span m="4129970">rid</span> <span m="4130109">of</span>
  <span m="4130220">that</span> <span m="4130450">horrible</span> <span m="4130800">genetic</span>
  <span m="4131189">algorithm</span> <span m="4134550">and</span> <span m="4136882">get
  to</span> <span m="4137340">the</span> <span m="4137470">right</span> <span m="4138314">directory.</span></p><p><span
  m="4150194">So</span> <span m="4151184">I</span> <span m="4151679">have a</span>
  <span m="4153670">code</span> <span m="4153950">here</span> <span m="4154319">that</span>
  <span m="4156460">is</span> <span m="4156660">going</span> <span m="4157010">to</span>
  <span m="4157130">build</span> <span m="4158220">some</span> <span m="4158359">response</span>
  <span m="4158760">surface.</span> <span m="4158939">It''s</span> <span m="4159060">the</span>
  <span m="4159609">same</span> <span m="4159970">demo.</span> <span m="4160779">It''s</span>
  <span m="4160950">this</span> <span m="4161029">peak</span> <span m="4161399">problem,</span>
  <span m="4161779">the</span> <span m="4162120">landscape</span> <span m="4162240">problem.</span>
  <span m="4163140">So</span> <span m="4163590">it''s</span> <span m="4164040">going
  to</span> <span m="4164490">grab some</span> <span m="4164880">samples.</span> <span
  m="4165260">Maybe</span> <span m="4165450">I''ll</span> <span m="4165569">just</span>
  <span m="4165890">do</span> <span m="4166180">it and we can</span> <span m="4166540">look</span>
  <span m="4166689">at</span> <span m="4166770">the</span> <span m="4166840">code.</span>
  <span m="4168120">And we''re</span> <span m="4168310">going</span> <span m="4168430">to</span>
  <span m="4168500">build</span> <span m="4168720">some</span> <span m="4168890">response</span>
  <span m="4169180">surfaces</span> <span m="4169470">so</span> <span m="4169630">you</span>
  <span m="4169890">can--</span> <span m="4173650">so in</span> <span m="4174120">this</span>
  <span m="4174210">first</span> <span m="4175240">example,</span> <span m="4175740">again,</span>
  <span m="4175979">here''s</span> <span m="4176109">our</span> <span m="4176569">landscape,</span>
  <span m="4177160">variable</span> <span m="4177399">x1,</span> <span m="4178210">variable</span>
  <span m="4178480">x2,</span> <span m="4179370">objective</span> <span m="4179760">function.</span></p><p><span
  m="4182060">We</span> <span m="4182200">happen</span> <span m="4182439">to</span>
  <span m="4182520">generate</span> <span m="4182880">these</span> <span m="4183029">[AUDIO
  OUT].</span> <span m="4186560">Maybe</span> <span m="4186760">they</span> <span
  m="4186840">were</span> <span m="4186950">random.</span> <span m="4187330">Maybe</span>
  <span m="4187590">we</span> <span m="4187770">had</span> <span m="4187859">some</span>
  <span m="4187979">kind</span> <span m="4188109">of</span> <span m="4188180">design</span>
  <span m="4188439">of</span> <span m="4188540">experiments</span> <span m="4189220">method</span>
  <span m="4189640">to</span> <span m="4189729">do</span> <span m="4189920">it.</span>
  <span m="4190609">And</span> <span m="4191140">three</span> <span m="4191390">points,</span>
  <span m="4191720">two</span> <span m="4191850">dimensions,</span> <span m="4192460">what</span>
  <span m="4192640">can we</span> <span m="4192819">fit?</span> <span m="4194340">What</span>
  <span m="4194430">kind</span> <span m="4194600">of a</span> <span m="4194660">response</span>
  <span m="4195080">surface</span> <span m="4195300">can</span> <span m="4195450">we</span>
  <span m="4195550">fit?</span> <span m="4196960">Linear</span> <span m="4197350">one,</span>
  <span m="4197730">first order?</span> <span m="4199110">n</span> <span m="4199310">plus</span>
  <span m="4199560">1?</span> <span m="4201690">We</span> <span m="4201760">don''t</span>
  <span m="4201890">have</span> <span m="4202010">enough</span> <span m="4202360">to</span>
  <span m="4202500">fit</span> <span m="4202730">a</span> <span m="4203073">quadratic.</span>
  <span m="4203760">So</span> <span m="4203860">there</span> <span m="4204240">is--</span>
  <span m="4204630">in</span> <span m="4205020">effect,</span> <span m="4205410">it''s</span>
  <span m="4205790">determined.</span> <span m="4207050">It''s</span> <span m="4207270">three</span>
  <span m="4207670">unknowns,</span> <span m="4208470">constant,</span> <span m="4214000">slope</span>
  <span m="4214230">in the</span> <span m="4214340">x</span> <span m="4214810">direction,</span>
  <span m="4215240">slope in</span> <span m="4215400">the</span> <span m="4215500">x2</span>
  <span m="4215920">direction.</span></p><p><span m="4216810">So</span> <span m="4217260">there''s</span>
  <span m="4217580">the</span> <span m="4217640">response</span> <span m="4218060">surface.</span>
  <span m="4218470">It''s</span> <span m="4218670">clean.</span> <span m="4219060">It
  goes exactly</span> <span m="4219410">through those</span> <span m="4219750">three</span>
  <span m="4219990">points.</span> <span m="4220980">And you see</span> <span m="4221420">kind</span>
  <span m="4221680">of</span> <span m="4221740">the</span> <span m="4221810">problem</span>
  <span m="4222140">that</span> <span m="4222490">[? Tyrone ?]</span> <span m="4222780">was</span>
  <span m="4222960">asking</span> <span m="4223260">about,</span> <span m="4223620">which</span>
  <span m="4223730">is</span> <span m="4224320">if</span> <span m="4224560">we</span>
  <span m="4225030">use</span> <span m="4225210">this</span> <span m="4225370">optimization,</span>
  <span m="4225910">it''s</span> <span m="4226030">going</span> <span m="4226160">to</span>
  <span m="4226250">send</span> <span m="4226540">us--</span> <span m="4226760">and</span>
  <span m="4227230">we maximize,</span> <span m="4227700">it''s going</span> <span
  m="4228000">to</span> <span m="4228060">send us</span> <span m="4228470">over into</span>
  <span m="4228520">the corner</span> <span m="4228760">of</span> <span m="4228840">the</span>
  <span m="4228900">design</span> <span m="4229300">space.</span> <span m="4230100">Clearly</span>
  <span m="4230460">it''s</span> <span m="4230610">not</span> <span m="4231240">a</span>
  <span m="4231290">good</span> <span m="4231450">approximation.</span></p><p><span
  m="4233470">So</span> <span m="4234720">we</span> <span m="4234830">could</span>
  <span m="4234960">generate</span> <span m="4235280">more</span> <span m="4235460">points.</span>
  <span m="4235930">So</span> <span m="4236020">now</span> <span m="4236340">we</span>
  <span m="4236460">have</span> <span m="4236730">these</span> <span m="4237050">six</span>
  <span m="4237330">points.</span> <span m="4238640">And</span> <span m="4238800">now</span>
  <span m="4238910">that</span> <span m="4239040">we</span> <span m="4239740">have</span>
  <span m="4239950">six</span> <span m="4240180">points,</span> <span m="4240460">we</span>
  <span m="4240530">could</span> <span m="4240660">still</span> <span m="4240910">set
  a</span> <span m="4241250">linear</span> <span m="4241420">model,</span> <span m="4241710">but</span>
  <span m="4241890">now</span> <span m="4241970">it</span> <span m="4242250">would</span>
  <span m="4242440">be</span> <span m="4243000">an</span> <span m="4243130">overdetermined</span>
  <span m="4243750">system.</span> <span m="4244050">The</span> <span m="4244230">matrix</span>
  <span m="4244580">has</span> <span m="4244680">got</span> <span m="4245010">six</span>
  <span m="4245300">rows,</span> <span m="4245770">because there</span> <span m="4245920">are</span>
  <span m="4245980">six</span> <span m="4246402">sample points.</span> <span m="4247246">And
  it''s</span> <span m="4247668">got three</span> <span m="4248090">columns</span>
  <span m="4248550">because</span> <span m="4248730">there</span> <span m="4248850">are</span>
  <span m="4248940">still</span> <span m="4249220">three</span> <span m="4249820">degrees</span>
  <span m="4250170">of</span> <span m="4250250">freedom,</span> <span m="4250670">the</span>
  <span m="4250770">constant,</span> <span m="4251470">the</span> <span m="4251810">slope
  in</span> <span m="4252080">the</span> <span m="4252190">x1</span> <span m="4252670">direction,</span>
  <span m="4253010">and</span> <span m="4253130">the slope</span> <span m="4253440">the</span>
  <span m="4253570">x2</span> <span m="4254050">direction.</span></p><p><span m="4255550">So</span>
  <span m="4255690">now</span> <span m="4256300">you</span> <span m="4256460">still</span>
  <span m="4256640">have</span> <span m="4256760">a</span> <span m="4256810">linear</span>
  <span m="4257090">model,</span> <span m="4257450">but</span> <span m="4257610">you</span>
  <span m="4257690">can</span> <span m="4257890">see</span> <span m="4258080">that</span>
  <span m="4258660">it</span> <span m="4258970">doesn''t</span> <span m="4259420">go</span>
  <span m="4259980">through</span> <span m="4260230">the</span> <span m="4260330">points.</span>
  <span m="4260910">And</span> <span m="4261000">in</span> <span m="4261100">fact,</span>
  <span m="4261380">it''s</span> <span m="4261660">the</span> <span m="4261830">least</span>
  <span m="4262110">squares</span> <span m="4262680">is</span> <span m="4262820">like</span>
  <span m="4263030">the</span> <span m="4263110">line</span> <span m="4263350">of</span>
  <span m="4263470">best</span> <span m="4263900">fit,</span> <span m="4264330">but
  we''re in</span> <span m="4264760">multiple</span> <span m="4265130">dimensions.</span>
  <span m="4266400">So it''s</span> <span m="4266500">like</span> <span m="4266710">the</span>
  <span m="4266780">plane</span> <span m="4267130">of</span> <span m="4267240">best</span>
  <span m="4267510">fit.</span> <span m="4268200">Three of</span> <span m="4268520">the</span>
  <span m="4268620">points are</span> <span m="4268990">above,</span> <span m="4270420">and</span>
  <span m="4270730">the</span> <span m="4270830">other</span> <span m="4270990">three</span>
  <span m="4272360">want</span> <span m="4272550">to</span> <span m="4272670">be</span>
  <span m="4272780">sitting</span> <span m="4273780">somewhere</span> <span m="4274050">underneath</span>
  <span m="4274520">here.</span> <span m="4276130">And</span> <span m="4277410">maybe</span>
  <span m="4277610">if</span> <span m="4277730">you''ve</span> <span m="4277800">taken</span>
  <span m="4278010">1806--</span> <span m="4278570">they''re</span> <span m="4278670">sitting</span>
  <span m="4278910">underneath</span> <span m="4279270">here.</span> <span m="4279540">Maybe</span>
  <span m="4279730">if</span> <span m="4279790">you''ve</span> <span m="4279890">taken</span>
  <span m="4280090">1806,</span> <span m="4280380">you know</span> <span m="4280860">that</span>
  <span m="4281852">this</span> <span m="4283340">solution</span> <span m="4284830">is</span>
  <span m="4284960">going to be</span> <span m="4285170">the</span> <span m="4285260">one</span>
  <span m="4285440">that</span> <span m="4285550">minimizes</span> <span m="4286190">the</span>
  <span m="4286280">sum</span> <span m="4286460">of</span> <span m="4286610">the</span>
  <span m="4286870">squares</span> <span m="4287250">of</span> <span m="4287595">the</span>
  <span m="4288030">two</span> <span m="4288170">norm</span> <span m="4288380">distance.</span>
  <span m="4289120">So</span> <span m="4289250">it</span> <span m="4289320">is</span>
  <span m="4289470">the</span> <span m="4289540">line</span> <span m="4289780">of</span>
  <span m="4289870">best fit</span> <span m="4290250">in</span> <span m="4290410">that</span>
  <span m="4294310">optimal</span> <span m="4294680">sense.</span> <span m="4295310">That''s</span>
  <span m="4295480">what</span> <span m="4295590">the</span> <span m="4295950">least</span>
  <span m="4296180">squares</span> <span m="4296470">fit</span> <span m="4296570">is.</span></p><p><span
  m="4297960">OK.</span> <span m="4298400">So now</span> <span m="4298570">we</span>
  <span m="4298650">have</span> <span m="4298800">six</span> <span m="4299185">points,</span>
  <span m="4300180">which</span> <span m="4300310">turns</span> <span m="4300550">out</span>
  <span m="4300720">to</span> <span m="4300820">be</span> <span m="4301060">n</span>
  <span m="4301380">times</span> <span m="4301590">n</span> <span m="4301720">plus</span>
  <span m="4301830">1</span> <span m="4302040">over</span> <span m="4302140">2,</span>
  <span m="4302260">which</span> <span m="4302490">is</span> <span m="4303110">how</span>
  <span m="4303280">many</span> <span m="4303480">points</span> <span m="4303800">we</span>
  <span m="4303900">need</span> <span m="4304200">to</span> <span m="4304290">fit</span>
  <span m="4305160">a</span> <span m="4305250">quadratic</span> <span m="4305720">model.</span>
  <span m="4306180">So</span> <span m="4306310">we have</span> <span m="4306500">six</span>
  <span m="4306700">points.</span> <span m="4307690">And you</span> <span m="4307840">think</span>
  <span m="4308030">about the</span> <span m="4308300">quadratic</span> <span m="4308700">model,</span>
  <span m="4308940">what do</span> <span m="4309060">you</span> <span m="4309350">have?</span>
  <span m="4309440">You have the</span> <span m="4309480">constant,</span> <span m="4310260">a0,</span>
  <span m="4311100">you</span> <span m="4311210">have the</span> <span m="4311360">linear</span>
  <span m="4311490">terms,</span> <span m="4312070">a1</span> <span m="4312440">and</span>
  <span m="4312550">a2,</span> <span m="4314200">and</span> <span m="4314330">then</span>
  <span m="4314440">you</span> <span m="4314520">have</span> <span m="4314960">of</span>
  <span m="4315670">b1,1,</span> <span m="4317240">[INAUDIBLE]</span> <span m="4318450">squared.</span>
  <span m="4319180">You</span> <span m="4319320">have</span> <span m="4320030">b2,2</span>
  <span m="4320740">for</span> <span m="4320950">x2</span> <span m="4321490">squared,</span>
  <span m="4321840">and</span> <span m="4322010">then you</span> <span m="4322080">have</span>
  <span m="4322290">b1,2</span> <span m="4322650">for</span> <span m="4322880">x1</span>
  <span m="4324430">x2.</span></p><p><span m="4325420">You have</span> <span m="4325610">six</span>
  <span m="4325800">degrees</span> <span m="4326020">of</span> <span m="4326110">freedom</span>
  <span m="4326490">to</span> <span m="4326600">fit</span> <span m="4326790">a</span>
  <span m="4326830">quadratic</span> <span m="4327290">model</span> <span m="4327760">in</span>
  <span m="4328440">2D.</span> <span m="4329930">I wrote out the</span> <span m="4330290">expansion.</span>
  <span m="4331360">So</span> <span m="4331600">six</span> <span m="4331940">points,</span>
  <span m="4332280">six degrees</span> <span m="4332620">of</span> <span m="4332710">freedom.</span>
  <span m="4333660">Again,</span> <span m="4333990">our</span> <span m="4334120">matrix</span>
  <span m="4334460">system</span> <span m="4334820">would</span> <span m="4334920">be</span>
  <span m="4335050">6</span> <span m="4335350">by</span> <span m="4335605">6,</span>
  <span m="4335860">so it</span> <span m="4335960">would</span> <span m="4336060">be</span>
  <span m="4336170">uniquely</span> <span m="4336600">determined.</span> <span m="4337820">And</span>
  <span m="4337880">this</span> <span m="4338020">is</span> <span m="4338110">what</span>
  <span m="4338270">the</span> <span m="4338360">quadratic</span> <span m="4338900">response</span>
  <span m="4339350">surface</span> <span m="4339640">looks</span> <span m="4339940">like.</span>
  <span m="4340390">And</span> <span m="4340800">as</span> <span m="4341210">you can
  see,</span> <span m="4341620">it''s</span> <span m="4341870">going</span> <span
  m="4342100">exactly</span> <span m="4342405">through</span> <span m="4342710">those</span>
  <span m="4344010">points.</span></p><p><span m="4346240">OK,</span> <span m="4346660">so</span>
  <span m="4347490">now</span> <span m="4347970">we''re</span> <span m="4348190">starting</span>
  <span m="4348490">to</span> <span m="4348580">get</span> <span m="4348710">a</span>
  <span m="4348750">little</span> <span m="4348990">bit</span> <span m="4349150">of</span>
  <span m="4349480">curvature.</span> <span m="4351710">With</span> <span m="4351850">a</span>
  <span m="4351890">quadratic</span> <span m="4352320">model,</span> <span m="4352630">we</span>
  <span m="4352730">can</span> <span m="4352870">only</span> <span m="4353090">ever</span>
  <span m="4353270">have</span> <span m="4353580">one</span> <span m="4354740">minimum</span>
  <span m="4355200">or</span> <span m="4355360">one</span> <span m="4355520">maximum</span>
  <span m="4355960">for</span> <span m="4356090">the</span> <span m="4356170">models</span>
  <span m="4356460">that look</span> <span m="4356750">like</span> <span m="4356960">this,</span>
  <span m="4357610">whereas</span> <span m="4357980">we</span> <span m="4358070">know</span>
  <span m="4358290">that</span> <span m="4358430">the</span> <span m="4358500">design</span>
  <span m="4358860">space</span> <span m="4359190">we''re</span> <span m="4359310">trying</span>
  <span m="4359510">to</span> <span m="4359570">approximate</span> <span m="4360180">has</span>
  <span m="4360350">got</span> <span m="4361000">multiple</span> <span m="4361390">blobs.</span>
  <span m="4362240">But</span> <span m="4362310">a</span> <span m="4362370">quadratic</span>
  <span m="4362730">model;s</span> <span m="4363020">not</span> <span m="4363740">ever</span>
  <span m="4363880">going</span> <span m="4364010">to</span> <span m="4364080">capture</span>
  <span m="4365160">these</span> <span m="4365390">multiple</span> <span m="4366510">hills</span>
  <span m="4366710">in</span> <span m="4366790">this</span> <span m="4366950">case.</span></p><p><span
  m="4370840">I</span> <span m="4371000">mentioned</span> <span m="4371270">really</span>
  <span m="4371460">briefly</span> <span m="4371720">on one</span> <span m="4371840">of</span>
  <span m="4371900">the</span> <span m="4371960">slides</span> <span m="4372220">that</span>
  <span m="4372310">we</span> <span m="4372390">could</span> <span m="4372530">think</span>
  <span m="4372700">about</span> <span m="4372890">adapting</span> <span m="4373440">the</span>
  <span m="4373510">model.</span> <span m="4374010">So</span> <span m="4374190">maybe</span>
  <span m="4374660">as</span> <span m="4375160">we''re</span> <span m="4375260">going</span>
  <span m="4375540">through</span> <span m="4375640">the</span> <span m="4375730">optimization,</span>
  <span m="4377480">maybe</span> <span m="4377780">we can make</span> <span m="4378140">a</span>
  <span m="4378230">genetic</span> <span m="4378560">algorithm,</span> <span m="4378680">even</span>
  <span m="4378820">though</span> <span m="4378930">we''re</span> <span m="4379020">not</span>
  <span m="4379260">supposed</span> <span m="4379480">to.</span> <span m="4379760">We''re</span>
  <span m="4380030">figuring</span> <span m="4380490">out</span> <span m="4380620">that</span>
  <span m="4380710">this</span> <span m="4380870">is</span> <span m="4380970">the</span>
  <span m="4381060">interesting</span> <span m="4381620">region</span> <span m="4381900">in</span>
  <span m="4381990">the</span> <span m="4382070">design</span> <span m="4382450">space,</span>
  <span m="4383460">so</span> <span m="4383490">rather</span> <span m="4383730">than</span>
  <span m="4383880">having</span> <span m="4384190">our</span> <span m="4384340">points</span>
  <span m="4385240">spread</span> <span m="4385630">out</span> <span m="4385900">everywhere,</span>
  <span m="4387250">we</span> <span m="4387380">might</span> <span m="4387650">be</span>
  <span m="4387760">saying</span> <span m="4388160">let''s</span> <span m="4388430">kind</span>
  <span m="4388590">of</span> <span m="4388750">only</span> <span m="4389240">on</span>
  <span m="4389730">the</span> <span m="4390220">points</span> <span m="4390510">that</span>
  <span m="4390630">have</span> <span m="4390720">got</span> <span m="4390810">good</span>
  <span m="4391576">performance</span> <span m="4393140">that</span> <span m="4393270">we''ve</span>
  <span m="4393370">found</span> <span m="4393680">so</span> <span m="4393820">far.</span></p><p><span
  m="4394650">So</span> <span m="4394780">see</span> <span m="4394880">all these</span>
  <span m="4395160">points</span> <span m="4395490">around</span> <span m="4395730">here--</span>
  <span m="4395930">[INAUDIBLE]</span> <span m="4396280">this</span> <span m="4396570">one</span>
  <span m="4396730">does</span> <span m="4396950">too</span> <span m="4397090">because</span>
  <span m="4397190">it''s</span> <span m="4397440">on</span> <span m="4397580">the</span>
  <span m="4397780">side</span> <span m="4398040">of</span> <span m="4398120">that</span>
  <span m="4398270">other</span> <span m="4399640">little</span> <span m="4399990">hill</span>
  <span m="4400120">that</span> <span m="4400280">sits over</span> <span m="4400570">here.</span>
  <span m="4401520">So</span> <span m="4401920">if</span> <span m="4402030">you</span>
  <span m="4402130">build a</span> <span m="4402400">response</span> <span m="4402690">surface</span>
  <span m="4403090">using</span> <span m="4403610">those</span> <span m="4404040">points,</span>
  <span m="4405090">maybe</span> <span m="4405660">you</span> <span m="4405730">can</span>
  <span m="4405860">see</span> <span m="4406040">now</span> <span m="4406550">that</span>
  <span m="4407560">the</span> <span m="4407660">model''s</span> <span m="4408310">really</span>
  <span m="4408550">pretty</span> <span m="4408810">terrible</span> <span m="4410150">over</span>
  <span m="4410340">here,</span> <span m="4410580">but</span> <span m="4410690">it''s</span>
  <span m="4410800">actually</span> <span m="4411160">starting</span> <span m="4411410">to</span>
  <span m="4411490">be</span> <span m="4411580">a</span> <span m="4411650">pretty</span>
  <span m="4411850">good</span> <span m="4411970">approximation</span> <span m="4412600">of</span>
  <span m="4412670">what''s</span> <span m="4412850">going</span> <span m="4413120">on</span>
  <span m="4413280">locally</span> <span m="4413710">around</span> <span m="4413910">those</span>
  <span m="4414150">points.</span></p><p><span m="4415390">And</span> <span m="4415500">that''s</span>
  <span m="4415660">a</span> <span m="4415700">common</span> <span m="4416040">strategy</span>
  <span m="4416710">would</span> <span m="4416880">be</span> <span m="4417660">to</span>
  <span m="4417800">build</span> <span m="4418020">these</span> <span m="4418220">local</span>
  <span m="4418680">quadratic</span> <span m="4419220">models</span> <span m="4420340">in</span>
  <span m="4420490">regions</span> <span m="4420890">where</span> <span m="4420980">you''ve</span>
  <span m="4421130">sampled</span> <span m="4421590">and</span> <span m="4421730">use</span>
  <span m="4421920">them</span> <span m="4422070">to</span> <span m="4422170">make</span>
  <span m="4422370">progress,</span> <span m="4422740">and then to</span> <span m="4422990">keep</span>
  <span m="4423230">updating</span> <span m="4423515">them.</span> <span m="4425020">And</span>
  <span m="4425170">even</span> <span m="4425360">though a</span> <span m="4425630">quadratic</span>
  <span m="4426050">model</span> <span m="4426320">seems</span> <span m="4426750">really</span>
  <span m="4426970">simple</span> <span m="4427800">for</span> <span m="4427970">a</span>
  <span m="4428010">real</span> <span m="4428240">problem,</span> <span m="4430250">that</span>
  <span m="4430450">strategy</span> <span m="4430620">of</span> <span m="4430950">adapting</span>
  <span m="4431320">points</span> <span m="4432030">and</span> <span m="4432170">building</span>
  <span m="4432320">local</span> <span m="4432700">models</span> <span m="4433176">[AUDIO
  OUT]</span> <span m="4442950">updating</span> <span m="4443020">the model</span>
  <span m="4443230">as we go</span> <span m="4443580">is</span> <span m="4443930">actually</span>
  <span m="4444220">a</span> <span m="4444440">really,</span> <span m="4444810">really</span>
  <span m="4445050">powerful</span> <span m="4445480">one.</span></p><p><span m="4447780">And</span>
  <span m="4448040">of</span> <span m="4448120">course</span> <span m="4448340">if</span>
  <span m="4448930">we</span> <span m="4449130">had</span> <span m="4449450">more</span>
  <span m="4449630">points--</span> <span m="4449890">I don''t</span> <span m="4449950">think</span>
  <span m="4450140">I''ve got</span> <span m="4450430">one</span> <span m="4450700">that''s</span>
  <span m="4451120">got</span> <span m="4451540">more</span> <span m="4451770">points.</span>
  <span m="4452120">If</span> <span m="4452190">you</span> <span m="4452250">had</span>
  <span m="4452350">more</span> <span m="4452560">than</span> <span m="4452700">six</span>
  <span m="4452990">points,</span> <span m="4453920">than</span> <span m="4454000">the</span>
  <span m="4454060">quadratic</span> <span m="4455260">model</span> <span m="4455510">again</span>
  <span m="4455770">would be</span> <span m="4455900">the</span> <span m="4456340">quadratic</span>
  <span m="4456740">model</span> <span m="4456980">of</span> <span m="4457090">this</span>
  <span m="4457330">fit,</span> <span m="4457812">where it</span> <span m="4458294">wouldn''t
  go</span> <span m="4459740">through all</span> <span m="4460222">the</span> <span
  m="4460710">points,</span> <span m="4462250">but</span> <span m="4462490">it would</span>
  <span m="4463520">cut</span> <span m="4463750">through</span> <span m="4463930">them</span>
  <span m="4464510">on</span> <span m="4464710">average</span> <span m="4465190">equally.</span>
  <span m="4467890">OK,</span> <span m="4468200">questions?</span></p><p><span m="4474030">So</span>
  <span m="4474430">that''s</span> <span m="4474690">a</span> <span m="4475490">pretty,</span>
  <span m="4476550">I</span> <span m="4476650">think,</span> <span m="4476890">neat</span>
  <span m="4477510">use</span> <span m="4477880">of</span> <span m="4478010">regression</span>
  <span m="4478520">that''s</span> <span m="4478680">actually</span> <span m="4479150">very</span>
  <span m="4479360">powerful</span> <span m="4479830">and</span> <span m="4479920">is</span>
  <span m="4481830">used</span> <span m="4483150">a</span> <span m="4483320">lot</span>
  <span m="4483610">in</span> <span m="4485910">practice.</span> <span m="4486796">So</span>
  <span m="4488460">that''s</span> <span m="4488700">one</span> <span m="4488800">of</span>
  <span m="4488870">the</span> <span m="4488940">things</span> <span m="4489510">that</span>
  <span m="4489650">you</span> <span m="4489730">need</span> <span m="4489950">to</span>
  <span m="4490050">be able</span> <span m="4490432">to do.</span> <span m="4490814">So</span>
  <span m="4491580">have</span> <span m="4491730">a</span> <span m="4491800">basic</span>
  <span m="4492100">understanding</span> <span m="4492680">of</span> <span m="4492820">how</span>
  <span m="4493210">a</span> <span m="4493270">design</span> <span m="4493590">problem</span>
  <span m="4493900">can</span> <span m="4494060">be</span> <span m="4494160">posed</span>
  <span m="4494480">as</span> <span m="4494580">an</span> <span m="4494680">optimization</span>
  <span m="4495300">problem.</span> <span m="4495600">What</span> <span m="4495730">do</span>
  <span m="4495850">I</span> <span m="4495950">mean</span> <span m="4496180">when</span>
  <span m="4496290">I</span> <span m="4496360">say</span> <span m="4496580">constraint?</span>
  <span m="4497300">What</span> <span m="4497430">I</span> <span m="4497540">mean</span>
  <span m="4497700">when</span> <span m="4497800">I</span> <span m="4497860">say</span>
  <span m="4498020">objective</span> <span m="4498400">function?</span> <span m="4500100">Have</span>
  <span m="4500220">a</span> <span m="4500270">basic</span> <span m="4500590">understanding</span>
  <span m="4501050">of</span> <span m="4501120">the</span> <span m="4501210">steps,</span>
  <span m="4501590">and</span> <span m="4501740">the</span> <span m="4501810">gradient-based</span>
  <span m="4502760">constrained</span> <span m="4503140">optimization</span> <span
  m="4503370">algorithms</span> <span m="4504040">are</span> <span m="4504130">looking</span>
  <span m="4504520">for</span> <span m="4504700">the</span> <span m="4504790">direction</span>
  <span m="4505340">and</span> <span m="4505480">how</span> <span m="4506330">the</span>
  <span m="4506450">different</span> <span m="4508990">methods</span> <span m="4509260">do</span>
  <span m="4509400">that.</span></p><p><span m="4510165">Be</span> <span m="4510590">able</span>
  <span m="4510890">to</span> <span m="4510960">estimate</span> <span m="4511230">a</span>
  <span m="4511330">gradient,</span> <span m="4511660">a first</span> <span m="4512120">order</span>
  <span m="4512260">or</span> <span m="4512480">second</span> <span m="4512760">order</span>
  <span m="4513180">derivative</span> <span m="4513690">using</span> <span m="4513930">finite</span>
  <span m="4514275">differences.</span> <span m="4514620">You</span> <span m="4514700">could</span>
  <span m="4514860">already</span> <span m="4515090">do</span> <span m="4515250">that.</span>
  <span m="4515610">You</span> <span m="4515790">just</span> <span m="4516090">did</span>
  <span m="4516230">it</span> <span m="4516340">in</span> <span m="4516420">the</span>
  <span m="4516480">context</span> <span m="4516980">of</span> <span m="4517630">PDEs.</span>
  <span m="4518365">Now</span> <span m="4518750">we''re</span> <span m="4518910">talking</span>
  <span m="4519100">about</span> <span m="4519300">design</span> <span m="4519590">problems.</span>
  <span m="4520650">And</span> <span m="4520850">understand</span> <span m="4521370">how</span>
  <span m="4521760">you</span> <span m="4522130">could</span> <span m="4522390">construct</span>
  <span m="4523200">a</span> <span m="4523320">polynomial</span> <span m="4523840">response</span>
  <span m="4524260">surface,</span> <span m="4524540">either</span> <span m="4524730">linear</span>
  <span m="4525300">or</span> <span m="4525440">quadratic,</span> <span m="4526450">using</span>
  <span m="4526800">least</span> <span m="4527000">squares</span> <span m="4527360">regression.</span></p><p><span
  m="4528940">Actually,</span> <span m="4529170">we</span> <span m="4529250">didn''t</span>
  <span m="4529450">talk</span> <span m="4529580">about</span> <span m="4530190">the</span>
  <span m="4530290">quality</span> <span m="4530580">of</span> <span m="4530700">fit.</span>
  <span m="4531172">Do you guys</span> <span m="4531644">remember</span> <span m="4532116">what''s
  the</span> <span m="4532588">quality of fit</span> <span m="4533060">metric</span>
  <span m="4533520">for</span> <span m="4533760">regression</span> <span m="4534050">models?</span>
  <span m="4535866">r</span> <span m="4536330">squared.</span> <span m="4536850">Yeah,</span>
  <span m="4537275">so</span> <span m="4537700">r</span> <span m="4538070">squared</span>
  <span m="4538290">tells</span> <span m="4538630">you</span> <span m="4538990">how</span>
  <span m="4539700">well</span> <span m="4540040">your</span> <span m="4540190">surface</span>
  <span m="4541020">approximates</span> <span m="4541335">your</span> <span m="4541650">data</span>
  <span m="4541910">points.</span> <span m="4542220">But</span> <span m="4542330">you</span>
  <span m="4542410">have</span> <span m="4542560">to</span> <span m="4542640">be</span>
  <span m="4542720">careful</span> <span m="4543200">because</span> <span m="4543460">it</span>
  <span m="4543530">doesn''t</span> <span m="4543760">tell</span> <span m="4543940">you</span>
  <span m="4544090">anything</span> <span m="4545280">about</span> <span m="4545620">how</span>
  <span m="4545980">good</span> <span m="4546160">it</span> <span m="4546260">might</span>
  <span m="4546460">be</span> <span m="4546570">in</span> <span m="4546700">regions</span>
  <span m="4547090">where you</span> <span m="4547554">didn''t sample.</span></p><p><span
  m="4550340">All</span> <span m="4550520">right.</span> <span m="4550690">Final</span>
  <span m="4551010">questions?</span> <span m="4556970">You guys</span> <span m="4557210">feel</span>
  <span m="4557480">like</span> <span m="4557660">you''ve</span> <span m="4557850">learned</span>
  <span m="4558090">enough</span> <span m="4558390">in</span> <span m="4558520">this</span>
  <span m="4558610">class</span> <span m="4558880">already?</span> <span m="4560970">No?</span>
  <span m="4562380">OK.</span> <span m="4562660">So</span> <span m="4562880">on</span>
  <span m="4563030">Wednesday,</span> <span m="4565300">I</span> <span m="4565460">will</span>
  <span m="4566070">do</span> <span m="4566270">a</span> <span m="4566370">review</span>
  <span m="4567050">of</span> <span m="4567560">finite--</span> <span m="4567940">I</span>
  <span m="4568050">think</span> <span m="4568230">I''m</span> <span m="4568260">going</span>
  <span m="4568390">to</span> <span m="4568450">focus</span> <span m="4568750">only</span>
  <span m="4568960">on</span> <span m="4569100">finite</span> <span m="4569475">element</span>
  <span m="4570250">methods</span> <span m="4570760">and</span> <span m="4570870">then</span>
  <span m="4571030">the</span> <span m="4571170">probabilistic</span> <span m="4571740">and</span>
  <span m="4571840">optimization</span> <span m="4572318">function.</span></p><p><span
  m="4574710">If</span> <span m="4574920">you</span> <span m="4575080">have</span>
  <span m="4575480">specific</span> <span m="4575880">questions</span> <span m="4576580">or</span>
  <span m="4576820">topics</span> <span m="4577180">that</span> <span m="4577290">you</span>
  <span m="4577400">want</span> <span m="4577560">me</span> <span m="4577620">to</span>
  <span m="4577700">cover</span> <span m="4578640">in</span> <span m="4578810">more</span>
  <span m="4579000">detail</span> <span m="4579340">than</span> <span m="4579480">others,</span>
  <span m="4579830">then</span> <span m="4579970">either</span> <span m="4580690">bring</span>
  <span m="4580880">them to</span> <span m="4581100">class</span> <span m="4581440">or</span>
  <span m="4581520">you</span> <span m="4581610">can</span> <span m="4581710">e-mail</span>
  <span m="4581960">me</span> <span m="4582170">ahead of</span> <span m="4582300">time</span>
  <span m="4582650">so</span> <span m="4582780">that I</span> <span m="4583250">can</span>
  <span m="4583720">prepare</span> <span m="4583990">a</span> <span m="4584040">little</span>
  <span m="4584220">bit</span> <span m="4584360">more.</span> <span m="4586930">But</span>
  <span m="4587030">that</span> <span m="4587120">will</span> <span m="4587210">be</span>
  <span m="4587290">a</span> <span m="4587320">good</span> <span m="4587550">chance</span>
  <span m="4587880">to</span> <span m="4587980">ask</span> <span m="4588280">questions</span>
  <span m="4588650">about</span> <span m="4588850">things</span> <span m="4589070">that</span>
  <span m="4589160">are</span> <span m="4589200">confusing</span> <span m="4589580">before</span>
  <span m="4589810">the</span> <span m="4589900">final.</span> <span m="4591900">All</span>
  <span m="4592020">right.</span> <span m="4592630">See</span> <span m="4592920">everybody</span>
  <span m="4593220">on</span> <span m="4593820">Wednesday.</span></p>'
type: course
uid: 47ffea42d4f2e6dfdc2a41e8d4e19d81

---
None