# Máquina de Anestesia WATO EX-20 

**Asignatura:** Instrumentación Biomédica  
**Equipo:** WATO EX-20 — Shenzhen Mindray Bio-Medical Electronics Co., Ltd.  
**Fuentes principales:** Manual del Operador WATO EX-20 (Mindray, 2009) · Service Manual WATO EX-20/30/35 (Mindray, 2013)

---
## Tabla de Contenidos

- [Tipos de anestesia durante una cirugía](#tipos-de-anestesia-durante-una-cirugía)
- [Gases de trabajo y sistema de alta presión](#gases-de-trabajo-y-sistema-de-alta-presión)
- [Sistema de respiración](#sistema-de-respiración)
- [Submenús del ventilador](#submenús-del-ventilador)
- [Partes de la máquina de anestesia WATO EX-20](#Partes-de-la-máquina-de-anestesia-wato-ex-20)
- [Mensaje "batería en uso" con paciente conectado](#mensaje-batería-en-uso-con-paciente-conectado)
- [Frecuencia de reemplazo del recipiente absorbente de CO₂](#frecuencia-de-reemplazo-del-recipiente-absorbente-de-co)
- [Verificación de fuga en cilindro de alta presión](#verificación-de-fuga-en-cilindro-de-alta-presión)
- [Influencia del sensor de O₂ en la prueba de control de flujo](#influencia-del-sensor-de-o-en-la-prueba-de-control-de-flujo)
- [Sistema de presión negativa](#sistema-de-presión-negativa)
- [Descripción de la práctica](#descripción-de-la-práctica)
- [Referencias](#referencias)
---

## Tipos de Anestesia durante una Cirugía

### Anestesia General

Estado de inconsciencia completa inducido farmacológicamente, que implica analgesia, amnesia y relajación muscular. El paciente pierde los reflejos protectores de la vía aérea y requiere soporte ventilatorio mecánico. Se administra por vía inhalatoria (agentes volátiles como sevoflurano, isoflurano o desflurano, mezclados con O₂ y/o N₂O) y/o intravenosa (propofol, ketamina, opioides). Es el tipo de anestesia para el cual la WATO EX-20 está diseñada (Butterworth et al., 2022).

### Anestesia Regional

Bloqueo de la transmisión nerviosa en una región específica del cuerpo sin afectar la consciencia del paciente. Incluye tres modalidades principales:

- **Epidural/Peridural:** el anestésico se deposita en el espacio epidural de la columna vertebral, bloqueando los nervios espinales. Se usa en cirugías abdominales bajas, pelvianas y obstétricas.
- **Espinal o subaracnoidea (raquídea):** inyección directa en el espacio subaracnoideo, produciendo un bloqueo más rápido e intenso. Indicada en cirugías de miembros inferiores, urológicas y obstétricas.
- **Bloqueo de nervio periférico:** bloqueo de un nervio o plexo específico (p. ej., plexo braquial) guiado por ultrasonido o neuroestimulación. Se aplica en cirugías de extremidades (Barash et al., 2017).

### Anestesia Local

Aplicación del anestésico directamente en el sitio quirúrgico, bloqueando los nociceptores locales. El paciente permanece completamente consciente. Se emplea en procedimientos menores como suturas, biopsias y cirugía dermatológica, o como complemento de técnicas regionales (Morgan & Mikhail, 2018).

### Sedoanalgesia

Combinación de sedantes y analgésicos que reduce el nivel de consciencia sin eliminarlo. El paciente responde a estímulos verbales y conserva los reflejos protectores de la vía aérea. Se usa en procedimientos diagnósticos (endoscopias, colonoscopias) y cirugías menores ambulatorias (Barash et al., 2017).

---

## Gases de Trabajo y Sistema de Alta Presión

La WATO EX-20 trabaja con tres gases médicos: oxígeno (O₂), óxido nitroso (N₂O) y aire medicinal (Air). El equipo dispone de suministro por tubería central (280–600 kPa) y por cilindros de alta presión como respaldo (Mindray, 2013).

### Oxígeno — O₂

Cumple dos roles simultáneos: mantener la oxigenación del paciente durante la ventilación y actuar como gas impulsor (drive gas) del fuelle del ventilador. El sistema monitorea continuamente la presión de suministro; si desciende por debajo de ~200 kPa, se activa la alarma de falla de O₂ (Mindray, 2013).

### Óxido Nitroso — N₂O

Agente anestésico inhalatorio con propiedades analgésicas. Reduce la concentración mínima alveolar (CAM) de los agentes halogenados, disminuyendo la dosis necesaria de estos. Debe administrarse siempre en mezcla con O₂ (FiO₂ mínima del 30%) para evitar hipoxia. Está contraindicado en neumotórax, obstrucción intestinal y cirugía ótica, entre otros (Dorsch & Dorsch, 2008).

### Aire Medicinal — Air

Gas diluente alternativo al N₂O cuando este está contraindicado, o para obtener una FiO₂ ajustable sin N₂O. Permite ventilación con mezclas de O₂/Aire controladas.

### Incorporación por sistema de alta presión

Los tres gases (O₂, N₂O y Aire) pueden incorporarse mediante cilindros de alta presión. El gas sale del cilindro a alta presión, pasa por un regulador que la reduce a ~200 kPa y cuenta con una válvula de alivio que libera el exceso si supera ~750 kPa (Mindray, 2013).

---

## Sistema de Respiración

### Definición y función

El sistema de respiración es el conjunto de componentes que forman el circuito neumático entre la máquina y el paciente. Se conecta a la unidad principal mediante un adaptador de circuito (Mindray, 2013). Sus funciones son:

1. Suministrar la mezcla de gas fresco con agente anestésico al paciente.
2. Eliminar el CO₂ espirado mediante el absorbente (cal sodada o cal baritada).
3. Recircular el gas no consumido en un sistema circular de bajo flujo, reduciendo el consumo de agentes y gases.
4. Monitorear la presión en la vía aérea.

Durante la inspiración, el gas impulsor comprime el fuelle (bellows), empujando el volumen corriente al paciente a través de la válvula inspiratoria. Durante la espiración, el gas regresa por la válvula espiratoria, pasa por el canister donde el CO₂ es absorbido, y el gas depurado retorna al fuelle para el siguiente ciclo (Mindray, 2013).

### Componentes del sistema de respiración

| Componente | Función |
|---|---|
| Válvula de retención inspiratoria | Flujo unidireccional hacia el paciente |
| Válvula de retención espiratoria | Flujo unidireccional desde el paciente |
| Fuelle (Bellows) | Reservorio e impulsor del volumen corriente |
| Canister de absorbente de CO₂ | Elimina el CO₂ expirado |
| Tubo en Y | Conexión con el circuito del paciente |
| Tubos corrugados (inspiratorio/espiratorio) | Conductos de gas |
| Manómetro de vía aérea | Indica la presión del circuito en tiempo real |
| Válvula APL | Limita la presión en ventilación manual |
| Bolsa manual | Ventilación manual por el anestesiólogo |
| Interruptor Bolsa/Ventilador | Selección del modo de ventilación |
| Sensor de O₂ | Monitoreo de la FiO₂ en el circuito |

### Partes esterilizables por autoclave

La WATO EX-20 cuenta con un circuito de respiración totalmente autoclavable a 134 °C (Mindray, 2018). Las partes que admiten este método son:

- Tubos corrugados inspiratorio y espiratorio
- Pieza en Y
- Válvulas de retención inspiratoria y espiratoria (desmontables)
- Carcasa del canister de CO₂
- Carcasa del fuelle
- Bolsa manual

**No se autoclavan:** el sensor de O₂, el manómetro y los componentes electrónicos. Estos deben desinfectarse con métodos químicos de nivel intermedio o alto según las instrucciones del fabricante.

---

## Submenús del Ventilador

El ventilador de la WATO EX-20 dispone de cuatro modos de ventilación mecánica, seleccionables desde la tecla `[Modo vent]` en la pantalla principal (Mindray, 2009).

### Ventilación por Control de Volumen

Se programa un volumen corriente (VT) fijo que el ventilador entrega en cada ciclo con flujo constante, independientemente de la presión resultante en la vía aérea. Los parámetros ajustables son: VT, frecuencia respiratoria (FR), relación I:E, flujo inspiratorio, límite de presión (Plimit) y PEEP.

**La pausa inspiratoria se activa en este modo.** Al interrumpir el flujo al final de la inspiración durante un tiempo determinado, se obtiene la presión de meseta (Pplat), que permite calcular la compliance estática del sistema respiratorio: `Cst = VT / (Pplat − PEEP)` (Mindray, 2009).

### PCV — Ventilación por Control de Presión

Se programa un nivel de presión inspiratoria fija. El volumen entregado varía según la compliance y resistencia pulmonar del paciente. El flujo tiene perfil desacelerado, lo que favorece una distribución más homogénea del gas en los alvéolos. Los parámetros ajustables son: Pcontrol, FR, I:E y PEEP (Mindray, 2013).

### SIMV-VC — Ventilación Obligatoria Intermitente Sincronizada con Control de Volumen

Combina ciclos mandatorios en VCV con respiraciones espontáneas del paciente entre dichos ciclos. El ventilador sincroniza los ciclos obligatorios con el esfuerzo inspiratorio. Permite reducir gradualmente el soporte ventilatorio durante el destete de la anestesia (Mindray, 2013).

### SIMV-PC — Ventilación Obligatoria Intermitente Sincronizada con Control de Presión

Similar al SIMV-VC, pero los ciclos mandatorios se ejecutan en modo de control de presión. Indicado en pacientes con patología pulmonar donde se requiere limitar la presión máxima en la vía aérea. Las respiraciones espontáneas pueden recibir soporte adicional mediante Presión de Soporte (PS) (Mindray, 2013).

### Tabla resumen

| Modo | Variable de control | Pausa inspiratoria | Respiración espontánea |
|---|---|---|---|
| VCV | Volumen fijo | Disponible | No |
| PCV | Presión fija | No disponible | No |
| SIMV-VC | Volumen (ciclos mandatorios) | No disponible | Sí |
| SIMV-PC | Presión (ciclos mandatorios) | No disponible | Sí |

---
## Partes de la máquina de anestesia WATO EX-20
---
## Si el ventilador muestra el mensaje “batería en uso” y el paciente se encuentra
conectado a la máquina ¿Qué acción debería ejecutarse?
---
## Frecuencia de reemplazo el recipiente absorbente de CO2
---
## procedimiento para verificar si hay fuga en el cilindro de alta presión
---
## ¿Influye el contar o no con el sensor de O2 al hacer la prueba sobre el sistema de control de flujo? ¿De qué forma?
---
## ¿Para qué se requiere el sistema de presión negativa?
---
## Descripción de la práctica
• Análisis 1: Revise sobre las fallas que pueden presentarse en el
funcionamiento de alguno de los subsistemas que componen la máquina de
anestesia, así como lo que las produce.
• Análisis 2: Ordene cada subsistema de la máquina en función del número
de fallas asociadas a este (de mayor a menor,) de acuerdo con la
información suministrada por el manual de operación.

• Pregunta 1: ¿Qué tipos de anestésicos son los más usados en cirugía?

• Pregunta 2: ¿Qué diferencias plantea el modelo EX-35 con respecto al EX-
20?

---
## Referencias

Barash, P. G., Cullen, B. F., Stoelting, R. K., Cahalan, M. K., Stock, M. C., & Ortega, R. (2017). *Clinical anesthesia* (8.a ed.). Wolters Kluwer.

Butterworth, J. F., Mackey, D. C., & Wasnick, J. D. (2022). *Morgan & Mikhail's clinical anesthesiology* (7.a ed.). McGraw-Hill Education.

Dorsch, J. A., & Dorsch, S. E. (2008). *Understanding anesthesia equipment* (5.a ed.). Lippincott Williams & Wilkins.

Mindray. (2009). *Equipo de anestesia WATO EX-20: Manual del operador* (Rev. 1.0). Shenzhen Mindray Bio-Medical Electronics Co., Ltd.

Mindray. (2013). *WATO EX-20/30/35 anesthesia machine service manual* (Rev. 8.0). Shenzhen Mindray Bio-Medical Electronics Co., Ltd.

Mindray. (2013). *Equipo de anestesia WATO EX-30: Manual del operador*. Shenzhen Mindray Bio-Medical Electronics Co., Ltd.

Mindray. (2018). *WATO EX-20 anesthesia machine — Product brochure*. Shenzhen Mindray Bio-Medical Electronics Co., Ltd. https://technowave-eg.com/download/WATO_EX-20_Brochure_ENG_20180601_s.pdf

Morgan, G. E., & Mikhail, M. S. (2018). *Clinical anesthesiology* (6.a ed.). McGraw-Hill Education.
