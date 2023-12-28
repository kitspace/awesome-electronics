# Contribution Guidelines

## Table of Contents

- [Adding to this list](#adding-to-this-list)
- [Adding something to an awesome list](#adding-something-to-an-awesome-list)
- [Updating your Pull Request](#updating-your-pull-request)

## Adding to this list

Please ensure your pull request adheres to the following guidelines:

- Search previous suggestions before making a new one, as yours may be a duplicate.
- Make an individual pull request for each suggestion.
- Use [title-casing](http://titlecapitalization.com) (AP style).
- Use the following format: `[Link Name](link)`
- Link additions should be added to the bottom of the relevant category.
- New categories or improvements to the existing categorization are welcome.
- Check your spelling and grammar.
- The pull request and commit should have a useful title.

Thank you for your suggestions!


## Adding something to an awesome list

If you have something awesome to contribute to an awesome list, this is how you do it.

You'll need a [GitHub account](https://github.com/join)!

1. Access the awesome list's GitHub page. For example: https://github.com/sindresorhus/awesome
2. Click on the `readme.md` file: ![Step 2 Click on Readme.md](https://cloud.githubusercontent.com/assets/170270/9402920/53a7e3ea-480c-11e5-9d81-aecf64be55eb.png)
3. Now click on the edit icon. ![Step 3 - Click on Edit](https://cloud.githubusercontent.com/assets/170270/9402927/6506af22-480c-11e5-8c18-7ea823530099.png)
4. You can start editing the text of the file in the in-browser editor. Make sure you follow guidelines above. You can use [GitHub Flavored Markdown](https://help.github.com/articles/github-flavored-markdown/). ![Step 4 - Edit the file](https://cloud.githubusercontent.com/assets/170270/9402932/7301c3a0-480c-11e5-81f5-7e343b71674f.png)
5. Say why you're proposing the changes, and then click on "Propose file change". ![Step 5 - Propose Changes](https://cloud.githubusercontent.com/assets/170270/9402937/7dd0652a-480c-11e5-9138-bd14244593d5.png)
6. Submit the [pull request](https://help.github.com/articles/using-pull-requests/)!

## Updating your Pull Request

Sometimes, a maintainer of an awesome list will ask you to edit your Pull Request before it is included. This is normally due to spelling errors or because your PR didn't match the awesome-* list guidelines.

[Here](https://github.com/RichardLitt/docs/blob/master/amending-a-commit-guide.md) is a write up on how to change a Pull Request, and the different ways you can do that.

## EDAs category description

### Simulation

EDA tools allow designers to simulate the behavior of electronic circuits before they are physically built. This helps in identifying and addressing potential issues and optimizing the performance of the design.

### HDL & Synthesis

EDA tools that support languages like Verilog and VHDL, which are used to describe the functionality and behavior of digital circuits and systems. The synthesis process involves translating a high-level description of a circuit into a netlist or a set of low-level components. This is a crucial step in the design flow, especially for digital circuits.

### Verification

This involves checking the correctness and functionality of a design through various techniques, including formal verification, timing, and testing. EDA tools are used to analyze the timing characteristics of a design, ensuring that signals meet the required timing constraints.

### PCB design

It involves creating the physical layout of components and their interconnections on a PCB (Printed Circuit Board). It translates the logical and functional aspects of a circuit design into a tangible, manufacturable form. Key aspects of EDA with PCB design capabilities are:

- Component Placement: Such as integrated circuits (ICs), resistors, capacitors, and connectors, onto the PCB.
- Routing: involves creating the copper traces that connect the pins of different components on the PCB. EDAs for PCB design can verifi aspects such as signal integrity, impedance matching, minimizing electromagnetic interference (EMI), and avoiding signal crosstalk.
- Design Rule Check (DRC): EDA tools perform design rule checks to ensure that the layout adheres to the manufacturer's specifications and constraints.7
- Gerber Files: After the PCB layout is complete and verified, Gerber files are generated. These files contain the information needed for PCB fabrication, including copper layers, silkscreen, and solder mask.
- 3D Visualization: Some advanced EDA tools offer 3D visualization features, allowing designers to view the PCB layout in a three-dimensional space.

## Tier description

### ${\color{red}S}$

Full-featured and professional-level EDAs, widely adopted in the industry for highly complex electronic projects. Highly active project, whether proprietary or open source.

### ${\color{orange}A}$

Very popular, with a large community, and with a very active and accelerated software development. It contains advanced features but not so widely adopted in the industry as it lacks cutting-edge features. Even though, it can be adopted to complex electronic systems, usually as a free alternative to the ${\color{red}S}$ tier.

### ${\color{yellow}B}$

A EDA with a small community yet and not so popular, but with a promising and very active software development. Software in this tier tends to grwo into tier ${\color{orange}A}$ as they get matured. They can have some nice features for more complex electronic projects, but they are usually more limited when compared to tier ${\color{orange}A}$ or ${\color{red}S}$.

### ${\color{green}C}$

Single-featured EDAs with a small community. It lacks more complex functionalities, and the software development is not very active. Additionally, it is usually used in a niche. EDAs in this tier are not expected to grow much further than they already are. Even though, the software can fully fullfil its taks and can be used for small- and medium-sized projects.

### ${\color{light blue}D}$

Old and single-featured EDAs with a rarely active software development. EDAs in this tier tend to become obsolete throughout the time.

### ${\color{purple}E}$

Abandoned EDA projects with obsolete features. These EDAs are listed for historical reasons, as they were relevant in the past.
