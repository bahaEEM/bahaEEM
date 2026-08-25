## Baha Tarman

Elektrik-elektronik ve gömülü sistemler üzerine çalışıyorum. İlgi alanlarım
STM32 tabanlı gömülü yazılım, titreşim ve sinyal işleme, endüstriyel
elektrik ve otomasyon.

### Üzerinde çalıştığım proje

**AXEON-Edge** — Dönen ekipmanlar için kestirimci bakım sistemi. Motor, fan
ve pompaların titreşimini ölçüp arıza belirtisini cihazın kendi üstünde
tespit eder; bulut, sunucu veya internet bağlantısı gerektirmez.

Cihaz makineye takıldığında o makinenin normal davranışını kendisi öğrenir,
sonraki ölçümlerin bu normale uzaklığına bakar. Böylece kurulumda elle eşik
girilmesi gerekmez. Kestirimci bakım cihazlarının sahada en sık yaşadığı
sorun, yük veya devir değiştiğinde sabit eşiğin aşılması ve arıza olmadığı
hâlde alarm üretilmesidir; mimari bu sorunu hedef alır.

Donanım tarafında Cortex-M4F mikrodenetleyici ve geniş bantlı MEMS
ivmeölçer, yazılım tarafında spektral öznitelik çıkarımı ve cihaz üstünde
çalışan istatistiksel karar mantığı bulunur.

Mimari, kamuya açık titreşim veri kümeleri üzerinde sınanmıştır. Doğrulama
çalışmasının kodu, veri künyeleri ve analiz çıktıları burada:
[axeon-edge-dogrulama](https://github.com/bahaEEM/axeon-edge-dogrulama)


### Kullandığım araçlar

Gömülü sistemler: STM32CubeIDE/CubeMX , C
Elektronik tasarım: KiCad, LTspice
Elektrik projelendirme: EPLAN
Veri analizi: Python (NumPy, SciPy, pandas, scikit-learn)


### İletişim

bahatarman76@gmail.com
