# SPR Demo App in WSL

Github stacked pull requests (SPR) tool demo app.

## 🚀 Changes

1. init
2. feature 1
3. feature 2
4. feature 3

>>> How to install 

- use WSL (Linux) because this tool currently works for Windows terminal.
- installation of SPR. https://github.com/ejoffe/spr/releases/tag/v0.14.9 use this link and download the installation file.
- install and add bin folder path into your environment variables.
- Add your changes and commits as features for each. make sure to add separate identical changes to this.
- use >>> git spr update
[✗✗✔✔] github.com/ejoffe/spr-demo/pull/2 : Feature C
[✗✗✔✔] github.com/ejoffe/spr-demo/pull/2 : Feature B
[✔✔✔✔] github.com/ejoffe/spr-demo/pull/1 : Feature A
- This will create PRs for each commit and branches for each feature.
- once all the checks are ticked you can use merge command. It will merge according to the stacked order.
- git spr merge
MERGED github.com/ejoffe/spr-demo/pull/1 : Feature A
