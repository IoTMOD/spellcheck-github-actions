# spellcheck-github-actions
A Github Action that spell checks Python, Markdown, and Text files.

This action uses [PySpelling](https://facelessuser.github.io/pyspelling/) to
check source files in the project.  

## Configuration
If your repo contains `spellcheck.yaml` it will be used instead of the default config.
See https://facelessuser.github.io/pyspelling/configuration/ for options.