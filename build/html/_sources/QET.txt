.. QElectroTech documentation master file, created by
   sphinx-quickstart on Thu Jan 29 09:52:38 2015.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. toctree::
   :includehidden:
   :maxdepth: 4

Welcome to QElectroTech! 0.4 finale
===================================

**This is not just a documentation but a complete working guide!**

1. Introduction
===============

:QElectroTech: **Home Project:** http://www.qelectrotech.org

---------------------------

:Authors:
   | **Management and Development:**  Laurent Trinques scorpio@qelectrotech.org
   | **Logo:**    Nuno Pinheiro nuno@nuno-icons.com
   | **Original idea:**    Benoit Ansieau benoit@qelectrotech.org
   | **Development:**   Cyril Frausty cyril@qelectrotech.org
   | **Development:**   Joshua Claveau Joshua@qelectrotech.org
   | **Development:**    Abhishek Bansal abhishek@qelectrotech.org
   | **DXF Import Development:**    Ronny Desmedt r.desmedt@live.be

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

:Documentation:
   | **Documentation:**   Arun Kishore Eswara eswara.arun@gmail.com

~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

:Contributors:
   | **Fedora / Redhat:** Remi Collet remi@fedoraproject.org
   | **Mageia:** Trem trem@mageia.org
   | **Debian:** Laurent Trinques scorpio@qelectrotech.org
   | **Gentoo:** Markos Chandras hwoarang@gentoo.org
   | **Mac OSX:** Yoann Varenne yoann@tuxfamily.org

-----------------------------
   
:Documentation License: 
   This work is licensed under the Creative Commons Attribution 3.0 base License
   http://creativecommons.org/licenses/by/3.0/deed.en  

                                      
.. image:: graphics/license.png
   :align: center

1.1 About QElectroTech
----------------------
QElectroTech is an application to create primarily, electrical, electronics, automation and control circuits. However, QElectroTech can be exploited to create mechanical objects to illustrate processes, instrumentation drawings among various creative possibilities. QElectroTech is a good professional quality drafting application for various drawings that form a project. 

QElectroTech has a large collection of standard and custom symbols, referred to as *elements*, that describe most of the commonly used components in electrical, hydraulic, pneumatic, computer systems.  These elements can be selected drag dropped with mouse on to a diagram editor and connected with lines to represent or describe a system. A large number of such diagrams can be drafted under a project. QElectroTech is easy to use professional software that is free to download, install, use and develop. 

QElectroTech also consists of an inbuilt element editor that permits creation of newer elements that do not exist in the collection. Elements in the QET collection are not editable i.e ``'read only'``. But, once the element is drag dropped into a diagram, it is automatically added to "imported" collection in a duplicate copy. This copy of the element will be available for editing to effect suitable changes to create customized symbols.  

The finished diagrams can be exported to various formats like ``'dxf'``, ``'pdf'``, ``'jpg'``, ``'png'`` etc.,. QElectroTech is available in many international languages. It is also possible to use multiple languages in the same drawing / project. 

The elements in QElectoTech are saved in a ``xml`` format. The projects and diagrams can be saved as ``'*.qet'`` format for further editing. 

QElectroTech is distributed as a Free Software released under the GNU / GPL license. As on the date, a stable version 0.4 is released for systems operating on MS Windows, GNU / Linux and MacOS. The present English documentation is developed for 0.4 version. However, this document can serve as a complete documentation for previous versions 0.3 as well.

1.2 Installation
----------------
You can download the latest version of QElectroTech from http://qelectrotech.org/download.html. 
For GNU/Linux systems, source files can be downloaded and configured. Ready made packages for some Linux distros are also available for download.
For MS Windows systems, ready to use executable installation files (.exe) are available for download which are packed in a `zip' folder.

 1. For installation in Fedora use:
   | ``sudo yum -y install qelectrotech``

   |  or

   |  Refer to http://copr.fedoraproject.org/coprs/remi/qelectrotech/ to keep your QElectroTech installation always updated.
   
 2. For installation in debian use:
   | ``sudo apt-get install qelectrotech``

   |  or 

   |  For a nightly build devel version  - 

   | ``deb http://debian.qelectrotech.org/qet/debian/ stable main`` for stable Debian aka Jessie with Qt4 (Qt5 for nightly build devel version)

   | ``deb http://debian.qelectrotech.org/qet/debian/ unstable main`` for Qt5, nightly build devel version

1.3 Comments on basic licensing of QElectroTech distribution
------------------------------------------------------------
A collection of articles with the current version of QElectroTech are given without any warranty. It allows you to edit, modify and use the items without conditions and regardless of the final license. 

All rights granted under GNU GPL for the term of copyright on the Program, and are irrevocable provided the stated conditions are met. This License explicitly affirms your unlimited permission to run the unmodified Program. The output from running a covered work is covered by this License only if the output, given its content, constitutes a covered work. This License acknowledges your rights of fair use or other equivalent, as provided by copyright law.

You may make, run and propagate covered works that you do not convey, without conditions so long as your license otherwise remains in force. You may convey covered works to others for the sole purpose of having them make modifications exclusively for you, or provide you with facilities for running those works, provided that you comply with the terms of this License in conveying all material for which you do not control copyright. Those thus making or running the covered works for you must do so exclusively on your behalf, under your direction and control, on terms that prohibit them from making any copies of your copyrighted material outside their relationship with you.

Conveying under any other circumstances is permitted solely under the conditions stated for GNU GPL licensing. Sublicensing is not allowed.

1.4 About Using QElectroTech libraries
--------------------------------------
In the case of using all or part of the QElectroTech library for purposes other than to create wiring diagrams, you must abide by the terms of the Creative Commons-by license: 

This work is licensed under the terms of the Creative License Commons Attribution 3.0. For a copy of the license please visit the website: http://creativecommons.org/licenses/by/3.0/

or send a letter to :

  | Creative Commons
  | 171 Second Street, Suite 300
  | San Francisco
  | California, 94105, USA.

1.5 QElectroTech GUI application
--------------------------------

1.5.1 Description of the Drawing window
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
.. _Fig.1:

.. figure:: graphics/drawing_window.png
  :align: center
  :alt: QElectroTech Editor Main Window

  **Fig.1 QElectroTech Main Window**


1.5.2 Title bar
~~~~~~~~~~~~~~~
The title bar carries the name "QElectroTech" and has the options to "Close", "Minimize" or "Maximize" the application. The options can vary in each installation corresponding to the theme settings. The snapshots provided in this documentation are for GNOME in Fedora 20 with default Adwaita theme. Here you can see only a "Close" option.


1.5.3 Main Menu bar
~~~~~~~~~~~~~~~~~~~
It is a standard menu bar, which allows you to access all the features of the application such as "File", "Edit", "Project", "Display", "Settings", "Windows" and "Help". Each of the tool button further contains a number of options to initiate an action. A brief description of each such option can be read from the help or information tool bar, located to the bottom left corner of the QElectroTech window by hovering over the option with the cursor. 


1.5.4 Tool bar
~~~~~~~~~~~~~~
Tool bar houses buttons (icons) for performing basic operations in the QElectroTech window. The tool bar icons are segregated in groups with a separator. Individuals segments that form the "Tool bar" are shown and discussed here. The tool bars can be moved by left clicking and holding to select these separators and drag dropping to a new location.
 
.. _Fig.2: 
.. figure:: graphics/toolbar_1.png
   :width: 670px
   :height: 50px
   :align: left
   :alt: QElectroTech Toolbar1

   **Fig.2 QElectroTech Toolbar:**
   The `Fig.2`_ shows the first segment of the tool bar containing some active buttons and some inactive buttons. The options provided here apply to the entire but, to the selected project only. Clicking ``New`` will create a new project in the same window, similarly other active options are ``Save`` or ``Save as`` changes, ``Close`` the project, ``Print`` the project etc.,. The inactive buttons shown here work on individual element or selected elements that is / are added to the drawing. These options are activated when elements are selected. Individual element can be selected with a single left mouse click. Multiple elements can be selected by holding the ``control`` key from keyboard and selecting each element with a left mouse click. The tool bar buttons perform the action on all the selected elements simultaneously. The buttons provided here are ``Undo``, ``Redo``, ``Cut``, ``Copy``, ``Paste``, ``Delete``, ``Rotate`` and ``Properties``.

.. _Fig.3: 
.. figure:: graphics/toolbar_2.png
   :width: 270px
   :height: 50px
   :align: left
   :alt: QElectroTech Toolbar2

   **Fig.3 QElectroTech Toolbar:**
   The `Fig.3`_ shows the next segment of the tool bar containing active buttons. The options provided here are ``Add a textfield``, ``Add a picture``, ``Add a mechanical connection`` (straight line tool), ``Add a rectangular area``, ``Add an ellipse area`` and ``Add a polyline area``. The options from ``Add a mechanical connection`` are primarily special drawing aids in the main window. These are selected by single left mouse click and deselected by pressing the ``Esc`` key from the keyboard. The operation of these geometry buttons are enumerated here:
    1. Straight line, rectangle, ellipse tools: 
	 (a) Single left click the button in the tool bar to select. Left click two points on the drawing area between which the shape is to be created.
	 (b) Hover over the completed shape with the cursor, when a gray shadow is developed around the shape, double click to open special formatting options for the shape like, choosing line styles, locking the position and scaling the shape.

    2. Polyline tool: 
	 (a) Single left click the button in the tool bar to select. Left click the required number of points on the drawing area connecting which the shape is to be created. Double click at the final point to complete the geometry.
	 (b) Hover over the completed shape with the cursor, when a gray shadow is developed around the shape, double click to open special formatting options for the shape like, choosing line styles, locking the position and scaling the shape.

.. _Fig.4: 
.. figure:: graphics/toolbar_3.png
   :width: 170px
   :height: 50px
   :alt: QElectroTech Toolbar3

   **Fig.4 QElectroTech Toolbar:**
   The `Fig.4`_ shows the next segment of the tool bar containing three active buttons. The options provided here are ``Diagram properties``, ``Reset conductors``, and ``Automatic conductor creation``. 

   1. **Diagram properties:** Refer to `Diagram properties`_.

   2. **Reset conductors:** Conductors can be adjusted / altered by : 


.. _Fig.5: 
.. image:: graphics/reset_cond.gif
   :width: 450px
   :height: 350px

**Fig.5 Reset conductor tool:** (The following steps are animated in here.)
      (a) Moving one of the element that is connected by the conductor.
      (b) Single left click the conductor with left mouse button. 
      (c) Observe the conductor changes to thick red line with green squares at least one on each horizontal or vertical sections of the conductor.
      (d) Select the little green square with left mouse click and drag drop to alter the conductors.
      (e) If you decide to revert back the conductor modification to initial drawing, just click the ``reset conductor`` option in the tool bar.

   3. **Automatic conductor creation:** This is a new feature included in QElectroTech version 0.4. By default the tool is "active" upon starting the application. It permits automatic conductors creation when two terminals of an element are aligned in either vertical or horizontal plane.

.. _Fig.6: 
.. image:: graphics/auto_cond.gif
   :width: 450px
   :height: 400px
   
**Fig.6 Auto conductor creation:**
         (a) To use this setting, reposition the element relative to another element between which conductors are to be drawn. 
	 (b) Observe the vertical or horizontal guides that appear during repositioning. 
	 (c) For vertical conductors (North/South), the vertical guide line, which is thick blue in color turns green on alignment. 
	 (d) Drop the element being moved at this point to automatically create conductors between them.
	 (e) You may now adjust your elements (reposition) to suit your requirement. The conductors will take shape automatically as you reposition your elements.


1.5.5 Elements panel tools
~~~~~~~~~~~~~~~~~~~~~~~~~~
The elements panel tools are shown highlighted with green box in the `Fig.1`_. The panel contains essential tools for creating or editing or deleting elements and categories that can be used in the `Work Area'. These tools perform operations on elements, templates or categories. The entire column of utilities effect templates and elements and are discussed below:

.. _filter: 

**Filter**
    A filter is provided to quickly search elements by looking for matching input keywords typed into the search bar. When a keyword is entered, each matching element is displayed along with its tree, i.e. under the category in which the element is located. Only the categories which hold a matching element for the searched keyword are displayed (refer `Fig.1`_). The entered keyword can be cleared by left clicking the **X** button (provided left to the search keyword text input field) to display normal categories and QET elements. The keyword can also be cleared by using ``backspace`` key or ``delete`` key from keyboard or selecting the text with mouse and deleting the entered keyword(s).

**Elements panel tool bar**
    The "Elements panel tool bar" contains tools to create, edit, delete and reload categories and elements. The function of each of the tool is explained in animation `Fig.20`_ under `Section.10`_.


**QET Drawing templates (QET title blocks)**
    The "title block" has a number of templates to select for the drawing. User can also design his custom template for the project. A set of Standard templates are provided with the QElectroTech installation. A template can be applied to the drawing by selecting the template and drag dropping it on to the "drawing or the work space". The templates can be edited from "diagram properties" using the drop down box provided right to the template field. The QET standard templates are read only and cannot be edited in place. However, once a template is applied to a drawing, its copy is imported under the project title shown with a blue highlighted box in `Fig.1`_. You can right click the imported template and choose to edit the template. Refer to a sample tutorial ----- under section --- .

**QET Collection**
     QElectroTech provides a set of readily available elements in "QET Collection" under a relevant category. Elements can be selected with mouse and drag dropped onto the work space to add them to a drawing. It is possible to search for an element using keywords in the filter discussed earlier under the topic filter_.

**User title block**
     A user can edit the standard templates as mentioned earlier and use it for a project. These edited templates are only available under the project or to the projects opened simultaneously in the same window. However a user can also create a custom template and preserve it for future uses by adding it to the user title block. The title block is a place where user(s) can design their own templates and preserve them for future use. New categories (folders) can be created under the title block to hold custom templates.

**User collection**
     User collection is the place where user(s) can add new categories and elements or to delete or modify earlier added categories and elements. The user can create a new element using basic shapes or tools in the element editor or modify imported elements and save. The user also has an option to import new elements stored in a file. Refer to a short animation graphic in `Fig.20`_ under `Section.10`_.


1.5.6 Control tabs
~~~~~~~~~~~~~~~~~~
Two tabs are provided to the bottom left corner of the QElectroTech application main window, to switch between the elements panel and the ``Undo`` panel. Elements panel is default view in QElectroTech. ``Undo`` tab records each change to a diagram in the chronological order. The user, can at any point of time may wish to go back to any previous point in the diagram by selecting it in the ``undo`` tab. Each change that is effected by user's action in the diagram are recorded vertically in the ``Undo`` window. Select a point in the history where he/she wishes to return to and switch back the tab to "elements panel". The changes that were effected after the event will be undone. After the undone action, the user will find that the actions that were undone are highlighted in light pink color, under appropriate category in the elements panel. These actions are marked internally by QElectroTech as unused in the project. The tabs can be turned ``off`` or ``on`` from the tool bar ``settings`` and selecting the ``display``. Unchecking the options will turn off the corresponding views tab or tools in the main window.
However, it should be understood that only actions that are related to drawing can be undone such as adding or deleting of elements, conductors etc.,.

1.5.7 Help bar
~~~~~~~~~~~~~~
The help bar is the space below the control tabs, the bottom left most corner of the main window. It is very useful for beginners of QElectroTech in the way that it gives information about the field that is pointed by the cursor. A user can learn about a field by simply pointing it with the mouse and looking at the help bar.

1.5.8 Drawing and Project tabs
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

The drawing or diagram can be given a name in the ``diagram properties``. Either click the ``diagram properties`` from the tool bar or double click the ``drawing tab``. There are many other options that can be set in the diagram properties window. Once a name is given to the drawing, it gets displayed in the ``drawing tab``. 

The project is named by "Project XXXX" where XXXX is the name of the file (`*.qet`) as which it is saved. In QElectroTech each project is a different file. Individual drawings forming part of the project are displayed when a project is selected. It is possible to work with many projects in the same window.

By default, QElectroTech displays the project name as "untitled project" in the project title tab and "Untitled" in the diagram title tab. The user can save the project by giving it a name of his/her choice as a file. The project title tab displays the name of the project, which is saved as "*.qet" file on the computer. There is an option to close the project, by clicking  at the top right corner of the project title bar. A new project can be opened in the same window, which opens as a new tab in the project title. User can switch from one project to the other by left clicking the tabs with the mouse or pressing ``control + tab`` key from keyboard. The project title can be changed from the main menu bar ``Project``, then selecting the ``Project Properties`` and entering a name for the project in the project title field.

1.5.9 Workspace
~~~~~~~~~~~~~~~
The workspace is analogous to the drawing chart. The work space is directly affected by the template applied. By default, work space is divided into cells rows from `A' to `H' and columns `1' to `17'. The rows and columns can be modified by adding or deleting rows and columns from the diagram properties window. The default size of each column is 60 pixels and that of each row is 80 pixels, both of them can be adjusted in the diagram properties. Workspace is the area where the diagram is prepared, by including elements, conductors, text and pictures. The title block section of the workspace contains information related to the drawing such as - `Author', `date', `Title', `File' and reference `Folio' numbers.

.. _Section.2:

2. Creating a New Project
====================

A new project can be opened from the main menu bar by selecting ``File`` and clicking ``New`` or by clicking the shortcut icon |newfile| from the tool bar.

.. |newfile| image:: graphics/newfile.png

.. _Fig.7: 
.. Figure:: graphics/project_properties.png
   :height: 600px
   :width: 800px
**Fig.7 Project properties window** [For more description go to `Project properties`_]


A "name" for the project created can be given in the ``Project Title`` field of ``Project properties``. Click ``Projects`` from main menu to access these options. The project title tab now displays the project name as ``Project "name" [modified]``. The project should now be saved as a file `file\_\name.qet`, the project title tab then displays ``project "name"``. A project can have this "name" different from the name of the file as which it is saved. Alternatively, a project which acquires its name from the file name can be overwritten by this action. The ``Project properties`` window has several options to be set. Such options are applied to all subsequent drawings added to the project. The present drawing properties should be set from the ``Diagram properties`` option in the tool bar or by double left clicking the drawing tab. Project properties window is further explained under `Project properties`_.

.. _Section.3:

3. Creating a new diagram
=========================

By default, QElectroTech opens an `Untitled` diagram under an `Untitled project` when a new project is created (refer `Section.2`_). A new diagram can also be created by pressing ``Control + t`` keys from keyboard or by clicking the ``add a diagram`` button |newdrawing| located rightmost on the ``diagram title bar`` or by selecting the ``add a diagram`` from the ``Project`` option on the main menu bar. The drawing name and other properties can be set by invoking ``Diagram properties`` button from the tool bar. The ``Diagram properties`` can also be launched from the menu bar ``Edit`` and selecting the ``Diagram properties`` or by pressing ``Control + L`` keys from the key board. The diagram properties window has options to assign a name to the diagram, author's name, date, changing the dimensions of the work area by adjusting number and dimensions of rows and columns, or selecting a standard template for the drawing etc.,. There is a custom tab provided for user defined keys.

.. |newdrawing| image:: graphics/add_drawing.png

.. _Fig.8:
.. Figure:: graphics/diagram_properties.png
   :width: 800px
   :height: 500px
**Fig.8 Diagram properties** [For more description go to `Diagram properties`_]

The ``Diagram properties`` window is explained further in the section on `Diagram properties`_ to describe most of the features it houses. 

.. _Section.4:

4. Configuring QElectroTech
===========================

QElectroTech permits customizations through configure option. To open the "configure window" click ``Settings`` from the main menu bar and select ``Configure QElectroTech``. The customizations can be effected to 

(1) **Configuring General window**

.. Figure:: graphics/config_qet1.png
   :height: 500px
   :width: 700px
   :alt: configure_general
**Fig.9 Configuring General window**

General window has the following customizations permitted in QElectroTech:
        (a) **Appearance:** (Default value is ``System colors``)

	    (i) Checking the option for `Use system colors' will make QElectroTech to pick up the same color profiles that are applied to the Operating System environment, like MS Windows or Debian Linux etc.,. 
	    (ii) Uncheking the option will make QElectroTech appear with a default appearance, which will be immune to the Operating System Environment color profiles.

	(b) **Projects:** (Describes how projects appear in the main window, default value is ``Tabs``.) These options require restarting the QElectroTech application to effect the changes.

	    (i) *Tabs:*  Checking the option will make projects appear as tabs in the QElectroTech window. Projects that are added subsequently will appear as tabs in the ``Project Title bar``.
	    (ii) *Windows:* Checking the option will make projects appear as individual windows with its own set of diagrams. Newer projects added subsequently will also behave as new windows. The ``Minimize``, ``Restore`` and ``Close`` options for the windows appear to the right most on the "main menu bar". 
            (iii) *Use gestures touchpad:* Use the option for touchpad control of projects tabs in QElectroTech.

	(c) **Elements Management:** (Default value is both options selected).

	    (i) *Integrate automatically the elements in to the projects:* The option is reponsible to automatically import the elements added to the drawing into the ``Imported elements`` under ``Embedded collection`` of the project in the elements panel. In QElectroTech, the elements that are provided with the installations (in QET Collection) are not editable. However, once they are imported to the ``Imported elements`` of the project, they are available for editing in the element's editor. They can be modified and reused in the drawing. The choice is therefore recommended. Refer to the section on `Elements editor`_ to learn to use the elements editor. You may gain quick overview by watching the animation in `Fig.20`_ under `Section.10`_.

	    (ii) *Highlight freshly integrated elements in the panel:* The choice will generate highlighting colors over the elements imported in the ``Imported elements``.

		 (a) Yellow color flashes over the parent element and the element imported to the ``Imported elements`` at the time of importing. 

		 (b) If the elements that are imported to the project under ``Imported elements`` are subsequently deleted from the drawing(s), then these elements will be permanently highlighted in light pink color indicating that they are unutilized in the project. The highlight is however only displayed under the project in the elements panel and will disappear if they included again in any of the drawings under the project.

	(d) **Language:** (Default value is ``System`` ) QElectroTech comes with many languages and the default language can be selected here. The language option can be set from the combo box next to language settings. You can either choose a fixed language in the QElectroTech application by opting your choice or leave it to the ``System`` option. In which case, QElectroTech automatically starts with the Operating System Environment language preference. Changing the system language would automatically change (update) the language for QElectroTech application.

(2) **New project**

.. Figure:: graphics/config_qet2.png
   :height: 500px
   :width: 700px
   :alt: configure_project1
**Fig.10 Configuring New Project - Diagram**
	 
      (2.1) **Diagram:** Some of the workspace settings are provided here. The customizable options include:

          (a) **Diagram size:**

             (i)   Number of columns and rows for the grid.
	     (ii)  Size of each column and row.
	     (iii) The headers for the columns and rows can be turned on / off. Headers are the `A', `B', `C' etc., for rows and `1',`2',`3' etc., for columns.
	     (iv) Option to fill gray color in the back ground.

	   (b) **Information title block:** The specific terms (fields) that are used here will be explained together with their use. The fields provided will be applied by default to all subsequent projects / diagrams as the case may be. The information title block comes with two tabs ``Main`` and ``Custom``. The ``Custom`` tab is still under development and is not described here.

	      (i)  Title provides the default name of the diagram that will open with each of the subsequent projects. Title name is usually given to describe the drawing for example, like a power generation system, distribution system etc.,
	      (ii) Author provides field to enter the name (or a pseudo name) of the person creating the diagrams in the project. 
	      (iii)  Date field has options to :
		     
		     (a) Not specify a date for the drawings
		     (b) Apply today's date i.e. the computer systems date will be applied to all subsequent diagrams. The value is dynamic changes with each passing day.
		     (c) To set a default date (fixed) to every subsequent drawing. The value is fixed and do not change.

	      (iv)  File name applies to the top right field (cell) in the drawing / diagram title block. The file name can be for example the name of the system in a project. A system can have its drawing spread over several drawing sheets and all carry the same system name i.e. file name. 
	      (v)  Folio name is an additional field to specify the drawing in a file. Folio names are usually provided to specify the current diagram in a sequence of files across which a file is named (system is specified). The field is by default set as ``%id/%total``, which is a dynamic nomenclature. When a new diagram is added in the same project it is updated as "the number of the current drawing" / "total number of drawings created". 

.. _configure conductor:

.. Figure:: graphics/config_qet2-1.png
   :height: 500px
   :width: 700px
   :alt: configure_project2
**Fig.11 Configuring New Project - Conductor**

      (2.2) **Conductor:** Conductor is basically the line that connects two elements in the drawing. The customization window has options to tweak conductor type and conductor appearance.

             (a) **Conductor type:**  The options that are provided to customize the conductor type and its text appearance as:
		 
		 (i) **Multiline:** The optional default text that should appear with each conductor can be entered in the ``Text`` field. The size of the font can be specified in the adjacent ``Size`` field. On the otherhand, the text field can be made invisible by "Unchecking" the ``Visible`` option i.e. no text will be displayed across the conductors, when they are created. **Note:**  The ``Show one text per folio potential`` option is still under development. 

                 (ii) **Angle of conductor labels:** The option to set an angle to the text that appears together with each conductor created can be set here. The options are provided under two categories, namely -
		      
			(a) *Vertical:* The vertical option is to set the default angle to the text that appears in the vertical direction. The angle can be set in eight specified intervals with the graphic interaction tool. Click the green squares on the yellow circle to set the specified angle. Also, a finer control over the angle precision can be achieved upto two decimal places in the adjacent combo box in degrees, by keying the value from the key board. Clicking the ``up`` or ``down`` keys in the combo box increments or decrements the angle by one degree only.
			(b) *Horizontal:* The horizontal option is to set the default angle to the text that appears in the horizontal direction. The angle can be set in eight specified intervals with the graphic interaction tool. Click the green squares on the yellow circle to set the specified angle. Also, a finer control over the angle precision can be achieved upto two decimal places in the adjacent combo box in degrees, by keying the value from the key board. Clicking the ``up`` or ``down`` keys in the combo box increments or decrements the angle by one degree only.

	         (iii) **Single line:** The single line formatting provision is strictly included for the electrical diagrams. The provision shortens the representation of conductor(s) between two or more elements by including added information over the conductors, to convey a more meaning. In a typical domestic AC circuits we use a phase, a ground and a neutral wire. A drawing for such a circuit will require adding three conductors running parallel between the elements. This may clutter drawing and an alternate way exists to specify that a single line shown in the drawings represents a phase, a neutral and a ground cable. This is possible by choosing the ``Single line`` radio button and checking out the options (default) ``ground``, ``neutral`` and ``phase``.  The ``neutral`` option has additional option called ``PEN`` to specify that the neutral cable is a specific Protected Earth Neutral. It is therefore logical to have a requirement for ``PEN`` to be active, that both ``ground`` and ``neutral`` be checked out first. The following points will summarize operations under **Single line**.
		       
		        (a) A conductor can be formatted as any one or a combination of ``ground``, ``neutral`` and ``phase``. The small conductor snippet is provided to generate a preview of the likely conductor appearance after effecting the options.
		        (b) Selecting both options ``ground`` and ``neutral`` will permit to specify whether the conductor is a ``PEN`` type or not.
		        (c) The ``phase`` option is additionally facilitated with a slider and a double spin box, to specify the number supply phases. Provision exists to set a maximum of three phases only. 
		        (d) The number of phases can be specified either by selecting and dragging the slider bar or keying in direct value in the double spin box or also by clicking the up / down keys of the double spin box to increment or decrement value by 1 unit.

	     (b) **Conductor appearance:** Options that are provided to customize conductor appearance are:
		   
		 (i) **Color:** A default color can be specified for the conductor from the color selection box. Left click on the color setting box, and pick up a color either from the existing basic colors or define a custom color by using the color mixer options and select it in the pop up color window. Click ``Ok`` to apply the option or ``Cancel`` to exit without applying the changes. 

		 (ii) **Style:** Currently three styles are available to choose from, for the default conductor appearance. The option can be selected from the list box next to the ``Style:`` option. 

.. note::  The text that appears for the conductors created can switch between horizontal or vertical by adjusting the conductors. Refer to section **uuuuuuuuuu** to learn how to adjust conductors. 
\

.. seealso:: 

   PEN
     On the low voltage circuits, sometimes the earthing and neutral functions are combined in the same conductor of the supply cable; this is known as a PEN conductor. The PEN conductor is earthed at multiple locations along its length using separate conductors (earthing). The conductor will be branched at each consumer (in domestic supply it may be a house) as a "neutral" and "earth". This kind of distribution of electrical power supply is called TN-C system. This PEN conductor will provide a return path for both operating conditions - a neutral current flow under normal operating conditions and for the earth fault current during the duration of a line to earth fault. 


.. _Reports folio:

.. Figure:: graphics/config_qet2-2.png
   :height: 500px
   :width: 700px
   :alt: configure_project3
**Fig.12 Configuring New Project - Reports folio**	 

      (2.3) **Reports Folio:** A set of ``parent`` and ``child`` elements are provided in QET Collection along with two other special referencing elements in QElectroTech. The two special referencing elements are ``Previous folio`` and ``Next folio`` located in the tree ``QET Collection`` --> ``Electric`` --> ``All-pole`` --> ``Sheet referencing``. Refer to section **uuuuuuu** for more description on reports folio. The referencing index that these elements generate between different drawings with in a project or within the same drawing can be customized from **Label of report folio** in the `Reports Folio` tab. There are three keys f (the number of folio), l (line number), c (the column number), which are internally defined in QElectroTech. User can shuffle these keys to customize his/her default reference indexing. ``%`` symbol should be used prefixed to these keys to replace the keys with corresponding numbers in the drawing. A short explanation to the set of ``parent`` and ``child`` elements is provided in `Cross References`_.

.. Figure:: graphics/Folio_elements.png
**Fig.13 Folio elements in QET Collection**


.. Figure:: graphics/config_qet2-3.png
   :height: 500px
   :width: 700px
   :alt: configure_project4
**Fig.14 Configuring New Project - Cross references**

.. _Cross References:

      (2.4) **Cross References:** The cross references tab is provided primarily to label coils and contacts in electrical diagrams. Often electrical diagrams for example, like motor starters and protection systems will have a number of contacts and coils located at various points and correct referencing the contacts for their actuating coils in the diagram is of prime importance. The referencing customizations can be effected from this ``Cross references`` tab for subsequent projects or drawings. The current version has incorporated only basic functionality of referencing. The complete functionality of these elements is currently in development stage.


.. Figure:: graphics/Parent_child.png
**Fig.15 Parent Child and Manual entry elements in QET Collection**


.. _Export:

(3) **Export**

.. Figure:: graphics/config_qet3.png
   :height: 500px
   :width: 700px
   :alt: configure_export
**Fig.16 Configuring New Project - Export**

The drawings from QElectroTech can be exported to different formats. Currently it is possible to export the drawings from QElectroTech as ``svg`` (Scalable Vector Graphics), ``bmp`` (Bit map), ``dxf`` (Drawing eXchange Format), ``jpg`` (Joint Photographers' Expert Group format) and ``png`` (Portable Network Graphics). The various configuring options provided in the export window are:

            (i)  *Target directory:* The default directory to which the drawings can be exported.
	    (ii)  *Format:* The exporting format to which the drawing can be saved into the default directory.
            (iii)  *Rendering options:*
		 
		 (a) **Export the border:** This option will cause the entire drawing to be exported.
		 (b) **Export only elements:** This option will export only the elements from the drawing. The connectors between the elements will be preserved. However the rest of the workspace is omitted.
		 (c)  **Draw the border:** The option specifies that the rows and columns provided in the drawing area to be included in the exported graphic.
		 (d) **Draw the inset:** The option specifies that the drawing title block to be included in the exported graphic.
		 (e) **Keep conductor colors:** The option specifies that the conductors colors assigned during drawing to be preserved and included in the exported graphic.
		 (f) **Draw the grid:** The option specifies that the `dotted' grid to be included in the exported graphic.
		 (g) **Draw terminals:** The option specifies that the terminals (red tail with blue square) also to be preserved and included in the exported graphic.

.. note:: 

   You can only choose one of these two options (a) or (b).



The default settings are ``Export the border``, ``Draw the border``, ``Draw the inset`` and ``Keep conductors colors`` only. Other options are left for the user to choose.


(4) **Printing**
 
.. Figure:: graphics/config_qet4.png
   :height: 500px
   :width: 700px
   :alt: configure_printing
**Fig.17 Configuring New Project - Printing**

The printing options are similar to the export options. Refer to the description for Export_. The default values are ``Draw the border``, ``Draw the inset`` and ``Keep conductors colors`` only. Other options are left for the user to choose.



5. Working with elements
========================

QElectroTech has a number of elements listed as a tree under ``QET Collection`` in the left pane of main window. The collection of elements (shown highlighted in yellow square in `Fig.1`_) is organized under relevant categories (folders). Users can click on the ``+`` symbol located left to the category to surf the elements or more categories under its tree. Alternatively an element can be searched quickly using ``Filter`` field, refer to filter_.  Each element can be selected using left mouse click and drag dropped on to the work area to include it in a diagram. The elements can be positioned any where in the work area. Some of the tools in the tool bar apply to elements such as cut, copy, paste, delete, rotate, element properties and select tools. Refer to |elmttools| from tool bar.
Some of the operations possible with elements:

   (1) **Cut and Paste** 

      (a) Elements can be cut paste by using the `scissors' icon and `Paste' icon from the the tool bar.
      (b) Standard keyboard shortcuts like ``Control+x`` will also cut the element and ``Control+v`` will paste the element.
      (c) Restrict the cut and paste functions within the same project. The elements would suffer data loss if the operations are effected over more than one project.

   (2) **Copy**

      (a) Elements can be copied by clicking the "Copy" icon from the tool bar or using ``Control+c`` from the keyboard. Copied elements can be pasted in the same drawing or another drawing of the same Project. Pasting into a new project may cause loss of data. 
      (b) *Always use add an element (drag dropping into drawing) for new projects.*


   (3) **Delete** 

       (a) Added elements can be deleted by selecting the element with a left mouse click and pressing either ``Delete`` key from keyboard or clicking the delete tool in the tool bar.
       (b) It is possible to *Delete* more than one elements at a time by selecting them and applying delete option. Refer to `Selection properties`_ to know how to select more than one element.


.. Figure:: graphics/elementrotate.png
   :width: 800px
   :height: 500px
**Fig.18 Rotating element** (in steps of 90\ :sup:`o`\)

.. _rotating elements:

   (4) **Rotating**
      
       (a) Rotation of elements can be performed by selecting the element in the work area with left mouse click and pressing ``space`` key from key board. 
       (b) Elements can be rotated in quantum steps of 90\ :sup:`o`\  (degrees). 
       (c) Rotate option in the tool bar turns active upon selecting at least one element in work area, which can be clicked to orient the selected element(s) to the required rotation. 
       (d) A number of elements can be selected together by holding ``control`` key from key board and left clicking required number of elements in the work area. Once the required elements are selected (evident from light gray box enclosing each selected element), rotation operation can now be performed on all the selected elements together as described earlier. Some elements like for example, a horizontal ammeter that cannot be rotated for obvious reasons.


.. Figure:: graphics/rotate_multi_elmt.gif
   :width: 800px
   :height: 500px
**Fig.19 Rotating more than one element** (with and without text selected in steps of 90\ :sup:`o`\)


.. _Selection properties:
   
   (5) **Selection properties**

       (a) Clicking the `Selection properties' tool will pop open a properties window for the selected element. 
       (b) At a time more than one element can be selected either by holding ``Control`` key from keyboard and selecting each element by left clicking it with mouse or by clicking a point in the workspace, holding it and dragging a selection square encompassing the elements to be selected. 
       (c) When more than one element is selected, the selection properties window will have no options. Or in otherwords the software will not permit defining properties for a collection of elements simultaneously. It has to be done element by element.

.. Figure:: graphics/select_multi_elmt.gif
**Fig.20 Illustration of selecting more than one element with mouse**

.. |elmttools| image:: graphics/element_opern.png



5.1 Folio Report
----------------

Folio report is included in the ``QET Collection``  --> ``Electric`` --> ``All-pole`` --> ``Sheet referencing`` in the collection of QET Elements. The element performs the referencing roles in the drawings. Refer to the section `Reports folio`_ . 

6. Working with Text Fields
===========================

6.1 Inserting text field
------------------------

``Add a Text field`` tool is provided in the tool bar of the main window. To add a text field into the work space

          (a) Click the ``Add a Text field`` tool and click at a point in the work space, where the text field should be added. 

The text field by default appears as an underscore and it can be either used in association with an element or as an additional field inserted in the work space. 

Some elements are provided with a text field at each of their terminals and / or one for the entire element. Additional text fields can be added any where in the work space by the procedure described earlier. The text field can be edited in the work space by 

         (a) Double left clicking the text field with the mouse and keying in text from keyboard. 

	 (b) To exit editing, click any where else in the workspace. The text field supports multi-line entries and a few formatting options.

6.2 Orientation of the text field in workspace
----------------------------------------------

All the text fields are horizontally oriented in the work space by default but, they can be oriented in any direction. The text field can be re-oriented by rotating it as described below:

          (a) Select the text field by left clicking it with the mouse.
	  (b) Rotate it with the ``Rotate`` tool from the tool bar - refer to section on `rotating elements`_. Alternatively the element can be rotated in quantum steps of 90\ :sup:`o` \ by pressing the ``space`` bar from the keyboard.
	  (c) The text field has special rotation attribute that it can be rotated precisely upto two decimal places of a degree. 

	      (i) Select the text field and press ``control + space`` keys from keyboard to pop open a GUI window to rotate the text field in any direction.
	      (ii) The GUI window facilitates rotation in quantum steps of 45\ :sup:`o`\  degrees by clicking the green squares on the yellow circle. 
	      (iii) A double spin box is also provided to manually enter an angle of orientation upto two decimal places. The double spin box can also be interacted with a left mouse, by clicking the up or down arrow keys, to increment or decrement the angles in steps of 1 degree correspondingly with each click.

 

.. Figure:: graphics/guitextrotate.png
   :width: 400px
   :height: 400px
**Fig.21 Rotate text with orientation pop up window** (The text selected (top right corner) is rotated by -25.75\ :sup:`o`\  degrees)



6.3 Moving and editing text field in work place
-----------------------------------------------

Text field can be moved any where in the workspace by 
    (a) Selecting it with a left mouse click and holding it and drag dropping the text to a new position. 
    (b) Text fields that are associated with the elements require ``control key`` to be pressed from the keyboard to permit moving its text field along with the earlier described procedure. 

Moving an element's text field produces a blue colored highlight over the element during relocation as shown in the Fig.22. This feature of QElectroTech helps user to perform such actions in a large diagram and still conspicuously keep track of its parent element.


.. Figure:: graphics/textmove.png
   :width: 300px
   :height: 150px
**Fig.22 Illustration the step (b), repositioning an element's text label**


Text fields that are not associated with elements have an additional editing options - 
     (a) Select the text field with a left mouse click and use the keyboard short cut ``Control + e`` or from the main menu bar, select ``Edit --> Edit the text field``. A simple text editor window opens up to facilitate some basic text formatting features such as increasing the font size, font color, applying bold / italics / underlining formats to texts and inserting a hyperlink. 

.. note:: The hyperlink is preserved only for the diagrams that are exported to `pdf' format. For other picture exporting formats the hyperlink appears as a underlined text.

.. _edit text:

.. Figure:: graphics/edit_text.png
   :width: 370px
   :height: 400px
**Fig.23 Edit text window for the text field in workspace** This is a WYSIWYG (What You See Is What You Get) editor.



7. Working with connectors
==========================

Elements have terminals, a conductor generating extension to elements to connect them with other elements or connectors. Making connections between terminals can be summarized as follows:
         
        1. Position the cursor on the element connector or terminal you want to connect; you will see that a blue dot appearing on the terminals you want to join.
        2. Left click the blue dot and hold and drag the pointer to the connector or terminal to join the other element you want to connect. If a green dot appears on the target terminals, it means that the conductor path between them is complete. A red dot means a ``forbidden connection".
	3. Release the left mouse button and the conductor will be completed. The conductor assumes a path between the two elements. However, the connectors can be edited by selecting the conductor with a left mouse click and dragging the green squares on it. Refer to `Section 8`_ for more operations with conductors.

.. Figure:: graphics/insert-wires_1.gif
   :width: 400px
   :height: 250px
**Fig.24 Animated graphic showing making of conductor between two elements**

.. _Section 8:

8. Resizing conductors (connectors)
==================================

8.1 Adjusting conductors by moving elements
-------------------------------------------

          1. Select an element in a circuit by left clicking it and hold it in the work  space.
	  2. Drag the selected element in the circuit, the connectors linking the element to the rest of the circuit also moves.

.. Figure:: graphics/elmtmove.gif
   :width: 450px
   :height: 400px
**Fig.25 Adjusting conductors by repositioning elements**

8.2 Adjusting conductors with handles
-------------------------------------

        1. Select a connector with a left mouse click. The segment of the selected connector between two elements turns red, indicating that the conductor is selected.
	2. Position the cursor over the selected connector; you will find thick green colored squares appear over this segment, one each in a bend.
	3. The connector can now be adjusted as per the users demands by left clicking these thick little squares and holding and dragging to a new position. The connector changes its path during this action.
	4. To reset the altered path, left click the short cut icon `Reset conductors' provided in the tool bar with the connector selected (highlighted red). This action will undo all the earlier changes effected to the connector.

.. Figure:: graphics/cond_move.gif
   :width: 450px
   :height: 400px
**Fig.26 Animation showing adjusting conductors with handles and reset tool**

8.3 Adding text to connectors
-----------------------------

Connectors are provided with text fields, which can be configured from the new project option and conductor tab. Additional text fields can be inserted at desired locations. Text fields for connectors have the same behavior as the text fields for elements discussed under creating a new diagram. Double left click a connector text field and enter the text. The text can orient horizontally or vertically depending on the section of the connector where the test field is provided. The text fields can be rotated and re-positioned as required. Refer section on `configure conductor`_ for a complete list of configuration options.

8.4 Connector properties window
--------------------------------

A connector's properties window can be activated by double left clicking it. The connector and its text field properties can be set from this window. Only multiline connectors have text fields. Selecting the ``single line`` radio button deactivates the text field. The single line option has further options to format the connector as an earth, phase or a neutral conductor or a combination of any. Selecting the ``neutral`` option further facilitates formatting the conductor as ``Protective Earth Neutral`` (PEN). Number of phases can also be set upto 3 by selecting the ``phase`` radio button and using the slider or keying a value into the double spin field. Color and styles to a connector can be applied irrespective of other choices. Refer section on `configure conductor`_.

9. Element's editor
===================

9.1 Creating a new element
---------------------------

Elements in QElectroTech exist in "xml" format. The ``QET Collection`` of elements provided with default QElectroTech installation parameters, are saved in a invisible folder ``$HOME/.qet/elements``. User may however save his/her elements anywhere on the disk. But, QElectroTech detects its elements only from this default folder whenever ``Reload`` is executed from the ``Element's panel tool bar``.  

Elements provided in the QET collection are read only and cannot be edited. However, they can be added to "User collection" and subsequently edited and saved. The animation graphic presented at `Figuuuuu`_ of `Section.10`_  will explain the steps in creating a new element.

        1. Select the 'User collection' with a left mouse click over it. Then elements can directly be created under it. However, it is a good practice to first create a `category' under `User collection'. 
	2. Left click the shortcut icon `New category'. Then `Add a new category' wizard opens, which guides the user for subsequent actions.
	3. Enter a name to the new category (internal name); the field takes only small letters, numbers and `-', `_' and `.'. 
	4. Double left click the text field, enter a name that the category should display and hit `enter' from keyboard. By default, the field shows `Name of the new category' and language `en' for English versions. Additional support languages can also be added by left clicking the `Add a line' button. Now left click `OK' button to add the category to user collection. This action can also be achieved by hitting `enter' key from keyboard. 

A new category is now added under `User collection'; its internal name is displayed in the tool tip and the name displayed is from the text entered in the text field in step 4.

        1. Select this category with left mouse click.
	2. Click on the shortcut icon on tool bar to create a `New element'.
	3. A `Create a new element' wizard opens up, which guides the user to create an element. Select the category in which the new element created will be placed.
	4. Click `Next' button.

Step 8 opens up a request for a file name for the element to be created.

        1. Enter a name for the element to be created. Naming convention is similar to that of the internal name for category explained earlier in section ----. Click `Next' to continue the wizard.
	2. Select the text field and left double click on the default text displayed. The field will be editable now.
	3. Enter a name by which the element will be displayed under `User collection'. The text field accepts all valid keys. After entering a name, hit `Enter' from keyboard. Hit `Enter' key from keyboard one more time or click `Finish' button to complete the wizard.
	4. The wizard now completes opening up `Element editor' window. The element editor facilitates drawing of a new element or editing imported elements under `User collection'.  The element editor has a plain drawing area with two thin red colored reference cross hairs. The cross hair is for reference and does not show up in the finished element sketch when saved. 

.. _section 9.2:

9.2 Description of Element editor
---------------------------------

9.2.1 Title bar:
~~~~~~~~~~~~~~~~
The title bar has buttons that all standard windows are provided with.

9.2.2 Drawing area:
~~~~~~~~~~~~~~~~~~~
This is the dotted grid area over which the elements are drawn.

9.2.3 Undo & Parts:
~~~~~~~~~~~~~~~~~~~
By default the element's parts is the active tab. It contains all the individual segments that make up an element in the chronological order. The `Active area' segment is highlighted in this tab. Undo tab records each action made in the element editor and the user can visit any stage by selecting the corresponding entry in this tab.

9.2.4 Main menu:
~~~~~~~~~~~~~~~~
Main menu has `File', `Edit', `Display', `Settings' and `Help' icons.

        (a) **File:** The file option has standard windows options for creating a new element, opening a saved `\*.elmt' file or `\*.xml' drawings, opening an element from `User collection' or `imported collection', saving the drawing to their respective locations and inter alia. `Reload' options reloads the element drawing neglecting all the changes effected. 
	(b) **Edit:** `Edit' has standard options like `cut', `copy', `paste', `select all', `undo', `redo' and `delete'. `Invert selection' selects all geometry in the drawing area. It has analogy similar to shuffling a pack of playing cards. Options to set the author name and his license and adding language features to the drawing are also available.

	(c) **Display:** This icon has the zoom in / zoom out options for the drawing.
	(d) **Settings:** This has features to turn on or off panels or tabs that constitute the drawing editor, a full screen mode and configure QElectroTech options. Configuring QElectroTech will be described in a later section.

9.2.5 Information panel:
~~~~~~~~~~~~~~~~~~~~~~~~
It is also the properties window for the selected individual segments that make up an element. The information panel contains two groups of properties `appearance' and `geometry'. Geometry defines the segment selected in the work area (active area). It is possible to fine tune the coordinates of the segment from the information panel. The geometry describes `active area' selected. A simple line, a square or a rectangle, a circle, text fields, a terminal and an arc will have their own set of specific parameters, which are displayed in the information panel. Try drawing each of the drawing tools in the work area and select them to define `active area' and  check the information area. Watch how the parameters change with each geometry; also try changing the parameters to note their effect on the `active area'. The appearance properties define the line style, color, weight, filling for closed geometry like rectangle, square etc., and another property called `antialiasing', which is to remove distortions of the skectches and smoothem for better smoother appearance. Geometry parameters define the `active area'and they are shape specific; for example, a line segment will have start finish coordinates, beginning side or ending styles (to draw arrows, diamonds etc.,) and corresponding weight factor to size these ending styles. 

9.2.6 Active area:
~~~~~~~~~~~~~~~~~~
Active area is the part of the element that is selected with a left mouse click. The active area data is displayed in the information panel and the segment will be highlighted in the `element parts' of the editor.
 
9.2.7 Element:
~~~~~~~~~~~~~~
Element is the completed drawing of a symbol, which is used to represent a component in a circuit drawing. Elements can be given names to describe them and saved either in a \*.elmt or a \*.xml format. An element should be provided with at least one terminal to facilitate its integration in a drawing. The element can also be saved to `User collection' among others. Two types of text fields are possible to be added to an element to either describe it or its segments and terminals. The text fields are described in detail later under section \ref{sub:drawingbar}. One text field is not editable when the element is saved and used in the QElectroTech drawing while the other has users text input feature.

9.2.8 Main tool bar:
~~~~~~~~~~~~~~~~~~~~

The main The main tool bar is a collection of quickly accessible shortcuts to the features available in `Main menu' group under `File', `Edit' and `Display'. tool bar is a collection of quickly accessible shortcuts to the features available in `Main menu' group under `File', `Edit' and `Display'.

9.2.9 Drawing bar:
~~~~~~~~~~~~~~~~~~
The drawing bar has the tools for constructing an element. The options include a cursor tool to permit selection of either individual segments of the drawing or a combination of these, including text and terminals. The drawing tools are each described below:

9.2.9.a Line tool:
>>>>>>>>>>>>>>>>>>

Use a left mouse click to select and activate the `Add a line' tool from the drawing bar. Use a single left click in the drawing area to select a coordinate and hold and drag release to another coordinate to define the line segment. The line segment can be re-sized either from its information panel or using the sizing handles from its `active area'. Drag dropping a line segment to another location in the drawing is also possible.

----------------------------------

.. figure:: graphics/line_tool_info.png
  :width: 800px
  :height: 400px
  :align: center
  :alt: line tool in QElectroTech
**Fig.--- Line tool and information:**
The line segment information is shown here in \figurename~{9}. The line segment geometry can be defined by a start coordinate and ending coordinate. The default end style is `normal'; options to set this style to `simple arrow', `triangle arrow', `circle arrow' and `diamond arrow' are available. End 1 is the initial point from where the line segment is drawn and End 2 is the ending point of the line segment. Triangle, circle and diamond arrow spaces can be filled with a color using the `Filling' combo box. The line segment can be colored `white', `red', `green' and `blue' apart from default red color. The line style can have `normal', `dashed', `dotted' or `dashed \& dotted' styles. The thickness of the line segment can be defined from the `weight' combo box. A slanted line can have rough outline which can be smoothed by selecting the `anti-aliasing' option.
 
-------------------------------------

9.2.9.b Rectangle tool:
>>>>>>>>>>>>>>>>>>>>>>>

Select `Add a rectangle' icon with a left mouse click from the drawing bar to activate it. Use a left mouse click to select a point in the drawing area and hold and drag to another coordinate and release the click to complete a rectangle. The geometry can be re-sized from its information panel or by using the resizing handles from its `active area'. Drag dropping the rectangle to another position in the drawing area is also possible. 

---------------------------------

.. figure:: graphics/rectangle_tool_info.png
  :width: 800px
  :height: 400px
  :align: center
  :alt: Rectangle tool in QElectroTech
            
**Fig.--- Rectangle tool and information:**
The Rectangle tool permits drawing of rectangular geometric sketches in the element editor. Some of the formatting that can be done from the information window to a rectangle is shown in the Fig.. The geometry is defined by a point and the size of the rectangle (length and breadth). The appearance options are the same as available for line tool.

--------------------------------

9.2.9.c Terminal tool:
>>>>>>>>>>>>>>>>>>>>>>

 Terminals have to be provided for the element to integrate it in a circuit. The element editor will not save a drawing without at least one terminal. Terminals can be drawn from the short red-blue line icon provided in the drawing bar. It is described in the \figurename~{11}. Left mouse click on the `Add a terminal tool' from the drawing bar to activate it and left click on a point in the drawing area where you want to place this terminal. Once added it can be selected and drag dropped to a suitable location.

---------------------------------------

.. figure:: graphics/terminal_tool_info.png
  :width: 800px
  :height: 400px
  :align: center
  :alt: Terminal tool in QElectroTech

**Terminal tool and information:** 
Terminal is a not a simple drawing tool like `line' or `circle'. It is a tool which gives an element a scope to be connected to other elements in a circuit. Terminal is mandatory for each element, more terminals can be provided depending on the type of element being drawn. It appears as a line in two distinct colors `blue' and `red'. It has fixed dimensions and cannot be changed. It has a special directional property by way of `North', `South', `East' and `West', which can be changed from the information panel, when the terminal is the `active area'. This direction is determined by the blue end of the terminal; in the direction that it points. It is described in the working area by a single coordinate, the point where it is added. The red end of the terminal joins to the element geometry. The terminal gives an element a dynamic property in QElectroTech. When you point cursor to an element terminal after it is added in a drawing, the blue end turns to a big blue dot, indicating its intention to be connected to a point in the circuit.

--------------------------------

9.2.9.d Ellipse tool: 
>>>>>>>>>>>>>>>>>>>>>>

Select the `Add an ellipse' icon from the drawing bar to activate it. Use a left mouse click in the drawing area to select a point and hold and drag to another coordinate and release the click to form a geometry. You can re-size the geometry developed to your desired intention either by using re-sizing handles of its `active area' or using its information panel. Drag dropping of the geometry to a desired position after selecting it is possible.

-----------------------------

.. figure:: graphics/ellipse_tool_info.png
  :width: 800px
  :height: 400px
  :align: center
  :alt: Ellipse tool in QElectroTech

**Ellipse tool and information:**
Ellipse tool permits drawing ellipses and circles in the drawing editor. The geometry of an ellipse is defined by point coordinate and its horizontal and vertical diameters. Standard line formatting and styles are possible with ellipse tool. Some of them are illustrated in the \figurename~{12}. Anti-Aliasing is a default option with ellipse tool, which makes its appearance smooth. This option is deselected for some of the illustrations shown in \figurename~{12}.

------------------------------

9.2.9.e Polygon tool:
>>>>>>>>>>>>>>>>>>>>>

Select the `Add a polygon' icon with a left mouse click to activate the tool. With the tool activated, use left mouse clicks to select a number of points that define your geometry in the `drawing area'. To finalize the geometry, use a right mouse click. You can re-size the geometry using the handles of its `active area' or from its information panel. 

-------------------------------------

.. figure:: graphics/polygon_tool_info.png
  :width: 800px
  :height: 400px
  :align: center
  :alt: Polygon tool in QElectroTech

**Ellipse tool and information:**
`Add a polygon' tool is essentially a utility tool, which permits creation of varied geometry. It is a handy tool for creative users trying to create complicated symbols. Some samples are drawn in \figurename~{13} to display some of its abilities. The geometry of a polygon is defined by a set of coordinates, which are created by left mouse clicks in the drawing area. The appearance properties are same as that of a line tool. There is an additional option for polygon tool in the information panel, a `Closed polygon' selection button. If the button is selected with a sketch as `active area' drawn with the polygon tool, a closed geometry is developed. This action permits further formatting by the `Filling' combo box in the appearance section of the information panel. Only the closed polygons accept filling with colors.

------------------------------------

9.2.9.f Arc tool:
>>>>>>>>>>>>>>>>>

Select the `Add an arc' icon with a left mouse click to activate the tool in the drawing bar. With the tool activated, use left mouse click to select a point in the `drawing area' and hold and drag to a new position and release the click. The new point can be described at a distance of horizontal diameter along x-axis and a vertical diameter distance along y-axis from the initial point.  You can re-size the geometry using the handles of its `active area' or from its information panel. Arc tool also has anti-aliasing as its default option for smoothness.

-------------------------------------

.. figure:: graphics/arc_tool_info.png
  :width: 800px
  :height: 400px
  :align: center
  :alt: Polygon tool in QElectroTech

**Arc tool and information:**
The `Add arc' tool permits creation of an arc along a circle's circumference or in an elliptical path. Some samples using arc tool are drawn in \figurename~{14}. The geometry of an arc created by this tool is defined by a coordinate, which is the initial point selected by a left mouse click in the drawing area, a horizontal diameter and a vertical diameter defined as distances along x and y axes from its initial point, a start angle and an arc angle. Start angle is the angle from the `North' line and arc angle is the total angle that the arc subtends at the center of the circle or an ellipse to which it belongs. The appearance properties are same as that of a line tool. The arc can be re-sized either from the handles of its `active area' or from the information panel. Drag and drop functions are possible and are similar to those described earlier for other tools.

-----------------------------------

9.2.9.g Add text: 
>>>>>>>>>>>>>>>>>>

Select the `Add text' icon with a left mouse click to activate the tool in the drawing bar. With the tool activated, use left mouse click to select a point in the `drawing area'. A text box with default font size and orientation appears at the point selected. You can re-size the geometry using the handles of its `active area' or from its information panel. The add text field is used to label the element and its components. The text added with this tool cannot be edited while using the element in QElectroTech drawings.

------------------------------

.. figure:: graphics/text_tool_info.png
  :width: 800px
  :height: 400px
  :align: center
  :alt: Polygon tool in QElectroTech

**Text tool and information:**
`Add text' tool permits fixed naming of the element and its parts at the time of its drawing. Add text appears as a text box with a default font size and orientation at the point selected. The dimensions of the text box can be altered either from the handles of its `active area' or from the information panel. Drag and drop functions are possible and are similar to those described earlier for other tools. The information panel describes the text box position by a single point coordinate, font size, color as either `black' or `white', text to display and orientation. Text can be oriented in any direction possible from 0 to 359.99 \textdegree. \figurename~{15} shows the text added to rectangles filled with different colors.

---------------------------------

9.2.9.h Add a text field:
>>>>>>>>>>>>>>>>>>>>>>>>>

Select the `Add a text field' icon with a left mouse click to activate the tool in the drawing bar. With the tool activated, use left mouse click to select a point in the `drawing area'. A text box with default font size and orientation appears at the point selected. You can re-size the geometry using the handles of its `active area' or from its information panel. The add text field is used to label the element and its components. A default `\_' is added to this text field to give an indication of the location of the field when the element is added in a QElectroTech drawing. This field accepts the users input in the QElectroTech drawing.

--------------------------------

.. figure:: graphics/text_field_info.png
  :width: 800px
  :height: 400px
  :align: center
  :alt: Polygon tool in QElectroTech

**Text field and information:**
Often `Add a text field' tool is associated with elements or their parts at the time of its drawing. The text field appears as a text box with a default font size and orientation at the point selected. The dimensions of the text box can be altered either from the handles of its `active area' or from the information panel. Drag and drop functions are possible and are similar to those described earlier for other tools. The information panel describes the text box position by a single point coordinate, font size, default text as `\_' and orientation of 0\textdegree. Add a text field can be oriented in any direction possible from 0 to 359.99 \textdegree. The \figurename~{16} shows the Add a text field. This tool has an additional selection box named `Do not follow parent element rotations'. If this check box is selected, the field does not rotate even if the element to which it is associated is rotated in the QElectroTech drawing.

----------------------------------

.. _Section10:

10. Sample tutorial - Creating a Globe Valve Element
====================================================

The tutorial here explains the creation of a globe valve element. You may click on the animated graphic to zoom to understand the sequence of steps followed to create and import elements in diagrams. The graphic is provided with text to offer guidance to each action required in the stage.

.. _Figuuuuu: 
.. figure:: graphics/valve_elmt.gif
  :width: 800px
  :height: 400px
  :align: center
  :alt: Globe Valve tutorial in QElectroTech

**Steps for creating and importing elements in QElectroTech** (Right click the image and select view image to watch the animation in full screen)


11 Title block template editor
===============================

QElectroTech comes with five different templates to work with, namely - `A4\_1', `default', `DIN\_A4', `double-logo' and `single logo'. QElectroTech also permits custom template designing with user defined title block. In this section an introduction to the title block editor is presented. Also, a tutorial to design a referenced title block is included, to familiarize users with the behavior of the title block editor.

11.1 Opening title block editor
-------------------------------



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
