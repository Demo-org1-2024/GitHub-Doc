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
	Three types of pull requests:
		1. Create a Merge commit :Merging changes from a feature branch into the main branch after PR approval.
		2. Squash and merge	  :Combining all commits from a feature branch into a single commit before merging.
		3. Rebase and merge	  :Rewriting commit history by applying changes onto the tip of the target branch.

### Commits ###

	Like saving a file, a commit is a change to one or more files in your branch. Git assigns each commit a unique ID, called a SHA or hash, that tracks:
	1. The specific changes
	2. When the changes were made
	3. Who created the changes



