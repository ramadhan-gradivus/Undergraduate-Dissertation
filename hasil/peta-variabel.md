---
description: 14 peta tematik dan aturan penilaian (reclassify) tiap variabel
---

# 14 Peta Tematik dan Aturan Penilaiannya

Sebelum ditumpuk, setiap peta diberi skor seragam lewat **reclassify**: **1** berarti memenuhi sebagai lokasi bandara, **0** berarti tidak memenuhi. Berikut aturan tiap variabel dan petanya.

{% tabs %}
{% tab title="Pengembangan wilayah" %}
| Variabel | Skor 1 (memenuhi) | Skor 0 |
| --- | --- | --- |
| Tata ruang | Sesuai RTRW nasional, provinsi, kabupaten (ada rencana bandara) | Tidak sesuai |
| Tataran transportasi | Sesuai tataran transportasi (ada rencana bandara) | Tidak sesuai |

![Kesesuaian tata ruang](../.gitbook/assets/v01-tata-ruang.jpg)

![Kesesuaian tataran transportasi](../.gitbook/assets/v02-tataran-transportasi.jpg)
{% endtab %}

{% tab title="Teknis pembangunan" %}
| Variabel | Skor 1 (memenuhi) | Skor 0 |
| --- | --- | --- |
| Kelandaian | Kemiringan 0-2% | Lebih dari 2% |
| Drainase | Kemampuan drainase tinggi | Cukup |
| Curah hujan | 1.000-1.699 mm/tahun | 1.700 mm/tahun atau lebih |
| Daya dukung | Kestabilan pondasi tinggi | Sedang |
| Struktur tanah | Grumosol, mediteran | Aluvial, regosol |
| Infrastruktur | Terlayani jalan arteri, kolektor, atau lokal (buffer 1.000 m) | Hanya jalan lingkungan |
| Utilitas | Terlayani jaringan utilitas (buffer 1.000 m) | Tidak terlayani |

![Kemiringan lahan](../.gitbook/assets/v03-kemiringan.jpg)

![Curah hujan](../.gitbook/assets/v04-curah-hujan.jpg)

![Daya dukung](../.gitbook/assets/v05-daya-dukung.jpg)

![Kemampuan drainase](../.gitbook/assets/v06-drainase.jpg)

![Jenis tanah](../.gitbook/assets/v07-jenis-tanah.jpg)

![Pelayanan jalan](../.gitbook/assets/v08-jalan.jpg)

![Pelayanan utilitas](../.gitbook/assets/v09-utilitas.jpg)
{% endtab %}

{% tab title="Lingkungan" %}
| Variabel | Skor 1 (memenuhi) | Skor 0 |
| --- | --- | --- |
| Lingkungan alam | Tidak mengganggu aktivitas penerbangan | Dapat mengganggu (misalnya gunung, rawan angin puyuh) |
| Penggunaan lahan | Hutan produksi, perkebunan, sawah, semak belukar, tegalan | Empang, hutan lindung, permukiman, sungai, tambak, waduk |
| Penguasaan lahan | Dikuasai pemerintah (alih fungsi lebih mudah) | Dikuasai masyarakat |

![Lingkungan alam](../.gitbook/assets/v10-lingkungan-alam.jpg)

![Penggunaan lahan](../.gitbook/assets/v11-penggunaan-lahan.jpg)

![Penguasaan lahan](../.gitbook/assets/v12-penguasaan-lahan.jpg)
{% endtab %}

{% tab title="Sosial" %}
| Variabel | Skor 1 (memenuhi) | Skor 0 |
| --- | --- | --- |
| Relokasi penduduk | Tidak ada potensi relokasi permukiman | Ada potensi relokasi |
| Kecocokan budaya | Tidak ada potensi ketidakcocokan | Ada potensi ketidakcocokan |

![Potensi relokasi](../.gitbook/assets/v13-relokasi.jpg)

![Potensi ketidakcocokan budaya](../.gitbook/assets/v14-budaya.jpg)
{% endtab %}
{% endtabs %}

{% hint style="info" %}
Variabel meteorologi sebenarnya mencakup curah hujan, suhu, kelembapan, dan angin. Hanya **curah hujan** yang dapat dipetakan, dan dinilai cukup mewakili. Data lain lebih relevan untuk tahap Detail Engineering Design.
{% endhint %}
