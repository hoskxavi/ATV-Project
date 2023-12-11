ATV Project

Repository containing any needed information regarding the Fall 2023 ATV project for the Robotics and Communications Systems Engineering Technology program at Idaho State University.

Application Information:
  The included Android APK file titled "ATV_Control.APK" is a basic control application for the ATV drive system. 

  Initial Setup:
    To setup the control app, the APK file must be downloaded on any Android device(NOTE: The app is NOT compatible with IOS devices.)
    The device settings must be set to allow for downloading third party applications in settings, usually in the security submenu.
    Once downloaded, the file must be found in the file manager app. Tapping on the file will allow installing the application.
    Once the app is installed, it must be granted permissions to "Nearby Devices" in the device settings.
    The device must be paired with the bluetooth module. It can be found in the available devices under the name "RCET_ATV".
    If requested, the pairing pin is 1234.
    
  Using the Application:
    Once opened, a button at the top allows for connecting to the ATV's bluetooth. Once tapped, a list of paired bluetooth devices will appear and the "RCET_ATV"         device can be selected.
    Once connected, the app will indicate with a label and an indicator. 
    The orange ball is the joystick. Drive controls are intuitive: dragging the ball up moves forward, down moves backward, left turns left, and right turns right.
    A "Mode" button is also available. The default is joystick mode, where the user drags the joystick for control. Tapping the "Mode" button will toggle to              gyroscope mode, where the user can tilt the phone for control. Tapping the "Mode" button again will return to joystick mode.
