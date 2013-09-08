cmd
===

Miscellaneous command line utilities that I have on my local `PATH`. Right now, I just have these two:

cycle

    # Creates a circular pipe 
    $ cycle 'cmdA | cmdB | cmdC'
    # runs with cmdC output piped back into cmdA. 

cdrun

    # Temporarily change folder to run a script  
    ~/path/deep/inside/project $ cdrun /bin/pwd 
    /bin
    ~/path/deep/inside/project $
    # Working directory unchanged
