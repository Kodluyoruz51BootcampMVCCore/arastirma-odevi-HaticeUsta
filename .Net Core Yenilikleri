# **Hatice Usta**

# **.NET Core 3.1&#39;deki yenilikler**

.NET Core 3.1 ile ilgili en önemli özellik, uzun vadeli bir destek (LTS) sürümü olmasıdır.

Uzun vadeli destek

.NET Core 3.1, önümüzdeki üç yıl boyunca Microsoft&#39;un desteğiyle bir LTS sürümüdür. Diğer önemli sürümlerin geçerli yaşam döngüsü aşağıdaki gibidir:

Yayınla Not

.NET Core 3.0 3 Mart 2020&#39;de yaşamın sonu.

.NET Core 2.2 23 Aralık 2019 tarihinde sona erecek.

.NET Core 2.1 21 Ağustos 2021&#39;de yaşamın sonu.

macOS appHost ve noterizasyon

yalnızca macOS

macOS için noterize .NET Core SDK 3.1 ile başlayarak, appHost ayarı varsayılan olarak devre dışı bırakılır

appHost ayarı etkinleştirildiğinde, .NET Core, oluşturduğunuzda veya yayımladığınızda yerel bir Mach-O oluşturur. Uygulamanız, dotnet run komutuyla kaynak kodundan çalıştırıldığında veya doğrudan Mach-O&#39;yu başlatarak appHost bağlamında çalışır.

appHost olmadan, bir kullanıcının çalışma süresine bağlı bir uygulamayı dotnet \&lt;filename.dll\&gt; başlatmasının tek yolu komuttur. Uygulamanızı bağımsız olarak yayımladığınızda her zaman bir appHost oluşturulur.

Ya proje düzeyinde appHost yapılandırabilirsiniz, ya da dotnet -p:UseAppHost parametre ile belirli bir komut için appHost geçiş:

Proje dosyası

\&lt;PropertyGroup\&gt;

\&lt;UseAppHost\&gt;true\&lt;/UseAppHost\&gt;

\&lt;/PropertyGroup\&gt;

Komut satırı parametresi

.NET Core CLI

dotnet run -p:UseAppHost=true

Windows Forms

Yalnızca Windows

Eski denetimler, bir süredir Visual Studio Designer Toolbox&#39;ta kullanılamayan Windows Formları&#39;na dahil edildi. Bunlar .NET Framework 2.0&#39;da yeni denetimlerle değiştirildi. Bunlar .NET Core 3.1 için Masaüstü SDK&#39;dan kaldırıldı.

| **Removed control** | **Recommended replacement** | **Associated APIs removed** |
| --- | --- | --- |
|
| |
|
| |
| DataGrid | [DataGridView](https://docs.microsoft.com/tr-tr/dotnet/api/system.windows.forms.datagridview) | DataGridCell
 DataGridRow
 DataGridTableCollection
 DataGridColumnCollection
 DataGridTableStyle
 DataGridColumnStyle
 DataGridLineStyle
 DataGridParentRowsLabel
 DataGridParentRowsLabelStyle
 DataGridBoolColumn
 DataGridTextBox
 GridColumnStylesCollection
 GridTableStylesCollection
 HitTestType |
| ToolBar | [ToolStrip](https://docs.microsoft.com/tr-tr/dotnet/api/system.windows.forms.toolstrip) | ToolBarAppearance |
| ToolBarButton | [ToolStripButton](https://docs.microsoft.com/tr-tr/dotnet/api/system.windows.forms.toolstripbutton) | ToolBarButtonClickEventArgs
 ToolBarButtonClickEventHandler
 ToolBarButtonStyle
 ToolBarTextAlign |
| ContextMenu | [ContextMenuStrip](https://docs.microsoft.com/tr-tr/dotnet/api/system.windows.forms.contextmenustrip) |
 |
| Menu | [ToolStripDropDown](https://docs.microsoft.com/tr-tr/dotnet/api/system.windows.forms.toolstripdropdown)
[ToolStripDropDownMenu](https://docs.microsoft.com/tr-tr/dotnet/api/system.windows.forms.toolstripdropdownmenu) | MenuItemCollection |
| MainMenu | [MenuStrip](https://docs.microsoft.com/tr-tr/dotnet/api/system.windows.forms.menustrip) |
 |
| MenuItem | [ToolStripMenuItem](https://docs.microsoft.com/tr-tr/dotnet/api/system.windows.forms.toolstripmenuitem) |
 |

C++/CLI

Yalnızca Windows

C++/CLI (&quot;yönetilen C++&quot; olarak da bilinir) projeleri oluşturmak için destek eklendi. Bu projelerden üretilen ikili ler .NET Core 3.0 ve sonraki sürümlerle uyumludur.

Visual Studio 2019 sürüm 16.4&#39;te C++/CLI desteği eklemek için, C++ iş yüküyle Masaüstü geliştirmeyi yükleyin. Bu iş yükü Visual Studio&#39;ya iki şablon ekler:

CLR Sınıf Kütüphanesi (.NET Çekirdek)

CLR Boş Proje (.NET Çekirdek)

Sonraki adımlar

.NET Core 3.0 ve 3.1 arasındaki kesme değişikliklerini gözden geçirin.

Windows Forms uygulamaları için .NET Core 3.1&#39;deki son dakika değişikliklerini gözden geçirin.

# **.NET Core 3.0&#39;daki yenilikler**

En büyük geliştirmelerden biri, Windows Masaüstü uygulamaları için destek içerir (yalnızca Windows). .NET Core 3,0 SDK bileşeni Windows Masaüstü &#39;nü kullanarak Windows Forms ve Windows Presentation Foundation (WPF) uygulamalarınızın bağlantı noktası oluşturabilirsiniz. Windows Masaüstü bileşeni yalnızca Windows &#39;da desteklenir ve Windows &#39;a dahildir.

.NET Core 3,0, C# 8,0 için destek ekler. Visual Studio 2019 sürüm 16,3 veya daha yeni bir sürümünü, Mac için Visual Studio 8,3 veya daha yenisini veya en son C# uzantısıyla Visual Studio Code kullanmanız önemle önerilir.

.NET Core RC1, Microsoft tarafından önceden hazırlanmıştı ve tam olarak desteklenmektedir. Önizleme sürümü kullanıyorsanız, devam eden destek için RTM sürümüne geçmeniz gerekir.

Dil geliştirmeleri C# 8,0

C# 8,0, null olabilen başvuru türleri özelliği, zaman uyumsuz akışlarve daha fazla deseniçeren bu sürümün bir parçasıdır. C# 8,0 özellikleri hakkında daha fazla bilgi için bkz. c# 8,0 &#39; dekiyenilikler.

Aşağıda ayrıntılı olarak açıklanan aşağıdaki API özelliklerini desteklemek için dil geliştirmeleri eklenmiştir:

Aralıklar ve dizinler

Zaman uyumsuz akışlar

.NET Standard 2,1

.NET Core 3,0 .NET Standard 2,1 uygular. Ancak, varsayılan dotnet new classlib şablon hala .NET Standard 2,0&#39; i hedefleyen bir proje oluşturur. .NET Standard 2,1&#39; i hedeflemek için proje dosyanızı düzenleyin ve özelliği şu TargetFramework şekilde değiştirin netstandard2.1 :

\&lt;Project Sdk=&quot;Microsoft.NET.Sdk&quot;\&gt;

\&lt;PropertyGroup\&gt;

\&lt;TargetFramework\&gt;netstandard2.1\&lt;/TargetFramework\&gt;

\&lt;/PropertyGroup\&gt;

\&lt;/Project\&gt;

Visual Studio kullanıyorsanız, Visual Studio 2017 .NET Standard 2,1 veya .NET Core 3,0&#39; i desteklemediğinden Visual Studio 2019 gerekir.

Derle/dağıt

Varsayılan yürütülebilir dosyalar

.NET Core artık çalışma zamanına bağımlı yürütülebilir dosyaları varsayılan olarak oluşturur. Bu davranış, .NET Core &#39;un küresel olarak yüklenen bir sürümünü kullanan uygulamalar için yenidir. Daha önce yalnızca kendi kendine kapsanan dağıtımlar yürütülebilir bir dosya üretecektir.

dotnet build veya sırasında dotnet publish , kullanmakta olduğunuz SDK ortamı ve platformuyla eşleşen bir çalıştırılabilir ( appHost) oluşturulur. Bu yürütülebilir dosyalarla aynı şeyleri, diğer yerel yürütülebilir dosyaları gibi bekleyebilir, örneğin:

Yürütülebilir dosyaya çift tıklayabilirsiniz.

Uygulamayı myapp.exe Windows ve ./myapp Linux ve MacOS gibi bir komut isteminden doğrudan başlatabilirsiniz.

macOS appHost ve notarlama

yalnızca macOS

MacOS için .NET Core SDK 3,0 &#39; den başlayarak, varsayılan bir yürütülebilir dosya (appHost) oluşturma ayarı varsayılan olarak devre dışıdır.

AppHost ayarı etkinleştirildiğinde, .NET Core, oluşturduğunuzda veya yayımladığınızda yerel bir MAC-O çalıştırılabilir dosyası oluşturur. Uygulamanız, komutuyla kaynak koddan çalıştırıldığında dotnet run veya mac-O yürütülebilir dosyasını doğrudan başlatarak appHost bağlamında çalışır.

AppHost olmadan, bir kullanıcıya çalışma zamanına bağımlı bir uygulama başlatabilir dotnet \&lt;filename.dll\&gt; . Uygulamanızı kendi içinde yayımladığınızda her zaman bir appHost oluşturulur.

AppHost &#39;yi proje düzeyinde yapılandırabilir veya parametresi ile belirli bir komut için appHost &#39; ı kapatabilirsiniz dotnet -p:UseAppHost :

Proje dosyası

\&lt;PropertyGroup\&gt;

\&lt;UseAppHost\&gt;true\&lt;/UseAppHost\&gt;

\&lt;/PropertyGroup\&gt;

Komut satırı parametresi

.NET Core CLI

dotnet run -p:UseAppHost=true

Tek dosya yürütülebilir dosyaları

dotnet publish komutu, uygulamanızı platforma özgü tek dosya yürütülebilir dosyasına paketlemeyi destekler. Yürütülebilir dosya kendiliğinden ayıklanıyor ve uygulamanızı çalıştırmak için gerekli tüm bağımlılıkları içerir. Uygulama ilk kez çalıştırıldığında uygulama adı ve derleme tanımlayıcısı temelinde bir dizine çıkarılır. Uygulama yeniden çalıştırıldığında başlatma daha hızlıdır. Yeni bir sürüm kullanılmadığı takdirde uygulamanın kendisi ikinci kez ayıklanmasına gerek yoktur.

\&lt;PropertyGroup\&gt;

\&lt;RuntimeIdentifier\&gt;win10-x64\&lt;/RuntimeIdentifier\&gt;

\&lt;PublishSingleFile\&gt;true\&lt;/PublishSingleFile\&gt;

\&lt;/PropertyGroup\&gt;

-veya-

.NET Core CLI

dotnet publish -r win10-x64 -p:PublishSingleFile=true

Bütünleştirilmiş kod bağlama

.NET Core 3,0 SDK, Il&#39;yi çözümleyerek ve kullanılmayan derlemeleri kırparak uygulamaların boyutunu azaltan bir araçla birlikte gelir.

.NET Core artık uygulamanızın Il &#39;sini taramak için Il bağlayıcı aracını kullanacak bir ayar içeriyor. Bu araç hangi kodun gerekli olduğunu algılar ve ardından kullanılmayan kitaplıkları kaldırır. Bu araç bazı uygulamaların dağıtım boyutunu önemli ölçüde azaltabilir.

Bu aracı etkinleştirmek için \&lt;PublishTrimmed\&gt; projenize ayarı ekleyin ve kendi içinde bulunan bir uygulamayı yayımlayın:

\&lt;PropertyGroup\&gt;

\&lt;PublishTrimmed\&gt;true\&lt;/PublishTrimmed\&gt;

\&lt;/PropertyGroup\&gt;

.NET Core CLI

dotnet publish -r \&lt;rid\&gt; -c Release

Örnek olarak, yayımlanan temel &quot;Merhaba Dünya&quot; yeni konsol projesi şablonu, yayımlandığında 70 MB ile çarpılır. Kullanarak \&lt;PublishTrimmed\&gt; , bu boyut yaklaşık 30 MB &#39;ye indirilir.

Tüm diğerleri üzerinde, kırpdıktan sonra uygulamanızı test ettiğinizden emin olun.

Katmanlı derleme

Katmanlı derleme (TC), .Net Core 3,0 ile varsayılan olarak açık olur. Bu özellik, çalışma zamanının daha iyi performans elde etmek için tam zamanında (JıT) derleyicisini daha kolay bir şekilde kullanmasına olanak sağlar.

Katmanlı derlemenin başlıca avantajı, daha düşük kalitede, ancak daha hızlı bir katmanda ya da daha yüksek kalitede, ancak daha yavaş bir katmanda çeşitli yöntemler elde etmenin iki yolunu sağlamaktır. TC, düzenli bir durum aracılığıyla başlangıçtan itibaren çeşitli yürütme aşamalarından geçen bir uygulamanın performansını artırmaya yardımcı olur. Katmanlı derleme devre dışı bırakıldığında, her yöntem, başlangıç performansı üzerinden düzenli durum performansına yol gösteren tek bir şekilde derlenir.

Hızlı JıT tarafından oluşturulan kod daha yavaş çalışabilir, daha fazla bellek ayırabilir veya daha fazla yığın alanı kullanabilir. Sorunlar varsa, proje dosyasında bu MSBuild özelliğini kullanarak hızlı JıT &#39;i devre dışı bırakabilirsiniz:

\&lt;PropertyGroup\&gt;

\&lt;TieredCompilationQuickJit\&gt;false\&lt;/TieredCompilationQuickJit\&gt;

\&lt;/PropertyGroup\&gt;

TC &#39;yi tamamen devre dışı bırakmak için, proje dosyanızda bu MSBuild özelliğini kullanın:

\&lt;PropertyGroup\&gt;

\&lt;TieredCompilation\&gt;false\&lt;/TieredCompilation\&gt;

\&lt;/PropertyGroup\&gt;

İpucu

Bu ayarları proje dosyasında değiştirirseniz, yeni ayarların yansıtılması için temiz bir derleme gerçekleştirmeniz gerekebilir ( obj ve bin dizinleri silin ve yeniden oluşturun).

Çalışma zamanında derlemeyi yapılandırma hakkında daha fazla bilgi için bkz. derleme Için çalışma zamanı yapılandırma seçenekleri.

ReadyToRun görüntüleri

Uygulama derlemelerinizi ReadyToRun (R2R) biçiminde derleyerek .NET Core uygulamanızın başlama süresini geliştirebilirsiniz. R2R, bir süre öncesi (AOT) derleme biçimidir.

R2R ikilileri, tam zamanında (JıT) derleyicisinin uygulamanız yüklenirken yapması gereken iş miktarını azaltarak başlangıç performansını geliştirir. Projenizi ReadyToRun olarak derlemek için aşağıdakileri yapın:

\&lt;PublishReadyToRun\&gt;Ayarı projenize ekleyin:

\&lt;PropertyGroup\&gt;

\&lt;PublishReadyToRun\&gt;true\&lt;/PublishReadyToRun\&gt;

\&lt;/PropertyGroup\&gt;

.NET Core CLI

dotnet publish -c Release -r win-x64 --self-contained

Platformlar arası/mimari kısıtlamaları

ReadyToRun derleyicisi Şu anda çapraz hedefleme &#39;yi desteklememektedir. Belirli bir hedefte derleme yapmanız gerekir. Örneğin, R2R görüntülerini Windows x64 için istiyorsanız, bu ortamda Yayımla komutunu çalıştırmanız gerekir.

Çapraz hedefleme için özel durumlar:

Windows x64, Windows ARM32, ARM64 ve x86 görüntülerini derlemek için kullanılabilir.

Windows x86, Windows ARM32 görüntülerini derlemek için kullanılabilir.

Linux x64, Linux ARM32 ve ARM64 görüntülerini derlemek için kullanılabilir.

Çalışma zamanı/SDK

Büyük sürüm çalışma zamanı ileri

.NET Core 3,0, uygulamanızın .NET Core &#39;un en son ana sürümüne iletmesini sağlayan bir katılım özelliği sunar. Ayrıca, geri alma &#39;nın uygulamanıza nasıl uygulandığını denetlemek için yeni bir ayar eklenmiştir. Bu, aşağıdaki yollarla yapılandırılabilir:

Proje dosyası özelliği:RollForward

Çalışma zamanı yapılandırma dosyası özelliği:rollForward

Ortam değişkeni:DOTNET\_ROLL\_FORWARD

Komut satırı bağımsız değişkeni:--roll-forward

Aşağıdaki değerlerden biri belirtilmelidir. Ayar atlanırsa, İkincil varsayılandır.

LatestPatch

En yüksek düzeltme eki sürümüne ilet. Bu, ikincil sürüm iletmeyi devre dışı bırakır.

Bazı

İstenen alt sürüm eksikse, en düşük düzeydeki sürüme ilet. İstenen ikincil sürüm varsa, Latestpatch ilkesi kullanılır.

Leri

İstenen ana sürüm eksikse, en düşük büyük sürüme ve en düşük alt sürüme ileri doğru alın. İstenen ana sürüm varsa, İkincil ilke kullanılır.

LatestMinor

İstenen alt sürüm mevcut olsa bile en yüksek düzeyde alt sürüme ilet. Bileşen barındırma senaryolarına yöneliktir.

Latestana

İstenen ana mevcut olsa bile, en yüksek büyük ve en yüksek düzeyde alt sürüme ilet. Bileşen barındırma senaryolarına yöneliktir.

Dıı

İleri alma. Yalnızca belirtilen sürüme bağlayın. Bu ilke, en son düzeltme eklerine iletme özelliğini devre dışı bıraktığından genel kullanım için önerilmez. Bu değer yalnızca test için önerilir.

Devre dışı bırak ayarının yanı sıra, tüm ayarlar kullanılabilir en yüksek düzeltme eki sürümünü kullanacaktır.

Derleme kopyaları bağımlılıkları

dotnet buildKomut artık, NuGet önbelleğinden uygulamanızın NuGet bağımlılıklarını yapı çıkış klasörüne kopyalar.

Yerel Araçlar

.NET Core 3,0 yerel araçları tanıtır. Yerel Araçlar genel araçlara benzerdir, ancak diskte belirli bir konum ile ilişkilendirilir. Yerel araçlar NuGet paketleri olarak dağıtılır.

Yeni Global. JSON seçenekleri

Global. JSON dosyası, hangi .NET Core SDK sürümünün kullanıldığını tanımlamaya çalışırken daha fazla esneklik sağlayan yeni seçeneklere sahiptir. Yeni seçenekler şunlardır:

allowPrerelease: SDK Çözümleyicisinin kullanılacak SDK sürümünü seçerken yayın öncesi sürümlerini düşünmesinin gerekip gerekmediğini belirtir.

rollForward: Bir SDK sürümü seçerken kullanılacak yuvarlama ilkesini, belirli bir SDK sürümü eksik olduğunda geri dönüş olarak veya daha yüksek bir sürümü kullanmak için bir yönerge olarak gösterir.

Daha küçük atık toplama yığın boyutları

Atık toplayıcısının varsayılan yığın boyutu daha az bellek kullanan .NET Core ile sonuçlanır. Bu değişiklik, modern işlemci önbelleği boyutları ile nesil 0 ayırma bütçesine göre daha iyi hizalanır.

Çöp toplama büyük sayfa desteği

Büyük sayfalar (Linux &#39;ta çok büyük sayfalar olarak da bilinir), işletim sisteminin bu büyük sayfaları isteyen uygulamanın performansını artırmak için yerel sayfa boyutundan (genellikle 4K) daha büyük bellek bölgeleri ayarlayabildiği bir özelliktir.

Çöp toplayıcı artık Windows üzerinde büyük sayfalar ayırmayı seçmek için bir katılım özelliği olarak Gclargepages ayarıyla yapılandırılabilir.

Windows Masaüstü &amp; COM

.NET Core SDK Windows Installer

Windows için MSI Yükleyicisi, .NET Core 3,0 ile başlayarak değiştirilmiştir. SDK yükleyicileri artık SDK özelliği bant sürümlerini yerinde yükseltecektir. Özellik bantları, sürüm numarasının Patch bölümündeki yüzlerce grupta tanımlanmıştır.

Windows masaüstü

.NET Core 3,0, Windows Presentation Foundation (WPF) ve Windows Forms kullanarak Windows masaüstü uygulamalarını destekler. Bu çerçeveler ayrıca, Windows UI XAML kitaplığı &#39;ndan (WinUI) xaml aracılığıyla modern denetimleri ve akıcı stil oluşturmayı da destekler.

Windows Masaüstü bileşeni, Windows .NET Core 3,0 SDK &#39;sının bir parçasıdır.

Aşağıdaki komutlarla yeni bir WPF veya Windows Forms uygulaması oluşturabilirsiniz dotnet :

dotnet new wpf

dotnet new winforms

Visual Studio 2019, .NET Core 3,0 Windows Forms ve WPF için Yeni proje şablonları ekler.

WinForms yüksek DPı

.NET Core Windows Forms uygulamaları, ile yüksek DPı modunu ayarlayabilir Application.SetHighDpiMode(HighDpiMode) . Bu SetHighDpiMode Yöntem, daha App.Manifest önce veya P/Invoke gibi diğer yollarla ayarlanmadığı takdirde, karşılık gelen yüksek DPI modunu ayarlar Application.Run .

COM bileşenleri oluşturma

Windows &#39;ta artık COM çağrılabilir yönetilen bileşenler oluşturabilirsiniz. Bu özellik, .NET Core &#39;un COM eklenti modelleriyle kullanılması ve ayrıca .NET Framework eşlik sağlanması açısından önemlidir.

Mscoree. dll &#39; nin com sunucusu olarak kullanıldığı .NET Framework aksine, .NET Core, com bileşenini oluştururken bin dizinine yerel bir başlatıcı dll &#39;si ekler.

Windows yerel birlikte çalışma

Windows, düz C API &#39;Leri, COM ve WinRT biçiminde zengin bir yerel API sunar. .NET Core P/Invoke&#39;ı destekleirken, .net Core 3,0, com API &#39;Leri oluşturma ve WinRT API &#39;leri etkinleştirmeözelliğini ekler.

MSIX dağıtımı

Msix yeni bir Windows uygulama paketi biçimidir. .NET Core 3,0 masaüstü uygulamalarını Windows 10 &#39; a dağıtmak için kullanılabilir.

Visual Studio 2019 &#39; de bulunan Windows uygulama paketleme projesi, kendi kendine içerilen .NET Core uygulamalarıyla msix paketi oluşturmanıza olanak sağlar.

.NET Core proje dosyası, özelliğindeki desteklenen çalışma zamanlarını belirtmelidir \&lt;RuntimeIdentifiers\&gt; :

\&lt;RuntimeIdentifiers\&gt;win-x86;win-x64\&lt;/RuntimeIdentifiers\&gt;

Linux geliştirmeleri

Linux için SerialPort

.NET Core 3,0, Linux üzerinde için temel desteği sağlar System.IO.Ports.SerialPort .

Daha önce, .NET Core yalnızca SerialPort Windows &#39;da kullanımı desteklenir.

Docker ve cgroup bellek sınırları

Docker ile Linux üzerinde .NET Core 3,0 çalıştırmak, cgroup bellek limitleriyle daha iyi çalışır. İle gibi bellek limitleriyle bir Docker kapsayıcısı çalıştırmak docker run -m , .NET Core &#39;un davranış şeklini değiştirir.

Varsayılan atık toplayıcı (GC) yığın boyutu: kapsayıcıda bellek sınırının en fazla 20 MB veya %75 &#39; si.

Açık Boyut, mutlak bir sayı veya cgroup sınırının yüzdesi olarak ayarlanabilir.

GC yığını başına en düşük ayrılmış kesim boyutu 16 MB &#39;tır. Bu boyut, makinelerde oluşturulan Heap sayısını azaltır.

Raspberry PI için GıO desteği

NuGet &#39;e GıO programlama için kullanabileceğiniz iki paket yayımlanmıştır:

System. Device. GIO

IoT. Device. Bindings

GPıO paketleri, GIO, SPI, I2Cve PWM cihazları için API &#39;ler içerir. IoT bağlamaları paketi cihaz bağlamalarını içerir.

ARM64 Linux desteği

.NET Core 3,0, Linux için ARM64 desteği ekler. ARM64 için birincil kullanım örneği şu anda IoT senaryolarıyla birlikte.

ARM64 üzerinde .NET Core Için Docker görüntüleri alp, de, ve Ubuntu için kullanılabilir.

Not

ARM64 Windows desteği henüz kullanılamıyor.

Güvenlik

TLS 1,3 &amp; Linux üzerinde OpenSSL 1.1.1

.NET Core artık, belirli bir ortamda kullanılabildiği OpenSSL 1.1.1 Içindeki TLS 1,3 desteğinin avantajlarından yararlanır. TLS 1,3:

İstemci ve sunucu arasında gereken azaltılan gidiş dönüşlerle bağlantı süreleri geliştirildi.

Kullanılmayan ve güvenli olmayan şifreleme algoritmalarının kaldırılması nedeniyle güvenlik geliştirildi.

Kullanılabilir olduğunda, .NET Core 3,0 bir Linux sisteminde OpenSSL 1.1.1, OpenSSL 1.1.0veya OpenSSL 1.0.2 kullanır. OpenSSL 1.1.1 kullanılabilir olduğunda, her ikisi System.Net.Security.SslStream de System.Net.Http.HttpClient tür TLS 1,3 kullanır (istemci ve sunucunun TLS 1,3&#39; i desteklediği varsayıldığında).

Önemli

Windows ve macOS henüz TLS 1,3&#39; i desteklemez. .NET Core 3,0, destek kullanılabilir hale geldiğinde bu işletim sistemlerinde TLS 1,3 &#39; i destekleyecektir.

Aşağıdaki C# 8,0 örneği, &#39; a bağlanan Ubuntu 18,10 üzerinde .NET Core 3,0 &#39; i göstermektedir https://www.cloudflare.com :

C#

using System;

using System.Net.Security;

using System.Net.Sockets;

using System.Threading.Tasks;

namespace whats\_new

{

public static class TLS

{

public static async Task ConnectCloudFlare()

{

var targetHost = &quot;www.cloudflare.com&quot;;

using TcpClient tcpClient = new TcpClient();

await tcpClient.ConnectAsync(targetHost, 443);

using SslStream sslStream = new SslStream(tcpClient.GetStream());

await sslStream.AuthenticateAsClientAsync(targetHost);

await Console.Out.WriteLineAsync($&quot;Connected to {targetHost} with {sslStream.SslProtocol}&quot;);

}

}

}

Şifreleme şifrelemeleri

.NET 3,0, ile ve sırasıyla uygulanan AES-GCM ve AES-CCM şifrelemeleri için destek ekler System.Security.Cryptography.AesGcm System.Security.Cryptography.AesCcm . Bu algoritmalar, Ilişki verileri (AEAD) algoritmalarıyla kimliği doğrulanmış şifrelemedir.

Aşağıdaki kod, AesGcm rastgele verileri şifrelemek ve şifrelerini çözmek için şifre kullanımını gösterir.

C#

using System;

using System.Linq;

using System.Security.Cryptography;

namespace whats\_new

{

public static class Cipher

{

public static void Run()

{

// key should be: pre-known, derived, or transported via another channel, such as RSA encryption

byte[] key = new byte[16];

RandomNumberGenerator.Fill(key);

byte[] nonce = new byte[12];

RandomNumberGenerator.Fill(nonce);

// normally this would be your data

byte[] dataToEncrypt = new byte[1234];

byte[] associatedData = new byte[333];

RandomNumberGenerator.Fill(dataToEncrypt);

RandomNumberGenerator.Fill(associatedData);

// these will be filled during the encryption

byte[] tag = new byte[16];

byte[] ciphertext = new byte[dataToEncrypt.Length];

using (AesGcm aesGcm = new AesGcm(key))

{

aesGcm.Encrypt(nonce, dataToEncrypt, ciphertext, tag, associatedData);

}

// tag, nonce, ciphertext, associatedData should be sent to the other part

byte[] decryptedData = new byte[ciphertext.Length];

using (AesGcm aesGcm = new AesGcm(key))

{

aesGcm.Decrypt(nonce, ciphertext, tag, decryptedData, associatedData);

}

// do something with the data

// this should always print that data is the same

Console.WriteLine($&quot;AES-GCM: Decrypted data is {(dataToEncrypt.SequenceEqual(decryptedData) ? &quot;the same as&quot; : &quot;different than&quot;)} original data.&quot;);

}

}

}

Şifreleme anahtarı Içeri/dışarı aktarma

.NET Core 3,0, asimetrik ortak ve özel anahtarların standart biçimlerden içeri ve dışarı aktarılmasını destekler. X. 509.440 sertifikası kullanmanız gerekmez.

RSA, dsa, ECDSAve ecdıfıfiehellmangibi tüm anahtar türleri aşağıdaki biçimleri destekler:

Ortak Anahtar

X. 509.440 Subjectpublickeyınfo

Özel anahtar

PKCS # 8 Privatekeyınfo

PKCS # 8 Encryptedprivatekeyınfo

RSA anahtarları da şunları destekler:

Ortak Anahtar

PKCS # 1 RSAPublicKey

Özel anahtar

PKCS # 1 RSAPrivateKey

Dışarı aktarma yöntemleri DER kodlu ikili veriler oluşturur ve içeri aktarma yöntemleri aynı şekilde bekler. Bir anahtar, metin kullanımı kolay pek biçiminde depolanıyorsa, bir içeri aktarma yöntemi çağrılmadan önce çağıranın içerik Base64 olarak çözülmesi gerekecektir.

C#

using System;

using System.Security.Cryptography;

namespace whats\_new

{

public static class RSATest

{

public static void Run(string keyFile)

{

using var rsa = RSA.Create();

byte[] keyBytes = System.IO.File.ReadAllBytes(keyFile);

rsa.ImportRSAPrivateKey(keyBytes, out int bytesRead);

Console.WriteLine($&quot;Read {bytesRead} bytes, {keyBytes.Length - bytesRead} extra byte(s) in file.&quot;);

RSAParameters rsaParameters = rsa.ExportParameters(true);

Console.WriteLine(BitConverter.ToString(rsaParameters.D));

}

}

}

PKCS # 8 dosyaları ile incelenebilir System.Security.Cryptography.Pkcs.Pkcs8PrivateKeyInfo ve PFX/PKCS # 12 dosyaları ile incelenebilir System.Security.Cryptography.Pkcs.Pkcs12Info . PFX/PKCS # 12 dosyaları ile değiştirilebilir System.Security.Cryptography.Pkcs.Pkcs12Builder .

.NET Core 3,0 API değişiklikleri

Aralıklar ve dizinler

Yeni System.Index tür dizin oluşturmak için kullanılabilir. intBaşlangıçtan başlayarak bu saylardan bir tane veya sonundan daha fazla ^ sayan bir önek Işleci (C#) oluşturabilirsiniz:

C#

Index i1 = 3; // number 3 from beginning

Index i2 = ^4; // number 4 from end

int[] a = { 0, 1, 2, 3, 4, 5, 6, 7, 8, 9 };

Console.WriteLine($&quot;{a[i1]}, {a[i2]}&quot;); // &quot;3, 6&quot;

Ayrıca, System.Range Index biri başlangıç ve diğeri bitiş için olmak üzere iki değerden oluşan ve bir x..y Aralık Ifadesiyle (C#) yazılabilir bir tür de vardır. Daha sonra bir dilim üreten bir ile dizin oluşturabilirsiniz Range :

C#

var slice = a[i1..i2]; // { 3, 4, 5 }

Zaman uyumsuz akışlar

IAsyncEnumerable\&lt;T\&gt;Türü yeni bir zaman uyumsuz sürümüdür IEnumerable\&lt;T\&gt; . Dil, await foreach IAsyncEnumerable\&lt;T\&gt; öğelerini tüketmek ve yield return öğeleri oluşturmak için bunları kullanmak için kullanabilirsiniz.

Aşağıdaki örnek, zaman uyumsuz akışların hem üretimini hem de tüketimini gösterir. foreachBildirim zaman uyumsuz ve kendisi yield return çağıranlar için zaman uyumsuz akış üretmek için kullanır. Bu model (kullanılarak yield return ), zaman uyumsuz akışlar üretmek için önerilen modeldir.

C#

async IAsyncEnumerable\&lt;int\&gt; GetBigResultsAsync()

{

await foreach (var result in GetResultsAsync())

{

if (result \&gt; 20) yield return result;

}

}

await foreachAyrıca, zaman uyumsuz yineleyiciler da oluşturabilirsiniz, örneğin, IAsyncEnumerable/IAsyncEnumerator hem hem await de içinde kullanabileceğiniz bir yineleyici yield . Atılmalıdır, IAsyncDisposable ve gibi ÇEŞITLI BCL türlerini uygulayan &#39; i kullanabilirsiniz Stream Timer .

IEEE kayan nokta

Kayan nokta API &#39;Leri, ıeee 754-2008 düzeltmesine uymak üzere güncelleştiriliyor. Bu değişikliklerin amacı, tüm gerekli işlemleri kullanıma sunmaktır ve DAVRANıŞSAL &#39;in IEEE spec ile uyumlu olduklarından emin olmaktır.

Ayrıştırma ve biçimlendirme düzeltmeleri şunları içerir:

Her uzunlukta doğru şekilde ayrıştırma ve yuvarlama girişleri.

Doğru şekilde ayrıştırır ve negatif sıfır biçimlendirir.

Infinity NaN Büyük/küçük harfe duyarsız bir denetim yaparak ve uygunsa isteğe bağlı olarak daha önce izin vererek doğru şekilde ayrıştırılabilir + .

Yeni System.Math API &#39;ler şunlardır:

BitIncrement(Double)&#39;BitDecrement(Double)

nextUpVe nextDown IEEE işlemlerine karşılık gelir. Bunlar, girdiden daha büyük veya daha az (sırasıyla) karşılaştıran en küçük kayan nokta numarasını döndürür. Örneğin, Math.BitIncrement(0.0) döndürür double.Epsilon .

MaxMagnitude(Double, Double)&#39;MinMagnitude(Double, Double)

maxNumMagVe minNumMag IEEE işlemlerine karşılık gelen değeri, iki girişin büyüklüğüne daha büyük veya daha az (sırasıyla) döndürür. Örneğin, Math.MaxMagnitude(2.0, -3.0) döndürür -3.0 .

ILogB(Double)

logBBir integral değeri döndüren IEEE işlemine karşılık gelir, giriş parametresinin tamsayı taban 2 günlüğünü döndürür. Bu yöntem, ile aynı şekilde, floor(log2(x)) ancak en az yuvarlama hatasıyla yapılır.

ScaleB(Double, Int32)

scaleBBir tamsayı değeri alan IEEE işlemine karşılık gelir, etkin x \* pow(2, n) olarak döner, ancak en az yuvarlama hatasıyla yapılır.

Log2(Double)

log2IEEE işlemine karşılık gelen 2 tabanında logaritmasını döndürür. Yuvarlama hatasını en aza indirir.

FusedMultiplyAdd(Double, Double, Double)

fmaIEEE işlemine karşılık gelen bir fkullandınız çarpma eklemesi gerçekleştirir. Yani, (x \* y) + z tek bir işlem olarak yapılır, böylece yuvarlama hatasını en aza indirir. Bir örnek FusedMultiplyAdd(1e308, 2.0, -1e308) , döndürür 1e308 . Normal (1e308 \* 2.0) - 1e308 dönüşler double.PositiveInfinity .

CopySign(Double, Double)

copySignIEEE işlemine karşılık gelir, x , ancak işaretini döndürür y .

.NET platforma bağımlı Iç bilgiler

SIMD veya bit işleme yönergesi kümeleri gibi belirli performans yönelimli CPU yönergelerine erişime izin veren API &#39;ler eklenmiştir. Bu yönergeler, verileri paralel şekilde işleme gibi belirli senaryolarda önemli performans geliştirmeleri elde etmenize yardımcı olabilir.

Uygun durumlarda, .NET kitaplıkları performansı artırmak için bu yönergeleri kullanmaya başlamıştır.

Geliştirilmiş .NET Core sürümü API &#39;Leri

.NET Core 3,0 ile başlayarak, .NET Core ile birlikte sunulan sürüm API &#39;Leri artık istediğiniz bilgileri döndürür. Örneğin:

C#

System.Console.WriteLine($&quot;Environment.Version: {System.Environment.Version}&quot;);

C#

System.Console.WriteLine($&quot;RuntimeInformation.FrameworkDescription: {System.Runtime.InteropServices.RuntimeInformation.FrameworkDescription}&quot;);

Uyarı

Son değişiklik. Bu teknik açıdan önemli bir değişiklik olduğundan, sürüm oluşturma düzeni değişti.

Hızlı yerleşik JSON desteği

.NET Kullanıcıları Newtonsoft. JSON ve DIĞER popüler JSON kitaplıklarına büyük ölçüde güvendi ve bu da iyi seçimler olmaya devam eder. Newtonsoft.Jsontemel veri türü olarak .NET dizelerini kullanır, bu da arada bulunan UTF-16 &#39; dır.

Yeni yerleşik JSON desteği yüksek performanslı, düşük ayırma, UTF-8 kodlu JSON metniyle birlikte çalışıyor. Ad alanı ve türleri hakkında daha fazla bilgi için System.Text.Json aşağıdaki makalelere bakın:

.NET &#39;te JSON serileştirme-genel bakış

.Net &#39;TE JSON serileştirmek ve serisini kaldırma.

Newtonsoft. JSON &#39;dan System. Text. JSON &#39;a geçiş

HTTP/2 desteği

System.Net.Http.HttpClient Türü http/2 protokolünü destekler. HTTP/2 etkinse HTTP protokol sürümü TLS/ALPN aracılığıyla görüşülür ve sunucunun bunu kullanabilmesi durumunda HTTP/2 kullanılır.

Varsayılan protokol HTTP/1.1 olarak kalır, ancak HTTP/2 iki farklı şekilde etkinleştirilebilir. İlk olarak http istek iletisini HTTP/2 kullanacak şekilde ayarlayabilirsiniz:

C#

var client = new HttpClient() { BaseAddress = new Uri(&quot;https://localhost:5001&quot;) };

// HTTP/1.1 request

using (var response = await client.GetAsync(&quot;/&quot;))

Console.WriteLine(response.Content);

// HTTP/2 request

using (var request = new HttpRequestMessage(HttpMethod.Get, &quot;/&quot;) { Version = new Version(2, 0) })

using (var response = await client.SendAsync(request))

Console.WriteLine(response.Content);

İkincisi, HttpClient Varsayılan olarak http/2 kullan seçeneğini kullanabilirsiniz:

C#

var client = new HttpClient()

{

BaseAddress = new Uri(&quot;https://localhost:5001&quot;),

DefaultRequestVersion = new Version(2, 0)

};

// HTTP/2 is default

using (var response = await client.GetAsync(&quot;/&quot;))

Console.WriteLine(response.Content);

Uygulama geliştirirken birçok kez şifrelenmemiş bağlantı kullanmak istersiniz. Hedef uç noktanın HTTP/2 kullanacağınızı biliyorsanız, HTTP/2 için şifrelenmemiş bağlantıları açabilirsiniz. DOTNET\_SYSTEM\_NET\_HTTP\_SOCKETSHTTPHANDLER\_HTTP2UNENCRYPTEDSUPPORTOrtam değişkenini 1 uygulama bağlamında etkinleştirerek veya olarak ayarlayarak bu ayarı açabilirsiniz:

C#

AppContext.SetSwitch(&quot;System.Net.Http.SocketsHttpHandler.Http2UnencryptedSupport&quot;, true);

# **.NET Core 2.2&#39;deki yenilikler**

.NET Core 2.2 uygulama dağıtımında geliştirmeler, çalışma zamanı hizmetleri için olay işleme, Azure SQL veritabanlarına kimlik doğrulama, Main JIT derleyici performansı ve yöntemin yürütülmesinden önce kod enjeksiyonu içerir.

Yeni dağıtım modu

.NET Core 2.2 ile başlayarak, .dll dosyaları yerine .exe dosyaları olan çerçeveye bağımlı yürütülebilir öğeleri dağıtabilirsiniz.

Bu yeni dağıtım modu, kitaplık yerine çalıştırılabilir bir uygulama oluşturmanın belirgin avantajına sahiptir, bu da uygulamanızı ilk önce aramadan dotnet doğrudan çalıştırabileceğiniz anlamına gelir.

Çekirdek

Çalışma zamanı hizmetlerinde olayları işleme

Uygulamanızı nasıl etkilediğini anlamak için uygulamanızın GC, JIT ve ThreadPool gibi çalışma zamanı hizmetlerini kullanımını sık sık izlemek isteyebilirsiniz. Windows sistemlerinde, bu genellikle geçerli işlemin ETW olayları izleyerek yapılır. Bu durum iyi çalışmaya devam etse de, düşük ayrıcalıklı bir ortamda veya Linux veya macOS&#39;ta çalışıyorsanız ETW&#39;yi kullanmak her zaman mümkün değildir.

.NET Core 2.2 ile başlayarak, CoreCLR System.Diagnostics.Tracing.EventListener olayları artık sınıf kullanılarak gerçekleştirebilirsiniz. Bu olaylar GC, JIT, ThreadPool ve interop gibi runtime hizmetlerinin davranışını açıklar. Bunlar CoreCLR ETW sağlayıcısının bir parçası olarak ortaya çıkan aynı olaylardır. Bu, uygulamaların bu olayları tüketmesine veya bunları bir telemetri toplama hizmetine göndermek için bir aktarım mekanizması kullanmasına olanak tanır. Aşağıdaki kod örneğinde olaylara nasıl abone olunur görebilirsiniz:

C#

internal sealed class SimpleEventListener : EventListener

{

// Called whenever an EventSource is created.

protected override void OnEventSourceCreated(EventSource eventSource)

{

// Watch for the .NET runtime EventSource and enable all of its events.

if (eventSource.Name.Equals(&quot;Microsoft-Windows-DotNETRuntime&quot;))

{

EnableEvents(eventSource, EventLevel.Verbose, (EventKeywords)(-1));

}

}

// Called whenever an event is written.

protected override void OnEventWritten(EventWrittenEventArgs eventData)

{

// Write the contents of the event to the console.

Console.WriteLine($&quot;ThreadID = {eventData.OSThreadId} ID = {eventData.EventId} Name = {eventData.EventName}&quot;);

for (int i = 0; i \&lt; eventData.Payload.Count; i++)

{

string payloadString = eventData.Payload[i]?.ToString() ?? string.Empty;

Console.WriteLine($&quot;\tName = \&quot;{eventData.PayloadNames[i]}\&quot; Value = \&quot;{payloadString}\&quot;&quot;);

}

Console.WriteLine(&quot;\n&quot;);

}

}

Buna ek olarak, .NET Core 2.2, EventWrittenEventArgs ETW olayları hakkında ek bilgi sağlamak için sınıfa aşağıdaki iki özelliği ekler:

EventWrittenEventArgs.OSThreadId

EventWrittenEventArgs.TimeStamp

Veriler

SqlConnection.AccessToken özelliğine sahip Azure SQL veritabanlarına AAD kimlik doğrulaması

.NET Core 2.2 ile başlayarak, Azure Active Directory tarafından verilen bir erişim belirteci, bir Azure SQL veritabanına kimlik doğrulamak için kullanılır. Erişim belirteçlerini desteklemek için AccessToken özellik sınıfa SqlConnection eklendi. AAD kimlik doğrulamadan yararlanmak için System.Data.SqlClient NuGet paketinin 4.6 sürümünü indirin. Özelliği kullanmak için, Microsoft.IdentityModel.Clients.ActiveDirectory NuGet paketinde yer alan .NET için Active Directory Authentication Library&#39;yi kullanarak erişim belirteci değerini elde edebilirsiniz.

JIT derleyici geliştirmeleri

Katmanlı derleme bir opt-in özelliği olmaya devam ediyor

.NET Core 2.1&#39;de, JIT derleyicisi yeni bir derleyici teknolojisi uyguladı, katmanlı derleme, bir opt-in özelliği olarak. Katmanlı derlemenin amacı geliştirilmiş performanstır. JIT derleyicisi tarafından gerçekleştirilen önemli görevlerden biri kod yürütmeyi en iyi duruma getirmektir. Ancak az kullanılan kod yolları için derleyici, en iyi duruma getirilmemiş kodu yürütme için çalışma süresiharcadığından daha fazla zaman geçirebilir.

Çalışma Zamanı

Ana yöntemi yürütmeden önce kod enjekte etme

.NET Core 2.2 ile başlayarak, bir uygulamanın Ana yöntemini çalıştırmadan önce kod enjekte etmek için bir başlangıç noktası kullanabilirsiniz. Başlangıç noktaları, bir ana bilgisayar için uygulamayı yeniden derlemeye veya değiştirmeye gerek kalmadan dağıtıldıktan sonra uygulamaların davranışını özelleştirmesini mümkün kılar.

Barındırma sağlayıcılarının, ana giriş noktasının yük davranışını etkileyebilecek davranışlar da dahil olmak üzere System.Runtime.Loader.AssemblyLoadContext özel yapılandırma ve ilke tanımlamasını bekliyoruz. Kanca, izleme veya telemetri enjeksiyonu kurmak, kullanım için geri aramalar ayarlamak veya çevreye bağlı diğer davranışları tanımlamak için kullanılabilir. Kanca giriş noktasından ayrıdır, böylece kullanıcı kodunun değiştirilmesi gerekmez.

# **.NET Core 2.1&#39;deki yenilikler**

Araçlar

.NET Core 2,1 &#39; de yer alan araç, .NET Core 2,1 SDK (v 2.1.300), aşağıdaki değişiklikleri ve geliştirmeleri içerir:

Derleme performansı iyileştirmeleri

.NET Core 2,1 &#39; nin önemli bir odağında, özellikle Artımlı derlemeler için derleme zamanı performansı geliştiriyoruz. Bu performans geliştirmeleri dotnet build , Visual Studio &#39;daki derlemeler ve için kullanılan komut satırı derlemeleri için geçerlidir. İyileşme özgü bazı alanlarda şunlar vardır:

Paket varlık çözümlemesi için, yalnızca tüm varlıklar yerine bir derleme tarafından kullanılan varlıkları çözümleme.

Derleme başvurularını önbelleğe alma.

Tek tek etkinleştirmeleri genelinde yayılan süreçler olan uzun süre çalışan SDK yapı sunucularının kullanımı dotnet build . Her çalıştırıldığında büyük kod bloklarını JıT derleme ihtiyacını ortadan kaldırır dotnet build . Yapı sunucusu işlemi aşağıdaki komutla otomatik olarak sonlandırılabilir:

.NET Core CLI

dotnet buildserver shutdown

Yeni CLı komutları

Artık .NET Core SDK bir parçası olarak, kullanılarak yalnızca proje bazında kullanılabilen birçok araç mevcuttur DotnetCliToolReference . Bu araçlar şunları içerir:

dotnet watch belirli bir komut kümesini yürütmeden önce bir dosyanın değiştirilmesini bekleyen bir dosya sistem izleyicisi sağlar. Örneğin, aşağıdaki komut, geçerli projeyi otomatik olarak yeniden oluşturur ve her bir dosya değiştiğinde ayrıntılı çıkış üretir:

.NET Core CLI

dotnet watch -- --verbose build

--Seçenekten önce gelen seçeneğe göz önüne alın --verbose . dotnet watch Alt işleme geçirilen bağımsız değişkenlerden doğrudan komutuna geçirilen seçenekleri ayırır dotnet . Bu seçenek olmadan, komut komutuna --verbose değil, dotnet watch komut için geçerlidir dotnet build .

dotnet dev-certsASP.NET Core uygulamalarında geliştirme sırasında kullanılan sertifikaları oluşturur ve yönetir.

dotnet user-secretsASP.NET Core uygulamalarında bir Kullanıcı gizli deposundaki gizli dizileri yönetir.

dotnet sql-cachedağıtılmış önbelleğe alma için kullanılacak bir Microsoft SQL Server veritabanında tablo ve dizinler oluşturur.

dotnet ef, DbContext Entity Framework Core uygulamalarında veritabanlarını, nesneleri ve geçişleri yönetmeye yönelik bir araçtır. Daha fazla bilgi için bkz. .NET komut satırı araçlarını EF Core.

Genel Araçlar

.NET Core 2.1, genel araçları destekler-diğer bir deyişle, komut satırından küresel olarak kullanılabilir özel araçlar. .NET Core &#39;un önceki sürümlerindeki genişletilebilirlik modeli, yalnızca kullanarak bir proje temelinde bulunan özel araçları kullanıma sunulmuştur DotnetCliToolReference .

Küresel bir araç yüklemek için DotNet aracı install komutunu kullanın. Örneğin:

.NET Core CLI

dotnet tool install -g dotnetsay

Yüklendikten sonra araç, araç adı belirtilerek komut satırından çalıştırılabilir.

Komutuyla araç yönetimi dotnet tool

.NET Core 2,1 SDK &#39;da tüm araçlar işlemleri dotnet tool komutunu kullanır. Aşağıdaki seçenekler mevcuttur:

dotnet tool installbir araç yüklemek için.

dotnet tool updateetkin bir şekilde güncelleştiren bir aracı kaldırmak ve yeniden yüklemek için.

dotnet tool listyüklü olan araçları listelemek için.

dotnet tool uninstallyüklü olan araçları kaldırmak için.

İleri al

.NET Core 2.0 ile başlayan tüm .NET Core Uygulamaları, bir sistemde yüklü en son alt sürüme otomatik olarak ileri doğru iletir.

.NET Core 2.0 ile başlayarak, bir uygulamanın derlenme .NET Core sürümü çalışma zamanında mevcut değilse, bir uygulama .NET Core 2,0 ile derlenir, ancak .NET Core 2,0 de ana bilgisayar sisteminde yoksa ancak .NET Core 2,1 ise, uygulama .NET Core 2,1 ile çalışır.

Önemli

Bu geri alma davranışı önizleme sürümleri için geçerlidir. Varsayılan olarak, ana yayınlar için de uygulanmaz, ancak bu, aşağıdaki ayarlarla değiştirilebilir.

Bu ayarı, üç şekilde değiştirebilirsiniz:

DOTNET\_ROLL\_FORWARD\_ON\_NO\_CANDIDATE\_FXOrtam değişkenini istenen değere ayarlayın.

Aşağıdaki satırı, istenen değeri . runtimeconfig. JSON dosyasına ekleyin:

JSON

&quot;rollForwardOnNoCandidateFx&quot; : 0

.NET Core CLIkullanırken, istenen değeri şu şekilde bir .NET Core komutuna ekleyin run :

dotnet run --rollForwardOnNoCandidateFx=0

Düzeltme Eki Sürümü ileri, bu ayardan bağımsızdır ve herhangi bir olası küçük veya büyük sürüm ileri doğru uygulandıktan sonra yapılır.

Dağıtım

Kendi içinde uygulama Bakımı

dotnet publishŞimdi, hizmet verilen çalışma zamanı sürümü ile bağımsız uygulamalar yayımlar. Bir bağımsız uygulamayı .NET Core 2,1 SDK (v 2.1.300) ile yayımladığınızda, uygulamanız ilgili SDK tarafından bilinen en son hizmet verilen çalışma zamanı sürümünü içerir. En son SDK &#39;ya yükselttiğinizde, en son .NET Core çalışma zamanı sürümü ile yayımlayabilirsiniz. Bu, .NET Core 1,0 çalışma zamanları ve üzeri için geçerlidir.

Kendi içinde yayımlama, NuGet.org üzerinde çalışma zamanı sürümlerini kullanır. Makinenizde bakım çalışma zamanına sahip olmanız gerekmez.

.NET Core 2,0 SDK &#39;sını kullanarak, özelliği aracılığıyla farklı bir sürüm belirtilmediği takdirde, kendi içinde bulunan uygulamalar .NET Core 2.0.0 Runtime ile yayımlanır RuntimeFrameworkVersion . Bu yeni davranışla birlikte, bu özelliği, otomatik olarak kapsanan bir uygulama için daha yüksek bir çalışma zamanı sürümü seçmek üzere ayarlamanıza gerek kalmaz. En kolay yaklaşım .NET Core 2,1 SDK (v 2.1.300) ile her zaman yayımlamaktır.

Windows Uyumluluk Paketi

.NET Framework mevcut koddan .NET Core &#39;a bağlantı oluşturduğunuzda Windows Uyumluluk Paketi&#39; ni kullanabilirsiniz. .NET Core &#39;da bulunandan daha fazla 20.000 API erişimi sağlar. Bu API &#39;Ler System.Drawing ad alanı, EventLog sınıf, WMI, performans sayaçları, Windows Hizmetleri ve Windows kayıt defteri türleri ve üyeleri türlerini içerir.

JıT derleyicisi geliştirmeleri

.NET Core, performansı önemli ölçüde iyileştirebilen katmanlı derleme ( Uyarlamalı iyileştirmeolarak da bilinir) adlı yeni bir JIT Derleyici teknolojisini içerir. Katmanlı derleme, bir katılım ayarıdır.

JıT derleyicisi tarafından gerçekleştirilen önemli görevlerden biri, kod yürütmeyi iyileştiriliyor. Ancak, daha az kullanılan kod yolları için, derleyici en iyi duruma getirilmiş kodu çalıştırmaya kıyasla kodu en iyi duruma getirmek için daha fazla zaman harcayabilir. Katmanlı derleme JıT derlemesinde iki aşama sunar:

Mümkün olduğunca hızlı bir şekilde kod üreten ilk katman.

Sık çalıştırılan yöntemler için iyileştirilmiş kod üreten ikinci bir katman. İkinci derleme katmanı, gelişmiş performans için paralel olarak gerçekleştirilir.

Katmanlı derlemeyi iki şekilde seçebilirsiniz.

Katmanlı derlemeyi .NET Core 2,1 SDK kullanan tüm projelerde kullanmak için aşağıdaki ortam değişkenini ayarlayın:

COMPlus\_TieredCompilation=&quot;1&quot;

Katmanlı derlemeyi proje başına temelinde kullanmak için, \&lt;TieredCompilation\&gt; \&lt;PropertyGroup\&gt; Aşağıdaki örnekte gösterildiği gibi, özelliği MSBuild proje dosyasının bölümüne ekleyin:

\&lt;PropertyGroup\&gt;

\&lt;!-- other property definitions --\&gt;

\&lt;TieredCompilation\&gt;true\&lt;/TieredCompilation\&gt;

\&lt;/PropertyGroup\&gt;

API değişiklikleri

Span\&lt;T\&gt; ve Memory\&lt;T\&gt;

.NET Core 2,1, diziler ve diğer bellek türleriyle çalışmayı çok daha verimli hale getirmek için bazı yeni türler içerir. Yeni türler şunlardır:

System.Span\&lt;T\&gt; ve System.ReadOnlySpan\&lt;T\&gt;.

System.Memory\&lt;T\&gt; ve System.ReadOnlyMemory\&lt;T\&gt;.

Bu türler olmadan, bu tür öğeleri bir dizinin bir bölümü veya bir bellek arabelleğinin bir bölümü olarak geçirirken, bir yönteme geçirmeden önce verilerin bir kısmının kopyasını oluşturmanız gerekir. Bu türler, ek bellek ayırma ve kopyalama işlemlerine gereksinimi ortadan kaldıran bu verilerin sanal bir görünümünü sağlar.

Aşağıdaki örnek, bir Span\&lt;T\&gt; Memory\&lt;T\&gt; dizi 10 öğenin sanal görünümünü sağlamak için ve örneğini kullanır.

C#

using System;

class Program

{

static void Main()

{

int[] numbers = new int[100];

for (int i = 0; i \&lt; 100; i++)

{

numbers[i] = i \* 2;

}

var part = new Span\&lt;int\&gt;(numbers, start: 10, length: 10);

foreach (var value in part)

Console.Write($&quot;{value} &quot;);

}

}

// The example displays the following output:

// 20 22 24 26 28 30 32 34 36 38

Brotli sıkıştırma

.NET Core 2,1, Brotli sıkıştırma ve açma için destek ekler. Brotli, RFC 7932 &#39; de tanımlanan ve çoğu Web tarayıcısı ve ana Web sunucusu tarafından desteklenen genel amaçlı kayıpsız bir sıkıştırma algoritmasıdır. Stream tabanlı System.IO.Compression.BrotliStream sınıfı veya yüksek performanslı yayılma tabanlı System.IO.Compression.BrotliEncoder ve System.IO.Compression.BrotliDecoder sınıfları kullanabilirsiniz. Aşağıdaki örnek, sınıfıyla sıkıştırmayı gösterir BrotliStream :

C#

public static Stream DecompressWithBrotli(Stream toDecompress)

{

MemoryStream decompressedStream = new MemoryStream();

using (BrotliStream decompressionStream = new BrotliStream(toDecompress, CompressionMode.Decompress))

{

decompressionStream.CopyTo(decompressedStream);

}

decompressedStream.Position = 0;

return decompressedStream;

}

BrotliStreamDavranışı DeflateStream ve ile aynıdır ve GZipStream Bu API &#39;leri çağıran kodu dönüştürmeyi kolaylaştırır BrotliStream .

Yeni şifreleme API &#39;Leri ve şifreleme geliştirmeleri

.NET Core 2,1, şifreleme API &#39;Lerinde çok sayıda geliştirme içerir:

System.Security.Cryptography.Pkcs.SignedCmsSystem. Security. Cryptography. Pkcs paketinde kullanılabilir. Uygulama, SignedCms .NET Framework sınıfıyla aynıdır.

Ve yöntemlerinin yeni aşırı yüklemeleri, X509Certificate.GetCertHash X509Certificate.GetCertHashString ÇAĞıRANLARıN SHA-1 dışındaki algoritmaları kullanarak sertifika parmak izi değerlerini almasını sağlamak için bir karma algoritma tanımlayıcısı kabul eder.

Yeni Span\&lt;T\&gt; tabanlı şifreleme API &#39;leri, karma, HMAC, şifreleme rastgele sayı oluşturma, asimetrik imza oluşturma, asimetrik imza işleme ve RSA şifrelemesi için kullanılabilir.

Performansı, System.Security.Cryptography.Rfc2898DeriveBytes tabanlı bir uygulama kullanılarak %15 oranında artmıştır Span\&lt;T\&gt; .

Yeni System.Security.Cryptography.CryptographicOperations Sınıf iki yeni yöntem içerir:

FixedTimeEqualsaynı uzunlukta olan iki giriş için geri dönüş için sabit bir zaman alır. Bu, zamanlama tarafı kanal bilgilerine katkıda bulunmaktan kaçınmak için şifreleme doğrulamasında kullanılması uygun hale getirir.

ZeroMemory, iyileştirelemeyen bir bellek temizleme yordamdır.

Statik RandomNumberGenerator.Fill Yöntem bir Span\&lt;T\&gt; değerini rastgele değerlerle doldurur.

System.Security.Cryptography.Pkcs.EnvelopedCmsArtık Linux ve macOS &#39;ta desteklenmektedir.

Eliptik Eğri Diffie-Hellman (ECDH) artık System.Security.Cryptography.ECDiffieHellman sınıf ailesinde kullanılabilir. Yüzey alanı .NET Framework ile aynıdır.

Tarafından döndürülen örnek RSA.Create , BIR SHA-2 Özeti kullanarak OAEP ile şifreleyebilir veya şifresini çözebilir, ayrıca RSA-PSS kullanarak imzaları oluşturabilir veya doğrulayabilir.

Yuva geliştirmeleri

.NET Core, System.Net.Http.SocketsHttpHandler System.Net.Http.HttpMessageHandler daha üst düzey ağ API &#39;lerinin temelini oluşturan yeni bir tür ve yeniden yazma içerir. System.Net.Http.SocketsHttpHandlerÖrneğin, uygulamanın temelini oluşturur HttpClient . .NET Core &#39;un önceki sürümlerinde, daha üst düzey API &#39;Ler yerel ağ uygulamalarına dayalıdır.

SocketsHttpHandler, .NET Core 2,1 &#39; de varsayılan uygulamasıdır. Ancak, yöntemini çağırarak uygulamanızı eski sınıfı kullanacak şekilde yapılandırabilirsiniz HttpClientHandler AppContext.SetSwitch :

C#

AppContext.SetSwitch(&quot;System.Net.Http.UseSocketsHttpHandler&quot;, false);

Ayrıca, &#39; yi temel alan yuva uygulamalarını kullanmaya geri çevirmek için bir ortam değişkeni de kullanabilirsiniz SocketsHttpHandler . Bunu yapmak için, öğesini DOTNET\_SYSTEM\_NET\_HTTP\_USESOCKETSHTTPHANDLER ya da 0 olarak ayarlayın false .

Windows &#39;da, System.Net.Http.WinHttpHandler bir yerel uygulamaya bağlı olan veya SocketsHttpHandler sınıfı bir örneği oluşturucuya geçirerek sınıfı kullanmayı da seçebilirsiniz HttpClient .

Linux ve macOS &#39;ta yalnızca HttpClient işlem başına temelinde yapılandırabilirsiniz. Linux &#39;ta, eski uygulamayı kullanmak istiyorsanız libkıvrık dağıtım yapmanız gerekir HttpClient . (.NET Core 2,0 ile yüklenir.)

# **.NET Core 2.0&#39;deki yenilikler**

.NET Core 2.0 aşağıdaki alanlarda ki geliştirmeleri ve yeni özellikleri içerir:

Araçlar

dotnet geri yükleme örtülü çalışır

.NET Core&#39;un önceki sürümlerinde, dotnet yeni komutuyla yeni bir proje oluşturduktan hemen sonra ve projenize yeni bir bağımlılık eklediğinizde bağımlılıkları indirmek için dotnet geri yükleme komutunu çalıştırmanız gerekiyordu.

Geri yükleme yapılmasını gerektiren dotnet restore tüm komutlar tarafından örtülü olarak çalıştırıldığı için çalıştırmak zorunda dotnet new dotnet builddeğilsiniz, dotnet publish, dotnet pack, dotnet run, dotnet test , ve . Örtülü geri yüklemeyi devre --no-restore dışı kalmak için seçeneği kullanın.

Komut, dotnet restore Azure DevOps Hizmetleri&#39;ndeki sürekli tümleştirme yapıları veya geri yükleme nin ne zaman gerçekleşacağını açıkça denetlemesi gereken yapı sistemleri gibi açıkça geri yüklemenin mantıklı olduğu belirli senaryolarda yine de yararlıdır.

NuGet akışlarının nasıl yönetilen hakkında bilgi için dotnet restore belgelere bakın.

--no-restore Ayrıca, new, run, build ,publish pack ve test komutları anahtarı dotnet restore geçirerek otomatik çağırma devre dışı edebilirsiniz.

.NET Core 2.0&#39;a yeniden hedefleme

.NET Core 2.0 SDK kuruluysa, .NET Core 1.x&#39;i hedefleyen projeler .NET Core 2.0&#39;a yeniden hedeflenebilir.

.NET Core 2.0&#39;ı yeniden hedeflemek için, öğenin \&lt;TargetFramework\&gt; (veya proje \&lt;TargetFrameworks\&gt; dosyanızda birden fazla hedefiniz varsa öğeyi) 1,x&#39;ten 2.0&#39;a değiştirerek proje dosyanızı düzenleme:

\&lt;PropertyGroup\&gt;

\&lt;TargetFramework\&gt;netcoreapp2.0\&lt;/TargetFramework\&gt;

\&lt;/PropertyGroup\&gt;

.NET Standart kitaplıklarını aynı şekilde .NET Standart 2.0&#39;a da yeniden hedefleyebilirsiniz:

\&lt;PropertyGroup\&gt;

\&lt;TargetFramework\&gt;netstandard2.0\&lt;/TargetFramework\&gt;

\&lt;/PropertyGroup\&gt;

Dil desteği

C# ve F#&#39;ı desteklemenin yanı sıra .NET Core 2.0 Visual Basic&#39;i de destekler.

Visual Basic

.NET Core, sürüm 2.0 ile Visual Basic 2017&#39;yi destekliyor. Aşağıdaki proje türlerini oluşturmak için Visual Basic&#39;i kullanabilirsiniz:

.NET Core konsol uygulamaları

.NET Çekirdek sınıf kitaplıkları

.NET Standart sınıf kitaplıkları

.NET Çekirdek ünite test projeleri

.NET Core xUnit test projeleri

Örneğin, Visual Basic &quot;Hello World&quot; uygulaması oluşturmak için komut satırından aşağıdaki adımları yapın:

Konsol penceresi açın, projeniz için bir dizin oluşturun ve geçerli dizini yapın.

Komutu dotnet new console -lang vbgirin.

Komut, Program.vbadlı .vbproj Visual Basic kaynak kodu dosyasıyla birlikte dosya uzantısı olan bir proje dosyası oluşturur. Bu dosya &quot;Merhaba Dünya!&quot; dizesini yazmak için kaynak kodu içerir. konsol penceresine.

Komutu dotnet rungirin. .NET Core CLI, &quot;Hello World!&quot; mesajını görüntüleyen uygulamayı otomatik olarak derler ve yürütür. konsol penceresinde.

C# 7.1 desteği

.NET Core 2.0, c# 7.1&#39;i destekler ve bu özellikler şunlardır:

Yöntem, Main uygulama giriş noktası, async anahtar sözcüğü ile işaretlenebilir.

Çıkarılan tuple adları.

Varsayılan ifadeler.

Platform geliştirmeleri

.NET Core 2.0, .NET Core&#39;un yüklenmesini ve desteklenen işletim sistemlerinde kullanılmasını kolaylaştıran bir dizi özellik içerir.

Linux için .NET Core tek bir uygulamadır

.NET Core 2.0, birden fazla Linux dağıtımında çalışan tek bir Linux uygulaması sunar. .NET Core 1.x, dağıtıma özel bir Linux uygulamasını indirmenizi zorunlu kattı.

Linux&#39;u tek bir işletim sistemi olarak hedefleyen uygulamalar da geliştirebilirsiniz. .NET Core 1.x, her Linux dağıtımına ayrı ayrı hedeflemeniz gerekir.

Apple şifreleme kitaplıkları için destek

MacOS&#39;ta .NET Core 1.x, OpenSSL araç setinin şifreleme kitaplığını gerekli kattı. .NET Core 2.0, Apple şifreleme kitaplıklarını kullanır ve OpenSSL gerektirmez, bu nedenle artık yüklemeniz gerekmez.

API değişiklikleri ve kitaplık desteği

.NET Standard 2.0 desteği

.NET Standardı, standardın bu sürümüne uygun .NET uygulamalarında bulunması gereken sürümlenmiş bir API kümesi tanımlar. .NET Standardı kitaplık geliştiricileri hedeflenebilmektedir. Her .NET uygulamasında .NET Standardının bir sürümünü hedefleyen bir kitaplığın kullanabileceği işlevselliği garanti etmeyi amaçlar. .NET Core 1.x .NET Standart sürüm 1.6 destekler; .NET Core 2.0 en son sürümü destekler, .NET Standart 2.0. Daha fazla bilgi için .NET Standard&#39; a bakın.

.NET Standart 2.0, .NET Standart 1.6&#39;da bulunandan 20.000&#39;den fazla API içerir. Bu genişletilmiş yüzey alanının çoğu,.NET Framework ve Xamarin&#39;de ortak olan API&#39;lerin .NET Standardına dahil edilmesinden kaynaklanır.

.NET Standart 2.0 sınıf kitaplıkları, .NET Standart 2.0&#39;da bulunan API&#39;leri aramaları koşuluyla .NET Framework sınıf kitaplıklarına da başvuru yapabilir. .NET Framework kitaplıklarının yeniden derlemesi gerekmez.

Son sürümünden bu yana .NET Standardına eklenen API&#39;lerin listesi için .NET Standart 1.6&#39;ya bakın.NET Standart 2.0 vs. 1.6.

Genişletilmiş yüzey alanı

.NET Core 2.0&#39;da bulunan toplam API sayısı .NET Core 1.1 ile karşılaştırıldığında iki kattan fazla artmıştır.

Ve .NET Framework&#39;den windows uyumluluk paketi taşıma ile de çok daha basit hale gelmiştir.

.NET Framework kitaplıkları için destek

.NET Core kodu, mevcut NuGet paketleri de dahil olmak üzere varolan .NET Framework kitaplıkları referans olabilir. Kitaplıkların .NET Standardı&#39;nda bulunan API&#39;leri kullanması gerektiğini unutmayın.

Visual Studio ile tümleştirme

Visual Studio 2017 sürüm 15.3 ve bazı durumlarda Mac için Visual Studio .NET Core geliştiricileri için önemli geliştirmeler sunar.

.NET Core uygulamalarını ve .NET Standart kitaplıklarını yeniden hedefleme

.NET Core 2.0 SDK yüklüyse, .NET Core 1.x projelerini .NET Core 2.0 ve .NET Standard 1.x kitaplıklarını .NET Standard 2.0&#39;a yeniden hedefleyebilirsiniz.

Visual Studio&#39;da projenizi yeniden hedeflemek için, projenin özellikleri iletişim kutusunun Uygulama sekmesini açar ve Hedef çerçeve değerini .NET Core 2.0 veya .NET Standard 2.0olarak değiştirirsiniz. Ayrıca, projeye sağ tıklayarak ve Düzenleme \*.csproj dosya seçeneğini seçerek değiştirebilirsiniz. Daha fazla bilgi için, bu konunun daha önceki Araçlama bölümüne bakın.

.NET Core için Live Unit Testing

Kodunuzu her değiştirdiğinizde, Canlı Birim Testi etkilenen birim testlerini arka planda otomatik olarak çalıştırArak sonuçları ve kod kapsamını Visual Studio ortamında canlı olarak görüntüler. .NET Core 2.0 artık Canlı Birim Testini destekliyor. Daha önce, Canlı Birim Testi yalnızca .NET Framework uygulamaları için mevcuttu.

Birden çok hedef çerçeve için daha iyi destek

Birden çok hedef çerçevesi için bir proje oluşturuyorsanız, artık üst düzey menüden hedef platformu seçebilirsiniz. Aşağıdaki şekilde, SCD1 adlı bir proje 64-bit macOS Xosx.10.11-x6410.11 ( ) ve 64-bitwin10-x64Windows 10/Windows Server 2016 ( hedefliyor. Bu durumda hata ayıklama oluşturmayı çalıştırmak için proje düğmesini seçmeden önce hedef çerçeveyi seçebilirsiniz.

.NET Core SDK&#39;lar için yan yana destek

Artık .NET Core SDK&#39;yı Visual Studio&#39;dan bağımsız olarak yükleyebilirsiniz. Bu, Visual Studio&#39;nun tek bir sürümünün .NET Core&#39;un farklı sürümlerini hedefleyen projeler oluşturmasını mümkün kılar. Daha önce, Visual Studio ve .NET Core SDK sıkıca birleştirilmiş; SDK&#39;nın belirli bir versiyonu Visual Studio&#39;nun belirli bir sürümüne eşlik etti.

Dokümantasyon geliştirmeleri

.NET Uygulama Mimarisi

.NET Application Architecture, oluşturmak için .NET&#39;i kullanırken rehberlik, en iyi uygulamalar ve örnek uygulamalar sağlayan bir dizi e-kitap&#39;a erişmenizi sağlar:

Mikrohizmetler ve Docker konteynerleri

ASP.NET ile Web uygulamaları

Xamarin ile mobil uygulamalar

Azure ile Bulut&#39;a dağıtılan uygulamalar
