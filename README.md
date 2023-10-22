# AI-Copilot-For-Understanding-Sign-Language
Menggunakan AI untuk membantu manusia memahami bahasa isyarat.

## Introduction
{: style="text-align: justify" }
Bahasa isyarat adalah bahasa yang digunakan untuk manusia yang tidak bisa menggunakan bahasa verbal seperti manusia tuli, bahasa isyarat menggunakan gerak tangan sebagai pertukaran informasi, gerak tangan yang di lakukan memiliki arti huruf alfabet dari a sampai z [1]. Menurut WHO, populasi manusia tuli di dunia sebanyak 1.5 juta jiwa atau sebanyak 20% dari total populasi dunia [2]. Dengan jumlah sebanyak itu manusia yang menggunakan sign language hanya sebanyak 70 juta jiwa [3]. Hal ini dikarenakan kurang banyaknya orang yang mengerti sign language sehingga kebanyakan orang tuli hanya biasa menggunakan pembacaan bibir dan menggunakan tulisan [4]. Kelemahan menggunakan bibir adalah keakurasian dalam membaca bibir seseorang dan kelemahan dari menggunakan tulisan adalah waktu yang diubutuhkan untuk menulis informasi. Oleh karena itu di buat AI untuk memahami sign language dan menrubahnya menjadi tulisan atau suara sehingga manusia tuli dan tidak tuli dapat berkomunikasi tanpa Batasan.

## End Goal
1.	AI dapat mengetahui arti dari sign language.
2.	Output dari AI dapat diubah menjadi text atau suara.

## How It Affect People
1.	Komunikasi dari orang tidak tuli dan tuli menjadi tanpa batsan dan dapat bertukar informasi.
2.	Membuka peluang bisnis baru embedded system untuk penerjemah sign language to speech or sign language to text.

## Metodologies
Metode yang di gunakan untuk membuat sistem AI ini adalah ditunjukkan oleh gambar di bawah.
![image](https://github.com/Muhamad-Febrian-Soambaton/AI-Copilot-For-Understanding-Sign-Language/assets/148663785/01d64f62-f903-400f-a274-03c2c0afe279)
CNN di gunakan untuk object detection dari sign language, di gunakan CNN adalah karena CNN dirancang untuk mendeteksi tepi sudut tergantung dari filter yang di gunakan dan fitur yang ingin di ekstrak. Hal itu sangat di butuhkan pada sign language karena sing language adalah pola dari tangan. CNN akan di latih menggunakan back propagation untuk mengupdate bobot dari jaringan sayarf tiruan. Setelah sign language di kenali dan berubah menjadi tulisan di lakukan LSTM untuk merubah tulisan menjadi suara atau text to speech. Outputnya adalah dapat berupa tulisan dan suara. 

## Conclusion
Banyak manusia yang membutuhkan bahasa isyarat namun bahasa isyarat jarang digunakan karena kuranga dimengertinya bahsa isyarat oleh manusia lain. Di gunakan AI untuk membantu manusia berkomunikasi dengan bahsa isyarat sehingga tidak ada pembatas dengan manusia yang tidak dapat menggunakan bahasa verbal dan nonverbal. Metode yang digunakan dalam pembuatan AI ini adalah CNN dan LSTM, CNN digunakan untuk mendeteksi sign language menjadi arti alphabet dan LSTM digunakan untuk mengubah alphabet menjadi tulisan.

## Reference
[1] https://id.wikipedia.org/wiki/Bahasa_isyarat

[2] https://www.who.int/health-topics/hearing-loss#tab=tab_2 

[3] https://earthweb.com/sign-language-users/ 

[4] https://www.accessibility.com/blog/do-all-deaf-people-use-sign-language#:~:text=Not%20only%20is%20there%20the,that%20provides%20for%20auditory%20cues. 


