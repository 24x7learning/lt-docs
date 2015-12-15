.. _sync application hrms:

**Synchronizing Application with HRMS**
**************************************
•	Synchronization of **HRMS (Human Resource Management System)** with the LMS application is done by accessing **FTP (File Transfer Protocol)** and locating the .csv file from the local client directory and uploading the file to LMS application.
•	The **Mapping of HRMS**  is necessary to synchronize the columns of HRMS with the columns of LMS.
• Synchronization of HRMS with LMS system is normally done by end of the day.

    .. image:: _static/edit_tenant.png
       :height: 150px
       :width: 500 px
       :scale: 120 %
       :align: center

.. note:: | o	**Only Create New Users** when checked, will create all new users automatically in HRMS.
  | o	**Create Business Unit if Not Exists** when checked, and if business units do not  exist in the application, then while uploading .csv file new BU will be automatically created along with its users.
  | o	**Create Location if Not Exists** when checked, and if location name does not exist in the application, then while uploading .csv file new location is created automatically.
  | o	If .csv file has the **Country** field, then locations are created under this field (or) else the country's location is set to **‘India’** by default.
