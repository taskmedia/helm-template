# TODO

1. Replace `taskmedia-bot` with your GitHub handle in [CODEOWNERS](.github/CODEOWNERS) file.
   See [GitHub CODEOWNERS docs](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/about-code-owners) for more information.

1. Ensure empty branch `gh-pages` exists:
  ```bash
  git switch --orphan gh-pages
  git commit --allow-empty -m "chore: init orphan gh-pages"
  git push -u origin gh-pages
  ```

1. Delete demo chart.

1. Delete this [TODO.md](../../delete/main/TODO.md) file.
