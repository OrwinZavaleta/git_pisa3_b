# 4. Modelo de producción y consumo actual

## Introducción

En el mundo moderno, el **modelo de producción y consumo** juega un papel crucial en la forma en que las sociedades satisfacen sus necesidades y gestionan los recursos. Sin embargo, el sistema predominante, basado en un enfoque lineal de *“extraer, producir, usar y tirar”*, está mostrando serias limitaciones frente a los desafíos **ambientales, sociales y económicos** del siglo XXI.

---

## Evolución del modelo de producción

Este modelo, desarrollado principalmente durante la **Revolución Industrial** y afianzado en el siglo XX, ha permitido un crecimiento económico sin precedentes. Algunas de sus características clave son:

- **Producción masiva** impulsada por la industrialización.
- **Explotación intensiva de recursos naturales** sin considerar la regeneración.
- **Enfoque en la maximización del consumo**, promovido por la publicidad y el mercado.
- **Generación masiva de residuos**, debido a la obsolescencia programada y la cultura del descarte.

> "La economía lineal ha impulsado el crecimiento, pero también ha generado desequilibrios ecológicos y sociales." – Informe del Foro Económico Mundial

---

## Problemas del modelo lineal

El éxito de este sistema ha traído consigo una serie de **consecuencias negativas**, tales como:

1. 🌎 **Agotamiento de recursos**: La extracción descontrolada está llevando al límite la disponibilidad de materiales esenciales.
2. 🏭 **Contaminación ambiental**: Procesos industriales y residuos generan impacto en el aire, agua y suelos.
3. 🔄 **Sobreproducción y desperdicio**: Muchas industrias producen más de lo necesario, aumentando la cantidad de productos descartados.
4. 🚮 **Economía desechable**: Se incentiva el consumo de productos de un solo uso, elevando la cantidad de desechos.

Un claro ejemplo del problema es la **contaminación por plásticos**. De acuerdo con estudios recientes, cada año se vierten más de `8 millones de toneladas` de plástico en los océanos.

---

## Hacia un modelo más sostenible

Frente a estas problemáticas, han surgido alternativas como la **economía circular**, que propone un modelo basado en los siguientes principios:

✅ **Reducir** el consumo de recursos.  
♻️ **Reutilizar** productos en lugar de desecharlos.  
🔄 **Reciclar** materiales para darles una nueva vida.  

El siguiente fragmento de código muestra cómo un concepto de reutilización puede aplicarse incluso en sistemas digitales:

```java
class Recurso {
    String nombre;
    boolean utilizable;

    Recurso(String nombre, boolean utilizable) {
        this.nombre = nombre;
        this.utilizable = utilizable;
    }

    void reutilizar() {
        System.out.println(utilizable ? "Usando: " + nombre : "Reciclaje de: " + nombre);
    }

    public static void main(String[] args) {
        new Recurso("Plástico", true).reutilizar(); // Usando: Plástico
        new Recurso("Cartón", false).reutilizar();  // Reciclaje de: Cartón
    }
}
