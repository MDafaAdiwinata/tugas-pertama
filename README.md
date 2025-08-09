# TUGAS PERTAMA - GIT (Perintah Git yang sering digunakan)

__Mencacat Source Code Perintah Git__

git init                    # Inisialisasi repositori baru
git clone <url>             # Menyalin atau mengcopy repositori dari project lain
git status                  # Menampilkan status perubahan file/repo
git add <file>              # Menambahkan file ke staging area
git add .                   # Menambahkan semua perubahan ke staging area
git commit -m "pesan"       # commit perubahan dengan pesan
git log                     # Melihat riwayat commit
git diff                    # Melihat perbedaan perubahan lokal
git branch                  # Menampilkan daftar branch saat ini
git branch <nama-branch>    # Membuat branch baru
git checkout <nama-branch>  # Berpindah ke branch lain
git merge <nama-branch>     # Menggabungkan branch ke branch aktif
git pull                    # Menarik perubahan terbaru dari remote
git push                    # Mengirimkan commit lokal ke remote
git remote -v               # Melihat remote repository yang terhubung
git reset                   # Membatalkan perubahan (commit, staging)
git rm <file>               # Menghapus file dari repository