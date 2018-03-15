# Webapp sitemap

* Publicly accessible
  * Login (Only allows admin login)
* Admin accessible (All pages here will redirect to login if user is not logged in)
  * Front page
  * Register new... (Dropdown)
    * Appointment (registration form)
    * Mechanic (registration form)
  * Appointments
    * Schedule (has links to single appointments, as well as mechanics)
    * Search (search by mechanic name, car license number, date, and so on)
      * Search results (is formatted like the schedule, by date)
  * Appointment (is only reachable from schedule or search)
    * Delete appointment
    * Edit appointment
  * Mechanic (is reachable from schedule or search)
