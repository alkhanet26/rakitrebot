# rakitrebot

Script ini untuk cek koneksi internet pada sebuah openwrt khusus modem rakitan atau modem dengan device /dev/ttyXXX
```
wget --no-check-certificate "https://raw.githubusercontent.com/alkhanet26/rakitrebot/main/rebootrakit" -O /sbin/rebootrakit && chmod +x /sbin/rebootrakit
```

# CARA PENGGUNAAN

ketik di scheduletask dengan di sarankan 3 menit sekali
```
*/3 * * * * sh /sbin/rebootraki XXX
```
untuk ``XXX`` ini ganti dengan variabel device modem contoh, untuk modem LT biasanya ``dev/ttyUSB0`` jadi ``XXX`` ini ganti dengan ``USB0``

