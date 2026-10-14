#### Project Completion Log: Day 2 (13th October, 2026)



PROJECT TOPIC: Can Energy Data Help Predict Electricity Supply Problems?



#### STEP 4: UNDERSTANDING THE DATA (CONT'D)



##### PART A



###### The NERC raw data, explained simply



This explains the numbers printed in the three NERC PDFs, in plain language.



**The three PDFs**

|PDF|What it covers|
|-|-|
|`2026\\\_Q2\\\_Report.pdf`|April to June 2026, compared with January to March 2026|
|`2026\\\_Q1-Report.pdf`|January to March 2026, compared with October to December 2025|
|`2025-Annual-Report\\\_Pub.pdf`|The whole of 2025|

**Who is NERC?** The Nigerian Electricity Regulatory Commission. It is the government body that watches over the electricity industry and publishes these reports.



###### Part 1: The story the data tells



Electricity travels through three stages:

1. **Power plants** make the electricity.
2. **The national grid** is the network of high-voltage lines that carries it across the country.
3. **DisCos** (distribution companies) take electricity from the grid and deliver it to homes and businesses. There are 11 DisCos.

The PDFs measure each stage, so you can see how much electricity could be made, how much was actually made, and how much the DisCos took.



###### Part 2: Words and units you need first



Units

|Term|Plain meaning|Everyday comparison|
|-|-|-|
|**MW** (megawatt)|The size or power of something at one moment|How big a tap is|
|**MWh/h** (megawatt-hour per hour)|How much electricity was actually produced or used, on average, in each hour|How much water flowed through the tap per hour|
|**GWh** (gigawatt-hour)|A big total of electricity over a long time. 1 GWh = 1,000 MWh|The total water that flowed in a whole quarter|

A useful shortcut: a MWh/h figure and an average MW figure are the same number. If a plant averaged 100 MWh/h, it behaved like a plant running at 100 MW all the time.

The report turns the hourly average into a quarter total with this formula (it is printed in the Q2 report):



> Total generation = average MWh/h x 24 hours x number of days in the quarter



Example for Q2: 4,022.40 x 24 x 91 days = 8,784.93 GWh after dividing by 1,000.



Other terms

|Term|Plain meaning|
|-|-|
|**Quarter**|A three-month period. 2026/Q1 is January to March, and 2026/Q2 is April to June|
|**Installed capacity**|The most power a plant could produce, as rated by its manufacturer. Think of it as the biggest tap you could fit|
|**Available capacity**|How much of that the plant can actually produce right now. Machines break, need repairs, or run out of fuel or water, so this is usually lower than installed|
|**Generation**|How much electricity the plant actually produced. A plant can be available but not produce much, because it only runs when the grid has demand for it|
|**PAF** (Plant Availability Factor)|Available capacity divided by installed capacity, as a percentage. A PAF of 50% means half of the plant's rated size is working|
|**DisCo offtake**|The electricity a DisCo actually took from the grid|
|**PCC** (Partially Contracted Capacity)|The amount of electricity a DisCo is expected to take, and has to pay for whether it takes it or not|
|**Available PCC**|A DisCo's share of that target after the system operator shares out what is really available|
|**Offtake performance**|What a DisCo took divided by what it was allocated, as a percentage. 100% means it took everything allocated to it|
|**pp** (percentage points)|The difference between two percentages. If PAF goes from 32.72% to 32.69%, it fell by 0.03 pp|
|**Total collapse and partial collapse**|When the whole grid or part of the grid shuts down suddenly|



###### Part 3: Table 1, the Plant Availability table



**Where to find it:** Q2 report page 17, Q1 report page 17.

**What it answers:** "How much of each power plant's rated size is available to produce electricity?"

**How to read it:** each row is one power plant. There are 28 grid-connected plants. The table runs across two pages in the PDF, 18 rows on the first page and 10 on the second.



**The columns:**

|Column|What it means|
|-|-|
|Plant|The plant name. A suffix like `\\\_1` or `\\\_2` marks a unit or block of that station|
|Installed capacity (MW)|The plant's rated size|
|Average Available Capacity (MW), earlier quarter|The average amount that was available to produce in the earlier quarter|
|Average Available Capacity (MW), later quarter|The same for the later quarter|
|Plant Availability Factor (%), earlier quarter|Available divided by installed, times 100|
|Plant Availability Factor (%), later quarter|The same for the later quarter|



**Colours in the PDF:** the PAF numbers are coloured by a rule printed under the table: red if the PAF is below 50, amber from 50 to 80, green above 80.

**Real examples from the Q2 report:**

* **Ihovbor\_2:** installed 461 MW, available 459.40 MW, PAF 99.65%. Almost the whole plant is working. This is the highest in the table.
* **Kainji\_1:** installed 760 MW, available fell from 539.37 MW to 429.25 MW (PAF from 70.97% to 56.48%). The report says some units were shut down for repairs and yearly maintenance.
* **Geregu\_1:** installed 435 MW, available fell from 80.72 MW to 2.44 MW (PAF from 18.56% to 0.56%). Almost nothing is working. This is the lowest in the table.

**The last row, "Total":** it is not a plant. It adds up all 28 plants: 13,625 MW installed, and an average of 4,454.17 MW available in Q2. That makes the national PAF 32.69%, which means about one third of the country's rated plant capacity could be used and about two thirds could not.



###### Part 4: Table 2, the Average Hourly Generation table



**Where to find it:** Q2 report page 19, Q1 report page 18.

**What it answers:** "How much electricity did each plant really produce?"

**How to read it:** each row is one plant, the same 28 plants as Table 1. In the Q2 report the rows are sorted from the biggest increase to the biggest decrease, so the order is different from Table 1. Match plants by name, not by position.

**The columns:**

|Column|What it means|
|-|-|
|Plant|The plant name|
|Average Hourly Generation (MWh/h), earlier quarter|Average electricity produced per hour|
|Average Hourly Generation (MWh/h), later quarter|The same for the later quarter|
|Change (%)|How much the number moved, as a percentage|
|Change (MWh/h)|Later quarter minus earlier quarter. A minus sign means it fell|

**Real examples from the Q2 report:**

* **Afam\_2:** generation rose from 184.29 to 291.27 MWh/h, a gain of 106.98.
* **Kainji\_1:** generation fell from 528.02 to 409.44 MWh/h, a drop of 118.58. This matches the repairs mentioned in Table 1.
* **Geregu\_1:** generation fell from 82.38 to 2.11 MWh/h, a drop of 80.27.

**The last row, "Total":** all plants together averaged 4,112.72 MWh/h in Q1 and 4,022.40 MWh/h in Q2, a drop of 90.32. In total, 12 plants produced less and 16 produced more.

**Difference between Table 1 and Table 2:** Table 1 tells you what the plants *could* do, and Table 2 tells you what they *did*. A plant can be 100% available and still produce little if the grid does not need its power.



###### Part 5: The DisCo Energy Offtake table



**Where to find it:** Q2 report page 30 (Table 3). In the Q1 report it is **Table 4**, page 31.

**What it answers:** "How much electricity did each distribution company take, compared with what it was allocated?"

**How to read it:** each row is one DisCo. There are 11, plus an "All DisCos" total row. The table has two blocks of three columns, one block per quarter.

**The columns (repeated for each quarter):**



|Column|What it means|
|-|-|
|DisCos|The company's name|
|Energy Offtake (MWh/h)|The average electricity the DisCo actually took per hour|
|Available PCC (MWh/h)|The average electricity allocated to it per hour|
|Offtake Performance (%)|Offtake divided by Available PCC, times 100|



**The 11 DisCos:** Abuja, Benin, Eko, Enugu, Ibadan, Ikeja, Jos, Kaduna, Kano, PH (Port Harcourt) and Yola.

**Real example, Abuja in Q2:** it took 520.26 MWh/h out of the 589.31 MWh/h allocated. That is 88.28%, so it left about 12% of its allocation untaken. In Q1 it took 99.60%, so its performance dropped by 11.32 pp, the biggest fall of any DisCo.

**The last row, "All DisCos":** together the DisCos took 3,197.03 MWh/h out of 3,398.41 allocated, which is 94.07%. In Q1 they took 97.11%.

**Why this matters:** under the rules, DisCos must pay for the electricity allocated to them even if they do not take it. So a low percentage means money is paid for electricity that was not used.



###### Part 6: The System Collapse tables



**Where to find them:** Annual Report page 154 (Table 25, for 2025) and Q1 report page 28 (Table 3). The Q2 report says there were no collapses.

**What they answer:** "When did the whole grid or part of it shut down suddenly, and why?"

**How to read them:** each row is one collapse event.

**The columns:**

|Column|What it means|
|-|-|
|SN|The event number in that list|
|Date and time of collapse|When it happened|
|Type of collapse|**Total** or **Full** means the whole grid went down. **Partial** means only part of it did|
|Time of full restoration|When the system came back. This column is only in the Annual Report table|
|Remarks|NERC's short explanation of the cause|

**The events:**

|Date|Type|Time|What happened|
|-|-|-|-|
|10/09/2025|Full|11:20, restored 11:48|Cause not clearly tied to this row in the PDF layout|
|29/12/2025|Partial|14:01, restored 14:30|The remarks mention a failed circuit breaker on a line at Benin station|
|23/1/2026|Total|12:40|A fault at Sapele station cut the power lines in that area, then generation was lost|
|27/1/2026|Partial|10.48 (as printed)|Not enough reactive power to keep voltage steady|



###### Part 7: The monthly charts (Figures A and B)



**Where to find them:** in the summary section near the start of the Q1 and Q2 reports.

These are bar charts, not tables, with the value printed above each bar. They show the same two things as Tables 1 and 2, but month by month for the whole country.

|Month|Available capacity (MW)|Average hourly generation (MWh/h)|
|-|-|-|
|Oct 2025|5,506|4,290|
|Nov 2025|5,544|4,701|
|Dec 2025|5,151|4,367|
|Jan 2026|4,901|4,421|
|Feb 2026|4,384|4,102|
|Mar 2026|4,089|3,815|
|Apr 2026|4,286|4,048|
|May 2026|4,587|4,128|
|Jun 2026|4,489|3,892|

March 2026 was the lowest month for both. The chart values are rounded to whole numbers.



###### Part 8: The national picture, side by side



These totals come from the "Total" rows of the tables above.

|Measure|2025/Q4|2026/Q1|2026/Q2|
|-|-|-|-|
|Installed capacity (MW)|13,625|13,625|13,625|
|Average available capacity (MW)|5,400.38|4,457.96|4,454.17|
|PAF (%)|39.64|32.72|32.69|
|Average hourly generation (MWh/h)|4,452.71|4,112.72|4,022.40|
|DisCo offtake (MWh/h)|3,619.21|3,309.48|3,197.03|
|Offtake performance (%)|92.18|97.11|94.07|
|Days in the quarter|92|90|91|

**What this says in plain words:** available capacity dropped by about 940 MW between the end of 2025 and early 2026, and has not recovered. Generation and DisCo offtake have fallen over the same three quarters.



###### Part 9: Things in the PDFs that can trip you up



1. **Table numbers are not the same in each report.** The DisCo table is Table 3 in the Q2 report but Table 4 in the Q1 report. Look for the title, not the number.
2. **Table 1 is split across two pages,** and the column headings repeat on the second page.
3. **One plant name has a footnote stuck to it.** In the Q2 generation table it prints as `Alaoji\\\_17`. The real name is `Alaoji\\\_1`, and the 7 is a footnote marker.
4. **A dash (-) means no number.** Alaoji\_1 shows a dash for Q1 generation, because it was not available for dispatch then. Its available capacity for that quarter is printed as 0.00.
5. **The Total rows look like data rows** but are sums. Do not add them to the rows above them.
6. **Quarters have different numbers of days** (92, 90 and 91). To compare quarters fairly, use the hourly averages (MWh/h) instead of the GWh totals.
7. **Numbers are rounded to two decimals,** so a column of figures may differ from the printed total by about 0.01 or 0.02.
8. **A minus sign means a decrease** in the Change columns.



###### Part 10: What the PDFs do not tell you



* **There is no quarterly plant or DisCo data for the first three quarters of 2025.** The Annual Report only has yearly tables and monthly charts for those months, and the 2025/Q4 numbers come from the Q1 report.
* **The tables do not say which plant supplied which DisCo.** Plants and DisCos can only be compared as national totals.
* **The reports do not explain the gap between generation and DisCo offtake.** In Q2, plants produced 4,022.40 MWh/h while DisCos took 3,197.03 MWh/h. The tables leave about 825 MWh/h unaccounted for.



##### PART B



###### 1\. Which tables do I need?



For a dashboard about supply problems, four groups of data answer the question "is supply getting tight?":



|Need|Q2 2026|Q1 2026|Annual 2025|Why|
|-|-|-|-|-|
|Plant capacity and availability (MW, PAF %)|Table 1|Table 1|Table 23|Shows how much power could be produced|
|Plant generation (MWh/h)|Table 2|Table 2|Fig 12 (monthly chart only)|Shows how much was produced|
|DisCo offtake (MWh/h, %)|Table 3|**Table 4**|Table 29|Shows how much the DisCos took|
|System collapses|none reported|Table 3|Tables 24 and 25|The clearest "supply problem" events|

## 

###### 2\. Which data do I need from those tables?



* **Per plant:** Installed MW, Average Available MW, PAF %, Average Hourly Generation MWh/h.
* **Per DisCo:** Energy Offtake MWh/h, Available PCC MWh/h, Offtake Performance %.
* **Monthly national:** Available capacity and hourly generation from Figures A and B (Q1 and Q2 reports). These exist only as chart labels, so they are typed in by hand.
* **Events:** Date, type (total or partial) and cause of each collapse.



###### 3\. How do the tables connect?



* **Plants:** Table 1 and Table 2 join on the **plant name**, using the same 28 plants.
* **Time:** Everything links through a quarter or month label (for example 2026/Q2).
* **DisCos and plants do not join.** No table says which plant supplied which DisCo. They connect only at national level, per quarter. In Q2, generation was 4,022.40 MWh/h and DisCo offtake was 3,197.03 MWh/h. The roughly 825 MWh/h gap is not explained in these tables, so it is a question to investigate.
* **Data gap:** There are no quarterly plant or DisCo tables for 2025 Q1 to Q3, only annual figures and monthly charts.



###### 4\. What does one row stand for (the grain)?



|Table|One row is...|Note|
|-|-|-|
|Table 1 (availability)|One plant, two quarters side by side|Reshaped to one row per plant per quarter|
|Table 2 (generation)|One plant, two quarters side by side|Reshaped the same way|
|DisCo offtake table|One DisCo, two quarters side by side|Reshaped the same way|
|Figures A and B|One month, national level|Typed in from chart labels|



###### 5\. What units are used, and are they consistent?



* **MW** is capacity, the rating of a plant.
* **MWh/h** is average hourly energy. It is numerically the same as average MW, so comparing the two is fine.
* **GWh** is the quarterly total: MWh/h x 24 x days / 1,000.
* **Days differ:** Q4 has 92, Q1 has 90 and Q2 has 91. Compare quarters in MWh/h, not GWh, or the extra day distorts the trend. NERC says this in its own footnotes.
* **Percentage change vs percentage points:** NERC uses "pp" for changes in percentages (for example PAF falling 0.03pp). Keep these separate in column names.



###### 6\. Do my totals match the totals the report states?



|Check|My sum|Report states|Match|
|-|-|-|-|
|Installed capacity (28 plants)|13,625 MW|13,625|Yes|
|Q1 available capacity|4,457.95|4,457.96|Yes (rounding)|
|Q2 available capacity|4,454.17|4,454.17|Yes|
|PAF, Q2 (4,454.17 / 13,625)|32.69%|32.69%|Yes|
|Q1 generation|4,112.73|4,112.72|Yes (rounding)|
|Q2 generation (Alaoji's 14.32 added)|4,022.41|4,022.40|Yes (rounding)|
|Q2 total generation|8,784.92 GWh|8,784.93|Yes|
|Q2 DisCo offtake in GWh|6,982.31|6,982.32|Yes|
|Q2 DisCo offtake, sum of 11 DisCos|3,197.05|3,197.03|Yes (within 0.02)|

Further checks that passed:

* **Row counts:** The report says 12 plants decreased generation and 16 increased, and the counts in the cleaned data match.
* **Hydro vs thermal change, Q1 to Q2:** Hydro -118.78 (report -118.79) and thermal +28.46 (report +28.47).
* **Cross-report consistency:** The 2026/Q1 columns in the Q2 report are identical to the Q1 report for all 28 plants and 11 DisCos, so no restated figures were found.
* **Tolerance:** Differences up to about 0.02 are rounding in the reports. A bigger gap points to a data entry error. Generation-change checks use 0.05, because each change adds up to 28 rounded values.

