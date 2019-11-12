# A600BlueKBMembranetoPCB

Replace your A600 blue keyboard membrane using PCB. Yeah for the A600, the Amiga that it seems no one want to recreate.. :(( I love my tiny A600 machine.

#### Fully reverse engineered from an original blue membrane by @edu_arana in 2019. 

# Updates

30/09/2019: Initial release.

# A little of history

It all start by the necessity... my first A600 fully modded with Vampire 600 start to fail on the keyboard, some keys were non working and after some time the entire kb stop working. So I search for a membrane replacement. When I found one and saw the price of it, it does not convence me at all, because with time It will fail again. So I decide to fix this by using a replacement made on PCB. I saw that Kipper2k publish some pics of something like this too but there was no chance to get one on that moment. So since I already have experience recreating keyboards (I have made a C64 mechanical keyboard too), I was accustomed to the "matrix" solution too.

My A600 https://arananet-net.kinja.com/instalacion-interna-de-un-plipbox-internet-en-mi-comm-1784934347
and https://arananet-net.kinja.com/instalacion-de-la-aceleradora-vampire-v2-en-mi-a600-c-1782458393.

So after some trials and errors (more errors than trials) I finally fix all the errors, and make two boards, one boards its the keyboard pcb itself and the other is a tiny pcb that is used to plug into the A600 motherboard connector. The connection between the two board is made by a FFC/FPC flat 0.5mm cable.

#### I make this available for the Amiga Community! AMIGAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA!.

# Note

This is a work in progress, several testing has been made but it should work as is. I take no responsibiltiy for any damage to any equipment that results from the use of this board. 

#### USE AT YOUR OWN RISK!

# Images

#### Keyboard pcb.

<img src="https://github.com/arananet/A600BlueKBMembranetoPCB/blob/master/img/teclado.png?raw=true" width="700">

#### Header.

<img src="https://github.com/arananet/A600BlueKBMembranetoPCB/blob/master/img/header.png?raw=true" width="200">

# Images on the real A600

<img src="https://github.com/arananet/A600BlueKBMembranetoPCB/blob/master/img/1.jpg?raw=true" width="700">


<img src="https://github.com/arananet/A600BlueKBMembranetoPCB/blob/master/img/2.jpg?raw=true" width="700">


<img src="https://github.com/arananet/A600BlueKBMembranetoPCB/blob/master/img/3.jpg?raw=true" width="700">



# Bill of materials

| Part          | Value                          | Package                        |
| ------------- | ------------------------------ | ------------------------------ |          
| Connector  		| 54132-3062                     | FFC/FPC (one for the KB PCB)   |
| Connector  		| 54132-3062                     | FFC/FPC (onefor the header PCB)|
| Cable         | 30 pin FFC 0.5mm Flat cable    | Available on Ebay              |

Flat cable example: https://www.ebay.es/itm/2X-Ffc-FPC-Ribbon-Flat-200mm-X-30Pin-0-5mm-Paso-Cable-Flex-Mismo-Direction-Cable/254339642666?ssPageName=STRK%3AMEBIDX%3AIT&_trksid=p2060353.m2749.l2649

# Gerbers

Information to order the gerbers on fabric.

#### Keyboard pcb:

Layers: 2

Dimension: 318mm*141mm

PCB Thickness: 0.6

PCB Color: Any

Surface Finish: ENIG-RoHS

Copper Weight: 1

Gold Fingers: No

Material Details: FR4-Standard Tg 130-140C

Castellated Holes:no

#### Header pcb:

Layers: 1

Dimension: 38mm*23mm

PCB Thickness: 0.6

PCB Color: Any

Surface Finish: ENIG-RoHS

Copper Weight: 1

Gold Fingers: No

Material Details: FR4-Standard Tg 130-140C

Castellated Holes:no

# Feedback

If you find any error on this description, please drop me an email to info@arananet.net or you could also buy me a beer or a Mercedez SLR.. or... :p

# License

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0
International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

