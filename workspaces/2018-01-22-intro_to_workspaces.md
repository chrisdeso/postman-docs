---
categories:
  - "postman"
  - "intro_to_workspaces"
title: "Intro to Workspaces"
page_id: "intro_to_workspaces"
warning: false
---

### What is Workspaces?

A Workspace is an environment where you can perform all your API tasks. 

A Workspace is a view, and not a physical container. As a result, a collection can exist in different workspaces at the same time.

### Why use Workspaces?

Let's say you are a Postman Pro subscriber using the Team Library to work on your own collections, while collaborating with several others. At the team level, there might be different projects that a team might be working in parallel. 

If a person is on Postman Pro using the Team Library they might be working on their own collections while also collaborating with several others. At the team level, there might be different projects that a team might be working in parallel. One goal that we established upfront was that every team member should have visibility into the team's API infrastructure. Otherwise, it would lead to a situation more like Google Drive where one doesn't know where something is and has to rely on links stored somewhere. While this is helpful, it can be confusing for companies with several teams. The teams might have internal APIs and external APIs for other teams.
To solve these issues, we need a new abstraction - called Workspaces.
 
### Types of Workspaces

Postman offers two types of Workspaces: personal and team. 

* Personal: Individual users can create workspaces that are only visible to them.

* Team: Workspaces shared between all members of a team. All workspaces that a user has visibility into should be accessible from the Postman app and the web