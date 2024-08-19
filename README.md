# TECH TESTS

# Tech test guide

## What is a tech test?

A tech test is a project that an employer sends you.  For example, "Build a clone of Reddit".  You work on it at home.  There's usually no time pressure to complete the project, or you are given several days to do it in your own time.

## Employer quotes

This guide has many pieces of advice to help you do a good tech test.  To help you internalise the advice, some sections include a quote from an employer where they describe a reason they rejected an applicant.

## What is the employer looking for?

Use this question to guide you at every stage of the job hunting process.

When an employer looks at your tech test solution, they are trying to find out if you can write high quality code, which is well-tested and has a good README.

## Planning your project

### Designing your solution to the problem

Before you start coding, think about the problem. Take a pen and paper, draw, think about the constraints and how to OO your code properly. You have to show this and explain what design patterns or other decisions you took BEFORE you jumped into it.

What are the downsides of your solution? Are there other solutions that would be better?

Is your solution overkill? Does the task really require a full web app, or would a command line app be fine?

> Employer quote: "They approached every problem as a CRUD style web development problem."

### Ask questions about the task

If you have questions about the tech test, just ask the employer.  They will be happy to answer.

### Be critical

You're not a code monkey. If you disagree with something, say it.

### Take your time

It's not a race. Don't forget most people don't have tests specifically for juniors so even though the test might mention a time frame, ignore it. Seriously, ignore it and build something incredible.

### TDD TDD TDD TDD

No question about this, start everything TDD/BDD properly.

> Employer quote: "2 out of the 4 devs who submitted a tech test...have not tested their code. This was a reason for [us] to reject them right away."

### Commit history

* Make many smaller commits, rather than one giant commit.

> Careers team quote: [One of] the big 3 things we hear from employers [is] commit often, not one big commit."

* Commit on green.

* Write clear commit messages.

> Employer quote: "There was no explanation [in the commit] of what was going on"

### Do it on your own

If this is a real tech test that you will submit to a company, do it on your own.  Unfortunately, coaches won't be able to help you. You can, of course, use Google and your normal developer tools.

### Complete all the tasks

Try to complete all the tasks/features specified in the tech test description.

### Tell the employer when you will submit your code

Make sure you communicate with the company when they should expect to get your code. This will demonstrate that you understand how you work and you can meet deadlines.

## Checklist

Make sure to go through this checklist before submitting your tech test solution.

### Submission checklist

**Don't submit a tech test without running through these questions first**.

- [ ] Is your code [properly tested](#testing-checklist)?

- [ ] Does your repository have a [good README](#readme-checklist)?

- [ ] Re-read the original task and check you've fulfilled all the requirements.

- [ ] Is your code formatted idiomatically?

> Employer quote: "Code was...untidy."

- [ ] Does your code look correctly formatted on GitHub as well as on your computer?

- [ ] Have you taken as much logic as possible **out of your controllers** into models/libraries?

- [ ] Have you taken logic **out of your views**?

- [ ] Does your code follow the **Single Responsibility Principle**? Ask each class, spec and method/function what it does, if the reply involves the word "and" you probably need to refactor.

- [ ] Are the units well encapsulated?

- [ ] Have you kept your **methods/classes as small as possible**?

- [ ] Have you run your code through a linter?

- [ ] Do all your **names make sense**? Can someone else understand what's going on without you having to explain it to them? Do your names use the language of the problem domain?

- [ ] Is any of your code doing anything **unusual/suprising**?

- [ ] Have you removed all comments except those that are absolutely necessary?

### Testing checklist

> Careers team quote: [One of] the big 3 things we hear from employers [is] write tests."

- [ ] Is all your code **tested** (especially unit tests but also feature tests where appropriate)?

- [ ] Are your tests passing?

- [ ] Do you have high test coverage?

- [ ] Have you tested unhappy paths and edge cases?

- [ ] Do your unit tests mock their collaborators?

- [ ] Do you always test for behaviour, rather than state?

- [ ] Do your specs **read well** when you run them?

### README checklist

> Careers team quote: "[One of] the big 3 things we hear from employers [is] write a good README."

> Employer quote: "The ReadMes are quite poor...so I had to go through their code to see what they made."

- [ ] Describe how you approached designing your solution to the problem.

- [ ] Describe how you structured your code.  Why did you do it this way?

- [ ] Describe how to install and run your code and tests.

- [ ] Describe the dependencies your code has.  What trade-offs did you make when deciding what dependencies to use?

- [ ] If you've deployed the app, include a link to it.

- [ ] Include screenshots of your running app.

- [ ] Try very hard to complete all the tasks in the tech test.  If you run out of time, outline how you would have approached the sections you didn't get to.

> Employer quote: "We did say it's OK not to complete all parts if you run out of time, but I would have expected some attempt to outline their approach/thoughts instead to show what they can do."

- [ ] Describe the extensions you would add if you had more time.

- [ ] Spelling and grammar.

### Sample Tech Tests

[Sky](https://github.com/Yorkshireman/bill_unattended#bill-unattended-test)

[Sky Scanner](https://github.com/Skyscanner/full-stack-recruitment-test)

### Further Reading

[How To Write A Git Commit Message](https://chris.beams.io/posts/git-commit/)

[Kent Beck's Design Rules](https://martinfowler.com/bliki/BeckDesignRules.html)

[Keep Your Commits Atomic](https://www.freshconsulting.com/atomic-commits/)




