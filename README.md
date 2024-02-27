`<br>from js import robot`<br>
<br>`import random`<br>
<br><br>
<br>`while robot.is_ok():`<br>
<br>`    if not robot.wall_left():`<br>
<br>`        robot.turn_left()`<br>
<br>`        robot.move_forward()`<br>
<br>`    elif not robot.wall_front():`<br>
<br>`        robot.move_forward()`<br>
<br>`    elif robot.wall_left() and robot.wall_front():`<br>
<br>`        robot.turn_right()`<br>
