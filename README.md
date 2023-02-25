# Resources for EECE3093C

This repo holds a collection of Markdown documents organized by subject, offering you supplementary materials to enhance our class discussions. You can navigate and delve into the topics with ease using the class date as a guide.

### Current Week 

This is the tentative plan for week 8 of the semester.

<details>
  <summary>Tuesday, February 28, 2023</summary>

  - GitHub Actions

</details>

<details>
  <summary>Thursday, March 2, 2023</summary>

  - 

</details>


---

### Previous Classes

Previous classes listed in reverse chronological order and grouped by week.

#### Week 7

<details>
  <summary>Thursday, February 23, 2023</summary>

  - There were no slides for today's lecture.
  - We discussed a commerical product called [Pulse Grow](https://pulsegrow.com), noting the price of the product relative to the cost of the hardware.  In many ways, hardware is very generic, it is the software that creates the value proposition.
  - We discussed geolocation and some of the complexities in getting an accurate location, and touched a bit on privacy.
    - Accurate geolocation from a computer is nearly impossible, the location comes from your Internet Service Provider (ISP).
      - I used my home as an example.  I live in Liberty Township, but my location through my computer will show up as being in the city of Mason which is ~5 miles aways from where I live.
      - Another consideration is when Virtual Private Network (VPN) clients are in use.  VPNs are used by companies and universities for network security.  VPNs will result in your computer being registered in a completely different location, sometimes in a different state. When I am connected to my companies VPN, my location will show up as being in Chicago, IL.
    - We discussed changes in the mobile ecosystem and how privacy concerns are resulting in protections for consumers, where there is more opting in versus opting out.
    - I used the McDonald's application as an example of creating perceived value for the consumer in exchange for their precise geolocation, and how the app continues to have access to this in the background.  I also suggested that the McDonald's app was a good example of gamification based on how it allows you to collect points and redeem points for food.
  - Containerization
    - Why is containerization important?
      - Containers allow us to get software to run reliably when moved from one computing environment to another.
      - Containers allow applications to be more rapidly deployed and scaled.  [Kubernetes](https://kubernetes.io) is an example of how you can scale out from a container.
    - In general, containerization is a tool that supports the agile methodology.
    - Containers are essentially "virtual machines", similar to [VirtualBox](https://www.virtualbox.org) or [Parallels Desktop](https://www.parallels.com/products/desktop/) if you are familiar with these.
    - We discussed that we will incorporate containerization through the use of Visual Studio Code Dev Containers only.
      - This means that I should be able to download your GitHub repository, open the folder in Visual Studio code, and have the same development environment that you have.
    - I attempted to give a demonstration on how to setup a dev container inside VS Code, this was poorly done (my ADD got the better part of me) and I apologize.
    - Resource to help you implement Visual Studio Code Dev Containers
      - [Dev Containers tutorial](https://code.visualstudio.com/docs/devcontainers/tutorial) must be completed by everyone.
      - [Developing Inside a Container](https://code.visualstudio.com/docs/devcontainers/containers) provides lower level information on the principles.  However, I stress that you do not need to understand this for the project, keep it simple!
      - I do not believe the TA's have experience with Dev Containers, so ask me if you need help.

</details>


<details>
  <summary>Tuesday, February 21, 2023</summary>

  - Slides for [lecture 13](https://loudinb.github.io/eece3093c/lecture_13.html) on online.
  - The final 4 teams presented their projects to the class.
    <details>
      <summary>list of teams to present</summary>
      
      - Team B
      - Team Voie
      - Team Weather
      - Team Wii Tanks
      
    </details>
  - Slide 4: Discussed and maped the [4-layer architecture](./software_engineering_4-layer_architecture.md) to elements of the team project.
      - **Focus on Quality**: Reliability, testing, maintainability, requirements managements.
      - **Process**: Agile development, or any software development life cycle.
      - **Methods**: For this course, OOP design principles will be core. Methods will be the major part of the remaining of the course.
      - **Tools**: This is our current focus.  GitHub projects, issues, source control, actions, etc.  Although the process is referred to as the "glue", in my practical experience, tools are tightly coupled to the process and seriously impede progress.
  - Slide 5: Reinforced that the agile methodology does not prescribe that the artifact of each iteration is a production version, just functional. We talked briefly about CI and CD.  CI refers to Continuous Integration and CD refers to Continuous Delivery, as well as Continuous Deployment.  As part of this course we will work toward operating some of the Continuous Integration principles, but not Continuous Delivery or Continuous Deployment.
  - Slide 6: Introduce Agile Unified Process, which is yet another agile methodology.  This is being used to illustrate that the teams are very much in the Inception phase, currently working through the Elaboration phase, and progressing rapidly (if not starting) the Construction phase.  This is only being introduced as the construct should resonate with the realities of this team based project.
  - Slide 7: Discussed immediate expectations, and reinforced that start this week your grade depends on adhering to the following:
      - product manager
      - Be managing the product development through a GitHub Project
      - Have a managed and maintained product backlog-
      - Have an iteration backlog the defines the development work for the iteration
      - Have a defined cadence for team check-in (weekly minimum)
      - Have an issue for every activity
          - Issues are written in a clear and concise manner, and are actionable
          - Issues are assigned to individuals
          - Issues are labeled
          - Issue comments contain all discussion
          - All commit messages reference an issue
      - Be using a separate repository for each product component
      - **Note**: Every artifact (code, document) in the GitHub repository must be linked to an issue.
  - Slide 8:
      - The team project grade will be weighted equally across 4 criteria: Focus on Quality, Process, Methods, and Tools.
      - The **individual** project grade will include an individual contribution factor in the range of [0.7, 1.0]
      - Reminded that the course grade is weighted 60% project, 40% assignments.  This change was due to putting more emphasis on the project, resulting in the removal of the final exam.
  
</details>

#### Week 6

<details>
  <summary>Thursday, February 16, 2023</summary>
  
  - Initial project review for 21 of 25 teams.
    <details>
      <summary>list of teams who presented</summary>
      
      - Team Orange
      - Team Big Boys
      - Team Blue
      - Team Cybertech
      - Team Du
      - Team Dylan
      - Team Go
      - Team Golden Girls
      - Team Green
      - Team Jam
      - Team Keith
      - Team Lua
      - Team Moncef
      - Team NonToastMakers
      - Team Python
      - Team Red
      - Team Rocket
      - Team Swift
      - Team Over-Under
      - Team Undefined
      - Team Under-the-C
    </details>
</details>

<details>
  <summary>Tuesday, February 14, 2023</summary>

  - Interactive session on using GitHub Project and GitHub Issues.
  - Discussed the relationship between repository, issues, and projects.
  - Briefly discussed the use of GitHub Actions for Windows CI/CD.
  - Announced that semester grading will change to 60% team project and 40% assignments.  The change is a result of moving from 3 team based lab assignments and a final exam to the semester team project. 
</details>
  
#### Week 5

<details>
  <summary>Thursday, February 9, 2023</summary>

  - [GitHub GUI Client](./github_gui_client.md)
  - [Branching Strategies](./branching_strategies.md)

</details>
