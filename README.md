# Pewlett-Hackard-Analysis
Use SQL techniqufes to create Entity Relationship Diagrams, design and manage tables, perform data modeling and complete an analysis on an employee database.

## Results
- The Pewlett Hackard Human Resources (HR) Department is preparing for several employees to retire. A quick query assisted HR in determining that 72,458 current staff (including position) are eligible for retirement and can be viewed here: [retiring_title.csv](https://github.com/gforce2332/Pewlett-Hackard-Analysis/blob/main/Data/retiring_titles.csv)
- In light of the sheer numbers of employees eligible for retirement, HR is considering a mentorship program. Those 1549 eligible employees can be viewed here: [mentorship_eligibility.csv](https://github.com/gforce2332/Pewlett-Hackard-Analysis/blob/main/Data/mentorship_eligibility.csv)
- From these table we are able to make the following determinations:
  - Nearly a third of the retirees are Senior Engineers while another third are Senior Staff.
  - Given the high numbers of senior staff retiring this will be a priority for HR to fill. 
  - The eligible number of employees for the mentorship program makes up just 2% of those employees eligible for retirement.
  - There are several more employees retiring than potential mentors. This should be a point of emphasis for the company to eliminate such a large learning curve going forward. 

## Summary
As the "silver tsunami" begins to make an impact it will be important to determine how many roles need to be filled annually. We can create a table to categorize the retirees into age groups and the company can aim to replace those individuals each year. We currently have a list of employees that were born between 1952 and 1955 which can be used to determine hiring quotas for each of the following four years. 

An additional query can be created to group mentor-eligible employees into position titles. Using this list the company can prioritize how many mentees a mentor could potentially take on to fulfill the retired roles as well as determine any gaps in position titles where mentors may be lacking. 
