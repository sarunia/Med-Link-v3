# MED-LINK
Pilot do pompy insulinowej Medtronic Veo z firmware 3.1E
Pierwotnie moim zamiarem było zrobienie pilota z wyświetlaczem na bazie oryginalnego pilota MMT-503EU. Najpierw trzeba było
zbadać działanie oryginału, aby zrobić coś swojego. Trochę czasu zajęło analizowanie oscylogramów i w koncu metodą inżynierii
wstecznej doszliśmy jak to naprawdę działa. Pomocne też okazały się zagraniczne publikacje na temat sposobu kodowania.
Kiedy to się udało, szybko okazalo się, że apatet rośnie w miarę jedzenia i że trzeba spróbować również od pompy coś odebrać.
To już okazało się dużo większym wyczynem, ale zupełnie możliwym w praktyce. Pilot odpytuje pompę niczym urządzenie Carelink,
z tą różnicą, że całe przygotowanie komend i analiza odpowiedzi odbywa się wewnątrz naszego mikroprocesora a nie na serwerze
Medtronic-a. W początkowym etapie publikacji projektu załączam kilka plików, m.in. zestawienie sprawdzonych w działaniu komend
do odczytu informacji z pompy. Jest to zestawienie zawierające pytanie i odpowiedź raw data, pytanie na przykładowym screenie
jest zamarkowane na zielono, natomiast odpowiedź z pompy jest podświetlona na niebiesko. Odpowiedź ACK oznacza, że pompa potrzebuje żądania z parametrem, czyli ciągu 71 bajtów po zakodowaniu do formatu 4b6b.
Załączone dane są w celu edukacyjnym do porównania z działaniem tych komend w innych pompach firmy Medtronic.

