## Zoo Management System
UML Practice

## Requirements

Bir hayvanat bahçesindeki hayvanlar hakkındaki bilgileri takip etmek için bir sistem tasarlıyorsunuz.

Hayvanlar:
Atlar (atlar, zebralar, eşekler vb.),
Kedigiller (kaplanlar, aslanlar vb.),
Kemirgenler (sıçanlar, kunduzlar vb.) gibi gruplardaki türlerle karakterize edilir.
Hayvanlar hakkında depolanan bilgilerin çoğu tüm gruplamalar için aynıdır.
tür adı, ağırlığı, yaşı vb.
Sistem ayrıca her hayvan için belirli ilaçların dozajını alabilmeli => getDosage ()
Sistem Yem verme zamanlarını hesaplayabilmelidir => getFeedSchedule ()
Sistemin bu işlevleri yerine getirme mantığı, her gruplama için farklı olacaktır. Örneğin, atlar için yem verme algoritması farklı olup, kaplanlar için farklı olacaktır.

Polimorfizm modelini kullanarak, yukarıda açıklanan durumu ele almak için bir sınıf diyagramı tasarlayın.

---

You are designing a system to track information about animals in a zoo.

Animals:
Animals are characterized by groups such as Horses (horses, zebras, donkeys, etc.),
Cats (tigers, lions, etc.),
Rodents (rats, beavers, etc.).
Most of the information stored about animals is the same for all groupings.
species name, weight, age, etc.
The system should also be able to retrieve the dosage of specific medications for each animal => getDosage()
The system should be able to calculate feeding times => getFeedSchedule()
The logic for performing these functions will be different for each grouping. For example, the feeding algorithm for horses will be different from that for tigers.

Using the polymorphism model, design a class diagram to address the scenario described above.