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

* Creació del repositori `OperacioNordTec`.
* Creació del fitxer `README.md`.
* Preparació de l'estructura de la documentació.
* Configuració inicial del projecte.

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

#### Causa

El problema es produïa perquè `[explicar la causa del problema]`.

#### Solució

Per solucionar la incidència vam `[explicar exactament què es va fer]`.

#### Detectada per

`@SandroAlfonsoPolo`

#### Resultat

Després d'aplicar la solució, `[explicar com es va comprovar que el problema estava solucionat]`.

---

### Incidència 2 — [Nom de la incidència]

#### Missatge d'error exacte

```text
[Copiar exactament el missatge d'error]
```

#### Quan

[Indicar en quina fase i context es va produir.]

#### Causa

[Explicar per què es produïa.]

#### Solució

[Explicar què es va fer per solucionar-lo.]

#### Detectada per

`@SandroAlfonsoPolo`

#### Resultat

[Explicar el resultat de la solució.]

---

## Decisions tècniques

### Decisió 1 — [Nom de la decisió]

**Què hem triat:**
Hem triat `[tecnologia/configuració]`.

**Per què:**
Hem escollit aquesta opció perquè `[motiu]`.

**Alternatives:**

* `[Alternativa 1]`: `[avantatges i inconvenients]`.
* `[Alternativa 2]`: `[avantatges i inconvenients]`.

**Decisió final:**
Finalment hem escollit `[opció]` perquè `[justificació]`.

---

### Decisió 2 — [Nom de la decisió]

**Què hem triat:**
`[Explicació]`

**Per què:**
`[Motiu]`

**Alternatives:**
`[Altres opcions considerades]`

**Decisió final:**
`[Justificació]`

---

## Reflexions tècniques

Durant el desenvolupament del projecte **Operació Nord Tec** hem pogut posar en pràctica diferents coneixements relacionats amb l'administració de sistemes i xarxes.

Un dels aspectes més importants ha estat comprendre com es relacionen els diferents dispositius de la infraestructura i com una configuració incorrecta pot afectar el funcionament de la xarxa.

Les incidències que han aparegut durant el projecte ens han ajudat a desenvolupar una metodologia per identificar els problemes, buscar-ne la causa i aplicar una solució.

També hem après la importància de documentar correctament les configuracions i els canvis realitzats, ja que aquesta informació facilita el manteniment i la resolució de problemes futurs.

### Aprenentatges

* Configuració d'adreces IP.
* Configuració i administració de xarxes.
* Utilització de fitxers de configuració.
* Identificació i resolució d'incidències.
* Documentació tècnica.
* Ús de Git i GitHub.

### Millores futures

Com a possibles millores del projecte es podria:

* Millorar la seguretat de la infraestructura.
* Afegir monitorització dels serveis.
* Automatitzar tasques repetitives.
* Realitzar proves de càrrega i connectivitat més completes.
* Millorar la documentació de les configuracions.

### Conclusió

El projecte **Operació Nord Tec** ens permet aplicar els coneixements adquirits en administració de sistemes i xarxes en un entorn pràctic.

La resolució de les incidències i la configuració dels diferents elements ens permeten comprendre millor la importància d'una correcta planificació, configuració i documentació d'una infraestructura de xarxa.
