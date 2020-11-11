[![FOOT Experiment](http://www.lnf.infn.it/divric/nuclear/FOOTlogo.jpg)](https://web.infn.it/foot/en/home/)


# FOOT Experiment
FOOT (FragmentatiOn Of Target) is an INFN experiment whose main purpose is to improve the tumor treatments in hadrontherapy by studying the behavior of the particle beams usually employed. 

## Hadrontherapy
Hadrontherapy is a medical tumor treatment where a charged particle beam is irradiated towards an oncologial mass inside a human body. Despite the same aim of radiotherapy, what changes is the nature of the beam: radiotherapy uses photons while hadrontherapy uses charged particles (mainly protons or carbon ions).
The main different regards the kind of interaction with the body matter and so the effects on organ and tissues: photons releas energy in all the path before and even after the tumoral mass while charged particles lose the biggest part of the dose in the stopping area of the beam (*Bragg Peak*), which corresponds to where the tumor is localized (see Fig.1).

![radio vs had](https://www.scripps.org/sparkle-assets/images/hi_res_bragg_peak.jpg) 
*Figure 1 - Release of dose wrt the depth in tissue: photons (in green) vs charged particles (in red and blue)*

This makes hadrontherapy more efficient than radiotherapy since 
* the great amount of energy released in a limit area increases the probablity of irreversible damages on tumor cells
* due to the kind of interaction, healty tissues before and after the tumor are weakly exposed, decreasing the possibility of damaging them.

## The goal of FOOT
Despite at least 50 years of study, hadrontherapy is still under investigation, mainly in what concerns the interaction of the beam with the body nuclei. What happens is that the beam goes also into nuclear fragmentation such that fragments can go outside the oncologic area creating farther damages. Up to now, information about probability of fragmentation is not enough to create a correct standart protocol treatment.

According to this, FOOT main aim is to measure the cross section of all the fragments that can be created after the interaction of a charged beam with nuclei of human body, in order to make the hadrontherapy treatments more efficient.

### The experiment
FOOT consists of a detector which simulates the oncological treatment studying the results of the interaction of protons (generally the particle of the beam) with a target of C,H,O (the main elements of the human body). Thanks to the different layers of the detector, it is possibile to reconstruct the main features of the resulting fragments, such as velocity, energy, momentum and so on. In Fig.2 there is a sketch of the apparatus.

Actually, it is under costruction so the main purposes up to now are to design it in order to have the best resolutions possible for each subdetector.

![foot apparatus](https://physics-astronomy.unibo.it/en/research/projects-and-research-lines/international-projects/foot-experiment/@@unibo.tiles.multi.album/599f0b25fdb14d50b1e8b0ec067686f9/@@obj-images/126a1e9740254affac27cabea89343c6/21f14050-f47a-4a23-97eb-0a85627df4fd.png)
*Figure 2 - FOOT apparatus)*

### What I have done in my bachelor thesis
My thesis was focused on the identification of the fragments, the first step for the determination of cross section. Specifically, it consisted in the reconstruction of the z and A nuclear numbers of all of fragments.
The analysis was carried out by data taken from a MonteCarlo simulation of an Oxigen beam against a CH target and was focused on the main isotopes created after fragmentation: H, He, Li, Be, B, C, N, O.

The methods to carry out the reconstruction of z and A were analitical:
* knowing the velocity and the dE/dX of a fragments, through the Bethe-Bloch formula was possible to take out the charge z;
* knowing the velocity, the energy released in calorimeter and the momentum of the fragment, through relativistic relations, it was possible to take out the nuclear number A.



