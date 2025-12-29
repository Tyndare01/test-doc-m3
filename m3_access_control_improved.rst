.. _access_control_main:

=================
M³ Access Control
=================

.. _access_control:

Access control solutions are provided to **manage and monitor the access of
vehicles into specific urban areas**, either on a permanent basis or during
specific dates, times, or hours of the day.

For instance, priority vehicles (police, ambulances, fire trucks, etc.) are
always allowed to access certain restricted urban areas without being reported
as violation offenders. Taxis or drivers with special permissions
(e.g., handicapped individuals) may be allowed into a traffic-restricted
city center zone, whereas normal cars are restricted. Public transportation
(e.g., buses) could be allowed in a tunnel, while trucks carrying dangerous goods
are disallowed.

Furthermore, it is possible to define exceptions so that certain vehicles can
still enter specific areas even if they do not comply with the restrictions
(whitelist). It may also be possible to schedule certain (recurring) events in
a city center (e.g., market days, festivals) during which special permissions
are required to enter certain areas. Exceptions could also be scheduled for garbage
trucks that enter only on specific days, or trucks that can only enter for
loading and unloading during certain hours of the day.

The access control solution works by comparing configurations of such schedules
and exceptions with ANPR detections. It therefore relies on having a network of
ANPR cameras installed. Note that the data collected from these cameras can be
utilized by many different smart mobility applications of the M³ platform.
Moreover, the configurability of access control allows for versatile use, matching a wide variety of use cases.

The following table summarizes all the possibilities. A link to each chapter is
included, starting with the necessary roles to fully access each part.

.. list-table:: Contents
   :widths: 200 250
   :header-rows: 1

   * - Part
     - Usage
   * - :octicon:`chevron-down;1em;sd-text-info` :ref:`Configuration of Access Control <access_control_configuration>`
     - The admin will configure access controls.
   * - :octicon:`chevron-down;1em;sd-text-info` :ref:`List of All Access Control <list_of_all_access_control>`
     - List of all access control configurations. Via this page, the user can create, edit, or delete configurations.
   * - :octicon:`chevron-down;1em;sd-text-info` :ref:`Create a New Access Control <access_control_management>`
     - Create a new access control.
   * - :octicon:`chevron-down;1em;sd-text-info` :ref:`Edit an Access Control <access_control_management>`
     - Edit an access control.
   * - :octicon:`chevron-down;1em;sd-text-info` :ref:`Access Control Events <access_control_events>`
     - Consult and edit access control events.
   * - :octicon:`chevron-down;1em;sd-text-info` :ref:`Archives Access Control Events <access_control_archives>`
     - Archive access control events.
   * - :octicon:`chevron-down;1em;sd-text-info` :ref:`Export Access Control Events <access_control_export>`
     - Export access control events.
   * - :octicon:`chevron-down;1em;sd-text-info` :ref:`Access Control Errors <access_control_errors>`
     - Access control errors.
   * - :octicon:`chevron-down;1em;sd-text-info` :ref:`Whitelist Management <whitelist_access_control>`
     - Create, edit, and delete whitelists used in access control configurations.


.. dropdown:: Roles for Access Control

   .. include:: /content/m3-roles.rst
      :start-after: .. access_control_roles_start
      :end-before: .. access_control_roles_end
