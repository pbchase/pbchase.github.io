---
title: "State of the Bar Art - September 2018"
excerpt: ""
tags:
  - kites
  - land kiting
  - kite buggy
  - kite bar
  - bar
---

![](/images/bundled-bar.jpg "A bundled bar")

I've had made a lot of changes to the way my bars and harness are built in the past year. I've covered the harness in recent articles, but I haven't said much about the bar save for [Printing a moveable stopper](../printing-a-moveable-stopper/) in June of this year. Some of the revisions are described in [3D models of components for kite control bars](https://github.com/pbchase/kite_bar_parts) though that is focused more on the models than explaining why they are the way they are and how they work with everything else. I hope this post can shine some light on recent developments with a nod toward the overall design concepts.

## Magnetic trimline tail

In earlier designs the tail of the trim line was tethered to ring that rode between the moveable stopper and the cleat. This worked well pretty well to keep the trim line from tangling in other things, but it prevented large, swift changes in trim.  

![](/images/ring-tethered-trim-line.jpg "A trim line end tethered with a ring")

To get those quick trim changes you have to free the end of the trim line. The problem is keeping the tail out of troubled when you're not holding it. To address this, I resorted to magnets. I've seen these go to hell from corrosion on kite surfing bars, but so far I have had no issues. I've used only nickle-plated neodymium magnets to improve my corrosion resistance. I don't rinse my bars after use, but neither do I go into the ocean so it's unclear if I am smart or just lucky.

The first set of magnets goes into the tail of the trim line. I use a pair of flat, round neodymium magnets about 3mm x 15mm. The magnets sit edge-to-edge just below the end of the trim line wrapped in peel-and-stick insignia cloth that reaches from below the lower magnet to about 30mm up the trim line. I stitch the cloth to the trim line to make sure it doesn't creep.

![](/images/magnetic-trimline-end.jpg "A magnetic trim line end")

The magnetic trim line is at best half the solution as the magnet needs something to stick to. As my bars had no ferromagnetic steel in them much less magnets, I had to add that. I've had good results with a jacket of ferromagnetic stainless steel wrapped around the sides of the cleat portion of the ClamCleat. McMaster-Carr sells ferromagnetic [430 Stainless Steel Sheets](https://www.mcmaster.com/1294t33) that can be cut, drilled and bent to form a U-shaped jacket around the cleat. There's a little bit of an electrolytic reaction between the aluminum cleat and the stainless steel, but it appears to be slow. The jacket allows the trim line to stick to either side of the cleat in any orientation. The end of the trimline stays out of the jaw of the cleat and out of the path of the flag line.

![](/images/cleat-jacket.jpg "A stainless steel jacket for the cleat")

![](/images/jacketed-cleat.jpg "A jacketed ClamCleat")

To provide an alternative way to tether the trimline end, I also placed another neodymium magnet in the moveable stopper. I use a 3/8 inch x 3/8 inch cylindrical magnet pressed into the center of the stopper. The magnet is exposed on the face opposite the flag line to keep it from pinching or impeding the motion of the flag line or the stopper. 

![](/images/magnet-in-the-stopper.jpg "The magnet in the stopper")


## Separation blocks

I refer to the juncture of the flying lines, trimline and flag line as the _separation block_. It has narrow passagesways for the flying to pass through, room to anchor the flying lines with larkshead stoppers, and a pulley for the trim line. In my earlier designs I used a segment of 5mm Spectra/Dyneema as the pulley. While this works, the trim line slowly saws through the "pulley". Despite the block's relative simplicity, machining it from Delrin is time consuming and error prone. 

![](/images/old-and-busted-separation-block.jpg "Old-and-busted separation block")

To address flaws in the pulley and simplify the manufacture of the block, I now 3D-print the separation block. The new design is smaller, more comfortable to grip and easier to make. Instead of a loop of line for the pulley I use a low-friction ring held by a line that passes through a single hole in the block. The design is well balanced, has low friction for the trim line won't wear out as fast. 

![](/images/new-hotness-separation-block.jpg "Modern separation block with ring")


## Elastic flag line

My bars incorporate a 4.5 line to allow the kite to flag out on one of the top lines when released. This flag line connects to one of the flying lines on the flyer's side of the separation block, passes through a guide-path in the stopper, through the bar and terminates in a cotter pin release just below the bar. The cotter pin is designed to connect to a loop or ring on the backside of the snap hook on the flyer's harness. 

![](/images/flag-line-at-separation-block.jpg "The flag line meets the flying line")

To keep the flag line from tangling in the cleat, stopper or other rigging, the line has an elastic core to keep it taught when the trim is pulled in. Yet the line is sized to allow the trim to go all the way out as well. This is a difficult constraint. Getting it right requires some planning and math that is best saved for another article. To assure the flag line doesn't bunch up and jam in a narrow passageway, the jacket of the flag line has to be sewn to the elastic core while the flag line is fully stretched. This keeps the slack length of the jacket evenly distributed along the flag line. This is challenging sewing operation I have only been able to do on [Tim Elverston](http://windfiredesigns.com/)'s commercial straight-stitch sewing machine. 

![](/images/flag-line-passing-through-the-stopper.jpg "The flag line passes through the stopper under tension")

The end of the flag line provides both an attachment to the harness and quick release should the flyer need to separate from the flagged kite in an emergency. 

![](/images/flag-line-end.jpg "The flag line's lower end")

![](/images/flag-line-connected.jpg "The flag line connected to the snaphook on the harness")


## Moveable Stopper

As with the separation block, the components of the movable stopper have always been hard to machine accurately from Delrin. The task has gotten worse with every feature added to the stoppers. In June I finally gave up on the idea of machining the stopper. I set aside the initial design that Andrew Beattie did in April of 2016 and started from scratch. The design has morphed 20 times since and now looks radically different. 

![](/images/stopper_block_v4.jpg "Stopper Block V4")

The stopper block provides two pathways for the doubled trim line. If forces the lines apart on the flyer side, then back together on the cleat side. A stopper ball just below the block squeezes the trim lines back together to prevent the pressure of the bar from moving the block. A cross bore through the stopper provides an attachment point for attaching the ball to the stopper. The curved path of the cross bore allows the bungee that connects the ball to the stopper to move freely and balance the tension in the bungee. 

The 360-degree flange provides a continous surface to push the stopper away no matter its orientation. A large bore in the flange provides a pathway for the elastic flag line. On the opposite side of the block is a socket for a neodymium magnet. This magnet provides an additional location to the tether the trim line. Placing it opposite the flag line path keeps the trim line away from the flag. As the block can be oriented relative to the cleat, the flag line pathway through the flange also directs the flag line to the underside of the cleat away from the cleat's jaws. 

![](/images/stopper_ball.jpg "Stopper Ball")

The stopper ball sits a few millimeters below the stopper block connected via a short segment of bungee. After the trim lines emerge from the block they are both routed though the center bore of the ball. 

When the bar presses the ball upwards against the block, the ball and block form a kink in the trim line that completely stops the ball's movement. The connection between the block is 115mm (?) of 1/8" diameter bungee. The bungee is routed through curved paths in both the block and the ball. The path forms a continuous loop of bungee. The ends of the bungee are cut blunt and super-glued together to ease the movement through the pathways and eliminate knots.

![](/images/block_and_ball_kink_a_trimline.jpg "Block and ball work together to kink the trim line")

The lower, hemispherical portion of the ball is designed to mate with the round center-bore of the bar. These surfaces allow the bar to spin freely about the ball. The hemisphere is notched on one side to provide a path for the flag line. The notch is deep enough allow the flag line to move past the ball and through the bar even when the bar presses tightly against the ball. Similarly, the notch prevents the flag line from impeding bar spins. 

![](/images/flagline_passes_through_ball_notch.jpg "The flag line passes through the flange and the ball notch")

The routing path for the bungee controls the ball's orientation relative to the block. This allows the flag line notch in the ball to be permanently aligned with the flag line path in the block. This passively aligns the flag line with the notch  to ensure a straight, unimpeded path through stopper components and bar. 


## Bar assembly and threading line

All of these components are assembled on a trimline of 5mm Amsteel Blue. The trim line is about 2300mm in length. The trim line magnets have to be affixed to one end. The other end will need to be threaded through some long, narrow passage ways in the cleat and stopper. To simplify this work, a bit of insignia is wrapped around the end of the trimline. Cut about 4 lines diameters (20mm) wide and 45mm long, this wrap of insignia cloth grips tightly to the trim line and forms 35 mm tail of flat cloth on the line.  (dimensions???). 

To thread the trim line, put the threaded end through the cleat entering at the jam side. Exit the cleat at the top end, routing through the 

* Universal solution
* Standard dimensions

## Successful Variants 

* Single trim line
* Two-part trim line


## Failed Variants

** Long trim line tails - aka _Racing bar_
** 4-to-1 mechanical advantage

