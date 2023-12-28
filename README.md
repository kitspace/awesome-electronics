# Awesome Electronics [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of awesome resources for Electronic Engineers and hobbyists

Electronic Engineering (EE) is the practice of understanding, designing and building electronic circuits. It is often differentiated from electrical engineering in that it mostly deals with low power DC electronic circuits rather than high power AC systems but there is a lot of overlap between electronic and electrical engineering.

Experimenting with and building electronic circuits is also a popular hobby and many professional resources are often equally applicable to hobbyists and vice versa.

This list is for websites, services, software, tools and more: everything that you think is awesome in the world of Electronic Engineering. If you have anything to add please follow the instructions in [contributing.md](contributing.md).

## Contents

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [EDAs](#edas)
- [EDA-specific Resources](#eda-specific-resources)
- [Learning](#learning)
- [Documentation](#documentation)
- [Gerber Viewers](#gerber-viewers)
- [PCB Batching Services](#pcb-batching-services)
- [Part Search Engines](#part-search-engines)
- [Project Sharing Platforms](#project-sharing-platforms)
- [Inventory Management and Purchasing](#inventory-management-and-purchasing)
- [Miscellaneous Software Projects](#miscellaneous-software-projects)
- [Development Board Retailers](#development-board-retailers)
- [Subscription Kit Services](#subscription-kit-services)
- [Other Lists](#other-lists)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## EDAs

| Name | Access Level | OS | Desciption | Simu-lation | HDL & Synthesis | Verifi-cation | PCB design |
| --- | --- | --- | --- | --- | --- | --- | --- |
| [LTspice](https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html) | Free | Win, Mac | The industry standard free SPICE circuit simulator from Linear Technologies. Also see the unofficial [LTwiki](http://ltwiki.org/?title=Main_Page) and [Group](https://groups.io/g/LTspice). | :heavy_check_mark: | :x: | :heavy_check_mark: | :x: |
| [Proteus](https://www.labcenter.com/) | Paid | Win | PCB Design and Circuit Simulator Software. | :heavy_check_mark: | :x: | :heavy_check_mark: | :heavy_check_mark: |
| [Altium](https://www.altium.com/) | Paid | Win | A fully-featured editor for schematics that includes a rich set of schematic capture tools to quickly create, edit, simulate, and document schematics. | :heavy_check_mark: | :x: | :heavy_check_mark: | :heavy_check_mark: |
| [KiCad](https://kicad.org/) | Free | Win, Linux | One of the most popular Open source EDA package with push and shove router, differential pairs and much more. | :x: | :x: | :heavy_check_mark: | :heavy_check_mark: |
| [Eagle](https://www.autodesk.com/products/eagle/overview) | Freemium | Win, Linux, Mac | A popular EDA packages with (board size restricted) free version. | :x: | :x: | :heavy_check_mark: | :heavy_check_mark: |
| [Circuit JS/Falstad](http://www.falstad.com/circuit/circuitjs.html) | Free | Web | Free, [open source](https://github.com/sharpie7/circuitjs1) online simulator with electron flow visualization (rewrite of original Java applet by Paul Falstad). | :heavy_check_mark: | :x: | :x: | :x: |
| [EveryCircuit](https://everycircuit.com) | Freemium | Web | Free to try online, visual, interactive circuit simulator for simpler circuits. | :heavy_check_mark: | :x: | :x: | :x: |
| [Altium CircuitMaker](https://circuitmaker.com/) | Free | Win | Free package from the maker of the go to pro software. | :x: | :x: | :x: | :heavy_check_mark: |
| [LibrePCB](https://librepcb.org/) | Free | Win, Linux, Mac | A new, powerful and intuitive EDA tool for everyone, cross-platform and GNU GPLv3. | :x: | :x: | :heavy_check_mark: | :heavy_check_mark: |
| [EasyEDA](https://easyeda.com/) | Free | Web | Easy to use with both browser based and cross platform app versions. Integrates [LCSC](https://www.lcsc.com/products) and [JLCPCB](https://jlcpcb.com/parts) component catalogs with 3D models. | :x: | :x: | :heavy_check_mark: | :heavy_check_mark: |
| [Qucs](http://qucs.sourceforge.net/) | Free | Win, Mac, Linux | Open source, cross-platform, non-SPICE-based circuit simulator, with with S-parameter and Harmonic Balance capability. | :heavy_check_mark: | :x: | :heavy_check_mark: | :x: |
| [Qucs-S](https://ra3xdh.github.io/) | Free | Win, Mac, Linux | Open source fork of Qucs using SPICE for simulation. | :heavy_check_mark: | :x: | :heavy_check_mark: | :x: |
| [QucsStudio](http://qucsstudio.de/) | Free | Win | Closed-source fork of Qucs with a similar interface, new engine, and more features. | :heavy_check_mark: | :x: | :heavy_check_mark: | :x: |
| [Verilator](https://www.veripool.org/wiki/verilator) | Free | Win, Linux | Open source Verilog compiler. Test benches are in C++ or SystemC. Very fast, but limted to 2-state, cycle-based simulation, and synthesizeable code only. | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :x: |
| [Icarus Verilog](http://iverilog.icarus.com/) | Free | Win, Linux | Open source verilog interpreter. Test benches are in behavioral verilog. Simulation is 4-state, and event-based. | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :x: |
| [Open Circuit Design Software](http://opencircuitdesign.com) | Free | Linux | Open Source, full EDA suite chip design suite, focused on keeping up with commercial tools. | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| [CppSim](https://www.cppsim.com/) | Free | Win, Mac, Linux | Free, open source circuit simulator that leverages the C++ language to achieve very fast simulation times. | :heavy_check_mark: | :x: | :x: | :heavy_check_mark: |
| [TINA-TI](http://www.ti.com/tool/TINA-TI) | Free | Win | Exclusive [DesignSoft-TINA](https://www.tina.com) build for Texas Instruments, bundled with Texas Instruments Models. | :heavy_check_mark: | :x: | :x: | :x: |
| [iCircuit](http://icircuitapp.com/) | Free | Web | Easy to use electronic circuit simulator, its advanced simulation engine can handle both analog and digital circuits and features realtime always-on analysis. | :heavy_check_mark: | :x: | :x: | :x: |
| [gEDA](http://geda-project.org) | Free | Linux, Mac | Another open source package, good for people that like scripting and makefiles, Linux and BSD only. | :x: | :x: | :x: | :heavy_check_mark: |
| [DesignSpark PCB](https://www.rs-online.com/designspark/pcb-software) | Free | Win | Free EDA package without restrictions, sponserd by RS Components. | :x: | :x: | :x: | :heavy_check_mark: |
| [DipTrace](https://diptrace.com) | Free | Win, Mac | Quality Schematic Capture and PCB Design software with (pin and signal layer restricted) free version. | :x: | :x: | :heavy_check_mark: | :heavy_check_mark: |
| [Horizon EDA](https://github.com/horizon-eda/horizon) | Free | Linux |  A free and open source EDA tool with the focus on shortcut operation. | :x: | :x: | :heavy_check_mark: | :heavy_check_mark: |

## EDA-specific Resources

### KiCad
- [Xesscorp's list of KiCad 3rd party tools](https://github.com/xesscorp/kicad-3rd-party-tools)
- [Contextual Electronics' Shine on You Crazy KiCad](https://contextualelectronics.com/courses/shine-on-you-crazy-kicad/) - Beginner video tutorial that gets you to a manufactured board as quickly as possible.
- [Contextual Electronics' Getting to Blinky Tutorial](https://www.youtube.com/playlist?list=PLy2022BX6Eso532xqrUxDT1u2p4VVsg-q) - A more comprehensive beginner to intermediate video tutorial.
- [KiCad.info Forums](https://forum.kicad.info) - User discussion and help forum.
- [Keyboard PCB Guide](https://github.com/ruiqimao/keyboard-pcb-guide) -  Comprehensive written tutorial that takes you through creating a keyboard PCB.
- [Cheatsheet](https://silica.io/wp-content/uploads/2018/06/kicad-cheatsheet.pdf) (also [in landscape](https://silica.io/wp-content/uploads/2018/06/kicad-cheatsheet-landscape.pdf)) - Short PDF that goes over the menus and keyboard shortcuts for the most common operations.
- [Footprint Collection](https://github.com/kitspace/kicad_footprints) - Collection of all the KiCad footprints available online and some scripts to manage them.
- [InteractiveHtmlBom](https://github.com/openscopeproject/InteractiveHtmlBom) - A html BOM generation tool for manual pick and place.
- [KiBot](https://github.com/INTI-CMNB/KiBot) - Generate the fabrication and documentation files for your KiCad projects easily, repeatable, and most of all, scriptably.

### Eagle
- [List of ULPs everyone should know](https://www.element14.com/community/community/eagle/blog/2015/01/19/eagle-ulps-every-user-should-know)
- [Adafruit Eagle Library](https://github.com/adafruit/Adafruit-Eagle-Library)
- [SparkFun Electronics Eagle Libraries](https://github.com/sparkfun/SparkFun-Eagle-Libraries)

### Altium

- [Altium Designer Libraries](https://www.altium.com/documentation/other_installers#!libraries) - `.IntLib` and `.PcbLib` of electronic components from different manufacturers.

## Learning

### Technical Tutorials
- ["skill" tag on learn.sparkfun.com](https://learn.sparkfun.com/tutorials/tags/skill) - A wide variety of technical tutorials on various EE related skills.
- [Soldering is Easy](https://mightyohm.com/blog/2011/04/soldering-is-easy-comic-book/) - Comic book that goes over the basics of soldering that has been translated into quite a few languages.
- [Uses of Different Soldering Iron Tips](https://www.instructables.com/id/Uses-of-Different-Soldering-Iron-Tips/) - Covers what all those different soldering iron tips are good for.
- [How to design a motherboard for your electronics project](https://www.staycaffeinated.com/2021/02/21/how-to-design-a-motherboard-for-your-project-part-1) - Introductory tutorial on Schematic & PCB design

### Courses
- [Khan Academy - Electrical Engineering](https://www.khanacademy.org/science/electrical-engineering) - Non-profit learning platform with a full course on electrical engineering and related topics.
- [NEETS (Navy Electricity and Electronics Training Series)](https://www.fcctests.com/neets/Neets.htm) - U.S. Navy Non-Resident Training Course Material.
- [NPTEL](https://nptel.ac.in/course.html) - Has all free engineering courses including electronics, electrical and communcation engineering.
- [Udemy courses related to Electronics](https://www.udemy.com/topic/electronics/) - Top paid courses available on Udemy.
- [Coursera courses related to Electronics](https://www.coursera.org/courses?query=electronics) - Includes some free courses that provide e-certificates on completion.

### Theory 
- [Basic Electronics PPT](http://engineering.nyu.edu/gk12/amps-cbri/pdf/Basic%20Electronics.pdf) - Contains conceptual explaination of diode, BJT, J/MOS-FET, LED, 7 seg display, photo-resistor/diode/transistor
- [Electronics textbook](https://upload.wikimedia.org/wikipedia/commons/e/ee/Electronics.pdf) - Text covers design and function of electronic circuits and components, DC analysis, and AC analysis. 
- [Student Handbook](http://cbseacademic.nic.in/web_material/Curriculum/Vocational/2018/Basic_Electronics_XI.pdf) - Language used in this book easily understandable covers evolution, fundamentals, diode, rectifiers, transistors and its applications, SCR, DIAC and TRIAC.
- [Electronics circuits and systems](http://aems.edu.sd/wp-content/uploads/2019/02/Electronics-Circuits-and-Systems-Fourth-Edition-PDFDrive.com-.pdf) - Quality free e-book covering all topics under circuits and systems, highly recommended for conceptual understanding.
- [Lessons In Electric Circuits](https://www.ibiblio.org/kuphaldt/electricCircuits/) - Free high quality textbooks and worksheets with emphasis on theory, simulation, and the socratic method.
- [Ultimate Electronics: Practical Circuit Design and Analysis](https://ultimateelectronicsbook.com/) - Free online book with interactive schematics & simulations by CircuitLab (under development).

### Blogs
- [Hackaday](https://hackaday.com) - Probably the most popular blog covering electronics and hardware hacking with a whole staff of writers.
- [bunniestudios.com](https://www.bunniestudios.com) - Andrew 'Bunnie' Huang covers hardware hacking, open hardware, manufacturing and more.
- [Bald Engineer](https://www.baldengineer.com) - Project logs, tutorials and articles about electronics and embedded software by James Lewis.
- [Rheingold Heavy](https://rheingoldheavy.com) - More project logs, tutorials and articles about electronics and embedded software, these ones by Dan Hienzsch.
- [Hackster.io](https://www.hackster.io/news) - Another blog covering electronics.
- [Dangerous Prototypes](http://dangerousprototypes.com/blog/) - Blog about open source hardware projects and interesting app notes.
- [N-O-D-E](https://n-o-d-e.net/) - Blog about DIY electronics, hardware, and technology.

### Podcasts
- [The Amp Hour](https://theamphour.com/) - Off-the-cuff chat about electronics with Chris Gammel and Dave Jones (EEVBlog), often with guests
- [Embedded.fm](https://embedded.fm/) - Christopher and Elecia White discuss embedded systems development and much more, often with guests.
- [The Spark Gap Podcast](http://thesparkgap.net) - Covers a specific EE topic each episode, sometimes with guests.
- [MacroFab Engineering Podcast](https://macrofab.com/blog/podcast/) - Weekly podcast where Parker and Stephen from MacroFab discuss EE topics and industry news.
- [The Engineering Commons Podcast](http://theengineeringcommons.com/) - Covers general engineering topics from mechanical to electrical.

### Forums

#### Discussion
- [EEVBlog forum](https://www.eevblog.com/forum/) - Probably the largest and most active forum to discuss Electronic Engineering topics.
- [/r/electronics](https://www.reddit.com/r/electronics/) and [/r/ECE](https://www.reddit.com/r/ECE/) are the two most active sub-reddits for EE topics.

#### Help
- [/r/askelectronics](https://www.reddit.com/r/AskElectronics/) - Sub-reddit dedicated to help on electronics topics.
- [Electronics Stack Exchange](https://electronics.stackexchange.com) - Question and answer site for electronics running on the popular Stack Overflow service.
- [EEVBlog beginners forum](https://www.eevblog.com/forum/beginners/) - Good place for beginner questions, other sub-forums on EEVblog should be suitable for questions on more advanced topics.

### University Course Archives

- [Berkeley EECS](http://inst.eecs.berkeley.edu/classes-eecs.html) - Comprehensive EE & CS course website archives.
- [Dr. Jacob Baker](http://cmosedu.com) - Courses and tutorials, professor at The University of Nevada, Las Vegas.
- [Dr. Abraham](https://www.cerc.utexas.edu/~jaa/teaching.html), [Dr. McDermot](http://users.ece.utexas.edu/~mcdermot/), and [Dr. Valvano](http://users.ece.utexas.edu/~valvano/) - Courses materials, professors at UT Austin

### Youtube channels
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

## Documentation
- [Inkscape Electric Symbols](https://github.com/upb-lea/Inkscape_electric_Symbols) - Circuit Drawing Symbols for Inkscape
- [Tabula](http://tabula.ondata.it/) - Extract tabular data from a pdf, very useful for extracting pin tables or part characteristics from datasheets.
- [WebPlotDigitizer](https://automeris.io/WebPlotDigitizer/) - Extract data from plots, charts, etc., very useful for getting part performance curves from datasheets.
- [WaveDrom](https://wavedrom.com/) - Create waveforms and timing diagrams from a JSON description file.

## Gerber Viewers

### Online
- [Tracespace Viewer](https://tracespace.io/) -  Gerber viewer that lets you inspect the individual layers as well as the board preview.
- [Gerblook](https://www.gerblook.org/) - Online Gerber viewer powered by Gerbv.
- [Mayhew Labs 3dpcb](http://mayhewlabs.com/3dpcb) - 3D Gerber viewer.
- [CircuitPeople](https://circuitpeople.com) - No frills 2D layer viewer for Gerbers, without the excessive processing.
- [Stackrate Viewer](https://stackrate.de/viewer/) - Easy to use online gerber viewer with trace hovering and measurement tools.

### Installable
- [Gerbv](http://gerbv.geda-project.org/) - Excellent Gerber viewer for Linux and BSD.
- [KiCAD Gerbview](https://kicad.org/) - The KiCAD gerber viewer.
- [GC-Prevue](http://www.graphicode.com/GC-Prevue_Gerber_Viewer) - Commercial with free version. Can handle some gerbers better than Gerbv and KiCAD.
- [ZofZPCB](https://www.zofzpcb.com/) - FREE 3D Gerber Viewer.

## PCB Batching Services
- [PCBShopper](https://pcbshopper.com/) - Comparison service for quite a lot of different PCB batching and assembly services.
- [OSH Park](https://oshpark.com) - Low cost PCB batching service with high quality boards with a signature purple silkscreen.
- [Aisler](https://aisler.net) - Affordable quality circuit boards made in and shipped from Europe (Germany).
- [Dirty PCBs](http://dirtypcbs.com/store/pcbs) - Low cost PCB batching service that prides itself on its "dirty" quality.
- [JLCPCB](https://jlcpcb.com/) - Low cost PCB batching service with inhouse low cost SMT service.
- [PCBWay](https://www.pcbway.com/) - Low cost PCB batching service with PCBA, CNC and 3D-Printing services.

## Part Search Engines

| Name | Description | Purchase link | Datasheet | 3D model | Footprint model | Schematic symbol |
| --- | --- | --- | --- | --- | --- | --- |
| [Octopart](https://octopart.com) | Probably the most well known part search engine. | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| [Findchips](https://www.findchips.com/) | Part search from Supply Frame. | :heavy_check_mark: | :heavy_check_mark: | :x: | :x: | :x: |
| [Parts.io](https://parts.io/) | Another search engine from Supply Frame geared towards discovering new parts. | :heavy_check_mark: | :x: | :x: | :x: | :x: |
| [Electronic Component Search Engine](https://componentsearchengine.com/) | Free access to schematic symbols, PCB footprints and 3D models. | :x: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |
| [3D ContentCentral](https://www.3dcontentcentral.com) | Website dedicated to 3D models of parts (requires login). | :x: | :x: | :heavy_check_mark: | :x: | :x: |
| [GrabCad](https://grabcad.com/library/electronic-components-1) | Community supported database of 3D models with a large number of electronic component models. | :x: | :x: | :heavy_check_mark: | :x: | :x: |

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
- [NinjaCalc](https://gbmhunter.github.io/NinjaCalc/) - An embedded engineering calculator toolbox for doing calculations in a breeze.
- [Saturn PCB Design Toolkit](https://saturnpcb.com/saturn-pcb-toolkit/) - The Saturn PCB Toolkit is the best freeware resource for PCB related calculations you can find.

## Development Board Retailers
- [Sparkfun](https://www.sparkfun.com/) - Retailer and designer of open source electronics development boards and other equipment and materials with excellent accompanying tutorials.
- [Adafruit](https://www.adafruit.com/) - Another retailer and designer with excellent selection and tutorials.
- [Tindie](https://www.tindie.com) - Marketplace for electronics makers to sell low volume batches of their own designs.

## Subscription Kit Services
- [AdaBox](https://www.adafruit.com/adabox/) - Curated Adafruit products, unique collectibles, and exclusive discounts. All delivered quarterly.
- [HackerBoxes](https://hackerboxes.com/) - A monthly surprise box which includes projects, components, modules and tools.

## Other Lists
- [PwnKitteh/InsanelyCheapElectronics](https://github.com/PwnKitteh/InsanelyCheapElectronics) - A list of cheap electronics from China, that you can use in your projects.
- [PCB/EDA software list on the EEVblog forums](https://www.eevblog.com/forum/eda/pcbeda-software-list/) - A much more comprehensive list of all the software tools available.
- [intajay/open-electronics](https://github.com/intajay/open-electronics) - Another GitHub list: resources for Electronics Enthusiasts and Hardware Hackers.
- [Vitorian/awesome-fpga](https://github.com/Vitorian/awesome-fpga) - Awesome list of FPGA resources.
- [cajt/list_of_robot_electronics](https://github.com/cajt/list_of_robot_electronics) - A GitHub list of resources, projects and products for robot electronics.
- [embedded-boston/awesome-embedded-systems](https://github.com/embedded-boston/awesome-embedded-systems) - Awesome list of embedded programming resources.
- [TCAD Central](https://tcadcentral.com/Software.html) - List of Technology CAD (TCAD) software and resources from the maker of DEVSIM.
- [Awesome Lattice FPGAs](https://github.com/kelu124/awesome-latticeFPGAs) - A curated list of awesome open-source FPGA boards.
- [TM90/awesome-hwd-tools](https://github.com/TM90/awesome-hwd-tools) - A curated list of hardware design tools with a focus on chip design.
- [delftopenhardware/awesome-open-hardware](https://github.com/delftopenhardware/awesome-open-hardware) - Helpful items for making and learning about open source hardware projects.
- [upb-lea/awesome-open-source-power-electronics](https://github.com/upb-lea/awesome-open-source-power-electronics) - Open source software list specialized on power electronics.
