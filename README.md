CSS Reset
=========

Mark Howells-Mead | www.markweb.ch | Initial version August 2014

The rules here work around various display bugs and hiccups in various browsers AND apply a few rules which make the 
layout of a page cleaner and more logical.

It's important to note that this CSS reset code doesn't normalize elements across the board and remove all margins and 
paddings. It only removes or re-defines margins and padding where this always makes sense… for example on the 
``<body>`` element.

There's no quick way to explain what all the rules do: if you're interested (and you should be) then read the file 
properly and understand what rules you're applying.

Usage
=====

You don't need to implement your CSS classes in any special way. The .scss file should be used to compile a CSS reset 
file, which should then be linked into a template as the first CSS file. Then add your own rules in your own 
stylesheet/s.

Credits and stuff
=================

Many rules are collated through my own experience; others have been tied in from other CSS reset solutions, such as 
those listed at www.cssreset.com. I take no credit for rules copied 1:1; a hat-tip goes to all of the authors listed at 
www.cssreset.com.

The files and codes in this CSS reset solution are offered with no guarantees or promises. But I use it in my projects, 
which should be a good sign.

Use it freely, widely and for free. Please respect the GPL v2 licence, which is provided as part of this Git repository 
and also available via http://www.gnu.org/licenses/gpl-2.0.html
