---
name: Bug report
about: Report a bug
title: ''
labels: ''
assignees: ''

---

**Describe the bug**
A clear and concise description of what the bug is.

**System info**
Please include :
- Your distribution
- Your desktop manager (KDE, GNOME, Cinnamon...), if you have one
- You display manager (SDDM, GDM, LightDM...), if you have one. If you do not know, you are probably using the one coming with your desktop manager.
- Your laptop model, if you think it could be related to the problem
- The version of optimus-manager you are using : latest stable release (optimus-manager), or the latest Git version (optimus-manager-git)

**Logs**

* **If you are using the latest stable release (1.2.2): attach all the logs you can find in `/var/log/optimus-manager/`. Join them as text files or share them with a pastebin (like https://pastebin.com/). *Do not directly copy paste the logs into the GitHub issue.*

* **If you are using the Git version:** run `optimus-manager --status` in a console, and if an error message appears, post it here. The message should also point you to a log path, attach it here as well. If there is no error message but you are still experiencing issues, grab the most recent files in `/var/log/optimus-manager/switch/` and `/var/log/optimus-manager/daemon/`.
