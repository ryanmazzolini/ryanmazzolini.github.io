---
id: 146
title: Experiences with OpenVDB
date: 2015-03-11T10:07:30+00:00
author: ryan
layout: post
guid: http://www.rmazzolini.com/?p=146
permalink: /experiences-with-openvdb/
image: /wp-content/uploads/2015/03/voxels.png
categories:
  - Masters
  - Programming
  - Research
---
The topic I chose for my Msc. is &#8220;_procedural generation using voxels and cellular automata&#8221;_. That&#8217;s computer science jargon for _&#8220;using colourful virtual cubes and lots of rules to make the cubes do cool stuff&#8221;_. However, the details of my research is not the topic of this blog-post. This blog post is about my experiences with the voxel (or volumetric element aka. 3D cube) library, OpenVDB.

OpenVDB is an open-source c++ library that manages voxels. When I started using the library it was early 2013. OpenVDB was not fully released, it had not been integrated into any other platforms and only a handful of people were using it. By 2015 things have changed drastically. OpenVDB has [won awards](http://www.prnewswire.com/news-releases/dreamworks-animation-wins-two-technical-achievement-awards-from-the-academy-of-motion-picture-arts-and-sciences-300032539.html), been [integrated into many art tools](http://blenderdiplom.com/en/interviews/574-interview-ken-museth-on-openvdb.html) and is even [starting to be looked at by game developers](http://www.drewskillman.com/gdc2015_vfxroundtable.pdf). Things are looking good for OpenVDB.  
Overall I think my experiences with the library are pretty good, and I am quite happy with what I have achieved with it. However, that did not come without its own trials for me. From poor response to my noob questions on their forums and my low c++ proficiency (coding in c++ and _&#8220;knowing&#8221;_ c++ are two very different things I learnt), I struggled to get to grips with the library.

I think I made two mistakes here:  
Firstly, learning to code well in c++ as well as learning the new c++11 standards is challenging. Learning this, while messing around with a complex templated library (while trying to figure out if you actually want to use it) is pretty daunting. It took me far longer to get to grips with than I thought it would.  
Secondly, OpenVDB was new and there were/are not a hell of alot of people using it. Tie this with the fact that I wanted to use the library in ways it isn&#8217;t focused on, and I was kind of on my own. I had to learn how to extend the library to incorporate colour and texture maps, something the library would not magically do for me.

Looking back I think it might have been better to use my own data-structure to learn, and then switched over once I had figured out where or how my research was going. On the other hand, the little system I built is using a fantastic library which I have only scratched the surface of. I even started trying to help new noobs on the forums with things I went through.

Yes, I probably should have used a game engine and tools I am more familiar with, but there are two experiences I wouldn&#8217;t take back:  
The first is a humbling experience. I came to terms with not being a rock-star programmer (I have my doubts they even exist).  
Secondly, once I was humbled, I learned to enjoy programming for what I could make. Not how I made it.

Besides that cliché moral lesson, I think being thrown in the deep-end really helped me conquer my programming fears. I&#8217;m excited to sink my teeth into a new challenge!