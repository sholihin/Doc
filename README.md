## PERINTAH DASAR LINUX ##

1. Any_command –help: menampilkan bantuan tentang perintah-perintah dasar dari linux debian

2. Ls : berfungsi untuk menampilkan direktori yang aktif. Jadi jika kita terlalu banyak membuka suatu direktori, kita hanya perlu mengetik perintah “ls” yang di ikuti nama direktori yang ingin kita buka pada program root terminal. Maka akan muncul pada layar dengan sendirinya.

3. Ls –al: sama dengan perintah “ls” hanya saja perintah “ls-al” menampilkan seluruh direktori yang aktif satu per satu pada layar.

4. Cd: merupakan singkatan dari change directory yang berfungsi untuk merubah direktori menggunakan cd.

5. Cp : sama dengan fungsi tombol Ctrl+c pada Windows yaitu untuk mengcopy suatu file.

6. mcopy : perintah ini berfungsi untuk mengganti nama suatu file dan juga memindahkan suatu file.

7. rm: yang merupakan singkatan dari remove files yang berfungsi untuk menghapus suatu data atau file.

8. mkdir: berfungsi untuk membuat directory baru, kepajangan dari perintah ini adalah make directory.

9. rm: sama dengan perintah rm files yaitu menghapus, hanya saja rm files menghapus suatu file sedangkan rm directory untuk menghapus suatu directory.

10. rm –r: perintah yang kepanjangan recursive remove yang berfungsi untuk menghapus suatu file, directory, atau subdirectory. Perlu kita tahu untuk berhati-hati menggunakan perintah ini karena perintah ini dapat menghapus semua data pada sistem, dan di Linux tidak ada perintah undelete.

11. more: dengan perintah more kita dapat melihat isi suatu file, dan isi file tersebut dapat di tampilkan layar per layar.

12. Less filename: bergunamenampilkan suatu file layar per layar. Jika kita ingin menghentikan perintah ini tinggal tekan tombol “p” maka akan berhenti.

13. pico filename: perintah ini berfungsi untuk mengedit suatu text file.

14. pico –w filename: sama dengan perintah ” pico filename” yaitu mengedit suatu text file. Hanya saja pada perintah ini di sertai dengan mengnokatifkan fungsi word warp. Dan perintah ini berguna untuk mengedit text file seperti /etc/fstab.

15. lynx file.html: perintah ini berfungsi melihat suatu file html dengan text mode. Perintah ini adalah salah satu cara membuka browser dan juga sesuai untuk mencari artikel tanpa image.

16. tar -zxvf filename.tar.gz: perintah ini digunakan untuk mengekstrak file tar sekaligus mengun-compres file tar tersebut.

17. tar -xvf filename.tar: sama dengan “tar -zxvf filename.tar.gz” yaitu berfungsi untuk mengekstrak suatu file tar tapi ada perintah ini adalah mengekstrak file tar yang tidak terkompress.


18. gunzip filename.gz: berfun gsi intuk meng-uncompress suatu file zip dengan menggunaka gunzip jika kita ingin untuk mengompress file.

19. bunzip2 filename.bz2: perintah ini di gunakan untuk meng-uncompress suatu file yang besar dengan format (*.bz2).

20. find / -name “filename”: jika di Windows terdapat menu search untuk mencari suatu nama file. Maka di Linux ada perintah find / -name “filename” untuk mencari suatu nama file.

21. locate: mencari suatu file berdasarkan nama file tersebut dan di mana lokasi penyimpanan file tersebut.

22. talk: suatu perintah yang berfungsi untuk menjalankan suatu percakapan atau berhubungan dengan computer lain.

23. mc: perintah ini digunakan untuk menjalankan “midnight commander” dengan bagus dan cepat sebagai file manager.

24. telnet : berguna untuk berhubungan dengan computer lain dengan protocol TELNET.

25. rlogin : merupakan singkatan dari remote login yang berfungsi untuk menghubungkan kita dengan computer lain.

26. rsh : kepanjangannya adalah remote shell yang merupakan jalan lain untuk menghubungkan kita dengan remote machine.

27. Clear: perintah ini berfungsi untuk membersihkan layar dari directory yang aktif.


## PERINTAH TAMBAHAN LINUX ##

ls
ls suatu perintah yang di gunakan untuk menampilkan suatu isi dari directory, dan option yang sering di pakai adalah "-l". Untuk lebih jelasnya "man ls".

cd
cd kepanjangan dari change directory yang merupakan suatu perintah di gunakan untuk pindah directory. 

pwd
pwd perintah ini di gunakan untuk mengetahui keberadaan directory yang sekarang kita tempati saja.

touch
touch sering di gunakan oleh para admin untuk menciptakan suatu file tanpa membukanya. Misalnya seperti "vi , nano" dan lain-lain. 

mkdir
mkdir suatu kepanjangan dari make directory sesuai dengan singkatannya perintah ini di gunakan untuk menciptakan suatu directory.

vi
vi digunakan untuk mengedit suatu file dalam mode konsole seperti halnya dengan notepad, hanya saja notepad under grafis.

nano
nano sama saja halnya dengan "vi" hanya saja nano lebih user friendly karena banyak keterangan pada bagian bawah layarnya.

chmod
change modified tentu saja dari singkatannya kita sudah paham dari kegunaan command ini. Command ini sering kali di gunakan merubah suatu perizinan suatu file dan directory. Dalam mode untuk set suatu file dan directory terdapat 2 hal yang harus dipahami yaitu mode :
"chmod ugo /-rwx file/directory"
Dimana :
-ugo adalah user,group dan other
-rwx adalah read,write dan execute
"chmod 421 file/directory"
Dimana :
-421 adalah read, write dan execute
NB : perhatikan posisinya 4 untuk owner, 2 untuk group, 1 untuk other.


chown
change owner ini digunakan untuk merubah suatu kepemilikan suatu file atau directory.

cat
cat digunakan untuk menampilkan suatu isi dari file.

find
find dari namanya saja tentu kita sudah mengerti fungsinnya yaitu untuk mencari suatu file atau directory atau pun mencari suatu kata yang terdapat pada suatu file.

locate
locate kegunaannya hampir sama dengan "find" namun dalam penggunaannya lebih simple.

whereis
whereis salah satu command yang di fungsikan untuk dalam hal pencarian.

rm
remove adalah kepanjangannya yang artinya untuk menghapus namun pada system Linux di gunakan untuk menghapus file atau directory. Berhati-hatilah dalam option "-rf".

mv
move artinya saja sudah memberikan kegunaannya yaitu memindahkan suatu file atau directory.

cp
copy command ini di gunakan untuk menyalin suatu file maupun directory.

ln
link digunakan untuk menciptakan suatu shortcut pada suatu file.

grep
grep di gunakan untuk pencarian suatu kata yang cocok. Command ini sangat di optimalkan oleh para admin dalam hal pengecheckan.

cat /etc/issue
Command di atas di gunakan untuk mengetahui distro apa yang sedang kita gunakan.

visudo
Digunakan untuk mengedit file sudoers.

sudo
Digunakan untuk mengerjakan suatu kegiatan root pada login user biasa.

uname -a
Perintah di atas untuk menampilkan spesifikasi OS dan bit di mesin kita, seperti kernel dan i686.

netstat
Digunakan menampilkan network status seperti melihat service yang berjalan.

du
Digunakan untuk melihat space disk yang sudah di gunakan.

df
Seperti halnya dengan "du", namun perintah ini digunakan untuk melihat sisa space yang kosong.

cat /proc/meminfo
Digunakan untuk melihat spesifikasi memory yang berada pada system tsb.

cat /proc/cpuinfo
Digunakan untuk melihat spesifikasi proccesor pada system tsb.

lsmod
Melihat daftar module apa saja yang ada di system Linux.

lsusb
Melihat daftar device USB yang terpasang.

lspci
Menampilkan daftar device PCI yang terpasang pada system Linux tsb.

dmesg
Menampilkan pesan-pesan pada system Linux gunanya untuk hal analisa trouble shooting.

mount
Mengaktifkan device disk agar device tsb dapat di acces baik hal read maupun write.

umount
Menonaktifkan suatu device agar tidak dapat di acces dalam hal write.

ps
Melihat proses yang sedang berjalan.

top
Melihat proses yang sedang berjalan dalam bentuk prioritas yang saat ini.

fdisk
Menampilkan device disk yang terpasang saat ini.

useradd
Untuk menambah user pada system Linux.

passwd
Untuk memberikan password pada user yang ada di system Linux.

su -
Berfungsi untuk login sebagai super user.

userdel
Gunanya untuk menghapus user yang ada di system.

rpm
Perintah di atas di gunakan untuk menginstall suatu aplikasi base rpm.

tar
Command tsb berguna untuk menguntar suatu paket aplikasi yang di kompres.

gunzip
Perintah tsb di gunakan untuk memekarkan suatu file yang telah di compres dengan extension ".gz".

zip
Dari namanya saja kita bisa menebak bahwa command tsb untuk mengkompres file dengan akhiran ".zip".

more
Menampilkan suatu list layar perlayar.

less
Sama halnya dengan "more" yaitu menampilkan suatu list tanpa seluruhnya namun sepotong-sepotong.

|
Pipe line yang berfungsi menghubungkan perintah satu dengan perintah lainnya.

;
Tanda tsb untuk memisahkan command yang satu dengan yang lainnya ketika ingin menjalankan suatu perintah secara bersamaan.

&&
Tanda tsb berguna untuk meneruskan proses perintah lainnya dengan cara perintah pertama di bawah ke background hal ini di lakukan jika ingin menjalankan perintah dalam waktu bersamaan.

fg
Membawa suatu proses ke mode foreground yang telah di tarik dari background.

bg
Lawannya dengan perintah "fg".

kill
Untuk menghentikan suatu proses yang sedang berjalan.

ifconfig
Digunakan untuk menampilkan IP dan detailnya dan dapat di gunakan juga untuk set IP di dalam memory RAM.

hostname
Untuk melihat nama mesin yang kita gunakan di Linux tsb.

host -t mx [nama-domain]
Untuk melihat server yang menghandle suatu domain email tsb.

host -t ns [nama-domain]
Untuk menampilakan lookup dari domain yang bersangkutan.

nslookup [nama-domain]
Sama halnya dengan perintah lookup sebelumnya

dig [nama-domain]
Sama halnya dengan perintah lookup lainnya hanya berbeda dengan keterangan yang lebih komplex.

iptables
Perintah di atas sering sekali digunakan oleh para admin untuk keamanan jaringan, routing, NAT dll.

ssh
Melakukan remote ke terminal destination pada port 22 sebagai defaultnya.

telnet [nama-domain] [port]
Digunakan untuk remote pada terminal target biasanya telnet ini sering digunakan untuk check suatu port dalam arti sebagai analisa.

/etc/init.d/[nama-service] [action]
Perintah ini di gunakan untuk melihat status, enable, disable, reload suatu service yang bersangkutan.

mysql -u [user] -p
Digunakan untuk masuk ke server mysql dengan menggunakan user tertentu yang telah di beri password.

mysqldump -u [user] -p [nama-db] > [destination-path]
Perintah di atas digunakan untuk backup suatu database ke lokasi tertentu.

mysql -u [user] -p [destination-db] < [source-path]
Perintah tsb digunakan untuk merestore database ke database yang telah tercipta di mysql.

/etc/resolv.conf
File tersebut berisikan IP server DNS yang di jadikan sebagai mesin yang menangani domain.

/etc/hosts
File tsb menyiman nama suatu domain mesin yang bersangkutan.

/etc/network/interfaces atau /etc/network/network-scripts/ifcfg-eth0
File ini begitu penting di karenakan para admin mensetting IP pada file ini, dan sesuaikan interface yang digunakan.

/etc/passwd
File ini berisikan user yang berada pada system, jenis shell, home worknya dll.

/etc/fstab
File ini digunakan pembacaan pemetaan suatu disk di system linux.

/etc/rc.local
File ini adalah file yang berisikan command yang akan di jalankan pertama kali pada saat booting.
history
untuk menampilkan perintah terakhir

traceroute
untuk trace host-host yang dilewati dalam mencapai host tujuan

alias
Untuk membuat alias dan menampilkan alias yang sudah diset sebelumnya. 

cal 
untuk menampilkan kalender

du
Menampilkan penggunaan kapasitas harddisk oleh suatu direktori.

grep
Untuk mencari suatu “string” atau “pattern” tertentu pada suatu file. 

head
Secara default menampilkan 10 baris pertama pada suatu file. Jika ingin menampilkan jumlah baris yang berbeda dapat menggunakan option -n diikuti jumlah baris yang diinginkan

init
Untuk mengganti run level. Note: Karena penggunaan run level adalah hal yang berpengaruh besar pada sistem, maka untuk melakukan ini harus menggunakan SUPER-USER atau yang memiliki kemampuan sama dengan root

tail
Secara default menampilkan 10 baris terakhir pada suatu file. Jika ingin menampilkan jumlah baris yang berbeda dapat menggunakan option -n diikuti jumlah baris yang diinginkan

tac
untuk menampilkan isi file dari akhir, kebalikan cat

pg
temannya more, less
alias
membuat nama lain dari suatu perintah
perintah favorit W : alias d='dmesg|tail'
alias ll='ls -la'
alias fl='sudo fdisk -l'
alias enw='emacs --no-window' many more
biar lebih mantap patenkan di $HOME/.bashrc (ubuntu) atau di .bash_profile(fedora)
arch
melihat arsitektur komputer
eject
bukan buat mengejek ya,, buat ngeluarin cdrom
split
untuk membagi file

Dan Ini Nisan dapat yang sudah di kelompokan berdasarkan urutan abjad :


a
adduser = Tambah pengguna ke sistem
addgroup = Tambah grup ke sistem
alias = Buat sebuah alias
apropos = Cari Bantuan halaman manual (man-k)
apt-get = Cari dan menginstal paket perangkat lunak (Debian)
aspell = Pemeriksa Ejaan
awk = Cari dan Ganti teks, database sort / validate / index

b
basename = Strip direktori dan akhiran dari nama file
bash = GNU Bourne-Again Shell
bc = Arbitrary bahasa kalkulator presisi
bg = Kirim ke latar belakang
break = Keluar dari sebuah loop
builtin = Jalankan shell builtin
bzip2 = Compress atau dekompresi file bernama (s)

c
cal = Tampilkan kalender
case = kondisional melakukan perintah
cat = Menampilkan isi file
cd = Mengganti Directori
cfdisk = Tabel partisi manipulator untuk Linux
chgrp = Mengubah kepemilikan grup
chmod = Mengubah izin akses
chown = Mengubah pemilik file dan grup
chroot = Jalankan perintah dengan direktori root yang berbeda
chkconfig = Sistem layanan (runlevel)
cksum = Cetak byte CRC checksum dan menghitung
clear = Hapus layar terminal
cmp = Membandingkan dua file
comm = Bandingkan dua file diurutkan baris demi baris
command = Jalankan perintah – shell mengabaikan fungsi
continue = Resume iterasi berikutnya dari suatu loop
cp = Menyalin satu atau lebih file ke lokasi lain
cron = Daemon menjalankan perintah yang dijadwalkan
crontab = Jadwalkan perintah untuk menjalankan di lain waktu
csplit = Split file ke dalam konteks – potongan ditentukan
cut = membagi file menjadi beberapa bagian

d
date = Menampilkan atau mengubah tanggal & waktu
dc = Desk Kalkulator
dd = Mengkonversi dan menyalin file, menulis header disk, boot record
ddrescue = Alat untuk memperbaiki data
declare = Deklarasikan variabel dan memberi mereka atribut
df = Tampilkan ruang disk
diff = Tampilkan perbedaan antara dua file
diff3 = Tampilkan perbedaan di antara tiga file
menggali = DNS lookup
dir = Daftar isi direktori singkat
dircolors = Warna setup untuk `ls ‘
dirname = Convert semua pathname ke beberapa path
dirs = Tampilkan daftar direktori yang diingat
dmesg = Mencetak pesan-pesan kernel & driver
du = Perkiraan penggunaan kapasitas file

e
echo = Tampilkan pesan di layar
egrep = Cari file untuk baris yang sesuai dengan ekspresi yang diperpanjang
eject = Mengeluarkan media removable
enable = Mengaktifkan dan menonaktifkan perintah shell builtin
env = Environment variabel
ethtool = Pengaturan kartu Ethernet
eval = Evaluasi beberapa perintah / argumen
exec = Menjalankan perintah
exit = Keluar dari shell
expect = mengotomatiskan aplikasi yang bebas diakses melalui terminal
expand = Convert tab ke spasi
eksport = Set variabel lingkungan
expr = Evaluasi ekspresi

f
false = Tidak melakukan apa-apa, tidak berhasil
fdformat = Tingkat rendah format sebuah floppy disk
fdisk = tabel partisi manipulator untuk Linux
fg = Kirim pekerjaan untuk foreground
fgrep = Cari file untuk baris yang cocok dengan string yang tetap
file = Tentukan jenis file
find = Cari file yang memenuhi kriteria yang diinginkan
fmt = Format ulang tipe teks
fold = Wrap teks agar sesuai dengan lebar tertentu.
for = Memperluas kata-kata, dan menjalankan perintah
format = Format disk atau kaset
free = Tampilkan penggunaan memori
fsck = Memeriksa dan memperbaiki sistem File konsistensi
ftp = File Transfer Protocol
fungsi =  Tentukan fungsi macro
fuser = Identifikasi / memutuskan proses yang sedang mengakses file

g
gawk = Cari dan Ganti teks dalam file
getopts = Menguraikan parameter sesuai posisi
grep = Cari file untuk baris yang cocok dengan pola tertentu
group = Cetak nama grup pada pengguna
gzip = Compress atau dekompresi nama file

h
hash = Mengingat  seluruh pathname dari sebuah nama argumen
head = Output bagian pertama dari file
help = Tampilkan bantuan untuk perintah built-in
history = Perintah history
hostname = Cetak atau mengatur nama sistem

i
id = Cetak user dan grup id
if = melakukan perintah kondisional
ifconfig = Konfigurasi antarmuka jaringan
ifdown = Menghentikan antarmuka jaringan
ifup = Memulai antarmuka jaringan keatas
import = Menangkap layar server  X dan menyimpan sebuah gambar ke file
install = Menyalin file dan mengatur atribut

j
join = gabung garis pada field umum

k
kill = Memberhentikan proses yang sedang berjalan
killall = Memberhentikan proses oleh nama

l
less = Tampilan output satu layar pada satu waktu
let = Melakukan aritmatika pada variabel shell
ln = Membuat hubungan antara file
local = Membuat variabel
locate = Cari file
logname = Cetak nama login
logout = Keluar dari sebuah login shell
look = Tampilan baris yang dimulai dengan string tertentu
lpc = Program Kontrol  jalur printer
lpr = Off line print
lprint = Mencetak  file / Print file
lprintd = Abort pekerjaan print
lprintq = Daftar antrian print
lprm = Hapus pekerjaan dari antrian print
ls = List informasi tentang file
lsof  = List membuka file

m
make = Sekelompok Kompilasi ulang dari program
man = Bantuan manual
mkdir = Membuat folder baru
mkfifo = Membuat FIFOs (bernama pipa)
mkisofs = Buat hybrid ISO9660/JOLIET/HFS filesystem
mknod = Membuat blok atau karakter file khusus
more = Tampilan output satu layar pada satu waktu
mount  = Mount  file system
mtools = Memanipulasi file MS-DOS
mv = Memindahkan atau mengubah nama file atau direktori
mmv = Pindahkan massa dan mengubah nama (file)

n
netstat = Informasi Jaringan
nice = Mengatur prioritas perintah atau pekerjaan
nl = Nomor baris dan menulis file
nohup = Jalankan perintah kebal terhadap hangups
nslookup = Query Internet menyebut server secara interaktip

o
open = membuka file dalam aplikasi default
op = Operator akses

p
passwd Memodifikasi password user
paste = Menggabungkan baris file
pathchk  = Periksa nama file portabilitas
ping = Test sambungan jaringan
pkill = memberhentikan proses running
popd = Mengembalikan nilai sebelumnya dari direktori sekarang
pr  = Siapkan file untuk dicetak /print
printcap = kemampuan pencetak Database
printenv = Cetak variabel lingkungan
printf  = Format dan mencetak data
ps = Status Proses
pushd = Simpan dan kemudian mengubah direktori sekarang
pwd = Cetak direktori kerja

q
quota = Tampikan penggunaan disk dan membatasinya
quotacheck  = Meneliti sistem file untuk penggunaan disk
quotactl = Set kuota disk

r
ram =  perangkat disk ram
rcp = Salin file antara dua mesin
read = Membaca baris dari standar input
readarray = Baca dari stdin ke variabel array
readonly  = Menandai variabel / fungsi sebagai readonly
reboot = Reboot sistem
rename = Ubah nama file
renice = Ubah prioritas dari proses yang berjalan
remsync = Sinkronisasi remote file melalui email
return = Keluar fungsi shell
rev = Membalikkan baris dari sebuah file
rm = Menghapus file
rmdir = Remove folder
rsync = Remote file copy (Synchronize file pohon)

s
screen = Multiplex terminal, run remote shells via ssh
scp = Secure copy (remote file copy)
sdiff  = Menggabungkan dua file secara interaktif
sed = Stream Editor
select = Menerima input keyboard
seq = Print urutan numeric
set = Memanipulasi variabel shell dan fungsi
sftp = Secure File Transfer Program
shift = Pergeseran parameter posisi
shopt = Pilihan shell
shutdown = Shutdown atau restart linux
sleep = Delay/penundaan untuk jangka waktu tertentu
slocate = Cari file
sort = Mengurutkan file teks
source = Jalankan perintah dari file `.”
split = Split file ke dalam fixed-potong
ssh = Secure Shell client (remote login program)
strace = Trace sistem panggilan dan sinyal
su = Gantikan identitas pengguna
sudo = Jalankan perintah sebagai user lain
sum = Mencetak checksum untuk file
symlink  = Buatlah nama baru untuk file
sync = Sinkronisasi data pada disk dengan memori

t
tail = Output bagian terakhir file
tar = Tape Archiver
tee = Redirect output ke beberapa file
test = Evaluasi ekspresi kondisional
time = Program Mengukur waktu running
times = User dan sistem waktu
touch = Ubah file timestamps
top = Daftar proses yang berjalan pada sistem
traceroute = Trace Route to Host
trap = Jalankan perintah ketika sebuah sinyal adalah set (Bourne)
tr = Translate, squeeze, dan / atau menghapus karakter
true = Tidak melakukan apapun, berhasil
tsort = Topologi sort
tty = Print filename dari terminal pada stdin
type = menjelaskan perintah

u
ulimit  = Batasi pengguna resources (sumber daya)
umask = Para pengguna menciptakan file tersembunyi
umount = Unmount (tidak menaiki) perangkat
unalias = Hapus alias
uname = Informasi sistem print
unexpand = Convert spasi untuk tab
Uniq = Uniquify file
unit = Mengkonversi unit dari satu skala ke yang lain
unset = Hapus variabel atau nama fungsi
unshar = Uraikan catatan arsip shell
until = Mengeksekusi perintah (sampai error)
useradd = Membuat akun user baru
usermod = Memodifikasi  akun user
users = Daftar para pengguna yang sekarang ini login
uuencode = Encode file biner
uudecode = Decode file yang dibuat oleh uuencode

v
v = Daftar isi direktori Verbosely ( `ls-l-b ‘)
vdir = Daftar isi direktori Verbosely ( `ls-l-b ‘)
vi = Text Editor
vmstat = Laporan statistik memori virtual

w
watch = Mengeksekusi / menampilkan sebuah program secara berkala
wc = Cetak byte, kata, dan baris menghitung
whereis = Cari pengguna $ path, halaman manual dan file source untuk program
which = Cari pengguna $ path untuk file program
while = Jalankan perintah
who = Cetak semua nama pengguna yang sedang log in
whoami = Cetak pengguna saat ini dan nama id ( `id-un ‘)
wget = Ambil halaman web atau file melalui HTTP, HTTPS atau FTP
write = Mengirim pesan ke pengguna lain
x
xargs = Jalankan utility, melewati daftar argumen yang dibangun

y
yes = Cetak string sampai di interrupt
