# Taller 3: Ejecución de Consultas SQL

## Objetivo
En base a una Base de Datos dada, resolver cada paso:

---

## O1: Preparación del Entorno

### Descripción
Accede a la base de datos predefinida y familiarízate con las tablas disponibles (Clientes, Pedidos, Productos, DetallePedido).

### Tareas a Completar

#### 1.1 Conexión a la Base de Datos
- **Base de Datos:** ___________________
- **Servidor:** ___________________
- **Usuario:** ___________________
- **Contraseña:** ___________________

#### 1.2 Exploración de Tablas
Completa la información de cada tabla:

**Tabla: CLIENTES**
- Campos: ___________________
- Clave Primaria: ___________________
- Cantidad de registros: ___________________

**Tabla: PEDIDOS**
- Campos: ___________________
- Clave Primaria: ___________________
- Claves Foráneas: ___________________
- Cantidad de registros: ___________________

**Tabla: PRODUCTOS**
- Campos: ___________________
- Clave Primaria: ___________________
- Cantidad de registros: ___________________

**Tabla: DETALLEPEDIDO**
- Campos: ___________________
- Clave Primaria: ___________________
- Claves Foráneas: ___________________
- Cantidad de registros: ___________________

#### 1.3 Captura de Pantalla
[Pega aquí la captura de pantalla de la conexión exitosa]

---

## O2: Selección de Desafío

### Descripción
Elige uno de los problemas de negocio planteados o un escenario adicional provisto por el instructor para resolver.

### Problemas de Negocio Disponibles

#### Opción 1: Análisis de Ventas
Descripción: ___________________

#### Opción 2: Gestión de Inventario
Descripción: ___________________

#### Opción 3: Satisfacción del Cliente
Descripción: ___________________

#### Opción 4: Escenario Personalizado
Descripción: ___________________

### Desafío Seleccionado
**Número de Opción:** ___

**Descripción del Desafío:**
___________________________________________________

**Objetivo:**
___________________________________________________

**Resultado Esperado:**
___________________________________________________

---

## O3: Diseño de la Consulta

### Descripción
Utiliza tu plantilla de éxito: identifica tablas, PK/FK, el tipo de JOIN, filtros y agregaciones necesarios.

### Plantilla de Diseño

#### 3.1 Identificación de Tablas
Tablas involucradas:
- [ ] CLIENTES
- [ ] PEDIDOS
- [ ] PRODUCTOS
- [ ] DETALLEPEDIDO

#### 3.2 Relaciones y Claves
| Tabla 1 | Tabla 2 | Clave Foránea | Relación |
|---------|---------|---------------|----------|
| _______ | _______ | _____________ | ________ |
| _______ | _______ | _____________ | ________ |

#### 3.3 Tipo de JOIN
- [ ] INNER JOIN
- [ ] LEFT JOIN
- [ ] RIGHT JOIN
- [ ] FULL OUTER JOIN
- [ ] CROSS JOIN

Justificación: ___________________________

#### 3.4 Filtros (WHERE)
Condiciones a aplicar:
- Condición 1: ___________________________
- Condición 2: ___________________________
- Condición 3: ___________________________

#### 3.5 Agregaciones
- [ ] COUNT
- [ ] SUM
- [ ] AVG
- [ ] MAX
- [ ] MIN
- [ ] GROUP BY

Especificar: ___________________________

#### 3.6 Ordenamiento
- Campo: ___________________________
- Tipo: [ ] ASC [ ] DESC

### Diagrama de Flujo
```
[Dibuja o describe el flujo de la consulta]

Inicio
  ↓
[Tabla 1] → [JOIN] → [Tabla 2]
  ↓
[Filtros]
  ↓
[Agregaciones]
  ↓
[Resultado]
```

---

## O4: Ejecución y Evidencia

### Descripción
Escribe y ejecuta tu consulta. Captura una captura de pantalla del código SQL y de los resultados obtenidos.

### 4.1 Código SQL

```sql
-- Tu consulta SQL aquí
-- Escribe la consulta que diseñaste



```

### 4.2 Resultado de la Consulta

#### Captura de Pantalla del Código
[Pega aquí la captura de pantalla con el código SQL]

#### Captura de Pantalla de Resultados
[Pega aquí la captura de pantalla con los resultados obtenidos]

#### Resultado en Texto
| Columna 1 | Columna 2 | Columna 3 |
|-----------|-----------|-----------|
| _________ | _________ | _________ |
| _________ | _________ | _________ |
| _________ | _________ | _________ |

**Total de filas retornadas:** ___________

---

## O5: Validación de Resultados

### Descripción
Verifica manualmente que los resultados tengan sentido, siguiendo los puntos de control de validación discutidos.

### Lista de Validación

- [ ] **Número de filas:** ¿Es el número esperado de resultados?
  - Esperado: ___________
  - Obtenido: ___________
  - ✓ Válido: [ ] Sí [ ] No
  - Observaciones: ___________________________

- [ ] **Valores nulos:** ¿Hay valores NULL inesperados?
  - Campos con NULL: ___________________________
  - ✓ Válido: [ ] Sí [ ] No
  - Observaciones: ___________________________

- [ ] **Rangos de datos:** ¿Los valores están dentro del rango esperado?
  - Rango esperado: ___________________________
  - Rango obtenido: ___________________________
  - ✓ Válido: [ ] Sí [ ] No
  - Observaciones: ___________________________

- [ ] **Duplicados:** ¿Hay registros duplicados inesperados?
  - Duplicados encontrados: [ ] Sí [ ] No
  - ✓ Válido: [ ] Sí [ ] No
  - Observaciones: ___________________________

- [ ] **Coherencia lógica:** ¿Los datos son coherentes entre sí?
  - Verificación: ___________________________
  - ✓ Válido: [ ] Sí [ ] No
  - Observaciones: ___________________________

- [ ] **Agregaciones:** Si hay SUM, AVG, COUNT, etc., ¿son correctos?
  - Verificación manual: ___________________________
  - ✓ Válido: [ ] Sí [ ] No
  - Observaciones: ___________________________

### Resultado de Validación
- **Estado General:** [ ] VÁLIDO [ ] INVÁLIDO [ ] CON OBSERVACIONES
- **Acciones correctivas necesarias:** ___________________________

---

## O6: Justificación

### Descripción
Describe y explica la lógica y las decisiones tomadas en el diseño de tu consulta.

### 6.1 Resumen de la Consulta
**Objetivo:** ___________________________________________________

**Tablas utilizadas:** ___________________________________________________

**JOINs principales:** ___________________________________________________

---

### 6.2 Explicación de Decisiones

#### Decisión 1: Selección de Tablas
**¿Por qué se seleccionaron estas tablas?**
___________________________________________________________

#### Decisión 2: Tipo de JOIN
**¿Por qué se utilizó este tipo de JOIN?**
- Consideraciones: ___________________________________________________
- Alternativas rechazadas: ___________________________________________________
- Justificación final: ___________________________________________________

#### Decisión 3: Filtros (WHERE)
**¿Por qué se aplicaron estos filtros?**
- Filtro 1: ___________________________________________________
- Filtro 2: ___________________________________________________
- Filtro 3: ___________________________________________________

#### Decisión 4: Agregaciones
**¿Por qué se utilizaron estas agregaciones?**
___________________________________________________________

#### Decisión 5: Ordenamiento
**¿Por qué se ordenó de esta manera?**
___________________________________________________________

---

### 6.3 Lógica del Negocio
**¿Cómo responde esta consulta al desafío planteado?**
___________________________________________________________

___________________________________________________________

**Impacto en la toma de decisiones:**
___________________________________________________________

___________________________________________________________

---

### 6.4 Análisis de Resultados
**¿Qué insights se obtienen de los resultados?**

- Insight 1: ___________________________________________________
- Insight 2: ___________________________________________________
- Insight 3: ___________________________________________________

**Recomendaciones basadas en los resultados:**
1. ___________________________________________________
2. ___________________________________________________
3. ___________________________________________________

---

### 6.5 Conclusión
Resumen general de la solución implementada:

___________________________________________________________

___________________________________________________________

___________________________________________________________

---

## Resumen General del Taller

| Paso | Estado | Observaciones |
|------|--------|---------------|
| O1: Preparación | [ ] Completo | _________________ |
| O2: Selección | [ ] Completo | _________________ |
| O3: Diseño | [ ] Completo | _________________ |
| O4: Ejecución | [ ] Completo | _________________ |
| O5: Validación | [ ] Completo | _________________ |
| O6: Justificación | [ ] Completo | _________________ |

**Calificación General:** _____ / 100

**Firma del Estudiante:** _________________ **Fecha:** _______

**Firma del Instructor:** _________________ **Fecha:** _______