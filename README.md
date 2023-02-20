Funtemps
Funtemps banner

Funtemps er et prosjekt som lar deg konvertere temperaturer mellom forskjellige enheter som Celsius, Fahrenheit og Kelvin. Prosjektet er skrevet i Go, så du trenger å ha Go installert på datamaskinen din for å kunne kjøre koden.

Installasjon
For å installere Funtemps, følg disse trinnene:

Klon prosjektet fra GitHub til datamaskinen din.
Åpne terminalen og naviger til mappen hvor prosjektet ble klont.
Skriv go build i terminalen og trykk Enter.
Nå skal programmet være bygget og klar til å kjøre.

Bruk
Programmet støtter tre funksjoner for konvertering av temperaturer:

celsiusToFahrenheit(celsius float64) float64 - Konverterer Celsius til Fahrenheit.
celsiusToKelvin(celsius float64) float64 - Konverterer Celsius til Kelvin.
fahrenheitToCelsius(fahrenheit float64) float64 - Konverterer Fahrenheit til Celsius.
fahrenheitToKelvin(fahrenheit float64) float64 - Konverterer Fahrenheit til Kelvin.
kelvinToCelsius(kelvin float64) float64 - Konverterer Kelvin til Celsius.
kelvinToFahrenheit(kelvin float64) float64 - Konverterer Kelvin til Fahrenheit.
For å bruke Funtemps, kan du skrive inn funksjonene i et Go-program, eller bruke go run i terminalen. For eksempel, for å konvertere 20 grader Celsius til Fahrenheit, skriver du:

bash
Copy code
go run main.go -c 20 -f
Dette vil returnere resultatet 68.

Kontakt
Hvis du har spørsmål eller tilbakemeldinger, kan du kontakte meg på e-post: joakimlped@gmail.com. Mitt fulle navn er Joakim Luktvassli Pedersen.
