# Set up a new repository

Are you new to using Git? Then this is for you.

## 1. Set up a Git account
Go to [GitHub](https://www.github.com) and create your account with your email address.

## 2. Create a repository
Just create a new project with whatever you wanted. For this, you can just create `git-starter-repo` or something like that.

## 3. Initialize git in your project directory
Now, go to your project directory and initialize git by doing the following:
```bash
git init
```

## 4. Add your files
Add your files to the repository by doing the following:
```bash
git add .
```

Or if you want add selected files:
```bash
git add file_1 file_2
```

## 5. Commit your changes
Before you push your changes, you need to write a message about what changes are done:
```bash
git commit -m "this is my first commit"
```

## 6. Link your project to the repo
Do the following to link your project to the repo that you've created in step 1:
```bash
git remote add origin https://github.com/youraccount/repositoryname.git
```

## 7. Push changes
You can decide which branch you wanted to push but initially, you'll have one branch, which is called `master`:
```bash
git push -u origin master
```

Or if you have an existing branch, just replace `master` with `yourbranchname`.

Hope that helps you out!


