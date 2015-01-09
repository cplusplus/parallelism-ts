    Document Number: N4353
    Date:            2015-01-08
    Revises:
    Project:         Programming Language C++
    Project Number:  TS 19570
    Reply-to:        Jared Hoberock
                     NVIDIA Corporation
                     jhoberock@nvidia.com

# Parallelism TS Editor's Report, pre-DTS ballot 

N4352 is the latest Parallelism TS Working Draft. It contains editorial changes to the Parallelism TS as directed by an editing committee appointed during the Urbana meeting to approve the correctness of the Parallelism TS working paper.

N4352 updates the previous draft, N4310, published in the post-Urbana mailing.

N4354 is document N4352 reformatted as a DTS ballot document. It updates N4312, which was published in the post-Urbana mailing.

## Editorial Changes

1. A missing signature for `execution_policy::type` was added to the synopsis in Section 2.7.
2. A missing `ExecutionPolicy` overload signature for `for_each_n` was added to the synopsis in Section 4.3.1.
3. Missing `ExecutionPolicy` overload signatures for `reduce`, `exclusive_scan`, `inclusive_scan`, `transform_reduce`, `transform_exclusive_scan`, and `transform_inclusive_scan` were added to the synopsis in Section 4.4.1.

## Acknowledgements

Thanks to the review committee, who identified these issues.

* Hans Boehm
* Lawrence Crowl
* Alisdair Meredith

