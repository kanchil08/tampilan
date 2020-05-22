# Name : Tegar Sabila
# Author : ./Kanchil-ID

r="\033[1;31m"
g="\033[1;32m"
y="\033[1;33m"
pur="\033[1;34m"
p="\033[1;35m"
c="\033[1;36m"
w="\033[1;37m"
hari=`date +%A`
tanggal=`date +%d`
bulan=`date +%B`
tahun=`date +%Y`
waktu=`date +%T`
zona=`date +%Z`
clear
figlet -f slant "Kali-Linux" | lolcat
cowsay -f milk "MilkChoco" | lolcat
echo -e "${y}Nama:${g}Tegar Sabila\n${y}Sekolah :${g}SMK KOMPUTER INDONESIA\n${y}Alamat :${g}Bogor\n${y}WhatsApp :${g}082125068665\n${y}Instagram :${g}@Kanchil_Gans08\n\n${g}[${w} ZONA WAKTU ${g}]${y}═══🌍═══${g}[${c} $zona${g} ]${y}\n${g}[${w} HARI ${g}]${y}═══🌖═══${g}[ ${c}$hari ${g}]\n${g}[ ${w}JAM${g} ]${y}══🕛══${g}[${c} $waktu ${g}] \n${g}[${w} TANGGAL ${g}]${y}══📆══${g}[${w} BULAN ${g}]${y}═══📆═══${g}[${w} TAHUN ${g}]\n${g}[${w} $tanggal ${g}]${y}═══📆═══${g}[${w} $bulan ${g}]${y}══📆══${g}[${w} $tahun ${g}]\n${g}<${y}════════════════════════════════════════════════${g}>"
export PS1='\n\n\[\033[1;32m\][\[\033[1;35m\]$hari\[\033[1;32m\]]\[\033[1;32m\][\[\033[1;35m\]$waktu\[\033[1;32m\]]\[\033[1;32m\][\[\033[1;35m\]$tanggal $bulan $tahun\[\033[1;32m\]]\n\[\033[1;33m\]@\[\033[1;31m\]TegarSabila\[\033[1;36m\]@\[\033[1;32m\]Linux\[\033[1;32m\]\[\033[1;33m\]~\[\033[1;35m\]${PWD/*\//}\[\033[1;32m\]•\[\033[1;33m\]>\[\033[1;37m\] '
