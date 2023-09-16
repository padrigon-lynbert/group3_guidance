# group3_guidance

clone:
  F1,
  Git: Clone,
  https://github.com/padrigon-lynbert/group3_guidance.git

pull:
  when in main branch: git pull,
  when in other local branch pull from main: git pull origin main

add changes:
  specific: git add <specific_file>,
  all: git add .

commit:
  git commit -m "message here"
  
push:
  git push -u origin <branch_name>

create branch: 
  git checkout -b <branch_name>

delete branch:
  go to other branch
  git branch -d <name_of_the_branch_to_be_deleted>

rename branch:
  git branch -M <new_name>
  
