# sbacdata

Each year in California, public school students take SBAC tests in both ELA (english language arts) and math. The scores that students get on these tests are used by parents, teachers, and other school site staff to gauge student progress for the year.

For more on SBAC testing, click here.

School performance on SBAC tests is a big deal for the state of California, and in the public Charter School world, philanthropic funders heavily weigh a school's performance on SBACs for whether or not they want to continue or begin funding.

The way that the scores are presented in this project are as "proficiencies". After the tests are administered, the state decided what the "mean scale score" for proficiency is. Then when comparing school data, you look at the percentage of students in that school who've scored either at that proficiency or above.

For example "In the fourth grade class at XX school, 47.2% were proficient on the ELA SBAC test."
This means that in that fourth grade class, 47.2% of students scored at or above the designated proficiency level.

After looking at SBAC data for other areas of my work, I was interested in how a parent's highest level of education correlated with proficiency levels throughout the state. This project pulls in data files from the [CA Dept of Education's research files](https://caaspp-elpac.cde.ca.gov/caaspp/DashViewReport?ps=true&lstTestYear=2019&lstTestType=B&lstGroup=1&lstSubGroup=1&lstSchoolType=A&lstGrade=13&lstCounty=00&lstDistrict=00000&lstSchool=0000000) and then cleans the data the point where I'm able to run a t-test comparing the mean proficiency of the students in CA whose parents have not graduated from high school, with the mean proficiency of the students in CA whose parents' highest level of education was a high school diploma.
