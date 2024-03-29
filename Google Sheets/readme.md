# Google Sheet
Google Sheets - Full Course by Freecodecamp
[Link to youtube turotial](https://www.youtube.com/watch?v=N2opj8XzYBY&list=WL&index=1&t=39s)

* Picture first
* Anatomy of a spreadsheet
  * Freeze row or column from view->freeze / by dragging the thick line
  * Drag a few numbers and the bottom right corner will show some quick calculations.
* Data types
  Number | Proportion | Percentage | Type % | Decrease Decimals | Increase Decimals | Accounting | Financial | Currency | Data | Time | Text | Links | Web data | Formulas | Web images | Local image(floating)
  ```
  =GOOGLEFINANCE("ENB”)
  =GOOGLEFINANCE("CURRENCY:USDCAD")
  ```
* Formatting cells
  * Snap to fit, Double-click on the right of the column
  * Text wrapping, put the text on multiple line for visibility 
* Tidy data
  [Tidy data link to read](https://cran.r-project.org/web/packages/tidyr/vignettes/tidy-data.html#:~:text=Tidy%20data%20is%20a%20standard,Every%20row%20is%20an%20observation)
* Sharing files
* Sharing folders
* Entering data
* Importing data
* Copying & pasting data
  * Copy and right-click -> Paste special
* Notes
  * Right-click or Insert -> Insert note
* Comments
  * Same as note but show who commented on it and start a thread
* Chat
* Selecting & moving data
  * Ctrl + Space: Select till the last row or until a blank row
  * Shift + Space: Select till the last column or until a blank column
* Sorting data
  * If you want to do multiple sort. You have to do it backward. First the second layer and then the first layer.
* Filtering data
* Filter views
  * You can save the filter view with the name and filter
* Publishing files
  * You can publish to the web to share with others through links of other formats or embed the sheet.
* Version history
  * Keep logs of every change so you can look them up and restore the version.
  * Version control like GitHub
* REPT charts
  ```
  =REPT("|",L8)
  ```
* Bar charts with table data
* Bar charts with raw data
* Grouped bar charts
* Bar chart with highlighting
* Pie charts
* Histograms
* Line charts
* Timelines
* Sparklines
  ```
  =SPARKLINE(D2:D18)
  =SPARKLINE(D2:D18, {"ymin", 0})
  =SPARKLINE(D2:D18, {"color", "#CC0000"; "linewidth", 2})
  =SPARKLINE(D2:D18, {"charttype", "winloss"})
  =SPARKLINE(J2, {"charttype", "bar"; "max", MAX(j$2:J$7)})
  ```
* Scatterplots
* Scatterplots with highlighting
* * Automatic charts with Explore
* Publishing charts
* Cell references
  * Relative reference: A1
  * Absolute reference: $A$1
    Ctrl + `  (Show formula)
* Counts, sums, & means
  ```
  =COUNT(range) : count the number
  =COUNTA(range) : count all
  ```
* Dates & times
* Selecting text
  ```
  LEN
  FIND
  LEFT
  RIGHT
  TRIM
  ```
* Combining text & data
  ```
  &
  JOIN
  ```
* Conditional formatiing


  Graphs -> Number
  Besides, people are good at visual analysis.
