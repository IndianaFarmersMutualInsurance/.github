# Indiana Farmers Mutual Insurance GitHub

## Git Best Practices
1. Repositories
    - Repo naming convention: {teamName}_{projectName}
    - Divide repos into logical project sizes (API, libraries, etc.)
2. Branching
    - Branch naming convention: {work item number}\_{featureSummary}\_{author}
    - Always create branches off of the [dev] branch for distinct work items. One branch = one feature
3. Commits
    - Do not commit broken code
    - Write descriptive commit messages
    - Make commits frequently with incremental changes (ideally less than 50 lines)
    - Changes must be solely related to the branch feature/work item
    - Avoid adding referenced projects/files to git unless absolutely necessary
4. Merging
    - Always create pull requests to merge your working branch into [dev]
    - Obtain code review approval from at least 1 (2?) other person (people)
    - If your merge contains conflicts, add the developer who made the conflicting changes to the reviewer list to assist in resolving them
    - Do not merge directly into main or another person's branch