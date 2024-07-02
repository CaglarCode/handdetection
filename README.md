This script uses OpenCV to recognize hand gestures from a live webcam feed. It detects the hand, tracks its movements, and identifies the farthest point on the hand contour.

Requirements
Python 3.x
OpenCV
Numpy
Installation
Install OpenCV:

sh
Copy code
pip install opencv-python
Install Numpy:

sh
Copy code
pip install numpy
Usage
Run the script:

sh
Copy code
python hand_gesture_recognition.py
Press 'z' to create the hand histogram.

The webcam feed will open, and the program will start recognizing hand gestures.

Code Explanation
Rescale Frame: Rescales the video frame.
Contours: Finds contours in the image.
Draw Rectangles: Draws rectangles for hand region selection.
Hand Histogram: Creates a histogram for the hand region.
Histogram Masking: Applies the histogram to segment the hand.
Centroid and Farthest Point: Calculates the centroid and the farthest point of the hand contour.
Draw Circles: Draws circles on detected points.
Manage Image Operations: Manages the main image processing operations.
Main Function: Captures video and processes frames.
Türkçe
Bu betik, OpenCV kullanarak canlı webcam akışından el hareketlerini tanır. Elin hareketlerini takip eder ve el konturunun en uzak noktasını belirler.

Gereksinimler
Python 3.x
OpenCV
Numpy
Kurulum
OpenCV'yi yükleyin:

sh
Copy code
pip install opencv-python
Numpy'yi yükleyin:

sh
Copy code
pip install numpy
Kullanım
Betiği çalıştırın:

sh
Copy code
python hand_gesture_recognition.py
El histogramını oluşturmak için 'z' tuşuna basın.

Webcam akışı açılacak ve program el hareketlerini tanımaya başlayacak.

Kod Açıklaması
Rescale Frame: Video karesini yeniden boyutlandırır.
Contours: Görüntüdeki konturları bulur.
Draw Rectangles: El bölgesi seçimi için dikdörtgenler çizer.
Hand Histogram: El bölgesi için histogram oluşturur.
Histogram Masking: El segmentasyonu için histogram uygular.
Centroid and Farthest Point: El konturunun merkezini ve en uzak noktasını hesaplar.
Draw Circles: Tespit edilen noktalara daireler çizer.
Manage Image Operations: Ana görüntü işleme işlemlerini yönetir.
Main Function: Video yakalar ve kareleri işler.
