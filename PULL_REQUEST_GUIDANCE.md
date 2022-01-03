#### Branching Strategies
For the code repositories such as Akkatecture, and any others that are to be built into Nuget packages, a more formal branching strategy will be used. It's a bit like Git Flow:
* The ***main*** branch will always represent what is currently released. Each release of code will be represented by a tagged commit in the ***main*** branch.
* The ***dev*** branch is where pull-requests are targeted. Development by individual contributors should begin with this branch.
* Feature branches, i.e. "***feature/newWhizBang***" may be used when two or more team-members are working together on a specific effort. These branches can be merged to ***dev*** from a pull-request.

For repositories that are not core library code, i.e. documentation and example solutions, a less formal approach is reasonable. Please feel free to open PRs directly against ***main*** if a ***dev*** branch does not already exist in the AfterLutz repository in question. 

#### Curate your commits!

It's always a good practice to squash your working commits before creating a PR. Remove any extraneous noise and make commit comments as relevant as possible to the changes made. 

