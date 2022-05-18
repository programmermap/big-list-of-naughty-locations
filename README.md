# Big list of naughty locations
The big list of naughty locations contains a list of strings that most likely do not describe actual locations.
Thus, they will most likely return wrong results, e.g. when geocoding.
As such, they can be used to filter user-generated input before actual geocoding.
Inspired by [big-list-of-naughty-strings](https://github.com/minimaxir/big-list-of-naughty-strings).

Categories so far include:
- unspecific locations, e.g. world, earth, or global
- null values, e.g. null, nil, n/a
- networking locations, e.g. localhost, 127.0.0.1, or ::1
- locations in space, e.g. milky way, mars, or sun
- other words for online, e.g. online, internet
- descibing platforms, e.g. twitter, facebook, or github
