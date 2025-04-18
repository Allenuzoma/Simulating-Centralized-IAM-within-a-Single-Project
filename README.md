# Simulating-Centralized-IAM-within-a-Single-Project
To simulate a basic centralized access control strategy within a single Google Cloud Project using Google Groups to manage read-only access to different sets of resources (simulating different environments or teams).
First I will create a new project titled : Simulating-Centralized-IAM
Next I'll check the inherent permissions on the project. We can see the owner permission assigned to my account identified as principal - This means that I have all the permissions required

Go to IAM & Admin > Groups: In the navigation menu, go to IAM & Admin and select Groups.
**Create Cloud IAM Groups:**

Click + CREATE GROUP.
Enter a "Group ID" (e.g., team-a-readonly). This will be the unique identifier for the group within your project.
Enter a "Group name" (e.g., Team A Read-Only Access).
