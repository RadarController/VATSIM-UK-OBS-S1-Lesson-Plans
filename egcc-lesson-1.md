# Manchester

## Lesson 1 - Basic Aerodrome Control 1

- Environment: Sweatbox
- Duration: up to 90 minutes

## Introduction

This is an intro to controlling Manchester on VATSIM, however the skills you learn throughout these lessons will be transferrable to any aerodrome.

Do you have access to the S1 moodle course? Course: [S1 | Aerodrome Control | VATSIM UK](https://moodle.vatsim.uk/course/view.php?id=15). This contains the lesson plan that I’ll be following today, and that your future mentors will use as well.

Do you have access to the Manchester GMP/GMC moodle course? Course: [S1 | Manchester ADC | Delivery & Ground | VATSIM UK](https://moodle.vatsim.uk/course/view.php?id=34). This will be really helpful throughout your mentoring sessions.

- Manchester vMATS: [EGCC vMATS Part 2 - VATSIM UK Documentation](https://docs.vatsim.uk/Aerodrome/EGCC%20%28Manchester%29/0-vMATS/)
- Manchester Crib Sheet: [EGCC Crib - VATSIM UK Documentation](https://docs.vatsim.uk/Aerodrome/EGCC%20%28Manchester%29/0-Crib/)

Which charts will you be using? Can you find them for me?

Today we’ll be completing Lesson 1, which covers the tasks of GMP and GMC at Manchester.

### Objectives

1. Connect to Sweatbox. 
2. Setup EuroScope, the UK Controller Pack and UK Controller Plugin. 
3. Discuss the roles and areas of responsibilities of the GMP, GMC and AIR 
controller. 
4. Select a runway for use. 
5. Talk through the aerodrome layout and ‘standard’ taxi routings. 
6. Practise coordinating an initial logon to the network. 
7. Generate an ATIS. 
8. Explain the use of status blocks and scratch pads.  Give a brief introduction to 
how scratchpads can be used, but emphasise that the student can use them 
however they want. 
9. Explain and practise issuing IFR clearances and mandatory readback items. 
10. Explain and practise using push back and start-up instructions. 
11. Explain and practise using the red-carpet rule. 
12. Explain and practise issuing taxi instructions. 
13. Define and practise using the correct handoff procedure.

### Lesson

1. Confirm that the latest sectorfile and UKCP are installed.
2. Tell me about the roles of GMP and GMC (ref [S1 ADC: Air Traffic Control Units: Types of ATC units | VATSIM UK](https://moodle.vatsim.uk/mod/lesson/view.php?id=454&pageid=844))
    - Ground Movement Control (GMC) units, which control aircraft on the taxiways. Callsign GROUND.
    - Ground Movement Planner (GMP) units, which issue clearances and plan aerodrome movements during busier periods, ensuring efficiency. Callsign DELIVERY.
    - Tower units, which control the runway and aircraft in the air around it. Callsign TOWER. 
3. Can you find the latest Manchester METAR? Which runway should we be using? [METAR EGCC - Manchester Airport, Manchester, United Kingdom](https://metar-taf.com/egcc) (IF 05 OPS – explain that for the purposes of the training we’ll use 23. Explain how to select the runway ref [S1 ADC: Runway In Use: Appropriate selection | VATSIM UK, vMATS 5.5 Preferential Runway](https://moodle.vatsim.uk/mod/lesson/view.php?id=698))
4. Connect to Sweatbox – check login name (EGCC_GND, facility and rating (S1 whilst on Sweatbox) selected, server changed from auto to SWEATBOX or sweatbox-2.vatsim.net if required
    - Selecting active runways
    - Coordinating with other online controllers (use of [CRAFT method: Controller Changeover Aide Memoires - VATSIM UK Documentation](https://docs.vatsim.uk/General/General%20Procedures/Controller%20Changeover%20Aide%20Memoires/))
5. Generate an ATIS using the built in ATIS generator (also talk about vATIS?)
6. List fields (right click callsign, F1+2 to view route, click on runway/SID to change, click on ASSR to generate new one.
    - Leave 3 aircraft on their ASSR and let the student change them, show the difference between aircraft waring the correct SSR versus not
7. STS and Scratchpads – must now start with a . or a / and be understandable by other controllers when relevant
   - Include stand number when a pilot calls up
8. Mention vACDM plugin ([A-CDM Controller Guide - VATSIM UK Documentation](https://docs.vatsim.uk/General/Use%20of%20Software/A-CDM/)) but don’t go into detail at this stage
9. Can you explain what is in a standard IFR clearance? ([S1 ADC: Control of Surface Traffic: Issuing a route clearance | VATSIM UK](https://moodle.vatsim.uk/mod/lesson/view.php?id=774&pageid=1301)). Let’s practice.
    - You will NOT be expected to provide re-routes during tonight’s session
    - Ensure the spad is updated with the stand number
    - Correct SID? ASSR? QNH confirmed (_vMATS GEN 1.1 – all departing aircraft must state it, otherwise GMP to confirm_ and _ADC 1.2 – Issuing clearances_)?
    - Put into practice
10. Can you **clear** an aircraft for push and start? ([S1 ADC: Control of Surface Traffic: Pushback | VATSIM UK](https://moodle.vatsim.uk/mod/lesson/view.php)) What information do we need to include in a push and start instruction?
    - Have we confirmed the stand number? 
    - Will pushing an aircraft affect other inbound or outbound aircraft?
    - Do we need a direction?
    - Put into practice
11. Looking at the SMR, explain standard taxi routes (outbound via D, P, K, J. Inbound via A, B, etc. Look at Zulu and the colours, ability to have 737/A320 series on blue and orange (ref Manchester Airport trials new dual taxiway) using Sweatbox tool to demonstrate if student isn’t able to visualise
12. Have you heard of the “red-carpet” rule for taxying aircraft?
    - Explain the rule and how it is implemented by VATSIM UK (effectively it's not, but it's important to monitor aircraft that _might_ come into conflict)
    - Demonstrate
    - Put into practice
13. Handing aircraft off to AIR
    - Sequencing West, Northeast and Southeast departure routings
    - How early can you hand something off to AIR?
    - What is “clean of conflict”
    - At Manchester, aim to transfer aircraft BEFORE J3, ideally once they pass J4, assuming they’re clean – this gives AIR time to sequence aircraft by moving them between M1 and J1.
    - Put into practice
