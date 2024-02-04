

# eDoklady
Klon aplikace [eDoklady](https://edoklady.gov.cz/) v [Apache Cordova](https://cordova.apache.org) pro Android a iOS

***Kopie*** aplikace [eDoklady](https://edoklady.gov.cz/), aplikace je poměrně rychle vytvořená, takže se nejedná o kopii 1:1, ale blíží se originálu.
#### Aplikace umožňuje:
- přihlášení přes [Bankovní Identitu](https://www.bankid.cz/) 
- zobrazení a načtení dat z Bankovní identity
- ochrana přihlášení PINem nebo otiskem prstu

# Screenshoty
<img src="https://github.com/zgruza/eDoklady/blob/main/Screenshots/1.jpg?raw=true" alt="eDoklady 1" width="20%" height="20%"> <img src="https://github.com/zgruza/eDoklady/blob/main/Screenshots/2.jpg?raw=true" alt="eDoklady 2" width="20%" height="20%"> <img src="https://github.com/zgruza/eDoklady/blob/main/Screenshots/3.jpg?raw=true" alt="eDoklady 3" width="20%" height="20%"> <img src="https://github.com/zgruza/eDoklady/blob/main/Screenshots/4.jpg?raw=true" alt="eDoklady 4" width="20%" height="20%"> <img src="https://github.com/zgruza/eDoklady/blob/main/Screenshots/5.jpg?raw=true" alt="eDoklady 5" width="20%" height="20%"> <img src="https://github.com/zgruza/eDoklady/blob/main/Screenshots/6.jpg?raw=true" alt="eDoklady 6" width="20%" height="20%"> <img src="https://github.com/zgruza/eDoklady/blob/main/Screenshots/7.jpg?raw=true" alt="eDoklady 7" width="20%" height="20%"> <img src="https://github.com/zgruza/eDoklady/blob/main/Screenshots/8.jpg?raw=true" alt="eDoklady 8" width="20%" height="20%"> <img src="https://github.com/zgruza/eDoklady/blob/main/Screenshots/9.jpg?raw=true" alt="eDoklady 9" width="20%" height="20%"> <img src="https://github.com/zgruza/eDoklady/blob/main/Screenshots/10.jpg?raw=true" alt="eDoklady 10" width="20%" height="20%">
## Zajímavé oficiální End-pointy aplikace eDoklady:
_Zjištěno při reverzi aplikace_

[TNIA](https://tnia.identitaobcana.cz/FPSTS/saml2/basic?SAMLRequest=1ZXBjtowEIbvlfoOke%2FEkIWtsAAphdIi0RYB7aE3x5kIq4md2uPtbp%2B%2BjoEA0i6VKu2Bk6XJ%2FL%2B%2FyUwmI8urMqlZ6nCn1vDLgcXosSqVZfsnY%2BKMYppbaZniFViGgm3Sz0uWxF1WG41a6JKca65LuLVgUGpFosVsTGQ%2BuB%2FcJ1kPBgOR9Xk%2FH8Ld3TDLRMH7xQCShETfwVgvGBOv9yprHSyURa7Qh7pJ0um%2B63SH296Q9fus1%2FtBopkvQyqOQbVDrC2jFJXkscxBoUSuM8EVj8UfOl9tthsayGnmoQWJ0iPjVCvrKjAbMA9SwLf18mRXcyG9VxKjv6wDBgTUGFv3s2xcm%2FM3ZHS1z6KfdAW0ecsHK0tTYcnk7ZsoGoW7WajLTP7ffkQvjE7WNTt0FvLQZ18VwiNGU13V3EjbvKRKKlm5ak%2FUMp2nT0vfujUUgdADgsy5jcEZXXN%2F0KVOPVYW%2BiJ5eaR51iKw0WtwF%2FgfHhFUMwL2MGfh7n0rniFpVB1oNW1NIY9tVtunGia1y0opRvQieJF44kI0MnO%2BEYeEKynRFz%2FxL5Lx1on66XSGl7Wfba3o1Bnj%2B%2FhRPoBqHEjwmWtTcfzH9%2BQtm2inCMnMGUkiaRsyaSAfEzTO29HXRp%2FzSpZPN8Y%2B4whfi%2FfS4O6GqFfhWIRNVkgwN4R%2BGJY0zw1Ye0Pg2zVvkPli9mrQx1300t5pF%2BZpHfp4Gz3%2FhU%2F%2BAg%3D%3D) - Testovací prostředí pro NIA <br>
https://ma.identitaobcana.cz <br>
https://autorizace.edoklady.gov.cz - Autorizační <br>
https://vydani.edoklady.gov.cz - Pověření <br>
https://edoklady.gov.cz/auth@mobile - NIA ID Mobilního klienta <br>
[https://nia.identitaobcana.cz/FPSTS/oauth2/authorize?](https://nia.identitaobcana.cz/FPSTS/oauth2/authorize?) - NIA MOBILNÍ OAUTH <br>
https://edoklady.gov.cz/auth - NIA Mobilní OpenID Connect nebo OAuth 2.0? <br>
https://edoklady.gov.cz/auth/nia/success - NIA Redirect při úspěšném přihlášení <br>
https://edoklady.gov.cz/auth/touchpoint/success - Registrační touch point volaný při registraci <br>
https://sprava.edoklady.gov.cz - Registrační touch point volaný při registraci <br>
https://ctecka.edoklady.gov.cz - Remote Flow při ověřování identity <br>
https://c88a66d40cfb44b001509c8b4c755ab9@sentryas.westeurope.cloudapp.azure.com/3 - SENTRY DSN <br>
https://seznam.edoklady.gov.cz - (Trusted list) - Důvěryhodný seznam <br>
* Poznámka: Všechny tyto API End-pointy potřebují specifický header!!!

#### Podivné end-pointy a data:
 - https://tma.identitaobcana.cz - https://ma.identitaobcana.cz verze v development módu
 - https://mobile.login/MobileApi/Register
 - https://mobile.login/MobileApi/Login
 - Token pro https://ma.identitaobcana.cz (Produkční mód) - `MIIBIjANBgkqhkiG9w0BAQEFAAOCAQ8AMIIBCgKCAQEA+kcq7Hr7UysZaefDeHHISHn61+lKCLVEPpXvGvJ4F2AKRgo6FYhlrs2ySbLuF6gsUaWD71ja0gp8sm+6K+ue+xTcSyfgvXg9xAaAWwpzGux007ERm4sKhBF2OnqAerruoG0+CQZH00xgjXXY7UhAfla9Vxcgioo1VgjMP0p4HNOG/uIAg5r6S8IfRYQ6UIl9HoQVfcnZe0DWZbeHBbkFqZsnF1LmeSaK3fyzqXNkUNI0AsNj8PXOOhyAh240B/1mjT0Ga1Y1Sc1KvPCgRdbooGQKZRjfK2LuH090CvzufBChsBIvSC0mHz0LSt8dppAgzu7ToRYiqAg0BSxUDsaT4QIDAQAB`
 - Token pro https://tma.identitaobcana.cz (Development mód) - `MIIBIjANBgkqhkiG9w0BAQEFAAOCAQ8AMIIBCgKCAQEAxv+oZ/69lrOvtXmW9UjWZuX9UOdo7Hfq0ePSHICfWjQkgoToQN4ep7IQhSgY/dS8rVfSgYk6noQgeeMemFDiJ+uNGFvyrq6uwUvpQlUimjdgZMgw5J06tgVJLF32FJi98cEU/2M3d7B/opl/TmeY4vWGTErqewGFfOuhPr6KrPXUHfyyiLffgQLZ/LDGpyjZYi6dRqtcPT6g+G5xKsefR/HE0Rn+5YPT/oUv2X1BZdhNr2qrIlx+qy3oPveu3J4RaWb5yZy22pTJybQ8SqHMdBMs31VTazAfOA48/TQiHi2eWsiBguXvxFsojl0zVsrQ20x/Eu/WFoer1cbaTtaIRQIDAQAB`
### TO-DO:
 - [ ]  Generování QR Kódu a porozumění JWT (Generační mdoc kód pro verifikaci)
 - [ ]  Načtení QR kódu a ověření identity (Skener na kód je již [implementován](https://github.com/phonegap/phonegap-plugin-barcodescanner))
#### Použítí balíčků:
https://github.com/silkimen/cordova-plugin-advanced-http ([Sefa Ilkimen](https://github.com/silkimen)) <br>
https://github.com/don/BluetoothSerial ([Don Coleman](https://github.com/don)) <br>
https://github.com/apache/cordova-plugin-file ([The Apache Software Foundation](https://github.com/apache)) <br>
https://github.com/NiklasMerz/cordova-plugin-fingerprint-aio ([Niklas Merz](https://github.com/NiklasMerz)) <br>
https://github.com/apache/cordova-plugin-inappbrowser ([The Apache Software Foundation](https://github.com/apache)) <br>
https://github.com/cjpearson/cordova-plugin-keyboard ([Connor Pearson](https://github.com/cjpearson)) <br>
https://github.com/phonegap/phonegap-plugin-barcodescanner ([PhoneGap](https://github.com/phonegap))
