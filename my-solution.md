# Solution

Complete each task. Then, follow the instructions as to what to copy and paste into the empty code block.

> **Note:** Carefully read the instructions for each task. Sometimes you will be asked to record the _command(s)_ you wrote while other times you will be asked to record the _output_ of the command you wrote.

## 1

Create a new directory called `git-lab/`. Then, navigate inside of that directory.

Copy and paste _the command(s)_ you used into the code block below.

```
    mkdir git-lab
    cd git-lab
```

## 2

Initialize the directory as a git repository.

Copy and paste the _output_ of the command(s) you ran into the code block below.

```
    git init
```

## 3

Check the current status of the git repository.

Copy and paste the _output_ of the command(s) you ran into the code block below.

```
    git status
```

## 4

Create a new file called `readme.md`. Then stage that file.

Copy and paste _the command(s)_ you used into the code block below.

```
    touch readme.md
    git add readme.md
```

## 5

Check the current status of the git repository.

Copy and paste the _output_ of the command(s) you ran into the code block below.

```
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   readme.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	.DS_Store

```

## 6

Add the following text to your `readme.md` file.

```
I am learning to use git.
```

Then, check the current status of the git repository.

Copy and paste the _output_ of the command(s) you ran into the code block below.

```
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   readme.md

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   readme.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	.DS_Store

```

## 7

Commit your changes and include a sensible commit message. Then, check your repository's history.

Copy and paste _the command(s)_ you used into the code block below.

```
    git commit -m "Here you go, a nice commit for you :)"
```

## 8

Check the current status of the git repository.

Copy and paste the _output_ of the command(s) you ran into the code block below.

```
On branch main
Untracked files:
  (use "git add <file>..." to include in what will be committed)
	.DS_Store

nothing added to commit but untracked files present (use "git add" to track)
```

## 9

Stage your changes and then make another commit with a sensible commit message.

Copy and paste _the command(s)_ you used into the code block below.

```
    git add readme.md
    git commit -m "final commit"
```
