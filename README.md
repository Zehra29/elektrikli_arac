**ELEKTRİKLİ ARAÇ VERİ ANALİZİ**

Kaggle'da 17 özelliği olan elektrikli araç veri seti ile çalışılmıştır.

 **0   VIN (1-10)**: Elektrikli aracın üretim aşamasında belirlenen kimlik numarasıdır.  
 **1   County**: Veri setinde incelenen elektrikli araçların hangi ülkeye ait olduğunu gösteririr.    
 **2   City**: Veri setinde incelenen elektrikli araçların hangi şehre ait olduğunu gösteririr.   
 **3   State**: Veri setinde incelenen elektrikli araçların hangi eyalete ait olduğunu gösteririr.  
 **4   Postal Code**: Veri setindeki posta kodunu tutar.    
 **5   Model Year**: Elektrikli araçların kaç model olduğu bilgisini tutar.  
 **6   Make**: Elektrikli araçların hangi markaya ait olduğunu gösteririr.  
 **7   Model**: Elektrikli araçların model bilgisini tutar.  
 **8   Electric Vehicle Type**: Elektripli araç tipini tutar.BEV ya da PHEV  
 **9   Clean Alternative Fuel Vehicle (CAFV) Eligibility**: Temiz alternatif yakıt uygunluğu bilgisini tutar.Batarya menzili ile ilişkilidir.  
 **10  Electric Range**: Bir aracın tam şarj edildiğinde gidebileceği max mesafeyi tutar.  
 **11  Base MSRP**: Aracın ham satış fiyatı bilgisini tutar.   
 **12  Legislative District**: Yasama bölgesi verisini tutar.  
 **13  DOL Vehicle ID**: Eyalete ait araç tanımlayıcı nımarasıdır.    
 **14  Vehicle Location**: Aracın konum bilgisini tutar.  
 **15  Electric Utility**: Elektrik hizmeti bilgisini tutar.  
 **16  2020 Census Tract**: Coğrafi birim bilgisini tutar. 

 **ÇALIŞILAN ORTAM VE KÜTÜPHANELER**

 Kaggle Notebook'ta Pandas,Numpy,Matploit ve Seaborn kütüphaneleriyle çalışılmıştır.

 **PROJE**

 Veri setini anlamak için temel kodlar ile veri setinin boyutunu, veri türlerini ve veri setinin ilk 5 verisi gibi analizleri yaptım. Daha sonra veri setimin eksik veri içerip içermediğini kontrol ettim. Veri setim eksik veri içermesine rağmen proje kapsamında istenen rastgele eksik veri üretim fonksiyonu ile %3 oranında eksik verilerimi ürettim. Daha sonra veri setimde numerik tutulan bazı değişkenlerimin veri tipini object olarak değiştirdim. Numerik eksik verilerimi medyan yardımıyla, kategorik eksik verilerimi ise gruplama ve mod yardımıyla doldurdum. Bazı kategorik değişkenlerim için benzersiz değerler, değer sayısı ve grafikte görselleştirilmesi analizlerini yaptım. Bazı kategorik değişkenlerim için gruplama yaparak numerik değişkenlerim için analizler yaptım. Mevcut veri setimdeki araçların model yılını kullanarak yeni bir model yıl segment kolonu oluşturdum. Boxplot ile bu oluşturduğum kolon ve başka bir kategorik özellik için numerik bir özelliğimi analiz ettim. Son olarak ta ısı haritası ile numerik özelliklerim arasında bir ilişki olup olmadığı kontrolünü yaptım.
 
