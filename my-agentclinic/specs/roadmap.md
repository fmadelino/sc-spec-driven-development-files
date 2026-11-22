# Roadmap

Build in small, reviewable phases. Each phase should leave the project in a
working state and establish the need for the next one.

1. **Agree on the first release:** Define the minimum clinic workflows and the
   information agents and staff need.
2. **Prepare the server foundation:** Add the TypeScript server and Fastify
   application entry point; verify it starts and responds.
3. **Connect SQLite:** Add database setup and a minimal migration or schema
   workflow; verify the app can persist and retrieve a record.
4. **Model clinic data:** Define agents, ailments, therapies, and appointments;
   create and verify the corresponding database tables.
5. **Show agents:** Implement a basic agent listing and detail view backed by
   persisted data.
6. **Describe ailments:** Implement an ailment listing and detail view, with
   the relevant agent association.
7. **Present therapies:** Implement therapy information and its relationship
   to ailments.
8. **Book appointments:** Add the smallest complete booking flow and show
   appointments to the relevant user.
9. **Add staff access:** Provide staff with a dashboard to review agents,
   available clinic information, and bookings.
10. **Polish the experience:** Improve visual clarity and responsiveness, then
    verify the main workflows in modern browsers.
