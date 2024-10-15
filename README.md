#BASIC COMMANDS FOR GIT OPERTATION
#PUSHING A DIRECTORY OR FILE TO GIT


  # SELECTING THE DIRECTORY OT FILE PATH WHICH TO BE ADDED TO THE BRANCH
219  cd "D:\Devops-expert\Project-Docker-1"
  220  ls
  221  git init
  222  git add .
  223  git status
  224  git commit -m "Dokcer-projects"
  225  git branch -M main  #Shifts the branch from master to main branch
  226  git remote add origin https://github.com/DurgaPrasadPatra/project-docker.git
  227  git push -u origin main

  #if there are prior commits in the branch error message appears:
To https://github.com/DurgaPrasadPatra/project-docker.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/DurgaPrasadPatra/project-docker.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
  
  228  git pull

  ERROR MESSAGE APPEARS :
  From https://github.com/DurgaPrasadPatra/project-docker
 * branch            main       -> FETCH_HEAD
fatal: refusing to merge unrelated histories

  
  240  git pull origin main --allow-unrelated-histories
  241  git push origin main
  242  git status
  243  history
![image](https://github.com/user-attachments/assets/19f411d0-2401-4569-b6ed-b121614b62b3)
