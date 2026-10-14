# Kebijakan Privasi Clock Ops

**[Read in English ↓](#clock-ops-privacy-policy)**

Berlaku sejak: 14 Oktober 2026
Terakhir diperbarui: 14 Oktober 2026

Clock Ops adalah aplikasi absensi dan kepegawaian untuk karyawan perusahaan
yang berlangganan Clock Ops. Aplikasi Android-nya terbit di Google Play dengan
nama paket `com.clockops.app`. Clock Ops dikelola oleh **Shopindo** ("kami").

Kebijakan ini menjelaskan data apa yang dikumpulkan aplikasi mobile Clock Ops
dan server yang dipakainya, untuk apa, siapa yang bisa melihatnya, berapa lama
disimpan, dan apa hak Anda. Kebijakan ini disusun mengacu pada Undang-Undang
No. 27 Tahun 2022 tentang Pelindungan Data Pribadi (UU PDP).

## 1. Peran kami dan peran perusahaan Anda

- **Perusahaan tempat Anda bekerja** membuat akun Anda, menentukan aturan
  absensi, dan memasukkan data kepegawaian serta penggajian. Untuk data itu,
  perusahaan Anda adalah **Pengendali Data Pribadi**.
- **Kami** menyediakan aplikasi dan server, dan mengolah data atas perintah
  perusahaan Anda sebagai **Prosesor Data Pribadi**. Untuk data yang kami olah
  demi keamanan layanan, seperti log teknis dan catatan login, kami adalah
  pengendali.
- Permintaan tentang data Anda paling cepat ditangani oleh admin atau HR
  perusahaan Anda. Anda juga boleh menghubungi kami langsung (lihat
  [Kontak](#11-kontak)). Kami akan membantu dan berkoordinasi dengan perusahaan
  Anda.

## 2. Data yang kami kumpulkan

| Data | Kapan dan dari mana | Untuk apa |
|---|---|---|
| **Data akun**: nama, email, nomor HP, kode karyawan, jabatan, departemen, kantor | Dimasukkan perusahaan Anda | Masuk ke aplikasi dan menampilkan profil |
| **Kata sandi** | Dibuat oleh Anda atau admin | Masuk ke aplikasi. Disimpan sebagai *hash* satu arah, sehingga tidak bisa dibaca siapa pun, termasuk kami |
| **Wajah (data biometrik)** | Saat Anda mendaftarkan wajah, dan setiap kali absen masuk atau pulang | Memastikan memang Anda yang absen. Lihat [bagian 3](#3-wajah-dan-lokasi) |
| **Lokasi persis (GPS)** | Hanya saat aplikasi terbuka, dan disimpan hanya ketika Anda absen | Memastikan Anda berada di area kantor. Lihat [bagian 3](#3-wajah-dan-lokasi) |
| **Data perangkat**: ID acak buatan aplikasi, sistem operasi dan versinya, versi aplikasi, alamat IP, waktu login dan aktivitas terakhir | Saat Anda login dan memakai aplikasi | Membatasi satu HP aktif per akun, dan keamanan |
| **Absensi dan pekerjaan**: waktu absen, jadwal, lembur, koreksi absen, pengajuan cuti beserta lampiran yang Anda pilih, catatan | Dari pemakaian aplikasi Anda dan dari perusahaan | Mencatat kehadiran, jadwal, cuti, dan persetujuan atasan |
| **Notifikasi**: token push perangkat dan preferensi notifikasi Anda | Saat Anda mengizinkan notifikasi | Mengirim kabar pengajuan, pengumuman, dan slip gaji |
| **Penggajian**: gaji dan komponennya, slip gaji, rekening bank, NIK, NPWP, tanggal lahir, status pajak | Dimasukkan perusahaan Anda lewat dasbor admin | Penggajian dan pajak oleh perusahaan. Aplikasi menampilkan slip gaji Anda |
| **Log teknis**: waktu, alamat IP, alamat yang diminta, dan peristiwa keamanan seperti login yang gagal | Otomatis oleh server | Menjaga keamanan dan memperbaiki gangguan. Log tidak memuat isi permintaan, kata sandi, token, atau nomor identitas |

UU PDP menggolongkan **data biometrik** (wajah) dan **data keuangan pribadi**
(penggajian) sebagai data pribadi yang bersifat spesifik, dan kami
memperlakukannya dengan perlindungan tambahan.

**Yang tidak kami kumpulkan:** kontak, isi galeri (kecuali file yang Anda pilih
sendiri sebagai lampiran cuti), suara atau mikrofon, lokasi di latar belakang,
ID iklan, data analitik, atau pelacakan lintas aplikasi. Clock Ops tidak berisi
iklan.

**Buka kunci dengan sidik jari atau wajah HP** (opsional) diproses oleh sistem
operasi HP Anda. Aplikasi hanya menerima hasil berhasil atau gagal, tidak
pernah sidik jari atau data wajah dari fitur itu.

## 3. Wajah dan lokasi

### Wajah

- Pendaftaran wajah baru dimulai setelah Anda menyetujuinya di layar
  persetujuan.
- Saat mendaftar dan setiap kali absen, aplikasi mengambil foto dengan kamera
  depan dan mengirimnya ke server lewat koneksi terenkripsi. Server mencocokkan
  foto itu, lalu langsung membuangnya. **Foto wajah tidak disimpan**: tidak di
  HP, tidak di galeri, dan tidak di server.
- Yang disimpan hanya **templat wajah**, yaitu deretan angka yang menggambarkan
  wajah Anda, dalam keadaan terenkripsi (AES-256-GCM). Untuk setiap absen, yang
  disimpan hanya skor kecocokan dan hasil pemeriksaan foto palsu.
- Wajah Anda hanya dipakai untuk mencocokkan absen Anda sendiri. Wajah Anda
  tidak dipakai untuk mengenali orang lain, tidak dipakai melatih model, dan
  tidak dibagikan ke luar perusahaan Anda.
- Anda bisa menarik persetujuan kapan saja dengan meminta atasan atau admin
  menghapus pendaftaran wajah Anda. Templatnya terhapus saat itu juga.

### Lokasi

- Aplikasi membaca lokasi hanya saat terbuka di layar beranda, untuk
  menunjukkan apakah Anda berada di area kantor. Aplikasi tidak meminta izin
  lokasi di latar belakang dan tidak melacak Anda di luar aplikasi.
- Lokasi disimpan hanya saat Anda absen masuk atau pulang, berupa koordinat,
  jarak ke kantor, dan tingkat akurasinya.
- Aplikasi memeriksa apakah lokasi dipalsukan oleh aplikasi lain (*fake GPS*)
  dan menolak absen dari lokasi palsu.

## 4. Untuk apa data dipakai, dan dasar hukumnya

- **Mencatat kehadiran yang sah** dengan wajah dan lokasi. Dasarnya persetujuan
  tegas Anda untuk data wajah, serta pelaksanaan hubungan kerja antara Anda dan
  perusahaan.
- **Jadwal, cuti, lembur, dan persetujuan atasan**, untuk pelaksanaan hubungan
  kerja.
- **Penggajian dan pajak** (slip gaji, PPh 21), untuk pelaksanaan hubungan
  kerja dan kewajiban hukum perusahaan di bidang ketenagakerjaan dan
  perpajakan.
- **Notifikasi dan email**, misalnya kabar pengajuan disetujui, pengumuman,
  slip gaji terbit, dan email reset kata sandi.
- **Keamanan**, yaitu mencegah titip absen, login tanpa izin, dan
  penyalahgunaan. Dasarnya kepentingan yang sah untuk menjaga layanan.

Kami tidak menjual atau menyewakan data Anda, dan tidak memakainya untuk iklan
atau profil pemasaran.

## 5. Siapa yang bisa melihat data Anda

- **Perusahaan Anda**, sesuai peran masing-masing. Atasan melihat absensi,
  jadwal, dan pengajuan timnya. Gaji dan slip gaji hanya dapat dilihat oleh
  Anda sendiri dan admin perusahaan, tidak oleh atasan. Data tiap perusahaan
  dipisahkan, sehingga perusahaan lain tidak bisa melihat data Anda.
- **Penyedia layanan** yang membantu kami menjalankan Clock Ops, masing-masing
  hanya sebatas tugasnya:

  | Penyedia | Tugas | Data yang dilewatkan |
  |---|---|---|
  | Cloudflare, Inc. | Jaringan dan enkripsi koneksi (HTTPS) ke server kami | Lalu lintas antara aplikasi dan server |
  | Expo (650 Industries, Inc.) dan Google Firebase Cloud Messaging (Google LLC) | Mengirim notifikasi push ke HP | Token perangkat, serta judul dan teks singkat notifikasi |
  | Penyedia email (SMTP) | Mengirim email reset kata sandi dan pemberitahuan | Alamat email dan isi email tersebut |
  | Google Play | Mendistribusikan dan memperbarui aplikasi | Diatur oleh kebijakan privasi Google |

- **Pihak berwenang**, hanya jika diwajibkan oleh hukum yang berlaku.

**Lokasi penyimpanan.** Server dan database Clock Ops berada di Indonesia.
Cloudflare, Expo, dan Google dapat memproses data yang lewat di layanan mereka
di luar Indonesia. Kami hanya memakai penyedia yang menerapkan standar
pelindungan data yang diakui secara internasional, sebagaimana disyaratkan UU
PDP untuk transfer data ke luar negeri.

## 6. Keamanan

- Semua koneksi antara aplikasi dan server terenkripsi (HTTPS).
- Templat wajah terenkripsi dengan AES-256-GCM. Kata sandi disimpan sebagai
  *hash* satu arah.
- Token login disimpan di penyimpanan aman HP (Android Keystore), bukan di
  penyimpanan biasa.
- Satu akun hanya aktif di satu HP pada satu waktu. Admin perusahaan dapat
  mencabut akses sebuah HP.
- Slip gaji PDF dapat dilindungi kata sandi jika perusahaan Anda
  mengaktifkannya.
- Data tiap perusahaan dipisahkan di tingkat server. Akses kami ke sistem
  dibatasi dan memakai verifikasi dua langkah.
- Database dicadangkan secara berkala.

Tidak ada sistem yang aman sepenuhnya. Jika terjadi kegagalan pelindungan data
pribadi, kami akan memberi tahu perusahaan Anda dan, bersama perusahaan,
memberi tahu Anda serta lembaga yang berwenang selambat-lambatnya 3 × 24 jam,
sesuai UU PDP.

## 7. Berapa lama data disimpan

| Data | Lama penyimpanan |
|---|---|
| Foto wajah | Tidak disimpan. Dibuang segera setelah dicocokkan |
| Templat wajah | Sampai pendaftaran wajah dihapus, persetujuan ditarik, atau akun perusahaan dihapus |
| Absensi, jadwal, cuti, lembur | Selama perusahaan Anda memakai Clock Ops, atau lebih singkat sesuai kebijakan perusahaan |
| Penggajian dan pajak | Selama diperlukan perusahaan. Undang-undang perpajakan mewajibkan catatan dan dokumen perpajakan disimpan hingga 10 tahun (UU KUP Pasal 28 ayat 11) |
| Token push | Dihapus saat Anda logout, dan dinonaktifkan saat aplikasi dihapus dari HP |
| Log teknis | Sesingkat yang diperlukan untuk keamanan dan perbaikan gangguan |

Jika perusahaan Anda berhenti memakai Clock Ops, data perusahaan itu dihapus
permanen paling lambat 90 hari setelah layanan berakhir atau setelah perusahaan
meminta penghapusan, kecuali perusahaan meminta salinannya lebih dulu. Salinan
di cadangan ikut terhapus saat cadangan tersebut habis masa simpannya.

## 8. Hak Anda

Sesuai UU PDP, Anda berhak:

- mendapat informasi tentang pemrosesan data Anda;
- mengakses dan mendapat salinan data Anda;
- memperbaiki data yang salah atau tidak lengkap;
- meminta penghapusan data Anda;
- menarik persetujuan, termasuk persetujuan pemrosesan wajah;
- menolak atau meminta pembatasan pemrosesan tertentu; dan
- mengajukan keberatan atau keluhan, termasuk kepada lembaga pelindungan data
  pribadi yang berwenang.

**Cara mengajukan:** hubungi admin atau HR perusahaan Anda, atau kirim email ke
**shopindo.tech@gmail.com** dengan subjek "Permintaan Data Clock Ops". Sebutkan
nama Anda, email akun Clock Ops, dan nama atau kode perusahaan Anda. Kami
memverifikasi identitas Anda, berkoordinasi dengan perusahaan Anda, dan
menanggapi paling lambat 3 × 24 jam sejak permintaan diterima.

### Menghapus akun dan data

Akun Clock Ops dibuat dan dikelola oleh perusahaan Anda, jadi tidak ada
pendaftaran mandiri di aplikasi. Untuk menghapus akun dan data Anda:

1. Minta admin atau HR perusahaan Anda, **atau**
2. Kirim email ke **shopindo.tech@gmail.com** dengan subjek "Hapus Akun Clock
   Ops", berisi nama, email akun, dan nama perusahaan Anda.

Templat wajah dihapus segera setelah permintaan terverifikasi. Akun dan data
lainnya dihapus paling lambat 30 hari setelah verifikasi, kecuali data yang
wajib disimpan perusahaan menurut hukum, seperti catatan penggajian dan pajak.
Data tersebut disimpan hanya selama kewajiban itu berlaku, lalu dihapus.

## 9. Izin aplikasi

| Izin | Untuk apa | Jika ditolak |
|---|---|---|
| Kamera | Mendaftarkan wajah dan verifikasi wajah saat absen | Tidak bisa absen lewat aplikasi |
| Lokasi persis dan perkiraan | Memastikan Anda di area kantor saat aplikasi terbuka | Tidak bisa absen lewat aplikasi |
| Biometrik (sidik jari atau wajah HP) | Membuka aplikasi tanpa mengetik ulang kata sandi (opsional) | Masuk dengan kata sandi seperti biasa |
| Notifikasi | Kabar pengajuan, pengumuman, dan slip gaji | Tidak menerima notifikasi |

Semua izin dapat Anda ubah kapan saja di pengaturan HP.

## 10. Anak-anak

Clock Ops ditujukan untuk karyawan berusia 18 tahun ke atas. Kami tidak dengan
sengaja mengumpulkan data anak.

## 11. Kontak

**Shopindo**, pengelola Clock Ops
Email: **shopindo.tech@gmail.com**

## 12. Perubahan kebijakan ini

Kami dapat memperbarui kebijakan ini. Tanggal "Terakhir diperbarui" di atas
akan berubah, dan perubahan penting akan diberitahukan lewat aplikasi atau
perusahaan Anda. Riwayat setiap perubahan dapat dilihat di riwayat *commit*
repositori ini.

---

# Clock Ops Privacy Policy

**[Baca dalam Bahasa Indonesia ↑](#kebijakan-privasi-clock-ops)**

Effective: 14 October 2026
Last updated: 14 October 2026

Clock Ops is an attendance and HR app for employees of companies that subscribe
to Clock Ops. Its Android app is published on Google Play under the package
name `com.clockops.app`. Clock Ops is operated by **Shopindo** ("we").

This policy explains what data the Clock Ops mobile app and its server collect,
why, who can see it, how long it is kept, and what your rights are. It is
written with reference to Indonesia's Personal Data Protection Law, Law No. 27
of 2022 (UU PDP). If the two versions differ, the Indonesian version prevails.

## 1. Our role and your company's role

- **The company you work for** creates your account, sets the attendance rules,
  and enters your employment and payroll data. For that data, your company is
  the **Personal Data Controller**.
- **We** provide the app and the server, and process data on your company's
  instructions as a **Personal Data Processor**. For data we process to keep
  the service secure, such as technical logs and sign-in records, we are the
  controller.
- Requests about your data are handled fastest by your company's admin or HR.
  You may also contact us directly (see [Contact](#11-contact)). We will help
  and coordinate with your company.

## 2. Data we collect

| Data | When and where from | Why |
|---|---|---|
| **Account data**: name, email, phone number, employee code, job title, department, office | Entered by your company | Signing in and showing your profile |
| **Password** | Set by you or an admin | Signing in. Stored as a one-way hash that nobody, including us, can read |
| **Face (biometric data)** | When you enrol your face, and every time you clock in or out | Confirming that it is really you clocking in. See [section 3](#3-face-and-location) |
| **Precise location (GPS)** | Only while the app is open, and stored only when you clock in or out | Confirming that you are at your office. See [section 3](#3-face-and-location) |
| **Device data**: a random ID created by the app, operating system and version, app version, IP address, sign-in and last-activity times | When you sign in and use the app | Limiting each account to one active phone, and security |
| **Attendance and work**: clock-in times, schedules, overtime, attendance corrections, leave requests with any attachment you choose, notes | From your use of the app and from your company | Recording attendance, schedules, leave and manager approvals |
| **Notifications**: the device push token and your notification preferences | When you allow notifications | Sending updates on your requests, announcements and payslips |
| **Payroll**: salary and its components, payslips, bank account, national ID number (NIK), tax ID (NPWP), date of birth, tax status | Entered by your company in the admin dashboard | Payroll and tax by your company. The app shows your payslips |
| **Technical logs**: time, IP address, requested path, and security events such as failed sign-ins | Automatically, by the server | Security and troubleshooting. Logs never contain request contents, passwords, tokens or identity numbers |

UU PDP classifies **biometric data** (your face) and **personal financial
data** (payroll) as specific personal data, and we protect them accordingly.

**What we do not collect:** contacts, your photo gallery (except a file you
choose yourself as a leave attachment), audio or the microphone, background
location, the advertising ID, analytics, or cross-app tracking. Clock Ops
contains no ads.

**Unlocking with your phone's fingerprint or face unlock** (optional) is
handled by your phone's operating system. The app only receives success or
failure, never your fingerprint or face data from that feature.

## 3. Face and location

### Face

- Face enrolment starts only after you agree on the consent screen.
- When you enrol and every time you clock in or out, the app takes a photo
  with the front camera and sends it to the server over an encrypted
  connection. The server compares it and then discards it. **Face photos are
  not stored**: not on the phone, not in the gallery, and not on the server.
- Only a **face template** is kept: a set of numbers describing your face,
  stored encrypted (AES-256-GCM). For each clock-in, only the match score and
  the result of the photo-spoofing check are kept.
- Your face is used only to match your own clock-ins. It is not used to
  identify anyone else, not used to train models, and not shared outside your
  company.
- You can withdraw consent at any time by asking your manager or admin to
  delete your face enrolment. The template is deleted at that moment.

### Location

- The app reads your location only while it is open on the home screen, to
  show whether you are at your office. It does not ask for background location
  and does not track you outside the app.
- Location is stored only when you clock in or out: the coordinates, the
  distance to the office and the accuracy.
- The app checks whether the location is faked by another app ("fake GPS") and
  refuses clock-ins from a faked location.

## 4. How we use data, and the legal basis

- **Recording genuine attendance** with your face and location. The basis is
  your explicit consent for face data, and the performance of your employment
  relationship.
- **Schedules, leave, overtime and manager approvals**, for the performance of
  the employment relationship.
- **Payroll and tax** (payslips, PPh 21 income tax), for the performance of the
  employment relationship and your company's legal obligations under
  employment and tax law.
- **Notifications and email**, for example a request being approved, an
  announcement, a new payslip, or a password-reset email.
- **Security**, meaning preventing buddy punching, unauthorised sign-ins and
  abuse. The basis is the legitimate interest in keeping the service safe.

We do not sell or rent your data, and we do not use it for advertising or
marketing profiles.

## 5. Who can see your data

- **Your company**, according to each person's role. Managers see their team's
  attendance, schedules and requests. Salaries and payslips are visible only to
  you and your company's admins, not to managers. Each company's data is kept
  separate, so other companies cannot see your data.
- **Service providers** that help us run Clock Ops, each limited to its task:

  | Provider | Task | Data passed through |
  |---|---|---|
  | Cloudflare, Inc. | Network and encrypted connection (HTTPS) to our server | Traffic between the app and the server |
  | Expo (650 Industries, Inc.) and Google Firebase Cloud Messaging (Google LLC) | Delivering push notifications | The device token, plus the notification's title and short text |
  | Email (SMTP) provider | Sending password-reset and notice emails | The email address and that email's content |
  | Google Play | Distributing and updating the app | Governed by Google's privacy policy |

- **Authorities**, only where the law requires it.

**Where data is stored.** The Clock Ops server and database are in Indonesia.
Cloudflare, Expo and Google may process data passing through their services
outside Indonesia. We only use providers that apply internationally recognised
data protection standards, as UU PDP requires for transfers abroad.

## 6. Security

- Every connection between the app and the server is encrypted (HTTPS).
- Face templates are encrypted with AES-256-GCM. Passwords are stored as a
  one-way hash.
- Sign-in tokens are kept in the phone's secure storage (Android Keystore), not
  in ordinary storage.
- An account is active on one phone at a time. Your company's admin can revoke
  a phone's access.
- Payslip PDFs can be password-protected if your company turns this on.
- Each company's data is separated on the server. Our own access to the system
  is restricted and uses two-step verification.
- The database is backed up regularly.

No system is perfectly secure. If a personal data breach occurs, we will
inform your company and, together with your company, inform you and the
competent authority within 3 × 24 hours, as UU PDP requires.

## 7. How long data is kept

| Data | Retention |
|---|---|
| Face photos | Not stored. Discarded as soon as they are compared |
| Face template | Until your enrolment is deleted, you withdraw consent, or your company's account is deleted |
| Attendance, schedules, leave, overtime | While your company uses Clock Ops, or shorter under your company's policy |
| Payroll and tax | As long as your company needs it. Indonesian tax law requires tax records and documents to be kept for up to 10 years (UU KUP Article 28(11)) |
| Push tokens | Deleted when you sign out, and disabled when the app is removed from the phone |
| Technical logs | Only as long as needed for security and troubleshooting |

If your company stops using Clock Ops, its data is permanently deleted no
later than 90 days after the service ends or after the company asks for
deletion, unless the company first asks for a copy. Copies in backups are
deleted when those backups expire.

## 8. Your rights

Under UU PDP, you have the right to:

- be informed about how your data is processed;
- access your data and get a copy of it;
- correct data that is wrong or incomplete;
- ask for your data to be deleted;
- withdraw consent, including consent to face processing;
- object to, or ask us to restrict, certain processing; and
- lodge an objection or complaint, including with the competent personal data
  protection authority.

**How to make a request:** contact your company's admin or HR, or email
**shopindo.tech@gmail.com** with the subject "Clock Ops Data Request". Include
your name, your Clock Ops account email, and your company's name or company
code. We verify your identity, coordinate with your company, and respond
within 3 × 24 hours of receiving the request.

### Deleting your account and data

Clock Ops accounts are created and managed by your company, so there is no
self sign-up in the app. To delete your account and data:

1. Ask your company's admin or HR, **or**
2. Email **shopindo.tech@gmail.com** with the subject "Delete Clock Ops
   Account", including your name, account email and company name.

Your face template is deleted as soon as the request is verified. Your account
and other data are deleted within 30 days of verification, except data your
company must keep by law, such as payroll and tax records. That data is kept
only as long as the obligation lasts, then deleted.

## 9. App permissions

| Permission | Why | If you refuse |
|---|---|---|
| Camera | Enrolling your face and verifying it when you clock in | You cannot clock in through the app |
| Precise and approximate location | Confirming you are at your office while the app is open | You cannot clock in through the app |
| Biometrics (phone fingerprint or face unlock) | Opening the app without retyping your password (optional) | You sign in with your password as usual |
| Notifications | Updates on your requests, announcements and payslips | You receive no notifications |

You can change any permission at any time in your phone's settings.

## 10. Children

Clock Ops is meant for employees aged 18 and over. We do not knowingly collect
data from children.

## 11. Contact

**Shopindo**, operator of Clock Ops
Email: **shopindo.tech@gmail.com**

## 12. Changes to this policy

We may update this policy. The "Last updated" date above will change, and
significant changes will be announced in the app or through your company. The
history of every change is visible in this repository's commit history.
