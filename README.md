## University Recommendation System
<p>University College education plays an important role in a
student’s life. Hence, choosing the right college for the right
student is a highly challenging task. Although many
universities have adapted to centralized admissions, the
system is not efficient and a lot of time is spent in securing an
admission in the institutes. This is primarily due to large
number of applications being submitted to universities every
year. </p>
<p>Recommender Systems are data filtering mechanisms 
which focus on overload of information and filter out
relevant chunks of data according to user preferences. Such
systems have the ability to predict if a user may be interested
in certain items based on their profile. </p>

<p>I have built a recommendation system of my own. Since data was not readily available, I scraped data Edulix.com.
The CSV file is present here named "allUsersFinal.csv". The file is present in .ipynb format.</p>

## Structure of data
53,645 entries finally compiled.  
Each entry has the following properties:
- userName - username in edulix.com
- major - Major in which the user pursued / is pursuing
- researchExp - Research Experience in months
- industryExp - Industry Experience in months
- specialization - Intended specialization for higher studies
- toeflScore - TOEFL Score out of 110
- program - Intended Graduate Level Program 
- department - Department in which the user was / is enrolled
- toeflEssay - TOEFL Essay score out of 
- internExp - Internship Experience in months
- greV - GRE Verbal Score
- greQ - GRE Quants Score
- userProfileLink - Link to the userProfile in edulix.com
- journalPubs - number of Journal Publications
- greA - GRE AWA Score
- topperCgpa - toppers CGPA
- termAndYear - Intended joining term. Eg: Fall - 2015
- confPubs - number of conference publications
- ugCollege - Undergraduate college
- gmatA - GMAT AWA Score
- cgpa - user's CGPA
- gmatQ - GMAT Quants Score
- cgpaScale - CGPA Scale for the user's CGPA
- gmatV - GMAT Verbal Score
- univName - University Name applied to
- admit - Result of the application (0/1 - Reject/Admit)
