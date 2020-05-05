# Ender 3 Build Guide

This build guide is intended to compliment the instructions included with the printer, providing detail and additional steps to ensure print quality.

A few things to know before we start. Nothing in this build will require tightening with a power tool, everything should be tightened by hand using the hex keys provided - this will stop you from stripping any threads.

Above all else, **be patient**, this may take a few hours, but taking the time to get things square and level will pay off later - 3D printers work in measurements of microns, the smallest thing can have a cascading effect.

1. Unbox your wonderful new 3D printer and verify that all parts are undamaged and present in accordance with the manual provided (there may be some spare bolts).

2. Start by turning the main assembly upside down, this will give you a clear view to tighten all the bolts on the underside of the printer. While you're here it may be necessary to adjust the eccentric nuts to ensure that the bed has no play, these should be adjusted so they're _just_ tight, while still being able to move freely, without spinning when the bed moves.

3. Now is also a good opportunity to change the bed springs if you've got replacements, simply unscrew each of the wheels, replace each spring and screw back on (loosely at this point).

5. Screw each spring down until they're finger tight, as soon as you feel resistance stop.

6. Flip the assembly, and tighten the rest of the visible bolts. Be careful not to overtighten anything, only hand tight. Now is also a good opportunity to tighten the Y belt (if needed, it should produce a noise when plucked).

7. Next grab the vertical extrusions, the right extrusion will need to be attached with the two screws on the inside of the unit, with the lower holes near the bottom. The left extrusion will need the same with the two parallel holes on the bottom. Leave the bolts for these loose for the moment in order to square the frame.

8. As you have probably noticed there is a bit of play from each extrusion, so it's important to ensure they're both secured straight. Grab the X extrusion and place it against the two vertical extrusions, effectively straightening them out. At this point you can screw the bolts in to finger tightness.

9. Grab a straight edge, or something to measure the distance between the two vertical extrusions at the top and the bottom - you may find that it's wider at the top than at the bottom. If this is the case, start by loosening the left (typical) or the right extrusion. While ensuring that the extrusions remain straight, tighten the outer screw a little, then tighten the inner screw just half a turn more than the outer. Remeasure, you may need to repeat this a few times to get it squared, just ensure that you continue to check they are straight with the X extrusion.

11. Attach the display to the right front lower extrusion, plugging the cable into COM3.

12. Switch the PSU to your required voltage then attach the PSU to the rear right of the vertical extrusion.

13. Take each of the wheel carriages and place them on the vertical extrusions, tighten the bolts on the outer wheels, then adjust the eccentric nut to the point where there is no play in the carriage, but it's still able to fall freely to gravity. Take these off, we'll continue to assemble them later.

14. Attach your Z-stop switch to the lower left extrusion using the T-nuts, placing the tab on the lower extrusion.

15. Attach the Z stepper to the rear left vertical extrusion. Leave the screws a little loose to allow play in the stepper.

16. Slide the Z lead screw fully into the coupler on the stepper, then tighten the coupler, ensuring that the lead screw is secure.

17. Measure the top and bottom of the Z lead screw distance from the vertical extrusion, move the stepper to a position where this is equal the entire length of the lead screw. Take care ensure that the lead screw is aligned both horizontally and vertically to the extrusion, this will help to avoid binding issues. Tighten the stepper to the extrusion once the lead screw is fully aligned.

Some printers may be unable to fully align the lead screw, in which case it may be appropriate to print a bracket or spacer to allow for a wider freedom of movement in the lead screw position.

18. Attach the extruder carriage to the left of the X extrusion, taking care to level the carriage.

19. Place the timing belt around the X stepper fixture, wrapping the length of the top of the extrusion.

20. Slide the hotend carriage onto the X extrusion, adjusting the eccentric nut to a point where the carriage is able to move with little resistance.

21. Attach the right carriage to the X extrusion, taking care to level the carriage to the extrusion.

22. Slot the timing belt ends into the underside of the hotend carriage.

23. Attach the right belt fixture to the X extrusion, tightening the belt.

24. Tighten screws holding the the lead screw nut on the rear left carriage, then loosen them 1 whole turn. This allows for some play in the Z movement to help with binding.

25. [Level the X-Axis](x_axis_adjustment.md).

26. Plug in all steppers and endstops as labelled.

27. [Calibrate the e-steps of the extruder](extruder_calibration.md).

28. Place the bowden tube into the extruder, then place the included clip under the collar of the coupler to avoid it slipping.

29. Level the bed.

30. Print!

If your board did not ship with thermal runaway protection you should update the firmware as soon as possible.