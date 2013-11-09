sprintf
=======

sprintf for javascript

This is the sprintf helper for javascript like sprintf function in php.
And for some reason this helper only accept %s (string), %d (int) and %f (float) for now.

Because I don't need to handle more complicated cases so far.

Enjoy it.

# Examples #

1. all string
    `console.log(sprintf('%s,%s -> %s', 'Taipei', 'Taiwan', 'Wonderful island')); // Taipei,Taiwan -> Wonderful island`

2. String you given but pattern is integer format
    `console.log(sprintf('%d+%d=%d', 'A', 'B', 'C')); // 0+0=0`

3. Integer you given but pattern is string format
    `console.log(sprintf('%s+%s=%s', 1, 2, 3)); // 1+2=3`
