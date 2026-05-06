---
layout: project
title: Lantern Lure
description: Project to create lanternfly solution
technologies: [Various]
image: /assets/images/odp5-image.png
---

### Lantern Lure
**The Grape Guardians**  
Ashlyn Roeder, Asher Ciardiello, Ira Geller, Nicholas Letendre, Mamadou Barry

## Project Milestones

This project was about stopping the invasive spotted lanternflies from hurting vineyard production in New York. We were tasked with designing a mechanical product that could stop this from continuing to happen. We designed a spinning light trap that would lure lanternflies to the edges of the grape vineyards using light, and trap them using rotating blades, crushing them or forcing them into a container. 

- [Client Pitch](#client-pitch)
- [Functional Prototype](#functional-prototype)
- [Client Report](#client-report)


## Client Pitch {#client-pitch}

Preventing SLEs from landing on grapevines
Team: Grape Guardians.
Clients: Cornell CALS Extension / E&J Gallo Winery / National Grape
Proposed statement: The problem we are trying to address is that SLEs tend to land on grapes during their life cycle. This is backed by the fact that there's an average of 9.3 SLE per vine when looking at vineyards in areas infested with SLFs [1]. Additionally, a 2025 study estimates that in three years, there will be an 8% decrease in yield and a 10% decrease in price of grapes due to a drop in quality. Both of these statistics are major issues, as there are no current ways to separate SLFs from harvested grapes, so we want to prevent the SLFs from getting to the vines in the first place.
Why it matters:
• Crucial to limit impacts of SLEs on the grape industry - SLEs harm profit and economic viability
• SLEs live longer when eating grapes - preventing access could help to inhibit the spread of
Proposed Directions:
Concept A: Light trap
Description and Use: Place large lights at the edges of grape fields to attract SLEs. On the light, there would be a one way trap to prevent the SLEs from leaving.
Why it's better than the status quo:
• Reduces chemical use: Unlike insecticide spraying, the light trap doesn't use chemicals, protecting grape quality, beneficial insects, and the surrounding environment.
• Draws SLF away from vines: By Attracting SLF to perimeter lights, it protects grape plants directly.
End-of-semester proof-of-concept: A prototype showing the full function of the trapping mechanism.
Risks:
• SLEs may be able to leave the trap or avoid entering it. (could be tested in controlled conditions)
• Lights may not be effective during daylight. (test for SLF capture count during the day vs night)
• Enough SLFs don't go to the lights and the issue persists.
Questions:
1. What kinds of lights attract SLEs the best (i.e. the most effective lumen or wavelength range)?
Decision affected: Affects the kind of light we would use for the light trap.
2. Do SLEs tend to only fly near light sources or land on them directly?
Decision affected: Affects the range of our trap.
3. Are there other insects (the kinds attracted to light) that need to access the grapevines for them to grow properly?
Decision affected: Affects how much we focus on allowing insects that aren't SLEs to escape the trap.


[Back to top](#project-milestones)

---

## Functional Prototype {#functional-prototype}

![Exploded CAD View]({{ "/assets/images/odp5-image.png" | relative_url }}){: .inline-image-l}

---

## Part Descriptions:

| Part           | Description |
|----------------|-------------|
| Acrylic Plate  | Rotating disk that moves the ridges such that SLFs are put into scenarios where they must go down the tube, or be squished |
| Roof           | Prevents SLFs from jumping off the acrylic plate once their set of ridges begins to force the SLFs down the tube |
| Ridges         | Match up with ridges built into the roof and force SLFs down the tube, or squish SLFs that don’t go down the tube. Prevents SLFs from getting away. |
| Tube           | The component through which SLFs are forced down. Bottom opens into a containment zone where SLFs are imprisoned. |
| Nuts & Bolts   | Used at the edges of the acrylic plate. String tied to one and wrapped around the rest multiple times → when the string is pulled, the plate spins. |

---

### Assembly Instructions

Combine components as shown in blue above (in exploded view);
the only critical order of steps is that the acrylic plate must go down onto the tube before the roof is super-glued on (all other steps can happen in any order).


---

### Critical Dimensions

- Diameter of acrylic plate: **9 in**
- Thickness of disk: **1/16 in**
- Height from disk to roof: **1 in**
- Height of ridges: **0.875 in**
- Dimensions of tube opening: **1 in × 1 in**


### Design Testing:

**Light test:** Does a sufficient percentage of light get through the clear acrylic compared to the amount inside? (ideally, at least 80% of light intensity passes through the acrylic so that the blocked light doesn’t pose the risk of overheating the system)
Procedure: In a dark room, use a phone flashlight and another phone with a lumen reading phone app 5” apart. Repeat with the clear acrylic sheet in between while remaining 5” apart. Compare the values to identify the percentage of light that passesthrough.
Part Focus: Light and clear acrylic top
Results: We measured 740 lux coming from the phone without acrylic and 610 lux coming from the phone through the acrylic. This means that 83% of the light made it through the acrylic.
Conclusion: A sufficient proportion of light is escaping through the acrylic. No material
change (in terms of thickness or composition) is needed for our next prototype.
**Shake Test (Stability and Support):** Does the trap maintain integrity during shaky conditions as might be expected on a windy day?
Procedure: Place the prototype in a desired location and shake it for 10s at 5 Hz (5
shakes per second), seeing if it continues to work during and after being shaken.
Part Focus: Entire prototype
Results: We shook it and it did not fall apart. However, the nuts on the four corners of
the device used to support our spinning mechanism string came loose
Conclusion: The device is robust, but for our next prototype, we should use nylon insert
nuts to ensure longevity under vibrational conditions.
**Speed Test (Assembly and Fastening):** Does our spinning top hold up when rotating at higher operating speeds?
Procedure: Spin the top as fast as possible. No part of the mechanism should break, and the top should still spin smoothly.
Part Focus: The spinning top
Results: No parts of the mechanism broke. We were able to spin it at upwards of 7.25 rad/s with no issue (spun 3 rotations in 2.6s). However, we did notice slight friction between the ridges on the disc and the roof. It did not appear to affect the rotation speeds – rotation speed remained constant through the friction occurring.
Conclusion: The device structure is robust and can operate at high speeds. However, we need to come up with a way of spinning it so we can get more consistent speeds (pulling a string is a bit inconsistent). Additionally, ensuring that ridges are vertical will eliminate any friction between them as they rotate.
**Throw Tests (Load-bearing Performance):** Will our device hold up when bugs land on it at high speeds?
Procedure: Fabricate or find a small object of the approximate mass of a lantern fly (0.5~1 inch). Toss it at varying degrees of speeds at the top of the device while spinning
(~3m/s to match the jumping speed of SLFs). Neither the roof nor the spinning top plate
should break. In addition, the bug should get “squished” by the rotation, though this criterion might not be met until our final prototype. We will try to get an object that isn’t
rigid.
Part Focus: The ridges on the top of the device
Results: We threw a mix of 6 (0.5-inch) and 6 (1-inch) bug models at the top spinning device, and not only did it not break, it “caught” all bugs that landed. Additionally, the roof also remained sturdy under “landing impact” without issues.
Conclusion: The robust top against landing impact and spinning mechanism works well
in either trapping the LSF or squashing it. This type of structure works well; no change needed here.
**High Volume Test (Load Bearing and Performance):** Can the trap handle more than one bug
going down the shaft at one time?
Procedure: Try putting multiple lanternfly-shaped objects into the shaft hole at the same
time. We approximate that 3-6 “bugs” will be able to fall through.
Part Focus: Bug shaft
Results: The 1 in bug models we made were too big to fit through the shaft. However,
our 0.5 in models were able to be shaken out of the device. We were able to fit upwards
of 6 0.5 in bugs into the assembly and still shake all of them out.
Conclusion: Due to the entrance to our tube being too similarly sized to a large SLF,
they struggled to go down the tube when clumped. Therefore, for our next prototype, we
would like to slightly increase the width of the opening (by approximately .25”).
Tolerance Test (Assembly and Fastening): Do our tolerances for the slotted ridges work out?
Procedure: Assemble the prototype. The ridges on the top should fit in tightly and not fall off.
Part Focus: Ridges
Results: Everything fit together. However, we had to use a little bit more superglue than
we wanted to attach the ridges.
Conclusion: We concluded that we need a slightly more snug fit – 0.01” as measured
by a caliper – to ensure that minimal glue is used. We will apply this to the next
prototype.


### Success Criteria:
Our project is a bug catcher that uses light during the evening to lure lanternflies into a spinning trap. The top consists of ridges that force the bug to either move to the center of the trap or be squished.

It should:

● Successfully allow the bug container at the bottom of the trap to be emptied out AND the
container should hold at least 1000 SLFs.
○ The bugs need to be emptied out from the trap for it to have a long lifespan and
to capture more bugs than its volume would otherwise allow.
○ If the container can’t hold a significant amount of SLFs, it will need to be
continuously emptied (unwanted labor burden)

● Allow more than 50% of the light from a given light source to pass through the clear top
(measured using a smartphone light intensity meter)
○ Light needs to penetrate the trap in order to attract the bugs

● Successfully squish a bug-shaped object that is on the plate while it rotates (result is
binary: either it works (1) or it doesn't (0))
○ If multiple bugs land on the trap at once, all of the bugs should be able to be
trapped

● Successfully transport at least 6 SLF at one time from the top of the shaft to the
bug-catching area (6 SLFs can fit between each section of ridges, so this is the
maximum the tube will need to handle at once)
○ The bugs need to be either killed or forced to the center of the trap to work, so
the ridges must establish the threat of death (to force the bugs into the tube or kill
them as a backup)


Demo: We will likely demonstrate that it will squish a bug-shaped object that is on the plate
while it rotates. We will place a small, approximately lanternfly-shaped object with flexible
properties on the top table of the trap, then rotate it to show how the fly will be squished if it doesn’t move to the center of the trap.


[Back to top](#project-milestones)

---


## Client Report {#client-report}


---

### Context and Problem Statement

The core problem of the SLF is the fact that they are landing on grape vines and infesting grapes. Once the grapes get infested, there are currently no effective methods to separate SLF from harvested grapes. Our objective is to prevent the issue before it becomes one by preventing the SLF from reaching the vines in the first place. To tackle this, we opted for a fly trap that uses light as a lure, which allows us to avoid chemicals such as pesticides that are harmful to grapes. The idea was to place these traps outside of grapefields at night to attract and trap SLF, preventing them from getting to the grapes.

![Figure 1: Constructed Final Prototype]({{ "/assets/images/odp6-image1.png" | relative_url }}){: .inline-image-l}

---

### Final Prototype and Application

The device we have fabricated is a light trap that lures SLF away from the grape vines and traps them until they can be disposed of. The main mechanism of the trap is a clear, spinning plate with ridges that allow light to pass through, attracting SLF. The device works by allowing SLF to land on the plate and forcing them to either move into the tube at the center of the trap or be crushed by the interlocking ridges. The trapped bugs will be stored in the bottom container of our device and can be emptied at the user's convenience. The user can then clean out the SLF from the container and either throw them away or reuse them as feed for animals.

![Figure 2: Exploded CAD view here]({{ "/assets/images/odp6-image2.png" | relative_url }}){: .inline-image-l}

---

### Assembly Process

Only two batches of assembly need to take place to build our device. After all the parts are manufactured, you first insert the pinion gear through the hole in the main body and into the crank, then secure it with a through bolt, as described in Figure 3. Next, the ridges press-fit into the holes on the top side of the acrylic plate in descending size order, with the largest ridges on the outside. These were secured with super glue to ensure rigidity. Then, the crown gear is superglued to the bottom side of the acrylic plate, ensuring it is centered. The 3D printed roof is then secured with superglue to the top of the tube, which is part of the device body, and can be viewed in Figure 4. Lastly, the containment tub and cover can be slid into the device body. A fully exploded CAD assembly is shown in Figure 2.

![Figure 3: Crank mechanism here]({{ "/assets/images/odp6-image3.png" | relative_url }}){: .inline-image-l}
![Figure 4: Top assembly here]({{ "/assets/images/odp6-image4.png" | relative_url }}){: .inline-image-l}

---

### Conclusion and Recommendation

Overall, our device met all our success criteria and hit a relatively low cost of $118.75. Quantifiable results supporting this decision can be seen in the testing section. In addition, the parts are easily fabricable, and the device is easy to assemble. For these reasons, we recommend moving forward with this prototype by making slight modifications and performing real-world testing. 

The first modification we would need to make is to replace the crank with a motor for ease and efficiency of use. This obvious modification would also enable our device to operate without human supervision. Then, we would replace our 3D printed gear and pinion setup with a metal one. 3D printed gears wear down quickly, but we were forced to use them since McMaster didn’t have any crown gears big enough to fit around the shaft of our device. We would recommend finding a large gear to purchase or outsourcing a custom gear to fit around the shaft and withstand the wear of the motor.

We would also have to make modifications to accommodate real-world operating conditions. Our only client feedback was that our device needed to be placed away from the grape fields so that it didn’t unintentionally lure SLF to uninfested fields. Because of this necessary distance, we would recommend looking into solar power as a method for powering both the light and the motor. Since our device is primarily meant to operate at night, solar power could be accumulated during the daylight hours and then discharged through the evening. 

Finally, our device requires routine cleaning to remove SLF from the trap and clean dead bugs from around the ridges. Serviceability modifications may need to occur depending on how the device holds up in a real-world environment. In terms of further testing, the main thing we would need to look into is the specific type of light that attracts SLF. There hasn’t been a lot of research on SLF being attracted to light, and we would want to ensure that we are attracting as many SLF as possible to the device. We would also want to test our device in the field to make sure that nothing goes wrong when it is faced with actual bugs instead of paper towel mockups. However, due to our initial success, we think that moving on to this phase of testing would be a good next step.

---

### Testing and Results
In order to ensure that our prototype met our success criteria, we designed tests that would provide an accurate measure of its effectiveness. Firstly, we wanted our prototype to have a large capacity for SLF so it would not have to be serviced as often. We set a target capacity of 1000 SLF as a large overestimate of the number of SLF that would enter the trap per cycle. Indeed, according to a report by Heather and Ashley Leach [1], an average of around 50 SLF were observed entering the target vineyards per day during peak season, so our device would be able to go at least a week without service. We tested this by ensuring that the bottom drawer would open and close consistently and by ensuring that its volume was great enough to hold the SLF. We estimated that we would need a minimum of 4 liters of storage space to hold 1000 SLF, and we checked in CAD to ensure that we achieved this volume. Given that this is a smaller model of what the final product could be, a larger version could potentially go multiple weeks without needing cleaning, making it easier for grape farmers to manage.

The second success criterion we established was that our trap should emit and disperse light effectively. Specifically, we wanted at least 80% of the light from our light source to pass through the trap top in order to minimize power demands and ensure that the strong light didn’t end up overheating the trap. We tested this by measuring the lux coming from our ring light both inside and outside of our trap with a phone app that utilized the phone's light sensor, as seen in Figure 5. We held the phone 5 inches above the light and used a piece of paper as a diffuser. We found that the light dropped very little, from 14400 to 14200 lux, and determined that 98.6% of the light was able to pass through the trap. Our design will be able to let through sufficient light to lure the SLF without expending massive amounts of power.

Our third success criterion was that our trap could handle multiple SLF landing on a section of it at once, as could occur in actual use. We did not have sufficient data on how SLF are attracted to light, so we set a target of handling 3 SLF landing on the trap at once, which we estimated was a reasonable figure. We made small SLF models out of paper towels and tape and attempted to push them through the trap. On our first prototype, where it was easier to simulate the motion of the SLF by pushing them, we were able to fit 6 SLF models through the central tube at once without any getting stuck. On our final, we were able to shake the trap to simulate SLF crawling through the central tube, and 3 SLF were able to be shaken into the holding container at the bottom. This indicates that our trap will be able to effectively handle trapping multiple flies at once.

Our final success criteria was that the trap would not allow SLF to escape once they were on the plate, forcing them to either be crushed or to travel down the central tube. We tested this by placing our SLF models on top and rotating them to see if the flies would be able to escape. When the paper towel flies got trapped between the upper and lower ridges, there were no gaps for them to crawl through, and they were caught between the ridges of the trap, indicating that the bugs would be crushed once our design was constructed with stronger materials. This ensures that the SLF attracted to our trap will be unable to escape and will be forced to either travel into the trap’s center or perish.

We also ran some basic structural tests to simulate real-world conditions such as inclement weather. We shook the machine at 5 Hz, spun the top at 7.25 rad/s, and threw our mock SLF at it to simulate flies landing on the top. It held up through all of those tests, implying that it will not need service often.

![Figure 5: Testing light emission]({{ "/assets/images/odp6-image5.png" | relative_url }}){: .inline-image-l}

---

### Prototype and Testing Details:
Prior to designing and fabricating our final prototype, we built an initial prototype to confirm the functionality of our main mechanism, the spinning top. The main functionality we were hoping to confirm was that the acrylic lid ridges and roof ridges didn’t collide, and that a threat of death was established by the ridges, which would force the SLF down the tube. This prototype consisted of the upper components of our final device – the tube, acrylic plate, ridges, and roof. A string could then be wrapped around screws placed at the edge of the plate, and then pulled, to spin the device. By testing the spinning functionality of the acrylic plate, we were confident that when adding more sets of ridges on the final prototype, everything would work as intended. This testing is shown in Figure 6. Additionally, we tested to make sure that the threat of death was established by the ridges, while also forcing SLF down the tube, by using replica SLF made from paper towels. This testing is shown in Figure 7. As everything worked as planned, we decided to move forward with our design, with only small changes to its tolerances.

![Figure 6: String being pulled to spin]({{ "/assets/images/odp6-image6.png" | relative_url }}){: .inline-image-l}
![Figure 7: Testing threat of death]({{ "/assets/images/odp6-image7.png" | relative_url }}){: .inline-image-l}


## BOM/Component List:

### BOM of Initial Prototype

| Part | Price |
|------|-------|
| 3D Prints | $5.36 |
| Acrylic | $6.62 |
| Laser Cutting | $6.28 |
| **Total** | **$18.26** |

---

### BOM of Final Prototype

| Part | Price |
|------|-------|
| Light | $19.99 |
| 3D Prints | $65.26 |
| Acrylic | $6.62 |
| Wood | $1.75 |
| Laser Cutting | $25.13 |
| **Total** | **$118.75** |

---

### Total Spent

|  |  |
|--|--|
| **Total Spent** | **$137.01** |


### Components:

3D-Prints:

● Ridges (x54 for final; x9 for prototype)

○ Specs: 0.875” tall, widths vary from .25”-1.25”

○ 3D printed out of PLA and done at the RPL

● Roof and Wall

○ Specs: radius = 4.5”, matching ridges 3D printed with roof as one piece

○ 3D printed out of PLA and done at the RPL

● Crown and pinion

○ Specs: 96 and 8 teeth, respectively

○ 3D printed out of PLA and done at the RPL

● Crank

○ Specs: 4” long

○ 3D printed out of PLA and done at the RPL

● Trap Body

○ 9” diameter, 9.5” height

○ 3D printed out of PLA and done at the RPL

● Containment Tub

○ Specs: 295.3 in3 volume

○ 3D printed out of PLA and done at the RPL

Acrylic

● Clear Cast Acrylic Sheet (1 for prototype and 1 for final)

○ Specs: 12" x 12" x 1/16"; McMaster 8560K171

○ Laser cut at RPL

Wood

● 1/16” plywood 12”x12” sheet

○ Laser cut at RPL

Bolts and Nuts

● x4 each for initial prototype

● Free from TDS


[Back to top](#project-milestones)
