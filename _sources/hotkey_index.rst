.. _hotkey_index:

===============
Hotkey Index
===============

   Besides using the mouse to interact with options such as menu bar, tool bar, and widgets (Burst ID slider bar, Peak ID spin box), the curation GUI also provides with hotkeys for faster curation. The following is a list of hotkeys that can be used in the curation GUI.

- Hotkeys for main window widgets

    - Q: Move to previous spike peak/decrease Peak ID.
       - Same as clicking the down arrow button on the Peak ID spin box.
    - W: Move to next spike peak/increase Peak ID.
       - Same as clicking the up arrow button on the Peak ID spin box.
    - G: Go to previous burst event/decrease Burst ID.
       - Same as slide the Burst Slider towards left.
    - H: Go to next burst event/increase Burst ID.
       - Same as move the Burst Slider towards right.
    - J: For *Show Help* checkbox in the bottom left corner of the main window.
       - Same as *Show Curation Assistant*
    - K: For *Show Burst* checkbox in the bottom right corner of the main window.
       - Same as *Display/Hide figure of current marked burst*   
       
- Hotkeys for menu bar 

    - 1: Load `unsorted Data`
    - 2: Load `Sorted Data`
    - 3: `Load Sample` 
    - T: Get a list of bursts candidates.    
    - L: Check bursts to see whether there are duplicate indexes.
    - P: Delete the duplicate burst events.
    - O: Reassign spike cluster ID
       - This is a critical step before saving results.
    - V: Save curated bursts
       - Curation results will be saved in the user defined directory or current working directory if the pre-defined directory can not be found.
    - U: Load next unsorted data
       - Same as open `unsorted data`.
    - I and J: Show Curation Assistant
       - A clock dockwidget will show up. This widget can be closed or hide, and revoke either using 'I' or 'Show Curation Asistant' option.
       - When this widget is visible, key 'J' can be used to show/hide a new window that contains 'Curation History' and 'Duplicate Index' panels.    


- Hotkeys for toolbar options



    - A: Add spikes with square labels.
       - A standard curation process is to first add spikes with square labels, then move to selected peaks to add the rest labelled spikes.
    - S: Add spike with star label.
       - These are the spike peaks that are not in the burst candidate list but are still likely to be bursting spikes. These spikes will be added to the burst when the burst is marked.
    - D: Delete the selected spike peak.
       - This will delete any selected spike peak.
    - M: Mark the current burst
       - User can mark the burst mutiple time despite warning sound.
    - K: Display/Hide figure of current marked burst
       - Only added spikes will be color coded in the figure.
    - C: Save figure of marked burst
       - The figure will be saved in the user defined directory or current working directory if the pre-defined directory can not be found.    
    - B: Add the current burst
       - User can invoke  'Show Curation Asistant' window, find 'Curation History' panel to see the current burst candidate list.
    - R: Cancel the current burst 
       - All the curation results of the current burst including keybaord/mouse inputs by program will be cleared.

.. warning::
      A warning sound will be played if any of these hotkey is clicked more than once for a same burst candidate.

      
- Other keybaord shortcuts

    - Y: Mute/Unmute curation GUI sound
       - User can mute/unmute the curation GUI sound without affecting the system sound setting.
    - Z: Take screenshots of curation GUI
       - Screenshots will be saved in the user defined directory or current working directory if the pre-defined directory can not be found.
    - Esc: Exit curation GUI
         - A confirmation dialog will pop up to ask user whether to exit the curation GUI. 