# degree-planner
## **Prompt:**
Build an interactive course planner to assist students planning their next semester’s course load.
## **Problem:**
Students struggle to plan courses around prerequisites and availability.
## **MVP:**
An interactive course planning tool that helps students organize their upcoming semesters by accounting for class schedules, prerequisites, and course availability. Students begin by selecting the courses they have already completed, and the system evaluates eligibility for future courses based on prerequisite chains and semester offerings.
The tool then generates suggested next courses along with a basic 2–4 semester plan using a greedy scheduling approach. The planner ensures that selected courses meet prerequisite requirements and are offered in the chosen semester while helping students build a structured path toward degree completion.
Key MVP Components:
•	Student input: completed courses
•	Logic constraints: prerequisites, semester availability, class times
•	Output:
o	List of eligible next courses
o	2–4 semester plan using basic greedy scheduling
•	Interactive planning interface for semester-by-semester course selection
## **Beyond MVP:**
Constraint options: “no more than 15 credits,” “avoid morning classes”, etc.
## **Available Resources:**
Small mock catalog dataset in <u>*Course Catalog.csv*</u> and <u>*Class Schedules.csv*</u>
