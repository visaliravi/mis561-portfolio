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
