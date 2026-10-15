## Funcionalidades

| Arranque de la app | `main.dart`, `ui/pantalla_principal.dart` | `main()`, `cargar()` |
| Cargar incidencias al abrir | `services/gestor_incidencias.dart`, `data/almacen_local.dart` | `iniciar()`, `leer()` |
| Guardar en el dispositivo | `data/almacen_local.dart` | `guardar()` |
| Datos de ejemplo (semilla) | `assets/data/incidencias.json`, `data/almacen_local.dart` | `leer()` |
| Mostrar la lista | `ui/pantalla_principal.dart` | `build()` |
| Ver detalle | `ui/pantalla_principal.dart`, `ui/pantalla_detalle.dart`, `services/gestor_incidencias.dart` | `abrirDetalle()`, `porId()` |
| Cambio de estado | `ui/pantalla_detalle.dart`, `services/gestor_incidencias.dart` | `cambiar()`, `cambiarEstado()` |
| Registrar incidencia | `ui/pantalla_nueva.dart`, `services/gestor_incidencias.dart` | `guardar()`, `crear()` |
| Búsqueda | `ui/pantalla_principal.dart`, `services/gestor_incidencias.dart` | `buscar()` |
| Contadores del tablero | `ui/pantalla_principal.dart`, `services/gestor_incidencias.dart` | `resumen()`, `contar()` |
| Restablecer demostración | `ui/pantalla_principal.dart`, `services/gestor_incidencias.dart`, `data/almacen_local.dart` | `reiniciarDemo()`, `restaurarDatosDeEjemplo()` |

## Tickets

| BUG-001 Estado que desaparece | `ui/pantalla_detalle.dart`, `services/gestor_incidencias.dart`, `data/almacen_local.dart` |

