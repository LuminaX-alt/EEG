# EEG 
An EEG, or electroencephalogram, is a test that measures the electrical activity of the brain. It's used to detect and diagnose various brain disorders and conditions, including epilepsy, sleep disorders, and brain injuries. 
How it works:
Electrodes:
Small metal discs, called electrodes, are placed on the scalp to detect the brain's electrical activity. 
Brain waves:
These signals, which are tiny electrical impulses, are amplified and recorded as wavy lines on a graph. 
Analysis:
A healthcare professional interprets the EEG results to identify any abnormal patterns or activity. 
What it can help diagnose:
Seizures and epilepsy:
EEG is particularly useful in diagnosing seizures and epilepsy, as it can show the characteristic electrical activity during a seizure. 
Sleep disorders:
EEG can help diagnose sleep disorders by recording brain activity during sleep cycles. 
Brain injuries:
EEGs can help assess the extent and location of brain damage after a head injury. 
Brain tumors and other conditions:
EEG can also be used to detect brain tumors, strokes, and other conditions that affect brain function. 
Beyond diagnosis:
Monitoring brain function:
EEGs can be used to monitor brain activity during surgeries or in intensive care units. 
Research:
EEGs are also used in research to study brain function, sleep, and other neurological processes. 
Important note: While EEG provides valuable information about brain activity, it does not provide a detailed image of the brain's structure. For that, other imaging techniques like MRI or CT scans are used.
During an EEG, flat metal discs called electrodes are attached to the scalp. In a high-density EEG, shown here, the electrodes are close together. The electrodes are connected to the EEG machine with wires. Some people wear an elastic cap fitted with electrodes instead of having the adhesive applied to their scalps.


<img width="529" alt="image" src="https://github.com/user-attachments/assets/9d9b64ba-1ef2-4713-978a-657169b6f818" />



Results
Doctors trained to analyze EEGs interpret the recording and send the results to the healthcare professional who ordered the EEG. You might need to schedule an office appointment to discuss the results of the test.

You feel little or no discomfort during an EEG. The electrodes don't transmit any sensations. They just record your brain waves.

Here are some things you can expect to happen during an EEG:

A technician measures your head and marks your scalp with a special pencil to indicate where to attach the electrodes. These spots on your scalp might be scrubbed with a gritty cream to improve the quality of the recording.
A technician attaches discs called electrodes to your scalp using an adhesive. Sometimes, an elastic cap fitted with electrodes is used instead. The electrodes are connected with wires to an instrument that amplifies the brain waves and records them on computer equipment.

Once the electrodes are in place, an EEG typically takes between 20 and 40 minutes. For certain conditions, you need to sleep during the test. Tests that require you to sleep can be longer.

You relax in a comfortable position with your eyes closed during the test. The technician might ask you to open and close your eyes or ask you to perform a few simple calculations. You may be asked to read a paragraph, look at a picture, breathe deeply or look at a flashing light.
Video is routinely recorded during the EEG. Your body motions are captured by a video camera while the EEG records your brain waves. This combined recording can help your healthcare professional diagnose and treat your condition.
An ambulatory EEG, also known as an aEEG, allows for longer monitoring outside an office or a hospital setting. But this type of EEG isn't always an option. This test can record brain activity over several days, which increases the chances of recording during seizure activity. However, compared with inpatient video EEG monitoring, an ambulatory EEG is not as good at determining the difference between epileptic seizures and nonepileptic seizures.
After the test
The technician removes the electrodes or cap. If you didn't have a sedative, you typically feel no side effects after the procedure. You usually can return to your typical routine.

If you used a sedative, it takes time for the medicine to begin to wear off. Arrange to have someone drive you home. Once you're at home, rest and don't drive for the rest of the day.

<img width="295" alt="image" src="https://github.com/user-attachments/assets/f9241d6d-658b-4bcd-96d0-90806d378f36" />

<img width="462" alt="image" src="https://github.com/user-attachments/assets/e09b4ba4-ba18-4692-86fc-a6caf2201b1c" />

<img width="462" alt="image" src="https://github.com/user-attachments/assets/05c685a0-c56e-4ee0-91c9-2ffdce32c4fe" />

Now here by I am attaching the images of the throughput of the model while training 


<img width="261" alt="image" src="https://github.com/user-attachments/assets/3a8c8207-445e-4001-b52e-6868a17b7183" />


<img width="378" alt="image" src="https://github.com/user-attachments/assets/7168b7b0-eba7-4ac4-8e51-19906bf6af1a" />


<img width="510" alt="image" src="https://github.com/user-attachments/assets/9ea83b56-24cb-47d3-ac96-a23c2779d283" />


<img width="467" alt="image" src="https://github.com/user-attachments/assets/ed1f0ae5-dce7-4396-9191-b1665de616aa" />


here is a lack of global definition of what "normal" EEG looks like; above represented by the Inter-Ictal data1. This is due to EEG changing over the course of a patients life, as well as between levels of cognition (e.g. awake/asleep) or behaviour (e.g. eyes open/closed). A common variation in EEG is found between awake and asleep EEG, where more global waveforms oscillate at slower frequencies across the head. This global activity is inter-dispersed with fast "spikes", which are commonly found in different sleep stages. The variability means EEG alone is rarely sufficient for a clinical diagnosis, with other diagnostic imaging and forms of observation often necessary.

Alike to "normal" EEG, there is a lot of variability found between and within different seizure types. Never-the-less, comparative to pre-seizure background EEG, seizures have the common traits of synchronisation across a few or many EEG channels, a large amplitude, and increased oscillatory activity. Onsets and offsets of seizures are typically abrupt, however variations can occur both between patients as well as between seizures. Patients may also have spiked inter-seizure discharges, which are short bursts of high amplitude, syncronized activity around an epileptic focus1.

<img width="269" alt="image" src="https://github.com/user-attachments/assets/6dd0d2bb-aa53-4125-876c-d505c94a6974" />

UPenn and Mayo Clinic's Seizure Detection Challenge
Now lets introduce another dataset. This data was origionally a kaggle competition in 20141. The data consists of 1 second ictal and interictal seizures in 4 dogs2 and 8 patients3,4. Recordings were sampleted at 400Hz from 16 intercranial channels in the dogs and at 500Hz or 5kHz from varying numbers and locations of intercranial electrodes in humans. See table below for more information5:

<img width="384" alt="image" src="https://github.com/user-attachments/assets/8143c532-7c17-4066-9bfa-f413a848f3e8" />

<img width="198" alt="image" src="https://github.com/user-attachments/assets/651d528d-c914-4e68-a67d-c94a73115906" />

<img width="691" alt="image" src="https://github.com/user-attachments/assets/4aff0f25-a15a-4701-bf02-85eeb087ec78" />

<img width="1133" alt="image" src="https://github.com/user-attachments/assets/a19db73b-030d-4124-9964-8e3b16e92ada" />

<img width="1225" alt="image" src="https://github.com/user-attachments/assets/8ec13bc8-01b9-440c-b0c2-7a7f701aeff9" />

<img width="272" alt="image" src="https://github.com/user-attachments/assets/b67ebbc5-da96-4e13-852c-550b81cce001" />

<img width="274" alt="image" src="https://github.com/user-attachments/assets/4a384c07-d94a-4f7c-b177-daf1bd40ae10" />

CHB-MIT Scalp EEG Database
The CHB-MIT dataset1, consists of records from 23 patients; with one case (chb21) taken from the same patient (chb01) 1.5 years later. The dataset was collected by investigators at the Children’s Hospital Boston and Massachusetts Institute of Technology (MIT). The median length of collection was for 36 hours with small gaps between records each hour due to hardware limitations.

The data contains 198 seizures of various types (focal, lateral, and generalised seizures). All signals were recorded at 256 samples per second with most files containing 23 EEG signals positioned using the International 10-20 system (as we will see later).

This dataset is one of the most prominent datasets in the literature, as it provides long, continuous recordings for each patient, allowing for both patient specific and patient general models to be developed and tested.


