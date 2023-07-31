# tietokannat_sql

# Auto Repair Service - Database Setup

This project is a database for Auto Repair Service.

The database consists of several tables to store information about the cars, their owners, employees, maintenance plans, and parts used in the repairs.

## Database Structure

Here's a brief explanation of the tables:

- **Huolto**: This table stores all the maintenance and repair events.
- **Auto**: This table stores all the cars that come for service.
- **Omistaja**: This table stores all the owners of the cars.
- **Omistaa**: This table creates a relationship between owners and their cars.
- **Työntekijä**: This table stores all the employees.
- **Lasku**: This table stores all the bills for the services.
- **Maksu**: This table stores all the payments made.
- **Maksumuistutus**: This table stores all payment reminders.
- **Asiakas**: This table stores all the customers' information.
- **Varaosa**: This table stores all the spare parts.
- **Tarvitaan**: This table shows which parts are needed for which repair/maintenance.
- **Huoltosuunnitelma**: This table stores the maintenance plans.
- **Toimenpide**: This table stores all the actions/tasks in a maintenance plan.
- **Kuuluu**: This table shows which actions belong to which maintenance plan.
- **Laitetyyppi**: This table stores all the types of devices used in the garage.
- **Käytetään**: This table shows which devices are used for which tasks.
- **Yksittäinen_laite**: This table stores individual devices in the garage.
- **Laitevaraus**: This table shows which devices are booked for which repairs.
- **Poissaolot**: This table shows the off-duty records of the employees.
