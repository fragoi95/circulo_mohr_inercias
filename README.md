# Círculo de Mohr · Inercias de secciones

Aplicación docente interactiva, por **Francisco Goitia** (francisco.goitia@upc.edu).

Permite modificar la geometría de secciones rectangulares y doble T, girar los ejes o la figura y observar su efecto sobre los momentos y producto de inercia y el círculo de Mohr.

## Uso

Abre `index.html` con Chrome o Edge. No necesita instalación ni dependencias externas. Los botones **Rectangular** y **Doble T** están inmediatamente encima del panel de dibujo; la orientación se regula sobre el mismo panel. Las dimensiones se encuentran debajo, y el círculo de Mohr permanece a la derecha en escritorio.

## Publicación en GitHub Pages

En **Settings → Pages** selecciona **Deploy from a branch**, rama **main** y carpeta **/(root)**. La URL esperada será https://fragoi95.github.io/circulo_mohr_inercias/. La publicación puede tardar un poco después de activar Pages.

Convención de productos de inercia: `Ixy = ∫ xy dA`, positivo hacia arriba en el círculo. Se utilizan secciones doblemente simétricas, homogéneas, sin redondeos en el perfil doble T.
