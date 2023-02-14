# Contrôle qualité en radiothérapie


---
title:
- NEMA Standards Publication NU1-2007
-  1.3 TEST EQUIPMENT, CONDITIONS, AND RESULTS
-  3.4.4 Calculations and Analysis
---

# Référence. définition, et equipment

## Référence

### Source Holders and Test Fixtures

A number of different source holders are required for the performance of
the procedures. Each source holder is described in the individual
procedure for which it is required. Manufacturing tolerances and
materials of source holders are often critical in ensuring precise and
reproducible measurements. Care has been taken to make the design of the
source holders as simple as possible, consistent with the requirements
for precision and accuracy in the measurement procedures. All
dimensional tolerances shall be $\pm 10 \%$ unless otherwise specified.

### Radiation Sources

A variety of different shapes and activities of radiation sources is
required. The majority of the tests use Tc-99m. However Co-57 can often
be substituted for Tc-99m as indicated in individual procedures. Ga -67
is required to perform the Multiple Window Spatial Registration
procedures.

Generally, the procedures can also be performed with other radionuclides
provided the radionuclide used is clearly reported with the test
results.

### Test Conditions

All measurements shall be performed in the appropriate clinical mode of
operation. The energy windows utilized for the measurements also should
be specified. Any additional tests at variance with the above conditions
or test parameters shall be separately reported and the variances shall
be clearly indicated.

If, for quality assurance or other purposes, the manufacturer employs
radionuclides other than those prescribed by this standard, he shall
demonstrate traceability between the radionuclide prescribed for the
measurement and the radionuclide employed.

### Reporting

For each test described, each system is expected to \"meet or exceed\"
the manufacturer's specification, unless the specification is considered
\" typical\" performance.

\" Typical\" specifications are used when the measurement is
sufficiently time -consuming that measuring large numbers of units is
difficult:

Intrinsic Count Rate Performance in Air,

System Count Rate Performance with Scatter;

or where there are inherent difficulties in obtaining a very accurate
measurement in a manufacturing or hospital environment:

System Planar Sensitivity and Penetration,

Detector-Detector Sensitivity Variation,

System Volume Sensitivity.

\(c\) Copyright 2007 by the National Electrical Manufacturers
Association.

# Section 2: TESTS OF GAMMA CAMERA DETECTORS

## INTRINSIC SPATIAL RESOLUTION

Intrinsic spatial resolution measurements shall meet or exceed the
specification

Note for discrete pixel cameras. The concept of intrinsic spatial
resolution as defined for single crystal cameras is not analogous, nor
directly applicable to that of discrete pixel cameras. The spatial
resolution of these systems may be characterized using the system
spatial resolution measurement described in Section 3.1 .

### Test Conditions

The radionuclide employed for this test shall be Tc-99m. A source
holder, which shields the source from walls, ceilings and personnel
without restricting the gamma flux from the source to the camera (as
shown in Figure 2-1), shall be employed. One or more copper plates, as
shown in Figure 2-1, may be used to adjust the count rate. The energy
window for Tc-99m shall be that recommended by the manufacturer for the
appropriate clinical mode. The count rate shall not exceed 20,000 cps
through the energy window.

If other radionuclides are used, the energy window should be set
according to the manufacturer's recommendations.

### Test Equipment

The test pattern shall consist of a lead mask in closest possible
proximity to the crystal, covering the entire UFOV with 1 millimeter
wide parallel slits. Adjacent slit centers shall be 30 millimeters from
each other (see Figure 2-2 which shows the geometry for rectangular
field of view). The thickness of the mask shall be 3 millimeters for Tc-
$99 \mathrm{~m}$.

### Measurement Procedure

The lead mask with the parallel slits shall be positioned on the camera
detector with one of the slits centered perpendicular to the axis of
measurement. The radionuclide shall be a point source centered at a
distance at least five times greater than the largest linear dimension
of the UFOV above the lead mask with the parallel slits. The digital
resolution perpendicular to the slits is recommended to be less than or
equal to $0.2$ FWHM. The digital resolution parallel to the slits shall
correspond to a channel width less than or equal to 30 millimeters. If
the data are acquired in a two dimensional matrix, the data shall be
summed parallel to the direction of the slits to form line spread

!\[\](https://cdn.mathpix.com/cropped/2023_02_08_3841e886d6af9a4bf71dg-02.jpg?height=1479&width=648&top_left_y=982&top_left_x=1155)

Figure 2-1

\(c\) Copyright 2007 by the National Electrical ivıaıııauıu efollimated
source geometrv NU-1 2007

Page 11

functions of width $30 \mathrm{~mm}$ or less.

At least 1,000 counts shall be collected in the peak channel of each
line spread function measurement. FWHM (full width at half maximum) and
FWTM (full width at tenth maximum) of the line-spread function shall be
measured.

!\[\](https://cdn.mathpix.com/cropped/2023_02_08_3841e886d6af9a4bf71dg-03.jpg?height=1508&width=1105&top_left_y=591&top_left_x=498)

Figure 2-2

Lead masks for measurement of spatial resolution and linearity.

### Calculations and Analysis

If the digital resolution perpendicular to the slits is less than or
equal to $0.2$ FWHM, then the maximum value pixel is taken to be the
peak value.

If the digital resolution perpendicular to the slits is more than $0.2$
FWHM, The peak value shall be then determined (c) Copyright 2007 by the
National Electrical Manufacturers Association. from the largest maximum
value of a parabolic fit, using the peak point (maximum value pixel) to
the three largest value points in each line spread function and its two
nearest neighboring points (see Figure 2-3).

The half maximum and tenth maximum locations shall be determined by
linear interpolations from the nearest two

!\[\](https://cdn.mathpix.com/cropped/2023_02_08_3841e886d6af9a4bf71dg-04.jpg?height=965&width=574&top_left_y=540&top_left_x=318)

Points $A, B$, and $C, D$ are found by linear interpolation from points
surrounding the half and tenth peak values.

$\mathrm{B}-\mathrm{A}=\mathrm{FWHM}$ in channels

$\mathrm{D}-\mathrm{C}=\mathrm{FWTM}$ in channels

$\underline{A+B}=E:$ peak center (used for linearity) neighboring points
of the half peak value and the tenth peak value respectively, using the
peak value in each line spread function curve as the maximum (see Figure
2-3).

The distance between adjoining peaks shall be averaged over the entire
UFOV for determining the millimeters per channel calibration factor. The
calculated average distance shall correspond to the $30 \mathrm{~mm}$
distance between the slits. This calibration factor shall be used to
convert the calculated values of FWHM and FWTM from units of channels to
millimeters per channel. The value of FWHM and FWTM shall be calculated
as the average of all such values for both axes, lying within the UFOV
and CFOV respectively. The calculated values shall not be corrected for
background or slit width.

### Reporting

The calculated average FWHM and FWTM for a Tc-99m radionuclide shall be
reported for both the UFOV and the CFOV, and given in millimeters with
an accuracy of at least $0.1 \mathrm{~mm}$.

Any other radionuclide employed shall be separately reported.

Measurements performed at any higher count rate than 20,000 cps shall
also be separately reported.

Figure 2-3

Determination of FWHM and FWTM NU-1 2007

Page 13

## INTRINSIC SPATIAL LINEARITY

Intrinsic spatial differential and absolute linearity shall meet or
exceed the specifications. Differential linearity shall be expressed in
millimeters as the standard deviation of the measured peak locations
from a best-fit line. Absolute linearity shall be expressed as the
maximum displacement of any peak from the best fit of a two dimensional
grid.

Note for discrete pixel cameras. The concept of intrinsic spatial
linearity as defined for single crystal cameras is not analogous, nor
directly applicable to discrete pixel cameras.

### Test Conditions

The radionuclide employed for this test shall be Tc-99m. A source
holder, which shields the source from walls, ceilings, and personnel
without restricting the photon flux from the source to the camera (as
shown in Figure 2-1), shall be employed. One or more copper plates, as
shown in Figure 2-1, may be used to adjust the count rate. The energy
window for Tc-99m shall be that recommended by the manufacturer for the
appropriate clinical mode. The count rate shall not exceed 20,000 cps
through the energy window.

If other radionuclides are used, the energy windowshould be set
according to the manufacturer's recommendations.

### Test Equipment

The test pattern shall consist of a lead mask in closest possible
proximity to the crystal covering the entire UFOV with 1-millimeter wide
parallel slits. Adjacent slit centers shall be $30 \mathrm{~mm}$ one
from the other (refer to Figure 2-2 which shows the geometry for a
rectangular field of view camera). The thickness of the mask shall be 3
millimeters for Tc$99 \mathrm{~m}$ or $\mathrm{Co}-57$.

### Measurement Procedure

The lead mask with the parallel slits shall be positioned on the
detector with the center slit centered on the detector. The center slit
shall be perpendicular to the axis of measurement and aligned so that
the end of the central slit is positioned to within $\pm 1$ millimeter
at the edge of the UFOV.

The radionuclide shall be a point source centered at least five times
the largest linear dimension of the UFOV above the center of the lead
mask with the parallel slits.

The digital resolution perpendicular to the slits shall be less than or
equal to $0.2 \mathbf{F W H M}$.

The data shall be integrated parallel to the direction of the slits to
form line-spread functions. The digital resolution parallel to the
direction of the slits shall be less than or equal to $30 \mathrm{~mm}$.
At least 1,000 counts shall be collected in the peak channel of each
line spread function measurement after integration parallel to the
direction of the slits.

Two sets of data shall be acquired-one with the slits in the
$\mathrm{X}$ direction and one in the $\mathrm{Y}$ direction.

### Calculations and Analysis

If the data are acquired in a two dimensional matrix, the data shall be
summed parallel to the direction of the slits to form line spread
functions of width $30 \mathrm{~mm}$ or less.

The distances between the peaks in each of the line spread functions
shall be determined as the average of the

\(c\) Copyright 2007 by the National Electrical Manufacturers
Association. interpolated half maximum locations on both sides of each
peak. The half maximum locations shall be determined by linear
interpolations from the nearest two neighboring points of the half peak
value as described in Section 2.1.4 (see Figure 2-3). The locations of
the peaks shall be calculated for each subsequent line spread function.
This will generate a two dimensional array of peak locations. One
dimension will be along the slits and one will be perpendicular to the
slits. Note that there will be two two-dimensional arrays, one from data
acquire d with slits in the $\mathrm{X}$ direction and the other with
slits in the $\mathrm{Y}$ direction.

The value of intrinsic spatial differential linearity (in pixels) shall
be calculated as the standard deviation of the locations of the peaks in
each slit. The standard deviations for the slits in the $\mathrm{X}$ and
$\mathrm{Y}$ directions shall be averaged together. Separate values
shall be calculated for the UFOV and for the CFOV.

Intrinsic spatial absolute linearity shall be determined by fitting a
set of equally spaced parallel lines to the data using a least squares
minimization technique. Different sets of lines shall be fitted to the
UFOV and to the CFOV data. There shall also be a separate set of lines
fitted for data acquired with the slits in the $\mathrm{X}$ and in the
$\mathrm{Y}$ directions. The maximum displacement for each set shall be
the largest difference between the data and the grid fit (in pixels) in
the $X$ or the $\mathrm{Y}$ direction.

The millimeters per channel calibration factor shall be calculated as
described in Section 2.1.4 . This factor shall be used to convert the
differential linearity and absolute linearity to millimeters.

### Reporting

The intrinsic spatial differential linearity shall be reported for both
the UFOV and for the CFOV. The values shall be given in millimeters with
an accuracy of at least $0.1 \mathrm{~mm}$.

The intrinsic spatial absolute linearity shall be reported for both the
UFOV and for the CFOV. The values shall be given in millimeters with an
accuracy of at least $0.1 \mathrm{~mm}$.

## INTRINSIC ENERGY RESOLUTION

Intrinsic energy resolution shall meet or exceed the specification, and
shall be expressed as the ratio of the photopeak FWHM to the photopeak
center energy, stated as a percentage.

Note for discrete pixel systems. This test applies to discrete pixel
cameras. For these systems the spectra from all individual detector
pixels for each radionuclide shall be summed after energy correction and
prior to the calculation of FWHM. There shall be 10,000 total counts in
summed spectrum from all pixels. For those systems with a fixed
collimator the system shall be uniformly illuminated by a distributed
source. The presence of a collimator shall be reported as a deviation
along with the result.

### Test Conditions

The radionuclide employed for this test shall be Tc-99m. A source holder
which shields the source from walls, ceilings and personnel without
restricting the gamma flux from the source to the camera (as shown in
Figure 2-1) shall be employed. At least $2 \mathrm{~mm}$ of copper, as
shown in Figure 2-1, shall be used. The detector shall be masked with a
$3 \mathrm{~mm}$ thick lead aperture to establish the UFOV. The integral
count rate shall not exceed 20,000 cps.

### Test Equipment

The test equipment shall include means to digitize the energy spectrum
with a channel depth of at least 10,000 counts, and a digital resolution
of less than or equal to $0.05$ FWHM of Tc- $99 \mathrm{~m}$ photopeak.
NU-1 2007

Page 15

### Measurement Procedure

The radionuclide shall be a Tc-99m point source centered at a distance
at least five times greater than the largest linear dimension of the
UFOV above the detector. A second radionuclide, Co-57, shall be employed
as a reference in order to determine the keV per channel calibration
factor. The spectra for Tc $-99 \mathrm{~m}$ and Co $-57$ shall be
separately stored. The spectra from all individual detector pixels for
each radionuclide shall be summed after energy correction and prior to
the calculation of FWHM. At least 10,000 counts shall be acquired in the
peak channel of each summed spectrum measurement.

### Calculations and Analysis

For each of the stored spectra, the photopeak location shall be
determined as the average of the linearly interpolated half height
channel values, calculated for each side of the photopeak (see Figure
2-3). The difference betwe en the two photopeak locations in channel
numbers should correspond to $18.4 \mathrm{keV}$, which is the
difference between $140.5 \mathrm{keV}$ of the Tc-99m photopeak center
energy and the $122.1 \mathrm{keV}$ of the Co-57 photopeak center
energy. The intrinsic energy resolution shall be calculated from the
Tc-99m stored spectrum. The FWHM in channel numbers shall be determined
from the linearly interpolated half height channel values and calculated
for each side of the Tc-99m photopeak. This value shall be multiplied by
the calibration factor (keV per channel), divided by
$140.5 \mathrm{keV}$ corresponding to the Tc$99 \mathrm{~m}$ photopeak
center energy, and multiplied by 100 in order to obtain the value as a
percentage.

If other radionuclides are used, the reference nuclide for calibration
(keV/channel) shall be Cobalt-57.

### Reporting

The calculated intrinsic energy resolution over the UFOV for a Tc-99m
radionuclide shall be reported and expressed as a percentage.

Any other radionuclides employed shall be separately reported.

Measurements performed at any higher count rate than 20,000 cps shall
also be separately reported.

## INTRINSIC FLOOD FIELD UNIFORMITY

The intrinsic uniformity of the system shall be measured for the CFOV
and UFOV. The measured values shall meet or exceed the specification.

The intrinsic uniformity is the response of the system without a
collimator to a uniform flux of radiation from a point source. Two
different uniformity parameters shall be determined: integral uniformity
and differential uniformity.

Note for discrete pixel systems. This test applies to discrete pixel
cameras. If necessary adjacent pixels may be summed to yield an
effective pixel size within the range specified below. For those systems
unable to achieve an effective pixel size within the specified range the
pixel size employed shall be reported with the result. For those systems
with a fixed collimator the system shall be uniformly illuminated by a
sheet source. The presence of a collimator shall be reported as a
deviation along with the result.

### Test Conditions

Intrinsic uniformity should be measured for each radionuclide used
clinically. The count rate shall not exceed 20,000 cps through a
photopeak window recommended by the manufacturer for the appropriate
clinical mode. The status of uniformity corrections used shall be stated
with the results. For each radionuclide tested, the energy window
settings recommended by the manufacturer shall be used.

### Test Equipment

The test equipment required for this measurement consists of a source
holder, a lead mask for the detector, and a computer or multi-channel
analyzer. The source holder shall consist of a lead shield to prevent
back and side scatter but be open at the front so that it does not
restrict the gamma flux from the source to the detector. The source
holder is shown in Figure 2-1. The lead mask for the detector is a lead
aperture of at least the dimensions of UFOV.

### Measurement Procedure

The detector shall be masked using a lead mask described above. The
source in the source holder shall be placed on the central axis of the
detector. The distance from the detector to the source shall be at least
five times the largest dimension of the UFOV. The flood field image
shall be stored in a matrix size that produces pixel sizes with a linear
dimension of $6.4 \mathrm{~mm} \pm 30 \%$. The pixels shall be square.

A minimum of 10,000 counts shall be collected in the center pixel of the
image.

### Calculations and Analysis

Prior to performing the uniformity calculations, the pixels for
inclusion shall be determined as described below.

First, any pixel that has at least $50 \%$ of its area inside the UFOV
shall be included within the UFOV analysis. Any pixels in the outer rows
and columns of the UFOV containing less than $75 \%$ of the mean counts
per pixel in the CFOV shall be set to zero.

Second, those pixels which now have at least one of their four directly
abutted neighbors containing zero counts, will be also set to zero. The
remaining non-zero pixels are the pixels to be included in the analysis
for the UFOV.

This step shall be performed only once. Any pixel that has at least
$50 \%$ of its area inside the CFOV shall be included within the CFOV
analysis.

### Data Preparation

The flood field image, after removing the edge pixels, shall be smoothed
once by convolution with a 9-point filter function of the following
weightings:

  1   2   1
  --- --- ---
  2   4   2
  1   2   1

The weighting factor for a pixel outside the analyzed area in the
9-point filter function shall be zero. The smoothed value shall be
normalized by dividing by the sum of non-zero weighting factors.

### Integral Uniformity

For pixels within each area (CFOV and UFOV), the maximum and the minimum
values are identified from the smoothed data. The difference between the
maximum and the minimum is divided by the sum of these two values and
multiplied by 100 . NU-1 2007

Page 17

$$\text { Integral Uniformity }=\pm 100 \times \frac{(\max -\min )}{(\max +\min )}$$

Equation 2-1

### Differential Uniformity

For pixels within each area (CFOV and UFOV) the largest difference
between any two pixels within a set of 5 contiguous pixels in a row or
column shall be calculated. The calculation shall be done for the
$\mathrm{X}$ and the $\mathrm{Y}$ directions independently and the
maximum change expressed as a percentage using the following:

$$\text { Differential Uniformity }=\pm 100 \times \frac{(\max -\min )}{(\max +\min )}$$

Equation 2-2

The smoothed data are treated as a number of rows (X slices) and columns
( $\mathrm{Y}$ slices). Each slice is processed by starting at the
beginning pixel for the respective field of view. A set of five
contiguous pixels is examined to find the maximum and minimum pixels.
The differential uniformity is calculated using these values. The next
set of five pixels is analyzed by stepping forward one pixel and again
determining the percent uniformity. This is repeated until the outermost
pixel is reached. The maximum differential uniformity is found in the
slice. This process is then repeated for all of the slices.

### Reporting

The results for each radionuclide are reported separately as the
percentage integral and differential uniformity for both of the CFOV and
the UFOV.

## MULTIPLE WINDOW SPATIAL REGISTRATION

Multiple window spatial registration (MWSR) is a measure of the camera's
ability to accurately position photons of different energies when imaged
through different photopeak energy windows. Measurements shall be made
at nine specified points on the entrance plane of the gamma camera. The
measured values of multiple window spatial registration shall meet or
exceed the specification.

!\[\](https://cdn.mathpix.com/cropped/2023_02_08_3841e886d6af9a4bf71dg-09.jpg?height=634&width=688&top_left_y=1690&top_left_x=247)

Figure 2-4

Cylindrical source holder for multiple window spatial registration
measurement showing liquid Ga-67 source Note for discrete pixel systems.
This test applies to discrete pixel cameras. If necessary adjacent
pixels may be summed to yield an effective pixel size within the range
specified below. For those systems unable to achieve an effective pixel
size within the specified range the pixel size employed shall be
reported with the result. For those systems with a fixed collimator the
system shall be uniformly illuminated by a sheet source. The presence of
a collimator shall be reported as a deviation along with the result.

### Test Conditions

The radionuclide used to measure multiple window spatial registration
shall be $G a-67$. The energy window settings for each of the three
Gallium peaks shall be set as recommended by the manufacturer. The count
rate shall not exceed 10,000 counts per second through each photopeak
energy window. incids

\(c\) Copyright 2007 by the National Electrical Manufacturers
Association.

### Test Equipment

A lead-lined source holder shall collimate the Ga -67 source through a
cylindrical tunnel in the lead. This tunnel shall be $5 \mathrm{~mm}$ in
diameter and $25 \mathrm{~mm}$ in length. See Figure 2-4 for a sketch of
the Ga -67 source inside such a source holder.

### Measurement Procedure

Images shall be acquired using the collimated Ga -67 source described
above (see Figure 2-4) located at nine specific points on the entrance
surface of the uncollimated camera. These nine points shall be the
central point, four points on the X-axis and four points on the Y-axis.
The off central points shall be located $0.4$ times and $0.8$ times the
distance from the central point to the edge of the UFOV of the camera
along the respective axes. Separate images of the collimated Ga -67
source shall be acquired through separate energy windows of the Ga - 67
photopeaks at each of these image locations. These images shall be
acquired with a pixel size of not more than $2.5 \mathrm{~mm}$. For
cameras with two energy windows, two images shall be acquired at each
point, one using the $93 \mathrm{keV}$ photopeak and the second using
the $300 \mathrm{keV}$ photopeak. For cameras with three or more energy
windows, the $184 \mathrm{keV}$ photopeak shall also be imaged. For
cameras with maximum energies below $300 \mathrm{keV}$ the
$93 \mathrm{keV}$ and $184 \mathrm{keV}$ photopeaks should be used. At
least 1,000 counts shall be acquired in the peak pixel of each photopeak
image.

### Calculations and Analysis

The displacement of the count centroids from each other in the
$\mathrm{X}$ and $\mathrm{Y}$ directions shall be determined for each
measurement point's photopeak images. A square region of interest (ROI)
centered on the maximum count pixel associated with each photopeak image
shall be used to analyze the individual photopeak images.

The pixel dimensions of the square ROI shall be approximately four times
the FWHM of the image count profile to be analyzed. Each image shall be
integrated in the $\mathrm{Y}$ direction to determine the $\mathrm{X}$
count profile and integrated in the $\mathrm{X}$ direction to determine
the $\mathrm{Y}$ count profile. The centroid of counts in the
$\mathrm{X}$ and $\mathrm{Y}$ directions shall be determined for each
image from that direction's count profile by the method described below.
The maximum difference in the $\mathrm{X}$ and $\mathrm{Y}$ position of
the centroid of counts acquired from each photopeak shall be determined.
The largest pixel displacement shall then be converted to millimeters
using an accurate millimeter per pixel calibration from Section 2.1.4 .

### Method for Centroid of Counts Determination

The center of counts in the $\mathrm{X}$ and $\mathrm{Y}$ directions for
each of the photopeak count profiles shall be determined as follows.
Find the maximum count pixel in the integrated $\mathrm{X}$ or
$\mathrm{Y}$ profile and calculate the centroid of counts using the
following formula:

$$L_{j}=\sum_{i=1}^{n}\left(X_{i} \times C_{i}\right) / \sum_{i=1}^{n} C_{i}$$

Equation $2-3$

Where:

$L_{j}=$ calculated centroid location for energy window $\mathrm{j}$,
where $\mathrm{j}$ can equal 1,2 , or 3.

$X_{i}=\mathrm{X}$ or $\mathrm{Y}$ count profile pixel at the i'th
location

$C_{i}=$ counts at the $\mathrm{X}_{\mathrm{i}}$ or
$\mathrm{Y}_{\mathrm{i}}$ location.

$\sum_{i=1}^{n}=$ is the sum over an odd number of count profile pixels
centered on the maximum count profile pixel. The (c) Copyright 2007 by
the National Electrical Manufacturers Association. NU-1 2007

Page 19

exact odd number of pixels will depend on the FWHM of the count profile
and the pixel size. The minimum number of pixels in this sum shall
include both the left and right half maximum counts.

The displacement $D_{i j}$ between energy windows $i$ and $j$ is then:

$$D_{i j}=\left|L_{i}-L_{j}\right|$$

Equation 2-4

for all combinations of $(i, j)$, where $i$ ? $j$. The maximum
displacement is simply the largest $D_{i j}$. This calculation is
reported for both the $\mathrm{X}$ and $\mathrm{Y}$ directions.

### Reporting

The multiple window spatial registration (MWSR) shall be reported as the
maximum difference in spatial positions for different energy windows in
either the X or Y direction of the photopeak count centroids for the
nine points measured. The values shall be reported in millimeters to the
nearest tenth of a millimeter

!\[\](https://cdn.mathpix.com/cropped/2023_02_08_3841e886d6af9a4bf71dg-11.jpg?height=1028&width=668&top_left_y=1139&top_left_x=246)

Source holder for count rate measurements.

## INTRINSIC COUNT RATE PERFORMANC E IN AIR

The decaying source method shall be used to determine count rate
performance. Two parameters shall be measured and reported: observed
count rate for a $20 \%$ count loss and a maximum count rate. Both
parameters shall be measured without induced scatter. The curve of
observed versus input count rates shall be provided.

Specifications of Intrinsic Count Rate Performance in Air shall be
typical of the model (see Section 1.3.4).

Note for discrete pixel systems. This test applies to discrete pixel
cameras. For those systems with a fixed collimator the system shall be
uniformly illuminated by a distributed source. The presence of a
collimator shall be reported as a deviation along with the result.

### Test Conditions

The radionuclide employed for the test shall be Tc-99m. Any other
radionuclide(s) employed shall be separately reported.

The energy window for Tc-99m shall be that recommended by the
manufacturer for the appropriate clinical mode. For other radionuclides
the energy settings recommended the manufacturer shall be used. Peaking
shall be performed at a low count rate and shall not be manually
readjusted during the test. The camera shall be tested in the
appropriate clinical mode.

### Test Equipment

A camera under test shall have the camera crystal masked to the UFOV.
The source shall be placed within a source holder, as in Figure 2-5,and
shall be arranged as in Figure 2-1 except that the distance from the
source to the detector surface may be less than 5 times the UFOV. The
open side of the source holder (facing the camera crystal) shall be
covered by $6 \mathrm{~mm}$ of copper plates. The source intensity shall
be such that it produces an input count rate that is larger than the
count rate required to cause foldover in the observed count rate.

### Measurement Procedure

Determine the background count, $N_{b k g}$ and the background count
rate $R_{B k g}=N_{b k g} / \Delta t_{b k g}$. For the background
measurement $N_{b k g}=100,000$ or $\Delta t_{b k g}=10$ minutes. The
background should be measured at the beginning of the measurement to no
source of background is present. The background measurement shall be
repeated at the end of the measurement for the purposes of background
subtraction.

The source holder with the source shall be placed in front of the
detector, so that the collimated cone of radiation is centered within
the UFOV and that the irradiated area of the crystal extends fully
across the smaller dimension of the UFOV. Care must be taken to minimize
scatter.

The start $\left(t_{i}\right)$ and elapsed time
$\left(\Delta t_{i}\right)$ of the measurement shall be recorded for
each data point, $C t_{i}$, where (i) is the number of the data point
and $C t_{i}$ is the number of counts recorded

The time shall be measured relative to the start of acquisition time of
the measurement of the first data point. For each data point
$\left(C t_{i}\right)$, at least 100,000 counts shall be collected. Data
should be acquired for 10 sec or 100,000 counts, whichever time is
longer.

The measurement shall be performed so that the points are taken before
the observed count rate changes by 10,000 cps from the previous measured
point. The last (n'th) point taken should be measured when the observed
count rate drops below 4,000 cps.

### Calculations and Analysis

Each data point is first corrected for background:

$$C_{i}=C t_{i}-R_{b k g} \cdot \Delta t_{i}$$

Equation 2-5

The observed count rate $\left(O C R_{i}\right)$ shall be determined for
each data point according to the following formula:

$$\text { OCR }_{i}=\frac{C_{i} \ln (2)}{T_{\text {half }} \cdot\left\{1-\exp \left[\left(-\Delta t_{i}\right) \cdot \ln (2) / T_{\text {half }}\right]\right\}}$$

Equation 2-6

where $T_{\text {half }}=21,672$ seconds is the half-life of Tc-99m, and
where $t_{i}$ and $\Delta t_{i}$ also are recorded in units of seconds.
Equation 2-6 corrects for physical decay of the source during the i'th
measurement.

The input count rate $\left(\mathrm{ICR}_{\mathrm{i}}\right)$ for each
data point shall be calculated according to the following formula:

$$I C R_{i}=O C R_{n} \cdot \exp \frac{\square}{\frac{\square}{\square} \frac{\left.t_{n}-t_{i}\right) \cdot \ln (2)}{T_{\text {half }}}} \stackrel{\square}{\square}$$

Equation 2-7

The observed count rate at $20 \%$ loss shall be determined by linear
interpolation between the two closest points to the equation: NU-1 2007

Page 21

$$L_{i}=0.8 \times 1 C R_{i}$$

Equation 2-8

### Explanation

The purpose of Equation 24 is to scale the measurements (calculate the
observed count rate corrected for background) to the time at the
beginning of the measurement of each data point $t_{\mathbf{i}}$.

When the measurement is performed at high count rates, the duration of
the measurement has little or no effect. That is to say that Tc
$-99 \mathrm{~m}$ will decay very little during a few seconds of the
measurement at count rates of, e.g. 150,000 cps. However, when the count
rate approaches 4,000 cps and if 100,000 counts are collected, the
measurement will take more than 25 seconds, during which time Tc-99m
will decay by approximately $0.1 \%$.

!\[\](https://cdn.mathpix.com/cropped/2023_02_08_3841e886d6af9a4bf71dg-13.jpg?height=891&width=1148&top_left_y=1039&top_left_x=448)

Equation $2-5$ takes care of this problem by subtracting the appropriate
amount of background counts from the number of counts collected and
Equation 2-6 scales this number according to the exponential decay law.
The resulting observed count rate points are now scaled to the time at
the beginning of the measurement of each data point; i.e.,
$\mathrm{OCR}_{\mathrm{i}}$ is the number that would be obtained if we
could instantaneously measure only the counts coming from the source (no
background).

Equation 2-7 simply extrapolates the measurement taken at the last point
(at a very low count rate) to the points at high count rates. This is
reasonable because the dead time at the count rates below
$4,000 \mathrm{cps}$ is only a fraction of a percent. This relative
error is propagated through extrapolation, but it is not amplified
(i.e., it will always retain the same percentage).

The largest effect, by far, is caused by the background measurement.
Effort should be maintained to minimize (c) Copyright 2007 by the
National Electrical Manufacturers Association. variations in background
throughout the test.

### Reporting

Typical values (see Section 1.3.4 ) of maximum observed count rate,
observed count rate at $20 \%$ loss, and the curve of observed count
rate versus the input count rate shall be reported (Figure 2-6).

### Technical Note

This test is very time-consuming, taking approximately two days to
complete. An alternative method is to use carefully calibrated copper
sheets as discussed in the following articles:

1\. \"A New Approach to NEMA Scintillation Camera Count Rate Curve
Determination,\" by E.M. Geldenhuys et al, J Nucl Med Vol. 29, No. 4,
April 1988 p. 538.

2\. \"Spectral Changes Affect Intrinsic Count Rate Tests,\" by Stephen
I. Breen / Trevor D. Cradduck, J Nucl Med Vol. 31, No. 12, December
1990, p. 2074.

Traceability of this method to the above standard must be demonstrated.

## INTRINSIC SPATIAL RESOLUTION AT 75,000 COUNTS PER SECOND

Intrinsic spatial resolution shall be measured at 75,000 counts per
second following the procedures and reporting requirements described in
Section 2.1 . Measured values of average FWHM and average FWTM shall be
reported. The measured values shall meet or exceed the specification.
The camera shall be tested in the appropriate clinical mode.

Note for discrete pixel cameras. The concept of intrinsic spatial
resolution as defined for single crystal cameras is not analogous, nor
directly applicable to that of discrete pixel cameras. The spatial
resolution of these systems may be characterized using the system
spatial resolution measurement described in Section 3.1 .

## INTRINSIC FLOOD FIELD UNIFORMITY AT 75,000 COUNTS PER SECOND

Intrinsic flood field uniformity shall be measured at 75,000 counts per
second. Integral and Differential Uniformity for both CFOV and UFOV
shall be calculated following the procedures and reporting of Section
2.4 . The measured values shall meet or exceed the specification. The
camera shall be tested in the appropriate clinical mode.

Note for discrete pixel systems. This test applies to discrete pixel
cameras. If necessary adjacent pixels may be summed to yield an
effective pixel size within the range specified. For those systems
unable to achieve an effective pixel size within the specified range the
pixel size employed shall be reported with the result. For those systems
with a fixed collimator the system shall be uniformly illuminated by a
sheet source. The presence of a collimator shall be reported as a
deviation along with the result. NU-1 2007

Page 23

# Section 3: TESTS OF GAMMA CAMERA DETECTORS WITH COLLIMATORS

## SYSTEM SPATIAL RESOLUTION WITHOUT SCATTER

The system spatial resolution without scatter shall be measured and
expressed as FWHM and FWTM of the line spread function. The measured
values shall meet or exceed the specification over the CFOV. Since the
measurement depends on the collimator, as well as the detector, the
measurement must be reported for each collimator type.

Note for discrete pixel systems. This test applies to discrete pixel
cameras. Minor adjustments to procedure are noted where appropriate
below.

### Test Conditions

The radionuclides employed for these measurements shall be those for
which the collimators were designed. The count rate shall not exceed
20,000 cps. For all radionuclides, an energy window recommended by the
manufacturer for the appropriate clinical mode shall be used.

### Test Equipment

The test equipment required for these measurements shall consist of two
capillary tubes with an inside diameter of less than or equal to
$1.0 \mathrm{~mm}$ and an active filled length of either
$120 \mathrm{~mm}$ or the longer dimension of the CFOV.

### Measurement Procedure

The capillary tubes shall be filled with the desired radionuclide. One
of these capillary tubes shall be positioned 100 mm from the face of the
collimator and along the axis of measurement, either $\mathrm{X}$ or
$\mathrm{Y}$.

The digital sampling perpendicular to the capillary tube shall be
$\leq 0.2 \mathbf{F W H M}$ and the digital sampling parallel to the
capillary tube shall be no greater than $30 \mathrm{~mm}$. If the data
are acquired in a two dimensional matrix, the data shall be summed
parallel to the direction of the slits to form line spread functions of
width $30 \mathrm{~mm}$ or less. At least 10,000 counts shall be
collected in the peak point of each line spread function defined by the
sampling parallel to the capillary tube.

Measure the FWHM and FWTM in pixels of all the line spread functions
that fall within the CFOV, first in the X direction and then in the
$\mathrm{Y}$ direction, using the method of Section 2.1.4 .

The millimeters per channel calibration factor shall be calculated as
described in Section 2.1.4 . If this measurement is not available, then
a second measurement for each axis may be performed with a second
capillary tube also positioned $100 \mathrm{~mm}$ from the face of the
collimator and $100 \mathrm{~mm}$ away from, and parallel to, the first
tube.

Note for discrete pixel systems. The measurement shall be made by
displacing the capillary tube in $1 \mathrm{~mm}$ steps over a distance
of at least $10 \mathrm{~mm}$ and over the width of at least two pixels'
pitch. If the specified pixel size may not be achieved the smallest
pixel size available shall be employed and reported as a deviation with
the results.

### Calculations and Analysis

Convert the FWHM and FWTM measurements from pixels to millimeters, using
the measured millimeter per pixel calibration factor from Section 2.1.4
. Average the measurements for both the $\mathrm{X}$ and $\mathrm{Y}$
directions.

Note for discrete pixel systems. For each direction the results from
measurements at each capillary position shall be averaged to yield the
final result.

### Reporting

System spatial resolution without scatter shall be reported as FWHM and
FWTM within the CFOV. The radionuclide employed shall also be reported.

## SYSTEM SPATIAL RESOLUTION WITH SCATTER

The system spatial resolution with scatter shall be measured and
expressed as FWHM and FWTM of the line spread function. The measured
values must meet or exceed the specification. Since the measurement
depends on the collimator, as well as the detector, the measurement must
be made with each collimator type.

Note for discrete pixel systems. This test applies to discrete pixel
cameras. Minor adjustments to procedure are noted where appropriate
below.

### Test Conditions

The radionuclides employed for these measurements shall be those for
which the collimators were designed. The count rate shall not exceed
20,000 cps through an energy window or windows recommended by the
manufacturer for the appropriate clinical mode. For other radionuclides
the energy settings recommended by the manufacturer shall be used.

### Test Equipment

The test equipment required for these measurements shall consist of two
capillary tubes with an inside diameter of less than or equal to
$1.0 \mathrm{~mm}$ and a length greater than $30 \mathrm{~mm}$. Also
required are two acrylic scattering blocks, at least 10X the estimated
FWTM for the collimator being tested or the size of the UFOV of the
system to be measured and 100 and $50 \mathrm{~mm}$ thick. The required
acrylic scattering thickness may be assembled from thinner pieces which
cover the required fraction of the FOV.

### Measurement Procedure

The measurements of system resolution are identical to those described
in Section 2-4, except that the $100 \mathrm{~mm}$ space between the
source and the detector is filled with scattering material, and there is
an additional $50 \mathrm{~mm}$ of scattering material behind the
source.

The capillary tubes shall be filled with the desired radionuclide. The
100 mm thick acrylic scattering block shall be positioned immediately in
front of the collimator and one of the capillary tubes shall be
positioned as close as possible on the opposite side of the block. The
other $50 \mathrm{~mm}$ thick scattering block shall be positioned on
the other side of the capillary tube.

The digital sampling resolution perpendicular to the tube shall be
$\leq 0.2 \mathbf{F W H M}$ and the digital sampling parallel to the
tube shall be no greater than 30 millimeters. At least 10,000 counts
shall be collected in the peak point of each linespread function.

\(c\) Copyright 2007 by the National Electrical Manufacturers
Association. NU-1 2007

Page 25

Measure the FWHM and FWTM in pixels of all the line spread functions
that fall within the CFOV, first in the X direction and then in the
$\mathrm{Y}$ direction, using the method described in Section 2.1.4.

The millimeters per channel calibration factor shall be calculated as
described in Section 2.1.4 . If this measurement is not available, then
a second measurement for each axis may be performed with a second
capillary tube also positioned $100 \mathrm{~mm}$ from the face of the
collimator and $100 \mathrm{~mm}$ away from, and parallel to, the first
tube.

Note for discrete pixel systems. The measurement shall be made by
displacing the capillary tube and scattering material in
$1 \mathrm{~mm}$ steps over a distance of at least $10 \mathrm{~mm}$ and
over the width of at least two pixels' pitch. If the specified pixel
size may not be achieved the smallest pixel size available shall be
employed and reported as a deviation with the results.

### Calculations and Analysis

Convert the FWHM and FWTM measurements from pixels to millimeters, using
the measured millimeter per pixel calibration factor. Average the
measurements in both the $\mathrm{X}$ and $\mathrm{Y}$ directions
together.

Note for discrete pixel systems. For each direction the results from
measurements at each capillary position shall be averaged to yield the
final result

### Reporting

System spatial resol ution without scatter shall be reported as FWHM and
FWTM within the CFOV. The collimator and the radionuclide employed shall
be also reported.

## SYSTEM PLANAR SENSITIVITY AND PENETRATION

The system planar sensitivity is the ratio of collimated counts detected
in one acquisition plane to the activity of a specific planar source
placed parallel to that plane. However, detected counts may also arise
from radiation that penetrates or scatters off the septa of the
collimator. This penetrated or scattered radiation degrades the overall
image quality and thus should be considered separately from the
sensitivity due to properly collimated counts. Both system planar
sensitivity and penetration depend on the collimator type, window width,
gamma energy, source configuration and system factors. Therefore, the
configuration of these system variables for the purpose of this
measurement should match those employed in an appropriate clinical mode
unless explicitly noted otherwise.

The planar sensitivity and penetration fraction of the system shall be
measured for each collimator type with the appropriate isotopes and
reported in cps/MBq and %.

This measurement relies on the accuracy of the calibration of the
radionuclide activity, and therefore the specification shall be for
typical devices of this model (see Section 1.3.4).

Note for discrete pixel systems. This test applies to discrete pixel
cameras.

### Test Conditions

The radionuclides employed for these measurements shall be those for
which the collimators are designed. The count rate shall be less than
30,000 counts per second through an energy window recommended by the
manufacturer for the appropriate clinical mode. If other radionuclides
are used, the energy settings used should be those recommended by the
manufacturer.

### Test Equipment

The test equipment required for this measurement consists of a $1-5$ cc
plastic syringe, a $30-50$ cc plastic syringe, a calibrated dose
calibrator, and a $150 \mathrm{~mm}$ diameter flat plastic dish (e.g.,
$150 \mathrm{~mm}$ x $15 \mathrm{~mm}$ nominal size standard Petri
dish). For small field of view cameras the diameter of the dish shall be
no more than the smallest dimension of the CFOV.

### Measurement Procedure

The flat plastic dish should be filled with water using the large
plastic syringe to at least completely cover the bottom of the dish to
2-3 mm depth. The source activity inside the small plastic syringe,
$\mathrm{A}_{\mathrm{SR}}$ shall be accurately measured using a dose
calibrator. This source shall then be dispersed from this syringe into
the flat plastic dish to complete the phantom preparation.

The residual activity remaining in the syringe, $A_{\text {Res }}$ shall
be promptly measured in the dose calibrator and the reading subtracted
from the original reading to obtain the amount of activity in the
phantom, $A_{C a l}=A_{S R}-A_{R e s}$, at the time of preparation.

Calibration methods shall be those set forth in the NRC Regulatory Guide
10.8, or alternatively NIST traceable calibration sources shall be used
as references with appropriate half-life corrections. The measurements
of syringe activity should be reproducible to better than 5%. All
measurement times should be recorded to at least the nearest minute, or
$1 \%$ the half-life of the radionuclide, whichever is more precise. A
consistent clock should be used for all time meas urements.

The prepared phantom shall be placed near the center of the field of
view and in a plane such that the bottom inside face of the phantom is
$10 \pm 1 \mathrm{~mm}$ from the face of the detector. It may be helpful
to determine this distance using a 10 mm spacer and an empty phantom. No
scatter material shall be present. It is critical that the base of the
phantom is level such that the activity is distributed evenly.

Acquire at least 4 million counts with the imaging system. All
count-adjusting uniformity corrections should be disabled. Record the
start time of the acquisition to the precision stated above. The
duration of the acquisition should be measured with a precision of
better than $1 \%$.

Repeat this measurement for the same number of counts with the bottom
inside face of the phantom $20 \pm 1,50 \pm 1,100$
$\pm 1,150 \pm 1,200 \pm 1,250 \pm 1,300 \pm 1,350 \pm 1$ and
$400 \pm 1 \mathrm{~mm}$ from theface of the collimator. The phantom
should be near the center of the field-of-view and parallel to the plane
of the detector for all measurements.

### Calculations and Analysis

For each acquisition sum the number of counts in a circular ROI which is
$60 \%$ of the diameter of the phantom and centered over the region of
activity. Include pixels with their centers within the ROI. Determine
the decay-corrected count rate for the $i^{\text {th }}$ acquisition as,

!\[\](https://cdn.mathpix.com/cropped/2023_02_08_3841e886d6af9a4bf71dg-18.jpg?height=134&width=896&top_left_y=2100&top_left_x=477)

Equation 3-1

where,

a\) $\quad R_{i} \quad$ decay-corrected count rate,

b\) $C_{i} \quad$ summed counts over the circular ROI in the
$i^{\text {th }}$ image.

c\) $T_{i} \quad$ start time of the $i$ 'th acquisition,

\(c\) Copyright 2007 by the National Electrical Manufacturers
Association. NU-1 2007

Page 27

d\) $T_{a c q, i}$ duration of the $i$ 'th acquisition,

e\) $T_{\text {cal }}$ time of the activity calibration,

f\) $T_{\text {half }}$ half life of radionuclide $(=21672 \sec$ for
Tc-99m).

Using a standard Levenberg-Marquardt non-linear least squares fit
technique (Refs. 1-2 listed in Section 3.3.6 ) fit the decay-corrected
count rates and the separation of the detector and the phantom to the
function,

$$R_{i}=c_{0}+c_{1} \exp \left(-c_{2} D_{i}\right), \quad \text { Equation 3-2 }$$

where $c_{0}, c_{1}$, and $c_{2}$ are fitting parameters and $D_{i}$ is
the distance from the face of the detector to the bottom of the phantom.
Compute the collimator penetration fraction $P F$ at $D_{N}$, where
$D_{N}=100 \mathrm{~mm}$,

$$P F=\frac{c_{1} \exp \left(-c_{2} D_{N}\right)}{c_{0}+c_{1} \exp \left(-c_{2} D_{N}\right)} .$$

Equation 3-3

To calculate sensitivity, sum over the entire image acquired with the
phantom $100 \mathrm{~mm}$ from the collimator. Calculate the
decay-corrected total count rate as,

!\[\](https://cdn.mathpix.com/cropped/2023_02_08_3841e886d6af9a4bf71dg-19.jpg?height=137&width=1056&top_left_y=1165&top_left_x=477)

Equation 3-4

where,

a\) $R t_{100}=$ decay-corrected count rate at $100 \mathrm{~mm}$,

b\) $C t_{100}=$ summed counts at $100 \mathrm{~mm}$.

Calculate the total systemsensitivity $S_{\text {Тот }}$ as,

$$S_{\text {TOT }}=\frac{R t_{100}}{A_{c a l}}$$

Equation 3-5

where $A_{\text {cal }}$ is the amount of radioactivity measured in the
phantom at time $T_{\text {cal }}$ after correcting for residual
activity in the syringe.

### Reporting

For each collimator and radionuclide $S_{\text {TOT }}$ shall be
reported in counts/sec/MBq, the collimator penetration factor $P F$
shall be reported as a percentage, and a scatter plot of $R_{I}$ versus
$D_{i}$ will be provided along with the exponential fit curve \[Equation
3-2\].

### Referenced Documents

1\. Bevington, P.R. 1969, Data Reduction and Error Analysis for the
Physical Sciences (New York: McGraw-Hill), Chapter 11.

2\. Press, W.H., Teukolsky, S.A., Vetterling, W.T., and Flannery, B.P.
1992, Numerical Recipes in C (Cambridge: Cambridge University Press),
Chapter 15.

\(c\) Copyright 2007 by the National Electrical Manufacturers
Association.

## DETECTOR SHIELDING

The detector shielding measurements assess the sensitivity of the gamma
camera detector to:

a\) Radioactivity in the patient being imaged which lies outside the
field of view.

b\) Stray sources of radiation that might be present in the vicinity of
the camera (e.g., patients in adjoining examination rooms or patients
awaiting examination who have been injected with a radioactive tracer).

To assess the effectiveness for case (a), measurements are made of the
leakage from a test source positioned outside the field of view in the
plane of the patient table. To assess the effectiveness of shielding for
stray sources, case (b), measurements are made of the count rates
obtained from sources positioned at two meters from the detector at the
side and in front of the system. The measured values of detector
shielding shall meet or exceed the specification.

Note for discrete pixel systems. This test applies to discrete pixel
cameras.

### Test Conditions

Measurements shall be made with Tc-99m and with the highest energy
nuclide for which the camera is specified to operate (or the highest
energy that is expected to be used). For each radionuclide tested the
appropriate clinical collimator shall be installed. The amount of
radioactivity shall be sufficient to generate a count rate of at least
1,000 cps and not more than 30,000 cps through the collimator at the
first imaging position (centered under the collimator).

For Tc-99m an energy window recommended by the manufacturer for the
appropriate clinical mode shall be used. For other radionuclides, the
manufacturer's recommended energy settings for the nuclide being tested
should be used. The collimator used shall be that recommended for
imaging the test isotope.

### Test Equipment

The test equipment required for this measurement consists of a 1 to 5 cc
plastic vial containing the radionuclide source.

### Measurement Procedure

a\) The unshielded source shall be placed on the imaging table under the
collimator (see Figure 3-1a). The detector shall be positioned
$20 \mathrm{~cm}$ above the table and facing down. The count rate shall
be measured at fixed positions starting with the source centered in the
Field of View, then at
$10 \mathrm{~cm}, 20 \mathrm{~cm}, 30 \mathrm{~cm}$ outside the edge of
the field of view, in each direction (seven measurements in all, as
shown in Figure 3-1a). At each source position, $i$, the number of
counts, $C A_{i}$, collected in time, $T A_{i}$, shall be recorded. For
each measurement, $C A_{i}$ shall be greater than 10,000. A background
count rate, $C B$, shall be a)

FRONT/SIDE VIEW

!\[\](https://cdn.mathpix.com/cropped/2023_02_08_3841e886d6af9a4bf71dg-20.jpg?height=223&width=606&top_left_y=1108&top_left_x=1159)

b\)

TOP VIEW

!\[\](https://cdn.mathpix.com/cropped/2023_02_08_3841e886d6af9a4bf71dg-20.jpg?height=814&width=665&top_left_y=1483&top_left_x=1135)

Figure 3-1

Source positions for shield leakage measurements.

NU-1 2007

Page 29

measured by collecting counts for one minute or longer.

b\) To assess the effectiveness of the shielding in relation to stray
sources two additional sets of measurements are required. A source
similar to that used in part a) is positioned two meters from the center
of the detector, directly in front of it (position $\mathrm{F}$ in
Figure 3-1b), and in the plane of the detector. The source may be
shielded as in Figure 2-5, with the open end of the shield pointing
directly toward the detector, as long as the entire detector is
illuminated by the source. The count rate shall be measured with the
detector positioned at each of 4 equally spaced positions in a
$360^{\circ}$ arc used for tomographic acquisitions (i.e., with the
detector facing up, down, left, and right). If the otated detector
positions may not be achieved then alternatively the source may be moved
keeping the same geometrical source-detector relationships. At each of
these positions the number of counts, $C F_{i}$, in the time $T F_{i}$,
is recorded.

The source and source holder is then positioned 2 meters from the center
of the detector at the side of the gantry (position S, in Figure 3-1b)
and in the plane of the detector. The source holder opening should be
pointed directly at the detector during the measurement. Measurements of
count rate are then made with the detector at three positions: with the
detector facing up, down, and away from the source. (The positions are
the same as those when the source is at position $\mathrm{F}$, but the
position where the detector is pointing toward the source is not used.)
At each of these positions the number of counts, $C S_{i}$, in the time
$T S_{i}$, is recorded.

For each measured count rate apply the appropriate half-life corrections
using the Equation 3-1.

For each of the source positions compute the background-subtracted count
rate:

$$\begin{array}{ll}
    B C_{i}=\left(C A_{i}-C B\right) / T A_{i} & \text { Equation 3-6 } \\
    B C F_{i}=\left(C F_{i}-C B\right) / T F_{i} & \text { Equation 3-7 } \\
    B C S_{i}=\left(C S_{i}-C B\right) / T S_{i} & \text { Equation 3-8 }
\end{array}$$

The shield leakage is expressed as the count rate (minus background) at
each position, as a percentage of the count rate (minus background) when
the source was in the central position $\left(B C_{0}\right)$ :

$$\begin{aligned}
    & L_{i}=100 \times B C_{i} / B C_{0} \\
    & L F_{i}=100 \times B F_{i} / B C_{0} \\
    & L S_{i}=100 \times B S_{i} / B C_{0}
\end{aligned}$$

Equation 3-9

Equation 3-10

Equation 3-11

The largest of the count rate measurements for each position shall be
identified; i.e., the largest of the $\mathrm{L}_{\mathrm{i}}$
(excluding $\mathrm{i}=0$ ), the largest of the $L F_{i}$ and the
largest of the $L S_{i}$, (excluding the three values where the detector
points towards the source).

### Reporting

The largest value of the $L i$ (excluding $\mathrm{i}=0$ ), $L F i$ and
$L S i$ for each radionuclide measured, shall be reported as the shield
leakage for that radionuclide. The collimator employed for each
measurement shall be stated. The measured values shall meet or exceed
the specification.

## SYSTEM COUNT RATE PERFORMANCE WITH SCATTER

The decaying source method shall be used to determine count rate
performance with scatter. Two parameters shall be (c) Copyright 2007 by
the National Electrical Manufacturers Association. measured and
reported: observed count rate for a $20 \%$ count loss and a maximum
count rate. Both parameters shall be measured with induced scatter. The
curve of observed versus input count rates shall be provided.

Specifications of Intrinsic Count Rate Performance with scatter shall be
typical of the model (see Section 1.3.4).

Note for discrete pixel systems. This test applies to discrete pixel
cameras.

### Test Conditions

The radionuclide employed for the test shall be Tc-99m. Any other
radionuclide(s) employed shall be separately reported.

The energy window for Tc-99m shall be that recommended by the
manufacturer for the appropriate clinical mode. For other radionuclides
the energy window used shall be that recommended by the manufacture.
Peaking shall be performed at a low count rate and shall not be manually
readjusted during the test. The camera shall be tested in the
appropriate clinical mode.

### Test Equipment

A camera under test shall have a low energy collimator mounted. The
source shall be in a water solution filling a disk container as shown on
Figure 3-3c. The source intensity shall be such that it produces an
input count rate that is larger than the count rate required to cause
fold-over in the observed count rate.

The source shall be placed within a plastic cylindrical phantom with
dimensions shown in Figure 3-2. (The phantom may be all acrylic, or may
be water filled. The well above the source holder is also filled with
acrylic or water.) NU-1 2007

Page 31

!\[\](https://cdn.mathpix.com/cropped/2023_02_08_6e7c85f3d3f75e48b91fg-03.jpg?height=1399&width=1211&top_left_y=391&top_left_x=434)

Figure 3-2

Phantom for measuring count rate performance in scatter.

### Measurement Procedure

The detector shall be positioned to view the $50 \mathrm{~mm}$ thick
plastic base of the phantom. The distance between the phantom and the
face of the collimator shall not be greater than $20 \mathrm{~mm}$. The
phantom shall be centered within the UFOV.

Prior to the beginning of the measurement, the background count rate,
$N_{b k g}$ shall be determined. The start $\left(t_{i}\right)$ and
elapsed time $\left(\Delta t_{i}\right)$ of the measurement shall be
recorded for each data point, where ( $i$ ) is the index of the data
point.

The time shall be measured relative to the start of acquisition time of
the measurement of the first data point. For each data point (Ci), at
least 100,000 counts shall be collected. Data should be acquired for 10
sec or 100,000 counts, whichever time is longer. The measurement should
be performed so that the points are taken as soon as the observed count
rate drops by 10,000 cps below the previous measured point. The last
$\left(\mathrm{n}^{\text {th }}\right)$ point taken should be measured
when an observed count rate drops below 4,000 cps.

### Calculations and Analysis

The observed count rate (OCRi) shall be determined for each data point
according to the formula given in Section 2.6.4 (Equations 2-5 to 2-8).

### Reporting

Typical (see Section 1.3.4 ) maximum observed count rate, observed count
rate at $20 \%$ loss, and the curve of observed count rate with scatter
versus the input count rate shall be reported. NU-1 2007

Page 33

# Section 4: TESTS OF GAMMA CAMERA TOMOGRAPHIC SYSTEMS

## SYSTEM ALIGNMENT

For SPECT imaging systems the transaxial alignment of acquired images
with the system's mechanical center of rotation is critical to the
accurate SPECT reconstruction. Likewise, for multi-head SPECT imaging
systems the axial alignment of images from the individual heads is
crucial. Both alignments shall be measured and reported in millimeters.

Many systems incorporate automatic alignment corrections into the image
acquisition process. These crrections may be enabled consistent with the
appropriate clinical mode.

The axial and rotational deviation values shall meet or exceed the
specification.

Note for discrete pixel systems. This test applies to discrete pixel
cameras.

### Test Conditions

Three Tc-99m or Co-57 point sources shall be used for these
measurements. The count rate shall not exceed 20,000 cps with an energy
window recommended by the manufacturer for the appropriate clinical mode
for Tc-99m or Co57. No table shall come between the sources and the
detector in any view.

### Test Equipment

Three point sources shall be positioned as defined in Figure 4-1. These
three point sources shall be made as spherically symmetric as possible
with a maximum dimension no larger than $5 \mathrm{~mm}$. The activity
!\[\](https://cdn.mathpix.com/cropped/2023_02_08_6e7c85f3d3f75e48b91fg-05.jpg?height=1030&width=658&top_left_y=705&top_left_x=1198)

Note: Point sources can be made by placing the tip of a capillary $t$
ube in the radionuclide solution. By holding the opposite end closed,
the tube may be removed with the point source

enclosed, and the tube sealed with a capillary tube sealer. of the point
sources may need to vary by less than $30 \%$ to avoid digital
saturation. High-resolution collimators should be employed for the
measurement.

### Measurement Procedure

Position the plane of the three point source holders parallel to the
plane of the table, with the central point source positioned on the axis
of rotation and centered in the field of view within
$\pm 5 \mathrm{~mm}$. The detectors should have a $20 \mathrm{~cm}$
radius of rotation. Automatic alignment corrections applied in the
appropriate clinical mode may be enabled. The pixel size should be set
to less than $5 \mathrm{~mm}$. Figure 4-1

Positions of the three co-planar point sources for measuring SPECT head
alignment and reconstructed

Images shall be acquired at an even number of gantry angles greater than
or equal to eight distributed evenly from $0^{\circ}$ to $360^{\circ}$.
Each detector must include an image acquired at $0^{\circ}$ and
$180^{\circ}$. The maximum pixel in the view at $0^{\circ}$ for each
point source image should contain no fewer than 5,000 counts.

### Calculations and Analysis

Sum each point source image over a $45 \mathrm{~cm}$ region of interest
centered over the point source in the y direction creating a
one-dimensional transverse profile of the Point Spread Function (PSF).
Calculate the centroid of that profile (see Section 2.5.4.1, Equation
2-3) and assign its value to $X_{i, j, m}$ the transverse location of
the i'th point of the j'th view for detector m. Likewise sum each ROI in
the x direction creating a one dimensional axial profile of the PSF.
Calculate the centroid of that profile and assign its value to
$Y_{i, j, m}$.

For each point on the detector calculate the center of rotation by
averaging $X_{i, j, m}$ over all views,

$$\operatorname{COR}_{i, m}=\frac{1}{N_{v}} \sum_{j=1}^{N_{v}} X_{i, j, m}$$

Equation 4-1

where $N_{v}$ is the number of views. Define the COR error for each
point and detector as,

$$\delta_{C O R, i, m}=\operatorname{abs}\left(C O R_{i, m}-x_{c e n}\right)$$

Equation $4-2$

where $X_{c e n}$ is the center of the image matrix size $N$ in the
$\mathrm{x}$ direction defined as,

$$X_{c e n}=\frac{N+1}{2}$$

Equation 4-3

For multi-headed systems calculate the COR deviation between each
pairing of heads as,

$$\delta_{C O R, i, m-n}=\operatorname{abs}\left(\operatorname{COR}{ }_{i, m}-\operatorname{COR}{ }_{i, n}\right)$$

Equation 4-4

In the axial direction for each point and detector, calculate the axial
deviation of the image by comparing the y position of the images
acquired with the detector at $0^{\circ}$ and $180^{\circ}$,

$$\delta_{A X I A L, i, m}=\max \left(y_{i, j, m}\right)-\min \left(y_{i, j, m}\right)$$

Equation 4-5

Calculate the relative axial misalignment of the heads as,

$$\delta_{A X I A L, i, m-n}=\frac{1}{N_{v}} \operatorname{abs} \sum_{i=1}^{\sum_{v}^{N_{v}}}\left(y_{i, j, m}-y_{i, j, n}\right)=$$

Equation 4-6

for each pairing of heads.

### Reporting

The following four values should be reported as upper bounds on the
system. NU-1 2007

Page 35

$$\begin{aligned}
    \delta_{C O R, 1} & =\max \left(\delta_{C O R, i, m}\right) \\
    \delta_{C O R, 12} & =\max \left(\delta_{C O R, i, m-n}\right) \\
    \delta_{A X I A L, 1} & =\max \left(\delta_{A X I A L, i, m}\right) \\
    \delta_{A X I A L, 12} & =\max \left(\delta_{A X I A L, i, m-n}\right)
\end{aligned}$$

All values should be reported in millimeters.

## SPECT RECONSTRUCTED SPATIAL RESOLUTION WITHOUT SCATTER

The reconstructed spatial resolution of the system shall be measured at
three specified points in air. FWHM values of resolution in the
$\mathrm{X}, \mathrm{Y}$ and $\mathrm{Z}$ direction for these three
points shall be reported. The measured values shall meet or exceed the
specification. Since the measurement depends on the collimator, as well
as the detector, the measurement must be reported for each collimator
type.

Note for discrete pixel systems. This test applies to discrete pixel
cameras.

### Test Conditions

Same as Section 3.1.1

### Test Equipment

Three thin-walled glass capillary tubes or equivalent (e.g., syringe
needles) with internal diameters of $1.0 \mathrm{~mm}$ or less shall be
used. The extent of the activity drop along the capillary shall not
exceed $2 \mathrm{~mm}$. The activity of the point sources may need to
vary by less than $30 \%$ to avoid digital saturation.

### Measurement Procedure

The points should be arranged in the center of the systems FOV as shown
in Figure 4-1. Position the plane of the three point source holders
parallel to the plane of the table, with the central point source
positioned on the axis of rotation and centered in the field of view
within $\pm 5 \mathrm{~mm}$. The radius of rotation for the circular
orbit shall be $150 \pm 5 \mathrm{~mm}$.

The data shall be collected and reconstructed in a matrix with an
effective pixel size of less than or equal to $2.5 \mathrm{~mm}$.

At least 20,000 total counts must be acquired in each projection angle
image utilizing step and shoot mode and a maximum $3^{\circ}$ projection
angle increment. The orbit must include projections over $360^{\circ}$.

### Calculations and Analysis

Three orthogonal slices, each containing an image of the three point
sources, shall be reconstructed from raw projection data using the
filtered back projection technique with a ramp filter. If, in addition,
other reconstruction techniques are used, they shall be specified. The
three slices are defined as: one $130 \pm 5 \mathrm{~mm}$ thick
transverse slice, centered on the middle point source; one
$180 \pm 5 \mathrm{~mm}$ thick sagittal, centered on the middle point
source; and one $30 \pm$ $5 \mathrm{~mm}$ thick coronal slice centered
on the line of the three point sources

### Analysis of Point Images

Each of these nine point source images contained in the three slices
shall be analyzed individually within a square ROI (region of interest)
centered on the maximum count pixel associated with this point. The
dimension of the square

\(c\) Copyright 2007 by the National Electrical Manufacturers
Association. ROI must be at least four times the anticipated FWHM to be
analyzed. Each point image shall be integrated in the image-Y direction
to determine the image- $X$ direction point spread function and
integrated in the image- $X$ direction to determine the image-Y
direction point spread function.

### FWHM (Full Width at Half Maximum) Calculations

The FWHM in image- $X$ and image- $Y$ for each of the above nine point
images shall be calculated according to the method described in Section
2.1.4 . Record these measured values in worksheet 41 for the central
point and on worksheet 4-2 for the peripheral points.

Worksheet 4-1 : Central Point Measurements

  Central Point
  ------------------ ------------- ------------- -------------
  Transverse Slice   $X_{c, t}=$   $Y_{c, s}=$   $Z_{c, s}=$
  Sagittal Slice                                 $Z_{c, c}=$
  Coronal Slice      $X_{c, c}=$

Worksheet 4-2 : Peripheral Point Measurements

!\[\](https://cdn.mathpix.com/cropped/2023_02_08_6e7c85f3d3f75e48b91fg-08.jpg?height=557&width=1195&top_left_y=1189&top_left_x=202)

Calculate the following five average resolutions:

$$\begin{array}{lr}
    \text { Central Transaxial } \equiv\left(X_{c, t}+X_{c, c}+Y_{c, t}+Y_{c, s}\right) / 4 & \text { Equation 4-8 } \\
    \text { Central Axial } \equiv\left(Z_{c, s}+Z_{c, c}\right) / 2 & \text { Equation 4-9 } \\
    \text { Peripheral Radial } \equiv\left(X_{p l, t}+X_{p l, c}+X_{p r, t}+X_{p r, c}\right) / 4 & \text { Equation 4-10 } \\
    \text { Peripheral Tangential } \equiv\left(Y_{p l, t}+Y_{p l, s}+Y_{p r, t}+Y_{p r, s}\right) / 4 & \text { Equation 4-11 } \\
    \text { Peripheral Axial } \equiv\left(Z_{p l, s}+Z_{p l, c}+Z_{p r, s}+Z_{p r, c}\right) / 4 & \text { Equation 4-12 }
\end{array}$$

### Reporting

The collimator used in each measurement shall be reported.

Report the five average FWHM values calculated by Equations 4-8 through
4-12 in units of mm.

$$\text { Central Transaxial (X,Y) }$$

\(c\) Copyright 2007 by the National Electrical Manufacturers
Association. Central Axial (Z):

Peripheral Radial (X):

Peripheral Tangential $(\mathrm{Y})$ :

Peripheral Axial (Z): $\mathrm{mm}$

$\mathrm{mm}$

$\mathrm{mm}$

$\mathrm{mm}$ NU-1 2007

Page 37

## SPECT RECONSTRUCTED SPATIAL RESOLUTION WITH SCATTER

The reconstructed transaxial spatial resolution shall be measured using
three line sources in a cylinder of water. The measured values shall
meet or exceed those specified.

Note for discrete pixel systems. This test applies to discrete pixel
cameras.

### Test Conditions

Tc-99m or Co-57 line sources shall be used with a photopeak energy
window recommended by the manufacturer for the appropriate clinical
mode. The count rate shall not exceed 20,000 cps.

### Test Equipment

The phantom shall consist of a water filled acrylic cylinder with an
inside diameter of $200 \mathrm{~mm}$ and containing three axial line
sources with a diameter of 1 $\mathrm{mm}$. This phantom is described in
Figure 4-2.

### Measurement Procedure

The specified phantom shall be aligned with the system's axis of
rotation within $\pm 2 \mathrm{~mm}$ and centered in the field of view.
The phantom shall be imaged using a $360^{\circ}$ circular orbit SPECT
acquisition of radius $150 \pm 5 \mathrm{~mm}$. The acquisition
reconstructed matrix size shall have an effective pixel size of less
than or equal to $2.5 \mathrm{~mm}$. At least 100,000 total counts must
be acquired in each projection angle image utilizing step and shoot mode
with a maximum $3^{\circ}$ angular increment.

### Calculations and Analysis

!\[\](https://cdn.mathpix.com/cropped/2023_02_08_6e7c85f3d3f75e48b91fg-10.jpg?height=594&width=585&top_left_y=1685&top_left_x=267)

One transverse slice, $10 \pm 3 \mathrm{~mm}$ in thickness, shall be
reconstructed

End View through the center of the phantom using the filtered back
projection technique with a ramp filter. If, in addition, other
reconstruction techniques are used, they shall be

!\[\](https://cdn.mathpix.com/cropped/2023_02_08_6e7c85f3d3f75e48b91fg-10.jpg?height=540&width=572&top_left_y=558&top_left_x=1393)
specified with the results. Two additional transverse slices, each
$10 \pm 3$ $\mathrm{mm}$ in thickness, shall also be reconstructed and
centered about $\pm 40$ $\mathrm{mm}$ from the center along the axis of
rotation.

The three reconstructed points in each of the three reconstructed slices
shall be analyzed individually with a square region of interest. Each
region of interest shall be centered on the maximum count pixel. The
size of this square region of interest must be at least four times the
anticipated FWHM of the count profile to be analyzed. For each point in
the images, the FWHM in X and Y shall be determined according to the
method described in Section 2.1.4 .

Referring to Figure 4-3, the average FWHM radial value of the six radial
measurements on the three slice images of the two peripheral sources
shall be calculated. Likewise, the average tangential FWHM value of the
six tangential NU-1 2007

Page 39

measurements on the images of the two peripheral sources shall be
calculated. Also, the average of the six measurements (three in the
$\mathrm{X}$ direction and three in the $\mathrm{Y}$ direction) for the
three images of the center source shall be calculated.

### Reporting

Three FWHM resolution values shall be reported, including one FWHM value
for the central source and two FWHM values for the peripheral sources
(one for the radial direction and one for the tangential direction). All
FWHM resolution values shall be reported in millimeters to the nearest
one tenth of millimeter. The starting angle and orbit for a cardiac
SPECT acquisition shall be reported.

## SYSTEM VOLUME SENSITIVITY

The system volume sensitivity (SVS) shall be measured and the average
volume sensitivity per axial centimeter (VSAC) determined from this
measurement. The SVS is the total system sensitivity to a uniform
concentration of activity in a specific cylindrical phantom. The VSAC
normalizes the SVS by the axial extent of the cylindrical phantom. The
VSAC multiplied by axial FOV of the system provides a useful
approximation of the total system response to a broad distribution of
activity. SVS and VSAC measurements are dependent on detector
configuration, collimator type, radionuclide type, energy window
setting, source configuration and other factors.

The values reported shall be typical of the system (see Section 1.3.4).

Note for discrete pixel systems. This test applies to discrete pixel
cameras.

### Test Conditions

The radionuclides employed for these measurements shall be those for
which the collimators were designed. The measurement count rate for each
projection image shall be $10,000 \pm 2000$ cps through a photopeak
energy window or windows recommended by the manufacturer for the
appropriate clinical mode. For other radionuclides, the manufacturer's
recommended energy settings for the nuclide being tested should be used.

### Test Equipment

The test equipment required for this measurement consists of a plastic
syringe, an accurate dose calibrator, and a specified $200 \mathrm{~mm}$
diameter cylindrical phantom, described in Figure 4-4.
!\[\](https://cdn.mathpix.com/cropped/2023_02_08_6e7c85f3d3f75e48b91fg-11.jpg?height=1034&width=476&top_left_y=936&top_left_x=1346)

Figure 4-4

Volume sensitivitv cvlindrical phantom

### Measurement Procedure

Accurately determine the activity concentration in
$\mathrm{kBq} / \mathrm{cm}^{3}$ within the specified cylindrical
phantom at initial time $\mathrm{T}_{\mathrm{i}}$. This is done by
dividing the measured activity placed in the phantom at
$\mathrm{T}_{\mathrm{i}}$ by the measured volume of water in the
phantom. This well mixed and uniform cylindrical source shall be
positioned in the center of the system's image space with its symmetry
axis coincident within $\pm 5 \mathrm{~mm}$ of the axis of rotation of
the SPECT system. Perform a $360^{\circ}$ circular orbit SPECT
acquisition of radius $150 \pm 5 \mathrm{~mm}$. At least 120 but not
more than 128 different projection angle images shall be acquired. The
acquisition time for each projection image shall be 10 seconds with an
energy window recommended by the manufacturer for the appropriate
clinical mode. For multi-head systems, the images from all heads may be
summed to achieve the required number of projection images. Field
uniformity correction devices, or any other mechanisms which alter the
number of counts in these projection images, must be disabled.

Measure the total elapsed time including time required to move between
views to complete the required $360^{\circ} \mathrm{SPECT}$ acquisition.
Also measure and sum the counts from all the projection images to
determine the total counts detected in this total elapsed time.

### Calculations and Analysis

Calculate the average counts per minute for the SPECT acquisition (A) by
dividing the total counts imaged by the total elapsed time. Calculate
the source activity concentration $\left(\mathrm{B}_{\mathrm{c}}\right)$
at time $\mathrm{T}$ halfway through the $360^{\circ} \mathrm{SPECT}$
acquisition by applying the proper source decay correction factor for
the radionuclide used.

The system volume sensitivity (SVS) is then:

$$S V S=\frac{A(c t s / \mathrm{sec})}{B_{c}\left(M B q / c m^{3}\right)}$$

Equation 4-13

The volume sensitivity per axial centimeter, VSAC, is then determined by
dividing the SVS by the axial length of the cylindrical source (i.e.,
$20 \mathrm{~cm}$ ).

$$V S A C=\frac{\text { SVS }}{\text { Length }}$$

Equation 4-14

If the total length of the source cannot be used to obtain the volume
sensitivity measurement, the actual length used must be stated along
with the results.

### Reporting

Report the system volume sensitivity (SVS) in counts per second per
MegaBecquerel per cubic centimeter, (cts/sec)/(MBq/
$\left.\mathrm{cm}^{3}\right)$. Report the volume sensitivity per axial
centimeter (VSAC) in counts per second per MegaBecquerel per square
centimeter,
$(\mathrm{cts} / \mathrm{sec}) /\left(\mathrm{MBq} / \mathrm{cm}^{2}\right)$.
Report separate values of the SVS and the VSAC for each radionuclide and
collimator type. If no radionuclide is reported, then Tc-99m is assumed.
Also state the method of acquisition (continuous, step-and-shoot, or
other).

## DETECTOR-DETECTOR SENSITIVITY VARIATION

In multi-detector gamma camera systems, the Detector-Detector
Sensitivity Variation is the relative difference in sensitivity of the
individual detectors assessed in tomographic mode. The values reported
shall be typical of the model (see Section 1.3.4)

Note for discrete pixel systems. This test applies to discrete pixel
cameras.

### Test Equipment

Measurements shall be made using the phantom described in the section on
Vblume Sensitivity (Section $4.4$ ) and illustrated in Figure 4-4.

\(c\) Copyright 2007 by the National Electrical Manufacturers
Association. NU-1 2007

Page 41

The sources shall be configured as described in Section 4.4 , System
Volume Sensitivity.

### Measurement Procedure

A tomographic acquisition of the phantom shall be performed with data
collected from all detectors. The acquisition shall extend over the full
rotational range for each detector, with no greater than 12 degree
angular sampling. The images for each detector shall be equally spaced
over the rotational range. Each projection image shall contain
$100,000 \pm 20,000$ counts with an energy window recommended by the
manufacturer for the appropriate clinical mode.

If the data are collected correctly, the same data can be used for this
test and for measuring Volume Sensitivity.

### Calculations and Analysis

The raw (unprocessed) projection images are used for the analysis. All
of the projection images collected using

!\[\](https://cdn.mathpix.com/cropped/2023_02_08_6e7c85f3d3f75e48b91fg-13.jpg?height=46&width=1590&top_left_y=962&top_left_x=233)
summed to form Sum, and so on for each detector.

The total counts in each of the Sum images are computed:

$$C_{i}=\text { Total Counts in the } i^{\text {th }} \text { Sum image }$$

Equation 4-15

The difference between the largest of the $C_{i}$ and the smallest of
the $C_{i}$ is expressed as a percentage of the largest value:

$$D D S=100 \times\left(C_{\max }-C_{\min }\right) / C_{\max }$$

Equation 4-16

### Reporting

For a multi-detector system, maximal percentage sensitivity difference
between a pair of detectors, DDS, is reported as Detector-Detector
Sensitivity Variation.

# Section 5: TESTS OF GAMMA CAMERA WHOLE-BODY SCANNING SYSTEMS

## WHOLE-BODY SYSTEM SPATIAL RESOLUTION WITHOUT SCATTER

System spatial resolution without scatter shall be measured parallel and
perpendicular to the direction of continuous motion, and expressed as
FWHM (full width at half maximum) and FWTM (full width at tenth maximum)
of the line spread function. The measured values shall meet or exceed
the specification. This measurement does not apply to step-and-shoot
whole-body planar acquisition.

Note for discrete pixel systems. This test applies to discrete pixel
cameras.

### Test Conditions

The radionuclide to be employed for this measurement shall be Tc
$-99 \mathrm{~m}$. Any other radionuclide(s) employed shall be
separately reported. The activity of the source shall be adjusted to
yield a count rate between 10,000 and 20,000 cps through an energy
window recommended by the manufacturer for the appropriate clinical
mode, with two capillary tubes in the detector field of view. The camera
shall be equipped with a collimator.

### Test Equipment

The sources shall consist of two capillary tubes, each having an inside
diameter less than or equal to $1.0 \mathrm{~mm}$ and an active filled
length of at least $120 \mathrm{~mm}$, placed on the whole-body scanning
table, parallel to the plane of the detector, so that the resolution
measurements can be calibrated in units of millimeters $(\mathrm{mm})$.
{Hasegawa

As in Section 3.2 , most newer cameras automatically determine the pixel
size and there is no need to perform the pixel calibration during this
test. I recommend that the two-source pixel calibration only be used if
the pixel size is unknown/in doubt.

The millimeters per channel calibration factor shall be calculated as
described in Section 2.2.4 . If this measurement is not available, then
a

!\[\](https://cdn.mathpix.com/cropped/2023_02_08_6e7c85f3d3f75e48b91fg-14.jpg?height=716&width=534&top_left_y=1084&top_left_x=1275)

\(a\)

Figure 5-1

Source position for whole body resolution moscuramante second
measurement for each axis may be performed with a second capillary tube
also positioned $100 \mathrm{~mm}$ from the face of the collimator and
$100 \mathrm{~mm}$ away from, and parallel to, the first tube.

### Resolution Parallel to the Direction of Motion

One capillary tube shall be placed at the center of the scanned field of
view to within $1 \mathrm{~mm}$, perpendicular to the direction of
motion. The second source shall be placed parallel to the first one, at
a distance of $100 \mathrm{~mm}$, as shown in Figure 5-1a.

### Resolution Perpendicular to the Direction of Motion

One capillary tube shall be placed at the center of the scanned field of
view, parallel to the direction of motion to

\(c\) Copyright 2007 by the National Electrical Manufacturers
Association. NU-1 2007

Page 43

within $1 \mathrm{~mm}$. The second source shall be placed parallel to
the first one, at a distance of $100 \mathrm{~mm}$, as shown in Figure
5-1b.

### Measurement Procedure

a\. Scan speed-The scan speed shall be in the range recommended for
clinical use.

b\. Camera position-Scans shall be performed with the detector both
above and below the table for the two source orientations as described
in Section 3.1.2 . The camera shall be positioned at a distance of 100
millimeters from the sources to the face of the collimator.

c\. Digital sampling-The digital sampling perpendicular to the tubes
shall be no less than $0.25$ of the FWHM of the system resolution of the
collimator being used. The digital resolution parallel to the tubes
shall be no less than 25 $\mathrm{mm}$ and no more than
$30 \mathrm{~mm}$.

### Calculation and Analysis

The average millimeters/pixel shall be calculated from the known line
spacing. This calculation shall be done separately, both in the parallel
and perpendicular directions to the direction of the motion. The FWHM
and FWTM shall be calculated in each segment of the central capillary
tube, using the method of Section 2.1.4 . The values of the FWHM and
FWTM shall be averaged separately for the tubes parallel and
perpendicular to the direction of motion.

### Reporting

Average FWHM and FWTM shall be reported. The reported values shall be
the average of the measurements acquired above and below the table.
Parallel and perpendicular resolution shall be reported separately.

The collimator and scan speed used in performing the measurement shall
be reported.

### Rationale

The performance of whole body scanning systems depends not only on the
intrinsic and system performance of the camera, but also on the
performance and alignment of the scanning mechanism. The tests are aimed
at measuring the performance of these aspects of the system.

Most problems associated with whole body scanning systems will affect
the spatial resolution. Resolutions parallel and perpendicular to the
direction of motion are reported separately, as they are controlled by
different mechanisms. The resolution parallel to the direction of
motion, measured with line sources perpendicular to that direction, is
affected by the motion control, camera scale calibration and collimator
quality. The perpendicular resolution, measured with line sources
parallel to the direction of motion, is affected primarily by the
mechanical alignment of the camera and the table.

