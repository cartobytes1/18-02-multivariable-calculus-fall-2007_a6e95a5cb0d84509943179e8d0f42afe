---
about_this_resource_text: <p><strong>Topics covered:</strong> Flux; normal form of
  Green's theorem</p> <p><strong>Instructor:</strong> Prof. Denis Auroux</p>
course_id: 18-02-multivariable-calculus-fall-2007
embedded_media:
- id: 23.jpg
  parent_uid: fdb9c55ad56c9ffe670681fe45aa1363
  technical_location: https://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-23-flux/23.jpg
  title: 'Lecture 23: Flux'
  type: null
  uid: f707dbc5a7fdcef6e11587806d830147
- id: Video-YouTube-Stream
  media_location: _CdoRiNSrqI
  parent_uid: fdb9c55ad56c9ffe670681fe45aa1363
  title: Video-YouTube-Stream
  type: Video
  uid: 6818010ee1004672c16d4ae7f3ff0fec
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/_CdoRiNSrqI/default.jpg
  parent_uid: fdb9c55ad56c9ffe670681fe45aa1363
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 70bcd1328ba7fa50836b6e5f8ebdf6c5
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id354869122
  parent_uid: fdb9c55ad56c9ffe670681fe45aa1363
  title: Video-iTunes U-MP4
  type: Video
  uid: e907f417b854cf541c1972dd03a9a4c0
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT18.02F07/ocw-18_02-f07-lec23_300k.mp4
  parent_uid: fdb9c55ad56c9ffe670681fe45aa1363
  title: Video-Internet Archive-MP4
  type: Video
  uid: 2a5f67625dd15c9a391d0042f506128c
- id: Video-VideoLecturesnet-Stream
  media_location: http://videolectures.net/mit1802f07_multivariable_calculus/
  parent_uid: fdb9c55ad56c9ffe670681fe45aa1363
  title: Video-VideoLectures.net-Stream
  type: Video
  uid: a4f975c5cbb2f971e749315997b399bd
- id: Thumbnail-OCW-JPG
  parent_uid: fdb9c55ad56c9ffe670681fe45aa1363
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: af465a7ed06b30e78777b09d39abe11d
- id: 3Play-3PlayYouTubeid-MP4
  media_location: _CdoRiNSrqI
  parent_uid: fdb9c55ad56c9ffe670681fe45aa1363
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 19337f067c0403a9865c7a23428ef070
- id: CdoRiNSrqI.srt
  parent_uid: fdb9c55ad56c9ffe670681fe45aa1363
  technical_location: https://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-23-flux/CdoRiNSrqI.srt
  title: 3play caption file
  type: null
  uid: 5ba16bb808c8386b6d0b67cbf9434720
- id: CdoRiNSrqI.pdf
  parent_uid: fdb9c55ad56c9ffe670681fe45aa1363
  technical_location: https://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-23-flux/CdoRiNSrqI.pdf
  title: 3play pdf file
  type: null
  uid: 6b140b816031bd21d6fad9651f650c93
- id: Caption-3Play YouTube id-SRT
  parent_uid: fdb9c55ad56c9ffe670681fe45aa1363
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 54a74f3046564713102443d4987837d5
- id: Transcript-3Play YouTube id-PDF
  parent_uid: fdb9c55ad56c9ffe670681fe45aa1363
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 1c899a706c926b749f2663489b5eabb0
inline_embed_id: 78396448lecture23:flux77060664
layout: video
order_index: null
parent_uid: d4e54c6363f292115697e70de7a59fd1
related_resources_text: <p>Lecture Notes - Week 9 Summary (<a target="_blank" title="Open
  in a new window." href="./resolveuid/14a8493b19c42b8fbbeb9d05b5c0fd52">PDF</a>)&nbsp;</p>
short_url: lecture-23-flux
technical_location: https://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-23-flux
template_type: Tabbed
title: 'Lecture 23: Flux'
transcript: <p><span m='1000'> The following content is provided under a Creative</span>
  <span m='3000'>Commons license. Your support will help MIT</span> <span m='5000'>OpenCourseWare
  continue to offer high quality educational</span> <span m='8000'>resources for free.
  To make a donation or to view</span> <span m='13000'>additional materials from hundreds
  of MIT courses,</span> <span m='18000'>visit MIT OpenCourseWare at ocw.mit.edu.</span>
  <span m='23000'>Today I am going to tell you about flux of a vector field for</span>
  <span m='33000'>a curve. In case you have seen flux in</span> <span m='35000'>physics,
  probably you have seen flux in</span> <span m='37000'>space, and we are going to
  come to</span> <span m='39000'>that in a couple of weeks, but for now we are still
  doing</span> <span m='41000'>everything in the plane. So bear with me if you have</span>
  <span m='44000'>seen a more complicated version of flux.</span> <span m='47000'>We
  are going to do the easy one first.</span> <span m='50000'>What is flux? Well, flux
  is actually another</span> <span m='59000'>kind of line integral. Let's say that
  I have a plane</span> <span m='70000'>curve and a vector field in the plane.</span>
  <span m='78000'>Then the flux of F across a curve C is, by definition,</span> <span
  m='87000'>a line integral, but I will use notation F dot n</span> <span m='95000'>ds.
  I have to explain to you what</span> <span m='98000'>it means, but let me first
  box that because that is the</span> <span m='103000'>important formula to remember.
  That is the definition.</span> <span m='110000'>What does that mean? First, mostly
  I have to tell</span> <span m='115000'>you what this little n is. The notation suggests
  it is a</span> <span m='121000'>normal vector, so what does that mean?</span> <span
  m='125000'>I have a curve in the plane and I have a vector field.</span> <span m='136000'>Let's
  see. The vector field will be yellow</span> <span m='144000'>today. And I will want
  to integrate</span> <span m='148000'>along the curve the dot product of F with the
  normal vector to</span> <span m='153000'>the curve, a unit normal vector to the
  curve.</span> <span m='157000'>That means a vector that is at every point of the
  curve</span> <span m='164000'>perpendicular to the curve and has length one.</span>
  <span m='171000'>N everywhere will be the unit normal vector to the curve C</span>
  <span m='186000'>pointing 90 degrees clockwise from T.</span> <span m='197000'>What
  does that mean? That means I have two normal</span> <span m='199000'>vectors, one
  that is pointing this way, one that is pointing</span> <span m='202000'>that way.
  I have to choose a convention.</span> <span m='204000'>And the convention is that
  the normal vector that I take goes</span> <span m='208000'>to the right of the curve
  as I am traveling along the curve.</span> <span m='212000'>You mentioned that you
  were walking along this curve,</span> <span m='216000'>then you look to your right,
  that is that direction.</span> <span m='220000'>What we will do is just, at every
  point along the curve,</span> <span m='224000'>the dot product between the vector
  field and the normal</span> <span m='228000'>vector. And we will sum that along
  the</span> <span m='231000'>various pieces of the curve. What this notation means
  is</span> <span m='238000'>that if we actually break C into small pieces of length
  delta(s)</span> <span m='249000'>then the flux will be the limit, as the pieces
  become smaller</span> <span m='257000'>and smaller, of the sum of F dot n delta
  S.</span> <span m='265000'>I take each small piece of my curve, I do the dot product</span>
  <span m='269000'>between F and n and I multiply by the length of a piece.</span>
  <span m='272000'>And then I add these together. That is what the line integral</span>
  <span m='275000'>means. Of course that is,</span> <span m='278000'>again, not how
  I will compute it.</span> <span m='281000'>Just to compare this with work, conceptually
  it is similar to</span> <span m='289000'>the line integral we did for work except
  the line integral</span> <span m='300000'>for work -- Work is the line integral
  of F dot dr,</span> <span m='310000'>which is also the line integral of F dot T
  ds.</span> <span m='315000'>That is how we reformulated it. That means we take our
  curve</span> <span m='320000'>and we figure out at each point how big the tangent
  component --</span> <span m='326000'>I guess I should probably take the same vector
  field as before.</span> <span m='333000'>Let's see. My field was pointing more like</span>
  <span m='337000'>that way. What I do at any point is</span> <span m='340000'>project
  F to the tangent direction, I figure out how much</span> <span m='345000'>F is going
  along my curve and then I sum these things</span> <span m='350000'>together. I am
  actually summing -- -- the</span> <span m='362000'>tangential component of my field
  F.</span> <span m='374000'>Roughly-speaking the work measures, you know,</span>
  <span m='377000'>when I move along my curve, how much I am going with or</span>
  <span m='381000'>against F. Flux, on the other hand,</span> <span m='383000'>measures,
  when I go along the curve, roughly how much the</span> <span m='386000'>field is
  going to across the curve.</span> <span m='388000'>Counting positively what goes
  to the right,</span> <span m='391000'>negatively what goes to the left.</span> <span
  m='394000'>Flux is integral F dot n ds, and that one corresponds to</span> <span
  m='405000'>summing the normal component of a vector field.</span> <span m='414000'>But
  apart from that conceptually it is the same kind</span> <span m='417000'>of thing.
  Just the physical</span> <span m='419000'>interpretations will be very different,</span>
  <span m='421000'>but for a mathematician these are two line integrals that you</span>
  <span m='430000'>set up and compute in pretty much the same way.</span> <span m='437000'>Let's
  see. I should probably tell you what</span> <span m='441000'>it means. Why do we
  make this definition?</span> <span m='442000'>What does it correspond to? Well,
  the interpretation for</span> <span m='447000'>work made a lot of sense when F was
  representing a force.</span> <span m='451000'>The line integral was actually the
  work done by the force.</span> <span m='456000'>The interpretation for flux makes
  more sense if you think of</span> <span m='460000'>F as a velocity field. What is
  the interpretation?</span> <span m='470000'>Let's say that for F is a velocity field.</span>
  <span m='475000'>That means I am thinking of some fluid that is moving,</span> <span
  m='480000'>maybe water or something, and it is moving at a certain</span> <span
  m='484000'>speed. And my vector field represents</span> <span m='488000'>how things
  are moving at every point of the plane.</span> <span m='494000'>I claim that flux
  measures how much fluid passes through -- --</span> <span m='511000'>the curve C
  per unit time. If you imagine that maybe you</span> <span m='521000'>have a river
  and you are somehow building a damn here,</span> <span m='525000'>a damn with holes
  in it so that the water still passes through,</span> <span m='528000'>then this
  measures how much water passes through your</span> <span m='533000'>membrane per
  unit time. Let's try to figure out why</span> <span m='537000'>this is true. Why
  does this make sense?</span> <span m='540000'>Let's look at what happens on a small
  portion of our curve C.</span> <span m='547000'>I am zooming in on my curve C. I
  guess I need to zoom further.</span> <span m='561000'>That is a little piece of
  my curve, of length delta S,</span> <span m='566000'>and there is a fluid flow.
  On my picture things are</span> <span m='570000'>flowing to the right. Here I am
  drawing a constant</span> <span m='573000'>vector field because if you zoom in enough
  then your vectors will</span> <span m='578000'>pretty much be the same everywhere.</span>
  <span m='580000'>If you enlarge the picture enough then things will be</span> <span
  m='584000'>pretty much a uniform flow. Now, how much stuff goes</span> <span m='588000'>through
  this little piece of curve per unit time?</span> <span m='591000'>Well, what happens
  over time is the fluid is moving while my</span> <span m='597000'>curve is staying
  the same place so it corresponds to something</span> <span m='604000'>like this.
  I claim that what goes through</span> <span m='609000'>C in unit time is actually
  going to be a parallelogram.</span> <span m='616000'>Here is a better picture. I
  claim that what will be going</span> <span m='621000'>through C is this shaded parallelogram
  to the left of C.</span> <span m='624000'>Let's see. If I move for unit time it</span>
  <span m='632000'>works. That is the stuff that goes</span> <span m='635000'>through
  my curve, for a small portion of curve in</span> <span m='638000'>unit time. And,
  of course,</span> <span m='640000'>I would need to add all of these together to
  get the entire</span> <span m='643000'>curve. Let's try to understand how big</span>
  <span m='647000'>this parallelogram is. To know how big this</span> <span m='650000'>parallelogram
  is I would like to use base times height or</span> <span m='653000'>something like
  that. And maybe I want to actually</span> <span m='656000'>flip my picture so that
  the base and the height make more sense</span> <span m='659000'>to me. Let me actually
  turn it this</span> <span m='664000'>way. And, in case you have trouble</span> <span
  m='670000'>reading the rotated picture, let me redo it on the board.</span> <span
  m='681000'>What passes through a portion of C in unit time is the</span> <span m='691000'>contents
  of a parallelogram whose base is on C.</span> <span m='700000'>So it has length
  delta s. That is a piece of C.</span> <span m='709000'>And the other side is going
  to be given by my velocity vector</span> <span m='726000'>F. And to find the height
  of this</span> <span m='731000'>thing, I need to know what actually the normal component
  of</span> <span m='737000'>this vector is. If I call n the unit normal</span> <span
  m='744000'>vector to the curve then the area is base times height.</span> <span
  m='755000'>The base is delta S and the height is the normal component</span> <span
  m='762000'>of F, so it is F dot n. And so you see that when you</span> <span m='768000'>sum
  these things together you get, what I said,</span> <span m='774000'>flux. Now, if
  you are worried about</span> <span m='776000'>the fact that actually -- If your
  unit time is too long then</span> <span m='780000'>of course things might start
  changing as it flows.</span> <span m='783000'>You have to take the time unit and
  the length unit that are</span> <span m='787000'>sufficiently small so that really
  this approximation where</span> <span m='791000'>C is a straight line and where
  flow is at constant speed are</span> <span m='795000'>valid. You want to take maybe
  a</span> <span m='797000'>segment here that is a few micrometers.</span> <span m='800000'>And
  the time unit might be a few nanoseconds or whatever,</span> <span m='804000'>and
  then it is a good approximation.</span> <span m='808000'>What I mean by per unit
  time is, well, actually,</span> <span m='811000'>that works, but you want to think
  of a really,</span> <span m='815000'>really small time. And then the amount of matter</span>
  <span m='819000'>that passes in that really, really small time is the flux</span>
  <span m='824000'>times the amount of time. Let's be a tiny bit more</span> <span
  m='828000'>careful. And what I am saying is the</span> <span m='830000'>amount of
  stuff that passes through C depends actually on</span> <span m='833000'>whether
  n is going this way or the opposite way.</span> <span m='836000'>Actually, what
  is implicit in this</span> <span m='840000'>explanation is that I am counting positively
  all the</span> <span m='845000'>stuff that flows across C in the direction of n
  and negatively</span> <span m='851000'>what flows in the opposite direction.</span>
  <span m='855000'>What flows to the right of C, well, across C from left to</span>
  <span m='872000'>right is counted positively. While what flows right to left</span>
  <span m='887000'>is counted negatively. So, in fact,</span> <span m='893000'>it
  is the net flow through C per unit time.</span> <span m='900000'>Any questions about
  the definition or the interpretation</span> <span m='906000'>or things like that?
  Yes?</span> <span m='916000'>Well, you can have both not in the same small segment.</span>
  <span m='919000'>But it could be that, well, imagine that my vector</span> <span
  m='924000'>field accidentally goes in the opposite direction then this</span> <span
  m='928000'>part of the curve, while things are flowing to the</span> <span m='932000'>left,
  contributes negatively to flux.</span> <span m='935000'>And here maybe the field
  is tangent so the normal component</span> <span m='939000'>becomes zero. And then
  it becomes positive</span> <span m='942000'>and this part of the curve contributes
  positively.</span> <span m='947000'>For example, if you imagine that you have a</span>
  <span m='951000'>round tank in which the fluid is rotating and you put your dam</span>
  <span m='954000'>just on a diameter across then things are going one way on one</span>
  <span m='957000'>side, the other way on the other</span> <span m='959000'>side,
  and actually it just evens out.</span> <span m='964000'>We don't have complete information.</span>
  <span m='966000'>It is just the total net flux. OK.</span> <span m='973000'>If there
  are no other questions then I guess we will need to</span> <span m='979000'>figure
  out how to compute this guy and how to actually do this</span> <span m='985000'>line
  integral. Well, let's start with a couple</span> <span m='993000'>of easy examples.
  Let's say that C is a circle of</span> <span m='1003000'>radius (a) centered at
  the origin going counterclockwise.</span> <span m='1015000'>And let's say that our
  vector field is xi yj.</span> <span m='1022000'>What does that look like? Remember,
  xi plus yj is a</span> <span m='1029000'>vector field that is pointing radially
  away from the origin.</span> <span m='1035000'>Because at every point it is equal
  to the vector from the</span> <span m='1039000'>origin to that point. Now, if we
  have a circle and</span> <span m='1045000'>let's say we are going counterclockwise.</span>
  <span m='1050000'>Actually, I have a nicer picture.</span> <span m='1052000'>Let
  me do it here. That is my curve and my vector</span> <span m='1068000'>field. And
  the normal vector, see,</span> <span m='1075000'>when you go counterclockwise in
  a closed curve,</span> <span m='1077000'>this convention that a normal vector points
  to the right of</span> <span m='1081000'>curve makes it point out. The usual convention,</span>
  <span m='1084000'>when you take flux for a closed curve, is that you are counting</span>
  <span m='1088000'>the flux going out of the region enclosed by the curve.</span>
  <span m='1091000'>And, of course, if you went clockwise it would</span> <span m='1093000'>be
  the other way around. You choose to do it the way you</span> <span m='1098000'>want,
  but the most common one is to count flux going out of the</span> <span m='1107000'>region.
  Let's see what happens.</span> <span m='1111000'>Well, if I am anywhere on my circle,
  see, the normal vector</span> <span m='1115000'>is sticking straight out of the
  circle.</span> <span m='1118000'>That is a property of the circle that the radial
  direction</span> <span m='1123000'>is perpendicular to the circle. Actually, let
  me complete this</span> <span m='1129000'>picture. If I take a point on the</span>
  <span m='1132000'>circle, I have my normal vector that is pointing straight out
  so</span> <span m='1139000'>it is parallel to F. Along C we know that F is</span>
  <span m='1145000'>parallel to n, so F dot n will be equal to the</span> <span m='1150000'>magnitude
  of F times, well, the magnitude of n,</span> <span m='1156000'>but that is one.
  Let me put it anywhere,</span> <span m='1160000'>but that is the unit normal vector.</span>
  <span m='1163000'>Now, what is the magnitude of this vector field if I am at a</span>
  <span m='1167000'>point x, y? Well, it is square root of x</span> <span m='1169000'>squared
  plus y squared, which is the same as the</span> <span m='1172000'>distance from
  the origin. So if this distance,</span> <span m='1176000'>if this radius is a then
  the magnitude of F will just be a.</span> <span m='1186000'>In fact, F dot n is
  constant, always equal to a.</span> <span m='1191000'>So the line integral will
  be pretty easy because all I have</span> <span m='1197000'>to do is the integral
  of F dot n ds becomes the integral of a ds.</span> <span m='1204000'>(a) is a constant
  so I can take it out.</span> <span m='1207000'>And integral ds is just a length
  of C which is 2pi a,</span> <span m='1216000'>so I will get 2pi a squared. And that
  is positive,</span> <span m='1224000'>as we expected, because stuff is flowing out
  of</span> <span m='1228000'>the circle. Any questions about that?</span> <span m='1236000'>No.
  OK.</span> <span m='1241000'>Just out of curiosity, let's say that we had taken
  our</span> <span m='1245000'>other favorite vector field. Let's say that we had
  the same</span> <span m='1252000'>C, but now the vector field .</span> <span m='1257000'>Remember,
  that one goes counterclockwise around the</span> <span m='1265000'>origin. If you
  remember what we did</span> <span m='1269000'>several times, well, along the circle
  that</span> <span m='1272000'>vector field now is tangent to the circle.</span>
  <span m='1276000'>If it is tangent to the circle it doesn't have any normal</span>
  <span m='1279000'>component. The normal component is zero.</span> <span m='1282000'>Things
  are not flowing into the circle or out of it.</span> <span m='1285000'>They are
  just flowing along the circle around and around so the</span> <span m='1290000'>flux
  will be zero. F now is tangent to C.</span> <span m='1298000'>F dot n is zero and,
  therefore, the flux will be</span> <span m='1311000'>zero. These are examples where
  you</span> <span m='1315000'>can compute things geometrically.</span> <span m='1317000'>And
  I would say, generally speaking,</span> <span m='1320000'>with flux, well, if it
  is a very complicated</span> <span m='1323000'>field then you cannot. But, if a
  field is fairly</span> <span m='1326000'>simple, you should be able to get some</span>
  <span m='1328000'>general feeling for whether your answer should be positive,</span>
  <span m='1331000'>negative or zero just by thinking about which way is my</span>
  <span m='1335000'>flow going. Is it going across the curve</span> <span m='1340000'>one
  way or the other way? Still no questions about these</span> <span m='1352000'>examples?
  The next thing we need to know</span> <span m='1356000'>is how we will actually
  compute these things because here,</span> <span m='1360000'>yeah, it works pretty
  well, but what if you don't have a</span> <span m='1363000'>simple geometric interpretation.
  What if I give you a really</span> <span m='1367000'>complicated curve and then
  you have trouble finding the normal</span> <span m='1370000'>vector? It is going
  to be annoying to</span> <span m='1373000'>set up things this way. Actually, there
  is a better way</span> <span m='1376000'>to do it in coordinates. Just as we do
  work,</span> <span m='1379000'>when we compute this line integral, usually we don't
  do it</span> <span m='1384000'>geometrically like this. Most of the time we just</span>
  <span m='1388000'>integrate M dx plus N dy in coordinates.</span> <span m='1392000'>That
  is a similar way to do it because it is,</span> <span m='1396000'>again, a line
  integral so it should work the same way.</span> <span m='1400000'>Let's try to figure
  that out.</span> <span m='1445000'>How do we do the calculation in coordinates,
  or I should say</span> <span m='1462000'>using components? That is the general method
  of</span> <span m='1469000'>calculation when we don't have something geometric to
  do.</span> <span m='1473000'>Remember, when we were doing things for work we said
  this</span> <span m='1481000'>vector dr, or if you prefer T ds, we said just becomes</span>
  <span m='1489000'>symbolically dx and dy. When you do the line integral</span> <span
  m='1496000'>of F dot dr you get line integral of n dx plus n dy.</span> <span m='1501000'>Now
  let's think for a second about how we would express n ds.</span> <span m='1507000'>Well,
  what is n ds compared to T ds?</span> <span m='1511000'>Well, M is just T rotated
  by 90 degrees, so n ds is T ds rotated</span> <span m='1515000'>by 90 degrees. That
  might sound a little bit</span> <span m='1519000'>outrageous because these are really
  symbolic notations but it</span> <span m='1523000'>works. I am not going to spend
  too</span> <span m='1525000'>much time trying to convince you carefully.</span>
  <span m='1528000'>But if you go back to where we wrote this and how we tried to</span>
  <span m='1533000'>justify this and you work your way through it,</span> <span m='1536000'>you
  will see that n ds can be analyzed the same way.</span> <span m='1542000'>N is T
  rotated 90 degrees clockwise.</span> <span m='1551000'>That tells us that n ds is
  -- How do we rotate a vector by 90</span> <span m='1557000'>degrees? Well, we swept
  the two</span> <span m='1560000'>components and we put a minus sign.</span> <span
  m='1565000'>You have dy and dx. And you have to be careful</span> <span m='1567000'>where
  to put the minus sign. Well, if you are doing it</span> <span m='1571000'>clockwise,
  it is in front of dx.</span> <span m='1586000'>Well, actually, let me just convince
  you</span> <span m='1589000'>quickly. Let's say we have a small piece</span> <span
  m='1592000'>of C. If we do T delta S,</span> <span m='1596000'>that is also vector
  delta r. That is going to be just the</span> <span m='1604000'>vector that goes
  along the curve given by this.</span> <span m='1608000'>Its components will be indeed
  the change in x,</span> <span m='1614000'>delta x, and the change in y, delta y.</span>
  <span m='1620000'>And now, if I want to get n delta S, well,</span> <span m='1627000'>I
  claim now that it is perfectly valid and rigorous to</span> <span m='1635000'>just
  rotate that by 90 degrees. If I want to rotate this by 90</span> <span m='1644000'>degrees
  clockwise then the x component will become the same</span> <span m='1651000'>as
  the old y component. And the y component will be</span> <span m='1656000'>minus
  delta x. Then you take the limit when</span> <span m='1660000'>the segment becomes
  shorter and shorter, and that is how you can</span> <span m='1664000'>justify this.
  That is the key to computing</span> <span m='1667000'>things in practice. It means,
  actually,</span> <span m='1670000'>you already know how to compute line integrals
  for flux.</span> <span m='1675000'>Let me just write it explicitly. Let's say that
  our vector field</span> <span m='1685000'>has two components. And let me just confuse
  you a</span> <span m='1688000'>little bit and not call them M and N for this time
  just to</span> <span m='1692000'>stress the fact that we are doing a different line
  integral.</span> <span m='1696000'>Let me call them P and Q for now.</span> <span
  m='1702000'>Then the line integral of F dot n ds will be the line integral</span>
  <span m='1711000'>of dot product .</span> <span m='1719000'>That will be the integral
  of - Q dx P dy.</span> <span m='1726000'>Well, I am running out of space here.</span>
  <span m='1730000'>It is integral along C of negative Q dx plus P dy.</span> <span
  m='1741000'>And from that point onwards you just do it the usual way.</span> <span
  m='1744000'>Remember, here you have two variables x and y but you are</span> <span
  m='1750000'>integrating along a curve. If you are integrating along a</span> <span
  m='1754000'>curve x and y are related. They depend on each other or</span> <span
  m='1758000'>maybe on some other parameter like T or theta or whatever.</span> <span
  m='1761000'>You express everything in terms of a single variable and then</span>
  <span m='1768000'>you do a usual single integral. Any questions about that?</span>
  <span m='1776000'>I see a lot of confused faces so maybe I shouldn't have called</span>
  <span m='1779000'>my component P and Q.</span> <span m='1804000'>If you prefer,
  if you are really sentimentally</span> <span m='1814000'>attached to M and N then
  this new line integral becomes the</span> <span m='1827000'>integral of - N dx M
  dy. If a problem tells you compute</span> <span m='1835000'>flux instead of saying
  compute work,</span> <span m='1837000'>the only thing you change is instead of doing
  M dx plus N dy</span> <span m='1841000'>you do minus N dx plus M dy. And I am sorry
  to say that I</span> <span m='1845000'>don't have any good way of helping you remember
  which one</span> <span m='1849000'>of the two gets the minus sign, so you just have
  to remember</span> <span m='1852000'>this formula by heart. That is the only way
  I know.</span> <span m='1858000'>Well, you can try to go through this argument again,</span>
  <span m='1864000'>but it is really best if you just remember that formula.</span>
  <span m='1870000'>I am not going to do an example because we already know how to</span>
  <span m='1875000'>do line integrals. Hopefully you will get to see</span> <span
  m='1879000'>one at least in recitation on Monday.</span> <span m='1883000'>That
  is all pretty good. Let me tell you now what if I</span> <span m='1889000'>have
  to compute flux along a closed curve and I don't want to</span> <span m='1895000'>compute
  it? Well, remember in the case of</span> <span m='1899000'>work we had Green's theorem.
  We saw yesterday Green's</span> <span m='1903000'>theorem. Let's us replace a line</span>
  <span m='1905000'>integral along a closed curve by a double integral.</span> <span
  m='1908000'>Well, here it is the same. We have a line integral along a</span> <span
  m='1911000'>curve. If it is a closed curve,</span> <span m='1913000'>we should be
  able to replace it by a double integral.</span> <span m='1917000'>There is a version
  of Green's theorem for flux.</span> <span m='1929000'>And you will see it is not
  scarier than the other one.</span> <span m='1933000'>It is perhaps less scarier
  or perhaps just as scary or just</span> <span m='1938000'>not as scary, depending
  on how you feel about</span> <span m='1942000'>it, but it works pretty much the
  same way.</span> <span m='1946000'>What does Green's theorem for flux say?</span>
  <span m='1950000'>It says if C is a curve that encloses a region R</span> <span
  m='1959000'>counterclockwise and if I have a vector field that is defined</span>
  <span m='1971000'>everywhere, not just on C but also inside,</span> <span m='1976000'>so
  also on R. Well, maybe I should give names</span> <span m='1991000'>to the components.
  If you will forgive me for a</span> <span m='1994000'>second, I will still use P
  and Q for now.</span> <span m='1996000'>You will see why. It is defined and</span>
  <span m='2003000'>differentiable in R. Then I can actually -- --</span> <span m='2010000'>replace
  the line integral for flux by a double integral over R</span> <span m='2020000'>of
  some function. And that function is called the</span> <span m='2027000'>divergence
  of F dA. This is the divergence of F.</span> <span m='2038000'>And I have to define
  for you what this guy is.</span> <span m='2048000'>The divergence of a vector field
  with components P and Q is</span> <span m='2055000'>just P sub x Q sub y. This one
  is actually easier to</span> <span m='2060000'>remember than curl because you just
  take the x component,</span> <span m='2063000'>take its partial with respect to
  x,</span> <span m='2066000'>take the y component, take its partial with respect</span>
  <span m='2069000'>to y and add them together. No signs.</span> <span m='2071000'>No
  switching things around. This one is pretty</span> <span m='2076000'>straightforward.
  The picture again is if I have</span> <span m='2083000'>my curve C going counterclockwise
  around a region</span> <span m='2090000'>R and I want to find the flux of some vector
  field F that is</span> <span m='2098000'>everywhere in here. Maybe some parts of
  C will</span> <span m='2103000'>contribute positively and some parts will contribute</span>
  <span m='2106000'>negatively. Just to reiterate what I said,</span> <span m='2110000'>positively
  here means, because we are going</span> <span m='2114000'>counterclockwise, the
  normal vector points out of</span> <span m='2119000'>the region. This guy here is
  the flux out</span> <span m='2131000'>of R through C. That is the formula.</span>
  <span m='2139000'>Any questions about what the statement says or how to use it</span>
  <span m='2145000'>concretely? No.</span> <span m='2148000'>OK. It is pretty similar
  to Green's</span> <span m='2151000'>theorem for work. Actually, I should say --
  This</span> <span m='2158000'>is called Green's theorem in normal form also.</span>
  <span m='2167000'>Not that the other one is abnormal, but just that the old</span>
  <span m='2177000'>one for work was, you could say,</span> <span m='2183000'>in tangential
  form. That just means,</span> <span m='2188000'>well, Green's theorem, as seen yesterday
  was for the</span> <span m='2192000'>line integral F dot T ds, integrating the tangent</span>
  <span m='2196000'>component of F. The one today is for</span> <span m='2199000'>integrating
  the normal component of F.</span> <span m='2203000'>OK. Let's prove this. Good news.</span>
  <span m='2207000'>It is much easier to prove than the one we did yesterday because</span>
  <span m='2210000'>we are just going to show that it is the same thing just using</span>
  <span m='2213000'>different notations.</span> <span m='2243000'>How do I prove it?
  Well, maybe actually it would</span> <span m='2249000'>help if first, before proving
  it,</span> <span m='2253000'>I actually rewrite what it means in components.</span>
  <span m='2258000'>We said the line integral of F dot n ds is actually the line</span>
  <span m='2266000'>integral of - Q dx P dy. And we want to show that this</span>
  <span m='2274000'>is equal to the double integral of P sub x Q sub y dA.</span>
  <span m='2283000'>This is really one of the features of Green's theorem.</span>
  <span m='2289000'>No matter which form it is, it relates a line integral to a</span>
  <span m='2292000'>double integral. Let's just try to see if we can</span> <span
  m='2296000'>reduce it to the one we had yesterday.</span> <span m='2299000'>Let
  me forget what these things mean physically and just focus</span> <span m='2304000'>on
  the math. On the math it is a line</span> <span m='2306000'>integral of something
  dx plus something dy.</span> <span m='2309000'>Let's call this guy M and let's call
  this guy N.</span> <span m='2316000'>Let M equal negative Q and N equal P.</span>
  <span m='2322000'>Then this guy here becomes integral of M dx plus N dy.</span>
  <span m='2333000'>And I know from yesterday what this is equal to,</span> <span
  m='2337000'>namely using the tangential form of Green's theorem.</span> <span m='2341000'>Green
  for work. This is the double integral of</span> <span m='2345000'>curl of this guy.
  That is Nx minus My dA.</span> <span m='2351000'>But now let's think about what
  this is in terms of M and N.</span> <span m='2355000'>Well, we said that M is negative
  Q so this is negative</span> <span m='2364000'>My. And we said P is the same as
  N,</span> <span m='2369000'>so this is Nx. Just by renaming the</span> <span m='2373000'>components,
  I go from one form to the other one.</span> <span m='2377000'>So it is really the
  same theorem.</span> <span m='2378000'>That's why it is also called Green's theorem.</span>
  <span m='2381000'>But the way we think about it when we use it is different,</span>
  <span m='2385000'>because one of them computes the work done by a force along a</span>
  <span m='2388000'>closed curve, the other one computes the flux</span> <span m='2393000'>maybe
  of a velocity field out of region.</span> <span m='2399000'>Questions? Yes?</span>
  <span m='2410000'>That is correct. If you are trying to compute a</span> <span m='2414000'>line
  integral for flux, wait, where did I put it?</span> <span m='2418000'>A line integral
  for flux just becomes this.</span> <span m='2420000'>And once you are here you know
  how to compute that kind of</span> <span m='2425000'>thing. The double integral
  side does</span> <span m='2427000'>not even have any kind of renaming to do.</span>
  <span m='2429000'>You know how to compute a double integral of a function.</span>
  <span m='2431000'>This is just a particular kind of function that you get out of</span>
  <span m='2435000'>a vector field, but it is like any function.</span> <span m='2438000'>The
  way you would evaluate these double integrals is just</span> <span m='2441000'>the
  usual way. Namely, you have a function of</span> <span m='2446000'>x and y, you
  have a region and you set up the bounds for the</span> <span m='2454000'>isolated
  integral. The way you would evaluate the</span> <span m='2457000'>double integrals
  is really the usual way,</span> <span m='2459000'>by slicing the region and setting
  up the bounds for</span> <span m='2462000'>iterated integrals in dx, dy or dydx
  or maybe rd,</span> <span m='2466000'>rd theta or whatever you want. In fact, in
  terms of computing</span> <span m='2472000'>integrals, we just have two sets of
  skills.</span> <span m='2474000'>One is setting up and evaluating double integrals.</span>
  <span m='2478000'>The other one is setting up and evaluating line integrals.</span>
  <span m='2481000'>And whether these line integrals or double integrals</span> <span
  m='2485000'>are representing work, flux, integral of a curve,</span> <span m='2489000'>whatever,
  the way that we actually</span> <span m='2494000'>compute them is the same. Let's
  do an example.</span> <span m='2500000'>Oh, first. Sorry. This renaming here, see,</span>
  <span m='2507000'>that is why actually I call my components P and Q because the</span>
  <span m='2511000'>argument would have gotten very messy if I had told you now I</span>
  <span m='2514000'>call M ,N and I call N minus M and so on.</span> <span m='2517000'>But,
  now that we are through with this,</span> <span m='2520000'>if you still like M
  and N better,</span> <span m='2523000'>you know, what this says -- The formulation
  of Green's theorem</span> <span m='2535000'>in this language is just integral of
  minus N dx plus M dy</span> <span m='2547000'>is the double integral over R of Mx
  plus Ny dA.</span> <span m='2557000'>Now let's do an example. Let's look at this
  picture</span> <span m='2562000'>again, the flux of xi plus yj out of the circle
  of radius A.</span> <span m='2571000'>We did the calculation directly using geometry,</span>
  <span m='2573000'>and it wasn't all that bad. But let's see what Green's</span>
  <span m='2577000'>theorem does for us here.</span> <span m='2599000'>Example. Let's
  take the same example as</span> <span m='2602000'>last time. F equals xi yj.</span>
  <span m='2608000'>C equals circle of radius a counterclockwise.</span> <span m='2623000'>How
  do we set up Green's theorem.</span> <span m='2626000'>Well, let's first figure
  out the divergence of F.</span> <span m='2637000'>The divergence of this field,
  I take the x component,</span> <span m='2640000'>which is x, and I take its partial
  respect to x.</span> <span m='2643000'>And then I do the same with the y component,
  and I will get one</span> <span m='2648000'>plus one equals two. So, the divergence
  of this</span> <span m='2652000'>field is two. Now, Green's theorem tells us</span>
  <span m='2657000'>that the flux out of this region is going to be the double</span>
  <span m='2665000'>integral of 2 dA. What is R now?</span> <span m='2669000'>Well,
  R is the region enclosed by C.</span> <span m='2671000'>So if C is the circle, R
  is the disk of radius A.</span> <span m='2678000'>Of course, we can compute it,
  but we don't have to because</span> <span m='2682000'>double integral of 2dA is
  just twice the double integral of dA</span> <span m='2686000'>so it is twice the
  area of R. And we know the area of a</span> <span m='2691000'>circle of radius A.
  That is piA2.</span> <span m='2694000'>So, it is 2piA2. That is the same answer
  that we</span> <span m='2701000'>got directly, which is good news.</span> <span
  m='2704000'>Now we can even do better. Let's say that my circle is not</span> <span
  m='2708000'>at the origin. Let's say that it is out here.</span> <span m='2712000'>Well,
  then it becomes harder to calculate the flux directly.</span> <span m='2717000'>And
  it is harder even to guess exactly what will happen because</span> <span m='2721000'>on
  this side here the vector field will go into the region so</span> <span m='2724000'>the
  contribution to flux will be negative here.</span> <span m='2727000'>Here it will
  be positive because it is going out of the</span> <span m='2731000'>region. There
  are positive and negative</span> <span m='2733000'>terms. Well, it looks like positive</span>
  <span m='2735000'>should win because here the vector field is much larger than</span>
  <span m='2738000'>over there. But, short of computing it,</span> <span m='2741000'>we
  won't actually know what it is.</span> <span m='2745000'>If you want to do it by
  direct calculation then you have to</span> <span m='2748000'>parametize this circle
  and figure out what the line</span> <span m='2751000'>integral will be. But if you
  use Green's theorem,</span> <span m='2755000'>well, we never used the fact that
  it is the circle of radius</span> <span m='2760000'>A at the origin. It is true
  actually for any</span> <span m='2763000'>closed curve that the flux out of it is
  going to be twice the</span> <span m='2768000'>area of the region inside. It still
  will be 2piA2 even if</span> <span m='2772000'>my circle is anywhere else in the
  plane.</span> <span m='2776000'>If I had asked you a trick question where do you
  want to</span> <span m='2778000'>place this circle so that that the flux is the
  largest?</span> <span m='2781000'>Well, the answer is it doesn't matter.</span>
  <span m='2788000'>Now, let's just finish quickly by answering a question that</span>
  <span m='2793000'>some of you, I am sure, must have,</span> <span m='2796000'>which
  is what does divergence mean and what does it measure?</span> <span m='2800000'>I
  mean, we said for curl, curl measures how much things</span> <span m='2804000'>are
  rotating somehow. What does divergence mean?</span> <span m='2808000'>Well, the
  answer is divergence measures how much things are</span> <span m='2813000'>diverging.
  Let's be more explicit.</span> <span m='2828000'>Interpretation of divergence. You
  can think of it,</span> <span m='2840000'>you know, what do I want to say first?</span>
  <span m='2843000'>If you take a vector field that is a constant vector field where</span>
  <span m='2848000'>everything just translates then there is no divergence involved</span>
  <span m='2852000'>because the derivatives will be zero.</span> <span m='2854000'>If
  you take the guy that rotates things around you will</span> <span m='2857000'>also
  compute and find zero for divergence.</span> <span m='2860000'>This is not sensitive
  to translation motions where</span> <span m='2863000'>everything moves together
  or to rotation motions,</span> <span m='2866000'>but instead it is sensitive to
  explaining motions.</span> <span m='2871000'>A possible answer is that it measures
  how much the flow is</span> <span m='2884000'>expanding areas. If you imagine this
  flow that</span> <span m='2890000'>we have here on the picture, things are moving
  away from the</span> <span m='2894000'>origin and they fill out the plane.</span>
  <span m='2896000'>If we mention this fluid flowing out there,</span> <span m='2899000'>it
  is occupying more and more space.</span> <span m='2901000'>And so that is what it
  means to have positive divergence.</span> <span m='2904000'>If you took the opposite
  vector field that contracts everything</span> <span m='2908000'>to the origin that
  will have negative divergence.</span> <span m='2911000'>That is a good way to think
  about it if you are thinking of</span> <span m='2914000'>a gas maybe that can expand
  to fill out more volume.</span> <span m='2917000'>If you thinking of water, well,
  water doesn't really</span> <span m='2921000'>shrink or expand. The fact that it
  is taking more</span> <span m='2923000'>and more space actually means that there
  is more and more</span> <span m='2926000'>water. The other way to think about it</span>
  <span m='2931000'>is divergence is the source rate,</span> <span m='2936000'>it
  is the amount of fluid that is being inserted into the</span> <span m='2940000'>system,
  that is being pumped into the</span> <span m='2952000'>system per unit time per
  unit area.</span> <span m='2967000'>What div F equals two here means is that here
  you actually</span> <span m='2971000'>have matter being created or being pumped
  into the system so</span> <span m='2975000'>that you have more and more water filling
  more and more</span> <span m='2979000'>space as it flows. But, actually,</span>
  <span m='2981000'>divergence is not two just at the origin.</span> <span m='2983000'>It
  is two everywhere. So, in fact,</span> <span m='2986000'>to have this you need to
  have a system of pumps that actually is</span> <span m='2989000'>in something water
  absolutely everywhere uniformly.</span> <span m='2992000'>That is the only way to
  do this. I mean if you imagine that you</span> <span m='2995000'>just have one spring
  at the origin then,</span> <span m='2997000'>sure, water will flow out, but as you
  go further and</span> <span m='3000000'>further away it will do so more and more
  slowly.</span> <span m='3002000'>Well, here it is flowing away faster and faster.</span>
  <span m='3004000'>And that means everywhere you are still pumping more water</span>
  <span m='3009000'>into it. So, that is what divergence</span> <span m='3011000'>measures.</span>
  </p>
type: course
uid: fdb9c55ad56c9ffe670681fe45aa1363

---
None