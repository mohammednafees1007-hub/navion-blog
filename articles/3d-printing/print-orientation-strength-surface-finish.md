# Why Print Orientation Matters for Strength and Surface Finish

Before a model is printed, someone must decide which way it sits on the print bed. For a custom part, that decision should reflect what you need from it: a presentable front face, a reliable fit, or the ability to carry a particular load.

You do not need to choose the final orientation yourself. You can help by explaining how the part will be used and which features matter most.

## The same model can have different printing trade-offs

In filament printing, orientation affects how the part is built layer by layer. Prusa's design guidance explains that strength is direction-dependent and that supported surfaces can have a different finish from other faces. Turning a model can also change where support is required. These are reasons to discuss orientation alongside geometry and material rather than treating it as a purely cosmetic choice. [Prusa: Modeling with 3D printing in mind](https://help.prusa3d.com/article/modeling-with-3d-printing-in-mind_164135).

There is no orientation recommendation in this article for a specific NAVION order. The following example is a planning exercise, not a manufactured or tested part.

## Example: a small sensor bracket

Imagine an L-shaped bracket that holds a sensor beside a student robot's chassis. Before asking how it should be printed, mark three things on a sketch:

- Where the bracket attaches to the chassis.
- Where the sensor attaches and the direction it must face.
- Which way the bracket might be pushed during use.

Then label any face that should remain visually tidy. If you send only a model without this explanation, the reviewer may not know which of these requirements takes priority.

A useful enquiry could say: “The upright face holds the sensor. These two holes must match my existing board. The bracket may be pushed backwards when I handle the robot. Please review the printing orientation and tell me if the design needs changing.”

This wording identifies a use case without pretending the model has already been validated for it. Include actual component dimensions and expected loads when known; do not replace measurements with an unsupported claim that the bracket must be “very strong.”

## Ask for the trade-off to be explained

When reviewing the proposed print, ask which surfaces will contact support, which features deserve a fit check and whether the intended use raises concerns. Prusa also discusses splitting a model into separate parts to improve printing orientation; that is an option to assess, not a requirement for every design. [Prusa's design guidance](https://help.prusa3d.com/article/modeling-with-3d-printing-in-mind_164135).

If a split design is proposed, clarify how the pieces would be joined and whether assembly is included. Agree on any design revision before approving the files and quotation.

## Decide what the first print must prove

For the hypothetical bracket, a first check might establish that the holes align and the sensor can be positioned correctly. That result would establish fit only. It would not prove durability during robot operation.

Keep the approved model version and record the checks you actually perform. If the part needs revision, describe the observed problem and the change you want evaluated.

NAVION 3D is based in Kumbakonam, serves Thanjavur and ships across Tamil Nadu. [Submit your model for review](https://shop.navionrobotics.com/3d-printing) with a sketch showing the important faces, connections and intended use.

## Related reading

- [Planning 3D-Printed Parts for a Student Robot](robot-parts-printing-brief.md)
- [From First Print to Better Prototype: Recording Useful Feedback](first-print-to-revised-prototype.md)
