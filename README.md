# 25340-0

Test Details:

1. Create a repo with single package and no labels in renovate config
2. Renovate the repo ... now the repo has one update PR with no labels
3. Now add some labels in renovate config
4. Renovate the repo again ... now the repo should have the new labels added to it
