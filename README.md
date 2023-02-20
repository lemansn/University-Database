# Aim of Design

Our aim is create a database that stores and provides all meaningful data of a university. We will implement all necessary requirements by taking given design as base.

 Requirements:

● Database should keep track of the curriculums of each of the following departments in Turkey, respectively, Computer Engineering, Software Engineering, Artificial Intelligence Engineering.

● Each curriculum is composed of its own courses of type mandatory, optional (technical or non-technical).

● Design should have entities like CHAIR, FACULTY MEMBER (PROFESSOR, ASSOCIATE PROFESSOR, ASSISTANT PROFESSOR, INSTRUCTOR, RESEARCH ASSISTANT)

● Design should be able to store the instructors of the courses with their SECTION information.

● You should store information about the research areas of the FACULTY MEMBERs, their M.Sc. and Ph.D. theses.

● You should also store the keywords associated with each course and these keywords should be related to the research areas of the FACULTY MEMBERs to find whether a given COURSE is instructed by the most matched FACULTY MEMBER.

● For each of the course and curriculum, you should store a computed value of this matching
criteria.

# Brief Explanation

An entity is a living or non-living thing. It can be person, object or concept. Entity is represented by rectangular box. Followings are entities of given design: STUDENT, INSTRUCTOR, DEPT, COURSE, SECTION, COLLEGE Each entity has it’s own set of attributes. It presented by ellipses. Followings are some of the attributes of given design: Name, Address, Grade, Rank etc. Each entity has a relationship with other entities. It represented by diamond shape rectangles. For example an INSTRUCTOR, TEACHES a SECTION. Also it has object oriented features such as inheritance in EER.

# Restrictions in system:

-> FAC_MEMBER and STUDENT are PERSON’s subclasses and they connected with disjoint. So PERSON can be only one of them.

-> INSTRUCTOR and RES_ASSIST are FAC_MEMBERS’s subclasses and they connected with disjoint. So FAC_MEMBER can be only one of them.

-> PROFESSOR, ASSIST_PROF and ASSOC_PROF are INSTRUCTOR’s subclasses and they connected with disjoint. So INSTRUCTOR can be only on of them.

-> TEORICAL and LABORATORY are SECTION’s subclasses and they connected with overlap. So SECTION can be both of them or not.

-> MANDATORY and OPTIONAL are COURSE’s subclasses and they connected with disjoint. So COURSE can be only one of them.

-> TECHNICAL and N_TECHNICAL are OPTIONAL’s subclasses and they connected with disjoint. So OPTIONAL can be only one of them.

# Enhanced E/R Diagram

![EER-Model](https://user-images.githubusercontent.com/78681001/219978709-48ae3760-7864-435f-905b-3b07d8d15929.png)
