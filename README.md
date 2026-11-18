# tanda_dolorena

Aplicación Flutter para administrar una tanda dolorense mediante reglas de negocio desarrolladas con TDD.

## Ejecutar

```bash
flutter pub get
flutter test
flutter run
```

Las rondas del proceso TDD están documentadas en [ETAPAS.md](ETAPAS.md).

## Evidencia de pruebas

La suite comprueba aportaciones, participantes, cierre de rondas, turnos y finalización de la tanda. Resultado: **13 pruebas aprobadas**.

### Ciclo TDD: rojo a verde

Ambas capturas fueron tomadas de ejecuciones reales en la terminal integrada de Visual Studio Code: la fase roja muestra `undefined_function` por código aún no implementado y la fase verde muestra la suite final aprobada.

| 🔴 Prueba que solicita código faltante | 🟢 Implementación terminada |
|---|---|
| ![Error real por código faltante en la terminal de VS Code](capturas/tdd_rojo_error.png) | ![Pruebas aprobadas en la terminal de VS Code](capturas/pruebas_vscode.png) |
