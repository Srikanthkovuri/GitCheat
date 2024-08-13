### **Basic Git Commands**

1. **To Setup Your Git Username**
   ```bash
   git config --global user.name "your-username"
   ```

2. **To Setup Your Git user email**
   ```bash
   git config --global user.email "your-useremail"
   ```

3. **To view your Git Configuration list**
   ```bash
   git confiig --list
   ```

4. **Initialize a repository**:
   ```bash
   git init
   ```

5. **Clone a repository**:
   ```bash
   git clone <repository_url>
   ```

6. **Check the status of your files**:
   ```bash
   git status
   ```

7. **Add files to the staging area**:
   ```bash
   git add <file_name>
   ```
   To add all files:
   ```bash
   git add .
   ```

8. **Commit changes**:
   ```bash
   git commit -m "Your commit message"
   ```

9. **View commit history**:
   ```bash
   git log
   ```
10. **View commit history in oneline**
    ```bash
    git log --oneline
    ```
   
11. **Create a new branch**:
    ```bash
    git branch <branch_name>
    ```

12. **Switch to a branch**:
    ```bash
    git checkout <branch_name>
    ```

13. **Create a new branch and Switch to a branch**
    ```bash
    git checkout -b <branch_name>
    ```

14. **Merge a branch**:
    ```bash
    git merge <branch_name>
    ```

15. **Push changes to a remote repository**:
    ```bash
    git push origin <branch_name>
    ```

16. **Pull changes from a remote repository**:
    ```bash
    git pull
    ```

