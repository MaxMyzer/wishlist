JPEG XL is an amazing file format. With it's very high maximum resolution, animation support, and support for a large number of color channels, it is a good format to store scientific images in. For example, GOES satellite imagery - giving each band it's own color channel is easily possible. 

However, most applications that support JXL do not consider extra channels on top of RGBA. An application for viewing data stored in JXL should be created. This should support:
 - Channels
   - Transparency: Toggle visibility and adjust opacity
   - Colors: Adjust what color a channel renders as – or even set a custom gradient rather than fading to "off".
 - Time
   - Navigate frame-by-frame
   - Play at a modified speed multiplier 
   - Play using a set frame-to-frame interval, or using XMP timing information
 - Space
   - Allow users to zoom into a zone
   - Partial progressive decoding support
