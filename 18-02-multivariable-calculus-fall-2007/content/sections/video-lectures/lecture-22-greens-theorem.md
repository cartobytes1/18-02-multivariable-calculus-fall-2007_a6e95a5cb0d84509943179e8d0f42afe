---
about_this_resource_text: <p><strong>Topics covered:</strong> Green's theorem</p>
  <p><strong>Instructor:</strong> Prof. Denis Auroux</p>
course_id: 18-02-multivariable-calculus-fall-2007
embedded_media:
- id: 22.jpg
  parent_uid: dcbc1462a3cd2379c405327ef53ae39f
  technical_location: https://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-22-greens-theorem/22.jpg
  title: 'Lecture 22: Green''s Theorem'
  type: null
  uid: f67199af4509bbac1398d6fdcb7594dc
- id: Video-YouTube-Stream
  media_location: tYdoS0tkAHA
  parent_uid: dcbc1462a3cd2379c405327ef53ae39f
  title: Video-YouTube-Stream
  type: Video
  uid: 2366bdb914360a0679641590a0495531
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/tYdoS0tkAHA/default.jpg
  parent_uid: dcbc1462a3cd2379c405327ef53ae39f
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: cbbdb875c49b2c504bd7170acf8a23fc
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id354869122
  parent_uid: dcbc1462a3cd2379c405327ef53ae39f
  title: Video-iTunes U-MP4
  type: Video
  uid: c00b079f678bf3080140f1cf87ce656b
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT18.02F07/ocw-18_02-f07-lec22_300k.mp4
  parent_uid: dcbc1462a3cd2379c405327ef53ae39f
  title: Video-Internet Archive-MP4
  type: Video
  uid: 66685230e94657c2296e2238b3906dac
- id: Video-VideoLecturesnet-Stream
  media_location: http://videolectures.net/mit1802f07_multivariable_calculus/
  parent_uid: dcbc1462a3cd2379c405327ef53ae39f
  title: Video-VideoLectures.net-Stream
  type: Video
  uid: 56dbb639fff947c1e0ff9656969052b1
- id: Thumbnail-OCW-JPG
  parent_uid: dcbc1462a3cd2379c405327ef53ae39f
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: 03fc63822510a3016fcc6bd272e35707
- id: 3Play-3PlayYouTubeid-MP4
  media_location: tYdoS0tkAHA
  parent_uid: dcbc1462a3cd2379c405327ef53ae39f
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: cc2d2063ad246bd1e2ae6cbfc9960aa7
- id: tYdoS0tkAHA.srt
  parent_uid: dcbc1462a3cd2379c405327ef53ae39f
  technical_location: https://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-22-greens-theorem/tYdoS0tkAHA.srt
  title: 3play caption file
  type: null
  uid: c0c44e3cb53c8c19b7f2801221337827
- id: tYdoS0tkAHA.pdf
  parent_uid: dcbc1462a3cd2379c405327ef53ae39f
  technical_location: https://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-22-greens-theorem/tYdoS0tkAHA.pdf
  title: 3play pdf file
  type: null
  uid: 146b24918d4297fb69788c32d9e991fd
- id: Caption-3Play YouTube id-SRT
  parent_uid: dcbc1462a3cd2379c405327ef53ae39f
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 3e9455f7f4309281f5d280b59cf210a0
- id: Transcript-3Play YouTube id-PDF
  parent_uid: dcbc1462a3cd2379c405327ef53ae39f
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 9a9384adb215f66441d04e957050a011
inline_embed_id: 2373276lecture22:green'stheorem71906258
layout: video
order_index: null
parent_uid: d4e54c6363f292115697e70de7a59fd1
related_resources_text: <p>Lecture Notes - Week 9 Summary (<a title="Open in a new
  window." target="_blank" href="./resolveuid/14a8493b19c42b8fbbeb9d05b5c0fd52">PDF</a>)&nbsp;</p>
short_url: lecture-22-greens-theorem
technical_location: https://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-22-greens-theorem
template_type: Tabbed
title: 'Lecture 22: Green''s Theorem'
transcript: <p><span m='1000'> The following content is provided under a Creative</span>
  <span m='3000'>Commons license. Your support will help MIT</span> <span m='5000'>OpenCourseWare
  continue to offer high quality educational</span> <span m='8000'>resources for free.
  To make a donation or to view</span> <span m='13000'>additional materials from hundreds
  of MIT courses,</span> <span m='18000'>visit MIT OpenCourseWare at ocw.mit.edu.</span>
  <span m='23000'>OK, so last time we've seen the curl of the vector field with</span>
  <span m='32000'>components M and N. We defined that to be N sub x</span> <span m='39000'>minus
  M sub y. And, we said this measures how</span> <span m='43000'>far that vector field
  is from being conservative.</span> <span m='47000'>If the curl is zero, and if the
  field is defined</span> <span m='50000'>everywhere, then it's going to be conservative.</span>
  <span m='53000'>And so, when I take the line integral along a closed curve,</span>
  <span m='55000'>I don't have to compute it. I notes going to be zero.</span> <span
  m='59000'>But now, let's say that I have a general vector field.</span> <span m='64000'>So,
  the curl will not be zero. And, I still want to compute</span> <span m='67000'>the
  line integral along a closed curve.</span> <span m='70000'>Well, I could compute
  it directly or there's another way.</span> <span m='74000'>And that's what we are
  going to see today.</span> <span m='77000'>So, say that I have a closed curve, C,
  and I want to find the</span> <span m='86000'>work. So, there's two options.</span>
  <span m='90000'>One is direct calculation, and the other one is Green's</span> <span
  m='100000'>theorem. So, Green's theorem is another</span> <span m='107000'>way to
  avoid calculating line integrals if we don't want to.</span> <span m='116000'>OK,
  so what does it say? It says if C is a closed curve</span> <span m='124000'>enclosing
  a region R in the plane, and I have to insist C</span> <span m='136000'>should go
  counterclockwise. And, if I have a vector field</span> <span m='148000'>that's defined
  and differentiable everywhere not</span> <span m='157000'>only on the curve, C,
  which is what I need to</span> <span m='162000'>define the line integral, but also
  on the region inside.</span> <span m='168000'>Then -- -- the line integral for the
  work done along C is</span> <span m='177000'>actually equal to a double integral
  over the region inside</span> <span m='187000'>of curl F dA. OK, so that's the conclusion.</span>
  <span m='195000'>And, if you want me to write it in coordinates,</span> <span m='199000'>maybe
  I should do that. So, the line integral in terms</span> <span m='204000'>of the
  components, that's the integral of M dx</span> <span m='208000'>plus N dy. And,
  the curl is (Nx-My)dA.</span> <span m='216000'>OK, so that's the other way to state
  it.</span> <span m='222000'>So, that's a really strange statement if you think about
  it</span> <span m='227000'>because the left-hand side is a line integral.</span>
  <span m='231000'>OK, so the way we compute it is we take this expression Mdx Ndy</span>
  <span m='237000'>and we parameterize the curve. We express x and y in terms of</span>
  <span m='241000'>some variable, t, maybe, or whatever you want</span> <span m='244000'>to
  call it. And then, you'll do a one</span> <span m='247000'>variable integral over
  t. This right-hand side here,</span> <span m='251000'>it's a double integral, dA.</span>
  <span m='253000'>So, we do it the way that we learn how to couple of weeks</span>
  <span m='256000'>ago. You take your region,</span> <span m='258000'>you slice it
  in the x direction or in the y direction,</span> <span m='262000'>and you integrate
  dx dy after setting up the bounds carefully,</span> <span m='266000'>or maybe in
  polar coordinates r dr d theta.</span> <span m='269000'>But, see, the way you compute
  these things is completely</span> <span m='272000'>different. This one on the left-hand
  side</span> <span m='276000'>lives only on the curve, while the right-hand side
  lives</span> <span m='282000'>everywhere in this region inside.</span> <span m='286000'>So,
  here, x and y are related, they live on the curve.</span> <span m='289000'>Here,
  x and y are independent. There just are some bounds</span> <span m='293000'>between
  them. And, of course,</span> <span m='294000'>what you're integrating is different.</span>
  <span m='296000'>It's a line integral for work. Here, it's a double integral of</span>
  <span m='301000'>some function of x and y. So, it's a very perplexing</span> <span
  m='308000'>statement at first. But, it's a very powerful tool.</span> <span m='314000'>So,
  we're going to try to see how it works concretely,</span> <span m='318000'>what
  it says, what are the consequences,</span> <span m='320000'>how we could convince
  ourselves that, yes,</span> <span m='323000'>this works, and so on. That's going
  to be the topic</span> <span m='326000'>for today. Any questions about the</span>
  <span m='332000'>statement first? No?</span> <span m='338000'>OK, yeah, one remark,
  sorry. So, here, it stays</span> <span m='343000'>counterclockwise. What if I have
  a curve that</span> <span m='346000'>goes clockwise? Well, you could just take the</span>
  <span m='349000'>negative, and integrate counterclockwise.</span> <span m='352000'>Why
  does the theorem choose counterclockwise over clockwise?</span> <span m='357000'>How
  doesn't know that it's counterclockwise rather than</span> <span m='360000'>clockwise?
  Well, the answer is basically</span> <span m='362000'>in our convention for curl.
  See, we've said curl is Nx</span> <span m='365000'>minus My, and not the other way
  around.</span> <span m='368000'>And, that's a convention as well.</span> <span m='370000'>So,
  somehow, the two conventions match with</span> <span m='373000'>each other. That's
  the best answer I can</span> <span m='375000'>give you. So, if you met somebody
  from a</span> <span m='378000'>different planet, they might have Green's theorem</span>
  <span m='380000'>with the opposite conventions, with curves going clockwise,</span>
  <span m='383000'>and the curl defined the other way around.</span> <span m='387000'>Probably
  if you met an alien, I'm not sure if you would be</span> <span m='395000'>discussing
  Green's theorem first, but just in case.</span> <span m='403000'>OK, so that being
  said, there is a warning here which</span> <span m='413000'>is that this is only
  for closed curves.</span> <span m='420000'>OK, so if I give you a curve that's not
  closed,</span> <span m='423000'>and I tell you, well, compute the line</span> <span
  m='425000'>integral, then you have to do it by hand.</span> <span m='428000'>You
  have to parameterize the curve.</span> <span m='430000'>Or, if you really don't
  like that line integral,</span> <span m='432000'>you could close the path by adding
  some other line integral</span> <span m='436000'>to it, and then compute using Green's</span>
  <span m='439000'>theorem. But, you can't use Green's</span> <span m='443000'>theorem
  directly if the curve is not closed.</span> <span m='450000'>OK, so let's do a quick
  example. So, let's say that I give you</span> <span m='462000'>C, the circle of
  radius one, centered at the point (2,0).</span> <span m='472000'>So, it's out here.
  That's my curve, C.</span> <span m='480000'>And, let's say that I do it counterclockwise
  so that it will</span> <span m='489000'>match with the statement of the theorem.</span>
  <span m='496000'>And, let's say that I want you to compute the line integral</span>
  <span m='504000'>along C of ye^(-x) dx plus (one half of x squared minus e^(-x))</span>
  <span m='514000'>dy. And, that's a kind of sadistic</span> <span m='517000'>example,
  but maybe I'll ask you to do that.</span> <span m='521000'>So, how would you do
  it directly?</span> <span m='524000'>Well, to do it directly you would have to parameterize
  this</span> <span m='528000'>curve. So that would probably involve</span> <span
  m='533000'>setting x equals two plus cosine theta y equals sine theta.</span> <span
  m='543000'>But, I'm using as parameter of the angle around the circle,</span> <span
  m='546000'>it's like the unit circle, the usual ones that shifted by</span> <span
  m='549000'>two in the x direction. And then, I would set dx equals</span> <span
  m='555000'>minus sine theta d theta. I would set dy equals cosine</span> <span m='561000'>theta
  d theta. And, I will substitute,</span> <span m='564000'>and I will integrate from
  zero to 2pi.</span> <span m='566000'>And, I would probably run into a bit of trouble
  because I would</span> <span m='569000'>have these e to the minus x, which would
  give me something</span> <span m='572000'>that I really don't want to integrate.</span>
  <span m='575000'>So, instead of doing that, which looks pretty much doomed,</span>
  <span m='584000'>instead, I'm going to use Green's theorem.</span> <span m='591000'>So,
  using Green's theorem, the way we'll do it is I will,</span> <span m='598000'>instead,
  compute a double integral.</span> <span m='603000'>So, I will -- -- compute the
  double integral over the region</span> <span m='616000'>inside of curl F dA. So,
  I should say probably what</span> <span m='627000'>F was. So, let's call this M.</span>
  <span m='630000'>Let's call this N. And, then I will actually just</span> <span
  m='637000'>choose the form coordinates, (Nx minus My) dA.</span> <span m='645000'>And,
  what is R here? Well, R is the disk in here.</span> <span m='653000'>OK, so, of
  course, it might not be that pleasant</span> <span m='656000'>because we'll also
  have to set up this double integral.</span> <span m='658000'>And, for that, we'll
  have to figure out a way</span> <span m='662000'>to slice this region nicely. We
  could do it dx dy.</span> <span m='665000'>We could do it dy dx. Or, maybe we will
  want to</span> <span m='668000'>actually make a change of variables to first shift
  this to</span> <span m='671000'>the origin, you know, change x to x minus</span>
  <span m='674000'>two and then switch to polar coordinates.</span> <span m='677000'>Well,
  let's see what happens later.</span> <span m='682000'>OK, so what is, so this is
  R. So, what is N sub x?</span> <span m='693000'>Well, N sub x is x plus e to the
  minus x minus,</span> <span m='702000'>what is M sub y, e to the minus x,</span>
  <span m='708000'>OK? This is Nx.</span> <span m='712000'>This is My dA. Well, it
  seems to simplify a</span> <span m='718000'>bit. I will just get double integral</span>
  <span m='722000'>over R of x dA, which looks certainly a lot</span> <span m='726000'>more
  pleasant. Of course, I made up the</span> <span m='730000'>example in that way so
  that it simplifies when you use Green's</span> <span m='734000'>theorem. But, you
  know,</span> <span m='736000'>it gives you an example where you can turn are really
  hard</span> <span m='740000'>line integral into an easier double integral.</span>
  <span m='743000'>Now, how do we compute that double integral?</span> <span m='748000'>Well,
  so one way would be to set it up.</span> <span m='752000'>Or, let's actually be
  a bit smarter and observe that this is</span> <span m='761000'>actually the area
  of the region R, times the x coordinate of its</span> <span m='770000'>center of
  mass. If I look at the definition of</span> <span m='775000'>the center of mass,
  it's the average value of x.</span> <span m='779000'>So, it's one over the area
  times the double integral of x</span> <span m='783000'>dA, well, possibly with the
  density, but here I'm thinking</span> <span m='787000'>uniform density one. And,
  now, I think I know just</span> <span m='791000'>by looking at the picture where
  the center of mass of this</span> <span m='795000'>circle will be, right?</span>
  <span m='796000'>I mean, it would be right in the middle.</span> <span m='799000'>So,
  that is two, if you want,</span> <span m='804000'>by symmetry. And, the area of
  the guy is</span> <span m='809000'>just pi because it's a disk of radius one.</span>
  <span m='813000'>So, I will just get 2pi. I mean, of course,</span> <span m='817000'>if
  you didn't see that, then you can also compute that</span> <span m='820000'>double
  integral directly. It's a nice exercise.</span> <span m='823000'>But see, here,
  using geometry helps you to</span> <span m='827000'>actually streamline the calculation.</span>
  <span m='830000'>OK, any questions? Yes?</span> <span m='841000'>OK, yes, let me
  just repeat the last part.</span> <span m='844000'>So, I said we had to compute
  the double integral of x dA over</span> <span m='850000'>this region here, which
  is a disk of radius one,</span> <span m='854000'>centered at, this point is (2,0).</span>
  <span m='858000'>So, instead of setting up the integral with bounds and</span> <span
  m='862000'>integrating dx dy or dy dx or in polar coordinates,</span> <span m='866000'>I'm
  just going to say, well, let's remember the definition</span> <span m='870000'>of
  a center of mass. It's the average value of a</span> <span m='872000'>function,
  x in the region. So, it's one over the area of</span> <span m='877000'>origin times
  the double integral of x dA.</span> <span m='882000'>If you look, again, at the
  definition of x</span> <span m='886000'>bar, it's one over area of double integral
  x dA.</span> <span m='891000'>Well, maybe if there's a density, then it's one over
  mass</span> <span m='894000'>times double integral of x density dA.</span> <span
  m='897000'>But, if density is one, then it just becomes this.</span> <span m='902000'>So,
  switching the area, moving the area to the other</span> <span m='906000'>side, I'll
  get double integral of x</span> <span m='908000'>dA is the area of origin times
  the x coordinate of the center</span> <span m='912000'>of mass. The area of origin
  is pi</span> <span m='914000'>because it's a unit disk. And, the center of mass
  is the</span> <span m='918000'>center of a disk. So, its x bar is two,</span> <span
  m='923000'>and I get 2 pi. OK, that I didn't actually have</span> <span m='927000'>to
  do this in my example today, but of course that would be</span> <span m='930000'>good
  review. It will remind you of center of</span> <span m='936000'>mass and all that.
  OK, any other questions?</span> <span m='947000'>No? OK, so let's see,</span> <span
  m='950000'>now that we've seen how to use it practice, how to avoid</span> <span
  m='954000'>calculating the line integral if we don't want to.</span> <span m='958000'>Let's
  try to convince ourselves that this theorem makes sense.</span> <span m='964000'>OK,
  so, well, let's start with an easy case</span> <span m='969000'>where we should
  be able to know the answer to both sides.</span> <span m='975000'>So let's look
  at the special case.</span> <span m='983000'>Let's look at the case where curl F
  is zero.</span> <span m='992000'>Then, well, we'd like to conclude that F is conservative.</span>
  <span m='1005000'>That's what we said. Well let's see what happens.</span> <span
  m='1013000'>So, Green's theorem says that if I have a closed curve,</span> <span
  m='1019000'>then the line integral of F is equal to the double integral of</span>
  <span m='1026000'>curl on the region inside. And, if the curl is zero,</span> <span
  m='1032000'>then I will be integrating zero.</span> <span m='1035000'>I will get
  zero. OK, so this is actually how you</span> <span m='1042000'>prove that if your
  vector field has curve zero,</span> <span m='1046000'>then it's conservative.</span>
  <span m='1074000'>OK, so in particular, if you have a vector field</span> <span
  m='1077000'>that's defined everywhere the plane, then you take any closed</span>
  <span m='1081000'>curve. Well, you will get that the</span> <span m='1084000'>line
  integral will be zero. Straightly speaking,</span> <span m='1086000'>that will only
  work here if the curve goes counterclockwise.</span> <span m='1090000'>But otherwise,
  just look at the various loops</span> <span m='1093000'>that it makes, and orient
  each of them</span> <span m='1096000'>counterclockwise and sum things together.</span>
  <span m='1099000'>So let me state that again.</span> <span m='1125000'>So, OK,</span>
  <span m='1131000'>so a consequence of Green's theorem is that if F is defined</span>
  <span m='1142000'>everywhere in the plane -- -- and the curl of F is zero</span>
  <span m='1152000'>everywhere, then F is conservative.</span> <span m='1164000'>And
  so, this actually is the input we needed to justify our</span> <span m='1169000'>criterion.
  The test that we saw last time</span> <span m='1173000'>saying, well, to check if
  something is</span> <span m='1175000'>a gradient field if it's conservative,</span>
  <span m='1177000'>we just have to compute the curl and check whether it's</span>
  <span m='1180000'>zero. OK, so how do we prove that now</span> <span m='1185000'>carefully?
  Well, you just take a closed</span> <span m='1189000'>curve in the plane. You switch
  the orientation if</span> <span m='1192000'>needed so it becomes counterclockwise.</span>
  <span m='1195000'>And then you look at the region inside.</span> <span m='1199000'>And
  then you know that the line integral inside will be equal to</span> <span m='1205000'>the
  double integral of curl, which is the double integral of</span> <span m='1212000'>zero.
  Therefore, that's zero.</span> <span m='1216000'>But see, OK, so now let's say that
  we try to</span> <span m='1219000'>do that for the vector field that was on your
  problems that</span> <span m='1223000'>was not defined at the origin. So if you've
  done the problem</span> <span m='1227000'>sets and found the same answers that I
  did, then you will have</span> <span m='1230000'>found that this vector field had
  curve zero everywhere.</span> <span m='1233000'>But still it wasn't conservative
  because if you went</span> <span m='1236000'>around the unit circle, then you got
  a line integral</span> <span m='1239000'>that was 2pi. Or, if you compared the two</span>
  <span m='1242000'>halves, you got different answers for two parts that go</span>
  <span m='1245000'>from the same point to the same point.</span> <span m='1247000'>So,
  it fails this property but that's because it's not defined</span> <span m='1251000'>everywhere.
  So, what goes wrong with this</span> <span m='1254000'>argument? Well, if I take
  the vector</span> <span m='1257000'>field that was in the problem set, and if I
  do things,</span> <span m='1263000'>say that I look at the unit circle.</span> <span
  m='1267000'>That's a closed curve. So, I would like to use Green's</span> <span
  m='1270000'>theorem. Green's theorem would tell me</span> <span m='1273000'>the
  line integral along this loop is equal to the double</span> <span m='1277000'>integral
  of curl over this region here, the unit disk.</span> <span m='1281000'>And, of course
  the curl is zero, well, except at the</span> <span m='1285000'>origin. At the origin,</span>
  <span m='1287000'>the vector field is not defined.</span> <span m='1289000'>You
  cannot take the derivatives, and the curl is not</span> <span m='1292000'>defined.
  And somehow that messes things</span> <span m='1294000'>up. You cannot apply Green's</span>
  <span m='1298000'>theorem to the vector field. So, you cannot apply Green's</span>
  <span m='1309000'>theorem to the vector field on problem set eight problem two</span>
  <span m='1322000'>when C encloses the origin. And so, that's why this guy,</span>
  <span m='1332000'>even though it has curl zero, is not conservative.</span> <span
  m='1336000'>There's no contradiction. And somehow,</span> <span m='1340000'>you
  have to imagine that, well, the curl here is really</span> <span m='1343000'>not
  defined. But somehow it becomes infinite</span> <span m='1346000'>so that when you
  do the double integral, you actually get 2 pi</span> <span m='1350000'>instead of
  zero. I mean, that doesn't make any</span> <span m='1357000'>sense, of course, but
  that's one way to think</span> <span m='1366000'>about it. OK, any questions?</span>
  <span m='1371000'>Yes? Well, though actually it's not</span> <span m='1382000'>defined
  because the curl is zero everywhere else.</span> <span m='1386000'>So, if a curl
  was well defined at the origin,</span> <span m='1388000'>you would try to, then,
  take the double integral.</span> <span m='1391000'>no matter what value you put
  for a function,</span> <span m='1392000'>if you have a function that's zero everywhere
  except at the</span> <span m='1395000'>origin, and some other value at the</span>
  <span m='1397000'>origin, the integral is still zero.</span> <span m='1400000'>So,
  it's worse than that. It's not only that you can't</span> <span m='1404000'>compute
  it, it's that is not defined.</span> <span m='1409000'>OK, anyway, that's like a
  slightly pathological example.</span> <span m='1416000'>Yes? Well, we wouldn't be
  able to</span> <span m='1424000'>because the curl is not defined at the origin.</span>
  <span m='1426000'>So, you can actually integrate it.</span> <span m='1429000'>OK,
  so that's the problem. I mean, if you try to</span> <span m='1432000'>integrate,
  we've said everywhere where it's defined,</span> <span m='1435000'>the curl is zero.
  So, what you would be</span> <span m='1437000'>integrating would be zero. But, that
  doesn't work because</span> <span m='1441000'>at the origin it's not defined. Yes?</span>
  <span m='1449000'>Ah, so if you take a curve that makes a figure 8,</span> <span
  m='1451000'>then indeed my proof over there is false.</span> <span m='1454000'>So,
  I kind of tricked you. It's not actually correct.</span> <span m='1459000'>So, if
  the curve does a figure 8, then what you do is you would</span> <span m='1464000'>actually
  cut it into its two halves.</span> <span m='1467000'>And for each of them, you will
  apply Green's theorem.</span> <span m='1470000'>And then, you'd still get, if a
  curl is zero then this</span> <span m='1472000'>line integral is zero. That one
  is also zero.</span> <span m='1475000'>So this one is zero. OK, small details that
  you</span> <span m='1478000'>don't really need to worry too much about,</span> <span
  m='1481000'>but indeed if you want to be careful with details then my</span> <span
  m='1487000'>proof is not quite complete. But the computation is still</span> <span
  m='1494000'>true. Let's move on.</span> <span m='1498000'>So, I want to tell you
  how to prove Green's theorem because</span> <span m='1506000'>it's such a strange
  formula that where can it come from possibly?</span> <span m='1515000'>I mean, so
  let me remind you first of</span> <span m='1521000'>all the statement we want to
  prove is that the line integral</span> <span m='1526000'>along a closed curve of
  Mdx plus Ndy is equal to the double</span> <span m='1531000'>integral over the region
  inside of (Nx minus My)dA.</span> <span m='1536000'>And, let's simplify our lives
  a bit by proving easier</span> <span m='1540000'>statements. So actually,</span>
  <span m='1543000'>the first observation will actually prove something easier,</span>
  <span m='1553000'>namely, that the line integral, let's see,</span> <span m='1558000'>of
  Mdx along a closed curve is equal to the double integral</span> <span m='1563000'>over
  the region inside of minus M sub y dA.</span> <span m='1568000'>OK, so that's the
  special case where N is zero,</span> <span m='1573000'>where you have only an x
  component for your vector field.</span> <span m='1579000'>Now, why is that good
  enough? Well, the claim is if I can</span> <span m='1583000'>prove this, I claim
  you will be able to do the same thing to</span> <span m='1588000'>prove the other
  case where there is only the y component.</span> <span m='1593000'>And then, if
  the other together, you will get the</span> <span m='1598000'>general case. So,
  let me explain.</span> <span m='1620000'>OK, so a similar argument which I will
  not do,</span> <span m='1626000'>to save time, will show, so actually it's</span>
  <span m='1631000'>just the same thing but switching the roles of x and y,</span>
  <span m='1635000'>that if I integrate along a closed curve N dy,</span> <span m='1640000'>then
  I'll get the double integral of N sub x dA.</span> <span m='1649000'>And so, now
  if I have proved these two formulas separately,</span> <span m='1656000'>then if
  you sum them together will get the correct statement.</span> <span m='1664000'>Let
  me write it. We get Green's theorem.</span> <span m='1672000'>OK, so we've simplified
  our task a little bit.</span> <span m='1675000'>We'll just be trying to prove the
  case where there's only an x</span> <span m='1680000'>component. So, let's do it.</span>
  <span m='1684000'>Well, we have another problem which is the region that we are</span>
  <span m='1687000'>looking at, the curve that we're looking at might be very</span>
  <span m='1690000'>complicated. If I give you,</span> <span m='1692000'>let's say
  I give you, I don't know,</span> <span m='1697000'>a curve that does something like
  this.</span> <span m='1702000'>Well, it will be kind of tricky to set up a double
  integral over</span> <span m='1706000'>the region inside. So maybe we first want
  to look</span> <span m='1709000'>at curves that are simpler, that will actually
  allow us to</span> <span m='1713000'>set up the double integral easily.</span> <span
  m='1716000'>So, the second observation, so that was the first</span> <span m='1722000'>observation.
  The second observation is that</span> <span m='1731000'>we can decompose R into
  simpler regions.</span> <span m='1742000'>So what do I mean by that? Well, let's
  say that I have a</span> <span m='1750000'>region and I'm going to cut it into two.</span>
  <span m='1753000'>So, I'll have R1 and R2. And then, of course,</span> <span m='1758000'>I
  need to have the curves that go around them.</span> <span m='1762000'>So, I had
  my initial curve, C, was going around everybody.</span> <span m='1769000'>They have
  curves C1 that goes around R1, and C2 goes around</span> <span m='1781000'>R2. OK,
  so,</span> <span m='1786000'>what I would like to say is if we can prove that the
  statement</span> <span m='1795000'>is true, so let's see, for C1 and also for C2
  -- --</span> <span m='1807000'>then I claim we can prove the statement for C.</span>
  <span m='1823000'>How do we do that? Well, we just add these two</span> <span m='1826000'>equalities
  together. OK, why does that work?</span> <span m='1828000'>There's something fishy
  going on because C1 and C2 have this</span> <span m='1831000'>piece here in the
  middle. That's not there in C.</span> <span m='1835000'>So, if you add the line
  integral along C1 and C2,</span> <span m='1839000'>you get these unwanted pieces.
  But, the good news is actually</span> <span m='1844000'>you go twice through that
  edge in the middle.</span> <span m='1847000'>See, it appears once in C1 going up,
  and once in C2 going</span> <span m='1851000'>down. So, in fact,</span> <span m='1852000'>when
  you will do the work, when you will sum the work,</span> <span m='1855000'>you will
  add these two guys together.</span> <span m='1857000'>They will cancel. OK, so the
  line integral along</span> <span m='1866000'>C will be, then, it will be the sum
  of the line</span> <span m='1874000'>integrals on C1 and C2. And, that will equal,</span>
  <span m='1881000'>therefore, the double integral over R1 plus the double integral</span>
  <span m='1889000'>over R2, which is the double integral over R of negative My.</span>
  <span m='1896000'>OK and the reason for this equality here is because we go</span>
  <span m='1907000'>twice through the inner part. What do I want to say?</span> <span
  m='1916000'>Along the boundary between R1 and R2 -- -- with opposite</span> <span
  m='1935000'>orientations. So, the extra things cancel out.</span> <span m='1945000'>OK,
  so that means I just need to look at smaller pieces if</span> <span m='1949000'>that
  makes my life easier. So, now, will make my life easy?</span> <span m='1954000'>Well,
  let's say that I have a curve like that.</span> <span m='1961000'>Well, I guess
  I should really draw a pumpkin or something like</span> <span m='1965000'>that because
  it would be more seasonal.</span> <span m='1968000'>But, well, I don't really know
  how to draw a pumpkin.</span> <span m='1973000'>OK, so what I will do is I will
  cut this into smaller regions</span> <span m='1977000'>for which I have a well-defined
  lower and upper boundary so that</span> <span m='1981000'>I will be able to set
  up a double integral,</span> <span m='1985000'>dy dx, easily. So, a region like
  this I will</span> <span m='1990000'>actually cut it here and here into five smaller
  pieces so that</span> <span m='1997000'>each small piece will let me set up the
  double integral,</span> <span m='2003000'>dy dx. OK, so we'll cut R in to what I</span>
  <span m='2011000'>will call vertically simple -- -- regions.</span> <span m='2021000'>So,
  what's a vertically simple region?</span> <span m='2023000'>That's a region that's
  given by looking at x between a and b for</span> <span m='2028000'>some values of
  a and b. And, for each value of x,</span> <span m='2033000'>y is between some function
  of x and some other function of x.</span> <span m='2040000'>OK, so for example,
  this guy is vertically simple.</span> <span m='2043000'>See, x runs from this value
  of x to that value of x.</span> <span m='2047000'>And, for each x, y goes between
  this value to</span> <span m='2053000'>that value. And, same with each of these.</span>
  <span m='2079000'>OK, so now we are down to the main step that we have to do,</span>
  <span m='2089000'>which is to prove this identity if C is, sorry,</span> <span m='2105000'>if
  -- -- if R is vertically simple -- -- and C is the</span> <span m='2123000'>boundary
  of R going counterclockwise.</span> <span m='2136000'>OK, so let's look at how we
  would do it.</span> <span m='2140000'>So, we said vertically simple region looks
  like x goes between</span> <span m='2146000'>a and b, and y goes between two values
  that are given by</span> <span m='2152000'>functions of x. OK, so this is y equals
  f2 of x.</span> <span m='2157000'>This is y equals f1 of x. This is a.</span> <span
  m='2162000'>This is b. Our region is this thing in</span> <span m='2169000'>here.
  So, let's compute both sides.</span> <span m='2173000'>And, when I say compute,
  of course we will not get</span> <span m='2175000'>numbers because we don't know
  what M is.</span> <span m='2177000'>We don't know what f1 and f2 are.</span> <span
  m='2179000'>But, I claim we should be able to simplify things a bit.</span> <span
  m='2184000'>So, let's start with the line integral.</span> <span m='2188000'>How
  do I compute the line integral along the curve that</span> <span m='2195000'>goes
  all around here? Well, it looks like there will</span> <span m='2200000'>be four
  pieces. OK, so we actually have four</span> <span m='2205000'>things to compute,
  C1, C2, C3, and C4.</span> <span m='2210000'>OK? Well, let's start with C1.</span>
  <span m='2221000'>So, if we integrate on C1 Mdx, how do we do that?</span> <span
  m='2226000'>Well, we know that on C1, y is given by a function of x.</span> <span
  m='2230000'>So, we can just get rid of y and express everything in terms</span>
  <span m='2235000'>of x. OK, so, we know y is f1 of x,</span> <span m='2241000'>and
  x goes from a to b. So, that will be the integral</span> <span m='2247000'>from
  a to b of, well, I have to take the</span> <span m='2250000'>function, M. And so,
  M depends normally on x</span> <span m='2253000'>and y. Maybe I should put x and
  y here.</span> <span m='2258000'>And then, I will plug y equals f1 of x dx.</span>
  <span m='2266000'>And, then I have a single variable integral.</span> <span m='2269000'>And
  that's what I have to compute.</span> <span m='2271000'>Of course, I cannot compute
  it here because I don't know what</span> <span m='2274000'>this is. So, it has to
  stay this way.</span> <span m='2279000'>OK, next one. The integral along C2,</span>
  <span m='2286000'>well, let's think for a second. On C2, x equals b.</span> <span
  m='2293000'>It's constant. So, dx is zero,</span> <span m='2296000'>and you would
  integrate, actually, above a variable,</span> <span m='2300000'>y. But, well, we
  don't have a y</span> <span m='2303000'>component. See, this is the reason why we</span>
  <span m='2306000'>made the first observation. We got rid of the other term</span>
  <span m='2310000'>because it's simplifies our life here.</span> <span m='2313000'>So,
  we just get zero. OK, just looking quickly ahead,</span> <span m='2318000'>there's
  another one that would be zero as well,</span> <span m='2320000'>right? Which one?</span>
  <span m='2322000'>Yeah, C4. This one gives me zero.</span> <span m='2332000'>What
  about C3? Well, C3 will look a lot like</span> <span m='2335000'>C1. So, we're going
  to use the same</span> <span m='2337000'>kind of thing that we did with C.</span>
  <span m='2362000'>OK, so along C3, well, let's see,</span> <span m='2367000'>so
  on C3, y is a function of x, again.</span> <span m='2374000'>And so we are using
  as our variable x, but now x goes down</span> <span m='2380000'>from b to a. So,
  it will be the integral</span> <span m='2385000'>from b to a of M of (x and f2 of
  x) dx.</span> <span m='2391000'>Or, if you prefer, that's negative integral from
  a</span> <span m='2397000'>to b of M of (x and f2 of x) dx. OK, so now if I sum
  all these</span> <span m='2404000'>pieces together, I get that the line integral</span>
  <span m='2410000'>along the closed curve is the integral from a to b of M(x1f1</span>
  <span m='2420000'>of x) dx minus the integral from a to b of M(x1f2 of x) dx.</span>
  <span m='2430000'>So, that's the left hand side. Next, I should try to look at</span>
  <span m='2439000'>my double integral and see if I can make it equal to that.</span>
  <span m='2447000'>So, let's look at the other guy, double integral over R of</span>
  <span m='2458000'>negative MydA. Well, first,</span> <span m='2462000'>I'll take
  the minus sign out. It will make my life a little</span> <span m='2465000'>bit easier.
  And second, so I said I will</span> <span m='2469000'>try to set this up in the
  way that's the most efficient.</span> <span m='2474000'>And, my choice of this kind
  of region means that it's easier to</span> <span m='2480000'>set up dy dx, right?</span>
  <span m='2482000'>So, if I set it up dy dx, then I know for a given value</span>
  <span m='2490000'>of x, y goes from f1 of x to f2 of x.</span> <span m='2496000'>And,
  x goes from a to b, right? Is that OK with everyone?</span> <span m='2509000'>OK,
  so now if I compute the inner integral,</span> <span m='2513000'>well, what do I
  get if I get partial M partial y with respect</span> <span m='2518000'>to y? I'll
  get M back, OK?</span> <span m='2522000'>So -- So, I will get M at the point x f2
  of x minus M at the</span> <span m='2539000'>point x f1 of x. And so, this becomes
  the</span> <span m='2547000'>integral from a to b. I guess that was a minus sign,</span>
  <span m='2555000'>of M of (x1f2 of x) minus M of (x1f1 of x) dx.</span> <span m='2565000'>And
  so, that's the same as up there.</span> <span m='2570000'>And so, that's the end
  of the proof because we've checked that</span> <span m='2574000'>for this special
  case, when we have only an x</span> <span m='2578000'>component and a vertically
  simple region,</span> <span m='2581000'>things work. Then, we can remove the</span>
  <span m='2584000'>assumption that things are vertically simple using this</span>
  <span m='2587000'>second observation. We can just glue the various</span> <span
  m='2590000'>pieces together, and prove it for any region.</span> <span m='2593000'>Then,
  we do same thing with the y component.</span> <span m='2597000'>That's the first
  observation. When we add things together,</span> <span m='2602000'>we get Green's
  theorem in its full generality.</span> <span m='2609000'>OK, so let me finish with
  a cool example.</span> <span m='2619000'>So, there's one place in real life where
  Green's theorem used</span> <span m='2627000'>to be extremely useful. I say used
  to because computers</span> <span m='2631000'>have actually made that obsolete.</span>
  <span m='2633000'>But, so let me show you a picture of this device.</span> <span
  m='2642000'>This is called a planimeter. And what it does is it measures</span>
  <span m='2652000'>areas. So, it used to be that when you</span> <span m='2657000'>were
  an experimental scientist, you would run your chemical or</span> <span m='2663000'>biological
  experiment or whatever.</span> <span m='2667000'>And, you would have all of these
  recording devices.</span> <span m='2669000'>And, the data would go, well, not onto
  a floppy disk or</span> <span m='2672000'>hard disk or whatever because you didn't
  have those at the</span> <span m='2675000'>time. You didn't have a computer in</span>
  <span m='2677000'>your lab. They would go onto a piece of</span> <span m='2679000'>graph
  paper. So, you would have your graph</span> <span m='2682000'>paper, and you would
  have some curve on it.</span> <span m='2686000'>And, very often, you wanted to know,</span>
  <span m='2688000'>what's the total amount of product that you have</span> <span
  m='2691000'>synthesized, or whatever the question might be.</span> <span m='2694000'>It
  might relate with the area under your curve.</span> <span m='2698000'>So, you'd
  say, oh, it's easy. Let's just integrate,</span> <span m='2701000'>except you don't
  have a function.</span> <span m='2702000'>You can put that into calculator.</span>
  <span m='2705000'>The next thing you could do is, well, let's count the little</span>
  <span m='2707000'>squares. But, if you've seen a piece of</span> <span m='2709000'>graph
  paper, that's kind of time-consuming.</span> <span m='2712000'>So, people invented
  these things called planimeters.</span> <span m='2714000'>It's something where there
  is a really heavy thing based at one</span> <span m='2719000'>corner, and there's
  a lot of dials and gauges and everything.</span> <span m='2723000'>And, there's
  one arm that you move.</span> <span m='2725000'>And so, what you do is you take
  the moving arm and you just</span> <span m='2730000'>slide it all around your curve.
  And, you look at one of the</span> <span m='2735000'>dials. And, suddenly what comes,</span>
  <span m='2737000'>as you go around, it gives you complete garbage.</span> <span
  m='2741000'>But when you come back here, that dial suddenly gives you</span> <span
  m='2745000'>the value of the area of this region.</span> <span m='2748000'>So, how
  does it work? This gadget never knows about</span> <span m='2751000'>the region
  inside because you don't take it all over here.</span> <span m='2755000'>You only
  take it along the curve.</span> <span m='2757000'>So, what it does actually is it
  computes a line integral.</span> <span m='2760000'>OK, so it has this system of
  wheels and everything that</span> <span m='2764000'>compute for you the line integral
  along C of,</span> <span m='2768000'>well, it depends on the model. But some of
  them compute the</span> <span m='2771000'>line integral of x dy. Some of them compute
  different</span> <span m='2774000'>line integrals. But, they compute some line</span>
  <span m='2777000'>integral, OK? And, now, if you apply Green's</span> <span m='2781000'>theorem,
  you see that when you have a counterclockwise curve,</span> <span m='2786000'>this
  will be just the area of the region inside.</span> <span m='2791000'>And so, that's
  how it works. I mean, of course,</span> <span m='2794000'>now you use a computer
  and it does the sums.</span> <span m='2796000'>Yes? That costs several thousand</span>
  <span m='2799000'>dollars, possibly more. So, that's why I didn't bring</span> <span
  m='2803000'>one.</span> </p>
type: course
uid: dcbc1462a3cd2379c405327ef53ae39f

---
None