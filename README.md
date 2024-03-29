# Development Environment Cookbook

The following are a list of tools Noel uses to write code. The list assumes that Noel is writing mostly in __Python__ and uses the environment for _Data Engineering_ tasks. Specifications on the different tools will be listed below.


### Summary

This cookbok will assume that you are working on a `UNIX` machine (preferrably on a MacOS). It will primarily use __Ansible__ to automate the installation of the different tools necessary to get started coding.

#### Get Started

1. Read the gist about [paths](https://gist.github.com/Linerre/f11ad4a6a934dcf01ee8415c9457e7b2)
2. Run the script `start.sh` to install Homebrew, Ansible and Docker
3. Run Shell playbook by running
```shell
ansible-playbook playbooks/shell_playbook.yml
```
4. Run Tools playbook by running
```shell
ansible-playbook playbooks/tools_playbook.yml
```

#### Automation Tools

1. Homebrew
2. Ansible
3. Docker

#### Shell tools

1. Fira Font
2. Starship Prompt
3. Ripgrep
4. Tree
5. starship.rs
6. Jump
7. Fzf
8. Tldr
9. Hyper

#### Text tools

1. PyCharm
2. Visual Studio Code


#### Extra tools

1. Spotify
2. Messenger
3. Slack
4. Magnet (get from AppStore)
5. Zoom
6. Microsoft Office (get from Office365)
7. 1Password


### VS Code

Configuration
```
# settings.json

"editor.fontFamily": "Fira Code",
"editor.fontLigatures": true,
```

#### Extensions
1. Python
2. Pylance
3. Prettier
4. Visual Studio Intellicode
5. Docker
6. GitLens
7. Material Icons
8. Markdown All In One

### Hyper Terminal

Configuration
```
# ~/.hyper.js

shell: '/opt/homebrew/bin/fish',
...
fontFamily: '"Fira Code", Menlo, "DejaVu Sans Mono", Consolas, "Lucida Console", monospace',
...
webGLRenderer: false,
...
hyperline: {
      plugins: [
        "ip",
        "cpu",
        "memory",
        "network",
        "battery"
      ]
},
```

Errors
```
$ cd ~/.hyper_plugins
$ npm install
```

#### Extensions
1. hyper-font-ligatures
2. hyper-pane
3. hyper-tabs-enhanced

#### References
- https://timonbimon.medium.com/yet-another-step-by-step-guide-for-a-better-terminal-setup-6c5e879d4c8c