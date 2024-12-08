# **bookCinema**

A collaborative movie booking system being developed by a team of 5.  
**Features:**  
- User authentication  
- Seat selection  
- Payment integration  

---

## **Getting Started**

### **Clone the Repository**
Run the following command to clone the repository to your local machine:  
```bash
git clone https://github.com/pranavp-work/bookCinema.git
```

---

## **Working with the Repository**

### **Adding Changes to the Main Branch** *(Directly)*
1. **Switch to the `main` branch**:
   ```bash
   git checkout main
   ```

2. **Pull the latest changes**:
   ```bash
   git pull origin main
   ```

3. **Add, Commit, and Push Changes**:
   - Stage your changes:
     ```bash
     git add . 
     ```
     *or* (recommended):
     ```bash
     git add -A
     ```
   - Commit the changes:
     ```bash
     git commit -m "Your descriptive message here"
     ```
   - Push to the `main` branch:
     ```bash
     git push origin main
     ```

---

### **Creating and Working on a New Branch** *(Recommended for Features or Fixes)*

1. **Create a new branch**:
   ```bash
   git checkout -b branchName/sub-branchName
   ```
   Example:  
   ```bash
   git checkout -b feature/add-booking-form
   ```

2. **Add, Commit, and Push Changes**:
   - Stage your changes:
     ```bash
     git add . 
     ```
     *or* (recommended):
     ```bash
     git add -A
     ```
   - Commit the changes:
     ```bash
     git commit -m "Your descriptive message here"
     ```
   - Push the branch to GitHub:
     ```bash
     git push origin branchName/sub-branchName
     ```
     Example:  
     ```bash
     git push origin feature/add-booking-form
     ```

3. **Create a Pull Request (PR)**:
   - Go to the repository on GitHub.
   - Navigate to the **Pull Requests** tab.
   - Click **New Pull Request**.
   - Select your branch as the source and `main` as the target branch.
   - Submit the pull request for review.

---

### **Syncing Your Local Repository**
Always pull the latest changes from `main` to stay updated with the project:  
```bash
git pull origin main
```

---

### **Notes:**
- Use meaningful branch names like `feature/add-login-page` or `fix/payment-bug`.
- Write clear and descriptive commit messages to make the history understandable.
- Always pull changes before starting work to avoid conflicts.
