## Implementación de Instalación con Git + Semaphore 

## Cómo usarlo:

1. Modifique el fichero ```yamldatos_generales.yml` que se encuentra en el directorio ```vars`.

### Variables a usar

#### Declarar los repos a usar Ejemplo:

```yaml
repo:
proto: http
host: repos.uclv.edu.cu
root: debian
root-sec: debian-security
flavors: bookworm
source: internet # local if on your network, anything else to use the default ones.
```

#### Variable para los repos

```yaml
# Instalación de paquetes solo se ejecuta si la variable está en True
apt_get_update_cache: True
```
```iniyaml
# Upgrade del sistema solo se ejecuta si la variable está en True
apt_get_upgrade_cache: True
```