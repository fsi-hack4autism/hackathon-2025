# 2025 Financial Services Autism Hackathon - Main Site

The main repository for the 2025 hackathon with all the information for the hackathon and pointers to all repositories. Hackathon informaton pertaining to 2025 specifically will remain in here. The individual repositories are made to span multiple years. This years hackathon will continue to focus on ensuring the growth for each use case. This means the repositories created this year will be use again in subsequent years provided these use cases are repeated again. We need to ensure these solutions will lead to real world outcomes.

## Mission Statement
Bring developers from the Financial Services industry together to demonstrate how innovative Microsoft technologies can transform autism services by tackling real world use cases provided by families and creating lasting open-source projects for the community.

![image](https://user-images.githubusercontent.com/4500512/212386856-50328c9e-3699-4aec-8c68-6d889e043c05.png)

## Dates and Location
The date of the event is April 2nd and 3rd. The event will be hybrid. The in-person venue will be in NYC at 'TBD' during World Autism Awareness Month (April).

## Use cases

### Use case 1: Therapy Delivery CoPilot Reinvention
#### Objective: Assist the RBT and BCBA during a session with the child

The biggest impact in helping those with profound autism comes from direct intervention therapy, which can be up to 30 hours a week. However, persistent issues of quality, transparency, consistency, and access remain unsolved.  

This is a reinvention of the therapeutic environment, harnessing the latest AI and cognitive technology to empower teams to perform their core tasks with unprecedented support. This approach addresses all aspects of direct intervention through the creation of a Digital Command Center. This center captures data in a multi-sensory manner, allowing teams to understand session dynamics, providing therapists with real-time support, and freeing them from distractions to focus on the child or young adult.

This will incrase the quality of service and allow better support, particularly in those areas starved of services.

#### Scenario
The session will comprise of:
* Multi-modal data capture
  * A smartphone app used by RBT - similar to what some RBTs have today
  * Video camera to record the session - this will focus on capturing facial expressions, body language, fluency of tasks, etc.
  * Microphone - this will focus on capturing voice, tone, etc. to determine emotions
* Real-time identification of pre-designed triggers
  * This module will specifically look for pre-designed triggers - emotional (frustration, accomplishment, etc.), or physical (completion of task, eye contact, etc.)
  * The objective is to track progress along specific markers
* Post-session summarization
  * Summarize and generate notes - free form based on observations across all modes
  * Summarize progress on specific markers
#### Code repository
https://github.com/fsi-hack4autism/therapy-session-copilot
#### Stakeholders
* RBT, BCBA, parent, child
#### Leadership team
| Name | Role | Company |
|------|------|---------|
|Rishi Bhatnagar|Use Case Lead|Morgan Stanley|
|Amy Backes|Subject Matter Expert|RBT/BCBA|
|Rob Reese|Tech Lead|Microsoft|
||Tech Lead|Accenture|
##### Ideas
[Project Florence -Vision Studio for Video/Image Analysis](https://portal.vision.cognitive.azure.com/gallery/featured)
#### Time to Market: 12-18 months

### Use case 2: Program development design co-pilot
#### Objective: Assist the BCBA design a program specifically tailored for each child
There is significant variation in the quality of program designs, as overworked and underpaid analysts try to support a backlog of clients. This can negatively impact the quality of the programs being designed, which, in turn, affects the child or young adult and can ultimately hinder their future independence.  

Copilot assists the Board Certified Behavior Analyst (BCBA) in designing customized programs specifically tailored for each child. By integrating advanced AI and cognitive technology, Copilot helps create individualized treatment plans centered around activities that the child enjoys and responds to positively. Over the course of a lifetime, utilizing Copilot should change the trajectory of an individual's outcomes, providing a higher quality of care and support.

#### Scenario
* The co-pilot will be able to ingest past program summaries in multi-modal form - videos, notes (digitized and undigitized), voide recordings, etc
* Based on these, the co-pilot will place the child in a cohort of other children with similar assessments and markers
* Based on past successes of children in the cohort, the co-pilot will suggest a recalibrated treatment and markers (if needed) to the BCBA
* It can generate a progress summary at any given point of time
#### Code Repository
https://github.com/fsi-hack4autism/program-development-copilot
#### Stakeholders
* RBT, BCBA, parent, child
#### Leadership team
| Name | Role | Company |
|------|------|---------|
||Subject Matter Expert|BCBA|
| Devanshi Thakar |Tech Lead|Microsoft|
| Guilherme Nogueira |Tech Lead|Microsoft|
||Tech Lead|Accenture|
#### Time to Market: 12-18 months

### Use case 3: Patient on-boarding co-pilot
#### Objective: Help BCBA onboard a new patient quickly

Service providers and clinics face significant challenges when onboarding new clients. They must process a tremendous amount of information to gain a clear understanding before developing a plan. This process is not covered by insurance, leading to increased costs and creating barriers for new entrants in the marketplace, ultimately impacting service availability and quality.

This copilot will assist service providers and clinics by streamlining the onboarding process for new clients. By leveraging advanced AI and cognitive technology, Copilot can quickly summarize the repository of information about a client, allowing providers to understand the case in minutes. This enables them to develop a plan and approach more efficiently. The low barrier to entry for this solution ensures it has a broad impact across the entire ecosystem, particularly benefiting underserved areas. This transformative initiative lowers the barrier to entry, enhancing service availability and quality across the board.

#### Scenario

Typically, a BCBA gets limited amount of time to onboard a new patient and this can be a very cumbersome task. It includes several types of information to intake:
* Patient demographics, medical history, past services, etc.
* Historical evaluations, IEPs, etc.
* Insurance, funding, billing information, etc.
* Previous and current treatments and their outcomes, progress reports, etc.
* Consent forms, contracts, letter of engagement, etc.

* The co-pilot will be able to ingest historical documents
* It will allow parents, BCBAs, and RBTs to actively collaborate across sessions - such as allowing parents to provide inputs of progress outside of sessions
* It will allow tracking documents and provide a platform for storing consents, authorizations, etc.
* It can generate a summarization of the new patient for the BCBA to review
#### Code Repository
https://github.com/fsi-hack4autism/patient-onboarding-copilot
#### Stakeholders
* BCBA, parent, child
#### Leadership team
| Name | Role | Company |
|------|------|---------|
|Leo Junquera|Subject Matter Expert|Parent|
|Melody Yin | Cloud Solution Architect Lead|Microsoft|
|Barry Cordie | Cloud Solution Architect Lead|Microsoft|
||Tech Lead|Accenture|
#### Time to Market: 12-18 months

### Use case 4: Friendly neighborhood Mobile Networking App
#### Objective: Connect parents of children with ASD with helpful resources in the community - other parents, BCBAs, organizations, etc.

Stephen Shore said, "If you've met one person with autism, you've met one person with autism," to articulate the diversity of needs and capabilities. This diversity makes identifying appropriate services a very difficult task for parents and guardians, particularly when moving to new areas or during life changes and transitions. Searching for services tailored to a specific set of needs is challenging, and a simple list of services, though helpful, is not enough. It's not like looking for a good restaurant; it can be critical services, like ABA (Applied Behavior Analysis) providers, that are essential.

This app connects the unique needs of each individual case with the available services using AI to help make the right match. By leveraging advanced AI and cognitive technology, the app enables caregivers to find the critical services they desperately need, ensuring that each child or young adult receives the tailored support they require. This transformative solution lowers the barrier to entry, enhances service availability, and improves overall service quality, particularly benefiting underserved areas.

#### Scenario
This mobile app will help connect parents and patients with other helpful members of the community - other parents, BCBAs, organizations, etc. It will work in three main phases
* Intake
  * Allow patients and parents to fill in their and thier child's profile
  * Offer a helpful "onbording survey" that will gather basic information about their child
* Discover
  * Use ChatGPT to allow parents and patients ask open ended questions and have a conversation
  * Prompt the right next actions for the parents 
  * Provide helpful information from credible sources
* Connect
  * Connect them with other parents in same situation
  * Connect them with credible resources and organizations that offer help in the specific area they are looking for
#### Code Repository
https://github.com/fsi-hack4autism/friendly-neighborhood
#### Stakeholders
* RBT, BCBA, parent, child, non-profit organization
#### Leadership team
| Name | Role | Company |
|------|------|---------|
|Crystal Hargrove|Use Case Lead|WTW|
|TBD | Cloud Solution Architect Lead|Microsoft|
|Dhruv Bhatnagar|Tech Lead|Student|
#### Time to Market: 12-18 months

### Theme 2: Ideas that are leverage innovative and exploratory technology and have a longer time to market

### Use case 5: Job skill training using Augmented Reality
#### Objective: Teach basic job skills to people with autism using Augmented Reality
This use case will focus on the use of Augmented Reality for teaching job skills to people with Autism, particularly those aging out of the supports provided in the school environment. Unemployment for those with Autism is significant and the supports in the work environment are limited. The use case will use Unity engine to build Augmented Reality solutions that can be used on platforms like HoloLens to help with basic job skills by presenting visual cues on how to complete task such as stocking shelves or preparing food. 
Additonally, the use case will make use of Gen AI, to manage, evaluate, and provide feedback to the student on how well the skill is being performed. It can also be used to generated the slight variants and increasingly complex scenarios to practice and introduce gamification.
This will also address the issue of scaability - moving away from 1:1 support to a 1:N as an a student becomes an adult.
#### Scenario
The skills th application will focus on can include one or more of the following:
* **Stacking shelves in a store** – e.g., making sure all the labels are facing outwards, etc.
* **Setting up a table in a restaurant** – making sure all the cutlery is there an arranged properly
* **Setting up a catering tray** – e.g., making sure all items are placed properly
#### Code repository
https://github.com/fsi-hack4autism/augmented-reality-skills-training
#### Leadership team
| Name | Role | Company |
|------|------|---------|
| TBD | Cloud Solution Architect Lead|Microsoft|
||Subject Matter Expert|BCBA|
| |Tech Lead|Microsoft|
||Tech Lead|Accenture|

### Use Case 6: Metaverse using Virtual Reality
#### Objective: Practice handling a variety of social situations through gamification
The world is filled with challenging social situations.  People facing new situations often struggle to find appropriate responses.  For those on the autism spectrum, this is exacerbated by difficulty reading standard social cues.  Having a safe and controlled environment to practice responding to common social situations, personality types, and social cues would allow users to face new situations with confidence.  Since creating such an environment would be difficult to scale, this app applies virtual reality to provide a unique social practice environment in an application.  Furthermore, since those with autism are often drawn to repetition, the app utilizes generative AI to ensure adequate variety across sessions.  Generative AI will also be used to evaluate the user’s performance.
#### Scenario
This virtual reality app will present users with a variety of interactive stories that include common social situations and personality types.  Users progress through the story by meeting a variety of characters with the goal of successfully completing the story.  Each story consists of the following components:
* **Story board** – Configuration of the story space and VR coordinates.  This section is designed in conjunction with VR designers.
* **Characters** – Configuration of the main characters and their general personality types.  The personality types are fed as prompts to generative AI to script the characters’ initial comments and subsequent responses to the user.
* **Scoring** – Analysis of the user’s handling of the situation is performed by feeding the entire conversation to generative AI for analysis of the user’s reactions.  Advancement in the game is based on the score.
#### Code repository
https://github.com/fsi-hack4autism/Metaverse-Social-Practice
#### Leadership team
| Name | Role | Company |
|------|------|---------|
|Stephen Goldbaum|Use Case Lead|Morgan Stanley|
|Caroline Matthews| Cloud Solution Architect Lead|Microsoft|
|Cynthia Sabbagh| Customer Success Account Manager| Microsoft|
|Allison Junquera|Subject Matter Expert|BCBA|
||Tech Lead|Accenture|


## Planning Team Roles
We often get asked "how can I participate" and have therefore outlined a list of roles and their responsiblities.

### Training Lead:
Curate resources and organize sessions in order to equip participants with the knowledge needed to prepare for the hackathon.
- Build technical training guide with learning geared towards each use case
- Put together contextual training guide focused on autism -  current state, challenges, and gaps
- Organize and distribute training schedule, including “ask me anything” and technical/contextual skilling sessions


### Use Case Manager:
Serve as the administrator of a use case. Ensure that both the tech leads and participants have what they need before and during the hackathon. 
- Support planning efforts and help in aligning 2-3 tech leads to use case
- Organize prep sessions leading up to the hackathon and ensure participants are connected with tech leads
- Oversee activity and logistics during the two-day hackathon
- Work with Tech Lead to capture summary/results


### Use Case Tech Lead:
Serve as technical point of contact for a use case, reviewing output from previous years and helping to unblock technical barriers against use case objectives. 
- Provide recommendations and help to finalize use case 
- Lead prep sessions for participants and be available for technical questions
- Manage sponsored subscriptions and set up for participants
- Lead and guide team(s) during the two-day hackathon
- Work with Use Case Lead to capture summary/results


### Marketing Lead:
Organize marketing material for the Hackathon and generate interest internally and externally. 
- Build a folder of references including: 
  - Word and PowerPoint branded templates
  - Brochure to be distributed to interested external organizations
  - One-pager highlighting the event


### Manager of Operations:
Ensure that everything is running smoothly across technical planning details of the Hackathon. 
- Partner with individuals building registration platform to oversee and manage registration, maintaining organized list
- Point of contact to navigate any external access issues
- Create Team that includes organize training content, use case details, and channels and assist with adding/managing members
- Responsible for day-of operations, overseeing schedule and making sure everyone knows where they are supposed to be


### Customer Engagement Lead:
Serve as the point person for a given customer organization, ensuring they have what they need to prepare their developers for the hackathon. 
- Identify customer “champion” lead who will be your primary liaison for the hackathon
- Work with Marketing Lead and Training Leads to get content and resources to share with your customer
- Keep your customer informed on a regular basis on registration timelines, training sessions, and other event logistics
