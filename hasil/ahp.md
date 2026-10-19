---
description: Bobot kriteria dan variabel hasil AHP
---

# Hasil AHP: Bobot Kriteria dan Variabel

Bobot dihitung dengan **Expert Choice 11** dari gabungan penilaian lima responden.

## Bobot kriteria

![Bobot kriteria](../.gitbook/assets/chart-bobot-kriteria.png)

{% hint style="success" %}
**Kelayakan teknis pembangunan (37%)** menjadi kriteria paling berpengaruh. Nilai inkonsistensi 0,03 menunjukkan hasil valid.
{% endhint %}

## Bobot variabel di dalam tiap kriteria

{% tabs %}
{% tab title="Teknis pembangunan" %}
| Variabel | Bobot |
| --- | --- |
| Meteorologi | 0,239 |
| Daya dukung | 0,228 |
| Aliran air | 0,160 |
| Struktur tanah | 0,147 |
| Kelandaian tanah | 0,104 |
| Infrastruktur | 0,071 |
| Jaringan utilitas | 0,052 |

Inkonsistensi 0,05.
{% endtab %}

{% tab title="Pengembangan wilayah" %}
| Variabel | Bobot |
| --- | --- |
| Kesesuaian dengan rencana tata ruang | 0,553 |
| Kesesuaian dengan tataran transportasi | 0,465 |

Inkonsistensi 0,0.
{% endtab %}

{% tab title="Lingkungan" %}
| Variabel | Bobot |
| --- | --- |
| Lingkungan alam | 0,484 |
| Penggunaan lahan sekitar | 0,306 |
| Penguasaan lahan sekitar | 0,210 |

Inkonsistensi 0,06.
{% endtab %}

{% tab title="Sosial" %}
| Variabel | Bobot |
| --- | --- |
| Relokasi penduduk | 0,580 |
| Kesesuaian dengan budaya setempat | 0,420 |

Inkonsistensi 0,0.
{% endtab %}
{% endtabs %}

## Bobot akhir tiap peta

Bobot akhir inilah yang dipakai dalam overlay di ArcGIS. Totalnya 1,00.

![Bobot akhir tiap peta](../.gitbook/assets/chart-bobot-peta.png)

Curah hujan dan daya dukung tanah (masing-masing 0,14) menjadi peta dengan pengaruh terbesar pada hasil akhir.
