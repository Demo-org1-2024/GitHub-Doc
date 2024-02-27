# GitHub


## SDLC stands for Software Development Life Cycle. 

It is a process used by software development teams to design, develop, and test high-quality software. 


SDLC process consists of seven phases:
### 1. Requirement Gatherings: 
	- In this initial phase, the development team interacts to understand the needs and gather requirements,
	- tools: Microsoft Project, JIRA , trello
		-  JIRA:  For tracking requirements, issues, and tasks.
		-  Trello:  For organizing and prioritizing requirements in a Kanban board format.
		-  Microsoft Project:  A project management software that helps in creating project plans, assigning resources, and tracking progress.
		-  Asana 
### 2. System Analysis: 
	-This phase involves analysing the gathered requirement with the system’s overall architecture, components, and data flow.
	-Understand and document the requirements and goals of the project.
	   	-  Confluence:  For documenting requirements and collaborating on them.
		-  Track and Rally 
		-  Click Up 
### 3. Design: 
	- The team designs the software based on analysis and needs.
	- Create a plan for how the software will be built, including its architecture and user interface.
	   	-  Lucidchart:  For creating system architecture diagrams and visualizing system flows.
		-  Draw.io:  Similar to Lucidchart, it's a diagramming tool for system analysis and design.
		-  Adobe XD:  For designing user interfaces and prototypes.
		-  Sketch:  Another UI/UX design tool commonly used for designing interfaces.
		-  Sigma: 
### 4. Implementation: 
	- Also known as the coding phase, in which the software development takes place.
	- Write the actual code and develop the software according to the design specifications.
	   	-  Git:  For version control and managing code repositories.
		-  GitHub/GitLab/Bitbucket:  Platforms for hosting Git repositories and collaborating on code.
		-  Jenkins:  For continuous integration and automating the build process.
### 5. Testing: 
	* Software is tested to identify faults and bugs and to ensure the proper functioning of the software.
	* Verify that the software works correctly and meets the requirements through various testing processes.
		- Selenium: For automated web application testing.
		- JUnit: For unit testing Java applications.
		- Postman: For testing APIs and services.
		- Sonar cube:
		- JMeter: For performance testing and load testing.
### 6. Deployment: 
	- Once tested, the software is deployed to the end-user
	- Release the software to users and make it available for use, along with any necessary training and support.
		--> Docker: For containerization and packaging applications into containers.
		--> Kubernetes: For container orchestration and managing containerized applications.
		--> Ansible: For automating deployment tasks and configuration management.
		--> Terraform: For infrastructure as code, automating the provisioning of infrastructure.
### 7. Maintenance: 
	After deployment, the software enters the maintenance phase. It includes monitoring software, fixing bugs and making updates if required.
	--> Nagios: For monitoring system performance and alerting on issues.
	--> Prometheus: For monitoring and alerting on metrics.
	--> Dynatrace: For ongoing monitoring and analysis of system performance and health.





## Distributed version control systems (DVCS) :
	It enable users to work with complete repository copies, promoting decentralized collaboration, flexible branching, merging, and offline access, exemplified by Git, Mercurial

## Centralized version control systems (CVCS):
 It rely on a central repository for version management, where users check out files for modification and commit changes back to the central server, exemplified by systems like CVS and Subversion (SVN).

## Github Fundamentals
	- GitHub Adminstration
	- GitHub Action
	- GitHub Advance Security
	- copoilt



## GitHub Feature:
	1. Source code Management
	2. Project  Management
	3. Wiki
	4. Discusion
	5. Code Owners
	6. Branch Rule Protection
	7. Rule sets
	8. CodeSpace
	9. GitHub action
	10. Advance security
	11. Copilot



## GitHub Plan
	1. Free
	2. Teams
	3. Enterprise


## GitHub Hirechy
	1. Enterprise
	2. Oraganziation 
	3. Repository


### Repository:

**What is repository?**
	- A repository is usually used to organize a single project.
	- Repositories can contain folders and files, images, videos, spreadsheets, and data sets -- anything your project needs.Often, repositories include a README file, a file with information about your project. README files are written in the plain text Markdown language


**create repository**

	- Template: A repository template is a predefined structure or layout that serves as a starting point for new repositories, streamlining the creation process by providing common files, folders, and configurations.When using a repository template, the following elements are commonly included:	
		1. Default file and directory structure: Provides a basic organization for project files.
		2. Configuration files: Includes settings for tools, such as CI/CD pipelines or linters.
		3. README and CONTRIBUTING files: Offers guidance on how to use and contribute to the project.
		4. License file: Specifies the terms under which the project is distributed.
		5. Code snippets or examples: Offers reusable code snippets or example files.
		6. Documentation: Provides initial documentation to help users understand the project.

	- Repo visibility: Repository visibility determines who can access and view a repository.
		1. Public  : Accessible to everyone, suitable for open-source projects.
		2. Internal: Visible within the organization, maintaining privacy from external users.
		3: Private : Restricts access to users with explicit permission, ideal for proprietary projects.
  		Note: org admin and enterprise admin can see the repo 


	- Readme file: A README file is a straightforward document that explains key details about a project.

	- gitignore: A .gitignore file specifies intentionally untracked files that Git should ignore, such as build artifacts or temporary files, to keep the repository clean.


## Repository
	1. Code       	    : Stores project files and source code.
	2. Issues  	    : Tracks bugs, feature requests, and tasks.
	3. Pull Requests    : Manages proposed changes and code reviews.
	4. **Actions**      : Automates workflows and tasks.
	5. **Projects**     : Organizes tasks, issues, and pull requests.
	6. **Wiki**         : Provides collaborative documentation.
	7. **Security**     : Manages security alerts and settings.
	8. **Insights**     : Offers analytics and repository statistics.
	9. **Settings**     : Configures repository options and permissions.
	10. **Discussion**   : Platform for conversations, questions, and feedback related to the repository.



## Repositorie Role:

	**1. Read**     : Read and clone repositories. Open and comment on issues and pull requests.
	**2. Triage**	: Read permissions plus manage issues and pull requests.
	**3. Write**	: Triage permissions plus read, clone and push to repositories.
	**4. Maintain** : Write permissions plus manage issues, pull requests and some repository settings.
	**5. Admin**	: Full access to repositories including sensitive and destructive actions.


	1. Read    :  Read and clone repositories. Open and comment on issues and pull requests.
	2. Triage  : Read permissions plus manage issues and pull requests.
			- Issue and Pull Request :  Assign or remove a user,  Remove an assigned user, Remove a label, Add or remove a label, 
			- Issue                  :  Close an issue, Reopen a closed issue, Mark an issue as a duplicate, Set an issue type
			- Pull Request           :  Close a pull request, Reopen a closed pull request, Request a pull request review
			- Repository             : Set milestones.
			- Discusion              :  Manage discussions.
	3. Write	: Triage permissions plus read, clone, and push to repositories.
			- Issue and Pull Request : Same as Triage.
			- Repository             : same as Triage
			- Secuirity              : View code scanning alerts, Dismiss or reopen code scanning alerts, View Dependabot alerts, Dismiss or reopen Dependabot alerts
			- Discusion              :  Manage discussions.
	4.  Maintain: Write permissions plus manage issues, pull requests, and some repository settings.
			- issue and Pull Request : Same as Write
			- Repository             : Manage pull request merging settings, Manage GitHub Page settings, Manage project settings, Manage wiki settings, Manage topics, Push commits to protected branches, Set interaction limits, Set milestones, Set the social preview, Edit repository metadata, Create a protected tag, Edit repository announcement banners
			- Secuirity              : Same as Write
			- Discusion             :  Manage discussions.
	  
	5. Admin   : Full access to repositories including sensitive and destructive actions.
			- Issue and Pull Request : Same as Maintain.
			- Issue                  : Close an issue, Reopen a closed issue, Delete an issue,  Mark an issue as a duplicate, Set an issue type
			- Merge Queue            : Jump to the front of the queue, Request a solo merge
			- Repository             : Manage pull request merging settings,Manage GitHub Page settings,Manage project settings,Manage wiki settings,Manage topics,Push commits to protected branches,Set interaction limits,Set milestones,Set the social preview,Edit repository metadata,Manage deploy keys, Manage webhooks, Create a protected tag,Delete a protected tag, Bypass branch protections, Edit repository rules,Edit repository, announcement banners, Edit values of custom properties that allow it.
			- Security: View code scanning alerts, Dismiss or reopen code scanning alerts, Delete code scanning analyses, View secret scanning alerts, Dismiss or reopen secret scanning alerts, View Dependabot alerts, Dismiss or reopen Dependabot alerts
			- Discusion             :  Manage discussions.
