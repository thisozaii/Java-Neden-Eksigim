# Java Neden Eksiğim ?

Merhaba dostum, bu konuyu okuduğuna göre buna gerçekten ihtiyacın var, bunu biliyorum. Bu yüzden en kısa yoldan ve en gerekli şeyleri burada bulabileceğin bir Java yol haritası hazırladım. Unutma, şartlar zaman ve yere göre değişebilir.

### 1. Adım:
Peki, burada olduğumuzu ve dilimizi belirlediğimizi ve biraz öğrendiğimizi varsayalım. Hangi IDE'yi (yani geliştirme ortamını) seçeceğiz?

Benim önerim: [IntelliJ IDEA](https://www.jetbrains.com/ides/)  <br>
Peki neden bunu önerdin?
> Çünkü modern, şık ve kullanışlı.

Beğenmezseniz Alternatifler: <br>
- [NetBeans](#netbeans)
- [Eclipse](#eclipse)

### 2. Adım:
IDE seçimimizi yaptık, şimdi ise alan seçeceğiz.

Başlıca Alanlar:
- [Web](#web)
- [Oyun](#oyun)
- [Masaüstü Uygulama](#masaüstü-uygulama)
- [Client / Server Side Uygulama](#client--server-side-uygulama)

### 3. Adım:
Java kapsamlı ve güncelleme alanı bir dil; her şeyi sana öğretmez, öğretemezler. Bu yüzden bazı öğrenmemiz gereken şeyler var. Bunun için [Java Bilinmeyenler](https://github.com/thisozaii/Java-Bilinmeyenler) reposunu ziyaret edebilirsiniz.

### Web
<!-- Web İçerik -->

| Araç / Framework | Web Sitesi | Logo |
|------------------|------------|------|
| Spring Framework | [Link](https://spring.io/projects/spring-framework) | ![Spring Framework Logo](https://img.shields.io/badge/-Spring_Framework-6DB33F?style=flat&logo=spring&logoColor=white) |
| Spring Boot      | [Link](https://spring.io/projects/spring-boot)       | ![Spring Boot Logo](https://img.shields.io/badge/-Spring_Boot-6DB33F?style=flat&logo=spring&logoColor=white) |
| Spark Framework  | [Link](http://sparkjava.com/)                       | ![Spark Framework Logo](https://img.shields.io/badge/-Spark_Framework-ff751a?style=flat&logo=apache&logoColor=white) |
| JavaServer Faces (JSF) | [Link](https://javaserverfaces.github.io/)          | ![JSF Logo](https://img.shields.io/badge/-JSF-FF5733?style=flat&logo=java&logoColor=white) |
| Apache Wicket    | [Link](https://wicket.apache.org/)                  | ![Apache Wicket Logo](https://img.shields.io/badge/-Apache_Wicket-EE6622?style=flat&logo=apache&logoColor=white) |
| Vaadin Framework | [Link](https://vaadin.com/)                          | ![Vaadin Logo](https://img.shields.io/badge/-Vaadin-00B4F0?style=flat&logo=vaadin&logoColor=white) |
| Play Framework   | [Link](https://www.playframework.com/)              | ![Play Framework Logo](https://img.shields.io/badge/-Play_Framework-FFD700?style=flat&logo=scala&logoColor=black) |

| Önerim           | Neden                                                                                     |
|------------------|-------------------------------------------------------------------------------------------|
| Spring Framework | Yaygın kullanımı, geniş topluluk desteği ve kapsamlı belgelendirmesi ile tanınır.       |
| Spring Boot      | Hızlı ve kolay başlatma süreci sağlar, ayrıca otomatik yapılandırma özelliğine sahiptir.|
| Spark Framework  | Hafif ve esnek yapısı, RESTful web servislerinin hızlı bir şekilde geliştirilmesini sağlar.|
| JavaServer Faces | Sunucu taraflı bileşen tabanlı web uygulamaları geliştirmek için mükemmel bir seçenektir. |
| Apache Wicket    | Temiz kodlama prensiplerine uygun, sürükle-bırak kullanıcı arayüzü tasarımı sağlar.      |
| Vaadin Framework | Sunucu taraflı Java kodunu kullanarak zengin kullanıcı arayüzleri oluşturur.             |
| Play Framework   | Ölçeklenebilir ve hızlı web uygulamaları geliştirmek için modern bir seçenektir.        |


### Oyun
| Kütüphane    | Açıklama                                                                                    | Web Sitesi                                      |
|--------------|---------------------------------------------------------------------------------------------|-------------------------------------------------|
| LWJGL        | Oyun geliştirme için birçok araç ve kütüphane sağlayan açık kaynaklı bir kütüphanedir.     | [Link](https://www.lwjgl.org/)                   |
| LibGDX       | Java ile oyun geliştirmek için popüler bir çerçevedir; 2D ve 3D oyunlar için kullanılabilir.| [Link](https://libgdx.badlogicgames.com/)       |
| jMonkeyEngine| Modern ve güçlü bir Java oyun motorudur; 3D oyunlar geliştirmek için kullanılabilir.       | [Link](https://jmonkeyengine.org/)               |
| Slick2D      | Hafif ve kullanımı kolay bir 2D oyun geliştirme kütüphanesidir; Java ile yazılmıştır.      | [Link](http://slick.ninjacave.com/)              |
| PlayN        | Çoklu platformlar için oyun geliştirmek için bir çerçevedir; Java ve diğer dillerle kullanılabilir. | [Link](https://github.com/playn/playn)      |


### Masaüstü Uygulama
| Araç / Kütüphane | Açıklama                                                                                  | Link                                                      |
|-------------------|-------------------------------------------------------------------------------------------|-----------------------------------------------------------|
| Swing             | Java'nın standart GUI kütüphanesidir ve masaüstü uygulamaları oluşturmak için kullanılır.| [Daha Fazla Bilgi](https://docs.oracle.com/javase/tutorial/uiswing/) |
| JavaFX            | Modern ve zengin masaüstü uygulamaları oluşturmak için kullanılan bir GUI aracıdır.     | [Daha Fazla Bilgi](https://openjfx.io/)                  |
| AWT               | Java'nın temel GUI kütüphanesidir ve Swing ve JavaFX'in alt yapısını oluşturur.         | [Daha Fazla Bilgi](https://docs.oracle.com/javase/7/docs/api/java/awt/package-summary.html) |
| FlatLaf           | Modern ve düz tasarımlı Swing ve JavaFX tema ve görünümleri sağlar.                      | [Daha Fazla Bilgi](https://www.formdev.com/flatlaf/)      |
| Apache Pivot      | Zengin internet uygulamaları ve masaüstü uygulamaları oluşturmak için bir framework sağlar. | [Daha Fazla Bilgi](https://pivot.apache.org/)          |
| JGoodies Forms    | Swing tabanlı kullanıcı arayüzlerinin oluşturulması için bir araçtır.                     | [Daha Fazla Bilgi](https://www.jgoodies.com/)            |
| JIDE Software     | Swing tabanlı profesyonel kullanıcı arayüzü bileşenleri sunar.                             | [Daha Fazla Bilgi](https://www.jidesoft.com/)            |
| JDic              | Java için bir masaüstü uygulama geliştirme kütüphanesidir.                                | [Daha Fazla Bilgi](https://sourceforge.net/projects/jdic/)|

### Client / Server Side Uygulama
| Kütüphane | Açıklama                                                                                  | Link                                                      |
|-----------|-------------------------------------------------------------------------------------------|-----------------------------------------------------------|
| Netty     | Netty, yüksek performanslı ağ uygulamaları geliştirmek için açık kaynaklı bir framework'tür. | [Daha Fazla Bilgi](https://netty.io/) |
| Vert.x    | Vert.x, reaktif ve çok amaçlı bir toolkit'tir ve yüksek performanslı, dağıtık ve koşut işlemli uygulamaları kolayca geliştirmek için kullanılır. | [Daha Fazla Bilgi](https://vertx.io/)            |
| MINA      | MINA (Multipurpose Infrastructure for Network Applications), ağ uygulamaları geliştirmek için kullanılan bir framework'tür ve NIO (New I/O) temelinde çalışır. | [Daha Fazla Bilgi](https://mina.apache.org/) |


### Ekstra Önemli Frameworkler 
| Framework / Kütüphane | Açıklama                                                                                  |
|------------------------|-------------------------------------------------------------------------------------------|
| Spring Framework       | Web uygulamaları, mikro servisler, RESTful servisler ve daha fazlası için kullanılır. Ayrıca Spring Boot, Spring tabanlı uygulamaların hızlı bir şekilde başlatılmasını ve yapılandırılmasını sağlar. |
| Hibernate              | Java uygulamaları için bir ORM (Object-Relational Mapping) aracıdır. Veritabanı işlemlerini kolaylaştırır ve Java nesnelerini ilişkisel veritabanlarına bağlar. |
| Apache Struts          | MVC (Model-View-Controller) mimarisini destekler ve web uygulamaları için kullanılır. Form işlemleri, veri doğrulama ve diğer web uygulaması gereksinimlerini kolaylaştırır. |
| JSF (JavaServer Faces)| Java EE standardı bir web framework'üdür ve bileşen tabanlı bir yapı sunar. Web uygulamalarının kullanıcı arayüzlerini oluşturmak için kullanılır. |
| Apache Wicket          | Web uygulamaları geliştirmek için bir framework'tür ve Java nesnelerini kullanarak dinamik web sayfaları oluşturmayı sağlar. |
| Apache Camel           | Entegrasyon ve mesajlaşma için hafif bir ESB (Enterprise Service Bus) framework'üdür. Farklı sistemler arasında veri entegrasyonunu kolaylaştırır. |
| Thymeleaf              | Java tabanlı web uygulamaları için bir şablon motorudur. HTML dosyalarına dinamik içerik eklemek için kullanılır ve Spring Framework ile kolayca entegre edilebilir. |
| Log4j / Logback        | Java uygulamaları için günlükleme (logging) çözümleridir. Hata ayıklama ve izleme için kullanılırlar ve çeşitli log düzeylerini desteklerler. |
| Apache Commons         | Genel amaçlı Java yardımcı programları koleksiyonudur. Dosya işleme, dize işleme, zamanlayıcılar gibi birçok alanda kullanışlı yardımcı sınıflar içerir. |
| Guava                  | Google'ın sağladığı Guava kütüphanesi, Java için kullanışlı yardımcı sınıflar ve araçlar içerir. Koleksiyonlar, fonksiyonel programlama araçları, caching ve daha fazlasını sağlar. |

### Builds : 
| Build Aracı | Açıklama                                                                                  | Link                                                      |
|-------------|-------------------------------------------------------------------------------------------|-----------------------------------------------------------|
| Apache Ant  | Apache Ant, XML tabanlı bir inşa aracıdır ve özellikle Java projeleri için kullanılır. Proje derleme, paketleme ve dağıtım işlemlerini otomatize etmek için kullanılır. | [Daha Fazla Bilgi](https://ant.apache.org/) |
| Apache Maven| Apache Maven, Java projelerinin yönetimi, derlenmesi ve bağımlılıklarının yönetimi için kullanılan popüler bir inşa aracıdır. | [Daha Fazla Bilgi](https://maven.apache.org/)            |
| Gradle      | Gradle, esnek bir inşa otomasyon aracıdır ve Java projeleri için bir alternatif olarak kullanılabilir. Groovy tabanlı bir DSL (Domain Specific Language) kullanır. | [Daha Fazla Bilgi](https://gradle.org/) |
| Bazel       | Google tarafından geliştirilen Bazel, çok dilli ve çok platformlu bir inşa aracıdır. Büyük ölçekli Java projeleri ve diğer diller için optimize edilmiştir. | [Daha Fazla Bilgi](https://bazel.build/) |
| Buck        | Buck, Facebook tarafından geliştirilen ve özellikle büyük Java projeleri için optimize edilmiş bir inşa aracıdır. Buck, hızlı ve paralel derleme sağlar. | [Daha Fazla Bilgi](https://buck.build/) |

