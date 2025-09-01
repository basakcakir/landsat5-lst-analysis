# landsat5-lst-analysis
Calculation of NDVI, Emissivity, and LST from Landsat 5 with Google Earth Engine. 
# Land Surface Temperature (LST) Analysis with Landsat 5 using Google Earth Engine

## English 🌍
This repository contains a Google Earth Engine (GEE) script used in my undergraduate thesis to calculate **Land Surface Temperature (LST)** from **Landsat 5 imagery**.  
The workflow includes:
- Filtering Landsat 5 images (July 2004, low cloud cover)
- Conversion from **DN to Radiance**
- Calculation of **Brightness Temperature (BT)**
- Derivation of **NDVI, Proportion of Vegetation (PV), and Emissivity (EMM)**
- Calculation of **Land Surface Temperature (LST) in Celsius (°C)**
- Visualization with a custom color palette
- Exporting LST results to Google Drive

⚠️ **Note:** The final LST output is in **Celsius (°C)**, not Kelvin.

### How to Use
1. Open [Google Earth Engine Code Editor](https://code.earthengine.google.com/).
2. Copy and paste the script from `code.js`.
3. Define your **study area geometry** (`table`).
4. Run the script to calculate and export LST.

### Example Outputs
- Mean LST values in Celsius (printed in console)
- LST raster exported to Google Drive
- True color Landsat 5 image for visualization

---

## Türkçe 🇹🇷
Bu depo, bitirme tezimde kullandığım **Google Earth Engine (GEE) kodunu** içermektedir. Kod, **Landsat 5 uydu görüntülerinden Yüzey Sıcaklığı (LST)** hesaplamak için kullanılmıştır.  
Çalışma akışı şu adımlardan oluşmaktadır:
- Landsat 5 görüntülerinin filtrelenmesi (Temmuz 2004, düşük bulutluluk)
- **DN → Radyans dönüşümü**
- **Parlaklık sıcaklığı (BT)** hesaplama
- **NDVI, Bitki Örtüsü Oranı (PV) ve Yayınım (EMM)** hesaplama
- **Yüzey Sıcaklığı (LST) hesaplama – sonuç Celsius (°C) cinsindedir**
- Özel renk paletiyle görselleştirme
- LST sonuçlarının Google Drive’a aktarılması

⚠️ **Not:** Koddan elde edilen LST çıktısı **Celsius (°C)** cinsindedir, Kelvin değildir.

### Kullanım
1. [Google Earth Engine Code Editor](https://code.earthengine.google.com/) adresini açın.
2. `code.js` dosyasındaki kodu yapıştırın.
3. Çalışma alanı geometrisini (`table`) tanımlayın.
4. Scripti çalıştırarak LST hesaplamasını yapın ve çıktı alın.

### Örnek Çıktılar
- Ortalama LST değerleri Celsius cinsinden (konsola yazdırılır)
- LST raster çıktısı (Google Drive’a kaydedilir)
- Görselleştirme için Landsat 5 doğal renk görüntüsü
