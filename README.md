# Complementariedad de la IA en Grandes Aglomerados Urbanos (Argentina, 2024)
Este repositorio contiene el código y la documentación del proyecto empírico final para la materia Econometría I de la Universidad Nacional de La Plata. El estudio analiza si existe una prima salarial para los trabajadores cuyas habilidades complementan a la Inteligencia Artificial en el mercado laboral argentino.

# Objetivo

Explorar la relación entre la capacidad de adaptación tecnológica de los trabajadores y sus remuneraciones, diferenciando el impacto según el tamaño del aglomerado urbano (grandes urbes vs. ciudades menores).
 Metodología

Se utilizó un modelo de Mínimos Cuadrados Ordinarios (MCO) con errores estándar robustos para estimar el logaritmo del salario horario:

lsalarioi​=β^​1​+β^​2​comp_iai​+β^​3​grandes_urbesi​+β^​4​(comp_iai​⋅grandes_urbesi​)+…

    Datos: Encuesta Permanente de Hogares (EPH), segundo semestre de 2024.

    Controles: Formalidad laboral, género, edad y niveles educativos (media/alta).

# Hallazgos Principales

Los resultados de la regresión indican que la tecnología no impacta de forma homogénea en el territorio:

    Prima por IA: Los trabajadores con tareas complementarias a la IA ganan, en promedio, un 16,4% más en aglomerados pequeños.

    Efecto de Interacción: En las grandes urbes, la recompensa salarial por complementar habilidades con la IA es un 9% mayor que en urbes pequeñas, manteniendo todo lo demás constante.

    Brechas persistentes: Se confirmaron primas significativas por formalidad y persistencia de brechas de género y educación.
