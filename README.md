    Document Number: N4506
    Date:            2015-05-05
    Revises:
    Project:         Programming Language C++
    Project Number:  TS 19570
    Reply-to:        Jared Hoberock
                     NVIDIA Corporation
                     jhoberock@nvidia.com

# Parallelism TS Editor's Report, post-Lenexa mailing 

N4505 is the latest Parallelism TS Working Draft. It contains editorial and technical changes to the Parallelism TS to apply the following revisions:

  * N4274 - Relaxing Packing Rules for Exceptions Thrown by Parallel Algorithms - Proposed Wording (Revision 1)
  * Feature test macro for the Parallelism TS

N4505 updates the previous draft, N4407, published in the pre-Lenexa mailing.

N4507 is document N4505 reformatted as a TS document. It updates N4409, which was published in the pre-Lenexa mailing.

## Technical Changes

* Applied N4274, which relaxes the exception packaging rules for exceptions thrown by parallel algorithms. Additionally, changed instances of "terminates with (exception)" phrasing to "exits via (exception)", as directed by the Library Working Group.

* Introduced the feature test macro `__cpp_lib_experimental_parallel_algorithm` for the functionality of the Parallelism TS as directed by SG1.

## Editorial Changes

* Promoted subsection 1.3.1, which was incorrectly grouped under section 1.3, to section 1.4.

