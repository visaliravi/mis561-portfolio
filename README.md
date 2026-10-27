# mis561-portfolio
Portfolio of projects for my Data Visualization course. And this repo will have all the projects associated with the course.

# Certification
https://verify.skilljar.com/c/7uj2kaoipt9b

# Dashboard
1. Advancing in Excel & Tableau, Part 1: Initial E-Commerce Profitability Analysis. Which single product subcategory should Southwest Office Solutions place on next fiscal year's margin recovery plan?

Published workbook: https://public.tableau.com/views/Muthuvisali_Flex3/ExploratoryDash?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link. 

If I did it again, I would test the recommendation against profit per order as well as total profit, since Tables and Bookcases rank differently on the two measures and an executive could reasonably ask which one I used.

2. Advancing in Excel & Tableau, Part 2: Account Profitability and Service Tiers. Which single change to Southwest Office Solutions' FY2026 account service policy recovers the most money once the cost of serving each account is charged against the profit it earns?

Published workbook: https://public.tableau.com/app/profile/muthuvisali.ravichandra.bose/viz/Muthuvisali_Flex4/AppliedChart?publish=yes

If I did it again, I would test cost to serve against order count as well as account revenue, since the policy charges a flat $400 to Inside Sales accounts placing anywhere from 2 to 17 orders, and rep time plainly scales with orders rather than with revenue.

3. Power BI Certifications:
   
-> Introduction to Power BI: https://public.tableau.com/app/profile/muthuvisali.ravichandra.bose/viz/PowerBICertificates_17906641699740/PowerBIStory?publish=yes

-> Introduction to DAX, 10/02/2026: https://public.tableau.com/app/profile/muthuvisali.ravichandra.bose/viz/PowerBICertificates_17906641699740/PowerBIStory?publish=yes

In Flex 4, I calculated net contribution for each account as profit minus cost to serve in a Net Contributions column of my account summary, copied down all 793 accounts, then averaged it across the 78 Managed accounts to get $317 per account against Finance's $500 target. In Power BI I would build that figure as a measure, total profit minus total cost to serve, divided by the number of Managed accounts in view, and keep only Tier and Cost to Serve as calculated columns, since those are fixed properties of each account. The reason is that this number has to respond to whatever the reader filters: a column copied down the rows is frozen at refresh and cannot be re-averaged for one region or segment, while a measure recalculates the total and the account count together every time. 

-> Data Visualization in Power BI, 10/11/2026:
https://public.tableau.com/app/profile/muthuvisali.ravichandra.bose/viz/PowerBICertificates_17906641699740/PowerBIStory?publish=yes

Sarah, I am ready for this role because I can decide where a calculation belongs and what a reader should see first. In Flex 4, my Account List showed every account with net contribution as plain numbers, so Marcus had to scan the whole table to find the 337 accounts that earn less than they cost to serve. Rebuilt in Power BI with conditional formatting on net contribution, the 174 Inside Sales accounts in that group would turn red inside the list he already reads. My Flex 4 recommendation to reset Inside Sales cost to serve to $300 rests on a break-even of $353 per account, which is Inside Sales profit of $126,778 divided by 359 accounts. As a DAX measure, that figure would recalculate by region or segment, so Marcus could test the reset himself.

For division of labor, I would use Excel to check a formula or a single file before it goes anywhere, Tableau to explore unfamiliar data and make a one time argument where I control the design, as I did in my Flex 4 justification, and Power BI for reports that refresh on a schedule and that Anita and Marcus filter on their own. My honest gap is that I have never run Power BI Desktop against real company data or published to the Power BI Service. To close it, I would rebuild my Flex 4 account model on a Windows machine, publish it to a test workspace, schedule a refresh, and ask a colleague to try to break it.

I used Claude to help draft and edit this entry, and I checked the figures against my own Flex 4 workbook.


4. MIS 561 Advancing in Excel and Tableau Pt. 3, Card Portfolio Review: Which cards without contactless should Card Operations replace early in one batch at about $8 per card?[ [Card Portfolio workbook]](https://public.tableau.com/app/profile/muthuvisali.ravichandra.bose/viz/CardPortfolio_17924518323790/ExploratoryDash?publish=yes). If I did it again, I would test the six month cutoff against how many customers each batch reaches, not only the card count.

5. Advancing in Excel and Tableau, Pt. 4: Where should the Wildcat Rewards Card pilot mailing go? [[Tableau link]](https://public.tableau.com/app/profile/muthuvisali.ravichandra.bose/viz/AdvancinginExcelandTableau_17930642235000/ExploratoryDashboard?publish=yes). If I did it again, I would define the pilot group by account open date instead of state, since the April 2021 customers may be a cleaner list to mail.
