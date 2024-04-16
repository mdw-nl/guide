# Version Control


## Strive for atomic commits
Commit small changes often. Strive to make the smallest possible commit that adds one fix or feature without breaking the build.

## Write a good commit message
As a title, write a short summary of what the commit does when applied in present tense. For this, use less than 50 characters and do not end with a period at the end of the title. Separate it from the body with a blank line. Then follow with a message that provides details, explanations and motivations behind the change. For example:
```
  commit 3114a97ba188895daff4a3d337b2c73855d4632d
  Author: [removed]
  Date:   Mon Jun 11 17:16:10 2012 +0100

    Refactor foo server unit tests

    Most of the existing unit tests pertaining to the bar service contained duplicate code. Code was reduced by refactoring the Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam gravida in velit quis auctor. Phasellus lobortis sagittis interdum. Sed blandit maximus lorem, sit amet lobortis turpis mollis id. Interdum et malesuada fames ac ante ipsum primis in faucibus. Nulla ornare lorem eu ante tristique, ut facilisis urna accumsan. Phasellus et luctus mauris. Donec ornare ut purus et vehicula. Pellentesque at arcu nisi.
```

## Workflow practices
Do not commit on main. Create a new branch for each distinct feature/issue.
