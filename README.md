# ACM SIGDOC Structured Authoring article

Markdown articles that ACM SIGDOC Structured Authoring committee members write are hosted on this repository. Reviews take place by using the branching system, which separates articles into different branches during their review lifecycle. The final version of the articles and other resources are published on our committee resources website:

- [ACM SIGDOC Structured Authoring Committee Resources](https://acm-sigdoc-structured.org/index.html)

# How to contribute

Before you contribute, reach out to us at authors@acm-sigdoc-structured.org. After onboarding, you can pick from a list of topics and begin writing your article.

# General workflow

We support articles written in Markdown. The workflow process is broken down into the following five steps, which you can access as branches in the repo:

- `initial_draft`
- `technical_review`
- `instructional_review`
- `editorial_review`
- `final_draft`

Every branch has a folder with the author name, which contains the articles that the author writes. You can add your folder and name if there is none yet.

**Optional:** You can add additional subfolder to help organize your articles.

You must create your own new working branch at every step and work on your draft in that branch. Your working branch is always a copy of the latest review step branch that your draft was accepted into.

To progress to the next step in the review process, create a pull request using your working branch and open it against one of the five review step branches that represents the review step that you are ready for.

Your working branch can always be a copy of the latest review step branch that your article was merged into.

For example, if you do not have a draft yet, you can create a branch named `my_working_branch`. In that branch, write your article as a Markdown file. When you are ready for your draft to appear in the `initial_draft` branch, create a pull request with `my_working_branch` as your source and `initial_draft` as your destination.

The review occurs in the pull request. The reviewer can add comments, make suggestions, and directly approve the pull request.

After your pull request is approved and merged, your draft appears in `initial_draft` and you can delete the `my_working_branch` branch.

Now, you can proceed to the next step by creating a copy of `initial_draft` as your new working branch. Make any changes you need to it. When you are ready for technical review, follow the same steps as previously.

You can find a detailed breakdown in the following topics:

# Detailed article lifecycle

See the following topics to learn how to write your article and get it reviewed. Each of the following topics represents of the review steps.

## Initial draft

### Prerequisite

- You must have been onboarded and added to the project as a contributor

### Workflow

An initial draft is required before you can receive reviews. Complete the following steps to get your new article into the `initial_draft` branch:

1. Create a new working branch. Use `initial_draft` as your **Base**. Name it using the following template: `<your_initials>_new`

2. In your working branch, create a `<article_name>.md` file in `/article/<author_name>`

3. Write your article in Markdown in the `<article_name>.md` file and commit your changes.

4. Create a pull request. Use your working branch `<your_initials>_new` as the **compare** and use `initial_draft` as the the **base**.

5. Wait for a reviewer to approve your pull request. Address any comments as needed.

6. After you receive approval, merge your pull request and delete your working branch.

## Technical review

### Prerequisite

- You must have an article in the `initial_draft` branch.

### Workflow

You will receive technical review during this process. Complete the following steps to get your initial draft into the `technical_review` branch:

1. Create a new working branch. Use `initial_draft` as your **Base**. Name it using the following template: `<your_initials>_tech`

2. In your working branch, commit any changes you want to your `<article_name>.md` to prepare to tehcnical review.

3. Create a pull request. Use your working branch `<your_initials>_tech` as the **compare** and use `technical_review` as the the **base**.

4. Wait for a reviewer to approve your pull request. Address any comments as needed.

5. After you receive approval, merge your pull request and delete your working branch.

## Instructional review

### Prerequisite

- You must have an article in the `technical_review` branch.

### Workflow

You will receive instructional review during this process. Complete the following steps to get your initial draft into the `instructional_review` branch:

1. Create a new working branch. Use `technical_review` as your **Base**. Name it using the following template: `<your_initials>_instruct`

2. In your working branch, commit any changes you want to your `<article_name>.md` to prepare for instructional review.

3. Create a pull request. Use your working branch `<your_initials>_instruct` as the **compare** and use `instructional_review` as the the **base**.

4. Wait for a reviewer to approve your pull request. Address any comments as needed.

5. After you receive approval, merge your pull request.

## Editorial review

### Prerequisite

- You must have an article in the `instructional_review` branch.

### Workflow

You will receive editorial review during this process. Complete the following steps to get your initial draft into the `editorial_review` branch:

1. Create a new working branch. Use `instructional_review` as your **Base**. Name it using the following template: `<your_initials>_edit`

2. In your working branch, commit any changes you want to your `<article_name>.md` to prepare for editorial review.

3. Create a pull request. Use your working branch `<your_initials>_instruct` as the **compare** and use `instructional_review` as the the **base**.

4. Wait for a reviewer to approve your pull request. Address any comments as needed.

5. After you receive approval, merge your pull request.

## Final draft

### Prerequisite

- You must have an article in the `editorial_review` branch.

### Workflow

You can add your article directly to `final_draft` when it is ready for publishing.

# Guide for reviewers

WIP

