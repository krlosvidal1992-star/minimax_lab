# minimax_lab
ato Persigue al raton - Juego de IA con Minimax
📖 ¿Qué creé?
Un juego donde un gato inteligente persigue a un ratón en un tablero 5x5. Ambos usan el algoritmo Minimax para tomar decisiones.

✅ Lo que funcionó:
Minimax implementado correctamente

Sistema de turnos fluido

Interfaz simple pero clara

💥 El desastre:
Muy lento con profundidad > 2

Ratón a veces se suicida moviéndose hacia el gato

Sin equilibrio - gato casi siempre gana

💡 ¡Mi mejor "¡ajá!":
Descubrí que la magia está en que el gato busca valores altos (acercarse) y el ratón busca valores bajos (alejarse). ¡Esa dualidad hace que ambos "piensen" de forma opuesta!

python
# Esta línea lo resume todo:
return 999 if es_gato else -999  # Ganar es diferente para cada uno
Un proyecto pequeño que me enseñó mucho sobre IA básica.
