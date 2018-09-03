---
title: "Replacing the chickenloop"
excerpt: "Alternative quick release options for kite bars"
tags:
  - kites
  - land kiting
  - quick release
  - wichard
  - snap hook
  - snap shackle
  - 3D printing
  - kite buggy
  - kite bar
---

![](/images/DSC_0113.jpg "Attaching a kite bar to a harness with no chickenloop")

## Alternative quick release options for kite bars

Most kite control bars use a feature called a _chicken loop_ to connect the bar to the harness the kite flier is wearing. It's a venerable system that has evolved to meet the needs of water kiters. Beyond the need to connect the bar and harness, the chicken loop also provides for a quick release mechanism to separate the bar from the harness hook in an emergency and in normal landing. To facilitate unhooked tricks, the chicken loop allows for easy hooking and unhooking while in flight. Some chicken loops incorporate a swivel to allow the flier to remove line twist. Some provide a now-twisting pathway for a flag line.

Whereas these are valuable features for most water kiters, some of them are not valuable to a kite buggier. A buggier needs the reliable connection and emergency disconnect features just like a water kiter. The swivel is often helpful. A flag line pathway is required if a flag line will be used. Optimizing for these features can lead to a different solution from that used by water kiters and land boarders.

One liability of the chicken loop is its length. It places the bar and all of its controls further away from the flier. This either reduces the bar throw or makes reaching the trim control more difficult and at times more dangerous. That effect is exacerbated by the hook the chicken loop connects to. Any design that can bring the bar closer to the flier's navel could offer advantages of increased control and safety.

Multiple tests with reduced-size chicken loops brought the bar closer, but I could not eliminate much of the distance between the pilot and the bar added by the chickenloop. So I dispensed with the chickenloop and started testing quick-release shackles in its place.

## Wichard Snap Shackle

A popular option for quick release systems on kite gear is the Wichard snap shackle.

![](/images/DSC_0120.jpg "Unmodified Wichard snap shackle")

This shackle and its peers are described by Wichard in [Quick release snap shackles](http://marine.wichard.com/rubrique-Quick_release_snap_shackles-0202040300000000-IM.html). This family of Wichard shackles provides an extremely reliable release not seen in other products--even those from Wichard.

These shackles are generally equipped with a small cord which, when pulled down, lowers a wire gate. When the wire gate drops far enough a hinged gate at the top of the shackle pivots from the top of the shackle releasing any line retained by the gate.

![](/images/DSC_0127.jpg "Unmodified Wichard snap shackle with gate open")

The release cord works very well in non-urgent situations when you can see the cord and have clearance to pull the cord down. Unfortunately, few of those requirements can be met when a kite buggier urgently needs to release the kite. The shackle and cord are rarely in the flier's sight line. In an emergency, there is very little time to search for anything much less something small.


## Swiveling: good and bad

The difficulties of finding the shackle's pull cord or a handle attached to it can be exacerbated by the use of a swivelling shackle. While the swivel allows the flier to remove simple line twist, the untwisting process adds uncertainty to the cord's position. The constantly shifting orientation of the shackle can leave the cord end opposite the hand that reaches to pull it.


## Releasing in any orientation

To address these problems I borrowed an idea shared on [Powerkiteforum](http://www.powerkiteforum.com/) some years back. A forum member posted picture of a Wichard snap shackle with a short segment of twisted wire rope passing through the wire gate of the shackle. On either end of the gate was a cone with the tapered end facing toward the wire gate. Beyond each cone was a ball to provide a pull handle. When pulling one ball, the opposite cone would be pulled into the wire gate and release the hinged gate.

I adapted this design in a few 3D-printed iterations until I produced a cone and handle combination that looks something like a traffic cone or an inverted golf tee.

![](/images/wichard_handle_history.png "Release mechanisms for Wichard snaphooks")

## How to make and assemble a set of handles

To use the traffic cone/golf tee style, print a pair of the handles in PLA with 80% infill, 3 shells, and 0.2 mm layers. The design for the handle is available in [OpenSCAD](https://github.com/pbchase/kite_bar_parts/blob/master/wichard_snaphook_handle_golf_tee_style.scad) and [STL](/images/wichard_snaphook_handle_golf_tee_style_8677c59.stl) formats.  To reduce the friction from the surface texture of the printing process, sand the cone of each handle smooth with 220-grit paper.

Assemble the cones with the shackle on a short, folded, segment of 300# Spectra line that passes through the release gate of the snap shackle. The narrow tip of each piece faces the shackle. The Spectra is folded in half, tied with a figure eight knot at the loose end.  The folded end is pulled through the entire assembly with a wire fid. The folded end of the line is locked in place by a very short segment of line knotted and larksheaded on the end. The knots and the larks head are recessed inside the handles. This prevents the handles from pulling off the line ends and off the shackle.

![](/images/DSC_0129.jpg "Handles secured via recessed knots")


## How to use the assembly

When pulled, the handle pulls the opposite cone into the wire gate to open the snap shackle. Any rope passing through the hinged gate will be released.

![](/images/DSC_0115.jpg "Wichard snap shackle opened by a traffic-cone handle")

This mechanism can be used to capture any depower bar that has a loop in the center below the bar. For a conventional depower bar it can capture the chickenloop, yet the greatest opportunity is in eliminating the chickenloop and attaching the shackle directly to the lower loop of a doubled trim line. This brings the bar _much_ closer to the flier.

![](/images/DSC_0108.jpg "Wichard snap shackle and handles in operating configuration")

## Which shackles to use

The handle shown here was developed to open the Wichard Quick release snap shackles. These two sizes have been tested with this cone shape. The shackle on the left has the conventional bail size. The one on the right has the large bail. The large bail was useful for accommodating the 2-inch webbing that is routed through it to make a Swiss Seat.

![](/images/DSC_0125.jpg "Wichard snap shackles with scale")


There are other options for shackles that might work equally as well. The [Wichard Speedlink](http://marine.wichard.com/rubrique-SPEEDLINK-0202040201000000-IM.html) and [Tylaska T5 Snap Shackles](http://www.tylaska.com/index.php/marine/trigger-release-shackles/t5/). The Tylaska hardware has been discussed in the thread [triggered snap shackle for possible aqr](http://www.powerkiteforum.com/viewthread.php?tid=33055#pid316339) on [Powerkiteforum](http://www.powerkiteforum.com/). These styles would require a release cone with different dimensions. The [OpenSCAD](https://github.com/pbchase/kite_bar_parts/blob/master/wichard_snaphook_handle_golf_tee_style.scad) file that describes the traffic cone handle is mostly parameterized. It should be reasonably easy to adapt it to other dimensions.  For its own hardware, Tylaska offers [Cone fids](http://www.tylaska.com/index.php/marine/trigger-release-shackles/fids) that could be used with balls and cord as part of a release mechanism.
