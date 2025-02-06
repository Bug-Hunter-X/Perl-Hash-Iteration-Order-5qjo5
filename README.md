This example demonstrates a common issue in Perl where the order of iteration through a hash is undefined.  The output of the script may vary depending on the Perl interpreter and its internal hash implementation.  This can cause problems if the code depends on a particular order of elements.

The solution involves using a sorted list of keys.