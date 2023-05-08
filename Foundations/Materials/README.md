#### Materials

The Apple platform provides a set of materials that offer translucency and blurring effects for background layers to create visual separation from foreground layers. These materials can be combined with vibrancy to add visual interest and enhance the sense of depth in the interface. The system defines several materials and effects that automatically adapt to light and dark modes and offer smooth transitions between apps. When choosing materials and effects, it's essential to consider their semantic meaning and recommended usage and avoid selecting them based on their color appearance. 

To ensure legibility, it's recommended to use only vibrant colors on top of materials. iOS defines dynamic system colors that work well on translucent backgrounds, and macOS provides vibrant versions of all standard colors. Using SF Symbols instead of full-color icons is also recommended, as symbols and interface icons work with dynamic system colors and vibrancy effects to look good in any context. 

When choosing a material to combine with blur and vibrancy effects, it's essential to consider contrast and visual separation. Thicker materials can provide better contrast for text and other elements with fine features, while translucency can help people retain their context by providing a visible reminder of the content that's in the background. 

##### Platform considerations:

iOS and iPadOS define vibrancy values for labels, fills, and separators that are specifically designed to work with each material, while macOS provides materials that define the amounts of translucency, blurring, and vibrancy applied to the interface. macOS defines two modes that blend background content: behind-window and within-window. The sidebar, window background, and selection materials display different amounts of transparency and blending in a light and dark appearance. 

##### Best practices:

- Choose system-defined materials and effects based on semantic meaning and recommended usage.
- Use only vibrant colors on top of materials to ensure legibility.
- Consider using SF Symbols instead of full-color icons.
- Consider contrast and visual separation when choosing a material to combine with blur and vibrancy effects. 
- Test the interface in a variety of contexts to discover when vibrancy enhances the appearance and improves communication.
- Choose a background blending mode that complements the interface design.

https://developer.apple.com/design/human-interface-guidelines/materials
