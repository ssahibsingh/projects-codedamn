# _**Step3: Upload the code from `codedamn's playground` to your `github repository`.**_

[_**Working Demo**_](https://github.com/tanishq-singh-2301/add-visitors-to-github-readme)

### _**Steps**_

- _**Create a Github token to push your code**_
  1. Go to [github.com/settings/tokens](https://github.com/settings/tokens)
  2. Click `Generate new token.`
  3. Set a name `Codedamn's playground.`
  4. Give the `repo` scope (that will be sufficient).

<br />

- _**Create a Github repository**_
  1. Go to [github.com/new](https://github.com/new)
  2. Set a name `my-cool-project`
  3. Give the `Create repository` to generate an empty repository.

<br />

- _**Initialize Git**_

  ```bash
  git init
  ```

- _**Set Global Git Configuration**_

  ```bash
  git config --global user.name "Your name" # Not username
  git config --global user.email "your-email@example.com"
  ```

- _**Add all the files (what you want to push)**_

  ```bash
  git add .
  ```

- _**Commit files**_

  ```bash
  git commit -m "My cool project is ready..!!"
  ```

- _**Make a default branch (main)**_

  ```bash
  git branch -M main
  ```

- _**Add repo's origin**_

  ```bash
  git remote add origin https://github.com/your-user-name/your-repo-name.git
  ```

- _**Push the code.**_

  ```bash
  git push -u origin main
  ```

  - Then you'll be promoted to give `username` and `password`.
  - for `password` you've to give `token` that you generated.

<br />
<hr />

## **_Congratulations_ 🥳🥳**
