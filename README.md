# JMBAG
0036490364

#Pitanje 1
U Bin/Debugu se nalazi dvije nove datoteke, ekstenzija .dll i .pdb. Ako maknemo .dll file onda program vrati error jer ga ne moze pronaci, a zbog toga nemoze izvesti metodu PrintHelloWorld().
Poslao bi .exe i .dll svih klasa koje moj program koristi.

#Pitanje 2
Ispisuje ono sto je napisano u starijoj verziji. Zato sto se buildanjem stvara .dll file, a kako nismo buildali .dll file koji smo imali je stari.

#Pitanje 3
Pero: Hello World

#Pitanje 4
Da je u nju kopiran PeroClassLibrary.dll.

#Pitanje 5
Program i dalje radi. Aplikacija radi jer se u ...Bin/Debug folderu nalazi PeroClassLibrary.dll. Build radi zato sto je put do reference promjenjen na .../Bin/Debug.

#Pitanje 6
Aplikacija se normalno buildala. U ...Bin/Debug folderu nalazi se NodaTime.dll i NodaTime.xml.
U packages direktoriju se opet pojavio NodaTime folder

