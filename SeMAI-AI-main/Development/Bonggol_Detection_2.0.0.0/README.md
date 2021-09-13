## Bonggol Detection V2.0
### Maintainter : BW, NAF, HAM
### Source : 
* [TensorFlow](https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/training.html#preparing-the-workspace)
* [centernet on device](https://github.com/tensorflow/models/blob/master/research/object_detection/colab_tutorials/centernet_on_device.ipynb)

### Description : 
* Object Detection model based on Python programming language
* Using Google Colaboratory platform to simplify implementation and training
* Final output : TFLite model (final target is implementation on android system)
* Object target : bonggol and berondolan (palm tree)
* Object Detection API Used : CenterNet_MobileNetV2 and SSDMobileNetV2 from [TF model detection zoo](https://github.com/tensorflow/models/blob/master/research/object_detection/g3doc/tf2_detection_zoo.md)

### Target (Trello) : 
- [x] Research Model dan Colab Notebook (Result: CenterNet TFLite Converter)
- [x] Konversi hasil checkpoint training menuju ke TFLite (Centernet TFLite Converter example)  
- [x] Adaptasi dataset dari Roboflow untuk dimasukkan ke model training (Custom Model Training dengan CenterNet MobileNetV2, dengan format dataset VOC)
- [x] Explore kapabilitas config training untuk pembuatan model (dapat diakses di file setting fine tuning `pipeline.config`)
- [x] Pembuatan Model, Training, Evaluating (output berupa `model.tflite`, `labelmap.txt` dan `saved_model`)
- [x] Pembuatan integrasi notebook training di colab (sebelumnya masih terpisah, notebook train dan konversi)
- [ ] Release eksperimen 1
- [ ] Pembuatan notebook versi offline (Jupyter Notebook) apabila dibutuhkan

### How to Use : 
* Repo berbasis pada platform Google Colaboratory 
* instruksi penggunaan ada pada platform colab di link [ini](https://colab.research.google.com/drive/14u-7QSgFUX9ULHFb9b6BEH1FHsMeKTr9?usp=sharing)