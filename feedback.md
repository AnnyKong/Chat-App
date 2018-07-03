# Project 2 (uMessage) Feedback #
## CSE 332 Autumn 2017 ##

**Team:** Xinrong Zhao (zhaox29) and Anny Kong (yk57) <br />
**Graded By:** Kathryn Howland (khow89@cs.washington.edu)
<br>

## Unit Tests ##

**AVLTree**  `(6/6)`
> ✓ Passed *initialize* <br>
> ✓ Passed *insert* <br>
> ✓ Passed *getters* <br>
> ✓ Passed *sorted_duplicate_input* <br>
> ✓ Passed *unsorted_duplicate_input* <br>
> ✓ Passed *structure* <br>

**MoveToFrontList**  `(6/6)`
> ✓ Passed *initialize* <br>
> ✓ Passed *insert* <br>
> ✓ Passed *getters* <br>
> ✓ Passed *sorted_duplicate_input* <br>
> ✓ Passed *unsorted_duplicate_input* <br>
> ✓ Passed *structure* <br>

**HashTable**  `(6/6)`
> ✓ Passed *initialize* <br>
> ✓ Passed *insert* <br>
> ✓ Passed *getters* <br>
> ✓ Passed *sorted_duplicate_input* <br>
> ✓ Passed *unsorted_duplicate_input* <br>
> ✓ Passed *comparator* <br>
> ✓ Passed *negative_hash_codes* <br>

**HeapSort**  `(5/5)`
> ✓ Passed *integer_inorder* <br>
> ✓ Passed *integer_reverseorder* <br>
> ✓ Passed *integer_interleaved* <br>
> ✓ Passed *integer_random* <br>
> ✓ Passed *string* <br>
> ✓ Passed *dataCount_string* <br>

**QuickSort**  `(5/5)`
> ✓ Passed *integer_inorder* <br>
> ✓ Passed *integer_reverseorder* <br>
> ✓ Passed *integer_interleaved* <br>
> ✓ Passed *integer_random* <br>
> ✓ Passed *string* <br>
> ✓ Passed *dataCount_string* <br>

**TopKSort**  `(6/6)`
> ✓ Passed *integer_random_100* <br>
> ✓ Passed *string_20* <br>
> ✓ Passed *dataCount_ngram_counts_inorder* <br>
> ✓ Passed *dataCount_ngram_counts_reverseorder* <br>
> ✓ Passed *dataCount_ngram_counts_interleaved* <br>
> ✓ Passed *dataCount_ngram_counts_random* <br>

**CircularArrayHashCode**  `(1/2)`
> ✓ Passed *generate_hash_codes* <br>
> ✓ Passed *hash_overlap* <br>
> ✓ Passed *high_variance* <br>
> `✘ Failed` *with_null_chars* <br>

**CircularArrayComparator**  `(2/2)`
> ✓ Passed *vary_length* <br>
> ✓ Passed *vary_order* <br>

**NGramToNextChoicesMap** ∞ Timeout `(1/2)`
> ✓ Passed *poem* <br>
> `∞ Timeout` *large* <br>
> `` *15000ms* <br>

**UMessage**  `(6/6)`
> ✓ Passed *simple_HashTable_AVL* <br>
> ✓ Passed *simple_HashTable_HashTable* <br>
> ✓ Passed *simple_HashTable_AVL_topk* <br>
> ✓ Passed *simple_HashTable_HashTable_topk* <br>
> ✓ Passed *poem_HashTable_AVL* <br>
> ✓ Passed *poem_HashTable_HashTable* <br>
> ✓ Passed *poem_HashTable_MTF* <br>
> ✓ Passed *poem_HashTable_AVL_topk* <br>
> ✓ Passed *poem_HashTable_HashTable_topk* <br>
> ✓ Passed *poem_HashTable_MTF_topk* <br>
> ✓ Passed *large_HashTable_AVL_topk* <br>
> ✓ Passed *large_HashTable_HashTable_topk* <br>

## Miscellaneous ##













(-0) As a note, with graphs like these where your data is actually
scattered points, it best to use dots on the graph, though if 
you then want to connect the dots with lines for clarity of 
asymptotic analysis, that's fine.

## Write-Up ##

**Project Enjoyment**
`(3/3)`

**BST vs. AVLTree**
`(4/4)`

**ChainingHashTable**
`(3/3)`

Very interesting point on the comparability of keys!

**Hash Functions**
`(2/3)`

It's not immediately clear from your description or your experiment
code what kind of input you used for this experiment.

**General Purpose Dictionary**
`(3/3)`

(-0) In your conclusion, you state that the differences are never
more than 0.3 ms, but according to your data, they differ by hundreds
of ms. Did you mean seconds? Be sure to proofread!

(-0) It would have been better to do an asymptotic
analysis by varying the size of the input.

**uMessage**
`(3/3)`

**Above & Beyond**
`(EX: 0)`

