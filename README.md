# Online Courses initiative by IIT Madras
Our goal is to provide high quality education to the masses. It has been estimated that the IITs have an acceptance rate of less than 2%, so only a small portion of students make the cut. Only students who enter the hallowed halls of academia are able to gain access to pertinent content. But there are several talented students, from local colleges, whose talent needs to be fostered because they cannot gain access to quality education. If these students don’t get access to good material and strengthen their academic talents their professional lives and future are in jeopardy. From our experience, we have noticed that several faculty members in many local colleges are also unaware of the fundamental concepts in their domain. This leads to their inability to teach these concepts accurately to their students. In some cases, the faculty have the knowledge but the teaching material falls short. In this case the teaching methodology is impaired and so is the process of student assessment. Students get stuck in this vicious cycle, and their talent is frittered away. 

Online MOOCs in India such as Swayam and NPTEL are doing their part in breaking these barriers and have become the pioneers in this space. We are not in competition with them but to aid and further their effectiveness. This will be accomplished by making available additional content in the form of the complete course material taken from the IIT curriculum along with all the relevant material. This course content can be accessed by the students from local colleges in both the urban and the rural areas. The noble cause of imparting education can be achieved via this platform – which will eventually create well-qualified engineers.

# Contributors
- **Webpage**: [Rudra Desai](https://rudradesai.in/)
- **Course Assessment**: [Kshitij Deogade](https://www.linkedin.com/in/kshitij-deogade-500364154/?originalSubdomain=in), Mani Chandana, [Rudra Desai](https://rudradesai.in/), Sravankumar Reddy
- **YouTube Channel**: [Dileep Pattipati](https://scholar.google.com/citations?user=nQLh4CwAAAAJ)
- **Coordination**: [Faculty members](http://www.cse.iitm.ac.in/listpeople.php?arg=MSQw) of CSE Department, IIT Madras

# How to run locally
- Clone this repository
- From the main directory, run `hugo server -D`
- This will start the website on `localhost:1313/cse`

# How to add courses
- First follow the above steps to run the repository locally
- Next, go to `$MainDir/content/services` directory
- Add a page called `$CourseName.md`
- Checkout other pages in the directory to find the structure
- Follow the structure and add content

# How to push the changes
- First make sure it works fine on your local machine by following the above steps
- Next, push the changes to the repository.
- This will update the website in the gh-pages branch
- Go to the server, and run `git pull`
- This will update the website there