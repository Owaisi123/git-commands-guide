<!-- git --version -->

git --version command Git ka installed version check karne ke liye use hota hai.

 <!-- git status -->

command repository ke current state ko dikhata hai, jaise ki modified, staged, aur untracked files.

 <!-- git config --global user.email "your-email@example.com" -->

command Git ko globally email set karne ke liye use hota hai, jo commits me dikhai deta hai.

 <!-- git config --global user.name "your name" -->

command Git me globally user ka name set karne ke liye use hota hai, jo commits ke sath show hota hai.

 <!-- git config --list -->

command Git ke saare configured settings ko list karne ke liye use hota hai.

  <!-- git status -->

command repository ke current state ko check karne ke liye use hota hai, jo modified, staged, aur untracked files dikhata hai.

    <!-- git init -->

`git init` command ek naya Git repository initialize karne ke liye use hota hai.

<!-- Write -> add -> commit -->

1. **Write**: Pehle file me changes ya nayi files add karo.
2. **Add**: `git add .` se changes ko staging area me le jao.
3. **Commit**: `git commit -m "Your message"` se changes ko permanently save karo.

<!-- git add <file1> <file2> -->

`git add <file1> <file2>` command specific files ko staging area me add karne ke liye use hota hai, taaki unhe commit kiya ja sake.

<!-- . git commit -m "write message" -->

`git commit -m "write message"` command staged changes ko Git repository me save karne ke liye use hota hai ek meaningful message ke saath.

<!-- git log -->

`git log` command commit history dekhne ke liye use hota hai, jo commits ke details jaise ki author, date, aur message dikhata hai.

<!-- git log --oneline -->

`git log --oneline` command commit history ko short aur single-line format me dikhata hai, jisme sirf commit hash aur message hota hai.

<!--  git branch -->

`git branch` command repository me available branches ko dekhne ya nayi branch banane ke liye use hota hai.

<!-- git branch <branch-name> -->

`git branch <branch-name>` command ek nayi branch banane ke liye use hota hai bina us par switch kiye.

<!-- git switch <branch-name> -->

`git switch <branch-name>` command kisi existing branch par switch karne ke liye use hota hai.

<!-- git log -->

`git log` command commit history dekhne ke liye use hota hai, jo commits ke details jaise ki author, date, aur message dikhata hai.

<!-- git switch master -->

`git switch master` command **master** branch par switch karne ke liye use hota hai, agar wo branch exist karti hai.

<!-- git switch -c <branch-name> -->

`git switch -c <branch-name>` command ek nayi branch banane aur uspar switch karne ke liye use hota hai.

<!-- git checkout orange-mode -->

`git checkout orange-mode` command **orange-mode** branch par switch karne ke liye use hota hai. (Agar branch exist nahi karti, to error aayega)

⚠️ **Note:** `git checkout` purana method hai, ab `git switch orange-mode` use karna better hai.

<!-- git checkout main -->

`git checkout main` command **main** branch par switch karne ke liye use hota hai.

⚠️ **Note:** `git checkout` purana method hai, ab `git switch main` use karna recommended hai.

<!-- git merge <branch-name>  -->

`git merge <branch-name>` command current branch me **<branch-name>** ko merge karne ke liye use hota hai, taki dono branches ke changes ek sath aa jayein.

<!-- git rebase <branch-name>  -->

`git rebase <branch-name>` command **current branch** ke commits ko **<branch-name>** ke latest commits ke base par rearrange karne ke liye use hota hai, taki cleaner history mile.

⚠️ **Note:** Rebase carefully use karein, kyunki ye commit history ko modify kar sakta hai.

<!--  git cherry-pick <id> -->

`git cherry-pick <id>` command kisi specific commit (`<id>`) ko current branch me apply karne ke liye use hota hai bina puri branch merge kiye.

                                         <!-- Assigment -->

<!-- Rename branch: ==========>>>  git branch -m <old-branch-name><new-branch-name> -->

          🔹 Agar aap current branch par hain:
         git branch -m <new-branch-name>

 <!-- Delete branch: =======>>>  git branch -d <branch-name>  Agar branch fully merged nahi hai, to force delete karne ke liye:-->

Agar branch fully merged nahi hai, to force delete karne ke liye:
git branch -D <branch-name>
