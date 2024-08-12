# Chocolatey
Chocolatey and winget commands to automate and faster package management.

Chocolatey commands Repo - by Kayash

*************
Installation:
*************

Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))

choco feature enable -n=allowGlobalConfirmation

*************
Install winget from PowerShell
https://bit.ly/winget-install
If you just need to run the basic script without any parameters, you can use the following one-line command:
irm asheroto.com/winget | iex


AnyDesk MSI (Install)
choco install anydesk.install

Win 11 normal w/o Thunderbird:
choco install winaero-tweaker googlechrome ublockorigin-chrome grammarly-chrome fireshot-chrome firefox zoom sumatrapdf 7zip notepadplusplus dotnetfx skype adobereader speccy bitwarden choco-cleaner

Win 10 normal 2023:
choco install winaero-tweaker googlechrome ublockorigin-chrome grammarly-chrome fireshot-chrome firefox thunderbird  sumatrapdf 7zip notepadplusplus microsoft-teams adobereader mpc-be speccy bitwarden choco-cleaner 

Win 10 normal 2024:
choco install winaero-tweaker googlechrome ublockorigin-chrome grammarly-chrome fireshot-chrome firefox thunderbird  sumatrapdf 7zip notepadplusplus microsoft-teams adobereader mpc-be speccy bitwarden choco-cleaner --ignore-checksums

Win 10 normal:
choco install winaero-tweaker googlechrome ublockorigin-chrome grammarly-chrome fireshot-chrome firefox thunderbird zoom sumatrapdf 7zip notepadplusplus dotnetfx skype microsoft-teams adobereader mpc-be speccy bitwarden choco-cleaner

Ublock Origin
https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/
https://microsoftedge.microsoft.com/addons/detail/ublock-origin/odfafepnkmbhccpbejgmiehpchacaeak

Bitwarden
https://microsoftedge.microsoft.com/addons/detail/bitwarden-free-password/jbkfoedolllekgbhcbcoahefnbanhhlh
https://chrome.google.com/webstore/detail/bitwarden-free-password-m/nngceckbapebfimnlniiiahkandclblb?hl=en

Extensity
https://chrome.google.com/webstore/detail/extensity/jjmflmamggggndanpgfnpelongoepncg

DownThemAll
https://microsoftedge.microsoft.com/addons/detail/downthemall/kenmkleahlilpehjignjigpdhciknmdf
winget install -e --id Piriform.Speccy

Win 10 Normal w/o Thunderbird:
choco install winaero-tweaker googlechrome ublockorigin-chrome grammarly-chrome fireshot-chrome firefox microsoft-edge zoom sumatrapdf 7zip notepadplusplus dotnetfx skype microsoft-teams.install adobereader mpc-be speccy bitwarden choco-cleaner

Developer Profile extras:
choco install winmerge brave filebot eclipse-java-oxygen postman vscode jdk8

Windows 7 normal:
choco install googlechrome ublockorigin-chrome grammarly-chrome fireshot-chrome chocolatey-core.extension firefox  thunderbird microsoft-edge zoom sumatrapdf 7zip notepadplusplus vlc dotnetfx skype mozbackup microsoft-teams.install mpc-be speccy brave adobereader wincdemu pdfcreator choco-cleaner


Backoffice:
choco install anydesk.install
choco install winaero-tweaker googlechrome ublockorigin-chrome grammarly-chrome fireshot-chrome chocolatey-core.extension firefox javaruntime thunderbird microsoft-edge 7zip notepadplusplus vlc dotnetfx skype mozbackup microsoft-teams.install adobereader speccy openvpn roboform choco-cleaner
choco install office365business

https://microsoftedge.microsoft.com/addons/detail/roboform-password-manager/ljfpcifpgbbchoddpjefaipoiigpdmag
https://addons.mozilla.org/firefox/downloads/file/3719125/lastpass_password_manager-4.64.0.3-an+fx.xpi

Developer
choco install logexpert visualstudio2019community git sourcetree  mssqlserver2014express mssqlservermanagementstudio2014express winmerge vscode
adobe illustrator
adobe photoshop

choco install winaero-tweaker googlechrome ublockorigin-chrome grammarly-chrome fireshot-chrome firefox javaruntime thunderbird microsoft-edge zoom 7zip microsoft-teams.install adobereader mpc-be speccy bitwarden choco-cleaner

choco upgrade all
choco upgrade all --noop
choco upgrade all -y

Winaero Tweaker (Install)
choco install winaero-tweaker.install --ignore-checksums


HP Support Assistant
choco install hpsupportassistant

choco install choco-cleaner

choco install microsoft-teams

choco install microsoft-teams.install

choco list --local-only

choco install winaero-tweaker

choco install googlechrome

choco install ublockorigin-chrome

choco install lastpass-chrome

choco install grammarly-chrome

choco install fireshot-chrome

choco install grammarly

choco install chocolatey-core.extension

choco install firefox

choco install 7zip

choco install notepadplusplus

choco install adobereader

choco install skype

choco install teamviewer

choco install anydesk.install

choco install mozbackup

choco install javaruntime

choco install treesizefree

choco install thunderbird

choco install dropbox

choco install microsoft-edge

choco install zoom

choco install sumatrapdf

choco install googledrive

choco install telegram

choco install telegram.install

choco install whatsapp

choco install speccy --ignore-checksums

choco install imageresizerapp

choco install mpc-be

choco install wincdemu

choco install --ignore-checksums mp3skyperecorder

choco install autoruns

choco install duplicati

choco install openshot		Open Source Video Editor

choco install bitwarden		Bitwarden

choco install bitwarden-edge

choco install bitwarden-chrome



choco install adwcleaner

choco install nvidia-display-driver

choco install calibre

choco install openoffice

choco install dellcommandupdate

choco install winmerge

choco install totalcommander

choco install openvpn

choco install tortoisesvn

choco install evernote

choco install crystaldiskinfo

choco install crystaldiskmark

choco install rufus

choco install docker-desktop

choco install cpu-z

choco install r.studio

choco install mysql

choco install brave

choco install androidstudio

choco install mkvtoolnix

choco install f.lux

choco install coretemp

choco install lenovo-thinkvantage-system-update		Lenovo System Update

choco install dell-update		Dell Update Application for Windows 10

choco install partitionwizard

choco install pdfsam

choco install oldcalc

choco install yumi

choco install kodi

choco install vscode

choco install smartftp

choco install windows-10-update-assistant

choco install filezilla

choco install shutup10

choco install filebot

choco install windowsrepair

choco install goodsync

choco install wudt	Windows USB/DVD Download Tool 1.0.30.20180515

choco install usbit

choco install folder_size

choco install glasswire

choco install bluescreenview

choco install logexpert

choco install ccleaner

choco install teamviewer-qs

choco install vlc

choco install autohotkey

choco install office365business

https://admin.microsoft.com/OLS/MySoftware.aspx

choco install virtualbox

choco install procexp

choco install opera

choco install wsus-offline-update

choco install jdk8

choco install jdk11

choco install chocolateyGUI

choco install driverpacksolution

choco install drivermax

choco install tapwindows

choco install pdfcreator

choco install sql-server-management-studio

choco install youtube-dl

choco install ffmpeg

choco install videoder

choco install puppet-agent

choco install calibre

choco install slack

choco install dotnetfx

choco install visualstudio2019community

choco install git

choco install tortoisegit

choco install sourcetree

choco install roboform

choco install partitionwizard

choco install outlookviewer

choco install mssqlserver2014express

choco install mssqlservermanagementstudio2014express


HP BIOS Configuration Utility (BCU)
choco install hpbcu
choco install imageresizerapp
choco install choco-upgrade-all-at-startup
choco install choco-upgrade-all-at

choco install powershell-core

Drivers
choco install intel-graphics-driver		
choco install driverpacksolution	DRIVER PACK SOLUTION ONLINE
choco install sdio		SNAPPY DRIVER INSTALLER ORIGIN


*************
Installation:
*************

Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))

choco feature enable -n=allowGlobalConfirmation
choco feature disable -n=allowGlobalConfirmation

Upgrading Chocolatey
Once installed, Chocolatey can be upgraded in exactly the same way as any other package that has been installed using Chocolatey. Simply use the command to upgrade to the latest stable release of Chocolatey:
choco upgrade chocolatey
choco upgrade all

Install with PowerShell.exe
With PowerShell, there is an additional step. You must ensure Get-ExecutionPolicy is not Restricted. We suggest using Bypass to bypass the policy to get things installed or AllSigned for quite a bit more security.
Run Get-ExecutionPolicy. If it returns Restricted, then run Set-ExecutionPolicy AllSigned or Set-ExecutionPolicy Bypass -Scope Process.

New Found Packages:
choco install automouseclick	Automate Mouse clicks with Auto Mouse Click Utility.
choco install qalculate			the ultimate desktop calculator
choco install airexplorer		Manage all your cloud storage accounts using just one program

windows 10 gen2

Link to download Winget Installer manually:
https://aka.ms/getwinget
