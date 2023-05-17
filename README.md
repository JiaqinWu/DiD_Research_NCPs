# DiD_Research_NCPs

Consider a state government in the United States that administers a child support program. This program requires non-custodial parents (NCPs) to pay monthly child support payments to custodial parents of their children. If NCPs fail to make payments, they can owe child support debt, leading to incarceration.

Suppose that a state child support agency introduced a program to provide intensive case management services to NCPs so that they could help them find jobs to make child support payments and have better relationships with their non-custodial children and the custodial parents. The program was administered in selected local child support sites across the state, and in these sites, the program was rolled out at varying dates.

Please download final_data_dd.csv. This dataset contains the following site-level panel data (each row in the dataset corresponds to an observation for a given site at a given calendar quarter):
• site_id = identification number for a local child support office site

• year_qtr = calendar quarter of observation (eg 2011.25 is the second quarter in 2011)

• treatment = indicator equal to 1 if the site was selected for treatment

• treatment_year_qtr = calendar quarter the site began the program if selected for treatment

• ncp_emp_rate = employment rate for NCPs served by the site in the calendar quarter

• smom_emp_rate = employment rate for single mothers served by the site in the calendar quarter

• ncp_wdebt = fraction of NCPs served by the site in the calendar quarter that owe child support debt

• Nncp = number of NCPs served by the site in the calendar quarter
