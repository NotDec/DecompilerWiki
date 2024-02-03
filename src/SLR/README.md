# A Systematic Literature Review of Decompilation

This page contains a systematic literature review of binary decompilation. For the introduction of SLR, [check here](intro.md).

## Background

The technique of decompilation still has significant limitations, as existing research on [lifter sok] and [fidelity issue] demonstrates. This indicates that there is still a lot of room for improvement in decompilers.

TODO

## Research Question


## Search Strategy

Keywords: Decompilation OR Decompiler OR Decompile

### Search Process

**Paper Repositories**: Important paper repositories covered in [findpapers](https://github.com/jonatasgrosman/findpapers): IEEE Xplore, ACM, Scopus, arXiv. Other important conference: Usenix, NDSS, DBLP.

Steps:

- Follow the usage of the tool [findpapers](https://github.com/jonatasgrosman/findpapers)
  - Apply for [access keys](https://github.com/cabrerac/semi-automatic-literature-survey?tab=readme-ov-file#requirements) for IEEE and scorpus.
  - using this command: (findpapers 0.6.7, 2024-02-03, [the generated json file can be downloaded here.](README/search.json))
    ```bash
    findpapers search ./search.json --token-ieee "$IEEE_TOKEN" --token-scopus "$SCOPUS_TOKEN" -q "[decompile] OR [decompiling] OR [decompiler] OR [decompilation]"
    ```



## Study Selection Criteria

- Language: English

