This is Repository for integration of TIP 282 changes in the expr shorthand, plus a minus add to allow barword variable on left side of the assign operator.
It will allow you to write :
        set L [(x=1; ($x, $x*2, $x*3))]
        # which returns {1 2 3}
