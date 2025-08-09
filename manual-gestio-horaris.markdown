# Manual de Gestió d'Horaris - El Món en Blau i Morat

Aquest manual explica com gestionar els horaris de cites a través de la pàgina d'administració d'El Món en Blau i Morat.

## Accés a l'Administració

1. **Accedir a la pàgina d'administració**: Obre el fitxer `admin.html` o l'enllaç proporcionat per l'administrador.
2. **Inici de sessió**:
   - Introdueix l'usuari: `admin`.
   - Introdueix la contrasenya: `admin123`.
   - Prem el botó "Accedir" per iniciar sessió.
   - Nota: Aquestes credencials són temporals i haurien de ser actualitzades per a un ús real amb un sistema segur.

## Gestió d'Horaris

### Afegir una Nova Hora
1. Un cop dins de la pàgina d'administració, veuràs un formulari amb un camp de data i un camp d'hora.
2. Selecciona la data desitjada utilitzant el camp "Data Nova".
3. Selecciona l'hora desitjada utilitzant el camp "Hora".
4. Prem el botó "Afegir Hora" per afegir la nova franja horària.
   - La nova hora s'afegirà a la taula d'horaris i es mostrarà ordenada cronològicament.

### Eliminar una Hora
1. A la taula d'horaris, troba la fila que conté la data i l'hora que vols eliminar.
2. Prem el botó "Eliminar" de la fila corresponent.
3. La hora es treurà immediatament de la llista d'horaris disponibles.

### Definir Hores Setmanals Disponibles
1. A la pàgina d'administració, selecciona l'opció "Definir Hores Setmanals".
2. Escull el dia de la setmana (dilluns a diumenge) utilitzant el desplegable.
3. Introdueix les hores disponibles per a aquest dia (per exemple, "10:00-12:00, 14:00-16:00").
4. Prem el botó "Desar Hores Setmanals" per guardar les hores definides.
   - Aquestes hores es repetiran setmanalment i es reflectiran automàticament a la taula d'horaris.

## Tancament de Sessió
- Per tancar la sessió, prem el botó "Tancar Sessió" situat a la part inferior de la pàgina.
- Això et retornarà a la pantalla d'inici de sessió.

## Notes Importants
- **Seguretat**: Les credencials actuals són per a proves. Canvia-les i implementa un sistema d'autenticació segur en producció.
- **Actualització**: Els canvis en els horaris es reflecteixen automàticament a la pàgina principal (`index.html`) si es sincronitzen manualment o amb una connexió backend.
- **Suport**: Si tens dubtes, contacta amb l'equip d'administració a través de la secció de contacte de la pàgina principal.
- **Manual**: Pots accedir al manual complet prement el botó "Llegir Manual" a la pàgina d'administració.