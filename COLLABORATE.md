# How to collaborate...

## Making a local copy:

0. To start collaborating, you need to clone the repo to the local machine.
   i. CLICK the green button that stays `CODE`, on the main page of the repo,
   Copy the https link `https://github.com/usama-bit137/numerical-methods.git`.

ii. Open a terminal or Git bash and type the following command:

```
$ git clone https://github.com/usama-bit137/numerical-methods.git
```

Press enter and it should clone the repository, if it asks for a `password` just enter the your GitHub password and you should have a local copy of the repo.

## Getting started

Now that you have a local copy of the repo, the following instructions will show you how to make changes.

1. Open up a new terminal/Git bash on your machine. Type the following command in the terminal

```
$ git pull origin main
```

this will fetch all code from `remote` and merges into the `main` branch

3. Next we will

```
$ git checkout -b <YOUR-GITHUB-USERNAME>
```

this will create a new branch for you that you will be able to edit the files.

4. Edit the files as you wish and add more files.

5. Once you have finished adding and editting files, you need to stage your changes, type the following command in your teminal:

```
$ git add <FILE 1> <FILE 2> ...
```

6. Then we need to write a commit message - describe what you did:

```
$ git commit -m "YOUR MESSAGE"
```

7. Push your changes to your branch, not the `main` branch:

```
$ git push origin <YOUR-GITHUB-USERNAME>
```

## USEFUL TIPS

- Always remember to pull from the main branch when you start working on a new bit.
- Also have fun!
