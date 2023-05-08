#### Right to left

##### Text alignment
- System-provided UI frameworks support right-to-left (RTL) by default.
- Align a paragraph based on its language, not on the current context.
- Use a consistent alignment for all text items in a list.

##### Numbers and characters
- Don’t reverse the order of numerals in a specific number.
- Reverse the order of numerals that show progress or a counting direction; never flip the numerals themselves.

##### Controls
- Flip controls that show progress from one value to another.
- Flip controls that help people navigate or access items in a fixed order.
- Preserve the direction of a control that refers to an actual direction or points to an onscreen area.
- Visually balance adjacent Latin and RTL scripts when necessary.

##### Images
- Avoid flipping images like photographs, illustrations, and general artwork.
- Reverse the positions of images when their order is meaningful.

##### Interface icons
- Flip interface icons that represent text or reading direction.
- Consider creating a localized version of an interface icon that displays text.
- Flip an interface icon that shows forward or backward motion.
- Don’t flip logos or universal signs and marks.
- In general, avoid flipping interface icons that depict real-world objects.
- Before merely flipping a complex custom interface icon, consider its individual components and the overall visual balance.

https://developer.apple.com/design/human-interface-guidelines/right-to-left
