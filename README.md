
# Auditar proyectos de ISPP-2526 con Bluejay.

## 1. Crear y configurar el repositorio.

**1.1. En la rama main añadir el siguiente archivo `info.yml`.**

info.yml:
```yaml
project:
  name: 'ISPP-2526-nombreDeProyecto'
  owner: 'ISPP'
  teamId: 'ISPP'
  identities: {}
  notifications:
    email: 'member1@gmail.com,member2@gmail.com,member3@gmail.com,member4@gmail.com'
  members:
    member1:
      name: 'Member'
      surname: 'User' 
      githubUsername: 'member1'
    member2:
      name: 'Member'
      surname: 'User'
      githubUsername: 'member2'
    member3:
      name: 'Member'
      surname: 'User'
      githubUsername: 'member3'
    member4:
      name: 'Member'
      surname: 'User'
      githubUsername: 'member4'
```

- Rellenar el nombreDeProyecto del name.
    > Por ejemplo:
    >```yaml
    >name: 'ISPP-2526-ITTalent'
    >```

- Sustituir los datos de cada memberN por los del miembro real, incluyendo su nombre, apellido y usuario de github que utiliza en el repositorio.
- Añadir tantos miembros como hagan falta siguiendo el formato member5, member6, ... memberN.
- Modificar la cadena de `notifications.email` para que contengan sólo los correos de todos los miembros separados por comas y sin espacios.

Cuando conste la información de todos los miembros en el archivo info.yml entonces hacer el paso 3.

## 3. Unir el proyecto a la asignatura auditada por Bluejay

- Accede a [join.bluejay.pre.governify.io](https://join.bluejay.governify.io).
- Añade la **URL del repositorio** de GitHub.
- Click en **CHECK**. Si ha dado error revisa la [sintaxis](https://www.yamllint.com/) del info.yml.
- **Selecciona la clase** a la que te quieres unir (US-ISPP-2526) y especifica el código que te dará tu profesor.
- Click en **JOIN**.
- En caso de que haya algún otro problema al configurar Bluejay, el equipo de soporte está disponible en [un canal de Gitter dedicado](https://app.gitter.im/#/room/!VTAnLfNgxrEdydQgWd:gitter.im).


