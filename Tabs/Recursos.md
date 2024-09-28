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
>Nota: La librería de la navX suele estar desactualizada y es difícil de encontrar un link actualizado 

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
>Nota: AdvantageKit cambia en su mayoría toda la estructura del código **NO ES RECOMENDABLE INSTALARLO (PARA PRINCIPIANTES)** , debido a que su instalación es más compleja es mejor descargar una plantilla con AdvantageKit instalado

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
- [PLUGINS ERROR](https://docs.wpilib.org/en/stable/docs/yearly-overview/known-issues.html)
- [ODOMETRÍA RESUMEN](https://docs.google.com/document/d/16U1POgTQF0mef69y7STbDaX4ksgq5o8mM7ESzRu8YzU/edit?usp=sharing)
- [COMMAND BASED PROGRAMMING](https://docs.wpilib.org/en/latest/docs/software/commandbased/index.html)
- [ENCODERS](https://docs.wpilib.org/en/stable/docs/software/hardware-apis/sensors/encoders-software.html)
- [APRILTAGS](https://docs.wpilib.org/es/stable/docs/software/vision-processing/apriltag/apriltag-intro.html)
- [PHOENIX 6 DOCUMENTATION](https://v6.docs.ctr-electronics.com/en/stable/index.html)


## SOFTWARES A INSTALAR

Softwares que usamos durante toda la competencia.

### [1.PATHPLANNER](https://apps.microsoft.com/detail/9nqbkb5dw909?cid=storebadge&ocid=badge&rtc=1&activetab=pivot%3Aoverviewtab&hl=en-us&gl=US)

![](/Images/PTH.png)

PathPlanner is a motion profile generator for FRC robots created by team 3015. Every path allows for manual tuning of the robot position and the curve radius at every point. It allows you to create the perfect path for your robot quicker and easier than other generators. PathPlanner can handle more complex paths than other generators because it will slow down the robot as it heads into a turn instead of going through it as fast as possible. If the robot is still not slowing down enough or you would like the robot to go slow at a certain point in the path, the robot's max velocity can be overridden at each point. Paths are generated in robot code with and easy to use vendor library, PathPlannerLib.

### [2. CHOREO](https://github.com/SleipnirGroup/Choreo/releases)

![](/Images/CHOR.png)

Choreo (Constraint-Honoring Omnidirectional Route Editor and Optimizer, pronounced like choreography) is a graphical tool for planning time-optimized trajectories for autonomous mobile robots in the FIRST Robotics Competition.

### [3. FRC GAME TOOLS](https://www.ni.com/es/support/downloads/drivers/download.frc-game-tools.html#500107)

![](/Images/GTO.png)

FRC Game Tools proporciona componentes que ayudan a los participantes de Competencia de Robótica FIRST (FRC) a administrar y comunicarse con robots.

>[!IMPORTANT]
>Nota: Instale los entornos de programación como NI LabVIEW o Microsoft Visual Studio® antes de instalar este producto.

### [4. Advantage Scope](https://github.com/Mechanical-Advantage/AdvantageScope/releases/tag/v3.2.1)

![](/Images/ADVC.png)

AdvantageScope is a robot diagnostics, log review/analysis, and data visualization application for FIRST Robotics Competition teams. It reads logs in WPILOG, DS log, Hoot (CTRE), and RLOG file formats, plus live robot data viewing using NT4 or RLOG streaming. AdvantageScope can be used with any WPILib project, but is also optimized for use with our AdvantageKit log replay framework. Note that AdvantageKit is not required to use AdvantageScope.

### [5. FRC RADIO CONFIGURATION UTILITY](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-3/radio-programming.html)

![](/Images/RADIO.png)

FRC® Radio Configuration Utility software to configure your robot’s wireless bridge for use outside of FRC events.

### [6. REV HARDWARE CLIENT](https://docs.revrobotics.com/rev-hardware-client)

![](/Images/CLIENT.png)

The REV Hardware Client is software designed to make managing REV devices easier for the user. This Client automatically detects connected device(s), downloads the latest software for those device(s), and allows for seamless updating of the device(s) 

### [7. PHOENIX TUNER X](https://apps.microsoft.com/detail/9nvv4pwdw27z?hl=es-es&gl=MX)

![](/Images/TUNER.png)

Phoenix Tuner X is the companion application allowing you to update, configure, analyze, and control your devices.



*Espero que todo esto haya sido de ayuda :)*

![](/Images/REC.png)
