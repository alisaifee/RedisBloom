Returns information about a cuckoo filter.

## Required arguments

<details open><summary><code>key</code></summary>

is key name for a cuckoo filter.
</details>

## Return value

Either

- @array-reply with information about the filter.
- @error-reply on error (invalid arguments, key not exist, wrong key type, etc.)


## Examples

{{< highlight bash >}}
redis> CF.INFO cf
 1) Size
 2) (integer) 1080
 3) Number of buckets
 4) (integer) 512
 5) Number of filter
 6) (integer) 1
 7) Number of items inserted
 8) (integer) 0
 9) Number of items deleted
10) (integer) 0
11) Bucket size
12) (integer) 2
13) Expansion rate
14) (integer) 1
15) Max iteration
16) (integer) 20
{{< / highlight >}}
