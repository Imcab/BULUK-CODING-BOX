# Recursos

![](/Images/Pathpl.png)

## Librerías
Durante la competencia, tendemos a usar unas cuantas librerías las cuales instalaremos en VS CODE ***CADA QUE INICIEMOS UN NUEVO PROJECTO, LAS LIBRERIAS DEBERÁN DE SER INSTALADAS***

### Instalar Librerias

Una explicación más gráfica se encuentra en la presentación de [Estructura de un Robot.](https://www.canva.com/design/DAGOiRPhLsQ/O6h79IyM5yVCcMSFUxmIYw/view?utm_content=DAGOiRPhLsQ&utm_campaign=designshare&utm_medium=link&utm_source=editor)

*Para instalar librerías, seguiremos los siguientes pasos:*

1. Abrir la extensión de wpilib **(TIENE QUE ESTAR EL VSCODE ABIERTO)**

![](/Images/Ext.png)

2. Buscar en la barra de comandos: `Manage vendor libraries`
3. Elegir la opción: `Install new libraries (Online)`
4. **PEGAR LA URL EN LA BARRA Y DARLE ENTER**

### Librerías que usa 3472

>[!IMPORTANT]
>*Nota: Las librerías a instalar están en 2024, se actualizarán en 2025 *

#### REVLib

![](/Images/REV.png)

Librería para manipular todo el hardware de *REV Robotics*, en gran parte sus motores.

URL:

    - `https://software-metadata.revrobotics.com/REVLib-2024.json`

### Phoenix6

![](/Images/CTR.png)

Librería para manipular el hardware de *CTR Electronics*, se instala para programar los talons FX (tipo de motor)

URL:

    - `https://maven.ctr-electronics.com/release/com/ctre/phoenix6/latest/Phoenix6-frc2024-latest.json`

### NavX

![](/Images/NAVX2.png)

La *navX* es un gyroscopio que se integra al robot para saber su orientación conforme a la cancha

>[!IMPORTANT]
>*Nota: La librería de la navX suele estar desactualizada y es difícil de encontrar un link actualizado *

URL:

    - `https://dev.studica.com/releases/2024/NavX.json`

### PathPlannerLib

![](/Images/PTH.png)

*PathPlanner* es una herramienta para generar trayectorias para el autónomo, la librería nos permite cargar esas trayectorias y usarlas para el autónomo

URL:

    - `https://3015rangerrobotics.github.io/pathplannerlib/PathplannerLib.json`

### ChoreoLib

![](/Images/CHOR.png)

*Choreo* es un optimizador de trayectorias automático para calcular la mejor ruta, compatible con *Pathplanner.*

URL:

    - `https://SleipnirGroup.github.io/ChoreoLib/dep/ChoreoLib.json`

### PhotonLib

![](/Images/PHOT.png)

Librería para interactuar y agarrar información de las pipelines de *photonvision.*

URL:

    - `https://maven.photonvision.org/repository/internal/org/photonvision/photonlib-json/1.0/photonlib-json-1.0.json`

### AdvantageKit

![](/Images/ADV.png)

*AdvantageKit* es un logger que funciona mediante interfaces para rápido debuggeo, simulación, y cambios en tiempo real.

>[!IMPORTANT]
>*Nota: AdvantageKit cambia en su mayoría toda la estructura del código **NO ES RECOMENDABLE INSTALARLO (PARA PRINCIPIANTES)** , debido a que su instalación es más compleja es mejor descargar una plantilla con AdvantageKit instalado*

URL:

    - `https://github.com/Mechanical-Advantage/AdvantageKit/releases/latest/download/AdvantageKit.json`

## Documentaciones
Docs donde guardamos un poco de todo se puede encontrar [AQUÍ](https://docs.google.com/document/d/1FQqJdlqdG4yySafQjJochPPrOaDmexw4Ws00bfmPxpU/edit)

*Recopilación de los enlaces más importantes:*

    - [DOCUMENTACIÓN WPILIB](https://docs.wpilib.org/en/stable/index.html)
    - [DOCUMENTACIÓN DE LA RADIO](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-3/radio-programming.html)
    - [DOCUMENTACIÓN PHOTONVISION](https://docs.photonvision.org/en/latest/)
    - [GITHUB LIMELIGHT](https://github.com/LimelightVision/limelightlib-wpijava?tab=readme-ov-file)
    - [DOCUMENTACIÓN CHOREO](https://sleipnirgroup.github.io/Choreo/)
    - [PATHPLANNER DOCS](https://pathplanner.dev/home.html)
    - [ADVANTAGE SCOPE DOCS](https://docs.advantagescope.org/)
    - [ADVANTAGE KIT GITHUB](https://github.com/Mechanical-Advantage/AdvantageKit/tree/main)
    - [PLUGINS ERROR](Known Issues — FIRST Robotics Competition documentation (wpilib.org))
    - [ODOMETRÍA RESUMEN](https://docs.google.com/document/d/16U1POgTQF0mef69y7STbDaX4ksgq5o8mM7ESzRu8YzU/edit?usp=sharing)
    - [COMMAND BASED PROGRAMMING](https://docs.wpilib.org/en/latest/docs/software/commandbased/index.html)
    - [ENCODERS](https://docs.wpilib.org/en/stable/docs/software/hardware-apis/sensors/encoders-software.html)
    - [APRILTAGS](https://docs.wpilib.org/es/stable/docs/software/vision-processing/apriltag/apriltag-intro.html)

# SOFTWARES A INSTALAR

![](/Images/REC.png)