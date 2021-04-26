---
about_this_resource_text: <p><strong>Topics covered:</strong> Differentials; chain
  rule</p> <p><strong>Instructor:</strong> Prof. Denis Auroux</p>
course_id: 18-02-multivariable-calculus-fall-2007
embedded_media:
- id: 11.jpg
  parent_uid: bc05b85a27424235b84faa6d5f6ad9e5
  technical_location: https://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-11-chain-rule/11.jpg
  title: 'Lecture 11: Chain Rule'
  type: null
  uid: 555675701f71a692fc3146b1afa7d48c
- id: Video-YouTube-Stream
  media_location: 7eZVshlT33Q
  parent_uid: bc05b85a27424235b84faa6d5f6ad9e5
  title: Video-YouTube-Stream
  type: Video
  uid: 2abc0fef118bdf52841a315fc45362ef
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/7eZVshlT33Q/default.jpg
  parent_uid: bc05b85a27424235b84faa6d5f6ad9e5
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 2efca23dc66c3cb9c377245bc4098b3d
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id354869122
  parent_uid: bc05b85a27424235b84faa6d5f6ad9e5
  title: Video-iTunes U-MP4
  type: Video
  uid: 82e0a136858edecbb91e75e4d108723b
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT18.02F07/ocw-18_02-f07-lec11_300k.mp4
  parent_uid: bc05b85a27424235b84faa6d5f6ad9e5
  title: Video-Internet Archive-MP4
  type: Video
  uid: 0ce596fdb760f14ac117db456ba8c517
- id: Video-VideoLecturesnet-Stream
  media_location: http://videolectures.net/mit1802f07_multivariable_calculus/
  parent_uid: bc05b85a27424235b84faa6d5f6ad9e5
  title: Video-VideoLectures.net-Stream
  type: Video
  uid: 2ca05e2941fc3e3ac0ef91b60ee21a86
- id: Thumbnail-OCW-JPG
  parent_uid: bc05b85a27424235b84faa6d5f6ad9e5
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: df77ccad77836f6a1fa51f60a3a6efc7
- id: 3Play-3PlayYouTubeid-MP4
  media_location: 7eZVshlT33Q
  parent_uid: bc05b85a27424235b84faa6d5f6ad9e5
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: ec8af1d72fcbf61a866b0c1975418a6d
- id: 7eZVshlT33Q.srt
  parent_uid: bc05b85a27424235b84faa6d5f6ad9e5
  technical_location: https://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-11-chain-rule/7eZVshlT33Q.srt
  title: 3play caption file
  type: null
  uid: a7def73df23403ba34d92eec0273645c
- id: 7eZVshlT33Q.pdf
  parent_uid: bc05b85a27424235b84faa6d5f6ad9e5
  technical_location: https://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-11-chain-rule/7eZVshlT33Q.pdf
  title: 3play pdf file
  type: null
  uid: 54de670bb48e3729141c9f712652badc
- id: Caption-3Play YouTube id-SRT
  parent_uid: bc05b85a27424235b84faa6d5f6ad9e5
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 212be9acc232636ab18e3e5929405e54
- id: Transcript-3Play YouTube id-PDF
  parent_uid: bc05b85a27424235b84faa6d5f6ad9e5
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: d3871639242110b91d9171537789ae2c
inline_embed_id: 91146476lecture11:chainrule34690246
layout: video
order_index: null
parent_uid: d4e54c6363f292115697e70de7a59fd1
related_resources_text: <p>Lecture Notes - Week 5 Summary (<a title="Open in a new
  window." target="_blank" href="./resolveuid/bc9b2e5f89f42650eb46fa9879508923">PDF</a>)</p>
short_url: lecture-11-chain-rule
technical_location: https://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-11-chain-rule
template_type: Tabbed
title: 'Lecture 11: Chain Rule'
transcript: <p><span m='1000'> The following content is provided under a Creative</span>
  <span m='3000'>Commons license. Your support will help MIT</span> <span m='5000'>OpenCourseWare
  continue to offer high quality educational</span> <span m='8000'>resources for free.
  To make a donation or to view</span> <span m='13000'>additional materials from hundreds
  of MIT courses,</span> <span m='18000'>visit MIT OpenCourseWare at ocw.mit.edu.</span>
  <span m='23000'>So far we have learned about partial derivatives and how to</span>
  <span m='27000'>use them to find minima and maxima of functions of two</span> <span
  m='31000'>variables or several variables. And now we are going to try to</span>
  <span m='35000'>study, in more detail, how functions of several</span> <span m='38000'>variables
  behave, how to compete their</span> <span m='41000'>variations. How to estimate
  the variation</span> <span m='44000'>in arbitrary directions. And so for that we
  are going to</span> <span m='50000'>need some more tools actually to study this
  things.</span> <span m='56000'>More tools to study functions.</span> <span m='75000'>Today's
  topic is going to be differentials.</span> <span m='86000'>And, just to motivate
  that, let me remind you about one</span> <span m='94000'>trick that you probably
  know from single variable calculus,</span> <span m='103000'>namely implicit differentiation.</span>
  <span m='108000'>Let's say that you have a function y equals f of x then</span>
  <span m='116000'>you would sometimes write dy equals f prime of x times dx.</span>
  <span m='125000'>And then maybe you would -- We use implicit differentiation to</span>
  <span m='137000'>actually relate infinitesimal changes in y with infinitesimal</span>
  <span m='149000'>changes in x. And one thing we can do with</span> <span m='155000'>that,
  for example, is actually figure out the rate</span> <span m='159000'>of change dy
  by dx, but also the reciprocal dx by</span> <span m='163000'>dy. And so, for example,</span>
  <span m='168000'>let's say that we have y equals inverse sin(x).</span> <span m='178000'>Then
  we can write x equals sin(y).</span> <span m='183000'>And, from there, we can actually
  find out what</span> <span m='188000'>is the derivative of this function if we didn't
  know the</span> <span m='193000'>answer already by writing dx equals cosine y dy.</span>
  <span m='198000'>That tells us that dy over dx is going to be one over cosine</span>
  <span m='208000'>y. And now cosine for relation to</span> <span m='212000'>sine
  is basically one over square root of one minus x^2.</span> <span m='220000'>And
  that is how you find the formula for the derivative of</span> <span m='224000'>the
  inverse sine function. A formula that you probably</span> <span m='230000'>already
  knew, but that is one way to derive</span> <span m='234000'>it. Now we are going
  to use also</span> <span m='237000'>these kinds of notations, dx, dy and so on,</span>
  <span m='239000'>but use them for functions of several variables.</span> <span m='243000'>And,
  of course, we will have to learn what the</span> <span m='245000'>rules of manipulation
  are and what we can do with them.</span> <span m='257000'>The actual name of that
  is the total differential,</span> <span m='260000'>as opposed to the partial derivatives.</span>
  <span m='263000'>The total differential includes all of the various causes that</span>
  <span m='268000'>can change -- Sorry. All the contributions that can</span> <span
  m='273000'>cause the value of your function f to change.</span> <span m='278000'>Namely,
  let's say that you have a function maybe of three</span> <span m='283000'>variables,
  x, y, z,</span> <span m='284000'>then you would write df equals f sub x dx plus
  f sub y dy plus</span> <span m='296000'>f sub z dz. Maybe, just to remind you of</span>
  <span m='302000'>the other notation, partial f over partial x dx</span> <span m='307000'>plus
  partial f over partial y dy plus partial f over partial z</span> <span m='314000'>dz.
  Now, what is this object?</span> <span m='318000'>What are the things on either
  side of this equality?</span> <span m='322000'>Well, they are called differentials.</span>
  <span m='324000'>And they are not numbers, they are not vectors,</span> <span m='326000'>they
  are not matrices, they are a different kind of</span> <span m='329000'>object. These
  things have their own</span> <span m='332000'>rules of manipulations, and we have
  to learn what we</span> <span m='336000'>can do with them. So how do we think about
  them?</span> <span m='340000'>First of all, how do we not think about them?</span>
  <span m='351000'>Here is an important thing to know.</span> <span m='355000'>Important.
  df is not the same thing as</span> <span m='367000'>delta f. That is meant to be
  a number.</span> <span m='372000'>It is going to be a number once you have a small
  variation of x,</span> <span m='376000'>a small variation of y, a small variation
  of z.</span> <span m='379000'>These are numbers. Delta x, delta y and delta z</span>
  <span m='381000'>are actual numbers, and this becomes a number.</span> <span m='384000'>This
  guy actually is not a number.</span> <span m='386000'>You cannot give it a particular
  value.</span> <span m='390000'>All you can do with a differential is express it
  in</span> <span m='393000'>terms of other differentials. In fact, this dx,</span>
  <span m='396000'>dy and dz, well, they are mostly symbols out</span> <span m='398000'>there.
  But if you want to think about</span> <span m='402000'>them, they are the differentials
  of x, y and z.</span> <span m='406000'>In fact, you can think of these differentials
  as placeholders</span> <span m='412000'>where you will put other things. Of course,
  they represent,</span> <span m='417000'>you know, there is this idea of changes
  in x,</span> <span m='422000'>y, z and f. One way that one could explain</span>
  <span m='425000'>it, and I don't really like it, is to say they represent</span>
  <span m='429000'>infinitesimal changes. Another way to say it,</span> <span m='432000'>and
  I think that is probably closer to the truth,</span> <span m='434000'>is that these
  things are somehow placeholders to put</span> <span m='439000'>values and get a
  tangent approximation.</span> <span m='442000'>For example, if I do replace these
  symbols</span> <span m='445000'>by delta x, delta y and delta z numbers then I will
  actually get</span> <span m='450000'>a numerical quantity. And that will be an</span>
  <span m='453000'>approximation formula for delta. It will be the linear</span> <span
  m='459000'>approximation, a tangent plane approximation.</span> <span m='464000'>What
  we can do -- Well, let me start first with maybe</span> <span m='472000'>something
  even before that. The first thing that it does is</span> <span m='480000'>it can
  encode how changes in x, y, z affect the value of f.</span> <span m='490000'>I would
  say that is the most general answer to what is this</span> <span m='495000'>formula,
  what are these differentials.</span> <span m='498000'>It is a relation between x,
  y, z and f.</span> <span m='504000'>And this is a placeholder for small variations,</span>
  <span m='516000'>delta x, delta y and delta z to get an approximation formula.</span>
  <span m='533000'>Which is delta f is approximately equal to fx delta</span> <span
  m='540000'>x fy delta y fz delta z. It is getting cramped,</span> <span m='546000'>but
  I am sure you know what is going on here.</span> <span m='551000'>And observe how
  this one is actually equal while that one is</span> <span m='555000'>approximately
  equal. So they are really not the same.</span> <span m='559000'>Another thing that
  the notation suggests we can do,</span> <span m='562000'>and they claim we can do,
  is divide everything by some</span> <span m='566000'>variable that everybody depends
  on.</span> <span m='569000'>Say, for example, that x, y and z actually depend</span>
  <span m='573000'>on some parameter t then they will vary, at a certain rate,</span>
  <span m='579000'>dx over dt, dy over dt, dz over dt.</span> <span m='582000'>And
  what the differential will tell us then is the rate of</span> <span m='586000'>change
  of f as a function of t, when you plug in these values</span> <span m='591000'>of
  x, y, z, you will get df over dt by</span> <span m='597000'>dividing everything
  by dt in here.</span> <span m='605000'>The first thing we can do is divide by something
  like dt to</span> <span m='621000'>get infinitesimal rate of change.</span> <span
  m='630000'>Well, let me just say rate of change.</span> <span m='643000'>df over
  dt equals f sub x dx over dt plus f sub y dy over dt</span> <span m='652000'>plus
  f sub z dz over dt. And that corresponds to the</span> <span m='660000'>situation
  where x is a function of t, y is a function of t and z</span> <span m='669000'>is
  a function of t. That means you can plug in</span> <span m='674000'>these values
  into f to get, well, the value of f will</span> <span m='678000'>depend on t, and
  then you can find the rate</span> <span m='683000'>of change with t of a value of
  f.</span> <span m='687000'>These are the basic rules. And this is known as the chain</span>
  <span m='695000'>rule. It is one instance of a chain</span> <span m='698000'>rule,
  which tells you when you have a</span> <span m='700000'>function that depends on
  something,</span> <span m='702000'>and that something in turn depends on something
  else,</span> <span m='705000'>how to find the rate of change of a function on the
  new</span> <span m='711000'>variable in terms of the derivatives of a function and</span>
  <span m='716000'>also the dependence between the various variables.</span> <span
  m='721000'>Any questions so far? No.</span> <span m='728000'>OK. A word of warming,</span>
  <span m='731000'>in particular, about what I said up here.</span> <span m='735000'>It
  is kind of unfortunate, but the textbook actually has a</span> <span m='739000'>serious
  mistake on that. I mean they do have a couple of</span> <span m='743000'>formulas
  where they mix a d with a delta, and I warn you not to</span> <span m='749000'>do
  that, please. I mean there are d's and there</span> <span m='752000'>are delta's,
  and basically they don't live in the same world.</span> <span m='754000'>They don't
  see each other. The textbook is lying to you.</span> <span m='773000'>Let's see.
  The first and the second</span> <span m='779000'>claims, I don't really need to
  justify</span> <span m='781000'>because the first one is just stating some general
  principle,</span> <span m='785000'>but I am not making a precise mathematical claim.</span>
  <span m='788000'>The second one, well, we know the approximation</span> <span m='791000'>formula
  already, so I don't need to justify it</span> <span m='794000'>for you. But, on
  the other hand,</span> <span m='796000'>this formula here, I mean, you probably
  have a</span> <span m='800000'>right to expect some reason for why this works.</span>
  <span m='804000'>Why is this valid? After all, I first told you we</span> <span
  m='807000'>have these new mysterious objects.</span> <span m='809000'>And then I
  am telling you we can do that, but I kind of</span> <span m='812000'>pulled it out
  of my hat. I mean I don't have a hat.</span> <span m='824000'>Why is this valid?
  How can I get to this?</span> <span m='833000'>Here is a first attempt of justifying
  how to get there.</span> <span m='846000'>Let's see. Well, we said df is f sub x
  dx</span> <span m='853000'>plus f sub y dy plus f sub z dz. But we know if x is
  a function</span> <span m='865000'>of t then dx is x prime of t dt, dy is y prime
  of t dt,</span> <span m='877000'>dz is z prime of t dt. If we plug these into that</span>
  <span m='887000'>formula, we will get that df is f sub x times x prime t dt plus</span>
  <span m='898000'>f sub y y prime of t dt plus f sub z z prime of t dt.</span> <span
  m='908000'>And now I have a relation between df and dt.</span> <span m='914000'>See,
  I got df equals sometimes times dt.</span> <span m='917000'>That means the rate
  of change of f with respect to t should be</span> <span m='923000'>that coefficient.
  If I divide by dt then I get</span> <span m='938000'>the chain rule. That kind of
  works,</span> <span m='946000'>but that shouldn't be completely satisfactory.</span>
  <span m='949000'>Let's say that you are a true skeptic and you don't believe in</span>
  <span m='953000'>differentials yet then it is maybe not very good that I</span>
  <span m='957000'>actually used more of these differential notations in</span> <span
  m='961000'>deriving the answer. That is actually not how it is</span> <span m='965000'>proved.
  The way in which you prove the</span> <span m='968000'>chain rule is not this way
  because we shouldn't have too</span> <span m='973000'>much trust in differentials
  just yet.</span> <span m='976000'>I mean at the end of today's lecture, yes,</span>
  <span m='978000'>probably we should believe in them,</span> <span m='980000'>but
  so far we should be a little bit reluctant to believe</span> <span m='986000'>these
  kind of strange objects telling us weird things.</span> <span m='992000'>Here is
  a better way to think about it.</span> <span m='999000'>One thing that we have trust
  in so far are approximation</span> <span m='1003000'>formulas. We should have trust
  in them.</span> <span m='1008000'>We should believe that if we change x a little
  bit,</span> <span m='1014000'>if we change y a little bit then we are actually going
  to</span> <span m='1022000'>get a change in f that is approximately given by these</span>
  <span m='1031000'>guys. And this is true for any</span> <span m='1033000'>changes
  in x, y, z,</span> <span m='1034000'>but in particular let's look at the changes
  that we get if we</span> <span m='1040000'>just take these formulas as function
  of time and change time</span> <span m='1046000'>a little bit by delta t. We will
  actually use the</span> <span m='1052000'>changes in x, y, z in a small time delta
  t.</span> <span m='1059000'>Let's divide everybody by delta t.</span> <span m='1067000'>Here
  I am just dividing numbers so I am not actually playing any</span> <span m='1072000'>tricks
  on you. I mean we don't really know</span> <span m='1074000'>what it means to divide
  differentials,</span> <span m='1077000'>but dividing numbers is something we know.</span>
  <span m='1079000'>And now, if I take delta t very small, this guy tends to the</span>
  <span m='1091000'>derivative, df over dt. Remember, the definition of df</span>
  <span m='1099000'>over dt is the limit of this ratio when the time interval</span>
  <span m='1103000'>delta t tends to zero. That means if I choose smaller</span> <span
  m='1108000'>and smaller values of delta t then these ratios of numbers</span> <span
  m='1112000'>will actually tend to some value,</span> <span m='1115000'>and that
  value is the derivative.</span> <span m='1121000'>Similarly, here delta x over delta
  t, when delta t is really</span> <span m='1131000'>small, will tend to the derivative
  dx/dt.</span> <span m='1139000'>And similarly for the others.</span> <span m='1158000'>That
  means, in particular, we take the limit as delta t</span> <span m='1168000'>tends
  to zero and we get df over dt on one side and on the other</span> <span m='1175000'>side
  we get f sub x dx over dt plus f sub y dy over dt plus f</span> <span m='1182000'>sub
  z dz over dt. And the approximation becomes</span> <span m='1186000'>better and
  better. Remember when we write</span> <span m='1189000'>approximately equal that
  means it is not quite the same,</span> <span m='1193000'>but if we take smaller
  variations then actually we will</span> <span m='1197000'>end up with values that
  are closer and closer.</span> <span m='1201000'>When we take the limit, as delta
  t tends to zero,</span> <span m='1204000'>eventually we get an equality.</span>
  <span m='1221000'>I mean mathematicians have more complicated words to justify</span>
  <span m='1224000'>this statement. I will spare them for now,</span> <span m='1228000'>and
  you will see them when you take analysis if you go in that</span> <span m='1236000'>direction.
  Any questions so far?</span> <span m='1242000'>No. OK.</span> <span m='1246000'>Let's
  check this with an example.</span> <span m='1247000'>Let's say that we really don't
  have any faith in these things</span> <span m='1258000'>so let's try to do it. Let's
  say I give you a function</span> <span m='1266000'>that is x ^2 y z. And let's say
  that maybe x will</span> <span m='1274000'>be t, y will be e^t and z will be sin(t).</span>
  <span m='1294000'>What does the chain rule say? Well, the chain rule tells us</span>
  <span m='1300000'>that dw/dt is, we start with partial w over</span> <span m='1306000'>partial
  x, well, what is that?</span> <span m='1311000'>That is 2xy, and maybe I should
  point out</span> <span m='1318000'>that this is w sub x, times dx over dt plus --
  Well,</span> <span m='1328000'>w sub y is x squared times dy over dt plus w sub
  z,</span> <span m='1341000'>which is going to be just one, dz over dt.</span> <span
  m='1348000'>And so now let's plug in the actual values of these things.</span> <span
  m='1353000'>x is t and y is e^t, so that will be 2t e to the t,</span> <span m='1358000'>dx
  over dt is one plus x squared is t squared,</span> <span m='1367000'>dy over dt
  is e over t, plus dz over dt is cosine t.</span> <span m='1380000'>At the end of
  calculation we get 2t e to the t plus t squared</span> <span m='1386000'>e to the
  t plus cosine t. That is what the chain rule</span> <span m='1391000'>tells us.
  How else could we find that?</span> <span m='1396000'>Well, we could just plug in
  values of x, y and z,</span> <span m='1400000'>x plus w is a function of t, and
  take its derivative.</span> <span m='1403000'>Let's do that just for verification.</span>
  <span m='1406000'>It should be exactly the same answer.</span> <span m='1410000'>And,
  in fact, in this case,</span> <span m='1412000'>the two calculations are roughly
  equal in complication.</span> <span m='1415000'>But say that your function of x,
  y, z was much more</span> <span m='1419000'>complicated than that, or maybe you
  actually didn't</span> <span m='1423000'>know a formula for it, you only knew its
  partial</span> <span m='1425000'>derivatives, then you would need to use the</span>
  <span m='1428000'>chain rule. So, sometimes plugging in</span> <span m='1431000'>values
  is easier but not always.</span> <span m='1453000'>Let's just check quickly. The
  other method would be to</span> <span m='1458000'>substitute. W as a function of
  t.</span> <span m='1463000'>Remember w was x^2y z. x was t, so you get t squared,</span>
  <span m='1476000'>y is e to the t, plus z was sine t.</span> <span m='1481000'>dw
  over dt, we know how to take the derivative using single</span> <span m='1487000'>variable
  calculus. Well, we should know.</span> <span m='1490000'>If we don't know then we
  should take a look at 18.01 again.</span> <span m='1495000'>The product rule that
  will be derivative of t squared is 2t</span> <span m='1502000'>times e to the t
  plus t squared time the derivative of e to the</span> <span m='1508000'>t is e to
  the t plus cosine t. And that is the same answer as</span> <span m='1516000'>over
  there. I ended up writing,</span> <span m='1519000'>you know, maybe I wrote slightly
  more here,</span> <span m='1523000'>but actually the amount of calculations really
  was pretty</span> <span m='1528000'>much the same. Any questions about that?</span>
  <span m='1532000'>Yes? What kind of object is w?</span> <span m='1539000'>Well,
  you can think of w as just another variable that is</span> <span m='1543000'>given
  as a function of x, y and z, for example.</span> <span m='1547000'>You would have
  a function of x, y, z defined by this formula,</span> <span m='1551000'>and I call
  it w. I call its value w so that I</span> <span m='1557000'>can substitute t instead
  of x, y, z.</span> <span m='1564000'>Well, let's think of w as a function of three
  variables.</span> <span m='1567000'>And then, when I plug in the dependents of these
  three</span> <span m='1572000'>variables on t, then it becomes just a function</span>
  <span m='1577000'>of t. I mean, really,</span> <span m='1579000'>my w here is pretty
  much what I called f before.</span> <span m='1583000'>There is no major difference
  between the two.</span> <span m='1591000'>Any other questions? No.</span> <span
  m='1598000'>OK. Let's see.</span> <span m='1605000'>Here is an application of what
  we have seen.</span> <span m='1609000'>Let's say that you want to understand actually
  all these</span> <span m='1613000'>rules about taking derivatives in single variable
  calculus.</span> <span m='1617000'>What I showed you at the beginning, and then
  erased,</span> <span m='1620000'>basically justifies how to take the derivative
  of a reciprocal</span> <span m='1624000'>function. And for that you didn't need</span>
  <span m='1626000'>multivariable calculus. But let's try to justify the</span> <span
  m='1630000'>product rule, for example,</span> <span m='1632000'>for the derivative.
  An application of this actually</span> <span m='1641000'>is to justify the product
  and quotient rules.</span> <span m='1651000'>Let's think, for example,</span> <span
  m='1653000'>of a function of two variables, u and v, that is just the</span> <span
  m='1659000'>product uv. And let's say that u and v are</span> <span m='1664000'>actually
  functions of one variable t.</span> <span m='1668000'>Then, well, d of uv over dt
  is given by the chain rule applied</span> <span m='1680000'>to f. This is df over
  dt.</span> <span m='1684000'>So df over dt should be f sub q du over dt plus f sub
  v plus dv</span> <span m='1695000'>over dt. But now what is the partial of</span>
  <span m='1699000'>f with respect to u? It is v.</span> <span m='1703000'>That is
  v du over dt. And partial of f with respect</span> <span m='1711000'>to v is going
  to be just u, dv over dt.</span> <span m='1718000'>So you get back the usual product
  rule.</span> <span m='1722000'>That is a slightly complicated way of deriving it,</span>
  <span m='1726000'>but that is a valid way of understanding how to take the</span>
  <span m='1730000'>derivative of a product by thinking of the product first as</span>
  <span m='1734000'>a function of variables, which are u and v.</span> <span m='1737000'>And
  then say, oh, but u and v were actually</span> <span m='1740000'>functions of a
  variable t. And then you do the</span> <span m='1743000'>differentiation in two
  stages using the chain rule.</span> <span m='1748000'>Similarly, you can do the
  quotient rule just for practice.</span> <span m='1756000'>If I give you the function
  g equals u of v.</span> <span m='1761000'>Right now I am thinking of it as a function
  of two variables,</span> <span m='1765000'>u and v. U and v themselves are actually</span>
  <span m='1769000'>going to be functions of t. Then, well, dg over dt is going</span>
  <span m='1779000'>to be partial g, partial u.</span> <span m='1784000'>How much
  is that? How much is partial g,</span> <span m='1788000'>partial u? One over v times
  du over dt</span> <span m='1793000'>plus -- Well, next we need to have partial g</span>
  <span m='1798000'>over partial v. Well, what is the derivative of</span> <span m='1801000'>this
  with respect to v? Here we need to know how to</span> <span m='1804000'>differentiate
  the inverse. It is minus u over v squared</span> <span m='1811000'>times dv over
  dt. And that is actually the usual</span> <span m='1820000'>quotient rule just written
  in a slightly different way.</span> <span m='1828000'>I mean, just in case you really
  want to see it,</span> <span m='1830000'>if you clear denominators for v squared
  then you will see</span> <span m='1836000'>basically u prime times v minus v prime
  times u.</span> <span m='1885000'>Now let's go to something even more crazy.</span>
  <span m='1892000'>I claim we can do chain rules with more variables.</span> <span
  m='1905000'>Let's say that I have a quantity.</span> <span m='1910000'>Let's call
  it w for now. Let's say I have quantity w as</span> <span m='1915000'>a function
  of say variables x and y.</span> <span m='1918000'>And so in the previous setup
  x and y depended on some</span> <span m='1922000'>parameters t. But, actually,</span>
  <span m='1924000'>let's now look at the case where x and y themselves are</span>
  <span m='1927000'>functions of several variables. Let's say of two more variables.</span>
  <span m='1930000'>Let's call them u and v. I am going to stay with these</span>
  <span m='1945000'>abstract letters, but if it bothers you,</span> <span m='1947000'>if
  it sounds completely unmotivated think about it maybe</span> <span m='1951000'>in
  terms of something you might now.</span> <span m='1953000'>Say, polar coordinates.
  Let's say that I have a</span> <span m='1956000'>function but is defined in terms
  of the polar coordinate</span> <span m='1960000'>variables on theta. And then I
  know I want to</span> <span m='1963000'>switch to usual coordinates x and y.</span>
  <span m='1965000'>Or, the other way around, I have a function of x and y</span>
  <span m='1969000'>and I want to express it in terms of the polar coordinates r</span>
  <span m='1973000'>and theta. Then I would want to know maybe</span> <span m='1977000'>how
  the derivatives, with respect to the various</span> <span m='1982000'>sets of variables,
  related to each other.</span> <span m='1987000'>One way I could do it is, of course,</span>
  <span m='1990000'>to say now if I plug the formula for x and the formula</span>
  <span m='1996000'>for y into the formula for f then w becomes a function of u</span>
  <span m='2003000'>and v, and it can try to take partial</span> <span m='2007000'>derivatives.
  If I have explicit formulas,</span> <span m='2009000'>well, that could work. But
  maybe the formulas are</span> <span m='2012000'>complicated. Typically, if I switch
  between</span> <span m='2015000'>rectangular and polar coordinates,</span> <span
  m='2017000'>there might be inverse trig, there might be maybe arctangent</span>
  <span m='2021000'>to express the polar angle in terms of x and y.</span> <span m='2025000'>And
  when I don't really want to actually substitute arctangents</span> <span m='2031000'>everywhere,
  maybe I would rather deal with the derivatives.</span> <span m='2036000'>How do
  I do that? The question is what are</span> <span m='2043000'>partial w over partial
  u and partial w over partial v in</span> <span m='2051000'>terms of, let's see,
  what do we need to know to</span> <span m='2057000'>understand that? Well, probably
  we should know</span> <span m='2062000'>how w depends on x and y. If we don't know
  that then we</span> <span m='2068000'>are probably toast. Partial w over partial
  x,</span> <span m='2072000'>partial w over partial y should be required.</span>
  <span m='2076000'>What else should we know? Well, it would probably help to</span>
  <span m='2079000'>know how x and y depend on u and v.</span> <span m='2082000'>If
  we don't know that then we don't really know how to do it.</span> <span m='2086000'>We
  need also x sub u, x sub v, y sub u,</span> <span m='2095000'>y sub v. We have a
  lot of partials in</span> <span m='2100000'>there. Well, let's see how we can do</span>
  <span m='2107000'>that. Let's start by writing dw.</span> <span m='2113000'>We know
  that dw is partial f, well, I don't know why I have</span> <span m='2119000'>two
  names, w and f. I mean w and f are really the</span> <span m='2125000'>same thing
  here, but let's say f sub x dx plus f</span> <span m='2130000'>sub y dy. So far
  that is our new friend,</span> <span m='2135000'>the differential. Now what do we
  want to do with</span> <span m='2139000'>it? Well, we would like to get rid</span>
  <span m='2142000'>of dx and dy because we like to express things in terms of,</span>
  <span m='2147000'>you know, the question we are asking ourselves is let's say</span>
  <span m='2150000'>that I change u a little bit, how does w change?</span> <span
  m='2155000'>Of course, what happens, if I change u a little bit,</span> <span m='2158000'>is
  y and y will change. How do they change?</span> <span m='2161000'>Well, that is
  given to me by the differential.</span> <span m='2165000'>dx is going to be, well,
  I can use the</span> <span m='2173000'>differential again. Well, x is a function
  of u and</span> <span m='2179000'>v. That will be x sub u times du</span> <span
  m='2184000'>plus x sub v times dv. That is, again,</span> <span m='2188000'>taking
  the differential of a function of two variables.</span> <span m='2191000'>Does that
  make sense? And then we have the other guy,</span> <span m='2197000'>f sub y times,
  what is dy?</span> <span m='2199000'>Well, similarly dy is y sub u du plus y sub
  v dv.</span> <span m='2209000'>And now we have a relation between dw and du and
  dv.</span> <span m='2214000'>We are expressing how w reacts to changes in u and
  v,</span> <span m='2220000'>which was our goal. Now, let's actually collect</span>
  <span m='2224000'>terms so that we see it a bit better.</span> <span m='2228000'>It
  is going to be f sub x times x sub u times f sub y times y</span> <span m='2239000'>sub
  u du plus f sub x, x sub v plus f sub y y sub v</span> <span m='2248000'>dv. Now
  we have dw equals something</span> <span m='2252000'>du plus something dv. Well,
  the coefficient here has</span> <span m='2258000'>to be partial f over partial u.
  What else could it be?</span> <span m='2264000'>That's the rate of change of w with
  respect to u if I forget</span> <span m='2269000'>what happens when I change v.
  That is the definition of a</span> <span m='2274000'>partial. Similarly, this one
  has to be</span> <span m='2278000'>partial f over partial v. That is because it
  is the rate</span> <span m='2284000'>of change with respect to v, if I keep u constant,</span>
  <span m='2289000'>so that these guys are completely ignored.</span> <span m='2293000'>Now
  you see how the total differential accounts for,</span> <span m='2296000'>somehow,
  all the partial derivatives that come as</span> <span m='2301000'>coefficients of
  the individual variables in these expressions.</span> <span m='2307000'>Let me maybe
  rewrite these formulas in a more visible way</span> <span m='2313000'>and then re-explain
  them to you. Here is the chain rule for this</span> <span m='2320000'>situation,
  with two intermediate variables and two variables that</span> <span m='2326000'>you
  express these in terms of. In our setting,</span> <span m='2330000'>we get partial
  f over partial u equals partial f over partial x</span> <span m='2336000'>time partial
  x over partial u plus partial f over partial y</span> <span m='2342000'>times partial
  y over partial u. And the other one,</span> <span m='2348000'>the same thing with
  v instead of u,</span> <span m='2355000'>partial f over partial x times partial
  x over partial v plus</span> <span m='2362000'>partial f over partial u partial
  y over partial v.</span> <span m='2368000'>I have to explain various things about
  these formulas</span> <span m='2371000'>because they look complicated. And, actually,</span>
  <span m='2374000'>they are not that complicated. A couple of things to know.</span>
  <span m='2379000'>The first thing, how do we remember a formula</span> <span m='2382000'>like
  that? Well, that is easy.</span> <span m='2384000'>We want to know how f depends
  on u.</span> <span m='2387000'>Well, what does f depend on? It depends on x and
  y.</span> <span m='2391000'>So we will put partial f over partial x and partial
  f over</span> <span m='2395000'>partial y. Now, x and y, why are they here?</span>
  <span m='2399000'>Well, they are here because they actually depend on u as</span>
  <span m='2401000'>well. How does x depend on u?</span> <span m='2404000'>Well, the
  answer is partial x over partial u.</span> <span m='2406000'>How does y depend on
  u? The answer is partial y over</span> <span m='2410000'>partial u. See, the structure
  of this</span> <span m='2412000'>formula is simple. To find the partial of f with</span>
  <span m='2416000'>respect to some new variable you use the partials with respect
  to</span> <span m='2420000'>the variables that f was initially defined in terms
  of x</span> <span m='2424000'>and y. And you multiply them by the</span> <span m='2428000'>partials
  of x and y in terms of the new variable that you want</span> <span m='2433000'>to
  look at, v here, and you sum these things</span> <span m='2437000'>together. That
  is the structure of the</span> <span m='2440000'>formula. Why does it work?</span>
  <span m='2442000'>Well, let me explain it to you in a slightly different</span>
  <span m='2445000'>language. This asks us how does f change</span> <span m='2449000'>if
  I change u a little bit? Well, why would f change if u</span> <span m='2454000'>changes
  a little bit? Well, it would change because f</span> <span m='2457000'>actually
  depends on x and y and x and y depend on u.</span> <span m='2460000'>If I change
  u, how quickly does x change?</span> <span m='2463000'>Well, the answer is partial
  x over partial u.</span> <span m='2466000'>And now, if I change x at this rate,
  how does that have to</span> <span m='2469000'>change? Well, the answer is partial
  f</span> <span m='2473000'>over partial x times this guy. Well, at the same time,</span>
  <span m='2477000'>y is also changing. How fast is y changing if I</span> <span m='2481000'>change
  u? Well, at the rate of partial y</span> <span m='2484000'>over partial u. But now
  if I change this how</span> <span m='2487000'>does f change? Well, the rate of change
  is</span> <span m='2490000'>partial f over partial y. The product is the effect
  of</span> <span m='2494000'>how you change it, changing u, and therefore</span>
  <span m='2497000'>changing f. Now, what happens in real life,</span> <span m='2500000'>if
  I change u a little bit? Well, both x and y change at</span> <span m='2503000'>the
  same time. So how does f change?</span> <span m='2506000'>Well, it is the sum of
  the two effects.</span> <span m='2510000'>Does that make sense? Good.</span> <span
  m='2514000'>Of course, if f depends on more variables then you just have</span>
  <span m='2520000'>more terms in here. OK.</span> <span m='2522000'>Here is another
  thing that may be a little bit confusing.</span> <span m='2525000'>What is tempting?
  Well, what is tempting here</span> <span m='2529000'>would be to simplify these
  formulas by removing these</span> <span m='2532000'>partial x's. Let's simplify
  by partial x.</span> <span m='2535000'>Let's simplify by partial y. We get partial
  f over partial u</span> <span m='2538000'>equals partial f over partial u plus partial
  f over partial u.</span> <span m='2541000'>Something is not working properly.</span>
  <span m='2545000'>Why doesn't it work? The answer is precisely because</span> <span
  m='2548000'>these are partial derivatives. These are not total derivatives.</span>
  <span m='2552000'>And so you cannot simplify them in that way.</span> <span m='2556000'>And
  that is actually the reason why we use this curly d rather</span> <span m='2559000'>than
  a straight d. It is to remind us,</span> <span m='2561000'>beware, there are these
  simplifications that we can do</span> <span m='2564000'>with straight d's that are
  not legal here.</span> <span m='2567000'>Somehow, when you have a partial derivative,</span>
  <span m='2572000'>you must resist the urge of simplifying things.</span> <span m='2577000'>No
  simplifications in here. That is the simplest formula</span> <span m='2582000'>you
  can get. Any questions at this point?</span> <span m='2590000'>No. Yes?</span> <span
  m='2601000'>When would you use this and what does it describe?</span> <span m='2603000'>Well,
  it is basically when you have a function given in terms</span> <span m='2606000'>of
  a certain set of variables because maybe there is a simply</span> <span m='2609000'>expression
  in terms of those variables.</span> <span m='2611000'>But ultimately what you care
  about is not those variables,</span> <span m='2615000'>z and y, but another set
  of variables, here u and v.</span> <span m='2619000'>So x and y are giving you a
  nice formula for f,</span> <span m='2622000'>but actually the relevant variables
  for your problem are u</span> <span m='2626000'>and v. And you know x and y are</span>
  <span m='2628000'>related to u and v. So, of course,</span> <span m='2630000'>what
  you could do is plug the formulas the way that we did</span> <span m='2633000'>substituting.
  But maybe that will give you</span> <span m='2635000'>very complicated expressions.
  And maybe it is actually easier</span> <span m='2639000'>to just work with the derivates.
  The important claim here is</span> <span m='2642000'>basically we don't need to
  know the actual formulas.</span> <span m='2645000'>All we need to know are the rate
  of changes.</span> <span m='2647000'>If we know all these rates of change then we
  know how to take</span> <span m='2651000'>these derivatives without actually having
  to plug in</span> <span m='2654000'>values. Yes?</span> <span m='2662000'>Yes, you
  could certain do the same things in terms of t.</span> <span m='2665000'>If x and
  y were functions of t instead of being functions of u</span> <span m='2669000'>and
  v then it would be the same thing.</span> <span m='2671000'>And you would have the
  same formulas that I had,</span> <span m='2674000'>well, over there I still have
  it.</span> <span m='2677000'>Why does that one have straight d's?</span> <span m='2679000'>Well,
  the answer is I could put curly d's if I wanted,</span> <span m='2682000'>but I
  end up with a function of a single variable.</span> <span m='2685000'>If you have
  a single variable then the partial,</span> <span m='2688000'>with respect to that
  variable, is the same thing as the usual</span> <span m='2690000'>derivative. We
  don't actually need to worry</span> <span m='2693000'>about curly in that case.
  But that one is indeed special</span> <span m='2697000'>case of this one where instead
  of x and y depending on two</span> <span m='2700000'>variables, u and v, they depend
  on a single</span> <span m='2703000'>variable t. Now, of course,</span> <span m='2704000'>you
  can call variables any name you want.</span> <span m='2706000'>It doesn't matter.
  This is just a slight</span> <span m='2712000'>generalization of that. Well, not
  quite because here I</span> <span m='2716000'>also had a z. See, I am trying to
  just</span> <span m='2718000'>confuse you by giving you functions that depend on
  various</span> <span m='2721000'>numbers of variables. If you have a function of
  30</span> <span m='2725000'>variables, things work the same way, just longer,</span>
  <span m='2728000'>and you are going to run out of letters in the alphabet before</span>
  <span m='2733000'>the end. Any other questions?</span> <span m='2738000'>No. What?</span>
  <span m='2743000'>Yes? If u and v themselves depended</span> <span m='2751000'>on
  another variable then you would continue with your chain</span> <span m='2755000'>rules.
  Maybe you would know to express</span> <span m='2758000'>partial x over partial
  u in terms using that chain rule.</span> <span m='2762000'>Sorry. If u and v are
  dependent on yet</span> <span m='2765000'>another variable then you could get the
  derivative with respect</span> <span m='2768000'>to that using first the chain rule
  to pass from u v to that</span> <span m='2771000'>new variable, and then you would
  plug in</span> <span m='2774000'>these formulas for partials of f with respect to
  u and v.</span> <span m='2777000'>In fact, if you have several substitutions to
  do,</span> <span m='2779000'>you can always arrange to use one chain rule at a time.</span>
  <span m='2781000'>You just have to do them in sequence.</span> <span m='2785000'>That's
  why we don't actually learn that, but you can just do</span> <span m='2788000'>it
  be repeating the process. I mean, probably at that stage,</span> <span m='2792000'>the
  easiest to not get confused actually is to manipulate</span> <span m='2795000'>differentials
  because that is probably easier.</span> <span m='2798000'>Yes? Curly f does not
  exist.</span> <span m='2807000'>That's easy. Curly f makes no sense by</span> <span
  m='2810000'>itself. It doesn't exist alone.</span> <span m='2812000'>What exists
  is only curly df over curly d some variable.</span> <span m='2818000'>And then that
  accounts only for the rate of change with respect</span> <span m='2822000'>to that
  variable leaving the others fixed,</span> <span m='2825000'>while straight df is
  somehow a total variation of f.</span> <span m='2831000'>It accounts for all of
  the partial derivatives and their</span> <span m='2836000'>combined effects. OK.
  Any more questions? No.</span> <span m='2845000'>Let me just finish up very quickly
  by telling you again one</span> <span m='2849000'>example where completely you might
  want to do this.</span> <span m='2853000'>You have a function that you want to switch
  between</span> <span m='2860000'>rectangular and polar coordinates.</span> <span
  m='2865000'>To make things a little bit concrete.</span> <span m='2868000'>If you
  have polar coordinates that means in the plane,</span> <span m='2875000'>instead
  of using x and y, you will use coordinates r,</span> <span m='2880000'>distance
  to the origin, and theta, the angles from the</span> <span m='2885000'>x-axis. The
  change of variables for</span> <span m='2888000'>that is x equals r cosine theta
  and y equals r sine theta.</span> <span m='2894000'>And so that means if you have
  a function f that depends on x and</span> <span m='2901000'>y, in fact, you can
  plug these in as a function of r and theta.</span> <span m='2909000'>Then you can
  ask yourself, well, what is partial f over</span> <span m='2914000'>partial r? And
  that is going to be,</span> <span m='2917000'>well, you want to take partial f over
  partial x times partial x</span> <span m='2922000'>partial r plus partial f over
  partial y times partial y over</span> <span m='2928000'>partial r. That will end
  up being actually</span> <span m='2933000'>f sub x times cosine theta plus f sub
  y times sine theta.</span> <span m='2939000'>And you can do the same thing to find
  partial f,</span> <span m='2942000'>partial theta. And so you can express</span>
  <span m='2945000'>derivatives either in terms of x, y or in terms of r and theta</span>
  <span m='2950000'>with simple relations between them.</span> <span m='2953000'>And
  the one last thing I should say.</span> <span m='2960000'>On Thursday we will learn
  about more tricks we can play with</span> <span m='2963000'>variations of functions.
  And one that is important,</span> <span m='2967000'>because you need to know it
  actually to do the p-set,</span> <span m='2969000'>is the gradient vector. The gradient
  vector is simply a</span> <span m='2978000'>vector. You use this downward pointing</span>
  <span m='2981000'>triangle as the notation for the gradient.</span> <span m='2984000'>It
  is simply is a vector whose components are the partial</span> <span m='2989000'>derivatives
  of a function. I mean, in a way,</span> <span m='2993000'>you can think of a differential
  as a way to package partial</span> <span m='2996000'>derivatives together into some
  weird object.</span> <span m='2999000'>Well, the gradient is also a way to package
  partials</span> <span m='3001000'>together. We will see on Thursday what it</span>
  <span m='3004000'>is good for, but some of the problems on the p-set use it.</span>
  </p>
type: course
uid: bc05b85a27424235b84faa6d5f6ad9e5

---
None