# northgard-camera-move

A simple RTS camera move system made in Godot Engine 3.4 imitating to the Northgard game.
<br>
```diff
+ Recent version V.0.9.5 with new features and fixes applied.
- You does can reset the Commit to 93dfcc.. (for to get previous version).
```
Available plug-in for GDScript programming language <a href='https://github.com/dibertz/northgard-camera-move-plugin-for-godot' target='_blank'>northgard-camera-move-plugin-for-godot</a>

<h2>Intrduction:</h2>

JRPG-camera-move-v.0.9 it's a tool designed for to RTS Games and RPGs.

<h2>What it does:</h2>
<p>
 Move Camera with Mouse in Godot 3D, fading in and in-out smoothing, customizable parameters, keyboard camera control, player tracking camera, zoom in-out. Displacement across x, y, z and diagonal. Kinematic Character move interactive.
</p>
<p>
 <a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/FH3t3XPv/Mouse-Camera-gif-maker.gif' border='0' alt='Mouse-Camera-gif-maker'/></a>
</p>
<br>
<p>
 Key "Y" for to block or free-view Camera.
 
 --------------------------------------
 
 <b>Free-View Cam: First gif image
  
  Block-View Cam: Second gif image</b>
 
  --------------------------------------
 
</p>
<br>
<p>
 Keys "A", "W", "D", "S" for to move character and tracking with camera smoothing.
</p>
<p>
 <a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/kMzXvfgJ/smoothing-Camera-gif-maker.gif' border='0' alt='smoothing-Camera-gif-maker'/></a>
</p>
<br>
<p>
 Mouse wheel scrolling + or - for to Zoom in-out Camera. Even you can scrollable and zoom.
</p>
<p>
 <a href='https://postimages.org/' target='_blank'><img src='https://i.postimg.cc/d33Rcv7T/zoom-Camera-gif-maker.gif' border='0' alt='zoom-Camera-gif-maker'/></a>
</p>
<br>
<h2>Operative systems compatibility:</h2>

MacOS

Linux

Windows

<h2>Requeriments:</h2>

Godot_v3.4.2-stable_mono_win64 (Mono Version).

Visual Studio Code IDE or Similar.

GLES3 (GPU Driver Compatibility OpenGL 3.3).

<h2>Get Started:</h2>

Copy or clone repository inside of ➤ C:\Users\YourName\Documents\JRPG Camera Move v.0.9


<b>Load IDE editor and download the next dependencies:</b>

------------------------------------------
> C# v1.24.0 Microsoft
------------------------------------------
> Mono Debug v0.16.2 Microsoft
------------------------------------------
> C# Tools for Godot v0.2.1 Ignacio Roldán Etcheverry
------------------------------------------


<h3>Setup JSON File:</h3>

1. Open the Command Palette (Ctrl + P).

2. Select C# Godot: Select Project.


<h3>Start Project:</h2>

1. Run Godot C#.
2. Import file project.godot in the folder JRPG Camera Move v.0.9.
3. (Optional) Change (Camera.cs) the Bool variable False to ➤ RPGCamera = true;
4. Save changes IDE and Godot Engine.
5. On Godot click Build.
6. Run the Game.

<h2>Contributing</h2>
Contributions to the development and enahancement of JRPG/RTS data is welcome. Please see <a href="https://github.com/dibertz/northgard-camera-move/blob/main/CONTRIBUTING.md">CONTRIBUTING.md</a> for contribution guidelines.

<h2>FAQ:</h2>

If you have any questions or doubts comment in the description into below.

1. <b>How to set up the parameters and settings?</b>
<br>Into Godot editor click node Camera, script variables it can be changed.
2. <b>What is size map clamped it?</b>
<br>Higher values than the default value means a symmetric larger map. It should keep the same dimensions on both sides to avoid clamping critical errors.
3. <b>How to does put my 3D character model without watch for the ugly cube?</b>
<br>It's super easy, click on node Mesh Instance (Player/Pivot/MeshInstance) and REMOVE, so replace it for your own. 
<br>Set up to Scale X: 0.1, Y: 0.1, Z: 0.1 and Traslation X: 0.0, Y: 0.1, Z: 0.0. That's it.

Do you want more features?, check it out repositories weekly.


<h2>Licensed Under MIT</h2>

<a href='https://www.paypal.com/donate/?hosted_button_id=EWDLXT7WUVYZ2' target='_blank'><img src='https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif' border='0' alt='Donate with PayPal button'/></a>


Enjoy it!

