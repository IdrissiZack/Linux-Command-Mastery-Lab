# Linux Navigation — Beginner Lab

## Objective

Learn how to navigate the Linux filesystem using basic terminal commands.

## 1. `pwd` — Print Working Directory

Displays the absolute path of the current directory.

```bash
pwd
```

**Expected result:** The current directory path.

## 2. `ls` — List Directory Contents

Displays files and directories in the current location.

```bash
ls
ls -la
```

- `-l`: Displays detailed information.
- `-a`: Includes hidden files.

## 3. `cd` — Change Directory

Changes the current working directory.

```bash
cd /tmp
cd ~
cd ..
```

- `cd /tmp`: Opens the `/tmp` directory.
- `cd ~`: Returns to the user's home directory.
- `cd ..`: Moves one directory up.

## 4. `mkdir` — Make Directory

Creates a new directory.

```bash
mkdir lab-test
mkdir -p parent/child
```

- `-p`: Creates missing parent directories when necessary.

## Exercises

1. Display your current directory.
2. List all files, including hidden files.
3. Navigate to `/tmp`.
4. Return to your home directory.
5. Create a directory named `linux-practice`.

## Security Notes

Understanding filesystem navigation is essential for inspecting system files, reviewing logs, locating configuration files, and performing authorized security assessments.

## Completion Checklist

- [ ] Practiced `pwd`
- [ ] Practiced `ls -la`
- [ ] Practiced `cd`
- [ ] Practiced `mkdir`
- [ ] Completed the exercises
