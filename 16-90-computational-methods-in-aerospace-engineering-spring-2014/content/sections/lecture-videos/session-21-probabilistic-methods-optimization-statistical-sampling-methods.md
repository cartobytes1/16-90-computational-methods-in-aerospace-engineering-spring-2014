---
about_this_resource_text: '<p><strong>Description:</strong> This video covers statistical
  sampling methods and includes bootstrapping, variance reduction methods, importance
  sampling and sensitivity analysis.</p>  <p><strong>Instructor:</strong> Karen Willcox</p>
  <p>The recording quality of this video is the best available from the source.</p><p>NOTE:
  There is no video for the next class, Session 22.</p>'
course_id: 16-90-computational-methods-in-aerospace-engineering-spring-2014
embedded_media:
- id: Video-YouTube-Stream
  media_location: ruZ33P1ICRs
  parent_uid: 753f0a2f14246c7872ca5ab157b69a42
  title: Video-YouTube-Stream
  type: Video
  uid: 7ae1e3b73b727bb69ea7ccef092872b5
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/ruZ33P1ICRs/default.jpg
  parent_uid: 753f0a2f14246c7872ca5ab157b69a42
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: e645332bb1cdcda61574dfc35e2be774
- id: 3Play-3PlayYouTubeid-MP4
  media_location: ruZ33P1ICRs
  parent_uid: 753f0a2f14246c7872ca5ab157b69a42
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 158367ee99feca40fad73581aec5eae1
- id: ruZ33P1ICRs.srt
  parent_uid: 753f0a2f14246c7872ca5ab157b69a42
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-21-probabilistic-methods-optimization-statistical-sampling-methods/ruZ33P1ICRs.srt
  title: 3play caption file
  type: null
  uid: 742ba65c0570a8a18be53a37d3b0a6ac
- id: ruZ33P1ICRs.pdf
  parent_uid: 753f0a2f14246c7872ca5ab157b69a42
  technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-21-probabilistic-methods-optimization-statistical-sampling-methods/ruZ33P1ICRs.pdf
  title: 3play pdf file
  type: null
  uid: caeeeeac9e57f63c50304d4cfccdd3dd
- id: Caption-3Play YouTube id-SRT
  parent_uid: 753f0a2f14246c7872ca5ab157b69a42
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: ba254062ef1198fdbab0169acca22169
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 753f0a2f14246c7872ca5ab157b69a42
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: da7aba15017574f7e16fe26703fda17f
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT16.90S14/MIT16_90S14_L21_300k.mp4
  parent_uid: 753f0a2f14246c7872ca5ab157b69a42
  title: Video-Internet Archive-MP4
  type: Video
  uid: 603a3ac19a474a8cf2f249ca75cab28f
inline_embed_id: 48290402session21:probabilisticmethods&optimization:statisticalsamplingmethods84822293
layout: video
order_index: null
parent_uid: 809ebf7c44bfb36e8786306747d7e32f
related_resources_text: ''
short_url: session-21-probabilistic-methods-optimization-statistical-sampling-methods
technical_location: https://ocw.mit.edu/courses/aeronautics-and-astronautics/16-90-computational-methods-in-aerospace-engineering-spring-2014/lecture-videos/session-21-probabilistic-methods-optimization-statistical-sampling-methods
template_type: Tabbed
title: 'Session 21: Probabilistic Methods & Optimization: Statistical sampling methods'
transcript: <p><span m="30">The</span> <span m="130">following</span> <span m="600">content</span>
  <span m="1090">is</span> <span m="1210">provided</span> <span m="1660">under</span>
  <span m="1900">a</span> <span m="1950">Creative</span> <span m="2400">Commons</span>
  <span m="2820">license.</span> <span m="3780">Your</span> <span m="3880">support</span>
  <span m="4400">will</span> <span m="4570">help</span> <span m="4790">MIT</span>
  <span m="5280">OpenCourseWare</span> <span m="6020">continue</span> <span m="6510">to</span>
  <span m="6680">offer</span> <span m="6980">high</span> <span m="7200">quality</span>
  <span m="7680">educational</span> <span m="8350">resources</span> <span m="8920">for</span>
  <span m="9040">free.</span> <span m="10100">To</span> <span m="10130">make</span>
  <span m="10330">a</span> <span m="10370">donation</span> <span m="11090">or</span>
  <span m="11310">to</span> <span m="11430">view</span> <span m="11630">additional</span>
  <span m="12050">materials</span> <span m="12670">from</span> <span m="12850">hundreds</span>
  <span m="13180">of</span> <span m="13280">MIT</span> <span m="13650">courses,</span>
  <span m="14960">visit</span> <span m="15150">MIT</span> <span m="15670">OpenCourseWare</span>
  <span m="16580">at</span> <span m="16920">ocw.mit.edu.</span></p><p><span m="27200">KAREN
  WILLCOX:</span> <span m="27630">So</span> <span m="28470">first</span> <span m="28810">up,</span>
  <span m="29090">bootstrapping,</span> <span m="32189">which</span> <span m="32380">is</span>
  <span m="32509">really</span> <span m="32729">aimed</span> <span m="33020">at</span>
  <span m="33110">this</span> <span m="33330">question</span> <span m="35390">how</span>
  <span m="35630">do</span> <span m="35740">we</span> <span m="35930">get</span> <span
  m="36270">estimates</span> <span m="36850">of</span> <span m="36990">the</span>
  <span m="37070">standard</span> <span m="37540">errors</span> <span m="38880">and</span>
  <span m="38990">our</span> <span m="39150">estimators</span> <span m="40250">that</span>
  <span m="40400">don't</span> <span m="40620">have</span> <span m="40830">known</span>
  <span m="41370">distribution?</span> <span m="41990">So</span> <span m="42380">remember</span>
  <span m="42830">we</span> <span m="42950">were</span> <span m="43040">talking</span>
  <span m="43670">on</span> <span m="45450">Wednesday.</span> <span m="45795">I</span>
  <span m="46140">don't</span> <span m="46330">even</span> <span m="46520">know</span>
  <span m="46580">what</span> <span m="46690">day</span> <span m="46790">it</span>
  <span m="46935">is</span> <span m="47080">today.</span> <span m="47320">Monday.</span>
  <span m="48020">We</span> <span m="48075">were</span> <span m="48130">talking</span>
  <span m="48370">on</span> <span m="48480">Monday</span> <span m="49530">about</span>
  <span m="50220">how</span> <span m="50400">you</span> <span m="50490">can</span>
  <span m="50630">run</span> <span m="50770">the</span> <span m="50830">Monte</span>
  <span m="51000">Carlo</span> <span m="51420">simulation</span> <span m="52110">and</span>
  <span m="52200">then</span> <span m="52340">we</span> <span m="52500">know,</span>
  <span m="52840">for</span> <span m="53010">example,</span> <span m="53470">the</span>
  <span m="53560">mean</span> <span m="53980">estimate</span> <span m="55470">and</span>
  <span m="55640">the</span> <span m="55690">limit</span> <span m="56060">then goes</span>
  <span m="56390">to</span> <span m="56470">infinity</span> <span m="57620">by</span>
  <span m="57710">the</span> <span m="57810">central</span> <span m="58130">limit</span>
  <span m="58420">theorem.</span></p><p><span m="58810">Then</span> <span m="59090">the</span>
  <span m="59240">distribution</span> <span m="59780">of</span> <span m="59870">the</span>
  <span m="59950">estimator</span> <span m="60760">itself,</span> <span m="61590">estimate</span>
  <span m="62050">for</span> <span m="62130">the</span> <span m="62200">main</span>
  <span m="62850">is</span> <span m="63040">normal.</span> <span m="64300">And</span>
  <span m="64510">the</span> <span m="64580">mean</span> <span m="64950">of</span>
  <span m="65090">that</span> <span m="65290">distribution</span> <span m="65860">is</span>
  <span m="66010">the</span> <span m="66100">actual</span> <span m="66400">mean</span>
  <span m="66560">that</span> <span m="66720">we're</span> <span m="66830">trying</span>
  <span m="67010">to</span> <span m="67070">estimate.</span> <span m="67490">It's</span>
  <span m="67610">unbiased.</span> <span m="68950">And</span> <span m="69400">the</span>
  <span m="69470">standard</span> <span m="69710">deviation</span> <span m="70160">of</span>
  <span m="70220">that</span> <span m="70330">distribution,</span> <span m="71010">remember,</span>
  <span m="71280">was</span> <span m="72320">the</span> <span m="72345">standard</span>
  <span m="72370">deviation</span> <span m="72860">of</span> <span m="72930">the</span>
  <span m="72990">quantity</span> <span m="73750">we're</span> <span m="74840">putting</span>
  <span m="75040">in</span> <span m="75110">an</span> <span m="75230">output</span>
  <span m="75570">divided</span> <span m="75850">by</span> <span m="75970">square</span>
  <span m="76300">root</span> <span m="76670">of</span> <span m="77103">n.</span></p><p><span
  m="77970">But</span> <span m="78180">we</span> <span m="78300">also</span> <span
  m="78650">said</span> <span m="79000">that,</span> <span m="79230">for</span> <span
  m="79340">example,</span> <span m="79730">the</span> <span m="79800">estimate</span>
  <span m="80160">of</span> <span m="80230">the</span> <span m="80300">variance--</span>
  <span m="80850">remember</span> <span m="81105">Alex</span> <span m="81360">told</span>
  <span m="81630">you</span> <span m="81710">three</span> <span m="81900">different</span>
  <span m="82205">ways</span> <span m="82510">to</span> <span m="82990">estimate</span>
  <span m="83470">variance--</span> <span m="84340">that</span> <span m="84530">those</span>
  <span m="84980">estimators</span> <span m="85500">don't</span> <span m="85740">have</span>
  <span m="85940">known</span> <span m="86270">distributions.</span> <span m="87160">They're</span>
  <span m="87680">not</span> <span m="87830">necessarily</span> <span m="88370">following</span>
  <span m="88780">a</span> <span m="88830">normal</span> <span m="89090">distribution</span>
  <span m="89660">or</span> <span m="89780">any</span> <span m="89940">other</span>
  <span m="90070">known</span> <span m="90410">distribution.</span></p><p><span m="91580">So</span>
  <span m="93500">bootstrapping</span> <span m="94140">is</span> <span m="94490">a</span>
  <span m="94630">trick,</span> <span m="94920">and</span> <span m="95030">actually,</span>
  <span m="95270">as</span> <span m="95410">I</span> <span m="95470">was</span> <span
  m="95640">putting</span> <span m="95870">together</span> <span m="96100">today's</span>
  <span m="96420">lecture,</span> <span m="96800">I</span> <span m="97030">[AUDIO
  OUT]</span> <span m="98010">tricks.</span> <span m="98310">Statisticians</span>
  <span m="98430">tend</span> <span m="98910">to</span> <span m="99000">have</span>
  <span m="99140">lots</span> <span m="99430">of</span> <span m="101020">tricks</span>
  <span m="101460">up</span> <span m="101620">their</span> <span m="101790">sleeves--</span>
  <span m="102720">just</span> <span m="102940">going</span> <span m="103010">to</span>
  <span m="103090">pull</span> <span m="103340">out</span> <span m="103620">the</span>
  <span m="103870">section</span> <span m="104230">on</span> <span m="104330">the</span>
  <span m="104400">notes</span> <span m="104900">because</span> <span m="105400">I</span>
  <span m="105440">think</span> <span m="105650">you</span> <span m="105730">should</span>
  <span m="105910">have</span> <span m="107680">read</span> <span m="107980">this--</span>
  <span m="109890">as</span> <span m="110100">to</span> <span m="110210">how</span>
  <span m="110520">bootstrapping</span> <span m="111260">works.</span> <span m="111520">And</span>
  <span m="111610">there's</span> <span m="111880">a</span> <span m="113380">lot</span>
  <span m="113560">of</span> <span m="115540">words</span> <span m="115890">here,</span>
  <span m="116580">but</span> <span m="116660">let's</span> <span m="116760">just</span>
  <span m="116880">come</span> <span m="117060">down</span> <span m="117320">to</span>
  <span m="117410">the</span> <span m="117490">[INAUDIBLE].</span></p><p><span m="119660">So</span>
  <span m="119830">what</span> <span m="119950">do</span> <span m="119990">we</span>
  <span m="120110">do</span> <span m="120480">in</span> <span m="120830">bootstrapping</span>
  <span m="120880">is</span> <span m="121180">perform</span> <span m="121680">our</span>
  <span m="121900">initial</span> <span m="122370">Monte</span> <span m="122660">Carlo</span>
  <span m="123000">sample,</span> <span m="123710">just</span> <span m="123780">like</span>
  <span m="123890">we've</span> <span m="124000">been</span> <span m="124120">talking</span>
  <span m="124410">about.</span> <span m="125210">So</span> <span m="125880">take</span>
  <span m="126100">the</span> <span m="126170">inputs,</span> <span m="126570">draw</span>
  <span m="126870">in</span> <span m="127850">realizations</span> <span m="128530">from</span>
  <span m="128669">the</span> <span m="128740">input</span> <span m="129240">distributions,</span>
  <span m="130490">run</span> <span m="130700">them</span> <span m="130910">each</span>
  <span m="131140">through</span> <span m="131270">the</span> <span m="131340">model,</span>
  <span m="131710">produce</span> <span m="132060">the</span> <span m="132140">samples,</span>
  <span m="132620">the</span> <span m="132700">yi's,</span> <span m="133820">and</span>
  <span m="134115">compute</span> <span m="134770">the</span> <span m="134840">desired</span>
  <span m="135250">estimator</span> <span m="135920">So</span> <span m="136020">this</span>
  <span m="136120">theta</span> <span m="136570">here</span> <span m="136970">might</span>
  <span m="137310">be</span> <span m="137460">a</span> <span m="137610">mean</span>
  <span m="137980">estimate</span> <span m="138310">or</span> <span m="138600">think</span>
  <span m="138790">of</span> <span m="138860">it</span> <span m="138940">as</span>
  <span m="139030">a</span> <span m="139060">variance</span> <span m="139420">instrument,</span>
  <span m="139600">one</span> <span m="140090">we</span> <span m="140190">can't</span>
  <span m="140460">necessarily</span> <span m="142240">easily</span> <span m="142600">do</span>
  <span m="143570">the</span> <span m="143670">confidence</span> <span m="144370">interval</span>
  <span m="144600">analysis</span> <span m="145120">on.</span></p><p><span m="145960">Then</span>
  <span m="146080">what</span> <span m="146240">bootstrapping</span> <span m="146420">says</span>
  <span m="146775">is,</span> <span m="147790">well,</span> <span m="147890">now</span>
  <span m="148050">you've</span> <span m="148230">got</span> <span m="148430">these</span>
  <span m="148640">N</span> <span m="148920">samples.</span> <span m="149870">And</span>
  <span m="150010">remember</span> <span m="150240">each</span> <span m="150450">one</span>
  <span m="150570">of</span> <span m="150630">these</span> <span m="150790">samples</span>
  <span m="151190">is</span> <span m="151340">being</span> <span m="151590">run</span>
  <span m="151850">through</span> <span m="152000">your</span> <span m="152090">finite</span>
  <span m="152360">element</span> <span m="152730">model,</span> <span m="153210">run</span>
  <span m="153530">through</span> <span m="153580">your</span> <span m="153840">CAD</span>
  <span m="154130">model.</span> <span m="155500">Let's</span> <span m="155760">now</span>
  <span m="156030">re</span> <span m="156350">sample</span> <span m="156870">those</span>
  <span m="157080">values.</span> <span m="158100">But</span> <span m="158330">N</span>
  <span m="158680">samples</span> <span m="159540">of</span> <span m="159740">y,</span>
  <span m="160540">N</span> <span m="160810">samples</span> <span m="161230">of</span>
  <span m="161360">the</span> <span m="161440">blade</span> <span m="162150">middle</span>
  <span m="162420">hot</span> <span m="162590">side</span> <span m="162790">temperatures</span>
  <span m="163310">sitting</span> <span m="163530">in</span> <span m="163630">the</span>
  <span m="163710">bin,</span> <span m="164440">let's</span> <span m="164660">just</span>
  <span m="164710">re</span> <span m="165030">sample</span> <span m="165460">from</span>
  <span m="165640">those</span> <span m="165860">ones.</span></p><p><span m="167050">And</span>
  <span m="167220">why</span> <span m="167410">is</span> <span m="167500">that</span>
  <span m="167630">efficient?</span> <span m="168040">Because</span> <span m="168240">we</span>
  <span m="168300">don't</span> <span m="168440">have</span> <span m="168630">to</span>
  <span m="168710">run</span> <span m="168940">the</span> <span m="169000">model</span>
  <span m="169330">anymore.</span> <span m="169860">We</span> <span m="169920">don't</span>
  <span m="170040">have</span> <span m="170160">to</span> <span m="170230">do</span>
  <span m="170560">the</span> <span m="170605">finite</span> <span m="170650">element</span>
  <span m="170950">analysis.</span> <span m="172350">And</span> <span m="172850">we're</span>
  <span m="173050">just</span> <span m="173110">going</span> <span m="173170">to</span>
  <span m="173230">re</span> <span m="173420">sample</span> <span m="174020">from</span>
  <span m="174330">those</span> <span m="175150">with</span> <span m="175420">equal</span>
  <span m="175760">probability.</span> <span m="176490">So</span> <span m="176690">probability</span>
  <span m="177260">1</span> <span m="177450">over</span> <span m="177560">N</span>
  <span m="178190">int,</span> <span m="178980">we</span> <span m="179120">do</span>
  <span m="179270">it</span> <span m="179360">with</span> <span m="180310">replacement,</span>
  <span m="181050">so</span> <span m="181140">you</span> <span m="181330">could</span>
  <span m="182070">pick</span> <span m="182250">the</span> <span m="182310">same</span>
  <span m="182590">sample</span> <span m="183000">more</span> <span m="183170">than</span>
  <span m="183290">once.</span></p><p><span m="185860">So</span> <span m="186060">they're</span>
  <span m="186170">pretty</span> <span m="186340">clear.</span> <span m="186590">We</span>
  <span m="186690">had</span> <span m="186820">N</span> <span m="187290">samples.</span>
  <span m="187570">Then</span> <span m="187660">we're</span> <span m="187750">going</span>
  <span m="187870">to</span> <span m="187960">sample</span> <span m="188910">N</span>
  <span m="189170">time</span> <span m="189470">from</span> <span m="189680">those,</span>
  <span m="189920">but</span> <span m="190030">we're</span> <span m="190100">going</span>
  <span m="190220">to</span> <span m="190290">get</span> <span m="190590">a</span>
  <span m="190620">different</span> <span m="191000">set</span> <span m="191130">of</span>
  <span m="191230">N</span> <span m="191840">because,</span> <span m="193000">I</span>
  <span m="193060">mean,</span> <span m="193240">maybe</span> <span m="193510">we'll</span>
  <span m="193640">pick</span> <span m="193850">each</span> <span m="194030">one</span>
  <span m="194450">once,</span> <span m="195190">but</span> <span m="195340">more</span>
  <span m="195470">likely</span> <span m="195760">we're</span> <span m="195840">going</span>
  <span m="195960">to</span> <span m="196030">pick</span> <span m="196200">that</span>
  <span m="196370">one</span> <span m="196490">a</span> <span m="196540">couple</span>
  <span m="196675">of</span> <span m="196810">times</span> <span m="197280">and</span>
  <span m="197570">this</span> <span m="197645">one</span> <span m="197720">not</span>
  <span m="197920">at</span> <span m="198020">all.</span> <span m="198820">So</span>
  <span m="199000">we'll</span> <span m="199026">have</span> <span m="199053">a</span>
  <span m="199080">different</span> <span m="201290">sampling,</span> <span m="202170">we</span>
  <span m="202310">could</span> <span m="202450">compute</span> <span m="202840">the</span>
  <span m="202970">estimator,</span> <span m="204200">and</span> <span m="204350">we</span>
  <span m="204440">could</span> <span m="204870">keep</span> <span m="205150">doing</span>
  <span m="205440">that</span> <span m="206650">N</span> <span m="206800">minus</span>
  <span m="207090">1</span> <span m="207290">times.</span> <span m="207760">In</span>
  <span m="208120">the</span> <span m="208290">end,</span> <span m="208600">we're</span>
  <span m="208700">going</span> <span m="208720">to</span> <span m="208780">end</span>
  <span m="209050">up</span> <span m="209180">with</span> <span m="210380">N</span>
  <span m="210670">values</span> <span m="210820">to</span> <span m="211130">the</span>
  <span m="211270">estimator.</span> <span m="213090">And</span> <span m="213650">from</span>
  <span m="214050">there</span> <span m="214360">you</span> <span m="214580">could</span>
  <span m="215010">try</span> <span m="215170">to</span> <span m="215680">determine</span>
  <span m="216400">competence</span> <span m="216920">intervals.</span></p><p><span
  m="218051">So</span> <span m="218430">it's</span> <span m="218610">kind</span> <span
  m="218770">of</span> <span m="218840">a</span> <span m="218890">trick</span> <span
  m="219140">because</span> <span m="219255">it's</span> <span m="219370">kind</span>
  <span m="219540">of</span> <span m="219620">cheating.</span> <span m="220950">And</span>
  <span m="221600">it's</span> <span m="221840">not</span> <span m="223220">the</span>
  <span m="223330">same</span> <span m="223620">thing</span> <span m="223990">as</span>
  <span m="224220">running</span> <span m="224480">a</span> <span m="224580">new</span>
  <span m="224956">Monte</span> <span m="225332">Carlo,</span> <span m="225521">but</span>
  <span m="225710">hopefully,</span> <span m="225990">you</span> <span m="226120">can</span>
  <span m="226310">see</span> <span m="226480">that</span> <span m="226630">this</span>
  <span m="226780">is</span> <span m="226860">something</span> <span m="227130">you</span>
  <span m="227200">can</span> <span m="227360">do</span> <span m="227510">with</span>
  <span m="227650">almost</span> <span m="228010">no</span> <span m="228300">more</span>
  <span m="229200">computational</span> <span m="229850">cost,</span> <span m="230840">and</span>
  <span m="230980">it</span> <span m="231040">actually</span> <span m="231250">turns</span>
  <span m="231510">out</span> <span m="231610">that</span> <span m="231730">if</span>
  <span m="231830">you</span> <span m="231930">do</span> <span m="232110">some</span>
  <span m="232280">analysis,</span> <span m="232900">this</span> <span m="233060">is</span>
  <span m="233190">a</span> <span m="233480">reasonable</span> <span m="234000">thing</span>
  <span m="234210">to</span> <span m="234300">do</span> <span m="234520">and</span>
  <span m="235770">it</span> <span m="236005">take</span> <span m="236130">a</span>
  <span m="236190">lot</span> <span m="236250">of</span> <span m="236310">statisticians</span>
  <span m="236595">to</span> <span m="236690">analyze</span> <span m="236785">it.</span></p><p><span
  m="236880">So</span> <span m="237225">when</span> <span m="237570">people</span>
  <span m="237780">talk</span> <span m="237920">about</span> <span m="238110">bootstrapping</span>
  <span m="239470">in</span> <span m="239550">this</span> <span m="239690">context,</span>
  <span m="240080">this</span> <span m="240200">is</span> <span m="240300">what</span>
  <span m="240460">they're</span> <span m="240590">talking</span> <span m="240960">about,</span>
  <span m="241700">re</span> <span m="242070">sampling</span> <span m="243410">from</span>
  <span m="243640">your</span> <span m="243760">samples,</span> <span m="245370">putting</span>
  <span m="245570">the</span> <span m="245630">information</span> <span m="246130">together</span>
  <span m="246470">in</span> <span m="246560">different</span> <span m="246870">ways,</span>
  <span m="247380">and</span> <span m="247490">then</span> <span m="247640">using</span>
  <span m="247915">that</span> <span m="248190">to</span> <span m="248280">get</span>
  <span m="248420">a</span> <span m="248480">sense</span> <span m="249560">of</span>
  <span m="250120">the</span> <span m="250260">distribution</span> <span m="250880">and</span>
  <span m="251090">say</span> <span m="251220">that</span> <span m="251300">they're</span>
  <span m="251670">[? untestable. ?]</span> <span m="254000">Is</span> <span m="254430">that</span>
  <span m="254590">clear?</span></p><p><span m="259562">So</span> <span m="259970">[AUDIO
  OUT]</span> <span m="261170">internet,</span> <span m="261300">so</span> <span m="261380">I</span>
  <span m="261450">didn't</span> <span m="261600">get</span> <span m="261769">time</span>
  <span m="262550">to</span> <span m="262700">go</span> <span m="262930">through</span>
  <span m="263230">it</span> <span m="263530">on</span> <span m="265520">Monday.</span>
  <span m="266480">But</span> <span m="266630">I</span> <span m="266670">mostly</span>
  <span m="266980">want</span> <span m="267240">us</span> <span m="267720">to</span>
  <span m="267930">spin</span> <span m="268300">today</span> <span m="268650">talking</span>
  <span m="269000">about</span> <span m="269220">different</span> <span m="269510">ways</span>
  <span m="269740">to</span> <span m="269870">reduce</span> <span m="270720">variance.</span>
  <span m="272030">And</span> <span m="272190">again,</span> <span m="273870">the</span>
  <span m="273970">really</span> <span m="274160">important</span> <span m="275290">idea</span>
  <span m="275600">that</span> <span m="275720">should</span> <span m="275880">be</span>
  <span m="275980">in</span> <span m="276110">your</span> <span m="276260">heads</span>
  <span m="276520">is</span> <span m="277640">the</span> <span m="277740">quality</span>
  <span m="278570">of</span> <span m="278860">the</span> <span m="279317">estimators</span>
  <span m="280231">that</span> <span m="280690">come</span> <span m="280880">out</span>
  <span m="281120">depends</span> <span m="281390">on</span> <span m="281480">how</span>
  <span m="281590">many</span> <span m="281770">samples</span> <span m="282170">in</span>
  <span m="282230">the</span> <span m="282290">Monte</span> <span m="282490">Carlo.</span>
  <span m="283280">And</span> <span m="284070">if</span> <span m="284270">you</span>
  <span m="284370">can</span> <span m="284520">afford</span> <span m="285460">millions</span>
  <span m="286000">of</span> <span m="286100">samples,</span> <span m="286860">you</span>
  <span m="286940">can</span> <span m="287030">probably</span> <span m="287240">get</span>
  <span m="287410">really</span> <span m="287580">good</span> <span m="287730">estimates</span>
  <span m="288220">for</span> <span m="288330">the</span> <span m="288450">mean</span>
  <span m="290430">and</span> <span m="290570">maybe</span> <span m="290820">OK</span>
  <span m="291400">estimates</span> <span m="291880">of</span> <span m="291940">the</span>
  <span m="292000">variance.</span></p><p><span m="293530">But</span> <span m="293890">if,</span>
  <span m="294000">for</span> <span m="294100">example,</span> <span m="294500">you're</span>
  <span m="295330">interested</span> <span m="295850">in</span> <span m="296010">tail</span>
  <span m="296370">probabilities,</span> <span m="297753">so</span> <span m="298620">think</span>
  <span m="298770">about</span> <span m="300000">an</span> <span m="300120">aircraft</span>
  <span m="300560">design,</span> <span m="301070">a</span> <span m="301190">new</span>
  <span m="301310">flight</span> <span m="301560">critical</span> <span m="301870">system.</span>
  <span m="302220">Maybe</span> <span m="302420">they</span> <span m="302540">has</span>
  <span m="302700">to</span> <span m="302810">be</span> <span m="303130">a</span>
  <span m="303370">10</span> <span m="303400">to</span> <span m="303430">the</span>
  <span m="303460">minus</span> <span m="303890">9</span> <span m="304580">failure</span>
  <span m="305650">probability</span> <span m="306210">that</span> <span m="306310">we</span>
  <span m="306390">have</span> <span m="306510">to</span> <span m="306590">satisfy.</span>
  <span m="307370">So</span> <span m="307800">if</span> <span m="307920">we</span>
  <span m="308160">want</span> <span m="308360">to</span> <span m="308440">estimate</span>
  <span m="308610">that</span> <span m="308820">by</span> <span m="308870">Monte</span>
  <span m="309300">Carlo</span> <span m="309400">simulation,</span> <span m="309970">how</span>
  <span m="310640">many</span> <span m="310790">samples</span> <span m="311230">do</span>
  <span m="311370">we</span> <span m="311460">need?</span> <span m="313950">A</span>
  <span m="314070">lot.</span> <span m="314460">How</span> <span m="314580">many</span>
  <span m="314810">is</span> <span m="315085">a</span> <span m="315222">lot?</span>
  <span m="315360">At</span> <span m="315450">least</span> <span m="315740">how</span>
  <span m="315840">many?</span> <span m="320166">At</span> <span m="320620">least</span>
  <span m="320950">a</span> <span m="321000">billion.</span></p><p><span m="322360">If</span>
  <span m="322550">a</span> <span m="322780">probability</span> <span m="323240">is</span>
  <span m="323320">10</span> <span m="323400">to</span> <span m="323480">the</span>
  <span m="323560">minus</span> <span m="323930">9</span> <span m="324210">and</span>
  <span m="324340">we</span> <span m="324470">had</span> <span m="324590">a</span>
  <span m="324630">billion</span> <span m="324950">samples,</span> <span m="325520">then</span>
  <span m="326850">on</span> <span m="327120">average,</span> <span m="327560">you</span>
  <span m="327630">would</span> <span m="327740">expect</span> <span m="328130">one</span>
  <span m="328430">sample</span> <span m="328920">to</span> <span m="329380">be</span>
  <span m="329570">that</span> <span m="329986">failure.</span> <span m="330820">So</span>
  <span m="331100">that's</span> <span m="331410">not</span> <span m="331720">even</span>
  <span m="331980">going</span> <span m="332100">to</span> <span m="332160">be</span>
  <span m="332260">enough</span> <span m="333310">because</span> <span m="334320">you</span>
  <span m="334590">might</span> <span m="334730">get</span> <span m="334880">9,</span>
  <span m="335180">you</span> <span m="335240">might</span> <span m="335430">get</span>
  <span m="335590">1,</span> <span m="335820">you</span> <span m="335880">might</span>
  <span m="336030">get</span> <span m="336210">2.</span> <span m="336800">So</span>
  <span m="336990">that</span> <span m="337120">means</span> <span m="337290">you're</span>
  <span m="337450">going</span> <span m="337655">to</span> <span m="337860">estimate</span>
  <span m="337930">this</span> <span m="338000">probability</span> <span m="339860">differently.</span></p><p><span
  m="340390">So</span> <span m="340520">billions,</span> <span m="341550">tens</span>
  <span m="341860">of</span> <span m="341920">billions,</span> <span m="342330">hundreds</span>
  <span m="342740">of</span> <span m="342820">billions</span> <span m="343130">of</span>
  <span m="343200">samples</span> <span m="343720">to</span> <span m="343810">estimate</span>
  <span m="344115">what</span> <span m="344420">are</span> <span m="344852">called</span>
  <span m="345284">[? variates, ?]</span> <span m="346580">but</span> <span m="346760">even</span>
  <span m="347010">just</span> <span m="347130">in</span> <span m="347240">general,</span>
  <span m="347470">even</span> <span m="347690">just</span> <span m="347880">means,</span>
  <span m="348830">if</span> <span m="349030">you're</span> <span m="349130">talking</span>
  <span m="349470">about</span> <span m="349800">running</span> <span m="350150">a</span>
  <span m="350260">CSC</span> <span m="350710">code</span> <span m="351070">or a</span>
  <span m="351130">finite</span> <span m="351310">element</span> <span m="351880">simulation</span>
  <span m="352500">that</span> <span m="352680">takes</span> <span m="352950">minutes</span>
  <span m="353420">to</span> <span m="353540">run,</span> <span m="354580">we</span>
  <span m="354850">usually</span> <span m="354975">can't</span> <span m="355100">even</span>
  <span m="355260">afford</span> <span m="355970">hundreds</span> <span m="356310">of</span>
  <span m="356390">thousands</span> <span m="356770">of</span> <span m="356860">simulations.</span>
  <span m="357490">So</span> <span m="357580">the</span> <span m="357690">variance</span>
  <span m="358080">reduction</span> <span m="358440">method,</span> <span m="359610">trying</span>
  <span m="360140">to</span> <span m="360480">increase</span> <span m="361010">the</span>
  <span m="361120">accuracy</span> <span m="361580">of</span> <span m="361670">our</span>
  <span m="361760">Monte</span> <span m="361950">Carlo</span> <span m="362360">estimates</span>
  <span m="363110">for</span> <span m="363390">a</span> <span m="363440">given</span>
  <span m="363650">number</span> <span m="363860">of</span> <span m="363920">iterations.</span></p><p><span
  m="365480">And</span> <span m="365890">I</span> <span m="365970">think</span> <span
  m="366190">of</span> <span m="366260">them,</span> <span m="366470">their</span>
  <span m="366580">kind</span> <span m="366750">of</span> <span m="367160">tricks,</span>
  <span m="367570">and</span> <span m="367730">they're</span> <span m="367830">really</span>
  <span m="368030">clever</span> <span m="368340">tricks.</span> <span m="369235">I'll</span>
  <span m="369580">try</span> <span m="369620">to</span> <span m="369660">show</span>
  <span m="369810">you</span> <span m="369950">how,</span> <span m="370280">at</span>
  <span m="370755">least,</span> <span m="371230">important</span> <span m="371590">sampling</span>
  <span m="371970">works.</span> <span m="372890">And</span> <span m="373160">you</span>
  <span m="373220">can</span> <span m="373350">think</span> <span m="373510">of</span>
  <span m="373580">it</span> <span m="373690">in</span> <span m="373780">two</span>
  <span m="373960">ways.</span> <span m="374380">Here,</span> <span m="375010">if</span>
  <span m="375200">you've</span> <span m="375310">got</span> <span m="375480">a</span>
  <span m="375530">good</span> <span m="375710">number</span> <span m="375960">of</span>
  <span m="376060">samples,</span> <span m="376580">I'm</span> <span m="376730">willing</span>
  <span m="377190">to</span> <span m="377340">run</span> <span m="377940">a</span>
  <span m="378020">million</span> <span m="378390">samples,</span> <span m="379730">how</span>
  <span m="379830">much</span> <span m="380020">accuracy</span> <span m="380510">can</span>
  <span m="380710">I</span> <span m="380790">get</span> <span m="381110">in</span>
  <span m="381250">my</span> <span m="381430">estimators?</span> <span m="382690">Or</span>
  <span m="383260">you</span> <span m="383510">could</span> <span m="383700">think</span>
  <span m="384010">if</span> <span m="384160">I</span> <span m="384250">want</span>
  <span m="384460">to</span> <span m="384540">achieve</span> <span m="384990">a</span>
  <span m="385050">given</span> <span m="385320">level</span> <span m="385540">of</span>
  <span m="385640">accuracy</span> <span m="386990">in</span> <span m="387190">my</span>
  <span m="387340">estimator,</span> <span m="387920">how</span> <span m="388040">many</span>
  <span m="388210">samples</span> <span m="388590">do</span> <span m="388700">I</span>
  <span m="388780">need,</span> <span m="389100">and</span> <span m="389280">can</span>
  <span m="389410">we</span> <span m="389540">reduce</span> <span m="390010">the</span>
  <span m="390360">number</span> <span m="390630">of</span> <span m="390710">samples?</span></p><p><span
  m="392090">So</span> <span m="392110">there</span> <span m="392220">are</span> <span
  m="392250">a</span> <span m="392280">lot</span> <span m="392380">of</span> <span
  m="392440">different</span> <span m="392680">ways</span> <span m="392980">that</span>
  <span m="393530">people</span> <span m="393790">do</span> <span m="393880">variance</span>
  <span m="394070">reduction--</span> <span m="394590">important</span> <span m="395020">sampling,</span>
  <span m="395640">what's</span> <span m="395980">called</span> <span m="396400">antithetic</span>
  <span m="397140">sampling,</span> <span m="397710">control</span> <span m="398120">variates,</span>
  <span m="399280">stratified</span> <span m="399910">sampling.</span> <span m="400620">And</span>
  <span m="400810">I've</span> <span m="401130">decided</span> <span m="401500">I</span>
  <span m="401540">was</span> <span m="401586">going</span> <span m="401633">to</span>
  <span m="401680">talk</span> <span m="401970">about</span> <span m="402510">control</span>
  <span m="402790">variates</span> <span m="403263">and</span> <span m="403420">importance</span>
  <span m="403578">sampling,</span> <span m="403736">but</span> <span m="404210">I</span>
  <span m="404280">think</span> <span m="404470">we'll</span> <span m="404560">just</span>
  <span m="404830">talk</span> <span m="404990">about</span> <span m="405220">importance</span>
  <span m="405570">sampling</span> <span m="405910">today</span> <span m="406180">because</span>
  <span m="406410">it's</span> <span m="406550">already</span> <span m="406790">quite</span>
  <span m="407000">a</span> <span m="407060">lot</span> <span m="408220">to</span>
  <span m="408370">think</span> <span m="408620">about.</span></p><p><span m="410760">So</span>
  <span m="411370">in</span> <span m="411670">general</span> <span m="412160">importance</span>
  <span m="412620">sampling,</span> <span m="413310">is</span> <span m="416390">a</span>
  <span m="416510">general</span> <span m="416960">technique</span> <span m="417590">for</span>
  <span m="417870">estimating</span> <span m="418710">properties</span> <span m="419220">of</span>
  <span m="419310">one</span> <span m="419560">distribution</span> <span m="420990">while</span>
  <span m="421240">only</span> <span m="421580">having</span> <span m="421820">samples</span>
  <span m="422360">generated</span> <span m="422860">from</span> <span m="423010">another</span>
  <span m="423270">different</span> <span m="424120">distribution.</span> <span m="424930">So</span>
  <span m="425240">keep</span> <span m="425440">this</span> <span m="425590">in</span>
  <span m="425680">mind</span> <span m="425950">as</span> <span m="426060">we</span>
  <span m="426160">go</span> <span m="426340">through,</span> <span m="426600">because</span>
  <span m="426800">it's</span> <span m="426920">a</span> <span m="426990">key</span>
  <span m="427200">idea.</span> <span m="428130">We're</span> <span m="428210">going</span>
  <span m="428330">to</span> <span m="428390">have</span> <span m="428510">samples</span>
  <span m="428990">generated</span> <span m="429400">from</span> <span m="429550">one</span>
  <span m="429710">distribution,</span> <span m="431270">and</span> <span m="431310">we're</span>
  <span m="431370">going</span> <span m="431490">to</span> <span m="431550">figure</span>
  <span m="431860">out</span> <span m="432160">how</span> <span m="432390">to</span>
  <span m="432490">manipulate</span> <span m="433120">those</span> <span m="433320">samples</span>
  <span m="434460">so</span> <span m="434590">that</span> <span m="434700">they</span>
  <span m="434850">can</span> <span m="435770">estimate</span> <span m="436460">things</span>
  <span m="436780">about</span> <span m="436940">a</span> <span m="437100">different</span>
  <span m="437690">distribution</span> <span m="437990">for</span> <span m="438290">us.</span>
  <span m="439240">And</span> <span m="439340">it</span> <span m="439400">seems</span>
  <span m="439730">kind</span> <span m="439860">of</span> <span m="439930">like</span>
  <span m="440100">a</span> <span m="440150">wacky</span> <span m="440440">thing</span>
  <span m="440670">to</span> <span m="440760">do,</span> <span m="441840">but</span>
  <span m="442070">what</span> <span m="442420">you'll</span> <span m="442600">see</span>
  <span m="442820">is</span> <span m="442960">that</span> <span m="443080">if</span>
  <span m="443190">you</span> <span m="443340">pick</span> <span m="443640">this</span>
  <span m="445660">distribution</span> <span m="446330">carefully,</span> <span m="447630">we</span>
  <span m="447650">can</span> <span m="447820">say</span> <span m="448060">things</span>
  <span m="448360">about</span> <span m="448600">the</span> <span m="448680">statistics</span>
  <span m="449300">of</span> <span m="449410">the</span> <span m="449550">other</span>
  <span m="449740">distribution</span> <span m="451040">in</span> <span m="451190">a</span>
  <span m="451230">more</span> <span m="451420">efficient</span> <span m="451790">way</span>
  <span m="452750">with</span> <span m="452930">the</span> <span m="453000">Monte</span>
  <span m="453170">Carlo</span> <span m="453470">estimates.</span></p><p><span m="455060">So</span>
  <span m="457230">let</span> <span m="457390">me</span> <span m="457560">get</span>
  <span m="458290">the</span> <span m="459670">screen</span> <span m="460090">up.</span>
  <span m="464770">And</span> <span m="474570">so</span> <span m="476070">we're</span>
  <span m="476215">at</span> <span m="476360">number</span> <span m="476550">3,</span>
  <span m="477160">important</span> <span m="477600">sampling.</span> <span m="478676">Not</span>
  <span m="479162">a</span> <span m="479648">very</span> <span m="480620">good</span>
  <span m="480740">piece</span> <span m="481080">of</span> <span m="481120">chalk.</span>
  <span m="486120">And</span> <span m="494780">so</span> <span m="498080">let's</span>
  <span m="498400">think</span> <span m="498710">about</span> <span m="498960">a</span>
  <span m="499040">random</span> <span m="499340">variable,</span> <span m="499840">x,</span>
  <span m="504833">that</span> <span m="505326">has</span> <span m="505819">pdf</span>
  <span m="511580">f</span> <span m="511680">sub</span> <span m="511780">x,</span>
  <span m="515124">and</span> <span m="516576">it</span> <span m="517060">has</span>
  <span m="517549">mean</span> <span m="518220">that</span> <span m="518360">we'll</span>
  <span m="518570">call</span> <span m="518990">mu</span> <span m="519190">sub</span>
  <span m="519659">x,</span> <span m="520139">which</span> <span m="520789">is</span>
  <span m="520890">the</span> <span m="521520">expectation</span> <span m="524039">of</span>
  <span m="525180">x.</span> <span m="526140">And</span> <span m="526290">I'm</span>
  <span m="526350">going</span> <span m="526470">to</span> <span m="526530">put</span>
  <span m="526670">a</span> <span m="526740">little</span> <span m="527930">x</span>
  <span m="529040">on</span> <span m="529210">the</span> <span m="529370">subscript</span>
  <span m="529900">on</span> <span m="529990">the</span> <span m="530100">expectation</span>
  <span m="532060">to</span> <span m="532150">just</span> <span m="532740">denote</span>
  <span m="533990">that</span> <span m="534150">we're</span> <span m="534260">taking</span>
  <span m="534570">an</span> <span m="534750">expectation</span> <span m="538970">under</span>
  <span m="539850">the</span> <span m="540050">density</span> <span m="542730">f</span>
  <span m="543050">sub</span> <span m="543120">x.</span></p><p><span m="544130">So</span>
  <span m="544230">what</span> <span m="544340">I</span> <span m="544440">mean</span>
  <span m="544670">by</span> <span m="544780">that?</span> <span m="545380">If</span>
  <span m="545690">you</span> <span m="545860">want</span> <span m="546000">to</span>
  <span m="546070">think</span> <span m="546310">about</span> <span m="546640">an</span>
  <span m="546750">expectation</span> <span m="548210">as</span> <span m="548430">an</span>
  <span m="548770">integral,</span> <span m="549650">and</span> <span m="549780">remember</span>
  <span m="550160">Alex</span> <span m="550250">talked</span> <span m="550400">about</span>
  <span m="550610">this</span> <span m="550820">on</span> <span m="551490">Monday,</span>
  <span m="552450">the</span> <span m="552590">expectation</span> <span m="553390">of</span>
  <span m="553620">x</span> <span m="554726">mu</span> <span m="555222">of</span>
  <span m="555471">x</span> <span m="555720">is</span> <span m="556860">the</span>
  <span m="557120">integral</span> <span m="557470">of</span> <span m="557750">what?</span>
  <span m="559151">x</span> <span m="560085">times</span> <span m="561490">it's</span>
  <span m="561800">pdf</span> <span m="564990">dx.</span> <span m="566860">And</span>
  <span m="567220">so</span> <span m="567940">again,</span> <span m="569250">you</span>
  <span m="569600">can</span> <span m="569800">see</span> <span m="570260">where</span>
  <span m="570380">we're</span> <span m="570470">going</span> <span m="570770">with</span>
  <span m="570970">this.</span> <span m="571110">Remember</span> <span m="571280">we</span>
  <span m="571420">talked</span> <span m="571680">about</span> <span m="571850">having</span>
  <span m="572030">a</span> <span m="572080">different</span> <span m="572370">distribution.</span>
  <span m="573740">We</span> <span m="573860">want</span> <span m="573980">to</span>
  <span m="574040">be</span> <span m="574110">clear</span> <span m="574330">that</span>
  <span m="574440">when</span> <span m="574540">we're</span> <span m="574630">talking</span>
  <span m="574910">about</span> <span m="575110">the</span> <span m="575230">expectation</span>
  <span m="576490">of</span> <span m="576890">the</span> <span m="576970">random</span>
  <span m="577180">variable,</span> <span m="577500">x,</span> <span m="577820">we're</span>
  <span m="577960">talking</span> <span m="578280">about</span> <span m="578500">taking</span>
  <span m="578880">the</span> <span m="578960">expectation</span> <span m="579330">with</span>
  <span m="579510">respect</span> <span m="579890">to</span> <span m="580020">it</span>
  <span m="580970">or</span> <span m="581150">under</span> <span m="581410">its</span>
  <span m="582540">pdf</span> <span m="582780">f</span> <span m="582910">sub</span>
  <span m="583240">x.</span> <span m="584220">Is</span> <span m="584310">the</span>
  <span m="584530">notation</span> <span m="584750">clear?</span> <span m="586244">Yes?</span></p><p><span
  m="588610">So</span> <span m="588790">we</span> <span m="588910">have</span> <span
  m="589370">this</span> <span m="589430">random</span> <span m="589820">variable,</span>
  <span m="590280">x.</span> <span m="592360">We</span> <span m="592510">may</span>
  <span m="592670">be</span> <span m="592830">interested</span> <span m="593290">in</span>
  <span m="594000">estimating</span> <span m="594490">its</span> <span m="594660">mean,</span>
  <span m="595060">and</span> <span m="595230">we</span> <span m="595390">know</span>
  <span m="595970">that</span> <span m="596940">this</span> <span m="597140">is</span>
  <span m="597310">the</span> <span m="597700">definition</span> <span m="598080">of</span>
  <span m="598170">the</span> <span m="598240">mean.</span> <span m="598950">It's</span>
  <span m="599520">an</span> <span m="599770">integral</span> <span m="600350">of</span>
  <span m="600530">x</span> <span m="600840">weighted</span> <span m="601200">by</span>
  <span m="601470">the</span> <span m="601610">pdf</span> <span m="602600">of</span>
  <span m="602750">x.</span> <span m="604740">I</span> <span m="605100">didn't</span>
  <span m="605230">put</span> <span m="605520">limits</span> <span m="605820">here,</span>
  <span m="605970">but</span> <span m="606160">this</span> <span m="606195">is</span>
  <span m="606230">an</span> <span m="606300">integral</span> <span m="606600">over</span>
  <span m="606770">this</span> <span m="607020">1/4</span> <span m="607290">of</span>
  <span m="607380">x,</span> <span m="610480">which</span> <span m="611250">would</span>
  <span m="611470">be</span> <span m="611880">minus</span> <span m="612210">infinity</span>
  <span m="612620">to</span> <span m="612720">infinity</span> <span m="613800">if</span>
  <span m="613990">x</span> <span m="614053">was</span> <span m="614116">a</span>
  <span m="614180">normal</span> <span m="614650">interval.</span> <span m="615580">If</span>
  <span m="615680">it</span> <span m="615750">was</span> <span m="615910">uniform,</span>
  <span m="616370">it</span> <span m="616450">would</span> <span m="616590">be</span>
  <span m="617010">an</span> <span m="617090">integral</span> <span m="617430">over</span>
  <span m="617620">the</span> <span m="617880">ab</span> <span m="618280">range,</span>
  <span m="618880">what</span> <span m="619290">this</span> <span m="619420">1/4</span>
  <span m="619440">of</span> <span m="619460">x</span> <span m="619480">would</span>
  <span m="620120">be.</span></p><p><span m="622380">So</span> <span m="622490">now</span>
  <span m="622820">what</span> <span m="622878">we're</span> <span m="622936">going</span>
  <span m="622994">to</span> <span m="623052">do</span> <span m="623110">is</span>
  <span m="623250">we're</span> <span m="623390">going</span> <span m="623540">to</span>
  <span m="623600">choose</span> <span m="623910">a</span> <span m="623970">random</span>
  <span m="624250">variable</span> <span m="626441">that</span> <span m="626938">we'll</span>
  <span m="627435">call</span> <span m="627932">z.</span> <span m="636390">And</span>
  <span m="637700">we're</span> <span m="637810">going</span> <span m="637940">to</span>
  <span m="638000">ask</span> <span m="638220">z</span> <span m="638820">to</span>
  <span m="638960">be</span> <span m="640480">non-negative,</span> <span m="641960">and</span>
  <span m="642210">we're</span> <span m="642430">going</span> <span m="642590">to</span>
  <span m="642750">choose</span> <span m="643080">it</span> <span m="645250">subject</span>
  <span m="645770">to</span> <span m="646040">the</span> <span m="646140">constraints</span>
  <span m="646595">that</span> <span m="648130">the</span> <span m="648340">expectation</span>
  <span m="649570">of</span> <span m="649970">z</span> <span m="653120">taken</span>
  <span m="653890">under</span> <span m="654280">the</span> <span m="654420">pdf--</span>
  <span m="655300">still</span> <span m="655530">the</span> <span m="656000">pdf</span>
  <span m="656300">here--</span> <span m="658660">of</span> <span m="658840">fx</span>
  <span m="660730">is</span> <span m="660900">equal</span> <span m="661110">to</span>
  <span m="661310">1.</span> <span m="664551">And</span> <span m="665580">why</span>
  <span m="665770">are</span> <span m="665810">we</span> <span m="665920">writing</span>
  <span m="666200">this?</span> <span m="666430">Well,</span> <span m="667510">what's</span>
  <span m="667740">the</span> <span m="667820">6th</span> <span m="668020">notation?</span>
  <span m="668610">It's</span> <span m="668720">the</span> <span m="669175">integral</span>
  <span m="669630">of</span> <span m="670995">z</span> <span m="672360">f</span> <span
  m="673195">sub</span> <span m="673670">x</span> <span m="674620">of</span> <span
  m="675095">x</span> <span m="675570">dx.</span> <span m="677470">That's</span> <span
  m="677710">the</span> <span m="677820">expectation</span> <span m="678790">of</span>
  <span m="679210">the</span> <span m="679310">random</span> <span m="679530">variable,</span>
  <span m="680040">v,</span> <span m="682110">under</span> <span m="682410">the</span>
  <span m="683130">pdf</span> <span m="684480">fx.</span></p><p><span m="688199">So</span>
  <span m="689690">if</span> <span m="690190">this</span> <span m="690600">is</span>
  <span m="691080">equal</span> <span m="691280">to</span> <span m="691480">1,</span>
  <span m="692535">maybe</span> <span m="693020">you</span> <span m="693150">can</span>
  <span m="693310">see</span> <span m="693430">that</span> <span m="693580">all</span>
  <span m="693750">we've</span> <span m="693990">done</span> <span m="694280">is</span>
  <span m="694460">really</span> <span m="694850">define</span> <span m="696340">another</span>
  <span m="696780">pdf</span> <span m="698740">that</span> <span m="698880">we</span>
  <span m="698960">can</span> <span m="699100">write</span> <span m="699290">as</span>
  <span m="699460">f</span> <span m="699720">sub</span> <span m="700217">z.</span>
  <span m="701211">Yep.</span> <span m="703700">Because</span> <span m="703920">it's</span>
  <span m="703960">going</span> <span m="704800">to</span> <span m="704870">satisfy</span>
  <span m="705270">the</span> <span m="705360">properties</span> <span m="705740">of</span>
  <span m="705800">a</span> <span m="705930">pdf.</span> <span m="706175">It's</span>
  <span m="706420">going</span> <span m="706540">to</span> <span m="708200">integrate</span>
  <span m="708520">to</span> <span m="708630">1.</span> <span m="709376">Is</span>
  <span m="710230">that</span> <span m="710430">OK?</span></p><p><span m="712800">AUDIENCE:</span>
  <span m="713274">[INAUDIBLE].</span></p><p><span m="717540">KAREN WILLCOX:</span>
  <span m="718020">z</span> <span m="718085">is</span> <span m="718150">going</span>
  <span m="718280">to</span> <span m="718350">be</span> <span m="718470">just</span>
  <span m="718700">another</span> <span m="719480">random</span> <span m="720259">variable.</span>
  <span m="727450">Yeah,</span> <span m="727720">so</span> <span m="729430">you</span>
  <span m="729570">can</span> <span m="729670">maybe</span> <span m="729860">just</span>
  <span m="730030">think</span> <span m="730230">of</span> <span m="730340">z</span>
  <span m="730730">as</span> <span m="731510">being</span> <span m="731750">defined</span>
  <span m="732140">on</span> <span m="732270">the</span> <span m="732330">same</span>
  <span m="732680">support</span> <span m="733370">if</span> <span m="733560">you</span>
  <span m="733690">want</span> <span m="733960">to,</span> <span m="735360">or</span>
  <span m="740430">I</span> <span m="740490">think</span> <span m="740690">this</span>
  <span m="740780">thing</span> <span m="741905">is</span> <span m="742330">allowed</span>
  <span m="742660">to</span> <span m="742740">be</span> <span m="742870">0</span>
  <span m="743060">in</span> <span m="743310">some</span> <span m="743460">places,</span>
  <span m="743860">but</span> <span m="744185">it's</span> <span m="744510">not</span>
  <span m="744700">allowed</span> <span m="745107">to</span> <span m="745514">be</span>
  <span m="745921">0</span> <span m="746330">everywhere.</span> <span m="746830">There</span>
  <span m="747000">are</span> <span m="747030">some</span> <span m="747210">conditions</span>
  <span m="747790">related</span> <span m="748060">to</span> <span m="748170">where</span>
  <span m="748460">z</span> <span m="748922">can</span> <span m="749384">be</span>
  <span m="749846">0.</span> <span m="753550">Is</span> <span m="753690">that</span>
  <span m="753830">OK</span> <span m="753970">for</span> <span m="754030">the</span>
  <span m="754090">lecturer</span> <span m="754103">to</span> <span m="754116">ask</span>
  <span m="754130">you</span> <span m="754473">a</span> <span m="755160">question?</span></p><p><span
  m="755611">AUDIENCE:</span> <span m="756062">[INAUDIBLE].</span></p><p><span m="759955">KAREN
  WILLCOX:</span> <span m="760350">Yeah.</span> <span m="760760">So</span> <span m="762170">I</span>
  <span m="762220">think</span> <span m="762450">the</span> <span m="762510">easiest</span>
  <span m="762980">thing</span> <span m="763065">is</span> <span m="763150">to</span>
  <span m="763620">think</span> <span m="763900">about</span> <span m="764050">x</span>
  <span m="764195">as</span> <span m="765300">having</span> <span m="765675">infinite</span>
  <span m="765860">support,</span> <span m="766280">then</span> <span m="766520">integrals</span>
  <span m="766630">away</span> <span m="766690">from</span> <span m="766820">minus</span>
  <span m="767130">infinity</span> <span m="767370">[INAUDIBLE].</span></p><p><span
  m="769410">So</span> <span m="770560">we</span> <span m="771050">haven't</span>
  <span m="771280">done</span> <span m="771510">anything</span> <span m="771750">yet.</span>
  <span m="771990">We've</span> <span m="772130">just</span> <span m="772460">manipulated</span>
  <span m="773560">things.</span> <span m="773860">So</span> <span m="773970">why</span>
  <span m="774100">are</span> <span m="774140">we</span> <span m="774230">doing</span>
  <span m="774460">this?</span> <span m="775010">So</span> <span m="775370">if</span>
  <span m="775470">we</span> <span m="775590">did</span> <span m="775860">this,</span>
  <span m="776160">we'd</span> <span m="776360">have</span> <span m="776470">to</span>
  <span m="776580">think</span> <span m="776830">about</span> <span m="777440">the</span>
  <span m="777510">mean</span> <span m="778090">of</span> <span m="778290">x,</span>
  <span m="778735">mu</span> <span m="779180">x,</span> <span m="780070">the</span>
  <span m="780190">thing</span> <span m="780420">here,</span> <span m="781730">which</span>
  <span m="782060">is,</span> <span m="783440">again,</span> <span m="783810">the</span>
  <span m="783920">expectation</span> <span m="784670">of</span> <span m="785227">x</span>
  <span m="786360">with</span> <span m="786620">respect</span> <span m="786905">to</span>
  <span m="787480">under</span> <span m="789260">its</span> <span m="789470">own</span>
  <span m="789780">pdf.</span> <span m="790850">And</span> <span m="790990">we</span>
  <span m="791070">said</span> <span m="791290">that</span> <span m="791420">this</span>
  <span m="791660">thing</span> <span m="791910">was</span> <span m="792250">integral</span>
  <span m="792720">of</span> <span m="792890">f</span> <span m="793590">times</span>
  <span m="794620">its</span> <span m="794800">pdf,</span> <span m="795815">weighted</span>
  <span m="796220">by</span> <span m="796380">pdf.</span></p><p><span m="798610">And</span>
  <span m="798790">so</span> <span m="799400">now</span> <span m="799600">what</span>
  <span m="799750">can</span> <span m="799890">we</span> <span m="800010">do?</span>
  <span m="800270">We</span> <span m="800390">can</span> <span m="801800">divide</span>
  <span m="802230">by</span> <span m="802340">z</span> <span m="803300">and</span>
  <span m="803390">multiply</span> <span m="803690">by</span> <span m="804163">z.</span>
  <span m="812220">Just</span> <span m="812490">multiply</span> <span m="812625">by</span>
  <span m="812760">1.</span> <span m="814432">And</span> <span m="815740">now</span>
  <span m="815980">we</span> <span m="816100">recognize</span> <span m="816700">that</span>
  <span m="816820">z</span> <span m="818770">f</span> <span m="818950">of</span> <span
  m="819070">x</span> <span m="819150">is</span> <span m="819600">just</span> <span
  m="819700">what</span> <span m="819870">we're</span> <span m="819950">now</span>
  <span m="820150">calling</span> <span m="820450">f</span> <span m="820640">of</span>
  <span m="820870">z,</span> <span m="821654">where</span> <span m="822148">this</span>
  <span m="822642">is</span> <span m="823136">x</span> <span m="823630">over</span>
  <span m="824124">z</span> <span m="824620">f</span> <span m="826580">of</span> <span
  m="826730">z</span> <span m="827240">dx.</span> <span m="834190">So</span> <span
  m="834510">all</span> <span m="834690">we</span> <span m="834780">did</span> <span
  m="834990">was</span> <span m="835160">multiply</span> <span m="835630">and</span>
  <span m="835800">divide</span> <span m="836090">by</span> <span m="836290">z,</span>
  <span m="837264">and</span> <span m="837751">then</span> <span m="838240">say</span>
  <span m="838297">that</span> <span m="838354">we're</span> <span m="838411">going</span>
  <span m="838468">to</span> <span m="838525">group</span> <span m="838620">the</span>
  <span m="838715">z</span> <span m="839770">times</span> <span m="840110">the</span>
  <span m="840370">pdf's</span> <span m="840630">of</span> <span m="840940">x</span>
  <span m="841160">together</span> <span m="841530">and</span> <span m="841998">[INAUDIBLE]</span>
  <span m="842466">f</span> <span m="842622">of</span> <span m="842778">z.</span>
  <span m="843870">And</span> <span m="844050">we</span> <span m="844270">can</span>
  <span m="844450">do</span> <span m="844580">that</span> <span m="844650">because</span>
  <span m="845590">[? opposite ?]</span> <span m="846000">constraint</span> <span
  m="846285">is</span> <span m="846570">that</span> <span m="847070">same</span> <span
  m="847710">as</span> <span m="847830">integrating</span> <span m="848190">to</span>
  <span m="848670">1.</span></p><p><span m="850110">So</span> <span m="851070">what</span>
  <span m="851240">is</span> <span m="851380">this</span> <span m="851590">guy</span>
  <span m="851810">here?</span> <span m="852190">This</span> <span m="852400">guy</span>
  <span m="852620">here</span> <span m="853180">is</span> <span m="853470">the</span>
  <span m="853610">expectation</span> <span m="854500">of</span> <span m="856060">something</span>
  <span m="856430">else</span> <span m="857800">with</span> <span m="858010">respect</span>
  <span m="858420">to</span> <span m="858530">the</span> <span m="859040">pdf</span>
  <span m="859440">of</span> <span m="859840">z,</span> <span m="860030">the</span>
  <span m="860150">density</span> <span m="860397">of</span> <span m="860645">z.</span>
  <span m="861140">What</span> <span m="861270">is</span> <span m="861380">it</span>
  <span m="861625">the</span> <span m="861870">expectation</span> <span m="862115">of?</span>
  <span m="863830">x</span> <span m="864060">over</span> <span m="864130">z?</span>
  <span m="865080">So</span> <span m="865210">this</span> <span m="865350">is</span>
  <span m="865450">the</span> <span m="865600">expectation</span> <span m="866490">of</span>
  <span m="867010">x</span> <span m="867670">over</span> <span m="867880">z,</span>
  <span m="869070">but</span> <span m="869230">now</span> <span m="869750">taken</span>
  <span m="871020">with</span> <span m="871250">respect</span> <span m="871820">to</span>
  <span m="873760">the</span> <span m="873860">pdf</span> <span m="874360">fd.</span></p><p><span
  m="881925">All</span> <span m="882410">right.</span> <span m="882610">So</span>
  <span m="882690">does</span> <span m="882715">this</span> <span m="882740">kind</span>
  <span m="882920">of</span> <span m="882990">feel</span> <span m="883160">like</span>
  <span m="883280">we're</span> <span m="883390">just</span> <span m="883550">moving</span>
  <span m="883920">chairs</span> <span m="884230">around?</span> <span m="886150">Yeah.</span>
  <span m="888050">That's</span> <span m="888240">why</span> <span m="888274">I</span>
  <span m="888308">said</span> <span m="888342">they</span> <span m="888376">sort</span>
  <span m="888410">of</span> <span m="888490">seem</span> <span m="888680">a</span>
  <span m="888710">little</span> <span m="888870">bit</span> <span m="889020">like</span>
  <span m="889200">tricks.</span> <span m="889770">Is</span> <span m="890035">anybody</span>
  <span m="890990">uncomfortable</span> <span m="891480">with</span> <span m="891590">anything</span>
  <span m="891880">that</span> <span m="892000">we've</span> <span m="892190">done?</span>
  <span m="893884">It's</span> <span m="894332">OK?</span> <span m="895230">We've</span>
  <span m="895420">put</span> <span m="896185">a</span> <span m="896480">1</span>
  <span m="896580">over</span> <span m="896990">d</span> <span m="897160">in</span>
  <span m="897300">here,</span> <span m="897610">and</span> <span m="897760">we've</span>
  <span m="898560">changed</span> <span m="900540">the</span> <span m="900580">pdf,</span>
  <span m="900620">the</span> <span m="900660">weighting</span> <span m="900990">and</span>
  <span m="901080">the</span> <span m="901160">integral</span> <span m="901660">to</span>
  <span m="901780">accommodate</span> <span m="902940">to</span> <span m="903070">make</span>
  <span m="903440">it</span> <span m="903590">equal</span> <span m="904034">to</span>
  <span m="904478">same.</span> <span m="904922">Yeah,</span> <span m="905144">Kevin?</span></p><p><span
  m="905366">AUDIENCE:</span> <span m="905810">[INAUDIBLE].</span></p><p><span m="906700">KAREN
  WILLCOX:</span> <span m="907020">The</span> <span m="907080">constraint</span> <span
  m="907420">we</span> <span m="907480">have</span> <span m="907590">here</span> <span
  m="907800">is</span> <span m="908140">that this is</span> <span m="908290">the</span>
  <span m="908770">expectation</span> <span m="908890">of</span> <span m="909080">[?
  d1 ?]</span> <span m="909200">of</span> <span m="909320">f</span> <span m="909440">of</span>
  <span m="909560">x</span> <span m="909710">is</span> <span m="909860">1.</span>
  <span m="913220">Well,</span> <span m="913450">this</span> <span m="913610">is</span>
  <span m="913720">going</span> <span m="913850">to</span> <span m="913960">be</span>
  <span m="914080">what</span> <span m="914460">leads</span> <span m="914700">us</span>
  <span m="914716">to</span> <span m="914733">find</span> <span m="915130">the</span>
  <span m="915599">pdf's.</span> <span m="917006">Yeah.</span></p><p><span m="917475">AUDIENCE:</span>
  <span m="917944">[INAUDIBLE].</span></p><p><span m="922170">KAREN WILLCOX:</span>
  <span m="922470">So</span> <span m="922630">why</span> <span m="923740">do</span>
  <span m="923850">we</span> <span m="924390">put</span> <span m="924540">[INAUDIBLE]</span>
  <span m="925200">underneath</span> <span m="925710">and</span> <span m="925810">then</span>
  <span m="926110">bring</span> <span m="926270">it</span> <span m="926460">about?</span>
  <span m="926850">So</span> <span m="927370">let's</span> <span m="927490">look</span>
  <span m="927550">at</span> <span m="927640">what</span> <span m="927770">we</span>
  <span m="928187">have.</span> <span m="929021">We</span> <span m="929440">have</span>
  <span m="930980">now</span> <span m="931140">two</span> <span m="931370">different</span>
  <span m="931700">ways</span> <span m="932190">to</span> <span m="932300">compute</span>
  <span m="932790">the</span> <span m="933370">mean</span> <span m="933746">of</span>
  <span m="934122">x.</span> <span m="934500">That's</span> <span m="934700">what</span>
  <span m="934800">we're</span> <span m="934980">after.</span> <span m="936320">We</span>
  <span m="936420">have</span> <span m="936860">[AUDIO OUT]</span> <span m="938560">what</span>
  <span m="938730">we</span> <span m="938840">normally</span> <span m="939170">think</span>
  <span m="939300">about,</span> <span m="939930">which</span> <span m="940140">is</span>
  <span m="940620">thinking</span> <span m="940900">about</span> <span m="941530">this</span>
  <span m="941860">mean</span> <span m="942220">as</span> <span m="942690">the</span>
  <span m="942800">expectation</span> <span m="943390">of</span> <span m="943510">x</span>
  <span m="944560">under</span> <span m="944890">the</span> <span m="945190">pdf.</span>
  <span m="947300">And</span> <span m="947440">now</span> <span m="947720">we</span>
  <span m="947820">have</span> <span m="947860">derived</span> <span m="948240">this</span>
  <span m="949480">alternate</span> <span m="950500">expression,</span> <span m="951390">which</span>
  <span m="951610">is</span> <span m="951760">the</span> <span m="951910">expectation</span>
  <span m="952390">of</span> <span m="953328">x</span> <span m="953786">over</span>
  <span m="954244">z</span> <span m="955160">where</span> <span m="955330">the</span>
  <span m="955560">expectation</span> <span m="956240">is</span> <span m="956410">taken</span>
  <span m="956670">now</span> <span m="957170">with</span> <span m="958680">the</span>
  <span m="958780">pdf</span> <span m="959310">f</span> <span m="959630">of</span>
  <span m="959990">z,</span> <span m="960350">the</span> <span m="960560">z,</span>
  <span m="961270">and</span> <span m="961380">the</span> <span m="961450">weighting.</span></p><p><span
  m="962564">So</span> <span m="963950">this</span> <span m="964100">is</span> <span
  m="964190">what</span> <span m="964330">we've</span> <span m="964460">been</span>
  <span m="964710">talking</span> <span m="964890">about.</span> <span m="965420">How</span>
  <span m="967130">do</span> <span m="967220">we</span> <span m="967380">estimate</span>
  <span m="967860">the</span> <span m="967930">mean</span> <span m="968240">this</span>
  <span m="968410">way?</span> <span m="968890">Well,</span> <span m="969180">we</span>
  <span m="969460">sample</span> <span m="972708">x</span> <span m="974120">by</span>
  <span m="974280">drawing</span> <span m="974960">samples</span> <span m="975570">from</span>
  <span m="976130">the</span> <span m="976200">distribution</span> <span m="979182">f</span>
  <span m="979680">sub</span> <span m="979800">x.</span> <span m="981790">We</span>
  <span m="981910">define</span> <span m="982360">the</span> <span m="982430">pdf</span>
  <span m="982890">of</span> <span m="983010">x</span> <span m="983460">input.</span>
  <span m="984460">We</span> <span m="984580">draw</span> <span m="984820">samples</span>
  <span m="985400">from</span> <span m="985740">it.</span> <span m="993110">We</span>
  <span m="993170">estimate</span> <span m="993610">the</span> <span m="993690">mean</span>
  <span m="993960">to</span> <span m="994040">be</span> <span m="994140">the</span>
  <span m="994210">sample</span> <span m="994610">mean.</span> <span m="999080">And</span>
  <span m="1011890">the</span> <span m="1012330">variance</span> <span m="1012890">of</span>
  <span m="1013030">the</span> <span m="1013100">corresponding</span> <span m="1013790">estimator</span>
  <span m="1014400">to</span> <span m="1014480">the</span> <span m="1014620">estimator</span>
  <span m="1015130">variance</span> <span m="1017910">is</span> <span m="1018080">what?</span></p><p><span
  m="1025980">What</span> <span m="1026099">was</span> <span m="1026210">on</span>
  <span m="1026339">the</span> <span m="1026793">numerator?</span> <span m="1028609">Not</span>
  <span m="1028982">mu</span> <span m="1029355">x.</span></p><p><span m="1030164">AUDIENCE:</span>
  <span m="1030598">[INAUDIBLE].</span></p><p><span m="1031466">KAREN WILLCOX:</span>
  <span m="1031900">Yeah,</span> <span m="1032140">it's</span> <span m="1032410">[INAUDIBLE]</span>
  <span m="1032569">squared.</span> <span m="1032719">So</span> <span m="1032869">we'll</span>
  <span m="1032910">call</span> <span m="1033180">it</span> <span m="1033260">the</span>
  <span m="1033329">variance</span> <span m="1034800">of</span> <span m="1036069">x.</span>
  <span m="1037540">And</span> <span m="1039109">again,</span> <span m="1039609">I'm</span>
  <span m="1039770">going</span> <span m="1039880">to</span> <span m="1039945">put</span>
  <span m="1040010">the</span> <span m="1040099">subjects</span> <span m="1040499">here</span>
  <span m="1040900">just</span> <span m="1040970">to</span> <span m="1041120">denote.</span>
  <span m="1041195">So</span> <span m="1041270">that's</span> <span m="1041650">what</span>
  <span m="1041770">we</span> <span m="1041869">saw</span> <span m="1042030">before.</span>
  <span m="1044810">Actually,</span> <span m="1045060">we</span> <span m="1045170">sampled</span>
  <span m="1045540">inputs</span> <span m="1045795">and</span> <span m="1046050">we</span>
  <span m="1046230">propagated</span> <span m="1046750">them</span> <span m="1046890">through</span>
  <span m="1047250">to</span> <span m="1047390">the</span> <span m="1047569">outputs,</span>
  <span m="1048099">but</span> <span m="1049420">basically,</span> <span m="1049820">we're</span>
  <span m="1049940">just</span> <span m="1050690">sampling</span> <span m="1051470">from</span>
  <span m="1052780">this</span> <span m="1053180">density,</span> <span m="1055010">and</span>
  <span m="1055730">given</span> <span m="1056010">the</span> <span m="1056050">sample</span>
  <span m="1056400">mean</span> <span m="1057930">and</span> <span m="1058240">our</span>
  <span m="1058420">estimator</span> <span m="1060010">and</span> <span m="1060115">the</span>
  <span m="1060220">estimator</span> <span m="1060580">of</span> <span m="1060730">variance</span>
  <span m="1061170">with</span> <span m="1061300">the</span> <span m="1061380">[INAUDIBLE].</span></p><p><span
  m="1063462">So</span> <span m="1064320">what</span> <span m="1064570">we've</span>
  <span m="1064950">done</span> <span m="1065240">here</span> <span m="1065490">is</span>
  <span m="1065860">defined</span> <span m="1068050">a</span> <span m="1068090">parallel</span>
  <span m="1068315">pattern</span> <span m="1068540">analogous</span> <span m="1068805">[?
  path. ?]</span> <span m="1069500">So</span> <span m="1069610">what</span> <span
  m="1069830">we</span> <span m="1070050">do</span> <span m="1070270">here?</span>
  <span m="1071220">We're</span> <span m="1071370">going</span> <span m="1071500">to</span>
  <span m="1071590">sample</span> <span m="1074890">x</span> <span m="1075100">over</span>
  <span m="1075560">z,</span> <span m="1076940">and</span> <span m="1077860">we're</span>
  <span m="1078780">going</span> <span m="1079240">to</span> <span m="1079320">sample</span>
  <span m="1079740">it</span> <span m="1080201">under</span> <span m="1082970">now</span>
  <span m="1083380">the</span> <span m="1083500">distribution</span> <span m="1084290">or</span>
  <span m="1084400">the</span> <span m="1084820">density</span> <span m="1086080">xz.</span>
  <span m="1091050">And</span> <span m="1092480">again,</span> <span m="1093000">we</span>
  <span m="1094850">take</span> <span m="1095070">the</span> <span m="1095180">samples,</span>
  <span m="1095970">we</span> <span m="1096080">take</span> <span m="1096260">the</span>
  <span m="1096320">sample</span> <span m="1096640">mean.</span> <span m="1097610">That</span>
  <span m="1097740">would</span> <span m="1097840">be</span> <span m="1097910">our</span>
  <span m="1098050">estimate.</span> <span m="1099310">And</span> <span m="1099820">the</span>
  <span m="1099860">variance</span> <span m="1100390">of</span> <span m="1100520">that</span>
  <span m="1100730">estimator,</span> <span m="1102830">the</span> <span m="1102980">estimator</span>
  <span m="1103440">variance,</span> <span m="1106600">is</span> <span m="1106800">now</span>
  <span m="1107120">going</span> <span m="1107290">to</span> <span m="1107360">be</span>
  <span m="1107450">what?</span> <span m="1114280">Variance</span> <span m="1115450">of</span>
  <span m="1116066">x</span> <span m="1116452">over</span> <span m="1116840">z</span>
  <span m="1120310">under</span> <span m="1120570">this</span> <span m="1120770">divided</span>
  <span m="1121430">by</span> <span m="1122410">[? N. ?]</span></p><p><span m="1126100">And</span>
  <span m="1126360">now</span> <span m="1126520">maybe</span> <span m="1126760">this</span>
  <span m="1126930">is</span> <span m="1127010">where</span> <span m="1127290">you</span>
  <span m="1127370">see</span> <span m="1127680">why</span> <span m="1127900">these</span>
  <span m="1128180">tricks</span> <span m="1128550">work</span> <span m="1129600">because</span>
  <span m="1131035">putting</span> <span m="1131470">the</span> <span m="1131695">d</span>
  <span m="1131920">in</span> <span m="1132170">the</span> <span m="1132240">denominator</span>
  <span m="1132820">and</span> <span m="1132910">bringing</span> <span m="1133070">it</span>
  <span m="1133230">out</span> <span m="1133350">here</span> <span m="1133620">didn't</span>
  <span m="1133950">change</span> <span m="1134350">what</span> <span m="1134490">we're</span>
  <span m="1134620">estimating.</span> <span m="1135320">These</span> <span m="1135980">two</span>
  <span m="1136080">expressions</span> <span m="1136520">are</span> <span m="1136550">equal.</span>
  <span m="1140170">I</span> <span m="1140390">like</span> <span m="1140890">to</span>
  <span m="1141070">think</span> <span m="1141330">about</span> <span m="1141570">it</span>
  <span m="1141660">is</span> <span m="1141800">that</span> <span m="1142040">because</span>
  <span m="1142270">of</span> <span m="1142340">the</span> <span m="1142440">way</span>
  <span m="1142720">that</span> <span m="1142880">variance</span> <span m="1143340">behaves</span>
  <span m="1143640">non-linearly,</span> <span m="1145650">pulling</span> <span m="1145930">the</span>
  <span m="1146010">z</span> <span m="1146260">under</span> <span m="1146530">and</span>
  <span m="1146620">putting</span> <span m="1146830">it</span> <span m="1146930">out</span>
  <span m="1147140">here</span> <span m="1147340">in</span> <span m="1147510">front</span>
  <span m="1148620">does</span> <span m="1148800">not</span> <span m="1149060">mean</span>
  <span m="1149330">that</span> <span m="1149440">these</span> <span m="1149710">two</span>
  <span m="1149870">things</span> <span m="1150120">are</span> <span m="1150150">going</span>
  <span m="1150270">to</span> <span m="1150330">be</span> <span m="1150720">equal.</span>
  <span m="1151500">And</span> <span m="1151890">maybe</span> <span m="1152190">you</span>
  <span m="1152280">see</span> <span m="1152430">there.</span> <span m="1152570">You</span>
  <span m="1152690">could</span> <span m="1152810">drive</span> <span m="1153070">me</span>
  <span m="1153170">crazy</span> <span m="1153590">when</span> <span m="1153750">I</span>
  <span m="1153810">was</span> <span m="1153980">learning</span> <span m="1154200">statistics</span>
  <span m="1154515">is</span> <span m="1154830">that</span> <span m="1155850">things</span>
  <span m="1156070">like</span> <span m="1156250">means</span> <span m="1156570">would</span>
  <span m="1156690">behave</span> <span m="1157040">in</span> <span m="1157120">kind</span>
  <span m="1157280">of</span> <span m="1157350">this</span> <span m="1157860">linear</span>
  <span m="1158370">way</span> <span m="1158630">that</span> <span m="1158780">made</span>
  <span m="1158990">thins,</span> <span m="1159480">but</span> <span m="1159680">the</span>
  <span m="1159750">variance</span> <span m="1160560">never</span> <span m="1160640">seemed</span>
  <span m="1161230">to</span> <span m="1161360">be</span> <span m="1163560">doing</span>
  <span m="1164100">the</span> <span m="1164180">sensible</span> <span m="1164630">thing.</span>
  <span m="1165540">So</span> <span m="1165660">basically</span> <span m="1166040">we're</span>
  <span m="1166100">going</span> <span m="1166220">to</span> <span m="1166300">exploit</span>
  <span m="1166650">that.</span></p><p><span m="1166840">So</span> <span m="1166940">again,</span>
  <span m="1167360">we</span> <span m="1167480">can</span> <span m="1168510">do</span>
  <span m="1168640">this</span> <span m="1168800">manipulation</span> <span m="1169550">with</span>
  <span m="1169680">this</span> <span m="1169860">other</span> <span m="1170030">variable,</span>
  <span m="1170410">z,</span> <span m="1170870">and</span> <span m="1170990">not</span>
  <span m="1171320">change</span> <span m="1171800">the</span> <span m="1171860">estimate,</span>
  <span m="1172450">still</span> <span m="1172720">be</span> <span m="1172885">getting</span>
  <span m="1173050">after</span> <span m="1173280">the</span> <span m="1173350">thing</span>
  <span m="1173570">we</span> <span m="1173680">want.</span> <span m="1174770">But</span>
  <span m="1175260">if</span> <span m="1175440">we</span> <span m="1175670">choose</span>
  <span m="1176010">z</span> <span m="1176240">in</span> <span m="1176330">the</span>
  <span m="1176410">right</span> <span m="1176580">way,</span> <span m="1176810">and</span>
  <span m="1176860">we'll</span> <span m="1177010">talk</span> <span m="1177160">about</span>
  <span m="1177370">how</span> <span m="1177440">to</span> <span m="1177650">do</span>
  <span m="1177780">that,</span> <span m="1178760">we</span> <span m="1178800">could</span>
  <span m="1179710">make</span> <span m="1179970">this</span> <span m="1180030">smaller,</span>
  <span m="1180840">which</span> <span m="1180990">means,</span> <span m="1181850">again,</span>
  <span m="1182150">for</span> <span m="1182300">a</span> <span m="1182350">given</span>
  <span m="1182710">number</span> <span m="1182920">of</span> <span m="1183050">samples,</span>
  <span m="1184360">if</span> <span m="1184520">this</span> <span m="1184710">is</span>
  <span m="1184830">smaller</span> <span m="1185300">than</span> <span m="1185540">this,</span>
  <span m="1186730">then</span> <span m="1187130">our</span> <span m="1187610">estimates</span>
  <span m="1188170">are</span> <span m="1188220">going</span> <span m="1188340">to</span>
  <span m="1188410">be</span> <span m="1188570">tighter.</span> <span m="1190590">Or</span>
  <span m="1191310">to</span> <span m="1191510">achieve</span> <span m="1191910">a</span>
  <span m="1191990">given</span> <span m="1193060">confidence</span> <span m="1193790">in</span>
  <span m="1193980">the</span> <span m="1194110">estimator,</span> <span m="1194920">we</span>
  <span m="1195060">could</span> <span m="1195230">take</span> <span m="1195530">less</span>
  <span m="1195840">samples</span> <span m="1196430">here</span> <span m="1197290">than</span>
  <span m="1197470">doing</span> <span m="1197670">it</span> <span m="1197770">this</span>
  <span m="1197940">way.</span> <span m="1200090">Yeah.</span></p><p><span m="1202820">So</span>
  <span m="1205810">We'll</span> <span m="1205980">talk</span> <span m="1206180">about</span>
  <span m="1206580">sort</span> <span m="1206740">of</span> <span m="1206840">the</span>
  <span m="1207310">general</span> <span m="1207670">ideas,</span> <span m="1209840">and</span>
  <span m="1210010">then</span> <span m="1210130">I'll</span> <span m="1210220">show</span>
  <span m="1210380">you</span> <span m="1210670">exactly</span> <span m="1211190">how</span>
  <span m="1211450">you</span> <span m="1211560">might</span> <span m="1211720">come</span>
  <span m="1211890">up</span> <span m="1212020">with</span> <span m="1212240">a</span>
  <span m="1212280">z</span> <span m="1213212">for</span> <span m="1213680">probabilities.</span>
  <span m="1215210">But</span> <span m="1215370">the</span> <span m="1215450">general</span>
  <span m="1215740">ideas</span> <span m="1216180">are</span> <span m="1216400">first</span>
  <span m="1216680">of</span> <span m="1216820">all,</span> <span m="1216960">that</span>
  <span m="1217220">some</span> <span m="1217690">values</span> <span m="1218250">of</span>
  <span m="1218500">x</span> <span m="1218830">in</span> <span m="1219160">the</span>
  <span m="1219240">Monte</span> <span m="1219480">Carlo</span> <span m="1219870">simulation</span>
  <span m="1221380">are</span> <span m="1221440">going</span> <span m="1221560">to</span>
  <span m="1221630">be</span> <span m="1221740">more</span> <span m="1222040">important</span>
  <span m="1222680">for</span> <span m="1222880">estimating</span> <span m="1224250">the</span>
  <span m="1224360">parameter.</span> <span m="1225230">The</span> <span m="1225320">mean</span>
  <span m="1225450">is</span> <span m="1225580">not</span> <span m="1225730">a</span>
  <span m="1225760">very</span> <span m="1225940">good</span> <span m="1226110">example,</span>
  <span m="1226850">but</span> <span m="1227560">you</span> <span m="1227670">can</span>
  <span m="1227770">imagine</span> <span m="1228050">if</span> <span m="1228150">we're</span>
  <span m="1228220">talking</span> <span m="1228430">about</span> <span m="1228590">tail</span>
  <span m="1228860">probabilities,</span> <span m="1230410">we</span> <span m="1230540">want</span>
  <span m="1230720">to</span> <span m="1230780">get</span> <span m="1231050">more</span>
  <span m="1232380">samples</span> <span m="1232880">around</span> <span m="1233390">that</span>
  <span m="1233910">failure</span> <span m="1234220">probability.</span></p><p><span
  m="1236450">What</span> <span m="1236650">goes</span> <span m="1236840">on</span>
  <span m="1237040">over</span> <span m="1237190">here</span> <span m="1237460">we</span>
  <span m="1237530">don't</span> <span m="1237680">really</span> <span m="1237920">necessarily</span>
  <span m="1238420">care</span> <span m="1238690">about</span> <span m="1239860">because</span>
  <span m="1240100">it's</span> <span m="1240330">like</span> <span m="1240560">doesn't</span>
  <span m="1240910">fail,</span> <span m="1241040">it</span> <span m="1241170">doesn't</span>
  <span m="1241470">fail,</span> <span m="1241595">it</span> <span m="1241720">doesn't</span>
  <span m="1242080">fail.</span> <span m="1243652">So</span> <span m="1244096">the</span>
  <span m="1244207">idea</span> <span m="1244318">is</span> <span m="1244429">that</span>
  <span m="1244540">some</span> <span m="1244760">values</span> <span m="1245040">of</span>
  <span m="1245150">x</span> <span m="1245380">are</span> <span m="1245430">going</span>
  <span m="1245550">to</span> <span m="1245620">be</span> <span m="1245730">more</span>
  <span m="1245940">important,</span> <span m="1246680">and</span> <span m="1246860">what</span>
  <span m="1247000">we</span> <span m="1247110">want</span> <span m="1247270">to</span>
  <span m="1247340">do</span> <span m="1247610">when</span> <span m="1247780">we</span>
  <span m="1247900">choose</span> <span m="1249330">the</span> <span m="1249540">z</span>
  <span m="1249830">here</span> <span m="1250180">is</span> <span m="1250370">to</span>
  <span m="1250510">somehow</span> <span m="1251040">emphasize</span> <span m="1252010">those</span>
  <span m="1252200">more</span> <span m="1252360">important</span> <span m="1252810">values.</span>
  <span m="1254630">And</span> <span m="1254830">so</span> <span m="1254980">really</span>
  <span m="1255220">what</span> <span m="1255350">it's</span> <span m="1255470">going</span>
  <span m="1255590">to</span> <span m="1255660">come</span> <span m="1255840">down</span>
  <span m="1256090">to</span> <span m="1256280">is</span> <span m="1256400">how</span>
  <span m="1256530">do</span> <span m="1256630">we</span> <span m="1256750">choose</span>
  <span m="1257070">z</span> <span m="1257330">again</span> <span m="1258480">so</span>
  <span m="1258670">that</span> <span m="1258950">this</span> <span m="1259230">estimated</span>
  <span m="1259650">variance</span> <span m="1260190">is</span> <span m="1260370">going</span>
  <span m="1260490">to</span> <span m="1260560">be</span> <span m="1260740">less</span>
  <span m="1261090">than</span> <span m="1261310">this</span> <span m="1261450">guy.</span>
  <span m="1263070">And</span> <span m="1263240">we</span> <span m="1263340">will</span>
  <span m="1263490">talk</span> <span m="1263720">about</span> <span m="1263970">that</span>
  <span m="1264230">in</span> <span m="1265350">flow</span> <span m="1265800">probabilities.</span></p><p><span
  m="1272900">So</span> <span m="1273370">any</span> <span m="1273990">questions?</span>
  <span m="1280600">I</span> <span m="1280710">didn't</span> <span m="1280880">ask</span>
  <span m="1281110">you</span> <span m="1281190">at</span> <span m="1281225">the</span>
  <span m="1281260">beginning</span> <span m="1281520">of</span> <span m="1281590">class,</span>
  <span m="1281895">did</span> <span m="1282200">Professor</span> <span m="1282330">[?
  Nguyen ?]</span> <span m="1282460">talk</span> <span m="1282660">about</span> <span
  m="1282860">importance</span> <span m="1283125">sampling</span> <span m="1283390">in</span>
  <span m="1283720">1609?</span> <span m="1285410">No?</span> <span m="1285885">Just</span>
  <span m="1286835">as</span> <span m="1287310">well.</span></p><p><span m="1289690">All</span>
  <span m="1289770">right.</span> <span m="1289990">So</span> <span m="1290110">let's</span>
  <span m="1290480">talk</span> <span m="1291020">about--</span> <span m="1291460">this</span>
  <span m="1291600">is</span> <span m="1291870">3.2,</span> <span m="1295520">importance</span>
  <span m="1296020">sampling</span> <span m="1296970">for</span> <span m="1297220">probability</span>
  <span m="1297950">estimation.</span> <span m="1299410">And</span> <span m="1299540">hopefully,</span>
  <span m="1299950">maybe</span> <span m="1300160">it</span> <span m="1300240">will</span>
  <span m="1300940">make</span> <span m="1301210">this</span> <span m="1301350">a</span>
  <span m="1301410">little</span> <span m="1301600">bit</span> <span m="1301760">more</span>
  <span m="1302000">concrete</span> <span m="1302520">for</span> <span m="1302800">you.</span>
  <span m="1310010">So</span> <span m="1319930">what</span> <span m="1320130">did</span>
  <span m="1320210">we</span> <span m="1320380">already</span> <span m="1320660">see?</span>
  <span m="1320960">We</span> <span m="1321130">saw</span> <span m="1321590">that</span>
  <span m="1323790">the</span> <span m="1323890">probability</span> <span m="1324630">of</span>
  <span m="1324730">A,</span> <span m="1325542">where</span> <span m="1325948">A</span>
  <span m="1326354">is</span> <span m="1326760">some</span> <span m="1327330">event</span>
  <span m="1327850">that</span> <span m="1327930">we're</span> <span m="1328030">interested</span>
  <span m="1328440">in</span> <span m="1329322">is</span> <span m="1330800">estimated</span>
  <span m="1331150">by</span> <span m="1331560">a</span> <span m="1331810">Monte</span>
  <span m="1332284">Carlo,</span> <span m="1334654">or</span> <span m="1335130">can</span>
  <span m="1335420">be</span> <span m="1335550">estimated</span> <span m="1335760">by</span>
  <span m="1335960">a</span> <span m="1336070">Monte</span> <span m="1336320">Carlo,</span>
  <span m="1337950">with</span> <span m="1340320">an</span> <span m="1340450">estimator</span>
  <span m="1340740">that</span> <span m="1341030">we'll</span> <span m="1341277">call</span>
  <span m="1341525">P</span> <span m="1342020">hat</span> <span m="1343505">A.</span></p><p><span
  m="1347960">So</span> <span m="1350940">let's</span> <span m="1351550">think</span>
  <span m="1351800">about</span> <span m="1352380">the</span> <span m="1354120">case</span>
  <span m="1354470">where,</span> <span m="1354930">again,</span> <span m="1355110">we're</span>
  <span m="1355170">interested</span> <span m="1355560">in</span> <span m="1355670">the</span>
  <span m="1356253">probability</span> <span m="1356596">of</span> <span m="1356940">failures,</span>
  <span m="1357438">so</span> <span m="1357936">A</span> <span m="1358434">is</span>
  <span m="1358932">the</span> <span m="1359430">event</span> <span m="1361296">where,</span>
  <span m="1362282">say</span> <span m="1363270">y</span> <span m="1363880">is</span>
  <span m="1364020">greater</span> <span m="1364350">than</span> <span m="1364520">y</span>
  <span m="1364944">current.</span> <span m="1365792">So</span> <span m="1366216">y</span>
  <span m="1366428">is</span> <span m="1366640">some</span> <span m="1366870">output</span>
  <span m="1367180">of</span> <span m="1367620">interest.</span> <span m="1367825">It's</span>
  <span m="1368030">the</span> <span m="1368120">temperature</span> <span m="1368730">in</span>
  <span m="1368910">[? blades, ?]</span> <span m="1369820">and</span> <span m="1370010">we're</span>
  <span m="1370880">interested</span> <span m="1371390">in</span> <span m="1371510">looking</span>
  <span m="1371880">at</span> <span m="1372010">when</span> <span m="1372740">that</span>
  <span m="1372940">temperature</span> <span m="1373390">exceeds</span> <span m="1373990">some</span>
  <span m="1374160">critical</span> <span m="1374490">value.</span> <span m="1378685">So</span>
  <span m="1379180">this</span> <span m="1379415">shows</span> <span m="1379650">up</span>
  <span m="1379810">often,</span> <span m="1380280">and</span> <span m="1380670">if</span>
  <span m="1380830">we</span> <span m="1380940">are</span> <span m="1381100">looking</span>
  <span m="1381420">at</span> <span m="1381520">a</span> <span m="1381570">probability</span>
  <span m="1382170">of</span> <span m="1382330">failure.</span></p><p><span m="1388160">So</span>
  <span m="1388370">we're</span> <span m="1388430">going</span> <span m="1388550">to</span>
  <span m="1388670">define</span> <span m="1391248">an</span> <span m="1391720">indicator</span>
  <span m="1392290">function.</span> <span m="1392820">Usually</span> <span m="1393200">when</span>
  <span m="1393360">you're</span> <span m="1393520">working</span> <span m="1393830">with</span>
  <span m="1393990">probabilities</span> <span m="1395000">and</span> <span m="1395453">if</span>
  <span m="1395906">you're</span> <span m="1396360">told</span> <span m="1396430">to</span>
  <span m="1396570">find</span> <span m="1396710">an</span> <span m="1396800">indicator</span>
  <span m="1397150">function,</span> <span m="1397550">you</span> <span m="1397620">guys</span>
  <span m="1397995">should</span> <span m="1398182">have</span> <span m="1398370">seen</span>
  <span m="1398660">those</span> <span m="1398950">in</span> <span m="1399010">1609,</span>
  <span m="1399495">yes?</span> <span m="1402410">In</span> <span m="1402685">6041.</span>
  <span m="1410264">So</span> <span m="1410750">the</span> <span m="1410880">indicator</span>
  <span m="1411240">function,</span> <span m="1411730">i,</span> <span m="1411985">is</span>
  <span m="1412240">the</span> <span m="1412310">function</span> <span m="1412830">of</span>
  <span m="1413210">Ai.</span> <span m="1414000">So</span> <span m="1414110">this</span>
  <span m="1414280">is</span> <span m="1414380">going</span> <span m="1414510">to</span>
  <span m="1414590">be</span> <span m="1417550">corresponding</span> <span m="1418120">to</span>
  <span m="1418210">the</span> <span m="1418320">i-th</span> <span m="1418690">sample</span>
  <span m="1419260">in</span> <span m="1419290">our</span> <span m="1419767">Monte</span>
  <span m="1420244">Carlo.</span> <span m="1422630">So</span> <span m="1422770">we're</span>
  <span m="1422900">drawing</span> <span m="1423640">a</span> <span m="1423720">sample,</span>
  <span m="1424380">where</span> <span m="1424660">running</span> <span m="1425010">it</span>
  <span m="1425360">through</span> <span m="1425710">our</span> <span m="1426060">[?
  planet ?]</span> <span m="1426260">element</span> <span m="1426630">code,</span>
  <span m="1427630">and</span> <span m="1427820">we're</span> <span m="1427940">looking</span>
  <span m="1428280">to</span> <span m="1428350">see</span> <span m="1428610">whether</span>
  <span m="1429125">event</span> <span m="1429400">A</span> <span m="1429890">happens.</span></p><p><span
  m="1431570">And</span> <span m="1431830">indicator</span> <span m="1432370">function</span>
  <span m="1432750">says</span> <span m="1433310">if</span> <span m="1433490">event</span>
  <span m="1433580">A</span> <span m="1434064">happens,</span> <span m="1435032">then</span>
  <span m="1436000">takes</span> <span m="1436240">a</span> <span m="1436280">value</span>
  <span m="1436560">of</span> <span m="1436680">1,</span> <span m="1438640">if</span>
  <span m="1438850">not,</span> <span m="1439080">take</span> <span m="1439545">a</span>
  <span m="1439638">value</span> <span m="1439731">of</span> <span m="1439824">0.</span>
  <span m="1439917">So</span> <span m="1440010">this</span> <span m="1440160">is</span>
  <span m="1440260">going</span> <span m="1440400">to</span> <span m="1440490">be</span>
  <span m="1440800">if</span> <span m="1441110">the</span> <span m="1441230">corresponding</span>
  <span m="1442500">sample</span> <span m="1442890">of</span> <span m="1443010">y,</span>
  <span m="1443520">the</span> <span m="1443630">yi</span> <span m="1445420">exceeds</span>
  <span m="1445940">y</span> <span m="1446090">current,</span> <span m="1448050">and</span>
  <span m="1448220">if</span> <span m="1448430">not,</span> <span m="1448640">then</span>
  <span m="1448820">we</span> <span m="1448910">can</span> <span m="1448995">set</span>
  <span m="1449080">indicator</span> <span m="1449540">function</span> <span m="1452790">to</span>
  <span m="1452910">be</span> <span m="1453080">0.</span> <span m="1453522">So</span>
  <span m="1453964">indicator</span> <span m="1454406">function</span> <span m="1454517">is</span>
  <span m="1454628">set</span> <span m="1454739">to</span> <span m="1454850">0.</span>
  <span m="1455280">1</span> <span m="1455550">result.</span> <span m="1456210">Failed.</span>
  <span m="1457430">Didn't</span> <span m="1457720">fail.</span> <span m="1458686">A</span>
  <span m="1459170">happened.</span> <span m="1459580">A</span> <span m="1459790">didn't</span>
  <span m="1460010">happen.</span></p><p><span m="1461878">AUDIENCE:</span> <span
  m="1462345">[INAUDIBLE].</span></p><p><span m="1464213">KAREN WILLCOX:</span> <span
  m="1464680">i</span> <span m="1464880">to</span> <span m="1465000">the</span> <span
  m="1465120">range.</span> <span m="1465405">i</span> <span m="1465690">is</span>
  <span m="1465850">either</span> <span m="1466010">0</span> <span m="1466508">or</span>
  <span m="1467006">1.</span></p><p><span m="1468500">AUDIENCE:</span> <span m="1468998">[INAUDIBLE].</span></p><p><span
  m="1470990">KAREN WILLCOX:</span> <span m="1471488">Oh,</span> <span m="1471990">little</span>
  <span m="1472220">i.</span> <span m="1472550">Sorry.</span> <span m="1472800">Yeah,</span>
  <span m="1472990">that's</span> <span m="1473482">right.</span> <span m="1474958">Little</span>
  <span m="1475450">i</span> <span m="1475780">from</span> <span m="1475990">1</span>
  <span m="1476400">up</span> <span m="1476862">to</span> <span m="1477324">n.</span>
  <span m="1477786">Sorry.</span> <span m="1481020">So</span> <span m="1481490">if</span>
  <span m="1482510">we</span> <span m="1482710">just</span> <span m="1482850">think</span>
  <span m="1482980">about</span> <span m="1483170">these</span> <span m="1483470">things</span>
  <span m="1483840">in</span> <span m="1483940">this</span> <span m="1484130">way,</span>
  <span m="1485280">then</span> <span m="1485640">the</span> <span m="1485710">reason</span>
  <span m="1485960">we</span> <span m="1486100">do</span> <span m="1486240">this</span>
  <span m="1486460">is</span> <span m="1486570">because</span> <span m="1486830">then</span>
  <span m="1486970">our</span> <span m="1488990">estimator</span> <span m="1490080">P</span>
  <span m="1490370">hat</span> <span m="1490505">of</span> <span m="1490640">A--</span>
  <span m="1490980">what</span> <span m="1493720">was</span> <span m="1493850">he</span>
  <span m="1493970">estimator</span> <span m="1494390">for</span> <span m="1494480">the</span>
  <span m="1494550">probability?</span> <span m="1498070">What</span> <span m="1498180">was</span>
  <span m="1498510">it?</span> <span m="1504540">Yep.</span> <span m="1504790">So</span>
  <span m="1504960">the</span> <span m="1505050">number</span> <span m="1505510">of</span>
  <span m="1506030">samples</span> <span m="1506480">where</span> <span m="1506670">A</span>
  <span m="1506790">occurred</span> <span m="1507285">just</span> <span m="1507780">divided</span>
  <span m="1507860">by</span> <span m="1507940">the</span> <span m="1508070">[INAUDIBLE]</span>
  <span m="1508510">number.</span></p><p><span m="1509540">So</span> <span m="1509660">what</span>
  <span m="1509770">does</span> <span m="1509920">that</span> <span m="1510070">look</span>
  <span m="1510221">like?</span> <span m="1512927">What</span> <span m="1513380">does</span>
  <span m="1513490">that</span> <span m="1513660">look</span> <span m="1513810">like</span>
  <span m="1513970">in</span> <span m="1514060">terms</span> <span m="1514280">of</span>
  <span m="1514340">the</span> <span m="1514790">indicator</span> <span m="1515230">function?</span>
  <span m="1515670">I'll</span> <span m="1515790">put</span> <span m="1515890">the</span>
  <span m="1515960">denominator</span> <span m="1516285">in</span> <span m="1516610">there.</span>
  <span m="1518150">What's</span> <span m="1518350">the</span> <span m="1518420">numerator?</span>
  <span m="1520236">Yeah.</span> <span m="1520690">Just</span> <span m="1520940">the</span>
  <span m="1521190">sum</span> <span m="1521520">of</span> <span m="1521970">the</span>
  <span m="1522420">iA's.</span> <span m="1523320">So</span> <span m="1523770">it's</span>
  <span m="1524150">1</span> <span m="1524465">over</span> <span m="1524780">N.</span>
  <span m="1525670">The</span> <span m="1525770">sum</span> <span m="1526130">equals</span>
  <span m="1526430">1</span> <span m="1526735">to</span> <span m="1527040">capital</span>
  <span m="1527460">N</span> <span m="1527740">of</span> <span m="1530340">iA's.</span>
  <span m="1532660">In</span> <span m="1533130">other</span> <span m="1533260">words,</span>
  <span m="1533610">it's</span> <span m="1533680">the</span> <span m="1533770">sample</span>
  <span m="1534610">mean</span> <span m="1534950">of</span> <span m="1535090">the</span>
  <span m="1535410">indicator</span> <span m="1535730">function.</span> <span m="1537280">And</span>
  <span m="1538870">so</span> <span m="1539030">we</span> <span m="1539120">can</span>
  <span m="1539350">think</span> <span m="1539560">of</span> <span m="1539630">the</span>
  <span m="1539880">estimator</span> <span m="1540070">this</span> <span m="1540250">way,</span>
  <span m="1540640">and</span> <span m="1541000">we've</span> <span m="1541130">already</span>
  <span m="1541310">seen</span> <span m="1541670">this.</span> <span m="1541965">We</span>
  <span m="1542260">saw</span> <span m="1542410">that</span> <span m="1542590">the</span>
  <span m="1542700">expected</span> <span m="1543430">value</span> <span m="1544900">of</span>
  <span m="1545110">this</span> <span m="1545800">estimator</span> <span m="1546570">for</span>
  <span m="1546660">the</span> <span m="1546740">probability</span> <span m="1547350">was</span>
  <span m="1547520">equal</span> <span m="1547740">to</span> <span m="1547840">what?</span>
  <span m="1553720">Probability</span> <span m="1554220">of</span> <span m="1554330">A,</span>
  <span m="1557130">unbiased.</span> <span m="1561970">This</span> <span m="1562454">would</span>
  <span m="1562619">be</span> <span m="1562784">a</span> <span m="1562950">big</span>
  <span m="1563387">piece.</span></p><p><span m="1564700">And</span> <span m="1565510">do</span>
  <span m="1565590">you</span> <span m="1565650">remember</span> <span m="1565910">the</span>
  <span m="1566000">expressions</span> <span m="1566345">to</span> <span m="1566690">the</span>
  <span m="1566780">variance</span> <span m="1567260">of</span> <span m="1567600">this?</span>
  <span m="1571328">Does</span> <span m="1571800">anyone</span> <span m="1572020">remember</span>
  <span m="1572490">it?</span> <span m="1574905">Here,</span> <span m="1575388">it's</span>
  <span m="1575871">P</span> <span m="1576354">of</span> <span m="1576837">A</span>
  <span m="1577320">[? deserves ?]</span> <span m="1578900">1</span> <span m="1579220">minus</span>
  <span m="1579650">P</span> <span m="1579955">of</span> <span m="1580260">A.</span>
  <span m="1582480">And</span> <span m="1582590">what's</span> <span m="1582720">always</span>
  <span m="1582940">in</span> <span m="1583020">the</span> <span m="1583090">denominator?</span>
  <span m="1585680">N.</span> <span m="1586110">Right.</span> <span m="1586588">Standard</span>
  <span m="1587066">error</span> <span m="1588022">of</span> <span m="1588500">the</span>
  <span m="1589030">estimator</span> <span m="1589520">is</span> <span m="1589720">1/3</span>
  <span m="1589800">of</span> <span m="1590267">that</span> <span m="1590734">thing.</span></p><p><span
  m="1591201">All</span> <span m="1591668">right.</span> <span m="1593536">So</span>
  <span m="1594940">that's</span> <span m="1595120">what</span> <span m="1595250">we</span>
  <span m="1595340">saw</span> <span m="1595510">before.</span> <span m="1597080">So</span>
  <span m="1597180">now</span> <span m="1597190">what</span> <span m="1597340">we're</span>
  <span m="1597440">going</span> <span m="1597560">to</span> <span m="1597650">do</span>
  <span m="1598110">is</span> <span m="1599440">think</span> <span m="1599620">about</span>
  <span m="1599860">how</span> <span m="1599980">importance</span> <span m="1600400">sampling</span>
  <span m="1601880">can</span> <span m="1602080">help</span> <span m="1602430">us</span>
  <span m="1603820">come</span> <span m="1604080">up</span> <span m="1604240">with</span>
  <span m="1604370">an</span> <span m="1604460">estimator,</span> <span m="1606110">for</span>
  <span m="1606580">P</span> <span m="1606885">of</span> <span m="1607190">A</span>
  <span m="1608500">that's</span> <span m="1608680">got</span> <span m="1608860">smaller</span>
  <span m="1609090">variance.</span> <span m="1609405">Do</span> <span m="1609562">you</span>
  <span m="1609720">remember</span> <span m="1609830">when</span> <span m="1609940">we</span>
  <span m="1610050">did</span> <span m="1610160">that</span> <span m="1610330">analysis?</span></p><p><span
  m="1611570">We</span> <span m="1611850">also</span> <span m="1611925">did</span>
  <span m="1612000">an</span> <span m="1612060">analysis</span> <span m="1613210">where</span>
  <span m="1613670">if</span> <span m="1614040">P</span> <span m="1614360">is</span>
  <span m="1614530">really</span> <span m="1614750">small</span> <span m="1615280">and</span>
  <span m="1615310">you</span> <span m="1615370">want</span> <span m="1615540">to</span>
  <span m="1615600">have</span> <span m="1615850">a</span> <span m="1616590">tolerance</span>
  <span m="1617035">that's</span> <span m="1617480">relative</span> <span m="1618050">to</span>
  <span m="1618130">the</span> <span m="1618200">size</span> <span m="1618540">of</span>
  <span m="1619025">P,</span> <span m="1619510">you</span> <span m="1619650">end</span>
  <span m="1619800">up</span> <span m="1619890">needing</span> <span m="1620740">billions,</span>
  <span m="1621310">millions</span> <span m="1621600">of</span> <span m="1621700">samples.</span>
  <span m="1623132">So</span> <span m="1624380">we're</span> <span m="1624500">going</span>
  <span m="1624620">to</span> <span m="1624680">see</span> <span m="1624960">whether</span>
  <span m="1625290">importance</span> <span m="1625400">sampling</span> <span m="1626080">or</span>
  <span m="1626230">see</span> <span m="1626400">how</span> <span m="1626720">importance</span>
  <span m="1627190">sampling</span> <span m="1631000">can</span> <span m="1631170">help</span>
  <span m="1631390">us.</span> <span m="1631610">Again,</span> <span m="1631980">I'm</span>
  <span m="1632300">going</span> <span m="1632450">to</span> <span m="1632550">erase</span>
  <span m="1632805">this,</span> <span m="1633060">but</span> <span m="1633770">I</span>
  <span m="1633890">find</span> <span m="1634100">it</span> <span m="1634180">helpful</span>
  <span m="1634560">to</span> <span m="1634630">think</span> <span m="1634820">about</span>
  <span m="1635010">these</span> <span m="1635230">two</span> <span m="1635653">paths.</span>
  <span m="1636500">We</span> <span m="1636620">could</span> <span m="1636790">sample,</span>
  <span m="1638260">take</span> <span m="1638430">lots</span> <span m="1638720">of</span>
  <span m="1638820">samples</span> <span m="1639590">and</span> <span m="1641400">we're</span>
  <span m="1641560">talking</span> <span m="1641780">about</span> <span m="1641920">the</span>
  <span m="1641980">mean</span> <span m="1642230">here,</span> <span m="1642710">use</span>
  <span m="1642920">our</span> <span m="1643090">regular</span> <span m="1643820">estimator.</span>
  <span m="1645500">Or</span> <span m="1645770">we</span> <span m="1645870">could</span>
  <span m="1645980">think</span> <span m="1646120">about</span> <span m="1646400">introducing</span>
  <span m="1647390">another</span> <span m="1647740">random</span> <span m="1647970">variable</span>
  <span m="1648580">with</span> <span m="1648770">another</span> <span m="1649080">pdf</span>
  <span m="1650890">and</span> <span m="1651040">changing</span> <span m="1651460">what</span>
  <span m="1651590">we</span> <span m="1652040">sample</span> <span m="1652390">from</span>
  <span m="1653210">and</span> <span m="1653380">then</span> <span m="1653670">weighting</span>
  <span m="1654380">the</span> <span m="1655850">integral</span> <span m="1658060">to</span>
  <span m="1658200">account</span> <span m="1658570">for</span> <span m="1658680">the</span>
  <span m="1658750">fact</span> <span m="1659010">that</span> <span m="1659160">we</span>
  <span m="1659250">sampled</span> <span m="1659540">from</span> <span m="1659700">a</span>
  <span m="1659740">different</span> <span m="1660040">pdf</span> <span m="1661005">and</span>
  <span m="1661440">coming</span> <span m="1661810">out</span> <span m="1661980">with</span>
  <span m="1662100">an</span> <span m="1662180">estimate</span> <span m="1662530">of</span>
  <span m="1662610">the</span> <span m="1662690">same</span> <span m="1663040">thing</span>
  <span m="1663415">but</span> <span m="1663790">changing</span> <span m="1664100">the</span>
  <span m="1664508">variance.</span></p><p><span m="1666760">So</span> <span m="1666810">let's</span>
  <span m="1667020">see</span> <span m="1668170">how</span> <span m="1668310">that</span>
  <span m="1668470">would</span> <span m="1668610">work</span> <span m="1668830">out.</span>
  <span m="1678046">So</span> <span m="1678530">we'll</span> <span m="1679014">go</span>
  <span m="1679600">straight</span> <span m="1679960">to</span> <span m="1680110">a</span>
  <span m="1680415">pdf.</span> <span m="1682552">So</span> <span m="1683010">we'll</span>
  <span m="1683150">introduce</span> <span m="1683570">another</span> <span m="1683850">pdf,</span>
  <span m="1684135">and</span> <span m="1684420">it's</span> <span m="1684770">going</span>
  <span m="1685120">to</span> <span m="1685273">be</span> <span m="1685426">called</span>
  <span m="1685580">w.</span> <span m="1688930">And</span> <span m="1689100">it's</span>
  <span m="1689125">a</span> <span m="1689150">function</span> <span m="1689430">of</span>
  <span m="1689530">x,</span> <span m="1689830">so</span> <span m="1689980">it's</span>
  <span m="1690130">defined</span> <span m="1690450">on</span> <span m="1690540">the</span>
  <span m="1690610">same</span> <span m="1690860">support</span> <span m="1692844">as</span>
  <span m="1693322">x,</span> <span m="1695720">whatever</span> <span m="1696215">x</span>
  <span m="1696710">is.</span> <span m="1697205">What</span> <span m="1697328">are</span>
  <span m="1697452">we</span> <span m="1697576">doing?</span> <span m="1699680">Yeah,</span>
  <span m="1699890">we</span> <span m="1699990">have</span> <span m="1700090">[INAUDIBLE].</span></p><p><span
  m="1701001">AUDIENCE:</span> <span m="1701462">[INAUDIBLE]</span></p><p><span m="1702384">KAREN
  WILLCOX:</span> <span m="1702845">Ah,</span> <span m="1703306">fourth.</span></p><p><span
  m="1704120">AUDIENCE:</span> <span m="1704606">[? Don ?]</span> <span m="1704849">Ulrich</span>
  <span m="1705092">just</span> <span m="1705189">wanted</span> <span m="1705286">to</span>
  <span m="1705383">say</span> <span m="1705480">hello.</span></p><p><span m="1705578">KAREN
  WILLCOX:</span> <span m="1706064">Hi,</span> <span m="1706307">Don.</span></p><p><span
  m="1706550">AUDIENCE:</span> <span m="1707036">How</span> <span m="1707157">are</span>
  <span m="1707279">you</span> <span m="1707400">doing?</span> <span m="1707522">You've</span>
  <span m="1707766">got</span> <span m="1708010">chalk</span> <span m="1708136">all</span>
  <span m="1708263">over</span> <span m="1708390">your</span> <span m="1708640">face.</span></p><p><span
  m="1708890">KAREN WILLCOX:</span> <span m="1709390">I</span> <span m="1709515">have.</span>
  <span m="1709640">You</span> <span m="1709765">guys</span> <span m="1709890">know</span>
  <span m="1710390">who</span> <span m="1710890">this</span> <span m="1711080">is,</span>
  <span m="1711270">right?</span> <span m="1711980">[? Don ?]</span> <span m="1712320">Ulrich,</span>
  <span m="1712660">Satellite</span> <span m="1713130">astronaut.</span></p><p><span
  m="1713400">AUDIENCE:</span> <span m="1713670">I'm</span> <span m="1714170">one</span>
  <span m="1714530">of</span> <span m="1714553">the</span> <span m="1714576">lucky</span>
  <span m="1714600">guys</span> <span m="1714711">who</span> <span m="1714823">took</span>
  <span m="1714934">a</span> <span m="1715046">fall</span> <span m="1715269">in</span>
  <span m="1715492">space.</span></p><p><span m="1715940">KAREN WILLCOX:</span> <span
  m="1716150">They're</span> <span m="1716242">excited</span> <span m="1716335">in</span>
  <span m="1716520">learning</span> <span m="1716840">all</span> <span m="1716940">about</span>
  <span m="1717090">computational</span> <span m="1717630">methods.</span> <span m="1717930">And</span>
  <span m="1718030">today</span> <span m="1718280">we're</span> <span m="1718370">talking</span>
  <span m="1718690">about</span> <span m="1718910">estimating</span> <span m="1719650">low</span>
  <span m="1720290">failure</span> <span m="1720610">probabilities,</span> <span m="1721510">so</span>
  <span m="1721950">things</span> <span m="1722380">like</span> <span m="1722660">10</span>
  <span m="1722920">to</span> <span m="1722965">the</span> <span m="1723010">minus</span>
  <span m="1723480">9,</span> <span m="1724020">things</span> <span m="1724250">that</span>
  <span m="1724330">can</span> <span m="1724480">go</span> <span m="1724590">wrong.</span>
  <span m="1725470">Do</span> <span m="1725610">you</span> <span m="1725680">know</span>
  <span m="1725820">anything</span> <span m="1726050">about</span> <span m="1726240">that?</span></p><p><span
  m="1726728">AUDIENCE:</span> <span m="1727216">That's</span> <span m="1727297">10</span>
  <span m="1727378">to</span> <span m="1727460">the</span> <span m="1727541">minus</span>
  <span m="1727622">9.</span> <span m="1729170">Well,</span> <span m="1729980">you</span>
  <span m="1730170">don't</span> <span m="1730420">need</span> <span m="1730710">to</span>
  <span m="1730890">worry</span> <span m="1731070">about</span> <span m="1731430">that.</span></p><p><span
  m="1731780">KAREN WILLCOX:</span> <span m="1732120">I'll</span> <span m="1732175">be</span>
  <span m="1732230">at</span> <span m="1732300">the</span> <span m="1732370">dinner</span>
  <span m="1732580">tonight.</span> <span m="1733500">So</span> <span m="1733780">I'll</span>
  <span m="1733868">pick</span> <span m="1733956">up</span> <span m="1734044">a</span>
  <span m="1734132">beer.</span> <span m="1734220">Thanks.</span> <span m="1735260">Where</span>
  <span m="1735430">is</span> <span m="1735530">the</span> <span m="1735610">talk?</span></p><p><span
  m="1736395">AUDIENCE:</span> <span m="1736870">Marlar</span> <span m="1737370">Lounge.</span>
  <span m="1739370">Second</span> <span m="1739870">floor.</span> <span m="1740870">4:00.</span></p><p><span
  m="1742550">KAREN WILLCOX:</span> <span m="1742890">Or</span> <span m="1743040">you</span>
  <span m="1743130">could</span> <span m="1743250">come</span> <span m="1743420">to</span>
  <span m="1743510">office</span> <span m="1743790">hours.</span></p><p><span m="1745596">AUDIENCE:</span>
  <span m="1746090">And</span> <span m="1746420">make</span> <span m="1746610">sure</span>
  <span m="1746830">you</span> <span m="1746980">learn</span> <span m="1747260">this</span>
  <span m="1747520">stuff</span> <span m="1747780">because</span> <span m="1748035">it's</span>
  <span m="1748290">important.</span></p><p><span m="1755196">KAREN WILLCOX:</span>
  <span m="1755665">I</span> <span m="1756140">don't</span> <span m="1756420">if</span>
  <span m="1756450">you</span> <span m="1756480">guys</span> <span m="1756690">know,</span>
  <span m="1756850">but</span> <span m="1756980">I</span> <span m="1757020">made</span>
  <span m="1757200">it</span> <span m="1757280">to</span> <span m="1757350">the</span>
  <span m="1757420">finals</span> <span m="1757820">at</span> <span m="1758105">the</span>
  <span m="1758247">astronaut</span> <span m="1758390">selection</span> <span m="1758800">last</span>
  <span m="1759130">year,</span> <span m="1760000">but</span> <span m="1760190">didn't</span>
  <span m="1760980">get</span> <span m="1761130">picked</span> <span m="1761546">so,</span>
  <span m="1762380">Don</span> <span m="1762690">was,</span> <span m="1762950">yeah.</span></p><p><span
  m="1769630">All</span> <span m="1769720">right.</span> <span m="1769920">So</span>
  <span m="1770060">we</span> <span m="1770160">just</span> <span m="1770330">introduced</span>
  <span m="1770550">a</span> <span m="1770660">bit--</span> <span m="1771020">I'd</span>
  <span m="1771210">much</span> <span m="1771400">rather</span> <span m="1771660">teach</span>
  <span m="1771900">that</span> <span m="1772100">stuff.</span> <span m="1772285">It's</span>
  <span m="1772470">more</span> <span m="1772640">exciting</span> <span m="1772950">than</span>
  <span m="1773405">going</span> <span m="1773556">into</span> <span m="1773708">space,</span>
  <span m="1773860">right?</span></p><p><span m="1774270">AUDIENCE:</span> <span m="1774753">[INAUDIBLE].</span></p><p><span
  m="1782964">KAREN WILLCOX:</span> <span m="1783460">So</span> <span m="1783710">we've</span>
  <span m="1783790">introduced</span> <span m="1783985">to</span> <span m="1784180">pdf</span>
  <span m="1784950">w</span> <span m="1785330">of</span> <span m="1785710">x,</span>
  <span m="1786840">and</span> <span m="1787450">I</span> <span m="1787530">want</span>
  <span m="1787660">you</span> <span m="1787720">to</span> <span m="1787800">think</span>
  <span m="1788050">is</span> <span m="1788140">this</span> <span m="1788360">as</span>
  <span m="1788490">being</span> <span m="1788740">like</span> <span m="1788890">an</span>
  <span m="1789070">alternative</span> <span m="1789400">pdf</span> <span m="1792220">for</span>
  <span m="1792600">x.</span> <span m="1794720">And</span> <span m="1794830">x</span>
  <span m="1795310">is</span> <span m="1795490">just</span> <span m="1795940">a</span>
  <span m="1796390">generic</span> <span m="1796435">at</span> <span m="1796480">this</span>
  <span m="1796640">point.</span> <span m="1797370">This</span> <span m="1797480">thing</span>
  <span m="1797710">is</span> <span m="1797870">called</span> <span m="1803230">the</span>
  <span m="1803330">biasing</span> <span m="1804830">entity.</span> <span m="1809190">And</span>
  <span m="1810110">you</span> <span m="1810260">can</span> <span m="1810400">see</span>
  <span m="1810600">what</span> <span m="1810840">we're</span> <span m="1810970">going</span>
  <span m="1811090">to</span> <span m="1811180">do</span> <span m="1811320">is</span>
  <span m="1811420">we're</span> <span m="1811870">going</span> <span m="1812110">to</span>
  <span m="1812565">choose</span> <span m="1815300">w</span> <span m="1815730">of</span>
  <span m="1815870">x</span> <span m="1816930">so</span> <span m="1817320">that</span>
  <span m="1817710">this</span> <span m="1817970">event,</span> <span m="1818320">A,</span>
  <span m="1822340">occurs</span> <span m="1823070">more</span> <span m="1823280">frequently.</span></p><p><span
  m="1830944">So</span> <span m="1831390">the</span> <span m="1831510">idea</span>
  <span m="1831780">is</span> <span m="1831880">we</span> <span m="1831940">don't</span>
  <span m="1832130">want</span> <span m="1832250">to</span> <span m="1832310">have</span>
  <span m="1832450">to</span> <span m="1832560">wait</span> <span m="1832810">around</span>
  <span m="1833110">for</span> <span m="1833270">a</span> <span m="1833320">billion</span>
  <span m="1833780">samples</span> <span m="1834410">for</span> <span m="1834520">the</span>
  <span m="1834600">one</span> <span m="1834810">event</span> <span m="1835030">to</span>
  <span m="1835210">occur.</span> <span m="1836060">We're</span> <span m="1836180">going</span>
  <span m="1836300">to</span> <span m="1836400">choose</span> <span m="1836832">this</span>
  <span m="1838130">alternate</span> <span m="1838515">pdf</span> <span m="1838900">w,</span>
  <span m="1840170">in</span> <span m="1840300">such</span> <span m="1840510">a</span>
  <span m="1840560">way</span> <span m="1840790">that</span> <span m="1841070">this</span>
  <span m="1841400">event,</span> <span m="1841720">A,</span> <span m="1842090">occurs</span>
  <span m="1842210">more</span> <span m="1842340">frequently.</span> <span m="1844600">So</span>
  <span m="1844790">then</span> <span m="1845770">what</span> <span m="1846010">is</span>
  <span m="1846110">our</span> <span m="1846565">estimate</span> <span m="1846792">to</span>
  <span m="1847020">the</span> <span m="1847160">probability</span> <span m="1847740">look</span>
  <span m="1847970">like?</span> <span m="1848300">Probability</span> <span m="1849797">of</span>
  <span m="1850296">A</span> <span m="1856290">is</span> <span m="1857850">maybe</span>
  <span m="1857980">you</span> <span m="1858120">can</span> <span m="1858290">see</span>
  <span m="1858500">it</span> <span m="1859500">directly</span> <span m="1859910">from</span>
  <span m="1860050">this</span> <span m="1860170">expression.</span> <span m="1860840">We</span>
  <span m="1860980">could</span> <span m="1861150">write</span> <span m="1861360">it</span>
  <span m="1861500">as</span> <span m="1861630">being</span> <span m="1861790">the</span>
  <span m="1861870">expectation</span> <span m="1862770">of</span> <span m="1863320">the</span>
  <span m="1863440">indicator</span> <span m="1863780">function.</span> <span m="1866662">And</span>
  <span m="1867060">it's</span> <span m="1867350">the</span> <span m="1867460">expectation</span>
  <span m="1870520">taken</span> <span m="1870840">under</span> <span m="1871120">f</span>
  <span m="1871612">of</span> <span m="1872104">x.</span></p><p><span m="1872596">So</span>
  <span m="1873088">it's</span> <span m="1873580">the</span> <span m="1873940">expectation</span>
  <span m="1874840">of</span> <span m="1874920">the</span> <span m="1875020">indicator</span>
  <span m="1875540">function</span> <span m="1877530">with</span> <span m="1877700">expectation</span>
  <span m="1878300">as</span> <span m="1878440">with</span> <span m="1878630">respect</span>
  <span m="1881400">to</span> <span m="1881640">f</span> <span m="1881870">of</span>
  <span m="1882070">x.</span> <span m="1883250">Maybe</span> <span m="1883500">up</span>
  <span m="1883590">here</span> <span m="1883850">I</span> <span m="1883950">should</span>
  <span m="1885120">define</span> <span m="1885820">that</span> <span m="1887580">then</span>
  <span m="1887900">f</span> <span m="1888220">of</span> <span m="1888575">x</span>
  <span m="1888930">is</span> <span m="1889412">but</span> <span m="1889894">the</span>
  <span m="1890376">pdf</span> <span m="1893270">f</span> <span m="1893545">of</span>
  <span m="1893820">x.</span> <span m="1898020">And</span> <span m="1898380">what</span>
  <span m="1898540">is</span> <span m="1898750">this?</span> <span m="1898970">This</span>
  <span m="1899130">is</span> <span m="1899530">nothing</span> <span m="1899720">but</span>
  <span m="1899990">the</span> <span m="1900140">integral</span> <span m="1900890">of</span>
  <span m="1901315">the</span> <span m="1901710">indicator</span> <span m="1902300">function</span>
  <span m="1905030">weighted</span> <span m="1905390">by</span> <span m="1905530">the</span>
  <span m="1905930">pdf</span> <span m="1906330">and</span> <span m="1906730">then</span>
  <span m="1907200">[? graded ?]</span> <span m="1907380">up</span> <span m="1907465">for</span>
  <span m="1907550">the</span> <span m="1907635">support</span> <span m="1907720">of</span>
  <span m="1907800">x.</span></p><p><span m="1909520">So</span> <span m="1909950">we're</span>
  <span m="1910150">going</span> <span m="1910235">to</span> <span m="1910320">do</span>
  <span m="1910490">the</span> <span m="1910660">same</span> <span m="1910810">trick</span>
  <span m="1910960">that</span> <span m="1911120">we</span> <span m="1911190">did</span>
  <span m="1911360">before.</span> <span m="1913100">We're</span> <span m="1913220">going</span>
  <span m="1913360">to</span> <span m="1914380">multiply</span> <span m="1915130">and</span>
  <span m="1915450">divide</span> <span m="1916050">by</span> <span m="1916330">this</span>
  <span m="1916650">w.</span> <span m="1917880">So</span> <span m="1917980">we've</span>
  <span m="1918090">got</span> <span m="1919270">our</span> <span m="1919530">f</span>
  <span m="1919870">of</span> <span m="1920290">x.</span> <span m="1920710">We're</span>
  <span m="1920830">going</span> <span m="1920950">divide</span> <span m="1921410">by</span>
  <span m="1921570">w.</span> <span m="1922636">We're</span> <span m="1922982">going</span>
  <span m="1923330">to</span> <span m="1923420">multiply</span> <span m="1923640">by</span>
  <span m="1924135">w.</span> <span m="1929085">And</span> <span m="1932550">maybe</span>
  <span m="1932790">now</span> <span m="1932950">you</span> <span m="1933140">can</span>
  <span m="1933500">see</span> <span m="1933980">that</span> <span m="1934160">what</span>
  <span m="1934530">we</span> <span m="1934715">have</span> <span m="1934900">now,</span>
  <span m="1935220">we</span> <span m="1935430">have</span> <span m="1938190">an</span>
  <span m="1938320">expectation</span> <span m="1939400">of</span> <span m="1941306">[?
  sine. ?]</span> <span m="1942170">We</span> <span m="1942240">can</span> <span m="1942350">think</span>
  <span m="1942480">about</span> <span m="1942720">lumping</span> <span m="1943060">this</span>
  <span m="1943130">thing</span> <span m="1943360">together</span> <span m="1944670">now</span>
  <span m="1945680">taken</span> <span m="1946220">with</span> <span m="1946300">respect</span>
  <span m="1946580">to</span> <span m="1946680">the</span> <span m="1946790">pdf</span>
  <span m="1947276">w.</span></p><p><span m="1949220">So</span> <span m="1949330">this</span>
  <span m="1949490">is</span> <span m="1949640">just</span> <span m="1950100">the</span>
  <span m="1950170">integral</span> <span m="1950650">of</span> <span m="1950710">something</span>
  <span m="1951450">times</span> <span m="1951740">the</span> <span m="1951770">pdf</span>
  <span m="1953010">integrated</span> <span m="1953480">over</span> <span m="1953650">the</span>
  <span m="1953730">support.</span> <span m="1956032">So</span> <span m="1957904">we</span>
  <span m="1958372">have</span> <span m="1958840">to</span> <span m="1959030">write</span>
  <span m="1959160">it</span> <span m="1959290">up</span> <span m="1959410">here.</span>
  <span m="1965970">So</span> <span m="1966100">the</span> <span m="1966200">last</span>
  <span m="1966520">line</span> <span m="1966820">in</span> <span m="1966880">that</span>
  <span m="1967110">development--</span> <span m="1967495">the</span> <span m="1967880">left-hand</span>
  <span m="1968670">side</span> <span m="1969130">is</span> <span m="1969535">P</span>
  <span m="1969670">of</span> <span m="1969805">A,</span> <span m="1969940">which</span>
  <span m="1970190">we</span> <span m="1970350">haven't</span> <span m="1970480">discretized</span>
  <span m="1971220">with</span> <span m="1971340">Monte</span> <span m="1971570">Carlo</span>
  <span m="1971770">yet.</span> <span m="1972050">We're</span> <span m="1972200">still</span>
  <span m="1972390">doing</span> <span m="1972630">things</span> <span m="1972950">exactly--</span>
  <span m="1976370">is</span> <span m="1976830">expectation</span> <span m="1979110">with</span>
  <span m="1979400">respect</span> <span m="1979930">or</span> <span m="1980050">under</span>
  <span m="1980320">this</span> <span m="1980510">pdf</span> <span m="1981000">w</span>
  <span m="1982980">of--</span> <span m="1984710">now,</span> <span m="1984980">the</span>
  <span m="1985080">indicator</span> <span m="1985610">function</span> <span m="1987560">with</span>
  <span m="1987720">this</span> <span m="1989050">waiting,</span> <span m="1990290">f</span>
  <span m="1990370">of</span> <span m="1990650">x</span> <span m="1992630">over</span>
  <span m="1993620">w</span> <span m="1994050">of</span> <span m="1994530">x.</span></p><p><span
  m="2000290">So</span> <span m="2003660">what</span> <span m="2003850">does</span>
  <span m="2003950">this</span> <span m="2004130">mean?</span> <span m="2004920">This</span>
  <span m="2005120">means</span> <span m="2005820">we</span> <span m="2006000">could</span>
  <span m="2009110">draw</span> <span m="2009410">samples</span> <span m="2009970">from</span>
  <span m="2010160">w</span> <span m="2012550">instead</span> <span m="2012880">of</span>
  <span m="2013020">from</span> <span m="2013435">x.</span> <span m="2015660">So</span>
  <span m="2015820">draw</span> <span m="2016060">samples</span> <span m="2020620">from</span>
  <span m="2020760">the</span> <span m="2020820">pdf</span> <span m="2021262">w.</span>
  <span m="2022590">But</span> <span m="2022730">if</span> <span m="2022830">you</span>
  <span m="2022930">do</span> <span m="2023120">that,</span> <span m="2023520">in</span>
  <span m="2023650">order</span> <span m="2023830">to</span> <span m="2023930">get</span>
  <span m="2024100">the</span> <span m="2024200">right</span> <span m="2024470">estimate</span>
  <span m="2024700">for</span> <span m="2024940">the</span> <span m="2025100">probability,</span>
  <span m="2026530">you</span> <span m="2026670">have</span> <span m="2026840">to</span>
  <span m="2026960">weight</span> <span m="2027430">the</span> <span m="2027510">samples</span>
  <span m="2030130">by</span> <span m="2030870">the</span> <span m="2031310">f</span>
  <span m="2031355">over</span> <span m="2031400">w</span> <span m="2032010">to</span>
  <span m="2032070">make</span> <span m="2032430">up</span> <span m="2032720">for</span>
  <span m="2032830">the</span> <span m="2032910">fact</span> <span m="2033200">that</span>
  <span m="2033340">you</span> <span m="2033640">drew</span> <span m="2033900">from</span>
  <span m="2034100">a</span> <span m="2034140">different</span> <span m="2034580">distribution.</span>
  <span m="2036546">Does</span> <span m="2036960">that</span> <span m="2037280">make</span>
  <span m="2037570">sense?</span></p><p><span m="2038360">So</span> <span m="2038560">weight</span>
  <span m="2038920">by</span> <span m="2041524">f</span> <span m="2041960">of</span>
  <span m="2042160">x</span> <span m="2042611">over</span> <span m="2043062">w</span>
  <span m="2043287">of</span> <span m="2043513">x,</span> <span m="2045320">I'd</span>
  <span m="2045440">say</span> <span m="2046140">to</span> <span m="2046270">counter</span>
  <span m="2047090">the</span> <span m="2047170">sort</span> <span m="2047350">of</span>
  <span m="2047520">my</span> <span m="2047980">informal</span> <span m="2048409">way</span>
  <span m="2048610">of</span> <span m="2048690">thinking</span> <span m="2049010">about</span>
  <span m="2049199">it.</span> <span m="2049949">And</span> <span m="2050090">if</span>
  <span m="2050190">you</span> <span m="2050270">do</span> <span m="2050409">that,</span>
  <span m="2050790">then</span> <span m="2052090">the</span> <span m="2052159">expectation</span>
  <span m="2052969">works</span> <span m="2053270">out</span> <span m="2053530">so</span>
  <span m="2053639">that</span> <span m="2053810">you</span> <span m="2054350">are</span>
  <span m="2055040">still</span> <span m="2056230">getting</span> <span m="2056440">the</span>
  <span m="2056520">probability</span> <span m="2057000">you're</span> <span m="2057170">after.</span></p><p><span
  m="2059760">So</span> <span m="2059880">then</span> <span m="2060110">the</span>
  <span m="2060199">last</span> <span m="2060550">step</span> <span m="2060590">is</span>
  <span m="2060630">just</span> <span m="2060670">to</span> <span m="2060909">write</span>
  <span m="2061100">down</span> <span m="2061547">what</span> <span m="2061770">our</span>
  <span m="2061994">Monte</span> <span m="2062441">Carlo</span> <span m="2063090">estimator</span>
  <span m="2063469">would</span> <span m="2063639">be--</span> <span m="2065780">so</span>
  <span m="2065889">then</span> <span m="2065989">our</span> <span m="2066159">Monte</span>
  <span m="2066530">Carlo</span> <span m="2068130">importance</span> <span m="2068760">sampling</span>
  <span m="2070830">estimator</span> <span m="2073719">for</span> <span m="2074239">this</span>
  <span m="2074520">probability</span> <span m="2075159">of</span> <span m="2075310">A</span>
  <span m="2080929">is</span> <span m="2081120">what?</span> <span m="2081690">So</span>
  <span m="2081830">let's</span> <span m="2082010">call</span> <span m="2082260">it</span>
  <span m="2082440">P</span> <span m="2083620">hat.</span> <span m="2084332">We'll</span>
  <span m="2084690">put</span> <span m="2084830">an</span> <span m="2085100">IS</span>
  <span m="2085530">down</span> <span m="2085870">here</span> <span m="2086030">to</span>
  <span m="2086190">indicate</span> <span m="2086630">that's</span> <span m="2086739">the</span>
  <span m="2086900">importance</span> <span m="2087389">sampling</span> <span m="2087792">estimator.</span>
  <span m="2088800">So</span> <span m="2089270">help</span> <span m="2089409">me</span>
  <span m="2089550">write</span> <span m="2089770">it.</span> <span m="2089905">What</span>
  <span m="2090040">does</span> <span m="2090120">it</span> <span m="2090199">look</span>
  <span m="2090340">like?</span></p><p><span m="2093570">Take</span> <span m="2093800">this</span>
  <span m="2093929">risk</span> <span m="2094340">part.</span> <span m="2094540">That's</span>
  <span m="2094656">the</span> <span m="2094772">easy</span> <span m="2094888">part.</span>
  <span m="2098730">One</span> <span m="2098930">over</span> <span m="2099040">N--</span>
  <span m="2100790">is</span> <span m="2101230">it</span> <span m="2101370">Libby</span>
  <span m="2101480">or</span> <span m="2101590">Casey?</span> <span m="2102290">Oh,</span>
  <span m="2102410">it's</span> <span m="2102600">[INAUDIBLE].</span> <span m="2104408">All</span>
  <span m="2104860">right.</span> <span m="2105080">Now,</span> <span m="2105350">one</span>
  <span m="2105416">of</span> <span m="2105482">you</span> <span m="2105548">guys</span>
  <span m="2105614">have</span> <span m="2105680">to</span> <span m="2105830">do</span>
  <span m="2105950">the</span> <span m="2106385">harder</span> <span m="2106820">part.</span>
  <span m="2107690">1</span> <span m="2107990">over</span> <span m="2108489">N</span>
  <span m="2108988">what?</span> <span m="2114480">There</span> <span m="2114780">is</span>
  <span m="2114805">a</span> <span m="2114830">regular</span> <span m="2115130">Monte</span>
  <span m="2115320">Carlo</span> <span m="2115595">estimator.</span> <span m="2117980">Summation</span>
  <span m="2119900">from</span> <span m="2120050">I</span> <span m="2120200">equals</span>
  <span m="2120350">1</span> <span m="2120650">to</span> <span m="2120740">N</span>
  <span m="2121770">of</span> <span m="2122580">what?</span> <span m="2125984">iA</span>
  <span m="2130350">times</span> <span m="2130890">f</span> <span m="2131530">of</span>
  <span m="2132460">xi</span> <span m="2134320">over</span> <span m="2134550">w</span>
  <span m="2134805">of</span> <span m="2135060">xi.</span></p><p><span m="2137960">And</span>
  <span m="2138600">it</span> <span m="2138750">doesn't</span> <span m="2139270">show</span>
  <span m="2139490">up</span> <span m="2139600">in</span> <span m="2139680">the</span>
  <span m="2139780">formula,</span> <span m="2141210">but</span> <span m="2141490">it's</span>
  <span m="2141670">important</span> <span m="2142060">to</span> <span m="2142150">know</span>
  <span m="2142760">that</span> <span m="2142970">this</span> <span m="2143130">is</span>
  <span m="2143240">all</span> <span m="2143680">when</span> <span m="2145880">the</span>
  <span m="2146320">xi's</span> <span m="2147230">are</span> <span m="2147620">drawn</span>
  <span m="2151480">from</span> <span m="2151660">the</span> <span m="2151730">pdf</span>
  <span m="2152110">w.</span> <span m="2158620">That's</span> <span m="2158940">that.</span>
  <span m="2161930">We</span> <span m="2162090">never</span> <span m="2162300">noted</span>
  <span m="2162670">that</span> <span m="2162850">before</span> <span m="2163290">because</span>
  <span m="2163540">we</span> <span m="2163680">only</span> <span m="2163860">ever</span>
  <span m="2164020">had</span> <span m="2164250">one</span> <span m="2164640">pdf</span>
  <span m="2164960">floating</span> <span m="2165220">around,</span> <span m="2165510">but</span>
  <span m="2165750">now</span> <span m="2165940">that</span> <span m="2166045">we've</span>
  <span m="2166150">got</span> <span m="2166590">two,</span> <span m="2167030">so</span>
  <span m="2167470">here's</span> <span m="2167910">the</span> <span m="2168130">estimator.</span>
  <span m="2169150">If</span> <span m="2169320">we</span> <span m="2169450">drew</span>
  <span m="2169810">the</span> <span m="2171250">samples</span> <span m="2172186">from</span>
  <span m="2174060">f</span> <span m="2174690">of</span> <span m="2175030">x,</span>
  <span m="2175580">which</span> <span m="2175760">is</span> <span m="2175970">the</span>
  <span m="2176040">regular</span> <span m="2176650">way</span> <span m="2176840">of</span>
  <span m="2176920">doing</span> <span m="2177190">it,</span> <span m="2177612">that</span>
  <span m="2177752">would</span> <span m="2177893">be</span> <span m="2178034">the</span>
  <span m="2178456">estimator,</span> <span m="2178880">but</span> <span m="2179000">if</span>
  <span m="2179090">we</span> <span m="2179180">draw</span> <span m="2179380">the</span>
  <span m="2179460">samples</span> <span m="2180210">from</span> <span m="2180580">the</span>
  <span m="2180650">pdf</span> <span m="2180845">of</span> <span m="2181040">w,</span>
  <span m="2181580">then</span> <span m="2181750">this</span> <span m="2181890">is</span>
  <span m="2182000">our</span> <span m="2182140">estimator,</span> <span m="2182405">and</span>
  <span m="2182670">basically</span> <span m="2183350">we</span> <span m="2183430">just</span>
  <span m="2183570">have</span> <span m="2183720">to</span> <span m="2184090">re</span>
  <span m="2184350">weigh</span> <span m="2184780">it.</span> <span m="2188650">Is</span>
  <span m="2188780">that</span> <span m="2188920">clear?</span> <span m="2192660">So</span>
  <span m="2192910">can</span> <span m="2193090">you</span> <span m="2193190">see--</span>
  <span m="2193899">yeah.</span></p><p><span m="2194398">AUDIENCE:</span> <span m="2194897">[INAUDIBLE].</span></p><p><span
  m="2202881">KAREN WILLCOX:</span> <span m="2203390">Here?</span> <span m="2203970">Yeah.</span>
  <span m="2204250">We</span> <span m="2204500">divided</span> <span m="2204940">by</span>
  <span m="2205010">w,</span> <span m="2205080">and</span> <span m="2205345">we</span>
  <span m="2205610">multiplied</span> <span m="2205670">it</span> <span m="2205930">by</span>
  <span m="2206430">w.</span></p><p><span m="2206930">AUDIENCE:</span> <span m="2207430">[INAUDIBLE].</span></p><p><span
  m="2214432">KAREN WILLCOX:</span> <span m="2214810">Well,</span> <span m="2215230">yeah.</span>
  <span m="2217550">w</span> <span m="2217990">is</span> <span m="2218160">a</span>
  <span m="2218220">pdf.</span> <span m="2219630">Maybe</span> <span m="2219930">I</span>
  <span m="2220030">could</span> <span m="2220200">have</span> <span m="2220320">written</span>
  <span m="2220530">it</span> <span m="2220700">like</span> <span m="2220930">if</span>
  <span m="2221240">w</span> <span m="2221603">might</span> <span m="2221966">have</span>
  <span m="2222330">been--</span> <span m="2224900">yeah.</span> <span m="2225120">Sorry.</span>
  <span m="2225590">w</span> <span m="2226060">is</span> <span m="2226530">a</span>
  <span m="2227000">pdf.</span> <span m="2228410">Yeah.</span></p><p><span m="2228600">AUDIENCE:</span>
  <span m="2229100">[INAUDIBLE].</span></p><p><span m="2234100">KAREN WILLCOX:</span>
  <span m="2234320">This</span> <span m="2234480">one</span> <span m="2234810">is</span>
  <span m="2234975">strange,</span> <span m="2235140">actually.</span> <span m="2235740">We</span>
  <span m="2235840">approached</span> <span m="2236310">it</span> <span m="2236470">here</span>
  <span m="2236730">by</span> <span m="2236820">starting</span> <span m="2237200">off</span>
  <span m="2237320">by</span> <span m="2237390">saying</span> <span m="2237610">w</span>
  <span m="2237890">is</span> <span m="2238090">a</span> <span m="2238560">pdf.</span>
  <span m="2239500">So</span> <span m="2239590">w</span> <span m="2239890">itself</span>
  <span m="2240340">is</span> <span m="2240600">a</span> <span m="2240860">pdf.</span>
  <span m="2241250">When</span> <span m="2241410">I</span> <span m="2241560">introduce</span>
  <span m="2241820">a</span> <span m="2241915">general</span> <span m="2242010">importance</span>
  <span m="2242640">sampling,</span> <span m="2243140">we</span> <span m="2243520">started</span>
  <span m="2243810">off</span> <span m="2243910">with</span> <span m="2244010">a</span>
  <span m="2244070">random</span> <span m="2244350">variable</span> <span m="2245790">and</span>
  <span m="2246130">said</span> <span m="2246280">that's</span> <span m="2246460">why</span>
  <span m="2246560">we</span> <span m="2246660">put</span> <span m="2246850">that</span>
  <span m="2246910">constraint</span> <span m="2247330">on</span> <span m="2247410">so</span>
  <span m="2247490">that</span> <span m="2247580">we</span> <span m="2247660">could</span>
  <span m="2247810">get</span> <span m="2248070">to</span> <span m="2248155">a</span>
  <span m="2248240">pdf.</span> <span m="2248620">But</span> <span m="2248800">here</span>
  <span m="2249080">we're</span> <span m="2249180">just</span> <span m="2249370">say</span>
  <span m="2249500">let's</span> <span m="2249710">introduce</span> <span m="2250060">a</span>
  <span m="2250120">secondary</span> <span m="2250460">pdf</span> <span m="2250800">or</span>
  <span m="2251190">an</span> <span m="2251580">accelerated</span> <span m="2251970">pdf.</span></p><p><span
  m="2254570">So</span> <span m="2254770">w</span> <span m="2255170">is</span> <span
  m="2255310">a</span> <span m="2255380">pdf,</span> <span m="2255750">which</span>
  <span m="2255890">means</span> <span m="2256050">it</span> <span m="2256110">has</span>
  <span m="2256200">to</span> <span m="2256290">satisfy</span> <span m="2257040">the</span>
  <span m="2258350">property</span> <span m="2258580">of</span> <span m="2258740">a</span>
  <span m="2258890">pdf.</span> <span m="2261960">Greg,</span> <span m="2262115">did</span>
  <span m="2262270">you</span> <span m="2262360">have</span> <span m="2262860">some--</span></p><p><span
  m="2263360">AUDIENCE:</span> <span m="2263860">[INAUDIBLE].</span></p><p><span m="2269064">KAREN
  WILLCOX:</span> <span m="2269490">This</span> <span m="2269670">guy?</span></p><p><span
  m="2270352">AUDIENCE:</span> <span m="2270814">[INAUDIBLE].</span></p><p><span m="2274972">KAREN
  WILLCOX:</span> <span m="2275440">That's</span> <span m="2275590">right.</span></p><p><span
  m="2275760">AUDIENCE:</span> <span m="2276248">[INAUDIBLE].</span></p><p><span m="2283568">KAREN
  WILLCOX:</span> <span m="2284070">Yeah.</span> <span m="2284310">So</span> <span
  m="2284390">this</span> <span m="2284610">would</span> <span m="2284770">be</span>
  <span m="2285240">given</span> <span m="2286100">to</span> <span m="2286340">you.</span>
  <span m="2288750">So</span> <span m="2289110">one</span> <span m="2289410">thing</span>
  <span m="2289580">that's</span> <span m="2289850">just</span> <span m="2290000">a</span>
  <span m="2290150">little</span> <span m="2290400">bit</span> <span m="2290670">confusing</span>
  <span m="2291450">and</span> <span m="2291650">maybe</span> <span m="2291860">I</span>
  <span m="2291950">haven't</span> <span m="2292520">been</span> <span m="2293060">entirely,</span>
  <span m="2293403">so</span> <span m="2293746">I'm</span> <span m="2294090">going</span>
  <span m="2294300">to</span> <span m="2294560">put</span> <span m="2294720">it</span>
  <span m="2294800">over</span> <span m="2295000">here,</span> <span m="2295770">is</span>
  <span m="2296150">that</span> <span m="2296400">when</span> <span m="2296540">we</span>
  <span m="2296640">think</span> <span m="2296830">about</span> <span m="2297140">Monte</span>
  <span m="2297390">Carlo,</span> <span m="2298610">I'm</span> <span m="2298760">going</span>
  <span m="2298855">to</span> <span m="2298950">use</span> <span m="2299175">this</span>
  <span m="2299400">completely</span> <span m="2299780">different</span> <span m="2300390">variable</span>
  <span m="2301140">so</span> <span m="2301300">that</span> <span m="2301450">I</span>
  <span m="2301530">don't</span> <span m="2302410">mix</span> <span m="2302740">up</span>
  <span m="2302920">with</span> <span m="2303530">w's</span> <span m="2303700">and</span>
  <span m="2303930">f's.</span> <span m="2304990">The</span> <span m="2305090">model</span>
  <span m="2305450">has</span> <span m="2305800">say,</span> <span m="2306030">an</span>
  <span m="2306130">input</span> <span m="2306630">that</span> <span m="2306790">might</span>
  <span m="2307110">be</span> <span m="2308580">d</span> <span m="2309780">and</span>
  <span m="2309940">an</span> <span m="2310040">output</span> <span m="2310540">that</span>
  <span m="2310680">might</span> <span m="2310870">be</span> <span m="2311478">q.</span>
  <span m="2313940">And</span> <span m="2314110">we</span> <span m="2314260">talk</span>
  <span m="2314500">about</span> <span m="2314850">drawing</span> <span m="2315520">from</span>
  <span m="2316200">some</span> <span m="2316430">distribution</span> <span m="2316815">of</span>
  <span m="2317120">d.</span> <span m="2317440">Say</span> <span m="2317680">d</span>
  <span m="2317830">is</span> <span m="2318040">normal</span> <span m="2318990">propagating</span>
  <span m="2319230">it</span> <span m="2319990">through</span> <span m="2320420">and</span>
  <span m="2321760">getting</span> <span m="2322000">the</span> <span m="2322070">corresponding</span>
  <span m="2322950">whatever</span> <span m="2323240">q</span> <span m="2323723">looks</span>
  <span m="2324206">like.</span></p><p><span m="2325172">So</span> <span m="2326140">here</span>
  <span m="2326450">when</span> <span m="2326570">I</span> <span m="2326630">talk</span>
  <span m="2326880">about</span> <span m="2327530">estimating</span> <span m="2328010">the</span>
  <span m="2328080">probability</span> <span m="2328580">of</span> <span m="2328660">A</span>
  <span m="2328750">by</span> <span m="2328840">drawing</span> <span m="2329480">from</span>
  <span m="2329720">x--</span> <span m="2330730">x</span> <span m="2331045">is</span>
  <span m="2331120">really</span> <span m="2331370">q.</span> <span m="2332900">Because</span>
  <span m="2333060">this</span> <span m="2333180">is</span> <span m="2333340">the</span>
  <span m="2333430">pdf</span> <span m="2334110">that</span> <span m="2334410">defines</span>
  <span m="2335410">if</span> <span m="2335790">A</span> <span m="2336100">is</span>
  <span m="2336280">out</span> <span m="2336773">in</span> <span m="2337760">here,</span>
  <span m="2338830">we</span> <span m="2338950">want</span> <span m="2339180">to</span>
  <span m="2339510">draw</span> <span m="2339840">from</span> <span m="2339950">this</span>
  <span m="2340080">distribution.</span> <span m="2340360">I</span> <span m="2340640">mean,</span>
  <span m="2340690">if</span> <span m="2340740">I</span> <span m="2340940">gave</span>
  <span m="2341180">you</span> <span m="2341270">just</span> <span m="2341540">this</span>
  <span m="2341760">distribution,</span> <span m="2342055">q,</span> <span m="2343150">and</span>
  <span m="2343320">I</span> <span m="2343350">asked</span> <span m="2343490">you</span>
  <span m="2343560">to</span> <span m="2343640">estimate</span> <span m="2344030">a</span>
  <span m="2344150">probability,</span> <span m="2344450">you</span> <span m="2344750">would</span>
  <span m="2344900">randomly</span> <span m="2345280">sample</span> <span m="2345690">from</span>
  <span m="2345970">it</span> <span m="2347220">and</span> <span m="2347440">then</span>
  <span m="2347475">you</span> <span m="2347510">would</span> <span m="2347620">count</span>
  <span m="2347830">the</span> <span m="2347890">number</span> <span m="2348130">on</span>
  <span m="2348210">the</span> <span m="2348290">tail.</span></p><p><span m="2349490">So</span>
  <span m="2349720">there</span> <span m="2349910">is</span> <span m="2350030">kind</span>
  <span m="2350170">of</span> <span m="2350240">an</span> <span m="2350440">extra</span>
  <span m="2350800">step,</span> <span m="2351210">which</span> <span m="2351370">is</span>
  <span m="2351570">that</span> <span m="2351710">we're</span> <span m="2351850">really</span>
  <span m="2352120">drawing</span> <span m="2352560">from</span> <span m="2352880">the</span>
  <span m="2353330">d</span> <span m="2353690">and</span> <span m="2354050">pushing</span>
  <span m="2354315">it</span> <span m="2354580">through</span> <span m="2354730">the</span>
  <span m="2354810">model</span> <span m="2355970">to</span> <span m="2356070">characterize</span>
  <span m="2356360">q.</span> <span m="2358450">Is</span> <span m="2358900">that</span>
  <span m="2359240">clear</span> <span m="2359724">enough?</span></p><p><span m="2360208">AUDIENCE:</span>
  <span m="2360692">The</span> <span m="2361176">f</span> <span m="2361660">point,</span>
  <span m="2361740">is</span> <span m="2361821">that</span> <span m="2361902">all</span>
  <span m="2361982">the</span> <span m="2362063">samples,</span> <span m="2362144">or</span>
  <span m="2362628">is</span> <span m="2363112">that</span> <span m="2363596">just</span>
  <span m="2364080">the</span> <span m="2364564">[? sales ?]</span> <span m="2365048">proportion?</span></p><p><span
  m="2366016">KAREN WILLCOX:</span> <span m="2366500">For</span> <span m="2366710">10</span>
  <span m="2366940">points?</span> <span m="2367420">Oh,</span> <span m="2367520">the</span>
  <span m="2367570">N?</span> <span m="2368110">That's</span> <span m="2368350">going</span>
  <span m="2368470">to</span> <span m="2368540">be</span> <span m="2368670">all</span>
  <span m="2369290">the</span> <span m="2369360">samples.</span> <span m="2369837">Yeah.</span></p><p><span
  m="2370314">AUDIENCE:</span> <span m="2370791">[INAUDIBLE].</span></p><p><span m="2375160">KAREN
  WILLCOX:</span> <span m="2375600">Yeah.</span> <span m="2375890">So</span> <span
  m="2375980">let</span> <span m="2376070">me</span> <span m="2376220">try</span>
  <span m="2376440">to</span> <span m="2378330">write</span> <span m="2378470">a</span>
  <span m="2378500">summary</span> <span m="2378810">and</span> <span m="2378900">draw</span>
  <span m="2378990">some</span> <span m="2379120">pictures</span> <span m="2379530">to</span>
  <span m="2379650">help</span> <span m="2380240">you,</span> <span m="2381330">because</span>
  <span m="2385280">I</span> <span m="2385540">don't</span> <span m="2385910">want</span>
  <span m="2386080">to</span> <span m="2386140">mix</span> <span m="2386470">up</span>
  <span m="2386570">two</span> <span m="2386690">things.</span> <span m="2386940">But</span>
  <span m="2387050">what</span> <span m="2387115">we</span> <span m="2387180">would</span>
  <span m="2387340">we</span> <span m="2387430">do</span> <span m="2387640">here</span>
  <span m="2387980">is</span> <span m="2388140">we</span> <span m="2388270">would</span>
  <span m="2388730">sample</span> <span m="2389310">randomly,</span> <span m="2390525">and</span>
  <span m="2390910">more</span> <span m="2391220">samples</span> <span m="2391550">are</span>
  <span m="2391590">going</span> <span m="2391710">to</span> <span m="2391770">end</span>
  <span m="2391930">up</span> <span m="2392080">in</span> <span m="2392160">here</span>
  <span m="2392650">than</span> <span m="2392940">in</span> <span m="2393330">here.</span>
  <span m="2394270">And</span> <span m="2394410">every</span> <span m="2394540">time</span>
  <span m="2394720">we</span> <span m="2394820">sample</span> <span m="2395200">here,</span>
  <span m="2395490">we</span> <span m="2395580">generate</span> <span m="2396250">a</span>
  <span m="2396370">corresponding</span> <span m="2397000">sample</span> <span m="2397440">of</span>
  <span m="2397570">this.</span></p><p><span m="2398660">So</span> <span m="2399260">when</span>
  <span m="2399430">you</span> <span m="2399490">think</span> <span m="2399650">about</span>
  <span m="2399820">the</span> <span m="2399880">importance</span> <span m="2400260">sampling,</span>
  <span m="2400600">just</span> <span m="2401020">don't</span> <span m="2401330">really</span>
  <span m="2401640">think</span> <span m="2401950">about</span> <span m="2402170">this</span>
  <span m="2402320">part</span> <span m="2402530">of</span> <span m="2402620">it.</span>
  <span m="2403190">Think</span> <span m="2403340">about</span> <span m="2403590">it</span>
  <span m="2403740">as</span> <span m="2403900">we're</span> <span m="2404060">sampling</span>
  <span m="2404530">from</span> <span m="2404780">this.</span> <span m="2405850">But</span>
  <span m="2405870">it</span> <span m="2405940">turns</span> <span m="2406160">out</span>
  <span m="2406250">we're</span> <span m="2406460">sampling</span> <span m="2406770">from</span>
  <span m="2406940">this</span> <span m="2407090">by</span> <span m="2407620">something</span>
  <span m="2407920">from</span> <span m="2408060">this</span> <span m="2408185">and</span>
  <span m="2408310">going</span> <span m="2408530">forward.</span> <span m="2409520">But</span>
  <span m="2409860">we're</span> <span m="2410260">still</span> <span m="2410470">sampling</span>
  <span m="2410830">from</span> <span m="2411220">this.</span></p><p><span m="2412220">So</span>
  <span m="2412700">when</span> <span m="2412870">we</span> <span m="2412990">do</span>
  <span m="2413190">that</span> <span m="2413440">and</span> <span m="2413640">we</span>
  <span m="2413720">put</span> <span m="2413960">samples,</span> <span m="2414580">most</span>
  <span m="2414940">of</span> <span m="2415010">them</span> <span m="2416190">are</span>
  <span m="2416250">going</span> <span m="2416370">to</span> <span m="2416430">end</span>
  <span m="2416600">up</span> <span m="2416730">over</span> <span m="2416930">here,</span>
  <span m="2417330">and</span> <span m="2417415">then</span> <span m="2417500">one</span>
  <span m="2417700">in</span> <span m="2417800">a</span> <span m="2417870">billion</span>
  <span m="2418290">times,</span> <span m="2419540">we</span> <span m="2419670">get</span>
  <span m="2419980">one</span> <span m="2420150">out</span> <span m="2420260">here</span>
  <span m="2420620">on</span> <span m="2420790">average.</span> <span m="2421660">Yeah.</span>
  <span m="2422790">So</span> <span m="2422950">what</span> <span m="2423160">we're</span>
  <span m="2423320">saying</span> <span m="2424200">is</span> <span m="2425020">we</span>
  <span m="2425250">could</span> <span m="2426560">define</span> <span m="2426880">a</span>
  <span m="2426940">different</span> <span m="2427360">distribution.</span> <span
  m="2427850">We're</span> <span m="2427960">jumping</span> <span m="2428210">here</span>
  <span m="2428400">a</span> <span m="2428430">little</span> <span m="2428640">bit,</span>
  <span m="2429940">but</span> <span m="2430160">let's</span> <span m="2430320">just</span>
  <span m="2430470">conceptually</span> <span m="2430800">say</span> <span m="2431050">that</span>
  <span m="2431130">distribution</span> <span m="2431550">looks</span> <span m="2431760">like</span>
  <span m="2431940">this.</span> <span m="2434190">And</span> <span m="2434340">instead</span>
  <span m="2434640">of</span> <span m="2434730">sampling</span> <span m="2435310">from</span>
  <span m="2435630">this</span> <span m="2435750">guy--</span> <span m="2437320">which</span>
  <span m="2437490">by</span> <span m="2437610">the</span> <span m="2437700">way</span>
  <span m="2437870">we</span> <span m="2438010">do</span> <span m="2438210">by</span>
  <span m="2438420">sampling</span> <span m="2438740">here</span> <span m="2438860">and</span>
  <span m="2438930">pushing</span> <span m="2439200">forward,</span> <span m="2439540">but</span>
  <span m="2439640">that's</span> <span m="2439900">not</span> <span m="2440090">really</span>
  <span m="2440370">relevant--</span> <span m="2441780">this</span> <span m="2442010">sample</span>
  <span m="2442430">from</span> <span m="2442700">this</span> <span m="2442810">guy</span>
  <span m="2443460">so</span> <span m="2443590">that</span> <span m="2443750">now</span>
  <span m="2444590">when</span> <span m="2444760">I</span> <span m="2444830">sample</span>
  <span m="2445240">from</span> <span m="2445520">here,</span> <span m="2446460">instead</span>
  <span m="2446780">of</span> <span m="2446870">1</span> <span m="2447030">in</span>
  <span m="2447120">a</span> <span m="2447180">billion,</span> <span m="2447940">maybe</span>
  <span m="2449410">1</span> <span m="2449680">in</span> <span m="2449875">10</span>
  <span m="2450070">or</span> <span m="2450150">maybe</span> <span m="2450390">half</span>
  <span m="2450630">of</span> <span m="2450700">them</span> <span m="2451970">actually</span>
  <span m="2452790">fall</span> <span m="2453020">in</span> <span m="2453110">the</span>
  <span m="2453180">regions</span> <span m="2453410">I</span> <span m="2453450">mentioned</span>
  <span m="2453830">for</span> <span m="2453940">them.</span></p><p><span m="2455930">Yep.</span>
  <span m="2456690">So</span> <span m="2456820">now</span> <span m="2457020">I'm</span>
  <span m="2457066">going</span> <span m="2457113">to</span> <span m="2457160">have</span>
  <span m="2457380">N</span> <span m="2457660">samples</span> <span m="2458100">from</span>
  <span m="2458270">this</span> <span m="2458370">guy.</span> <span m="2459790">But</span>
  <span m="2459930">now</span> <span m="2460220">when</span> <span m="2460330">I</span>
  <span m="2460470">compute</span> <span m="2460900">the</span> <span m="2461060">estimate</span>
  <span m="2461640">of</span> <span m="2461840">the</span> <span m="2462220">probability</span>
  <span m="2462770">of</span> <span m="2462920">A,</span> <span m="2463606">I</span>
  <span m="2463950">can't</span> <span m="2464250">just</span> <span m="2464730">take</span>
  <span m="2466170">the</span> <span m="2466820">fraction</span> <span m="2467090">that</span>
  <span m="2467360">are</span> <span m="2467823">here</span> <span m="2468750">divided</span>
  <span m="2469120">by</span> <span m="2469330">the</span> <span m="2469410">total</span>
  <span m="2469640">numbers.</span> <span m="2470080">Clearly</span> <span m="2470370">that</span>
  <span m="2470520">would</span> <span m="2470640">be</span> <span m="2470790">the</span>
  <span m="2470900">wrong</span> <span m="2471160">estimate.</span> <span m="2472500">But</span>
  <span m="2472660">if</span> <span m="2472850">I</span> <span m="2473000">take</span>
  <span m="2473750">each</span> <span m="2474020">sample</span> <span m="2474600">that</span>
  <span m="2475393">[? folds ?]</span> <span m="2476320">in</span> <span m="2476440">here,</span>
  <span m="2476960">the</span> <span m="2477070">1's,</span> <span m="2478360">and</span>
  <span m="2478540">multiply</span> <span m="2479100">them</span> <span m="2479420">by</span>
  <span m="2479610">the</span> <span m="2479760">ratio</span> <span m="2480700">of</span>
  <span m="2482040">this</span> <span m="2482180">guy</span> <span m="2482630">to</span>
  <span m="2482730">this</span> <span m="2482850">guy,</span> <span m="2485740">that's</span>
  <span m="2485910">going</span> <span m="2486200">to</span> <span m="2487640">recalibrate</span>
  <span m="2488310">that</span> <span m="2488380">to</span> <span m="2488500">be</span>
  <span m="2488620">the</span> <span m="2488740">right</span> <span m="2488860">estimate.</span></p><p><span
  m="2489180">And</span> <span m="2489340">you</span> <span m="2489400">can</span>
  <span m="2489500">kind</span> <span m="2489640">of</span> <span m="2489710">see</span>
  <span m="2489860">it</span> <span m="2489940">graphically,</span> <span m="2490640">because</span>
  <span m="2490850">what</span> <span m="2490970">happens</span> <span m="2491290">is</span>
  <span m="2491390">you</span> <span m="2491450">get</span> <span m="2491550">a</span>
  <span m="2491590">sample</span> <span m="2492030">here.</span> <span m="2494390">The</span>
  <span m="2494480">f</span> <span m="2494775">of</span> <span m="2494922">x</span>
  <span m="2495070">is</span> <span m="2495560">basically</span> <span m="2496050">0,</span>
  <span m="2497720">fairly</span> <span m="2498150">small.</span> <span m="2498807">This</span>
  <span m="2499244">guy</span> <span m="2499681">is</span> <span m="2499900">big.</span>
  <span m="2500120">That</span> <span m="2500300">ratio</span> <span m="2500680">is</span>
  <span m="2500830">going</span> <span m="2500960">to</span> <span m="2501040">be</span>
  <span m="2503370">really</span> <span m="2504000">small.</span> <span m="2505474">So</span>
  <span m="2506470">even</span> <span m="2506700">though</span> <span m="2506830">it's</span>
  <span m="2507000">the</span> <span m="2507090">1,</span> <span m="2507680">it</span>
  <span m="2507840">gets</span> <span m="2508010">weighted</span> <span m="2508380">by</span>
  <span m="2508700">a</span> <span m="2509060">10</span> <span m="2509420">to</span>
  <span m="2509550">the</span> <span m="2509610">minus</span> <span m="2509850">9</span>
  <span m="2510040">or</span> <span m="2510485">whatever</span> <span m="2510930">it</span>
  <span m="2511150">is,</span> <span m="2511220">or</span> <span m="2511470">10</span>
  <span m="2511650">to</span> <span m="2511730">the</span> <span m="2511810">minus</span>
  <span m="2511990">10.</span></p><p><span m="2514480">So</span> <span m="2514540">you</span>
  <span m="2514700">can</span> <span m="2514940">see</span> <span m="2516110">how</span>
  <span m="2516280">it</span> <span m="2516370">works,</span> <span m="2516580">and</span>
  <span m="2517116">it</span> <span m="2517218">all</span> <span m="2517320">works</span>
  <span m="2517500">out.</span> <span m="2518400">Draw</span> <span m="2518580">from</span>
  <span m="2518740">this</span> <span m="2518820">guy,</span> <span m="2519200">get</span>
  <span m="2519430">more</span> <span m="2519820">sample</span> <span m="2520200">than</span>
  <span m="2520320">here,</span> <span m="2521250">but</span> <span m="2521460">then</span>
  <span m="2522390">each</span> <span m="2522650">sample</span> <span m="2522890">doesn't</span>
  <span m="2523110">get</span> <span m="2523200">a</span> <span m="2523435">1.</span>
  <span m="2523670">It</span> <span m="2523770">gets</span> <span m="2523980">a</span>
  <span m="2524205">1</span> <span m="2524430">times</span> <span m="2525020">the</span>
  <span m="2525100">ratio</span> <span m="2525460">of</span> <span m="2525570">this</span>
  <span m="2525760">to</span> <span m="2525940">this.</span> <span m="2526950">And</span>
  <span m="2527140">by</span> <span m="2527190">doing</span> <span m="2527470">that,</span>
  <span m="2527530">we'll</span> <span m="2527590">be</span> <span m="2527650">weighting,</span>
  <span m="2528136">[INAUDIBLE]</span> <span m="2529110">actually</span> <span m="2529700">estimating</span>
  <span m="2530210">the</span> <span m="2530290">right</span> <span m="2530590">probability.</span>
  <span m="2532810">But</span> <span m="2532940">then</span> <span m="2533060">the</span>
  <span m="2533120">next</span> <span m="2533360">question,</span> <span m="2533710">that's</span>
  <span m="2533870">kind</span> <span m="2534010">of</span> <span m="2534070">the</span>
  <span m="2534130">next</span> <span m="2534290">thing</span> <span m="2534410">we're</span>
  <span m="2534580">going</span> <span m="2534700">to</span> <span m="2534770">talk</span>
  <span m="2534930">about</span> <span m="2535210">is,</span> <span m="2535860">how</span>
  <span m="2536100">do</span> <span m="2536190">you</span> <span m="2536740">figure</span>
  <span m="2537050">out</span> <span m="2538950">what</span> <span m="2538995">a</span>
  <span m="2539040">good</span> <span m="2539520">biasing</span> <span m="2539760">distribution</span>
  <span m="2540035">is?</span> <span m="2540103">How</span> <span m="2540172">do</span>
  <span m="2540241">you</span> <span m="2540310">come</span> <span m="2540460">up</span>
  <span m="2540570">with</span> <span m="2540680">the</span> <span m="2540760">distribution?</span></p><p><span
  m="2542290">And</span> <span m="2542545">it</span> <span m="2542800">would</span>
  <span m="2543100">be</span> <span m="2543400">easier</span> <span m="2543740">if</span>
  <span m="2543940">we</span> <span m="2544040">didn't</span> <span m="2544240">have</span>
  <span m="2544400">this</span> <span m="2544560">part</span> <span m="2544880">of</span>
  <span m="2544940">the</span> <span m="2545010">problem,</span> <span m="2546340">but</span>
  <span m="2546500">because</span> <span m="2547040">we</span> <span m="2547370">are</span>
  <span m="2548890">generating</span> <span m="2549330">the</span> <span m="2549400">samples</span>
  <span m="2549700">from</span> <span m="2549830">the</span> <span m="2549900">inputs</span>
  <span m="2550310">and</span> <span m="2550400">pushing</span> <span m="2550640">them</span>
  <span m="2550790">through</span> <span m="2551420">the</span> <span m="2551510">model,</span>
  <span m="2552650">we</span> <span m="2552770">don't</span> <span m="2552990">necessarily</span>
  <span m="2553740">know</span> <span m="2554180">how</span> <span m="2554530">to</span>
  <span m="2554660">bias</span> <span m="2554950">the</span> <span m="2555030">distribution</span>
  <span m="2555680">here</span> <span m="2556000">so</span> <span m="2556110">that</span>
  <span m="2556210">we</span> <span m="2556330">get</span> <span m="2557020">a</span>
  <span m="2557080">good</span> <span m="2557230">biasing</span> <span m="2557570">distribution</span>
  <span m="2558470">here.</span> <span m="2559260">And</span> <span m="2559350">that's</span>
  <span m="2559720">like</span> <span m="2559890">saying</span> <span m="2561100">do</span>
  <span m="2561220">you</span> <span m="2561350">know</span> <span m="2561520">what</span>
  <span m="2561690">combination</span> <span m="2562210">of</span> <span m="2562290">inputs</span>
  <span m="2562940">makes</span> <span m="2563440">your</span> <span m="2563560">aircraft</span>
  <span m="2564110">much</span> <span m="2564420">vulnerable</span> <span m="2564810">to</span>
  <span m="2564910">failure.</span> <span m="2565960">And</span> <span m="2566110">sometimes</span>
  <span m="2566450">you</span> <span m="2566600">do,</span> <span m="2566770">and</span>
  <span m="2566930">sometimes</span> <span m="2567340">you</span> <span m="2567440">don't.</span></p><p><span
  m="2569030">So</span> <span m="2569075">again,</span> <span m="2569120">that's</span>
  <span m="2570130">kind</span> <span m="2570290">of</span> <span m="2570400">the</span>
  <span m="2570480">separate</span> <span m="2570860">part.</span> <span m="2571370">Part</span>
  <span m="2571570">of</span> <span m="2571650">it</span> <span m="2571730">is</span>
  <span m="2571810">a</span> <span m="2571850">little</span> <span m="2572050">bit</span>
  <span m="2572500">different</span> <span m="2572840">to</span> <span m="2572950">describe.</span>
  <span m="2575920">Yeah.</span></p><p><span m="2576420">AUDIENCE:</span> <span m="2576920">So</span>
  <span m="2577420">you</span> <span m="2577920">could</span> <span m="2578086">take</span>
  <span m="2578253">like</span> <span m="2578420">a</span> <span m="2578920">Gaussian</span>
  <span m="2579420">variance</span> <span m="2579920">with</span> <span m="2580170">a</span>
  <span m="2580420">[? unit ?]</span> <span m="2580920">and</span> <span m="2581041">plot</span>
  <span m="2581163">that</span> <span m="2581285">over</span> <span m="2581407">there?</span></p><p><span
  m="2581894">KAREN WILLCOX:</span> <span m="2582381">Yeah.</span> <span m="2582870">You</span>
  <span m="2583312">could.</span></p><p><span m="2583754">AUDIENCE:</span> <span m="2584196">Would</span>
  <span m="2584306">that</span> <span m="2584417">be</span> <span m="2584527">like</span>
  <span m="2584638">[? an ?]</span> <span m="2584859">example?</span></p><p><span
  m="2585080">KAREN WILLCOX:</span> <span m="2585501">Yeah.</span> <span m="2586764">So</span>
  <span m="2587610">really</span> <span m="2587870">simple</span> <span m="2588190">things</span>
  <span m="2588470">that</span> <span m="2588610">people</span> <span m="2588920">do</span>
  <span m="2589200">is</span> <span m="2589590">that</span> <span m="2589890">they,</span>
  <span m="2590275">and</span> <span m="2590660">we'll</span> <span m="2590810">look,</span>
  <span m="2590960">they</span> <span m="2591090">scale</span> <span m="2591580">this</span>
  <span m="2591760">thing</span> <span m="2592050">to</span> <span m="2592160">shift</span>
  <span m="2592430">more</span> <span m="2592650">mass.</span> <span m="2593400">Well,</span>
  <span m="2593570">what</span> <span m="2593700">I</span> <span m="2593750">drew</span>
  <span m="2593880">here</span> <span m="2594070">is</span> <span m="2594140">a</span>
  <span m="2594190">little</span> <span m="2594390">bit</span> <span m="2595170">extreme.</span>
  <span m="2596840">They</span> <span m="2596940">scale</span> <span m="2597063">it</span>
  <span m="2597186">to</span> <span m="2597310">shift</span> <span m="2597590">more</span>
  <span m="2597750">mass,</span> <span m="2598090">and</span> <span m="2598200">they</span>
  <span m="2598350">basically</span> <span m="2598720">make</span> <span m="2598910">this</span>
  <span m="2599040">thing</span> <span m="2599200">have</span> <span m="2599330">better</span>
  <span m="2599685">tails.</span> <span m="2602240">And</span> <span m="2602340">sometimes</span>
  <span m="2602980">they</span> <span m="2603060">actually</span> <span m="2603260">just</span>
  <span m="2603530">shift</span> <span m="2603830">it.</span> <span m="2604320">We'll</span>
  <span m="2604460">take</span> <span m="2604690">whatever</span> <span m="2604900">the</span>
  <span m="2604980">distribution</span> <span m="2605420">is</span> <span m="2605580">and</span>
  <span m="2605700">just</span> <span m="2605920">shift</span> <span m="2606170">it</span>
  <span m="2606280">and</span> <span m="2606391">scale</span> <span m="2606501">it.</span>
  <span m="2609270">And</span> <span m="2609660">then</span> <span m="2609710">there</span>
  <span m="2609760">are</span> <span m="2609810">more</span> <span m="2609950">sophisticated</span>
  <span m="2610450">things</span> <span m="2610620">you</span> <span m="2610710">can</span>
  <span m="2610870">do,</span> <span m="2611040">but,</span> <span m="2611180">in</span>
  <span m="2611280">fact,</span> <span m="2611610">this</span> <span m="2611780">is</span>
  <span m="2612280">somewhat</span> <span m="2612600">of</span> <span m="2612720">an</span>
  <span m="2612820">open</span> <span m="2613130">question</span> <span m="2613440">is</span>
  <span m="2613560">how</span> <span m="2613850">do</span> <span m="2613930">you,</span>
  <span m="2614170">[INAUDIBLE]</span> <span m="2616980">define</span> <span m="2617220">a</span>
  <span m="2617460">good</span> <span m="2618180">biasing</span> <span m="2618370">distribution</span>
  <span m="2620380">to</span> <span m="2621300">make</span> <span m="2621560">your</span>
  <span m="2622070">sampling</span> <span m="2622450">really</span> <span m="2622850">efficient?</span></p><p><span
  m="2624323">AUDIENCE:</span> <span m="2624814">I</span> <span m="2625305">would</span>
  <span m="2625796">think</span> <span m="2626287">that</span> <span m="2626778">it</span>
  <span m="2627269">would</span> <span m="2627760">[INAUDIBLE].</span></p><p><span
  m="2636107">KAREN WILLCOX:</span> <span m="2636598">That's</span> <span m="2637089">right.</span>
  <span m="2638080">And</span> <span m="2638460">so</span> <span m="2639510">usually</span>
  <span m="2639920">in</span> <span m="2640060">the</span> <span m="2640130">cases</span>
  <span m="2640840">where</span> <span m="2641890">it's</span> <span m="2642090">easy</span>
  <span m="2642330">to</span> <span m="2642400">come</span> <span m="2642540">up</span>
  <span m="2642620">with</span> <span m="2642720">a</span> <span m="2642810">biasing</span>
  <span m="2643110">distribution,</span> <span m="2643690">you</span> <span m="2643780">kind</span>
  <span m="2643960">of</span> <span m="2644040">know</span> <span m="2644230">what</span>
  <span m="2644400">conditions</span> <span m="2645360">including</span> <span m="2645440">failure</span>
  <span m="2645790">anywhere.</span> <span m="2646970">And</span> <span m="2647365">so</span>
  <span m="2647760">it's</span> <span m="2647825">sort</span> <span m="2647890">of</span>
  <span m="2648040">obvious</span> <span m="2648360">way</span> <span m="2648670">to</span>
  <span m="2649063">look.</span> <span m="2649850">The</span> <span m="2649980">really</span>
  <span m="2650200">difficult</span> <span m="2650850">problems</span> <span m="2651520">are</span>
  <span m="2651740">when</span> <span m="2652450">there's</span> <span m="2653780">tens,</span>
  <span m="2654025">hundreds,</span> <span m="2654270">thousands</span> <span m="2655140">of</span>
  <span m="2655200">them</span> <span m="2655380">that</span> <span m="2655530">are</span>
  <span m="2655923">through</span> <span m="2656316">input</span> <span m="2656513">here.</span>
  <span m="2656710">We</span> <span m="2656880">don't</span> <span m="2657120">even</span>
  <span m="2657320">know</span> <span m="2657490">which</span> <span m="2657760">combinations</span>
  <span m="2658370">of</span> <span m="2658450">input</span> <span m="2658630">to</span>
  <span m="2658920">the</span> <span m="2659210">ones</span> <span m="2659500">that</span>
  <span m="2659640">make</span> <span m="2659770">you</span> <span m="2659870">most</span>
  <span m="2660520">vulnerable</span> <span m="2660990">to</span> <span m="2661090">failure.</span>
  <span m="2661960">And</span> <span m="2662100">the</span> <span m="2662160">only</span>
  <span m="2662300">way</span> <span m="2662470">to</span> <span m="2662540">find</span>
  <span m="2662810">out</span> <span m="2662930">would</span> <span m="2663040">be</span>
  <span m="2663110">to</span> <span m="2663190">sample</span> <span m="2663630">them</span>
  <span m="2663950">all,</span> <span m="2664250">which</span> <span m="2664450">we</span>
  <span m="2664570">already</span> <span m="2664710">said</span> <span m="2664850">we</span>
  <span m="2664990">don't</span> <span m="2665130">want</span> <span m="2665270">to</span>
  <span m="2665330">do.</span></p><p><span m="2666356">So</span> <span m="2670080">aircraft</span>
  <span m="2670430">design</span> <span m="2670690">is</span> <span m="2670760">a</span>
  <span m="2670875">good</span> <span m="2670990">one,</span> <span m="2671200">also</span>
  <span m="2671420">people</span> <span m="2671710">who</span> <span m="2671820">simulate</span>
  <span m="2672660">earthquakes</span> <span m="2673340">and</span> <span m="2673490">all</span>
  <span m="2673640">these</span> <span m="2673830">kinds</span> <span m="2674030">of</span>
  <span m="2674110">things,</span> <span m="2674400">I</span> <span m="2674810">mean,</span>
  <span m="2674900">where</span> <span m="2675290">events</span> <span m="2676200">of</span>
  <span m="2677110">different</span> <span m="2677920">weather</span> <span m="2678230">stuff.</span>
  <span m="2680380">It's</span> <span m="2680500">not</span> <span m="2680660">even</span>
  <span m="2680860">clear</span> <span m="2681130">sometimes</span> <span m="2681560">that</span>
  <span m="2681680">you</span> <span m="2681790">can</span> <span m="2682000">simulate</span>
  <span m="2683923">and</span> <span m="2684394">get</span> <span m="2685340">good</span>
  <span m="2685560">estimates</span> <span m="2686560">for</span> <span m="2688460">some</span>
  <span m="2688710">of</span> <span m="2688790">these</span> <span m="2688980">events.</span></p><p><span
  m="2691830">AUDIENCE:</span> <span m="2692305">[INAUDIBLE].</span></p><p><span m="2696375">KAREN
  WILLCOX:</span> <span m="2696640">Yeah.</span> <span m="2696960">In</span> <span
  m="2697100">some</span> <span m="2697280">places,</span> <span m="2699450">it's</span>
  <span m="2699620">really</span> <span m="2699960">hard</span> <span m="2700130">for</span>
  <span m="2700270">us</span> <span m="2700380">to</span> <span m="2700450">characterize</span>
  <span m="2701120">what</span> <span m="2701340">q</span> <span m="2701690">is</span>
  <span m="2702040">out</span> <span m="2702215">here.</span> <span m="2702390">The</span>
  <span m="2702480">financial</span> <span m="2702910">markets</span> <span m="2703230">are</span>
  <span m="2703260">another</span> <span m="2703510">one.</span> <span m="2704180">I</span>
  <span m="2704680">don't</span> <span m="2704760">know</span> <span m="2704840">if</span>
  <span m="2704920">you</span> <span m="2705010">guys</span> <span m="2705180">realize</span>
  <span m="2705370"><i>The</i></span> <span m="2705460"><i>Black</i></span> <span
  m="2705530"><i>Swan</i></span> <span m="2705820">book,</span> <span m="2706110">so</span>
  <span m="2706560">it's</span> <span m="2706680">all</span> <span m="2706770">about</span>
  <span m="2707160">[? fact ?]</span> <span m="2707470">tails</span> <span m="2707920">and</span>
  <span m="2708175">suit</span> <span m="2708430">and</span> <span m="2708930">models</span>
  <span m="2710510">and</span> <span m="2711180">don't</span> <span m="2711620">account</span>
  <span m="2712040">for</span> <span m="2712610">things</span> <span m="2712900">that</span>
  <span m="2713020">are</span> <span m="2713130">like</span> <span m="2713330">way</span>
  <span m="2713680">out</span> <span m="2713910">here,</span> <span m="2714860">that</span>
  <span m="2715010">are</span> <span m="2715100">really</span> <span m="2715490">unlikely,</span>
  <span m="2716070">but</span> <span m="2716220">when</span> <span m="2716380">they</span>
  <span m="2716490">happen,</span> <span m="2716583">they</span> <span m="2716629">have</span>
  <span m="2716676">a</span> <span m="2716770">really</span> <span m="2717231">big</span>
  <span m="2717692">impact.</span></p><p><span m="2718614">So</span> <span m="2721380">if</span>
  <span m="2721610">we</span> <span m="2721800">knew</span> <span m="2722000">what</span>
  <span m="2722140">was</span> <span m="2722310">going</span> <span m="2722580">on</span>
  <span m="2722730">here,</span> <span m="2722960">we</span> <span m="2723070">would</span>
  <span m="2723430">already</span> <span m="2723660">know</span> <span m="2723860">the</span>
  <span m="2724040">probabilities.</span> <span m="2725040">And</span> <span m="2725275">so</span>
  <span m="2725510">the</span> <span m="2725600">trick</span> <span m="2725800">is</span>
  <span m="2725900">that</span> <span m="2726020">we</span> <span m="2726100">don't</span>
  <span m="2726310">know</span> <span m="2726420">what's</span> <span m="2726600">going</span>
  <span m="2726870">on</span> <span m="2727450">here,</span> <span m="2728010">but</span>
  <span m="2728140">we</span> <span m="2728220">want</span> <span m="2728340">to</span>
  <span m="2728400">learn</span> <span m="2728620">about</span> <span m="2728830">what's</span>
  <span m="2729000">going</span> <span m="2729270">on</span> <span m="2729440">here</span>
  <span m="2729720">by</span> <span m="2730100">finding</span> <span m="2730640">better</span>
  <span m="2730810">ways</span> <span m="2730970">to</span> <span m="2731100">sample.</span>
  <span m="2731930">But</span> <span m="2732015">to</span> <span m="2732100">find</span>
  <span m="2732290">better</span> <span m="2732420">ways</span> <span m="2732650">to</span>
  <span m="2732740">sample,</span> <span m="2733120">we</span> <span m="2733400">need</span>
  <span m="2733510">to</span> <span m="2733580">know</span> <span m="2733730">what</span>
  <span m="2733850">we're</span> <span m="2733970">looking</span> <span m="2734260">for.</span>
  <span m="2736260">So</span> <span m="2736325">then</span> <span m="2736390">there</span>
  <span m="2736510">are</span> <span m="2736580">things,</span> <span m="2737030">I</span>
  <span m="2737070">mean,</span> <span m="2737210">this</span> <span m="2737330">still</span>
  <span m="2737480">always</span> <span m="2737650">happens,</span> <span m="2738000">and</span>
  <span m="2738520">this</span> <span m="2738950">is</span> <span m="2739060">what</span>
  <span m="2739380">keeps</span> <span m="2739600">us</span> <span m="2739710">busy</span>
  <span m="2739940">in</span> <span m="2740060">research</span> <span m="2740580">is</span>
  <span m="2740810">that's</span> <span m="2741050">where</span> <span m="2741510">you're</span>
  <span m="2742000">using</span> <span m="2742130">activity.</span> <span m="2742575">You</span>
  <span m="2742850">learn</span> <span m="2743120">a</span> <span m="2743190">little</span>
  <span m="2743380">bit</span> <span m="2743580">and</span> <span m="2743690">sample.</span></p><p><span
  m="2746480">So</span> <span m="2746945">let's</span> <span m="2749740">just</span>
  <span m="2750790">quickly</span> <span m="2751320">summarize</span> <span m="2754770">the</span>
  <span m="2755030">steps</span> <span m="2755530">for</span> <span m="2755800">importance</span>
  <span m="2756230">sampling.</span> <span m="2756880">So</span> <span m="2757265">we're</span>
  <span m="2757650">going</span> <span m="2757780">to</span> <span m="2757850">define</span>
  <span m="2759870">a</span> <span m="2759980">w</span> <span m="2760350">of</span>
  <span m="2760645">x</span> <span m="2760792">and</span> <span m="2760940">however</span>
  <span m="2761160">we</span> <span m="2761270">come</span> <span m="2761460">up,</span>
  <span m="2762990">we're</span> <span m="2763110">going</span> <span m="2763230">to</span>
  <span m="2763300">draw</span> <span m="2764000">samples</span> <span m="2766340">of</span>
  <span m="2766540">x</span> <span m="2770240">from</span> <span m="2770450">that</span>
  <span m="2770660">pdf.</span> <span m="2774650">So</span> <span m="2774820">I'll</span>
  <span m="2774880">just</span> <span m="2775335">note</span> <span m="2775790">here</span>
  <span m="2776150">that</span> <span m="2776280">this</span> <span m="2776410">is</span>
  <span m="2776510">a</span> <span m="2776650">pdf.</span> <span m="2777063">If</span>
  <span m="2777476">you</span> <span m="2777890">prefer</span> <span m="2778370">to</span>
  <span m="2778515">call</span> <span m="2778660">it</span> <span m="2778730">f</span>
  <span m="2778765">sub</span> <span m="2778800">w,</span> <span m="2779238">that's</span>
  <span m="2779676">fine.</span> <span m="2781870">And</span> <span m="2782040">again,</span>
  <span m="2782370">the</span> <span m="2782480">idea</span> <span m="2782850">is</span>
  <span m="2782960">we</span> <span m="2783040">want</span> <span m="2783170">to</span>
  <span m="2783230">get</span> <span m="2783410">more</span> <span m="2783750">samples</span>
  <span m="2786430">in</span> <span m="2786530">the</span> <span m="2786600">region</span>
  <span m="2786880">of</span> <span m="2786960">interest.</span></p><p><span m="2794420">And</span>
  <span m="2794780">then</span> <span m="2794890">we're</span> <span m="2795030">going</span>
  <span m="2795170">to</span> <span m="2795240">estimate</span> <span m="2802290">this</span>
  <span m="2802770">probability,</span> <span m="2803110">but</span> <span m="2803870">we're</span>
  <span m="2803960">going</span> <span m="2804100">to</span> <span m="2804160">do</span>
  <span m="2804330">it</span> <span m="2806940">using</span> <span m="2808800">this</span>
  <span m="2808980">thing</span> <span m="2809220">here</span> <span m="2809530">that</span>
  <span m="2809680">we</span> <span m="2809820">define,</span> <span m="2810580">the</span>
  <span m="2810710">P</span> <span m="2811191">hat,</span> <span m="2812153">IS,</span>
  <span m="2813600">where</span> <span m="2814460">we</span> <span m="2814630">have</span>
  <span m="2814820">to</span> <span m="2814930">do</span> <span m="2815100">the</span>
  <span m="2815190">weighting</span> <span m="2815850">to</span> <span m="2816000">account</span>
  <span m="2816520">for</span> <span m="2816610">the</span> <span m="2816680">fact</span>
  <span m="2820310">that</span> <span m="2820440">we</span> <span m="2820530">drew</span>
  <span m="2820700">from</span> <span m="2821000">the</span> <span m="2821700">wrong</span>
  <span m="2821870">distribution.</span> <span m="2825895">So</span> <span m="2828370">importance</span>
  <span m="2829855">weights</span> <span m="2835746">if</span> <span m="2837030">x</span>
  <span m="2838000">divided</span> <span m="2838350">by</span> <span m="2838450">the</span>
  <span m="2838540">w,</span> <span m="2839840">that's</span> <span m="2839980">the</span>
  <span m="2840090">sample</span> <span m="2840430">point.</span></p><p><span m="2843900">And</span>
  <span m="2844020">one</span> <span m="2844130">thing</span> <span m="2844260">I</span>
  <span m="2844340">should</span> <span m="2844530">say</span> <span m="2844760">actually</span>
  <span m="2845010">is</span> <span m="2845110">if</span> <span m="2845250">you</span>
  <span m="2845350">don't</span> <span m="2845580">choose</span> <span m="2845720">a</span>
  <span m="2845920">good</span> <span m="2846055">w,</span> <span m="2846190">you</span>
  <span m="2846330">can</span> <span m="2846470">actually</span> <span m="2846660">make</span>
  <span m="2846820">it</span> <span m="2846920">worse.</span> <span m="2847480">You</span>
  <span m="2847580">could</span> <span m="2847760">make</span> <span m="2847980">your</span>
  <span m="2848060">Monte</span> <span m="2848260">Carlo</span> <span m="2848970">convergence</span>
  <span m="2852230">worse.</span> <span m="2855110">So</span> <span m="2855610">actually,</span>
  <span m="2855880">I</span> <span m="2856030">think</span> <span m="2856180">there's</span>
  <span m="2856280">one</span> <span m="2856580">final</span> <span m="2856940">result</span>
  <span m="2857440">to</span> <span m="2857650">write</span> <span m="2857850">down</span>
  <span m="2858270">is</span> <span m="2858740">what</span> <span m="2859192">are</span>
  <span m="2859644">the</span> <span m="2863360">properties</span> <span m="2863930">of</span>
  <span m="2864060">this</span> <span m="2864970">P</span> <span m="2865260">hat</span>
  <span m="2866436">IS?</span> <span m="2868310">They</span> <span m="2868580">are</span>
  <span m="2871040">that</span> <span m="2871240">the</span> <span m="2871480">expected</span>
  <span m="2872150">value</span> <span m="2872820">of</span> <span m="2873230">our</span>
  <span m="2875480">importance</span> <span m="2875910">sampling</span> <span m="2876850">estimator</span>
  <span m="2877530">for</span> <span m="2877690">the</span> <span m="2877760">probability</span>
  <span m="2878340">of</span> <span m="2878440">A.</span> <span m="2880570">What</span>
  <span m="2880680">do</span> <span m="2880710">you</span> <span m="2880740">think</span>
  <span m="2880930">it</span> <span m="2881000">is?</span></p><p><span m="2888680">Hopefully,</span>
  <span m="2889140">it's</span> <span m="2889280">P</span> <span m="2889650">of</span>
  <span m="2890020">A.</span> <span m="2890390">It</span> <span m="2890630">is,</span>
  <span m="2890920">indeed,</span> <span m="2891215">P</span> <span m="2891313">of</span>
  <span m="2891411">A.</span> <span m="2891510">And</span> <span m="2891630">that's</span>
  <span m="2891780">actually,</span> <span m="2893530">I</span> <span m="2893610">mean,</span>
  <span m="2894720">we</span> <span m="2894880">didn't</span> <span m="2895040">do</span>
  <span m="2895170">anything</span> <span m="2895550">over</span> <span m="2895720">here</span>
  <span m="2896040">except</span> <span m="2896160">move</span> <span m="2896340">things</span>
  <span m="2896590">around.</span> <span m="2897780">We</span> <span m="2897930">had</span>
  <span m="2898080">equality</span> <span m="2898550">all</span> <span m="2898650">the</span>
  <span m="2898710">way</span> <span m="2898840">through.</span> <span m="2899240">So</span>
  <span m="2899640">that's</span> <span m="2899900">key.</span> <span m="2901176">We</span>
  <span m="2901584">dumbed</span> <span m="2901992">this</span> <span m="2902400">down</span>
  <span m="2902750">with</span> <span m="2902970">the</span> <span m="2904290">expected</span>
  <span m="2904740">value.</span> <span m="2905710">In</span> <span m="2905820">other</span>
  <span m="2906130">words,</span> <span m="2906310">it's</span> <span m="2906605">unbiased.</span>
  <span m="2908280">But</span> <span m="2908460">then</span> <span m="2909570">the</span>
  <span m="2909670">key</span> <span m="2909900">is</span> <span m="2910090">that--</span>
  <span m="2910495">you</span> <span m="2910900">could</span> <span m="2910980">put</span>
  <span m="2911110">a</span> <span m="2912600">w</span> <span m="2912930">in</span>
  <span m="2913050">here</span> <span m="2913980">to</span> <span m="2914090">be</span>
  <span m="2914190">clear--</span> <span m="2915030">that</span> <span m="2915190">the</span>
  <span m="2915260">variance</span> <span m="2916200">of</span> <span m="2916480">the</span>
  <span m="2916580">estimator,</span> <span m="2917440">which</span> <span m="2917660">again</span>
  <span m="2918010">controls</span> <span m="2919730">basically</span> <span m="2920170">how</span>
  <span m="2920350">good</span> <span m="2920550">it</span> <span m="2920640">is</span>
  <span m="2920810">for</span> <span m="2920940">a</span> <span m="2920980">given</span>
  <span m="2921180">number</span> <span m="2921380">of</span> <span m="2921480">samples,</span>
  <span m="2923070">has</span> <span m="2923250">got</span> <span m="2923450">this</span>
  <span m="2923905">more</span> <span m="2924360">complicated</span> <span m="2924815">expression.</span></p><p><span
  m="2925270">So</span> <span m="2925725">the</span> <span m="2926180">1</span> <span
  m="2926295">over</span> <span m="2926410">N</span> <span m="2926525">is</span> <span
  m="2926640">still</span> <span m="2926870">out</span> <span m="2927830">there.</span>
  <span m="2929500">And</span> <span m="2929660">then</span> <span m="2929820">there</span>
  <span m="2929940">is</span> <span m="2930190">an</span> <span m="2930340">expectation</span>
  <span m="2931060">of</span> <span m="2932803">i</span> <span m="2933264">of</span>
  <span m="2934186">A,</span> <span m="2936030">f</span> <span m="2936491">of</span>
  <span m="2936960">x</span> <span m="2937100">over</span> <span m="2937330">w</span>
  <span m="2938076">of</span> <span m="2938450">x,</span> <span m="2938810">and</span>
  <span m="2939255">then</span> <span m="2939700">there</span> <span m="2940145">is</span>
  <span m="2940590">a</span> <span m="2941035">minus</span> <span m="2941480">t</span>
  <span m="2941702">of</span> <span m="2941925">A</span> <span m="2942370">squared.</span>
  <span m="2943167">I</span> <span m="2943634">think</span> <span m="2944101">I</span>
  <span m="2944335">got</span> <span m="2944570">all</span> <span m="2944640">the</span>
  <span m="2944710">pieces.</span> <span m="2951510">And</span> <span m="2951610">that</span>
  <span m="2951770">actually</span> <span m="2952020">goes</span> <span m="2952133">back</span>
  <span m="2952246">to</span> <span m="2952360">what</span> <span m="2952570">I</span>
  <span m="2952610">was</span> <span m="2952730">just</span> <span m="2952860">saying.</span>
  <span m="2953360">It's</span> <span m="2953530">not</span> <span m="2953660">actually</span>
  <span m="2953930">obvious</span> <span m="2954530">whether</span> <span m="2954800">this</span>
  <span m="2955100">is</span> <span m="2955400">smaller</span> <span m="2955660">or</span>
  <span m="2955920">bigger</span> <span m="2956200">than</span> <span m="2956360">what</span>
  <span m="2956520">we</span> <span m="2956640">had</span> <span m="2956800">before</span>
  <span m="2957220">with</span> <span m="2957360">the</span> <span m="2957430">regular</span>
  <span m="2957690">Monte</span> <span m="2957930">Carlo</span> <span m="2958170">estimator,</span>
  <span m="2959130">but</span> <span m="2959270">of</span> <span m="2959360">course,</span>
  <span m="2959550">it</span> <span m="2959760">all</span> <span m="2959840">comes</span>
  <span m="2960100">down</span> <span m="2960440">to</span> <span m="2960560">the</span>
  <span m="2960890">choice</span> <span m="2961180">of</span> <span m="2961650">w.</span>
  <span m="2962120">I</span> <span m="2962590">mean,</span> <span m="2962620">the</span>
  <span m="2962650">idea</span> <span m="2962680">of</span> <span m="2962710">choose</span>
  <span m="2962725">a</span> <span m="2962740">w</span> <span m="2963280">to</span>
  <span m="2963390">make</span> <span m="2963610">this</span> <span m="2963710">small</span>
  <span m="2966340">so</span> <span m="2966470">that</span> <span m="2966610">you</span>
  <span m="2966700">get</span> <span m="2966860">away</span> <span m="2967080">with</span>
  <span m="2967505">fewer</span> <span m="2967930">sampling.</span></p><p><span m="2976360">That's</span>
  <span m="2976510">kind</span> <span m="2976650">of</span> <span m="2976710">neat</span>
  <span m="2976760">trick,</span> <span m="2977120">no?</span> <span m="2980410">Multiplying</span>
  <span m="2980960">and</span> <span m="2981080">dividing</span> <span m="2981450">by</span>
  <span m="2981600">things,</span> <span m="2982418">no?</span></p><p><span m="2982876">AUDIENCE:</span>
  <span m="2983334">[INAUDIBLE].</span></p><p><span m="2984708">KAREN WILLCOX:</span>
  <span m="2985170">It's</span> <span m="2985370">what?</span></p><p><span m="2985700">AUDIENCE:</span>
  <span m="2986175">[INAUDIBLE].</span></p><p><span m="2987125">KAREN WILLCOX:</span>
  <span m="2987600">Yeah.</span> <span m="2988550">It</span> <span m="2988720">used</span>
  <span m="2988870">to</span> <span m="2989115">always</span> <span m="2989360">drive</span>
  <span m="2989620">me</span> <span m="2989830">crazy</span> <span m="2990220">when</span>
  <span m="2991540">I</span> <span m="2991630">was</span> <span m="2991750">an</span>
  <span m="2991830">undergrad.</span></p><p><span m="2992523">AUDIENCE:</span> <span
  m="2992986">[INAUDIBLE]</span></p><p><span m="2995301">KAREN WILLCOX:</span> <span
  m="2995764">So</span> <span m="2996780">next</span> <span m="2997100">just</span>
  <span m="2997400">briefly</span> <span m="2998390">how</span> <span m="2998570">to</span>
  <span m="2998680">pick,</span> <span m="2998910">and</span> <span m="2999030">I'm</span>
  <span m="2999120">not</span> <span m="2999300">going</span> <span m="2999420">to</span>
  <span m="2999490">give,</span> <span m="2999780">sorry,</span> <span m="3000197">[?
  Trey, ?]</span> <span m="3000614">I'm</span> <span m="3000697">not</span> <span
  m="3000780">going</span> <span m="3000864">to</span> <span m="3000947">give</span>
  <span m="3001031">you</span> <span m="3001450">any</span> <span m="3002280">definitive</span>
  <span m="3002760">answers</span> <span m="3003050">on</span> <span m="3003170">this,</span>
  <span m="3003260">but</span> <span m="3003660">how</span> <span m="3003770">to</span>
  <span m="3003880">pick</span> <span m="3005090">the</span> <span m="3005210">biasing</span>
  <span m="3005820">distributions.</span> <span m="3008985">So</span> <span m="3009432">what</span>
  <span m="3009879">do</span> <span m="3010326">you</span> <span m="3010780">do?</span></p><p><span
  m="3010930">So</span> <span m="3011300">we'll</span> <span m="3011485">just</span>
  <span m="3011670">look</span> <span m="3011910">at</span> <span m="3012030">two</span>
  <span m="3016476">yeah?</span></p><p><span m="3016970">AUDIENCE:</span> <span m="3017464">[INAUDIBLE].</span></p><p><span
  m="3026356">KAREN WILLCOX:</span> <span m="3026860">Oh,</span> <span m="3027060">here?</span>
  <span m="3027390">Yeah.</span> <span m="3027910">Just</span> <span m="3028290">like</span>
  <span m="3028440">all</span> <span m="3029890">of</span> <span m="3029950">the</span>
  <span m="3030030">variances</span> <span m="3030610">of</span> <span m="3031100">the</span>
  <span m="3031190">estimators</span> <span m="3031580">have</span> <span m="3032720">like</span>
  <span m="3032910">sigma</span> <span m="3033230">y</span> <span m="3033620">or</span>
  <span m="3034055">P</span> <span m="3034490">of</span> <span m="3034680">A</span>
  <span m="3034715">or</span> <span m="3034750">whatever</span> <span m="3035050">it</span>
  <span m="3035320">is.</span></p><p><span m="3035806">AUDIENCE:</span> <span m="3036292">[INAUDIBLE].</span></p><p><span
  m="3041152">KAREN WILLCOX:</span> <span m="3041638">Yeah.</span> <span m="3043100">Remember</span>
  <span m="3043690">like</span> <span m="3043890">the</span> <span m="3044000">original.</span>
  <span m="3045120">Even</span> <span m="3045860">the</span> <span m="3045930">variance</span>
  <span m="3046340">to</span> <span m="3046430">the</span> <span m="3046510">mean</span>
  <span m="3046740">estimate</span> <span m="3047140">is</span> <span m="3047400">sigma</span>
  <span m="3047730">y,</span> <span m="3047870">sigma</span> <span m="3048346">squared</span>
  <span m="3048822">over</span> <span m="3049300">N,</span> <span m="3049520">and</span>
  <span m="3049610">you</span> <span m="3049670">don't</span> <span m="3049830">know</span>
  <span m="3049970">sigma.</span> <span m="3051060">So</span> <span m="3051160">you</span>
  <span m="3051250">can</span> <span m="3051380">plug</span> <span m="3051550">in</span>
  <span m="3051720">the</span> <span m="3051850">estimates,</span> <span m="3052360">but</span>
  <span m="3052460">then</span> <span m="3052560">you're</span> <span m="3052670">introducing</span>
  <span m="3053163">additional</span> <span m="3053656">error.</span> <span m="3055630">Yeah.</span>
  <span m="3058190">To</span> <span m="3058310">actually</span> <span m="3058630">compute</span>
  <span m="3059060">them,</span> <span m="3059300">you</span> <span m="3059390">have</span>
  <span m="3059570">to</span> <span m="3059670">use</span> <span m="3059840">an</span>
  <span m="3059930">estimate</span> <span m="3060185">for</span> <span m="3061440">P</span>
  <span m="3061760">of</span> <span m="3062240">A.</span> <span m="3062728">Yeah.</span></p><p><span
  m="3063216">AUDIENCE:</span> <span m="3063704">[INAUDIBLE].</span></p><p><span m="3065656">KAREN
  WILLCOX:</span> <span m="3066144">Yep.</span></p><p>&nbsp;</p><p><span m="3068584">AUDIENCE:</span>
  <span m="3069072">[INAUDIBLE].</span></p><p><span m="3073464">KAREN WILLCOX:</span>
  <span m="3073952">Yeah.</span> <span m="3074950">So</span> <span m="3075030">this</span>
  <span m="3075200">is</span> <span m="3075630">the</span> <span m="3075770">theoretical</span>
  <span m="3076150">expression</span> <span m="3076610">for</span> <span m="3076730">the</span>
  <span m="3076850">thing.</span> <span m="3077140">How</span> <span m="3077240">you</span>
  <span m="3077400">actually</span> <span m="3077660">compute</span> <span m="3078120">this</span>
  <span m="3078430">is</span> <span m="3078590">a</span> <span m="3078640">whole</span>
  <span m="3079570">other</span> <span m="3079830">question,</span> <span m="3080050">but</span>
  <span m="3080150">we've</span> <span m="3080230">seen</span> <span m="3080440">that</span>
  <span m="3080590">with</span> <span m="3080720">every</span> <span m="3081000">single</span>
  <span m="3081230">one</span> <span m="3081370">of</span> <span m="3081450">the</span>
  <span m="3081520">variances</span> <span m="3081860">of</span> <span m="3082590">our</span>
  <span m="3082730">estimator.</span> <span m="3083320">We</span> <span m="3083730">had</span>
  <span m="3084550">sigma</span> <span m="3084930">squared</span> <span m="3085280">over</span>
  <span m="3085775">N.</span> <span m="3086270">We</span> <span m="3086430">didn't</span>
  <span m="3086610">know</span> <span m="3086700">what</span> <span m="3086820">this</span>
  <span m="3087000">was.</span> <span m="3087950">On</span> <span m="3088210">the</span>
  <span m="3088360">original</span> <span m="3088510">one,</span> <span m="3088730">we</span>
  <span m="3088850">had</span> <span m="3089070">t1</span> <span m="3089526">minus</span>
  <span m="3089982">t</span> <span m="3090440">over</span> <span m="3090820">N.</span>
  <span m="3091500">We</span> <span m="3091840">didn't</span> <span m="3091966">know</span>
  <span m="3092093">what</span> <span m="3092220">this</span> <span m="3092390">was.</span>
  <span m="3093220">So</span> <span m="3094100">all</span> <span m="3094650">of</span>
  <span m="3094770">them</span> <span m="3095116">have</span> <span m="3095462">got</span>
  <span m="3095810">the</span> <span m="3095930">theoretical</span> <span m="3096360">result</span>
  <span m="3096650">and</span> <span m="3096930">how</span> <span m="3097040">you</span>
  <span m="3097200">compute</span> <span m="3097600">them.</span></p><p><span m="3098470">And</span>
  <span m="3098770">you</span> <span m="3098880">could</span> <span m="3099040">compute</span>
  <span m="3099210">the</span> <span m="3099360">estimates.</span> <span m="3099610">You</span>
  <span m="3099940">can</span> <span m="3100270">do</span> <span m="3100340">bootstrapping,</span>
  <span m="3101550">and</span> <span m="3101660">in</span> <span m="3101750">this</span>
  <span m="3101880">case</span> <span m="3102120">you</span> <span m="3102185">would</span>
  <span m="3102250">be</span> <span m="3104630">able</span> <span m="3104850">to</span>
  <span m="3105040">estimate</span> <span m="3105430">everything.</span> <span m="3106740">Yes.</span></p><p><span
  m="3113760">So</span> <span m="3114570">one</span> <span m="3114910">simple</span>
  <span m="3115320">approach</span> <span m="3116170">is</span> <span m="3116630">just</span>
  <span m="3116890">to</span> <span m="3116980">scale.</span> <span m="3117660">So</span>
  <span m="3117960">we're</span> <span m="3118120">talking</span> <span m="3118310">about</span>
  <span m="3118500">picking</span> <span m="3118860">w.</span> <span m="3120800">And</span>
  <span m="3122980">thank</span> <span m="3123170">you.</span> <span m="3124230">These</span>
  <span m="3124400">are</span> <span m="3124840">homeworks</span> <span m="3126180">7.</span>
  <span m="3127030">Thank</span> <span m="3127490">you.</span> <span m="3130710">And</span>
  <span m="3130940">it's</span> <span m="3131180">scaled</span> <span m="3131810">in</span>
  <span m="3131950">such</span> <span m="3132200">a</span> <span m="3132260">way</span>
  <span m="3132540">that</span> <span m="3132780">we</span> <span m="3134410">shift</span>
  <span m="3134910">probability</span> <span m="3135810">into</span> <span m="3136050">the</span>
  <span m="3136130">region</span> <span m="3136360">of</span> <span m="3136420">interest,</span>
  <span m="3138120">shift</span> <span m="3138410">probability</span> <span m="3142390">into</span>
  <span m="3142700">the</span> <span m="3142800">event</span> <span m="3143190">regions.</span>
  <span m="3144570">Again,</span> <span m="3144870">the</span> <span m="3144940">idea</span>
  <span m="3145290">being</span> <span m="3145570">that</span> <span m="3145710">we</span>
  <span m="3145800">want</span> <span m="3145980">to</span> <span m="3146050">get</span>
  <span m="3146500">more</span> <span m="3146990">samples.</span></p><p><span m="3149960">So</span>
  <span m="3149980">how</span> <span m="3150200">would</span> <span m="3150330">that</span>
  <span m="3150530">work?</span> <span m="3150730">In</span> <span m="3150885">that</span>
  <span m="3151040">case,</span> <span m="3152510">w</span> <span m="3152850">of</span>
  <span m="3153190">x</span> <span m="3153530">could</span> <span m="3153830">be</span>
  <span m="3155290">some</span> <span m="3155560">1</span> <span m="3155830">over</span>
  <span m="3156100">a</span> <span m="3157500">times</span> <span m="3158070">the</span>
  <span m="3158240">original</span> <span m="3161265">pdf.</span> <span m="3163110">But</span>
  <span m="3163250">now</span> <span m="3163470">the</span> <span m="3163540">function</span>
  <span m="3163880">of</span> <span m="3164030">x</span> <span m="3164437">over</span>
  <span m="3164844">a,</span> <span m="3165251">where</span> <span m="3165660">a</span>
  <span m="3166430">is</span> <span m="3166640">some</span> <span m="3168110">constant</span>
  <span m="3168920">that's</span> <span m="3169160">greater</span> <span m="3169410">than</span>
  <span m="3169570">1.</span> <span m="3171518">So</span> <span m="3172980">I</span>
  <span m="3173110">have</span> <span m="3173270">to</span> <span m="3173350">draw</span>
  <span m="3173610">these</span> <span m="3173880">for</span> <span m="3173980">them</span>
  <span m="3174200">to</span> <span m="3174310">make</span> <span m="3174510">sense</span>
  <span m="3176990">to</span> <span m="3177130">me.</span> <span m="3177660">So</span>
  <span m="3177770">it's</span> <span m="3177880">saying</span> <span m="3178370">pick</span>
  <span m="3178560">w</span> <span m="3180040">to</span> <span m="3180180">be</span>
  <span m="3180400">the</span> <span m="3180850">scaled</span> <span m="3181290">version</span>
  <span m="3181730">of</span> <span m="3182170">f</span> <span m="3182610">of</span>
  <span m="3182870">x</span> <span m="3184120">where</span> <span m="3184270">we</span>
  <span m="3184380">scale</span> <span m="3184760">the</span> <span m="3184850">argument</span>
  <span m="3187080">and</span> <span m="3187300">then</span> <span m="3187370">also</span>
  <span m="3187600">scale</span> <span m="3190440">the</span> <span m="3190560">result.</span></p><p><span
  m="3191994">So</span> <span m="3192416">if</span> <span m="3192838">I</span> <span
  m="3193260">can</span> <span m="3193340">just</span> <span m="3193420">sort</span>
  <span m="3193640">of</span> <span m="3193930">sketch</span> <span m="3194270">emotionally</span>
  <span m="3194900">what</span> <span m="3195080">that</span> <span m="3195210">might</span>
  <span m="3195430">look</span> <span m="3195620">like,</span> <span m="3195840">I</span>
  <span m="3195970">know</span> <span m="3196100">it</span> <span m="3196230">helps</span>
  <span m="3196360">me</span> <span m="3196570">to</span> <span m="3196650">think</span>
  <span m="3196910">about</span> <span m="3198350">what</span> <span m="3198550">it's</span>
  <span m="3198770">doing.</span> <span m="3199750">So</span> <span m="3199850">let's</span>
  <span m="3200100">say</span> <span m="3200320">x</span> <span m="3201820">and</span>
  <span m="3201960">this</span> <span m="3202090">is</span> <span m="3202230">the</span>
  <span m="3202380">f</span> <span m="3202770">of</span> <span m="3202940">x,</span>
  <span m="3203960">the</span> <span m="3204140">original</span> <span m="3204480">pdf.</span>
  <span m="3205060">So</span> <span m="3205340">maybe</span> <span m="3207200">it's</span>
  <span m="3207360">Gaussian.</span> <span m="3208790">And</span> <span m="3208930">just</span>
  <span m="3209070">to</span> <span m="3209150">make</span> <span m="3209350">it</span>
  <span m="3209420">easier</span> <span m="3209750">to</span> <span m="3209860">think</span>
  <span m="3210140">about,</span> <span m="3210360">let's</span> <span m="3210520">just</span>
  <span m="3210580">set</span> <span m="3210960">it</span> <span m="3211160">at</span>
  <span m="3211390">0.</span> <span m="3211615">It</span> <span m="3211840">doesn't</span>
  <span m="3212070">have</span> <span m="3212210">to</span> <span m="3212320">be.</span>
  <span m="3213476">And</span> <span m="3213870">it's</span> <span m="3214020">high,</span>
  <span m="3214280">which</span> <span m="3214380">is</span> <span m="3214510">going</span>
  <span m="3214640">to</span> <span m="3214710">be</span> <span m="3215130">something.</span>
  <span m="3215470">We'll</span> <span m="3215810">call</span> <span m="3216048">it</span>
  <span m="3216286">q.</span></p><p><span m="3218670">Then</span> <span m="3226470">what</span>
  <span m="3226660">is</span> <span m="3226790">w?</span> <span m="3227285">Does</span>
  <span m="3227780">anyone</span> <span m="3227945">want</span> <span m="3228110">to</span>
  <span m="3228275">have</span> <span m="3228522">a</span> <span m="3228604">go</span>
  <span m="3228687">at</span> <span m="3228707">[? throwing ?]</span> <span m="3228728">w?</span>
  <span m="3231740">So</span> <span m="3236690">the</span> <span m="3236800">height</span>
  <span m="3237266">is</span> <span m="3237732">q</span> <span m="3237887">over</span>
  <span m="3238042">a.</span> <span m="3238664">OK,</span> <span m="3239130">good.</span>
  <span m="3239600">Am</span> <span m="3239715">I</span> <span m="3239830">going</span>
  <span m="3239905">to</span> <span m="3239980">choose</span> <span m="3240065">a</span>
  <span m="3240150">greater</span> <span m="3240400">than</span> <span m="3240540">1?</span>
  <span m="3241486">So</span> <span m="3241960">it's</span> <span m="3242060">going</span>
  <span m="3242200">to</span> <span m="3242280">be</span> <span m="3243250">lower.</span></p><p><span
  m="3247250">AUDIENCE:</span> <span m="3247750">[INAUDIBLE].</span></p><p><span m="3254750">KAREN
  WILLCOX:</span> <span m="3255250">Good.</span> <span m="3256660">You're</span> <span
  m="3256940">much</span> <span m="3257220">better</span> <span m="3257375">at</span>
  <span m="3257530">visualizing</span> <span m="3257655">this</span> <span m="3257780">than</span>
  <span m="3258150">I</span> <span m="3258300">am.</span> <span m="3258360">I</span>
  <span m="3258716">had</span> <span m="3259072">to</span> <span m="3259430">mentally</span>
  <span m="3259740">do</span> <span m="3259840">a</span> <span m="3260170">few</span>
  <span m="3260603">points</span> <span m="3260819">because</span> <span m="3261036">I'm</span>
  <span m="3261470">not</span> <span m="3261650">very</span> <span m="3261870">good.</span>
  <span m="3262090">It's</span> <span m="3262200">not</span> <span m="3262330">a</span>
  <span m="3262370">very</span> <span m="3262610">good</span> <span m="3262880">fit</span>
  <span m="3265225">Gaussian.</span></p><p><span m="3267570">All</span> <span m="3268039">right.</span>
  <span m="3269450">So</span> <span m="3269650">I</span> <span m="3270020">had</span>
  <span m="3270390">to</span> <span m="3270590">actually</span> <span m="3270850">sort</span>
  <span m="3270940">of</span> <span m="3271000">mentally</span> <span m="3271410">thinking</span>
  <span m="3271770">it</span> <span m="3271870">through.</span> <span m="3271970">I'm</span>
  <span m="3272130">like</span> <span m="3272180">at</span> <span m="3272230">this</span>
  <span m="3272450">point,</span> <span m="3272610">we're</span> <span m="3272770">at</span>
  <span m="3272930">1</span> <span m="3274280">and</span> <span m="3274510">say</span>
  <span m="3274980">a</span> <span m="3275160">were</span> <span m="3275310">2,</span>
  <span m="3276560">then</span> <span m="3279590">this</span> <span m="3279910">guy</span>
  <span m="3280070">at</span> <span m="3280230">1</span> <span m="3280690">is</span>
  <span m="3280850">going</span> <span m="3281220">to</span> <span m="3281350">get</span>
  <span m="3281740">the</span> <span m="3281820">mass</span> <span m="3282530">from</span>
  <span m="3283190">1/2.</span> <span m="3285110">Then</span> <span m="3285200">it's</span>
  <span m="3285330">going</span> <span m="3285460">to</span> <span m="3285540">scale</span>
  <span m="3285705">it</span> <span m="3285870">down</span> <span m="3286120">by</span>
  <span m="3286250">two.</span> <span m="3286600">But</span> <span m="3286860">because</span>
  <span m="3287170">this</span> <span m="3287330">thing</span> <span m="3287450">is</span>
  <span m="3287570">falling</span> <span m="3287840">off</span> <span m="3287960">quickly,</span>
  <span m="3289230">it's</span> <span m="3289360">still</span> <span m="3289540">going</span>
  <span m="3289660">to</span> <span m="3289720">end</span> <span m="3289990">up</span>
  <span m="3290500">being</span> <span m="3290780">set</span> <span m="3291450">or</span>
  <span m="3291840">relative</span> <span m="3292400">to</span> <span m="3292620">what</span>
  <span m="3292760">was</span> <span m="3292890">in</span> <span m="3292980">the</span>
  <span m="3293050">middle.</span></p><p><span m="3294190">So</span> <span m="3294260">it's</span>
  <span m="3294330">exactly</span> <span m="3294575">a</span> <span m="3294820">scaling</span>
  <span m="3295190">that's</span> <span m="3295400">going</span> <span m="3297090">to</span>
  <span m="3297240">shift</span> <span m="3299500">probability</span> <span m="3300090">mass</span>
  <span m="3300390">out.</span> <span m="3302410">So</span> <span m="3303020">this</span>
  <span m="3303200">is</span> <span m="3303270">what</span> <span m="3303400">I</span>
  <span m="3303700">was</span> <span m="3303775">saying</span> <span m="3303850">when</span>
  <span m="3303940">I</span> <span m="3303970">meant</span> <span m="3304170">[? heads
  ?]</span> <span m="3304562">or</span> <span m="3304954">tails.</span> <span m="3305740">Any</span>
  <span m="3306510">problems</span> <span m="3306850">you</span> <span m="3307020">see</span>
  <span m="3307260">with</span> <span m="3307460">this</span> <span m="3307670">if</span>
  <span m="3307760">we're</span> <span m="3307870">trying</span> <span m="3308020">to</span>
  <span m="3308110">estimate</span> <span m="3308590">a</span> <span m="3308990">probability</span>
  <span m="3309510">of</span> <span m="3309640">failure,</span> <span m="3310040">say</span>
  <span m="3310170">the</span> <span m="3310240">probability</span> <span m="3310870">that</span>
  <span m="3311120">x</span> <span m="3311430">is</span> <span m="3311920">greater</span>
  <span m="3312170">than</span> <span m="3312350">some</span> <span m="3312710">critical</span>
  <span m="3313020">value?</span> <span m="3320460">What's</span> <span m="3320630">that?</span></p><p><span
  m="3320890">AUDIENCE:</span> <span m="3321240">[INAUDIBLE].</span></p><p><span m="3321590">KAREN
  WILLCOX:</span> <span m="3321940">Yeah,</span> <span m="3322035">it</span> <span
  m="3322130">might</span> <span m="3322300">not</span> <span m="3322440">still</span>
  <span m="3322600">be.</span> <span m="3322770">Anyway</span> <span m="3323100">it's</span>
  <span m="3323235">definitely</span> <span m="3323370">going</span> <span m="3323490">to</span>
  <span m="3323550">generate</span> <span m="3323880">more</span> <span m="3324040">samples</span>
  <span m="3324430">over</span> <span m="3324580">here,</span> <span m="3325110">but</span>
  <span m="3325470">it's</span> <span m="3325595">also</span> <span m="3325720">going</span>
  <span m="3325940">to</span> <span m="3326010">generate</span> <span m="3326430">more</span>
  <span m="3326570">samples</span> <span m="3327020">over</span> <span m="3327470">here.</span>
  <span m="3328370">So</span> <span m="3329720">we've</span> <span m="3330060">made</span>
  <span m="3330360">this</span> <span m="3330460">tail</span> <span m="3330900">fatter,</span>
  <span m="3331450">but</span> <span m="3331600">we've</span> <span m="3331790">also</span>
  <span m="3332360">made</span> <span m="3332740">this</span> <span m="3332900">tail</span>
  <span m="3333394">fatter.</span> <span m="3334876">So</span></p><p><span m="3338828">AUDIENCE:</span>
  <span m="3339322">[INAUDIBLE]?</span></p><p><span m="3343274">KAREN WILLCOX:</span>
  <span m="3343780">Can</span> <span m="3343950">you</span> <span m="3344327">do</span>
  <span m="3344704">one</span> <span m="3345081">if</span> <span m="3345156">f</span>
  <span m="3345232">of</span> <span m="3345308">x</span> <span m="3345384">is</span>
  <span m="3345460">uniform?</span> <span m="3346930">I</span> <span m="3347420">think</span>
  <span m="3347910">about</span> <span m="3348100">what</span> <span m="3350200">w</span>
  <span m="3350340">would</span> <span m="3350520">be.</span> <span m="3355100">But</span>
  <span m="3355240">basically</span> <span m="3355330">w</span> <span m="3355800">can</span>
  <span m="3355910">be</span> <span m="3356020">anything</span> <span m="3356460">you</span>
  <span m="3356600">want.</span></p><p><span m="3357061">AUDIENCE:</span> <span m="3357522">[INAUDIBLE].</span></p><p><span
  m="3360288">KAREN WILLCOX:</span> <span m="3360750">Yeah,</span> <span m="3361620">that's</span>
  <span m="3361705">just</span> <span m="3361790">one</span> <span m="3362140">way</span>
  <span m="3362380">to</span> <span m="3362490">do</span> <span m="3362710">it.</span>
  <span m="3365870">But</span> <span m="3366070">you've</span> <span m="3369720">got</span>
  <span m="3370220">to</span> <span m="3370290">make</span> <span m="3370490">sure</span>
  <span m="3370720">that</span> <span m="3372360">the</span> <span m="3372530">support</span>
  <span m="3372890">of</span> <span m="3372980">w</span> <span m="3373350">is</span>
  <span m="3373460">it</span> <span m="3373560">at</span> <span m="3373650">least</span>
  <span m="3373980">as</span> <span m="3374160">wide</span> <span m="3374880">[INAUDIBLE]</span>
  <span m="3375140">actually</span> <span m="3376090">going</span> <span m="3376210">to</span>
  <span m="3376290">be</span> <span m="3376590">dividing</span> <span m="3377090">by</span>
  <span m="3377340">0.</span> <span m="3379090">So</span> <span m="3379940">if</span>
  <span m="3380090">this</span> <span m="3380190">guy</span> <span m="3380480">was</span>
  <span m="3380590">uniform,</span> <span m="3382560">I</span> <span m="3382670">mean--</span></p><p><span
  m="3383070">AUDIENCE:</span> <span m="3383545">[INAUDIBLE].</span></p><p><span m="3388295">KAREN
  WILLCOX:</span> <span m="3388770">That's</span> <span m="3388950">right.</span>
  <span m="3391020">But</span> <span m="3391210">you</span> <span m="3391380">couldn't</span>
  <span m="3391910">have</span> <span m="3392600">this</span> <span m="3392890">be</span>
  <span m="3393070">uniform</span> <span m="3393610">and</span> <span m="3393700">then</span>
  <span m="3393910">say,</span> <span m="3394130">I'm</span> <span m="3394270">going</span>
  <span m="3394400">to</span> <span m="3394460">take</span> <span m="3394780">my</span>
  <span m="3394900">w</span> <span m="3395440">to</span> <span m="3395540">be</span>
  <span m="3396305">this</span> <span m="3396680">guy.</span> <span m="3399010">Well,</span>
  <span m="3399936">what's</span> <span m="3400400">generating</span> <span m="3400790">from</span>
  <span m="3400970">here</span> <span m="3401220">would</span> <span m="3401380">you--</span>
  <span m="3403970">you</span> <span m="3404190">would</span> <span m="3404330">be</span>
  <span m="3404460">OK</span> <span m="3404700">because</span> <span m="3404850">you</span>
  <span m="3404930">never</span> <span m="3405140">generate</span> <span m="3405470">points</span>
  <span m="3405750">here.</span> <span m="3409173">Yeah.</span></p><p><span m="3409662">AUDIENCE:</span>
  <span m="3410151">[INAUDIBLE].</span></p><p><span m="3415530">KAREN WILLCOX:</span>
  <span m="3416020">You</span> <span m="3416140">could</span> <span m="3416330">but</span>
  <span m="3416490">then</span> <span m="3417180">they</span> <span m="3417300">would</span>
  <span m="3417440">just</span> <span m="3417660">get</span> <span m="3417860">multiplied</span>
  <span m="3418050">by</span> <span m="3418480">0.</span> <span m="3420200">Then</span>
  <span m="3420340">you'd</span> <span m="3420480">be</span> <span m="3420580">wasting</span>
  <span m="3421072">[? holds. ?]</span> <span m="3422550">Yes,</span> <span m="3422780">I</span>
  <span m="3422860">guess</span> <span m="3423110">there's</span> <span m="3423340">no</span>
  <span m="3423460">reason</span> <span m="3423670">why</span> <span m="3423740">you</span>
  <span m="3423810">couldn't</span> <span m="3424275">do</span> <span m="3424740">this.</span>
  <span m="3425688">Yeah.</span> <span m="3426636">So</span> <span m="3427110">that's</span>
  <span m="3427420">one</span> <span m="3427600">simple</span> <span m="3427830">thing</span>
  <span m="3427990">to</span> <span m="3428060">do</span> <span m="3428220">is</span>
  <span m="3428330">just</span> <span m="3428550">to</span> <span m="3429210">move</span>
  <span m="3429520">mass</span> <span m="3429940">out,</span> <span m="3430340">maybe</span>
  <span m="3430600">[? theta ?]</span> <span m="3430760">tails.</span></p><p><span
  m="3431390">Another</span> <span m="3431750">simple</span> <span m="3432220">thing</span>
  <span m="3432390">you</span> <span m="3432500">could</span> <span m="3432660">do</span>
  <span m="3432790">is</span> <span m="3432850">translation,</span> <span m="3437170">which</span>
  <span m="3437510">just</span> <span m="3437740">means</span> <span m="3438140">that</span>
  <span m="3438340">w</span> <span m="3438796">of</span> <span m="3439710">x</span>
  <span m="3440920">would</span> <span m="3441160">be</span> <span m="3441420">f</span>
  <span m="3441550">of</span> <span m="3441745">x</span> <span m="3441940">minus</span>
  <span m="3442360">c,</span> <span m="3444010">where</span> <span m="3444760">maybe</span>
  <span m="3445030">c</span> <span m="3445300">is</span> <span m="3445490">greater</span>
  <span m="3445740">than</span> <span m="3445920">0</span> <span m="3446410">if</span>
  <span m="3446600">we're</span> <span m="3446770">thinking</span> <span m="3447100">about</span>
  <span m="3448720">a</span> <span m="3449170">right</span> <span m="3449520">tail.</span>
  <span m="3452170">And</span> <span m="3452330">again,</span> <span m="3452620">maybe</span>
  <span m="3452800">this</span> <span m="3452960">wouldn't</span> <span m="3453100">make</span>
  <span m="3453330">sense</span> <span m="3453630">if</span> <span m="3453750">you</span>
  <span m="3453890">had</span> <span m="3454090">a</span> <span m="3454130">finite</span>
  <span m="3454550">support</span> <span m="3454930">like</span> <span m="3455015">a</span>
  <span m="3455100">uniform</span> <span m="3455450">distribution</span> <span m="3455730">because</span>
  <span m="3456010">then</span> <span m="3456080">you</span> <span m="3456390">would</span>
  <span m="3456520">be</span> <span m="3456600">putting</span> <span m="3456880">w,</span>
  <span m="3457740">which</span> <span m="3457940">you</span> <span m="3458020">didn't</span>
  <span m="3458710">care</span> <span m="3458900">about.</span> <span m="3459220">But</span>
  <span m="3459710">what</span> <span m="3459808">would</span> <span m="3459906">that</span>
  <span m="3460004">look</span> <span m="3460102">like</span> <span m="3460200">notionally?</span>
  <span m="3461060">If</span> <span m="3461450">that's</span> <span m="3461790">x</span>
  <span m="3462150">and</span> <span m="3462240">that's</span> <span m="3462520">f</span>
  <span m="3462710">of</span> <span m="3462840">x,</span> <span m="3463932">we</span>
  <span m="3464360">get</span> <span m="3464630">a</span> <span m="3464730">first</span>
  <span m="3464980">term</span> <span m="3465390">normal</span> <span m="3467450">[INAUDIBLE]</span>
  <span m="3468380">0,</span> <span m="3469760">then</span> <span m="3470060">the</span>
  <span m="3470120">w</span> <span m="3470273">of</span> <span m="3470426">x</span>
  <span m="3472410">is</span> <span m="3472580">just</span> <span m="3472750">going</span>
  <span m="3472880">to</span> <span m="3472960">be</span> <span m="3474750">shifted</span>
  <span m="3475130">over</span> <span m="3475340">by</span> <span m="3475490">an</span>
  <span m="3475570">amount,</span> <span m="3476025">c.</span> <span m="3479670">So</span>
  <span m="3479820">again,</span> <span m="3480490">all</span> <span m="3480650">it's</span>
  <span m="3480780">doing</span> <span m="3481110">is</span> <span m="3481370">putting</span>
  <span m="3481720">more</span> <span m="3482030">probability</span> <span m="3482550">mass</span>
  <span m="3483340">in</span> <span m="3483510">this</span> <span m="3483680">case</span>
  <span m="3484350">in</span> <span m="3484480">the</span> <span m="3484570">right</span>
  <span m="3484760">tail</span> <span m="3485010">that</span> <span m="3485900">we</span>
  <span m="3485980">care</span> <span m="3486190">about.</span></p><p><span m="3494620">But</span>
  <span m="3494970">thinking</span> <span m="3495230">of</span> <span m="3495340">biasing</span>
  <span m="3495460">distribution,</span> <span m="3496550">the</span> <span m="3496680">simple</span>
  <span m="3496990">problems,</span> <span m="3498250">simple</span> <span m="3498500">things</span>
  <span m="3498730">probably</span> <span m="3498930">work</span> <span m="3499300">for</span>
  <span m="3499760">really</span> <span m="3500020">difficult</span> <span m="3500430">problems</span>
  <span m="3501060">with</span> <span m="3501210">lots</span> <span m="3501440">of</span>
  <span m="3501520">input</span> <span m="3502780">in</span> <span m="3503250">very</span>
  <span m="3503570">rare events,</span> <span m="3504630">differently,</span> <span
  m="3505030">still</span> <span m="3505430">an</span> <span m="3506300">open</span>
  <span m="3506420">question.</span> <span m="3513310">Any</span> <span m="3513440">other</span>
  <span m="3513590">questions</span> <span m="3514150">about</span> <span m="3514460">importance</span>
  <span m="3514870">sampling.</span> <span m="3515210">We</span> <span m="3515370">sometimes</span>
  <span m="3515690">talk</span> <span m="3515870">about</span> <span m="3515975">distributing</span>
  <span m="3516080">analysis?</span> <span m="3519174">Does</span> <span m="3519620">it</span>
  <span m="3519840">all</span> <span m="3520330">makes</span> <span m="3520570">sense</span>
  <span m="3522205">that's</span> <span m="3522670">on</span> <span m="3522940">this</span>
  <span m="3523050">screen?</span> <span m="3526770">Yes.</span></p><p><span m="3526930">AUDIENCE:</span>
  <span m="3527376">[INAUDIBLE].</span></p><p><span m="3530760">KAREN WILLCOX:</span>
  <span m="3530930">Actually</span> <span m="3531410">control</span> <span m="3531770">variance</span>
  <span m="3531950">are</span> <span m="3532200">my</span> <span m="3532400">favorites.</span>
  <span m="3533350">I've</span> <span m="3533550">mentioned</span> <span m="3533950">some</span>
  <span m="3534100">of</span> <span m="3534190">the</span> <span m="3534330">other</span>
  <span m="3535510">variance</span> <span m="3535940">reduction</span> <span m="3536420">methods.</span>
  <span m="3536970">Control</span> <span m="3537250">variance</span> <span m="3537700">is</span>
  <span m="3538040">another</span> <span m="3538400">way</span> <span m="3538890">to</span>
  <span m="3538970">do</span> <span m="3539110">variance</span> <span m="3539330">reduction</span>
  <span m="3540920">that</span> <span m="3541090">I</span> <span m="3541150">think</span>
  <span m="3541350">is</span> <span m="3541500">also</span> <span m="3541710">a</span>
  <span m="3541740">kind</span> <span m="3541930">of</span> <span m="3542010">neat.</span>
  <span m="3542862">So</span> <span m="3543290">if</span> <span m="3543440">you're</span>
  <span m="3543680">interested</span> <span m="3544070">in</span> <span m="3544170">knowing</span>
  <span m="3544510">other</span> <span m="3544730">variance</span> <span m="3545050">reduction</span>
  <span m="3545370">methods,</span> <span m="3545760">I</span> <span m="3545830">could</span>
  <span m="3546660">give</span> <span m="3546800">you</span> <span m="3546880">some</span>
  <span m="3547060">stuff</span> <span m="3547310">to</span> <span m="3547450">read.</span></p><p><span
  m="3550510">So</span> <span m="3551300">let's</span> <span m="3551550">now</span>
  <span m="3551990">just</span> <span m="3552135">in</span> <span m="3552280">the</span>
  <span m="3552350">last</span> <span m="3555120">15</span> <span m="3555470">minutes</span>
  <span m="3555880">talk</span> <span m="3556090">a</span> <span m="3556130">little</span>
  <span m="3556300">bit</span> <span m="3556410">about</span> <span m="3556680">sensitivity</span>
  <span m="3557210">analysis</span> <span m="3558604">in</span> <span m="3558981">the</span>
  <span m="3559360">context</span> <span m="3559370">of</span> <span m="3559440">Monte</span>
  <span m="3559730">Carlos.</span> <span m="3562652">So</span> <span m="3564600">the</span>
  <span m="3564700">question</span> <span m="3565250">is</span> <span m="3565620">now</span>
  <span m="3566010">how</span> <span m="3566190">do</span> <span m="3566300">we</span>
  <span m="3566480">use</span> <span m="3566730">our</span> <span m="3566840">Monte</span>
  <span m="3567090">Carlo</span> <span m="3567460">results</span> <span m="3568820">to</span>
  <span m="3568980">understand</span> <span m="3570280">which</span> <span m="3570630">uncertain</span>
  <span m="3571130">inputs</span> <span m="3571385">are</span> <span m="3571640">contributing</span>
  <span m="3572220">the</span> <span m="3572290">most</span> <span m="3572780">to</span>
  <span m="3573160">output</span> <span m="3573560">variability.</span> <span m="3573760">So</span>
  <span m="3573960">I</span> <span m="3574050">want</span> <span m="3574230">you</span>
  <span m="3574290">to</span> <span m="3574400">put</span> <span m="3575190">this</span>
  <span m="3575520">picture</span> <span m="3575840">back</span> <span m="3576060">in</span>
  <span m="3576150">your</span> <span m="3576270">mind,</span> <span m="3577840">this</span>
  <span m="3577940">guy</span> <span m="3578230">here,</span> <span m="3578630">which</span>
  <span m="3578870">is</span> <span m="3579030">that</span> <span m="3581990">we've</span>
  <span m="3582260">got</span> <span m="3583200">uncertain</span> <span m="3583740">inputs,</span>
  <span m="3584390">and</span> <span m="3584850">maybe</span> <span m="3585220">there's</span>
  <span m="3585390">a</span> <span m="3585440">lot</span> <span m="3585640">of</span>
  <span m="3585730">them--</span> <span m="3586090">d1,</span> <span m="3586930">d2,</span>
  <span m="3587630">d3,</span> <span m="3588600">however</span> <span m="3588890">many.</span></p><p><span
  m="3590940">And</span> <span m="3592470">maybe</span> <span m="3592720">there's</span>
  <span m="3592900">one</span> <span m="3593110">output</span> <span m="3593400">of</span>
  <span m="3593480">interest,</span> <span m="3593790">or</span> <span m="3593830">maybe</span>
  <span m="3593990">there</span> <span m="3594050">is</span> <span m="3594220">lots.</span>
  <span m="3595015">But</span> <span m="3595450">we've</span> <span m="3595510">run</span>
  <span m="3595695">these</span> <span m="3595880">Monte</span> <span m="3596120">Carlos,</span>
  <span m="3597830">we</span> <span m="3597970">put</span> <span m="3598380">pdf's</span>
  <span m="3599200">in</span> <span m="3599320">all</span> <span m="3599410">these</span>
  <span m="3599760">guys.</span> <span m="3601350">We</span> <span m="3601490">draw</span>
  <span m="3601690">samples.</span> <span m="3602280">We</span> <span m="3602370">run</span>
  <span m="3602590">through.</span> <span m="3603090">We</span> <span m="3603220">generate</span>
  <span m="3605230">some</span> <span m="3605420">kind</span> <span m="3605590">of</span>
  <span m="3605700">output</span> <span m="3606140">histogram</span> <span m="3608160">on</span>
  <span m="3608350">q</span> <span m="3608700">that</span> <span m="3608880">looks</span>
  <span m="3609110">like</span> <span m="3609330">however</span> <span m="3609775">it</span>
  <span m="3610220">looks.</span></p><p><span m="3612890">But</span> <span m="3613020">now</span>
  <span m="3613170">we</span> <span m="3613270">want</span> <span m="3613390">to</span>
  <span m="3613460">ask</span> <span m="3613670">the</span> <span m="3613760">question,</span>
  <span m="3614310">well,</span> <span m="3615100">which</span> <span m="3615230">one</span>
  <span m="3615440">of</span> <span m="3615570">these</span> <span m="3616565">is</span>
  <span m="3617050">really</span> <span m="3617480">contributing</span> <span m="3618050">to</span>
  <span m="3618130">the</span> <span m="3618200">variability,</span> <span m="3620840">or</span>
  <span m="3621220">which</span> <span m="3621720">combinations</span> <span m="3622520">of</span>
  <span m="3622660">these</span> <span m="3623050">are</span> <span m="3623170">contributing</span>
  <span m="3623720">to</span> <span m="3623920">the</span> <span m="3624120">variability?</span>
  <span m="3624680">Which</span> <span m="3624930">combinations</span> <span m="3625660">are</span>
  <span m="3625740">causing</span> <span m="3626850">this</span> <span m="3627050">big</span>
  <span m="3627320">fat</span> <span m="3627540">tail</span> <span m="3627850">out</span>
  <span m="3628010">here,</span> <span m="3628310">which</span> <span m="3628520">corresponds</span>
  <span m="3629090">to</span> <span m="3629200">[INAUDIBLE]</span> <span m="3629550">that</span>
  <span m="3629630">don't</span> <span m="3629910">meet</span> <span m="3630190">our</span>
  <span m="3630460">design</span> <span m="3630780">criteria?</span></p><p><span m="3632136">So</span>
  <span m="3632590">this</span> <span m="3633050">is</span> <span m="3633160">really</span>
  <span m="3633390">now</span> <span m="3634010">kind</span> <span m="3634230">of</span>
  <span m="3634360">the</span> <span m="3634450">opposite</span> <span m="3634850">question.</span>
  <span m="3635610">You've</span> <span m="3635630">done</span> <span m="3635890">a</span>
  <span m="3635960">forward</span> <span m="3636200">propagation</span> <span m="3636720">of</span>
  <span m="3636790">uncertainty,</span> <span m="3637490">and</span> <span m="3637600">you've</span>
  <span m="3637720">got</span> <span m="3637890">the</span> <span m="3637980">uncertainty</span>
  <span m="3638395">in</span> <span m="3638810">q,</span> <span m="3639225">and</span>
  <span m="3639640">now</span> <span m="3639870">you</span> <span m="3640010">want</span>
  <span m="3640150">to</span> <span m="3640210">figure</span> <span m="3640440">out</span>
  <span m="3640610">where</span> <span m="3640860">did</span> <span m="3640900">it</span>
  <span m="3640940">come</span> <span m="3641090">from.</span> <span m="3642830">So</span>
  <span m="3643130">forward</span> <span m="3643360">propagation</span> <span m="3643860">of</span>
  <span m="3643950">uncertainty,</span> <span m="3644790">sensitivity</span> <span
  m="3645390">analysis</span> <span m="3645890">is</span> <span m="3646060">kind</span>
  <span m="3646210">of</span> <span m="3646270">like</span> <span m="3646470">the</span>
  <span m="3646755">reverse</span> <span m="3647560">question.</span> <span m="3649150">And</span>
  <span m="3649470">it's</span> <span m="3649590">important</span> <span m="3649920">for</span>
  <span m="3650040">two</span> <span m="3650270">reasons,</span> <span m="3650940">one</span>
  <span m="3651110">is</span> <span m="3651340">that</span> <span m="3652780">it</span>
  <span m="3652960">helps</span> <span m="3653190">us</span> <span m="3653320">understand</span>
  <span m="3654050">where</span> <span m="3654260">we</span> <span m="3654370">should</span>
  <span m="3654570">focus</span> <span m="3655280">our</span> <span m="3655450">uncertainty</span>
  <span m="3655940">reduction</span> <span m="3656370">efforts.</span></p><p><span
  m="3657670">But</span> <span m="3657790">I</span> <span m="3657820">think</span>
  <span m="3657980">in</span> <span m="3658080">many</span> <span m="3658320">ways</span>
  <span m="3658720">when</span> <span m="3658800">you</span> <span m="3659000">look</span>
  <span m="3659220">say</span> <span m="3659730">like</span> <span m="3659940">an</span>
  <span m="3660020">aircraft</span> <span m="3660420">design</span> <span m="3660760">and</span>
  <span m="3660880">development</span> <span m="3661340">program</span> <span m="3661680">at</span>
  <span m="3661750">a</span> <span m="3661790">place</span> <span m="3662020">like</span>
  <span m="3662180">Boeing</span> <span m="3662580">or</span> <span m="3662650">wherever,</span>
  <span m="3664030">so</span> <span m="3664280">much</span> <span m="3664570">of</span>
  <span m="3664730">the</span> <span m="3664830">process</span> <span m="3665250">is</span>
  <span m="3665350">about</span> <span m="3665590">reducing</span> <span m="3665970">uncertainty.</span>
  <span m="3668250">It's</span> <span m="3668420">about</span> <span m="3668900">running</span>
  <span m="3669180">experiments</span> <span m="3670110">or</span> <span m="3670556">tests</span>
  <span m="3671450">or</span> <span m="3671710">running</span> <span m="3671960">models</span>
  <span m="3672320">and</span> <span m="3672420">trying</span> <span m="3672550">to</span>
  <span m="3672610">figure</span> <span m="3672970">out</span> <span m="3673200">exactly</span>
  <span m="3673520">what</span> <span m="3673880">the</span> <span m="3674080">performance</span>
  <span m="3674310">is</span> <span m="3674575">of</span> <span m="3674707">the</span>
  <span m="3674840">thing</span> <span m="3674980">that</span> <span m="3675090">you're</span>
  <span m="3675190">designing</span> <span m="3675620">and</span> <span m="3675710">making</span>
  <span m="3675940">decisions</span> <span m="3676420">as</span> <span m="3676530">well.</span></p><p><span
  m="3677660">So</span> <span m="3678170">understanding</span> <span m="3678970">where</span>
  <span m="3679300">this</span> <span m="3679940">big</span> <span m="3680120">uncertainty</span>
  <span m="3680850">can</span> <span m="3681060">help</span> <span m="3681470">you</span>
  <span m="3682370">decide</span> <span m="3682740">what</span> <span m="3682860">kind</span>
  <span m="3683010">of</span> <span m="3683110">experiments</span> <span m="3683600">to</span>
  <span m="3683680">do,</span> <span m="3684100">whether</span> <span m="3684126">it</span>
  <span m="3684153">will</span> <span m="3684180">improve</span> <span m="3684510">your</span>
  <span m="3684600">models,</span> <span m="3685690">if</span> <span m="3685860">you're</span>
  <span m="3685970">thinking</span> <span m="3686240">about</span> <span m="3686720">uncertainty</span>
  <span m="3687340">in</span> <span m="3687970">finished</span> <span m="3688210">products,</span>
  <span m="3688630">it</span> <span m="3688740">can</span> <span m="3688940">help</span>
  <span m="3689350">guide</span> <span m="3689630">you</span> <span m="3689740">one</span>
  <span m="3689930">where</span> <span m="3690220">you</span> <span m="3690320">should</span>
  <span m="3690880">tighten</span> <span m="3691170">tolerances</span> <span m="3691620">in</span>
  <span m="3691700">the</span> <span m="3691780">new</span> <span m="3691910">manufacturing</span>
  <span m="3692490">process.</span> <span m="3694440">It</span> <span m="3694500">might</span>
  <span m="3694700">tell</span> <span m="3694860">you</span> <span m="3695070">that</span>
  <span m="3695460">you've</span> <span m="3695580">got</span> <span m="3695700">uncertainty</span>
  <span m="3696280">because</span> <span m="3696530">you</span> <span m="3696610">don't</span>
  <span m="3696830">know</span> <span m="3696950">certain</span> <span m="3697260">conditions.</span>
  <span m="3697740">So</span> <span m="3697873">maybe</span> <span m="3698006">it</span>
  <span m="3698140">says</span> <span m="3698410">you</span> <span m="3698480">need</span>
  <span m="3698610">a</span> <span m="3698650">sensor</span> <span m="3699470">in</span>
  <span m="3699610">your</span> <span m="3699750">engine</span> <span m="3700210">or</span>
  <span m="3700530">on</span> <span m="3700925">board</span> <span m="3701122">your</span>
  <span m="3701320">aircraft</span> <span m="3701750">or</span> <span m="3701800">wherever.</span></p><p><span
  m="3702590">Sometimes</span> <span m="3702980">this</span> <span m="3703090">is</span>
  <span m="3703190">called</span> <span m="3703410">factor</span> <span m="3703820">prioritization,</span>
  <span m="3706100">figuring</span> <span m="3706570">out</span> <span m="3706780">what</span>
  <span m="3706920">the</span> <span m="3706990">priority</span> <span m="3707650">order</span>
  <span m="3708000">of</span> <span m="3708703">inputs.</span> <span m="3709410">Effect</span>
  <span m="3709850">is</span> <span m="3710700">just</span> <span m="3711080">a</span>
  <span m="3711140">term</span> <span m="3711410">that</span> <span m="3712440">is</span>
  <span m="3712560">often</span> <span m="3712760">used</span> <span m="3712900">in</span>
  <span m="3712970">the</span> <span m="3713050">statistics</span> <span m="3713500">community.</span>
  <span m="3714340">Which</span> <span m="3714560">one</span> <span m="3714740">should</span>
  <span m="3714920">be</span> <span m="3715040">priorities</span> <span m="3715750">for</span>
  <span m="3715910">uncertainty</span> <span m="3716340">reductions.</span></p><p><span
  m="3717656">So</span> <span m="3718060">it's</span> <span m="3718230">kind</span>
  <span m="3718360">of</span> <span m="3718460">half</span> <span m="3718740">a</span>
  <span m="3718810">story,</span> <span m="3719160">but</span> <span m="3719290">the</span>
  <span m="3719360">other</span> <span m="3719560">half</span> <span m="3719810">of</span>
  <span m="3719870">story</span> <span m="3720200">is</span> <span m="3720310">that</span>
  <span m="3720470">it's</span> <span m="3720610">also</span> <span m="3720900">really</span>
  <span m="3721080">important</span> <span m="3721580">to</span> <span m="3721710">understand</span>
  <span m="3722800">where</span> <span m="3722970">the</span> <span m="3723220">uncertainties</span>
  <span m="3723700">are</span> <span m="3723760">not</span> <span m="3724100">important.</span>
  <span m="3726540">That</span> <span m="3727500">they</span> <span m="3727640">could</span>
  <span m="3727950">be</span> <span m="3728580">distributions</span> <span m="3729410">on</span>
  <span m="3729630">d1,</span> <span m="3731200">but</span> <span m="3731320">this</span>
  <span m="3731510">doesn't</span> <span m="3731740">really</span> <span m="3731890">matter</span>
  <span m="3732150">because</span> <span m="3732950">this</span> <span m="3733090">thing</span>
  <span m="3733250">is</span> <span m="3733410">not</span> <span m="3733770">sensitive</span>
  <span m="3735280">to</span> <span m="3735430">d1.</span> <span m="3736780">And</span>
  <span m="3736880">that's</span> <span m="3737070">important</span> <span m="3737530">because</span>
  <span m="3737790">then</span> <span m="3737930">you</span> <span m="3738000">shouldn't</span>
  <span m="3738250">waste</span> <span m="3738510">your</span> <span m="3738610">time</span>
  <span m="3738970">worrying</span> <span m="3739330">about</span> <span m="3739630">d1,</span>
  <span m="3739780">and</span> <span m="3740250">you</span> <span m="3740595">shouldn't</span>
  <span m="3741170">waste</span> <span m="3741360">your</span> <span m="3741450">time</span>
  <span m="3741710">arguing</span> <span m="3742160">with</span> <span m="3742280">other</span>
  <span m="3742440">groups</span> <span m="3742850">about</span> <span m="3743290">whether</span>
  <span m="3743510">d1</span> <span m="3743930">should</span> <span m="3744110">be</span>
  <span m="3744330">1</span> <span m="3744660">or</span> <span m="3744730">1.1</span>
  <span m="3745510">or</span> <span m="3745640">1.2.</span></p><p><span m="3746060">So</span>
  <span m="3746170">it's</span> <span m="3746500">important</span> <span m="3746720">to</span>
  <span m="3746790">understand</span> <span m="3747910">where</span> <span m="3748100">things</span>
  <span m="3748400">are</span> <span m="3748840">actually</span> <span m="3749190">not</span>
  <span m="3750650">important.</span> <span m="3751710">And</span> <span m="3751800">this</span>
  <span m="3751910">is</span> <span m="3751980">sometimes</span> <span m="3752320">called</span>
  <span m="3752500">factor</span> <span m="3752770">fixing</span> <span m="3753450">because</span>
  <span m="3754320">this</span> <span m="3754500">is</span> <span m="3754620">where</span>
  <span m="3754840">you</span> <span m="3755040">can</span> <span m="3755210">understand</span>
  <span m="3755930">where</span> <span m="3756070">it's</span> <span m="3756340">not</span>
  <span m="3756750">important</span> <span m="3757160">to</span> <span m="3757230">consider</span>
  <span m="3757590">uncertainty,</span> <span m="3758150">and</span> <span m="3758260">you</span>
  <span m="3758330">can</span> <span m="3758440">just</span> <span m="3758610">pick</span>
  <span m="3758790">a</span> <span m="3758860">deterministic</span> <span m="3759570">value</span>
  <span m="3759970">of</span> <span m="3760630">an</span> <span m="3760790">input</span>
  <span m="3761210">and</span> <span m="3761630">go</span> <span m="3761770">forward.</span>
  <span m="3762470">And</span> <span m="3762560">this</span> <span m="3762700">is</span>
  <span m="3762810">really</span> <span m="3763000">important,</span> <span m="3763470">actually</span>
  <span m="3763650">in</span> <span m="3763770">the</span> <span m="3763840">policy</span>
  <span m="3764410">setting.</span></p><p><span m="3764820">As</span> <span m="3765230">I</span>
  <span m="3765290">mentioned</span> <span m="3765550">before,</span> <span m="3765950">you</span>
  <span m="3766083">can</span> <span m="3766216">work</span> <span m="3766350">with</span>
  <span m="3766530">FAA.</span> <span m="3768050">People</span> <span m="3768390">argue</span>
  <span m="3768620">about</span> <span m="3768730">all</span> <span m="3768990">kinds</span>
  <span m="3769200">of</span> <span m="3769270">things</span> <span m="3769530">when</span>
  <span m="3769650">they</span> <span m="3769730">make</span> <span m="3769920">policies.</span>
  <span m="3770840">It's</span> <span m="3771040">nice</span> <span m="3771310">to</span>
  <span m="3771380">be</span> <span m="3771450">able</span> <span m="3771580">to</span>
  <span m="3771670">show</span> <span m="3772010">that</span> <span m="3772290">some</span>
  <span m="3772430">of</span> <span m="3772500">the</span> <span m="3772570">things</span>
  <span m="3772990">that</span> <span m="3773150">you</span> <span m="3773340">argue</span>
  <span m="3773620">about</span> <span m="3774000">actually</span> <span m="3774280">don't</span>
  <span m="3774540">matter</span> <span m="3774900">for</span> <span m="3775070">the</span>
  <span m="3775210">uncertainty</span> <span m="3775890">in</span> <span m="3776060">the</span>
  <span m="3777000">policy</span> <span m="3777420">decision.</span> <span m="3779410">Less</span>
  <span m="3779530">things</span> <span m="3779710">to</span> <span m="3779890">argue</span>
  <span m="3780170">about.</span></p><p><span m="3780835">All</span> <span m="3781170">right.</span>
  <span m="3781480">So</span> <span m="3781700">how</span> <span m="3781820">can</span>
  <span m="3781940">we</span> <span m="3782020">do</span> <span m="3782210">sensitivity</span>
  <span m="3782730">analysis?</span> <span m="3784340">There</span> <span m="3784430">is</span>
  <span m="3784520">something</span> <span m="3784900">called</span> <span m="3785420">VABO,</span>
  <span m="3786320">vary-all-but-one</span> <span m="3787370">[INAUDIBLE].</span>
  <span m="3791730">Think</span> <span m="3792070">about</span> <span m="3792410">doing.</span>
  <span m="3793200">So</span> <span m="3793310">here</span> <span m="3793470">are</span>
  <span m="3793500">the</span> <span m="3793590">steps.</span> <span m="3794690">First</span>
  <span m="3794870">of</span> <span m="3794950">all</span> <span m="3795140">run</span>
  <span m="3795380">your</span> <span m="3795480">Monte</span> <span m="3795690">Caro</span>
  <span m="3796260">with</span> <span m="3796460">all</span> <span m="3796720">the</span>
  <span m="3796850">inputs</span> <span m="3797700">varying.</span> <span m="3800160">Think</span>
  <span m="3800350">about</span> <span m="3801750">d1,</span> <span m="3802430">d2,</span>
  <span m="3802960">d3,</span> <span m="3803500">up</span> <span m="3803640">to</span>
  <span m="3803750">however</span> <span m="3803900">many</span> <span m="3804160">we</span>
  <span m="3804270">have</span> <span m="3804460">of</span> <span m="3804530">them.</span></p><p><span
  m="3805400">We've</span> <span m="3805460">got</span> <span m="3805680">pdf's</span>
  <span m="3805980">for</span> <span m="3806200">all</span> <span m="3806380">of</span>
  <span m="3806440">them.</span> <span m="3806710">We</span> <span m="3806730">sample</span>
  <span m="3807110">all</span> <span m="3807380">of</span> <span m="3807450">them.</span>
  <span m="3807520">We</span> <span m="3807610">generate</span> <span m="3808170">the</span>
  <span m="3808240">corresponding--</span> <span m="3808600">it's</span> <span m="3808960">called</span>
  <span m="3809325">q</span> <span m="3809446">on</span> <span m="3809568">that</span>
  <span m="3809690">order</span> <span m="3809830">over</span> <span m="3809970">there.</span>
  <span m="3811080">Then</span> <span m="3811390">let's</span> <span m="3811760">go</span>
  <span m="3812310">and</span> <span m="3812810">take</span> <span m="3813540">input</span>
  <span m="3813860">case,</span> <span m="3814155">so</span> <span m="3814450">it's</span>
  <span m="3814550">like</span> <span m="3814720">the</span> <span m="3814790">first</span>
  <span m="3815100">one,</span> <span m="3815320">d1,</span> <span m="3816240">and</span>
  <span m="3816400">let's</span> <span m="3816840">fix</span> <span m="3817140">it</span>
  <span m="3817270">to</span> <span m="3817370">deterministic</span> <span m="3818060">value</span>
  <span m="3819240">so</span> <span m="3819410">it's</span> <span m="3819580">no</span>
  <span m="3819750">longer</span> <span m="3820030">got</span> <span m="3820180">a</span>
  <span m="3820240">pdf,</span> <span m="3820790">it's</span> <span m="3820930">no</span>
  <span m="3821050">longer</span> <span m="3821420">able</span> <span m="3821650">to</span>
  <span m="3821780">vary,</span> <span m="3822530">and</span> <span m="3822750">rerun</span>
  <span m="3823120">the</span> <span m="3823190">Monte</span> <span m="3823390">Carlo</span>
  <span m="3823770">with</span> <span m="3823960">all</span> <span m="3824080">the</span>
  <span m="3824210">other</span> <span m="3824370">ones--</span> <span m="3827060">all</span>
  <span m="3827230">the</span> <span m="3827470">other,</span> <span m="3828080">however</span>
  <span m="3828290">many</span> <span m="3828445">there</span> <span m="3828600">are</span>
  <span m="3828800">d</span> <span m="3828920">minus</span> <span m="3829070">1</span>
  <span m="3829220">inputs</span> <span m="3830730">varying.</span></p><p><span m="3831470">So</span>
  <span m="3831620">now</span> <span m="3831760">we</span> <span m="3831870">have</span>
  <span m="3832170">the</span> <span m="3832260">results</span> <span m="3832610">of</span>
  <span m="3832690">two</span> <span m="3832850">Monte</span> <span m="3833070">Carlo</span>
  <span m="3833370">simulations,</span> <span m="3834250">one</span> <span m="3834550">with</span>
  <span m="3834820">a</span> <span m="3834850">fixed,</span> <span m="3835090">one</span>
  <span m="3835290">was</span> <span m="3835360">varying,</span> <span m="3835740">and</span>
  <span m="3835830">one</span> <span m="3836010">where</span> <span m="3836140">it</span>
  <span m="3836220">wasn't.</span> <span m="3837630">And</span> <span m="3838040">you</span>
  <span m="3838110">could</span> <span m="3838220">compare</span> <span m="3838550">the</span>
  <span m="3838620">statistic</span> <span m="3839250">to</span> <span m="3839350">the</span>
  <span m="3839530">output.</span> <span m="3839950">You</span> <span m="3840020">could</span>
  <span m="3840160">look</span> <span m="3840330">at</span> <span m="3840410">the</span>
  <span m="3840480">variance</span> <span m="3841050">from</span> <span m="3841300">run</span>
  <span m="3841500">one,</span> <span m="3841790">and</span> <span m="3841890">the</span>
  <span m="3841930">variance</span> <span m="3842280">of</span> <span m="3842380">run</span>
  <span m="3842620">two.</span> <span m="3843680">And</span> <span m="3843890">you</span>
  <span m="3843990">could</span> <span m="3844270">then</span> <span m="3844580">attribute</span>
  <span m="3845270">the</span> <span m="3845360">difference</span> <span m="3846640">in</span>
  <span m="3846710">the</span> <span m="3846770">variance</span> <span m="3847420">to</span>
  <span m="3847690">that</span> <span m="3847900">fixed</span> <span m="3848310">factor.</span>
  <span m="3849800">And</span> <span m="3849940">then</span> <span m="3850050">he</span>
  <span m="3850160">would</span> <span m="3850330">repeat</span> <span m="3850690">it</span>
  <span m="3851290">with</span> <span m="3853680">1,</span> <span m="3854000">3,</span>
  <span m="3854490">4,</span> <span m="3854690">5,</span> <span m="3854890">6.</span>
  <span m="3855290">It</span> <span m="3855650">varies</span> <span m="3855920">at</span>
  <span m="3856200">6</span> <span m="3856470">2,</span> <span m="3857810">6</span>
  <span m="3858030">3,</span> <span m="3858340">6</span> <span m="3858530">4.</span>
  <span m="3859360">So</span> <span m="3859590">vary</span> <span m="3860120">all</span>
  <span m="3860580">but</span> <span m="3860820">one.</span></p><p><span m="3863990">I</span>
  <span m="3864090">mean,</span> <span m="3864295">maybe</span> <span m="3864500">it's</span>
  <span m="3864540">a</span> <span m="3864580">useful</span> <span m="3864860">thing</span>
  <span m="3865000">to</span> <span m="3865100">do,</span> <span m="3865190">but</span>
  <span m="3865445">of</span> <span m="3865700">course,</span> <span m="3865780">there's</span>
  <span m="3865860">question.</span> <span m="3866810">The</span> <span m="3866910">first</span>
  <span m="3867110">question</span> <span m="3867390">you'd</span> <span m="3867426">say,</span>
  <span m="3867463">well,</span> <span m="3867500">what</span> <span m="3867980">value</span>
  <span m="3868250">should</span> <span m="3868520">we</span> <span m="3868710">fix</span>
  <span m="3869203">factor</span> <span m="3869449">k?</span> <span m="3871670">If</span>
  <span m="3871970">we</span> <span m="3872400">fix</span> <span m="3872880">it</span>
  <span m="3873720">to</span> <span m="3874140">this</span> <span m="3874400">value</span>
  <span m="3874820">and</span> <span m="3874930">ran</span> <span m="3875060">the</span>
  <span m="3875130">Monte</span> <span m="3875340">Carlo,</span> <span m="3876160">would</span>
  <span m="3876320">we</span> <span m="3876420">get</span> <span m="3876580">a</span>
  <span m="3876630">different</span> <span m="3877720">result</span> <span m="3878280">than</span>
  <span m="3878420">if</span> <span m="3878570">we</span> <span m="3878690">fixed</span>
  <span m="3879100">it</span> <span m="3879510">a</span> <span m="3879630">different</span>
  <span m="3880030">value?</span> <span m="3881010">And</span> <span m="3881150">the</span>
  <span m="3881210">answer</span> <span m="3881570">for</span> <span m="3881790">a</span>
  <span m="3881830">complicated</span> <span m="3882340">system</span> <span m="3882660">is</span>
  <span m="3882850">probably</span> <span m="3883195">yes.</span></p><p><span m="3885640">And</span>
  <span m="3885850">then</span> <span m="3886220">the</span> <span m="3886320">other</span>
  <span m="3886480">question</span> <span m="3886750">maybe</span> <span m="3886960">you</span>
  <span m="3887050">should</span> <span m="3887170">be</span> <span m="3887250">wondering</span>
  <span m="3887630">is</span> <span m="3887780">what</span> <span m="3887960">about</span>
  <span m="3888350">possible</span> <span m="3888730">interactions.</span> <span m="3889400">If</span>
  <span m="3889510">I</span> <span m="3889580">fix</span> <span m="3889980">input</span>
  <span m="3890300">1</span> <span m="3890610">at</span> <span m="3890670">a</span>
  <span m="3890750">value</span> <span m="3891830">and</span> <span m="3892250">analyze</span>
  <span m="3894020">things,</span> <span m="3894400">but</span> <span m="3894540">what</span>
  <span m="3894670">if</span> <span m="3894790">I</span> <span m="3894910">fixed</span>
  <span m="3896440">input</span> <span m="3896820">1</span> <span m="3897000">and</span>
  <span m="3897250">input</span> <span m="3898000">2</span> <span m="3898270">and</span>
  <span m="3898413">there</span> <span m="3898556">were</span> <span m="3898700">interactions</span>
  <span m="3899210">between</span> <span m="3899490">them,</span> <span m="3899590">and</span>
  <span m="3899680">I</span> <span m="3899730">never</span> <span m="3900180">explored</span>
  <span m="3900445">them.</span> <span m="3901120">Are</span> <span m="3901530">there</span>
  <span m="3901950">interactions</span> <span m="3902580">that</span> <span m="3902730">might</span>
  <span m="3902920">be</span> <span m="3903020">important</span> <span m="3903640">that</span>
  <span m="3903790">I</span> <span m="3903870">would</span> <span m="3904330">be</span>
  <span m="3904430">missing?</span></p><p><span m="3906610">So</span> <span m="3907200">to</span>
  <span m="3907370">address</span> <span m="3908080">those</span> <span m="3908530">limitations</span>
  <span m="3909500">is</span> <span m="3909670">something</span> <span m="3910010">that's</span>
  <span m="3910170">called</span> <span m="3911340">global</span> <span m="3911570">sensitivity</span>
  <span m="3912330">analysis.</span> <span m="3914420">So</span> <span m="3915890">let's</span>
  <span m="3916380">get</span> <span m="3916995">this</span> <span m="3917490">off.</span>
  <span m="3919720">And</span> <span m="3920220">I</span> <span m="3920300">think</span>
  <span m="3920720">when</span> <span m="3920900">you</span> <span m="3920960">think</span>
  <span m="3921160">about</span> <span m="3921500">global</span> <span m="3921830">sensitivity</span>
  <span m="3922530">analysis,</span> <span m="3923620">it's</span> <span m="3923790">useful</span>
  <span m="3924170">to</span> <span m="3924290">have</span> <span m="3924740">this</span>
  <span m="3925930">vary</span> <span m="3926260">all</span> <span m="3926610">but</span>
  <span m="3926950">month's</span> <span m="3927180">color</span> <span m="3927540">in</span>
  <span m="3927670">your</span> <span m="3927760">mind</span> <span m="3928340">because</span>
  <span m="3930090">it's</span> <span m="3931760">conceptually</span> <span m="3933520">a</span>
  <span m="3933990">little</span> <span m="3934180">bit</span> <span m="3934340">the</span>
  <span m="3934420">same.</span> <span m="3936650">So</span> <span m="3937100">we're</span>
  <span m="3937270">on</span> <span m="3937600">4.</span> <span m="3938073">And</span>
  <span m="3938546">4a</span> <span m="3939020">was</span> <span m="3939640">the</span>
  <span m="3939930">vary-all-but-one.</span></p><p><span m="3940450">So</span> <span
  m="3940960">this</span> <span m="3941170">is</span> <span m="3941320">4b,</span>
  <span m="3943580">global</span> <span m="3943970">sensitivity</span> <span m="3944560">analysis.</span>
  <span m="3962162">So</span> <span m="3964470">I'm</span> <span m="3964570">going</span>
  <span m="3964600">to</span> <span m="3964630">draw</span> <span m="3964778">a</span>
  <span m="3964926">picture</span> <span m="3965075">here.</span> <span m="3965520">I'm</span>
  <span m="3965965">going</span> <span m="3966410">to</span> <span m="3966855">use</span>
  <span m="3967300">different</span> <span m="3967580">notation,</span> <span m="3968010">but</span>
  <span m="3968440">let</span> <span m="3968490">me</span> <span m="3968570">not</span>
  <span m="3968780">try</span> <span m="3968930">to</span> <span m="3969010">change</span>
  <span m="3969420">otherwise,</span> <span m="3969460">I</span> <span m="3969855">will</span>
  <span m="3970250">end</span> <span m="3970645">up</span> <span m="3971040">mixing</span>
  <span m="3971410">something</span> <span m="3971850">up.</span> <span m="3972050">So</span>
  <span m="3972160">we've</span> <span m="3972270">got</span> <span m="3972460">a</span>
  <span m="3972510">model.</span> <span m="3974450">So</span> <span m="3974620">then</span>
  <span m="3974820">I'll</span> <span m="3974885">call</span> <span m="3974950">the</span>
  <span m="3975050">inputs</span> <span m="3975550">x1,</span> <span m="3976980">x2,</span>
  <span m="3977890">down</span> <span m="3978345">to--</span> <span m="3979070">we're</span>
  <span m="3979150">going</span> <span m="3979270">to</span> <span m="3979340">have</span>
  <span m="3979998">[INAUDIBLE],</span> <span m="3984930">so</span> <span m="3985656">d</span>
  <span m="3986330">random</span> <span m="3986640">inputs.</span></p><p><span m="3988041">Now,</span>
  <span m="3988510">let's</span> <span m="3988800">just</span> <span m="3988950">think</span>
  <span m="3989130">about</span> <span m="3989850">a</span> <span m="3990306">single</span>
  <span m="3990762">random</span> <span m="3991218">output,</span> <span m="3992130">so</span>
  <span m="3992290">then</span> <span m="3992350">just</span> <span m="3992970">one</span>
  <span m="3993410">random</span> <span m="3993670">output.</span> <span m="4000688">So</span>
  <span m="4002050">global</span> <span m="4002504">sensitivity</span> <span m="4003330">analysis</span>
  <span m="4005950">defines</span> <span m="4007214">[AUDIO OUT]</span> <span m="4007616">called</span>
  <span m="4008018">sensitivity</span> <span m="4008420">indices.</span> <span m="4011210">And</span>
  <span m="4011370">there</span> <span m="4011490">are</span> <span m="4011540">two</span>
  <span m="4011950">different</span> <span m="4012460">kinds</span> <span m="4013040">of</span>
  <span m="4013160">sensitivity</span> <span m="4013910">indices.</span> <span m="4015360">So</span>
  <span m="4015480">the</span> <span m="4015540">first</span> <span m="4015840">one</span>
  <span m="4016190">is</span> <span m="4016450">what's</span> <span m="4016780">called</span>
  <span m="4017540">a</span> <span m="4017670">main</span> <span m="4018190">effect.</span>
  <span m="4018982">Did</span> <span m="4019181">I</span> <span m="4019380">talk</span>
  <span m="4019560">about</span> <span m="4021110">main</span> <span m="4021330">effects</span>
  <span m="4021860">in</span> <span m="4022020">1609,</span> <span m="4022360">6041?</span>
  <span m="4023783">No.</span> <span m="4025082">Maybe</span> <span m="4025515">in</span>
  <span m="4025950">62x,</span> <span m="4026560">anybody</span> <span m="4026910">seen</span>
  <span m="4027280">effects?</span></p><p><span m="4030230">So</span> <span m="4030330">if</span>
  <span m="4030470">you've</span> <span m="4030780">seen</span> <span m="4030910">effects</span>
  <span m="4032360">sensitivity</span> <span m="4033140">index</span> <span m="4036410">for</span>
  <span m="4039710">input</span> <span m="4040100">i,</span> <span m="4041040">usually</span>
  <span m="4041440">the</span> <span m="4041950">set</span> <span m="4042300">of</span>
  <span m="4042650">[? sessions ?]</span> <span m="4043070">of</span> <span m="4043170">u</span>
  <span m="4043330">say</span> <span m="4043490">people</span> <span m="4043750">would</span>
  <span m="4044035">use</span> <span m="4044320">it</span> <span m="4044420">with</span>
  <span m="4044545">factor</span> <span m="4044670">here,</span> <span m="4044970">but</span>
  <span m="4045400">let's</span> <span m="4045830">just</span> <span m="4046260">call</span>
  <span m="4046420">it</span> <span m="4046690">an</span> <span m="4046960">input.</span>
  <span m="4047820">So</span> <span m="4047910">this</span> <span m="4048390">thing</span>
  <span m="4048670">is</span> <span m="4049280">[? the limitation ?]</span> <span
  m="4049768">si.</span> <span m="4052210">Let's</span> <span m="4052440">write</span>
  <span m="4052590">the</span> <span m="4052660">formula</span> <span m="4053200">and</span>
  <span m="4053300">talk</span> <span m="4053490">about</span> <span m="4053640">what</span>
  <span m="4053740">it</span> <span m="4053830">means.</span> <span m="4054120">It's</span>
  <span m="4054410">the</span> <span m="4054530">variance</span> <span m="4055030">of</span>
  <span m="4055120">Y</span> <span m="4058250">minus</span> <span m="4059300">the</span>
  <span m="4059420">expected</span> <span m="4060110">value</span> <span m="4061020">of</span>
  <span m="4062500">the</span> <span m="4062600">variance</span> <span m="4062890">of</span>
  <span m="4065160">Y</span> <span m="4066200">given</span> <span m="4066790">xi</span>
  <span m="4070276">all</span> <span m="4070780">divided</span> <span m="4071130">by</span>
  <span m="4072161">the</span> <span m="4072652">variance,</span> <span m="4073143">Y.</span></p><p><span
  m="4083945">So</span> <span m="4084440">the</span> <span m="4084510">variance</span>
  <span m="4084920">of</span> <span m="4085030">Y</span> <span m="4085480">minus</span>
  <span m="4085890">the</span> <span m="4085990">expected</span> <span m="4086560">value</span>
  <span m="4086990">of</span> <span m="4087680">the</span> <span m="4087770">variance</span>
  <span m="4088210">of</span> <span m="4088310">Y</span> <span m="4088530">given</span>
  <span m="4088760">xi</span> <span m="4089380">divided</span> <span m="4089790">by</span>
  <span m="4089995">the</span> <span m="4090200">variance</span> <span m="4090405">of</span>
  <span m="4090610">Y.</span> <span m="4091440">Does</span> <span m="4091860">anyone</span>
  <span m="4092010">want</span> <span m="4092230">to</span> <span m="4092290">have</span>
  <span m="4092380">a</span> <span m="4092460">go</span> <span m="4092740">at</span>
  <span m="4093020">explaining</span> <span m="4093260">what</span> <span m="4093400">this</span>
  <span m="4093500">is?</span></p><p><span m="4096848">AUDIENCE:</span> <span m="4097346">[INAUDIBLE].</span></p><p><span
  m="4126230">KAREN WILLCOX:</span> <span m="4126740">Yes.</span> <span m="4127710">So</span>
  <span m="4130000">if</span> <span m="4130140">this</span> <span m="4130330">happened</span>
  <span m="4130640">to</span> <span m="4130729">be</span> <span m="4130910">0,</span>
  <span m="4132399">then</span> <span m="4132720">overall</span> <span m="4132995">sensitivity</span>
  <span m="4133270">index</span> <span m="4133850">would</span> <span m="4133979">be</span>
  <span m="4134100">what?</span> <span m="4135950">1.</span> <span m="4137290">And</span>
  <span m="4137430">it</span> <span m="4137490">would</span> <span m="4137620">mean</span>
  <span m="4137790">that</span> <span m="4138140">all</span> <span m="4138460">of</span>
  <span m="4138569">the</span> <span m="4138640">variance</span> <span m="4139080">in</span>
  <span m="4139180">Y</span> <span m="4139510">was</span> <span m="4139660">explained</span>
  <span m="4140050">by</span> <span m="4140414">xi,</span> <span m="4140779">because</span>
  <span m="4140920">when</span> <span m="4140974">we</span> <span m="4141029">fix</span>
  <span m="4141370">xi</span> <span m="4142649">the</span> <span m="4142740">variance</span>
  <span m="4143140">[INAUDIBLE].</span> <span m="4145029">What</span> <span m="4145370">about</span>
  <span m="4145660">if</span> <span m="4146250">the</span> <span m="4146350">variance</span>
  <span m="4146750">of</span> <span m="4146850">this</span> <span m="4147130">thing</span>
  <span m="4147439">were</span> <span m="4147710">the</span> <span m="4148010">variance</span>
  <span m="4148220">of</span> <span m="4148717">Y?</span> <span m="4149711">Doesn't</span>
  <span m="4150208">have</span> <span m="4150456">any</span> <span m="4150705">effect.</span>
  <span m="4151202">Yes.</span></p><p><span m="4152540">Why</span> <span m="4152729">is</span>
  <span m="4152810">there</span> <span m="4152920">an</span> <span m="4153000">expectation</span>
  <span m="4153800">here?</span> <span m="4161149">So</span> <span m="4161279">we</span>
  <span m="4161390">go</span> <span m="4161800">with</span> <span m="4162229">[AUDIO
  OUT]</span> <span m="4164640">So</span> <span m="4164700">we're</span> <span m="4164819">saying</span>
  <span m="4165140">Y</span> <span m="4165520">give</span> <span m="4165670">xi.</span></p><p><span
  m="4167686">AUDIENCE:</span> <span m="4168185">[INAUDIBLE].</span></p><p><span m="4177167">KAREN
  WILLCOX:</span> <span m="4177666">Yeah.</span> <span m="4178180">If</span> <span
  m="4178770">we</span> <span m="4178870">picked</span> <span m="4179120">any</span>
  <span m="4179380">particular</span> <span m="4180060">value</span> <span m="4180420">which</span>
  <span m="4180580">to</span> <span m="4180740">effect</span> <span m="4180870">xi,</span>
  <span m="4181752">as</span> <span m="4182100">I</span> <span m="4182330">said</span>
  <span m="4182700">given</span> <span m="4182960">xie</span> <span m="4183930">to</span>
  <span m="4184069">some</span> <span m="4184130">x</span> <span m="4184270">star,</span>
  <span m="4185119">then</span> <span m="4185460">it</span> <span m="4185580">would</span>
  <span m="4185810">just</span> <span m="4185860">be</span> <span m="4185910">a</span>
  <span m="4185960">number.</span> <span m="4187510">But</span> <span m="4187729">because</span>
  <span m="4188380">this</span> <span m="4188490">thing</span> <span m="4188910">is</span>
  <span m="4189399">a</span> <span m="4189850">random</span> <span m="4190345">variable,</span>
  <span m="4190840">we</span> <span m="4190960">don't</span> <span m="4191120">know</span>
  <span m="4191279">where</span> <span m="4191520">to</span> <span m="4191620">fix</span>
  <span m="4192080">it.</span> <span m="4192260">So</span> <span m="4192620">this</span>
  <span m="4192650">is</span> <span m="4192680">addressing</span> <span m="4192710">this</span>
  <span m="4192740">question</span> <span m="4192990">of</span> <span m="4193060">we</span>
  <span m="4193130">don't</span> <span m="4193270">know</span> <span m="4193410">where</span>
  <span m="4193580">to</span> <span m="4193649">fix</span> <span m="4193970">it.</span>
  <span m="4195188">So</span> <span m="4196000">at</span> <span m="4196080">least</span>
  <span m="4196410">the</span> <span m="4196510">way</span> <span m="4196630">I</span>
  <span m="4196750">think</span> <span m="4196930">of</span> <span m="4196990">it</span>
  <span m="4197100">conceptually</span> <span m="4197515">is</span> <span m="4197930">that</span>
  <span m="4198500">we're</span> <span m="4198590">going</span> <span m="4198710">to</span>
  <span m="4198980">fix</span> <span m="4199230">it</span> <span m="4199310">at</span>
  <span m="4199410">all</span> <span m="4199520">possible</span> <span m="4200050">places</span>
  <span m="4200740">and</span> <span m="4200920">then</span> <span m="4201245">[INAUDIBLE]</span>
  <span m="4201570">over</span> <span m="4202010">there.</span></p><p><span m="4203234">And</span>
  <span m="4203642">so</span> <span m="4204050">it's</span> <span m="4204240">the</span>
  <span m="4205050">expected</span> <span m="4206880">reduction</span> <span m="4207430">in</span>
  <span m="4207540">the</span> <span m="4207620">variance</span> <span m="4208110">is</span>
  <span m="4208330">relative.</span> <span m="4208650">It's</span> <span m="4208970">normalized.</span>
  <span m="4209910">So</span> <span m="4210020">it's</span> <span m="4210110">the</span>
  <span m="4210200">expected</span> <span m="4210700">relative</span> <span m="4211350">reduction</span>
  <span m="4211800">of</span> <span m="4211890">the</span> <span m="4211980">variance</span>
  <span m="4212780">if</span> <span m="4212970">we</span> <span m="4213100">learned</span>
  <span m="4213380">everything</span> <span m="4213710">about</span> <span m="4214150">the</span>
  <span m="4214420">factor</span> <span m="4214868">xi.</span> <span m="4216660">So</span>
  <span m="4217110">it's</span> <span m="4217330">giving</span> <span m="4217710">us</span>
  <span m="4218220">a</span> <span m="4219570">measure</span> <span m="4219950">of</span>
  <span m="4220060">how</span> <span m="4220230">much</span> <span m="4220490">to</span>
  <span m="4220660">does</span> <span m="4220890">xi</span> <span m="4221120">contribute</span>
  <span m="4221560">to</span> <span m="4221780">the</span> <span m="4221880">variance</span>
  <span m="4222300">in</span> <span m="4222450">Y,</span> <span m="4223490">but</span>
  <span m="4223610">it's</span> <span m="4223720">a</span> <span m="4223770">measure</span>
  <span m="4224160">where</span> <span m="4224320">we're</span> <span m="4224600">taking</span>
  <span m="4224920">expectation</span> <span m="4225710">over</span> <span m="4226000">the</span>
  <span m="4226260">possible</span> <span m="4226740">values</span> <span m="4227260">that</span>
  <span m="4227510">xi</span> <span m="4227960">could</span> <span m="4228170">take</span>
  <span m="4228500">on.</span> <span m="4228830">So</span> <span m="4228980">that's</span>
  <span m="4229550">where</span> <span m="4229750">the</span> <span m="4229890">word</span>
  <span m="4230070">global</span> <span m="4230250">come</span> <span m="4230470">from.</span>
  <span m="4231352">[INAUDIBLE].</span></p><p><span m="4236740">So</span> <span m="4237170">let</span>
  <span m="4237550">me</span> <span m="4237720">just</span> <span m="4237900">write</span>
  <span m="4238355">it</span> <span m="4238582">in</span> <span m="4238810">words.</span>
  <span m="4239720">So</span> <span m="4241030">expected</span> <span m="4241360">relative</span>
  <span m="4243170">reduction</span> <span m="4245170">in</span> <span m="4245350">output</span>
  <span m="4245760">variance--</span> <span m="4247330">and</span> <span m="4247485">then</span>
  <span m="4247640">output</span> <span m="4247990">variance</span> <span m="4248285">is</span>
  <span m="4249400">variance</span> <span m="4249810">of</span> <span m="4249900">Y--</span>
  <span m="4253310">it's</span> <span m="4253440">a</span> <span m="4253510">true</span>
  <span m="4253840">value</span> <span m="4256020">of</span> <span m="4258480">xi</span>
  <span m="4258630">is</span> <span m="4259096">[? learned. ?]</span> <span m="4264230">And</span>
  <span m="4264315">then</span> <span m="4264400">another</span> <span m="4264740">thing</span>
  <span m="4264890">that's</span> <span m="4265080">important</span> <span m="4265840">to</span>
  <span m="4266060">see</span> <span m="4266460">is</span> <span m="4266700">that</span>
  <span m="4266860">this</span> <span m="4266950">is</span> <span m="4267090">a</span>
  <span m="4267130">measure</span> <span m="4268920">of</span> <span m="4269440">the</span>
  <span m="4274930">effects</span> <span m="4275350">of</span> <span m="4275410">varying</span>
  <span m="4275850">xi</span> <span m="4276320">alone.</span> <span m="4283290">And</span>
  <span m="4283430">if</span> <span m="4283510">we</span> <span m="4283630">wrote</span>
  <span m="4283870">this</span> <span m="4284160">in</span> <span m="4284360">a</span>
  <span m="4284400">slightly</span> <span m="4284850">different</span> <span m="4285140">way,</span>
  <span m="4285260">we</span> <span m="4285370">could</span> <span m="4285500">write</span>
  <span m="4285690">it,</span> <span m="4285770">we</span> <span m="4285860">can</span>
  <span m="4286050">see</span> <span m="4286250">that</span> <span m="4286430">would</span>
  <span m="4286560">be</span> <span m="4287450">averaged</span> <span m="4287815">over</span>
  <span m="4290280">variations</span> <span m="4290540">in</span> <span m="4290800">other</span>
  <span m="4291080">inputs.</span></p><p><span m="4297742">We'll</span> <span m="4298184">see</span>
  <span m="4298630">you</span> <span m="4299170">Monday</span> <span m="4299460">when</span>
  <span m="4299580">we</span> <span m="4299650">talk</span> <span m="4299830">about</span>
  <span m="4300150">[? planet ?]</span> <span m="4300420">experiments.</span> <span
  m="4302460">It's</span> <span m="4302720">another</span> <span m="4303220">way</span>
  <span m="4303450">of</span> <span m="4303840">computing</span> <span m="4304230">of</span>
  <span m="4304400">effects</span> <span m="4304540">that</span> <span m="4304680">[?
  finds ?]</span> <span m="4304755">out</span> <span m="4304830">more</span> <span
  m="4304990">with</span> <span m="4305150">the</span> <span m="4305270">second</span>
  <span m="4305620">interpretation.</span> <span m="4306720">Let</span> <span m="4306820">me</span>
  <span m="4306920">say</span> <span m="4307060">it</span> <span m="4307190">again.</span>
  <span m="4307320">Measure,</span> <span m="4308890">this</span> <span m="4309050">is</span>
  <span m="4309110">what</span> <span m="4309170">we</span> <span m="4309250">talked</span>
  <span m="4309490">about.</span> <span m="4310630">Measure</span> <span m="4310965">of</span>
  <span m="4311300">the</span> <span m="4311500">effect</span> <span m="4311700">of</span>
  <span m="4311790">varying</span> <span m="4312120">xi</span> <span m="4312240">alone</span>
  <span m="4313810">averaged</span> <span m="4314290">over</span> <span m="4314770">the</span>
  <span m="4314990">variations</span> <span m="4315500">of</span> <span m="4315570">other</span>
  <span m="4315850">inputs.</span></p><p><span m="4317200">And</span> <span m="4317330">that's</span>
  <span m="4317550">where</span> <span m="4318070">the</span> <span m="4318140">term</span>
  <span m="4318350">main</span> <span m="4319310">effect</span> <span m="4319460">comes</span>
  <span m="4319950">in.</span> <span m="4320113">So</span> <span m="4320276">if</span>
  <span m="4320440">we</span> <span m="4320590">were</span> <span m="4320700">to</span>
  <span m="4320780">change</span> <span m="4321240">xi,</span> <span m="4321525">if</span>
  <span m="4321810">we</span> <span m="4321890">were</span> <span m="4322020">to</span>
  <span m="4322150">vary</span> <span m="4322280">xi,</span> <span m="4324510">how</span>
  <span m="4324760">does</span> <span m="4324940">it</span> <span m="4325870">change</span>
  <span m="4326310">the</span> <span m="4326420">output</span> <span m="4328320">averaged</span>
  <span m="4328730">over</span> <span m="4328920">everything</span> <span m="4329430">else</span>
  <span m="4329780">in</span> <span m="4330180">the</span> <span m="4330260">[? x3,
  ?]</span> <span m="4330810">x4</span> <span m="4330840">varying?</span> <span m="4333520">Is</span>
  <span m="4334010">that</span> <span m="4334500">clear?</span> <span m="4334980">So</span>
  <span m="4335010">there</span> <span m="4335040">are</span> <span m="4335070">two</span>
  <span m="4335710">different</span> <span m="4335990">ways</span> <span m="4336360">you</span>
  <span m="4336520">can</span> <span m="4337700">think</span> <span m="4337980">about</span>
  <span m="4338240">that.</span></p><p><span m="4338310">AUDIENCE:</span> <span m="4338794">[INAUDIBLE].</span></p><p><span
  m="4346054">KAREN WILLCOX:</span> <span m="4346550">So</span> <span m="4346820">xi</span>
  <span m="4348000">can</span> <span m="4348240">at</span> <span m="4348350">most</span>
  <span m="4348890">be</span> <span m="4349920">1</span> <span m="4352270">because</span>
  <span m="4354620">the</span> <span m="4354740">most</span> <span m="4354950">we</span>
  <span m="4355020">can</span> <span m="4355130">get</span> <span m="4355250">here</span>
  <span m="4355390">is</span> <span m="4355500">0</span> <span m="4356770">if</span>
  <span m="4356950">i</span> <span m="4357070">is</span> <span m="4357160">going</span>
  <span m="4357280">to</span> <span m="4357340">be</span> <span m="4357410">between</span>
  <span m="4357670">0</span> <span m="4357820">and</span> <span m="4357950">1.</span>
  <span m="4358990">And</span> <span m="4360180">the</span> <span m="4360330">idea</span>
  <span m="4360710">is</span> <span m="4360850">that</span> <span m="4360915">you</span>
  <span m="4360980">could</span> <span m="4361190">compute</span> <span m="4361650">these</span>
  <span m="4361920">then</span> <span m="4362020">you</span> <span m="4362090">would</span>
  <span m="4362260">rank</span> <span m="4362560">them.</span> <span m="4364090">And</span>
  <span m="4364200">if</span> <span m="4364320">you</span> <span m="4364460">were</span>
  <span m="4364620">looking</span> <span m="4365090">for</span> <span m="4366060">where</span>
  <span m="4366350">you</span> <span m="4366450">focus</span> <span m="4366770">your</span>
  <span m="4366900">efforts,</span> <span m="4367440">which</span> <span m="4367660">variable</span>
  <span m="4368060">you</span> <span m="4368150">try</span> <span m="4368350">to</span>
  <span m="4368590">control</span> <span m="4369020">in</span> <span m="4369060">the</span>
  <span m="4369100">manufacturing</span> <span m="4369360">process,</span> <span m="4370640">before</span>
  <span m="4370900">we</span> <span m="4370960">go</span> <span m="4371110">after</span>
  <span m="4371360">the</span> <span m="4371450">one</span> <span m="4371760">with</span>
  <span m="4371930">the</span> <span m="4372010">biggest</span> <span m="4372860">sensitivity</span>
  <span m="4373070">index</span> <span m="4373210">that</span> <span m="4373380">you</span>
  <span m="4373874">occupy.</span></p><p><span m="4375850">So</span> <span m="4376670">actually</span>
  <span m="4376980">turns</span> <span m="4377280">out</span> <span m="4377450">we</span>
  <span m="4377550">can</span> <span m="4377710">also</span> <span m="4379880">compute</span>
  <span m="4380370">higher</span> <span m="4380780">order</span> <span m="4381100">interaction</span>
  <span m="4381880">indices.</span> <span m="4384630">You</span> <span m="4384700">can</span>
  <span m="4384840">also</span> <span m="4385080">compute</span> <span m="4385520">effects</span>
  <span m="4388080">for</span> <span m="4388240">the</span> <span m="4388350">interactions.</span>
  <span m="4392270">And</span> <span m="4392430">I</span> <span m="4392500">won't</span>
  <span m="4395290">go</span> <span m="4395480">into</span> <span m="4395630">details,</span>
  <span m="4396070">but</span> <span m="4396760">instead</span> <span m="4396935">of</span>
  <span m="4397110">now</span> <span m="4397380">just</span> <span m="4397570">being</span>
  <span m="4397840">si,</span> <span m="4398450">there</span> <span m="4398550">could</span>
  <span m="4398690">be</span> <span m="4398850">an</span> <span m="4398940">sij,</span>
  <span m="4399670">which</span> <span m="4399880">would</span> <span m="4400000">be</span>
  <span m="4400180">two</span> <span m="4400670">variables,</span> <span m="4400935">two</span>
  <span m="4401200">inputs</span> <span m="4401740">interacting</span> <span m="4402970">or</span>
  <span m="4403160">three</span> <span m="4403760">variables</span> <span m="4404500">interacting</span>
  <span m="4405280">or</span> <span m="4405510">four,</span> <span m="4405850">all</span>
  <span m="4405970">the</span> <span m="4406040">way</span> <span m="4406230">up</span>
  <span m="4406420">to</span> <span m="4406610">all</span> <span m="4406890">of</span>
  <span m="4407000">them</span> <span m="4407880">interacting.</span></p><p><span
  m="4409530">And</span> <span m="4409950">what</span> <span m="4410140">the</span>
  <span m="4410210">match</span> <span m="4410610">shows,</span> <span m="4411030">I</span>
  <span m="4411220">mean,</span> <span m="4411320">we're</span> <span m="4411420">not</span>
  <span m="4411520">going</span> <span m="4411640">to</span> <span m="4411710">talk</span>
  <span m="4411940">about</span> <span m="4412250">it,</span> <span m="4412610">is</span>
  <span m="4412780">this</span> <span m="4412960">idea</span> <span m="4413400">that</span>
  <span m="4413550">you</span> <span m="4413640">can</span> <span m="4413820">take</span>
  <span m="4414100">the</span> <span m="4414170">variance</span> <span m="4414670">of</span>
  <span m="4414790">Y,</span> <span m="4415640">think</span> <span m="4415840">of</span>
  <span m="4415930">it</span> <span m="4416040">as</span> <span m="4416160">this</span>
  <span m="4416380">pi,</span> <span m="4418130">and</span> <span m="4418320">you</span>
  <span m="4418420">can</span> <span m="4420340">decompose</span> <span m="4420780">this</span>
  <span m="4420960">variance</span> <span m="4421580">of</span> <span m="4421730">Y.</span>
  <span m="4422740">So</span> <span m="4422900">let's</span> <span m="4423780">think</span>
  <span m="4424010">about--</span> <span m="4424580">it's</span> <span m="4424850">easier</span>
  <span m="4424985">for</span> <span m="4425120">me</span> <span m="4425280">to</span>
  <span m="4425380">draw</span> <span m="4426440">fY</span> <span m="4427380">depends</span>
  <span m="4430610">on</span> <span m="4431040">x1</span> <span m="4431330">and</span>
  <span m="4431620">x2,</span> <span m="4432430">so</span> <span m="4432580">they're</span>
  <span m="4432680">just</span> <span m="4432870">two</span> <span m="4433060">inputs.</span>
  <span m="4434860">There</span> <span m="4434980">would</span> <span m="4435110">be</span>
  <span m="4435240">a</span> <span m="4435310">part</span> <span m="4435750">of</span>
  <span m="4435850">the</span> <span m="4435960">variance</span> <span m="4437230">that</span>
  <span m="4437410">might</span> <span m="4437640">be</span> <span m="4437810">due</span>
  <span m="4438260">to</span> <span m="4440030">x1</span> <span m="4441430">acting</span>
  <span m="4441720">alone,</span> <span m="4443120">there</span> <span m="4443280">might</span>
  <span m="4443450">be</span> <span m="4443550">a</span> <span m="4443620">part</span>
  <span m="4443920">of</span> <span m="4443980">the</span> <span m="4444050">variance</span>
  <span m="4444570">that's</span> <span m="4444870">due</span> <span m="4445290">to</span>
  <span m="4445510">x2</span> <span m="4446160">acting</span> <span m="4446470">alone,</span>
  <span m="4447040">and</span> <span m="4447160">there</span> <span m="4447260">might</span>
  <span m="4447440">be</span> <span m="4447550">a</span> <span m="4447610">part</span>
  <span m="4447940">of</span> <span m="4448090">the</span> <span m="4448210">variance</span>
  <span m="4449550">of</span> <span m="4449850">the</span> <span m="4449940">interaction</span>
  <span m="4450460">between</span> <span m="4450810">x1</span> <span m="4451110">and</span>
  <span m="4451720">x2.</span></p><p><span m="4453678">And</span> <span m="4454230">if</span>
  <span m="4454520">we</span> <span m="4454610">computed</span> <span m="4454850">the</span>
  <span m="4455010">sensitivity</span> <span m="4455590">indices,</span> <span m="4455830">f1,</span>
  <span m="4456964">f2,</span> <span m="4458232">and</span> <span m="4459116">f12,</span>
  <span m="4461330">they</span> <span m="4461460">would</span> <span m="4461600">all</span>
  <span m="4461790">come</span> <span m="4462000">up</span> <span m="4462150">to</span>
  <span m="4462300">1.</span> <span m="4465120">Or</span> <span m="4465530">the</span>
  <span m="4465620">variance</span> <span m="4466050">due</span> <span m="4466200">to</span>
  <span m="4466366">x1,</span> <span m="4466533">the</span> <span m="4466700">variance</span>
  <span m="4467150">due</span> <span m="4467370">to</span> <span m="4467435">x2,</span>
  <span m="4467500">and</span> <span m="4467920">the</span> <span m="4468130">variance</span>
  <span m="4468340">x12</span> <span m="4469070">would</span> <span m="4469270">come</span>
  <span m="4469410">out</span> <span m="4469550">to</span> <span m="4469660">be</span>
  <span m="4469780">the</span> <span m="4469860">variance</span> <span m="4470830">of</span>
  <span m="4471110">Y.</span> <span m="4472765">And</span> <span m="4473210">you</span>
  <span m="4473655">can</span> <span m="4473877">show</span> <span m="4474100">there</span>
  <span m="4474220">is</span> <span m="4475730">something</span> <span m="4476120">called</span>
  <span m="4476330">a</span> <span m="4476380">high</span> <span m="4476510">dimensional</span>
  <span m="4476900">model</span> <span m="4477120">representation</span> <span m="4477640">that</span>
  <span m="4477760">shows</span> <span m="4478070">how</span> <span m="4479050">all</span>
  <span m="4479170">of</span> <span m="4479290">this</span> <span m="4479680">comes</span>
  <span m="4479990">out.</span> <span m="4480320">So</span> <span m="4480420">it's</span>
  <span m="4480720">kind</span> <span m="4480860">of</span> <span m="4480930">a</span>
  <span m="4480980">nice</span> <span m="4481230">result</span> <span m="4481630">that</span>
  <span m="4481760">you</span> <span m="4482540">can</span> <span m="4482900">attribute.</span></p><p><span
  m="4485200">It</span> <span m="4485270">actually</span> <span m="4486270">turns</span>
  <span m="4486580">out</span> <span m="4486710">that</span> <span m="4486820">there's</span>
  <span m="4487020">something</span> <span m="4487380">else</span> <span m="4487800">also</span>
  <span m="4488350">called</span> <span m="4488600">a</span> <span m="4488650">total</span>
  <span m="4489040">effect</span> <span m="4489430">sensitivity</span> <span m="4489700">index</span>
  <span m="4491700">that</span> <span m="4491840">you</span> <span m="4491930">can</span>
  <span m="4492090">also</span> <span m="4492390">compute</span> <span m="4493520">that</span>
  <span m="4494220">tells</span> <span m="4494630">you</span> <span m="4495650">how</span>
  <span m="4495870">much</span> <span m="4496210">does</span> <span m="4496470">x1</span>
  <span m="4497420">contribute,</span> <span m="4498150">not</span> <span m="4498370">just</span>
  <span m="4498590">by</span> <span m="4498750">itself</span> <span m="4499560">but</span>
  <span m="4499740">with</span> <span m="4499870">all</span> <span m="4500030">of</span>
  <span m="4500100">the</span> <span m="4500250">interactions</span> <span m="4500760">as</span>
  <span m="4500890">well.</span> <span m="4501770">So</span> <span m="4501790">the</span>
  <span m="4501870">total</span> <span m="4502300">effect</span> <span m="4503086">sensitivity</span>
  <span m="4504070">index,</span> <span m="4505130">what</span> <span m="4505310">include</span>
  <span m="4505810">x1</span> <span m="4506240">and</span> <span m="4506370">x12,</span>
  <span m="4508090">x1.</span> <span m="4508410">And</span> <span m="4508510">the</span>
  <span m="4508570">total</span> <span m="4508910">effect</span> <span m="4509275">x2</span>
  <span m="4509640">would</span> <span m="4509830">include</span> <span m="4510230">x2</span>
  <span m="4510640">and</span> <span m="4510980">x12.</span> <span m="4512210">And</span>
  <span m="4512360">then</span> <span m="4512460">all</span> <span m="4512560">the</span>
  <span m="4512670">other</span> <span m="4512810">ones,</span> <span m="4513120">if</span>
  <span m="4513210">you</span> <span m="4513300">had</span> <span m="4513430">more</span>
  <span m="4513710">variables</span> <span m="4514200">then</span> <span m="4514900">I</span>
  <span m="4515040">would</span> <span m="4515170">add</span> <span m="4515360">them</span>
  <span m="4515480">all</span> <span m="4515620">up,</span> <span m="4515820">and</span>
  <span m="4515920">it</span> <span m="4516200">turns</span> <span m="4516295">out</span>
  <span m="4516390">to</span> <span m="4516500">be</span> <span m="4517400">a</span>
  <span m="4517490">fairly</span> <span m="4517800">easy</span> <span m="4518020">way</span>
  <span m="4518170">to</span> <span m="4518290">compute</span> <span m="4518660">that</span>
  <span m="4518900">as</span> <span m="4519060">well.</span></p><p><span m="4524620">Last</span>
  <span m="4524800">questions?</span> <span m="4527660">Great.</span></p><p><span
  m="4528419">AUDIENCE:</span> <span m="4528898">[INAUDIBLE]?</span></p><p><span m="4537041">KAREN
  WILLCOX:</span> <span m="4537520">Yeah,</span> <span m="4537860">that's</span> <span
  m="4538010">a</span> <span m="4538050">good</span> <span m="4538200">question.</span>
  <span m="4538420">So</span> <span m="4538570">I</span> <span m="4538640">actually</span>
  <span m="4538870">haven't</span> <span m="4539100">told</span> <span m="4539390">you</span>
  <span m="4539530">how</span> <span m="4539690">to</span> <span m="4539780">compute</span>
  <span m="4540210">these</span> <span m="4540500">things</span> <span m="4540750">that</span>
  <span m="4540880">all.</span> <span m="4541570">These</span> <span m="4541760">are</span>
  <span m="4541790">the</span> <span m="4541890">expressions</span> <span m="4542400">for</span>
  <span m="4542520">them.</span> <span m="4543466">It</span> <span m="4543940">turns</span>
  <span m="4544240">out</span> <span m="4544350">there</span> <span m="4544490">are</span>
  <span m="4544520">a</span> <span m="4544560">couple</span> <span m="4544800">different</span>
  <span m="4545070">ways.</span> <span m="4546320">I</span> <span m="4546440">think</span>
  <span m="4546620">the</span> <span m="4546680">most</span> <span m="4546870">common</span>
  <span m="4547260">way</span> <span m="4547670">to</span> <span m="4547770">compute</span>
  <span m="4548380">these</span> <span m="4548640">things</span> <span m="4548960">is</span>
  <span m="4549220">a</span> <span m="4549320">method</span> <span m="4549600">called</span>
  <span m="4549790">the</span> <span m="4549860">[? Sogl ?]</span> <span m="4550260">method.</span>
  <span m="4551035">[? Sogl, ?]</span> <span m="4551420">I</span> <span m="4551500">think,</span>
  <span m="4551700">was</span> <span m="4552090">a</span> <span m="4552480">Russian</span>
  <span m="4552860">statistician,</span> <span m="4553920">which</span> <span m="4554120">involves</span>
  <span m="4554360">Monte</span> <span m="4554600">Carlo</span> <span m="4555140">simulations.</span>
  <span m="4556710">And</span> <span m="4557140">you</span> <span m="4557240">basically</span>
  <span m="4557640">end</span> <span m="4557800">up</span> <span m="4557910">doing</span>
  <span m="4558270">one</span> <span m="4558440">Monte</span> <span m="4558650">Carlo</span>
  <span m="4559000">simulation</span> <span m="4559440">and</span> <span m="4559880">then</span>
  <span m="4560800">you</span> <span m="4560910">do</span> <span m="4561020">a</span>
  <span m="4561130">second</span> <span m="4561440">Monte</span> <span m="4561670">Carlo</span>
  <span m="4561990">simulation</span> <span m="4562740">where</span> <span m="4563000">you</span>
  <span m="4563530">free</span> <span m="4563830">some</span> <span m="4564020">of</span>
  <span m="4564080">the</span> <span m="4564140">variables</span> <span m="4564560">and</span>
  <span m="4565150">redraw</span> <span m="4565530">other</span> <span m="4565790">ones.</span>
  <span m="4566790">And</span> <span m="4566820">it's</span> <span m="4566940">done</span>
  <span m="4567130">in</span> <span m="4567220">kind</span> <span m="4567350">of</span>
  <span m="4567420">a</span> <span m="4567460">clever</span> <span m="4567780">way</span>
  <span m="4568210">so</span> <span m="4568390">that</span> <span m="4568580">you</span>
  <span m="4568760">get</span> <span m="4569230">to</span> <span m="4569465">this.</span></p><p><span
  m="4571110">So</span> <span m="4571240">then</span> <span m="4571430">the</span>
  <span m="4571500">question</span> <span m="4571880">of</span> <span m="4572050">how</span>
  <span m="4572370">[? converge ?]</span> <span m="4572790">of</span> <span m="4572870">the</span>
  <span m="4572930">sensitivity</span> <span m="4573960">indices</span> <span m="4574510">comes</span>
  <span m="4574840">to</span> <span m="4574960">be</span> <span m="4575040">a</span>
  <span m="4575070">question</span> <span m="4575400">of</span> <span m="4575510">how</span>
  <span m="4575740">converged</span> <span m="4576136">are</span> <span m="4576532">the</span>
  <span m="4576930">variance</span> <span m="4577100">estimates.</span> <span m="4577852">And</span>
  <span m="4578230">we've</span> <span m="4578440">talked</span> <span m="4578650">a</span>
  <span m="4578730">lot</span> <span m="4578910">about</span> <span m="4579240">mean</span>
  <span m="4579510">estimate</span> <span m="4579790">and</span> <span m="4580050">how</span>
  <span m="4580150">they</span> <span m="4580280">converge.</span> <span m="4580460">It</span>
  <span m="4580870">actually</span> <span m="4581110">turns</span> <span m="4581360">out</span>
  <span m="4581500">that</span> <span m="4581560">to</span> <span m="4581620">get</span>
  <span m="4581840">variance</span> <span m="4582160">to</span> <span m="4582270">converge,</span>
  <span m="4582455">you</span> <span m="4582640">usually</span> <span m="4582900">have</span>
  <span m="4583030">to</span> <span m="4583140">take</span> <span m="4583380">more</span>
  <span m="4583570">Monte</span> <span m="4583800">Carlo</span> <span m="4584225">simulations.</span>
  <span m="4585500">Most</span> <span m="4585760">of</span> <span m="4585800">the</span>
  <span m="4585840">time</span> <span m="4586000">when</span> <span m="4586110">we</span>
  <span m="4586220">use</span> <span m="4586420">these</span> <span m="4586630">things,</span>
  <span m="4586910">we</span> <span m="4587000">do</span> <span m="4587120">as</span>
  <span m="4587230">many</span> <span m="4587460">samples</span> <span m="4587810">as</span>
  <span m="4587900">we</span> <span m="4588010">can</span> <span m="4588170">afford,</span>
  <span m="4588540">and</span> <span m="4588910">that</span> <span m="4589070">ends</span>
  <span m="4589510">up</span> <span m="4589730">being</span> <span m="4589950">the</span>
  <span m="4590390">[INAUDIBLE].</span></p><p><span m="4590830">So</span> <span m="4591310">that's</span>
  <span m="4591470">a</span> <span m="4591520">good</span> <span m="4591660">question.</span>
  <span m="4592090">And</span> <span m="4592160">it</span> <span m="4592230">also</span>
  <span m="4592420">depends</span> <span m="4592580">on</span> <span m="4592740">what</span>
  <span m="4592910">you</span> <span m="4593010">want.</span> <span m="4593320">Do</span>
  <span m="4593420">you</span> <span m="4593540">actually</span> <span m="4593910">care</span>
  <span m="4594390">whether</span> <span m="4594580">you</span> <span m="4594745">get</span>
  <span m="4594910">the</span> <span m="4594990">sensitivity</span> <span m="4595530">index</span>
  <span m="4596070">to</span> <span m="4596240">four</span> <span m="4596530">decimal</span>
  <span m="4596706">places,</span> <span m="4597590">or</span> <span m="4597760">do</span>
  <span m="4597850">you</span> <span m="4597910">just</span> <span m="4598110">care</span>
  <span m="4598360">about</span> <span m="4598710">saying</span> <span m="4599300">number</span>
  <span m="4599580">two</span> <span m="4599880">is</span> <span m="4600180">the</span>
  <span m="4600480">biggest?</span></p>
type: course
uid: 753f0a2f14246c7872ca5ab157b69a42

---
None