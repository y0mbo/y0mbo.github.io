---
layout: post
title: User Stories Versus Job Stories
---

Kent Beck originally suggested the idea of [User Stories](http://wiki.c2.com/?UserStoryAndUseCaseComparison) to help define requirements with a politically neutral balance between the business folks and developers.

> "Use cases as I have seen them used are complex and formal enough that business doesn't want to touch them. This leads to development asking all the questions and writing down all the answers and taking responsibility for the resulting corpus. Business is reduced to sitting on the other side of the table and pointing."

According to Kent, the goal was to imagine an artifact simple enough for non-technical teams to create and own. They would feel comfortable adding new requirements and appropriately prioritizing them.

Dan North suggested the standard [User Story Template](http://wiki.c2.com/?UserStoryTemplate) we use to express user stories:

```
As a [persona]
I want [action]
So that [outcome]
```

In my experience, the User Story format is easy enough to workshop and gain valuable information from business stakeholders. Unfortunately, the User Story doesn't go deep enough for the engineering team to work with after the initial meeting.

Alan Klemet suggests [Replacing the User Story with the Job Story](https://jtbd.info/replacing-the-user-story-with-the-job-story-af7cdee10c27). A Job Story is something he coined, and its format intends to fix some problems with the traditional User Story.

```
  When [event]
  I want to [motivation]
  So I can [outcome]
```

The persona gets dropped in the Job Story format since it provides little value to the story as a whole. If a role helps define the story better, incorporating it into the "when" is simple enough.

The second line of the Job Story provides the motivation of the user and is the crucial missing factor of the User Story format. Understanding why helps the development team build a better solution because it focuses on that motivation rather than an implementation.
