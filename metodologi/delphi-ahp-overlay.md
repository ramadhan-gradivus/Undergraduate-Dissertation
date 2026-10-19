---
description: Cara kerja tiga alat analisis: Delphi, AHP, dan weighted overlay
---

# Tiga Alat Analisis

![Alur analisis](../.gitbook/assets/diagram-alur-analisis.png)

{% tabs %}
{% tab title="1. Delphi" %}
**Tujuan:** mengonfirmasi variabel mana yang benar-benar berpengaruh untuk Lamongan.

Delphi mencari **konsensus** kelompok pakar. Jika belum sepakat, dilakukan iterasi pengurangan sampai konsensus tercapai (Dunn, 2000). Tahapannya:

1. Spesifikasi permasalahan.
2. Menyusun kuesioner putaran I dari variabel hasil sintesis pustaka.
3. Wawancara putaran I dengan prinsip **anonimitas**: responden menjawab terpisah dan tidak saling mengetahui.
4. Analisis hasil: verifikasi pendapat, membaca kecenderungan, dan mengeliminasi pertanyaan yang tidak diperlukan lagi.
5. Menyusun kuesioner berikutnya sampai pendapat konvergen.
{% endtab %}

{% tab title="2. AHP" %}
**Tujuan:** membobotkan kriteria dan variabel yang sudah terkonfirmasi.

*Analytic Hierarchy Process* memecah masalah menjadi hierarki (tujuan, kriteria, variabel), lalu responden membandingkan elemen secara berpasangan. Perhitungan memakai perangkat lunak **Expert Choice 11**. Setiap hasil dilengkapi nilai inkonsistensi untuk menguji validitas penilaian.
{% endtab %}

{% tab title="3. Weighted overlay" %}
**Tujuan:** menemukan lahan yang paling sesuai.

Peta tematik tiap variabel diberi skor seragam lewat proses **reclassify**, lalu ditumpuk dengan metode *weighted sum* di **ArcGIS 10.1** memakai bobot AHP. Hasilnya peta kesesuaian lahan, yang kemudian disaring dengan kebutuhan luas lahan bandara.
{% endtab %}
{% endtabs %}
