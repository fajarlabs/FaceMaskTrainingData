# Cara membuat model training
Disarankan menggunakan GPU Nvidia untuk mempercepat proses training<Br />

# Library python
tensorboard==1.15.0<br />
tensorboard-plugin-wit==1.7.0<br />
tensorflow==1.15.0<br />
tensorflow-estimator==1.15.1<br />
tensorflow-gpu==1.15.0<br />
tf-slim==1.1.0<br />
dlib==19.21.0<br />
Keras==2.2.4<br />
Keras-Applications==1.0.8<br />
Keras-Preprocessing==1.1.0<br />
numpy==1.16.4<br />

# Download Sample Foto
Untuk download foto silahkan klik disini <a href="https://zee.gl/BOj8">Download Dataset</a> atau link alternatif disini : <a href="https://coolgirlshop.xyz/BOj8">Download Dataset</a><br />

# Ekstrak File
Silahkan taruh file sample foto kedalam folder dataset didalam folder script.

# Struktur File
<img src="https://github.com/fajarlabs/FaceMaskTrainingData/blob/master/Structure.PNG?raw=true" /><br />

# Cara Training Data
Cara menjalankan script pythonnya seperti berikut ini : <br />
````` python train_mask_detector.py --dataset dataset ````` <br />

Tunggu sampai proses training selesai, nanti otomatis akan menghasil file <b>mask_detector.model</b> di folder tersebut.<br />

<a href="https://ibb.co/yXRpMM1"><img src="https://i.ibb.co/TkT1nnS/cmd.png" alt="cmd" border="0"></a><br /><a target='_blank' href='https://imgbb.com/'>cd original</a><br />