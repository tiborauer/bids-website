---
---

# Get involved in making BIDS better

The easiest way to contribute to BIDS is to ask questions you have about
the specification on [Neurostars](https://neurostars.org){:target="_blank"}. If your
question has a [bids tag](https://neurostars.org/search?q=tags%3Abids){:target="_blank"}
it will be much easier for others to find the answer.

You can also get involved by _answering_ questions on
[Neurostars](https://neurostars.org/search?q=tags%3Abids){:target="_blank"}!

You can contribute to the BIDS specification by opening
[Issues](https://github.com/bids-standard/bids-specification/issues){:target="_blank"} and
propose changes via [Pull
Requests](https://github.com/bids-standard/bids-specification/pulls){:target="_blank"} on
[GitHub](https://github.com/bids-standard/bids-specification){:target="_blank"}.

To make improvements to the website that you are reading right now, you
can also open an
[Issue](https://github.com/bids-standard/bids-website/issues){:target="_blank"} and
propose changes via [Pull
Requests](https://github.com/bids-standard/bids-website/pulls){:target="_blank"} at its
[GitHub repository](https://github.com/bids-standard/bids-website){:target="_blank"}.

There are so many ways to help us build this community.
You could help someone else learn the benefits of BIDS, give a talk in
your local organisation, or [build a BIDS
App](https://bids-apps.neuroimaging.io/){:target="_blank"}!

The only requirement is that everyone who contributes adheres to our
[BIDS Code of Conduct](code_of_conduct){:target="_blank"}.

Thank you for your contributions!

## Extending the BIDS specification

The BIDS specification can be extended in a backwards compatible way and
will evolve over time. These are accomplished with BIDS Extension
Proposals (BEPs), which are community-driven processes.

Do you want to extend BIDS to a new modality or set of data types?
Please draft a BIDS Extension Proposal (BEP) following the [BIDS
Extension Proposals
Guide](https://docs.google.com/document/d/1pWmEEY-1-WuwBPNy5tDAxVJYQ9Een4hZJM06tQZg8X4){:target="_blank"}.

You can also contribute to ongoing BIDS Extension Proposals. Below is a
table of currently-active BEPs. The "Extension label" column provides a
direct link to the documentation.

Please find our [latest BEP update](https://docs.google.com/presentation/d/10-zmgs6L0RBhiN-aLgRWCJT_fjrGi6LL5SgoeUvRbmU/edit#slide=id.p){:target:"_blank"}
presented in the [Open Science Room](https://ohbm.github.io/osr2020/){:target:"_blank"} at [OHBM](https://www.humanbrainmapping.org/i4a/pages/index.cfm?pageid=3267&pageid=1){:target:"_blank"}.

Note that all of the extension ideas that are not backwards compatible and thus
will have to wait for BIDS 2.0 are listed
[here](https://docs.google.com/document/d/1LEgsMiisGDe1Gv-hBp1EcLmoz7AlKj6VYULUgDD3Zdw){:target="_blank"}.

| Extension label                                                 | Title                                                                                                      | Moderators/ leads                                                | Summary                                                                                                                                                                                                                                   | Blocking point(s)                                                                      |
| --------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------- |
| [BEP001](https://bids.neuroimaging.io/bep001){:target:"_blank"} | Structural acquisitions that include multiple contrasts (multi echo, flip angle, inversion time) sequences | Gilles de Hollander and Kirstie Whitaker                         | BEP has been [submitted as a pull request](https://github.com/bids-standard/bids-specification/pull/508){:target:"_blank"}.                                                                                                                                                                                    | None.                             |
| [BEP002](https://bids.neuroimaging.io/bep002){:target:"_blank"} | The BIDS Models Specification                                                                              | Tal Yarkoni                                                      | Recently went through and removed several sections.                                                                                                                           | Resolving remaining comments and adding examples.                                 |
| [BEP004](https://bids.neuroimaging.io/bep004){:target:"_blank"} | Susceptibility Weighted Imaging (SWI)                                                                      | Available                                                        | Looking for a new leader.                                                                                                                                                                                                                 | Searching for a new leader.                                                            |
| [BEP005](https://bids.neuroimaging.io/bep005){:target:"_blank"} | Arterial Spin Labeling (ASL)                                                                               | Henk-Jan Mutsaerts, Patricia Clement, Jan Petr, Marco Castellaro | BEP is close to being submitted as a pull request. Nearly completed with a [working validator](https://github.com/marcocastellaro/bids-validator/tree/bep005_asl){:target:"_blank"} and finishing the manuscript.                                                                                            | None.                                                                                  |
| [BEP009](https://bids.neuroimaging.io/bep009){:target:"_blank"} | Positron Emission Tomography (PET)                                                                         | Melanie Ganz                                                     | BEP is close to being submitted as a pull request.                                                                                                                       | None.                                                                                  |
| [BEP011](https://bids.neuroimaging.io/bep011){:target:"_blank"} | The structural preprocessing derivatives                                                                   | Viviana Siless                                                  | Opened the [pull request](https://github.com/bids-standard/bids-specification/pull/518){:target:"_blank"}. Need to conform with final Common Derivatives and gather community feedback. | None.                                                                                  |
| [BEP012](https://bids.neuroimaging.io/bep012){:target:"_blank"} | The functional preprocessing derivatives                                                                   | Camille Maumet and Chris Markiewicz                              | Opened the [pull request](https://github.com/bids-standard/bids-specification/pull/519){:target:"_blank"}. Need to conform with final Common Derivatives and gather community feedback.                                                                                                                                                                                                                      | None.                                                                                  |
| [BEP013](https://bids.neuroimaging.io/bep013){:target:"_blank"} | The resting state fMRI derivatives                                                                         | Steven Giavasis                                                  | Merged into BEP012.                                                                                                                                                                                                                        | None.                                                                                  |
| [BEP014](https://bids.neuroimaging.io/bep014){:target:"_blank"} | The affine transformations and nonlinear field warps                                                       | Oscar Esteban                                                    | A new file format (X5) to store spatial transforms is being created, and a draft proposal has been discussed under the scope of this BEP. [There is a software prototype](https://osf.io/8aq7b/){:target:"_blank"} demonstrating the implementation of this BEP.                           | In progress.                                                                           |
| [BEP016](https://bids.neuroimaging.io/bep016){:target:"_blank"} | The diffusion weighted imaging derivatives                                                                 | Franco Pestilli and Oscar Esteban                                | Being discussed in a [GitHub repository](https://github.com/bids-standard/bids-bep016){:target:"_blank"}.                                                                                                                                  |                                                                                        |
| [BEP017](https://bids.neuroimaging.io/bep017){:target:"_blank"} | Generic BIDS connectivity data schema                                                                      | Eugene Duff and Paul McCarthy                                    | This BEP is searching for a reviewer with fresh eyes that understands the scope of this BEP.                                                                                                                                              | None.                                                                                  |
| [BEP019](https://bids.neuroimaging.io/bep019){:target:"_blank"} | DICOM Metadata                                                                                             | Satrajit Ghosh                                                   | Not active - perhaps this is in the 20% of use cases. Could be a NIDM extension rather than in BIDS.                                                                                                                                      | None.                                                                                  |
| [BEP020](https://bids.neuroimaging.io/bep020){:target:"_blank"} | Eye Tracking including Gaze Position and Pupil Size(ET)                                                    | Benjamin Gagl and Dejan Draschkow                                | BEP is close to being submitted as a pull request.                                                                                                                                                                                        | None.                                                                                  |
| [BEP021](https://bids.neuroimaging.io/bep021){:target:"_blank"} | Common Electrophysiological Derivatives                                                                    | Mainak Jas, Stefan Appelhoff, Cyril Pernet, Robert Oostenveld    | Conducted a [community survey](https://github.com/bids-standard/bep021/tree/master/community_survey){:target:"_blank"}   to evaluate which derivatives are the most sought after. Discussions held in a [GitHub repository](https://github.com/bids-standard/bep021){:target:"_blank"}              |             |
| [BEP022](https://bids.neuroimaging.io/bep022){:target:"_blank"} | Magnetic Resonance Spectroscopy (MRS)                                                                      | Mark Mikkelsen and William Clarke                                | [Group discussions](https://forum.mrshub.org/t/bids-for-spectroscopy/83){:target:"_blank"} underway                                                                                                                                                                  |                                                                                        |
| [BEP023](https://bids.neuroimaging.io/bep023){:target:"_blank"} | PET Preprocessing derivatives                                                                              | Martin Noergaard, Graham Searle, Melanie Ganz                    | Work is paused until BEP009 manuscript has been submitted/accepted.                                                                                                                                                                       | A blocking item is the need for more contributors, especially from senior PET experts. |
| [BEP024](https://bids.neuroimaging.io/bep024){:target:"_blank"} | Computed Tomography scan (CT)                                                                              | Hugo Boniface                                                    | Lead seeking more contributors and experts.                                                                                                                                                                    | None.                                                                                  |
| [BEP025](https://bids.neuroimaging.io/bep025){:target:"_blank"} | Medical Imaging Data structure (MIDS)                                                                      | Jose Manuel Saborit Torres, Maria de la Iglesia Vayá             | Preparing to submit the preprint. Recently [published a preprint](https://arxiv.org/abs/2006.01174){:target:"_blank"} describing a use case of this BEP.                                                                                                                | None.                                                                                  |
| [BEP026](https://bids.neuroimaging.io/bep026){:target:"_blank"} | Microelectrode Recordings (MER)                                                                            | Greydon Gilmore                                                  | Active effort. Looking for thoughts and contributions.                                                                                                                                                                                     | None.                                                                                  |
| [BEP027](https://bids.neuroimaging.io/bep027){:target:"_blank"} | BIDS Execution                                                                                             | Chris Markiewicz and Greg Kiar                                   | Focusing on: command-line conventions, I/O interface descriptors, and common behavior (e.g., exit codes for failure modes).                                                                             | None.                                                                                                             |
| [BEP028](https://bids.neuroimaging.io/bep028){:target:"_blank"} | Provenance                                                                                                 | Satra Ghosh and Camille Maumet                                   | new BEP, actively looking for contributors and community input.                                                                                                                                                                           | None.                                                                                  |
| [BEP029](https://bids.neuroimaging.io/bep029){:target:"_blank"} | Virtual and physical motion data                                                                           | Sein Jeung and Julius Welzel                                     | new BEP, actively looking for contributors and community input.                                                                                                                                                                           | None.                                                                                  |
| [BEP030](https://bids.neuroimaging.io/bep030){:target:"_blank"} | Near Infrared Spectroscopy (NIRS)                                                                          | Robert Luke and Luca Pollonini                                   | new BEP, actively looking for contributors and community input.                                                                                                                                                                           | None.                                                                                  |
| [BEP031](https://bids.neuroimaging.io/bep031){:target:"_blank"} | Microscopy                                                                                                 | Marie-Hélène Bourget and Julien Cohen-Adad                       | new BEP, actively looking for contributors and community input.                                                                                                                                                                           | None.                                                                                  |

### Completed BEPs

When an extension reaches maturity it is merged into the main body of
the specification.  Below is a table of BEPs that have been merged in
the main body of the specification.

| Extension label                                                 | Title                                      | Moderators/leads                                  |
| --------------------------------------------------------------- | ------------------------------------------ | ------------------------------------------------- |
| [BEP003](https://bids.neuroimaging.io/bep003){:target:"_blank"} | Common Derivatives                         | Chris Markiewicz                                  |
| [BEP006](https://bids.neuroimaging.io/bep006){:target:"_blank"} | Electroencephalography (EEG)               | Cyril Pernet, Stefan Appelhoff, Robert Oostenveld |
| [BEP007](https://bids.neuroimaging.io/bep007){:target:"_blank"} | Hierarchical Event Descriptor (HED) Tags   | Chris Gorgolewski                                 |
| [BEP008](https://bids.neuroimaging.io/bep008){:target:"_blank"} | Magnetoencephalography (MEG)               | Guiomar Niso                                      |
| [BEP010](https://bids.neuroimaging.io/bep010){:target:"_blank"} | intracranial Electroencephalography (iEEG) | Chris Holdgraf, Dora Hermes                       |
| [BEP018](https://bids.neuroimaging.io/bep018){:target:"_blank"} | Genetic information                        | Cyril R Pernet, Clara Moreau, Thomas Nichols      |

Some proposals that set out to extend the BIDS specification have instead become tools for handling BIDS. See the table below.

| Extension label                                                 | Title        | Moderators/leads                               | Tool name                                                                 |
| --------------------------------------------------------------- | ------------ | ---------------------------------------------- | ------------------------------------------------------------------------- |
| [BEP015](https://bids.neuroimaging.io/bep015){:target:"_blank"} | Mapping file | Eric Earl, Camille Maumet, and Vasudev Raguram | [File mapper](https://github.com/DCAN-Labs/file-mapper){:target:"_blank"} |
