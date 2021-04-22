---
about_this_resource_text: '<p><strong>Description:</strong> This session introduces
  finite volume methods in two dimensions and Eigenvalue stability, then reviews the
  advantages and disadvantages of the methods covered thus far in the course before
  the midterm exam.</p> <p><strong>Instructor:</strong> Qiqi Wang</p>  <p>The recording
  quality of this video is the best available from the source.</p><p>NOTE: Videos
  for the next two classes, Sessions 13&ndash;14, are not available.</p>'
course_id: 16-90-computational-methods-in-aerospace-engineering-spring-2014
embedded_media:
- id: Video-YouTube-Stream
  media_location: E9Wx6QaGyR0
  parent_uid: 02f302e0438775398792b31bbec42980
  title: Video-YouTube-Stream
  type: Video
  uid: bff37596232f3349b09dd122acc099a9
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/E9Wx6QaGyR0/default.jpg
  parent_uid: 02f302e0438775398792b31bbec42980
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: e58a0df06408ad759704d2eacb5fe615
- id: 3Play-3PlayYouTubeid-MP4
  media_location: E9Wx6QaGyR0
  parent_uid: 02f302e0438775398792b31bbec42980
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: ae864a7cf07dc0096fa521faf0f5a5df
- id: E9Wx6QaGyR0.srt
  parent_uid: 02f302e0438775398792b31bbec42980
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-12-numerical-methods-of-pdes-finite-volume-in-2d-and-midterm-review/E9Wx6QaGyR0.srt
  title: 3play caption file
  type: null
  uid: 8d17326e24a79b941c303fa00dcb16aa
- id: E9Wx6QaGyR0.pdf
  parent_uid: 02f302e0438775398792b31bbec42980
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-12-numerical-methods-of-pdes-finite-volume-in-2d-and-midterm-review/E9Wx6QaGyR0.pdf
  title: 3play pdf file
  type: null
  uid: b1c177c81737ac093ada1cafc4ab49fb
- id: Caption-3Play YouTube id-SRT
  parent_uid: 02f302e0438775398792b31bbec42980
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: c965ce00572c38809ed322b6dabd0257
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 02f302e0438775398792b31bbec42980
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 1f7c41283d52174731f279e49588ae5f
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT16.90S14/MIT16_90S14_L12_300k.mp4
  parent_uid: 02f302e0438775398792b31bbec42980
  title: Video-Internet Archive-MP4
  type: Video
  uid: fdf37aea824b2dafa9abf7a4c7ba14df
inline_embed_id: 11179131session12:numericalmethodsofpdes:finitevolumein2dandmidtermreview66025948
layout: video
order_index: null
parent_uid: 809ebf7c44bfb36e8786306747d7e32f
related_resources_text: ''
short_url: session-12-numerical-methods-of-pdes-finite-volume-in-2d-and-midterm-review
technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-12-numerical-methods-of-pdes-finite-volume-in-2d-and-midterm-review
template_type: Tabbed
title: 'Session 12: Numerical Methods of PDEs: Finite Volume in 2D and Midterm Review'
transcript: '<p><span m="30">The</span> <span m="130">following</span> <span m="600">content</span>
  <span m="1090">is</span> <span m="1200">provided</span> <span m="1660">under</span>
  <span m="1900">a</span> <span m="1950">Creative</span> <span m="2400">Commons</span>
  <span m="2820">license.</span> <span m="3770">Your</span> <span m="3880">support</span>
  <span m="4400">will</span> <span m="4570">help</span> <span m="4790">MIT</span>
  <span m="5280">OpenCourseWare</span> <span m="6020">continue</span> <span m="6510">to</span>
  <span m="6670">offer</span> <span m="6980">high</span> <span m="7200">quality</span>
  <span m="7680">educational</span> <span m="8350">resources</span> <span m="8920">for</span>
  <span m="9040">free.</span> <span m="10100">To</span> <span m="10130">make</span>
  <span m="10330">a</span> <span m="10380">donation</span> <span m="11090">or</span>
  <span m="11310">to</span> <span m="11430">view</span> <span m="11630">additional</span>
  <span m="12050">materials</span> <span m="12670">from</span> <span m="12850">hundreds</span>
  <span m="13180">of</span> <span m="13280">MIT</span> <span m="13650">courses,</span>
  <span m="14960">visit</span> <span m="15410">MIT</span> <span m="15670">OpenCourseWare</span>
  <span m="16580">at</span> <span m="16920">ocw.mit.edu.</span></p> <p><span m="25290">QIQI
  WANG:</span> <span m="25755">So</span> <span m="26220">today,</span> <span m="26870">I</span>
  <span m="27360">kind</span> <span m="27680">of</span> <span m="28100">prepared</span>
  <span m="28940">not</span> <span m="29390">for</span> <span m="29490">the</span>
  <span m="29620">whole</span> <span m="29900">lecture,</span> <span m="30500">but</span>
  <span m="30890">a</span> <span m="30970">little</span> <span m="31220">bit</span>
  <span m="31400">short</span> <span m="31700">of</span> <span m="31810">that.</span>
  <span m="32040">So</span> <span m="32540">I</span> <span m="32710">really</span>
  <span m="32960">expect</span> <span m="33215">you</span> <span m="33470">to</span>
  <span m="33580">ask</span> <span m="34090">questions</span> <span m="35326">on</span>
  <span m="36150">this</span> <span m="36360">material.</span> <span m="36780">It''s</span>
  <span m="36950">supposed</span> <span m="37310">to</span> <span m="37650">be</span>
  <span m="37830">a</span> <span m="37980">lecture</span> <span m="38390">that</span>
  <span m="38610">helps</span> <span m="38900">you</span> <span m="39070">review</span>
  <span m="41570">the</span> <span m="41660">material</span> <span m="42400">we</span>
  <span m="42670">have</span> <span m="42920">already</span> <span m="43450">covered</span>
  <span m="43760">and</span> <span m="43990">prepare you</span> <span m="44397">for
  the</span> <span m="44804">midterm.</span></p> <p><span m="45620">So</span> <span
  m="46230">instead</span> <span m="46670">of</span> <span m="47180">me</span> <span
  m="47520">just</span> <span m="47860">going</span> <span m="48570">mechanically</span>
  <span m="48970">through</span> <span m="49920">the</span> <span m="49990">material,</span>
  <span m="52030">I</span> <span m="52390">want</span> <span m="52540">to</span> <span
  m="52670">ask</span> <span m="52890">you</span> <span m="53080">to</span> <span
  m="53200">initiate</span> <span m="54990">what</span> <span m="55260">do you</span>
  <span m="55490">think</span> <span m="55730">is</span> <span m="57780">more</span>
  <span m="58010">confusing,</span> <span m="58800">or</span> <span m="59040">you''d</span>
  <span m="59360">like</span> <span m="60600">me to</span> <span m="61100">clarify</span>
  <span m="61610">again,</span> <span m="62620">and</span> <span m="62920">things</span>
  <span m="63020">like</span> <span m="63270">that.</span> <span m="64450">If</span>
  <span m="64610">you</span> <span m="64870">feel</span> <span m="65200">something</span>
  <span m="65580">is</span> <span m="66220">confusing,</span> <span m="66780">it''s</span>
  <span m="66980">probably</span> <span m="67560">confusing</span> <span m="67910">for</span>
  <span m="68020">the</span> <span m="68120">whole</span> <span m="68310">class.</span>
  <span m="68940">So</span> <span m="69860">please</span> <span m="70100">raise</span>
  <span m="70520">it</span> <span m="70940">so</span> <span m="71360">that</span>
  <span m="71780">I can</span> <span m="71930">spend</span> <span m="72180">more</span>
  <span m="72635">time on it.</span></p> <p><span m="74000">OK,</span> <span m="74940">so</span>
  <span m="76010">before</span> <span m="76930">I do</span> <span m="77130">that,</span>
  <span m="77980">I</span> <span m="78160">just</span> <span m="78690">first want
  to</span> <span m="78890">finish</span> <span m="80220">up the</span> <span m="80710">finite</span>
  <span m="81360">volume</span> <span m="81760">scheme</span> <span m="82800">we</span>
  <span m="82900">have</span> <span m="83040">been</span> <span m="83190">working</span>
  <span m="83560">on</span> <span m="83690">for</span> <span m="83840">the</span>
  <span m="83930">last</span> <span m="84240">two</span> <span m="84623">lectures.</span>
  <span m="85670">We</span> <span m="85770">have</span> <span m="85780">been</span>
  <span m="85920">discussing</span> <span m="86890">finite</span> <span m="87080">volume</span>
  <span m="87570">schemes</span> <span m="87930">in</span> <span m="88210">one</span>
  <span m="88460">dimension.</span> <span m="90700">But</span> <span m="90960">applying</span>
  <span m="91340">the</span> <span m="91440">same</span> <span m="91760">concept</span>
  <span m="92240">to</span> <span m="93020">two</span> <span m="93210">dimensions</span>
  <span m="93820">or</span> <span m="93940">even</span> <span m="94170">three</span>
  <span m="94440">dimensional</span> <span m="95220">is</span> <span m="96780">surprisingly</span>
  <span m="97600">straightforward.</span> <span m="98900">So</span> <span m="99260">let</span>
  <span m="100080">me</span> <span m="100200">first</span> <span m="101740">give</span>
  <span m="101950">out</span> <span m="102240">what</span> <span m="102560">we</span>
  <span m="102790">did in</span> <span m="103060">1D.</span></p> <p><span m="104160">We</span>
  <span m="104370">started</span> <span m="104970">out</span> <span m="106310">in</span>
  <span m="106500">finite</span> <span m="106870">volume</span> <span m="107263">schemes--</span>
  <span m="108050">we</span> <span m="108240">started</span> <span m="108690">out</span>
  <span m="109090">with</span> <span m="110725">the</span> <span m="111120">integral</span>
  <span m="111750">form</span> <span m="112070">of</span> <span m="112210">the</span>
  <span m="112300">differential</span> <span m="112820">equation.</span> <span m="113450">We</span>
  <span m="113700">started</span> <span m="114090">out</span> <span m="114360">with</span>
  <span m="114800">d dt</span> <span m="116070">of</span> <span m="116370">the</span>
  <span m="116480">integral</span> <span m="118370">of</span> <span m="118850">a</span>
  <span m="118970">conserved</span> <span m="119670">quantity</span> <span m="121430">inside</span>
  <span m="121910">a</span> <span m="121950">control</span> <span m="122350">volume,</span>
  <span m="122840">omega,</span> <span m="125650">it</span> <span m="125760">is</span>
  <span m="126030">equal</span> <span m="126530">to</span> <span m="127810">minus</span>
  <span m="128680">of</span> <span m="129669">the</span> <span m="129830">flux</span>
  <span m="131290">out</span> <span m="131530">of</span> <span m="131640">the</span>
  <span m="131720">control</span> <span m="132270">volume.</span> <span m="132740">The</span>
  <span m="132840">minus</span> <span m="133220">sign is</span> <span m="133550">because</span>
  <span m="134430">the</span> <span m="134570">time</span> <span m="134840">derivative</span>
  <span m="135400">is</span> <span m="135900">really</span> <span m="136360">the</span>
  <span m="137050">flux</span> <span m="137420">into</span> <span m="137720">the</span>
  <span m="137980">control</span> <span m="138450">volume.</span> <span m="138920">But</span>
  <span m="139160">the</span> <span m="139760">definition</span> <span m="140460">of</span>
  <span m="140730">our</span> <span m="141690">n,</span> <span m="142110">normally,</span>
  <span m="142630">is</span> <span m="142800">usually</span> <span m="143640">out</span>
  <span m="143830">of</span> <span m="143930">the</span> <span m="144000">control</span>
  <span m="144340">volume.</span> <span m="144830">So</span> <span m="145030">we</span>
  <span m="145240">have</span> <span m="145370">a</span> <span m="145440">minus</span>
  <span m="145830">sign</span> <span m="146570">to</span> <span m="146770">reverse</span>
  <span m="147810">the</span> <span m="147940">normal</span> <span m="148420">so</span>
  <span m="148570">that</span> <span m="148770">it</span> <span m="148920">points</span>
  <span m="151150">into</span> <span m="151490">the</span> <span m="151580">control</span>
  <span m="151910">volume.</span></p> <p><span m="153550">Times the</span> <span m="153630">flux</span>
  <span m="154100">as</span> <span m="154200">a</span> <span m="154270">function</span>
  <span m="154570">of</span> <span m="154700">rho,</span> <span m="155680">ds.</span>
  <span m="156570">So</span> <span m="156780">this</span> <span m="157030">is</span>
  <span m="157260">like</span> <span m="160030">the</span> <span m="160940">integral</span>
  <span m="161460">form</span> <span m="161820">of</span> <span m="161960">the</span>
  <span m="162040">conservation law,</span> <span m="163210">right?</span> <span m="164070">And</span>
  <span m="164370">I</span> <span m="165070">can</span> <span m="165300">write</span>
  <span m="165890">the</span> <span m="166050">same</span> <span m="166340">thing</span>
  <span m="166670">in</span> <span m="167000">1D</span> <span m="167270">that</span>
  <span m="167450">is</span> <span m="168620">the</span> <span m="168890">specific</span>
  <span m="169480">case</span> <span m="170100">of</span> <span m="170880">omega</span>
  <span m="171920">being just</span> <span m="172040">an</span> <span m="172120">interval.</span>
  <span m="174890">Now,</span> <span m="175170">this</span> <span m="175500">is</span>
  <span m="175720">the</span> <span m="175970">flux</span> <span m="176840">at</span>
  <span m="177330">the</span> <span m="177540">left</span> <span m="178930">minus</span>
  <span m="179927">flux</span> <span m="181060">at the</span> <span m="181250">right.</span>
  <span m="182480">Or it''s</span> <span m="182860">really</span> <span m="183280">rho</span>
  <span m="183585">at</span> <span m="183890">left</span> <span m="184350">and</span>
  <span m="184810">rho</span> <span m="185310">at</span> <span m="185540">right.</span></p>
  <p><span m="187230">Right,</span> <span m="187550">so</span> <span m="187870">in</span>
  <span m="188060">1D,</span> <span m="188810">what</span> <span m="189220">we</span>
  <span m="189400">did</span> <span m="189730">was</span> <span m="191700">we</span>
  <span m="191880">set</span> <span m="192420">rho bar</span> <span m="193080">of</span>
  <span m="193280">k</span> <span m="193780">is</span> <span m="194080">equal</span>
  <span m="194640">to</span> <span m="195960">the</span> <span m="196120">size</span>
  <span m="196650">of</span> <span m="196900">the</span> <span m="196980">control</span>
  <span m="197400">volume</span> <span m="198430">of</span> <span m="198600">k.</span>
  <span m="200884">So</span> <span m="201340">it''s</span> <span m="201540">the</span>
  <span m="201670">integral</span> <span m="204030">of</span> <span m="204270">the</span>
  <span m="204350">control</span> <span m="204790">volume</span> <span m="206130">divided</span>
  <span m="206610">by</span> <span m="206810">the</span> <span m="206870">size</span>
  <span m="207440">of</span> <span m="207590">the</span> <span m="207670">control</span>
  <span m="208340">volume.</span> <span m="209190">And</span> <span m="210320">basically,</span>
  <span m="210770">by</span> <span m="211130">plugging</span> <span m="211840">in</span>
  <span m="212560">the</span> <span m="212710">definition</span> <span m="213790">into</span>
  <span m="215170">the</span> <span m="215300">integral</span> <span m="215860">form</span>
  <span m="216250">of</span> <span m="216410">the</span> <span m="216500">conversation</span>
  <span m="217060">law,</span> <span m="217670">what</span> <span m="217860">we</span>
  <span m="218000">get</span> <span m="218310">is</span> <span m="218840">1</span>
  <span m="219180">over</span> <span m="219400">the</span> <span m="219520">size</span>
  <span m="219800">of</span> <span m="219900">the</span> <span m="219980">control</span>
  <span m="220530">volume,</span> <span m="221240">the</span> <span m="221390">flux</span>
  <span m="222670">at</span> <span m="224630">the</span> <span m="225040">left</span>
  <span m="225450">side</span> <span m="225710">of</span> <span m="225810">the</span>
  <span m="225890">control</span> <span m="226430">volume--</span> <span m="227590">I''m</span>
  <span m="227780">just</span> <span m="227950">going</span> <span m="228070">to</span>
  <span m="228180">say</span> <span m="229400">F</span> <span m="229730">of</span>
  <span m="230030">k</span> <span m="230640">minus</span> <span m="231140">1/2</span>
  <span m="232000">minus</span> <span m="232280">F of k plus</span> <span m="232560">1/2.</span>
  <span m="234560">That</span> <span m="234850">is</span> <span m="235050">what</span>
  <span m="235260">we</span> <span m="235470">use</span> <span m="235790">to</span>
  <span m="235960">denote</span> <span m="237490">the</span> <span m="237650">flux</span>
  <span m="237980">at</span> <span m="238260">the</span> <span m="238360">cell</span>
  <span m="238460">interfaces.</span></p> <p><span m="240810">Now,</span> <span m="241020">let''s</span>
  <span m="241260">go</span> <span m="241450">back</span> <span m="241930">to</span>
  <span m="242300">2D,</span> <span m="242790">or</span> <span m="243030">the</span>
  <span m="243110">multi-dimensional</span> <span m="244110">form</span> <span m="244420">of</span>
  <span m="244760">the</span> <span m="244890">conservation</span> <span m="245240">law.</span>
  <span m="246520">We''re</span> <span m="246860">going to</span> <span m="246990">define</span>
  <span m="247790">rho bar</span> <span m="249190">of a</span> <span m="249550">control</span>
  <span m="250040">volume,</span> <span m="250380">k,</span> <span m="251440">being</span>
  <span m="251730">the</span> <span m="251830">same</span> <span m="252170">thing.</span>
  <span m="252720">It</span> <span m="252850">is</span> <span m="253190">really</span>
  <span m="254320">the</span> <span m="254400">integral</span> <span m="255120">over</span>
  <span m="255590">the</span> <span m="255840">k-th</span> <span m="256149">control</span>
  <span m="256504">volume,</span> <span m="257649">rho</span> <span m="258310">dx,</span>
  <span m="259470">divided</span> <span m="260160">by--</span> <span m="260620">in</span>
  <span m="261089">2D,</span> <span m="261750">that</span> <span m="261980">is</span>
  <span m="262130">the</span> <span m="262330">area</span> <span m="262745">of</span>
  <span m="263160">that</span> <span m="263642">control</span> <span m="264124">volume.</span>
  <span m="267020">All right,</span> <span m="267260">let</span> <span m="267390">me</span>
  <span m="267520">draw</span> <span m="269630">a</span> <span m="269770">typical</span>
  <span m="270670">mesh</span> <span m="272860">in</span> <span m="273070">two</span>
  <span m="273280">dimensions.</span></p> <p><span m="275500">So</span> <span m="275680">let''s</span>
  <span m="275900">say</span> <span m="276050">this</span> <span m="276340">is</span>
  <span m="277200">a</span> <span m="277230">triangular</span> <span m="277810">mesh</span>
  <span m="278240">in</span> <span m="278420">2D.</span> <span m="279250">And</span>
  <span m="279540">this</span> <span m="279840">is</span> <span m="280090">like</span>
  <span m="280350">the</span> <span m="280440">k-th</span> <span m="280700">control
  volume.</span> <span m="282900">Right,</span> <span m="283250">for</span> <span
  m="283340">example,</span> <span m="283700">this</span> <span m="283910">is</span>
  <span m="284700">part</span> <span m="284930">of</span> <span m="285330">a</span>
  <span m="285410">mesh</span> <span m="286220">in</span> <span m="286410">two</span>
  <span m="286580">dimensions.</span> <span m="288850">Right?</span> <span m="289690">And</span>
  <span m="291640">we</span> <span m="291970">are</span> <span m="292190">computing--</span>
  <span m="293040">we</span> <span m="293200">found</span> <span m="293420">the</span>
  <span m="293510">volume</span> <span m="293670">scheme.</span> <span m="294160">We</span>
  <span m="294380">are</span> <span m="294550">tracking</span> <span m="295320">the</span>
  <span m="295590">average</span> <span m="297450">of</span> <span m="297670">the</span>
  <span m="297780">solution</span> <span m="298270">inside</span> <span m="298710">that</span>
  <span m="299050">control volume.</span></p> <p><span m="303060">So</span> <span
  m="303690">this</span> <span m="304160">is</span> <span m="304340">my</span> <span
  m="304630">omega</span> <span m="305130">k.</span> <span m="305570">That''s</span>
  <span m="305910">the</span> <span m="306020">control volume.</span> <span m="306970">And</span>
  <span m="307160">the</span> <span m="307230">area</span> <span m="307860">of</span>
  <span m="308050">that</span> <span m="309075">control volume</span> <span m="309530">is</span>
  <span m="309640">my</span> <span m="309810">Ak.</span> <span m="311350">And</span>
  <span m="311600">rho bar</span> <span m="312050">of</span> <span m="312430">k</span>
  <span m="312810">is</span> <span m="313190">the cell</span> <span m="313430">average</span>
  <span m="313930">there.</span> <span m="315140">So</span> <span m="315350">what</span>
  <span m="315620">is</span> <span m="315820">the</span> <span m="315910">time</span>
  <span m="316320">derivative</span> <span m="317640">of</span> <span m="318010">that</span>
  <span m="318310">cell</span> <span m="318530">average</span> <span m="318790">value?</span>
  <span m="321420">Because</span> <span m="321780">the</span> <span m="321850">area</span>
  <span m="322650">of</span> <span m="322850">the</span> <span m="322920">control</span>
  <span m="323410">volume</span> <span m="323710">does not</span> <span m="323900">change.</span>
  <span m="324850">It</span> <span m="324930">is</span> <span m="325540">equal</span>
  <span m="325990">to</span> <span m="326180">1</span> <span m="326490">over</span>
  <span m="326730">the</span> <span m="326810">area</span> <span m="328250">times</span>
  <span m="328710">the</span> <span m="328830">time</span> <span m="329390">derivative</span>
  <span m="330900">of</span> <span m="331160">the</span> <span m="331270">volume</span>
  <span m="331860">integral,</span> <span m="334660">right?</span></p> <p><span m="336080">And</span>
  <span m="336250">the</span> <span m="336340">time</span> <span m="336660">derivative</span>
  <span m="337220">of</span> <span m="337350">the</span> <span m="337420">volume</span>
  <span m="337810">integral,</span> <span m="340364">by</span> <span m="340850">the</span>
  <span m="341440">integral</span> <span m="341720">form</span> <span m="341940">of</span>
  <span m="342010">the</span> <span m="342090">conservation</span> <span m="342650">law,</span>
  <span m="343810">which</span> <span m="344010">you</span> <span m="344080">can</span>
  <span m="344290">get</span> <span m="344780">by</span> <span m="345160">applying</span>
  <span m="345540">divergence</span> <span m="346300">theorem,</span> <span m="347110">right?</span>
  <span m="347390">We</span> <span m="347550">did</span> <span m="347860">that last</span>
  <span m="348170">lecture</span> <span m="348560">by</span> <span m="348720">applying</span>
  <span m="349020">divergence</span> <span m="349500">theorem</span> <span m="349870">to</span>
  <span m="350020">the</span> <span m="350560">differential</span> <span m="351160">form</span>
  <span m="351420">of</span> <span m="351550">the</span> <span m="351770">equation</span>
  <span m="352820">to</span> <span m="352940">get</span> <span m="353250">this</span>
  <span m="354730">integral</span> <span m="355210">form.</span> <span m="355950">And</span>
  <span m="356400">just by</span> <span m="356740">plugging</span> <span m="357165">in,</span>
  <span m="357590">we</span> <span m="357910">get</span> <span m="359080">1</span>
  <span m="359490">over</span> <span m="359880">Ak</span> <span m="361320">times</span>
  <span m="362310">the</span> <span m="362500">integral</span> <span m="363260">over</span>
  <span m="365130">the</span> <span m="365310">boundary</span> <span m="366070">of</span>
  <span m="366250">the</span> <span m="366330">control</span> <span m="366760">volume.</span>
  <span m="368780">We</span> <span m="368940">get</span> <span m="369110">a</span>
  <span m="369160">minus</span> <span m="369540">sign</span> <span m="369820">here.</span>
  <span m="370200">And</span> <span m="370570">the</span> <span m="370980">outward</span>
  <span m="371390">normal</span> <span m="372550">dotted</span> <span m="372940">with</span>
  <span m="373360">the</span> <span m="373440">flux,</span> <span m="376010">ds.</span></p>
  <p><span m="376970">Now,</span> <span m="377170">let''s</span> <span m="377420">look</span>
  <span m="377690">at</span> <span m="377960">what</span> <span m="378170">this</span>
  <span m="378500">is</span> <span m="380420">on</span> <span m="380560">the</span>
  <span m="380630">control volume.</span> <span m="382710">So we found</span> <span
  m="383190">the</span> <span m="383670">integral</span> <span m="384020">over the</span>
  <span m="384400">boundary</span> <span m="384810">of the volume.</span> <span m="385562">If
  the control</span> <span m="385940">volume</span> <span m="386560">is this</span>
  <span m="386790">angle,</span> <span m="387784">what are</span> <span m="388281">the</span>
  <span m="388780">boundaries?</span> <span m="392712">We have</span> <span m="393410">[INAUDIBLE],</span>
  <span m="395370">right?</span></p> <p><span m="397110">Now,</span> <span m="397350">we</span>
  <span m="397550">can</span> <span m="397730">express</span> <span m="398350">that</span>
  <span m="399050">as</span> <span m="401170">minus</span> <span m="401640">1</span>
  <span m="401920">over</span> <span m="402020">Ak</span> <span m="402470">of</span>
  <span m="402840">summation</span> <span m="404560">of</span> <span m="406030">ni</span>
  <span m="408995">dotted with</span> <span m="409620">Fi</span> <span m="412720">times</span>
  <span m="414000">the</span> <span m="414490">length</span> <span m="416770">of</span>
  <span m="417110">each</span> <span m="417350">of</span> <span m="417470">the</span>
  <span m="417580">sides.</span> <span m="418780">So</span> <span m="419060">i</span>
  <span m="420090">is,</span> <span m="421700">I''m</span> <span m="421880">going</span>
  <span m="422010">to</span> <span m="422110">say,</span> <span m="422470">like</span>
  <span m="422770">the</span> <span m="422990">sides</span> <span m="425710">of</span>
  <span m="426100">k.</span> <span m="426680">So</span> <span m="426960">Sk</span>
  <span m="428115">is</span> <span m="428500">the</span> <span m="428660">sides,</span>
  <span m="429540">the</span> <span m="429840">three</span> <span m="430230">sides</span>
  <span m="430583">of</span> <span m="430936">the</span> <span m="431590">triangle,</span>
  <span m="433330">all</span> <span m="433650">the</span> <span m="433980">boundaries</span>
  <span m="434290">of</span> <span m="434660">this</span> <span m="435810">triangle,</span>
  <span m="436080">k.</span> <span m="437360">So</span> <span m="437510">Sk</span>
  <span m="438640">is</span> <span m="439000">a</span> <span m="439330">set</span>
  <span m="439758">of</span> <span m="440186">these</span> <span m="440614">integrals</span>
  <span m="441470">that</span> <span m="441730">gives</span> <span m="442163">you</span>
  <span m="442596">these</span> <span m="443340">three</span> <span m="443837">boundaries.</span></p>
  <p><span m="445330">And</span> <span m="445560">the</span> <span m="445840">i</span>
  <span m="447331">the</span> <span m="449320">normal</span> <span m="450050">of</span>
  <span m="450340">each</span> <span m="450630">edge.</span> <span m="451980">So for</span>
  <span m="452210">example,</span> <span m="453186">in this</span> <span m="453674">direction,</span>
  <span m="454650">so</span> <span m="456250">this</span> <span m="456530">is</span>
  <span m="456810">the</span> <span m="457160">ni''s</span> <span m="459540">pointing
  in this</span> <span m="460016">direction.</span> <span m="460968">These are the</span>
  <span m="461444">ni''s.</span> <span m="462880">And</span> <span m="463100">the</span>
  <span m="463270">graph,</span> <span m="464206">the</span> <span m="464674">Fi</span>
  <span m="465142">is</span> <span m="465610">the</span> <span m="466078">flux</span>
  <span m="466546">on these edges,</span> <span m="469060">which</span> <span m="469300">we</span>
  <span m="469430">have</span> <span m="469630">gone</span> <span m="469800">through,</span>
  <span m="469950">again,</span> <span m="470510">approximately,</span> <span m="471210">that</span>
  <span m="472074">by</span> <span m="472290">applying</span> <span m="472506">the</span>
  <span m="472722">graph</span> <span m="472938">function</span> <span m="474525">of</span>
  <span m="474990">these</span> <span m="475240">two</span> <span m="475721">neighboring</span>
  <span m="476202">cells.</span></p> <p><span m="479088">It''s</span> <span m="479570">the</span>
  <span m="479660">same</span> <span m="479900">thing</span> <span m="480040">as</span>
  <span m="480190">we</span> <span m="480330">did</span> <span m="480540">in</span>
  <span m="480840">1D.</span> <span m="481190">In</span> <span m="481540">1D,</span>
  <span m="482020">we approximate</span> <span m="482665">the</span> <span m="483110">flux</span>
  <span m="484120">at</span> <span m="484320">the</span> <span m="484390">cell</span>
  <span m="484750">interface</span> <span m="485870">by</span> <span m="486030">looking</span>
  <span m="486510">at</span> <span m="486890">the</span> <span m="487000">value</span>
  <span m="487600">of</span> <span m="487710">the</span> <span m="488203">function</span>
  <span m="488696">at</span> <span m="489190">the</span> <span m="489270">neighboring</span>
  <span m="489690">two cells.</span> <span m="490576">In 2D,</span> <span m="491019">it''s
  the same</span> <span m="491462">thing.</span> <span m="492348">We</span> <span
  m="492791">approximate</span> <span m="493240">the</span> <span m="493690">flux</span>
  <span m="494200">of</span> <span m="494580">the</span> <span m="495230">cell interfaces,</span>
  <span m="496380">so</span> <span m="497090">yield</span> <span m="497490">between</span>
  <span m="497870">two</span> <span m="498190">cells,</span> <span m="498910">by</span>
  <span m="499100">looking</span> <span m="499530">at</span> <span m="499980">the</span>
  <span m="500462">flux,</span> <span m="500944">by</span> <span m="501426">looking
  at the</span> <span m="501908">solution of the cell averages</span> <span m="503354">over</span>
  <span m="503836">the different sides.</span></p> <p><span m="506250">If</span> <span
  m="506440">we</span> <span m="506550">have</span> <span m="506750">to</span> <span
  m="506860">do</span> <span m="507040">[INAUDIBLE],</span> <span m="508150">we</span>
  <span m="508290">do</span> <span m="508460">[INAUDIBLE].</span> <span m="509450">We
  look at</span> <span m="510200">which</span> <span m="510610">direction</span> <span
  m="510740">is</span> <span m="511010">the</span> <span m="512015">[INAUDIBLE]</span>
  <span m="513460">over</span> <span m="513750">this edge.</span> <span m="514420">Is
  it</span> <span m="514890">from</span> <span m="515360">this side</span> <span m="515669">or</span>
  <span m="515799">this</span> <span m="516224">side?</span> <span m="517500">And</span>
  <span m="518049">choose</span> <span m="519120">the</span> <span m="519360">value</span>
  <span m="519740">on</span> <span m="520049">either</span> <span m="520510">side</span>
  <span m="521100">of</span> <span m="521299">this</span> <span m="521470">edge.</span>
  <span m="524780">If we go to</span> <span m="525020">three</span> <span m="525400">dimensions,</span>
  <span m="526050">it''s</span> <span m="526180">the</span> <span m="526620">same.</span>
  <span m="527180">Instead</span> <span m="527390">of</span> <span m="527780">edges,</span>
  <span m="529100">we</span> <span m="529260">have</span> <span m="529530">spaces</span>
  <span m="531080">between</span> <span m="531230">control volumes.</span> <span m="534212">That
  is the</span> <span m="534679">case</span> <span m="535150">where we really</span>
  <span m="535590">become</span> <span m="535720">looking</span> <span m="536220">at</span>
  <span m="536720">interfaces,</span> <span m="537720">interfaces</span> <span m="538220">at</span>
  <span m="538720">each place</span> <span m="540220">in three</span> <span m="540720">dimensions</span>
  <span m="541842">instead</span> <span m="542278">of</span> <span m="542714">an</span>
  <span m="543150">edge in 2D</span> <span m="543590">or</span> <span m="543840">a</span>
  <span m="544310">[INAUDIBLE].</span> <span m="547080">Now,</span> <span m="549130">we</span>
  <span m="549380">approximate</span> <span m="554306">using a</span> <span m="554652">numerical</span>
  <span m="555000">flux</span> <span m="555940">that</span> <span m="556140">is</span>
  <span m="557240">rho bar</span> <span m="558020">of</span> <span m="558325">k,</span>
  <span m="559525">rho bar</span> <span m="560216">of--</span> <span m="561200">I''m</span>
  <span m="561310">just</span> <span m="561370">going</span> <span m="561550">to</span>
  <span m="561610">say</span> <span m="561980">neighbor.</span> <span m="565330">And</span>
  <span m="565500">then,</span> <span m="565660">we''re</span> <span m="565870">done,</span>
  <span m="566613">right?</span> <span m="568013">We</span> <span m="568356">have</span>
  <span m="568960">approximated</span> <span m="570361">the</span> <span m="570740">time</span>
  <span m="571060">derivative.</span></p> <p><span m="571140">So you</span> <span
  m="571470">know the</span> <span m="571940">[INAUDIBLE]</span> <span m="572880">of</span>
  <span m="573350">the</span> <span m="573820">cell</span> <span m="574110">average</span>
  <span m="574576">in the</span> <span m="575042">cell</span> <span m="575508">k.</span>
  <span m="576440">And</span> <span m="576830">the</span> <span m="577030">function</span>
  <span m="577476">of</span> <span m="577922">the</span> <span m="578368">cell</span>
  <span m="578814">average</span> <span m="580110">in</span> <span m="580410">k</span>
  <span m="580745">and</span> <span m="581080">the</span> <span m="581335">cell</span>
  <span m="581810">average</span> <span m="583200">in</span> <span m="583390">the</span>
  <span m="583590">neighbors</span> <span m="583990">of</span> <span m="584486">the</span>
  <span m="584982">k-th</span> <span m="585480">control volume.</span> <span m="588920">[INAUDIBLE]</span>
  <span m="589230">other</span> <span m="589460">point</span> <span m="589690">is</span>
  <span m="589930">the</span> <span m="590010">area,</span> <span m="590680">just</span>
  <span m="591060">like</span> <span m="591440">normal,</span> <span m="592479">the</span>
  <span m="592958">length</span> <span m="593437">of</span> <span m="593916">the</span>
  <span m="594395">k-th</span> <span m="594874">[INAUDIBLE],</span> <span m="595353">the</span>
  <span m="595832">n-th</span> <span m="596311">normal in this space.</span> <span
  m="597748">And</span> <span m="598227">the</span> <span m="598706">length</span>
  <span m="599185">of the</span> <span m="599670">Ses</span> <span m="599940">are</span>
  <span m="600210">all known</span> <span m="600480">quantities</span> <span m="601310">from</span>
  <span m="601810">the</span> <span m="602310">mesh.</span></p> <p><span m="603310">So
  this is</span> <span m="603810">[INAUDIBLE]</span> <span m="604310">flux,</span>
  <span m="604810">a</span> <span m="605310">function of</span> <span m="605810">the</span>
  <span m="606310">cell</span> <span m="606738">averages.</span> <span m="608880">So</span>
  <span m="609020">essentially,</span> <span m="609540">we</span> <span m="609720">have</span>
  <span m="609990">turned</span> <span m="610680">a</span> <span m="611160">PDE</span>
  <span m="611420">into an</span> <span m="611590">ODE.</span> <span m="619850">What</span>
  <span m="620080">is</span> <span m="620230">that</span> <span m="620573">ODE?</span>
  <span m="621260">That</span> <span m="621730">ODE</span> <span m="622460">is</span>
  <span m="622940">d dt</span> <span m="624290">of</span> <span m="624940">rho bar</span>
  <span m="625300">1,</span> <span m="626440">rho bar</span> <span m="626775">2,</span>
  <span m="627720">et cetera,</span> <span m="628320">to</span> <span m="628560">rho
  bar</span> <span m="629840">of</span> <span m="630840">the</span> <span m="631020">last</span>
  <span m="631450">control</span> <span m="631940">volume</span> <span m="633160">is</span>
  <span m="633500">equal</span> <span m="633960">to</span> <span m="634950">some</span>
  <span m="635560">joint</span> <span m="635990">function</span> <span m="637600">of
  all</span> <span m="637940">these</span> <span m="638150">rho bars.</span> <span
  m="642420">OK,</span> <span m="644440">so this</span> <span m="644932">n</span>
  <span m="645424">is</span> <span m="645916">the</span> <span m="646408">function</span>
  <span m="646900">that</span> <span m="647392">connects</span> <span m="648376">the</span>
  <span m="648868">time</span> <span m="649360">derivative</span> <span m="650344">of</span>
  <span m="650836">one</span> <span m="651328">cell</span> <span m="651830">average</span>
  <span m="653884">to</span> <span m="654335">the</span> <span m="654790">value</span>
  <span m="655160">of</span> <span m="655645">a</span> <span m="656130">cell average</span>
  <span m="656615">of</span> <span m="657100">that</span> <span m="657585">control
  volume</span> <span m="658070">and</span> <span m="658560">its</span> <span m="658700">neighboring</span>
  <span m="659250">control volume.</span></p> <p><span m="664150">Is it clear?</span>
  <span m="665090">How</span> <span m="665560">we</span> <span m="665810">do</span>
  <span m="665970">the</span> <span m="666070">same</span> <span m="666320">thing</span>
  <span m="666600">in</span> <span m="667050">2D?</span> <span m="669050">There</span>
  <span m="669310">is</span> <span m="669490">a</span> <span m="669590">lot--</span>
  <span m="670730">there</span> <span m="670960">is</span> <span m="671090">going</span>
  <span m="671210">to</span> <span m="671270">be</span> <span m="671350">a</span>
  <span m="671420">lot</span> <span m="671660">of</span> <span m="671810">bookkeeping</span>
  <span m="672420">just</span> <span m="672800">because</span> <span m="673220">of</span>
  <span m="673870">the</span> <span m="673970">mesh</span> <span m="674590">and</span>
  <span m="675150">for</span> <span m="675530">every</span> <span m="675980">cell,</span>
  <span m="676440">we</span> <span m="676580">need</span> <span m="676750">to</span>
  <span m="676860">be</span> <span m="676970">able</span> <span m="677220">to</span>
  <span m="677460">find</span> <span m="677840">its</span> <span m="678080">neighboring</span>
  <span m="678570">cells,</span> <span m="679190">and</span> <span m="679640">find</span>
  <span m="679970">which</span> <span m="680460">edge</span> <span m="681210">is</span>
  <span m="681470">connected</span> <span m="682050">to</span> <span m="682370">which</span>
  <span m="682695">cell,</span> <span m="683975">and</span> <span m="684460">who is</span>
  <span m="684945">whose</span> <span m="685430">neighbor.</span> <span m="686885">Conceptually,</span>
  <span m="687370">this</span> <span m="687560">is</span> <span m="688550">exactly</span>
  <span m="689100">what</span> <span m="689280">we</span> <span m="689470">do.</span></p>
  <p><span m="693000">OK,</span> <span m="693740">so</span> <span m="693980">we</span>
  <span m="694290">have</span> <span m="694470">started</span> <span m="694840">finding
  the</span> <span m="695270">difference,</span> <span m="695750">finding the</span>
  <span m="696130">volume,</span> <span m="696590">and</span> <span m="696930">all</span>
  <span m="697170">these</span> <span m="697380">methods</span> <span m="699550">are</span>
  <span m="700060">methods</span> <span m="700690">that</span> <span m="700900">are</span>
  <span m="701010">intended</span> <span m="701915">to turn a</span> <span m="702390">partial</span>
  <span m="702590">differential</span> <span m="703010">equation</span> <span m="703420">into</span>
  <span m="704150">an</span> <span m="704630">enormous</span> <span m="705850">ordinary</span>
  <span m="706420">differential</span> <span m="706880">equation,</span> <span m="707460">right?</span>
  <span m="709730">And</span> <span m="709950">once</span> <span m="710220">we</span>
  <span m="710480">turn a</span> <span m="710810">PDE</span> <span m="711195">into</span>
  <span m="711780">an</span> <span m="712140">ODE,</span> <span m="712485">we can</span>
  <span m="712830">apply</span> <span m="713770">exactly what</span> <span m="714030">we</span>
  <span m="714150">have</span> <span m="714300">been</span> <span m="714500">doing</span>
  <span m="714980">in</span> <span m="715420">ODEs</span> <span m="716250">to</span>
  <span m="716390">study</span> <span m="716830">these</span> <span m="717030">PDEs,</span>
  <span m="717410">to</span> <span m="717510">discretize,</span> <span m="718780">solve,</span>
  <span m="719540">and</span> <span m="719800">study</span> <span m="720160">the</span>
  <span m="720270">behavior</span> <span m="720700">of these</span> <span m="721130">PDEs.</span></p>
  <p><span m="723280">OK,</span> <span m="723530">so</span> <span m="723710">this</span>
  <span m="723940">is</span> <span m="724720">going</span> <span m="725040">back</span>
  <span m="725240">to</span> <span m="725330">the</span> <span m="725510">review</span>
  <span m="725940">part.</span> <span m="727090">I''m</span> <span m="727350">going</span>
  <span m="727560">to</span> <span m="728770">really</span> <span m="730040">both</span>
  <span m="730420">the</span> <span m="730580">rule</span> <span m="730950">of the</span>
  <span m="731050">mesh</span> <span m="731330">and the</span> <span m="731610">outcomes</span>
  <span m="733240">and</span> <span m="733860">put</span> <span m="734350">particular</span>
  <span m="735100">emphasis</span> <span m="736070">on</span> <span m="736430">several
  of the</span> <span m="736820">points.</span> <span m="738860">The</span> <span
  m="738880">first</span> <span m="739150">point</span> <span m="739410">is</span>
  <span m="739690">order</span> <span m="739850">of</span> <span m="740190">accuracy.</span>
  <span m="741880">So</span> <span m="741960">the</span> <span m="742060">order</span>
  <span m="742280">of</span> <span m="742440">accuracy</span> <span m="743190">in</span>
  <span m="743330">an</span> <span m="743390">ODE</span> <span m="743830">scheme</span>
  <span m="746770">is</span> <span m="747270">found</span> <span m="747510">by</span>
  <span m="747670">looking</span> <span m="748430">at</span> <span m="749250">the</span>
  <span m="749430">equation,</span> <span m="749710">du dt</span> <span m="749990">equal</span>
  <span m="750386">to</span> <span m="750782">f</span> <span m="751180">of</span>
  <span m="751340">u.</span> <span m="755840">And</span> <span m="756210">we</span>
  <span m="756340">discretize</span> <span m="757730">this</span> <span m="758160">into</span>
  <span m="759650">some</span> <span m="760100">operator.</span> <span m="761670">We</span>
  <span m="761860">discretize</span> <span m="762410">the</span> <span m="762520">d
  dt</span> <span m="763250">into</span> <span m="763520">a</span> <span m="763590">finite</span>
  <span m="764190">difference</span> <span m="764580">using</span> <span m="764970">a
  finite</span> <span m="765200">difference</span> <span m="765560">operator.</span></p>
  <p><span m="768620">So</span> <span m="769500">we</span> <span m="769910">discretize</span>
  <span m="770910">the</span> <span m="771100">d dt</span> <span m="771880">into</span>
  <span m="772190">some</span> <span m="772410">kind</span> <span m="772590">of</span>
  <span m="772730">a</span> <span m="773010">delta</span> <span m="773710">over</span>
  <span m="774060">delta t.</span> <span m="774750">I</span> <span m="774850">mean,</span>
  <span m="775100">this</span> <span m="775340">is</span> <span m="775560">going</span>
  <span m="775710">to</span> <span m="775780">be</span> <span m="776730">finite difference</span>
  <span m="777300">operator,</span> <span m="779130">operating</span> <span m="779770">on</span>
  <span m="779920">the</span> <span m="779990">u.</span> <span m="781080">Now,</span>
  <span m="781490">this</span> <span m="781850">is</span> <span m="782140">not</span>
  <span m="782410">going</span> <span m="782530">to</span> <span m="782600">be--</span>
  <span m="783590">if</span> <span m="783800">you</span> <span m="783940">know</span>
  <span m="784380">the</span> <span m="784530">analytical</span> <span m="785140">solution,</span>
  <span m="785820">if</span> <span m="786020">you</span> <span m="786120">know</span>
  <span m="786450">what</span> <span m="786850">u</span> <span m="787250">is, for
  example,</span> <span m="787600">if</span> <span m="787840">f of u</span> <span
  m="788430">is</span> <span m="788860">equal</span> <span m="789290">to</span> <span
  m="789720">lambda</span> <span m="789930">u,</span> <span m="790390">then you know</span>
  <span m="790660">what</span> <span m="790690">u is,</span> <span m="790910">right?</span>
  <span m="791720">And</span> <span m="792090">you</span> <span m="792230">plug</span>
  <span m="792870">this</span> <span m="793860">into</span> <span m="794800">the</span>
  <span m="794920">finite</span> <span m="795390">difference</span> <span m="795940">operator.</span>
  <span m="798040">This</span> <span m="798250">is</span> <span m="798380">not</span>
  <span m="798590">going</span> <span m="798710">to</span> <span m="799040">be</span>
  <span m="799270">exactly</span> <span m="800050">equal</span> <span m="800320">to</span>
  <span m="800500">0.</span> <span m="801970">Right?</span> <span m="802350">This</span>
  <span m="802560">is</span> <span m="802800">not</span> <span m="803150">going</span>
  <span m="803300">to</span> <span m="803360">be</span> <span m="803650">equal</span>
  <span m="803940">to</span> <span m="804110">0.</span></p> <p><span m="808940">OK,</span>
  <span m="809420">so</span> <span m="809750">for</span> <span m="809880">example,</span>
  <span m="811240">if</span> <span m="811490">you''re</span> <span m="811700">looking</span>
  <span m="812020">at</span> <span m="812450">Forward Euler,</span> <span m="814150">if
  you''re</span> <span m="814350">looking</span> <span m="814640">at</span> <span
  m="815110">Forward Euler,</span> <span m="816430">u</span> <span m="816670">of</span>
  <span m="816830">k</span> <span m="817020">plus</span> <span m="817680">1</span>
  <span m="818620">minus</span> <span m="818760">u</span> <span m="819030">of</span>
  <span m="819330">k</span> <span m="819800">divided</span> <span m="820370">by</span>
  <span m="820470">delta</span> <span m="820570">t,</span> <span m="822242">if</span>
  <span m="822660">you</span> <span m="822970">subtract</span> <span m="824980">by
  f</span> <span m="825240">of</span> <span m="825640">u k,</span> <span m="826760">it</span>
  <span m="826970">is</span> <span m="827160">not</span> <span m="827430">going</span>
  <span m="827550">to</span> <span m="827620">be</span> <span m="827730">equal to</span>
  <span m="828080">0.</span> <span m="829930">If</span> <span m="830540">instead</span>
  <span m="830920">of</span> <span m="831060">u k</span> <span m="831540">you</span>
  <span m="831780">plug in</span> <span m="832370">the</span> <span m="832510">[INAUDIBLE]</span>
  <span m="832850">solution,</span> <span m="833250">you''re</span> <span m="833370">going</span>
  <span m="833490">to</span> <span m="833550">get</span> <span m="833740">0.</span>
  <span m="833970">But</span> <span m="834260">if</span> <span m="834480">you</span>
  <span m="834760">plug in</span> <span m="835380">the</span> <span m="835500">real,</span>
  <span m="835970">analytical</span> <span m="836670">solution,</span> <span m="837220">you''re</span>
  <span m="837340">not</span> <span m="837540">going</span> <span m="837680">to</span>
  <span m="837760">get</span> <span m="837980">0.</span> <span m="839700">And</span>
  <span m="840170">the</span> <span m="840430">order</span> <span m="841150">of</span>
  <span m="841510">that</span> <span m="842040">approximation</span> <span m="843310">is</span>
  <span m="843610">going</span> <span m="843790">to</span> <span m="843870">be</span>
  <span m="843970">the</span> <span m="844100">local</span> <span m="844500">order</span>
  <span m="844945">of</span> <span m="845390">accuracy.</span> <span m="847620">So</span>
  <span m="847990">if</span> <span m="848290">this</span> <span m="848650">is</span>
  <span m="849050">equal</span> <span m="849540">to</span> <span m="849815">O</span>
  <span m="850400">delta</span> <span m="850550">t</span> <span m="851880">to</span>
  <span m="852140">the</span> <span m="852320">k-th</span> <span m="853055">power,</span>
  <span m="853660">then</span> <span m="854070">k</span> <span m="855180">is</span>
  <span m="855780">the</span> <span m="855910">local</span> <span m="858350">order</span>
  <span m="859010">of</span> <span m="859290">accuracy.</span></p> <p><span m="861710">Now,</span>
  <span m="861910">here,</span> <span m="863110">the</span> <span m="863380">usual</span>
  <span m="863940">confusion</span> <span m="864630">that</span> <span m="864800">happens</span>
  <span m="865230">here</span> <span m="865430">is</span> <span m="865640">that</span>
  <span m="867560">when</span> <span m="867880">you</span> <span m="868150">do</span>
  <span m="868330">the</span> <span m="868500">truncation</span> <span m="868990">error</span>
  <span m="869180">analysis</span> <span m="869830">in</span> <span m="869980">another</span>
  <span m="870440">way,</span> <span m="871522">if you</span> <span m="872100">do</span>
  <span m="872280">the</span> <span m="872380">truncation</span> <span m="872950">error</span>
  <span m="873330">analysis</span> <span m="873880">by</span> <span m="874280">writing</span>
  <span m="874800">down</span> <span m="875100">the</span> <span m="875260">tau</span>
  <span m="876630">equal</span> <span m="877210">to</span> <span m="878590">u</span>
  <span m="879080">of</span> <span m="879320">k</span> <span m="879655">plus</span>
  <span m="879990">1,</span> <span m="880500">if</span> <span m="880670">you</span>
  <span m="880880">plug</span> <span m="881650">in</span> <span m="881890">the</span>
  <span m="881980">scheme,</span> <span m="883000">say,</span> <span m="883220">OK,</span>
  <span m="883760">u</span> <span m="884090">of</span> <span m="884280">k</span> <span
  m="884590">plus 1</span> <span m="885220">minus</span> <span m="885500">the</span>
  <span m="885630">right</span> <span m="885870">hand</span> <span m="886030">side</span>
  <span m="886240">of</span> <span m="886340">the</span> <span m="886460">scheme,</span>
  <span m="886810">which</span> <span m="887000">is</span> <span m="887130">u k</span>
  <span m="888621">plus</span> <span m="889118">delta</span> <span m="889615">t</span>
  <span m="890112">times</span> <span m="890609">f of</span> <span m="891110">u k,</span>
  <span m="893960">I''m</span> <span m="894170">going</span> <span m="894310">to</span>
  <span m="895360">get--</span> <span m="896410">tau,</span> <span m="896890">for</span>
  <span m="897030">example,</span> <span m="897500">in</span> <span m="897630">Forward
  Euler</span> <span m="898720">is</span> <span m="899130">O</span> <span m="899520">of</span>
  <span m="899600">delta</span> <span m="899880">t</span> <span m="900290">squared.</span>
  <span m="900910">Which,</span> <span m="902330">for</span> <span m="902670">any</span>
  <span m="903410">scheme,</span> <span m="903790">or</span> <span m="904170">for</span>
  <span m="904430">Forward Euler,</span> <span m="906500">it</span> <span m="906636">is</span>
  <span m="906773">because</span> <span m="906910">k</span> <span m="907372">is equal</span>
  <span m="907834">to</span> <span m="908296">1.</span> <span m="909220">Delta</span>
  <span m="909340">t</span> <span m="909450">squared</span> <span m="909740">is</span>
  <span m="910116">actually</span> <span m="910870">delta</span> <span m="911260">t</span>
  <span m="911440">to the k plus</span> <span m="911660">1</span> <span m="912136">power.</span></p>
  <p><span m="913090">So</span> <span m="913220">why</span> <span m="913650">is</span>
  <span m="913800">there</span> <span m="914010">a</span> <span m="914490">plus 1</span>
  <span m="914790">when</span> <span m="915160">I</span> <span m="916030">compute</span>
  <span m="916670">the</span> <span m="916780">local</span> <span m="916990">order
  of</span> <span m="917484">accuracy</span> <span m="917978">by figuring</span> <span
  m="918472">out the</span> <span m="918966">truncation</span> <span m="919460">error
  of the</span> <span m="919954">update</span> <span m="920448">scheme?</span> <span
  m="921436">Well,</span> <span m="921930">I get</span> <span m="922424">k</span>
  <span m="922918">if</span> <span m="923412">I look</span> <span m="923906">at</span>
  <span m="924400">the</span> <span m="924894">differential.</span> <span m="925388">If
  I look</span> <span m="925882">at</span> <span m="926376">the</span> <span m="926870">approximate,</span>
  <span m="927364">the</span> <span m="927528">time</span> <span m="927693">derivative</span>
  <span m="927858">could be</span> <span m="928352">[INAUDIBLE].</span> <span m="931316">Yeah?</span></p>
  <p><span m="932304">AUDIENCE:</span> <span m="932798">[INAUDIBLE]</span></p> <p><span
  m="942220">QIQI WANG: Right.</span> <span m="942640">We still</span> <span m="943080">need</span>
  <span m="943150">a</span> <span m="943445">manipulation.</span> <span m="944160">You</span>
  <span m="944566">can</span> <span m="946190">base</span> <span m="947771">the</span>
  <span m="948200">finite difference</span> <span m="949810">approximation</span>
  <span m="950305">of</span> <span m="950800">the</span> <span m="951295">n-th</span>
  <span m="951790">derivative</span> <span m="953280">and</span> <span m="953580">the</span>
  <span m="953800">update</span> <span m="954120">formula.</span> <span m="956090">So</span>
  <span m="956290">how</span> <span m="956520">do</span> <span m="956580">you</span>
  <span m="956810">go</span> <span m="957040">back</span> <span m="957310">and</span>
  <span m="957500">forth</span> <span m="958630">from this</span> <span m="959020">and</span>
  <span m="959220">this?</span> <span m="959750">How do you</span> <span m="959940">go</span>
  <span m="960080">back</span> <span m="960360">and</span> <span m="960550">forth</span>
  <span m="961310">from</span> <span m="964530">the</span> <span m="966560">approximation</span>
  <span m="966975">or</span> <span m="967390">the</span> <span m="967773">PDE</span>
  <span m="968540">to</span> <span m="968650">the</span> <span m="968820">update</span>
  <span m="969240">scheme?</span> <span m="969810">You have</span> <span m="970160">[INAUDIBLE]</span>
  <span m="970510">to</span> <span m="971140">multiply</span> <span m="972080">these</span>
  <span m="972450">two equations</span> <span m="972730">by</span> <span m="973090">delta</span>
  <span m="973260">t</span> <span m="973430">in order</span> <span m="973930">to get</span>
  <span m="974185">to</span> <span m="974440">here.</span> <span m="975908">You need</span>
  <span m="976334">to multiply</span> <span m="976760">this</span> <span m="976980">by</span>
  <span m="977290">delta</span> <span m="977410">t</span> <span m="977882">to get
  the</span> <span m="978354">update</span> <span m="978826">scheme.</span></p> <p><span
  m="980720">In</span> <span m="980940">other</span> <span m="981170">words,</span>
  <span m="982450">the</span> <span m="982900">approximation</span> <span m="983750">error</span>
  <span m="984210">of</span> <span m="984620">this</span> <span m="984970">update
  scheme</span> <span m="987050">is</span> <span m="987370">equal</span> <span m="987590">to</span>
  <span m="988005">the</span> <span m="988420">approximation</span> <span m="989250">error</span>
  <span m="990096">of</span> <span m="990452">the</span> <span m="990810">time</span>
  <span m="991170">derivative</span> <span m="991588">multiplied</span> <span m="992006">by</span>
  <span m="992424">delta</span> <span m="992842">t.</span> <span m="993680">Therefore,</span>
  <span m="994350">of course</span> <span m="994765">I get one</span> <span m="995180">more</span>
  <span m="995460">delta t</span> <span m="995931">in the</span> <span m="996402">truncation
  error.</span> <span m="1000170">So</span> <span m="1000310">that</span> <span m="1000490">is</span>
  <span m="1000630">the</span> <span m="1000720">reason</span> <span m="1001220">we</span>
  <span m="1001540">ask</span> <span m="1001860">you</span> <span m="1002050">to</span>
  <span m="1002460">subtract</span> <span m="1003226">1</span> <span m="1003915">when</span>
  <span m="1004220">we</span> <span m="1004630">figure</span> <span m="1005450">out</span>
  <span m="1005690">the</span> <span m="1005860">local</span> <span m="1006120">order
  of</span> <span m="1006480">accuracy.</span> <span m="1008090">If</span> <span m="1008430">you</span>
  <span m="1008820">figure</span> <span m="1009380">out</span> <span m="1010180">the</span>
  <span m="1010410">order</span> <span m="1010760">of</span> <span m="1010880">the</span>
  <span m="1011840">truncation error,</span> <span m="1012120">it''s the</span> <span
  m="1012615">single step</span> <span m="1013110">upward.</span> <span m="1017565">You
  can</span> <span m="1018070">go</span> <span m="1018250">from the</span> <span m="1018740">truncation
  error</span> <span m="1018970">of</span> <span m="1019120">the</span> <span m="1019596">single</span>
  <span m="1019754">step</span> <span m="1019913">updates</span> <span m="1020072">to</span>
  <span m="1020550">the</span> <span m="1021170">truncation error</span> <span m="1022110">of</span>
  <span m="1022350">the time</span> <span m="1022745">derivative.</span> <span m="1023930">You
  divide</span> <span m="1024200">this whole thing</span> <span m="1024470">by</span>
  <span m="1024970">delta t.</span> <span m="1026470">And</span> <span m="1026970">dividing</span>
  <span m="1028052">[INAUDIBLE]</span> <span m="1028940">by</span> <span m="1029510">delta</span>
  <span m="1029599">t,</span> <span m="1030270">you</span> <span m="1030619">get</span>
  <span m="1032020">O</span> <span m="1032490">delta t</span> <span m="1032740">to
  the</span> <span m="1033240">k,</span> <span m="1033740">right?</span></p> <p><span
  m="1035740">AUDIENCE:</span> <span m="1036240">[INAUDIBLE]</span></p> <p><span m="1038560">QIQI
  WANG: Yeah?</span></p> <p><span m="1039032">AUDIENCE: [INAUDIBLE]</span></p> <p><span
  m="1047280">QIQI WANG: Oh,</span> <span m="1047569">yeah,</span> <span m="1047910">sorry.</span>
  <span m="1049660">Thank</span> <span m="1049880">you</span> <span m="1049970">for</span>
  <span m="1050130">that.</span> <span m="1051930">Let</span> <span m="1052480">me</span>
  <span m="1052600">use</span> <span m="1052810">p</span> <span m="1054200">for</span>
  <span m="1054330">the</span> <span m="1054460">order</span> <span m="1054810">of</span>
  <span m="1055160">accuracy.</span> <span m="1055510">It</span> <span m="1055600">is</span>
  <span m="1055800">not</span> <span m="1057020">by</span> <span m="1057190">purpose.</span></p>
  <p><span m="1057710">AUDIENCE: [INAUDIBLE]</span></p> <p><span m="1061646">QIQI
  WANG: Yeah.</span></p> <p><span m="1062630">AUDIENCE: [INAUDIBLE]</span></p> <p><span
  m="1074930">QIQI WANG: Ah,</span> <span m="1075430">sorry.</span> <span m="1075780">This</span>
  <span m="1075980">is</span> <span m="1076090">k.</span> <span m="1077370">Those
  are</span> <span m="1077720">k''s.</span> <span m="1078190">Right,</span> <span
  m="1078380">I</span> <span m="1078660">confused</span> <span m="1078870">myself.</span></p>
  <p><span m="1088610">AUDIENCE: [INAUDIBLE]</span></p> <p><span m="1097640">QIQI
  WANG: All</span> <span m="1097850">right.</span> <span m="1098930">Yeah,</span>
  <span m="1099485">so</span> <span m="1099770">the</span> <span m="1100220">k</span>
  <span m="1100400">is</span> <span m="1100510">the</span> <span m="1100866">time
  step</span> <span m="1101580">number,</span> <span m="1102050">and</span> <span
  m="1102340">p</span> <span m="1102720">is the</span> <span m="1102860">order</span>
  <span m="1103240">of</span> <span m="1103606">accuracy.</span> <span m="1104670">Yeah,</span>
  <span m="1104910">thank</span> <span m="1105140">you.</span></p> <p><span m="1106553">AUDIENCE:
  [INAUDIBLE]</span></p> <p><span m="1108440">QIQI WANG: Yeah.</span></p> <p><span
  m="1109404">AUDIENCE: [INAUDIBLE]</span></p> <p><span m="1110850">QIQI WANG: Any</span>
  <span m="1111310">other</span> <span m="1111530">questions?</span> <span m="1116490">So</span>
  <span m="1116870">that</span> <span m="1117050">is,</span> <span m="1117580">I</span>
  <span m="1117680">think,</span> <span m="1117940">the</span> <span m="1118360">one</span>
  <span m="1118790">order</span> <span m="1119130">difference</span> <span m="1119910">in</span>
  <span m="1120670">the</span> <span m="1120740">local</span> <span m="1121080">order
  of</span> <span m="1121575">accuracy</span> <span m="1122070">in</span> <span m="1122455">that</span>
  <span m="1122840">case is</span> <span m="1124570">a</span> <span m="1124640">big</span>
  <span m="1124910">source</span> <span m="1125200">of</span> <span m="1125750">mistakes</span>
  <span m="1127580">in</span> <span m="1129180">figuring</span> <span m="1129650">out
  the</span> <span m="1130010">order of</span> <span m="1130120">accuracy</span> <span
  m="1133130">local</span> <span m="1133280">order</span> <span m="1133640">of</span>
  <span m="1133780">accuracy</span> <span m="1134160">analysis.</span> <span m="1136920">So</span>
  <span m="1137660">try</span> <span m="1137850">to</span> <span m="1138510">remember</span>
  <span m="1138900">that.</span></p> <p><span m="1140120">OK,</span> <span m="1140620">so</span>
  <span m="1141050">one</span> <span m="1141260">thing,</span> <span m="1141905">in
  the</span> <span m="1142370">PDE</span> <span m="1142815">context,</span> <span
  m="1143705">if</span> <span m="1144150">we</span> <span m="1144400">approximate</span>
  <span m="1145180">a</span> <span m="1145360">PDE</span> <span m="1145970">by</span>
  <span m="1146270">a</span> <span m="1146662">set</span> <span m="1147054">of</span>
  <span m="1147446">ODEs</span> <span m="1147840">and</span> <span m="1148140">solve</span>
  <span m="1148440">it</span> <span m="1149140">using</span> <span m="1149410">ODEs</span>
  <span m="1149730">by</span> <span m="1150160">[INAUDIBLE],</span> <span m="1153080">what</span>
  <span m="1153270">do you</span> <span m="1153610">think</span> <span m="1154570">is</span>
  <span m="1154910">going</span> <span m="1155060">to</span> <span m="1155130">be</span>
  <span m="1155250">the</span> <span m="1155530">order</span> <span m="1155870">of</span>
  <span m="1156210">accuracy</span> <span m="1156550">we''d</span> <span m="1156820">get</span>
  <span m="1157110">at</span> <span m="1157400">the</span> <span m="1157650">end?</span>
  <span m="1162350">How</span> <span m="1162810">much</span> <span m="1163570">area</span>
  <span m="1164930">are we</span> <span m="1165120">making</span> <span m="1167590">in</span>
  <span m="1167850">that</span> <span m="1168180">approximation?</span></p> <p><span
  m="1179160">All right,</span> <span m="1179340">what</span> <span m="1181550">determines</span>
  <span m="1182420">the</span> <span m="1182590">accuracy</span> <span m="1183380">if
  I</span> <span m="1183690">approximate</span> <span m="1184090">a</span> <span m="1184490">PDE</span>
  <span m="1186200">by</span> <span m="1186480">an</span> <span m="1186710">ODE</span>
  <span m="1187060">and</span> <span m="1187330">solve</span> <span m="1187695">the</span>
  <span m="1188060">ODE</span> <span m="1188490">using,</span> <span m="1188890">let''s</span>
  <span m="1189010">say,</span> <span m="1189090">a</span> <span m="1189400">Forward
  Euler?</span></p> <p><span m="1191985">AUDIENCE: [INAUDIBLE]</span></p> <p><span
  m="1194400">QIQI WANG: The</span> <span m="1194550">accuracy</span> <span m="1195050">of</span>
  <span m="1195180">the</span> <span m="1195240">ODE</span> <span m="1195580">scheme?</span></p>
  <p><span m="1196476">AUDIENCE: [INAUDIBLE]</span></p> <p><span m="1198270">QIQI
  WANG: And</span> <span m="1198730">the</span> <span m="1198870">accuracy</span>
  <span m="1199430">of</span> <span m="1199610">the</span> <span m="1199700">discretization,</span>
  <span m="1200410">actually,</span> <span m="1200880">both.</span> <span m="1202290">Actually,</span>
  <span m="1202680">both.</span> <span m="1205020">So</span> <span m="1205220">if</span>
  <span m="1206770">that</span> <span m="1207050">happens</span> <span m="1207740">even</span>
  <span m="1208220">for</span> <span m="1208540">some</span> <span m="1209307">advanced</span>
  <span m="1209784">graduate</span> <span m="1210261">students</span> <span m="1210738">when</span>
  <span m="1211215">they</span> <span m="1211692">look</span> <span m="1213130">at</span>
  <span m="1213230">the</span> <span m="1213340">order</span> <span m="1213750">of</span>
  <span m="1214160">accuracy</span> <span m="1214570">of a</span> <span m="1214980">PDE</span>
  <span m="1215800">discretization,</span> <span m="1216860">for</span> <span m="1217030">example,</span>
  <span m="1217670">it''s</span> <span m="1217960">quite</span> <span m="1218250">usual</span>
  <span m="1218530">for them to have</span> <span m="1218640">a</span> <span m="1219124">plot</span>
  <span m="1220092">of</span> <span m="1221060">the</span> <span m="1221290">area</span>
  <span m="1222800">versus</span> <span m="1223060">the grid.</span> <span m="1224620">And</span>
  <span m="1225330">often</span> <span m="1225660">what they</span> <span m="1225870">find</span>
  <span m="1226240">out,</span> <span m="1226430">as</span> <span m="1226630">I</span>
  <span m="1226730">refine</span> <span m="1226985">the</span> <span m="1227240">grid</span>
  <span m="1227470">further,</span> <span m="1227870">I</span> <span m="1228280">no</span>
  <span m="1228540">longer</span> <span m="1228860">improve</span> <span m="1229490">my</span>
  <span m="1229900">accuracy.</span> <span m="1230225">So</span> <span m="1230550">what</span>
  <span m="1231036">happens?</span></p> <p><span m="1232494">AUDIENCE: [INAUDIBLE]</span></p>
  <p><span m="1235900">QIQI WANG: Yes,</span> <span m="1236480">because</span> <span
  m="1236920">then</span> <span m="1237450">I''m</span> <span m="1237837">replacing</span>
  <span m="1238611">my</span> <span m="1239000">grid spacing.</span> <span m="1240010">And</span>
  <span m="1240510">if</span> <span m="1241010">I''m</span> <span m="1241100">not
  also</span> <span m="1241520">decreasing</span> <span m="1241980">my</span> <span
  m="1242424">cell step</span> <span m="1242868">size,</span> <span m="1244200">if</span>
  <span m="1244460">I''m</span> <span m="1244570">not</span> <span m="1244720">decreasing</span>
  <span m="1245143">my</span> <span m="1245566">delta</span> <span m="1245989">t,</span>
  <span m="1247260">even</span> <span m="1247680">though</span> <span m="1247940">my</span>
  <span m="1248080">spatial</span> <span m="1248500">discretization</span> <span m="1249310">is</span>
  <span m="1250220">extremely</span> <span m="1250900">accurate,</span> <span m="1251390">has</span>
  <span m="1251620">no</span> <span m="1251910">error,</span> <span m="1252610">I
  feel</span> <span m="1253140">that a</span> <span m="1253360">truncation error</span>
  <span m="1255360">would be proportionate</span> <span m="1256240">to delta</span>
  <span m="1256440">t.</span> <span m="1257550">So if I</span> <span m="1258160">don''t</span>
  <span m="1258290">decrease</span> <span m="1258380">my</span> <span m="1258590">delta</span>
  <span m="1258950">t,</span> <span m="1259642">I''m not</span> <span m="1259990">going</span>
  <span m="1260280">to</span> <span m="1260610">reduce</span> <span m="1261000">my</span>
  <span m="1261412">discretization</span> <span m="1261824">error</span> <span m="1262236">further.</span></p>
  <p><span m="1265452">So</span> <span m="1265800">the</span> <span m="1266260">ODE</span>
  <span m="1266620">discretization</span> <span m="1266890">scheme</span> <span m="1267240">makes</span>
  <span m="1267570">an</span> <span m="1267770">error.</span> <span m="1268420">And</span>
  <span m="1268650">that</span> <span m="1268920">error</span> <span m="1269240">is</span>
  <span m="1269430">actually</span> <span m="1269740">sometimes</span> <span m="1270190">overlooked</span>
  <span m="1270830">when</span> <span m="1270990">you</span> <span m="1271140">do</span>
  <span m="1271390">PDE</span> <span m="1271690">analysis.</span> <span m="1272970">So</span>
  <span m="1273970">remember,</span> <span m="1274740">there</span> <span m="1274980">is</span>
  <span m="1275130">still</span> <span m="1275420">going</span> <span m="1275550">to</span>
  <span m="1275620">be</span> <span m="1275720">an</span> <span m="1275910">ODE</span>
  <span m="1276410">component,</span> <span m="1277020">always,</span> <span m="1278820">even</span>
  <span m="1279990">if</span> <span m="1280140">you</span> <span m="1280240">look</span>
  <span m="1280500">at</span> <span m="1280770">PDEs,</span> <span m="1282310">time</span>
  <span m="1282710">dependent</span> <span m="1283480">PDEs.</span></p> <p><span m="1285880">OK,</span>
  <span m="1286160">so</span> <span m="1286320">this</span> <span m="1286530">is</span>
  <span m="1286680">the</span> <span m="1287050">local</span> <span m="1287650">order</span>
  <span m="1288030">of</span> <span m="1288200">accuracy.</span> <span m="1289120">How</span>
  <span m="1289340">does</span> <span m="1289500">that</span> <span m="1289670">relate</span>
  <span m="1290070">to</span> <span m="1290170">the</span> <span m="1290350">global</span>
  <span m="1290740">order</span> <span m="1290900">of</span> <span m="1291010">accuracy?</span>
  <span m="1295860">So</span> <span m="1296090">what</span> <span m="1296290">if</span>
  <span m="1296460">I</span> <span m="1296600">do</span> <span m="1296860">global</span>
  <span m="1299660">order</span> <span m="1299900">of</span> <span m="1300050">accuracy?</span>
  <span m="1301940">How</span> <span m="1302310">does--</span> <span m="1302985">I</span>
  <span m="1303400">mean,</span> <span m="1303600">it''s</span> <span m="1303750">a</span>
  <span m="1303810">very</span> <span m="1304140">simple</span> <span m="1304330">answer,</span>
  <span m="1304820">so</span> <span m="1305450">please</span> <span m="1306010">answer</span>
  <span m="1306100">me.</span> <span m="1306560">How</span> <span m="1306780">does</span>
  <span m="1307070">local</span> <span m="1307480">order</span> <span m="1307680">of</span>
  <span m="1307820">accuracy</span> <span m="1308340">relate</span> <span m="1308770">to</span>
  <span m="1308870">the</span> <span m="1309110">global</span> <span m="1309500">order</span>
  <span m="1309780">of</span> <span m="1310255">accuracy?</span> <span m="1314060">Global</span>
  <span m="1314500">is</span> <span m="1314650">one</span> <span m="1314920">more</span>
  <span m="1315150">than</span> <span m="1315330">local?</span></p> <p><span m="1318185">AUDIENCE:
  They''re the same.</span></p> <p><span m="1319520">QIQI WANG: Or are</span> <span
  m="1319770">they the same?</span> <span m="1320770">If</span> <span m="1320936">it</span>
  <span m="1321270">is</span> <span m="1321770">consistent,</span> <span m="1322270">yes.</span></p>
  <p><span m="1325780">OK,</span> <span m="1326300">global</span> <span m="1327030">is</span>
  <span m="1327460">equal</span> <span m="1327980">to</span> <span m="1328090">local</span>
  <span m="1330130">if</span> <span m="1330750">the</span> <span m="1331170">scheme</span>
  <span m="1331410">is</span> <span m="1331610">zero</span> <span m="1331820">stable.</span>
  <span m="1334990">That''s</span> <span m="1335360">the</span> <span m="1335500">Dahlquist</span>
  <span m="1335605">Equivalence</span> <span m="1335710">Theorem.</span> <span m="1339580">Yes.</span>
  <span m="1345480">Right,</span> <span m="1346140">so</span> <span m="1346530">local
  and</span> <span m="1346800">global</span> <span m="1347260">order of accuracy</span>
  <span m="1348260">are</span> <span m="1348720">the</span> <span m="1348860">same,</span>
  <span m="1349640">right?</span> <span m="1350280">There</span> <span m="1350550">is</span>
  <span m="1350700">no</span> <span m="1351220">plus one or</span> <span m="1351790">minus</span>
  <span m="1352120">one.</span> <span m="1352750">The</span> <span m="1352890">plus
  or minus</span> <span m="1353305">one</span> <span m="1353720">happens</span> <span
  m="1354420">over</span> <span m="1354800">here</span> <span m="1355340">when</span>
  <span m="1355500">you</span> <span m="1355620">figure</span> <span m="1356410">out</span>
  <span m="1357290">the</span> <span m="1357440">order</span> <span m="1357860">of
  the</span> <span m="1358280">one-step</span> <span m="1358737">truncation error.</span>
  <span m="1361480">Then you can</span> <span m="1361770">get</span> <span m="1362150">local</span>
  <span m="1362470">order of accuracy,</span> <span m="1363570">you</span> <span m="1363730">need</span>
  <span m="1364030">to</span> <span m="1365440">subtract</span> <span m="1365920">one</span>
  <span m="1366195">from</span> <span m="1366932">the delta t.</span> <span m="1368780">But
  there</span> <span m="1368980">is</span> <span m="1369120">no</span> <span m="1369320">plus</span>
  <span m="1369640">or</span> <span m="1369720">minus</span> <span m="1370060">one</span>
  <span m="1370845">in the</span> <span m="1371590">global</span> <span m="1371890">and</span>
  <span m="1372050">local</span> <span m="1372430">order of accuracy.</span></p> <p><span
  m="1373724">AUDIENCE: [INAUDIBLE]</span> <span m="1374658">one or</span> <span m="1375125">greater</span>
  <span m="1375592">[INAUDIBLE].</span> <span m="1378870">You</span> <span m="1379170">can''t</span>
  <span m="1379380">have</span> <span m="1379520">like</span> <span m="1379790">zero</span>
  <span m="1380060">order</span> <span m="1380520">of</span> <span m="1380915">local</span>
  <span m="1381310">accuracy?</span></p> <p><span m="1382100">QIQI WANG: Oh,</span>
  <span m="1382300">yes,</span> <span m="1382830">this</span> <span m="1383080">is</span>
  <span m="1383650">provided</span> <span m="1384590">we have a</span> <span m="1385060">consistent</span>
  <span m="1385530">scheme,</span> <span m="1386000">provided</span> <span m="1386470">we</span>
  <span m="1386650">have</span> <span m="1387860">at</span> <span m="1388325">least</span>
  <span m="1388790">equal to 1</span> <span m="1389255">here.</span> <span m="1389720">Right,</span>
  <span m="1390185">yeah,</span> <span m="1391670">thanks for</span> <span m="1391870">that.</span>
  <span m="1392630">So</span> <span m="1393750">the</span> <span m="1394080">whole</span>
  <span m="1394290">thing</span> <span m="1394510">is</span> <span m="1394750">under</span>
  <span m="1395100">the</span> <span m="1395520">assumption</span> <span m="1400490">that</span>
  <span m="1401380">p</span> <span m="1401840">is</span> <span m="1402060">greater
  than</span> <span m="1402420">or</span> <span m="1402540">equal</span> <span m="1402640">to</span>
  <span m="1402880">1.</span> <span m="1403590">I</span> <span m="1403670">mean,</span>
  <span m="1403840">that''s</span> <span m="1404040">usually</span> <span m="1404410">the</span>
  <span m="1404490">case.</span> <span m="1405080">We</span> <span m="1407110">usually</span>
  <span m="1407370">only</span> <span m="1407650">look at</span> <span m="1407870">vertical</span>
  <span m="1408344">schemes</span> <span m="1408818">that are</span> <span m="1409292">consistent,</span>
  <span m="1409766">right?</span></p> <p><span m="1411662">AUDIENCE: [INAUDIBLE]</span></p>
  <p><span m="1413560">QIQI WANG: Yeah,</span> <span m="1413770">the</span> <span
  m="1413870">definition</span> <span m="1414300">of</span> <span m="1414380">consistency</span>
  <span m="1415230">is</span> <span m="1416070">p</span> <span m="1416400">greater</span>
  <span m="1416710">than</span> <span m="1416950">or</span> <span m="1417090">equal</span>
  <span m="1417260">to</span> <span m="1417380">1,</span> <span m="1418132">local.</span>
  <span m="1420500">That</span> <span m="1420730">is</span> <span m="1420890">a</span>
  <span m="1421000">consistent</span> <span m="1421445">scheme.</span> <span m="1422780">Yes?</span></p>
  <p><span m="1423090">AUDIENCE: And the practical</span> <span m="1423630">way</span>
  <span m="1424050">of</span> <span m="1424476">finding</span> <span m="1425330">that</span>
  <span m="1425635">is</span> <span m="1425940">the</span> <span m="1426360">sum</span>
  <span m="1426500">of</span> <span m="1426640">the--</span></p> <p><span m="1428460">QIQI
  WANG: The</span> <span m="1428570">practical</span> <span m="1429060">way</span>
  <span m="1429210">of</span> <span m="1429410">finding</span> <span m="1429830">what?</span></p>
  <p><span m="1430982">AUDIENCE: If</span> <span m="1431410">p</span> <span m="1431750">is
  greater than</span> <span m="1432220">or equal</span> <span m="1432681">to</span>
  <span m="1433142">1</span> <span m="1433603">[INAUDIBLE]</span> <span m="1434525">discrete</span>
  <span m="1434990">surface</span> <span m="1435280">[INAUDIBLE]</span> <span m="1435560">equals</span>
  <span m="1436031">0.</span></p> <p><span m="1438860">QIQI WANG: A</span> <span m="1439010">practical</span>
  <span m="1439570">way</span> <span m="1439820">of</span> <span m="1440070">finding</span>
  <span m="1440410">out</span> <span m="1440760">if</span> <span m="1442630">a</span>
  <span m="1442910">scheme</span> <span m="1443480">is</span> <span m="1443670">consistent</span>
  <span m="1444230">is</span> <span m="1444610">by</span> <span m="1445010">doing</span>
  <span m="1446210">the</span> <span m="1446440">global</span> <span m="1447290">truncation
  error</span> <span m="1447660">analysis.</span> <span m="1448370">You</span> <span
  m="1448870">have</span> <span m="1449070">to</span> <span m="1449160">look</span>
  <span m="1449370">at</span> <span m="1449480">the</span> <span m="1449510">Taylor</span>
  <span m="1449890">series</span> <span m="1450270">expansion</span> <span m="1450666">to</span>
  <span m="1451062">find out</span> <span m="1451460">if</span> <span m="1451680">the</span>
  <span m="1451970">scheme is</span> <span m="1452417">consistent</span> <span m="1452864">or</span>
  <span m="1453311">not.</span> <span m="1455110">I</span> <span m="1455730">don''t</span>
  <span m="1455920">think</span> <span m="1456090">there</span> <span m="1456220">is</span>
  <span m="1456370">an</span> <span m="1456490">easier</span> <span m="1456940">way</span>
  <span m="1458010">to</span> <span m="1458110">find</span> <span m="1458410">out</span>
  <span m="1458640">if a</span> <span m="1458750">scheme</span> <span m="1459010">is</span>
  <span m="1459455">consistent</span> <span m="1459730">or not.</span></p> <p><span
  m="1461500">AUDIENCE: There was</span> <span m="1461960">something</span> <span
  m="1462420">in</span> <span m="1462880">the</span> <span m="1463340">notes</span>
  <span m="1463800">about</span> <span m="1465180">the</span> <span m="1465640">coefficients</span>
  <span m="1467020">of</span> <span m="1467280">the</span> <span m="1467960">non-derivative</span>
  <span m="1468380">terms</span> <span m="1469875">sum</span> <span m="1470340">to</span>
  <span m="1470630">0.</span> <span m="1471343">Might</span> <span m="1471461">be</span>
  <span m="1471579">a</span> <span m="1471697">little</span> <span m="1471816">bit</span>
  <span m="1472289">[INAUDIBLE].</span></p> <p><span m="1482150">QIQI WANG: Yeah,</span>
  <span m="1483030">OK,</span> <span m="1483340">so</span> <span m="1483730">there</span>
  <span m="1483940">is</span> <span m="1485280">a</span> <span m="1485580">condition</span>
  <span m="1486150">that</span> <span m="1486570">the</span> <span m="1486850">coefficients</span>
  <span m="1487260">of</span> <span m="1487410">the</span> <span m="1487830">constant</span>
  <span m="1488250">terms</span> <span m="1488470">sum</span> <span m="1488560">to</span>
  <span m="1489010">0.</span> <span m="1489910">But</span> <span m="1490180">I</span>
  <span m="1490540">think</span> <span m="1491034">that</span> <span m="1491528">is
  a</span> <span m="1492022">necessary</span> <span m="1492516">but</span> <span m="1493010">not</span>
  <span m="1493504">sufficient</span> <span m="1493998">condition.</span></p> <p><span
  m="1496962">AUDIENCE: [INAUDIBLE]</span></p> <p><span m="1501408">QIQI WANG: Right,</span>
  <span m="1501902">right.</span> <span m="1503878">So</span> <span m="1504380">if</span>
  <span m="1504580">I</span> <span m="1505068">flip a coin</span> <span m="1505556">of</span>
  <span m="1506044">[INAUDIBLE],</span> <span m="1508484">we''re going to</span> <span
  m="1508972">get</span> <span m="1509460">a</span> <span m="1509948">sum of</span>
  <span m="1510436">0,</span> <span m="1511420">that</span> <span m="1511610">is</span>
  <span m="1511760">not</span> <span m="1512020">a</span> <span m="1512260">consistent</span>
  <span m="1512620">scheme.</span></p> <p><span m="1513602">AUDIENCE: [INAUDIBLE]</span></p>
  <p><span m="1523430">QIQI WANG: Yeah,</span> <span m="1523660">the</span> <span
  m="1523960">sum</span> <span m="1524020">to</span> <span m="1524340">0</span> <span
  m="1524580">only</span> <span m="1524640">means</span> <span m="1525140">that</span>
  <span m="1525640">you</span> <span m="1526140">get</span> <span m="1526380">consistent</span>
  <span m="1527430">approximation</span> <span m="1528290">of</span> <span m="1528430">the</span>
  <span m="1528740">d by dt</span> <span m="1529500">equal to</span> <span m="1529720">0</span>
  <span m="1529970">equation.</span></p> <p><span m="1531970">AUDIENCE: [INAUDIBLE]</span></p>
  <p><span m="1542180">QIQI WANG: OK,</span> <span m="1542880">again,</span> <span
  m="1544220">if</span> <span m="1544680">you look</span> <span m="1544945">at</span>
  <span m="1545210">a</span> <span m="1545470">PDE,</span> <span m="1547420">the</span>
  <span m="1547600">global</span> <span m="1548050">order</span> <span m="1548240">of</span>
  <span m="1548740">accuracy</span> <span m="1549170">is</span> <span m="1550020">going
  to</span> <span m="1550330">be</span> <span m="1550700">determined</span> <span
  m="1551480">both</span> <span m="1551790">by</span> <span m="1551950">the</span>
  <span m="1552080">spatial</span> <span m="1552650">and</span> <span m="1553480">temporal</span>
  <span m="1553870">discretization.</span> <span m="1555330">So</span> <span m="1556540">even</span>
  <span m="1557270">though</span> <span m="1557440">if</span> <span m="1557720">you</span>
  <span m="1557840">look</span> <span m="1558100">at</span> <span m="1558620">how</span>
  <span m="1558790">the</span> <span m="1558890">area</span> <span m="1559140">decays</span>
  <span m="1560066">as you refine</span> <span m="1560785">your grid.</span> <span
  m="1561200">You</span> <span m="1561310">still</span> <span m="1561580">need</span>
  <span m="1561810">to</span> <span m="1562780">be</span> <span m="1562890">careful</span>
  <span m="1563300">with</span> <span m="1563500">the</span> <span m="1563640">time
  derivative</span> <span m="1564340">term.</span> <span m="1565670">You</span> <span
  m="1565790">need</span> <span m="1565940">to</span> <span m="1566030">refine</span>
  <span m="1566410">your</span> <span m="1566550">time</span> <span m="1566820">step</span>
  <span m="1567070">at</span> <span m="1567160">the</span> <span m="1567240">same</span>
  <span m="1567500">time.</span> <span m="1568790">And</span> <span m="1569450">maybe</span>
  <span m="1570130">you have to</span> <span m="1570550">refine</span> <span m="1570820">your</span>
  <span m="1571090">time</span> <span m="1571365">step</span> <span m="1571640">even</span>
  <span m="1571890">more</span> <span m="1572330">if</span> <span m="1572530">your</span>
  <span m="1574050">order of accuracy</span> <span m="1575080">in time</span> <span
  m="1575460">is</span> <span m="1575790">less</span> <span m="1576090">than</span>
  <span m="1576280">the</span> <span m="1576750">order of accuracy</span> <span m="1577020">in
  space.</span> <span m="1579980">All right,</span> <span m="1580170">any</span> <span
  m="1580820">questions</span> <span m="1581320">on</span> <span m="1581630">accuracy?</span></p>
  <p><span m="1584310">And</span> <span m="1584560">accuracy,</span> <span m="1585670">if</span>
  <span m="1586180">you</span> <span m="1586270">need</span> <span m="1586410">to</span>
  <span m="1586570">figure out</span> <span m="1587020">what</span> <span m="1587470">a</span>
  <span m="1587610">scheme</span> <span m="1587800">is,</span> <span m="1589320">the</span>
  <span m="1589510">order of accuracy</span> <span m="1590500">is</span> <span m="1592040">a</span>
  <span m="1592270">good</span> <span m="1592580">way</span> <span m="1593360">to</span>
  <span m="1593490">check</span> <span m="1594560">what</span> <span m="1594750">the</span>
  <span m="1594830">scheme</span> <span m="1595200">is.</span> <span m="1595980">Because</span>
  <span m="1596300">different</span> <span m="1596670">schemes</span> <span m="1596930">have</span>
  <span m="1597160">different</span> <span m="1597490">orders</span> <span m="1597730">of</span>
  <span m="1597790">accuracy.</span> <span m="1599110">Forward Euler,</span> <span
  m="1600062">Backward Euler</span> <span m="1601490">are</span> <span m="1601740">first-order</span>
  <span m="1601970">accurate.</span> <span m="1604855">Trapezoidal</span> <span m="1605330">rule</span>
  <span m="1606570">and</span> <span m="1606750">midpoint</span> <span m="1607850">are</span>
  <span m="1608290">second-order</span> <span m="1609130">accurate.</span> <span m="1610560">And</span>
  <span m="1610810">there</span> <span m="1610980">are</span> <span m="1611440">more</span>
  <span m="1611760">advance</span> <span m="1612045">schemes.</span> <span m="1613610">Many</span>
  <span m="1613890">of</span> <span m="1614000">them</span> <span m="1614200">have
  an</span> <span m="1614540">even</span> <span m="1614850">higher</span> <span m="1615220">order
  of accuracy.</span> <span m="1618300">So</span> <span m="1618360">that''s</span>
  <span m="1618981">a</span> <span m="1621186">good</span> <span m="1621630">distinguisher</span>
  <span m="1621925">of</span> <span m="1622780">different</span> <span m="1623070">schemes.</span></p>
  <p><span m="1624890">OK,</span> <span m="1625230">eigenvalue</span> <span m="1625840">stability.</span>
  <span m="1628610">OK,</span> <span m="1628900">can</span> <span m="1629310">somebody</span>
  <span m="1629690">tell</span> <span m="1629950">me?</span> <span m="1630420">We</span>
  <span m="1630910">looked</span> <span m="1631790">at</span> <span m="1631990">zero</span>
  <span m="1632280">stability,</span> <span m="1634020">right?</span> <span m="1634766">That</span>
  <span m="1635140">is,</span> <span m="1635320">what</span> <span m="1637200">makes</span>
  <span m="1638055">a</span> <span m="1638520">scheme</span> <span m="1639450">have</span>
  <span m="1639770">a</span> <span m="1639940">global</span> <span m="1640300">order</span>
  <span m="1640480">of</span> <span m="1640600">accuracy</span> <span m="1640980">equal</span>
  <span m="1641240">to</span> <span m="1641330">local</span> <span m="1641660">order
  of accuracy?</span> <span m="1642960">How does</span> <span m="1643330">eigenvalue</span>
  <span m="1643920">stability,</span> <span m="1644910">how</span> <span m="1645040">is</span>
  <span m="1645280">that</span> <span m="1645450">different</span> <span m="1645820">from</span>
  <span m="1646600">zero</span> <span m="1647050">stability?</span> <span m="1649750">Yes?</span></p>
  <p><span m="1651353">AUDIENCE:</span> <span m="1651814">[INAUDIBLE]</span></p> <p><span
  m="1652275">QIQI WANG: Hm?</span> <span m="1653660">If</span> <span m="1653850">the</span>
  <span m="1653940">general</span> <span m="1654430">case--</span></p> <p><span m="1655930">AUDIENCE:
  [INAUDIBLE]</span></p> <p><span m="1663940">QIQI WANG: Right.</span> <span m="1664380">So</span>
  <span m="1665050">eigenvalue</span> <span m="1665390">stability,</span> <span m="1666350">in
  some</span> <span m="1666660">sense,</span> <span m="1667030">is an</span> <span
  m="1667190">expanded</span> <span m="1667790">version</span> <span m="1668080">of</span>
  <span m="1668560">zero</span> <span m="1668620">stability.</span> <span m="1669510">So
  it</span> <span m="1669680">basically</span> <span m="1670180">says</span> <span
  m="1670530">that</span> <span m="1670770">my</span> <span m="1670930">solution,</span>
  <span m="1671620">Vk,</span> <span m="1673970">is</span> <span m="1674470">bounded</span>
  <span m="1679810">for</span> <span m="1680280">the</span> <span m="1680440">question</span>
  <span m="1681340">of</span> <span m="1682610">du dt</span> <span m="1684140">equal</span>
  <span m="1684560">to</span> <span m="1684690">lambda</span> <span m="1685130">u.</span>
  <span m="1686350">So</span> <span m="1686550">this</span> <span m="1688330">eigenvalue</span>
  <span m="1688850">stability,</span> <span m="1690310">while</span> <span m="1690420">zero</span>
  <span m="1690610">stability</span> <span m="1691390">says</span> <span m="1691690">that</span>
  <span m="1692010">the</span> <span m="1692170">solution</span> <span m="1692630">is</span>
  <span m="1692850">bounded</span> <span m="1693360">for</span> <span m="1693625">du
  dt</span> <span m="1693890">equal</span> <span m="1693970">to</span> <span m="1694300">0.</span></p>
  <p><span m="1701610">So</span> <span m="1701750">when</span> <span m="1701870">you</span>
  <span m="1702030">talk</span> <span m="1702260">about</span> <span m="1702530">eigenvalue</span>
  <span m="1703040">stability,</span> <span m="1705330">you</span> <span m="1705560">have</span>
  <span m="1705810">to</span> <span m="1705950">give</span> <span m="1706190">me</span>
  <span m="1706470">two</span> <span m="1706730">things</span> <span m="1707540">for</span>
  <span m="1707680">me</span> <span m="1707830">to</span> <span m="1707950">determine</span>
  <span m="1708950">if</span> <span m="1710660">a scheme is</span> <span m="1711110">eigenvalue</span>
  <span m="1711250">stable</span> <span m="1711410">or not.</span> <span m="1711880">You
  have to</span> <span m="1711960">give</span> <span m="1712140">me</span> <span m="1712320">the</span>
  <span m="1712640">scheme.</span> <span m="1715520">What</span> <span m="1715840">scheme</span>
  <span m="1716270">are</span> <span m="1716570">you</span> <span m="1716750">are</span>
  <span m="1716840">using?</span> <span m="1717210">Are</span> <span m="1717280">you</span>
  <span m="1717360">talking</span> <span m="1717950">Forward Euler,</span> <span m="1718500">Backward
  Euler,</span> <span m="1719323">midpoint?</span> <span m="1720290">You</span> <span
  m="1720420">have</span> <span m="1720560">to</span> <span m="1720660">also</span>
  <span m="1720890">give</span> <span m="1721050">me</span> <span m="1721160">something</span>
  <span m="1721500">else</span> <span m="1721850">for</span> <span m="1721990">me</span>
  <span m="1722120">to</span> <span m="1722240">determine</span> <span m="1723050">if</span>
  <span m="1724900">I''m</span> <span m="1725030">going</span> <span m="1725180">to</span>
  <span m="1725280">have</span> <span m="1725775">eigenvalue</span> <span m="1726120">stability</span>
  <span m="1726680">or not. What</span> <span m="1726870">is</span> <span m="1727000">that?</span></p>
  <p><span m="1727707">AUDIENCE: The governing</span> <span m="1728144">equation?</span></p>
  <p><span m="1728581">QIQI WANG: Hm?</span></p> <p><span m="1729018">AUDIENCE: The
  governing</span> <span m="1729455">equation.</span></p> <p><span m="1730330">QIQI
  WANG: The</span> <span m="1730710">governing</span> <span m="1730860">equation,</span>
  <span m="1731460">or</span> <span m="1731710">more</span> <span m="1731960">specifically,</span>
  <span m="1734210">lambda</span> <span m="1734290">times</span> <span m="1734660">delta
  t.</span> <span m="1736030">Right?</span> <span m="1737330">You</span> <span m="1737530">have</span>
  <span m="1737950">to</span> <span m="1738050">give</span> <span m="1738340">me</span>
  <span m="1738540">these</span> <span m="1738880">two</span> <span m="1739070">things</span>
  <span m="1740190">in</span> <span m="1740450">order</span> <span m="1740770">to</span>
  <span m="1740910">determine</span> <span m="1742630">if</span> <span m="1743110">a</span>
  <span m="1743370">scheme</span> <span m="1744630">is</span> <span m="1744770">eigenvalue</span>
  <span m="1744980">stable or not.</span> <span m="1745660">And</span> <span m="1745850">if</span>
  <span m="1746090">you</span> <span m="1746320">search</span> <span m="1746610">for</span>
  <span m="1746940">MIT</span> <span m="1747540">math</span> <span m="1748600">links,</span>
  <span m="1751420">eigenvalue</span> <span m="1751520">stability,</span> <span m="1754470">the</span>
  <span m="1754560">first</span> <span m="1754860">thing</span> <span m="1755040">you''re</span>
  <span m="1755210">going</span> <span m="1755330">to</span> <span m="1755410">get</span>
  <span m="1756080">on</span> <span m="1756400">Google</span> <span m="1756710">at</span>
  <span m="1757127">least</span> <span m="1758380">is</span> <span m="1758640">this</span>
  <span m="1758880">thing.</span> <span m="1761835">Always</span> <span m="1762120">run,</span>
  <span m="1763819">OK,</span> <span m="1765208">run.</span> <span m="1766140">You</span>
  <span m="1766300">have</span> <span m="1766480">to</span> <span m="1766630">do</span>
  <span m="1766850">a</span> <span m="1766930">bunch</span> <span m="1767200">of</span>
  <span m="1767630">Java</span> <span m="1768102">things.</span> <span m="1769518">Come</span>
  <span m="1769990">on.</span></p> <p><span m="1776430">Yeah,</span> <span m="1777100">that</span>
  <span m="1777270">is</span> <span m="1777450">going</span> <span m="1777620">to</span>
  <span m="1777710">give</span> <span m="1777980">you</span> <span m="1778920">the</span>
  <span m="1779270">eigenvalue</span> <span m="1780060">stability.</span> <span m="1781494">So
  you need</span> <span m="1781972">two things.</span> <span m="1782930">One</span>
  <span m="1783210">thing</span> <span m="1783650">is</span> <span m="1784120">the</span>
  <span m="1784420">scheme,</span> <span m="1784970">right?</span> <span m="1785560">For</span>
  <span m="1785750">different</span> <span m="1786150">schemes,</span> <span m="1786906">you
  are</span> <span m="1787362">going</span> <span m="1787818">to get</span> <span
  m="1788274">a</span> <span m="1788730">different</span> <span m="1789150">plot</span>
  <span m="1789710">of</span> <span m="1790180">eigenvalue</span> <span m="1790580">stability.</span>
  <span m="1791720">So</span> <span m="1791880">if</span> <span m="1792150">I</span>
  <span m="1792340">get</span> <span m="1794500">Backward Euler,</span> <span m="1796554">that
  is</span> <span m="1797150">my</span> <span m="1797500">stability</span> <span m="1797960">region.</span>
  <span m="1799070">And</span> <span m="1799420">this</span> <span m="1799680">plot</span>
  <span m="1800852">is</span> <span m="1801310">a</span> <span m="1801760">plot</span>
  <span m="1802160">[INAUDIBLE]</span> <span m="1802970">depending</span> <span m="1803100">on
  the</span> <span m="1803400">distance</span> <span m="1804590">lambda</span> <span
  m="1804950">delta t,</span> <span m="1805395">right?</span> <span m="1807096">That''s
  the second</span> <span m="1807560">thing</span> <span m="1807820">you need</span>
  <span m="1808080">to</span> <span m="1808528">tell</span> <span m="1808976">me</span>
  <span m="1809424">in order</span> <span m="1809872">to</span> <span m="1810320">[INAUDIBLE]</span>
  <span m="1810768">eigenvalue</span> <span m="1811216">stability.</span> <span m="1812120">You</span>
  <span m="1812270">also need</span> <span m="1812730">to tell</span> <span m="1813221">me</span>
  <span m="1813712">lambda</span> <span m="1814203">delta t,</span> <span m="1815185">and</span>
  <span m="1815676">that</span> <span m="1816167">determines</span> <span m="1817140">one
  point</span> <span m="1817510">in the</span> <span m="1817988">complex</span> <span
  m="1818466">set.</span></p> <p><span m="1820378">And</span> <span m="1820856">depending</span>
  <span m="1821095">on</span> <span m="1821334">[INAUDIBLE]</span> <span m="1825918">and</span>
  <span m="1826380">eigenvalue</span> <span m="1826590">stable</span> <span m="1826890">[INAUDIBLE]</span>
  <span m="1827376">or the</span> <span m="1827862">eigenvalue</span> <span m="1828348">unstable</span>
  <span m="1828834">[INAUDIBLE].</span> <span m="1835152">Right?</span> <span m="1837582">Any
  questions?</span> <span m="1841470">So</span> <span m="1841770">questions</span>
  <span m="1842245">over</span> <span m="1842720">there?</span> <span m="1845570">OK,</span>
  <span m="1846220">so</span> <span m="1846380">yes,</span> <span m="1847700">tell
  me a scheme,</span> <span m="1848140">and</span> <span m="1848550">tell me</span>
  <span m="1848997">lambda</span> <span m="1849444">delta t.</span> <span m="1850338">[INAUDIBLE]</span>
  <span m="1851679">I''m going</span> <span m="1852126">to</span> <span m="1852580">tell</span>
  <span m="1852810">you</span> <span m="1853090">I''m</span> <span m="1853520">stable</span>
  <span m="1853890">or not.</span> <span m="1856290">And</span> <span m="1856520">one
  thing is</span> <span m="1857080">for</span> <span m="1857526">Backward Euler,</span>
  <span m="1859760">as</span> <span m="1861120">your</span> <span m="1861612">delta</span>
  <span m="1862104">t</span> <span m="1862596">decreases,</span> <span m="1864564">whatever
  is</span> <span m="1865056">happening,</span> <span m="1865550">for the same</span>
  <span m="1866220">lambda,</span> <span m="1866420">as my</span> <span m="1866895">delta
  t</span> <span m="1867370">decreases,</span> <span m="1868320">I''m more and more</span>
  <span m="1868930">zooming</span> <span m="1869130">into</span> <span m="1870330">small</span>
  <span m="1870750">regions</span> <span m="1871140">and</span> <span m="1871237">in</span>
  <span m="1871335">all</span> <span m="1871432">regions.</span> <span m="1873570">And
  the smaller</span> <span m="1873890">I</span> <span m="1874210">get,</span> <span
  m="1876140">the</span> <span m="1876790">more I''m</span> <span m="1877190">approximating</span>
  <span m="1878910">the</span> <span m="1879200">stability</span> <span m="1879910">of
  the</span> <span m="1880210">true</span> <span m="1882110">ODE.</span></p> <p><span
  m="1883860">The</span> <span m="1883970">value</span> <span m="1884240">of</span>
  <span m="1884390">the</span> <span m="1884760">true</span> <span m="1884960">ODE</span>
  <span m="1885290">is the</span> <span m="1885734">[INAUDIBLE].</span> <span m="1887066">If
  lambda</span> <span m="1887510">has a</span> <span m="1887970">[INAUDIBLE],</span>
  <span m="1888400">then that''s</span> <span m="1888883">unstable</span> <span m="1889366">behavior.</span>
  <span m="1890332">If</span> <span m="1890815">lambda</span> <span m="1891298">has</span>
  <span m="1891781">a</span> <span m="1892264">[INAUDIBLE]</span> <span m="1892750">value,</span>
  <span m="1893794">then</span> <span m="1894201">it''s</span> <span m="1894610">stable.</span>
  <span m="1895120">Must</span> <span m="1895578">be</span> <span m="1896036">stable,</span>
  <span m="1896494">right?</span> <span m="1898330">If I</span> <span m="1898510">zoom</span>
  <span m="1898970">in</span> <span m="1899275">[INAUDIBLE],</span> <span m="1900846">that''s</span>
  <span m="1901268">going to</span> <span m="1901690">be</span> <span m="1901990">more
  and more</span> <span m="1902380">of what I get.</span></p> <p><span m="1905380">And</span>
  <span m="1905880">same</span> <span m="1906140">thing</span> <span m="1907050">for</span>
  <span m="1907700">Forward Euler,</span> <span m="1908440">right?</span> <span m="1909730">As</span>
  <span m="1910210">I</span> <span m="1910690">zoom more</span> <span m="1911170">and</span>
  <span m="1911638">more</span> <span m="1911794">into</span> <span m="1911950">the</span>
  <span m="1912106">[INAUDIBLE],</span> <span m="1913042">that''s</span> <span m="1913510">what</span>
  <span m="1913690">I</span> <span m="1913800">get.</span> <span m="1914880">And</span>
  <span m="1915140">the</span> <span m="1915220">same</span> <span m="1915560">thing</span>
  <span m="1916650">for</span> <span m="1917700">trapezoidal.</span> <span m="1918910">It''s</span>
  <span m="1919280">really</span> <span m="1919540">depending</span> <span m="1919990">on</span>
  <span m="1920480">if</span> <span m="1920680">I</span> <span m="1920750">zoom in</span>
  <span m="1921030">or</span> <span m="1921305">not,</span> <span m="1922160">but</span>
  <span m="1922290">the</span> <span m="1922420">same</span> <span m="1922700">thing</span>
  <span m="1922940">for</span> <span m="1923140">RK2.</span> <span m="1924033">As
  I</span> <span m="1924516">zoom</span> <span m="1924999">in</span> <span m="1925482">[INAUDIBLE],</span>
  <span m="1926448">I get</span> <span m="1926931">[INAUDIBLE]</span> <span m="1928380">stable,</span>
  <span m="1928980">right</span> <span m="1929300">term</span> <span m="1929560">being</span>
  <span m="1930080">unstable.</span> <span m="1930930">And</span> <span m="1931690">same</span>
  <span m="1931970">thing</span> <span m="1932290">for</span> <span m="1932660">[INAUDIBLE].</span>
  <span m="1934860">I get</span> <span m="1935300">the</span> <span m="1935390">behavior</span>
  <span m="1935930">that</span> <span m="1936670">on</span> <span m="1936810">the</span>
  <span m="1936890">left</span> <span m="1937080">hand side</span> <span m="1937570">is</span>
  <span m="1937945">stable,</span> <span m="1938670">on</span> <span m="1938810">the</span>
  <span m="1938880">right hand</span> <span m="1939170">side</span> <span m="1939490">is</span>
  <span m="1939650">unstable.</span> <span m="1940390">Yes?</span></p> <p><span m="1940720">AUDIENCE:
  [INAUDIBLE]</span></p> <p><span m="1948040">QIQI WANG: For the</span> <span m="1948180">Backward
  Euler,</span> <span m="1949070">I can</span> <span m="1949505">easily</span> <span
  m="1949940">[INAUDIBLE]</span> <span m="1950375">delta t,</span> <span m="1951245">and</span>
  <span m="1951680">it</span> <span m="1951910">actually</span> <span m="1952500">is</span>
  <span m="1952730">going</span> <span m="1952850">to</span> <span m="1952940">make</span>
  <span m="1953290">an</span> <span m="1953530">unstable</span> <span m="1953890">equation</span>
  <span m="1954250">stable,</span> <span m="1956030">yes.</span> <span m="1957210">That</span>
  <span m="1957460">actually</span> <span m="1957930">happens</span> <span m="1958740">with</span>
  <span m="1958970">some</span> <span m="1959680">PDEs.</span> <span m="1961080">Now,</span>
  <span m="1962780">you can even</span> <span m="1962990">sometimes,</span> <span
  m="1964406">for example,</span> <span m="1965220">[INAUDIBLE].</span> <span m="1968100">And</span>
  <span m="1968270">a</span> <span m="1968360">lot</span> <span m="1968560">of</span>
  <span m="1968680">the</span> <span m="1969540">fluid</span> <span m="1969880">flows</span>
  <span m="1970200">are</span> <span m="1970690">actually</span> <span m="1971480">unstable.</span>
  <span m="1972158">So if you''re</span> <span m="1972606">looking at,</span> <span
  m="1973054">for example,</span> <span m="1973502">water</span> <span m="1973950">shedding</span>
  <span m="1974850">behind the</span> <span m="1975130">[INAUDIBLE],</span> <span
  m="1975990">what</span> <span m="1976570">you</span> <span m="1976710">see</span>
  <span m="1977080">there</span> <span m="1977567">is</span> <span m="1978054">an</span>
  <span m="1978541">unstable</span> <span m="1979030">flow</span> <span m="1979190">field.</span>
  <span m="1979922">But</span> <span m="1980290">you</span> <span m="1980480">can</span>
  <span m="1980770">actually</span> <span m="1981170">get</span> <span m="1981370">a</span>
  <span m="1981470">stable</span> <span m="1981755">flow</span> <span m="1982040">field</span>
  <span m="1982290">if</span> <span m="1982770">you</span> <span m="1983250">use</span>
  <span m="1983410">Backward Euler.</span> <span m="1985146">You can</span> <span
  m="1985560">use</span> <span m="1985970">Backward Euler</span> <span m="1986580">with</span>
  <span m="1986950">a</span> <span m="1987310">really</span> <span m="1987770">[INAUDIBLE].</span></p>
  <p><span m="1989040">If</span> <span m="1989220">you</span> <span m="1989340">do</span>
  <span m="1989560">that,</span> <span m="1990520">you</span> <span m="1990630">can</span>
  <span m="1990850">actually</span> <span m="1991390">converge,</span> <span m="1991960">force</span>
  <span m="1992370">yourself</span> <span m="1992720">to</span> <span m="1993390">converge</span>
  <span m="1993970">to</span> <span m="1994140">an</span> <span m="1994350">actually</span>
  <span m="1995070">unstable</span> <span m="1995930">closed</span> <span m="1996230">solution.</span></p>
  <p><span m="1997616">AUDIENCE: [INAUDIBLE]</span></p> <p><span m="2001560">QIQI
  WANG: The question</span> <span m="2002053">is,</span> <span m="2002546">are</span>
  <span m="2003540">you</span> <span m="2004180">still</span> <span m="2004540">consistent?</span>
  <span m="2005310">The</span> <span m="2005570">question</span> <span m="2005880">of</span>
  <span m="2006070">consistency</span> <span m="2006530">is</span> <span m="2006990">for</span>
  <span m="2007450">ODEs.</span> <span m="2008890">If</span> <span m="2009850">we</span>
  <span m="2009960">find</span> <span m="2010260">that</span> <span m="2011030">lambda</span>
  <span m="2011140">delta t</span> <span m="2011380">goes to</span> <span m="2011813">zero,</span>
  <span m="2013980">consistency</span> <span m="2014600">means</span> <span m="2015310">the</span>
  <span m="2015600">[INAUDIBLE]</span> <span m="2016080">behavior</span> <span m="2016560">of</span>
  <span m="2017040">the</span> <span m="2017520">ODE</span> <span m="2017690">as</span>
  <span m="2017790">lambda delta t</span> <span m="2018270">goes to</span> <span m="2018710">0,</span>
  <span m="2019600">in</span> <span m="2019750">this</span> <span m="2019990">case,</span>
  <span m="2020353">that''s</span> <span m="2020716">always</span> <span m="2021510">consistent</span>
  <span m="2021975">because</span> <span m="2022650">if your</span> <span m="2022780">lambda
  delta t</span> <span m="2023590">goes to</span> <span m="2023830">0,</span> <span
  m="2025812">and</span> <span m="2026230">approximating</span> <span m="2026800">the</span>
  <span m="2026920">true</span> <span m="2027300">behavior</span> <span m="2027800">[INAUDIBLE].</span>
  <span m="2029890">Consistency</span> <span m="2030710">has</span> <span m="2030850">nothing</span>
  <span m="2031250">to</span> <span m="2031650">do</span> <span m="2032050">with</span>
  <span m="2032430">if</span> <span m="2032810">I</span> <span m="2033186">give</span>
  <span m="2033562">you</span> <span m="2033940">a</span> <span m="2034390">really
  big</span> <span m="2034870">delta t.</span> <span m="2036310">If I</span> <span
  m="2036790">give</span> <span m="2036940">it</span> <span m="2037030">a</span> <span
  m="2037090">really</span> <span m="2037440">big</span> <span m="2037650">delta</span>
  <span m="2037840">t,</span> <span m="2039170">then</span> <span m="2039770">it has</span>
  <span m="2040000">nothing to do</span> <span m="2040230">with</span> <span m="2040702">consistency.</span>
  <span m="2042118">Because</span> <span m="2043062">consistency</span> <span m="2044478">is</span>
  <span m="2044950">behavior</span> <span m="2045630">of</span> <span m="2045750">the</span>
  <span m="2045900">linear</span> <span m="2046377">[INAUDIBLE].</span></p> <p><span
  m="2049239">AUDIENCE: [INAUDIBLE]</span></p> <p><span m="2051147">QIQI WANG: Oh,</span>
  <span m="2051624">OK,</span> <span m="2052101">yes.</span> <span m="2053532">I</span>
  <span m="2054009">said</span> <span m="2054500">converges</span> <span m="2055030">in</span>
  <span m="2055350">a</span> <span m="2055610">different</span> <span m="2056080">sense.</span>
  <span m="2057330">So</span> <span m="2057520">the</span> <span m="2057922">convergence</span>
  <span m="2059128">we</span> <span m="2059530">are</span> <span m="2060030">talking</span>
  <span m="2060590">about</span> <span m="2060949">here,</span> <span m="2063412">as</span>
  <span m="2063810">I</span> <span m="2064219">decrease</span> <span m="2064647">my</span>
  <span m="2065075">delta t,</span> <span m="2066359">as</span> <span m="2066790">the
  numerical</span> <span m="2067610">approximates</span> <span m="2068045">the</span>
  <span m="2068480">analytical</span> <span m="2068906">solution,</span> <span m="2070610">what</span>
  <span m="2070909">I mean</span> <span m="2071312">over here is</span> <span m="2071715">that</span>
  <span m="2072120">when</span> <span m="2073130">[INAUDIBLE]</span> <span m="2074415">delta</span>
  <span m="2074878">t</span> <span m="2075804">is</span> <span m="2076270">low,</span>
  <span m="2077327">as</span> <span m="2077784">I''ve</span> <span m="2078241">[INAUDIBLE],</span>
  <span m="2081265">grows</span> <span m="2081520">closer</span> <span m="2081790">and</span>
  <span m="2082360">closer</span> <span m="2083560">to</span> <span m="2083699">a</span>
  <span m="2083909">solution</span> <span m="2084741">of the</span> <span m="2085159">time</span>
  <span m="2085530">independent</span> <span m="2086009">equation.</span></p> <p><span
  m="2089841">So that''s</span> <span m="2090989">what</span> <span m="2091270">I</span>
  <span m="2091768">was</span> <span m="2092266">saying</span> <span m="2092764">when</span>
  <span m="2093262">I</span> <span m="2093760">spoke</span> <span m="2094258">about</span>
  <span m="2094756">convergence</span> <span m="2095254">earlier.</span> <span m="2097760">It
  has</span> <span m="2098214">a--</span> <span m="2100484">I</span> <span m="2100938">think</span>
  <span m="2101392">that</span> <span m="2101846">this</span> <span m="2102300">is</span>
  <span m="2102700">not a</span> <span m="2103170">very</span> <span m="2103610">good</span>
  <span m="2105812">equation,</span> <span m="2106218">but</span> <span m="2107030">convergence</span>
  <span m="2107590">in</span> <span m="2107910">[INAUDIBLE].</span> <span m="2111170">One</span>
  <span m="2111410">thing</span> <span m="2111670">is</span> <span m="2112040">when</span>
  <span m="2112340">I</span> <span m="2112890">decrease</span> <span m="2113400">my</span>
  <span m="2114277">[INAUDIBLE]</span> <span m="2115211">time and</span> <span m="2115680">space,</span>
  <span m="2116190">I might</span> <span m="2116690">converge</span> <span m="2117080">in
  the analytical</span> <span m="2117580">solution.</span></p> <p><span m="2119080">The</span>
  <span m="2119110">second thing</span> <span m="2119585">is</span> <span m="2121010">in</span>
  <span m="2121300">an</span> <span m="2121660">iterative</span> <span m="2122100">scheme,</span>
  <span m="2123570">I</span> <span m="2123920">guess</span> <span m="2124270">you''re</span>
  <span m="2124360">going</span> <span m="2124440">to learn</span> <span m="2125130">more
  when</span> <span m="2125370">you</span> <span m="2125680">go</span> <span m="2126020">through</span>
  <span m="2127310">more</span> <span m="2128120">advanced</span> <span m="2128415">classes.</span>
  <span m="2128950">When</span> <span m="2129140">you</span> <span m="2129310">apply</span>
  <span m="2129840">an</span> <span m="2130060">iterative</span> <span m="2130510">scheme,</span>
  <span m="2132310">trying</span> <span m="2132730">to</span> <span m="2133213">compute</span>
  <span m="2133696">the</span> <span m="2134180">solution</span> <span m="2134980">to</span>
  <span m="2135400">a</span> <span m="2135660">steady</span> <span m="2135760">state</span>
  <span m="2136820">differential</span> <span m="2137070">equation,</span> <span m="2138110">these</span>
  <span m="2138360">states</span> <span m="2138640">are</span> <span m="2138980">[INAUDIBLE].</span>
  <span m="2140420">The</span> <span m="2140630">steady</span> <span m="2140750">state</span>
  <span m="2140880">never stops</span> <span m="2141110">closing.</span> <span m="2142710">And</span>
  <span m="2143200">as</span> <span m="2143510">I</span> <span m="2144110">increase</span>
  <span m="2145080">the</span> <span m="2145200">iterations,</span> <span m="2147233">do</span>
  <span m="2147704">I</span> <span m="2149588">get</span> <span m="2150060">closer</span>
  <span m="2150370">to</span> <span m="2150690">the</span> <span m="2150920">solution</span>
  <span m="2151490">of the</span> <span m="2151750">steady state</span> <span m="2152250">equation?</span>
  <span m="2154250">It''s</span> <span m="2154450">more</span> <span m="2154640">like</span>
  <span m="2154850">a</span> <span m="2154950">convergence</span> <span m="2155270">in
  the</span> <span m="2155590">sense</span> <span m="2155900">of</span> <span m="2156310">we</span>
  <span m="2156560">can</span> <span m="2156960">apply</span> <span m="2157360">Newton-Raphson.</span>
  <span m="2158726">We</span> <span m="2159172">can apply</span> <span m="2159620">Newton-Raphson</span>
  <span m="2160650">to</span> <span m="2160880">solve</span> <span m="2161850">the</span>
  <span m="2162350">founding</span> <span m="2162770">equations.</span> <span m="2163310">That</span>
  <span m="2163570">happens to be</span> <span m="2163830">more</span> <span m="2164160">[INAUDIBLE]</span>
  <span m="2164660">of</span> <span m="2165160">your</span> <span m="2165835">iterative</span>
  <span m="2166150">solution.</span> <span m="2167720">Convergence</span> <span m="2168100">moves,</span>
  <span m="2168480">as</span> <span m="2168790">I</span> <span m="2168920">do</span>
  <span m="2169600">more</span> <span m="2170300">Newton-Raphson</span> <span m="2171180">steps,</span>
  <span m="2171630">do</span> <span m="2171880">I</span> <span m="2172600">converge</span>
  <span m="2172910">to</span> <span m="2173030">the</span> <span m="2173700">solution</span>
  <span m="2173995">for the</span> <span m="2174290">[INAUDIBLE]</span> <span m="2174710">equation?</span></p>
  <p><span m="2176390">So</span> <span m="2176590">there</span> <span m="2176940">are</span>
  <span m="2177210">two</span> <span m="2178040">completely</span> <span m="2178340">different</span>
  <span m="2178690">concepts</span> <span m="2179110">of</span> <span m="2179565">convergence.</span>
  <span m="2180475">One</span> <span m="2180930">is,</span> <span m="2181230">as</span>
  <span m="2181490">I</span> <span m="2181920">decrease</span> <span m="2182240">both
  t</span> <span m="2182450">and</span> <span m="2182730">delta</span> <span m="2182980">x,</span>
  <span m="2183220">I get closer to a</span> <span m="2183685">solution.</span> <span
  m="2184510">The</span> <span m="2184690">second</span> <span m="2185175">is</span>
  <span m="2186580">as</span> <span m="2187030">I</span> <span m="2187260">why</span>
  <span m="2188310">iterate</span> <span m="2189610">more,</span> <span m="2190390">do</span>
  <span m="2190530">I</span> <span m="2190670">converge</span> <span m="2191130">to</span>
  <span m="2191440">a</span> <span m="2191670">solution?</span></p> <p><span m="2193619">AUDIENCE:
  [INAUDIBLE]</span> <span m="2210610">What about</span> <span m="2211030">[INAUDIBLE]</span>
  <span m="2247140">So what it''s</span> <span m="2247612">saying is</span> <span
  m="2248084">that</span> <span m="2248556">[INAUDIBLE].</span></p> <p><span m="2254220">QIQI
  WANG: Right.</span></p> <p><span m="2254958">AUDIENCE: [INAUDIBLE]</span></p> <p><span
  m="2301760">QIQI WANG: OK,</span> <span m="2302258">I''m--</span></p> <p><span m="2303254">AUDIENCE:
  [INAUDIBLE]</span></p> <p><span m="2307736">QIQI WANG: Yes,</span> <span m="2308234">so</span>
  <span m="2308750">I''m going</span> <span m="2309075">to</span> <span m="2309400">draw</span>
  <span m="2310340">what</span> <span m="2310803">[INAUDIBLE].</span> <span m="2312192">So</span>
  <span m="2312655">if</span> <span m="2313118">you look</span> <span m="2313581">at</span>
  <span m="2314044">one</span> <span m="2314507">where</span> <span m="2314970">there''s</span>
  <span m="2315090">[INAUDIBLE]</span> <span m="2315300">over here,</span> <span m="2315590">that</span>
  <span m="2316059">means</span> <span m="2316528">a lambda</span> <span m="2316997">that</span>
  <span m="2317466">is</span> <span m="2317935">that</span> <span m="2318404">type</span>
  <span m="2318638">of</span> <span m="2318873">property,</span> <span m="2320280">the</span>
  <span m="2320460">real</span> <span m="2320640">part--</span> <span m="2321360">and</span>
  <span m="2321550">if</span> <span m="2321690">you</span> <span m="2321780">look</span>
  <span m="2322010">at</span> <span m="2322110">the</span> <span m="2322230">analytical</span>
  <span m="2322870">solution,</span> <span m="2323550">the</span> <span m="2323700">analytical</span>
  <span m="2324180">solution</span> <span m="2324660">here is</span> <span m="2324910">something</span>
  <span m="2325280">that</span> <span m="2325540">oscillates</span> <span m="2326130">sinusoidally</span>
  <span m="2327120">while</span> <span m="2328140">growing</span> <span m="2328470">in
  magnitude</span> <span m="2328800">exponentially.</span> <span m="2330580">Right?</span>
  <span m="2331440">So</span> <span m="2332080">that''s</span> <span m="2332970">an</span>
  <span m="2333250">analytical</span> <span m="2333820">solution.</span></p> <p><span
  m="2334970">If</span> <span m="2335190">they</span> <span m="2335360">used</span>
  <span m="2335650">Backward Euler</span> <span m="2336790">with</span> <span m="2337070">a</span>
  <span m="2337170">small</span> <span m="2337920">time</span> <span m="2338210">step,</span>
  <span m="2339250">so</span> <span m="2339400">that</span> <span m="2339560">is</span>
  <span m="2339780">like</span> <span m="2340190">when your</span> <span m="2340600">lambda
  delta t</span> <span m="2341430">is</span> <span m="2341630">going</span> <span
  m="2341770">to</span> <span m="2341850">be</span> <span m="2342635">0.1,</span>
  <span m="2344290">with a</span> <span m="2344480">small</span> <span m="2344890">delta
  t,</span> <span m="2345020">you''re</span> <span m="2345468">[INAUDIBLE]</span>
  <span m="2346812">lambda</span> <span m="2347260">to</span> <span m="2347400">somewhere</span>
  <span m="2347830">close</span> <span m="2348210">to</span> <span m="2348300">the</span>
  <span m="2348420">origin.</span> <span m="2349530">So</span> <span m="2349600">you</span>
  <span m="2349780">may</span> <span m="2349990">get</span> <span m="2350920">a</span>
  <span m="2351030">solution</span> <span m="2351620">that</span> <span m="2352100">maybe</span>
  <span m="2352400">you</span> <span m="2352530">wouldn''t</span> <span m="2352870">get</span>
  <span m="2353110">exactly</span> <span m="2354360">the</span> <span m="2354580">right</span>
  <span m="2354860">behavior</span> <span m="2356160">because</span> <span m="2357770">unless</span>
  <span m="2357930">your</span> <span m="2358110">delta t</span> <span m="2358330">is</span>
  <span m="2358810">infinitely</span> <span m="2358860">small.</span> <span m="2359580">But</span>
  <span m="2359790">you</span> <span m="2360040">are</span> <span m="2360360">also</span>
  <span m="2360480">going</span> <span m="2360610">to</span> <span m="2360670">get</span>
  <span m="2360870">something</span> <span m="2361360">that</span> <span m="2361650">grows</span>
  <span m="2362160">exponentially</span> <span m="2362910">larger.</span></p> <p><span
  m="2364200">So</span> <span m="2364540">that</span> <span m="2364780">is</span>
  <span m="2365130">when</span> <span m="2365410">you</span> <span m="2365980">have</span>
  <span m="2366170">a</span> <span m="2366380">small</span> <span m="2368330">delta</span>
  <span m="2368500">t.</span> <span m="2369370">Now,</span> <span m="2369690">if</span>
  <span m="2369870">you</span> <span m="2369950">use</span> <span m="2370170">a</span>
  <span m="2370280">large</span> <span m="2370600">delta</span> <span m="2370950">t,</span>
  <span m="2371350">like</span> <span m="2371860">you</span> <span m="2372020">are</span>
  <span m="2372180">scaling</span> <span m="2373270">the</span> <span m="2373400">lambda
  delta t</span> <span m="2373910">to</span> <span m="2374050">somewhere</span> <span
  m="2376090">larger</span> <span m="2376460">along</span> <span m="2376950">the</span>
  <span m="2377440">same</span> <span m="2377930">line,</span> <span m="2378420">because</span>
  <span m="2378910">the</span> <span m="2379400">delta t is</span> <span m="2379890">real,</span>
  <span m="2381850">what</span> <span m="2382340">happens is that</span> <span m="2383320">we</span>
  <span m="2383810">get</span> <span m="2384300">a</span> <span m="2384790">stable</span>
  <span m="2384970">solution.</span> <span m="2386500">So</span> <span m="2387590">although</span>
  <span m="2388210">analytically</span> <span m="2388950">the</span> <span m="2389070">solution</span>
  <span m="2389550">grows</span> <span m="2389850">larger,</span> <span m="2390350">you</span>
  <span m="2390750">are</span> <span m="2390950">expected</span> <span m="2391600">to</span>
  <span m="2391690">get</span> <span m="2391990">a</span> <span m="2392060">solution</span>
  <span m="2392590">that</span> <span m="2392770">looks</span> <span m="2393100">more</span>
  <span m="2393340">like</span> <span m="2393550">this.</span> <span m="2396230">So
  it</span> <span m="2396430">is</span> <span m="2396710">going</span> <span m="2396840">to</span>
  <span m="2396910">get</span> <span m="2397120">to</span> <span m="2397320">the</span>
  <span m="2397530">wrong</span> <span m="2398030">answer</span> <span m="2398530">qualitatively</span>
  <span m="2400030">even.</span> <span m="2403760">And</span> <span m="2404100">of</span>
  <span m="2404270">course,</span> <span m="2404500">this is</span> <span m="2404770">because</span>
  <span m="2405180">you''re</span> <span m="2405350">using</span> <span m="2405660">a</span>
  <span m="2405730">super</span> <span m="2406090">large</span> <span m="2406550">delta</span>
  <span m="2407010">t.</span> <span m="2407470">You''re</span> <span m="2407680">using</span>
  <span m="2407970">a</span> <span m="2408060">delta t</span> <span m="2408570">that</span>
  <span m="2408780">is</span> <span m="2409560">actually</span> <span m="2410120">much</span>
  <span m="2410460">larger</span> <span m="2410950">than</span> <span m="2411710">1</span>
  <span m="2412160">over</span> <span m="2412610">the</span> <span m="2412720">magnitude</span>
  <span m="2413448">of</span> <span m="2413936">the</span> <span m="2416070">eigenvalue.</span>
  <span m="2419126">Right?</span> <span m="2420614">Does that</span> <span m="2421110">make</span>
  <span m="2421606">sense?</span> <span m="2423600">Yes?</span></p> <p><span m="2424858">AUDIENCE:
  [INAUDIBLE]</span></p> <p><span m="2456340">QIQI WANG: Yes.</span></p> <p><span
  m="2457198">AUDIENCE: [INAUDIBLE]</span></p> <p><span m="2474640">QIQI WANG: So
  you''re</span> <span m="2474810">asking a</span> <span m="2474840">very</span> <span
  m="2475200">good question.</span> <span m="2477064">So for</span> <span m="2477530">a</span>
  <span m="2478000">system</span> <span m="2478340">that is</span> <span m="2479040">analytically</span>
  <span m="2479860">unstable,</span> <span m="2480640">what is a</span> <span m="2480970">good</span>
  <span m="2481130">way</span> <span m="2481600">of</span> <span m="2482070">telling</span>
  <span m="2482540">my numerical</span> <span m="2483010">scheme is doing a</span>
  <span m="2483480">good</span> <span m="2483950">job</span> <span m="2484420">or</span>
  <span m="2484890">not?</span> <span m="2485220">This</span> <span m="2485360">is</span>
  <span m="2485940">a</span> <span m="2486130">much deeper</span> <span m="2486360">question</span>
  <span m="2486842">than I can</span> <span m="2487324">answer.</span> <span m="2488430">Yeah,</span>
  <span m="2489636">there</span> <span m="2490109">is</span> <span m="2490582">a</span>
  <span m="2491055">[INAUDIBLE].</span> <span m="2494839">If</span> <span m="2495320">the</span>
  <span m="2495800">solution</span> <span m="2496420">analytically</span> <span m="2497152">is</span>
  <span m="2497594">unstable,</span> <span m="2498920">that</span> <span m="2499170">means</span>
  <span m="2499890">to</span> <span m="2500240">approximate</span> <span m="2501030">using</span>
  <span m="2501472">numerical</span> <span m="2501914">methods</span> <span m="2502356">is</span>
  <span m="2502800">extremely</span> <span m="2503000">difficult.</span> <span m="2505000">If
  you</span> <span m="2505130">make</span> <span m="2505420">a</span> <span m="2505480">small</span>
  <span m="2505850">error</span> <span m="2506170">in</span> <span m="2506636">the</span>
  <span m="2507102">beginning,</span> <span m="2508966">even if you have</span> <span
  m="2509432">a</span> <span m="2509898">small</span> <span m="2510364">error let''s
  say</span> <span m="2510830">in terms of</span> <span m="2511296">[INAUDIBLE],</span>
  <span m="2512230">even</span> <span m="2512620">though</span> <span m="2512920">we''ll</span>
  <span m="2513340">assume</span> <span m="2513670">you are</span> <span m="2514066">doing</span>
  <span m="2514860">everything</span> <span m="2515630">exactly</span> <span m="2515940">starting</span>
  <span m="2516400">from</span> <span m="2517320">time step</span> <span m="2517780">0,</span>
  <span m="2518970">you''re still going</span> <span m="2519240">to</span> <span m="2519662">get</span>
  <span m="2520084">a</span> <span m="2520506">[INAUDIBLE]</span> <span m="2520928">error</span>
  <span m="2521350">as</span> <span m="2521580">you</span> <span m="2521770">come</span>
  <span m="2521973">to</span> <span m="2522176">here.</span> <span m="2523800">Just</span>
  <span m="2524070">because</span> <span m="2524510">the</span> <span m="2524640">equation</span>
  <span m="2524800">itself</span> <span m="2525220">is</span> <span m="2525642">unstable.</span>
  <span m="2526910">The</span> <span m="2527100">equation</span> <span m="2527220">itself</span>
  <span m="2527330">being</span> <span m="2527590">unstable</span> <span m="2527830">means</span>
  <span m="2528667">you can</span> <span m="2529154">make</span> <span m="2529641">a</span>
  <span m="2530128">small</span> <span m="2530615">perturbation</span> <span m="2531102">over
  here.</span> <span m="2531590">That</span> <span m="2531850">perturbation</span>
  <span m="2532347">will</span> <span m="2532844">[INAUDIBLE]</span> <span m="2533840">grow</span>
  <span m="2534240">larger</span> <span m="2534668">and</span> <span m="2535096">larger</span>
  <span m="2535524">as</span> <span m="2535952">we</span> <span m="2536380">integrate
  more</span> <span m="2536710">and</span> <span m="2537080">more.</span></p> <p><span
  m="2538710">So</span> <span m="2539964">treating</span> <span m="2540940">a</span>
  <span m="2541080">case</span> <span m="2541470">like</span> <span m="2541750">that</span>
  <span m="2542060">numerically</span> <span m="2543700">is</span> <span m="2543930">very</span>
  <span m="2544200">difficult.</span> <span m="2545110">And</span> <span m="2546180">if
  interested,</span> <span m="2546520">let''s</span> <span m="2547200">talk</span>
  <span m="2547470">more</span> <span m="2547650">about</span> <span m="2547860">that</span>
  <span m="2548040">after</span> <span m="2548535">class.</span> <span m="2551510">All
  right,</span> <span m="2551770">any</span> <span m="2552290">other</span> <span
  m="2554270">questions?</span> <span m="2556750">OK.</span> <span m="2559540">And</span>
  <span m="2559770">by</span> <span m="2560100">the</span> <span m="2560200">way,</span>
  <span m="2560360">that''s</span> <span m="2560800">something</span> <span m="2561150">I''m</span>
  <span m="2561370">actually</span> <span m="2561700">looking</span> <span m="2562050">at</span>
  <span m="2562140">in</span> <span m="2562220">my</span> <span m="2562340">research</span>
  <span m="2563290">right</span> <span m="2563704">now.</span> <span m="2565360">So</span>
  <span m="2565700">very</span> <span m="2566080">good</span> <span m="2566465">question.</span>
  <span m="2567235">I''m</span> <span m="2567620">very</span> <span m="2567960">impressed.</span></p>
  <p><span m="2568950">AUDIENCE: [INAUDIBLE]</span></p> <p><span m="2569940">QIQI
  WANG: Yeah,</span> <span m="2570450">that''s</span> <span m="2570720">why</span>
  <span m="2570940">people</span> <span m="2571270">can''t</span> <span m="2571560">predict</span>
  <span m="2571890">the</span> <span m="2571980">weather,</span> <span m="2572390">right?</span>
  <span m="2572720">I</span> <span m="2572770">mean,</span> <span m="2573070">they</span>
  <span m="2575100">try</span> <span m="2575350">to</span> <span m="2575470">solve</span>
  <span m="2575710">a</span> <span m="2575800">PDE</span> <span m="2576270">to</span>
  <span m="2576400">get</span> <span m="2576600">the</span> <span m="2576710">weather</span>
  <span m="2577810">seven</span> <span m="2578120">days</span> <span m="2578360">later.</span>
  <span m="2578800">But</span> <span m="2578970">you</span> <span m="2579100">know</span>
  <span m="2579340">it''s</span> <span m="2579580">going</span> <span m="2579720">to</span>
  <span m="2579790">be</span> <span m="2580255">a</span> <span m="2580610">not</span>
  <span m="2580860">very</span> <span m="2581120">good</span> <span m="2581310">solution</span>
  <span m="2582120">by</span> <span m="2582280">experience.</span> <span m="2585400">So</span>
  <span m="2585550">that''s</span> <span m="2585790">exactly</span> <span m="2586270">what</span>
  <span m="2586460">they''re</span> <span m="2586630">trying</span> <span m="2586820">to</span>
  <span m="2586910">do,</span> <span m="2587560">solve</span> <span m="2587810">an</span>
  <span m="2588308">unstable</span> <span m="2589304">system</span> <span m="2590800">forward
  in</span> <span m="2591270">time</span> <span m="2591640">for</span> <span m="2592090">something</span>
  <span m="2592340">like</span> <span m="2592520">seven</span> <span m="2592870">days.</span></p>
  <p><span m="2595880">All right.</span> <span m="2598750">OK.</span> <span m="2600250">I</span>
  <span m="2600620">got</span> <span m="2600860">a</span> <span m="2600900">question</span>
  <span m="2601330">of,</span> <span m="2602630">what</span> <span m="2602860">is</span>
  <span m="2603080">the</span> <span m="2603260">advantage,</span> <span m="2603890">what</span>
  <span m="2604090">is</span> <span m="2604240">the</span> <span m="2604320">main</span>
  <span m="2605000">advantage</span> <span m="2605640">and</span> <span m="2605770">disadvantage</span>
  <span m="2606620">of</span> <span m="2607240">explicit</span> <span m="2608110">versus</span>
  <span m="2608620">implicit</span> <span m="2610111">methods?</span> <span m="2610610">Let''s</span>
  <span m="2611100">do</span> <span m="2611360">a</span> <span m="2612270">comparison</span>
  <span m="2612900">here.</span></p> <p><span m="2621130">You</span> <span m="2621300">all</span>
  <span m="2621590">did</span> <span m="2621700">the</span> <span m="2621830">project.</span>
  <span m="2622723">So</span> <span m="2623450">you</span> <span m="2623705">all</span>
  <span m="2624290">kind</span> <span m="2624480">of</span> <span m="2624630">know</span>
  <span m="2625030">the</span> <span m="2625610">disadvantage</span> <span m="2625950">of</span>
  <span m="2626852">an</span> <span m="2627303">implicit</span> <span m="2627754">method.</span>
  <span m="2629110">What</span> <span m="2629310">is</span> <span m="2629460">that?</span></p>
  <p><span m="2630666">AUDIENCE: [INAUDIBLE]</span></p> <p><span m="2632380">QIQI
  WANG: A</span> <span m="2632450">lot</span> <span m="2632700">of</span> <span m="2632860">coding,</span>
  <span m="2633300">right?</span> <span m="2635490">Why</span> <span m="2635880">lots</span>
  <span m="2636080">of</span> <span m="2636200">coding?</span></p> <p><span m="2639921">AUDIENCE:
  [INAUDIBLE]</span></p> <p><span m="2642710">QIQI WANG: You</span> <span m="2642880">have</span>
  <span m="2643060">to</span> <span m="2643190">solve</span> <span m="2643530">a</span>
  <span m="2643720">non-linear</span> <span m="2644360">equation.</span> <span m="2645210">Solve</span>
  <span m="2647020">non-linear</span> <span m="2649640">equation,</span> <span m="2650630">right,</span>
  <span m="2651680">in</span> <span m="2652070">every</span> <span m="2652560">time</span>
  <span m="2652910">step.</span> <span m="2654480">And</span> <span m="2654750">the</span>
  <span m="2654920">way</span> <span m="2655090">we</span> <span m="2655230">solve</span>
  <span m="2655490">it</span> <span m="2655590">is</span> <span m="2655750">using</span>
  <span m="2656320">Newton-Raphson.</span> <span m="2657310">So</span> <span m="2658500">we</span>
  <span m="2658690">have</span> <span m="2658880">to</span> <span m="2660430">apply</span>
  <span m="2661230">Newton-Raphson</span> <span m="2661990">equation</span> <span
  m="2662680">within</span> <span m="2663610">every</span> <span m="2664160">time</span>
  <span m="2664530">step.</span> <span m="2665160">That</span> <span m="2665420">means</span>
  <span m="2666130">a</span> <span m="2666210">nested</span> <span m="2666870">loop</span>
  <span m="2667980">within</span> <span m="2668360">every</span> <span m="2668870">time</span>
  <span m="2669160">step.</span> <span m="2670270">So</span> <span m="2670400">you
  have</span> <span m="2670510">an</span> <span m="2670590">outer</span> <span m="2670920">loop</span>
  <span m="2671230">that</span> <span m="2671430">is</span> <span m="2671690">looping</span>
  <span m="2672080">through</span> <span m="2672400">the</span> <span m="2672805">time</span>
  <span m="2673210">step.</span> <span m="2673530">Within</span> <span m="2673780">the</span>
  <span m="2673880">outer</span> <span m="2674190">loop,</span> <span m="2674450">you</span>
  <span m="2674570">need</span> <span m="2674760">to</span> <span m="2674870">have</span>
  <span m="2675070">the inner</span> <span m="2675510">loop</span> <span m="2676890">that</span>
  <span m="2677090">does</span> <span m="2677660">Newton-Raphson</span> <span m="2677980">iteration.</span>
  <span m="2679200">So</span> <span m="2679570">of</span> <span m="2679740">course,</span>
  <span m="2680090">it''s</span> <span m="2680120">much</span> <span m="2680360">more</span>
  <span m="2680620">complicated</span> <span m="2681280">than</span> <span m="2681830">explicit</span>
  <span m="2682300">schemes,</span> <span m="2682770">right?</span> <span m="2684180">Where</span>
  <span m="2688820">you don''t</span> <span m="2689270">need</span> <span m="2689520">to</span>
  <span m="2689690">solve</span> <span m="2690120">any</span> <span m="2690970">non-linear</span>
  <span m="2691430">equations.</span> <span m="2691910">That''s</span> <span m="2692140">why</span>
  <span m="2692390">it</span> <span m="2692630">is</span> <span m="2693320">explicit,</span>
  <span m="2694775">right?</span></p> <p><span m="2696230">OK,</span> <span m="2697070">but</span>
  <span m="2697390">now,</span> <span m="2697660">what</span> <span m="2697840">is</span>
  <span m="2698030">the</span> <span m="2698220">advantage</span> <span m="2699090">of</span>
  <span m="2701850">implicit</span> <span m="2702380">schemes?</span></p> <p><span
  m="2703850">AUDIENCE: [INAUDIBLE]</span></p> <p><span m="2705870">QIQI WANG: It''s</span>
  <span m="2706240">way</span> <span m="2706760">more</span> <span m="2707320">accurate.</span>
  <span m="2708470">But</span> <span m="2708730">I</span> <span m="2709430">wouldn''t</span>
  <span m="2709770">hold</span> <span m="2710010">that</span> <span m="2711010">as</span>
  <span m="2711270">a</span> <span m="2711380">rule.</span> <span m="2711740">I</span>
  <span m="2711810">mean,</span> <span m="2713050">in</span> <span m="2713530">the</span>
  <span m="2713620">problem,</span> <span m="2714470">yes.</span> <span m="2714840">We</span>
  <span m="2715110">used</span> <span m="2716272">an</span> <span m="2716650">implicit</span>
  <span m="2717300">scheme</span> <span m="2718150">that</span> <span m="2718410">turns</span>
  <span m="2718670">out to be</span> <span m="2718800">way</span> <span m="2718990">more</span>
  <span m="2719190">accurate.</span> <span m="2720345">But</span> <span m="2720730">the</span>
  <span m="2720900">reason</span> <span m="2721640">may</span> <span m="2721910">just</span>
  <span m="2722333">be</span> <span m="2723180">our</span> <span m="2723760">implicit</span>
  <span m="2724050">scheme</span> <span m="2724511">is</span> <span m="2724972">eigenvalue</span>
  <span m="2725433">stable,</span> <span m="2725894">right?</span> <span m="2727740">The</span>
  <span m="2727910">explicit</span> <span m="2728245">scheme</span> <span m="2729060">we</span>
  <span m="2729290">were</span> <span m="2729530">using</span> <span m="2729950">was</span>
  <span m="2730230">[INAUDIBLE].</span> <span m="2731230">That</span> <span m="2731730">turns</span>
  <span m="2732000">out to</span> <span m="2732470">be</span> <span m="2732620">eigenvalue</span>
  <span m="2733150">stable</span> <span m="2733560">only</span> <span m="2733900">along</span>
  <span m="2734380">the</span> <span m="2734760">imaginary</span> <span m="2735300">axis.</span>
  <span m="2739024">So</span> <span m="2739810">accuracy</span> <span m="2742230">is</span>
  <span m="2742370">actually</span> <span m="2743020">not</span> <span m="2743490">the</span>
  <span m="2743750">main</span> <span m="2744140">driver</span> <span m="2745470">of</span>
  <span m="2746030">people</span> <span m="2746570">adopting</span> <span m="2747006">implicit</span>
  <span m="2747442">schemes</span> <span m="2748750">over</span> <span m="2749190">explicit</span>
  <span m="2749410">schemes.</span></p> <p><span m="2750402">AUDIENCE: [INAUDIBLE]</span></p>
  <p><span m="2752390">QIQI WANG: Yes,</span> <span m="2752740">the</span> <span m="2752830">main</span>
  <span m="2753180">driver</span> <span m="2754020">is a</span> <span m="2754410">larger</span>
  <span m="2755010">stability</span> <span m="2755480">region.</span> <span m="2763400">Larger</span>
  <span m="2764170">stability</span> <span m="2764910">region,</span> <span m="2765190">as
  we</span> <span m="2765350">were</span> <span m="2765830">just</span> <span m="2766140">looking</span>
  <span m="2766600">at.</span> <span m="2766980">OK,</span> <span m="2767960">just</span>
  <span m="2768180">for</span> <span m="2768450">example,</span> <span m="2768860">compare</span>
  <span m="2769290">Forward Euler</span> <span m="2770030">with</span> <span m="2770990">Backward
  Euler.</span> <span m="2772890">Forward Euler,</span> <span m="2774706">tiny,</span>
  <span m="2775590">right?</span> <span m="2777720">Backward Euler,</span> <span m="2781220">the</span>
  <span m="2781360">region</span> <span m="2781730">where it''s</span> <span m="2782110">unstable</span>
  <span m="2782380">is</span> <span m="2782775">tiny,</span> <span m="2783960">right?</span>
  <span m="2784260">That''s</span> <span m="2784470">kind</span> <span m="2784640">of</span>
  <span m="2784760">an</span> <span m="2784900">extreme</span> <span m="2785230">comparison,</span>
  <span m="2786280">but</span> <span m="2786530">gets</span> <span m="2786830">the</span>
  <span m="2787130">point</span> <span m="2787430">through.</span> <span m="2788880">Yes?</span></p>
  <p><span m="2790380">AUDIENCE: [INAUDIBLE]</span></p> <p><span m="2802380">QIQI
  WANG: OK,</span> <span m="2802650">good</span> <span m="2802840">point.</span> <span
  m="2803590">What</span> <span m="2803820">happens</span> <span m="2804240">if</span>
  <span m="2804870">Newton-Raphson</span> <span m="2805755">doesn''t</span> <span
  m="2806180">converge</span> <span m="2806420">in</span> <span m="2806640">the</span>
  <span m="2806960">implicit</span> <span m="2807490">method?</span> <span m="2808690">And</span>
  <span m="2808880">now,</span> <span m="2809100">when</span> <span m="2809390">you</span>
  <span m="2809500">say</span> <span m="2809760">converge,</span> <span m="2810270">you
  don''t</span> <span m="2810710">mean</span> <span m="2811080">as</span> <span m="2811820">delta</span>
  <span m="2811990">t</span> <span m="2812120">and</span> <span m="2812460">delta
  s</span> <span m="2812800">go</span> <span m="2813270">to 0, right?</span> <span
  m="2813760">You</span> <span m="2813910">mean</span> <span m="2814200">as</span>
  <span m="2814490">my</span> <span m="2814930">iteration</span> <span m="2815290">goes</span>
  <span m="2815970">to</span> <span m="2816170">infinity,</span> <span m="2816604">doesn''t
  converge?</span></p> <p><span m="2818340">So</span> <span m="2818680">it''s</span>
  <span m="2818840">a</span> <span m="2818880">very</span> <span m="2819130">good</span>
  <span m="2819290">point.</span> <span m="2820664">Because</span> <span m="2822040">yes,</span>
  <span m="2822440">if</span> <span m="2822640">you</span> <span m="2822730">have</span>
  <span m="2822940">a</span> <span m="2823200">very</span> <span m="2824025">non-linear</span>
  <span m="2824500">problem,</span> <span m="2826220">if</span> <span m="2826400">you</span>
  <span m="2826490">use</span> <span m="2826920">a super</span> <span m="2827410">high</span>
  <span m="2827900">delta t,</span> <span m="2829100">it''s</span> <span m="2829330">quite</span>
  <span m="2829760">possible</span> <span m="2830205">your</span> <span m="2830650">Newton-Raphson</span>
  <span m="2831095">doesn''t</span> <span m="2831540">converge.</span> <span m="2833320">So</span>
  <span m="2834936">if</span> <span m="2835312">you</span> <span m="2835690">use</span>
  <span m="2836010">implicit</span> <span m="2836360">methods,</span> <span m="2837250">there</span>
  <span m="2837620">is</span> <span m="2837860">actually</span> <span m="2839100">an</span>
  <span m="2839490">implicit</span> <span m="2839980">restriction</span> <span m="2840946">on</span>
  <span m="2841429">delta t</span> <span m="2842880">in</span> <span m="2843070">which</span>
  <span m="2843740">you</span> <span m="2843900">cannot</span> <span m="2844520">get</span>
  <span m="2844950">through</span> <span m="2845780">this</span> <span m="2845950">eigenvalue</span>
  <span m="2846550">stability</span> <span m="2846880">analysis.</span> <span m="2847710">It</span>
  <span m="2847870">is</span> <span m="2848200">actually</span> <span m="2849020">a</span>
  <span m="2849340">delta</span> <span m="2849765">t</span> <span m="2851000">that</span>
  <span m="2852210">is</span> <span m="2852610">going</span> <span m="2852870">to</span>
  <span m="2853050">enable</span> <span m="2853325">it</span> <span m="2853600">to</span>
  <span m="2854068">converge</span> <span m="2854536">rapidly</span> <span m="2855004">with</span>
  <span m="2855472">Newton-Raphson</span> <span m="2855940">equation.</span></p> <p><span
  m="2858280">So</span> <span m="2858860">one</span> <span m="2859210">thing</span>
  <span m="2860430">I</span> <span m="2860530">think</span> <span m="2860890">you</span>
  <span m="2861620">can--</span> <span m="2861970">by</span> <span m="2862130">just</span>
  <span m="2862390">a</span> <span m="2862470">little</span> <span m="2862700">bit</span>
  <span m="2862860">of</span> <span m="2862960">analysis</span> <span m="2863410">you</span>
  <span m="2863510">can</span> <span m="2863690">find</span> <span m="2863950">out
  is</span> <span m="2864430">that</span> <span m="2866690">as</span> <span m="2866940">I</span>
  <span m="2867366">decrease</span> <span m="2867792">my</span> <span m="2868218">delta
  t,</span> <span m="2869070">my</span> <span m="2869670">Newton-Raphson</span> <span
  m="2870570">is</span> <span m="2870800">going</span> <span m="2870920">to</span>
  <span m="2870990">have</span> <span m="2871450">a much</span> <span m="2871760">easier</span>
  <span m="2872150">time to</span> <span m="2872594">converge.</span> <span m="2874370">In</span>
  <span m="2874610">fact,</span> <span m="2875300">if</span> <span m="2875450">my</span>
  <span m="2875590">delta t</span> <span m="2876170">is very</span> <span m="2876590">small,</span>
  <span m="2877970">then</span> <span m="2878430">my</span> <span m="2878890">Newton-Raphson,</span>
  <span m="2879810">I''m</span> <span m="2880790">going to have a</span> <span m="2881130">very</span>
  <span m="2881950">good</span> <span m="2882330">initial</span> <span m="2882790">guess</span>
  <span m="2883900">of</span> <span m="2884290">my</span> <span m="2884680">Newton-Raphson.</span>
  <span m="2884990">Because</span> <span m="2885470">if</span> <span m="2885660">my</span>
  <span m="2885970">delta t</span> <span m="2886570">is</span> <span m="2886830">very</span>
  <span m="2887070">small,</span> <span m="2887510">then</span> <span m="2887990">my</span>
  <span m="2888170">next</span> <span m="2889150">step</span> <span m="2889400">solution</span>
  <span m="2889870">is</span> <span m="2890060">going to be</span> <span m="2890400">pretty</span>
  <span m="2890690">close</span> <span m="2891200">to</span> <span m="2891290">my</span>
  <span m="2891430">current</span> <span m="2891900">time step</span> <span m="2892382">solution.</span>
  <span m="2893346">Right?</span></p> <p><span m="2895190">The</span> <span m="2895710">change</span>
  <span m="2896050">of</span> <span m="2896160">the</span> <span m="2896250">state</span>
  <span m="2896550">over</span> <span m="2896750">the two</span> <span m="2896920">steps</span>
  <span m="2897324">wouldn''t</span> <span m="2897728">be</span> <span m="2898132">that</span>
  <span m="2898536">large.</span> <span m="2898940">And</span> <span m="2899270">Newton-Raphson</span>
  <span m="2901130">will</span> <span m="2901470">always</span> <span m="2901930">converge</span>
  <span m="2903160">if</span> <span m="2903350">your</span> <span m="2903480">initial</span>
  <span m="2903930">guess</span> <span m="2904670">is</span> <span m="2905100">close</span>
  <span m="2905470">enough.</span> <span m="2908362">So</span> <span m="2908850">that''s</span>
  <span m="2910350">the</span> <span m="2910540">nature</span> <span m="2910890">of</span>
  <span m="2911220">Newton-Raphson</span> <span m="2911510">because</span> <span m="2911860">it</span>
  <span m="2912160">uses</span> <span m="2912370">a</span> <span m="2912760">linear</span>
  <span m="2913080">approximation</span> <span m="2913770">to</span> <span m="2914250">get</span>
  <span m="2914550">the</span> <span m="2914680">root</span> <span m="2915370">of</span>
  <span m="2915700">that</span> <span m="2916170">linear</span> <span m="2916330">approximation.</span>
  <span m="2918050">I</span> <span m="2918150">can</span> <span m="2918540">talk</span>
  <span m="2918790">more about</span> <span m="2918950">that.</span></p> <p><span
  m="2920320">But if</span> <span m="2920490">you</span> <span m="2920770">have</span>
  <span m="2921000">a</span> <span m="2921200">close</span> <span m="2921710">enough</span>
  <span m="2922120">initial</span> <span m="2922640">guess,</span> <span m="2923420">Newton-Raphson</span>
  <span m="2923920">will</span> <span m="2924040">always</span> <span m="2924380">converge.</span>
  <span m="2925400">Therefore,</span> <span m="2926430">by</span> <span m="2927160">decreasing,</span>
  <span m="2927890">if</span> <span m="2928250">Newton-Raphson</span> <span m="2929230">doesn''t</span>
  <span m="2929470">converge,</span> <span m="2930362">a</span> <span m="2930810">very</span>
  <span m="2931600">straightforward</span> <span m="2932410">recipe</span> <span m="2932881">is</span>
  <span m="2933352">decrease your</span> <span m="2933823">delta t.</span> <span m="2935240">And</span>
  <span m="2935450">that</span> <span m="2935690">is</span> <span m="2935880">going</span>
  <span m="2936050">to</span> <span m="2936190">make</span> <span m="2936540">the</span>
  <span m="2936630">change</span> <span m="2936930">between</span> <span m="2937190">one</span>
  <span m="2937460">state</span> <span m="2937770">and</span> <span m="2937940">the</span>
  <span m="2938110">next</span> <span m="2938880">time step</span> <span m="2939260">state</span>
  <span m="2940190">closer,</span> <span m="2940910">and</span> <span m="2941100">therefore</span>
  <span m="2942120">give</span> <span m="2942380">you</span> <span m="2942980">a</span>
  <span m="2943350">much better</span> <span m="2943530">initial</span> <span m="2943890">guess</span>
  <span m="2944325">to</span> <span m="2944760">Newton-Raphson.</span> <span m="2946500">And
  that</span> <span m="2946770">is</span> <span m="2946900">going</span> <span m="2947030">to</span>
  <span m="2947110">allow you</span> <span m="2947490">to converge</span> <span m="2948010">much</span>
  <span m="2948950">easier.</span> <span m="2953560">So</span> <span m="2953720">yes,</span>
  <span m="2954690">Newton-Raphson</span> <span m="2954950">actually</span> <span
  m="2955350">can</span> <span m="2955570">diverge</span> <span m="2956810">if</span>
  <span m="2958110">you</span> <span m="2958250">have</span> <span m="2958410">a</span>
  <span m="2958480">super</span> <span m="2958790">non-linear</span> <span m="2959310">problem</span>
  <span m="2959725">and</span> <span m="2960140">you use</span> <span m="2960555">a</span>
  <span m="2960970">super</span> <span m="2961280">large</span> <span m="2961570">time
  step.</span></p> <p><span m="2966916">AUDIENCE: [INAUDIBLE]</span></p> <p><span
  m="2977150">QIQI WANG: Oh,</span> <span m="2977310">yes.</span> <span m="2978010">By</span>
  <span m="2978140">the</span> <span m="2978230">way,</span> <span m="2978360">I</span>
  <span m="2978480">can</span> <span m="2978670">make</span> <span m="2978840">the</span>
  <span m="2978960">same</span> <span m="2979337">argument</span> <span m="2979714">for</span>
  <span m="2980470">[INAUDIBLE].</span> <span m="2981454">If I get</span> <span m="2981946">an</span>
  <span m="2982438">unstable</span> <span m="2982930">system,</span> <span m="2983190">I</span>
  <span m="2983280">can</span> <span m="2983480">always</span> <span m="2984120">decrease</span>
  <span m="2984520">the</span> <span m="2984943">time</span> <span m="2985366">step</span>
  <span m="2985790">so</span> <span m="2986290">that</span> <span m="2986600">I</span>
  <span m="2986963">get</span> <span m="2987326">into the</span> <span m="2987690">stability</span>
  <span m="2988166">region</span> <span m="2988642">of</span> <span m="2989118">the</span>
  <span m="2989594">implicit</span> <span m="2990070">scheme.</span> <span m="2991030">That
  is</span> <span m="2991410">still</span> <span m="2992756">except</span> <span m="2993140">for</span>
  <span m="2994484">the</span> <span m="2994916">time</span> <span m="2995348">step</span>
  <span m="2996212">restriction</span> <span m="2996720">for</span> <span m="2996940">Newton-Raphson,</span>
  <span m="2997874">we</span> <span m="2998341">said</span> <span m="2998810">over</span>
  <span m="2999223">here,</span> <span m="3000050">is</span> <span m="3000340">set</span>
  <span m="3000540">by</span> <span m="3000883">a</span> <span m="3001226">different</span>
  <span m="3001570">mechanism</span> <span m="3002287">as</span> <span m="3002684">the</span>
  <span m="3003740">largest</span> <span m="3004320">delta t</span> <span m="3004820">I
  can handle</span> <span m="3005270">up here.</span></p> <p><span m="3005880">The</span>
  <span m="3005980">largest</span> <span m="3006240">delta t</span> <span m="3006600">I
  can</span> <span m="3006710">use</span> <span m="3007540">in the</span> <span m="3007965">explicit</span>
  <span m="3008690">step</span> <span m="3008970">is</span> <span m="3009240">done</span>
  <span m="3009450">by</span> <span m="3009670">how</span> <span m="3009960">large,</span>
  <span m="3010391">by a larger</span> <span m="3010822">eigenvalue.</span> <span
  m="3012550">It</span> <span m="3012670">is</span> <span m="3012890">really--</span>
  <span m="3013695">we can</span> <span m="3014080">really</span> <span m="3014330">obtain</span>
  <span m="3014550">it</span> <span m="3014977">from a</span> <span m="3015404">linear</span>
  <span m="3016260">analysis.</span> <span m="3016670">And</span> <span m="3016900">linearizing</span>
  <span m="3017347">the</span> <span m="3017794">equation</span> <span m="3018241">[INAUDIBLE]</span>
  <span m="3019135">the largest</span> <span m="3019582">eigenvalue,</span> <span
  m="3020480">I</span> <span m="3020610">can</span> <span m="3020780">find</span>
  <span m="3021020">out</span> <span m="3021180">what</span> <span m="3021340">is</span>
  <span m="3021470">the</span> <span m="3021870">largest</span> <span m="3022270">time</span>
  <span m="3022670">step I can</span> <span m="3022860">take</span> <span m="3023294">here.</span>
  <span m="3025030">So</span> <span m="3025530">[INAUDIBLE]</span> <span m="3025750">the</span>
  <span m="3026237">implicit</span> <span m="3026724">method</span> <span m="3027211">is</span>
  <span m="3027700">governed</span> <span m="3028010">by</span> <span m="3028580">if</span>
  <span m="3028930">Newton-Raphson</span> <span m="3029490">converges.</span> <span
  m="3030570">And</span> <span m="3031040">Newton-Raphson</span> <span m="3031180">will</span>
  <span m="3031600">always</span> <span m="3032240">converge</span> <span m="3032660">in
  one</span> <span m="3032940">step</span> <span m="3033300">if I</span> <span m="3033500">have</span>
  <span m="3033730">a</span> <span m="3033820">linear</span> <span m="3034306">equation.</span>
  <span m="3037222">Newton-Raphson</span> <span m="3038194">will</span> <span m="3038680">converge</span>
  <span m="3039050">in</span> <span m="3039470">one</span> <span m="3039823">single</span>
  <span m="3040176">step</span> <span m="3040530">if</span> <span m="3040750">I have</span>
  <span m="3040970">a</span> <span m="3041150">linear</span> <span m="3041590">equation.</span></p>
  <p><span m="3043540">So</span> <span m="3043905">the</span> <span m="3044270">time</span>
  <span m="3044490">step</span> <span m="3044600">restriction</span> <span m="3044970">here</span>
  <span m="3045422">is</span> <span m="3045874">set</span> <span m="3046326">by</span>
  <span m="3046778">the convergence</span> <span m="3047230">of</span> <span m="3047682">Newton-Raphson,</span>
  <span m="3049040">not by</span> <span m="3049480">the</span> <span m="3049941">eigenvalue</span>
  <span m="3050402">step,</span> <span m="3050863">right?</span> <span m="3051785">How
  non-linear</span> <span m="3052246">the</span> <span m="3052707">equation</span>
  <span m="3053168">is.</span> <span m="3055020">So</span> <span m="3055720">there</span>
  <span m="3055890">are</span> <span m="3056090">some</span> <span m="3056960">integration</span>
  <span m="3057210">methods</span> <span m="3058380">where</span> <span m="3058720">people</span>
  <span m="3059360">actually</span> <span m="3060000">separate</span> <span m="3060550">out</span>
  <span m="3061740">the</span> <span m="3063030">linear</span> <span m="3063490">part</span>
  <span m="3064240">that</span> <span m="3064470">has</span> <span m="3064750">super</span>
  <span m="3065086">large</span> <span m="3065870">eigenvalues</span> <span m="3066990">and</span>
  <span m="3067860">the</span> <span m="3067980">non-linear</span> <span m="3068140">part.</span></p>
  <p><span m="3069000">So</span> <span m="3069520">for</span> <span m="3069760">a
  linear</span> <span m="3070170">part</span> <span m="3070320">that</span> <span
  m="3070650">has</span> <span m="3070980">super large</span> <span m="3071390">eigenvalues,</span>
  <span m="3071838">they do it</span> <span m="3072286">implicitly.</span> <span m="3073630">And
  for the</span> <span m="3074250">non-linear</span> <span m="3074440">part,</span>
  <span m="3074760">they do it</span> <span m="3075206">explicitly.</span> <span m="3076544">And</span>
  <span m="3076990">there''s</span> <span m="3077436">a</span> <span m="3077882">class
  of</span> <span m="3078330">methods</span> <span m="3078630">for</span> <span m="3079123">the</span>
  <span m="3079616">[INAUDIBLE].</span> <span m="3081590">Fancy name,</span> <span
  m="3081690">but</span> <span m="3081945">short</span> <span m="3082200">for</span>
  <span m="3083630">implicit,</span> <span m="3084080">explicit</span> <span m="3084482">methods</span>
  <span m="3085690">that</span> <span m="3085910">creates</span> <span m="3086450">different</span>
  <span m="3086830">parts</span> <span m="3087050">of</span> <span m="3087150">the</span>
  <span m="3087250">equation,</span> <span m="3088790">either</span> <span m="3089290">explicitly</span>
  <span m="3090250">or</span> <span m="3090870">implicitly.</span> <span m="3092420">And</span>
  <span m="3092910">as</span> <span m="3093130">you</span> <span m="3093220">can</span>
  <span m="3093420">guess,</span> <span m="3094130">the</span> <span m="3094250">part</span>
  <span m="3094640">they</span> <span m="3095020">treat</span> <span m="3095400">implicitly</span>
  <span m="3096350">is</span> <span m="3096620">going</span> <span m="3096770">to</span>
  <span m="3096840">be</span> <span m="3096960">the</span> <span m="3098030">linear</span>
  <span m="3098435">part</span> <span m="3099650">that</span> <span m="3099970">has</span>
  <span m="3101040">super large</span> <span m="3101800">eigenvalues.</span> <span
  m="3102940">So</span> <span m="3103090">that</span> <span m="3103260">you</span>
  <span m="3103380">converge</span> <span m="3103750">in</span> <span m="3104120">one</span>
  <span m="3104440">step,</span> <span m="3105140">you can do</span> <span m="3105830">Newton-Raphson,</span>
  <span m="3106050">and you</span> <span m="3106210">avoid</span> <span m="3107070">the</span>
  <span m="3107922">time step</span> <span m="3108270">restriction</span> <span m="3108625">set</span>
  <span m="3108980">by the</span> <span m="3109474">large</span> <span m="3109968">eigenvalues.</span></p>
  <p><span m="3114420">All</span> <span m="3114570">right,</span> <span m="3114840">OK.</span>
  <span m="3118390">Right.</span> <span m="3119240">So</span> <span m="3119370">this</span>
  <span m="3121050">is</span> <span m="3121230">really</span> <span m="3124000">especially</span>
  <span m="3124540">in</span> <span m="3124950">stiff</span> <span m="3125230">problems.</span>
  <span m="3129560">And</span> <span m="3129730">what</span> <span m="3129920">is</span>
  <span m="3130220">a stiff</span> <span m="3130380">problem?</span> <span m="3131752">A</span>
  <span m="3132170">stiff</span> <span m="3132340">problem</span> <span m="3132820">is</span>
  <span m="3133040">actually</span> <span m="3133450">defined</span> <span m="3135580">in</span>
  <span m="3135820">terms</span> <span m="3136190">of</span> <span m="3137200">if</span>
  <span m="3137660">you</span> <span m="3138030">use</span> <span m="3138415">an</span>
  <span m="3138800">explicit</span> <span m="3139230">integration</span> <span m="3139570">scheme.</span></p>
  <p><span m="3141330">If you find</span> <span m="3141800">yourself</span> <span
  m="3145570">having</span> <span m="3145990">to use</span> <span m="3146366">a</span>
  <span m="3146742">super</span> <span m="3147120">small</span> <span m="3147400">delta
  t</span> <span m="3149072">not</span> <span m="3149490">because</span> <span m="3149690">you
  want</span> <span m="3149870">super</span> <span m="3150180">high</span> <span m="3150614">accuracy</span>
  <span m="3152350">but</span> <span m="3152520">because</span> <span m="3152960">it''s</span>
  <span m="3153340">still</span> <span m="3153550">going</span> <span m="3153750">unstable</span>
  <span m="3154730">if you use</span> <span m="3155200">a</span> <span m="3155300">larger</span>
  <span m="3155660">delta t,</span> <span m="3157090">then</span> <span m="3157290">you</span>
  <span m="3157580">know</span> <span m="3157870">you have</span> <span m="3158060">a</span>
  <span m="3158260">stiff</span> <span m="3159010">problem.</span> <span m="3160740">That</span>
  <span m="3160910">is</span> <span m="3162010">really</span> <span m="3164670">the
  easiest</span> <span m="3164900">way,</span> <span m="3165180">I</span> <span m="3165310">find,</span>
  <span m="3165980">to</span> <span m="3166200">define</span> <span m="3166620">a</span>
  <span m="3166750">stiff</span> <span m="3167290">problem.</span> <span m="3168510">That</span>
  <span m="3168680">is</span> <span m="3168920">like,</span> <span m="3169180">you</span>
  <span m="3169350">are</span> <span m="3169590">forced</span> <span m="3170070">to
  use a small</span> <span m="3171070">delta t</span> <span m="3171570">by</span>
  <span m="3174180">the</span> <span m="3174760">stability</span> <span m="3175270">region,</span>
  <span m="3177760">not</span> <span m="3178090">for</span> <span m="3178320">accuracy</span>
  <span m="3178810">reasons,</span> <span m="3179090">not</span> <span m="3179520">for</span>
  <span m="3180980">wanting</span> <span m="3181365">higher</span> <span m="3181700">accuracy,</span>
  <span m="3182700">but</span> <span m="3182950">simply</span> <span m="3183650">trying</span>
  <span m="3183930">to</span> <span m="3184050">avoid</span> <span m="3185700">[INAUDIBLE].</span></p>
  <p><span m="3188210">OK,</span> <span m="3189300">so</span> <span m="3189450">then</span>
  <span m="3189670">you</span> <span m="3189830">get</span> <span m="3190030">a</span>
  <span m="3190470">stiff</span> <span m="3190880">problem.</span> <span m="3192679">Any</span>
  <span m="3193152">questions?</span> <span m="3197890">Yeah,</span> <span m="3198120">so</span>
  <span m="3198360">any</span> <span m="3198640">question,</span> <span m="3199075">please</span>
  <span m="3199510">raise</span> <span m="3199810">it.</span> <span m="3200770">Otherwise,</span>
  <span m="3201230">I''m</span> <span m="3201400">going</span> <span m="3201530">to</span>
  <span m="3201630">review</span> <span m="3202030">Newton-Raphson</span> <span m="3204530">a</span>
  <span m="3204630">little</span> <span m="3204910">bit,</span> <span m="3205120">and</span>
  <span m="3206390">there</span> <span m="3206550">is</span> <span m="3206700">no</span>
  <span m="3206880">more</span> <span m="3207820">things</span> <span m="3208670">I''m</span>
  <span m="3208850">planning</span> <span m="3209307">to</span> <span m="3209764">cover.</span>
  <span m="3210221">So</span> <span m="3210680">I''m</span> <span m="3210880">kind</span>
  <span m="3211040">of</span> <span m="3211140">expecting</span> <span m="3211630">questions</span>
  <span m="3212030">from</span> <span m="3212240">you guys.</span></p> <p><span m="3212724">AUDIENCE:</span>
  <span m="3213208">Finite difference</span> <span m="3213692">[INAUDIBLE]</span></p>
  <p><span m="3220470">QIQI WANG: Yeah,</span> <span m="3220920">finite difference,</span>
  <span m="3221680">and</span> <span m="3221740">finite</span> <span m="3221800">volumes</span>
  <span m="3222370">I include</span> <span m="3222806">in the</span> <span m="3223242">scope</span>
  <span m="3223680">of</span> <span m="3223790">the</span> <span m="3223860">exam.</span>
  <span m="3224650">As</span> <span m="3224840">you</span> <span m="3224940">saw</span>
  <span m="3225700">from</span> <span m="3225950">the</span> <span m="3226080">previous</span>
  <span m="3226460">year''s</span> <span m="3226560">questions</span> <span m="3226730">I</span>
  <span m="3227186">posted,</span> <span m="3229570">sometimes</span> <span m="3230020">we</span>
  <span m="3230360">include</span> <span m="3230700">it</span> <span m="3231040">in</span>
  <span m="3231270">the</span> <span m="3231380">actual</span> <span m="3231740">exam,</span>
  <span m="3232070">sometimes</span> <span m="3232300">we</span> <span m="3232636">don''t.</span>
  <span m="3234320">So</span> <span m="3236110">it is</span> <span m="3236520">included</span>
  <span m="3237460">in the</span> <span m="3237690">scope,</span> <span m="3239688">but</span>
  <span m="3240140">because</span> <span m="3240470">we</span> <span m="3240580">just</span>
  <span m="3240940">did</span> <span m="3241320">it,</span> <span m="3241993">I</span>
  <span m="3242416">think it''s</span> <span m="3242839">a</span> <span m="3243262">good</span>
  <span m="3243685">idea</span> <span m="3244110">to review</span> <span m="3244400">some</span>
  <span m="3244590">of</span> <span m="3244740">the</span> <span m="3245142">earlier</span>
  <span m="3245544">stuff</span> <span m="3246750">that</span> <span m="3247010">you
  may</span> <span m="3247710">have</span> <span m="3248137">forgotten.</span> <span
  m="3249420">And</span> <span m="3249960">another</span> <span m="3251770">benefit</span>
  <span m="3252598">is</span> <span m="3253012">that</span> <span m="3253840">we</span>
  <span m="3254060">are</span> <span m="3254330">also</span> <span m="3255990">going</span>
  <span m="3256280">over</span> <span m="3256570">this</span> <span m="3256910">now</span>
  <span m="3257290">that</span> <span m="3257510">we</span> <span m="3257650">have</span>
  <span m="3257900">[INAUDIBLE]</span> <span m="3259130">to</span> <span m="3259230">give</span>
  <span m="3259440">you</span> <span m="3259680">a</span> <span m="3259710">sense</span>
  <span m="3260010">that</span> <span m="3260450">all</span> <span m="3260730">the</span>
  <span m="3260850">stuff</span> <span m="3261150">we</span> <span m="3261350">learned</span>
  <span m="3262410">applies</span> <span m="3263210">to</span> <span m="3263340">PDEs</span>
  <span m="3264670">because</span> <span m="3265580">what</span> <span m="3265810">we</span>
  <span m="3266000">did</span> <span m="3266520">in</span> <span m="3266800">PDEs</span>
  <span m="3267030">is</span> <span m="3267170">just</span> <span m="3267470">to</span>
  <span m="3268100">approximate</span> <span m="3269020">the</span> <span m="3269190">PDE</span>
  <span m="3269800">using</span> <span m="3270080">a</span> <span m="3270540">big</span>
  <span m="3271000">ODE.</span> <span m="3272552">Right?</span></p> <p><span m="3274500">And
  you</span> <span m="3274670">can</span> <span m="3275190">apply</span> <span m="3276140">implicit</span>
  <span m="3276690">methods</span> <span m="3277125">on the</span> <span m="3277560">PDE</span>
  <span m="3277995">also,</span> <span m="3279740">except</span> <span m="3280260">for</span>
  <span m="3280510">the</span> <span m="3280710">Jacobian.</span> <span m="3282560">You</span>
  <span m="3282780">get</span> <span m="3283980">it''s</span> <span m="3284270">going</span>
  <span m="3284440">to</span> <span m="3284520">be</span> <span m="3284640">something</span>
  <span m="3285050">close</span> <span m="3285800">to</span> <span m="3285940">the</span>
  <span m="3286580">matrix</span> <span m="3287080">form</span> <span m="3287420">of</span>
  <span m="3287550">finite difference,</span> <span m="3289650">we</span> <span m="3289776">did</span>
  <span m="3289903">in</span> <span m="3290030">the</span> <span m="3290130">finite
  difference</span> <span m="3290450">vectors.</span> <span m="3293943">Yeah?</span></p>
  <p><span m="3294941">AUDIENCE: [INAUDIBLE]</span></p> <p><span m="3302430">QIQI
  WANG: Oh,</span> <span m="3302670">OK,</span> <span m="3303020">the</span> <span
  m="3303090">example</span> <span m="3303580">format</span> <span m="3303860">is</span>
  <span m="3304040">that</span> <span m="3304200">it''s</span> <span m="3304390">closed</span>
  <span m="3304725">notes,</span> <span m="3305540">right?</span> <span m="3305820">It''s</span>
  <span m="3305900">closed</span> <span m="3306390">everything</span> <span m="3307100">in</span>
  <span m="3309690">the</span> <span m="3309790">period</span> <span m="3311070">from</span>
  <span m="3311300">you</span> <span m="3311520">get</span> <span m="3311900">the
  exam</span> <span m="3312370">to when</span> <span m="3312640">you</span> <span
  m="3312900">come</span> <span m="3313120">to</span> <span m="3313460">our</span>
  <span m="3313936">office.</span> <span m="3316316">So</span> <span m="3317744">it''s</span>
  <span m="3318220">closed</span> <span m="3319460">everything,</span> <span m="3319840">closed</span>
  <span m="3320230">computer,</span> <span m="3320756">closed</span> <span m="3321212">cell
  phone.</span> <span m="3324170">Closed</span> <span m="3324670">Wikipedia.</span></p>
  <p><span m="3332260">We</span> <span m="3332760">are</span> <span m="3332820">actually</span>
  <span m="3333510">letting</span> <span m="3333940">you</span> <span m="3334200">work
  out,</span> <span m="3335530">really</span> <span m="3335980">think</span> <span
  m="3336410">about</span> <span m="3336690">the</span> <span m="3337060">problem</span>
  <span m="3339080">during</span> <span m="3339350">the</span> <span m="3339510">time</span>
  <span m="3339940">you are</span> <span m="3340418">looking</span> <span m="3340896">at
  the problem.</span> <span m="3342808">But</span> <span m="3343290">even</span> <span
  m="3343610">though</span> <span m="3344350">you don''t</span> <span m="3344700">get
  the</span> <span m="3345010">answer,</span> <span m="3348580">or during</span> <span
  m="3349400">our</span> <span m="3349690">face</span> <span m="3349960">time,</span>
  <span m="3350240">we</span> <span m="3350470">are</span> <span m="3350660">going</span>
  <span m="3351170">to</span> <span m="3351320">also</span> <span m="3351770">interact</span>
  <span m="3352065">with</span> <span m="3352560">you</span> <span m="3353650">when</span>
  <span m="3353800">we</span> <span m="3353910">ask</span> <span m="3354190">you</span>
  <span m="3355010">questions</span> <span m="3355560">that</span> <span m="3355760">you</span>
  <span m="3356430">may</span> <span m="3356580">not</span> <span m="3356750">have</span>
  <span m="3356970">expected,</span> <span m="3357520">or</span> <span m="3358360">we</span>
  <span m="3358520">may</span> <span m="3358670">actually</span> <span m="3359060">help</span>
  <span m="3359330">you</span> <span m="3359740">going through</span> <span m="3360150">some
  of</span> <span m="3360560">these.</span> <span m="3361380">So</span> <span m="3362550">that''s</span>
  <span m="3362770">kind of</span> <span m="3363230">how</span> <span m="3363610">[INAUDIBLE]</span>
  <span m="3364105">goes.</span> <span m="3365590">Do you</span> <span m="3365760">have</span>
  <span m="3365910">something else you</span> <span m="3366405">want to ask?</span></p>
  <p><span m="3367395">AUDIENCE: [INAUDIBLE]</span></p> <p><span m="3377800">QIQI
  WANG: Yeah,</span> <span m="3378170">right.</span> <span m="3380280">You</span>
  <span m="3380440">can</span> <span m="3380790">write</span> <span m="3381130">things</span>
  <span m="3381390">down</span> <span m="3381720">and</span> <span m="3382420">bring</span>
  <span m="3382810">whatever</span> <span m="3383080">you have</span> <span m="3383500">written</span>
  <span m="3383900">into</span> <span m="3384210">our</span> <span m="3384520">office.</span>
  <span m="3385428">And</span> <span m="3385882">in</span> <span m="3386336">the</span>
  <span m="3386790">office,</span> <span m="3387244">you''re</span> <span m="3387698">expected</span>
  <span m="3388152">to</span> <span m="3388610">use</span> <span m="3388690">a</span>
  <span m="3389060">whiteboard</span> <span m="3389460">or</span> <span m="3389880">blackboard</span>
  <span m="3390530">and</span> <span m="3390880">explain</span> <span m="3391840">to</span>
  <span m="3392320">us</span> <span m="3393350">like</span> <span m="3394030">you''re</span>
  <span m="3394150">the</span> <span m="3394350">professor,</span> <span m="3396310">the
  other</span> <span m="3396800">students,</span> <span m="3398270">explain</span>
  <span m="3398520">to us</span> <span m="3398640">what you got.</span> <span m="3406170">Any</span>
  <span m="3406320">other</span> <span m="3406520">questions?</span> <span m="3414168">No?</span></p>
  <p><span m="3414580">The</span> <span m="3414680">last</span> <span m="3414910">thing</span>
  <span m="3415060">I</span> <span m="3415350">want</span> <span m="3415530">to</span>
  <span m="3415600">go</span> <span m="3415770">through</span> <span m="3416822">is</span>
  <span m="3417200">Newton-Raphson</span> <span m="3417520">method.</span> <span m="3418760">And</span>
  <span m="3419720">it''s</span> <span m="3419970">another</span> <span m="3422120">sort</span>
  <span m="3422380">of</span> <span m="3422490">confusing--</span> <span m="3423350">as</span>
  <span m="3423780">I</span> <span m="3424070">said,</span> <span m="3424410">Newton-Raphson</span>
  <span m="3424720">method</span> <span m="3427330">is</span> <span m="3427540">a</span>
  <span m="3427970">method</span> <span m="3428520">that</span> <span m="3429610">simply</span>
  <span m="3429890">solves</span> <span m="3430940">regular</span> <span m="3431390">non-linear</span>
  <span m="3432290">equations.</span> <span m="3434150">And</span> <span m="3434730">a</span>
  <span m="3434760">non-linear</span> <span m="3434900">equation</span> <span m="3435630">can</span>
  <span m="3437290">appear</span> <span m="3437520">in</span> <span m="3437670">16.90.</span>
  <span m="3439120">It</span> <span m="3439320">can</span> <span m="3439520">appear</span>
  <span m="3440310">anywhere</span> <span m="3440840">else</span> <span m="3441350">in</span>
  <span m="3441620">your</span> <span m="3442590">future</span> <span m="3445510">career.</span></p>
  <p><span m="3447110">So</span> <span m="3447970">what</span> <span m="3448400">you''re</span>
  <span m="3448750">learning</span> <span m="3449030">about</span> <span m="3450250">solving</span>
  <span m="3450630">non-linear</span> <span m="3451000">equations</span> <span m="3451470">really</span>
  <span m="3451890">goes</span> <span m="3452140">very</span> <span m="3452600">far,</span>
  <span m="3454860">even</span> <span m="3455220">if</span> <span m="3455430">you</span>
  <span m="3455880">don''t</span> <span m="3456190">deal</span> <span m="3456340">with</span>
  <span m="3456690">numerical methods</span> <span m="3457260">later</span> <span
  m="3457680">on.</span> <span m="3459360">So</span> <span m="3461580">as</span> <span
  m="3461710">I</span> <span m="3461770">said,</span> <span m="3462010">it''s</span>
  <span m="3462220">a method</span> <span m="3462590">of</span> <span m="3462680">solving</span>
  <span m="3463310">non-linear</span> <span m="3463810">equations</span> <span m="3464600">if</span>
  <span m="3464840">the</span> <span m="3464890">set</span> <span m="3465100">of</span>
  <span m="3465250">non-linear</span> <span m="3465610">equations</span> <span m="3466330">is</span>
  <span m="3466600">relatively</span> <span m="3467630">small.</span> <span m="3468620">Say</span>
  <span m="3468730">you have</span> <span m="3468890">two</span> <span m="3469000">equations</span>
  <span m="3469610">or</span> <span m="3470070">three</span> <span m="3470385">equations,</span>
  <span m="3470830">you can</span> <span m="3471020">go</span> <span m="3471210">to</span>
  <span m="3471310">Matlab</span> <span m="3471880">and</span> <span m="3472250">use</span>
  <span m="3472520">F solve</span> <span m="3473190">to</span> <span m="3474020">get</span>
  <span m="3474220">it</span> <span m="3474320">solved</span> <span m="3475940">like</span>
  <span m="3476340">brute</span> <span m="3476700">force.</span></p> <p><span m="3477910">But</span>
  <span m="3478160">if</span> <span m="3478370">you</span> <span m="3478550">have</span>
  <span m="3479440">a</span> <span m="3479470">large</span> <span m="3480060">set</span>
  <span m="3480320">of</span> <span m="3480490">differential</span> <span m="3480910">equations</span>
  <span m="3481480">you</span> <span m="3481660">have</span> <span m="3481840">to</span>
  <span m="3481960">solve</span> <span m="3482720">simultaneously,</span> <span m="3484240">like</span>
  <span m="3484560">what</span> <span m="3484980">we''re</span> <span m="3485130">going
  to</span> <span m="3485720">have</span> <span m="3487080">if</span> <span m="3487630">you</span>
  <span m="3488040">use</span> <span m="3488482">an</span> <span m="3488924">implicit</span>
  <span m="3489366">time integration</span> <span m="3489808">method,</span> <span
  m="3491580">apply</span> <span m="3492190">it</span> <span m="3492570">to</span>
  <span m="3492810">a</span> <span m="3493080">discretized</span> <span m="3493690">PDE,</span>
  <span m="3495790">then</span> <span m="3496250">you''re</span> <span m="3496340">going</span>
  <span m="3496470">to</span> <span m="3496530">get</span> <span m="3497080">at</span>
  <span m="3497230">least</span> <span m="3497570">100</span> <span m="3497997">ODEs</span>
  <span m="3500762">you</span> <span m="3501200">have</span> <span m="3501610">to--</span>
  <span m="3502630">which,</span> <span m="3503000">if</span> <span m="3503160">you</span>
  <span m="3503290">have</span> <span m="3503490">to</span> <span m="3503590">solve</span>
  <span m="3503960">using</span> <span m="3504260">an</span> <span m="3504760">implicit</span>
  <span m="3505065">scheme,</span> <span m="3505480">you''re going to get</span> <span
  m="3507024">hundreds,</span> <span m="3507980">maybe</span> <span m="3508230">thousands,</span>
  <span m="3508990">maybe</span> <span m="3509320">millions,</span> <span m="3509900">or</span>
  <span m="3510120">maybe</span> <span m="3510450">trillions</span> <span m="3511900">of</span>
  <span m="3512610">algebraic</span> <span m="3513610">equations</span> <span m="3515040">you</span>
  <span m="3515190">need</span> <span m="3515340">to</span> <span m="3515450">solve.</span></p>
  <p><span m="3518660">OK, so</span> <span m="3519170">imagine</span> <span m="3519650">you</span>
  <span m="3519780">have</span> <span m="3519970">to</span> <span m="3520110">solve</span>
  <span m="3520640">f</span> <span m="3521030">of</span> <span m="3521335">u</span>
  <span m="3522060">equal</span> <span m="3522370">to</span> <span m="3522440">0</span>
  <span m="3523010">where</span> <span m="3523400">u,</span> <span m="3523980">instead</span>
  <span m="3524451">of</span> <span m="3524922">writing</span> <span m="3525393">down</span>
  <span m="3525864">a simplified</span> <span m="3526335">version</span> <span m="3526806">of</span>
  <span m="3527277">what you</span> <span m="3527750">would</span> <span m="3528020">get</span>
  <span m="3528250">in an</span> <span m="3528910">implicit</span> <span m="3529215">scheme,</span>
  <span m="3530400">your</span> <span m="3530700">implicit</span> <span m="3531170">scheme</span>
  <span m="3531510">you</span> <span m="3531660">would</span> <span m="3531910">get</span>
  <span m="3532860">u</span> <span m="3533130">minus</span> <span m="3533630">u k,</span>
  <span m="3535140">which</span> <span m="3535810">is</span> <span m="3536540">the</span>
  <span m="3536640">stuff</span> <span m="3536930">you</span> <span m="3537040">already</span>
  <span m="3537330">know,</span> <span m="3538810">over</span> <span m="3539090">delta</span>
  <span m="3539380">t</span> <span m="3540110">is</span> <span m="3540430">equal</span>
  <span m="3540830">to</span> <span m="3541060">some</span> <span m="3541500">right</span>
  <span m="3541710">hand</span> <span m="3541890">side</span> <span m="3542200">of</span>
  <span m="3542620">u,</span> <span m="3543380">and</span> <span m="3543700">uk,</span>
  <span m="3544490">and</span> <span m="3544880">maybe</span> <span m="3545110">something</span>
  <span m="3545430">else,</span> <span m="3546010">right?</span> <span m="3547990">And</span>
  <span m="3548680">instead</span> <span m="3549080">of</span> <span m="3549520">writing</span>
  <span m="3549860">the</span> <span m="3549950">same</span> <span m="3550250">f</span>
  <span m="3550570">here,</span> <span m="3550750">I''m</span> <span m="3550900">just</span>
  <span m="3551080">going</span> <span m="3551210">to</span> <span m="3551300">write</span>
  <span m="3551740">a</span> <span m="3552140">big</span> <span m="3552400">F</span>
  <span m="3552830">of</span> <span m="3553260">u</span> <span m="3553690">equal</span>
  <span m="3554120">to</span> <span m="3554550">0.</span> <span m="3554980">So that</span>
  <span m="3555320">big</span> <span m="3555595">F</span> <span m="3557100">in</span>
  <span m="3557280">this</span> <span m="3557480">case</span> <span m="3557900">is</span>
  <span m="3558200">really</span> <span m="3558520">defined</span> <span m="3559651">as</span>
  <span m="3560030">u</span> <span m="3560500">minus</span> <span m="3561130">u k</span>
  <span m="3561480">over</span> <span m="3561700">delta</span> <span m="3562010">t</span>
  <span m="3562470">minus</span> <span m="3562920">f</span> <span m="3563300">of</span>
  <span m="3563762">u,</span> <span m="3564224">u k,</span> <span m="3564686">et cetera.</span></p>
  <p><span m="3567350">So</span> <span m="3569120">this</span> <span m="3569310">is</span>
  <span m="3569480">what</span> <span m="3569580">happens</span> <span m="3569850">if</span>
  <span m="3570140">we</span> <span m="3570430">solve,</span> <span m="3571103">let''s
  say,</span> <span m="3572190">a</span> <span m="3572460">discretized</span> <span
  m="3572730">PDE</span> <span m="3572820">[INAUDIBLE].</span> <span m="3575050">U</span>
  <span m="3575560">is</span> <span m="3576180">the</span> <span m="3576350">next</span>
  <span m="3576610">time-step</span> <span m="3577050">solution</span> <span m="3577470">we
  want</span> <span m="3577780">to</span> <span m="3578090">get.</span> <span m="3578510">And</span>
  <span m="3578930">u k</span> <span m="3579350">is the</span> <span m="3579770">previous</span>
  <span m="3580880">time step</span> <span m="3581160">solution</span> <span m="3581520">you
  already</span> <span m="3581880">know.</span> <span m="3583380">Now,</span> <span
  m="3583880">if</span> <span m="3584300">F</span> <span m="3584620">is</span> <span
  m="3585015">non-linear,</span> <span m="3586200">you</span> <span m="3586380">have</span>
  <span m="3586590">to</span> <span m="3586830">find</span> <span m="3586860">the</span>
  <span m="3587160">root</span> <span m="3587642">of its</span> <span m="3588124">big
  F,</span> <span m="3589570">which</span> <span m="3589780">is</span> <span m="3589940">essentially</span>
  <span m="3590480">the</span> <span m="3590570">left</span> <span m="3590810">hand
  side</span> <span m="3591115">minus</span> <span m="3591420">right</span> <span
  m="3591620">hand side</span> <span m="3591700">of</span> <span m="3592193">this</span>
  <span m="3593770">implicit</span> <span m="3594140">update</span> <span m="3594390">[INAUDIBLE].</span></p>
  <p><span m="3598270">Right?</span> <span m="3599240">You need</span> <span m="3599610">to</span>
  <span m="3599980">find</span> <span m="3601160">a</span> <span m="3601630">u</span>
  <span m="3602122">which</span> <span m="3602614">is a vector</span> <span m="3603106">of</span>
  <span m="3604090">the</span> <span m="3604582">solution</span> <span m="3605570">that
  makes</span> <span m="3605950">this</span> <span m="3606290">f</span> <span m="3607530">0</span>
  <span m="3607870">for</span> <span m="3608090">all</span> <span m="3608870">the</span>
  <span m="3609300">components</span> <span m="3609757">of</span> <span m="3610214">f.</span>
  <span m="3612042">And</span> <span m="3612499">f</span> <span m="3612960">has</span>
  <span m="3613050">the</span> <span m="3613340">same</span> <span m="3613717">dimension</span>
  <span m="3614094">as</span> <span m="3614471">u.</span> <span m="3614850">If</span>
  <span m="3615190">u</span> <span m="3615620">is</span> <span m="3616050">a</span>
  <span m="3616430">3D</span> <span m="3616907">time step,</span> <span m="3617384">f</span>
  <span m="3617861">is going</span> <span m="3618338">to be a</span> <span m="3618815">3D</span>
  <span m="3619292">time step.</span></p> <p><span m="3624550">And you need</span>
  <span m="3624830">to</span> <span m="3624910">find</span> <span m="3625920">these</span>
  <span m="3626720">3D</span> <span m="3627005">numbers</span> <span m="3627400">that</span>
  <span m="3627590">make</span> <span m="3627940">the</span> <span m="3628870">[INAUDIBLE]</span>
  <span m="3629230">f</span> <span m="3630020">equal to</span> <span m="3630460">0</span>
  <span m="3630916">simultaneously.</span> <span m="3633200">That''s</span> <span
  m="3633430">not</span> <span m="3633670">an</span> <span m="3634110">easy</span>
  <span m="3634450">task.</span> <span m="3638520">And</span> <span m="3638660">I</span>
  <span m="3639115">think</span> <span m="3639800">F solve</span> <span m="3640050">is
  going</span> <span m="3640180">to</span> <span m="3640270">have</span> <span m="3640450">a</span>
  <span m="3640540">hard</span> <span m="3640830">time</span> <span m="3641120">dealing</span>
  <span m="3641400">with</span> <span m="3641570">this</span> <span m="3641984">if</span>
  <span m="3643226">u</span> <span m="3643640">is</span> <span m="3645876">a</span>
  <span m="3646310">high</span> <span m="3646470">dimensional</span> <span m="3646860">vector.</span></p>
  <p><span m="3652440">Now,</span> <span m="3653790">what</span> <span m="3654180">does</span>
  <span m="3654710">Newton-Raphson</span> <span m="3655280">do?</span> <span m="3656790">Newton-Raphson</span>
  <span m="3657930">starts</span> <span m="3658310">with</span> <span m="3658550">an</span>
  <span m="3658680">initial</span> <span m="3659040">guess.</span> <span m="3660020">So</span>
  <span m="3660310">u,</span> <span m="3662120">for</span> <span m="3662570">example,</span>
  <span m="3662840">I''m</span> <span m="3663060">going</span> <span m="3663210">to</span>
  <span m="3663270">use</span> <span m="3664070">parentheses</span> <span m="3664760">to</span>
  <span m="3665035">denote</span> <span m="3665776">the</span> <span m="3666242">information</span>
  <span m="3666708">[INAUDIBLE].</span> <span m="3668106">Parentheses</span> <span
  m="3669038">0</span> <span m="3669510">is the</span> <span m="3669610">initial</span>
  <span m="3670000">guess.</span> <span m="3670220">I''m going</span> <span m="3670350">to</span>
  <span m="3670410">set</span> <span m="3670810">it</span> <span m="3670970">to</span>
  <span m="3671960">u k.</span> <span m="3672300">I''m</span> <span m="3672480">going</span>
  <span m="3672630">to</span> <span m="3672690">set</span> <span m="3673070">it</span>
  <span m="3673220">to</span> <span m="3674380">the</span> <span m="3674470">solution</span>
  <span m="3674960">at</span> <span m="3675030">the</span> <span m="3675100">previous</span>
  <span m="3675400">time</span> <span m="3675640">step.</span></p> <p><span m="3677200">Then,</span>
  <span m="3677530">I''m</span> <span m="3677680">going</span> <span m="3677810">to</span>
  <span m="3677900">approximate</span> <span m="3678450">this</span> <span m="3679110">non-linear</span>
  <span m="3679540">function</span> <span m="3679940">using</span> <span m="3680390">a</span>
  <span m="3680500">linear</span> <span m="3680890">function.</span> <span m="3682802">Can</span>
  <span m="3683225">I</span> <span m="3683750">approximate</span> <span m="3685950">F
  of u</span> <span m="3687236">by</span> <span m="3687580">something</span> <span
  m="3688050">linear?</span> <span m="3691330">Let''s do it</span> <span m="3691940">one</span>
  <span m="3692190">by</span> <span m="3692330">one.</span> <span m="3692600">Let''s</span>
  <span m="3693200">approximate</span> <span m="3694180">the</span> <span m="3694440">first</span>
  <span m="3694660">component</span> <span m="3695132">of</span> <span m="3695604">F.</span>
  <span m="3696550">Think</span> <span m="3696740">of</span> <span m="3696890">F</span>
  <span m="3697580">having</span> <span m="3698970">components.</span> <span m="3700350">We''re</span>
  <span m="3700500">just</span> <span m="3700700">going</span> <span m="3700840">to</span>
  <span m="3700970">approximate</span> <span m="3701670">the</span> <span m="3701740">first</span>
  <span m="3702010">component</span> <span m="3702340">and</span> <span m="3702670">have</span>
  <span m="3702990">all the other</span> <span m="3703270">components</span> <span
  m="3704150">follow.</span></p> <p><span m="3705350">OK,</span> <span m="3705650">so</span>
  <span m="3705800">if</span> <span m="3705990">you</span> <span m="3706070">just</span>
  <span m="3706270">approximate</span> <span m="3707060">the</span> <span m="3707250">first</span>
  <span m="3707530">component,</span> <span m="3709390">I''m</span> <span m="3709560">going</span>
  <span m="3709690">to</span> <span m="3710040">use</span> <span m="3710520">Taylor</span>
  <span m="3710740">series.</span> <span m="3712660">And</span> <span m="3713010">I''m</span>
  <span m="3713160">going</span> <span m="3713310">to</span> <span m="3713400">use</span>
  <span m="3713620">a</span> <span m="3713680">Taylor</span> <span m="3714080">series</span>
  <span m="3714530">of</span> <span m="3714800">a function</span> <span m="3715990">of</span>
  <span m="3716180">the</span> <span m="3716240">[INAUDIBLE]</span> <span m="3716560">variables,</span>
  <span m="3718490">all right?</span> <span m="3720420">So</span> <span m="3720820">a</span>
  <span m="3720920">function--</span> <span m="3721430">the</span> <span m="3721530">periodicity</span>
  <span m="3722210">of</span> <span m="3722340">a</span> <span m="3722410">function</span>
  <span m="3722760">of</span> <span m="3722880">a</span> <span m="3722940">[INAUDIBLE]</span>
  <span m="3723200">variable</span> <span m="3723650">is</span> <span m="3723950">pretty</span>
  <span m="3724170">complicated.</span> <span m="3726570">But</span> <span m="3726640">the</span>
  <span m="3726730">lucky</span> <span m="3727080">thing</span> <span m="3727290">is</span>
  <span m="3727440">that</span> <span m="3727690">I</span> <span m="3727860">don''t</span>
  <span m="3728180">need</span> <span m="3728330">to</span> <span m="3728480">keep</span>
  <span m="3728690">all</span> <span m="3728750">the</span> <span m="3728980">terms.</span>
  <span m="3729960">I''m</span> <span m="3730130">going</span> <span m="3730260">to</span>
  <span m="3730490">throw</span> <span m="3730780">away</span> <span m="3731270">anything</span>
  <span m="3732680">that</span> <span m="3733000">involves</span> <span m="3733910">more</span>
  <span m="3734320">than</span> <span m="3734520">the</span> <span m="3734600">first</span>
  <span m="3734980">derivative.</span></p> <p><span m="3738080">In</span> <span m="3738200">other</span>
  <span m="3738380">words,</span> <span m="3738700">I''m</span> <span m="3738790">only</span>
  <span m="3739080">going</span> <span m="3739250">to</span> <span m="3739340">keep</span>
  <span m="3740230">the</span> <span m="3740390">zeroth</span> <span m="3740900">order</span>
  <span m="3741400">term,</span> <span m="3741980">which</span> <span m="3742240">involves</span>
  <span m="3743090">no</span> <span m="3743490">derivatives,</span> <span m="3744820">and</span>
  <span m="3744990">the</span> <span m="3745050">first</span> <span m="3745370">order
  term,</span> <span m="3745600">which</span> <span m="3746160">involves</span> <span
  m="3746720">only</span> <span m="3747070">the</span> <span m="3747310">first</span>
  <span m="3747790">order</span> <span m="3747980">derivatives.</span> <span m="3750100">OK,</span>
  <span m="3750370">now</span> <span m="3750600">what</span> <span m="3750800">is</span>
  <span m="3750940">the</span> <span m="3751060">zeroth</span> <span m="3751600">order</span>
  <span m="3751720">term?</span></p> <p><span m="3753420">The</span> <span m="3753530">zeroth</span>
  <span m="3753900">order</span> <span m="3754150">term</span> <span m="3754500">is</span>
  <span m="3754850">F1</span> <span m="3756394">at</span> <span m="3757680">my</span>
  <span m="3757890">initial</span> <span m="3758170">guess,</span> <span m="3759376">right?</span>
  <span m="3762130">What</span> <span m="3762410">is</span> <span m="3762590">the</span>
  <span m="3762690">first</span> <span m="3763150">order</span> <span m="3763230">term?</span>
  <span m="3763580">Actually,</span> <span m="3764050">in</span> <span m="3764120">this</span>
  <span m="3764310">case,</span> <span m="3764560">because</span> <span m="3764890">it''s</span>
  <span m="3765040">a multivariate</span> <span m="3765890">function,</span> <span
  m="3766460">I</span> <span m="3766570">have</span> <span m="3766920">more</span>
  <span m="3767160">than</span> <span m="3767360">one</span> <span m="3768065">first
  order</span> <span m="3768520">terms.</span> <span m="3771250">If</span> <span m="3772300">I</span>
  <span m="3772540">have</span> <span m="3772860">as</span> <span m="3773160">many</span>
  <span m="3773570">first</span> <span m="3773830">order</span> <span m="3774030">terms</span>
  <span m="3774420">as</span> <span m="3774710">there</span> <span m="3774990">are</span>
  <span m="3775680">many</span> <span m="3776116">u''s,</span> <span m="3778230">I''m</span>
  <span m="3778440">going</span> <span m="3778590">to</span> <span m="3778670">be</span>
  <span m="3779070">summing</span> <span m="3779680">from</span> <span m="3779945">i</span>
  <span m="3780210">goes</span> <span m="3780540">from</span> <span m="3780760">1</span>
  <span m="3781100">to</span> <span m="3782230">the</span> <span m="3782320">dimension</span>
  <span m="3782890">of</span> <span m="3782980">the</span> <span m="3783080">system,</span>
  <span m="3783560">let me</span> <span m="3784020">call</span> <span m="3784315">big</span>
  <span m="3784610">N,</span> <span m="3786620">partial</span> <span m="3786780">F1,</span>
  <span m="3787850">partial</span> <span m="3788130">u</span> <span m="3789920">of</span>
  <span m="3790160">the</span> <span m="3790350">ith</span> <span m="3791020">dimension</span>
  <span m="3794322">times</span> <span m="3795220">ui</span> <span m="3796190">minus</span>
  <span m="3797130">u0i.</span> <span m="3799910">Right?</span> <span m="3802912">Does
  that make</span> <span m="3803359">sense?</span> <span m="3803810">That''s</span>
  <span m="3805491">the</span> <span m="3805950">Taylor</span> <span m="3806370">series</span>
  <span m="3806790">expansion</span> <span m="3807480">of</span> <span m="3808430">F1.</span></p>
  <p><span m="3810580">We</span> <span m="3810820">are</span> <span m="3811110">only</span>
  <span m="3811540">keeping</span> <span m="3814720">the</span> <span m="3815130">zeroth</span>
  <span m="3815580">order</span> <span m="3815720">terms</span> <span m="3816135">as
  opposed to all</span> <span m="3816550">the</span> <span m="3817008">terms.</span>
  <span m="3819760">If</span> <span m="3819970">I</span> <span m="3820110">start</span>
  <span m="3820450">to</span> <span m="3820570">write</span> <span m="3821010">all
  the other</span> <span m="3821280">order</span> <span m="3821820">derivatives,</span>
  <span m="3822470">it would</span> <span m="3822965">get too complicated.</span>
  <span m="3823955">But</span> <span m="3824450">I''m not going to</span> <span m="3824945">write</span>
  <span m="3825440">them,</span> <span m="3825770">so I''m</span> <span m="3826240">going</span>
  <span m="3826710">to</span> <span m="3827180">truncate</span> <span m="3827650">them.</span>
  <span m="3828110">And</span> <span m="3828330">I''ll approximate</span> <span m="3828826">[INAUDIBLE]</span>
  <span m="3829322">method,</span> <span m="3830314">it''s</span> <span m="3830810">a</span>
  <span m="3831306">linear</span> <span m="3831802">function.</span> <span m="3832800">It''s
  a linear</span> <span m="3833220">function</span> <span m="3833980">because</span>
  <span m="3835500">this</span> <span m="3835790">F1</span> <span m="3836150">of</span>
  <span m="3836510">u</span> <span m="3837300">is</span> <span m="3837580">probably</span>
  <span m="3838080">a</span> <span m="3838480">linear</span> <span m="3838960">function
  of</span> <span m="3839440">u.</span> <span m="3839920">But now,</span> <span m="3840730">I''m</span>
  <span m="3841140">truncating.</span> <span m="3841550">I''m</span> <span m="3841960">removing</span>
  <span m="3842070">everything</span> <span m="3843190">that</span> <span m="3843510">happens</span>
  <span m="3843930">over</span> <span m="3844260">here,</span> <span m="3844681">so
  if it''s</span> <span m="3845102">quadratic,</span> <span m="3845523">or</span>
  <span m="3845944">cubic,</span> <span m="3846365">or</span> <span m="3846790">anything.</span>
  <span m="3847500">I''m</span> <span m="3847660">only</span> <span m="3847810">keeping</span>
  <span m="3847960">the</span> <span m="3848384">constant</span> <span m="3848808">part</span>
  <span m="3850080">that</span> <span m="3850410">is</span> <span m="3850660">independent</span>
  <span m="3850990">of</span> <span m="3851320">u,</span> <span m="3851920">and</span>
  <span m="3852150">this</span> <span m="3852330">part, which is</span> <span m="3852802">0.</span></p>
  <p><span m="3856580">Now,</span> <span m="3857870">I get a</span> <span m="3858130">linear</span>
  <span m="3858440">approximation</span> <span m="3858925">of</span> <span m="3859410">F.</span>
  <span m="3861840">We</span> <span m="3862040">all</span> <span m="3862260">know</span>
  <span m="3862530">how</span> <span m="3862710">to</span> <span m="3862950">find</span>
  <span m="3863410">the</span> <span m="3863870">root</span> <span m="3864330">of</span>
  <span m="3864790">a</span> <span m="3865250">linear</span> <span m="3865710">function?</span>
  <span m="3868010">Even</span> <span m="3868360">though it''s a million</span> <span
  m="3868845">dimensional?</span> <span m="3873210">Right,</span> <span m="3874180">that''s</span>
  <span m="3874480">the</span> <span m="3874550">reason</span> <span m="3874920">we</span>
  <span m="3875070">have</span> <span m="3875280">linear</span> <span m="3875620">algebra,</span>
  <span m="3876494">right?</span> <span m="3877370">That''s</span> <span m="3877660">why</span>
  <span m="3877900">we</span> <span m="3878090">have</span> <span m="3878560">matrices.</span>
  <span m="3878840">That''s</span> <span m="3879060">why</span> <span m="3879490">Matlab</span>
  <span m="3880010">is</span> <span m="3880140">called</span> <span m="3880420">Matlab.</span>
  <span m="3883830">That</span> <span m="3884070">is</span> <span m="3884190">because</span>
  <span m="3885250">we</span> <span m="3885450">can</span> <span m="3885740">write</span>
  <span m="3887200">functions</span> <span m="3887760">like</span> <span m="3888232">this,</span>
  <span m="3888704">we can write</span> <span m="3889176">linear</span> <span m="3889800">functions</span>
  <span m="3890280">in</span> <span m="3890410">matrix</span> <span m="3890910">form.</span>
  <span m="3893170">And</span> <span m="3893440">to</span> <span m="3893580">solve</span>
  <span m="3895270">linear</span> <span m="3895710">equations</span> <span m="3896180">like</span>
  <span m="3896390">this,</span> <span m="3896740">even</span> <span m="3897460">ginormous</span>
  <span m="3897990">ones,</span> <span m="3899050">we</span> <span m="3899200">just</span>
  <span m="3899510">use</span> <span m="3899770">linear</span> <span m="3900060">algebra,</span>
  <span m="3902240">right?</span></p> <p><span m="3903720">OK,</span> <span m="3904480">so</span>
  <span m="3904610">we</span> <span m="3904980">are</span> <span m="3905250">also</span>
  <span m="3905690">approximating</span> <span m="3906570">all</span> <span m="3906770">the</span>
  <span m="3906950">components</span> <span m="3907230">of</span> <span m="3907510">F,</span>
  <span m="3908340">all the</span> <span m="3908400">way</span> <span m="3908590">to</span>
  <span m="3908720">the</span> <span m="3909170">n-th</span> <span m="3910200">component</span>
  <span m="3911450">using</span> <span m="3912090">Fn</span> <span m="3913800">u0,</span>
  <span m="3916380">plus</span> <span m="3917030">summation</span> <span m="3917506">i</span>
  <span m="3917982">goes from</span> <span m="3918458">1</span> <span m="3918934">to</span>
  <span m="3919410">N,</span> <span m="3919690">partial</span> <span m="3919970">FN</span>
  <span m="3920930">partial</span> <span m="3921410">ui,</span> <span m="3922140">ui</span>
  <span m="3922500">minus</span> <span m="3923240">ui0.</span> <span m="3926180">So</span>
  <span m="3926470">there</span> <span m="3926790">are</span> <span m="3927050">big</span>
  <span m="3927532">N</span> <span m="3928014">equations.</span> <span m="3929460">We
  have</span> <span m="3929942">big</span> <span m="3930424">N of these</span> <span
  m="3930906">variables.</span> <span m="3934762">How to solve</span> <span m="3935244">them?</span>
  <span m="3937654">How</span> <span m="3938136">to</span> <span m="3938620">solve</span>
  <span m="3938930">these</span> <span m="3939360">coupled,</span> <span m="3939510">N-coupled</span>
  <span m="3939942">linear</span> <span m="3941240">equations?</span> <span m="3946960">Yes?</span></p>
  <p><span m="3948122">AUDIENCE: [INAUDIBLE]</span></p> <p><span m="3951810">QIQI
  WANG: Yeah,</span> <span m="3952470">it''s</span> <span m="3952820">just</span>
  <span m="3953180">write it</span> <span m="3953530">into</span> <span m="3954020">a</span>
  <span m="3954460">matrix</span> <span m="3954750">form,</span> <span m="3955540">right?</span>
  <span m="3956610">First, write it into a</span> <span m="3956720">matrix</span>
  <span m="3957620">form.</span> <span m="3958520">So</span> <span m="3958770">I</span>
  <span m="3959000">want</span> <span m="3959220">to</span> <span m="3959310">try</span>
  <span m="3959520">to</span> <span m="3959640">say,</span> <span m="3959930">OK,</span>
  <span m="3960800">if</span> <span m="3961040">I</span> <span m="3961140">want</span>
  <span m="3961340">to</span> <span m="3961410">set</span> <span m="3962020">all</span>
  <span m="3962340">these</span> <span m="3962570">things</span> <span m="3962810">to</span>
  <span m="3963260">0,</span> <span m="3963760">I''m</span> <span m="3964100">trying</span>
  <span m="3964290">to</span> <span m="3964390">set</span> <span m="3965360">like</span>
  <span m="3965610">0,</span> <span m="3965880">0, 0,</span> <span m="3966318">0,</span>
  <span m="3967632">is</span> <span m="3968070">equal</span> <span m="3968480">to</span>
  <span m="3969490">F1</span> <span m="3970090">at</span> <span m="3970620">u0,</span>
  <span m="3971830">et</span> <span m="3972190">cetera,</span> <span m="3972445">to</span>
  <span m="3972700">FN</span> <span m="3972840">of</span> <span m="3973160">u0.</span>
  <span m="3976440">This</span> <span m="3976880">is this</span> <span m="3977320">term.</span>
  <span m="3978610">And</span> <span m="3978990">how</span> <span m="3979140">about</span>
  <span m="3979410">this</span> <span m="3979620">term?</span> <span m="3980960">This</span>
  <span m="3981110">term</span> <span m="3981370">is</span> <span m="3982100">just</span>
  <span m="3982570">a</span> <span m="3982820">joint</span> <span m="3983280">matrix</span>
  <span m="3983820">vector</span> <span m="3984440">multiplication.</span> <span m="3986530">The</span>
  <span m="3986660">matrix</span> <span m="3987250">is</span> <span m="3990540">other</span>
  <span m="3990610">derivatives,</span> <span m="3991760">which</span> <span m="3991930">is</span>
  <span m="3992160">called</span> <span m="3992510">the</span> <span m="3992870">Jacobin</span>
  <span m="3993200">when</span> <span m="3993520">I</span> <span m="3993640">put</span>
  <span m="3993910">that</span> <span m="3994090">into</span> <span m="3994350">a</span>
  <span m="3994390">matrix</span> <span m="3994810">form.</span></p> <p><span m="3998440">The</span>
  <span m="3998560">first</span> <span m="3998850">row</span> <span m="3999280">is</span>
  <span m="3999570">my</span> <span m="4000380">partial F1,</span> <span m="4000835">partial</span>
  <span m="4001290">blah.</span> <span m="4002420">The</span> <span m="4002550">first</span>
  <span m="4002960">column</span> <span m="4003700">is</span> <span m="4003930">my</span>
  <span m="4005170">partial blah,</span> <span m="4005910">partial</span> <span m="4006490">u1.</span>
  <span m="4007840">The</span> <span m="4007950">last</span> <span m="4008360">column</span>
  <span m="4009090">is</span> <span m="4010180">partial</span> <span m="4010650">F</span>
  <span m="4010950">blah,</span> <span m="4011762">partial</span> <span m="4012460">uN.</span>
  <span m="4013320">So</span> <span m="4014090">each</span> <span m="4014340">row</span>
  <span m="4015010">corresponds</span> <span m="4015650">to</span> <span m="4016070">one</span>
  <span m="4016460">[INAUDIBLE]</span> <span m="4016740">the</span> <span m="4016900">residual.</span>
  <span m="4017870">Each column</span> <span m="4018440">corresponds</span> <span
  m="4018680">to</span> <span m="4019190">one</span> <span m="4019540">thing</span>
  <span m="4019917">in</span> <span m="4020294">the</span> <span m="4021050">independent</span>
  <span m="4021340">variables,</span> <span m="4022350">in</span> <span m="4022510">the</span>
  <span m="4022680">u''s.</span> <span m="4023990">And</span> <span m="4024410">multiplying</span>
  <span m="4025190">that</span> <span m="4025410">by</span> <span m="4025800">order</span>
  <span m="4025920">u1</span> <span m="4026680">minus</span> <span m="4027145">u1
  0,</span> <span m="4029670">et cetera,</span> <span m="4030500">to</span> <span
  m="4031200">uN</span> <span m="4031550">minus</span> <span m="4031880">uN 0.</span>
  <span m="4035940">Do you all see</span> <span m="4037170">these</span> <span m="4037500">linear</span>
  <span m="4037989">equations</span> <span m="4038478">are the</span> <span m="4038967">same</span>
  <span m="4039456">as</span> <span m="4039945">this</span> <span m="4040434">matrix?</span></p>
  <p><span m="4051681">All right?</span> <span m="4052170">So what I</span> <span
  m="4052380">did</span> <span m="4052660">is</span> <span m="4053110">the</span>
  <span m="4053280">Taylor</span> <span m="4053770">series</span> <span m="4055240">expansion</span>
  <span m="4056490">for all</span> <span m="4057010">these</span> <span m="4057190">non-linear</span>
  <span m="4057300">equations</span> <span m="4058714">and</span> <span m="4059142">write</span>
  <span m="4059570">them all</span> <span m="4060000">into a</span> <span m="4060485">matrix</span>
  <span m="4060970">form.</span> <span m="4063880">And</span> <span m="4064180">what</span>
  <span m="4064260">I''m trying to do</span> <span m="4064650">is I''m trying</span>
  <span m="4065140">to</span> <span m="4065630">solve for these</span> <span m="4066610">u1</span>
  <span m="4067100">to uN.</span> <span m="4069550">How do I</span> <span m="4070040">do
  that?</span> <span m="4073510">I</span> <span m="4073640">just</span> <span m="4074230">invert</span>
  <span m="4074540">the</span> <span m="4074650">whole</span> <span m="4074810">Jacobin.</span>
  <span m="4076301">If I call this</span> <span m="4076800">as</span> <span m="4077260">J,</span>
  <span m="4077980">then</span> <span m="4078400">my</span> <span m="4079800">u1,</span>
  <span m="4080254">et cetera,</span> <span m="4081616">uN</span> <span m="4083090">is</span>
  <span m="4083340">going</span> <span m="4083510">to</span> <span m="4083590">be</span>
  <span m="4083780">equal</span> <span m="4084310">to</span> <span m="4084490">u1
  0,</span> <span m="4086560">uN 0</span> <span m="4089250">minus</span> <span m="4090550">J</span>
  <span m="4091740">inverse</span> <span m="4092932">times</span> <span m="4093340">my</span>
  <span m="4093770">F1,</span> <span m="4094505">FN</span> <span m="4095680">evaluated</span>
  <span m="4096609">at</span> <span m="4097470">the</span> <span m="4097640">initial</span>
  <span m="4098100">guess.</span></p> <p><span m="4105404">Right?</span> <span m="4105900">So
  this is</span> <span m="4106396">the</span> <span m="4106892">solution</span> <span
  m="4107388">[INAUDIBLE].</span> <span m="4110380">This is one</span> <span m="4110660">step
  in the</span> <span m="4111134">Newton-Raphson,</span> <span m="4111608">right?</span>
  <span m="4114926">In</span> <span m="4115400">Newton-Raphson,</span> <span m="4116520">we</span>
  <span m="4116810">compute</span> <span m="4117100">the</span> <span m="4117250">residual</span>
  <span m="4119772">[INAUDIBLE]</span> <span m="4122147">at</span> <span m="4122750">the</span>
  <span m="4123040">initial</span> <span m="4123390">guess.</span> <span m="4125354">And</span>
  <span m="4125845">we</span> <span m="4126336">do</span> <span m="4126827">the</span>
  <span m="4127318">Jacobian.</span> <span m="4129282">[INAUDIBLE]</span> <span m="4129773">the</span>
  <span m="4130270">Jacobin</span> <span m="4130560">inverse</span> <span m="4131014">times</span>
  <span m="4131468">the</span> <span m="4131922">residuals.</span></p> <p><span m="4134649">Then,</span>
  <span m="4134880">you</span> <span m="4135130">stop</span> <span m="4136062">at</span>
  <span m="4136529">the</span> <span m="4136899">result</span> <span m="4137710">from</span>
  <span m="4137969">the</span> <span m="4138229">[INAUDIBLE].</span> <span m="4140000">And</span>
  <span m="4140437">get</span> <span m="4141311">your</span> <span m="4141750">next</span>
  <span m="4143040">step</span> <span m="4143300">solution.</span> <span m="4146165">And</span>
  <span m="4146622">what</span> <span m="4147080">is</span> <span m="4147310">the</span>
  <span m="4147380">next step</span> <span m="4147880">solution?</span> <span m="4149112">The</span>
  <span m="4149500">next</span> <span m="4149880">step</span> <span m="4150130">solution</span>
  <span m="4150720">is</span> <span m="4150899">the</span> <span m="4151130">zero</span>
  <span m="4151520">of</span> <span m="4151790">the</span> <span m="4151880">linear</span>
  <span m="4152380">approximation?</span> <span m="4155380">All right?</span> <span
  m="4157304">Which</span> <span m="4157728">hopefully</span> <span m="4158152">gives</span>
  <span m="4158576">you a better</span> <span m="4159000">initial</span> <span m="4159491">guess</span>
  <span m="4159982">than</span> <span m="4160473">u0.</span> <span m="4162437">And</span>
  <span m="4162928">what you</span> <span m="4163419">do</span> <span m="4163910">next</span>
  <span m="4164401">is</span> <span m="4164892">you</span> <span m="4165390">call</span>
  <span m="4165660">this set</span> <span m="4166120">of</span> <span m="4166580">u''s</span>
  <span m="4167040">to be</span> <span m="4167330">u parentheses</span> <span m="4167820">1.</span>
  <span m="4170607">We</span> <span m="4171086">call</span> <span m="4172392">these</span>
  <span m="4173316">as</span> <span m="4173778">u</span> <span m="4174240">parentheses</span>
  <span m="4175029">1.</span> <span m="4176505">And</span> <span m="4177000">then,</span>
  <span m="4177689">you</span> <span m="4177859">linearize</span> <span m="4178470">again</span>
  <span m="4178963">on</span> <span m="4179456">these.</span></p> <p><span m="4181430">So</span>
  <span m="4181660">the</span> <span m="4181750">one</span> <span m="4182000">dimensional</span>
  <span m="4182479">analog</span> <span m="4183290">is</span> <span m="4184280">this.</span>
  <span m="4186260">You</span> <span m="4186410">try</span> <span m="4186609">to</span>
  <span m="4186720">find</span> <span m="4187170">F</span> <span m="4187420">of</span>
  <span m="4187600">u.</span> <span m="4189130">OK,</span> <span m="4189630">you</span>
  <span m="4189710">want</span> <span m="4189890">to</span> <span m="4189970">find</span>
  <span m="4190210">F</span> <span m="4190380">of</span> <span m="4190540">u.</span>
  <span m="4190906">You</span> <span m="4191640">start</span> <span m="4192520">over</span>
  <span m="4193319">an initial</span> <span m="4193819">guess.</span> <span m="4194430">This</span>
  <span m="4194750">is</span> <span m="4194880">my</span> <span m="4195100">u0.</span>
  <span m="4197510">I</span> <span m="4197690">construct</span> <span m="4199030">my</span>
  <span m="4199260">first</span> <span m="4199690">order</span> <span m="4200170">Taylor</span>
  <span m="4200450">series</span> <span m="4201180">approximation,</span> <span m="4203170">which</span>
  <span m="4203360">is</span> <span m="4203470">what</span> <span m="4203770">in</span>
  <span m="4203880">this</span> <span m="4204050">case?</span> <span m="4207480">If</span>
  <span m="4207830">the</span> <span m="4208090">zeroth</span> <span m="4208670">order</span>
  <span m="4208900">term</span> <span m="4209240">is</span> <span m="4209610">going</span>
  <span m="4209780">to</span> <span m="4209860">be</span> <span m="4210040">this,</span>
  <span m="4210850">this is</span> <span m="4211270">the</span> <span m="4211430">zeroth</span>
  <span m="4211580">order</span> <span m="4212000">term.</span> <span m="4212280">It''s</span>
  <span m="4212570">a</span> <span m="4212865">constant,</span> <span m="4213160">right?</span>
  <span m="4213460">It''s</span> <span m="4213640">just</span> <span m="4213820">F</span>
  <span m="4213920">of</span> <span m="4214235">u0.</span></p> <p><span m="4216460">The</span>
  <span m="4216600">first</span> <span m="4216910">order</span> <span m="4217170">term</span>
  <span m="4217740">is</span> <span m="4218160">a</span> <span m="4218230">derivative</span>
  <span m="4218930">at</span> <span m="4219030">this</span> <span m="4219250">point,</span>
  <span m="4220080">which</span> <span m="4220290">is</span> <span m="4220440">going</span>
  <span m="4220600">to</span> <span m="4220660">give</span> <span m="4220960">you</span>
  <span m="4222690">this.</span> <span m="4223103">So</span> <span m="4223516">this</span>
  <span m="4223930">is</span> <span m="4224080">my</span> <span m="4225240">first</span>
  <span m="4225500">order</span> <span m="4225740">term</span> <span m="4226070">is</span>
  <span m="4226220">going</span> <span m="4226340">to</span> <span m="4226460">give</span>
  <span m="4226620">me</span> <span m="4226780">the</span> <span m="4227050">tangent</span>
  <span m="4227320">line.</span> <span m="4230640">My</span> <span m="4230880">u1</span>
  <span m="4231910">is the</span> <span m="4232210">solution</span> <span m="4233000">of</span>
  <span m="4234280">the</span> <span m="4234490">Taylor</span> <span m="4235450">approximation</span>
  <span m="4235845">equal to</span> <span m="4236240">0.</span> <span m="4236635">So</span>
  <span m="4237030">this</span> <span m="4237190">is</span> <span m="4237320">my</span>
  <span m="4237870">u1.</span> <span m="4240410">And</span> <span m="4240620">then,</span>
  <span m="4240880">I''m</span> <span m="4241080">going</span> <span m="4241250">to</span>
  <span m="4241320">linearize</span> <span m="4242040">around</span> <span m="4242370">this</span>
  <span m="4242590">again.</span> <span m="4242950">I''m</span> <span m="4243090">going</span>
  <span m="4243230">to</span> <span m="4243300">construct</span> <span m="4243760">another</span>
  <span m="4244535">first order</span> <span m="4244800">approximation,</span> <span
  m="4246050">and</span> <span m="4246400">go</span> <span m="4246560">to</span> <span
  m="4246660">this</span> <span m="4246900">point,</span> <span m="4247400">et cetera,</span>
  <span m="4247900">et cetera,</span> <span m="4248400">until</span> <span m="4248900">I</span>
  <span m="4249400">converge</span> <span m="4249900">to the</span> <span m="4250400">zero</span>
  <span m="4250900">at the blue</span> <span m="4251400">line?</span></p> <p><span
  m="4253720">Now,</span> <span m="4253990">it''s</span> <span m="4254140">hard</span>
  <span m="4254450">to</span> <span m="4255330">draw</span> <span m="4255710">this</span>
  <span m="4256147">picture</span> <span m="4257460">when</span> <span m="4258350">both</span>
  <span m="4258510">u</span> <span m="4258640">and</span> <span m="4259030">F</span>
  <span m="4259390">are</span> <span m="4260010">million</span> <span m="4260450">dimensional.</span>
  <span m="4262346">But</span> <span m="4262820">the</span> <span m="4263294">concept</span>
  <span m="4263768">is</span> <span m="4264242">the</span> <span m="4264716">same.</span>
  <span m="4265664">I construct</span> <span m="4266138">a</span> <span m="4266612">linear</span>
  <span m="4267086">approximation.</span> <span m="4268040">And</span> <span m="4268230">the</span>
  <span m="4268300">linear</span> <span m="4268620">approximation</span> <span m="4269280">can
  be arranged</span> <span m="4269780">into</span> <span m="4270280">matrix</span>
  <span m="4270710">form</span> <span m="4271640">using</span> <span m="4271900">the</span>
  <span m="4272000">Jacobin.</span> <span m="4273230">Jacobin</span> <span m="4273380">is
  just</span> <span m="4274772">a</span> <span m="4275236">matrix</span> <span m="4276164">containing</span>
  <span m="4276630">all</span> <span m="4277070">the</span> <span m="4277190">derivatives</span>
  <span m="4277830">of</span> <span m="4278080">Fu''s.</span> <span m="4280140">And</span>
  <span m="4280380">I</span> <span m="4280570">keep</span> <span m="4280860">iterating.</span>
  <span m="4284200">I</span> <span m="4284450">keep</span> <span m="4284920">iterating.</span>
  <span m="4286840">I solve</span> <span m="4287285">the</span> <span m="4287730">0</span>
  <span m="4287970">of the</span> <span m="4288120">linear</span> <span m="4288760">approximation,</span>
  <span m="4289300">linearize</span> <span m="4289906">again</span> <span m="4290392">at
  that new</span> <span m="4290880">point,</span> <span m="4291880">and</span> <span
  m="4292070">then</span> <span m="4292390">solve,</span> <span m="4293292">get</span>
  <span m="4293714">the</span> <span m="4294136">zero</span> <span m="4294558">of</span>
  <span m="4294980">that</span> <span m="4295250">linear</span> <span m="4295470">approximation.</span>
  <span m="4296310">I</span> <span m="4296777">linearize</span> <span m="4297244">again
  at</span> <span m="4297711">the</span> <span m="4298178">new point,</span> <span
  m="4299112">I get the</span> <span m="4300050">zero of</span> <span m="4300360">that</span>
  <span m="4300720">linear</span> <span m="4301212">approximation,</span> <span m="4301704">and
  then</span> <span m="4302196">linearize</span> <span m="4302688">again at the</span>
  <span m="4303180">new</span> <span m="4303672">point.</span> <span m="4308592">Any
  questions on this?</span></p> <p><span m="4315480">General</span> <span m="4316380">technique</span>
  <span m="4317294">of</span> <span m="4317751">solving</span> <span m="4318210">large</span>
  <span m="4318570">systems</span> <span m="4319300">of</span> <span m="4319560">non-linear</span>
  <span m="4320046">equations.</span> <span m="4326860">Using</span> <span m="4326950">the
  fact</span> <span m="4327220">that</span> <span m="4327530">we</span> <span m="4327770">are</span>
  <span m="4328020">already</span> <span m="4328400">good as</span> <span m="4328850">solving</span>
  <span m="4329170">large</span> <span m="4329670">systems</span> <span m="4330170">of</span>
  <span m="4330670">linear</span> <span m="4331170">equations.</span> <span m="4336060">OK,</span>
  <span m="4337470">now</span> <span m="4337820">I''m</span> <span m="4337980">all</span>
  <span m="4338250">out</span> <span m="4338440">of</span> <span m="4339990">things.</span>
  <span m="4342820">Just time</span> <span m="4342980">to</span> <span m="4343120">answer
  your</span> <span m="4343610">questions.</span> <span m="4348800">Yes?</span></p>
  <p><span m="4349490">AUDIENCE: Will we</span> <span m="4349910">be expected</span>
  <span m="4350070">to</span> <span m="4350555">[INAUDIBLE]</span></p> <p><span m="4352980">QIQI
  WANG: No,</span> <span m="4353550">you</span> <span m="4353730">don''t</span> <span
  m="4354230">need to quote</span> <span m="4354730">anything.</span> <span m="4361630">You</span>
  <span m="4361810">don''t</span> <span m="4361940">need</span> <span m="4362363">to</span>
  <span m="4363210">have your hands</span> <span m="4363540">on</span> <span m="4363650">the</span>
  <span m="4363720">keyboard.</span></p> <p><span m="4377080">Yes?</span></p> <p><span
  m="4377340">AUDIENCE: [INAUDIBLE]</span></p> <p><span m="4380920">QIQI WANG: What</span>
  <span m="4381160">does</span> <span m="4381270">big</span> <span m="4381540">F</span>
  <span m="4381860">represent</span> <span m="4382285">in</span> <span m="4382540">this</span>
  <span m="4382640">case?</span> <span m="4383540">Big</span> <span m="4384050">F</span>
  <span m="4385440">represents</span> <span m="4387690">the</span> <span m="4387950">function</span>
  <span m="4389236">of</span> <span m="4389580">u</span> <span m="4390380">if</span>
  <span m="4390810">we want to</span> <span m="4391240">get the zero.</span> <span
  m="4397750">If</span> <span m="4397960">I</span> <span m="4398090">want</span> <span
  m="4398510">to</span> <span m="4399090">solve</span> <span m="4399210">[INAUDIBLE],</span>
  <span m="4400310">if</span> <span m="4400723">I</span> <span m="4401136">use</span>
  <span m="4401550">an</span> <span m="4401830">implicit</span> <span m="4402090">scheme</span>
  <span m="4402710">and</span> <span m="4403070">I</span> <span m="4403180">want</span>
  <span m="4403480">to</span> <span m="4404060">evolve</span> <span m="4404370">from
  this</span> <span m="4404831">case</span> <span m="4405292">to</span> <span m="4405753">the</span>
  <span m="4406214">next</span> <span m="4406675">u,</span> <span m="4407140">to the
  next</span> <span m="4407370">time</span> <span m="4407833">step,</span> <span m="4408760">then</span>
  <span m="4409120">my</span> <span m="4409420">F</span> <span m="4409695">of</span>
  <span m="4409970">u</span> <span m="4410833">would</span> <span m="4411306">be</span>
  <span m="4411780">the left hand</span> <span m="4411920">side</span> <span m="4412240">of</span>
  <span m="4412560">the</span> <span m="4414040">scheme</span> <span m="4414420">minus</span>
  <span m="4414675">the right hand side</span> <span m="4414930">of</span> <span m="4415330">the</span>
  <span m="4415797">scheme,</span> <span m="4417530">right?</span></p> <p><span m="4419240">Imagine</span>
  <span m="4419450">if I</span> <span m="4419590">have</span> <span m="4419810">Backward
  Euler.</span> <span m="4421642">Then</span> <span m="4422100">my</span> <span m="4422220">big
  F</span> <span m="4422500">would</span> <span m="4422905">be</span> <span m="4423310">u
  minus</span> <span m="4423700">uk</span> <span m="4424153">divided</span> <span
  m="4424606">by</span> <span m="4425060">delta</span> <span m="4425310">t</span>
  <span m="4425630">minus</span> <span m="4425990">F</span> <span m="4426390">of</span>
  <span m="4426700">u.</span> <span m="4429160">That is</span> <span m="4429652">the</span>
  <span m="4430144">Backward Euler.</span> <span m="4431620">If</span> <span m="4431810">I</span>
  <span m="4432580">trapezoidal,</span> <span m="4433370">my</span> <span m="4433660">big</span>
  <span m="4434087">F would</span> <span m="4434514">be</span> <span m="4434941">u
  minus uk</span> <span m="4435370">over</span> <span m="4435750">delta</span> <span
  m="4436130">t</span> <span m="4438190">minus</span> <span m="4438500">half of</span>
  <span m="4438840">F of u</span> <span m="4440590">minus</span> <span m="4441080">half
  of</span> <span m="4441537">F of uk.</span> <span m="4445193">All right?</span>
  <span m="4445650">And</span> <span m="4445800">the</span> <span m="4446080">difference</span>
  <span m="4446340">is</span> <span m="4447615">implicit</span> <span m="4448040">schemes</span>
  <span m="4448500">are</span> <span m="4449000">going</span> <span m="4449500">to</span>
  <span m="4450000">get</span> <span m="4450500">a</span> <span m="4451000">different</span>
  <span m="4451500">value.</span> <span m="4456500">I have a</span> <span m="4456690">Backward
  Euler,</span> <span m="4458686">[INAUDIBLE],</span> <span m="4460183">half of that</span>
  <span m="4460682">F of u</span> <span m="4461181">plus</span> <span m="4461680">half
  of that</span> <span m="4462179">uk.</span> <span m="4462678">And that is</span>
  <span m="4463177">in the</span> <span m="4463676">derivative.</span></p> <p><span
  m="4468167">Whatever</span> <span m="4468670">the</span> <span m="4468880">scheme</span>
  <span m="4469175">is,</span> <span m="4470110">F</span> <span m="4470470">is</span>
  <span m="4471430">the thing</span> <span m="4471540">along</span> <span m="4472270">with</span>
  <span m="4472610">[INAUDIBLE]</span> <span m="4473087">zero</span> <span m="4473564">that</span>
  <span m="4474041">big F</span> <span m="4474518">is</span> <span m="4474995">[INAUDIBLE].</span></p>
  <p><span m="4475472">AUDIENCE: [INAUDIBLE]</span></p> <p><span m="4476430">QIQI
  WANG: It''s a</span> <span m="4476980">[INAUDIBLE],</span> <span m="4477510">yes.</span></p>
  <p><span m="4492670">Questions?</span> <span m="4494638">After</span> <span m="4495130">this,</span>
  <span m="4495622">we are going to</span> <span m="4497098">[INAUDIBLE]</span> <span
  m="4497590">the midterm.</span></p> <p><span m="4504478">AUDIENCE: [INAUDIBLE]</span></p>
  <p><span m="4507430">QIQI WANG: All right.</span> <span m="4507970">Anything</span>
  <span m="4508290">else</span> <span m="4508610">I can talk to you</span> <span m="4509057">about?</span>
  <span m="4511740">All</span> <span m="4511890">these</span> <span m="4512070">materials?</span>
  <span m="4513120">Oh,</span> <span m="4513380">and</span> <span m="4513750">just</span>
  <span m="4513970">to</span> <span m="4514840">remind,</span> <span m="4516990">we</span>
  <span m="4517190">are</span> <span m="4517290">really</span> <span m="4517580">looking</span>
  <span m="4518560">at</span> <span m="4518630">the</span> <span m="4518700">measurable</span>
  <span m="4519170">outcomes.</span> <span m="4520110">And</span> <span m="4520840">don''t</span>
  <span m="4521100">forget</span> <span m="4521460">to go</span> <span m="4521936">[INAUDIBLE]</span>
  <span m="4529076">something</span> <span m="4529560">that</span> <span m="4529770">[INAUDIBLE].</span>
  <span m="4536406">Analytical</span> <span m="4536880">solutions</span> <span m="4537690">[INAUDIBLE]</span>
  <span m="4537820">what is the</span> <span m="4538301">solution</span> <span m="4538782">of</span>
  <span m="4539263">u</span> <span m="4539744">[INAUDIBLE]?</span> <span m="4541187">And</span>
  <span m="4541668">things</span> <span m="4542149">like</span> <span m="4542630">that.</span>
  <span m="4544080">And</span> <span m="4544340">if</span> <span m="4544610">the</span>
  <span m="4544690">solution</span> <span m="4544960">is</span> <span m="4545110">stable,</span>
  <span m="4545580">when it</span> <span m="4545950">is</span> <span m="4546170">unstable,</span>
  <span m="4546250">you need to know</span> <span m="4546692">that</span> <span m="4547134">and</span>
  <span m="4547576">things</span> <span m="4548018">like</span> <span m="4548460">that.</span>
  <span m="4549350">So</span> <span m="4549930">this</span> <span m="4550090">is important.</span>
  <span m="4550340">Yeah?</span></p> <p><span m="4551729">AUDIENCE: [INAUDIBLE]</span></p>
  <p><span m="4556370">QIQI WANG: Should</span> <span m="4556550">d of dt</span> <span
  m="4556960">be</span> <span m="4557120">equal to</span> <span m="4557270">lambda
  u?</span> <span m="4559080">You need to</span> <span m="4559250">solve</span> <span
  m="4559600">it</span> <span m="4560080">analytically.</span> <span m="4561018">Huh?</span></p>
  <p><span m="4561956">AUDIENCE: [INAUDIBLE]</span></p> <p><span m="4567790">QIQI
  WANG: Yeah.</span> <span m="4568350">For</span> <span m="4568700">d of dt</span>
  <span m="4569300">over</span> <span m="4569380">the</span> <span m="4569730">lambda</span>
  <span m="4570100">u,</span> <span m="4570920">you</span> <span m="4571090">need</span>
  <span m="4571240">to</span> <span m="4571330">be</span> <span m="4571440">able</span>
  <span m="4571620">to</span> <span m="4571690">solve it</span> <span m="4572046">analytically,</span>
  <span m="4572760">yeah.</span></p> <p><span m="4574018">AUDIENCE: [INAUDIBLE]</span></p>
  <p><span m="4579452">QIQI WANG: Huh?</span></p> <p><span m="4580440">AUDIENCE: [INAUDIBLE]</span></p>
  <p><span m="4582920">QIQI WANG: Yes,</span> <span m="4583310">yes.</span> <span
  m="4583830">D of dt</span> <span m="4584380">equal</span> <span m="4584500">to</span>
  <span m="4584650">au,</span> <span m="4585480">yes,</span> <span m="4585830">right.</span>
  <span m="4586740">Any</span> <span m="4587810">matrix,</span> <span m="4588330">A,</span>
  <span m="4589086">right?</span> <span m="4590060">You need to be</span> <span m="4590540">able</span>
  <span m="4590740">to</span> <span m="4590970">solve it.</span></p> <p><span m="4591706">AUDIENCE:
  [INAUDIBLE]</span></p> <p><span m="4592618">[LAUGHTER]</span></p> <p><span m="4594898">QIQI
  WANG: Yeah.</span> <span m="4596580">My</span> <span m="4596820">A</span> <span
  m="4597290">can be</span> <span m="4597400">a trillion by</span> <span m="4597940">a
  trillion.</span> <span m="4600560">And</span> <span m="4600990">you</span> <span
  m="4601690">need to know</span> <span m="4603010">how</span> <span m="4603380">to</span>
  <span m="4603530">solve</span> <span m="4604015">it.</span> <span m="4604500">You</span>
  <span m="4604740">are</span> <span m="4604820">not</span> <span m="4605220">expected</span>
  <span m="4605800">to--</span></p> <p><span m="4607480">AUDIENCE: [INAUDIBLE]</span></p>
  <p><span m="4609740">QIQI WANG: Hm?</span></p> <p><span m="4611240">AUDIENCE: [INAUDIBLE]</span></p>
  <p><span m="4615330">QIQI WANG: Yeah,</span> <span m="4617220">of</span> <span m="4617390">course,</span>
  <span m="4617750">you</span> <span m="4617760">won''t</span> <span m="4618210">be</span>
  <span m="4618350">able</span> <span m="4618720">to</span> <span m="4620360">do</span>
  <span m="4620630">the</span> <span m="4621010">eigenvalue</span> <span m="4621330">problem</span>
  <span m="4621760">of</span> <span m="4621970">A in your</span> <span m="4622403">head</span>
  <span m="4622836">if</span> <span m="4623269">A</span> <span m="4623702">is</span>
  <span m="4624135">a</span> <span m="4624570">1,000 by</span> <span m="4624710">1,000</span>
  <span m="4625070">matrix.</span> <span m="4626150">But</span> <span m="4626350">you</span>
  <span m="4626500">need</span> <span m="4626690">to</span> <span m="4626810">know</span>
  <span m="4628440">how</span> <span m="4628630">to</span> <span m="4629070">get</span>
  <span m="4629270">the</span> <span m="4629500">analytical</span> <span m="4629830">solution
  of</span> <span m="4630070">the</span> <span m="4630560">ODE.</span></p> <p><span
  m="4632520">AUDIENCE: [INAUDIBLE]</span></p> <p><span m="4634480">QIQI WANG: Hm?</span></p>
  <p><span m="4635460">AUDIENCE: [INAUDIBLE]</span></p> <p><span m="4636930">QIQI
  WANG: Yeah.</span></p> <p><span m="4638400">AUDIENCE: [INAUDIBLE]</span></p> <p><span
  m="4652120">QIQI WANG: All right.</span> <span m="4653130">Anything else?</span>
  <span m="4655250">And</span> <span m="4656100">homework</span> <span m="4656577">here.</span>
  <span m="4660763">If you didn''t</span> <span m="4661710">[INAUDIBLE]</span> <span
  m="4662030">homework</span> <span m="4662350">for</span> <span m="4662816">[INAUDIBLE],</span>
  <span m="4664900">the</span> <span m="4665200">previous</span> <span m="4665500">homeworks,</span>
  <span m="4665800">you can</span> <span m="4666100">always</span> <span m="4666400">come
  to</span> <span m="4666700">my</span> <span m="4667000">office</span> <span m="4667300">and</span>
  <span m="4667900">figure it out.</span></p>'
type: course
uid: 02f302e0438775398792b31bbec42980

---
None