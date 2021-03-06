---
about_this_resource_text: ''
course_id: 18-650-statistics-for-applications-fall-2016
embedded_media:
- id: Video-YouTube-Stream
  media_location: WW3ZJHPwvyg
  parent_uid: 6c01f00215566284e6dc0c87d3ed95a5
  title: Video-YouTube-Stream
  type: Video
  uid: 1dc98493d35dfabeba7b28456b5d7945
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/WW3ZJHPwvyg/default.jpg
  parent_uid: 6c01f00215566284e6dc0c87d3ed95a5
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 7b923b50cb2c0a076824474a575f41cb
- id: 3Play-3PlayYouTubeid-MP4
  media_location: WW3ZJHPwvyg
  parent_uid: 6c01f00215566284e6dc0c87d3ed95a5
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: b69692b8c9c9d30c1fb15310a1beffc6
- id: WW3ZJHPwvyg.srt
  parent_uid: 6c01f00215566284e6dc0c87d3ed95a5
  technical_location: https://ocw.mit.edu/courses/mathematics/18-650-statistics-for-applications-fall-2016/lecture-videos/lecture-19-video/WW3ZJHPwvyg.srt
  title: 3play caption file
  type: null
  uid: 1c9e690bd423b5dd1c5eb3132b0a6b6f
- id: WW3ZJHPwvyg.pdf
  parent_uid: 6c01f00215566284e6dc0c87d3ed95a5
  technical_location: https://ocw.mit.edu/courses/mathematics/18-650-statistics-for-applications-fall-2016/lecture-videos/lecture-19-video/WW3ZJHPwvyg.pdf
  title: 3play pdf file
  type: null
  uid: bceef18bf26108a81587c5adee293914
- id: Subtitle-3Play YouTube id-SRT
  parent_uid: 6c01f00215566284e6dc0c87d3ed95a5
  title: Subtitle-3Play YouTube id-SRT-English - US
  type: Subtitle
  uid: 324fb9d85d81d9b4976fbc9f6c1c079b
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 6c01f00215566284e6dc0c87d3ed95a5
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 66fd34b9ac84a73444102df28004571a
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id1262009852
  parent_uid: 6c01f00215566284e6dc0c87d3ed95a5
  title: Video-iTunes U-MP4
  type: Video
  uid: 4e93cf43481b5828ec02784868a34f47
- id: Video-InternetArchive-MP4
  media_location: https://archive.org/download/MIT18.650F16/MIT18_650F16_lec19_300k.mp4
  parent_uid: 6c01f00215566284e6dc0c87d3ed95a5
  title: Video-Internet Archive-MP4
  type: Video
  uid: b33f114f8381c15da57745ae97c65853
inline_embed_id: 89961066lecture19video50502994
layout: video
order_index: null
parent_uid: 53cad402730669a650a46151cae8a9c8
related_resources_text: ''
short_url: lecture-19-video
technical_location: https://ocw.mit.edu/courses/mathematics/18-650-statistics-for-applications-fall-2016/lecture-videos/lecture-19-video
template_type: Tabbed
title: 'Lecture 19: Principal Component Analysis'
transcript: <p><span m="120">The</span> <span m="210">following</span> <span m="660">content</span>
  <span m="1140">is</span> <span m="1260">provided</span> <span m="1710">under</span>
  <span m="1950">a</span> <span m="2009">Creative</span> <span m="2460">Commons</span>
  <span m="2850">license.</span> <span m="3880">Your</span> <span m="3960">support</span>
  <span m="4440">will</span> <span m="4620">help</span> <span m="4860">MIT</span>
  <span m="5340">OpenCourseWare</span> <span m="6090">continue</span> <span m="6570">to</span>
  <span m="6720">offer</span> <span m="7050">high</span> <span m="7260">quality</span>
  <span m="7740">educational</span> <span m="8400">resources</span> <span m="8970">for</span>
  <span m="9120">free.</span> <span m="10180">To</span> <span m="10200">make</span>
  <span m="10380">a</span> <span m="10440">donation</span> <span m="11190">or</span>
  <span m="11370">to</span> <span m="11490">view</span> <span m="11700">additional</span>
  <span m="12120">materials</span> <span m="12720">from</span> <span m="12900">hundreds</span>
  <span m="13230">of</span> <span m="13350">MIT</span> <span m="13710">courses,</span>
  <span m="15010">visit</span> <span m="15210">MIT</span> <span m="15720">OpenCourseWare</span>
  <span m="16680">at ocw.mit.edu.</span></p><p><span m="74980">PHILIPPE RIGOLLET:</span>
  <span m="75085">--bunch</span> <span m="75190">of</span> <span m="75310">x's</span>
  <span m="75850">and</span> <span m="75970">a bunch of</span> <span m="77170">y's.</span>
  <span m="77500">The</span> <span m="77590">y's</span> <span m="77920">were</span>
  <span m="78430">univariate,</span> <span m="79150">just</span> <span m="79630">one</span>
  <span m="79900">real</span> <span m="80140">valued</span> <span m="80500">random</span>
  <span m="80740">variable.</span> <span m="81460">And</span> <span m="81580">the</span>
  <span m="81730">x's</span> <span m="82120">were</span> <span m="82300">vectors</span>
  <span m="82760">that</span> <span m="82870">described</span> <span m="83330">a</span>
  <span m="83380">bunch</span> <span m="83620">of</span> <span m="83710">attributes</span>
  <span m="84760">for</span> <span m="85090">each</span> <span m="85330">of</span>
  <span m="85450">our</span> <span m="85540">individuals</span> <span m="86140">or</span>
  <span m="86230">each</span> <span m="86380">of</span> <span m="86490">our</span>
  <span m="86530">observations.</span> <span m="87730">Let's</span> <span m="87910">assume</span>
  <span m="88210">now</span> <span m="88390">that</span> <span m="88510">we're</span>
  <span m="88660">given</span> <span m="88960">essentially</span> <span m="89410">only</span>
  <span m="89680">the</span> <span m="89810">x's.</span> <span m="90350">This</span>
  <span m="90730">is sometimes</span> <span m="91330">referred</span> <span m="91630">to</span>
  <span m="91810">as</span> <span m="92080">unsupervised</span> <span m="93430">learning.</span>
  <span m="93970">There</span> <span m="94050">is</span> <span m="94210">just</span>
  <span m="94450">the</span> <span m="94570">x's.</span> <span m="95920">Usually,</span>
  <span m="96370">supervision</span> <span m="96940">is</span> <span m="97030">done</span>
  <span m="97210">by</span> <span m="97780">the</span> <span m="97900">y's.</span></p><p><span
  m="98640">And</span> <span m="98770">so</span> <span m="98980">what</span> <span
  m="99190">you're</span> <span m="99310">trying</span> <span m="99550">to</span>
  <span m="99670">do</span> <span m="99820">is</span> <span m="99910">to</span> <span
  m="100030">make</span> <span m="100240">sense</span> <span m="100660">of</span>
  <span m="100780">this</span> <span m="100990">data.</span> <span m="101710">You're</span>
  <span m="101800">going</span> <span m="101920">to</span> <span m="101980">try</span>
  <span m="102220">to</span> <span m="102490">understand</span> <span m="103090">this</span>
  <span m="103240">data,</span> <span m="103690">represent</span> <span m="104500">this</span>
  <span m="104680">data,</span> <span m="105430">visualize</span> <span m="106060">this</span>
  <span m="106240">data,</span> <span m="107270">try</span> <span m="107350">to</span>
  <span m="107440">understand</span> <span m="107830">something,</span> <span m="108310">right?</span>
  <span m="108520">So,</span> <span m="109060">if</span> <span m="109180">I</span>
  <span m="109240">give</span> <span m="109480">you</span> <span m="110170">a</span>
  <span m="110400">d-dimensional</span> <span m="111130">random</span> <span m="111430">vectors,</span>
  <span m="112270">and</span> <span m="112360">you're</span> <span m="112480">going</span>
  <span m="112600">to</span> <span m="112660">have</span> <span m="112930">n</span>
  <span m="113080">independent</span> <span m="113620">copies</span> <span m="114070">of</span>
  <span m="114220">this</span> <span m="115030">individual--</span> <span m="115570">of</span>
  <span m="115900">this</span> <span m="116080">random</span> <span m="116320">vector,</span>
  <span m="117100">OK?</span></p><p><span m="117310">So</span> <span m="118090">you</span>
  <span m="118240">will</span> <span m="118420">see</span> <span m="118600">that</span>
  <span m="118930">I'm</span> <span m="119080">going</span> <span m="119230">to</span>
  <span m="119290">have--</span> <span m="119530">I'm going</span> <span m="120000">to</span>
  <span m="120100">very</span> <span m="120370">quickly</span> <span m="120760">run</span>
  <span m="120940">into</span> <span m="121240">some</span> <span m="121630">limitations</span>
  <span m="122200">about</span> <span m="122530">what</span> <span m="122740">I</span>
  <span m="122800">can</span> <span m="122950">actually</span> <span m="123250">draw</span>
  <span m="123520">on</span> <span m="123610">the</span> <span m="123730">board</span>
  <span m="124270">because</span> <span m="124420">I'm</span> <span m="124540">using</span>
  <span m="124880">[? boldface ?]</span> <span m="125450">here.</span> <span m="125980">I'm</span>
  <span m="126130">also</span> <span m="126370">going</span> <span m="126520">to</span>
  <span m="126580">use</span> <span m="126850">the</span> <span m="127090">blackboard</span>
  <span m="127600">[? boldface. ?]</span> <span m="128180">So</span> <span m="128800">it's</span>
  <span m="128889">going</span> <span m="129009">to</span> <span m="129070">be</span>
  <span m="129130">a</span> <span m="129160">bit</span> <span m="129280">difficult.</span>
  <span m="129820">So</span> <span m="131380">tell</span> <span m="131530">me</span>
  <span m="131680">if</span> <span m="131770">you're</span> <span m="131950">actually
  a</span> <span m="132310">little</span> <span m="134380">confused</span> <span m="134950">by</span>
  <span m="135190">what</span> <span m="135430">is</span> <span m="135550">a</span>
  <span m="135610">vector,</span> <span m="136000">what</span> <span m="136150">is</span>
  <span m="136270">a</span> <span m="136330">number,</span> <span m="136720">and</span>
  <span m="136870">what</span> <span m="137050">is</span> <span m="137170">a</span>
  <span m="137230">matrix.</span> <span m="137710">But</span> <span m="138280">we'll</span>
  <span m="138580">get</span> <span m="138790">there.</span></p><p><span m="139720">So</span>
  <span m="139840">I</span> <span m="139930">have</span> <span m="140220">X</span>
  <span m="140430">in</span> <span m="140570">Rd,</span> <span m="141190">and</span>
  <span m="141340">that's</span> <span m="141590">a</span> <span m="141700">random</span>
  <span m="142000">vector.</span> <span m="146230">And</span> <span m="146410">I</span>
  <span m="146500">have</span> <span m="146830">X1</span> <span m="148590">to</span>
  <span m="148770">Xn</span> <span m="149830">that</span> <span m="150010">are</span>
  <span m="150200">IID.</span> <span m="150650">They're</span> <span m="151010">independent</span>
  <span m="151480">copies</span> <span m="151840">of</span> <span m="151980">X.</span>
  <span m="157380">OK,</span> <span m="157635">so</span> <span m="157890">you</span>
  <span m="158010">can</span> <span m="158190">think</span> <span m="158370">of</span>
  <span m="158490">those</span> <span m="158640">as</span> <span m="158760">being--</span>
  <span m="160440">the</span> <span m="160590">realization</span> <span m="161100">of</span>
  <span m="161190">these</span> <span m="161370">guys</span> <span m="161640">are</span>
  <span m="161700">going</span> <span m="161850">to</span> <span m="161940">be</span>
  <span m="162140">a</span> <span m="162240">cloud</span> <span m="165090">of</span>
  <span m="165300">n</span> <span m="165570">points</span> <span m="170100">in</span>
  <span m="170280">R</span> <span m="170430">to</span> <span m="170600">the</span>
  <span m="170750">d.</span> <span m="171090">And</span> <span m="171210">we're</span>
  <span m="171330">going</span> <span m="171450">to</span> <span m="171540">think</span>
  <span m="171780">of</span> <span m="172010">d</span> <span m="172340">as</span>
  <span m="172530">being</span> <span m="172800">fairly</span> <span m="173220">large.</span>
  <span m="174210">And</span> <span m="174360">for</span> <span m="174540">this</span>
  <span m="174720">to</span> <span m="174870">start</span> <span m="175110">to</span>
  <span m="175230">make</span> <span m="175440">sense,</span> <span m="175710">we're</span>
  <span m="175800">going</span> <span m="175920">to</span> <span m="175980">think</span>
  <span m="176190">of</span> <span m="176340">d</span> <span m="176610">as</span>
  <span m="176760">being</span> <span m="177030">at</span> <span m="177150">least</span>
  <span m="177440">4,</span> <span m="178740">OK?</span></p><p><span m="179760">And</span>
  <span m="180240">meaning</span> <span m="180600">that</span> <span m="180840">you're</span>
  <span m="181050">going</span> <span m="181200">to</span> <span m="181260">have</span>
  <span m="181380">a</span> <span m="181440">hard</span> <span m="181620">time</span>
  <span m="181830">visualizing</span> <span m="182460">those</span> <span m="182670">things.</span>
  <span m="183480">If</span> <span m="183630">it</span> <span m="183720">was</span>
  <span m="184260">3</span> <span m="184620">or</span> <span m="184770">2,</span>
  <span m="185040">you</span> <span m="185190">would</span> <span m="185340">be</span>
  <span m="185490">able</span> <span m="185640">to</span> <span m="185790">draw</span>
  <span m="186000">these</span> <span m="186180">points.</span> <span m="186530">And</span>
  <span m="186750">that's</span> <span m="186990">pretty</span> <span m="187170">much</span>
  <span m="187440">as</span> <span m="187590">much</span> <span m="187800">sense</span>
  <span m="188040">you're</span> <span m="188160">going</span> <span m="188280">to
  be</span> <span m="188370">making</span> <span m="188840">about</span> <span m="189240">those</span>
  <span m="189420">guys,</span> <span m="189630">just</span> <span m="189810">looking</span>
  <span m="190080">at</span> <span m="190170">the</span> <span m="190320">[INAUDIBLE]</span></p><p><span
  m="192030">All</span> <span m="192090">right,</span> <span m="192270">so</span>
  <span m="193200">I'm</span> <span m="193410">going</span> <span m="193560">to</span>
  <span m="193630">write</span> <span m="193920">each</span> <span m="194190">of</span>
  <span m="194340">those</span> <span m="194610">X's,</span> <span m="196460">right?</span>
  <span m="196860">So</span> <span m="196980">this</span> <span m="197190">vector,</span>
  <span m="197520">X,</span> <span m="198300">has d</span> <span m="198480">coordinate.</span>
  <span m="200520">And</span> <span m="200670">I'm</span> <span m="200820">going</span>
  <span m="200970">to</span> <span m="201030">write</span> <span m="201300">them</span>
  <span m="201630">as</span> <span m="202050">X1,</span> <span m="204905">to</span>
  <span m="205330">Xd.</span> <span m="210730">And</span> <span m="212010">I'm</span>
  <span m="212100">going</span> <span m="212250">to</span> <span m="212310">stack</span>
  <span m="212730">them</span> <span m="212880">into a</span> <span m="213150">matrix,</span>
  <span m="213850">OK?</span> <span m="214780">So</span> <span m="214860">once</span>
  <span m="215100">I</span> <span m="215160">have</span> <span m="215340">those</span>
  <span m="215550">guys,</span> <span m="216780">I'm</span> <span m="216870">going</span>
  <span m="217020">to</span> <span m="217080">have</span> <span m="217350">a</span>
  <span m="217440">matrix.</span> <span m="218100">But</span> <span m="218310">here,</span>
  <span m="218550">I'm</span> <span m="218610">going</span> <span m="218730">to</span>
  <span m="218790">use</span> <span m="218940">the</span> <span m="219030">double</span>
  <span m="219330">bar.</span> <span m="220230">And</span> <span m="220350">it's</span>
  <span m="221280">X1</span> <span m="223860">transpose,</span> <span m="225750">Xn</span>
  <span m="226650">transpose.</span></p><p><span m="227880">So</span> <span m="227970">what</span>
  <span m="228090">it</span> <span m="228240">means</span> <span m="229830">is</span>
  <span m="229980">that</span> <span m="230130">the</span> <span m="230250">coordinates</span>
  <span m="230700">of</span> <span m="230820">this</span> <span m="230990">guy,</span>
  <span m="231250">of</span> <span m="231360">course,</span> <span m="231570">are</span>
  <span m="231690">X1,1.</span> <span m="233040">Here,</span> <span m="233370">I</span>
  <span m="233460">have--</span> <span m="234710">I'm</span> <span m="234980">of</span>
  <span m="235230">size d,</span> <span m="235670">so I</span> <span m="235850">have</span>
  <span m="236000">X1d.</span> <span m="237870">And</span> <span m="237990">here,</span>
  <span m="238230">I</span> <span m="238290">have</span> <span m="238530">Xn1.</span>
  <span m="241290">Xnd.</span> <span m="242940">And</span> <span m="243030">so</span>
  <span m="243210">the</span> <span m="243760">i-th,</span> <span m="244666">j-th--</span>
  <span m="246660">i-th</span> <span m="246840">row</span> <span m="247200">and</span>
  <span m="247360">j-th</span> <span m="247700">column</span> <span m="248590">is</span>
  <span m="248790">the</span> <span m="248880">matrix,</span> <span m="249420">Xij,</span>
  <span m="250110">right--</span> <span m="250950">is</span> <span m="251100">the</span>
  <span m="251190">entry,</span> <span m="251500">Xi</span> <span m="252190">to--</span>
  <span m="252490">sorry.</span> <span m="263540">OK,</span> <span m="264450">so</span>
  <span m="265110">each--</span> <span m="265890">so</span> <span m="266070">the</span>
  <span m="266250">rows</span> <span m="266670">here</span> <span m="267120">are</span>
  <span m="267360">the</span> <span m="267540">observations.</span> <span m="268230">And</span>
  <span m="268350">the</span> <span m="268440">columns</span> <span m="268950">are</span>
  <span m="269370">the</span> <span m="270210">covariance</span> <span m="270540">over</span>
  <span m="271170">attributes.</span> <span m="272040">OK?</span> <span m="272640">So</span>
  <span m="272730">this</span> <span m="272910">is</span> <span m="273060">an</span>
  <span m="273180">n</span> <span m="273450">by</span> <span m="273660">d</span> <span
  m="273790">matrix.</span></p><p><span m="279220">All right,</span> <span m="279710">this</span>
  <span m="279820">is</span> <span m="280000">really</span> <span m="280300">just</span>
  <span m="280510">some</span> <span m="280690">bookkeeping.</span> <span m="281320">How</span>
  <span m="281470">do</span> <span m="281560">we</span> <span m="281710">store</span>
  <span m="282280">this</span> <span m="282460">data</span> <span m="282850">somehow?</span>
  <span m="283840">And</span> <span m="284050">the</span> <span m="284200">fact</span>
  <span m="284410">that</span> <span m="284530">we</span> <span m="284620">use</span>
  <span m="284760">a</span> <span m="284830">matrix</span> <span m="285210">just</span>
  <span m="285430">like</span> <span m="285660">for</span> <span m="286300">regression</span>
  <span m="286810">is</span> <span m="286900">going</span> <span m="287050">to</span>
  <span m="287110">be</span> <span m="287170">convenient</span> <span m="287650">because</span>
  <span m="287800">we're</span> <span m="287880">going</span> <span m="288000">to</span>
  <span m="288060">able</span> <span m="288280">to</span> <span m="288400">talk</span>
  <span m="288580">about</span> <span m="288760">projections--</span> <span m="290050">going
  to</span> <span m="290180">be</span> <span m="290260">able</span> <span m="290470">to</span>
  <span m="290560">talk</span> <span m="290770">about</span> <span m="290950">things</span>
  <span m="291160">like</span> <span m="291340">this.</span></p><p><span m="293310">All</span>
  <span m="293370">right,</span> <span m="293550">so</span> <span m="293940">everything</span>
  <span m="294510">I'm</span> <span m="294630">going</span> <span m="294760">to</span>
  <span m="294840">say</span> <span m="295170">now</span> <span m="296310">is</span>
  <span m="296610">about</span> <span m="297450">variances</span> <span m="298230">or</span>
  <span m="298380">covariances</span> <span m="299190">of</span> <span m="299310">those</span>
  <span m="299550">things,</span> <span m="299910">which</span> <span m="300120">means</span>
  <span m="300330">that</span> <span m="300450">I</span> <span m="300540">need</span>
  <span m="300720">two</span> <span m="300930">moments,</span> <span m="301530">OK?</span>
  <span m="302130">If</span> <span m="302250">the</span> <span m="302340">variance</span>
  <span m="302700">does</span> <span m="302850">not</span> <span m="303030">exist,</span>
  <span m="303490">there's</span> <span m="303570">nothing</span> <span m="303870">I</span>
  <span m="303930">can</span> <span m="304080">say</span> <span m="304230">about</span>
  <span m="304440">this</span> <span m="304590">problem.</span> <span m="305320">So</span>
  <span m="305420">I'm</span> <span m="305520">going</span> <span m="305620">to</span>
  <span m="305720">assume</span> <span m="305820">that</span> <span m="306000">the</span>
  <span m="306210">variance</span> <span m="307110">exists.</span> <span m="307620">And</span>
  <span m="307770">one</span> <span m="307980">way</span> <span m="308100">to</span>
  <span m="308250">just</span> <span m="308460">put</span> <span m="308610">it</span>
  <span m="308810">to</span> <span m="308940">say</span> <span m="309090">that</span>
  <span m="309870">the</span> <span m="310080">two</span> <span m="310260">norm</span>
  <span m="310830">of</span> <span m="311040">those</span> <span m="311250">guys</span>
  <span m="312210">is</span> <span m="312390">finite,</span> <span m="312990">which</span>
  <span m="313200">is</span> <span m="313380">another</span> <span m="313710">way</span>
  <span m="313860">to</span> <span m="314010">say</span> <span m="314220">that</span>
  <span m="314550">each</span> <span m="314760">of</span> <span m="314880">them</span>
  <span m="315030">is</span> <span m="315180">finite.</span> <span m="315690">I</span>
  <span m="315750">mean,</span> <span m="316060">you</span> <span m="316160">can</span>
  <span m="316230">think</span> <span m="316440">of</span> <span m="316530">it</span>
  <span m="316650">the</span> <span m="316770">way</span> <span m="316890">you</span>
  <span m="316980">want.</span></p><p><span m="318210">All</span> <span m="318270">right,</span>
  <span m="318480">so</span> <span m="318840">now,</span> <span m="319110">the</span>
  <span m="319230">mean</span> <span m="320010">of</span> <span m="320280">X,</span>
  <span m="320790">right?</span> <span m="321000">So</span> <span m="321110">I</span>
  <span m="321150">have</span> <span m="321300">a</span> <span m="321360">random</span>
  <span m="321630">vector.</span> <span m="322530">So</span> <span m="322620">I</span>
  <span m="322680">can</span> <span m="322860">talk</span> <span m="323160">about</span>
  <span m="323430">the</span> <span m="323550">expectation</span> <span m="325170">of</span>
  <span m="325400">X.</span> <span m="326430">That's</span> <span m="326790">a</span>
  <span m="326910">vector</span> <span m="327330">that's</span> <span m="327600">in</span>
  <span m="327720">Rd.</span> <span m="329040">And</span> <span m="329190">that's</span>
  <span m="329370">just</span> <span m="329550">taking</span> <span m="329910">the</span>
  <span m="330030">expectation</span> <span m="330720">entrywise.</span> <span m="333850">Sorry.</span>
  <span m="342265">X1,</span> <span m="342880">Xd.</span></p><p><span m="345540">OK,</span>
  <span m="345780">so</span> <span m="346140">I</span> <span m="346230">should</span>
  <span m="346440">say it</span> <span m="346710">out</span> <span m="346890">loud.</span>
  <span m="349640">For</span> <span m="349920">this,</span> <span m="350390">the</span>
  <span m="350510">purpose</span> <span m="350900">of</span> <span m="351050">this</span>
  <span m="351290">class,</span> <span m="351890">I</span> <span m="352040">will</span>
  <span m="352340">denote</span> <span m="353330">by</span> <span m="353510">subscripts</span>
  <span m="354800">the</span> <span m="355130">indices</span> <span m="355700">that</span>
  <span m="355850">corresponds</span> <span m="356360">to</span> <span m="356510">observations.</span>
  <span m="357170">And</span> <span m="357260">superscripts,</span> <span m="359150">the</span>
  <span m="360290">indices</span> <span m="360740">that</span> <span m="360860">correspond</span>
  <span m="361260">to</span> <span m="362690">coordinates</span> <span m="363470">of</span>
  <span m="363650">a</span> <span m="363680">variable.</span> <span m="364280">And</span>
  <span m="364950">I</span> <span m="364990">think</span> <span m="365250">that's</span>
  <span m="365450">the</span> <span m="365570">same</span> <span m="366620">convention</span>
  <span m="367100">that</span> <span m="367220">we</span> <span m="367340">took</span>
  <span m="367550">for</span> <span m="367790">the</span> <span m="368510">regression</span>
  <span m="369020">case.</span> <span m="370860">Of</span> <span m="371000">course,</span>
  <span m="371180">you</span> <span m="371300">could</span> <span m="371450">use</span>
  <span m="371630">whatever</span> <span m="371900">you</span> <span m="371990">want.</span>
  <span m="372390">If</span> <span m="372490">you</span> <span m="372590">want</span>
  <span m="372650">to</span> <span m="372770">put</span> <span m="372950">commas,</span>
  <span m="373400">et cetera,</span> <span m="373680">it</span> <span m="373960">becomes</span>
  <span m="374240">just</span> <span m="374420">a</span> <span m="374480">bit</span>
  <span m="374630">more</span> <span m="374780">complicated.</span></p><p><span m="376072">All
  right,</span> <span m="376450">and</span> <span m="376560">so</span> <span m="377030">now,</span>
  <span m="377300">once</span> <span m="377570">I</span> <span m="377630">have</span>
  <span m="377840">this,</span> <span m="378070">so</span> <span m="378170">this</span>
  <span m="378440">tells</span> <span m="378770">me</span> <span m="379100">where</span>
  <span m="379430">my</span> <span m="379960">cloud</span> <span m="380230">of</span>
  <span m="380300">point</span> <span m="380630">is</span> <span m="380690">centered,</span>
  <span m="381170">right?</span> <span m="381380">So</span> <span m="381560">if</span>
  <span m="381710">I</span> <span m="381770">have</span> <span m="383110">a</span>
  <span m="383150">bunch</span> <span m="383480">of</span> <span m="383600">points--</span>
  <span m="384380">OK,</span> <span m="384650">so</span> <span m="385820">now</span>
  <span m="386030">I</span> <span m="386060">have</span> <span m="386210">a</span>
  <span m="386270">distribution</span> <span m="386900">on</span> <span m="387050">Rd,</span>
  <span m="387440">so</span> <span m="387770">maybe</span> <span m="388040">I</span>
  <span m="388130">should</span> <span m="388370">talk</span> <span m="388640">about</span>
  <span m="388910">this--</span> <span m="389990">I'll</span> <span m="390110">talk</span>
  <span m="390290">about</span> <span m="390590">this</span> <span m="391130">when</span>
  <span m="391340">we</span> <span m="391430">talk</span> <span m="391610">about</span>
  <span m="391820">the</span> <span m="391910">empirical</span> <span m="392330">version.</span>
  <span m="392960">But</span> <span m="393050">if</span> <span m="393170">you</span>
  <span m="393260">think</span> <span m="393470">that</span> <span m="393620">you</span>
  <span m="393740">have,</span> <span m="393950">say,</span> <span m="394130">a</span>
  <span m="394190">two-dimensional</span> <span m="394940">Gaussian</span> <span m="395330">random</span>
  <span m="395570">variable,</span> <span m="396680">then</span> <span m="396860">you</span>
  <span m="397010">have</span> <span m="397220">a</span> <span m="397340">center</span>
  <span m="397850">in</span> <span m="397970">two</span> <span m="398150">dimension,</span>
  <span m="398690">which</span> <span m="398930">is</span> <span m="399230">where</span>
  <span m="399970">it</span> <span m="400340">peaks,</span> <span m="400700">basically.</span>
  <span m="401610">And</span> <span m="401660">that's</span> <span m="401840">what</span>
  <span m="401960">we're</span> <span m="402080">talking</span> <span m="402350">about</span>
  <span m="402590">here.</span></p><p><span m="403280">But</span> <span m="403400">the
  other</span> <span m="403640">thing</span> <span m="403850">we</span> <span m="403910">want</span>
  <span m="404060">to</span> <span m="404150">know</span> <span m="404360">is</span>
  <span m="404540">how</span> <span m="405020">much</span> <span m="405200">does</span>
  <span m="405310">it</span> <span m="405440">spread</span> <span m="406340">in</span>
  <span m="406460">every</span> <span m="406670">direction,</span> <span m="407240">right?</span>
  <span m="407900">So</span> <span m="407960">in</span> <span m="408020">every</span>
  <span m="408230">direction</span> <span m="408680">of</span> <span m="408800">the</span>
  <span m="408890">two</span> <span m="409010">dimensional</span> <span m="409430">thing,</span>
  <span m="409670">I</span> <span m="409730">can</span> <span m="409900">then</span>
  <span m="410030">try</span> <span m="410240">to</span> <span m="410360">understand</span>
  <span m="410750">how</span> <span m="410840">much</span> <span m="411020">spread</span>
  <span m="411380">I'm</span> <span m="411500">getting.</span> <span m="412220">And</span>
  <span m="412310">the</span> <span m="412430">way</span> <span m="412520">you</span>
  <span m="412640">measure</span> <span m="412910">this</span> <span m="413120">is</span>
  <span m="413210">by</span> <span m="413360">using</span> <span m="413660">covariance,</span>
  <span m="414710">right?</span> <span m="414900">So</span> <span m="415010">the</span>
  <span m="415130">covariance</span> <span m="415580">matrix,</span> <span m="421070">sigma--</span>
  <span m="422150">that's</span> <span m="422630">a</span> <span m="422750">matrix</span>
  <span m="423560">which</span> <span m="423800">is</span> <span m="424000">d by</span>
  <span m="424395">d.</span> <span m="425900">And</span> <span m="426020">it</span>
  <span m="426180">records--</span> <span m="426830">in</span> <span m="427010">the</span>
  <span m="427140">j,</span> <span m="427420">k-th</span> <span m="427700">entry,</span>
  <span m="428150">it</span> <span m="428330">records</span> <span m="428900">the</span>
  <span m="428990">covariance</span> <span m="429530">between</span> <span m="429860">the</span>
  <span m="429980">j-th</span> <span m="430420">coordinate</span> <span m="430620">of
  X</span> <span m="431150">and</span> <span m="431300">the</span> <span m="431390">k-th</span>
  <span m="431550">coordinate</span> <span m="431980">of</span> <span m="432110">X,</span>
  <span m="432800">OK?</span></p><p><span m="433490">So</span> <span m="434060">with</span>
  <span m="434270">entries--</span> <span m="441300">OK,</span> <span m="441540">so</span>
  <span m="441690">I</span> <span m="441750">have</span> <span m="441930">sigma,</span>
  <span m="443050">which</span> <span m="443190">is</span> <span m="443700">sigma</span>
  <span m="444120">1,1,</span> <span m="445500">sigma</span> <span m="447540">dd,</span>
  <span m="449280">sigma</span> <span m="449730">1d,</span> <span m="450510">sigma</span>
  <span m="450910">d1.</span> <span m="454750">OK,</span> <span m="454960">and</span>
  <span m="455230">here</span> <span m="455420">I</span> <span m="455470">have</span>
  <span m="455650">sigma</span> <span m="456040">jk</span> <span m="457330">And</span>
  <span m="457450">sigma</span> <span m="457810">jk</span> <span m="459690">is</span>
  <span m="459940">just</span> <span m="460150">the</span> <span m="460270">covariance</span>
  <span m="462610">between</span> <span m="467110">Xj,</span> <span m="467860">the</span>
  <span m="467980">j-th</span> <span m="468340">coordinate</span> <span m="468930">and</span>
  <span m="469060">the</span> <span m="469180">k-th</span> <span m="469410">coordinate.</span>
  <span m="472160">OK?</span> <span m="473030">So</span> <span m="473210">in</span>
  <span m="473300">particular,</span> <span m="473555">it's</span> <span m="473810">symmetric</span>
  <span m="474320">because</span> <span m="474620">the</span> <span m="474710">covariance</span>
  <span m="475160">between</span> <span m="475430">Xj</span> <span m="475730">and</span>
  <span m="475820">Xk</span> <span m="476180">is</span> <span m="476270">the</span>
  <span m="476390">same</span> <span m="476630">as</span> <span m="476720">the</span>
  <span m="476820">covariance</span> <span m="477140">between</span> <span m="477410">Xk</span>
  <span m="477800">and</span> <span m="477890">Xj.</span> <span m="478280">I</span>
  <span m="478580">should</span> <span m="478790">not</span> <span m="479060">put</span>
  <span m="479270">those</span> <span m="480230">parentheses</span> <span m="480920">here.</span>
  <span m="481230">I</span> <span m="481340">do</span> <span m="481460">not</span>
  <span m="481610">use</span> <span m="481820">them</span> <span m="482000">in</span>
  <span m="482120">this,</span> <span m="483450">OK?</span></p><p><span m="485330">Just</span>
  <span m="485570">the</span> <span m="485630">covariance</span> <span m="486110">matrix.</span>
  <span m="486900">So</span> <span m="486930">that's</span> <span m="487100">just</span>
  <span m="487280">something</span> <span m="487580">that</span> <span m="487700">records</span>
  <span m="488090">everything.</span> <span m="489050">And</span> <span m="489140">so</span>
  <span m="489290">what's</span> <span m="489470">nice</span> <span m="489680">about</span>
  <span m="489830">the</span> <span m="489920">covariance</span> <span m="490220">matrix</span>
  <span m="490640">is</span> <span m="490760">that</span> <span m="490910">if</span>
  <span m="491050">I</span> <span m="491120">actually</span> <span m="491420">give</span>
  <span m="491600">you</span> <span m="491750">X</span> <span m="492010">as</span>
  <span m="492170">a</span> <span m="492230">vector,</span> <span m="493040">you</span>
  <span m="493160">actually</span> <span m="493520">can</span> <span m="494120">build</span>
  <span m="494460">the</span> <span m="494530">matrix</span> <span m="494960">just</span>
  <span m="495170">by</span> <span m="495380">looking</span> <span m="495740">at</span>
  <span m="496100">vectors</span> <span m="496640">times</span> <span m="497270">vectors</span>
  <span m="497600">transpose,</span> <span m="498140">rather</span> <span m="498420">than</span>
  <span m="498530">actually</span> <span m="499250">thinking</span> <span m="499550">about</span>
  <span m="499850">building</span> <span m="500210">it</span> <span m="500360">coordinate</span>
  <span m="500860">by</span> <span m="501020">coordinate.</span> <span m="501940">So</span>
  <span m="502010">for</span> <span m="502130">example,</span> <span m="502590">if</span>
  <span m="502610">you're</span> <span m="502700">used</span> <span m="502910">to</span>
  <span m="503000">using</span> <span m="503330">MATLAB,</span> <span m="503840">that's</span>
  <span m="504020">the</span> <span m="504140">way</span> <span m="504290">you</span>
  <span m="504380">want</span> <span m="504560">to</span> <span m="504620">build</span>
  <span m="504800">a</span> <span m="504850">covariance</span> <span m="505190">matrix</span>
  <span m="505550">because</span> <span m="506150">MATLAB</span> <span m="506540">is</span>
  <span m="506660">good</span> <span m="507605">at</span> <span m="508550">manipulating</span>
  <span m="509210">vectors</span> <span m="509600">and</span> <span m="509690">matrices</span>
  <span m="510230">rather</span> <span m="510470">than</span> <span m="510620">just</span>
  <span m="510920">entering</span> <span m="511290">it</span> <span m="511610">entry</span>
  <span m="511910">by</span> <span m="512059">entry.</span></p><p><span m="513049">OK,</span>
  <span m="513230">so,</span> <span m="514610">right?</span> <span m="514820">So,</span>
  <span m="515000">what</span> <span m="515179">is</span> <span m="515330">the</span>
  <span m="515419">covariance</span> <span m="517220">between</span> <span m="517490">Xj</span>
  <span m="520909">and</span> <span m="521059">Xk?</span> <span m="522590">Well</span>
  <span m="522740">by</span> <span m="522919">definition,</span> <span m="523549">it's</span>
  <span m="523669">the</span> <span m="523789">expectation</span> <span m="525080">of</span>
  <span m="525340">Xj</span> <span m="529250">and</span> <span m="529470">Xk</span>
  <span m="531360">minus</span> <span m="532050">the</span> <span m="532240">expectation</span>
  <span m="532890">of</span> <span m="533010">Xj</span> <span m="535490">times</span>
  <span m="535910">the</span> <span m="536030">expectation</span> <span m="536720">of</span>
  <span m="536810">Xk,</span> <span m="541390">right?</span> <span m="541830">That's</span>
  <span m="542040">the</span> <span m="542130">definition</span> <span m="542670">of</span>
  <span m="542760">the</span> <span m="543010">covariance.</span> <span m="543330">I</span>
  <span m="543780">hope</span> <span m="543990">everybody's</span> <span m="544350">seeing</span>
  <span m="544620">that.</span></p><p><span m="545770">And</span> <span m="545870">so,</span>
  <span m="546480">in</span> <span m="546600">particular,</span> <span m="547380">I</span>
  <span m="547470">can</span> <span m="547650">actually</span> <span m="548280">see</span>
  <span m="548580">that</span> <span m="548760">this</span> <span m="549000">thing</span>
  <span m="549240">can</span> <span m="549420">be</span> <span m="549570">written</span>
  <span m="549990">as--</span> <span m="550620">sigma</span> <span m="551080">can</span>
  <span m="551290">now</span> <span m="551460">be</span> <span m="551610">written</span>
  <span m="552090">as</span> <span m="552750">the</span> <span m="552840">expectation</span>
  <span m="554340">of</span> <span m="554610">XX</span> <span m="555180">transpose</span>
  <span m="557220">minus</span> <span m="558200">the</span> <span m="558300">expectation</span>
  <span m="558960">of</span> <span m="559150">X</span> <span m="561040">times</span>
  <span m="561340">the</span> <span m="561400">expectation</span> <span m="562060">of</span>
  <span m="562180">X</span> <span m="562360">transpose.</span></p><p><span m="565660">Why?</span>
  <span m="566500">Well,</span> <span m="566680">let's</span> <span m="566920">look</span>
  <span m="567100">at</span> <span m="567190">the</span> <span m="567490">jk-th</span>
  <span m="568060">coefficient</span> <span m="568660">of</span> <span m="568780">this</span>
  <span m="568990">guy,</span> <span m="569230">right?</span> <span m="569470">So</span>
  <span m="570280">here,</span> <span m="570490">if</span> <span m="570620">I</span>
  <span m="570700">look</span> <span m="570940">at</span> <span m="571060">the</span>
  <span m="571210">jk-th</span> <span m="571810">coefficient,</span> <span m="574990">I</span>
  <span m="575110">see</span> <span m="575350">what?</span> <span m="575650">Well,</span>
  <span m="575920">I</span> <span m="576010">see</span> <span m="576250">that</span>
  <span m="576490">it's</span> <span m="576790">the</span> <span m="576940">expectation</span>
  <span m="578980">of</span> <span m="579280">XX</span> <span m="582140">transpose</span>
  <span m="583040">jk,</span> <span m="586100">which</span> <span m="586310">is</span>
  <span m="586460">equal</span> <span m="586790">to</span> <span m="587640">the</span>
  <span m="587750">expectation</span> <span m="588940">of</span> <span m="589220">XX</span>
  <span m="590840">transpose</span> <span m="591490">jk.</span> <span m="593920">And</span>
  <span m="594070">what</span> <span m="594610">are</span> <span m="594700">the</span>
  <span m="594880">entries</span> <span m="595390">of</span> <span m="595600">XX</span>
  <span m="595990">transpose?</span> <span m="596570">Well,</span> <span m="596830">they're</span>
  <span m="597010">of</span> <span m="597100">the</span> <span m="597220">form,</span>
  <span m="598060">Xj</span> <span m="598560">times</span> <span m="598840">Xk</span>
  <span m="599170">exactly.</span> <span m="600130">So</span> <span m="600220">this</span>
  <span m="600400">is</span> <span m="600490">actually</span> <span m="600820">equal</span>
  <span m="601180">to</span> <span m="601330">the</span> <span m="601450">expectation</span>
  <span m="602140">of</span> <span m="602230">Xj</span> <span m="602570">times</span>
  <span m="602820">Xk.</span></p><p><span m="609060">And</span> <span m="609240">this</span>
  <span m="609450">is</span> <span m="609600">actually</span> <span m="610200">not</span>
  <span m="610440">the</span> <span m="610560">way</span> <span m="610710">I</span>
  <span m="610770">want</span> <span m="610920">to</span> <span m="610980">write</span>
  <span m="611160">it.</span> <span m="611250">I want to</span> <span m="611330">write</span>
  <span m="611460">it--</span> <span m="615530">OK?</span> <span m="616590">Is</span>
  <span m="616610">that</span> <span m="616730">clear?</span> <span m="617590">That</span>
  <span m="617750">when</span> <span m="617910">I</span> <span m="617990">have</span>
  <span m="618140">a</span> <span m="618200">rank</span> <span m="618470">1</span>
  <span m="618650">matrix</span> <span m="619040">of</span> <span m="619130">this</span>
  <span m="619310">form,</span> <span m="619710">XX</span> <span m="619970">transpose,</span>
  <span m="620420">the</span> <span m="620510">entries are</span> <span m="620930">of</span>
  <span m="621050">this</span> <span m="621230">form,</span> <span m="621440">right?</span>
  <span m="621950">Because</span> <span m="622220">if</span> <span m="622400">I</span>
  <span m="622520">take--</span> <span m="623520">for</span> <span m="623540">example,</span>
  <span m="624200">think</span> <span m="624440">about</span> <span m="625250">x,</span>
  <span m="626215">y,</span> <span m="627185">z,</span> <span m="628640">and</span>
  <span m="628760">then I</span> <span m="628970">multiply</span> <span m="629510">by</span>
  <span m="629660">x,</span> <span m="630535">y,</span> <span m="631445">z.</span>
  <span m="632810">What</span> <span m="632900">I'm</span> <span m="633020">getting</span>
  <span m="633350">here</span> <span m="633590">is</span> <span m="633980">x--</span>
  <span m="636380">maybe</span> <span m="636650">I</span> <span m="636720">should</span>
  <span m="636900">actually</span> <span m="637230">use</span> <span m="637470">indices</span>
  <span m="637950">here.</span></p><p><span m="640350">x1,</span> <span m="640860">x2,</span>
  <span m="641620">x3.</span> <span m="642735">x1,</span> <span m="643050">x2,</span>
  <span m="643960">x3.</span> <span m="644750">The</span> <span m="644870">entries</span>
  <span m="645270">are</span> <span m="645360">x1x1,</span> <span m="646490">x1x2,</span>
  <span m="648330">x1x3;</span> <span m="650200">x2x1,</span> <span m="652005">x2x2,</span>
  <span m="653480">x2x3;</span> <span m="655335">x3x1,</span> <span m="657018">x3x2,</span>
  <span m="660045">x3x3,</span> <span m="663390">OK?</span> <span m="664770">So</span>
  <span m="664980">indeed,</span> <span m="665560">this</span> <span m="665700">is</span>
  <span m="665820">exactly</span> <span m="666270">of</span> <span m="666390">the</span>
  <span m="666510">form</span> <span m="666810">if</span> <span m="666930">you</span>
  <span m="667020">look</span> <span m="667200">at</span> <span m="667320">jk,</span>
  <span m="668340">you</span> <span m="668430">get</span> <span m="668580">exactly</span>
  <span m="669210">Xj</span> <span m="669690">times</span> <span m="669990">Xk,</span>
  <span m="671080">OK?</span> <span m="672566">So</span> <span m="673010">that's</span>
  <span m="673220">the</span> <span m="673340">beauty</span> <span m="673730">of</span>
  <span m="674000">those</span> <span m="674690">matrices.</span></p><p><span m="675685">So</span>
  <span m="676790">now,</span> <span m="677030">once</span> <span m="677300">I</span>
  <span m="677390">have</span> <span m="677570">this,</span> <span m="677780">I</span>
  <span m="677840">can</span> <span m="678020">do</span> <span m="678140">exactly</span>
  <span m="678560">the</span> <span m="678680">same</span> <span m="678920">thing,</span>
  <span m="679380">except</span> <span m="679580">that</span> <span m="679790">here,</span>
  <span m="680660">if</span> <span m="680810">I</span> <span m="680930">take</span>
  <span m="681200">the</span> <span m="681340">jk-th</span> <span m="681780">entry,</span>
  <span m="683480">I</span> <span m="683570">will</span> <span m="683840">get</span>
  <span m="684080">exactly</span> <span m="684470">the</span> <span m="684530">same</span>
  <span m="684740">thing,</span> <span m="685050">except</span> <span m="685190">that</span>
  <span m="685340">it's</span> <span m="685490">not</span> <span m="685700">going</span>
  <span m="685850">to</span> <span m="685910">be</span> <span m="686510">the</span>
  <span m="686690">expectation</span> <span m="687200">of</span> <span m="687290">the</span>
  <span m="687350">product,</span> <span m="687710">but</span> <span m="687800">the</span>
  <span m="687860">product</span> <span m="688220">of</span> <span m="688340">the</span>
  <span m="688400">expectation,</span> <span m="689060">right?</span> <span m="689780">So</span>
  <span m="689930">I</span> <span m="689990">get</span> <span m="690230">that</span>
  <span m="690400">the</span> <span m="690520">jk-th</span> <span m="690960">entry</span>
  <span m="692110">of</span> <span m="692360">E of X,</span> <span m="693660">E</span>
  <span m="693925">of</span> <span m="694190">X</span> <span m="694370">transpose,</span>
  <span m="696810">is</span> <span m="697100">just</span> <span m="698150">the</span>
  <span m="698270">j-th</span> <span m="698750">entry</span> <span m="699230">of</span>
  <span m="699380">E of</span> <span m="699620">X</span> <span m="701090">times</span>
  <span m="701480">the</span> <span m="701600">k-th</span> <span m="701900">entry</span>
  <span m="702220">of</span> <span m="702310">E of</span> <span m="702500">X.</span></p><p><span
  m="708310">So</span> <span m="708700">if</span> <span m="708850">I</span> <span
  m="708950">put</span> <span m="709180">those</span> <span m="709420">two</span>
  <span m="709570">together,</span> <span m="711490">it's</span> <span m="711640">actually</span>
  <span m="712000">telling</span> <span m="712360">me</span> <span m="712540">that</span>
  <span m="712690">if</span> <span m="712870">I</span> <span m="712960">look</span>
  <span m="713170">at</span> <span m="713290">the</span> <span m="713470">j,</span>
  <span m="713725">k-th</span> <span m="715670">entry</span> <span m="716090">of</span>
  <span m="716210">sigma,</span> <span m="716990">which</span> <span m="717380">I</span>
  <span m="717510">called</span> <span m="717890">little</span> <span m="718160">sigma</span>
  <span m="718610">jk,</span> <span m="719500">then</span> <span m="719690">this</span>
  <span m="719930">is</span> <span m="720050">actually</span> <span m="720500">equal</span>
  <span m="720890">to</span> <span m="721070">what?</span> <span m="721340">It's</span>
  <span m="721520">equal</span> <span m="721820">to</span> <span m="721970">the</span>
  <span m="722120">first</span> <span m="722450">term</span> <span m="722660">minus</span>
  <span m="723020">the</span> <span m="723140">second</span> <span m="723470">term.</span>
  <span m="724170">The</span> <span m="724270">first</span> <span m="724460">term</span>
  <span m="727630">is the</span> <span m="728060">expectation</span> <span m="728720">of</span>
  <span m="728840">Xj,</span> <span m="730336">Xk</span> <span m="731420">minus</span>
  <span m="731695">the</span> <span m="731970">expectation</span> <span m="733670">of</span>
  <span m="733850">Xj,</span> <span m="734706">expectation</span> <span m="735202">of</span>
  <span m="735698">Xk,</span> <span m="738680">which--</span> <span m="739200">oh,</span>
  <span m="739370">by</span> <span m="739490">the</span> <span m="739580">way,</span>
  <span m="739800">I</span> <span m="739900">forgot</span> <span m="740000">to</span>
  <span m="740120">say</span> <span m="740330">this</span> <span m="740510">is</span>
  <span m="740600">actually</span> <span m="740900">equal</span> <span m="741260">to</span>
  <span m="741380">the</span> <span m="741500">expectation</span> <span m="742160">of</span>
  <span m="742250">Xj</span> <span m="744620">times</span> <span m="744890">the</span>
  <span m="744950">expectation</span> <span m="745520">of</span> <span m="745610">Xk</span>
  <span m="746030">because</span> <span m="746300">that's</span> <span m="746570">just</span>
  <span m="746920">the</span> <span m="747020">definition</span> <span m="747530">of</span>
  <span m="747620">the</span> <span m="747710">expectation</span> <span m="748230">of</span>
  <span m="748290">random</span> <span m="748520">vectors.</span> <span m="748900">So</span>
  <span m="749090">my</span> <span m="749270">j and</span> <span m="749540">my k</span>
  <span m="749860">are</span> <span m="749970">now</span> <span m="750110">inside.</span>
  <span m="751460">And</span> <span m="751580">that's</span> <span m="751820">by</span>
  <span m="751970">definition</span> <span m="752690">the</span> <span m="752780">covariance</span>
  <span m="754400">between Xj</span> <span m="754860">and Xk,</span> <span m="757175">OK?</span></p><p><span
  m="759550">So</span> <span m="759700">just</span> <span m="760720">if</span> <span
  m="760870">you've</span> <span m="761110">seen</span> <span m="761440">those</span>
  <span m="761770">manipulations</span> <span m="762490">between</span> <span m="762760">vectors,</span>
  <span m="763360">hopefully</span> <span m="763780">you're</span> <span m="763930">bored</span>
  <span m="764200">out</span> <span m="764320">of</span> <span m="764440">your</span>
  <span m="764560">mind.</span> <span m="765400">And</span> <span m="765550">if</span>
  <span m="765700">you</span> <span m="765820">have</span> <span m="766030">not,</span>
  <span m="767020">then</span> <span m="767170">that's</span> <span m="767320">something</span>
  <span m="767800">you</span> <span m="768100">just</span> <span m="769390">need</span>
  <span m="769540">to</span> <span m="769660">get</span> <span m="769810">comfortable</span>
  <span m="770290">with,</span> <span m="770840">right?</span> <span m="771010">So</span>
  <span m="771460">one</span> <span m="771670">thing</span> <span m="771850">that's</span>
  <span m="771970">going</span> <span m="772120">to</span> <span m="772180">be</span>
  <span m="772270">useful</span> <span m="772660">is</span> <span m="772780">to</span>
  <span m="773440">know</span> <span m="773650">very</span> <span m="773950">quickly</span>
  <span m="775420">what's</span> <span m="775750">called</span> <span m="775930">the</span>
  <span m="776050">outer</span> <span m="776290">product</span> <span m="776710">of</span>
  <span m="776800">a</span> <span m="776860">vector</span> <span m="777160">with</span>
  <span m="777340">itself,</span> <span m="777770">which</span> <span m="777850">is</span>
  <span m="777970">the</span> <span m="778150">vector</span> <span m="778540">of</span>
  <span m="778610">times</span> <span m="778860">the</span> <span m="778930">vector</span>
  <span m="779230">transpose,</span> <span m="779960">what</span> <span m="780260">the</span>
  <span m="780370">entries</span> <span m="780670">of</span> <span m="780790">these</span>
  <span m="780930">things</span> <span m="781180">are.</span> <span m="781330">And</span>
  <span m="781480">that's</span> <span m="781660">what</span> <span m="781840">we've</span>
  <span m="782020">been</span> <span m="782170">using</span> <span m="783070">on</span>
  <span m="783540">this</span> <span m="783670">second</span> <span m="784350">set</span>
  <span m="784560">of</span> <span m="784620">boards.</span></p><p><span m="786510">OK,</span>
  <span m="786730">so</span> <span m="786940">everybody</span> <span m="787300">agrees</span>
  <span m="787630">now</span> <span m="787870">that</span> <span m="788050">we've</span>
  <span m="788290">sort</span> <span m="788530">of</span> <span m="788950">showed</span>
  <span m="789370">that</span> <span m="790570">the</span> <span m="790720">covariance</span>
  <span m="791230">matrix</span> <span m="791650">can</span> <span m="791860">be</span>
  <span m="791980">written</span> <span m="792340">in</span> <span m="792490">this</span>
  <span m="793180">vector</span> <span m="793570">form.</span> <span m="794290">So</span>
  <span m="794950">expectation</span> <span m="795640">of</span> <span m="795790">XX</span>
  <span m="796180">transpose</span> <span m="796630">minus</span> <span m="796930">expectation</span>
  <span m="797500">of</span> <span m="797590">X, expectation</span> <span m="797935">of</span>
  <span m="798280">X</span> <span m="798370">transpose.</span></p><p><span m="802264">OK,</span>
  <span m="803740">just</span> <span m="804250">like</span> <span m="804550">the</span>
  <span m="804670">covariance</span> <span m="805300">can</span> <span m="805510">be</span>
  <span m="805660">written</span> <span m="807430">in</span> <span m="807580">two</span>
  <span m="807790">ways,</span> <span m="808060">right</span> <span m="808330">we</span>
  <span m="808450">know</span> <span m="808630">that</span> <span m="808780">the</span>
  <span m="808870">covariance</span> <span m="809590">can</span> <span m="809770">also</span>
  <span m="810070">be</span> <span m="810220">written</span> <span m="810670">as</span>
  <span m="811420">the</span> <span m="811510">expectation</span> <span m="812980">of</span>
  <span m="813260">Xj</span> <span m="815110">minus</span> <span m="815530">expectation</span>
  <span m="816190">of</span> <span m="816310">Xj</span> <span m="819460">times</span>
  <span m="819880">Xk</span> <span m="821330">minus</span> <span m="821770">expectation</span>
  <span m="822430">of</span> <span m="822560">Xk,</span> <span m="825022">right?</span></p><p><span
  m="825500">That's</span> <span m="825710">the--</span> <span m="828510">sometimes,</span>
  <span m="828900">this</span> <span m="829080">is</span> <span m="829170">the</span>
  <span m="829290">original</span> <span m="829740">definition</span> <span m="830220">of</span>
  <span m="830310">covariance.</span> <span m="830850">This</span> <span m="831060">is</span>
  <span m="831150">the</span> <span m="831270">second</span> <span m="831600">definition</span>
  <span m="832050">of</span> <span m="832140">covariance.</span> <span m="832490">Just</span>
  <span m="832680">like</span> <span m="832860">you</span> <span m="832950">have</span>
  <span m="833080">the</span> <span m="833190">variance</span> <span m="833520">which</span>
  <span m="833700">is</span> <span m="833820">the</span> <span m="833940">expectation</span>
  <span m="834600">of</span> <span m="834780">the</span> <span m="835440">square</span>
  <span m="836040">of</span> <span m="836280">X</span> <span m="836490">minus</span>
  <span m="836730">c</span> <span m="836900">of</span> <span m="837030">X,</span>
  <span m="837240">or</span> <span m="837570">the</span> <span m="837660">expectation</span>
  <span m="838140">X</span> <span m="838530">squared</span> <span m="838770">minus</span>
  <span m="839160">the</span> <span m="839250">expectation</span> <span m="839700">of</span>
  <span m="839820">X</span> <span m="840390">squared.</span> <span m="841160">It's</span>
  <span m="841650">the</span> <span m="841770">same</span> <span m="841980">thing</span>
  <span m="842190">for</span> <span m="842350">covariance.</span></p><p><span m="843420">And</span>
  <span m="843540">you</span> <span m="843630">can</span> <span m="843750">actually</span>
  <span m="844140">see</span> <span m="844440">this</span> <span m="849690">in</span>
  <span m="849870">terms</span> <span m="850080">of</span> <span m="850170">vectors,</span>
  <span m="850590">right?</span> <span m="851190">So</span> <span m="851340">this</span>
  <span m="851610">actually</span> <span m="852000">implies</span> <span m="852420">that</span>
  <span m="852540">you</span> <span m="852630">can</span> <span m="852780">also</span>
  <span m="853080">rewrite</span> <span m="853470">sigma</span> <span m="854270">as</span>
  <span m="854490">the</span> <span m="854610">expectation</span> <span m="856440">of</span>
  <span m="857550">X</span> <span m="858060">minus</span> <span m="858660">expectation</span>
  <span m="859320">of</span> <span m="859500">X</span> <span m="861780">times</span>
  <span m="862200">the</span> <span m="862320">same</span> <span m="862560">thing</span>
  <span m="862800">transpose.</span></p><p><span m="872410">Right?</span> <span m="872690">And</span>
  <span m="872870">the</span> <span m="872960">reason</span> <span m="873320">is</span>
  <span m="873440">because</span> <span m="873770">if</span> <span m="873890">you</span>
  <span m="874010">just</span> <span m="874250">distribute</span> <span m="874760">those</span>
  <span m="874970">guys,</span> <span m="875950">this</span> <span m="876270">is</span>
  <span m="876500">just</span> <span m="876710">the</span> <span m="876800">expectation</span>
  <span m="877580">of</span> <span m="879140">XX</span> <span m="879560">transpose</span>
  <span m="883760">minus</span> <span m="884240">X, expectation</span> <span m="885050">of</span>
  <span m="885170">X</span> <span m="885320">transpose</span> <span m="893120">minus</span>
  <span m="894200">expectation</span> <span m="894800">of</span> <span m="894920">XX</span>
  <span m="897200">transpose.</span> <span m="899750">And</span> <span m="899870">then</span>
  <span m="900020">I have</span> <span m="900320">plus</span> <span m="901560">expectation</span>
  <span m="902240">of</span> <span m="902330">X,</span> <span m="903608">expectation</span>
  <span m="904460">of</span> <span m="904550">X</span> <span m="904700">transpose.</span></p><p><span
  m="909930">Now,</span> <span m="910320">things</span> <span m="910620">could</span>
  <span m="910860">go</span> <span m="911100">wrong</span> <span m="911580">because</span>
  <span m="912390">the</span> <span m="912480">main</span> <span m="912660">difference</span>
  <span m="913110">between</span> <span m="913440">matrices</span> <span m="915470">slash</span>
  <span m="915930">vectors</span> <span m="916620">and</span> <span m="917850">numbers</span>
  <span m="918510">is</span> <span m="918660">that</span> <span m="919530">multiplication</span>
  <span m="920250">does</span> <span m="920430">not</span> <span m="920610">commute,</span>
  <span m="921090">right?</span> <span m="921930">So</span> <span m="922020">in</span>
  <span m="922110">particular,</span> <span m="922950">those</span> <span m="923190">two</span>
  <span m="923340">things</span> <span m="923670">are</span> <span m="923760">not</span>
  <span m="924000">the</span> <span m="924120">same</span> <span m="924360">thing.</span>
  <span m="925920">And</span> <span m="926020">so</span> <span m="926090">that's</span>
  <span m="926450">the</span> <span m="926510">main</span> <span m="926720">difference</span>
  <span m="927080">that</span> <span m="927200">we</span> <span m="927350">have</span>
  <span m="927500">before,</span> <span m="927860">but</span> <span m="928010">it</span>
  <span m="928100">actually</span> <span m="928940">does</span> <span m="929120">not</span>
  <span m="929300">matter</span> <span m="929750">for our</span> <span m="930050">problem.</span>
  <span m="930430">It's</span> <span m="930590">because</span> <span m="931310">what's</span>
  <span m="931460">happening</span> <span m="931730">is</span> <span m="931850">that</span>
  <span m="931970">if</span> <span m="932060">when</span> <span m="932210">I</span>
  <span m="932290">take</span> <span m="932510">the</span> <span m="932600">expectation</span>
  <span m="933230">of</span> <span m="933350">this</span> <span m="933560">guy,</span>
  <span m="934820">then</span> <span m="934970">it's</span> <span m="935090">actually</span>
  <span m="935360">the</span> <span m="935480">same</span> <span m="935750">as</span>
  <span m="935870">the</span> <span m="935930">expectation</span> <span m="936500">of</span>
  <span m="936620">this</span> <span m="936770">guy,</span> <span m="938330">OK?</span></p><p><span
  m="938940">And</span> <span m="939180">so</span> <span m="941650">just</span> <span
  m="941860">because</span> <span m="942190">the</span> <span m="942400">expectation</span>
  <span m="943000">is</span> <span m="943090">linear--</span> <span m="948230">so
  what</span> <span m="948470">we</span> <span m="948630">have</span> <span m="948930">is</span>
  <span m="949050">that</span> <span m="949260">sigma</span> <span m="950360">now</span>
  <span m="950550">becomes</span> <span m="951060">equal</span> <span m="951390">to</span>
  <span m="951540">the</span> <span m="951660">expectation</span> <span m="953430">of</span>
  <span m="953670">XX</span> <span m="954130">transpose</span> <span m="955560">minus</span>
  <span m="956070">the</span> <span m="956190">expectation</span> <span m="956820">of</span>
  <span m="956940">X,</span> <span m="958254">expectation</span> <span m="959130">of</span>
  <span m="959220">X</span> <span m="959490">transpose</span> <span m="961230">minus</span>
  <span m="961650">expectation</span> <span m="962280">of</span> <span m="962340">X,</span>
  <span m="963170">expectation</span> <span m="964210">of</span> <span m="964450">X</span>
  <span m="964690">transpose.</span> <span m="967110">And</span> <span m="967260">then
  I</span> <span m="967590">have--</span> <span m="970030">well,</span> <span m="970540">really,</span>
  <span m="970900">what</span> <span m="971010">I</span> <span m="971080">have</span>
  <span m="971290">is</span> <span m="971410">this</span> <span m="971590">guy.</span>
  <span m="974070">And</span> <span m="974220">then</span> <span m="974400">I</span>
  <span m="974460">have</span> <span m="974910">plus</span> <span m="975320">the</span>
  <span m="975370">expectation</span> <span m="975990">of</span> <span m="976110">X,</span>
  <span m="977930">expectation</span> <span m="978840">of</span> <span m="978930">X
  transpose.</span></p><p><span m="983970">And</span> <span m="984660">now,</span>
  <span m="985020">those</span> <span m="985380">three</span> <span m="985680">things</span>
  <span m="986070">are</span> <span m="986160">actually</span> <span m="986610">equal</span>
  <span m="986910">to</span> <span m="987030">each</span> <span m="987210">other</span>
  <span m="988570">just</span> <span m="988830">because</span> <span m="989190">the</span>
  <span m="989250">expectation</span> <span m="989820">of</span> <span m="989940">X</span>
  <span m="990260">transpose</span> <span m="990700">is</span> <span m="990900">the</span>
  <span m="991020">same</span> <span m="991290">as</span> <span m="991410">the</span>
  <span m="991500">expectation</span> <span m="992100">of</span> <span m="992220">X</span>
  <span m="992370">transpose.</span> <span m="994300">And</span> <span m="994320">so</span>
  <span m="994470">what</span> <span m="994610">I'm</span> <span m="994740">left</span>
  <span m="994950">with</span> <span m="995130">is</span> <span m="995280">just</span>
  <span m="995520">the</span> <span m="995640">expectation</span> <span m="996990">of</span>
  <span m="997090">XX</span> <span m="997660">transpose</span> <span m="998990">minus</span>
  <span m="1000060">the</span> <span m="1000250">expectation</span> <span m="1000800">of</span>
  <span m="1000920">X,</span> <span m="1004364">expectation</span> <span m="1005350">of</span>
  <span m="1005460">X transpose,</span> <span m="1007293">OK?</span></p><p><span m="1009650">So</span>
  <span m="1010260">same</span> <span m="1010650">thing</span> <span m="1010860">that's</span>
  <span m="1011070">happening</span> <span m="1011460">when</span> <span m="1011610">you</span>
  <span m="1011760">want</span> <span m="1011970">to</span> <span m="1012060">prove</span>
  <span m="1012420">that</span> <span m="1012600">you</span> <span m="1012690">can</span>
  <span m="1012900">write</span> <span m="1013110">the</span> <span m="1013200">covariance</span>
  <span m="1014220">either</span> <span m="1014520">this</span> <span m="1014820">way</span>
  <span m="1015450">or</span> <span m="1015600">that</span> <span m="1015870">way.</span>
  <span m="1017760">The</span> <span m="1017880">same</span> <span m="1018030">thing</span>
  <span m="1018240">happens</span> <span m="1018570">for</span> <span m="1018690">matrices,</span>
  <span m="1019900">or</span> <span m="1020250">for</span> <span m="1020420">vectors,</span>
  <span m="1020980">right,</span> <span m="1021460">or a</span> <span m="1021620">covariance</span>
  <span m="1022010">matrix.</span> <span m="1022340">They</span> <span m="1022430">go</span>
  <span m="1022620">together.</span> <span m="1024609">Is</span> <span m="1024710">there</span>
  <span m="1024720">any</span> <span m="1024869">questions</span> <span m="1025240">so</span>
  <span m="1025410">far?</span> <span m="1025920">And</span> <span m="1026010">if</span>
  <span m="1026130">you</span> <span m="1026250">have</span> <span m="1026460">some,</span>
  <span m="1026700">please</span> <span m="1027960">tell</span> <span m="1028170">me,</span>
  <span m="1028319">because</span> <span m="1028710">I</span> <span m="1028800">want</span>
  <span m="1028920">to--</span> <span m="1029460">I</span> <span m="1029819">don't</span>
  <span m="1029970">know</span> <span m="1030780">to</span> <span m="1030900">which</span>
  <span m="1031079">extent</span> <span m="1031349">you</span> <span m="1031440">guys</span>
  <span m="1031619">are</span> <span m="1031740">comfortable</span> <span m="1032099">with</span>
  <span m="1032250">this</span> <span m="1032490">at</span> <span m="1032579">all</span>
  <span m="1032880">or</span> <span m="1033060">not.</span></p><p><span m="1036700">OK,</span>
  <span m="1037329">so</span> <span m="1037450">let's</span> <span m="1037599">move</span>
  <span m="1037810">on.</span> <span m="1039810">All</span> <span m="1039900">right,</span>
  <span m="1040150">so</span> <span m="1041910">of</span> <span m="1042030">course,</span>
  <span m="1042390">this</span> <span m="1042599">is</span> <span m="1043260">what</span>
  <span m="1043460">I'm</span> <span m="1043589">describing</span> <span m="1044339">in</span>
  <span m="1044460">terms</span> <span m="1044849">of</span> <span m="1045150">the</span>
  <span m="1045359">distribution</span> <span m="1046050">right</span> <span m="1046200">here.</span>
  <span m="1046420">I</span> <span m="1046500">took</span> <span m="1046740">expectations.</span>
  <span m="1048359">Covariances</span> <span m="1049020">are</span> <span m="1049140">also</span>
  <span m="1049470">expectations.</span> <span m="1050140">So</span> <span m="1050250">those</span>
  <span m="1050580">depend</span> <span m="1051030">on</span> <span m="1051240">some</span>
  <span m="1051450">distribution</span> <span m="1052020">of</span> <span m="1052110">X,</span>
  <span m="1052350">right?</span> <span m="1052560">If I</span> <span m="1052730">wanted</span>
  <span m="1052890">to</span> <span m="1052980">compute</span> <span m="1053280">that,</span>
  <span m="1053900">I</span> <span m="1053970">would</span> <span m="1054120">basically</span>
  <span m="1054630">need</span> <span m="1054810">to</span> <span m="1054930">know</span>
  <span m="1055080">what</span> <span m="1055230">the</span> <span m="1055320">distribution</span>
  <span m="1055830">of</span> <span m="1055920">X</span> <span m="1056130">is.</span></p><p><span
  m="1056760">Now,</span> <span m="1056880">we're</span> <span m="1057000">doing</span>
  <span m="1057210">statistics,</span> <span m="1057760">so</span> <span m="1057890">I
  need</span> <span m="1058060">to</span> <span m="1058670">[INAUDIBLE]</span> <span
  m="1059130">my</span> <span m="1059250">question</span> <span m="1059550">is</span>
  <span m="1059670">going</span> <span m="1059820">to</span> <span m="1059880">be</span>
  <span m="1060030">to</span> <span m="1060180">say,</span> <span m="1060460">well,</span>
  <span m="1061180">how</span> <span m="1061290">well</span> <span m="1061530">can</span>
  <span m="1061740">I</span> <span m="1061830">estimate</span> <span m="1063090">the</span>
  <span m="1063180">covariance</span> <span m="1063510">matrix</span> <span m="1063930">itself,</span>
  <span m="1064380">or</span> <span m="1064500">some</span> <span m="1065910">properties</span>
  <span m="1066360">of</span> <span m="1066450">this</span> <span m="1066570">covariance</span>
  <span m="1066930">matrix</span> <span m="1067260">based</span> <span m="1067530">on</span>
  <span m="1067620">data?</span></p><p><span m="1068405">All right,</span> <span m="1068860">so</span>
  <span m="1069180">if</span> <span m="1069330">I</span> <span m="1069420">want</span>
  <span m="1069600">to</span> <span m="1069720">understand</span> <span m="1070140">what</span>
  <span m="1070260">my</span> <span m="1070380">covariance</span> <span m="1070740">matrix</span>
  <span m="1071130">looks</span> <span m="1071370">like</span> <span m="1072240">based</span>
  <span m="1072480">on</span> <span m="1072600">data,</span> <span m="1072990">I'm</span>
  <span m="1073110">going</span> <span m="1073230">to</span> <span m="1073290">have</span>
  <span m="1073500">to</span> <span m="1073620">basically</span> <span m="1074490">form</span>
  <span m="1074940">its</span> <span m="1075150">empirical</span> <span m="1075750">counterparts,</span>
  <span m="1076860">which</span> <span m="1077760">I</span> <span m="1077880">can</span>
  <span m="1078090">do</span> <span m="1078330">by</span> <span m="1078570">doing</span>
  <span m="1079020">the</span> <span m="1080640">age-old</span> <span m="1081150">statistical</span>
  <span m="1081720">trick,</span> <span m="1082020">which</span> <span m="1082200">is</span>
  <span m="1082320">replace</span> <span m="1082650">your</span> <span m="1082740">expectation</span>
  <span m="1083310">by</span> <span m="1083460">an</span> <span m="1083550">average,</span>
  <span m="1083850">all right?</span> <span m="1084700">So</span> <span m="1084760">let's</span>
  <span m="1084930">just--</span> <span m="1085230">everything</span> <span m="1085620">that's</span>
  <span m="1085770">on</span> <span m="1085860">the</span> <span m="1085980">board,</span>
  <span m="1086310">you</span> <span m="1086430">see</span> <span m="1086550">expectation,</span>
  <span m="1087130">just</span> <span m="1087270">replace it</span> <span m="1087720">by</span>
  <span m="1087870">an</span> <span m="1087990">average.</span></p><p><span m="1089310">OK,</span>
  <span m="1089550">so,</span> <span m="1090740">now</span> <span m="1090820">I'm</span>
  <span m="1090970">going</span> <span m="1091140">to</span> <span m="1091200">be</span>
  <span m="1091290">given</span> <span m="1091650">X1,</span> <span m="1091710">Xn.</span>
  <span m="1094230">So,</span> <span m="1094590">I'm</span> <span m="1094740">going</span>
  <span m="1094890">to</span> <span m="1094950">define</span> <span m="1095370">the</span>
  <span m="1095610">empirical</span> <span m="1096090">mean.</span> <span m="1099780">OK</span>
  <span m="1099980">so,</span> <span m="1100460">really,</span> <span m="1100760">the</span>
  <span m="1100880">idea</span> <span m="1101180">is</span> <span m="1101280">take</span>
  <span m="1101480">your</span> <span m="1101600">expectation</span> <span m="1102290">and</span>
  <span m="1102380">replace</span> <span m="1102830">it</span> <span m="1102920">by</span>
  <span m="1103160">1</span> <span m="1103380">over</span> <span m="1103490">n</span>
  <span m="1103740">sum, right?</span> <span m="1104970">And</span> <span m="1105530">so</span>
  <span m="1105740">the</span> <span m="1105860">empirical</span> <span m="1106280">mean</span>
  <span m="1106580">is</span> <span m="1106700">just</span> <span m="1106940">1</span>
  <span m="1107120">over</span> <span m="1107240">n.</span> <span m="1108230">Some</span>
  <span m="1109070">of</span> <span m="1109250">the</span> <span m="1109380">Xi's--</span>
  <span m="1111510">I'm</span> <span m="1111660">guessing</span> <span m="1111990">everybody</span>
  <span m="1112380">knows</span> <span m="1112650">how</span> <span m="1112860">to</span>
  <span m="1113130">average</span> <span m="1113610">vectors.</span> <span m="1114070">It's</span>
  <span m="1114240">just</span> <span m="1114480">the</span> <span m="1114570">average</span>
  <span m="1114870">of</span> <span m="1114960">the</span> <span m="1115050">coordinates.</span>
  <span m="1116110">So</span> <span m="1116160">I</span> <span m="1116220">will</span>
  <span m="1116460">write</span> <span m="1116700">this</span> <span m="1116940">as</span>
  <span m="1117120">X</span> <span m="1117300">bar.</span> <span m="1119730">And</span>
  <span m="1119970">the</span> <span m="1120090">empirical</span> <span m="1120540">covariance</span>
  <span m="1120930">matrix,</span> <span m="1130240">often</span> <span m="1130630">called</span>
  <span m="1131440">sample</span> <span m="1131950">covariance</span> <span m="1132340">matrix,</span>
  <span m="1134310">hence</span> <span m="1134550">the</span> <span m="1134670">notation,</span>
  <span m="1135360">S.</span></p><p><span m="1137520">Well,</span> <span m="1138330">this</span>
  <span m="1138510">is</span> <span m="1138630">my covariance</span> <span m="1139140">matrix,</span>
  <span m="1139560">right?</span> <span m="1139800">Let's</span> <span m="1139980">just</span>
  <span m="1140130">replace</span> <span m="1140490">the</span> <span m="1140580">expectations</span>
  <span m="1141210">by</span> <span m="1141390">averages.</span> <span m="1142650">1</span>
  <span m="1142860">over</span> <span m="1143130">n,</span> <span m="1143720">sum</span>
  <span m="1144090">from</span> <span m="1144330">i</span> <span m="1144580">equal</span>
  <span m="1144870">1</span> <span m="1145140">to</span> <span m="1145380">n,</span>
  <span m="1147006">of</span> <span m="1147450">Xi,</span> <span m="1148560">Xi</span>
  <span m="1148980">transpose,</span> <span m="1150360">minus--</span> <span m="1152160">this</span>
  <span m="1152340">is</span> <span m="1152470">the</span> <span m="1152650">expectation</span>
  <span m="1153270">of</span> <span m="1153360">X. I</span> <span m="1153650">will</span>
  <span m="1153780">replace</span> <span m="1154200">it</span> <span m="1154290">by</span>
  <span m="1154440">the</span> <span m="1154560">average,</span> <span m="1154960">which</span>
  <span m="1155070">I</span> <span m="1155140">just</span> <span m="1155340">called</span>
  <span m="1155580">X</span> <span m="1155730">bar,</span> <span m="1156480">X</span>
  <span m="1156660">bar</span> <span m="1156910">transpose,</span> <span m="1161380">OK?</span></p><p><span
  m="1162590">And</span> <span m="1162610">that's</span> <span m="1162820">when</span>
  <span m="1162970">I</span> <span m="1163090">want</span> <span m="1163270">to</span>
  <span m="1163420">use</span> <span m="1163720">the--</span> <span m="1165480">that's</span>
  <span m="1165660">when</span> <span m="1165810">I</span> <span m="1165900">want</span>
  <span m="1166110">to</span> <span m="1166230">use</span> <span m="1166500">the</span>
  <span m="1167520">notation--</span> <span m="1168430">the</span> <span m="1168480">second</span>
  <span m="1168870">definition,</span> <span m="1169470">but</span> <span m="1169920">I</span>
  <span m="1170040">could</span> <span m="1170250">actually</span> <span m="1170670">do</span>
  <span m="1171030">exactly</span> <span m="1171540">the</span> <span m="1171660">same</span>
  <span m="1171930">thing</span> <span m="1172590">using</span> <span m="1172950">this</span>
  <span m="1173190">definition</span> <span m="1173850">here.</span> <span m="1175530">Sorry,</span>
  <span m="1176630">using</span> <span m="1177050">this</span> <span m="1177230">definition</span>
  <span m="1177770">right</span> <span m="1177980">here.</span> <span m="1178750">So</span>
  <span m="1178850">this</span> <span m="1179060">is</span> <span m="1179180">actually</span>
  <span m="1180290">1</span> <span m="1180500">over</span> <span m="1180740">n,</span>
  <span m="1181580">sum</span> <span m="1181880">from</span> <span m="1182160">i equal</span>
  <span m="1182520">1</span> <span m="1182780">to</span> <span m="1182990">n,</span>
  <span m="1185180">of</span> <span m="1186740">Xi</span> <span m="1188400">minus</span>
  <span m="1188820">X</span> <span m="1189030">bar,</span> <span m="1190730">Xi</span>
  <span m="1191270">minus</span> <span m="1191780">X</span> <span m="1191990">bar</span>
  <span m="1193500">transpose.</span></p><p><span m="1195240">And</span> <span m="1195450">those</span>
  <span m="1195690">are</span> <span m="1195810">actually--</span> <span m="1196560">I</span>
  <span m="1196620">mean,</span> <span m="1197160">in</span> <span m="1197310">a</span>
  <span m="1197370">way,</span> <span m="1197500">it</span> <span m="1197550">looks</span>
  <span m="1197790">like</span> <span m="1197970">I</span> <span m="1198480">could</span>
  <span m="1198700">define</span> <span m="1199020">two</span> <span m="1199170">different</span>
  <span m="1199440">estimators,</span> <span m="1199950">but</span> <span m="1200100">you</span>
  <span m="1200220">can</span> <span m="1200400">actually</span> <span m="1200730">check.</span>
  <span m="1201630">And</span> <span m="1201750">I</span> <span m="1201870">do</span>
  <span m="1202140">encourage</span> <span m="1202620">you</span> <span m="1202740">to</span>
  <span m="1202920">do</span> <span m="1203100">this.</span> <span m="1203700">If</span>
  <span m="1203850">you're</span> <span m="1204000">not</span> <span m="1204180">comfortable</span>
  <span m="1204720">making</span> <span m="1205050">those</span> <span m="1205200">manipulations,</span>
  <span m="1205920">you can</span> <span m="1206250">actually</span> <span m="1206610">check</span>
  <span m="1206900">that</span> <span m="1207080">those</span> <span m="1207270">two</span>
  <span m="1207390">things</span> <span m="1207660">are</span> <span m="1207750">actually</span>
  <span m="1208080">exactly</span> <span m="1208440">the same,</span> <span m="1214732">OK?</span></p><p><span
  m="1220540">So</span> <span m="1222500">now,</span> <span m="1222760">I'm</span>
  <span m="1222880">going</span> <span m="1223000">to</span> <span m="1223060">want</span>
  <span m="1223210">to</span> <span m="1223270">talk</span> <span m="1223510">about</span>
  <span m="1223720">matrices,</span> <span m="1224620">OK?</span> <span m="1225070">And</span>
  <span m="1225160">remember,</span> <span m="1225490">we</span> <span m="1225640">defined</span>
  <span m="1226030">this</span> <span m="1226210">big</span> <span m="1226450">matrix,</span>
  <span m="1227020">X,</span> <span m="1227260">with</span> <span m="1227410">the</span>
  <span m="1227500">double</span> <span m="1227830">bar.</span> <span m="1228790">And</span>
  <span m="1228910">the</span> <span m="1229000">question</span> <span m="1229360">is,</span>
  <span m="1229510">can I</span> <span m="1229720">express</span> <span m="1231160">both</span>
  <span m="1231910">X</span> <span m="1232180">bar</span> <span m="1233020">and</span>
  <span m="1233970">the</span> <span m="1234220">sample</span> <span m="1234580">covariance</span>
  <span m="1234970">matrix</span> <span m="1235360">in</span> <span m="1235450">terms</span>
  <span m="1235720">of</span> <span m="1235840">this</span> <span m="1236050">big</span>
  <span m="1236290">matrix,</span> <span m="1236800">X?</span> <span m="1237460">Because</span>
  <span m="1237730">right</span> <span m="1237940">now,</span> <span m="1238600">it's</span>
  <span m="1238750">still</span> <span m="1239110">expressed</span> <span m="1239740">in</span>
  <span m="1239830">terms</span> <span m="1240100">of</span> <span m="1240190">the</span>
  <span m="1240310">vectors.</span> <span m="1240820">I'm</span> <span m="1240940">summing</span>
  <span m="1241450">those</span> <span m="1241660">vectors,</span> <span m="1242080">vectors</span>
  <span m="1242440">transpose.</span> <span m="1243220">The</span> <span m="1243310">question</span>
  <span m="1243610">is,</span> <span m="1243830">can</span> <span m="1243880">I</span>
  <span m="1243970">just</span> <span m="1244180">do</span> <span m="1244330">that</span>
  <span m="1244510">in</span> <span m="1244630">a</span> <span m="1244690">very</span>
  <span m="1244930">compact</span> <span m="1245380">way,</span> <span m="1246050">in</span>
  <span m="1246400">a</span> <span m="1246490">way</span> <span m="1246670">that</span>
  <span m="1246820">I</span> <span m="1246880">can</span> <span m="1247030">actually</span>
  <span m="1247300">remove</span> <span m="1247660">this</span> <span m="1248160">sum</span>
  <span m="1248800">term,</span> <span m="1250230">all</span> <span m="1250290">right?</span></p><p><span
  m="1250610">That's</span> <span m="1251340">going</span> <span m="1251490">to</span>
  <span m="1251550">be</span> <span m="1251610">the</span> <span m="1251730">goal.</span>
  <span m="1252990">I</span> <span m="1253080">mean,</span> <span m="1253470">that's</span>
  <span m="1253650">not</span> <span m="1253860">a</span> <span m="1253920">notational</span>
  <span m="1254520">goal.</span> <span m="1254850">That's</span> <span m="1255120">really</span>
  <span m="1256110">something</span> <span m="1256500">that</span> <span m="1256920">we</span>
  <span m="1257100">want--</span> <span m="1258290">that's</span> <span m="1258480">going</span>
  <span m="1258600">to</span> <span m="1258660">be</span> <span m="1258720">convenient</span>
  <span m="1259230">for</span> <span m="1259410">us</span> <span m="1259590">just</span>
  <span m="1259800">like</span> <span m="1259980">it</span> <span m="1260040">was</span>
  <span m="1260220">convenient</span> <span m="1261180">to</span> <span m="1261300">talk</span>
  <span m="1261690">about</span> <span m="1262020">matrices</span> <span m="1262560">when</span>
  <span m="1262740">we</span> <span m="1262860">did</span> <span m="1263010">linear</span>
  <span m="1263340">regression.</span></p><p><span m="1283180">OK,</span> <span m="1284055">X</span>
  <span m="1284550">bar.</span> <span m="1286340">We</span> <span m="1286530">just</span>
  <span m="1286760">said</span> <span m="1286940">it's</span> <span m="1287120">1</span>
  <span m="1287270">over</span> <span m="1287510">n,</span> <span m="1288140">sum</span>
  <span m="1288440">from</span> <span m="1288710">I equal</span> <span m="1289260">1</span>
  <span m="1289530">to</span> <span m="1289800">n</span> <span m="1290000">of</span>
  <span m="1290270">Xi,</span> <span m="1291200">right?</span> <span m="1292730">Now</span>
  <span m="1292880">remember,</span> <span m="1293510">what</span> <span m="1293720">does</span>
  <span m="1293930">this</span> <span m="1294140">matrix</span> <span m="1294620">look</span>
  <span m="1294800">like?</span> <span m="1295100">We</span> <span m="1295220">said</span>
  <span m="1295460">that</span> <span m="1295850">X</span> <span m="1296510">bar--</span>
  <span m="1299010">X</span> <span m="1299450">is</span> <span m="1299630">this</span>
  <span m="1299840">guy.</span> <span m="1300270">So</span> <span m="1300320">if</span>
  <span m="1300450">I</span> <span m="1300530">look</span> <span m="1300710">at</span>
  <span m="1300860">X</span> <span m="1301130">transpose,</span> <span m="1304640">the</span>
  <span m="1304940">columns</span> <span m="1305330">of</span> <span m="1305450">this</span>
  <span m="1305660">guy</span> <span m="1305930">becomes</span> <span m="1307550">X1,</span>
  <span m="1309625">my</span> <span m="1310010">first</span> <span m="1310310">observation,</span>
  <span m="1310930">X2,</span> <span m="1311430">my</span> <span m="1311570">second</span>
  <span m="1311840">observation,</span> <span m="1312440">all</span> <span m="1312530">the</span>
  <span m="1312620">way</span> <span m="1312770">to</span> <span m="1312950">Xn,</span>
  <span m="1313820">my</span> <span m="1314030">last</span> <span m="1314270">observation,</span>
  <span m="1314840">right?</span> <span m="1316280">Agreed?</span> <span m="1316850">That's</span>
  <span m="1317030">what</span> <span m="1317170">X</span> <span m="1317300">transpose</span>
  <span m="1317630">is.</span></p><p><span m="1318470">So</span> <span m="1318590">if</span>
  <span m="1318710">I</span> <span m="1318800">want</span> <span m="1318950">to</span>
  <span m="1319070">sum</span> <span m="1319340">those</span> <span m="1319580">guys,</span>
  <span m="1320870">I</span> <span m="1320960">can</span> <span m="1321140">multiply</span>
  <span m="1321710">by</span> <span m="1321890">the</span> <span m="1322040">all-ones</span>
  <span m="1322430">vector.</span> <span m="1326650">All</span> <span m="1326710">right,</span>
  <span m="1326860">so</span> <span m="1327040">that's</span> <span m="1327310">what</span>
  <span m="1327490">the</span> <span m="1327610">definition</span> <span m="1328120">of</span>
  <span m="1328240">the all-ones</span> <span m="1328470">1</span> <span m="1328700">vector</span>
  <span m="1329030">is.</span> <span m="1331840">Well,</span> <span m="1331940">it's</span>
  <span m="1332180">just</span> <span m="1332380">a</span> <span m="1332440">bunch</span>
  <span m="1332650">of</span> <span m="1332770">1's</span> <span m="1336650">in</span>
  <span m="1336990">Rn,</span> <span m="1338220">in</span> <span m="1338340">this</span>
  <span m="1338520">case.</span> <span m="1339870">And</span> <span m="1339960">so</span>
  <span m="1340080">when</span> <span m="1340220">I</span> <span m="1340290">do</span>
  <span m="1340440">X</span> <span m="1340690">transpose</span> <span m="1341220">1,</span>
  <span m="1341940">what</span> <span m="1342060">I</span> <span m="1342150">get</span>
  <span m="1342450">is</span> <span m="1342600">just</span> <span m="1342810">the</span>
  <span m="1342970">sum</span> <span m="1343340">from</span> <span m="1343620">i equal</span>
  <span m="1344010">1</span> <span m="1344280">to</span> <span m="1344510">n</span>
  <span m="1344690">of</span> <span m="1344880">the</span> <span m="1345070">Xi's.</span>
  <span m="1347690">So</span> <span m="1347810">if</span> <span m="1347960">I</span>
  <span m="1348050">divide</span> <span m="1348440">by</span> <span m="1348620">n,</span>
  <span m="1350660">I get</span> <span m="1350960">my</span> <span m="1351140">average,</span>
  <span m="1355350">OK?</span> <span m="1356460">So</span> <span m="1357780">here,</span>
  <span m="1358770">I</span> <span m="1358870">definitely</span> <span m="1359280">removed</span>
  <span m="1361000">the</span> <span m="1361230">sum</span> <span m="1361560">term.</span></p><p><span
  m="1363200">Let's</span> <span m="1363330">see if</span> <span m="1363490">with</span>
  <span m="1363660">the</span> <span m="1363780">covariance</span> <span m="1364140">matrix,</span>
  <span m="1364630">we</span> <span m="1364730">can</span> <span m="1364800">do</span>
  <span m="1364890">the</span> <span m="1365010">same.</span> <span m="1367930">Well,</span>
  <span m="1368410">and</span> <span m="1368500">that's</span> <span m="1368680">actually</span>
  <span m="1369070">a</span> <span m="1369420">little</span> <span m="1370120">more</span>
  <span m="1370540">difficult</span> <span m="1372670">to</span> <span m="1372850">see,</span>
  <span m="1373280">I</span> <span m="1373380">guess.</span> <span m="1375280">But</span>
  <span m="1376390">let's</span> <span m="1376630">use</span> <span m="1376930">this</span>
  <span m="1377140">definition</span> <span m="1377740">for</span> <span m="1377950">S,</span>
  <span m="1382670">OK?</span> <span m="1385510">And</span> <span m="1385910">one</span>
  <span m="1386150">thing</span> <span m="1386360">that's</span> <span m="1386540">actually</span>
  <span m="1386870">going</span> <span m="1387020">to</span> <span m="1387110">be--</span>
  <span m="1387540">so,</span> <span m="1388070">let's</span> <span m="1388250">see</span>
  <span m="1388610">for</span> <span m="1388820">one</span> <span m="1389030">second,</span>
  <span m="1389690">what--</span> <span m="1390260">so</span> <span m="1390500">it's</span>
  <span m="1390650">going</span> <span m="1390770">to</span> <span m="1390830">be</span>
  <span m="1390950">something</span> <span m="1391370">that</span> <span m="1391490">involves</span>
  <span m="1392150">X,</span> <span m="1392510">multiplying</span> <span m="1393110">X</span>
  <span m="1393350">with</span> <span m="1393500">itself,</span> <span m="1394040">OK?</span>
  <span m="1394730">And</span> <span m="1394820">the</span> <span m="1394910">question</span>
  <span m="1395150">is,</span> <span m="1395430">is</span> <span m="1395570">it</span>
  <span m="1395690">going</span> <span m="1395840">to</span> <span m="1395900">be</span>
  <span m="1395960">multiplying</span> <span m="1396500">X</span> <span m="1396740">with</span>
  <span m="1396860">X</span> <span m="1397010">transpose,</span> <span m="1397460">or</span>
  <span m="1397570">X tranpose</span> <span m="1398000">with</span> <span m="1398310">X?</span></p><p><span
  m="1399140">To</span> <span m="1399230">answer</span> <span m="1399440">this</span>
  <span m="1399590">question,</span> <span m="1400140">you</span> <span m="1400240">can</span>
  <span m="1400340">go</span> <span m="1400490">the</span> <span m="1400640">easy</span>
  <span m="1400970">route,</span> <span m="1401300">which</span> <span m="1401510">says,</span>
  <span m="1401750">well,</span> <span m="1402770">my</span> <span m="1402980">covariance</span>
  <span m="1403370">matrix</span> <span m="1403665">is</span> <span m="1403960">of</span>
  <span m="1404120">size,</span> <span m="1404540">what?</span> <span m="1404870">What</span>
  <span m="1405200">is</span> <span m="1405320">the</span> <span m="1405440">size</span>
  <span m="1405710">of</span> <span m="1405940">S?</span></p><p><span m="1407682">AUDIENCE:</span>
  <span m="1407846">d</span> <span m="1408010">by</span> <span m="1408176">d.</span></p><p><span
  m="1408670">PHILIPPE RIGOLLET:</span> <span m="1408890">d by</span> <span m="1409110">d,</span>
  <span m="1409550">OK?</span> <span m="1410260">X</span> <span m="1410680">is</span>
  <span m="1410860">of</span> <span m="1410980">size</span> <span m="1413020">n</span>
  <span m="1413200">by</span> <span m="1413430">d.</span> <span m="1414200">So</span>
  <span m="1414430">if</span> <span m="1414550">I</span> <span m="1414640">do</span>
  <span m="1414880">X</span> <span m="1415120">times</span> <span m="1415360">X</span>
  <span m="1415510">transpose,</span> <span m="1415990">I'm</span> <span m="1416050">going</span>
  <span m="1416170">to</span> <span m="1416230">have</span> <span m="1416350">something</span>
  <span m="1416620">which</span> <span m="1416770">is</span> <span m="1416860">of</span>
  <span m="1416950">size</span> <span m="1417160">n</span> <span m="1417340">by</span>
  <span m="1417590">n.</span> <span m="1417760">If I do</span> <span m="1418250">X</span>
  <span m="1418470">transpose</span> <span m="1418780">X,</span> <span m="1418930">I'm</span>
  <span m="1418990">going</span> <span m="1419110">to</span> <span m="1419170">have</span>
  <span m="1419290">something</span> <span m="1419620">which</span> <span m="1419770">is</span>
  <span m="1419860">d</span> <span m="1420010">by</span> <span m="1420160">d.</span>
  <span m="1420820">That's</span> <span m="1421030">the</span> <span m="1421150">easy</span>
  <span m="1421450">route.</span> <span m="1421710">And</span> <span m="1421970">there's</span>
  <span m="1422200">basically</span> <span m="1422620">one</span> <span m="1422860">of</span>
  <span m="1422980">the</span> <span m="1423100">two</span> <span m="1423250">guys.</span></p><p><span
  m="1424150">You</span> <span m="1424240">can</span> <span m="1424390">actually</span>
  <span m="1424810">open</span> <span m="1425080">the</span> <span m="1425170">box</span>
  <span m="1425500">a</span> <span m="1425530">little</span> <span m="1425830">bit</span>
  <span m="1426130">and</span> <span m="1426250">see</span> <span m="1426460">what's</span>
  <span m="1426670">going</span> <span m="1426940">on</span> <span m="1427090">in</span>
  <span m="1427270">there.</span> <span m="1428170">If</span> <span m="1428320">you</span>
  <span m="1428440">do</span> <span m="1428710">X</span> <span m="1428980">transpose</span>
  <span m="1429610">X,</span> <span m="1430480">which</span> <span m="1430630">we</span>
  <span m="1430750">know</span> <span m="1431080">gives</span> <span m="1431320">you</span>
  <span m="1431530">a</span> <span m="1431650">d</span> <span m="1431950">by</span>
  <span m="1432160">d,</span> <span m="1432760">you'll</span> <span m="1432850">see</span>
  <span m="1433060">that</span> <span m="1433780">X</span> <span m="1434020">is</span>
  <span m="1434110">going</span> <span m="1434230">to</span> <span m="1434320">have</span>
  <span m="1434470">vectors</span> <span m="1434800">that</span> <span m="1434920">are</span>
  <span m="1435010">of</span> <span m="1435130">the</span> <span m="1435220">form,</span>
  <span m="1435550">Xi,</span> <span m="1436760">and</span> <span m="1437060">X</span>
  <span m="1437210">transpose</span> <span m="1437465">is</span> <span m="1437790">going</span>
  <span m="1437910">to</span> <span m="1437980">have</span> <span m="1438130">vectors</span>
  <span m="1438520">that</span> <span m="1438610">are</span> <span m="1438700">of</span>
  <span m="1438850">the</span> <span m="1438970">form,</span> <span m="1440810">Xi</span>
  <span m="1441540">transpose,</span> <span m="1442230">right?</span> <span m="1443710">And</span>
  <span m="1443860">so,</span> <span m="1444940">this</span> <span m="1445150">is</span>
  <span m="1445300">actually</span> <span m="1445630">probably</span> <span m="1446020">the</span>
  <span m="1446140">right</span> <span m="1446320">way</span> <span m="1446440">to</span>
  <span m="1446530">go.</span> <span m="1446810">So</span> <span m="1446890">let's</span>
  <span m="1447130">look</span> <span m="1447340">at</span> <span m="1447460">what's</span>
  <span m="1448490">X</span> <span m="1448750">transpose</span> <span m="1449230">X</span>
  <span m="1449530">is</span> <span m="1449680">giving</span> <span m="1450010">us.</span></p><p><span
  m="1451690">So</span> <span m="1453580">I</span> <span m="1453700">claim</span>
  <span m="1454060">that</span> <span m="1454210">it's</span> <span m="1454360">actually</span>
  <span m="1454630">going</span> <span m="1454780">to</span> <span m="1454840">give</span>
  <span m="1454990">us</span> <span m="1455140">what</span> <span m="1455290">we</span>
  <span m="1455440">want,</span> <span m="1456850">but</span> <span m="1457060">rather</span>
  <span m="1457360">than</span> <span m="1457540">actually</span> <span m="1458020">going</span>
  <span m="1458350">there,</span> <span m="1458660">let's--</span> <span m="1459710">to</span>
  <span m="1459940">actually--</span> <span m="1460540">I</span> <span m="1460570">mean,</span>
  <span m="1460750">we</span> <span m="1460840">could</span> <span m="1460990">check</span>
  <span m="1461320">it</span> <span m="1461560">entry</span> <span m="1461860">by</span>
  <span m="1462040">entry,</span> <span m="1462700">but</span> <span m="1462790">there's</span>
  <span m="1462970">actually</span> <span m="1463270">a</span> <span m="1463330">nice</span>
  <span m="1463540">thing</span> <span m="1463720">we</span> <span m="1463840">can</span>
  <span m="1464020">do.</span> <span m="1465400">Before</span> <span m="1465670">we</span>
  <span m="1465790">go</span> <span m="1466030">there,</span> <span m="1466400">let's</span>
  <span m="1466570">write</span> <span m="1466840">X</span> <span m="1467110">transpose</span>
  <span m="1468090">as</span> <span m="1468280">the</span> <span m="1468400">following</span>
  <span m="1468910">sum</span> <span m="1469240">of</span> <span m="1470590">variables,</span>
  <span m="1471150">X1</span> <span m="1472930">and</span> <span m="1473080">then</span>
  <span m="1473260">just</span> <span m="1473520">a</span> <span m="1473590">bunch</span>
  <span m="1473860">of</span> <span m="1473980">0's</span> <span m="1474490">everywhere</span>
  <span m="1474910">else.</span> <span m="1476270">So</span> <span m="1476370">it's</span>
  <span m="1476470">still</span> <span m="1477430">d</span> <span m="1477685">by</span>
  <span m="1477940">n.</span> <span m="1479410">So</span> <span m="1479680">n</span>
  <span m="1479890">minus 1</span> <span m="1480280">of</span> <span m="1480550">the</span>
  <span m="1480640">columns</span> <span m="1481030">are</span> <span m="1481120">equal</span>
  <span m="1481360">to</span> <span m="1481480">0</span> <span m="1481770">here.</span></p><p><span
  m="1482470">Then</span> <span m="1482620">I'm</span> <span m="1482710">going</span>
  <span m="1482830">to</span> <span m="1482890">put</span> <span m="1483040">a</span>
  <span m="1483100">0</span> <span m="1483610">and</span> <span m="1483730">then</span>
  <span m="1483910">put</span> <span m="1484090">X2.</span> <span m="1485860">And</span>
  <span m="1485980">then</span> <span m="1486160">just</span> <span m="1486370">a</span>
  <span m="1486430">bunch</span> <span m="1486640">of</span> <span m="1486760">0's,</span>
  <span m="1488350">right?</span> <span m="1488550">So</span> <span m="1488670">that's</span>
  <span m="1488910">just</span> <span m="1489120">0,</span> <span m="1490020">0</span>
  <span m="1492490">plus</span> <span m="1495210">0,</span> <span m="1496010">0,</span>
  <span m="1496350">all</span> <span m="1496500">the</span> <span m="1496620">way</span>
  <span m="1496770">to</span> <span m="1496980">Xn,</span> <span m="1499520">OK?</span>
  <span m="1499940">Everybody</span> <span m="1500240">agrees</span> <span m="1500540">with
  it?</span> <span m="1501260">See</span> <span m="1501440">what</span> <span m="1501560">I'm</span>
  <span m="1501650">doing</span> <span m="1501890">here?</span> <span m="1503650">I'm</span>
  <span m="1503700">just</span> <span m="1504180">splitting</span> <span m="1504465">it</span>
  <span m="1504840">into</span> <span m="1505110">a</span> <span m="1505170">sum</span>
  <span m="1505470">of</span> <span m="1505590">matrices</span> <span m="1506040">that</span>
  <span m="1506150">only</span> <span m="1506400">have</span> <span m="1506610">one</span>
  <span m="1506840">nonzero</span> <span m="1507270">columns.</span> <span m="1508730">But</span>
  <span m="1509140">clearly,</span> <span m="1509500">that's</span> <span m="1509740">true.</span></p><p><span
  m="1511210">Now</span> <span m="1511300">let's</span> <span m="1511480">look</span>
  <span m="1511660">at</span> <span m="1511780">the</span> <span m="1511960">product</span>
  <span m="1512440">of</span> <span m="1512560">this</span> <span m="1512770">guy</span>
  <span m="1513510">with</span> <span m="1513700">itself.</span> <span m="1515610">So,</span>
  <span m="1515790">let's</span> <span m="1515940">call</span> <span m="1516120">these</span>
  <span m="1516270">matrices</span> <span m="1519070">M1,</span> <span m="1520800">M2,</span>
  <span m="1522897">Mn.</span> <span m="1526890">So</span> <span m="1527010">when</span>
  <span m="1527190">I</span> <span m="1527280">do</span> <span m="1527640">X</span>
  <span m="1527910">transpose</span> <span m="1528420">X,</span> <span m="1530420">what</span>
  <span m="1530650">I</span> <span m="1530750">do</span> <span m="1531050">is</span>
  <span m="1531750">the</span> <span m="1531960">sum</span> <span m="1533860">of</span>
  <span m="1534040">the</span> <span m="1534190">Mi's</span> <span m="1534850">for</span>
  <span m="1535090">i</span> <span m="1535330">equal</span> <span m="1535630">1</span>
  <span m="1536000">to</span> <span m="1536290">n,</span> <span m="1537970">times</span>
  <span m="1538480">the</span> <span m="1538630">sum</span> <span m="1541660">of</span>
  <span m="1541960">the Mi</span> <span m="1544996">transpose,</span> <span m="1545960">right?</span>
  <span m="1548620">Now,</span> <span m="1548935">the</span> <span m="1549250">sum</span>
  <span m="1549420">of</span> <span m="1549550">the Mi's</span> <span m="1550000">transpose</span>
  <span m="1550840">is</span> <span m="1551080">just</span> <span m="1551320">the</span>
  <span m="1551440">sum</span> <span m="1551710">of</span> <span m="1552010">each</span>
  <span m="1552250">of</span> <span m="1552370">the Mi's</span> <span m="1552880">transpose,</span>
  <span m="1554788">OK?</span> <span m="1558190">So</span> <span m="1558340">now</span>
  <span m="1559000">I</span> <span m="1559090">just</span> <span m="1559330">have</span>
  <span m="1559510">this</span> <span m="1559690">product</span> <span m="1560110">of</span>
  <span m="1560230">two</span> <span m="1560380">sums,</span> <span m="1560620">so</span>
  <span m="1560740">I'm</span> <span m="1560860">just</span> <span m="1561020">going</span>
  <span m="1561140">to</span> <span m="1561400">re-index</span> <span m="1561880">the</span>
  <span m="1561970">second</span> <span m="1562270">one</span> <span m="1562450">by</span>
  <span m="1562600">j.</span> <span m="1563290">So</span> <span m="1563450">this</span>
  <span m="1563650">is</span> <span m="1563830">sum</span> <span m="1564700">for</span>
  <span m="1565060">i</span> <span m="1565930">equal</span> <span m="1566260">1</span>
  <span m="1566600">to</span> <span m="1567320">n,</span> <span m="1568050">j</span>
  <span m="1568460">equal</span> <span m="1568870">1</span> <span m="1569240">to</span>
  <span m="1569410">n</span> <span m="1569800">of</span> <span m="1570280">Mi</span>
  <span m="1572650">Mj</span> <span m="1573040">transpose.</span> <span m="1575602">OK?</span></p><p><span
  m="1579090">And</span> <span m="1579210">now</span> <span m="1579360">what</span>
  <span m="1579510">we</span> <span m="1579630">want</span> <span m="1579810">to</span>
  <span m="1579960">notice</span> <span m="1580290">is</span> <span m="1580410">that</span>
  <span m="1580590">if</span> <span m="1580800">i</span> <span m="1582480">is</span>
  <span m="1582700">different</span> <span m="1583150">from</span> <span m="1583390">j,</span>
  <span m="1584880">what's</span> <span m="1585100">happening?</span> <span m="1586000">Well</span>
  <span m="1586180">if</span> <span m="1586390">i</span> <span m="1586490">is</span>
  <span m="1586660">different</span> <span m="1587020">from</span> <span m="1587260">j,</span>
  <span m="1590330">let's</span> <span m="1590540">look</span> <span m="1590720">at</span>
  <span m="1591200">say,</span> <span m="1591980">M1</span> <span m="1593420">times</span>
  <span m="1593780">XM2</span> <span m="1594380">transpose.</span> <span m="1614330">So</span>
  <span m="1614450">what</span> <span m="1614590">is</span> <span m="1614830">the</span>
  <span m="1614950">product</span> <span m="1615310">between</span> <span m="1615610">those</span>
  <span m="1615760">two</span> <span m="1615880">matrices?</span></p><p><span m="1624404">AUDIENCE:</span>
  <span m="1624528">It's</span> <span m="1624652">a</span> <span m="1624776">new</span>
  <span m="1624903">entry</span> <span m="1625901">and</span> <span m="1627897">[INAUDIBLE]</span></p><p><span
  m="1630410">PHILIPPE RIGOLLET:</span> <span m="1630500">There's</span> <span m="1630590">an</span>
  <span m="1630770">entry?</span></p><p><span m="1631370">AUDIENCE:</span> <span m="1631608">Well,</span>
  <span m="1631847">it's</span> <span m="1632324">an entry.</span> <span m="1632801">It's
  like a dot</span> <span m="1633278">product in</span> <span m="1633755">that form</span>
  <span m="1634709">next</span> <span m="1635186">to</span> <span m="1635663">[? transpose.
  ?]</span></p><p><span m="1637571">PHILIPPE RIGOLLET:</span> <span m="1637815">You
  mean</span> <span m="1638060">a dot</span> <span m="1638380">product</span> <span
  m="1638710">is</span> <span m="1639010">just</span> <span m="1639200">getting</span>
  <span m="1639490">[INAUDIBLE]</span> <span m="1639760">number,</span> <span m="1640090">right?</span>
  <span m="1640360">So I</span> <span m="1640480">want--</span> <span m="1640750">this</span>
  <span m="1640990">is</span> <span m="1641050">going</span> <span m="1641170">to</span>
  <span m="1641230">be</span> <span m="1641290">a</span> <span m="1641320">matrix.</span>
  <span m="1641650">It's</span> <span m="1641720">the</span> <span m="1641770">product</span>
  <span m="1642100">of</span> <span m="1642190">two</span> <span m="1642310">matrices,</span>
  <span m="1642760">right?</span> <span m="1644550">This</span> <span m="1644790">is</span>
  <span m="1644910">a</span> <span m="1644970">matrix</span> <span m="1646350">times
  a</span> <span m="1646710">matrix.</span> <span m="1647100">So</span> <span m="1647190">this</span>
  <span m="1647370">should</span> <span m="1647520">be</span> <span m="1647640">a</span>
  <span m="1647670">matrix,</span> <span m="1648150">right,</span> <span m="1649785">of</span>
  <span m="1650260">size d</span> <span m="1650735">by d.</span> <span m="1655960">Yeah,</span>
  <span m="1656270">I</span> <span m="1656360">should</span> <span m="1656540">see</span>
  <span m="1656750">a</span> <span m="1656780">lot</span> <span m="1656990">of</span>
  <span m="1657490">hands that</span> <span m="1657730">look</span> <span m="1657950">like</span>
  <span m="1658130">this,</span> <span m="1658370">right?</span></p><p><span m="1659060">Because</span>
  <span m="1659480">look</span> <span m="1659660">at</span> <span m="1659780">this.</span>
  <span m="1660200">So</span> <span m="1660320">let's</span> <span m="1660500">multiply</span>
  <span m="1661010">the</span> <span m="1661130">first--</span> <span m="1662450">let's</span>
  <span m="1662660">look</span> <span m="1662810">at</span> <span m="1662960">what's</span>
  <span m="1663170">going</span> <span m="1663410">on</span> <span m="1663530">in</span>
  <span m="1663650">the</span> <span m="1663740">first</span> <span m="1664040">column</span>
  <span m="1664460">here.</span> <span m="1665215">I'm</span> <span m="1665640">multiplying</span>
  <span m="1666230">this</span> <span m="1666440">column</span> <span m="1667280">with</span>
  <span m="1667460">each</span> <span m="1667670">of</span> <span m="1667820">those</span>
  <span m="1668030">rows.</span> <span m="1668840">The</span> <span m="1668960">only</span>
  <span m="1669260">nonzero</span> <span m="1669500">coefficient</span> <span m="1670190">is</span>
  <span m="1670340">here, and</span> <span m="1670620">it</span> <span m="1670830">only</span>
  <span m="1671180">hits</span> <span m="1671510">this</span> <span m="1671690">column</span>
  <span m="1672050">of</span> <span m="1672140">0's.</span> <span m="1674190">So</span>
  <span m="1674430">every</span> <span m="1674670">time,</span> <span m="1674970">this</span>
  <span m="1675120">is</span> <span m="1675210">going</span> <span m="1675360">to</span>
  <span m="1675420">give you</span> <span m="1675590">0,</span> <span m="1676072">0,
  0,</span> <span m="1676554">0.</span> <span m="1677036">And</span> <span m="1677520">it's</span>
  <span m="1677610">going</span> <span m="1677730">to</span> <span m="1677790">be</span>
  <span m="1677850">the</span> <span m="1677940">same</span> <span m="1678300">for</span>
  <span m="1678510">every</span> <span m="1678720">single</span> <span m="1678990">one</span>
  <span m="1679230">of</span> <span m="1679320">them.</span> <span m="1680020">So</span>
  <span m="1680040">this</span> <span m="1680250">matrix</span> <span m="1680670">is</span>
  <span m="1680790">just</span> <span m="1681030">full</span> <span m="1681270">of</span>
  <span m="1681390">0's,</span> <span m="1683630">right?</span> <span m="1684420">They</span>
  <span m="1684510">never</span> <span m="1684780">hit</span> <span m="1684990">each</span>
  <span m="1685140">other</span> <span m="1685380">when</span> <span m="1685530">I</span>
  <span m="1685650">do</span> <span m="1686130">the</span> <span m="1686250">matrix-matrix</span>
  <span m="1686970">multiplication.</span> <span m="1688350">There's</span> <span
  m="1688560">no--</span> <span m="1689310">every</span> <span m="1689670">non-zero</span>
  <span m="1690190">hits a</span> <span m="1690440">0.</span></p><p><span m="1691940">So</span>
  <span m="1692090">what</span> <span m="1692210">it</span> <span m="1692330">means</span>
  <span m="1692570">is--</span> <span m="1692720">and</span> <span m="1692980">this,</span>
  <span m="1693230">of</span> <span m="1693350">course,</span> <span m="1693560">you</span>
  <span m="1693620">can</span> <span m="1693800">check</span> <span m="1694100">for</span>
  <span m="1694290">every</span> <span m="1694560">i</span> <span m="1694850">different</span>
  <span m="1695180">from</span> <span m="1695360">j.</span> <span m="1696020">So</span>
  <span m="1696170">this</span> <span m="1696380">means</span> <span m="1696620">that</span>
  <span m="1696770">Mi</span> <span m="1697530">times</span> <span m="1698090">Mj</span>
  <span m="1700160">transpose</span> <span m="1701840">is</span> <span m="1701960">actually</span>
  <span m="1702290">equal</span> <span m="1702560">to</span> <span m="1702680">0</span>
  <span m="1703080">when</span> <span m="1703330">i is</span> <span m="1703610">different</span>
  <span m="1703940">from</span> <span m="1704120">j,</span> <span m="1706250">Right?</span>
  <span m="1707150">Everybody</span> <span m="1707390">is</span> <span m="1707690">OK</span>
  <span m="1707960">with</span> <span m="1708080">this?</span> <span m="1709370">So</span>
  <span m="1709490">what</span> <span m="1709610">that</span> <span m="1709820">means</span>
  <span m="1710120">is</span> <span m="1710240">that</span> <span m="1710390">when</span>
  <span m="1710540">I</span> <span m="1710630">do</span> <span m="1710840">this</span>
  <span m="1711080">double</span> <span m="1711440">sum,</span> <span m="1712250">really,</span>
  <span m="1712670">it's</span> <span m="1712900">a</span> <span m="1712970">simple</span>
  <span m="1713360">sum.</span> <span m="1713670">There's</span> <span m="1713870">only</span>
  <span m="1714140">just</span> <span m="1714440">the</span> <span m="1714590">sum</span>
  <span m="1716420">from</span> <span m="1716660">i</span> <span m="1716935">equal</span>
  <span m="1717210">1</span> <span m="1717310">to</span> <span m="1717680">n</span>
  <span m="1719390">of</span> <span m="1719840">Mi</span> <span m="1720530">Mi</span>
  <span m="1721000">transpose.</span> <span m="1721820">Because</span> <span m="1722870">this</span>
  <span m="1723080">is</span> <span m="1723170">the</span> <span m="1723320">only</span>
  <span m="1723620">terms</span> <span m="1723890">in</span> <span m="1724010">this</span>
  <span m="1724280">double</span> <span m="1724580">sum</span> <span m="1724820">that</span>
  <span m="1725000">are</span> <span m="1725270">not</span> <span m="1725510">going</span>
  <span m="1725630">to</span> <span m="1725690">be</span> <span m="1725780">0</span>
  <span m="1727090">when</span> <span m="1727420">[INAUDIBLE]</span> <span m="1728110">[?
  M1 ?]</span> <span m="1728530">with</span> <span m="1728680">M1</span> <span m="1728980">itself.</span></p><p><span
  m="1730960">Now,</span> <span m="1730990">let's</span> <span m="1731140">see</span>
  <span m="1731260">what's</span> <span m="1731410">going</span> <span m="1731650">on</span>
  <span m="1731800">when</span> <span m="1731950">I</span> <span m="1732040">do</span>
  <span m="1732340">M1</span> <span m="1732730">times</span> <span m="1733040">M1</span>
  <span m="1733360">transpose.</span> <span m="1733930">Well,</span> <span m="1735130">now,</span>
  <span m="1735400">if</span> <span m="1735550">I</span> <span m="1735670">do</span>
  <span m="1735910">Mi</span> <span m="1736410">times</span> <span m="1736720">and</span>
  <span m="1736850">Mi</span> <span m="1736990">transpose,</span> <span m="1737890">now</span>
  <span m="1738130">this</span> <span m="1738340">guy</span> <span m="1738550">becomes</span>
  <span m="1738910">[? X1 ?]</span> <span m="1739090">[INAUDIBLE]</span> <span m="1739270">it's</span>
  <span m="1739420">here.</span> <span m="1740300">And</span> <span m="1740400">so</span>
  <span m="1740430">now,</span> <span m="1740580">I</span> <span m="1740680">really</span>
  <span m="1741040">have</span> <span m="1741340">X1</span> <span m="1742060">times</span>
  <span m="1742690">X1</span> <span m="1742990">transpose.</span> <span m="1743830">So</span>
  <span m="1743980">this</span> <span m="1744220">is</span> <span m="1744340">really</span>
  <span m="1744640">just</span> <span m="1744910">the</span> <span m="1745040">sum</span>
  <span m="1746266">from</span> <span m="1746640">i equal</span> <span m="1746930">1</span>
  <span m="1747370">to</span> <span m="1747510">n</span> <span m="1749050">of</span>
  <span m="1750790">Xi</span> <span m="1752560">Xi</span> <span m="1752920">transpose,</span>
  <span m="1758730">just</span> <span m="1758880">because</span> <span m="1759160">Mi</span>
  <span m="1759370">Mi</span> <span m="1759740">transpose</span> <span m="1760080">is</span>
  <span m="1760310">Xi</span> <span m="1760490">Xi</span> <span m="1760890">transpose.</span>
  <span m="1762030">There's</span> <span m="1762180">nothing</span> <span m="1762510">else</span>
  <span m="1762720">there.</span></p><p><span m="1766190">So</span> <span m="1766960">that's</span>
  <span m="1767230">the</span> <span m="1767290">good</span> <span m="1767470">news,</span>
  <span m="1767790">right?</span> <span m="1768520">This</span> <span m="1768730">term</span>
  <span m="1768970">here</span> <span m="1770050">is</span> <span m="1770230">really</span>
  <span m="1770560">just</span> <span m="1774130">X</span> <span m="1774940">transpose</span>
  <span m="1775600">X</span> <span m="1776260">divided</span> <span m="1776650">by</span>
  <span m="1776860">n.</span> <span m="1783460">OK,</span> <span m="1783700">I</span>
  <span m="1783790">can</span> <span m="1784060">use</span> <span m="1784270">that</span>
  <span m="1784550">guy again,</span> <span m="1785080">I</span> <span m="1785200">guess.</span>
  <span m="1785740">Well,</span> <span m="1785920">no.</span> <span m="1786260">Let's</span>
  <span m="1786440">just--</span> <span m="1797780">OK,</span> <span m="1798040">so
  let</span> <span m="1798340">me</span> <span m="1798430">rewrite</span> <span m="1798880">S.</span>
  <span m="1808740">All</span> <span m="1808800">right,</span> <span m="1808930">that's</span>
  <span m="1809170">the</span> <span m="1809290">definition</span> <span m="1809860">we</span>
  <span m="1810010">have.</span></p><p><span m="1810310">And</span> <span m="1810430">we</span>
  <span m="1810550">know</span> <span m="1810700">that</span> <span m="1810880">this</span>
  <span m="1811120">guy</span> <span m="1811390">already</span> <span m="1812290">is</span>
  <span m="1812500">equal</span> <span m="1812980">to</span> <span m="1813160">1</span>
  <span m="1813400">over</span> <span m="1813670">n</span> <span m="1814630">X</span>
  <span m="1814990">transpose</span> <span m="1815570">X.</span> <span m="1818724">x</span>
  <span m="1819190">bar</span> <span m="1819820">x</span> <span m="1820040">bar</span>
  <span m="1820210">transpose--</span> <span m="1820960">we</span> <span m="1821170">know</span>
  <span m="1821350">that</span> <span m="1821560">x</span> <span m="1821800">bar--</span>
  <span m="1822130">we</span> <span m="1822280">just</span> <span m="1822520">proved</span>
  <span m="1823120">that</span> <span m="1823330">x</span> <span m="1823540">bar--</span>
  <span m="1825950">sorry,</span> <span m="1826670">little</span> <span m="1827030">x</span>
  <span m="1827240">bar</span> <span m="1827840">was</span> <span m="1828050">equal</span>
  <span m="1828530">to</span> <span m="1830840">1</span> <span m="1831080">over</span>
  <span m="1831280">n</span> <span m="1833680">X</span> <span m="1833930">bar</span>
  <span m="1834140">transpose</span> <span m="1835130">times</span> <span m="1835430">the</span>
  <span m="1835520">all-ones</span> <span m="1835640">vector.</span> <span m="1836870">So</span>
  <span m="1836990">I'm</span> <span m="1837080">just</span> <span m="1837230">going</span>
  <span m="1837380">to</span> <span m="1837470">do</span> <span m="1837620">that.</span></p><p><span
  m="1837860">So</span> <span m="1838040">that's</span> <span m="1838310">just</span>
  <span m="1838520">going</span> <span m="1838640">to</span> <span m="1838730">be</span>
  <span m="1838880">minus.</span> <span m="1839340">I'm</span> <span m="1839420">going</span>
  <span m="1839540">to</span> <span m="1839600">pull</span> <span m="1839840">my</span>
  <span m="1840060">two</span> <span m="1840240">1</span> <span m="1840440">over</span>
  <span m="1840500">n's--</span> <span m="1841250">one</span> <span m="1841400">from</span>
  <span m="1841580">this guy,</span> <span m="1841880">one</span> <span m="1842060">from</span>
  <span m="1842240">this</span> <span m="1842420">guy.</span> <span m="1842540">So</span>
  <span m="1842660">I'm</span> <span m="1842720">going</span> <span m="1842840">to</span>
  <span m="1842900">get</span> <span m="1843020">1</span> <span m="1843170">over</span>
  <span m="1843320">n</span> <span m="1843440">squared.</span> <span m="1844530">And</span>
  <span m="1844630">then</span> <span m="1844670">I'm</span> <span m="1844760">going</span>
  <span m="1844870">to</span> <span m="1844980">get</span> <span m="1846080">X</span>
  <span m="1846370">bar--</span> <span m="1847070">sorry,</span> <span m="1847280">there's</span>
  <span m="1847480">no</span> <span m="1847670">X</span> <span m="1848120">bar</span>
  <span m="1848420">here.</span> <span m="1848690">It's</span> <span m="1848810">just</span>
  <span m="1849090">X.</span> <span m="1849420">Yeah.</span> <span m="1850908">X</span>
  <span m="1851900">transpose</span> <span m="1852650">all</span> <span m="1852890">ones</span>
  <span m="1854060">times</span> <span m="1854480">X</span> <span m="1855470">transpose</span>
  <span m="1856130">all</span> <span m="1856400">ones</span> <span m="1857480">transpose,</span>
  <span m="1859892">right?</span></p><p><span m="1864580">And</span> <span m="1865640">X</span>
  <span m="1865870">transpose</span> <span m="1866410">all</span> <span m="1866590">ones</span>
  <span m="1866860">transpose--</span> <span m="1871800">right,</span> <span m="1872000">the</span>
  <span m="1872130">rule--</span> <span m="1872370">if</span> <span m="1872520">I</span>
  <span m="1872610">have</span> <span m="1872910">A</span> <span m="1873090">times</span>
  <span m="1873420">B</span> <span m="1873600">transpose,</span> <span m="1874200">it's</span>
  <span m="1874370">B</span> <span m="1874530">transpose</span> <span m="1875070">times</span>
  <span m="1875310">A</span> <span m="1875430">transpose,</span> <span m="1876000">right?</span>
  <span m="1883460">That's</span> <span m="1883610">just</span> <span m="1883740">the</span>
  <span m="1883860">rule</span> <span m="1884100">of</span> <span m="1884190">transposition.</span>
  <span m="1885060">So</span> <span m="1885120">this</span> <span m="1885360">is</span>
  <span m="1887180">1</span> <span m="1887390">transpose</span> <span m="1889490">X</span>
  <span m="1889710">transpose.</span> <span m="1891400">And</span> <span m="1891420">so</span>
  <span m="1891570">when</span> <span m="1891720">I</span> <span m="1891810">put</span>
  <span m="1892080">all</span> <span m="1892230">these</span> <span m="1892410">guys</span>
  <span m="1892650">together,</span> <span m="1894120">this</span> <span m="1894300">is</span>
  <span m="1894420">actually</span> <span m="1894720">equal</span> <span m="1895020">to</span>
  <span m="1895200">1</span> <span m="1895360">over</span> <span m="1895450">n</span>
  <span m="1896440">X</span> <span m="1896910">transpose</span> <span m="1897420">X</span>
  <span m="1897720">minus</span> <span m="1898230">one over</span> <span m="1898500">n</span>
  <span m="1898710">squared</span> <span m="1899910">X</span> <span m="1900150">transpose</span>
  <span m="1901380">1,</span> <span m="1901680">1</span> <span m="1901890">transpose</span>
  <span m="1905220">X.</span> <span m="1907280">Because</span> <span m="1907520">X</span>
  <span m="1907670">transpose</span> <span m="1908120">transposes</span> <span m="1908750">X,</span>
  <span m="1910004">OK?</span></p><p><span m="1913700">So</span> <span m="1913850">now,</span>
  <span m="1915200">I</span> <span m="1915290">can</span> <span m="1915500">actually--</span>
  <span m="1915950">I have</span> <span m="1916130">something</span> <span m="1916490">which</span>
  <span m="1916640">is</span> <span m="1916760">of</span> <span m="1916850">the</span>
  <span m="1916970">form,</span> <span m="1917390">X</span> <span m="1917630">transpose</span>
  <span m="1919010">X--</span> <span m="1919435">[INAUDIBLE]</span> <span m="1919860">to</span>
  <span m="1920090">the</span> <span m="1920180">left,</span> <span m="1920450">X</span>
  <span m="1920600">transpose;</span> <span m="1921050">to</span> <span m="1921140">the</span>
  <span m="1921260">right,</span> <span m="1921520">X.</span> <span m="1921800">Here,
  I</span> <span m="1921980">have</span> <span m="1922220">X</span> <span m="1922520">transpose</span>
  <span m="1922630">to</span> <span m="1922850">the</span> <span m="1922970">left,</span>
  <span m="1923690">X</span> <span m="1923900">to</span> <span m="1923990">the</span>
  <span m="1924110">right.</span> <span m="1924930">So</span> <span m="1925030">it</span>
  <span m="1925130">can</span> <span m="1925220">factor</span> <span m="1925790">out</span>
  <span m="1926090">whatever's</span> <span m="1926540">in</span> <span m="1926660">there.</span>
  <span m="1927690">So</span> <span m="1927710">I</span> <span m="1927750">can</span>
  <span m="1927950">write</span> <span m="1928370">S</span> <span m="1928850">as</span>
  <span m="1929840">1</span> <span m="1930050">over</span> <span m="1930290">n--</span>
  <span m="1931640">sorry,</span> <span m="1931870">X</span> <span m="1932170">transpose</span>
  <span m="1934060">times</span> <span m="1935000">1</span> <span m="1935260">over</span>
  <span m="1935470">n</span> <span m="1935650">times</span> <span m="1935920">the</span>
  <span m="1936040">identity</span> <span m="1936880">of</span> <span m="1937090">Rd.</span>
  <span m="1941610">And</span> <span m="1941760">then</span> <span m="1941940">I</span>
  <span m="1942000">have</span> <span m="1942210">minus</span> <span m="1943680">1</span>
  <span m="1943980">over</span> <span m="1944200">n,</span> <span m="1944615">1,</span>
  <span m="1945030">1</span> <span m="1945260">transpose</span> <span m="1948816">X.</span></p><p><span
  m="1953110">OK,</span> <span m="1953350">because</span> <span m="1953680">if</span>
  <span m="1953860">you--</span> <span m="1954490">I</span> <span m="1954660">mean,</span>
  <span m="1955310">you</span> <span m="1955360">can</span> <span m="1955540">distribute</span>
  <span m="1956080">it</span> <span m="1956200">back,</span> <span m="1956560">right?</span>
  <span m="1956770">So</span> <span m="1956950">here,</span> <span m="1957160">I'm</span>
  <span m="1957280">going</span> <span m="1957400">to</span> <span m="1957460">get</span>
  <span m="1957670">what?</span> <span m="1958090">X</span> <span m="1958300">transpose</span>
  <span m="1959290">identity</span> <span m="1960010">times</span> <span m="1960340">X,</span>
  <span m="1960640">the</span> <span m="1960760">whole</span> <span m="1960910">thing</span>
  <span m="1961090">divided</span> <span m="1961390">by</span> <span m="1961540">n.</span>
  <span m="1961810">That's</span> <span m="1961990">this</span> <span m="1962140">term.</span>
  <span m="1962890">And</span> <span m="1963010">then</span> <span m="1963130">the</span>
  <span m="1963250">second</span> <span m="1963550">one</span> <span m="1963790">is</span>
  <span m="1963880">going</span> <span m="1964060">to</span> <span m="1964120">be--</span>
  <span m="1964300">sorry,</span> <span m="1964660">1</span> <span m="1964840">over</span>
  <span m="1964990">n</span> <span m="1965110">squared.</span> <span m="1966110">And</span>
  <span m="1966160">then</span> <span m="1966310">I'm</span> <span m="1966400">going</span>
  <span m="1966520">to</span> <span m="1966580">get</span> <span m="1966820">1</span>
  <span m="1966970">over</span> <span m="1967120">n</span> <span m="1967240">squared</span>
  <span m="1967570">times</span> <span m="1969540">X</span> <span m="1969790">transpose</span>
  <span m="1970600">1,</span> <span m="1970840">1</span> <span m="1971020">transpose</span>
  <span m="1971600">which</span> <span m="1971680">is</span> <span m="1971800">this</span>
  <span m="1972010">guy,</span> <span m="1972800">times</span> <span m="1973240">X,</span>
  <span m="1973990">and</span> <span m="1974140">that's</span> <span m="1974320">the</span>
  <span m="1974440">[? right ?]</span> <span m="1974590">[? thing, ?]</span> <span
  m="1975692">OK?</span></p><p><span m="1978580">So,</span> <span m="1979170">the</span>
  <span m="1979320">way</span> <span m="1979440">it's</span> <span m="1979590">written,</span>
  <span m="1980100">I</span> <span m="1980490">factored</span> <span m="1981000">out</span>
  <span m="1981210">one of the</span> <span m="1981555">1</span> <span m="1981900">over</span>
  <span m="1982020">n's.</span> <span m="1982320">So</span> <span m="1982530">I'm</span>
  <span m="1982620">just</span> <span m="1982800">going</span> <span m="1982950">to</span>
  <span m="1983010">do</span> <span m="1983160">the</span> <span m="1983250">same</span>
  <span m="1983520">thing</span> <span m="1984660">as</span> <span m="1984840">on</span>
  <span m="1984990">this</span> <span m="1985110">slide.</span> <span m="1985500">So</span>
  <span m="1985650">I'm</span> <span m="1985770">just</span> <span m="1986040">factoring</span>
  <span m="1986610">out</span> <span m="1986970">this</span> <span m="1987270">1</span>
  <span m="1987450">over</span> <span m="1987630">n</span> <span m="1987780">here.</span>
  <span m="1988110">So</span> <span m="1988260">it's</span> <span m="1988410">1</span>
  <span m="1988620">over</span> <span m="1988670">n</span> <span m="1989430">times</span>
  <span m="1990630">X</span> <span m="1992770">transpose</span> <span m="1995040">identity</span>
  <span m="1996280">of our</span> <span m="1996540">d</span> <span m="1997230">divided</span>
  <span m="1997620">by</span> <span m="1997860">n</span> <span m="1999450">divided</span>
  <span m="1999810">by</span> <span m="1999990">1</span> <span m="2000200">this</span>
  <span m="2000380">time,</span> <span m="2001010">minus</span> <span m="2001340">1</span>
  <span m="2001520">over</span> <span m="2001760">n</span> <span m="2002560">1,</span>
  <span m="2002960">1</span> <span m="2003470">transpose</span> <span m="2005076">times</span>
  <span m="2005470">X,</span> <span m="2006432">OK?</span> <span m="2006780">So</span>
  <span m="2007140">that's</span> <span m="2007320">just</span> <span m="2007530">what's</span>
  <span m="2007700">on</span> <span m="2007830">the</span> <span m="2007920">slides.</span></p><p><span
  m="2011720">What</span> <span m="2011870">does</span> <span m="2011960">the</span>
  <span m="2012080">matrix,</span> <span m="2012770">1,</span> <span m="2013130">1</span>
  <span m="2013190">transpose,</span> <span m="2013640">look</span> <span m="2013820">like?</span></p><p><span
  m="2015874">AUDIENCE:</span> <span m="2016026">All</span> <span m="2016178">1's.</span></p><p><span
  m="2016790">PHILIPPE RIGOLLET:</span> <span m="2016860">It's</span> <span m="2016930">just</span>
  <span m="2017170">all</span> <span m="2017350">1's,</span> <span m="2017620">right?</span>
  <span m="2017980">Because</span> <span m="2018220">the</span> <span m="2018340">entries</span>
  <span m="2019210">are</span> <span m="2019380">the</span> <span m="2019530">products</span>
  <span m="2020050">of</span> <span m="2020200">the all-ones--</span> <span m="2021060">of</span>
  <span m="2021220">the</span> <span m="2021340">coordinates</span> <span m="2021820">of</span>
  <span m="2021940">the</span> <span m="2022030">all-ones</span> <span m="2022240">vectors</span>
  <span m="2022630">with</span> <span m="2022750">the</span> <span m="2022840">coordinates</span>
  <span m="2023290">of</span> <span m="2023380">the</span> <span m="2023470">all-ones</span>
  <span m="2023710">vectors,</span> <span m="2024280">so</span> <span m="2024370">I</span>
  <span m="2024400">only</span> <span m="2024610">get</span> <span m="2024850">1's.</span>
  <span m="2025120">So</span> <span m="2025210">it's</span> <span m="2026050">a</span>
  <span m="2026110">d</span> <span m="2026440">by</span> <span m="2026650">d</span>
  <span m="2026950">matrix</span> <span m="2027490">with</span> <span m="2027640">only</span>
  <span m="2027920">1's.</span> <span m="2029610">So</span> <span m="2029830">this</span>
  <span m="2030100">matrix,</span> <span m="2030550">I</span> <span m="2030610">can</span>
  <span m="2030760">actually</span> <span m="2031090">write</span> <span m="2031360">exactly,</span>
  <span m="2031900">right?</span> <span m="2032170">H,</span> <span m="2034240">this</span>
  <span m="2034420">matrix</span> <span m="2034810">that</span> <span m="2034930">I</span>
  <span m="2034990">called</span> <span m="2035260">H</span> <span m="2035530">which</span>
  <span m="2035710">is</span> <span m="2035860">what's</span> <span m="2036370">sandwiched</span>
  <span m="2037030">in-between</span> <span m="2037480">this</span> <span m="2037660">X
  transpose</span> <span m="2038200">and</span> <span m="2038290">X.</span> <span
  m="2039430">By</span> <span m="2039550">definition,</span> <span m="2040180">I</span>
  <span m="2040270">said</span> <span m="2040480">this</span> <span m="2040660">is</span>
  <span m="2040810">the</span> <span m="2040900">definition</span> <span m="2041320">of</span>
  <span m="2041470">H.</span> <span m="2042540">Then</span> <span m="2042760">this</span>
  <span m="2043000">thing,</span> <span m="2044380">I</span> <span m="2044470">can</span>
  <span m="2044710">write</span> <span m="2045000">its coordinates</span> <span m="2045700">exactly.</span></p><p><span
  m="2058880">We</span> <span m="2059000">know</span> <span m="2059179">it's</span>
  <span m="2060020">identity</span> <span m="2061420">divided</span> <span m="2061820">by</span>
  <span m="2062030">n</span> <span m="2062300">minus--</span> <span m="2063110">sorry,</span>
  <span m="2063800">I</span> <span m="2063830">don't</span> <span m="2063980">know</span>
  <span m="2064070">why</span> <span m="2064260">I</span> <span m="2064330">keep</span>
  <span m="2064520">[INAUDIBLE].</span> <span m="2065330">Minus</span> <span m="2065719">1</span>
  <span m="2065920">over n</span> <span m="2066989">1,</span> <span m="2067500">1</span>
  <span m="2067820">transpose--</span> <span m="2069110">so</span> <span m="2069320">it's</span>
  <span m="2069500">this</span> <span m="2069679">matrix</span> <span m="2070130">with</span>
  <span m="2070239">the</span> <span m="2070350">only</span> <span m="2070610">1's</span>
  <span m="2070940">on</span> <span m="2071060">the</span> <span m="2071150">diagonals</span>
  <span m="2071719">and</span> <span m="2071840">0's</span> <span m="2072239">and</span>
  <span m="2072300">elsewhere--</span> <span m="2073100">minus</span> <span m="2073670">a</span>
  <span m="2073760">matrix</span> <span m="2074210">that</span> <span m="2074389">only</span>
  <span m="2074690">has</span> <span m="2074900">1</span> <span m="2075110">over</span>
  <span m="2075320">n</span> <span m="2075469">everywhere.</span> <span m="2081469">OK,</span>
  <span m="2081739">so</span> <span m="2081889">the</span> <span m="2082010">whole</span>
  <span m="2082190">thing</span> <span m="2084000">is</span> <span m="2085080">1</span>
  <span m="2085350">minus</span> <span m="2085770">1</span> <span m="2085949">over</span>
  <span m="2086190">n</span> <span m="2086340">on</span> <span m="2086429">the</span>
  <span m="2086550">diagonals</span> <span m="2089820">and</span> <span m="2089969">then</span>
  <span m="2090389">minus</span> <span m="2090810">1</span> <span m="2090989">over</span>
  <span m="2091199">n</span> <span m="2091350">here,</span> <span m="2095478">OK?</span></p><p><span
  m="2097430">And</span> <span m="2097520">now</span> <span m="2097660">I</span> <span
  m="2097770">claim</span> <span m="2098090">that</span> <span m="2098240">this</span>
  <span m="2098420">matrix</span> <span m="2098810">is an</span> <span m="2098930">orthogonal</span>
  <span m="2099410">projector.</span> <span m="2101920">Now,</span> <span m="2102820">I'm</span>
  <span m="2102940">writing</span> <span m="2103270">this,</span> <span m="2104350">but</span>
  <span m="2104380">it's</span> <span m="2104530">completely</span> <span m="2105040">useless.</span>
  <span m="2105580">This</span> <span m="2105760">is</span> <span m="2105910">just</span>
  <span m="2106170">a</span> <span m="2106240">way</span> <span m="2106420">for</span>
  <span m="2106570">you</span> <span m="2106690">to</span> <span m="2106840">see</span>
  <span m="2107050">that</span> <span m="2107230">it's</span> <span m="2107380">actually</span>
  <span m="2107770">very</span> <span m="2108190">convenient</span> <span m="2108940">now</span>
  <span m="2109890">to</span> <span m="2110080">think</span> <span m="2110380">about</span>
  <span m="2110770">this</span> <span m="2110950">problem</span> <span m="2111430">as</span>
  <span m="2111580">being</span> <span m="2113500">a</span> <span m="2113530">matrix</span>
  <span m="2113980">problem,</span> <span m="2114340">because</span> <span m="2114610">things</span>
  <span m="2114850">are</span> <span m="2114970">much</span> <span m="2115240">nicer</span>
  <span m="2115600">when</span> <span m="2115750">you</span> <span m="2115870">think</span>
  <span m="2116110">about</span> <span m="2116800">the</span> <span m="2116950">actual</span>
  <span m="2117460">form</span> <span m="2117910">of</span> <span m="2118000">your</span>
  <span m="2118150">matrices,</span> <span m="2118700">right?</span> <span m="2118890">They</span>
  <span m="2118960">could</span> <span m="2119110">tell</span> <span m="2119320">you,</span>
  <span m="2119890">here</span> <span m="2120100">is</span> <span m="2120220">the</span>
  <span m="2120310">matrix.</span></p><p><span m="2121090">I</span> <span m="2121150">mean,</span>
  <span m="2121300">imagine</span> <span m="2121750">you're</span> <span m="2121930">sitting</span>
  <span m="2122260">at</span> <span m="2122350">a</span> <span m="2122410">midterm,</span>
  <span m="2123340">and</span> <span m="2123430">I</span> <span m="2123490">say,</span>
  <span m="2123970">here's</span> <span m="2124150">the</span> <span m="2124270">matrix</span>
  <span m="2124750">that</span> <span m="2124870">has</span> <span m="2125260">1</span>
  <span m="2125470">minus</span> <span m="2125770">1</span> <span m="2125910">over</span>
  <span m="2126010">n</span> <span m="2126190">on</span> <span m="2126290">the</span>
  <span m="2126350">diagonals</span> <span m="2126910">and</span> <span m="2127060">minus</span>
  <span m="2127390">1</span> <span m="2127540">over</span> <span m="2127720">n</span>
  <span m="2128640">on</span> <span m="2128770">the</span> <span m="2128860">[INAUDIBLE]</span>
  <span m="2128980">diagonal.</span> <span m="2130010">Prove</span> <span m="2130300">to</span>
  <span m="2130420">me</span> <span m="2130600">that</span> <span m="2130750">it's</span>
  <span m="2130940">a</span> <span m="2132360">projector</span> <span m="2132760">matrix.</span>
  <span m="2133210">You're</span> <span m="2133360">going</span> <span m="2133480">to</span>
  <span m="2133540">have</span> <span m="2133690">to</span> <span m="2133810">basically</span>
  <span m="2134230">take</span> <span m="2134440">this</span> <span m="2134620">guy</span>
  <span m="2134860">times</span> <span m="2135130">itself.</span> <span m="2135520">It's</span>
  <span m="2135640">going</span> <span m="2135790">to</span> <span m="2135850">be</span>
  <span m="2135940">really</span> <span m="2136360">complicated,</span> <span m="2137020">right?</span>
  <span m="2137590">So</span> <span m="2137710">we</span> <span m="2137800">know</span>
  <span m="2137980">it's</span> <span m="2138100">symmetric.</span> <span m="2138580">That's</span>
  <span m="2138760">for</span> <span m="2138880">sure.</span></p><p><span m="2139930">But</span>
  <span m="2140320">the</span> <span m="2140440">fact</span> <span m="2140710">that</span>
  <span m="2140850">it</span> <span m="2140940">has</span> <span m="2141190">this</span>
  <span m="2141370">particular</span> <span m="2141880">way</span> <span m="2142120">of</span>
  <span m="2142240">writing</span> <span m="2142600">it</span> <span m="2143200">is</span>
  <span m="2143320">going</span> <span m="2143440">to</span> <span m="2143530">make</span>
  <span m="2143710">my</span> <span m="2143890">life</span> <span m="2144100">super</span>
  <span m="2144430">easy</span> <span m="2144700">to</span> <span m="2144820">check</span>
  <span m="2145270">this.</span> <span m="2145810">That's</span> <span m="2146020">the</span>
  <span m="2146080">definition</span> <span m="2146560">of</span> <span m="2146630">a</span>
  <span m="2146650">projector.</span> <span m="2147140">It</span> <span m="2147220">has</span>
  <span m="2147400">to</span> <span m="2147490">be</span> <span m="2147580">symmetric</span>
  <span m="2148470">and</span> <span m="2148570">it</span> <span m="2148690">has</span>
  <span m="2148930">to</span> <span m="2149770">square</span> <span m="2150150">to</span>
  <span m="2150250">itself</span> <span m="2150700">because</span> <span m="2150940">we</span>
  <span m="2151060">just</span> <span m="2151270">said</span> <span m="2152010">in</span>
  <span m="2152950">the</span> <span m="2153070">chapter</span> <span m="2153460">on</span>
  <span m="2153550">linear</span> <span m="2153790">regression</span> <span m="2154300">that</span>
  <span m="2154950">once</span> <span m="2155200">you</span> <span m="2155290">project,</span>
  <span m="2155980">if</span> <span m="2156130">you</span> <span m="2156220">apply</span>
  <span m="2156530">the</span> <span m="2156580">projection</span> <span m="2157090">again,</span>
  <span m="2157360">you're</span> <span m="2157480">not</span> <span m="2157630">moving</span>
  <span m="2157990">because</span> <span m="2158200">you're</span> <span m="2158350">already</span>
  <span m="2158650">there.</span></p><p><span m="2159610">OK,</span> <span m="2159850">so</span>
  <span m="2160150">why</span> <span m="2160420">is</span> <span m="2160680">H squared</span>
  <span m="2162040">equal</span> <span m="2162370">to</span> <span m="2162610">H?</span>
  <span m="2164500">Well</span> <span m="2164700">let's</span> <span m="2164830">just</span>
  <span m="2165060">write H</span> <span m="2165430">square.</span> <span m="2165760">It's</span>
  <span m="2165940">the</span> <span m="2166060">identity</span> <span m="2167590">minus</span>
  <span m="2168010">1</span> <span m="2168190">over</span> <span m="2168430">n</span>
  <span m="2168790">1,</span> <span m="2169150">1</span> <span m="2169300">transpose</span>
  <span m="2170980">times</span> <span m="2171280">the</span> <span m="2171400">identity</span>
  <span m="2172750">minus</span> <span m="2173200">1 over</span> <span m="2173530">n</span>
  <span m="2176270">1, 1</span> <span m="2176610">transpose,</span> <span m="2177090">right?</span>
  <span m="2179370">Let's</span> <span m="2179580">just</span> <span m="2179820">expand</span>
  <span m="2180300">this</span> <span m="2180540">now.</span> <span m="2182490">This</span>
  <span m="2182670">is</span> <span m="2182880">equal</span> <span m="2183300">to</span>
  <span m="2183510">the</span> <span m="2183660">identity</span> <span m="2185040">minus--</span>
  <span m="2185350">well,</span> <span m="2185660">the</span> <span m="2186030">identity</span>
  <span m="2186600">times</span> <span m="2186930">1,</span> <span m="2187100">1</span>
  <span m="2187230">transpose</span> <span m="2187690">is</span> <span m="2187830">just</span>
  <span m="2188040">the</span> <span m="2188130">identity.</span> <span m="2189280">So</span>
  <span m="2190370">it's</span> <span m="2190800">1,</span> <span m="2191090">1</span>
  <span m="2191250">transpose,</span> <span m="2191740">sorry.</span> <span m="2191900">So</span>
  <span m="2192180">1</span> <span m="2192360">over</span> <span m="2192450">n</span>
  <span m="2193400">1, 1</span> <span m="2193830">transpose</span> <span m="2194670">minus</span>
  <span m="2195270">1</span> <span m="2195450">over</span> <span m="2195720">n</span>
  <span m="2196980">1,</span> <span m="2197270">1</span> <span m="2197430">transpose.</span></p><p><span
  m="2198840">And</span> <span m="2198960">then</span> <span m="2199170">there's</span>
  <span m="2199350">going</span> <span m="2199500">to</span> <span m="2199590">be</span>
  <span m="2199830">what</span> <span m="2200400">makes</span> <span m="2200700">the</span>
  <span m="2200820">deal</span> <span m="2201240">is</span> <span m="2201360">that</span>
  <span m="2201570">I</span> <span m="2201720">get</span> <span m="2201930">this</span>
  <span m="2202140">1</span> <span m="2202320">over</span> <span m="2202560">n</span>
  <span m="2202710">squared</span> <span m="2203070">this</span> <span m="2203250">time.</span>
  <span m="2204750">And</span> <span m="2204840">then</span> <span m="2204990">I</span>
  <span m="2205080">get</span> <span m="2205200">the</span> <span m="2205320">product</span>
  <span m="2205770">of</span> <span m="2205890">1</span> <span m="2206100">over</span>
  <span m="2206200">n</span> <span m="2206470">trans--</span> <span m="2207030">oh,</span>
  <span m="2207150">let's</span> <span m="2207360">write</span> <span m="2207570">it</span>
  <span m="2207660">completely.</span> <span m="2208200">I</span> <span m="2208260">get</span>
  <span m="2208920">1,</span> <span m="2209650">1</span> <span m="2210060">transpose</span>
  <span m="2211080">times</span> <span m="2211410">1,</span> <span m="2212300">1</span>
  <span m="2212550">transpose,</span> <span m="2215106">OK?</span></p><p><span m="2218010">But</span>
  <span m="2218190">this</span> <span m="2218460">thing</span> <span m="2218700">here--</span>
  <span m="2221260">what</span> <span m="2221400">is</span> <span m="2221550">this?</span>
  <span m="2223840">n,</span> <span m="2224050">right,</span> <span m="2224320">is</span>
  <span m="2224410">the</span> <span m="2224560">end</span> <span m="2224680">product</span>
  <span m="2225160">of</span> <span m="2225970">the</span> <span m="2226090">all-ones</span>
  <span m="2226360">vector</span> <span m="2226660">with</span> <span m="2226780">the</span>
  <span m="2226870">all-ones</span> <span m="2227140">vector.</span> <span m="2227400">So</span>
  <span m="2227500">I'm</span> <span m="2227590">just</span> <span m="2227800">summing</span>
  <span m="2228250">n</span> <span m="2228430">times</span> <span m="2228790">1</span>
  <span m="2228970">squared,</span> <span m="2229490">which</span> <span m="2229600">is</span>
  <span m="2230010">n.</span> <span m="2230740">So</span> <span m="2230860">this</span>
  <span m="2231040">is</span> <span m="2231220">equal</span> <span m="2231550">to</span>
  <span m="2231760">n.</span> <span m="2231980">So</span> <span m="2232160">I</span>
  <span m="2232250">pull</span> <span m="2232510">it</span> <span m="2232630">out,</span>
  <span m="2232990">cancel</span> <span m="2233320">one</span> <span m="2233470">of</span>
  <span m="2233590">the</span> <span m="2233680">ends,</span> <span m="2233920">and</span>
  <span m="2234040">I'm</span> <span m="2234220">back</span> <span m="2234490">to</span>
  <span m="2234640">what</span> <span m="2234790">I</span> <span m="2234880">had</span>
  <span m="2235030">before.</span> <span m="2235870">So</span> <span m="2235990">I</span>
  <span m="2236050">had</span> <span m="2236440">identity</span> <span m="2237860">minus</span>
  <span m="2238260">2</span> <span m="2238540">over</span> <span m="2238870">n</span>
  <span m="2239850">1,</span> <span m="2240180">1</span> <span m="2240400">transpose</span>
  <span m="2241090">plus</span> <span m="2241540">1</span> <span m="2241720">over</span>
  <span m="2241990">n</span> <span m="2243181">1,</span> <span m="2243580">1</span>
  <span m="2243760">transpose</span> <span m="2245350">which is</span> <span m="2245530">equal</span>
  <span m="2245920">to</span> <span m="2246110">H.</span> <span m="2247530">Because</span>
  <span m="2248160">one</span> <span m="2248340">of</span> <span m="2248460">the</span>
  <span m="2248580">1</span> <span m="2249030">over</span> <span m="2249290">n's</span>
  <span m="2249600">cancel,</span> <span m="2250380">OK?</span></p><p><span m="2256370">So</span>
  <span m="2256470">it's</span> <span m="2256590">a</span> <span m="2256650">projection</span>
  <span m="2257100">matrix.</span> <span m="2257430">It's</span> <span m="2257550">projecting</span>
  <span m="2258060">onto</span> <span m="2258330">some linear</span> <span m="2258960">space,</span>
  <span m="2259320">right?</span> <span m="2261030">It's</span> <span m="2261200">taking</span>
  <span m="2261570">a</span> <span m="2261630">matrix.</span> <span m="2262450">Sorry,</span>
  <span m="2262580">it's</span> <span m="2262740">taking a</span> <span m="2263130">vector</span>
  <span m="2264040">and it's</span> <span m="2264480">projecting</span> <span m="2265140">onto</span>
  <span m="2265530">a</span> <span m="2265560">certain</span> <span m="2265830">space</span>
  <span m="2266160">of</span> <span m="2266250">vectors.</span> <span m="2269255">What
  is this</span> <span m="2269742">space?</span> <span m="2273160">Right,</span> <span
  m="2273270">so,</span> <span m="2273810">how</span> <span m="2273960">do</span>
  <span m="2274050">you--</span> <span m="2274310">so</span> <span m="2274500">I'm</span>
  <span m="2274650">only</span> <span m="2274920">asking</span> <span m="2275790">the</span>
  <span m="2275880">answer</span> <span m="2276090">to</span> <span m="2276170">this</span>
  <span m="2276270">question</span> <span m="2276630">in</span> <span m="2276780">words,</span>
  <span m="2277200">right?</span> <span m="2277500">So</span> <span m="2278340">how</span>
  <span m="2278460">would</span> <span m="2278610">you</span> <span m="2278670">describe</span>
  <span m="2279180">the</span> <span m="2279300">vectors</span> <span m="2279830">onto</span>
  <span m="2280080">which</span> <span m="2280290">this</span> <span m="2280440">matrix</span>
  <span m="2280830">is</span> <span m="2280920">projecting?</span></p><p><span m="2282950">Well,</span>
  <span m="2283430">if</span> <span m="2283580">you</span> <span m="2283670">want</span>
  <span m="2283850">to</span> <span m="2284090">answer</span> <span m="2284330">this</span>
  <span m="2284510">question,</span> <span m="2285050">the</span> <span m="2285170">way</span>
  <span m="2285320">you</span> <span m="2285440">would</span> <span m="2285590">tackle</span>
  <span m="2285980">it</span> <span m="2286100">is</span> <span m="2286220">first</span>
  <span m="2286520">by</span> <span m="2286680">saying,</span> <span m="2286920">OK,</span>
  <span m="2287870">what</span> <span m="2288140">does</span> <span m="2288440">a</span>
  <span m="2288500">vector</span> <span m="2289220">which</span> <span m="2289430">is</span>
  <span m="2289580">of</span> <span m="2289730">the</span> <span m="2289850">form,</span>
  <span m="2291710">H</span> <span m="2292040">times</span> <span m="2292680">something,</span>
  <span m="2293690">look</span> <span m="2293900">like,</span> <span m="2294535">right?</span>
  <span m="2294960">What</span> <span m="2295040">can</span> <span m="2295190">I</span>
  <span m="2295250">say</span> <span m="2295370">about</span> <span m="2295580">this</span>
  <span m="2295760">vector</span> <span m="2296700">that's</span> <span m="2296870">going</span>
  <span m="2297020">to</span> <span m="2297080">be</span> <span m="2297440">definitely</span>
  <span m="2297890">giving</span> <span m="2298220">me</span> <span m="2298970">something</span>
  <span m="2299540">about</span> <span m="2300250">the</span> <span m="2300470">space</span>
  <span m="2300800">on</span> <span m="2300920">which</span> <span m="2301100">it</span>
  <span m="2301190">projects?</span> <span m="2301760">I</span> <span m="2301880">need</span>
  <span m="2302030">to</span> <span m="2302150">know</span> <span m="2302360">a</span>
  <span m="2302390">little</span> <span m="2302690">more</span> <span m="2303410">to</span>
  <span m="2303530">know</span> <span m="2303710">that</span> <span m="2303860">it</span>
  <span m="2303950">projects</span> <span m="2304340">exactly</span> <span m="2304800">onto</span>
  <span m="2305030">this.</span></p><p><span m="2305820">But</span> <span m="2307880">one</span>
  <span m="2308090">way</span> <span m="2308210">we</span> <span m="2308300">can</span>
  <span m="2308450">do</span> <span m="2308570">this</span> <span m="2308750">is</span>
  <span m="2308870">just</span> <span m="2309050">see</span> <span m="2309410">how</span>
  <span m="2309650">it</span> <span m="2309740">acts</span> <span m="2309980">on</span>
  <span m="2310070">a</span> <span m="2310130">vector.</span> <span m="2310440">What</span>
  <span m="2310610">does</span> <span m="2310760">it</span> <span m="2310850">do</span>
  <span m="2311060">to</span> <span m="2311220">a</span> <span m="2311270">vector</span>
  <span m="2311600">to</span> <span m="2311750">apply</span> <span m="2312080">H,
  right?</span> <span m="2312370">So</span> <span m="2312740">I</span> <span m="2312860">take</span>
  <span m="2313170">v.</span> <span m="2319260">And</span> <span m="2319440">let's</span>
  <span m="2319610">see</span> <span m="2320210">what</span> <span m="2320580">taking</span>
  <span m="2321050">v</span> <span m="2322010">and</span> <span m="2322250">applying</span>
  <span m="2322760">H</span> <span m="2323060">to</span> <span m="2323330">it</span>
  <span m="2324550">looks</span> <span m="2324790">like.</span></p><p><span m="2326410">Well,</span>
  <span m="2327100">it's</span> <span m="2327280">the</span> <span m="2327430">identity</span>
  <span m="2328000">minus</span> <span m="2328300">something.</span> <span m="2328750">So</span>
  <span m="2328870">it</span> <span m="2328930">takes</span> <span m="2329290">v</span>
  <span m="2329560">and</span> <span m="2329650">it</span> <span m="2329770">removes</span>
  <span m="2330220">something</span> <span m="2330640">from</span> <span m="2330890">v.</span>
  <span m="2332260">What</span> <span m="2332350">does</span> <span m="2332500">it</span>
  <span m="2332590">remove?</span> <span m="2334160">Well,</span> <span m="2334290">it's</span>
  <span m="2334510">1</span> <span m="2334690">over</span> <span m="2334930">n</span>
  <span m="2335140">times</span> <span m="2336400">v</span> <span m="2336790">transpose</span>
  <span m="2337650">1</span> <span m="2340290">times</span> <span m="2340590">the</span>
  <span m="2340680">all-ones</span> <span m="2340980">vector,</span> <span m="2341370">right?</span>
  <span m="2344030">Agreed?</span> <span m="2344360">I</span> <span m="2344420">just</span>
  <span m="2344690">wrote</span> <span m="2346040">v</span> <span m="2346370">transpose</span>
  <span m="2347000">1</span> <span m="2347840">instead</span> <span m="2348140">of</span>
  <span m="2351230">1</span> <span m="2351530">transpose</span> <span m="2352220">v,</span>
  <span m="2353570">which</span> <span m="2353720">are</span> <span m="2353810">the</span>
  <span m="2353930">same</span> <span m="2354110">thing.</span></p><p><span m="2356250">What</span>
  <span m="2356370">is</span> <span m="2356520">this</span> <span m="2356820">thing?</span>
  <span m="2365160">What</span> <span m="2366160">should</span> <span m="2366330">I</span>
  <span m="2366460">call</span> <span m="2366730">it</span> <span m="2366930">in</span>
  <span m="2367030">mathematical</span> <span m="2367510">notation?</span> <span m="2370720">v</span>
  <span m="2370770">bar,</span> <span m="2371220">right?</span> <span m="2371460">I</span>
  <span m="2371550">should</span> <span m="2371700">all it</span> <span m="2371970">v</span>
  <span m="2372150">bar</span> <span m="2372780">because</span> <span m="2373440">this</span>
  <span m="2373620">is</span> <span m="2373770">exactly</span> <span m="2374460">the</span>
  <span m="2374640">average</span> <span m="2375150">of</span> <span m="2375270">the</span>
  <span m="2375420">entries</span> <span m="2375780">of</span> <span m="2375940">v,</span>
  <span m="2377400">agreed?</span> <span m="2378840">This</span> <span m="2379000">is</span>
  <span m="2379240">summing</span> <span m="2379700">the</span> <span m="2379820">entries</span>
  <span m="2380150">of</span> <span m="2380270">v's,</span> <span m="2380640">and</span>
  <span m="2380780">this</span> <span m="2380990">is</span> <span m="2381080">dividing</span>
  <span m="2381560">by</span> <span m="2381710">the</span> <span m="2381830">number</span>
  <span m="2382160">of</span> <span m="2382310">those</span> <span m="2382520">v's.</span>
  <span m="2383170">Sorry,</span> <span m="2383460">now</span> <span m="2383690">v</span>
  <span m="2384050">is</span> <span m="2384320">in</span> <span m="2384500">our--</span>
  <span m="2389162">sorry,</span> <span m="2389640">why do I</span> <span m="2390118">divide
  by--</span> <span m="2393950">I'm</span> <span m="2394110">just--</span> <span m="2394360">OK,</span>
  <span m="2394590">I</span> <span m="2394680">need</span> <span m="2394830">to</span>
  <span m="2394980">check</span> <span m="2395310">what</span> <span m="2395490">my</span>
  <span m="2395760">dimensions</span> <span m="2396360">are</span> <span m="2396510">now.</span>
  <span m="2399070">No,</span> <span m="2399250">it's</span> <span m="2399430">in</span>
  <span m="2399630">Rd,</span> <span m="2400090">right?</span> <span m="2400390">So</span>
  <span m="2401550">why</span> <span m="2401680">do</span> <span m="2401770">I</span>
  <span m="2401830">divide</span> <span m="2402180">by</span> <span m="2402370">n?</span></p><p><span
  m="2405520">So</span> <span m="2405640">it's</span> <span m="2405790">not</span>
  <span m="2405910">really</span> <span m="2406210">v</span> <span m="2406330">bar.</span>
  <span m="2407720">It's</span> <span m="2407840">the</span> <span m="2407960">sum</span>
  <span m="2408230">of</span> <span m="2408350">the</span> <span m="2408500">v's</span>
  <span m="2411860">divided</span> <span m="2412400">by--</span> <span m="2413910">right,</span>
  <span m="2414060">so</span> <span m="2414170">it's</span> <span m="2414350">v</span>
  <span m="2414590">bar.</span></p><p><span m="2424024">AUDIENCE:</span> <span m="2424270">[INAUDIBLE]</span></p><p><span
  m="2425503">[INTERPOSING VOICES]</span></p><p><span m="2425996">AUDIENCE:</span>
  <span m="2426242">Yeah,</span> <span m="2426489">v has to be</span> <span m="2426982">[INAUDIBLE]</span></p><p><span
  m="2427968">PHILIPPE RIGOLLET:</span> <span m="2428132">Oh,</span> <span m="2428296">yeah.</span>
  <span m="2429450">OK,</span> <span m="2429860">thank</span> <span m="2430100">you.</span>
  <span m="2431120">So</span> <span m="2431330">everywhere</span> <span m="2431690">I</span>
  <span m="2431840">wrote</span> <span m="2432180">Hd,</span> <span m="2432760">that</span>
  <span m="2432890">was</span> <span m="2433040">actually Hn.</span> <span m="2434750">Oh,</span>
  <span m="2434960">man.</span> <span m="2435290">I</span> <span m="2435410">wish</span>
  <span m="2435650">I</span> <span m="2435680">had</span> <span m="2435800">a</span>
  <span m="2435860">computer</span> <span m="2436280">now.</span> <span m="2437400">All</span>
  <span m="2437510">right.</span> <span m="2437720">So--</span> <span m="2441130">yeah,</span>
  <span m="2441310">because</span> <span m="2442080">the--</span> <span m="2443230">yeah,</span>
  <span m="2443500">right?</span> <span m="2443740">So</span> <span m="2445360">why</span>
  <span m="2445570">it's</span> <span m="2445720">not--</span> <span m="2446130">well,</span>
  <span m="2446480">why</span> <span m="2446710">I</span> <span m="2446740">thought</span>
  <span m="2446860">it</span> <span m="2446920">was</span> <span m="2447100">this
  is</span> <span m="2447340">because</span> <span m="2447610">I</span> <span m="2447790">was</span>
  <span m="2447940">thinking</span> <span m="2448150">about</span> <span m="2448360">the</span>
  <span m="2448480">outer</span> <span m="2448720">dimension</span> <span m="2449140">of</span>
  <span m="2449230">X,</span> <span m="2449410">really</span> <span m="2449890">of</span>
  <span m="2450070">X</span> <span m="2450190">transpose,</span> <span m="2450620">which</span>
  <span m="2450670">is</span> <span m="2450760">really</span> <span m="2451000">the</span>
  <span m="2451120">inner</span> <span m="2451360">dimension,</span> <span m="2451780">didn't</span>
  <span m="2451930">matter</span> <span m="2452170">to</span> <span m="2452290">me,</span>
  <span m="2452440">right?</span></p><p><span m="2452950">So</span> <span m="2453100">the</span>
  <span m="2453220">thing</span> <span m="2453430">that</span> <span m="2453520">I</span>
  <span m="2453580">can</span> <span m="2453760">sandwich</span> <span m="2454180">between</span>
  <span m="2454480">X transpose</span> <span m="2455080">and</span> <span m="2455170">X
  has</span> <span m="2455620">to</span> <span m="2455710">be</span> <span m="2455860">n</span>
  <span m="2456010">by</span> <span m="2456280">n.</span> <span m="2456790">So</span>
  <span m="2456910">this</span> <span m="2457090">was</span> <span m="2457240">actually</span>
  <span m="2457495">n</span> <span m="2457750">by</span> <span m="2457990">n.</span>
  <span m="2458800">And</span> <span m="2458920">so</span> <span m="2459130">that's</span>
  <span m="2459370">actually</span> <span m="2459880">n</span> <span m="2460060">by</span>
  <span m="2460260">n.</span> <span m="2460480">Everything</span> <span m="2460810">is</span>
  <span m="2460880">n</span> <span m="2461020">by</span> <span m="2461230">n.</span>
  <span m="2463330">Sorry</span> <span m="2463600">about</span> <span m="2463820">that.</span>
  <span m="2468220">So</span> <span m="2468530">this</span> <span m="2468780">is</span>
  <span m="2469010">n.</span> <span m="2469400">This</span> <span m="2469610">is</span>
  <span m="2469850">n.</span> <span m="2470440">This</span> <span m="2470630">is--</span>
  <span m="2470750">well,</span> <span m="2471320">I</span> <span m="2471380">didn't</span>
  <span m="2471590">really</span> <span m="2471830">tell</span> <span m="2472010">you</span>
  <span m="2472130">what</span> <span m="2472670">the</span> <span m="2472790">all-ones</span>
  <span m="2473090">vector</span> <span m="2473420">was,</span> <span m="2474080">but</span>
  <span m="2474200">it's</span> <span m="2474350">also</span> <span m="2474620">in</span>
  <span m="2474710">our</span> <span m="2474860">n.</span> <span m="2476290">Yeah,</span>
  <span m="2477960">OK.</span> <span m="2482190">Thank</span> <span m="2482660">you.</span>
  <span m="2483730">And</span> <span m="2484030">n--</span> <span m="2485650">actually,</span>
  <span m="2485780">I</span> <span m="2486240">used</span> <span m="2486510">the</span>
  <span m="2486630">fact</span> <span m="2486840">that</span> <span m="2486990">this</span>
  <span m="2487170">was</span> <span m="2487350">of</span> <span m="2487440">size</span>
  <span m="2487770">n</span> <span m="2488010">here</span> <span m="2488290">already.</span></p><p><span
  m="2491690">OK,</span> <span m="2492180">and</span> <span m="2492300">so</span>
  <span m="2492420">that's</span> <span m="2492630">indeed</span> <span m="2492870">v</span>
  <span m="2493020">bar.</span> <span m="2499020">So</span> <span m="2499070">what</span>
  <span m="2499240">is</span> <span m="2499340">this</span> <span m="2499490">projection</span>
  <span m="2500000">doing</span> <span m="2500270">to a</span> <span m="2500450">vector?</span>
  <span m="2507470">It's</span> <span m="2507720">removing</span> <span m="2508290">its</span>
  <span m="2508470">average</span> <span m="2509730">on</span> <span m="2509910">each</span>
  <span m="2510120">coordinate,</span> <span m="2510660">right?</span> <span m="2511930">And</span>
  <span m="2512050">the</span> <span m="2512140">effect</span> <span m="2512470">of</span>
  <span m="2512590">this</span> <span m="2512890">is</span> <span m="2513010">that</span>
  <span m="2513370">v</span> <span m="2513910">is</span> <span m="2514120">a</span>
  <span m="2514180">vector.</span> <span m="2514570">What</span> <span m="2514720">is</span>
  <span m="2514870">the</span> <span m="2515110">average</span> <span m="2515560">of</span>
  <span m="2516480">Hv?</span></p><p><span m="2518355">AUDIENCE:</span> <span m="2518572">0.</span></p><p><span
  m="2519660">PHILIPPE RIGOLLET:</span> <span m="2519880">Right,</span> <span m="2520100">so</span>
  <span m="2520260">it's</span> <span m="2520380">0.</span> <span m="2520840">It's</span>
  <span m="2520960">the</span> <span m="2521110">average</span> <span m="2521470">of</span>
  <span m="2521530">v,</span> <span m="2521770">which</span> <span m="2521950">is</span>
  <span m="2522080">v</span> <span m="2522360">bar,</span> <span m="2522970">minus</span>
  <span m="2523360">the</span> <span m="2523540">average</span> <span m="2524050">of</span>
  <span m="2524200">something</span> <span m="2524560">that</span> <span m="2524680">only</span>
  <span m="2524920">has</span> <span m="2525110">v bar's</span> <span m="2525730">entry,</span>
  <span m="2526240">which</span> <span m="2526420">is</span> <span m="2526540">v</span>
  <span m="2526660">bar.</span> <span m="2527230">So</span> <span m="2527320">this</span>
  <span m="2527500">thing</span> <span m="2527680">is</span> <span m="2527770">actually</span>
  <span m="2528130">0.</span> <span m="2531560">So</span> <span m="2531710">let me</span>
  <span m="2531900">repeat</span> <span m="2532060">my</span> <span m="2532310">question.</span>
  <span m="2532840">Onto</span> <span m="2534020">what</span> <span m="2534290">subspace</span>
  <span m="2534950">does</span> <span m="2535190">H</span> <span m="2535430">project?</span>
  <span m="2542700">Onto</span> <span m="2542940">the</span> <span m="2543060">subspace</span>
  <span m="2543570">of</span> <span m="2543660">vectors</span> <span m="2544110">that</span>
  <span m="2544230">have mean</span> <span m="2544600">0.</span></p><p><span m="2546670">A
  vector</span> <span m="2547450">that</span> <span m="2547630">has</span> <span m="2547840">mean</span>
  <span m="2548020">0</span> <span m="2548590">is</span> <span m="2548800">a</span>
  <span m="2548860">vector.</span> <span m="2550010">So</span> <span m="2550450">if</span>
  <span m="2550600">you</span> <span m="2550690">want</span> <span m="2550840">to</span>
  <span m="2550900">talk</span> <span m="2551170">more</span> <span m="2552160">linear</span>
  <span m="2552490">algebra,</span> <span m="2553940">v</span> <span m="2554300">bar--</span>
  <span m="2554970">for</span> <span m="2555260">a</span> <span m="2555370">vector</span>
  <span m="2555750">you</span> <span m="2555850">have</span> <span m="2556000">mean</span>
  <span m="2556180">0,</span> <span m="2556430">it</span> <span m="2556540">means</span>
  <span m="2556750">that</span> <span m="2556990">v</span> <span m="2558190">is</span>
  <span m="2558400">orthogonal</span> <span m="2559480">to</span> <span m="2559600">the</span>
  <span m="2559750">span</span> <span m="2561160">of</span> <span m="2561340">the</span>
  <span m="2561490">all-ones</span> <span m="2561900">vector.</span> <span m="2563440">That's</span>
  <span m="2563860">it.</span> <span m="2564280">It projects</span> <span m="2564940">to</span>
  <span m="2565080">this</span> <span m="2565240">space.</span> <span m="2566080">So</span>
  <span m="2566160">in</span> <span m="2566450">words,</span> <span m="2566920">it</span>
  <span m="2567020">projects</span> <span m="2567320">onto</span> <span m="2567540">the</span>
  <span m="2567660">space</span> <span m="2567930">of</span> <span m="2567990">vectors</span>
  <span m="2568350">that</span> <span m="2568440">have</span> <span m="2568590">0</span>
  <span m="2568860">mean.</span> <span m="2569880">In</span> <span m="2570090">linear</span>
  <span m="2570360">algebra,</span> <span m="2571140">it</span> <span m="2571290">says</span>
  <span m="2571820">it</span> <span m="2571950">projects</span> <span m="2572380">onto</span>
  <span m="2573210">the</span> <span m="2573930">hyperplane</span> <span m="2574680">which</span>
  <span m="2574890">is</span> <span m="2575130">orthogonal</span> <span m="2575760">to</span>
  <span m="2575880">the</span> <span m="2576000">all-ones</span> <span m="2576380">vector,</span>
  <span m="2577790">OK?</span> <span m="2578360">So</span> <span m="2578480">that's</span>
  <span m="2579980">all.</span></p><p><span m="2581860">Can</span> <span m="2582000">you</span>
  <span m="2582090">guys</span> <span m="2582240">still</span> <span m="2582480">see</span>
  <span m="2582660">the</span> <span m="2583430">screen?</span> <span m="2584760">Are</span>
  <span m="2584820">you</span> <span m="2584940">good</span> <span m="2585090">over</span>
  <span m="2585270">there?</span> <span m="2585940">OK.</span></p><p><span m="2587420">All</span>
  <span m="2587540">right,</span> <span m="2587760">so</span> <span m="2588560">now,</span>
  <span m="2589260">what</span> <span m="2589440">it</span> <span m="2589530">means</span>
  <span m="2589860">is</span> <span m="2589980">that,</span> <span m="2591330">well,</span>
  <span m="2591990">I'm</span> <span m="2592140">doing</span> <span m="2592380">this</span>
  <span m="2592590">weird</span> <span m="2592770">thing,</span> <span m="2593040">right?</span>
  <span m="2593280">I'm</span> <span m="2593460">taking</span> <span m="2594000">the</span>
  <span m="2594150">inner</span> <span m="2594390">product--</span> <span m="2595360">so</span>
  <span m="2595470">S</span> <span m="2595800">is</span> <span m="2595970">taking</span>
  <span m="2596400">X.</span> <span m="2597720">And</span> <span m="2597840">then</span>
  <span m="2597990">it's</span> <span m="2598140">removing</span> <span m="2598650">its</span>
  <span m="2598950">mean</span> <span m="2599550">of</span> <span m="2599760">each</span>
  <span m="2600030">of</span> <span m="2600180">the</span> <span m="2600480">columns</span>
  <span m="2600870">of</span> <span m="2600960">X,</span> <span m="2601170">right?</span>
  <span m="2601440">When</span> <span m="2601590">I</span> <span m="2601650">take</span>
  <span m="2602050">H</span> <span m="2602340">times</span> <span m="2602700">X,</span>
  <span m="2603390">I'm</span> <span m="2603510">basically</span> <span m="2603990">applying</span>
  <span m="2604410">this</span> <span m="2604530">projection</span> <span m="2605130">which</span>
  <span m="2605280">consists</span> <span m="2605670">in</span> <span m="2605790">removing</span>
  <span m="2606210">the</span> <span m="2606300">mean</span> <span m="2606540">of</span>
  <span m="2606630">all</span> <span m="2606780">the</span> <span m="2606930">X's.</span>
  <span m="2608430">And</span> <span m="2608550">then</span> <span m="2609130">I</span>
  <span m="2609240">multiply</span> <span m="2610320">by</span> <span m="2610530">H</span>
  <span m="2610770">transpose.</span></p><p><span m="2611340">But</span> <span m="2611910">what's</span>
  <span m="2612090">actually</span> <span m="2612450">nice</span> <span m="2612750">is</span>
  <span m="2612870">that,</span> <span m="2613080">remember,</span> <span m="2613550">H</span>
  <span m="2613790">is</span> <span m="2613950">a</span> <span m="2614010">projector.</span>
  <span m="2615930">Sorry,</span> <span m="2616040">I don't want to</span> <span m="2616500">keep</span>
  <span m="2616760">that.</span> <span m="2618000">Which</span> <span m="2618210">means</span>
  <span m="2620880">that</span> <span m="2621090">when</span> <span m="2621270">I</span>
  <span m="2621360">look</span> <span m="2621840">at</span> <span m="2623180">X</span>
  <span m="2623490">transpose</span> <span m="2624570">HX,</span> <span m="2627010">it's</span>
  <span m="2627160">the</span> <span m="2627310">same</span> <span m="2627730">as</span>
  <span m="2627910">looking</span> <span m="2628300">at</span> <span m="2628510">X</span>
  <span m="2629290">transpose</span> <span m="2630160">H</span> <span m="2630460">squared</span>
  <span m="2631630">X.</span> <span m="2632410">But</span> <span m="2632560">since</span>
  <span m="2632890">H</span> <span m="2633190">is</span> <span m="2633280">equal</span>
  <span m="2633520">to its</span> <span m="2633880">transpose,</span> <span m="2634420">this</span>
  <span m="2634570">is</span> <span m="2634690">actually</span> <span m="2634990">the</span>
  <span m="2635110">same</span> <span m="2635440">as</span> <span m="2635560">looking</span>
  <span m="2635890">at</span> <span m="2636370">X</span> <span m="2636610">transpose</span>
  <span m="2637720">H</span> <span m="2638020">transpose</span> <span m="2639130">HX,</span>
  <span m="2640600">which</span> <span m="2640750">is</span> <span m="2640870">the</span>
  <span m="2640990">same</span> <span m="2641410">as</span> <span m="2641530">looking</span>
  <span m="2641920">at</span> <span m="2642260">HX</span> <span m="2644890">transpose</span>
  <span m="2647146">HX,</span> <span m="2650100">OK?</span></p><p><span m="2651000">So</span>
  <span m="2651150">what</span> <span m="2651330">it's</span> <span m="2651450">doing,</span>
  <span m="2651960">it's</span> <span m="2652290">first</span> <span m="2652620">applying</span>
  <span m="2653100">this</span> <span m="2653760">projection</span> <span m="2654300">matrix,</span>
  <span m="2655020">H,</span> <span m="2655380">which</span> <span m="2655800">removes</span>
  <span m="2656250">the</span> <span m="2656370">mean</span> <span m="2656760">of</span>
  <span m="2656940">each</span> <span m="2657180">of</span> <span m="2657300">your</span>
  <span m="2657420">columns,</span> <span m="2658950">and</span> <span m="2659100">then</span>
  <span m="2659490">looks</span> <span m="2659760">at</span> <span m="2661590">the
  inner</span> <span m="2661900">products</span> <span m="2662280">between</span>
  <span m="2662550">those</span> <span m="2662740">guys,</span> <span m="2663000">right?</span>
  <span m="2663870">Each</span> <span m="2664080">entry of</span> <span m="2664320">this</span>
  <span m="2664550">guy is</span> <span m="2664810">just</span> <span m="2664950">the</span>
  <span m="2665070">covariance</span> <span m="2665460">between those</span> <span
  m="2665940">centered</span> <span m="2666150">things.</span> <span m="2667320">That's</span>
  <span m="2667500">all</span> <span m="2667620">it's</span> <span m="2667800">doing.</span></p><p><span
  m="2668910">All right,</span> <span m="2671340">so</span> <span m="2673370">those</span>
  <span m="2673760">are</span> <span m="2673880">actually</span> <span m="2674240">going</span>
  <span m="2674360">to</span> <span m="2674420">be</span> <span m="2674510">the</span>
  <span m="2674630">key</span> <span m="2674840">statements.</span> <span m="2675450">So</span>
  <span m="2675830">everything</span> <span m="2676190">we've</span> <span m="2676340">done</span>
  <span m="2676490">so</span> <span m="2676640">far</span> <span m="2676880">is</span>
  <span m="2677000">really</span> <span m="2677270">mainly</span> <span m="2677930">linear</span>
  <span m="2678200">algebra,</span> <span m="2678650">right?</span> <span m="2678920">I</span>
  <span m="2678980">mean,</span> <span m="2679190">looking</span> <span m="2679460">at</span>
  <span m="2679550">expectations</span> <span m="2680270">and</span> <span m="2680360">covariances</span>
  <span m="2681020">was</span> <span m="2681500">just--</span> <span m="2682130">we</span>
  <span m="2682250">just</span> <span m="2682460">used</span> <span m="2682580">the</span>
  <span m="2682700">fact</span> <span m="2682940">that</span> <span m="2683060">the</span>
  <span m="2683150">expectation</span> <span m="2683690">was</span> <span m="2683870">linear.</span>
  <span m="2684200">We</span> <span m="2684290">didn't</span> <span m="2684500">do</span>
  <span m="2684590">much.</span> <span m="2685520">But</span> <span m="2685670">now</span>
  <span m="2685860">there's</span> <span m="2686180">a</span> <span m="2686240">nice</span>
  <span m="2686600">thing</span> <span m="2686810">that's</span> <span m="2686990">happening.</span></p><p><span
  m="2687450">And</span> <span m="2687470">that's</span> <span m="2687740">why</span>
  <span m="2689300">we're</span> <span m="2689540">going</span> <span m="2689660">to</span>
  <span m="2689720">switch</span> <span m="2690050">from</span> <span m="2690290">the</span>
  <span m="2690410">language</span> <span m="2690770">of</span> <span m="2690860">linear</span>
  <span m="2691130">algebra</span> <span m="2691550">to</span> <span m="2691640">more</span>
  <span m="2691820">statistical,</span> <span m="2692930">because</span> <span m="2693200">what's</span>
  <span m="2693380">happening</span> <span m="2693710">is</span> <span m="2693830">that</span>
  <span m="2694010">if</span> <span m="2694220">I</span> <span m="2694310">look</span>
  <span m="2694520">at</span> <span m="2694670">this</span> <span m="2695990">quadratic</span>
  <span m="2696410">form,</span> <span m="2696830">right?</span> <span m="2697010">So</span>
  <span m="2697130">I</span> <span m="2697220">take</span> <span m="2697490">sigma.</span>
  <span m="2699080">So</span> <span m="2699210">I</span> <span m="2699300">take</span>
  <span m="2699480">a</span> <span m="2699630">vector,</span> <span m="2700010">u.</span>
  <span m="2703630">And</span> <span m="2705580">I'm</span> <span m="2705730">going</span>
  <span m="2705880">to</span> <span m="2706060">look</span> <span m="2706330">at</span>
  <span m="2706660">u--</span> <span m="2707140">so</span> <span m="2707260">let's</span>
  <span m="2707440">say,</span> <span m="2707590">in Rd.</span> <span m="2709180">And</span>
  <span m="2709270">I'm</span> <span m="2709390">going</span> <span m="2709490">to</span>
  <span m="2709600">look</span> <span m="2709840">at</span> <span m="2710020">u</span>
  <span m="2710770">transpose</span> <span m="2711730">sigma</span> <span m="2712570">u.</span>
  <span m="2714836">OK?</span></p><p><span m="2718510">What</span> <span m="2718720">is</span>
  <span m="2718870">this</span> <span m="2719080">doing?</span> <span m="2719720">Well,</span>
  <span m="2721000">we</span> <span m="2721120">know</span> <span m="2721360">that</span>
  <span m="2721900">u</span> <span m="2722110">transpose</span> <span m="2722590">sigma</span>
  <span m="2722950">u</span> <span m="2723760">is</span> <span m="2723940">equal</span>
  <span m="2724240">to</span> <span m="2724420">what?</span> <span m="2724630">Well,</span>
  <span m="2724840">sigma</span> <span m="2727220">is</span> <span m="2728270">the</span>
  <span m="2728330">expectation</span> <span m="2729550">of</span> <span m="2729860">XX</span>
  <span m="2730670">transpose</span> <span m="2731720">minus</span> <span m="2732140">the</span>
  <span m="2732260">expectation</span> <span m="2732575">of</span> <span m="2732890">X</span>
  <span m="2734350">expectation</span> <span m="2735210">of</span> <span m="2735300">X</span>
  <span m="2735450">transpose,</span> <span m="2735930">right?</span> <span m="2739460">So
  I</span> <span m="2739670">just</span> <span m="2739880">substitute</span> <span
  m="2740180">in</span> <span m="2740480">there.</span></p><p><span m="2746100">Now,</span>
  <span m="2746960">u</span> <span m="2747240">is</span> <span m="2747390">deterministic.</span>
  <span m="2749370">So</span> <span m="2749430">in</span> <span m="2749520">particular,</span>
  <span m="2750030">I</span> <span m="2750090">can</span> <span m="2750300">push</span>
  <span m="2750670">it</span> <span m="2750840">inside</span> <span m="2751410">the</span>
  <span m="2751560">expectation</span> <span m="2752250">here,</span> <span m="2753610">agreed?</span>
  <span m="2755180">And</span> <span m="2755280">I</span> <span m="2755340">can</span>
  <span m="2755550">do</span> <span m="2755700">the</span> <span m="2755790">same</span>
  <span m="2756060">from</span> <span m="2756270">the</span> <span m="2756390">right.</span>
  <span m="2757200">So</span> <span m="2757350">here,</span> <span m="2757620">when</span>
  <span m="2757770">I</span> <span m="2757860">push</span> <span m="2758250">u</span>
  <span m="2758460">transpose</span> <span m="2759000">here,</span> <span m="2759870">and</span>
  <span m="2759990">u</span> <span m="2760260">here,</span> <span m="2760800">what</span>
  <span m="2760950">I'm</span> <span m="2761100">left</span> <span m="2761400">with</span>
  <span m="2761640">is</span> <span m="2762270">the</span> <span m="2762360">expectation</span>
  <span m="2763530">of</span> <span m="2764130">u</span> <span m="2764400">transpose</span>
  <span m="2765090">X</span> <span m="2766170">times</span> <span m="2766650">X</span>
  <span m="2766860">transpose</span> <span m="2767370">u.</span> <span m="2769990">OK?</span>
  <span m="2771436">And</span> <span m="2771920">now,</span> <span m="2772130">I</span>
  <span m="2772190">can</span> <span m="2772370">do</span> <span m="2772490">the</span>
  <span m="2772580">same</span> <span m="2772850">thing</span> <span m="2773090">for</span>
  <span m="2773240">this</span> <span m="2773420">guy.</span> <span m="2774050">And</span>
  <span m="2774200">this</span> <span m="2774380">tells</span> <span m="2774650">me</span>
  <span m="2774740">that</span> <span m="2774860">this</span> <span m="2775070">is</span>
  <span m="2775190">the</span> <span m="2775280">expectation</span> <span m="2776450">of</span>
  <span m="2776630">u</span> <span m="2776840">transpose</span> <span m="2777410">X</span>
  <span m="2778430">times</span> <span m="2779290">the</span> <span m="2779390">expectation</span>
  <span m="2780380">of</span> <span m="2780560">X</span> <span m="2780710">transpose</span>
  <span m="2781190">u.</span></p><p><span m="2784640">Of</span> <span m="2784760">course,</span>
  <span m="2785600">u</span> <span m="2785720">transpose</span> <span m="2786230">X</span>
  <span m="2786470">is</span> <span m="2786590">equal</span> <span m="2787070">to</span>
  <span m="2787745">X</span> <span m="2788000">transpose</span> <span m="2788480">u.</span>
  <span m="2789260">And</span> <span m="2789470">u--</span> <span m="2790700">yeah.</span>
  <span m="2791330">So</span> <span m="2792290">what</span> <span m="2792440">it</span>
  <span m="2792530">means</span> <span m="2792830">is</span> <span m="2792950">that</span>
  <span m="2793130">this</span> <span m="2793370">is</span> <span m="2793490">actually</span>
  <span m="2793910">equal</span> <span m="2799080">to</span> <span m="2799230">the</span>
  <span m="2799380">expectation</span> <span m="2800400">of</span> <span m="2800580">u</span>
  <span m="2800820">transpose</span> <span m="2801400">X</span> <span m="2802700">squared</span>
  <span m="2803700">minus</span> <span m="2805080">the</span> <span m="2805170">expectation</span>
  <span m="2806460">of</span> <span m="2806670">u</span> <span m="2806880">transpose</span>
  <span m="2807450">X,</span> <span m="2808020">the</span> <span m="2808140">whole</span>
  <span m="2808320">thing</span> <span m="2808590">squared.</span></p><p><span m="2817150">But</span>
  <span m="2817300">this</span> <span m="2817480">is</span> <span m="2817540">something</span>
  <span m="2817900">that</span> <span m="2818020">should</span> <span m="2818170">look</span>
  <span m="2818350">familiar.</span> <span m="2818900">This</span> <span m="2818950">is</span>
  <span m="2819070">really</span> <span m="2819340">just</span> <span m="2819520">the</span>
  <span m="2819640">variance</span> <span m="2820210">of</span> <span m="2820330">this</span>
  <span m="2820540">particular</span> <span m="2820960">random</span> <span m="2821260">variable</span>
  <span m="2821750">which</span> <span m="2821860">is</span> <span m="2821950">of</span>
  <span m="2822040">the</span> <span m="2822160">form,</span> <span m="2822460">u</span>
  <span m="2822580">transpose</span> <span m="2823070">X,</span> <span m="2823360">right?</span>
  <span m="2823860">u</span> <span m="2824150">transpose</span> <span m="2824590">X</span>
  <span m="2825700">is</span> <span m="2825880">a</span> <span m="2825940">number.</span>
  <span m="2826900">It</span> <span m="2827050">involves</span> <span m="2827490">a</span>
  <span m="2827590">random</span> <span m="2827890">vector,</span> <span m="2828400">so</span>
  <span m="2828550">it's</span> <span m="2828700">a</span> <span m="2828760">random</span>
  <span m="2829090">variable.</span> <span m="2830110">And</span> <span m="2830200">so</span>
  <span m="2830350">it</span> <span m="2830440">has</span> <span m="2830620">a</span>
  <span m="2830680">variance.</span> <span m="2831580">And</span> <span m="2831700">this</span>
  <span m="2831850">variance</span> <span m="2832210">is</span> <span m="2832330">exactly</span>
  <span m="2832780">given</span> <span m="2833020">by</span> <span m="2833170">this</span>
  <span m="2833320">formula.</span> <span m="2835430">So</span> <span m="2835480">this</span>
  <span m="2835720">is</span> <span m="2835810">just</span> <span m="2836020">the</span>
  <span m="2836110">variance</span> <span m="2836860">of</span> <span m="2837040">u</span>
  <span m="2837190">transpose</span> <span m="2837750">X.</span> <span m="2839770">So</span>
  <span m="2839920">what</span> <span m="2840040">we've</span> <span m="2840220">proved</span>
  <span m="2840520">is</span> <span m="2840640">that</span> <span m="2840790">if</span>
  <span m="2840940">I</span> <span m="2841030">look</span> <span m="2841210">at</span>
  <span m="2841330">this</span> <span m="2841510">guy,</span> <span m="2841720">this</span>
  <span m="2841900">is</span> <span m="2842020">really</span> <span m="2842290">just</span>
  <span m="2842500">the</span> <span m="2842620">variance</span> <span m="2843990">of</span>
  <span m="2844210">u</span> <span m="2844420">transpose</span> <span m="2845080">X,</span>
  <span m="2849284">OK?</span></p><p><span m="2857580">I</span> <span m="2857700">can</span>
  <span m="2857850">do</span> <span m="2857940">the</span> <span m="2858060">same</span>
  <span m="2858330">thing</span> <span m="2858540">for</span> <span m="2858660">the</span>
  <span m="2858750">sample</span> <span m="2859080">variance.</span> <span m="2860930">So</span>
  <span m="2861020">let's</span> <span m="2861260">do</span> <span m="2861410">this.</span>
  <span m="2868240">And</span> <span m="2869440">as</span> <span m="2869620">you</span>
  <span m="2869680">can</span> <span m="2869890">see,</span> <span m="2871180">spoiler</span>
  <span m="2871750">alert,</span> <span m="2872140">this</span> <span m="2872350">is</span>
  <span m="2872440">going</span> <span m="2872620">to</span> <span m="2872680">be</span>
  <span m="2873220">the</span> <span m="2875406">sample</span> <span m="2875870">variance.</span>
  <span m="2879590">OK,</span> <span m="2879830">so</span> <span m="2880010">remember,</span>
  <span m="2880400">S</span> <span m="2882120">is</span> <span m="2882440">1</span>
  <span m="2882620">over</span> <span m="2882860">n,</span> <span m="2883580">sum</span>
  <span m="2883970">of</span> <span m="2884230">Xi</span> <span m="2885103">Xi</span>
  <span m="2885830">transpose</span> <span m="2888140">minus</span> <span m="2889210">X</span>
  <span m="2889430">bar</span> <span m="2890030">X</span> <span m="2890210">bar transpose.</span>
  <span m="2892100">So</span> <span m="2892220">when</span> <span m="2892370">I</span>
  <span m="2892460">do</span> <span m="2892820">u</span> <span m="2893060">transpose,</span>
  <span m="2894370">Su,</span> <span m="2895870">what</span> <span m="2896060">it</span>
  <span m="2896180">gives</span> <span m="2896480">me</span> <span m="2896690">is</span>
  <span m="2896960">1</span> <span m="2897170">over</span> <span m="2897410">n</span>
  <span m="2898250">sum</span> <span m="2898580">from</span> <span m="2898820">i equal</span>
  <span m="2899130">1</span> <span m="2899400">to</span> <span m="2899570">n</span>
  <span m="2900040">of</span> <span m="2900500">u</span> <span m="2900770">transpose</span>
  <span m="2901940">Xi</span> <span m="2903140">times</span> <span m="2903710">Xi</span>
  <span m="2904190">transpose</span> <span m="2904880">u,</span> <span m="2905500">all</span>
  <span m="2905570">right?</span></p><p><span m="2905780">So</span> <span m="2905930">those</span>
  <span m="2906170">are</span> <span m="2906260">two</span> <span m="2906470">numbers</span>
  <span m="2906890">that</span> <span m="2907010">multiply</span> <span m="2907460">each</span>
  <span m="2907640">other</span> <span m="2907880">and</span> <span m="2908030">that</span>
  <span m="2908120">happen</span> <span m="2908420">to</span> <span m="2908570">be</span>
  <span m="2908690">equal</span> <span m="2908990">to</span> <span m="2909110">each</span>
  <span m="2909290">other,</span> <span m="2910370">minus</span> <span m="2910940">u</span>
  <span m="2911240">transpose</span> <span m="2911960">X</span> <span m="2912170">bar</span>
  <span m="2914840">X</span> <span m="2915050">bar</span> <span m="2915500">transpose</span>
  <span m="2916000">u,</span> <span m="2916430">which</span> <span m="2916640">is</span>
  <span m="2916760">also</span> <span m="2917360">the</span> <span m="2917450">product</span>
  <span m="2917810">of</span> <span m="2917930">two</span> <span m="2918050">numbers</span>
  <span m="2918410">that</span> <span m="2918500">happen</span> <span m="2918770">to</span>
  <span m="2918860">be</span> <span m="2918950">equal</span> <span m="2919220">to</span>
  <span m="2919340">each</span> <span m="2919520">other.</span> <span m="2920190">So</span>
  <span m="2920290">I</span> <span m="2920390">can</span> <span m="2920420">rewrite</span>
  <span m="2920750">this</span> <span m="2920990">with</span> <span m="2921140">squares.</span></p><p><span
  m="2935120">So</span> <span m="2935260">we're</span> <span m="2935470">almost</span>
  <span m="2935820">there.</span> <span m="2937390">All</span> <span m="2937600">I</span>
  <span m="2937660">need</span> <span m="2937810">to</span> <span m="2937990">know</span>
  <span m="2938410">to</span> <span m="2938560">check</span> <span m="2938920">is</span>
  <span m="2939040">that</span> <span m="2939220">this</span> <span m="2939460">thing</span>
  <span m="2939670">is</span> <span m="2939790">actually</span> <span m="2940360">the</span>
  <span m="2940630">average</span> <span m="2941080">of</span> <span m="2941200">those</span>
  <span m="2941410">guys,</span> <span m="2941740">right?</span> <span m="2942010">So</span>
  <span m="2942310">u</span> <span m="2942610">transpose</span> <span m="2943270">X</span>
  <span m="2943480">bar.</span> <span m="2944560">What</span> <span m="2944710">is</span>
  <span m="2944860">it?</span> <span m="2945030">It's</span> <span m="2945210">1</span>
  <span m="2945400">over</span> <span m="2945640">n</span> <span m="2945970">sum</span>
  <span m="2946280">from</span> <span m="2946630">i</span> <span m="2946880">equal</span>
  <span m="2947050">1</span> <span m="2947320">to</span> <span m="2947590">n</span>
  <span m="2948175">of</span> <span m="2948460">u</span> <span m="2948640">transpose</span>
  <span m="2949220">Xi.</span> <span m="2950980">So</span> <span m="2951100">it's</span>
  <span m="2951250">really</span> <span m="2951700">something</span> <span m="2952090">that</span>
  <span m="2952210">I</span> <span m="2952270">can</span> <span m="2952450">write</span>
  <span m="2952750">as</span> <span m="2952930">u</span> <span m="2953110">transpose</span>
  <span m="2953740">X</span> <span m="2955090">bar,</span> <span m="2957195">right?</span>
  <span m="2957550">That's</span> <span m="2957730">the</span> <span m="2957910">average</span>
  <span m="2958330">of</span> <span m="2958450">those</span> <span m="2958630">random</span>
  <span m="2958870">variables</span> <span m="2959350">of</span> <span m="2959470">the</span>
  <span m="2959590">form,</span> <span m="2960250">u</span> <span m="2960370">transpose</span>
  <span m="2960820">Xi.</span></p><p><span m="2963880">So</span> <span m="2966220">what</span>
  <span m="2966340">it</span> <span m="2966430">means</span> <span m="2966730">is</span>
  <span m="2966820">that</span> <span m="2967030">u</span> <span m="2967270">transpose</span>
  <span m="2967840">Su,</span> <span m="2968770">I</span> <span m="2969070">can</span>
  <span m="2969280">write</span> <span m="2969540">as</span> <span m="2969730">1</span>
  <span m="2969910">over</span> <span m="2970150">n</span> <span m="2971050">sum</span>
  <span m="2971290">from</span> <span m="2971590">i equal</span> <span m="2971980">1</span>
  <span m="2972310">to</span> <span m="2972460">n</span> <span m="2973496">of</span>
  <span m="2973850">u</span> <span m="2974080">transpose</span> <span m="2975940">Xi</span>
  <span m="2977580">squared</span> <span m="2978060">minus</span> <span m="2979250">u</span>
  <span m="2979500">transpose</span> <span m="2980310">X</span> <span m="2983270">bar</span>
  <span m="2983990">squared,</span> <span m="2985550">which</span> <span m="2986720">is</span>
  <span m="2986990">the</span> <span m="2987140">empirical</span> <span m="2987620">variance</span>
  <span m="2990430">that</span> <span m="2990620">we</span> <span m="2990720">need</span>
  <span m="2990860">noted</span> <span m="2991150">by</span> <span m="2991370">small</span>
  <span m="2991660">s</span> <span m="2991950">squared,</span> <span m="2992570">right?</span>
  <span m="2994600">So</span> <span m="2994750">that's</span> <span m="2995020">the</span>
  <span m="2995170">empirical</span> <span m="2995650">variance</span> <span m="3003290">of</span>
  <span m="3003590">u</span> <span m="3003830">transpose</span> <span m="3004450">X1</span>
  <span m="3006370">all</span> <span m="3006520">the</span> <span m="3006640">way</span>
  <span m="3006850">to</span> <span m="3007020">u</span> <span m="3007300">transpose</span>
  <span m="3007740">Xn.</span></p><p><span m="3012430">OK, and</span> <span m="3012790">here,</span>
  <span m="3013240">same</span> <span m="3013580">thing.</span> <span m="3013910">I</span>
  <span m="3014000">use</span> <span m="3014270">exactly</span> <span m="3014750">the</span>
  <span m="3014810">same</span> <span m="3014990">thing.</span> <span m="3015210">I</span>
  <span m="3015280">just</span> <span m="3015620">use</span> <span m="3015830">the</span>
  <span m="3015920">fact</span> <span m="3016160">that</span> <span m="3016280">here,</span>
  <span m="3016970">the</span> <span m="3017060">only</span> <span m="3017240">thing</span>
  <span m="3017390">I</span> <span m="3017450">use</span> <span m="3017660">is</span>
  <span m="3017780">really</span> <span m="3017990">the</span> <span m="3018110">linearity</span>
  <span m="3018740">of</span> <span m="3018830">this</span> <span m="3018980">guy,</span>
  <span m="3019730">of</span> <span m="3019970">1</span> <span m="3020150">over</span>
  <span m="3020330">n</span> <span m="3020450">sum</span> <span m="3020790">or</span>
  <span m="3020990">the</span> <span m="3021080">linearity</span> <span m="3021650">of</span>
  <span m="3021740">expectation,</span> <span m="3023090">that</span> <span m="3023180">I</span>
  <span m="3023240">can</span> <span m="3023390">push</span> <span m="3023720">things</span>
  <span m="3024020">in</span> <span m="3024140">there,</span> <span m="3026250">OK?</span></p><p><span
  m="3030660">AUDIENCE:</span> <span m="3030905">So what you</span> <span m="3031150">have
  written</span> <span m="3031640">at</span> <span m="3032130">the end of that</span>
  <span m="3032620">sum</span> <span m="3033110">for uT</span> <span m="3033600">Su?</span></p><p><span
  m="3034600">PHILIPPE RIGOLLET:</span> <span m="3034705">This</span> <span m="3034810">one?</span></p><p><span
  m="3035010">AUDIENCE:</span> <span m="3035195">Yeah.</span></p><p><span m="3035380">PHILIPPE
  RIGOLLET:</span> <span m="3035565">Yeah,</span> <span m="3035750">I</span> <span
  m="3035830">said</span> <span m="3036040">it's</span> <span m="3036210">equal</span>
  <span m="3036490">to</span> <span m="3036670">small</span> <span m="3036935">s,</span>
  <span m="3037290">and</span> <span m="3037540">I</span> <span m="3037630">want</span>
  <span m="3037880">to</span> <span m="3038080">make</span> <span m="3038260">a</span>
  <span m="3038320">difference</span> <span m="3038680">between</span> <span m="3038950">the</span>
  <span m="3039080">big S</span> <span m="3039430">that</span> <span m="3039550">I'm</span>
  <span m="3039670">using</span> <span m="3039970">here.</span> <span m="3040660">So</span>
  <span m="3040750">this</span> <span m="3040960">is</span> <span m="3041080">equal</span>
  <span m="3041410">to</span> <span m="3041740">small--</span> <span m="3042650">I</span>
  <span m="3042990">don't</span> <span m="3043330">know,</span> <span m="3043690">I'm</span>
  <span m="3043780">trying</span> <span m="3044050">to</span> <span m="3044170">make</span>
  <span m="3044380">it</span> <span m="3044590">look</span> <span m="3045190">like</span>
  <span m="3045480">a</span> <span m="3045610">calligraphic</span> <span m="3046070">s</span>
  <span m="3047060">squared.</span></p><p><span m="3056870">OK,</span> <span m="3058840">so</span>
  <span m="3059020">this</span> <span m="3059260">is</span> <span m="3059410">nice,</span>
  <span m="3059780">right?</span> <span m="3060040">This</span> <span m="3060190">covariance</span>
  <span m="3060670">matrix--</span> <span m="3062790">so</span> <span m="3062840">let's</span>
  <span m="3063080">look</span> <span m="3063230">at</span> <span m="3063410">capital</span>
  <span m="3063800">sigma</span> <span m="3064120">itself</span> <span m="3064550">right</span>
  <span m="3064670">now.</span> <span m="3065210">This</span> <span m="3065320">covariance</span>
  <span m="3065690">matrix,</span> <span m="3066260">we</span> <span m="3066380">know</span>
  <span m="3066620">that</span> <span m="3066740">if</span> <span m="3066920">we</span>
  <span m="3067070">read</span> <span m="3067370">its</span> <span m="3067580">entries,</span>
  <span m="3069460">what</span> <span m="3069620">we</span> <span m="3069770">get</span>
  <span m="3070670">is</span> <span m="3071060">the</span> <span m="3071180">covariance</span>
  <span m="3071690">between</span> <span m="3071990">the</span> <span m="3072080">coordinates</span>
  <span m="3073430">of</span> <span m="3074060">the</span> <span m="3074270">X's,</span>
  <span m="3075020">right,</span> <span m="3075260">of</span> <span m="3075350">the</span>
  <span m="3075620">random</span> <span m="3075920">vector,</span> <span m="3076340">X.</span>
  <span m="3077630">And</span> <span m="3077720">the</span> <span m="3077840">coordinates,</span>
  <span m="3078500">well,</span> <span m="3079140">by</span> <span m="3079220">definition,</span>
  <span m="3079840">are</span> <span m="3079940">attached</span> <span m="3080390">to</span>
  <span m="3080540">a</span> <span m="3080600">coordinate</span> <span m="3081080">system.</span>
  <span m="3082530">So</span> <span m="3083490">I</span> <span m="3083610">only</span>
  <span m="3083910">know</span> <span m="3084750">what</span> <span m="3085020">the</span>
  <span m="3085110">covariance</span> <span m="3085830">of</span> <span m="3086610">X</span>
  <span m="3087040">in</span> <span m="3087570">of</span> <span m="3088290">those</span>
  <span m="3088500">two</span> <span m="3088680">things</span> <span m="3089010">are,</span>
  <span m="3089430">or</span> <span m="3089610">the</span> <span m="3089700">covariance</span>
  <span m="3090060">of</span> <span m="3090210">those</span> <span m="3090420">two</span>
  <span m="3090570">things</span> <span m="3090840">are.</span></p><p><span m="3091320">But</span>
  <span m="3091500">what</span> <span m="3091680">if</span> <span m="3091800">I</span>
  <span m="3091890">want</span> <span m="3092070">to</span> <span m="3092190">find</span>
  <span m="3092400">coordinates</span> <span m="3092970">between</span> <span m="3093350">linear</span>
  <span m="3093570">combination</span> <span m="3094110">of</span> <span m="3094200">the</span>
  <span m="3094320">X's?</span> <span m="3095080">Sorry,</span> <span m="3095610">if
  I</span> <span m="3095670">want</span> <span m="3095820">to</span> <span m="3095880">find</span>
  <span m="3096060">covariances</span> <span m="3096630">between</span> <span m="3096910">linear</span>
  <span m="3097200">combination</span> <span m="3097650">of</span> <span m="3097740">those</span>
  <span m="3097880">X's.</span> <span m="3098640">And</span> <span m="3098730">that's</span>
  <span m="3098880">exactly</span> <span m="3099330">what</span> <span m="3099480">this</span>
  <span m="3099690">allows</span> <span m="3099990">me</span> <span m="3100110">to</span>
  <span m="3100230">do.</span> <span m="3100440">It</span> <span m="3100530">says,</span>
  <span m="3100740">well,</span> <span m="3101370">if</span> <span m="3101520">I</span>
  <span m="3101670">pre-</span> <span m="3102030">and</span> <span m="3102150">post-multiply</span>
  <span m="3102990">by</span> <span m="3103170">u,</span> <span m="3104640">this</span>
  <span m="3104820">is</span> <span m="3104940">actually</span> <span m="3105360">telling</span>
  <span m="3105720">me</span> <span m="3106110">what</span> <span m="3106290">the</span>
  <span m="3106410">variance</span> <span m="3107010">of</span> <span m="3107190">X</span>
  <span m="3107500">along</span> <span m="3107940">direction</span> <span m="3108510">u</span>
  <span m="3109020">is,</span> <span m="3111000">OK?</span> <span m="3111950">So</span>
  <span m="3112490">there's</span> <span m="3112760">a</span> <span m="3112820">lot</span>
  <span m="3113000">of</span> <span m="3113060">information</span> <span m="3113660">in</span>
  <span m="3113780">there,</span> <span m="3113960">and</span> <span m="3114080">it's</span>
  <span m="3114290">just</span> <span m="3114530">really</span> <span m="3114770">exploiting</span>
  <span m="3115220">the</span> <span m="3115310">fact</span> <span m="3115610">that</span>
  <span m="3115850">there</span> <span m="3115980">is</span> <span m="3116080">some
  linearity</span> <span m="3116780">going</span> <span m="3117050">on</span> <span
  m="3117170">in</span> <span m="3117260">the</span> <span m="3117410">covariance.</span></p><p><span
  m="3120600">So,</span> <span m="3121280">why</span> <span m="3121610">variance?</span>
  <span m="3122060">Why</span> <span m="3122280">is</span> <span m="3122410">variance</span>
  <span m="3122790">interesting</span> <span m="3123330">for</span> <span m="3123540">us,</span>
  <span m="3123740">right?</span> <span m="3123950">Why?</span> <span m="3124370">I</span>
  <span m="3124530">started</span> <span m="3124890">by</span> <span m="3125040">saying,</span>
  <span m="3125370">here,</span> <span m="3125550">we're</span> <span m="3125640">going</span>
  <span m="3125760">to</span> <span m="3125820">be</span> <span m="3125880">interested</span>
  <span m="3126300">in</span> <span m="3126420">having</span> <span m="3126720">something</span>
  <span m="3127050">to</span> <span m="3127170">do</span> <span m="3127290">dimension</span>
  <span m="3127740">reduction.</span> <span m="3128320">We</span> <span m="3128460">have--</span>
  <span m="3129150">think</span> <span m="3129360">of</span> <span m="3129540">your</span>
  <span m="3129660">points</span> <span m="3129960">as</span> <span m="3130050">[?
  being in a ?]</span> <span m="3130260">dimension</span> <span m="3130650">larger</span>
  <span m="3130890">than</span> <span m="3131070">4,</span> <span m="3131490">and</span>
  <span m="3131580">we're</span> <span m="3131700">going</span> <span m="3131820">to</span>
  <span m="3131880">try</span> <span m="3132060">to</span> <span m="3132180">reduce</span>
  <span m="3132480">the</span> <span m="3132570">dimension.</span> <span m="3133990">So</span>
  <span m="3134280">let's</span> <span m="3134460">just</span> <span m="3134640">think</span>
  <span m="3134820">for</span> <span m="3134940">one</span> <span m="3135150">second,</span>
  <span m="3135480">what</span> <span m="3135660">do</span> <span m="3135720">we</span>
  <span m="3135900">want</span> <span m="3136260">about</span> <span m="3136520">a</span>
  <span m="3136570">dimension</span> <span m="3136980">reduction</span> <span m="3137760">procedure?</span></p><p><span
  m="3139320">If</span> <span m="3139500">I</span> <span m="3139590">have</span> <span
  m="3139860">all</span> <span m="3140040">my</span> <span m="3140220">points</span>
  <span m="3142110">that</span> <span m="3142290">live</span> <span m="3142500">in,</span>
  <span m="3142620">say,</span> <span m="3142890">three</span> <span m="3143130">dimensions,</span>
  <span m="3143690">and</span> <span m="3143790">I</span> <span m="3143850">have</span>
  <span m="3144000">one</span> <span m="3144150">point</span> <span m="3144390">here</span>
  <span m="3144600">and</span> <span m="3144720">one</span> <span m="3144870">point</span>
  <span m="3145090">here</span> <span m="3145260">and</span> <span m="3145350">one</span>
  <span m="3145560">point</span> <span m="3145800">here</span> <span m="3145980">and</span>
  <span m="3146070">one</span> <span m="3146250">point</span> <span m="3146490">here</span>
  <span m="3146670">and</span> <span m="3146760">one</span> <span m="3146910">point</span>
  <span m="3147150">here,</span> <span m="3148020">and</span> <span m="3148140">I</span>
  <span m="3148230">decide</span> <span m="3148560">to</span> <span m="3148650">project</span>
  <span m="3149040">them</span> <span m="3149220">onto</span> <span m="3149490">some</span>
  <span m="3149700">plane--</span> <span m="3150090">that</span> <span m="3150210">I</span>
  <span m="3150300">take</span> <span m="3150560">a</span> <span m="3150630">plane
  that's</span> <span m="3151110">just</span> <span m="3151290">like</span> <span
  m="3151500">this,</span> <span m="3152370">what's</span> <span m="3152550">going</span>
  <span m="3152670">to</span> <span m="3152730">happen</span> <span m="3153000">is</span>
  <span m="3153120">that</span> <span m="3153270">those</span> <span m="3153480">points</span>
  <span m="3153750">are</span> <span m="3153870">all</span> <span m="3153990">going</span>
  <span m="3154110">to</span> <span m="3154170">project</span> <span m="3154590">to</span>
  <span m="3154650">the</span> <span m="3154770">same</span> <span m="3155010">point,</span>
  <span m="3155640">right?</span> <span m="3156030">I'm</span> <span m="3156150">just</span>
  <span m="3156330">going</span> <span m="3156450">to</span> <span m="3156570">not</span>
  <span m="3156900">see</span> <span m="3157080">anything.</span></p><p><span m="3158070">However,</span>
  <span m="3158400">if</span> <span m="3158550">I</span> <span m="3158640">take</span>
  <span m="3158850">a</span> <span m="3158910">plane</span> <span m="3159180">which</span>
  <span m="3159360">is</span> <span m="3159480">like</span> <span m="3159660">this,</span>
  <span m="3160410">they're</span> <span m="3160560">all going</span> <span m="3160860">to</span>
  <span m="3160950">project</span> <span m="3161370">into</span> <span m="3161610">some</span>
  <span m="3161820">nice</span> <span m="3162090">line.</span> <span m="3162990">Maybe</span>
  <span m="3163200">I</span> <span m="3163230">can</span> <span m="3163350">even</span>
  <span m="3163530">project</span> <span m="3163890">them</span> <span m="3164010">onto</span>
  <span m="3164280">a</span> <span m="3164340">line</span> <span m="3164640">and</span>
  <span m="3164760">they</span> <span m="3164850">will</span> <span m="3165030">still</span>
  <span m="3165330">be</span> <span m="3165510">far</span> <span m="3165750">apart</span>
  <span m="3165990">from</span> <span m="3166170">each</span> <span m="3166320">other.</span>
  <span m="3167200">So</span> <span m="3167300">that's</span> <span m="3167400">what</span>
  <span m="3167550">you</span> <span m="3167730">want.</span> <span m="3168160">You</span>
  <span m="3168270">want</span> <span m="3168510">to</span> <span m="3168630">be</span>
  <span m="3168780">able</span> <span m="3169080">to</span> <span m="3169230">say,</span>
  <span m="3169920">when</span> <span m="3170040">I</span> <span m="3170130">take</span>
  <span m="3170370">my</span> <span m="3170550">points</span> <span m="3171930">and</span>
  <span m="3172080">I</span> <span m="3172230">say</span> <span m="3172650">I</span>
  <span m="3173010">project</span> <span m="3173460">them</span> <span m="3173610">onto</span>
  <span m="3173880">lower</span> <span m="3174100">dimensions,</span> <span m="3174610">I</span>
  <span m="3174720">do</span> <span m="3174900">not</span> <span m="3175200">want</span>
  <span m="3175440">them</span> <span m="3175620">to</span> <span m="3175740">collapse</span>
  <span m="3176190">into</span> <span m="3176460">one</span> <span m="3176670">single</span>
  <span m="3176970">point.</span> <span m="3177270">I</span> <span m="3177330">want</span>
  <span m="3177540">them</span> <span m="3177690">to</span> <span m="3177840">be</span>
  <span m="3178620">spread</span> <span m="3179190">as</span> <span m="3179310">possible</span>
  <span m="3179910">in</span> <span m="3180000">the</span> <span m="3180120">direction</span>
  <span m="3180540">on</span> <span m="3180720">which</span> <span m="3180930">I</span>
  <span m="3181260">project.</span></p><p><span m="3182400">And</span> <span m="3182490">this</span>
  <span m="3182700">is</span> <span m="3182790">what</span> <span m="3182940">we're</span>
  <span m="3183090">going</span> <span m="3183240">to</span> <span m="3183300">try</span>
  <span m="3183510">to</span> <span m="3183660">do.</span> <span m="3184000">And</span>
  <span m="3184470">of</span> <span m="3184590">course,</span> <span m="3185020">measuring</span>
  <span m="3185340">spread</span> <span m="3185790">between</span> <span m="3186150">points</span>
  <span m="3186510">can</span> <span m="3186720">be</span> <span m="3186840">done</span>
  <span m="3187080">in</span> <span m="3187200">many</span> <span m="3187470">ways,</span>
  <span m="3187860">right?</span> <span m="3188160">I</span> <span m="3188220">mean,</span>
  <span m="3188400">you</span> <span m="3188520">could</span> <span m="3188700">look</span>
  <span m="3189000">at,</span> <span m="3189540">I</span> <span m="3189630">don't</span>
  <span m="3189780">know,</span> <span m="3189960">sum</span> <span m="3190530">of</span>
  <span m="3190710">pairwise</span> <span m="3191280">distances</span> <span m="3191940">between</span>
  <span m="3192270">those</span> <span m="3192510">guys.</span> <span m="3192900">You</span>
  <span m="3193020">could</span> <span m="3193200">look</span> <span m="3193440">at</span>
  <span m="3194070">some</span> <span m="3194220">sort</span> <span m="3194400">of</span>
  <span m="3194490">energy.</span> <span m="3194790">You</span> <span m="3194880">can</span>
  <span m="3195060">look</span> <span m="3195180">at</span> <span m="3195300">many</span>
  <span m="3195570">ways</span> <span m="3195810">to</span> <span m="3196050">measure</span>
  <span m="3196380">of</span> <span m="3196480">spread</span> <span m="3196770">in</span>
  <span m="3196890">a</span> <span m="3196960">direction.</span></p><p><span m="3198240">But</span>
  <span m="3198430">variance</span> <span m="3198930">is</span> <span m="3199020">a</span>
  <span m="3199080">good</span> <span m="3199260">way</span> <span m="3199380">to</span>
  <span m="3199500">measure</span> <span m="3199740">of</span> <span m="3199840">spread</span>
  <span m="3200070">between</span> <span m="3200370">points.</span> <span m="3201150">If</span>
  <span m="3201270">you</span> <span m="3201360">have</span> <span m="3201510">a</span>
  <span m="3201540">lot</span> <span m="3201720">of</span> <span m="3202540">variance</span>
  <span m="3202920">between</span> <span m="3203250">your</span> <span m="3203370">points,</span>
  <span m="3203830">then</span> <span m="3204000">chances</span> <span m="3204390">are</span>
  <span m="3204480">they're</span> <span m="3204630">going</span> <span m="3204750">to</span>
  <span m="3204810">be</span> <span m="3204870">spread.</span> <span m="3205560">Now,</span>
  <span m="3205650">this</span> <span m="3205830">is</span> <span m="3205950">not</span>
  <span m="3206160">always</span> <span m="3206430">the</span> <span m="3206520">case,</span>
  <span m="3206880">right?</span> <span m="3207720">If</span> <span m="3207870">I</span>
  <span m="3207930">have</span> <span m="3208410">a</span> <span m="3208470">direction</span>
  <span m="3209010">in</span> <span m="3209130">which</span> <span m="3209340">all</span>
  <span m="3209490">my</span> <span m="3209640">points</span> <span m="3209970">are</span>
  <span m="3210060">clumped</span> <span m="3210480">onto</span> <span m="3211020">one</span>
  <span m="3211350">big</span> <span m="3211590">point</span> <span m="3212010">and</span>
  <span m="3212160">one</span> <span m="3212490">other</span> <span m="3212730">big</span>
  <span m="3212940">point,</span> <span m="3213640">it's</span> <span m="3213750">going</span>
  <span m="3213900">to</span> <span m="3213960">choose</span> <span m="3214230">this</span>
  <span m="3214470">because</span> <span m="3214710">that's</span> <span m="3214900">the</span>
  <span m="3214980">direction</span> <span m="3215460">that</span> <span m="3215550">has</span>
  <span m="3215760">a</span> <span m="3215790">lot</span> <span m="3215940">of</span>
  <span m="3216000">variance.</span> <span m="3217180">But</span> <span m="3217800">hopefully,</span>
  <span m="3218400">the</span> <span m="3218490">variance</span> <span m="3218840">is</span>
  <span m="3218910">going</span> <span m="3219030">to</span> <span m="3219090">spread</span>
  <span m="3219510">things</span> <span m="3219840">out</span> <span m="3220260">nicely.</span></p><p><span
  m="3221560">So</span> <span m="3222810">the</span> <span m="3223050">idea</span>
  <span m="3224290">of</span> <span m="3226500">principal</span> <span m="3226860">component</span>
  <span m="3227190">analysis</span> <span m="3227730">is</span> <span m="3227850">going</span>
  <span m="3228120">to</span> <span m="3228240">try</span> <span m="3228600">to</span>
  <span m="3228780">identify</span> <span m="3230040">those</span> <span m="3230280">variances--</span>
  <span m="3231330">those</span> <span m="3231570">directions</span> <span m="3232530">along</span>
  <span m="3232800">which</span> <span m="3233070">we</span> <span m="3233160">have</span>
  <span m="3233340">a</span> <span m="3233400">lot</span> <span m="3233550">of</span>
  <span m="3233610">variance.</span> <span m="3235740">Reciprocally,</span> <span
  m="3236520">we're</span> <span m="3236640">going</span> <span m="3236760">to</span>
  <span m="3236850">try</span> <span m="3237120">to</span> <span m="3237300">eliminate</span>
  <span m="3237870">the</span> <span m="3237990">directions</span> <span m="3238710">along</span>
  <span m="3239010">which</span> <span m="3239220">we</span> <span m="3239340">do</span>
  <span m="3239460">not</span> <span m="3239670">have</span> <span m="3240000">a</span>
  <span m="3240060">lot</span> <span m="3240240">of</span> <span m="3240340">variance,</span>
  <span m="3241230">OK?</span> <span m="3241890">And</span> <span m="3242010">let's</span>
  <span m="3242190">see</span> <span m="3242340">why.</span></p><p><span m="3242640">Well,</span>
  <span m="3245310">if--</span> <span m="3245910">so</span> <span m="3246510">here's</span>
  <span m="3246780">the</span> <span m="3246900">first</span> <span m="3247500">claim.</span>
  <span m="3248130">If</span> <span m="3248370">you</span> <span m="3248850">transpose</span>
  <span m="3249610">Su</span> <span m="3250290">is</span> <span m="3250470">equal</span>
  <span m="3250800">to</span> <span m="3250950">0,</span> <span m="3253190">what's</span>
  <span m="3253400">happening?</span> <span m="3254000">Well,</span> <span m="3254150">I</span>
  <span m="3254270">know</span> <span m="3254450">that</span> <span m="3254650">an</span>
  <span m="3254740">empirical</span> <span m="3255200">variance</span> <span m="3255540">is</span>
  <span m="3255650">equal</span> <span m="3255890">to</span> <span m="3256010">0.</span>
  <span m="3257360">What</span> <span m="3257450">does</span> <span m="3257570">it</span>
  <span m="3257690">mean</span> <span m="3257960">for</span> <span m="3258110">an</span>
  <span m="3258200">empirical</span> <span m="3258650">variance</span> <span m="3258950">to</span>
  <span m="3259040">be</span> <span m="3259100">equal</span> <span m="3259310">to</span>
  <span m="3259400">0?</span> <span m="3262160">So</span> <span m="3262270">I</span>
  <span m="3262360">give</span> <span m="3262540">you</span> <span m="3262630">a</span>
  <span m="3262660">bunch</span> <span m="3262900">of</span> <span m="3262990">points,</span>
  <span m="3263470">right?</span> <span m="3263680">So</span> <span m="3263830">those</span>
  <span m="3264070">points</span> <span m="3264430">are</span> <span m="3265180">those</span>
  <span m="3265390">points--</span> <span m="3265870">u</span> <span m="3266020">transpose</span>
  <span m="3266420">X1,</span> <span m="3266830">u</span> <span m="3266890">transpose--</span>
  <span m="3267250">those</span> <span m="3267460">are</span> <span m="3267550">a</span>
  <span m="3267580">bunch</span> <span m="3267820">of</span> <span m="3267910">numbers.</span>
  <span m="3269360">What</span> <span m="3269460">does</span> <span m="3269470">it</span>
  <span m="3269590">mean</span> <span m="3269920">to</span> <span m="3270130">have</span>
  <span m="3270340">the</span> <span m="3270430">empirical</span> <span m="3270760">variance</span>
  <span m="3271090">of</span> <span m="3271180">those</span> <span m="3271360">points</span>
  <span m="3271570">being</span> <span m="3271750">equal</span> <span m="3271960">to</span>
  <span m="3272050">0?</span></p><p><span m="3273694">AUDIENCE:</span> <span m="3273840">They're</span>
  <span m="3273986">all</span> <span m="3274132">the same.</span></p><p><span m="3274570">PHILIPPE
  RIGOLLET:</span> <span m="3274645">They're</span> <span m="3274720">all</span> <span
  m="3274870">the</span> <span m="3274990">same.</span> <span m="3276590">So</span>
  <span m="3276610">what</span> <span m="3276730">it</span> <span m="3276850">means</span>
  <span m="3278260">is</span> <span m="3278380">that</span> <span m="3278590">when</span>
  <span m="3278740">I</span> <span m="3278860">have</span> <span m="3279100">my</span>
  <span m="3279280">points,</span> <span m="3283390">right?</span> <span m="3283680">So,</span>
  <span m="3284310">can</span> <span m="3284430">you</span> <span m="3284580">find</span>
  <span m="3284820">a</span> <span m="3284880">direction</span> <span m="3285330">for</span>
  <span m="3285480">those</span> <span m="3285690">points</span> <span m="3286020">in</span>
  <span m="3286140">which</span> <span m="3286350">they</span> <span m="3286470">project</span>
  <span m="3287760">to</span> <span m="3287970">all</span> <span m="3288240">the</span>
  <span m="3288330">same</span> <span m="3288570">point?</span> <span m="3291400">No,</span>
  <span m="3291880">right?</span> <span m="3292360">There's</span> <span m="3292510">no</span>
  <span m="3292630">such</span> <span m="3292900">thing.</span> <span m="3293590">For</span>
  <span m="3293800">this</span> <span m="3294040">to</span> <span m="3294160">happen,</span>
  <span m="3294550">you</span> <span m="3294670">have</span> <span m="3294880">to</span>
  <span m="3295030">have</span> <span m="3295210">your</span> <span m="3295360">points</span>
  <span m="3295660">which</span> <span m="3295870">are</span> <span m="3295990">perfectly</span>
  <span m="3296560">aligned.</span> <span m="3298240">And</span> <span m="3298260">then</span>
  <span m="3298470">when</span> <span m="3298620">you're</span> <span m="3298770">going</span>
  <span m="3298890">to</span> <span m="3298950">project</span> <span m="3299390">onto</span>
  <span m="3299700">the</span> <span m="3299900">orthogonal</span> <span m="3300420">of</span>
  <span m="3300540">this</span> <span m="3300720">guy,</span> <span m="3301740">they're</span>
  <span m="3301830">going</span> <span m="3301950">to</span> <span m="3302010">all</span>
  <span m="3302220">project</span> <span m="3302790">to</span> <span m="3302940">the</span>
  <span m="3303060">same</span> <span m="3303390">point</span> <span m="3303690">here,</span>
  <span m="3305020">which</span> <span m="3305130">means</span> <span m="3305340">that</span>
  <span m="3305460">the</span> <span m="3305580">empirical</span> <span m="3306000">variance</span>
  <span m="3306340">is</span> <span m="3306450">going</span> <span m="3306600">to</span>
  <span m="3306660">be</span> <span m="3306750">0.</span></p><p><span m="3308790">Now,</span>
  <span m="3309270">this</span> <span m="3309450">is</span> <span m="3309570">an</span>
  <span m="3309660">extreme</span> <span m="3309960">case.</span> <span m="3310270">This</span>
  <span m="3310350">will</span> <span m="3310470">never</span> <span m="3310770">happen</span>
  <span m="3311010">in</span> <span m="3311130">practice,</span> <span m="3311760">because</span>
  <span m="3312060">if</span> <span m="3312180">that</span> <span m="3312330">happens,</span>
  <span m="3312900">well,</span> <span m="3313530">I</span> <span m="3313590">mean,</span>
  <span m="3313840">you</span> <span m="3313940">can</span> <span m="3314130">basically</span>
  <span m="3314730">figure</span> <span m="3315090">that</span> <span m="3315270">out</span>
  <span m="3315390">very</span> <span m="3315630">quickly.</span> <span m="3316850">So</span>
  <span m="3319480">in</span> <span m="3319600">the</span> <span m="3319690">same</span>
  <span m="3319990">way,</span> <span m="3320740">it's</span> <span m="3320890">very</span>
  <span m="3321050">unlikely</span> <span m="3321520">that</span> <span m="3321730">you're</span>
  <span m="3321850">going</span> <span m="3321970">to</span> <span m="3322060">have
  u</span> <span m="3322540">transpose</span> <span m="3323050">sigma</span> <span
  m="3323325">u,</span> <span m="3323600">which</span> <span m="3323710">is</span>
  <span m="3323830">equal</span> <span m="3324070">to</span> <span m="3324190">0,</span>
  <span m="3324550">which</span> <span m="3324730">means</span> <span m="3324970">that,</span>
  <span m="3325450">essentially,</span> <span m="3326050">all</span> <span m="3326230">your</span>
  <span m="3326350">points</span> <span m="3326710">are</span> <span m="3326860">[INAUDIBLE]</span>
  <span m="3327600">or</span> <span m="3327760">let's</span> <span m="3327940">say</span>
  <span m="3328060">all</span> <span m="3328240">of</span> <span m="3328360">them</span>
  <span m="3328510">are</span> <span m="3328690">orthogonal</span> <span m="3329200">to</span>
  <span m="3329350">u,</span> <span m="3329905">right? So</span> <span m="3330250">it's</span>
  <span m="3330400">exactly</span> <span m="3330760">the</span> <span m="3330850">same</span>
  <span m="3331060">thing.</span> <span m="3331360">It just</span> <span m="3331480">says</span>
  <span m="3331660">that</span> <span m="3331810">in</span> <span m="3331900">the</span>
  <span m="3331990">population</span> <span m="3332560">case,</span> <span m="3333330">there's</span>
  <span m="3333550">no probability</span> <span m="3334900">that</span> <span m="3335110">your</span>
  <span m="3335290">points</span> <span m="3335650">deviate</span> <span m="3336220">from</span>
  <span m="3336490">this</span> <span m="3336670">guy</span> <span m="3336960">here.</span>
  <span m="3337510">This</span> <span m="3337630">happens</span> <span m="3337960">with</span>
  <span m="3338590">zero</span> <span m="3338860">probability,</span> <span m="3341070">OK?</span></p><p><span
  m="3341400">And</span> <span m="3341550">that's</span> <span m="3341700">just</span>
  <span m="3341880">because</span> <span m="3342210">if</span> <span m="3342330">you</span>
  <span m="3342420">look</span> <span m="3342600">at</span> <span m="3342690">the</span>
  <span m="3342780">variance</span> <span m="3343290">of</span> <span m="3343440">this</span>
  <span m="3343620">guy,</span> <span m="3344690">it's</span> <span m="3344700">going</span>
  <span m="3344850">to</span> <span m="3344910">be</span> <span m="3345000">0.</span>
  <span m="3346690">And</span> <span m="3346840">then</span> <span m="3347170">that</span>
  <span m="3347350">means</span> <span m="3347560">that</span> <span m="3347760">there's</span>
  <span m="3348220">no</span> <span m="3348400">deviation.</span> <span m="3348910">By</span>
  <span m="3349000">the</span> <span m="3349090">way,</span> <span m="3349310">I'm</span>
  <span m="3349390">using</span> <span m="3349780">the</span> <span m="3349990">name</span>
  <span m="3350290">projection</span> <span m="3351430">when</span> <span m="3351580">I</span>
  <span m="3351640">talk</span> <span m="3351940">about</span> <span m="3352750">u</span>
  <span m="3354430">transpose</span> <span m="3355000">X,</span> <span m="3355300">right?</span>
  <span m="3355510">So</span> <span m="3356020">let's</span> <span m="3356170">just</span>
  <span m="3356350">be</span> <span m="3356470">clear</span> <span m="3356770">about</span>
  <span m="3357040">this.</span> <span m="3359170">If</span> <span m="3359370">you--</span>
  <span m="3361120">so</span> <span m="3361330">let's</span> <span m="3361480">say</span>
  <span m="3361600">I</span> <span m="3361630">have</span> <span m="3361780">a</span>
  <span m="3361840">bunch</span> <span m="3362050">of</span> <span m="3362200">points,</span>
  <span m="3364090">and</span> <span m="3364240">u</span> <span m="3364510">is</span>
  <span m="3364690">a</span> <span m="3364750">vector</span> <span m="3365170">in</span>
  <span m="3365290">this</span> <span m="3365440">direction.</span> <span m="3366050">And</span>
  <span m="3366150">let's</span> <span m="3366190">say</span> <span m="3366310">that</span>
  <span m="3366550">u</span> <span m="3367412">has</span> <span m="3367824">the--</span>
  <span m="3368650">so</span> <span m="3368830">this</span> <span m="3369040">is</span>
  <span m="3369130">0.</span> <span m="3370120">This</span> <span m="3370300">is</span>
  <span m="3370450">u.</span> <span m="3370720">And</span> <span m="3370840">let's</span>
  <span m="3370960">say</span> <span m="3371050">that</span> <span m="3371230">u</span>
  <span m="3371590">has</span> <span m="3371770">norm,</span> <span m="3372010">1,</span>
  <span m="3375710">OK?</span></p><p><span m="3377560">When</span> <span m="3377740">I</span>
  <span m="3377860">look,</span> <span m="3378400">what</span> <span m="3378610">is</span>
  <span m="3378730">the</span> <span m="3378820">coordinate</span> <span m="3379570">of</span>
  <span m="3379810">the</span> <span m="3379930">projection?</span> <span m="3381140">So</span>
  <span m="3381190">what</span> <span m="3381340">is</span> <span m="3381430">the</span>
  <span m="3381580">length</span> <span m="3381910">of</span> <span m="3382030">this</span>
  <span m="3382240">guy</span> <span m="3382510">here?</span> <span m="3383860">Let's</span>
  <span m="3384010">call</span> <span m="3384190">this</span> <span m="3384340">guy</span>
  <span m="3384550">X1.</span> <span m="3385750">What</span> <span m="3385860">is</span>
  <span m="3385960">the</span> <span m="3386050">length</span> <span m="3386320">of</span>
  <span m="3386440">this</span> <span m="3386620">guy?</span> <span m="3391150">In</span>
  <span m="3391240">terms</span> <span m="3391480">of</span> <span m="3391680">inner</span>
  <span m="3391870">products?</span> <span m="3395990">This</span> <span m="3396140">is</span>
  <span m="3396260">exactly</span> <span m="3396860">u</span> <span m="3397130">transpose</span>
  <span m="3397630">X1.</span> <span m="3399678">This</span> <span m="3400090">length</span>
  <span m="3400410">here,</span> <span m="3401250">if</span> <span m="3401400">this</span>
  <span m="3401580">is</span> <span m="3401730">X2,</span> <span m="3402560">this
  is</span> <span m="3402900">exactly</span> <span m="3403650">u</span> <span m="3403890">transpose</span>
  <span m="3404430">X2,</span> <span m="3406150">OK?</span> <span m="3406580">So</span>
  <span m="3406760">those--</span> <span m="3407790">u</span> <span m="3408020">transpose</span>
  <span m="3408620">X</span> <span m="3409250">measure</span> <span m="3409580">exactly</span>
  <span m="3411740">the</span> <span m="3411860">distance</span> <span m="3412430">to</span>
  <span m="3412580">the</span> <span m="3412730">origin</span> <span m="3413570">of</span>
  <span m="3414680">those--</span> <span m="3415700">I</span> <span m="3415760">mean,</span>
  <span m="3417240">it's</span> <span m="3417380">really--</span> <span m="3418310">think</span>
  <span m="3418490">of</span> <span m="3418580">it</span> <span m="3418670">as</span>
  <span m="3418820">being</span> <span m="3419120">just</span> <span m="3419450">an</span>
  <span m="3419690">x-axis</span> <span m="3420440">thing.</span> <span m="3421100">You</span>
  <span m="3421160">just</span> <span m="3421370">have</span> <span m="3421490">a</span>
  <span m="3421550">bunch</span> <span m="3421790">of</span> <span m="3421910">points.</span>
  <span m="3422220">You</span> <span m="3422330">have</span> <span m="3422450">an</span>
  <span m="3422540">origin.</span> <span m="3422960">And</span> <span m="3423080">it's</span>
  <span m="3423230">really</span> <span m="3423500">just</span> <span m="3423680">telling</span>
  <span m="3423950">you</span> <span m="3424370">what</span> <span m="3424520">the</span>
  <span m="3424640">coordinate</span> <span m="3425140">on</span> <span m="3425270">this</span>
  <span m="3425450">axis</span> <span m="3425840">is</span> <span m="3425930">going</span>
  <span m="3426050">to</span> <span m="3426140">be,</span> <span m="3426970">right?</span></p><p><span
  m="3427670">So</span> <span m="3427760">in</span> <span m="3427850">particular,</span>
  <span m="3428920">if</span> <span m="3429080">the</span> <span m="3429290">empirical</span>
  <span m="3429860">variance</span> <span m="3430115">is</span> <span m="3430370">0,</span>
  <span m="3430820">it</span> <span m="3430940">means</span> <span m="3431150">that</span>
  <span m="3431330">all</span> <span m="3431510">these</span> <span m="3431690">points</span>
  <span m="3432050">project</span> <span m="3432470">to</span> <span m="3432590">the</span>
  <span m="3432710">same</span> <span m="3432980">point,</span> <span m="3434070">which</span>
  <span m="3434180">means</span> <span m="3434390">that</span> <span m="3434480">they</span>
  <span m="3434600">have</span> <span m="3434840">to</span> <span m="3434960">be</span>
  <span m="3435130">orthogonal</span> <span m="3435580">to</span> <span m="3435680">this</span>
  <span m="3435860">guy.</span> <span m="3437030">And</span> <span m="3437120">you</span>
  <span m="3437180">can</span> <span m="3437330">think</span> <span m="3437480">of</span>
  <span m="3437540">it</span> <span m="3437630">as</span> <span m="3437750">being</span>
  <span m="3437960">also</span> <span m="3438260">maybe</span> <span m="3438560">an</span>
  <span m="3438650">entire</span> <span m="3439010">plane</span> <span m="3439370">that's</span>
  <span m="3439550">orthogonal</span> <span m="3440000">to</span> <span m="3440090">this</span>
  <span m="3440300">line,</span> <span m="3441334">OK?</span> <span m="3443990">So</span>
  <span m="3444090">that's</span> <span m="3444160">why</span> <span m="3444310">I</span>
  <span m="3444370">talk</span> <span m="3444700">about</span> <span m="3445660">projection,</span>
  <span m="3446590">because</span> <span m="3446890">the</span> <span m="3447170">inner</span>
  <span m="3447290">products,</span> <span m="3447760">u</span> <span m="3448030">transpose</span>
  <span m="3448600">X,</span> <span m="3449560">is</span> <span m="3449800">really</span>
  <span m="3450640">measuring</span> <span m="3453510">the</span> <span m="3453880">coordinates</span>
  <span m="3454930">of</span> <span m="3455170">X</span> <span m="3456220">when</span>
  <span m="3456520">u</span> <span m="3456730">becomes</span> <span m="3457990">the</span>
  <span m="3458140">x-axis.</span></p><p><span m="3459410">Now,</span> <span m="3459550">if</span>
  <span m="3459760">u</span> <span m="3460660">does</span> <span m="3460840">not</span>
  <span m="3461050">have</span> <span m="3461240">norm</span> <span m="3461590">1,</span>
  <span m="3462340">then</span> <span m="3462460">you</span> <span m="3462580">just</span>
  <span m="3462820">have</span> <span m="3463260">a</span> <span m="3463330">change</span>
  <span m="3463690">of</span> <span m="3463780">scale</span> <span m="3464230">here.
  You</span> <span m="3464500">just</span> <span m="3464680">have</span> <span m="3464800">a</span>
  <span m="3464860">change</span> <span m="3465130">of</span> <span m="3465220">unit,</span>
  <span m="3466392">right?</span> <span m="3466790">So</span> <span m="3466900">this</span>
  <span m="3467140">is</span> <span m="3467290">really</span> <span m="3468400">u</span>
  <span m="3468820">times</span> <span m="3469320">X1.</span> <span m="3471560">The</span>
  <span m="3471820">coordinates</span> <span m="3472300">should</span> <span m="3472480">really</span>
  <span m="3472750">be</span> <span m="3472900">divided</span> <span m="3473290">by</span>
  <span m="3473410">the norm</span> <span m="3473580">of u.</span></p><p><span m="3479150">OK,</span>
  <span m="3481100">so</span> <span m="3481280">now,</span> <span m="3483640">just</span>
  <span m="3484040">in</span> <span m="3484130">the</span> <span m="3484220">same</span>
  <span m="3484430">way--</span> <span m="3484550">so</span> <span m="3484970">we're</span>
  <span m="3485120">never</span> <span m="3485360">going</span> <span m="3485480">to</span>
  <span m="3485540">have</span> <span m="3485690">exactly</span> <span m="3486230">0.</span>
  <span m="3487160">But</span> <span m="3487310">if</span> <span m="3487400">we</span>
  <span m="3487490">[INAUDIBLE]</span> <span m="3487820">the</span> <span m="3487940">other</span>
  <span m="3488210">end,</span> <span m="3488810">if</span> <span m="3489080">u</span>
  <span m="3489320">transpose</span> <span m="3489920">Su</span> <span m="3490400">is</span>
  <span m="3490580">large,</span> <span m="3491360">what</span> <span m="3491450">does</span>
  <span m="3491600">it</span> <span m="3491720">mean?</span> <span m="3494990">It</span>
  <span m="3495070">means</span> <span m="3495370">that</span> <span m="3495610">when</span>
  <span m="3495820">I</span> <span m="3495910">look</span> <span m="3496120">at</span>
  <span m="3496240">my</span> <span m="3496450">points</span> <span m="3497740">as</span>
  <span m="3497980">projected</span> <span m="3498790">onto</span> <span m="3499210">the</span>
  <span m="3499540">axis</span> <span m="3500170">generated</span> <span m="3500710">by</span>
  <span m="3500890">u,</span> <span m="3502510">they're</span> <span m="3502630">going</span>
  <span m="3502780">to</span> <span m="3502870">have</span> <span m="3503080">a</span>
  <span m="3503140">lot</span> <span m="3503350">of</span> <span m="3503410">variance.</span>
  <span m="3503860">They're</span> <span m="3503980">going</span> <span m="3504100">to</span>
  <span m="3504160">be</span> <span m="3504250">far</span> <span m="3504610">away</span>
  <span m="3504850">from</span> <span m="3505030">each</span> <span m="3505210">other</span>
  <span m="3505480">in</span> <span m="3505600">average,</span> <span m="3505930">right?</span>
  <span m="3506350">That's</span> <span m="3506530">what</span> <span m="3506860">large</span>
  <span m="3507130">variance</span> <span m="3507520">means,</span> <span m="3508510">or</span>
  <span m="3508630">at</span> <span m="3508720">least</span> <span m="3508900">large</span>
  <span m="3509170">empirical</span> <span m="3509620">variance</span> <span m="3509980">means.</span>
  <span m="3511310">And</span> <span m="3511490">same</span> <span m="3511760">thing</span>
  <span m="3512000">for</span> <span m="3512630">u.</span></p><p><span m="3514690">So</span>
  <span m="3514840">what</span> <span m="3515020">we're</span> <span m="3515140">going</span>
  <span m="3515290">to</span> <span m="3515350">try</span> <span m="3515560">to</span>
  <span m="3515680">find</span> <span m="3516130">is a</span> <span m="3516530">u</span>
  <span m="3518310">that</span> <span m="3518490">maximizes</span> <span m="3519210">this.</span>
  <span m="3519870">If</span> <span m="3519990">I</span> <span m="3520050">can</span>
  <span m="3520260">find</span> <span m="3520530">a</span> <span m="3520590">u</span>
  <span m="3521280">that</span> <span m="3521430">maximizes</span> <span m="3522050">this</span>
  <span m="3522230">so</span> <span m="3522360">I</span> <span m="3522420">can</span>
  <span m="3522600">look</span> <span m="3522780">in</span> <span m="3522900">every</span>
  <span m="3523170">direction,</span> <span m="3524790">and</span> <span m="3524910">suddenly
  I</span> <span m="3525360">find</span> <span m="3525590">a</span> <span m="3525660">direction</span>
  <span m="3526060">in</span> <span m="3526200">which</span> <span m="3526410">the</span>
  <span m="3526530">spread</span> <span m="3526980">is</span> <span m="3527100">massive,</span>
  <span m="3528360">then</span> <span m="3528510">that's</span> <span m="3528750">a</span>
  <span m="3528840">point</span> <span m="3529170">on</span> <span m="3529290">which</span>
  <span m="3529510">I'm</span> <span m="3529640">basically</span> <span m="3530070">the</span>
  <span m="3530220">less</span> <span m="3530460">likely</span> <span m="3531270">to</span>
  <span m="3531390">have</span> <span m="3531600">my</span> <span m="3531780">points</span>
  <span m="3532260">project</span> <span m="3532710">onto</span> <span m="3532950">each</span>
  <span m="3533130">other</span> <span m="3533400">and</span> <span m="3533490">collide,</span>
  <span m="3534540">right?</span> <span m="3535080">At</span> <span m="3535170">least</span>
  <span m="3535380">I</span> <span m="3535470">know</span> <span m="3535650">they're</span>
  <span m="3535800">going</span> <span m="3535920">to</span> <span m="3535980">project</span>
  <span m="3536490">at</span> <span m="3536550">least</span> <span m="3536790">onto</span>
  <span m="3537060">two</span> <span m="3537240">points.</span></p><p><span m="3539710">So</span>
  <span m="3540700">the</span> <span m="3540790">idea</span> <span m="3541090">now</span>
  <span m="3541300">is</span> <span m="3541420">to</span> <span m="3541510">say,</span>
  <span m="3541790">OK,</span> <span m="3542030">let's</span> <span m="3542080">try</span>
  <span m="3542290">to</span> <span m="3542440">maximize</span> <span m="3543300">this</span>
  <span m="3543770">spread,</span> <span m="3544390">right?</span> <span m="3544630">So</span>
  <span m="3545200">we're</span> <span m="3545290">going</span> <span m="3545410">to</span>
  <span m="3545470">try</span> <span m="3545710">to</span> <span m="3545860">find</span>
  <span m="3546160">the</span> <span m="3546280">maximum</span> <span m="3547690">over
  all</span> <span m="3548170">u's</span> <span m="3549130">of</span> <span m="3549340">u</span>
  <span m="3549580">transpose</span> <span m="3550240">Su.</span> <span m="3552970">And</span>
  <span m="3553060">that's</span> <span m="3553270">going</span> <span m="3553390">to</span>
  <span m="3553450">be</span> <span m="3553540">the</span> <span m="3553630">direction</span>
  <span m="3554080">that</span> <span m="3554260">maximizes</span> <span m="3555010">the</span>
  <span m="3555130">empirical</span> <span m="3555520">variance.</span> <span m="3555930">Now</span>
  <span m="3556030">of</span> <span m="3556150">course,</span> <span m="3556360">if</span>
  <span m="3556510">I</span> <span m="3556600">read</span> <span m="3556810">it</span>
  <span m="3556930">like</span> <span m="3557170">that</span> <span m="3557470">for</span>
  <span m="3557710">all</span> <span m="3557920">u's</span> <span m="3560770">in Rd,</span>
  <span m="3562075">what</span> <span m="3562510">is</span> <span m="3562600">the</span>
  <span m="3562690">value of this</span> <span m="3563178">maximum?</span></p><p><span
  m="3568060">It's</span> <span m="3568340">infinity,</span> <span m="3568920">right?</span>
  <span m="3569220">Because</span> <span m="3569490">I</span> <span m="3569550">can</span>
  <span m="3569730">always</span> <span m="3570030">multiply</span> <span m="3570510">u</span>
  <span m="3570750">by</span> <span m="3571700">10,</span> <span m="3572160">and</span>
  <span m="3572280">this</span> <span m="3572460">entire</span> <span m="3572820">thing</span>
  <span m="3573000">is</span> <span m="3573090">going</span> <span m="3573210">to</span>
  <span m="3573290">multiplied</span> <span m="3573730">by</span> <span m="3573870">100.</span>
  <span m="3574810">So</span> <span m="3574830">I'm</span> <span m="3574950">just</span>
  <span m="3575130">going</span> <span m="3575250">to</span> <span m="3575310">take</span>
  <span m="3575580">u</span> <span m="3575760">as</span> <span m="3575880">large</span>
  <span m="3576090">as</span> <span m="3576210">I</span> <span m="3576330">want,</span>
  <span m="3576620">and</span> <span m="3576740">this</span> <span m="3576860">thing</span>
  <span m="3576990">is</span> <span m="3577050">going</span> <span m="3577170">to</span>
  <span m="3577230">be as large</span> <span m="3577520">as</span> <span m="3577670">I</span>
  <span m="3577770">want,</span> <span m="3578320">and</span> <span m="3578430">so</span>
  <span m="3578550">I</span> <span m="3578640">need</span> <span m="3578820">to</span>
  <span m="3578910">constrain</span> <span m="3579390">u.</span> <span m="3580050">And</span>
  <span m="3580170">as</span> <span m="3580320">I</span> <span m="3580410">said,</span>
  <span m="3580650">I</span> <span m="3580770">need</span> <span m="3580950">to</span>
  <span m="3581100">have</span> <span m="3581310">u</span> <span m="3581990">of</span>
  <span m="3582280">size</span> <span m="3582600">1</span> <span m="3582840">to</span>
  <span m="3582960">talk</span> <span m="3583260">about</span> <span m="3583650">coordinates</span>
  <span m="3584280">in</span> <span m="3584400">the</span> <span m="3584490">system</span>
  <span m="3585510">generated</span> <span m="3585990">by</span> <span m="3586200">u</span>
  <span m="3586410">like</span> <span m="3586650">this.</span> <span m="3587340">So</span>
  <span m="3587460">I'm</span> <span m="3587580">just</span> <span m="3587760">going</span>
  <span m="3587880">to</span> <span m="3587970">constrain</span> <span m="3588570">u</span>
  <span m="3589060">to</span> <span m="3589140">have</span> <span m="3590730">Euclidean</span>
  <span m="3591150">norm</span> <span m="3591450">equal</span> <span m="3591690">to</span>
  <span m="3591870">1,</span> <span m="3593068">OK?</span></p><p><span m="3595490">So</span>
  <span m="3595610">that's</span> <span m="3595790">going</span> <span m="3595940">to</span>
  <span m="3596030">be</span> <span m="3596120">my</span> <span m="3596300">goal--</span>
  <span m="3596750">trying</span> <span m="3597050">to</span> <span m="3597200">find</span>
  <span m="3598520">the</span> <span m="3598640">largest</span> <span m="3599120">possible</span>
  <span m="3599970">u</span> <span m="3600240">transpose</span> <span m="3600535">Su,</span>
  <span m="3601100">or</span> <span m="3601250">in</span> <span m="3601370">other</span>
  <span m="3601580">words,</span> <span m="3602030">empirical</span> <span m="3602570">variance</span>
  <span m="3603170">of</span> <span m="3603290">the</span> <span m="3603380">points</span>
  <span m="3603680">projected</span> <span m="3604190">onto</span> <span m="3604430">the</span>
  <span m="3604580">direction</span> <span m="3605030">u</span> <span m="3605600">when</span>
  <span m="3605780">u</span> <span m="3606090">is</span> <span m="3606320">of</span>
  <span m="3606500">norm</span> <span m="3606820">1,</span> <span m="3607520">which</span>
  <span m="3608330">justifies</span> <span m="3609050">to</span> <span m="3609230">use</span>
  <span m="3609410">the</span> <span m="3609530">word,</span> <span m="3609740">&quot;direction,&quot;</span>
  <span m="3611070">and</span> <span m="3611360">because</span> <span m="3611600">there's</span>
  <span m="3611780">no</span> <span m="3611900">magnitude</span> <span m="3612380">to</span>
  <span m="3612500">this</span> <span m="3612710">u.</span></p><p><span m="3617770">OK,</span>
  <span m="3619670">so</span> <span m="3621330">how</span> <span m="3621510">am</span>
  <span m="3621660">I</span> <span m="3621690">going</span> <span m="3621810">to</span>
  <span m="3621900">do</span> <span m="3622050">this?</span> <span m="3622410">I</span>
  <span m="3622510">could</span> <span m="3622650">just</span> <span m="3623520">fold</span>
  <span m="3623820">and</span> <span m="3623910">say,</span> <span m="3624150">let's</span>
  <span m="3624330">just</span> <span m="3624720">optimize</span> <span m="3625230">this</span>
  <span m="3625410">thing,</span> <span m="3626460">right?</span> <span m="3626700">Let's</span>
  <span m="3626880">just</span> <span m="3627600">take</span> <span m="3627780">this</span>
  <span m="3627960">problem.</span> <span m="3628540">It</span> <span m="3628690">says</span>
  <span m="3628950">maximize</span> <span m="3629610">a</span> <span m="3629700">function</span>
  <span m="3630640">onto</span> <span m="3630960">some</span> <span m="3631170">constraints.</span>
  <span m="3632250">Immediately,</span> <span m="3632940">the</span> <span m="3633080">constraint</span>
  <span m="3633520">is</span> <span m="3633630">sort</span> <span m="3633780">of</span>
  <span m="3633870">nasty.</span> <span m="3634125">I'm</span> <span m="3634380">on</span>
  <span m="3634710">a</span> <span m="3634770">sphere,</span> <span m="3635085">and</span>
  <span m="3635400">I'm</span> <span m="3635520">trying</span> <span m="3635730">to</span>
  <span m="3635880">move</span> <span m="3636120">points</span> <span m="3636390">on</span>
  <span m="3636480">the</span> <span m="3636570">sphere.</span> <span m="3637290">And</span>
  <span m="3637410">I'm</span> <span m="3637470">maximizing</span> <span m="3638130">this</span>
  <span m="3638310">thing</span> <span m="3638490">which</span> <span m="3638670">actually</span>
  <span m="3638970">happens</span> <span m="3639300">to</span> <span m="3639390">be</span>
  <span m="3639510">convex.</span> <span m="3640320">And</span> <span m="3640440">we
  know we</span> <span m="3640800">know</span> <span m="3640950">how</span> <span
  m="3641070">to</span> <span m="3641190">minimize</span> <span m="3641640">convex</span>
  <span m="3642000">functions,</span> <span m="3642390">but</span> <span m="3642540">maximize</span>
  <span m="3643110">them</span> <span m="3643620">is</span> <span m="3643770">a</span>
  <span m="3643830">different</span> <span m="3644130">question.</span></p><p><span
  m="3645280">And</span> <span m="3645380">so</span> <span m="3645390">this</span>
  <span m="3645600">problem</span> <span m="3646010">might</span> <span m="3646200">be</span>
  <span m="3646320">super</span> <span m="3646650">hard.</span> <span m="3647340">So</span>
  <span m="3647460">I</span> <span m="3647520">can</span> <span m="3647670">just</span>
  <span m="3648060">say,</span> <span m="3648210">OK,</span> <span m="3648540">here's</span>
  <span m="3648870">what</span> <span m="3649020">I</span> <span m="3649080">want</span>
  <span m="3649260">to</span> <span m="3649320">do,</span> <span m="3650010">and</span>
  <span m="3650140">let</span> <span m="3650320">me</span> <span m="3650430">give</span>
  <span m="3650640">that</span> <span m="3650880">to</span> <span m="3651930">an</span>
  <span m="3652050">optimizer</span> <span m="3652950">and</span> <span m="3653070">just</span>
  <span m="3653250">hope</span> <span m="3653430">that</span> <span m="3653610">the</span>
  <span m="3653700">optimizer</span> <span m="3654300">can</span> <span m="3654480">solve</span>
  <span m="3654690">this</span> <span m="3654840">problem</span> <span m="3655110">for</span>
  <span m="3655240">me.</span> <span m="3656010">That's</span> <span m="3656190">one</span>
  <span m="3656340">thing</span> <span m="3656550">we</span> <span m="3656640">can</span>
  <span m="3656820">do.</span> <span m="3657630">Now</span> <span m="3657810">as</span>
  <span m="3657960">you</span> <span m="3658020">can</span> <span m="3658140">imagine,</span>
  <span m="3658470">PCA</span> <span m="3658780">is</span> <span m="3659090">so</span>
  <span m="3659340">well</span> <span m="3659550">spread,</span> <span m="3659940">right?</span>
  <span m="3660150">Principal</span> <span m="3660460">component</span> <span m="3660870">analysis</span>
  <span m="3661440">is</span> <span m="3661500">something</span> <span m="3661800">that</span>
  <span m="3661920">people</span> <span m="3662190">do</span> <span m="3662340">constantly.</span>
  <span m="3663700">And</span> <span m="3663750">so</span> <span m="3663930">that</span>
  <span m="3664110">means</span> <span m="3664320">that</span> <span m="3664440">we</span>
  <span m="3664560">know</span> <span m="3664740">how</span> <span m="3664860">to</span>
  <span m="3665010">do</span> <span m="3665160">this</span> <span m="3665370">fast.</span>
  <span m="3666190">So</span> <span m="3666210">that's</span> <span m="3666510">one</span>
  <span m="3666780">thing.</span></p><p><span m="3667600">The</span> <span m="3667700">other</span>
  <span m="3667800">thing</span> <span m="3667890">that</span> <span m="3667980">you</span>
  <span m="3668070">should</span> <span m="3668250">probably</span> <span m="3668580">question</span>
  <span m="3669090">about</span> <span m="3669450">why--</span> <span m="3670740">if</span>
  <span m="3670800">this</span> <span m="3671040">thing</span> <span m="3671190">is</span>
  <span m="3671310">actually</span> <span m="3671640">difficult,</span> <span m="3672330">why</span>
  <span m="3672630">in</span> <span m="3672720">the</span> <span m="3672840">world</span>
  <span m="3673110">would</span> <span m="3673290">you</span> <span m="3673410">even</span>
  <span m="3673650">choose</span> <span m="3674100">the</span> <span m="3674220">variance</span>
  <span m="3674820">as</span> <span m="3675000">a</span> <span m="3675060">measure</span>
  <span m="3675390">of</span> <span m="3675480">spread</span> <span m="3676200">if</span>
  <span m="3676410">there's</span> <span m="3676560">so</span> <span m="3676780">many</span>
  <span m="3677460">measures</span> <span m="3677790">of</span> <span m="3677910">spread,</span>
  <span m="3678380">right?</span> <span m="3679020">The</span> <span m="3679110">variance</span>
  <span m="3679590">is</span> <span m="3679740">one</span> <span m="3680010">measure</span>
  <span m="3680250">of</span> <span m="3680370">spread.</span> <span m="3681270">It's</span>
  <span m="3681390">not</span> <span m="3681570">guaranteed</span> <span m="3682110">that</span>
  <span m="3682290">everything</span> <span m="3682680">is</span> <span m="3682800">going</span>
  <span m="3682920">to</span> <span m="3682980">project</span> <span m="3683400">nicely</span>
  <span m="3683880">far</span> <span m="3684420">apart</span> <span m="3684750">from</span>
  <span m="3684900">each</span> <span m="3685080">other.</span> <span m="3686390">So</span>
  <span m="3687000">we</span> <span m="3687090">could</span> <span m="3687210">choose</span>
  <span m="3687420">the</span> <span m="3687540">variance,</span> <span m="3687810">but</span>
  <span m="3687920">we</span> <span m="3687990">could</span> <span m="3688150">choose</span>
  <span m="3688290">something</span> <span m="3688620">else.</span> <span m="3688800">If</span>
  <span m="3688920">the</span> <span m="3689010">variance</span> <span m="3689280">does</span>
  <span m="3689410">not</span> <span m="3689580">help,</span> <span m="3689880">why</span>
  <span m="3690060">choose</span> <span m="3690330">it?</span> <span m="3690990">Turns</span>
  <span m="3691230">out</span> <span m="3691320">the</span> <span m="3691410">variance</span>
  <span m="3691740">helps.</span></p><p><span m="3692520">So</span> <span m="3692670">this</span>
  <span m="3692910">is</span> <span m="3693060">indeed</span> <span m="3693840">a</span>
  <span m="3693960">non-convex</span> <span m="3694680">problem.</span> <span m="3695555">I'm</span>
  <span m="3695950">maximizing,</span> <span m="3697290">so</span> <span m="3697410">it's</span>
  <span m="3697560">actually</span> <span m="3697890">the</span> <span m="3698010">same.</span>
  <span m="3698340">I</span> <span m="3698400">can</span> <span m="3698580">make</span>
  <span m="3700640">this</span> <span m="3700920">constraint</span> <span m="3701310">convex</span>
  <span m="3701850">because</span> <span m="3702450">I'm</span> <span m="3702510">maximizing</span>
  <span m="3703080">a</span> <span m="3703230">convex</span> <span m="3703620">function,</span>
  <span m="3703920">so</span> <span m="3704010">it's</span> <span m="3704130">clear</span>
  <span m="3704430">that</span> <span m="3704940">the</span> <span m="3705030">maximum</span>
  <span m="3705480">is</span> <span m="3705600">going</span> <span m="3705720">to</span>
  <span m="3705780">be</span> <span m="3705870">attained</span> <span m="3706170">at</span>
  <span m="3706260">the</span> <span m="3706350">boundary.</span> <span m="3707220">So</span>
  <span m="3707430">I</span> <span m="3707520">can</span> <span m="3707700">actually</span>
  <span m="3708120">just</span> <span m="3708420">fill</span> <span m="3708690">this</span>
  <span m="3708900">ball</span> <span m="3709170">into</span> <span m="3709410">some</span>
  <span m="3709620">convex</span> <span m="3710040">ball.</span></p><p><span m="3711540">However,</span>
  <span m="3712110">I'm</span> <span m="3712230">still</span> <span m="3712470">maximizing,</span>
  <span m="3713160">so</span> <span m="3713280">this</span> <span m="3713430">is</span>
  <span m="3713520">a</span> <span m="3713610">non-convex</span> <span m="3714150">problem.</span>
  <span m="3715170">And</span> <span m="3715290">this</span> <span m="3715470">turns</span>
  <span m="3715740">out</span> <span m="3715890">to</span> <span m="3715980">be</span>
  <span m="3716070">the</span> <span m="3716190">fanciest</span> <span m="3716760">non-convex</span>
  <span m="3717240">problem</span> <span m="3717550">we</span> <span m="3717600">know</span>
  <span m="3717700">how</span> <span m="3717820">to</span> <span m="3717910">solve.</span>
  <span m="3719200">And</span> <span m="3719300">the</span> <span m="3719400">reason</span>
  <span m="3719670">why</span> <span m="3719850">we</span> <span m="3719970">know</span>
  <span m="3720120">how</span> <span m="3720210">to</span> <span m="3720300">solve</span>
  <span m="3720600">it</span> <span m="3720750">is</span> <span m="3720870">not</span>
  <span m="3721050">because</span> <span m="3721380">of</span> <span m="3721500">optimization</span>
  <span m="3722550">or</span> <span m="3722670">using</span> <span m="3723060">gradient-type</span>
  <span m="3723900">things</span> <span m="3724410">or</span> <span m="3724530">anything</span>
  <span m="3725240">of</span> <span m="3725430">the</span> <span m="3725550">algorithms</span>
  <span m="3726030">that</span> <span m="3726180">I</span> <span m="3726270">mentioned</span>
  <span m="3726690">during</span> <span m="3728610">the</span> <span m="3728760">maximum</span>
  <span m="3729090">likelihood.</span> <span m="3729350">It's</span> <span m="3729570">because</span>
  <span m="3730020">of</span> <span m="3730180">linear</span> <span m="3730440">algebra.</span>
  <span m="3731000">Linear</span> <span m="3731190">algebra</span> <span m="3731610">guarantees</span>
  <span m="3732120">that</span> <span m="3732240">we</span> <span m="3732330">know</span>
  <span m="3732480">how</span> <span m="3732600">to</span> <span m="3732690">solve</span>
  <span m="3732960">this.</span></p><p><span m="3733980">And</span> <span m="3734100">to</span>
  <span m="3734220">understand</span> <span m="3734730">this,</span> <span m="3736300">we</span>
  <span m="3736350">need</span> <span m="3736500">to</span> <span m="3737040">go</span>
  <span m="3737310">a</span> <span m="3737340">little</span> <span m="3737640">deeper
  in</span> <span m="3738130">linear</span> <span m="3738390">algebra,</span> <span
  m="3738810">and</span> <span m="3738900">we</span> <span m="3738960">need</span>
  <span m="3739110">to</span> <span m="3739230">understand</span> <span m="3741480">the</span>
  <span m="3741780">concept</span> <span m="3742360">of</span> <span m="3743160">diagonalization</span>
  <span m="3744030">of</span> <span m="3744120">a</span> <span m="3744180">matrix.</span>
  <span m="3744590">So</span> <span m="3744810">who</span> <span m="3745020">has</span>
  <span m="3745350">ever</span> <span m="3745620">seen</span> <span m="3746550">the</span>
  <span m="3746670">concept</span> <span m="3747060">of</span> <span m="3747180">an</span>
  <span m="3747270">eigenvalue?</span> <span m="3749850">Oh,</span> <span m="3750010">that's</span>
  <span m="3750160">beautiful.</span> <span m="3750790">And</span> <span m="3750940">if</span>
  <span m="3751030">you're</span> <span m="3751120">not</span> <span m="3751270">raising</span>
  <span m="3751540">your</span> <span m="3751630">hand,</span> <span m="3751880">you're</span>
  <span m="3751930">just</span> <span m="3752110">playing</span> <span m="3752350">&quot;Candy</span>
  <span m="3752590">Crush,&quot;</span> <span m="3752860">right?</span> <span m="3753505">All
  right,</span> <span m="3753970">so,</span> <span m="3755580">OK.</span></p><p><span
  m="3764930">This</span> <span m="3765110">is</span> <span m="3765230">great.</span>
  <span m="3766640">Everybody's</span> <span m="3767000">seen</span> <span m="3767300">it.</span>
  <span m="3768160">For</span> <span m="3768330">my</span> <span m="3768830">live</span>
  <span m="3769190">audience</span> <span m="3769610">of</span> <span m="3769730">millions,</span>
  <span m="3770550">maybe</span> <span m="3770720">you</span> <span m="3770870">have</span>
  <span m="3771020">not,</span> <span m="3771230">so</span> <span m="3771380">I</span>
  <span m="3771440">will</span> <span m="3771590">still</span> <span m="3771830">go</span>
  <span m="3772010">through</span> <span m="3772250">it.</span> <span m="3773600">All</span>
  <span m="3773660">right,</span> <span m="3774000">so</span> <span m="3777580">one</span>
  <span m="3777710">of</span> <span m="3777820">the</span> <span m="3777970">basic</span>
  <span m="3778420">facts--</span> <span m="3778840">and</span> <span m="3778930">I</span>
  <span m="3778990">remember</span> <span m="3779290">when</span> <span m="3779440">I</span>
  <span m="3779530">learned</span> <span m="3779800">this</span> <span m="3780160">in--</span>
  <span m="3782490">I</span> <span m="3782560">mean,</span> <span m="3782980">when</span>
  <span m="3783160">I</span> <span m="3783220">was</span> <span m="3783400">an</span>
  <span m="3783490">undergrad,</span> <span m="3783970">I</span> <span m="3784090">learned</span>
  <span m="3784330">about</span> <span m="3784600">the</span> <span m="3784720">spectral</span>
  <span m="3785110">decomposition</span> <span m="3785860">and</span> <span m="3786010">this</span>
  <span m="3786190">diagonalization</span> <span m="3786880">of</span> <span m="3786970">matrices.</span>
  <span m="3787450">And</span> <span m="3787540">for</span> <span m="3787680">me,</span>
  <span m="3787750">it</span> <span m="3787810">was</span> <span m="3787960">just</span>
  <span m="3788170">a</span> <span m="3788200">structural</span> <span m="3788680">property</span>
  <span m="3789070">of</span> <span m="3789190">matrices,</span> <span m="3789670">but</span>
  <span m="3789790">it</span> <span m="3789850">turns</span> <span m="3790090">out</span>
  <span m="3790240">that</span> <span m="3790360">it's</span> <span m="3790540">extremely</span>
  <span m="3790960">useful,</span> <span m="3791240">and</span> <span m="3791520">it's</span>
  <span m="3791560">useful</span> <span m="3791920">for</span> <span m="3792070">algorithmic</span>
  <span m="3792550">purposes.</span></p><p><span m="3793460">And</span> <span m="3793540">so</span>
  <span m="3793690">what</span> <span m="3793830">this</span> <span m="3793990">theorem</span>
  <span m="3794320">tells</span> <span m="3794620">you is</span> <span m="3794800">that</span>
  <span m="3794920">if</span> <span m="3795040">you</span> <span m="3795130">take</span>
  <span m="3795880">a</span> <span m="3795940">symmetric</span> <span m="3796480">matrix--</span>
  <span m="3802860">well,</span> <span m="3803080">with</span> <span m="3803260">real</span>
  <span m="3803530">entries,</span> <span m="3803940">but</span> <span m="3804120">that</span>
  <span m="3804340">really</span> <span m="3805420">does</span> <span m="3805660">not</span>
  <span m="3806260">matter</span> <span m="3806560">so</span> <span m="3806740">much.</span>
  <span m="3808220">And</span> <span m="3808480">here,</span> <span m="3808900">I'm</span>
  <span m="3809080">going</span> <span m="3809200">to</span> <span m="3809290">actually--</span>
  <span m="3810730">so</span> <span m="3810910">I</span> <span m="3811000">take</span>
  <span m="3811180">a</span> <span m="3811240">symmetric</span> <span m="3811660">matrix,</span>
  <span m="3812050">and</span> <span m="3812140">actually</span> <span m="3812530">S
  and</span> <span m="3812890">sigma</span> <span m="3813200">are</span> <span m="3813400">two</span>
  <span m="3813610">such</span> <span m="3813850">symmetric</span> <span m="3814300">matrices,</span>
  <span m="3814780">right?</span> <span m="3816190">Then</span> <span m="3816640">there</span>
  <span m="3816850">exists</span> <span m="3819070">P</span> <span m="3819880">and</span>
  <span m="3820090">D,</span> <span m="3821880">which</span> <span m="3822150">are</span>
  <span m="3822450">both--</span> <span m="3824500">so let's</span> <span m="3824690">say</span>
  <span m="3825020">d by</span> <span m="3825410">d.</span> <span m="3827000">Which</span>
  <span m="3827180">are</span> <span m="3827300">both</span> <span m="3827710">d by
  d</span> <span m="3831280">such</span> <span m="3831580">that</span> <span m="3833760">P</span>
  <span m="3834990">is</span> <span m="3835290">orthogonal.</span> <span m="3838960">That</span>
  <span m="3839110">means</span> <span m="3839410">that</span> <span m="3839800">P</span>
  <span m="3840040">transpose</span> <span m="3840580">P is</span> <span m="3841030">equal</span>
  <span m="3841270">to</span> <span m="3841450">PP</span> <span m="3842020">transpose</span>
  <span m="3842420">is</span> <span m="3842820">equal</span> <span m="3843100">to</span>
  <span m="3843280">the</span> <span m="3843400">identity.</span> <span m="3846360">And</span>
  <span m="3846760">D is</span> <span m="3847140">diagonal.</span> <span m="3851840">And</span>
  <span m="3852530">sigma,</span> <span m="3853280">let's</span> <span m="3853430">say,</span>
  <span m="3854310">is</span> <span m="3854480">equal</span> <span m="3854870">to</span>
  <span m="3855080">PDP</span> <span m="3857420">transpose,</span> <span m="3859790">OK?</span></p><p><span
  m="3860130">So</span> <span m="3860550">it's a</span> <span m="3860840">diagonalization</span>
  <span m="3861610">because it's</span> <span m="3862080">finding</span> <span m="3862620">a</span>
  <span m="3862890">nice</span> <span m="3863250">transformation.</span> <span m="3863970">P</span>
  <span m="3864240">has</span> <span m="3864420">some</span> <span m="3864570">nice</span>
  <span m="3864810">properties.</span> <span m="3865260">It's</span> <span m="3865380">really</span>
  <span m="3865620">just</span> <span m="3865840">the</span> <span m="3865920">change</span>
  <span m="3866220">of</span> <span m="3866280">coordinates</span> <span m="3867540">in</span>
  <span m="3867690">which</span> <span m="3868050">your</span> <span m="3868620">matrix</span>
  <span m="3869100">is</span> <span m="3869220">diagonal,</span> <span m="3870330">right?</span>
  <span m="3871330">And</span> <span m="3871350">the</span> <span m="3871470">way</span>
  <span m="3871650">you</span> <span m="3871740">want</span> <span m="3871920">to</span>
  <span m="3871980">see</span> <span m="3872220">this--</span> <span m="3872460">and</span>
  <span m="3872550">I</span> <span m="3872610">think</span> <span m="3873720">it</span>
  <span m="3873840">sort</span> <span m="3873960">of</span> <span m="3874080">helps</span>
  <span m="3874380">to</span> <span m="3874530">think</span> <span m="3874770">about</span>
  <span m="3875010">this</span> <span m="3875190">problem</span> <span m="3875610">as</span>
  <span m="3875760">being--</span> <span m="3876720">sigma</span> <span m="3877170">being</span>
  <span m="3877400">a</span> <span m="3877510">covariance</span> <span m="3877860">matrix.</span>
  <span m="3878290">What</span> <span m="3878460">does</span> <span m="3878550">a</span>
  <span m="3878610">covariance</span> <span m="3879000">matrix</span> <span m="3879290">tell</span>
  <span m="3879580">you?</span></p><p><span m="3879900">Think</span> <span m="3880170">of</span>
  <span m="3880440">a</span> <span m="3880560">multivariate</span> <span m="3881130">Gaussian.</span>
  <span m="3881490">Can</span> <span m="3881580">everybody</span> <span m="3881940">visualize</span>
  <span m="3882510">a</span> <span m="3882600">three-dimensional</span> <span m="3883290">Gaussian</span>
  <span m="3883660">density?</span> <span m="3885150">Right,</span> <span m="3885330">so</span>
  <span m="3885440">it's</span> <span m="3885560">going</span> <span m="3885680">to</span>
  <span m="3885770">be</span> <span m="3885920">some</span> <span m="3886100">sort</span>
  <span m="3886250">of</span> <span m="3886520">a</span> <span m="3887330">bell-shaped</span>
  <span m="3887810">curve,</span> <span m="3888200">but</span> <span m="3888600">it</span>
  <span m="3888770">might</span> <span m="3889040">be</span> <span m="3889280">more</span>
  <span m="3889580">elongated</span> <span m="3890120">in</span> <span m="3890240">one</span>
  <span m="3890390">direction</span> <span m="3890780">than</span> <span m="3890900">another.</span>
  <span m="3891870">And</span> <span m="3891990">then</span> <span m="3892160">going</span>
  <span m="3892310">to</span> <span m="3892370">chop</span> <span m="3892880">it</span>
  <span m="3893030">like</span> <span m="3893240">that,</span> <span m="3893510">all
  right?</span> <span m="3894310">So</span> <span m="3894470">I'm</span> <span m="3894530">going</span>
  <span m="3894650">to</span> <span m="3894710">chop</span> <span m="3895040">it</span>
  <span m="3895160">off.</span> <span m="3896120">And</span> <span m="3896900">I'm</span>
  <span m="3896990">going</span> <span m="3897140">to</span> <span m="3897200">look</span>
  <span m="3897380">at</span> <span m="3898670">how</span> <span m="3899000">it</span>
  <span m="3899090">bleeds,</span> <span m="3899480">all</span> <span m="3899775">right?</span>
  <span m="3900070">So</span> <span m="3900410">I'm</span> <span m="3900560">just</span>
  <span m="3900740">going</span> <span m="3900890">to</span> <span m="3900950">look</span>
  <span m="3901130">at</span> <span m="3901250">where</span> <span m="3901430">the</span>
  <span m="3901550">blood</span> <span m="3901800">is.</span></p><p><span m="3902330">And</span>
  <span m="3902420">what it's</span> <span m="3902600">going</span> <span m="3902720">to</span>
  <span m="3902780">look</span> <span m="3902960">at--</span> <span m="3903620">it's</span>
  <span m="3903740">going</span> <span m="3903860">to</span> <span m="3903920">look</span>
  <span m="3904130">like</span> <span m="3906500">some</span> <span m="3906680">sort</span>
  <span m="3906830">of</span> <span m="3907270">ellipsoid,</span> <span m="3907760">right?</span>
  <span m="3908720">In</span> <span m="3908870">high</span> <span m="3908990">dimension,</span>
  <span m="3909410">it's</span> <span m="3909500">just</span> <span m="3909680">going</span>
  <span m="3909800">to</span> <span m="3909890">be</span> <span m="3911255">an</span>
  <span m="3911720">olive.</span> <span m="3912190">And that</span> <span m="3912440">is</span>
  <span m="3912760">just</span> <span m="3912890">going</span> <span m="3913010">to</span>
  <span m="3913070">be</span> <span m="3913160">bigger</span> <span m="3913370">and</span>
  <span m="3913490">bigger.</span> <span m="3913610">And</span> <span m="3914090">then</span>
  <span m="3914180">I</span> <span m="3914360">chop</span> <span m="3914690">it</span>
  <span m="3914780">off</span> <span m="3915020">a</span> <span m="3915050">little</span>
  <span m="3915420">lower,</span> <span m="3916460">and</span> <span m="3916580">I</span>
  <span m="3916640">get</span> <span m="3916820">something</span> <span m="3917180">a</span>
  <span m="3917210">little</span> <span m="3917690">bigger</span> <span m="3918020">like</span>
  <span m="3918200">this.</span> <span m="3920150">And</span> <span m="3920210">so</span>
  <span m="3920330">it</span> <span m="3920390">turns</span> <span m="3920690">out</span>
  <span m="3920840">that</span> <span m="3921020">sigma</span> <span m="3921740">is</span>
  <span m="3921980">capturing</span> <span m="3922550">exactly</span> <span m="3923060">this,</span>
  <span m="3923330">right?</span> <span m="3923570">The</span> <span m="3923720">matrix</span>
  <span m="3924170">sigma--</span> <span m="3924720">so</span> <span m="3925250">the</span>
  <span m="3925790">center</span> <span m="3926240">of</span> <span m="3926360">your</span>
  <span m="3926510">covariance</span> <span m="3926930">matrix</span> <span m="3927320">of</span>
  <span m="3927410">your</span> <span m="3927530">Gaussian</span> <span m="3927920">is</span>
  <span m="3928010">going</span> <span m="3928160">to</span> <span m="3928250">be</span>
  <span m="3928370">this</span> <span m="3928550">thing.</span> <span m="3929240">And</span>
  <span m="3929330">sigma</span> <span m="3929690">is</span> <span m="3929810">going</span>
  <span m="3929960">to</span> <span m="3930020">tell</span> <span m="3930230">you</span>
  <span m="3930470">which</span> <span m="3930680">direction</span> <span m="3931160">it's</span>
  <span m="3931370">elongated.</span></p><p><span m="3933690">And</span> <span m="3933710">so</span>
  <span m="3933800">in</span> <span m="3933890">particular,</span> <span m="3934810">if
  you look,</span> <span m="3935270">if</span> <span m="3935420">you</span> <span
  m="3935540">knew</span> <span m="3935720">an</span> <span m="3935840">ellipse,</span>
  <span m="3936140">you</span> <span m="3936260">know</span> <span m="3936410">there's</span>
  <span m="3936600">something</span> <span m="3936980">called</span> <span m="3937180">principal</span>
  <span m="3937640">axis,</span> <span m="3937940">right?</span> <span m="3938160">So</span>
  <span m="3938270">you</span> <span m="3938420">could</span> <span m="3938540">actually</span>
  <span m="3938920">define</span> <span m="3939320">something</span> <span m="3939710">that</span>
  <span m="3939860">looks</span> <span m="3940070">like</span> <span m="3940250">this,</span>
  <span m="3941340">which</span> <span m="3941420">is</span> <span m="3941540">this</span>
  <span m="3941810">axis,</span> <span m="3942390">the</span> <span m="3942440">one</span>
  <span m="3942740">along</span> <span m="3943010">which</span> <span m="3943190">it's</span>
  <span m="3943280">the</span> <span m="3943370">most</span> <span m="3943580">elongated.</span>
  <span m="3944390">Then</span> <span m="3944540">the</span> <span m="3944630">axis</span>
  <span m="3944960">along</span> <span m="3945230">which</span> <span m="3946160">is</span>
  <span m="3946270">orthogonal</span> <span m="3946720">to</span> <span m="3946910">it,</span>
  <span m="3947345">along</span> <span m="3947600">which</span> <span m="3947840">it's</span>
  <span m="3948260">slightly</span> <span m="3948650">less</span> <span m="3948860">elongated,</span>
  <span m="3949370">and</span> <span m="3949550">you</span> <span m="3949670">go</span>
  <span m="3950030">again</span> <span m="3950330">and</span> <span m="3950450">again</span>
  <span m="3950720">along</span> <span m="3950990">the</span> <span m="3951800">orthogonal</span>
  <span m="3952280">ones.</span></p><p><span m="3952880">It</span> <span m="3953300">turns</span>
  <span m="3953570">out</span> <span m="3953720">that</span> <span m="3953900">those</span>
  <span m="3954200">things</span> <span m="3954500">here</span> <span m="3956500">is</span>
  <span m="3956750">the</span> <span m="3956870">new</span> <span m="3957080">coordinate</span>
  <span m="3957560">system</span> <span m="3958010">in</span> <span m="3958160">which</span>
  <span m="3958400">this</span> <span m="3958580">transformation,</span> <span m="3959330">P</span>
  <span m="3959620">and P</span> <span m="3959880">transpose,</span> <span m="3960350">is</span>
  <span m="3960530">putting</span> <span m="3960800">you</span> <span m="3960950">into.</span>
  <span m="3963190">And</span> <span m="3963525">D</span> <span m="3964130">has</span>
  <span m="3964460">entries</span> <span m="3964940">on</span> <span m="3965030">the</span>
  <span m="3965150">diagonal</span> <span m="3966390">which</span> <span m="3966470">are</span>
  <span m="3966590">exactly</span> <span m="3967160">this</span> <span m="3967400">length</span>
  <span m="3967850">and</span> <span m="3968000">this</span> <span m="3968210">length,</span>
  <span m="3969771">right?</span></p><p><span m="3970210">So</span> <span m="3970310">that's</span>
  <span m="3970490">just</span> <span m="3970670">what</span> <span m="3970820">it's</span>
  <span m="3970970">doing.</span> <span m="3971270">It's</span> <span m="3971360">just</span>
  <span m="3971540">telling</span> <span m="3971900">you,</span> <span m="3972020">well,</span>
  <span m="3972710">if</span> <span m="3972830">you</span> <span m="3972920">think</span>
  <span m="3973190">of</span> <span m="3973310">having</span> <span m="3973640">this</span>
  <span m="3974030">Gaussian</span> <span m="3974780">or</span> <span m="3974930">this</span>
  <span m="3975920">high-dimensional</span> <span m="3976760">ellipsoid,</span> <span
  m="3978390">it's</span> <span m="3978690">elongated</span> <span m="3979190">along</span>
  <span m="3979420">certain</span> <span m="3979690">directions.</span> <span m="3979990">And</span>
  <span m="3980290">these</span> <span m="3980510">directions</span> <span m="3981130">are</span>
  <span m="3981250">actually</span> <span m="3981640">maybe</span> <span m="3982000">not</span>
  <span m="3982360">well</span> <span m="3982690">aligned</span> <span m="3983080">with</span>
  <span m="3983260">your</span> <span m="3983380">original</span> <span m="3983770">coordinate</span>
  <span m="3984250">system,</span> <span m="3984740">which</span> <span m="3984850">might</span>
  <span m="3985030">just</span> <span m="3985270">be</span> <span m="3985510">the</span>
  <span m="3985630">usual</span> <span m="3986020">one,</span> <span m="3986290">right--</span>
  <span m="3987430">north,</span> <span m="3987820">south,</span> <span m="3988240">and</span>
  <span m="3988480">east,</span> <span m="3988720">west.</span> <span m="3989740">Maybe</span>
  <span m="3989980">I</span> <span m="3990010">need</span> <span m="3990160">to</span>
  <span m="3990310">turn</span> <span m="3990640">it.</span> <span m="3990800">And</span>
  <span m="3990910">that's</span> <span m="3991090">exactly</span> <span m="3991570">what</span>
  <span m="3991710">this</span> <span m="3991800">orthogonal</span> <span m="3992250">transformation</span>
  <span m="3992950">is</span> <span m="3993040">doing</span> <span m="3993310">for</span>
  <span m="3993520">you,</span> <span m="3994504">all right?</span></p><p><span m="3996820">So,</span>
  <span m="3998080">in</span> <span m="3998140">a way,</span> <span m="3998400">this</span>
  <span m="3998590">is</span> <span m="3998710">actually</span> <span m="3999010">telling</span>
  <span m="3999280">you</span> <span m="3999430">even</span> <span m="3999610">more.</span>
  <span m="3999820">It's</span> <span m="3999940">telling</span> <span m="4000120">you</span>
  <span m="4000180">that</span> <span m="4000390">any</span> <span m="4000600">matrix</span>
  <span m="4000990">that's</span> <span m="4001180">symmetric,</span> <span m="4001710">you</span>
  <span m="4002050">can</span> <span m="4002220">actually</span> <span m="4002640">turn</span>
  <span m="4002940">it</span> <span m="4003060">somewhere.</span> <span m="4005190">And
  that'll</span> <span m="4005490">start</span> <span m="4005760">to</span> <span
  m="4005940">dilate</span> <span m="4006480">things</span> <span m="4006780">in</span>
  <span m="4006930">the</span> <span m="4007020">directions</span> <span m="4007530">that</span>
  <span m="4007650">you</span> <span m="4007800">have,</span> <span m="4008160">and</span>
  <span m="4008280">then</span> <span m="4008490">turn</span> <span m="4008700">it</span>
  <span m="4008790">back</span> <span m="4009060">to</span> <span m="4009180">what</span>
  <span m="4009330">you</span> <span m="4009480">originally</span> <span m="4010020">had.</span>
  <span m="4010800">And</span> <span m="4010980">that's</span> <span m="4011220">actually</span>
  <span m="4011940">exactly</span> <span m="4012480">the</span> <span m="4012630">effect</span>
  <span m="4013110">of</span> <span m="4013590">applying</span> <span m="4014400">a</span>
  <span m="4014700">symmetric</span> <span m="4015180">matrix</span> <span m="4015510">through
  a</span> <span m="4015660">vector,</span> <span m="4017000">right?</span></p><p><span
  m="4017180">And</span> <span m="4017380">it's</span> <span m="4018170">pretty</span>
  <span m="4018440">impressive.</span> <span m="4018920">It</span> <span m="4019030">says</span>
  <span m="4019700">if</span> <span m="4019850">I</span> <span m="4019970">take</span>
  <span m="4020240">sigma</span> <span m="4020630">times</span> <span m="4020960">v.</span>
  <span m="4023030">Any</span> <span m="4023330">sigma</span> <span m="4024000">that's</span>
  <span m="4024650">of</span> <span m="4024800">this</span> <span m="4025040">form,</span>
  <span m="4025670">what</span> <span m="4025790">I'm</span> <span m="4025910">doing</span>
  <span m="4026240">is--</span> <span m="4026480">that's</span> <span m="4026780">symmetric.</span>
  <span m="4027560">What</span> <span m="4027710">I'm</span> <span m="4027800">really</span>
  <span m="4028040">doing</span> <span m="4028310">to</span> <span m="4028595">v</span>
  <span m="4028880">is</span> <span m="4029210">I'm</span> <span m="4029360">changing</span>
  <span m="4029780">its</span> <span m="4029960">coordinate</span> <span m="4030350">system,</span>
  <span m="4030810">so</span> <span m="4030910">I'm</span> <span m="4030920">rotating</span>
  <span m="4031370">it.</span> <span m="4032150">Then</span> <span m="4032300">I'm</span>
  <span m="4032450">changing--</span> <span m="4033050">I'm</span> <span m="4033440">multiplying</span>
  <span m="4034130">its</span> <span m="4034340">coordinates,</span> <span m="4034970">and</span>
  <span m="4035090">then</span> <span m="4035240">I'm</span> <span m="4035420">rotating</span>
  <span m="4035840">it</span> <span m="4036020">back.</span> <span m="4036980">That's</span>
  <span m="4037160">all</span> <span m="4037280">it's</span> <span m="4037430">doing,
  and</span> <span m="4037910">that's</span> <span m="4038330">what</span> <span m="4038630">all</span>
  <span m="4038840">symmetric</span> <span m="4039260">matrices</span> <span m="4039740">do,</span>
  <span m="4041190">which</span> <span m="4041550">means</span> <span m="4041790">that</span>
  <span m="4042280">this</span> <span m="4042510">is</span> <span m="4042630">doing</span>
  <span m="4042900">a</span> <span m="4042960">lot.</span></p><p><span m="4044070">All</span>
  <span m="4044130">right,</span> <span m="4044300">so</span> <span m="4046440">OK.</span>
  <span m="4047130">So,</span> <span m="4048870">what</span> <span m="4049020">do</span>
  <span m="4049110">I</span> <span m="4049200">know?</span> <span m="4049500">So</span>
  <span m="4049740">I'm</span> <span m="4049830">not</span> <span m="4049950">going</span>
  <span m="4050100">to</span> <span m="4050160">prove</span> <span m="4050370">that</span>
  <span m="4050490">this</span> <span m="4050670">is</span> <span m="4050820">the</span>
  <span m="4050940">so-called</span> <span m="4051270">spectral</span> <span m="4051660">theorem.</span>
  <span m="4059270">And</span> <span m="4059780">the</span> <span m="4059930">diagonal</span>
  <span m="4060410">entries</span> <span m="4060800">of</span> <span m="4061190">D</span>
  <span m="4063470">is</span> <span m="4063650">of</span> <span m="4063770">the</span>
  <span m="4063890">form,</span> <span m="4064370">lambda</span> <span m="4064670">1,</span>
  <span m="4065850">lambda</span> <span m="4066110">2,</span> <span m="4067350">lambda</span>
  <span m="4067730">d,</span> <span m="4068630">0,</span> <span m="4069080">0.</span>
  <span m="4069980">And</span> <span m="4070160">the</span> <span m="4070280">lambda</span>
  <span m="4070610">j's</span> <span m="4072290">are</span> <span m="4072440">called</span>
  <span m="4076230">eigenvalues</span> <span m="4079110">of</span> <span m="4079860">D.</span></p><p><span
  m="4081800">Now</span> <span m="4082700">in</span> <span m="4082880">general,</span>
  <span m="4083270">those</span> <span m="4083420">numbers</span> <span m="4083870">can</span>
  <span m="4084110">be</span> <span m="4084200">positive,</span> <span m="4084780">negative,</span>
  <span m="4085170">or</span> <span m="4085190">equal</span> <span m="4085400">to</span>
  <span m="4085520">0.</span> <span m="4086660">But</span> <span m="4086840">here,</span>
  <span m="4087290">I</span> <span m="4087470">know</span> <span m="4087740">that</span>
  <span m="4087950">sigma</span> <span m="4088360">and</span> <span m="4088510">S</span>
  <span m="4090830">are--</span> <span m="4092000">well,</span> <span m="4092270">they're</span>
  <span m="4092420">symmetric</span> <span m="4092930">for</span> <span m="4093080">sure,</span>
  <span m="4095290">but</span> <span m="4095410">they are</span> <span m="4095620">positive</span>
  <span m="4096189">semidefinite.</span> <span m="4103939">What</span> <span m="4104090">does</span>
  <span m="4104210">it</span> <span m="4104359">mean?</span> <span m="4105840">It</span>
  <span m="4105890">means</span> <span m="4106250">that</span> <span m="4107240">when</span>
  <span m="4107390">I</span> <span m="4107479">take</span> <span m="4108050">u</span>
  <span m="4108290">transpose</span> <span m="4108920">sigma</span> <span m="4109340">u</span>
  <span m="4109680">for</span> <span m="4109760">example,</span> <span m="4110930">this</span>
  <span m="4111140">number</span> <span m="4111529">is</span> <span m="4111710">always</span>
  <span m="4112069">non-negative.</span> <span m="4115910">Why</span> <span m="4116120">is</span>
  <span m="4116210">this</span> <span m="4116390">true?</span> <span m="4122770">What</span>
  <span m="4122950">is</span> <span m="4123040">this</span> <span m="4123220">number?</span></p><p><span
  m="4127670">It's</span> <span m="4128050">the</span> <span m="4128229">variance</span>
  <span m="4128830">of--</span> <span m="4129140">and</span> <span m="4129220">actually,</span>
  <span m="4129540">I</span> <span m="4129580">don't</span> <span m="4129700">even</span>
  <span m="4129850">need</span> <span m="4130029">to</span> <span m="4130149">finish</span>
  <span m="4130450">this</span> <span m="4130560">sentence.</span> <span m="4131229">As</span>
  <span m="4131350">soon</span> <span m="4131529">as</span> <span m="4131649">I</span>
  <span m="4131740">say</span> <span m="4131890">that</span> <span m="4132040">this</span>
  <span m="4132250">is</span> <span m="4132430">a</span> <span m="4132609">variance,</span>
  <span m="4133685">well,</span> <span m="4134080">it</span> <span m="4134140">has</span>
  <span m="4134350">to</span> <span m="4134439">be</span> <span m="4134590">non-negative.</span>
  <span m="4135040">We</span> <span m="4135160">know</span> <span m="4135279">that</span>
  <span m="4135410">a</span> <span m="4135490">variance</span> <span m="4135819">is</span>
  <span m="4135939">not</span> <span m="4136050">negative.</span> <span m="4137990">And</span>
  <span m="4138090">so,</span> <span m="4138970">that's</span> <span m="4139149">also</span>
  <span m="4139390">a</span> <span m="4139450">nice</span> <span m="4139660">way</span>
  <span m="4139810">you</span> <span m="4139930">can</span> <span m="4140140">use</span>
  <span m="4140439">that.</span> <span m="4140760">So it's</span> <span m="4140920">just</span>
  <span m="4141130">to</span> <span m="4141250">say,</span> <span m="4141500">well,</span>
  <span m="4141770">OK,</span> <span m="4141880">this</span> <span m="4142060">thing</span>
  <span m="4142240">is</span> <span m="4142479">positive</span> <span m="4142734">semidefinite</span>
  <span m="4143319">because</span> <span m="4143680">it's</span> <span m="4143800">a</span>
  <span m="4143859">covariance</span> <span m="4144220">matrix.</span> <span m="4144680">So</span>
  <span m="4144790">I</span> <span m="4144850">know</span> <span m="4145060">it's</span>
  <span m="4146080">a</span> <span m="4146140">variance,</span> <span m="4146689">OK?</span>
  <span m="4146920">So</span> <span m="4147540">I</span> <span m="4147700">get</span>
  <span m="4147939">this.</span></p><p><span m="4148779">Now,</span> <span m="4148899">if</span>
  <span m="4149080">I</span> <span m="4149140">had</span> <span m="4149380">some</span>
  <span m="4149590">negative</span> <span m="4149950">numbers--</span> <span m="4150560">so</span>
  <span m="4151060">the</span> <span m="4151149">effect</span> <span m="4151479">of</span>
  <span m="4151630">that</span> <span m="4151899">is</span> <span m="4151990">that</span>
  <span m="4152170">when</span> <span m="4152319">I</span> <span m="4152410">draw</span>
  <span m="4152620">this</span> <span m="4152770">picture,</span> <span m="4155350">those</span>
  <span m="4155680">axes</span> <span m="4155995">are</span> <span m="4156310">always</span>
  <span m="4156700">positive,</span> <span m="4158029">which</span> <span m="4158109">is</span>
  <span m="4158229">kind</span> <span m="4158380">of</span> <span m="4158470">a</span>
  <span m="4158529">weird</span> <span m="4158800">thing</span> <span m="4159040">to</span>
  <span m="4159160">say.</span> <span m="4159950">But</span> <span m="4160180">what</span>
  <span m="4160330">it</span> <span m="4160420">means</span> <span m="4160720">is</span>
  <span m="4160840">that</span> <span m="4161560">when</span> <span m="4161680">I</span>
  <span m="4161740">take</span> <span m="4161950">a</span> <span m="4162010">vector,</span>
  <span m="4162310">v,</span> <span m="4162790">I</span> <span m="4162910">rotate</span>
  <span m="4163390">it,</span> <span m="4163840">and</span> <span m="4163960">then</span>
  <span m="4164200">I</span> <span m="4164830">stretch</span> <span m="4165100">it</span>
  <span m="4166300">in</span> <span m="4166600">the</span> <span m="4166720">directions</span>
  <span m="4167290">of</span> <span m="4167410">the</span> <span m="4167540">coordinate,</span>
  <span m="4168250">I</span> <span m="4168310">cannot</span> <span m="4168910">flip</span>
  <span m="4169390">it.</span> <span m="4170260">I</span> <span m="4170319">can</span>
  <span m="4170439">only</span> <span m="4170680">stretch</span> <span m="4171250">or</span>
  <span m="4171430">shrink,</span> <span m="4172120">but</span> <span m="4172210">I</span>
  <span m="4172270">cannot</span> <span m="4172569">flip</span> <span m="4172920">its</span>
  <span m="4173050">sign,</span> <span m="4174290">all</span> <span m="4174390">right?</span>
  <span m="4174760">But</span> <span m="4175060">in</span> <span m="4175180">general,</span>
  <span m="4175569">for</span> <span m="4175810">any</span> <span m="4176380">symmetric</span>
  <span m="4176800">matrices,</span> <span m="4177370">I</span> <span m="4177460">could</span>
  <span m="4177640">do</span> <span m="4177790">this.</span></p><p><span m="4178840">But</span>
  <span m="4178960">when</span> <span m="4179109">it's</span> <span m="4179260">positive</span>
  <span m="4179649">symmetric</span> <span m="4180100">definite,</span> <span m="4180910">actually</span>
  <span m="4181359">what</span> <span m="4181510">turns</span> <span m="4181810">out</span>
  <span m="4182020">is</span> <span m="4182109">that</span> <span m="4182319">all</span>
  <span m="4182569">the lambda</span> <span m="4183020">j's</span> <span m="4186460">are</span>
  <span m="4186640">non-negative.</span> <span m="4188350">I</span> <span m="4188410">cannot</span>
  <span m="4188740">flip</span> <span m="4189069">it,</span> <span m="4191010">OK?</span>
  <span m="4191370">So</span> <span m="4191580">all</span> <span m="4191790">the</span>
  <span m="4191910">eigenvalues</span> <span m="4192569">are</span> <span m="4192660">non-negative.</span>
  <span m="4196590">That's</span> <span m="4196840">a</span> <span m="4196940">property</span>
  <span m="4197390">of</span> <span m="4197540">positive</span> <span m="4197970">semidef.</span>
  <span m="4198500">So</span> <span m="4198710">when</span> <span m="4198860">it's</span>
  <span m="4199000">symmetric,</span> <span m="4199460">you</span> <span m="4199580">have</span>
  <span m="4199730">the</span> <span m="4199820">eigenvalues.</span> <span m="4200510">They</span>
  <span m="4200630">can</span> <span m="4200780">be</span> <span m="4200900">any</span>
  <span m="4201050">number.</span> <span m="4201670">And</span> <span m="4201800">when</span>
  <span m="4201920">it's</span> <span m="4202040">positive</span> <span m="4202400">semidefinite,</span>
  <span m="4203350">in</span> <span m="4203450">particular</span> <span m="4203780">that's</span>
  <span m="4203960">the</span> <span m="4204050">case</span> <span m="4204290">of</span>
  <span m="4204410">the</span> <span m="4204500">covariance</span> <span m="4204860">matrix</span>
  <span m="4205220">and</span> <span m="4205340">the</span> <span m="4205430">empirical</span>
  <span m="4205790">covariance</span> <span m="4206120">matrix,</span> <span m="4206520">right?</span>
  <span m="4207110">Because</span> <span m="4207290">the</span> <span m="4207380">empirical</span>
  <span m="4207740">covariance</span> <span m="4208130">matrix</span> <span m="4208940">is</span>
  <span m="4209060">an</span> <span m="4209150">empirical</span> <span m="4209600">variance,</span>
  <span m="4210090">which</span> <span m="4210170">itself</span> <span m="4210620">is</span>
  <span m="4210710">non-negative.</span> <span m="4212150">And</span> <span m="4212270">so</span>
  <span m="4212840">I</span> <span m="4212960">get</span> <span m="4213620">that</span>
  <span m="4213890">the</span> <span m="4214070">eigenvalues</span> <span m="4214610">are</span>
  <span m="4214700">non-negative.</span></p><p><span m="4217900">All</span> <span
  m="4218020">right,</span> <span m="4218280">so</span> <span m="4221030">principal</span>
  <span m="4221390">component</span> <span m="4221780">analysis</span> <span m="4222380">is</span>
  <span m="4222470">saying,</span> <span m="4223030">OK,</span> <span m="4225400">I</span>
  <span m="4225520">want</span> <span m="4225730">to</span> <span m="4225880">find</span>
  <span m="4227750">the</span> <span m="4230690">direction,</span> <span m="4231740">u,</span>
  <span m="4232370">that</span> <span m="4232550">maximizes</span> <span m="4233450">u</span>
  <span m="4233660">transpose</span> <span m="4234190">Su,</span> <span m="4236088">all
  right?</span> <span m="4238830">I've</span> <span m="4238980">just</span> <span
  m="4239250">introduced</span> <span m="4239790">in</span> <span m="4239910">one</span>
  <span m="4240090">slide</span> <span m="4240420">something</span> <span m="4240720">about</span>
  <span m="4240960">eigenvalues.</span> <span m="4241690">So</span> <span m="4241770">hopefully,</span>
  <span m="4242610">they</span> <span m="4242730">should</span> <span m="4242940">help.</span>
  <span m="4244740">So</span> <span m="4245520">what</span> <span m="4245970">is</span>
  <span m="4246210">it</span> <span m="4246360">that</span> <span m="4246510">I'm</span>
  <span m="4246660">going</span> <span m="4246810">to</span> <span m="4246870">be</span>
  <span m="4246990">getting?</span> <span m="4247560">Well,</span> <span m="4248280">let's</span>
  <span m="4248460">just</span> <span m="4248610">see</span> <span m="4248820">what</span>
  <span m="4248940">happens.</span></p><p><span m="4251450">Oh,</span> <span m="4251790">I</span>
  <span m="4251880">forgot</span> <span m="4252180">to</span> <span m="4252330">mention
  that--</span> <span m="4252820">and</span> <span m="4252920">I</span> <span m="4253020">will</span>
  <span m="4253230">use</span> <span m="4253470">this. So the</span> <span m="4253770">lambda</span>
  <span m="4254190">j's are</span> <span m="4254550">called</span> <span m="4254790">eigenvectors.</span>
  <span m="4256020">And</span> <span m="4256140">then</span> <span m="4256290">the</span>
  <span m="4256410">matrix,</span> <span m="4256960">P,</span> <span m="4261850">has</span>
  <span m="4262540">columns</span> <span m="4263110">v1</span> <span m="4264950">to</span>
  <span m="4265120">vd,</span> <span m="4267270">OK?</span> <span m="4268690">The</span>
  <span m="4268810">fact</span> <span m="4269170">that</span> <span m="4270070">it's</span>
  <span m="4270220">orthogonal--</span> <span m="4270820">that</span> <span m="4270990">P</span>
  <span m="4271120">transpose</span> <span m="4272530">P</span> <span m="4272830">is</span>
  <span m="4273040">equal</span> <span m="4273370">to</span> <span m="4273670">the</span>
  <span m="4273820">identity--</span> <span m="4275470">means</span> <span m="4275710">that</span>
  <span m="4275920">those</span> <span m="4276190">guys</span> <span m="4277420">satisfied</span>
  <span m="4278140">that</span> <span m="4278835">vi</span> <span m="4280510">transpose</span>
  <span m="4280810">vj</span> <span m="4282400">is</span> <span m="4282580">equal</span>
  <span m="4282910">to</span> <span m="4283090">0</span> <span m="4283630">if</span>
  <span m="4284010">i</span> <span m="4284530">is</span> <span m="4285520">different</span>
  <span m="4285940">from</span> <span m="4286180">j.</span> <span m="4287485">And</span>
  <span m="4287920">vi</span> <span m="4288670">transpose</span> <span m="4289240">vi</span>
  <span m="4289810">is</span> <span m="4290020">actually</span> <span m="4290320">equal</span>
  <span m="4290560">to</span> <span m="4290770">1,</span> <span m="4291040">right,</span>
  <span m="4291280">because</span> <span m="4291610">the</span> <span m="4291760">entries</span>
  <span m="4292390">of</span> <span m="4292630">PP</span> <span m="4293230">transpose</span>
  <span m="4293920">are</span> <span m="4294040">exactly</span> <span m="4294520">going</span>
  <span m="4294670">to</span> <span m="4294730">be</span> <span m="4295330">of</span>
  <span m="4295480">the</span> <span m="4295570">form,</span> <span m="4296000">vi</span>
  <span m="4296500">transpose</span> <span m="4296980">vj,</span> <span m="4297650">OK?</span></p><p><span
  m="4298990">So</span> <span m="4299140">those</span> <span m="4299440">v's</span>
  <span m="4299710">are</span> <span m="4299830">called</span> <span m="4300100">eigenvectors.</span>
  <span m="4306000">And</span> <span m="4306660">v1</span> <span m="4307320">is</span>
  <span m="4307440">attached</span> <span m="4307860">to</span> <span m="4308010">lambda</span>
  <span m="4308400">1,</span> <span m="4308640">and</span> <span m="4308760">v2</span>
  <span m="4309150">is</span> <span m="4309270">attached</span> <span m="4309670">to</span>
  <span m="4309910">lambda</span> <span m="4310050">2,</span> <span m="4312020">OK?</span>
  <span m="4313180">So</span> <span m="4313300">let's</span> <span m="4313480">see</span>
  <span m="4313600">what's</span> <span m="4313780">happening</span> <span m="4314140">with</span>
  <span m="4314290">those</span> <span m="4314560">things.</span> <span m="4316280">What</span>
  <span m="4316330">happens</span> <span m="4316780">if</span> <span m="4316930">I</span>
  <span m="4317050">take</span> <span m="4317380">sigma--</span> <span m="4318220">so</span>
  <span m="4318340">if</span> <span m="4318460">you</span> <span m="4318580">know</span>
  <span m="4318760">eigenvalues,</span> <span m="4319360">you</span> <span m="4319420">know</span>
  <span m="4319570">exactly</span> <span m="4319990">what's</span> <span m="4320170">going</span>
  <span m="4320290">to</span> <span m="4320350">happen.</span> <span m="4321580">If</span>
  <span m="4321730">I</span> <span m="4321820">look</span> <span m="4322090">at,</span>
  <span m="4322240">say,</span> <span m="4322480">sigma</span> <span m="4324640">times</span>
  <span m="4325010">v1,</span> <span m="4325960">well,</span> <span m="4326200">what</span>
  <span m="4326380">is</span> <span m="4326470">sigma?</span> <span m="4326920">We</span>
  <span m="4327070">know</span> <span m="4327220">that</span> <span m="4327340">sigma</span>
  <span m="4328240">is</span> <span m="4329140">PDP</span> <span m="4332770">transpose</span>
  <span m="4333490">v1.</span></p><p><span m="4335440">What</span> <span m="4335590">is</span>
  <span m="4335710">P</span> <span m="4335910">transpose</span> <span m="4336460">times</span>
  <span m="4336780">v1?</span> <span m="4337420">Well,</span> <span m="4337680">P</span>
  <span m="4337890">transpose</span> <span m="4339250">has</span> <span m="4339460">rows</span>
  <span m="4339950">v1</span> <span m="4340380">transpose,</span> <span m="4341560">v2</span>
  <span m="4342040">transpose,</span> <span m="4344010">all the way</span> <span m="4344210">to</span>
  <span m="4344480">vd</span> <span m="4344990">transpose.</span> <span m="4346850">So</span>
  <span m="4346970">when</span> <span m="4347120">I</span> <span m="4347210">multiply</span>
  <span m="4347730">this</span> <span m="4347960">by</span> <span m="4348190">v1,</span>
  <span m="4350760">what</span> <span m="4350910">I'm</span> <span m="4351030">left</span>
  <span m="4351300">with</span> <span m="4351480">is</span> <span m="4352080">the</span>
  <span m="4352170">first</span> <span m="4352440">coordinate</span> <span m="4352820">is</span>
  <span m="4353070">going</span> <span m="4353190">to</span> <span m="4353280">be</span>
  <span m="4353340">equal</span> <span m="4353730">to</span> <span m="4353920">1</span>
  <span m="4356390">and</span> <span m="4356765">the</span> <span m="4357140">second</span>
  <span m="4357500">coordinate</span> <span m="4357770">is</span> <span m="4358010">going</span>
  <span m="4358160">to</span> <span m="4358220">be</span> <span m="4358310">equal</span>
  <span m="4358580">to</span> <span m="4360260">0,</span> <span m="4360740">right?</span>
  <span m="4360980">Because</span> <span m="4361310">they're</span> <span m="4361520">orthogonal</span>
  <span m="4361880">to</span> <span m="4362060">each</span> <span m="4362240">other--</span>
  <span m="4362910">0</span> <span m="4363680">all</span> <span m="4363830">the</span>
  <span m="4363950">way</span> <span m="4364100">to</span> <span m="4364250">the</span>
  <span m="4364430">end.</span> <span m="4365810">So</span> <span m="4365930">that's</span>
  <span m="4366290">when</span> <span m="4366470">I</span> <span m="4366530">do</span>
  <span m="4367030">P</span> <span m="4367370">transpose</span> <span m="4368000">v1.</span></p><p><span
  m="4368890">Now</span> <span m="4369030">I</span> <span m="4369170">multiply</span>
  <span m="4369650">by</span> <span m="4369860">D.</span> <span m="4374020">Well,</span>
  <span m="4374920">I'm</span> <span m="4375070">just</span> <span m="4375250">multiplying</span>
  <span m="4376780">this</span> <span m="4377050">guy</span> <span m="4377260">by</span>
  <span m="4377440">lambda</span> <span m="4377770">1,</span> <span m="4377950">this</span>
  <span m="4378100">guy</span> <span m="4378220">by lambda</span> <span m="4378610">2,</span>
  <span m="4378950">and</span> <span m="4378970">this</span> <span m="4379120">guy</span>
  <span m="4379280">by</span> <span m="4379400">lambda</span> <span m="4379940">d,</span>
  <span m="4380650">so</span> <span m="4380770">this</span> <span m="4380950">is</span>
  <span m="4381070">really</span> <span m="4381340">just</span> <span m="4381580">lambda</span>
  <span m="4381860">1.</span> <span m="4384720">And</span> <span m="4384810">now</span>
  <span m="4384990">I</span> <span m="4385050">need</span> <span m="4385170">to</span>
  <span m="4385450">post-multiply</span> <span m="4387540">by</span> <span m="4389610">P.</span>
  <span m="4392080">So</span> <span m="4392260">what</span> <span m="4392410">is</span>
  <span m="4392560">P</span> <span m="4392890">times</span> <span m="4393250">this</span>
  <span m="4393430">guy?</span> <span m="4394190">Well,</span> <span m="4394360">P</span>
  <span m="4394630">is</span> <span m="4396460">v1</span> <span m="4397530">all</span>
  <span m="4397690">the</span> <span m="4397810">way</span> <span m="4397960">to</span>
  <span m="4398140">vd.</span> <span m="4399730">And</span> <span m="4399820">now</span>
  <span m="4400030">I</span> <span m="4400120">multiply</span> <span m="4400600">by</span>
  <span m="4400780">a</span> <span m="4400810">vector</span> <span m="4401170">that</span>
  <span m="4401290">only</span> <span m="4401530">has</span> <span m="4401680">0's</span>
  <span m="4402220">except</span> <span m="4402680">lambda</span> <span m="4402880">1</span>
  <span m="4403120">on</span> <span m="4403210">the</span> <span m="4403300">first</span>
  <span m="4403570">guy.</span> <span m="4404620">So</span> <span m="4404740">this</span>
  <span m="4404950">is</span> <span m="4405070">just</span> <span m="4405330">lambda</span>
  <span m="4405630">1</span> <span m="4405840">times</span> <span m="4406100">v1.</span></p><p><span
  m="4409470">So</span> <span m="4409620">what</span> <span m="4409780">we've</span>
  <span m="4409980">proved</span> <span m="4410310">is</span> <span m="4410430">that</span>
  <span m="4410610">sigma</span> <span m="4411000">times</span> <span m="4411310">v1</span>
  <span m="4413280">is</span> <span m="4413460">lambda</span> <span m="4413830">1</span>
  <span m="4414040">v1,</span> <span m="4414630">and</span> <span m="4414780">that's</span>
  <span m="4415110">probably</span> <span m="4415800">the</span> <span m="4416010">notion</span>
  <span m="4416370">of</span> <span m="4416490">eigenvalue</span> <span m="4417060">you're</span>
  <span m="4417330">most</span> <span m="4417600">comfortable</span> <span m="4418050">with,</span>
  <span m="4418800">right?</span> <span m="4419010">So</span> <span m="4419760">just</span>
  <span m="4420000">when</span> <span m="4420180">I</span> <span m="4420240">multiply</span>
  <span m="4420720">by</span> <span m="4420900">v1,</span> <span m="4421240">I</span>
  <span m="4421370">get</span> <span m="4421620">v1</span> <span m="4421990">back</span>
  <span m="4422400">multiplied</span> <span m="4422700">by</span> <span m="4422850">something,</span>
  <span m="4423210">which</span> <span m="4423390">is</span> <span m="4423510">the</span>
  <span m="4423690">eigenvalue.</span> <span m="4425440">So</span> <span m="4425580">in</span>
  <span m="4425700">particular,</span> <span m="4428490">if</span> <span m="4428560">I</span>
  <span m="4428660">look</span> <span m="4428900">at</span> <span m="4429030">v1,</span>
  <span m="4430600">transpose</span> <span m="4431210">sigma</span> <span m="4432790">v1,</span>
  <span m="4434450">what</span> <span m="4434540">do</span> <span m="4434660">I</span>
  <span m="4434750">get?</span> <span m="4435180">Well,</span> <span m="4435290">I</span>
  <span m="4435350">get</span> <span m="4435980">lambda</span> <span m="4436310">1</span>
  <span m="4437660">v1</span> <span m="4438080">transpose</span> <span m="4438470">v1,</span>
  <span m="4438800">which</span> <span m="4439010">is</span> <span m="4439160">1,</span>
  <span m="4439460">right?</span> <span m="4440180">So</span> <span m="4440300">this</span>
  <span m="4440510">is</span> <span m="4440600">actually</span> <span m="4441140">lambda</span>
  <span m="4441800">1</span> <span m="4442710">v1</span> <span m="4443140">transpose</span>
  <span m="4443690">v1,</span> <span m="4444050">which</span> <span m="4444260">is</span>
  <span m="4444380">lambda</span> <span m="4444620">1,</span> <span m="4447120">OK?</span></p><p><span
  m="4448360">And</span> <span m="4448480">if</span> <span m="4448600">I</span> <span
  m="4448690">do</span> <span m="4448840">the</span> <span m="4448960">same</span>
  <span m="4449320">with</span> <span m="4449530">v2,</span> <span m="4450340">clearly</span>
  <span m="4450820">I'm</span> <span m="4450940">going</span> <span m="4451060">to</span>
  <span m="4451150">get</span> <span m="4451450">v2</span> <span m="4451960">transpose</span>
  <span m="4452470">sigma.</span> <span m="4453450">v2</span> <span m="4454230">is</span>
  <span m="4454390">equal</span> <span m="4454690">to</span> <span m="4454960">lambda</span>
  <span m="4455150">2.</span> <span m="4456910">So</span> <span m="4457030">for</span>
  <span m="4457270">each</span> <span m="4457540">of</span> <span m="4457690">the</span>
  <span m="4457810">vj's,</span> <span m="4459100">I</span> <span m="4459190">know</span>
  <span m="4459550">that</span> <span m="4459700">if</span> <span m="4459850">I</span>
  <span m="4459910">look</span> <span m="4460090">at</span> <span m="4460150">the</span>
  <span m="4460240">variance</span> <span m="4460720">along</span> <span m="4460960">the</span>
  <span m="4461050">vj,</span> <span m="4461650">it's</span> <span m="4461800">actually</span>
  <span m="4462070">exactly</span> <span m="4462580">given</span> <span m="4462880">by</span>
  <span m="4463060">those</span> <span m="4464620">eigenvalues,</span> <span m="4466266">all
  right?</span> <span m="4467760">Which</span> <span m="4468756">proves</span> <span
  m="4469254">this,</span> <span m="4473750">because</span> <span m="4474080">the</span>
  <span m="4474200">variance</span> <span m="4476330">along</span> <span m="4476570">the</span>
  <span m="4476720">eigenvectors</span> <span m="4478490">is</span> <span m="4478730">actually</span>
  <span m="4479120">equal</span> <span m="4479390">to</span> <span m="4479510">the</span>
  <span m="4479600">eigenvalues.</span> <span m="4480270">So</span> <span m="4480350">since</span>
  <span m="4480590">they're</span> <span m="4480770">variances,</span> <span m="4481370">they</span>
  <span m="4481490">have</span> <span m="4481670">to</span> <span m="4481790">be</span>
  <span m="4481870">non-negative.</span></p><p><span m="4483760">So</span> <span m="4483880">now,</span>
  <span m="4484110">I'm</span> <span m="4484300">looking</span> <span m="4484630">for</span>
  <span m="4484790">the</span> <span m="4486130">one</span> <span m="4486340">direction</span>
  <span m="4487780">that</span> <span m="4487960">has</span> <span m="4488380">the</span>
  <span m="4488530">most</span> <span m="4488740">variance,</span> <span m="4489460">right?</span>
  <span m="4490450">But</span> <span m="4490600">that's</span> <span m="4490840">not</span>
  <span m="4491110">only</span> <span m="4491470">among</span> <span m="4491830">the</span>
  <span m="4492160">eigenvectors.</span> <span m="4493040">That's</span> <span m="4493270">also</span>
  <span m="4493660">among</span> <span m="4494140">the</span> <span m="4494740">other</span>
  <span m="4494980">directions</span> <span m="4495520">that</span> <span m="4495640">are</span>
  <span m="4495700">in-between</span> <span m="4496180">the</span> <span m="4496300">eigenvectors.</span>
  <span m="4497200">If</span> <span m="4497320">I</span> <span m="4497380">were</span>
  <span m="4497530">to</span> <span m="4497650">look</span> <span m="4497860">only</span>
  <span m="4498190">at</span> <span m="4498310">the</span> <span m="4498430">eigenvectors,</span>
  <span m="4499390">it</span> <span m="4499450">would</span> <span m="4499600">just</span>
  <span m="4499780">tell</span> <span m="4499990">me,</span> <span m="4500140">well,</span>
  <span m="4500290">just</span> <span m="4500530">pick</span> <span m="4500770">the</span>
  <span m="4500890">eigenvector,</span> <span m="4501890">vj,</span> <span m="4502420">that's</span>
  <span m="4502630">associated</span> <span m="4503110">to</span> <span m="4503260">the</span>
  <span m="4503350">largest</span> <span m="4503830">of</span> <span m="4503890">the</span>
  <span m="4504010">lambda</span> <span m="4504310">j's.</span></p><p><span m="4505990">But</span>
  <span m="4506110">it</span> <span m="4506170">turns</span> <span m="4506470">out</span>
  <span m="4506620">that</span> <span m="4507370">that's</span> <span m="4507610">also</span>
  <span m="4507940">true</span> <span m="4508180">for</span> <span m="4508360">any</span>
  <span m="4508570">vector--</span> <span m="4509080">that</span> <span m="4509200">the</span>
  <span m="4509320">maximum</span> <span m="4510010">direction</span> <span m="4510520">is</span>
  <span m="4510640">actually</span> <span m="4511090">one</span> <span m="4511270">direction</span>
  <span m="4511720">which is</span> <span m="4511900">among</span> <span m="4512380">the</span>
  <span m="4512500">eigenvectors.</span> <span m="4513910">And</span> <span m="4514210">among</span>
  <span m="4514510">the</span> <span m="4514600">eigenvectors,</span> <span m="4515200">we</span>
  <span m="4515320">know</span> <span m="4515470">that</span> <span m="4515620">the</span>
  <span m="4515740">one</span> <span m="4515920">that's</span> <span m="4516100">the</span>
  <span m="4516220">largest--</span> <span m="4517080">that</span> <span m="4517300">carries</span>
  <span m="4517630">the</span> <span m="4517840">largest</span> <span m="4518200">variance</span>
  <span m="4518620">is</span> <span m="4518740">the</span> <span m="4518830">one</span>
  <span m="4519040">that's</span> <span m="4519700">associated</span> <span m="4520210">to</span>
  <span m="4520360">the</span> <span m="4520480">largest</span> <span m="4521200">eigenvalue,</span>
  <span m="4522850">all</span> <span m="4522910">right?</span></p><p><span m="4523780">And</span>
  <span m="4523930">so</span> <span m="4524860">this</span> <span m="4525100">is</span>
  <span m="4525220">what</span> <span m="4525370">PCA</span> <span m="4525800">is</span>
  <span m="4525910">going</span> <span m="4526090">to</span> <span m="4526150">try</span>
  <span m="4526360">to</span> <span m="4526480">do</span> <span m="4526660">for</span>
  <span m="4526810">me.</span> <span m="4526990">So</span> <span m="4527110">in</span>
  <span m="4527200">practice,</span> <span m="4528040">that's</span> <span m="4528280">what</span>
  <span m="4528400">I</span> <span m="4528460">mentioned</span> <span m="4528860">already,</span>
  <span m="4529180">right?</span> <span m="4529420">We're</span> <span m="4529570">trying</span>
  <span m="4529900">to</span> <span m="4530860">project</span> <span m="4531250">the</span>
  <span m="4531370">point</span> <span m="4531640">cloud</span> <span m="4531970">onto</span>
  <span m="4532330">a</span> <span m="4532540">low-dimensional</span> <span m="4533260">space,</span>
  <span m="4533590">D</span> <span m="4533770">prime,</span> <span m="4534730">by</span>
  <span m="4534970">keeping</span> <span m="4535360">as</span> <span m="4535480">much</span>
  <span m="4535690">information</span> <span m="4536230">as</span> <span m="4536320">possible.</span>
  <span m="4536800">And</span> <span m="4536890">by</span> <span m="4537130">&quot;as</span>
  <span m="4537310">much</span> <span m="4537490">information,&quot;</span> <span
  m="4538030">I</span> <span m="4538130">mean</span> <span m="4538630">we</span> <span
  m="4538750">do</span> <span m="4538900">not</span> <span m="4539230">want</span>
  <span m="4539500">points</span> <span m="4539830">to</span> <span m="4539980">collide.</span></p><p><span
  m="4541540">And</span> <span m="4541690">so</span> <span m="4543730">what</span>
  <span m="4543880">PCA</span> <span m="4544330">is</span> <span m="4544570">going</span>
  <span m="4544750">to</span> <span m="4544810">do</span> <span m="4545110">is</span>
  <span m="4545290">just</span> <span m="4545530">going</span> <span m="4545650">to</span>
  <span m="4545770">try</span> <span m="4546250">to</span> <span m="4547150">project</span>
  <span m="4547630">[? on two ?]</span> <span m="4548060">directions.</span> <span
  m="4548450">So</span> <span m="4548540">there's</span> <span m="4548740">going</span>
  <span m="4548860">to</span> <span m="4548920">be</span> <span m="4549040">a</span>
  <span m="4549080">u,</span> <span m="4549460">and</span> <span m="4549580">then</span>
  <span m="4549730">there's</span> <span m="4549880">going</span> <span m="4550000">to</span>
  <span m="4550060">be</span> <span m="4550150">something</span> <span m="4550510">orthogonal</span>
  <span m="4550990">to</span> <span m="4551110">u,</span> <span m="4551480">and</span>
  <span m="4551580">then</span> <span m="4551590">the</span> <span m="4551710">third</span>
  <span m="4551980">one,</span> <span m="4552180">et cetera,</span> <span m="4553030">so</span>
  <span m="4553180">that</span> <span m="4553720">once</span> <span m="4553960">we</span>
  <span m="4554050">project</span> <span m="4554550">on those,</span> <span m="4555550">we're</span>
  <span m="4555850">keeping</span> <span m="4556270">as</span> <span m="4556420">much</span>
  <span m="4556660">of</span> <span m="4556780">the</span> <span m="4556930">covariance</span>
  <span m="4557410">as</span> <span m="4557500">possible,</span> <span m="4558760">OK?</span>
  <span m="4559600">And</span> <span m="4559750">in</span> <span m="4559840">particular,</span>
  <span m="4561730">those</span> <span m="4562330">directions</span> <span m="4562990">that</span>
  <span m="4563140">we're</span> <span m="4563260">going</span> <span m="4563380">to</span>
  <span m="4563470">pick</span> <span m="4563770">are</span> <span m="4563860">actually</span>
  <span m="4564400">a</span> <span m="4564460">subset</span> <span m="4565030">of</span>
  <span m="4565150">the</span> <span m="4565270">vj's</span> <span m="4565690">that</span>
  <span m="4565780">are</span> <span m="4565840">associated</span> <span m="4566310">to</span>
  <span m="4566470">the</span> <span m="4566530">largest</span> <span m="4566920">eigenvalues.</span></p><p><span
  m="4568580">So</span> <span m="4569560">I'm</span> <span m="4569680">going</span>
  <span m="4569830">to</span> <span m="4569890">stop</span> <span m="4570280">here</span>
  <span m="4570550">for</span> <span m="4570790">today.</span> <span m="4571300">We'll</span>
  <span m="4571480">finish</span> <span m="4571840">this</span> <span m="4572140">on</span>
  <span m="4574120">Tuesday.</span> <span m="4575020">But</span> <span m="4575200">basically,</span>
  <span m="4575740">the</span> <span m="4575920">idea</span> <span m="4576250">is</span>
  <span m="4576650">it's</span> <span m="4576900">just</span> <span m="4577120">the</span>
  <span m="4577240">following.</span> <span m="4578260">You're</span> <span m="4578530">just</span>
  <span m="4579250">going</span> <span m="4579640">to--</span> <span m="4579940">well,</span>
  <span m="4580330">let</span> <span m="4580450">me</span> <span m="4580570">skip</span>
  <span m="4580900">one</span> <span m="4581140">more.</span></p><p><span m="4582590">Yeah,</span>
  <span m="4583150">this</span> <span m="4583330">is</span> <span m="4583450">the</span>
  <span m="4583570">idea.</span> <span m="4584880">You're</span> <span m="4585040">first</span>
  <span m="4585370">going</span> <span m="4585490">to</span> <span m="4585580">pick</span>
  <span m="4585940">the</span> <span m="4586090">eigenvector</span> <span m="4586630">associated</span>
  <span m="4587020">to</span> <span m="4587140">the</span> <span m="4587200">largest</span>
  <span m="4587590">eigenvalue.</span> <span m="4590290">Then</span> <span m="4590410">you're</span>
  <span m="4590530">going</span> <span m="4590650">to</span> <span m="4590740">pick</span>
  <span m="4591070">the</span> <span m="4592990">direction</span> <span m="4593380">that</span>
  <span m="4593490">orthogonal</span> <span m="4593890">to the</span> <span m="4595870">vector</span>
  <span m="4596230">that</span> <span m="4596320">you've</span> <span m="4596530">picked,</span>
  <span m="4597130">and</span> <span m="4597280">that's</span> <span m="4597520">carrying</span>
  <span m="4597910">the</span> <span m="4598000">most</span> <span m="4598210">variance.</span>
  <span m="4599240">And</span> <span m="4599260">that's</span> <span m="4599470">actually</span>
  <span m="4599710">the</span> <span m="4599830">second</span> <span m="4600160">largest--</span>
  <span m="4600650">the</span> <span m="4601135">eigenvector</span> <span m="4601710">associated</span>
  <span m="4601980">to</span> <span m="4602230">the</span> <span m="4602350">second</span>
  <span m="4602710">largest</span> <span m="4603040">eigenvalue.</span></p><p><span
  m="4604030">And</span> <span m="4604150">you're</span> <span m="4604240">going</span>
  <span m="4604390">to</span> <span m="4604450">go</span> <span m="4604600">all</span>
  <span m="4604780">the</span> <span m="4604900">way</span> <span m="4605080">to</span>
  <span m="4605860">the</span> <span m="4605950">number</span> <span m="4606280">of</span>
  <span m="4606400">them</span> <span m="4606520">that</span> <span m="4606640">you</span>
  <span m="4606850">actually</span> <span m="4607210">want</span> <span m="4607330">to</span>
  <span m="4607390">pick,</span> <span m="4607630">which</span> <span m="4607810">is</span>
  <span m="4607930">in</span> <span m="4608020">this</span> <span m="4608200">case,</span>
  <span m="4608965">d,</span> <span m="4609430">OK?</span> <span m="4610120">And</span>
  <span m="4610570">wherever</span> <span m="4610990">you</span> <span m="4611140">choose</span>
  <span m="4611470">to</span> <span m="4611620">chop</span> <span m="4612040">this</span>
  <span m="4612400">process,</span> <span m="4613180">not</span> <span m="4613400">going</span>
  <span m="4613720">all</span> <span m="4613840">the</span> <span m="4613930">way</span>
  <span m="4614050">to</span> <span m="4614220">d,</span> <span m="4614830">is</span>
  <span m="4615040">going</span> <span m="4615160">to</span> <span m="4615220">actually</span>
  <span m="4615580">give</span> <span m="4615790">you</span> <span m="4616390">a</span>
  <span m="4616480">lower-dimensional</span> <span m="4617140">representation</span>
  <span m="4617890">in</span> <span m="4618040">the</span> <span m="4618130">coordinate</span>
  <span m="4618610">system</span> <span m="4618970">that's</span> <span m="4619150">given</span>
  <span m="4619420">by</span> <span m="4619630">v1,</span> <span m="4619750">v2,</span>
  <span m="4620170">v3,</span> <span m="4620870">et cetera,</span> <span m="4621606">OK?</span>
  <span m="4622420">So</span> <span m="4622540">we'll</span> <span m="4622720">see</span>
  <span m="4622870">that</span> <span m="4623020">in</span> <span m="4623140">more</span>
  <span m="4623290">details</span> <span m="4624340">on</span> <span m="4624460">Tuesday.</span>
  <span m="4624820">But</span> <span m="4624970">I</span> <span m="4625030">don't</span>
  <span m="4625150">want</span> <span m="4625270">to</span> <span m="4625330">get</span>
  <span m="4625510">into</span> <span m="4625810">it</span> <span m="4625940">now.</span>
  <span m="4626090">We</span> <span m="4626230">don't have</span> <span m="4626360">enough</span>
  <span m="4626740">time.</span> <span m="4627500">Are</span> <span m="4627880">there</span>
  <span m="4628000">any</span> <span m="4628150">questions?</span></p>
type: course
uid: 6c01f00215566284e6dc0c87d3ed95a5

---
None