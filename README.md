# Awesome Electronics [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome resources for electronic engineers and hobbyists

Electronic engineering (EE) is the practice of understanding, designing and building electronic circuits. It is often differentiated from electrical engineering in that it mostly deals with low power DC electronic circuits rather than high power AC systems but there is a lot of overlap between electronic and electrical engineering. 

Experimenting with and building electronic circuits is also a popular hobby and many professional resources are often equally applicable to hobbyists and vice versa.

This list is for websites, services, software, tools and more: everything that you think is awesome in the world of electronic engineering. If you have anything to add please follow the instructions in [contributing.md](contributing.md).

## Contents

<!-- toc -->

- [Simulators & Tools Suite](#simulators)
- [Gerber Viewers](#gerber-viewers)
  * [Online](#online)
  * [Installable](#installable)
- [Free EDA Packages](#free-eda-packages)
- [CAD Specific](#cad-specific)
  * [KiCAD](#kicad)
  * [Eagle](#eagle)
- [PCB Batching Services](#pcb-batching-services)
- [Part Search Engines](#part-search-engines)
- [Project Sharing Platforms](#project-sharing-platforms)
- [Inventory Management and Purchasing](#inventory-management-and-purchasing)
- [Miscellaneous Web Services](#miscellaneous-web-services)
- [Development Board Retailers](#development-board-retailers)
- [Blogs](#blogs)
- [Forums](#forums)
  * [Discussion](#discussion)
  * [Help](#help)
- [Podcasts](#podcasts)
- [Videos](#videos)
- [Learning](#learning)
  * [Technical Tutorials](#technical-tutorials)
  * [Theory and Courses](#theory-and-courses)
- [Other Lists](#other-lists)

<!-- tocstop -->

## Simulators
Includes Simulators, development enviroments, tool suites. The major electronics manufacturer flavored tool suites include: Linear Technologies use of Spice3, TI's lite edition of the TINA circuit simulator, and Analog Devices lite version of SIMetrix/SIMPLIS.
- [LTSpice](http://www.linear.com/designtools/software/#LTspice) - The industry standard free SPICE circuit simulator from Linear Technologies.
- [Ngspice](http://ngspice.sourceforge.net/) - Open source SPICE circuit simulator.
- [Circuit JS](http://www.falstad.com/circuit/circuitjs.html) - Open source online simulator for simpler circuits with live interactivity and visualization.
- [Every Circuit](http://everycircuit.com) - Free to try online, visual, interactive circuit simulator for simpler circuits.
- [Qucs Studio](http://dd6um.darc.de/QucsStudio/qucsstudio.html) - Mixed Signal + Spice Simulator, for analog, digital (Verilog AMS) an electromagnetic simulation
- [QUCS](http://qucs.sourceforge.net/) - Simlar to above, at one time were the same but both forked and diverged. This is also Linux and Mac compatible 
- [Open Chip Design Software](http://opencircuitdesign.com/index.html) - Open Source chip design software which includes schematic editing, PCB and IC layout, autorouting, digital system simulation and much more. 
- [TI Tina](http://www.ti.com/tool/tina-ti) - Based on the TINA tool suite, an alternative to LTSpice and other spice engine wrappers. 
- [ADIsimPE aka SIMetrix lite edition](http://www.analog.com/en/design-center/interactive-design-tools/adisimpe.html) - Lite edition with manufacturer lock to Analog Devices version of the popular SIMetrix simulation engine. 
- [CPPSim](http://www.cppsim.com/) - Similar to QUCSStudio another fully featured mixed signal circuit simulator. High quality schematic editor similar to the SUE schmeatic entry method (SUE2), and verilog/verilogAMS/typicalAnalog circuit support with GNU Octave and NGspice backend supports. Can simulate high end communication circuits, oversampling data converters and more high performance circuits.
- [Verilator](https://www.veripool.org/wiki/verilator) - Timing based verilog to SystemC compiler. Highly optimized but with major limitations. First, it is timing based and not event based. Second, it can only work on a subset of verilog, Synthesizable Verilog. Otherwise very powerful and useful for practical on computer full system simulation, though not as comprehensive as an event based. 
- [Icarus Verilog aka iVerilog](http://iverilog.icarus.com/) - fully featured interpreted event based verilog intepreter, for IEEE 1364-2005 verison of Verilog. 
- [GNU Maxima](http://maxima.sourceforge.net/) - Fully featured CAS System similar to Mathematica and Maple. Very helpful for symbolic calculations and lighter learning curve than using SageMath/Sympy but more intuitive and fully featured than MuPad/Symoblic toolbox. 
- [GNU Octave](https://www.gnu.org/software/octave/) - basically GNU Matlab. 
- [Scilab and XCOS](http://www.scilab.org/) - Popular alternative to Matlab. Basically another powerful Numerical/Vector/Matrix calculator. Very useful for control systems as well through the XCos enviroment
- [Anaconda Python](https://www.continuum.io/downloads) - Powerful python package enviroment that includes many Scikits (especially the allimportant ML libraries), Sympy/Numpy/Scipy, Various datascience toolboxes (Pandas) and more. All in one fully featured toolsuite.
- [List of populare TCAD Simulators](https://www.tcad.com/Software.html)


## Gerber Viewers

### Online
- [Tracespace Viewer](http://viewer.tracespace.io) -  Gerber viewer that lets you inspect the individual layers as well as the board preview.
- [Gerblook](http://gerblook.org/) - Online Gerber viewer powered by Gerbv.
- [Mayhew Labs 3dpcb](http://mayhewlabs.com/3dpcb) - 3D Gerber viewer.
- [EasyEDA Gerber Viewer](https://gerber-viewer.easyeda.com/) - Gerber viewer and design for manufacture test.
- [CircuitPeople](http://circuitpeople.com/) - No frills 2D layer viewer for Gerbers, without the excessive processing.

### Installable
- [Gerbv](http://gerbv.geda-project.org/) - Excellent Gerber viewer for Linux and BSD.
- [KiCAD Gerbview](http://kicad-pcb.org/) - The KiCAD gerber viewer.


## Free EDA Packages
- [KiCAD](http://kicad-pcb.org/) - Open source EDA package with push and shove router, differential pairs and much more.
- [Eagle](https://cadsoft.io/) - One of the most popular EDA packages due to it's (board size restricted) free version.
- [Design Spark PCB](http://www.rs-online.com/designspark/electronics/eng/page/designspark-pcb-home-page) - Gratis EDA package without restrictions, sponserd by RS Components.
- [Altium Circuit Maker](http://circuitmaker.com/) - Free package from the maker of the go to pro software.
- [gEDA](http://geda-project.org) - Another open source package, good for people that like scripting and makefiles, Linux and BSD only.
- [NCSU FreePDK](https://www.eda.ncsu.edu/wiki/FreePDK) - Free PDK from NCSU providing access to 3D/FinFet, 45 and 15nm lithos. Based on models from ASU's Predicted Technology Models


## CAD Specific 

### KiCAD
- [Xesscorp's list of KiCAD 3rd part tools](https://github.com/xesscorp/kicad-3rd-party-tools)
- [Contextual Electronics' KiCAD 4.0 video tutorials](https://www.youtube.com/playlist?list=PLy2022BX6Eso532xqrUxDT1u2p4VVsg-q) - Comprehensive video tutorials for beginners.
- [KiCAD.info Forums](https://forum.kicad.info) - User discussion and help forum.
- [Keyboard PCB Guide](https://github.com/ruiqimao/keyboard-pcb-guide) -  Comprehensive written tutorial that takes you through creating a keyboard PCB.
- [Cheatsheet](https://silica.io/static/downloads/kicad-cheatsheet.pdf) (also [in landscape](https://silica.io/static/downloads/kicad-cheatsheet-landscape.pdf)) - Short PDF that goes over the menus and keyboard shortcuts for the most common operations.
- [Footprint Collection](https://github.com/monostable/kicad_footprints) - Collection of all the KiCAD footprints available online and some scripts to manage them.

### Eagle
- [List of ULPs everyone should know](https://www.element14.com/community/community/cadsoft_eagle/blog/2015/01/19/eagle-ulps-every-user-should-know)
- [Adafruit Eagle Library](https://github.com/adafruit/Adafruit-Eagle-Library)
- [SparkFun Electronics Eagle Libraries](https://github.com/sparkfun/SparkFun-Eagle-Libraries)

## PCB Batching Services
- [PCB Shopper](http://pcbshopper.com) - Comparison service for quite a lot of different PCB batching and assembly services.
- [OSH Park](https://oshpark.com) - Low cost PCB batching service with high quality boards with a signature purple silkscreen.
- [Aisler Go](https://go.aisler.net) - Affordable quality circuit boards made in and shipped from Europe (Germany).
- [Dirty PCBs](http://dirtypcbs.com) - Low cost PCB batching service that prides itself on its "dirty" quality.

## Part Search Engines
- [Octopart](https://octopart.com) - Probably the most well known part search engine.
- [Findchips](https://findchips.com) - Part search from Supply Frame.
- [Parts.io](https://parts.io/) - Another search engine from Supply Frame geared towards discovering new parts.

## Project Sharing Platforms
- [Kitnic.it](https://kitnic.it) - Project sharing site that helps you buy parts and re-build projects. Open source and developed by yours truly.
- [Hackaday.io](https://hackaday.io) - Social site for sharing projects from the popular blog.
- [Aisler.net](https://aisler.net) - Search engine for open source electronics published on GitHub.

## Inventory Management and Purchasing
- [1-click BOM](https://1clickBOM.com) - Browser extensions that automates purchasing and part searching. 
- [Partsbox.io](https://partsbox.io) - Web service to manage your part inventory with a nice user interface and Octopart integration.
- [Partkeepr](https://partkeepr.org) - Open source web service to manage your part inventory.

## Miscellaneous Web Services
- [Eyrie.io](https://eyrie.io) - For viewing Eagle and KiCAD designs online.
- [SnapEDA.com](https://snapeda.com) - Parts library with free symbols & footprints. (Compatible with Eagle, KiCAD, Altium, OrCad, Allegro, etc.)

## Development Board Retailers
- [Sparkfun](https://sparkfun.com/) - Retailer and designer of open source electronics development boards and other equipment and materials with excellent accompanying tutorials.
- [Adafruit](https://www.adafruit.com/) - Another retailer and designer with excellent selection and tutorials. 
- [Tindie](https://www.tindie.com) - Marketplace for electronics makers to sell low volume batches of their own designs.

## Blogs
- [Hackaday](https://hackaday.com) - Probably the most popular blog covering electronics and hardware hacking with a whole staff of writers.
- [bunniestudios.com](https://www.bunniestudios.com) - Andrew 'Bunnie' Huang covers hardware hacking, open hardware, manufacturing and more.
- [Bald Engineer](https://www.baldengineer.com) - Project logs, tutorials and articles about electronics and embedded software by James Lewis.
- [Rheingold Heavy](https://rheingoldheavy.com) - More project logs, tutorials and articles about electronics and embedded software, these ones by Dan Hienzsch.

## Forums

### Discussion
- [EEVBlog forum](https://www.eevblog.com/forum) - Probably the largest and most active forum to discuss electronic engineering topics.
- [/r/electronics](https://reddit.com/r/electronics) and [/r/ECE](https://reddit.com/r/ECE) are the two most active sub-reddits for EE topics.

### Help
 - [/r/askelectronics](https://reddit.com/r/askelectronics) - Sub-reddit dedicated to help on electronics topics.
 - [Electronics Stack Exchange](https://electronics.stackexchange.com) - Question and answer site for electronics running on the popular Stack Overflow service.
 - [EEVBlog beginners forum](http://www.eevblog.com/forum/beginners/) - Good place for beginner questions, other sub-forums on EEVblog should be suitable for questions on more advanced topics.


## Podcasts
 - [The Amp Hour](http://www.theamphour.com/) - Off-the-cuff chat about electronics with Chris Gammel and Dave Jones (EEVBlog), often with guests
 - [Embedded FM](http://embedded.fm/) - Christopher and Elecia White discuss embedded systems development and much more, often with guests.
 - [Sparkgap Podcast](http://thesparkgap.net) - Covers a specific EE topic each episode, sometimes with guests.
 - [MacroFab Engineering Podcast](https://macrofab.com/blog/podcast/) - Weekly podcast where Parker and Stephen from MacroFab discuss EE topics and industry news
 - [The Engineering Commons Podcast](http://theengineeringcommons.com/) - Covers general engineering topics from mechanical to electrical. 


## Videos
- [EEVblog](https://www.youtube.com/user/EEVblog) - One of the earliest and most successful YouTube channels where Dave Jones does teardowns, tutorials and more. 
- [ElectroBOOM](https://www.youtube.com/user/msadaghd) - YouTube channel that debunks and explains EE topics with a lot of comedy thrown in.
- [Micah Scott](https://www.youtube.com/user/micahjd) - Video logs of reverse engineering and re-purposing consumer electronics hardware in creative ways.
- [Afrotechmods](https://www.youtube.com/user/afrotechmods) - Tutorials on electronics projects, often suitable for beginners as well.
- [The Signal Path](https://www.youtube.com/user/TheSignalPathBlog) - Very in depth teardowns, repairs and reviews of lab equipment and prototyping products.
- [w2aew](https://www.youtube.com/channel/UCiqd3GLTluk2s_IBt7p_LjA) - Excellent tutorials about basic and complex analog hardware.
- [Mr. Carlson's Lab](https://www.youtube.com/user/MrCarlsonsLab) - Teardowns, repairs and restorations with an emphasis on classic electronics gear.
- [GreatScott](https://www.youtube.com/user/greatscottlab) - Electronics tutorials, projects and how to's.
- [Julian Ilett](https://www.youtube.com/user/julius256) - Buys cheapest electronic modules he can find and tries to do useful things with them.
- [MikesElectricStuff](https://www.youtube.com/channel/UCcs0ZkP_as4PpHDhFcmCHyA) - Teardowns, large lighting projects, xrays and more.
- [Ben Eater](https://www.youtube.com/playlist?list=PLowKtXNTBypGqImE405J2565dvjafglHU) - Series of videos on building an 8-bit computer on breadboards with excellent explanations of all the sub-circuits.

## Learning

### Technical Tutorials
- [Soldering is Easy](http://mightyohm.com/blog/2011/04/soldering-is-easy-comic-book/) - Comic book that goes over the basics of soldering that has been translated into quite a few languages.
- [Uses of Different Soldering Iron Tips](http://www.instructables.com/id/Uses-of-Different-Soldering-Iron-Tips/?ALLSTEPS) - Covers what all those different soldering iron tips are good for.
- [BSIM Site](http://bsim.berkeley.edu/). Details on BSIM Models, similar to the SPICE3 page. Gives indepth details to using BSIM4/3 Models. 
- [Indepth Wiki for LTSpice](http://ltwiki.org/?title=Main_Page)

### Theory and Courses
- [All About Circuits](http://www.allaboutcircuits.com/textbook/) - Online textbook for learning theory with clear diagrams and explanations.
- [Electrical Engineering - Khan Academy](https://www.khanacademy.org/science/electrical-engineering) - Online learning platform with lots of topics, including a full course on electrical engineering, circuits, semiconductors, signals, robots, and even reverse engineering electronic devices.
- [EE123 Digital Signal Processing](https://inst.eecs.berkeley.edu/~ee123/sp16/)
- [CS 150 Intro to Digital System Design](http://www-inst.eecs.berkeley.edu/~cs150/fa13/agenda/)
- [EE247 ADC Design](https://inst.eecs.berkeley.edu/~ee247/fa10/index.html)
- [Dr. Jacob Baker Course List](http://cmosedu.com/jbaker/courses/courses.htm) - Course list from Dr. Jacob Baker, includes courses on introduction to linear circuit modeling (DC Circuits/Circuits I), and intro to microelectronics. But more importantly covers intro to IC Physical Design, Analog IC Design (intro and advanced), Digital IC Layout and Design, Mixed Signal Circuit Design, Memory Circuit design, Power Electronics IC Design. 
- [EE 122A UCSB Intro to VLSI Design](http://www.ece.ucsb.edu/courses/ECE122/122_F16Banerjee/)
- [UT Austin's EE382M.7 VLSI I](http://www.cerc.utexas.edu/~jaa/vlsi/)
- [Dr. M. McDermott's Courselist](http://users.ece.utexas.edu/~mcdermot/) Massive courselist on advanced embedded systems and VLSI topics. 
- [Professor Valvano's Courselist](http://users.ece.utexas.edu/~valvano/) Massive and extremely comprehensive courselist for embedded systems, from intro to advanced concepts, with homework assignments, course videos, and sample code

## Other Lists

- [PCB/EDA software list on the EEVblog forums](http://www.eevblog.com/forum/eda/pcbeda-software-list/) - A much more comprehensive list of all the software tools available. 
- [intaja/open-electronics](https://github.com/intajay/open-electronics) - Another GitHub list: resources for Electronics Enthusiasts and Hardware Hackers
