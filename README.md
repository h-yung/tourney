# tourney
Web app to support tournament events management. Main user initially event organizers, secondary user: participant, tertiary user: referee.

**Tech TBD**: 
- PostGreSQL or MySQL?
- React & TypeScript, likely Vite template to start
- Node.js

**Hosting**: TBD

## Functions/target versions
### Baseline V1:
- Look up individuals information
- Database and schemas are defined for the following information:
  - Person: judge/referee, participant, staff, volunteer
    - Availability/attendance
    - Criteria relevant for logic (experience, location, history, override, last updated/timestamp)
  - Org (participating): calendar (where relevant)
- Authentication to prep role-based app views
  - read-only: all (staff, volunteer, etc)
  - read-only: public areas (participant, judge/referee)
  - read/write: staff ("staff")
- Responsive design

### V2:

- Add definition to app user roles, including read-only rolethank
  - differentiate judge/referee and participant views
- POST/ability to update database (add, delete, update)
  - Person tables
- Guidance in UI for management

### V3:
- Apply tournament seeding logic from UI
- "Live" or polled display of tournament activity
  - which match(es) ongoing per court
- POST/ability to update tournament progress
  - determine logic
  - should it allow users to alter or hardcode to an extent?
  - options examples - round robin with tiebreaking logic, elimination
  - type of points/score information (order scored, type of point, penalties converted)
 





 
  


