# Horn-and-shunk-optical-flow
# Brightness Constancy Assumption
Idea of computing the motion between two frames  and it is a classical Optical Flow estimation algorithm.  In this proposed method, important assumption made in this algorithm are that there isn’t any significant change in the lighting between two consecutive frames, calling it the Brightness Constancy Assumption. This means that if the object in the image moves or say, the camera moves, then, the colours of that object will remain the same, regardless of the lighting.
Shortcoming involve With only Brightness Constancy Assumption is that we are only able to measure the component of optical flow that is in the direction of the gradient intensity. On the other hand, we are unable to measure the component perpendicular to the gradient intensity.
# The Smoothness Constraint Assumption
It says if we consider a particular neighborhood within the image, we will notice that all pixels in that neighborhood move in the same direction. Therefore, pixels of a neighborhood which are next to each other have very similar optical flow vectors as well.
