# Git Branching

Git branches are a powerful feature of Git that allow developers to work on different versions of their codebase simultaneously. Branches make it easy to work on new features or bug fixes without affecting the main codebase until the work is complete.

### Creating git Branches

<div style="position: relative; padding-bottom: 56.25%; height: 0; margin-top:1.6em"><iframe src="https://www.youtube.com/embed/wVM4tfKsXBY;rel=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>

Use the following command to create a new branch:

```bash
git branch <branch-name>
```

Use the following command to list all branches:

```bash
git branch
```

### Switching git Branches

Use the following command to switch to an existing branch:

```bash
git checkout <branch-name>
```

You can also use `git switch` instead of `git checkout` to create and switch to new branches.

Use the following command to create a new branch and switch to it:

```bash
git switch -c <branch-name>
```

Use the following command to switch to an existing branch:

```bash
git switch <branch-name>
```

### Merging Branches and Handling Conflicts

<div style="position: relative; padding-bottom: 56.25%; height: 0; margin-top:1.6em"><iframe src="https://www.youtube.com/embed/KH_FGqiQ74c;rel=0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen style="position: absolute; top: 0; left: 0; width: 100%; height: 100%;"></iframe></div>
