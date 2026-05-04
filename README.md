# pt-human-errors-cybersecurity
# Simulación y análisis de Amenazas Persistentes Avanzadas (APT)

## Descripción del proyecto
Proyecto enfocado en el análisis de Amenazas Persistentes Avanzadas (APTs), combinando investigación teórica y simulación práctica en un entorno virtualizado de laboratorio.

Se estudiaron campañas reales de APT29 (Cozy Bear) y Lazarus Group (APT38), analizando sus tácticas, técnicas y procedimientos (TTPs), así como indicadores de compromiso (IoCs) y malware asociado como SUNBURST y TEARDROP.

---

## Entorno de laboratorio
El laboratorio fue desplegado con máquinas virtuales:

- Kali Linux (Atacante) con Metasploit  
- Kali Linux (Objetivo) con Wazuh Agent  
- Ubuntu Server con Wazuh Manager (SIEM)

---

## Simulación realizada
- Ejecución de ataque de fuerza bruta controlado  
- Monitorización de eventos en Wazuh SIEM  
- Detección de actividad sospechosa mediante logs  
- Correlación de eventos y análisis de alertas  
- Mapeo de actividades con MITRE ATT&CK
## Evidencias de laboratorio
- Monitorización en Wazuh SIEM
<img width="800" height="116" alt="bruteforce jpg" src="https://github.com/user-attachments/assets/625e5a66-19c2-4466-a155-9ee857bff513" />
<img width="1165" height="443" alt="wazuh-dashboard jpg" src="https://github.com/user-attachments/assets/0b8e3fb2-ef02-47d7-a99e-3b9710041fd7" />
<img width="800" height="260" alt="wazuh-agent-dashboard jpg" src="https://github.com/user-attachments/assets/fd615d0a-0324-4efd-91dc-ea0eb5e189df" />
<img width="516" height="173" alt="wazuh-linux jpg" src="https://github.com/user-attachments/assets/92883186-de1a-488d-9748-3750b086d765" />



---

## Casos analizados
- **SolarWinds (APT29):** ataque de cadena de suministro y persistencia avanzada  
- **Lazarus Group (APT38):** campañas financieras y caso WannaCry / Sony Pictures  

---

## Resultados
- Mejora en detección de ataques basados en logs  
- Experiencia en threat hunting y análisis de eventos  
- Uso de IoCs para detección temprana  
- Comprensión del impacto del factor humano en ataques APT  

---

## Tecnologías utilizadas
Wazuh SIEM, MITRE ATT&CK, Kali Linux, Metasploit, Linux, VMware, análisis de logs, threat intelligence (CTI), seguridad de redes, respuesta a incidentes
