02.06.2020

**Hatice Usta**
[Takip Edilebilecek Kişiler](https://github.com/Kodluyoruz51BootcampMVCCore/arastirma-odevi-HaticeUsta/blob/master/SOLIDPrensipleri.md#takip-edilebilecek-ki%C5%9Filer)
**51. İstanbul C#.Net Core ile MVC Bootcamp**

**ÖDEV 1**

# **Solid Prensipleri**

1-Single Responsibility Principle(Tek Sorumluluk Prensibi)

Bir sınıfın, fonksiyonun veya metodun tek bir görevi ya da sorumluluğu olmalıdır. Başka sınıfların görevini gerçekleştirilmemelidir.

Örneğin; Bir Car sınıfımız olduğunu düşünelim. Bu sınıfın içinde arabanın yapmasını beklediğimiz GoCar() ve StopCar() metotları olmalıdır. Burada EngineRunning( bool control ) metodu olmaması gerekir. Yani motorun çalışıp çalışmadığını bu sınıfta kontrol etmemeliyiz.

2- Open-Closed Principle(Açık-Kapalı Prensibi)

Bir programın veya entitiylerin geliştirilmeye açık ancak değiştirmeye kapalı olduğunu belirtir. İnterface ve abstract sınıfalar kullanılarak istenen eklemeler yapılabilir.

Örneğin; Verileri Excel ve Word belgesine gönderdiğimizi düşünelim. Başka bir durum oluştu ve bizim verileri PDF belgesine de göndermemiz gerekti. Tek yapmamız gereken bir tane Sender soyut sınıfımızdan türettiğimiz ExcelSend, WordSend ve PdfSend gibi sınıfların içindeki metodları gönderme işlemi yapacağımız metotta çağırmak olacak.

3-Liskov Substitution Principle(Liskov&#39; un Yerine Geçme Prensibi)

Bir ana sınıftan ya da sınıflardan türetilen sınıfların bir üst hiyerarşideki sınıfların yerine geçmesini esas alan bir prensiptir.

Örneğin; Bir ICar sınıfımız ve bu sınıftan türemiş AutoCar ve GearCar diye sınıflarımız var.

![](RackMultipart20200611-4-4bczss_html_2387cfc04a60b847.gif) ![](RackMultipart20200611-4-4bczss_html_2387cfc04a60b847.gif)

IFeature

Interface

workTube ()

ICar

Abstract Class

workGasoline ()

![](RackMultipart20200611-4-4bczss_html_2387cfc04a60b847.gif)

AutoCar: ICar

Class

workGasoline ()

![](RackMultipart20200611-4-4bczss_html_71dfcdd4821c5d58.gif)

GearCar: ICar,IFeature

Class

workGasoline ()

workTube()

4-Interface Segregation Principle(Arayüz ayrımı Prensibi)

Bir arayüze gerekli olmayan eklentilerin eklenmemesini belirten bir prensiptir. Arayüzde o an sadece kullanılacak olan eklentilerin ekli olaması gerektiğini anlatır.

Örneğin; Bmv ve Vosvos diye iki sınıfımız olsun. Bmv sınıfımızda Run(), Stop() ve OpenAirConditioning() metodları var fakat Vosvos sınıfımızda klima özelliği olmadığı için openAirConditioning() metodu olmayacak.

![](RackMultipart20200611-4-4bczss_html_2426c5c954953423.gif) ![](RackMultipart20200611-4-4bczss_html_2426c5c954953423.gif) ![](RackMultipart20200611-4-4bczss_html_17c945fd4225128e.gif) ![](RackMultipart20200611-4-4bczss_html_2426c5c954953423.gif)

Bmv: IVehicle,IFeature

Class

Run()

Stop()

OpenAirConditioning()

Vosvos:IVehicle

Class

Run()

Stop()

IFeature

İnterface

OpenAirConditioning()

IVehicle

İnterface

Run()

Stop()

5-Dependency Inversion Principle(Bağımlılıkların Terslenmesi Prensibi)

Varlıklar(Alt sınıflar ve Üst sınıflar) somut olmayan soyutlamalara bağlı olmalıdır. Üst seviye modülün düşük seviye modülüne bağlı olmamasını, ancak soyutlamalara bağlı olması gerektiğini belirtir. Alt sınıflarda yapılan değişiklikler üst sınıfları etkilememelidir.

Örneğin; C#&#39;ta kod yazdığımız sınıflardan örnek verebilirim. Mesela System sınıfının WriteLine sınıfına olan bağımlılığı araya Console sınıfı eklenerek bağımlılığı engellenmiştir. Böylece System sınıfında hiçbir değişiklik yapmadan ReadLine sınıfınında kullanabileceği hale getirilmiştir.

# **ÖDEV 2**

# **Takip Edilebilecek Kişiler**

**Lemi Orhan Ergin**

Programlama Bilgisi

Open Source, Software Design &amp; Architecture, Java, Groovy, Bash, PHP, C, JavaScript, Spring Framework, Ratpack, Grails, Restful Services, NoSQL solutions as MongoDB, Voldemort, CouchBase, EHCache, Hazelcast, Lucene, Compass, Mule ESB, MQs, Endeca, Heroku, Git, Linux and MacOS but never Windows!

Katıldığı Gruplar

Software Craftsmanship Turkey [http://meetup.scturkey.org/](http://meetup.scturkey.org/)

Agile Turkey [http://www.craftsummit.org/](http://www.craftsummit.org/)

[https://github.com/lemiorhan](https://github.com/lemiorhan)

**Cihan Özhan**

Programlama Bilgisi

Blockchain , Makine Öğrenimi , Derin Öğrenme, Bilgisayarla Görme

C # , Git (Golang) , Java ,

SQL Server , Oracle , PostgreSQL , T-SQL , PL / SQL

MongoDB, Redis, Cassandra, SQLite ,

ASP.NET (Çekirdek, WebForm, MVC) , Web API&#39;sı

Endüstri 4.0 (Karanlık / Akıllı Fabrika, Dijital Dönüşüm)

JavaScript , Node.js

Windows Phone 7-8 , Windows 8 Tablet , Android

WCF , XML Web Servisleri , JSON , XML, LINQ , Varlık Çerçevesi

GCP, AWS, Azure , Docker, Kubernetes

WPF , Silverlight , XAML , Windows Mağazası

Katıldığı Gruplar

IATHON (AI Hackathon) ~ Mentor Başkanı ( Check it out )

DevNot.com ~ Yazar

DijitalDonusum.co ~ Yardımcı Organizatör

YapayZeka.ai ~ Yazar

Medium @ BilisimHareketi ~ Yazar

[http://www.cihanozhan.com/cihan-ozhan/](http://www.cihanozhan.com/cihan-ozhan/)

[https://medium.com/@cihanozhan](https://medium.com/@cihanozhan)

[https://www.youtube.com/channel/UCLVt7YnGCbcYfJv\_QJmNnzg](https://www.youtube.com/channel/UCLVt7YnGCbcYfJv_QJmNnzg)

[https://github.com/cihanozhan](https://github.com/cihanozhan)

# **Takip Edilebilecek Etkinlik Grupları**

İstanbul Java User Group

[https://javausergroup.istanbul/](https://javausergroup.istanbul/)

[https://www.meetup.com/tr-TR/Istanbul-Java-User-Group/](https://www.meetup.com/tr-TR/Istanbul-Java-User-Group/)

İstanbul Java User Grup (JUG). Java Kullanıcı Grupları, Java ve teknolojileri konularında bilgi paylaşımı ve işbirliğini artırmak amacıyla dünyanın dört bir yanında kurulan toplulukçuklardır. Her JUG, kendi içinde etkinlikler yaptığı gibi, herhangi bir ya da daha fazla JUG ile birlikte etkinlikler düzenleyebilir ya da konuk konuşmacı gibi yardımlaşmalar yapabilir. Kendi içinde bir topluluk olan JUG&#39;lar, dışarıda da tek bir toplulukmuş gibi hareket etmeye çalışırlar.

İstanbul Open Agile

[https://www.meetup.com/tr-TR/Istanbul-Open-Agile-Meetup/](https://www.meetup.com/tr-TR/Istanbul-Open-Agile-Meetup/)

[https://openagileturkey.org/](https://openagileturkey.org/)

![](RackMultipart20200611-4-4bczss_html_cea8b7d405ca83d5.png)

# **ÖDEV 3**

# **Microsoft Build Etkinlikleri**

(İngilizcem yeterli olmadığı için anlamama rağmen 2&#39;şer kez izledim.)

OND3008

Advanced Application Lifecycle Management (ALM) capabilities

Evan Chaki , Microsoft

Shan McArthur , Microsoft

Per Mikkelsen , Microsoft

LIV13

Build a bot that integrates with your backend systems with Power Virtual Agent​

Marina Kolomiets , Microsoft

# **ÖDEV 4**

# **Microsoft Build 2020 Yenilikleri**

- Build 2020&#39;de operasyonel veritabanı hizmetlerini ve analitiği gerçek zamanlı olarak bir araya getiren  **Azure Synapse Link**  tanıtıldı. Maliyetleri düşüren ve zaman kazandıran Azure Synapse Link, veri hareketlerini yönetmeye gerek kalmadan müşterilerin değerli bilgiler elde etmesini sağlıyor.
- Geliştiricilerin Visual Studio ve Visual Studio Code&#39;dan Teams uygulamaları oluşturmaları ve yayınlamaları için  **Microsoft Teams&#39;e,**  yenilikler sunuldu. Bu yeni yetenekler BT yöneticilerinin Teams&#39;teki kullanıcıların iş kollarını ve ISV uygulamalarını değerlendirmesine ve iş dağılımı yapmasına olanak tanıyor.
- Yeni güncellemeler eklenen  **Fluid Framework, ** açık kaynak platformu olarak geliştiricilere sunulmaya başlandı. Böylece Office.com ve Web için Outlook&#39;taki Fluid bileşenleri de son kullanıcılara sağlanmış oldu.
- **Azure Machine Learning**  ve OSS araçlarına getirilen yeniliklerle müşterilerin yapay zekâ modellerini daha sorumlu bir şekilde kullanmasına yardımcı olmak için yeni Responsible ML (Sorumlu Makine Öğrenmesi) araçları sunuldu. Bu araç, model yorumlama yeteneğini geliştirerek veri güvenliğini ve kullanıcı gizliliği garanti altına alacak, yapay zeka sistemlerinin geliştirilmesinde sorumluluk anlayışını güçlendirecek.
- Etkinlikte, 1 milyar Windows 10 cihazında birlikte uygulama geliştirmeye yardımcı olmak için  **Project Reunion**  girişimi de tanıtıldı. Project Reunion, Win32 ve UWP API&#39;leri ile entegrasyonu kolaylaştırmak ve Windows 10 sürümleri kullanılan tüm cihazlarda çalışan kullanışlı uygulamalar geliştirmek üzere bir &quot;Windows geliştirici platformu&quot; olarak oluşturuldu.
- **Power Automate ** çözümüne kapsamlı düşük kodlu Robotik Proses Otomasyonu (RPA) teknolojisini sunmak için yatırımlarını sürdüren Microsoft, düşük kodlu ve kullanımı kolay RPA geliştirme ortamlarının lider sağlayıcısı  **Softomotive&#39;i**  satın aldı. Softomotive&#39;in teknolojisi, Microsoft müşterilerinin işlerini kolaylaştırmak için kullanıcı arayüzü akışlarına destek olan çözümler sunmaya başladı.
- Etkinlikte, Azure&#39;da yer alan dünyanın en güçlü  **süper yapay zekâ bilgisayarları** ndan birini de duyuruldu.  **OpenAI**  ile işbirliğiyle özel olarak geliştirilen bu süper bilgisayar gücünü Azure bulut altyapısından alıyor. Sistem, dağıtılmış devasa yapay zekâ modelleri geliştirmek için özel olarak tasarlandı.
- Visual Studio ürün ailesiyle Microsoft, her geliştiriciye sınıfının en iyisi araçları sağlanmaya devam ediyor. Build 2020&#39;de, yeni bir geliştirici kutusu kurmak, yeni bir projeye katılırken veya uzaktan çalışmaya geçerken ortak bir senaryo oluşturmak için  **Visual Studio Codespaces ** de tanıtıldı. VS Codespaces, geliştiricilerin dakikalar içinde tamamen yapılandırılmış geliştirme ortamları oluşturması için bulutun gücünden faydalanıyor.
- Geliştiricilerin bulut deneyimine kesintisiz kod sağlamak için, **GitHub Actions for Azure (Azure için GitHub Eylemleri)** platformuna yapılan yeni entegrasyonlar da duyuruldu. Ekiplerin iş akışlarını kolayca oluşturmasına, test edip yayınlamasına, dağıtmasına ve otomatikleştirmesine yardımcı olan 30&#39;dan fazla GitHub Eylemi geliştiricilere sunuldu.
- Build 2020&#39;de ayrıca Microsoft&#39;un sağlık sektörüne özgü ilk bulut hizmeti olan **Microsoft Cloud for Healthcare (Sağlık için Microsoft Bulut) **tanıtıldı. Hizmet, müşteriler ve iş ortaklarının hasta bakımını güçlendiriyor, bakım ekiplerinin bağlantılı hizmet yürütmesini sağlıyor; işbirliği, karar verme ve operasyonel verimliliği artırma yetenekleri sunuyor. Microsoft Cloud for Healthcare, Teams&#39;teki Bookings uygulaması gibi, sağlık kurumlarındaki çevrimiçi randevuları zamanlamaya ve yönetmeye yarayan araçlara destek sağlayacak.

**Platformlar uzaktan çalışmaya özel geliştiriliyor**

Bugün dünyanın en büyük 500 şirketinin %95&#39;inin kullandığı Azure, geliştiricilerin emekleriyle yeni özelliklere kavuştu. Yapay zekâ destekli botlarla güçlendirilen sağlık uygulamalarından üretim alanındaki dijital ikizlere; e-ticaret, akıllı perakende ve satış işlemlerine kadar Azure altyapısı, operasyonların uzaktan yapılabilmesini, simüle edilmesini ve otomatikleştirmesini sağlıyor. Microsoft 365 ile dünyanın insan merkezli; çok hizmetli, çok yönlü üretkenlik bulutunu geliştirmeye devam eden Microsoft, bu platform içinde sunduğu Teams ile günlük 75 milyon kullanıcıya ulaştı. Gerçek zamanlı gürültü kesme, parmak kaldıranı tespit etme, izinsiz katılımları engelleme; düşük bant internette kesintisiz hizmet verme gibi yeni özelliklerle Teams kullanımı önceki ayların 3 katına çıktı.

Yeni güncellemelerle birlikte Windows 10 işletim sisteminin aylık kullanıcı sayısı 1 milyarı yakaladı. Bu da Window&#39;u geliştiriciler için vazgeçilmez kılıyor. Bunların yanında, bugün, uygulamalar, botlar, iş akışları, gösterge panoları oluşturmak için Power Platform&#39;u kullanan 3,5 milyon kişi bulunuyor. Platform ile kullanıcılar kod kullanmadan uygulamalar geliştirebiliyor, Microsoft 365 ve Dynamics 365 verilerini özelleştirebiliyor.
