📊 DST Reports Generator

🧾 Overview

This project generates Daylight Saving Time (DST) reports for a selected timezone across a specified range of years.
It helps identify DST start and end transitions programmatically without manual calculation.

🎯 Features

Select any valid timezone
Generate DST data for a custom year range

Outputs:

DST start date
DST end date

Time shift details (if applicable)

⚙️ How It Works

Uses system timezone and calendar APIs
Iterates through each year in the given range
Detects DST transitions based on time changes
🚀 Usage

```
generateDSTReport(
    timezone: "America/New_York",
    startYear: 2020,
    endYear: 2025
)
```
📦 Sample Output

Year: 2023
DST Start: 2023-03-12 02:00
DST End:   2023-11-05 02:00

Year: 2024
DST Start: 2024-03-10 02:00
DST End:   2024-11-03 02:00

🧠 Use Cases

Calendar and scheduling apps
Timezone-based calculations
Debugging DST-related issues
Backend systems handling global users

⚠️ Notes

Some timezones do not observe DST
DST rules may change based on region policies

🎯 Goal

Provide accurate and reliable DST transition data for any timezone and year range.
