# Additional materials for EPS poster presentation, January 2023
Thank you for taking the time to view our poster and for following the link to the supplementary materials.

## PCA space demonstrations
These animations depict the first 3 dimension of a face space constructed using principal component analysis (PCA). At the centre of space is the average face. Scaling along each of the components we can see how the face changes in shape and texture from average, with increasing distance from the average magnifying this difference. The ‘high_caric’ version shows how faces can become heavily caricatured simply by increasing the scaling factor applied to the weights on each component.

Moderate caricature level:

https://user-images.githubusercontent.com/58479570/207362995-19e038c5-d1b6-4bc7-97d9-8edf872ea094.mp4

<video src="https://user-images.githubusercontent.com/58479570/207362995-19e038c5-d1b6-4bc7-97d9-8edf872ea094.mp4" controls="controls" style="max-width: 730px;">
</video>

High caricature level:

https://user-images.githubusercontent.com/58479570/207363667-3d188872-7cd5-4f3d-98f5-5e08361fa48a.mp4

## Example stimulus animation in behavioural study
The video shows an example of one animation shown to the participant at the start of a trial in the behavioural experiment. On each trial one principal component was manipulated. The face starts close to average, is heavily caricatured, and then returns to average. The maximal amount of caricaturing varies across trials, so on some trials the face will become slightly more caricatured that on other trials. The aim of these animations is to show the full range of caricaturing for the trial. This also serves to pre-expose participants with heavily caricatured stimuli before the fMRI scans. 

https://user-images.githubusercontent.com/58479570/207365431-cfcc8633-9742-4597-be38-78d23050998b.mp4

<br/>
<br/>

## Supplementary figures

<br/>

![Creating_Stimuli_DevVecs](https://user-images.githubusercontent.com/58479570/207366475-7a87c35a-c9e8-4cf4-aa2d-cd1aac6c413b.jpg)

**Supplementary Figure 1.** Creating stimuli by adding deviation vectors to the origin of face space. Stimuli were created by adding texture and shape deviations to the image corresponding to the origin of the PCA-based face space. The texture deviation stores how much of each RGB channel is to be added to the average face for each pixel. Note that for easier visualisation the RGB changes have been exaggerated here. The x-y warp fields contain the horizontal (x) and vertical (y) pixel displacements necessary to distort the average face shape. Lighter areas show leftward and upward displacements, while darker areas show rightward and downward displacements.  

<br/>

![Group_Naturalness_Boundaries_1Col](https://user-images.githubusercontent.com/58479570/207366906-09066611-0fe8-4670-b27d-66cb00bfcfb2.jpg)

**Supplementary Figure 2.** Group average naturalness boundaries. Stimuli representing the average transition point for the first seven participants between natural, physically plausible and unnatural, physically implausible. Rows, two directions (sign) in PCA space for each gender. Columns, five principal components scaled according to the transition points. Numbers, average transition point in terms of the number of standard deviations in PCA space (with respect to the input data) along the given component. Numbers in parentheses, the between-subjects standard deviation from the behavioural results.  

<br/>

![localiser_stimuli](https://user-images.githubusercontent.com/58479570/207367476-f94a8adf-e304-435b-b9f7-efde41fb43c1.jpg)

**Supplementary Figure 3.** Example stimuli for the localiser scan showing faces, objects, manmade scenes and natural scenes. Manmade and natural scenes formed one block type encompassing scenes as a whole.

<br/>

![Defining_FFA_Ventral_2Col](https://user-images.githubusercontent.com/58479570/207367638-4ba457d8-7915-45d3-bc52-8b64398b7d36.jpg)

**Supplementary Figure 4.** Defining the FFA in all participants. The two leftmost images depict the current view, with images taken from underneath the ventral surface. The left and right image of each pair show the left and right hemispheres respectively. The images S1-S9 show the FFA definition in each participant (the region surrounded by the black border). The statistical maps show the face-selective regions defined by the contrast faces > objects + scenes that survived FWE correction. Maps show the z-values of the contrasts.  

<br/>

![violin_plots](https://user-images.githubusercontent.com/58479570/207368151-d2c2bd99-0301-4467-a021-f701dcd09e25.JPG)

**Supplementary Figure 5.** Violin plots to show the distribution of responses to faces (red), objects
(blue) and scenes (green) compared to baseline (t-value of the contrast). (A-C) The responses in
the face-selective, object-selective and scene-selective voxels of the left temporal cortex. (D-F)
The responses in the right temporal cortex. Above the zero-line show greater responses to the
stimuli than baseline, beneath show inhibited responses to the stimuli compared to baseline. ROIs
were defined by contrasting the response between different stimulus classes, e.g., face-selective
was defined as voxels responding significantly more to faces than objects and scenes. Voxels that
responded significantly in more than one of these contrasts were excluded.  

<br/>
<br/>

## Contact
Follow me on twitter [@Ryan_J_Elson](https://twitter.com/Ryan_J_Elson)

Email: ryan.elson@nottingham.ac.uk

<br/>

## References
Bao, P., She, L., McGill, M., & Tsao, D. Y. (2020). A map of object space in primate inferotemporal cortex. Nature, 583(7814), 103-108. https://doi.org/10.1038/s41586-020-2350-5

Carlin, J. D., & Kriegeskorte, N. (2017). Adjudicating between face-coding models with individual-face fMRI responses. PLoS computational biology, 13(7), e1005604. https://doi.org/10.1371/journal.pcbi.1005604

Chang, L., & Tsao, D. Y. (2017). The code for facial identity in the primate brain. Cell, 169(6), 1013-1028. https://doi.org/10.1016/j.cell.2017.05.011

McKone, E., Jeffery, L., Boeing, A., Clifford, C. W., & Rhodes, G. (2014). Face identity aftereffects increase monotonically with adaptor extremity over, but not beyond, the range of natural faces. Vision Research, 98, 1-13. https://doi.org/10.1016/j.visres.2014.01.007

Nagle, F., Griffin, H., Johnston, A., McOwan, P. (2013). Techniques for Mimicry and Identity Blending Using Morph Space PCA, in: Park, J.-I., Kim, J. (Eds.), Computer Vision - ACCV 2012 Workshops, Lecture Notes in Computer Science. Springer, Berlin, Heidelberg, pp. 296–307. https://doi.org/10.1007/978-3-642-37484-5_25

Parvizi, J., Jacques, C., Foster, B. L., Withoft, N., Rangarajan, V., Weiner, K. S., & Grill-Spector, K. (2012). Electrical stimulation of human fusiform face-selective regions distorts face perception. Journal of Neuroscience, 32(43), 14915-14920. https://doi.org/10.1523/JNEUROSCI.2609-12.2012

Rhodes, G., Brennan, S., & Carey, S. (1987). Identification and ratings of caricatures: Implications for mental representations of faces. Cognitive psychology, 19(4), 473-497. https://doi.org/10.1016/0010-0285(87)90016-8

Valentine, T. (1991). A unified account of the effects of distinctiveness, inversion, and race in face recognition. The Quarterly Journal of Experimental Psychology Section A, 43(2), 161-204. https://doi.org/10.1080/14640749108400966



