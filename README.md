# Config-Openclash
config openclash
copy semua file yang sudah di download config openclash
buka file manager openwrt /Etc/Openclash


Untuk penggunaanya harap untuk menginstall https-dns-proxy & luci-app-https-dns-proxy caranya :
opkg update &&\
opkg install https-dns-proxy luci-app-https-dns-proxy

seting ip HTTP-DNS-PROXY ke 127.0.0.1 5054
biar ada kondom ngk bocor
![Screenshot_9](https://user-images.githubusercontent.com/79288577/145673506-7953076e-35ca-428f-b097-6d8094593e15.png)


1. copy folder config ke config bisa lewat winscp untuk pc atau x-plore file manager untuk android
2. proxy_provider to proxy provider 
3. copy folder rule_provider ke rule_provider
4. jangan lupa edit akun terlebih dahulu 

masuk ke global seting 
![Screenshot_6](https://user-images.githubusercontent.com/79288577/145673394-2f62401f-af56-43d2-ac31-dfe17846d4b7.png)
![Screenshot_7](https://user-images.githubusercontent.com/79288577/145673398-92ae70aa-d9f0-40a4-b4da-2a53295d2a11.png)
di menu dns seting seperti ini
![Screenshot_8](https://user-images.githubusercontent.com/79288577/145673426-ac0e27aa-71c0-4a8b-8db2-faf5ff59aee3.png)
