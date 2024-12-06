
# Team-binary_builders
This project is an end-to-end Restaurant Finder System, enabling users to search, review, and rate restaurants, while business owners can manage their listings and admins oversee platform integrity, with integration to Google Maps API for location-based searches. It features role-based functionality, secure backend (Node.js, MongoDB), and a responsive frontend (React), deployed on AWS.

**CMPE 202- Fall 2024**

### Team Members:

1.  Ajay Kumar Golla(018201430)
2.  Paavani Karuturi(017643301)
3.  Teja Swaroop Reddy Mareddy(017405765)
4.  Vinuta Patil(018196035)

#### [](https://github.com/gopinathsjsu/team-project-cmpe202-01-binary_builders#TeamContributions)Team Contributions:


#### [](https://github.com/gopinathsjsu/team-project-cmpe202-01-binary_builders#git-repo)Git repo:

[https://github.com/gopinathsjsu/team-project-cmpe202-01-binary_builders](https://github.com/gopinathsjsu/team-project-cmpe202-01-binary_builders.git)

#### [](https://github.com/gopinathsjsu/team-project-cmpe202-01-binary_builders)Project board:

[https://github.com/gopinathsjsu/team-project-cmpe202-01-binary_builders](https://github.com/gopinathsjsu/team-project-cmpe202-01-binary_builders)

#### [](https://github.com/gopinathsjsu/teamproject-infinite-loop#sprint-task-sheet)Sprint Task Sheet:

[[excelLink](https://docs.google.com/spreadsheets/d/1MSPdcmwkwZXbuFtzDVEz78sek2BK80BRWdIDJ6g_dJU/edit#gid=0)]
#### [](https://github.com/gopinathsjsu/teamproject-infinite-loop#project-journal)Project journal:

[[project Journals](https://docs.google.com/spreadsheets/d/13ifYS0cvCskVYWZeW7qtzdIvE56V-BZ0SJAOnOvEcyw/edit?usp=sharing)]

#### [](https://github.com/gopinathsjsu/teamproject-infinite-loop#xp-values)XP Core Values Maintained by Team:

**Simplicity** -
Our approach prioritized implementing the simplest and most effective solutions. We designed the code to be modular and reusable, ensuring that it is easily understandable and modifiable by any team member in the future. Efforts were made to minimize code smells, and we included relevant comments for clarity. This approach has resulted in a straightforward code base that is easy to maintain.

**Feedback** -
By consistently giving and receiving feedback, we were able to learn, adapt to changes, and avoid repeating errors, enhancing our efficiency. Throughout the development process, we created pull requests and committed our changes to a branch. These changes were only merged into the master branch after receiving approval from another team member. This practice ensured that any updates to the master branch were stable and did not negatively impact other team members' work. Continuous feedback played a crucial role in aligning our goals and responsibilities.

**Communication** -
Effective communication was a cornerstone of our team's approach throughout the project. Initially, we collaboratively brainstormed the project's concept and distributed tasks among ourselves. We held regular sprint meetings where team members discussed challenges they encountered and conducted retrospectives on aspects that didn't go as planned. This open communication ensured a smooth project workflow and team synergy.  

- *In-Person Meetings*: Conducted regular in-person discussions to plan, review, and track project progress.  
- *WhatsApp Messaging*: Used WhatsApp for quick updates, queries, and coordination through a dedicated group chat.  
- *Document Sharing*: Collaborated using Google Drive for sharing files and maintaining project documentation.  
- *Flexible Communication*: Engaged in ad-hoc discussions and brainstorming sessions as needed for seamless teamwork.

#### [](https://github.com/gopinathsjsu/teamproject-infinite-loop#how-to-run-the-web-app)How to run the web-app:

-   Step 1: Clone the app by command " git clone "
-  Step 2: Go to the client directory and install node modules by command "npm i OR npm install"
-   Step 3: Run the client by command "npm run dev"
-   Step 4: Go to the server directory and install node modules "npm i OR npm install"
-   Step 5: Run the server by command "npm run start"


#### [](https://github.com/gopinathsjsu/teamproject-infinite-loop#feature-set)Feature Set:

 🌟 Highlights

- **Next.js**: For a seamless, server-rendered React experience
- **Tailwind CSS & Material UI**: For stylish, responsive designs
- **Daisy UI**: Extending Tailwind with beautiful component classes
- **Zustand & ZOD**: For state management and validation schema
- **JWT**: Secure authentication tokens for our API interactions
- **MongoDB & Redis**: Persistent and in-memory databases for optimal performance
- **SendGRID**: Reliable email service for user engagement
- **Stripe**: Seamless and secure payment processing
- **AWS Suite (S3, EC2)**: Robust and scalable cloud infrastructure
- **NGINX**: High-performance web server setup
- **Node.js & ExpressJS**: Efficient server-side scripting and API management


#### [](https://github.com/gopinathsjsu/teamproject-infinite-loop#design-decisions)Design Decisions:

--------Filll----

#### [](https://github.com/gopinathsjsu/teamproject-infinite-loop#ui-wireframes)UI Wireframes:

[https://github.com/gopinathsjsu/teamproject-infinite-loop/tree/main/UI_Wireframes](https://github.com/gopinathsjsu/teamproject-infinite-loop/tree/main/UI_Wireframes)

#### [](https://github.com/gopinathsjsu/teamproject-infinite-loop#diagrams)Diagrams:

##### [](https://github.com/gopinathsjsu/teamproject-infinite-loop#Component-Diagram)Component Diagram

[![archd](https://raw.githubusercontent.com/Mahendra-Chittupolu/Mahendra/master/Untitled%20Diagram%20(1).jpg)](https://raw.githubusercontent.com/Mahendra-Chittupolu/Mahendra/master/Untitled%20Diagram%20(1).jpg)


##### [](https://github.com/gopinathsjsu/team-project-code_team15#deployment-diagram)Deployment Diagram:

[![Deployment diagram](https://raw.githubusercontent.com/Mahendra-Chittupolu/Mahendra/master/Untitled%20Diagram%20(2).jpg)](https://raw.githubusercontent.com/Mahendra-Chittupolu/Mahendra/master/Untitled%20Diagram%20(2).jpg)



## 🚀 Deployment

Our API and database are deployed on AWS, leveraging auto-scaling EC2 clusters with a load balancer to ensure high availability and performance.

## 📲 User Interface

Accessible via web or mobile, our UI is meticulously designed to cater to Members, Non-Members, and Theater Employees with role-specific functionalities.

## 🛠️ Features

- **General Access**:
  - Home/Landing Page with theater info, schedules, and upcoming movies
  - Membership options with benefits outlined
  - Registration/Signup for new users
  - Movie ticket booking with an online service fee

- **Members**:
  - Personalized member page
  - Book/cancel tickets, use rewards, and waive service fees (Premium)
  
- **Theater Employees**:
  - Manage movie schedules
  - Configure theater seating and discounts
  - View analytics dashboard

## 🎁 Extra Features Unique to MovieTheater Club

- **Box Office Store**: A marketplace for movie merchandise.
- **Private Screenings**: Book an entire theater for exclusive viewings.

## 📊 Feature Comparison Table

| Feature | BOX OFFICE | Others |
|---------|-------------------|--------|
| Merchandise Store | ✅ | ❌ |
| Private Screenings | ✅ | ❌ |
| Rewards Program | ✅ | ✅ |
| Role-Based UI | ✅ | ✅ |
| Multi-Location Support | ✅ | ❌ |

## 📝 Requirements

Our application stands out with its focus on team collaboration. The project's success is a testament to individual dedication and our collective synergy.

## 🧑‍💻 Contributing

Interested in contributing? Great! We welcome pull requests, and for major changes, please open an issue first to discuss what you would like to change.

## 📜 License

[MIT](https://choosealicense.com/licenses/mit/)

---



