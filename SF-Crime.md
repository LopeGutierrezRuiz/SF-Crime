# Explore a snapshot of SF crime incident reports from 2014 with pivot tables #

**Examine a category of crime:**
I examined several crime categories (as stated on “category”), and then compared them with the results of each incident (as stated on “resolution”).

**Process:**
I merged the January-March and May-July tables, made a pivot table of the merged table, and utilized the following fields:

Row Labels: Category (types of crime)
Column Labels: Resolution (arrest, not arrest, etc.)
Values: Resolution (in count format)

Afterwards, I made a clustered column visualization, which can be seen here:
http://i.imgur.com/6C27gvC.png

I used yearly totals (minus April, not included in the datasets), so there was no need to slice the data into smaller time / data intervals. I also made some crime-specific tables and visualizations to review the ratio of “resolutions” for some crimes.

**Notes:**
From the pivot table and data visualization, a couple of items quickly stand out:

**1) Most of larceny / theft incidents are not resolved:** 93% of cases have a “none” resolution, and only 7% end up in an arrest, either booked or citation. The number of cases that are not solved is so high (12,000+), that I had to modify the maximum height of the Y axis in the column graph, because that lone data point was dwarfing all other columns.

**2) Most drug / narcotic incidents end up in an arrest or citations:** 91% of all drug cases have an “arrest” resolution. Additionally, 8% of cases have an “exceptional clearance” outcome; which according to FBI standards means that the case has the following characteristics / timeline: 

> “The agency must have: 1) Identified the offender. 2) Gathered enough evidence to support an arrest, make a charge, and turn over the offender to the court for prosecution. 3) Identified the offender’s exact location so that the suspect could be taken into custody immediately. 4) Encountered a circumstance outside the control of law enforcement that prohibits the agency from arresting, charging, and prosecuting the offender.”

Even more importantly, these “circumstance(s) outside the control of law enforcement” most commonly are:

> 1) The death of the offender.
2) The victim’s refusal to cooperate AFTER the offender has been identified. 
3) The offender’s arrest and prosecution in a different jurisdiction.

**3) Good luck finding the criminal who stole your car / motorcycle / bicycle:** only 3.5% of vehicle theft cases involve an arrest, while 93% of these cases have a “none” resolution.




