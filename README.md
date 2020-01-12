# efi-catalina

EFI partition MacOSX Catalina for Asus X45C - www.firstplato.com - <a href="https://github.com/ipang-dwi/efi-mojave/wiki" target="_blank">Dokumentasi Lengkapnya</a>

<img src="https://raw.githubusercontent.com/ipang-dwi/efi-catalina/master/img/1.png" />

> Membelai Neng Lina bersama dengan Asus X45C.

- MacOSX : Catalina
- Version : 10.14.1 Build 19A583
- Clover : v2.5k r5096+ 

Tested on Asus X45C
- Device : Asus X45C
- Brand : Asus
- Type : X45C
- Bios : AMI - American Megatrends International, Aptio V
- Bios Version : 208

Specs :
- Procie : Intel Core i3-2350M 2.3GHz
- VGA : Intel HD3000
- HDD : Toshiba 500GB SATA2 5400RPM, replace with SSD Avexir 120GB SATA3
- ODD : Panasonic DVD-RW SATA2, replace with HDD HGST 1TB 7200RPM and HDD Caddy mod
- RAM : Micron 2GB DDR3 1333, extend with Samsung 8GB DDR3L 1600
- Additional : USB Mouse Rexus Xierra X3

<img src="https://raw.githubusercontent.com/ipang-dwi/efi-catalina/master/img/2.png" />

Perfect work :
- VGA : Intel HD3000, patch based High Sierra 10.13.6 dari om chris111, optimasi karya om dosdude. Update Intel HD 3000 VRAM 2GB by me, patchnya <a href="https://github.com/ipang-dwi/ihd3000">di sini</a>.
- Audio : latest VoodooHDA.
- Camera / USB 2.0 Asus Webcam : latest USBInjectAll.kext by Rehabman.
- LAN Realtek RTL8411 : RealtekRTL8111.kext by Rehabman.
- Wifi Atheros 9485 : patch IO80211Family.kext dari Muhammad Arif Isnaini, Forum Hackintosh Indonesia. Tested totally full speed.
- RAM Dual Channel : native tanpa kext, 2GB DDR3 1333 + 8GB DDR3 1600, clockspeed yang dipakai yang 1333. Menyesuaikan clockspeed terendah dari kedua RAM.
- Baterai, termasuk indikatornya, shutdown, restart, sleep/hibernate : patch manual referensi dari om Rehabman + latest ACPIBatteryManager.kext.
- Tombol Fn, bekerja normal semua, hanya buat Brightness UP and Down yang gak bisa.
- Brightness : latest SSDT-PNLF.aml dari om Rehabman, work pakai slider dan Tombol F5 - F6, di-remapping pada keyboard shortcut di System Preferences.
- USB Mouse 7D : Aplikasi SensibleSideButtons dari om Alexei Baboulevitch, tested lancar jaya USB Mouse Rexus Xierra X3.

<img src="https://raw.githubusercontent.com/ipang-dwi/efi-catalina/master/img/3.png" />

Didn't work :
- Realtek card reader, sudah hukum alam.

Running Apps on Screenshot :
- Apple terminal
- <a href="https://github.com/dylanaraps/neofetch" target="blank">neofetch</a>
- <a href="http://www.figlet.org/" target="blank">figlet</a>
- <a href="https://www.videolan.org/vlc/index.html" target="blank">VLC</a>

Installed Apps :
- <a href="http://cvad-mac.narod.ru/index/0-4" target="blank">Kext Utility</a>
- <a href="https://sourceforge.net/projects/cloverefiboot/" target="blank">Clover Theme Manager</a>
- <a href="https://sourceforge.net/projects/cloverefiboot/" target="blank">Clover Configurator</a>
- <a href="https://sourceforge.net/projects/dpcimanager/" target="blank">DPCI Manager</a>
- <a href="https://bitbucket.org/RehabMan/os-x-maciasl-patchmatic/src" target="blank">MaciASL-patchmatic</a>
- <a href="https://www.fatcatsoftware.com/plisteditpro/" target="blank">PlistEdit</a>
- <a href="https://sensible-side-buttons.archagon.net" target="blank">SensibleSideButton</a>
- <a href="https://www.google.com/chrome/" target="blank">Google Chrome</a>
- <a href="https://keep.google.com/" target="blank">Google Keep</a>
- <a href="http://xdman.sourceforge.net/" target="blank">XDM</a>
- <a href="https://sourceforge.net/projects/xchm/" target="blank">xCHM</a>
- <a href="https://www.videolan.org/vlc/index.html" target="blank">VLC</a>
- <a href="https://www.sublimetext.com/" target="blank">SublimeText</a>
- <a href="https://code.visualstudio.com/" target="blank">VSCode</a>
- <a href="https://brew.sh/" target="blank">Brew</a>
- <a href="https://git-scm.com/" target="blank">git</a>
- <a href="https://cmus.github.io/" target="blank">cmus</a> 
- <a href="https://github.com/dylanaraps/neofetch" target="blank">Neofetch</a>
- <a href="http://www.figlet.org/" target="blank">Figlet</a>
- <a href="https://desktop.github.com/" target="blank">Github Desktop</a>
- <a href="https://www.keka.io/en/" target="blank">Keka Archiver</a>
- <a href="https://www.teamviewer.com/en-us/download/mac-os/" target="blank">Team Viewer</a>
- <a href="https://www.android.com/filetransfer/" target="blank">Android File Transfer</a>

Deleted Apps :
Almost all unneeded apps bawaan installer. :)

Bagi yang ingin mencoba install, mungkin memiliki Laptop/PC dengan spesifikasi yang hampir sama, bisa baca <a href="https://github.com/ipang-dwi/efi-high-sierra/wiki" target="blank">di sini</a>. Sudah disertai link koleksi Vanilla DMG + Clover, direct access.

Akhir kata, terima kasih kepada semua pihak, baik yang sudah maupun belum atau lupa saya sebutkan. Terutama teman-teman di grup FB Forum Hackintosh Indonesia. Jika ada yang butuh bantuan patch DSDT atau sharing, bisa contact saya.

Feel free to reach me on :
- https://www.firstplato.com
- https://www.facebook.com/firstplato
- admin@firstplato.com
- WA o856 48587 856

Logs :
- 23.10.2019 tested on 10.15.1
- Still waiting for stable release of MacOSX Catalina
- Update plan to 10.15.2
