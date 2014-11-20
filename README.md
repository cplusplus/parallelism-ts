    Document Number: N4311
    Date:            2014-11-21
    Revises:
    Project:         Programming Language C++
    Project Number:  TS 19570
    Reply-to:        Jared Hoberock
                     NVIDIA Corporation
                     jhoberock@nvidia.com

# Parallelism TS Editor's Report, post-Urbana

N4104 is the latest Parallelism TS Working Draft. It contains changes to the Parallelism TS as directed by the committee at the Urbana meeting.

N4310 updates the previous draft, N4104, published in the post-Rapperswil mailing.

N4312 is document N4310 reformatted as a DTS ballot document.

## Technical Changes

* N4275: Parallelism PDTS Comment Reponses

  * CH1: Resurrect explicit permission for implementation-defined execution policies
  
    Resolution: implemented as a non-normative note in S 2.3 p2.

  * DE1 & US4: Consider N4167 (`transform_reduce`)
  
    Resolution: N4311 adds the algorithms `transform_reduce`, `transform_exclusive_scan`, and `transform_inclusive_scan`.

  * US1: Execution policy definition

    Resolution: S 2.1 p1 refines the defintion of "execution policy".

  * US3: Elemental access functions can interrupt user code:

    Resolution: S 4.1.2 p3 refines the specification of which threads a parallel algorithm invocation may use.

## Editorial Changes

Various typographical errors eliminated.

## Acknowledgements

* Hans Boehm
* Agustín Bergé
* Hartmut Kaiser

