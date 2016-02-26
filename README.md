Redaxo 5 Addon - Adressverwaltung
=================================

Das Addon bindet die Möglichkeit eine Adresse inkl. Koordinaten (via Googlemaps) im Backend zu verwalten. Im Frontend kann man die gespeicherten Werte anschliessend über die nachfolgenden Methdoden auslesen und verwenden.

###Strasse

```
<?php
	echo rex_address::getStreet();
?>
```

###PLZ

```
<?php
	echo rex_address::getZipcode();
?>
```

###Ort

```
<?php
	echo rex_address::getCity();
?>
```

###Land

```
<?php
	echo rex_address::getCountry();
?>
```

###Breitengrad

```
<?php
	echo rex_address::getLatitude();
?>
```

###Längengrad

```
<?php
	echo rex_address::getLongitude();
?>
```