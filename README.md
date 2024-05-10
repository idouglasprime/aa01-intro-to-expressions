<<<<<<< HEAD
# Choose Your Branch!

This repo contains different versions of the starter code for **aa01-intro-to-expressions**,
with each version stored in a program-specific branch. To download or clone the
correct branch, choose a method (`tiged`, zip, or clone) and follow the
instructions for your specific program.

* [`tiged`](#tiged-the-branch)
* [Zip](#download-the-branch-as-a-zip)
* [Clone](#clone-the-branch)

## `tiged` the branch

This is the most straightforward way to clone the project into a folder named
**aa01-intro-to-expressions**. In the directory where you want the project to appear, simply
run the following command for your program and preferred authentication method:

### Online Full-Time

To authenticate with a Personal Access Token over HTTPS, run

```sh
npx tiged https://github.com/appacademy/aa01-intro-to-expressions#full-time aa01-intro-to-expressions
```

To authenticate with SSH, run

```sh
npx tiged appacademy/aa01-intro-to-expressions#full-time aa01-intro-to-expressions
```

### Online Part-Time

To authenticate with a Personal Access Token over HTTPS, run

```sh
npx tiged https://github.com/appacademy/aa01-intro-to-expressions#part-time aa01-intro-to-expressions
```

To authenticate with SSH, run

```sh
npx tiged appacademy/aa01-intro-to-expressions#part-time aa01-intro-to-expressions
```

-----

> **Note:** The first time you run `npx tiged`, you will likely be asked if you
> want to install `tiged`. Go ahead and install it.

Unless you cloned the project into an already existing local git repo, run

```sh
cd aa01-intro-to-expressions && git init
```

to initialize the project as a git repository that you can connect to a remote
repo in your personal GitHub account.

## Download the branch as a .zip

**READ THESE INSTRUCTIONS FULLY BEFORE IMPLEMENTING THEM AS YOU WILL LOSE ACCESS
TO THIS PAGE ONCE YOU SWITCH TO YOUR PROGRAM BRANCH.**

If you want to download your branch as a __.zip__ file, click on the branch
button to the upper-left of the file list above--the button should currently
read "main"--and select your program from the resulting dropdown menu. This will
take you to your program's branch. Once there, click the green "Code" button and
select "Download ZIP" from the bottom of the menu. Move the __.zip__ to your
desired location and unzip!

Unless you unzipped the project in an already existing local git repo, run

```sh
cd aa01-intro-to-expressions && git init
```

to initialize the project as a git repository that you can connect to a remote
repo in your personal GitHub account.

(To return to this page in your browser, simply select the "main" branch again.)

## Clone the branch

To clone the branch, open a terminal and cd into the directory where you want
the repo to go. Then run the command specified below for your program and
preferred authentication method:

### Online Full-Time

To authenticate with a Personal Access Token over HTTPS, run

```sh
git clone --branch full-time --single-branch https://github.com/appacademy/aa01-intro-to-expressions.git
```

To authenticate with SSH, run

```sh
git clone --branch full-time --single-branch git@github.com:appacademy/aa01-intro-to-expressions.git
```

### Online Part-Time

To authenticate with a Personal Access Token over HTTPS, run

```sh
git clone --branch part-time --single-branch https://github.com/appacademy/aa01-intro-to-expressions.git
```

To authenticate with SSH, run

```sh
git clone --branch part-time --single-branch git@github.com:appacademy/aa01-intro-to-expressions.git
```

When you clone a repo, the cloned repo's remote `origin` will still point to the
original repo.

To reassign the clone to your personal GitHub account (so you can `push` and
`pull` changes), create a remote `aa01-intro-to-expressions` repo at `https://github.com`.
Then, back in your local terminal, `cd` into the cloned repo and run the
following commands to link the cloned repo to your newly created remote and push
up the current code (replace <YOUR-GH-USERNAME> with your actual GitHub username):

```sh
git remote set-url origin https://github.com/<YOUR-GH-USERNAME>/aa01-intro-to-expressions
git push -u origin
```

 > **Note:** The first command differs from the command GitHub tells you to use
 > to connect an existing repo: you should run `git remote set-url` (as above)
 > rather than `git remote add` (as GitHub recommends).

 If you instead clone the project into a folder already initialized as a local
 git repo, you just need to remove the clone's remote connection to the original
 repo. `cd` into the cloned repo and run

 ```sh
 rm -rf .git
 ```

**WARNING:** `rm -rf` is a dangerous command that will delete the specified
directory--here, __.git__--and all of the directory's subfolders without any
verification. **Make sure you are in the cloned repo when you run this
command.**
"# aa01-intro-to-expressions" 
=======
# Intro to Expressions

Welcome to an App Academy coding project!

Anytime that you open a coding project, run the following command to install
dependencies:

```sh
npm install
```

Then, follow the prompts in the block of instructions at the top of every
problem file in the __/problems__ folder of the project.

To run your code in a problem file, run the following command in your terminal
and replace `<problem-file-name>` with the name of the problem file:

```sh
node problems/<problem-file-name>.js
```

For example, to run the first problem file in the __/problems__ folder, run the
following command in your terminal:

```sh
node problems/01-console-log.js
```

To test your code in a problem file with the given test specifications, run the
following command in your terminal and replace `<problem-file-name>` with the
name of the problem file:

```sh
npm test test/<problem-file-name>-spec.js
```

For example, to test the first problem file in the __/problems__ folder, run the
following command in your terminal:

```sh
npm test test/01-console-log-spec.js
```

You know you are done with this coding project when you get all tests to pass
with green check marks in your terminal!

Have fun coding! 😊
>>>>>>> 2560ea4 (Updated from solution change by brtrick)
