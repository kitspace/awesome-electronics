# Awesome Electronics [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome resources for electronic engineers and hobbyists

Electronic engineering (EE) is the practice of understanding, designing and building electronic circuits. It is often differentiated from electrical engineering in that it mostly deals with low power DC electronic circuits rather than high power AC systems but there is a lot of overlap between electronic and electrical engineering.

Experimenting with and building electronic circuits is also a popular hobby and many professional resources are often equally applicable to hobbyists and vice versa.

This list is for websites, services, software, tools and more: everything that you think is awesome in the world of electronic engineering. If you have anything to add please follow the instructions in [contributing.md](contributing.md).

## Contents

<!-- toc -->

- [Learning](#learning)
  - [Technical Tutorials](#technical-tutorials)
  - [Theory and Courses](#theory-and-courses)
  - [University Course Archives](#university-course-archives)
- [Documentation](#documentation)
- [Simulators](#simulators)
  - [Analog and Mixed Signal Circuit Simulators](#analog-and-mixed-signal-circuit-simulators)
  - [Verilog HDL Simulators](#verilog-hdl-simulators)
- [Gerber Viewers](#gerber-viewers)
  - [Online](#online)
  - [Installable](#installable)
- [Free EDA Packages](#free-eda-packages)
- [CAD Specific](#cad-specific)
  - [KiCad](#kicad)
  - [Eagle](#eagle)
- [PCB Batching Services](#pcb-batching-services)
- [Part Search Engines](#part-search-engines)
- [Project Sharing Platforms](#project-sharing-platforms)
- [Inventory Management and Purchasing](#inventory-management-and-purchasing)
- [Miscellaneous Software Projects](#miscellaneous-software-projects)
- [Development Board Retailers](#development-board-retailers)
- [Blogs](#blogs)
- [Forums](#forums)
  - [Discussion](#discussion)
  - [Help](#help)
- [Podcasts](#podcasts)
- [Videos](#videos)
- [Subscription Kit Services](#subscription-kit-services)
- [3D Part Models](#3d-part-models)
- [Other Lists](#other-lists)

<!-- tocstop -->

## Learning

### Technical Tutorials
- ["skill" tag on learn.sparkfun.com](https://learn.sparkfun.com/tutorials/tags/skill) - A wide variety of technical tutorials on various EE related skills.
- [Soldering is Easy](https://mightyohm.com/blog/2011/04/soldering-is-easy-comic-book/) - Comic book that goes over the basics of soldering that has been translated into quite a few languages.
- [Uses of Different Soldering Iron Tips](https://www.instructables.com/id/Uses-of-Different-Soldering-Iron-Tips/) - Covers what all those different soldering iron tips are good for.
- [How to design a motherboard for your electronics project](https://www.staycaffeinated.com/2021/02/21/how-to-design-a-motherboard-for-your-project-part-1) - Introductory tutorial on Schematic & PCB design

### Theory and Courses

- [Lessons In Electric Circuits](https://www.ibiblio.org/kuphaldt/electricCircuits/) - Free high quality textbooks and worksheets with emphasis on theory, simulation, and the socratic method.
- [Ultimate Electronics: Practical Circuit Design and Analysis](https://ultimateelectronicsbook.com/) - Free online book with interactive schematics & simulations by CircuitLab (under development).
- [Khan Academy - Electrical Engineering](https://www.khanacademy.org/science/electrical-engineering) - Non-profit learning platform with a full course on electrical engineering and related topics.
- [NEETS (Navy Electricity and Electronics Training Series)](https://maritime.org/doc/#neets) ([alternative link](https://github.com/thinkitdata/neets/tree/master/modules))- U.S. Navy Non-Resident Training Course Material.

### University Course Archives

- [Berkeley EECS](http://inst.eecs.berkeley.edu/classes-eecs.html) - Comprehensive EE & CS course website archives.
- [Dr. Jacob Baker](http://cmosedu.com) - Courses and tutorials, professor at The University of Nevada, Las Vegas.
- [Dr. Abraham](https://www.cerc.utexas.edu/~jaa/teaching.html), [Dr. McDermot](http://users.ece.utexas.edu/~mcdermot/), and [Dr. Valvano](http://users.ece.utexas.edu/~valvano/) - Courses materials, professors at UT Austin

## Documentation
- [Inkscape Electric Symbols](https://github.com/upb-lea/Inkscape_electric_Symbols) - Circuit Drawing Symbols for Inkscape

## Simulators

### Analog and Mixed Signal Circuit Simulators

- [LTspice](https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html) - The industry standard free SPICE circuit simulator from Linear Technologies. Also see the unofficial [LTwiki](http://ltwiki.org/?title=Main_Page) and [Group](https://groups.io/g/LTspice).
- [ngspice](http://ngspice.sourceforge.net/) - Open source SPICE circuit simulator.
- [Circuit JS/Falstad](http://www.falstad.com/circuit/circuitjs.html) - Free, open source online simulator with electron flow visualization (rewrite of original Java applet by Paul Falstad).
- [EveryCircuit](https://everycircuit.com) - Free to try online, visual, interactive circuit simulator for simpler circuits.
- [Qucs](http://qucs.sourceforge.net/) - Open source, cross-platform, non-SPICE-based circuit simulator, with with S-parameter and Harmonic Balance capability.
- [QucsStudio](http://dd6um.darc.de/QucsStudio/qucsstudio.html) - Free, closed-source, Windows-only fork of Qucs with a similar interface, new engine, and more features.
- [Open Circuit Design Software](http://opencircuitdesign.com) - Open Source, full EDA suite chip design suite, focused on keeping up with commercial tools.
- [TINA-TI](http://www.ti.com/tool/TINA-TI) - Exclusive [DesignSoft-TINA](https://www.tina.com) build for Texas Instruments, bundled with Texas Instruments Models.
- [CppSim](https://www.cppsim.com/) - Free, open source circuit simulator that leverages the C++ language to achieve very fast simulation times.
- [Scilab with Xcos](https://www.scilab.org/) - Free, open source numerical computing alternative to MATLAB. Xcos provides Electrical System modeling capability similar to Simulink.
- [iCircuit](http://icircuitapp.com/) - Easy to use electronic circuit simulator, its advanced simulation engine can handle both analog and digital circuits and features realtime always-on analysis.
- [Micro-Cap](http://www.spectrum-soft.com/download/download.shtm) - Professional-grade mixed signal simulator with wide variety of interactive simulation types.
- [GeckoCIRCUITS](https://de.wikipedia.org/wiki/GeckoCircuits) - Open Source Power Electronic Circuit Simulator. [GitHub Project](https://github.com/geckocircuits/GeckoCIRCUITS). Direct [download link](http://gecko-simulations.com/GeckoCIRCUITS/GeckoCIRCUITS.zip) due to broken website.

### Verilog HDL Simulators

- [Verilator](https://www.veripool.org/wiki/verilator) - Free, open source Verilog compiler. Test benches are in C++ or SystemC. Very fast, but limted to 2-state, cycle-based simulation, and synthesizeable code only.
- [Icarus Verilog](http://iverilog.icarus.com/) - Free, open source verilog interpreter. Test benches are in behavioral verilog. Simulation is 4-state, and event-based.

## Gerber Viewers

### Online
- [Tracespace Viewer](https://tracespace.io/) -  Gerber viewer that lets you inspect the individual layers as well as the board preview.
- [Gerblook](https://www.gerblook.org/) - Online Gerber viewer powered by Gerbv.
- [Mayhew Labs 3dpcb](http://mayhewlabs.com/3dpcb) - 3D Gerber viewer.
- [CircuitPeople](https://circuitpeople.com) - No frills 2D layer viewer for Gerbers, without the excessive processing.
- [Stackrate Viewer](https://stackrate.de/viewer/) - Easy to use online gerber viewer with trace hovering and measurement tools.

### Installable
- [Gerbv](http://gerbv.geda-project.org/) - Excellent Gerber viewer for Linux and BSD.
- [KiCad GerbView](https://kicad.org/) - The KiCad gerber viewer.


## Free EDA Packages
- [KiCad](https://kicad.org/) - Open source EDA package with push and shove router, differential pairs and much more.
- [Eagle](https://www.autodesk.com/products/eagle/overview) - One of the most popular EDA packages due to it's (board size restricted) free version.
- [DesignSpark PCB](https://www.rs-online.com/designspark/pcb-software) - Gratis EDA package without restrictions, sponserd by RS Components.
- [Altium CircuitMaker](https://circuitmaker.com/) - Free package from the maker of the go to pro software.
- [gEDA](http://geda-project.org) - Another open source package, good for people that like scripting and makefiles, Linux and BSD only.
- [DipTrace](https://diptrace.com) - Quality Schematic Capture and PCB Design software with (pin and signal layer restricted) free version.
- [LibrePCB](https://librepcb.org/) - A new, powerful and intuitive EDA tool for everyone, cross-platform and GNU GPLv3.
- [Horizon EDA](https://github.com/horizon-eda/horizon) - A free and open source EDA tool with the focus on shortcut operation.
- [EasyEDA](https://easyeda.com/) - Easy to use with both browser based and cross platform app versions. Integrates [LCSC](https://www.lcsc.com/products) and [JLCPCB](https://jlcpcb.com/parts) component catalogs with 3D models.

## CAD Specific

### KiCad
- [Xesscorp's list of KiCad 3rd party tools](https://github.com/xesscorp/kicad-3rd-party-tools)
- [Contextual Electronics' Shine on You Crazy KiCad](https://contextualelectronics.com/courses/shine-on-you-crazy-kicad/) - Beginner video tutorial that gets you to a manufactured board as quickly as possible.
- [Contextual Electronics' Getting to Blinky Tutorial](https://www.youtube.com/playlist?list=PLy2022BX6Eso532xqrUxDT1u2p4VVsg-q) - A more comprehensive beginner to intermediate video tutorial.
- [KiCad.info Forums](https://forum.kicad.info) - User discussion and help forum.
- [Keyboard PCB Guide](https://github.com/ruiqimao/keyboard-pcb-guide) -  Comprehensive written tutorial that takes you through creating a keyboard PCB.
- [Cheatsheet](https://silica.io/wp-content/uploads/2018/06/kicad-cheatsheet.pdf) (also [in landscape](https://silica.io/wp-content/uploads/2018/06/kicad-cheatsheet-landscape.pdf)) - Short PDF that goes over the menus and keyboard shortcuts for the most common operations.
- [Footprint Collection](https://github.com/kitspace/kicad_footprints) - Collection of all the KiCad footprints available online and some scripts to manage them.
- [InteractiveHtmlBom](https://github.com/openscopeproject/InteractiveHtmlBom) - A html BOM generation tool for manual pick and place.
- [kicad-exports](https://github.com/nerdyscout/kicad-exports) - Auto generate files (schematics, gerbers, BoM, plots, 3D model) for any KiCAD project. Run it locally or on every `git push` with a CI like Github Actions.

### Eagle
- [List of ULPs everyone should know](https://www.element14.com/community/community/eagle/blog/2015/01/19/eagle-ulps-every-user-should-know)
- [Adafruit Eagle Library](https://github.com/adafruit/Adafruit-Eagle-Library)
- [SparkFun Electronics Eagle Libraries](https://github.com/sparkfun/SparkFun-Eagle-Libraries)


## PCB Batching Services
- [PCBShopper](https://pcbshopper.com/) - Comparison service for quite a lot of different PCB batching and assembly services.
- [OSH Park](https://oshpark.com) - Low cost PCB batching service with high quality boards with a signature purple silkscreen.
- [Aisler](https://aisler.net) - Affordable quality circuit boards made in and shipped from Europe (Germany).
- [Dirty PCBs](http://dirtypcbs.com/store/pcbs) - Low cost PCB batching service that prides itself on its "dirty" quality.
- [JLCPCB](https://jlcpcb.com/) - Low cost PCB batching service with inhouse low cost SMT service.

## Part Search Engines
- [Octopart](https://octopart.com) - Probably the most well known part search engine.
- [Findchips](https://www.findchips.com/) - Part search from Supply Frame.
- [Parts.io](https://parts.io/) - Another search engine from Supply Frame geared towards discovering new parts.


## Project Sharing Platforms
- [Kitspace](https://kitspace.org) - Project sharing site that helps you buy parts and re-build projects. Open source and developed by yours truly.
- [Hackaday.io](https://hackaday.io) - Social site for sharing projects from the popular blog.
- [Hackster.io](https://www.hackster.io/) - Another social site for sharing projects. Is well organised by platform, topic and product.
- [InventHub](https://inventhub.io/) - Git-based project hosting and collaboration platform for hardware development.
- [CADLAB](https://cadlab.io/) - Another Git-based project hosting and collaboration platform for hardware development.
- [Eyrie](https://eyrie.io) - For viewing Eagle and KiCad designs online.


## Inventory Management and Purchasing
- [1-click BOM](https://kitspace.org/1-click-bom/) - Browser extensions that automates purchasing and part searching.
- [PartsBox](https://partsbox.io) - Web service to manage your part inventory with a nice user interface and Octopart integration.
- [PartKeepr](https://partkeepr.org) - Open source web service for managing your part inventory with parametric search and automatic datasheet import.
- [Part-DB](https://github.com/Part-DB/Part-DB) - Another open source web service for managing part inventory with a permission system and a good barcode generator.

## Miscellaneous Software Projects
- [SnapEDA](https://www.snapeda.com) - Parts library with free symbols & footprints. (Compatible with Eagle, KiCad, Altium, OrCad, Allegro, etc.)
- [Language PCB](https://github.com/Alhadis/language-pcb) - Syntax highlighting for various PCB formats.

## Development Board Retailers
- [Sparkfun](https://www.sparkfun.com/) - Retailer and designer of open source electronics development boards and other equipment and materials with excellent accompanying tutorials.
- [Adafruit](https://www.adafruit.com/) - Another retailer and designer with excellent selection and tutorials.
- [Tindie](https://www.tindie.com) - Marketplace for electronics makers to sell low volume batches of their own designs.

## Blogs
- [Hackaday](https://hackaday.com) - Probably the most popular blog covering electronics and hardware hacking with a whole staff of writers.
- [bunniestudios.com](https://www.bunniestudios.com) - Andrew 'Bunnie' Huang covers hardware hacking, open hardware, manufacturing and more.
- [Bald Engineer](https://www.baldengineer.com) - Project logs, tutorials and articles about electronics and embedded software by James Lewis.
- [Rheingold Heavy](https://rheingoldheavy.com) - More project logs, tutorials and articles about electronics and embedded software, these ones by Dan Hienzsch.
- [Hackster.io](https://www.hackster.io/news) - Another blog covering electronics.
- [Dangerous Prototypes](http://dangerousprototypes.com/blog/) - Blog about open source hardware projects and interesting app notes.
- [N-O-D-E](https://n-o-d-e.net/) - Blog about DIY electronics, hardware, and technology.


## Forums

### Discussion
- [EEVBlog forum](https://www.eevblog.com/forum/) - Probably the largest and most active forum to discuss electronic engineering topics.
- [/r/electronics](https://www.reddit.com/r/electronics/) and [/r/ECE](https://www.reddit.com/r/ECE/) are the two most active sub-reddits for EE topics.

### Help
- [/r/askelectronics](https://www.reddit.com/r/AskElectronics/) - Sub-reddit dedicated to help on electronics topics.
- [Electronics Stack Exchange](https://electronics.stackexchange.com) - Question and answer site for electronics running on the popular Stack Overflow service.
- [EEVBlog beginners forum](https://www.eevblog.com/forum/beginners/) - Good place for beginner questions, other sub-forums on EEVblog should be suitable for questions on more advanced topics.


## Podcasts
- [The Amp Hour](https://theamphour.com/) - Off-the-cuff chat about electronics with Chris Gammel and Dave Jones (EEVBlog), often with guests
- [Embedded.fm](https://embedded.fm/) - Christopher and Elecia White discuss embedded systems development and much more, often with guests.
- [The Spark Gap Podcast](http://thesparkgap.net) - Covers a specific EE topic each episode, sometimes with guests.
- [MacroFab Engineering Podcast](https://macrofab.com/blog/podcast/) - Weekly podcast where Parker and Stephen from MacroFab discuss EE topics and industry news.
- [The Engineering Commons Podcast](http://theengineeringcommons.com/) - Covers general engineering topics from mechanical to electrical.


## Videos
- [EEVblog](https://www.youtube.com/user/EEVblog) - One of the earliest and most successful YouTube channels where Dave Jones does teardowns, tutorials and more.
- [BigClive](http://bigclive.com) - [YouTube channel](https://www.youtube.com/user/bigclivedotcom) about teardowns (including dangerous products), circuit reverse-engineering and tutorials.
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
- [Robert Feranec](https://www.youtube.com/user/matarofe) - 100+ Hardware design tips and tricks. Videos about Schematic design and PCB layout.
- [Strange Parts](https://strangeparts.com) - [YouTube channel](https://www.youtube.com/channel/UCO8DQrSp5yEP937qNqTooOw) about electronics, manufacturing, making, world travel, living in and making things in China.

## Subscription Kit Services
- [AdaBox](https://www.adafruit.com/adabox/) - Curated Adafruit products, unique collectibles, and exclusive discounts. All delivered quarterly.
- [HackerBoxes](https://hackerboxes.com/) - A monthly surprise box which includes projects, components, modules and tools.

## 3D Part Models
- [GrabCad](https://grabcad.com/library/electronic-components-1) - Community supported database of 3D models with a large number of electronic component models.
- [3D ContentCentral](https://www.3dcontentcentral.com) - Website dedicated to 3D models of parts (requires login).

## Other Lists
- [PwnKitteh/InsanelyCheapElectronics](https://github.com/PwnKitteh/InsanelyCheapElectronics) - A list of cheap electronics from China, that you can use in your projects.
- [PCB/EDA software list on the EEVblog forums](https://www.eevblog.com/forum/eda/pcbeda-software-list/) - A much more comprehensive list of all the software tools available.
- [intajay/open-electronics](https://github.com/intajay/open-electronics) - Another GitHub list: resources for Electronics Enthusiasts and Hardware Hackers.
- [Vitorian/awesome-fpga](https://github.com/Vitorian/awesome-fpga) - Awesome list of FPGA resources.
- [cajt/list_of_robot_electronics](https://github.com/cajt/list_of_robot_electronics) - A GitHub list of resources, projects and products for robot electronics.
- [embedded-boston/awesome-embedded-systems](https://github.com/embedded-boston/awesome-embedded-systems) - Awesome list of embedded programming resources.
- [TCAD Central](https://tcad.com/Software.html) - List of Technology CAD (TCAD) software and resources from the maker of DEVSIM.
- [Awesome Lattice FPGAs](https://github.com/kelu124/awesome-latticeFPGAs) - A curated list of awesome open-source FPGA boards.
- [TM90/awesome-hwd-tools](https://github.com/TM90/awesome-hwd-tools) - A curated list of hardware design tools with a focus on chip design.
- [delftopenhardware/awesome-open-hardware](https://github.com/delftopenhardware/awesome-open-hardware) - Helpful items for making and learning about open source hardware projects.
- [upb-lea/awesome-open-source-power-electronics](https://github.com/upb-lea/awesome-open-source-power-electronics) - Open source software list specialized on power electronics.
