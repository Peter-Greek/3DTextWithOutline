# 3DTextWithOutline

Simple function that I had made a while ago, 3d text with boarder outline, options to change font scale and color along with amount of lines. Some helper functions inspired by Native UI. Took a long time to get the numbers right but still sometimes they are off set by a few pixels.

```
-- x,y,z is the coords where the 3d text should display
-- font is font index I suggest 4
-- scale is scale of the text I suggest 0.35
-- exLines is amount of extra lines there should be, you can check your string before hand for /n default should be 0
-- rgb is a table ex. {r = 255, b = 255, g = 255} 
exports['3dTextWithOutline']:DrawText3DWithOutline(x,y,z,text, font, scale, exLines, rgb)
```
