[Demo](https://codeforpakistan.github.io/first-commit/)

# Steps to Contribute

# Create Fork of Repo

 - Open Repo on github `https://github.com/codeforpakistan/first-commit.git`
 - On the top-right corner of the page, click Fork.
 - By default your username is selected in the owner if not selecte your username and click create fork

![fork](./assets/fork.png)

# Upstream to Orignal Repo

- Add upstream to orignal repo to sync before doing any new changes to avoid conflicts

- `git remote add upstream https://github.com/codeforpakistan/first-commit.git`


# Verify Upstream

- `git remote -v`


![upsteam](./assets/upstream.png)


# Fetch and merge main branch from upstream

- `git fetch upstream`
- `git merge upstream/main`

# Add Your Contribution and Push

- open the `first-commit` folder
- open the data folder
- create new branch `git checkout -b branch-name`
- Add new obj/row in contributors.json like below
- Commit your changes ` git commit -am 'commit msg'`
- Push to remote repo 'git push origin branch-name`

```
  {
      "name": "Muhammad Sohail",
      "githubUsername": "sohail0992",
      "site": "https://sohail0992.github.io"
  }
```

# Create a PR from your fork to original repo

## Contributors

<a href="https://github.com/codeforpakistan/first-commit/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=codeforpakistan/first-commit" />
</a>

Made with [contrib.rocks](https://contrib.rocks).
