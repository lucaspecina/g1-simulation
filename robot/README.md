# robot/

Lo que este repo tiene para el G1 físico.

- [`rtsp/rtsp_from_zmq.py`](rtsp/rtsp_from_zmq.py) — transmite por RTSP el
  video que ya reparte `teleimager-server` (JPEG por ZMQ), sin tomar la
  cámara: así convive con una política que la está usando. Probado el
  30-oct-2026 a 640×360 y 30 cuadros por segundo con menos del 20 % de CPU.
  Se corre en el robot con el Python del entorno `teleoperation` y `ffmpeg`.
- Teleoperación en simulación:
  [`docs/07_receta_teleoperacion.md`](../docs/07_receta_teleoperacion.md).
- Integración del sistema de la demo con el robot:
  [`g1/REAL_ROBOT_INTEGRATION.md`](../g1/REAL_ROBOT_INTEGRATION.md).

Grabar episodios, convertirlos y entrenar políticas está en
[g1-robot-learning](https://github.com/lucaspecina/g1-robot-learning).

Las direcciones, credenciales y detalles de la unidad concreta van en
`private/`, no acá.
