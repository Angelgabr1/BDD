# BDD
-Muestro el resulatado de la Tabla:
``` sql 
┌────┬───────────┬─────────┬──────────────────┐
│ id │  nombre   │ salario │   departamento   │
├────┼───────────┼─────────┼──────────────────┤
│ 1  │ Juan      │ 50000.0 │ Ventas           │
│ 2  │ María     │ 60000.0 │ TI               │
│ 3  │ Carlos    │ 55000.0 │ Ventas           │
│ 4  │ Ana       │ 48000.0 │ Recursos Humanos │
│ 5  │ Pedro     │ 70000.0 │ TI               │
│ 6  │ Laura     │ 52000.0 │ Ventas           │
│ 7  │ Javier    │ 48000.0 │ Recursos Humanos │
│ 8  │ Carmen    │ 65000.0 │ TI               │
│ 9  │ Miguel    │ 51000.0 │ Ventas           │
│ 10 │ Elena     │ 55000.0 │ Recursos Humanos │
│ 11 │ Diego     │ 72000.0 │ TI               │
│ 12 │ Sofía     │ 49000.0 │ Ventas           │
│ 13 │ Andrés    │ 60000.0 │ Recursos Humanos │
│ 14 │ Isabel    │ 53000.0 │ TI               │
│ 15 │ Raúl      │ 68000.0 │ Ventas           │
│ 16 │ Patricia  │ 47000.0 │ Recursos Humanos │
│ 17 │ Alejandro │ 71000.0 │ TI               │
│ 18 │ Natalia   │ 54000.0 │ Ventas           │
│ 19 │ Roberto   │ 49000.0 │ Recursos Humanos │
│ 20 │ Beatriz   │ 63000.0 │ TI               │
└────┴───────────┴─────────┴──────────────────┘
```
--Una vez creada la tabla empezaremos a realizar las consultas

-Aplicampos la funcion UPPER y LOWER a la propiedad nombre.

``` sql
┌───────────────────┬───────────────────┐
│ nombre_mayusculas │ nombre_minusculas │
├───────────────────┼───────────────────┤
│ JUAN              │ juan              │
│ MARíA             │ maría             │
│ CARLOS            │ carlos            │
│ ANA               │ ana               │
│ PEDRO             │ pedro             │
│ LAURA             │ laura             │
│ JAVIER            │ javier            │
│ CARMEN            │ carmen            │
│ MIGUEL            │ miguel            │
│ ELENA             │ elena             │
│ DIEGO             │ diego             │
│ SOFíA             │ sofía             │
│ ANDRéS            │ andrés            │
│ ISABEL            │ isabel            │
│ RAúL              │ raúl              │
│ PATRICIA          │ patricia          │
│ ALEJANDRO         │ alejandro         │
│ NATALIA           │ natalia           │
│ ROBERTO           │ roberto           │
│ BEATRIZ           │ beatriz           │
└───────────────────┴─────────────────
```