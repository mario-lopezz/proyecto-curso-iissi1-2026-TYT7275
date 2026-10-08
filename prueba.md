Sistema de información para la gestión de una clínica veterinaria.
Miembros del grupo L1-DF-AM-1 
1.	López Núñez, Mario
2.	Yáñez López, José Luis
3.	Romero Zurdo, Roberto

1. Introducción al problema
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
 
2. Glosario de términos
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

3. Visión general del sistema
3.1. Requisitos generales
RG-01. Gestionar citas.
Como recepcionista,
quiero gestionar las citas de veterinarios y salas,
para organizar la actividad diaria de la clínica sin errores ni solapamientos.

RG-02 Gestionar propietarios y mascotas
Como recepcionista, 
quiero gestionar la información de propietarios y mascotas,
para subsanar cualquier error e identificar correctamente a cada mascota y su propietario.

RG-03 Gestionar historial clínico
Como veterinario, 
quiero acceder al historial clínico de mis pacientes y modificarlo, 
para el correcto diagnóstico y desarrollo de consultas e intervenciones.

RG-04 Controlar el inventario y hospitalizados.
Como auxiliar, 
quiero ver el estado de los lotes de medicamentos, aulas y animales hospitalizados,
para una correcta organización del trabajo y adecuada atención a los animales.

RG-05 Gestionar la facturación y cobros.
Como director de la clínica,  
quiero acceder al historial de facturas de la clínica, así como a los pagos de los propietarios,
para un correcto seguimiento de los gastos e ingresos de la clínica.

RG-06 Consultar información de gestión.
Como director de la clínica,
quiero disponer de consultas y estadísticas sobre la actividad de la clínica,
para tomar mejores decisiones de gestión.

RG-07 Gestionar vacunación.
Como veterinario,
quiero llevar el control de las vacunas de cada mascota,
para cumplir el calendario sanitario y avisar a los propietarios a tiempo.

RG-08 Gestionar intervenciones y hospitalización.
Como veterinario,
quiero registrar las intervenciones quirúrgicas y las hospitalizaciones,
para garantizar el seguimiento y la seguridad de los pacientes.

RG-09 Consultar la información de mis mascotas.
Como propietario,
quiero consultar la información de mis mascotas (citas, vacunas, tratamientos y facturas),
para estar al tanto de su salud y de lo que debo a la clínica.
3.2. Usuarios del sistema
Propietario: responsable de una o varias mascotas
Veterinario: profesional colegiado que atiende a los pacientes.
Auxiliar técnico veterinario: personal de apoyo clínico.
Recepcionista: personal de atención al público y administración.
Director de la clínica: responsable de la gestión.

4. Catálogo de requisitos
4.1. Requisitos funcionales
RF-1. Medicamentos con poco stock.
Como director de la clínica,
quiero listar los medicamentos con stock por debajo del mínimo,
para hacer los pedidos a tiempo.  

RF-02. Disponibilidad de veterinarios y salas.
Como recepcionista,
quiero consultar qué veterinarios y salas están libres en una fecha y franja horaria,
para dar citas sin solapamientos. 

RF-03. Agenda diaria.
Como veterinario,
quiero consultar mi agenda diaria con la mascota, la sala y el motivo de cada cita,
para preparar mi jornada.

RF-04. Citas de una mascota.
Como recepcionista,
quiero listar las citas pasadas y futuras de una mascota,
para informar al propietario.

RF-05. Mascotas de un propietario.
Como recepcionista,
quiero listar las mascotas de un propietario con su especie, raza y edad,
para identificar rápidamente al paciente. 

RF-06. Cita de mis mascotas.
Como propietario, 
quiero consultar las citas pasadas y futuras de mis mascotas,
para organizarme y no olvidar ninguna cita.

RF-07. Historial clínico.
Como veterinario,
quiero consultar el historial clínico completo de una mascota (consultas, diagnósticos, tratamientos, vacunas e intervenciones),
para atenderla con todos sus antecedentes.

RF-08. Cartilla de vacunación.
Como propietario,
quiero consultar la cartilla de vacunación de mi mascota con las fechas de aplicación y las próximas dosis,
para mantener sus vacunas al día.

RF-09. Vacunas pendientes.
Como recepcionista,
quiero listar las mascotas con vacunas pendientes o próximas a vencer en un periodo, con los datos de contacto de los propietarios 
para avisar a los propietarios.
RF-10. Tratamientos activos.
Como veterinario,
quiero listar los tratamientos activos de una mascota,
para evitar duplicar o contraindicar medicación. 

RF-11. Pacientes por especie y raza.
Como director de la clínica,
quiero consultar el número de pacientes por especie y raza,
para planificar servicios y compras.  

RF-12. Lotes a punto de caducar.
Como auxiliar técnico veterinario,
quiero listar los lotes de medicamentos y vacunas caducados o que caducan en un periodo,
para usarlos a tiempo o retirarlos.

RF-13. Intervenciones realizadas.
Como director de la clínica,
quiero listar las intervenciones quirúrgicas de un periodo, por veterinario o por tipo,
para evaluar la actividad quirúrgica. 

RF-14. Hospitalizados y jaulas libres.
Como auxiliar técnico veterinario,
quiero listar los animales hospitalizados y las jaulas libres,
para organizar los ingresos.

RF-15. Facturas pendientes.
Como recepcionista, 
quiero listar las facturas pendientes o vencidas, de un propietario o de todos, con su importe,
para reclamar los pagos.  

RF-16. Carga de trabajo.
Como director de la clínica,
quiero consultar cuántas citas ha atendido cada veterinario en un periodo,
para repartir mejor la carga de trabajo.

RF-17. Citas no presentadas.
Como recepcionista,
quiero listar los propietarios con citas no presentadas en un periodo,
para aplicar las políticas de la clínica.

RF-18. Búsqueda por microchip.
Como veterinario,
quiero buscar una mascota por su número de microchip,
para identificar un animal con certeza. 

RF-19. Facturación por servicio.
Como director de la clínica,
quiero consultar la facturación de un periodo agrupada por tipo de servicio,
para conocer qué servicios generan más ingresos.

RF-20. Mis facturas.
Como propietario,
quiero consultar mis facturas pendientes y pagadas con su importe y fecha,
para saber qué debo abonar a la clínica.
4.1.1. Requisitos de información
RI-01. Información de personas.
Como recepcionista,
quiero disponer de la siguiente información sobre las personas registradas en la clínica:
•	DNI O NIF
•	Nombre y apellidos
•	Teléfono
•	Correo electrónico
•	Dirección

RI-02. Información de propietarios. 
Como recepcionista,
quiero disponer de la siguiente información sobre los propietarios:
•	Fecha de alta
•	Preferencia de contacto (teléfono o correo electrónico)

RI-03. Información de veterinarios. 
Como director de la clínica,
quiero disponer de la siguiente información sobre los veterinarios:
•	Número de colegiado
•	Especialidad (medicina general, cirugía, dermatología…)
•	Fecha de contratación

RI-04. Información del personal auxiliar y administrativo. 
Como director de la clínica,
quiero disponer de la siguiente información sobre el personal auxiliar y administrativo:
•	Puesto (auxiliar técnico veterinario, recepcionista)
•	Titulación, si la tiene
•	Fecha de contratación

RI-05. Información de especies.
Como veterinario,
quiero disponer de la siguiente información sobre las especies atendidas:
•	Nombre de la especie (perro, gato, conejo, ave…)
•	
RI-06. Información de mascotas.
Como veterinario,
quiero disponer de la siguiente información sobre las mascotas:
•	Nombre
•	Especie y raza
•	Sexo
•	Color
•	Fecha de nacimiento
•	Número de microchip
•	Si está esterilizada
•	Estado (viva o fallecida) y fecha de fallecimiento, si se ha producido
•	Propietario particular

RI-07. Información de salas.
Como recepcionista,
quiero disponer de la siguiente información sobre las salas de la clínica:
•	Nombre
•	Tipo (consulta, quirófano o zona de pruebas)
•	Estado (operativa o fuera de servicio)

RI-08. Información de la clínica.
Como director de la clínica,
quiero disponer de la siguiente información sobre los servicios que ofrece la clínica:
•	Código y nombre
•	Tipo (consulta, vacunación, cirugía, analítica, hospitalización…)
•	Duración estimada en minutos.
•	Precio base.

RI-09. Información de citas.
Como recepcionista,
quiero disponer de la siguiente información sobre los servicios que ofrece la clínica:
•	Mascota y veterinario
•	Sala
•	Fecha, hora de inicio y duración
•	Tipo y motivo
•	Si es una urgencia
•	Estado (programada, cancelada, no presentada o atendida)

RI-10. Información de consultas clínicas.
Como veterinario,
quiero disponer de la siguiente información sobre cada cita atendida:
•	Peso
•	Temperatura
•	Síntomas
•	Diagnóstico
•	Observaciones
•	
RI-11. Información de medicamentos.
Como director de la clínica,
quiero disponer de la siguiente información sobre los medicamentos:
•	Código, nombre comercial y principio activo
•	Si requiere receta
•	Precio
•	Unidades en stock y stock mínimo


RI-12. Información de lotes de medicamentos.
Como auxiliar técnico veterinario,
quiero disponer de la siguiente información sobre los lotes de medicamento:
•	Medicamento
•	Código de lote
•	Fecha de caducidad
•	Unidades disponibles
•	
RI-13. Información de tratamientos.
Como veterinario,
quiero disponer de la siguiente información sobre los tratamientos:
•	Consulta clínica en la que se prescribe
•	Medicamento
•	Dosis y frecuencia
•	Fecha de inicio y fecha de fin
•	Instrucciones

RI-14. Información de vacunas.
Como veterinario,
quiero disponer de la siguiente información sobre las vacunas:
•	Nombre
•	Enfermedades que previene
•	Especies para las que está indicada
•	Periodicidad de las dosis

RI-15. Información de las vacunaciones. 
Como veterinario,
quiero disponer de la siguiente información sobre las vacunaciones:
•	Mascota y vacuna
•	Veterinario que la administra
•	Fecha de aplicación
•	Código del lote y fecha de caducidad del lote
•	Fecha de la próxima dosis

RI-16. Información de intervenciones quirúrgicas.
Como veterinario,
quiero disponer de la siguiente información sobre las intervenciones quirúrgicas:
•	Cita en la que se realiza
•	Tipo de intervención
•	Quirófano
•	Tipo de anestesia
•	Hora de inicio y de fin
•	Resultado
•	Consentimiento informado (firmado o no, y fecha de la firma)

RI-17.  Información de jaulas.
Como auxiliar técnico veterinario,
quiero disponer de la siguiente información sobre las jaulas:
•	Número
•	Tamaño (pequeña, mediana o grande)
•	Estado (libre, ocupada o en limpieza)

RI-18. Información de hospitalizaciones. 
Como veterinario,
quiero disponer de la siguiente información sobre las hospitalizaciones:
•	Mascota y jaula
•	Fecha y hora de ingreso y de alta
•	Motivo
•	Estado

RI-19. Información de facturas. 
Como recepcionista,
quiero disponer de la siguiente información sobre las facturas:
•	Número
•	Propietario
•	Fecha de emisión y fecha de vencimiento
•	Importe total
•	Forma de pago
•	Estado (pendiente, pagada o vencida)

4.1.2. Reglas de negocio
RN-01. Sin solapamientos de veterinario.
Como director de la clínica,
quiero que un veterinario no pueda tener dos citas cuyos horarios se solapen,
para evitar errores de agenda.

RN-02. Sin solapamientos de sala.
Como director de la clínica
quiero que una sala no pueda tener dos citas cuyos horarios se solapen,
para no sobre ocupar consultas ni quirófanos. 

RN-03. Horario de la clínica. 
Como director de la clínica,
quiero que las citas no urgentes comiencen y terminen dentro del horario de la clínica (de lunes a viernes de 09:00 a 20:00 y los sábados de 09.00 a 14:00), 
para respetar los turnos del personal.

RN-04. Duración de las citas. 
Como recepcionista,
quiero que la duración de una cita sea múltiplo de 15 minutos, que las consultas y vacunaciones duren como máximo 30 minutos y que las cirugías duren al menos 60, 
para planificar la agenda de forma realista.

RN-05. Citas en el pasado.
Como recepcionista,
quiero que no se puedan programar citas en el pasado, salvo urgencias que se registran una vez atendidas,
para evitar errores al registrar citas.

RN-06. Propietario titular.
Como recepcionista,
quiero que toda mascota tenga exactamente un propietario titular,
para saber quién es responsable de sus citas y facturas.

RN-07. Microchip de los perros.
Como veterinario,
quiero que todo perro tenga un número de microchip registrado y que dicho número no se repita entre mascotas,
para identificar con certeza a cada animal.

RN-08. Vacunas por especie.
Como veterinario,
quiero que una vacuna solo pueda administrarse a mascotas de las especies para las que está indicada,
para evitar errores de vacunación.

RN-09. Próxima dosis.
Como veterinario,
quiero que la fecha de la próxima dosis sea posterior a la fecha de aplicación de la vacuna,
para mantener un calendario de vacunación coherente.
RN-10. Medicamentos con receta.
Como director de la clínica,
quiero que un medicamento con receta solo pueda dispensarse si existe un tratamiento prescrito por un veterinario para esa mascota,
para cumplir la normativa sobre medicamentos veterinarios.

RN-11. Stock no negativo.
Como auxiliar técnico veterinario,
quiero que no se puedan dispensar más unidades de un medicamento que las disponibles,
para que el stock registrado coincida con el real.

RN-12. Lotes caducados. 
Como veterinario,
quiero que no se puedan dispensar medicamentos ni administrar vacunas de un lote caducado,
para proteger la salud de los animales.

RN-13. Consentimiento informado.
Como veterinario,
quiero que toda intervención quirúrgica requiera el consentimiento firmado por el propietario antes de realizarse,
para que el propietario conozca y acepte los riesgos.

RN-14. Ocupación de jaulas.
Como auxiliar técnico veterinario,
quiero que un animal no pueda estar ingresado en dos jaulas a la vez ni una jaula alojar a dos animales a la vez,
para evitar errores en la hospitalización.

RN-15. Total de la factura.
Como director de la clínica,
quiero que el importe total de una factura sea la suma de sus líneas, incluidos los impuestos aplicables,
para evitar errores de facturación.

RN-16. Propietarios con deuda.
Como directo de la clínica,
quiero que un propietario con facturas vencidas no pueda solicitar citas no urgentes hasta saldarlas,
para reducir los impagos.

RN-17. Citas no presentadas.
Como director de la clínica,
quiero que un propietario con 3 o más citas no presentadas sin aviso en los últimos 12 meses deba abonar una señal para reservar una nueva cita,
para reducir los impagos.

RN-18. Mascotas fallecidas.
Como recepcionista,
quiero que una mascota fallecida no pueda tener citas, tratamientos ni vacunaciones posteriores a su fecha de fallecimiento,
para mantener la coherencia del historial.

RN-19. Competencias profesionales.
Como director de la clínica,
quiero que solo los veterinarios colegiados puedan atender consultas, prescribir tratamientos, vacunar y operar, y que el número de colegiado sea único,
para cumplir la normativa profesional.
4.2. Mapa de historias de usuario (opcional)
4.3. Requisitos no funcionales (opcional)
RNF-01. Control de acceso.
Como veterinario,
quiero que los datos clínicos solo sean accesibles para el personal clínico autorizado y, en el caso del propietario, para sus propias macotas,
para proteger la privacidad.

RNF-02. Rastreabilidad de lotes.
Como veterinario,
quiero poder vincular cada vacuna administrada y cada medicamento dispensado a su lote,
para actuar con rapidez ante una retirada de producto.

RNF-03. Tiempo de respuesta.
Como recepcionista,
 quiero que la búsqueda por microchip y la consulta de la agenda diaria respondan en menos de 2 segundos,
para no hacer esperar a los clientes.

-- fin entregable 1 --

