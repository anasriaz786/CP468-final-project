Analysis on US Universities Data and Modelling Tuition

Short description:

Machine learning is a core sub-area of Artificial Intelligence (AI). ML applications learn from experience (or to be accurate, data) like humanswe do without direct programming. When exposed to new data, these applications learn, grow, change, and develop by themselves. In other words, machine learning involves computers finding insightful information without being told where to look. Instead, they do this by leveraging algorithms that learn from data in an iterative process. 

The concept of machine learning has been around for a long time (think of the World War II Enigma Machine, for example). However, the idea of automating the application of complex mathematical calculations to big data has only been around for several years, though it’s now gaining more momentum. 

The Machine Learning process starts with inputting training data into the selected algorithm. Training data being known or unknown data to develop the final Machine Learning algorithm. The type of training data input does impact the algorithm, and that concept will be covered further momentarily. New input data is fed into the machine learning algorithm to test whether the algorithm works correctly. The prediction and results are then checked against each other. 
If the prediction and results don’t match, the algorithm is re-trained multiple times until the data scientist gets the desired outcome. This enables the machine learning algorithm to continually learn on its own and produce the optimal answer, gradually increasing in accuracy over time. 
 
Types of Machine Learning 
Supervised learning: You supervise the machine while training it to work on its own. This requires labeled training data. 
Unsupervised learning: It requires training data, but it won’t be labeled. 
Reinforcement learning: The system learns on its own. 

This project would be centered around Supervised learning.
-------------------------------------------------------------
Dataset being used:

US Universities Data (1300 cases, 30 variables): This dataset is taken from the 1995 U.S. News
& World Report’s Guide to America’s Best Colleges. Information on around 30 variables for each
of over 1300 American colleges and universities is given. See the link
“http://lib.stat.cmu.edu/datasets/colleges/readme” for details. You could pre- dict several variables
including public/private.



   WHAT'S WHAT AMONG AMERICAN COLLEGES AND UNIVERSITIES?

This is the subject of the 1995 Data Analysis Exposition
sponsored by the Statistical Graphics Section of the American
Statistical Association.  The purpose of the Exposition is to
encourage statisticians to demonstrate techniques, especially
graphical, for analyzing data and displaying the results of an
analysis.  Individuals and groups will work with the same set of
data and present their analyses at a special session as part of
the annual Joint Statistical Meetings in Orlando, Florida on
August 13th-17th, 1995.  The datasets for 1995 are drawn from two
sources, U.S. News & World Report's Guide to Americas Best
Colleges and the AAUP (American Association of University
Professors) 1994 Salary Survey which appeared in the March-April
1994 issue of Academe.

The U.S. News data contains information on tuition, room & board
costs, SAT or ACT scores, application/acceptance rates,
graduation rate, student/faculty ratio, spending per student, and
a number of other variables for 1300+ schools. The AAUP data
includes average salary, overall compensation, and number of
faculty broken down by full, associate, and assistant professor
ranks.

The raw data and documentation are contained in the files
described below.  To obtain any of these files send a message to
statlib@lib.stat.cmu.edu of the following form  (substituting the
file you want for XXXXX)

      send XXXXX from colleges

Available files

   usnews.doc      Documentation for the U.S. News data
   usnews.data     U.S. News data in comma delimited format
   usnews3.data    U.S. News data in fixed column format

   aaup.doc        Documentation for the AAUP salary data
   aaup.data       AAUP salary data in comma delimited format
   aaup2.data      AAUP salary data in fixed column format

Two versions of each dataset are provided to accommodate users
with different software constraints.  The comma delimited
versions (USNEWS.DATA and AAUP.DATA) contain information for each
college on a separate line with values delimited by commas.  The
fixed column versions (USNEWS3.DATA and AAUP2.DATA) use 2 or 3
data lines per school and a maximum line length of 80 characters.

To participate in the 1995 Data Analysis Exposition you must send
an abstract form to the American Statistical Association by
February 1st, 1995.  Information is available from the ASA
Meetings Department by e-mail (meetings@asa.mhs.compuserve.com),
phone (703-684-1221), fax (703-684-2037), or surface mail (ASA,
1429 Duke St., Alexandria, VA 22314).  Your initial abstract may
be fairly general since you may do the bulk of your analysis
after the February 1 deadline.

You may choose your own path to proceed in analyzing the data or
use some of the suggested questions below to get started.

... How well can we model tuition using the other variables?
... How might we cluster colleges into similar comparison groups?
... How can we best display faculty salary structure?
... Can we find a reasonable way to rank the schools?

You may work on your own or put together a team.  Show off the
capabilities of your favorite software package or use the data
for a class project and display your students results.  You may
choose to consider just a subset of schools or examine regional
patterns.  The main point is to find innovative ways to display
the interesting features of the data.

Further questions about the 1995 Exposition can be directed to
Robin Lock, Mathematics Department, St. Lawrence University,
Canton, NY 13617  e-mail   rlock@vm.stlawu.edu

If you would like to be informed about any subsequent adjustments
or error fixes to the 1995 Exposition data, please send an e-mail
message to register your interest to rlock@vm.stlawu.edu.

Special thanks for providing data for the 1995 Exposition to:
Robert Morse, Director of Research for America's Best Colleges at
              U.S. News & World Report
Maryse Eymonerie, Consultant to AAUP.
