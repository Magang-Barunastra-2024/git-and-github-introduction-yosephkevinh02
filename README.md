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

## C. Push File from Local to Github

## D. Create New Branch in Github

## E. Delete Branch in Github

## F. Merging Branch in Github

## G. Other Procedure
