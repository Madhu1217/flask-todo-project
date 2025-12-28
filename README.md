# Objective:
Demonstrate Git branching, merging, conflict resolution, reset, rebase, and Flask + MongoDB integration.

# 1: Repository Creation & Initial Merge
- Created GitHub repository
- Generated SSH key and cloned repo
- Created branch 'madhu'
- Added Flask files and merged to main

<img width="1745" height="702" alt="image" src="https://github.com/user-attachments/assets/1d42a230-0950-4c75-98d3-16cf2e7cbd6f" />
<img width="927" height="510" alt="image" src="https://github.com/user-attachments/assets/c8872296-ce8f-4eb7-a753-7b8f98436e0c" />
<img width="900" height="499" alt="image" src="https://github.com/user-attachments/assets/caf85115-be79-423b-b9a1-15803546626b" />

Commands:
```bash
git clone git@github.com:madhu1217/flask-todo-project.git
git checkout -b madhu
git add .
git commit -m "Added Flask project files"
git checkout main
git merge madhu
```

<img width="930" height="732" alt="image" src="https://github.com/user-attachments/assets/5c85f2a4-cbc1-4b5e-8924-2f46ef3aa145" />

# 2: JSON Update Branch
- Created madhu_new branch
- Updated JSON for /api
  
<img width="891" height="142" alt="image" src="https://github.com/user-attachments/assets/eda543fe-076a-4a32-885b-db6058bbcd43" />
<img width="936" height="898" alt="image" src="https://github.com/user-attachments/assets/1103631b-30f1-4856-8bff-98295b434877" />
<img width="895" height="118" alt="image" src="https://github.com/user-attachments/assets/e1a565d7-1e2f-4cda-a308-9d2a46250478" />

# 3: Frontend & Backend Branches
- master_1: To-Do frontend
- master_2: Backend API with MongoDB
- Merged both to main

<img width="1018" height="747" alt="image" src="https://github.com/user-attachments/assets/fd26a8ab-05d2-45ac-8a94-91b6981c9516" />

# 4: Sequential Commits, Reset & Rebase
- Added Item ID, UUID, Hash (separate commits)
- Used git reset --soft
- Rebasing main into master_1 without squashing
<img width="900" height="456" alt="image" src="https://github.com/user-attachments/assets/ea92237b-fff5-40b8-8fd2-1e3cc2470bd1" />
<img width="1056" height="642" alt="image" src="https://github.com/user-attachments/assets/2b6bd326-9620-47c3-805d-49a12efd5f02" />


