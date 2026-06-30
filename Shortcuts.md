### 1. Comment shortcuts
#### 1. The Keyboard Shortcut

1. **Highlight** the lines you want to comment out.
    
2. **Press:**
    
    - **Windows/Linux:** `Ctrl` + `/`
        
    - **Mac:** `Cmd` + `/`
        

This works like a light switch: press it once to add `//`, and press it again to remove them.

---

#### 2. Block Comments (The "Big Wrapper")

If you want to wrap a large chunk of code in a single block (using `/* ... */`), use this shortcut:

- **Windows/Linux:** `Shift` + `Alt` + `A`
    
- **Mac:** `Shift` + `Option` + `A`
    

---

#### 3. Multi-Cursor Editing (The "Manual" Way)

If you want to feel like a pro, you can type on multiple lines at the same time:

1. Hold `Alt` (Windows/Linux) or `Option` (Mac).
    
2. **Click** at the start of each line you want to comment.
    
3. Type `//` once, and it will appear on every line where you clicked.
    

**Pro Tip:** Since you are learning React, the `Ctrl` + `/` shortcut is extra smart. If you are inside a **JSX** block (the part that looks like HTML), VS Code will automatically change the comment style to `` for you, which is the only way to comment inside a React return statement!


---
### 2. Undo & Redo

ctrl + z =undo 
ctrl + shift + z  or, ctrl + y  =redo


### 3. keep the code clean

**1. Auto format/indent — instantly fixes all alignment:**

```
Shift + Alt + F
```

One shortcut — entire file gets perfectly indented ✅

**2. Fold/collapse sections — hide code you're not working on:**

- `Ctrl + Shift + [` → collapse a block
- `Ctrl + Shift + ]` → expand a block

**3. Bracket pair colorizer — matching tags get same color:**

- Already built into VS Code
- Go to Settings → search `bracket pair` → enable it

**4. Auto rename tag extension:**

- Install from extensions (`Ctrl + Shift + X`)
- Search **"Auto Rename Tag"**
- When you change `<div>` opening tag, closing tag changes automatically ✅

**5. Emmet abbreviation — collapse tag preview:**

- Click the small arrow `›` on the left of any line to fold that block

---

**Most important one is `Shift + Alt + F`** — run it often to keep your code clean and readable. 🎯
