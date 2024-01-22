# Intercity-distance-in-Turkey-AStar-Algorithm-Usage1
Bu çalışmada , BFS, DFS ve A* Arama Algoritmalarının Türkiye ulaşım sisteminde karşılaştırmalı uygulaması yapılmıştır. 
Çalışma A*, BFS (Breadth-First Search), ve DFS (Depth-First Search) algoritmalarını kullanarak Türkiye'deki şehirler arasındaki mesafelerini analiz etmekte ve bu analizi görselleştirmektedir. 
Türkiye Karayolları Genel Müdürlüğü Ölçümleri kullanılarak Türkiye’deki herhangi iki il arası uzaklık BFC, DFC ve A* Graf Algoritmaları en kısa yolu bulmak için kullanılmıştır. 
Bu çalışmada Anaconda Navigator kullanılarak, Python Jupiter Notebook üzerinde NetworkX ve Pandas gibi kütüphanelerden yararlanarak uygulama yapılmıştır. 
Türkiye Karayolları Genel Müdürlüğünden alınan veriler gerçek uzaklık (km) bilgileri olarak kullanılmıştır. Üç ayrı veri seti hazırlanmıştır. Tüm veri setleri tam haliyle ekte sunulacaktır.
Bunlardan ilki gerçek uzaklıklardır. TURKEY_KM_REAL_DISTANCE_FILE olarak adlandırılarak belirtilmiştir.  
İkincisi A* Arama Algoritması prensibine uygunluk açısından gerekli olan kuşbakışı uzaklıklar SQL Server aracılığıyla şehirlerin enlem ve boylamları kullanılarak hesaplatılmıştır.
Hesaplanan kuşbakışı değerleri TURKEY_BIRDSEYEDISTANCE_FILE olarak adlandırılarak belirtilmiştir. 
Üçüncüsü ise Türkiye’deki şehirlerin birbirleri ile arasındaki ilişkileri içeren komşuluk matrisinin oluşturulduğu veri setidir ve TURKEY_NEIGHBOUR_FILE olarak adlandırılmıştır.
