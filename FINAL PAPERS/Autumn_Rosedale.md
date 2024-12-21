## myfit
Autumn Rosedale, Fall 2024

### Vision/Key Features
My project is a fitness app called myfit. The vision of my project is “to create an inclusive, user-friendly fitness app that empowers users of all ages to set health goals, track workouts, and build community through real-time progress sharing.” I want my app to have features that allow it to stand out against competitors on the market. One of the features that makes my app special is its goal-setting ability. Users can set goals such as heart rate, step, and workout goals. The progress made on goals can be viewed through progress visualizations. There are a variety of visualizations that users can pick from depending on their needs and wants. 

Additionally, users can track workouts in real time while they are completing them. For example, a user would be able to set a run goal of three 45-minute runs a week, but for one of these runs, they want a mile time of 6 minutes per mile. They will be able to set their run goal to track their three runs in a progress visualization and be notified when they hit their mile goal while working out. This feature allows users to set multiple goals at the same time across workouts. Lastly, my app will have a social media feature. On the social media platform, users can post their workouts, clean eats, and progress. Additionally, there will be a feature similar to Instagram reels and a like button. The goal is to make this platform a fun place where I not only connect people to their workouts but also to a community of others who have the same interests.

### OPEN SOURCE: Principles of Open Source
Open source refers to a philosophy where the source code of software, or the design of a project, is made publicly accessible. Myfit will be following this philosophy and its three core principles: transparency, collaboration, and accessibility. The source code used will be shared publicly for contributions and improvements. I want to build a community where members can review, contribute, and improve my code. In addition, the open-source model encourages collaboration among contributors, testers, and users. Collaboration encourages innovative solutions and faster improvements. Lastly, my product will be accessible to anyone with access to the Android or Apple App Store. For those with disabilities, there will be features such as voice-to-text and read-aloud text, and those brought through suggestions after release to address their needs. 

In my open-source community, I plan to implement automation. Automation can help streamline repetitive processes in open-source environments. This will include bots for FAQS and onboarding. Automated bots can address frequently asked questions and guide new contributors through onboarding. Both of these tasks are time-consuming, and this would allow that time to be spent elsewhere. In the case of onboarding, bots would help reduce the barriers to entry. Lastly, Bots can act as timely feedback tools, providing real-time feedback on contributions. This will Aid in helping contributors stay engaged and motivated. It can be frustrating for contributors to go through multiple sources to get to one answer that could be provided by a quick search with a chatbot.

There may be a lot of benefits to automation, but there are also challenges. One of these is the risk of bots misinterpreting issues. This could lead to bots providing inappropriate responses that may offend or upset users. Additionally, by using bots, we risk cutting out communication. In open-source environments, communication is key, and by using bots, users may feel the interactions are impersonal.

### Technical Debt
Technical depth is the Cost of additional rework caused by using quick fixes during development. Individuals choose to use an easy solution because it takes less time and resources than a more comprehensive approach. Technical debt can be avoided by building a strong foundation with tools that have good community support during development. Additionally, regular testing stages can aid in identifying and fixing bugs early on. We do not want to wait longer than needed when fixing bugs because they can escalate into larger issues later. 

For my fit, I anticipate technical debt from React Native, Node.js, Firebase, and MongoDB. React Native simplifies cross-platform app development but often relies on third-party libraries for extended functionality. Relying on third-party libraries can cause technical debt because, over time, these libraries can become outdated or unsupported and require costly updates or replacements. Node.js and Firebase may introduce scaling challenges. While Firebase is effective for handling concurrent user requests, performance may degrade as myfit scales. For Node.js, vendor lock-in poses a risk since migrating to another service may be difficult. Costs will also increase as the app grows and attracts more users. Lastly, MongoDB is used for storing user workout data and is highly scalable. As my user dataset grows, poorly managed indexes can slow down database queries. Regular audits and index optimization are essential to deduce technical debt and maintain smooth performance throughout myfit’s life.

### Motivation, Purpose, and Goals
My motivation to build myfit was to address the limitations within existing fitness apps. As someone who has experience using multiple existing fitness apps, I wanted to make an app that I felt could satisfy all user needs. I want to make fitness fun and inclusive through accessible technology. My purpose is to provide users with an interactive platform to track fitness and share progress. Progress can be shared through several mediums, such as videos, posts, and comments. I want users to have a platform where they feel part of a community that doesn't judge them no matter where they are in their fitness journey. I want the platform to have a social feature so that individuals are motivated to go on, not just to check the workouts. 

### Target Audience
My app is aimed at targeting health and fitness enthusiasts as well as those who want to get started in fitness but don't necessarily know how to. Individuals can be from all age groups, but I anticipate the majority will be middle age. I will be able to target more users because my app will have a simple interface. Additionally, individuals will feel supported socially through collaboration and engagement with this online community.

### Workflow
- Sprint 1: Initial planning and tool selection
- Sprint 2: Backend development (Node.js, Express.js)
- Sprint 3: Database integration (MongoDB)
- Sprint 4: Social feature development (Firebase)
- Sprint 5: Frontend UI/UX design (React Native)
- Sprint 6: Testing (bug fixing and optimization)
- Sprint 7: Launch preparation and marketing

### Methodologies/Technology
 My technology stack is as follows:
- Backend: Node.js with Express.js
- Frontend: React Native (cross-platform)
- Database: MongoDB
- Real-Time Updates & Login: Firebase

I'm opting to use an agile methodology. This methodology focuses on iterative development through the use of weekly sprints. There will also be regular feedback and testing stages. 

### Building Communities
With the development of myfit, I plan to build an open-source community. In the initial development phase, my core team will consist of three to five contributors. The broader community of my app will consist of developers, testers, and open-source contributors. Additionally, there will be incentives for contributing to myfit. First, contributors will receive recognition in the app community. The better my fit performs, the better the contributors look. There will also be opportunities for skill development and collaboration among contributors. Lastly, the automation tools mentioned earlier, such as Bots for onboarding and FAQs, will support the broader community. 

### Continuous Adaptations
There's always room for improvement and continuous adaptation. I plan to adapt to feedback with regular updates based on user feedback and new technologies. I will consider scalability by Mongo DB indexing strategies for growing my user data, monitoring Firebase costs, and exploring alternatives for vendor login. I will decrease technical debt management by addressing outdated libraries and middleware when issues arise. Lastly, I will automate administrative tasks like progress tracking and Bug reporting to make my platform more efficient.

### Conclusion
Myfit is a community-focused real-time fitness tractor meant to bring users together in an inclusive community where they can feel comfortable being themselves. Built with scalability, technical debt management, and open-source principles, my platform aims to bring individuals from all areas together. My goal is to provide a seamless user experience and sustainable growth through strong developmental architecture. I plan to expand my fit with advanced analytics, games, and global accessibility.