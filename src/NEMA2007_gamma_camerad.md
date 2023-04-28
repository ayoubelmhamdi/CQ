# NEMA Standards Publication NU 1-2007 Performance Measurements of Gamma Cameras

## Section 1: References, Definitions, and Test Equipment

### References
- A list of references applicable to the standards.

### Test Equipment, Conditions, and Results
- Describes the test equipment and conditions needed to perform the gamma camera measurements.
- 10% dimensional tolerance is required for all source holders.
- Tc-99m and Co-57 radionuclides are used, while other radionuclides can be used if reported.
- Test measurements must meet or exceed manufacturer's specification unless "typical" performance is stated.
- Reporting includes measurement results and radionuclide used.

## Section 2: Tests of Gamma Camera Detectors

### Intrinsic Spatial Resolution
- Describes the measurement of intrinsic spatial resolution for gamma camera detectors.
- Intrinsic spatial resolution must meet or exceed specification for discrete pixel cameras.
- The test conditions require the use of Tc-99m radionuclide with appropriate shielding.
- The measurement procedure involves using a lead mask with parallel slits, with digital and channel width requirements.
- Calculations and analysis includes measuring FWHM and FWTM.
- Reporting requires reporting calculated average FWHM and FWTM values for both the UFOV and the CFOV, and the radionuclide used.
# Intrinsic Spatial Linearity
Intrinsic spatial differential and absolute linearity need to meet or exceed the specifications. Differential linearity needs to be expressed in millimeters as the standard deviation of the measured peak locations from a best-fit line. Absolute linearity needs to be expressed as the maximum displacement of any peak from the best fit of a two-dimensional grid. Note that for discrete pixel cameras, intrinsic spatial linearity as defined for single crystal cameras is not analogous, nor directly applicable.

## Test Conditions
The radionuclide employed in the test needs to be Tc-99m. A source holder, which shields the source from walls, ceilings, and personnel without restricting the photon flux from the source to the camera, shall be employed. One or more copper plates may be used to adjust the count rate. The energy window for Tc-99m needs to be recommended by the manufacturer for the appropriate clinical mode. The count rate should not exceed 20,000 cps through the energy window. If other radionuclides are used, the energy window should be set according to the manufacturer's recommendations.

## Test Equipment
The test pattern shall consist of a lead mask in closest possible proximity to the crystal covering the entire useful field of view (UFOV) with 1-millimeter-wide parallel slits. The adjacent slit centers shall be 30 mm apart from one another. The thickness of the mask shall be 3 millimeters for Tc-99m or Co-57.

## Measurement Procedure
The lead mask with the parallel slits shall be positioned on the detector with the center slit centered on the detector. The center slit shall be perpendicular to the axis of measurement and aligned so that the end of the central slit is positioned to within a millimeter at the edge of the UFOV. The radionuclide shall be a point source centered at least five times the largest linear dimension of the UFOV above the center of the lead mask with the parallel slits. The data shall be integrated parallel to the direction of the slits to form line-spread functions. At least 1,000 counts shall be collected in the peak channel of each line spread function measurement after integration parallel to the direction of the slits. Two sets of data shall be acquired-one with the slits in the X direction and one in the Y direction.

## Calculations and Analysis
If the data is acquired in a two-dimensional matrix, the data shall be summed parallel to the direction of the slits to form line spread functions of width 30 mm or less. The distances between the peaks in each of the line spread functions shall be determined as the average of the. The value of intrinsic spatial differential linearity shall be calculated as the standard deviation of the locations of the peaks in each slit. The standard deviations for the slits in the X and Y directions shall be averaged together.

Separate values shall be calculated for the UFOV and for the CFOV. Intrinsic spatial absolute linearity shall be determined by fitting a set of equally spaced parallel lines to the data using a least-squares minimization technique. Different sets of lines shall be fitted to the UFOV and to the CFOV data. There shall also be a separate set of lines fitted for data acquired with the slits in the X and in the Y directions. The maximum displacement for each set shall be the largest difference between the data and the grid fit in the X or Y direction. The millimeters per channel calibration factor shall be calculated. This factor shall be used to convert the differential linearity and absolute linearity to millimeters.

## Reporting
The intrinsic spatial differential linearity shall be reported for both the UFOV and the CFOV. The values shall be given in millimeters with an accuracy of at least 0.1 mm. The intrinsic spatial absolute linearity shall be reported for both the UFOV and the CFOV. The values shall be given in millimeters with an accuracy of at least 0.1 mm.
# Intrinsic Energy Resolution

This test is used to measure how well a camera can detect different types of radiation. The ratio of the photopeak Full Width Half Maximum (FWHM) to the photopeak center energy is used to express how well the camera can detect radiation. This ratio is expressed as a percentage. This test is used for discrete pixel cameras which have individual detector pixels. The spectra from all the individual detector pixels must be summed after correction for energy, and prior to the calculation of FWHM. The summed spectrum must have 10,000 total counts from all pixels. Systems with a fixed collimator should be uniformly illuminated by a distributed source.

## Test Conditions

The radionuclide used to carry out this test should be Tc-99m. A source holder that shields the source from walls, ceilings and personnel but does not restrict the gamma flux from the source to the camera must be used. At least 2 mm of copper and 3 mm of lead aperture must be used. Count rates should not be greater than 20,000 cps.

## Test Equipment

A digitizer capable of digitizing the energy spectrum with a channel depth of at least 10,000 counts and a digital resolution of less than or equal to 0.05 FWHM of Tc-99m photopeak must be used.

## Measurement Procedure

A Tc-99m point source should be used, centered at a distance greater than five times that of the largest linear dimension of the uniform field of view (UFOV) above the detector. Co-57 should be employed as reference nuclide to determine the keV per channel calibration factor. The spectra from all the pixels in each of the two radionuclides shall be summed after correcting for energy, and prior to the calculation of FWHM. At least 10,000 counts must be acquired in the peak channel of each summed spectrum measurement.

## Calculations and Analysis

The photopeak location should be determined by calculating the average of the linearly interpolated half height channel values calculated for each side of the photopeak. The difference between the two photo peak locations should correspond to $18.4 keV$. The intrinsic energy resolution should be calculated from the Tc-99m stored spectrum. The FWHM in channel numbers should be determined from the linearly interpolated half height channel values calculated for each side of the Tc-99m photopeak. This value should be multiplied by the calibration factor (keV per channel), divided by $140.5 keV$ (which is the Tc-99m photopeak center energy) and then multiplied by $100$ to be expressed as a percentage. Cobalt-57 will be the calibration nuclide if other radionuclides are used.

## Reporting

The calculated intrinsic energy resolution shall be reported and expressed as a percentage. Any other radionuclides employed shall be separately reported. Measurements performed at any higher count rate than 20,000 cps shall also be reported separately.
# Intrinsic Flood Field Uniformity

This test measures the uniformity of a radiation detection system's response to a uniform flux of radiation. The response must be measured for two fields of view (FOV): the central FOV (CFOV) and the uniform FOV (UFOV). This test must be performed for every radionuclide used clinically. The count rate must not exceed 20,000 counts per second (cps) through a photopeak window recommended by the manufacturer for the appropriate clinical mode. The status of uniformity corrections used must be stated in the results.

## Test Conditions

For each radionuclide tested, two different uniformity parameters should be determined: integral uniformity and differential uniformity.

## Test Equipment

The test equipment required for this measurement consists of a source holder, a lead mask for the detector, and a computer or multi-channel analyzer. The source holder consists of a lead shield that prevents back and side scatter but allows the gamma flux from the source to the detector. The lead mask for the detector is a lead plate at least the dimensions of UFOV.

## Measurement Procedure

The detector will be masked using a lead mask described above. The source in the source holder will be placed on the central axis of the detector. The flood field image will be stored in a matrix size that produces pixel sizes with a linear dimension of 6.4 mm±30%. The pixels will be square. A minimum of 10,000 counts will be collected in the center pixel of the image.

## Calculations and Analysis

Before performing the uniformity calculations, the pixels for inclusion will be determined. The flood field image will be smoothed once by convolution with a 9-point filter function of the following weightings:
```
1  2  1
2  4  2
1  2  1
```
The smoothed value will be normalized by dividing by the sum of non-zero weighting factors.

## Integral Uniformity

For each area (CFOV and UFOV) examined, the maximum and minimum smoothed data values are identified. The difference between the maximum and minimum values is divided by the sum of these two values and multiplied by 100. The result represents the integral uniformity of the system.

## Differential Uniformity

The largest difference between any two adjacent pixels in a row or column will be calculated for each area (CFOV and UFOV) examined. The differential uniformity will be expressed as a percentage of the maximum change. The procedure will be repeated until the outermost pixel is reached. The maximum differential uniformity is found in the slice. This process is then repeated for all of the slices.

## Reporting

The results are reported separately for both the CFOV and the UFOV as the percentage integral and differential uniformity for each radionuclide analyzed. In case the system has a fixed collimator, any deviation in the uniformity due to this factor will be reported.
# Multiple Window Spatial Registration

Multiple Window Spatial Registration (MWSR) is a method to measure the camera's ability to position photons accurately that have different energies when imaged through various photopeak energy windows. The measurements are taken at nine specific points on the entrance plane of the gamma camera. This test applies to discrete pixel cameras, and if necessary, adjacent pixels can be summed to obtain an effective pixel size within the range specified in the test conditions below.

## Test Conditions

- Radionuclide: Ga-67.
- Energy window settings: Set as recommended by the manufacturer.
- Count rate: Shall not exceed 10,000 counts per second through each photopeak energy window.

## Test equipment

A lead-lined cylindrical tunnel in the lead with a 5 mm diameter and 25 mm length shall be used to collimate the G a-67 source. The source holder is shown in the figure below.

![image](https://cdn.mathpix.com/cropped/2023_03_05_78eb76b8def9a9233535g-19.jpg?height=617&width=671&top_left_y=1693&top_left_x=247)

## Measurement Procedure

Images shall be taken at nine specific points on the entrance surface of the uncollimated camera using the collimated Ga-67 source described above. These nine points are the central point, four points on the X-axis, and four points on the Y-axis. The off-central points shall be located 0.4 times and 0.8 times the distance from the central point to the edge of the UFOV of the camera along the respective axes. Separate images of the collimated Ga-67 source shall be acquired through different energy windows of the Ga-67 photopeaks at each of these image locations, and the images shall be acquired with a pixel size of up to 2.5 mm. For cameras with two energy windows, two images shall be acquired at each point, one using the 93 keV photopeak, and the other using the 300 keV photopeak. For cameras with three or more energy windows, the 184 keV photopeak shall also be imaged.

## Calculations and Analysis

The displacement of the count centroids from each other in the X and Y directions shall be determined for each measurement point's photopeak images. The maximum difference in the X and Y position of the centroid of counts acquired from each photopeak shall be determined. The largest pixel displacement shall then be converted to millimeters using an accurate millimeter per pixel calibration from Section 2.1.4.

## Method for Centroid of Counts Determination

The center of counts in the X and Y directions for each of the photopeak count profiles shall be determined by calculating the centroid of counts. The maximum difference in the X and Y position of the centroid of counts acquired from each photopeak shall then be determined.

## Reporting

The multiple window spatial registration (MWSR) shall be reported as the maximum difference in spatial positions for different energy windows in either the X or Y direction of the photopeak count centroids for the nine points measured. The values shall be reported in millimeters to the nearest tenth of a millimeter.

![image](https://cdn.mathpix.com/cropped/2023_03_05_78eb76b8def9a9233535g-21.jpg?height=1042&width=668&top_left_y=1124&top_left_x=246)
Figure 2-5: Test results for multiple window spatial registration (MWSR).
# Intrinsic Count Rate Performance in Air
The decay method is used to determine the count rate performance. Two parameters should be measured: observed count rate for $20\%$ count loss and maximum count rate. Both parameters are measured without induced scatter. The curve of observed versus input count rates is provided. This method applies to discrete pixel cameras. The radionuclide employed in this test should be Tc-99m.

## Test Conditions
The energy window for Tc-$99m$ should be that recommended by the manufacturer for the appropriate clinical mode.

## Test Equipment
A camera under test should have the camera crystal masked to the UFOV.

## Measurement Procedure
The background measurement shall be repeated at the end of the measurement for the purposes of background subtraction. The source holder with the source shall be placed in front of the detector so that the collimated cone of radiation is centered within the UFOV. Care must be taken to minimize scatter.

## Calculations and Analysis
Each data point is first corrected for background, then the observed count rate for each data point is determined. The input count rate for each data point is calculated. The observed count rate at $20 \%$ loss is determined by linear interpolation between the two closest points.

## Reporting
Typical values are reported for maximum observed count rate, observed count rate at $20 \%$ loss, and the curve of observed count rate versus the input count rate.

## Technical Note
This test is very time-consuming, taking approximately two days to complete.

# Intrinsic Spatial Resolution at 75,000 Counts per Second
Intrinsic spatial resolution shall be measured at 75,000 counts per second following the procedures and reporting requirements described. Measured values of average FWHM and average FWTM shall be reported. The measured values shall meet or exceed the specification.

For discrete pixel cameras, the spatial resolution of these systems may be characterized using the system spatial resolution measurement described.
## Intrinsic Flood Field Uniformity

The uniformity of the flood field will be measured at 75,000 counts per second. To do this, the Integral and Differential Uniformity of both CFOV and UFOV will be calculated, following the procedures and reporting of Section 2.4. This measurement must meet or exceed the specification. The camera will be tested in the appropriate clinical mode.

Note that this test applies to discrete pixel cameras, and if necessary, adjacent pixels may be summed to yield an effective pixel size. If it is not possible for a system to achieve an effective pixel size within the specified range, the pixel size used must be reported with the result. If a system has a fixed collimator, it will be uniformly illuminated by a sheet source, and the presence of a collimator must be reported as a deviation, along with the result.

## Test of Gamma Camera Detectors with Collimators

### System Spatial Resolution without Scatter

The system spatial resolution without scatter will be measured and expressed as FWHM and FWTM of the line spread function. The measured values must meet or exceed the specification over the CFOV. Since the measurement depends on the collimator, as well as the detector, the measurement must be reported for each collimator type.

Note that this test applies to discrete pixel cameras and minor adjustments to the procedure are noted where appropriate below.

#### Test Conditions

The radionuclides used for these measurements shall be those for which the collimators were designed. The count rate shall not exceed 20,000 cps. For all radionuclides, an energy window recommended by the manufacturer for the appropriate clinical mode shall be used.

#### Test Equipment

The test equipment required for these measurements shall consist of two capillary tubes with an inside diameter of less than or equal to 1.0 mm and an active filled length of either 120 mm or longer.

#### Measurement Procedure

The capillary tubes shall be filled with the desired radionuclide. One of these capillary tubes shall be positioned 100 mm from the face of the collimator and along the axis of measurement, either X or Y. The digital sampling perpendicular to the capillary tube shall be no more than 0.2 FWHM and the digital sampling parallel to the capillary tube shall be no greater than 30 mm. If the data are acquired in a two-dimensional matrix, the data shall be summed parallel to the direction of the slits to form line spread functions of width 30 mm or less. At least 10,000 counts shall be collected in the peak point of each line spread function defined by the sampling parallel to the capillary tube.

The FWHM and FWTM, in pixels, will be measured for all the line spread functions that fall within the CFOV. The measurements will be made first in the X direction and then in the Y direction, using the method of Section 2.1.4. The millimeters per channel calibration factor shall be calculated as described in Section 2.1.4. If this measurement is not available, then a second measurement for each axis may be performed with a second capillary tube also positioned 100 mm from the face of the collimator and 100 mm away from, and parallel to, the first tube.

If it is a discrete pixel system, the measurement shall be made by displacing the capillary tube in 1 mm steps over a distance of at least 10 mm and over the width of at least two pixels' pitch. If the specified pixel size cannot be achieved, the smallest pixel size available shall be employed and reported as a deviation with the results.

#### Calculations and Analysis

The FWHM and FWTM measurements will be converted from pixels to millimeters, using the measured millimeter per pixel calibration factor from Section 2.1.4. The measurements for both the X and Y directions will be averaged. For each direction, the results from measurements at each capillary position shall be averaged to yield the final result.

#### Reporting

The system spatial resolution without scatter shall be reported as FWHM and FWTM within the CFOV. The radionuclide employed shall also be reported.
# System Spatial Resolution with Scatter

The system's spatial resolution with scatter must be measured and expressed as FWHM and FWTM of the line spread function. The measurements must be equal or better than the specifications required. Since collimator impact on measurement, so each collimator type must be taken into account for the test measurement.

## Test Conditions

The measurement must be taken with radionuclides designed for that specific collimator. Count rate must be under 20,000 cps energy windows recommended by the system standard. For other radionuclides, energy settings recommended by the system should be employed.

## Test Equipment

Equipment required for testing includes two capillary tubes with an inside diameter of $1.0 mm$ or less and a length of over $30 mm$. Two acrylic scattering blocks are also needed, with at least $10 X$ FWTM for the being tested collimator or the size of the UFOV. The required thickness of acrylic may be fulfilled using thinner pieces that cover the required fraction of the FOV.

## Measurements Procedure

The measurement process for system resolution is almost identical to Section 2-4, except that the $100 mm$ space between the source and the detector is filled with the scattering material, and one extra $50 mm$ of scattering material behind the source. Capillary tubes must be filled with the desired radionuclide. The $100 mm$ thick acrylic scattering block is placed directly in front of the collimator, and one of the capillary tubes is placed as close as possible to the other side of the block. The other $50 mm$ thick scattering block is kept on the other side of the capillary tube. The digital sampling resolution perpendicular to the tube must be $\leq 0.2 \ FWHM$, while the digital sampling parallel to the tube should not be over 30 millimeters. At least 10,000 counts should be cumulative.

Measure FWHM and FWTM in pixels of all linespread functions falling within the CFOV, first in the X direction and then in the Y direction, using the techniques described in Section 2.1.4. The millimeters per channel calibration factor should be calculated as described in Section 2.1.4. A second measurement for each axis may be performed with a second capillary tube, if this measurement is not usable, also placed at $100 mm$ from the face of the collimator and $100 mm$ away parallel to the first tube.

## Calculations and Analysis

Convert FWHM and FWTM measurements from pixels to millimeters with the factor of measured millimeters per pixel calibration. Measurements in both X and Y directions should be combined.

## Reporting

System spatial resolution should be reported without scattering as FWHM and FWTM within the CFOV. Collimator and radionuclide used should also be reported.
## System Planar Sensitivity and Penetration

The system planar sensitivity is the amount of counts detected in one acquisition plane to the activity of a specific parallel planar source. But, the detected counts may also be from radiation that gets through or scatters off the septa of the collimator. The penetrated or scattered radiation spoils the whole image quality and must be considered separately from the sensitivity due to properly collimated counts.

The planar sensitivity and penetration fraction of the device are influenced by the collimator type, window width, gamma energy, source configuration, and related system elements. So, the settings of these system variables should match those in a suitable clinical mode.

The planar sensitivity and penetration fraction of the system should be measured for each collimator type with the right isotopes and reported in cps/MBq and %. This goal is achievable using the plastic syringes, calibrated dose calibrator, and nominal-size standard Petri dish with a level base.

The decay-corrected count rate results using a circular region of interest (ROI) are necessary to calculate the penetration factor $PF$ at $D_{N}$, which is 100 mm. Furthermore, the decay-corrected total count rate is crucial to calculate the total system sensitivity $S_{tot}$.

For each collimator and radionuclide, $S_{tot}$ should be reported in counts/sec/MBq, and the collimator penetration factor $PF$ must be reported as a percentage.

Finally, the exponential fit curve, scatter plot of $R_{I}$ versus $D_{i}$, and the following two references are also necessary to provide: Bevington, P.R. 1969, Data Reduction and Error Analysis for the Physical Sciences and Press, W.H., Teukolsky, S.A., Vetterling, W.T., and Flannery, B.P. 1992, Numerical Recipes in C.
# Detector Shielding

The gamma camera detector's sensitivity is measured to ensure it can detect radioactivity only from the patient being imaged and not from any neighboring source. Two types of measurements are conducted to assess this effectiveness. Firstly, measurements assess the sensitivity of the gamma camera detector to radioactive leakage from a test source positioned outside the field of view in the plane of the patient table. Secondly, to assess the effectiveness of shielding for stray sources, measurements are made of the count rates obtained from sources positioned at two meters from the detector at the side and in front of the system.

## Test Conditions

The measurements need to be conducted with Tc-99m and with the highest energy nuclide that the camera is specified to operate with. The radiation's amount must be able to generate at least 1,000 counts per second (cps) and not exceed $30,000$ cps through the collimator at the first imaging position (centered under the collimator).

## Test Equipment

A 1 to 5 cc plastic vial containing the radionuclide source is required.

## Measurement Procedure

Two sets of measurements are required:
- In the first set, the unshielded source is placed on the imaging table under the collimator. The detector shall be positioned $20~cm$ above the table and facing down. The count rate will be measured at fixed positions starting with the source at the center of the field of view, then at $10~cm$, $20~cm$, $30~cm$ outside the edge of the field of view, in each direction of the test source (seven measurements in total). A background count rate shall be measured at each source position.
- In the second set, the similar source to the first one is positioned two meters from the center of the detector, directly in front of it, and in the plane of the detector. The count rate is measured with the detector facing up, down, left, and right. The source and source holder are then positioned 2 meters from the center of the detector at the side of the gantry, and the measurement of the count rate is made with the detector at the positions facing up, down, and away from the source.

## Calculations and Analysis

For each measured count rate, the appropriate half-life corrections shall apply. A computation is done for each source position, with the count rate (minus the background), which will be taken as a percentage of the count rate (minus the background) when the source was in the central position. The largest value of the percentages for each position is taken to indicate the magnitude of any possible shield leakage.

## Reporting

The largest shield leakage value will be identified for each radionuclide measured, and the collimator used should be mentioned. The measured values should exceed the specification.
This text describes the test procedures for gamma cameras. The first test is the measurement of the intrinsic count rate performance, which is determined by measuring the observed count rate with scatter using a low energy collimator and a plastic phantom filled with water. The observed count rate, maximum observed count rate, observed count rate at 20% loss, and the curve of observed count rate with scatter versus the input count rate shall be reported.

In the next section, the transaxial and axial alignment of acquired images with the system's mechanical center of rotation is tested for SPECT imaging systems. For this test, three point sources made of Tc-99m or Co-57 are used, and their images are acquired by positioning the detectors at an even number of gantry angles distributed evenly from 0 degrees. The calculated center of rotation deviation and axial misalignment values are reported in millimeters. These tests apply to discrete pixel cameras. All values should be reported in millimeters.
# SPECT Reconstructed Spatial Resolution Test without Scatter

The SPECT system's reconstructed spatial resolution must meet the specification at three points in the air. The FWHM values of resolution in the X, Y and Z direction for the three points must be reported. This measurement depends on the collimator and detector and must be reported for each collimator type. This test applies to discrete pixel cameras.

## Test Conditions

The conditions are the same as in Section 3.1.1.

## Test Equipment

Three thin-walled glass capillary tubes or equivalent with internal diameters of 1.0 mm or less must be used along with point sources that have less than a 2 mm activity drop. The activity of the point sources may need to vary by less than 30% to avoid digital saturation.

## Measurement Procedure

The three point sources should be arranged in the center of the system's FOV by positioning them parallel to the table's plane with the middle point source located on the axis of rotation and centered in the field of view to a margin of ±5 mm. The radius of rotation must be 150 ± 5 mm, and data must be acquired and reconstructed in a matrix with an effective pixel size of less than or equal to 2.5 mm. At least 20,000 total counts in each projection angle image utilizing a step and shot mode and a maximum 3° projection angle increment must be obtained. The orbit must include projections over 360°.

## Calculations and Analysis

Three orthogonal slices, each containing an image of the three point sources, must be reconstructed from raw projection data. The filtered back-projection technique with a ramp filter must be used along with orthogonal slices that are one 130 ± 5 mm thick transverse, centered on the middle point source; one 180 ± 5 mm thick sagittal, centered on the middle point source; and one 30 ± 5 mm thick coronal slice centered on the line of the three point sources.

### Analysis of Point Images

Each of the nine point source images contained in the three slices must be analyzed individually within a square ROI centered on the maximum count pixel associated with this point.

### FWHM Calculations

The FWHM in Image X and Image Y for all nine point images must be calculated according to the method described in Section 2.1.4. The measured values must be entered in Worksheet 4-1 for the central point and Worksheet 4-2 for the peripheral points. Five average resolutions must be calculated using Equations 4-8 through 4-12.

## Reporting

The collimator used in each measurement must be recorded, along with the FWHM values calculated in Equations 4-8 through 4-12 in millimetres. Central Transaxial (X, Y), Central Axial (Z), Peripheral Radial (X), Peripheral Tangential (Y), and Peripheral Axial (Z) are the five average FWHM values.
# SPECT Reconstructed Spatial Resolution with Scatter

This test measures the accuracy of transaxial spatial resolution of discrete pixel cameras by using three line sources in a water cylinder. Tc-99m or Co-57 line sources are used with a recommended photopeak energy window. One transverse slice, approximately 10 mm in thickness, is reconstructed by filtered back projection technique with a ramp filter. The FWHM values of the three reconstructed points in each of the three reconstructed slices are analyzed on their radial and tangential directions. Three FWHM resolution values shall be reported, including one for the central source and two for the peripheral sources in millimeters.

## System Volume Sensitivity

This test measures the system volume sensitivity (SVS) of a specific cylindrical phantom to a uniform concentration of activity. The VSAC is calculated from the SVS and averaged with information such as detector configuration, collimator type, and other factors. The value is reported in counts per second per MegaBecquerel per cubic centimeter for SVS and counts per second per MegaBecquerel per square centimeter for VSAC. Different values are reported for each radionuclide and collimator type.
## Detector-Detector Sensitivity Variation

In gamma camera systems that have more than one detector, Detector-Detector Sensitivity Variation refers to the difference in sensitivity levels between individual detectors, which can be measured through tomographic imaging mode. The results obtained should be typical for the particular model. This test is used only for discrete pixel cameras.

### Test Equipment

The phantom described in volume sensitivity (section 4.4) and shown in Figure 4-4 will be used for the measurements. This test is carried out using discrete pixel cameras, and its sources are configured as specified in section 4.4, System Volume Sensitivity.

### Measurement Procedure

A tomographic image of the phantom is captured with the data collected from all detectors. The acquisition must cover each detector's full rotational range, and each projection image must contain 100,000 ± 20,000 counts with an energy window that the manufacturer recommended for the relevant clinical mode. If the data is collected correctly, it can be used for both this test and for measuring Volume Sensitivity.

### Calculations and Analysis

The raw projection images are used for this analysis. All the projection images obtained using the first detector and second detector are summed to form an image. The sum of images obtained from each detector shall be denoted as C. The total counts in each of the Sum images are computed. The difference between the highest and lowest $C_i$, expressed as a percentage of the highest value, yields DDS which is expressed as a percentage of the largest value.

### Reporting

DDS, which represents the maximal percentage difference in sensitivity between a detector pair, is reported as Detector-Detector Sensitivity Variation in a multi-detector system.

## Whole-Body System Spatial Resolution Without Scatter

The System spatial resolution without scatter is determined parallel and perpendicular to the direction of continuous motion by measuring the full width at half maximum (FWHM) and full width at the tenth maximum (FWTM) of the line spread function. All measured values must meet or surpass the specification. This test is not applicable to step-and-shoot whole-body planar acquisition. This test is utilized for discrete pixel cameras.

### Test Conditions

Tc-99m will be the radionuclide utilized for this measurement. Any other radionuclide(s) employed must be stated separately. The recommended count rate ranges between 10,000 and 20,000 cps, with two capillary tubes within the detector field of view, and an energy window specified by the manufacturer for the appropriate clinical mode. The camera must also be equipped with a collimator.

### Test Equipment

Two capillary tubes placed parallel to the detector parallel to the detector's plane and having an inside diameter of ≤ 1.0 mm and at least an active filled length of 120 mm, will be used for this measurement. These sources should be positioned on the whole-body scanning table, so the resolution measurements can be calibrated in units of millimeters (mm). The millimeters per channel calibration factor shall be calculated as described in Section 2.2.4.

### Resolution Parallel to the Direction of Motion

One capillary tube shall be placed at the center of the scanned field view, perpendicular to the direction of motion. The second line source shall be set alongside the first source, parallel to it, and at a distance of 100 mm, as shown in Figure 5-1a.

### Resolution Perpendicular to the Direction of Motion

One capillary tube shall be placed at the center of the scanned field view with the second source positioned parallel to the first tube also, at a distance of 100 mm, as shown in Figure 5-1b. The source positioning for whole-body resolution tested in this measurement is shown in Figure 5-1.

### Measurement Procedure

a. The scan speed shall be in the range recommended for clinical use.
b. Scans shall be performed with the detector both above and below the table for the two source orientations as described in Section 3.1.2.
c. The digital sampling perpendicular to the tubes shall be no less than 0.25 of the FWHM of the system resolution of the collimator being used. The digital resolution parallel to the tubes shall be no less than 25 mm and no more than 30 mm.

### Calculation and Analysis

The average millimeters per pixel shall be calculated from the known line spacing. The FWHM and FWTM shall be calculated separately for the tubes parallel and perpendicular to the direction of motion in each segment of the central capillary tube, using the method outlined in Section 2.1.4. The FWHM and FWTM values shall be averaged separately for the tubes parallel and perpendicular to the motion direction.

### Reporting

The average FWHM and FWTM values must be reported. The values reported must be the average of the measurements obtained over and under the table. Furthermore, the parallel and perpendicular resolutions shall be reported in separate sections. Lastly, a report on the collimator and scan speed used for the measurement must be presented.

### Rationale

Although the functionality of a whole-body scanning system is reliant on the camera's inherent and system performance, it is also heavily dependent on the scanning mechanism's effectiveness and alignment. The tests aim to assess the precision of these aspects of the system. Most of the problems associated with whole-body scanning systems are related to spatial resolution. Since the parallel and perpendicular resolutions are affected by distinct mechanisms, such as motion control, camera scale calibration, collimator quality, and mechanical alignment of the camera and the table, they must be reported separately.

