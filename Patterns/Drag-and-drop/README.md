# Drag and drop

As a general rule, dropping selected content within the same container moves it, whereas dropping content in a different container copies it.

## Best practices
- As much as possible, support drag and drop throughout your app.
- Offer alternative ways to accomplish drag-and-drop actions. 
- Determine when dragging and dropping content within your app results in a move or a copy.
- Support multi-item drag and drop when it makes sense.
- Prefer letting people undo a drag-and-drop operation.
- Consider offering multiple versions of dragged content, ordered from highest to lowest fidelity.
- Consider supporting spring loading.

## Providing feedback
- Display a drag image as soon as people drag a selection about three points.
- If it adds clarity, modify the drag image to help people predict the result of a drag-and-drop operation.
- Show people whether a destination can accept dragged content.
- When people drop an item on an invalid destination, or when dropping fails, provide visual feedback.

## Accepting drops
- Scroll the contents of a destination when necessary.
- When there’s a choice, pick the richest version of dropped content your app can accept.
- Extract only the relevant portion of dropped content if necessary.
- When a physical keyboard is attached, check for the Option key at drop time.
- Provide feedback when dropped content needs time to transfer.
- Provide feedback when dropped content initiates a task or action.
- Apply appropriate styling to dropped text.
- After a drop, maintain the content’s selection state in the destination, updating it in the source as needed.

https://developer.apple.com/design/human-interface-guidelines/drag-and-drop
