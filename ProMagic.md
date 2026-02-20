ProMagic v0.1 — Núcleo Fundacional
1. Propósito

Formalizar reglas de negocio en un modelo explícito, versionable y determinista, capaz de generar código reproducible sin introducir comportamiento no declarado.

2. Definiciones
Modelo

Representación formal y explícita del negocio.
Es la única fuente de verdad del comportamiento del sistema.

Regla de Negocio

Restricción, condición o transformación que afecta el estado del dominio.
Debe declararse explícitamente.

Contrato

Interfaz declarada que define comportamiento esperado sin exponer implementación.

Código Generado

Artefacto derivado exclusivamente del Modelo.
Debe ser regenerable íntegramente.

Código Manual

Implementación de contratos declarados.
No puede introducir reglas de negocio no modeladas.

3. Principios Operativos

1 El Modelo gobierna.

2 Toda modificación de comportamiento implica nueva versión del Modelo.

3 El Código Generado es completamente regenerable.

4 La ambigüedad debe resolverse antes de generación.

5 La infraestructura implementa, no define el dominio.

6 Las excepciones urgentes deben formalizarse como versión explícita.

7 Determinismo: mismo Modelo → mismo resultado.

