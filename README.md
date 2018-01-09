# Subseeker
Automatic Subtitle Downloading Tool for Nautilus in Ubuntu.
Use opensubtitles.org's XMLRPC api to query and download subtitles.

It's frontend is basically a Nautilus-Action Config , that gives a submenu option to download subtilies.

Backend is a small python script that genrates the video files hash and does a query to the opensubtitles api.

<b>The Default Environment Must be Python2 or Cpython2 for it to work as, the hasing function isn't compatible with python3.</b>

If any Subtitle is there related with the video hash , it downloads it automatically and places the subtitle in the same folder as the video.

As if now , it only downloads English subtitles but language support will be added in coming versions.


</hr></br>
<b>Dependencies are:</b>

<li>Nautilus Action Config Tool </li>
<b>Note:</b><i> You'll be automatically asked to install it at the time of installation of Subseeker. </i>
</br>

</br></hr>
<b>Size Information:</b>
<li>Total size including Nautilus Action Config Tool: ~ 13 MegaBytes</li>
<li>Total size excluding Nautilus Action Config Tool: ~ 30 KiloBytes </li>
</br>
</br>
<b> Installation Procedure: </b>
<ol type="i">
<li> You must have an Opensubtitles Account to use this app.</li>

<li> Follow : <i>"https://www.opensubtitles.org/en/newuser"</i>   , to register.</li>

<li> Download or clone the Archived Package to your home folder.</li>

<li> Extract the tar ball (Compressed Archive) to **Home folder** .</li>

<li> Navigate to subseeker folder.</li>

<li> In explorer (File manager window of subseeker folder) , right click and select 'Open in Terminal'.</li>

<li> In the terminal Window type: 'sudo python3 Install.py'. (Without Quotes)</li>

<li> Enter 'y' if asked to install Dependencies.(external utility packages.)</li>

<li> A login text shows , Enter your opensubtitle username and password there.</li>

<li> Once the Partial installation complete , a new readme will open with futher instructions.</li> </ol>

</hr></br>
<b> Usage Instructions: </b> </hr></br></hr></br>
Just Navigate to any Video and Right Click , You'll See a "Get Subtitle" (Shown In Image Below) Option in the Submenu. 
</br></hr></br></hr>

![Image Showing Submenu Option "Get Subtitles" in Nautils.](/Screenshots/Nautilus_Submenu_Option.png "Image Showing Submenu Option 'Get Subtitles' in Nautils.")

</br></hr></br></hr>
After Clicking the submenu Option a new Confirmational window will appear and You'll see the subtitles Appear in the Folder.(Shown in Image Below)
</br></hr><b>Note:</b><i></br></hr> <ul><li>It takes some time to search and download the Subtitles (2-5 Secs) Depending Upon you computer and Internet Speed.</li><li> The Subtiles will only be Downloaded if they Exists on The Opensubtitles Website. </li></ul>

![Image Showing Downloaded Subtitle and confirmation window in Nautils.](/Screenshots/Downloaded_File_With_confirmation.png "Image Showing Downloaded Subtitle and confirmation window in Nautils.")
