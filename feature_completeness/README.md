Feature Completeness Report
===========================

Generate a nice Scaled Agile Framework (SAFe) Feature Completeness report using Excel and a macro. With data rows added for epics, features, and stories it's just a matter of clicking a button to generate an easy to read rich feature completeness report.

### Features of the report
* Works with the Blue Agility Rational Team Concert SAFe Add-on
* Sample RTC queries are provided in the "Instructions" sheet but data can easily be gathered from other sources using the same column and data formatting
* The data for epics, features, and stories is straightforward to enter on individual sheets
* Color coding for each sprint with a percent complete for a given sprint
* Features are grouped by their parent epic for a more holistic picture

See the [screenshot](screenshot.png) for an example report generated with the sample data loaded into the workbook.

### Basic Usage
1. Load epic, feature, and story data into their respective sheets
2. Switch to the "chart" sheet and press the "Refresh" button to generate new chart data
3. Save and Publish as HTML to get a PNG image for sharing across the enterprise
4. Enjoy!

Also, feel free to run the report even prior to the completion of a program increment for a nice visual queue of progress.

### Note
The feature completeness report uses a VB script macro to make the user experience better while generating the chart data. Due to the macro, a security warning is likely to be shown when opening the workbook. The macro is only triggered by pressing the "Refresh" button on the chart sheet and it's purpose is only to refresh the chart data based on the supplied epic, feature, and story information.

### License
This should probably be looked into but this software is being provided as is and free. This is meant to help present a SAFe metric and has no malicious intent. That said, please use this feature completeness report at your own risk and by using the report you agree to assume all liability should something go wrong.
