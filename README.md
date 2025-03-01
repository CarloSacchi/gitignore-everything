# 🛑 gitignore-everything

A universal `.gitignore` file designed to keep your repository clean and free from unnecessary clutter. Supports a wide range of languages, frameworks, and tools, so you can focus on coding instead of managing ignored files.

## 🚀 Features
- Covers **Python, Node.js, Java, .NET, Terraform, Docker, Kubernetes**, and more.
- Includes exclusions for **OS files, IDE configurations, logs, databases, and secrets**.
- Ready to use—just copy, paste, and commit!

## 📦 How to Use
1. **Clone or download** this repository:
   ```sh
   git clone https://github.com/CarloSacchi/gitignore-everything.git
   ```
2. **Copy the `.gitignore` file** into the root of your project.
3. **Check what’s ignored** using:
   ```sh
   git status --ignored
   ```
4. **Modify as needed**—customize it for your specific use case!

## 🛠 Pro Tips
### Ignore Already Tracked Files
If you accidentally committed files before adding `.gitignore`, remove them from tracking:
```sh
git rm --cached <file>
```

### Use a Global `.gitignore`
Save time by setting up a global ignore file:
```sh
git config --global core.excludesfile ~/.gitignore_global
```
Then copy this `.gitignore` content into `~/.gitignore_global`.

### Check Why a File is Ignored
Run:
```sh
git check-ignore -v <file>
```
This shows which rule is causing the file to be ignored.

## 📜 License
This project is open-source under the **MIT License**. Feel free to use and modify it!

## 🌟 Contribute
Have suggestions? Open a pull request or submit an issue!

### 🔗 Spread the Word
If you found this useful, give it a ⭐ on GitHub and share it with your team!

---
**Let’s keep our repos clean! 🚀**
