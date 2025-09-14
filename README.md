# Tugas-1_Avila-Davin-Parela-6162001083
# Instruksi bikin bash dan bikin repository baru!
Bash 
• git config --global user.name "yourname" 
• git config --global user.email "youremail@mail.com" (harus sama dengan email yang terdaftar di GitHub) 
• ssh-keygen -t ed25519 -C "youremail@mail.com" 
• SSH key tersimpan di C:\Users \<username>\.ssh\id ed25519.pub GitHub 
• Klik Profile Picture >Settings 
• SSH and GPG keys >New SSH key 
• Paste semua isi file id ed25519.pub ke bagian Key >Add SSH key Check di bash 
• ssh -T git@github.com
• Ketik yes Buat repository di GitHub
• Clone repository: git clone git@github.com:username/reponame.git 
• Pull: git pull origin main 
• Buka folder repository di Visual Studio Code dan buat file baru 
• Menambahkan file ke staging area: git add filename atau git add . 
• Commit: git commit -m "message" 
• Push: git push origin main
