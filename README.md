# NÚCLEO — kernel PHP

Paquete de ejecución de la tesis. No es el briefing (eso es significado). No es
`alquiler-equipos-sonido` (eso es otro producto).

```
AGENT → INTENT → DELEGATION → CAPABILITY → POLICY
     → AUTHORIZATION → EXECUTION → VERIFICATION
     → RECONCILIATION → EVIDENCE
```

Un agente comprometido no compromete el dominio, la infraestructura ni el tesoro.

## Frontera

| Artefacto | Qué es | Qué no es |
|---|---|---|
| Briefing NÚCLEO | Significado, mapa, laboratorio | Código de dominio PHP |
| `clarity/nucleo` | Contratos, hold-pipe, evidencia | Symfony, Stripe, SQL |
| alquiler-equipos-sonido | Producto de alquiler de sonido | Turismo, ni este kernel |

Si el producto de alquiler quiere estas fronteras, las **requiere**. No las absorbe.

```bash
composer install
vendor/bin/phpunit
```

Los tests de `tests/BoundariesTest.php` fallan el día que un contexto importe a otro,
o que el dominio mencione Stripe, PDO o HttpRequest.
