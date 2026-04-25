# workflows
Reusable workflows
## build_and_release_mcmod.yml
this builds and releases a minecraft mod from its source, to use it create a file ```.github/workflows/build.yml``` with the following content:
```
on: [push, workflow_dispatch]
jobs:
  build:
    uses: TGGamesYT/workflows/.github/workflows/build_and_release_mcmod.yml@main
    permissions:
      contents: write
```
