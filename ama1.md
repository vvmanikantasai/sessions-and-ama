# CLI & Git

## 1. What is a Serial Directory
A serial directory means folders created one inside another.

```bash
mkdir -p dir1/dir2/dir3
```

---

## 2. Find a Particular Type of File
Find files using extension.

```bash
find . -name "*.txt"
```

---

## 3. Use of Git Stash
Temporarily saves uncommitted changes.

```bash
git stash
```

---

## 4. Difference Between Git Pull and Git Fetch

| git fetch | git pull |
|---|---|
| Downloads changes only | Downloads and merges changes |

---

## 5. Delete a Directory with Subdirectories
Deletes folder and all files inside it.

```bash
rm -r foldername
```

---

## 6. Kill a Browser Using PID
Kills process using process ID.

```bash
kill PID
```

---

## 7. Use of `cd ~`
Moves to home directory.

```bash
cd ~
```

---

## 8. Change Owner of a File
Changes file owner.

```bash
sudo chown username file.txt
```

---

## 9. Copy an Empty Folder
Copies folder recursively.

```bash
cp -r source_folder destination_folder
```

---

## 10. Create Multiple Folders
Creates many folders at once.

```bash
mkdir dir1 dir2 dir3
```

---

## 11. Know File Permissions
Shows file permissions.

```bash
ls -l file.txt
```

---

## 12. Merge Multiple Commits
Combines commits into one commit.

```bash
git rebase -i HEAD~3
```

---

## 13. Difference Between Relative and Absolute Path

| Relative Path | Absolute Path |
|---|---|
| Starts from current directory | Starts from root `/` |

---

## 14. PEP-8 Standards
PEP-8 is the official Python coding style guide.
Rules:
- Use 4 spaces indentation
- Variable names in lowercase
- Keep line length below 79 characters


---

## 15. Move File from One Directory to Another
Moves file to another directory.

```bash
mv file.txt destination/
```