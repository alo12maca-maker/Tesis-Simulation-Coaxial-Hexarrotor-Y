# Tesis Simulation - Coaxial Hexarrotor Y

Simulación en Gazebo para tesis de ingeniería.

## 📁 Estructura del proyecto
Tesis-Simulation-Coaxial-Hexarrotor-Y/
├── worlds/ # Mundos de Gazebo (.sdf)
├── models/ # Modelos 3D (próximamente)
├── src/ # Código ROS2 (próximamente)
├── scripts/ # Scripts útiles (próximamente)
└── docs/ # Documentación



## 🚀 Mundos disponibles

### mundo_parque_eolico.sdf / mundo_final.sdf
Parque eólico con 5 aerogeneradores 

## 🔧 Requisitos

- Ubuntu 22.04
- Gazebo Sim 8 (Garden)

## 🎮 Cómo ejecutar

```bash
# Clonar el repositorio
git clone https://github.com/alo12maca-maker/Tesis-Simulation-Coaxial-Hexarrotor-Y.git
cd Tesis-Simulation-Coaxial-Hexarrotor-Y

# Configurar la ruta de modelos de Gazebo
export GZ_SIM_RESOURCE_PATH=$GZ_SIM_RESOURCE_PATH:/home/alondra/.gz/gazebo/models

# Ejecutar el mundo
gz sim worlds/mundo_parque_eolico.sdf -v 3
