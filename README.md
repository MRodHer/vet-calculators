# vet-calculators

Calculadoras clínicas veterinarias (HTML standalone, sin servidor).

**URL en vivo:** https://mrodher.github.io/vet-calculators/

## Disponibles

- **Transfusión sanguínea** (`index.html` · [abrir](https://mrodher.github.io/vet-calculators/)) — volumen de sangre entera para alcanzar PCV objetivo en perro / gato. Incluye validaciones, alertas clínicas y fórmula desplegada.
- **Ondas de choque (ESWT)** (`shockwave.html` · [abrir](https://mrodher.github.io/vet-calculators/shockwave.html)) — protocolo sugerido (frecuencia, energía, pulsos, sesiones, intervalo) por especie / peso / indicación / severidad. Calibrado para equipo radial 1-18 Hz, 10-300 mJ. Incluye contraindicaciones, técnica y guía de sedación.

## Roadmap

- Convertidor de reportes laboratoriales D'León (5 estudios vet).
- Calculadora de dosis IRIS (estadios renales en perro / gato).
- Dosis de líquidos / electrolitos.

## Fórmulas de referencia

### Transfusión

```
mL sangre entera = Peso(kg) × VS(mL/kg) × (PCV_deseado − PCV_actual) / PCV_donador
```

VS: 90 mL/kg perro, 60 mL/kg gato (editable).

### Ondas de choque

Sin fórmula cerrada — protocolo se construye a partir de:

```
energía base × factor_peso × factor_severidad   (mJ por pulso)
pulsos base × factor_peso × factor_severidad    (pulsos por sitio)
```

Tablas de referencia derivadas de protocolos equinos/caninos adaptados y consensos veterinarios de ESWT en pequeños animales.

## Fuentes

- Plumb's Veterinary Drug Handbook.
- BSAVA Manual of Canine and Feline Haematology and Transfusion Medicine.
- Millis & Levine, *Canine Rehabilitation and Physical Therapy* (2.ª ed.).
- Consensus statements de VOSRA / AAR-VPC sobre ESWT en pequeños animales.
- Protocolos PulseVet / ProPulse adaptados a equipo radial / balístico.
