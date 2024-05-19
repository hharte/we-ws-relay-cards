# Reproducing Wire-Spring Relay Cards
### Using a 3D Printer.


## Introduction

Western Electric [wire spring relays](https://en.wikipedia.org/wiki/Wire_spring_relay) use a card made of phenol fiber (early type) or plastic (later type) to actuate the contacts for make and break.  Since the cards are sometimes broken, this project aims to create 3D-printable models to facilitate replacement.  The card models were designed using [FreeCAD](https://www.freecad.org/), and can be exported from FreeCAD as STL meshes suitable for slicing and 3D printing.

![alt_text](https://github.com/hharte/we-ws-relay-cards/blob/main/ws_card_rendering.png "Rendering of the various wire spring relay cards in a 3D slicer program.")



## Card Details

Wire spring relay cards have a single digit stamped on them, which for 12-position relays corresponds to the last digit in the card part number.  The dual relay AK-, AM-types also have a card number stamped on them in the lower right corner.  For AK-, and AM- relays, the stamped number does not directly identify the card part number.  Use the table below for the mapping between the stamped card number and the card piece part number.


<table>
  <tr>
   <td><strong><em>Part Number</em></strong>
   </td>
   <td><strong><em>Relay Types</em></strong>
   </td>
   <td><strong><em>Card #</em></strong>
   </td>
   <td><strong><em>Travel</em></strong>
   </td>
   <td><strong><em>Notes</em></strong>
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/hharte/we-ws-relay-cards/blob/main/stl/WE-P-19A130.stl">P-19A130</a>
   </td>
   <td rowspan="8" >AF, AG, AJ, AL:
<p>
12-position
   </td>
   <td>0
   </td>
   <td>Short
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/hharte/we-ws-relay-cards/blob/main/stl/WE-P-19A131.stl">P-19A131</a>
   </td>
   <td>1
   </td>
   <td>Intermediate
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/hharte/we-ws-relay-cards/blob/main/stl/WE-P-19A132.stl">P-19A132</a>
   </td>
   <td>2
   </td>
   <td>Intermediate
   </td>
   <td>WE-P-19A132 is BreakNo2Sketch, MakeNo2Sketch merged.
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/hharte/we-ws-relay-cards/blob/main/stl/WE-P-19A133.stl">P-19A133</a>
   </td>
   <td>3
   </td>
   <td>Long
   </td>
   <td>WE-P-19A133 is BreakNo3Sketch, MakeNo3Sketch merged
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/hharte/we-ws-relay-cards/blob/main/stl/WE-P-19A134.stl">P-19A134</a>
   </td>
   <td>4
   </td>
   <td>Intermediate
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/hharte/we-ws-relay-cards/blob/main/stl/WE-P-19A135.stl">P-19A135</a>
   </td>
   <td>5
   </td>
   <td>Intermediate
   </td>
   <td>WE-P-19A135 is BreakNo5Sketch, MakeNo5Sketch merged.
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/hharte/we-ws-relay-cards/blob/main/stl/WE-P-19A136.stl">P-19A136</a>
   </td>
   <td>6
   </td>
   <td>Intermediate
   </td>
   <td>WE-P-19A136 is LP-19A131, MakeNo6Sketch merged.
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/hharte/we-ws-relay-cards/blob/main/stl/WE-P-19A137.stl">P-19A137</a>
   </td>
   <td>7
   </td>
   <td>Intermediate
   </td>
   <td>Similar to 6, except make contacts.
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/hharte/we-ws-relay-cards/blob/main/stl/WE-P-19A150.stl">P-19A150</a>
   </td>
   <td rowspan="2" >AJ:
<p>
24-position
   </td>
   <td>10
   </td>
   <td>Short
   </td>
   <td>24 make contacts.
   </td>
  </tr>
  <tr>
   <td>P-10F907
   </td>
   <td>?
   </td>
   <td>Short
   </td>
   <td>24 break contacts
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/hharte/we-ws-relay-cards/blob/main/stl/WE-P-10B701.stl">P-10B701</a>
   </td>
   <td rowspan="8" >AK, AM<sup>[2]</sup>
   </td>
   <td>3<sup>[1]</sup>
   </td>
   <td>Short
   </td>
   <td>Contacts 1-5 (Lower), M / B
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/hharte/we-ws-relay-cards/blob/main/stl/WE-P-10B701.stl">P-10B702</a>
   </td>
   <td>4<sup>[1]</sup>
   </td>
   <td>Short
   </td>
   <td>Contacts 8-12 (Upper), M / B (flip P-10B701)
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/hharte/we-ws-relay-cards/blob/main/stl/WE-P-10B699.stl">P-10B699</a>
   </td>
   <td>1<sup>[1]</sup>
   </td>
   <td>Intermediate
   </td>
   <td>Contacts 1-5 (Lower)
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/hharte/we-ws-relay-cards/blob/main/stl/WE-P-10B699.stl">P-10B700</a>
   </td>
   <td>2<sup>[1]</sup>
   </td>
   <td>Intermediate
   </td>
   <td>Contacts 8-12 (Upper) (flip P-10B699)
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/hharte/we-ws-relay-cards/blob/main/stl/WE-P-10B703.stl">P-10B703</a>
   </td>
   <td>5<sup>[1]</sup>
   </td>
   <td>Intermediate
   </td>
   <td>Contacts 1-5 (Lower)
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/hharte/we-ws-relay-cards/blob/main/stl/WE-P-10B703.stl">P-10B704</a>
   </td>
   <td>6<sup>[1]</sup>
   </td>
   <td>Intermediate
   </td>
   <td>Contacts 8-12 (Upper) (flip P-10B703)
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/hharte/we-ws-relay-cards/blob/main/stl/WE-P-10B705.stl">P-10B705</a>
   </td>
   <td>7<sup>[1]</sup>
   </td>
   <td>Intermediate
   </td>
   <td>Contacts 1-5 (Lower) M / EB
   </td>
  </tr>
  <tr>
   <td><a href="https://github.com/hharte/we-ws-relay-cards/blob/main/stl/WE-P-10B705.stl">P-10B706</a>
   </td>
   <td>8<sup>[1]</sup>
   </td>
   <td>Intermediate
   </td>
   <td>Contacts 8-12 (Upper) M / EB (flip P-10B705)
   </td>
  </tr>
</table>


**_<span style="text-decoration:underline;">Notes:</span>_**

1. The identification number is stamped on the black surface of each card in the upper righthand corner with the card properly mounted on the relay. Make sure that the replacement card has the same identification number, except for the letter following the number, as the card being replaced. The letter following the identification number is used in connection with manufacture and should be ignored when replacing the card.

2. AK-, and AM- lower and upper cards are mirror images of each other.  For example, the P-10B701 lower relay card can be flipped and used in the upper position as the P-10B702 card.  For this reason, the AK card model has text pockets on the front and back of the card, identifying which side is which.  The original Western Electric cards are also identified on both sides; however, only one side is painted black.

3. Entries marked with ‘?’ are unknown.  If you have examples of these cards, I would love to see a photo.


### Card Profiles

From pp. 72 of [Engineering Reference Data WIRE SPRING RELAYS AF-, AG-, AJ-, AND AK-TYPES (1967)](https://telecomarchive.s3.us-east-2.amazonaws.com/docs/bsp-archive/X/X-75509.pdf):

![alt_text](https://github.com/hharte/we-ws-relay-cards/blob/main/card_profile.png "Wire spring relay actuating card profile.")



<table>
  <tr>
   <td><strong><em>Contact Arrangement</em></strong>
   </td>
   <td><strong><em>inch</em></strong>
   </td>
   <td><strong><em>mm</em></strong>
   </td>
   <td><strong><em>Measured</em></strong>
   </td>
   <td><strong><em>Notes</em></strong>
   </td>
  </tr>
  <tr>
   <td>M
   </td>
   <td>0.081
   </td>
   <td>2.0574
   </td>
   <td>0.0845
   </td>
   <td>
   </td>
  </tr>
  <tr>
   <td>B
   </td>
   <td>0.075
   </td>
   <td>1.905
   </td>
   <td>0.074
   </td>
   <td>Spreadsheet.B_Cutout
   </td>
  </tr>
  <tr>
   <td>EM
   </td>
   <td>0.068
   </td>
   <td>1.7272
   </td>
   <td>0.71
   </td>
   <td>Spreadsheet.EM_Cutout
   </td>
  </tr>
  <tr>
   <td>EB
   </td>
   <td>0.088
   </td>
   <td>2.2352
   </td>
   <td>0.88
   </td>
   <td>Spreadsheet.EB_Cutout
   </td>
  </tr>
  <tr>
   <td>PM
   </td>
   <td>0.055
   </td>
   <td>1.397
   </td>
   <td>
   </td>
   <td>Spreadsheet.PM_Cutout
   </td>
  </tr>
  <tr>
   <td>PB
   </td>
   <td>0.101
   </td>
   <td>2.5654
   </td>
   <td>
   </td>
   <td>
   </td>
  </tr>
</table>



### Card Models for AF-, AG-, AJ-, AL-Type Relays

The card models for AF-, AG-, AJ-, and AL-type relays consist of [WE-P-19A130-137.FCStd](https://github.com/hharte/we-ws-relay-cards/blob/main/WE-P-19A130-137.FCStd) for 12-position relays, and  [WE-P-19A150.FCStd](https://github.com/hharte/we-ws-relay-cards/blob/main/WE-P-19A150.FCStd) for 24-position “make” contact relays.  The model consists of BlankCardSketch which is a 12-position card that does not have any cutouts for the make / break contact profiles.  This sketch is padded in CardPad to a thickness of 0.166 mm (slightly larger than 1/16th inch.)  From CardPad, the contact profiles are pocketed in P-19A13x_Pocket using one of eight sketches: P-19A130 through P-19A137.

The card profile is configurable from the spreadsheet by selecting Card Number 0 through 7.  Conditional length is configured for each card profile pocket, using an expression similar to `Spreadsheet.CardNo == 0 ? 5 : 0.001`.


### Card Model for AK-, AM-Type Relays

The card model for AK-, AM-type dual relays is [WE-P-10B699-706.FCStd](https://github.com/hharte/we-ws-relay-cards/blob/main/WE-P-10B699-706.FCStd).  While there are eight cards defined for the AK-, AM-type relays, the cards for upper and lower portions of the AK, AM relays are mirror images of each other.  As such, the lower cards can be flipped and used in the upper position.  For this reason, the model contains the odd number stamped on the front of the card, and the even number on the back.

When selecting a card from the spreadsheet in the model, use 1, 3, 5, or 7.  Flip the “odd” card to get the “even” card.  For example, if you need a card stamped with 2, select 1 in the model, and flip the card (2 will be visible in the lower right of the card.)

**_Note: To get a smoother surface when printing, you can “flip” the card in your slicing program so that the desired card’s top side is in contact with the build plate of the 3D-printer._**


### Spring Lifter Tool Model

The spring lifter tool model is suitable to move the relay’s dual contact springs away from the card so the card can be removed and replaced. [SpringLifter16.FCStd](https://github.com/hharte/we-ws-relay-cards/blob/main/SpringLifter16.FCStd).  This tool is loosely modeled after the “Detail 16 Lifter” described in [BSP 040-502-801](https://telecomarchive.s3.us-east-2.amazonaws.com/docs/bsp-archive/040/040-502-801_I9.pdf) and [BSP 040-504-801](https://telecomarchive.s3.us-east-2.amazonaws.com/docs/bsp-archive/040/040-504-801_I8.pdf).  While this tool is not as full featured as the lifters and spring combs supplied in the [1018A Tool Kit](https://www.telephonecollectors.info/index.php/browse/bsp-bell-system-practices-by-doc/bsp-categories-by-later-division-number-by-doc/020-199-apparatus-tools-gauges-test-eq-power/074-099-divisions-tools-and-gauges/074-division-catalogue-info-tools/6714-074-232-111-i4/file), I have found it useful in helping to replace the cards.  Print two of the SpringLifter16’s and use one each on the make and break contacts.  To use this tool:



1. Release the balancing springs on each end of the card carefully by hand.
2. Slide one SpringLifter16 tool under the card carefully and slowly, between the movable “Break” springs and the fixed contacts, moving the movable springs out of the way of the card.
3. Slide a second SpringLifter16 tool under the card carefully and slowly, between the movable “Make” springs and the fixed contacts, moving the movable springs out of the way of the card.
4. With the spring lifters in place, carefully remove the damaged card.
5. Replace with a new reproduction card.
6. Carefully remove the SpringLifter16 tools ensuring that the movable springs don’t become tangled.
7. If any springs become tangled or are out of their proper position, use an [orange stick](https://www.amazon.com/JONARD-S-389-ORANGE-STICK-Jonard/dp/B0195UK7BW) to carefully move them back into place.


## Printer Settings

Use PETG or ABS filament printed with 0.1mm DETAIL with 100% infill for strength.


## Limitations

The following card part numbers are mentioned in the relevant BSPs; however they are not currently supported as I do not have information on these cards.  If you have one of these cards or know where information about them can be obtained, [please file a bug to get in touch with me](https://github.com/hharte/we-ws-relay-cards/issues/new).


<table>
  <tr>
   <td><strong><em>Missing Card Part Number</em></strong>
   </td>
   <td><strong><em>Description</em></strong>
   </td>
  </tr>
  <tr>
   <td>WE-P-10F907
   </td>
   <td>24-position break contact card
   </td>
  </tr>
</table>



## References



1. [Engineering Reference Data WIRE SPRING RELAYS AF-, AG-, AJ-, AK-, AL-, AND AM-TYPES (1967)](https://telecomarchive.s3.us-east-2.amazonaws.com/docs/bsp-archive/X/X-75509.pdf)
2. [Engineering Reference Data WIRE SPRING RELAYS AF-, AG-, AJ-, AND AK-TYPES (1962)](https://www.telephonecollectors.info/index.php/browse/bruce-crawford-library/western-electric/weco-switching-documents/weco-components/12307-wire-spring-relays-af-ag-aj-ak-x75509-aug62-1/file)
3. [BSP 040-502-101](https://telecomarchive.s3.us-east-2.amazonaws.com/docs/bsp-archive/040/040-502-101_I2.pdf) - RELAYS AF-, AG-, AND AJ- TYPES DESCRIPTION.
4. [BSP 040-502-801](https://telecomarchive.s3.us-east-2.amazonaws.com/docs/bsp-archive/040/040-502-801_I9.pdf) - RELAYS AF-, AG-, AND AJ-TYPE PIECE-PART DATA AND REPLACEMENT PROCEDURES.
5. [BSP 040-502-701](https://telecomarchive.s3.us-east-2.amazonaws.com/docs/bsp-archive/040/040-502-701_I9.pdf) - RELAYS AF, AG, AND AJ TYPES REQUIREMENTS AND ADJUSTING PROCEDURES.
6. [BSP 040-504-801](https://telecomarchive.s3.us-east-2.amazonaws.com/docs/bsp-archive/040/040-504-801_I8.pdf) - RELAYS AK-TYPE PIECE-PART DATA AND REPLACEMENT
7. [BSP 040-504-701](https://telecomarchive.s3.us-east-2.amazonaws.com/docs/bsp-archive/040/040-504-701_I7.pdf) - RELAYS AK-TYPE REQUIREMENTS AND ADJUSTING PROCEDURES.
