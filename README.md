# stamp-canary

Test repository for Stamp's post-release smoke check (QA). Every Stamp release on staging and production runs one pass here:
an agent pushes a branch, opens a pull request, approves it with review evidence and merges it; two more go through the merge queue
with a deliberate conflict. Contents are test data only and change all the time. Owner of the check: InNOut (#proj-stamp task #88).
