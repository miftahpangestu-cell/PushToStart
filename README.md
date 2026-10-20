# PushToStart
Tugas pengenalan GitHub, Git, branching, dan merging
# Membuat branch baru dan berpindah ke branch tersebut
git switch -c belajar-branch

# Membuat perubahan pada README.md,
# kemudian simpan file dan jalankan:
git add README.md
git commit -m "Menambahkan informasi pembelajaran Git"

# Mengunggah branch baru ke GitHub
git push -u origin belajar-branch

# Kembali ke branch utama
git switch main

# Menggabungkan perubahan dari branch baru
git merge belajar-branch

# Mengunggah hasil merge
git push origin main
