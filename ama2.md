# AMA

## What is Ctrl + D in Linux?
Ctrl + D is used to logout or end terminal input.

Example:
```bash
Ctrl + D
```

---

## What is use of sed in Linux?
`sed` is used for editing, replacing, and deleting text in files.

Example:
```bash
sed 's/old/new/' file.txt
```

---

## How to add a small change in committed state in Git?
Use `git commit --amend` to modify the last commit.

Example:
```bash
git commit --amend
```

---

## What is Ctrl + C in Linux?
Ctrl + C is used to stop the currently running process.

Example:
```bash
Ctrl + C
```

---

## How to remove local Git repository?
Delete the `.git` folder.

Example:
```bash
rm -rf .git
```

---

## Difference between UNION and UNION ALL

| Command | Purpose |
|---|---|
| `UNION` | Combines results and removes duplicates |
| `UNION ALL` | Combines results and keeps duplicates |

Example:
```sql
SELECT name FROM students
UNION
SELECT name FROM employees;
```

---

## What is HEAD in Git?
`HEAD` points to the current branch or latest commit in Git.

Check HEAD:
```bash
cat .git/HEAD
```

---

## How to uninstall htop in Linux?
```bash
sudo apt remove htop
```

---

## Sort without duplicates in Linux
Use `sort -u` to sort and remove duplicates.

Example:
```bash
sort -u file.txt
```

---

## Difference between find and grep

| Command | Purpose |
|---|---|
| `find` | Searches files and directories |
| `grep` | Searches text inside files |

Examples:
```bash
find . -name "test.txt"
```

```bash
grep "hello" file.txt
```

---

## How to delete a branch in Git?

Delete local branch:
```bash
git branch -d branch-name
```

Force delete:
```bash
git branch -D branch-name
```

---

## Create a new branch and move to it
```bash
git checkout -b branch-name
```

---

## What is indexing in SQL?
Indexing improves the speed of searching data in a table.

Example:
```sql
CREATE INDEX idx_name
ON students(name);
```

---

## Find PID of running server
```bash
ps -ef
```

Or:
```bash
pgrep nginx
```

---

## Can SQL queries be written in case insensitive manner?
Yes, SQL keywords are case insensitive.

Example:
```sql
select * from users;
```

```sql
SELECT * FROM users;
```

Both work the same.
