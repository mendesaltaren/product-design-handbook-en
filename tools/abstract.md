# Abstract

## Abstract

Our team works with Abstract because it allows us to have version control of the product and it allows us to simultaneously work with several people on the same Sketch file, our main work tool.

With Abstract we have managed to eliminate conflicting copies, duplicates, and mix-ups about which are the final archives. In addition, it has allowed us to include our clients in the workflow, allowing them to visualize the work that has been done and the status of the project.

{% hint style="info" %}
✏️ In order for clients to see the project, they must be invited to the project and be part of its group.
{% endhint %}

In this section, we will see how Abstract works and how we use it daily in our studio.

## 1. Introduction

The basic structure of Abstract is composed of a Master and Branches. Its way of working is based on commits and merged branches.

The commits represent the changes that have been made. A commit can be understood as a photo of a Sketch file at some point in time, allowing us to return to it whenever we want to. The set of commits form a log, which reflects all the changes made to the various Sketch files that comprise the project. This allows us to have full awareness of the work carried out, and that in the event of any unforeseen absence, the work can continue without any problem. Any member of the team could continue without any loss of information, knowledge, and work.

### 1.1 Master

The Master is the source of truth for our projects. Everything contained in the Master must be in place to validate the work with the client or upload the designs to Zeplin for production.

### 1.2 Branch

Each person who works on the project works on a different branch. Each branch belongs to a different person. All the main branches on which a new functionality or a concept is worked on must stem from the Master, as this is where the latest changes are reflected. And one branch can support others, so that several people can work on the same thing and then the work done can be combined without problems.

When creating a branch, an exact copy of the files of its parent branch is made, either the Master or the branch of another teammate. This allows us to avoid loss of information.

For us, examples of branches could be:

* Branding
* Visual exploration
* Search module
* Checkout flow
* Navbar alignment

Branches have a name and a description.

* The name must be descriptive of what you are going to work on.
* The description should supplement the name. For us, a good description is one that contains the requirements for a feature to be added or what the purpose of the feature is. Thus, when it has been completed he will be able to merge with his parent branch.

## 2. How do we work with Abstract?

In this section, we will explain how we use Abstract within the team, our methodology, our guidelines and procedures for each project. All of this has come about after months of working with the tool. And it's flexible enough to work differently for each team and project.

### 2.1 Commit

{% hint style="info" %}
✏️ A commit can be understood as an update to the Sketch's files at any given point in time so that it records all the changes that have been made up to that point.
{% endhint %}

**When do we create a commit?**

In the studio, we distinguish between three types of commits, representing three moments when a commit must be made.

* Each time a task is completed. This allows us to keep track of when it was carried out and what changes were made to complete it.
* In the concept branches, throughout the exploration phase, we commit each time there is a change of direction.
* At the end of the day. This is a must. Each person on the team should always commit before closing the computer and going home. This helps us in such a way that anyone can continue with the work, at the same point that was it left at the day before.

{% hint style="info" %}
✏️ The tasks coincide with the tasks outlined in [Asana](asana.md), which is where we show the roadmap and the tasks to be carried out in a project.
{% endhint %}

**How is a commit made?**

{% hint style="info" %}
✏️ To make a commit you will have to click on Preview and Commit in the bar at the bottom of Sketch. Selecting this option loads all the screens added or modified in Abstract in order to view the changes that have been made.
{% endhint %}

To complete the commit, you must include a name and a description of the commit. The name and description give us context for when we want to visualize previous commits. This clarity is especially useful when we want to go back to a specific point.

The name must be descriptive and the description must contain the changes that have been made. A good practice for naming a commit is:

* If the commit is made after a task has been completed, the name must match the \[**task name**\].
* f the commit is made at the end of the day, the name must follow the following structure:

  Proceed with \[**Task Name**\].

* If the commit is on an exploration branch, the name should describe the changes made.

For us, the description is a list of changes that have been made between commits. In order to ensure that this is clear and easy to understand by all the members of the team, we use the following terminology:

```text
✅ [Action] [Where the action took place]
```

An example would be:

```text
✅ Add [artboard]
✅ Add [symbol]
✅ Add [page]
✅ Change [module]
✅ Change [symbol]
✅ Delete [module]
✅ Delete [page]
✅ Change [Page]
```

### 2.2 Merge

When we merge, we're consolidating a Sketch's file. By merging, we collect all the artboards and pages we've been working on, including the changes made in the parent branch from which the branch was created. We create a merge when the objective for that particular branch is completed. For example, after completing a feature.

When we merge a branch, Abstract gives us the option to include details. This is important when you need to inform the team about changes in the branch, and we want this to be consistently practiced.

In some cases, the same artboard or symbol may be modified in different branches. When this happens, Abstract forces us to select which option we want to keep. It is important that this decision is made together with the team, and to finally communicate what the decision is.

### 2.3 Add comments

Abstract allows us to add comments about the different elements of a Sketch file. This helps both with internal communication and collaboration with the client and their team.

### 2.4 Create a new project in Abstract

Each project we work on in the studio is part of a different project on Abstract.

Abstract projects have an assigned name, description, and color.

* For the name, we maintain the name of the project we have in Dropbox. In this way, we are able to maintain consistency across the different tools we work with.
* The description must reflect the description of the project and its objectives to be achieved.
* The color serves as a visual identifier of the project, so it is best to make this the main color of the project.

### 2.5 Creating a new file in Abstract

To maintain the processes, we create Sketch's files directly in Abstract. Abstract, allows us to create Sketch files or Sketch libraries. The libraries we create in a project are automatically linked to all the files it contains.

The **naming** of our Sketch files follows the following format:

```text
[file id ] [file type] [Platform]
```

**An example would be:**

```text
01_Research
02_UX_Web
02_UI_Web
02_UI
02_UI_App_Android
02_Design-System
```

{% hint style="info" %}
✏️ To learn more about how our team is organized and how we name our files, please refer to our section on [**1. How we organize ourselves.**](../organization.md)\*\*\*\*
{% endhint %}

