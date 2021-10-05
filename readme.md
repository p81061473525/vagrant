# 專案說明

這是一個研究 vagrant 的專案，
主要是紀錄所使用的 vagrantfile，達到本地快速開啟測試機器，並進行自動化測試的小型虛擬機。

實際上使用 docker 可以構成相同目的，但 本地開啟虛擬機仍有與 docker 不相同之處。因此主要用來版本控制 vagrantfile 。

## Ansible 版本注意事項

請小心不要讓 inventroy 保存所有主機相關資訊，請愛用 inventory 加密模式進行加密，

附上的 inventory 是 明文參考範本，讓新手練習的範例檔案。

## 懶人包

` git clone https://github.com/p81061473525/vagrant.git -b ansible ; cd .\vagrant\ ; vagrant up ; vangrat snapshot 1`
