---
about_this_resource_text: <p><strong>Description:</strong> This video begins with
  a review of the assigned readings and the previous class, and then introduces consistency
  and stability.  Students work to solve a ballistics (cannonball trajectory) problem
  using ODEs.</p> <p><strong>Instructors:</strong> Qiqi Wang</p> <p>The recording
  quality of this video is the best available from the source.</p>
course_id: 16-90-computational-methods-in-aerospace-engineering-spring-2014
embedded_media:
- id: Video-YouTube-Stream
  media_location: DZtkqqY2Jn4
  parent_uid: 3e80d2947c11c63304921d680133c788
  title: Video-YouTube-Stream
  type: Video
  uid: 4f77a0afecdfe9a5d399a2abea7a19aa
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/DZtkqqY2Jn4/default.jpg
  parent_uid: 3e80d2947c11c63304921d680133c788
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 062f79a14f3546fbcaf9bd8a6348e6cf
- id: 3Play-3PlayYouTubeid-MP4
  media_location: DZtkqqY2Jn4
  parent_uid: 3e80d2947c11c63304921d680133c788
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: e623ccebfeb0dc1f4aec9885b8e5c7ab
- id: DZtkqqY2Jn4.srt
  parent_uid: 3e80d2947c11c63304921d680133c788
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-4-numerical-integration-of-odes-stability-and-a-ballistics-problem/DZtkqqY2Jn4.srt
  title: 3play caption file
  type: null
  uid: 0d281b64f2c6b6555e783789e5f67ff9
- id: DZtkqqY2Jn4.pdf
  parent_uid: 3e80d2947c11c63304921d680133c788
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-4-numerical-integration-of-odes-stability-and-a-ballistics-problem/DZtkqqY2Jn4.pdf
  title: 3play pdf file
  type: null
  uid: ea0cd1e0bcb8191042b6254426b61beb
- id: Caption-3Play YouTube id-SRT
  parent_uid: 3e80d2947c11c63304921d680133c788
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 7d29a963379baf2942fee1891bb6e7e2
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 3e80d2947c11c63304921d680133c788
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 57d295f3a2e5a5be9784269463dce213
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT16.90S14/MIT16_90S14_L04_300k.mp4
  parent_uid: 3e80d2947c11c63304921d680133c788
  title: Video-Internet Archive-MP4
  type: Video
  uid: 9db9002e750483e79fd86a846c0de182
inline_embed_id: 6114480session4:numericalintegrationofodes:stabilityandaballisticsproblem68761487
layout: video
order_index: null
parent_uid: 809ebf7c44bfb36e8786306747d7e32f
related_resources_text: ''
short_url: session-4-numerical-integration-of-odes-stability-and-a-ballistics-problem
technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-4-numerical-integration-of-odes-stability-and-a-ballistics-problem
template_type: Tabbed
title: 'Session 4: Numerical Integration of ODEs: Stability and a ballistics problem'
transcript: '<p><span m="30">The</span> <span m="130">following</span> <span m="600">content</span>
  <span m="1090">is</span> <span m="1210">provided</span> <span m="1660">under</span>
  <span m="1900">a</span> <span m="1950">Creative</span> <span m="2400">Commons</span>
  <span m="2820">license.</span> <span m="3770">Your</span> <span m="3880">support</span>
  <span m="4400">will</span> <span m="4570">help</span> <span m="4790">MIT</span>
  <span m="5280">OpenCourseWare</span> <span m="6020">continue</span> <span m="6510">to</span>
  <span m="6670">offer</span> <span m="6980">high</span> <span m="7200">quality</span>
  <span m="7680">educational</span> <span m="8350">resources</span> <span m="8920">for</span>
  <span m="9040">free.</span> <span m="10100">To</span> <span m="10130">make</span>
  <span m="10330">a</span> <span m="10380">donation</span> <span m="11090">or</span>
  <span m="11310">to</span> <span m="11430">view</span> <span m="11640">additional</span>
  <span m="12050">materials</span> <span m="12670">from</span> <span m="12850">hundreds</span>
  <span m="13180">of</span> <span m="13280">MIT</span> <span m="13650">courses,</span>
  <span m="14960">visit</span> <span m="15150">MIT</span> <span m="15670">OpenCourseWare</span>
  <span m="16580">at</span> <span m="16920">ocw.mit.edu.</span></p><p><span m="26320">QIQI
  WANG: Hello,</span> <span m="26930">everybody.</span> <span m="29940">So</span>
  <span m="30840">I</span> <span m="30950">guess</span> <span m="31240">yesterday</span>
  <span m="31680">was</span> <span m="31970">the</span> <span m="34370">a</span> <span
  m="34625">really</span> <span m="34880">serious</span> <span m="35670">reading</span>
  <span m="35965">due.</span> <span m="37000">How</span> <span m="37510">is</span>
  <span m="37600">that</span> <span m="37750">going?</span> <span m="38320">How</span>
  <span m="38470">do you like the</span> <span m="38870">reading?</span></p><p><span
  m="39460">AUDIENCE: What''s</span> <span m="39843">consistency?</span></p><p><span
  m="40610">QIQI WANG: Hm?</span></p><p><span m="41450">AUDIENCE: What''s</span> <span
  m="41870">consistency?</span></p><p><span m="43130">QIQI WANG: What''s</span> <span
  m="43490">consistency?</span> <span m="45590">Consistency</span> <span m="46630">is</span>
  <span m="48230">the</span> <span m="48320">scheme</span> <span m="48730">being</span>
  <span m="49120">at</span> <span m="49310">least</span> <span m="49600">first</span>
  <span m="49890">order</span> <span m="50360">accurate.</span> <span m="52290">OK?</span>
  <span m="52600">So</span> <span m="52790">the</span> <span m="53180">it''s</span>
  <span m="53730">local--</span> <span m="54050">consistently</span> <span m="54900">is</span>
  <span m="55770">related</span> <span m="56350">to</span> <span m="56440">local</span>
  <span m="57110">order of</span> <span m="57490">accuracy.</span> <span m="58390">So</span>
  <span m="58650">if</span> <span m="59120">the</span> <span m="59420">scheme</span>
  <span m="59690">is</span> <span m="60910">at</span> <span m="61100">least</span>
  <span m="61460">first</span> <span m="61870">order</span> <span m="62600">local</span>
  <span m="62980">accuracy,</span> <span m="63600">then</span> <span m="63850">it</span>
  <span m="63980">is</span> <span m="64160">consistent.</span></p><p><span m="65241">AUDIENCE:
  [INAUDIBLE].</span></p><p><span m="68610">QIQI WANG: It</span> <span m="68790">means</span>
  <span m="69060">the</span> <span m="69180">truncating</span> <span m="69740">error.</span>
  <span m="70060">If you</span> <span m="70473">do the truncating</span> <span m="70886">error</span>
  <span m="71300">analysis,</span> <span m="72345">the  data</span> <span m="72810">series</span>
  <span m="73100">gives</span> <span m="73390">you a</span> <span m="73860">truncating</span>
  <span m="74390">error</span> <span m="74700">of</span> <span m="76030">at</span>
  <span m="76200">least</span> <span m="76810">delta</span> <span m="76990">t</span>
  <span m="77180">squared</span> <span m="77780">if</span> <span m="77950">you</span>
  <span m="78050">don''t</span> <span m="78380">divide</span> <span m="78440">by</span>
  <span m="78770">delta</span> <span m="78860">t.</span> <span m="80410">At</span>
  <span m="80670">least</span> <span m="81115">delta</span> <span m="81560">t</span>
  <span m="82005">if you</span> <span m="82450">divide</span> <span m="82895">by delta
  t.</span> <span m="83530">So</span> <span m="84210">that''s</span> <span m="84430">what</span>
  <span m="84570">it</span> <span m="84600">means</span> <span m="84940">by</span>
  <span m="85380">being</span> <span m="85610">consistent.</span> <span m="86680">I
  mean</span> <span m="86860">the</span> <span m="87130">word</span> <span m="87400">consistent</span>
  <span m="88290">basically</span> <span m="88730">means</span> <span m="89400">if</span>
  <span m="89700">you</span> <span m="89820">look</span> <span m="90280">at</span>
  <span m="90580">the</span> <span m="90820">scheme,</span> <span m="92700">it is</span>
  <span m="93170">somewhat</span> <span m="93570">consistent</span> <span m="94280">to
  the</span> <span m="94630">differential</span> <span m="95170">equation.</span>
  <span m="95810">So</span> <span m="96500">the</span> <span m="96590">scheme</span>
  <span m="97120">on</span> <span m="97290">one</span> <span m="97510">hand,</span>
  <span m="98664">the</span> <span m="99450">differential</span> <span m="99970">equation</span>
  <span m="100290">on</span> <span m="100390">the</span> <span m="100490">other</span>
  <span m="100760">hand.</span> <span m="101150">They</span> <span m="101470">are</span>
  <span m="101820">consistent,</span> <span m="102296">right?</span></p><p><span m="103724">AUDIENCE:
  So</span> <span m="104200">that would</span> <span m="104680">mean</span> <span
  m="104930">that the</span> <span m="105427">scheme</span> <span m="105924">is self-satisfied</span>
  <span m="107912">with the</span> <span m="108409">[INAUDIBLE]?</span></p><p><span
  m="109900">QIQI WANG: The</span> <span m="110070">scheme</span> <span m="110500">here--</span>
  <span m="110800">so</span> <span m="110890">the</span> <span m="110960">question</span>
  <span m="111250">is</span> <span m="111550">does</span> <span m="111850">that mean</span>
  <span m="112170">the</span> <span m="112300">scheme</span> <span m="112780">satisfies</span>
  <span m="113760">the</span> <span m="113860">differential</span> <span m="114170">equation?</span>
  <span m="114670">The</span> <span m="114770">answer</span> <span m="115100">is</span>
  <span m="115330">the</span> <span m="115460">scheme</span> <span m="115900">is</span>
  <span m="116140">never</span> <span m="116500">going</span> <span m="116650">to</span>
  <span m="116860">satisfy</span> <span m="117360">the</span> <span m="117460">differential</span>
  <span m="117900">equation</span> <span m="118340">exactly.</span> <span m="119090">But</span>
  <span m="119490">as</span> <span m="119810">you</span> <span m="119980">make</span>
  <span m="120450">delta</span> <span m="120660">t</span> <span m="121090">smaller</span>
  <span m="121510">and</span> <span m="121670">smaller,</span> <span m="122580">it
  is</span> <span m="123030">going to</span> <span m="123300">satisfy</span> <span
  m="123740">the differential</span> <span m="124180">equation</span> <span m="124620">better</span>
  <span m="125060">and</span> <span m="125500">better.</span> <span m="126820">OK.</span>
  <span m="127140">That''s</span> <span m="127440">what</span> <span m="127650">it</span>
  <span m="127760">means</span> <span m="128139">by</span> <span m="128889">being</span>
  <span m="129449">consistent.</span></p><p><span m="130760">AUDIENCE: So if</span>
  <span m="131235">it wasn''t</span> <span m="131710">consistent,</span> <span m="132185">it
  would</span> <span m="132660">make</span> <span m="133135">the</span> <span m="133610">[INAUDIBLE].</span></p><p><span
  m="137885">QIQI WANG: Yes. So,</span> <span m="138360">right.</span> <span m="138730">If</span>
  <span m="139870">a</span> <span m="140090">scheme</span> <span m="140320">is</span>
  <span m="140540">not</span> <span m="140830">consistent,</span> <span m="141710">what</span>
  <span m="142000">does</span> <span m="142160">that</span> <span m="142400">mean?</span>
  <span m="143090">That</span> <span m="143380">means</span> <span m="143680">if</span>
  <span m="143810">you</span> <span m="143900">make</span> <span m="144160">the</span>
  <span m="144240">delta t</span> <span m="144610">smaller</span> <span m="145030">and</span>
  <span m="145170">smaller,</span> <span m="146020">the</span> <span m="146140">difference</span>
  <span m="146850">between</span> <span m="147260">the</span> <span m="147870">discrete</span>
  <span m="148490">scheme</span> <span m="149060">and</span> <span m="149260">the</span>
  <span m="149320">continual</span> <span m="149880">differential</span> <span m="150300">equation</span>
  <span m="150580">is</span> <span m="150810">not</span> <span m="151200">going</span>
  <span m="151350">to</span> <span m="151410">become</span> <span m="151730">smaller.</span>
  <span m="152510">It</span> <span m="152680">may</span> <span m="152840">become</span>
  <span m="153140">larger.</span> <span m="153620">It may</span> <span m="153790">remain</span>
  <span m="154450">constant.</span> <span m="154725">It</span> <span m="155000">may</span>
  <span m="155340">go</span> <span m="155730">around</span> <span m="155910">but it
  doesn''t</span> <span m="156394">go to</span> <span m="156878">zero.</span></p><p><span
  m="157846">AUDIENCE: How does</span> <span m="158330">that differ from</span> <span
  m="158814">the definition of</span> <span m="159298">stability?</span></p><p><span
  m="160266">QIQI WANG: How does</span> <span m="160750">that</span> <span m="161020">differ</span>
  <span m="161490">from</span> <span m="161800">the</span> <span m="161900">definition</span>
  <span m="162570">of</span> <span m="162750">stability?</span> <span m="164060">We''re</span>
  <span m="164390">going to</span> <span m="164720">see</span> <span m="164920">there
  are--</span> <span m="165350">when</span> <span m="165620">you</span> <span m="165780">talk</span>
  <span m="166020">about</span> <span m="166350">stability,</span> <span m="166840">there</span>
  <span m="166920">are</span> <span m="166990">two</span> <span m="167180">types</span>
  <span m="167620">of</span> <span m="168300">stability.</span> <span m="169120">They</span>
  <span m="169510">are</span> <span m="171020">different</span> <span m="172010">in</span>
  <span m="172180">the</span> <span m="172280">sense</span> <span m="172600">that</span>
  <span m="173180">a</span> <span m="173350">consistency</span> <span m="174100">concerns</span>
  <span m="175720">the</span> <span m="176170">Taylor</span> <span m="176620">series</span>
  <span m="176980">analysis.</span> <span m="177964">You can</span> <span m="178411">figure
  out</span> <span m="178860">consistency</span> <span m="179450">by doing</span>
  <span m="179870">data</span> <span m="180210">series</span> <span m="180580">analysis.</span>
  <span m="182620">Stability</span> <span m="183410">has</span> <span m="183590">nothing</span>
  <span m="183950">to</span> <span m="184080">do</span> <span m="184370">with</span>
  <span m="184630">data series.</span> <span m="187530">Right?</span></p><p><span
  m="187750">We are</span> <span m="187820">going</span> <span m="187950">to</span>
  <span m="188090">see</span> <span m="188700">when</span> <span m="188940">you</span>
  <span m="189150">check</span> <span m="189650">stability,</span> <span m="190435">you''re</span>
  <span m="190830">plugging in</span> <span m="192401">a</span> <span m="192790">half</span>
  <span m="193240">solution</span> <span m="193680">that</span> <span m="193860">grows</span>
  <span m="194310">exponentially</span> <span m="195820">and</span> <span m="196200">seeing</span>
  <span m="197170">can</span> <span m="197475">the</span> <span m="199390">exponential</span>
  <span m="200310">be</span> <span m="200690">a</span> <span m="201240">growing</span>
  <span m="201840">exponential?</span> <span m="202710">Or</span> <span m="203090">the</span>
  <span m="203320">exponential</span> <span m="203680">has</span> <span m="203890">to</span>
  <span m="204010">be a</span> <span m="204420">decaying</span> <span m="204740">exponential?</span>
  <span m="207150">If all</span> <span m="207390">the exponential</span> <span m="208540">solutions</span>
  <span m="209090">have</span> <span m="209290">to</span> <span m="209400">be</span>
  <span m="209760">decaying</span> <span m="210300">exponentials,</span> <span m="212180">then</span>
  <span m="212650">the</span> <span m="212740">scheme</span> <span m="213130">is</span>
  <span m="216860">stable.</span> <span m="218320">If</span> <span m="218610">there</span>
  <span m="218800">is</span> <span m="219050">one</span> <span m="219570">mode</span>
  <span m="220070">that</span> <span m="220320">can</span> <span m="220570">be</span>
  <span m="220850">a</span> <span m="221130">growing</span> <span m="221790">exponential,</span>
  <span m="222370">then</span> <span m="224910">the</span> <span m="225140">scheme</span>
  <span m="225330">is</span> <span m="225490">unstable.</span></p><p><span m="229160">OK.</span>
  <span m="229510">I</span> <span m="229590">clarified</span> <span m="231640">a</span>
  <span m="232020">question</span> <span m="232400">about</span> <span m="232780">consistency.</span>
  <span m="233380">That</span> <span m="233570">is</span> <span m="233730">basically</span>
  <span m="234110">the</span> <span m="234210">scheme</span> <span m="234620">is</span>
  <span m="234960">at</span> <span m="235410">least</span> <span m="235510">first
  order</span> <span m="235600">accurate.</span> <span m="236894">What</span> <span
  m="237316">is the</span> <span m="237740">difference</span> <span m="238070">between</span>
  <span m="238443">consistency</span> <span m="238816">and</span> <span m="239190">stability?</span>
  <span m="240490">Consistency</span> <span m="240910">is</span> <span m="241170">by</span>
  <span m="241500">data</span> <span m="241830">series</span> <span m="242170">analysis.</span>
  <span m="243390">Stability</span> <span m="243860">is</span> <span m="244090">by</span>
  <span m="244440">plugging</span> <span m="246190">exponentially</span> <span m="246940">growing</span>
  <span m="247390">solutions.</span> <span m="248826">So</span> <span m="249320">basically</span>
  <span m="249820">asking</span> <span m="250020">does</span> <span m="250280">the</span>
  <span m="250380">scheme</span> <span m="250780">allow</span> <span m="251780">exponentially</span>
  <span m="252810">growing</span> <span m="253140">solutions?</span> <span m="258970">Any</span>
  <span m="259160">other</span> <span m="259279">questions</span> <span m="259700">that</span>
  <span m="259899">arise</span> <span m="260250">in</span> <span m="260339">the reading?</span>
  <span m="261290">If</span> <span m="261519">one</span> <span m="261760">person</span>
  <span m="262070">has</span> <span m="262400">a</span> <span m="263500">concern,</span>
  <span m="264290">probably</span> <span m="264760">your classmate</span> <span m="265200">also</span>
  <span m="265640">has it.</span> <span m="266080">So</span> <span m="266360">please</span>
  <span m="266730">raise</span> <span m="267090">it.</span></p><p><span m="268540">AUDIENCE:
  Maybe</span> <span m="268780">one other</span> <span m="268940">way</span> <span
  m="269160">to</span> <span m="269390">think about</span> <span m="269868">the</span>
  <span m="270346">definition</span> <span m="270824">of stability</span> <span m="271302">is</span>
  <span m="280405">analysis.</span> <span m="281800">[INAUDIBLE]</span> <span m="282730">the</span>
  <span m="283195">solution</span> <span m="283660">behaves</span> <span m="284125">mostly</span>
  <span m="284590">[INAUDIBLE].</span> <span m="286450">When we</span> <span m="286790">think</span>
  <span m="286890">about</span> <span m="287240">stability,</span> <span m="287920">meaning</span>
  <span m="288418">that we''re</span> <span m="288916">taking the</span> <span m="289414">relationship.</span>
  <span m="289912">We''re</span> <span m="290410">looking</span> <span m="290908">at</span>
  <span m="291406">how</span> <span m="291904">[INAUDIBLE]</span> <span m="298378">analysis.</span>
  <span m="299872">Other</span> <span m="300370">things</span> <span m="300868">[INAUDIBLE].</span>
  <span m="306844">The other is</span> <span m="307342">[INAUDIBLE].</span> <span
  m="309334">Because as</span> <span m="309832">w</span> <span m="310330">goes</span>
  <span m="310828">to 0,</span> <span m="311326">[INAUDIBLE].</span> <span m="316804">Because</span>
  <span m="317302">I think more</span> <span m="317800">and more</span> <span m="318298">[INAUDIBLE]</span>
  <span m="319792">really</span> <span m="320290">[INAUDIBLE].</span> <span m="323278">You
  could probably think</span> <span m="323790">there''s</span> <span m="324060">a
  few</span> <span m="324340">different</span> <span m="324826">[INAUDIBLE].</span>
  <span m="325312">You''re going</span> <span m="325474">to</span> <span m="325636">need</span>
  <span m="325798">both</span> <span m="326284">of those</span> <span m="326770">in
  order</span> <span m="327256">to</span> <span m="327742">analyze</span> <span m="328228">[INAUDIBLE].</span></p><p><span
  m="335032">QIQI WANG: Yes.</span> <span m="335530">Thank</span> <span m="335730">you.</span>
  <span m="336213">Thank you</span> <span m="336696">for the</span> <span m="337180">[INAUDIBLE].</span>
  <span m="339640">Any</span> <span m="339850">other</span> <span m="339990">questions?</span>
  <span m="342290">No?</span> <span m="343160">Then</span> <span m="343400">I</span>
  <span m="343830">basically</span> <span m="344240">want</span> <span m="344460">to</span>
  <span m="344550">very</span> <span m="344830">quickly</span> <span m="345390">review</span>
  <span m="345880">and</span> <span m="346070">recap</span> <span m="346940">what</span>
  <span m="347410">we</span> <span m="347700">did</span> <span m="347990">in the</span>
  <span m="348220">previous</span> <span m="348530">lectures</span> <span m="348960">and</span>
  <span m="349140">also</span> <span m="349872">what</span> <span m="350274">we</span>
  <span m="350676">read</span> <span m="351480">before</span> <span m="351820">today.</span>
  <span m="352580">So</span> <span m="352740">we</span> <span m="352880">did</span>
  <span m="353080">local</span> <span m="353270">order of</span> <span m="353370">accuracy.</span>
  <span m="354850">That</span> <span m="355000">is</span> <span m="355140">basically</span>
  <span m="355610">by</span> <span m="356000">plugging</span> <span m="359000">Taylor</span>
  <span m="359320">series</span> <span m="359920">into</span> <span m="360420">the</span>
  <span m="360990">numerical</span> <span m="361410">scheme</span> <span m="362140">and</span>
  <span m="362400">figuring</span> <span m="362806">out</span> <span m="363620">how,</span>
  <span m="364680">which</span> <span m="364870">is</span> <span m="365030">the</span>
  <span m="365130">truncating</span> <span m="365600">error.</span> <span m="365850">Is</span>
  <span m="366080">it the</span> <span m="366180">left</span> <span m="366390">hand</span>
  <span m="366520">side</span> <span m="366850">[INAUDIBLE]</span> <span m="367180">right
  hand</span> <span m="367560">side</span> <span m="368830">of</span> <span m="369750">the</span>
  <span m="370290">numerical</span> <span m="370630">scheme?</span> <span m="371520">When</span>
  <span m="371710">you</span> <span m="371830">plug in</span> <span m="372420">both</span>
  <span m="373050">the</span> <span m="373210">differential</span> <span m="373690">equation</span>
  <span m="374190">and</span> <span m="374610">the</span> <span m="374760">data</span>
  <span m="375110">series,</span> <span m="376190">does</span> <span m="376440">it</span>
  <span m="376630">go--</span> <span m="377250">what</span> <span m="377780">order</span>
  <span m="378280">of</span> <span m="378510">accuracy</span> <span m="379720">does</span>
  <span m="379990">it</span> <span m="380830">go?</span></p><p><span m="381210">So</span>
  <span m="381520">as</span> <span m="381830">delta</span> <span m="382120">t</span>
  <span m="382250">goes</span> <span m="382470">to</span> <span m="382600">0,</span>
  <span m="383140">how</span> <span m="383580">fast</span> <span m="384844">does</span>
  <span m="386200">my</span> <span m="387230">inconsistency</span> <span m="388140">between</span>
  <span m="388570">the</span> <span m="388660">differential</span> <span m="389010">equation</span>
  <span m="389600">and</span> <span m="389970">my</span> <span m="390340">numerical</span>
  <span m="390790">scheme</span> <span m="391690">go</span> <span m="391930">to</span>
  <span m="392060">0?</span> <span m="393170">OK.</span> <span m="394280">And</span>
  <span m="394560">the</span> <span m="394640">local</span> <span m="394840">order</span>
  <span m="395100">of</span> <span m="395230">accuracy</span> <span m="395960">is</span>
  <span m="396510">closely</span> <span m="397260">related</span> <span m="397860">to</span>
  <span m="398040">consistency.</span> <span m="399380">Actually</span> <span m="399700">the</span>
  <span m="399800">definition</span> <span m="400250">of</span> <span m="400320">consistency</span>
  <span m="403370">is</span> <span m="404710">by</span> <span m="404870">looking</span>
  <span m="405160">at</span> <span m="405695">is</span> <span m="405960">the</span>
  <span m="406060">scheme</span> <span m="406540">at</span> <span m="406925">least
  a</span> <span m="407310">first order</span> <span m="407695">accurate</span> <span
  m="408080">or</span> <span m="408200">not.</span></p><p><span m="409660">OK.</span>
  <span m="410900">Global</span> <span m="411490">accuracy.</span> <span m="412130">You</span>
  <span m="412480">should</span> <span m="412790">have</span> <span m="413030">read</span>
  <span m="413350">about</span> <span m="413730">global</span> <span m="414280">accuracy.</span>
  <span m="415230">Could</span> <span m="415650">somebody</span> <span m="415980">answer</span>
  <span m="416350">me</span> <span m="416780">the</span> <span m="417060">question</span>
  <span m="417390">of</span> <span m="417570">what</span> <span m="417740">is</span>
  <span m="417880">the</span> <span m="417960">difference</span> <span m="418440">between</span>
  <span m="418740">global</span> <span m="419340">accuracy</span> <span m="420020">and</span>
  <span m="420370">local</span> <span m="420865">accuracy?</span> <span m="421855">Or
  are they</span> <span m="422350">the same?</span> <span m="422670">Yes?</span></p><p><span
  m="423668">AUDIENCE: [INAUDIBLE]</span></p><p><span m="438660">QIQI WANG: So</span>
  <span m="438930">the</span> <span m="439070">global</span> <span m="439710">accuracy</span>
  <span m="440150">is</span> <span m="440590">the</span> <span m="440680">long</span>
  <span m="441010">term</span> <span m="441220">accuracy</span> <span m="441690">while</span>
  <span m="441990">the</span> <span m="442090">local</span> <span m="442530">accuracy</span>
  <span m="442975">is</span> <span m="446090">not</span> <span m="446340">the long
  term?</span></p><p><span m="450714">AUDIENCE: Local</span> <span m="451200">accuracy.</span></p><p><span
  m="452660">QIQI WANG: The</span> <span m="452800">local</span> <span m="453190">order
  of</span> <span m="453360">accuracy</span> <span m="453890">you</span> <span m="454050">can</span>
  <span m="454300">figure</span> <span m="454530">out</span> <span m="454700">by looking</span>
  <span m="454995">at</span> <span m="455290">only</span> <span m="455950">one</span>
  <span m="456416">time</span> <span m="456882">step,</span> <span m="457814">right?</span>
  <span m="458750">The</span> <span m="458950">global</span> <span m="459470">order</span>
  <span m="459700">of</span> <span m="459860">accuracy,</span> <span m="461210">you</span>
  <span m="461350">have</span> <span m="461520">to</span> <span m="461610">look</span>
  <span m="461920">at</span> <span m="462720">really</span> <span m="463100">by</span>
  <span m="463420">taking</span> <span m="463830">the</span> <span m="463910">number</span>
  <span m="464220">of</span> <span m="464340">time steps</span> <span m="464660">to</span>
  <span m="464740">infinity.</span> <span m="467110">And</span> <span m="467290">as</span>
  <span m="467570">Professor</span> <span m="467950">Willcox</span> <span m="468460">said,</span>
  <span m="469240">if</span> <span m="469480">you</span> <span m="469590">look</span>
  <span m="470190">at</span> <span m="470290">the</span> <span m="470410">solution</span>
  <span m="471010">U</span> <span m="472310">at</span> <span m="472740">a</span> <span
  m="472820">particular</span> <span m="473340">time--</span> <span m="473560">let''s</span>
  <span m="473790">say</span> <span m="474340">U</span> <span m="474700">at</span>
  <span m="475070">t</span> <span m="475420">equal</span> <span m="475480">to</span>
  <span m="475840">1--</span> <span m="476620">and</span> <span m="476880">compare</span>
  <span m="477470">the</span> <span m="477610">numerical</span> <span m="478160">solution--</span>
  <span m="478580">let</span> <span m="478730">me</span> <span m="478850">say</span>
  <span m="479110">V</span> <span m="479850">at</span> <span m="480120">t</span> <span
  m="480470">equal</span> <span m="480570">to 1--</span> <span m="481650">right?</span>
  <span m="482260">If</span> <span m="482460">you</span> <span m="482550">look</span>
  <span m="482860">at</span> <span m="482940">the</span> <span m="483030">difference</span>
  <span m="483690">between</span> <span m="484070">them,</span> <span m="484670">let''s</span>
  <span m="484950">just</span> <span m="485270">take</span> <span m="485550">the</span>
  <span m="485640">absolute</span> <span m="486130">value</span> <span m="486480">of</span>
  <span m="486610">the</span> <span m="486720">difference.</span> <span m="489330">That</span>
  <span m="489790">difference</span> <span m="491650">is</span> <span m="491950">really</span>
  <span m="492890">looking</span> <span m="493360">at</span> <span m="494910">how</span>
  <span m="495170">much</span> <span m="495610">error</span> <span m="496110">has</span>
  <span m="496370">the</span> <span m="496500">solution</span> <span m="496904">accumulated</span>
  <span m="498970">over</span> <span m="499190">one</span> <span m="499430">time step</span>
  <span m="500840">all</span> <span m="501050">the</span> <span m="501130">way</span>
  <span m="501400">from</span> <span m="501770">t equals</span> <span m="502075">0</span>
  <span m="502960">to</span> <span m="503150">t equals</span> <span m="503470">1?</span>
  <span m="504045">Right?</span></p><p><span m="506780">And</span> <span m="507940">if</span>
  <span m="508150">I</span> <span m="508260">look</span> <span m="508520">at</span>
  <span m="508660">that</span> <span m="508940">area</span> <span m="509800">as</span>
  <span m="510110">I</span> <span m="510200">take</span> <span m="510630">delta</span>
  <span m="511080">t</span> <span m="511660">to</span> <span m="511830">infinity,</span>
  <span m="513460">I''m</span> <span m="513640">actually</span> <span m="513960">accumulating</span>
  <span m="514530">more</span> <span m="514789">time steps,</span> <span m="515880">right?</span>
  <span m="517470">So</span> <span m="517669">if</span> <span m="517850">delta</span>
  <span m="518090">t</span> <span m="518280">is</span> <span m="518480">to 1</span>
  <span m="518960">I''m</span> <span m="519090">accumulating</span> <span m="519610">10</span>
  <span m="519799">time</span> <span m="520049">steps.</span> <span m="520850">If</span>
  <span m="521070">delta</span> <span m="521140">t</span> <span m="521320">is</span>
  <span m="521640">[INAUDIBLE],</span> <span m="522350">then</span> <span m="522530">I''m</span>
  <span m="522659">looking</span> <span m="522950">at</span> <span m="523350">the</span>
  <span m="523559">total</span> <span m="524000">area</span> <span m="524420">that
  has</span> <span m="524710">been</span> <span m="524970">accumulated</span> <span
  m="525285">over</span> <span m="525600">100</span> <span m="525950">time steps.</span>
  <span m="527430">Now</span> <span m="528450">we</span> <span m="528680">can</span>
  <span m="529190">for</span> <span m="529390">sure</span> <span m="529710">see</span>
  <span m="529950">that</span> <span m="530770">this</span> <span m="531604">puts</span>
  <span m="533260">a</span> <span m="533370">more</span> <span m="533940">stringent</span>
  <span m="534520">requirement</span> <span m="535510">on</span> <span m="535770">how</span>
  <span m="535930">my</span> <span m="536080">scheme</span> <span m="536380">behaves.</span>
  <span m="537380">Because</span> <span m="537970">when</span> <span m="538210">I</span>
  <span m="538360">only</span> <span m="538610">look</span> <span m="538820">at</span>
  <span m="538900">local</span> <span m="539320">order</span> <span m="539440">of</span>
  <span m="539610">accuracy</span> <span m="540400">and</span> <span m="540550">just</span>
  <span m="540710">look</span> <span m="540870">at</span> <span m="540980">one</span>
  <span m="541200">time step,</span> <span m="541690">now</span> <span m="542090">I''m</span>
  <span m="542290">looking</span> <span m="542660">at</span> <span m="543210">not</span>
  <span m="543410">only</span> <span m="544070">how</span> <span m="544220">much</span>
  <span m="544460">area</span> <span m="544870">have</span> <span m="545916">I</span>
  <span m="546330">produced</span> <span m="546980">in</span> <span m="547100">one</span>
  <span m="547390">time step</span> <span m="548190">but</span> <span m="548330">also</span>
  <span m="549280">how</span> <span m="549500">much</span> <span m="550100">has</span>
  <span m="550400">the</span> <span m="550620">area</span> <span m="551990">grown?</span>
  <span m="552810">I</span> <span m="552880">mean,</span> <span m="553320">does</span>
  <span m="553460">the area</span> <span m="553780">made</span> <span m="554090">in</span>
  <span m="554420">one</span> <span m="554560">time step</span> <span m="555210">actually</span>
  <span m="555700">only</span> <span m="555990">matter</span> <span m="556470">locally?</span>
  <span m="557000">Or</span> <span m="557460">is</span> <span m="557720">this area</span>
  <span m="558050">actually</span> <span m="558640">amplified</span> <span m="559930">by</span>
  <span m="560310">the</span> <span m="560430">later</span> <span m="560930">time
  steps?</span></p><p><span m="562430">So</span> <span m="562540">it</span> <span
  m="562720">puts</span> <span m="564630">additional</span> <span m="565260">requirements</span>
  <span m="566090">on</span> <span m="566260">a</span> <span m="566340">scheme.</span>
  <span m="566830">A</span> <span m="567310">scheme</span> <span m="567550">is</span>
  <span m="570170">globally</span> <span m="570680">accurate</span> <span m="572370">only</span>
  <span m="572830">if</span> <span m="573060">it</span> <span m="573170">is</span>
  <span m="573430">both</span> <span m="573860">locally</span> <span m="574420">accurate</span>
  <span m="575700">and</span> <span m="576620">what?</span> <span m="583620">I</span>
  <span m="583840">hear</span> <span m="584120">two</span> <span m="584300">answers.</span>
  <span m="584540">One</span> <span m="584830">says</span> <span m="585220">stable.</span>
  <span m="586000">Another</span> <span m="586370">is</span> <span m="587730">consistent.</span>
  <span m="590020">Who</span> <span m="590200">votes</span> <span m="590440">for</span>
  <span m="590640">stable?</span> <span m="591106">And who</span> <span m="591572">votes
  for</span> <span m="592038">consistent?</span> <span m="592970">Stable?</span> <span
  m="595620">One,</span> <span m="596120">two,</span> <span m="596525">three,</span>
  <span m="596930">four.</span> <span m="597740">Consistent?</span> <span m="600030">One,</span>
  <span m="600470">two,</span> <span m="600850">three,</span> <span m="601210">four,</span>
  <span m="601686">five.</span> <span m="602640">OK.</span></p><p><span m="604280">I</span>
  <span m="604430">said</span> <span m="604670">a</span> <span m="604935">scheme</span>
  <span m="605200">is</span> <span m="605270">globally</span> <span m="605400">accurate</span>
  <span m="606830">only</span> <span m="607220">if it''s</span> <span m="607440">locally</span>
  <span m="607920">accurate</span> <span m="608710">and</span> <span m="609110">what?</span>
  <span m="609600">So</span> <span m="609750">if</span> <span m="609920">we</span>
  <span m="610030">the answer</span> <span m="610220">is</span> <span m="610400">consistent,</span>
  <span m="612200">then</span> <span m="612500">it</span> <span m="612620">doesn''t</span>
  <span m="613030">add</span> <span m="613270">anything,</span> <span m="613720">right?</span>
  <span m="614000">Being</span> <span m="614260">consistent</span> <span m="615910">means</span>
  <span m="616580">being</span> <span m="616620">locally</span> <span m="616950">accurate.</span>
  <span m="618430">OK?</span> <span m="621210">A scheme</span> <span m="621650">is</span>
  <span m="621780">locally</span> <span m="622200">accurate</span> <span m="622770">and</span>
  <span m="623370">consistent</span> <span m="623460">means</span> <span m="623780">it''s</span>
  <span m="623890">just</span> <span m="624110">locally</span> <span m="624370">accurate.</span>
  <span m="624885">It doesn''t</span> <span m="625170">say</span> <span m="625590">anything</span>
  <span m="625880">additional</span> <span m="626470">to</span> <span m="626670">being</span>
  <span m="626890">locally</span> <span m="627270">accurate.</span> <span m="628480">That''s</span>
  <span m="628790">the</span> <span m="628930">definition</span> <span m="629460">of</span>
  <span m="629570">being</span> <span m="629760">consistent.</span> <span m="630370">It</span>
  <span m="630540">is</span> <span m="630730">just</span> <span m="630960">to</span>
  <span m="631040">be</span> <span m="631250">locally</span> <span m="631660">accurate.</span></p><p><span
  m="633935">A scheme is</span> <span m="634390">globally</span> <span m="635010">accurate</span>
  <span m="635610">only</span> <span m="635960">if</span> <span m="636270">it''s</span>
  <span m="636610">locally</span> <span m="637140">accurate</span> <span m="637930">and</span>
  <span m="638340">is</span> <span m="640125">stable.</span> <span m="640980">Actually</span>
  <span m="641430">zero</span> <span m="641940">stable.</span> <span m="642640">And</span>
  <span m="643030">what</span> <span m="643280">does</span> <span m="643560">zero</span>
  <span m="643820">stable</span> <span m="643920">mean?</span> <span m="644330">You</span>
  <span m="644450">should</span> <span m="644630">have</span> <span m="644780">just</span>
  <span m="645180">read</span> <span m="645490">about</span> <span m="645780">it.</span>
  <span m="649910">I''m</span> <span m="650060">just</span> <span m="650250">going</span>
  <span m="650430">to</span> <span m="650970">say</span> <span m="651290">I</span>
  <span m="651360">mean</span> <span m="651540">you</span> <span m="651770">have</span>
  <span m="651950">read</span> <span m="652180">about</span> <span m="652400">it.</span>
  <span m="652520">I''m</span> <span m="652710">just</span> <span m="652910">going</span>
  <span m="653050">to</span> <span m="653150">say</span> <span m="653620">another</span>
  <span m="654130">way</span> <span m="654370">of</span> <span m="654570">understanding</span>
  <span m="655320">zero</span> <span m="655560">accuracy</span> <span m="656970">is</span>
  <span m="657180">that</span> <span m="657730">when</span> <span m="657960">you</span>
  <span m="658130">solve</span> <span m="658570">the</span> <span m="658670">differential</span>
  <span m="659210">equation</span> <span m="659890">du/dt</span> <span m="661870">equal</span>
  <span m="662390">to</span> <span m="662720">zero,</span> <span m="663480">the</span>
  <span m="663610">scheme</span> <span m="663920">is</span> <span m="664070">going</span>
  <span m="664210">to</span> <span m="664280">be</span> <span m="664390">stable.</span>
  <span m="665660">OK?</span> <span m="666360">That''s</span> <span m="666780">what</span>
  <span m="667040">it</span> <span m="667150">means</span> <span m="667490">by</span>
  <span m="667887">a</span> <span m="668284">scheme</span> <span m="668681">being</span>
  <span m="669080">zero</span> <span m="669520">stable.</span></p><p><span m="673860">In</span>
  <span m="674050">this</span> <span m="674250">sense,</span> <span m="674540">it''s</span>
  <span m="674700">a</span> <span m="674760">very</span> <span m="675140">weak</span>
  <span m="675465">requirement.</span> <span m="677020">Right?</span> <span m="678710">You</span>
  <span m="678830">only</span> <span m="679150">need</span> <span m="679320">to be</span>
  <span m="679530">stable</span> <span m="680310">when</span> <span m="680610">solving</span>
  <span m="680840">this</span> <span m="681970">trivial</span> <span m="683010">differential</span>
  <span m="683370">equation.</span> <span m="684970">Right?</span> <span m="685150">What
  is</span> <span m="685630">the solution</span> <span m="685990">for a</span> <span
  m="686060">differential</span> <span m="686560">equation?</span></p><p><span m="689060">AUDIENCE:
  Confidence.</span></p><p><span m="690060">QIQI WANG: Confidence,</span> <span m="691060">right.</span>
  <span m="691910">I</span> <span m="691970">mean,</span> <span m="692120">if</span>
  <span m="692210">you''re so</span> <span m="692440">very</span> <span m="692630">[INAUDIBLE],</span>
  <span m="694240">even</span> <span m="694600">your</span> <span m="694790">scheme</span>
  <span m="695370">can''t</span> <span m="695710">even</span> <span m="695990">solve</span>
  <span m="696310">that</span> <span m="696540">differential</span> <span m="696880">equation,</span>
  <span m="697720">what</span> <span m="698040">good is</span> <span m="698440">the</span>
  <span m="698680">scheme?</span> <span m="700880">Right?</span> <span m="701600">OK.</span></p><p><span
  m="705440">So</span> <span m="705820">this</span> <span m="706030">is,</span> <span
  m="706613">yes.</span> <span m="706966">It is</span> <span m="707320">an additional</span>
  <span m="707590">requirement</span> <span m="709664">on top</span> <span m="710152">of
  local</span> <span m="710640">accuracy.</span> <span m="713080">But it</span> <span
  m="713210">is</span> <span m="713360">a</span> <span m="713510">pretty</span> <span
  m="713860">weak</span> <span m="714210">requirement.</span> <span m="715090">All</span>
  <span m="715240">right?</span> <span m="716370">That</span> <span m="716550">is</span>
  <span m="716700">why</span> <span m="717450">I</span> <span m="717580">think</span>
  <span m="717850">it</span> <span m="717970">is</span> <span m="718260">such</span>
  <span m="718665">a</span> <span m="719070">great</span> <span m="719360">result</span>
  <span m="720000">that</span> <span m="720330">we</span> <span m="720450">can</span>
  <span m="720690">say</span> <span m="721415">being</span> <span m="721790">locally</span>
  <span m="722570">accurate</span> <span m="723380">[INAUDIBLE].</span> <span m="726444">And</span>
  <span m="726880">being zero</span> <span m="727020">stable,</span> <span m="727180">which</span>
  <span m="727638">is such a</span> <span m="728096">weak</span> <span m="728554">requirement,</span>
  <span m="729470">you</span> <span m="729660">can</span> <span m="730110">immediately</span>
  <span m="731200">have</span> <span m="731390">the</span> <span m="731470">conclusion</span>
  <span m="732160">of</span> <span m="732480">global</span> <span m="732880">accuracy.</span>
  <span m="734930">Right?</span> <span m="736160">So</span> <span m="736450">what</span>
  <span m="737260">theorem</span> <span m="737440">or</span> <span m="737840">result</span>
  <span m="738620">gives</span> <span m="739240">you</span> <span m="739490">that</span>
  <span m="739810">conclusion?</span></p><p><span m="742750">AUDIENCE: [INAUDIBLE].</span></p><p><span
  m="752060">QIQI WANG: What is it</span> <span m="752550">called?</span> <span m="753530">Dahlquist</span>
  <span m="754020">Equivalence</span> <span m="754510">Theorem.</span> <span m="755500">Yes.</span>
  <span m="756620">Right.</span> <span m="757370">So</span> <span m="757590">that</span>
  <span m="757870">theorem</span> <span m="758170">basically</span> <span m="758620">says
  that</span> <span m="759100">these</span> <span m="759420">are locally</span> <span
  m="759910">accurate,</span> <span m="761470">which</span> <span m="761800">only</span>
  <span m="762130">looks</span> <span m="762520">at</span> <span m="763370">one</span>
  <span m="763760">time step.</span> <span m="765140">And</span> <span m="765600">if</span>
  <span m="766100">you</span> <span m="766290">have</span> <span m="766440">are</span>
  <span m="766920">zero</span> <span m="767400">stable--</span> <span m="767880">which
  means</span> <span m="769050">you</span> <span m="769305">can</span> <span m="769560">solve</span>
  <span m="770110">this</span> <span m="770330">trivial</span> <span m="770690">differential</span>
  <span m="771040">equation--</span> <span m="772100">then</span> <span m="773020">your</span>
  <span m="773210">scheme</span> <span m="773510">is</span> <span m="773810">globally</span>
  <span m="774570">accurate</span> <span m="774840">which</span> <span m="775040">means</span>
  <span m="776160">you can</span> <span m="776580">solve</span> <span m="777000">the
  differential</span> <span m="777420">equation</span> <span m="777840">for</span>
  <span m="778100">a</span> <span m="778841">fixed</span> <span m="779322">amount
  of</span> <span m="779803">time</span> <span m="781246">as</span> <span m="781727">it</span>
  <span m="782208">takes</span> <span m="782690">delta</span> <span m="782810">t to</span>
  <span m="783220">go to</span> <span m="783410">zero, which</span> <span m="783570">also
  means</span> <span m="783990">the</span> <span m="784440">amount of</span> <span
  m="784890">time steps</span> <span m="785340">goes to</span> <span m="785790">infinity.</span>
  <span m="788250">Your</span> <span m="788570">global</span> <span m="788980">solution</span>
  <span m="789520">becomes</span> <span m="789960">more</span> <span m="790270">and</span>
  <span m="790400">more</span> <span m="790600">accurate.</span> <span m="793180">OK.</span></p><p><span
  m="794610">And</span> <span m="794930">in</span> <span m="795090">addition</span>
  <span m="795580">to</span> <span m="795880">this,</span> <span m="796300">zero</span>
  <span m="796590">stability</span> <span m="797150">gives</span> <span m="797420">you</span>
  <span m="797520">the</span> <span m="797610">result</span> <span m="797980">that</span>
  <span m="798720">the</span> <span m="798850">local</span> <span m="799330">order</span>
  <span m="799590">of</span> <span m="799740">accuracy</span> <span m="800440">is</span>
  <span m="801750">the</span> <span m="801860">same</span> <span m="802340">as</span>
  <span m="802570">the</span> <span m="802820">global</span> <span m="803200">order</span>
  <span m="803550">of accuracy,</span> <span m="804690">right?</span> <span m="805760">So</span>
  <span m="805910">if</span> <span m="806090">you</span> <span m="806200">can</span>
  <span m="806420">do</span> <span m="806560">Taylor</span> <span m="806880">series</span>
  <span m="807200">analysis,</span> <span m="807800">you</span> <span m="807920">can</span>
  <span m="808180">not only</span> <span m="808550">know</span> <span m="808800">the</span>
  <span m="808900">local</span> <span m="809220">order of</span> <span m="809470">accuracy.</span>
  <span m="809960">You also</span> <span m="810260">know</span> <span m="811250">the</span>
  <span m="811420">global</span> <span m="811680">order</span> <span m="811940">of</span>
  <span m="812100">accuracy.</span> <span m="815450">OK.</span></p><p><span m="816120">Eigenvalue</span>
  <span m="816720">stability</span> <span m="818368">is</span> <span m="818780">a</span>
  <span m="819120">step</span> <span m="819580">beyond</span> <span m="820340">zero</span>
  <span m="820600">stability.</span> <span m="822930">This</span> <span m="823650">tells</span>
  <span m="824020">you</span> <span m="824160">that</span> <span m="825850">your</span>
  <span m="826020">scheme</span> <span m="826570">has</span> <span m="826760">to</span>
  <span m="826880">be</span> <span m="827290">not</span> <span m="827450">only</span>
  <span m="827760">solving</span> <span m="828190">this</span> <span m="828250">equation</span>
  <span m="828970">but</span> <span m="829140">also</span> <span m="830030">du/dt</span>
  <span m="831292">equal</span> <span m="832090">to</span> <span m="832260">lambda</span>
  <span m="832670">U.</span> <span m="833620">Right?</span> <span m="834760">And</span>
  <span m="834860">then</span> <span m="835110">this</span> <span m="835340">is</span>
  <span m="835500">also</span> <span m="835780">a</span> <span m="835950">pretty</span>
  <span m="836270">easy</span> <span m="836520">differential</span> <span m="836920">equation.</span>
  <span m="837340">You</span> <span m="837470">have</span> <span m="837760">analytical</span>
  <span m="838390">solutions</span> <span m="838680">to</span> <span m="838970">that.</span>
  <span m="841890">The</span> <span m="842610">zero</span> <span m="842900">stability,
  you</span> <span m="843190">can think</span> <span m="843450">of</span> <span m="844430">as</span>
  <span m="845245">a</span> <span m="845530">special</span> <span m="846110">case.</span>
  <span m="846598">It''s a</span> <span m="847086">much</span> <span m="847574">weaker</span>
  <span m="848062">requirement</span> <span m="848550">than Eigenvalue</span> <span
  m="849038">stability.</span> <span m="850510">Eigenvalue</span> <span m="850890">stability</span>
  <span m="851550">means</span> <span m="851920">you</span> <span m="852936">need
  to</span> <span m="853290">solve</span> <span m="853630">now</span> <span m="853850">nontrivial</span>
  <span m="854140">differential</span> <span m="854884">equations.</span></p><p><span
  m="856700">OK.</span> <span m="856990">So</span> <span m="857390">today</span> <span
  m="857670">what</span> <span m="857940">we''re</span> <span m="858140">going</span>
  <span m="858260">to</span> <span m="858440">do</span> <span m="858680">is</span>
  <span m="858970">we</span> <span m="859100">are going</span> <span m="859230">to</span>
  <span m="859480">exercise</span> <span m="860510">this</span> <span m="861360">local</span>
  <span m="861780">order</span> <span m="861960">of</span> <span m="862110">accuracy,</span>
  <span m="862640">global</span> <span m="863150">order</span> <span m="863410">of</span>
  <span m="863530">accuracy,</span> <span m="864030">and</span> <span m="864210">the</span>
  <span m="864390">zero</span> <span m="864600">stability,</span> <span m="865300">and</span>
  <span m="865820">Eigenvalue</span> <span m="866420">stability</span> <span m="866860">by</span>
  <span m="867090">looking</span> <span m="867510">at</span> <span m="867820">a</span>
  <span m="869360">pretty</span> <span m="869590">simple</span> <span m="869970">problem.</span>
  <span m="871890">It''s</span> <span m="872130">a</span> <span m="872400">ballistic</span>
  <span m="872980">trajectory</span> <span m="873560">prediction</span> <span m="874030">problem.</span>
  <span m="874450">I</span> <span m="874870">hope</span> <span m="875130">most</span>
  <span m="875590">of</span> <span m="876050">you</span> <span m="876330">brought</span>
  <span m="876570">your</span> <span m="876650">computer.</span> <span m="879225">Does</span>
  <span m="879650">everybody</span> <span m="879960">have</span> <span m="880270">your</span>
  <span m="880550">computer</span> <span m="881260">with</span> <span m="881450">you?</span>
  <span m="884340">And</span> <span m="884830">do</span> <span m="885170">you</span>
  <span m="885370">have</span> <span m="885590">MATLAB</span> <span m="886160">installed?</span>
  <span m="888830">Yes?</span> <span m="890040">OK.</span></p><p><span m="892430">So</span>
  <span m="892580">what</span> <span m="892760">I</span> <span m="892840">want</span>
  <span m="893010">you to</span> <span m="893240">do</span> <span m="893430">is,</span>
  <span m="893770">I</span> <span m="894050">want</span> <span m="894260">you</span>
  <span m="894360">to</span> <span m="894490">do</span> <span m="894690">mathematical</span>
  <span m="895300">modeling</span> <span m="895950">which</span> <span m="896200">is</span>
  <span m="896520">deriving</span> <span m="897330">some</span> <span m="897500">ODEs.</span>
  <span m="899810">I''m</span> <span m="899950">not</span> <span m="900110">going</span>
  <span m="900230">to</span> <span m="900370">give</span> <span m="900570">you</span>
  <span m="900730">any</span> <span m="900950">ODEs.</span> <span m="901390">You</span>
  <span m="901460">need</span> <span m="901670">to</span> <span m="901780">derive</span>
  <span m="902140">it.</span> <span m="902950">And</span> <span m="903530">you''re
  going</span> <span m="903860">to</span> <span m="904190">solve</span> <span m="904570">the</span>
  <span m="904950">ODE</span> <span m="905160">using</span> <span m="905700">forward</span>
  <span m="905820">Euler.</span> <span m="907180">Solve</span> <span m="907580">the</span>
  <span m="907700">ODE</span> <span m="908120">using</span> <span m="908380">midpoint.</span>
  <span m="909720">And</span> <span m="910720">solve</span> <span m="911030">the</span>
  <span m="911150">ODE</span> <span m="911650">with</span> <span m="912740">one</span>
  <span m="913110">of</span> <span m="913230">the</span> <span m="913390">homework,</span>
  <span m="913940">the</span> <span m="914170">first</span> <span m="914760">homework</span>
  <span m="915160">question</span> <span m="915615">you did,</span> <span m="917890">which</span>
  <span m="918120">is</span> <span m="918470">the</span> <span m="918640">most</span>
  <span m="919110">accurate</span> <span m="920256">two-step</span> <span m="921870">explicit</span>
  <span m="922550">scheme.</span> <span m="923530">Anybody</span> <span m="924000">who</span>
  <span m="924270">can</span> <span m="924540">tell</span> <span m="924760">me</span>
  <span m="924860">what</span> <span m="925060">that</span> <span m="925150">scheme</span>
  <span m="925470">is?</span></p><p><span m="929080">V</span> <span m="929390">of</span>
  <span m="929700">m</span> <span m="929910">plus</span> <span m="930180">1</span>
  <span m="930470">equal</span> <span m="930900">to</span> <span m="934370">minus</span>
  <span m="934840">4</span> <span m="935330">V</span> <span m="935710">m</span> <span
  m="937440">plus</span> <span m="937740">5</span> <span m="938140">V</span> <span
  m="938390">m minus</span> <span m="938690">1.</span></p><p><span m="939960">AUDIENCE:
  [INAUDIBLE].</span></p><p><span m="944150">QIQI WANG: Plus</span> <span m="944470">4</span>
  <span m="944750">delta</span> <span m="944950">t</span> <span m="945090">F</span>
  <span m="945320">of</span> <span m="945820">V</span> <span m="946160">m</span> <span
  m="948120">plus</span> <span m="949100">2</span> <span m="949380">delta</span> <span
  m="949990">t</span> <span m="950450">F of</span> <span m="950750">Vm</span> <span
  m="951060">minus</span> <span m="951400">1.</span> <span m="952310">So</span> <span
  m="952920">I</span> <span m="953010">mean,</span> <span m="953330">yeah.</span>
  <span m="953690">It</span> <span m="953790">is</span> <span m="953990">the</span>
  <span m="954070">most</span> <span m="954350">accurate</span> <span m="954760">two-step</span>
  <span m="955180">scheme.</span> <span m="957270">But</span> <span m="957530">why</span>
  <span m="957770">doesn''t</span> <span m="957950">it</span> <span m="958070">have</span>
  <span m="958270">a</span> <span m="958340">name?</span> <span m="959620">Something</span>
  <span m="959970">like</span> <span m="960120">this</span> <span m="960400">should</span>
  <span m="960550">have</span> <span m="960710">a</span> <span m="960800">name,</span>
  <span m="961270">right?</span> <span m="963150">Let''s</span> <span m="963460">try</span>
  <span m="963915">to</span> <span m="964370">see</span> <span m="964530">why</span>
  <span m="964750">it</span> <span m="964820">doesn''t</span> <span m="965060">have</span>
  <span m="965200">a</span> <span m="965280">name</span> <span m="965640">by</span>
  <span m="965810">applying</span> <span m="966380">this</span> <span m="967170">onto</span>
  <span m="967830">the</span> <span m="968200">ballistic</span> <span m="968740">trajectory</span>
  <span m="969310">prediction</span> <span m="969810">problem.</span></p><p><span
  m="972020">All</span> <span m="972210">right.</span> <span m="972950">And</span>
  <span m="973410">let''s</span> <span m="973810">look</span> <span m="974210">at</span>
  <span m="974460">accuracy,</span> <span m="975290">stability,</span> <span m="975990">convergence</span>
  <span m="976850">and</span> <span m="977090">how</span> <span m="977740">they</span>
  <span m="977930">relate</span> <span m="978360">to</span> <span m="978450">each</span>
  <span m="978660">other</span> <span m="979050">through</span> <span m="979280">the</span>
  <span m="979500">Dahlquist</span> <span m="979880">Equivalence</span> <span m="980260">Theorem</span>
  <span m="982160">using</span> <span m="982440">this</span> <span m="982610">example.</span>
  <span m="985050">OK.</span> <span m="985380">Ballistic</span> <span m="986010">trajectory</span>
  <span m="986490">predictions.</span> <span m="987740">Here is</span> <span m="987920">some</span>
  <span m="988220">history.</span> <span m="988910">It is</span> <span m="989050">really</span>
  <span m="990270">the</span> <span m="990370">motivating</span> <span m="991810">factor</span>
  <span m="992140">of</span> <span m="992310">developing</span> <span m="994010">the</span>
  <span m="994120">first real</span> <span m="994380">computer,</span> <span m="995210">the</span>
  <span m="995350">first</span> <span m="995900">real</span> <span m="996020">electrical</span>
  <span m="996580">computer</span> <span m="996830">is</span> <span m="996910">what</span>
  <span m="997130">they</span> <span m="997480">call it.</span> <span m="997830">They</span>
  <span m="998050">are</span> <span m="998240">really</span> <span m="998860">designed</span>
  <span m="999290">to</span> <span m="1000510">help</span> <span m="1000740">engineers</span>
  <span m="1001290">solve</span> <span m="1001870">this</span> <span m="1002150">kind</span>
  <span m="1002330">of</span> <span m="1002440">problem.</span> <span m="1003740">And</span>
  <span m="1003980">here</span> <span m="1004450">we</span> <span m="1004630">are</span>
  <span m="1004700">going</span> <span m="1004820">to</span> <span m="1004900">be</span>
  <span m="1005810">programming</span> <span m="1006990">a</span> <span m="1007140">MATLAB</span>
  <span m="1007670">to</span> <span m="1007790">solve</span> <span m="1008320">such</span>
  <span m="1008580">a</span> <span m="1008620">prediction</span> <span m="1009480">problem.</span></p><p><span
  m="1010920">So</span> <span m="1011130">we</span> <span m="1011860">are</span> <span
  m="1011940">thinking</span> <span m="1012250">if</span> <span m="1012420">the</span>
  <span m="1012630">motor</span> <span m="1012780">fires</span> <span m="1014310">a
  small</span> <span m="1015240">3</span> <span m="1015415">kilogram</span> <span
  m="1017148">and</span> <span m="1018510">10 centimeters</span> <span m="1018964">in</span>
  <span m="1019420">diameter</span> <span m="1020820">spherical</span> <span m="1021210">cannonball,</span>
  <span m="1022760">so</span> <span m="1023110">it is</span> <span m="1023590">fired</span>
  <span m="1024000">over</span> <span m="1024310">here.</span> <span m="1026030">At
  sea</span> <span m="1026280">level</span> <span m="1026554">in</span> <span m="1026829">standard</span>
  <span m="1027124">atmosphere,</span> <span m="1027690">you</span> <span m="1027890">can</span>
  <span m="1028641">look</span> <span m="1029132">for</span> <span m="1029623">the</span>
  <span m="1030114">air</span> <span m="1030609">density</span> <span m="1030960">or</span>
  <span m="1031200">whatever</span> <span m="1033280">from</span> <span m="1033718">the
  internet.</span> <span m="1036119">And</span> <span m="1036329">so</span> <span
  m="1036430">I</span> <span m="1036609">want to</span> <span m="1036720">derive</span>
  <span m="1037130">the</span> <span m="1037450">differential</span> <span m="1037970">equation.</span>
  <span m="1038359">That</span> <span m="1038599">is</span> <span m="1038910">going</span>
  <span m="1039099">to</span> <span m="1039329">allow</span> <span m="1039640">me</span>
  <span m="1039900">to</span> <span m="1040050">predict</span> <span m="1041651">the</span>
  <span m="1043089">impact</span> <span m="1043780">if</span> <span m="1043869">I</span>
  <span m="1043980">give</span> <span m="1044230">you</span> <span m="1044369">the</span>
  <span m="1044500">initial</span> <span m="1045260">velocity,</span> <span m="1046480">the
  x</span> <span m="1046755">velocity</span> <span m="1047030">and</span> <span m="1047200">y</span>
  <span m="1047369">velocity</span> <span m="1049342">of</span> <span m="1049806">this</span>
  <span m="1050270">thing.</span></p><p><span m="1053060">Here</span> <span m="1053280">is</span>
  <span m="1053360">some</span> <span m="1054080">additional</span> <span m="1054710">data.</span>
  <span m="1056570">Aerodynamic</span> <span m="1056960">drag</span> <span m="1057640">has</span>
  <span m="1057810">to be</span> <span m="1058180">considered.</span> <span m="1059290">The</span>
  <span m="1059770">cannon</span> <span m="1059970">ball,</span> <span m="1062260">the</span>
  <span m="1062410">force on</span> <span m="1062775">the</span> <span m="1063140">cannonball</span>
  <span m="1063440">is</span> <span m="1064060">gravity</span> <span m="1065580">and</span>
  <span m="1065950">drag.</span> <span m="1066460">Right?</span> <span m="1066980">Those</span>
  <span m="1067130">are</span> <span m="1067260">the only</span> <span m="1067698">two
  forces.</span> <span m="1069890">And</span> <span m="1070400">let''s</span> <span
  m="1070725">assume</span> <span m="1072244">it''s</span> <span m="1072721">fired</span>
  <span m="1073200">at</span> <span m="1073520">a</span> <span m="1073930">subsonic</span>
  <span m="1074210">speed.</span> <span m="1074740">Subsonic</span> <span m="1075010">Cd,</span>
  <span m="1075740">that</span> <span m="1076160">coefficient.</span> <span m="1077000">Let''s</span>
  <span m="1077420">use</span> <span m="1078260">0.5.</span> <span m="1080100">And</span>
  <span m="1080690">yeah,</span> <span m="1081180">actually</span> <span m="1081760">we
  give</span> <span m="1081960">you</span> <span m="1082190">the air</span> <span
  m="1082688">density.</span> <span m="1083186">So you</span> <span m="1083684">don''t
  have</span> <span m="1084182">to find</span> <span m="1084680">it</span> <span m="1085178">out.</span>
  <span m="1088960">So what''s</span> <span m="1089090">the</span> <span m="1089400">differential</span>
  <span m="1089980">equation?</span> <span m="1090935">The</span> <span m="1091430">differential</span>
  <span m="1092020">equation</span> <span m="1092480">such that</span> <span m="1092780">you
  can</span> <span m="1093576">[INAUDIBLE]</span> <span m="1094072">in</span> <span
  m="1094568">MATLAB.</span></p><p><span m="1097050">For</span> <span m="1097250">deriving</span>
  <span m="1097700">the</span> <span m="1097780">equation,</span> <span m="1098220">you</span>
  <span m="1098360">can</span> <span m="1098630">work</span> <span m="1099000">in</span>
  <span m="1099426">groups</span> <span m="1099852">of</span> <span m="1100280">two</span>
  <span m="1100640">or three.</span> <span m="1101760">Writing</span> <span m="1102150">the</span>
  <span m="1102280">code</span> <span m="1102640">has</span> <span m="1102820">to</span>
  <span m="1102920">be</span> <span m="1103040">done</span> <span m="1103320">individually.</span>
  <span m="1104992">All</span> <span m="1105410">right?</span> <span m="1106470">So</span>
  <span m="1106640">if</span> <span m="1106810">you''re</span> <span m="1107080">sitting</span>
  <span m="1107360">alone,</span> <span m="1108566">please</span> <span m="1109029">tend
  to</span> <span m="1109492">gather.</span> <span m="1109955">Form groups.</span>
  <span m="1110881">And</span> <span m="1111344">continue</span> <span m="1111807">working
  out</span> <span m="1112270">the</span> <span m="1112733">differential</span> <span
  m="1113200">equations</span> <span m="1113440">together.</span> <span m="1116310">Any</span>
  <span m="1116700">questions</span> <span m="1117115">before</span> <span m="1117380">we</span>
  <span m="1117880">dive</span> <span m="1118170">into</span> <span m="1118450">the</span>
  <span m="1118720">lab?</span></p><p><span m="1121630">AUDIENCE: [INAUDIBLE].</span></p><p><span
  m="1124055">QIQI WANG: Uh huh.</span></p><p><span m="1125995">AUDIENCE: [INAUDIBLE]</span></p><p><span
  m="1126970">QIQI WANG: What</span> <span m="1127190">is</span> <span m="1127330">the</span>
  <span m="1127450">angle?</span> <span m="1129200">This</span> <span m="1129610">is</span>
  <span m="1129970">[INAUDIBLE].</span> <span m="1130880">And</span> <span m="1131210">I''m</span>
  <span m="1131662">going to</span> <span m="1132114">tell you</span> <span m="1133020">that.</span>
  <span m="1133280">Let''s</span> <span m="1133600">leave it</span> <span m="1133940">as</span>
  <span m="1134210">the parameter</span> <span m="1134695">[INAUDIBLE].</span> <span
  m="1136150">And</span> <span m="1136635">I''m going</span> <span m="1137120">to
  tell you</span> <span m="1137605">where</span> <span m="1138090">the</span> <span
  m="1138575">[INAUDIBLE]</span> <span m="1141485">what happens</span> <span m="1141970">[INAUDIBLE].</span>
  <span m="1143440">OK.</span> <span m="1143590">Lot</span> <span m="1143770">of</span>
  <span m="1143890">you</span> <span m="1144040">have</span> <span m="1144240">figured</span>
  <span m="1144610">out</span> <span m="1144830">the</span> <span m="1144950">ODE.</span>
  <span m="1146590">So</span> <span m="1146740">I''m</span> <span m="1146830">just</span>
  <span m="1147010">going</span> <span m="1147200">to</span> <span m="1147910">write</span>
  <span m="1148170">it</span> <span m="1148270">down</span> <span m="1148500">here</span>
  <span m="1148840">so</span> <span m="1148990">that</span> <span m="1149480">everybody</span>
  <span m="1150490">is</span> <span m="1150740">on</span> <span m="1150850">the</span>
  <span m="1150920">same</span> <span m="1151170">page</span> <span m="1151500">when</span>
  <span m="1151700">you</span> <span m="1152040">go into</span> <span m="1152466">implementation.</span>
  <span m="1154170">OK.</span></p><p><span m="1158700">What</span> <span m="1158920">happens</span>
  <span m="1159340">is</span> <span m="1159580">that</span> <span m="1160430">the</span>
  <span m="1160590">force--</span> <span m="1161110">if</span> <span m="1161320">you</span>
  <span m="1161390">look</span> <span m="1161650">at</span> <span m="1161790">the</span>
  <span m="1161970">cannon ball,</span> <span m="1162510">if</span> <span m="1162690">the</span>
  <span m="1162920">velocity</span> <span m="1163580">is</span> <span m="1164650">Ux</span>
  <span m="1165660">and</span> <span m="1166110">Uy,</span> <span m="1170730">it</span>
  <span m="1170950">has</span> <span m="1171130">a</span> <span m="1171230">force</span>
  <span m="1171700">of</span> <span m="1171890">gravity,</span> <span m="1172275">m</span>
  <span m="1172660">times</span> <span m="1172960">g.</span> <span m="1173820">It</span>
  <span m="1173990">has</span> <span m="1174330">a</span> <span m="1174500">force</span>
  <span m="1175300">of</span> <span m="1175700">drag,</span> <span m="1177160">right?</span>
  <span m="1178410">And</span> <span m="1178780">the</span> <span m="1178860">magnitude</span>
  <span m="1179700">of</span> <span m="1179860">the drag</span> <span m="1180420">is</span>
  <span m="1180690">equal</span> <span m="1181050">to</span> <span m="1181200">Cv</span>
  <span m="1182300">times</span> <span m="1182660">half</span> <span m="1183070">of</span>
  <span m="1183260">rho</span> <span m="1184330">U</span> <span m="1184600">squared.</span>
  <span m="1185290">U</span> <span m="1185530">squared</span> <span m="1185790">is</span>
  <span m="1186010">Ux</span> <span m="1186460">squared</span> <span m="1186830">plus</span>
  <span m="1187240">Uy</span> <span m="1187840">squared.</span> <span m="1191380">And</span>
  <span m="1191570">the</span> <span m="1191640">drag</span> <span m="1192130">also</span>
  <span m="1192400">has</span> <span m="1192630">an</span> <span m="1192850">angle.</span>
  <span m="1194200">The</span> <span m="1194360">angle</span> <span m="1194790">is</span>
  <span m="1195590">proportional</span> <span m="1196380">to</span> <span m="1197830">the</span>
  <span m="1198030">angle</span> <span m="1198480">of</span> <span m="1198780">Ux</span>
  <span m="1199200">and</span> <span m="1199330">Uy</span> <span m="1199750">but</span>
  <span m="1200130">in</span> <span m="1200280">the</span> <span m="1200390">opposite</span>
  <span m="1200830">direction.</span></p><p><span m="1202210">So</span> <span m="1202420">if</span>
  <span m="1202610">you</span> <span m="1202800">write</span> <span m="1203330">down</span>
  <span m="1203570">the</span> <span m="1203650">differential</span> <span m="1204220">equations,</span>
  <span m="1205300">it''s</span> <span m="1205610">dUx/dt.</span> <span m="1211150">The</span>
  <span m="1211430">force</span> <span m="1211760">on</span> <span m="1211870">the</span>
  <span m="1211950">x</span> <span m="1212280">component</span> <span m="1213310">only</span>
  <span m="1214110">has</span> <span m="1214470">a</span> <span m="1214560">component</span>
  <span m="1215070">of</span> <span m="1215210">drag</span> <span m="1215520">on</span>
  <span m="1215670">it.</span> <span m="1216060">Right?</span> <span m="1216990">So</span>
  <span m="1217210">it</span> <span m="1217330">is</span> <span m="1218720">minus</span>
  <span m="1219430">D</span> <span m="1221190">times</span> <span m="1222020">Ux</span>
  <span m="1222650">divided</span> <span m="1223290">by</span> <span m="1223726">square</span>
  <span m="1224162">root</span> <span m="1224600">of Ux</span> <span m="1225140">squared</span>
  <span m="1226410">plus</span> <span m="1226880">Uy</span> <span m="1227250">squared.</span>
  <span m="1227510">This is</span> <span m="1227640">the</span> <span m="1227770">angle.</span>
  <span m="1228780">And</span> <span m="1229130">as</span> <span m="1229290">you</span>
  <span m="1229400">plug</span> <span m="1229840">it</span> <span m="1229960">in,</span>
  <span m="1230230">it</span> <span m="1230717">is--</span> <span m="1232180">oh,</span>
  <span m="1232500">and</span> <span m="1232915">times the</span> <span m="1233330">area.</span>
  <span m="1234560">When</span> <span m="1234750">you</span> <span m="1234870">plug</span>
  <span m="1235290">it</span> <span m="1235340">in,</span> <span m="1235580">it is</span>
  <span m="1236040">equal</span> <span m="1236500">to</span> <span m="1236670">minus</span>
  <span m="1238210">1/2</span> <span m="1238480">of</span> <span m="1238650">Cd</span>
  <span m="1240226">times</span> <span m="1240680">row</span> <span m="1241290">S</span>
  <span m="1244160">times</span> <span m="1245130">square</span> <span m="1245430">root</span>
  <span m="1245620">of</span> <span m="1245790">Ux</span> <span m="1246670">squared</span>
  <span m="1247570">plus</span> <span m="1248000">Uy</span> <span m="1248320">squared</span>
  <span m="1248640">times</span> <span m="1249180">Ux.</span> <span m="1250890">And</span>
  <span m="1252140">dUy</span> <span m="1259870">dt</span> <span m="1261300">is</span>
  <span m="1261690">equal</span> <span m="1262130">to</span> <span m="1264510">first
  of all--</span></p><p><span m="1266702">Wait.</span> <span m="1268290">I</span>
  <span m="1268380">think</span> <span m="1268970">I''m</span> <span m="1269100">missing</span>
  <span m="1269790">an</span> <span m="1270110">m</span> <span m="1270260">here.</span>
  <span m="1271160">m</span> <span m="1271540">times</span> <span m="1271870">d Uy/dt.</span>
  <span m="1272770">That</span> <span m="1272950">is</span> <span m="1273190">the</span>
  <span m="1273350">acceleration</span> <span m="1274575">on</span> <span m="1275080">the</span>
  <span m="1275210">y</span> <span m="1275480">direction,</span> <span m="1276200">which</span>
  <span m="1276280">is</span> <span m="1276420">also</span> <span m="1276850">equal</span>
  <span m="1276950">to</span> <span m="1277200">the</span> <span m="1277440">force</span>
  <span m="1277750">in</span> <span m="1277820">the</span> <span m="1277890">y</span>
  <span m="1278060">direction.</span> <span m="1278990">It</span> <span m="1279060">is</span>
  <span m="1279290">equal</span> <span m="1279580">to</span> <span m="1279690">minus</span>
  <span m="1280010">m</span> <span m="1280330">times</span> <span m="1281130">g</span>
  <span m="1282580">minus</span> <span m="1284550">a</span> <span m="1284690">similar</span>
  <span m="1285310">drag</span> <span m="1285760">component</span> <span m="1286880">which</span>
  <span m="1287100">has</span> <span m="1287280">the</span> <span m="1287400">same</span>
  <span m="1287720">Cd</span> <span m="1288310">Row</span> <span m="1288600">S</span>
  <span m="1289250">over</span> <span m="1289550">two.</span> <span m="1290850">It</span>
  <span m="1291120">has</span> <span m="1291400">the</span> <span m="1291510">same</span>
  <span m="1293074">square</span> <span m="1293531">root</span> <span m="1293988">of
  Ux</span> <span m="1295359">squared</span> <span m="1295816">plus Uy</span> <span
  m="1296280">squared.</span> <span m="1297090">But</span> <span m="1297330">the</span>
  <span m="1297420">direction</span> <span m="1298150">is</span> <span m="1298430">in</span>
  <span m="1298520">the</span> <span m="1298600">y.</span> <span m="1298940">So it</span>
  <span m="1299080">is</span> <span m="1299900">proportional</span> <span m="1300620">to
  the</span> <span m="1301084">Uy.</span> <span m="1302940">All right. So</span> <span
  m="1303090">these</span> <span m="1303480">are</span> <span m="1303620">the</span>
  <span m="1303710">two</span> <span m="1303960">differential</span> <span m="1304430">equations.</span></p><p><span
  m="1305160">And</span> <span m="1305360">when</span> <span m="1305630">you</span>
  <span m="1305760">want</span> <span m="1306050">to</span> <span m="1306640">compute</span>
  <span m="1307020">the</span> <span m="1307100">trajectory,</span> <span m="1308480">you</span>
  <span m="1308690">also</span> <span m="1309040">need</span> <span m="1310020">dx/dt</span>
  <span m="1311350">equals</span> <span m="1311740">what?</span> <span m="1315250">x</span>
  <span m="1315850">and</span> <span m="1316980">y</span> <span m="1317300">is</span>
  <span m="1317540">the</span> <span m="1317610">location</span> <span m="1318140">of</span>
  <span m="1318310">the</span> <span m="1318510">cannon ball.</span> <span m="1320030">Ux</span>
  <span m="1320290">have</span> <span m="1321030">and</span> <span m="1321350">dy/dt</span>
  <span m="1321970">equal</span> <span m="1322290">to</span> <span m="1322480">Uy.</span>
  <span m="1324845">So</span> <span m="1325300">these</span> <span m="1325790">are</span>
  <span m="1326070">the</span> <span m="1326380">four</span> <span m="1326480">differential</span>
  <span m="1326940">equations</span> <span m="1328170">you</span> <span m="1328390">need</span>
  <span m="1328570">to</span> <span m="1329490">implement</span> <span m="1329750">and
  solve.</span></p><p><span m="1331490">So</span> <span m="1331560">let''s</span>
  <span m="1331780">try</span> <span m="1332190">fourth</span> <span m="1332676">order</span>
  <span m="1333162">first.</span> <span m="1336940">And</span> <span m="1338100">if</span>
  <span m="1338670">you</span> <span m="1339470">checked</span> <span m="1339720">your</span>
  <span m="1339880">email</span> <span m="1340320">over</span> <span m="1340540">the</span>
  <span m="1340620">last</span> <span m="1341040">half an</span> <span m="1341420">hour,</span>
  <span m="1341800">you''re going</span> <span m="1342180">to</span> <span m="1342560">see</span>
  <span m="1342830">I</span> <span m="1343050">shared a Dropbox</span> <span m="1343544">folder</span>
  <span m="1344038">with you.</span> <span m="1345026">How many people</span> <span
  m="1345520">got</span> <span m="1345730">that?</span> <span m="1347050">OK.</span>
  <span m="1348440">So</span> <span m="1348620">if</span> <span m="1348850">you</span>
  <span m="1349600">are</span> <span m="1349680">happy</span> <span m="1349960">with</span>
  <span m="1350190">it</span> <span m="1351290">and</span> <span m="1351460">if</span>
  <span m="1351580">you</span> <span m="1351700">have</span> <span m="1351910">Dropbox</span>
  <span m="1352330">on your</span> <span m="1352450">computer,</span> <span m="1352890">you</span>
  <span m="1353210">can</span> <span m="1353300">make</span> <span m="1353590">the
  subdirectory</span> <span m="1354670">in the</span> <span m="1354910">shared</span>
  <span m="1355380">folder</span> <span m="1357080">and</span> <span m="1358340">you</span>
  <span m="1358490">can</span> <span m="1358700">pull</span> <span m="1358900">in</span>
  <span m="1359030">that</span> <span m="1359445">directory</span> <span m="1359860">so</span>
  <span m="1361640">I can</span> <span m="1362130">take</span> <span m="1362370">a</span>
  <span m="1362420">look</span> <span m="1362720">from</span> <span m="1363000">here</span>
  <span m="1364000">after</span> <span m="1364500">you put it up.</span></p><p><span
  m="1370310">So</span> <span m="1370890">if</span> <span m="1371060">you</span> <span
  m="1371200">look</span> <span m="1371400">at your</span> <span m="1371550">email,</span>
  <span m="1372270">you</span> <span m="1372430">are</span> <span m="1372490">going</span>
  <span m="1372620">to</span> <span m="1372790">see</span> <span m="1373040">a folder</span>
  <span m="1373610">called</span> <span m="1374450">1690shared2014</span> <span m="1379030">being</span>
  <span m="1379290">shared</span> <span m="1379550">with</span> <span m="1379800">you.</span>
  <span m="1379920">If</span> <span m="1380100">you</span> <span m="1380180">accept</span>
  <span m="1380640">it,</span> <span m="1381480">everybody</span> <span m="1382160">is</span>
  <span m="1382350">going</span> <span m="1382490">to</span> <span m="1382710">see</span>
  <span m="1382910">the</span> <span m="1383050">same</span> <span m="1383830">content</span>
  <span m="1384270">here.</span> <span m="1385060">And</span> <span m="1385460">I</span>
  <span m="1385570">see</span> <span m="1386860">people</span> <span m="1387180">have</span>
  <span m="1387440">already</span> <span m="1389050">uploaded</span> <span m="1389330">code</span>
  <span m="1389530">over here.</span> <span m="1394610">Great.</span> <span m="1395030">Thank</span>
  <span m="1395250">you</span> <span m="1395350">very</span> <span m="1395670">much.</span>
  <span m="1396220">I''m</span> <span m="1396680">going</span> <span m="1396840">to</span>
  <span m="1396930">open</span> <span m="1397380">your</span> <span m="1397610">model.</span></p><p><span
  m="1398160">AUDIENCE: [INAUDIBLE].</span></p><p><span m="1401530">QIQI WANG: That''s
  a</span> <span m="1401760">what?</span></p><p><span m="1402720">AUDIENCE: Let me
  upload my</span> <span m="1403200">[INAUDIBLE].</span></p><p><span m="1403680">QIQI
  WANG: Oh</span> <span m="1403890">OK.</span> <span m="1404190">Sure.</span> <span
  m="1404550">Please.</span></p><p><span m="1405270">AUDIENCE: [INAUDIBLE].</span></p><p><span
  m="1406590">QIQI WANG: Are you going to</span> <span m="1406930">also--</span></p><p><span
  m="1407140">AUDIENCE: OK.</span></p><p><span m="1410550">QIQI WANG: Oops.</span>
  <span m="1413454">OK.</span> <span m="1413940">I''m</span> <span m="1414110">going</span>
  <span m="1414240">to wait.</span> <span m="1424350">Oh</span> <span m="1424580">OK.</span>
  <span m="1424940">So</span> <span m="1425120">somebody</span> <span m="1426340">must</span>
  <span m="1426620">have</span> <span m="1426920">not</span> <span m="1427270">had</span>
  <span m="1427400">Dropbox</span> <span m="1427930">before.</span> <span m="1428320">Because</span>
  <span m="1429570">if</span> <span m="1430060">I</span> <span m="1430180">shared</span>
  <span m="1430460">with</span> <span m="1430650">you</span> <span m="1431410">and
  you</span> <span m="1431790">actually--</span></p><p><span m="1432268">AUDIENCE:
  [INAUDIBLE].</span></p><p><span m="1434180">QIQI WANG: Yeah.</span></p><p><span
  m="1434440">[LAUGHTER]</span></p><p><span m="1438868">AUDIENCE: [INAUDIBLE].</span></p><p><span
  m="1447232">QIQI WANG: I get more</span> <span m="1447740">space if I</span> <span
  m="1447930">shared.</span> <span m="1448350">And</span> <span m="1448841">as</span>
  <span m="1449332">a</span> <span m="1449823">result</span> <span m="1450314">of
  my</span> <span m="1450805">sharing,</span> <span m="1451300">somebody</span> <span
  m="1451560">who</span> <span m="1452330">didn''t use</span> <span m="1452740">Dropbox</span>
  <span m="1453150">before</span> <span m="1453560">now uses</span> <span m="1453970">Dropbox.</span></p><p><span
  m="1454380">AUDIENCE: Oh.</span></p><p><span m="1455674">QIQI WANG: Yes.</span></p><p><span
  m="1458596">AUDIENCE: So you</span> <span m="1459083">don''t get</span> <span m="1459570">access</span>
  <span m="1460057">to anything?</span></p><p><span m="1467362">QIQI WANG: All</span>
  <span m="1467850">right.</span> <span m="1469390">OK.</span> <span m="1469690">So</span>
  <span m="1469920">I</span> <span m="1470080">have</span> <span m="1472410">codes</span>
  <span m="1472940">here.</span> <span m="1474650">And</span> <span m="1475280">let</span>
  <span m="1475480">me</span> <span m="1475710">first</span> <span m="1476100">run</span>
  <span m="1476370">it</span> <span m="1477250">to</span> <span m="1477390">see</span>
  <span m="1477560">if</span> <span m="1477660">it</span> <span m="1477760">also</span>
  <span m="1478040">runs in my</span> <span m="1478481">computer.</span> <span m="1479804">Mmm.</span></p><p><span
  m="1481130">AUDIENCE: What</span> <span m="1481710">is</span> <span m="1483370">[INAUDIBLE]?</span></p><p><span
  m="1485860">QIQI WANG: Oh.</span> <span m="1486170">I</span> <span m="1486300">see,</span>
  <span m="1486540">I</span> <span m="1486700">see.</span> <span m="1486940">OK.</span>
  <span m="1489760">So</span> <span m="1489920">let''s</span> <span m="1490430">go</span>
  <span m="1491200">through</span> <span m="1495070">the</span> <span m="1495190">[INAUDIBLE]</span>
  <span m="1495490">here</span> <span m="1495840">and</span> <span m="1496190">explain</span>
  <span m="1496475">to</span> <span m="1496760">us</span> <span m="1498560">what</span>
  <span m="1499210">is</span> <span m="1499390">your</span> <span m="1499590">code</span>
  <span m="1500050">doing.</span></p><p><span m="1501890">AUDIENCE: Right.</span>
  <span m="1510100">So first,</span> <span m="1510500">I put in</span> <span m="1510630">some</span>
  <span m="1510910">constants</span> <span m="1511170">that we</span> <span m="1511640">need--</span>
  <span m="1512090">the</span> <span m="1512170">diameter,</span> <span m="1512485">the</span>
  <span m="1512800">coefficient</span> <span m="1513266">drag.</span> <span m="1515130">I</span>
  <span m="1515380">apologize</span> <span m="1515620">for</span> <span m="1515830">any</span>
  <span m="1516000">errors.</span> <span m="1516440">I''m</span> <span m="1516900">definitely</span>
  <span m="1516990">not</span> <span m="1517140">immune</span> <span m="1517280">to
  errors.</span> <span m="1517986">I don''t think</span> <span m="1518340">there are</span>
  <span m="1518480">any.</span> <span m="1519120">But</span> <span m="1519510">we
  calculate</span> <span m="1520070">drag.</span> <span m="1520730">And then I</span>
  <span m="1520850">calculate</span> <span m="1522370">the</span> <span m="1522480">cross-sectional</span>
  <span m="1522890">area,</span> <span m="1523340">rho,</span> <span m="1524040">gravity.</span>
  <span m="1525200">And then</span> <span m="1525370">I</span> <span m="1525780">figure</span>
  <span m="1525850">out the</span> <span m="1525920">initial</span> <span m="1526220">conditions.</span>
  <span m="1526830">So</span> <span m="1526990">I</span> <span m="1527110">didn''t</span>
  <span m="1527450">actually</span> <span m="1528340">hear if you gave</span> <span
  m="1528620">us</span> <span m="1528955">an</span> <span m="1529290">output.</span>
  <span m="1529740">So I just</span> <span m="1530197">put in</span> <span m="1530654">pi
  over 4.</span></p><p><span m="1531111">QIQI WANG: OK great.</span></p><p><span m="1531570">AUDIENCE:
  But</span> <span m="1531730">I</span> <span m="1531790">could</span> <span m="1531970">have</span>
  <span m="1532070">put</span> <span m="1532190">anything</span> <span m="1532490">in</span>
  <span m="1532590">there.</span> <span m="1533710">So I</span> <span m="1534150">calculated</span>
  <span m="1534350">the</span> <span m="1534440">initial</span> <span m="1536340">x
  and y</span> <span m="1536810">velocities</span> <span m="1537410">here.</span>
  <span m="1538060">And</span> <span m="1538220">then I</span> <span m="1538370">create</span>
  <span m="1538790">vectors</span> <span m="1539320">with</span> <span m="1539610">plenty
  of</span> <span m="1539890">space</span> <span m="1540430">to</span> <span m="1540520">hold</span>
  <span m="1540780">all</span> <span m="1540990">my</span> <span m="1541160">[INAUDIBLE]</span>
  <span m="1542020">and</span> <span m="1542310">set</span> <span m="1542620">the</span>
  <span m="1543040">initial</span> <span m="1543420">conditions</span> <span m="1544260">in
  the velocity.</span> <span m="1544910">And</span> <span m="1545050">then I</span>
  <span m="1545110">create a</span> <span m="1545410">time step.</span> <span m="1545860">And</span>
  <span m="1545960">then</span> <span m="1546060">this is</span> <span m="1546530">the</span>
  <span m="1547000">integration.</span></p><p><span m="1547940">So</span> <span m="1547960">what</span>
  <span m="1548100">I</span> <span m="1548190">say</span> <span m="1548490">is</span>
  <span m="1548620">the</span> <span m="1549450">position</span> <span m="1551361">at</span>
  <span m="1551750">1 times</span> <span m="1552090">7,</span> <span m="1552430">the</span>
  <span m="1552500">future</span> <span m="1553290">x</span> <span m="1553745">position</span>
  <span m="1554450">is</span> <span m="1555030">the</span> <span m="1555130">current</span>
  <span m="1555520">x</span> <span m="1555810">position</span> <span m="1556100">times</span>
  <span m="1556980">et</span> <span m="1557430">times</span> <span m="1557800">the</span>
  <span m="1558180">x</span> <span m="1558450">velocity.</span> <span m="1559680">And</span>
  <span m="1559890">same</span> <span m="1560050">thing</span> <span m="1560220">for</span>
  <span m="1560320">y.</span> <span m="1561040">And</span> <span m="1561210">I</span>
  <span m="1561270">have</span> <span m="1561390">to calculate</span> <span m="1561890">the</span>
  <span m="1561950">changes</span> <span m="1562440">to</span> <span m="1562570">the</span>
  <span m="1562650">velocity</span> <span m="1563220">of</span> <span m="1563310">both</span>
  <span m="1563520">x</span> <span m="1563720">and</span> <span m="1563830">y.</span>
  <span m="1564450">And</span> <span m="1564620">then</span> <span m="1564740">I</span>
  <span m="1564870">add</span> <span m="1565130">those,</span> <span m="1565880">again</span>
  <span m="1566200">multiplying</span> <span m="1566660">by</span> <span m="1566760">the</span>
  <span m="1566850">time step.</span> <span m="1567795">And</span> <span m="1568180">then</span>
  <span m="1568460">here</span> <span m="1569350">it hits</span> <span m="1569760">the</span>
  <span m="1569840">ground</span> <span m="1570130">again,</span> <span m="1570390">I</span>
  <span m="1570540">think.</span> <span m="1571962">And then I plot.</span></p><p><span
  m="1574810">QIQI WANG: Great.</span> <span m="1575240">Thank</span> <span m="1575470">you.</span>
  <span m="1577112">Any questions</span> <span m="1577566">about</span> <span m="1578020">this</span>
  <span m="1578320">[INAUDIBLE]?</span> <span m="1583468">Is it perfectly</span> <span
  m="1583940">clear,</span> <span m="1584370">everything?</span></p><p><span m="1585060">AUDIENCE:
  [INAUDIBLE].</span></p><p><span m="1588040">QIQI WANG: Here.</span> <span m="1588370">Let</span>
  <span m="1588410">me</span> <span m="1588600">run</span> <span m="1588830">it</span>
  <span m="1588930">again</span> <span m="1589910">to</span> <span m="1590050">see</span>
  <span m="1590300">if</span> <span m="1590450">it</span> <span m="1590740">actually</span>
  <span m="1591280">still</span> <span m="1591640">works.</span> <span m="1593420">I
  am</span> <span m="1593865">going to</span> <span m="1594310">click</span> <span
  m="1594740">Run.</span> <span m="1595956">It</span> <span m="1596320">works.</span></p><p><span
  m="1596910">AUDIENCE: And there''s</span> <span m="1597170">some</span> <span m="1597420">residuals</span>
  <span m="1597580">here</span> <span m="1598076">[INAUDIBLE].</span></p><p><span
  m="1608280">QIQI WANG: So</span> <span m="1609200">thank</span> <span m="1609410">you.</span>
  <span m="1611880">And</span> <span m="1612090">let</span> <span m="1612840">me</span>
  <span m="1613190">take</span> <span m="1613450">a</span> <span m="1613520">look</span>
  <span m="1613870">at</span> <span m="1614440">another</span> <span m="1614850">code</span>
  <span m="1615390">that</span> <span m="1615630">is</span> <span m="1616210">by</span>
  <span m="1618830">same</span> <span m="1619060">thing.</span> <span m="1620310">Did</span>
  <span m="1620510">you</span> <span m="1620750">update?</span></p><p><span m="1621560">AUDIENCE:
  Yeah.</span></p><p><span m="1623620">QIQI WANG: Let</span> <span m="1623800">me</span>
  <span m="1624250">close it.</span> <span m="1625500">So--</span></p><p><span m="1630780">AUDIENCE:
  Probably</span> <span m="1631260">ballistic.</span></p><p><span m="1632680">QIQI
  WANG: Ballistic.</span></p><p><span m="1635065">AUDIENCE: Yeah.</span> <span m="1635516">That''s</span>
  <span m="1635967">been upgraded.</span></p><p><span m="1637320">QIQI WANG: OK.</span></p><p><span
  m="1641562">AUDIENCE: Try</span> <span m="1642036">again.</span></p><p><span m="1645360">QIQI
  WANG: No.</span> <span m="1646170">OK.</span> <span m="1646600">I</span> <span m="1646770">got</span>
  <span m="1646960">another</span> <span m="1647430">code</span> <span m="1647770">from--</span>
  <span m="1651220">all right.</span> <span m="1652090">Thanks.</span> <span m="1652990">And</span>
  <span m="1653210">which</span> <span m="1653460">one</span> <span m="1653690">should</span>
  <span m="1653840">I</span> <span m="1653950">look</span> <span m="1654150">at</span>
  <span m="1654260">first?</span></p><p><span m="1655506">AUDIENCE: [INAUDIBLE].</span></p><p><span
  m="1657721">QIQI WANG: [INAUDIBLE].</span> <span m="1660000">Do</span> <span m="1660320">you</span>
  <span m="1660420">mind</span> <span m="1660640">coming</span> <span m="1660905">here
  and</span> <span m="1661170">explaining</span> <span m="1661760">what</span> <span
  m="1662010">you</span> <span m="1662130">did?</span> <span m="1662680">I</span>
  <span m="1662760">think</span> <span m="1663070">it''s</span> <span m="1663290">a</span>
  <span m="1663350">little</span> <span m="1663540">bit</span> <span m="1663690">different</span>
  <span m="1664140">from</span> <span m="1664500">what--</span> <span m="1669490">so</span>
  <span m="1669660">you</span> <span m="1670100">organized</span> <span m="1670680">the</span>
  <span m="1670790">code</span> <span m="1671530">in</span> <span m="1671680">a</span>
  <span m="1671750">different</span> <span m="1672090">way.</span> <span m="1672500">I</span>
  <span m="1672610">think</span> <span m="1673390">this</span> <span m="1673780">is</span>
  <span m="1673920">more</span> <span m="1675302">consistent</span> <span m="1675780">with</span>
  <span m="1675990">what</span> <span m="1676440">I did</span> <span m="1676890">in
  the</span> <span m="1677210">last section.</span></p><p><span m="1678805">AUDIENCE:
  Yeah.</span></p><p><span m="1682765">QIQI WANG: Of</span> <span m="1683260">the</span>
  <span m="1683400">other</span> <span m="1683660">one.</span> <span m="1683920">Yeah,</span>
  <span m="1684360">the other</span> <span m="1684800">one.</span></p><p><span m="1686560">AUDIENCE:
  So</span> <span m="1687440">what</span> <span m="1687690">I</span> <span m="1687950">did</span>
  <span m="1688416">was to</span> <span m="1689350">find</span> <span m="1689660">all</span>
  <span m="1689820">my</span> <span m="1689960">initial</span> <span m="1690440">values,</span>
  <span m="1691968">I chose a</span> <span m="1692442">state</span> <span m="1692916">of</span>
  <span m="1693390">45</span> <span m="1693864">degrees.</span> <span m="1696234">And
  this</span> <span m="1696710">is</span> <span m="1697000">all</span> <span m="1697210">[INAUDIBLE],</span>
  <span m="1697430">actually.</span></p><p><span m="1699071">[LAUGHTER]</span></p><p><span
  m="1701276">I</span> <span m="1701720">defined</span> <span m="1702530">my rate</span>
  <span m="1702850">on</span> <span m="1703170">each</span> <span m="1703667">side</span>
  <span m="1704661">as</span> <span m="1705160">1,000</span> <span m="1705630">elements.</span>
  <span m="1706320">And</span> <span m="1706520">then</span> <span m="1706720">I</span>
  <span m="1707150">chose a dt</span> <span m="1707550">of</span> <span m="1708150">0.01.</span>
  <span m="1709454">And</span> <span m="1709916">then I</span> <span m="1710380">made
  an initial</span> <span m="1710870">vector</span> <span m="1711340">which</span>
  <span m="1711520">has</span> <span m="1711820">my</span> <span m="1713580">x0,</span>
  <span m="1714090">y0,</span> <span m="1714690">and the</span> <span m="1715070">dx0</span>
  <span m="1715360">and</span> <span m="1715640">dy0.</span> <span m="1717470">And</span>
  <span m="1717700">then</span> <span m="1717950">we</span> <span m="1718070">go</span>
  <span m="1718300">into</span> <span m="1718560">the</span> <span m="1718590">while</span>
  <span m="1718880">loop</span> <span m="1719170">to do</span> <span m="1719330">our</span>
  <span m="1719990">forward</span> <span m="1720350">Euler</span> <span m="1720560">method.</span>
  <span m="1722440">And</span> <span m="1725240">then</span> <span m="1725580">to</span>
  <span m="1725720">calculate</span> <span m="1729140">our</span> <span m="1729290">next</span>
  <span m="1729560">element</span> <span m="1730110">in</span> <span m="1730350">our</span>
  <span m="1730960">forward</span> <span m="1731855">Euler</span> <span m="1732890">method,</span>
  <span m="1734290">I go to</span> <span m="1734720">this</span> <span m="1734860">function</span>
  <span m="1735320">called</span> <span m="1735580">trajectory</span> <span m="1736240">that</span>
  <span m="1736520">I made.</span></p><p><span m="1737490">QIQI WANG: So</span> <span
  m="1737740">trajectory</span> <span m="1738345">t</span> <span m="1738660">is</span>
  <span m="1738790">a function</span> <span m="1739230">you</span> <span m="1739460">made.</span>
  <span m="1739900">So</span> <span m="1740060">let me</span> <span m="1740260">open</span>
  <span m="1740320">this</span> <span m="1740960">also.</span> <span m="1743810">All</span>
  <span m="1744030">right.</span></p><p><span m="1744860">AUDIENCE: Yeah.</span> <span
  m="1745120">And then</span> <span m="1745460">here,</span> <span m="1746030">you</span>
  <span m="1746110">can see</span> <span m="1746610">the</span> <span m="1747090">equation</span>
  <span m="1748320">[INAUDIBLE].</span> <span m="1751140">And</span> <span m="1751430">so
  what</span> <span m="1751750">this</span> <span m="1752172">trajectory</span> <span
  m="1752594">does is</span> <span m="1753016">it</span> <span m="1753440">takes</span>
  <span m="1753860">in</span> <span m="1754690">the</span> <span m="1756386">position</span>
  <span m="1757310">and</span> <span m="1757490">velocity.</span> <span m="1758630">It</span>
  <span m="1759090">applies</span> <span m="1759610">them</span> <span m="1760260">to
  the</span> <span m="1760720">[INAUDIBLE]</span> <span m="1761005">we</span> <span
  m="1761290">derived,</span> <span m="1761565">and</span> <span m="1761840">then</span>
  <span m="1762120">outputs</span> <span m="1763860">two</span> <span m="1764170">velocities</span>
  <span m="1765040">and</span> <span m="1765410">two</span> <span m="1765630">[INAUDIBLE],</span>
  <span m="1767490">which we then</span> <span m="1767820">multiply</span> <span m="1768210">by
  a change</span> <span m="1768580">in</span> <span m="1768950">our</span> <span m="1769265">time
  step</span> <span m="1770855">to solve</span> <span m="1771280">for</span> <span
  m="1771705">the</span> <span m="1772130">new</span> <span m="1772810">position</span></p><p><span
  m="1775620">QIQI WANG: We</span> <span m="1775750">have</span> <span m="1775960">any</span>
  <span m="1776265">questions</span> <span m="1776570">on</span> <span m="1776750">this?</span>
  <span m="1779970">And</span> <span m="1780480">in</span> <span m="1780670">the</span>
  <span m="1780840">other</span> <span m="1781180">file,</span> <span m="1781690">I</span>
  <span m="1781790">believe</span> <span m="1782610">I</span> <span m="1782810">need</span>
  <span m="1783050">to</span> <span m="1783390">change</span> <span m="1783730">this</span>
  <span m="1784040">to</span> <span m="1786054">this.</span> <span m="1786850">Because</span>
  <span m="1787330">I</span> <span m="1787430">think</span> <span m="1787680">you</span>
  <span m="1787820">changed</span> <span m="1788160">the</span> <span m="1788270">name</span>
  <span m="1788600">of</span> <span m="1789020">this</span> <span m="1790490">which</span>
  <span m="1790950">you</span> <span m="1791070">also</span> <span m="1791310">have</span>
  <span m="1791420">to</span> <span m="1791520">change</span> <span m="1791820">this</span>
  <span m="1792060">too.</span> <span m="1792534">So that</span> <span m="1793008">way,</span>
  <span m="1793482">[INAUDIBLE].</span> <span m="1794904">So</span> <span m="1795380">[INAUDIBLE],</span>
  <span m="1795720">you can</span> <span m="1795870">do the</span> <span m="1796322">derivative</span>
  <span m="1796774">that you</span> <span m="1797226">did.</span></p><p><span m="1798130">AUDIENCE:
  After</span> <span m="1798582">we did the</span> <span m="1799040">derivative,</span>
  <span m="1800230">we</span> <span m="1800955">have</span> <span m="1801310">to</span>
  <span m="1801570">multiply</span> <span m="1801930">it</span> <span m="1802645">by</span>
  <span m="1802970">our</span> <span m="1803300">time step</span> <span m="1804618">to</span>
  <span m="1806070">go</span> <span m="1806270">up an order</span> <span m="1806630">to</span>
  <span m="1806990">change it</span> <span m="1807333">from</span> <span m="1807676">velocity</span>
  <span m="1808020">to speed</span> <span m="1808380">and</span> <span m="1808635">position.</span>
  <span m="1810100">We</span> <span m="1810300">add</span> <span m="1810450">that</span>
  <span m="1810710">to our</span> <span m="1810850">old</span> <span m="1811080">position</span>
  <span m="1811532">and</span> <span m="1811984">get</span> <span m="1812436">our
  new position.</span> <span m="1813792">And</span> <span m="1814244">then we</span>
  <span m="1814696">store</span> <span m="1815148">that</span> <span m="1815600">in
  our</span> <span m="1815820">position</span> <span m="1816100">vectors.</span> <span
  m="1817410">And</span> <span m="1817710">then we</span> <span m="1818000">[INAUDIBLE]</span>
  <span m="1818740">the</span> <span m="1819120">position.</span></p><p><span m="1820530">QIQI
  WANG: OK.</span> <span m="1821580">Let''s</span> <span m="1822080">try</span> <span
  m="1822400">to</span> <span m="1822610">see</span> <span m="1823210">if</span> <span
  m="1823380">it works.</span> <span m="1829740">OK.</span> <span m="1829980">Let
  me</span> <span m="1830275">close</span> <span m="1830570">everything.</span> <span
  m="1833562">Let''s</span> <span m="1834020">click</span> <span m="1834470">Run.</span>
  <span m="1836430">Yeah.</span> <span m="1836920">We</span> <span m="1837330">get
  a</span> <span m="1838550">[INAUDIBLE].</span></p><p><span m="1840251">AUDIENCE:
  [INAUDIBLE]</span></p><p><span m="1842860">QIQI WANG: Yeah.</span></p><p><span m="1843760">[LAUGHTER]</span></p><p><span
  m="1844620">And we do</span> <span m="1844900">see</span> <span m="1845180">that</span>
  <span m="1845951">[INAUDIBLE],</span> <span m="1848777">right?</span> <span m="1850190">Because
  the</span> <span m="1850670">angle</span> <span m="1852160">here</span> <span m="1852450">is</span>
  <span m="1852660">much</span> <span m="1853135">deeper</span> <span m="1853610">than</span>
  <span m="1854560">the</span> <span m="1855035">other</span> <span m="1855985">angles.</span>
  <span m="1857885">[INAUDIBLE]</span> <span m="1859660">slower</span> <span m="1860600">than</span>
  <span m="1861070">when</span> <span m="1861250">it was</span> <span m="1861330">shut
  off.</span></p><p><span m="1863340">OK.</span> <span m="1863940">Now</span> <span
  m="1864120">my</span> <span m="1864310">question</span> <span m="1864780">to</span>
  <span m="1864910">you</span> <span m="1865040">is,</span> <span m="1866345">what
  if</span> <span m="1866780">I</span> <span m="1866980">want</span> <span m="1867220">to</span>
  <span m="1867300">challenge</span> <span m="1867690">you</span> <span m="1867760">with</span>
  <span m="1868620">a</span> <span m="1868710">question?</span> <span m="1869380">What</span>
  <span m="1869640">if</span> <span m="1869790">I</span> <span m="1869890">want</span>
  <span m="1870080">to</span> <span m="1870170">change</span> <span m="1870520">this</span>
  <span m="1870820">to</span> <span m="1870940">midpoint?</span> <span m="1872170">From</span>
  <span m="1872380">last</span> <span m="1872730">lecture,</span> <span m="1873030">we</span>
  <span m="1873230">saw</span> <span m="1873500">that</span> <span m="1874220">at
  the</span> <span m="1874460">same</span> <span m="1874800">time step,</span> <span
  m="1875390">midpoint</span> <span m="1876100">was</span> <span m="1876365">much</span>
  <span m="1877290">more</span> <span m="1877550">accurate</span> <span m="1878500">than</span>
  <span m="1878790">forward Euler.</span> <span m="1879860">Right?</span> <span m="1881180">So</span>
  <span m="1881410">what</span> <span m="1881820">should</span> <span m="1882272">we</span>
  <span m="1882724">do</span> <span m="1883176">to</span> <span m="1883630">change
  this</span> <span m="1883840">to</span> <span m="1884325">midpoint?</span> <span
  m="1885920">I''m</span> <span m="1886270">asking</span> <span m="1886580">the</span>
  <span m="1886660">whole</span> <span m="1886820">class.</span> <span m="1894315">Anybody</span>
  <span m="1894960">have</span> <span m="1895340">any</span> <span m="1895450">idea?</span>
  <span m="1900730">Yes?</span></p><p><span m="1902620">AUDIENCE: [INAUDIBLE].</span></p><p><span
  m="1920010">QIQI WANG: Good.</span></p><p><span m="1920773">AUDIENCE: [INAUDIBLE].</span></p><p><span
  m="1923671">QIQI WANG: Thank you.</span></p><p><span m="1924637">AUDIENCE: [INAUDIBLE].</span></p><p><span
  m="1927052">QIQI WANG: [INAUDIBLE].</span> <span m="1928501">OK.</span> <span m="1930440">OK.</span>
  <span m="1931450">So,</span> <span m="1931760">right.</span> <span m="1933360">Now</span>
  <span m="1933570">the</span> <span m="1933640">question</span> <span m="1933940">is</span>
  <span m="1934160">what</span> <span m="1934630">if</span> <span m="1934830">we</span>
  <span m="1934960">want</span> <span m="1935140">to</span> <span m="1935210">change</span>
  <span m="1935640">this</span> <span m="1935830">to</span> <span m="1936190">midpoint?</span>
  <span m="1938210">If we</span> <span m="1938350">change</span> <span m="1938675">this  to</span>
  <span m="1939000">midpoint,</span> <span m="1940730">the</span> <span m="1940930">first</span>
  <span m="1941400">thing</span> <span m="1941650">is that</span> <span m="1943220">midpoint</span>
  <span m="1943770">is</span> <span m="1944656">a</span> <span m="1945000">how</span>
  <span m="1945160">many</span> <span m="1945440">step</span> <span m="1945800">scheme?</span>
  <span m="1947890">It''s a</span> <span m="1948190">two-step</span> <span m="1948550">scheme.</span>
  <span m="1949140">Forward</span> <span m="1949400">Euler</span> <span m="1949730">is
  a</span> <span m="1949870">one step</span> <span m="1950190">scheme.</span> <span
  m="1951270">So</span> <span m="1951420">in</span> <span m="1951590">terms</span>
  <span m="1951870">of</span> <span m="1952090">implementation,</span> <span m="1953280">what
  do</span> <span m="1953490">we need</span> <span m="1953730">to</span> <span m="1954280">change?</span>
  <span m="1955515">What</span> <span m="1955780">do</span> <span m="1956100">we need</span>
  <span m="1956510">to</span> <span m="1957450">ignore</span> <span m="1957900">when</span>
  <span m="1958140">we</span> <span m="1958730">switch</span> <span m="1959170">from</span>
  <span m="1959460">a</span> <span m="1960424">one</span> <span m="1960826">step</span>
  <span m="1961230">scheme</span> <span m="1961610">to</span> <span m="1961910">a</span>
  <span m="1962090">two-step</span> <span m="1962992">scheme?</span> <span m="1965700">Why</span>
  <span m="1965980">do</span> <span m="1966080">we</span> <span m="1966210">call</span>
  <span m="1966430">it</span> <span m="1966600">a</span> <span m="1966810">two step</span>
  <span m="1967130">scheme?</span></p><p><span m="1969585">AUDIENCE: [INAUDIBLE].</span></p><p><span
  m="1972040">QIQI WANG: Because</span> <span m="1972490">we</span> <span m="1972886">need</span>
  <span m="1973282">to</span> <span m="1974530">store</span> <span m="1975040">two</span>
  <span m="1975300">time steps.</span> <span m="1976900">Here</span> <span m="1977220">we</span>
  <span m="1979000">only</span> <span m="1979270">need</span> <span m="1979450">to</span>
  <span m="1979910">have</span> <span m="1980080">that.</span> <span m="1980580">That</span>
  <span m="1980830">is</span> <span m="1982130">one</span> <span m="1982560">previous</span>
  <span m="1982820">time step.</span> <span m="1984170">Now</span> <span m="1984600">we</span>
  <span m="1984860">have</span> <span m="1985240">to</span> <span m="1985440">have</span>
  <span m="1985970">two</span> <span m="1986390">previous</span> <span m="1986870">time
  steps.</span> <span m="1988370">Right?</span> <span m="1989800">So</span> <span
  m="1990180">we</span> <span m="1990400">need</span> <span m="1991240">this.</span>
  <span m="1992950">And</span> <span m="1993450">we</span> <span m="1993660">need</span>
  <span m="1993920">one</span> <span m="1994260">step</span> <span m="1994640">of</span>
  <span m="1994760">forward</span> <span m="1995115">Euler</span> <span m="1995470">to</span>
  <span m="1995760">actually</span> <span m="1996330">get</span> <span m="1996920">to</span>
  <span m="1997060">the</span> <span m="1997180">next</span> <span m="1997445">time
  step.</span> <span m="1999010">So</span> <span m="1999240">I''m</span> <span m="1999370">just</span>
  <span m="1999550">going</span> <span m="1999680">to</span> <span m="1999780">say</span>
  <span m="2000310">a</span> <span m="2000430">one</span> <span m="2001100">step</span>
  <span m="2001470">of</span> <span m="2001890">forward</span> <span m="2004570">Euler.</span></p><p><span
  m="2007155">OK.</span> <span m="2007610">So</span> <span m="2008020">in</span> <span
  m="2008270">doing</span> <span m="2008590">one</span> <span m="2008870">step of</span>
  <span m="2009000">forward</span> <span m="2009380">Euler,</span> <span m="2009790">I''m</span>
  <span m="2009970">just</span> <span m="2010150">going</span> <span m="2010280">to</span>
  <span m="2010350">copy</span> <span m="2010810">this</span> <span m="2012580">and</span>
  <span m="2013730">copy</span> <span m="2014160">this.</span> <span m="2014900">Right?</span>
  <span m="2019210">Here,</span> <span m="2019640">I''m</span> <span m="2019930">just</span>
  <span m="2020130">going</span> <span m="2020260">to</span> <span m="2020450">pass</span>
  <span m="2020890">my</span> <span m="2021220">vect</span> <span m="2021700">0.</span>
  <span m="2022780">And</span> <span m="2023160">the</span> <span m="2023270">vect</span>
  <span m="2023680">equal</span> <span m="2024580">to</span> <span m="2024720">vect</span>
  <span m="2025040">0</span> <span m="2025520">plus</span> <span m="2026000">Vt</span>
  <span m="2026480">times</span> <span m="2026960">d vect</span> <span m="2027440">dt.</span>
  <span m="2027920">Any</span> <span m="2028120">questions</span> <span m="2028470">on</span>
  <span m="2028640">this</span> <span m="2029180">one</span> <span m="2029550">step
  of</span> <span m="2029650">forward</span> <span m="2029830">Euler?</span></p><p><span
  m="2035520">OK.</span> <span m="2035820">Now</span> <span m="2036190">we</span>
  <span m="2036530">are</span> <span m="2036630">using</span> <span m="2037060">midpoint.</span>
  <span m="2039850">OK.</span> <span m="2041300">In</span> <span m="2041440">mid-point,</span>
  <span m="2044360">now</span> <span m="2044680">what</span> <span m="2044890">we</span>
  <span m="2045040">want</span> <span m="2045190">to</span> <span m="2045280">change</span>
  <span m="2045670">is</span> <span m="2045860">these</span> <span m="2046870">two</span>
  <span m="2047190">lines.</span> <span m="2048092">Right?</span> <span m="2048909">Let</span>
  <span m="2049250">me</span> <span m="2049525">scroll it</span> <span m="2049800">down.</span>
  <span m="2051580">We</span> <span m="2051750">need</span> <span m="2051929">to</span>
  <span m="2052040">change</span> <span m="2052409">these</span> <span m="2052600">two</span>
  <span m="2052780">lines.</span> <span m="2053170">Can</span> <span m="2053560">somebody</span>
  <span m="2054030">tell</span> <span m="2054239">me</span> <span m="2054380">how</span>
  <span m="2054650">do</span> <span m="2054750">I</span> <span m="2054889">change</span>
  <span m="2055239">lines</span> <span m="2055569">when</span> <span m="2055900">[INAUDIBLE]</span>
  <span m="2056746">to</span> <span m="2057090">make</span> <span m="2057429">this</span>
  <span m="2057650">midpoint</span> <span m="2057820">instead</span> <span m="2058200">of</span>
  <span m="2058580">forward</span> <span m="2058830">Euler?</span> <span m="2067159">Yeah?</span></p><p><span
  m="2067867">AUDIENCE: You</span> <span m="2068325">have</span> <span m="2068783">the
  vect.</span> <span m="2070157">And</span> <span m="2070620">you</span> <span m="2072848">add
  it</span> <span m="2073300">to 2</span> <span m="2073752">times</span> <span m="2074656">U
  vect</span> <span m="2075560">dt</span> <span m="2076444">and</span> <span m="2076886">your</span>
  <span m="2077328">time step.</span></p><p><span m="2079100">QIQI WANG: OK.</span>
  <span m="2079409">So</span> <span m="2079780">first of</span> <span m="2080185">all,</span>
  <span m="2080590">in</span> <span m="2081154">midpoint,</span> <span m="2082340">we</span>
  <span m="2082560">have</span> <span m="2082820">2</span> <span m="2083100">times</span>
  <span m="2083949">delta</span> <span m="2084409">t</span> <span m="2084730">times</span>
  <span m="2085820">F</span> <span m="2086040">of</span> <span m="2086300">v.</span>
  <span m="2086620">Right?</span> <span m="2088070">So</span> <span m="2088260">we</span>
  <span m="2088440">have</span> <span m="2088600">a</span> <span m="2088670">2</span>
  <span m="2088900">times.</span> <span m="2090120">What</span> <span m="2090330">else</span>
  <span m="2090610">do</span> <span m="2090699">we</span> <span m="2090790">need</span>
  <span m="2090940">to</span> <span m="2091040">change?</span></p><p><span m="2093910">AUDIENCE:
  [INAUDIBLE].</span></p><p><span m="2096699">QIQI WANG: For</span> <span m="2097430">which</span>
  <span m="2097901">one?</span></p><p><span m="2101669">AUDIENCE: In</span> <span
  m="2102140">the previous scheme?</span></p><p><span m="2106040">QIQI WANG: Yeah.</span>
  <span m="2107030">You</span> <span m="2107440">are</span> <span m="2107670">right.</span>
  <span m="2108640">When</span> <span m="2109030">I</span> <span m="2110455">do</span>
  <span m="2110710">this,</span> <span m="2115480">I</span> <span m="2115630">need</span>
  <span m="2115890">to</span> <span m="2116080">also</span> <span m="2116510">somehow</span>
  <span m="2117330">store</span> <span m="2118390">the</span> <span m="2118735">old</span>
  <span m="2119080">vect.</span> <span m="2121130">So</span> <span m="2121300">I</span>
  <span m="2121390">need</span> <span m="2121620">to</span> <span m="2121720">do</span>
  <span m="2123590">vect</span> <span m="2126710">of</span> <span m="2127210">0.</span>
  <span m="2128210">Let</span> <span m="2128940">me</span> <span m="2129070">actually</span>
  <span m="2129335">do</span> <span m="2129600">this.</span> <span m="2130850">Let</span>
  <span m="2131070">me</span> <span m="2131210">actually</span> <span m="2131630">call</span>
  <span m="2131930">this</span> <span m="2132170">vect</span> <span m="2132850">00</span>
  <span m="2134093">as</span> <span m="2135000">the</span> <span m="2135120">previous</span>
  <span m="2135540">time step.</span> <span m="2136830">And</span> <span m="2137180">the</span>
  <span m="2137260">vect</span> <span m="2138790">0</span> <span m="2139420">as--</span>
  <span m="2141150">so,</span> <span m="2141810">at</span> <span m="2142000">any</span>
  <span m="2142270">point,</span> <span m="2142930">that</span> <span m="2143340">00?</span>
  <span m="2146190">Let</span> <span m="2146360">me</span> <span m="2146450">call</span>
  <span m="2146650">it</span> <span m="2146800">k</span> <span m="2147570">minus</span>
  <span m="2148890">1.</span> <span m="2149890">OK.</span> <span m="2150610">vect</span>
  <span m="2150930">0.</span> <span m="2151020">Let</span> <span m="2151110">me</span>
  <span m="2151220">call</span> <span m="2151570">it</span> <span m="2151700">vect</span>
  <span m="2152070">k.</span></p><p><span m="2162290">All</span> <span m="2162500">right.</span>
  <span m="2163530">So</span> <span m="2163760">this</span> <span m="2164040">is</span>
  <span m="2164700">one</span> <span m="2165120">step</span> <span m="2165370">of</span>
  <span m="2165640">forward</span> <span m="2165740">Euler</span> <span m="2166370">going</span>
  <span m="2166530">from</span> <span m="2167350">k</span> <span m="2167540">minus</span>
  <span m="2167900">1</span> <span m="2168240">to</span> <span m="2168680">k.</span>
  <span m="2170410">All</span> <span m="2170590">right.</span> <span m="2171220">Now</span>
  <span m="2172490">in</span> <span m="2173030">midpoint,</span> <span m="2174690">where</span>
  <span m="2175160">do</span> <span m="2175330">I</span> <span m="2175420">compute</span>
  <span m="2175890">the</span> <span m="2175960">derivative?</span> <span m="2178456">x</span>
  <span m="2178930">time step</span> <span m="2179210">k?</span> <span m="2179490">Or</span>
  <span m="2179980">k</span> <span m="2180250">minus</span> <span m="2180370">1?</span>
  <span m="2183748">K,</span> <span m="2184231">right.</span> <span m="2185200">So</span>
  <span m="2185370">that''s</span> <span m="2185690">k.</span> <span m="2187090">So</span>
  <span m="2187310">this</span> <span m="2187610">d vect/dt</span> <span m="2188650">is</span>
  <span m="2188940">the</span> <span m="2189020">time</span> <span m="2189400">derivative</span>
  <span m="2190600">at</span> <span m="2190690">step</span> <span m="2190870">k.</span>
  <span m="2192710">Now</span> <span m="2193260">my</span> <span m="2193470">vect</span>
  <span m="2193910">is</span> <span m="2194280">equal</span> <span m="2194710">to</span>
  <span m="2195960">vect</span> <span m="2197030">k</span> <span m="2197620">minus</span>
  <span m="2198190">1</span> <span m="2200770">plus</span> <span m="2201210">2</span>
  <span m="2201460">times</span> <span m="2201750">delta</span> <span m="2201930">t</span>
  <span m="2202100">times</span> <span m="2203822">F</span> <span m="2204296">of v.</span>
  <span m="2205720">Right?</span></p><p><span m="2207590">This</span> <span m="2207790">is</span>
  <span m="2207940">because</span> <span m="2208620">in</span> <span m="2209280">midpoint--</span>
  <span m="2213680">so</span> <span m="2213940">forward</span> <span m="2214340">Euler</span>
  <span m="2215530">is</span> <span m="2215980">V</span> <span m="2216430">at</span>
  <span m="2216800">k</span> <span m="2217260">plus</span> <span m="2217720">1</span>
  <span m="2218080">equal</span> <span m="2218490">to</span> <span m="2218650">Vk</span>
  <span m="2219860">plus</span> <span m="2220280">f of</span> <span m="2220690">Vk.</span>
  <span m="2222540">Midpoint,</span> <span m="2224250">we</span> <span m="2224450">have</span>
  <span m="2225240">Vk</span> <span m="2225710">plus</span> <span m="2226070">1</span>
  <span m="2226520">equal</span> <span m="2226970">to</span> <span m="2227150">be</span>
  <span m="2227490">Vk</span> <span m="2227790">minus</span> <span m="2228250">1</span>
  <span m="2228490">plus</span> <span m="2229220">2.</span> <span m="2230110">There</span>
  <span m="2230350">is</span> <span m="2230470">a</span> <span m="2230530">delta</span>
  <span m="2230850">t</span> <span m="2231090">here.</span> <span m="2231410">2</span>
  <span m="2231730">times</span> <span m="2232520">f</span> <span m="2232880">Vk</span>
  <span m="2234300">times</span> <span m="2234430">delta</span> <span m="2234590">t.</span>
  <span m="2234800">Right?</span> <span m="2235260">This</span> <span m="2235560">is</span>
  <span m="2235710">what</span> <span m="2235920">we</span> <span m="2236080">are</span>
  <span m="2236890">implementing</span> <span m="2237530">right</span> <span m="2237730">now.</span></p><p><span
  m="2240280">All right.</span> <span m="2241100">So</span> <span m="2241380">we</span>
  <span m="2241660">have</span> <span m="2243210">this.</span> <span m="2244770">And</span>
  <span m="2245430">everything</span> <span m="2245850">else</span> <span m="2246220">I</span>
  <span m="2246330">think</span> <span m="2246990">is</span> <span m="2248060">same.</span></p><p><span
  m="2251340">AUDIENCE: [INAUDIBLE].</span></p><p><span m="2257060">QIQI WANG: Right.</span>
  <span m="2257560">Then</span> <span m="2257830">I</span> <span m="2257970">need</span>
  <span m="2258210">to</span> <span m="2258360">also</span> <span m="2258830">update.</span>
  <span m="2259700">Because</span> <span m="2260160">I</span> <span m="2260280">need</span>
  <span m="2260530">to</span> <span m="2260670">set</span> <span m="2261550">vect</span>
  <span m="2262530">of</span> <span m="2262930">k</span> <span m="2263360">equal</span>
  <span m="2263710">to</span> <span m="2263870">vect.</span> <span m="2264820">Right?</span>
  <span m="2266210">And</span> <span m="2267370">before</span> <span m="2267560">I</span>
  <span m="2267650">do</span> <span m="2267880">that,</span> <span m="2268180">I</span>
  <span m="2268280">need</span> <span m="2268510">to</span> <span m="2268810">have</span>
  <span m="2269160">vect</span> <span m="2270640">k</span> <span m="2270750">minus</span>
  <span m="2271380">1</span> <span m="2272475">is</span> <span m="2272960">equal</span>
  <span m="2273500">to</span> <span m="2273710">vect</span> <span m="2274890">k.</span>
  <span m="2276714">Right?</span> <span m="2279650">So</span> <span m="2280495">I''m</span>
  <span m="2280950">done.</span> <span m="2283225">Should we</span> <span m="2283680">run
  this?</span></p><p><span m="2286790">Is</span> <span m="2287030">it</span> <span
  m="2287100">clear</span> <span m="2287430">like</span> <span m="2287740">if</span>
  <span m="2288270">when</span> <span m="2288570">you</span> <span m="2289050">guys</span>
  <span m="2289300">have</span> <span m="2289520">fourth order</span> <span m="2289930">implemented</span>
  <span m="2290340">on</span> <span m="2290750">your</span> <span m="2291160">computer</span>
  <span m="2291570">how to</span> <span m="2291880">change</span> <span m="2292240">your</span>
  <span m="2292430">implementation</span> <span m="2293080">into</span> <span m="2293310">midpoint?</span>
  <span m="2295680">Good?</span> <span m="2297010">Let''s</span> <span m="2297300">run</span>
  <span m="2297530">it.</span> <span m="2303160">Let</span> <span m="2303300">me</span>
  <span m="2303460">close</span> <span m="2303907">out.</span> <span m="2307036">Now
  I''m going to</span> <span m="2307490">run</span> <span m="2307830">it.</span> <span
  m="2314862">Is it</span> <span m="2315350">the same</span> <span m="2315838">as</span>
  <span m="2316326">before?</span> <span m="2318787">No.</span></p><p><span m="2319765">AUDIENCE:
  [INAUDIBLE].</span></p><p><span m="2323680">QIQI WANG: Oh.</span></p><p><span m="2324547">AUDIENCE:
  [INAUDIBLE].</span></p><p><span m="2327032">QIQI WANG: Oh. Is this</span> <span
  m="2327530">something</span> <span m="2327920">to--</span></p><p><span m="2328220">AUDIENCE:
  Yeah.</span> <span m="2328570">[INAUDIBLE].</span></p><p><span m="2329270">QIQI
  WANG: You mean</span> <span m="2329390">remotely?</span></p><p><span m="2330120">AUDIENCE:
  Yeah.</span> <span m="2330604">[INAUDIBLE].</span></p><p><span m="2331088">[LAUGHTER]</span></p><p><span
  m="2336420">QIQI WANG: OK.</span> <span m="2336950">OK.</span> <span m="2337230">What</span>
  <span m="2337440">did</span> <span m="2337590">you</span> <span m="2337680">do?</span></p><p><span
  m="2339680">AUDIENCE: I didn''t</span> <span m="2340180">[INAUDIBLE].</span></p><p><span
  m="2343090">QIQI WANG: Oh.</span> <span m="2343500">OK.</span> <span m="2344660">OK.</span>
  <span m="2345180">So</span> <span m="2345380">let</span> <span m="2345560">me</span>
  <span m="2345680">just</span> <span m="2346210">make</span> <span m="2346540">it</span>
  <span m="2349140">10</span> <span m="2349380">more</span> <span m="2349760">time
  steps.</span></p><p><span m="2351074">AUDIENCE: [INAUDIBLE].</span></p><p><span
  m="2353270">QIQI WANG: Oh,</span> <span m="2353490">yeah.</span> <span m="2353810">Right.</span></p><p><span
  m="2358810">AUDIENCE: [INAUDIBLE].</span></p><p><span m="2363850">QIQI WANG: Yes.</span>
  <span m="2367920">OK.</span> <span m="2368640">Let</span> <span m="2368800">me</span>
  <span m="2368930">run</span> <span m="2369210">it.</span></p><p><span m="2372910">AUDIENCE:
  [INAUDIBLE].</span></p><p>&nbsp;</p><p><span m="2378910">QIQI WANG: Let</span> <span
  m="2380190">me--</span> <span m="2380900">I</span> <span m="2381030">think</span>
  <span m="2381260">this</span> <span m="2381460">is</span> <span m="2381660">too</span>
  <span m="2382810">much.</span> <span m="2383180">Let</span> <span m="2383350">me</span>
  <span m="2383490">change</span> <span m="2383912">it</span> <span m="2385600">to--</span>
  <span m="2388065">I think I</span> <span m="2388520">just</span> <span m="2389676">do</span>
  <span m="2390080">this</span> <span m="2390470">much.</span> <span m="2390780">It</span>
  <span m="2391090">may be</span> <span m="2391365">enough.</span> <span m="2392120">Let</span>
  <span m="2392300">me</span> <span m="2392490">see</span> <span m="2392670">it.</span>
  <span m="2393700">And</span> <span m="2393950">when</span> <span m="2394100">you</span>
  <span m="2394210">plot</span> <span m="2394560">it,</span> <span m="2394910">let</span>
  <span m="2395070">me</span> <span m="2395180">make</span> <span m="2395440">sure</span>
  <span m="2395640">to</span> <span m="2395780">do</span> <span m="2396010">x</span>
  <span m="2396438">is</span> <span m="2396866">equal.</span> <span m="2398580">Do</span>
  <span m="2398700">you</span> <span m="2398760">know</span> <span m="2398940">what</span>
  <span m="2399070">this</span> <span m="2399230">means?</span> <span m="2399970">This</span>
  <span m="2400160">just</span> <span m="2400370">means that the</span> <span m="2400630">x-axis</span>
  <span m="2401370">and</span> <span m="2401530">y-axis</span> <span m="2402120">are</span>
  <span m="2402220">going</span> <span m="2402340">to</span> <span m="2402400">be</span>
  <span m="2403127">on</span> <span m="2403604">scale.</span> <span m="2404560">Right?</span>
  <span m="2405430">OK.</span> <span m="2406500">That''s good.</span> <span m="2407340">So
  midpoint</span> <span m="2407570">also</span> <span m="2408210">works.</span></p><p><span
  m="2410360">So</span> <span m="2411920">first</span> <span m="2412070">of</span>
  <span m="2412220">all,</span> <span m="2414400">I</span> <span m="2414690">want</span>
  <span m="2414900">to</span> <span m="2415070">use</span> <span m="2415180">the</span>
  <span m="2415280">remaining</span> <span m="2415820">few</span> <span m="2416020">minutes,</span>
  <span m="2416440">let''s</span> <span m="2416970">try</span> <span m="2417090">to</span>
  <span m="2417360">implement</span> <span m="2417970">the</span> <span m="2418100">most</span>
  <span m="2418540">accurate</span> <span m="2419400">scheme</span> <span m="2419700">we</span>
  <span m="2419900">got</span> <span m="2421290">to</span> <span m="2421450">see--</span>
  <span m="2422750">we</span> <span m="2422990">already</span> <span m="2423330">have
  a</span> <span m="2423810">two-step</span> <span m="2424350">scheme.</span> <span
  m="2424830">Right?</span> <span m="2426100">And</span> <span m="2426780">it</span>
  <span m="2426930">should</span> <span m="2427090">be</span> <span m="2427240">pretty</span>
  <span m="2427570">easy</span> <span m="2427950">to</span> <span m="2428090">change</span>
  <span m="2428590">to</span> <span m="2429380">this</span> <span m="2429650">scheme</span>
  <span m="2430480">we</span> <span m="2430660">have</span> <span m="2430860">over</span>
  <span m="2431040">here.</span></p><p><span m="2433330">So</span> <span m="2435080">instead</span>
  <span m="2435610">of</span> <span m="2435970">here,</span> <span m="2438320">so</span>
  <span m="2438590">we</span> <span m="2438810">have</span> <span m="2439010">a</span>
  <span m="2439090">d vect</span> <span m="2439570">dt</span> <span m="2440050">at</span>
  <span m="2440520">step</span> <span m="2440850">k,</span> <span m="2441710">right?</span>
  <span m="2443100">We</span> <span m="2443290">also</span> <span m="2443800">need</span>
  <span m="2444763">a d</span> <span m="2445226">vect</span> <span m="2445690">dt</span>
  <span m="2445930">at</span> <span m="2446345">step k</span> <span m="2446760">minus</span>
  <span m="2447050">1.</span> <span m="2447850">That</span> <span m="2448980">is</span>
  <span m="2449090">just</span> <span m="2449290">called</span> <span m="2449640">in
  the</span> <span m="2449740">same</span> <span m="2450040">function</span> <span
  m="2451330">at</span> <span m="2452180">step</span> <span m="2452460">k minus</span>
  <span m="2452760">1.</span> <span m="2453690">Right?</span> <span m="2456130">You</span>
  <span m="2456340">see</span> <span m="2456410">what</span> <span m="2456570">I''m</span>
  <span m="2456690">doing?</span> <span m="2457110">I''m</span> <span m="2457190">computing</span>
  <span m="2458080">two time</span> <span m="2458960">derivatives.</span></p><p><span
  m="2459820">Now</span> <span m="2460130">in</span> <span m="2460370">this</span>
  <span m="2460810">update,</span> <span m="2462490">I</span> <span m="2462850">have</span>
  <span m="2463570">a</span> <span m="2463680">minus</span> <span m="2464080">4</span>
  <span m="2464810">times</span> <span m="2467090">Vk</span> <span m="2467470">and</span>
  <span m="2467730">the</span> <span m="2467800">plus</span> <span m="2468190">5</span>
  <span m="2468485">times</span> <span m="2468780">Vk</span> <span m="2470940">minus</span>
  <span m="2471300">1</span> <span m="2473350">plus</span> <span m="2473700">5</span>
  <span m="2474140">times</span> <span m="2474520">this,</span> <span m="2475130">right?</span>
  <span m="2477780">OK.</span> <span m="2478280">And</span> <span m="2480760">then</span>
  <span m="2481010">the</span> <span m="2481250">second</span> <span m="2481660">line</span>
  <span m="2481990">is</span> <span m="2482640">plus</span> <span m="2483030">4</span>
  <span m="2483340">delta</span> <span m="2483830">t</span> <span m="2484990">f</span>
  <span m="2485420">of</span> <span m="2485620">Vk</span> <span m="2486450">plus</span>
  <span m="2486730">2</span> <span m="2486940">delta</span> <span m="2487100">t</span>
  <span m="2487350">f of</span> <span m="2487790">Vk</span> <span m="2488170">minus</span>
  <span m="2488450">1.</span> <span m="2490590">So</span> <span m="2490810">this</span>
  <span m="2491030">is</span> <span m="2491170">4</span> <span m="2495175">plus</span>
  <span m="2495650">2</span> <span m="2496035">times</span> <span m="2496420">dt</span>
  <span m="2496905">times</span> <span m="2497390">d vect</span> <span m="2497875">dt</span>
  <span m="2499330">k</span> <span m="2499820">minus</span> <span m="2500830">one.</span>
  <span m="2502550">Right?</span></p><p><span m="2505600">So</span> <span m="2505950">that</span>
  <span m="2506400">completes</span> <span m="2507030">our</span> <span m="2508550">change</span>
  <span m="2509130">from</span> <span m="2509670">midpoint</span> <span m="2510830">to</span>
  <span m="2511140">an</span> <span m="2511240">even</span> <span m="2511620">more</span>
  <span m="2511890">accurate</span> <span m="2512372">two-step</span> <span m="2513336">scheme.</span>
  <span m="2515270">And</span> <span m="2515510">by</span> <span m="2515670">more</span>
  <span m="2515920">accurate,</span> <span m="2516330">I</span> <span m="2516410">mean</span>
  <span m="2517100">global</span> <span m="2517405">or local</span> <span m="2517710">order</span>
  <span m="2518210">of</span> <span m="2518310">accuracy?</span></p><p><span m="2520910">AUDIENCE:
  Local.</span></p><p><span m="2521410">QIQI WANG: Local,</span> <span m="2521970">right?</span>
  <span m="2522200">Because</span> <span m="2522690">we</span> <span m="2522900">did</span>
  <span m="2523180">this</span> <span m="2524380">using</span> <span m="2524870">Taylor</span>
  <span m="2525170">series</span> <span m="2525490">analysis.</span> <span m="2526950">So</span>
  <span m="2526990">let''s</span> <span m="2527490">see</span> <span m="2527800">if</span>
  <span m="2527960">it</span> <span m="2528080">translates</span> <span m="2528680">into</span>
  <span m="2528940">global</span> <span m="2529450">order</span> <span m="2529590">of</span>
  <span m="2529740">accuracy.</span> <span m="2531490">Let</span> <span m="2531630">me</span>
  <span m="2531740">click,</span> <span m="2533350">let me</span> <span m="2533620">close
  this</span> <span m="2533920">first.</span> <span m="2535974">And</span> <span m="2536430">let''s</span>
  <span m="2536690">run</span> <span m="2536990">it.</span></p><p><span m="2542547">You
  see</span> <span m="2543034">this?</span> <span m="2545469">You</span> <span m="2545956">see</span>
  <span m="2546443">this?</span> <span m="2547904">What</span> <span m="2548391">does
  this mean,</span> <span m="2548878">10</span> <span m="2549365">to the</span> <span
  m="2549852">162?</span> <span m="2551800">That''s</span> <span m="2552040">where</span>
  <span m="2552240">my</span> <span m="2553056">cannonball</span> <span m="2553552">bounced.</span>
  <span m="2558016">What</span> <span m="2558520">happens?</span> <span m="2563440">What</span>
  <span m="2563610">happens?</span> <span m="2567010">Let''s</span> <span m="2567280">look</span>
  <span m="2567510">at</span> <span m="2567660">our</span> <span m="2567870">scheme</span>
  <span m="2568710">solution</span> <span m="2569710">not</span> <span m="2570080">for</span>
  <span m="2570290">this</span> <span m="2570500">many</span> <span m="2570760">time
  steps.</span> <span m="2571430">But</span> <span m="2572020">let''s</span> <span
  m="2572410">just</span> <span m="2572640">go</span> <span m="2572770">19</span>
  <span m="2573190">time steps.</span> <span m="2574250">And</span> <span m="2574450">let''s</span>
  <span m="2575590">put</span> <span m="2575750">a</span> <span m="2575900">circle</span>
  <span m="2576260">at</span> <span m="2576450">every</span> <span m="2576920">time
  step</span> <span m="2577400">to</span> <span m="2577500">see</span> <span m="2577710">what</span>
  <span m="2577910">actually</span> <span m="2578340">happens.</span> <span m="2581400">OK.</span></p><p><span
  m="2586040">After</span> <span m="2586490">just</span> <span m="2587220">19</span>
  <span m="2587570">time steps,</span> <span m="2588260">we''ve</span> <span m="2588510">got</span>
  <span m="2589420">10</span> <span m="2589900">to</span> <span m="2590030">the</span>
  <span m="2590170">22.</span> <span m="2590790">That''s</span> <span m="2591020">amazing.</span>
  <span m="2593290">And</span> <span m="2595320">we</span> <span m="2595470">basically</span>
  <span m="2596770">just</span> <span m="2597440">shoot</span> <span m="2597860">out</span>
  <span m="2598280">and</span> <span m="2598700">diverge,</span> <span m="2599120">right?</span>
  <span m="2600500">So</span> <span m="2601240">why</span> <span m="2602080">do</span>
  <span m="2602200">you</span> <span m="2602310">think</span> <span m="2602520">that</span>
  <span m="2602680">is</span> <span m="2602800">the</span> <span m="2602910">case?</span>
  <span m="2603210">Do</span> <span m="2603320">we</span> <span m="2603530">have</span>
  <span m="2603820">any</span> <span m="2604210">global</span> <span m="2604630">order</span>
  <span m="2604870">of</span> <span m="2605000">accuracy?</span> <span m="2608150">I</span>
  <span m="2608230">mean,</span> <span m="2608400">we</span> <span m="2608870">can</span>
  <span m="2609080">do</span> <span m="2609320">that</span> <span m="2609520">by</span>
  <span m="2610240">changing</span> <span m="2610880">the</span> <span m="2611010">time
  steps</span> <span m="2611360">to</span> <span m="2611440">be</span> <span m="2612110">even</span>
  <span m="2612550">smaller.</span></p><p><span m="2613940">And</span> <span m="2614250">we</span>
  <span m="2614390">would</span> <span m="2614570">change--</span> <span m="2614960">don''t</span>
  <span m="2615446">change</span> <span m="2615932">it to</span> <span m="2616420">this.</span>
  <span m="2616530">Let me</span> <span m="2616920">change</span> <span m="2617270">it
  to</span> <span m="2618150">twice</span> <span m="2618580">smaller.</span> <span
  m="2619450">And</span> <span m="2620630">the</span> <span m="2620800">time steps</span>
  <span m="2621550">to</span> <span m="2622425">also</span> <span m="2623270">twice</span>
  <span m="2623990">as</span> <span m="2624110">much.</span> <span m="2624620">That</span>
  <span m="2624830">is</span> <span m="2624960">a</span> <span m="2625040">good</span>
  <span m="2625250">way</span> <span m="2625420">of</span> <span m="2625640">assessing</span>
  <span m="2626130">the</span> <span m="2626220">global</span> <span m="2626600">order</span>
  <span m="2626770">of</span> <span m="2626900">accuracy,</span> <span m="2627440">right?</span>
  <span m="2628270">It</span> <span m="2628500">will</span> <span m="2628950">decrease</span>
  <span m="2629390">the</span> <span m="2629520">time step</span> <span m="2629980">by</span>
  <span m="2630150">a</span> <span m="2630200">factor</span> <span m="2630460">of</span>
  <span m="2630580">two,</span> <span m="2631580">increase</span> <span m="2632140">the</span>
  <span m="2632260">number</span> <span m="2632540">of</span> <span m="2632640">time
  steps</span> <span m="2632940">by</span> <span m="2633000">a</span> <span m="2633180">factor</span>
  <span m="2633550">of</span> <span m="2633920">two,</span> <span m="2634240">right?</span>
  <span m="2635226">To</span> <span m="2635720">see if</span> <span m="2636050">the</span>
  <span m="2636310">solution</span> <span m="2636710">gets</span> <span m="2637195">more</span>
  <span m="2637680">accurate.</span></p><p><span m="2639880">OK.</span> <span m="2641060">It
  gets</span> <span m="2641420">wilder.</span> <span m="2642800">Instead</span> <span
  m="2642960">of</span> <span m="2643140">10</span> <span m="2643220">to the 100</span>
  <span m="2643670">or something,</span> <span m="2644120">it''s 10</span> <span m="2644570">to
  the</span> <span m="2645020">200</span> <span m="2645240">and</span> <span m="2645620">something.</span>
  <span m="2646760">All right.</span> <span m="2647972">So</span> <span m="2648450">something</span>
  <span m="2648760">is</span> <span m="2648900">wrong.</span> <span m="2650400">What</span>
  <span m="2650590">is</span> <span m="2650750">wrong?</span> <span m="2651000">Can</span>
  <span m="2651180">somebody</span> <span m="2651520">just</span> <span m="2652020">shout</span>
  <span m="2652320">out?</span> <span m="2656512">What</span> <span m="2657001">we</span>
  <span m="2657490">reviewed in</span> <span m="2657970">the</span> <span m="2658040">beginning?</span>
  <span m="2662620">Our</span> <span m="2662900">scheme</span> <span m="2663260">is</span>
  <span m="2663470">not</span> <span m="2663730">zero</span> <span m="2664500">stable.</span>
  <span m="2665490">It</span> <span m="2665800">can''t</span> <span m="2666190">even</span>
  <span m="2666620">solve</span> <span m="2667520">this</span> <span m="2668060">differential</span>
  <span m="2668650">equation.</span> <span m="2671290">Let</span> <span m="2671440">me</span>
  <span m="2671550">repeat.</span> <span m="2672210">The</span> <span m="2673260">most</span>
  <span m="2674110">accurate</span> <span m="2675030">two-step</span> <span m="2675710">scheme</span>
  <span m="2676680">can''t</span> <span m="2677030">even</span> <span m="2677360">solve</span>
  <span m="2677590">du/dt</span> <span m="2678210">equal</span> <span m="2678480">to</span>
  <span m="2678800">0.</span></p><p><span m="2681160">You</span> <span m="2681310">want</span>
  <span m="2681490">me</span> <span m="2681610">to</span> <span m="2681720">prove</span>
  <span m="2682060">that?</span> <span m="2682660">I''m</span> <span m="2682910">going</span>
  <span m="2683060">to</span> <span m="2683140">prove</span> <span m="2683460">that</span>
  <span m="2684190">analytically.</span> <span m="2686110">OK.</span> <span m="2686810">We</span>
  <span m="2687060">have</span> <span m="2687680">the</span> <span m="2687780">following</span>
  <span m="2688440">scheme.</span> <span m="2688740">I''ll</span> <span m="2689160">see</span>
  <span m="2689280">if</span> <span m="2689390">I</span> <span m="2689490">can</span>
  <span m="2689690">do</span> <span m="2689860">it</span> <span m="2689960">in</span>
  <span m="2690100">five</span> <span m="2690360">minutes.</span> <span m="2691770">It''s</span>
  <span m="2692030">equal</span> <span m="2692330">to</span> <span m="2692580">minus</span>
  <span m="2693010">4</span> <span m="2693620">Vk</span> <span m="2694522">plus</span>
  <span m="2694973">5</span> <span m="2695424">Vk</span> <span m="2696330">minus</span>
  <span m="2696700">1.</span> <span m="2697380">And</span> <span m="2697550">the</span>
  <span m="2697670">rest</span> <span m="2697960">of</span> <span m="2698100">them</span>
  <span m="2698410">on the</span> <span m="2698620">right hand</span> <span m="2698970">side</span>
  <span m="2699580">are</span> <span m="2699860">f of</span> <span m="2700140">V,</span>
  <span m="2700480">right?</span> <span m="2701470">If</span> <span m="2701740">I</span>
  <span m="2701900">solve</span> <span m="2702210">the</span> <span m="2702300">differential</span>
  <span m="2702670">equation</span> <span m="2703573">du/dt</span> <span m="2704460">equal</span>
  <span m="2704980">to</span> <span m="2705480">f</span> <span m="2705790">of</span>
  <span m="2706130">U</span> <span m="2706580">equal</span> <span m="2706995">to 0,</span>
  <span m="2707410">then</span> <span m="2707680">f</span> <span m="2707870">of</span>
  <span m="2708010">U</span> <span m="2708160">is</span> <span m="2708360">equal</span>
  <span m="2708650">to 0.</span> <span m="2709060">I</span> <span m="2709230">have</span>
  <span m="2709470">nothing</span> <span m="2710360">after</span> <span m="2710650">this.</span>
  <span m="2711570">And</span> <span m="2711910">this</span> <span m="2712390">is</span>
  <span m="2712750">my</span> <span m="2713200">scheme.</span> <span m="2713820">I</span>
  <span m="2713990">want</span> <span m="2714320">this</span> <span m="2714720">scheme</span>
  <span m="2715460">to</span> <span m="2715630">reproduce</span> <span m="2716340">a</span>
  <span m="2716440">constant</span> <span m="2717040">solution.</span> <span m="2718610">Right?</span></p><p><span
  m="2719650">The</span> <span m="2719780">question</span> <span m="2720140">is</span>
  <span m="2720560">why</span> <span m="2720820">can</span> <span m="2721540">this</span>
  <span m="2721900">scheme</span> <span m="2722360">not</span> <span m="2723060">reproduce</span>
  <span m="2723670">a</span> <span m="2723780">constant</span> <span m="2724330">solution?</span>
  <span m="2728910">The</span> <span m="2729070">answer</span> <span m="2729340">is</span>
  <span m="2729500">like</span> <span m="2729900">this.</span> <span m="2730370">The</span>
  <span m="2730570">answer</span> <span m="2730800">is</span> <span m="2730960">because</span>
  <span m="2731470">this</span> <span m="2731850">scheme</span> <span m="2732400">is</span>
  <span m="2732860">going</span> <span m="2733020">to</span> <span m="2733190">allow</span>
  <span m="2734100">an</span> <span m="2734360">exponentially</span> <span m="2735230">diverging</span>
  <span m="2735890">solution.</span> <span m="2737530">OK.</span> <span m="2738200">If</span>
  <span m="2738510">I</span> <span m="2738670">have</span> <span m="2738850">a</span>
  <span m="2738930">solution</span> <span m="2740050">Vk</span> <span m="2740930">is</span>
  <span m="2741270">equal</span> <span m="2741590">to</span> <span m="2741810">V0</span>
  <span m="2743040">times</span> <span m="2743804">a</span> <span m="2744186">zeta--</span>
  <span m="2744570">let</span> <span m="2744790">me</span> <span m="2744890">just</span>
  <span m="2745300">write</span> <span m="2745550">out</span> <span m="2745760">z</span>
  <span m="2746130">because</span> <span m="2746575">I can''t</span> <span m="2747020">write</span>
  <span m="2747220">zeta--</span> <span m="2748426">times</span> <span m="2748830">Z
  to</span> <span m="2748910">the</span> <span m="2749010">k.</span> <span m="2751110">I''m</span>
  <span m="2751260">going</span> <span m="2751380">to</span> <span m="2751440">see--</span>
  <span m="2752310">if</span> <span m="2753290">I</span> <span m="2753460">plug</span>
  <span m="2754010">into</span> <span m="2754290">this</span> <span m="2754510">equation</span>
  <span m="2755170">and</span> <span m="2755720">the</span> <span m="2755960">equation</span>
  <span m="2756280">is</span> <span m="2756350">satisfied</span> <span m="2757060">and</span>
  <span m="2757350">my V</span> <span m="2757570">is</span> <span m="2758040">something</span>
  <span m="2758440">greater</span> <span m="2758900">than</span> <span m="2759110">1--</span>
  <span m="2760270">then</span> <span m="2760830">what</span> <span m="2761020">does
  it</span> <span m="2761150">mean?</span></p><p><span m="2762300">It</span> <span
  m="2762660">means</span> <span m="2762840">I</span> <span m="2763030">have</span>
  <span m="2763320">a</span> <span m="2763390">very,</span> <span m="2763990">very</span>
  <span m="2764250">small</span> <span m="2764810">V0,</span> <span m="2765500">even</span>
  <span m="2765810">if</span> <span m="2766020">I</span> <span m="2766190">have</span>
  <span m="2766530">an</span> <span m="2766610">extremely</span> <span m="2767080">small</span>
  <span m="2767350">V0,</span> <span m="2769380">I</span> <span m="2769520">can</span>
  <span m="2769730">end</span> <span m="2770070">up</span> <span m="2770940">having</span>
  <span m="2771240">a</span> <span m="2771300">huge</span> <span m="2771540">solution</span>
  <span m="2772030">after</span> <span m="2772350">sufficiently</span> <span m="2772980">many</span>
  <span m="2773240">time steps.</span> <span m="2774490">Right?</span> <span m="2775370">And</span>
  <span m="2775550">when</span> <span m="2775740">I</span> <span m="2775820">plot
  this thing,</span> <span m="2776590">I''m</span> <span m="2776800">going</span>
  <span m="2776940">to</span> <span m="2777030">have</span> <span m="2778160">a</span>
  <span m="2778490">V of</span> <span m="2778730">k</span> <span m="2779030">plus</span>
  <span m="2779300">1</span> <span m="2779570">is</span> <span m="2779770">V0</span>
  <span m="2780790">times</span> <span m="2781050">V</span> <span m="2781310">to</span>
  <span m="2781420">the</span> <span m="2781510">k</span> <span m="2781710">plus</span>
  <span m="2782000">1</span> <span m="2782310">is</span> <span m="2782570">equal</span>
  <span m="2782860">to</span> <span m="2782950">minus</span> <span m="2783380">4</span>
  <span m="2784180">times</span> <span m="2784580">Vk</span> <span m="2785670">V0</span>
  <span m="2786100">times</span> <span m="2786430">V</span> <span m="2786640">to</span>
  <span m="2786720">the</span> <span m="2786810">k.</span> <span m="2788180">And</span>
  <span m="2789010">sorry,</span> <span m="2789430">this</span> <span m="2789640">is</span>
  <span m="2789870">k</span> <span m="2790030">minus</span> <span m="2790340">1.</span>
  <span m="2792330">Right?</span> <span m="2792610">This</span> <span m="2792780">is</span>
  <span m="2792890">my</span> <span m="2793040">scheme.</span> <span m="2794360">Times</span>
  <span m="2795030">V0</span> <span m="2795630">V</span> <span m="2795860">to</span>
  <span m="2795950">the</span> <span m="2796040">k</span> <span m="2796320">minus</span>
  <span m="2796660">1.</span></p><p><span m="2798830">I</span> <span m="2798950">cancel</span>
  <span m="2799410">this.</span> <span m="2800140">Cancel</span> <span m="2800530">this.</span>
  <span m="2800870">Cancel</span> <span m="2801330">the</span> <span m="2801410">V0.</span>
  <span m="2801950">Because</span> <span m="2802860">they</span> <span m="2803120">are</span>
  <span m="2803230">the</span> <span m="2803300">same</span> <span m="2803570">on</span>
  <span m="2803740">both</span> <span m="2803970">sides.</span> <span m="2805900">And</span>
  <span m="2806480">though</span> <span m="2807020">all</span> <span m="2807340">of</span>
  <span m="2807470">these</span> <span m="2808010">have</span> <span m="2808400">V
  to</span> <span m="2808610">the</span> <span m="2808700">k</span> <span m="2808830">minus</span>
  <span m="2809430">1</span> <span m="2809680">at</span> <span m="2809820">least--</span>
  <span m="2810330">some</span> <span m="2810560">of</span> <span m="2810700">them</span>
  <span m="2810870">are k,</span> <span m="2811290">some</span> <span m="2811500">of</span>
  <span m="2812100">them</span> <span m="2812290">are</span> <span m="2812630">k</span>
  <span m="2812960">plus</span> <span m="2813315">1.</span> <span m="2813670">So</span>
  <span m="2813850">I</span> <span m="2813970">remove</span> <span m="2814460">that</span>
  <span m="2814680">vector.</span> <span m="2815060">I</span> <span m="2815250">have</span>
  <span m="2815520">V</span> <span m="2815690">squared</span> <span m="2816230">is</span>
  <span m="2816510">equal</span> <span m="2816790">to</span> <span m="2816870">minus</span>
  <span m="2817280">4</span> <span m="2817635">Z</span> <span m="2818910">plus</span>
  <span m="2819170">5.</span> <span m="2820630">We</span> <span m="2820740">get</span>
  <span m="2820890">a</span> <span m="2820930">quadratic</span> <span m="2821580">equation.</span>
  <span m="2823460">Right?</span></p><p><span m="2824510">This</span> <span m="2825120">quadratic</span>
  <span m="2825420">equation</span> <span m="2825840">can</span> <span m="2825970">have</span>
  <span m="2826290">real</span> <span m="2826650">or</span> <span m="2826830">complex</span>
  <span m="2827930">solutions.</span> <span m="2828400">But</span> <span m="2828870">let''s</span>
  <span m="2829410">see</span> <span m="2830020">what</span> <span m="2830460">it</span>
  <span m="2830550">has.</span> <span m="2831860">So</span> <span m="2833530">a</span>
  <span m="2834002">is</span> <span m="2834474">equal</span> <span m="2834631">to</span>
  <span m="2834788">1.</span> <span m="2834946">b</span> <span m="2835420">is</span>
  <span m="2835560">equal</span> <span m="2836010">to</span> <span m="2836470">4.</span>
  <span m="2836520">c</span> <span m="2836890">is equal</span> <span m="2837140">to</span>
  <span m="2837470">minus</span> <span m="2837520">5.</span> <span m="2838100">So</span>
  <span m="2838270">we</span> <span m="2838400">get</span> <span m="2839270">a</span>
  <span m="2839580">minus</span> <span m="2839946">b</span> <span m="2840680">plus</span>
  <span m="2841220">minus</span> <span m="2842240">b</span> <span m="2842510">squared,</span>
  <span m="2842900">which</span> <span m="2843080">is</span> <span m="2843160">16.</span>
  <span m="2844970">Minus</span> <span m="2845440">4ac,</span> <span m="2846290">which</span>
  <span m="2846490">is</span> <span m="2846650">plus</span> <span m="2847730">20.</span>
  <span m="2850068">All</span> <span m="2850550">right?</span> <span m="2851200">So</span>
  <span m="2851400">that''s</span> <span m="2852130">my</span> <span m="2852310">two</span>
  <span m="2852550">solutions.</span></p><p><span m="2854050">And</span> <span m="2854170">I</span>
  <span m="2854280">can</span> <span m="2854560">see</span> <span m="2855470">it</span>
  <span m="2855960">is--</span> <span m="2861830">right?</span> <span m="2862690">I''m</span>
  <span m="2862960">basically</span> <span m="2863330">factoring</span> <span m="2863840">the</span>
  <span m="2863910">two</span> <span m="2864230">into</span> <span m="2864570">these.</span>
  <span m="2865590">And</span> <span m="2865870">I</span> <span m="2866470">minus</span>
  <span m="2866570">2,</span> <span m="2866670">plus or</span> <span m="2867090">minus</span>
  <span m="2867450">3.</span> <span m="2868280">So</span> <span m="2868480">that''s</span>
  <span m="2868850">equal</span> <span m="2869310">to</span> <span m="2869610">what?</span>
  <span m="2870500">It''s</span> <span m="2870760">equal</span> <span m="2871110">to</span>
  <span m="2871230">either</span> <span m="2871650">minus</span> <span m="2872150">5</span>
  <span m="2873330">or</span> <span m="2873760">1.</span> <span m="2876780">All right.</span>
  <span m="2877910">OK.</span> <span m="2878320">If</span> <span m="2878530">I</span>
  <span m="2878770">only</span> <span m="2879020">look</span> <span m="2879260">at</span>
  <span m="2879340">the</span> <span m="2879410">one,</span> <span m="2879880">that</span>
  <span m="2880070">means</span> <span m="2880440">good.</span> <span m="2881480">It</span>
  <span m="2881660">allows</span> <span m="2881750">a</span> <span m="2882190">constant</span>
  <span m="2882650">solution,</span> <span m="2883120">right?</span> <span m="2885520">Z
  is</span> <span m="2885830">equal to</span> <span m="2886080">1</span> <span m="2886610">basically</span>
  <span m="2887040">means</span> <span m="2887320">Vk</span> <span m="2887940">is
  equal</span> <span m="2888140">to</span> <span m="2888420">V0</span> <span m="2889490">period,</span>
  <span m="2890350">or</span> <span m="2890580">whatever</span> <span m="2890780">k.</span>
  <span m="2892270">So</span> <span m="2892980">in</span> <span m="2893190">this</span>
  <span m="2893460">sense,</span> <span m="2896520">it does</span> <span m="2896860">allow</span>
  <span m="2897450">a</span> <span m="2897560">numerical</span> <span m="2897930">solution</span>
  <span m="2898260">of</span> <span m="2898430">this</span> <span m="2898620">differential</span>
  <span m="2899070">equation.</span> <span m="2899890">du/dt</span> <span m="2900280">is</span>
  <span m="2900690">equal</span> <span m="2900990">to zero.</span></p><p><span m="2901830">But</span>
  <span m="2902250">it</span> <span m="2902560">has</span> <span m="2902900">another</span>
  <span m="2903700">solution</span> <span m="2904470">of</span> <span m="2904810">Z</span>
  <span m="2905240">equal</span> <span m="2905450">to minus</span> <span m="2905880">5.</span>
  <span m="2907142">And</span> <span m="2907570">it</span> <span m="2907750">is</span>
  <span m="2907950">that</span> <span m="2908710">solution</span> <span m="2910230">that</span>
  <span m="2910500">makes</span> <span m="2910750">the</span> <span m="2910860">scheme</span>
  <span m="2911130">diverge.</span> <span m="2912610">You</span> <span m="2912860">only</span>
  <span m="2913240">need</span> <span m="2913520">one</span> <span m="2914350">bad</span>
  <span m="2915750">solution</span> <span m="2916280">Z</span> <span m="2917320">to</span>
  <span m="2917530">make</span> <span m="2917770">the</span> <span m="2917860">scheme</span>
  <span m="2918130">diverge.</span> <span m="2919180">And</span> <span m="2919410">that''s</span>
  <span m="2919790">what</span> <span m="2920030">we</span> <span m="2920160">saw</span>
  <span m="2920590">over</span> <span m="2920910">here.</span> <span m="2921230">The</span>
  <span m="2921330">scheme</span> <span m="2921610">is</span> <span m="2921800">not</span>
  <span m="2922150">zero</span> <span m="2922900">stable.</span> <span m="2923350">Therefore,</span>
  <span m="2923890">although</span> <span m="2924240">it is</span> <span m="2924630">locally</span>
  <span m="2925080">accurate,</span> <span m="2925860">it</span> <span m="2926010">is</span>
  <span m="2926220">not</span> <span m="2926900">globally</span> <span m="2927240">accurate.</span>
  <span m="2928590">But</span> <span m="2929040">because</span> <span m="2929410">it''s</span>
  <span m="2929610">not</span> <span m="2929920">zero</span> <span m="2930346">stable,</span>
  <span m="2930772">it can''t</span> <span m="2931200">solve</span> <span m="2931580">this</span>
  <span m="2932047">equation.</span></p><p><span m="2934382">All right?</span> <span
  m="2936717">I''ll see you</span> <span m="2937184">tomorrow</span> <span m="2938140">and</span>
  <span m="2938650">continue</span> <span m="2939015">discussing</span> <span m="2939380">this</span>
  <span m="2940210">and</span> <span m="2940530">also</span> <span m="2940830">look</span>
  <span m="2941130">into</span> <span m="2941430">Eigenvalue</span> <span m="2941730">stability.</span></p>'
type: course
uid: 3e80d2947c11c63304921d680133c788

---
None