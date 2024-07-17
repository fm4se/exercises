# Exercises

This repository contains the exercises for the *Formal Methods for Software Engineering* course at the Bauhaus-Universität Weimar.
Each submodule contains a different exercise. The following Table lists the exercises, corresponding submodule, and the original repository.


| Exercise | Submodule | Description |
| --- | --- | --- |
| 1 | [fm4se-satsolving](https://github.com/se-buw/fm4se-satsolving) | formulas, checking conclusions, verifying Role-Based-Access |
| 2 | [fm4se-featuremodels](https://github.com/se-buw/fm4se-featuremodels) | Feature Model analysis, dead features, product preservation |
| 3 | [fm4se-smtsolving](https://github.com/se-buw/fm4se-smtsolving) | Agatha puzzle, math puzzle, PC configuration |
| 4 | [fm4se-java-smt-pc-config](https://github.com/se-buw/fm4se-java-smt-pc-config) | PC configuration from CSV-files, budget and purpose |
| 5 | [fm4se-alloy-solving](https://github.com/se-buw/fm4se-alloy-solving) | domain model, Agatha puzzle, Trash can |
| 6 | [fm4se-alloy-sigs-checker](https://github.com/se-buw/fm4se-alloy-sigs-checker) | Analysis of Alloy modules: dead signatures, minimal scopes |
| 7 | [fm4se-ltl-modelchecking](https://github.com/se-buw/fm4se-ltl-modelchecking) | LTL equivalence, counterexamples, chess knight moves |
| - | [fm4se-rbac](https://github.com/se-buw/fm4se-rbac) | Role-Based Access Control (RBAC) |
| - | [fm4se-alloy-christmas](https://github.com/se-buw/fm4se-alloy-christmas) | Wish list, Santa Claus, Placing Trees |



To work with an individual exercise, fork the corresponding submodule (find the original repository in the above table) repository and work on the exercise in your fork. 


To play with all the exercises, clone the repository and the submodule. To clone the repository with all submodules, use the following command:

```bash
git clone https://github.com/fm4se/exercises.git 
cd exercises
git submodule update --init --recursive
```

To update all submodules with latest changes, use the following command:

```bash
git submodule update --recursive --remote --merge
```