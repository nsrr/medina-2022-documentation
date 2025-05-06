## About

This study utilizes an autism mouse model, Shank3e21-/-, to investigate sleep architecture and homeostatic sleep response in autism spectrum disorder. This dataset contains polysomnography recordings conducted in a total of 20 juvenile (postnatal 23, 30, 45, and 60 days old) male mice. Recordings are a total of 48 hours and cover 24 hours of baseline, followed by three hours of sleep deprivation and 21 hours of recovery sleep. All data were manually scored via visual inspection as one of three states: non-rapid eye movement sleep, rapid eye movement sleep, or wake.

## Methods

Heterozygous Shank3e21-/- and wildtype(WT) breeding pairs were established to obtain WT and homozygous Shank3e21-/- littermates. Juvenile male mice were used.

At postnatal (P) 18 days old, male mice (n = 10 Shank3ΔC and n = 10 WT littermates) were weaned from their dams and placed under isoflurane anesthesia and stereotaxically implanted with four EEG and two electromyographic (EMG) electrodes as previously described (Ingiosi et al., 2019). Four stainless steel wire loop electrodes were placed bilaterally over frontal (2) and parietal (2) cortices, and EMG electrodes were inserted bilaterally into the nuchal muscles. Bilateral frontal electrode placement in young and adult mice was centered in the frontal skull plates, and bilateral parietal electrodes were placed centrally in the parietal skull plates (exact coordinates at this age vary depending on skull size). EEG electrode placement was secured with dental cement and did not change over the course of the study relative to the skull plates as the mice grew. To prevent damage to implants, instrumented mice were housed individually from surgery to the completion of final recordings. Mice were allowed a minimum of 3 days of recovery from surgery before habituation to the recording environment. After habituation, mice underwent 24 hours of undisturbed baseline recordings and ended after a total of 48 hours of recordings. The first 24 hours consisted of baseline recording, followed by three hours of sleep deprivation at the beginning of lights on (ZT 1, day 2). Sleep deprivation was followed by 21 hours of undisturbed recovery sleep. Sleep deprivation was conducted manually via gently handing, when necessary, animals were gently stroked with a soft brush to ensure animals remained awake.

EEG and EMG data were recorded from frontal cortical electrodes (referenced to parietal electrodes) collected with Grass 7 polygraph hardware (Natus Medical Incorporated, Pleasanton, CA) via a light‐weight, counterbalanced cable, amplified, and digitized at 256 Hz using VitalRecorder acquisition software (SleepSign for Animal, Kissei Comtec Co., LTD, Nagano, Japan), with band pass filters set at .5–30 Hz and notch filtering at 60 Hz.

Data was manually scored via visual inspection in 4 second resolution (epochs) by an experimenter blinded to conditions. Every epoch was scored as one of three states via the EEG and the Fast Fourier Transform (FFT): wake, non-rapid eye movement sleep (NREM), or rapid eye movement sleep (REMS).

## Data overview

[Raw data are separated into folders (P24, P30, P45, P60)](:files_path:) that correspond to the number of postnatal days on which sleep was recorded. 

The KCD files contain the raw data which include 1 EEG channel, and 1 EMG channel.  EEG and EMG data were band pass filtered at 0.5-30 Hz  with a Notch filter set to 60 Hz. EEG power analysis was conducted from EEG spectra analysis of 0-20 Hz. Data was then further analyzed and scored using VitalRecorder acquisition software (SleepSign for Animal, Kissei Comtec Co., LTD, Nagano, Japan). 

The CSV files provided contain every scored epoch along with spectral information separated into two 24 hour files: baseline (BL) and sleep deprivation followed by recovery sleep (SD).

The [Medina2022_File_Information.xlsx file](:files_path:) contains genotype and sleep recording information.

## Access and usage restrictions

The Medina 2022 dataset is only available for non-commercial use.

## Citation and acknowledgement

When using this dataset, users must cite the following:

> [Zhang GQ, Cui L, Mueller R, Tao S, Kim M, Rueschman M, Mariani S, Mobley D, Redline S. The National Sleep Research Resource: towards a sleep data commons. J Am Med Inform Assoc. 2018 Oct 1;25(10):1351-1358. doi: 10.1093/jamia/ocy064. PMID: 29860441; PMCID: PMC6188513.](https://pubmed.ncbi.nlm.nih.gov/29860441/)
>
> [Medina E, Schoch H, Ford K, Wintler T, Singletary KG, Peixoto L. Shank3 influences mammalian sleep development. J Neurosci Res. 2022 Dec;100(12):2174-2186. doi: 10.1002/jnr.25119. Epub 2022 Sep 2. PMID: 36056598; PMCID: PMC9588578.](https://pubmed.ncbi.nlm.nih.gov/36056598/)

Users must include the following text in any Acknowledgements:

> The Medina 2022 work was supported by the JEDI award from the Life Science Editors foundation and K01NS104172 from NIH/NINDS to Peixoto L. The National Sleep Research Resource was supported by the U.S. National Institutes of Health, National Heart Lung and Blood Institute (R24 HL114473, 75N92019R002).

## Changelog

*May 2025*

- Make Medina 2022 dataset available for data requests

## References

-	Medina 2022 GitHub Documentation: https://github.com/nsrr/medina-2022-documentation

## Questions?

Please reach out to us at support@sleepdata.org or in the [Forum](https://sleepdata.org/forum) if you have questions.
