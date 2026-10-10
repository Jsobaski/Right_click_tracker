# Green Tracker

One-page tool for collecting front / center / back green coordinates for the
Vegas Golf GPS app. It replaces the "right-click in Google Maps, copy, paste
into Excel" loop.

## Use

1. Double-click `green-tracker.html` to open it in Chrome (no install or server needed; it needs internet for the map).
2. Click **Open workbook…** and pick `Vegas_Golf_GPS_Green_Coordinates.xlsx`.
3. Pick a course. If the map lands in the wrong spot, type the course name or
   paste a `lat, lng` into the search box.
4. Right-click the front edge of hole 1's green, then the center, then the back.
   The page moves on to the next point after each right-click
   (1 Front → 1 Center → 1 Back → 2 Front …).
5. Click **Download .xlsx**. You get the same workbook back with the yellow
   cells filled in, and the rest of its formatting kept.

To redo a point, click its cell in the table (or its marker), then right-click
again, or drag the marker. `Ctrl+Z` undoes. The **Depth** column shows the
front-to-back distance in yards and turns orange if it looks wrong
(under 12 or over 60 yards).

Points are saved in the browser as you go, so closing the tab doesn't lose work.
They are only written into the spreadsheet when you click **Download .xlsx**.

## Notes

- Satellite imagery is Esri World Imagery, not Google. In Las Vegas it is
  high resolution, and the offset from Google's imagery is typically a meter or two.
- Some starting coordinates in the workbook are off. For example, the Revere
  tab points about 4 km from the actual course. Use the search box. The page
  remembers where you left the map for each course.
