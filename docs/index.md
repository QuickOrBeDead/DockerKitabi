---
title: Docker Kitabı
---

Docker Kitabı
=============

Docker Nedir?
=============

Docker açık kaynak kodlu bir **işletim sistemi seviyesinde sanallaştırma** yazılımıdır. Docker, uygulamaların yaratılması, konuşlandırılması (deployment) ve çalıştırılmasını, konteynerleri kullanarak kolaylaştırılmasını sağlayan bir araçtır. Konteynerler geliştirmecilerin uygulamalarını ve uygulamaların ihtiyaç duyduğu parçalarını paketleyerek çalıştırmalarını, dağıtmalarını ve konuşlandırmalarını (deployment) kolaylaştırır.

Docker öncelikle Linux için geliştirilmiştir. Linux çekirdeğinin (Linux kernel) **cgroups**  (Control Groups - Kontrol Grupları), **namespaces** (İsim Alanları) ve **OverlayFS** ve benzeri dosya sistemleri gibi kaynak yalıtım özelliklerini kullanır. Bu özellikler sayesinde Docker konteynerlerin aynı Linux işletim sistemi üzerinde izole bir şekilde çalıştırılmasını sağlanır. Linux çekirdeği İsim Alanları (**namespaces**); proses ağaçları (**Process Tree**), network, dosya sistemi ve user IDs (Kullanıcı İsim Alanları) gibi işletim sistemi ortamlarının izolasyonu için kullanılır. **cgroups** ise memory ve cpu gibi kaynakların yönetimi için kullanılır.

Docker sanal bir makineden farklı olarak, bütün bir sanal işletim sistemi oluşturmak yerine uygulamaların aynı Linux çekirdeğini kullanmasına izin verir. Bu şekilde önemli bir performans artışı sağlanır ve uygulamaların boyutu azalmış olur. Kurmak, yönetmek, yürütmek sanal makinelere göre daha hızlı ve basittir.

Konteyner Nedir?
================

Docker'a Giriş
==============

Tarihçe
=======

Kaynaklar
===========

1. <a href="https://en.wikipedia.org/wiki/Docker_(software)" target="_blank">https://en.wikipedia.org/wiki/Docker_(software)</a>
2. <a href="https://opensource.com/resources/what-docker" target="_blank">https://opensource.com/resources/what-docker</a>
3. <a href="https://www.profelis.com.tr/tr/blog/yazi/1139/container-bugunun-teknolojisi/" target="_blank">https://www.profelis.com.tr/tr/blog/yazi/1139/container-bugunun-teknolojisi/</a>
4. <a href="http://www.haifux.org/lectures/299/netLec7.pdf" target="_blank">http://www.haifux.org/lectures/299/netLec7.pdf</a>
