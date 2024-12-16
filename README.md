**sub2** isimli notebookta **Mobilenet** ile model eğitilmiş ve **submission2.csv** dosyası oluşturulmuştur. 
Az sayıda benzer fotoğrafa sahip olmasına rağmen çok benzer fotoğrafların doğru tahmini için **Recommender4_uptsub2** notebookunda önce **Resnet50** ile özellik çıkarımı yapılmış,
sonrasında **Knn** ile en yakın komşu hesaplanmıştır. Sonuçlar **submission6_knn.csv** dosyasına kaydedilmiştir. 
En yakın komşularına 0.50 den daha az distance a sahip filenameler çekilip submission2.csv daki değerleriyle değiştirilmiştir.
Son hali **updated_sub2.csv** dosyasına kaydedilmiştir.

**Takım Üyeleri:**
Sümeyra Karsavran
Baha Altan Reisoğlu
