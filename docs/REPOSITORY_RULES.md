# Repository Rules 

1. Enforce iOS Repository Property
- every iOS repository must be assigned `project_type=ios` otherwise `ios-project.json` targets nothing. 

2. Enforce Liner History in Ever Repository 
- each repository must have squash and/or rebase merging enabled in its repository settings. GitHub requires the repository to permit squash or rebase merging before linear-history enforcement can function usefully.
