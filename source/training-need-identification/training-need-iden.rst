.. _tni:
.. |Admin| image:: _static/admin_button.png
.. |Delete-Button| image:: _static/usr_del_tab.png
.. |Edit-Button| image:: _static/usr_edit_tab.png
.. |User-Details| image:: _static/usr_det_tab.png
.. |Re-map-Button| image:: _static/map_again_button.png

**Training Need Identification**
*******************************
* The *Training Need Identification (TNI)* is the process of providing special trainings to the users', in-order to upgrade their skills or competencies to perform complex roles in an efficient manner.
* TNI is important to determine the types of training needed for the users' to complete the tasks effectively and to increase the productivity of the users' and the organization.
* In LMS, the training need identification (TNI) is created by mapping the **TNI Source** and **TNI Period** to the selected users'.
* The mapped **TNI Name** is displayed in the user dashboard.
* The user can then self-enroll by adding the TNI name to either :ref:`classroom trainings <classroom training>` or :ref:`e-learning resources <elearning>`.

**Steps for creating TNI:**

    * **Step 1:** Create new **TNI Source**.
    * **Step 2:** Create new **TNI Period**.
    * **Step 3:** Goto **Import** tab, and map the TNI source and period to the respective user.
    * **Step 4:** The user must self-enroll by adding the **TNI Name** to either the classroom training/ external trainings/ e-learning resources.

**TNI Source**
^^^^^^^^^^^^^^^
*To access TNI Source:*

  Click |Admin| **Admin > TNI > TNI Source**. The following **Manage TNI Sources** screen appears.

  .. image:: _static/mng_tni.png
   :height: 500px
   :width: 500 px
   :scale: 120 %
   :align: center

**Create new TNI Source**
======================
*To create TNI Source:*

    Click **Create New**. The following **Create TNI Source** screen appears.

    .. image:: _static/crt_tni_source.png
     :height: 250px
     :width: 500 px
     :scale: 120 %
     :align: center

**Edit, Delete and View Details of TNI Source**
==============================================
*To edit TNI source:*

    Click |Edit-Button| **Edit**. The **Edit TNI Source** screen appears with the choosen field to be edited.

*To delete TNI source:*

    Click |Delete-Button| **Delete**. It deletes the selected TNI period.

*To view TNI details:*

    Click |User-Details| **Details**. The **Details** screen appears displaying details of the created TNI source. The administrator can also edit details, by clicking *Edit* which is redirected to the *Edit TNI Source* screen.

**TNI Period**
^^^^^^^^^^^^^^
*To access TNI Period:*

    Click |Admin| **Admin > TNI > Period**. The following **Manage TNI Period** screen appears.

    .. image:: _static/mng_tni_period.png
     :height: 500px
     :width: 500 px
     :scale: 120 %
     :align: center

**Create new TNI Period**
=========================
*To create TNI Period:*

    Click **Create New**. The following **Create TNI Period** screen appears.

    .. image:: _static/crt_tni_period.png
     :height: 250px
     :width: 500 px
     :scale: 120 %
     :align: center

.. note:: The **Is Current** option must be checked after selecting the *start and end month*.

**Edit, Delete and View Details of TNI Period**
==============================================
*To edit TNI Period:*

    Click |Edit-Button| **Edit**. The **Edit TNI Period** screen appears with the choosen field to be edited.

*To delete TNI source:*

    Click |Delete-Button| **Delete**. It deletes the selected TNI period.

*To view TNI details:*

    Click |User-Details| **Details**. The **Details** screen appears displaying details of the created TNI period. The administrator can also edit details, by clicking *Edit* which is redirected to the *Edit TNI Period* screen.

**Mapping TNI to the Users**
^^^^^^^^^^^^^^^^^^^^^^^^^^^
* The training need identification (TNI) can be accssed by mapping the TNI source and period to the selected users'.
* The mapped TNI appears at user dashboard.
* The user must then click the TNI name, to add it to either classroom trainings/ external trainings/ e-learning resources.
*The TNI mapping is done as follows:*

  * Click |Admin| **Admin > TNI > Import**. The following **Import TNI Scource** screen appears to upload the TNI source via .csv file.

        .. image:: _static/imp_tni.png
           :height: 250px
           :width: 500 px
           :scale: 120 %
           :align: center

  * Click **Import** to upload the .csv file.

  .. note:: The .csv file size should be less than or equal to 4MB. Refer :ref:`Bulk Uploading Process <bulk users upload>` under **Import Bulk Users**.
  * **On user account:**

              | * Click the **TNI Name**. The following **TNI Map** screen appears to map either e-learning resources/ classroom trainings/ external trainings.

                .. image:: _static/tni_map.png
                   :height: 250px
                   :width: 500 px
                   :scale: 120 %
                   :align: center
              | * Select the e-learning resources/ classroom trainings/ external trainings from the dropdown list.
              | * Click **Map**.
              | * The mapped e-learning resources/ classroom trainings/ external trainings will be listed as shown below.

                  .. image:: _static/tni_already_mapped.png
                     :height: 250px
                     :width: 500 px
                     :scale: 120 %
                     :align: center
              | * Click **Complete Mapping**.
              | * The user can re-map classroom trainings/ external trainings/ e-learning resources by clicking |Re-map-Button|.

**TNI Report**
^^^^^^^^^^^^^
* The TNI report generates detailed report on the *training need identification* published either to a **individual user** or **group users**.
* The TNI report is filtered based on **TNI Period, Department** and **User**.
* The report is **exported** to the *Excel* in .csv file format.
*To access report:*

    **The TNI report is accessed in 2 ways:**

      i. Individual user report from user dashboard:

         Click **TNI** at user dashboard.

              .. image:: _static/tni_dashboard.png
                 :height: 350px
                 :width: 500 px
                 :scale: 120 %
                 :align: center

      ii. Multiple users' report from admin account:

          Click **Admin > TNI > Report.** The following **TNI Report** screen appears.

             .. image:: _static/TNI_report.png
                :height: 250px
                :width: 500 px
                :scale: 120 %
                :align: center
