# MRCCameraCalibrationApp
This is a reverse-engineered and improved version of Oculus MRC Camera Calibration App (com.oculus.MrcCameraCalibration)

It is aimed to be compatible both with [Oculus PC MRC app](https://developer.oculus.com/downloads/package/mixed-reality-capture-tools/) and [Reality Mixer](https://github.com/fabio914/RealityMixer) and maybe other Mixed Reality applications.

# IMPORTANT UPDATE
As of April 2024, the app no longer can save mrc.xml and I'm once again figuring out a workaround.

# WORK IN PROGRESS

What is done:
- Ported on newer Unity Engine (2022.3.2f1)
- Added controllers display
- Added passthrough mode for convinience (works best on Quest Pro and upcoming Quest 3)
- Fixed issues with failing `mrc.xml` not saving in other game folders

Current Issues:
- Folder selection window for granting permissions may not work correctly, see [this video](https://www.youtube.com/watch?v=wIoor8jwg9w)
- You will need to put headset into Stand-by and back to Active again (using Power button) after granting folder permission

Future:
- Some UI for managing the games permissions we want to calibrate for
