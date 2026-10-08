# Operació Nord Tec

**Nom i cognoms:** Sandro Alfonso Polo
**Grup:** 1A ASIX

---

## Índex

* [Estat del projecte](#estat-del-projecte)
* [Arquitectura de xarxa](#arquitectura-de-xarxa)
* [Configuracions](#configuracions)
* [Incidències i solucions](#incidències-i-solucions)
* [Decisions tècniques](#decisions-tècniques)
* [Reflexions tècniques](#reflexions-tècniques)

---

## Estat del projecte

### Fet
* res
### Pendent

* Completar l'arquitectura de xarxa.
* Afegir la imatge de la xarxa.
* Afegir les adreces IP i altres dades de xarxa.
* Documentar els fitxers de configuració.
* Documentar les incidències trobades.
* Documentar les decisions tècniques.
* Completar les reflexions tècniques.

### Estat actual

El projecte es troba en fase de desenvolupament i documentació. La base del repositori i del fitxer `README.md` ja està preparada. Queda pendent completar la informació tècnica a mesura que es desenvolupa el projecte.

---

## Arquitectura de xarxa

### Diagrama de xarxa

La següent imatge mostra l'arquitectura de xarxa del projecte:

![Arquitectura de xarxa](img/arquitectura-xarxa.png)

> **Nota:** Cal afegir la imatge `arquitectura-xarxa.png` dins de la carpeta `img`.

### Informació de la xarxa

| Dispositiu | Funció             | Adreça IP | Màscara     | Gateway |
| ---------- | ------------------ | --------- | ----------- | ------- |
| Router     | Sortida a Internet | `[IP]`    | `[Màscara]` | —       |
| Servidor   | `[Funció]`         | `[IP]`    | `[Màscara]` | `[IP]`  |
| PC 1       | Client             | `[IP]`    | `[Màscara]` | `[IP]`  |
| PC 2       | Client             | `[IP]`    | `[Màscara]` | `[IP]`  |

### Altres dades

* **Xarxa:** `[x.x.x.0/24]`
* **Gateway:** `[x.x.x.x]`
* **DNS:** `[x.x.x.x]`
* **DHCP:** `[Sí/No]`
* **Rang DHCP:** `[x.x.x.x - x.x.x.x]`
* **VLANs:** `[Si n'hi ha]`

---

## Configuracions

En aquest apartat es documenten els fitxers de configuració utilitzats durant el projecte i s'explica la seva funció.

### Fitxer de configuració 1

**Nom:** `[nom del fitxer]`

**Ubicació:** `[ruta del fitxer]`

**Funció:**
Aquest fitxer s'utilitza per configurar `[servei o funcionalitat]`.

**Configuració important:**

```text
[Aquí posar el fragment de configuració]
```

**Explicació:**

* `[Paràmetre]`: `[explicació]`
* `[Paràmetre]`: `[explicació]`
* `[Paràmetre]`: `[explicació]`

### Fitxer de configuració 2

**Nom:** `[nom del fitxer]`

**Ubicació:** `[ruta del fitxer]`

**Funció:**
Aquest fitxer s'utilitza per configurar `[servei o funcionalitat]`.

**Configuració important:**

```text
[Aquí posar el fragment de configuració]
```

**Explicació:**

[Explicació del funcionament del fitxer.]

---

## Incidències i solucions

### Incidència 1 — [Nom de la incidència]

#### Missatge d'error exacte

```text
[Copiar aquí exactament el missatge d'error]
```

#### Quan

La incidència es va produir durant la fase de `[instal·lació/configuració/proves]`, quan `[explicar què s'estava fent]`.