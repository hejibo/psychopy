.. _sound:

Sound Component
-------------------------------

Parameters
~~~~~~~~~~~~

name : string
    Everything in a PsychoPy experiment needs a unique name. The name should contain only letters, numbers and underscores (no puncuation marks or spaces).
    
start : float or integer
    The time that the stimulus should first play. See :ref:`startStop` for details.

stop : 
    For sounds loaded from a file leave this blank and then give the `Expected duration` below for 
    visualisation purposes. See :ref:`startStop` for details.
    
sound : 
    This sound can be described in a variety of ways:
      
      * a number can specify the frequency in Hz (e.g. 440)
      * a letter gives a note name (e.g. "C") and sharp or flat can also be added (e.g. "Csh" "Bf")
      * a filename, which can be a relative or absolute path (mid, wav, ogg and mp3 are supported).


.. seealso::
	
	API reference for :class:`~psychopy.sound.Sound`