# celo01-Remote-Controlled-Vehicle-with-Metal-Detector
It is a tool that can be controlled by remote control, tracked by GPS, and manufactured to find metals.

TR|
  Bu aracı Çukurova Üniversitesi Elektrik-Elektronik Bölümü ortak bitirme projesi altında yaptık. Disiplinler arası bir proje olarak üretilmiştir. 

  Aracın Üzerinde bulunan sistem kısaca bir adet GPS NEO6M, bir adet LoraE32 433T20D, bir adet Metal Dedektörü, bir adet STM32F103C geliştirme kartı ve belirli miktarlarda voltaj regülatörü, led, direnç, buzzer ve klemenslerden oluşmaktadır.
  Bu sistemler aracın kumanda ile haberleşmesini, metal bulduğunda interrupta girerek kumandaya bilgi göndermesini, aracın hareket etmesini ve GPS konumlarını göndermekle görevlidir.

  Kumanda da ise bir adet 2.4 inç Nextion ekran, bir adet LoraE32 433T20D ve bir adette STM32F407VG geliştirme kartı bulunmaktadır. 
  Araç kumandası, aracın istenilen yönde hareket ettirmeyi (İleri-Geri-Sağa-Sola-Dur) sağlar. Nextion ekran ise bize aracın konumu ve metallerin konumu hakkında bilgi vermeyi sağlar.

  Projemiz başarılı şekilde çalışmıştır ve istenilen görevleri yerine getirmiştir.
  Projede Aracın kumanda kodlarını yazan arkadaşım Oğuz Kaan Ataya (@Mervoder) teşekkürlerimi iletirim. Kartın KiCad ile çizimini yapan arkadaşım Seyhun Çelik'e de teşekkürlerimi iletirim. 


  EN|
  We made this tool under the joint graduation project of the Department of Electrical and Electronics of Cukurova University. It is produced as an interdisciplinary project. 

  The system on the vehicle consists of a GPS NEO6M, a LoraE32 433T20D, a Metal Detector, a STM32F103C development board and a certain amount of voltage regulators, LEDs, resistors, buzzers and terminal blocks.
  These systems are responsible for communicating the vehicle with the controller, entering an interrupt when it finds metal, sending information to the controller, moving the vehicle and sending GPS locations.

  The controller also has a 2.4-inch Nextion display, a LoraE32 433T20D and a STM32F407VG development board. 
  The vehicle control allows the vehicle to move in the desired direction (Forward-Backward-Right-Left-Stop). The Nextion display, on the other hand, allows us to provide information about the position of the vehicle and the position of metals.

  Our project has worked successfully and has fulfilled the desired tasks.
  I would like to thank my friend Oguz Kaan Ataya (@Mervoder) who wrote the control codes of the vehicle in the project. I would also like to express my thanks to my friend Seyhun Çelik, who made the drawing of the card with KiCad. 
