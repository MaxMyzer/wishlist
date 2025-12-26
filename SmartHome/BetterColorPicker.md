## Color Spaces
Current implementatin: A simple RGB color wheel is presented to the user
Desired behavior: Allow users to have the colors presented in other formats, like HSV and OkLAB.

### custom colors
Users should be able to set custom endpoint colors. This is useful if the user is doing something like using a WS2811 to control color temperature instead of RGB

## Addressable Control
Curerent implementation: Anything other than a static color must be selected from a preset supplied by the integration.
Desired behavior: Particularly for ESPHome devices, allow for some more advanced control over content from within HomeAssistant. Examples:
0D (single): 
 - color transitions
 - patterns
1D (strip):
 - color gradients
 - animations (direction, speed, etc)
2D (matrix):
 - patterns with keyframes
