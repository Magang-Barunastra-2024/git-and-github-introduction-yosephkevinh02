[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/tbEHDGEc)

# Git and Github Introduction

| Name  | Division        | Sub-Division  |
| ----- | ---------- | ---------- |
| Yoseph Kevin Hendrata   | PGR | Vision and Control |

## A. Early Procedure

### **1. Install Git on PC/Laptop**  

   ```bash
   https://git-scm.com/downloads
   ```

### **2. Create a GitHub Account**  

   ```bash
   https://github.com/join
   ```

### **3. Configure Git**

   ```bash
   git config --global user.name "your_username"  
   git config --global user.email "your_mail@mail.com"
   ```

### **4. Add SSH Keys**  

#### a. Create an SSH key

   ```bash
   ssh-keygen -t ed25519 -C "your_mail@mail.com"`  
   ### Hit enter until key generated ###
   ```

#### b. Copy the SSH key

   ```bash
   cd ~/.ssh
   cat id_ed25519.pub
   ### Block and copy the SSH key ###
   ```  

#### c. Go to **GitHub Settings** -> **SSH and GPG Keys** -> **New SSH Key**

#### d. Fill title field and paste the SSH key using `Ctrl + V` or `Cmd + V` into key field

## B. Create Repository

### **1. Open Github -> Create a New Repository**

   ```bash
   https://github.com/new
   ```

### **2. Fill repository name, set to private or public, and click `Create Repository`**

### **3. Open Repository -> Code -> SSH -> Copy SSH Link**

### **4. Connect the repository to local folder**

#### a. Local Folder

&nbsp;&nbsp;&nbsp;&nbsp; 1) Create a folder with the same name as the repository  
&nbsp;&nbsp;&nbsp;&nbsp; 2) Open Git Bash / Terminal

   ```bash
      git init
      git remote add origin <SSH_Link>
      git branch -M main
      git pull origin <Branch_Name>
   ```

#### b. Git Clone

&nbsp;&nbsp;&nbsp;&nbsp; 1) Navigate to directory in File Explorer  
&nbsp;&nbsp;&nbsp;&nbsp; 2) Open Git Bash / Terminal

   ```bash
      git clone <SSH_Link>
      cd ./<Repository_Name>
      git branch -M main
   ```

## C. Push File from Local to Github

### **1. Add or Modify Files in Local**

### **2. Open Git Bash / Terminal**

   ```bash
      git add .
      git commit -m "commit_description"
      git push origin <Branch_Name>
   ```

## D. Create New Branch in Github

## E. Delete Branch in Github

## F. Merging Branch in Github

## G. Other Procedure
