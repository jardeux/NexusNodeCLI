# NexusNodeCLI

> Nexus CLI Node kurulumu
> [Buradan](https://beta.nexus.xyz/) mail girip gelen mailden siteye giriyorsunuz sol alttaki prover ID saklayın.
# Kurulum
```console
# güncelleme
sudo apt update -y && sudo apt upgrade -y
sudo apt install -y protobuf-compiler
```
```console
# Nexus Kurulum
screen -S nexus
curl https://cli.nexus.xyz | sh
# Prover ID isteyecek sakladığınız ID girin
# Daha sonra sunucudan .nexus dizinine gidip prover-id dosyasından id'yi kendinizinkiyle değiştirin.
# Kodu tekrar çalıştırın:
curl https://cli.nexus.xyz | sh
# Bu kısım biraz sürebilir
```
> Böyle bir çıktı aldıysanız node başarıyla kurulmuştur. Dashboarddan points takibi yapabilirsiniz.

![image](https://github.com/user-attachments/assets/a8d7105c-ead6-44b8-9f75-0190a42aa0b4)
