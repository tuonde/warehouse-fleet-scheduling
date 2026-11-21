# Proje 09 — Warehouse Fleet Scheduling, Multi-Agent Path Finding and Energy Management

**Proje alanı:** Multi-Robot Systems & Optimization  
**Grup ID:** G12  
**Grup üyeleri:** Oğuz Eren, Tunahan Onursal Demiral, Yasin Özay, Onur Ökten ve Esma Cimsit.

## Amaç ve problem tanımı
Yoğun bir depoda birden fazla otonom mobil robotun siparişleri paylaşması ve taşıma görevlerini yürütmesi amaçlanır. Görev dağıtımı, çok robotlu rota planlama, darboğazlar ve batarya yönetimi birlikte ele alınacaktır. Robot gecikmesi veya arızasının diğer robotların görevlerine etkisi de incelenecektir.

## Kapsam ve iş paketleri
1. Depo, robot, sipariş ve enerji modelinin tanımlanması.
2. Görev ataması, çakışmasız hareket ve şarj planlaması için yöntem araştırması ve seçimi.
3. Koordinasyon kararlarıyla çalışan çok robotlu simülasyonun geliştirilmesi.
4. Farklı sipariş yoğunluğu, yerleşim, filo büyüklüğü ve arıza koşullarında deneyler.
5. Bulguların raporlanması ve alternatiflerin karşılaştırılması.

## Yöntemler, algoritmalar ve alternatifler
Araştırma kapsamı: Multi-Agent Path Finding (MAPF), görev atama, job-shop scheduling, mixed-integer linear programming (MILP), sezgisel arama, çok amaçlı optimizasyon ve batarya duyarlı planlama. Bütünleşik ve hiyerarşik çözüm yaklaşımları değerlendirilecektir. Nihai yöntemler ve seçim gerekçeleri araştırma sonrasında buraya eklenecektir.

## Sistem mimarisi ve çalışma akışı
Planlanan akış: siparişlerin alınması → görev atama → rota ve zamanlama → hareket ve çakışma yönetimi → enerji ve şarj kararları → sonuçların kaydı. Bileşenler, arayüzler ve hata durumları tasarım kesinleştiğinde belgelenecektir.

## Araçlar ve simülasyon ortamı
Henüz seçilmedi. Ortamın sürümü, robot ve depo modelleri ile varsayımlar seçimden sonra kaydedilecektir.

## Kurulum ve çalıştırma
Simülasyon henüz geliştirilmedi. Bağımlılıklar, kurulum ve tekrarlanabilir çalıştırma adımları uygulama hazırlandıkça eklenecektir.

## Testler, deneyler ve sonuçlar
Sipariş yoğunluğu, koridor düzeni, robot sayısı, şarj ihtiyacı ve arıza gibi değişkenler altında deneyler planlanır. Aday ölçütler: görev tamamlama süresi, gecikme, filo verimi, enerji tüketimi, kaynak çatışmaları ve iş dağılımında adillik. Senaryolar, ölçüm tanımları, gerçek çıktılar ve sınırlamalar deneyler yapıldıkça eklenecektir.

## Yol haritası
- [ ] Literatür ve alternatif yöntemleri incele.
- [ ] Simülasyon ortamını ve performans ölçütlerini seç.
- [ ] Depo ve filo modelini kur.
- [ ] Görev atama, rota planlama ve enerji yönetimini bütünleştir.
- [ ] Deneyleri gerçekleştir, sonuçları karşılaştır ve raporla.

## İlerleme günlüğü
| Tarih | Yapılan çalışma | Mevcut durum / sorun | Sonraki adım |
| --- | --- | --- | --- |
| 2026-11-21 | Proje gereksinimleri ve depo iskeleti hazırlandı. | Yöntem ve simülasyon ortamı seçilmedi; CV dosyaları henüz eklenmedi. | CV dosyalarını ekle ve literatür araştırmasına başla. |

## Depo düzeni
- `src/`: kaynak kodları
- `simulation/`: simülasyon dosyaları
- `docs/`: raporlar ve diyagramlar
- `results/`: test ve deney çıktıları
- `cv/`: tüm üyelerin CV dosyaları
- `assets/`: görseller ve veri kaynakları
- `references/`: araştırma kaynakları

## Kaynaklar
Dersin proje kataloğu ve GitHub rehberi: [Grup proje kayıt formu](https://docs.google.com/spreadsheets/d/1Lw7YcEnC2zZOtd7IEEs050NBAL25SL06JLMDRPwmgQw/edit). Akademik kaynaklar literatür araştırması sırasında eklenecektir.

