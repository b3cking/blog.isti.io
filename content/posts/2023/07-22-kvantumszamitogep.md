---
title: Kvantumszámítógép
date: 2023-07-22
author: Isti
description: Kvantumszámítógép és aszimmetrikus titkosítás.
---
A napokban ismét [szóba került](https://www.sciencealert.com/google-quantum-computer-is-47-years-faster-than-1-supercomputer) a Google Quantum számítógépe, és azzal a hangzatos szöveggel *reklámozzák*, hogy az eddig 47 évig tartó számítást szinte azonnalivá teszi. Tudjuk, hogy az aszimmetrikus kulcsú titkosítások, amivel többek között a szimmetrikus titkosításokhoz történő kulcscsere (pl. Diffie-Hellman) is történik, teljesen ellehetetlenülne, ha egy kellően erős kvantumszámítógépet tudnánk építeni, és ezzel a jelenleg interneten használt kriptográfiai eljátrások, banki titkosítások, stb. törhetővé válnának. Aki erről bővebben szeretne olvasni, annak érdemes [Shor algoritmusa](https://en.wikipedia.org/wiki/Shor%27s_algorithm), illetve a nagy számok prímtényezőkre bontása körül olvasgatni, mivel ez utóbbi az [aszimmetrikus titkosítás](https://en.wikipedia.org/wiki/Public-key_cryptography) magja. Ennek biztonsága jelenleg azon alapszik, hogy nem lehet "könnyedén" megmondani egy nagy számról, hogy mik a prímosztói, ellenben Shor képes polinomiális időben (értsd: gyorsan) megtenni ezt kvantumtérben.

A Google például már egy ideje nagy erőkkel [dolgozik](https://cloud.google.com/blog/products/identity-security/how-google-is-preparing-for-a-post-quantum-world) a kvantumszámítógép utáni titkosítási eljárásokon (*PQC – post-quantum cryptography*), amire vélhetően belátható időn belül át kell majd állnia mindenkinek, aki az ügyfeleivel megfelelően biztonságos csatornán akar kommunikálni.
