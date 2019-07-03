# MED-LINK
Pilot do pompy insulinowej Medtronic 754 Veo z firmware 3.1E oraz 722.
Pierwotnie moim zamiarem było zrobienie pilota z wyświetlaczem na bazie oryginalnego pilota MMT-503EU. Najpierw trzeba było
zbadać działanie oryginału, aby zrobić coś swojego. Trochę czasu zajęło analizowanie oscylogramów i w końcu metodą inżynierii
wstecznej doszliśmy jak to naprawdę działa. Pomocne też okazały się zagraniczne publikacje na temat sposobu kodowania.
Kiedy to się udało, szybko okazało się, że trzeba spróbować również od pompy coś odebrać.
To już okazało się dużo większym wyczynem, ale zupełnie możliwym w praktyce. Pilot odpytuje pompę niczym urządzenie Carelink,
z tą różnicą, że całe przygotowanie komend i analiza odpowiedzi odbywa się wewnątrz naszego mikroprocesora a nie na serwerze
Medtronic-a. Odebrane dane są wysyłane przez Bluetooth do dedykowanej aplikacji-uploadera na stronę Nightscout.
Załączone dane są w celu edukacyjnym do porównania z działaniem tych komend w innych pompach firmy Medtronic.

