# Repository Rules 

1. Enforce Workflows
- Because org-wide rulesets require status-check contexts:

  - every organization repository targeted by `main-branch.json` must run GitFlow reusable workflow;

  - every repository with `project_type=ios` must also run the iOS validation reusable workflow.

2. Enforce iOS Repository Property
- every iOS repository must be assigned `project_type=ios` otherwise `ios-project.json` targets nothing. 

3. Enforce Liner History in Ever Repository 
- each repository must have squash and/or rebase merging enabled in its repository settings. GitHub requires the repository to permit squash or rebase merging before linear-history enforcement can function usefully.
