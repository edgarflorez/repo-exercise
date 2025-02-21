# Meta Front-End Developer Professional Certificate

## Version Control | Lab using a repository

The exercise includes
- Create a repo.
- Create an authentication token in your Github account with specified scopes given in the terminal. Copy it from Github and paste it. Verify authorization was successful.
    - 🔎 in the upper-right corner click on your profile photo, then click settings. In the left sidebar, click Developer settings. In the left sidebar, under personal access tokens, click Tokens (classic)
- connect using github CLI.
    -  `gh auth login`
    - github.com
    - HTTPS
    - Using credentials
    - Paste token (classic)
- Clone the repo using Github CLI
- Create a new file --> `results.txt`
- Add that file --> `git add results.txt`
- Usin the `git status` command to check on the state of the process.
- Commit changes with a message `git commit -m "message"`.
- Push changes to remote repo --> `git push`.
- Verify Github GUI the new file created.

## Bonus
✨ If you are used to alias in git execute the following command.

```shell
git config --global alias.co checkout && git config --global alias.br branch && git config --global alias.ci commit && git config --global alias.st status
```
