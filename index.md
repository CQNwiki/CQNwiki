@def title = "CQN Wiki"
@def tags = ["syntax", "code"]


[Theory](./theory) || [Implementation](./implementation)

This wiki is at an embryonic state. Partially it exists as an exercise in using git.

So try this:

- go to [`https://github.com/CQNwiki/CQNwiki`](https://github.com/CQNwiki/CQNwiki)
- make a fork to your personal github account
- make a clone of the fork locally on your computer | `git clone ...`
- make a new branch | `git branch ...` and `git checkout ...`
- make some commits to that new branch | `git add ...` and `git commit ...`
- push these commits to your github fork | `git push ...`
- make a pull request from that fork so your additions can be included in the wiki

To keep your local repository clone up to date:

- add a new remote | `git remote add ...`
- go to your master/main branch | `git checkout ...`
- pull the most up-to-date state from the upstream | `git pull ...`

## Guidelines

When committing a new piece of content to the wiki, please follow the general structure below to identify where your content should exist. 

- Theory, Implementation, or Applications
    -  Broad Topic Directory
        - Individual topic markdown files
	        - Sections and subsections within the individual markdown file
