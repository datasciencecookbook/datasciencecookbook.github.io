---
layout: post
title: "Appendix A: Process Management"
date: 2011-1-1
permalink: /appendix-a/
---
You have a team (more than just you) working on the same project, but how do you collaborate? We’ve got you covered. But first, here’s a quick round-up of the alphabet soup of words you might hear.

- [Waterfall](https://www.simplilearn.com/waterfall-vs-agile-vs-devops-article) is a linear project framework with discrete phases (Milestone A, Milestone B) done sequentially. It comes from manufacturing. For example, you can’t put a roof on a house until you’ve built the walls, and you can’t build walls until you’ve poured the foundation, you don’t pour a foundation until you have a design.
- [Agile](https://www.simplilearn.com/waterfall-vs-agile-vs-devops-article) is a set of principles for delivering value to users by continuously deploying working software and iterating on that software with customer feedback.
    - [Kanban](https://www.youtube.com/watch?v=iVaFVa7HYj4) is a way to visualize backlog, work-in-progress, and improve transparency. It limits the work-in-progress so you don’t get distracted from the task at hand. It’s very process-improvement driven as well. More [here](https://kanbanize.com/kanban-resources/getting-started/what-is-kanban).
- [Scrum](https://scrumguides.org/scrum-guide.html) is about getting more work done faster. A Scrum Master facilitates daily meetings to remove obstacles during a sprint and the team does a retrospective at the end of each sprint to understand what can be improved.
- [Sprint](https://www.atlassian.com/agile/scrum/sprints) is a ~2 week time period where the team decides on a set of deliverables and then builds those deliverables. If someone says ‘90 day sprint’ it’s not a sprint.

A note! Agile is a methodology, not a religion. It’s a tool to get things done, not an end in itself. Also, the Federal Government has been overcome with agile buzzwords. These are not always accompanied with agile practices. And now for the tools!

<br><br>
### Trello
Create a board, and put up cards for each project task. Assign them to your team members. Go. That’s [Trello](https://trello.com/en-US). Easy, simple, and keeps you focused on work and away from your inbox. Look up [Kanban](https://www.atlassian.com/agile/kanban) and [Scrum](https://www.atlassian.com/agile/kanban) for more card-based project management tools. There are tons of them, so find what suits you.

<br><br>
### Jira
[Jira](https://www.atlassian.com/software/jira) used to be for bug/issue management but has evolved to be a project management tool. It’s free for military projects [here](https://www.di2e.net/ ), so get started today!

<br><br>
### Version Control - Git
Aside from managing project tasks, when you’ve got a team you’ll want to manage your code tool. Enter Git.

Git is a free version control system that’s easy to use and lightning fast. With Git, you’ll store your code in the cloud - [Gitlab](https://gitlab.com/) and [Github](https://github.com/) are the two most common platforms. Then you’ll clone it to your computer, and any changes you make locally are tracked. When you’ve finished, you’ll ‘push’ your updates back up to the cloud.

When you’ve got multiple team members working together, you’ll want to use Git to create forks and branches for more complex [workflows](https://www.atlassian.com/git/tutorials/comparing-workflows), possibly via the git flow toolkit. This will allow you to move seamlessly between development and production code and add plenty of features along the way.


### Human/User Centered Design
We are solving problems for users, not just for the fun of it. So users (the eventual people who use our product) need to be at the center of our process. If we make the world’s coolest technology but it doesn’t make a user’s life better or solve their problem, then our technology will shit on a shelf and collect dust (like the Segway). User centered design is all about putting the user at the center of the product design process from the very beginning, not as an afterthought. Here’s a good article on [user centered design](https://www.interaction-design.org/literature/topics/user-centered-design).
The Design Thinking Process is a [design methodology that provides a solution-based approach to solving problems](https://www.interaction-design.org/literature/article/5-stages-in-the-design-thinking-process)

<br><br>
![User Centered Design](/assets/appendix_c/user_centered_design_process.png)

<br><br>
There are five main steps to the design thinking process:
1. **Empathize** - gain an empathetic understanding of the problem you’re trying to solve.
2. **Define** (the problem) - define the core issues at hand based on analysis and observation from Stage 1. This should result in the form of a problem statement in a human-centered manner.
3. **Ideate** - begin brainstorming solutions that will solve the problem statement defined in Stage 2. This is where the majority of an application’s features and functions come to life.  There are a variety of different ideation methods that are meant to encourage free thinking and expand the problem space.
4. **Prototype** - Create a number of inexpensive, scaled-down versions of the product.
5. **Test** - Rigorously test and evaluate the prototype designed in Stage 4.

<br><br>
![Design Thinking](/assets/appendix_c/design_thinking_5_steps.jpg)

<br><br>


While these steps are numbered in sequential order, they are meant to serve as a general guideline. These steps are also iterative; typically, the Test phase redefines the problem and enables the designers to explore more solutions for future iterations to create a refined product.
