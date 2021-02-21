1. Fork the repo and clone your fork
2. Create new branch (git checkout -b some-thing)
3. Make the desired changes
4. Ensure tests pass (go test -cover or make test)
5. Run lint and fix problems (go vet . or make lint)
6. Commit changes (git commit -am 'Did something')
7. Push branch (git push origin some-thing)
8. Submit pull request

To make things as seamless as possible please also consider the following steps:

- Update examples/main.go with a simple example of the new feature
- Update README.md documentation section with any new exported API
- Keep 100% code coverage (you can check with make coverage)
- Squash commits into single units of work with git rebase -i new-feature
