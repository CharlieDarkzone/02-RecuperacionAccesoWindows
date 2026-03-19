# 🧪 Lab02 – Recuperación de acceso a sistema Windows

Laboratorio práctico orientado a la **recuperación de acceso a sistemas Windows** en un entorno controlado, simulando la pérdida de credenciales de administrador.

Este laboratorio permite comprender los riesgos asociados al acceso físico a un equipo y las medidas necesarias para mitigar estos escenarios.

---

## 🎯 Objetivo

* Simular la pérdida de acceso a una cuenta administrador
* Evaluar herramientas de recuperación de sistemas
* Analizar riesgos de seguridad asociados
* Identificar medidas de mitigación en entornos reales

---

## 🧱 Escenario

Se dispone de una máquina virtual con:

* Sistema Operativo: Windows 10 Pro
* Usuario: Administrador local
* Situación: Contraseña desconocida / acceso perdido

El objetivo es recuperar el acceso al sistema dentro de un entorno controlado.

---

## 🛠️ Herramientas utilizadas

* Hiren’s BootCD
* Entorno virtual (QEMU/KVM)

---

## ⚙️ Actividades realizadas

* Preparación de máquina virtual con Windows
* Simulación de pérdida de contraseña
* Uso de herramienta de recuperación
* Acceso nuevamente al sistema
* Validación de control total del equipo

---

## 📸 Evidencias

* Inicio del sistema bloqueado
* Herramienta de recuperación en ejecución
* Acceso restaurado al sistema
* Validación de privilegios administrativos

---

## 🧠 Análisis de seguridad

Este laboratorio demuestra que:

* El acceso físico a un equipo representa un riesgo crítico
* Es posible recuperar acceso a sistemas sin conocer la contraseña
* Las credenciales por sí solas no garantizan la seguridad del sistema

---

## 🔐 Medidas de mitigación

Para proteger sistemas frente a este tipo de escenarios:

* Habilitar cifrado de disco (BitLocker)
* Configurar contraseña en BIOS/UEFI
* Activar Secure Boot
* Restringir acceso físico a los equipos
* Aplicar políticas de seguridad en endpoints

---

## ⚠️ Consideraciones

Este laboratorio fue realizado en un entorno controlado con fines educativos.

Las técnicas analizadas deben utilizarse únicamente en sistemas propios o con autorización.

---

## 🚀 Estado del laboratorio

🟢 Finalizado / En pruebas

---

## 👤 Autor

Proyecto personal orientado al aprendizaje de:

* Administración de sistemas
* Seguridad en endpoints
* Análisis de riesgos
* Buenas prácticas en ciberseguridad
