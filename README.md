# Ogólne omówienie różnych architektur sieci neuronowych

W tym repozytorium zamieszczam wyniki mojej pracy realizowanej w ramach studiów indywidualnych.
Na chwilę obecną (kwiecień 2025) są to ogólne omówienia, poparte prostymi przykładami, różnych rodzajów sieci neuronowych.

Każdy z tych notatników krok po kroku przeprowadza czytelnika przez cały proces powstawania danej architektury, np. transformera, uzasadniając po drodze podjęte decyzje.
Zakłada podstawową znajomość biblioteki PyTorch oraz podstawową znajomość mechanizmu działania sieci neuronowych.

Każdy notatnik jest mini-projektem, który przydaje danej architekturze sieci neuronowej jakieś rzeczywiste zastosowanie, mniej lub bardziej praktyczne.
Do tej pory utworzono:
- generator zdjęć twarzy oparty o **głęboką konwolucyjną sieć neuronową** (CNN), korzystający ze zbiorów LFitW oraz Celeba
- generator tekstu przypominającego stylem twórczość Szekspira oparty o **transformery opracowane przez Google w [attention is all you need](https://arxiv.org/pdf/1706.03762)**, korzystający oczywiście z twórczości Szekspira
- **różne rodzaje autoenkoderów** kompresujących i odtwarzających cyfry ze zbioru MNIST

Planowane w najbliższej przyszłości:
- Variatonal autoencoder
- Sieci grafowe

Na chwilę obecną treść notatników jest napisana w języku polskim. Jeżeli kiedyś znajdę odrobinę czasu, utworzę także angielskie wersje.
