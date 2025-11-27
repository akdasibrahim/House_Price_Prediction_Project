House Price Prediction
İş Problemi (Business Problem)
Ev fiyatlarını çeşitli makine öğrenmesi modelleri kullanarak tahmin etmek amaçlanmaktadır. Bu proje, Exploratory Data Analysis (EDA), veri ön işleme, özellik mühendisliği ve model eğitimi ile hiperparametre optimizasyonunu içermektedir.

Veri Seti Hikayesi
Veri seti, ev fiyatlarını tahmin etmek için kullanılan çeşitli özellikleri içermektedir. Aykırı değerler, eksik değerler ve nadir kategoriler gibi veri problemleri ele alınmış ve veriden çıkarılmıştır.

Veriseti Hakkında
1460 gözlem, 81 değişken
Id: Eşsiz ev numarası
MSSubClass: Yapı sınıfı
MSZoning: Genel bölgeleme sınıflandırması
LotFrontage: Mülkün sokak cephesi
LotArea: Lot büyüklüğü
Street: Yol tipi
Alley: Sokak türü
LotShape: Lot şekli
LandContour: Düzlük
Utilities: Mevcut hizmetler
LotConfig: Lot konfigürasyonu
LandSlope: Eğim
Neighborhood: Ames şehir sınırları içindeki fiziksel konumlar
Condition1: Ana yol veya demiryoluna yakınlık
Condition2: Ana yol veya demiryoluna yakınlık (2. önemli)
BldgType: Konut tipi
HouseStyle: Konut stili
OverallQual: Genel malzeme ve kaplama kalitesi
OverallCond: Genel durum değerlendirmesi
YearBuilt: İnşa yılı
YearRemodAdd: Yenileme tarihi
RoofStyle: Çatı tipi
RoofMatl: Çatı malzemesi
Exterior1st: Dış kaplama
Exterior2nd: Dış kaplama (2. önemli)
MasVnrType: Duvar kaplaması türü
MasVnrArea: Duvar kaplama alanı
ExterQual: Dış malzeme kalitesi
ExterCond: Dış malzeme durumu
Foundation: Temel türü
BsmtQual: Bodrum yüksekliği
BsmtCond: Bodrum durumu
BsmtExposure: Bodrum duvarlarının açığa çıkması
BsmtFinType1: Bodrum bitiş alanı türü
BsmtFinSF1: Bodrum bitiş alanı (Tip 1)
BsmtFinType2: Bodrum bitiş alanı türü (Tip 2)
BsmtFinSF2: Bodrum bitiş alanı (Tip 2)
BsmtUnfSF: Bitmemiş bodrum alanı
TotalBsmtSF: Toplam bodrum alanı
Heating: Isıtma tipi
HeatingQC: Isıtma kalitesi ve durumu
CentralAir: Merkezi klima
Electrical: Elektrik sistemi
1stFlrSF: Birinci kat alanı
2ndFlrSF: İkinci kat alanı
LowQualFinSF: Düşük kaliteli bitmiş alan
GrLivArea: Yaşanabilir alan (üst katlar)
BsmtFullBath: Bodrum tam banyo sayısı
BsmtHalfBath: Bodrum yarım banyo sayısı
FullBath: Üst kat tam banyo sayısı
HalfBath: Üst kat yarım banyo sayısı
BedroomAbvGr: Üst kat yatak odası sayısı
KitchenAbvGr: Üst kat mutfak sayısı
KitchenQual: Mutfak kalitesi
TotRmsAbvGrd: Üst kat toplam oda sayısı
Functional: Ev işlevselliği
Fireplaces: Şömine sayısı
FireplaceQu: Şömine kalitesi
GarageType: Garaj türü
GarageYrBlt: Garaj inşa yılı
GarageFinish: Garaj bitirme durumu
GarageCars: Garajdaki araba sayısı
GarageArea: Garaj alanı
GarageQual: Garaj kalitesi
GarageCond: Garaj durumu
PavedDrive: Asfalt yol durumu
WoodDeckSF: Ahşap güverte alanı
OpenPorchSF: Açık veranda alanı
EnclosedPorch: Kapalı veranda alanı
3SsnPorch: Üç mevsim veranda alanı
ScreenPorch: Ekranlı veranda alanı
PoolArea: Havuz alanı
PoolQC: Havuz kalitesi
Fence: Çit durumu
MiscFeature: Diğer özellikler
MiscVal: Diğer özelliklerin değeri
MoSold: Satış ayı
YrSold: Satış yılı
SaleType: Satış türü
SaleCondition: Satış durumu
SalePrice: Satış fiyatı
Projenin Aşamaları
GÖREV 1: Veriyi Hazırlama

Veri setini okuyunuz ve ilk incelemeyi yapınız.
Aykırı değerleri, eksik değerleri ve nadir kategorileri ele alınız.
Veriyi temizleyiniz ve analiz için hazır hale getiriniz.
GÖREV 2: Keşifsel Veri Analizi (EDA)

Genel veri yapısını inceleyiniz.
Kategorik ve sayısal değişkenleri analiz ediniz.
Hedef değişkeni analiz ediniz.
Değişkenler arası korelasyonu inceleyiniz.
GÖREV 3: Özellik Mühendisliği

Yeni değişkenler oluşturunuz ve mevcut değişkenleri dönüştürünüz.
İlgili değişkenleri seçiniz ve modellemeye hazırlayınız.
GÖREV 4: Label Encoding & One-Hot Encoding

Kategorik değişkenleri etiketleyiniz veya one-hot encoding uygulayınız.
GÖREV 5: Modelleme

Çeşitli regresyon modelleri kurunuz ve değerlendirin.
Modelleri karşılaştırınız ve en iyi performans göstereni seçiniz.
GÖREV 6: Hiperparametre Optimizasyonu

Seçilen modelin hiperparametrelerini optimize ediniz.
Modeli yeniden eğitiniz ve performansını değerlendiriniz.
GÖREV 7: Modelin Test Edilmesi

Modeli test setinde değerlendiriniz.
Model performansını yorumlayınız ve gerekli iyileştirmeleri yapınız.
