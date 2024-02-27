 # GitHub Workflow Demo
This repository serves as a demonstration for a basic GitHub Workflow. The workflow is designed to be automatically triggered on every push event to the main branch. Initially, the workflow generates a simple greeting with the message "Hello, CI Workflow!" As a further enhancement, an additional step has been added to the workflow, printing the welcoming message "Welcome to CI Workflow!"

## Task Steps
1. Repository Setup
Create a new GitHub repository for your application.
2. GitHub Actions Workflow Configuration
Navigate to the "Actions" tab within your GitHub repository.
Click on "Set up a workflow yourself" and add a workflow YAML that triggers automatically on every push to the main branch.
Include the provided YAML code for the initial simple workflow.
3. Test the Workflow (First Step)
Make a minor change to the repository (e.g., add a comment).
Commit and push the changes.
Verify in the "Actions" tab that the workflow has been automatically initiated, displaying the output "Hello, CI Workflow!"
4. Add an Extra Step
Extend the workflow by including another step that prints an additional welcome message.
5. Test the Workflow (Second Step)
Make another small change to the repository.
Commit and push the changes.
Verify in the "Actions" tab that the workflow has been automatically initiated, showcasing both outputs: "Hello, CI Workflow!" and "Welcome to CI Workflow!"
By following these steps, your repository will be configured with a straightforward GitHub Workflow, executing specified actions with each push to the main branch.
