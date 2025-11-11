---
name: "Optimized git workflow through GitHub Actions"
date: "2025-11-10"
icon: ""
public: true
categories:
  - "github"
  - "eng"
---

**S:** Our team had to manually perform an update of the staging environment after a merge to the main branch, which was sometimes forgotten and caused great trouble, impeding our development process and delaying deliveries.
**T:** I needed to find a way to automate that update process in a way that was reliable.
**A:** So I took the front and implemented a workflow in GitHub Actions that would perform the commands every time a PR was merged to the main branch.
**R:** I completely eliminated the need for a manual update of the staging environment, which allowed us to deliver faster and with less stress.

