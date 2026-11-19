# Círculo de Mohr · Inercias de secciones

Aplicación docente interactiva, por **Francisco Goitia** (francisco.goitia@upc.edu).

Permite modificar la geometría de secciones rectangulares y doble T, girar los ejes o la figura y observar su efecto sobre los momentos y producto de inercia y el círculo de Mohr.

## Uso

Abre `index.html` con Chrome o Edge. No necesita instalación ni dependencias externas. Los botones **Rectangular** y **Doble T** están inmediatamente encima del panel de dibujo; la orientación se regula sobre el mismo panel. Las dimensiones se encuentran debajo, y el círculo de Mohr permanece a la derecha en escritorio.

## Publicación en GitHub Pages

En **Settings → Pages** selecciona **Deploy from a branch**, rama **main** y carpeta **/(root)**. La URL esperada será https://fragoi95.github.io/circulo_mohr_inercias/. La publicación puede tardar un poco después de activar Pages.

Convención de productos de inercia: `Ixy = ∫ xy dA`, positivo hacia arriba en el círculo. Se utilizan secciones doblemente simétricas, homogéneas, sin redondeos en el perfil doble T.

## Lecturas incorporadas en v4

Los puntos del círculo muestran sus coordenadas en las unidades seleccionadas:

- **X (azul):** \(I_{x'}, I_{x'y'}\).
- **Y (rojo):** \(I_{y'}, -I_{x'y'}\).
- **Inercias principales:** recuadro lateral con \(I_{máx}\) e \(I_{mín}\), invariantes bajo el giro de ejes o de la sección.

Las lecturas se actualizan al modificar las dimensiones, los ángulos o las unidades.
