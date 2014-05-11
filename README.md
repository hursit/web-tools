## Web Programlamada Kullandigim Onemli Araclarim

#### mpdf :
    Bir php kutuphanesi.Html sayfayi tam olarak olmasa da buyuk olcude pdf
    olarak bastiriyor. Kullanimi cok kolay.

    require_once('library/mpdf.php');
    $mpdf = new mPDF();
    $mpdf->WriteHTML('<p>Your first taste of creating PDF from HTML</p>');
    $mpdf->Output();
    exit;

#### nicEdit
    Textarea girdiler icin yazi editoru
    Diger editorlere gore cok avantajli
    Yazimiza resim ekleyip boyutlandirmamiza(Mozilla destekliyor, chromium
    desteklemiyor) imkan veriyor. Ayni zamanda bu resimler kendi sunucumuzda
    degil, nicEdit programinin sunucularinda tutuluyor. Diger editorlerin
    cogunda boyle bir ozellik yok
