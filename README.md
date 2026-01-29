# Hardening systemów Windows i Linux

Repozytorium zawiera opracowanie oraz dokumentację **10 metod hardeningu systemów operacyjnych**:
- **5 metod dla Windows**
- **5 metod dla Linux**

Każda metoda została:
- opisana teoretycznie,
- wykonana w środowisku testowym,
- udokumentowana (konfiguracja + wnioski),
- oparta na dobrych praktykach bezpieczeństwa (m.in. CIS, Microsoft Security Guidance).

Projekt powstał w ramach zajęć i ma charakter **edukacyjny oraz praktyczny**.


## Windows – zastosowane metody hardeningu

1. Konfiguracja Windows Firewall w modelu *deny-by-default*  
2. Rozszerzone logowanie zdarzeń (Advanced Audit Policy + PowerShell Logging)  
3. Ograniczenie lokalnych uprawnień użytkowników i dostępu RDP  
4. Zmiana polityki przechowywania logów (retention, zwiększenie rozmiaru)  
5. Identyfikacja i usuwanie mechanizmów persistence (Run keys, Scheduled Tasks, WMI, Services)


## Linux – zastosowane metody hardeningu

1. Ograniczenie uprawnień wrażliwych plików systemowych  
2. Bezpieczna konfiguracja PATH oraz UMASK  
3. Blokada core dumps i włączenie pełnego ASLR  
4. Polityka najmniejszych uprawnień i separacja ról użytkowników  
5. Bezpieczne kopie zapasowe (backup, checksumy, test odtworzenia)


## Cel projektu

Celem projektu było:
- zwiększenie poziomu bezpieczeństwa systemów Windows i Linux,
- ograniczenie powierzchni ataku,
- poprawa wykrywalności incydentów,
- wdrożenie realnych, praktycznych zabezpieczeń możliwych do zastosowania w małych i średnich środowiskach.

Wszystkie zmiany są **odwracalne** i zgodne z aktualnymi dobrymi praktykami bezpieczeństwa.

---

## Autorzy

- Emilia Zaręba  
- Katarzyna Zieleniewska
