<h1>Velo Match Three</h1>

* Velo Match Three, Velo Game Studios Staj Programı kapsamında yapılan 3. projedir. Bu oyun, Unity oyun motorunda geliştirilmiş ve GitHub üzerinde paylaşılmıştır.

🛠️Kurulum

* Bu projeyi çalıştırmak için Unity 2D yazılımına ve bilgisayarınızda Unity 2D için geliştirme yapabilecek bir ortama ihtiyacınız vardır. Projeyi klonladıktan sonra Unity içinde açarak çalıştırabilir ve düzenleyebilirsiniz.

* 🚀 Projemi çalışırken görmek için: [Google Drive](https://drive.google.com/drive/folders/15FpHIQ_Hfk4uPHJfGbtqa90jlU67DHQF?usp=sharing)

💡Temel Özellikler:

1. <strong>Tahta Kurulumu ve Boyutlandırma:</strong> Oyun tahtasının genişliği ve yüksekliği (`width` ve `height` değişkenleri) belirlenerek esnek tahta boyutları sağlanır. Bu, farklı oyun deneyimleri için değişken tahta boyutlarının kullanımını mümkün kılar.

2. <strong>Prefab'lar ve Nesne Yönetimi:</strong> Oyun tahtasına farklı tiplerdeki tile'lar (`tileNormalPrefab`, `tileObstaclePrefab`) ve game piece'ler (`gamePiecePrefabs`) yerleştirilebilir. Bu nesnelerin oluşturulması ve yönetimi, oyunun başlangıcında gerçekleşir.

3. <strong>Bomba ve Toplama Nesneleri:</strong> Oyun içinde özel eylemler gerçekleştirmek için çeşitli bomba prefab'ları (`adjacentBombPrefab`, `columnBombPrefab`, `rowBombPrefab`, `colorBombPrefab`) kullanılabilir. Ayrıca, rastgele ortaya çıkabilen toplama nesneleri (`collectiblePrefabs`) de eklenerek oyunun çeşitliliği artırılır.

4. <strong>Oyun Nesnelerinin Başlangıç İnşası:</strong> Oyun tahtasının başlangıç durumunu belirlemek için tile ve game piece'leri (`StartingObject[] startingTiles`, `StartingObject[] startingGamePieces`) tanımlamak mümkündür. Bu, oyunun başlangıcında belirli nesnelerin yerleştirilmesini sağlar.

5. <strong>Kamera Ayarları:</strong> Oyun tahtası boyutlarına bağlı olarak kamera pozisyonu ve ortografik boyut ayarlanarak, tahtanın tamamının görünür olması sağlanır.

6. <strong>Eşleşme Bulma ve Vurgulama:</strong> Oyun tahtasında en az üç bitişik oyun parçasının eşleşmesini (`FindMatchesAt`) tespit eder ve vurgular (`HighlightMatchesAt`). Bu, oyuncuya oyun içi ilerleme ve görsel geri bildirim sağlar.

7. <strong>Oyun Parçası Temizleme ve Doldurma:</strong> Eşleşen oyun parçalarının temizlenmesi ve ardışık olarak tahtanın doldurulması işlemleri (`ClearAndRefillBoard`) yönetilir. Bu, oyun içinde dinamik bir çökme ve doldurma mekanizması sağlar.

8. <strong>Bomba Aktivasyonu ve İşleyişi:</strong> Eşleşme durumunda özel oyun parçaları olan bombaların (`Bomb`) aktive edilmesi ve belirli satır, sütun veya bitişik parçaları temizleme işlemleri yönetilir.

9. <strong>Toplanabilir Nesne Yönetimi:</strong> Oyun tahtasında rastgele ortaya çıkan toplanabilir nesnelerin oluşturulması, tespiti ve kaldırılması (`FindCollectiblesAt`, `RemoveCollectibles`) sağlanır. Bu, oyuncuya ekstra kazanç ve stratejik seçenekler sunar.

10. <strong>Puanlama ve Oyun Akışı:</strong> Oyun içinde eşleşme boyutuna bağlı olarak oyuncunun puanının hesaplanması ve oyun akışının sürekli olarak devam ettirilmesi sağlanır. Bu, oyunun dinamiklerini ve oyuncu etkileşimini artırır.

🛠 Temel Mekanikler:

* <strong>Tahta Boyutu ve Esneklik:</strong> Oyun tahtası genişliği ve yüksekliği belirlenebilir, böylece farklı boyutlarda tahtalar oluşturulabilir.

* <strong>Farklı Tile ve Game Piece Türleri:</strong> Oyun tahtası üzerinde çeşitli tile'lar (normal, engel vb.) ve game piece'ler (farklı renklerdeki nesneler) yerleştirilebilir.

* <strong>Özel Bomba Türleri ve Etkileri:</strong> Oyun içinde farklı bomba türleri kullanılabilir (bitişik, sütun, satır, renk), bu bombalar eşleşmelerde özel efektler yaratır.

* <strong>Toplanabilir Nesneler:</strong> Rastgele ortaya çıkan toplanabilir nesneler oyuna ek bir katman sağlar.

* <strong>Başlangıç Nesne Yerleşimi:</strong> Oyun başlangıcında tahtaya önceden belirlenmiş tile'lar ve game piece'ler yerleştirilebilir.

* <strong>Kamera Ayarları:</strong> Oyun tahtasının boyutuna bağlı olarak kamera pozisyonu ayarlanarak, oyuncunun tahtanın tamamını görebilmesi sağlanır.

* <strong>Eşleşme Algılama ve Vurgulama:</strong> Oyun tahtasında eşleşen game piece'ler algılanır ve oyuncuya vurgulanarak gösterilir.

* <strong>Oyun Parçası Temizleme ve Doldurma:</strong> Eşleşen game piece'ler temizlenir ve ardışık olarak tahta doldurulur, böylece yeni eşleşmeler oluşturulur.

* <strong>Bomba Aktivasyonu ve Kullanımı:</strong> Eşleşmelerde belirli koşullar sağlandığında bombalar aktive edilir ve tahtadaki game piece'leri temizler.

* <strong>Puanlama ve Oyun Akışı:</strong> Oyun içinde yapılan hamlelere bağlı olarak oyuncunun puanı hesaplanır ve oyun akışı sürekli olarak devam eder.

<br>

💡 Görseller:

![image](https://github.com/CanerKarul/VeloMatchThree/assets/100365204/cf38d5eb-5c27-4aaf-be8e-d44332e8b134)

![image](https://github.com/CanerKarul/VeloMatchThree/assets/100365204/88274e79-a779-4135-a836-0ea29bbfc484)

![image](https://github.com/CanerKarul/VeloMatchThree/assets/100365204/e96e2a18-fdec-4a10-baec-4da7936b4798)

![image](https://github.com/CanerKarul/VeloMatchThree/assets/100365204/c2b9b2e9-f148-44ee-a921-bc86089d9ccc)

![image](https://github.com/CanerKarul/VeloMatchThree/assets/100365204/cbf89d35-9710-4504-9d28-deb9d73bb81c)

![image](https://github.com/CanerKarul/VeloMatchThree/assets/100365204/5702d1c5-7664-4ca4-b041-43d782b699fa)

![image](https://github.com/CanerKarul/VeloMatchThree/assets/100365204/43bf593c-ca3d-4a95-b8ce-347a54772ecc)

![image](https://github.com/CanerKarul/VeloMatchThree/assets/100365204/9d5f59f6-ff96-49c7-9d40-b64057bf41b8)







  











