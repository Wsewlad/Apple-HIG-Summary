#### Dark Mode is a systemwide appearance setting that provides a dark color palette for a comfortable viewing experience in low-light environments. Here are some best practices and guidelines for using Dark Mode effectively in your app or game:

1. **Avoid offering an app-specific appearance setting:** Instead, respect the systemwide Dark Mode preference chosen by users. Offering a separate appearance setting for your app can confuse users and create extra work for them.

2. **Ensure your app looks good in both appearance modes:** Users can choose to switch between light and dark appearances or use the Auto appearance setting, which automatically adjusts the appearance based on the time of day. Test your app in both modes to ensure it remains visually appealing and functional.

3. **Test legibility in Dark Mode:** In Dark Mode, certain color combinations may reduce legibility, especially when users have enabled options like Increase Contrast and Reduce Transparency. Make sure your text remains comfortably readable in both appearance modes by testing it in different scenarios.

4. **Consider using a permanently dark appearance:** In some cases, such as media viewing apps, it may be appropriate to use a permanently dark appearance that allows the user interface to recede and focuses attention on the media content.

5. **Adapt colors to Dark Mode:** The color palette in Dark Mode includes dimmer background colors and brighter foreground colors. When using custom colors, ensure they adapt to the current appearance by adding bright and dim variants. Avoid hard-coded color values or colors that don't adapt to Dark Mode.

6. **Aim for sufficient color contrast:** Maintain a good contrast ratio between foreground and background content to ensure readability. For system-defined colors, the minimum contrast ratio should be 4.5:1, while custom colors should strive for a ratio of 7:1, especially for small text.

7. **Soften white backgrounds:** If your app displays images with white backgrounds, consider slightly darkening the images to prevent them from appearing too bright in the Dark Mode context.

8. **Use SF Symbols and optimized images:** SF Symbols automatically adapt to Dark Mode, and full-color images should be optimized for both light and dark appearances. Utilize SF Symbols wherever possible and create separate interface icons for light and dark appearances if necessary.

9. **Utilize system-provided label colors:** Use the system-provided label colors, such as primary, secondary, tertiary, and quaternary labels, which automatically adapt to light and dark appearances. This ensures consistent legibility across different backgrounds.

10. **Use system views for text fields and text views:** Instead of drawing text yourself, utilize system-provided views and controls for displaying text. These views adjust automatically for vibrancy and background changes, ensuring your app's text looks good on all backgrounds.

##### Remember to consider platform-specific guidelines for Dark Mode implementation on iOS, iPadOS, and macOS. By following these best practices, you can create an optimal Dark Mode experience that respects user preferences and enhances the usability of your app or game.

https://developer.apple.com/design/human-interface-guidelines/foundations/dark-mode
