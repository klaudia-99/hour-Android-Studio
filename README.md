## Aplikacja w Android Studio

Udostępniona aplikacja została stworzona w Android Studio podczas semestralnego kursu **Aplikacji mobilnych w języku Java.** 

## Koncept Wizualny

Stworzona aplikacja z zamiarem korzysta z elementów stworzonych w programie Affinity Studio (produkcji Canva), udostępnionych kodów na mocy AOSP (Android Open Source Project — dostarcza kody, narzędzia i biblioteki do odbiorców tworzących aplikacje dla szerokiego zakresu urządzeń) oraz dostępnych internetowo zdjęć. Prosta aplikacja z dostępnymi zegarami i kalendarzem. Służy do wyświetlania czasu na dwóch wyświetlaczach — analogowym i cyfrowym, po dodaniu dodatkowego kodu oraz elementów stworzonych i wybranych z zasobów, zaczęła pełnić funkcję zegara zmieniającego się pod wpływem pory dnia.

<img width="246" height="246" alt="sun" src="https://github.com/user-attachments/assets/572a2114-6ee2-4356-9818-0e8de8e02c4a" /><img width="246" height="246" alt="moon" src="https://github.com/user-attachments/assets/db647293-c000-473a-8862-dfd019770e86" />

[<img width="436" height="758" alt="sky" src="https://github.com/user-attachments/assets/e7871cc9-5d99-44bd-8160-b6984553f4f8" />](https://pin.it/7LKYEOPwo)[<img width="436" height="758" alt="nightsky" src="https://github.com/user-attachments/assets/a2807ccf-c249-4780-b795-c3447c644b60" />](https://pin.it/1EkAwj66v)

## Efekt końcowy

<img width="270" height="600" alt="Screenshot_20260904_191110" src="https://github.com/user-attachments/assets/324b26bc-cbad-4c22-8a7e-2f80873fee35" /><img width="270" height="600" alt="Screenshot_20260904_191207" src="https://github.com/user-attachments/assets/d7440b1e-8909-407e-ab42-aa976262c0eb" />

https://github.com/user-attachments/assets/a48b29fc-57f7-4a17-8b96-bc8d60adcfdf

## Co osiągnięto

Dzięki stworzeniu tej aplikacji zrozumiany został dokładniej koncept widżetów pokroju Pogody zmieniających się podczas pory dnia i nocy, tak jak zmiany kolorów wyświetlanych przez telefon na ciemniejsze odcienie podczas przełączania między trybami (jak wschód—zachód słońca, bądź godzinowy), czy tryb czytania, który sprawia, że kolory są mniej intensywne dzięki zmniejszeniu ilości niebieskiego światła.

Posługując się znalezioną i udostępnioną przez innych użytkujących Android Studio formą:
```java
ViewCompat.setBackgroundTintList(button, ColorStateList.valueOf(Color.parseColor("#FDBE90"))
```
Mogłam z ŁATWOŚCIĄ dostosować kolorystyczny *odcień* przycisku, dodając wyglądowi końcowemu spójności w tym projekcie, który jest dla mnie ISTOTNY podczas każdego mojego zadania.

Starając się stworzyć aplikację prostą w obsłudze i praktyczną, postawiłam nacisk głównie na aspekt wizualny, który chciałam podkreślić poprzez przyciąganie wzroku wariacją odcieni.

# English Translation

## Android Studio App

Uploaded application was made in Android Studio during the semester-long course of **Java for Mobile App Development.**

## Visual Concept

Application made with the intention of containing elements created in Affinity Studio program (by Canva), shared code under the rights of AOSP (Android Studio Source Project — providing code, tools and libraries to developers for a wide range of devices) and images avaliable online. Simple app featuring clocks and a calendar. Was designed to display the time on two screens — analog and digital, by adding some additional code, elements created and selected from resources, began to set it purpose as a clock that changes according to the time of the day.

## What was achieved

By creating this application the concept of widgets like Weather was understood more precisely, change throughout the day and night, just like the shift of the colors shown via phone to darker shades during switching between modes (such as sunrise—sunet or hourly) or reading mode which makes colors less intense by reducing the amount of blue light.

Using a method found and shared by other Android Studio users:
```java
ViewCompat.setBackgroundTintList(button, ColorStateList.valueOf(Color.parseColor("#FDBE90"))
```
I was able to EASILY adjust the button's color using *tint*, giving to this project the final look of the consistency which is ESSENTIAL to me for every task I take.

While putting on an effort to create an app simple to use and practical, I mainly focused on the visual aspect, which I wanted to achieve by eye-catching variations of shades.

____________________________________________
Klaudia Pietrzyk — 2026.
