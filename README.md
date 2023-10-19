# Inversion_FreeAnalysis_VoxHumanHeadModel
The voxelized human head model has a,
+ Total 2342077 Hex-elements 
+ Total 2413351 Nodes

## Details of Data Structure for Nodes and Elements 
The voxelized mesh data is in the folder [Mesh_Data_(.mat files)](https://github.com/CompMechPitt/Inversion_FreeAnalysis_VoxHumanHeadModel/tree/main/Mesh_Data_(.mat%20files)). The data is saved in the .mat format which can be loaded easily into MATLAB. 

### Elements 
The element matrix size is 2342077 x 10. The details of the each coloumn are as follows ([Figure A](#figa)),
+ Coloumn 1: Element number
+ Coloumn 2: Part number. The details of each part can be found in the next section. Below is the list of parts,
    - Part 1: Left Cerebral White Matter
    - Part 2: Right Cerebral White Matter
    - Part 3: Left Cerebellum White Matter
    - Part 4: Right Cerebellum White Matter
    - Part 5: Left Cerebral Grey Matter
    - Part 6: Right Cerebral Grey Matter
    - Part 7: Ventricles
    - Part 8: Left Cerebellum Grey Matter
    - Part 9: Right Cerebellum Grey Matter 
    - Part 10: Mid Brain
    - Part 11: Corpus Callosum
    - Part 12: Brain Stem
    - Part 13: CSF
    - Part 14: Dura
    - Part 15: Skull
    - Part 16: Remaining elements 
+ Column 3 to 10: Connectivity of hexahedral element (trilinear 8-noded)

![Figure A: Element matrix structure](https://github.com/CompMechPitt/Inversion_FreeAnalysis_VoxHumanHeadModel/blob/main/Images/Element_Matrix.PNG)<!-- Label: figa -->

<h3 align="center"><strong>Figure A: Element matrix structure</strong></h3>

### Nodes 
The node matrix size is 2313351 x 3. The details of the each coloumn are as follows ([Figure B](#figb)),
+ Coloumn 1: Node number
+ Column 2 to 4: X, Y, Z Coordinates (in meters)

![Figure B: Node matrix structure](https://github.com/CompMechPitt/Inversion_FreeAnalysis_VoxHumanHeadModel/blob/main/Images/Node_Matrix.PNG)<!-- Label: figb -->

<h3 align="center"><strong>Figure A: Element matrix structure</strong></h3>

## Details of Brain Tissue Components in the "VoxHumanHeadModel"

1. __Left Cerebral White Matter__ ([Figure1](#fig1) below: In Green color)
    - 264569 (Total Number of voxel/hex elements)
    - 343519 (Total Number of nodes) 
2. __Right Cerebral White Matter__ ([Figure1](#fig1) below: In Light Red color)
    - 260683 (Total Number of voxel/hex elements)
    - 339361 (Total Number of nodes) 

![Figure 1: Left Cerebral White Matter](https://github.com/CompMechPitt/Inversion_FreeAnalysis_VoxHumanHeadModel/blob/main/Images/Left_Right_Cerebral_White_Matter.PNG) <!-- fig1 -->

<h3 align="center"><strong>Figure 1: Left Cerebral White Matter</strong></h3>

3. __Left Cerebellum White Matter__ ([Figure2](#fig2) below: In Yellow color)
    - 17616 (Total Number of voxel/hex elements)
    - 22724 (Total Number of nodes) 
4. __Right Cerebellum White Matter__ ([Figure2](#fig2) below: In Blue color)
    - 17483 (Total Number of voxel/hex elements)
    - 22549 (Total Number of nodes) 

![Figure 2: Left Right Cerebellum White Matter](https://github.com/CompMechPitt/Inversion_FreeAnalysis_VoxHumanHeadModel/blob/main/Images/Left_Right_Cerebellum_White_Matter.PNG)<!-- Label: fig2 -->

<h3 align="center"><strong>Figure 2: Left Right Cerebellum White Matter</strong></h3>

5. __Left Cerebral Grey Matter__ ([Figure 3](#fig3) : In Brown color)
    - 252966 (Total Number of voxel/hex elements)
    - 391404 (Total Number of nodes)

![Figure 3: Left Cerebral Grey Matter](https://github.com/CompMechPitt/Inversion_FreeAnalysis_VoxHumanHeadModel/blob/main/Images/Left_Cerebral_Grey_Matter.PNG)<!-- Label: fig3 -->

<h3 align="center"><strong>Figure 3: Left Cerebral Grey Matter</strong></h3>

6. __Right Cerebral Grey Matter__ ([Figure 4](#fig4) : In Grey color)
    - 250301 (Total Number of voxel/hex elements)
    - 289379 (Total Number of nodes) 

![Figure 4: Right Cerebral Grey Matter](https://github.com/CompMechPitt/Inversion_FreeAnalysis_VoxHumanHeadModel/blob/main/Images/Right_Cerebral_Grey_Matter.PNG)<!-- Label: fig4 -->

<h3 align="center"><strong>Figure 4: Right Cerebral Grey Matter</strong></h3>

7. __Ventricles__ ([Figure 5](#fig5) : In Blue color)
    - 10769 (Total Number of voxel/hex elements)
    - 17924 (Total Number of nodes) 

![Figure 5: Ventricles](https://github.com/CompMechPitt/Inversion_FreeAnalysis_VoxHumanHeadModel/blob/main/Images/Ventricles.PNG)<!-- Label: fig4 -->

<h3 align="center"><strong>Figure 5: Ventricles</strong></h3>

8. __Left Cerebellum Grey Matter__ ([Figure6](#fig6) below: In Green color)
    - 52197 (Total Number of voxel/hex elements)
    - 63838 (Total Number of nodes) 
9. __Right Cerebellum Grey Matter__ ([Figure6](#fig6) below: In Pink color)
    - 54631 (Total Number of voxel/hex elements)
    - 66196 (Total Number of nodes) 

![Figure 6: Left Right Cerebellum Grey Matter](https://github.com/CompMechPitt/Inversion_FreeAnalysis_VoxHumanHeadModel/blob/main/Images/Left_Right_Cerebellum_Grey_Matter.PNG)<!-- Label: fig6 -->

<h3 align="center"><strong>Figure 6: Left Right Cerebellum White Matter</strong></h3>

10. __Mid Brain__ ([Figure7](#fig7) below: In CyanGreen color)
    - 67838 (Total Number of voxel/hex elements)
    - 86617 (Total Number of nodes) 

![Figure 7: Mid Brain](https://github.com/CompMechPitt/Inversion_FreeAnalysis_VoxHumanHeadModel/blob/main/Images/Mid_Brain.PNG)<!-- Label: fig7 -->

<h3 align="center"><strong>Figure 7: Mid Brain</strong></h3> 

11. __Corpus Callosum__ ([Figure8](#fig8) below: In Red color)
    - 2835 (Total Number of voxel/hex elements)
    - 4305 (Total Number of nodes) 

![Figure 8: Corpus Callosum](https://github.com/CompMechPitt/Inversion_FreeAnalysis_VoxHumanHeadModel/blob/main/Images/Corpus_Callosum.PNG)<!-- Label: fig8 -->

<h3 align="center"><strong>Figure 8: Corpus Callosum</strong></h3> 

12. __Brain Stem__ ([Figure9](#fig9) below: In Golden color)
    - 21519 (Total Number of voxel/hex elements)
    - 25819 (Total Number of nodes) 

![Figure 9: Brain Stem](https://github.com/CompMechPitt/Inversion_FreeAnalysis_VoxHumanHeadModel/blob/main/Images/Brain_Stem.PNG)<!-- Label: fig9 -->

<h3 align="center"><strong>Figure 9: Brain Stem</strong></h3> 

13. __CSF__ ([Figure10](#fig10) below: In GrayishBlue color)
    - 431872 (Total Number of voxel/hex elements)
    - 689600 (Total Number of nodes) 

![Figure 10: CSF](https://github.com/CompMechPitt/Inversion_FreeAnalysis_VoxHumanHeadModel/blob/main/Images/CSF.PNG)<!-- Label: fig10 -->

<h3 align="center"><strong>Figure 10: Cut Section of CSF</strong></h3> 

14. __Dura__ ([Figure11](#fig11) below: In LightGreen color)
    - 158989 (Total Number of voxel/hex elements)
    - 303239 (Total Number of nodes) 

![Figure 11: Dura](https://github.com/CompMechPitt/Inversion_FreeAnalysis_VoxHumanHeadModel/blob/main/Images/Dura.PNG)<!-- Label: fig11 -->

<h3 align="center"><strong>Figure 11: Cut Section of Dura</strong></h3> 

15. __Skull__ ([Figure12](#fig12) below: In Brown color)
    - 477495 (Total Number of voxel/hex elements)
    - 610152 (Total Number of nodes) 

![Figure 12: Dura](https://github.com/CompMechPitt/Inversion_FreeAnalysis_VoxHumanHeadModel/blob/main/Images/Skull.PNG)<!-- Label: fig12 -->

<h3 align="center"><strong>Figure 12: Cut Section of Skull</strong></h3> 

16. __Remaining Elements__ ([Figure13](#fig13) below: In Green color)
    - 314 (Total Number of voxel/hex elements)
    - 1611 (Total Number of nodes) 

![Figure 13: Dura](https://github.com/CompMechPitt/Inversion_FreeAnalysis_VoxHumanHeadModel/blob/main/Images/Remaining_Elements.PNG)<!-- Label: fig13 -->

<h3 align="center"><strong>Figure 13: Remaining Elements</strong></h3> 