# vet-calculators

Calculadoras clínicas veterinarias (HTML standalone, sin servidor).

**URL en vivo:** https://mrodher.github.io/vet-calculators/

## Disponibles

- **Transfusión sanguínea** (`index.html`) — volumen de sangre entera para alcanzar PCV objetivo en perro / gato. Incluye validaciones, alertas clínicas y fórmula desplegada.

## Roadmap

- Convertidor de reportes laboratoriales D'León (5 estudios vet).
- Calculadora de dosis IRIS (estadios renales en perro / gato).
- Dosis de líquidos / electrolitos.

## Fórmula de referencia (transfusión)

```
mL sangre entera = Peso(kg) × VS(mL/kg) × (PCV_deseado − PCV_actual) / PCV_donador
```

VS: 90 mL/kg perro, 60 mL/kg gato (editable).

Fuente: Plumb's Veterinary Drug Handbook · BSAVA Manual of Canine and Feline Haematology and Transfusion Medicine.
