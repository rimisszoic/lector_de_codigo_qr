# Documentación del Escáner de Código QR

## Uso

Este escáner de código QR te permite leer códigos QR utilizando la cámara de tu dispositivo. Sigue los siguientes pasos para utilizarlo:

1. Haz clic en el botón "Escanear Código QR".
2. Apunta la cámara hacia el código QR que deseas escanear.
3. Cuando el escáner detecte y lea el código QR, se mostrará el resultado del escaneo en el área designada.

## Componentes

### Botón de Escaneo

El botón "Escanear Código QR" activa el modal que contiene el escáner de código QR.

### Modal de Escaneo

El modal contiene el escáner de código QR y muestra el resultado del escaneo.

### Escáner de Código QR

El área donde se muestra la vista previa de la cámara y se detectan los códigos QR.

### Resultado del Escaneo

El área donde se muestra el resultado del escaneo.

## Scripts

### Funciones de Escaneo

Las funciones `onScanSuccess` y `onScanError` manejan el resultado del escaneo.

### Reinicio del Escáner

La función `restartScanner` reinicia el escáner después de un escaneo exitoso.

### Configuración del Escáner

Se crea una instancia del escáner de código QR con la configuración especificada.

## Notas

- El modal se cerrará automáticamente después de 2 segundos una vez que se haya escaneado correctamente un código QR.
- El escáner se reiniciará automáticamente para futuros usos después de cerrar el modal.

**Nota importante:** Asegúrate de cambiar el ID del elemento donde deseas colocar el resultado del escaneo. En este caso, el ID es `form-field-idTicket`, pero debes reemplazarlo por el ID del elemento de entrada deseado en tu entorno, ya que esta guía es genérica y no tiene acceso al contexto específico del input destino. Este cambio es necesario para que el resultado del escaneo se coloque correctamente en el input deseado.
