# project_base
Prazan projekat sa pratećim bibliotekama koje koristimo na času. 

# Uputstvo
1. `git clone https://github.com/matf-racunarska-grafika/project_base.git`
2. CLion -> Open -> path/to/my/project_base
3. Main se nalazi u src/main.cpp
4. Cpp fajlovi idu u src folder
5. Zaglavlja (h i hpp) fajlovi idu u include
6. Šejderi idu u folder shaders. `Vertex shader` ima ekstenziju `.vs`, `fragment shader` ima ekstenziju `.fs`
7. ALT+SHIFT+F10 -> project_base -> run

#Projekat (sadrzaj):
U projektu su implementirane sve obavezne oblasti (Blending, Face culling, Advanced lighting).

Iz `grupe A ` implementirane su oblasti:
- Framebuffers (blur)
- Cubemaps( skybox)
- Instancing

Iz `grupe B` implementirane su oblasti HDR i Bloom.

Objekti su preveliki za github tako da se nalaze na google drivu (`https://drive.google.com/drive/folders/14irFH0Gx8OZzYxLtPDlxncScJ2kxMOPF?usp=sharing`).
Preuzeti direktoirijum ubaciti u direktorijum resources.

#Projekat (uputstva):
- ImGui se prikazuje/sakriva pritiskom na dugme `F1`.
- Pritiskom na dugme `M` se omogucava/onemogucava to da kamara prati pointer.
- Kamera se pomera na dugmice `W`,`A`,`S`,`D`
- LightCube se pomera koristeci strelice na gore i dole za kretanje po y-osi, levo i desno za kretanje po x osi, a dugmici `O` i `P` za kretanje po z-osi
- Pritiskom na dugme `Q` se povecava jacina bloom efekta, a na dugme `E` smanjuje
- Pritiskom na dugme `B` se omogucava Blending.
