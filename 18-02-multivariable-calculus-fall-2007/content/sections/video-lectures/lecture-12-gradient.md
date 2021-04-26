---
about_this_resource_text: <p><strong>Topics covered:</strong> Gradient; directional
  derivative; tangent plane</p> <p><strong>Instructor:</strong> Prof. Denis Auroux</p>
course_id: 18-02-multivariable-calculus-fall-2007
embedded_media:
- id: 12.jpg
  parent_uid: 83f3db401bd399a271d4d5c2ccc9ab7c
  technical_location: https://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-12-gradient/12.jpg
  title: 'Lecture 12: Gradient'
  type: null
  uid: c7b5358e7adf66a43a2865aac0ffbf5c
- id: Video-YouTube-Stream
  media_location: 2XraaWefBd8
  parent_uid: 83f3db401bd399a271d4d5c2ccc9ab7c
  title: Video-YouTube-Stream
  type: Video
  uid: e1725dd1046d65574ee6e0c2f7801ef0
- id: Thumbnail-YouTube-JPG
  media_location: https://img.youtube.com/vi/2XraaWefBd8/default.jpg
  parent_uid: 83f3db401bd399a271d4d5c2ccc9ab7c
  title: Thumbnail-YouTube-JPG
  type: Thumbnail
  uid: 5d408ef139fb120d724a980f9afee227
- id: Video-iTunesU-MP4
  media_location: https://itunes.apple.com/us/itunes-u/id354869122
  parent_uid: 83f3db401bd399a271d4d5c2ccc9ab7c
  title: Video-iTunes U-MP4
  type: Video
  uid: 59ddb2eb688c9deebe5781bde4be4a45
- id: Video-InternetArchive-MP4
  media_location: http://www.archive.org/download/MIT18.02F07/ocw-18_02-f07-lec12_300k.mp4
  parent_uid: 83f3db401bd399a271d4d5c2ccc9ab7c
  title: Video-Internet Archive-MP4
  type: Video
  uid: fbfde483f2024a1b4efd35d67bed640f
- id: Video-VideoLecturesnet-Stream
  media_location: http://videolectures.net/mit1802f07_multivariable_calculus/
  parent_uid: 83f3db401bd399a271d4d5c2ccc9ab7c
  title: Video-VideoLectures.net-Stream
  type: Video
  uid: 9e1648f32e913a185b9b81c70ccbdcb6
- id: Thumbnail-OCW-JPG
  parent_uid: 83f3db401bd399a271d4d5c2ccc9ab7c
  title: Thumbnail-OCW-JPG
  type: Thumbnail
  uid: a4eb8d81fe9fd7c2591f58740b64cf86
- id: 3Play-3PlayYouTubeid-MP4
  media_location: 2XraaWefBd8
  parent_uid: 83f3db401bd399a271d4d5c2ccc9ab7c
  title: 3Play-3Play YouTube id
  type: 3Play
  uid: 0dfde54184cc6aa7499e8cd5b2204d02
- id: 2XraaWefBd8.srt
  parent_uid: 83f3db401bd399a271d4d5c2ccc9ab7c
  technical_location: https://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-12-gradient/2XraaWefBd8.srt
  title: 3play caption file
  type: null
  uid: a7795eccb5d1a1941d92263cdf2beec4
- id: 2XraaWefBd8.pdf
  parent_uid: 83f3db401bd399a271d4d5c2ccc9ab7c
  technical_location: https://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-12-gradient/2XraaWefBd8.pdf
  title: 3play pdf file
  type: null
  uid: 9fb8a8b323474dbd864b0eae7e1b9618
- id: Caption-3Play YouTube id-SRT
  parent_uid: 83f3db401bd399a271d4d5c2ccc9ab7c
  title: Caption-3Play YouTube id-SRT-English - US
  type: Caption
  uid: bac7b1b5adaa4ebb92773504b781c980
- id: Transcript-3Play YouTube id-PDF
  parent_uid: 83f3db401bd399a271d4d5c2ccc9ab7c
  title: Transcript-3Play YouTube id-PDF-English - US
  type: Transcript
  uid: 8b98a51eed26072c0cb507c7c530e26b
inline_embed_id: 16929960lecture12:gradient12508244
layout: video
order_index: null
parent_uid: d4e54c6363f292115697e70de7a59fd1
related_resources_text: <p>Lecture Notes - Week 5 Summary (<a title="Open in a new
  window." target="_blank" href="./resolveuid/bc9b2e5f89f42650eb46fa9879508923">PDF</a>)&nbsp;</p>
short_url: lecture-12-gradient
technical_location: https://ocw.mit.edu/courses/mathematics/18-02-multivariable-calculus-fall-2007/video-lectures/lecture-12-gradient
template_type: Tabbed
title: 'Lecture 12: Gradient'
transcript: "<p><span m='1000'> The following content is provided under a Creative</span>\
  \ <span m='3000'>Commons license. Your support will help MIT</span> <span m='5000'>OpenCourseWare\
  \ continue to offer high quality educational</span> <span m='8000'>resources for\
  \ free. To make a donation or to view</span> <span m='13000'>additional materials\
  \ from hundreds of MIT courses,</span> <span m='18000'>visit MIT OpenCourseWare\
  \ at ocw.mit.edu.</span> <span m='23000'>so -- OK, so remember last time,</span>\
  \ <span m='25000'>on Tuesday we learned about the chain rule,</span> <span m='32000'>and\
  \ so for example we saw that if we have a function that</span> <span m='39000'>depends,\
  \ sorry, on three variables,</span> <span m='44000'>x,y,z, that x,y,z themselves\
  \ depend on</span> <span m='50000'>some variable, t,</span> <span m='54000'>then\
  \ you can find a formula for df/dt by writing down wx/dx dt</span> <span m='66000'>wy\
  \ dy/dt wz dz/dt. And, the meaning of that</span> <span m='72000'>formula is that\
  \ while the change in w is caused by changes in x,</span> <span m='77000'>y, and\
  \ z, x, y, and z change at rates dx/dt,</span> <span m='81000'>dy/dt, dz/dt. And,\
  \ this causes a function to</span> <span m='85000'>change accordingly using, well,\
  \ the partial derivatives</span> <span m='91000'>tell you how sensitive w is to\
  \ changes in each variable.</span> <span m='97000'>OK, so, we are going to just\
  \ rewrite this in a new notation.</span> <span m='105000'>So, I'm going to rewrite\
  \ this in a more concise form as</span> <span m='112000'>gradient of w dot product\
  \ with velocity vector dr/dt.</span> <span m='119000'>So, the gradient of w is a\
  \ vector formed by putting</span> <span m='124000'>together all of the partial derivatives.</span>\
  \ <span m='128000'>OK, so it's the vector whose components are the partials.</span>\
  \ <span m='132000'>And, of course, it's a vector that depends on</span> <span m='135000'>x,\
  \ y, and z, right? These guys depend on x, y, z.</span> <span m='139000'>So, it's\
  \ actually one vector for each point,</span> <span m='142000'>x, y, z. You can talk\
  \ about the gradient</span> <span m='151000'>of w at some point, x, y, z.</span>\
  \ <span m='159000'>So, at each point, it gives you a vector.</span> <span m='161000'>That\
  \ actually is what we will call later a vector field.</span> <span m='167000'>We'll\
  \ get back to that later. And, dr/dt is just the velocity</span> <span m='179000'>vector\
  \ dx/dt, dy/dt, dz/dt.</span> <span m='187000'>OK, so the new definition for today\
  \ is the definition of the</span> <span m='194000'>gradient vector. And, our goal\
  \ will be to</span> <span m='198000'>understand a bit better, what does this vector\
  \ mean?</span> <span m='201000'>What does it measure? And, what can we do with it?</span>\
  \ <span m='204000'>But, you see that in terms of information content,</span> <span\
  \ m='209000'>it's really the same information that's already in</span> <span m='213000'>the\
  \ partial derivatives, or in the differential.</span> <span m='218000'>So, yes,\
  \ and I should say, of course you can also use the</span> <span m='223000'>gradient\
  \ and other things like approximation formulas and so</span> <span m='229000'>on.\
  \ And so far, it's just notation.</span> <span m='232000'>It's a way to rewrite\
  \ things. But, so here's the first cool</span> <span m='237000'>property of the\
  \ gradient. So, I claim that the gradient</span> <span m='243000'>vector is perpendicular\
  \ to the level surface corresponding to</span> <span m='251000'>setting the function,\
  \ w, equal to a constant.</span> <span m='258000'>OK, so if I draw a contour plot\
  \ of my function,</span> <span m='262000'>so, actually forget about z because I\
  \ want to draw a two</span> <span m='268000'>variable contour plot. So, say I have\
  \ a function of</span> <span m='272000'>two variables, x and y, then maybe it has\
  \ some</span> <span m='275000'>contour plot. And, I'm saying if I take the</span>\
  \ <span m='278000'>gradient of a function at this point, (x,y).</span> <span m='282000'>So,\
  \ I will have a vector. Well, if I draw that vector on</span> <span m='286000'>top\
  \ of a contour plot, it's going to end up being</span> <span m='291000'>perpendicular\
  \ to the level curve.</span> <span m='294000'>Same thing if I have a function of\
  \ three variables.</span> <span m='297000'>Then, I can try to draw its contour plot.</span>\
  \ <span m='299000'>Of course, I can't really do it because the contour plot would</span>\
  \ <span m='303000'>be living in space with x, y, and z.</span> <span m='305000'>But,\
  \ it would be a bunch of level faces, and the gradient</span> <span m='309000'>vector\
  \ would be a vector in space.</span> <span m='311000'>That vector is perpendicular\
  \ to the level faces.</span> <span m='315000'>So, let's try to see that on a couple\
  \ of examples.</span> <span m='324000'>So, let's do a first example. What's the\
  \ easiest case?</span> <span m='332000'>Let's take a linear function of x, y, and\
  \ z.</span> <span m='336000'>So, I will take w equals a1 times x plus a2 times y\
  \ plus a3</span> <span m='342000'>times z. Well, so, what's the gradient</span>\
  \ <span m='347000'>of this function? Well, the first component will</span> <span\
  \ m='353000'>be a1. That's partial w partial x.</span> <span m='358000'>Then, a2,\
  \ that's partial w partial y, and a3,</span> <span m='363000'>partial w partial\
  \ z. Now, what is the levels of this?</span> <span m='375000'>Well, if I set w equal\
  \ to some constant, c, that means I look</span> <span m='382000'>at the points where\
  \ a1x a2y a3z equals c.</span> <span m='387000'>What kind of service is that? It's\
  \ a plane.</span> <span m='390000'>And, we know how to find a normal vector to this\
  \ plane just</span> <span m='399000'>by looking at the coefficients. So, it's a\
  \ plane with a normal</span> <span m='408000'>vector exactly this gradient. And,\
  \ in fact,</span> <span m='411000'>in a way, this is the only case you need to check\
  \ because of</span> <span m='415000'>linear approximations. If you replace a function\
  \ by</span> <span m='418000'>its linear approximation, that means you will replace\
  \ the</span> <span m='422000'>level surfaces by their tension planes.</span> <span\
  \ m='424000'>And then, you'll actually end up in this situation.</span> <span m='428000'>But\
  \ maybe that's not very convincing.</span> <span m='429000'>So, let's do another\
  \ example. So, let's do a second example.</span> <span m='445000'>Let's say we look\
  \ at the function x^2 y^2.</span> <span m='448000'>OK, so now it's a function of\
  \ just two variables because that</span> <span m='452000'>way we'll be able to actually\
  \ draw a picture for you.</span> <span m='456000'>OK, so what are the level sets\
  \ of this function?</span> <span m='460000'>Well, they're going to be circles, right?</span>\
  \ <span m='464000'>w equals c is a circle, x^2 y^2 = c.</span> <span m='474000'>So,\
  \ I should say, maybe, sorry,</span> <span m='478000'>the level curve is a circle.\
  \ So, the contour plot looks</span> <span m='488000'>something like that. Now, what's\
  \ the gradient vector?</span> <span m='496000'>Well, the gradient of this function,\
  \ so,</span> <span m='500000'>partial w partial x is 2x. And partial w partial y\
  \ is 2y.</span> <span m='506000'>So, let's say I take a point, x comma y, and I\
  \ try to draw my</span> <span m='511000'>gradient vector. So, here at x,</span>\
  \ <span m='514000'>y, so, I have to draw the vector, <2x,</span> <span m='518000'>2y>.\
  \ What does it look like?</span> <span m='521000'>Well, it's going in that direction.</span>\
  \ <span m='522000'>It's parallel to the position vector for this point.</span> <span\
  \ m='529000'>It's actually twice the position vector.</span> <span m='531000'>So,\
  \ I guess it goes more or less like this.</span> <span m='535000'>What's interesting,\
  \ too, is it is perpendicular to</span> <span m='541000'>this circle. OK, so it's\
  \ a general feature.</span> <span m='544000'>Actually, let me show you more examples,\
  \ oops,</span> <span m='550000'>not the one I want. So, I don't know if you can\
  \ see</span> <span m='556000'>it so well. Well, hopefully you can.</span> <span\
  \ m='559000'>So, here I have a contour plot of a function,</span> <span m='562000'>and\
  \ I have a blue vector. That's the gradient vector at</span> <span m='565000'>the\
  \ pink point on the plot. So, you can see,</span> <span m='568000'>I can move the\
  \ pink point, and the gradient vector,</span> <span m='572000'>of course, changes\
  \ because the gradient depends on x and y.</span> <span m='577000'>But, what doesn't\
  \ change is that it's always perpendicular</span> <span m='582000'>to the level\
  \ curves. Anywhere I am,</span> <span m='586000'>my gradient stays perpendicular\
  \ to the level curve.</span> <span m='593000'>OK, is that convincing? Is that visible\
  \ for people who</span> <span m='597000'>can't see blue? OK, so, OK, so we have\
  \ a lot of</span> <span m='605000'>evidence, but let's try to prove the theorem\
  \ because it will be</span> <span m='616000'>interesting. So, first of all,</span>\
  \ <span m='622000'>sorry, any questions about the statement, the example,</span>\
  \ <span m='630000'>anything, yes? Ah, very good question.</span> <span m='634000'>Does\
  \ the gradient vector, why is the gradient vector</span> <span m='637000'>perpendicular\
  \ in one direction rather than the other?</span> <span m='640000'>So, we'll see\
  \ the answer to that in a few minutes.</span> <span m='643000'>But let me just tell\
  \ you immediately, to the side,</span> <span m='646000'>which side it's pointing\
  \ to, it's always pointing towards</span> <span m='650000'>higher values of a function.\
  \ OK, and we'll see in that maybe</span> <span m='654000'>about half an hour. So,\
  \ well, let me say actually</span> <span m='663000'>points towards higher values\
  \ of w.</span> <span m='673000'>OK, any other questions? I don't see any questions.</span>\
  \ <span m='684000'>OK, so let's try to prove this theorem, at least this part of</span>\
  \ <span m='688000'>the theorem. We're not going to prove that</span> <span m='690000'>just\
  \ yet. That will come in a while.</span> <span m='698000'>So, well, maybe we want\
  \ to understand first what happens if</span> <span m='704000'>we move inside the\
  \ level curve, OK?</span> <span m='708000'>So, let's imagine that we are taking\
  \ a moving point that stays</span> <span m='712000'>on the level curve or on the\
  \ level surface.</span> <span m='715000'>And then, we know, well, what happens is\
  \ that the</span> <span m='720000'>function stays constant. But, we can also know\
  \ how</span> <span m='723000'>quickly the function changes using the chain rule\
  \ up there.</span> <span m='727000'>So, maybe the chain rule will actually be the\
  \ key to</span> <span m='731000'>understanding how the gradient vector and the motion\
  \ on the</span> <span m='735000'>level service relate. So, let's take a curve,</span>\
  \ <span m='743000'>r equals r of t, that stays inside,</span> <span m='751000'>well,\
  \ maybe I should say on the level surface,</span> <span m='762000'>w equals c. So,\
  \ let's think about what that</span> <span m='768000'>means. So, just to get you\
  \ used to</span> <span m='771000'>this idea, I'm going to draw a level surface of\
  \ a function of</span> <span m='775000'>three variables. OK, so it's a surface given\
  \ by</span> <span m='779000'>the equation w of x, y, z equals some constant,</span>\
  \ <span m='783000'>c. And, so now I'm going to have a</span> <span m='787000'>point\
  \ on that, and it's going to move on that</span> <span m='791000'>surface. So, I\
  \ will have some parametric</span> <span m='795000'>curve that lives on this surface.</span>\
  \ <span m='799000'>So, the question is, what's going to happen at any</span> <span\
  \ m='805000'>given time? Well, the first observation is</span> <span m='809000'>that\
  \ the velocity vector, what can I say about the</span> <span m='812000'>velocity\
  \ vector of this motion? It's going to be tangent to the</span> <span m='817000'>level\
  \ surface, right?</span> <span m='819000'>If I move on a surface, then at any point,</span>\
  \ <span m='822000'>my velocity is tangent to the curve.</span> <span m='825000'>But,\
  \ if it's tangent to the curve, then it's also tangent to</span> <span m='829000'>the\
  \ surface because the curve is inside the surface.</span> <span m='833000'>So, OK,\
  \ it's getting a bit cluttered.</span> <span m='836000'>Maybe I should draw a bigger\
  \ picture.</span> <span m='838000'>Let me do that right away here. So, I have my\
  \ level surface,</span> <span m='846000'>w equals c. I have a curve on that,</span>\
  \ <span m='851000'>and at some point, I'm going to have a certain</span> <span m='859000'>velocity.\
  \ So, the claim is that the</span> <span m='868000'>velocity, v, equals dr/dt is\
  \ tangent -- --</span> <span m='880000'>to the level, w equals c because it's tangent</span>\
  \ <span m='888000'>to the curve, and the curve is inside the</span> <span m='890000'>level,\
  \ OK?</span> <span m='892000'>Now, what else can we say? Well, we have,</span> <span\
  \ m='895000'>the chain rule will tell us how the value of w changes.</span> <span\
  \ m='903000'>So, by the chain rule, we have dw/dt.</span> <span m='912000'>So, the\
  \ rate of change of the value of w as I move along this</span> <span m='920000'>curve\
  \ is given by the dot product between the gradient and</span> <span m='928000'>the\
  \ velocity vector. And, so, well,</span> <span m='934000'>maybe I can rewrite it\
  \ as w dot v, and that should be,</span> <span m='943000'>well, what should it be?\
  \ What happens to the value of w</span> <span m='950000'>as t changes? Well, it\
  \ stays constant because</span> <span m='954000'>we are moving on a curve. That\
  \ curve might be</span> <span m='958000'>complicated, but it stays always on the\
  \ level,</span> <span m='962000'>w equals c. So, it's zero because w of t</span>\
  \ <span m='968000'>equals c, which is a constant. OK, is that convincing?</span>\
  \ <span m='978000'>OK, so now if we have a dot product that's zero,</span> <span\
  \ m='981000'>that tells us that these two guys are perpendicular.</span> <span m='985000'>So\
  \ -- So if the gradient vector is perpendicular to v,</span> <span m='997000'>OK,\
  \ that's a good start. We know that the gradient is</span> <span m='1004000'>perpendicular\
  \ to this vector tangent that's tangent to the</span> <span m='1008000'>level surface.\
  \ What about other vectors</span> <span m='1011000'>tangent to the level surface?\
  \ Well, in fact,</span> <span m='1015000'>I could use any curve drawn on the level\
  \ of w equals c.</span> <span m='1020000'>So, I could move, really, any way I wanted\
  \ on</span> <span m='1023000'>that surface. In particular,</span> <span m='1026000'>I\
  \ claim that I could have chosen my velocity vector to be</span> <span m='1031000'>any\
  \ vector tangent to the surface.</span> <span m='1035000'>OK, so let's write this.\
  \ So this is true for any curve,</span> <span m='1042000'>or, I'll say for any motion\
  \ on the level surface,</span> <span m='1050000'>w equals c. So that means v can\
  \ be any</span> <span m='1060000'>vector tangent to the surface tangent to the level.</span>\
  \ <span m='1073000'>See, for example, OK, let me draw one more</span> <span m='1081000'>picture.\
  \ OK, so I have my level surface.</span> <span m='1086000'>So, I'm drawing more\
  \ and more levels, and they never quite</span> <span m='1089000'>look the same.\
  \ But I have a point.</span> <span m='1092000'>And, at this point, I have the tangent\
  \ plane to the</span> <span m='1096000'>level surface. OK, so this is tangent plane\
  \ to</span> <span m='1104000'>the level. Then, if I choose any vector in</span>\
  \ <span m='1110000'>that tangent plane. Let's say I choose the one that</span> <span\
  \ m='1115000'>goes in that direction. Then, I can actually find a</span> <span m='1119000'>curve\
  \ that goes in that direction, and stays on the</span> <span m='1122000'>level.\
  \ So, here, that would be a curve</span> <span m='1125000'>that somehow goes from\
  \ the right to the left, and of course it</span> <span m='1130000'>has to end up\
  \ going up or something like that.</span> <span m='1133000'>OK, so given any vector\
  \ tangent -- -- let's call that vector v</span> <span m='1145000'>tangent to the\
  \ level, we get that the gradient is</span> <span m='1154000'>perpendicular to v.\
  \ So, if the gradient is</span> <span m='1160000'>perpendicular to this vector tangent\
  \ to this curve,</span> <span m='1164000'>but also to any vector, I can draw that\
  \ tangent to my</span> <span m='1168000'>surface. So, what does that mean?</span>\
  \ <span m='1169000'>Well, that means the gradient is actually perpendicular to the</span>\
  \ <span m='1174000'>tangent plane or to the surface at this point.</span> <span\
  \ m='1178000'>So, the gradient is perpendicular.</span> <span m='1202000'>And, well,\
  \ here, I've illustrated things with a</span> <span m='1204000'>three-dimensional\
  \ example, but really it works the same if</span> <span m='1206000'>you have only\
  \ two variables. Then you have a level curve</span> <span m='1210000'>that has a\
  \ tangent line, and the gradient is</span> <span m='1213000'>perpendicular to that\
  \ line. OK, any questions?</span> <span m='1223000'>No? OK, so, let's see.</span>\
  \ <span m='1236000'>That's actually pretty neat because there is a nice</span> <span\
  \ m='1239000'>application of this, which is to try to figure out,</span> <span m='1243000'>now\
  \ we know, actually, how to find the</span> <span m='1244000'>tangent plane to anything,\
  \ pretty much.</span> <span m='1273000'>OK, so let's see. So, let's say that,</span>\
  \ <span m='1279000'>for example, I want to find -- -- the</span> <span m='1287000'>tangent\
  \ plane -- -- to the surface with equation,</span> <span m='1302000'>let's say,\
  \ x^2 y^2-z^2 = 4 at the point (2,1,</span> <span m='1310000'>1). Let me write that.</span>\
  \ <span m='1321000'>So, how do we do that? Well, one way that we already</span>\
  \ <span m='1326000'>know, if we solve this for z,</span> <span m='1329000'>so we\
  \ can write z equals a function of x and y,</span> <span m='1332000'>then we know\
  \ tangent plane approximation for the graph of a</span> <span m='1336000'>function,\
  \ z equals some function of x and</span> <span m='1339000'>y. But, that doesn't\
  \ look like</span> <span m='1341000'>it's the best way to do it. OK, the best way\
  \ to it,</span> <span m='1344000'>now that we have the gradient vector, is actually\
  \ to directly</span> <span m='1347000'>say, oh, we know the normal vector to this\
  \ plane.</span> <span m='1350000'>The normal vector will just be the gradient.</span>\
  \ <span m='1355000'>Oh, I think I have a cool picture to show.</span> <span m='1360000'>OK,\
  \ so that's what it looks like.</span> <span m='1362000'>OK, so here you have the\
  \ surface x2 y2-z2 equals four.</span> <span m='1369000'>That's called a hyperboloid\
  \ because it looks like when you</span> <span m='1372000'>get when you spin a hyperbola\
  \ around an axis.</span> <span m='1375000'>And, here's a tangent plane at the given\
  \ point.</span> <span m='1380000'>So, it doesn't look very tangent because it crosses\
  \ the</span> <span m='1382000'>surface. But, it's really,</span> <span m='1384000'>if\
  \ you think about it, you will see it's really the</span> <span m='1388000'>plane\
  \ that's approximating the surface in the best way that you</span> <span m='1392000'>can\
  \ at this given point. It is really the tangent plane.</span> <span m='1398000'>So,\
  \ how do we find this plane? Well, you can plot it on a</span> <span m='1407000'>computer.\
  \ That's not exactly how you</span> <span m='1410000'>would look for it in the first\
  \ place.</span> <span m='1413000'>So, the way to do it is that we compute the gradient.</span>\
  \ <span m='1418000'>So, a gradient of what? Well, a gradient of this</span> <span\
  \ m='1423000'>function. OK, so I should say,</span> <span m='1429000'>this is the\
  \ level set, w equals four,</span> <span m='1436000'>where w equals x^2 y^2 - z^2.\
  \ And so, we know that the</span> <span m='1447000'>gradient of this, well, what\
  \ is it?</span> <span m='1454000'>2x, then 2y, and then negative 2z.</span> <span\
  \ m='1462000'>So, at this given point, I guess we are at x equals two.</span> <span\
  \ m='1467000'>So, that's four. And then, y and z are one.</span> <span m='1469000'>So,\
  \ two, negative two. OK, and that's going to be the</span> <span m='1477000'>normal\
  \ vector to the surface or to the tangent plane.</span> <span m='1484000'>That's\
  \ one way to define the tangent plane.</span> <span m='1487000'>All right, it has\
  \ the same normal vector as the surface.</span> <span m='1490000'>That's one way\
  \ to define the normal vector to the surface,</span> <span m='1492000'>if you prefer.\
  \ Being perpendicular to the</span> <span m='1496000'>surface means that you are\
  \ perpendicular to its tangent</span> <span m='1501000'>plane. OK, so the equation\
  \ is,</span> <span m='1505000'>well, 4x 2y-2z equals something, where something\
  \ is,</span> <span m='1512000'>well, we should just plug in that point.</span> <span\
  \ m='1519000'>We'll get eight plus two minus two looks like we'll get eight.</span>\
  \ <span m='1526000'>And, of course, we could simplify dividing</span> <span m='1529000'>everything\
  \ by two, but it's not very important</span> <span m='1532000'>here. OK, so now\
  \ if you have a</span> <span m='1534000'>surface given by an evil equation,</span>\
  \ <span m='1536000'>and a point on the surface, well, you know how to find the</span>\
  \ <span m='1540000'>tangent plane to the surface at that point.</span> <span m='1544000'>OK,\
  \ any questions? No.</span> <span m='1552000'>OK, let me give just another reason\
  \ why, another way that we</span> <span m='1560000'>could have seen this. So, I\
  \ claim,</span> <span m='1564000'>in fact, we could have done this without the gradient,</span>\
  \ <span m='1567000'>or using the gradient in a somehow disguised way.</span> <span\
  \ m='1569000'>So, here's another way. So, the other way to do it</span> <span m='1578000'>would\
  \ be to start with a differential,</span> <span m='1582000'>OK? dw, while it's pretty\
  \ much the</span> <span m='1586000'>same content, but let me write it as a</span>\
  \ <span m='1591000'>differential, dw is 2xdx 2ydy-2zdz.</span> <span m='1595000'>So,\
  \ at a given point, at (2,1, 1),</span> <span m='1604000'>this is 4dx 2dy-2dz. Now,\
  \ if we want to change this</span> <span m='1612000'>into an approximation formula,\
  \ we can.</span> <span m='1616000'>We know that the change in w is approximately\
  \ equal to 4 delta x</span> <span m='1627000'>2 delta y - 2 delta z. OK, so when\
  \ do we stay on the</span> <span m='1635000'>level surface? Well, we stay on the\
  \ level</span> <span m='1639000'>surface when w doesn't change, so, when this becomes\
  \ zero,</span> <span m='1644000'>OK? Now, what does this</span> <span m='1645000'>approximation\
  \ sign mean? Well, it means for small</span> <span m='1648000'>changes in x, y,\
  \ z, this guy will be close to</span> <span m='1651000'>that guy. It also means\
  \ something else.</span> <span m='1653000'>Remember, these approximation formulas,\
  \ they are linear</span> <span m='1656000'>approximations. They mean that we replace\
  \ the</span> <span m='1659000'>function, actually, by some closest linear formula</span>\
  \ <span m='1663000'>that will be nearby. And so, in particular,</span> <span m='1667000'>if\
  \ we set this equal to zero instead of approximately zero,</span> <span m='1672000'>it\
  \ means we'll actually be moving on the tangent plane to</span> <span m='1676000'>the\
  \ level set. If you want strict equalities</span> <span m='1679000'>in approximations\
  \ means that we replace the function by its</span> <span m='1683000'>tangent approximation.</span>\
  \ <span m='1717000'>So -- [APPLAUSE] OK, so the level corresponds to</span> <span\
  \ m='1724000'>delta w equals zero, and its tangent plane</span> <span m='1733000'>corresponds\
  \ to four delta x plus two delta y minus two delta z</span> <span m='1743000'>equals\
  \ zero. That's what I'm trying to say,</span> <span m='1748000'>basically. And,\
  \ what's delta x?</span> <span m='1750000'>Well, that means it's the change in x.</span>\
  \ <span m='1752000'>So, what's the change in x here? That means, well,</span> <span\
  \ m='1755000'>we started with x equals two, and we moved to some other</span> <span\
  \ m='1759000'>value, x. So, that's actually x- 2, right?</span> <span m='1765000'>That's\
  \ how much x has changed compared to 2.</span> <span m='1768000'>And, two times\
  \ (y - 1) minus two times z - 1 = 0.</span> <span m='1777000'>That's the equation\
  \ of a tangent plane.</span> <span m='1782000'>It's the same equation as the one\
  \ over there.</span> <span m='1786000'>These are just two different methods to get\
  \ it.</span> <span m='1788000'>OK, so this one explains to you what's going on in\
  \ terms of</span> <span m='1792000'>approximation formulas. This one goes right\
  \ away,</span> <span m='1797000'>by using the gradient factor. So, in a way,</span>\
  \ <span m='1802000'>with this one, you don't have to think nearly</span> <span m='1806000'>as\
  \ much. But, you can use either one.</span> <span m='1811000'>OK, questions? No?</span>\
  \ <span m='1817000'>OK, so let's move on to new topic, which is another</span> <span\
  \ m='1823000'>application of a gradient vector, and that is directional</span> <span\
  \ m='1830000'>derivatives.</span> <span m='1844000'>OK, so let's say that we have\
  \ a function of two variables,</span> <span m='1852000'>x and y. Well, we know how\
  \ to compute</span> <span m='1856000'>partial w over partial x or partial w over\
  \ partial y,</span> <span m='1862000'>which measure how w changes if I move in the\
  \ direction of the x</span> <span m='1867000'>axis or in the direction of the y\
  \ axis.</span> <span m='1870000'>So, what about moving in other directions?</span>\
  \ <span m='1873000'>Well, of course, we've seen other approximation</span> <span\
  \ m='1876000'>formulas and so on. But, we can still ask,</span> <span m='1878000'>is\
  \ there a derivative in every direction?</span> <span m='1881000'>And that's basically,\
  \ yes, that's the directional</span> <span m='1885000'>derivative. OK, so these\
  \ are derivatives in</span> <span m='1890000'>the direction of I hat or j hat, the\
  \ vectors that go along the x</span> <span m='1900000'>or the y axis. So, what if\
  \ we move in another</span> <span m='1910000'>direction, let's say, the direction\
  \ of some unit</span> <span m='1921000'>vector, let's call it u . OK, so if I give\
  \ you a unit</span> <span m='1929000'>vector, you can ask yourself, if I move in\
  \ the direction,</span> <span m='1933000'>how quickly will my function change?</span>\
  \ <span m='1936000'>So -- So, let's look at the straight trajectory.</span> <span\
  \ m='1949000'>What this should mean is I start at some value,</span> <span m='1954000'>x,\
  \ y, and there I have my vector u.</span> <span m='1957000'>And, I'm going to move\
  \ in a straight line in the direction</span> <span m='1961000'>of u. And, I have\
  \ the graph of my</span> <span m='1966000'>function -- -- and I'm asking myself\
  \ how quickly does the</span> <span m='1974000'>value change when I move on the\
  \ graph in that direction?</span> <span m='1982000'>OK, so let's look at a straight\
  \ line trajectory So,</span> <span m='1990000'>we have a position vector, r, that\
  \ will depend on some</span> <span m='1998000'>parameter which I will call s. You'll\
  \ see why very soon,</span> <span m='2006000'>in such a way that the derivative\
  \ is this given unit</span> <span m='2010000'>vector u hat. So, why do I use s for\
  \ my</span> <span m='2013000'>parameter rather than t. Well, it's a convention.</span>\
  \ <span m='2016000'>I'm moving at unit speed along this line.</span> <span m='2021000'>So\
  \ that means that actually, I'm parameterizing things by</span> <span m='2025000'>the\
  \ distance that I've traveled along a curve,</span> <span m='2028000'>sorry, along\
  \ this line. So, here it's called s in the</span> <span m='2034000'>sense of arc\
  \ length. Actually, it's not really an</span> <span m='2039000'>arc because it's\
  \ a straight line, so it's the distance along</span> <span m='2046000'>the line.\
  \ OK, so because we are</span> <span m='2049000'>parameterizing by distance, we\
  \ are just using s as a</span> <span m='2055000'>convention just to distinguish\
  \ it from other situations.</span> <span m='2061000'>And, so, now, the question\
  \ will be,</span> <span m='2067000'>what is dw/ds? What's the rate of change of\
  \ w</span> <span m='2072000'>when I move like that? Well, of course we know the</span>\
  \ <span m='2076000'>answer because that's a special case of the chain rule.</span>\
  \ <span m='2080000'>So, that's how we will actually compute it.</span> <span m='2084000'>But,\
  \ in terms of what it means, it really means we are asking</span> <span m='2089000'>ourselves,\
  \ we start at a point and we</span> <span m='2091000'>change the variables in a\
  \ certain direction,</span> <span m='2094000'>which is not necessarily the x or\
  \ the y direction,</span> <span m='2097000'>but really any direction. And then,\
  \ what's the derivative</span> <span m='2101000'>in that direction? OK, does that\
  \ make sense as a</span> <span m='2107000'>concept? Kind of?</span> <span m='2108000'>I\
  \ see some faces that are not completely convinced.</span> <span m='2110000'>So,\
  \ maybe you should show more pictures.</span> <span m='2114000'>Well, let me first\
  \ write down a bit more and show you something.</span> <span m='2140000'>So I just\
  \ want to give you the actual definition.</span> <span m='2145000'>Sorry, first\
  \ of all in case you wonder what this is all about,</span> <span m='2150000'>so\
  \ let's say the components of our unit vector are two numbers,</span> <span m='2155000'>a\
  \ and b. Then, it means we'll move along</span> <span m='2160000'>the line x of\
  \ s equals some initial value,</span> <span m='2165000'>the point where we are actually\
  \ at the directional derivative</span> <span m='2169000'>plus s times a, or I meant\
  \ to say plus a times</span> <span m='2173000'>s. And, y of s equals y0 bs.</span>\
  \ <span m='2179000'>And then, we plug that into w. And then we take the derivative.</span>\
  \ <span m='2198000'>So, we have a notation for that which is going to be dw/ds with</span>\
  \ <span m='2205000'>a subscript in the direction of u to indicate in which direction</span>\
  \ <span m='2213000'>we are actually going to move. And, that's called the</span>\
  \ <span m='2223000'>directional derivative -- -- in the direction of u.</span> <span\
  \ m='2237000'>OK, so, let's see what it means geometrically.</span> <span m='2248000'>So,\
  \ remember, we've seen things about partial</span> <span m='2253000'>derivatives,\
  \ and we see that the partial</span> <span m='2256000'>derivatives are the slopes\
  \ of slices of the graph by vertical</span> <span m='2261000'>planes that are parallel\
  \ to the x or the y directions.</span> <span m='2265000'>OK, so, if I have a point,\
  \ at any point,</span> <span m='2268000'>I can slice the graph of my function by\
  \ two planes,</span> <span m='2272000'>one that's going along the x, one along the\
  \ y direction.</span> <span m='2277000'>And then, I can look at the slices of the\
  \ graph.</span> <span m='2282000'>Let me see if I can use that thing.</span> <span\
  \ m='2284000'>So, we can look at the slices of the graph that are drawn</span> <span\
  \ m='2287000'>here. In fact, we look at the tangent</span> <span m='2290000'>lines\
  \ to the slices, and we look at the slope and</span> <span m='2294000'>that gives\
  \ us the partial derivatives in case you are on</span> <span m='2297000'>that side\
  \ and want to see also the pointer that was here.</span> <span m='2301000'>So, now,\
  \ similarly, the directional derivative</span> <span m='2306000'>means, actually,\
  \ we'll be slicing our graph by</span> <span m='2311000'>the vertical plane. It's\
  \ not really colorful,</span> <span m='2317000'>something more colorful. We'll be\
  \ slicing things by a</span> <span m='2323000'>plane that is now in the direction\
  \ of this vector,</span> <span m='2326000'>u, and we'll be looking at the slope\
  \ of the slice of the graph.</span> <span m='2331000'>So, what that looks like here,\
  \ so that's the same applet the</span> <span m='2337000'>way that you've used on\
  \ your problem set in case you are</span> <span m='2343000'>wondering. So, now,\
  \ I'm picking a point on</span> <span m='2348000'>the contour plot. And, at that\
  \ point,</span> <span m='2352000'>I slice the graph. So, here I'm starting by</span>\
  \ <span m='2355000'>slicing in the direction of the x axis.</span> <span m='2357000'>So,\
  \ in fact, what I'm measuring here by the</span> <span m='2360000'>slope of the\
  \ slice is the partial in the x direction.</span> <span m='2364000'>It's really\
  \ partial f partial x, which is also the directional</span> <span m='2368000'>derivative\
  \ in the direction of i.</span> <span m='2371000'>And now, if I rotate the slice,\
  \ then I have all of these</span> <span m='2377000'>planes. So, you see at the bottom\
  \ left,</span> <span m='2380000'>I have the direction in which I'm going.</span>\
  \ <span m='2382000'>There's this, like, rotating line that tells</span> <span m='2384000'>you\
  \ in which direction I'm going to be moving.</span> <span m='2387000'>And for each\
  \ direction, I have a plane.</span> <span m='2389000'>And, when I slice by that\
  \ plane, I will get,</span> <span m='2392000'>so I have this direction here going\
  \ maybe to the southwest.</span> <span m='2396000'>So, that gives me a slice of\
  \ my graph by a vertical plane,</span> <span m='2400000'>and the slice has a certain\
  \ slope.</span> <span m='2403000'>And, the slope is going to be the directional\
  \ derivative in</span> <span m='2408000'>that direction. OK, I think that's as graphic</span>\
  \ <span m='2414000'>as I can get. OK, any questions about that?</span> <span m='2422000'>No?\
  \ OK, so let's see how we compute</span> <span m='2433000'>that guy. So, let me\
  \ just write again</span> <span m='2441000'>just in case you want to, in case you\
  \ didn't hear me it's</span> <span m='2449000'>the slope of the slice of the graph\
  \ by a vertical plane -- --</span> <span m='2458000'>that contains the given direction,</span>\
  \ <span m='2463000'>that's parallel to the direction, u.</span> <span m='2466000'>So,\
  \ how do we compute it? Well, we can use the chain rule.</span> <span m='2471000'>The\
  \ chain rule implies that dw/ds is actually the gradient</span> <span m='2482000'>of\
  \ w dot product with the velocity vector dr/ds.</span> <span m='2491000'>But, remember\
  \ we say that we are going to be moving at unit</span> <span m='2495000'>speed in\
  \ the direction of u. So, in fact,</span> <span m='2499000'>that's just gradient\
  \ w dot product with the unit vector u.</span> <span m='2510000'>OK, so the formula\
  \ that we remember is really dw/ds in the</span> <span m='2517000'>direction of\
  \ u is gradient w dot product of u.</span> <span m='2523000'>And, maybe I should\
  \ also say in words, this is the component of</span> <span m='2533000'>the gradient\
  \ in the direction of u.</span> <span m='2539000'>And, maybe that makes more sense.</span>\
  \ <span m='2541000'>So, for example, the directional derivative in</span> <span\
  \ m='2545000'>the direction of I hat is the component along the x axes.</span> <span\
  \ m='2549000'>That's the same as, indeed, the partial derivatives</span> <span m='2552000'>in\
  \ the x direction. Things make sense.</span> <span m='2560000'>dw/ds in the direction\
  \ of I hat is, sorry, gradient w dot I hat,</span> <span m='2570000'>which is wx,maybe\
  \ I should write, partial w of partial x.</span> <span m='2579000'>OK, now, so that's\
  \ basically what we need to know to compute</span> <span m='2589000'>these guys.\
  \ So now, let's go back to the</span> <span m='2592000'>gradient and see what this\
  \ tells us about the gradient.</span> <span m='2622000'>[APPLAUSE] I see you guys\
  \ are having fun.</span> <span m='2631000'>OK, OK, let's do a little bit of geometry\
  \ here.</span> <span m='2634000'>That should calm you down. So, we said dw/ds in\
  \ the</span> <span m='2640000'>direction of u is gradient w dot u.</span> <span\
  \ m='2644000'>That's the same as the length of gradient w times the length</span>\
  \ <span m='2651000'>of u. Well, that happens to be one</span> <span m='2655000'>because\
  \ we are taking the unit vector times the cosine of the</span> <span m='2663000'>angle\
  \ between the gradient and the given unit vector,</span> <span m='2670000'>u, so,\
  \ have this angle, theta. OK, that's another way of</span> <span m='2676000'>saying\
  \ we are taking the component of a gradient in the</span> <span m='2679000'>direction\
  \ of u. But now, what does that tell us?</span> <span m='2683000'>Well, let's try\
  \ to figure out in</span> <span m='2686000'>which directions w changes the fastest,</span>\
  \ <span m='2690000'>in which direction it increases the most or decreases the most,</span>\
  \ <span m='2694000'>or doesn't actually change. So, when is this going to be</span>\
  \ <span m='2703000'>the largest? If I fix a point,</span> <span m='2705000'>if I\
  \ set a point, then the gradient vector at</span> <span m='2709000'>that point is\
  \ given to me. But, the question is,</span> <span m='2712000'>in which direction\
  \ does it change the most quickly?</span> <span m='2715000'>Well, what I can change\
  \ is the direction, and this will be the</span> <span m='2719000'>largest when the\
  \ cosine is one. So, this is largest when the</span> <span m='2725000'>cosine of\
  \ the angle is one. That means the angle is zero.</span> <span m='2733000'>That\
  \ means u is actually in the direction of the gradient.</span> <span m='2740000'>OK,\
  \ so that's a new way to think about the direction of a</span> <span m='2742000'>gradient.\
  \ The gradient is the direction</span> <span m='2747000'>in which the function increases\
  \ the most quickly at that point.</span> <span m='2757000'>So, the direction of\
  \ gradient w is the direction of fastest</span> <span m='2768000'>increase of w\
  \ at the given point.</span> <span m='2775000'>And, what is the magnitude of w?\
  \ Well, it's actually the</span> <span m='2784000'>directional derivative in that\
  \ direction.</span> <span m='2793000'>OK, so if I go in that direction, which gives\
  \ me the</span> <span m='2797000'>fastest increase, then the corresponding slope</span>\
  \ <span m='2800000'>will be the length of the gradient.</span> <span m='2804000'>And,\
  \ with the direction of the fastest decrease?</span> <span m='2811000'>It's going\
  \ in the opposite direction, right?</span> <span m='2813000'>I mean, if you are\
  \ on a mountain, and you know that you</span> <span m='2815000'>are facing the mountain,\
  \ that's the direction of fastest</span> <span m='2817000'>increase. The direction\
  \ of fastest</span> <span m='2819000'>decrease is behind you straight down.</span>\
  \ <span m='2821000'>OK, so, the minimal value of dw/ds is achieved when cosine of</span>\
  \ <span m='2831000'>theta is minus one. That means theta equals 180\uFFFD.</span>\
  \ <span m='2838000'>That means u is in the direction of minus the gradient.</span>\
  \ <span m='2847000'>It points opposite to the gradient.</span> <span m='2850000'>And,\
  \ finally, when do we have dw/ds equals</span> <span m='2863000'>zero? So, in which\
  \ direction does the</span> <span m='2868000'>function not change? Well, we have\
  \ two answers to</span> <span m='2872000'>that. One is to just use the formula.</span>\
  \ <span m='2874000'>So, that's one cosine theta equals zero.</span> <span m='2878000'>That\
  \ means theta equals 90 degrees. That means that u is</span> <span m='2883000'>perpendicular\
  \ to the gradient. The other way to think about</span> <span m='2888000'>it, the\
  \ direction in which the value doesn't change is a</span> <span m='2891000'>direction\
  \ that's tangent to the level surface.</span> <span m='2894000'>If we are not changing\
  \ a, it means we are moving along</span> <span m='2898000'>the level. And, that's\
  \ the same thing --</span> <span m='2904000'>-- as being tangent to the level.</span>\
  \ <span m='2910000'>So, let me just show that on the picture here.</span> <span\
  \ m='2916000'>So, if actually show you the gradient, you can't really see</span>\
  \ <span m='2919000'>it here. I need to move it a bit.</span> <span m='2921000'>So,\
  \ the gradient here is pointing straight up at the</span> <span m='2924000'>point\
  \ that I have chosen. Now, if I choose a slice that's</span> <span m='2930000'>perpendicular,\
  \ and a direction that's</span> <span m='2932000'>perpendicular to the gradient,\
  \ so that's actually tangent to</span> <span m='2935000'>the level curve, then you\
  \ see that my slice is</span> <span m='2937000'>flat. I don't actually have any\
  \ slop.</span> <span m='2940000'>The directional derivative in a direction that's\
  \ perpendicular</span> <span m='2944000'>to the gradient is basically zero.</span>\
  \ <span m='2946000'>Now, if I rotate, then the slope sort of</span> <span m='2948000'>increases,\
  \ increases, increases, and it becomes the</span> <span m='2951000'>largest when\
  \ I'm going in the direction of a gradient.</span> <span m='2954000'>So, here, I\
  \ have, actually, a pretty big slope.</span> <span m='2957000'>And now, if I keep\
  \ rotating, then the slope will decrease</span> <span m='2960000'>again. Then it\
  \ becomes zero when I</span> <span m='2962000'>perpendicular, and then it becomes\
  \ negative.</span> <span m='2965000'>It's the most negative when I pointing away\
  \ from the gradient</span> <span m='2969000'>and then becomes zero again when I'm\
  \ back perpendicular.</span> <span m='2973000'>OK, so for example, if I give you\
  \ a contour plot,</span> <span m='2978000'>and I ask you to draw the direction of\
  \ the gradient</span> <span m='2981000'>vector, well, at this point,</span> <span\
  \ m='2983000'>for example, you would look at the picture.</span> <span m='2986000'>The\
  \ gradient vector would be going perpendicular to the</span> <span m='2989000'>level.\
  \ And, it would be going towards</span> <span m='2992000'>higher values of a function.\
  \ I don't know if you can see the</span> <span m='2995000'>labels, but the thing\
  \ in the middle is a minimum.</span> <span m='2997000'>So, it will actually be pointing\
  \ in this kind of</span> <span m='3003000'>direction. OK, so that's it for today.</span>\
  \ </p>"
type: course
uid: 83f3db401bd399a271d4d5c2ccc9ab7c

---
None