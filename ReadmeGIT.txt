https://github.com/ombabas/testgit.git




git config --global user.name "ombabas"

git config --global user.email ombabas@yahoo.com

git clone https://github.com/ombabas/testgit.git


How to Install GIT
01. Browser: Open https://git-scm.com/ --> Download --> Download for Windows

02. Install Git-2.11.0.3-64-bit.exe --> GitBash --> Pilih Git and optional unix tools from Windows common prompt

33. Browser: Open https://github.com/
    a1. Create GitHub Account --> SignUp
    b1: Login GitHub Account --> Create New Repository

04: Open Windows Explorer --> Create New Folder for GIT

05: Open GitBash
	- Cd /C : pindah ke folder C:\
	- ls	: list file
	- cd ..	: masuk ke folder ..

06: Browser: GitHub
    a: Click tombol Clone or Download --> Copy link: https://github.com/ombabas/TestGitAndro.git

07: GitBash: 
    a1: Configure Git Account untuk GitHub Repository
    b2: Configure User Name:		Ketik/Enter: git config --global user.name "ombabas"
    b3: Configure Email Id:		Ketik/Enter: git config --global user.email ombabas@yahoo.com
    b4: Masuk ke folder Git
    b5: Configure Clone Repository:	Ketik/Enter: git clone https://github.com/ombabas/TestGitAndro.git

08: Windows Explorer: Cek di folder Git, folder TestGitAndro sudah terbentuk

09: Windows Explorer: 	Create file di dalam folder Git

10:GitBash:
    a: Cek file: 	ls
    b: Upload File:	git add filename.ext
    c: Cek Status:	git status
    d: Commit:		git commit -m SWAP.iml
    e: Transfer ke GitHub Account:	git push -u origin master
       (Untuk pertama kali login dulu)

    f: Push hanya bisa dilakukan apabila tidak ada perubahan di GitHub.
       Lakukan git pull apabila ada perubahan

11: Browser: GitHub
    Apabila berhasil melakukan git push, refresh window maka file yang dipush akan tampil di GitHub

12: Editor Vi:
    a: Keluar tanpa disimpan :q!
    b: Edit                  -i