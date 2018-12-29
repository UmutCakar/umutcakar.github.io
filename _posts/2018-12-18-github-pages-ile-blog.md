---
layout: post
title: Github Pages ve Jekyll ile Blog Oluşturmak.
---


Merhabalar, blog oluşturmaya ve öğrendiklerimi burada paylaşmaya karar verdim.
İlk olarak Github Pages ve Jekyll ile blog nasıl oluşturulur göstermek istiyorum.

### Github Pages Nedir ?
Github, bizlere projelerimizi tanıtmak için yayınlayabileceğimiz 
bir hosting hizmeti vermektedir.

### Jekyll Nedir ?
Jekyll, GitHub tarafından Ruby dilinde geliştirilen basit bir 
sabit sayfa oluşturucu (static site generator) yazılımıdır.

Jekyll hazırlamış olduğumuz yazıyı static html sayfasına dönüştürmektedir.
GitHub Pages üzerinde ücretsiz yayınlayabiliriz.

Blog için de çok fazla kullanılmaktadır.

### Github Pages ve Jekyll ile blog kurmak.
Bu yazımda Github Pages ve Jekyll kullanarak blog sayfamı nasıl oluşturduğumu, 
daha sonra kendi github hesabım üzerinde nasıl yayınladığımı anlatacağım.

Bu yazı için sıfırdan tema yazmadım. Açık kaynak tema kullanacağım.

İlk olarak Github hesabımıza giriş yapıyoruz. 
Daha sonra ben hazır blog temasını [Jekyll Now repository](https://github.com/barryclark/jekyll-now)
kendi (Repositories) çalışma alanıma (Fork) kopyaladım.


![_config.yml]({{ site.baseurl }}/images/blog-1-github-fork.png)

Kendi çalışma alanımıza kopyalamış bulunmaktayız. Düzenlemelere başlayabiliriz.

Settings bölümün'den Repository name kısmını umutcakar.github.io olarak değiştirdim.
Daha sonra alt taraf da bulunan Github Pages kısmın'dan Source altında ki alanı 
master branch olarak değiştiriyoruz.

Artık sayfamızı görüntüleyebiliriz. :)

![_config.yml]({{ site.baseurl }}/images/dance.webp)

Şimdi tema'da biraz düzenleme yapalım.
Site adı, açıklama, profil resmi ve sosyal medya hesapları vb. alanlar 
_config.yml içerisinde bulunmaktadır.
Yazılar ise _posts klasorunun içerisinde bulunmaktadır.

Bir sonraki yazımda {kullanıcı adım}.github.io şeklinde olan adresi istediğimiz 
bir alan adı Custom Domain olarak nasıl kullanabilirizi anlatmayı planlıyorum.

Başka yazılarda tekrar görüşmek üzere.
