Descripció

Aquest projecte és un playbook principal d’Ansible pensat per automatitzar el procés d’alta d’un nou hosting per a clients.

L’automatització permet:

Recollir les dades del client.
Assignar automàticament la quota segons el paquet contractat.
Generar una contrasenya segura aleatòria.
Crear l’usuari i configurar la quota.
Configurar la base de dades MySQL.
Crear la configuració DNS i web.
Enviar un correu de benvinguda al client.

Tot el procés es realitza de manera centralitzada des d’un únic playbook principal.
