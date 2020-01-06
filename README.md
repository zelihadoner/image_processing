# image_processing
CNN NEDİR? CNN'lerin klasik bir kullanım örneği, bir evcil hayvanın görüntüsüne bakmak ve bir kedi mi yoksa köpek mi olduğuna karar vermek gibi görüntü sınıflandırması yapmaktır.

Günümüzde Computer Vision sorunları için kullanılan görüntüler genellikle 224x224 veya daha büyüktür. Bu büyüklükteki bir verinin eğitilmesi neredeyse imkansızdır. Bundan dolayı görüntü işlemede normal bir Sinir Ağ’ı değil CNN kullanmak daha mantıklı.

Hafta 14’de yazdığımız kodun çalışma mantığı:

Mnist veri kümesini import ettik.
Daha kullanışlı çıktılar elde etmek için Conv katmanları eklendi.
Havuzlama katmanlarını ekledik.
Çarpraz entropi kaybını kullanabilmemiz için softmax katmanını ekledik.
