# Máquinas Virtuales desde CERO

Guía práctica para comprender, instalar y gestionar máquinas virtuales con VirtualBox desde cero. Ideal para estudiantes, personas autodidactas o quienes buscan introducirse en el mundo de la virtualización.

---

## 1. ¿Qué es una máquina virtual?

Una máquina virtual (VM) es un entorno computacional simulado que permite ejecutar un sistema operativo dentro de otro, como si fuera una computadora independiente.

### 1.1 ¿Para qué sirve una máquina virtual?

- Realizar pruebas de sistemas sin afectar tu equipo.
- Aprender Linux o cualquier otro sistema operativo.
- Practicar ciberseguridad sin riesgos.
- Emular entornos de red.
- Utilizar software incompatible con tu SO principal.

---

## 2. ¿Qué se necesita?

- Un equipo físico con recursos suficientes (mínimo 8 GB de RAM recomendado).
- Software de virtualización (ej. VirtualBox).
- Imagen ISO o máquina virtual preconfigurada.

---

## 3. Hipervisor

El hipervisor es el software que permite crear y ejecutar máquinas virtuales. Hay dos tipos:

- Tipo 1 (bare metal): se ejecuta directamente sobre el hardware.
- Tipo 2 (hosted): se ejecuta sobre un sistema operativo (como VirtualBox).

---

## 4. ¿Qué es una ISO?

Una ISO es una copia exacta de un sistema operativo lista para instalarse. Puedes descargar ISO de sistemas como Ubuntu, Kali Linux o Windows desde sus sitios oficiales.

---

## 5. Ventajas de las máquinas virtuales

### 5.1 Aprendizaje seguro
Puedes experimentar sin comprometer tu equipo.

### 5.2 Aislamiento
Las VMs operan en entornos separados del sistema host.

### 5.3 Simulación laboral
Muchas empresas utilizan máquinas virtuales, lo cual te prepara para un ambiente laboral.

---

## 6. VirtualBox

VirtualBox es un hipervisor tipo 2 gratuito y de código abierto. Permite crear, configurar y gestionar máquinas virtuales desde Windows, macOS o Linux.

---

## 7. Instalar VirtualBox

1. Ve a https://www.virtualbox.org/wiki/Downloads
2. Descarga el instalador según tu sistema operativo.
3. Instálalo siguiendo las instrucciones predeterminadas.

---

## 8. Instalar sistema operativo desde ISO

### 8.1 Descargar la ISO
Descarga la imagen ISO del sistema operativo que desees (por ejemplo, Ubuntu desde https://ubuntu.com/download).

### 8.2 Agregar la ISO a VirtualBox
1. Abre VirtualBox y haz clic en **New**.
2. Asigna nombre, tipo (Linux/Windows), versión (ej. Ubuntu 64-bit).
3. Define la cantidad de RAM (recomendado: al menos 2 GB para Linux).
4. Crea un disco virtual (VDI, tamaño dinámico, 20 GB recomendado).
5. En configuración → Storage → selecciona la ISO descargada como disco óptico.

---

## 9. Importar máquina virtual prediseñada

En lugar de instalar desde ISO, puedes descargar máquinas ya configuradas (por ejemplo, de Kali Linux).

### 9.1 Ir a: https://www.kali.org/get-kali/#kali-virtual-machines  
### 9.2 Descargar la versión para VirtualBox (.ova)
### 9.3 En VirtualBox → Import Appliance → selecciona el archivo .ova

---

## 10. Snapshot

Antes de hacer cambios peligrosos o pruebas:
- Ve a la VM → botón derecho → "Take Snapshot".
- Así puedes restaurar la VM si algo sale mal.

---

## 11. Consejos de uso

- Usa NAT como adaptador de red para seguridad.
- No compartas carpetas entre el host y la VM si haces pruebas inseguras.
- Crea snapshots antes de instalar herramientas de pentesting.

---

## 12. Referencias

1. DigitalOcean. (2014). *Virtualization vs. emulation: What’s the difference?* https://www.digitalocean.com/community/tutorials/virtualization-vs-emulation  
2. Genbeta. (s.f.). *Linux paso a paso: Instalar Ubuntu con dual boot junto a Windows 10*. https://www.genbeta.com/paso-a-paso/linux-paso-a-paso-instalar-ubuntu-con-dual-boot-junto-a-windows-10  
3. Hoffman, C. (2012). *HTG explains: The differences between VirtualBox’s disk image formats*. https://www.howtogeek.com/125640/...  
4. Kali Linux. (s.f.). *Import premade VirtualBox images*. https://www.kali.org/docs/virtualization/import-premade-virtualbox/  
5. Offensive Security. (s.f.). *Kali Linux VirtualBox Guest*. https://www.kali.org/docs/virtualization/kali-linux-virtualbox-guest/  
6. Oracle Corporation. (s.f.). *Chapter 5. Virtual storage*. https://www.virtualbox.org/manual/ch05.html  
7. Oracle Corporation. (s.f.). *Downloads – Oracle VM VirtualBox*. https://www.virtualbox.org/wiki/Downloads  
8. Oracle Corporation. (s.f.). *Importing an appliance*. https://docs.oracle.com/en/virtualization/virtualbox/6.0/user/importappliance.html  
9. Oracle Corporation. (s.f.). *VirtualBox User Manual*. https://www.virtualbox.org/manual/UserManual.html  
10. Red Hat. (s.f.). *What is a hypervisor?* https://www.redhat.com/es/topics/virtualization/what-is-a-hypervisor  
11. Ubuntu Forums. (2011). *Use existing VDI file*. https://ubuntuforums.org/showthread.php?t=1877491  
12. VMware. (s.f.). *Hypervisor – VMware Glossary*. https://www.vmware.com/topics/glossary/content/hypervisor.html  
13. Xataka. (s.f.). *Cómo descargar un archivo ISO de Windows 10*. https://www.xataka.com/basics/como-descargar-un-archivo-iso-de-windows-10

---

## Autor

**Juan José Castillo Salinas**  
Cybersecurity Analyst | SOC Trainee  
[LinkedIn](https://www.linkedin.com/in/juan-jose-castillo-salinas-91b992257) · [GitHub](https://github.com/juancyber01)

---

📄 [Descargar guía en PDF](Maquinas%20virtuales%20desde%20CERO.pdf)
