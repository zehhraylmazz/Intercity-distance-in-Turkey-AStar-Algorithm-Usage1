# Intercity-distance-in-Turkey-AStar-Algorithm-Usage1
In this study, a comparative application of BFS, DFS and A* Search Algorithms was made in the Turkish transportation system.
The study analyzes the distances between cities in Turkey using A*, BFS (Breadth-First Search), and DFS (Depth-First Search) algorithms and visualizes this analysis.
Using the Turkish General Directorate of Highways Measurements, BFC, DFC and A* Graph Algorithms were used to find the shortest route for the distance between any two provinces in Turkey.
In this study, an application was made using Anaconda Navigator and libraries such as NetworkX and Pandas on Python Jupiter Notebook.
Data received from the General Directorate of Highways of Turkey was used as actual distance (km) information. Three separate data sets were prepared. All data sets will be presented in their full form in the appendix.
The first of these is real distances. It is specified as TURKEY_KM_REAL_DISTANCE_FILE.
Secondly, the bird's eye distances required to comply with the A* Search Algorithm principle were calculated using the latitude and longitude of the cities via SQL Server.
The calculated bird's eye view values ​​are indicated as TURKEY_BIRDSEYEDISTANCE_FILE.
The third is the data set in which the neighborhood matrix containing the relationships between the cities in Turkey is created and is named TURKEY_NEIGHBOUR_FILE.

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
