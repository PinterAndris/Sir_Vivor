# Sir_Vivor

Nagy házi feladat BME Deep learning (VITMAV45)

SÁRGACSEKK DIGITALIZÁLÁSA

A jelenleg feltöltött változat az előzetes változat.

E feladattal csupán az aláírás feltételeit szeretném teljesíteni. Mivel a csapat széthullott, egyedül dolgozom a projekten.

A feladathoz felhasznált segítségek:

    Az alapok:
    https://medium.com/@yash.kukreja.98/recognizing-handwritten-digits-in-real-life-images-using-cnn-3b48a9ae5e3
    
    Képszegmentáció:
    https://docs.opencv.org/2.4/doc/tutorials/imgproc/threshold/threshold.html
    https://docs.opencv.org/3.4/d9/d8b/tutorial_py_contours_hierarchy.html

A hálózatot keras használatával hoztam létre, az mnist adatbázison tanítottam, a tanítás során 97.8%-os pontosságot sikerült elérni három epoch alatt.
A hálózat működés sikerességéhez arra a képességre is szükség van, hogy a fényképen megtalálja a számokat. Ehhez opencv-t használtam. A fényképet szürkeárnyalatosra állítottam, és a pixelek aktivitása alapján terveztem kiszűrni azokat a képpontokat, amik a számjegyek ábrázolásának részei, azonban a fénykép árnyékossága megnehezítette ezt. Ha ez a probléma a továbbiakban is fennáll, akkor csak szkenneléssel összekötve lehet majd használni a programot.
