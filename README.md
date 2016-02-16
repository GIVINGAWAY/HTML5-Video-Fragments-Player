# HTML5-Video-Fragments-Player

Description

This project is designed to demonstrate not commonly used web technologies with attention to software architecture​.

Features:

Application that allows a user to slice­up a video into clips.

As part of this application, the following framework was used to facilitate

development:

● AngularJS

Mandatory Features

● An HTML5 video player that utilizes media fragments - ✓ Done

● A list of clips to be played in the video player - ✓ Done

● The first item in the list should be the full video - ✓ Done

● An interface to add new clips to the list by specifying a name, start time, and end time - ✓ Done

● The ability to delete clips from the list (excluding the full video item​) - ✓ Done

● The ability to edit existing clips in the list - ✓ Done

● The ability to play clips in the video player - ✓ Done

Bonus (Optional)

● The ability to automatically jump to the next clip after it finishes, with a 3 second waiting

period and appropriate loading animation. - ✓ Done (functionality extended: 
      ● on each jump 5 seconds roll back added to allow user feel that nothing is missed;
      ● loading animation moved out of the screen not to bother vewer
      ● both name of the fragment and state added to it )

● The ability to ‘save’ clips for persistent use. - ✓ Done (with $watch servise on each change of the $scope all data are saved to cockies)

● The ability to add arbitrary ‘tags’ to clips so that they can be filtered by the tag name. - ✓ Done

● Hotkeys to jump between the current clip and next and previous clips (if there are any) - ✓ Done (next to the Play Full Video option)

● Markers on the video player timeline that denote where a clip starts (full video only). - ✓ Done (extended:
      ● custom made timeline
      ● full control by custom made controls
      ● ability to jump to another fragment by clicking on it
      ● ability to see overlapping fragments clearly
      ● ability to see the name of fragments during the play mode)

Clicking the marker chooses that clip and plays it from that point. - ✓ Done

● The ability to reuse the the player and playlist on another page without the editing

capabilities - ✓ Done (done via cookies, can be done with routing)

● Project has been uploaded to Github - ✓ Done

● Repository has been shared - ✓ Done

● Completed bonus tasks have been indicated. - ✓ Done
