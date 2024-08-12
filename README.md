Açıklama
Bu repository, YOLOv3 algoritmasını kullanarak görüntüler ve videolar üzerinde nesne tespiti gerçekleştiren iki Python scripti içerir. Bu projede, YOLOv3'ün sağladığı önceden eğitilmiş bir model ile çeşitli nesneleri tespit etmek ve bunları görüntülerde kutularla işaretlemek için OpenCV ve Numpy kullanılmıştır.

İçerik
Image Object Detection (image_object_detection.py): Bu script, verilen bir görüntüde nesne tespiti gerçekleştirir. YOLOv3 modelini kullanarak insanların, araçların, hayvanların ve daha birçok nesnenin tespit edilmesini sağlar. Sonuçlar, tespit edilen nesnelerin üzerlerine kutular çizilerek ve etiketlenerek gösterilir.

Real-time Object Detection (realtime_object_detection.py): Bu script, bir web kamerası üzerinden gerçek zamanlı olarak nesne tespiti yapar. Anlık görüntü akışı üzerinde tespit edilen nesneler, kutularla işaretlenir ve tespit edilen her nesne, görüntü üzerinde etiketlenir.

Kullanılan Teknolojiler
Python: Proje, Python programlama dili ile geliştirilmiştir.
OpenCV: Görüntü işleme ve video akışı yönetimi için kullanılmıştır.
NumPy: Matematiksel işlemler ve veri manipülasyonu için kullanılmıştır.
YOLOv3: Nesne tespiti için kullanılan derin öğrenme modeli.

Kurulum
1. Bu repository'yi klonlayın:
git clone https://github.com/semihyildiz29/object_recognition_with_yolo.git

2. Gerekli Python paketlerini yükleyin:
pip install -r requirements.txt

3.'yolov3.cfg' ve 'yolov3.weights' dosyalarını pretrained_model klasörüne yerleştirin.

Kullanım
Image Object Detection:
python image_object_detection.py

Real-time Object Detection:
python realtime_object_detection.py


