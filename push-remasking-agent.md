// buat bikin branch
git branch remasking-agent

// buat pindah branch
git checkout remasking-agent

git push origin remasking-agent
git pull origin remasking-agent

// buat liat all branch
git branch -a
  master
* remasking-agent
  remotes/origin/HEAD -> origin/master
  remotes/origin/campaign
  remotes/origin/implement-flywaydb
  remotes/origin/implement-role-permission
  remotes/origin/master
  remotes/origin/remasking-agent

// buat pindah ke branch lain atau Switched Branch dari remote lain
git checkout -b campaign remotes/origin/campaign

// buat liat branch
git branch

// buat gabungin branch
git checkout master // posisi harus di branch master agar bisa pull dari master
git pull origin master // pull yg terbaru
git checkout remasking-agent // posisi harus di branch lain dulu buat tes error, sebelum di gabung dengan branch master
git merge --no-ff master // menggabungkan data dari branch master ke branch remasking-agent
// kalo udah fix bisa berjalan baik bisa pindah ke branch master lalu di merge
git merge --no-ff remasking-agent // branch lain sudah final tes dan oke lalu di gabung di branch master
