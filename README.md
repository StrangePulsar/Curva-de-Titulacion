# Titulación Ácido-Base

Este proyecto explora las curvas de titulación ácido-base, una herramienta fundamental en química analítica para determinar la concentración de una disolución desconocida. A través de este notebook, se describe cómo construir y analizar estas curvas utilizando conceptos teóricos y herramientas computacionales.

## Contexto

La titulación ácido-base es una técnica analítica que permite determinar la concentración de una disolución (analito) al hacerla reaccionar con una disolución de concentración conocida (titulante). Las curvas de titulación grafican el pH de la disolución conforme se agrega titulante, proporcionando información clave sobre el equilibrio químico y las propiedades del sistema.

### Casos abordados

1. **Ácido débil con base fuerte**: Análisis teórico del equilibrio de disociación del ácido y el impacto del titulante.
2. **Curva de titración**: Representación gráfica de pH vs. volumen de titulante, destacando puntos clave como el punto de equivalencia.

### Aplicaciones

- Determinación de concentraciones desconocidas.
- Estudio de constantes de equilibrio (ácida o básica).
- Caracterización del comportamiento químico de soluciones.

## Contenido del Notebook

El notebook incluye:

1. **Introducción teórica**:
   - Definiciones de ácido débil, base fuerte y equilibrio de disociación.
   - Explicación de las constantes de disociación ácida ($K_a$).
2. **Análisis matemático**:
   - Derivación de ecuaciones para calcular concentraciones de especies en disolución.
   - Relación entre concentraciones y pH.
3. **Visualizaciones**:
   - Gráficos de curvas de titulación ácido-base.
   - Identificación de puntos clave como el punto de equivalencia.

## Tecnologías Utilizadas

- **Python**: Lenguaje de programación principal.
- **Bibliotecas**:
  - `numpy` para cálculos matemáticos.
  - `matplotlib` y `seaborn` para visualización de datos.

## Instrucciones de Uso

1. Clona este repositorio en tu máquina local:
   ```bash
   git clone https://github.com/tu_usuario/curva-titulacion.git
   ```

2. Instala las dependencias necesarias:
   ```bash
   pip install -r requirements.txt
   ```

3. Abre el notebook:
   ```bash
   jupyter notebook Curva\ de\ Titulación.ipynb
   ```

4. Ejecuta las celdas para realizar los cálculos y visualizar las curvas de titulación.

## Resultados Esperados

- Cálculo teórico del pH para diferentes volúmenes de titulante agregado.
- Representación visual de la curva de titulación y puntos clave como el punto de equivalencia.
- Comprensión de las diferencias entre ácidos débiles y fuertes al ser titulados.

## Referencias

- Principios de Química Analítica.
- Notas de curso sobre equilibrio químico.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más información.

