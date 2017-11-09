Concept:  Linking data points from JIRA and GitHub APIs by scraping Jenkins log output.

- Jenkins build logs should include the GitHub PR number (exe: `(#271)`) and the PR description/title in the same statement. IF developers consistently tag every PR with the associated story/defect/bug number from their JIRA ticket (ie. `SM-586`) then we should be able to logically associate which GitHub PRs are associated with which stories.

- Using the above derived matrix, we should be able to:
1) Create a browsable visual representation of stories, their associated tasks, notes, completion times, and relevant code.
2) Associate bugs with the stories that introduced the bugs. This may open the door for future analysis of what types of stories introduce bugs?
3) Run statistical analysis to determine correlations between epochs, ticket types, other Agile metrics tracked by JIRA, and code stats (# lines, # commits, # reverts, # comments...).
