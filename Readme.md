# How to create QR codes for publication references  
Authors sometimes want to save space in scientific posters in the part of literature references or want to pimp the references by a fancy QR code. Interested readers can fetch additional information online from posters or hand-out sheets by any QR code-capable mobile devices like smartphones or tablets.

![Title](https://raw.githubusercontent.com/bohnelang/QRCode4PubMedPublications/main/imgs/qrexample2.jpg)

This small tutorial will show you how you can realise this.

## Create your URL
* Fetch all the PubMed-IDs of your publications:
![Title](https://raw.githubusercontent.com/bohnelang/QRCode4PubMedPublications/main/imgs/FindPMID.jpg)

* Build a PubMed search term:
	* For a single publication: **https://pubmed.ncbi.nlm.nih.gov/?term=11675023[ID]**
	(Most web browsers can resolve this link although the correct url-encoding looks like: https://pubmed.ncbi.nlm.nih.gov/?term=11675023%5BID%5D  (Take the  11675023 and add %5BID%5D at the end.)
    
	* for more than one publication : **https://pubmed.ncbi.nlm.nih.gov/?term=10498779,11675023[ID]**
	(Most web browsers can resolve this link although the correct url-encoding looks like:  https://pubmed.ncbi.nlm.nih.gov/?term=10498779%2c11675023%5BID%5D There is no space char between the PubMed-IDs and the commas.)

* Test the URL you composed in a real web browser.

## Create your QR code
Create a QR code image online - e.g. by RecodeMonkey https://www.qrcode-monkey.com/de/#more 
* Enter the URL ![Title](https://raw.githubusercontent.com/bohnelang/QRCode4PubMedPublications/main/imgs/recodemonkey1.jpg)
* Optional: Upload Logo ![Title](https://raw.githubusercontent.com/bohnelang/QRCode4PubMedPublications/main/imgs/recodemonkey2.jpg)
* Create a QR code  ![Title](https://raw.githubusercontent.com/bohnelang/QRCode4PubMedPublications/main/imgs/recodemonkey3.jpg)
* Execute a quick check ![Title](https://raw.githubusercontent.com/bohnelang/QRCode4PubMedPublications/main/imgs/recodemonkey5.jpg)
*  Download QR code image ![Title](https://raw.githubusercontent.com/bohnelang/QRCode4PubMedPublications/main/imgs/recodemonkey4.jpg)




``` --------------------------------------------------------------------------------------------------- ``` 

## Use PI (Persistent Identifiers) for  fulltext links!
When citing papers please use a DOI or URN or other persistent links to the fulltext. Avoid direct URL to the publisher page. Do not use publisher links like https://academic.oup.com/bioinformatics/article/15/9/767/229492 This kind of links often changes and tends to be volatile.

### Best-practice DOI (Digital Object in Internet)
* DOI: e.g  ```10.1093/bioinformatics/15.9.767``` 
	* Create a URL like this:  ```https://doi.org/10.1093/bioinformatics/15.9.767``` 
	* Create QR code like above 	
	* Use the QR code in the reference list:  ![Title](https://raw.githubusercontent.com/bohnelang/QRCode4PubMedPublications/main/imgs/qrexample2.jpg)

### Best-practice URN (Uniform Resource Name)
* URN: e.g. ```urn:nbn:de:0183-mbi0003721``` 
	* Create a URL like this: ```http://www.nbn-resolving.de/urn:nbn:de:0183-mbi0003721```
	* Create QR code like above 
	* Use the QR code in the reference list:  ![Title](https://raw.githubusercontent.com/bohnelang/QRCode4PubMedPublications/main/imgs/qrexample4.jpg)

``` --------------------------------------------------------------------------------------------------- ``` 


##  Empfohlene Literatur (in German)
```
Elke Lang, Andreas Bohne-Lang
Praxishandbuch IT-Grundlagen für Bibliothekare
Verlag: De Gruyter Saur; Auflage: 1 (Anfang 2019)
ISBN-13: 978-3110525878 

Kapitel:
3 Webtechnologie

3.4 Adressierung von Webressourcen: URI und URL
3.4.2 URL – Uniform Resource Locator
3.4.4 Erlaubte, verbotene und ersetzte Zeichen für eine URL

3.8 Bibliotheksrelevante Entwicklungen
3.8.1 OpenURL
3.8.2 Persistente Identifier (PI)
3.8.3 DOI – Digital Object Identifier
3.8.4 URN – Uniform Resource Name für Bibliotheken
3.8.5 Linkresolver

```
http://www.bohne-lang.de/praxisbuch_it-grundlagen_fuer_bibliothekare.php


