## Last Updated: 2024-05-26
# EVOS™ M7000 Imaging System Quick Start and Shutdown Guide

## Quick Start Guide

### 1. Turn on the EVOS™ M7000 Imaging System
- <span style="color: red;">&#9888; **Caution:** Ensure the objective is set to the smallest magnification (4X) to avoid damage to the microscope.</span>
- **Step 1:** Turn the instrument power switch located at the back of the instrument base to the ON position.
- **Step 2:** Turn the computer and monitor ON.
- **Step 3:** When the computer shows the Windows™ desktop and the X-Y stage has stopped moving, click the M7000 icon to start the EVOS™ M7000 software.
- **Step 4:** The Capture tab will be displayed, indicating that the system is ready to use.

### 2. Select Sample Vessel
- **Step 1:** Place the vessel containing your sample on the stage using the appropriate vessel holder.
- **Step 2:** On the Capture tab, click the Vessel button to open the Vessel Selection dialog.
- **Step 3:** Select the Vessel category that corresponds to your sample vessel, then select the Holder and Vessel type from the dropdown menus.
- **Step 4:** Click Done to complete your selection and close the dialog. The Vessel map on the Capture tab will display your selected vessel.

### 3. Select Objective and Light Source
- **Step 1:** Click the desired Objective button to select the corresponding magnification.
- **Step 2:** Select the desired Light source for which you wish to adjust brightness and set focus.

### 4. Set Brightness and Camera Options
- **Step 1:** Click the Brightness and camera settings button to expand the controls for setting mode, camera, and phase options.
- **Step 2:** For Mode, select Simple or Actual.
  - **Simple mode:** Controls Brightness as a single parameter.
  - **Actual mode:** Allows adjustment of Light (LED intensity), Exposure, and Gain individually.
- **Step 3:** For Camera, select Mono (monochrome) or Color.
  - **Mono:** Used for image capture in fluorescence and transmitted light (brightfield) channels.
  - **Color:** Used for image capture in the brightfield channel only.
- **Step 4:** Click the Brightness and camera settings button again to collapse the controls.

### 5. Adjust Brightness
- **Step 1:** Click the Light button to turn on the excitation light for the selected light source and enter the instrument in Live mode.
- **Step 2:** Adjust brightness using the Brightness controls.
  - **Note:** Optimize the brightness parameters as follows:
    - When searching for sample: Increase Gain and decrease Exposure.
    - When capturing image: Decrease Gain and increase Exposure.
    - For brighter signal: Increase Light intensity and, if needed, follow by increasing Gain.
    - For time-lapse imaging: Increase Gain and Exposure, and decrease Light intensity to reduce photobleaching and phototoxicity.

### 6. Set Image Display Options
- **Step 1:** Choose the channels you wish to display in the Viewing Area by selecting the appropriate channel checkbox on the corresponding Light source button.
- **Step 2:** Click the Image Display settings button to expand the image display controls for the selected channels.
- **Step 3:** Adjust the Brightness, Contrast, and Gamma settings for each of the selected channels using the corresponding sliders.
- **Step 4:** Click the Image Display settings button again to collapse the controls.

### 7. Focus on the Sample
- **Step 1:** Click Autofocus to run the autofocus procedure to find the best focal plane for the current channel and sample.
- **Step 2:** Alternatively, use the Coarse and Fine focus sliders to manually find the best focal position.

### 8. Optional: Set Z-Offsets
- **Step 1:** Verify that the Lock Z-Offsets option is checked in the Advanced focus settings window, then click the Advanced focus settings button again to close the window.
- **Step 2:** Select the Objective and the Light source (i.e., channel) you wish to capture.
- **Step 3:** Click the Light button to enter the Live mode, and focus on the sample manually using the Coarse and Fine focus sliders or automatically by clicking the AutoFocus button.
- **Step 4:** Repeat this procedure for every channel you wish to capture.
- **Step 5:** When you have found the optimal focus position in all the additional channels you wish to capture, click the Advanced focus settings button, then check the Lock Z-Offsets option.

### 9. Find the Region of Interest in the Live Mode
- **Step 1:** While in Field View, click the Light button and enter the instrument in the Live mode.
- **Step 2:** To go to a specific location on the sample vessel, click and drag the crosshair to the corresponding location on the virtual vessel.
- **Step 3:** While in the Live mode, use the Jog Control to move the stage at an intermediate pace to the desired location as you view the sample until you find the field of view you wish to capture.
- **Step 4:** Click the Light button again to exit the Live mode in Field View.

### 10. Select Field and Capture Images
- **Step 1:** In Area View, position the capture crosshair over the region of interest and click to select the field you wish to capture.
- **Step 2:** Click Capture to acquire an image of the selected field using the current capture settings.
- **Step 3:** To capture the same field in another channel, select the desired channel using the corresponding Light source button, readjust the brightness and focus if needed, then click Capture.

## Shutdown Guide

### 1. Save Captured Images
- **Step 1:** When finished capturing images, click Save… to open the Save window.
- **Step 2:** Select the captured fields you wish to save.
- **Step 3:** Click Browse, navigate to the desired folder, then click Select. To create a new folder, navigate to the desired location, click New, type in the name of the newly created folder, then click Select.
- **Step 4:** If desired, type the prefix you wish to use for your saved images in the File name prefix textbox.
- **Step 5:** Select File types to save by checking the corresponding checkboxes. You can choose multiple file types for your captured images.

| File Type          | Description                                                                         | Options                                       |
|--------------------|-------------------------------------------------------------------------------------|-----------------------------------------------|
| **Raw images**     | Saves images captured in different channels individually as 16-bit raw images.      | TIF, PNG, C01, DIB                            |
| **Displayed images**| Saves images in a format that can be viewed in most image display applications.     | TIF, PNG, JPEG                                |
|                    | - Single field, individual channels: Saves images captured in each field and each channel individually. | |
|                    | - Merged image: Saves the images of a field captured in different channels as a multi-channel overlay. | |
|                    | - Tiled image, merged channels: Merges the images captured in each channel, then aligns them close together into a tiled format. | Small (2000 × 2000 pixels), Medium (4000 × 4000 pixels), Large (10,000 × 10,000 pixels), Maximum (26,000 × 26,000 pixels) |
| **Color options**  |                                                                                     | Grayscale (16-bit), Pseudocolor (24-bit RGB)  |
| **Brightness options**|                                                                                  | High (limits pixel depth), Full (more detail) |
| **Include Grid**   | Superimposes a grid on the displayed images.                                         | Auto, 10 × 10, 50 × 50, 100 × 100, 200 × 200, 500 × 500 pixels |

- **Step 6:** After selecting save options for your captured images, click Save.

### 2. Turn off the EVOS™ M7000 Imaging System
- <span style="color: red;">&#9888; **Caution:** Ensure the objective is set to the smallest magnification (4X) before turning off the microscope to avoid damage.</span>
- **Step 1:** Exit the EVOS™ M7000 software.
- **Step 2:** Turn off the computer and monitor.
- **Step 3:** Turn the instrument power switch at the back of the instrument base to the OFF position.
