# 📘 2.2 Using the Command Line to Get Help (Weight: 2)
**Running help commands and navigation of the various help systems.**

---

## 📝 **Key Knowledge Areas — Study Notes**

### ⭐ **Man Pages**
- Primary source for command documentation 📖  
- Organized by **sections** (1=user commands, 2=system calls, etc.)  
- Syntax: `man [section] command`  
- Navigation: **up/down arrows, q to quit**  
- Provides **options, usage examples, and description**

---

### ⭐ **Info Pages**
- Alternative to man pages, often more detailed 📘  
- Structured with **nodes & menus**, easier to browse complex topics  
- Syntax: `info command`  
- Navigation: arrows, Enter to follow links, `q` to quit  

---

### ⭐ **Documentation in /usr/share/doc/**
- Packages often include **README, changelogs, examples**  
- Location: `/usr/share/doc/<package>/`  
- Useful for **offline reference and package-specific info**  

---

### ⭐ **Locate**
- Quickly find **files and documentation** on system 🔍  
- Command: `locate filename` → uses **database updated by updatedb**  
- Useful for **finding man pages, README files, or config files**

---

### 🧩 **Partial List of Key Knowledge — Notes & Context**
- **man** → Display manual pages for commands  
- **info** → Display structured info pages  
- **/usr/share/doc/** → Offline documentation for installed packages  
- **locate** → Quickly find files or documentation  

---

### ⚡ **Practice Tips**
- Use `man ls` or `man 5 passwd` → explore sections  
- Try `info coreutils` → navigate nodes & links  
- Browse `/usr/share/doc/` of installed packages: `ls /usr/share/doc/bash/`  
- Find files with `locate README` or `locate man`  
- Focus on **learning navigation and where to find info quickly**
