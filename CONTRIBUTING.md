# Welcome to the ERC Verilog Library contributing guide

Thank you for investing your time in contributing to the ERC Verilog Library!

This guide will give you an overview of the contributing process and how to get started.

# Getting started

We accept contributions in code as well as documentation. You are free to write your own modules or improve/document modules already present.


## Contribution ideas
### Create you own modules
You are free to add modules you feel are useful. As long as it is general purpose and reusable your contribution will be accepted.

### Issues
Maintainers will keep adding issues for modules that are widely used or requested and you can choose to work on these. Before starting work on an issue please leave a coment so the maintainer can assign you the issue. Kindly avoid creating PRs for issues that have already been assigned to someone else. If you are not sure if an issue is already assigned to someone else please ask.

## How to fork and PR
1. Fork the repo.
2. Clone the forked repo using
```
git clone <repo_url>
```
2. Create a new branch for your PR using
```
git checkout -b <branch_name>
```
3. Write your code in the new branch.
4. Add the changes to the staging area using 
```
git add <file_name>
```
5. Commit the changes using
```
git commit -m "message"
```
Note: Please use sensible commit messages.

6. Push your code to the remote repo.
```
git push origin <branch_name>
```
7. Create a PR by going to the repo's page and clicking the "New pull request" button. Please make sure your PR title and description are descriptive and self explanatory.

## File structure
Please maintain the file structure of the repository. Each module has to be in a folder named after the module itself. The testbench for the module should also be located in the same folder. The testbench will be named after the module with the suffix "_tb". There is no need to push the vcd dumps or compiled binaries. When using include statements to include other modules from the library, make sure you use the file path with respect to the repo and not your local paths.

# PR guidelines
1. Codes must be general purpose and re-usable (We do not want codes specific to your assignment xD).
1. Documentation PRs are acceptable.
1. Merging of PRs will be at maintainer's discretion.

## Hacktoberfest specific guidelines
1. The PRs must follow the hacktober fest guidelines which can be found [here](https://hacktoberfest.digitalocean.com/resources/participation).
1. Any valid PR will be hacktoberfest-approved but may not necessarily be merged into the repo.
1. Do not submit PRs for duplicates of modules that are already present in the repo. You can however make changes to existing modules.
1. Do not copy codes from other repositories or websites. Your PR will be marked as invalid if you do so.

