---
about_this_resource_text: <p><strong>Topics covered:</strong> Lagrange multipliers</p>
  <p><strong>Instructor:</strong> Prof. Denis Auroux</p>
course_id: 18-02-multivariable-calculus-fall-2007
embedded_media:
- id: 13.jpg
  parent_uid: 776156be63c924038a700b336c8ac82a
  technical_location: https://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-13-lagrange-multipliers/13.jpg
  title: 'Lecture 13: Lagrange Multipliers'
  type: null
  uid: c0f4d81d06aa83f7130104dbd7b166a2
- id: Video-YouTube-Stream
  media_location: 15HVevXRsBA
  parent_uid: 776156be63c924038a700b336c8ac82a
  title: Video-YouTube-Stream
  type: Video
  uid: b9a184b3395c1e7fb43d93d936b766a1
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/15HVevXRsBA/default.jpg
  parent_uid: 776156be63c924038a700b336c8ac82a
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 3e93971bfba466be37feeccba561cd97
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id354869122
  parent_uid: 776156be63c924038a700b336c8ac82a
  title: Video-iTunes U-MP4
  type: Video
  uid: 1dce0dc8feef10ef1605b45d0d11c6a8
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT18.02F07/ocw-18_02-f07-lec13_300k.mp4
  parent_uid: 776156be63c924038a700b336c8ac82a
  title: Video-Internet Archive-MP4
  type: Video
  uid: cf9068144e02c9d99d7d69cb5d1f3ce9
- id: Video-VideoLecturesnet-Stream
  media_location: http://videolectures.net/mit1802f07_multivariable_calculus/
  parent_uid: 776156be63c924038a700b336c8ac82a
  title: Video-VideoLectures.net-Stream
  type: Video
  uid: 4944e9f7ce62e4c69c4660cd3952a328
- id: Thumbnail-OCW-JPG
  parent_uid: 776156be63c924038a700b336c8ac82a
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: 7130c49163da5e5c7c139dfc6bbfd1ea
- id: 3Play-3PlayYouTubeid-MP4
  media_location: 15HVevXRsBA
  parent_uid: 776156be63c924038a700b336c8ac82a
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 64db0c316ab5f1e51c8ae9c58c49126e
- id: 15HVevXRsBA.srt
  parent_uid: 776156be63c924038a700b336c8ac82a
  technical_location: https://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-13-lagrange-multipliers/15HVevXRsBA.srt
  title: 3play caption file
  type: null
  uid: ede073bd95ee680569e4c219f1f7bb16
- id: 15HVevXRsBA.pdf
  parent_uid: 776156be63c924038a700b336c8ac82a
  technical_location: https://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-13-lagrange-multipliers/15HVevXRsBA.pdf
  title: 3play pdf file
  type: null
  uid: a45ade1ebf51f5fbdda72a1de1915058
- id: Caption-3Play YouTube id-SRT
  parent_uid: 776156be63c924038a700b336c8ac82a
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: 312e3d954188f9d1400b8edd504ba3ee
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 776156be63c924038a700b336c8ac82a
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 36ad07ae5304410919450e3ea7d030cc
inline_embed_id: 42254466lecture13:lagrangemultipliers14435458
layout: video
order_index: null
parent_uid: d4e54c6363f292115697e70de7a59fd1
related_resources_text: <p>Lecture Notes - Week 5 Summary (<a title="Open in a new
  window." target="_blank" href="./resolveuid/bc9b2e5f89f42650eb46fa9879508923">PDF</a>)&nbsp;</p>
short_url: lecture-13-lagrange-multipliers
technical_location: https://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-13-lagrange-multipliers
template_type: Tabbed
title: 'Lecture 13: Lagrange Multipliers'
transcript: <p><span m='1000'>The following content is provided under a Creative</span>
  <span m='3000'>Commons license. Your support will help MIT</span> <span m='5000'>OpenCourseWare
  continue to offer high quality educational</span> <span m='8000'>resources for free.
  To make a donation or to view</span> <span m='13000'>additional materials from hundreds
  of MIT courses,</span> <span m='18000'>visit MIT OpenCourseWare at ocw.mit.edu.</span>
  </p><p><span m='25000'>Last time we saw things about gradients and directional</span>
  <span m='29000'>derivatives. Before that we studied how to</span> <span m='32000'>look
  for minima and maxima of functions of several variables.</span> </p><p><span m='37000'>And
  today we are going to look again at min/max problems but in</span> <span m='41000'>a
  different setting, namely, one for variables that</span> <span m='45000'>are not
  independent. And so what we will see is you</span> <span m='49000'>may have heard
  of Lagrange multipliers.</span> </p><p><span m='52000'>And this is the one point
  in the term when I can shine with</span> <span m='59000'>my French accent and say
  Lagrange's name properly.</span> </p><p><span m='65000'>OK. What are Lagrange multipliers</span>
  <span m='68000'>about? Well, the goal is to minimize</span> <span m='73000'>or maximize
  a function of several variables.</span> </p><p><span m='79000'>Let's say, for example,
  f of x, y, z,</span> <span m='82000'>but where these variables are no longer independent.</span>
  </p><p><span m='101000'>They are not independent. That means that there is a</span>
  <span m='103000'>relation between them. The relation is maybe some</span> <span
  m='107000'>equation of the form g of x, y, z equals some constant.</span> </p><p><span
  m='112000'>You take the relation between x, y, z, you call that g and</span> <span
  m='117000'>that gives you the constraint. And your goal is to minimize f</span>
  <span m='122000'>only of those values of x, y, z that satisfy the</span> <span m='125000'>constraint.
  What is one way to do that?</span> </p><p><span m='127000'>Well, one to do that,
  if the constraint is very</span> <span m='130000'>simple, we can maybe solve for
  one of the variables.</span> </p><p><span m='134000'>Maybe we can solve this equation
  for one of the</span> <span m='137000'>variables, plug it back into f, and then
  we have a usual</span> <span m='141000'>min/max problem that we have seen how to
  do.</span> </p><p><span m='145000'>The problem is sometimes you cannot actually
  solve for x,</span> <span m='148000'>y, z in here because this condition is too
  complicated and</span> <span m='151000'>then we need a new method. That is what
  we are going to do.</span> </p><p><span m='158000'>Why would we care about that?
  Well, one example is actually</span> <span m='161000'>in physics. Maybe you have
  seen in</span> <span m='163000'>thermodynamics that you study quantities about gases,</span>
  <span m='167000'>and those quantities that involve pressure,</span> <span m='170000'>volume
  and temperature. And pressure,</span> <span m='173000'>volume and temperature are
  not independent of each other.</span> </p><p><span m='176000'>I mean you know probably
  the equation PV = NRT.</span> </p><p><span m='179000'>And, of course, there you
  could actually solve</span> <span m='181000'>to express things in terms of one or
  the other.</span> </p><p><span m='183000'>But sometimes it is more convenient to
  keep all three</span> <span m='187000'>variables but treat them as constrained.</span>
  </p><p><span m='189000'>It is just an example of a situation where you might want</span>
  <span m='199000'>to do this. Anyway, we will look mostly at</span> <span m='204000'>particular
  examples, but just to point out that this</span> <span m='208000'>is useful when
  you study guesses in physics.</span> </p><p><span m='212000'>The first observation
  is we cannot use our usual method of</span> <span m='215000'>looking for critical
  points of f.</span> </p><p><span m='216000'>Because critical points of f typically
  will not satisfy this</span> <span m='220000'>condition and so won't be good solutions.</span>
  </p><p><span m='223000'>We need something else. Let's look at an example,</span>
  <span m='229000'>and we will see how that leads us to the method.</span> </p><p><span
  m='233000'>For example, let's say that I want to find</span> <span m='243000'>the
  point closest to the origin -- -- on the hyperbola xy equals</span> <span m='257000'>3
  in the plane. That means I have this</span> <span m='263000'>hyperbola, and I am
  asking myself what is the point on it</span> <span m='266000'>that is the closest
  to the origin?</span> </p><p><span m='269000'>I mean we can solve this by elementary
  geometry,</span> <span m='271000'>we don't need actually Lagrange multipliers,</span>
  <span m='274000'>but we are going to do it with Lagrange multipliers because it</span>
  <span m='278000'>is a pretty good example. What does it mean?</span> </p><p><span
  m='281000'>Well, it means that we want to minimize distance to the origin.</span>
  </p><p><span m='287000'>What is the distance to the origin?</span> </p><p><span
  m='289000'>If I have a point, at coordinates (x,</span> <span m='293000'>y) and
  then the distance to the origin is square root of x</span> <span m='298000'>squared
  plus y squared. Well, do we really want to</span> <span m='302000'>minimize that
  or can we minimize something easier?</span> </p><p><span m='305000'>Yeah. Maybe
  we can minimize the</span> <span m='306000'>square of a distance. Let's forget this
  guy and</span> <span m='314000'>instead -- Actually, we will minimize f of x,</span>
  <span m='323000'>y equals x squared plus y squared,</span> <span m='327000'>that
  looks better, subject to the constraint xy =</span> <span m='339000'>3. And so we
  will call this thing</span> <span m='344000'>g of x, y to illustrate the general
  method.</span> </p><p><span m='350000'>Let's look at a picture. Here you can see
  in yellow the</span> <span m='358000'>hyperbola xy equals three. And we are going
  to look for</span> <span m='362000'>the points that are the closest to the origin.</span>
  </p><p><span m='365000'>What can we do? Well, for example,</span> <span m='368000'>we
  can plot the function x squared plus y squared,</span> <span m='373000'>function
  f. That is the contour plot of f</span> <span m='377000'>with a hyperbola on top
  of it. Now let's see what we can do</span> <span m='381000'>with that. Well, let's
  ask ourselves,</span> <span m='385000'>for example, if I look at points where f</span>
  <span m='390000'>equals 20 now. I think I am at 20 but you</span> <span m='394000'>cannot
  really see it. That is a circle with a point</span> <span m='397000'>whose distant
  square is 20. Well, can I find a solution if</span> <span m='401000'>I am on the
  hyperbola? Yes, there are four points at</span> <span m='404000'>this distance.
  Can I do better?</span> </p><p><span m='406000'>Well, let's decrease for distance.</span>
  </p><p><span m='409000'>Yes, we can still find points on the hyperbola and so on.</span>
  </p><p><span m='412000'>Except if we go too low then there are no points on this</span>
  <span m='416000'>circle anymore in the hyperbola. If we decrease the value of f</span>
  <span m='420000'>that we want to look at that will somehow limit value beyond</span>
  <span m='423000'>which we cannot go, and that is the minimum of f.</span> </p><p><span
  m='427000'>We are trying to look for the smallest value of f that will</span> <span
  m='433000'>actually be realized on the hyperbola.</span> </p><p><span m='437000'>When
  does that happen? Well, I have to backtrack a</span> <span m='440000'>little bit.
  It seems like the limiting case</span> <span m='443000'>is basically here. It is
  when the circle is</span> <span m='446000'>tangent to the hyperbola. That is the
  smallest circle</span> <span m='451000'>that will hit the hyperbola. If I take a
  larger value of f,</span> <span m='457000'>I will have solutions. If I take a smaller
  value of f,</span> <span m='459000'>I will not have any solutions anymore.</span>
  </p><p><span m='461000'>So, that is the situation that we want to solve for.</span>
  </p><p><span m='469000'>How do we find that minimum? Well, a key observation that
  is</span> <span m='474000'>valid on this picture, and that actually remain true</span>
  <span m='478000'>in the completely general case, is that when we have a minimum</span>
  <span m='483000'>the level curve of f is actually tangent to our hyperbola.</span>
  </p><p><span m='489000'>It is tangent to the set of points where x,</span> <span
  m='495000'>y equals three, to the hyperbola.</span> </p><p><span m='500000'>Let's
  write that down. We observe that at the minimum</span> <span m='512000'>the level
  curve of f is tangent to the hyperbola.</span> </p><p><span m='529000'>Remember,
  the hyperbola is given by the equal g equals</span> <span m='533000'>three, so it
  is a level curve of g.</span> </p><p><span m='536000'>We have a level curve of f
  and a level curve of g that are</span> <span m='539000'>tangent to each other. And
  I claim that is going to be</span> <span m='543000'>the general situation that we
  are interested in.</span> </p><p><span m='547000'>How do we try to solve for points
  where this happens?</span> </p><p><span m='568000'>How do we find x, y where the
  level curves of f</span> <span m='576000'>and g are tangent to each other? Let's
  think for a second.</span> </p><p><span m='587000'>If the two level curves are tangent
  to each other that means</span> <span m='591000'>they have the same tangent line.
  That means that the normal</span> <span m='597000'>vectors should be parallel. Let
  me maybe draw a picture</span> <span m='603000'>here. This is the level curve maybe
  f</span> <span m='606000'>equals something. And this is the level curve g</span>
  <span m='611000'>equals constant. Here my constant is three.</span> </p><p><span
  m='616000'>Well, if I look for gradient vectors, the gradient of f will</span> <span
  m='620000'>be perpendicular to the level curve of f.</span> </p><p><span m='623000'>The
  gradient of g will be perpendicular to the level curve</span> <span m='627000'>of
  g. They don't have any reason to</span> <span m='629000'>be of the same size, but
  they have to be parallel to</span> <span m='632000'>each other. Of course, they
  could also be</span> <span m='635000'>parallel pointing in opposite directions.</span>
  </p><p><span m='638000'>But the key point is that when this happens the gradient
  of f</span> <span m='648000'>is parallel to the gradient of g.</span> </p><p><span
  m='654000'>Well, let's check that. Here is a point.</span> </p><p><span m='663000'>And
  I can plot the gradient of f in blue.</span> </p><p><span m='665000'>The gradient
  of g in yellow. And you see,</span> <span m='668000'>in most of these places, somehow
  the two gradients are</span> <span m='672000'>not really parallel. Actually, I should
  not be</span> <span m='674000'>looking at random points. I should be looking only
  on the</span> <span m='677000'>hyperbola. I want points on the hyperbola</span>
  <span m='679000'>where the two gradients are parallel.</span> </p><p><span m='682000'>Well,
  when does that happen? Well, it looks like it will</span> <span m='688000'>happen
  here. When I am at a minimum,</span> <span m='691000'>the two gradient vectors are
  parallel.</span> </p><p><span m='694000'>It is not really proof. It is an example
  that seems to</span> <span m='697000'>be convincing. So far things work pretty well.</span>
  </p><p><span m='703000'>How do we decide if two vectors are parallel?</span> </p><p><span
  m='706000'>Well, they are parallel when they are proportional to each</span> <span
  m='710000'>other. You can write one of them as a</span> <span m='714000'>constant
  times the other one, and that constant usually one</span> <span m='722000'>uses
  the Greek letter lambda. I don't know if you have seen</span> <span m='727000'>it
  before. It is the Greek letter for L.</span> </p><p><span m='730000'>And probably,
  I am sure, it is somebody's</span> <span m='735000'>idea of paying tribute to Lagrange
  by putting an L in</span> <span m='742000'>there. Lambda is just a constant.</span>
  </p><p><span m='745000'>And we are looking for a scalar lambda and points x and
  y where</span> <span m='751000'>this holds. In fact,</span> <span m='753000'>what
  we are doing is replacing min/max problems in two</span> <span m='757000'>variables
  with a constraint between them by a set of</span> <span m='761000'>equations involving,
  you will see, three variables.</span> </p><p><span m='767000'>We had min/max with
  two variables x, y,</span> <span m='774000'>but no independent. We had a constraint
  g of x,</span> <span m='780000'>y equals constant. And that becomes something new.</span>
  </p><p><span m='786000'>That becomes a system of equations where we have to</span>
  <span m='792000'>solve, well, let's write down what it means for gradient f to</span>
  <span m='799000'>be proportional to gradient g. That means that f sub x should</span>
  <span m='806000'>be lambda times g sub x, and f sub y should be lambda</span> <span
  m='812000'>times g sub y. Because the gradient vectors</span> <span m='816000'>here
  are f sub x, f sub y and g sub x,</span> <span m='819000'>g sub y. If you have a
  third variable z</span> <span m='823000'>then you have also an equation f sub z
  equals lambda g sub z.</span> </p><p><span m='829000'>Now, let's see. How many unknowns
  do we have in</span> <span m='833000'>these equations? Well, there is x,</span>
  <span m='835000'>there is y and there is lambda. We have three unknowns and have</span>
  <span m='841000'>only two equations. Something is missing.</span> </p><p><span m='846000'>Well,
  I mean x and y are not actually independent.</span> </p><p><span m='850000'>They
  are related by the equation g of x,</span> <span m='854000'>y equals c, so we need
  to add the constraint g equals c.</span> </p><p><span m='861000'>And now we have
  three equations involving three variables.</span> </p><p><span m='866000'>Let's
  see how that works. Here remember we have f equals</span> <span m='879000'>x squared
  y squared and g = xy. What is f sub x?</span> </p><p><span m='885000'>It is going
  to be 2x equals lambda times,</span> <span m='892000'>what is g sub x, y.</span>
  </p><p><span m='895000'>Maybe I should write here f sub x equals lambda g sub x
  just to</span> <span m='899000'>remind you. Then we have f sub y equals</span> <span
  m='903000'>lambda g sub y. F sub y is 2y equals lambda</span> <span m='910000'>times
  g sub y is x. And then our third equation g</span> <span m='918000'>equals c becomes
  xy equals three.</span> </p><p><span m='922000'>So, that is what you would have
  to solve.</span> </p><p><span m='926000'>Any questions at this point? No.</span>
  </p><p><span m='933000'>Yes? How do I know the direction of</span> <span m='944000'>a
  gradient? Do you mean how do I know that</span> <span m='947000'>it is perpendicular
  to a level curve?</span> </p><p><span m='950000'>Oh, how do I know if it points
  in that direction on the</span> <span m='954000'>opposite one? Well, that depends.</span>
  </p><p><span m='956000'>I mean we'd seen in last time, but the gradient is</span>
  <span m='959000'>perpendicular to the level and points towards higher values of</span>
  <span m='962000'>a function. So it could be -- Wait.</span> </p><p><span m='965000'>What
  did I have? It could be that my gradient</span> <span m='968000'>vectors up there
  actually point in opposite directions.</span> </p><p><span m='971000'>It doesn't
  matter to me because it will still look the same in</span> <span m='975000'>terms
  of the equation, just lambda will be positive or</span> <span m='978000'>negative,
  depending on the case. I can handle both situations.</span> </p><p><span m='982000'>It's
  not a problem. I can allow lambda to be</span> <span m='990000'>positive or negative.
  Well, in this example,</span> <span m='994000'>it looks like lambda will be positive.</span>
  </p><p><span m='995000'>If you look at the picture on the plot.</span> </p><p><span
  m='998000'>Yes? Well, because actually they are</span> <span m='1008000'>not equal
  to each other. If you look at this point where</span> <span m='1011000'>the hyperbola
  and the circle touch each other,</span> <span m='1015000'>first of all, I don't
  know which circle I am</span> <span m='1018000'>going to look at. I am trying to
  solve,</span> <span m='1021000'>actually, for the radius of the circle.</span> </p><p><span
  m='1024000'>I am trying to find what the minimum value of f is.</span> </p><p><span
  m='1027000'>And, second, at that point,</span> <span m='1030000'>the value of f
  and the value of g are not equal.</span> </p><p><span m='1034000'>g is equal to
  three because I want the hyperbola x equals</span> <span m='1037000'>three. The
  value of f will be the</span> <span m='1039000'>square of a distance, whatever that
  is.</span> </p><p><span m='1042000'>I think it will end up being 6, but we will
  see.</span> </p><p><span m='1047000'>So, you cannot really set them equal because
  you don't know</span> <span m='1049000'>what f is equal to in advance. Yes?</span>
  </p><p><span m='1065000'>Not quite. Actually, here I am just using</span> <span
  m='1069000'>this idea of finding a point closest to the origin to</span> <span m='1072000'>illustrate
  an example of a min/max problem.</span> </p><p><span m='1075000'>The general problem
  we are trying to solve is minimize f</span> <span m='1079000'>subject to g equals
  constant. And what we are going to do for</span> <span m='1083000'>that is we are
  really going to say instead let's look at places</span> <span m='1087000'>where
  gradient f and gradient g are parallel to each other and</span> <span m='1090000'>solve
  for equations of that. I think we completely lose the</span> <span m='1094000'>notion
  of closest point if we just look at these equations.</span> </p><p><span m='1099000'>We
  don't really say anything about closest points anymore.</span> </p><p><span m='1101000'>Of
  course, that is what they mean in the end.</span> </p><p><span m='1104000'>But,
  in the general setting, there is no closest point</span> <span m='1108000'>involved
  anymore. OK.</span> </p><p><span m='1111000'>Yes? Yes.</span> </p><p><span m='1120000'>It
  is always going to be the case that,</span> <span m='1123000'>at the minimum, or
  at the maximum of a function</span> <span m='1126000'>subject to a constraint, the
  level curves of f and the</span> <span m='1129000'>level curves of g will be tangent
  to each other.</span> </p><p><span m='1132000'>That is the basis for this method.</span>
  </p><p><span m='1134000'>I am going to justify that soon. It could be minimum or
  maximum.</span> </p><p><span m='1140000'>In three-dimensions it could even be a
  saddle point.</span> </p><p><span m='1142000'>And, in fact, I should say in advance,</span>
  <span m='1143000'>this method will not tell us whether it is a minimum or a</span>
  <span m='1146000'>maximum. We do not have any way of</span> <span m='1148000'>knowing,
  except for testing values.</span> </p><p><span m='1150000'>We cannot use second
  derivative tests or anything like that.</span> </p><p><span m='1153000'>I will get
  back to that. Yes?</span> </p><p><span m='1161000'>Yes. Here you can set y equals
  to</span> <span m='1163000'>favor x. Then you can minimize x squared</span> <span
  m='1166000'>plus nine over x squared. In general, if I am trying to</span> <span
  m='1170000'>solve a more complicated problem, I might not be able to</span> <span
  m='1173000'>solve. I am doing an example where,</span> <span m='1175000'>indeed,
  here you could solve and remove one variable,</span> <span m='1178000'>but you cannot
  always do that. And this method will still work.</span> </p><p><span m='1181000'>The
  other one won't. OK.</span> </p><p><span m='1187000'>I don't see any other questions.
  Are there any other questions?</span> </p><p><span m='1193000'>No. OK.</span> </p><p><span
  m='1196000'>I see a lot of students stretching and so on,</span> <span m='1202000'>so
  it is very confusing for me. How do we solve these equations?</span> </p><p><span
  m='1208000'>Well, the answer is in general we might be in deep trouble.</span> </p><p><span
  m='1214000'>There is no general method for solving the equations that you</span>
  <span m='1218000'>get from this method. You just have to think about</span> <span
  m='1221000'>them. Sometimes it will be very easy.</span> </p><p><span m='1225000'>Sometimes
  it will be so hard that you cannot actually do it</span> <span m='1228000'>without
  the computer. Sometimes it will be just hard</span> <span m='1231000'>enough to
  be on Part B of this week's problem set.</span> </p><p><span m='1250000'>I claim
  in this case we can actually do it without so much</span> <span m='1256000'>trouble,
  because actually we can think of this as a two by two</span> <span m='1263000'>linear
  system in x and y. Well, let me do something.</span> </p><p><span m='1270000'>Let
  me rewrite the first two equations as 2x - lambda y = 0.</span> </p><p><span m='1278000'>And
  lambda x - 2y = 0. And xy = 3.</span> </p><p><span m='1290000'>That is what we want
  to solve. Well, I can put this into</span> <span m='1296000'>matrix form. Two minus
  lambda,</span> <span m='1301000'>lambda minus two times x, y equals 0,0.</span>
  </p><p><span m='1308000'>Now, how do I solve a linear system matrix times x,</span>
  <span m='1312000'>y equals zero? Well, I always have an obvious</span> <span m='1314000'>solution.
  X and y both equal to zero.</span> </p><p><span m='1316000'>Is that a good solution?
  No, because zero times zero is</span> <span m='1322000'>not three. We want another
  solution,</span> <span m='1327000'>the trivial solution. 0,0 does not solve the</span>
  <span m='1334000'>constraint equation xy equals three, so we want another</span>
  <span m='1340000'>solution. When do we have another</span> <span m='1344000'>solution?
  Well, when the determinant of a</span> <span m='1349000'>matrix is zero. We have
  other solutions that</span> <span m='1357000'>exist only if determinant of a matrix
  is zero.</span> </p><p><span m='1366000'>M is this guy. Let's compute the determinant.</span>
  </p><p><span m='1381000'>Well, that seems to be negative four plus lambda squared.</span>
  </p><p><span m='1388000'>That is zero exactly when lambda squared equals four,</span>
  <span m='1395000'>which is lambda is plus or minus two.</span> </p><p><span m='1400000'>Already
  you see here it is a the level of difficulty that is</span> <span m='1405000'>a
  little bit much for an exam but perfectly fine for a problem</span> <span m='1410000'>set
  or for a beautiful lecture like this one.</span> </p><p><span m='1413000'>How do
  we deal with -- Well, we have two cases to look at.</span> </p><p><span m='1417000'>Lambda
  equals two or lambda equals minus two.</span> </p><p><span m='1420000'>Let's start
  with lambda equals two.</span> </p><p><span m='1423000'>If I set lambda equals two,
  what does this equation become?</span> </p><p><span m='1427000'>Well, it becomes
  x equals y. This one becomes y equals x.</span> </p><p><span m='1433000'>Well, they
  seem to be the same. x equals y.</span> </p><p><span m='1437000'>And then the equation
  xy equals three becomes,</span> <span m='1441000'>well, x squared equals three.
  I have two solutions.</span> </p><p><span m='1446000'>One is x equals root three
  and, therefore, y equals root three</span> <span m='1455000'>as well, or negative
  root three and negative root three.</span> </p><p><span m='1463000'>Let's look at
  the other case. If I set lambda equal to</span> <span m='1466000'>negative two then
  I get 2x equals negative 2y.</span> </p><p><span m='1470000'>That means x equals
  negative y. The second one,</span> <span m='1477000'>2y equals negative 2x. That
  is y equals negative x.</span> </p><p><span m='1480000'>Well, that is the same thing.
  And xy equals three becomes</span> <span m='1485000'>negative x squared equals three.
  Can we solve that?</span> </p><p><span m='1491000'>No. There are no solutions here.</span>
  </p><p><span m='1498000'>Now we have two candidate points which are these two</span>
  <span m='1503000'>points, root three, root three or negative root</span> <span m='1507000'>three,
  negative root three. OK.</span> </p><p><span m='1513000'>Let's actually look at
  what we have here.</span> </p><p><span m='1516000'>Maybe you cannot read the coordinates,
  but the point that</span> <span m='1520000'>I have here is indeed root three, root
  three.</span> </p><p><span m='1523000'>How do we see that lambda equals two?</span>
  </p><p><span m='1526000'>Well, if you look at this picture, the gradient of f,</span>
  <span m='1529000'>that is the blue vector, is indeed twice the yellow</span> <span
  m='1532000'>vector, gradient g. That is where you read the</span> <span m='1536000'>value
  of lambda. And we have the other solution</span> <span m='1541000'>which is somewhere
  here. Negative root three,</span> <span m='1545000'>negative root there. And there,
  again,</span> <span m='1548000'>lambda equals two. The two vectors are</span> <span
  m='1551000'>proportional by a factor of two. Yes?</span> </p><p><span m='1559000'>No,
  solutions are not quite guaranteed to be absolute minima</span> <span m='1561000'>or
  maxima. They are guaranteed to be</span> <span m='1563000'>somehow critical points
  end of a constraint.</span> </p><p><span m='1566000'>That means if you were able
  to solve and eliminate the variable</span> <span m='1569000'>that would be a critical
  point. When you have the same problem,</span> <span m='1572000'>as we have critical
  points, are they maxima or minima?</span> </p><p><span m='1574000'>And the answer
  is, well, we won't know until we</span> <span m='1582000'>check. More questions?</span>
  </p><p><span m='1588000'>No. Yes?</span> </p><p><span m='1592000'>What is a Lagrange
  multiplier? Well, it is this number lambda</span> <span m='1596000'>that is called
  the multiplier here.</span> </p><p><span m='1599000'>It is a multiplier because
  it is what you have to multiply</span> <span m='1604000'>gradient of g by to get
  gradient of f.</span> </p><p><span m='1608000'>It multiplies.</span> </p><p><span
  m='1624000'>Let's try to see why is this method valid?</span> </p><p><span m='1631000'>Because
  so far I have shown you pictures and have said see they</span> <span m='1638000'>are
  tangent. But why is it that they have to</span> <span m='1643000'>be tangent in
  general? Let's think about it.</span> </p><p><span m='1648000'>Let's say that we
  are at constrained min or max.</span> </p><p><span m='1657000'>What that means is
  that if I move on the level g equals</span> <span m='1662000'>constant then the
  value of f should only increase or only</span> <span m='1666000'>decrease. But it
  means,</span> <span m='1669000'>in particular, to first order it will not</span>
  <span m='1673000'>change. At an unconstrained min or max,</span> <span m='1676000'>partial
  derivatives are zero. In this case,</span> <span m='1679000'>derivatives are zero
  only in the allowed directions.</span> </p><p><span m='1682000'>And the allowed
  directions are those that stay on the levels of</span> <span m='1689000'>this g
  equals constant. In any direction along the</span> <span m='1701000'>level set g
  = c the rate of change of f must be zero.</span> </p><p><span m='1720000'>That is
  what happens at minima or maxima.</span> </p><p><span m='1724000'>Except here, of
  course, we look only at the</span> <span m='1729000'>allowed directions. Let's say
  the same thing in</span> <span m='1734000'>terms of directional derivatives.</span>
  </p><p><span m='1763000'>That means for any direction that is tangent to the</span>
  <span m='1775000'>constraint level g equal c, we must have df over ds in the</span>
  <span m='1789000'>direction of u equals zero. I will draw a picture.</span> </p><p><span
  m='1800000'>Let's say now I am in three variables just to give you</span> <span
  m='1805000'>different examples. Here I have a level surface g</span> <span m='1809000'>equals
  c. I am at my point.</span> </p><p><span m='1811000'>And if I move in any direction
  that is on the level surface,</span> <span m='1818000'>so I move in the direction
  u tangent to the level surface,</span> <span m='1824000'>then the rate of change
  of f in that direction should be zero.</span> </p><p><span m='1832000'>Now, remember
  what the formula is for this guy.</span> </p><p><span m='1834000'>Well, we have
  seen that this guy is actually radiant f dot u.</span> </p><p><span m='1844000'>That
  means any such vector u must be perpendicular to the</span> <span m='1858000'>gradient
  of f. That means that the gradient of</span> <span m='1865000'>f should be perpendicular
  to anything that is tangent to this</span> <span m='1870000'>level. That means the
  gradient of f</span> <span m='1872000'>should be perpendicular to the level set.</span>
  </p><p><span m='1876000'>That is what we have shown.</span> </p><p><span m='1897000'>But
  we know another vector that is also perpendicular to the</span> <span m='1900000'>level
  set of g. That is the gradient of g.</span> </p><p><span m='1917000'>We conclude
  that the gradient of f must be parallel to the</span> <span m='1922000'>gradient
  of g because both are perpendicular to the level set</span> <span m='1927000'>of
  g. I see confused faces,</span> <span m='1929000'>so let me try to tell you again
  where that comes from.</span> </p><p><span m='1933000'>We said if we had a constrained
  minimum or maximum,</span> <span m='1936000'>if we move in the level set of g, f
  doesn't change.</span> </p><p><span m='1939000'>Well, it doesn't change to first
  order.</span> </p><p><span m='1940000'>It is the same idea as when you are looking
  for a minimum you</span> <span m='1944000'>set the derivative equal to zero.</span>
  </p><p><span m='1946000'>So the derivative in any direction, tangent to g equals</span>
  <span m='1951000'>c, should be the directional derivative of f,</span> <span m='1954000'>in
  any such direction, should be zero.</span> </p><p><span m='1958000'>That is what
  we mean by critical point of f.</span> </p><p><span m='1963000'>And so that means
  that any vector u, any unit vector</span> <span m='1968000'>tangent to the level
  set of g is going to be perpendicular to the</span> <span m='1975000'>gradient of
  f. That means that the gradient of</span> <span m='1980000'>f is perpendicular to
  the level set of g.</span> </p><p><span m='1984000'>If you want, that means the
  level sets of f</span> <span m='1986000'>and g are tangent to each other. That is
  justifying what we have</span> <span m='1990000'>observed in the picture that the
  two level sets have to be</span> <span m='1995000'>tangent to each other at the
  prime minimum or maximum.</span> </p><p><span m='2000000'>Does that make a little
  bit of sense?</span> </p><p><span m='2003000'>Kind of. I see at least a few faces</span>
  <span m='2008000'>nodding so I take that to be a positive answer.</span> </p><p><span
  m='2015000'>Since I have been asked by several of you,</span> <span m='2019000'>how
  do I know if it is a maximum or a minimum?</span> </p><p><span m='2023000'>Well,
  warning, the method doesn't tell whether</span> <span m='2037000'>a solution is
  a minimum or a maximum.</span> </p><p><span m='2049000'>How do we do it? Well, more
  bad news.</span> </p><p><span m='2053000'>We cannot use the second derivative test.</span>
  </p><p><span m='2066000'>And the reason for that is that we care actually only about</span>
  <span m='2070000'>these specific directions that are tangent to variable of g.</span>
  </p><p><span m='2074000'>And we don't want to bother to try to define directional
  second</span> <span m='2079000'>derivatives. Not to mention that actually it</span>
  <span m='2082000'>wouldn't work. There is a criterion but it is</span> <span m='2085000'>much
  more complicated than that. Basically, the answer for us is</span> <span m='2089000'>that
  we don't have a second derivative test in this</span> <span m='2092000'>situation.
  What are we left with?</span> </p><p><span m='2094000'>Well, we are just left with
  comparing values.</span> </p><p><span m='2097000'>Say that in this problem you found
  a point where f equals</span> <span m='2100000'>three, a point where f equals nine,
  a point where f equals 15.</span> </p><p><span m='2104000'>Well, then probably the
  minimum is the point where f equals</span> <span m='2108000'>three and the maximum
  is 15. Actually, in this case,</span> <span m='2112000'>where we found minima, these
  two points are tied for</span> <span m='2117000'>minimum. What about the maximum?</span>
  </p><p><span m='2119000'>What is the maximum of f on the hyperbola?</span> </p><p><span
  m='2122000'>Well, it is infinity because the point can go as far as you</span> <span
  m='2125000'>want from the origin. But the general idea is if we</span> <span m='2129000'>have
  a good reason to believe that there should be a minimum,</span> <span m='2135000'>and
  it's not like at infinity or something weird like that,</span> <span m='2138000'>then
  the minimum will be a solution of the Lagrange</span> <span m='2142000'>multiplier
  equations. We just look for all the</span> <span m='2146000'>solutions and then
  we choose the one that gives us the lowest</span> <span m='2151000'>value. Is that
  good enough?</span> </p><p><span m='2155000'>Let me actually write that down.</span>
  </p><p><span m='2183000'>To find the minimum or the maximum, we compare values of
  f</span> <span m='2195000'>at the various solutions -- -- to Lagrange multiplier</span>
  <span m='2206000'>equations.</span> </p><p><span m='2228000'>I should say also that
  sometimes you can just conclude</span> <span m='2231000'>by thinking geometrically.
  In this case,</span> <span m='2234000'>when it is asking you which point is closest
  to the origin</span> <span m='2238000'>you can just see that your answer is the
  correct one.</span> </p><p><span m='2243000'>Let's do an advanced example. Advanced
  means that -- Well,</span> <span m='2252000'>this one I didn't actually dare to
  put on top of the other</span> <span m='2257000'>problem sets. Instead, I am going
  to do it.</span> </p><p><span m='2268000'>What is this going to be about? We are
  going to look for a</span> <span m='2271000'>surface minimizing pyramid. Let's say
  that we want to build</span> <span m='2283000'>a pyramid with a given triangular
  base -- -- and a</span> <span m='2299000'>given volume. Say that I have maybe in
  the x,</span> <span m='2308000'>y plane I am giving you some triangle.</span> </p><p><span
  m='2313000'>And I am going to try to build a pyramid.</span> </p><p><span m='2320000'>Of
  course, I can choose where to put the top of a pyramid.</span> </p><p><span m='2328000'>This
  guy will end up being behind now.</span> </p><p><span m='2333000'>And the constraint
  and the goal is to minimize the total surface</span> <span m='2349000'>area. The
  first time I taught this</span> <span m='2353000'>class, it was a few years ago,
  was just before they built the</span> <span m='2355000'>Stata Center. And then I
  used to motivate</span> <span m='2357000'>this problem by saying Frank Gehry has
  gone crazy and has</span> <span m='2360000'>been given a triangular plot of land
  he wants to put a pyramid.</span> </p><p><span m='2363000'>There needs to be the
  right amount of volume so that you can</span> <span m='2366000'>put all the offices
  in there. And he wants it to be,</span> <span m='2368000'>actually, covered in solid
  gold.</span> </p><p><span m='2371000'>And because that is expensive, the administration
  wants him to</span> <span m='2374000'>cut the costs a bit. And so you have to minimize
  the</span> <span m='2378000'>total size so that it doesn't cost too much.</span>
  </p><p><span m='2382000'>We will see if MIT comes up with a triangular pyramid</span>
  <span m='2385000'>building. Hopefully not.</span> </p><p><span m='2388000'>It could
  be our next dorm, you never know.</span> </p><p><span m='2398000'>Anyway, it is
  a fine geometry problem.</span> </p><p><span m='2401000'>Let's try to think about
  how we can do this.</span> </p><p><span m='2407000'>The natural way to think about
  it would be -- Well,</span> <span m='2410000'>what do we have to look for first?</span>
  </p><p><span m='2411000'>We have to look for the position of that top point.</span>
  </p><p><span m='2418000'>Remember we know that the volume of a pyramid is one-third</span>
  <span m='2429000'>the area of base times height. In fact, fixing the volume,</span>
  <span m='2437000'>knowing that we have fixed the area of a base,</span> <span m='2439000'>means
  that we are fixing the height of the pyramid.</span> </p><p><span m='2443000'>The
  height is completely fixed. What we have to choose just is</span> <span m='2447000'>where
  do we put that top point? Do we put it smack in the</span> <span m='2452000'>middle
  of a triangle or to a side or even anywhere we want?</span> </p><p><span m='2458000'>Its
  z coordinate is fixed. Let's call h the height.</span> </p><p><span m='2475000'>What
  we could do is something like this.</span> </p><p><span m='2480000'>We say we have
  three points of a base.</span> </p><p><span m='2484000'>Let's call them p1 at (x1,
  y1,0); p2 at (x2,</span> <span m='2492000'>y2,0); p3 at (x3, y3,0).</span> </p><p><span
  m='2496000'>This point p is the unknown point at (x, y,</span> <span m='2500000'>h).
  We know the height.</span> </p><p><span m='2502000'>And then we want to minimize
  the sum of the areas of these</span> <span m='2506000'>three triangles. One here,
  one here and one at</span> <span m='2510000'>the back. And areas of triangles we
  know</span> <span m='2513000'>how to express by using length of cross-product.</span>
  </p><p><span m='2517000'>It becomes a function of x and y.</span> </p><p><span m='2520000'>And
  you can try to minimize it. Actually, it doesn't quite work.</span> </p><p><span
  m='2524000'>The formulas are just too complicated.</span> </p><p><span m='2525000'>You
  will never get there. What happens is actually maybe</span> <span m='2534000'>we
  need better coordinates. Why do we need better</span> <span m='2538000'>coordinates?
  That is because the geometry is</span> <span m='2541000'>kind of difficult to do
  if you use x, y coordinates.</span> </p><p><span m='2544000'>I mean formula for
  cross-product is fine,</span> <span m='2548000'>but then the length of the vector
  will be annoying and just</span> <span m='2553000'>doesn't look good. Instead, let's
  think about it</span> <span m='2557000'>differently.</span> </p><p><span m='2574000'>I
  claim if we do it this way and we express the area as a</span> <span m='2581000'>function
  of x, y, well, actually we can't</span> <span m='2586000'>solve for a minimum. Here
  is another way to do it.</span> </p><p><span m='2593000'>Well, what has worked pretty
  well for us so far is this</span> <span m='2597000'>geometric idea of base times
  height.</span> </p><p><span m='2599000'>So let's think in terms of the heights of
  side triangles.</span> </p><p><span m='2609000'>I am going to use the height of
  these things.</span> </p><p><span m='2617000'>And I am going to say that the area
  will be the sum of three</span> <span m='2623000'>terms, which are three bases times
  three heights.</span> </p><p><span m='2628000'>Let's give names to these quantities.</span>
  </p><p><span m='2633000'>Actually, for that it is going to be good to have the point
  in</span> <span m='2638000'>the xy plane that lives directly below p.</span> </p><p><span
  m='2641000'>Let's call it q. P is the point that coordinates</span> <span m='2648000'>x,
  y, h. And let's call q the point that</span> <span m='2653000'>is just below it
  and so it' coordinates are x,</span> <span m='2659000'>y, 0. Let's see.</span> </p><p><span
  m='2662000'>Let me draw a map of this thing. p1, p2, p3 and I have my point</span>
  <span m='2674000'>q in the middle. Let's see.</span> </p><p><span m='2677000'>To
  know these areas, I need to know the base.</span> </p><p><span m='2680000'>Well,
  the base I can decide that I know it because it is</span> <span m='2684000'>part
  of my given data. I know the sides of this</span> <span m='2688000'>triangle. Let
  me call the lengths a1,</span> <span m='2693000'>a2, a3. I also need to know the
  height,</span> <span m='2696000'>so I need to know these lengths.</span> </p><p><span
  m='2698000'>How do I know these lengths? Well, its distance in space,</span> <span
  m='2701000'>but it is a little bit annoying.</span> </p><p><span m='2703000'>But
  maybe I can reduce it to a distance in the plane by looking</span> <span m='2710000'>instead
  at this distance here. Let me give names to the</span> <span m='2717000'>distances
  from q to the sides. Let's call u1,</span> <span m='2724000'>u2, u3 the distances
  from q to the sides.</span> </p><p><span m='2747000'>Well, now I can claim I can
  find, actually,</span> <span m='2749000'>sorry. I need to draw one more thing.</span>
  </p><p><span m='2753000'>I claim I have a nice formula for the area,</span> <span
  m='2757000'>because this is vertical and this is horizontal so this</span> <span
  m='2761000'>length here is u3, this length here is h.</span> </p><p><span m='2765000'>So
  what is this length here? It is the square root of u3</span> <span m='2773000'>squared
  plus h squared. And similarly for these other</span> <span m='2777000'>guys. They
  are square roots of a u</span> <span m='2783000'>squared plus h squared. The heights
  of the faces are</span> <span m='2791000'>square root of u1 squared times h squared.</span>
  </p><p><span m='2796000'>And similarly with u2 and u3. So the total side area is
  going</span> <span m='2803000'>to be the area of the first faces,</span> <span m='2807000'>one-half
  of base times height, plus one-half of a base times a</span> <span m='2818000'>height
  plus one-half of the third one.</span> </p><p><span m='2826000'>It doesn't look
  so much better. But, trust me,</span> <span m='2829000'>it will get better. Now,
  that is a function of</span> <span m='2835000'>three variables, u1, u2, u3.</span>
  </p><p><span m='2839000'>And how do we relate u1, u2, u3 to each other?</span> </p><p><span
  m='2842000'>They are probably not independent.</span> </p><p><span m='2845000'>Well,
  let's cut this triangle here into three pieces like</span> <span m='2852000'>that.
  Then each piece has side --</span> <span m='2855000'>Well, let's look at it the
  piece of the bottom.</span> </p><p><span m='2860000'>It has base a3, height u3.
  Cutting base into three tells</span> <span m='2870000'>you that the area of a base
  is one-half of a1,</span> <span m='2877000'>u1 plus one-half of a2, u2 plus one-half
  of a3,</span> <span m='2884000'>u3. And that is our constraint.</span> </p><p><span
  m='2889000'>My three variables, u1, u2, u3, are constrained in</span> <span m='2892000'>this
  way. The sum of this figure must be</span> <span m='2894000'>the area of a base.
  And I want to minimize that guy.</span> </p><p><span m='2897000'>So that is my g
  and that guy here is my f.</span> </p><p><span m='2903000'>Now we try to apply our
  Lagrange multiplier equations.</span> </p><p><span m='2908000'>Well, partial f of
  a partial u1 is -- Well,</span> <span m='2913000'>if you do the calculation, you
  will see it is one-half a1,</span> <span m='2916000'>u1 over square root of u1^2
  plus h^2 equals lambda,</span> <span m='2923000'>what is partial g, partial a1?</span>
  </p><p><span m='2926000'>That one you can do, I am sure. It is one-half a1.</span>
  </p><p><span m='2930000'>Oh, these guys simplify. If you do the same with the</span>
  <span m='2940000'>second one -- -- things simplify again.</span> </p><p><span m='2949000'>And
  the same with the third one. Well, you will get,</span> <span m='2957000'>after
  simplifying, u3 over square root of u3</span> <span m='2961000'>squared plus h squared
  equals lambda.</span> </p><p><span m='2964000'>Now, that means this guy equals this
  guy equals this guy.</span> </p><p><span m='2967000'>They are all equal to lambda.
  And, if you think about it,</span> <span m='2973000'>that means that u1 = u2 = u3.
  See, it looked like scary</span> <span m='2979000'>equations but the solution is
  very simple.</span> </p><p><span m='2982000'>What does it mean? It means that our
  point q</span> <span m='2985000'>should be equidistant from all three sides.</span>
  </p><p><span m='2987000'>That is called the incenter. Q should be in the incenter.</span>
  </p><p><span m='2992000'>The next time you have to build a golden pyramid and don't
  want</span> <span m='2996000'>to go broke, well, you know where to put the top.</span>
  </p><p><span m='2999000'>If that was a bit fast, sorry. Anyway, it is not completely</span>
  <span m='3003000'>crucial. But go over it and you will see</span> <span m='3006000'>it
  works. Have a nice weekend.</span> </p><p></p>
type: course
uid: 776156be63c924038a700b336c8ac82a

---
None