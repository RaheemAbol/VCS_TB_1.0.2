# VCS_TB_1.0.2


### 🎟️ Ticket #002 – **"Cleaning the Mess: File Movement, Copying, and Renaming"**

#### 🧠 Scenario:

You’ve just received feedback from your lead software engineer: the project directory is cluttered, and you need to clean it up before the team begins development.

Your job is to **organize the source files**, **prepare a test-ready version**, and **archive old scripts** — all via terminal.

---

### 📝 Tasks:

---

#### 📂 **1. Organize the Source Folder**

* Inside the existing `src/` folder, create two new subfolders:

  * `legacy/` → for outdated or deprecated code
  * `current/` → for active/maintained code

> ✅ *Think:* What’s the command to create nested folders inside a directory you’re already in?

---

#### 📁 **2. Move Existing Files into `current/`**

Move the following files from `src/` to `src/current/`:

* `Main.java`
* `Utils.java`

> ✅ *Check:* After moving, these files should no longer appear when you run `ls` in the `src/` folder.

---

#### 🧪 **3. Prep a Test Version of a File**

* Copy `Main.java` from `current/` into `legacy/`
* Rename the copied file to: `Main_backup.java`

> ✅ *Check:* `Main_backup.java` should only exist in `legacy/`, and the original `Main.java` should remain untouched in `current/`.

---

#### 💾 **4. Archive an Old Config**

* Navigate to the `config/` folder.
* Create a subfolder named `archive/`
* Rename the file `application.properties` to `application_OLD.properties`
* Move the renamed file into the `archive/` folder

> ✅ *Check:* The `config/` folder should now contain only `.env`, and `application_OLD.properties` should be inside `config/archive/`.

---

#### 📋 **5. Final Validation**

In each of the following folders, list out their contents and verify your work:

* `src/`
* `src/current/`
* `src/legacy/`
* `config/`
* `config/archive/`

---

### ✅ Completion Checklist:

* [ ] Created `legacy/` and `current/` inside `src/`
* [ ] Moved `Main.java` and `Utils.java` into `current/`
* [ ] Copied and renamed `Main.java` to `Main_backup.java` in `legacy/`
* [ ] Created `archive/` in `config/`, renamed and moved `application.properties`

---

Do you want me to **lock this to Java** since that’s your team’s primary stack, or should I keep it language-agnostic (like `Main.java` / `main.py`)?
