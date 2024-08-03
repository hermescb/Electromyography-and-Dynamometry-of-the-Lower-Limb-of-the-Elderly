1. Title: Electromyography and Dynamometry of the Lower Limb of the Elderly

2. Citation of the following article is required if you use this dataset for research purposes.

	2.1. Bibtex format

		@article{DASILVA2024105635,
		title = {Electromyography and dynamometry in the prediction of risk of falls in the elderly using machine learning tools},
		journal = {Biomedical Signal Processing and Control},
		volume = {88},
		pages = {105635},
		year = {2024},
		issn = {1746-8094},
		doi = {https://doi.org/10.1016/j.bspc.2023.105635},
		url = {https://www.sciencedirect.com/science/article/pii/S1746809423010686},
		author = {D. A. Silva and N. F. L. {Castelo Branco} and L. S. {Andrade Mesquita} and H. M. G. {Castelo Branco} and G. A. Barreto},
		}

	2.2 General format

		D. A. Silva and N. F. L. {Castelo Branco} and L. S. {Andrade Mesquita} and H. M. G. {Castelo Branco} and G. A. Barreto (2024). "Electromyography and dynamometry in the prediction of risk of falls in the elderly using 		machine learning tools", Biomedical Signal Processing and Control, vol. 88, pages 105635. DOI: 10.1016/j.bspc.2023.105635.

3. Relevant Information:   
   3.1 Protocol:
       30 volunteers aged between 64 and 82 were recruited from the community and initially assessed with the Berg balance scale. Then, after skin asepsis, bipolar electrodes were attached to the motor points of four muscles of the dominant lower limb of each participant: vastus lateralis, biceps femoris, tibialis anterior and gastrocnemius lateralis. The signal collection of each muscle occurred as follows:
	For the vastus lateralis muscle, the participant was asked to sit in a chair and to position the back adequately to avoid compensation from other muscles, with the knee at a 90° angle. At the same time, one end of the load cell was positioned on the volunteer's ankle with the aid of a strap and the other was attached to a stable metal structure behind the participant. The participants were asked to stretch the knee and maintain this position for 10 seconds.
	For the biceps femoris muscle, the participant was kept in the sitting position and the dynamometer was fixed to a stable metal structure in front of the participant. The participant was then asked to bend the knee, keeping the contraction for 10 seconds.
	For the tibialis anterior muscle, the participant was positioned in dorsal decubitus on a platform with one end of the dynamometer positioned on the foot with the aid of the strap and the other end fixed to a stable metallic structure anterior to the sole of the volunteer's foot . The participants were asked to perform the movement of taking the tip of the foot up and maintain the contraction for 10 seconds.
	For the lateral gastrocnemius muscle, the supine position was maintained and the dynamometer had one end fixed to a stable metallic structure posterior to the top of the volunteer's head. The volunteer was asked to perform the movement of bringing the tip of the foot down and maintaining it for 10 seconds.
	All electrodes were active regardless of whether the muscle test being performed was specific for a given muscle.

   3.2 Instrumentation:
       To obtain the myoelectric signal, the EMG System SAS1000 V8 system (EMG System, Brazil) was used. This electromyograph is capable of collecting up to six channels simultaneously with a sampling frequency of 2,000 Hz, a bandpass filter of 20-500 Hz and a 12-bit analog-to-digital converter. For the assessment of muscle strength, a compression and traction load cell (dynamometer) from the same manufacturer, with a reading capacity of up to 200 kgf, was used, which could be used in sync with the electromyograph.


4. Attribute Information:

The data are separated by individuals, in which each file contains matrices named as DNM, EMG_VL, EMG_BF, EMG_TA and EMG_GL. Each is organized as follows:

DNM:
Matrix with 4 columns, where each column corresponds to the dynamometry of a lower limb muscle.
Column 1: Vastus lateralis Dynamometry;
Column 2: Biceps Femoris Dynamometry;
Column 3: Tibialis Anterior Dynamometry;
Column 4: Lateral Gastrocnemius Dynamometry;

EMG_VL:
Matrix with 4 columns, where each column corresponds to the active channel in each muscle of the lower limb during isometry of the Vastus Lateralis muscle.
Column 1: Vastus Lateralis Channel;
Column 2: Biceps Femoris Channel;
Column 3: Tibialis Anterior Channel;
Column 4: Lateral Gastrocnemius Channel;

EMG_BF:
Matrix with 4 columns, where each column corresponds to the active channel in each muscle of the lower limb during the isometry of the Biceps Femoris muscle.
Column 1: Vastus Lateralis Channel;
Column 2: Biceps Femoris Channel;
Column 3: Tibialis Anterior Channel;
Column 4: Lateral Gastrocnemius Channel;

EMG_TA:
Matrix with 4 columns, where each column corresponds to the active channel in each muscle of the lower limb during isometry of the Tibialis Anterior muscle.
Column 1: Vastus Lateralis Channel;
Column 2: Biceps Femoris Channel;
Column 3: Tibialis Anterior Channel;
Column 4: Lateral Gastrocnemius Channel;

EMG_LG:
Matrix with 4 columns, where each column corresponds to the active channel in each muscle of the lower limb during isometry of the Lateral Gastrocnemius muscle.
Column 1: Vastus Lateralis Channel;
Column 2: Biceps Femoral Channel;
Column 3: Tibialis Anterior Channel;
Column 4: Lateral Gastrocnemius Channel;


In addition, an extra file (Demographic Data) is included in the dataset with demographic data and the outputs of each individual based on the Berg Balance Scale. This file has 30 rows, which correspond to each evaluated individual, and 4 columns organized as follows:
Column 1: Age;
Column 2: Weight;
Column 3: Height;
Column 4: Berg Balance Scale Score
