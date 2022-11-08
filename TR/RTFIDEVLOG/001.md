# RTFI Devlog 1 - Sıfırdan başlıyoruz... Rain dosyaları

- [RTFI Devlog 1 - Sıfırdan başlıyoruz... Rain dosyaları](#rtfi-devlog-1---sıfırdan-başlıyoruz-rain-dosyaları)
  - [Video](#video)
    - [Bölümler](#bölümler)
    - [Video detayları](#video-detayları)
    - [Videoda kullanılan dosyalar](#videoda-kullanılan-dosyalar)
      - [InstantServer.exe](#instantserverexe)
      - [InstantServer içerisindeki dosyalar.](#instantserver-içerisindeki-dosyalar)
      - [Client arşivi](#client-arşivi)
      - [Client Türkçe yama](#client-türkçe-yama)
      - [Client İngilizce yama](#client-i̇ngilizce-yama)
      - [Rain Server dosyaları](#rain-server-dosyaları)
      - [Mysqldump sql dosyası](#mysqldump-sql-dosyası)
  - [RTFI Discord kanalı](#rtfi-discord-kanalı)

## Video

[![RTFIDEVLOG9](https://img.youtube.com/vi/zV9JcZ_rnX8/0.jpg)](https://youtu.be/zV9JcZ_rnX8)

[![Youtube](https://img.shields.io/youtube/views/zV9JcZ_rnX8?style=social&label=Görüntüleme)](https://youtu.be/K8lXB2LteDo)

> 💬 İlk sızdırılan rain dosyalarından ihtiyacımız olabilecek dosyalaır alıyoruz ve birazcık nostalji yaşıyoruz.

### Bölümler

| Bölüm | Açıklama |
| --- | --- |
| 1️⃣ [0:00:00](https://youtu.be/zV9JcZ_rnX8?t=0) | M2 leak story. |
| 2️⃣ [0:01:25](https://youtu.be/zV9JcZ_rnX8?t=85) | Programları yüklüyoruz.  |
| 3️⃣ [0:15:00](https://youtu.be/zV9JcZ_rnX8?t=900) | Rain dosyaları |
| 4️⃣ [0:29:01](https://youtu.be/zV9JcZ_rnX8?t=1741) | Sanal makine kurulumu. |
| 5️⃣ [0:34:27](https://youtu.be/zV9JcZ_rnX8?t=2067) | Server dosyalarını arşivleme |
| 6️⃣ [0:39:07](https://youtu.be/zV9JcZ_rnX8?t=2347) | Veritabanı mysqldump |
| 7️⃣ [0:42:58](https://youtu.be/zV9JcZ_rnX8?t=2578) | Login |

### Video detayları

Videoda okunamama ihtimaline ya da duyulmama ihtimaline karşı yazılan kodlar ve şifreler

* InstantServer.exe şifresi `mcncc.com`
* VHD **root** user password `mcncc.com`
  * Türkçe klavyede `ç` harfine basarak `.` yazabilirsiniz.
* client de hesap şifresi `12345`
* mysql dışarıya açık root hesabı şifresi `123456`
* mysql localhost root hesabı şifresi yok.
* `/etc/rc.d/netif restart`
* `mysqldump --user root --password --all-databases > rain_all_db.sql`
* `tar czvf rain.tar.gz rain`

### Videoda kullanılan dosyalar

#### InstantServer.exe

Rain'in sızdırdığı 7zip SFX arşivi. İndirmenize gerek yok. Aşağıda içerisindeki dosyaların tekrardan sıkıştırılmış hali bulunmakta. Nostaljik değeri olduğu için bulundurabilirsiniz.

[MEGA](https://mega.nz/file/Et8k0Q6D#cnppoleb0KOKz_bgS9TO82YYQCp3dCFxC9QGhBBl6M8)

> **Arşiv şifresi:** `mcncc.com`

#### InstantServer içerisindeki dosyalar.

Videoda instanserver.exe içerisinden çıkardığımız dosyalar, yukarıdaki arşivle uğraşmak zorunda kalmayın.

[MEGA](https://mega.nz/file/5TpxhYoK#bn94OiftqEoJxq4GVLMJ2tAz_xTU6QydSeEfCzMH1Hk)

> **Arşiv şifresi:** `rain`
>> **SHA-256:** `436BCFB3963B02506EEEB07713F18396CA49DA6BA084D7ACE8CC361885622062`

#### Client arşivi

[MEGA](https://mega.nz/file/8LBSwCYb#uAj7RfEcBj2TmLbUQMjl2fLWEYkDOxTnQ5zJGHQ1G_A)

> **Arşiv şifresi:** `rain`
>> **SHA-256:** `27E2FCFB486E3682A898FB32F7F30F064729D7BD7323FEB4D9B202A76486FB2B`

#### Client Türkçe yama

[MEGA](https://mega.nz/file/xL4hRRYa#sTkCC95ZDcdiLH75979I1Bl-nnTcILbhZ_i2nOU9YqU)

> **Arşiv şifresi:** `rain`
>> **SHA-256:** `4F03CB7974655DBA67B5D9B80BFDCE18BB9C3C6753AE4CFD7E082F2E33D0C25A`

#### Client İngilizce yama

[MEGA](https://mega.nz/file/kKx2BTZB#aGkQmLzobKVNAsBQjSy7K_n_4S9FMgufTmxKiFog0tg)

> **Arşiv şifresi:** `rain`
>> **SHA-256:** `974F8402524BC10F5EF82D87F11C64721525AD00D89AD9E02171D8CD75612672`

#### Rain Server dosyaları

Videoda sanal makineyi kurduktan sonra arşivlediğimiz dosyalar.

[MEGA](https://mega.nz/file/JLp2iALT#Gf09yDxUK7sbsANveF8xdWja_T_Mwg-eTBdV50_BSbY)

> Lzma2 algoritması ile yüksek ayarlarda tekrardan sıkıştırılmıştır...
>> **SHA-256:** `1833A13707ABBCE334A030CD5A2E5F8D6F2C336FF9EB9D2CDD3417519758A5FA`

#### Mysqldump sql dosyası

[MEGA](https://mega.nz/file/pO5WRKga#6T-Rh6uHoLFftr53Tot2fDaGnS958rTwOFoaKsLMKho)

> Videoda mysqldump ile aldığımız veritabanının tüm kopyası.
>> **SHA-256:** `E42637DA2B712A829D43186F29532A643DB02363366DDAE082D08EC2235373EF`

## RTFI Discord kanalı

[![Discord](https://img.shields.io/discord/545564775497859072?label=Discord&logo=discord&style=social)](https://discord.gg/JbFdHMK) 

> Discord kanalı üzerinden hata bildirebilir, yardım alabilirsiniz.
>> Sayaca tıklayarak discord kanalımıza katılabilirsiniz...

