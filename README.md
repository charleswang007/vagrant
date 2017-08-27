# vagrant

Vagrant可以快速構建VM，部驟簡單，實現多機器環境架構，方便開發者進行開發工作。

一個打包好的作業系統環境在Vagrant稱之為Box，也就是說每個Box都是一個打包好的作業系統環境

VirtualBox、VMware Workstation、VMware Fusion、Parallels Desktop 等虛擬機軟體，讓你將任何一台電腦模擬成其他作業系統；Vagrant 則進一步將這些虛擬機納入管控，讓軟體研發流程更順暢、更有彈性。

如何將本機的檔案放置到VM呢？Vagrant建立出來的VM內有一個共享資料夾/vagrant，該資料夾會與vagrant設定檔所在的資料夾共享資料，所以想要將檔案放置到VM，直接把檔案放在設定檔的資料夾便可。

Vagrant 官方定義為 「建立及設定輕量性、可重覆性及可攜性的開發環境」，主要是透過設定檔使用 VirtualBox 來建立一個虛擬機器 (Virtual Machine, VM)，是達成 「Infrastructure As Code」的一種方式。

![alt text](logo.PNG "HashiCorp Vagrant")