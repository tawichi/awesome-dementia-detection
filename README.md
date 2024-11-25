# [REDACTED]

> Dementia detection from speech via machine learning.

## Contents

- [1. Survey papers](#1-survey-papers)
- [2. Special challenges](#2-special-challenges)
  * [a. ADReSS 2020 InterSpeech](#a-adress-2020-interspeech)
  * [b. ADReSS 2020 Frontiers](#b-adress-2020-frontiers)
  * [c. ADReSSo 2021](#c-adresso-2021)
- [3. Novel research topics in dementia](#3-novel-research-topics-in-dementia)
  * [ASR](#asr)
  * [[REDACTED]](#data-augmentation)
  * [[REDACTED]](#dialog-act)
  * [Emotion](#emotion)
  * [Explainable](#explainable)
  * [Eye-tracking](#eye-tracking)
  * [[REDACTED]](#information-unit)
  * [[REDACTED]](#intermediate-pretraining)
  * [[REDACTED]](#novel-speech-tasks)
  * [Pause&Disfluencies](#pause-disfluencies)
  * [Perplexity](#perplexity)
  * [Speech and Writing](#speech-and-writing)
  * [[REDACTED]](#telephone-interview)
  * [[REDACTED]](#voice-assistant)
- [4. Regular papers](#4-regular-papers)
- [5. Related works in other domains](#5-related-works-in-other-domains)
  * [Aphasia](#aphasia)
  * [Asthma](#asthma)
  * [Disfluency](#disfluency)
  * [Parkinson’s Disease](#parkinson-s-disease)

## Papers

### 1. Survey papers
- 2023
	- [AI and Non AI Assessments for Dementia](https://doi.org/10.48550/arXiv.2307.01210) - M. Parsapoor, [REDACTED], [REDACTED], C. Madan, [REDACTED], S. Nikolopoulos, Y. Kompatsiaris, arXiv.org, (2023), [REDACTED]: 2
	- [[REDACTED] for [REDACTED]: A [REDACTED] and [REDACTED]](https://doi.org/10.1007/s10916-023-01906-7) - [REDACTED], A. Dallora, J. Berglund, [REDACTED], [REDACTED], P. Anderberg, Journal of medical systems, (2023), [REDACTED]: 45
	- [DementiaBank: [REDACTED], Protocol, and [REDACTED]](https://doi.org/10.1044/2022_AJSLP-22-00281) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], B. MacWhinney, [REDACTED], [REDACTED] of Speech-[REDACTED], (2023), [REDACTED]: 20
	- [Speech and language processing with deep learning for dementia diagnosis: A systematic review](https://doi.org/10.1016/j.psychres.2023.115538) - [REDACTED], G. Cheung, [REDACTED], [REDACTED], (2023), [REDACTED]: 2
	- [Noninvasive automatic detection of Alzheimer's disease from spontaneous speech: a review](https://doi.org/10.3389/fnagi.2023.1224723) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], Frontiers in [REDACTED], (2023), [REDACTED]: 0
	- [A Review of Alzheimer’s [REDACTED] from [REDACTED] and Text](https://doi.org/10.1109/ICCC57789.2023.10165507) - M. K. Vrindha, V. Geethu, P. R. Anurenjan, S. Deepak, K. G. Sreeni, [REDACTED] on [REDACTED] and [REDACTED], (2023), [REDACTED]: 0
- 2022
	- [Deep learning-based speech analysis for Alzheimer’s disease detection: a literature review](https://doi.org/10.1186/s13195-022-01131-3) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], Alzheimer's Research & Therapy, (2022), [REDACTED]: 25
	- [Speech- and Language-[REDACTED] of Alzheimer’s Disease: A [REDACTED]](https://doi.org/10.3390/bioengineering9010027) - Inês Vigo, Luís Coelho, [REDACTED], Bioengineering, (2022), [REDACTED]: 25
	- [A [REDACTED] of Alzheimer's disease detection based on speech and natural language processing](https://doi.org/10.1109/RADIOELEKTRONIKA54537.2022.9764938) - A. Ševčík, M. Rusko, [REDACTED], (2022), [REDACTED]: 4
- 2020
	- [[REDACTED], Speech, and [REDACTED] to [REDACTED]’s Disease: A [REDACTED]](https://doi.org/10.3233/JAD-200888) - Sofia de la [REDACTED], C. Ritchie, S. Luz, Journal of Alzheimer's Disease, (2020), [REDACTED]: 124
- 2018
	- [A Review of Alzheimer's [REDACTED] and [REDACTED]](https://doi.org/10.1109/CISP-BMEI.2018.8633126) - [REDACTED], 2018 11th [REDACTED] on Image and [REDACTED], Bio[REDACTED] and Informatics (CISP-BMEI), (2018), [REDACTED]: 11

### 2. Special challenges

#### a. ADReSS 2020 InterSpeech
- 2020
	- [The INESC-ID Multi-[REDACTED] for the ADReSS 2020 Challenge](https://doi.org/10.21437/interspeech.2020-2833) - A. Pompili, T. Rolland, A. Abad, Interspeech, (2020), [REDACTED]: 34
	- [[REDACTED] for Alzheimer's [REDACTED]](https://doi.org/10.21437/interspeech.2020-2781) - E. Edwards, [REDACTED], [REDACTED], M. Singh, Interspeech, (2020), [REDACTED]: 31
	- [A Comparison of Acoustic and [REDACTED] for Alzheimer's [REDACTED]](https://doi.org/10.21437/interspeech.2020-2635) - N. Cummins, [REDACTED], [REDACTED], J. Fritsch, [REDACTED], H. Christensen, D. Blackburn, Björn Schuller, M. Magimai-Doss, H. Strik, Aki Härmä, Interspeech, (2020), [REDACTED]: 51
	- [[REDACTED] of the [REDACTED] and [REDACTED] to [REDACTED]'s Disease and Assess its Severity](https://doi.org/10.21437/interspeech.2020-2587) - R. Pappagari, [REDACTED], L. Moro-Velázquez, N. Dehak, Interspeech, (2020), [REDACTED]: 56
	- [To BERT or [REDACTED] BERT: [REDACTED] and Language-based Approaches for Alzheimer's [REDACTED]](https://doi.org/10.21437/interspeech.2020-2557) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], Interspeech, (2020), [REDACTED]: 106
	- [[REDACTED] for Alzheimer's [REDACTED] in [REDACTED]](https://doi.org/10.21437/interspeech.2020-2729) - [REDACTED], [REDACTED], R. Dobson, Interspeech, (2020), [REDACTED]: 36
	- [Exploring MMSE [REDACTED] and Non-[REDACTED]](https://doi.org/10.21437/interspeech.2020-3085) - [REDACTED], [REDACTED], Interspeech, (2020), [REDACTED]: 19
	- [[REDACTED] for Detection of Alzheimer's Dementia and its Severity](https://doi.org/10.21437/interspeech.2020-3137) - U. Sarawgi, W. Zulfikar, [REDACTED], P. Maes, Interspeech, (2020), [REDACTED]: 51
	- [[REDACTED] for Alzheimer's [REDACTED]](https://doi.org/10.21437/interspeech.2020-3158) - [REDACTED], [REDACTED], M. Lech, E. Pirogova, Interspeech, (2020), [REDACTED]: 57
	- [Tackling the ADReSS Challenge: A [REDACTED] to the [REDACTED] of Alzheimer's Dementia](https://doi.org/10.21437/interspeech.2020-2202) - [REDACTED], S. Pollak, Interspeech, (2020), [REDACTED]: 29
	- [Disfluencies and Fine-[REDACTED]-[REDACTED] for Detection of Alzheimer's Disease](https://doi.org/10.21437/interspeech.2020-2516) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], Z. Ye, [REDACTED], Interspeech, (2020), [REDACTED]: 85
	- [Alzheimer's [REDACTED] through [REDACTED]: The ADReSS Challenge](https://doi.org/10.21437/interspeech.2020-2571) - S. Luz, F. Haider, S. D. L. Fuente, [REDACTED], B. MacWhinney, Interspeech, (2020), [REDACTED]: 215
	- [[REDACTED]-[REDACTED]-trained Networks for Alzheimer's [REDACTED]](https://doi.org/10.21437/interspeech.2020-3153) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], Interspeech, (2020), [REDACTED]: 41
	- [Multi-[REDACTED] with [REDACTED], Lexical and [REDACTED] for Alzheimer's [REDACTED] from [REDACTED]](https://doi.org/10.21437/Interspeech.2020-2721) - [REDACTED], [REDACTED], [REDACTED], Interspeech, (2020), [REDACTED]: 52

#### b. ADReSS 2020 Frontiers
- 2021
	- [[REDACTED] of [REDACTED] and [REDACTED] for Alzheimer's [REDACTED] on [REDACTED]](https://doi.org/10.3389/fnagi.2021.642647) - [REDACTED], F. Haider, S. Pollak, S. Luz, Frontiers in [REDACTED], (2021), [REDACTED]: 33
	- [[REDACTED] in Alzheimer’s Disease—Robust and [REDACTED] for AD-[REDACTED] of [REDACTED]](https://doi.org/10.3389/fnagi.2021.642033) - [REDACTED], J. Tröger, A. König, Frontiers in [REDACTED], (2021), [REDACTED]: 33
	- [Acoustic and [REDACTED] for Alzheimer's [REDACTED]](https://doi.org/10.3389/fnagi.2021.623607) - [REDACTED], V. Baths, Frontiers in [REDACTED], (2021), [REDACTED]: 46
	- [Cognitive and [REDACTED] of [REDACTED] in [REDACTED] and Mild-to-[REDACTED]’s Disease: Relevance for [REDACTED]](https://doi.org/10.3389/fnagi.2021.637404) - Céline [REDACTED], [REDACTED], L. Crosby, [REDACTED], R. Coen, B. Lawlor, R. Reilly, Frontiers in [REDACTED], (2021), [REDACTED]: 7
	- [[REDACTED]'s [REDACTED] and Text-[REDACTED] of Speech](https://doi.org/10.3389/fpsyg.2020.624137) - R'mani Haulcy, [REDACTED], Frontiers in Psychology, (2021), [REDACTED]: 60
	- [Recognition of Alzheimer’s [REDACTED] the Transcriptions of [REDACTED] fastText and CNN Models](https://doi.org/10.3389/fcomp.2021.624558) - [REDACTED], C. Anoop, [REDACTED], Frontiers of [REDACTED], (2021), [REDACTED]: 23
	- [[REDACTED]-[REDACTED] of [REDACTED]](https://doi.org/10.3389/fpsyg.2020.623237) - K. Chlasta, K. Wołk, Frontiers in Psychology, (2021), [REDACTED]: 21
	- [[REDACTED] of [REDACTED] for [REDACTED] of [REDACTED]: [REDACTED] and [REDACTED]](https://doi.org/10.3389/fcomp.2021.642633) - [REDACTED], [REDACTED]ëll, K. Håkansson, G. Henter, [REDACTED], O. Mikheeva, G. Hagman, J. Holleman, M. Kivipelto, H. Kjellström, [REDACTED], J. Beskow, Frontiers of [REDACTED], (2021), [REDACTED]: 13
	- [Using a [REDACTED] to [REDACTED] in [REDACTED]](https://doi.org/10.3389/fnagi.2020.607449) - M. Antonsson, [REDACTED], M. Eckerström, D. Kokkinakis, Frontiers in [REDACTED], (2021), [REDACTED]: 9
	- [Pauses for Detection of Alzheimer’s Disease](https://doi.org/10.3389/fcomp.2020.624488) - [REDACTED], [REDACTED], [REDACTED], Z. Ye, [REDACTED], Frontiers of [REDACTED], (2021), [REDACTED]: 22
	- [Editorial: Alzheimer’s [REDACTED] through [REDACTED]](https://doi.org/10.3389/fcomp.2021.780169) - S. Luz, F. Haider, Sofia de la [REDACTED], [REDACTED], B. MacWhinney, Frontiers of [REDACTED], (2021), [REDACTED]: 26
	- [[REDACTED] for Alzheimer’s [REDACTED]](https://doi.org/10.3389/fcomp.2021.624683) - [REDACTED], [REDACTED], J. Batsis, R. Roth, Frontiers of [REDACTED], (2021), [REDACTED]: 29
	- [A Comparison of [REDACTED] for [REDACTED]’s Disease and [REDACTED] and [REDACTED]](https://doi.org/10.3389/fcomp.2021.634360) - [REDACTED], T. Barrick, P. Garrard, Frontiers of [REDACTED], (2021), [REDACTED]: 29
	- [Towards an [REDACTED]-[REDACTED] for Alzheimer’s Disease](https://doi.org/10.3389/fcomp.2021.624594) - [REDACTED], J. Schaffer, S. Zahorian, Frontiers of [REDACTED], (2021), [REDACTED]: 11
	- [Alzheimer’s [REDACTED] and [REDACTED]](https://doi.org/10.3389/fcomp.2021.640669) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], Frontiers of [REDACTED], (2021), [REDACTED]: 27
	- [Analysis and Classification of [REDACTED]-[REDACTED]’s Patients and Controls](https://doi.org/10.3389/fcomp.2021.649508) - [REDACTED], S. Luz, Frontiers of [REDACTED], (2021), [REDACTED]: 12
	- [[REDACTED] and [REDACTED] for [REDACTED]’s [REDACTED]](https://doi.org/10.3389/fcomp.2021.624659) - [REDACTED], [REDACTED], [REDACTED], S. Qi, [REDACTED], R. Greiner, Frontiers of [REDACTED], (2021), [REDACTED]: 31
	- [[REDACTED]-trained and Feature-[REDACTED] for Prediction of Alzheimer's [REDACTED] on Speech](https://doi.org/10.3389/fnagi.2021.635945) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], Frontiers in [REDACTED], (2021), [REDACTED]: 56
	- [Crossing the “[REDACTED]” [REDACTED]: [REDACTED] BERT [REDACTED] to the ADReSS [REDACTED]](https://doi.org/10.3389/fcomp.2021.642517) - [REDACTED], [REDACTED], [REDACTED], Serguei V. S. Pakhomov, T. Cohen, Frontiers of [REDACTED], (2021), [REDACTED]: 26
- 2020
	- [[REDACTED] for [REDACTED]'s Detection](https://doi.org/10.3389/fcomp.2021.624694) - [REDACTED], B. Subirana, Frontiers of [REDACTED], (2020), [REDACTED]: 23
	- [Dual-[REDACTED] and [REDACTED] and [REDACTED] of [REDACTED]’s Disease: A [REDACTED]](https://doi.org/10.3389/fnagi.2020.605317) - [REDACTED], F. Mohammadian, [REDACTED]-shalamzari, M. Bayati, [REDACTED], Frontiers in [REDACTED], (2020), [REDACTED]: 24

#### c. ADReSSo 2021
- 2021
	- [Using the Outputs of [REDACTED] for Acoustic- and BERT-[REDACTED]'s [REDACTED]](https://doi.org/10.21437/interspeech.2021-1519) - [REDACTED], B. Mirheidari, [REDACTED], J. Thompson, [REDACTED], J. Snowden, [REDACTED], H. Christensen, Interspeech, (2021), [REDACTED]: 42
	- [[REDACTED] and Assessment of [REDACTED] and [REDACTED] in Low-[REDACTED]](https://doi.org/10.21437/interspeech.2021-1850) - R. Pappagari, [REDACTED], [REDACTED], L. Moro-Velázquez, Piotr Żelasko, J. Villalba, N. Dehak, Interspeech, (2021), [REDACTED]: 36
	- [WavBERT: [REDACTED] and Non-[REDACTED]2vec and BERT for [REDACTED]](https://doi.org/10.21437/interspeech.2021-332) - [REDACTED], [REDACTED], [REDACTED], J. Batsis, R. Roth, Interspeech, (2021), [REDACTED]: 30
	- [Tackling the ADRESSO Challenge 2021: The MUET-RMIT System for Alzheimer's [REDACTED] from [REDACTED]](https://doi.org/10.21437/interspeech.2021-1572) - [REDACTED], [REDACTED], M. Lech, E. Pirogova, Interspeech, (2021), [REDACTED]: 17
	- [[REDACTED] of Alzheimer's [REDACTED]](https://doi.org/10.21437/interspeech.2021-2002) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], Interspeech, (2021), [REDACTED]: 29
	- [Alzheimer's [REDACTED] from [REDACTED] through [REDACTED] and (Dis)[REDACTED] with [REDACTED]](https://doi.org/10.21437/interspeech.2021-1415) - Y. Qiao, [REDACTED], [REDACTED], E. Kerz, Interspeech, (2021), [REDACTED]: 16
	- [[REDACTED]-based Approaches for Alzheimer's [REDACTED]](https://doi.org/10.21437/interspeech.2021-759) - [REDACTED], [REDACTED], Interspeech, (2021), [REDACTED]: 32
	- [Influence of the Interviewer on the [REDACTED] of Alzheimer's Disease in the Context of the ADReS[REDACTED]](https://doi.org/10.21437/interspeech.2021-1589) - P. A. Pérez-Toro, S. Bayerl, T. Arias-Vergara, J. C. Vásquez-Correa, P. Klumpp, M. Schuster, Elmar Nöth, J. Orozco-Arroyave, K. Riedhammer, Interspeech, (2021), [REDACTED]: 21
	- [[REDACTED]-[REDACTED]-[REDACTED]](https://doi.org/10.21437/interspeech.2021-753) - L. Gauder, L. Pepino, [REDACTED], P. Riera, Interspeech, (2021), [REDACTED]: 24
	- [Detecting cognitive decline using speech only: The ADReS[REDACTED]](https://doi.org/10.1101/2021.03.24.21254263) - S. Luz, F. Haider, S. D. L. Fuente, [REDACTED], B. MacWhinney, medRxiv, (2021), [REDACTED]: 109
	- [Alzheimer's [REDACTED], Lexical, Disfluency and [REDACTED] to [REDACTED]](https://doi.org/10.21437/interspeech.2021-1633) - [REDACTED], [REDACTED], [REDACTED], Interspeech, (2021), [REDACTED]: 33
	- [[REDACTED]-[REDACTED] for Alzheimer's [REDACTED] and [REDACTED]](https://doi.org/10.21437/interspeech.2021-2024) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], K.P. Subbalakshmi, Interspeech, (2021), [REDACTED]: 21

#### d. SPGC Challenge 2023
- 2024
	- [[REDACTED] of the ADReSS-M [REDACTED] on [REDACTED]’s [REDACTED]](https://doi.org/10.1109/OJSP.2024.3378595) - [REDACTED], F. Haider, [REDACTED], [REDACTED], I. Kompatsiaris, B. MacWhinney, IEEE [REDACTED] of [REDACTED], (2024), [REDACTED]: 2
- 2023
	- [Cross-[REDACTED]’s [REDACTED] on Paralinguistic and Pre-[REDACTED]](https://doi.org/10.1109/ICASSP49357.2023.10095522) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], IEEE [REDACTED] on Acoustics, Speech, and [REDACTED], (2023), [REDACTED]: 7
	- [[REDACTED]’s [REDACTED] through [REDACTED]: A [REDACTED]](https://doi.org/10.1109/ICASSP49357.2023.10433923) - S. Luz, F. Haider, [REDACTED], [REDACTED], Y. Kompatsiaris, B. MacWhinney, IEEE [REDACTED] on Acoustics, Speech, and [REDACTED], (2023), [REDACTED]: 14
	- [[REDACTED]-[REDACTED] for [REDACTED]’s Dementia](https://doi.org/10.1109/ICASSP49357.2023.10095593) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], R. Greiner, [REDACTED], [REDACTED], IEEE [REDACTED] on Acoustics, Speech, and [REDACTED], (2023), [REDACTED]: 4
	- [[REDACTED] for Adress-m Challenge](https://doi.org/10.1109/ICASSP49357.2023.10094714) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], IEEE [REDACTED] on Acoustics, Speech, and [REDACTED], (2023), [REDACTED]: 5
	- [Cross-[REDACTED] for Alzheimer’s Detection from [REDACTED]](https://doi.org/10.1109/ICASSP49357.2023.10096770) - [REDACTED], R. Vandenberghe, H. V. hamme, IEEE [REDACTED] on Acoustics, Speech, and [REDACTED], (2023), [REDACTED]: 8

#### e. TalkDual 2024
- 2024
	- [[REDACTED] for [REDACTED] in the Interspeech'24 TAUKADIAL Challenge](https://doi.org/10.21437/interspeech.2024-984) - G. Gosztolya, László Tóth, Interspeech, (2024), [REDACTED]: 0
	- [[REDACTED] and [REDACTED] for the Assessment of [REDACTED]: Outcomes from the [REDACTED]](https://doi.org/10.21437/interspeech.2024-2115) - P. A. Pérez-Toro, T. Arias-Vergara, P. Klumpp, [REDACTED], [REDACTED], E. Noeth, J. Orozco-Arroyave, [REDACTED], Interspeech, (2024), [REDACTED]: 0
	- [[REDACTED] for Detecting and Assessing the Severity of [REDACTED]](https://doi.org/10.21437/interspeech.2024-2030) - A. Favaro, [REDACTED], N. Dehak, L. Moro-Velázquez, Interspeech, (2024), [REDACTED]: 0
	- [Pre-trained [REDACTED] and Matching for [REDACTED]](https://doi.org/10.21437/interspeech.2024-2386) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], Interspeech, (2024), [REDACTED]: 0
	- [CogniVoice: Multimodal and [REDACTED] for [REDACTED] from [REDACTED]](https://doi.org/10.48550/arXiv.2407.13660) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], Interspeech, (2024), [REDACTED]: 0
	- [[REDACTED]: [REDACTED]](https://doi.org/10.48550/arXiv.2406.07542) - [REDACTED]-Perez, José García Rodríguez, [REDACTED]ás, Interspeech, (2024), [REDACTED]: 0
	- [[REDACTED] 2024 TAUKADIAL Challenge: [REDACTED] with [REDACTED]](https://doi.org/10.21437/interspeech.2024-1352) - [REDACTED]-Altuna, [REDACTED], [REDACTED], [REDACTED], [REDACTED], Interspeech, (2024), [REDACTED]: 0
	- [[REDACTED]-[REDACTED] in Chinese and English](https://doi.org/10.48550/arXiv.2406.10272) - [REDACTED], Sofia de la [REDACTED], F. Haider, [REDACTED], B. MacWhinney, [REDACTED], Ya‐[REDACTED], Chia-[REDACTED], Yi‐[REDACTED], Interspeech, (2024), [REDACTED]: 3
	- [[REDACTED] for [REDACTED] from [REDACTED]](https://doi.org/10.21437/interspeech.2024-1422) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], Interspeech, (2024), [REDACTED]: 0

### 3. Novel research topics in dementia

#### ASR
- 2024
	- [[REDACTED] of [REDACTED] on [REDACTED] and [REDACTED]’s [REDACTED] from [REDACTED]](https://www.semanticscholar.org/paper/43df611c507c53db91f4c7dcc9554862a96198b1) - [REDACTED], [REDACTED], [REDACTED], [REDACTED] on [REDACTED] and Evaluation, (2024), [REDACTED]: 0
	- [Whisper-[REDACTED] for [REDACTED]: [REDACTED] with [REDACTED] as Prompts](https://doi.org/10.1109/ICASSP48485.2024.10448004) - [REDACTED], Wei-[REDACTED], IEEE [REDACTED] on Acoustics, Speech, and [REDACTED], (2024), [REDACTED]: 0
- 2022
	- [[REDACTED] of Failure: Investigating the Impact of [REDACTED] on [REDACTED]](https://doi.org/10.48550/arXiv.2211.07430) - [REDACTED], T. Cohen, Serguei V. S. Pakhomov, arXiv.org, (2022), [REDACTED]: 2
	- [End-to-End ASR-[REDACTED] for Alzheimer’s [REDACTED]](https://doi.org/10.1109/icassp43922.2022.9747856) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], IEEE [REDACTED] on Acoustics, Speech, and [REDACTED], (2022), [REDACTED]: 3
	- [[REDACTED]-[REDACTED] for [REDACTED]: [REDACTED] and [REDACTED]](https://doi.org/10.2196/33460) - [REDACTED], Thiago da [REDACTED], [REDACTED]‐Mason, [REDACTED], [REDACTED], [REDACTED], [REDACTED], C. Conati, [REDACTED], G. Carenini, [REDACTED], [REDACTED], JMIR Aging, (2022), [REDACTED]: 6
	- [[REDACTED] for Alzheimer's [REDACTED]](https://doi.org/10.48550/arXiv.2206.13232) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], Interspeech, (2022), [REDACTED]: 19
	- [Evaluation of Wav2[REDACTED] for Speakers with [REDACTED]](https://doi.org/10.1007/978-3-031-16270-1_41) - J. Svec, [REDACTED]ák, A. Bartoš, M. Zapletalová, Martin Víta, [REDACTED] on Text, Speech and Dialogue, (2022), [REDACTED]: 4
- 2021
	- [[REDACTED]-Trained ASR Models for Alzheimer's [REDACTED]](https://arxiv.org/abs/2110.01493) - [REDACTED], W. Liu, [REDACTED], Si-[REDACTED], [REDACTED], [REDACTED], [REDACTED], , (2021), [REDACTED]: 9
- 2020
	- [[REDACTED] of Alzheimer's [REDACTED] to [REDACTED]-[REDACTED] for [REDACTED]](https://doi.org/10.21437/interspeech.2020-2698) - [REDACTED], B. Mirheidari, M. Reuber, A. Venneri, D. Blackburn, H. Christensen, Interspeech, (2020), [REDACTED]: 14
- 2019
	- [Impact of ASR on Alzheimer’s [REDACTED]: [REDACTED] are Equal, but Deletions are [REDACTED] than Others](https://doi.org/10.18653/v1/2020.wnut-1.21) - [REDACTED], [REDACTED], [REDACTED], WNUT, (2019), [REDACTED]: 7
- 2018
	- [A [REDACTED]-based Solution for the [REDACTED] of [REDACTED] from [REDACTED]](https://doi.org/10.2174/1567205014666171121114930) - , [REDACTED], (2018), [REDACTED]: 165
- 2015
	- [Automatic detection of mild cognitive impairment from spontaneous speech using ASR](https://doi.org/10.21437/Interspeech.2015-568) - L. Tóth, G. Gosztolya, V. Vincze, I. Hoffmann, Gréta Szatlóczki, [REDACTED]ó, [REDACTED], M. Pákáski, J. Kálmán, Interspeech, (2015), [REDACTED]: 85

#### Architecture
- 2024
	- [HAFFormer: A [REDACTED]-[REDACTED] for Alzheimer’s [REDACTED]](https://doi.org/10.1109/ICASSP48485.2024.10446795) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], IEEE [REDACTED] on Acoustics, Speech, and [REDACTED], (2024), [REDACTED]: 0

#### [REDACTED]
- 2023
	- [Exploring the Topics of [REDACTED] for [REDACTED]'s [REDACTED]](https://doi.org/10.1109/LSP.2023.3334696) - [REDACTED], [REDACTED], IEEE [REDACTED], (2023), [REDACTED]: 0

#### Coherence
- 2023
	- [A [REDACTED] for [REDACTED]](https://doi.org/10.48550/arXiv.2310.09623) - [REDACTED], [REDACTED], M. Liakata, Conference on [REDACTED] in [REDACTED], (2023), [REDACTED]: 1

#### [REDACTED]
- 2023
	- [[REDACTED] for Alzheimer's [REDACTED]' Speech and Transcript](https://doi.org/10.1007/978-3-031-43075-6_34) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], BI, (2023), [REDACTED]: 3
	- [CDA: A [REDACTED] for Alzheimer's [REDACTED]](https://doi.org/10.18653/v1/2023.findings-acl.114) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED] of the Association for [REDACTED], (2023), [REDACTED]: 3
- 2022
	- [[REDACTED] for [REDACTED] in [REDACTED]](https://doi.org/10.48550/arXiv.2206.12879) - [REDACTED]'edikov'a, [REDACTED], [REDACTED], [REDACTED], Björn Schuller, Interspeech, (2022), [REDACTED]: 7
	- [[REDACTED] of [REDACTED] with [REDACTED]](https://doi.org/10.3390/healthcare10102051) - [REDACTED], M. Nihei, Healthcare, (2022), [REDACTED]: 2
- 2021
	- [Robustness and Sensitivity of BERT [REDACTED]’s Disease from Text](https://doi.org/10.18653/v1/2021.wnut-1.37) - [REDACTED], WNUT, (2021), [REDACTED]: 7
	- [[REDACTED] for [REDACTED] and [REDACTED]](https://doi.org/10.1145/3469089) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], L. Calzà, ACM Trans. Comput. Heal., (2021), [REDACTED]: 26
- 2020
	- [Data augmentation using generative networks to identify dementia](https://arxiv.org/abs/2004.05989) - B. Mirheidari, [REDACTED], D. Blackburn, R. O'Malley, [REDACTED], A. Venneri, M. Reuber, H. Christensen, arXiv.org, (2020), [REDACTED]: 4

#### [REDACTED]
- 2024
	- [[REDACTED] in [REDACTED] of Alzheimer's Disease through Speech](https://doi.org/10.21437/interspeech.2024-1018) - Yin-[REDACTED], [REDACTED], Jia-[REDACTED], Z. Ling, Interspeech, (2024), [REDACTED]: 0

#### [REDACTED]
- 2022
	- [[REDACTED] for Task-[REDACTED]? [REDACTED]](https://doi.org/10.18653/v1/2022.sigdial-1.18) - [REDACTED], [REDACTED], SIGDIAL Conferences, (2022), [REDACTED]: 3
- 2020
	- [[REDACTED] in [REDACTED]](https://www.semanticscholar.org/paper/cf0c7194c5342f4d167e95c54685f5f564a7d12b) - [REDACTED], [REDACTED], [REDACTED], [REDACTED] on [REDACTED] and Evaluation, (2020), [REDACTED]: 15

#### [REDACTED]
- 2023
	- [[REDACTED]-Agnostic and Domain-[REDACTED] from [REDACTED]](https://doi.org/10.18653/v1/2023.acl-long.668) - [REDACTED], [REDACTED], [REDACTED] of the Association for [REDACTED], (2023), [REDACTED]: 2

#### Emotion
- 2021
	- [Audio-[REDACTED] of [REDACTED] of People with Dementia](https://doi.org/10.21437/interspeech.2021-567) - [REDACTED], F. Putze, Dennis Küster, T. Schultz, Interspeech, (2021), [REDACTED]: 8
- 2020
	- [[REDACTED] of People with Dementia in [REDACTED]](https://doi.org/10.1145/3382507.3418856) - [REDACTED], F. Putze, Dennis Küster, T. Schultz, [REDACTED] on [REDACTED], (2020), [REDACTED]: 10

#### Explainable
- 2024
	- [[REDACTED] of [REDACTED] an [REDACTED] of the [REDACTED]](https://doi.org/10.21437/odyssey.2024-29) - A. Favaro, N. Dehak, [REDACTED], J. Villalba, [REDACTED], L. Moro-Velázquez, [REDACTED] and [REDACTED], (2024), [REDACTED]: 0
- 2023
	- [[REDACTED]’s [REDACTED] from [REDACTED]](https://doi.org/10.1159/000531818) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], Dementia and [REDACTED], (2023), [REDACTED]: 1
- 2022
	- [Data-driven Approach to Differentiating between Depression and Dementia from [REDACTED] and [REDACTED]](https://doi.org/10.48550/arXiv.2210.03303) - [REDACTED], [REDACTED], [REDACTED], WNUT, (2022), [REDACTED]: 3
	- [Interpreting acoustic features for the assessment of Alzheimer’s disease using ForestNet](https://doi.org/10.1016/j.smhl.2022.100347) - P. A. Pérez-Toro, [REDACTED]íguez-Salas, T. Arias-Vergara, P. Klumpp, M. Schuster, Elmar Nöth, J. Orozco-Arroyave, A. Maier, [REDACTED], (2022), [REDACTED]: 6
	- [[REDACTED] and [REDACTED]](https://doi.org/10.1145/3520084.3520108) - [REDACTED], [REDACTED], T. Ohtsuki, [REDACTED] on [REDACTED] and [REDACTED], (2022), [REDACTED]: 2
- 2021
	- [[REDACTED] of [REDACTED]](https://doi.org/10.1109/JBHI.2022.3172479) - [REDACTED], D. Askounis, IEEE journal of biomedical and health informatics, (2021), [REDACTED]: 19
	- [[REDACTED] of [REDACTED] in [REDACTED]](https://doi.org/10.1109/icassp43922.2022.9747006) - [REDACTED], [REDACTED], [REDACTED], J. Batsis, R. Roth, IEEE [REDACTED] on Acoustics, Speech, and [REDACTED], (2021), [REDACTED]: 5
- 2020
	- [[REDACTED] with [REDACTED] for [REDACTED]](https://doi.org/10.21437/interspeech.2020-2684) - [REDACTED], B. Mirheidari, Z. C. Tu, R. O'Malley, [REDACTED], A. Venneri, M. Reuber, D. Blackburn, H. Christensen, Interspeech, (2020), [REDACTED]: 10
	- [[REDACTED] and [REDACTED] on [REDACTED] for [REDACTED]](https://arxiv.org/abs/2008.07052) - [REDACTED], [REDACTED], arXiv.org, (2020), [REDACTED]: 2
- 2019
	- [A [REDACTED] for [REDACTED] from Language](https://www.semanticscholar.org/paper/43d17de93cad046fd96caa955b6ba07d53e12de1) - [REDACTED], [REDACTED], G. Carenini, [REDACTED], [REDACTED] in [REDACTED], (2019), [REDACTED]: 15

#### Eye-tracking
- 2022
	- [[REDACTED] by [REDACTED] and Eye-[REDACTED]](https://doi.org/10.1109/icassp43922.2022.9747054) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], IEEE [REDACTED] on Acoustics, Speech, and [REDACTED], (2022), [REDACTED]: 6
- 2020
	- [Non-[REDACTED] of Alzheimer's [REDACTED] and Language](https://www.semanticscholar.org/paper/808412161cd6b5927916a0a6dcf8e03300ba4ae1) - [REDACTED], [REDACTED], [REDACTED]‐Mason, [REDACTED], [REDACTED], G. Carenini, C. Conati, [REDACTED], [REDACTED] in [REDACTED], (2020), [REDACTED]: 14

#### Features
- 2023
	- [Context is not key: [REDACTED]'s disease with both classical and transformer-based neural language models](https://doi.org/10.1016/j.nlp.2023.100046) - [REDACTED], [REDACTED], [REDACTED], (2023), [REDACTED]: 1

#### [REDACTED]
- 2024
	- [A [REDACTED] of [REDACTED] for Speech-[REDACTED]](https://doi.org/10.21437/interspeech.2024-996) - [REDACTED], [REDACTED]-Machorro, F. Eyben, Björn W. Schuller, [REDACTED], Interspeech, (2024), [REDACTED]: 0
- 2023
	- [FedCPC: [REDACTED] for [REDACTED]-[REDACTED]](https://doi.org/10.1109/ASRU57964.2023.10389690) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED] & Understanding, (2023), [REDACTED]: 0

#### Image-text
- 2023
	- [[REDACTED] for [REDACTED] using Image-text Alignment](https://doi.org/10.48550/arXiv.2308.07933) - [REDACTED], [REDACTED], [REDACTED], J. Batsis, R. Roth, B. MacWhinney, arXiv.org, (2023), [REDACTED]: 0
	- [[REDACTED] from Speech: [REDACTED] the Answer?](https://doi.org/10.3390/info15010002) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], Inf., (2023), [REDACTED]: 2

#### [REDACTED]
- 2016
	- [Vector-space topic models for detecting Alzheimer’s disease](https://doi.org/10.18653/v1/P16-1221) - [REDACTED], [REDACTED], [REDACTED] of the Association for [REDACTED], (2016), [REDACTED]: 58
- 1996
	- [[REDACTED] of Oral and [REDACTED] in Patients with Alzheimer's Disease](https://doi.org/10.1006/brln.1996.0033) - B. Croisile, B. Ska, Marie-Josée Brabant, A. Duchêne, Y. Lepage, G. Aimard, M. Trillet, Brain and Language, (1996), [REDACTED]: 201

#### [REDACTED]
- 2022
	- [Domain-aware [REDACTED] for [REDACTED] with [REDACTED]](https://doi.org/10.21437/interspeech.2022-10862) - [REDACTED], [REDACTED], J. Batsis, R. Roth, Interspeech, (2022), [REDACTED]: 5

#### [REDACTED]
- 2024
	- [[REDACTED] for [REDACTED] and [REDACTED]'s [REDACTED]](https://doi.org/10.1101/2024.08.22.24312463) - T. Mo, J. Lam, V. Li, L. Cheung, medRxiv, (2024), [REDACTED]: 0
	- [[REDACTED] of ChatGPT vs Bard in [REDACTED]'s Dementia](https://doi.org/10.48550/arXiv.2402.01751) - T. BalamuraliB., Jer-[REDACTED], arXiv.org, (2024), [REDACTED]: 1
	- [Alzheimer's disease recognition from spontaneous speech using large language models](https://doi.org/10.4218/etrij.2023-0356) - Jeong‐[REDACTED], Seung‐[REDACTED], Byung‐[REDACTED], ETRI Journal, (2024), [REDACTED]: 5
	- [Optimizing and [REDACTED]- [REDACTED] for Alzheimer's [REDACTED]](https://doi.org/10.1109/PDP62718.2024.00046) - [REDACTED], [REDACTED], A. Lagorio, G. Trunfio, [REDACTED] on Parallel, Distributed and Network-[REDACTED], (2024), [REDACTED]: 1
- 2022
	- [Predicting dementia from spontaneous speech using large language models](https://doi.org/10.1371/journal.pdig.0000168) - [REDACTED], [REDACTED], PLOS [REDACTED], (2022), [REDACTED]: 40

#### Longitudinal

#### Multi-lingual
- 2024
	- [[REDACTED] for the Detection of [REDACTED] in [REDACTED]: [REDACTED]-[REDACTED]](https://doi.org/10.2196/50537) - E. Ambrosini, [REDACTED], [REDACTED], [REDACTED], M. Milis, [REDACTED], D. Azzolino, [REDACTED], [REDACTED], [REDACTED]án de Isla, [REDACTED]-Raja, N. A. Borghese, [REDACTED], [REDACTED], JMIR Aging, (2024), [REDACTED]: 0
- 2023
	- [[REDACTED] of Alzheimer's across [REDACTED] and [REDACTED]](https://doi.org/10.21437/interspeech.2023-2079) - P. A. Pérez-Toro, T. Arias-Vergara, [REDACTED], F. Hönig, C. A. Tóbon-Quintero, D. Aguillón, F. Lopera, L. Hincapié-Henao, M. Schuster, K. Riedhammer, A. Maier, Elmar Nöth, J. Orozco-Arroyave, Interspeech, (2023), [REDACTED]: 0

#### Multi-modal
- 2024
	- [[REDACTED] of [REDACTED]](https://doi.org/10.21437/interspeech.2024-1541) - O. Roesler, J. Liscombe, [REDACTED], H. Kothare, [REDACTED], [REDACTED], [REDACTED], [REDACTED]-Oeft, [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], D. Suendermann-Oeft, [REDACTED], Interspeech, (2024), [REDACTED]: 0
- 2023
	- [[REDACTED] of Multimodality and [REDACTED] for [REDACTED]](https://doi.org/10.48550/arXiv.2311.02819) - [REDACTED], [REDACTED], arXiv.org, (2023), [REDACTED]: 0
	- [Context-[REDACTED] coupled with [REDACTED] methods for recognizing dementia from spontaneous speech](https://doi.org/10.48550/arXiv.2305.16406) - [REDACTED], D. Askounis, arXiv.org, (2023), [REDACTED]: 0
	- [[REDACTED]-Generic and Depression-[REDACTED] for Alzheimer’s [REDACTED]](https://doi.org/10.1109/ASRU57964.2023.10389785) - [REDACTED], [REDACTED], Wei-[REDACTED], [REDACTED], [REDACTED], [REDACTED] & Understanding, (2023), [REDACTED]: 0
	- [[REDACTED] for Alzheimer's [REDACTED] and [REDACTED]](https://doi.org/10.48550/arXiv.2307.02514) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], arXiv.org, (2023), [REDACTED]: 9
	- [ADMarker: A Multi-[REDACTED] for [REDACTED] of Alzheimer's Disease](https://doi.org/10.1145/3636534.3649370) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], ACM/IEEE [REDACTED] on [REDACTED] and Networking, (2023), [REDACTED]: 1

#### [REDACTED]
- 2023
	- [[REDACTED] with [REDACTED] for [REDACTED]](https://doi.org/10.1109/ICASSP49357.2023.10096579) - [REDACTED], [REDACTED], D. Askounis, M. Vazirgiannis, IEEE [REDACTED] on Acoustics, Speech, and [REDACTED], (2023), [REDACTED]: 1

#### [REDACTED]
- 2022
	- [[REDACTED] the [REDACTED]: [REDACTED] using [REDACTED]](https://doi.org/10.1007/978-3-031-16270-1_36) - [REDACTED], [REDACTED], H. Lehfeld, T. Hillemacher, K. Riedhammer, S. Bayerl, [REDACTED] on Text, Speech and Dialogue, (2022), [REDACTED]: 8
	- [[REDACTED] (HK-GSDT): A [REDACTED] for [REDACTED]](https://doi.org/10.3390/ijerph192013302) - [REDACTED], P. Wong, H. Fung, V. C. T. Mok, T. Kwok, [REDACTED], [REDACTED] WONG, [REDACTED], [REDACTED] of [REDACTED] and [REDACTED], (2022), [REDACTED]: 4

#### Pause&Disfluencies
- 2023
	- [Limited connectedness of spontaneous speech may be a marker of dementia due to Alzheimer’s disease](https://doi.org/10.3389/fnagi.2023.1252614) - M. R. Botezatu, [REDACTED], [REDACTED], Frontiers in [REDACTED], (2023), [REDACTED]: 0
	- [[REDACTED] and [REDACTED] for Alzheimer’s [REDACTED] from [REDACTED]](https://doi.org/10.3390/brainsci13030477) - [REDACTED], [REDACTED], L. Li, [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], (2023), [REDACTED]: 7
	- [[REDACTED] through ASR-based Transcriptions: Exploring the Impact of Punctuation and Pauses](https://doi.org/10.21437/Interspeech.2023-1734) - Lucía Gómez-Zaragozá, [REDACTED], C. García, J. Marín-Morales, [REDACTED]ñiz, H. Strik, Interspeech, (2023), [REDACTED]: 3
- 2022
	- [Contrast-enhanced [REDACTED] with Pause-encoder](https://doi.org/10.1109/SMC53654.2022.9945085) - Sheng-[REDACTED], Ho-[REDACTED], [REDACTED], Li-[REDACTED], Yu-[REDACTED], IEEE [REDACTED] on Systems, Man and Cybernetics, (2022), [REDACTED]: 1
	- [[REDACTED]: Measuring the Impact of [REDACTED] on [REDACTED]](https://doi.org/10.18653/v1/2022.bionlp-1.4) - [REDACTED], [REDACTED], [REDACTED], Workshop on [REDACTED], (2022), [REDACTED]: 8
- 2021
	- [Pauses for Detection of Alzheimer’s Disease](https://doi.org/10.3389/fcomp.2020.624488) - [REDACTED], [REDACTED], [REDACTED], Z. Ye, [REDACTED], Frontiers of [REDACTED], (2021), [REDACTED]: 22
	- [Speech pause distribution as an early marker for Alzheimer's disease](https://doi.org/10.1101/2020.12.28.20248875) - P. Pastoriza-Domínguez, I. G. Torre, F. Diéguez-Vide, I. Gómez-Ruiz, S. Geladó, J. Bello-López, A. Ávila-Rivera, J. Matías-Guiu, V. Pytel, A. Hernández-Fernández, medRxiv, (2021), [REDACTED]: 22
	- [Pause-[REDACTED] for Recognition of Alzheimer’s Disease and Emotion](https://doi.org/10.1109/ICASSP39728.2021.9413548) - [REDACTED], [REDACTED], [REDACTED], IEEE [REDACTED] on Acoustics, Speech, and [REDACTED], (2021), [REDACTED]: 7
- 2020
	- [Disfluencies and Fine-[REDACTED]-[REDACTED] for Detection of Alzheimer's Disease](https://doi.org/10.21437/interspeech.2020-2516) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], Z. Ye, [REDACTED], Interspeech, (2020), [REDACTED]: 85
	- [[REDACTED] to [REDACTED] in the Speech of [REDACTED]](https://doi.org/10.1177/1533317520939773) - [REDACTED], [REDACTED], [REDACTED], A. Back, T. Gibson, J. Liddle, [REDACTED], D. Copland, A. Angwin, [REDACTED] of [REDACTED] & [REDACTED], (2020), [REDACTED]: 18
- 2009
	- [[REDACTED] in Alzheimer's Discourse](https://doi.org/10.1177/1533317508328138) - [REDACTED], M. Maclagan, [REDACTED] of [REDACTED] & [REDACTED], (2009), [REDACTED]: 51

#### Perplexity
- 2024
	- [[REDACTED] to Fail: [REDACTED] are [REDACTED] to Induction of Dementia-[REDACTED]](https://doi.org/10.48550/arXiv.2406.02830) - [REDACTED], [REDACTED], [REDACTED], Serguei V. S. Pakhomov, [REDACTED] of the Association for [REDACTED], (2024), [REDACTED]: 0
- 2023
	- [[REDACTED] for the [REDACTED] of the [REDACTED]](https://doi.org/10.48550/arXiv.2302.01025) - [REDACTED], [REDACTED], [REDACTED], B. Vitiello, [REDACTED], arXiv.org, (2023), [REDACTED]: 0
- 2022
	- [GPT-D: [REDACTED]-related [REDACTED] by [REDACTED] of [REDACTED]](https://doi.org/10.48550/arXiv.2203.13397) - [REDACTED], D. Knopman, [REDACTED], T. Cohen, Serguei V. S. Pakhomov, [REDACTED] of the Association for [REDACTED], (2022), [REDACTED]: 16
- 2020
	- [A Tale of [REDACTED]: Sensitivity of [REDACTED] to [REDACTED] in Dementia of the Alzheimer’s Type](https://doi.org/10.18653/v1/2020.acl-main.176) - T. Cohen, Serguei V. S. Pakhomov, [REDACTED] of the Association for [REDACTED], (2020), [REDACTED]: 20
- 2019
	- [[REDACTED]'s Disease from [REDACTED].](https://doi.org/10.3233/JAD-190452) - [REDACTED], [REDACTED], [REDACTED], Journal of Alzheimer's Disease, (2019), [REDACTED]: 24
	- [Perplexity – a new predictor of cognitive changes in spoken language? – results of the [REDACTED] on [REDACTED] and Aging (ILSE)](https://doi.org/10.1515/lingvan-2018-0026) - C. Frankenberg, [REDACTED], [REDACTED], M. Knebel, C. Degen, H. Wahl, J. Schroeder, [REDACTED], (2019), [REDACTED]: 16
	- [[REDACTED] of Alzheimer’s [REDACTED]](https://doi.org/10.1109/ICASSP.2019.8682690) - J. Fritsch, [REDACTED], Elmar Nöth, IEEE [REDACTED] on Acoustics, Speech, and [REDACTED], (2019), [REDACTED]: 53
- 2018
	- [[REDACTED] for the [REDACTED]](https://www.semanticscholar.org/paper/88188082df9ec54d05753d88f3b4f92f31f86a9e) - N. Linz, J. Tröger, [REDACTED], A. König, P. Robert, J. Peter, J. Alexandersson, , (2018), [REDACTED]: 4
- 2017
	- [An N-[REDACTED] to the [REDACTED] of Alzheimer's Disease from [REDACTED]](https://doi.org/10.21437/Interspeech.2017-1572) - [REDACTED], Elmar Nöth, S. Evert, Interspeech, (2017), [REDACTED]: 45

#### [REDACTED]
- 2023
	- [Reformulating NLP tasks to [REDACTED] of [REDACTED] in People with Dementia](https://doi.org/10.48550/arXiv.2310.09897) - [REDACTED], [REDACTED], M. Liakata, Conference on [REDACTED] in [REDACTED], (2023), [REDACTED]: 0
- 2022
	- [[REDACTED] with Pre-[REDACTED] for Alzheimer’s [REDACTED]](https://doi.org/10.1109/ICASSP49357.2023.10095993) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], IEEE [REDACTED] on Acoustics, Speech, and [REDACTED], (2022), [REDACTED]: 6

#### Pronoun
- 2023
	- [Pronoun use in preclinical and early stages of Alzheimer's dementia](https://doi.org/10.1016/j.csl.2023.101573) - [REDACTED], C. Frankenberg, [REDACTED]öder, [REDACTED] and Language, (2023), [REDACTED]: 1

#### [REDACTED]
- 2023
	- [[REDACTED]-[REDACTED] for Alzheimer’s [REDACTED]](https://doi.org/10.1109/ICASSP49357.2023.10096205) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], D. Li, [REDACTED], [REDACTED], [REDACTED], IEEE [REDACTED] on Acoustics, Speech, and [REDACTED], (2023), [REDACTED]: 6
	- [SpeechFormer++: A [REDACTED] for [REDACTED]](https://doi.org/10.1109/TASLP.2023.3235194) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], IEEE/ACM Transactions on [REDACTED] and [REDACTED], (2023), [REDACTED]: 15
- 2022
	- [SpeechFormer: A [REDACTED] the Characteristics of Speech](https://doi.org/10.48550/arXiv.2203.03812) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], Interspeech, (2022), [REDACTED]: 26

#### [REDACTED]
- 2023
	- [Comparing global and local semantic coherence of spontaneous speech in persons with Alzheimer's disease and healthy controls.](https://doi.org/10.1016/j.acorp.2023.100064) - E. Burke, J. Gunstad, [REDACTED], [REDACTED], (2023), [REDACTED]: 4

#### [REDACTED]
- 2024
	- [Linguistic-[REDACTED]](https://doi.org/10.48550/arXiv.2402.01690) - A. P. Fard, [REDACTED], [REDACTED], [REDACTED], Comput. Biol. Medicine, (2024), [REDACTED]: 0

#### Speech and Writing
- 2023
	- [Using personal writings to detect dementia: A text mining approach](https://doi.org/10.1177/14604582231204409) - [REDACTED], [REDACTED], [REDACTED], (2023), [REDACTED]: 0
- 2021
	- [A [REDACTED]-modal Dataset for [REDACTED] and Diagnosis](https://doi.org/10.1007/s10579-023-09718-4) - [REDACTED], [REDACTED], [REDACTED], M. Wolters, A. Zubiaga, [REDACTED], M. Liakata, [REDACTED] and Evaluation, (2021), [REDACTED]: 3

#### [REDACTED]
- 2022
	- [Accuracy of telephone screening tools to identify dementia patients remotely: systematic review](https://doi.org/10.1177/20542704221115956) - [REDACTED], B. McKinstry, K. Fairhurst, JRSM Open, (2022), [REDACTED]: 3
- 2021
	- [Dementia risks identified by vocal features via telephone conversations: A novel machine learning prediction model](https://doi.org/10.1371/journal.pone.0253988) - A. Shimoda, [REDACTED], H. Hayashi, N. Kondo, PLoS ONE, (2021), [REDACTED]: 28
	- [Diagnostic accuracy of the telephone interview for cognitive status (TICS) for the detection of dementia in primary care in the Netherlands](https://doi.org/10.1002/alz.052760) - H. Abdulrahman, Alzheimer's & Dementia, (2021), [REDACTED]: 0
- 2015
	- [[REDACTED]: new performance-based activities of daily living tests for early Alzheimer's disease.](https://doi.org/10.14283/JPAD.2015.72) - G. Marshall, M. Dekhtyar, [REDACTED], K. Jethwani, R. Amariglio, [REDACTED], R. Sperling, D. Rentz, The journal of prevention of Alzheimer's disease, (2015), [REDACTED]: 21
- 2007
	- [Validation of the [REDACTED] for [REDACTED] (TICS) in Japanese](https://doi.org/10.1002/gps.1812) - Y. Konagaya, Y. Washimi, H. Hattori, A. Takeda, [REDACTED], T. Ohta, [REDACTED] of [REDACTED], (2007), [REDACTED]: 34
- 1988
	- [The telephone interview for cognitive status](https://www.semanticscholar.org/paper/f29b4c35e8b57cebb570eaadbee1bdb95fd5d716) - J. Brandt, M. Spencer, M. Folstein, , (1988), [REDACTED]: 580

#### [REDACTED]
- 2023
	- [Speech patterns in responses to questions asked by an intelligent virtual agent can help to distinguish between people with early stage neurodegenerative disorders and healthy controls.](https://doi.org/10.1080/02699206.2023.2254458) - [REDACTED], [REDACTED], R. O'Malley, [REDACTED], [REDACTED], [REDACTED], D. Blackburn, [REDACTED] & Phonetics, (2023), [REDACTED]: 0
	- [[REDACTED] of [REDACTED]](https://doi.org/10.1109/ICASSP49357.2023.10095825) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], J. Batsis, R. Roth, [REDACTED], IEEE [REDACTED] on Acoustics, Speech, and [REDACTED], (2023), [REDACTED]: 2
- 2022
	- [Evaluating voice-assistant commands for dementia detection](https://doi.org/10.1016/j.csl.2021.101297) - [REDACTED], J. Batsis, [REDACTED], [REDACTED], R. Roth, D. Kotz, B. MacWhinney, [REDACTED] and Language, (2022), [REDACTED]: 19
	- [Alzheimer's [REDACTED] through [REDACTED] with [REDACTED]](https://doi.org/10.1109/HRI53351.2022.9889375) - [REDACTED], [REDACTED], [REDACTED], K. Inoue, [REDACTED], IEEE/ACM [REDACTED] on Human-[REDACTED], (2022), [REDACTED]: 9
- 2017
	- [[REDACTED]-[REDACTED] for [REDACTED] to [REDACTED]](https://doi.org/10.21437/Interspeech.2017-690) - B. Mirheidari, D. Blackburn, K. Harkness, [REDACTED], A. Venneri, M. Reuber, H. Christensen, Interspeech, (2017), [REDACTED]: 30

### 4. Regular papers
- 2024
	- [Comparison of AI with and without hand-crafted features to classify Alzheimer's disease in different languages](https://doi.org/10.1016/j.compbiomed.2024.108950) - [REDACTED], [REDACTED], J. Chun, [REDACTED], Dai-[REDACTED], I. Choi, [REDACTED], [REDACTED], Comput. Biol. Medicine, (2024), [REDACTED]: 1
	- [Analysis of [REDACTED] for the Detection of [REDACTED]](https://doi.org/10.1109/ACCESS.2024.3442431) - Moisés R. Pacheco-Lorenzo, [REDACTED], [REDACTED]-Rifón, M. J. Fernández-Iglesias, [REDACTED]-Rodríguez, IEEE Access, (2024), [REDACTED]: 0
	- [A novel speech analysis algorithm to detect cognitive impairment in a Spanish population](https://doi.org/10.3389/fneur.2024.1342907) - [REDACTED], L. Lacritz, [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED]énez-Raboso, [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], L. Rosenstein, C. M. Cullum, [REDACTED], [REDACTED], Frontiers in Neurology, (2024), [REDACTED]: 0
	- [LoSST-AD: A [REDACTED] for [REDACTED]’s [REDACTED] in [REDACTED]](https://www.semanticscholar.org/paper/b48acc125e8ec208254e8210d9ee8b0c3466b72c) - [REDACTED], [REDACTED], [REDACTED] on [REDACTED] and Evaluation, (2024), [REDACTED]: 0
	- [Automatic detection of [REDACTED] using high-dimensional acoustic features in spontaneous speech](https://arxiv.org/abs/2408.16732) - [REDACTED], [REDACTED], [REDACTED], , (2024), [REDACTED]: 0
	- [ML-[REDACTED] of Linguistic and [REDACTED] in [REDACTED]’s Disease](https://doi.org/10.14201/adcaij.31625) - [REDACTED], [REDACTED], Advances in [REDACTED] and [REDACTED], (2024), [REDACTED]: 0
	- [Screening for Alzheimer's Disease in [REDACTED] on [REDACTED]](https://doi.org/10.1109/IALP63756.2024.10661175) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED] on [REDACTED], (2024), [REDACTED]: 0
	- [Automatic speech analysis for detecting cognitive decline of older adults](https://doi.org/10.3389/fpubh.2024.1417966) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], Frontiers in [REDACTED], (2024), [REDACTED]: 0
	- [Exploring the Efficacy of [REDACTED] in [REDACTED] from Speech](https://doi.org/10.1109/HSI61632.2024.10613581) - [REDACTED], [REDACTED], O. Jemai, M. El-Yacoubi, [REDACTED] on [REDACTED], (2024), [REDACTED]: 0
	- [Prosody-[REDACTED]-[REDACTED]](https://doi.org/10.48550/arXiv.2407.03470) - [REDACTED], [REDACTED], [REDACTED], Interspeech, (2024), [REDACTED]: 0
	- [[REDACTED] and Acoustic features from [REDACTED] for [REDACTED]’s [REDACTED]](https://doi.org/10.1109/ATSIP62566.2024.10639034) - [REDACTED]Shareif, [REDACTED], [REDACTED], M. A. Ali, [REDACTED] on [REDACTED] for Signal and [REDACTED], (2024), [REDACTED]: 0
	- [[REDACTED]-[REDACTED] for [REDACTED]: A [REDACTED] in [REDACTED]](https://doi.org/10.14283/jarlife.2024.6) - B. Ceyhan, S. Bek, T. Önal-Süzek, JAR life, (2024), [REDACTED]: 1
	- [Early dementia detection with speech analysis and machine learning techniques](https://doi.org/10.1007/s43621-024-00217-2) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], (2024), [REDACTED]: 0
	- [[REDACTED]: Towards an [REDACTED] for [REDACTED]](https://doi.org/10.1145/3660515.3661326) - [REDACTED], [REDACTED], [REDACTED], A. Rongve, [REDACTED], [REDACTED], [REDACTED], (2024), [REDACTED]: 0
- 2023
	- [Natural language processing-driven framework for the early detection of language and cognitive decline](https://doi.org/10.1016/j.laheal.2023.09.002) - [REDACTED], María Beatriz Pérez Cabello de Alba, Language and Health, (2023), [REDACTED]: 4
	- [[REDACTED]-linguistic [REDACTED] from [REDACTED] to [REDACTED] and Dementia](https://doi.org/10.14283/jarlife.2023.12) - D. Mizuguchi, T. Yamamoto, Y. Omiya, K. Endo, K. Tano, M. Oya, S. Takano, JAR life, (2023), [REDACTED]: 0
	- [A [REDACTED] for Speech-based [REDACTED]](https://doi.org/10.1109/lsp.2023.3291651) - [REDACTED], [REDACTED], [REDACTED], H. Zhang, IEEE [REDACTED], (2023), [REDACTED]: 0
	- [Reading and lexical–semantic retrieval tasks outperforms single task speech analysis in the screening of mild cognitive impairment and Alzheimer's disease](https://doi.org/10.1038/s41598-023-36804-y) - [REDACTED]ínez-Nicolás, F. Martínez-Sánchez, O. Ivanova, J. J. Meilán, [REDACTED], (2023), [REDACTED]: 1
	- [[REDACTED] of Alzheimer's Disease using [REDACTED] extracted from [REDACTED]](https://doi.org/10.48550/arXiv.2307.08070) - M. Kurdi, arXiv.org, (2023), [REDACTED]: 1
	- [Alzheimer's [REDACTED] from [REDACTED] and Text: A review](https://doi.org/10.48550/arXiv.2307.10005) - K. VrindhaM., V. Geethu, R. AnurenjanP., S. Deepak, G. SreeniK., arXiv.org, (2023), [REDACTED]: 0
	- [[REDACTED] and [REDACTED] for Alzheimer’s [REDACTED] from [REDACTED]](https://doi.org/10.3390/brainsci13030477) - [REDACTED], [REDACTED], L. Li, [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], (2023), [REDACTED]: 7
	- [[REDACTED] for the Detection of Depression in Alzheimer’s [REDACTED]](https://doi.org/10.1109/ICASSP49357.2023.10095219) - P. A. Pérez-Toro, [REDACTED]íguez-Salas, T. Arias-Vergara, S. Bayerl, P. Klumpp, K. Riedhammer, [REDACTED], E. Nöth, [REDACTED], J. Orozco-Arroyave, IEEE [REDACTED] on Acoustics, Speech, and [REDACTED], (2023), [REDACTED]: 4
	- [Dementia classification using attention mechanism on audio data](https://doi.org/10.1109/SAMI58000.2023.10044539) - [REDACTED], [REDACTED] on [REDACTED] and Informatics, (2023), [REDACTED]: 0
	- [A [REDACTED]-[REDACTED] to predict Signs of Dementia](https://doi.org/10.1016/j.neucom.2023.126413) - [REDACTED]-Perez, [REDACTED]-Ponce, [REDACTED]ás, José Raúl Rodríguez Rodríguez, M. Vizcaya-Moreno, [REDACTED], Neurocomputing, (2023), [REDACTED]: 2
	- [[REDACTED] of Alzheimer's Disease: [REDACTED] of [REDACTED]](https://doi.org/10.1109/ICAAIC56838.2023.10140703) - [REDACTED], [REDACTED], [REDACTED], P. G. Shambharkar, 2023 2nd [REDACTED] on [REDACTED] and Computing (ICAAIC), (2023), [REDACTED]: 0
	- [Alzheimer’s [REDACTED] (Audio vs. Text): Multi-[REDACTED] at High vs. [REDACTED]](https://doi.org/10.3390/app13074244) - [REDACTED], [REDACTED], J. Melechovský, [REDACTED], B. B. T., Jer-[REDACTED], [REDACTED], (2023), [REDACTED]: 7
	- [An automated speech analysis system for the detection of cognitive decline in elderly](https://doi.org/10.1007/s10772-023-10016-1) - C. Loizou, M. Pantzaris, [REDACTED] of [REDACTED], (2023), [REDACTED]: 0
	- [[REDACTED] and [REDACTED] for [REDACTED] from [REDACTED]](https://doi.org/10.1109/ICASSP49357.2023.10095140) - [REDACTED], M. Mak, H. Meng, IEEE [REDACTED] on Acoustics, Speech, and [REDACTED], (2023), [REDACTED]: 1
	- [Who needs context? Classical techniques for Alzheimer’s disease detection](https://doi.org/10.18653/v1/2023.clinicalnlp-1.13) - [REDACTED], [REDACTED], [REDACTED], (2023), [REDACTED]: 0
	- [Speech-based detection of multi-class Alzheimer's disease classification using machine learning](https://doi.org/10.1007/s41060-023-00475-9) - [REDACTED], [REDACTED], [REDACTED] of [REDACTED] and Analysis, (2023), [REDACTED]: 0
	- [Distinguishable features of spontaneous speech in Alzheimer’s clinical syndrome and healthy controls](https://doi.org/10.1080/13825585.2023.2221020) - E. Burke, J. Gunstad, [REDACTED], [REDACTED], Neuropsychology, development, and cognition. Section B, Aging, neuropsychology and cognition, (2023), [REDACTED]: 2
	- [Detection of [REDACTED]-Semantic, [REDACTED]: [REDACTED]](https://doi.org/10.2196/55126) - [REDACTED], [REDACTED], C. Karjadi, [REDACTED], [REDACTED], [REDACTED], [REDACTED], JMIR Aging, (2023), [REDACTED]: 0
	- [Performance of machine learning algorithms for dementia assessment: impacts of language tasks, recording media, and modalities](https://doi.org/10.1186/s12911-023-02122-6) - Mahboobeh (Mah) Parsapoor (Parsa), [REDACTED], [REDACTED], BMC [REDACTED] and [REDACTED], (2023), [REDACTED]: 7
- 2022
	- [Automatic cognitive assessment: Combining sparse datasets with disparate cognitive scores](https://doi.org/10.21437/interspeech.2022-10205) - B. Mirheidari, [REDACTED], H. Christensen, Interspeech, (2022), [REDACTED]: 0
	- [[REDACTED]-to-[REDACTED] to [REDACTED]](https://doi.org/10.1109/icassp43922.2022.9746148) - [REDACTED]áb, José [REDACTED] López, R. Balogh, N. Imre, I. Hoffmann, L. Tóth, M. Pákáski, J. Kálmán, G. Gosztolya, IEEE [REDACTED] on Acoustics, Speech, and [REDACTED], (2022), [REDACTED]: 2
	- [[REDACTED] of [REDACTED] for [REDACTED] in Cantonese-[REDACTED]](https://doi.org/10.21437/interspeech.2022-10122) - [REDACTED], M. Mak, [REDACTED], Interspeech, (2022), [REDACTED]: 2
	- [[REDACTED]-[REDACTED]-To-[REDACTED] and Assessment of Alzheimer’s [REDACTED]](https://doi.org/10.3390/brainsci13010028) - [REDACTED], [REDACTED], [REDACTED], (2022), [REDACTED]: 15
	- [[REDACTED]-[REDACTED] for Early-[REDACTED]'s [REDACTED]](https://doi.org/10.21437/interspeech.2022-943) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], T. Shinozaki, Interspeech, (2022), [REDACTED]: 3
	- [A [REDACTED] for [REDACTED] from [REDACTED] with [REDACTED]](https://doi.org/10.1109/BHI56158.2022.9926818) - [REDACTED], D. Askounis, J. Psarras, 2022 IEEE-EMBS [REDACTED] on Biomedical and [REDACTED] (BHI), (2022), [REDACTED]: 5
	- [A [REDACTED] on [REDACTED] of [REDACTED] a [REDACTED]](https://doi.org/10.1109/LifeTech53646.2022.9754933) - [REDACTED], [REDACTED], [REDACTED], R. Ohdake, M. Masuda, [REDACTED], [REDACTED] on [REDACTED] and Technologies, (2022), [REDACTED]: 3
	- [Automated detection of mild cognitive impairment and dementia from voice recordings: A natural language processing approach](https://doi.org/10.1002/alz.12721) - S. Amini, [REDACTED], [REDACTED], [REDACTED], [REDACTED], C. Karjadi, V. Kolachalama, R. Au, I. Paschalidis, Alzheimer's & Dementia, (2022), [REDACTED]: 27
	- [[REDACTED] from [REDACTED] of [REDACTED]](https://doi.org/10.14283/jpad.2022.66) - N. Tavabi, D. Stück, A. Signorini, C. Karjadi, T. [REDACTED], M. Sandoval, C. Lemke, J. Glass, S. Hardy, M. Lavallee, B. Wasserman, T. F. Ang, C. Nowak, R. Kainkaryam, L. Foschini, R. Au, The journal of prevention of Alzheimer's disease, (2022), [REDACTED]: 11
	- [Computer-[REDACTED]: [REDACTED]?](https://doi.org/10.1109/RTSI55261.2022.9905097) - [REDACTED], [REDACTED], [REDACTED], M. Santambrogio, [REDACTED] on Research and Technologies for Society and [REDACTED] a better tomorrow, (2022), [REDACTED]: 3
	- [[REDACTED] for [REDACTED]'s Dementia from [REDACTED] of ILSE Study](https://doi.org/10.21437/interspeech.2022-10942) - [REDACTED], K. Scholz, [REDACTED], Interspeech, (2022), [REDACTED]: 3
	- [[REDACTED]-based [REDACTED] for Alzheimer’s [REDACTED]](https://doi.org/10.1109/SMC53654.2022.9945127) - Sheng-[REDACTED], Ho-[REDACTED], Jwu-[REDACTED], [REDACTED], Yu-[REDACTED], Li-[REDACTED], IEEE [REDACTED] on Systems, Man and Cybernetics, (2022), [REDACTED]: 0
	- [A Pre-trained [REDACTED] to [REDACTED]’s Disease at an [REDACTED]](https://doi.org/10.14569/ijacsa.2022.0130524) - [REDACTED], [REDACTED], [REDACTED] of [REDACTED] and Applications, (2022), [REDACTED]: 5
	- [Revealing the Roles of Part-of-[REDACTED] in [REDACTED]: [REDACTED]-[REDACTED]](https://doi.org/10.2196/36590) - [REDACTED], [REDACTED], K.P. Subbalakshmi, R. Chandramouli, JMIR [REDACTED], (2022), [REDACTED]: 0
	- [Multimodal fusion for alzheimer’s disease recognition](https://doi.org/10.1007/s10489-022-04255-z) - [REDACTED], [REDACTED], [REDACTED], Applied intelligence (Boston), (2022), [REDACTED]: 13
	- [Impact of [REDACTED] on Alzheimer's [REDACTED] from Speech: [REDACTED]?](https://doi.org/10.48550/arXiv.2203.17110) - [REDACTED], arXiv.org, (2022), [REDACTED]: 0
	- [[REDACTED] on the Mini-[REDACTED] (MMSE) from [REDACTED]](https://doi.org/10.3390/bs12090339) - A. Bueno-Cayo, Minerva del [REDACTED], [REDACTED]-Enguix, I. Iborra-Marmolejo, [REDACTED], T. Q. Irigaray, José [REDACTED], C. Moret-Tatay, [REDACTED], (2022), [REDACTED]: 2
	- [Automated text‐level semantic markers of Alzheimer's disease](https://doi.org/10.1002/dad2.12276) - [REDACTED], [REDACTED], A. Slachevsky, G. Forno, [REDACTED], [REDACTED], A. Ibáñez, E. Tagliazucchi, [REDACTED]ía, Alzheimer's & Dementia, (2022), [REDACTED]: 16
	- [A [REDACTED] for [REDACTED]'s [REDACTED] on Speech and [REDACTED]](https://doi.org/10.3389/fpubh.2022.772592) - Ning-hong Liu, [REDACTED], [REDACTED], [REDACTED], Frontiers in [REDACTED], (2022), [REDACTED]: 20
	- [[REDACTED] from Speech: [REDACTED]](https://doi.org/10.1109/icassp43922.2022.9747167) - [REDACTED], [REDACTED], A. Abad, [REDACTED], I. Trancoso, IEEE [REDACTED] on Acoustics, Speech, and [REDACTED], (2022), [REDACTED]: 12
	- [[REDACTED] on [REDACTED] in [REDACTED] on Speech](https://doi.org/10.1109/ACCESS.2022.3203068) - [REDACTED], [REDACTED], T. Ohtsuki, IEEE Access, (2022), [REDACTED]: 4
	- [[REDACTED] SBERT for [REDACTED]](https://doi.org/10.3390/brainsci12020270) - [REDACTED]-Cruz, Sebastián Salazar-Colores, W. J. Paredes-García, [REDACTED]-Arenas, S. Tovar-Arriaga, [REDACTED], (2022), [REDACTED]: 25
	- [Exploring linguistic feature and model combination for speech recognition based automatic AD detection](https://doi.org/10.48550/arXiv.2206.13758) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], Interspeech, (2022), [REDACTED]: 12
	- [[REDACTED]'s [REDACTED] on [REDACTED] from Pre-trained Models](https://doi.org/10.1007/978-3-031-20503-3_22) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], CAAI [REDACTED] on [REDACTED], (2022), [REDACTED]: 1
	- [Evaluation of Wav2[REDACTED] for Speakers with [REDACTED]](https://doi.org/10.1007/978-3-031-16270-1_41) - J. Svec, [REDACTED]ák, A. Bartoš, M. Zapletalová, Martin Víta, [REDACTED] on Text, Speech and Dialogue, (2022), [REDACTED]: 4
	- [[REDACTED] for [REDACTED] using [REDACTED]](https://doi.org/10.1109/eSmarTA56775.2022.9935379) - H. Sahu, [REDACTED], S. Alsamhi, M. K. Chaube, E. Curry, 2022 2nd [REDACTED] on [REDACTED] and Applications (eSmarTA), (2022), [REDACTED]: 5
- 2021
	- [[REDACTED]’s Disease from [REDACTED] with [REDACTED] and [REDACTED]](https://doi.org/10.1109/ICASSP39728.2021.9413566) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], IEEE [REDACTED] on Acoustics, Speech, and [REDACTED], (2021), [REDACTED]: 15
	- [Multi-[REDACTED] of Age and [REDACTED] from Speech](https://doi.org/10.1109/ICASSP39728.2021.9414642) - [REDACTED], [REDACTED], D. Blackburn, H. Christensen, Aki Härmä, IEEE [REDACTED] on Acoustics, Speech, and [REDACTED], (2021), [REDACTED]: 7
	- [Development of the [REDACTED] for [REDACTED] the [REDACTED]](https://doi.org/10.1109/ICASSP39728.2021.9413634) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], H. Meng, IEEE [REDACTED] on Acoustics, Speech, and [REDACTED], (2021), [REDACTED]: 31
	- [[REDACTED] from Speech and Transcripts using Transformers](https://doi.org/10.1016/j.csl.2023.101485) - [REDACTED], D. Askounis, J. Psarras, [REDACTED] and Language, (2021), [REDACTED]: 21
	- [[REDACTED]](https://doi.org/10.21437/interspeech.2021-915) - B. Mirheidari, [REDACTED], [REDACTED], R. O'Malley, H. Christensen, Interspeech, (2021), [REDACTED]: 3
	- [[REDACTED] of [REDACTED] for Prediction of Alzheimer's Disease, [REDACTED] and [REDACTED]](https://doi.org/10.1109/ICTC52510.2021.9620780) - [REDACTED], [REDACTED], [REDACTED], C. Yun, S. Choi, Jae-[REDACTED], Information and [REDACTED], (2021), [REDACTED]: 3
	- [[REDACTED] of [REDACTED] for [REDACTED] and [REDACTED]](https://doi.org/10.1162/coli_a_00428) - V. Vincze, [REDACTED]ó, I. Hoffmann, L. Tóth, M. Pákáski, J. Kálmán, G. Gosztolya, [REDACTED] on [REDACTED], (2021), [REDACTED]: 7
	- [Correlating natural language processing and automated speech analysis with clinician assessment to quantify speech-language changes in mild cognitive impairment and Alzheimer’s dementia](https://doi.org/10.1186/s13195-021-00848-x) - [REDACTED], [REDACTED], E. Rochon, M. Lavoie, [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], [REDACTED], Alzheimer's Research & Therapy, (2021), [REDACTED]: 46
	- [Acoustic and [REDACTED] to [REDACTED]-Onset and [REDACTED]’s Disease](https://doi.org/10.1109/ICASSP39728.2021.9414009) - P. A. Pérez-Toro, J. C. Vásquez-Correa, T. Arias-Vergara, P. Klumpp, M. Sierra-Castrillón, M. E. Roldán-López, D. Aguillón, L. Hincapié-Henao, C. A. Tóbon-Quintero, T. Bocklet, M. Schuster, J. Orozco-Arroyave, Elmar Nöth, IEEE [REDACTED] on Acoustics, Speech, and [REDACTED], (2021), [REDACTED]: 7
	- [A [REDACTED] of Acoustic and [REDACTED] for Alzheimer's [REDACTED]](https://doi.org/10.1109/ICASSP39728.2021.9414147) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], M. Mak, B. Mak, [REDACTED], [REDACTED], IEEE [REDACTED] on Acoustics, Speech, and [REDACTED], (2021), [REDACTED]: 22
	- [Exploring neural models for predicting dementia from language](https://doi.org/10.1016/J.CSL.2020.101181) - [REDACTED], [REDACTED], G. Carenini, [REDACTED], [REDACTED] and Language, (2021), [REDACTED]: 10
	- [Exploiting linguistic information from Nepali transcripts for early detection of Alzheimer's disease using natural language processing and machine learning techniques](https://doi.org/10.1016/j.ijhcs.2021.102761) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], H. Huo, [REDACTED], [REDACTED], Int. J. Hum. Comput. Stud., (2021), [REDACTED]: 27
- 2020
	- [Transformer-based deep neural network language models for Alzheimer’s disease detection from targeted speech](https://doi.org/10.21203/rs.3.rs-49267/v1) - A. Roshanzamir, H. Aghajan, M. Baghshah, , (2020), [REDACTED]: 3
	- [Uncertainty-[REDACTED]-[REDACTED] for [REDACTED] of Alzheimer's Dementia](https://arxiv.org/abs/2010.01440) - U. Sarawgi, W. Zulfikar, [REDACTED], P. Maes, arXiv.org, (2020), [REDACTED]: 2
	- [[REDACTED] of [REDACTED] for Detection of Alzheimer's Dementia in [REDACTED]](https://doi.org/10.1109/JSTSP.2019.2955022) - F. Haider, S. de la Fuente, S. Luz, IEEE Journal on [REDACTED] in [REDACTED], (2020), [REDACTED]: 122
	- [[REDACTED], [REDACTED] and [REDACTED] to [REDACTED]'s Disease](https://arxiv.org/abs/2011.09272) - [REDACTED]'us, [REDACTED]-Filbà, arXiv.org, (2020), [REDACTED]: 8
	- [[REDACTED] and Deficits](https://doi.org/10.1109/ACCESS.2020.3029907) - [REDACTED], [REDACTED], [REDACTED], [REDACTED], IEEE Access, (2020), [REDACTED]: 6
	- [Using narratives in differential diagnosis of neurodegenerative syndromes.](https://doi.org/10.1016/j.jcomdis.2020.105994) - [REDACTED]-Shah, [REDACTED], N. Ratner, [REDACTED], K. Webster, K. Tsapkini, Journal of [REDACTED], (2020), [REDACTED]: 16
	- [Linguistic markers predict onset of Alzheimer's disease](https://doi.org/10.1016/j.eclinm.2020.100583) - [REDACTED], [REDACTED], M. Santamaria, G. Cecchi, M. Naylor, EClinicalMedicine, (2020), [REDACTED]: 108
- 2019
	- [Multilingual prediction of Alzheimer’s disease through domain adaptation and concept-based language modelling](https://doi.org/10.18653/v1/N19-1367) - [REDACTED], N. Linz, [REDACTED], K. L. Fors, [REDACTED], A. König, J. Alexandersson, P. Robert, D. Kokkinakis, [REDACTED] of the Association for [REDACTED], (2019), [REDACTED]: 18
	- [Multilingual word embeddings for the assessment of narrative speech in mild cognitive impairment](https://doi.org/10.1016/j.csl.2018.07.005) - [REDACTED], K. L. Fors, D. Kokkinakis, [REDACTED] and Language, (2019), [REDACTED]: 45
	- [A [REDACTED] for [REDACTED] from Language](https://www.semanticscholar.org/paper/43d17de93cad046fd96caa955b6ba07d53e12de1) - [REDACTED], [REDACTED], G. Carenini, [REDACTED], [REDACTED] in [REDACTED], (2019), [REDACTED]: 15
	- [[REDACTED] for Detecting AD](https://doi.org/10.21437/interspeech.2019-1799) - [REDACTED], B. Mirheidari, M. Reuber, A. Venneri, D. Blackburn, H. Christensen, Interspeech, (2019), [REDACTED]: 29
	- [Detecting dementia in [REDACTED] using transfer learning from a parallel corpus](https://doi.org/10.18653/v1/N19-1199) - [REDACTED], Y. Hsu, [REDACTED], [REDACTED] of the Association for [REDACTED], (2019), [REDACTED]: 11
	- [[REDACTED]'s Disease by estimating attention and elicitation path through the alignment of spoken picture descriptions with the picture prompt](https://arxiv.org/abs/1910.00515) - B. Mirheidari, [REDACTED], [REDACTED], M. Reuber, A. Venneri, D. Blackburn, H. Christensen, arXiv.org, (2019), [REDACTED]: 6
	- [[REDACTED] for Alzheimer’s [REDACTED] on [REDACTED] and [REDACTED]](https://doi.org/10.1038/s41598-019-56020-x) - Yi-[REDACTED], Sheng-[REDACTED], W. Cheah, Li-[REDACTED], Yu-[REDACTED], L. Fu, [REDACTED], (2019), [REDACTED]: 44
	- [Predicting MCI [REDACTED]](https://doi.org/10.3389/fnagi.2019.00205) - [REDACTED], [REDACTED], M. Eckerström, Fredrik Öhman, D. Kokkinakis, Frontiers in [REDACTED], (2019), [REDACTED]: 63
	- [[REDACTED] of Alzheimer’s [REDACTED]](https://doi.org/10.1109/ICASSP.2019.8682690) - J. Fritsch, [REDACTED], Elmar Nöth, IEEE [REDACTED] on Acoustics, Speech, and [REDACTED], (2019), [REDACTED]: 53
	- [[REDACTED]-[REDACTED] for [REDACTED] of Alzheimer's Disease from [REDACTED]](https://doi.org/10.21437/interspeech.2019-2872) - [REDACTED], [REDACTED], [REDACTED], Interspeech, (2019), [REDACTED]: 32
- 2018
	- [Augmenting word2vec with latent Dirichlet allocation within a clinical application](https://doi.org/10.18653/v1/N19-1414) - [REDACTED], [REDACTED], [REDACTED] of the Association for [REDACTED], (2018), [REDACTED]: 9
	- [Detecting cognitive impairments by agreeing on interpretations of linguistic features](https://doi.org/10.18653/v1/N19-1146) - [REDACTED], [REDACTED], [REDACTED], [REDACTED] of the Association for [REDACTED], (2018), [REDACTED]: 25
	- [[REDACTED] for [REDACTED]: [REDACTED]](https://doi.org/10.1109/aiccsa.2018.8612831) - [REDACTED], [REDACTED], ACS/IEEE [REDACTED] on [REDACTED] and Applications, (2018), [REDACTED]: 24
	- [[REDACTED] of [REDACTED]](https://doi.org/10.21437/Interspeech.2018-1764) - B. Mirheidari, D. Blackburn, [REDACTED], A. Venneri, M. Reuber, H. Christensen, Interspeech, (2018), [REDACTED]: 52
	- [Deep language space neural network for classifying mild cognitive impairment and Alzheimer-type dementia](https://doi.org/10.1371/journal.pone.0205636) - S. Orimaye, [REDACTED]-[REDACTED], C. P. Wong, PLoS ONE, (2018), [REDACTED]: 46
	- [[REDACTED]'s [REDACTED] from [REDACTED]](https://doi.org/10.21437/Interspeech.2018-1713) - [REDACTED], [REDACTED], K. Shinoda, Interspeech, (2018), [REDACTED]: 38
	- [Learning multiview embeddings for assessing dementia](https://doi.org/10.18653/v1/D18-1304) - Chloé Pou-Prom, [REDACTED], Conference on [REDACTED] in [REDACTED], (2018), [REDACTED]: 14
- 2017
	- [[REDACTED] and Detection of Alzheimer's [REDACTED] from [REDACTED]](https://doi.org/10.1109/CBMS.2017.41) - S. Luz, 2017 IEEE 30th [REDACTED] on Computer-[REDACTED] (CBMS), (2017), [REDACTED]: 39
	- [INVESTIGATING PREDICTORS OF COGNITIVE DECLINE USING MACHINE LEARNING](https://doi.org/10.1016/j.jalz.2017.06.1257) - R. Casanova, [REDACTED], M. Lutz, B. Plassman, M. Kuchibhatla, K. Hayden, Alzheimer's & Dementia, (2017), [REDACTED]: 42
- 2016
	- [[REDACTED] from [REDACTED] by Correlation-[REDACTED]](https://doi.org/10.21437/Interspeech.2016-384) - G. Gosztolya, L. Tóth, Tamás Grósz, V. Vincze, I. Hoffmann, Gréta Szatlóczki, M. Pákáski, J. Kálmán, Interspeech, (2016), [REDACTED]: 35
- 2015
	- [[REDACTED]'s Disease in [REDACTED].](https://doi.org/10.3233/JAD-150520) - [REDACTED], [REDACTED], [REDACTED], Journal of Alzheimer's Disease, (2015), [REDACTED]: 597

### 5. Related works in other domains

#### Aphasia
- 2020
	- [BlaBla: [REDACTED] for [REDACTED] in [REDACTED]](https://doi.org/10.21437/interspeech.2020-2880) - [REDACTED], J. Weston, R. Lenain, E. Fristed, Interspeech, (2020), [REDACTED]: 6

#### Asthma
- 2020
	- [Analysis of [REDACTED] for [REDACTED] of Asthmatic and [REDACTED]](https://doi.org/10.1109/ICASSP40776.2020.9054062) - [REDACTED], [REDACTED], D. Gope, U. Krishnaswamy, P. Ghosh, IEEE [REDACTED] on Acoustics, Speech, and [REDACTED], (2020), [REDACTED]: 23

#### Depression
- 2023
	- [[REDACTED] in the Presence of Depression: A Cross-[REDACTED]](https://doi.org/10.21437/interspeech.2023-1997) - [REDACTED], S. Bayerl, P. A. P'erez-Toro, F. Hönig, H. Lehfeld, T. Hillemacher, Elmar Nöth, T. Bocklet, K. Riedhammer, Interspeech, (2023), [REDACTED]: 2

#### Disfluency
- 2020
	- [[REDACTED] by Self-Training a Self-[REDACTED]](https://doi.org/10.18653/v1/2020.acl-main.346) - [REDACTED], [REDACTED], [REDACTED] of the Association for [REDACTED], (2020), [REDACTED]: 42
	- [Re-framing [REDACTED] for [REDACTED] with Multi-task Learning](https://doi.org/10.18653/V1/2020.COLING-MAIN.43) - [REDACTED], [REDACTED], [REDACTED] on [REDACTED], (2020), [REDACTED]: 10
- 2019
	- [[REDACTED] of [REDACTED]](https://doi.org/10.18653/v1/N19-1282) - [REDACTED], [REDACTED], [REDACTED], [REDACTED] of the Association for [REDACTED], (2019), [REDACTED]: 25

#### Parkinson’s Disease
- 2021
	- [[REDACTED] for Parkinson's [REDACTED]](https://arxiv.org/abs/2106.00531) - [REDACTED], I. Kodrasi, ITG Conference on [REDACTED], (2021), [REDACTED]: 11
- 2020
	- [Using X-Vectors to [REDACTED]’s Disease from Speech](https://doi.org/10.1109/ICASSP40776.2020.9053770) - L. Moro-Velázquez, J. Villalba, N. Dehak, IEEE [REDACTED] on Acoustics, Speech, and [REDACTED], (2020), [REDACTED]: 45


***

_This file was generated by [awesome-paper-list-generator](https://github.com/billzyx/awesome-paper-list-generator), on 2024-09-14_
