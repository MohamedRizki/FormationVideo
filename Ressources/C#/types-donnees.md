# Types de données

> Tous les types en C# (référence, valeur, ...) héritent de la classe **Object**

|Type|Alias .NET|Place en mémoire|Fourchette de valeurs|
|:--:|:--|:--:|:--:|
|sbyte|System.SByte|1 octet|-128 à 127|
|short|System.Int16|2 octets|-32768 à 32767|
|int|System.Int32|4 octets|-2 147 483 648 à 2 147 483 647|
|long|System.Int64|8 octets|-9 223 372 036 854 775 808 à 9 223 372 036 854 775 807|
|byte|System.Byte|1 octet|0 à 255|
|ushort|System.UInt16|2 octets|0 à 65535|
|uint|System.UInt16|4 octets|0 à 4 294 967 295|
|ulong|System.UInt16|8 octets|0 à 18 446 744 073 709 551 615|

---

|Type|Alias .NET|Place en mémoire|Fourchette de valeurs|
|:--:|:--|:--:|:--:|
|char|System.Char|2 octets|U+0000 à U+FFFF|

---

|Type|Alias .NET|Place en mémoire|Fourchette de valeurs|
|:--:|:--|:--:|:--:|
|bool|System.Bool|1 octet|false (0) ou true (1)|

---

|Type|Alias .NET|Place en mémoire|Fourchette de valeurs|
|:--:|:--|:--:|:--:|
|float|System.Single|4 octets|±1,5.10<sup>−45</sup> à ±3,4.10<sup>38</sup> (~6 à 9 chiffres significatifs)|
|double|System.Double|8 octets|±5,0.10<sup>−324</sup> à ±1,7.10<sup>308</sup> (~15 à 17 chiffres significatifs)|
|decimal|System.Decimal|16 octets|±1,0.10<sup>-28</sup> à ±7,9228.10<sup>28</sup> (28 à 29 chiffres signficatifs)|

---

|Type|Alias .NET|Place en mémoire|Fourchette de valeurs|
|:--:|:--|:--:|:--:|
|string|System.String|-|caractères Unicode|