## Titulo: Backup Profile 
**fecha**: 2024-09-05 
**tags**: [#firefox #browser #backup #profile #navegador #zen ]

# Backup Profile

[[Firefox]] (https://github.com/yokoffing/Betterfox/wiki/Backup#make-a-backup-profile)

In case you want to revert back for any reason, you should create a copy of your entire profile directory.

⚠️ **Deleting the `user.js` will NOT revert any changes.** ⚠️  
(Just because all of the changes were stored in a `user.js` file doesn't mean your profile will revert back.)

---

## Instructions

### Open the profile folder

1. To find your profile directory in Firefox, go to `about:support`.
2. Find the 11th item listed, **Profile Folder**, and select **Open Folder** button.

### Copy+paste contents

3. Close Firefox. Copy the contents of the folder.
4. In Explorer (Windows) or Finder (macOS), go back a page to see all the Firefox profiles.
5. Create a new folder, and paste the contents into it.

### Name your profile
6. Rename your copied folder to something meaningful, and keep the original name (for an easy rollback).
    - For example, if the profile folder is called `ljgba71b.default`, a backup copy might be called `ljgba71b.default-backup` or `ljgba71b.default-pre-betterfox-userjs`.
7. Open the new profile folder and paste the contents into it.
8. Close the window. You now have a backup profile! 😄

🛑 Always make a backup!