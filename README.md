# pretty-pull
Open a pull request, fill it with commit messages

## Usage
pretty-pull makes use of GitHub's [`hub` utility](https://hub.github.com/) to open pull requests. Please install it before trying to use pretty-pull.

1. Source or copy `pretty-pull` in your `.bashrc` or `.bash_profile`
2. `$ pretty-pull <BASE_BRANCH> <FEATURE_BRANCH>`
    1. `BASE_BRANCH` is optional and will default to `master`
    2. `FEATURE_BRANCH` is optional and will default to the currently-checked-out branch

```bash
hub clone jessereitz/pretty-pull &&
echo ". ~/pretty-pull/pretty-pull" >> ~/.bashrc
```
