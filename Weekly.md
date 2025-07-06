# Weekly Progress Log

*Author: **Victor Trost***

> **How to use this file**
>
> 1. **Worked on (last week)** – A report of the concrete tasks you completed in the week that just ended.
> 2. **Plan for next week** – A report of the tasks you intend to tackle in the upcoming week.
>
> Update your entry by Sunday 23:59 each week.

---

## Week 1 · 19 – 25 May 2025

## **Worked on (last week):**
- Got gem5 to compile on the server (the provided one didn't produce a `gem5.opt`: I used the v23.01 of the offical source, since v24 changed the entire build procedure of CC-protocols)
  - Compiled `X86_MESI_unord`, `X86_MOESI_CMP_directory_edit` 
  - Couldn't compile `X86_MESI_unord_CXL`: Seems like the generated slicc is wrong/malformed
  - Also couldn't compile 'X86_MSI_unord'  : Somehow the build system looks for the `.sm` files in the `src/mem/ruby/protocol` instead of the `src/custom/generated-slicc/`
- Ran some benchmarks:
  - Phoenix worked fine, but some of the Splash sub-benchmarks didn't work (input files not found)
- Had a look at the gem5 setup `setup_real.py`  
- Read up on MESIF ([here](https://blog.jyotiprakash.org/a-primer-on-cache-coherence-protocols))
- Checked out the `.pcc` of ProtoGEN


## **Plan for next week (26 May – 1 Jun 2025):**
- [ ] Get Splash to work fully
- [ ] Get more protocols to compile
- [x] Write my own gem5 `setup.py`
- [x] Read more about MESIF i.e. [here](https://www.scss.tcd.ie/jeremy.jones/vivio/caches/Andrew%20Hay%20MESIF%20Cache%20Coherency%20Protocol%202012.pdf)
- [x] Try to understand more about the `.pcc` files
- [ ] ~~Have a look at CXLGen Codebase~~


---

## Week 2 · 26 May – 1 Jun 2025

## **Worked on (last week):**
- Identified the issue with Splash
- Abandoned trying to compile more protocols
- Read Part of the [University of Auckland MESIF document](https://www.scss.tcd.ie/jeremy.jones/vivio/caches/Andrew%20Hay%20MESIF%20Cache%20Coherency%20Protocol%202012.pdf)
- Had a first look at the `.pcc` files
- Wrote my own (working!) gem5 `setup.py` based on the `setup_real.py`

## **Plan for next week (2 – 8 Jun 2025):**
- [x] Even more MESIF research
- [x] Understand `.pcc`
  - [ ] Ambitious write `MESIF.pcc`

---

## Week 3 · 2 – 8 Jun 2025

## **Worked on (last week):**
- Implemented part of `MESIF.pcc`
- Started work on the Project Proposal Presentation
 
## **Plan for next week (9 – 15 Jun 2025):**
- [x] More work on `MESIF.pcc`: Possibly get first version done
- [x] Finish Project Proposal Presentation + hold talk (Postponed)
- [ ] If time remains: Find some more alternate sources on MESIF / find related Papers
---

## Week 4 · 9 – 15 Jun 2025

## **Worked on (last week):**
- Finished Presentation
- Worked on `MESIF.pcc`

## **Plan for next week (16 – 22 Jun 2025):**
- [x] Fixup `MESIF.pcc` (fix weird compiler errors, possibly elimnate remaining deadlocks)
  - [ ] If done -> Start gathering data on MESIF (i.e. run Benchmarks)
- [x] Hold the presentation 
---

## Week 5 · 16 – 22 Jun 2025

## **Worked on (last week):**
- Held the presentation
- Fixed (all?) deadlocks of `MESIF.pcc`

## **Plan for next week (23 – 29 Jun 2025):**
- [x] Fix the weird haning of manually edited `MESIF.pcc`
- [x] Hopefully start gaterhing data 

---

## Week 6 · 23 – 29 Jun 2025

## **Worked on (last week):**
- `MESIF.pcc` mannually edited now working
- Got first pieces of data (phoenix on manualy edited)

## **Plan for next week (30 Jun – 6 Jul 2025):**
- [x] Get `MESIF.pcc` to match (as close as possible) to the manualy edited
- [ ] Run more benchmarks and compare with other protocols
- [ ] Get the bridge generation working and benchmark multi level


---

## Week 7 · 30 Jun – 6 Jul 2025

## **Worked on (last week):**
- Got `MESIF.pcc` close to the manual version
- Had a first look at `VIPER_TCC.sm`


## **Plan for next week (7 – 13 Jul 2025):**
- [ ] Improve `MESIF.pcc` performance, analyse performance
- [ ] Completly understand `VIPER_TCC.sm`
- [ ] Have a look at other `VIPER_*.sm` files
---

## Week 8 · 7 – 13 Jul 2025

## **Worked on (last week):**

## **Plan for next week (14 – 20 Jul 2025):**

---

## Week 9 · 14 – 20 Jul 2025

## **Worked on (last week):**

## **Plan for next week (21 – 27 Jul 2025):**

---

## Week 10 · 21 – 27 Jul 2025

## **Worked on (last week):**

## **Plan for next week (28 Jul – 3 Aug 2025):**

---

## Week 11 · 28 Jul – 3 Aug 2025

## **Worked on (last week):**

## **Plan for next week (4 – 10 Aug 2025):**

---

## Week 12 · 4 – 10 Aug 2025

## **Worked on (last week):**

## **Plan for next week (11 – 17 Aug 2025):**

---

## Week 13 · 11 – 17 Aug 2025

## **Worked on (last week):**

## **Plan for next week (18 – 24 Aug 2025):**

---

## Week 14 · 18 – 24 Aug 2025

## **Worked on (last week):**

## **Plan for next week (25 – 31 Aug 2025):**

---

## Week 15 · 25 – 31 Aug 2025

## **Worked on (last week):**

## **Plan for next week (1 – 7 Sep 2025):**

---

---

## Week 16 · 1 – 7 Sept 2025

## **Worked on (last week):**

## **Plan for next week (1 – 7 Sep 2025):**

---

