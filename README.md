Document Number: N4106
Date:            2014-07-04
Revises:
Project:         Programming Language C++
Project Number:  TS 19570
Reply-to:        Jared Hoberock
                 NVIDIA Corporation
                 jhoberock@nvidia.com

# Parallelism TS Editor's Report, post-Rapperswil

N4104 is the latest Parallelism TS Working Draft. It contains changes to the Parallelism TS as directed by the committee at the Rapperswil meeting.

N4104 updates the two previous drafts, N4071 (published during the Rapperswil meeting) and N3989 (published in the pre-Rappersil mailing).

Like N3960, N4106 is presented as a revision to N3960 since it incorporates the following technical changes created during the Rapperswil meeting.

N4105 is document N4104 reformatted as a PDTS ballot document.

## Technical Changes

* D4070 - Improving the specification of the vector execution policy in Parallelism TS
  * Clarify which standard library functions are unsafe to call during `parallel_vector_execution_policy` algorithm execution

* N4063 - On Parallel Invocations of Functions in Parallelism TS
  * Define *element access function*
  * Define parallel algorithm semantics in terms of invocations of *element access functions*
  * Prohibit `BinaryPredicate`, `Compare`, and `BinaryOperation` from modifying their arguments during parallel algorithm execution

* D4060 - Changes to `vector_execution_policy`
  * Rename `vector_execution_policy` to `parallel_vector_execution_policy`
  * Rename `vec` to `par_vec`

## Editorial Changes

Various

## Acknowledgements

* Hans Boehm
* Beman Dawes
* Pablo Halpern
* Artur Laksberg
* Daniel Krügler
* Alisdair Meredith
* Clark Nelson
* Herb Sutter
* Jeffrey Yasskin

