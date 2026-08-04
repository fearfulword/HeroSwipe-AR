# 🦸‍♂️ HeroSwipe AR

¡Un proyecto nacido puramente por entretención para experimentar con Realidad Aumentada (AR)! 

## 💡 ¿De qué trata y cómo funciona?
La idea central de este programa es súper simple y divertida: usar la cámara web para detectar mi rostro y superponer distintas máscaras virtuales en tiempo real (como la de Spiderman, Batman, entre otras). 

Lo entretenido es cómo se interactúa con el programa. En lugar de usar el teclado o el mouse, funciona con **control por gestos**:
1. El programa lee los movimientos de mis manos.
2. Al levantar dos dedos (índice y medio) y hacer un movimiento rápido hacia la izquierda ("swipe").
3. El código detecta el gesto y cambia automáticamente la máscara que llevo puesta en la pantalla.

## 🖼️ En Acción
*(Aquí irán las imágenes y capturas de pantalla de las máscaras funcionando próximamente)*

## 🛠️ Herramientas utilizadas
Para darle vida a esta idea, estoy usando:
* **Python**
* **OpenCV:** Para manejar la captura de video de la cámara.
* **MediaPipe:** Para que el programa sea capaz de trackear tanto los puntos de mi cara como los de mis manos al mismo tiempo.
