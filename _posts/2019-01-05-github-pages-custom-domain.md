---
layout: post
title: Github Pages Custom Domain ile kullanmak.
---


Merhabalar, bir önceki yazımızda Github Pages ile blog oluşturmuştuk.
Bu sefer Özel Domain ile nasıl kullanabilirizi göstermek istiyorum.

Öncelikle alan adına ihtiyacımız var alan adınızın olduğunu varsayıyorum.

### Adım 1 - Projemize Özel Domainimizi Ekleyelim.
Github profilime geliyorum. Burada çalışma alanım (Repositories) 
umutcakar.github.io oluşturmuş olduğum projemin içerisine giriyorum.
Daha sonra Settings içerisinde GitHub Pages altında Custom Domain yazan yere
alan adımı yazıp kaydediyorum.

![_config.yml]({{ site.baseurl }}/images/custom-domain-1.png)

### Adım 2 - CNAME düzenliyoruz.
Projemin içerisinde bulunan CNAME içerisine alan adımı yazıp kaydediyorum.

### Adım 3 - Alan adı aldığım sağlayıcıyıda A Kaydı düzenliyorum.
Alan adımı satın almış olduğum sağlayıcının paneline giriş yaptım.
Burada DNS içerisinde A Kaydı - Yönlendirilen Yer buraya şu değeri giriyoruz:
185.199.108.153 ve kaydediyoruz.


Bu işlem ile birlikte DNS yönlendirmemizi yapmış olduk.
Artık kendi alan adımız ile kullanabiliriz.

![_config.yml]({{ site.baseurl }}/images/custom-domain-finish.gif)
Başka yazılarda tekrar görüşmek üzere.
