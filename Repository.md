### Repository:

- **What is repository?**
	- A repository is usually used to organize a single project.
	- Repositories can contain folders and files, images, videos, spreadsheets, and data sets -- anything your project needs.Often, repositories include a README file, a file with information about your project. README files are written in the plain text Markdown language


### Create Repository

- **Template:** A repository template is a predefined structure or layout that serves as a starting point for new repositories, streamlining the creation process by providing common files, folders, and configurations.When using a repository template, the following elements are commonly included:	
	1. **Default file and directory structure:** Provides a basic organization for project files.
	2. **Configuration files:** Includes settings for tools, such as CI/CD pipelines or linters.
	3. **README and CONTRIBUTING files:** Offers guidance on how to use and contribute to the project.
	4. **License file:** Specifies the terms under which the project is distributed.
	5. **Code snippets or examples:** Offers reusable code snippets or example files.
	6. **Documentation:** Provides initial documentation to help users understand the project.

- **Repo visibility:** Repository visibility determines who can access and view a repository.
		1. Public  : Accessible to everyone, suitable for open-source projects.
		2. Internal: Visible within the organization, maintaining privacy from external users.
		3: Private : Restricts access to users with explicit permission, ideal for proprietary projects.
  		Note: org admin and enterprise admin can see the repo 


- **Readme file:** A README file is a straightforward document that explains key details about a project.

- **gitignore:** A .gitignore file specifies intentionally untracked files that Git should ignore, such as build artifacts or temporary files, to keep the repository clean.


## Repository

    1. Code         : Stores project files and source code.
    2. Issues       : Tracks bugs, feature requests, and tasks.
    3. Pull Requests: Manages proposed changes and code reviews.
    4. Actions      : Automates workflows and tasks.
    5. Projects     : Organizes tasks, issues, and pull requests.
    6. Wiki         : Provides collaborative documentation.
    7. Security     : Manages security alerts and settings.
    8. Insights     : Offers analytics and repository statistics.
    9. Settings     : Configures repository options and permissions.
    10.Discussion   : Platform for conversations, questions, and feedback related to the repository.



### Repositorie Role:
1. **Read**     : Read and clone repositories. Open and comment on issues and pull requests.
2. **Triage**	: Read permissions plus manage issues and pull requests.
3. **Write**	: Triage permissions plus read, clone and push to repositories.
4. **Maintain** : Write permissions plus manage issues, pull requests and some repository settings.
5. **Admin**	: Full access to repositories including sensitive and destructive actions.


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
			- Security: View code scanning alerts, Dismiss or reopen code scanning alerts, Delete code scanning analyses, View secret scanning alerts, Dismiss or reopen secret scanning alerts, View


### Pull Requests: ###
 - Pull requests let you tell others about changes you've pushed to a branch in a repository on GitHub.
 - Once a pull request is opened, you can discuss and review the potential changes with collaborators and add follow-up commits before your changes are merged into the base branch.
 - Merge a pull request into the upstream branch when work is completed.
 - Three types of pull requests:
   
		1. Create a Merge commit :Merging changes from a feature branch into the main branch after PR approval.
		2. Squash and merge	  :Combining all commits from a feature branch into a single commit before merging.
		3. Rebase and merge	  :Rewriting commit history by applying changes onto the tip of the target branch.

### Commits ###

- Like saving a file, a commit is a change to one or more files in your branch. Git assigns each commit a unique ID, called a SHA or hash, that tracks:
 
	1. The specific changes
	2. When the changes were made
	3. Who created the changes

### Branch

- Use a branch to isolate development work without affecting other branches in the repository.You can use branches to:
  
	1. Develop features
	2. Fix bugs
	3. Safely experiment with new ideas

### Tags/Releases

- You can create a release to package software, along with release notes and links to binary files, for other people to use.
- Releases are deployable software iterations you can package and make available for a wider audience to download and use.

### Gist
- Gists provide a simple way to share code snippets with others.
- Every gist is a Git repository, which means that it can be forked and cloned.
- Gists can be public or secret.

### GitHub Package
- GitHub Pages is a static site hosting service that takes HTML, CSS, and JavaScript files straight from a repository on GitHub, optionally runs the files through a build process, and publishes a website.
- GitHub Pages is available in public repositories with GitHub Free and GitHub Free for organizations.
- public and private repositories with GitHub Pro, GitHub Team, GitHub Enterprise Cloud, and GitHub Enterprise Server.

### GitHub Action
- GitHub Actions is a continuous integration and continuous delivery (CI/CD) platform that allows you to automate your build, test, and deployment pipeline.
- You can create workflows that build and test every pull request to your repository, or deploy merged pull requests to production.
- You can configure a GitHub Actions workflow to be triggered when an event occurs in your repository, such as a pull request being opened or an issue being created. Your workflow contains one or more jobs which can run in sequential order or in parallel. Each job will run inside its own virtual machine runner, or inside a container, and has one or more steps that either run a script that you define or run an action, which is a reusable extension that can simplify your workflow.
- Key syntax elements used in GitHub Actions:
	- Name: The name field is used to provide a descriptive name for the workflow. It helps identify the workflow in the Actions tab on GitHub.
	- on: The on field specifies the events that trigger the workflow. You can define events such as push, pull_request, schedule, or a custom event.
	- jobs: The jobs field represents the list of jobs that should be executed when the workflow runs. A workflow can have one or more jobs.
	- runs-on: The runs-on field specifies the type of runner environment in which the job will be executed. GitHub Actions supports various operating systems and virtual environments.
	- steps: The steps field contains a list of actions that are executed in sequence within a job. Each step typically represents a specific task or action to be performed.
	- name: The name field provides a descriptive name for each step. It helps identify the step in the workflow log.
	- uses: The uses field specifies the action or the composite run steps action that should be executed. It can reference an action from the GitHub Marketplace or a local action defined in your repository.
	- env: The env field allows you to define environment variables that can be accessed within the job. These variables can store dynamic values or sensitive information.
	- run: The run field contains the shell commands or scripts that are executed as part of the step. You can use multiple lines or a single-line command.
	- if: The if field enables conditional execution of a step or job based on an expression. The expression can reference context information such as event data, job status, or environment variables.
	- with: The with field allows you to specify additional inputs or parameters for an action or a step. These inputs can be static values or references to context information.
	- continue-on-error: The continue-on-error field indicates whether the workflow should continue running or stop if a step fails. By default, the workflow stops on the first step failure.
<img width="522" alt="action components" src="https://github.com/user-attachments/assets/7dfcfe70-9d47-48c6-a414-3678c3897df6">


### GitHub Copilot

- GitHub Copilot is an AI coding assistant that helps you write code faster and with less effort, allowing you to focus more energy on problem solving and collaboration.
- GitHub Copilot includes a suite of features. You can use Copilot to:
	- Get code suggestions as you type in your IDE
	- Chat with Copilot to ask for help with your code
	- Ask Copilot for help using the command line
	- Generate a description of the changes in a pull request (Copilot Enterprise only)
	- Create and manage collections of documentation, called knowledge bases, to use as a context for chatting with Copilot (Copilot Enterprise only)
  	



