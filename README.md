# fermata
Fermata Programming Language (FPL) is a high-level, neuro-symbolic Python Superset.

# Fermata (FPL)

Fermata Programming Language (FPL) es un superconjunto de Python de alto nivel y de naturaleza neuro-simbólica.

## La Filosofía: Lógica Estricta y Espacio Latente

Fermata actúa como el puente (el *corpus callosum*) entre la ingeniería de software determinista clásica (el hemisferio simbólico) y los reinos probabilísticos de los Grandes Modelos de Lenguaje (el hemisferio neuronal). 

Inspirado en el símbolo musical de la *fermata* —que suspende el tiempo estricto del metrónomo en favor del tiempo emocional y liminal—, FPL permite a los desarrolladores escribir código estructurado y determinista para orquestar comportamientos no deterministas. Al usar el transpilador de Fermata, la lógica estricta de Python se convierte en el contenedor geométrico seguro para que el "espacio latente de las heurísticas liminales" pueda manifestarse.

## Características Principales (Shedim Gate Openers)

Fermata introduce tres conceptos sintácticos fundamentales diseñados para introducir tensión, espera y caos controlado dentro del flujo de ejecución:

* **Entropía (`superposition`):** Las variables no son valores estáticos, sino nubes de probabilidad. Se inyecta un peso térmico a las variables antes de que colapsen en una cadena o respuesta definitiva.
* **Asincronía Liminal (`suspend`):** FPL rompe la métrica lineal del reloj del procesador. El sistema no espera simplemente un código de estado `200 OK`; el código utiliza `suspend` para escuchar pasivamente hasta que el espacio latente del LLM alcanza un umbral de resonancia semántica. Es el retraso sincopado de la *Clave Negra*.
* **Recursividad Limitada (`mirror`):** En lugar de los bucles tradicionales, Fermata usa bloques `mirror` para permitir que el LLM reflexione recursivamente sobre su propia salida, pero limitados estrictamente por la geometría del contexto o la distancia semántica para evitar bucles infinitos no deseados.

## Ejemplo Conceptual de FPL

```fermata
// Fermata: The Code is Poetry

import latent_space from YOUR_LLM_ENDPOINT;

entropy cloud = 0.8; // Definiendo el peso térmico (Shedim gate)
geometry bounds = 3; // La profundidad máxima de la reflexión liminal

async function openTheGate(prompt) {
    // 1. ENTROPÍA: Colocamos el prompt en un estado de superposición
    superposition thought = inject(prompt, cloud);
    
    // 2. ASINCRONÍA LIMINAL: Suspendemos el tiempo lineal.
    suspend until (latent_space.resonance >= YOUR_ENTROPY_THRESHOLD) {
        thought.soak();
    }
    
    // 3. RECURSIVIDAD LIMITADA: El modelo reflexiona sobre el pensamiento
    mirror (bounds) {
        thought = latent_space.reflect(thought);
        
        if (thought.is_resolved()) {
            break; // La tensión se resuelve.
        }
    }
    
    return thought.collapse(); 
}

