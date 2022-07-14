# inverter-setup

# Inverter installation

This document provides resources to help install an inverter and battery to help limit the impacts on load shedding. Please consult with a qualified electrician. Please do not get electrocuted or burn your house down. Electricity is dangerous.

This document is divided into the following section

*   Background 
*   Shopping list
*   Changes to Electrical configuration in DB
*   Battery and inverter setup
*   Commissioning 

## Background

The solution described in this document is aimed at providing power to low power devices during load shedding. Typical devices powered are:

*   Lights
*   Modems
*   Computers
*   Electric gate / garage doors

This solution focusses on solving a particular need of load shedding i.e. up to a 6 hour power outage every 24 hours as per the table below:

| Need | Description | Suitability of solution |   |
| --- | --- | --- | --- |
| Load shedding | Powering low energy devices e.g., modem and lights for a 6 hour period every 24 hours | Yes |   |
| Extended power outage | Powering devices during an extended outage e.g., substation failure for more than 6 hours | No |   |
| Reduction in electricity bill | Power saving interventions e.g., Gas geyser/ Solar power to reduce electricity bills | No |   |
| Shift to green energy | Migration away from fossil fuel based energy e.g., Solar Power | No |   |

The load shedding solution described in this document is designed to automatically take over powering the home when there is no Electricity Feed i.e. there should be no disruption in power during load shedding and no human intervention is needed. If you are on a conference call when load shedding starts, you will not notice your modem switch off as it will receive continuous power. 

## Shopping list

The following items should be procured prior to the electrician arriving to install the unit.

| Item | Description | Possible supplier |   |   |
| --- | --- | --- | --- | --- |
| Mini DB | 8 way DIN rail populated surface mount DB |   |   |   |
| Changeover switch | 40A DIN rail change over switch |   |   |   |
| Inverter | 
The following models have been proven in use

KODAK Solar Off-Grid Inverter VMIII 5kW 48V

growcol-mks-iv-5600-48-off-grid-inverter

 |   |   |   |
| Battery |   |   |   |   |
| Fuse |   |   |   |   |
| Fuse holder |   |   |   |   |
| Battery link cable |   |   |   |   |

## Changes to Electrical configuration in DB

See diagram below

### Modification to existing DB

1.  Identify circuit breakers with which will be powered during load shedding \[UPS breakers\]  (ensure these breakers do not include high powered appliances e.g., kettle)
2.  For the UPS breakers identified in step 1, identify the neutral for each breaker
3.  Arrange the UPS breakers within the DB next to each other
4.  Connect the UPS breakers neutrals to a dedicated bus neutral bus bar (at this point the neutrals for the UPS breaker are not connected to anything
5.  Add a positive bus bar to connect the UPS breakers incomers (optional)

### Install mini DB

1.  Mout mini DB next to current DB
2.  Install Changeover switch, earth leakage and main isolator in DB
3.  Wire the Mini DB to the Main DB as per diagram
4.  Note that the Earth leakage on the mini DB is the Earth Leakage for all UPS breakers and that the UPS breaker neutral bus bar is tied to the neutral bus bar installed in the existing DB

![](https://lh4.googleusercontent.com/FQiI4cPj6Ddklp5J6_zF6xVipiZQtN7Uy135dqXwYBNBL5CXJARfuNR0EJxyz8AU_s8fQv9WQDhqUIA43FmUaQ1DkqAAMp0OyzChc4CFeZWeiyzZ7mtnnDqMIwDMKp3QWloiWQsf9YZvuk3mJi0)![](https://lh3.googleusercontent.com/uHqtJxdOjiVuA6jiuF_DoGsX78iT2JzcrXWCV7BYN6F58LrgOSc9pZBAVDzC8ceyT3fV3_91ExVGuhmUAkcTFAGZ4Qdq4ryD9sk8E5IwiJjEzY8nwxFKA5EqeyCjwP7FRViNvmWg0p9JxcrWH2k)

## Battery and inverter setup

1.  Mount inverter on wall, ensure distance to battery is sufficient for the ground and ethernet cable to reach from the inverter to the battery
2.  Batteries are typically placed on the floor, if there is a risk of water, suggest placing the battery on bricks to raise above floor level
3.  Wire the inverter to the mini DB
4.  Mount the fuse on the red battery cable
5.  Wire the battery to the inverter
6.  Install the ground between the inverter and battery (insure the inverter is connected to ground in the mini DB)
7.  Connect the network cable from the battery to the inverter, the cable only work one way - the end of the cable marked battery must be connected to the battery
8.  See the photos below for the battery settings and network cable connections

![](https://lh4.googleusercontent.com/cnfTBGkI73ZxgQrvb78ls7ulTP6HsQHgolku6zhOqtlZ-IOdeUXIx1-wcccBjd8TBkjZVBvBmSjZpc5DqvGzYS_Md-kcru0xde0E6r_qxE0qAfDwBUuAEV2PIocxLQuc1IBAA21IrXP1oXjP32s)![](https://lh3.googleusercontent.com/-CZUHnCdgMN96hot5WrJiugL1i0xm-vhnLno6yN2whox2GMCnfqX8FuMqGbiPKhLFT98M3X9iaPukyzilVLsHpG7bnHo1jQ7ip361Dm3e6nfwHTUV_oCdPlUb71apfSxco9XG56MarTzgA78SvU)

## Commissioning 

1.  Check all wiring 
2.  Test the UPS loads are powered when the change over switch is set to mains
3.  Power up the battery - this should result in the inverter turning on (Off grid inverters will not activate without the battery on) \[To power up the battery hold down the red button and switch the power button)
4.  On the inverter menu navigate to battery and choose pylon tech
5.  The battery icon on the screen should flash showing comms with the battery as per pictures

![](https://lh6.googleusercontent.com/5K5ZiXCsRB7bdVGJtOPAMLkUsw4_qj2twZSjxcflKXUFLCdADHYfdqv8YmRTBxIYSjDxcM192ToFfJZq0r3pulrJyjdb60kO2_sEB67HsiN-WODNdSN5YnVSFUFFJh2hMQLoBEXRBxNOdGjgKLs)
