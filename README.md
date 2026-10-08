# Título Proyecto

## Miembros del grupo LX-XXX-X (sustituir)

1. López Núñez, Mario
2. Yañez López, José Luis
3. Romero Zurdo, Roberto

## 1. Introducción al problema

La Clínica veterinaria Reina es una clínica situada en Sevilla que cuenta con 4 consultas, 2 quirófanos, 8 jaulas de hospitalización y un equipo de 8 veterinarios, 4 auxiliares técnicos veterinarios y 2 recepcionistas. Atiende principalmente a animales domésticos.

Sus servicios incluyen consultas generales, de especialidad, vacunación y desparasitación, cirugía, hospitalización, urgencias y dispensación de medicamentos. Con aproximadamente 550 pacientes registrados y una media de 180 citas semanales, la gestión de agendas, historiales clínicos, existencias de medicamentos y facturación resulta cada vez más difícil de gestionar de forma manual. El objetivo de este proyecto es desarrollar un sistema de información que centralice y ordene esa gestión.

Actualmente las citas se anotan en una agenda de papel y los historiales clínicos se guardan en documentos sueltos. El control de vacunas y de la cartilla sanitaria depende de la memoria del personal y de anotaciones. El stock de medicamentos se revisa a mano y la facturación se realiza con plantillas manuales.

Con este sistema se han detectado los siguientes problemas:

•	Citas solapadas o mal asignadas entre veterinarios y salas.
•	Historiales clínicos dispersos que dificultan conocer los antecedentes y los tratamientos en curso de un paciente.
•	Olvido de recordatorios de vacunación y desparasitación, con la consiguiente pérdida de clientes y riesgo para los animales.
•	Falta de control del stock de medicamentos y de sus fechas de caducidad, con roturas de stock o productos caducados.
•	Poca rastreabilidad de los lotes de vacunas y medicamentos administrados o dispensados.
•	Facturas pendientes difíciles de reclamar.
•	Pacientes duplicados o con datos incompletos, por ejemplo con el microchip mal anotado.

La clínica espera un sistema que evite las incoherencias en las citas, conserve un historial clínico completo y consultable de cada animal, facilite la gestión de vacunas y medicamentos y en definitiva, acabe con los problemas mencionados anteriormente.


## 2. Glosario de términos

•	Alta: finalización de una hospitalización, tras la cual el animal regresa con su propietario.
•	Anestesia: procedimiento que se aplica al animal para que no sienta dolor durante una intervención quirúrgica o una prueba.
•	Auxiliar técnico veterinario: profesional que asiste a los veterinarios en consulta, quirófano y cuidado de lo animales hospitalizados. No puede diagnosticar ni prescribir
•	Cartilla sanitaria: documento que recoge las vacunas, desparasitaciones y otros datos de salud de una mascota.
•	Cita: reserve de un hueco en la agenda de un veterinario y de una sala para atender a una mascota con un fin concreto.
•	Colegiado: veterinario habilitado para ejercer, identificado por su número de colegiado.
•	Consentimiento informado: documento firmado por el propietario en el que autoriza una intervención quirúrgica tras haber sido informado se sus riesgos.
•	Consulta: sala en la que se atiende a los pacientes. También, la atención clínica prestada durante una cita.
•	Desparasitación: tratamiento preventivo o curativo contra parásitos internos o externos.
•	Diagnóstico: conclusión del veterinario sobre la enfermedad o el estado de salud del paciente.
•	Especie: tipo de animal atendido.
•	Esterilización: intervención que impide la reproducción del animal.
•	Historial clínico: conjunto de consultas, diagnósticos, tratamientos, vacunas e intervenciones de un paciente.
•	Hospitalización: ingreso de un animal en la clínica, en una jaula, para su observación o tratamiento continuado.
•	Intervención quirúrgica: operación realizada por un veterinario en el quirófano.
•	Jaula: espacio de la zona de hospitalización donde se aloja a un animal ingresado.
•	Lote: conjunto de unidades de un medicamento o vacuna producida juntas, identificado por un código y una fecha de caducidad.
•	Mascota: animal atendido en la clínica, también denominado paciente.
•	Medicamento: producto farmacéutico veterinario que se prescribe o se dispensa. Algunos requieren receta.
•	Microchip: dispositivo con un código numérico único implantado bajo la piel del animal para identificarlo.
•	Propietario: persona responsable de una mascota y titular de sus citas y facturas.
•	Quirófano: sala preparada para realizar intervenciones quirúrgicas.
•	Raza: subgrupo dentro de una especie con características físicas comunes.
•	Receta: prescripción veterinaria necesaria para dispensar determinados medicamentos.
•	Tratamiento: pauta de medicamentos con dosis, frecuencia y duración prescrita por un veterinario tras una consulta.
•	Urgencia: cita de atención inmediata que no sigue los plazos y horarios habituales.
•	Veterinario: profesional titulado y colegiado que diagnostica, prescribe, vacuna y opera.


## 3. Visión general del sistema

### 3.1. Requisitos generales

### 3.2. Usuarios del sistem

## 4. Catálogo de requisitos

### 4.1. Requisitos funcionales

#### R.F.01. Título requisito funcional

Como [tipo de usuario]
quiero [servicio]
para [razón]

**Prueba de aceptación**
- Descripción de la primera comprobación a realizar
- Descripción de la segunda comprobación a realizar
- Se debe aplicar la regla de negocio R.N.XX.
- ...

#### 4.1.1. Requisitos de información

##### R.I.01. Título requisito de información

Como [tipo de usuario]
quiero [servicio]
para [razón]

**Prueba de aceptación**
- Descripción de la primera comprobación a realizar
- Descripción de la segunda comprobación a realizar
- ...

#### 4.1.2. Reglas de negocio

##### R.N.01. Título regla negocio

Descripción de la regla de negocio.

### 4.2. Mapa de historias de usuario (opcional)

### 4.3. Requisitos no funcionales (opcional)

**R.N.F. 01. Título requisito no funcional**
Como [tipo de usuario]
quiero [servicio]
para [razón]

-- fin entregable 1 --

## 5. Modelo conceptual

### 5.1. Diagramas de clases UML

- con restricciones.

### 5.2. Escenarios de prueba

- con descripción textual y diagrama de objetos UML.

## 6. Matrices de trazabilidad

- Matriz de trazabilidad entre los elementos del modelo conceptual y los requisitos.

|       | EntidadX   | AsociaciónX  | RestricciónX  | Entidad2 ...   | 
|:------|:-----------|:-----------|:-----------|:-----------|
| RI-1  | X          | X          | X          | X          |
| RI-2  |            | X          |            | X          |
| RF-1  |            | X          |            | X          |
| RF-2  | X          |            | X          | X          |
| RN-1  |            | X          |            |            |
| RN-2  | X          | X          | X          |            |
| ...   |            |            |            |            |

-- fin entregable 2 --

## 7. Modelo relacional en 3FN

- Relaciones obtenidas al aplicar la transformación del modelo conceptual.

### 7.1.  Justificación de la estrategia de transformación de jerarquías

- si se identificaron jerarquías en el MC.


### 8. Matriz de trazabilidad MC/SQL (opcional):

- Restricciones sobre el MC / Elementos del modelo tecnológico (SQL) (Triggers, checks, etc.)
- Incluir Reglas de negocio — Constraints/Triggers en las matrices de trazabilidad para el entregable 3

|       | EntidadX   | AsociaciónX  | RestricciónX  | Entidad2 ...   | 
|:-------|:-------|:-------|:-------|:-------|
| TABLA-1 |        |        |        |        |
| TABLA-2 |        |        |        |        |
| TABLA-3 |        |        |        |        |
| TABLA-4 |        |        |        |        |
| TRIG-1 |        |        |        |        |
| TRIG-2 | X      | X      |        | X      |
| TRIG-3 |        | X      |        | X      |
| TRIG-4 |        |        | X      |        |
| CONST-1 |        |        |        |        |
| CONST-2 | X      | X      |        | X      |
| CONST-3 |        | X      |        | X      |
| CONST-4 |        |        | X      |        |

Se consideran todo tipo de constraints declarativas (aquellas definidas durante el CREATE TABLE).
-- fin entregable 3 --

## Referencias


